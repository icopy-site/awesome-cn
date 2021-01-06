<div class="github-widget" data-repo="mjhea0/awesome-fastapi"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint disable double-link-->

## Awesome FastAPI [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

&gt;与FastAPI相关的精选事物的精选列表.

[FastAPI](https://fastapi.tiangolo.com/) 是一个现代的，高性能的，包含电池的Python Web框架，非常适合构建RESTful API.



## Third-Party Extensions

### Admin

- [FastAPI Admin](https://github.com/long2ice/fastapi-admin) -功能管理面板，提供用于对数据执行CRUD操作的用户界面.

### Auth

- [FastAPI Auth](https://github.com/dmontagu/fastapi-auth) -可插拔身份验证，支持带有JWT访问和刷新令牌的OAuth2密码流.
- [FastAPI Login](https://github.com/MushroomMaula/fastapi_login) -帐户管理和身份验证（基于 [Flask-Login](https://github.com/maxcountryman/flask-login)).
- [FastAPI JWT Auth](https://github.com/IndominusByte/fastapi-jwt-auth) -JWT身份验证（基于 [Flask-JWT-Extended](https://github.com/vimalloc/flask-jwt-extended)).
- [FastAPI Permissions](https://github.com/holgi/fastapi-permissions) -行级权限.
- [FastAPI Security](https://github.com/jmagnusson/fastapi-security) -将身份验证和授权实现为FastAPI中的依赖项.
- [FastAPI Simple Security](https://github.com/mrtolkien/fastapi_simple_security) -开箱即用的API密钥安全性可通过路径操作进行管理.
- [FastAPI Users](https://github.com/frankie567/fastapi-users) -帐户管理，身份验证，授权.

### Databases

#### ORMs

- [FastAPI SQLAlchemy](https://github.com/mfreeborn/fastapi-sqlalchemy) -FastAPI与 [SQLAlchemy](https://www.sqlalchemy.org/).
- [Tortoise ORM](https://tortoise-orm.readthedocs.io/en/latest/index.html) -受Django启发的易于使用的异步ORM（对象关系映射器）.
  - [FastAPI Example](https://tortoise-orm.readthedocs.io/en/latest/examples/fastapi.html) -Tortoise-ORM FastAPI集成的示例.
  - [Tutorial: Setting up Tortoise ORM with FastAPI](https://web.archive.org/web/20200523174158/https://robwagner.dev/tortoise-fastapi-setup/)
  - [Aerich](https://tortoise-orm.readthedocs.io/en/latest/migration.html) -乌龟ORM迁移工具.
- [GINO](https://github.com/python-gino/gino) -在SQLAlchemy核心之上为Python asyncio构建的轻量级异步ORM.
  - [FastAPI Example](https://github.com/leosussan/fastapi-gino-arq-uvicorn)
- [ORM](https://github.com/encode/orm) -异步ORM.
- [ormar](https://collerek.github.io/ormar/fastapi/) -适用于Python的异步迷你ORM.


#### Query Builders

- [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) -包装纸 [asyncpg](https://github.com/MagicStack/asyncpg) 用于 [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/).
- [Databases](https://github.com/encode/databases) -可以在 [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/) 表达语言.

#### ODMs

- [MongoEngine](http://mongoengine.org/) -一个文档对象映射器（认为是ORM，但适用于文档数据库），用于从Python使用MongoDB.
- [Motor](https://motor.readthedocs.io/) -MongoDB的异步Python驱动程序.
- [ODMantic](https://art049.github.io/odmantic/) -与AsyncIO MongoDB ODM集成 [Pydantic](https://pydantic-docs.helpmanual.io/). 

#### Other Tools

- [Pydantic-SQLAlchemy](https://github.com/tiangolo/pydantic-sqlalchemy) -将SQLAlchemy模型转换为 [Pydantic](https://pydantic-docs.helpmanual.io/) 楷模.
- [FastAPI-CamelCase](https://ahmednafies.github.io/fastapi_camelcase/) -利用FastAPI的CamelCase JSON支持 [Pydantic](https://pydantic-docs.helpmanual.io/).
  - [CamelCase Models with FastAPI and Pydantic](https://medium.com/analytics-vidhya/camel-case-models-with-fast-api-and-pydantic-5a8acb6c0eee) -扩展作者的随附博客文章.

### Developer Tools

- [FastAPI Client Generator](https://github.com/dmontagu/fastapi_client) -根据OpenAPI规范生成mypy和IDE友好的API客户端.
- [FastAPI Versioning](https://github.com/DeanWay/fastapi-versioning) -API版本控制.
- [Jupyter Notebook REST API](https://github.com/Invictify/Jupter-Notebook-REST-API) -将Jupyter笔记本作为RESTful API端点运行.
- [Manage FastAPI](https://github.com/ycd/manage-fastapi) -用于生成和管理FastAPI项目的CLI工具.
- [msgpack-asgi](https://github.com/florimondmanca/msgpack-asgi) -自动 [MessagePack](https://msgpack.org/) 内容协商.

### Email

- [FastAPI Mail](https://github.com/sabuhish/fastapi-mail) -用于发送电子邮件和附件（个人和批量）的轻型邮件系统.

### Utils

- [FastAPI Cache](https://github.com/comeuplater/fastapi_cache) -一个简单的轻量级缓存系统.
- [FastAPI Contrib](https://github.com/identixone/fastapi_contrib) -一套实用的实用程序：分页，身份验证中间件，权限，自定义异常处理程序，MongoDB支持和Opentracing中间件.
- [FastAPI CRUDRouter](https://github.com/awtkns/fastapi-crudrouter) -FastAPI路由器，可以为您的模型自动创建并记录CRUD路由.
- [FastAPI Plugins](https://github.com/madkote/fastapi-plugins) -Redis和Scheduler插件.
- [FastAPI ServiceUtils](https://github.com/skallfass/fastapi_serviceutils) -用于创建API服务的生成器.
- [FastAPI SocketIO](https://github.com/pyropy/fastapi-socketio) -轻松集成FastAPI和SocketIO.
- [FastAPI Utilities](https://github.com/dmontagu/fastapi-utils) -可重用的实用程序：基于类的视图，推理路由器，周期性任务，定时中间件，SQLAlchemy会话，OpenAPI规范简化.
- [Prerender Python Starlette](https://github.com/BeeMyDesk/prerender-python-starlette) -用于Prerender的Starlette中间件.
- [Prometheus FastAPI Instrumentator](https://github.com/trallnag/prometheus-fastapi-instrumentator) -适用于FastAPI应用程序的可配置模块化Prometheus Instrumentator.
- [SlowApi](https://github.com/laurents/slowapi) -速率限制器（基于 [Flask-Limiter](https://flask-limiter.readthedocs.io)).
- [Starlette Prometheus](https://github.com/perdy/starlette-prometheus) -用于FastAPI和Starlette的Prometheus集成.
- [Starlette Exporter](https://github.com/stephenhillier/starlette_exporter) -FastAPI和Starlette的另一种Prometheus集成.
- [Starlette-OpenTracing](https://github.com/acidjunk/starlette-opentracing) -对Starlette和FastAPI的Opentracing支持.

## Resources

### Official Resources

- [Documentation](https://fastapi.tiangolo.com/) -全面的文档.
- [Tutorial](https://fastapi.tiangolo.com/tutorial/) -正式教程，逐步向您展示如何使用FastAPI及其大部分功能.
- [Source Code](https://github.com/tiangolo/fastapi) -托管在GitHub上.
- [Gitter Chat](https://gitter.im/tiangolo/fastapi) -与其他FastAPI用户聊天.

### Podcasts

- [Build The Next Generation Of Python Web Applications With FastAPI](https://www.pythonpodcast.com/fastapi-web-application-framework-episode-259/) -在这集 [Podcast Init](https://www.pythonpodcast.com/)，创建FastAPI， [Sebastián Ramirez](https://tiangolo.com/)，分享了他构建FastAPI的动机以及它在幕后的工作方式.
- [FastAPI on PythonBytes](https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855) -该项目的概述.

### Articles

- [FastAPI has Ruined Flask Forever for Me](https://towardsdatascience.com/fastapi-has-ruined-flask-forever-for-me-73916127da)
- [Why we switched from Flask to FastAPI for production machine learning](https://towardsdatascience.com/why-we-switched-from-flask-to-fastapi-for-production-machine-learning-765aab9b3679) -深入了解为什么您可能希望从Flask转到FastAPI.

### Tutorials

- [Demystifying Authentication with FastAPI and a Frontend](https://kernelpanic.io/demystifying-authentication-with-fastapi-and-a-frontend/) -添加基于令牌的身份验证.
- [Deploy Machine Learning Models with Keras, FastAPI, Redis and Docker](https://medium.com/analytics-vidhya/deploy-machine-learning-models-with-keras-fastapi-redis-and-docker-4940df614ece)
- [Deploying Iris Classifications with FastAPI and Docker](https://towardsdatascience.com/deploying-iris-classifications-with-fastapi-and-docker-7c9b83fdec3a) -Docker化FastAPI应用程序.
- [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) -使用Test-Driven Development使用FastAPI，Postgres，Pytest和Docker开发和测试异步API.
- [FastAPI for Flask Users](https://amitness.com/2020/06/fastapi-vs-flask/) -通过与Flask的并行代码比较来学习FastAPI.
- [FastAPI Microservice Patterns](https://florian-kromer.medium.com/fastapi-microservice-patterns-3052c1241019) -具有微服务模式的示例性实现的博客文章系列.
  - [Local Development Environment](https://florian-kromer.medium.com/fastapi-microservice-patterns-local-development-environment-12182e786f1c) -简而言之，Skaffold，docker，kubectl和minikube.
  - [Service discovery in Container Orchestration Platforms](https://florian-kromer.medium.com/fastapi-microservice-patterns-service-discovery-in-container-orchestration-platforms-290c00d1ad8) -说明了如何在Kubernetes中启用FastAPI服务通信.
  - [Asynchronous Communication](https://florian-kromer.medium.com/fastapi-microservice-patterns-asynchronous-communication-45a3b68f8bb8) -通过消息启用松散耦合的服务.
  - [Application monitoring](https://florian-kromer.medium.com/fastapi-microservice-patterns-application-monitoring-49fcb7341d9a) -使用Prometheus和Grafana进行应用程序指标监视.
  - [Serverless deployment](https://florian-kromer.medium.com/fastapi-microservice-serverless-deployment-41a6d21e5cb3) -关于FastAPI和Kubernetes原生FaaS平台之间的兼容性的当前状态.
- [How to deploy your ConvNet classifier with Keras and FastAPI](https://www.machinecurve.com/index.php/2020/03/19/tutorial-how-to-deploy-your-convnet-classifier-with-keras-and-fastapi/) -通过基于Web的API部署机器学习模型.
- [How to monitor your FastAPI service](https://guitton.co/posts/fastapi-monitoring/) -说明如何使用OpenTelemetry和Datadog / Jaeger实施应用程序性能监视（APM）.
- [Introducing FARM Stack - FastAPI, React, and MongoDB](https://developer.mongodb.com/how-to/FARM-Stack-FastAPI-React-MongoDB/) -完整的FastAPI Web应用程序堆栈入门.
- [Introduction to the FastAPI Python Framework](https://www.errietta.me/blog/python-fastapi-intro/) -快速介绍FastAPI.
- [Porting Flask to FastAPI for ML Model Serving](https://www.pluralsight.com/tech-blog/porting-flask-to-fastapi-for-ml-model-serving/) -Flask与FastAPI的比较.
- [Real-time data streaming using FastAPI and WebSockets](https://stribny.name/blog/2020/07/real-time-data-streaming-using-fastapi-and-websockets/) -了解如何将数据从FastAPI直接流式传输到实时图表中.
- [Serving Machine Learning Models with FastAPI in Python](https://medium.com/@8B_EC/tutorial-serving-machine-learning-models-with-fastapi-in-python-c1a27319c459) -使用FastAPI作为RESTful API在Python中快速轻松地部署和提供机器学习模型.
- [Using Hypothesis and Schemathesis to Test FastAPI](https://testdriven.io/blog/fastapi-hypothesis/) -将基于属性的测试应用于FastAPI.

### Talks

- [PyConBY 2020: Serve ML models easily with FastAPI](https://www.youtube.com/watch?v=z9K5pwb0rt8) -通过Sebastian Ramirez的演讲，您将学习如何使用FastAPI轻松为ML模型构建生产就绪的Web（JSON）API，包括默认的最佳实践.
- [PyCon UK 2019: FastAPI from the ground up](https://www.youtube.com/watch?v=3DLwPcrE5mA) -此演讲显示了如何使用FastAPI从头开始为数据库构建简单的REST API.

### Videos

- [Building a Stock Screener with FastAPI](https://www.youtube.com/watch?v=5GorMC2lPpk) -使用FastAPI构建基于Web的股票筛选器后，将向您介绍FastAPI的许多功能，包括pydantic模型，依赖项注入，后台任务和SQLAlchemy集成.
- [Building Web APIs Using FastAPI](https://www.youtube.com/watch?v=Pe66M8mn-wA) -使用FastAPI构建Web应用程序编程接口（RESTful API）.
- [FastAPI - A Web Framework for Python](https://www.youtube.com/watch?v=PUhio8CprhI&list=PL5gdMNl42qynpY-o43Jk3evfxEKSts3HS) -了解如何使用FastAPI进行数值验证.
- [FastAPI vs. Django vs. Flask](https://www.youtube.com/watch?v=9YBAOYQOzWs)  -哪种框架最适合2020年的Python？ 哪个使用异步/等待最好？ 哪个最快？ 
- [Serving Machine Learning Models As API with FastAPI](https://www.youtube.com/watch?v=mkDxuRvKUL8) -使用FastAPI构建机器学习API.

### Courses

- [Test-Driven Development with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/) -了解如何使用Python，FastAPI和Docker构建，测试和部署文本汇总微服务.

## Hosting

### PaaS

(Platforms-as-a-Service)

- [Heroku](https://www.heroku.com/) ([Step-by-step tutorial](https://www.tutlinks.com/create-and-deploy-fastapi-app-to-heroku/), [ML model on Heroku tutorial](https://testdriven.io/blog/fastapi-machine-learning/))
- [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
- [Google App Engine](https://cloud.google.com/appengine/)
- [Microsoft Azure App Service](https://azure.microsoft.com/services/app-service/)
- [Deta](https://www.deta.sh/) ([example](https://dev.to/athulcajay/fastapi-deta-ni5))

### IaaS

(Infrastructure-as-a-Service)

- [AWS EC2](https://aws.amazon.com/ec2/)
- [Google Compute Engine](https://cloud.google.com/compute/)
- [Digital Ocean](https://www.digitalocean.com/)
- [Linode](https://www.linode.com/)

### Serverless

Frameworks:

- [Chalice](https://github.com/aws/chalice)
- [Mangum](https://mangum.io/) -使用AWS Lambda和API Gateway运行ASGI应用程序的适配器.
- [Vercel](https://vercel.com/) -（以前的时间）（[example](https://github.com/paul121/fastapi-zeit-now)).
- [Zappa](https://github.com/Miserlou/Zappa)

Compute:

- [AWS Lambda](https://aws.amazon.com/lambda/) ([tutorial](https://iwpnd.pw/articles/2020-01/deploy-fastapi-to-aws-lambda), [code](https://github.com/iwpnd/fastapi-aws-lambda-example))
- [Google Cloud Functions](https://cloud.google.com/functions/)
- [Azure Functions](https://azure.microsoft.com/en-us/services/functions/)
- [Google Cloud Run](https://cloud.google.com/run) ([example](https://github.com/anthcor/cloudrun-fastapi))

## Projects

### Boilerplate

- [Full Stack FastAPI and PostgreSQL - Base Project Generator](https://github.com/tiangolo/full-stack-fastapi-postgresql) -全栈的现代Web应用程序生成器，其中包括FastAPI，PostgreSQL，Docker，Celery，Vue前端，自动HTTPS等（由FastAPI的创建者开发， [Sebastián Ramírez](https://github.com/tiangolo)).
- [FastAPI and Tortoise ORM](https://github.com/prostomarkeloff/fastapi-tortoise) -带有FastAPI（作为Web框架）和Tortoise-ORM（用于通过数据库工作而毫不费力）的强大，简单的Web API模板.
- [FastAPI Model Server Skeleton](https://github.com/eightBEC/fastapi-ml-skeleton) -骨架应用程序，可为生产准备就绪的机器学习模型提供服务.
- [cookiecutter-spacy-fastapi](https://github.com/microsoft/cookiecutter-spacy-fastapi) -使用FastAPI快速部署spaCy模型.
- [cookiecutter-fastapi](https://github.com/arthurhenrique/cookiecutter-fastapi) -使用以下内容的FastAPI项目的Cookiecutter模板：机器学习，诗歌，Azure管道和pytest.
- [openapi-python-client](https://github.com/triaxtec/openapi-python-client) -从OpenAPI生成现代FastAPI Python客户端（通过FastAPI）.
- [Pywork](https://github.com/vutran1710/YeomanPywork) - [Yeoman](https://yeoman.io/) 生成器以构建FastAPI应用.
- [uvicorn-gunicorn-fastapi-docker](https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker) -由Gunicorn管理的带有Uvicorn的Docker映像，用于具有性能自动调整功能的Python 3.7和3.6中的高性能FastAPI Web应用程序.
- [fastapi-gino-arq-uvicorn](https://github.com/leosussan/fastapi-gino-arq-uvicorn)  -使用Python尝试高性能的REST异步API.  FastAPI + GINO + Arq + Uvicorn（带有Redis和PostgreSQL）.
- [FastAPI and React Template](https://github.com/Buuntu/fastapi-react) -使用FastAPI，TypeScript，Docker，PostgreSQL和React的全栈cookiecutter样板.
- [FastAPI Nano](https://github.com/rednafi/fastapi-nano) -具有工厂模式架构的简单FastAPI模板.

### Open Source Projects

- [Awesome FastAPI Projects](https://github.com/Kludex/awesome-fastapi-projects) -使用FastAPI的项目的组织清单.
- [Bitcart](https://github.com/bitcartcc/bitcart) -为商人，用户和开发人员提供易于设置和使用的平台.
- [Dispatch](https://github.com/Netflix/dispatch) -管理安全事件.
- FastAPI CRUD Example:
  - [Async flavor](https://github.com/testdrivenio/fastapi-crud-async)
  - [Sync Flavor](https://github.com/testdrivenio/fastapi-crud-sync)
- [FastAPI Websocket Broadcast](https://github.com/cthwaite/fastapi-websocket-broadcast) -Websocket“广播”演示.
- [FastAPI with Celery, RabbitMQ, and Redis](https://github.com/GregaVrbancic/fastapi-celery) -最小化示例，该示例将FastAPI和Celery与RabbitMQ一起用于任务队列，将Redis用于Celery后端，并使用Flower监视Celery任务.
- [JSON-RPC Server](https://github.com/smagafurov/fastapi-jsonrpc) -基于FastAPI的JSON-RPC服务器.
- [Mailer](https://github.com/rclement/mailer) -用于静态网站的简单死信邮件微服务.
- [RealWorld Example App - mongo](https://github.com/markqiu/fastapi-mongodb-realworld-example-app)
- [RealWorld Example App - postgres](https://github.com/nsidnev/fastapi-realworld-example-app)
- [redis-streams-fastapi-chat](https://github.com/leonh/redis-streams-fastapi-chat) -使用Websockets，Asyncio和FastAPI / Starlette的简单Redis Streams支持的聊天应用程序.
- [Sprites as a service](https://github.com/ljvmiranda921/sprites-as-a-service) -使用Cellular Automata生成您的个人8位头像.
- [Slackers](https://github.com/uhavin/slackers) -松弛的webhooks API.
- [TermPair](https://github.com/cs01/termpair) -通过端到端加密从浏览器查看和控制终端.
- [Universities](https://github.com/ycd/universities) -API服务，用于获取有关全球+9600所大学的信息.
---

<br>

&gt; **注意**：该项目由**提供支持[TestDriven.io](https://testdriven.io/) **. 请通过购买我们的FastAPI课程来支持此开源项目： [Test-Driven Development with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/).
