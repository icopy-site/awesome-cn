<div class="github-widget" data-repo="mjhea0/awesome-fastapi"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint disable double-link-->

## Awesome FastAPI | [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

&gt; 与 FastAPI 相关的精彩内容的精选列表.

[FastAPI](https://fastapi.tiangolo.com/) 是一个现代的、高性能的、包含电池的 Python Web 框架，非常适合构建 RESTful API.



## Third-Party Extensions

### Admin

- [FastAPI Admin](https://github.com/fastapi-admin/fastapi-admin) - 功能性管理面板，提供用于对数据执行 CRUD 操作的用户界面.

### Auth

- [FastAPI Auth](https://github.com/dmontagu/fastapi-auth) - 支持 OAuth2 密码流和 JWT 访问和刷新令牌的可插入身份验证.
- [FastAPI Azure auth](https://github.com/Intility/fastapi-azure-auth) - FastAPI 的 Azure AD 身份验证.
- [FastAPI Cloud Auth](https://github.com/tokusumi/fastapi-cloudauth) - FastAPI 和云身份验证服务（AWS Cognito、Auth0、Firebase 身份验证）之间的简单集成.
- [FastAPI Login](https://github.com/MushroomMaula/fastapi_login) - 账户管理和认证（基于 [Flask-Login](https://github.com/maxcountryman/flask-login)).
- [FastAPI JWT Auth](https://github.com/IndominusByte/fastapi-jwt-auth) - JWT 身份验证（基于 [Flask-JWT-Extended](https://github.com/vimalloc/flask-jwt-extended)).
- [FastAPI Permissions](https://github.com/holgi/fastapi-permissions) - 行级权限.
- [FastAPI Security](https://github.com/jmagnusson/fastapi-security) - 在 FastAPI 中实现身份验证和授权作为依赖项.
- [FastAPI Simple Security](https://github.com/mrtolkien/fastapi_simple_security) - 开箱即用的 API 密钥安全可通过路径操作进行管理.
- [FastAPI Users](https://github.com/frankie567/fastapi-users) - 账户管理、认证、授权.

### Databases

#### ORMs

- [FastAPI SQLAlchemy](https://github.com/mfreeborn/fastapi-sqlalchemy) - FastAPI 和 [SQLAlchemy](https://www.sqlalchemy.org/).
- [FastAPIwee](https://github.com/Ignisor/FastAPIwee) - 一种基于 REST API 创建的简单方法 [PeeWee](https://github.com/coleifer/peewee) 模型.
- [GINO](https://github.com/python-gino/gino) - 构建在 SQLAlchemy 核心之上的轻量级异步 ORM，用于 Python asyncio.
  - [FastAPI Example](https://github.com/leosussan/fastapi-gino-arq-uvicorn)
- [ORM](https://github.com/encode/orm) - 一个异步 ORM.
- [ormar](https://collerek.github.io/ormar/)  - Ormar 是一个异步 ORM，它使用 pydantic 验证，可以直接在 FastAPI 请求和响应中使用，因此您只需要维护一组模型. 包括 Alembic 迁移.
  - [FastAPI Example](https://collerek.github.io/ormar/fastapi/) - 在 ormar 中使用 FastAPI.
- [Piccolo](https://github.com/piccolo-orm/piccolo) - 一个异步 ORM 和查询构建器，支持 Postgres 和 SQLite，带有电池（迁移、安全等）.
  - [FastAPI Examples](https://github.com/piccolo-orm/piccolo_examples) - 将 FastAPI 与 Piccolo 一起使用.
  - [Piccolo Admin](https://github.com/piccolo-orm/piccolo_admin) - 强大且现代的管理 GUI，使用 Piccolo ORM.
- [Tortoise ORM](https://tortoise-orm.readthedocs.io/en/latest/index.html) - 受 Django 启发的易于使用的 asyncio ORM（对象关系映射器）.
  - [FastAPI Example](https://tortoise-orm.readthedocs.io/en/latest/examples/fastapi.html) - Tortoise-ORM FastAPI 集成的一个例子.
  - [Tutorial: Setting up Tortoise ORM with FastAPI](https://web.archive.org/web/20200523174158/https://robwagner.dev/tortoise-fastapi-setup/)
  - [Aerich](https://tortoise-orm.readthedocs.io/en/latest/migration.html) - Tortoise ORM 迁移工具.

#### Query Builders

- [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) - 一个包装 [asyncpg](https://github.com/MagicStack/asyncpg) 用于 [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/).
- [Databases](https://github.com/encode/databases) - 异步 SQL 查询构建器，在 [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/) 表达语言.

#### ODMs

- [Beanie](https://github.com/roman-right/beanie) - MongoDB 的异步 Python ODM，基于 [Motor](https://motor.readthedocs.io/en/stable/)
and [Pydantic](https://pydantic-docs.helpmanual.io/)，它支持开箱即用的数据和架构迁移.
- [MongoEngine](http://mongoengine.org/) - 用于从 Python 处理 MongoDB 的文档对象映射器（想想 ORM，但用于文档数据库）.
- [Motor](https://motor.readthedocs.io/) - 用于 MongoDB 的异步 Python 驱动程序.
- [ODMantic](https://art049.github.io/odmantic/) - AsyncIO MongoDB ODM 集成 [Pydantic](https://pydantic-docs.helpmanual.io/).

#### Other Tools

- [Pydantic-SQLAlchemy](https://github.com/tiangolo/pydantic-sqlalchemy) - 将 SQLAlchemy 模型转换为 [Pydantic](https://pydantic-docs.helpmanual.io/) 模型.
- [FastAPI-CamelCase](https://ahmednafies.github.io/fastapi_camelcase/) - 使用 FastAPI 的 CamelCase JSON 支持 [Pydantic](https://pydantic-docs.helpmanual.io/).
  - [CamelCase Models with FastAPI and Pydantic](https://medium.com/analytics-vidhya/camel-case-models-with-fast-api-and-pydantic-5a8acb6c0eee) - 扩展作者随附的博客文章.

### Developer Tools

- [FastAPI Code Generator](https://github.com/koxudaxi/fastapi-code-generator) - 从 OpenAPI 文件创建 FastAPI 应用程序，支持架构驱动开发.
- [FastAPI Client Generator](https://github.com/dmontagu/fastapi_client) - 从 OpenAPI 规范生成一个 mypy 和 IDE 友好的 API 客户端.
- [FastAPI Profiler](https://github.com/sunhailin-Leo/fastapi_profiler) - joerick/pyinstrument 的 FastAPI 中间件，用于检查您的服务性能.
- [FastAPI Versioning](https://github.com/DeanWay/fastapi-versioning) - API 版本控制.
- [Jupyter Notebook REST API](https://github.com/Invictify/Jupter-Notebook-REST-API) - 将您的 Jupyter 笔记本作为 RESTful API 端点运行.
- [Manage FastAPI](https://github.com/ycd/manage-fastapi) - 用于生成和管理 FastAPI 项目的 CLI 工具.
- [msgpack-asgi](https://github.com/florimondmanca/msgpack-asgi) - 自动 [MessagePack](https://msgpack.org/) 内容协商.

### Email

- [FastAPI Mail](https://github.com/sabuhish/fastapi-mail) - 用于发送电子邮件和附件（个人和批量）的轻量级邮件系统.

### Utils

- [FastAPI Cache](https://github.com/comeuplater/fastapi_cache) - 一个简单的轻量级缓存系统.
- [FastAPI Chameleon](https://github.com/mikeckennedy/fastapi-chameleon) - 将 Chameleon 模板语言集成到 FastAPI.
- [FastAPI Contrib](https://github.com/identixone/fastapi_contrib) - 自以为是的实用程序集：分页、身份验证中间件、权限、自定义异常处理程序、MongoDB 支持和 Opentracing 中间件.
- [FastAPI CRUDRouter](https://github.com/awtkns/fastapi-crudrouter) - FastAPI 路由器，可自动为您的模型创建和记录 CRUD 路由.
- [FastAPI Jinja](https://github.com/AGeekInside/fastapi-jinja) - 向 FastAPI 添加 Jinja 模板语言的集成.
- [FastAPI Limiter](https://github.com/long2ice/fastapi-limiter) - FastAPI 的请求速率限制器.
- [FastAPI MQTT](https://github.com/sabuhish/fastapi-mqtt) - MQTT 协议的扩展.
- [FastAPI Pagination](https://github.com/uriyyo/fastapi-pagination) - FastAPI 的分页.
- [FastAPI Plugins](https://github.com/madkote/fastapi-plugins) - Redis 和调度程序插件.
- [FastAPI ServiceUtils](https://github.com/skallfass/fastapi_serviceutils) - 用于创建 API 服务的生成器.
- [FastAPI SocketIO](https://github.com/pyropy/fastapi-socketio) - FastAPI 和 SocketIO 的轻松集成.
- [FastAPI Utilities](https://github.com/dmontagu/fastapi-utils) - 可重用的实用程序：基于类的视图、响应推断路由器、周期性任务、计时中间件、SQLAlchemy 会话、OpenAPI 规范简化.
- [FastAPI Websocket Pub/Sub](https://github.com/authorizon/fastapi_websocket_pubsub) - 经典的发布/订阅模式可以通过网络和云实时轻松访问和扩展.
- [FastAPI Websocket RPC](https://github.com/authorizon/fastapi_websocket_rpc) - Websockets 上的 RPC（双向 JSON RPC）变得简单、健壮和生产就绪.
- [OpenTelemetry FastAPI Instrumentation](https://github.com/open-telemetry/opentelemetry-python-contrib/tree/main/instrumentation/opentelemetry-instrumentation-fastapi) - 库提供 FastAPI Web 框架的自动和手动检测，检测由使用该框架的应用程序提供的 http 请求.
- [Prerender Python Starlette](https://github.com/BeeMyDesk/prerender-python-starlette) - Prerender 的 Starlette 中间件.
- [Prometheus FastAPI Instrumentator](https://github.com/trallnag/prometheus-fastapi-instrumentator) - 适用于 FastAPI 应用程序的可配置和模块化 Prometheus Instrumentator.
- [SlowApi](https://github.com/laurents/slowapi) - 速率限制器（基于 [Flask-Limiter](https://flask-limiter.readthedocs.io)).
- [Starlette Context](https://github.com/tomwojcik/starlette-context) - 允许您在项目中的任何位置存储和访问请求数据，这对记录很有用.
- [Starlette Exporter](https://github.com/stephenhillier/starlette_exporter) - FastAPI 和 Starlette 的更多普罗米修斯集成.
- [Starlette OpenTracing](https://github.com/acidjunk/starlette-opentracing) - 对 Starlette 和 FastAPI 的 Opentracing 支持.
- [Starlette Prometheus](https://github.com/perdy/starlette-prometheus) - FastAPI 和 Starlette 的 Prometheus 集成.

## Resources

### Official Resources

- [Documentation](https://fastapi.tiangolo.com/) - 综合文档.
- [Tutorial](https://fastapi.tiangolo.com/tutorial/) - 官方教程向您展示如何使用 FastAPI 的大部分功能，一步一步.
- [Source Code](https://github.com/tiangolo/fastapi) - 托管在 GitHub 上.
- [Gitter Chat](https://gitter.im/tiangolo/fastapi) - 与其他 FastAPI 用户聊天.

### External Resources

- [TestDriven.io FastAPI](https://testdriven.io/blog/topics/fastapi/) - 多篇针对 FastAPI 的文章，专注于开发和测试生产就绪的 RESTful API、提供机器学习模型等.

### Podcasts

- [Build The Next Generation Of Python Web Applications With FastAPI](https://www.pythonpodcast.com/fastapi-web-application-framework-episode-259/) - 在这一集中 [Podcast Init](https://www.pythonpodcast.com/), FastAPI 的创建, [Sebastián Ramirez](https://tiangolo.com/)，分享了他构建 FastAPI 的动机以及它是如何工作的.
- [FastAPI on PythonBytes](https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855) - 很好的项目概述.

### Articles

- [FastAPI has Ruined Flask Forever for Me](https://towardsdatascience.com/fastapi-has-ruined-flask-forever-for-me-73916127da)
- [Why we switched from Flask to FastAPI for production machine learning](https://towardsdatascience.com/why-we-switched-from-flask-to-fastapi-for-production-machine-learning-765aab9b3679) - 深入了解您可能想要从 Flask 迁移到 FastAPI 的原因.

### Tutorials

- [Async SQLAlchemy with FastAPI](https://stribny.name/blog/fastapi-asyncalchemy/) - 了解如何异步使用 SQLAlchemy.
- [Build and Secure an API in Python with FastAPI](https://blog.yezz.me/blog/Build-and-Secure-an-API-in-Python-with-FastAPI) - 保护和维护基于 FastAPI 和 SQLAlchemy 的 API.
- [Demystifying Authentication with FastAPI and a Frontend](https://kernelpanic.io/demystifying-authentication-with-fastapi-and-a-frontend/) - 添加基于令牌的身份验证.
- [Deploy a Dockerized FastAPI App to Google Cloud Platform](https://towardsdatascience.com/deploy-a-dockerized-fastapi-app-to-google-cloud-platform-24f72266c7ef) - 使用 Cloud Run 和 SQL 实例将 Dockerized Python 应用程序部署到 Google Cloud Platform 的简短指南.
- [Deploy Machine Learning Models with Keras, FastAPI, Redis and Docker](https://medium.com/analytics-vidhya/deploy-machine-learning-models-with-keras-fastapi-redis-and-docker-4940df614ece)
- [Deploying Iris Classifications with FastAPI and Docker](https://towardsdatascience.com/deploying-iris-classifications-with-fastapi-and-docker-7c9b83fdec3a) - Dockerizing 一个 FastAPI 应用程序.
- [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - 使用测试驱动开发，使用 FastAPI、Postgres、Pytest 和 Docker 开发和测试异步 API.
- [FastAPI for Flask Users](https://amitness.com/2020/06/fastapi-vs-flask/) - 通过与 Flask 的并排代码比较来学习 FastAPI.
- [FastAPI Microservice Patterns](https://florian-kromer.medium.com/fastapi-microservice-patterns-3052c1241019) - 包含微服务模式示例性实现的博客文章系列.
  - [Local Development Environment](https://florian-kromer.medium.com/fastapi-microservice-patterns-local-development-environment-12182e786f1c) - 简而言之，Skaffold、docker、kubectl 和 minikube.
  - [Service discovery in Container Orchestration Platforms](https://florian-kromer.medium.com/fastapi-microservice-patterns-service-discovery-in-container-orchestration-platforms-290c00d1ad8) - 解释了在 Kubernetes 中启用 FastAPI 服务通信.
  - [Asynchronous Communication](https://florian-kromer.medium.com/fastapi-microservice-patterns-asynchronous-communication-45a3b68f8bb8) - 通过消息传递启用松散耦合的服务.
  - [Application Monitoring](https://medium.com/swlh/fastapi-microservice-patterns-application-monitoring-49fcb7341d9a) - 使用 Prometheus 和 Grafana 进行应用程序指标监控.
  - [Serverless Deployment](https://medium.com/swlh/fastapi-microservice-serverless-deployment-41a6d21e5cb3) - 关于 FastAPI 与 Kubernetes 原生 FaaS 平台兼容性的现状.
- [How to deploy your ConvNet classifier with Keras and FastAPI](https://www.machinecurve.com/index.php/2020/03/19/tutorial-how-to-deploy-your-convnet-classifier-with-keras-and-fastapi/) - 通过基于 Web 的 API 部署机器学习模型.
- [How to monitor your FastAPI service](https://guitton.co/posts/fastapi-monitoring/) - Explains how to implement Application Performance Monitoring (APM) using OpenTelemetry and Datadog/Jaeger.
- [Implementing FastAPI Services – Abstraction and Separation of Concerns](https://camillovisini.com/article/abstracting-fastapi-services/) - FastAPI 应用程序和服务结构，提供更易于维护的代码库.
- [Introducing FARM Stack - FastAPI, React, and MongoDB](https://www.mongodb.com/developer/how-to/FARM-Stack-FastAPI-React-MongoDB/) - 开始使用完整的 FastAPI Web 应用程序堆栈.
- [Introduction to the FastAPI Python Framework](https://www.errietta.me/blog/python-fastapi-intro/) - FastAPI 的快速介绍.
- [Porting Flask to FastAPI for ML Model Serving](https://www.pluralsight.com/tech-blog/porting-flask-to-fastapi-for-ml-model-serving/) - Flask 与 FastAPI 的比较.
- [Real-time data streaming using FastAPI and WebSockets](https://stribny.name/blog/2020/07/real-time-data-streaming-using-fastapi-and-websockets/) - 了解如何将来自 FastAPI 的数据直接流式传输到实时图表中.
- [Running FastAPI applications in production](https://stribny.name/blog/fastapi-production/) - 使用 Gunicorn 和 systemd 进行生产部署.
- [Serving Machine Learning Models with FastAPI in Python](https://medium.com/@8B_EC/tutorial-serving-machine-learning-models-with-fastapi-in-python-c1a27319c459) - 使用 FastAPI 以 RESTful API 的形式在 Python 中快速轻松地部署和提供机器学习模型.
- [Streaming video with FastAPI](https://stribny.name/blog/fastapi-video/) - 了解如何提供视频流.
- [Using Hypothesis and Schemathesis to Test FastAPI](https://testdriven.io/blog/fastapi-hypothesis/) - 将基于属性的测试应用于 FastAPI.

### Talks

- [PyConBY 2020: Serve ML models easily with FastAPI](https://www.youtube.com/watch?v=z9K5pwb0rt8) - 从 Sebastian Ramirez 的演讲中，您将学习如何使用 FastAPI 为您的 ML 模型轻松构建生产就绪 Web (JSON) API，包括默认的最佳实践.
- [PyCon UK 2019: FastAPI from the ground up](https://www.youtube.com/watch?v=3DLwPcrE5mA) - 本演讲展示了如何使用 FastAPI 从头开始​​为数据库构建简单的 REST API.

### Videos

- [Building a Stock Screener with FastAPI](https://www.youtube.com/watch?v=5GorMC2lPpk) - 如果您使用 FastAPI 构建基于 Web 的股票筛选器，您将了解 FastAPI 的许多功能，包括 pydantic 模型、依赖项注入、后台任务和 SQLAlchemy 集成.
- [Building Web APIs Using FastAPI](https://www.youtube.com/watch?v=Pe66M8mn-wA) - 使用 FastAPI 构建 Web 应用程序编程接口（RESTful API）.
- [FastAPI - A Web Framework for Python](https://www.youtube.com/watch?v=PUhio8CprhI&list=PL5gdMNl42qynpY-o43Jk3evfxEKSts3HS) - 了解如何使用 FastAPI 进行数字验证.
- [FastAPI vs. Django vs. Flask](https://www.youtube.com/watch?v=9YBAOYQOzWs)  - 2020 年哪个框架最适合 Python？ 哪个使用 async/await 最好？ 哪个最快？
- [Serving Machine Learning Models As API with FastAPI](https://www.youtube.com/watch?v=mkDxuRvKUL8) - 使用 FastAPI 构建机器学习 API.

### Courses

- [Test-Driven Development with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/) - 了解如何使用 Python、FastAPI 和 Docker 构建、测试和部署文本摘要微服务.
- [Modern APIs with FastAPI and Python](https://training.talkpython.fm/courses/getting-started-with-fastapi) - 旨在让您使用 FastAPI 快速创建在云中运行的新 API 的课程.
- [Full Web Apps with FastAPI Course](https://training.talkpython.fm/courses/full-html-web-applications-with-fastapi) - 您将学习使用 FastAPI 构建完整的 Web 应用程序，相当于您可以使用 Flask 或 Django 执行的操作.
- [The Definitive Guide to Celery and FastAPI](https://testdriven.io/courses/fastapi-celery/) - 了解如何将 Celery 添加到 FastAPI 应用程序以提供异步任务处理.

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
- [Mangum](https://mangum.io/) - 用于使用 AWS Lambda 和 API Gateway 运行 ASGI 应用程序的适配器.
- [Vercel](https://vercel.com/) - （以前的时间）（[example](https://github.com/paul121/fastapi-zeit-now)).
- [Zappa](https://github.com/Miserlou/Zappa)

Compute:

- [AWS Lambda](https://aws.amazon.com/lambda/) ([tutorial](https://iwpnd.pw/articles/2020-01/deploy-fastapi-to-aws-lambda), [code](https://github.com/iwpnd/fastapi-aws-lambda-example))
- [Google Cloud Functions](https://cloud.google.com/functions/)
- [Azure Functions](https://azure.microsoft.com/en-us/services/functions/)
- [Google Cloud Run](https://cloud.google.com/run) ([example](https://github.com/anthcor/cloudrun-fastapi))

## Projects

### Boilerplate

- [Full Stack FastAPI and PostgreSQL - Base Project Generator](https://github.com/tiangolo/full-stack-fastapi-postgresql) - 全栈式现代 Web 应用程序生成器，包括 FastAPI、PostgreSQL、Docker、Celery、Vue 前端、自动 HTTPS 等（由 FastAPI 的创建者开发， [Sebastián Ramírez](https://github.com/tiangolo)).
- [FastAPI and Tortoise ORM](https://github.com/prostomarkeloff/fastapi-tortoise) - 强大而简单的 Web API 模板，带有 FastAPI（作为 Web 框架）和 Tortoise-ORM（用于通过数据库工作而不会头疼）.
- [FastAPI Model Server Skeleton](https://github.com/eightBEC/fastapi-ml-skeleton) - 为机器学习模型提供生产就绪的骨架应用程序.
- [cookiecutter-spacy-fastapi](https://github.com/microsoft/cookiecutter-spacy-fastapi) - 使用 FastAPI 快速部署 spaCy 模型.
- [cookiecutter-fastapi](https://github.com/arthurhenrique/cookiecutter-fastapi) - FastAPI 项目的 Cookiecutter 模板，使用：机器学习、诗歌、Azure Pipelines 和 pytest.
- [openapi-python-client](https://github.com/openapi-generators/openapi-python-client) - 从 OpenAPI 生成现代 FastAPI Python 客户端（通过 FastAPI）.
- [Pywork](https://github.com/vutran1710/YeomanPywork) - [Yeoman](https://yeoman.io/) 生成器来构建 FastAPI 应用程序.
- [uvicorn-gunicorn-fastapi-docker](https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker) - Docker 镜像与 Uvicorn 由 Gunicorn 管理，用于 Python 3.7 和 3.6 中具有性能自动调整的高性能 FastAPI Web 应用程序.
- [fastapi-gino-arq-uvicorn](https://github.com/leosussan/fastapi-gino-arq-uvicorn)  - 使用 Python 提供高性能异步 REST API 的模板.  FastAPI + GINO + Arq + Uvicorn（带 Redis 和 PostgreSQL）.
- [FastAPI and React Template](https://github.com/Buuntu/fastapi-react) - 使用 FastAPI、TypeScript、Docker、PostgreSQL 和 React 的全栈 cookiecutter 样板.
- [FastAPI Nano](https://github.com/rednafi/fastapi-nano) - 具有工厂模式架构的简单 FastAPI 模板.
- [inboard](https://github.com/br3ndonland/inboard) - Docker 映像为您的 FastAPI 应用程序提供支持并帮助您更快地交付.

### Open Source Projects

- [Awesome FastAPI Projects](https://github.com/Kludex/awesome-fastapi-projects) - 使用 FastAPI 的有组织的项目列表.
- [Bitcart](https://github.com/bitcartcc/bitcart) - 为商家、用户和开发人员提供易于设置和使用的平台.
- [Coronavirus-tg-api](https://github.com/egbakou/coronavirus-tg-api) - 用于跟踪全球冠状病毒（COVID-19、SARS-CoV-2）爆发的 API.
- [Dispatch](https://github.com/Netflix/dispatch) - 管理安全事件.
- FastAPI CRUD 示例：
  - [Async flavor](https://github.com/testdrivenio/fastapi-crud-async)
  - [Sync Flavor](https://github.com/testdrivenio/fastapi-crud-sync)
- [DogeAPI](https://github.com/yezz123/DogeAPI) - 具有高性能的 API，可使用 OAuth2PasswordBearer 创建简单的博客和 CRUD.
- [FastAPI Websocket Broadcast](https://github.com/cthwaite/fastapi-websocket-broadcast) - Websocket“广播”演示.
- [FastAPI with Celery, RabbitMQ, and Redis](https://github.com/GregaVrbancic/fastapi-celery) - Minimal example utilizing FastAPI and Celery with RabbitMQ for task queue, Redis for Celery backend, and Flower for monitoring the Celery tasks.
- [JeffQL](https://github.com/yezz123/JeffQL/) - 使用 GraphQL 和 JWT 的简单身份验证和登录 API.
- [JSON-RPC Server](https://github.com/smagafurov/fastapi-jsonrpc) - 基于 FastAPI 的 JSON-RPC 服务器.
- [Mailer](https://github.com/rclement/mailer) - 用于静态网站的极其简单的邮件微服务.
- [OPAL (Open Policy Administration Layer)](https://github.com/authorizon/opal)  - 基于 Open-Policy 的实时授权更新； 使用 FastAPI、Typer 和 FastAPI WebSocket 发布/订阅构建.
- [RealWorld Example App - mongo](https://github.com/markqiu/fastapi-mongodb-realworld-example-app)
- [RealWorld Example App - postgres](https://github.com/nsidnev/fastapi-realworld-example-app)
- [redis-streams-fastapi-chat](https://github.com/leonh/redis-streams-fastapi-chat) - 一个简单的 Redis Streams 支持的聊天应用程序，使用 Websockets、Asyncio 和 FastAPI/Starlette.
- [Sprites as a service](https://github.com/ljvmiranda921/sprites-as-a-service) - 使用元胞自动机生成您的个人 8 位头像.
- [Slackers](https://github.com/uhavin/slackers) - Slack webhooks API.
- [TermPair](https://github.com/cs01/termpair) - 通过端到端加密从浏览器查看和控制终端.
- [Universities](https://github.com/ycd/universities) - 用于获取全球 +9600 所大学信息的 API 服务.

## Sponsors

请通过查看我们的赞助商来支持这个开源项目：

<a href="https://www.deta.sh/?ref=awesome-fastapi" target="_blank" title="The launchpad for all your (team's) ideas"><img src="https://raw.githubusercontent.com/mjhea0/awesome-fastapi/master/images/deta.svg?sanitize=true"></a>

<a href="https://testdriven.io/courses/tdd-fastapi/?ref=awesome-fastapi" target="_blank" title="Learn to build high-quality web apps with best practices"><img src="https://raw.githubusercontent.com/mjhea0/awesome-fastapi/master/images/testdriven.svg?sanitize=true"></a>
