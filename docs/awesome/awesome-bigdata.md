<div class="github-widget" data-repo="onurakpolat/awesome-bigdata"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Big Data

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

一个很棒的大数据框架、资源和其他很棒的精选列表. 灵感来自 [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [awesome-ruby](https://github.com/Sdogruyol/awesome-ruby), [hadoopecosystemtable](http://hadoopecosystemtable.github.io/) & [big-data](http://usefulstuff.io/big-data/).

随时欢迎您的贡献！


## RDBMS
* [MySQL](https://www.mysql.com/) 世界上最流行的开源数据库.
* [PostgreSQL](https://www.postgresql.org/) 世界上最先进的开源数据库.
* [Oracle Database](http://www.oracle.com/us/corporate/features/database-12c/index.html) - 对象关系数据库管理系统.
* [Teradata](http://www.teradata.com/products-and-services/teradata-database/) - 高性能 MPP 数据仓库平台.

## Frameworks

* [Bistro](https://github.com/facebook/bistro)  - 用于批处理和流分析的通用数据处理引擎. 它基于一种新颖的数据模型，它通过*函数*表示数据并通过*列操作*处理数据，而不是像 MapReduce 或 SQL 这样的传统方法中只有设置操作.
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/)  - 分布式处理和实时分析平台. 与大数据生态系统中的许多流行技术（Kafka、HDFS、Spark 等）集成
* [Apache Hadoop](http://hadoop.apache.org/)  - 分布式处理框架. 集成 MapReduce（并行处理）、YARN（作业调度）和 HDFS（分布式文件系统）.
* [Tigon](https://github.com/caskdata/tigon) - 高吞吐量实时流处理框架.
* [Pachyderm](http://pachyderm.io/) - Pachyderm 是一个建立在 Docker 和 Kubernetes 之上的数据存储平台，提供可重现的数据处理和分析.
* [Polyaxon](https://github.com/polyaxon/polyaxon) - 一个可重复和可扩展的机器学习和深度学习平台.
* [Smooks](https://github.com/smooks/smooks) - 用于构建 XML 和非 XML（CSV、EDI、Java 等）流应用程序的可扩展 Java 框架.

## Distributed Programming

* [AddThis Hydra](https://github.com/addthis/hydra) - 最初在 AddThis 开发的分布式数据处理和存储系统.
* [AMPLab SIMR](http://databricks.github.io/simr/) - 在 Hadoop MapReduce v1 上运行 Spark.
* [Apache APEX](https://apex.apache.org/) - 用于大数据流和批处理的统一企业平台.
* [Apache Beam](https://beam.apache.org/) - 用于定义和执行数据处理工作流的统一模型和一组特定于语言的 SDK.
* [Apache Crunch](http://crunch.apache.org/) - 一个简单的 Java API，用于在普通 MapReduce 上实现繁琐的连接和数据聚合等任务.
* [Apache DataFu](http://incubator.apache.org/projects/datafu.html) - LinkedIn 为 Hadoop 和 Pig 开发的用户定义函数的集合.
* [Apache Flink](http://flink.apache.org/) - 高性能运行时和自动程序优化.
* [Apache Gearpump](http://gearpump.apache.org/) - 基于Akka的实时大数据流引擎.
* [Apache Gora](http://gora.apache.org/) - 内存数据模型和持久性框架.
* [Apache Hama](http://hama.apache.org/) - BSP（批量同步并行）计算框架.
* [Apache MapReduce](https://wiki.apache.org/hadoop/MapReduce/) - 用于在集群上使用并行分布式算法处理大型数据集的编程模型.
* [Apache Pig](https://pig.apache.org/) - 用于表达 Hadoop 数据分析程序的高级语言.
* [Apache REEF](http://reef.apache.org/) - 可保留的评估器执行框架，以简化和统一大数据系统的较低层.
* [Apache S4](http://incubator.apache.org/projects/s4.html) - 流处理框架，S4 的实现.
* [Apache Spark](http://spark.apache.org/) - 内存集群计算框架.
* [Apache Spark Streaming](https://spark.apache.org/docs/latest/streaming-programming-guide.html) - 流处理框架，Spark 的一部分.
* [Apache Storm](http://storm.apache.org) - Twitter 也在 YARN 上进行流处理的框架.
* [Apache Samza](http://samza.apache.org/) - 流处理框架，基于 Kafka 和 YARN.
* [Apache Tez](http://tez.apache.org/) - 用于执行复杂的 DAG（有向无环图）任务的应用程序框架，构建在 YARN 上.
* [Apache Twill](https://incubator.apache.org/projects/twill.html) - 对 YARN 的抽象，降低了开发分布式应用程序的复杂性.
* [Baidu Bigflow](http://bigflow.cloud/en/index.html) - 一个允许编写分布式计算程序的接口，提供许多简单、灵活、强大的 API 来轻松处理任何规模的数据.
* [Cascalog](http://cascalog.org/) - 数据处理和查询库.
* [Cheetah](http://vldbarc.org/pvldb/vldb2010/pvldb_vol3/I08.pdf) - 基于 MapReduce 的高性能自定义数据仓库.
* [Concurrent Cascading](http://www.cascading.org/) - Hadoop 上的数据管理/分析框架.
* [Damballa Parkour](https://github.com/damballa/parkour) - Clojure 的 MapReduce 库.
* [Datasalt Pangool](https://github.com/datasalt/pangool) - 替代 MapReduce 范式.
* [DataTorrent StrAM](https://www.datatorrent.com/) - 实时引擎旨在以尽可能无阻塞的方式启用分布式、异步、实时内存大数据计算，同时将开销和对性能的影响降至最低.
* [Facebook Corona](https://www.facebook.com/notes/facebook-engineering/under-the-hood-scheduling-mapreduce-jobs-more-efficiently-with-corona/10151142560538920) - 消除单点故障的 Hadoop 增强功能.
* [Facebook Peregrine](http://peregrine_mapreduce.bitbucket.org/) - Map Reduce 框架.
* [Facebook Scuba](https://www.facebook.com/notes/facebook-engineering/under-the-hood-data-diving-with-scuba/10150599692628920) - 分布式内存数据存储.
* [Google Dataflow](https://googledevelopers.blogspot.it/2014/06/cloud-platform-at-google-io-new-big.html) - 创建数据管道以帮助他们获取、转换和分析数据.
* [Google MapReduce](https://research.google.com/archive/mapreduce.html) - 映射减少框架.
* [Google MillWheel](https://research.google.com/pubs/pub41378.html) - 容错流处理框架.
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/)  - 分布式处理和实时分析平台. 提供开箱即用的高级分析工具包，如地理空间、时间序列等.
* [JAQL](https://code.google.com/p/jaql/) - 用于处理结构化、半结构化和非结构化数据的声明式编程语言.
* [Kite](http://kitesdk.org/docs/current/) - 是一组库、工具、示例和文档，专注于使在 Hadoop 生态系统上构建系统变得更容易.
* [Metamarkets Druid](http://druid.io/) - 大型数据集实时分析框架.
* [Netflix PigPen](https://github.com/Netflix/PigPen) - Clojure 的 map-reduce 编译为 Apache Pig.
* [Nokia Disco](http://discoproject.org/) - 诺基亚开发的 MapReduce 框架.
* [Onyx](http://www.onyxplatform.org/) - 云的分布式计算.
* [Pinterest Pinlater](https://medium.com/@Pinterest_Engineering/pinlater-an-asynchronous-job-execution-system-b8664cb8aa7d) - 异步作业执行系统.
* [Pydoop](http://crs4.github.io/pydoop/) - 用于 Hadoop 的 Python MapReduce 和 HDFS API.
* [Ray](https://github.com/ray-project/ray) - 用于构建和运行分布式应用程序的快速而简单的框架. 
* [Rackerlabs Blueflood](http://blueflood.io/) - 多租户分布式度量处理系统
* [Skale](https://github.com/skale-me/skale-engine) - NodeJS 中的高性能分布式数据处理.
* [Stratosphere](http://stratosphere.eu/) - 通用集群计算框架.
* [Streamdrill](https://streamdrill.com/) - 用于计算不同时间窗口内事件流的活动并找到最活跃的活动.
* [streamsx.topology](https://github.com/IBMStreams/streamsx.topology) - 支持在 Java、Python 或 Scala 中构建 IBM Streams 应用程序的库.
* [Tuktu](https://github.com/UnderstandLingBV/Tuktu) - 易于使用的批处理和流计算平台，使用 Scala、Akka 和 Play 构建！
* [Twitter Heron](https://github.com/twitter/heron) - Heron 是 Twitter 取代 Storm 的实时、分布式、容错流处理引擎.
* [Twitter Scalding](https://github.com/twitter/scalding) - 基于级联构建的用于 Map Reduce 作业的 Scala 库.
* [Twitter Summingbird](https://github.com/twitter/summingbird) - 使用 Scalding 和 Storm 流式传输 MapReduce，来自 Twitter.
* [Twitter TSAR](https://blog.twitter.com/engineering/en_us/a/2014/tsar-a-timeseries-aggregator.html) - Twitter 的 TimeSeries AggregatorR.
* [Wallaroo](http://www.wallaroolabs.com/community)  - 超快和弹性的数据处理引擎. 大数据或快速数据 - 无需大惊小怪，无需 Java.

## Distributed Filesystem

* [Ambry](https://github.com/linkedin/ambry) - 一个分布式对象存储，支持存储数万亿个小型不可变对象以及数十亿个大型对象.
* [Apache HDFS](http://hadoop.apache.org/) - 一种跨多台机器存储大文件的方法.
* [Apache Kudu](http://kudu.apache.org/) - Hadoop 的存储层，可对快速数据进行快速分析.
* [Ceph Filesystem](http://ceph.com/ceph-storage/file-system/) - 设计的软件存储平台.
* [Disco DDFS](http://disco.readthedocs.org/en/latest/howto/ddfs.html) - 分布式文件系统.
* [Facebook Haystack](https://www.facebook.com/note.php?note_id=76191543919) - 对象存储系统.
* [Google Megastore](https://research.google.com/pubs/pub36971.html) - 可扩展、高度可用的存储.
* [GridGain](https://www.gridgain.com/) - GGFS，符合 Hadoop 的内存文件系统.
* [Lustre file system](http://wiki.lustre.org/) - 高性能分布式文件系统.
* [Microsoft Azure Data Lake Store](https://hadoop.apache.org/docs/current/hadoop-azure-datalake/index.html) - Azure 云中的 HDFS 兼容存储
* [Quantcast File System QFS](https://www.quantcast.com/about-us/quantcast-file-system/) - 开源分布式文件系统.
* [Red Hat GlusterFS](http://gluster.org/) - 横向扩展网络附加存储文件系统.
* [Seaweed-FS](https://github.com/chrislusf/seaweedfs) - 简单且高度可扩展的分布式文件系统.
* [Alluxio](http://www.alluxio.org/) - 跨集群框架以内存速度进行可靠的文件共享.
* [Tahoe-LAFS](https://www.tahoe-lafs.org/trac/tahoe-lafs) - 去中心化的云存储系统.
* [Baidu File System](https://github.com/baidu/bfs) - 分布式文件系统.

## Distributed Index

* [Pilosa](https://github.com/pilosa/pilosa) 开源分布式位图索引，可显着加速跨多个海量数据集的查询. 

## Document Data Model

* [Actian Versant](https://www.actian.com/data-management/ingres-sql-rdbms/) - 商业面向对象的数据库管理系统.
* [Crate Data](https://crate.io/)  - 是一个开源的可大规模扩展的数据存储. 它需要零管理.
* [Facebook Apollo](http://www.infoq.com/news/2014/06/facebook-apollo) - Facebook 的类似 Paxos 的 NoSQL 数据库.
* [jumboDB](http://comsysto.github.io/jumbodb/) - 基于 Hadoop 的面向文档的数据存储.
* [LinkedIn Espresso](https://engineering.linkedin.com/data) - 水平可扩展的面向文档的 NoSQL 数据存储.
* [MarkLogic](http://www.marklogic.com/) - 与架构无关的企业 NoSQL 数据库技术.
* [Microsoft Azure DocumentDB](https://azure.microsoft.com/en-us/services/cosmos-db/) - NoSQL 云数据库服务，支持 MongoDB 协议 
* [MongoDB](https://www.mongodb.com/) - 面向文档的数据库系统.
* [RavenDB](https://ravendb.net/) - 一个事务性的开源文档数据库.
* [RethinkDB](https://rethinkdb.com/) - 支持表连接和分组依据等查询的文档数据库.

## Key Map Data Model

 **注意**：业界有一些术语混淆，两种不同的东西被称为“列式数据库”. 这里列出的一些是围绕“键映射”数据模型构建的分布式持久数据库：所有数据都有一个（可能是复合的）键，键值对映射与之相关联. 在一些系统中，多个这样的值映射可以与一个键相关联，这些映射被称为“列族”（值映射键被称为“列”）.

另一组技术也可以称为“列式数据库”，其特点在于它如何在磁盘或内存中存储数据——而不是以传统方式存储数据，即给定键的所有列值彼此相邻存储，“逐行”，这些系统将所有*列*值彼此相邻存储. 因此，获取给定键的所有列需要更多的工作，但获取给定列的所有值所需的工作更少.

前一组在这里被称为“键映射数据模型”. 这些之间的界线 [Key-value Data Model](#key-value-data-model) 商店相当模糊.

后者更多地是关于存储格式而不是关于数据模型，列在下面 [Columnar Databases](#columnar-databases).

您可以在 Daniel Abadi 教授的博客上阅读有关此区别的更多信息： [Distinguishing two major types of Column Stores](http://dbmsmusings.blogspot.com/2010/03/distinguishing-two-major-types-of_29.html).

* [Apache Accumulo](http://accumulo.apache.org/) - 分布式键/值存储，构建在 Hadoop 上.
* [Apache Cassandra](http://cassandra.apache.org/) - 受 BigTable 启发的面向列的分布式数据存储.
* [Apache HBase](http://hbase.apache.org/) - 受 BigTable 启发的面向列的分布式数据存储.
* [Baidu Tera](https://github.com/baidu/tera) - 一个互联网规模的数据库，灵感来自 BigTable.
* [Facebook HydraBase](https://code.facebook.com/posts/321111638043166/hydrabase-the-evolution-of-hbase-facebook/) - 由 Facebook 开发的 HBase 的演变.
* [Google Cloud Datastore](https://cloud.google.com/datastore/docs/concepts/overview) - 是一个完全托管的无模式数据库，用于在 BigTable 上存储非关系数据.
* [Hypertable](http://www.hypertable.org/) - 受 BigTable 启发的面向列的分布式数据存储.
* [InfiniDB](https://github.com/infinidb/infinidb/) - is accessed through a MySQL interface and use massive parallel processing to parallelize queries.
* [Tephra](https://github.com/caskdata/tephra) - HBase 的事务.
* [Twitter Manhattan](https://blog.twitter.com/engineering/en_us/a/2014/manhattan-our-real-time-multi-tenant-distributed-database-for-twitter-scale.html) - 用于 Twitter 规模的实时、多租户分布式数据库.
* [ScyllaDB](http://www.scylladb.com/) - 用 C++ 编写的面向列的分布式数据存储，与 Apache Cassandra 完全兼容.


## Key-value Data Model

* [Aerospike](http://www.aerospike.com/)  - NoSQL 闪存优化，内存中. 开源和“&#39;C&#39;（不是Java或Erlang）中的服务器代码经过精确调整以避免上下文切换和内存复制.”
* [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - 分布式键/值存储，Dynamo 论文的实现.
* [Badger](https://open.dgraph.io/post/badger/) - 用 Go 本地编写的快速、简单、高效且持久的键值存储.
* [Bolt](https://github.com/boltdb/bolt) - Go 的嵌入式键值数据库.
* [BTDB](https://github.com/Bobris/BTDB) - .Net 中的键值数据库，带有对象数据库层、RPC、动态 IL 等等
* [BuntDB](https://github.com/tidwall/buntdb) - 用于 Go 的快速、可嵌入、内存中键/值数据库，具有自定义索引和地理空间支持.
* [Edis](https://github.com/cbd/edis) - 是 Redis 的协议兼容服务器替代品.
* [ElephantDB](https://github.com/nathanmarz/elephantdb) - 专门用于从 Hadoop 导出数据的分布式数据库.
* [EventStore](https://geteventstore.com/) - 分布式时间序列数据库.
* [GhostDB](https://github.com/jakekgrog/GhostDB) - 分布式、内存中、通用的键值数据存储，可提供任何规模的微秒级性能.
* [Graviton](https://github.com/deroproject/graviton) - 一个简单、快速、版本化、经过身份验证、可嵌入的纯 Go(lang) 键值存储数据库.
* [GridDB](https://github.com/griddb/griddb_nosql) - 适用于存储在时间序列中的传感器数据.
* [HyperDex](https://github.com/rescrv/HyperDex) - 具有广泛特性的可扩展的下一代键值和文档存储，包括一致性、容错性和高性能.
* [Ignite](https://ignite.apache.org/index.html) - 是一种内存键值数据存储，提供完全符合 SQL 的数据访问，可以选择由磁盘存储支持.
* [LinkedIn Krati](https://github.com/linkedin-sna/sna-page/tree/master/krati) - 是一个简单的持久数据存储，具有非常低的延迟和高吞吐量.
* [Linkedin Voldemort](http://www.project-voldemort.com/voldemort/) - 分布式键/值存储系统.
* [Oracle NoSQL Database](http://www.oracle.com/technetwork/database/database-technologies/nosqldb/overview/index.html) - Oracle Corporation 的分布式键值数据库.
* [Redis](https://redis.io/) - 在内存键值数据存储中.
* [Riak](https://github.com/basho/riak) - 去中心化的数据存储.
* [Storehaus](https://github.com/twitter/storehaus) - 用于异步键值存储的库，由 Twitter 提供.
* [SummitDB](https://github.com/tidwall/summitdb) - 内存中的 NoSQL 键/值数据库，具有磁盘持久性并使用 Raft 共识算法.
* [Tarantool](https://github.com/tarantool/tarantool) - 高效的 NoSQL 数据库和 Lua 应用服务器.
* [TiKV](https://github.com/pingcap/tikv) - 由 Rust 提供支持并受 Google Spanner 和 HBase 启发的分布式键值数据库.
* [Tile38](https://github.com/tidwall/tile38) - 地理定位数据存储、空间索引和实时地理围栏，支持各种对象类型，包括纬度/经度点、边界框、XYZ 图块、Geohashes 和 GeoJSON
* [TreodeDB](https://github.com/Treode/store) - 复制和分片的键值存储，并提供原子多行写入.


## Graph Data Model

* [AgensGraph](http://www.agensgraph.com/) - 适用于现代复杂数据环境的新一代多模型图数据库.
* [Apache Giraph](http://giraph.apache.org/) - 基于 Hadoop 的 Pregel 的实现.
* [Apache Spark Bagel](http://spark.apache.org/docs/0.7.3/bagel-programming-guide.html) - Pregel 的实现，Spark 的一部分.
* [ArangoDB](https://www.arangodb.com/) - 多模型分布式数据库.
* [DGraph](https://github.com/dgraph-io/dgraph) - 一个可扩展、分布式、低延迟、高吞吐量的图形数据库，旨在提供 Google 生产级别的规模和吞吐量，具有足够低的延迟以服务实时用户查询，超过 TB 的结构化数据.
* [EliasDB](https://github.com/krotik/eliasdb) - 基于图形的轻量级数据库，不需要任何第三方库.
* [Facebook TAO](https://www.facebook.com/notes/facebook-engineering/tao-the-power-of-the-graph/10151525983993920) - TAO 是 Facebook 广泛使用的分布式数据存储，用于存储和服务社交图谱.
* [GCHQ Gaffer](https://github.com/gchq/Gaffer) - GCHQ 的 Gaffer 是一个框架，可以轻松存储节点和边具有统计信息的大规模图.
* [Google Cayley](https://github.com/cayleygraph/cayley) - 开源图形数据库.
* [Google Pregel](http://kowshik.github.io/JPregel/pregel_paper.pdf) - 图处理框架.
* [GraphLab PowerGraph](https://turi.com/products/create/docs/) - 一个核心 C++ GraphLab API 和一系列构建在 GraphLab API 之上的高性能机器学习和数据挖掘工具包.
* [GraphX](https://amplab.cs.berkeley.edu/publication/graphx-grades/) - Spark 上的弹性分布式图形系统.
* [Gremlin](https://github.com/tinkerpop/gremlin) - 图遍历语言.
* [Infovore](https://github.com/paulhoule/infovore) - 以 RDF 为中心的 Map/Reduce 框架.
* [Intel GraphBuilder](https://01.org/graphbuilder/) - 在 Hadoop 之上构建大规模图的工具.
* [JanusGraph](http://janusgraph.org) - 开源的分布式图形数据库
  具有多种存储后端选项（Bigtable、HBase、Cassandra 等）
  和索引后端（Elasticsearch、Solr、Lucene）.
* [MapGraph](https://www.blazegraph.com/mapgraph-technology/) - GPU 上的大规模并行图处理.
* [Microsoft Graph Engine](https://github.com/Microsoft/GraphEngine) - 分布式内存数据处理引擎，由强类型内存键值存储和通用分布式计算引擎支持.
* [Neo4j](https://neo4j.com/) - 完全用 Java 编写的图形数据库.
* [OrientDB](http://orientdb.com/) - 文档和图形数据库.
* [Phoebus](https://github.com/xslogic/phoebus) - 大规模图形处理的框架.
* [Titan](http://thinkaurelius.github.io/titan/) - 基于 Cassandra 构建的分布式图形数据库.
* [Twitter FlockDB](https://github.com/twitter-archive/flockdb) - 分布式图形数据库.
* [NodeXL](https://nodexl.codeplex.com/) - 适用于 Microsoft® Excel® 2007、2010、2013 和 2016 的免费开源模板，可以轻松探索网络图.


## Columnar Databases

**注意**请阅读注意 [Key-Map Data Model](#key-map-data-model) 部分.

* [Columnar Storage](http://the-paper-trail.org/blog/columnar-storage/) - 什么是列式存储以及何时需要它的解释.
* [Actian Vector](http://www.actian.com/) - column-oriented analytic database.
* [ClickHouse](https://clickhouse.yandex/) - 一个开源的面向列的数据库管理系统，允许实时生成分析数据报告.
* [EventQL](http://eventql.io/) - 为大规模事件收集和分析而构建的分布式、面向列的数据库.
* [MonetDB](https://www.monetdb.org/) - 列存储数据库.
* [Parquet](http://parquet.apache.org/) - Hadoop 的列式存储格式.
* [Pivotal Greenplum](https://pivotal.io/pivotal-greenplum) - 专门构建的专用分析数据仓库，提供列式引擎和传统的基于行的引擎.
* [Vertica](https://www.vertica.com/) - 旨在管理大量快速增长的数据，并在用于数据仓库时提供非常快速的查询性能.
* [SQream DB](http://sqream.com/) - 一个 GPU 驱动的大数据数据库，专为分析和数据仓库而设计，具有符合 ANSI-92 的 SQL，适用于 10TB 到 1PB 的数据集.
* [Google BigQuery](https://cloud.google.com/bigquery/what-is-bigquery) - 谷歌的云产品以他们在 Dremel 上的开创性工作为后盾.
* [Amazon Redshift](https://aws.amazon.com/redshift/) - 亚马逊的云产品，同样基于柱状数据存储后端.
* [IndexR](https://github.com/shunfei/indexr) - 一种开源列式存储格式，用于对大数据进行快速实时分析.
* [LocustDB](https://github.com/cswinter/LocustDB) - 一个实验性分析数据库，旨在为商品硬件上的查询性能设定新标准. 

## NewSQL Databases

* [Actian Ingres](http://www.actian.com/products/operational-databases/) - 商业支持的开源 SQL 关系数据库管理系统.
* [ActorDB](https://github.com/biokoda/actordb) - 具有 KV 存储可扩展性的分布式 SQL 数据库，同时保留关系数据库的查询能力.
* [Amazon RedShift](http://aws.amazon.com/redshift/) - 数据仓库服务，基于 PostgreSQL.
* [BayesDB](https://github.com/probcomp/BayesDB) - 面向统计的 SQL 数据库.
* [Bedrock](http://bedrockdb.com/) - 一个构建在 SQLite 之上的简单、模块化、网络化和分布式事务层.
* [CitusDB](https://www.citusdata.com/) - 通过分片和复制扩展 PostgreSQL.
* [Cockroach](https://github.com/cockroachdb/cockroach) - 可扩展、异地复制、事务性数据存储.
* [Comdb2](https://github.com/bloomberg/comdb2) - 基于乐观并发控制技术构建的集群 RDBMS.
* [Datomic](http://www.datomic.com/) - 分布式数据库旨在实现可扩展、灵活和智能的应用程序.
* [FoundationDB](https://foundationdb.com/) - 受 F1 启发的分布式数据库.
* [Google F1](https://research.google.com/pubs/pub41344.html) - 基于 Spanner 构建的分布式 SQL 数据库.
* [Google Spanner](https://research.google.com/archive/spanner.html) - 全球分布式半关系数据库.
* [H-Store](http://hstore.cs.brown.edu/) - 是一个实验性的主内存并行数据库管理系统，针对在线事务处理 (OLTP) 应用程序进行了优化.
* [Haeinsa](https://github.com/VCNC/haeinsa) - 基于 Percolator 的 HBase 线性可扩展多行、多表事务库.
* [HandlerSocket](https://www.percona.com/doc/percona-server/5.5/performance/handlersocket.html) - MySQL/MariaDB 的 NoSQL 插件.
* [InfiniSQL](http://www.infinisql.org/) - 无限可扩展的 RDBMS.
* [KarelDB](https://github.com/rayokota/kareldb) - 由 Apache Kafka 支持的关系数据库.
* [Map-D](https://www.mapd.com/) - GPU内存数据库，大数据分析和可视化平台.
* [MemSQL](http://www.memsql.com/) - 在闪存上没有优化的列式存储的内存 SQL 数据库.
* [NuoDB](http://www.nuodb.com/) - 符合 SQL/ACID 的分布式数据库.
* [Oracle TimesTen in-Memory Database](http://www.oracle.com/technetwork/database/database-technologies/timesten/overview/index.html) - 具有持久性和可恢复性的内存关系数据库管理系统.
* [Pivotal GemFire XD](http://gemfirexd.docs.pivotal.io/latest/)  - 低延迟、内存中、分布式 SQL 数据存储. 提供内存表数据的 SQL 接口，可持久保存在 HDFS 中.
* [SAP HANA](https://hana.sap.com/abouthana.html) - 是一个内存中、面向列的关系数据库管理系统.
* [SenseiDB](http://senseidb.github.io/sensei/) - 分布式、实时、半结构化数据库.
* [Sky](http://skydb.io/) - 用于对行为数据进行灵活、高性能分析的数据库.
* [SymmetricDS](http://www.symmetricds.org/) - 用于文件和数据库同步的开源软件.
* [TiDB](https://github.com/pingcap/tidb)  - TiDB 是一个分布式 SQL 数据库. 灵感来自 Google F1 的设计.
* [VoltDB](https://www.voltdb.com/) - 声称是最快的内存数据库.
* [yugabyteDB](https://github.com/YugaByte/yugabyte-db) - open source, high-performance, distributed SQL database compatible with PostgreSQL.

## Time-Series Databases

* [Axibase Time Series Database](http://axibase.com/products/axibase-time-series-database/) - 基于 HBase 的集成时间序列数据库，内置可视化、规则引擎和 SQL 支持.
* [Chronix](http://chronix.io/) - 一个时间序列存储，用于存储高度压缩的时间序列和快速访问时间.
* [Cube](http://square.github.io/cube/) - 使用 MongoDB 存储时间序列数据.
* [Heroic](https://spotify.github.io/heroic/#!/index) - 是一个基于 Cassandra 和 Elasticsearch 的可扩展时间序列数据库.
* [InfluxDB](https://www.influxdata.com/) - 具有优化 IO 和查询的时间序列数据库，支持 pgsql 和 influx 线协议.
* [QuestDB](https://questdb.io/) - 适用于金融服务、物联网、机器学习、DevOps 和可观察性应用的高性能开源 SQL 数据库.
* [IronDB](https://www.circonus.com/irondb/) - 可扩展的通用时间序列数据库.
* [Kairosdb](https://github.com/kairosdb/kairosdb) - 类似于 OpenTSDB，但允许使用 Cassandra.
* [M3DB](http://m3db.github.io/m3/m3db/) - 一个分布式时间序列数据库，可用于存储长期保留的实时指标.
* [Newts](https://opennms.github.io/newts/) - 基于 Apache Cassandra 的时间序列数据库.
* [TDengine](https://github.com/taosdata/TDengine/) - C 语言的时间序列数据库利用物联网的独特功能来提高读/写吞吐量并减少存储数据所需的空间
* [OpenTSDB](http://opentsdb.net) - 基于 HBase 的分布式时间序列数据库.
* [Prometheus](https://prometheus.io/) - 时间序列数据库和服务监控系统.
* [Beringei](https://github.com/facebookincubator/beringei) - Facebook 的内存时间序列数据库.
* [TrailDB](http://traildb.io/) - 用于存储和查询一系列事件的有效工具.
* [Druid](https://github.com/druid-io/druid/) 面向列的分布式数据存储非常适合为交互式应用程序提供动力
* [Riak-TS](http://basho.com/products/riak-ts/) Riak TS 是唯一专门针对 IoT 和时间序列数据优化的企业级 NoSQL 时间序列数据库.
* [Akumuli](https://github.com/akumuli/Akumuli)  Akumuli 是一个数字时间序列数据库. 它可用于实时捕获、存储和处理时间序列数据.  “akumuli”这个词可以从世界语翻译为“积累”.
* [Rhombus](https://github.com/Pardot/Rhombus) Cassandra 的时间序列对象存储，可处理构建宽行索引的所有复杂性.
* [Dalmatiner DB](https://github.com/dalmatinerdb/dalmatinerdb) 快速分布式指标数据库
* [Blueflood](https://github.com/rackerlabs/blueflood) 设计用于摄取和处理时间序列数据的分布式系统
* [Timely](https://github.com/NationalSecurityAgency/timely) Timely 是一个时间序列数据库应用程序，它提供对基于 Accumulo 和 Grafana 的时间序列数据的安全访问.
* [SiriDB](https://github.com/transceptor-technology/siridb-server) 具有集群功能的高度可扩展、健壮且快速的开源时间序列数据库.
* [Thanos](https://github.com/improbable-eng/thanos) - Thanos 是一组组件，用于使用多个（现有）Prometheus 部署创建具有无限存储容量的高度可用的度量系统.
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics)  - 与 Prometheus 兼容的快速、可扩展且资源高效的开源 TSDB. 包括单节点和集群版本

## SQL-like processing

* [Actian SQL for Hadoop](http://www.actian.com/analytic-database/vectorh-sql-hadoop) - 对所有 Hadoop 数据的高性能交互式 SQL 访问.
* [Apache Drill](http://drill.apache.org/) - 交互式分析框架，受 Dremel 启发.
* [Apache HCatalog](https://cwiki.apache.org/confluence/display/Hive/HCatalog) - Hadoop 的表和存储管理层.
* [Apache Hive](http://hive.apache.org/) - 类似 SQL 的 Hadoop 数据仓库系统.
* [Apache Calcite](http://calcite.apache.org/) - 允许高效转换涉及异构和联合数据的查询的框架.
* [Apache Phoenix](http://phoenix.apache.org/index.html) - HBase 上的 SQL 皮肤.
* [Aster Database](http://www.teradata.com/products-and-services/Teradata-Aster/teradata-aster-database) - MapReduce 的类 SQL 分析处理.
* [Cloudera Impala](https://www.cloudera.com/products/apache-hadoop/impala.html) - 交互式分析框架，受 Dremel 启发.
* [Concurrent Lingual](http://www.cascading.org/projects/lingual/) - 用于级联的类 SQL 查询语言.
* [Datasalt Splout SQL](http://www.datasalt.com/products/splout-sql/) - 用于大数据集的完整 SQL 查询引擎.
* [Dremio](https://www.dremio.com/) - 基于 Apache Arrow 的开源、类似 SQL 的数据即服务平台.
* [Facebook PrestoDB](https://prestodb.io/) - 分布式 SQL 查询引擎.
* [Google BigQuery](https://research.google.com/pubs/pub36632.html) - 交互式分析框架，Dremel 的实现.
* [Materialize](https://github.com/materializeinc/materialize) - 是用于实时应用程序的流数据库，使用 SQL 进行查询并支持大部分 PostgreSQL.
* [Invantive SQL](https://documentation.invantive.com/2017R2/invantive-sql-grammar/invantive-sql-grammar-17.30.html) - 用于在线和本地使用的 SQL 引擎，具有集成的本地数据复制和 70 多个连接器.
* [PipelineDB](https://www.pipelinedb.com/) - 一个开源关系数据库，它在流上连续运行 SQL 查询，将结果以增量方式存储在表中.
* [Pivotal HDB](https://pivotal.io/pivotal-hdb) - 类似 SQL 的 Hadoop 数据仓库系统.
* [RainstorDB](http://rainstor.com/products/rainstor-database/) - 用于存储 PB 级结构化和半结构化数据的数据库.
* [Spark Catalyst](https://github.com/apache/spark/tree/master/sql) - 是 Spark 和 Shark 的查询优化框架.
* [SparkSQL](https://databricks.com/blog/2014/03/26/spark-sql-manipulating-structured-data-using-spark-2.html) - 使用 Spark 操作结构化数据.
* [Splice Machine](https://www.splicemachine.com/) - 具有 ACID 事务的全功能 SQL-on-Hadoop RDBMS.
* [Stinger](https://hortonworks.com/innovation/stinger/) - Hive 的交互式查询.
* [Tajo](http://tajo.apache.org/) - Hadoop 上的分布式数据仓库系统.
* [Trafodion](https://wiki.trafodion.org/wiki/index.php/Main_Page) - 针对大数据事务或操作工作负载的企业级 SQL-on-HBase 解决方案.

## Data Ingestion
* [redpanda](https://vectorized.io/redpanda)  - 任务关键系统的 Kafka® 替代品； 快 10 倍. 用 C++ 编写.
* [Amazon Kinesis](https://aws.amazon.com/kinesis/) - 大规模实时处理流数据.
* [Amazon Web Services Glue](https://aws.amazon.com/glue/) - 无服务器完全托管的提取、转换和加载 (ETL) 服务
* [Census](https://getcensus.com/)  - 一种反向 ETL 产品，可让您将数据从数据仓库同步到 SaaS 应用程序. 不需要工程方面的帮助——只需要 SQL.
* [Apache Chukwa](http://chukwa.apache.org/) - 数据收集系统.
* [Apache Flume](http://flume.apache.org/) - 管理大量日志数据的服务.
* [Apache Kafka](http://kafka.apache.org/) - 分布式发布订阅消息系统.
* [Apache NiFi](https://nifi.apache.org/) - Apache NiFi 是一个集成的数据物流平台，用于自动化不同系统之间的数据移动.
* [Apache Pulsar](https://github.com/apache/pulsar) - 一个分布式发布-订阅消息平台，具有非常灵活的消息模型和直观的客户端 API.
* [Apache Sqoop](http://sqoop.apache.org/) - 在 Hadoop 和结构化数据存储之间传输数据的工具.
* [Embulk](http://www.embulk.org) - 开源批量数据加载器，有助于在各种数据库、存储、文件格式和云服务之间传输数据.
* [Facebook Scribe](https://github.com/facebookarchive/scribe) - 流式日志数据聚合器.
* [Fluentd](http://www.fluentd.org) - 收集事件和日志的工具.
* [Gazette](https://github.com/gazette/core) - 建立在云存储上的分布式流媒体基础设施，这使得混合和匹配批处理和流媒体范式变得容易.
* [Google Photon](https://research.google.com/pubs/pub41318.html) - 地理分布式系统，用于实时加入多个连续流动的数据流，具有高可扩展性和低延迟.
* [Heka](https://github.com/mozilla-services/heka) - 开源流处理软件系统.
* [HIHO](https://github.com/sonalgoyal/hiho) - 使用 Hadoop 连接不同数据源的框架.
* [Kestrel](https://github.com/papertrail/kestrel) - 分布式消息队列系统.
* [LinkedIn Databus](https://engineering.linkedin.com/data) - 数据库的变更捕获事件流.
* [LinkedIn Kamikaze](https://github.com/linkedin/kamikaze) - 用于压缩排序整数数组的实用程序包.
* [LinkedIn White Elephant](https://github.com/linkedin/white-elephant) - 日志聚合器和仪表板.
* [Logstash](https://www.elastic.co/products/logstash) - 用于管理事件和日志的工具.
* [Netflix Suro](https://github.com/Netflix/suro) - 基于 Chukwa 的日志聚合器，如 Storm 和 Samza.
* [Pinterest Secor](https://github.com/pinterest/secor) - 是一个实现Kafka日志持久化的服务.
* [Linkedin Gobblin](https://github.com/linkedin/gobblin) -linkedin 的通用数据摄取框架.
* [Skizze](https://github.com/skizzehq/skizze) - 草图数据存储以使用概率数据结构处理有关计数和草图的所有问题.
* [StreamSets Data Collector](https://github.com/streamsets/datacollector) - 使用简单易用的 IDE 持续获取大数据基础设施.
* [Alooma](https://www.alooma.com/integrations/mysql) - 数据管道即服务，能够将 MySQL 等数据源移动到数据仓库中.
* [RudderStack](https://github.com/rudderlabs/rudder-server) - 一个用 go 编写的开源客户数据基础设施（segment，mParticle 替代方案）.

## Service Programming

* [Akka Toolkit](http://akka.io/) - JVM 上分布式和容错事件驱动应用程序的运行时.
* [Apache Avro](http://avro.apache.org/) - 数据序列化系统.
* [Apache Curator](http://curator.apache.org/) - Apache ZooKeeper 的 Java 库.
* [Apache Karaf](http://karaf.apache.org/) - 在任何 OSGi 框架之上运行的 OSGi 运行时.
* [Apache Thrift](http://thrift.apache.org//) - 构建二进制协议的框架.
* [Apache Zookeeper](http://zookeeper.apache.org/) - 流程管理的集中服务.
* [Google Chubby](https://research.google.com/archive/chubby.html) - 松散耦合分布式系统的锁服务.
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - 用于将 Apache Spark 分析作业和机器学习模型公开为实时、批处理或反应式 Web 服务的服务.
* [Linkedin Norbert](https://engineering.linkedin.com/data) - 集群管理器.
* [Mara](https://github.com/mara/data-integration) - 一个轻量级的 ETL 框架，介于普通脚本和 Apache Airflow 之间
* [OpenMPI](https://www.open-mpi.org/) - 消息传递框架.
* [Serf](https://www.serf.io/) - 用于服务发现和编排的分散式解决方案.
* [Spotify Luigi](https://github.com/spotify/luigi)  - 用于构建批处理作业的复杂管道的 Python 包. 它处理依赖项解析、工作流管理、可视化、处理故障、命令行集成等等.
* [Spring XD](https://github.com/spring-projects/spring-xd) - 用于数据摄取、实时分析、批处理和数据导出的分布式和可扩展系统.
* [Twitter Elephant Bird](https://github.com/twitter/elephant-bird) - 用于处理 LZOP 压缩数据的库.
* [Twitter Finagle](https://twitter.github.io/finagle/) - JVM 的异步网络堆栈.

## Scheduling

* [Apache Airflow](https://github.com/apache/incubator-airflow) - 一个以编程方式创作、安排和监控工作流程的平台.
* [Apache Aurora](http://aurora.apache.org/) - 是一个运行在 Apache Mesos 之上的服务调度器.
* [Apache Falcon](http://falcon.apache.org/) - 数据管理框架.
* [Apache Oozie](http://oozie.apache.org/) - 工作流作业调度程序.
* [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/data-factory-introduction) - 用于本地、云和 HDInsight 的基于云的管道编排
* [Chronos](http://mesos.github.io/chronos/) - 分布式和容错调度程序.
* [Cronicle](https://github.com/jhuckaby/Cronicle) - 分布式，易于安装，基于NodeJS，任务调度器
* [Dagster](https://github.com/dagster-io/dagster) - 用于机器学习、分析和 ETL 的数据编排器.
* [Linkedin Azkaban](https://azkaban.github.io/) - 批处理工作流作业调度程序.
* [Schedoscope](https://github.com/ottogroup/schedoscope) - 用于灵活调度 Hadoop 作业的 Scala DSL.
* [Sparrow](https://github.com/radlab/sparrow) - 调度平台.


## Machine Learning

* [Azure ML Studio](https://studio.azureml.net/) - 基于云的 AzureML、R、Python 机器学习平台
* [brain](https://github.com/harthur/brain) - JavaScript 中的神经网络.
* [Oryx](https://github.com/OryxProject/oryx) - Apache Spark 上的 Lambda 架构，用于实时大规模机器学习的 Apache Kafka.
* [Concurrent Pattern](http://www.cascading.org/projects/pattern/) - 用于级联的机器学习库.
* [convnetjs](https://github.com/karpathy/convnetjs)  - Javascript 中的深度学习. 在浏览器中训练卷积神经网络（或普通网络）.
* [DataVec](https://github.com/deeplearning4j/DataVec)  - 用于 Java 和 Scala 深度学习的矢量化和数据预处理库.  Deeplearning4j 生态系统的一部分. 
* [Deeplearning4j](https://github.com/deeplearning4j)  - 用于 JVM（Java、Scala、Clojure）的快速、开放式深度学习. 由 C++ 库提供支持的神经网络配置层. 使用 Spark 和 Hadoop 在多个 GPU 和 CPU 上训练网络.
* [Decider](https://github.com/danielsdeleo/Decider) - Ruby 中灵活且可扩展的机器学习.
* [ENCOG](http://www.heatonresearch.com/encog/) - 支持各种高级算法的机器学习框架，以及用于规范化和处理数据的类.
* [etcML](http://www.etcml.com/) - 使用机器学习进行文本分类.
* [Etsy Conjecture](https://github.com/etsy/Conjecture) - Scalding 中的可扩展机器学习.
* [Feast](https://github.com/gojek/feast)  - 用于管理、发现和访问机器学习功能的功能存储.  Feast 为模型训练和模型服务提供了一致的特征数据视图.
* [GraphLab Create](https://dato.com/products/create/) - 一个 Python 机器学习平台，包含广泛的 ML 工具包、数据工程和部署工具.
* [H2O](https://github.com/h2oai/h2o-3/)  - 使用 Hadoop 的统计、机器学习和数学运行时.  R 和 Python.
* [Karate Club](https://github.com/benedekrozemberczki/karateclub)  - 用于图形结构化数据的无监督机器学习库.  Python
* [Keras](https://github.com/fchollet/keras) - 受 Torch 启发的直观神经网络 API，运行在 Theano 和 Tensorflow 之上.
* [Lambdo](https://github.com/johnsonc/lambdo) - Lambdo 是一个工作流引擎，它通过统一特征工程和机器学习操作显着简化了分析过程.
* [Little Ball of Fur](https://github.com/benedekrozemberczki/littleballoffur)  - 图形结构化数据的子采样库.  Python
* [Mahout](http://mahout.apache.org/) - 一个 Apache 支持的 Hadoop 机器学习库.
* [MLbase](http://www.mlbase.org/) - BDAS 堆栈的分布式机器学习库.
* [MLPNeuralNet](https://github.com/nikolaypavlov/MLPNeuralNet) - 适用于 iOS 和 Mac OS X 的快速多层感知器神经网络库.
* [ML Workspace](https://github.com/ml-tooling/ml-workspace) - 专用于机器学习和数据科学的基于 Web 的多合一 IDE.
* [MOA](http://moa.cms.waikato.ac.nz) - MOA 实时进行大数据流挖掘和大规模机器学习.
* [MonkeyLearn](https://monkeylearn.com/)  - 文本挖掘变得容易. 从文本中提取和分类数据.
* [ND4J](https://github.com/deeplearning4j/nd4j)  - JVM 的矩阵库. 用于 Java 的 Numpy. 
* [nupic](https://github.com/numenta/nupic) - Numenta 智能计算平台：受大脑启发的机器智能平台，以及基于皮层学习算法的生物精确神经网络.
* [PredictionIO](http://predictionio.incubator.apache.org/index.html) - 基于 Hadoop、Mahout 和 Cascading 的机器学习服务器.
* [PyTorch Geometric Temporal](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) - PyTorch Geometric 的时间扩展库.
* [RL4J](https://github.com/deeplearning4j/rl4j)  - Java 和 Scala 的强化学习. 包括 Deep-Q 学习和 A3C 算法，并与 Open AI 的 Gym 集成. 在 Deeplearning4j 生态系统中运行. 
* [SAMOA](http://samoa.incubator.apache.org/) - 分布式流机器学习框架.
* [scikit-learn](https://github.com/scikit-learn/scikit-learn) - scikit-learn：Python 中的机器学习.
* [Shapley](https://github.com/benedekrozemberczki/shapley) - 一个数据驱动的框架，用于量化机器学习集成中分类器的价值. 
* [Spark MLlib](http://spark.apache.org/docs/0.9.0/mllib-guide.html) - 一些常见机器学习 (ML) 功能的 Spark 实现.
* [Sibyl](https://users.soe.ucsc.edu/~niejiazhong/slides/chandra.pdf) - 谷歌大规模机器学习系统.
* [TensorFlow](https://github.com/tensorflow/tensorflow) - 来自 Google 的库，用于使用数据流图进行机器学习.
* [Theano](https://github.com/theano) - 蒙特利尔大学支持的以 Python 为重点的机器学习库.
* [Torch](https://github.com/torch) - 一个带有 Lua API 的深度学习库，由纽约大学和 Facebook 支持.
* [Velox](https://github.com/amplab/velox-modelserver) - 用于服务机器学习预测的系统.
* [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/wiki) - 由微软和雅虎赞助的学习系统.
* [WEKA](http://www.cs.waikato.ac.nz/ml/weka/) - 机器学习软件套件.
* [BidMach](https://github.com/BIDData/BIDMach) - CPU 和 GPU 加速的机器学习库.

## Benchmarking

* [Apache Hadoop Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-3561) - 用于测试 Hadoop 性能的微基准测试.
* [Berkeley SWIM Benchmark](https://github.com/SWIMProjectUCB/SWIM/wiki) - 真实世界的大数据工作负载基准.
* [Intel HiBench](https://github.com/intel-hadoop/HiBench) - 一个 Hadoop 基准测试套件.
* [PUMA Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-5116) - MapReduce 应用程序的基准套件.
* [Yahoo Gridmix3](http://yahoohadoop.tumblr.com/post/98294079296/gridmix3-emulating-production-workload-for) - 来自雅虎工程师团队的 Hadoop 集群基准测试.
* [Deeplearning4j Benchmarks](https://github.com/deeplearning4j/dl4j-benchmark)

## Security
* [Apache Ranger](http://ranger.apache.org/) - Central security admin & fine-grained authorization for Hadoop
* [Apache Eagle](http://eagle.apache.org/) - 实时监控解决方案
* [Apache Knox Gateway](http://knox.apache.org/) - Hadoop 集群的单点安全访问.
* [Apache Sentry](http://incubator.apache.org/projects/sentry.html) - 存储在 Hadoop 中的数据的安全模块.
* [BDA](https://github.com/kotobukki/BDA/) - Hadoop 和 Spark 的漏洞检测器

## System Deployment

* [Apache Ambari](http://ambari.apache.org/) - Hadoop 管理的操作框架.
* [Apache Bigtop](http://bigtop.apache.org//) - Hadoop 生态系统的系统部署框架.
* [Apache Helix](http://helix.apache.org/) - 集群管理框架.
* [Apache Mesos](http://mesos.apache.org/) - 集群管理器.
* [Apache Slider](https://github.com/apache/incubator-slider) - 是一个 YARN 应用程序，用于在 YARN 上部署现有的分布式应用程序.
* [Apache Whirr](http://whirr.apache.org/) - 一组用于运行云服务的库.
* [Apache YARN](https://hortonworks.com/hadoop/yarn/) - 集群管理器.
* [Brooklyn](http://brooklyncentral.github.io/) - 简化应用程序部署和管理的库.
* [Buildoop](http://buildoop.github.io/) - 类似于基于 Groovy 语言的 Apache BigTop.
* [Cloudera HUE](http://gethue.com/) - 用于与 Hadoop 交互的 Web 应用程序.
* [Facebook Prism](http://www.wired.com/2012/08/facebook-prism/) - 多数据中心复制系统.
* [Google Borg](https://www.wired.com/2013/03/google-borg-twitter-mesos/all/) - 作业调度和监控系统.
* [Google Omega](https://www.youtube.com/watch?v=0ZFMlO98Jkc) - 作业调度和监控系统.
* [Hortonworks HOYA](https://hortonworks.com/blog/introducing-hoya-hbase-on-yarn/) - 可以在 YARN 上部署 HBase 集群的应用程序.
* [Kubernetes](https://kubernetes.io/) - 用于自动化部署、扩展和管理容器化应用程序的系统.
* [Marathon](https://github.com/mesosphere/marathon) - 用于长期运行服务的 Mesos 框架.
* [Linkis](https://github.com/WeBankFinTech/Linkis) - Linkis 有助于轻松连接到各种后端计算/存储引擎.

## Applications

* [411](https://github.com/etsy/411) - 一个用于警报管理的 Web 应用程序，该应用程序由对 Elasticsearch 的预定搜索产生.
* [Adobe spindle](https://github.com/adobe-research/spindle) - 使用 Scala、Spark 和 Parquet 进行下一代 Web 分析处理.
* [Apache Metron](http://metron.apache.org/) - 集成多种开源大数据技术的平台，为安全监控和分析提供集中工具.
* [Apache Nutch](http://nutch.apache.org/) - 开源网络爬虫.
* [Apache OODT](http://oodt.apache.org/) - 为 NASA 的科学档案采集、处理和共享数据.
* [Argus](https://github.com/salesforce/Argus) - 时间序列监控和警报平台.
* [AthenaX](https://github.com/uber/AthenaX) - 一个流分析平台，使用户能够使用结构化查询语言 (SQL) 运行生产质量的大规模流分析.
* [Atlas](https://github.com/Netflix/atlas) - 用于管理维度时间序列数据的后端.
* [Countly](https://count.ly/) - 基于 Node.js 和 MongoDB 的开源移动和 Web 分析平台.
* [Domino](https://www.dominodatalab.com/) - 运行、扩展、共享和部署模型 - 无需任何基础架构.
* [Eclipse BIRT](http://www.eclipse.org/birt/) - 基于 Eclipse 的报告系统.
* [ElastAert](https://github.com/Yelp/elastalert) - ElastAlert 是一个简单的框架，用于根据 ElasticSearch 中的数据对异常、峰值或其他感兴趣的模式发出警报.
* [Eventhub](https://github.com/Codecademy/EventHub) - 开源事件分析平台.
* [HASH](https://hash.ai) - 开源仿真和可视化平台.
* [Hermes](https://github.com/allegro/hermes) - 建立在 Kafka 之上的异步消息代理.
* [Hunk](https://www.splunk.com/en_us/download/hunk.html) - Hadoop 的 Splunk 分析.
* [Imhotep](http://opensource.indeedeng.io/imhotep/) - 确实是大型分析平台.
* [Indicative](https://www.indicative.com/) - 网络和移动分析工具，具有数据仓库（AWS、BigQuery）集成.
* [Jupyter](https://jupyter.org/) - 用于跨所有编程语言的交互式数据科学和科学计算的笔记本和项目应用程序.
* [MADlib](http://madlib.incubator.apache.org/community/) - 用于分析数据的 RDBMS 的数据处理库.
* [Kapacitor](https://github.com/influxdata/kapacitor) - 用于处理、监控和警报时间序列数据的开源框架.
* [Kylin](http://kylin.apache.org/) - 来自 eBay 的开源分布式分析引擎.
* [PivotalR](https://github.com/pivotalsoftware/PivotalR) - R 在 Pivotal HD / HAWQ 和 PostgreSQL 上.
* [Rakam](https://github.com/rakam-io/rakam) - 由 Postgresql、Kinesis 和 PrestoDB 提供支持的开源实时自定义分析平台. 
* [Qubole](https://www.qubole.com/) - 自动扩展 Hadoop 集群，内置数据连接器.
* [SnappyData](https://github.com/SnappyDataInc/snappydata) - 用于实时操作分析的分布式内存数据存储，在单个集成集群中构建在 Spark 上的流分析、OLTP（在线事务处理）和 OLAP（在线分析处理）.
* [Snowplow](https://github.com/snowplow/snowplow) - 企业级 Web 和事件分析，由 Hadoop、Kinesis、Redshift 和 Postgres 提供支持.
* [SparkR](http://amplab-extras.github.io/SparkR-pkg/) - Spark 的 R 前端.
* [Splunk](https://www.splunk.com/) - 机器生成数据的分析器.
* [Sumo Logic](https://www.sumologic.com/) - 基于云的机器生成数据分析器.
* [Talend](http://www.talend.com/products/big-data/) - 用于 YARN、Hadoop、HBASE、Hive、HCatalog 和 Pig 的统一开源环境.

## Search engine and framework

* [Apache Lucene](http://lucene.apache.org/) - 搜索引擎库.
* [Apache Solr](http://lucene.apache.org/solr/) - Apache Lucene 的搜索平台.
* [Elassandra](https://github.com/strapdata/elassandra) - 是 Elasticsearch 的一个分支，经过修改，可以在 Apache Cassandra 之上以可扩展且有弹性的点对点架构运行.
* [ElasticSearch](https://www.elastic.co/) - 基于 Apache Lucene 的搜索和分析引擎.
* [Enigma.io](https://www.enigma.com/) – 免费增值强大的网络应用程序，用于探索、过滤、分析、搜索和导出从网络上抓取的大量数据集.
* [Google Caffeine](https://googleblog.blogspot.it/2010/06/our-new-search-index-caffeine.html) - 连续索引系统.
* [Google Percolator](https://research.google.com/pubs/pub36726.html) - 连续索引系统.
* [HBase Coprocessor](https://blogs.apache.org/hbase/entry/coprocessor_introduction) - Percolator 的实现，HBase 的一部分.
* [LinkedIn Bobo](http://senseidb.github.io/bobo/) - 是一个完全用 Java 编写的 Faceted Search 实现，是 Apache Lucene 的扩展.
* [LinkedIn Cleo](https://github.com/linkedin/cleo) - 是一个灵活的软件库，用于快速开发部分、无序和实时预输入搜索.
* [LinkedIn Galene](https://engineering.linkedin.com/search/did-you-mean-galene) - LinkedIn 的搜索架构.
* [LinkedIn Zoie](https://github.com/senseidb/zoie) - 是一个用 Java 编写的实时搜索/索引系统.
* [MG4J](http://mg4j.di.unimi.it/) - MG4J (Managing Gigabytes for Java) is a full-text search engine for large document collections written in Java. It is highly customisable, high-performance and provides state-of-the-art features and new research algorithms.
* [Sphinx Search Server](http://sphinxsearch.com/) - 全文搜索引擎.
* [Vespa](http://vespa.ai/)  - 是对大型数据集进行低延迟计算的引擎. 它存储和索引您的数据，以便可以在服务时执行对数据的查询、选择和处理.
* [Facebook Faiss](https://github.com/facebookresearch/faiss)  - 是一个用于密集向量的高效相似性搜索和聚类的库. 它包含在任意大小的向量组中搜索的算法，直到可能不适合 RAM 的向量组. 它还包含用于评估和参数调整的支持代码.  Faiss 是用 C++ 编写的，带有 Python/numpy 的完整包装器.
* [Annoy](https://github.com/spotify/annoy)  - 是一个带有 Python 绑定的 C++ 库，用于搜索空间中靠近给定查询点的点. 它还创建了大型只读基于文件的数据结构，这些数据结构被映射到内存中，以便许多进程可以共享相同的数据.
* [Weaviate](https://github.com/semi-technologies/weaviate) - Weaviate 是一个基于 GraphQL 的语义搜索引擎，具有内置（词）嵌入.

## MySQL forks and evolutions

* [Amazon RDS](https://aws.amazon.com/rds/) - 亚马逊云中的 MySQL 数据库.
* [Drizzle](http://www.drizzle.org/) - MySQL 6.0 的演变.
* [Google Cloud SQL](https://cloud.google.com/sql/docs/) - 谷歌云中的 MySQL 数据库.
* [MariaDB](https://mariadb.org/) - 增强的 MySQL 替代品.
* [MySQL Cluster](https://www.mysql.com/products/cluster/) - 使用 NDB Cluster 存储引擎的 MySQL 实现.
* [Percona Server](https://www.percona.com/software/mysql-database/percona-server) - 增强的 MySQL 替代品.
* [ProxySQL](https://github.com/renecannao/proxysql) - MySQL 的高性能代理.
* [TokuDB](https://www.percona.com/) - TokuDB 是 MySQL 和 MariaDB 的存储引擎.
* [WebScaleSQL](http://webscalesql.org/) - 是来自几家公司的工程师之间的合作，这些公司在大规模运行 MySQL 方面面临类似的挑战.

## PostgreSQL forks and evolutions

* [HadoopDB](http://db.cs.yale.edu/hadoopdb/hadoopdb.html) - MapReduce 和 DBMS 的混合体.
* [IBM Netezza](http://www-01.ibm.com/software/data/netezza/) - 高性能数据仓库设备.
* [Postgres-XL](http://www.postgres-xl.org/) - 可扩展的基于 PostgreSQL 的开源数据库集群.
* [RecDB](http://www-users.cs.umn.edu/~sarwat/RecDB/) - 完全在 PostgreSQL 内部构建的开源推荐引擎.
* [Stado](http://www.stormdb.com/community/stado) - 专门针对数据仓库和数据集市应用程序的开源 MPP 数据库系统.
* [Yahoo Everest](https://www.scribd.com/doc/3159239/70-Everest-PGCon-RT) - 由 PostgreSQL 派生的多 PB 数据库/MPP.
* [TimescaleDB](http://www.timescale.com/) - 针对快速摄取和复杂查询进行了优化的开源时间序列数据库
* [PipelineDB](https://www.pipelinedb.com/)  - 流式 SQL 数据库. 一个开源关系数据库，在流上连续运行 SQL 查询，将结果增量存储在表中

## Memcached forks and evolutions

* [Facebook McDipper](https://www.facebook.com/notes/facebook-engineering/mcdipper-a-key-value-cache-for-flash-storage/10151347090423920) - 用于闪存存储的键/值缓存.
* [Facebook Memcached](https://www.facebook.com/notes/facebook-engineering/scaling-memcache-at-facebook/10151411410803920) - Memcache 的分支.
* [Twemproxy](https://github.com/twitter/twemproxy) - 一个快速、轻量级的 memcached 和 redis 代理.
* [Twitter Fatcache](https://github.com/twitter/fatcache) - 用于闪存存储的键/值缓存.
* [Twitter Twemcache](https://github.com/twitter/twemcache) - Memcache 的分支.

## Embedded Databases

* [Actian PSQL](http://www.actian.com/products/operational-databases/) - 由 Pervasive Software 开发的符合 ACID 的 DBMS，针对嵌入应用程序进行了优化.
* [BerkeleyDB](https://www.oracle.com/database/berkeley-db/index.html) - 为键/值数据提供高性能嵌入式数据库的软件库.
* [HanoiDB](https://github.com/krestenkrab/hanoidb) - Erlang LSM BTree 存储.
* [LevelDB](https://github.com/google/leveldb) - 一个由 Google 编写的快速键值存储库，提供从字符串键到字符串值的有序映射.
* [LMDB](https://symas.com/mdb/) - 由 Symas 开发的超快速、超紧凑的键值嵌入式数据存储.
* [RocksDB](http://rocksdb.org/) - 可嵌入的持久键值存储，用于基于 LevelDB 的快速存储.

## Business Intelligence

* [BIME Analytics](https://www.bimeanalytics.com/?lang=en) - 云中的商业智能平台.
* [Blazer](https://github.com/ankane/blazer) - 商业智能变得简单.
* [Chartio](https://chartio.com) - 用于可视化和探索数据的精益商业智能平台.
* [Count](https://count.co) - 使用 SQL 或拖放操作的基于笔记本的分析和可视化平台.
* [datapine](https://www.datapine.com/) - 云端自助式商业智能工具.
* [Dekart](https://dekart.xyz/) - 基于 Kepler.gl 的 Google BigQuery 大规模地理空间分析.
* [GoodData](https://www.gooddata.com/) - 数据产品和嵌入式分析平台.
* [Jaspersoft](https://www.jaspersoft.com/) - 强大的商业智能套件.
* [Jedox Palo](https://www.jedox.com/en/) - 可定制的商业智能平台.
* [Jethrodata](https://jethro.io/) - 交互式大数据分析.
* [intermix.io](https://intermix.io/) - Amazon Redshift 的性能监控
* [Metabase](https://github.com/metabase/metabase) - 为公司中的每个人提供商业智能和分析的最简单、最快捷的方式.
* [Microsoft](http://www.microsoft.com/en-us/server-cloud/solutions/business-intelligence/default.aspx) - 商业智能软件和平台.
* [Microstrategy](https://www.microstrategy.com/) - 用于商业智能、移动智能和网络应用的软件平台.
* [Numeracy](https://numeracy.co/) - 快速、干净的 SQL 客户端和商业智能.
* [Pentaho](http://www.pentaho.com/) - 商业智能平台.
* [Qlik](http://www.qlik.com/us/) - 商业智能和分析平台.
* [Redash](https://redash.io/) - 开源商业智能平台，支持多数据源和计划查询.
* [Saiku Analytics](https://www.meteorite.bi/) - 开源分析平台.
* [Knowage](https://www.knowage-suite.com/)  - 开源商业智能平台.  （以前 [SpagoBi](http://www.spagobi.org/))
* [SparklineData SNAP](http://sparklinedata.com/) - 由 Apache Spark 提供支持的现代 BI 平台.
* [Tableau](https://www.tableau.com/) - 商业智能平台.
* [Zoomdata](https://www.zoomdata.com/) - 大数据分析.


## Data Visualization

* [Airpal](https://github.com/airbnb/airpal) - PrestoDB 的 Web UI.
* [AnyChart](http://www.anychart.com) - 具有纯 JS API 的快速、简单和灵活的 JavaScript (HTML5) 图表库.
* [Arbor](https://github.com/samizdatco/arbor) - 使用网络工作者和 jQuery 的图形可视化库.
* [Banana](https://github.com/LucidWorks/banana) - visualize logs and time-stamped data stored in Solr. Port of Kibana.
* [Bloomery](https://github.com/ufukomer/bloomery) - Impala 的 Web UI.
* [Bokeh](http://bokeh.pydata.org/en/latest/) - 一个强大的 Python 交互式可视化库，针对现代 Web 浏览器进行演示，目标是提供 D3.js 风格的新颖图形的优雅、简洁的构造，同时还通过非常大的或流式传输的高性能交互性提供此功能数据集.
* [C3](http://c3js.org/) - 基于 D3 的可重用图表库
* [CartoDB](https://github.com/CartoDB/cartodb) - 地理空间数据库的开源或免费增值托管，具有强大的前端编辑功能和强大的 API.
* [chartd](http://chartd.co/) - 响应式、视网膜兼容的图表，只有一个 img 标签.
* [Chart.js](http://www.chartjs.org/) - 开源 HTML5 图表可视化.
* [Chartist.js](https://github.com/gionkunz/chartist-js) - 另一个开源 HTML5 图表可视化.
* [Crossfilter](http://square.github.io/crossfilter/)  - 用于在浏览器中探索大型多元数据集的 JavaScript 库. 适用于 dc.js 和 d3.js.
* [Cubism](https://github.com/square/cubism) - 用于时间序列可视化的 JavaScript 库.
* [Cytoscape](http://cytoscape.github.io/) - 用于可视化复杂网络的 JavaScript 库.
* [DC.js](http://dc-js.github.io/dc.js/)  - 构建的维度图表与使用 d3.js 呈现的 crossfilter 本地工作. 非常适合将图表/附加元数据连接到 D3 中的悬停事件.
* [D3](https://d3js.org/) - 用于操作文档的 javaScript 库.
* [D3.compose](https://github.com/CSNW/d3.compose) - 从可重复使用的图表和组件组成复杂的、数据驱动的可视化.
* [D3Plus](http://d3plus.org) - 一组相当强大的 d3.js 可重用图表和样式.
* [Dash](https://github.com/plotly/dash)  - 适用于 Python、R、Julia 和 Jupyter 的分析 Web 应用程序. 建立在 plotly 之上，不需要 JS
* [Dekart](https://dekart.xyz/) - 基于 Kepler.gl 的 Google BigQuery 大规模地理空间分析.
* [DevExtreme React Chart](https://devexpress.github.io/devextreme-reactive/react/chart/) - 用于 Bootstrap 和 Material Design 的高性能基于插件的 React 图表.
* [Echarts](https://github.com/ecomfe/echarts) - 百度企业排行榜.
* [Envisionjs](https://github.com/HumbleSoftware/envisionjs) - 动态 HTML5 可视化.
* [FnordMetric](https://metrictools.org/) - 编写返回 SVG 图表而不是表格的 SQL 查询
* [Frappe Charts](https://frappe.io/charts) - 受 GitHub 启发的简单而现代的 SVG 网络图表，零依赖.
* [Freeboard](https://github.com/Freeboard/freeboard) - 用于物联网和其他网络混搭的笔源实时仪表板构建器.
* [Gephi](https://github.com/gephi/gephi)  - 一个屡获殊荣的开源平台，用于可视化和操作大型图形和网络连接. 它就像 Photoshop，但用于图形. 适用于 Windows 和 Mac OS X.
* [Google Charts](https://developers.google.com/chart/) - 简单的图表 API.
* [Grafana](https://grafana.com/) - 石墨仪表板前端、编辑器和图形编辑器.
* [Graphite](http://graphiteapp.org/) - 可扩展的实时图形.
* [Highcharts](https://www.highcharts.com/) - 简单灵活的图表 API.
* [IPython](http://ipython.org/) - 为交互式计算提供了丰富的架构.
* [Kibana](https://www.elastic.co/products/kibana) - 可视化日志和时间戳数据
* [Lumify](http://lumify.io/) - 开源大数据分析与可视化平台
* [Matplotlib](https://github.com/matplotlib/matplotlib) - 用 Python 绘图.
* [Metricsgraphic.js](https://metricsgraphicsjs.org/) - 建立在 D3 之上的库，针对时间序列数据进行了优化
* [NVD3](http://nvd3.org/) - d3.js 的图表组件.
* [Peity](https://github.com/benpickles/peity) - 渐进式 SVG 条形图、折线图和饼图.
* [Plot.ly](https://plot.ly/)  - 易于使用的网络服务，允许快速创建复杂的图表，从热图到直方图. 上传数据以使用 Plotly 的在线电子表格创建和设计图表样式. 分叉别人的阴谋.
* [Plotly.js](https://github.com/plotly/plotly.js) 强大的开源 javascript 图形库.
* [Recline](https://github.com/okfn/recline) - 简单但功能强大的库，用于在纯 Javascript 和 HTML 中构建数据应用程序.
* [Redash](https://github.com/getredash/redash) - open-source platform to query and visualize data.
* [ReCharts](http://recharts.org/) - 基于 React 组件构建的可组合图表库
* [Shiny](http://shiny.rstudio.com/) - R 的 Web 应用程序框架.
* [Sigma.js](https://github.com/jacomyal/sigma.js) - 专用于图形绘制的 JavaScript 库.
* [Superset](https://github.com/apache/incubator-superset) - 设计为可视化、直观和交互式的数据探索平台，可以轻松地对数据进行切片、切块和可视化，并以思维的速度执行分析.
* [Vega](https://github.com/vega/vega) - 可视化语法.
* [Zeppelin](https://github.com/ZEPL/zeppelin) - 笔记本式的协作数据分析.
* [Zing Charts](https://www.zingchart.com/) - 用于大数据的 JavaScript 图表库.
* [DataSphere Studio](https://github.com/WeBankFinTech/DataSphereStudio) - 一站式数据应用开发管理门户.

## Internet of things and sensor data
* [Apache Edgent (Incubating)](http://edgent.apache.org/) - 一种编程模型和微内核风格的运行时，可以嵌入网关和小尺寸边缘设备中，支持在边缘设备上进行本地实时分析.
* [Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) - 基于云的双向监控和消息中心
* [TempoIQ](https://www.tempoiq.com/) - 基于云的传感器分析.
* [2lemetry](http://2lemetry.com/) - 物联网平台.
* [Pubnub](https://www.pubnub.com/) - 数据流网络
* [ThingWorx](https://www.thingworx.com/) - 智能系统的快速开发和连接
* [IFTTT](https://ifttt.com/) - 如果这个那么那个
* [Evrything](https://evrythng.com/)- 让产品智能化
* [NetLytics](https://github.com/marty90/netlytics/) - Analytics platform to process network data on Spark.
* [Ably](https://ably.com/) - 物联网的发布/订阅消息平台 

## Interesting Readings

* [Big Data Benchmark](https://amplab.cs.berkeley.edu/benchmark/) - Redshift、Hive、Shark、Impala 和 Stiger/Tez 的基准.
* [NoSQL Comparison](https://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis) - Cassandra vs MongoDB vs CouchDB vs Redis vs Riak vs HBase vs Couchbase vs Neo4j vs Hypertable vs ElasticSearch vs Accumulo vs VoltDB vs Scalaris 比较.
* [Monitoring Kafka performance](https://www.datadoghq.com/blog/monitoring-kafka-performance-metrics?ref=awesome) - 监控 Apache Kafka 的指南，包括用于指标收集的本机方法.
* [Monitoring Hadoop performance](https://www.datadoghq.com/blog/monitor-hadoop-metrics?ref=awesome) - Hadoop 监控指南，概述了 Hadoop 架构，以及用于指标收集的本机方法.
* [Monitoring Cassandra performance](https://www.datadoghq.com/blog/how-to-monitor-cassandra-performance-metrics/?ref=awesome) - Cassandra 监控指南，包括指标收集的本地方法.

## Interesting Papers

### 2015 - 2016
* [2015](http://www.vldb.org/pvldb/vol8/p1804-ching.pdf) - **Facebook** - 万亿边缘：Facebook 规模的图形处理.

### 2013 - 2014
* [2014](http://infolab.stanford.edu/~ullman/mmds/book.pdf) - **斯坦福** - 海量数据集的挖掘.
* [2013](http://research.microsoft.com/pubs/200169/now-vldb.pdf) - **Microsoft** - 云中大数据的可扩展渐进式分析.
* [2013](http://static.druid.io/docs/druid.pdf) - **Metamarkets** - Druid：实时分析数据存储.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p764-rae.pdf) - **Google** - F1 中的在线异步架构更改.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p734-akidau.pdf) - **Google** - MillWheel：互联网规模的容错流处理.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p767-wiener.pdf) - **Facebook** - Scuba：在 Facebook 深入研究数据.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p871-curtiss.pdf) - **Facebook** - Unicorn：一种搜索社交图谱的系统.
* [2013](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf) - **Facebook** - 在 Facebook 扩展 Memcache.

### 2011 - 2012

* [2012](http://vldb.org/pvldb/vol5/p1771_georgelee_vldb2012.pdf) - **Twitter** - 统一的日志基础设施
用于 Twitter 的数据分析.
* [2012](https://www.usenix.org/system/files/login/articles/zaharia.pdf) - **AMPLab** - 使用 Spark 对 Hadoop 数据进行快速交互式分析.
* [2012](https://www.usenix.org/legacy/event/nsdi11/tech/full_papers/Bolosky.pdf) - **Microsoft** - Paxos 复制状态机作为高性能数据存储的基础.
* [2012](http://research.microsoft.com/pubs/178045/ppaoxs-paper29.pdf) - ** Microsoft ** - Paxos 并行.
* [2012](https://arxiv.org/pdf/1203.5485.pdf) - **AMPLab** - BlinkDB：​​对非常大的数据进行有界错误和有界响应时间的查询.
* [2012](http://vldb.org/pvldb/vol5/p1436_alexanderhall_vldb2012.pdf) - **Google** - 每次鼠标点击处理一万亿个细胞.

### 2001 - 2010

* [2010](https://www.usenix.org/legacy/event/osdi10/tech/full_papers/Beaver.pdf) - **Facebook** - 在 Haystack 中寻找针头：Facebook 的照片存储.
* [2010](http://kowshik.github.io/JPregel/pregel_paper.pdf) - **Google** - Pregel：一种用于大规模图形处理的系统.
* [2010](http://leoneu.github.io/) - **Yahoo** - S4：分布式流计算平台.
* [2009](http://www.cs.umd.edu/~abadi/papers/hadoopdb.pdf) - HadoopDB：用于分析工作负载的 MapReduce 和 DBMS 技术的架构混合.	
* [2008](https://cwiki.apache.org/confluence/download/attachments/120729877/chukwa_cca08.pdf?version=1&modificationDate=1562667399000&api=v2) - **AMPLab** - Chukwa：大型监控系统.
* [2007](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/decandia07dynamo.pdf) - **亚马逊** - Dynamo：亚马逊的高可用键值存储.

## Videos

* [Spark in Motion](https://www.manning.com/livevideo/spark-in-motion) - Spark in Motion 教您如何使用 Spark 进行批处理和流式数据分析.
* [Machine Learning, Data Science and Deep Learning with Python ](https://www.manning.com/livevideo/machine-learning-data-science-and-deep-learning-with-python) - 涵盖机器学习、Tensorflow、人工智能和神经网络的 LiveVideo 教程.
* [Data warehouse schema design - dimensional modeling and star schema](https://snir.dev/talks/data-warehouse-schema-design) - 介绍使用星型模式方法的数据仓库模式设计.
* [Elasticsearch 7 and Elastic Stack](https://www.manning.com/livevideo/elasticsearch-7-and-elastic-stack) - LiveVideo 教程，涵盖使用 Elasticsearch、Logstash、Beats、Kibana 等在集群上搜索、分析和可视化大数据.

## Books

#### Streaming
* [Data Science at Scale with Python and Dask](https://www.manning.com/books/data-science-at-scale-with-python-and-dask) - 使用 Python 和 Dask 进行大规模数据科学教您如何构建可以处理大量数据的分布式数据项目.
* [Streaming Data](https://www.manning.com/books/streaming-data) - 流式数据介绍了流式和实时数据系统的概念和要求.
* [Storm Applied](https://www.manning.com/books/storm-applied) - Storm Applied 是使用 Apache Storm 执行与处理和分析实时数据流相关的实际任务的实用指南.
* [Fundamentals of Stream Processing: Application Design, Systems, and Analytics](http://www.cambridge.org/us/academic/subjects/engineering/communications-and-signal-processing/fundamentals-stream-processing-application-design-systems-and-analytics) - 这本综合性的实践指南结合了流处理的基本构建块和新兴研究，非常适合应用程序设计人员、系统构建人员、分析开发人员以及该领域的学生和研究人员.
* [Stream Data Processing: A Quality of Service Perspective](http://www.springer.com/us/book/9780387710020) - 提出了一种适用于流和复杂事件处理的新范式.
* [Unified Log Processing](https://www.manning.com/books/event-streams-in-action) - 统一日志处理是在您的业务中实现事件流（Kafka 或 Kinesis）统一日志的实用指南
* [Kafka Streams in Action](https://www.manning.com/books/kafka-streams-in-action) - Kafka Streams in Action 教您对流入 Kafka 平台的数据实施流处理所需知道的一切，让您可以专注于从数据中获取更多信息，而无需牺牲时间或精力.
* [Big Data](https://www.manning.com/books/big-data) - 大数据教您使用架构构建大数据系统，该架构利用集群硬件以及专为捕获和分析网络规模数据而设计的新工具.
* [Spark in Action](https://www.manning.com/books/spark-in-action) & [Spark in Action 2nd Ed.](https://www.manning.com/books/spark-in-action-second-edition)  - Spark in Action 教您使用 Spark 有效处理批处理和流数据所需的理论和技能. 针对 Spark 2.0 进行了全面更新.
* [Kafka in Action](https://www.manning.com/books/kafka-in-action) - Kafka in Action 快速介绍了与 Kafka 合作的各个方面，您需要真正从中受益.
* [Fusion in Action](https://www.manning.com/books/fusion-in-action) - Fusion in Action 教您构建功能齐全的数据分析管道，包括文档和数据搜索以及分布式数据聚类.
* [Reactive Data Handling](https://www.manning.com/books/reactive-data-handling) - 反应性数据处理是由曼努埃尔·伯恩哈特 (Manuel Bernhardt) 选择的五个精选章节的集合，向您介绍构建能够处理大量数据负载的实时处理的反应性应用程序——免费电子书！ 
* [Azure Data Engineering](https://www.manning.com/books/azure-data-engineering) - 一本关于一般数据工程和 Azure 平台的书 
* [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems)  - Grokking Streaming Systems 可帮助您了解什么是流媒体系统、它们的工作方式以及它们是否适合您的业务. 与工具无关，无论您选择哪种框架，您都可以应用所学.

#### Distributed systems
* [Distributed Systems for fun and profit](http://book.mixu.net/distsys/)  – 分布式系统理论. 包括有关时间和排序、复制和不可能结果的部分.

#### Graph Based approach
* [Graph-Powered Machine Learning](https://www.manning.com/books/graph-powered-machine-learning)  - 亚历山德罗·内格罗. 结合图论和模型来改进机器学习项目

### Data Visualization
 * [The beauty of data visualization](https://www.youtube.com/watch?v=5Zg-C8AAIGg)
 * [Designing Data Visualizations with Noah Iliinsky](https://www.youtube.com/watch?v=R-oiKt7bUU8)
 * [Hans Rosling's 200 Countries, 200 Years, 4 Minutes](https://www.youtube.com/watch?v=jbkSRLYSojo)
 * [Ice Bucket Challenge Data Visualization](https://www.youtube.com/watch?v=qTEchen97rQ)


## Other Awesome Lists
- 其他很棒的列表 [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).
- 更多列表 [awesome](https://github.com/sindresorhus/awesome).
- 另一个清单？ [list](https://github.com/jnv/lists).
- 跆拳道！ [awesome-awesome-awesome](https://github.com/t3chnoboy/awesome-awesome-awesome).
- 分析 [awesome-analytics](https://github.com/onurakpolat/awesome-analytics).
- 公共数据集 [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets).
- 图分类 [awesome-graph-classification](https://github.com/benedekrozemberczki/awesome-graph-classification).
- 网络嵌入 [awesome-network-embedding](https://github.com/chihming/awesome-network-embedding).
- 社区检测 [awesome-community-detection](https://github.com/benedekrozemberczki/awesome-community-detection).
- 决策树论文 [awesome-decision-tree-papers](https://github.com/benedekrozemberczki/awesome-decision-tree-papers).
- 欺诈检测论文 [awesome-fraud-detection-papers](https://github.com/benedekrozemberczki/awesome-fraud-detection-papers).
- 梯度提升论文 [awesome-gradient-boosting-papers](https://github.com/benedekrozemberczki/awesome-gradient-boosting-papers).
- 蒙特卡洛树搜索论文 [awesome-monte-carlo-tree-search-papers](https://github.com/benedekrozemberczki/awesome-monte-carlo-tree-search-papers).
- 卡夫卡 [awesome-kafka](https://github.com/monksy/awesome-kafka).
- [Google Bigtable](https://github.com/zrosenbauer/awesome-bigtable).
