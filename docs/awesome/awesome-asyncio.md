<div class="github-widget" data-repo="timofurrer/awesome-asyncio"></div>
## Awesome asyncio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精心策划的Python异步框架，库，软件和资源列表.

Python [asyncio](https://docs.python.org/3/library/asyncio.html) 使用Python 3.4引入标准库的模块提供了使用协同程序编写单线程并发代码，通过套接字和其他资源多路复用I / O访问，运行网络客户端和服务器以及其他相关原语的基础结构.

Asyncio并不是一种全新的技术，但它几年后似乎非常趋势 - 特别是在Python社区和2016年3月发布的Python 3.4.
因此，很难让自己与最精彩的软件包保持同步.
在这里找到一些*很棒的*包，如果你错过了一个，我们指望你 [create an Issue or a Pull Request](https://github.com/timofurrer/awesome-asyncio/blob/master/CONTRIBUTING.md) 提出你的建议.




***

## Web Frameworks

*用于构建Web应用程序的库.*

* [aiohttp](https://github.com/KeepSafe/aiohttp) - 用于asyncio的Http客户端/服务器（PEP-3156）.
* [sanic](https://github.com/channelcat/sanic) -  Python 3.5+ Web服务器，写得快.
* [Quart](https://gitlab.com/pgjones/quart) - 与Flask具有相同API的asyncio Web微框架.
* [Vibora](https://github.com/vibora-io/vibora) - 受Flask启发的高性能Web框架.
* [cirrina](https://github.com/neolynx/cirrina) - 基于aiohttp的Opinionated异步Web框架.
* [autobahn](https://github.com/crossbario/autobahn-python) - 支持asyncio和Twisted的WebSocket和WAMP，适用于客户端和服务器.
* [websockets](https://github.com/aaugustin/websockets/) - 用于在Python中构建WebSocket服务器和客户端的库，重点是正确性和简单性.
* [Tornado](http://www.tornadoweb.org/en/stable/) - 高性能的Web框架和异步网络库.
* [Japronto!](https://github.com/squeaky-pl/japronto) - 基于uvloop和picohttpparser构建的实验性http工具包.
* [Starlette](https://github.com/encode/starlette) - 用于构建高性能服务的轻量级ASGI框架/工具包.
* [uvicorn](https://github.com/encode/uvicorn) - 闪电般快速的ASGI服务器.

## Message Queues

*使用消息队列实现应用程序的库.*

* [aioamqp](https://github.com/Polyconseil/aioamqp) - 使用asyncio实现AMQP.
* [aiozmq](https://github.com/aio-libs/aiozmq) -  Asyncio（pep 3156）与ZeroMQ集成.
* [crossbar](https://github.com/crossbario/crossbar) -  Crossbar.io是分布式和微服务应用程序的网络平台.
* [asyncio-nats](https://github.com/nats-io/asyncio-nats) -  NATS消息传递系统的客户端.
* [aiokafka](https://github.com/aio-libs/aiokafka) -  Apache Kafka的客户端.

## Database Drivers

*图书馆连接数据库.*

* [asyncpg](https://github.com/MagicStack/asyncpg) - 用于Python / asyncio的快速PostgreSQL数据库客户端库.
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) - 具有sqlalchemy核心支持的Asyncpg.
* [aiopg](https://github.com/aio-libs/aiopg/) - 用于访问PostgreSQL数据库的库.
* [aiomysql](https://github.com/aio-libs/aiomysql) - 用于访问MySQL数据库的库
* [aioodbc](https://github.com/aio-libs/aioodbc) - 用于访问ODBC数据库的库.
* [motor](https://github.com/mongodb/motor) -  MongoDB的异步Python驱动程序.
* [aioredis](https://github.com/aio-libs/aioredis) - [aio-libs](https://github.com/aio-libs) Redis客户端（PEP 3156）.
* [asyncio-redis](https://github.com/jonathanslenders/asyncio-redis) - 用于Python asyncio的Redis客户端（PEP 3156）.
* [aiocouchdb](https://github.com/aio-libs/aiocouchdb) - 基于aiohttp（asyncio）构建的CouchDB客户端.
* [aioinflux](https://github.com/plugaai/aioinflux) - 基于aiohttp构建的InfluxDB客户端.
* [aioes](https://github.com/aio-libs/aioes) - 用于弹性搜索的Asyncio兼容驱动程序.
* [peewee-async](https://github.com/05bit/peewee-async) - 基于ORM的实现 [peewee](https://github.com/coleifer/peewee) 和aiopg.
* [GINO](https://github.com/fantix/gino) - 是一个基于的轻量级异步Python ORM [SQLAlchemy](https://www.sqlalchemy.org/) 核心，有 [asyncpg](https://github.com/MagicStack/asyncpg) 方言.
* [Tortoise ORM](https://github.com/tortoise/tortoise-orm) - 具有类似Django API的原生多后端ORM和简单的关系管理.

## Networking

*图书馆可在您的网络中进行通信.*

* [AsyncSSH](https://github.com/ronf/asyncssh) - 提供SSHv2协议的异步客户端和服务器实现.
* [aiodns](https://github.com/saghul/aiodns) -  asyncio的简单DNS解析器

## Testing

*用于测试基于asyncio的应用程序的库.*

* [aiomock](https://github.com/nhumrich/aiomock/) - 支持异步方法的python模拟库.
* [asynctest](https://github.com/Martiusweb/asynctest/)   - 增强标准单元测试包，并提供测试功能.  asyncio库
* [pytest-asyncio](https://github.com/pytest-dev/pytest-asyncio) -  Pytest支持asyncio.
* [aresponses](https://github.com/CircleUp/aresponses)   -  Asyncio http嘲笑.  类似于 [responses](https://github.com/getsentry/responses) 图书馆用于 [requests](https://github.com/requests/requests)
* [aioresponses](https://github.com/pnuckowski/aioresponses) - 用于Python aiohttp包中的模拟/伪造Web请求的助手.

## Alternative Loops

*替代asyncio循环实现.*

* [uvloop](https://github.com/MagicStack/uvloop) - 在libuv上快速实现asyncio事件循环.
* [curio](https://github.com/dabeaz/curio) - 协程并发库.

## Misc

*其他令人敬畏的asyncio库.*

* [aiofiles](https://github.com/Tinche/aiofiles/) - 对asyncio的文件支持.
* [aiodebug](https://github.com/qntln/aiodebug) - 用于监视和测试asyncio程序的小型库.
* [aiorun](https://github.com/cjrh/aiorun) - 一个`run（）`函数，它处理启动和正常关闭的所有常用样板.
* [aioserial](https://github.com/changyuheng/aioserial) - 直接替换 [pySerial](https://github.com/pyserial/pyserial).
* [aiozipkin](https://github.com/aio-libs/aiozipkin) - 使用zipkin的asyncio分布式跟踪工具

## Writings

*文档，博客文章和其他关于asyncio的精彩文章.*

* [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) - 异步I / O，事件循环，协同程序和任务.
* [Short well-written intro to asyncio](http://masnun.com/2015/11/13/python-generators-coroutines-native-coroutines-and-async-await.html) -  Generators，Coroutines，Native Coroutines和async / await.
* [Async Through the looking Glass](https://hackernoon.com/async-through-the-looking-glass-d69a0a88b661) - 关于使用asyncio或不使用特定用例的好文章.
* [Asynchronous Python](https://hackernoon.com/asynchronous-python-45df84b82434) - 使用Python简介异步编程.
* [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) - 从基本示例到URL提取的简单介绍异步编程.
* [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) - 使用python-aiohttp发出100万个请求.

## Talks

*记录有关asyncio的精彩演讲.*

* [Topics of Interest (Python Asyncio)](https://youtu.be/ZzfHjytDceU) | [screencast](https://youtu.be/lYe8W04ERnY) | [slides](https://speakerdeck.com/dabeaz/topics-of-interest-async) -  PyCon Brasil 2015主题演讲（David Beazley）.
* [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) | [blog post](http://pgbovine.net/python-async-io-walkthrough.htm) -  8部分代码演练（Philip Guo）.
