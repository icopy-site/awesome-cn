<div class="github-widget" data-repo="wernerkrauss/awesome-silverstripe-cms"></div>
## Awesome Silverstripe CMS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!--lint disable double-link-->
[<img src="https://raw.githubusercontent.com/wernerkrauss/awesome-silverstripe-cms/master/images/logo-silverstripe-cms.png" align="right" width="200">](https://www.silverstripe.org/)
<!--lint enable double-link-->
&gt; Silverstripe Framework 和 CMS 的有用资源

 Silverstripe CMS 是一个用于构建 Web 应用程序的开源 PHP 框架. 它是一个快速开发的 MVC 框架，可用作经典的完全成熟的 CMS 或无头 CMS，可以通过 GraphQL 或自定义 API 进行查询.
遵循“Active Record”设计模式，您可以使用项目特定的数据模型轻松扩展内置功能.

[Contributions welcome](https://github.com/wernerkrauss/awesome-silverstripe-cms/blob/master/CONTRIBUTING.md)，请发送拉取请求或打开问题以开始讨论.

过时的项目可以在 [archive](https://github.com/wernerkrauss/awesome-silverstripe-cms/blob/master/ARCHIVE.md).

<!-- PLEASE USE `doctoc --maxlevel 3 README.md` TO KEEP THE TOC TO AN APPROPRIATE SIZE -->
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->



<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## Official Websites
<!--lint disable double-link-->
- [www.silverstripe.org](https://www.silverstripe.org) - 框架和 CMS.
<!--lint enable double-link-->
- [www.silverstripe.com](https://www.silverstripe.com) - Silverstripe Ltd.，CMS 背后的公司.

## Tools
- [SSPak](https://github.com/silverstripe/sspak) - 用于管理来自 Silverstripe 环境的数据库/资产包的工具.
- [SSPy](https://github.com/Firesphere/silverstripe-sspy)  - SSPak 的 Python 版本，可以处理更大的资产.  SSPak 最多支持 2GB，SSPy 没有限制. 但是，它的安装和设置不太容易.

### IDE Plugins
- [VSCode Silverstripe](https://marketplace.visualstudio.com/items?itemName=adrian.silverstripe) - VSCode 中 Silverstripe 模板文件的语法突出显示.
- [Jetbrains / PHPStorm Silverstripe Template Language Support](https://plugins.jetbrains.com/plugin/7201-silverstripe-template-language-support) - PHPStorm 中 Silverstripe 模板文件的语法突出显示.
- [PHPStorm / Webstorm Live Templates](https://github.com/northcreation-agency/silverstripe-php-web-storm-live-templates) - 添加各种 Silverstripe 特定代码片段的快捷方式.

## Documentation
- [API Docs](http://api.silverstripe.org/) - 自动生成的 API 文档.
- [Technical Documentation](http://doc.silverstripe.org/framework/en/)  - 对于开发人员. 解释所有核心概念.
- [Using the CMS](http://userhelp.silverstripe.org/) - 最终用户如何使用核心功能的文档.
- [TinyMCE Configuration Examples For SS3](https://github.com/jonom/silverstripe-tinytidy)

## Tutorials
- [Silverstripe Lessons](https://www.silverstripe.org/learn/lessons/) - 了解如何通过实际项目逐步构建 Silverstripe 站点.

## Blogs
- [Official Silverstripe Blog](https://www.silverstripe.org/blog/) - 欢迎投稿！
- [SilverStrip.es](http://www.silverstrip.es)  - Silverstripe 开发人员的有用发现. 欢迎投稿！

## Video Channels
- [Official StripeCon YouTube Channel](https://www.youtube.com/channel/UC38vU3H_UrdGFnc3vTJiORA) - 各种 Silverstripe 会议的演讲.
- [Official Silverstripe Vimeo Channel](https://vimeo.com/silverstripe) - 来自聚会和会议的各种视频.

## Community
- [Stack Overflow](https://stackoverflow.com/questions/tagged/silverstripe) - 关于 Stack Overflow 的 Silverstripe 相关问题.
- [Silverstripe User Slack](https://silverstripe-users.slack.com/) - 用于即时帮助或与其他开发人员交流的社区松弛通道.
  - [Invitation to Silverstripe User Slack](https://www.silverstripe.org/community/slack-signup)
- [Forum](https://forum.silverstripe.org/) - 用于提问或讨论的官方论坛.

### Conferences & Meetups
- [European Silverstripe Conference](https://www.stripecon.eu) - 每年在另一个国家.
- [Meetups](https://www.meetup.com/topics/silverstripe/all/) - 与 Silverstripe 相关的聚会列表.

## Very Useful Modules
- [SS Addons: Themes and Modules](https://addons.silverstripe.org) - 官方模块注册表.
- [SSMods: Detailed Module Search](http://ssmods.com) - 替代模块搜索.
- [Most Used Modules](https://addons.silverstripe.org/add-ons?sort=relative) - 显示下载最多的模块.

### Silverstripe 4 Recipes
- [Silverstripe Recipes on Packagist](https://packagist.org/packages/silverstripe/recipe-plugin/dependents)

### General Modules
- [Multiuser editing alert](https://github.com/silverstripe/silverstripe-multiuser-editing-alert) - 当多人编辑同一页面时，在 Silverstripe CMS 中提醒用户.

### I18N (Internationalisation)
- [Fluent](https://github.com/tractorcow-farm/silverstripe-fluent) - Silverstripe 的多语言翻译模块，无需管理单独的站点树.
- [Autotranslate](https://github.com/bratiask/silverstripe-autotranslate) - 使用 Google Translate API 创建字段的自动翻译.

### Site Search 
- [Silverstripe Searchable](https://github.com/i-lateral/silverstripe-searchable)  - 使用 Silverstripe ORM 添加更复杂的站点搜索. 使用跨多个搜索对象的搜索结果专用模板.
- [Searchable DataObjects](https://github.com/g4b0/silverstripe-searchable-dataobjects)  - 快速简单的基于 MySQL 的搜索. 对单一语言网站很有用.

#### Solr 4
- [Fulltext Search](https://github.com/silverstripe/silverstripe-fulltextsearch) - Solr4 的完整搜索界面.
- [Fulltext Search Local Solr](https://addons.silverstripe.org/add-ons/silverstripe/fulltextsearch-localsolr) - 易于安装用于本地开发的 Solr4 实例.

#### Newer Solr versions
- [Solr search](https://github.com/firesphere/silverstripe-solr-search)  - 完整的 Solr 搜索界面，支持最新的 Solr 版本. 它有子模块，例如从上面提到的“全文搜索”模块转换，以及子站点、流利等.

### Development Helpers
- [Debugbar](https://github.com/lekoala/silverstripe-debugbar/) - 在浏览器中显示调试统计信息.
- [IdeAnnotator](https://github.com/silverleague/silverstripe-ideannotator) - 在开发/构建时自动生成类注释.
- [Populate](https://github.com/dnadesign/silverstripe-populate) - 通过 YAML 文件填充您的数据库.
- [Mock DataObjects](https://github.com/unclecheese/silverstripe-mock-dataobjects) - 允许 DataObjects 使用假数据智能地自我填充.
- [Version Truncator](https://github.com/axllent/silverstripe-version-truncator) - 自动删除旧的 SiteTree 页面版本.
- [UserSwitcher](https://github.com/sheadawson/silverstripe-userswitcher) - 在前端和后端添加一个小表单，以任何用户身份快速登录.
- [Masquerade](https://github.com/dhensby/silverstripe-masquerade)  - 允许管理员以另一个“会员”身份“登录”. 这对于调试和远程支持很有用.

### Fancy Form Fields
- [Markdown Field](https://github.com/Silverstripers/markdownfield) - 可以替换您的 HTMLEditorFields（使用 TinyMCE），以便您可以使用 Markdown 语法.
- [Code Editor Field](https://github.com/nathancox/silverstripe-codeeditorfield) - 为您提供语法高亮的文本区域字段 - 非常适合基于 CMS 的 YAML 或 HTML.

## Virtualisation

### Vagrant

没有像 Laravel 有它的 homestead box 那样的官方 box. 但是，您可以使用一些适用于 Vagrant 的好盒子：
- [Twisted Bytes](https://www.twistedbytes.nl/en/blog/php-vagrant-box/) - 有用的 vagrant box，具有多个 PHP 版本、MariaDB 或 PostgreSQL、邮件捕捉器等等.
- [Twisted Bytes Box Templates](https://derkbox.com) - 使用 Twisted Bytes vagrant box 的不同开发场景的有用模板.
- [Laravel Homestead](https://github.com/laravel/homestead) - 用于本地开发的预包装盒.
- [Scotchbox](https://box.scotch.io) - 用于本地开发的流行 LAMP/LEMP 堆栈.
- [Zauberfisch Vagrant Boxes](https://github.com/Zauberfisch/vagrant-boxes) - SS3 和 SS4 的预配置 Vagrant 盒子.

### Docker

- [brettt89/silverstripe-web](https://hub.docker.com/r/brettt89/silverstripe-web) - Apache + PHP Docker 图像，带有预安装的 PHP 模块以支持 SilverStripe.
- [brettt89/sspak](https://hub.docker.com/r/brettt89/sspak) - SSPak Docker 图像.
- [brettt89/silverstripe-solr-cwp](https://hub.docker.com/r/brettt89/silverstripe-solr-cwp) - CWP Solr Docker 图像.
