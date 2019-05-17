<div class="github-widget" data-repo="jakoch/awesome-composer"></div>
## Awesome Composer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/jakoch/awesome-composer.svg?branch=master)](https://travis-ci.org/jakoch/awesome-composer) [![license](https://img.shields.io/github/license/jakoch/awesome-composer.svg?maxAge=2592000)]()

[<img src="https://raw.githubusercontent.com/jakoch/awesome-composer/master/logo-composer-transparent.png" align="right" width="150">](https://getcomposer.org/)

&gt; Composer，Packagist，Satis，插件，脚本，视频，教程的精选资源列表.

你可能还喜欢 [awesome-php](https://github.com/ziadoz/awesome-php).

*请阅读 [contribution guidelines](https://github.com/jakoch/awesome-composer/blob/master/contributing.md) 在贡献之前.*

## Composer

- [Official Website](https://getcomposer.org/)
- [Issues](https://github.com/composer/composer/issues)
- [Github](https://github.com/composer/composer)
- [Getting Started Guide and Installation Instructions](https://getcomposer.org/doc/00-intro.md)
- [Documentation](https://getcomposer.org/doc/)
- [API Documentation](https://getcomposer.org/apidoc/master/index.html)
- [Find Packages on Packagist](https://packagist.org/)
- [CheatSheet](http://composer.json.jolicode.com/) -  CLI命令和`composer.json`模式概述.
- [Composer Installers](https://github.com/composer/installers) - 适用于多个框架的Composer安装程序.

### Support

#### Stack Overflow

- 你可以使用以下标签：`composer-php`，`packagist`，`satisf` +`php`.
- [Ask a new question](http://stackoverflow.com/questions/ask?tags=composer-php+php)
- [Find questions tagged `composer-php`](http://stackoverflow.com/questions/tagged/composer-php)

#### IRC

-  IRC频道在`irc.freenode.org`上： [#composer](https://webchat.freenode.net/?channels=composer) 对于用户和 [#composer-dev](https://webchat.freenode.net/?channels=composer-dev) 发展.

---------------------------------------------------------

## Plugins

- [Documentation for Plugins](https://getcomposer.org/doc/articles/plugins.md) - 编写Composer插件时，这个官方文档是一个很好的起点.
- [Composer-Asset-Plugin](https://github.com/fxpio/composer-asset-plugin) -  Composer的npm / Bower依赖关系管理器.
- [Composer-AWS](https://github.com/naderman/composer-aws) - 该插件从Amazon S3加载存储库数据并下载包（具有对私有存储库的身份验证支持）.
- [Composer-Composition](https://github.com/bamarni/composition) - 提供API，用于在运行时检查您的环境.
- [Composer-Suggest](https://github.com/nfreear/composer-suggest) - 允许您根据关键字模式安装自定义建议包组.
- [Composer-Versions-Check](https://github.com/Soullivaneuh/composer-versions-check) - 使用更新命令后显示上一个主要版本的过期软件包（显示“Latest is vX.YZ”）.
- [Composer-Changelogs](https://github.com/pyrech/composer-changelogs)   - 提供更新摘要以及指向changelog / releasenote / tag的链接.  更新composer.lock文件时，输出已准备好粘贴到提交消息中.
- [Composer-Merge-Plugin](https://github.com/wikimedia/composer-merge-plugin) - 在Composer运行时合并多个`composer.json`文件.
- [Composer-Bin-Plugin](https://github.com/bamarni/composer-bin-plugin) - 添加对在单个存储库中管理多个包的依赖关系的支持或隔离bin依赖关系.
- [Composer-Inheritance-Plugin](https://github.com/theofidry/composer-inheritance-plugin) - 维基媒体作曲家合并插件的观点版本与Bamarni composer-bin-plugin配合使用.
- [Composer-MonoRepo-Plugin](https://github.com/beberlei/composer-monorepo-plugin) - 该插件有助于管理单个存储库中多个包的依赖关系.
- [Composer-Patches-Plugin](https://github.com/netresearch/composer-patches-plugin)   - 使您能够从任何包中为任何包提供补丁.  获取依赖项后，将修补程序应用于顶部.
- [Composer-Patches](https://github.com/cweagans/composer-patches) - 该插件将补丁从本地或远程文件应用于任何所需的包.
- [Composer-Patches](https://github.com/vaimo/composer-patches) - 将本地或远程文件中的修补程序应用于属于给定作曲家项目的任何程序包.
- [Composer-Patchset](https://github.com/creativestyle/composer-plugin-patchset) - 自动获取，更新和应用补丁到任何编曲器包扭曲 - 将补丁集存储为作曲家包本身.
- [Composer-Plugin-QA](https://github.com/Webysther/composer-plugin-qa) - 作曲家执行PHP质量保证工具的综合插件.
- [Composer-Cleanup-Plugin](https://github.com/barryvdh/composer-cleanup-plugin) - 从供应商目录中删除测试和文档文件夹.
- [Composer-Cleaner](https://github.com/dg/composer-cleaner) - 该工具从供应商目录中删除不必要的文件和目录.
- [Composer-Ignore-Plugin](https://github.com/lichunqiang/composer-ignore-plugin)   - 使您可以从供应商文件夹中删除文件和文件夹（以使更清洁，更小的部署到生产）.  它是`.gitattributes`的替代品.
- [Composer-Shared-Package-Plugin](https://github.com/Letudiant/composer-shared-package-plugin) - 允许您通过创建符号链接在项目之间共享选定的包.
- [Composer-Symlinker](https://github.com/dg/composer-symlinker) - 使您可以从不同的目录加载包（而不是从/ vendor加载它们）.
- [Prestissimo](https://github.com/hirak/prestissimo) - 使用`phpext_curl`的并行下载程序.
- [Composer-Curl-Plugin](https://github.com/ngyuki/composer-curl-plugin) - 该插件使用phpext_curl下载包.
- [Composer-Custom-Directory-Installer](https://github.com/mnsami/composer-custom-directory-installer) - 作曲家插件，用于在默认编写器安装路径（供应商文件夹）之外的自定义目录中安装不同类型的编写器包.
- [Composer-Dependency-Analyzer](https://packagist.org/packages/jms/composer-deps-analyzer) - 允许您为已安装的编写器项目构建依赖关系图.
- [Graph-Composer](https://github.com/clue/graph-composer) - 为项目的“composer.json”及其依赖项提供图形可视化.
- [PackageVersions](https://github.com/Ocramius/PackageVersions) - 提供对已安装的composer依赖版本的非常快速和轻松的访问.
- [Composer Locator](https://github.com/mindplay-dk/composer-locator) - 提供查找给定Composer包名称的安装路径的方法.
- [PackageInfo](https://github.com/ThaDafinser/PackageInfo) - 使您可以检索所有包信息（如版本，标签，发布日期，说明）.
- [Composer-Git-Hooks](https://github.com/BrainMaestro/composer-git-hooks) - 一个库，可以轻松管理作曲家配置中的git挂钩.
- [Symfony-Flex](https://github.com/symfony/flex) - 提供 [recipe-based](https://github.com/symfony/recipes) Symfony软件包的安装和配置管理.
- [Narrowspark-Automatic](https://github.com/narrowspark/automatic) - 自动执行应用程序的最常见任务，提升包下载，添加作曲家安全审计等.
- [PHPCodeSniffer-Composer-Installer](https://github.com/DealerDirect/phpcodesniffer-composer-installer) - 该插件使您可以安装 [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 编码标准（规则集）.
- [Composer-Warmup](https://github.com/jderusse/composer-warmup) - 该插件将命令`warmup-opcode`添加到Composer，它会触发将项目中发现的所有PHP文件编译到Opcache中.
- [Foxy](https://github.com/fxpio/foxy) - 安装或更新composer包时执行npm / yarn包安装操作的Composer插件.
- [NodeJS-Installer](https://github.com/thecodingmachine/nodejs-installer) - 下载并安装NodeJS和npm作为composer包. 
- [Imposter-Plugin](https://github.com/typisttech/imposter-plugin)   - 将所有作曲家供应商包装在您自己的命名空间中.  用于WordPress插件.
- [Composer Preload](https://github.com/Ayesh/Composer-Preload) - 该插件生成一个`vendor / preload.php`文件来预热Opcache.
- [PHP Inc](https://github.com/krakphp/php-inc) - 自动包含autoload和autoload-dev文件，以便于在编写器加载的应用程序中使用函数和分组定义.
- [Composer Registry Manager](https://github.com/slince/composer-registry-manager) - 使您可以在不同的编写器存储库之间切换.
- [Production-Dependencies-Guard](https://github.com/kalessil/production-dependencies-guard) - 防止将开发包添加到require和进入生产环境中.

## Tools

- [Composer SemVer Checker](https://semver.mwl.be) - 通过对Packagist托管包进行语义版本检查，使您能够识别对版本解析问题的约束.
- [Composer-Yaml](https://github.com/igorw/composer-yaml) - 这个工具将`composer.yml`转换为`composer.json`.
- [Studio](https://github.com/franzliedke/studio)   - 用于开发Composer包的工作台.  它可以替代编辑供应商文件夹中的依赖项或使用 [PathRepositories](https://getcomposer.org/doc/05-repositories.md#path) 将依赖项的本地克隆加载到项目中.
- [OctoLinker Browser Extension](https://github.com/OctoLinker/OctoLinker) - 使您能够在Github上导航Composer / NPM依赖项.
- [ComposerRequireChecker](https://github.com/maglnet/ComposerRequireChecker) - 用于分析依赖关系并验证包的源中未使用未知导入符号的CLI工具.
- [Composer-Normalize](https://github.com/localheinz/composer-normalize) - 该插件通过重组和排序条目（规范化）有助于保持`composer.json`文件的一致性.
- [Composer-Service](https://github.com/pborreli/composer-service) - 使您可以在远程服务器上将Composer作为服务运行.
- [Composer PreferLowest Checker](https://github.com/dereuromark/composer-prefer-lowest) - 严格地将composer.json的指定最小版本与prefer-lowest composer update命令选项实际使用的版本进行比较.

## Scripts

- [ParameterHandler](https://github.com/Incenteev/ParameterHandler) - 允许您在运行编写器安装或更新时管理忽略的参数.
- [Tooly](https://github.com/tommy-muehle/tooly-composer-script)   - 在项目`composer.json`中管理所需的PHAR文件.  每个PHAR文件都将保存在composer二进制目录中.  可选择每个PHAR的GPG验证.
- [Melody](https://github.com/sensiolabs/melody) - 单文件编写器脚本.
- [Composer-Travis-Lint](https://github.com/raphaelstolt/composer-travis-lint) - 允许您对Travis CI配置文件（`.travis.yml`）进行lint.
- [Composer-Multitest](https://github.com/raphaelstolt/composer-multitest) - 使您能够针对多个本地安装的PHP版本运行Composer脚本，这些PHP版本由PHPBrew或phpenv管理.
- [ScriptsDev](https://github.com/neronmoon/scriptsdev) - 使您可以使用`scripts-dev`部分，该部分仅在开发模式下触发脚本.
- [PhantomJS-Installer](https://github.com/jakoch/phantomjs-installer)- 一个Composer Package，它将PhantomJS二进制文件（Linux，Windows，Mac）安装到项目的/ bin中.

## GUI 

- [Composercat](https://www.getcomposercat.com/) -  Composercat是Composer包管理器的综合GUI，专为专业人士和使用Composer迈出第一步的人员而设计.

## Services

- [Dependabot](https://dependabot.com/)   -  Dependabot是一个依赖更新服务.  它通过发送拉取请求来监视和更新您的依赖项.  该服务是免费的公共回购和个人帐户回购.

---------------------------------------------------------

## Tutorials

- [A beginners guide to Composer](https://scotch.io/tutorials/a-beginners-guide-to-composer)
- [A short & simple Composer tutorial](https://www.dev-metal.com/composer-tutorial/)
- [Easy package management with Composer](https://code.tutsplus.com/tutorials/easy-package-management-with-composer--net-25530)
- [PHP Dependency Management with Composer](https://www.sitepoint.com/re-introducing-composer/)
- [Composer Primer](https://daylerees.com/composer-primer/)
- [PHP Composer Magento Tutorial by Alan Storm](https://alanstorm.com/php_composer_magento_tutorial/ )

## Books

- [Creating and Using Composer Packages](https://hub.packtpub.com/creating-and-using-composer-packages/)

## Blogs

- [Jordi Boggiano (seldaek)](https://seld.be/)
- [Nils Adermann (naderman)](http://naderman.de/)
- [Composer: Part 1 - What & Why](http://blog.nelm.io/2011/12/composer-part-1-what-why/)
- [Composer: Part 2 - Impact](http://blog.nelm.io/2011/12/composer-part-2-impact/)
- [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html)
- [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html)

## Videos

- [Composer Best Practices 2018 - Nils Adermann @ phpday 2018](https://www.youtube.com/watch?v=EpvihKaQyLs)
- [Managing dependencies is more than running "composer update" -  Nils Adermann @ phpsrb17](https://www.youtube.com/watch?v=QL6w8H2eHQE)
-  [作曲家最佳实践 -  Jordi Boggiano @ php [tek] 2015]（https://www.youtube.com/watch?v=uNlYpSTiAcA）
- [Wonderful World of Composer](https://symfonycasts.com/screencast/composer)
- [PHP Composer Quickstart](https://www.youtube.com/watch?v=Ejr4Xqs9V2I)
- [How Composer helped shape the new way of writing PHP - Nils Adermann @ Drupal Camp Frankfurt](https://www.youtube.com/watch?v=C2jfLM-Egvg)
- [Composer Package Management - Nils Adermann @ T3CON12DE](https://www.youtube.com/watch?v=P4Qnp90TG0g)

## Slides

-  Nils Adermann的幻灯片 
  - 来源：http：//www.naderman.de/slippy/slides/
  - [PHP Reinvented - How Composer helped shape the new way of writing PHP](http://www.naderman.de/slippy/src/?file=2014-04-13-PHP-Reinvented.html)
  - [Composer Update](http://www.naderman.de/slippy/src/?file=2015-02-03-Composer-Update.html)
  - [Dependency Management with Composer PHP Reinvented](http://www.naderman.de/slippy/src/?file=2015-02-01-Dependency-Management-with-Composer-PHP-Reinvented.html)
  -  [管理依赖关系是
不仅仅是跑步
“作曲家更新”]（http://naderman.de/slippy/slides/2017-06-30-DPC-Dependency-Management-is-more-than-composer-update.pdf）
  -  [作曲家
最佳实践@ T3DD17]（http://www.naderman.de/slippy/slides/2017-07-13-T3DD17-Composer-Best-Practices.pdf）
  -  [获得对你的控制权
依赖性
Private Packagist]（http://www.naderman.de/slippy/slides/2017-07-14-T3DD17-Gain-control-over-your-dependencies-with-private-packagist.pdf）
  - [Composer.lock demystified](http://www.naderman.de/slippy/slides/2018-01-26-composer-lock-demystified.pdf)
  - [Compoer In-Depth @ Contao Konferenz 2018](http://www.naderman.de/slippy/slides/2018-06-08-Contao-Konferenz-2018-Composer-In-Depth.pdf)
  - [Composer Best Practices 2018](http://www.naderman.de/slippy/slides/2018-06-27-Composer-Best-Practices-2018.pdf)
  - [Developing and Deploying Magento with Composer Best Practices](http://www.naderman.de/slippy/slides/2018-06-18-Developing-and-Deploying-Magento-with-Composer-Best-Practices.pdf)
  - [Composer Platform Config (check-platform-reqs) @ SymfonCon 2018](http://www.naderman.de/slippy/slides/2018-12-07-SymfonCon-Composer-Platform-Config.pdf)
-  Jordi Boggiano的滑梯
  - 来源：http：//slides.seld.be/
  - [Dependency Management with Composer (2013)](http://slides.seld.be/?file=2013-10-04+Dependency+Management+with+Composer.html)
  - [In Depth with Composer (2013)](http://slides.seld.be/?file=2013-10-05+In-Depth+with+Composer.html)
  - [Composer Best Practices (2015)](http://slides.seld.be/?file=2015-07-25+Composer+Best+Practices.html)
  - [Introduction to Composer (2015)](http://slides.seld.be/?file=2015-06-30+Introduction+to+Composer.html)
  - [Composer in 2016](http://slides.seld.be/?file=2016-07-22+Composer+in+2016.html)

---------------------------------------------------------

## Packagist

- [Packagist Mirror from Brazil](https://github.com/Webysther/packagist-mirror) - 这是一个维护稳定版本 [packagist crawler](https://github.com/hirak/packagist-crawler).
- [Docker Image](https://github.com/Webysther/packagist-mirror-docker) - 此Docker镜像有助于创建自定义的包装镜像.
- [Packagist Mirror from Indonesia](https://github.com/IndraGunawan/packagist-mirror) - 另一种创建包装镜像的实现.

### Packagist Mirrors

关于元数据镜像：https：//packagist.org/mirrors

- 北美
  - 加拿大 -  [packagist.org](https://packagist.org) *主镜*
- 南美洲
  - 巴西 - [packagist.com.br](https://packagist.com.br)
- 非洲
  - 南非 -  [https://github.com/jakoch/awesome-composer/blob/master/packagist.co.za](https://github.com/jakoch/awesome-composer/blob/master/packagist.co.za)
- 亚洲
  - 中国 -  [php.cnpkg.org](https://php.cnpkg.org), [https://pkg.phpcomposer.com/](https://pkg.phpcomposer.com/)
  - 印尼 -  [packagist.phpindonesia.id](https://packagist.phpindonesia.id)
  - 日本 - [packagist.jp](https://packagist.jp)

## Composer Repositories

### Private Packagist
- [Private Packagist Cloud](https://packagist.com) - A Composer Repository as a Service for private packages and to mirror packages from other repositories.
- [Private Packagist Enterprise](https://packagist.com) - 私有包装的内部部署自托管版本.
- [Private Packagist API Client](https://github.com/packagist/private-packagist-api-client)   -  Private Packagist API的PHP客户端.  客户端处理身份验证，签名生成和对所有端点的访问.

## Packagist-compatible repositories

- [WordPress Packagist](https://wpackagist.org/) - 将WordPress插件和主题目录镜像为Composer存储库.
- [Asset Packagist](https://asset-packagist.org/) - 允许将Bower和NPM软件包安装为本机Composer软件包.
- [Firegento](http://packages.firegento.com/) - 提供Magento模块的Composer存储库.
- [Drupal Packagist](https://www.drupal.org/node/2822344) -  Drupal 7和8核心，模块和主题的Composer存储库.
- [Satis Server](https://github.com/lukaszlach/satis-server) - 此docker容器提供Satis服务器，使您能够运行私有的，自托管的Composer存储库，支持Git，Mercurial和Subversion，HTTP API，HTTPs支持，webhook处理程序和预定构建.
- [Cloudsmith](https://cloudsmith.io) - 完全托管的包管理SaaS，支持PHP / Composer（以及许多其他）.
- [Release Belt](https://github.com/Rarst/release-belt) - 自托管Composer存储库实现，可快速集成第三方非Composer版本的ZIP文件.

### Satis

- [Gitlab-Composer](https://github.com/wemakecustom/gitlab-composer) - 这是Gitlab存储库的分支/标记索引器.
- [Satisfy](https://github.com/ludofleury/satisfy) - 具有Web UI的Satis作曲家存储库管理器.
- [Satis Control Panel](https://github.com/realshadow/satis-control-panel) - 一个简单的Web UI，用于管理具有可选CI集成的Satis存储库.
- [Satis Go](https://github.com/benschw/satis-go) - 用于管理Satis配置和托管生成的Composer存储库的Web服务器.

### Toran Proxy

- [ToranProxy](https://toranproxy.com/) （不建议使用） - 除了提供作曲家存储库外，ToranProxy还充当Packagist和GitHub的代理服务器.

---------------------------------------------------------

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Jens A. Koch](https://github.com/jakoch) 已放弃对此作品的所有版权及相关或相邻权利.
