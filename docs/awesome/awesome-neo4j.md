<div class="github-widget" data-repo="neueda/awesome-neo4j"></div>
很棒的 Neo4j
==============
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/neueda/awesome-neo4j.svg?branch=master )](https://travis-ci.org/neueda/awesome-neo4j)

精选清单 [Neo4j](https://neo4j.com/) 资源.  
灵感来自 GitHub 上的“awesome-*”趋势.

目标是建立一个分类的社区驱动的非常知名的资源集合.  
随时欢迎分享、建议和贡献！

谢谢大家 [contributors](https://github.com/Neueda/awesome-neo4j/graphs/contributors).

维护者 [Neueda R&D](http://labs.neueda.com/).

目录
=================


由...制作 [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

## Basics

- [Official documentation](https://neo4j.com/docs/)
- [Cypher Refcard](https://neo4j.com/docs/cypher-refcard/current/)
- [Developer resources](https://neo4j.com/developer/get-started/)
- [Gists](http://graphgist.neo4j.com/)  - 使用 Neo4j GraphGists，您可以在一个简单的文本文件中描述和建模您的域，并将其呈现为任何浏览器中的丰富的交互式页面. 完美记录特定领域、用例、问题或图形问题.
- [Neo4j Examples](https://github.com/neo4j-examples) - Neo4j 和库使用示例.

## Related project

- [openCypher](http://www.opencypher.org/) - openCypher 是一个开源项目，旨在为业界最广泛采用的图形查询语言 Cypher 带来全新的公共实施.
- [Bolt Protocol](https://boltprotocol.org) - Bolt 网络协议是一种高效、轻量级的客户端-服务器协议，专为数据库应用而设计.

## Connectors

## Bolt

- [neo4j-java-driver](https://github.com/neo4j/neo4j-java-driver) - Neo4j 二进制协议的 Java 驱动程序.
- [neo4j-python-driver](https://github.com/neo4j/neo4j-python-driver) - Neo4j 二进制协议的 Python 驱动程序.
- [neo4j-javascript-driver](https://github.com/neo4j/neo4j-javascript-driver) - Neo4j 二进制协议的 JavaScript 驱动程序.
- [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) - Neo4j (Bolt) 的 .Net 驱动程序.
- [neo4j-bolt-php](https://github.com/graphaware/neo4j-bolt-php) - Neo4j 二进制协议的 PHP 驱动程序.
- [libneo4j-client](https://github.com/cleishm/libneo4j-client)  - libneo4j-client 是用 C 为 Neo4j 编写的客户端库. 它不是作为一个完整的驱动程序，而是作为构建各种语言的基本工具和驱动程序的基础.  libneo4j-client 负责与 Neo4j 服务器建立会话、发送评估语句和检索结果的所有细节.
- [neo4j-spark-connector](https://github.com/neo4j-contrib/neo4j-spark-connector) - Neo4j-Spark-Connector 基于 Neo4j 3.0 的 Bolt 协议
- [neo4j-elixir-driver](https://github.com/mschae/boltex) - 用于 neo4j 螺栓协议的 Elixir 驱动程序
- [neo4j-elixir-wrapper](https://github.com/florinpatrascu/bolt_sips)  - Elixir 的 Neo4j 驱动程序，围绕 Bolt 协议.  Boltex 的叉子.

## REST API

### Java

- [neo4j-ogm](https://github.com/neo4j/neo4j-ogm) - Neo4j 的对象图映射库.
- [spring-data-neo4j](https://github.com/spring-projects/spring-data-neo4j) - 在使用 neo4j 图形数据库时提供支持以提高 Java 开发人员的工作效率.
- [neo4j-jdbc](https://github.com/neo4j-contrib/neo4j-jdbc) - Neo4j JDBC 驱动程序.
- [jcypher](https://github.com/Wolfgang-Schuetzelhofer/jcypher) - 以多个抽象级别对 Neo4J 图形数据库进行 Java 访问.

### Ruby

- [neo4jrb](https://github.com/neo4jrb/neo4j) - 用于 Ruby 的 Neo4j 图形数据库的活动模型包装器.
- [neography](https://github.com/maxdemarzi/neography) - Neo4j Rest API 的薄 Ruby 包装器.

### Python

- [py2neo](https://github.com/nigelsmall/py2neo) - Py2neo 是一个综合工具包，用于从 Python 应用程序或命令行中使用 Neo4j.
- [neomodel](https://github.com/neo4j-contrib/neomodel) - 用于 neo4j 图形数据库的对象图形映射器 (OGM)，建立在很棒的 py2neo 之上.

### PHP

- [Neo4j-PHP-OGM](https://github.com/graphaware/neo4j-php-ogm) - Neo4j 的 Doctrine 风格对象图映射器
- [neo4jphp](https://github.com/jadell/neo4jphp) - Neo4j REST 接口的 PHP 包装器.
- [NeoEloquent](https://github.com/Vinelab/NeoEloquent) - 一个 Neo4j ORM - 基于 Eloquent.
- [neo4j-php-client](https://github.com/graphaware/neo4j-php-client/tree/4.0) - 利用 Http 和 Bolt 协议的 Neo4j PHP 客户端.
- [Spider](https://github.com/spider/spider) - 一个简单、灵活、漂亮的 php 图形数据抽象.

### Other

- [node-neo4j](https://github.com/thingdom/node-neo4j) - 用于 Node.js 的 REST API 客户端.
- [Neo4jClient](https://github.com/Readify/Neo4jClient) - .NET 客户端绑定.
- [neoism](https://github.com/jmcvetta/neoism) - Golang 的客户端.
- [neocons](https://github.com/michaelklishin/neocons) - 用于 REST API 的功能丰富的惯用 Clojure 客户端.
- [RNeo4j](https://github.com/nicolewhite/RNeo4j) - R 的驱动程序.
- [AnormCypher](https://github.com/AnormCypher/AnormCypher) - 基于 Play Framework 中 Anorm 的 Scala 库.

## Cloud

- [GrapheneDB](https://www.graphenedb.com/) - 世界上第一个完全托管
Neo4j 图形数据库.
- [GraphStory](https://www.graphstory.com/) - Neo4j 企业云提供商

## Packages

- [Debian Packages](http://debian.neo4j.org/)
- [Yum Repo](http://yum.neo4j.org/stable/)

## Docker

- [docker-neo4j](https://github.com/neo4j/docker-neo4j) - 用于 Neo4j 图形数据库的 Docker 图像.
- [docker-neo4j-cluster](https://github.com/ekino/docker-neo4j-cluster) - 立即启动并运行 Neo4j 集群.

## Full-text search

- [GraphAware Neo4j Elasticsearch Integration](https://github.com/graphaware/neo4j-to-elasticsearch) - 用于将 Neo4j 与 Elasticsearch 集成的 GraphAware 框架模块.
- [GraphAware Graph-Aided Search](https://github.com/graphaware/graph-aided-search) - 为个性化搜索提供 Neo4j 集成的 Elasticsearch 插件.
- [neo4j-elasticsearch](https://github.com/neo4j-contrib/neo4j-elasticsearch) - Neo4j 弹性搜索集成.

## Import

- [GraphAware Neo4j Importer](https://github.com/graphaware/neo4j-importer) - 用于复杂、业务逻辑繁重的高性能 Neo4j 的 Java 导入器框架，直接从 SQL 数据库、CSV 文件等导入.
- [neo4j-csv-firehose](https://github.com/sarmbruster/neo4j-csv-firehose) - 使 Neo4j 的 `LOAD CSV` Cypher 命令也可以从其他数据源加载.
- [neo4j-rdbms-import](https://github.com/jexp/neo4j-rdbms-import) - 关系数据库到 Neo4j 的自动导入器.
- [Doc manager for Neo4j](https://github.com/neo4j-contrib/neo4j_doc_manager) - Neo4j 文档管理器采用 MongoDB 文档，并按照 Mongo 连接器指定的格式使它们在 Neo4j 图形结构中可用，从而使查询它们之间的关系变得容易.
- [neoloadcsvskelgen](https://github.com/wadael/neoloadcsvskelgen)  - 将从非常少的输入（文件名、分隔符、提示）输出 LOAD CSV Cypher 代码的框架. 节省时间，避免错别字. 

## Benchmarking

- [neoprofiler](https://github.com/moxious/neoprofiler) - Neo4J 数据库分析实用程序.

## Extensions

- [GraphAware Neo4j UUID](https://github.com/graphaware/neo4j-uuid) - GraphAware 运行时模块，它透明地为图中的所有节点分配一个 UUID.
- [GraphAware Neo4j ChangeFeed](https://github.com/graphaware/neo4j-changefeed) - 一个 GraphAware 框架运行时模块，允许用户找出在图形上执行的最新更改.
- [GraphAware Neo4j TimeTree](https://github.com/graphaware/neo4j-timetree) - 用于在 Neo4j 中处理时间表示树的 Java 和 REST API.
- [GraphAware Neo4j Recommendation Engine](https://github.com/graphaware/neo4j-reco) - 基于 Neo4j 的推荐引擎模块，具有实时和预计算的推荐.
- [GraphAware Neo4j Algorithms](https://github.com/graphaware/neo4j-algorithms) - 具有自己的 Java 和 REST API 的 Neo4j 自定义图形算法.
- [GraphAware Neo4j Warmup](https://github.com/graphaware/neo4j-warmup) - 通过单个 REST 调用预热 Neo4j 缓存的简单库.
- [GraphAware Neo4j RestTest](https://github.com/graphaware/neo4j-resttest) - GraphAware RestTest 是一个简单的库，用于测试与在独立服务器模式下运行的 Neo4j 对话的代码.
- [GraphAware Neo4j Expire](https://github.com/graphaware/neo4j-expire) - GraphAware Expire 是一个简单的库，当节点和关系达到到期日期或生存时间 (TTL) 时，它会自动从数据库中删除节点和关系.
- [Spatial](https://github.com/neo4j-contrib/spatial) - Neo4j Spatial 是 Neo4j 的实用程序库，可促进对数据进行空间操作.
- [Graphify](https://github.com/Graphify/graphify) - Graphify 是一个 Neo4j 非托管扩展，用于使用基于图形的分层模式识别对文档和文本进行分类.
- [neo4j-tx-participation](https://github.com/jexp/neo4j-tx-participation) - 这是一个 Neo4j 服务器扩展，使 Neo4j REST-API 参与由事务性 Cypher 端点启动的事务.

## Stored Procedures

- [Apoc : Awesome Procedures on Cypher](https://github.com/neo4j-contrib/neo4j-apoc-procedures) - Neo4j 3.x 的有用程序集合
- [Graphgen](https://github.com/graphaware/neo4j-graphgen-procedure) - 使用 Cypher 轻松生成测试数据的 Neo4j 程序

## Development

- [Maven repositories](https://m2.neo4j.org/index.html) - Neo4j Maven 存储库（发布、快照）.
- [GraphAware Neo4j Framework](https://github.com/graphaware/neo4j-framework)- GraphAware Framework 通过提供一个平台来构建有用的通用和特定领域的功能、分析能力、（迭代）图形算法等，从而加速 Neo4j 的开发.
- [cypher-dsl](https://github.com/neo4j-contrib/cypher-dsl) - 用于 Cypher 查询语言的 Java DSL 和可选的查询 DSL 模式.
- [Liquigraph](https://github.com/liquigraph/liquigraph) - 数据库迁移管理工具，基于 Liquibase 的工作原理.
- [blueprints](https://github.com/tinkerpop/blueprints)  - 蓝图是属性图数据模型的接口、实现、补充和测试套件的集合. 蓝图类似于 JDBC，但适用于图形数据库.
- [structr](https://github.com/structr/structr) - 基于 Neo4j 的图形应用平台.
- [Reco4PHP](https://github.com/graphaware/reco4php) - 基于 Neo4j 的 PHP 推荐引擎框架.

## Editors

- [jetbrains-plugin-graph-database-support](https://github.com/neueda/jetbrains-plugin-graph-database-support) - 图形数据库支持 Jetbrains 系列 IDE.
- [cypher-vim-syntax](https://github.com/neo4j-contrib/cypher-vim-syntax) - Cypher 的非常基本的 Vim 语法.

## Shell

- [cycli](https://github.com/nicolewhite/cycli) - Cypher 的命令行界面.
- [neo4j-shell-tools](https://github.com/jexp/neo4j-shell-tools) - A bunch of import/export tools for the neo4j-shell.

## Visualization

- [neoclipse](https://github.com/neo4j-contrib/neoclipse) - Neoclipse 是一种查看、编辑和探索 Neo4j 数据库的工具.
- [Gephi](https://github.com/gephi/gephi) - Gephi 是一个屡获殊荣的开源平台，用于可视化和操作大型图形.
- [Linkurious](https://linkurio.us/) - Linkurious 通过一个简单的基于 Web 的界面帮助搜索和可视化您的图形数据.
- [yFiles for HTML](https://www.yworks.com/products/yfiles-for-html) - yFiles 是一个商业通用的图形可视化编程库，自带 [a demo to visualize your neo4j databases in JavaScript](http://live.yworks.com/demos/#neo4j) . 这也是基础 [free neo4j Graph Explorer app](https://www.yworks.com/neo4j-explorer/).

## Tools

- [Graphgen](http://graphgen.graphaware.com) - 基于 Cypher DSL 的图形生成引擎.
- [store-utils](https://github.com/jexp/store-utils) - 用于压缩、复制、修复、分析 Neo4j 存储的实用程序.
- [ineo](https://github.com/cohesivestack/ineo)- 一个简单但有用的 Neo4j 实例管理器.
- [yFiles neo4j Graph Explorer](https://www.yworks.com/blog/neo4j-node-design) - 一个简单、免费的在线工具，用于可视化您的图形数据和数据库模式.

## Learn

- [Getting Started with Neo4j](https://neo4j.com/graphacademy/online-training/getting-started-graph-databases-using-neo4j/)
- [Neo4j in Production](https://neo4j.com/graphacademy/online-training/neo4j-production/)
- [Neo4j Koans](https://github.com/jimwebber/neo4j-tutorial) - 用于 Neo4j 的 Java 中的 koan 风格教程.

## Certification

- [Neo4j Certification](https://neo4j.com/graphacademy/neo4j-certification/) - 成为 Neo4j 认证专家.

## Miscellaneous

- [Neo4j's Idea board](https://trello.com/b/2zFtvDnV/public-idea-board)
- [Hardware Sizing Calculator](https://neo4j.com/hardware-sizing-calculator/)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Neueda R&D](https://github.com/Neueda) 已放弃该作品的所有版权和相关或邻接权.
