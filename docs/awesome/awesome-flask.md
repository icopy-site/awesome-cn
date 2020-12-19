<div class="github-widget" data-repo="mjhea0/awesome-flask"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Flask [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

&gt;与Flask相关的精选精彩清单.

<!--lint ignore double-link-->
[Flask](https://flask.palletsprojects.com/) 是用Python编写的轻量级WSGI Web应用程序框架.



## Third-Party Extensions

### Admin

- [Flask-Admin](https://github.com/flask-admin/flask-admin) -功能性管理面板，提供用于基于模型管理数据的用户界面.

### APIs

#### RESTful API Support

- [Eve](https://docs.python-eve.org) -专为人类设计的RESTful API框架.
- [Flask-Classful](https://flask-classful.teracy.org/) -增加了对基于类的视图的支持，以设置RESTful API路由端点.
- [Flask-MongoRest](https://github.com/closeio/flask-mongorest) -环绕的RESTful API框架 [MongoEngine](http://mongoengine.org/).
- [Flask-RESTful](https://flask-restful.readthedocs.io) -快速构建RESTful API.

#### RESTful API + Swagger/OpenAPI Documentation Support

- [Connexion](https://connexion.readthedocs.io) -基于Flask构建的基于OpenAPI的开源REST框架.
- [Flask-Rebar](https://github.com/plangrid/flask-rebar) -结合烧瓶 [marshmallow](https://marshmallow.readthedocs.io/)和 [OpenAPI](https://www.openapis.org/) 用于强大的REST服务.
- [Flask-RESTX](https://flask-restx.readthedocs.io) -社区驱动 [Flask-RESTPlus](https://flask-restplus.readthedocs.io/) 使用Flask可以轻松构建和记录RESTful API.

#### Swagger/OpenAPI Documentation Support

- [Flask-APISpec](https://flask-apispec.readthedocs.io/) -自动记录REST API.
- [SAFRS: Python OpenAPI & JSON:API Framework](https://github.com/thomaxxl/safrs) -SAFRS是* S * ql * A * lchemy * F * lask- * R * est * * S * wagger的首字母缩写，旨在帮助开发人员为SQLAlchemy数据库对象和关系创建自文档化JSON API.

### Auth

#### Basic Auth and Session-based (for HTML Endpoints)

- [Flask-HTTPAuth](https://flask-httpauth.readthedocs.io) -身份验证.
- [Flask-Login](https://flask-login.readthedocs.io/) -帐户管理和身份验证.
- [Flask Principal](https://pythonhosted.org/Flask-Principal/) -授权.
- [Flask-Security-Too](https://flask-security-too.readthedocs.io/en/stable/) -帐户管理，身份验证，授权.
- [Flask-SimpleLogin](https://github.com/flask-extensions/flask_simplelogin) -身份验证.
- [Flask-User](https://flask-user.readthedocs.io) -帐户管理，身份验证，授权.

 &gt;对Flask-User和Flask-Security之间的差异感到好奇吗？ 查看烧瓶用户 [FAQ](https://flask-user.readthedocs.io/en/latest/faq.html).

#### JWT-based (for JSON Endpoints)

- [Flask-JWT](https://pythonhosted.org/Flask-JWT/) -与JWT合作的基本支持.
- [Flask-JWT-Extended](https://flask-jwt-extended.readthedocs.io) -与JWT合作的高级支持.
- [Flask-JWT-Router](https://github.com/joegasewicz/flask-jwt-router) -将授权路线添加到Flask应用.
- [Flask-Praetorian](https://flask-praetorian.readthedocs.io) -Flask API的身份验证和授权.

#### OAuth

- [Authlib](https://authlib.org/) -用于构建OAuth和OpenID客户端和服务器的库.
- [Authomatic](https://github.com/authomatic/authomatic) -Python Web应用程序的框架不可知库，可通过OAuth和OpenID简化用户的身份验证和授权.
- [Flask-Dance](https://github.com/singingwolfboy/flask-dance) -通过OAuth支持 [OAuthLib](https://oauthlib.readthedocs.io/).

### Cache

- [Flask-Caching](https://flask-caching.readthedocs.io/) -缓存支持.

### Data Validation and Serialization

- [Flask-Marshmallow](https://flask-marshmallow.readthedocs.io) -Flask和棉花糖的薄集成层（对象序列化/反序列化库），为棉花糖添加了其他功能.
- [Flask-Pydantic](https://github.com/bauerji/flask_pydantic) - [Pydantic](https://github.com/samuelcolvin/pydantic) 支持.

### Databases

#### ORMs

- [Flask-Peewee](https://flask-peewee.readthedocs.io) -支持Peewee，一种ORM和数据库迁移工具.
- [Flask-Pony](https://pypi.org/project/Flask-Pony/) -支持Pony ORM.
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com) -支持SQLAlchemy，SQL工具包和ORM.

#### ODMs

- [Flask-MongoEngine](https://flask-mongoengine.readthedocs.io) -桥接Flask和MongoEngine以与MongoDB一起使用.
- [Flask-PyMongo](https://flask-pymongo.readthedocs.io) -Bridges Flask和PyMongo与MongoDB一起工作.

#### Migrations

- [Flask-Alembic](https://flask-alembic.readthedocs.io) -可配置 [Alembic](https://alembic.sqlalchemy.org/) Flask-SQLAlchemy数据库周围的迁移环境，用于处理数据库迁移.
<!--lint ignore double-link-->
- [Flask-DB](https://github.com/nickjj/flask-db) -Flask CLI扩展，可帮助您迁移，删除，创建和播种SQL数据库.
- [Flask-Migrate](https://flask-migrate.readthedocs.io) -通过Alembic处理SQLAlchemy数据库迁移.

<!--lint ignore double-link-->
 &gt;对Alembic，Flask-Alembic，Flask-Migrate和Flask-DB之间的差异感到好奇吗？ 评论 [this item](https://github.com/nickjj/flask-db#differences-between-alembic-flask-migrate-flask-alembic-and-flask-db) 从Flask-DB的常见问题解答中获取.

#### Other Tools

- [Flask-Excel](https://github.com/pyexcel-webwares/Flask-Excel) -用途 [pyexcel](https://github.com/pyexcel/pyexcel) 以不同的Excel格式读取，操作和写入数据：csv，ods，xls，xlsx和xlsm.

### Developer Tools

#### Debugging

- [Flask-DebugToolbar](https://flask-debugtoolbar.readthedocs.io) -Flask的Django调试工具栏的端口.
- [Flask-Profiler](https://github.com/muatik/flask-profiler) -端点分析器/分析器.

#### Fixtures

- [Flask-Fixtures](https://github.com/croach/Flask-Fixtures) -从JSON或YAML创建数据库装置.
- [Mixer](https://mixer.readthedocs.io) -对象生成工具.

#### Logging

- [Rollbar](https://rollbar.com/error-tracking/flask/) -使用Rollbar记录烧瓶错误.

#### Monitoring

- [Airbrake](https://airbrake.io/docs/installing-airbrake/installing-airbrake-in-a-flask-app/) -Airbrake Flask集成.
- [Elastic APM Agent](https://www.elastic.co/guide/en/apm/agent/python/current/flask-support.html) -弹性APM Flask集成.
- [Flask Monitoring Dashboard](https://flask-monitoringdashboard.readthedocs.io) -用于自动监视Flask Web服务的仪表板.
- [Sentry Python SDK](https://sentry.io/for/flask/) -Sentry SDK Flask集成.

#### Tracing

- [Flask-OpenTracing](https://github.com/opentracing-contrib/python-flask) -OpenTracing工具.

#### Testing

- [Flask-Testing](https://pythonhosted.org/Flask-Testing/) -单元测试扩展.
- [Pytest-Flask](https://github.com/pytest-dev/pytest-flask) -Pytest支持，用于测试Flask应用程序.

### Email

- [Flask-Mail](https://pythonhosted.org/Flask-Mail/) -提供简单的电子邮件发送功能.

### Forms

- [Flask-WTF](https://flask-wtf.readthedocs.io) -将Flask与WTForms集成（还提供CSRF保护）.

### Full-text Search


- [flask-msearch](https://github.com/honmaple/flask-msearch) -全文搜索.
- [Flask-WhooshAlchemy3](https://github.com/blakev/Flask-WhooshAlchemy3) -全文搜索+ Flask-SQLAlchemy的Whoosh索引功能.
- [SQLAlchemy-Searchable](https://sqlalchemy-searchable.readthedocs.io) -提供SQLAlchemy模型的全文本搜索功能.

### Security

- [Flask-Bcrypt](https://flask-bcrypt.readthedocs.io) -提供bcrypt哈希实用程序.
- [Flask-CORS](https://flask-cors.readthedocs.io) -跨源资源共享（CORS）处理.
- [Flask-SeaSurf](https://github.com/maxcountryman/flask-seasurf/) -防止跨站请求伪造（CSRF）.
- [Flask-Talisman](https://github.com/GoogleCloudPlatform/flask-talisman) -HTTPS和安全标头.

### Task Queues

- [Celery](https://docs.celeryproject.org/) -最常用的Python库，用于处理异步任务和调度.
- [Dramatiq](https://flask-dramatiq.rtfd.io/) -快速可靠的替代芹菜.
- [Flask-RQ](https://github.com/mattupstate/flask-rq) - [RQ](https://python-rq.org/) （Redis Queue）集成.
- [Huey](https://huey.readthedocs.io) - [Redis](https://redis.io/)基于任务的队列，旨在为执行任务提供一个简单而灵活的框架.

### Utils

- [Flask-Babel](https://github.com/python-babel/flask-babel) -支持国际化（i18n）和本地化（l10n）.
- [Flask-File-Upload](https://github.com/joegasewicz/flask-file-upload) -轻松上传文件.
- [Flask-FlatPages](https://pythonhosted.org/Flask-FlatPages/) -提供基于文本文件的平面静态页面.
- [Frozen-Flask](https://github.com/Frozen-Flask/Frozen-Flask) -将Flask应用程序冻结为一组静态文件.
- [Flask-GraphQL](https://github.com/graphql-python/flask-graphql) -GraphQL支持.
- [Flask-Injector](https://github.com/alecthomas/flask_injector) -增加了对依赖注入的支持.
- [Flask-Limiter](https://flask-limiter.readthedocs.io) -Flask路由的速率限制功能.
- [Flask-Moment](https://github.com/miguelgrinberg/Flask-Moment) -用于Jinja2模板的Moment.js日期和时间格式帮助器.
- [Flask-Paginate](https://pythonhosted.org/Flask-paginate/) -分页支持.
- [Flask-Sitemap](https://flask-sitemap.readthedocs.io) -生成站点地图.
- [Flask-SocketIO](https://flask-socketio.readthedocs.io) -Socket.IO集成.

## Resources

### Official Resources

- [Project Website](https://palletsprojects.com/p/flask/) -Flask官方网站.
<!--lint ignore double-link-->
- [Documentation](https://flask.palletsprojects.com) -有关所有Flask版本的综合文档.
- [Flaskr Tutorial](https://flask.palletsprojects.com/tutorial/) -构建一个名为Flaskr的基本博客应用程序.
- [Source Code](https://github.com/pallets/flask) -托管在GitHub上.

### External Resources

- [Full Stack Python's Flask Page](https://www.fullstackpython.com/flask.html) -说明Flask原理，并链接到其他资源和教程.
- [Miguel Grinberg's Blog](https://blog.miguelgrinberg.com/category/Flask) -多个Flask特定的教程.

- [Nick Janetakis's Blog](https://nickjanetakis.com/blog/tag/flask-tips-tricks-and-tutorials) -烧瓶技巧，窍门和教程.
- [Patrick Kennedy's Blog](http://www.patricksoftwareblog.com/flask-tutorial/) -有关使用Flask学习Python Web应用程序开发的大量教程.
- [RealPython](https://realpython.com/tutorials/flask/) -Flask上的许多高质量教程.
- [TestDriven.io](https://testdriven.io/blog/topics/flask/) -Flask上的最新教程.

### Community

- [Discord](https://discord.com/invite/t6rrQZH) - Pallets Projects community on Discord (use the `#get-help` channel for Flask support).
- [Flask Jobs](https://flaskjobs.com) -致力于Flask的工作委员会.
- IRC Channel - Chat with other Flask users on IRC channel `#pocoo` on FreeNode.
- [Mailing List](https://mail.python.org/mailman/listinfo/flask) -Flask和Pallets项目的一般讨论（flask @ python.org`）.
- [Reddit](https://www.reddit.com/r/flask/) -Flask subreddit.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/flask) -标有“ flask”的问题.
- [Twitter](https://twitter.com/PalletsTeam) -有关更新，安全修补程序等的官方公告.

### Conferences

- [FlaskCon](https://flaskcon.com/) -由社区推动的Flask活动，旨在让世界各地的演讲者和参与者参加与Flask相关的技术和福音派会议.
- [PyConWeb](https://pyconweb.com/)  -涵盖Django，Tornado，Flask，API框架.  AsyncIO，网络，前端，JavaScript和Web安全.
- [Flask Conf Brazil](https://2019.flask.python.org.br/) -Flask开发人员和用户大会.
- [PyCon US](https://us.pycon.org/) -使用和开发开放源代码Python编程语言的社区最大的年度聚会.
- [PyCon Australia](https://pycon-au.org/) -为Python编程社区组织的全国性会议.
- [Euro Python](https://europython.eu/) -欧洲最大的Python会议.
- [PyCon](https://pycon.org/) -在全球范围内完整列出所有PyCon.

### Meetups

- [Flask](https://www.meetup.com/topics/flask/all/) -20个国家/地区的40多个团体.
- [Python Web Development](https://www.meetup.com/topics/python-web-development/all/) -81个国家/地区的600多个团体.
- [Python](https://www.meetup.com/topics/python/all/) -100个国家/地区的2,400多个团体.

### Podcasts

- [TalkPython](https://talkpython.fm/) -领先的Python播客，包含Flask上的几集内容.
- [Podcast Init](https://www.pythonpodcast.com/) -流行的Python播客，有时会邀请Flask来宾参加.
- [Python Bytes](https://pythonbytes.fm/) -另一个不时讨论Flask的Python播客.
- [Full Stack Python's Best Python Podcasts Page](https://www.fullstackpython.com/best-python-podcasts.html) -活动的特定于Python的播客列表.

### Tutorials

- [Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world) -适用于Python初学者和中级开发人员的总体教程，该课程教授使用Flask框架进行Web开发.
- [Flaskr TDD](https://github.com/mjhea0/flaskr-tdd) -Flask，测试驱动开发（TDD）和JavaScript简介.
- [Make a Web App Using Python & Flask!](https://aryaboudaie.com/python/technical/educational/web/flask/2018/10/17/flask.html) -从头开始创建Python网站.

### Courses

- [Developing Web Applications with Python and Flask](https://testdriven.io/courses/learn-flask/) -本课程着重于通过使用测试驱动开发（TDD）构建和测试Web应用程序来教授Flask的基础知识.
- [Test-Driven Development with Python, Flask, and Docker](https://testdriven.io/courses/tdd-flask/) -了解如何构建，测试和部署由Python，Flask和Docker支持的生产级微服务.
- [Authentication with Flask, React, and Docker](https://testdriven.io/courses/auth-flask-react/) -了解如何向Flask and React微服务添加身份验证！
- [Deploying a Flask and React Microservice to AWS ECS](https://testdriven.io/courses/aws-flask-react/) -了解如何将微服务部署到由Flask，React和Docker支持的Amazon ECS.
- [Build a SAAS App with Flask](https://buildasaasappwithflask.com) -学习使用Flask和Docker构建Web应用程序.
- [Full Stack Foundations](https://www.udacity.com/course/full-stack-foundations--ud088) -使用Python构建数据驱动的网络应用.
- [Designing RESTful APIs](https://www.udacity.com/course/designing-restful-apis--ud388) -构建并保护后端API服务器.

### Books

- [Flask Web Development](https://www.oreilly.com/library/view/flask-web-development/9781491991725/) -通过逐步开发一个实际项目，从头开始学习框架.
- [Real Python](https://realpython.com) -通过示例学习Python编程.
- [Explore Flask](https://exploreflask.com/) -使用Flask开发Web应用程序的最佳做法和模式.

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
- [Microsoft Azure App Service](https://azure.microsoft.com/services/app-service/)
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

- [cookiecutter-flask](https://github.com/cookiecutter-flask/cookiecutter-flask) -使用Bootstrap 4，通过Webpack，入门模板和注册/身份验证进行资产捆绑和最小化.
- [Cookiecutter Flask Skeleton](https://github.com/testdrivenio/cookiecutter-flask-skeleton) -的烧瓶启动器项目 [Cookiecutter](https://github.com/cookiecutter/cookiecutter).
- [gae-init](https://gae-init.appspot.com) -用于在Google App Engine上启动新应用程序.
- [Flask-AppBuilder](https://github.com/dpgaspar/Flask-AppBuilder) -简单，快速的应用程序开发框架，其中包括详细的安全性，为模型自动生成CRUD，Google图表等等.
- [flask-base](http://hack4impact.github.io/flask-base/) -包括SQLAlchemy，Redis，用户身份验证等.
- [Flask-Bootstrap](https://github.com/esbullington/flask-bootstrap) -集成的SQLAlchemy，身份验证和Bootstrap前端.
- [uwsgi-nginx-flask-docker](https://github.com/tiangolo/uwsgi-nginx-flask-docker) -带有uWSGI和Nginx的Docker映像，用于在单个容器中运行的Python中的Flask应用程序.
- [React-Redux-Flask](https://github.com/dternyak/React-Redux-Flask) -Flask JWT后端和带有Material UI的React / Redux前端的样板应用程序.
- [Flask-Scaffold](https://github.com/Leo-G/Flask-Scaffold) -带有Flask的Angular 6，Bootstrap 4和REST API中的原型数据库驱动的Web应用程序.
- [Flask-VueJS](https://github.com/marcuxyz/flask-vuejs) -将Flask应用程序与VueJS连接.

### Open Source Projects

- [ActorCloud](https://github.com/actorcloud/ActorCloud) -开源物联网平台.
- [Airflow](https://github.com/apache/airflow/tree/master/airflow/www)
- [Busy Beaver](https://github.com/busy-beaver-dev/busy-beaver) -Chicago Python的社区参与松弛机器人.
- [FlaskBB](https://github.com/flaskbb/flaskbb) -经典论坛软件.
- [Indico](https://github.com/indico/indico) -功能丰富的事件管理系统，在 [CERN](https://home.cern/).
- [Quokka CMS](https://github.com/quokkaproject) -世界上最幸福的CMS.
- [PythonBuddy](https://github.com/ethanchewy/PythonBuddy) -具有实时语法检查和执行功能的在线Python编辑器.
- [Redash](https://github.com/getredash/redash) -旨在使任何人，无论技术水平如何，都能利用大小数据的力量.
- [SkyLines](https://github.com/skylines-project/skylines) -实时跟踪，航班数据库和比赛框架.
- [Security Monkey](https://github.com/Netflix/security_monkey) -监视AWS，GCP，OpenStack和GitHub组织的资产及其随时间的变化.
- [SecureDrop](https://github.com/freedomofpress/securedrop) -开源举报人提交系统，媒体组织可以使用该系统安全地接受匿名来源的文档并与之进行通信.
- [SimpleLogin](https://github.com/simple-login/app) -使用电子邮件别名保护您的在线身份.
- [sr.ht](https://git.sr.ht/~sircmpwn/core.sr.ht/tree) -Git托管服务（签出 [Why I chose Flask to build sr.ht's mini-services](https://drewdevault.com/2019/01/30/Why-I-built-sr.ht-with-Flask.html) as well).
- [Timesketch](https://github.com/google/timesketch) -协作取证时间表分析.

---

<br>

&gt; **注意**：该项目由**提供支持[TestDriven.io](https://testdriven.io/) **. 请通过购买我们的Flask课程之一来支持此开源项目. 了解如何构建，测试和部署由Docker，Flask和React支持的微服务！
