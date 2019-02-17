<div class="github-widget" data-repo="uralbash/awesome-pyramid"></div>
## Awesome Pyramid
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![IRC
Freenode](https://img.shields.io/badge/irc-freenode-blue.svg)](https://webchat.freenode.net/?channels=pyramid)

> [Sushi Sprint at PloneConf 2018 in Tokyo, Japan](https://2018.ploneconf.org/sprints) （2018年11月10日至11日）

 精彩的Pyramid应用程序，项目和资源的精选列表.  灵感来自和
基于 [awesome-python](https://github.com/vinta/awesome-python/).


## Admin interface

*扩展Admin界面，添加或改进功能的软件包.*

* [pyramid_formalchemy](https://github.com/FormAlchemy/pyramid_formalchemy) -
  为FormAlchemy提供金字塔的CRUD界面.
* [pyramid_sacrud](https://github.com/sacrud/pyramid_sacrud) - 金字塔CRUD界面.
  为Pyramid提供管理Web界面.
  与传统的CRUD不同，pyramid_sacrud允许覆盖和灵活性
  自定义您的界面，类似于django.contrib.admin但使用了
   不同的后端提供资源.  [新建筑]（
  <http://pyramid-sacrud.readthedocs.io/pages/contribute/architecture.html>)
  建立在资源和机制遍历上，允许在各种情况下使用它.
    * [ps_alchemy](https://github.com/sacrud/ps_alchemy) -  pyramid_sacrud的扩展名
      它提供了SQLAlchemy模型.
    * [ps_tree](https://github.com/sacrud/ps_tree) - 延期
      [pyramid_sacrud](https://github.com/sacrud/pyramid_sacrud) 哪个显示
       作为树的记录列表.  这适用于来自的模型
      [sqlalchemy_mptt](https://github.com/uralbash/sqlalchemy_mptt).
* [Websauna](https://websauna.org/docs/) -  Pyramid的完整堆栈应用程序框架

## Asset Management

*有助于管理项目静态资产的软件包.*

* [pyramid_webassets](https://github.com/sontek/pyramid_webassets) - 金字塔
  使用webassets库的扩展.
* [pyramid_bowerstatic](https://github.com/mrijken/pyramid_bowerstatic) -
  Bowerstatic在金字塔中的整合

## Async

* [aiopyramid](https://github.com/housleyjk/aiopyramid) - 使用运行金字塔
  ASYNCIO.
* [gevent-socketio](https://github.com/abourget/gevent-socketio) -
  gevent-socketio是Socket.IO协议的Python实现，
  最初由LearnBoost为Node.js开发，然后移植到其他
  语言.
* [Stargate](https://github.com/boothead/stargate) - 星际之门是一个包
  使用优秀的方法为金字塔应用程序添加WebSockets支持
  用于长时间连接的eventlet库.
* [channelstream](https://github.com/AppEnlight/channelstream) -  websocket通信服务器（fenced）.

## Authentication

*改进或扩展金字塔身份验证方法的软件包.*

* [pyramid_ldap](https://github.com/Pylons/pyramid_ldap) - 一个LDAP
  金字塔的身份验证政策.
* [pyramid_ldap3](https://github.com/Cito/pyramid_ldap3) - 提供LDAP身份验证
  基于ldap3包的Pyramid应用程序的服务.
* [pyramid_who](https://github.com/Pylons/pyramid_who) - 认证政策
  使用repoze.who 2.0 API进行金字塔.
* [velruse](https://github.com/bbangert/velruse) - 简化第三方
   Web应用程序的身份验证  它支持大多数身份验证
  [providers](https://github.com/bbangert/velruse/tree/master/velruse/providers).
* [pyramid_simpleauth](https://github.com/thruflo/pyramid_simpleauth) - 会议
  基于身份验证和基于角色的Pyramid应用程序安全性
* [Python Social Auth](https://github.com/omab/python-social-auth) - 社交
  认证/注册机制，支持大量
  [providers](https://github.com/omab/python-social-auth#auth-providers).
* [Authomatic](https://github.com/authomatic/authomatic) - 简单而强大
  Python Web应用程序的授权/身份验证客户端库.
* [apex](https://github.com/cd34/apex) - 金字塔工具包，一个Pylons项目，
  使用Velruse（OAuth）和/或本地添加身份验证和授权
  数据库，CSRF，ReCaptcha，会话，Flash消息和I18N.
* [pyramid_authsanity](https://github.com/usingnamespace/pyramid_authsanity) -
  这样可以简化安全的身份验证策略
  使用后端.
* [pyramid_jwt](https://github.com/wichert/pyramid_jwt) - 这个包
  使用[JSON Web Tokens]为Pyramid实现身份验证策略.
   此标准（[RFC 7519]）通常用于保护backens API.  该
  优秀的[PyJWT]库用于JWT编码/解码逻辑.
* [pyramid_ipauth](https://github.com/mozilla-services/pyramid_ipauth) -
  基于远程ip地址的金字塔身份验证策略.

  [JSON Web令牌]：https：//jwt.io/
  [RFC 7519]：https：//tools.ietf.org/html/rfc7519
  [PyJWT]：https：//pyjwt.readthedocs.io/en/latest/


## Authorization

*与授权基础架构和权限相关的包.*

* [ziggurat_foundations](https://github.com/ergo/ziggurat_foundations) -
  与构建应用程序的sqlalchemy类的框架无关的集合
  这需要权限一项简单的任务.
* [pyramid_multiauth](https://github.com/mozilla-services/pyramid_multiauth) -
  Pyramid的身份验证策略，代理其他堆栈
  身份验证策略
* [pyramid_authstack](https://github.com/wichert/pyramid_authstack) - 使用
  使用Pyramid的多个身份验证策略.
* [horus](https://github.com/Pylons/horus) - 用户注册和登录系统
  用于金字塔Web框架.
* [pyramid_yosai](https://github.com/YosaiProject/pyramid_yosai) -  Pyramid与安全框架的Python应用程序集成，其中包括授权（rbac权限和角色），身份验证（2fa totp），会话管理和广泛的审计跟踪https://yosaiproject.github.io/yosai/

## Caching & Session

*有助于缓存和会话的软件包.*

* [pyramid_beaker](https://github.com/Pylons/pyramid_beaker) - 烧杯会议
  工厂后端为Pyramid，也是缓存配置器.
    * [你为什么要切换到
      dogpile.cache]（http://techspot.zzzeek.org/2012/04/19/using-beaker-for-caching-why-you-ll-want-to-switch-to-dogpile.cache/）
* [pyramid_redis_sessions](https://github.com/ericrasmussen/pyramid_redis_sessions) -
  由Redis支持的金字塔Web框架会话工厂.
* [pyramid_dogpile_cache](https://github.com/moriyoshi/pyramid_dogpile_cache) -
  Pyramid的dogpile.cache配置包
* [pyramid_sessions](https://github.com/joulez/pyramid_sessions) - 多
  对Pyramid Web Framework的会话支持
* [pyramid_nacl_session](https://github.com/Pylons/pyramid_nacl_session) -
  使用.定义一个加密的，基于pickle的cookie序列化器
  [PyNaCl](http://pynacl.readthedocs.io/en/latest/secret/) 生成
  cookie状态的对称加密.

## Debugging

*帮助追捕错误的软件包.*

* [pyramid_debugtoolbar](https://github.com/Pylons/pyramid_debugtoolbar) -
  在开发金字塔时提供了一个有用的调试工具栏
  应用.
* [pyramid_exclog](https://github.com/Pylons/pyramid_exclog) - 一个包
  记录Pyramid应用程序中的异常.
* [pyramid_debugtoolbar_dogpile](https://github.com/jvanasco/pyramid_debugtoolbar_dogpile) -
  对pyramid_debugtoolbar的dogpile缓存支持
* [pyramid_ipython](https://github.com/Pylons/pyramid_ipython) -  IPython
  Pyramid的pshell绑定
* [pyramid_bpython](https://github.com/Pylons/pyramid_bpython) -  bpython
  Pyramid的pshell绑定
* [pyramid_pycallgraph](https://github.com/disko/pyramid_pycallgraph) - 金字塔补间为每个请求生成一个调用图像

## Email

*有助于管理电子邮件发送的软件包.*

* [pyramid_mailer](https://github.com/Pylons/pyramid_mailer) - 一个包
  从Pyramid应用程序发送电子邮件.
* [pyramid_marrowmailer](https://github.com/domenkozar/pyramid_marrowmailer) -
  用于marrow.mailer的Pyramid集成包，以前称为TurboMail
* [pyramid_mailgun](https://github.com/evannook/pyramid_mailgun) -
  用于marrow.mailer的Pyramid集成包，以前称为TurboMail

## Forms

*扩展表单功能或添加新类型表单的包.*

* [deform](https://github.com/Pylons/deform) - 是一个Python HTML表单生成
  图书馆.
* [colander](https://github.com/Pylons/colander) - 一个
  用于字符串，映射和的序列化/反序列化/验证库
  名单.
* [WTForms](https://github.com/wtforms/wtforms) - 是一种灵活的形式
  用于python web开发的验证和呈现库.
* [ColanderAlchemy](https://github.com/stefanofontanelli/ColanderAlchemy) -
  帮助您自动生成基于SQLAlchemy的Colander模式
  映射类.
* [marshmallow](https://github.com/marshmallow-code/marshmallow) - 一个
  轻量级库，用于将复杂对象转换为简单的Python
  数据类型（即（de）序列化和验证）.

## Media-Management

* [pyramid_elfinder](https://github.com/uralbash/pyramid_elfinder) - This is
  elfinder文件管理器的conector，为金字塔框架编写.
* [pyramid_storage](https://github.com/danjac/pyramid_storage) - 这是一个用于处理Pyramid框架应用程序中的文件上传的包.

## RESTful API

*用于开发RESTful API的软件包.*

* [cornice](https://github.com/Cornices/cornice) - 提供帮助
  使用Pyramid构建和记录REST-ish Web服务，具有良好的默认值
   行为.  它负责自动遵循HTTP规范
  尽可能的方式.
* [rest_toolkit](https://github.com/wichert/rest_toolkit) - 是一个Python包
   这提供了一种非常方便的方法来构建REST服务器.  它建立在
  金字塔顶部，但你不需要太多了解金字塔使用
  rest_toolkit.
* [pyramid_royal](https://github.com/hadrien/pyramid_royal) - 皇家是一个
  金字塔扩展，可以轻松编写RESTful Web应用程序.
* [cliquet](https://github.com/mozilla-services/cliquet) -  Cliquet是一个工具包
  轻松实现HTTP微服务，例如数据驱动的REST
  蜜蜂.
* [webargs](https://github.com/sloria/webargs) - 一个友好的解析库
  HTTP请求参数，内置支持流行的Web框架.
* [ramses](https://github.com/ramses-tech/ramses) - 使用生成RESTful API
   肾错构瘤.  它使用Nefertari提供ElasticSearch支持的视图.
* [nefertari](https://github.com/ramses-tech/nefertari) -  Nefertari是一个REST
  API框架位于Pyramid和ElasticSearch之上.
* [pyramid_swagger](https://github.com/striglia/pyramid_swagger) - 方便
  使用Swagger在Pyramid webapp中定义和验证接口的工具.
* [pyramid_jsonapi](https://github.com/colinhiggs/pyramid-jsonapi) - 自动 
  创建一个 [JSON API](http://jsonapi.org/) 来自数据库的标准API使用
  sqlAlchemy ORM和金字塔框架.
* [pyramid_apispec](https://github.com/ergo/pyramid_apispec) - 创建一个OpenAPI
  使用apispec和Marshmallow模式的规范文件.

## Search

*为项目提供搜索功能的软件包.*

* [hypatia](https://github.com/Pylons/hypatia) -  Python索引和
  搜索系统.

## Security

*提高项目安全性的软件包.*

## Services

* [pyramid_sms](https://github.com/websauna/pyramid_sms) -
   Pyramid Web框架的SMS服务.

## Settings

*有助于管理项目可配置性的软件包.*

* [pyramid_zcml](https://github.com/Pylons/pyramid_zcml) -  Zope配置
  Pyramid的标记语言配置支持.
* [pyramid_services](https://github.com/mmerickel/pyramid_services) - 定义一个
  用于访问可插入服务层的模式和帮助方法
  在你的金字塔应用程序中.
* [hupper](https://github.com/Pylons/hupper) - 开发人员的进程监视器/重新加载器
    可以监视文件的更改并重新启动该过程.

## Storage

*扩展现有存储后端功能的软件包
提供新的存储后端.*

* [pyramid_tm](https://github.com/Pylons/pyramid_tm) - 集中交易
  金字塔应用程序的管理（没有中间件）.
* [zope.sqlalchemy](https://github.com/zopefoundation/zope.sqlalchemy) -
  SQLAlchemy与事务管理的集成.
    * [Zope交易经理对我意味着什么（和
      你）（https://metaclassical.com/what-the-zope-transaction-manager-means-to-me-and-you/）
* [pyramid_sqlalchemy](https://github.com/wichert/pyramid_sqlalchemy) -
  提供了一些基本的粘合剂，以方便使用SQLAlchemy和Pyramid.
* [pyramid_zodbconn](https://github.com/Pylons/pyramid_zodbconn) -  ZODB
  Pyramid的数据库连接管理.
* [pyramid_mongoengine](https://github.com/marioidival/pyramid_mongoengine) -
  金字塔 -  mongoengine包基于烧瓶 - 在其他地方
* [pyramid_mongodb](https://github.com/niallo/pyramid_mongodb) - 
  基本金字塔脚手架可以轻松使用MongoDB与Pyramid Web框架进行持久化
* [pyramid-excel](https://github.com/pyexcel-webwares/pyramid-excel) -  pyramid-excel基于 [pyexcel](https://github.com/pyexcel/pyexcel)  并且可以通过HTTP协议以及文件系统轻松地使用/生成存储在excel文件中的信息.  该库可以将excel数据转换为列表列表，记录列表（字典），列表字典.  反之亦然.  因此，它可以让您专注于基于金字塔的Web开发中的数据，而不是文件格式.

## Task Queue

*使任务/背景队列更容易使用的软件包.*

* [pyramid_celery](https://github.com/sontek/pyramid_celery) - 金字塔
   配置芹菜整合.  允许您使用金字塔.ini文件
  配置芹菜并在芹菜任务中进行金字塔配置.
* [pyramid_rq](https://github.com/wichert/pyramid_rq) - 使用rq支持
   金字塔排队系统.  最简单的监控和使用方式
  [RQ](http://python-rq.org) 在你的金字塔项目中.

## Templates

* [pyramid_mako](https://github.com/Pylons/pyramid_mako) -  Mako模板
  Pyramid Web框架的系统绑定.
* [pyramid_chameleon](https://github.com/Pylons/pyramid_chameleon) - 变色龙
  金字塔的模板编译器.
* [pyramid_jinja2](https://github.com/Pylons/pyramid_jinja2) -  Jinja2
  金字塔Web框架的模板系统绑定.
* [Tonnikala](https://github.com/ztane/Tonnikala) -  Python模板引擎
  与金字塔集成
* [Kajiki](https://github.com/nandoflorestan/kajiki) - 提供快速格式良好的XML模板 [Pyramid integration](https://github.com/nandoflorestan/kajiki/blob/master/kajiki/integration/pyramid.py)

## Testing

*帮助测试代码或生成测试数据的软件包.*

* [webtest](https://github.com/Pylons/webtest) - 包装任何WSGI应用程序和
  无需启动即可轻松将测试请求发送到该应用程序
  一个HTTP服务器.

## Translations

*包帮助完成翻译项目的任务.*

* [lingua](https://github.com/wichert/lingua) -  Lingua是一个带工具的包
  从您的代码中提取可翻译文本，并检查现有文本
   翻译.  它取代了gettext中xgettext命令的使用，或者
  来自巴贝尔的pybabel.
* [pyramid_i18n_helper](https://github.com/sahama/pyramid_i18n_helper) - 帮助创建新的smgid并将msgid转换为本地语言.

## Web frontend integration

* [PyramidVue](https://github.com/eddyekofo94/pyramidVue) - 带有热模块替换启动器模板的金字塔和VueJs（JavaScript）模板.

## Workflows

*进行流程，程序和/或业务任务管理的软件包.*

## Other

* [pyramid_layout](https://github.com/Pylons/pyramid_layout) - 金字塔附加组件
  用于管理UI布局.
* [pyramid_skins](https://github.com/Pylons/pyramid_skins) - 这个包
  提供了一个简单的框架来集成代码与模板和资源.
* [waitress](https://github.com/Pylons/waitress) - 女服务员应该是一个
  生产质量纯的Python WSGI服务器，具有非常可接受的性能.
  它除了存在于Python标准库中的依赖项之外没有依赖项.
* [pyramid_handlers](https://github.com/Pylons/pyramid_handlers) - 类似
  金字塔的挂架式“控制器”.
* [pyramid_rpc](https://github.com/Pylons/pyramid_rpc) -  RPC服务加载项
  Pyramid以比pyramid_xmlrpc更可扩展的方式支持XML-RPC
  支持JSON-RPC和AMF.
* [pyramid_autodoc](https://github.com/SurveyMonkey/pyramid_autodoc) - 狮身人面像
  用于记录Pyramid API的扩展.
* [pyramid_pages](https://github.com/uralbash/pyramid_pages) - 提供一个
   树页面集合到Pyramid应用程序.  这非常相似
  到django.contrib.flatpages但具有树结构和遍历算法
  在URL dispath中.
* [paginate](https://github.com/Pylons/paginate) -  Python分页模块.
* [pyramid_tablib](https://github.com/lxneng/pyramid_tablib) -  tablib渲染器
  （xlsx，xls，csv）金字塔
* [tomb_routes](https://github.com/sontek/tomb_routes) - 简单的实用程序库
  围绕金字塔路由
* [pyramid_extdirect](https://github.com/jenner/pyramid_extdirect)   - 这个金字塔插件为ExtJS中包含的ExtDirect Sencha API提供了一个路由器.  ExtDirect允许直接通过JavaScript运行服务器端回调，而无需额外的AJAX样板. 
* [pyramid_retry](https://github.com/Pylons/pyramid_retry) -  pyramid_retry是Pyramid的执行策略，它包装请求，并且在指示客户端失败之前，可以在某些“可重试”错误条件下重试它们可配置的次数.

## Projects

*杰出的金字塔项目.*

## Framework

* [Ringo](http://www.ringo-framework.org/) -  Ringo是基于Python的高级别
   Web应用程序框架构建在Pyramid之上.  可以使用该框架
  构建基于表单的管理或管理软件.
* [cone.app](https://github.com/bluedynamics/cone.app) - 金字塔顶部的综合Web应用程序存根.

## CMS

* [nive_cms](https://github.com/nive/nive_cms) -  Nive很专业
  基于python的移动和桌面网站的盒子内容管理系统
   和webframework金字塔.  请访问网站cms.nive.co了解
  详细资料.
* [substanced](https://github.com/Pylons/substanced) - 应用程序服务器
   建立在金字塔网络框架之上.  它提供了一个用户界面
  管理内容以及使其易于使用的库和实用程序
  创建应用程序
* [Kotti](https://github.com/Kotti/Kotti) - 用户友好，重量轻，重量轻
   可扩展的Web内容管理系统.  基于Pyramid和SQLAlchemy.
* [KARL](https://karlproject.readthedocs.io/en/latest/) - 中等大小
   应用程序（大约80K行的Python代码）构建在Pyramid之上.  它是
  一个开源的网络
  协作系统，组织内联网和知识管理系统.
  它提供维基，日历，手册，搜索，标记，
   评论和文件上传.  请参阅KARL站点以进行下载和安装
  细节.
  
## Cookiecutters

* [Pylons](https://github.com/Pylons?q=cookiecutter) - 官方cookiecutter模板
* [Pyramid Runner](https://github.com/asif-mahmud/pyramid_runner) - A minimal Pyramid
  脚手架旨在提供一个入门模板来构建从小到大的Web服务.
  
  *基于遍历的应用程序
  *仅JSON响应
  * JWT身份验证策略
  * Alembic用于数据库修订
  *对基本测试，视图和模型的一些简单修改，以减少键入


## e-Commerce

## Other

* [cluegun](https://github.com/Pylons/cluegun) - 一个简单的pastebin应用程序
   基于Rocky Burt的ClueBin.  它演示了表单处理，安全性和
  在Pyramid应用程序中使用ZODB.
* [shootout](https://github.com/Pylons/shootout) - 一个例子“的想法
   竞争“Carlos de la Guardia和Lukasz Fidosz的申请.  它
  演示URL分派，简单身份验证，与SQLAlchemy集成
  和pyramid_simpleform.
* [virginia](https://github.com/Pylons/virginia) - 一个非常简单的动态
   文件呈现应用程序  它愿意呈现结构化文本
   文档，HTML文档和文件系统目录中的图像.  这也是
   遍历的一个很好的例子.  该应用程序的早期版本运行
  repoze.org网站.
* [Akhet](https://docs.pylonsproject.org/projects/akhet/en/latest/) - 一个
   金字塔图书馆和演示应用程序，具有类似Pylons的感觉.  它最为人所知
  因其以前的应用程序脚手架，帮助用户过渡
       Pylons和那些喜欢更像Pylons的API的人.  脚手架已经
      退休，但演示扮演类似的角色.
* [Khufu Project](http://khufuproject.github.io/) - 胡夫是一个申请
  金字塔的脚手架，提供与Jinja2和
  SQLAlchemy的.
* [Ptah](https://github.com/ptahproject/ptah) -  Ptah快速，有趣，开放
  源高级Python Web开发环境.
* [warehouse](https://github.com/pypa/warehouse) - 仓库是下一个
  生成Python包存储库旨在替换遗留代码库
  目前为PyPI提供支持.
* [travelcrm](https://github.com/mazvv/travelcrm) -  TravelCRM是一个有效的免费和开源应用程序，用于从小型网络到大型网络的各级旅行社的客户关系自动化.
* [RhodeCode](https://rhodecode.com/)   - 企业源代码管理平台.  它在Mercurial，Git和Subversion存储库中应用统一的用户控制，权限，代码审查和工具集成.  全世界大型且不断发展的软件团队使用RhodeCode在安全的防火墙后环境中进行协作. 

## Project Management

* [AppEnlight](https://getappenlight.com/) -  Web的性能，异常和正常运行时间监视

## Resources

在哪里发现新的Pyramid应用程序和项目.

## Books

* [Python Web Frameworks](http://www.oreilly.com/web-platform/free/python-web-frameworks.csp) - 深入细节
   six Python frameworks—Django, Flask, Tornado, Bottle, Pyramid, and CherryPy.

## Websites

* [Try Pyramid](https://trypyramid.com/) - 开始小，完成大，
   保持完成框架.  官方网站.

## Conferences

* [Sushi Sprint at PloneConf 2018 in Tokyo, Japan](https://2018.ploneconf.org/sprints) （2018年11月10日至11日）
* [Pyramid Workshop in Munich, Germany.](https://pyconweb.com/talks/28-05-2017/pyramid-workshop) （2017年5月28日上午10:30  - 下午12:30）
* [PloneConf 2017](https://2017.ploneconf.org/) - 巴塞罗那Plone数字体验大会（2017年10月16日至22日）
* [PloneConf 2016](https://2016.ploneconf.org/) -  Boston Plone数字体验大会（2016年10月17日至23日）
* [DragonSprint 2016](http://dragonsprint.com/)   -  DragonSprint是金字塔上为期一周的冲刺.  冲刺发生在12月的第一周（5日至9日）在欧盟斯洛文尼亚的卢布尔雅那.  主要的两个冲刺主题是Pyramid 2.0和Pyramid for Newcomers.


## Videos
* [List of videos from the official site](https://docs.pylonsproject.org/projects/pyramid_cookbook/en/latest/misc/videos.html)
* [Online Video Courses at Talk Python Training](https://training.talkpython.fm/courses/all)
* [使用Python和金字塔的Web应用程序
  框架]（http://shop.oreilly.com/product/0636920041900.do） - 
  在此Web应用程序中使用Python和Pyramid Framework进行培训
  当然，专家作者保罗埃弗里特将教你所需的功能
   用于Python Web开发，以及Pyramid的独特功能.  这个
  课程专为已具备Python基础知识的用户设计.

  您将首先了解单个文件Web应用程序，模板和
   多条路线和视图.  从那里，保罗将教你关于MyApp
   Python包，视图和路由以及模板和静态资产.  这个
  视频教程还包括表单，数据库和会话，身份验证
   和授权，以及JSON.  最后，您将了解可扩展性，
  包括自定义配置设置，扩展和覆盖，以及
  自定义视图谓词.

  完成这个基于计算机的培训课程后，您将拥有
  基本了解Python Web所需的功能
  开发和Pyramid独有的功能.

## Who uses it?

* [使用的项目，网站，公司和组织
  金字塔]（https://trypyramid.com/community-powered-by-pyramid.html） - 将您的项目添加到列表中

## Contributing

只需使用你真棒的Pyramid应用程序，项目或者发送拉取请求
resources.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，@uralbash已放弃所有版权和相关内容
或相邻的权利.
