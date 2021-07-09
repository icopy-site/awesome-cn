<div class="github-widget" data-repo="uralbash/awesome-pyramid"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Pyramid
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![IRC
Freenode](https://img.shields.io/badge/irc-freenode-blue.svg)](https://webchat.freenode.net/?channels=pyramid)

精选的 Pyramid 应用程序、项目和资源列表. 灵感来自和
基于 [awesome-python](https://github.com/vinta/awesome-python/).


## Admin interface

*扩展管理界面、添加或改进功能的软件包.*

* [pyramid_formalchemy](https://github.com/FormAlchemy/pyramid_formalchemy) -
  为基于 FormAlchemy 的金字塔提供 CRUD 接口.
* [pyramid_sacrud](https://github.com/sacrud/pyramid_sacrud) - 金字塔 CRUD 界面.
  为 Pyramid 提供管理 Web 界面.
  与经典的 CRUD 不同， pyramid_sacrud 允许覆盖和灵活性
  自定义您的界面，类似于 django.contrib.admin 但使用
  不同的后端提供资源.  [新架构](
  <http://pyramid-sacrud.readthedocs.io/pages/contribute/architecture.html>)
  建立在资源和机制遍历上，允许在各种情况下使用它.
    * [ps_alchemy](https://github.com/sacrud/ps_alchemy) - pyramid_sacrud 的扩展
      它提供了 SQLAlchemy 模型.
    * [ps_tree](https://github.com/sacrud/ps_tree) - 扩展名
      [pyramid_sacrud](https://github.com/sacrud/pyramid_sacrud) 显示
      作为树的记录列表. 这适用于来自的模型
      [sqlalchemy_mptt](https://github.com/uralbash/sqlalchemy_mptt).
* [Websauna](https://websauna.org/docs/) - Pyramid 的全栈应用框架

## Asset Management

*帮助管理项目静态资产的包.*

* [pyramid_webassets](https://github.com/sontek/pyramid_webassets) - 金字塔
  使用 webassets 库的扩展.
* [pyramid_bowerstatic](https://github.com/mrijken/pyramid_bowerstatic) -
  将 Bowerstatic 集成到 Pyramid 中

## Async

* [aiopyramid](https://github.com/housleyjk/aiopyramid) - 运行金字塔使用
  异步.
* [gevent-socketio](https://github.com/abourget/gevent-socketio) -
  gevent-socketio 是 Socket.IO 协议的 Python 实现，
  最初由 LearnBoost 为 Node.js 开发，然后移植到其他
  语言.
* [Stargate](https://github.com/boothead/stargate) - 星际之门是一个包
  将 WebSockets 支持添加到使用优秀的金字塔应用程序
  用于长时间运行的连接的 eventlet 库.
* [channelstream](https://github.com/AppEnlight/channelstream) - websocket 通信服务器（通风口）.

## Authentication

*改进或扩展 Pyramid 身份验证方法的包.*

* [pyramid_ldap](https://github.com/Pylons/pyramid_ldap) - LDAP
  Pyramid 的身份验证策略.
* [pyramid_ldap3](https://github.com/Cito/pyramid_ldap3) - 提供 LDAP 身份验证
  基于 ldap3 包的 Pyramid 应用程序服务.
* [pyramid_who](https://github.com/Pylons/pyramid_who) - 认证政策
  金字塔使用 repoze.who 2.0 API.
* [velruse](https://github.com/bbangert/velruse) - 简化第三方
   Web 应用程序的身份验证. 它支持大部分身份验证
  [providers](https://github.com/bbangert/velruse/tree/master/velruse/providers).
* [pyramid_simpleauth](https://github.com/thruflo/pyramid_simpleauth) - 会议
  Pyramid 应用程序的基于身份验证和基于角色的安全性
* [Python Social Auth](https://github.com/omab/python-social-auth) - 社会
  身份验证/注册机制，支持大量
  [providers](https://github.com/omab/python-social-auth#auth-providers).
* [Authomatic](https://github.com/authomatic/authomatic) - 简单而强大
  Python Web 应用程序的授权/身份验证客户端库.
* [apex](https://github.com/cd34/apex) - 金字塔工具包，一个塔项目，
  to add Authentication and Authorization using Velruse (OAuth) and/or a local
  数据库、CSRF、ReCaptcha、会话、Flash 消息和 I18N.
* [pyramid_authsanity](https://github.com/usingnamespace/pyramid_authsanity) -
  这将使拥有一个简单的安全身份验证策略变得更简单
  使用后端.
* [pyramid_jwt](https://github.com/wichert/pyramid_jwt) - 这个包
  使用 [JSON Web Tokens] 为 Pyramid 实现身份验证策略.
  该标准 ([RFC 7519]) 通常用于保护后端 API. 这
  优秀的 [PyJWT] 库用于 JWT 编码/解码逻辑.
* [pyramid_ipauth](https://github.com/mozilla-services/pyramid_ipauth) -
  基于远程IP地址的金字塔认证策略.

  [JSON 网络令牌]：https://jwt.io/
  [RFC 7519]：https://tools.ietf.org/html/rfc7519
  [PyJWT]：https://pyjwt.readthedocs.io/en/latest/


## Authorization

*与授权基础设施和权限相关的包.*

* [ziggurat_foundations](https://github.com/ergo/ziggurat_foundations) -
  与框架无关的一组 sqlalchemy 类，用于构建应用程序
  需要权限的一项简单任务.
* [pyramid_multiauth](https://github.com/mozilla-services/pyramid_multiauth) -
  Pyramid 的身份验证策略，它代理了一堆其他
  身份验证策略.
* [pyramid_authstack](https://github.com/wichert/pyramid_authstack) - 用
  使用 Pyramid 的多个身份验证策略.
* [horus](https://github.com/Pylons/horus) - 用户注册和登录系统
  for the Pyramid Web Framework.
* [pyramid_yosai](https://github.com/YosaiProject/pyramid_yosai) - Pyramid 与 Python 应用程序的安全框架集成，具有授权（rbac 权限和角色）、身份验证（2fa totp）、会话管理和广泛的审计跟踪 https://yosaiproject.github.io/yosai/

## Caching & Session

*有助于缓存和会话的软件包.*

* [pyramid_beaker](https://github.com/Pylons/pyramid_beaker) - 烧杯会议
  Pyramid 的工厂后端，也是缓存配置器.
    * [为什么你想切换到
      dogpile.cache](http://techspot.zzzeek.org/2012/04/19/using-beaker-for-caching-why-you-ll-want-to-switch-to-dogpile.cache/)
* [pyramid_redis_sessions](https://github.com/ericrasmussen/pyramid_redis_sessions) -
  由 Redis 支持的 Pyramid Web 框架会话工厂.
* [pyramid_dogpile_cache](https://github.com/moriyoshi/pyramid_dogpile_cache) -
  Pyramid 的 dogpile.cache 配置包
* [pyramid_sessions](https://github.com/joulez/pyramid_sessions) - 多
  Pyramid Web 框架的会话支持
* [pyramid_nacl_session](https://github.com/Pylons/pyramid_nacl_session) -
  定义了一个加密的、基于pickle 的cookie 序列化程序，使用
  [PyNaCl](http://pynacl.readthedocs.io/en/latest/secret/) 生成
  cookie 状态的对称加密.

## Debugging

*帮助追捕错误的软件包.*

* [pyramid_debugtoolbar](https://github.com/Pylons/pyramid_debugtoolbar) -
  提供在您开发 Pyramid 时有用的调试工具栏
  应用.
* [pyramid_exclog](https://github.com/Pylons/pyramid_exclog) - 一个包
  记录来自 Pyramid 应用程序的异常.
* [pyramid_debugtoolbar_dogpile](https://github.com/jvanasco/pyramid_debugtoolbar_dogpile) -
  对 pyramid_debugtoolbar 的 dogpile 缓存支持
* [pyramid_ipython](https://github.com/Pylons/pyramid_ipython) - IPython
  Pyramid 的 pshell 的绑定
* [pyramid_bpython](https://github.com/Pylons/pyramid_bpython) - 蟒蛇
  Pyramid 的 pshell 的绑定
* [pyramid_pycallgraph](https://github.com/disko/pyramid_pycallgraph) - 金字塔补间为每个请求生成调用图图像

## Email

*帮助管理电子邮件发送的软件包.*

* [pyramid_mailer](https://github.com/Pylons/pyramid_mailer) - 一个包
  从您的 Pyramid 应用程序发送电子邮件.
* [pyramid_marrowmailer](https://github.com/domenkozar/pyramid_marrowmailer) -
  用于mone.mailer 的Pyramid 集成包，以前称为TurboMail
* [pyramid_mailgun](https://github.com/evannook/pyramid_mailgun) - Pyramid 框架的 Mailgun 集成.

## Forms

*扩展表单功能或添加新表单类型的包.*

* [deform](https://github.com/Pylons/deform) - 是一个 Python HTML 表单生成器
  图书馆.
* [colander](https://github.com/Pylons/colander) - 一种
  字符串、映射和序列化/反序列化/验证库
  列表.
* [WTForms](https://github.com/wtforms/wtforms) - 是一种灵活的形式
  用于 Python Web 开发的验证和渲染库.
* [ColanderAlchemy](https://github.com/stefanofontanelli/ColanderAlchemy) -
  帮助您自动生成基于 SQLAlchemy 的漏勺模式
  映射类.
* [marshmallow](https://github.com/marshmallow-code/marshmallow) - 一种
  用于将复杂对象与简单 Python 相互转换的轻量级库
  数据类型（即（反）序列化和验证）.

## Media-Management

* [pyramid_elfinder](https://github.com/uralbash/pyramid_elfinder) - 这是
  elfinder 文件管理器的连接器，为金字塔框架编写.
* [pyramid_storage](https://github.com/danjac/pyramid_storage) - 这是一个用于在您的 Pyramid 框架应用程序中处理文件上传的包.

## RESTful API

*用于开发 RESTful API 的包.*

* [cornice](https://github.com/Cornices/cornice) - 提供帮手
  使用 Pyramid 构建和记录 REST 风格的 Web 服务，默认设置不错
  行为. 它负责以自动化方式遵循 HTTP 规范
  尽可能的方式.
* [rest_toolkit](https://github.com/wichert/rest_toolkit) - 是一个 Python 包
  它提供了一种非常方便的方式来构建 REST 服务器. 它建立在
  金字塔的顶部，但您不需要对金字塔了解太多就可以使用
  休息工具包.
* [pyramid_royal](https://github.com/hadrien/pyramid_royal) - 皇家是一个
  金字塔扩展，可简化编写 RESTful Web 应用程序.
* [cliquet](https://github.com/mozilla-services/cliquet) - Cliquet 是一个工具包
  简化 HTTP 微服务的实现，例如数据驱动的 REST
  蜜蜂.
* [webargs](https://github.com/sloria/webargs) - 一个友好的解析库
  HTTP 请求参数，内置支持流行的 Web 框架.
* [ramses](https://github.com/ramses-tech/ramses) - 使用生成 RESTful API
  拉姆. 它使用 Nefertari 提供基于 ElasticSearch 的视图.
* [nefertari](https://github.com/ramses-tech/nefertari) - Nefertari 是一个 REST
  API 框架位于 Pyramid 和 ElasticSearch 之上.
* [pyramid_swagger](https://github.com/striglia/pyramid_swagger) - 方便
  使用 Swagger 在 Pyramid webapp 中定义和验证接口的工具.  （Swagger 2.0 文档）
* [pyramid-openapi3](https://github.com/niteoweb/pyramid_openapi3)  - 根据 OpenAPI 3.0 文档验证金字塔视图. 类似于 pyramid_swagger 但适用于 OpenAPI 3.0.
* [pyramid_jsonapi](https://github.com/colinhiggs/pyramid-jsonapi) - 自动地 
  创建一个 [JSON API](http://jsonapi.org/) 使用数据库的标准 API
  sqlAlchemy ORM 和金字塔框架.
* [pyramid_apispec](https://github.com/ergo/pyramid_apispec) - 创建一个 OpenAPI
  使用 apispec 和 Marshmallow 模式的规范文件.


## Search

*为项目提供搜索功能的包.*

* [hypatia](https://github.com/Pylons/hypatia) - Python 索引和
  搜索系统.

## Security

*提高项目安全性的软件包.*

## Services

* [pyramid_sms](https://github.com/websauna/pyramid_sms) -
   Pyramid Web 框架的 SMS 服务.

## Settings

*帮助管理项目可配置性的包.*

* [pyramid_zcml](https://github.com/Pylons/pyramid_zcml) - Zope 配置
  Pyramid 的标记语言配置支持.
* [pyramid_services](https://github.com/mmerickel/pyramid_services) - 定义一个
  用于访问可插入服务层的模式和辅助方法
  在您的 Pyramid 应用程序中.
* [hupper](https://github.com/Pylons/hupper) - 开发人员的进程监视器/重新加载器
    可以监视文件的更改并重新启动该过程.

## Storage

*扩展现有存储后端功能的软件包或
提供新的存储后端.*

* [pyramid_tm](https://github.com/Pylons/pyramid_tm) - 中心化交易
  金字塔应用程序的管理（无中间件）.
* [zope.sqlalchemy](https://github.com/zopefoundation/zope.sqlalchemy) -
  SQLAlchemy 与事务管理的集成.
    * [Zope 事务管理器对我意味着什么（以及
      你)](https://metaclassical.com/what-the-zope-transaction-manager-means-to-me-and-you/)
* [pyramid_sqlalchemy](https://github.com/wichert/pyramid_sqlalchemy) -
  提供了一些基本的胶水，以方便在 Pyramid 中使用 SQLAlchemy.
* [pyramid_zodbconn](https://github.com/Pylons/pyramid_zodbconn) - ZODB
  Pyramid 的数据库连接管理.
* [pyramid_mongoengine](https://github.com/marioidival/pyramid_mongoengine) -
  基于flask-mongoengine的pyramid-mongoengine包
* [pyramid_mongodb](https://github.com/niallo/pyramid_mongodb) - 
  Basic Pyramid Scaffold 可轻松使用 MongoDB 实现 Pyramid Web 框架的持久性
* [pyramid-excel](https://github.com/pyexcel-webwares/pyramid-excel) - 金字塔excel是基于 [pyexcel](https://github.com/pyexcel/pyexcel) 并且可以轻松地使用/生成通过 HTTP 协议以及文件系统存储在 Excel 文件中的信息. 该库可以将excel数据转换为列表列表、记录列表（字典）、列表字典. 反之亦然. 因此，它让您可以专注于基于 Pyramid 的 Web 开发中的数据，而不是文件格式.

## Task Queue

*使使用任务/后台队列更容易的包.*

* [pyramid_celery](https://github.com/sontek/pyramid_celery) - 金字塔
  与 celery 集成的配置. 允许您使用金字塔 .ini 文件
  配置 celery 并在 celery 任务中设置金字塔配置.
* [pyramid_rq](https://github.com/wichert/pyramid_rq) - 支持使用 rq
  金字塔排队系统. 最简单的监控和使用方式
  [RQ](http://python-rq.org) 在您的金字塔项目中.

## Templates

* [pyramid_mako](https://github.com/Pylons/pyramid_mako) - Mako 模板
  Pyramid Web 框架的系统绑定.
* [pyramid_chameleon](https://github.com/Pylons/pyramid_chameleon) - 变色龙
  金字塔的模板编译器.
* [pyramid_jinja2](https://github.com/Pylons/pyramid_jinja2) - Jinja2
  Pyramid Web 框架的模板系统绑定.
* [Tonnikala](https://github.com/ztane/Tonnikala) - Python 模板引擎
  与金字塔集成
* [Kajiki](https://github.com/nandoflorestan/kajiki) - 提供快速格式良好的 XML 模板，具有 [Pyramid integration](https://github.com/nandoflorestan/kajiki/blob/master/kajiki/integration/pyramid.py)

## Testing

*帮助测试代码或生成测试数据的包.*

* [webtest](https://github.com/Pylons/webtest) - 包装任何 WSGI 应用程序和
  可以轻松地向该应用程序发送测试请求，而无需启动
  一个 HTTP 服务器.

## Translations

*包有助于翻译项目的任务.*

* [lingua](https://github.com/wichert/lingua) - Lingua 是一个带有工具的包
  从您的代码中提取可翻译文本，并检查现有
  翻译. 它取代了 gettext 中 xgettext 命令的使用，或
  来自 Babel 的 pybabel.
* [pyramid_i18n_helper](https://github.com/sahama/pyramid_i18n_helper) - 帮助创建新的 smgid 并将 msgid 转换为本地语言.

## Web frontend integration

* [PyramidVue](https://github.com/eddyekofo94/pyramidVue) - Pyramid 和 VueJs (JavaScript) 模板，带有 Hot-Module-Replacement 入门模板.

## Workflows

*执行流程、程序和/或业务任务管理的包.*

## Other

* [pyramid_layout](https://github.com/Pylons/pyramid_layout) - 金字塔附加组件
  用于管理 UI 布局.
* [pyramid_skins](https://github.com/Pylons/pyramid_skins) - 这个包
  提供了一个简单的框架来将代码与模板和资源集成.
* [waitress](https://github.com/Pylons/waitress) - 女服务员应该是一个
  具有非常可接受的性能的生产质量纯 Python WSGI 服务器.
  除了存在于 Python 标准库中的依赖项之外，它没有任何依赖项.
* [pyramid_handlers](https://github.com/Pylons/pyramid_handlers) - 类似物
  Pyramid 的塔式“控制器”.
* [pyramid_rpc](https://github.com/Pylons/pyramid_rpc) - RPC 服务插件
  Pyramid，以比 pyramid_xmlrpc 更可扩展的方式支持 XML-RPC
  支持 JSON-RPC 和 AMF.
* [pyramid_autodoc](https://github.com/SurveyMonkey/pyramid_autodoc) - 狮身人面像
  用于记录您的 Pyramid API 的扩展.
* [pyramid_pages](https://github.com/uralbash/pyramid_pages) - 提供一个
  将树页面集合添加到您的 Pyramid 应用程序. 这非常相似
  到 django.contrib.flatpages 但具有树结构和遍历算法
  在 URL 调度中.
* [paginate](https://github.com/Pylons/paginate) - Python 分页模块.
* [pyramid_tablib](https://github.com/lxneng/pyramid_tablib) - tablib 渲染器
  (xlsx, xls, csv) for pyramid
* [tomb_routes](https://github.com/sontek/tomb_routes) - 简单的实用程序库
  围绕金字塔路由
* [pyramid_extdirect](https://github.com/jenner/pyramid_extdirect)  - 这个金字塔插件为 ExtJS 中包含的 ExtDirect Sencha API 提供了一个路由器.  ExtDirect 允许直接通过 JavaScript 运行服务器端回调，而无需额外的 AJAX 样板. 
* [pyramid_retry](https://github.com/Pylons/pyramid_retry) - pyramid_retry 是 Pyramid 的执行策略，它包装请求，并且可以在向客户端指示失败之前在某些“可重试”错误条件下重试可配置的次数.

## Projects

*杰出的金字塔项目.*

## Framework

* [Ringo](http://www.ringo-framework.org/) - Ringo 是一个基于 Python 的高层
   Web 应用程序框架构建在 Pyramid 之上. 该框架可以使用
  构建基于表单的管理或管理软件.
* [cone.app](https://github.com/conestack/cone.app) - 基于 Pyramid 的综合 Web 应用程序存根.

## CMS

* [nive_cms](https://github.com/nive/nive_cms) - Nive 是专业
  基于python的移动和桌面网站的盒子内容管理系统
  和网络框架金字塔. 请参考网站 cms.nive.co
  详细资料.
* [substanced](https://github.com/Pylons/substanced) - 应用服务器
  建立在 Pyramid 网络框架之上. 它提供了一个用户界面
  管理内容以及库和实用程序，这使得它很容易
  创建应用程序.
* [Kotti](https://github.com/Kotti/Kotti) - 一个用户友好的、轻量级的和
  可扩展的网络内容管理系统. 基于 Pyramid 和 SQLAlchemy.
* [KARL](https://karlproject.readthedocs.io/en/latest/) - 一个中等大小
  应用程序（大约 8 万行 Python 代码）构建在 Pyramid 之上. 这是
  一个开源网络
  用于协作、组织内联网和知识管理的系统.
  它为维基、日历、手册、搜索、标记、
  评论和文件上传. 参见 KARL 站点下载和安装
  细节.
  
## Cookiecutters

* [Pylons](https://github.com/Pylons?q=cookiecutter) - 官方 cookiecutter 模板
* [Pyramid Runner](https://github.com/asif-mahmud/pyramid_runner) - 一个最小的金字塔
  scaffold 旨在提供一个入门模板来构建小型到大型的 Web 服务.
  
  * 基于遍历的应用程序
  * 仅 JSON 响应
  * JWT 认证策略
  * Alembic 用于数据库修订
  * 对基础测试、视图和模型基础的一些简单修改以减少打字


## e-Commerce

## Other

* [cluegun](https://github.com/Pylons/cluegun) - 一个简单的 pastebin 应用程序
  基于 Rocky Burt 的 ClueBin. 它演示了表单处理、安全性和
  在 Pyramid 应用程序中使用 ZODB.
* [shootout](https://github.com/Pylons/shootout) - 一个例子“想法
   Carlos de la Guardia 和 Lukasz Fidosz 的“竞争”申请. 它
  演示 URL 调度、简单的身份验证、与 SQLAlchemy 的集成
  和pyramid_simpleform.
* [virginia](https://github.com/Pylons/virginia) - 一个非常简单的动态
  文件渲染应用程序. 愿意渲染结构化文本
  文件系统目录中的文档、HTML 文档和图像. 这也是
  遍历的一个很好的例子. 此应用程序的早期版本运行
  repoze.org 网站.
* [Akhet](https://docs.pylonsproject.org/projects/akhet/en/latest/) - 一种
   Pyramid 库和演示应用程序，具有类似 Pylons 的感觉. 它最广为人知
  用于其以前的应用程序脚手架，它帮助用户从
       Pylons 和那些喜欢更像 Pylons 的 API 的人. 脚手架已经
      已退休，但演示也起到了类似的作用.
* [Khufu Project](http://khufuproject.github.io/) - 胡夫是一个应用程序
  Pyramid 的脚手架，提供与 Jinja2 和
  SQLAlchemy.
* [Ptah](https://github.com/ptahproject/ptah) - Ptah 是一个快速、有趣、开放
  源高级 Python Web 开发环境.
* [warehouse](https://github.com/pypa/warehouse) - 仓库是下一个
  生成 Python Package Repository 旨在替换遗留代码库
  目前为 PyPI 提供动力.
* [travelcrm](https://github.com/mazvv/travelcrm) - TravelCRM 是一种有效的免费开源应用程序，用于自动化各级旅行社的客户关系，从小型到大型网络.
* [RhodeCode](https://rhodecode.com/)  - 企业源代码管理平台. 它跨 Mercurial、Git 和 Subversion 存储库应用统一的用户控制、权限、代码审查和工具集成. 世界各地的大型且不断发展的软件团队使用 RhodeCode 在安全的防火墙后环境中进行协作. 

## Project Management

* [AppEnlight](https://getappenlight.com/) - Web 的性能、异常和正常运行时间监控

## Resources

在哪里可以发现新的 Pyramid 应用程序和项目.

## Books

* [Python Web Frameworks](http://www.oreilly.com/web-platform/free/python-web-frameworks.csp) - 深入了解顶部的细节
   六个 Python 框架——Django、Flask、Tornado、Bottle、Pyramid 和 CherryPy.

## Websites

* [Try Pyramid](https://trypyramid.com/) - 从小开始，大结局，
  保持完成框架. 官方网站.

## Conferences

* [Sushi Sprint at PloneConf 2018 in Tokyo, Japan](https://2018.ploneconf.org/sprints) （2018年11月10-11日）
* [Pyramid Workshop in Munich, Germany.](https://pyconweb.com/talks/28-05-2017/pyramid-workshop) （2017 年 5 月 28 日，上午 10:30 - 下午 12:30）
* [PloneConf 2017](https://2017.ploneconf.org/) - 巴塞罗那Plone数字体验大会（2017年10月16~22日）
* [PloneConf 2016](https://2016.ploneconf.org/) - 波士顿Plone数字体验大会（2016年10月17~23日）
* [DragonSprint 2016](http://dragonsprint.com/)  - DragonSprint 是一个为期一周的 Pyramid 冲刺. 冲刺赛于 12 月的第一周（5 日至 9 日）在欧盟斯洛文尼亚卢布尔雅那举行. 主要的两个 sprint 主题是 Pyramid 2.0 和 Pyramid for Newcomers.


## Videos
* [List of videos from the official site](https://docs.pylonsproject.org/projects/pyramid_cookbook/en/latest/misc/videos.html)
* [Online Video Courses at Talk Python Training](https://training.talkpython.fm/courses/all)
* [使用 Python 和 Pyramid 的 Web 应用程序
  框架](http://shop.oreilly.com/product/0636920041900.do) -
  在此 Web Applications with Python and the Pyramid Framework 培训中
  当然，专家作者 Paul Everitt 将教您所需的功能
  用于 Python Web 开发，以及 Pyramid 的独特功能. 这
  课程是为已经具备 Python 基础知识的用户设计的.

  您将首先了解单文件 Web 应用程序、模板和
  多条路线和景观. 从那里，保罗会教你关于 MyApp
   Python 包、视图和路由，以及模板和静态资产. 这
  视频教程还包括表单、数据库和会话、身份验证
  和授权，以及 JSON. 最后，您将了解可扩展性，
  包括自定义配置设置、扩展和覆盖，以及
  自定义视图谓词.

  完成此基于计算机的培训课程后，您将拥有
  对 Python web 所需的功能有了基本的了解
  开发和 Pyramid 独有的功能.

## Who uses it?

* [项目、网站、公司和组织使用
  Pyramid](https://trypyramid.com/community-powered-by-pyramid.html) - 将您的项目添加到列表中

## Contributing

只需使用您出色的 Pyramid 应用程序、项目或
resources.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，@uralbash 已放弃所有版权和相关
或此作品的邻接权.
