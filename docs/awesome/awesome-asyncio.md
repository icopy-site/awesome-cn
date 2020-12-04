<div class="github-widget" data-repo="timofurrer/awesome-asyncio"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome asyncio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精心精选的Python异步框架，库，软件和资源清单.

Python [asyncio](https://docs.python.org/3/library/asyncio.html) 使用Python 3.4引入标准库的Java模块提供了用于使用协程编写单线程并发代码，通过套接字和其他资源对I / O进行多路访问，运行网络客户端和服务器以及其他相关原语的基础结构.

Asyncio并不是真正的崭新技术，但是自几年以来，它似乎一直非常流行，尤其是在Python社区以及2014年3月发布的Python 3.4中.
因此，要使自己与最新的最棒的软件包保持同步是非常困难的.
在这里找到一些“很棒的”软件包，如果您缺少其中的一个，我们相信您可以 [create an Issue or a Pull Request](https://github.com/timofurrer/awesome-asyncio/blob/master/CONTRIBUTING.md) 与您的建议.




***

## Web Frameworks

*用于构建Web应用程序的库.*

* [aiohttp](https://github.com/KeepSafe/aiohttp) -异步的Http客户端/服务器（PEP-3156）.
* [sanic](https://github.com/channelcat/sanic) -编写速度更快的Python 3.5+网络服务器.
* [Quart](https://gitlab.com/pgjones/quart) -具有与Flask相同的API的asyncio网络微框架.
* [Vibora](https://github.com/vibora-io/vibora) -受Flask启发的高性能Web框架.
* [cirrina](https://github.com/neolynx/cirrina) -基于aiohttp的自以为是的异步Web框架.
* [autobahn](https://github.com/crossbario/autobahn-python) -用于客户端和服务器的WebSocket和WAMP支持asyncio和Twisted.
* [websockets](https://github.com/aaugustin/websockets/) -一个库，用于在Python中构建WebSocket服务器和客户端，重点在于正确性和简单性.
* [Tornado](http://www.tornadoweb.org/en/stable/) -Performance Web框架和异步网络库.
* [Japronto!](https://github.com/squeaky-pl/japronto) -基于uvloop和picohttpparser构建的实验性HTTP工具包.
* [Starlette](https://github.com/encode/starlette) -用于构建高性能服务的轻量级ASGI框架/工具包.
* [uvicorn](https://github.com/encode/uvicorn) -快如闪电的ASGI服务器.
* [FastAPI](https://github.com/tiangolo/fastapi)  -基于类型提示的非常高性能的Python 3.6+ API框架. 由Starlette和Pydantic提供支持.

## Message Queues

*使用消息队列实现应用程序的库.*

* [aioamqp](https://github.com/Polyconseil/aioamqp) -使用asyncio实现AMQP.
* [pyzmq](https://github.com/zeromq/pyzmq) -ZeroMQ的Python绑定.
* [aiozmq](https://github.com/aio-libs/aiozmq) -与ZeroMQ的替代性Asyncio集成.
* [crossbar](https://github.com/crossbario/crossbar) -Crossbar.io是用于分布式和微服务应用程序的网络平台.
* [asyncio-nats](https://github.com/nats-io/asyncio-nats) - Client for the NATS messaging system.
* [aiokafka](https://github.com/aio-libs/aiokafka) -Apache Kafka的客户端.

## Database Drivers

*用于连接数据库的库.*

* [asyncpg](https://github.com/MagicStack/asyncpg) -适用于Python / asyncio的快速PostgreSQL数据库客户端库.
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) -具有sqlalchemy核心支持的Asyncpg.
* [aiopg](https://github.com/aio-libs/aiopg/) -用于访问PostgreSQL数据库的库.
* [aiomysql](https://github.com/aio-libs/aiomysql) -用于访问MySQL数据库的库
* [aioodbc](https://github.com/aio-libs/aioodbc) -用于访问ODBC数据库的库.
* [motor](https://github.com/mongodb/motor) -MongoDB的异步Python驱动程序.
* [aioredis](https://github.com/aio-libs/aioredis) - [aio-libs](https://github.com/aio-libs) Redis客户端（PEP 3156）.
* [asyncio-redis](https://github.com/jonathanslenders/asyncio-redis) -用于Python异步的Redis客户端（PEP 3156）.
* [aiocouchdb](https://github.com/aio-libs/aiocouchdb) -建立在aiohttp（asyncio）之上的CouchDB客户端.
* [aioinflux](https://github.com/plugaai/aioinflux) -在aiohttp之上构建的InfluxDB客户端.
* [aioes](https://github.com/aio-libs/aioes) -用于Elasticsearch的Asyncio兼容驱动程序.
* [peewee-async](https://github.com/05bit/peewee-async) -基于ORM的实现 [peewee](https://github.com/coleifer/peewee) 和aiopg.
* [GINO](https://github.com/fantix/gino) -是基于的轻量级异步Python ORM [SQLAlchemy](https://www.sqlalchemy.org/) 核心， [asyncpg](https://github.com/MagicStack/asyncpg) 方言.
* [Tortoise ORM](https://github.com/tortoise/tortoise-orm) -具有类似Django的API和易于进行的关系管理的本机多后端ORM.
* [Databases](https://github.com/encode/databases) -对SQLAlchemy核心的异步数据库访问，并支持PostgreSQL，MySQL和SQLite.

## Networking

*在您的网络中进行通信的图书馆.*

* [AsyncSSH](https://github.com/ronf/asyncssh) -提供SSHv2协议的异步客户端和服务器实现.
* [aiodns](https://github.com/saghul/aiodns) -用于异步的简单DNS解析器
* [httpx](https://github.com/encode/httpx) -适用于Python 3的异步HTTP客户端 [requests](https://github.com/psf/requests) 兼容的API.

## GraphQL

*用于构建GraphQL服务器的库.

* [Ariadne](https://ariadnegraphql.org) -Schema-first Python库，用于实现GraphQL服务器.
* [Tartiflette](https://tartiflette.io/) -建立在`libgraphqlparser`之上的模式优先的Python 3.6+ GraphQL引擎.

## Testing

*用于测试基于异步应用程序的库.

* [aiomock](https://github.com/nhumrich/aiomock/) -支持异步方法的python模拟库.
* [asynctest](https://github.com/Martiusweb/asynctest/)  -通过测试功能增强标准的单元测试包. 异步库
* [pytest-asyncio](https://github.com/pytest-dev/pytest-asyncio) -异步的Pytest支持.
* [aresponses](https://github.com/CircleUp/aresponses)  -Asyncio http模拟. 类似于 [responses](https://github.com/getsentry/responses) 用于的库 [requests](https://github.com/requests/requests)
* [aioresponses](https://github.com/pnuckowski/aioresponses) -Python aiohttp包中的模拟/伪造Web请求的帮助程序.

## Alternative Loops

*异步循环的替代实现.

* [uvloop](https://github.com/MagicStack/uvloop) -在libuv上超快速实现asyncio事件循环.

## Misc

*其他很棒的asyncio库.

* [aiocache](https://github.com/argaen/aiocache) -用于不同后端的缓存管理器.
* [aiofiles](https://github.com/Tinche/aiofiles/) -对asyncio的文件支持.
* [aiodebug](https://github.com/qntln/aiodebug) -一个用于监视和测试异步程序的小型库.
* [aiorun](https://github.com/cjrh/aiorun) -一个run（）函数，用于处理启动和正常关闭的所有常用样板.
* [aioserial](https://github.com/changyuheng/aioserial) -的替代品 [pySerial](https://github.com/pyserial/pyserial).
* [aiozipkin](https://github.com/aio-libs/aiozipkin) -带有zipkin的asyncio的分布式跟踪工具
* [asgiref](https://github.com/django/asgiref) -从ASGI到WSGI集成的后端utils，包括sync_to_async和async_to_sync函数包装.
* [ruia](https://github.com/howie6879/ruia) -基于asyncio的异步Web抓取微框架.
## Writings

*有关asyncio的文档，博客文章和其他精彩文章.*

* [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) -异步I / O，事件循环，协程和任务.
* [Short well-written intro to asyncio](http://masnun.com/2015/11/13/python-generators-coroutines-native-coroutines-and-async-await.html) -生成器，协程，本机协程和异步/等待.
* [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) -从基本示例到URL提取，对异步编程进行了详尽的介绍.
* [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) -使用python-aiohttp发出1百万个请求.
* [ASGI (Asynchronous Server Gateway Interface)](https://asgi.readthedocs.io/en/latest/) -WSGI的精神继承者，旨在在具有异步功能的Python Web服务器，框架和应用程序之间提供标准接口.
* [First Principles Introduction to Asyncio](https://hackernoon.com/a-simple-introduction-to-pythons-asyncio-595d9c9ecf8c) -asyncio内部工作原理的第一流原则.
* [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) -本教程介绍了如何使用测试驱动开发（TDD）使用FastAPI开发和测试异步API.

## Talks

*有关asyncio的精彩演讲的记录.

* [Topics of Interest (Python Asyncio)](https://youtu.be/ZzfHjytDceU) | [screencast](https://youtu.be/lYe8W04ERnY) | [slides](https://speakerdeck.com/dabeaz/topics-of-interest-async) -PyCon Brasil 2015主旨演讲（David Beazley）.
* [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) | [blog post](http://pgbovine.net/python-async-io-walkthrough.htm) -由8部分组成的代码演练（Philip Guo）.
* [Async/await in Python 3.5 and why it is awesome](https://www.youtube.com/watch?v=m28fiN9y_r8&t=132s) -EuroPython 2016（Yury Selivanov）.
* [Fear and Awaiting in Async: A Savage Journey to the Heart of the Coroutine Dream](https://www.youtube.com/watch?v=E-1Y4kSsAFc) | [screencast](https://www.youtube.com/watch?v=Bm96RqNGbGo) -PyOhio 2016主旨演讲（David Beazley）.
* [Asynchronous Python for the Complete Beginner](https://www.youtube.com/watch?v=iG6fr81xHKA) | [slides](https://speakerdeck.com/pycon2017/miguel-grinberg-asynchronous-python-for-the-complete-beginner) -PyCon 2017（Miguel Grinberg）.

## Alternatives to asyncio

*用Python进行异步编程的替代方法，其中一些尝试支持与`asyncio`的兼容性，而另一些则根本不兼容.*

* [curio](https://github.com/dabeaz/curio) -协程并发库.
  * [Curio-Asyncio Bridge](https://github.com/dabeaz/curio/issues/190) -基本的古董-&gt;异步协程桥
* [trio](https://github.com/python-trio/trio) -适用于人类和蛇人的Pythonic异步I / O.
  * [trio-asyncio](https://github.com/python-trio/trio-asyncio) -在Trio之上重新实现asyncio主循环
