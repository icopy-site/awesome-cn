<div class="github-widget" data-repo="uralbash/awesome-pyramid"></div>
## Awesome Pyramid
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![IRC
Freenode](https://img.shields.io/badge/irc-freenode-blue.svg)](https://webchat.freenode.net/?channels=pyramid)

精选的 Pyramid 应用程序、项目和资源列表. 灵感来自和
基于 [awesome-python](https://github.com/vinta/awesome-python/).


## Admin interface

*扩展管理界面、添加或改进功能的包.*

* [pyramid_formalchemy](https://github.com/FormAlchemy/pyramid_formalchemy) -
  基于FormAlchemy为金字塔提供CRUD接口.
* [pyramid_sacrud](https://github.com/sacrud/pyramid_sacrud) - 金字塔增删改查界面.
  为 Pyramid 提供管理 Web 界面.
  与经典的 CRUD 不同，pyramid_sacrud 允许覆盖和灵活性
  自定义您的界面，类似于 django.contrib.admin 但使用
  不同的后端提供资源.  [新架构](
  <http://pyramid-sacrud.readthedocs.io/pages/contribute/architecture.html>)
  建立在资源和机制遍历之上，允许在各种情况下使用它.
    * [ps_alchemy](https://github.com/sacrud/ps_alchemy) - pyramid_sacrud 的扩展
      它提供了 SQLAlchemy 模型.
    * [ps_tree](https://github.com/sacrud/ps_tree) - 扩展
      [pyramid_sacrud](https://github.com/sacrud/pyramid_sacrud) 显示
      作为树的记录列表. 这适用于来自的模型
      [sqlalchemy_mptt](https://github.com/uralbash/sqlalchemy_mptt).
* [Websauna](https://websauna.org/docs/) - Pyramid 的全栈应用程序框架

## Asset Management

*帮助管理项目静态资产的包.*

* [pyramid_webassets](https://github.com/sontek/pyramid_webassets) - 金字塔
  使用 webassets 库的扩展.
* [pyramid_bowerstatic](https://github.com/mrijken/pyramid_bowerstatic) -
  Bowerstatic 在 Pyramid 中的集成

## Async

* [aiopyramid](https://github.com/housleyjk/aiopyramid) - 使用运行金字塔
  异步.
* [gevent-socketio](https://github.com/abourget/gevent-socketio) -
  gevent-socketio 是 Socket.IO 协议的 Python 实现，
  最初由 LearnBoost 为 Node.js 开发，然后移植到其他
  语言.
* [Stargate](https://github.com/boothead/stargate) - 星际之门是一个包
  使用出色的方法将 WebSockets 支持添加到金字塔应用程序
  用于长时间运行连接的 eventlet 库.
* [channelstream](https://github.com/AppEnlight/channelstream) - 网络套接字通信服务器（通风口）.

## Authentication

*改进或扩展 Pyramid 身份验证方法的软件包.*

* [pyramid_ldap](https://github.com/Pylons/pyramid_ldap) - 一个 LDAP
  金字塔的身份验证策略.
* [pyramid_ldap3](https://github.com/Cito/pyramid_ldap3) - 提供 LDAP 身份验证
  基于 ldap3 包的 Pyramid 应用程序服务.
* [pyramid_who](https://github.com/Pylons/pyramid_who) - 身份验证策略
  使用 repoze.who 2.0 API 的金字塔.
* [velruse](https://github.com/bbangert/velruse) - 简化第三方
   Web 应用程序的身份验证. 它支持大部分授权
  [providers](https://github.com/bbangert/velruse/tree/master/velruse/providers).
* [pyramid_simpleauth](https://github.com/thruflo/pyramid_simpleauth) - 会议
  Pyramid 应用程序的基于身份验证和基于角色的安全性
* [Python Social Auth](https://github.com/omab/python-social-auth) - 社会
  认证/注册机制，支持大量
  [providers](https://github.com/omab/python-social-auth#auth-providers).
* [Authomatic](https://github.com/authomatic/authomatic) -  Simple yet powerful
  Python Web 应用程序的授权/身份验证客户端库.
* [apex](https://github.com/cd34/apex) - Pyramid 工具包，一个 Pylons 项目，
  使用 Velruse (OAuth) 和/或本地添加身份验证和授权
  数据库、CSRF、ReCaptcha、会话、Flash 消息和 I18N.
* [pyramid_authsanity](https://github.com/usingnamespace/pyramid_authsanity) -
  这将使拥有安全的身份验证策略变得更加简单
  使用后端.
* [pyramid_jwt](https://github.com/wichert/pyramid_jwt) - 这个包
  使用 [JSON Web Tokens] 为 Pyramid 实施身份验证策略.
  该标准（[RFC 7519]）通常用于保护后端 API. 这
  优秀的 [PyJWT] 库用于 JWT 编码/解码逻辑.
* [pyramid_ipauth](https://github.com/mozilla-services/pyramid_ipauth) -
  基于远程ip地址的金字塔认证策略.

  [JSON 网络令牌]：https://jwt.io/
  [RFC 7519]：https://tools.ietf.org/html/rfc7519
  [PyJWT]：https://pyjwt.readthedocs.io/en/latest/


## Authorization

*与授权基础设施和权限相关的包.*

* [ziggurat_foundations](https://github.com/ergo/ziggurat_foundations) -
  与框架无关的一组 sqlalchemy 类，用于构建应用程序
  需要权限的任务很容易.
* [pyramid_multiauth](https://github.com/mozilla-services/pyramid_multiauth) -
  Pyramid 的身份验证策略，代理到其他堆栈
  身份验证策略.
* [pyramid_authstack](https://github.com/wichert/pyramid_authstack) - 使用
  使用 Pyramid 的多个身份验证策略.
* [horus](https://github.com/Pylons/horus) - 用户注册和登录系统
  用于金字塔网络框架.
* [pyramid_yosai](https://github.com/YosaiProject/pyramid_yosai) - Pyramid 与 Python 应用程序的安全框架集成，具有授权（rbac 权限和角色）、身份验证（2fa totp）、会话管理和广泛的审计跟踪 https://yosaiproject.github.io/yosai/

## Caching & Session

*有助于缓存和会话的软件包.*

* [pyramid_beaker](https://github.com/Pylons/pyramid_beaker) - 烧杯会议
  Pyramid 的工厂后端，也是缓存配置器.
    * [为什么你要切换到
      dogpile.cache](http://techspot.zzzeek.org/2012/04/19/using-beaker-for-caching-why-you-ll-want-to-switch-to-dogpile.cache/)
* [pyramid_redis_sessions](https://github.com/ericrasmussen/pyramid_redis_sessions) -
  由 Redis 支持的 Pyramid Web 框架会话工厂.
* [pyramid_dogpile_cache](https://github.com/moriyoshi/pyramid_dogpile_cache) -
  Pyramid 的 dogpile.cache 配置包
* [pyramid_sessions](https://github.com/joulez/pyramid_sessions) - 多种
  对 Pyramid Web Framework 的会话支持
* [pyramid_nacl_session](https://github.com/Pylons/pyramid_nacl_session) -
  定义一个加密的、基于 pickle 的 cookie 序列化器，使用
  [PyNaCl](http://pynacl.readthedocs.io/en/latest/secret/) 生成
  cookie 状态的对称加密.

## Debugging

*帮助查找错误的软件包.*

* [pyramid_debugtoolbar](https://github.com/Pylons/pyramid_debugtoolbar) -
  提供调试工具栏，在您开发 Pyramid 时很有用
  应用.
* [pyramid_exclog](https://github.com/Pylons/pyramid_exclog) - 一个包裹
  记录 Pyramid 应用程序的异常.
* [pyramid_debugtoolbar_dogpile](https://github.com/jvanasco/pyramid_debugtoolbar_dogpile) -
  对 pyramid_debugtoolbar 的 dogpile 缓存支持
* [pyramid_ipython](https://github.com/Pylons/pyramid_ipython) - IPython
  Pyramid 的 pshell 的绑定
* [pyramid_bpython](https://github.com/Pylons/pyramid_bpython) -bpython
  Pyramid 的 pshell 的绑定
* [pyramid_pycallgraph](https://github.com/disko/pyramid_pycallgraph) - 金字塔补间为每个请求生成调用图图像

## Email

*帮助管理电子邮件发送的软件包.*

* [pyramid_mailer](https://github.com/Pylons/pyramid_mailer) - 一个包裹
  从您的 Pyramid 应用程序发送电子邮件.
* [pyramid_marrowmailer](https://github.com/domenkozar/pyramid_marrowmailer) -
  marrow.mailer 的金字塔集成包，以前称为 TurboMail
* [pyramid_mailgun](https://github.com/evannook/pyramid_mailgun) - 金字塔框架的 Mailgun 集成.

## Forms

*扩展表单功能或添加新类型表单的包.*

* [deform](https://github.com/Pylons/deform) - 是一个 Python HTML 表单生成
  图书馆.
* [colander](https://github.com/Pylons/colander) - A
  字符串、映射和的序列化/反序列化/验证库
  列出.
* [WTForms](https://github.com/wtforms/wtforms) - 是一种灵活的形式
  用于 python web 开发的验证和渲染库.
* [ColanderAlchemy](https://github.com/stefanofontanelli/ColanderAlchemy) -
  帮助您自动生成基于 SQLAlchemy 的漏勺模式
  映射类.
* [marshmallow](https://github.com/marshmallow-code/marshmallow) - A
  用于将复杂对象与简单 Python 相互转换的轻量级库
  数据类型（即（反）序列化和验证）.

## Media-Management

* [pyramid_elfinder](https://github.com/uralbash/pyramid_elfinder) - 这是
  elfinder 文件管理器的连接器，为金字塔框架编写.
* [pyramid_storage](https://github.com/danjac/pyramid_storage) - This is a package for handling file uploads in your Pyramid framework application.

## RESTful API

*用于开发 RESTful API 的软件包.*

* [cornice](https://github.com/Cornices/cornice) - 提供帮手
  使用 Pyramid 构建和记录 REST-ish Web 服务，具有不错的默认值
  行为. 它负责以自动化方式遵循 HTTP 规范
  尽可能的方式.
* [rest_toolkit](https://github.com/wichert/rest_toolkit) - 是一个 Python 包
  它提供了一种非常方便的方式来构建 REST 服务器. 它建立在
  Pyramid 的顶部，但你不需要对 Pyramid 了解太多就可以使用
  rest_toolkit.
* [pyramid_royal](https://github.com/hadrien/pyramid_royal) - 皇家是
  金字塔扩展，简化了 RESTful Web 应用程序的编写.
* [cliquet](https://github.com/mozilla-services/cliquet) - Cliquet 是一个工具包
  简化 HTTP 微服务的实施，例如数据驱动的 REST
  蜜蜂.
* [webargs](https://github.com/sloria/webargs) - 一个友好的解析库
  HTTP 请求参数，内置对流行网络框架的支持.
* [ramses](https://github.com/ramses-tech/ramses) - 使用生成 RESTful API
   RAML. 它使用 Nefertari，它提供 ElasticSearch 支持的视图.
* [nefertari](https://github.com/ramses-tech/nefertari) - REST不携带
  API 框架位于 Pyramid 和 ElasticSearch 之上.
* [pyramid_swagger](https://github.com/striglia/pyramid_swagger) - 方便
  使用 Swagger 在 Pyramid webapp 中定义和验证接口的工具.  （招摇2.0文档）
* [pyramid-openapi3](https://github.com/niteoweb/pyramid_openapi3)  - 根据 OpenAPI 3.0 文档验证 Pyramid 视图. 类似于 pyramid_swagger 但适用于 OpenAPI 3.0.
* [pyramid_jsonapi](https://github.com/colinhiggs/pyramid-jsonapi) - 自动地 
  创建一个 [JSON API](http://jsonapi.org/) 来自数据库的标准 API 使用
  sqlAlchemy ORM 和金字塔框架.
* [pyramid_apispec](https://github.com/ergo/pyramid_apispec) - 创建一个 OpenAPI
  使用 apispec 和棉花糖模式的规范文件.


## Search

*为项目提供搜索功能的包.*

* [hypatia](https://github.com/Pylons/hypatia) - 一个 Python 索引和
  搜索系统.

## Security

*提高项目安全性的软件包.*

## Services

* [pyramid_sms](https://github.com/websauna/pyramid_sms) -
   Pyramid 网络框架的 SMS 服务.

## Settings

*帮助管理项目可配置性的包.*

* [pyramid_zcml](https://github.com/Pylons/pyramid_zcml) - Zope配置
  Pyramid 的标记语言配置支持.
* [pyramid_services](https://github.com/mmerickel/pyramid_services) - 定义一个
  用于访问可插入服务层的模式和辅助方法
  在您的 Pyramid 应用程序中.
* [hupper](https://github.com/Pylons/hupper) - 开发人员的进程监视器/重新加载器
    可以监视文件的更改并重新启动进程.

## Storage

*扩展现有存储后端或
提供新的存储后端.*

* [pyramid_tm](https://github.com/Pylons/pyramid_tm) - 集中交易
  Pyramid 应用程序的管理（没有中间件）.
* [zope.sqlalchemy](https://github.com/zopefoundation/zope.sqlalchemy) -
  SQLAlchemy 与事务管理的集成.
    * [Zope 事务管理器对我意味着什么（以及
      你)](https://metaclassical.com/what-the-zope-transaction-manager-means-to-me-and-you/)
* [pyramid_sqlalchemy](https://github.com/wichert/pyramid_sqlalchemy) -
  提供了一些基本的胶水以方便将 SQLAlchemy 与 Pyramid 一起使用.
* [pyramid_zodbconn](https://github.com/Pylons/pyramid_zodbconn) - ZODB
  Pyramid 的数据库连接管理.
* [pyramid_mongoengine](https://github.com/marioidival/pyramid_mongoengine) -
  基于 flask-mongoengine 的 pyramid-mongoengine 包
* [pyramid_mongodb](https://github.com/niallo/pyramid_mongodb) - 
  基本的 Pyramid Scaffold 可以轻松地使用 MongoDB 来持久化 Pyramid Web 框架
* [pyramid-excel](https://github.com/pyexcel-webwares/pyramid-excel) - pyramid-excel是基于 [pyexcel](https://github.com/pyexcel/pyexcel) 并使通过 HTTP 协议以及文件系统轻松使用/生成存储在 excel 文件中的信息. 这个库可以把excel数据变成列表的列表，记录的列表（字典），列表的字典. 反之亦然. 因此，它可以让您专注于基于 Pyramid 的 Web 开发中的数据，而不是文件格式.

## Task Queue

*使处理任务/后台队列更容易的包.*

* [pyramid_celery](https://github.com/sontek/pyramid_celery) - 金字塔
  配置与芹菜集成. 允许您使用金字塔 .ini 文件
  配置芹菜并在芹菜任务中配置金字塔.
* [pyramid_rq](https://github.com/wichert/pyramid_rq) - 支持使用 rq
  带金字塔的排队系统. 最简单的监控和使用方式
  [RQ](http://python-rq.org) 在你的金字塔项目中.

## Templates

* [pyramid_mako](https://github.com/Pylons/pyramid_mako) - Mako 模板
  Pyramid 网络框架的系统绑定.
* [pyramid_chameleon](https://github.com/Pylons/pyramid_chameleon) - 变色龙
  金字塔的模板编译器.
* [pyramid_jinja2](https://github.com/Pylons/pyramid_jinja2) - Jinja2
  金字塔网络框架的模板系统绑定.
* [Tonnikala](https://github.com/ztane/Tonnikala) - Python 模板引擎
  与金字塔集成
* [Kajiki](https://github.com/nandoflorestan/kajiki) - 提供快速的格式良好的 XML 模板，与 [Pyramid integration](https://github.com/nandoflorestan/kajiki/blob/master/kajiki/integration/pyramid.py)

## Testing

*帮助测试代码或生成测试数据的包.*

* [webtest](https://github.com/Pylons/webtest) - 包装任何 WSGI 应用程序和
  无需启动即可轻松向该应用程序发送测试请求
  HTTP 服务器.

## Translations

*包有助于翻译项目的任务.*

* [lingua](https://github.com/wichert/lingua) - Lingua 是一个带有工具的包
  从您的代码中提取可翻译的文本，并检查现有
  翻译. 它取代了 gettext 中 xgettext 命令的使用，或者
  来自 Babel 的 pybabel.
* [pyramid_i18n_helper](https://github.com/sahama/pyramid_i18n_helper) - 创建新的 smgid 并将 msgid 翻译成本地语言的助手.

## Web frontend integration

* [PyramidVue](https://github.com/eddyekofo94/pyramidVue) - 带有热模块替换入门模板的金字塔和 VueJs (JavaScript) 模板.

## Workflows

*执行流程、程序和/或业务任务管理的软件包.*

## Other

* [pyramid_layout](https://github.com/Pylons/pyramid_layout) - 金字塔附加组件
  用于管理 UI 布局.
* [pyramid_skins](https://github.com/Pylons/pyramid_skins) - 这个包
  提供了一个简单的框架来将代码与模板和资源集成.
* [waitress](https://github.com/Pylons/waitress) - 女服务员应该是
  生产质量的纯 Python WSGI 服务器，具有非常可接受的性能.
  除了存在于 Python 标准库中的依赖项外，它没有任何依赖项.
* [pyramid_handlers](https://github.com/Pylons/pyramid_handlers) - 类似物
  Pyramid 的塔式“控制器”.
* [pyramid_rpc](https://github.com/Pylons/pyramid_rpc) - RPC 服务附加组件
  Pyramid，以比 pyramid_xmlrpc 更可扩展的方式支持 XML-RPC
  支持 JSON-RPC 和 AMF.
* [pyramid_autodoc](https://github.com/SurveyMonkey/pyramid_autodoc) - 狮身人面像
  用于记录 Pyramid API 的扩展.
* [pyramid_pages](https://github.com/uralbash/pyramid_pages) - 提供一个
  树页面的集合到您的 Pyramid 应用程序. 这个很相似
  到 django.contrib.flatpages 但具有树结构和遍历算法
  在 URL 调度中.
* [paginate](https://github.com/Pylons/paginate) - Python 分页模块.
* [pyramid_tablib](https://github.com/lxneng/pyramid_tablib) - 标签库渲染器
  (xlsx, xls, csv) 金字塔
* [tomb_routes](https://github.com/sontek/tomb_routes) - 简单的实用程序库
  围绕金字塔路由
* [pyramid_extdirect](https://github.com/jenner/pyramid_extdirect)  - 这个金字塔插件为 ExtJS 中包含的 ExtDirect Sencha API 提供了一个路由器.  ExtDirect 允许直接通过 JavaScript 运行服务器端回调，而无需额外的 AJAX 样板. 
* [pyramid_retry](https://github.com/Pylons/pyramid_retry) - pyramid_retry 是 Pyramid 的执行策略，它包装请求并可以在某些“可重试”错误条件下重试可配置的次数，然后再向客户端指示失败.

## Projects

*杰出的金字塔项目.*

## Framework

* [Ringo](http://www.ringo-framework.org/) - Ringo 是一个基于 Python 的高级
  建立在 Pyramid 之上的 Web 应用程序框架. 该框架可以使用
  构建基于表单的管理或管理软件.
* [cone.app](https://github.com/conestack/cone.app) - 位于金字塔之上的综合 Web 应用程序存根.

## CMS

* [nive_cms](https://github.com/nive/nive_cms) - Nive 是专业
  基于python的手机和桌面网站的盒子内容管理系统
  和网络框架金字塔. 请参考网站 cms.nive.co
  详细资料.
* [substanced](https://github.com/Pylons/substanced) - 一个应用服务器
  建立在金字塔网络框架之上. 它提供了一个用户界面
  管理内容以及库和实用程序，这使得它很容易
  创建应用程序.
* [Kotti](https://github.com/Kotti/Kotti) - 用户友好，重量轻，
  可扩展的网络内容管理系统. 基于金字塔和 SQLAlchemy.
* [KARL](https://karlproject.readthedocs.io/en/latest/) - 一个中等大小
  构建在 Pyramid 之上的应用程序（大约 80K 行 Python 代码）. 这是
  开源网站
  用于协作、组织内部网和知识管理的系统.
  它为 wiki、日历、手册、搜索、标记、
  评论和文件上传. 请参阅 KARL 站点以进行下载和安装
  细节.
  
## Cookiecutters

* [Pylons](https://github.com/Pylons?q=cookiecutter) - 官方 cookiecutter 模板
* [Pyramid Runner](https://github.com/asif-mahmud/pyramid_runner) - 一个最小的金字塔
  scaffold 旨在提供一个入门模板来构建小型到大型 web 服务.
  
  * 基于遍历的应用
  * 仅 JSON 响应
  * JWT认证策略
  * 用于数据库修订的 Alembic
  * 对基础测试、视图和模型基础进行一些简单修改以减少输入


## e-Commerce

## Other

* [cluegun](https://github.com/Pylons/cluegun) - 一个简单的 pastebin 应用程序
  基于 Rocky Burt 的 ClueBin. 它演示了表单处理、安全性和
  在 Pyramid 应用程序中使用 ZODB.
* [shootout](https://github.com/Pylons/shootout) - 一个例子“想法
   Carlos de la Guardia 和 Lukasz Fidosz 的竞争”申请. 它
  演示 URL 调度、简单身份验证、与 SQLAlchemy 的集成
  和 pyramid_simpleform.
* [virginia](https://github.com/Pylons/virginia) - 一个非常简单的动态
  文件渲染应用程序. 它愿意呈现结构化文本
  文件系统目录中的文档、HTML 文档和图像. 这也是
  遍历的一个很好的例子. 此应用程序的早期版本运行
  repoze.org 网站.
* [Akhet](https://docs.pylonsproject.org/projects/akhet/en/latest/) - A
  具有 Pylons 风格的 Pyramid 库和演示应用程序. 它最著名
  用于其以前的应用程序脚手架，它帮助用户从
       Pylons 和那些更喜欢 Pylons-like API 的人. 脚手架已经
      退休但演示扮演类似的角色.
* [Khufu Project](http://khufuproject.github.io/) - 胡夫是一个应用程序
  Pyramid 的脚手架，它提供了与 Jinja2 和
  SQL炼金术.
* [Ptah](https://github.com/ptahproject/ptah) - Ptah 是一个快速、有趣、开放
  源代码高级 Python Web 开发环境.
* [warehouse](https://github.com/pypa/warehouse) - 仓库是下一个
  生成 Python Package Repository 旨在替换遗留代码库
  目前为 PyPI 提供支持.
* [travelcrm](https://github.com/mazvv/travelcrm) - TravelCRM 是有效的免费和开源应用程序，用于从小型到大型网络的各级旅行社的客户关系自动化.
* [RhodeCode](https://rhodecode.com/) - enterprise source code management platform. It applies unified user control, permissions, code reviews, and tool integration across Mercurial, Git, and Subversion repositories. Large and growing software teams all over the world use RhodeCode to collaborate in a secure, behind-the-firewall environment. 

## Project Management

* [AppEnlight](https://getappenlight.com/) - Web 的性能、异常和正常运行时间监控

## Resources

在哪里可以发现新的 Pyramid 应用程序和项目.

## Books

* [Python Web Frameworks](http://www.oreilly.com/web-platform/free/python-web-frameworks.csp) - 深入了解顶部的细节
   六个 Python 框架——Django、Flask、Tornado、Bottle、Pyramid 和 CherryPy.

## Websites

* [Try Pyramid](https://trypyramid.com/) - 小处着手，大处着手，
  保持完成框架. 官方网站.

## Conferences

* [Sushi Sprint at PloneConf 2018 in Tokyo, Japan](https://2018.ploneconf.org/sprints) （2018年11月10-11日）
* [Pyramid Workshop in Munich, Germany.](https://pyconweb.com/talks/28-05-2017/pyramid-workshop) (2017年5月28日上午10时30分至中午12时30分)
* [PloneConf 2017](https://2017.ploneconf.org/) - 巴塞罗那克隆人数字体验大会（2017年10月16日~22日）
* [PloneConf 2016](https://2016.ploneconf.org/) - 波士顿克隆人数字体验大会（2016年10月17日~23日）
* [DragonSprint 2016](http://dragonsprint.com/)  - DragonSprint 是 Pyramid 上为期一周的冲刺. 冲刺赛将于 12 月的第一周（5 日至 9 日）在欧盟斯洛文尼亚的卢布尔雅那举行. 主要的两个冲刺主题是 Pyramid 2.0 和 Pyramid for Newcomers.


## Videos
* [List of videos from the official site](https://docs.pylonsproject.org/projects/pyramid_cookbook/en/latest/misc/videos.html)
* [Online Video Courses at Talk Python Training](https://training.talkpython.fm/courses/all)
* [使用 Python 和金字塔的 Web 应用程序
  框架](http://shop.oreilly.com/product/0636920041900.do) -
  在此使用 Python 和 Pyramid 框架培训的 Web 应用程序中
  当然，专家作者 Paul Everitt 会教您所需的功能
  用于 Python web 开发，以及 Pyramid 的独特功能. 这
  课程专为已经具备 Python 基础知识的用户设计.

  您将从学习单文件 Web 应用程序、模板和
  多条路线和观点. 从那里，Paul 将教您有关 MyApp 的知识
   Python 包、视图和路由，以及模板和静态资产. 这
  视频教程还涵盖表单、数据库和会话、身份验证
  和授权，以及 JSON. 最后，您将了解可扩展性，
  包括自定义配置设置、扩展和覆盖，以及
  自定义视图谓词.

  完成此基于计算机的培训课程后，您将拥有
  对 Python Web 所需的功能有了基本的了解
  开发和金字塔独有的功能.

## Who uses it?

* [使用的项目、网站、公司和组织
  Pyramid](https://trypyramid.com/community-powered-by-pyramid.html) - 将您的项目添加到列表中

## Contributing

只需使用您出色的 Pyramid 应用程序、项目或
resources.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，@uralbash 已放弃所有版权和相关
或该作品的邻接权.
