<div class="github-widget" data-repo="collective/awesome-plone"></div>
## Awesome Plone [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!--lint ignore double-link-->
[<img align="right" src="https://raw.githubusercontent.com/collective/awesome-plone/master/logo.png" height="64">](https://plone.org)

&gt; 社区精选的 _awesome_ Plone 附加组件列表.

<!--lint ignore double-link-->
[Plone](https://plone.org) 是一个用 Python 编写的开源 CMS，专注于开箱即用的功能、可定制性和安全性.

有超过 [3000 add-ons for Plone on pypi](https://pypi.org/search/?q=&o=&c=Framework+%3A%3A+Plone) 以及 1500 多个存储库 [collective](https://github.com/collective/) . 如果你想知道是否已经有适合你需要的 Plone 附加组件，在 GitHub 或 pypi 上搜索它可能很困难. 很难理解哪个可能是一个好的解决方案.

此列表旨在填补这一空白，并创建关于常见产品和技术的共享知识.

此列表仅涵盖适用于最新主要版本 Plone（目前为 5.2 和 6）的附加组件，并且仅涵盖那些支持 Python 3 的附加组件.

 Plone 6 带有一个名为 Volto 的新默认前端，它是用 React 编写的，并使用 `plone.restapi` 与 Plone 进行通信.  Volto 本身具有很强的可扩展性. 签出 [awesome-volto list](https://github.com/collective/awesome-volto) 用于 Volto 的附加组件.




---


_为内容提供内容类型或附加功能的附加组件_

* [collective.a11ycheck](https://github.com/collective/collective.a11ycheck) - 保存页面时向站点编辑报告可访问性问题.
* [collective.bbcodesnippets](https://github.com/collective/collective.bbcodesnippets) - 为 Plone 提供通用和可扩展的 BBCode 标记集成.
* [collective.consent](https://github.com/collective/collective.consent) - 要求用户同意不同的主题，然后才能继续.
* [collective.documentviewer](https://github.com/collective/collective.documentviewer) - 非常好的文档查看器，将 DocumentCloud 查看器和 PDF 处理集成到 Plone 中.
* [collective.folderishtraverse](https://github.com/collective/collective.folderishtraverse) - 遍历到文件夹中的第一项.
* [collective.lineage](https://github.com/collective/collective.lineage)  - 子站点：将 Plone 站点的子文件夹显示为自治 Plone 站点. 还有一个完整的生态系统关闭特定于子站点的插件.
* [collective.mailchimp](https://github.com/collective/collective.mailchimp) - Plone 的 MailChimp 时事通讯集成.
* [collective.restrictportlets](https://github.com/collective/collective.restrictportlets) - 允许您限制非经理可以添加的可用 portlet.
* [collective.richdescription](https://github.com/collective/collective.richdescription) - Plone 的可格式化描述字段.
* [Products.EasyNewsletter](https://github.com/collective/Products.EasyNewsletter) - Plone 的强大时事通讯/邮寄产品.


## Searching and Categorizing

* [collective.bookmarks](https://github.com/collective/collective.bookmarks) - Plone 的书签/收藏夹/愿望清单.
* [collective.elasticsearch](https://github.com/collective/collective.elasticsearch) - 使用 ElasticSearch 作为 Plone 的搜索后端.
* [collective.solr](https://github.com/collective/collective.solr) - Plone 的 Solr 搜索引擎集成.
* [Products.PloneKeywordManager](https://github.com/collective/Products.PloneKeywordManager) - 更改、合并和删除关键字/标签/主题）.
* [zopyx.typesense](https://github.com/zopyx/zopyx.typesense)  - Plone 与外部 Typesense 搜索服务器（开源）的集成. 这是 collective.solr 或 Elasticsearch 的替代方案.


## Layout

_帮助开发人员和用户创建和管理网站布局的产品和资源._

* [collective.cover](https://github.com/collective/collective.cover)  - Cover 允许创建围绕拖放界面构建的精美封面. 使用与 plone.app.mosaic 相同的块/瓷砖生态系统，但使用不同的编辑方法.


## Tiles

_扩展布局编辑器 plone.app.mosaic._ 的附加组件

* [plone.app.standardtiles](https://github.com/plone/plone.app.standardtiles) - Mosaic 使用的一组标准图块，但可以从任何其他图块管理器使用.
* [collective.tiles.carousel](https://github.com/collective/collective.tiles.carousel) - 基于 Bootstrap 5 轮播组件的 plone.app.mosaic 滑块.
* [collective.tiles.advancedstatic](https://github.com/collective/collective.tiles.advancedstatic) - 显示 html 文本的磁贴（类似于静态文本 portlet），带有一些额外的配置，例如添加自定义 css 类的可能性.
* [collective.tiles.collection](https://github.com/collective/collective.tiles.collection) - 显示一组集合结果的磁贴，可以选择（和开发）自定义布局.


## Events

_处理事件和日历的附加组件._

* [collective.easyformplugin.registration](https://github.com/collective/collective.easyformplugin.registration) - 向 collective.easyform 添加一个行为来管理事件的注册表.
* [collective.fullcalendar](https://github.com/collective/collective.fullcalendar) - 使用 https://fullcalendar.io 在漂亮的日历 UI 中显示事件.


## Forms

_允许生成和使用表单的附加组件._

* [collective.easyform](https://github.com/collective/collective.easyform)  - EasyForm 使用字段、小部件、操作和验证器通过网络提供一个 Plone 表单构建器. 表单输入可以保存或通过电子邮件发送. 一个简单且用户友好的界面允许非程序员创建自定义表单.
* [collective.honeypot](https://github.com/collective/collective.honeypot) - 表单蜜罐保护.
* [collective.z3cform.datagridfield](https://github.com/collective/collective.z3cform.datagridfield) - 带有数据网格（表）的字段，其中每一行都是一个子表单.
* [collective.z3cform.norobots](https://github.com/collective/collective.z3cform.norobots) - 基于问题/答案列表的“人类”验证码小部件.
* [plone.formwidgets.hcaptcha](https://github.com/plone/plone.formwidget.hcaptcha) - 用于保护 Plone 免受机器人、垃圾邮件和其他形式的自动滥用的 HCaptcha 小部件.
* [yafowil.plone](https://github.com/bluedynamics/yafowil.plone)  - Yafowil 是 Python 的表单库. 这是它的 Plone Integration 包.


## Multilingual

_帮助管理多语言网站的插件._

* [collective.linguatags](https://github.com/collective/collective.linguatags) - Plone 的多语言标签.


## Media

_处理图像、视频和音频内容的附加组件._

* [collective.autoscaling](https://github.com/collective/collective.autoscaling)  - 自动缩放大图像. 当编辑上传太大的图像时，有助于减小数据库大小.
* [collective.behavior.banner](https://github.com/collective/collective.behavior.banner) - 从横幅创建横幅和滑块的行为.
* [collective.lazysizes](https://github.com/collective/collective.lazysizes) - 集成 lazysizes，一个轻量级的延迟加载器，到 Plone.
* [collective.wavesurfer](https://github.com/collective/collective.wavesurfer) - 为 Plone 实施 https://wavesurfer-js.org 音频播放器.
* [plone.app.imagecropping](https://github.com/collective/plone.app.imagecropping) - 使用 cropper JS 库在 Plone 中手动裁剪图像.
* [plone.gallery](https://github.com/plone/plone.gallery) - Plone 的照片库视图.
* [redturtle.gallery](https://github.com/RedTurtle/redturtle.gallery) - 添加带有 slick 制作的轮播的画廊视图.


## Security

* [collective.geotransform](https://github.com/collective/collective.geotransform) - 优雅的 Plone 电子邮件混淆.

## SEO

_用于搜索引擎优化的附加组件._

* [bda.plone.gtm](https://github.com/bluedynamics/bda.plone.gtm) - 谷歌标签管理器集成.
* [collective.behavior.seo](https://github.com/collective/collective.behavior.seo) - 添加用于 SEO 优化的额外字段.



## Authentication

_身份验证插件列表，用于将 Plone 与外部用户、Importsources 和 Migrations.import 集成_

* [pas.plugins.ldap](https://github.com/collective/pas.plugins.ldap) - 提供来自 LDAP 目录的用户和组.
* [pas.plugins.authomatic](https://github.com/collective/pas.plugins.authomatic) - 与 Plone 的 Authomatic OAuth1/OAuth2/OpenID 登录集成.
* [iw.rejectanonymous](https://github.com/collective/iw.rejectanonymous)  - 拒绝来自 Plone 站点的无条件匿名用户，无需对您的安全策略矩阵或工作流程进行任何更改. 基本用例是外联网，所有访问者都必须经过身份验证.
* [pas.plugins.headers](https://github.com/collective/pas.plugins.headers)  - 读取请求标头并使用它们进行身份验证. 想想由 Apache 或 nginx 等前端 Web 服务器设置的 SAML 标头.
* [dm.zope.saml2](https://pypi.org/project/dm.zope.saml2/) - 支持基于 SAML2 的单点登录.
* [collective.pwexpiry](https://github.com/collective/collective.pwexpiry) - 提供了在 Plone 和密码攻击保护中增强用户密码的方法.


## Shop

* [bda.plone.productshop](https://github.com/bluedynamics/bda.plone.productshop) - 灵活和模块化的 Plone 电子商务解决方案.


## Export, Import and Migrations

* [collective.migrationhelpers](https://github.com/collective/collective.migrationhelpers/) - 在迁移过程中使用的助手和示例.


## Themes

* [plonetheme.tokyo](https://github.com/collective/plonetheme.tokyo) - Plone 的 Tokyo Theme 将 Bootstrap 4 实施到 Plone 中，重点是让事情尽可能接近“默认”.
* [plonetheme.grueezibuesi](https://github.com/collective/plonetheme.grueezibuesi) - Plone 6 的小猫灵感主题.
* [collective.sidebar](https://github.com/collective/collective.sidebar) - 合并工具栏和导航的侧边栏.
* [collective.editablemenu](https://github.com/RedTurtle/collective.editablemenu) - Plone 的可定制导航菜单.


## Develop

_帮助开发 Plone 的插件_

* [Products.PDBDebugMode](https://github.com/collective/Products.PDBDebugMode)  - 事后调试：每当发生异常时打开 pdb 会话，这样您就可以找出问题所在. 另外：通过将 /pdb 添加到 url，您最终会进入当前上下文的 pdb 会话. 开发人员的杀手级工具.
* [plone.reload](https://github.com/plone/plone.reload) - 无需重启服务器即可重新加载代码和配置.
* [Products.PrintingMailHost](https://github.com/collective/Products.PrintingMailHost) - 记录邮件消息而不是发送邮件.
* [experimental.gracefulblobmissing](https://github.com/collective/experimental.gracefulblobmissing/) - 优雅地处理 Plone 中丢失的二进制文件.
* [collective.patchwatcher](https://github.com/collective/collective.patchwatcher) - 跟踪修补或覆盖文件的好伙伴.
* [collective.relationhelpers](https://github.com/collective/collective.relationhelpers)  - 在 Plone 5.x 中管理、创建、导出和重建关系的助手. 对于 Plone 6，这被合并到 Plone 核心中.


## Sysadmin

_帮助管理员部署和维护 Plone 的附加组件_

* [collective.catalogcleanup](https://github.com/collective/collective.catalogcleanup) - 从目录中删除不再属于实际对象的数据.
* [collective.fingerpointing](https://github.com/collective/collective.fingerpointing) - 跟踪不同的事件并将它们写到审计日志中.
* [collective.ifttt](https://github.com/collective/collective.ifttt)  - 允许任何 Plone 站点在 IFTTT 生态系统中播放. 例如，当发布一条新闻时，发布推文或将其发布在 Facebook 上.
* [collective.purgebyid](https://github.com/collective/collective.purgebyid) - 在 Plone 中使用基于标签的缓存失效（例如使用 Varnish 的 xkey 模块）.
* [collective.recipe.backup](https://github.com/collective/collective.recipe.backup) - 强大而灵活的 Plone 备份/恢复解决方案.
* [collective.regenv](https://github.com/collective/collective.regenv) - 使用环境变量覆盖注册表设置.
* [collective.revisionmanager](https://github.com/collective/collective.revisionmanager) - 管理可能会使您的数据库膨胀的 Products.CMFEditions 历史记录.
* [collective.sentry](https://github.com/collective/collective.sentry) - 哨兵集成以汇总错误并帮助查找其原因.
* [dm.historical](https://pypi.org/project/dm.historical)  - 访问数据库的任何历史状态. 可用于找出对象过去发生的情况以及恢复意外删除或修改的对象.
* [haufe.requestmonitoring](https://github.com/collective/haufe.requestmonitoring)  - 在发布事件之上的详细请求日志记录功能. 有助于找出什么比它应该花费的时间更长.


## Finding more add-ons

很难找到适合您要求的附加组件.
以下是一些提示：

* 列出所需功能.
* 首先查看此列表.
* 搜索pypi: https://pypi.org/search/?c=Framework+%3A%3A+Plone
* 在github上搜索集体组织：https://github.com/collective
* 在github上搜索plone组织：https://github.com/plone
* 谷歌满足您的要求

一旦你有了一个候选名单，就可以测试这些附加组件. 以下是在生产站点上安装附加组件之前需要测试的主要问题：

 * 测试所有必需的功能. 阅读但不相信文档
* 检查插件是否在您需要的版本上运行
* 检查是否维护
* 它是否支持 i18n，即用户界面是否已翻译成您的语言？
* 卸载干净吗？
* 检查不需要的依赖项

找到喜欢的附加组件后，您可以询问社区您是否做出了正确的选择，或者您是否遗漏了什么：

* 留言板：https://community.plone.org

如果您找不到 100% 符合您要求的东西，您可以：

* 使您的要求适应可用的条件.
* Invest the time & money to customize an existing add-ons to better fit your needs.
* 创建一个完全满足您需要的新插件.

## Official resources

_因为Plone官方也有很多不错的info资源_

<!--lint ignore double-link-->
* [plone.org](https://plone.org/) - 开发者和社区的官方网站.
* [community.plone.org](https://community.plone.org/) - 官方社区论坛，获得帮助的最佳场所.
* [Discord chat](https://discord.gg/zFY3EBbjaj) - Discord 是与 Plone 社区成员聊天的最佳方式.
* [Plone support](https://plone.org/support) - 在哪里寻求帮助.
* [docs.plone.org](https://docs.plone.org/) - 开发人员/集成商的官方文档.
* [Plone 6 Documentation](https://6.dev-docs.plone.org/) - 即将推出的 Plone 6 的官方文档（正在进行中）.
* [training.plone.org](https://training.plone.org/) - 开发人员/集成商/用户/设计师的培训课程.
* [plone.api](https://6.dev-docs.plone.org/plone.api/index.html) - plone.api 的文档.


## Contributing

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/collective/awesome-plone/blob/master/contributing.md).
