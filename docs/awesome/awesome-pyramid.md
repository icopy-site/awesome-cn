<div class="github-widget" data-repo="uralbash/awesome-pyramid"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Pyramid
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![IRC
Freenode](https://img.shields.io/badge/irc-freenode-blue.svg)](https://webchat.freenode.net/?channels=pyramid)

精选的Pyramid应用程序，项目和资源的精选列表. 受到和的启发
基于 [awesome-python](https://github.com/vinta/awesome-python/).


## Admin interface

*扩展管理界面，添加或改进功能的软件包.*

* [pyramid_formalchemy](https://github.com/FormAlchemy/pyramid_formalchemy) -
  为基于FormAlchemy的金字塔提供CRUD接口.
* [pyramid_sacrud](https://github.com/sacrud/pyramid_sacrud) -金字塔CRUD接口.
  提供金字塔的管理Web界面.
  与经典CRUD不同，pyramid_sacrud允许覆盖和灵活性
  自定义您的界面，类似于django.contrib.admin，但使用
  不同的后端提供资源.  [新架构]（
  <http://pyramid-sacrud.readthedocs.io/pages/contribute/architecture.html>)
  建立在资源和机制遍历的基础上，允许在各种情况下使用它.
    * [ps_alchemy](https://github.com/sacrud/ps_alchemy) -pyramid_sacrud的扩展
      提供SQLAlchemy模型.
    * [ps_tree](https://github.com/sacrud/ps_tree) -的扩展
      [pyramid_sacrud](https://github.com/sacrud/pyramid_sacrud) 显示
      记录列表（如树）. 这适用于以下型号
      [sqlalchemy_mptt](https://github.com/uralbash/sqlalchemy_mptt).
* [Websauna](https://websauna.org/docs/) -金字塔的完整堆栈应用程序框架

## Asset Management

*有助于管理项目静态资产的软件包.*

* [pyramid_webassets](https://github.com/sontek/pyramid_webassets) -金字塔
  用于使用webassets库的扩展.
* [pyramid_bowerstatic](https://github.com/mrijken/pyramid_bowerstatic) -
  Bowerstatic在金字塔中的集成

## Async

* [aiopyramid](https://github.com/housleyjk/aiopyramid) -使用运行金字塔
  异步
* [gevent-socketio](https://github.com/abourget/gevent-socketio) -
  gevent-socketio是Socket.IO协议的Python实现，
  由LearnBoost最初为Node.js开发，然后移植到其他
  语言.
* [Stargate](https://github.com/boothead/stargate) -星际之门是
  使用出色的功能向金字塔应用程序添加WebSockets支持
  eventlet库用于长时间运行的连接.
* [channelstream](https://github.com/AppEnlight/channelstream) -Web套接字通信服务器（gevent）.

## Authentication

*改进或扩展了金字塔身份验证方法的软件包.

* [pyramid_ldap](https://github.com/Pylons/pyramid_ldap) -LDAP
  金字塔的身份验证策略.
* [pyramid_ldap3](https://github.com/Cito/pyramid_ldap3) -提供LDAP认证
  基于ldap3软件包的Pyramid应用程序的服务.
* [pyramid_who](https://github.com/Pylons/pyramid_who) -认证政策
  使用repoze.who 2.0 API的金字塔.
* [velruse](https://github.com/bbangert/velruse) -简化第三方
   Web应用程序的身份验证. 它支持大多数身份验证
  [providers](https://github.com/bbangert/velruse/tree/master/velruse/providers).
* [pyramid_simpleauth](https://github.com/thruflo/pyramid_simpleauth) - 会议
  金字塔应用程序的基于身份验证和基于角色的安全性
* [Python Social Auth](https://github.com/omab/python-social-auth) - 社会
  认证/注册机制，支持大量
  [providers](https://github.com/omab/python-social-auth#auth-providers).
* [Authomatic](https://github.com/authomatic/authomatic) -简单但功能强大
  用于Python Web应用程序的授权/身份验证客户端库.
* [apex](https://github.com/cd34/apex) -金字塔工具包，塔架项目，
  to add Authentication and Authorization using Velruse (OAuth) and/or a local
  数据库，CSRF，ReCaptcha，会话，Flash消息和I18N.
* [pyramid_authsanity](https://github.com/usingnamespace/pyramid_authsanity) -
  这将使通过简单易行的安全身份验证策略变得更加简单
  使用后端.
* [pyramid_jwt](https://github.com/wichert/pyramid_jwt) -这个包
  使用[JSON Web令牌]实现对Pyramid的身份验证策略.
  该标准（[RFC 7519]）通常用于保护Backens API. 这
  优秀的[PyJWT]库用于JWT编码/解码逻辑.
* [pyramid_ipauth](https://github.com/mozilla-services/pyramid_ipauth) -
  基于远程IP地址的金字塔身份验证策略.

  [JSON Web令牌]：https://jwt.io/
  [RFC 7519]：https：//tools.ietf.org/html/rfc7519
  [PyJWT]：https://pyjwt.readthedocs.io/en/latest/


## Authorization

*与授权基础结构和权限相关的软件包.

* [ziggurat_foundations](https://github.com/ergo/ziggurat_foundations) -
  框架无关的sqlalchemy类集，可用于构建应用程序
  需要权限的一项简单任务.
* [pyramid_multiauth](https://github.com/mozilla-services/pyramid_multiauth) -
  金字塔的身份验证策略，可替代其他协议栈
  身份验证策略.
* [pyramid_authstack](https://github.com/wichert/pyramid_authstack) - 用
  金字塔的多个身份验证策略.
* [horus](https://github.com/Pylons/horus) -用户注册和登录系统
  for the Pyramid Web Framework.
* [pyramid_yosai](https://github.com/YosaiProject/pyramid_yosai) -与Python应用程序安全框架的金字塔集成，具有授权（rbac权限和角色），身份验证（2fa totp），会话管理和广泛的审计追踪功能https://yosaiproject.github.io/yosai/

## Caching & Session

*有助于缓存和会话的软件包.*

* [pyramid_beaker](https://github.com/Pylons/pyramid_beaker) -烧杯会议
  金字塔的工厂后端，也是缓存配置器.
    * [为什么要切换到
      dogpile.cache]（http://techspot.zzzeek.org/2012/04/19/using-beaker-for-caching-why-you-ll-want-to-switch-to-dogpile.cache/）
* [pyramid_redis_sessions](https://github.com/ericrasmussen/pyramid_redis_sessions) -
  由Redis支持的金字塔Web框架会话工厂.
* [pyramid_dogpile_cache](https://github.com/moriyoshi/pyramid_dogpile_cache) -
  金字塔的dogpile.cache配置包
* [pyramid_sessions](https://github.com/joulez/pyramid_sessions) - 多
  金字塔Web框架的会话支持
* [pyramid_nacl_session](https://github.com/Pylons/pyramid_nacl_session) -
  使用以下命令定义一个加密的，基于泡菜的Cookie序列化程序
  [PyNaCl](http://pynacl.readthedocs.io/en/latest/secret/) 产生
  Cookie状态的对称加密.

## Debugging

*有助于查找错误的软件包.*

* [pyramid_debugtoolbar](https://github.com/Pylons/pyramid_debugtoolbar) -
  提供了一个调试工具栏，在您开发金字塔时非常有用
  应用.
* [pyramid_exclog](https://github.com/Pylons/pyramid_exclog) -一个包装
  记录来自金字塔应用程序的异常.
* [pyramid_debugtoolbar_dogpile](https://github.com/jvanasco/pyramid_debugtoolbar_dogpile) -
  dogpile缓存对pyramid_debugtoolbar的支持
* [pyramid_ipython](https://github.com/Pylons/pyramid_ipython) -IPython
  金字塔的pshell的绑定
* [pyramid_bpython](https://github.com/Pylons/pyramid_bpython) -bpython
  金字塔的pshell的绑定
* [pyramid_pycallgraph](https://github.com/disko/pyramid_pycallgraph) -金字塔补间为每个请求生成一个调用图图像

## Email

*有助于管理电子邮件发送的软件包.*

* [pyramid_mailer](https://github.com/Pylons/pyramid_mailer) -的包装
  从您的Pyramid应用程序发送电子邮件.
* [pyramid_marrowmailer](https://github.com/domenkozar/pyramid_marrowmailer) -
  适用于marrow.mailer的金字塔集成软件包，以前称为TurboMail
* [pyramid_mailgun](https://github.com/evannook/pyramid_mailgun) -用于Pyramid框架的Mailgun集成.

## Forms

*扩展表格功能或添加新类型表格的软件包.

* [deform](https://github.com/Pylons/deform) -是Python HTML表单生成
  图书馆.
* [colander](https://github.com/Pylons/colander) - 一种
  字符串，映射和序列化/反序列化/验证库
  列表.
* [WTForms](https://github.com/wtforms/wtforms) -是一种灵活的形式
  python Web开发的验证和渲染库.
* [ColanderAlchemy](https://github.com/stefanofontanelli/ColanderAlchemy) -
  帮助您自动生成基于SQLAlchemy的Colander模式
  映射的类.
* [marshmallow](https://github.com/marshmallow-code/marshmallow) - 一种
  轻量级的库，用于将复杂的对象与简单的Python相互转换
  数据类型（即（反）序列化和验证）.

## Media-Management

* [pyramid_elfinder](https://github.com/uralbash/pyramid_elfinder) - 这是
  Elfinder文件管理器的容器，为金字塔框架编写.
* [pyramid_storage](https://github.com/danjac/pyramid_storage) -这是用于在Pyramid框架应用程序中处理文件上传的软件包.

## RESTful API

*用于开发RESTful API的软件包.

* [cornice](https://github.com/Cornices/cornice) -提供帮助
  使用Pyramid构建和记录REST式Web服务，默认情况下不错
  行为. 它负责自动遵循HTTP规范
  可能的方式.
* [rest_toolkit](https://github.com/wichert/rest_toolkit) -是Python套件
  这提供了构建REST服务器的非常方便的方法. 它建立在
  金字塔的顶部，但是您不需要了解太多有关使用金字塔的信息
  rest_toolkit.
* [pyramid_royal](https://github.com/hadrien/pyramid_royal) -皇家是
  金字塔扩展，可简化编写RESTful Web应用程序的过程.
* [cliquet](https://github.com/mozilla-services/cliquet) -球拍是一个工具包
  简化HTTP微服务的实现，例如数据驱动的REST
  蜜蜂.
* [webargs](https://github.com/sloria/webargs) -友好的解析库
  HTTP请求参数，对流行的Web框架具有内置支持.
* [ramses](https://github.com/ramses-tech/ramses) -使用生成RESTful API
   RAML. 它使用Nefertari来提供ElasticSearch支持的视图.
* [nefertari](https://github.com/ramses-tech/nefertari) -Nefertari是REST
  位于Pyramid和ElasticSearch之上的API框架.
* [pyramid_swagger](https://github.com/striglia/pyramid_swagger) - 方便
  使用Swagger在Pyramid Webapp中定义和验证界面的工具.  （Swagger 2.0文档）
* [pyramid-openapi3](https://github.com/niteoweb/pyramid_openapi3)  -针对OpenAPI 3.0文档验证金字塔视图. 与pyramid_swagger相似，但适用于OpenAPI 3.0.
* [pyramid_jsonapi](https://github.com/colinhiggs/pyramid-jsonapi) - 自动地 
  创建一个 [JSON API](http://jsonapi.org/) 使用
  sqlAlchemy ORM和金字塔框架.
* [pyramid_apispec](https://github.com/ergo/pyramid_apispec) -创建一个OpenAPI
  使用apispec和棉花糖架构的规范文件.


## Search

*为项目提供搜索功能的软件包.*

* [hypatia](https://github.com/Pylons/hypatia) -Python索引和
  搜索系统.

## Security

*提高项目安全性的软件包.*

## Services

* [pyramid_sms](https://github.com/websauna/pyramid_sms) -
   金字塔Web框架的SMS服务.

## Settings

*有助于管理项目可配置性的软件包.*

* [pyramid_zcml](https://github.com/Pylons/pyramid_zcml) -Zope配置
  金字塔的标记语言配置支持.
* [pyramid_services](https://github.com/mmerickel/pyramid_services) -定义一个
  用于从中访问可插拔服务层的模式和辅助方法
  在您的Pyramid应用程序中.
* [hupper](https://github.com/Pylons/hupper) -面向开发人员的过程监控器/重新加载器
    可以监视文件的更改并重新启动该过程.

## Storage

*扩展现有存储后端功能的软件包或
提供新的存储后端.*

* [pyramid_tm](https://github.com/Pylons/pyramid_tm) -集中交易
  金字塔应用程序的管理（无中间件）.
* [zope.sqlalchemy](https://github.com/zopefoundation/zope.sqlalchemy) -
  SQLAlchemy与事务管理的集成.
    * [Zope Transaction Manager对我的意义（和
      您）]（https://metaclassical.com/what-the-zope-transaction-manager-means-to-me-and-you/）
* [pyramid_sqlalchemy](https://github.com/wichert/pyramid_sqlalchemy) -
  提供一些基本的胶水来促进将SQLAlchemy与Pyramid结合使用.
* [pyramid_zodbconn](https://github.com/Pylons/pyramid_zodbconn) -ZODB
  金字塔的数据库连接管理.
* [pyramid_mongoengine](https://github.com/marioidival/pyramid_mongoengine) -
  基于flask-mongoengine的金字塔mongoengine软件包
* [pyramid_mongodb](https://github.com/niallo/pyramid_mongodb) - 
  基本的金字塔支架可轻松使用MongoDB来实现金字塔Web框架的持久性
* [pyramid-excel](https://github.com/pyexcel-webwares/pyramid-excel) -pyramid-excel基于 [pyexcel](https://github.com/pyexcel/pyexcel) 并易于通过HTTP协议以及在文件系统上使用/产生存储在excel文件中的信息. 该库可以将excel数据转换为列表列表，记录列表（字典），列表字典. 反之亦然. 因此，它使您可以专注于基于金字塔的Web开发中的数据，而不是文件格式.

## Task Queue

*使处理任务/后台队列更容易的软件包.*

* [pyramid_celery](https://github.com/sontek/pyramid_celery) -金字塔
  与芹菜整合的配置. 允许您使用金字塔.ini文件
  配置celery，并将金字塔配置包含在celery任务中.
* [pyramid_rq](https://github.com/wichert/pyramid_rq) -支持使用RQ
  金字塔排队系统. 监视和使用的最简单方法
  [RQ](http://python-rq.org) 在您的金字塔项目中.

## Templates

* [pyramid_mako](https://github.com/Pylons/pyramid_mako) -抹子模板
  Pyramid Web框架的系统绑定.
* [pyramid_chameleon](https://github.com/Pylons/pyramid_chameleon) -变色龙
  金字塔的模板编译器.
* [pyramid_jinja2](https://github.com/Pylons/pyramid_jinja2) -Jinja2
  为Pyramid Web框架模板化系统绑定.
* [Tonnikala](https://github.com/ztane/Tonnikala) -Python模板引擎
  与金字塔整合
* [Kajiki](https://github.com/nandoflorestan/kajiki) -提供格式正确的快速XML模板， [Pyramid integration](https://github.com/nandoflorestan/kajiki/blob/master/kajiki/integration/pyramid.py)

## Testing

*有助于测试代码或生成测试数据的软件包.*

* [webtest](https://github.com/Pylons/webtest) -包装任何WSGI应用程序，然后
  可以轻松地将测试请求发送到该应用程序，而无需启动
  HTTP服务器.

## Translations

*软件包有助于翻译项目.*

* [lingua](https://github.com/wichert/lingua) -Lingua是一个带有工具的软件包
  从您的代码中提取可翻译的文本，并检查现有
  翻译. 它替换了gettext中xgettext命令的使用，或者
  来自Babel的pybabel.
* [pyramid_i18n_helper](https://github.com/sahama/pyramid_i18n_helper) -帮助程序创建新的smgid并将msgid转换为本地lang.

## Web frontend integration

* [PyramidVue](https://github.com/eddyekofo94/pyramidVue) -带有Hot-Module-Replacement入门模板的Pyramid和VueJs（JavaScript）模板.

## Workflows

*进行流程，程序和/或业务任务管理的软件包.*

## Other

* [pyramid_layout](https://github.com/Pylons/pyramid_layout) -金字塔插件
  用于管理UI布局.
* [pyramid_skins](https://github.com/Pylons/pyramid_skins) -这个包
  提供了一个简单的框架来将代码与模板和资源集成在一起.
* [waitress](https://github.com/Pylons/waitress) -女服务员注定要成为一名
  具有生产质量的纯Python WSGI服务器，具有非常令人满意的性能.
  除了存在于Python标准库中的依赖项之外，它没有任何依赖项.
* [pyramid_handlers](https://github.com/Pylons/pyramid_handlers) -类似
  金字塔的塔式样式“控制器”.
* [pyramid_rpc](https://github.com/Pylons/pyramid_rpc) -的RPC服务附加组件
  金字塔以比pyramid_xmlrpc更可扩展的方式支持XML-RPC
  支持JSON-RPC和AMF.
* [pyramid_autodoc](https://github.com/SurveyMonkey/pyramid_autodoc) -狮身人面像
  文档金字塔API的扩展名.
* [pyramid_pages](https://github.com/uralbash/pyramid_pages) -提供一个
  金字塔应用程序的树页面集合. 这非常相似
  到django.contrib.flatpages，但具有树结构和遍历算法
  在URL分配中.
* [paginate](https://github.com/Pylons/paginate) -Python分页模块.
* [pyramid_tablib](https://github.com/lxneng/pyramid_tablib) -tablib渲染器
  (xlsx, xls, csv) for pyramid
* [tomb_routes](https://github.com/sontek/tomb_routes) -简单的实用程序库
  围绕金字塔路由
* [pyramid_extdirect](https://github.com/jenner/pyramid_extdirect)  -这个金字塔插件为ExtJS中包含的ExtDirect Sencha API提供了路由器.  ExtDirect允许直接通过JavaScript运行服务器端回调，而无需额外的AJAX样板. 
* [pyramid_retry](https://github.com/Pylons/pyramid_retry) -pyramid_retry是Pyramid的执行策略，用于包装请求，并可以在某些“可重试”错误条件下重试请求，次数可配置多次，然后再向客户端指示失败.

## Projects

*杰出的金字塔项目.*

## Framework

* [Ringo](http://www.ringo-framework.org/) -Ringo是基于Python的高级
   Web应用程序框架建立在Pyramid之上. 该框架可以使用
  构建基于表单的管理或管理软件.
* [cone.app](https://github.com/bluedynamics/cone.app) -金字塔顶部的综合Web应用程序存根.

## CMS

* [nive_cms](https://github.com/nive/nive_cms) -Nive是专业人士
  基于python的移动和桌面网站的盒子内容管理系统
  和网络框架金字塔. 请访问网站cms.nive.co以获取更多信息.
  详细资料.
* [substanced](https://github.com/Pylons/substanced) -应用服务器
  建立在Pyramid Web框架上. 它提供了一个用户界面
  管理内容以及库和实用程序，使其易于
  创建应用程序.
* [Kotti](https://github.com/Kotti/Kotti) -用户友好，重量轻，
  可扩展的Web内容管理系统. 基于Pyramid和SQLAlchemy.
* [KARL](https://karlproject.readthedocs.io/en/latest/) -中等大小
  在Pyramid之上构建的应用程序（大约80K行Python代码）. 这是
  开源网站
  协作，组织内部网和知识管理的系统.
  它提供了用于Wiki，日历，手册，搜索，标记，
  评论和文件上传. 请访问KARL网站进行下载和安装
  细节.
  
## Cookiecutters

* [Pylons](https://github.com/Pylons?q=cookiecutter) -官方cookiecutter模板
* [Pyramid Runner](https://github.com/asif-mahmud/pyramid_runner) -最小的金字塔
  旨在提供一个入门模板以构建小型到大型Web服务的脚手架.
  
  *基于遍历的应用程序
  *仅JSON响应
  * JWT身份验证策略
  * Alembic用于数据库修订
  *对基本测试，视图和模型的一些简单修改，以减少输入


## e-Commerce

## Other

* [cluegun](https://github.com/Pylons/cluegun) -一个简单的pastebin应用程序
  基于Rocky Burt的ClueBin. 它演示了表单处理，安全性和
  在金字塔应用程序中使用ZODB.
* [shootout](https://github.com/Pylons/shootout) -例如“想法”
  比赛”由Carlos de la Guardia和Lukasz Fidosz提出. 它
  演示URL分配，简单身份验证以及与SQLAlchemy的集成
  和pyramid_simpleform.
* [virginia](https://github.com/Pylons/virginia) -一个非常简单的动态
  文件渲染应用程序. 愿意渲染结构化文本
  文件系统目录中的文档，HTML文档和图像. 这也是
  遍历的一个很好的例子. 此应用程序的早期版本运行
  repoze.org网站.
* [Akhet](https://docs.pylonsproject.org/projects/akhet/en/latest/) - 一种
  金字塔库和演示应用程序，具有类似Pylons的感觉. 它最有名
  为其以前的应用程序支架提供帮助，从而帮助用户从
      定向塔和那些更喜欢类似于定向塔的API的人. 脚手架已经
      退休了，但演示版扮演了类似的角色.
* [Khufu Project](http://khufuproject.github.io/) -Khufu是一个应用程序
  金字塔的脚手架，提供了与Jinja2和
  SQLAlchemy.
* [Ptah](https://github.com/ptahproject/ptah) -Ptah快速，有趣，开放
  源高级Python Web开发环境.
* [warehouse](https://github.com/pypa/warehouse) -下一个仓库
  旨在替换旧代码库的新一代Python软件包系统信息库
  目前为PyPI提供支持.
* [travelcrm](https://github.com/mazvv/travelcrm) -TravelCRM是有效的免费开放源代码应用程序，可用于从小型到大型网络的各个级别的旅行社的客户关系自动化.
* [RhodeCode](https://rhodecode.com/)  -企业源代码管理平台. 它在Mercurial，Git和Subversion存储库中应用统一的用户控制，权限，代码审查和工具集成. 全球范围内不断壮大的软件团队正在使用RhodeCode在安全的防火墙环境中进行协作. 

## Project Management

* [AppEnlight](https://getappenlight.com/) -Web的性能，异常和正常运行时间监控

## Resources

在哪里发现新的Pyramid应用程序和项目.

## Books

* [Python Web Frameworks](http://www.oreilly.com/web-platform/free/python-web-frameworks.csp) -在顶部深入了解细节
   六个Python框架-Django，Flask，Tornado，Bottle，Pyramid和CherryPy.

## Websites

* [Try Pyramid](https://trypyramid.com/) -从小处开始，从大处完成，
  保持成品框架. 官方网站.

## Conferences

* [Sushi Sprint at PloneConf 2018 in Tokyo, Japan](https://2018.ploneconf.org/sprints) （2018年11月10-11日）
* [Pyramid Workshop in Munich, Germany.](https://pyconweb.com/talks/28-05-2017/pyramid-workshop) （2017年5月28日，上午10:30-下午12:30）
* [PloneConf 2017](https://2017.ploneconf.org/) -巴塞罗那克隆人数字体验会议（2017年10月16日至22日）
* [PloneConf 2016](https://2016.ploneconf.org/) -波士顿克隆数字体验会议（2016年10月17日至23日）
* [DragonSprint 2016](http://dragonsprint.com/)  -DragonSprint是对金字塔进行的为期一周的冲刺. 这项冲刺活动于12月的第一周（5日至9日）在欧盟的斯洛文尼亚卢布尔雅那举行. 冲刺的两个主要主题是Pyramid 2.0和Pyramid for Newcomers.


## Videos
* [List of videos from the official site](https://docs.pylonsproject.org/projects/pyramid_cookbook/en/latest/misc/videos.html)
* [Online Video Courses at Talk Python Training](https://training.talkpython.fm/courses/all)
* [带有Python和金字塔的Web应用程序
  框架]（http://shop.oreilly.com/product/0636920041900.do）-
  在本Web应用程序中使用Python和Pyramid框架进行培训
  课程，专家作者Paul Everitt将教您所需的功能
   Python Web开发以及Pyramid的独特功能. 这
  本课程是为已经具有Python基本知识的用户设计的.

  您将首先学习有关单个文件的Web应用程序，模板和
  多个路线和视图. 保罗将从那里教您有关MyApp的信息
   Python包，视图和路由以及模板和静态资产. 这
  视频教程还介绍了表单，数据库和会话，身份验证
  和授权以及JSON. 最后，您将了解可扩展性，
  包括自定义配置设置，扩展和覆盖，以及
  自定义视图谓词.

  完成此基于计算机的培训课程后，您将拥有
  对Python Web所需的功能有了基本的了解
  开发和金字塔独有的功能.

## Who uses it?

* [使用的项目，网站，公司和组织
  金字塔]（https://trypyramid.com/community-powered-by-pyramid.html）-将您的项目添加到列表中

## Contributing

只需分叉，然后使用您很棒的Pyramid应用，项目或
resources.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，@ uralbash放弃了所有版权及相关
或这项工作的邻近权利.
