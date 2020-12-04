<div class="github-widget" data-repo="jakoch/awesome-composer"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Composer [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/jakoch/awesome-composer.svg?branch=master)](https://travis-ci.org/jakoch/awesome-composer) [![license](https://img.shields.io/github/license/jakoch/awesome-composer.svg?maxAge=2592000)]()

[<img src="https://raw.githubusercontent.com/jakoch/awesome-composer/master/logo-composer-transparent.png" align="right" width="150">](https://getcomposer.org/)

&gt;精选的Composer，Packagist，Satis，插件，脚本，视频，教程资源列表.

您可能还喜欢 [awesome-php](https://github.com/ziadoz/awesome-php).

*请阅读 [contribution guidelines](https://github.com/jakoch/awesome-composer/blob/master/contributing.md) 在捐款之前.*

## Composer

- [Official Website](https://getcomposer.org/)
- [Github](https://github.com/composer/composer)
- [Issues](https://github.com/composer/composer/issues)
- [Source](https://github.com/composer/composer/tree/HEAD/src/Composer)
- [Documentation](https://getcomposer.org/doc/)
- [Getting Started Guide and Installation Instructions](https://getcomposer.org/doc/00-intro.md)
- [Find Packages on Packagist](https://packagist.org/)
- [CheatSheet](https://composer.json.jolicode.com/) -CLI命令和`composer.json`模式的概述.
- [Composer Installers](https://github.com/composer/installers) -适用于多个框架的Composer安装程序.

### Support

#### Stack Overflow

-您可以使用以下标签：`composer-php`，`packagist`，`satis` +`php`.
- [Ask a new question](http://stackoverflow.com/questions/ask?tags=composer-php+php)
- [Find questions tagged `composer-php`](http://stackoverflow.com/questions/tagged/composer-php)

#### IRC

-IRC频道位于`irc.freenode.org`上： [#composer](https://webchat.freenode.net/#composer) 对于用户和 [#composer-dev](https://webchat.freenode.net/#composer-dev) 为发展.

---------------------------------------------------------

## Plugins

- [Documentation for Plugins](https://getcomposer.org/doc/articles/plugins.md) -编写Composer插件时，此官方文档是一个很好的起点.
- [Composer-Asset-Plugin](https://github.com/fxpio/composer-asset-plugin) -Composer的npm / Bower依赖性管理器.
- [Composer-AWS](https://github.com/naderman/composer-aws) -该插件加载存储库数据并从Amazon S3下载软件包（具有对私有存储库的身份验证支持）.
- [Composer-Composition](https://github.com/bamarni/composition) -提供API，用于在运行时检查您的环境.
- [Composer-Suggest](https://github.com/nfreear/composer-suggest) -使您能够根据关键字模式安装一组自定义的建议软件包.
- [Composer-Versions-Check](https://github.com/Soullivaneuh/composer-versions-check) -使用更新命令后，显示最近主要版本中已过期的软件包（显示“最新是vX.YZ”）.
- [Composer-Changelogs](https://github.com/pyrech/composer-changelogs)  -提供更新摘要，并带有指向changelog / releasenote / tag的链接. 更新composer.lock文件时，准备将输出粘贴到提交消息中.
- [Composer-Merge-Plugin](https://github.com/wikimedia/composer-merge-plugin) -在Composer运行时合并多个`composer.json`文件.
- [Composer-Bin-Plugin](https://github.com/bamarni/composer-bin-plugin) -增加了对在单个存储库中管理多个程序包的依赖性的支持，或隔离了bin依赖性.
- [Composer-Inheritance-Plugin](https://github.com/theofidry/composer-inheritance-plugin) -Wikimedia composer-merge-plugin的官方版本可与Bamarni composer-bin-plugin一起使用.
- [Composer-MonoRepo-Plugin](https://github.com/beberlei/composer-monorepo-plugin) -该插件有助于管理单个存储库中多个软件包的依赖性.
- [Composer-Patches-Plugin](https://github.com/netresearch/composer-patches-plugin)  -使您能够为任何软件包中的任何软件包提供补丁. 提取依赖项后，补丁将应用在最上面.
- [Composer-Patches](https://github.com/cweagans/composer-patches) -该插件将补丁从本地或远程文件应用到任何必需的软件包.
- [Composer-Patches](https://github.com/vaimo/composer-patches) -将补丁从本地或远程文件应用到给定Composer项目中的任何软件包.
- [Composer-Patchset](https://github.com/mageops/php-composer-plugin-patchset) -自动获取，更新补丁并将其应用于任何作曲家程序包-将补丁集存储为作曲家程序包本身.
- [Composer-Plugin-QA](https://github.com/Webysther/composer-plugin-qa) -全面的插件，供作曲者使用以执行PHP质量保证工具.
- [Composer-Cleanup-Plugin](https://github.com/barryvdh/composer-cleanup-plugin) -从供应商目录中删除测试和文档文件夹.
- [Composer-Cleaner](https://github.com/dg/composer-cleaner) -该工具可从供应商目录中删除不必要的文件和目录.
- [Composer-Ignore-Plugin](https://github.com/lichunqiang/composer-ignore-plugin)  -使您能够从供应商文件夹中删除文件和文件夹（以进行更清洁，更小规模的生产部署）. 它是`.gitattributes`的替代.
- [Composer-Vendor-Cleaner](https://github.com/liborm85/composer-vendor-cleaner) -插件通过glob模式语法从`vendor`目录中删除了不必要的开发文件和目录.
- [Drupal Vendor Hardening Composer Plugin](https://github.com/drupal/core-vendor-hardening) -从项目的供应商目录中删除无关的目录，并将.htaccess和web.config文件添加到项目的供应商目录的根目录中.
- [Composer-Shared-Package-Plugin](https://github.com/Letudiant/composer-shared-package-plugin) -允许您通过创建符号链接在项目之间共享选定的包.
- [Composer-Symlinker](https://github.com/e-picas/composer-symlinker) -使您能够从不同目录加载软件包（而不是从/ vendor加载软件包）.
- [Prestissimo](https://github.com/hirak/prestissimo) -使用`phpext_curl`的并行下载器.
- [Composer-Curl-Plugin](https://github.com/ngyuki/composer-curl-plugin) -该插件使用phpext_curl下载软件包.
- [Composer-Custom-Directory-Installer](https://github.com/mnsami/composer-custom-directory-installer) -一个composer插件，用于在默认composer安装路径（供应商文件夹）之外的自定义目录中安装不同类型的composer软件包.
- [Composer-Dependency-Analyzer](https://packagist.org/packages/jms/composer-deps-analyzer) -允许您为已安装的composer项目构建依赖关系图.
- [Graph-Composer](https://github.com/clue/graph-composer) -为项目的`composer.json`及其依赖项提供图形可视化.
- [PackageVersions](https://github.com/Ocramius/PackageVersions) -提供对已安装的作曲家依赖版本的快速便捷访问.
- [Composer Locator](https://github.com/mindplay-dk/composer-locator) -提供一种查找给定Composer软件包名称的安装路径的方法.
- [PackageInfo](https://github.com/ThaDafinser/PackageInfo) -使您能够检索所有软件包信息（例如版本，标签，发布日期，说明）.
- [Composer-Git-Hooks](https://github.com/BrainMaestro/composer-git-hooks) -一个库，可轻松管理作曲家配置中的git挂钩.
- [Symfony-Flex](https://github.com/symfony/flex) -提供 [recipe-based](https://github.com/symfony/recipes) Symfony软件包的安装和配置管理.
- [Narrowspark-Automatic](https://github.com/narrowspark/automatic) -自动执行应用程序中最常见的任务，增加软件包下载量，添加作曲家安全审核等.
- [PHPCodeSniffer-Composer-Installer](https://github.com/DealerDirect/phpcodesniffer-composer-installer) -该插件可让您安装 [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 编码标准（规则集）.
- [Composer-Warmup](https://github.com/jderusse/composer-warmup) -该插件将命令“ warmup-opcode”添加到Composer，这会触发将在项目中发现的所有PHP文件编译到Opcache中.
- [Foxy](https://github.com/fxpio/foxy) -在安装或更新composer软件包时，执行npm / yarn软件包安装操作的Composer插件.
- [NodeJS-Installer](https://github.com/thecodingmachine/nodejs-installer) -NodeJS和npm的安装程序.
- [Node-Composer](https://github.com/mariusbuescher/node-composer) -NodeJS，npm和yarn的安装程序.
- [Imposter-Plugin](https://github.com/typisttech/imposter-plugin)  -将所有Composer供应商软件包包装在您自己的名称空间中. 适用于WordPress插件.
- [Composer Preload](https://github.com/Ayesh/Composer-Preload) - The plugin generates a `vendor/preload.php` file to warm up the Opcache.
- [PHP Inc](https://github.com/krakphp/php-inc) -自动包含用于autoload和autoload-dev的文件，以便于在composer加载的应用程序中使用函数和分组定义.
- [Composer Registry Manager](https://github.com/slince/composer-registry-manager) -使您可以在不同的作曲者存储库之间切换.
- [Production-Dependencies-Guard](https://github.com/kalessil/production-dependencies-guard) -防止将开发包添加到需求中并进入生产环境.
- [Composer Exclusive Install](https://github.com/erickskrauch/composer-exclusive-install) -一次阻止多个安装或更新操作.
- [Composer-Downloads-Plugin](https://github.com/civicrm/composer-downloads-plugin) -轻量级的机制，仅通过“ url”和“ path”下载外部资源（ZI​​P / TAR文件）.
- [Private-Composer-Installer](https://github.com/ffraenz/private-composer-installer) -安装帮助程序，将包密钥中的敏感密钥外包到环境变量中.
- [CycloneDX-PHP-Composer](https://github.com/CycloneDX/cyclonedx-php-composer) -创建一个 [CycloneDX](https://cyclonedx.org/) 用于项目依赖项的“软件物料清单”（SBOM）.  SBOM可以通过以下方式进行依赖项监视和风险分析： [OWASP DependencyTrack](https://dependencytrack.org/).
- [Composer-Compile-Plugin](https://github.com/civicrm/composer-compile-plugin)  -允许PHP库定义简单，自由格式的编译任务. 支持任何包装中的安装后挂钩.

## Tools

- [Composer SemVer Checker](https://semver.mwl.be) -通过对Packagist托管软件包进行语义版本检查，使您能够确定对版本解析问题的约束.
- [Composer-Yaml](https://github.com/igorw/composer-yaml) -此工具将`composer.yml`转换为`composer.json`.
- [Studio](https://github.com/franzliedke/studio)  -用于开发Composer软件包的工作台. 它是编辑供应商文件夹中的依赖项或使用 [PathRepositories](https://getcomposer.org/doc/05-repositories.md#path) 将依赖项的本地副本加载到项目中.
- [OctoLinker Browser Extension](https://github.com/OctoLinker/OctoLinker) -使您能够浏览Github上的Composer / NPM依赖关系.
- [ComposerRequireChecker](https://github.com/maglnet/ComposerRequireChecker) -一个CLI工具，用于分析依赖关系并验证软件包的来源中没有使用未知的导入符号.
- [Composer-Unused](https://github.com/composer-unused/composer-unused) -一个CLI工具，可扫描您的代码并显示未使用的Composer依赖性.
- [Composer-Normalize](https://github.com/ergebnis/composer-normalize) -该插件通过重组和排序条目（规范化）来帮助保持您的`composer.json`文件一致.
- [Composer-Service](https://github.com/pborreli/composer-service) - Enables you to run Composer as a service on a remote server.
- [Composer PreferLowest Checker](https://github.com/dereuromark/composer-prefer-lowest) -严格比较composer.json的指定最低版本与preferred-lowest composer update命令选项实际使用的最低版本.
- [Bramus/Composer-Autocomplete](https://github.com/bramus/composer-autocomplete) -适用于Composer的Bash / Shell自动完成脚本.
- [Composer/Xdebug-Handler](https://github.com/composer/xdebug-handler) -帮助您在不加载xdebug扩展名的情况下重新启动CLI进程.

## Scripts

- [ParameterHandler](https://github.com/Incenteev/ParameterHandler) -允许您在运行作曲家安装或更新时管理忽略的参数.
- [Tooly](https://github.com/tommy-muehle/tooly-composer-script)  -在项目`composer.json`中管理所需的PHAR文件. 每个PHAR文件将保存在作曲家的二进制目录中. 每个PHAR的GPG验证均可选.
- [Melody](https://github.com/sensiolabs/melody) -一文件式作曲家脚本.
- [Composer-Travis-Lint](https://github.com/raphaelstolt/composer-travis-lint) -允许您填充Travis CI配置文件（.travis.yml`）.
- [Composer-Multitest](https://github.com/raphaelstolt/composer-multitest) -使您可以针对多个本地安装的PHP版本（由PHPBrew或phpenv管理）运行Composer脚本.
- [ScriptsDev](https://github.com/neronmoon/scriptsdev) -使您能够使用`scripts-dev`部分，该部分仅在开发模式下触发脚本.
- [PhantomJS-Installer](https://github.com/jakoch/phantomjs-installer) -一个Composer软件包，可将PhantomJS二进制文件（Linux，Windows，Mac）安装到项目的/ bin中.
- [Composer-Vendor-Cleanup](https://github.com/0xch/composer-vendor-cleanup) -从供应商目录中删除列入白名单的不必要文件（例​​如测试/文档等）的脚本.
- [Composer Substitution Plugin](https://github.com/villfa/composer-substitution-plugin) -一个Composer插件，用动态值替换“脚本”部分中的占位符.

## Services

- [Dependabot](https://dependabot.com/)  -Dependabot是依赖项更新服务. 它通过发送请求请求来监视和更新您的依赖项. 该服务对于公共回购和个人帐户回购是免费的.

---------------------------------------------------------

## Tutorials

- [A beginners guide to Composer](https://scotch.io/tutorials/a-beginners-guide-to-composer)
- [A short & simple Composer tutorial](https://www.dev-metal.com/composer-tutorial/)
- [Easy package management with Composer](https://code.tutsplus.com/tutorials/easy-package-management-with-composer--net-25530)
- [PHP Dependency Management with Composer](https://www.sitepoint.com/re-introducing-composer/)
- [Composer Primer](https://daylerees.com/composer-primer/)
- [PHP Composer Magento Tutorial by Alan Storm](https://alanstorm.com/php_composer_magento_tutorial/ )
- [Creating and Using Composer Packages](https://hub.packtpub.com/creating-and-using-composer-packages/)

## Blogs

- [Jordi Boggiano (seldaek)](https://seld.be/)
- [Nils Adermann (naderman)](https://naderman.de/)
- [Composer: Part 1 - What & Why](http://blog.nelm.io/2011/12/composer-part-1-what-why/)
- [Composer: Part 2 - Impact](http://blog.nelm.io/2011/12/composer-part-2-impact/)
- [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html)
- [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html)

## Videos

- [Composer Best Practices 2018 - Nils Adermann @ phpday 2018](https://www.youtube.com/watch?v=EpvihKaQyLs)
- [Managing dependencies is more than running "composer update" -  Nils Adermann @ phpsrb17](https://www.youtube.com/watch?v=QL6w8H2eHQE)
-[作曲家最佳做法-Jordi Boggiano @ php [tek] 2015]（https://www.youtube.com/watch?v=uNlYpSTiAcA）
- [Wonderful World of Composer](https://symfonycasts.com/screencast/composer)
- [PHP Composer Quickstart](https://www.youtube.com/watch?v=Ejr4Xqs9V2I)
- [How Composer helped shape the new way of writing PHP - Nils Adermann @ Drupal Camp Frankfurt](https://www.youtube.com/watch?v=C2jfLM-Egvg)
- [Composer Package Management - Nils Adermann @ T3CON12DE](https://www.youtube.com/watch?v=P4Qnp90TG0g)

## Slides

-Nils Adermann的幻灯片
  -来源：https：//naderman.de/slippy/src/
  - [PHP Reinvented - How Composer helped shape the new way of writing PHP](https://naderman.de/slippy/src/?file=2014-04-13-PHP-Reinvented.html)
  - [Composer Update](https://naderman.de/slippy/src/?file=2015-02-03-Composer-Update.html)
  - [Dependency Management with Composer PHP Reinvented](https://naderman.de/slippy/src/?file=2015-02-01-Dependency-Management-with-Composer-PHP-Reinvented.html)
  -[管理依赖项是
不仅仅是跑步
“ composer更新”]（https://naderman.de/slippy/slides/2017-06-30-DPC-Dependency-Management-is-more-than-composer-update.pdf）
  -[作曲家
最佳做法@ T3DD17]（https://naderman.de/slippy/slides/2017-07-13-T3DD17-Composer-Best-Practices.pdf）
  -[控制您
依赖
私人包装专家]（https://naderman.de/slippy/slides/2017-07-14-T3DD17-Gain-control-over-your-dependencies-with-private-packagist.pdf）
  - [Composer.lock demystified](https://naderman.de/slippy/slides/2018-01-26-composer-lock-demystified.pdf)
  - [Compoer In-Depth @ Contao Konferenz 2018](https://naderman.de/slippy/slides/2018-06-08-Contao-Konferenz-2018-Composer-In-Depth.pdf)
  - [Composer Best Practices 2018](https://naderman.de/slippy/slides/2018-06-27-Composer-Best-Practices-2018.pdf)
  - [Developing and Deploying Magento with Composer Best Practices](https://naderman.de/slippy/slides/2018-06-18-Developing-and-Deploying-Magento-with-Composer-Best-Practices.pdf)
  - [Composer Platform Config (check-platform-reqs) @ SymfonCon 2018](https://naderman.de/slippy/slides/2018-12-07-SymfonCon-Composer-Platform-Config.pdf)
-Jordi Boggiano的幻灯片
  -来源：http：//slides.seld.be/
  - [Dependency Management with Composer (2013)](http://slides.seld.be/?file=2013-10-04+Dependency+Management+with+Composer.html)
  - [In Depth with Composer (2013)](http://slides.seld.be/?file=2013-10-05+In-Depth+with+Composer.html)
  - [Composer Best Practices (2015)](http://slides.seld.be/?file=2015-07-25+Composer+Best+Practices.html)
  - [Introduction to Composer (2015)](http://slides.seld.be/?file=2015-06-30+Introduction+to+Composer.html)
  - [Composer in 2016](http://slides.seld.be/?file=2016-07-22+Composer+in+2016.html)

---------------------------------------------------------

## Packagist

[Packagist](https://packagist.org) 是PHP软件包存储库.

### Setup a Packagist Mirror

- [Packagist Mirror](https://github.com/Webysther/packagist-mirror)  -此脚本有助于设置打包镜像. 它是的维护和稳定版本 [Packagist Crawler](https://github.com/hirak/packagist-crawler).
- [Docker Image](https://github.com/Webysther/packagist-mirror-docker) -此Docker映像有助于创建自定义的packagist镜像.
- [Packagist Mirror from Indonesia](https://github.com/IndraGunawan/packagist-mirror) -用于创建打包镜像的另一种实现.

### Packagist Mirrors

关于元数据镜像：https://packagist.org/mirrors

- 北美
  -加拿大- [packagist.org](https://packagist.org) *主镜*
- 南美洲
  - 巴西 - [packagist.com.br](https://packagist.com.br)
-非洲
  -南非- [https://github.com/jakoch/awesome-composer/blob/master/packagist.co.za](https://github.com/jakoch/awesome-composer/blob/master/packagist.co.za)
-亚洲
  -中国- [php.cnpkg.org](https://php.cnpkg.org), [https://pkg.phpcomposer.com/](https://pkg.phpcomposer.com/), [https://mirrors.aliyun.com/composer/](https://mirrors.aliyun.com/composer/)
  -印度- [https://packagist.in/](https://packagist.in/)
  -印尼- [packagist.phpindonesia.id](https://packagist.phpindonesia.id)
  - 日本 - [packagist.jp](https://packagist.jp)

## Composer Repositories

### Private repositories
- [fxpio/tug](https://github.com/fxpio/tug) -使您可以在AWS Serverless上托管私有Composer注册表，以服务私有PHP程序包，这些程序包托管在Github或Gitlab服务上.

### Private Packagist
- [Private Packagist Cloud](https://packagist.com) -Composer存储库即服务，用于私有软件包并镜像其他存储库中的软件包.
- [Private Packagist Enterprise](https://packagist.com) -私有Packagist的本地自托管版本.
- [Private Packagist API Client](https://github.com/packagist/private-packagist-api-client)  -Private Packagist API的PHP客户端. 客户端处理身份验证，签名生成以及对所有端点的访问.

### Repman

- [repman.io](https://repman.io) & [repman-io/repman](https://github.com/repman-io/repman) -私有PHP软件包存储库管理器和Packagist代理.
- [repman-io/composer-plugin](https://github.com/repman-io/composer-plugin) -该插件可通过为所有依赖项添加分发镜像URL来通过Repman下载（无需更新`composer.lock`文件）. 

## Packagist-compatible repositories

- [WordPress Packagist](https://wpackagist.org/) -将WordPress插件和主题目录镜像为Composer存储库.
- [Asset Packagist](https://asset-packagist.org/) -允许将Bower和NPM软件包安装为本地Composer软件包.
- [Firegento](https://packages.firegento.com/) -提供Magento模块的Composer信息库.
- [Drupal Packagist](https://www.drupal.org/node/2822344) -用于Drupal 7和8核心，模块和主题的Composer存储库.
- [Satis Server](https://github.com/lukaszlach/satis-server) -该Docker容器提供了Satis Server，使您能够运行私有，自托管的Composer存储库，并支持Git，Mercurial和Subversion，HTTP API，HTTPs，webhook处理程序和计划的构建.
- [Cloudsmith](https://cloudsmith.com/) -具有PHP / Composer支持（以及许多其他功能）的完全托管的软件包管理SaaS.
- [Release Belt](https://github.com/Rarst/release-belt) -自托管的Composer存储库实施，可快速集成第三方非Composer版本的ZIP文件.
- [Packeton](https://github.com/vtsykun/packeton)  -供供应商使用的私人自托管Composer存储库. 包装专家的分支，增加了对授权，客户用户，组，webhooks的支持.

### Satis

- [Gitlab-Composer](https://github.com/wemakecustom/gitlab-composer) -这是Gitlab存储库的分支/标签索引器.
- [Satisfy](https://github.com/ludofleury/satisfy) -具有Web UI的Satis作曲者存储库管理器.
- [Satis Control Panel](https://github.com/realshadow/satis-control-panel) -一个简单的Web UI，用于通过可选的CI集成管理您的Satis存储库.
- [Satis Go](https://github.com/benschw/satis-go) -用于管理Satis配置并托管生成的Composer存储库的Web服务器.

### Toran Proxy

- [ToranProxy](https://toranproxy.com/) （已弃用）-除了提供作曲家存储库外，ToranProxy还充当Packagist和GitHub的代理服务器.

---------------------------------------------------------

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Jens A. Koch](https://github.com/jakoch) 放弃了此作品的所有版权以及相关或邻近的权利.
