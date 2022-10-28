<div class="github-widget" data-repo="friendsofcake/awesome-cakephp"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome CakePHP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
令人惊叹的 **CakePHP 3.x+** 插件、资源和闪亮的东西的精选列表.

带有“:strawberry:”图标的插件也有与 CakePHP 4 兼容的版本.

如果您正在寻找 CakePHP 2.x 资源，请访问：
- 这 [CakePHP 2.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake2) 这个很棒的清单
- 这个维基有 [list of not-yet upgraded plugins](https://github.com/FriendsOfCake/awesome-cakephp/wiki#plugins-not-yet-upgraded-from-2x-to-3x)

您可能会发现有用的其他列表：
- [CakePHP Plugins](https://plugins.cakephp.org)
- [Awesome PHP](https://github.com/ziadoz/awesome-php)
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness)

 &gt; 对于那些想知道的人； 此列表与 plugins.cakephp.org 的不同之处在于支持
&gt; 插件子部分（而不仅仅是整个插件/repo），更细化
&gt; 分组和主要关注特定于任务的功能.



## Plugins

## APM
*应用程序性能监控插件.*

- [NewRelic plugin](https://github.com/jippi/cakephp-newrelic/tree/cake3) - 一个完整的插件，可为 CakePHP 应用程序启用完整的 New Relic 集成，包括 CLI 命名、异常发送、自定义计时等.
- [NewRelic plugin](https://github.com/brunitto/cakephp-new-relic) - 一个简单的插件，使用 New Relic PHP 代理只启用名称事务和浏览器计时.

## Architecture

- ：草莓： [Burzum/CakeServiceLayer plugin](https://github.com/burzum/cakephp-service-layer) - 服务层和领域/业务模型实现.

## Asset Management
*用于管理、压缩和缩小网站资产的工具.*

- ：草莓： [AssetCompress plugin](https://github.com/markstory/asset_compress) - CakePHP 的完整资产管理器.
- ：草莓： [AssetMix plugin](https://github.com/ishanvyas22/asset-mix) - 提供与 [Laravel Mix](https://laravel-mix.com) 资产汇编.
- [Assets plugin](https://github.com/mirko-pagliai/cakephp-assets) - 动态和“动态”资产文件.
- [Less plugin](https://github.com/elboletaire/less-cake-plugin) - CakePHP 的更少解析器插件.
- [MinifyHtml plugin](https://github.com/WyriHaximus/MinifyHtml) - 压缩 HTML 输出.

## Auditing / Logging
*用于审计和日志记录的插件.*

- ：草莓： [AuditStash plugin](https://github.com/lorenzo/audit-stash) - 灵活且坚如磐石的审计日志跟踪.
- ：草莓： [DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) - 简单和独立的日志记录到数据库而不是文件.
- ：草莓： [Muffin/Footprint plugin](https://github.com/UseMuffin/Footprint) - 允许将当前登录的用户传递到模型层的插件.
- ：草莓： [Version plugin](https://github.com/josegonzalez/cakephp-version) - 一个促进版本化数据库实体的插件.

## Authentication and Authorization
*用于实现身份验证和授权的插件和库.*

- ：草莓： [Acl plugin](https://github.com/cakephp/acl/) - 将 ACL 管理为数据库方法.
- ：草莓： [ADmad/JwtAuth plugin](https://github.com/ADmad/cakephp-jwt-auth) - 使用 JSON Web 令牌进行身份验证的插件.
- ：草莓： [ADmad/SocialAuth plugin](https://github.com/ADmad/cakephp-social-auth) - 一个插件，允许您使用 Facebook/Google/Twitter 等社交服务提供商进行身份验证，使用 [SocialConnect/auth](https://github.com/SocialConnect/auth) 图书馆的社会标志.
- ：草莓： [Authentication plugin](https://github.com/cakephp/authentication) - 官方 CakePHP 认证中间件插件.
- ：草莓： [Authorization plugin](https://github.com/cakephp/authorization) - 官方 CakePHP 授权堆栈.
- [CakeDC/NavAuth plugin](https://github.com/CakeDC/cakephp-nav-auth)  - 使用 SOAP 或 OData 服务对 Navision® 服务进行身份验证的插件. 它包括 NTLM 身份验证等.
- ：草莓： [CakeDC/Users plugin](https://github.com/CakeDC/users) - 完整的用户管理（管理面板、记住我等）、社交登录（FB、Twitter、LinkedIn、Google、Instagram）、RBAC、API 等.
- [CookieAuth plugin](https://github.com/Xety/Cake3-CookieAuth) - 一个简单的 Cake 3 插件，可自动使用 Cookie 对用户进行身份验证.
- [HierAuth plugin](https://github.com/btaens/cakephp-hier-auth) - 一个用于分层、基于角色、简单授权的 CakePHP 插件.
- [Muffin/OAuth2 plugin](https://github.com/usemuffin/oauth2) - 使用 OAuth2 身份验证 [`league/oauth2-client`](https://github.com/thephpleague/oauth2-client).
- ：草莓： [Muffin/Tokenize plugin](https://github.com/UseMuffin/Tokenize) - 用于轻松生成一次性安全令牌的事件驱动行为.
- [MultiTenant plugin](https://github.com/pronique/multitenant) - 轻松构建支持 SaaS 的 Web 应用程序.
- ：草莓： [TinyAuth plugin](https://github.com/dereuromark/cakephp-tinyauth) - 身份验证和基于角色的（单/多）授权作为非常轻量级的方法.
- ：草莓： [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) - 包含 [Passwordable behavior](https://github.com/dereuromark/cakephp-tools/blob/master/docs/Behavior/Passwordable.md) 用于密码散列的 DRY 方法.
- ：草莓： [TwoFactorAuth plugin](https://github.com/andrej-griniuk/cakephp-two-factor-auth)  - 允许使用 Google Authenticator 或类似应用程序进行双重身份验证以生成一次性代码. 基于 [RobThree/TwoFactorAuth](https://github.com/RobThree/TwoFactorAuth) 图书馆.
- [UserPermissions plugin](https://github.com/AlessandroMinoccheri/UserPermissions) - 允许用户组或单个用户查看特定页面.

## Caching
*用于缓存数据的插件.*

- ：草莓： [Cache plugin](https://github.com/dereuromark/cakephp-cache) - 用于将视图（HTML、CSV、JSON、XML 等）缓存为静态缓存文件.

## Code Analysis
*用于分析、解析和操作代码库的插件.*

- ：草莓： [CakeDC/PHPStan](https://github.com/CakeDC/cakephp-phpstan) - 一个 PHPStan 扩展来解决 CakePHP 魔术围绕静态分析器的 getter 返回类型.
- ：草莓： [IdeHelper plugin](https://github.com/dereuromark/cakephp-ide-helper) - 通过向现有代码添加注释，类似于烘焙对新代码的作用，有助于更好地支持 IDE.
- ：草莓： [TestHelper plugin](https://github.com/dereuromark/cakephp-test-helper) - 提供测试增强和 TDD 支持作为浏览器后端.

## Debugging
*用于调试和本地开发的插件.*

- [Airbrake plugin](https://github.com/chrisShick/AirbrakeCake) 一个用于将 Airbrake 与 CakePHP 无缝集成以处理错误和异常的插件.
- ：草莓： [AssociationsDebugger plugin](https://github.com/zunnu/associations-debugger) - 一个将您的模型关联绘制为图表的插件.
- ：草莓： [CakephpWhoops plugin](https://github.com/dereuromark/cakephp-whoops) - PHP errors and exceptions for cool kids with [filp/whoops](https://github.com/filp/whoops).
- ：草莓： [DebugKit plugin](https://github.com/cakephp/debug_kit) - 调试的事实标准.
- [ErrorEmail plugin](https://github.com/ebrigham1/cakephp-error-email) - 将异常/错误信息通过电子邮件发送给您的开发团队的插件.
- ：草莓： [Execution order](https://github.com/dereuromark/executionorder) - 一个演示应用程序，用于显示文件、方法和回调的执行顺序.
- [Psa/FixtureCheck plugin](https://github.com/World-Architects/cakephp-fixture-check) - 一个插件，可帮助检测实时数据库和夹具中的不匹配，以使基于夹具的测试更可靠，部署更安全.
- ：草莓： [Sentry plugin](https://github.com/Connehito/cake-sentry) 一个插件，用于将 Sentry 与 CakePHP 无缝集成以处理错误和异常.
- ：草莓： [Setup plugin](https://github.com/dereuromark/cakephp-setup) - 包含调试和维护工具的轻量级设置插件.

## Dependency Injection
*实现依赖注入设计模式的插件.*

- [PimpleDi plugin](https://github.com/rochamarcelo/cake-pimple-di) 允许基于 Pimple 库的依赖注入.
- [PipingBag plugin](https://github.com/lorenzo/piping-bag) - 依赖注入容器插件，增加了在使用之前配置对象实例及其依赖项的能力，并将它们存储到容器类中以便于访问.

## E-commerce
*用于支付和建立在线电子商务商店的插件和应用程序.*

- [PaypalWPP plugin](https://github.com/cpierce/paypal-wpp) - 用于与 Paypal Web Payments Pro 进行通信以获取有关您帐户的交易和信息.

## Email
*用于发送和解析电子邮件的插件.*

- [Elastic Email plugin](https://github.com/sprintcube/cakephp-elastic-email) - 用于通过 Elastic Email API 发送电子邮件的电子邮件传输插件.
- ：草莓： [EmailQueue plugin](https://github.com/lorenzo/cakephp-email-queue) - 带有预览和发件人外壳的电子邮件队列插件.
- [Gourmet/Email plugin](https://github.com/gourmet/email) - 电子邮件助手、布局等.
- ：草莓： [Mailgun plugin](https://github.com/narendravaghela/cakephp-mailgun) - 用于通过 Mailgun 发送电子邮件的电子邮件传输插件.
- [SendGrid plugin](https://github.com/sprintcube/cakephp-sendgrid) - 用于通过 SendGrid API 发送电子邮件的电子邮件传输插件.

## Environment
*环境插件.*

- [Environments plugin](https://github.com/josegonzalez/cakephp-environments) - 处理环境的插件.
- [Gourmet/Aroma plugin](https://github.com/gourmet/aroma) - 基于数据库的配置.
- [Settings plugin](https://github.com/cakemanager/cakephp-settings) - 通过数据库管理您的设置的插件.

## File Manipulation
*用于文件操作的插件.*

- ：草莓： [FileStorage plugin](https://github.com/burzum/cakephp-file-storage) - 抽象文件存储和上传插件.
- [FlyPie plugin](https://github.com/WyriHaximus/FlyPie) - 使用 Flysystem 抽象文件系统访问.
- [Image plugin](https://github.com/josbeir/image) - 图像行为与 Cake 内置的 TranslateBehavior 非常相似.
- ：草莓： [Josbeir/Filesystem plugin](https://github.com/josbeir/cakephp-filesystem) - 抽象 [Flysystem](https://flysystem.thephpleague.com/) + 基于文件实体的上传插件.
- ：草莓： [Josegonzalez/Upload plugin](https://github.com/FriendsOfCake/cakephp-upload) - 一个可定制的插件，使用 [Flysystem](https://flysystem.thephpleague.com/) 写入多个后端（Dropbox、FTP、S3、Local 等）.
- [Proffer plugin](https://github.com/davidyell/CakePHP3-Proffer) - 具有缩略图生成功能的可自定义上传插件.
- [Xety/Cake3Upload plugin](https://github.com/Xety/Cake3-Upload) - 一个上传文件的小插件.

## Filtering and Validation
*用于过滤和验证数据的插件.*

- [Gourmet/Filters plugin](https://github.com/gourmet/filters) - 额外的调度过滤器（维护、机器人、IP 等）.
- [Gourmet/Validation plugin](https://github.com/gourmet/validation) - 额外的验证提供者（尊重、IsoCodes 等）和规则.
- [HtmlPurifier plugin](https://github.com/burzum/cakephp-html-purifier)  - 净化器插件，具有特征、行为和助手，可让您在需要的地方进行消毒和过滤. 您也可以配置多组过滤规则.
- [HtmlPurifier plugin](https://github.com/chrisShick/CakePHP3-HtmlPurifier) - 净化器插件行为，在数据被编组到实体之前和/或在保存之前清理数据.

## Geolocation
*用于地理编码地址和处理纬度和经度的插件.*

- ：草莓： [Geo plugin](https://github.com/dereuromark/cakephp-geo) - 包含 [Geocoder behavior](https://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) 和 [GoogleMaps helper](https://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).

## HTTP
*HTTP 和客户端抽象的插件*

- ：草莓： [Http/Adapter/Cake library](https://github.com/php-http/cakephp-adapter) - 适配器 [HTTPlug](https://github.com/php-http/httplug) HTTP 客户端抽象.

## I18n
*用于 I18n（国际化）和 L10n（本地化）的插件.*

- ：草莓： [ADmad/I18n plugin](https://github.com/ADmad/cakephp-i18n) - 带有 I18n 相关工具的插件.
- ：草莓： [Cake/Localized plugin](https://github.com/cakephp/localized) - 本地化验证和即用型翻译 PO 文件.
- ：草莓： [ShadowTranslate plugin](https://github.com/AD7six/cakephp-shadow-translate) - 一个基于影子表替换核心翻译行为的插件.
- [Transifex plugin](https://github.com/dereuromark/cakephp-transifex) - 通过 Transifex API 管理 i18n PO 文件和翻译.
- [Translate plugin](https://github.com/dereuromark/cakephp-translate)  - 通过网络后端轻松管理静态内容的翻译，包括. 从 POT 文件导入，通过 API 自动建议和自动翻译.
- [Translation plugin](https://github.com/ava007/wnk_translation) - 提取pot文件，翻译字符串（手动，谷歌，社区），将翻译导出到pot文件.

## Imagery
*用于操作图像的插件.*

- ：草莓： [ADmad/Glide plugin](https://github.com/ADmad/cakephp-glide) - 一个使用插件 [Glide](https://glide.thephpleague.com/) 图像处理库.
- [HtmlToImageView plugin](https://github.com/andrej-griniuk/cakephp-html-to-image-view) - 使用将 HTML 视图渲染为图像（jpg 或 png） [wkhtmltoimage](https://wkhtmltopdf.org).
- [Imagine plugin](https://github.com/burzum/cakephp-imagine-plugin) - 一个图像处理插件和包装器 [Imagine](https://github.com/avalanche123/Imagine).
- [Thumber plugin](https://github.com/mirko-pagliai/cakephp-thumber) - 使用创建缩略图的插件 [intervention/image](https://github.com/Intervention/image).

## Libs
*不属于任何其他类别的有用库或工具.*

- [Capcake](https://github.com/jadb/capcake) - 使用 Capistrano 部署 CakePHP 应用程序.
- [Chronos](https://github.com/cakephp/chronos) - A simple standalone DateTime API extension (successor of Carbon).
- [Composer Installers](https://github.com/composer/installers) - 一个多框架 Composer 库安装程序.
- [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - 一个包和依赖管理器.
- [Graphviz](https://github.com/alexandresalome/graphviz) - Graphviz 库.
- [Rocketeer](https://github.com/rocketeers/rocketeer) - PHP 任务运行器和部署包.
- [makallio85/YamlRoute plugin](https://github.com/makallio85/yaml-route) - 使用简单的 YAML 文件配置路由.

## Markup
*用于处理标记的插件.*

- [Gourmet/CommonMark plugin](https://github.com/gourmet/common-mark) - 添加 [CommonMark](https://commonmark.org/) 降价解析.
- ：草莓： [Markup plugin](https://github.com/dereuromark/cakephp-markup) - 允许使用基于 PHP 或 JS 的语法高亮.

## Migration
*有关迁移和升级的插件和资源.*

- ：草莓： [Migrations plugin](https://github.com/cakephp/migrations) - (DB) 迁移插件.
- ：草莓： [Upgrade app](https://github.com/cakephp/upgrade) - 2.x=&gt;3.x 和 3.x=&gt;4.x 的官方升级应用.
- ：草莓： [Upgrade app (extended)](https://github.com/dereuromark/upgrade) - 2.x=&gt;3.x 的扩展升级应用程序，介于 3.x 和一些 4.x 片段之间.
- [Upgrade/Migration Guide](https://book.cakephp.org/3.0/en/appendices.html) - 官方迁移指南.

## Miscellaneous
*其他插件和库.*

- [ActionsClass plugin](https://github.com/HavokInspiration/cakephp-actions-class) - 使您能够将控制器操作作为单个类进行管理.
- ：草莓： [Ajax plugin](https://github.com/dereuromark/cakephp-ajax) - 简化处理 AJAX 请求的插件.
- [CakeAdmin plugin](https://github.com/cakemanager/cakephp-cakeadmin) - 带有内置管理区域的不稳定用户管理插件.
- ：草莓： [CakeDC/Enum plugin](https://github.com/CakeDC/enum) - 为您的应用添加枚举列表支持的插件.
- ：草莓： [CakeDto plugin](https://github.com/dereuromark/cakephp-dto) - 快速为您的应用程序生成有用的数据传输对象（可变/不可变），替换凌乱的数组并通过类型提示和自动完成来利用您的 IDE.
- ：草莓： [CakeImpersonate plugin](https://github.com/jomweb/CakeImpersonate)  - 存储当前身份验证会话并为模拟用户创建新会话的组件. 用户无需重新登录即可恢复到原始身份验证会话.
- [CakeMiddlewares](https://github.com/chrisShick/CakeMiddlewares) - Cakephp 中间件的集合.
- ：草莓： [Calendar plugin](https://github.com/dereuromark/cakephp-calendar)  - 用于生成基本日历. 包括用于 ICS 日历文件生成的 IcalView.
- [Comments plugin](https://github.com/Kareylo/CakePHP-Comments) - 一个完全可定制的评论插件.
- [CurrencyConverter plugin](https://github.com/AlessandroMinoccheri/cakephp-currency-converter) - 将货币转换为另一种货币的插件.
- [Dashboard plugin](https://github.com/gourmet/dashboard) - 为您的蛋糕构建漂亮的仪表板.
- [DatabaseBackup plugin](https://github.com/mirko-pagliai/cakephp-database-backup) - 用于导出、导入和管理数据库备份的插件.
- ：草莓： [Feedback plugin](https://github.com/dereuromark/cakephp-feedback)  - 允许访问者发送快速简便的反馈，包括. 通过侧边栏形式的屏幕截图.
- ：草莓： [Flash plugin](https://github.com/dereuromark/cakephp-flash) - 为您的应用程序提供更强大的闪存消息.
- ：草莓： [OPCache Preloader](https://github.com/cnizzardini/cakephp-preloader) - CakePHP 4.x 应用程序的 OPCache 预加载器. 
- [OrcaServices/Heartbeat plugin](https://github.com/orca-services/cakephp-heartbeat/) - 监控您的应用程序的心跳（例如，数据库是否可用并且是最新的）.
- [Inertia plugin](https://github.com/ishanvyas22/cakephp-inertiajs) - Inertia.js 的服务器端适配器.
- [Interval plugin](https://github.com/LubosRemplik/CakePHP-Interval) - 将秒转换为人类可读的字符串（字符串到秒），使用营业时间（1 周 = 5 天，1 天 = 8 小时）.
- [LinkScanner plugin](https://github.com/mirko-pagliai/cakephp-link-scanner) - 递归扫描链接的插件.
- [Robotusers/Tactician plugin](https://github.com/robotusers/cakephp-tactician) - Tactician 命令总线集成工具.
- ：草莓： [Setup:Maintenance](https://github.com/dereuromark/cakephp-setup/blob/master/docs/Maintenance/Maintenance.md) - 维护 shell 进入维护模式，用于所有带有可选 IP 白名单的请求.
- ：草莓： [Shim plugin](https://github.com/dereuromark/cakephp-shim) - 一个包含有用垫片和改进的插件，作为您应用程序的基础.
- [TokenVerify plugin](https://github.com/mosaxiv/cakephp-token-verify) - 轻松发布可用于邮件身份验证的令牌.
- ：草莓： [Tools plugin](https://github.com/dereuromark/cakephp-tools) - 包含许多有用的库、助手、行为、组件、shell 等.
- [UserTools plugin](https://github.com/burzum/cakephp-user-tools)  - 用于登录、注册、密码重置等的用户工具. 像 CRUD 一样开箱即用，并且高度可配置.
- [Utils plugin](https://github.com/cakemanager/cakephp-utils) - 包含有用的组件（Authorizer、Menu）和行为（WhoDidIt、Uploadable、Metas、Stateable）.
- [Wrench plugin](https://github.com/HavokInspiration/wrench)  - 维护模式插件. 易于扩展和定制.
- [Yaml plugin](https://github.com/guemidiborhane/Cake-Yaml) - 用于使用 YAML 配置文件而不是 PHP 数组.

## Navigation
*用于构建导航结构的工具.*

- ：草莓： [Icings/Menu plugin](https://github.com/icings/menu) - 一个 [KnpMenu](https://github.com/KnpLabs/KnpMenu) CakePHP 的经验丰富的菜单插件.

## NoSQL
*用于“NoSQL”后端的插件.*

- [Monga plugin](https://github.com/lewestopher/cakephp-monga) - 使用提供对 MongoDB 数据源的访问 [`thephpleague/monga`](https://github.com/thephpleague/monga).

## Notifications
*用于通知软件的插件.*

- [ker0x/CakeGcm plugin](https://github.com/ker0x/CakeGCM) - 通过 Google Cloud Messaging 将下游消息发送到 Android 或 iOS 设备的插件.
- [Notifier plugin](https://github.com/cakemanager/cakephp-notifier) - 一个让创建和阅读通知变得容易的插件.
- [ker0x/Push plugin](https://github.com/ker0x/cakephp-push) - 通过 Firebase 云消息传递等服务发送推送通知的插件.

## ORM / Database / Datamapping
*实现对象关系映射或数据映射技术的插件.*

- ：草莓： [ADmad/Sequence plugin](https://github.com/ADmad/cakephp-sequence) - 维护有序记录列表的行为.
- ：草莓： [CakeDecimal plugin](https://github.com/dereuromark/cakephp-decimal) - 处理小数的值对象方法.
- ：草莓： [Duplicatable plugin](https://github.com/riesenia/cakephp-duplicatable) - 复制实体（包括相关数据）的行为.
- [Fetchable plugin](https://github.com/riesenia/cakephp-fetchable) - 从缓存/内存中获取实体的行为.
- ：草莓： [Lampager/Cake plugin](https://github.com/lampager/lampager-cakephp) - 快速分页，无需使用 OFFSET.
- [JeremyHarris/LazyLoad plugin](https://github.com/jeremyharris/cakephp-lazyload) - 实体的关联惰性加载器.
- [Lqdt/OrmJson plugin](https://github.com/liqueurdetoile/cakephp-orm-json) - 通过 CakePHP ORM 在 JSON 类型字段中选择、查找、获取和设置属性和值的行为和特征.
- [Money plugin](https://github.com/gourmet/money) - CakePHP 实体的货币数据类型使用 [sebastianbergmann/money](https://github.com/sebastianbergmann/money).
- ：草莓： [Muffin/Orderly plugin](https://github.com/usemuffin/orderly) - 允许为您的表格设置默认顺序.
- ：草莓： [Muffin/Sti plugin](https://github.com/UseMuffin/Sti) - CakePHP 的单表继承. 
- ：草莓： [Muffin/Trash plugin](https://github.com/usemuffin/trash) - CakePHP 的软删除行为.
- [PersistRelatedData plugin](https://github.com/riesenia/persist-related-data) - 保持相关模型的选定字段的行为.
- [Robotusers/Excel plugin](https://github.com/robotusers/cakephp-excel) - PHPExcel 的 ORM 包装器.
- ：草莓： [Robotusers/TableInheritance plugin](https://github.com/robotusers/cakephp-table-inheritance) - 单表继承 (STI) 插件.
- ：草莓： [RowLocker plugin](https://github.com/lorenzo/row-locker) - 表中行的排他锁.
- [Serializeable Data Types plugin](https://github.com/burzum/cakephp-serialize-data-types) - 将数据库内容序列化为 JSON 或使用 phps 序列化函数.
- ：草莓： [Muffin/Webservices ORM plugin](https://github.com/usemuffin/webservice) - 一个类似 ORM 的 web 服务接口.
- ：草莓： [Connehito/CakephpMasterReplica plugin](https://github.com/Connehito/cakephp-master-replica) - 切换主/副本数据库连接.
- ：草莓： [Itosho/EasyQuery plugin](https://github.com/itosho/easy-query) - 轻松生成一些复杂查询的行为，例如（批量）插入/更新插入等.
- ：草莓： [Icings/Partitionable plugin](https://github.com/icings/partitionable) - 可分区的关联允许对每个组进行基本限制.

## PDF
*用于处理 PDF 文件的插件和软件.*

- ：草莓： [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) - 一个围绕 PDF 生成的插件.

## Queue
*用于处理事件和任务队列的插件.*

- [CakeResque plugin](https://github.com/wa0x6e/Cake-Resque) - Resque 的插件，一个用于创建后台作业的库.
- ：草莓： [CakeQueuesadilla plugin](https://github.com/josegonzalez/cakephp-queuesadilla) - 提供与各种后端（BeanstalkD、MySQL、Redis 等）的队列集成的插件.
- [Gearman plugin](https://github.com/cvo-technologies/cakephp-gearman) - 一个用于将 CakePHP 任务卸载到 Gearman 作业服务器的插件.
- ：草莓： [Queue plugin](https://github.com/dereuromark/cakephp-queue) - 最小且无依赖的队列解决方案.

## REST and API
*用于开发 REST-ful API 的插件和 Web 工具.*

- ：草莓： [Alt3/Swagger plugin](https://github.com/alt3/cakephp-swagger) - 使用 swagger-php 和 swagger-ui 的 CakePHP API 的 Swagger 2.0 文档.
- [Alt3/ValidationExposer plugin](https://github.com/alt3/cakephp-validation-exposer) - 轻松公开您的应用程序的验证规则.
- [ApiPagination plugin](https://github.com/bcrowe/cakephp-api-pagination) - 将来自 CakePHP 的分页器的分页信息注入到序列化的 JsonView 和 XmlView 响应中.
- ：草莓： [CakeDC/Api plugin](https://github.com/CakeDC/cakephp-api)  - 提供完整 API 的多合一解决方案. 它包括版本控制、渲染器、CRUD、身份验证、扩展（分页、过滤器、HATEOAS）等等.
- [Cors plugin](https://github.com/ozee31/cakephp-cors) - 使用中间件激活 CORS.
- [Cors plugin](https://github.com/snelg/cakephp-cors) - 用于将 CORS 标头添加到指定端点的轻量级插件.
- [CrudJsonApi plugin](https://github.com/FriendsOfCake/crud-json-api) - 用于建筑的粗鲁监听器 [JSON API](https://jsonapi.org/) 兼容的 API.
- ：草莓： [FractalTransformerView plugin](https://github.com/andrej-griniuk/cakephp-fractal-transformer-view) - 一个允许使用的插件 [Fractal transformers](https://fractal.thephpleague.com/transformers/) 用于您的 API 输出.
- ：草莓： [MixerApi](https://mixerapi.com) - 为您的团队 CakePHP 项目简化现代 RESTful API 的开发.
- ：草莓： [SwaggerBake plugin](https://github.com/cnizzardini/cakephp-swagger-bake) - 此插件自动从您现有的模型和路线构建 OpenAPI，以在 Swagger 和 Redoc 中显示.

## Search
*用于索引和执行数据搜索查询的插件和软件.*

- ：草莓： [Cake/ElasticSearch plugin](https://github.com/cakephp/elastic-search) - 使用替代 ORM [Elasticsearch](https://www.elastic.co/) 作为它的后端.
- ：草莓： [PlumSearch plugin](https://github.com/skie/plum_search)  - 搜索插件实现自定义、灵活和可扩展的搜索策略. 实现 PRG 模式.
- ：草莓： [Search plugin](https://github.com/FriendsOfCake/search) - 使用 PRG 模式为分页视图提供简单的搜索/过滤.
- [SphinxSearch plugin](https://github.com/voycey/cakephp-sphinxsearch) - 查询 SphinxSearch 索引的基本行为实现.
- ：草莓： [Tags plugin](https://github.com/dereuromark/cakephp-tags) - 用于标记和查找标记的记录.

## Security
*有关安全性的插件和信息，防止漏洞和防止 XSS 等.*

- ：草莓： [Bruteforce](https://github.com/Ali1/cakephp-bruteforce/) - 在不涉及数据库的情况下将蛮力保护添加到您的安装中的简单方法.
- [BryanCrowe/EncryptedType](https://github.com/bcrowe/cakephp-encrypted-type) - 使加密数据类型能够存储在数据库中的简单解决方案.
- ：草莓： [Captcha plugin](https://github.com/dereuromark/cakephp-captcha) - 简单、不显眼且可扩展的验证码解决方案，默认提供基于图像的数学验证码.
- [CipherBehavior plugin](https://github.com/adayth/cakephp-cipher-behavior)  - 使用此行为加密您的实体数据. 加密是使用 CakePHP Security 类在 PHP 级别完成的.
- ：草莓： [Expose plugin](https://github.com/dereuromark/cakephp-expose) - 通过额外的 UUID 而不是它们的 AIID 主键公开实体，以混淆与这些数字排序值关联的那些 ID 和数据.
- ：草莓： [Muffin/Obfuscate plugin](https://github.com/usemuffin/obfuscate) - 使用 UUID、HashId、Optimus、Tiny 和/或自定义混淆策略的主键混淆/缩短.
- ：草莓： [Muffin/Throttle plugin](https://github.com/usemuffin/throttle) - 用于速率限制 (API) 请求的插件.
- ：草莓： [Recaptcha plugin](https://github.com/ctlabvn/Recaptcha) - 简单、轻量级的 Google Recaptcha v2.
- [Recaptcha Mailhide plugin](https://github.com/mirko-pagliai/cakephp-recaptcha-mailhide) - 一个允许您使用 reCAPTCHA 隐藏电子邮件地址的插件.
- [StopSpam plugin](https://github.com/mirko-pagliai/cakephp-stop-spam) - 允许您检查用户名、电子邮件地址或 IP 地址是否已被报告为垃圾邮件发送者的插件.

## SEO
*搜索引擎优化.*

- ：草莓： [Muffin/Slug plugin](https://github.com/UseMuffin/Slug)  - 用于生成 slug 并通过 slug 查找记录的插件. 使用可插拔架构，允许使用您自己的 slug 生成器类.
- [Seo plugin](https://github.com/orgasmicnightmare/cakephp-seo) - 自动创建和管理您的 SEO 标签.
- [Sluggable plugin](https://github.com/Xety/Cake3-Sluggable) - 一个简单的 Cake3 插件，用于 slug 字段并通过 slug 查找记录.
- ：草莓： [Tools:Slugged](https://github.com/dereuromark/cakephp-tools) - 包含 Slugged 行为以从标题自动生成与 URL 兼容的 slug.

## Skeleton
*围绕应用程序骨架的插件和存储库.*

- ：草莓： [App template](https://github.com/cakephp/app) - 一个与作曲家一起使用的空 CakePHP 项目.
- ：草莓： [Crud plugin](https://github.com/FriendsOfCake/crud) - 类固醇上的 CakePHP 应用程序开发 - 快速原型设计/脚手架和生产就绪代码.
- ：草莓： [MixerApi/Bake](https://github.com/mixerapi/bake) - 用于生成 RESTful 控制器的烘焙主题.
- [Plugin Skeleton](https://github.com/Xety/Cake3-PluginSkeleton) - 创建 Cake3 插件的骨架示例.

## Social
*围绕社交功能的插件.*

- [CakeDC/Forum plugin](https://github.com/CakeDC/cakephp-forum) - 论坛插件，包括类别、线程和回复、报告消息、版主、管理界面等.
- ：草莓： [Ratings plugin](https://github.com/dereuromark/cakephp-ratings) - 允许用户对记录进行评分并显示评分.
- [SocialShare plugin](https://github.com/drmonkeyninja/cakephp-social-share) - 用于在社交网络上共享内容的链接生成器.

## Templating
*用于模板和词法分析的插件.*

- [Address plugin](https://github.com/drmonkeyninja/cakephp-address) - 输出标记地址的地址助手.
- ：草莓： [Bake plugin](https://github.com/cakephp/bake) - 提供代码生成功能.
- [Bootstrap plugin](https://github.com/elboletaire/twbs-cake-plugin) - 支持 LESS 的 Bootstrap 3 插件.
- ：草莓： [BootstrapUI plugin](https://github.com/friendsofcake/bootstrap-ui) - Bootstrap 3 集成.
- [CakeExcel plugin](https://github.com/dakota/CakeExcel) - 用于生成 XLSX 文件的 Excel 视图.
- [Chocolate plugin](https://github.com/commercial-hippie/chocolate) - 前端框架 FormHelper 扩展.
- [CommonMark plugin](https://github.com/gourmet/common-mark) - 添加 [CommonMark](https://commonmark.org) (markdown) 对模型和视图的支持.
- ：草莓： [CsvView plugin](https://github.com/FriendsOfCake/cakephp-csvview) - 一个易于生成 CSV 的视图类.
- [Datalist plugin](https://github.com/rrd108/cakephp-datalist) - 支持 HTML5 数据列表元素，可以在相关模型中创建新条目.
- ：草莓： [Feed plugin](https://github.com/dereuromark/cakephp-feed) - 包含一个 RssView 类以轻松生成（复杂）RSS 提要.
- [InlineCss plugin](https://github.com/drmonkeyninja/cakephp-inline-css) - 将 HTML 样式块转换为视图模板上的内联 CSS 的插件（用于电子邮件模板）.
- [JadeView plugin](https://github.com/clthck/cakephp-jade) - Jade 模板引擎插件.
- [Liquid plugin](https://github.com/gourmet/liquid) - 使用 Liquid 模板语言进行视图的插件.
- ：草莓： [Meta plugin](https://github.com/dereuromark/cakephp-meta) - 使处理元标记和 SEO 相关的 HTML 标记变得干燥和容易.
- [SocialMeta plugin](https://github.com/gourmet/social-meta) - 添加对 Facebook 的 OpenGraph 和 Twitter 的 Card 元标记的支持.
- ：草莓： [TwigView plugin](https://github.com/cakephp/twig-view) - 将 Twig 模板语言用于视图的插件.
- [VideoEmbed plugin](https://github.com/drmonkeyninja/cakephp-video-helper) - 嵌入 YouTube、Vimeo 和 Dailymotion 视频的助手.

## Testing
*用于测试代码库和生成测试数据的插件/工具.*

- [CakePHP Codeception module](https://github.com/cakephp/codeception) - 官方 CakePHP 集成 [Codeception](https://codeception.com).
- [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) - 官方 CakePHP CS 规则.
- ：草莓： [CakephpFixtureFactories plugin](https://github.com/pakacuda/cakephp-fixture-factories) - 在测试的基础上动态创建你的fixture，加速你的测试的编写和维护.
- [Faker plugin](https://github.com/gourmet/faker) - [Faker](https://github.com/fzaninotto/Faker) 支持 CakePHP 固定装置.
- [Fixtures plugin](https://github.com/LubosRemplik/CakePHP-Fixtures) - 夹具插件可读取现有夹具并创建表/插入数据以快速启动应用程序.
- [FriendsOfCake/Fixturize plugin](https://github.com/FriendsOfCake/fixturize) - 通过减少插入量（仅限mysql）运行测试套件时更有效地插入夹具.
- [Gourmet/Muffin plugin](https://github.com/gourmet/muffin) - [FactoryMuffin](https://github.com/thephpleague/factory-muffin) 支持 CakePHP 固定记录.

## Third Party APIs
*用于访问第三方 API 的插件.*

- [CakeTmdb plugin](https://github.com/drmonkeyninja/cakephp-tmdb) - 电影数据库 (TMDB) API 集成.
- [CloudflareDeploy Plugin](https://github.com/challgren/cakephp-cloudflare-deploy) - 用于使用 Cloudflare 部署 CakePHP 应用程序的有用控制台命令.
- [GitHub plugin](https://github.com/cvo-technologies/cakephp-github) - 允许使用 GitHub REST API 访问 [Webservice](https://github.com/UseMuffin/Webservice) 甲骨文.
- [Jira plugin](https://github.com/fr3nch13/cakephp-jira) - 提供一个帮助程序以允许使用访问 Jira 的 REST API [lesstif/php-jira-rest-client](https://github.com/lesstif/php-jira-rest-client) 作为卖方. 当前只读访问.
- [Ratchet plugin](https://github.com/WyriHaximus/Ratchet) - 将 Ratchet websocket 包引入 CakePHP.
- [Salesforce plugin](https://github.com/voycey/cakephp-salesforce) - 允许使用 CakePHP 的 ORM 来查询和与 Salesforce 企业实例交互.
- [Twitter plugin](https://github.com/cvo-technologies/cakephp-twitter) - 允许使用 Twitter REST 和流 API 访问 [Webservice](https://github.com/UseMuffin/Webservice) 甲骨文.

## Software
*用于创建开发环境的软件.*

## Development Environment
*用于创建沙盒开发环境的软件和工具.*

- [CakePHP.gitignore](https://github.com/github/gitignore/blob/master/CakePHP.gitignore) - .gitignore 文件提案.
- ：草莓： [CakePHP Docker](https://github.com/cnizzardini/cakephp-docker) - 用于 docker 和 kubernetes 设置的 cakephp/app 模板.
- [CakePHP Vagrant Setup](https://github.com/cpierce/cakephp-vagrant-setup) - 用于启动多个 CakePHP 3.x Vanilla 开发环境的工具.
- [Devilbox](https://devilbox.readthedocs.io/en/latest/) - 一个用于（CakePHP）应用程序的 docker 开发环境，可以自动设置，包括很多工具.
- [Docker](https://github.com/stefanvangastel/docker-cakephp) - docker 容器环境中的 CakePHP.
- ：草莓： [Galley](https://gitlab.com/amayer5125/galley) - 一个用于 CakePHP 开发的小型 Docker 开发环境，其中包括一个简单的命令行实用程序.
- [Mixer](https://github.com/CakeDC/mixer) - 一个用于发现和管理 CakePHP 插件的插件.
- [NetBeans](https://github.com/junichi11/cakephp3-netbeans) - 这个包在 NetBeans 8.1+ 中提供对 CakePHP 的支持.
- [Oven](https://github.com/CakeDC/oven) - 使用 1 个文件和 1 次单击设置您最喜欢的框架.
- [PhpStorm plugin](https://github.com/skie/PhpStorm) - CakePHP 自动完成对 PhpStorm IDE 中控制台命令的支持.
- [Puppet](https://puppetlabs.com/) - 服务器自动化框架和应用程序.
- [Vagrant](https://www.vagrantup.com/) - 一个可移植的开发环境实用程序.

可以找到 IDE 特定的兼容性信息和提示 [here](https://github.com/dereuromark/cakephp-ide-helper/wiki#ide-support-and-tips).

## Web Applications

## CMS and applications built on CakePHP

- [CakeBlog](https://github.com/gwhitcher/CakeBlog) - 开源博客软件.
- [Croogo](https://croogo.org) - CMS软件
- [QuickApps-CMS](https://github.com/quickapps/cms) - 开源内容管理系统.

## Demo
*基于 Web（演示）的应用程序和工具.*

- [BlogMVC](https://github.com/Kareylo/BlogMVC-CakePHP3) - 基于 CakePHP 的简单博客示例 [BlogMVC Project](https://github.com/Grafikart/BlogMVC).
- [Bookmarkr](https://github.com/lorenzo/cakephp3-bookmarkr) 使用 CRUD 插件构建的书签应用程序.
- [CakeFest](http://cakefest.dereuromark.de/) - 围绕年度 CakePHP 大会“CakeFest”的演示应用程序.
- [Croogo 3.x](http://demo.croogo.org/3.0) - Croogo 3.x 演示
- [Fluentd + Grafana Loki demo application](https://github.com/ishanvyas22/cakephp-loki-demo) - 将 CakePHP docker 容器日志发送到的演示应用程序 [Grafana Loki](https://grafana.com/logs/) 通过 [Fluentd](https://www.fluentd.org/).
- [RealWorld](https://github.com/gothinkster/cakephp-realworld-example-app) - 包含真实世界示例（CRUD、auth、高级模式等）的示例 CakePHP 代码库 [RealWorld](https://github.com/gothinkster/realworld-example-apps) 规范和 API.
- [Sandbox](https://sandbox.dereuromark.de) - 一个带有大量演示和插件展示的沙盒 CakePHP 应用程序.
- [Query Examples](https://github.com/lorenzo/cakephp3-examples) Advanced query building examples.
- [Xeta](https://github.com/XetaIO/Xeta) - 帮助人们开始使用 CakePHP 的资源.
- [Vue.js Demo App](https://github.com/ishanvyas22/cakephpvue-spa) - CakePHP + VueJS 单页应用程序框架.

## Resources
各种资源，例如书籍、网站和文章，用于提高您的 CakePHP 开发技能和知识.

## Help
*在哪里获得帮助.*

- [CakePHP-FR.org](http://cakephp-fr.org) - 法语社区网站.
- [Official CakePHP Forum](https://discourse.cakephp.org/) - 这是针对一般问题等.
- [IRC Channel](https://www.dereuromark.de/2013/01/27/irc-cakephp-channel/) - 与其他开发人员和核心开发人员进行实时聊天/讨论.
- [stackoverflow.com/questions/tagged/cakephp](https://stackoverflow.com/questions/tagged/cakephp) - 这是针对特定问题的，最好是一些示例代码.

## CakePHP Websites
*有用的和最新的 CakePHP 相关的网站和博客.*

- [CakeDC](http://www.cakedc.com/articles) - 关于 CakePHP 的文章.
- [dereuromark.de](https://www.dereuromark.de) - 一个广泛的 CakePHP 核心开发博客.
- [jedistirfry.co.uk](http://jedistirfry.co.uk) - 一个与 CakePHP 相关的开发博客.
- [josediazgonzalez.com](http://josediazgonzalez.com/) - 一个主要与 CakePHP 相关的核心开发博客.
- [mark-story.com](http://mark-story.com) - CakePHP 领导开发博客.
- [waltherlalk.com](http://waltherlalk.com) - CakePHP 相关的核心开发博客.

## CakePHP Books and Articles
*很棒的 CakePHP 相关 (e) 书籍和其他阅读材料.*

## CakePHP Videos
*精彩的 CakePHP 相关视频.*

- [CakePHP](https://www.youtube.com/user/CakePHP) - 关于 CakePHP 视频的频道.


## CakePHP Tutorials
*必做教程.*

- [Official Blog tutorial](https://book.cakephp.org/3.0/en/tutorials-and-examples/blog/blog.html)
- ：草莓： [Official Content Management Tutorial](https://book.cakephp.org/4/en/tutorials-and-examples/cms/installation.html)

## CakePHP Reading and Listening
*文档和 CakePHP 相关的阅读和听力材料.*

- [CakePHP Cookbook(!)](https://book.cakephp.org/) - 官方 CakePHP 文档.

## CakePHP Internals Reading
*阅读与 CakePHP 内部结构和决策相关的材料.*

- [Top 10 (and more) core contributors](https://github.com/cakephp/cakephp/graphs/contributors) - 帮他们一把.

## Conferences

## Official
*国际会议.*

- [cakefest.org](https://cakefest.org/) - 年度 CakePHP 会议.

## MeetUps
*区域聚会.*

- [CakePHP-DE](https://www.meetup.com/CakePHP-DE) - 德国的聚会.

## Contributing
请参见 [CONTRIBUTING](https://github.com/friendsofcake/awesome-cakephp/blob/master/CONTRIBUTING.md) 详情.

## Credits
awesome-cakephp 由 [dereuromark](https://github.com/dereuromark) 目前由他和 FriendsOfCake 小组维护. 谢谢你们 [contributors](https://github.com/FriendsOfCake/awesome-cakephp/graphs/contributors)， 也.
