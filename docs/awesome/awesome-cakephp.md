<div class="github-widget" data-repo="friendsofcake/awesome-cakephp"></div>
## Awesome CakePHP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
精选的CakePHP 3.x **插件，资源和闪亮的东西.

如果您正在寻找CakePHP 2.x资源，请访问：
-  [CakePHP 2.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake2) 这个很棒的清单
- 这个wiki有一个 [list of not-yet upgraded plugins](https://github.com/FriendsOfCake/awesome-cakephp/wiki#plugins-not-yet-upgraded-from-2x-to-3x)

您可能会发现有用的其他列表：
- [CakePHP Plugins](https://plugins.cakephp.org)
- [Awesome PHP](https://github.com/ziadoz/awesome-php)
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness)

 &gt;对于那些想知道的人;  这个列表与plugins.cakephp.org的不同之处在于支持
&gt;插件子部分（而不仅仅是整个插件/ repo），更精细
&gt;分组，主要关注任务特定功能.



## Plugins

## APM
*应用程序性能监控插件.*

- [NewRelic plugin](https://github.com/jippi/cakephp-newrelic/tree/cake3) - 一个完整的插件，可以为CakePHP应用程序实现完整的New Relic集成，包括CLI命名，异常发送，自定义计时等.它不依赖于New Relic代理.

- [Brunitto/NewRelic plugin](https://github.com/brunitto/cakephp-new-relic) - 一个简单的插件，它使用New Relic PHP代理为CakePHP 3应用程序启用名称事务和浏览器计时.

## Asset Management
*用于管理，压缩和缩小网站资产的工具.*

- [AssetCompress plugin](https://github.com/markstory/asset_compress) -  CakePHP的完整资产管理器.
- [Assets plugin](https://github.com/mirko-pagliai/cakephp-assets) - 动态和“动态”资产文件.
- [Less plugin](https://github.com/elboletaire/less-cake-plugin) -  CakePHP的解析器插件较少.
- [MinifyHtml plugin](https://github.com/WyriHaximus/MinifyHtml) - 压缩HTML输出.

## Auditing / Logging
*用于审计和记录的插件.*

- [AuditStash plugin](https://github.com/lorenzo/audit-stash) - 灵活且坚如磐石的审计日志跟踪.
- [DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) - 简单且独立的日志记录到数据库而不是文件.
- [Muffin/Footprint plugin](https://github.com/UseMuffin/Footprint) - 允许将当前登录用户传递给模型层的插件.
- [Version plugin](https://github.com/josegonzalez/cakephp-version) - 一个便于版本化数据库实体的插件.

## Authentication and Authorization
*用于实现身份验证和授权的插件和库.*

- [Acl plugin](https://github.com/cakephp/acl/) - 将ACL作为数据库方法管理.
- [ADmad/HybridAuth plugin](https://github.com/ADmad/CakePHP-HybridAuth) - 允许使用的插件 [HybridAuth](https://github.com/hybridauth/hybridauth) 与CakePHP的图书馆的社会标志.
- [ADmad/JwtAuth plugin](https://github.com/ADmad/cakephp-jwt-auth) - 使用JSON Web令牌进行身份验证的插件.
- [Authentication plugin](https://github.com/cakephp/authentication) - 官方CakePHP身份验证中间件插件.
- [Authorization plugin](https://github.com/cakephp/authorization) - 官方CakePHP授权堆栈.
- [CakeDC/NavAuth plugin](https://github.com/CakeDC/cakephp-nav-auth)   - 使用SOAP或OData服务对Navision®服务进行身份验证的插件.  它包括NTLM身份验证等.
- [CakeDC/Users plugin](https://github.com/CakeDC/users) - 完整的用户管理（管理面板，记住我等），社交登录（FB，Twitter，LinkedIn，谷歌，Instagram），RBAC，API等.
- [CookieAuth plugin](https://github.com/Xety/Cake3-CookieAuth) - 一个简单的Cake 3插件，可以使用Cookie自动验证用户身份.
- [HierAuth plugin](https://github.com/btaens/cakephp-hier-auth) -  CakePHP插件，用于分层，基于角色的简单授权.
- [Muffin/OAuth2 plugin](https://github.com/usemuffin/oauth2) - 使用OAuth2身份验证 [`league/oauth2-client`](https://github.com/thephpleague/oauth2-client).
- [Muffin/Tokenize plugin](https://github.com/UseMuffin/Tokenize) - 事件驱动的行为，可轻松生成一次性安全令牌.
- [MultiTenant plugin](https://github.com/pronique/multitenant) - 轻松构建支持SaaS的Web应用程序.
- [TinyAuth plugin](https://github.com/dereuromark/cakephp-tinyauth) - 认证和基于角色的（单/多）授权作为非常轻量级的方法.
- [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) - 包含 [Passwordable behavior](https://github.com/dereuromark/cakephp-tools/blob/master/docs/Behavior/Passwordable.md) 用于密码散列的DRY方法.
- [TwoFactorAuth plugin](https://github.com/andrej-griniuk/cakephp-two-factor-auth)   - 允许使用Google身份验证器或类似应用进行双因素身份验证，以生成一次性代码.  基于 [RobThree/TwoFactorAuth](https://github.com/RobThree/TwoFactorAuth) 图书馆.
- [UserPermissions plugin](https://github.com/AlessandroMinoccheri/UserPermissions) - 允许用户组或单个用户查看特定页面.

## Caching
*用于缓存数据的插件.*

- [Cache plugin](https://github.com/dereuromark/cakephp-cache) - 用于将视图（HTML，CSV，JSON，XML，...）缓存为静态缓存文件.

## Code Analysis
*用于分析，解析和操作代码库的插件.*

- [IdeHelper plugin](https://github.com/dereuromark/cakephp-ide-helper) - 通过向现有代码添加注释，帮助更好地支持IDE，类似于烘焙对新代码的注释.
- [TestHelper plugin](https://github.com/dereuromark/cakephp-test-helper) - 提供测试增强功能和TDD支持作为浏览器后端.

## Debugging
*用于调试的插件.*

- [Airbrake plugin](https://github.com/chrisShick/AirbrakeCake) 一个插件，可以将Airbrake与CakePHP无缝集成，以实现错误和异常.
- [DebugKit plugin](https://github.com/cakephp/debug_kit) - 事实上的调试标准.
- [ErrorEmail plugin](https://github.com/ebrigham1/cakephp-error-email) - 将异常/错误信息通过电子邮件发送给您的开发团队的插件.
- [Execution order](https://github.com/dereuromark/executionorder) - 一个演示应用程序，用于显示文件，方法和回调的执行顺序.
- [Psa/FixtureCheck plugin](https://github.com/World-Architects/cakephp-fixture-check) - 一个插件，可帮助检测实时DB和夹具中的不匹配，以使基于夹具的测试更可靠，部署更安全.
- [Sentry plugin](https://github.com/Connehito/cake-sentry) 一个插件，可以将Sentry与CakePHP无缝集成，以实现错误和异常.
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - 包含调试和维护工具的轻量级安装插件.
- [Whoops plugin](https://github.com/dereuromark/cakephp-whoops) - 适合酷孩子的PHP错误和例外 [filp/whoops](https://github.com/filp/whoops).

## Dependency Injection
*实现依赖注入设计模式的插件.*

- [PimpleDi plugin](https://github.com/rochamarcelo/cake-pimple-di) 允许基于Pimple库的依赖注入.
- [PipingBag plugin](https://github.com/lorenzo/piping-bag) - 依赖注入容器插件，它添加了在使用对象实例及其依赖项之前配置它们的能力，并将它们存储到容器类中以便于访问.

## E-commerce
*用于支付款项和建立在线电子商务商店的插件和应用程序.*

- [PaypalWPP plugin](https://github.com/cpierce/paypal-wpp) - 用于与Paypal Web Payments Pro进行通信的包，用于交易和有关您帐户的信息.

## Email
*用于发送和解析电子邮件的插件.*

- [Elastic Email plugin](https://github.com/sprintcube/cakephp-elastic-email) - 用于通过Elastic Email API发送电子邮件的电子邮件传输插件.
- [EmailQueue plugin](https://github.com/lorenzo/cakephp-email-queue) - 具有预览和发件人shell的电子邮件队列插件.
- [Gourmet/Email plugin](https://github.com/gourmet/email) - 电子邮件帮助，布局等.
- [Mailgun plugin](https://github.com/narendravaghela/cakephp-mailgun) - 用于通过Mailgun发送电子邮件的电子邮件传输插件.
- [SendGrid plugin](https://github.com/sprintcube/cakephp-sendgrid) - 用于通过SendGrid API发送电子邮件的电子邮件传输插件.
- [SparkPost plugin](https://github.com/syntaxera/cakephp-sparkpost-plugin) - 用于通过SparkPost API发送电子邮件的电子邮件传输插件.

## Environment
*环境插件.*

- [Environments plugin](https://github.com/josegonzalez/cakephp-environments) - Plugin to handle environments.
- [Gourmet/Aroma plugin](https://github.com/gourmet/aroma) - 基于数据库的配置.
- [Settings plugin](https://github.com/cakemanager/cakephp-settings) - 通过数据库管理设置的插件.
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - 处理非常基本环境的插件.

## Files
*用于文件操作的插件.*

- [FileStorage plugin](https://github.com/burzum/cakephp-file-storage) - 抽象文件存储和上传插件.
- [FlyPie plugin](https://github.com/WyriHaximus/FlyPie) - 使用Flysystem进行抽象文件系统访问.
- [FriendsOfCake/Upload plugin](https://github.com/FriendsOfCake/cakephp-upload) - 使用的可自定义插件 [Flysystem](http://flysystem.thephpleague.com/) 写入多个后端（Dropbox，FTP，S3，Local等）.
- [Image plugin](https://github.com/josbeir/image) - 图像行为与Cake内置的TranslateBehavior非常相似.
- [Josbeir/Filesystem plugin](https://github.com/josbeir/cakephp-filesystem) - 摘要 [Flysystem](http://flysystem.thephpleague.com/) +基于文件实体的上传插件.
- [Proffer plugin](https://github.com/davidyell/CakePHP3-Proffer) - 具有缩略图生成功能的可自定义上传插件.
- [Upload plugin](https://github.com/Xety/Cake3-Upload) - 上传文件的小插件.

## Filtering and Validation
*用于过滤和验证数据的插件.*

- [Gourmet/Filters plugin](https://github.com/gourmet/filters) - 额外的调度过滤器（维护，机器人，IP等）.
- [Gourmet/Validation plugin](https://github.com/gourmet/validation) - Extra validation providers (Respect, IsoCodes, etc.) and rules.
- [HtmlPurifier plugin](https://github.com/burzum/cakephp-html-purifier)   - 具有特征，行为和帮助的Purifier插件，允许您在需要的地方进行消毒和过滤.  您也可以配置多组过滤规则.
- [HtmlPurifier plugin](https://github.com/chrisShick/CakePHP3-HtmlPurifier) -  Purifier Plugin行为，用于在数据被封送到实体之前和/或保存之前清理数据.

## Geolocation
*地址编码地址和处理纬度和经度的插件.*

- [Geo plugin](https://github.com/dereuromark/cakephp-geo) - 包含 [Geocoder behavior](http://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) 和 [GoogleMaps helper](http://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).

## I18n
*用于I18n（国际化）和L10n（本地化）的插件.*

- [ADmad/I18n plugin](https://github.com/ADmad/cakephp-i18n) - 一个带有I18n相关工具的插件.
- [Localized plugin](https://github.com/cakephp/localized) - 本地化验证和即用型翻译PO文件.
- [ShadowTranslate plugin](https://github.com/AD7six/cakephp-shadow-translate) - 基于影子表的插件替换核心的翻译行为.
- [Transifex plugin](https://github.com/dereuromark/cakephp-transifex) - 通过Transifex API管理i18n PO文件和翻译.
- [Translate plugin](https://github.com/dereuromark/cakephp-translate)   - 通过网络后端轻松管理静态内容的翻译，包括.  从POT文件导入，自动建议和通过API自动翻译.
- [Translation plugin](https://github.com/ava007/wnk_translation) - 提取pot文件，翻译字符串（手动，谷歌，社区），将翻译导出到pot文件.

## Imagery
*用于处理图像的插件.*

- [ADmad/Glide plugin](https://github.com/ADmad/cakephp-glide) - 使用的插件 [Glide](http://glide.thephpleague.com/) 图像处理库.
- [HtmlToImageView plugin](https://github.com/andrej-griniuk/cakephp-html-to-image-view) - 使用将HTML视图渲染为图像（jpg或png） [wkhtmltoimage](https://wkhtmltopdf.org).
- [Imagine plugin](https://github.com/burzum/cakephp-imagine-plugin) - 图像处理插件和包装 [Imagine](https://github.com/avalanche123/Imagine).
- [Thumber plugin](https://github.com/mirko-pagliai/cakephp-thumber) - 使用创建缩略图的插件 [intervention/image](https://github.com/Intervention/image).

## Libs
*有用的库或工具不适合任何其他类别.*

- [Aura.Intl](https://github.com/auraphp/Aura.Intl) - 功能强大的I18n库 - 用于CakePHP 3.x核心.
- [Capcake](https://github.com/jadb/capcake) - 使用Capistrano部署CakePHP应用程序.
- [Chronos](https://github.com/cakephp/chronos) - 一个简单的独立DateTime API扩展（Carbon的后继者）.
- [Composer Installers](https://github.com/composer/installers) - 多框架Composer库安装程序.
- [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - 包和依赖管理器.
- [Graphviz](https://github.com/alexandresalome/graphviz) -  Graphviz库.
- [Jenkins](http://jenkins-ci.org/) - 私人（GitHub）回购的免费替代品.
- [Rocketeer](https://github.com/rocketeers/rocketeer) -  PHP任务运行器和部署包.
- [Travis CI](https://travis-ci.org/) - 持续集成平台 - 事实上的测试标准（GitHub）回购.
- [YamlRoute](https://github.com/makallio85/yaml-route) - 使用简单的YAML文件配置路由.

## Markup
*用于处理标记的插件.*

- [Gourmet/CommonMark plugin](https://github.com/gourmet/common-mark) - 添加 [CommonMark](http://commonmark.org/) Markdown解析.
- [Markup plugin](https://github.com/dereuromark/cakephp-markup) - 允许使用基于PHP或JS的语法突出显示.

## Migration
*有关迁移和升级的插件和资源.*

- [Migrations plugin](https://github.com/cakephp/migrations) - （DB）迁移插件.
- [Upgrade app](https://github.com/cakephp/upgrade) -  2.x =&gt; 3.x的官方升级应用程序.
- [Upgrade app (extended)](https://github.com/dereuromark/upgrade) -  2.x =&gt; 3.x和3.x之间的扩展升级应用程序.
- [Upgrade/Migration Guide](http://book.cakephp.org/3.0/en/appendices.html) - 官方移民指南.

## Miscellaneous
*其他插件和库.*

- [ActionsClass plugin](https://github.com/HavokInspiration/cakephp-actions-class) - 使您能够将Controller操作作为单个类进行管理.
- [Ajax plugin](https://github.com/dereuromark/cakephp-ajax) - 一个易于处理AJAX请求的插件.
- [CakeAdmin plugin](https://github.com/cakemanager/cakephp-cakeadmin) - 具有内置管理区域的非稳定用户管理插件.
- [CakeDC/Enum](https://github.com/CakeDC/enum) - 一个为您的应用添加枚举列表支持的插件.
- [CakeDto plugin](https://github.com/dereuromark/cakephp-dto) - 为您的应用程序快速生成有用的数据传输对象（可变/不可变），替换凌乱的数组并通过类型化和自动完成来利用您的IDE.
- [CakeImpersonate plugin](https://github.com/jomweb/CakeImpersonate)   - 存储当前身份验证会话并为模拟用户创建新会话的组件.  用户无需重新登录即可恢复原始身份验证会话.
- [CakeMiddlewares](https://github.com/chrisShick/CakeMiddlewares) -  Cakephp中间件的集合.
- [Calendar plugin](https://github.com/dereuromark/cakephp-calendar)   - 用于生成基本日历.  包括用于ICS日历文件生成的IcalView.
- [Comments plugin](https://github.com/Kareylo/CakePHP-Comments) - 完全可自定义的评论插件.
- [CurrencyConverter plugin](https://github.com/AlessandroMinoccheri/cakephp-currency-converter) - 将货币转换为另一种货币的插件.
- [Dashboard plugin](https://github.com/gourmet/dashboard) - 为您的蛋糕打造漂亮的仪表板.
- [DatabaseBackup plugin](https://github.com/mirko-pagliai/cakephp-database-backup) - 用于导出，导入和管理数据库备份的插件.
- [Feedback plugin](https://github.com/dereuromark/cakephp-feedback)   - 允许访问者发送快速简便的反馈，包括.  通过侧边栏表单截图.
- [Flash plugin](https://github.com/dereuromark/cakephp-flash) - 为您的应用程序提供更强大的Flash消息.
- [Hashid plugin](https://github.com/dereuromark/cakephp-hashid) - 允许使用哈希值不向用户公开数据库ID.
- [Heartbeat plugin](https://github.com/orca-services/cakephp-heartbeat/) - 监控应用程序的听力（例如，数据库是否可用且是最新的）.
- [Interval plugin](https://github.com/LubosRemplik/CakePHP-Interval) - 将秒转换为人类可读的字符串（字符串为秒），使用营业时间（1周= 5天，1天= 8小时）.
- [LinkScanner](https://github.com/mirko-pagliai/cakephp-link-scanner) - 用于递归扫描链接的插件
- [Robotusers/Tactician plugin](https://github.com/robotusers/cakephp-tactician) -  Tactician命令总线集成工具.
- [Setup:Maintenance](https://github.com/dereuromark/cakephp-setup/blob/master/docs/Maintenance/Maintenance.md) - 使用可选IP白名单的所有请求进入维护模式的维护shell.
- [Shim plugin](https://github.com/dereuromark/cakephp-shim) - 包含有用填充程序和改进的插件，作为您的应用程序的基础.
- [TokenVerify plugin](https://github.com/mosaxiv/cakephp-token-verify) - 轻松发布可用于邮件身份验证的令牌.
- [Tools plugin](https://github.com/dereuromark/cakephp-tools) - 包含许多有用的库，助手，行为，组件，shell等.
- [UserTools plugin](https://github.com/burzum/cakephp-user-tools)   - 用于登录，注册，密码重置等的用户工具.  开箱即用的CRUD就像是高度可配置的.
- [Utils plugin](https://github.com/cakemanager/cakephp-utils) - 包含有用的组件（授权器，菜单）和行为（WhoDidIt，Uploadable，Metas，Stateable）.
- [Wrench plugin](https://github.com/HavokInspiration/wrench)   - 维护模式插件.  易于扩展和可定制.
- [Yaml plugin](https://github.com/guemidiborhane/Cake-Yaml) - 使用YAML配置文件而不是PHP数组.

## Navigation
*用于构建导航结构的工具.*

- [Icings/Menu plugin](https://github.com/icings/menu) - 一个 [KnpMenu](https://github.com/KnpLabs/KnpMenu) CakePHP经验丰富的菜单插件.

## NoSQL
*用于处理“NoSQL”后端的插件.*

- [Monga plugin](https://github.com/lewestopher/cakephp-monga) - 使用提供对MongoDB数据源的访问 [`thephpleague/monga`](https://github.com/thephpleague/monga).

## Notifications
*用于处理通知软件的插件.*

- [ker0x/CakeGcm plugin](https://github.com/ker0x/CakeGCM) - 通过Google Cloud Messaging将下游消息发送到Android或iOS设备的插件.
- [Notifier plugin](https://github.com/cakemanager/cakephp-notifier) - 一个插件，可以轻松创建和阅读通知.
- [ker0x/Push plugin](https://github.com/ker0x/cakephp-push) - 通过Firebase云消息传递等服务发送推送通知的插件.

## ORM and Datamapping
*实现对象关系映射或数据映射技术的插件.*

- [ADmad/Sequence plugin](https://github.com/ADmad/cakephp-sequence) - 维护有序记录列表的行为.
- [Duplicatable plugin](https://github.com/riesenia/cakephp-duplicatable) - 复制实体（包括相关数据）的行为.
- [JeremyHarris/LazyLoad plugin](https://github.com/jeremyharris/cakephp-lazyload) - 实体的关联延迟加载器.
- [Lqdt/OrmJson plugin](https://github.com/liqueurdetoile/cakephp-orm-json) - 通过CakePHP ORM在JSON类型字段中选择，查找，获取和设置属性和值的行为和特征.
- [Money plugin](https://github.com/gourmet/money) - 使用CakePHP实体的Money数据类型 [sebastianbergmann/money](https://github.com/sebastianbergmann/money).
- [Muffin/Orderly plugin](https://github.com/usemuffin/orderly) - 允许设置表的默认顺序.
- [Muffin/Trash plugin](https://github.com/usemuffin/trash) -  CakePHP的软删除行为.
- [PersistRelatedData plugin](https://github.com/riesenia/persist-related-data) - 用于保留相关模型的选定字段的行为.
- [Robotusers/Excel plugin](https://github.com/robotusers/cakephp-excel) -  PHPExcel的ORM包装器.
- [Robotusers/TableInheritance plugin](https://github.com/robotusers/cakephp-table-inheritance) -  Singe Table Inheritance（STI）插件.
- [RowLocker plugin](https://github.com/lorenzo/row-locker) - 表中行的独占锁.
- [Serializeable Data Types plugin](https://github.com/burzum/cakephp-serialize-data-types) - 将DB内容序列化为JSON或使用phps序列化功能.
- [Muffin/Webservices ORM plugin](https://github.com/usemuffin/webservice) - 一个类似ORM的web服务接口.

## PDF
*用于处理PDF文件的插件和软件.*

- [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) - 围绕PDF生成的插件.

## Queue
*用于处理事件和任务队列的插件.*

- [CakeResque plugin](https://github.com/wa0x6e/Cake-Resque) -  Resque的插件，一个用于创建后台作业的库.
- [CakeQueuesadilla plugin](https://github.com/josegonzalez/cakephp-queuesadilla) - 一个插件，提供与各种后端的排队集成（BeanstalkD，MySQL，Redis等）.
- [Gearman plugin](https://github.com/cvo-technologies/cakephp-gearman) - 用于将CakePHP任务卸载到Gearman作业服务器的插件.
- [Queue plugin](https://github.com/dereuromark/cakephp-queue) - 最小且无依赖的队列解决方案.

## REST and API
*用于开发REST-ful API的插件和Web工具.*

- [Alt3/Swagger plugin](https://github.com/alt3/cakephp-swagger) - 使用swagger-php和swagger-ui为CakePHP API提供Swagger 2.0文档.
- [Alt3/ValidationExposer plugin](https://github.com/alt3/cakephp-validation-exposer) - 轻松公开您的应用程序的验证规则.
- [ApiPagination plugin](https://github.com/bcrowe/cakephp-api-pagination) - 将CakePHP的Paginator中的分页信息注入序列化的JsonView和XmlView响应中.
- [CakeDC/Api plugin](https://github.com/CakeDC/cakephp-api)   - 提供完整API的一体化解决方案.  它包括版本控制，渲染器，CRUD，身份验证，扩展（分页，过滤，HATEOAS）等等.
- [Cors plugin](https://github.com/ozee31/cakephp-cors) - 使用中间件激活CORS.
- [Cors plugin](https://github.com/snelg/cakephp-cors) - 一个轻量级插件，用于将CORS头添加到指定的端点.
- [CrudJsonApi plugin](https://github.com/FriendsOfCake/crud-json-api) - 建筑用的聆听者 [JSON API](http://jsonapi.org/) 兼容的API.
- [FractalTransformerView plugin](https://github.com/andrej-griniuk/cakephp-fractal-transformer-view) - 允许使用的插件 [Fractal transformers](http://fractal.thephpleague.com/transformers/) 为您的API输出.
- [JsonApi plugin](https://github.com/josbeir/cakephp-json-api) - 实现 [JSON API](http://jsonapi.org/) 格式.
- [RestApi plugin](https://github.com/multidots/cakephp-rest-api) - 为构建REST API服务提供基本支持.

## Search
*用于索引和执行数据搜索查询的插件和软件.*

- [ElasticSearch plugin](https://github.com/cakephp/elastic-search) - 使用弹性搜索作为后端的备用ORM.
- [PlumSearch plugin](https://github.com/skie/plum_search)   - 搜索插件实现自定义，灵活和可扩展的搜索策略.  实现PRG模式.
- [FriendsOfCake/Search plugin](https://github.com/FriendsOfCake/search) -  Search为CakePHP应用程序提供搜索/过滤模块.
- [SphinxSearch plugin](https://github.com/voycey/cakephp-sphinxsearch) - 查询SphinxSearch索引的基本行为实现.
- [Tags plugin](https://github.com/dereuromark/cakephp-tags) - 用于标记和查找标记记录.

## Security
*有关安全性的插件和信息，可防止漏洞和防范XSS等.*

- [Captcha plugin](https://github.com/dereuromark/cakephp-captcha) - 简单，不显眼且可扩展的验证码解决方案，默认提供基于图像的数学验证码.
- [CipherBehavior plugin](https://github.com/adayth/cakephp-cipher-behavior)   - 使用此行为加密实体数据.  使用CakePHP Security类在PHP级别完成加密.
- [Muffin/Obfuscate plugin](https://github.com/usemuffin/obfuscate) - 使用HashIds，Optimus，Tiny和/或自定义混淆策略的主键混淆.
- [Muffin/Throttle plugin](https://github.com/usemuffin/throttle) - 用于速率限制（API）请求的插件.
- [Recaptcha plugin](https://github.com/agiletechvn/Recaptcha) - 简单轻巧的Google Recaptcha v2.
- [Recaptcha Mailhide plugin](https://github.com/mirko-pagliai/cakephp-recaptcha-mailhide) - 一个允许您使用reCAPTCHA隐藏电子邮件地址的插件.

## SEO
*搜索引擎优化.*

- [Muffin/Slug plugin](https://github.com/UseMuffin/Slug)   - 用于生成slu and和通过slug查找记录的插件.  使用可插拔的架构，允许使用自己的slug生成器类.
- [Seo plugin](https://github.com/orgasmicnightmare/cakephp-seo) - 自动创建和管理您的SEO标签.
- [Sluggable plugin](https://github.com/Xety/Cake3-Sluggable) - 一个简单的Cake3插件，用于slug字段并通过slug查找记录.
- [Tools:Slugged](https://github.com/dereuromark/cakephp-tools) - 包含Slugged行为以从标题自动生成与URL兼容的slugs.

## Skeleton
* app骷髅周围的插件和存储库.*

- [App template](https://github.com/cakephp/app) - 用于作曲家的空CakePHP项目.
- [App template with material ui](https://github.com/coolops/web-app) -  CakePHP材料ui管理模板项目，用于与作曲家一起使用.
- [Crud plugin](https://github.com/FriendsOfCake/crud) -  CakePHP类固醇的应用程序开发 - 快速原型制作/脚手架和生产就绪代码.
- [Plugin Skeleton](https://github.com/Xety/Cake3-PluginSkeleton) - 创建Cake3插件的框架示例.

## Social
*社交功能插件.*

- [CakeDC/Forum plugin](https://github.com/CakeDC/cakephp-forum) - 论坛插件，包括类别，主题和回复，报告消息，主持人，管理界面等.
- [Ratings plugin](https://github.com/dereuromark/cakephp-ratings) - 允许用户评分记录.
- [SocialShare plugin](https://github.com/drmonkeyninja/cakephp-social-share) - 用于在社交网络上共享内容的链接生成器.

## Templating
*用于模板和lexing的插件.*

- [Address plugin](https://github.com/drmonkeyninja/cakephp-address) - 输出标记地址的地址助手.
- [Bake plugin](https://github.com/cakephp/bake) - 提供代码生成功能.
- [Bootstrap plugin](https://github.com/elboletaire/twbs-cake-plugin) - A Bootstrap 3 plugin with support for LESS.
- [BootstrapUI plugin](https://github.com/friendsofcake/bootstrap-ui) -  Bootstrap 3集成.
- [CakeExcel plugin](https://github.com/dakota/CakeExcel) - 用于生成XLSX文件的Excel视图.
- [Chocolate plugin](https://github.com/commercial-hippie/chocolate) - 前端框架FormHelper扩展.
- [CommonMark plugin](https://github.com/gourmet/common-mark) - 添加 [CommonMark](http://commonmark.org) （降价）对模型和视图的支持.
- [CsvView plugin](https://github.com/FriendsOfCake/cakephp-csvview) - 可轻松生成CSV的视图类.
- [Datalist plugin](https://github.com/rrd108/cakephp-datalist) - 支持HTML5 datalist元素，可以在关联模型中创建新条目.
- [Feed plugin](https://github.com/dereuromark/cakephp-feed) - 包含RssView类，可轻松生成（复杂）RSS源.
- [InlineCss plugin](https://github.com/drmonkeyninja/cakephp-inline-css) - 一个插件，用于将HTML样式块转换为View模板上的内联CSS（用于电子邮件模板）.
- [JadeView plugin](https://github.com/clthck/cakephp-jade) - 玉模板引擎插件.
- [Liquid plugin](https://github.com/gourmet/liquid) - 一个使用Liquid模板语言进行视图的插件.
- [Meta plugin](https://github.com/dereuromark/cakephp-meta) - 处理元标记和SEO相关的HTML标记DRY和简单.
- [SocialMeta plugin](https://github.com/gourmet/social-meta) - 增加对Facebook的OpenGraph和Twitter的Card元标记的支持.
- [TwigView plugin](https://github.com/WyriHaximus/TwigView) - 一个使用Twig Templating Language进行视图的插件.
- [VideoEmbed plugin](https://github.com/drmonkeyninja/cakephp-video-helper) - 帮助嵌入YouTube，Vimeo和Dailymotion视频.

## Testing
*用于测试代码库和生成测试数据的插件/工具.*

- [CakePHP Codeception module](https://github.com/cakephp/codeception) - 官方CakePHP集成 [Codeception](http://codeception.com).
- [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) - 官方CakePHP CS规则.
- [CodeSniffer plugin](https://github.com/dereuromark/cakephp-codesniffer) - 自动查找代码问题/气味并自动修复CS错误.
- [Faker plugin](https://github.com/gourmet/faker) - [Faker](https://github.com/fzaninotto/Faker) 支持CakePHP灯具.
- [Fixtures plugin](https://github.com/LubosRemplik/CakePHP-Fixtures) -  Fixtures插件，用于读取现有灯具并创建表/插入数据，以便快速启动app.
- [FriendsOfCake/fixturize](https://github.com/FriendsOfCake/fixturize) - 通过减少插入量（仅限mysql）运行测试套件时更有效地插入灯具.
- [Gourmet/Muffin plugin](https://github.com/gourmet/muffin) - [FactoryMuffin](https://github.com/thephpleague/factory-muffin) 支持CakePHP夹具记录.

## Third Party APIs
*用于访问第三方API的插件.*

- [CakeTmdb plugin](https://github.com/drmonkeyninja/cakephp-tmdb) - 电影数据库（TMDB）API集成.
- [GitHub plugin](https://github.com/cvo-technologies/cakephp-github) - 允许使用.访问GitHub REST API [Webservice](https://github.com/UseMuffin/Webservice) ORM.
- [Ratchet plugin](https://github.com/WyriHaximus/Ratchet) - 将Ratchet websocket包带到CakePHP.
- [Salesforce plugin](https://github.com/voycey/cakephp-salesforce) - 允许使用CakePHP的ORM查询和与Salesforce Enterprise实例交互.
- [Twitter plugin](https://github.com/cvo-technologies/cakephp-twitter) - 允许使用.访问Twitter REST和流API [Webservice](https://github.com/UseMuffin/Webservice) ORM.

## Software
*用于创建开发环境的软件.*

## Development Environment
*用于创建沙盒开发环境的软件和工具.*

- [Cakebox](https://github.com/alt3/cakebox) - 由CakePHP 3.x控制台提供支持的Vagrant开发环境.
- [CakePHP.gitignore](https://github.com/github/gitignore/blob/master/CakePHP.gitignore) -  .gitignore文件提案.
- [CakePHP Vagrant Setup](https://github.com/cpierce/cakephp-vagrant-setup) - 用于启动多个CakePHP 3.x Vanilla Dev环境的工具.
- [Docker](https://github.com/stefanvangastel/docker-cakephp) -  Docker容器环境中的CakePHP.
- [Mixer](https://github.com/CakeDC/mixer) - 一个发现和管理CakePHP插件的插件.
- [NetBeans plugin](https://github.com/junichi11/cakephp3-netbeans) - 此插件为NetBeans 8.1+中的CakePHP提供支持.
- [Oven](https://github.com/CakeDC/oven) - 使用1个文件和1个单击设置您喜欢的框架.
- [PhpStorm plugin](https://github.com/skie/PhpStorm) - 在PhpStorm IDE中对控制台命令的CakePHP自动完成支持.
- [PuPHPet](https://puphpet.com/) - 用于构建Vagrant + Puppet框的Web界面.
- [Puppet](https://puppetlabs.com/) - 服务器自动化框架和应用程序.
- [Vagrant](https://www.vagrantup.com/) - 便携式开发环境实用程序.
- [Vagrant CakePHP](https://github.com/salines/vagrant-cakephp)   -  Vagrant LEMP环境包括.  最新的CakePHP.

## Web Applications

## CMS and applications built on CakePHP

- [CakeBlog](https://github.com/gwhitcher/CakeBlog) - 开源博客软件.
- [Croogo](https://croogo.org) -  CMS软件
- [QuickApps-CMS](https://github.com/quickapps/cms) - 开源内容管理系统.

## Demo
*基于Web（演示）的应用程序和工具.*

- [BlogMVC](https://github.com/Kareylo/BlogMVC-CakePHP3) - 一个基于CakePHP的简单博客示例 [BlogMVC Project](https://github.com/Grafikart/BlogMVC).
- [Bookmarkr](https://github.com/lorenzo/cakephp3-bookmarkr) 使用CRUD插件构建的书签应用程序.
- [CakeFest](http://cakefest.dereuromark.de/) - 围绕年度CakePHP会议“CakeFest”的演示应用程序.
- [Croogo 3.x](http://demo.croogo.org/3.0) -Croogo 3.x演示
- [RealWorld](https://github.com/gothinkster/cakephp-realworld-example-app) - 示例CakePHP代码库包含遵循的真实世界示例（CRUD，auth，高级模式等） [RealWorld](https://github.com/gothinkster/realworld-example-apps) 规范和API.
- [Sandbox](http://sandbox.dereuromark.de) - 沙盒CakePHP应用程序，包含大量演示和插件显示.
- [Query Examples](https://github.com/lorenzo/cakephp3-examples) 高级查询构建示例.
- [Xeta](https://github.com/XetaIO/Xeta) - 帮助人们从CakePHP开始的资源.
- [Vue.js Demo App](https://github.com/ishanvyas22/cakephpvue-spa) -  CakePHP + VueJS单页面应用程序框架.

## Resources
各种资源，如书籍，网站和文章，用于提高您的CakePHP开发技能和知识.

## Help
*在哪里获得帮助.*

- [cakephpbrasil.com.br](http://cakephpbrasil.com.br/) - 巴西社区网站.
- [CakePHP-FR.org](http://cakephp-fr.org) - 法国社区网站.
- [CakePHP.ir](http://forum.cakephp.ir/) - 与波斯社区的其他开发者和一般性问题进行讨论.
- [Official CakePHP Forum](http://discourse.cakephp.org/) - 这是针对一般性问题的.
- [IRC Channel](http://www.dereuromark.de/2013/01/27/irc-cakephp-channel/) - 与其他开发者和核心开发者进行实时聊天/讨论.
- [stackoverflow.com/questions/tagged/cakephp](http://stackoverflow.com/questions/tagged/cakephp) - 这是针对特定问题，理想情况下是一些示例代码.

## CakePHP Websites
*有用且与当前CakePHP相关的网站和博客.*

- [AD7six.com](http://AD7six.com) -  CakePHP核心开发博客.
- [CakeDC](http://www.cakedc.com/articles) - 关于CakePHP的文章.
- [dereuromark.de](http://www.dereuromark.de) - 广泛的CakePHP核心开发博客.
- [florian-kraemer.net](http://florian-kraemer.net) -  CakePHP相关的核心开发博客.
- [jedistirfry.co.uk](http://jedistirfry.co.uk) -  CakePHP相关开发博客.
- [josediazgonzalez.com](http://josediazgonzalez.com/) - 主要是CakePHP相关的核心开发博客.
- [mark-story.com](http://mark-story.com) -  CakePHP领导开发博客.
- [waltherlalk.com](http://waltherlalk.com) -  CakePHP相关的核心开发博客.

## CakePHP Books and Articles
* Fantastic CakePHP相关（e）书籍和其他阅读材料.*

## CakePHP Videos
* Fantastic CakePHP相关视频.*

- [CakePHP](https://www.youtube.com/user/CakePHP) - 关于CakePHP视频的频道.


## CakePHP Tutorials
*必须做的教程.*

- [Official Blog tutorial](http://book.cakephp.org/3.0/en/tutorials-and-examples/blog/blog.html)

## CakePHP Reading and Listening
*文档和CakePHP相关的阅读和听力材料.*

- [CakePHP Cookbook(!)](http://book.cakephp.org/) -  CakePHP官方文档.
- [CakePHP Reporter](http://www.scoop.it/t/cakephp-reporter) - 一份关于CakePHP的报纸和材料集.

## CakePHP Internals Reading
*与CakePHP内部和决定相关的阅读材料.*

- [Core Google Group](https://groups.google.com/forum/#!forum/cakephp-core) - 围绕CakePHP核心的讨论.
- [Top 10 (and more) core contributors](https://github.com/cakephp/cakephp/graphs/contributors) - 给他们一只手.

## Conferences

## Official
*国际会议.*

- [cakefest.org](http://cakefest.org/) - 年度CakePHP会议.

## MeetUps
*区域聚会.*

- [CakePHP-DE](http://www.meetup.com/CakePHP-DE) - 德国的MeetUps.
- [CakePHP-France](http://www.meetup.com/CakePHP-France) - 法国的MeetUps.
- [CakePHP-NL](http://www.meetup.com/CakePHP-NL) - 荷兰的MeetUps.

## Contributing
请参阅 [CONTRIBUTING](https://github.com/friendsofcake/awesome-cakephp/blob/master/CONTRIBUTING.md) 详情.

## Credits
awesome-cakephp已被创建 [dereuromark](https://github.com/dereuromark)  目前由他和FriendsOfCake小组维护.  谢谢你们 [contributors](https://github.com/FriendsOfCake/awesome-cakephp/graphs/contributors)也是.
