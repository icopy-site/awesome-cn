<div class="github-widget" data-repo="neueda/awesome-neo4j"></div>
真棒Neo4j
==============
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/neueda/awesome-neo4j.svg?branch=master )](https://travis-ci.org/neueda/awesome-neo4j)

精彩的精选列表 [Neo4j](https://neo4j.com/) 资源.  
灵感来自GitHub上的&#39;awesome- *&#39;趋势.

目标是建立一个由知名资源组成的分类社区驱动集合.  
欢迎分享，建议和贡献！

谢谢大家 [contributors](https://github.com/Neueda/awesome-neo4j/graphs/contributors).

由...维护 [Neueda R&D](http://labs.neueda.com/).

目录
=================


由...制作 [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

## Basics

- [Official documentation](https://neo4j.com/docs/)
- [Cypher Refcard](https://neo4j.com/docs/cypher-refcard/current/)
- [Developer resources](https://neo4j.com/developer/get-started/)
- [Gists](http://graphgist.neo4j.com/)   - 使用Neo4j GraphGists，您可以在简单的文本文件中描述和建模您的域，并在任何浏览器中将其呈现为丰富的交互式页面.  完美记录特定域，用例，问题或图形问题.
- [Neo4j Examples](https://github.com/neo4j-examples) -  Neo4j和库使用的示例.

## Related project

- [openCypher](http://www.opencypher.org/) -  openCypher是一个开源项目，旨在实现业界最广泛采用的图形查询语言的新公共实现：Cypher.
- [Bolt Protocol](https://boltprotocol.org) -  Bolt网络协议是一种高效，轻量级的客户端 - 服务器协议，专为数据库应用程序而设计.

## Connectors

## Bolt

- [neo4j-java-driver](https://github.com/neo4j/neo4j-java-driver) -  Neo4j二进制协议的Java驱动程序.
- [neo4j-python-driver](https://github.com/neo4j/neo4j-python-driver) -  Neo4j二进制协议的Python驱动程序.
- [neo4j-javascript-driver](https://github.com/neo4j/neo4j-javascript-driver) -  Neo4j二进制协议的JavaScript驱动程序.
- [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) -  .Net驱动程序Neo4j（Bolt）.
- [neo4j-bolt-php](https://github.com/graphaware/neo4j-bolt-php) - 用于Neo4j二进制协议的PHP驱动程序.
- [libneo4j-client](https://github.com/cleishm/libneo4j-client)   -  libneo4j-client是一个用C语言编写的Neo4j客户端库.  它不是一个完整的驱动程序，而是作为可以构建各种语言的基本工具和驱动程序的基础.  libneo4j-client负责处理与Neo4j服务器建立会话的所有细节，发送用于评估的语句以及检索结果.
- [neo4j-spark-connector](https://github.com/neo4j-contrib/neo4j-spark-connector) -  Neo4j-Spark-Connector基于Neo4j 3.0的Bolt协议
- [neo4j-elixir-driver](https://github.com/mschae/boltex) - 用于neo4j螺栓协议的Elixir驱动程序
- [neo4j-elixir-wrapper](https://github.com/florinpatrascu/bolt_sips)   - 用于Elixir的Neo4j驱动程序，包含Bolt协议.  Boltex的叉子.

## REST API

### Java

- [neo4j-ogm](https://github.com/neo4j/neo4j-ogm) -  Neo4j的对象图映射库.
- [spring-data-neo4j](https://github.com/spring-projects/spring-data-neo4j) - 在使用neo4j图形数据库时，提供支持以提高开发人员的Java生产力.
- [neo4j-jdbc](https://github.com/neo4j-contrib/neo4j-jdbc) -  Neo4j JDBC驱动程序.
- [jcypher](https://github.com/Wolfgang-Schuetzelhofer/jcypher) -  Java在多个抽象级别访问Neo4J图形数据库.

### Ruby

- [neo4jrb](https://github.com/neo4jrb/neo4j) - 用于Ruby的Neo4j图形数据库的活动模型包装器.
- [neography](https://github.com/maxdemarzi/neography) -  Neo4j Rest API的瘦Ruby包装器.

### Python

- [py2neo](https://github.com/nigelsmall/py2neo) -  Py2neo是一个综合工具包，用于在Python应用程序或命令行中使用Neo4j.
- [neomodel](https://github.com/neo4j-contrib/neomodel) - 用于neo4j图形数据库的对象图形映射器（OGM），构建在令人敬畏的py2neo上.

### PHP

- [Neo4j-PHP-OGM](https://github.com/graphaware/neo4j-php-ogm) -  Neo4j的Doctrine样式Object Graph Mapper
- [neo4jphp](https://github.com/jadell/neo4jphp) -  Neo4j REST接口的PHP包装器.
- [NeoEloquent](https://github.com/Vinelab/NeoEloquent) - 一个Neo4j ORM  - 基于Eloquent.
- [neo4j-php-client](https://github.com/graphaware/neo4j-php-client/tree/4.0) - 利用Http和Bolt协议的Neo4j的PHP客户端.
- [Spider](https://github.com/spider/spider) - 一个简单，灵活，美观的图形数据抽象的PHP.

### Other

- [node-neo4j](https://github.com/thingdom/node-neo4j) -  Node的REST API客户端.
- [Neo4jClient](https://github.com/Readify/Neo4jClient) -  .NET客户端绑定.
- [neoism](https://github.com/jmcvetta/neoism) - 客户端Golang.
- [neocons](https://github.com/michaelklishin/neocons) -  REST API的功能丰富的惯用Clojure客户端.
- [RNeo4j](https://github.com/nicolewhite/RNeo4j) -  R.的驱动程序
- [AnormCypher](https://github.com/AnormCypher/AnormCypher) -  Play框架中基于Anorm的Scala库.

## Cloud

- [GrapheneDB](https://www.graphenedb.com/) - 世界上第一个完全管理
Neo4j图数据库.
- [GraphStory](https://www.graphstory.com/) -  Neo4j企业云提供商

## Packages

- [Debian Packages](http://debian.neo4j.org/)
- [Yum Repo](http://yum.neo4j.org/stable/)

## Docker

- [docker-neo4j](https://github.com/neo4j/docker-neo4j) -  Neo4j图数据库的Docker镜像.
- [docker-neo4j-cluster](https://github.com/ekino/docker-neo4j-cluster) - 立即启动和运行Neo4j集群.

## Full-text search

- [GraphAware Neo4j Elasticsearch Integration](https://github.com/graphaware/neo4j-to-elasticsearch) - 用于将Neo4j与Elasticsearch集成的GraphAware框架模块.
- [GraphAware Graph-Aided Search](https://github.com/graphaware/graph-aided-search) -  Elasticsearch插件，为个性化搜索提供Neo4j集成.
- [neo4j-elasticsearch](https://github.com/neo4j-contrib/neo4j-elasticsearch) -  Neo4j ElasticSearch集成.

## Import

- [GraphAware Neo4j Importer](https://github.com/graphaware/neo4j-importer) - 用于复杂，业务逻辑繁重的高性能Neo4j的Java导入程序框架直接从SQL数据库，CSV文件等导入.
- [neo4j-csv-firehose](https://github.com/sarmbruster/neo4j-csv-firehose) - 启用Neo4j的`LOAD CSV` Cypher命令以从其他数据源加载.
- [neo4j-rdbms-import](https://github.com/jexp/neo4j-rdbms-import) -  Neo4j关系数据库的自动导入程序.
- [Doc manager for Neo4j](https://github.com/neo4j-contrib/neo4j_doc_manager) -  Neo4j Doc Manager采用MongoDB文档，通过使用Mongo Connector指定的格式在Neo4j图形结构中提供它们，可以轻松查询它们之间的关系.
- [neoloadcsvskelgen](https://github.com/wadael/neoloadcsvskelgen)   - 将从非常少的输入（文件名，分隔符，提示）输出LOAD CSV Cypher代码的框架.  节省时间，避免拼写错误. 

## Benchmarking

- [neoprofiler](https://github.com/moxious/neoprofiler) -  Neo4J数据库分析实用程序.

## Extensions

- [GraphAware Neo4j UUID](https://github.com/graphaware/neo4j-uuid) -  GraphAware运行时模块，它透明地为图中的所有节点分配UUID.
- [GraphAware Neo4j ChangeFeed](https://github.com/graphaware/neo4j-changefeed) -  GraphAware框架运行时模块，允许用户找出在图表上执行的最新更改.
- [GraphAware Neo4j TimeTree](https://github.com/graphaware/neo4j-timetree) - 用于在Neo4j中使用时间表示树的Java和REST API.
- [GraphAware Neo4j Recommendation Engine](https://github.com/graphaware/neo4j-reco) - 基于Neo4j的推荐引擎模块，具有实时和预先计算的推荐.
- [GraphAware Neo4j Algorithms](https://github.com/graphaware/neo4j-algorithms) -  Neo4j的自定义图算法，具有自己的Java和REST API.
- [GraphAware Neo4j Warmup](https://github.com/graphaware/neo4j-warmup) - 简单的库，通过单个REST调用来加热Neo4j缓存.
- [GraphAware Neo4j RestTest](https://github.com/graphaware/neo4j-resttest) -  GraphAware RestTest是一个简单的库，用于测试与独立服务器模式下运行的Neo4j对话的代码.
- [GraphAware Neo4j Expire](https://github.com/graphaware/neo4j-expire) -  GraphAware Expire是一个简单的库，可以在数据库到期或生存时间（TTL）时自动删除数据库中的节点和关系.
- [Spatial](https://github.com/neo4j-contrib/spatial) -  Neo4j Spatial是Neo4j的实用程序库，可以促进数据的空间操作.
- [Graphify](https://github.com/Graphify/graphify) -  Graphify是一个Neo4j非托管扩展，用于使用基于图形的分层模式识别进行文档和文本分类.
- [neo4j-tx-participation](https://github.com/jexp/neo4j-tx-participation) - 这是一个Neo4j服务器扩展，使Neo4j REST-API参与由事务性Cypher端点启动的事务.

## Stored Procedures

- [Apoc : Awesome Procedures on Cypher](https://github.com/neo4j-contrib/neo4j-apoc-procedures) - 收集Neo4j 3.x的有用程序
- [Graphgen](https://github.com/graphaware/neo4j-graphgen-procedure) - 使用Cypher轻松生成测试数据的Neo4j程序

## Development

- [Maven repositories](https://m2.neo4j.org/index.html) -  Neo4j Maven存储库（发布，快照）.
- [GraphAware Neo4j Framework](https://github.com/graphaware/neo4j-framework)-  GraphAware Framework通过提供一个平台来加速Neo4j的开发，该平台用于构建有用的通用功能，特定于域的功能，分析功能，（迭代）图算法等.
- [cypher-dsl](https://github.com/neo4j-contrib/cypher-dsl) - 用于Cypher查询语言的Java DSL和可选的Query DSL模式.
- [Liquigraph](https://github.com/liquigraph/liquigraph) - 数据库迁移管理工具，基于Liquibase的工作原理.
- [blueprints](https://github.com/tinkerpop/blueprints)   -  Blueprints是属性图数据模型的接口，实现，ouplementations和测试套件的集合.  蓝图类似于JDBC，但对于图形数据库.
- [structr](https://github.com/structr/structr) - 基于Neo4j的图形应用平台.
- [Reco4PHP](https://github.com/graphaware/reco4php) - 基于Neo4j的PHP推荐引擎框架.

## Editors

- [jetbrains-plugin-graph-database-support](https://github.com/neueda/jetbrains-plugin-graph-database-support) - 图形数据库支持Jetbrains系列IDE.
- [cypher-vim-syntax](https://github.com/neo4j-contrib/cypher-vim-syntax) -  Cypher非常基本的Vim语法.

## Shell

- [cycli](https://github.com/nicolewhite/cycli) -  Cypher的命令行接口.
- [neo4j-shell-tools](https://github.com/jexp/neo4j-shell-tools) - A bunch of import/export tools for the neo4j-shell.

## Visualization

- [neoclipse](https://github.com/neo4j-contrib/neoclipse) -  Neoclipse是一个查看，编辑和浏览Neo4j数据库的工具.
- [Gephi](https://github.com/gephi/gephi) -  Gephi是一个屡获殊荣的开源平台，用于可视化和操作大型图形.
- [Linkurious](https://linkurio.us/) -  Linkurious通过简单的基于Web的界面帮助搜索和可视化您的图形数据.
- [yFiles for HTML](https://www.yworks.com/products/yfiles-for-html) -  yFiles是一个商业通用图形可视化编程库 [a demo to visualize your neo4j databases in JavaScript](http://live.yworks.com/demos/#neo4j) .  它也是基础 [free neo4j Graph Explorer app](https://www.yworks.com/neo4j-explorer/).

## Tools

- [Graphgen](http://graphgen.graphaware.com) - 基于Cypher DSL的图形生成引擎.
- [store-utils](https://github.com/jexp/store-utils) - 用于压缩，复制，修复，分析Neo4j商店的实用程序.
- [ineo](https://github.com/cohesivestack/ineo)- 一个简单但有用的Neo4j实例管理器.
- [yFiles neo4j Graph Explorer](https://www.yworks.com/blog/neo4j-node-design) - 一个简单的免费在线工具，可视化您的图形数据和数据库模式.

## Learn

- [Getting Started with Neo4j](https://neo4j.com/graphacademy/online-training/getting-started-graph-databases-using-neo4j/)
- [Neo4j in Production](https://neo4j.com/graphacademy/online-training/neo4j-production/)
- [Neo4j Koans](https://github.com/jimwebber/neo4j-tutorial) - 用于Neo4j的Java的koan风格教程.

## Certification

- [Neo4j Certification](https://neo4j.com/graphacademy/neo4j-certification/) - 成为Neo4j认证专家.

## Miscellaneous

- [Neo4j's Idea board](https://trello.com/b/2zFtvDnV/public-idea-board)
- [Hardware Sizing Calculator](https://neo4j.com/hardware-sizing-calculator/)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Neueda R&D](https://github.com/Neueda) 已放弃对此作品的所有版权及相关或相邻权利.
