<div class="github-widget" data-repo="phanan/htaccess"></div>
## .htaccess Snippets [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
一组有用的 .htaccess 片段，全部集中在一个地方.

 **注意**：`.htaccess` 文件供无权编辑主服务器配置文件的人员使用. 它们本质上比使用主配置更慢、更复杂. 请参阅 [howto in the httpd documentation](https://httpd.apache.org/docs/current/howto/htaccess.html) 了解更多详情.

 **免责声明**：虽然在大多数情况下将代码片段放入 .htaccess 文件就足够了，但在某些情况下可能需要进行某些修改. 使用风险自负.

 **重要提示**：Apache 2.4 引入了一些重大更改，最显着的是访问控制配置. 有关详细信息，请查看 [upgrading document](https://httpd.apache.org/docs/2.4/upgrading.html) 也 [this issue](https://github.com/phanan/htaccess/issues/2).

## Credits
我们在这里所做的主要是从整个互联网上收集有用的片段（例如，一个很好的块来自 [Apache Server Configs](https://github.com/h5bp/server-configs-apache) ) 到一个地方. 虽然我们一直在尝试在到期时归功，但可能会遗漏一些东西. 如果你认为这里有任何东西是你的工作并且应该给予学分，请告诉我们，或者只是发送 PR.


## Rewrite and Redirection
注意：假设您已经安装并启用了 `mod_rewrite`.

### Force www
```apacheconf
重写引擎开启
RewriteCond %{HTTP_HOST} ^example\.com [NC]
重写规则 ^(.*)$ http://www.example.com/$1 [L,R=301,NC]
```

### Force www in a Generic Way
```apacheconf
RewriteCond %{HTTP_HOST} !^$
 RewriteCond %{HTTP_HOST} !^www\.  [数控]
RewriteCond %{HTTPS}s ^on(s)|
重写规则 ^ http%1://www.%{HTTP_HOST}%{REQUEST_URI} [R=301,L]
```
这适用于_any_ 域. [Source](https://stackoverflow.com/questions/4916222/htaccess-how-to-force-www-in-a-generic-way)

### Force non-www
It’s [still](http://www.sitepoint.com/domain-www-or-no-www/) [open](https://devcenter.heroku.com/articles/apex-domains) [for](http://yes-www.org/) [debate](http://no-www.org/) 无论 www 还是非 www 都是要走的路，所以如果您碰巧是裸域的粉丝，请看这里：
```apacheconf
重写引擎开启
RewriteCond %{HTTP_HOST} ^www\.example\.com [NC]
重写规则 ^(.*)$ http://example.com/$1 [L,R=301]
```

### Force non-www in a Generic Way
```apacheconf
重写引擎开启
RewriteCond %{HTTP_HOST} ^www\.
RewriteCond %{HTTPS}s ^on(s)|off
RewriteCond http%1://%{HTTP_HOST} ^(https?://)(www\.)?(.+)$
重写规则 ^ %1%3%{REQUEST_URI} [R=301,L]
```

### Force HTTPS
```apacheconf
重写引擎开启
RewriteCond %{HTTPS} !on
重写规则 (.*) https://%{HTTP_HOST}%{REQUEST_URI}

## Note: It’s also recommended to enable HTTP Strict Transport Security (HSTS)
## on your HTTPS website to help prevent man-in-the-middle attacks.
## See https://developer.mozilla.org/en-US/docs/Web/Security/HTTP_strict_transport_security
<IfModule mod_headers.c>
    #如果您不想在所有子域上强制执行 HSTS，请删除“includeSubDomains”
    标头始终设置 Strict-Transport-Security &quot;max-age=31536000;includeSubDomains&quot;
</IfModule>
```

### Force HTTPS Behind a Proxy
如果您的服务器前面有代理执行 TLS 终止，则很有用.
```apacheconf
RewriteCond %{HTTP:X-Forwarded-Proto} !https
重写规则 (.*) https://%{HTTP_HOST}%{REQUEST_URI}
```

### Force Trailing Slash
```apacheconf
RewriteCond %{REQUEST_URI} /+[^\.]+$
重写规则 ^(.+[^/])$ %{REQUEST_URI}/ [R=301,L]
```

### Remove Trailing Slash
此代码段会将以斜杠结尾的路径重定向到非斜杠结尾的对应路径（实际目录除外），例如，将“http://www.example.com/blog/”重定向到“http://www.example.com/”博客`. 这对 SEO 很重要，因为它 [recommended](http://overit.com/blog/canonical-urls) 每个页面都有一个规范的 URL.
```apacheconf
RewriteCond %{REQUEST_FILENAME} !-d
RewriteCond %{REQUEST_URI} (.+)/$
重写规则 ^ %1 [R=301,L]
```
[Source](https://stackoverflow.com/questions/21417263/htaccess-add-remove-trailing-slash-from-url#27264788)

### Redirect a Single Page
```apacheconf
重定向 301 /oldpage.html http://www.example.com/newpage.html
重定向 301 /oldpage2.html http://www.example.com/folder/
```
[Source](http://css-tricks.com/snippets/htaccess/301-redirects/)

### Redirect Using RedirectMatch
```apacheconf
RedirectMatch 301 /子目录(.*) http://www.newsite.com/newfolder/$1
RedirectMatch 301 ^/(.*).htm$ /$1.html
RedirectMatch 301 ^/200([0-9])/([^01])(.*)$ /$2$3
RedirectMatch 301 ^/类别/(.*)$ /$1
RedirectMatch 301 ^/(.*)/htaccesselite-ultimate-htaccess-article.html(.*) /htaccess/htaccess.html
RedirectMatch 301 ^/(.*).html/1/(.*) /$1.html$2
RedirectMatch 301 ^/手册/(.*)$ http://www.php.net/manual/$1
RedirectMatch 301 ^/dreamweaver/(.*)$ /tools/$1
RedirectMatch 301 ^/z/(.*)$ http://static.askapache.com/$1
```
[Source](http://www.askapache.com/htaccess/301-redirect-with-mod_rewrite-or-redirectmatch.html#301_Redirects_RedirectMatch)

### Alias a Single Directory
```apacheconf
重写引擎开启
RewriteRule ^源目录/(.*) /目标目录/$1 [R=301,L]
```

### Alias Paths to Script
```apacheconf
FallbackResource /index.fcgi
```
此示例在某个目录中有一个 index.fcgi 文件，该目录中无法解析文件名/目录的任何请求都将发送到 index.fcgi 脚本. 如果您希望在维护 `baz.foo/css/ style.css` 之类的. 从 PATH_INFO 环境变量获取对暴露给脚本环境的原始路径的访问权.

```apacheconf
重写引擎开启
重写规则 ^$ index.fcgi/ [QSA,L]
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
重写规则 ^(.*)$ index.fcgi/$1 [QSA,L]
```
这是 FallbackResource 指令的一个低效版本（因为使用 `mod_rewrite` 比仅仅处理 `FallbackResource` 指令更复杂），但它也更灵活.

### Redirect an Entire Site
```apacheconf
重定向 301 / http://newsite.com/
```
这种方式在链接完好无损的情况下完成. 即 `www.oldsite.com/some/crazy/link.html` 将变为 `www.newsite.com/some/crazy/link.html`. 当您只是将站点“移动”到新域时，这非常有用. [Source](http://css-tricks.com/snippets/htaccess/301-redirects/)

### Alias “Clean” URLs
此代码段允许您使用“干净”的 URL——那些没有 PHP 扩展名的 URL，例如“example.com/users”而不是“example.com/users.php”.
```apacheconf
重写引擎开启
RewriteCond %{SCRIPT_FILENAME} !-d
重写规则 ^([^.]+)$ $1.php [NC,L]
```
[Source](http://www.abeautifulsite.net/access-pages-without-the-php-extension-using-htaccess/)

### Exclude URL from Redirection
此代码段允许您从重定向中排除 URL. 例如，如果您设置了重定向规则但想要排除 robots.txt，以便搜索引擎可以按预期访问该 URL.
```apacheconf
重写引擎开启
重写规则 ^robots.txt - [L]
```

## Security
### Deny All Access
```apacheconf
## Apache 2.2
全部拒绝

## Apache 2.4
## Require all denied
```

但是等等，这也会将您锁定在您的内容之外！ 从而引入...

### Deny All Access Except Yours
```apacheconf
## Apache 2.2
命令拒绝，允许
全部拒绝
允许来自 xxx.xxx.xxx.xxx

## Apache 2.4
## Require all denied
## Require ip xxx.xxx.xxx.xxx
```
 `xxx.xxx.xxx.xxx` 是您的 IP. 例如，如果您将最后三位数字替换为“0/12”，这将指定同一网络内的 IP 范围，从而避免您单独列出所有允许的 IP 的麻烦. [Source](http://speckyboy.com/2013/01/08/useful-htaccess-snippets-and-hacks/)

现在当然有一个颠倒的版本：

### Allow All Access Except Spammers'
```apacheconf
## Apache 2.2
命令拒绝，允许
来自 xxx.xxx.xxx.xxx 的拒绝
来自 xxx.xxx.xxx.xxy 的拒绝

## Apache 2.4
## Require all granted
## Require not ip xxx.xxx.xxx.xxx
## Require not ip xxx.xxx.xxx.xxy
```

### Deny Access to Hidden Files and Directories
隐藏文件和目录（名称以点“.”开头的文件和目录）即使不是全部，也应该在大多数情况下得到保护. 例如：`.htaccess`、`.htpasswd`、`.git`、`.hg`...
```apacheconf
RewriteCond %{SCRIPT_FILENAME} -d [或]
RewriteCond %{SCRIPT_FILENAME} -f
重写规则“(^|/)\.”  - [F]
```

或者，您可以只引发“未找到”错误，让攻击者无所适从：
```apacheconf
重定向匹配 404 /\..*$
```

### Deny Access to Backup and Source Files
这些文件可能是由某些文本/HTML 编辑器（如 Vi/Vim）留下的，如果暴露给公众会造成很大的安全隐患.
```apacheconf
<FilesMatch "(\.(bak|config|dist|fla|inc|ini|log|psd|sh|sql|swp)|~)$">
    ##阿帕奇 2.2
    订单允许、拒绝
    全部拒绝
    满足所有

    ##阿帕奇 2.4
    #要求全部拒绝
</FilesMatch>
```
[Source](https://github.com/h5bp/server-configs-apache)

### Disable Directory Browsing
```apacheconf
期权全指数
```

### Disable Image Hotlinking
```apacheconf
重写引擎开启
## Remove the following line if you want to block blank referrer too
RewriteCond %{HTTP_REFERER} !^$

RewriteCond %{HTTP_REFERER} !^https?://(.+\.)?example.com [NC]
重写规则 \.(jpe?g|png|gif|bmp)$ - [NC,F,L]

## If you want to display a “blocked” banner in place of the hotlinked image,
## replace the above rule with:
## RewriteRule \.(jpe?g|png|gif|bmp) http://example.com/blocked.png [R,L]
```

### Disable Image Hotlinking for Specific Domains
有时您只想禁用来自某些坏人的图像盗链.
```apacheconf
重写引擎开启
RewriteCond %{HTTP_REFERER} ^https?://(.+\.)?badsite\.com [NC,OR]
RewriteCond %{HTTP_REFERER} ^https?://(.+\.)?badsite2\.com [NC,OR]
重写规则 \.(jpe?g|png|gif|bmp)$ - [NC,F,L]

## If you want to display a “blocked” banner in place of the hotlinked image,
## replace the above rule with:
## RewriteRule \.(jpe?g|png|gif|bmp) http://example.com/blocked.png [R,L]
```

### Password Protect a Directory
首先，您需要在系统某处创建一个 .htpasswd 文件：
``` 狂欢
htpasswd -c /home/fellowship/.htpasswd boromir
```

然后您可以使用它进行身份验证：
```apacheconf
授权类型基本
AuthName &quot;一不简单&quot;
AuthUserFile /home/fellowship/.htpasswd
需要有效用户
```

### Password Protect a File or Several Files
```apacheconf
AuthName &quot;一尚不简&quot;
授权类型基本
AuthUserFile /home/fellowship/.htpasswd

<Files "one-ring.o">
需要有效用户
</Files>

<FilesMatch ^((one|two|three)-rings?\.o)$>
需要有效用户
</FilesMatch>
```

### Block Visitors by Referrer
这会拒绝来自（由）特定域的所有用户的访问.
[Source](http://www.htaccess-guide.com/deny-visitors-by-referrer/)
```apacheconf
重写引擎开启
## Options +FollowSymlinks
RewriteCond %{HTTP_REFERER} somedomain\.com [NC,OR]
RewriteCond %{HTTP_REFERER} anotherdomain\.com
重写规则 .* - [F]
```

### Prevent Framing the Site
这可以防止网站被加框（即放入 `iframe` 标签），同时仍然允许为特定 URI 加框.
```apacheconf
SetEnvIf Request_URI &quot;/starry-night&quot; allow_framing=true
标头设置 X-Frame-Options SAMEORIGIN env=!allow_framing
```

## Performance
### Compress Text Files
```apacheconf
<IfModule mod_deflate.c>

    #强制压缩损坏的标头.
    #https://developer.yahoo.com/blogs/ydn/pushing-beyond-gzipping-25601.html
    <IfModule mod_setenvif.c>
        <IfModule mod_headers.c>
            SetEnvIfNoCase ^(Accept-EncodXng|X-cept-Encoding|X{15}|~{15}|-{15})$ ^((gzip|deflate)\s*,?\s*)+|[X~ -]{4,13}$ HAVE_Accept-编码
            RequestHeader 追加 Accept-Encoding &quot;gzip,deflate&quot; env=HAVE_Accept-Encoding
        </IfModule>
    </IfModule>

    #压缩所有标有以下 MIME 类型之一的输出
    #(Apache 2.3.7以下版本不需要开启`mod_filter`
    #并且可以删除`<IfModule mod_filter.c>  ` 和 `</IfModule>  `线
    #  as `AddOutputFilterByType` is still in the core directives).
    <IfModule mod_filter.c>
        AddOutputFilterByType DEFLATE application/atom+xml \
                                      应用程序/JavaScript \
                                      应用程序/json \
                                      应用程序/rss+xml \
                                      应用程序/vnd.ms-字体对象\
                                      应用程序/x-字体-ttf \
                                      应用程序/x-web-app-manifest+json \
                                      应用程序/xhtml+xml \
                                      应用程序/XML \
                                      字体/opentype \
                                      图片/svg+xml \
                                      图片/x-icon \
                                      文字/CSS \
                                      文本/HTML \
                                      文本/纯 \
                                      文本/x-组件\
                                      文本/xml
    </IfModule>

</IfModule>
```
[Source](https://github.com/h5bp/server-configs-apache)


### Set Expires Headers
 _Expires headers_ 告诉浏览器他们是应该从服务器请求特定文件还是从缓存中获取它. 建议将静态内容的过期标头设置为将来的某个时间.

如果您不使用基于文件名的缓存清除来控制版本控制，请考虑将 CSS 和 JS 等资源的缓存时间降低到 1 周左右. [Source](https://github.com/h5bp/server-configs-apache)
```apacheconf
<IfModule mod_expires.c>
    ExpiresActive 于
    ExpiresDefault &quot;访问加 1 个月&quot;

  #CSS
    ExpiresByType text/css “访问加 1 年”

  #数据交换
    ExpiresByType application/json &quot;访问加 0 秒&quot;
    ExpiresByType application/xml “访问加 0 秒”
    ExpiresByType text/xml “访问加 0 秒”

  #Favicon（无法重命名！）
    ExpiresByType 图像/x-图标“访问加 1 周”

  #HTML 组件 (HTC)
    ExpiresByType 文本/x-组件“访问加 1 个月”

  #HTML
    ExpiresByType text/html &quot;访问加 0 秒&quot;

  #JavaScript
    ExpiresByType 应用程序/javascript“访问加 1 年”

  #清单文件
    ExpiresByType application/x-web-app-manifest+json   "access plus 0 seconds"
    ExpiresByType 文本/缓存清单“访问加 0 秒”

  #媒体
    ExpiresByType 音频/ogg“访问加 1 个月”
    ExpiresByType image/gif “访问加 1 个月”
    ExpiresByType image/jpeg “访问加 1 个月”
    ExpiresByType image/png “访问加 1 个月”
    ExpiresByType 视频/mp4“访问加 1 个月”
    ExpiresByType 视频/ogg“访问加 1 个月”
    ExpiresByType 视频/webm“访问加 1 个月”

  #网络订阅
    ExpiresByType application/atom+xml “访问加 1 小时”
    ExpiresByType application/rss+xml “访问加 1 小时”

  #网络字体
    ExpiresByType application/font-woff2 “访问加 1 个月”
    ExpiresByType application/font-woff “访问加 1 个月”
    ExpiresByType application/vnd.ms-fontobject“访问加 1 个月”
    ExpiresByType application/x-font-ttf “访问加 1 个月”
    ExpiresByType 字体/opentype“访问加 1 个月”
    ExpiresByType image/svg+xml “访问加 1 个月”
</IfModule>
```

### Turn eTags Off
通过删除 `ETag` 标头，您可以禁用缓存和浏览器验证文件的能力，因此它们被迫依赖于您的 `Cache-Control` 和 `Expires` 标头. [Source](http://www.askapache.com/htaccess/apache-speed-etags.html)
```apacheconf
<IfModule mod_headers.c>
    标题看不见的 ETag
</IfModule>
FileETag 无
```

## Miscellaneous

### Set PHP Variables
```apacheconf
php_value<key><val>

## For example:
php_value upload_max_filesize 50M
php_value max_execution_time 240
```

### Custom Error Pages
```apacheconf
ErrorDocument 500 “休斯顿，我们有问题.”
错误文档 401 http://error.example.com/mordor.html
错误文档 404 /errors/halflife3.html
```

### Force Downloading
有时你想强制浏览器下载一些内容而不是显示它.
```apacheconf
<Files *.md>
    ForceType 应用程序/八位字节流
    标头集 Content-Disposition 附件
</Files>
```

现在这个阴有一个阳：

### Prevent Downloading
有时您想强制浏览器显示某些内容而不是下载它.
```apacheconf
<FilesMatch "\.(tex|log|aux)$">
    标头集 Content-Type text/plain
</FilesMatch>
```

### Allow Cross-Domain Fonts
由于以下原因，CDN 提供的网络字体可能无法在 Firefox 或 IE 中运行 [CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing) . 这个片段解决了这个问题.
```apacheconf
<IfModule mod_headers.c>
    <FilesMatch "\.(eot|otf|ttc|ttf|woff|woff2)$">
        标头设置 Access-Control-Allow-Origin &quot;*&quot;
    </FilesMatch>
</IfModule>
```
[Source](https://github.com/h5bp/server-configs-apache/issues/32)

### Auto UTF-8 Encode
您的文本内容应该始终采用 UTF-8 编码，不是吗？
```apacheconf
## Use UTF-8 encoding for anything served text/plain or text/html
添加默认字符集 utf-8

## Force UTF-8 for a number of file formats
添加字符集 utf-8 .atom .css .js .json .rss .vtt .xml
```
[Source](https://github.com/h5bp/server-configs-apache)

### Switch to Another PHP Version
如果您在共享主机上，可能安装了多个版本的 PHP，有时您需要为您的网站安装一个特定版本. 以下代码段应为您切换 PHP 版本.

```apacheconf
添加处理程序应用程序/x-httpd-php56 .php

## Alternatively, you can use AddType
添加类型应用程序/x-httpd-php56 .php
```

### Disable Internet Explorer Compatibility View
 IE 中的兼容性视图可能会影响某些网站的显示方式. 以下代码段应强制 IE 使用边缘渲染引擎并禁用兼容性视图.

```apacheconf
<IfModule mod_headers.c>
    BrowserMatch MSIE 是 msie
    标头集 X-UA-Compatible IE=edge env=is-msie
</IfModule>
```

### Serve WebP Images
If [WebP images](https://developers.google.com/speed/webp/?csw=1) 受支持，并且在与将要提供的 jpg/png 图像相同的位置找到具有 .webp 扩展名和相同名称的图像，然后将提供 WebP 图像.

```apacheconf
重写引擎开启
RewriteCond %{HTTP_ACCEPT} 图片/webp
RewriteCond %{DOCUMENT_ROOT}/$1.webp -f
RewriteRule (.+)\.(jpe?g|png)$ $1.webp [T=image/webp,E=accept:1]
```
[Source](https://github.com/vincentorback/WebP-images-with-htaccess)
