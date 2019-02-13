## .htaccess Snippets [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
一组有用的.htaccess片段，全部集中在一个地方.

 **注意**：`.htaccess`文件适用于无权编辑主服务器配置文件的人.  它们本质上比使用主配置更慢，更复杂.  请看看 [howto in the httpd documentation](https://httpd.apache.org/docs/current/howto/htaccess.html) 了解更多详情.

 **免责声明**：虽然将片段放入`.htaccess`文件大部分时间都足够了，但有些情况下可能需要进行某些修改.  使用风险由您自己承担.

 **重要**：Apache 2.4引入了一些重大更改，尤其是访问控制配置.  有关更多信息，请查看 [upgrading document](https://httpd.apache.org/docs/2.4/upgrading.html) 以及 [this issue](https://github.com/phanan/htaccess/issues/2).

## Credits
我们在这里做的主要是从各个网站收集有用的片段（例如，一个很好的块来自 [Apache Server Configs](https://github.com/h5bp/server-configs-apache) ）到一个地方.  虽然我们一直试图归于应有的地方，但事情可能会失踪.  如果您认为这里的任何内容都是您的工作并且应该给予积分，请告诉我们，或者只是发送PR.

## Table of Contents
- [Rewrite and Redirection](#rewrite-and-redirection)
    - [Force www](#force-www)
    - [Force www in a Generic Way](#force-www-in-a-generic-way)
    - [Force non-www](#force-non-www)
    - [Force non-www in a Generic Way](#force-non-www-in-a-generic-way)
    - [Force HTTPS](#force-https)
    - [Force HTTPS Behind a Proxy](#force-https-behind-a-proxy)
    - [Force Trailing Slash](#force-trailing-slash)
    - [Remove Trailing Slash](#remove-trailing-slash)
    - [Redirect a Single Page](#redirect-a-single-page)
    - [Redirect Using RedirectMatch](#redirect-using-redirectmatch)
    - [Alias a Single Directory](#alias-a-single-directory)
    - [Alias Paths to Script](#alias-paths-to-script)
    - [Redirect an Entire Site](#redirect-an-entire-site)
    - [Alias "Clean" URLs](#alias-clean-urls)
    - [Exclude a URL from Redirection](#exclude-url-from-redirection)
- [Security](#security)
    - [Deny All Access](#deny-all-access)
    - [Deny All Access Except Yours](#deny-all-access-except-yours)
    - [Allow All Access Except Spammers'](#allow-all-access-except-spammers)
    - [Deny Access to Hidden Files and Directories](#deny-access-to-hidden-files-and-directories)
    - [Deny Access to Backup and Source Files](#deny-access-to-backup-and-source-files)
    - [Disable Directory Browsing](#disable-directory-browsing)
    - [Disable Image Hotlinking](#disable-image-hotlinking)
    - [Disable Image Hotlinking for Specific Domains](#disable-image-hotlinking-for-specific-domains)
    - [Password Protect a Directory](#password-protect-a-directory)
    - [Password Protect a File or Several Files](#password-protect-a-file-or-several-files)
    - [Block Visitors by Referrer](#block-visitors-by-referrer)
    - [Prevent Framing the Site](#prevent-framing-the-site)
- [Performance](#performance)
    - [Compress Text Files](#compress-text-files)
    - [Set Expires Headers](#set-expires-headers)
    - [Turn eTags Off](#turn-etags-off)
- [Miscellaneous](#miscellaneous)
    - [Set PHP Variables](#set-php-variables)
    - [Custom Error Pages](#custom-error-pages)
    - [Force Downloading](#force-downloading)
    - [Prevent Downloading](#prevent-downloading)
    - [Allow Cross-Domain Fonts](#allow-cross-domain-fonts)
    - [Auto UTF-8 Encode](#auto-utf-8-encode)
    - [Switch to Another PHP Version](#switch-to-another-php-version)
    - [Disable Internet Explorer Compatibility View](#disable-internet-explorer-compatibility-view)
    - [Serve WebP Images](#serve-webp-images)

## Rewrite and Redirection
注意：假设您已安装并启用了“mod_rewrite”.

### Force www
```apacheconf
RewriteEngine on
RewriteCond％{HTTP_HOST} ^ example \ .com [NC]
RewriteRule ^（.*）$ http://www.example.com/$1 [L，R = 301，NC]
```

### Force www in a Generic Way
```apacheconf
RewriteCond％{HTTP_HOST}！^ $
 RewriteCond％{HTTP_HOST}！^ www \.  [NC]
RewriteCond％{HTTPS} s ^ on（s）|
RewriteRule ^ http％1：//www.% {HTTP_HOST}％{REQUEST_URI} [R = 301，L]
```
这适用于_any_域. [Source](https://stackoverflow.com/questions/4916222/htaccess-how-to-force-www-in-a-generic-way)

### Force non-www
It’s [still](http://www.sitepoint.com/domain-www-or-no-www/) [open](https://devcenter.heroku.com/articles/apex-domains) [for](http://yes-www.org/) [debate](http://no-www.org/) 无论是www还是非www都是要走的路，所以如果你碰巧是裸域的粉丝，那么你去：
```apacheconf
RewriteEngine on
RewriteCond％{HTTP_HOST} ^ www \ .example \ .com [NC]
RewriteRule ^（.*）$ http://example.com/$1 [L，R = 301]
```

### Force non-www in a Generic Way
```apacheconf
RewriteEngine on
RewriteCond％{HTTP_HOST} ^ www \.
RewriteCond％{HTTPS} s ^ on（s）| off
RewriteCond http％1：//％{HTTP_HOST} ^（https？：//）（www \.）？（.+）$
RewriteRule ^％1％3％{REQUEST_URI} [R = 301，L]
```

### Force HTTPS
```apacheconf
RewriteEngine on
RewriteCond％{HTTPS}！on
RewriteRule（.*）https：//％{HTTP_HOST}％{REQUEST_URI}

## Note: It’s also recommended to enable HTTP Strict Transport Security (HSTS)
## on your HTTPS website to help prevent man-in-the-middle attacks.
## See https://developer.mozilla.org/en-US/docs/Web/Security/HTTP_strict_transport_security
<IfModule mod_headers.c>
    # 如果您不想在所有子域上强制执行HSTS，请删除“includeSubDomains”
    标题始终设置Strict-Transport-Security“max-age = 31536000; includeSubDomains”
</IfModule>
```

### Force HTTPS Behind a Proxy
如果您的服务器前面有代理执行TLS终止，则非常有用.
```apacheconf
RewriteCond％{HTTP：X-Forwarded-Proto}！https
RewriteRule（.*）https：//％{HTTP_HOST}％{REQUEST_URI}
```

### Force Trailing Slash
```apacheconf
RewriteCond％{REQUEST_URI} /+ [^\.]+$
RewriteRule ^（.+ [^ /]）$％{REQUEST_URI} / [R = 301，L]
```

### Remove Trailing Slash
 这个片段将以斜杠结尾的路径重定向到非斜线终止的对应物（实际目录除外），例如`http：// www.example.com / blog /`到`http://www.example.com/ blog`.  对于SEO来说这很重要，因为它是 [recommended](http://overit.com/blog/canonical-urls) 为每个页面都有一个规范的URL.
```apacheconf
RewriteCond％{REQUEST_FILENAME}！-d
RewriteCond％{REQUEST_URI}（.+）/ $
RewriteRule ^％1 [R = 301，L]
```
[Source](https://stackoverflow.com/questions/21417263/htaccess-add-remove-trailing-slash-from-url#27264788)

### Redirect a Single Page
```apacheconf
重定向301 /oldpage.html http://www.example.com/newpage.html
重定向301 /oldpage2.html http://www.example.com/folder/
```
[Source](http://css-tricks.com/snippets/htaccess/301-redirects/)

### Redirect Using RedirectMatch
```apacheconf
RedirectMatch 301 /subdirectory(.*)http://www.newsite.com/newfolder/$1
RedirectMatch 301 ^ /（.*）.htm $ /$1.html
RedirectMatch 301 ^ / 200（[0-9]）/（[^ 01]）（.*）$ / $ 2 $ 3
RedirectMatch 301 ^ / category /(.*)$ / $ 1
RedirectMatch 301 ^ /（.*）/ htaccesselite-ultimate-htaccess-article.html（.*）/ htaccess / htaccess.html
RedirectMatch 301 ^ /（.*）.html / 1 /(.*)/$1.html$2
RedirectMatch 301 ^ / manual /(.*)$ http://www.php.net/manual/$1
RedirectMatch 301 ^ / dreamweaver /(.*)$ / tools / $ 1
RedirectMatch 301 ^ / z /(.*)$ http://static.askapache.com/$1
```
[Source](http://www.askapache.com/htaccess/301-redirect-with-mod_rewrite-or-redirectmatch.html#301_Redirects_RedirectMatch)

### Alias a Single Directory
```apacheconf
RewriteEngine On
RewriteRule ^ source-directory /(.*）/ target-directory / $ 1 [R = 301，L]
```

### Alias Paths to Script
```apacheconf
FallbackResource /index.fcgi
```
 此示例在某个目录中有一个`index.fcgi`文件，该目录中未能解析文件名/目录的任何请求都将被发送到`index.fcgi`脚本.  如果你希望`baz.foo / some / path`由`baz.foo / index.fcgi`（也支持对`baz.foo`的请求）处理，同时保持`baz.foo/css/，那就太好了. style.css`等.  从PATH_INFO环境变量访问原始路径，这将暴露给您的脚本环境.

```apacheconf
RewriteEngine On
RewriteRule ^ $ index.fcgi / [QSA，L]
RewriteCond％{REQUEST_FILENAME}！ -  f
RewriteCond％{REQUEST_FILENAME}！-d
RewriteRule ^（.*）$ index.fcgi / $ 1 [QSA，L]
```
这是一个效率较低的FallbackResource指令版本（因为使用`mod_rewrite`比处理`FallbackResource`指令更复杂），但它也更灵活.

### Redirect an Entire Site
```apacheconf
重定向301 / http://newsite.com/
```
 这种方式与链接完好无损.  那就是`www.oldsite.com / some / crazy / link.html`将成为`www.newsite.com / some / crazy / link.html`.  当您将网站“移动”到新域时，这非常有用. [Source](http://css-tricks.com/snippets/htaccess/301-redirects/)

### Alias “Clean” URLs
此代码段允许您使用“干净”的URL  - 没有PHP扩展名的URL，例如`example.com / users`而不是`example.com / users.php`.
```apacheconf
RewriteEngine On
RewriteCond％{SCRIPT_FILENAME}！-d
RewriteRule ^（[^.] +）$ $ 1.php [NC，L]
```
[Source](http://www.abeautifulsite.net/access-pages-without-the-php-extension-using-htaccess/)

### Exclude URL from Redirection
 此代码段允许您从重定向中排除URL.  例如，如果您有重定向规则设置但想要排除robots.txt，那么搜索引擎可以按预期访问该URL.
```apacheconf
RewriteEngine On
RewriteRule ^ robots.txt  -  [L]
```

## Security
### Deny All Access
```apacheconf
## Apache 2.2
拒绝所有人

## Apache 2.4
## Require all denied
```

 但是等等，这也会阻止你的内容！  因此介绍......

### Deny All Access Except Yours
```apacheconf
## Apache 2.2
命令拒绝，允许
拒绝所有人
允许来自xxx.xxx.xxx.xxx

## Apache 2.4
## Require all denied
## Require ip xxx.xxx.xxx.xxx
```
 `xxx.xxx.xxx.xxx`是你的IP.  例如，如果用“0/12”替换最后三位数字，这将指定同一网络中的一系列IP，从而省去了单独列出所有允许的IP的麻烦. [Source](http://speckyboy.com/2013/01/08/useful-htaccess-snippets-and-hacks/)

现在当然有一个反转版本：

### Allow All Access Except Spammers'
```apacheconf
## Apache 2.2
命令拒绝，允许
从xxx.xxx.xxx.xxx拒绝
拒绝来自xxx.xxx.xxx.xxy

## Apache 2.4
## Require all granted
## Require not ip xxx.xxx.xxx.xxx
## Require not ip xxx.xxx.xxx.xxy
```

### Deny Access to Hidden Files and Directories
 隐藏文件和目录（名称以点`.`开头的那些文件和目录）应该保护大部分时间（如果不是全部的话）.  例如：`.htaccess`，`.htpasswd`，`.git`，`.hg` ...
```apacheconf
RewriteCond％{SCRIPT_FILENAME} -d [OR]
RewriteCond％{SCRIPT_FILENAME} -f
 RewriteRule“（^ | /）\.”  - [F]
```

或者，你可以提出一个“未找到”错误，给攻击者毫无头绪：
```apacheconf
RedirectMatch 404 /\..*$
```

### Deny Access to Backup and Source Files
这些文件可能会被某些文本/ HTML编辑器（如Vi / Vim）留下，如果暴露给公众，会造成很大的安全隐患.
```apacheconf
<FilesMatch "(\.(bak|config|dist|fla|inc|ini|log|psd|sh|sql|swp)|~)$">
    ## Apache 2.2
    订单允许，拒绝
    拒绝所有人
    满足所有

    ## Apache 2.4
    # 要求全部拒绝
</FilesMatch>
```
[Source](https://github.com/h5bp/server-configs-apache)

### Disable Directory Browsing
```apacheconf
选项全部 - 索引
```

### Disable Image Hotlinking
```apacheconf
RewriteEngine on
## Remove the following line if you want to block blank referrer too
RewriteCond％{HTTP_REFERER}！^ $

RewriteCond％{HTTP_REFERER}！^ https？：//（.+ \.）？example.com [NC]
RewriteRule \.（jpe？g | png | gif | bmp）$  -  [NC，F，L]

## If you want to display a “blocked” banner in place of the hotlinked image,
## replace the above rule with:
## RewriteRule \.(jpe?g|png|gif|bmp) http://example.com/blocked.png [R,L]
```

### Disable Image Hotlinking for Specific Domains
有时您只想禁用某些坏人的图像热链接.
```apacheconf
RewriteEngine on
RewriteCond％{HTTP_REFERER} ^ https？：//（.+ \.）？badsite \ .com [NC，OR]
RewriteCond％{HTTP_REFERER} ^ https？：//（.+ \.）？badsite2 \ .com [NC，OR]
RewriteRule \.（jpe？g | png | gif | bmp）$  -  [NC，F，L]

## If you want to display a “blocked” banner in place of the hotlinked image,
## replace the above rule with:
## RewriteRule \.(jpe?g|png|gif|bmp) http://example.com/blocked.png [R,L]
```

### Password Protect a Directory
首先，您需要在系统中的某处创建一个`.htpasswd`文件：
```bash
htpasswd -c /home/fellowship/.htpasswd boromir
```

然后您可以使用它进行身份验证：
```apacheconf
AuthType Basic
AuthName“一个不简​​单”
AuthUserFile /home/fellowship/.htpasswd
需要有效用户
```

### Password Protect a File or Several Files
```apacheconf
AuthName“一个仍然不简单”
AuthType Basic
AuthUserFile /home/fellowship/.htpasswd

<Files "one-ring.o">
需要有效用户
</Files>

<FilesMatch ^((one|two|three)-rings?\.o)$>
需要有效用户
</FilesMatch>
```

### Block Visitors by Referrer
这会拒绝所有来自（引用）特定域的用户的访问权限.
[Source](http://www.htaccess-guide.com/deny-visitors-by-referrer/)
```apacheconf
RewriteEngine on
## Options +FollowSymlinks
RewriteCond％{HTTP_REFERER} somedomain \ .com [NC，OR]
RewriteCond％{HTTP_REFERER} anotherdomain \ .com
RewriteRule.*  -  [F]
```

### Prevent Framing the Site
当仍允许为特定URI构建框架时，这可以防止网站被框起（即放入“iframe”标签）.
```apacheconf
SetEnvIf Request_URI“/ starry-night”allow_framing = true
标题设置X-Frame-Options SAMEORIGIN env =！allow_framing
```

## Performance
### Compress Text Files
```apacheconf
<IfModule mod_deflate.c>

    # 对受损标头强制压缩.
    # https://developer.yahoo.com/blogs/ydn/pushing-beyond-gzipping-25601.html
    <IfModule mod_setenvif.c>
        <IfModule mod_headers.c>
            SetEnvIfNoCase ^（Accept-EncodXng | X-cept-Encoding | X {15} |〜{15} |  -  {15}）$ ^（（gzip | deflate）\ s *，？\ s *）+ | [X~ - ] {4,13} $ HAVE_Accept-Encoding
            RequestHeader附加Accept-Encoding“gzip，deflate”env = HAVE_Accept-Encoding
        </IfModule>
    </IfModule>

    # 压缩标记有以下MIME类型之一的所有输出
    # （对于2.3.7以下的Apache版本，您不需要启用`mod_filter`
    #   并可以删除` <IfModule mod_filter.c>  `和` </IfModule>  `线
    #  as `AddOutputFilterByType` is still in the core directives).
    <IfModule mod_filter.c>
        AddOutputFilterByType DEFLATE application / atom + xml \
                                      应用程序/ javascript \
                                      申请/ json \
                                      application / rss + xml \
                                      application / vnd.ms-fontobject \
                                      application / x-font-ttf \
                                      application / x-web-app-manifest + json \
                                      application / xhtml + xml \
                                      application / xml \
                                      font / opentype \
                                      image / svg + xml \
                                      图像/ x图标
                                      文字/ css \
                                      文字/ html \
                                      文字/简单\
                                      text / x-component \
                                      文/ XML
    </IfModule>

</IfModule>
```
[Source](https://github.com/h5bp/server-configs-apache)


### Set Expires Headers
 _Expires headers_告诉浏览器他们是应该从服务器请求特定文件还是从缓存中获取它.  建议将静态内容的expires头设置为将来的某些内容.

如果您不使用基于文件名的缓存清除来控制版本控制，请考虑将CSS和JS等资源的缓存时间缩短到1周. [Source](https://github.com/h5bp/server-configs-apache)
```apacheconf
<IfModule mod_expires.c>
    ExpiresActive on
    ExpiresDefault“访问加1个月”

  # CSS
    ExpiresByType text / css“access plus 1 year”

  # 数据交换
    ExpiresByType应用程序/ json“访问加0秒”
    ExpiresByType application / xml“access plus 0 seconds”
    ExpiresByType text / xml“access plus 0 seconds”

  # Favicon（无法重命名！）
    ExpiresByType image / x-icon“访问加1周”

  # HTML组件（HTC）
    ExpiresByType text / x-component“access plus 1 month”

  # HTML
    ExpiresByType text / html“access plus 0 seconds”

  # JavaScript
    ExpiresByType应用程序/ javascript“访问加1年”

  # 清单文件
    ExpiresByType application/x-web-app-manifest+json   "access plus 0 seconds"
    ExpiresByType text / cache-manifest“access plus 0 seconds”

  # 媒体
    ExpiresByType音频/ ogg“访问加1个月”
    ExpiresByType image / gif“access plus 1 month”
    ExpiresByType image / jpeg“access plus 1 month”
    ExpiresByType image / png“access plus 1 month”
    ExpiresByType视频/ mp4“访问加1个月”
    ExpiresByType视频/ ogg“访问加1个月”
    ExpiresByType视频/ webm“访问加1个月”

  # 网络订阅源
    ExpiresByType应用程序/ atom + xml“访问加1小时”
    ExpiresByType应用程序/ rss + xml“访问加1小时”

  # Web字体
    ExpiresByType应用程序/ font-woff2“访问加1个月”
    ExpiresByType应用程序/ font-woff“访问加1个月”
    ExpiresByType application / vnd.ms-fontobject“access plus 1 month”
    ExpiresByType application / x-font-ttf“access plus 1 month”
    ExpiresByType字体/ opentype“访问加1个月”
    ExpiresByType image / svg + xml“access plus 1 month”
</IfModule>
```

### Turn eTags Off
通过删除`ETag`标头，您可以禁用缓存和浏览器来验证文件，因此它们被迫依赖于您的`Cache-Control`和`Expires`标头. [Source](http://www.askapache.com/htaccess/apache-speed-etags.html)
```apacheconf
<IfModule mod_headers.c>
    标题未设置ETag
</IfModule>
FileETag无
```

## Miscellaneous

### Set PHP Variables
```apacheconf
php_value <key><val>

## For example:
php_value upload_max_filesize 50M
php_value max_execution_time 240
```

### Custom Error Pages
```apacheconf
ErrorDocument 500“休斯顿，我们遇到了问题.”
ErrorDocument 401 http://error.example.com/mordor.html
ErrorDocument 404 /errors/halflife3.html
```

### Force Downloading
有时您想强制浏览器下载某些内容而不是显示它.
```apacheconf
<Files *.md>
    ForceType应用程序/八位字节流
    标题设置内容处理附件
</Files>
```

现在这个阴有一个阳：

### Prevent Downloading
有时您希望强制浏览器显示某些内容而不是下载它.
```apacheconf
<FilesMatch "\.(tex|log|aux)$">
    标题集设置Content-Type text / plain
</FilesMatch>
```

### Allow Cross-Domain Fonts
CDN服务的webfonts可能无法在Firefox或IE中使用 [CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing) .  这个片段解决了这个问题.
```apacheconf
<IfModule mod_headers.c>
    <FilesMatch "\.(eot|otf|ttc|ttf|woff|woff2)$">
        标题集Access-Control-Allow-Origin“*”
    </FilesMatch>
</IfModule>
```
[Source](https://github.com/h5bp/server-configs-apache/issues/32)

### Auto UTF-8 Encode
您的文本内容应始终采用UTF-8编码，不是吗？
```apacheconf
## Use UTF-8 encoding for anything served text/plain or text/html
AddDefaultCharset utf-8

## Force UTF-8 for a number of file formats
AddCharset utf-8 .atom .css .js .json .rss .vtt .xml
```
[Source](https://github.com/h5bp/server-configs-apache)

### Switch to Another PHP Version
 如果您在共享主机上，则可能安装了多个版本的PHP，有时您需要特定版本的网站.  以下代码段应该为您切换PHP版本.

```apacheconf
AddHandler应用程序/ x-httpd-php56 .php

## Alternatively, you can use AddType
AddType application / x-httpd-php56 .php
```

### Disable Internet Explorer Compatibility View
 IE中的兼容性视图可能会影响某些网站的显示方式.  以下代码段应强制IE使用边缘渲染引擎并禁用兼容性视图.

```apacheconf
<IfModule mod_headers.c>
    BrowserMatch MSIE是-msie
    标头设置X-UA兼容IE =边缘env = is-msie
</IfModule>
```

### Serve WebP Images
If [WebP images](https://developers.google.com/speed/webp/?csw=1) 支持并且在与要提供的jpg / png图像相同的位置找到扩展名为.webp且名称相同的图像，然后提供WebP图像.

```apacheconf
RewriteEngine On
RewriteCond％{HTTP_ACCEPT} image / webp
RewriteCond％{DOCUMENT_ROOT} / $ 1.webp -f
RewriteRule（.+）\.（jpe？g | png）$ $ 1.webp [T = image / webp，E = accept：1]
```
[Source](https://github.com/vincentorback/WebP-images-with-htaccess)
