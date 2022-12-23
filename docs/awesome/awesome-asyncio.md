<div class="github-widget" data-repo="timofurrer/awesome-asyncio"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome asyncio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 精心挑选的 Python asyncio 框架、库、软件和资源列表.

巨蟒 [asyncio](https://docs.python.org/3/library/asyncio.html) Python 3.4 引入标准库的模块为使用协程编写单线程并发代码、通过套接字和其他资源进行多路复用 I/O 访问、运行网络客户端和服务器以及其他相关原语提供了基础设施.

Asyncio 并不是真正的全新技术，但几年来它似乎非常流行——尤其是在 Python 社区以及 2014 年 3 月发布的 Python 3.4 中.
因此，很难让自己了解最新的最棒的软件包.
在这里找到一些*很棒的*包裹，如果您缺少一个，我们指望您 [create an Issue or a Pull Request](https://github.com/timofurrer/awesome-asyncio/blob/master/CONTRIBUTING.md) 有了你的建议.




***

## Web Frameworks

*用于构建 Web 应用程序的库.*

* [FastAPI](https://github.com/tiangolo/fastapi)  - 基于类型提示的高性能 Python 3.6+ API 框架. 由 Starlette 和 Pydantic 提供支持.
* [Django](https://www.djangoproject.com/) - 具有庞大社区和生态系统的成熟的高级 Python Web 框架.
* [Starlette](https://github.com/encode/starlette) - 用于构建高性能服务的轻量级 ASGI 框架/工具包.
* [aiohttp](https://github.com/KeepSafe/aiohttp) - asyncio 的 HTTP 客户端/服务器（PEP-3156）.
* [sanic](https://github.com/channelcat/sanic) - 专为快速运行而编写的 Python 3.5+ Web 服务器.
* [Quart](https://github.com/pallets/quart) - 具有与 Flask 相同 API 的异步 Web 微框架.
* [autobahn](https://github.com/crossbario/autobahn-python) - WebSocket 和 WAMP 支持客户端和服务器的 asyncio 和 Twisted.
* [websockets](https://github.com/aaugustin/websockets/) - 一个用于在 Python 中构建 WebSocket 服务器和客户端的库，重点是正确性和简单性.
* [Tornado](http://www.tornadoweb.org/en/stable/) - 高性能网络框架和异步网络库.
* [uvicorn](https://github.com/encode/uvicorn) - 快如闪电的 ASGI 服务器.


## Message Queues

*使用消息队列实现应用程序的库.*

* [aioamqp](https://github.com/Polyconseil/aioamqp) - 使用 asyncio 的 AMQP 实现.
* [pyzmq](https://github.com/zeromq/pyzmq) - ZeroMQ 的 Python 绑定.
* [aiozmq](https://github.com/aio-libs/aiozmq) - 与 ZeroMQ 的替代 Asyncio 集成.
* [crossbar](https://github.com/crossbario/crossbar) - Crossbar.io 是一个用于分布式和微服务应用程序的网络平台.
* [asyncio-nats](https://github.com/nats-io/asyncio-nats) - NATS 消息系统的客户端.
* [aiokafka](https://github.com/aio-libs/aiokafka) - Apache Kafka 客户端.

## Database Drivers

*连接数据库的库.*

* [asyncpg](https://github.com/MagicStack/asyncpg) - 用于 Python/asyncio 的快速 PostgreSQL 数据库客户端库.
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) - 具有 sqlalchemy 核心支持的 Asyncpg.
* [aiopg](https://github.com/aio-libs/aiopg/) - 用于访问 PostgreSQL 数据库的库.
* [aiomysql](https://github.com/aio-libs/aiomysql) - 用于访问 MySQL 数据库的库
* [aioodbc](https://github.com/aio-libs/aioodbc) - 用于访问 ODBC 数据库的库.
* [motor](https://github.com/mongodb/motor) - MongoDB 的异步 Python 驱动程序.
* [redis-py](https://github.com/redis/redis-py) - Redis Python 客户端（包括 [aioreadis](https://github.com/aio-libs/aioredis) 现在）.
* [aiocouchdb](https://github.com/aio-libs/aiocouchdb) - 建立在 aiohttp (asyncio) 之上的 CouchDB 客户端.
* [aioinflux](https://github.com/plugaai/aioinflux) - 建立在 aiohttp 之上的 InfluxDB 客户端.
* [aioes](https://github.com/aio-libs/aioes) - 用于弹性搜索的 Asyncio 兼容驱动程序.
* [peewee-async](https://github.com/05bit/peewee-async) - 基于ORM的实现 [peewee](https://github.com/coleifer/peewee) 和aiopg.
* [GINO](https://github.com/fantix/gino) - 是一个轻量级的异步Python ORM，基于 [SQLAlchemy](https://www.sqlalchemy.org/) 核心，与 [asyncpg](https://github.com/MagicStack/asyncpg) 方言.
* [Tortoise ORM](https://github.com/tortoise/tortoise-orm) - 本机多后端 ORM，具有类似 Django 的 API 和简单的关系管理.
* [Databases](https://github.com/encode/databases) - SQLAlchemy 核心的异步数据库访问，支持 PostgreSQL、MySQL 和 SQLite.
* [Prisma Client Python](https://github.com/RobertCraigie/prisma-client-py) - 一个自动生成的、完全类型安全的 ORM，由 Pydantic 提供支持，专门为您的模式量身定制——支持 SQLite、PostgreSQL、MySQL、MongoDB、MariaDB 等.
* [Piccolo](https://github.com/piccolo-orm/piccolo) - 一个 ORM / 查询生成器，可以在异步和同步模式下工作，具有漂亮的管理 GUI 和 ASGI 中间件.
* [Beanie](https://beanie-odm.dev) - An async MongoDB ODM built on [motor](https://github.com/mongodb/motor) 和 [Pydantic](https://pydantic-docs.helpmanual.io).

## Networking

*在您的网络中进行通信的库.*

* [AsyncSSH](https://github.com/ronf/asyncssh) - 提供 SSHv2 协议的异步客户端和服务器实现.
* [aiodns](https://github.com/saghul/aiodns) - 用于 asyncio 的简单 DNS 解析器.
* [aioping](https://github.com/stellarbit/aioping) - ICMP (ping) 协议的快速异步实现.
* [httpx](https://github.com/encode/httpx) - 用于 Python 3 的异步 HTTP 客户端 [requests](https://github.com/psf/requests) 兼容的API.

## GraphQL

*构建 GraphQL 服务器的库.*

* [Ariadne](https://ariadnegraphql.org) - 用于实现 GraphQL 服务器的模式优先 Python 库.
* [Tartiflette](https://tartiflette.io/) - 架构优先的 Python 3.6+ GraphQL 引擎构建在 `libgraphqlparser` 之上.
* [Strawberry](https://strawberry.rocks) - 代码优先的 Python 3 GraphQL 服务器，支持 Django、Flask 和 FastAPI/Starlette.

## Testing

*用于测试基于 asyncio 的应用程序的库.*

* [aiomock](https://github.com/nhumrich/aiomock/) - 一个支持异步方法的 python 模拟库.
* [asynctest](https://github.com/Martiusweb/asynctest/)  - 使用测试功能增强标准单元测试包. 异步库
* [pytest-asyncio](https://github.com/pytest-dev/pytest-asyncio) - Pytest 支持异步.
* [aresponses](https://github.com/CircleUp/aresponses)  - 异步 http 模拟. 类似于 [responses](https://github.com/getsentry/responses) 图书馆用于 [requests](https://github.com/requests/requests).
* [aioresponses](https://github.com/pnuckowski/aioresponses) - Python aiohttp 包中模拟/伪造 Web 请求的帮助程序.

## Alternative Loops

*替代异步循环实现.*

* [uvloop](https://github.com/MagicStack/uvloop) - 在 libuv 之上超快速地实现异步事件循环.

## Misc

*其他很棒的异步库.*

* [aiochan](https://github.com/zh217/aiochan) - 在 asyncio 之上使用通道、选择和多处理的 CSP 样式并发.
* [aiocache](https://github.com/argaen/aiocache) - 不同后端的缓存管理器.
* [aiofiles](https://github.com/Tinche/aiofiles/) - 文件支持异步.
* [aiopath](https://github.com/alexdelorenzo/aiopath) - asyncio 的异步 `pathlib`.
* [aiodebug](https://github.com/qntln/aiodebug) - 一个用于监控和测试异步程序的小型库.
* [aiorun](https://github.com/cjrh/aiorun) - 一个 `run()` 函数，用于处理启动和正常关闭的所有常用样板.
* [aiosc](https://github.com/artfwo/aiosc) - 轻量级开放声音控制实施.
* [aioserial](https://github.com/changyuheng/aioserial) - 直接替换 [pySerial](https://github.com/pyserial/pyserial).
* [aiozipkin](https://github.com/aio-libs/aiozipkin) - 使用 zipkin 的 asyncio 分布式跟踪工具
* [asgiref](https://github.com/django/asgiref) - 用于 ASGI 到 WSGI 集成的后端实用程序，包括 sync_to_async 和 async_to_sync 函数包装器.
* [ruia](https://github.com/howie6879/ruia) - 基于 asyncio 的异步网络抓取微框架.
* [kubernetes_asyncio](https://github.com/tomplus/kubernetes_asyncio) - Kubernetes 的异步客户端库.
* [aiomisc](https://github.com/aiokitchen/aiomisc) - `asyncio` 的杂项实用程序.

## Writings

*文档、博客文章和其他关于 asyncio 的精彩文章.*

* [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) - 异步 I/O、事件循环、协程和任务.
* [Short well-written intro to asyncio](http://masnun.com/2015/11/13/python-generators-coroutines-native-coroutines-and-async-await.html) - 生成器、协程、本机协程和异步/等待.
* [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) - 对异步编程的简单介绍，从基本示例到 URL 获取.
* [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) - 使用 python-aiohttp 发出 100 万次请求.
* [ASGI (Asynchronous Server Gateway Interface)](https://asgi.readthedocs.io/en/latest/) - WSGI 的精神继承者，旨在提供具有异步能力的 Python Web 服务器、框架和应用程序之间的标准接口.
* [First Principles Introduction to Asyncio](https://hackernoon.com/a-simple-introduction-to-pythons-asyncio-595d9c9ecf8c) - 对 asyncio 内部工作原理的非流行语第一原则介绍.
* [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - 本教程介绍如何使用测试驱动开发 (TDD) 使用 FastAPI 开发和测试异步 API.
* [Python Concurrency with asyncio](https://www.manning.com/books/python-concurrency-with-asyncio) - 了解如何使用并发编程和尖端的 asyncio 库加速慢速 Python 代码.

## Talks

*有关 asyncio 的精彩演讲录音.*

* [Topics of Interest (Python Asyncio)](https://youtu.be/ZzfHjytDceU) | [screencast](https://youtu.be/lYe8W04ERnY) | [slides](https://speakerdeck.com/dabeaz/topics-of-interest-async) - PyCon Brasil 2015 主题演讲（David Beazley）.
* [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) - 8 部分代码演练（Philip Guo）.
* [Async/await in Python 3.5 and why it is awesome](https://www.youtube.com/watch?v=m28fiN9y_r8&t=132s) - EuroPython 2016（Yury Selivanov）.
* [Fear and Awaiting in Async: A Savage Journey to the Heart of the Coroutine Dream](https://www.youtube.com/watch?v=E-1Y4kSsAFc) | [screencast](https://www.youtube.com/watch?v=Bm96RqNGbGo) - PyOhio 2016 主题演讲（David Beazley）.
* [Asynchronous Python for the Complete Beginner](https://www.youtube.com/watch?v=iG6fr81xHKA) | [slides](https://speakerdeck.com/pycon2017/miguel-grinberg-asynchronous-python-for-the-complete-beginner) - PyCon 2017（米格尔·格林伯格）.
* [Demystifying Python's Async and Await Keywords](https://www.youtube.com/watch?v=F19R_M4Nay4) - JetBrains TV 2020（迈克尔·肯尼迪）

## Alternatives to asyncio

*在 Python 中进行异步编程的替代方法，其中一些尝试支持与 `asyncio` 的某些兼容性，另一些则根本不兼容.*

* [curio](https://github.com/dabeaz/curio) - 协程并发库.
  * [Curio-Asyncio Bridge](https://github.com/dabeaz/curio/issues/190) - 基本 curio -&gt; asyncio 协程桥.
* [trio](https://github.com/python-trio/trio) - 用于人类和蛇人的 Pythonic 异步 I/O.
  * [trio-asyncio](https://github.com/python-trio/trio-asyncio) - 在 Trio 之上重新实现异步主循环.
* [AnyIO](https://github.com/agronholm/anyio) - 在 trio 或 asyncio 之上工作的高级异步并发和网络框架.
