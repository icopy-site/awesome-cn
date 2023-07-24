<div class="github-widget" data-repo="DavidLambauer/awesome-magento2"></div>
## Awesome Magento 2 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

<div align="center">
	<a href="https://vshymanskyy.github.io/StandWithUkraine">
		<img width="500" height="350" src="https://raw.githubusercontent.com/DavidLambauer/awesome-magento2/master/media/logo-ua.svg?sanitize=true" alt="Awesome">
		<img src="https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg">
	</a>
	<br>
	<br>
	<br>
	<br>
	<hr>
</div>


&gt; 精彩的 Magento 2 扩展和资源的精选列表.

- [What is an awesome list?](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
- [Contribution guide](https://github.com/DavidLambauer/awesome-magento2/blob/master/contributing.md) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/DavidLambauer/awesome-magento2/issues)

---



---

## What is Magento?

 Magento 是一个开源电子商务应用程序，可让您创建网上商店. 我们经常谈论前端（
店面（客户购买产品的店面）和后端（Magento 管理面板，客户和产品在其中进行
管理）. 开源位指的是 Magento 的源代码（PHP、HTML、CSS、JS、XML 等）
根据开源许可证 (OSLv3) 分发，允许任何人重用代码并对其进行更改. 这
开源方面导致了Magento产品的广泛流行，以至于我们经常使用Magento这个词来表示
指的是产品、其周围的社区或两者.

Magento 由一家名为 Varien 的公司创立，随着 Magento 版本 1（首次发布于 2008 年），受欢迎程度开始增长.
Magento 版本 2 于 2015 年 11 月首次发布，但由于其复杂性而在采用时遇到了问题
架构和过时的功能（KnockoutJS、RequireJS、Zend Framework 1）. 在店面部分，
这导致了各种新的前端.  2018 年，Magento 被 Adob​​e 收购. 后来整合了Magento Enterprise
作为 Adob​​e Commerce Cloud 进入 Adob​​e 云，而 Magento 社区版则被重新标记为 Magento 开源. 在
社区中，Adobe 是否会长期维持 Magento 开源存在不确定性
社区会认为合适. 这种不确定性催生了一项名为 Mage-OS 的社区倡议.

另请参阅：

- [en.wikipedia.org/wiki/Magento](https://en.wikipedia.org/wiki/Magento)

## Events: Meet the community

- [MageUnconference 🇩🇪](https://www.mageunconference.org/) - 德国举办的 Magento Unconference.
- [MageUnconference 🇳🇱](https://mageunconference.nl/) - 在荷兰举行的 Magento Unconference.
- [meet commerce](https://meetcommerce.tech/) - 在西班牙马德里举行的以电子商务为重点的会议.

### Meet Magento

Meet Magento 活动将所有人聚集在一起，从商家到开发人员、解决方案和技术提供商， 
营销人员——我们继续扩张. 

- [Meet Magento New York](https://meetmagentonyc.com/) - 认识 Magento 纽约 
- [Meet Magento UK](https://uk.meet-magento.com/) - 认识 Magento 英国 
- [Meet Magento Baltics](https://meetmagentobaltics.com/) - 认识 Magento Baltics

## Frontends
Magento 2 的店面可以采用多种方式设计：

 - **Luma** (`Magento/luma`) - 这实际上是 Magento 2 本身的默认演示主题，它再次从核心扩展的 `Magento/blank` 扩展而来. 但更常见的是，Luma 这个名称指的是整个堆栈：XML 布局生成块和容器的树形结构，最终通过 PHTML 模板呈现. 服务器端渲染的 HTML 通过 CSS（从 LESS 源文件编译）和 JavaScript（RequireJS、KnockoutJS、jQuery）进行了丰富.
 - **Adobe PWA Studio** - 一个新的无头前端，由 Adob​​e/Magento 创建，基于 ReactJS. 它对 Magento GraphQL API 进行 GraphQL 调用以检索数据. 前端提供 Venia（演示主题和 UI 组件库）、Peregrine（React hooks）、Buildpack（Webpack 配置）和 UPWARD（用于 SSR 和图像优化的中间件）. 
- **好的** （[hyva.io](https://hyva.io/) ) - Luma 的替代方案，用 TailwindCSS 替换 LESS/CSS，用 AlpineJS 替换 JavaScript. 目前，它只能通过商业许可证获得. 但对于这个价格，团队努力为第三方模块创建兼容性模块，提供支持并使整个解决方案变得越来越通用.
- **店面视图**
- **神灵**
- **斯堪迪PWA**
- **Breeze Evolution** - 100 页面速度得分前端主题，与所有基于 Luma 的扩展兼容. [breezefront.com](https://breezefront.com/themes)

## Tools

- [n98-magerun2](https://github.com/netz98/n98-magerun2) - Magento 2 的 CLI 瑞士军刀.
- [RabbitMQ Retry Mechanism](https://github.com/run-as-root/magento2-message-queue-retry) - Magento 2 扩展提供了重试 RabbitMQ 失败消息的可能性
- [Documentation Search for Alfred](https://github.com/DavidLambauer/Alfred-Workflow-Magento-2-DevDocs-Search) - 容易地
  将官方 Magento 2 搜索集成到您的 Alfred 工作流程中.
- [Tablerates Generator](https://elgentos.nl/tablerates/) - 使用在线工具生成表率.
- [Pestle](https://github.com/astorm/pestle) - Alan Storm 的代码生成工具.
- [Mage2Gen](https://mage2gen.com/) - 在线模块创建器.
- [Mage Chrome Toolbar](https://github.com/magespecialist/mage-chrome-toolbar) - 必备的 Chrome 扩展程序
  Magento 2 由 [MageSpecialist](https://github.com/magespecialist).
- [MageSpecialist DevTools for Magento 2](https://github.com/magespecialist/m2-MSP_DevTools) 开发者工具栏
- [magento2docker](https://github.com/aliuosio/magento2docker) - MariaDB、PHP、Redis、ElasticSearch 位于一个 dockerfile 中，用于快速演示和开发环境
- [markshust/docker-magento](https://github.com/markshust/docker-magento) - Mark Shust 的 Docker 配置
  马根托
- [Warden](https://github.com/davidalger/warden) - 用于使用 docker-compose 环境的 CLI 实用程序
  经过 [David Alger](https://davidalger.com/)
- [AmpersandHQ/ampersand-magento2-upgrade-patch-helper](https://github.com/AmpersandHQ/ampersand-magento2-upgrade-patch-helper)
    - 帮助程序脚本通过检测覆盖来帮助升级 magento 2 网站.
- [PhpStorm Magento2 Extension](https://github.com/magento/magento2-phpstorm-plugin) - 官方 PhpStorm Magento2
  扩大.
- [PhpInsights](https://github.com/nunomaduro/phpinsights) - PHP 质量检查（使用 Magento2 预设）
- [Tango](https://github.com/roma-glushko/tango) - 用于分析访问日志的 CLI
- [Masquerade](https://github.com/elgentos/masquerade) - Faker驱动，基于配置，与平台无关，
  与区域设置兼容的数据伪造工具
- [Magento 2 Composer patches helper](https://chrome.google.com/webstore/detail/magento-2-composer-patche/gfndadbceejgfjahpfaijcacnmdloiad)
    - Chrome 扩展，用于为 vaimo/composer-patches 创建可复制粘贴的作曲家补丁定义.
- [Migrate DB Magento 2 Commerce to Magento 2 Open-Source](https://github.com/opengento/magento2-downgrade-ee-ce)
- [Magento 2 Database Synchronizer](https://github.com/jellesiderius/mage-db-sync)  - Magento 2（和Wordpress）的数据库同步器，基于Magerun2. 轻松保持开发、预演和生产同步.
- [Subodha Magento2 Gulp Integration](https://github.com/subodha/magento-2-gulp) - Magento 2 Gulp 集成

## Open Source Extensions

### Development Utilities

- [Cypress Testing Suite](https://github.com/elgentos/magento2-cypress-testing-suite/) - 社区驱动的 Cypress
  Magento 2 测试套件
- [Config ImportExport](https://github.com/semaio/Magento2-ConfigImportExport) - 基于 CLI 的配置管理.
- [Whoops Exceptions](https://github.com/yireo/Yireo_Whoops) - Magento 2 中 Cool Kids 的 PHP 例外情况.
- [Magento Cache Clean](https://github.com/mage2tv/magento-cache-clean) - bin/magento 的替换速度更快
  缓存：使用 Vinai Kopp 的文件观察器进行清理](https://twitter.com/vinaikopp)
- [Developer Toolbar](https://github.com/mgtcommerce/Mgt_Developertoolbar) - Magento 2 开发人员工具栏.
- [Advanced Template Hints](https://github.com/ho-nl/magento2-Ho_Templatehints) - Magento 2 模板提示助手.
- Scopehints](https://github.com/avstudnitz/AvS_ScopeHint2) - 在商店配置中显示附加信息
  作者：[安德烈亚斯·冯·斯图尼茨.
- [Magento 2 Configurator](https://github.com/ctidigital/magento2-configurator) - 最初创建的 Magento 模块
  CTI Digital 使用文件创建和维护数据库变量.
- [Auto Cache Flush](https://github.com/yireo/Yireo_AutoFlushCache) - Magento 2 模块自动刷新缓存.
- [Magento 2 PHPStorm File Templates](https://github.com/lfolco/phpstorm-m2-filetemplates) - PHPStorm Magento 2 文件
  模板.
- [MageVulnDB](https://github.com/gwillem/magevulndb) - 已知的第三方 Magento 扩展的中央存储库
  安全问题.
- [Magento 2 Prometheus Exporter](https://github.com/run-as-root/magento2-prometheus-exporter) - 普罗米修斯出口商
  常见的 Magento 数据.
- [graycoreio/magento2-cors](https://github.com/graycoreio/magento2-cors) - 启用可配置的 CORS 标头
  Magento GraphQL API.
- [bitExpert/phpstan-magento](https://github.com/bitExpert/phpstan-magento) - PHPStan 的 Magento 特定扩展
- [Dot Env](https://github.com/zepgram/magento-dotenv) - Magento 2 Environment Variable Component - Implementing Symfony Dotenv.
- [Rest Client](https://github.com/zepgram/module-rest) - Magento 2 技术模块提供简单的开发模式、配置和优化，以便基于 Guzzle 客户端向外部服务发出 REST API 请求.

### Deployment

- [Deployer Magento2 Recipe](https://github.com/deployphp/deployer/blob/master/recipe/magento2.php) - Magento2
  部署配方 [deployer](https://deployer.org/).
- [Magento 2 Deployer Plus](https://github.com/jalogut/magento2-deployer-plus) - 基于deployer.org的工具来执行
  Magento 2 项目的零停机部署.
- [Github Actions for Magento2](https://github.com/extdn/github-actions-m2) - Magento 2 扩展的 GitHub Actions

### Localization

- [de_DE](https://github.com/splendidinternet/Magento2_German_LocalePack_de_DE) :de: - 德语语言包.
- [de_CH](https://github.com/staempfli/magento2-language-de-ch) - 瑞士语言包.
- [fr_FR](https://github.com/Imaginaerum/magento2-language-fr-fr) :fr: - 法语语言包.
- [da_DK](https://magentodanmark.dk/) - 丹麦语语言包.
- [es_AR](https://github.com/SemExpert/Magento2-language-es_ar) - 西班牙语（阿根廷）语言包.
- [es_ES](https://github.com/eusonlito/magento2-language-es_es) :es: - 西班牙语语言包.
- [pt_BR](https://github.com/rafaelstz/traducao_magento2_pt_br) - 巴西葡萄牙语语言包.
- [it_IT](https://github.com/mageplaza/magento-2-italian-language-pack) :it: - 意大利语.
- [nl_NL](https://github.com/magento-l10n/language-nl_NL) - 荷兰语语言包.
- [pl_PL](https://github.com/SnowdogApps/magento2-pl_pl) - 波兰语语言包.
- [tr_TR](https://github.com/hidonet/magento2-language-tr_tr) :tr: - 土耳其语语言包.
- [ro_RO](https://github.com/EaDesgin/magento2-romanian-language-pack) - 罗马尼亚语语言包.
- [fi_FL](https://github.com/mageplaza/magento-2-finnish-language-pack) - 芬兰语语言包.
- [ko_KR](https://github.com/mageplaza/magento-2-korean-language-pack) 🇰🇷 - Korean Language Package.
- [sk_SK](https://github.com/mageplaza/magento-2-slovak-language-pack) - 斯洛伐克语语言包.
- [sl_SI](https://github.com/symfony-si/magento2-sl-si) - 斯洛文尼亚语语言包.
- [en_GB](https://github.com/cubewebsites/magento2-language-en-gb) :gb: - 英国语言包.
- [hr_HR](https://marketplace.magento.com/inchoo-language-hr-hr.html) :croatia: - 克罗地亚语语言包.

### Search

- [Algolia Search Integration](https://github.com/algolia/algoliasearch-magento-2) - Algolia 搜索（SaaS）集成.
- [Elastic Suite Integration](https://github.com/Smile-SA/elasticsuite/) - 弹性套件集成.
- [FastSimpleImport2](https://github.com/firegento/FireGento_FastSimpleImport2) - Magento 2 ImportExport 功能的包装器，可从阵列导入产品和客户.
- [Disable Search Engine](https://github.com/zepgram/module-disable-search-engine) - 禁用 Elasticsearch 和全文索引以进行类别搜索.

### CMS

- [Mageplaza Blog Extension](https://github.com/mageplaza/magento-2-blog-extension) - 简单但运作良好的博客
  扩大.
- [Magento 2 Blog Extension by Magefan](https://github.com/magefan/module-blog) - Magento 2 的免费博客模块
  无限的博客文章和类别、SEO 友好、延迟加载和 AMP 支持.
- [Opengento GDPR](https://github.com/opengento/magento2-gdpr) - Magento 2 GDPR 模块是必须具有的扩展
  全球最大的电子商务 CMS. 该模块有助于遵守 GDPR.

### Marketing

- [MagePlaza Seo](https://github.com/mageplaza/magento-2-seo-extension) - 有据可查的多用途 SEO 扩展.
- [Magento 2 PDF](https://github.com/staempfli/magento2-module-pdf) - 基于PDF生成器
  在 [wkhtmltopdf](http://wkhtmltopdf.org/).
- [Google Tag Manager](https://github.com/magepal/magento2-google-tag-manager) - 带有数据的 Google 跟踪代码管理器 (GTM)
  Magento2 的层.

### Adminhtml / Backend

- [Customer Force Login](https://github.com/bitExpert/magento2-force-login) - 强制客户先登录
  访问某些页面.
- [Checkout Tester](https://github.com/yireo/Yireo_CheckoutTester2) - 用于快速测试结帐更改的扩展.
- [Preview Checkout Success Page](https://github.com/magepal/magento2-preview-checkout-success-page) - 快速并且
  轻松预览和测试您的订单确认页面，无需每次都下新订单.
- [FireGento Fast Simple Import](https://github.com/firegento/FireGento_FastSimpleImport2) - Magento 2 的包装
  ImportExport 功能，从阵列导入产品和客户
- [Magento 2 Import Framework](https://github.com/techdivision/import) - 支持通用 Magento 2 导入的库
  功能性
- [Menu Editor](https://github.com/SnowdogApps/magento2-menu) - 提供强大的菜单编辑器来替换基于类别的菜单
  Magento 2 中的菜单.
- [PageNotFound](https://github.com/experius/Magento-2-Module-PageNotFound) - 将即将到来的 404 保存在您的数据库中
  创建重定向的可能性.
- [Sentry.io](https://github.com/justbetter/magento2-sentry) - 应用程序监控和错误跟踪软件
  马真托2
- [Custom SMTP](https://github.com/magepal/magento2-gmail-smtp-app) - 配置 Magento 2 发送所有事务
  使用 Google App、Gmail、Amazon Simple Email Service (SES)、Microsoft Office365 和其他 SMTP 服务器发送电子邮件.
- [Reset Customer Password](https://github.com/Vinai/module-customer-password-command) - 设置客户密码
  bin/magento 作者： [Vinai Kopp](https://github.com/Vinai/).
- [Guest to Customer](https://github.com/magepal/magento2-guest-to-customer) - 快速轻松地转换现有客人
  结帐客户至注册客户.
- [Reset UI Bookmarks](https://github.com/magenizr/Magenizr_ResetUiBookmarks) - 重置 UI 书签允许管理员用户
  重置他们自己的 UI 书签，例如过滤器状态、列位置和应用的排序（例如“销售”&gt;“订单”）.
- [Clean Admin Menu](https://github.com/redchamps/clean-admin-menu) - 将第 3 方扩展合并到单个菜单.
- [shkoliar/magento-grid-colors](https://github.com/shkoliar/magento-grid-colors) - Magento 2 网格颜色模块
  为管理网格着色. 支持借助网格书签保存状态.
  经过 [Dmitry Shkoliar](https://shkoliar.com/)
- [extdn/extension-dashboard-m2](https://github.com/extdn/extension-dashboard-m2) - 要显示的 Magento 2 仪表板
  安装的扩展. 经过 [Magento Extension Developers Network](https://extdn.org/)
- [hivecommerce/magento2-content-fuzzyfyr](https://github.com/hivecommerce/magento2-content-fuzzyfyr) - 内容
   Magento2 的 Fuzzyfyr 模块用虚拟内容替换真实内容. 这是出于开发目的，例如保存
  准备测试数据和匹配 GDPR 限制的时间.
- [Disable Stock Reservation](https://github.com/AmpersandHQ/magento2-disable-stock-reservation) - 此模块禁用 Magento 2.3.3 中作为 MSI 一部分引入的库存预留逻辑.

### Security

- [Magento Patch Repository](https://github.com/brentwpeterson/magento-patches) - 您需要的所有 Magento 补丁
  一个地方

### Payment Service Provider

- [PAYONE](https://github.com/PAYONE-GmbH/magento-2) - PAYONE 支付集成.
- [Stripe](https://github.com/pmclain/module-stripe) - Magento 2 的 Stripe 付款.
- [Braintree Payments](https://marketplace.magento.com/paypal-module-braintree.html) - 官方 Braintree 集成
  对于 Magento2.

### Infrastructure

- [Fastly Extension](https://github.com/fastly/fastly-magento2) - Magento 2 快速集成.
- [Ethan3600/magento2-CronjobManager](https://github.com/Ethan3600/magento2-CronjobManager) - Cron 作业管理器
  马根托2.
- [Magento 2 Ngrok](https://github.com/shkoliar/magento-ngrok) - Magento 2 Ngrok 集成
- [Clean Media](https://github.com/sivaschenko/magento2-clean-media) - 提供有关媒体信息的模块
  文件和潜在的删除选项.

---

### Proprietary Extensions

- [Commercebug Debugging Extension](http://store.pulsestorm.net/products/commerce-bug-3) - Magento 2 调试扩展.
- [Magicento](http://magicento.com/) - [PHPStorm](https://www.jetbrains.com/phpstorm/) 添加Magento 2相关的插件
  功能.

---

#### Progressive Web Application

- [ScandiPWA Theme](https://github.com/scandipwa/base-theme) - 基于 React 和 Redux 的 Magento 2.3+ PWA 主题

---

## Blogs

### Personal Blogs

- [Alan Storm](http://alanstorm.com/category/magento-2/)
- [Fabian Schmengler](https://www.schmengler-se.de/)

### Company Blogs

- [Atwix](https://www.atwix.com/blog/)
- [Classy Llama](https://www.classyllama.com/blog)
- [dev98](https://dev98.de/)
- [FireBear Studio](https://firebearstudio.com/blog)
- [Fooman](http://store.fooman.co.nz/blog)
- [inchoo](http://inchoo.net/category/magento-2/)
- [M.academy](https://m.academy/blog/)
- [integer_net blog](https://www.integer-net.com/blog/)
- [MageComp](https://magecomp.com/blog/category/magento-2/)
- [bitExpert AG](https://blog.bitexpert.de/blog/tags/magento)
- [OneStepCheckout](https://blog.onestepcheckout.com/)

### Other

- MageTalk：Magento 社区播客](http://magetalk.com/) - 社区播客 [Kalen Jordan 和 [Phillip]
  杰克逊.

## Learning

- [M.academy](https://m.academy/) - 通过视频课程和课程，以最简单的方式学习 Magento 2 和 Adob​​e Commerce
- [MageTitans Italia 2016](https://www.youtube.com/playlist?list=PLwB4Uz_0hoVP3Fm_c4HfNPK5JdRD6DIDl)
- [MageTitans MCR 2016](https://www.youtube.com/playlist?list=PLwB4Uz_0hoVMOnBRS49ICbNWOU5jhNNWC)
- [MageTitans USA/Texas 2016](https://www.youtube.com/playlist?list=PLwB4Uz_0hoVOLU7LPRNL4lAmJeAv7HQ-b)
- [Max Bucknell Magento 2 Javascript](https://www.youtube.com/watch?v=tHxebA-jOSo)
- [Max Pronko DevChannel](https://www.youtube.com/channel/UCxbWGz6h6KNQsi2ughRUV2Q)
- [The Magento 2 Beginner Tutorial Class](https://www.youtube.com/playlist?list=PLtaXuX0nEZk9eL59JGE3ny-_GAU-z5X5D&utm_content=buffer797bf&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
    - 用于学习 Magento 2 的免费 YouTube 系列.
- [Vinai Kopp Mage2Katas](https://www.youtube.com/channel/UCRFDWo7jTlrpEsJxzc7WyPw)
- [Mage2.tv](https://www.mage2.tv) - Vinai Kopp 的 Magento 2 开发者截屏视频
- [magento-notes/magento2-exam-notes](https://github.com/magento-notes/magento2-exam-notes) - 准备笔记
  Magento 2 认证专业开发人员考试
- [magento-notes/magento2-cloud-developer-notes](https://github.com/magento-notes/magento2-cloud-developer-notes) -
  Magento 2 认证专业云开发人员考试准备说明
- [roma-glushko/magento2-dev-plus-exam](https://github.com/roma-glushko/magento2-dev-plus-exam) - 准备笔记
  Magento 2 认证专业开发人员 Plus 考试
- [fisheye-academy/m2cpfed-training](https://github.com/fisheye-academy/m2cpfed-training) - Magento 2 的资源
  认证专业前端开发人员考试

---

## Platforms

- [StackExchange](http://magento.stackexchange.com/) - 问答论坛.

---

## Official Resources

- [Magento Official Website](https://www.magento.com) - Magento 的官方网站.
- [Magento Developer Documentation](http://devdocs.magento.com/) - 官方开发者文档.
- [Magento Forum](https://community.magento.com/) - Magento 的社区论坛.
- [Magento Github Repository](https://github.com/magento/magento2) - Github 存储库.
- [Magento Developer Blog](https://community.magento.com/t5/Magento-DevBlog/bg-p/devblog?nobounce=) - 开发者博客
  马根托.
- [Magento 2 data migration tool](https://github.com/magento/data-migration-tool) - 官方 Magento 1 到 Magento 2
  迁移工具.
- [Magento Coding Standards](https://github.com/magento/magento-coding-standard) - 官方Magento2高级套件
  PHP_CodeSniffer 的规则.
- [Magento 2 Architecture](https://github.com/magento/architecture) - Magento 架构讨论的地方
  咬.

- Magento 大师赛 2017
    - [Peter Jaap Blaakmeer](https://twitter.com/PeterJaap) - 首席技术官 [elgentos](https://www.elgentos.nl/)
    - Carmen Bremen - 自由职业者 [neoshops](http://neoshops.de/)
    - Tony Brown - 技术总监 [space48](http://www.space48.com/)
    ——西弘和
    - 布伦特·彼得森
    - 索尼娅·里斯特尔
    ——克里斯托夫·林格莱夫
    - 亚历山大·朗奇
    ——马蒂亚斯·蔡司
    - 兹沃林斯基
    ——加布里埃尔·瓜里诺
    ——菲利普·杰克逊
    ——桑德·曼格尔
    ——拉斐尔·佩特里尼
    ——法比安·施门格勒
    ——马吕斯·斯特拉耶鲁
    ——安娜·沃尔克尔
    ——伊万·切普尔尼
    ——致威娜·科普
    - 杰西·雷茨玛

---

## List of trustworthy Extension Developers

- [Aheadworks](https://www.aheadworks.com/)
- [Altima](https://shop.altima.net.au/)
- [Blue Jalappeno](http://bluejalappeno.com/)
- [Dotmailer](https://www.dotmailer.com/)
- [Integer-net](https://www.integer-net.com/solr-magento/)
- [Genmato](https://genmato.com/)
- [Fooman](http://store.fooman.co.nz/)
- [Ebizmarts](https://ebizmarts.com/)
- [Magemail](https://magemail.co/)
- [MagePal](https://packagist.org/packages/magepal/)
- [Modulwerft](https://www.modulwerft.com/)
- [Paradox Labs](https://www.paradoxlabs.com/)
- [The Extension Lab](https://github.com/theextensionlab/)
- [Sweet Tooth](https://www.sweettoothrewards.com/)
- [Rocket Web](http://rocketweb.com/)
- [ProxiBlue](https://www.proxiblue.com.au/)
- [Unirgy](http://www.unirgy.com/)
- [WebShopApps](http://webshopapps.com/eu/)
- [Yireo](https://www.yireo.com/)
- [FireBear Studio](https://firebearstudio.com/)
- [OneStepCheckout](https://onestepcheckout.com/)

&gt; **Magento 扩展开发者网络 (ExtDN)**
&gt; Magento 扩展开发者网络 (ExtDN) 是一个经过审查的扩展开发者网络，其核心业务是
 &gt; 开发和销售优质的 Magento 扩展. 我创立 ExtDN 是为了给 Magento 扩展带来责任感和信任
 &gt; 市场.  ExtDN 成员同意对编码、版权和商业行为的高标准负责.

Explanation
by [Fooman](http://store.fooman.co.nz/blog/how-to-find-trustworthy-information-about-magento-extensions.html)

---

## Other Magento 2 related Awesome Lists

- [Mageres](https://github.com/aleron75/mageres) - Alessandro Ronchi 的 Magento 1 和 Magento 2 资源列表.
- [Awesome PHP](https://github.com/ziadoz/awesome-php) - 精选的精彩 PHP 资源列表.
- [Awesome Magento](https://github.com/sunel/awesome-magento) - 一个很棒的 Magento 列表，包含 M1 和 M2 内容混合
  经过 [sunel](https://github.com/sunel).

---

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，David Lambauer 已放弃本内容的所有版权以及相关或邻接权
work.

---

Thanks [Anna Völkl](https://github.com/avoelkl) & [Sander Mangel](https://github.com/sandermangel) 用于收集所有
语言包！

---

Thanks [MageTitans](http://www.magetitans.co.uk/) 在 YouTube 上分享演讲.
