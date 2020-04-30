<div class="github-widget" data-repo="mohataher/awesome-tinkerpop"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome TinkerPop [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

![alt tag](https://raw.githubusercontent.com/mohataher/awesome-tinkerpop/master/tinkerpop-splash.png)


Github上只有很棒的TinkerPop库的精选列表.

&gt; Apache TinkerPop™是用于图形数据库（OLTP）和图形分析系统（OLAP）的图形计算框架.


### <A NAME="tinkerpop3"></A>TinkerPop3 Libraries
#### <A NAME="tinkerpop3-implementations"></A>Implementations
* [TinkerPop3 implementation](https://github.com/apache/tinkerpop) -Apache TinkerPop的镜像.
* [sqlg](https://github.com/pietermartin/sqlg) -Sqlg是RDBMS上TinkerPop3的实现.
* [blazegraph](https://github.com/blazegraph/database) -TinkerPop3 [implementation](https://github.com/blazegraph/tinkerpop3)  用于Blaze Graph；  高性能图形数据库.
* [tinkergraph-js](https://github.com/jbmusso/tinkergraph-js) -TinkerPop的TinkerGraph内存图形数据库的纯JavaScript实现.
* [gremlin-javascript](https://github.com/jbmusso/gremlin-javascript) -TinkerPop3 Gremlin服务器的JavaScript图形数据库客户端.
* [Elastic Gremlin](https://github.com/rmagen/elastic-gremlin) -在Elasticsearch后端实施TinkerPop3.
* [Hadoop (Giraph)](http://tinkerpop.apache.org/docs/current/reference/#giraphgraphcomputer) -使用Giraph的OLAP图形处理器.
* [Hadoop (Spark)](http://tinkerpop.apache.org/docs/current/reference/#sparkgraphcomputer) -使用Spark的OLAP图形处理器.
* [IBM Graph](https://console.ng.bluemix.net/catalog/services/ibm-graph/) -OLTP图形数据库即服务.
* [Neo4j](http://tinkerpop.apache.org/docs/currentg/#neo4j-gremlin) -OLTP图形数据库.
* [Stardog](http://stardog.com/) -具有OLTP和OLAP支持的RDF图形数据库.
* [TinkerGraph](http://tinkerpop.apache.org/docs/current/reference/#tinkergraph-gremlin) -内存中的OLTP和OLAP参考实现.
* [Unipop](https://github.com/rmagen/unipop) -OLTP Elasticsearch和JDBC支持的图.
* [DuctileDB](https://github.com/PureSolTechnologies/DuctileDB) -Ductile DB是基于Hadoop / HBase的图形数据库，具有大量功能.
* [hgraphdb](https://github.com/rayokota/hgraphdb) -HBase作为TinkerPop图形数据库.
* [JanusGraph](https://github.com/JanusGraph/janusgraph) -JanusGraph：开源的分布式图形数据库http://janusgraph.org 
* [JanusGraph for DynamoDB (Amazon)](https://github.com/awslabs/dynamodb-janusgraph-storage-backend) -JanusGraph的Amazon DynamoDB存储后端.
* [orientdb-gremlin](https://github.com/orientechnologies/orientdb-gremlin) -针对OrientDB的TinkerPop3图形结构实现.


#### <A NAME="wrappers"></A>Wrappers/Clients
##### C# .NET
*   [Teva Gremlin](https://www.nuget.org/packages/Teva.Common.Data.Gremlin/) (.NET - C#) - A Gremlin Server driver for .NET.

##### Clojure
* [ogre](https://github.com/clojurewerkz/ogre) -Clojure库，用于查询TinkerPop图.
* [scalajs-gremlin-client](https://github.com/viagraphs/scalajs-gremlin-client) （scala）-具有临时可扩展，反应式，基于类的API的Gremlin-Server客户端.

##### Go
* [go-gremlin](https://github.com/go-gremlin/gremlin) -用于TinkerPop3 Gremlin Server的图形数据库客户端.
* [Gremgo](https://github.com/qasaur/gremgo) -TinkerPop图形数据库堆栈的快速，高效且易于使用的Go客户端.
* [grammes](https://github.com/northwesternmutual/grammes) -Go软件包，用于使用Gremlin与Apache TinkerPop™Graph计算框架进行通信.

##### Haskell
* [greskell-websocket](https://github.com/debug-ito/greskell) -TinkerPop3 Gremlin服务器的Haskell客户端.

##### Java
* [gremlin-driver](http://tinkerpop.apache.org/docs/current/reference/#connecting-via-java) （java）-用于Java的Gremlin服务器驱动程序.
* [neo4j-tinkerpop-api](https://github.com/neo4j-contrib/neo4j-tinkerpop-api) -TinkerPop3的Apache许可Neo4j API.
* [neo4j-gremlin-bolt](https://github.com/SteelBridgeLabs/neo4j-gremlin-bolt) -允许通过BOLT协议在neo4j服务器上使用Apache Tinkerpop Java API.
* [Ferma](https://github.com/Syncleus/Ferma) -TinkerPop图形堆栈的ORM / OGM.

##### Javascript
* [ts-tinkerpop](https://github.com/RedSeal-co/ts-tinkerpop) -通过Typescript中的node-java API使用TinkerPop3的实用程序.
* [gremlin-javascript](https://github.com/jbmusso/gremlin-javascript) （js）-用于JavaScript的Gremlin服务器驱动程序.

##### PHP
* [gremlin-php](https://github.com/PommeVerte/gremlin-php)  -与TinkerPop3兼容的gremlin-server php驱动程序.  它将允许您连接到gremlin服务器及其后端（Neo4J，Titan等）.

##### Python
* [Mogwai](https://github.com/platinummonkey/mogwai) -适用于Python的TinkerPop3图形数据库库.
* [python-gremlin-rest](https://github.com/windj007/python-gremlin-rest) -Gremlin服务器的基于REST的客户端.
* [gremlinclient](https://github.com/davebshow/gremlinclient) -Gremlin Server的异步Python 2/3客户端，允许灵活的协程语法-Trollius，Tornado，Asyncio.
* [aiogremlin](https://github.com/davebshow/aiogremlin) （python）-基于asyncio和aiohttp的Python 3库，该库使用websocket与Gremlin Server通信.
* [gremlinrestclient](http://gremlinrestclient.readthedocs.org/en/latest/) （python）-使用HTTP通过REST与Gremlin Server通信的Python 2/3库.
* [goblin](https://github.com/ZEROFAIL/goblin) -TinkerPop3 Gremlin服务器的OGM.
* [goblin 3.5](https://github.com/davebshow/goblin) -TinkerPop 3 OGM Goblin的Python 3.5重写.

##### Reactive
* [reactive-gremlin](https://github.com/coreyauger/reactive-gremlin) （scala）-Akka HTTP Websocket连接器.

##### Scala
* [Gremlin Scala](https://github.com/mpollmeier/gremlin-scala) -Apache TinkerPop3 Graph DSL的Scala包装器.
* [blueprints-scala](https://github.com/anvie/blueprints-scala) -Tinkerpop蓝图Scala.

#### <A NAME="qlang"></A>Query Languages
* [gremlin-py](https://github.com/emehrkay/gremlinpy) -编写可发送到Gremlin Server的纯Python Gremlin.
* [gremlin-scala](https://github.com/mpollmeier/gremlin-scala) -TinkerPop3的Scala语言包装.
* [gremlin-template-string](https://github.com/jbmusso/gremlin-template-string) -Javascript Gremlin语言生成器.
* [ipython-gremlin](https://github.com/davebshow/ipython-gremlin) -IPython和Jupyter中的Gremlin.
* [ogre](http://ogre.clojurewerkz.org/) -TinkerPop3的Clojure语言包装器.
* [Peapod](https://github.com/bayofmany/peapod) -Tinkerpop3图形堆栈的新对象图形包装器.
* [sparql-gremlin](https://github.com/dkuppitz/sparql-gremlin) -SPARQL到Gremlin遍历编译器.
* [sql-gremlin](https://github.com/twilmes/sql-gremlin) -SQL到Gremlin遍历编译器.
* [greskell](https://github.com/debug-ito/greskell) -用于Gremlin图查询语言的Haskell绑定
* [Cypher for Gremlin](https://github.com/opencypher/cypher-for-gremlin) -Cypher for Gremlin向任何Gremlin图形数据库添加了Cypher支持.

### <A NAME="tinkerpop2"></A>TinkerPop 2 Libraries
* [Ferma](https://github.com/Syncleus/Ferma) -TinkerPop图形堆栈的ORM / OGM.
* [Frames](https://github.com/tinkerpop/frames) -图形框架对象.
* [Archimedes](https://github.com/clojurewerkz/archimedes) -用于蓝图的Clojure库（TinkerPop图形堆栈的一部分）.
* [AccumuloGraph](https://github.com/JHUAPL/AccumuloGraph) -使用Accumulo实现TinkerPop蓝图.
* [Frontenac](https://github.com/Loupi/Frontenac) -TinkerPop堆栈的.NET端口.
* [Mogwai](https://github.com/platinummonkey/mogwai) -适用于Python的TinkerPop 2图形数据库库.
* [spring-data-gremlin](https://github.com/gjrwebber/spring-data-gremlin)  -Spring数据gremlin使其更易于实现基于图的存储库.  该模块扩展了Spring Data，以支持任何可能实现TinkerPop Blueprints 2.x API的Graph数据库.
* [blueprints-scala](https://github.com/anvie/blueprints-scala) -TinkerPop蓝图Scala.

## <A NAME="communites"></A>Communities
* [Gremlin-users](https://groups.google.com/forum/#!forum/gremlin-users) -Gremlin用户的邮件列表.
* [Stack Overflow](http://stackoverflow.com/questions/tagged/tinkerpop3) -堆栈溢出有一个相对活跃的社区.
* [TinkerPop-dev](http://mail-archives.apache.org/mod_mbox/incubator-tinkerpop-dev/) -TP3开发人员的邮件列表.

## <A NAME="people-to-follow"></A>People to Follow 
* [Marko Rodriguez](https://markorodriguez.com/) -TinkerPop和Aurelius的创始人.
* [Stephen Mallette](https://twitter.com/spmallette?lang=en-gb) -Gremlin，TinkerPop和Titan DB的高级开发人员.
* [Daniel Kuppitz](https://about.me/daniel.kuppitz) -Gremlin的主要开发人员之一.
* [Jason Plurad](https://github.com/pluradj)  -IBM高级开发人员.  TinkerPop提交者，在社区中活跃.

## <A NAME="tutorials-and-resources"></A>Tutorials and Resources
* [Introduction to Gremlin](http://tinkerpop.apache.org/gremlin.html) -Gremlin语言的官方介绍.
* [Datastax Introduction](https://academy.datastax.com/resources/getting-started-tinkerpop-and-gremlin) -Datastax提供给Gremlin和TinkerPop3的教程.
* [TinkerPop Book](http://www.tinkerpopbook.com/)  -关于Tinkeprop的承诺已久的书，但直到现在都没有兑现.  您可以罐装直到发出通知.
* [Linux Foundation Presentation](http://events.linuxfoundation.org/sites/events/files/slides/ApacheCon2015TinkerPop3.pdf) -David Robinson在IBM的Apache TinkerPop3上由Linux Foundation提供的演示文稿.
* [Getting Started with TinkerPop](http://tinkerpop.apache.org/docs/current/tutorials/getting-started/) -了解TinkerPop入门和入门的基本知识.
* [The Gremlin Console](http://tinkerpop.apache.org/docs/current/tutorials/the-gremlin-console/) -讨论Gremlin控制台的使用案例和使用模式.
* [Gremlin Recipes](http://tinkerpop.apache.org/docs/3.2.1-SNAPSHOT/recipes/) -常见遍历样式和样式的参考.
* [Gremlin Language Variants](http://tinkerpop.apache.org/docs/3.2.1-SNAPSHOT/tutorials/gremlin-language-variants/) -了解如何将Gremlin嵌入宿主编程语言.
* [SQL2Gremlin](http://sql2gremlin.com/) - Learn Gremlin using typical patterns found when querying data with SQL.
* [Getting Started with Graph Databases](https://academy.datastax.com/demos/getting-started-graph-databases) -将关系数据库与图形数据库进行比较，并将SQL与Gremlin进行比较.
* [Graph](https://github.com/krlawrence/graph) -图形数据库，Gremlin和TinkerPop-教程.


## <A NAME="contributing"></A>How to Contribute
![alt tag](https://raw.githubusercontent.com/mohataher/awesome-tinkerpop/master/awesome-tinkerpop.jpg)

请按照 [guidelines here](https://github.com/mohataher/awesome-tinkerpop/blob/master/contributing.md) .  请确保您的贡献和PR很棒！

## <A NAME="license"></A>License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [@mohataher](https://github.com/mohataher) 已放弃此作品的所有版权以及相关或邻近的权利.
