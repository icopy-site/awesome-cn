<div class="github-widget" data-repo="timofurrer/awesome-asyncio"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome asyncio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 精心挑选的优秀 Python 异步框架、库、软件和资源列表.

蟒蛇 [asyncio](https://docs.python.org/3/library/asyncio.html) Python 3.4 标准库中引入的模块为使用协程编写单线程并发代码、通过套接字和其他资源多路复用 I/O 访问、运行网络客户端和服务器以及其他相关原语提供了基础设施.

Asyncio 并不是真正的全新技术，但几年来它似乎非常流行 - 特别是在 Python 社区以及 2014 年 3 月 Python 3.4 的发布.
因此，要让自己及时了解最棒的软件包是非常困难的.
在这里找到一些 *awesome* 包，如果你错过了一个，我们指望你 [create an Issue or a Pull Request](https://github.com/timofurrer/awesome-asyncio/blob/master/CONTRIBUTING.md) 有了你的建议.




***

## Web Frameworks

*用于构建 Web 应用程序的库.*

* [aiohttp](https://github.com/KeepSafe/aiohttp) - 用于 asyncio 的 Http 客户端/服务器 (PEP-3156).
* [sanic](https://github.com/channelcat/sanic) - 专为快速运行而编写的 Python 3.5+ 网络服务器.
* [Quart](https://gitlab.com/pgjones/quart) - 与 Flask 具有相同 API 的异步 Web 微框架.
* [Vibora](https://github.com/vibora-io/vibora) - Performant web framework inspired by Flask.
* [cirrina](https://github.com/neolynx/cirrina) - 基于 aiohttp 的自以为是的异步 Web 框架.
* [autobahn](https://github.com/crossbario/autobahn-python) - WebSocket 和 WAMP 支持 asyncio 和 Twisted，用于客户端和服务器.
* [websockets](https://github.com/aaugustin/websockets/) - 用于在 Python 中构建 WebSocket 服务器和客户端的库，重点是正确性和简单性.
* [Tornado](http://www.tornadoweb.org/en/stable/) - 高性能网络框架和异步网络库.
* [Japronto!](https://github.com/squeaky-pl/japronto) - 建立在 uvloop 和 picohttpparser 之上的实验性 http 工具包.
* [Starlette](https://github.com/encode/starlette) - 用于构建高性能服务的轻量级 ASGI 框架/工具包.
* [uvicorn](https://github.com/encode/uvicorn) - 闪电般快速的 ASGI 服务器.
* [FastAPI](https://github.com/tiangolo/fastapi)  - 基于类型提示的非常高性能的 Python 3.6+ API 框架. 由 Starlette 和 Pydantic 提供支持.

## Message Queues

*使用消息队列实现应用程序的库.*

* [aioamqp](https://github.com/Polyconseil/aioamqp) - 使用 asyncio 的 AMQP 实现.
* [pyzmq](https://github.com/zeromq/pyzmq) - ZeroMQ 的 Python 绑定.
* [aiozmq](https://github.com/aio-libs/aiozmq) - 与 ZeroMQ 的替代 Asyncio 集成.
* [crossbar](https://github.com/crossbario/crossbar) - Crossbar.io 是分布式和微服务应用程序的网络平台.
* [asyncio-nats](https://github.com/nats-io/asyncio-nats) - NATS 消息传递系统的客户端.
* [aiokafka](https://github.com/aio-libs/aiokafka) - Apache Kafka 客户端.

## Database Drivers

*连接到数据库的库.*

* [asyncpg](https://github.com/MagicStack/asyncpg) - 用于 Python/asyncio 的快速 PostgreSQL 数据库客户端库.
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) - 具有 sqlalchemy 核心支持的 Asyncpg.
* [aiopg](https://github.com/aio-libs/aiopg/) - 用于访问 PostgreSQL 数据库的库.
* [aiomysql](https://github.com/aio-libs/aiomysql) - 用于访问 MySQL 数据库的库
* [aioodbc](https://github.com/aio-libs/aioodbc) - 用于访问 ODBC 数据库的库.
* [motor](https://github.com/mongodb/motor) - MongoDB 的异步 Python 驱动程序.
* [aioredis](https://github.com/aio-libs/aioredis) - [aio-libs](https://github.com/aio-libs) Redis 客户端 (PEP 3156).
* [asyncio-redis](https://github.com/jonathanslenders/asyncio-redis) - 用于 Python asyncio 的 Redis 客户端（PEP 3156）.
* [aiocouchdb](https://github.com/aio-libs/aiocouchdb) - 建立在 aiohttp (asyncio) 之上的 CouchDB 客户端.
* [aioinflux](https://github.com/plugaai/aioinflux) - 建立在 aiohttp 之上的 InfluxDB 客户端.
* [aioes](https://github.com/aio-libs/aioes) - 用于 elasticsearch 的 Asyncio 兼容驱动程序.
* [peewee-async](https://github.com/05bit/peewee-async) - 基于 ORM 的实现 [peewee](https://github.com/coleifer/peewee) 和aiopg.
* [GINO](https://github.com/fantix/gino) - 是一个基于 Python 的轻量级异步 Python ORM [SQLAlchemy](https://www.sqlalchemy.org/) 核心，与 [asyncpg](https://github.com/MagicStack/asyncpg) 方言.
* [Tortoise ORM](https://github.com/tortoise/tortoise-orm) - 带有类似 Django 的 API 和简单的关系管理的本机多后端 ORM.
* [Databases](https://github.com/encode/databases) - SQLAlchemy 核心的异步数据库访问，支持 PostgreSQL、MySQL 和 SQLite.

## Networking

*在您的网络中进行通信的库.*

* [AsyncSSH](https://github.com/ronf/asyncssh) - 提供 SSHv2 协议的异步客户端和服务器实现.
* [aiodns](https://github.com/saghul/aiodns) - 用于 asyncio 的简单 DNS 解析器
* [httpx](https://github.com/encode/httpx) - 带有 Python 3 的异步 HTTP 客户端 [requests](https://github.com/psf/requests) 兼容的 API.

## GraphQL

*用于构建 GraphQL 服务器的库.*

* [Ariadne](https://ariadnegraphql.org) - 用于实现 GraphQL 服务器的模式优先 Python 库.
* [Tartiflette](https://tartiflette.io/) - 架构优先的 Python 3.6+ GraphQL 引擎，构建在 `libgraphqlparser` 之上.

## Testing

*用于测试基于 asyncio 的应用程序的库.*

* [aiomock](https://github.com/nhumrich/aiomock/) - 一个支持异步方法的 python 模拟库.
* [asynctest](https://github.com/Martiusweb/asynctest/)  - 使用测试功能增强标准单元测试包. 异步库
* [pytest-asyncio](https://github.com/pytest-dev/pytest-asyncio) - 对 asyncio 的 Pytest 支持.
* [aresponses](https://github.com/CircleUp/aresponses)  - Asyncio http 模拟. 类似于 [responses](https://github.com/getsentry/responses) 库用于 [requests](https://github.com/requests/requests)
* [aioresponses](https://github.com/pnuckowski/aioresponses) - 在 Python aiohttp 包中模拟/伪造 Web 请求的助手.

## Alternative Loops

*替代异步循环实现.*

* [uvloop](https://github.com/MagicStack/uvloop) - 在 libuv 之上的异步事件循环的超快速实现.

## Misc

*其他很棒的异步库.*

* [aiocache](https://github.com/argaen/aiocache) - 不同后端的缓存管理器.
* [aiofiles](https://github.com/Tinche/aiofiles/) - 对 asyncio 的文件支持.
* [aiodebug](https://github.com/qntln/aiodebug) - 一个用于监控和测试异步程序的微型库.
* [aiorun](https://github.com/cjrh/aiorun) - 一个 `run()` 函数，用于处理启动和正常关闭的所有常用样板.
* [aioserial](https://github.com/changyuheng/aioserial) - 直接替换 [pySerial](https://github.com/pyserial/pyserial).
* [aiozipkin](https://github.com/aio-libs/aiozipkin) - 带有 zipkin 的 asyncio 分布式跟踪检测
* [asgiref](https://github.com/django/asgiref) - 用于 ASGI 到 WSGI 集成的后端工具，包括 sync_to_async 和 async_to_sync 函数包装器.
* [ruia](https://github.com/howie6879/ruia) - 基于 asyncio 的异步网页抓取微框架.
## Writings

*文档、博客文章和其他关于 asyncio 的精彩文章.*

* [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) - 异步 I/O、事件循环、协程和任务.
* [Short well-written intro to asyncio](http://masnun.com/2015/11/13/python-generators-coroutines-native-coroutines-and-async-await.html) - 生成器、协程、本地协程和 async/await.
* [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) - 从基本示例到 URL 获取对异步编程的温和介绍.
* [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) - 使用 python-aiohttp 发出 100 万个请求.
* [ASGI (Asynchronous Server Gateway Interface)](https://asgi.readthedocs.io/en/latest/) - WSGI 的精神继承者，旨在提供具有异步功能的 Python Web 服务器、框架和应用程序之间的标准接口.
* [First Principles Introduction to Asyncio](https://hackernoon.com/a-simple-introduction-to-pythons-asyncio-595d9c9ecf8c) - 对 asyncio 内部工作原理的非流行语第一原则介绍.
* [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - 本教程着眼于如何使用测试驱动开发 (TDD) 使用 FastAPI 开发和测试异步 API.
* [Python Concurrency with asyncio](https://www.manning.com/books/python-concurrency-with-asyncio) - 了解如何通过并发编程和尖端的 asyncio 库来加速缓慢的 Python 代码.

## Talks

*关于 asyncio 的精彩演讲录音.*

* [Topics of Interest (Python Asyncio)](https://youtu.be/ZzfHjytDceU) | [screencast](https://youtu.be/lYe8W04ERnY) | [slides](https://speakerdeck.com/dabeaz/topics-of-interest-async) - PyCon Brasil 2015 主题演讲 (David Beazley).
* [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) | [blog post](http://pgbovine.net/python-async-io-walkthrough.htm) - 8 部分代码演练（Philip Guo）.
* [Async/await in Python 3.5 and why it is awesome](https://www.youtube.com/watch?v=m28fiN9y_r8&t=132s) - EuroPython 2016 (Yury Selivanov).
* [Fear and Awaiting in Async: A Savage Journey to the Heart of the Coroutine Dream](https://www.youtube.com/watch?v=E-1Y4kSsAFc) | [screencast](https://www.youtube.com/watch?v=Bm96RqNGbGo) - PyOhio 2016 主题演讲（大卫·比兹利）.
* [Asynchronous Python for the Complete Beginner](https://www.youtube.com/watch?v=iG6fr81xHKA) | [slides](https://speakerdeck.com/pycon2017/miguel-grinberg-asynchronous-python-for-the-complete-beginner) - PyCon 2017 (Miguel Grinberg).

## Alternatives to asyncio

*在 Python 中进行异步编程的替代方法，其中一些尝试支持与 `asyncio` 的某些兼容性，而另一些则根本不兼容.*

* [curio](https://github.com/dabeaz/curio) - 协程并发库.
  * [Curio-Asyncio Bridge](https://github.com/dabeaz/curio/issues/190) - 基本古玩 -&gt; asyncio 协程桥
* [trio](https://github.com/python-trio/trio) - 人类和蛇人的 Pythonic 异步 I/O.
  * [trio-asyncio](https://github.com/python-trio/trio-asyncio) - 在 Trio 之上重新实现 asyncio 主循环
