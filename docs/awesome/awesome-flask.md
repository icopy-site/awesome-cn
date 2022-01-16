<div class="github-widget" data-repo="mjhea0/awesome-flask"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Flask [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

&gt; 与 Flask 相关的精彩内容的精选列表.

<!--lint ignore double-link-->
[Flask](https://flask.palletsprojects.com/) 是一个用 Python 编写的轻量级 WSGI Web 应用程序框架.



## Third-Party Extensions

### Admin

- [Flask-Admin](https://github.com/flask-admin/flask-admin) - 功能性管理面板，提供用于根据您的模型管理数据的用户界面.

### APIs

#### RESTful API Support

- [Eve](https://docs.python-eve.org) - 为人类设计的 RESTful API 框架.
- [Flask-Classful](https://flask-classful.teracy.org/) - 添加了对用于设置 RESTful API 路由端点的基于类的视图的支持.
- [Flask-MongoRest](https://github.com/closeio/flask-mongorest) - RESTful API 框架 [MongoEngine](http://mongoengine.org/).
- [Flask-RESTful](https://flask-restful.readthedocs.io) - 快速构建 RESTful API.

#### RESTful API + Swagger/OpenAPI Documentation Support

- [Connexion](https://connexion.readthedocs.io) - 基于 Flask 的开源、基于 OpenAPI 的 REST 框架.
- [Flask-Rebar](https://github.com/plangrid/flask-rebar) - 结合烧瓶， [marshmallow](https://marshmallow.readthedocs.io/)， 和 [OpenAPI](https://www.openapis.org/) 用于强大的 REST 服务.
- [Flask-RESTX](https://flask-restx.readthedocs.io) - 社区驱动的分叉 [Flask-RESTPlus](https://flask-restplus.readthedocs.io/) 这使得使用 Flask 构建和记录 RESTful API 变得容易.

#### Swagger/OpenAPI Documentation Support

- [Flask-APISpec](https://flask-apispec.readthedocs.io/) - 自动记录 REST API.
- [SAFRS: Python OpenAPI & JSON:API Framework](https://github.com/thomaxxl/safrs) - SAFRS 是 *S*ql*A*lchemy *F*lask-*R*estful *S*wagger 的首字母缩写词，旨在帮助开发人员为 SQLAlchemy 数据库对象和关系创建自记录 JSON API.

### Auth

#### Basic Auth and Session-based (for HTML Endpoints)

- [Flask-HTTPAuth](https://flask-httpauth.readthedocs.io) - 验证.
- [Flask-Login](https://flask-login.readthedocs.io/) - 帐户管理和身份验证.
- [Flask Principal](https://pythonhosted.org/Flask-Principal/) - 授权.
- [Flask-Security-Too](https://flask-security-too.readthedocs.io/en/stable/) - 账户管理、认证、授权.
- [Flask-SimpleLogin](https://github.com/flask-extensions/Flask-SimpleLogin) - 验证.
- [Flask-User](https://flask-user.readthedocs.io) - 账户管理、认证、授权.

 &gt; 好奇 Flask-User 和 Flask-Security 的区别？ 查看 Flask 用户 [FAQ](https://flask-user.readthedocs.io/en/latest/faq.html).

#### JWT-based (for JSON Endpoints)

- [Flask-JWT](https://pythonhosted.org/Flask-JWT/) - 对使用 JWT 的基本支持.
- [Flask-JWT-Extended](https://flask-jwt-extended.readthedocs.io) - 对使用 JWT 的高级支持.
- [Flask-JWT-Router](https://github.com/joegasewicz/flask-jwt-router) - 将授权路由添加到 Flask 应用程序.
- [Flask-Praetorian](https://flask-praetorian.readthedocs.io) - Flask API 的身份验证和授权.

#### OAuth

- [Authlib](https://authlib.org/) - 用于构建 OAuth 和 OpenID 客户端和服务器的库.
- [Authomatic](https://github.com/authomatic/authomatic) - 用于 Python Web 应用程序的框架无关库，可通过 OAuth 和 OpenID 简化用户的身份验证和授权.
- [Flask-Dance](https://github.com/singingwolfboy/flask-dance) - 通过 OAuth 支持 [OAuthLib](https://oauthlib.readthedocs.io/).

### Cache

- [Flask-Caching](https://flask-caching.readthedocs.io/) - 缓存支持.

### Data Validation and Serialization

- [Flask-Marshmallow](https://flask-marshmallow.readthedocs.io) - Flask 和 marshmallow（一个对象序列化/反序列化库）的薄集成层，为 marshmallow 添加了附加功能.
- [Flask-Pydantic](https://github.com/bauerji/flask-pydantic) - [Pydantic](https://github.com/samuelcolvin/pydantic) 支持.

### Databases

#### ORMs

- [Flask-Peewee](https://flask-peewee.readthedocs.io) - 支持 Peewee，一种 ORM 和数据库迁移工具.
- [Flask-Pony](https://pypi.org/project/Flask-Pony/) - 支持小马 ORM.
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com) - 支持 SQLAlchemy，一个 SQL 工具包和 ORM.

#### ODMs

- [Flask-MongoEngine](https://flask-mongoengine.readthedocs.io) - 连接 Flask 和 MongoEngine 以使用 MongoDB.
- [Flask-PyMongo](https://flask-pymongo.readthedocs.io) - 桥接 Flask 和 PyMongo 以使用 MongoDB.

#### Migrations

- [Flask-Alembic](https://flask-alembic.readthedocs.io) - 可配置 [Alembic](https://alembic.sqlalchemy.org/) 围绕 Flask-SQLAlchemy 数据库的迁移环境，用于处理数据库迁移.
<!--lint ignore double-link-->
- [Flask-DB](https://github.com/nickjj/flask-db) - Flask CLI 扩展，可帮助您迁移、删除、创建和播种 SQL 数据库.
- [Flask-Migrate](https://flask-migrate.readthedocs.io) - 通过 Alembic 处理 SQLAlchemy 数据库迁移.

<!--lint ignore double-link-->
 &gt; 对 Alembic、Flask-Alembic、Flask-Migrate 和 Flask-DB 之间的区别感到好奇吗？ 审查 [this item](https://github.com/nickjj/flask-db#differences-between-alembic-flask-migrate-flask-alembic-and-flask-db) 来自 Flask-DB 的常见问题解答.

#### Other Tools

- [Flask-Excel](https://github.com/pyexcel-webwares/Flask-Excel) - 用途 [pyexcel](https://github.com/pyexcel/pyexcel) 以不同的 Excel 格式读取、操作和写入数据：csv、ods、xls、xlsx 和 xlsm.

### Developer Tools

#### Debugging

- [Flask-DebugToolbar](https://flask-debugtoolbar.readthedocs.io) - Django 的 Flask 调试工具栏的端口.
- [Flask-Profiler](https://github.com/muatik/flask-profiler) - 端点分析器/分析器.

#### Fixtures

- [Flask-Fixtures](https://github.com/croach/Flask-Fixtures) - 从 JSON 或 YAML 创建数据库装置.
- [Mixer](https://mixer.readthedocs.io) - 对象生成工具.

#### Logging

- [Rollbar](https://rollbar.com/platforms/flask-error-tracking/) - 使用 Rollbar 记录烧瓶错误.

#### Monitoring

- [Airbrake](https://docs.airbrake.io/docs/platforms/flask/) - Airbrake Flask 集成.
- [Elastic APM Agent](https://www.elastic.co/guide/en/apm/agent/python/current/flask-support.html) - 弹性 APM Flask 集成.
- [Flask Monitoring Dashboard](https://flask-monitoringdashboard.readthedocs.io) - 用于自动监控 Flask Web 服务的仪表板.
- [Sentry Python SDK](https://sentry.io/for/flask/) - Sentry SDK Flask 集成.

#### Tracing

- [Flask-OpenTracing](https://github.com/opentracing-contrib/python-flask) - OpenTracing 仪器.

#### Testing

- [Flask-Testing](https://pythonhosted.org/Flask-Testing/) - 单元测试扩展.
- [Pytest-Flask](https://github.com/pytest-dev/pytest-flask) - Pytest 支持测试 Flask 应用程序.

### Email

- [Flask-Mail](https://pythonhosted.org/Flask-Mail/) - 提供简单的电子邮件发送功能.
- [Flask-Mailman](https://pypi.org/project/flask-mailman/) - Flask 的 `django.mail` 端口.

### Forms

- [Flask-WTF](https://flask-wtf.readthedocs.io) - 将 Flask 与 WTForms 集成（也提供 CSRF 保护）.

### Full-text Search


- [flask-msearch](https://github.com/honmaple/flask-msearch) - 全文搜索.
- [Flask-WhooshAlchemy3](https://github.com/blakev/Flask-WhooshAlchemy3) - Flask-SQLAlchemy 的全文搜索 + Whoosh 索引功能.
- [SQLAlchemy-Searchable](https://sqlalchemy-searchable.readthedocs.io) - 为 SQLAlchemy 模型提供全文搜索功能.

### Security

- [Flask-Bcrypt](https://flask-bcrypt.readthedocs.io) - 提供 bcrypt 散列实用程序.
- [Flask-CORS](https://flask-cors.readthedocs.io) - 跨域资源共享 (CORS) 处理.
- [Flask-SeaSurf](https://github.com/maxcountryman/flask-seasurf/) - 跨站点请求伪造 (CSRF) 预防.
- [Flask-Talisman](https://github.com/GoogleCloudPlatform/flask-talisman) - HTTPS 和安全标头.

### Task Queues

- [Celery](https://docs.celeryproject.org/) - 用于处理异步任务和调度的最常用的 Python 库.
- [Dramatiq](https://flask-dramatiq.rtfd.io/) - 芹菜的快速可靠替代品.
- [Flask-RQ](https://github.com/mattupstate/flask-rq) - [RQ](https://python-rq.org/) （Redis 队列）集成.
- [Huey](https://huey.readthedocs.io) - [Redis](https://redis.io/)- 基于任务队列，旨在为执行任务提供一个简单但灵活的框架.

### Utils

- [Flask-Babel](https://github.com/python-babel/flask-babel) - 支持国际化 (i18n) 和本地化 (l10n).
- [Flask-File-Upload](https://github.com/joegasewicz/flask-file-upload) - 轻松的文件上传.
- [Flask-FlatPages](https://pythonhosted.org/Flask-FlatPages/) - 提供基于文本文件的平面静态页面.
- [Frozen-Flask](https://github.com/Frozen-Flask/Frozen-Flask) - 将 Flask 应用程序冻结为一组静态文件.
- [Flask-GraphQL](https://github.com/graphql-python/flask-graphql) - GraphQL 支持.
- [Flask-Injector](https://github.com/alecthomas/flask_injector) - 添加对依赖注入的支持.
- [Flask-Limiter](https://flask-limiter.readthedocs.io) - Flask 路由的速率限制功能.
- [Flask-Moment](https://github.com/miguelgrinberg/Flask-Moment) - Moment.js date and time formatting helpers for Jinja2 templates.
- [Flask-Paginate](https://pythonhosted.org/Flask-paginate/) - 分页支持.
- [Flask-Reactize](https://github.com/jchomarat/flask-reactize) - 用 Flask 替换 React 的 Node.js 开发后端.
- [Flask-Shell2HTTP](https://github.com/Eshaan7/Flask-Shell2HTTP) - Python 子进程 API 的 RESTful/HTTP 包装器，因此您可以将任何命令行工具转换为 RESTful API 服务.
- [Flask-Sitemap](https://flask-sitemap.readthedocs.io) - 站点地图生成.
- [Flask-SocketIO](https://flask-socketio.readthedocs.io) - Socket.IO 集成.

## Resources

### Official Resources

- [Project Website](https://palletsprojects.com/p/flask/) - Flask 官方网站.
<!--lint ignore double-link-->
- [Documentation](https://flask.palletsprojects.com) - 所有 Flask 版本的综合文档.
- [Flaskr Tutorial](https://flask.palletsprojects.com/tutorial/) - 构建一个名为 Flaskr 的基本博客应用程序.
- [Source Code](https://github.com/pallets/flask) - 托管在 GitHub 上.

### External Resources

- [Full Stack Python's Flask Page](https://www.fullstackpython.com/flask.html) - Flask 理念的解释以及其他资源和教程的链接.
- [Miguel Grinberg's Blog](https://blog.miguelgrinberg.com/category/Flask) - 多个 Flask 特定教程.

- [Nick Janetakis's Blog](https://nickjanetakis.com/blog/tag/flask-tips-tricks-and-tutorials) - 烧瓶提示、技巧和教程.
- [Patrick Kennedy's Blog](http://www.patricksoftwareblog.com/flask-tutorial/) - 大量关于使用 Flask 学习 Python Web 应用程序开发的教程.
- [RealPython](https://realpython.com/tutorials/flask/) - 许多关于 Flask 的高质量教程.
- [TestDriven.io](https://testdriven.io/blog/topics/flask/) - 关于 Flask 的最新教程.

### Community

- [Discord](https://discord.com/invite/t6rrQZH) - Pallets Projects community on Discord (use the `#get-help` channel for Flask support).
- IRC Channel - Chat with other Flask users on IRC channel `#pocoo` on FreeNode.
- [Mailing List](https://mail.python.org/mailman/listinfo/flask) - Flask 和 Pallets 项目的一般讨论（`flask@python.org`）.
- [Reddit](https://www.reddit.com/r/flask/) - 烧瓶子版块.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/flask) - 标记为“烧瓶”的问题.
- [Twitter](https://twitter.com/PalletsTeam) - 有关更新、安全修复等的官方公告.

### Conferences

- [FlaskCon](https://flaskcon.com/) - 社区驱动的 Flask 活动，旨在让世界各地的演讲者和与会者参与与 Flask 相关的技术和福音派会议.
- [PyConWeb](https://twitter.com/pyconweb)  - 涵盖 Django、Tornado、Flask、API 框架.  AsyncIO、网络、前端、JavaScript 和网络安全.
- [Flask Conf Brazil](https://2019.flask.python.org.br/) - Flask 开发者和用户的会议.
- [PyCon US](https://us.pycon.org/) - 使用和开发开源 Python 编程语言的社区最大的年度聚会.
- [PyCon Australia](https://pycon-au.org/) - 为 Python 编程社区组织的全国会议.
- [Euro Python](https://europython.eu/) - 欧洲最大的 Python 会议.
- [PyCon](https://pycon.org/) - 全球所有 PyCons 的完整列表.

### Meetups

- [Flask](https://www.meetup.com/topics/flask/all/) - 20 个国家的 40 多个团体.
- [Python Web Development](https://www.meetup.com/topics/python-web-development/all/) - 81 个国家/地区的 600 多个团体.
- [Python](https://www.meetup.com/topics/python/all/) - 100 个国家/地区的 2,400 多个团体.

### Podcasts

- [TalkPython](https://talkpython.fm/) - 领先的 Python 播客，在 Flask 上有几集.
- [Podcast Init](https://www.pythonpodcast.com/) - 一个流行的 Python 播客，有时会邀请 Flask 来宾.
- [Python Bytes](https://pythonbytes.fm/) - 另一个不时讨论 Flask 的 Python 播客.
- [Full Stack Python's Best Python Podcasts Page](https://www.fullstackpython.com/best-python-podcasts.html) - 活跃的 Python 特定播客列表.

### Tutorials

- [Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world) - 面向 Python 初学者和中级开发人员的总体教程，教授使用 Flask 框架进行 Web 开发.
- [Flaskr TDD](https://github.com/mjhea0/flaskr-tdd) - Flask、测试驱动开发 (TDD) 和 JavaScript 简介.
- [Make a Web App Using Python & Flask!](https://aryaboudaie.com/python/technical/educational/web/flask/2018/10/17/flask.html) - 自下而上创建 Python 网站.

### Courses

- [Developing Web Applications with Python and Flask](https://testdriven.io/courses/learn-flask/) - 本课程侧重于通过使用测试驱动开发 (TDD) 构建和测试 Web 应用程序来教授 Flask 的基础知识.
- [Test-Driven Development with Python, Flask, and Docker](https://testdriven.io/courses/tdd-flask/) - 了解如何构建、测试和部署由 Python、Flask 和 Docker 提供支持的生产级微服务.
- [Authentication with Flask, React, and Docker](https://testdriven.io/courses/auth-flask-react/) - 了解如何向 Flask 和 React 微服务添加身份验证！.
- [Deploying a Flask and React Microservice to AWS ECS](https://testdriven.io/courses/aws-flask-react/) - 了解如何将微服务部署到由 Flask、React 和 Docker 提供支持的 Amazon ECS.
- [Build a SAAS App with Flask](https://buildasaasappwithflask.com) - 学习使用 Flask 和 Docker 构建 Web 应用程序.
- [Full Stack Foundations](https://www.udacity.com/course/full-stack-foundations--ud088) - 使用 Python 构建数据驱动的 Web 应用程序.
- [Designing RESTful APIs](https://www.udacity.com/course/designing-restful-apis--ud388) - 构建和保护后端 API 服务器.

### Books

- [Flask Web Development](https://www.oreilly.com/library/view/flask-web-development/9781491991725/) - 通过逐步开发真实世界的项目，从头开始学习框架.
- [Real Python](https://realpython.com) - 通过示例学习 Python 编程.
- [Explore Flask](https://exploreflask.com/) - 使用 Flask 开发 Web 应用程序的最佳实践和模式.

### Videos

- [PyVideo](https://pyvideo.org/search.html?q=flask)
- [Practical Flask Web Development Tutorials](https://www.youtube.com/playlist?list=PLQVvvaa0QuDc_owjTbIY4rbgXOFkUYOUB)
- [Python Flask Tutorial: Full-Featured Web App](https://www.youtube.com/playlist?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH)
- [Discover Flask - Full Stack Web Development with Flask](https://github.com/realpython/discover-flask)

## Hosting

### PaaS

(Platforms-as-a-Service)

- [Heroku](https://www.heroku.com/)
- [PythonAnywhere](https://www.pythonanywhere.com/details/flask_hosting)
- [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
- [Google App Engine](https://cloud.google.com/appengine/)
- [Microsoft Azure App Service](https://azure.microsoft.com/en-us/services/app-service/)
- [Divio](https://www.divio.com)
- [Render](https://render.com/)

### IaaS

(Infrastructure-as-a-Service)

- [AWS EC2](https://aws.amazon.com/ec2/)
- [Google Compute Engine](https://cloud.google.com/compute/)
- [Digital Ocean](https://www.digitalocean.com/)
<!-- markdown-link-check-disable-next-line -->
- [Linode](https://www.linode.com/)

### Serverless

Frameworks:

- [Zappa](https://github.com/Miserlou/Zappa)
- [Chalice](https://github.com/aws/chalice)

Compute:

- [AWS Lambda](https://aws.amazon.com/lambda/)
- [Google Cloud Functions](https://cloud.google.com/functions/)
- [Azure Functions](https://azure.microsoft.com/en-us/services/functions/)

## Projects

### Boilerplates

- [cookiecutter-flask](https://github.com/cookiecutter-flask/cookiecutter-flask) - 使用 Bootstrap 4，使用 webpack、starter 模板和注册/身份验证进行资产捆绑和缩小.
- [Cookiecutter Flask Skeleton](https://github.com/testdrivenio/cookiecutter-flask-skeleton) - 烧瓶启动项目 [Cookiecutter](https://github.com/cookiecutter/cookiecutter).
- [Flask-AppBuilder](https://github.com/dpgaspar/Flask-AppBuilder) - 简单快速的应用程序开发框架，包括详细的安全性、模型的自动 CRUD 生成、Google 图表等等.
- [flask-base](http://hack4impact.github.io/flask-base/) - 包括 SQLAlchemy、Redis、用户身份验证等.
- [Flask-Bootstrap](https://github.com/esbullington/flask-bootstrap) - 集成 SQLAlchemy、身份验证和 Bootstrap 前端.
- [uwsgi-nginx-flask-docker](https://github.com/tiangolo/uwsgi-nginx-flask-docker) - 带有 uWSGI 和 Nginx 的 Docker 映像，用于在单个容器中运行的 Python 中的 Flask 应用程序.
- [React-Redux-Flask](https://github.com/dternyak/React-Redux-Flask) - Flask JWT 后端和带有 Material UI 的 React/Redux 前端的样板应用程序.
- [Flask-Scaffold](https://github.com/Leo-G/Flask-Scaffold) - 在 Angular 6、Bootstrap 4 和带有 Flask 的 REST API 中原型数据库驱动的 Web 应用程序.
- [Flask-VueJS](https://github.com/marcuxyz/flask-vuejs) - 将 Flask 应用程序与 VueJS 连接.

### Open Source Projects

- [ActorCloud](https://github.com/actorcloud/ActorCloud) - 开源物联网平台.
- [Airflow](https://github.com/apache/airflow/tree/master/airflow/www)
- [Busy Beaver](https://github.com/busy-beaver-dev/busy-beaver) - Chicago Python 的社区参与 Slack 机器人.
- [FlaskBB](https://github.com/flaskbb/flaskbb) - 经典的论坛软件.
- [Indico](https://github.com/indico/indico) - 功能丰富的事件管理系统，在 [CERN](https://home.cern/).
- [Quokka CMS](https://github.com/quokkaproject) - 世界上最快乐的 CMS.
- [PythonBuddy](https://github.com/ethanchewy/PythonBuddy) - 具有实时语法检查和执行功能的在线 Python 编辑器.
- [Redash](https://github.com/getredash/redash) - 旨在使任何人，无论技术复杂程度如何，都能利用大大小小的数据的力量.
- [SkyLines](https://github.com/skylines-project/skylines) - 实时跟踪、航班数据库和竞赛框架.
- [Security Monkey](https://github.com/Netflix/security_monkey) - 监控 AWS、GCP、OpenStack 和 GitHub 组织的资产及其随时间的变化.
- [SecureDrop](https://github.com/freedomofpress/securedrop) - 开源举报人提交系统，媒体组织可以使用它来安全地接受来自匿名来源的文件，并与匿名来源进行交流.
- [SimpleLogin](https://github.com/simple-login/app) - 使用电子邮件别名保护您的在线身份.
- [sr.ht](https://git.sr.ht/~sircmpwn/core.sr.ht/tree) - Git 托管服务（查看 [Why I chose Flask to build sr.ht's mini-services](https://drewdevault.com/2019/01/30/Why-I-built-sr.ht-with-Flask.html) 以及）.
- [Timesketch](https://github.com/google/timesketch) - 协作取证时间线分析.

---

<br>

&gt; **注意**：此项目由**提供支持[TestDriven.io](https://testdriven.io/) **. 请购买我们的一门 Flask 课程来支持这个开源项目. 了解如何构建、测试和部署由 Docker、Flask 和 React 提供支持的微服务！
