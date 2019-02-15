<div class="github-widget" data-repo="onurakpolat/awesome-bigdata"></div>
## Awesome Big Data

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 精选的大数据框架，资源和其他令人敬畏的精选列表.  灵感来自 [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [awesome-ruby](https://github.com/Sdogruyol/awesome-ruby), [hadoopecosystemtable](http://hadoopecosystemtable.github.io/) & [big-data](http://usefulstuff.io/big-data/).

欢迎您的贡献！


## RDBMS
* [MySQL](https://www.mysql.com/) 世界上最流行的开源数据库.
* [PostgreSQL](https://www.postgresql.org/) 世界上最先进的开源数据库.
* [Oracle Database](http://www.oracle.com/us/corporate/features/database-12c/index.html) - 对象关系数据库管理系统.
* [Teradata](http://www.teradata.com/products-and-services/teradata-database/) - 高性能MPP数据仓库平台.

## Frameworks

* [Bistro](https://github.com/asavinov/bistro)   - 用于批处理和流分析的通用数据处理引擎.  它基于一种新颖的数据模型，它通过* functions *表示数据，并通过*列操作*处理数据，而不是像MapReduce或SQL这样的常规方法中设置操作.
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/)   - 分布式处理和实时分析的平台.  与大数据生态系统中的许多流行技术（Kafka，HDFS，Spark等）集成
* [Apache Hadoop](http://hadoop.apache.org/)   - 分布式处理框架.  集成MapReduce（并行处理），YARN（作业调度）和HDFS（分布式文件系统）.
* [Tigon](https://github.com/caskdata/tigon) - 高吞吐量实时流处理框架.
* [Pachyderm](http://pachyderm.io/) -  Pachyderm是一个基于Docker和Kubernetes构建的数据存储平台，可提供可重复的数据处理和分析.
* [Polyaxon](https://github.com/polyaxon/polyaxon) - 可重复和可扩展的机器学习和深度学习的平台.

## Distributed Programming

* [AddThis Hydra](https://github.com/addthis/hydra) - 最初在AddThis开发的分布式数据处理和存储系统.
* [AMPLab SIMR](http://databricks.github.io/simr/) - 在Hadoop MapReduce v1上运行Spark.
* [Apache APEX](https://apex.apache.org/) - 用于大数据流和批处理的统一企业平台.
* [Apache Beam](https://beam.apache.org/) - 统一的模型和一组特定于语言的SDK，用于定义和执行数据处理工作流程.
* [Apache Crunch](http://crunch.apache.org/) - 一个简单的Java API，用于加入和数据聚合等任务，这些任务在普通的MapReduce上实现起来很繁琐.
* [Apache DataFu](http://incubator.apache.org/projects/datafu.html) - 由LinkedIn开发的Hadoop和Pig的用户定义函数的集合.
* [Apache Flink](http://flink.apache.org/) - 高性能运行时和自动程序优化.
* [Apache Gearpump](http://gearpump.apache.org/) - 基于Akka的实时大数据流媒体引擎.
* [Apache Gora](http://gora.apache.org/) - 内存数据模型和持久性的框架.
* [Apache Hama](http://hama.apache.org/) -  BSP（批量同步并行）计算框架.
* [Apache MapReduce](https://wiki.apache.org/hadoop/MapReduce/) - 用于在群集上使用并行分布式算法处理大型数据集的编程模型.
* [Apache Pig](https://pig.apache.org/) - 用于表达Hadoop数据分析程序的高级语言.
* [Apache REEF](http://reef.apache.org/) - 可保留的评估程序执行框架，以简化和统一大数据系统的较低层.
* [Apache S4](http://incubator.apache.org/projects/s4.html) - 流处理框架，S4的实现.
* [Apache Spark](http://spark.apache.org/) - 内存中集群计算的框架.
* [Apache Spark Streaming](http://spark.apache.org/docs/0.7.3/streaming-programming-guide.html) - 流处理框架，Spark的一部分.
* [Apache Storm](http://storm.apache.org) -  Twitter也在YARN上进行流处理的框架.
* [Apache Samza](http://samza.apache.org/) - 基于Kafka和YARN的流处理框架.
* [Apache Tez](http://tez.apache.org/) - 用于执行基于YARN的任务的复杂DAG（有向无环图）的应用程序框架.
* [Apache Twill](https://incubator.apache.org/projects/twill.html) - 对YARN的抽象，降低了开发分布式应用程序的复杂性.
* [Baidu Bigflow](http://bigflow.cloud/en/index.html) - 允许编写分布式计算程序的接口，提供大量简单，灵活，功能强大的API，可轻松处理任何规模的数据.
* [Cascalog](http://cascalog.org/) - 数据处理和查询库.
* [Cheetah](http://vldbarc.org/pvldb/vldb2010/pvldb_vol3/I08.pdf) -  MapReduce之上的高性能，自定义数据仓库.
* [Concurrent Cascading](http://www.cascading.org/) -  Hadoop上的数据管理/分析框架.
* [Damballa Parkour](https://github.com/damballa/parkour) -  Clojure的MapReduce库.
* [Datasalt Pangool](https://github.com/datasalt/pangool) - 替代MapReduce范例.
* [DataTorrent StrAM](https://www.datatorrent.com/) - 实时引擎旨在以尽可能不受限制的方式实现分布式，异步，实时内存中大数据计算，同时将开销和性能降至最低.
* [Facebook Corona](https://www.facebook.com/notes/facebook-engineering/under-the-hood-scheduling-mapreduce-jobs-more-efficiently-with-corona/10151142560538920) -  Hadoop增强功能，可消除单点故障.
* [Facebook Peregrine](http://peregrine_mapreduce.bitbucket.org/) -  Map Reduce框架.
* [Facebook Scuba](https://www.facebook.com/notes/facebook-engineering/under-the-hood-data-diving-with-scuba/10150599692628920) - 分布式内存数据存储.
* [Google Dataflow](https://googledevelopers.blogspot.it/2014/06/cloud-platform-at-google-io-new-big.html) - 创建数据管道以帮助他们提取，转换和分析数据.
* [Google MapReduce](https://research.google.com/archive/mapreduce.html) -  map reduce框架.
* [Google MillWheel](https://research.google.com/pubs/pub41378.html) - 容错流处理框架.
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/)   - 分布式处理和实时分析的平台.  提供开箱即用的高级分析工具包，如地理空间，时间序列等.
* [JAQL](https://code.google.com/p/jaql/) - 用于处理结构化，半结构化和非结构化数据的声明性编程语言.
* [Kite](http://kitesdk.org/docs/current/) - 是一组库，工具，示例和文档，专注于使在Hadoop生态系统之上构建系统变得更加容易.
* [Metamarkets Druid](http://druid.io/) - 用于实时分析大型数据集的框架.
* [Netflix PigPen](https://github.com/Netflix/PigPen) - 用于编译Apache Pig的Clojure的map-reduce.
* [Nokia Disco](http://discoproject.org/) - 由诺基亚开发的MapReduce框架.
* [Onyx](http://www.onyxplatform.org/) - 云的分布式计算.
* [Pinterest Pinlater](https://medium.com/@Pinterest_Engineering/pinlater-an-asynchronous-job-execution-system-b8664cb8aa7d) - 异步作业执行系统.
* [Pydoop](http://crs4.github.io/pydoop/) - 用于Hadoop的Python MapReduce和HDFS API.
* [Rackerlabs Blueflood](http://blueflood.io/) - 多租户分布式度量处理系统
* [Skale](https://github.com/skale-me/skale-engine) -  NodeJS中的高性能分布式数据处理.
* [Stratosphere](http://stratosphere.eu/) - 通用集群计算框架.
* [Streamdrill](https://streamdrill.com/) - 用于计算不同时间窗口上事件流的活动并找到最活跃的时间窗口.
* [streamsx.topology](https://github.com/IBMStreams/streamsx.topology) - 使用Java，Python或Scala构建IBM Streams应用程序的库.
* [Tuktu](https://github.com/UnderstandLingBV/Tuktu) - 易于使用的批处理和流式计算平台，使用Scala，Akka和Play构建！
* [Twitter Heron](https://github.com/twitter/heron) -  Heron是一个实时的，分布式的，容错的流处理引擎，来自Twitter取代Storm.
* [Twitter Scalding](https://github.com/twitter/scalding) - 用于Map Reduce作业的Scala库，基于Cascading构建.
* [Twitter Summingbird](https://github.com/twitter/summingbird) - 通过Twitter流式传输MapReduce与烫伤和风暴.
* [Twitter TSAR](https://blog.twitter.com/engineering/en_us/a/2014/tsar-a-timeseries-aggregator.html) -  Twitter的TimeSeries AggregatoR.
* [Wallaroo](http://www.wallaroolabs.com/community)   - 超快速和弹性数据处理引擎.  大数据或快速数据 - 无需大惊小怪，无需Java.

## Distributed Filesystem

* [Ambry](https://github.com/linkedin/ambry) - 分布式对象存储，支持存储数万亿个小的不可变对象以及数十亿个大对象.
* [Apache HDFS](http://hadoop.apache.org/) - 一种跨多台机器存储大型文件的方法.
* [Apache Kudu](http://kudu.apache.org/) -  Hadoop的存储层，可以快速分析快速数据.
* [Ceph Filesystem](http://ceph.com/ceph-storage/file-system/) - 设计的软件存储平台.
* [Disco DDFS](http://disco.readthedocs.org/en/latest/howto/ddfs.html) - 分布式文件系统.
* [Facebook Haystack](https://www.facebook.com/note.php?note_id=76191543919) - 对象存储系统.
* [Google Megastore](https://research.google.com/pubs/pub36971.html) - 可扩展，高可用性存储.
* [GridGain](https://www.gridgain.com/) -  GGFS，兼容Hadoop的内存文件系统.
* [Lustre file system](http://wiki.lustre.org/) - 高性能的分布式文件系统.
* [Microsoft Azure Data Lake Store](https://hadoop.apache.org/docs/current/hadoop-azure-datalake/index.html) -  Azure云中的HDFS兼容存储
* [Quantcast File System QFS](https://www.quantcast.com/about-us/quantcast-file-system/) - 开源分布式文件系统.
* [Red Hat GlusterFS](http://gluster.org/) - 横向扩展网络附加存储文件系统.
* [Seaweed-FS](https://github.com/chrislusf/seaweedfs) - 简单且高度可扩展的分布式文件系统.
* [Alluxio](http://www.alluxio.org/) - 跨群集框架以内存速度可靠地共享文件.
* [Tahoe-LAFS](https://www.tahoe-lafs.org/trac/tahoe-lafs) - 分散式云存储系统.
* [Baidu File System](https://github.com/baidu/bfs) - 分布式文件系统.

## Distributed Index

* [Pilosa](https://github.com/pilosa/pilosa) 开源分布式位图索引，可显着加速跨多个海量数据集的查询. 

## Document Data Model

* [Actian Versant](https://www.actian.com/data-management/ingres-sql-rdbms/) - 面向商业对象的数据库管理系统.
* [Crate Data](https://crate.io/)   - 是一个开源的大规模可扩展数据存储.  它需要零管理.
* [Facebook Apollo](http://www.infoq.com/news/2014/06/facebook-apollo) -  Facebook的Paxos式NoSQL数据库.
* [jumboDB](http://comsysto.github.io/jumbodb/) - 面向Hadoop的面向文档的数据存储.
* [LinkedIn Espresso](https://engineering.linkedin.com/data) - 可横向扩展的面向文档的NoSQL数据存储.
* [MarkLogic](http://www.marklogic.com/) - 与架构无关的企业NoSQL数据库技术.
* [Microsoft Azure DocumentDB](https://azure.microsoft.com/en-us/services/cosmos-db/) - 具有MongoDB协议支持的NoSQL云数据库服务 
* [MongoDB](https://www.mongodb.com/) - 面向文档的数据库系统.
* [RavenDB](https://ravendb.net/) - 一个事务性的开源文档数据库.
* [RethinkDB](https://rethinkdb.com/) - 支持表连接和分组依据等查询的文档数据库.

## Key Map Data Model

**Note**: There is some term confusion in the industry, and two different things are called "Columnar Databases". Some, listed here, are distributed, persistent databases built around the "key-map" data model: all data has a (possibly composite) key, with which a map of key-value pairs is associated. In some systems, multiple such value maps can be associated with a key, and these maps are referred to as "column families" (with value map keys being referred to as "columns").

 另一组也称为“柱状数据库”的技术的特征在于它如何在磁盘或内存中存储数据 - 而不是以传统方式存储数据，其中给定密钥的所有列值彼此相邻存储，“逐行”，这些系统将所有*列*值相互存储.  因此，需要更多的工作来获取给定键的所有列，但是需要更少的工作来获取给定列的所有值.

 前一组在这里被称为“关键地图数据模型”.  这些和之间的界限 [Key-value Data Model](#key-value-data-model) 商店相当模糊.

后者更多地是关于存储格式而不是数据模型，列在下面 [Columnar Databases](#columnar-databases).

你可以在Daniel Abadi教授的博客上阅读更多关于这种区别的信息： [Distinguishing two major types of Column Stores](http://dbmsmusings.blogspot.com/2010/03/distinguishing-two-major-types-of_29.html).

* [Apache Accumulo](http://accumulo.apache.org/) - 基于Hadoop构建的分布式键/值存储.
* [Apache Cassandra](http://cassandra.apache.org/) - 受BigTable启发的面向列的分布式数据存储区.
* [Apache HBase](http://hbase.apache.org/) - 受BigTable启发的面向列的分布式数据存储区.
* [Baidu Tera](https://github.com/baidu/tera) - 受BigTable启发的互联网规模数据库.
* [Facebook HydraBase](https://code.facebook.com/posts/321111638043166/hydrabase-the-evolution-of-hbase-facebook/) -  Facebook制作HBase的演变.
* [Google Cloud Datastore](https://cloud.google.com/datastore/docs/concepts/overview) - 是一个完全托管的无模式数据库，用于在BigTable上存储非关系数据.
* [Hypertable](http://www.hypertable.org/) - 受BigTable启发的面向列的分布式数据存储区.
* [InfiniDB](https://github.com/infinidb/infinidb/) - 通过MySQL接口访问，并使用大规模并行处理来并行化查询.
* [Tephra](https://github.com/caskdata/tephra) -  HBase的交易.
* [Twitter Manhattan](https://blog.twitter.com/engineering/en_us/a/2014/manhattan-our-real-time-multi-tenant-distributed-database-for-twitter-scale.html) - 用于Twitter规模的实时，多租户分布式数据库.
* [ScyllaDB](http://www.scylladb.com/) - column-oriented distributed datastore written in C++, totally compatible with Apache Cassandra.


## Key-value Data Model

* [Aerospike](http://www.aerospike.com/)   -  NoSQL闪存优化，内存中.  开源和“C&#39;中的服务器代码（不是J​​ava或Erlang）经过精确调整，以避免上下文切换和内存复制.”
* [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - 分布式键/值存储，Dynamo纸张的实现.
* [Badger](https://open.dgraph.io/post/badger/) -  Go中本地编写的快速，简单，高效且持久的键值存储.
* [Bolt](https://github.com/boltdb/bolt) -  Go的嵌入式键值数据库.
* [BTDB](https://github.com/Bobris/BTDB) -  .Net中的键值数据库，包括对象DB层，RPC，动态IL等等
* [BuntDB](https://github.com/tidwall/buntdb) -  Go的快速，可嵌入，内存中键/值数据库，具有自定义索引和地理空间支持.
* [Edis](https://github.com/cbd/edis) - 是Redis的协议兼容服务器替代品.
* [ElephantDB](https://github.com/nathanmarz/elephantdb) - 专门从Hadoop导出数据的分布式数据库.
* [EventStore](https://geteventstore.com/) - 分布式时间序列数据库.
* [GridDB](https://github.com/griddb/griddb_nosql) - 适用于存储在时间序列中的传感器数据.
* [HyperDex](https://github.com/rescrv/HyperDex) - 可扩展的下一代键值和文档存储，具有多种功能，包括一致性，容错性和高性能.
* [Ignite](https://ignite.apache.org/index.html) - 是一个内存中的键值数据存储，提供完全符合SQL的数据访问，可以选择由磁盘存储支持.
* [LinkedIn Krati](https://github.com/linkedin-sna/sna-page/tree/master/krati) - 是一个简单的持久数据存储，具有非常低的延迟和高吞吐量.
* [Linkedin Voldemort](http://www.project-voldemort.com/voldemort/) - 分布式密钥/值存储系统.
* [Oracle NoSQL Database](http://www.oracle.com/technetwork/database/database-technologies/nosqldb/overview/index.html) -  Oracle Corporation的分布式键值数据库.
* [Redis](https://redis.io/) - 在内存键值数据存储区中.
* [Riak](https://github.com/basho/riak) - 分散的数据存储区.
* [Storehaus](https://github.com/twitter/storehaus) - 通过Twitter使用异步键值存储库的库.
* [SummitDB](https://github.com/tidwall/summitdb) - 内存中的NoSQL键/值数据库，具有磁盘持久性并使用Raft一致性算法.
* [Tarantool](https://github.com/tarantool/tarantool) - 高效的NoSQL数据库和Lua应用服务器.
* [TiKV](https://github.com/pingcap/tikv) - 由Rust提供支持且受Google Spanner和HBase启发的分布式键值数据库.
* [Tile38](https://github.com/tidwall/tile38) - 地理定位数据存储，空间索引和实时地理围栏，支持各种对象类型，包括纬度/经度点，边界框，XYZ切片，Geohashes和GeoJSON
* [TreodeDB](https://github.com/Treode/store) - 复制和分片的键值存储，并提供原子多行写入.


## Graph Data Model

* [AgensGraph](http://www.agensgraph.com/) - 用于现代复杂数据环境的新一代多模型图数据库.
* [Apache Giraph](http://giraph.apache.org/) - 基于Hadoop实现Pregel.
* [Apache Spark Bagel](http://spark.apache.org/docs/0.7.3/bagel-programming-guide.html) - 实施Pregel，Spark的一部分.
* [ArangoDB](https://www.arangodb.com/) - 多模型分布式数据库.
* [DGraph](https://github.com/dgraph-io/dgraph) - 可扩展，分布式，低延迟，高吞吐量的图形数据库，旨在提供谷歌生产水平的规模和吞吐量，具有足够低的延迟，可以提供超过数TB的结构化数据的实时用户查询.
* [EliasDB](https://github.com/krotik/eliasdb) - 基于轻量级图形的数据库，不需要任何第三方库.
* [Facebook TAO](https://www.facebook.com/notes/facebook-engineering/tao-the-power-of-the-graph/10151525983993920) -  TAO是分布式数据存储，在Facebook上广泛用于存储和提供社交图.
* [GCHQ Gaffer](https://github.com/gchq/Gaffer) -  GCHQ的Gaffer是一个框架，可以轻松存储节点和边缘具有统计数据的大型图形.
* [Google Cayley](https://github.com/cayleygraph/cayley) - 开源图数据库.
* [Google Pregel](http://kowshik.github.io/JPregel/pregel_paper.pdf) - 图形处理框架.
* [GraphLab PowerGraph](https://turi.com/products/create/docs/) - 核心C ++ GraphLab API以及基于GraphLab API构建的高性能机器学习和数据挖掘工具包的集合.
* [GraphX](https://amplab.cs.berkeley.edu/publication/graphx-grades/) -  Spark上的弹性分布式图形系统.
* [Gremlin](https://github.com/tinkerpop/gremlin) - 图形遍历语言.
* [Infovore](https://github.com/paulhoule/infovore) - 以RDF为中心的Map / Reduce框架.
* [Intel GraphBuilder](https://01.org/graphbuilder/) - 在Hadoop之上构建大型图形的工具.
* [JanusGraph](http://janusgraph.org) - 开源，分布式图形数据库
  有多个存储后端选项（Bigtable，HBase，Cassandra等）
  和索引后端（Elasticsearch，Solr，Lucene）.
* [MapGraph](https://www.blazegraph.com/mapgraph-technology/) -  GPU上的大规模并行图处理.
* [Microsoft Graph Engine](https://github.com/Microsoft/GraphEngine) - 分布式内存数据处理引擎，以强类型内存键值存储和通用分布式计算引擎为基础.
* [Neo4j](https://neo4j.com/) - 完全用Java编写的图形数据库.
* [OrientDB](http://orientdb.com/) - 文档和图形数据库.
* [Phoebus](https://github.com/xslogic/phoebus) - 大规模图处理的框架.
* [Titan](http://thinkaurelius.github.io/titan/) - 分布式图形数据库，构建于Cassandra之上.
* [Twitter FlockDB](https://github.com/twitter-archive/flockdb) - 分布式图形数据库.
* [NodeXL](https://nodexl.codeplex.com/) - Microsoft®Excel®2007,2010,2013和2016的免费开源模板，可以轻松浏览网络图.


## Columnar Databases

**注意**请阅读说明 [Key-Map Data Model](#key-map-data-model) 部分.

* [Columnar Storage](http://the-paper-trail.org/blog/columnar-storage/) - 对什么是柱状存储以及何时需要它的说明.
* [Actian Vector](http://www.actian.com/) - 面向列的分析数据库.
* [C-Store](http://db.lcs.mit.edu/projects/cstore/) - 面向列的DBMS.
* [ClickHouse](https://clickhouse.yandex/) - 面向开源列的数据库管理系统，允许实时生成分析数据报告.
* [EventQL](http://eventql.io/) - 面向列的分布式数据库，专为大规模事件收集和分析而构建.
* [MonetDB](https://www.monetdb.org/) - 列存储数据库.
* [Parquet](http://parquet.apache.org/) -  Hadoop的列式存储格式.
* [Pivotal Greenplum](https://pivotal.io/pivotal-greenplum) - 专门构建的专用分析数据仓库，提供柱状引擎以及传统的基于行的引擎.
* [Vertica](https://www.vertica.com/) - 旨在管理大量，快速增长的数据量，并在用于数据仓库时提供非常快速的查询性能.
* [SQream DB](http://sqream.com/) -  GPU驱动的大数据数据库，专为分析和数据仓库而设计，符合ANSI-92标准的SQL，适用于10TB到1PB的数据集.
* [Google BigQuery](https://cloud.google.com/bigquery/what-is-bigquery) - 谷歌的云产品以他们在Dremel上的开创性工作为后盾.
* [Amazon Redshift](https://aws.amazon.com/redshift/) - 亚马逊的云产品，也基于柱状数据存储后端.
* [IndexR](https://github.com/shunfei/indexr) - 一种开源的柱状存储格式，用于快速实时分析大数据.
* [LocustDB](https://github.com/cswinter/LocustDB) - 旨在为商用硬件设置查询性能的新标准的实验性分析数据库. 

## NewSQL Databases

* [Actian Ingres](http://www.actian.com/products/operational-databases/) - 商业支持的开源SQL关系数据库管理系统.
* [ActorDB](https://github.com/biokoda/actordb) - a distributed SQL database with the scalability of a KV store, while keeping the query capabilities of a relational database.
* [Amazon RedShift](http://aws.amazon.com/redshift/) - 基于PostgreSQL的数据仓库服务.
* [BayesDB](http://probcomp.csail.mit.edu/bayesdb/index.html) - 面向统计的SQL数据库.
* [Bedrock](http://bedrockdb.com/) - 在SQLite上构建的简单，模块化，联网和分布式事务层.
* [CitusDB](https://www.citusdata.com/) - 通过分片和复制扩展PostgreSQL.
* [Cockroach](https://github.com/cockroachdb/cockroach) - 可扩展，地理复制，事务数据存储.
* [Comdb2](https://github.com/bloomberg/comdb2) - 基于乐观并发控制技术的集群RDBMS.
* [Datomic](http://www.datomic.com/) - 分布式数据库，旨在实现可扩展，灵活和智能的应用程序
* [FoundationDB](https://foundationdb.com/) - 受F1启发的分布式数据库.
* [Google F1](https://research.google.com/pubs/pub41344.html) - 基于Spanner构建的分布式SQL数据库.
* [Google Spanner](https://research.google.com/archive/spanner.html) - 全球分布的半关系数据库.
* [H-Store](http://hstore.cs.brown.edu/) - 是一个实验性的主内存并行数据库管理系统，针对在线事务处理（OLTP）应用程序进行了优化.
* [Haeinsa](https://github.com/VCNC/haeinsa) - 基于Percolator的HBase线性可扩展多行，多表事务库.
* [HandlerSocket](https://www.percona.com/doc/percona-server/5.5/performance/handlersocket.html) -  MySQL / MariaDB的NoSQL插件.
* [InfiniSQL](http://www.infinisql.org/) - 无限可扩展RDBMS.
* [Map-D](https://www.mapd.com/) -  GPU内存数据库，大数据分析和可视化平台.
* [MemSQL](http://www.memsql.com/) - 在内存中SQL数据库，在闪存上优化了柱状存储.
* [NuoDB](http://www.nuodb.com/) - 符合SQL / ACID的分布式数据库.
* [Oracle TimesTen in-Memory Database](http://www.oracle.com/technetwork/database/database-technologies/timesten/overview/index.html) - 具有持久性和可恢复性的内存中关系数据库管理系统.
* [Pivotal GemFire XD](http://gemfirexd.docs.pivotal.io/latest/)   - 低延迟，内存中，分布式SQL数据存储.  为内存表数据提供SQL接口，可在HDFS中保留.
* [SAP HANA](https://hana.sap.com/abouthana.html) - 是一个内存中，面向列的关系数据库管理系统.
* [SenseiDB](http://senseidb.github.io/sensei/) - 分布式，实时，半结构化数据库.
* [Sky](http://skydb.io/) - 用于灵活，高性能的行为数据分析的数据库.
* [SymmetricDS](http://www.symmetricds.org/) - 用于文件和数据库同步的开源软件.
* [TiDB](https://github.com/pingcap/tidb)   -  TiDB是一个分布式SQL数据库.  灵感来自Google F1的设计.
* [VoltDB](https://www.voltdb.com/) - 声称是最快的内存数据库.

## Time-Series Databases

* [Axibase Time Series Database](http://axibase.com/products/axibase-time-series-database/) -  HBase之上的集成时间序列数据库，内置可视化，规则引擎和SQL支持.
* [Chronix](http://chronix.io/) - 时间序列存储，用于存储高度压缩的时间序列和快速访问时间.
* [Cube](http://square.github.io/cube/) - 使用MongoDB存储时间序列数据.
* [Heroic](https://spotify.github.io/heroic/#!/index) - 是一个基于Cassandra和Elasticsearch的可扩展时间序列数据库.
* [InfluxDB](https://www.influxdata.com/) - 分布式时间序列数据库.
* [Kairosdb](https://github.com/kairosdb/kairosdb) - 类似于OpenTSDB但允许使用Cassandra.
* [M3DB](http://m3db.github.io/m3/m3db/) - 分布式时间序列数据库，可用于存储长期保留的实时指标.
* [Newts](https://opennms.github.io/newts/) - 基于Apache Cassandra的时间序列数据库.
* [OpenTSDB](http://opentsdb.net) - distributed time series database on top of HBase.
* [Prometheus](https://prometheus.io/) - 时间序列数据库和服务监控系统.
* [Beringei](https://github.com/facebookincubator/beringei) -  Facebook的内存时间序列数据库.
* [TrailDB](http://traildb.io/) - 用于存储和查询一系列事件的有效工具.
* [Druid](https://github.com/druid-io/druid/) 面向列的分布式数据存储非常适合为交互式应用程
* [Riak-TS](http://basho.com/products/riak-ts/) Riak TS是唯一专门针对物联网和时间序列数据进行优化的企业级NoSQL时间序列数据库.
* [Akumuli](https://github.com/akumuli/Akumuli)  Akumuli是一个数字时间序列数据库.  它可用于实时捕获，存储和处理时间序列数据.  “akumuli”这个词可以从世界语翻译为“积累”.
* [Rhombus](https://github.com/Pardot/Rhombus) Cassandra的时间序列对象存储库，用于处理构建宽行索引的所有复杂性.
* [Dalmatiner DB](https://github.com/dalmatinerdb/dalmatinerdb) 快速分布式度量数据库
* [Blueflood](https://github.com/rackerlabs/blueflood) 用于摄取和处理时间序列数据的分布式系统
* [Timely](https://github.com/NationalSecurityAgency/timely) Timely是一个时间序列数据库应用程序，提供基于Accumulo和Grafana的时间序列数据的安全访问.
* [SiriDB](https://github.com/transceptor-technology/siridb-server) 具有集群功能的高度可扩展，强大且快速的开源时间序列数据库.
* [Thanos](https://github.com/improbable-eng/thanos) -  Thanos是一组组件，用于使用多个（现有）Prometheus部署创建具有无限存储容量的高可用度量系统.

## SQL-like processing

* [Actian SQL for Hadoop](http://www.actian.com/analytic-database/vectorh-sql-hadoop) - 对所有Hadoop数据的高性能交互式SQL访问.
* [Apache Drill](http://drill.apache.org/) - 受Dremel启发的交互式分析框架.
* [Apache HCatalog](https://cwiki.apache.org/confluence/display/HCATALOG/Index) -  Hadoop的表和存储管理层.
* [Apache Hive](http://hive.apache.org/) - 用于Hadoop的类似SQL的数据仓库系统.
* [Apache Calcite](http://calcite.apache.org/) - 允许有效翻译涉及异构和联合数据的查询的框架.
* [Apache Phoenix](http://phoenix.apache.org/index.html) -  HBase上的SQL皮肤.
* [Aster Database](http://www.teradata.com/products-and-services/Teradata-Aster/teradata-aster-database) -  MapReduce的类似SQL的分析处理.
* [Cloudera Impala](https://www.cloudera.com/products/apache-hadoop/impala.html) - 交互式分析框架，灵感来自Dremel.
* [Concurrent Lingual](http://www.cascading.org/projects/lingual/) -  Cascading的类SQL查询语言.
* [Datasalt Splout SQL](http://www.datasalt.com/products/splout-sql/) - 用于大型数据集的完整SQL查询引擎.
* [Facebook PrestoDB](https://prestodb.io/) - 分布式SQL查询引擎.
* [Google BigQuery](https://research.google.com/pubs/pub36632.html) - 交互式分析框架，Dremel的实施.
* [PipelineDB](https://www.pipelinedb.com/) - 一个开源的关系数据库，可以在流上连续运行SQL查询，逐步将结果存储在表中.
* [Pivotal HDB](https://pivotal.io/pivotal-hdb) - 用于Hadoop的类似SQL的数据仓库系统.
* [RainstorDB](http://rainstor.com/products/rainstor-database/) - 用于存储PB级结构化和半结构化数据的数据库.
* [Spark Catalyst](https://github.com/apache/spark/tree/master/sql) - 是Spark和Shark的查询优化框架.
* [SparkSQL](https://databricks.com/blog/2014/03/26/spark-sql-manipulating-structured-data-using-spark-2.html) - 使用Spark操纵结构化数据.
* [Splice Machine](https://www.splicemachine.com/) - 具有ACID事务的全功能SQL-on-Hadoop RDBMS.
* [Stinger](https://hortonworks.com/innovation/stinger/) -  Hive的交互式查询.
* [Tajo](http://tajo.apache.org/) -  Hadoop上的分布式数据仓库系统.
* [Trafodion](https://wiki.trafodion.org/wiki/index.php/Main_Page) - 面向大数据事务或操作工作负载的企业级SQL-on-HBase解决方案.

## Data Ingestion

* [Amazon Kinesis](https://aws.amazon.com/kinesis/) - 大规模实时处理流数据.
* [Amazon Web Services Glue](https://aws.amazon.com/glue/) - 无服务器完全托管的提取，转换和加载（ETL）服务
* [Apache Chukwa](http://chukwa.apache.org/) - 数据收集系统.
* [Apache Flume](http://flume.apache.org/) - 用于管理大量日志数据的服务.
* [Apache Kafka](http://kafka.apache.org/) - 分布式发布 - 订阅消息传递系统.
* [Apache NiFi](https://nifi.apache.org/) -  Apache NiFi是一个集成的数据物流平台，用于自动化不同系统之间的数据移动.
* [Apache Sqoop](http://sqoop.apache.org/) - 在Hadoop和结构化数据存储之间传输数据的工具.
* [Cloudera Morphlines](https://github.com/cloudera/cdk/tree/master/cdk-morphlines) - 帮助ETL到Solr，HBase和HDFS的框架.
* [Embulk](http://www.embulk.org) - 开源批量数据加载器，可帮助在各种数据库，存储，文件格式和云服务之间进行数据传输.
* [Facebook Scribe](https://github.com/facebookarchive/scribe) - 流式日志数据聚合器.
* [Fluentd](http://www.fluentd.org) - 收集事件和日志的工具.
* [Google Photon](https://research.google.com/pubs/pub41318.html) - 地理上分布式系统，用于实时连接多个连续流动的数据流，具有高可扩展性和低延迟.
* [Heka](https://github.com/mozilla-services/heka) - 开源流处理软件系统.
* [HIHO](https://github.com/sonalgoyal/hiho) - 用于将不同数据源与Hadoop连接的框架.
* [Kestrel](https://github.com/papertrail/kestrel) - 分布式消息队列系统.
* [LinkedIn Databus](https://engineering.linkedin.com/data) - 数据库的更改捕获事件流.
* [LinkedIn Kamikaze](https://github.com/linkedin/kamikaze) - 用于压缩排序整数数组的实用程序包.
* [LinkedIn White Elephant](https://github.com/linkedin/white-elephant) - 记录聚合器和仪表板.
* [Logstash](https://www.elastic.co/products/logstash) - 用于管理事件和日志的工具.
* [Netflix Suro](https://github.com/Netflix/suro) - 根据Chukwa记录像Storm和Samza这样的agregattor.
* [Pinterest Secor](https://github.com/pinterest/secor) - 是一项实现Kafka日志持久性的服务.
* [Linkedin Gobblin](https://github.com/linkedin/gobblin) -  linkedin的通用数据提取框架.
* [Skizze](https://github.com/skizzehq/skizze) - 草绘数据存储以处理使用概率数据结构进行计数和草绘的所有问题.
* [StreamSets Data Collector](https://github.com/streamsets/datacollector) - 具有简单易用的IDE的连续大数据摄取基础设施.
* [Yahoo Pulsar](https://github.com/apache/incubator-pulsar) - 分布式pub-sub消息传递平台，具有非常灵活的消息传递模型和直观的客户端API.
* [Alooma](https://www.alooma.com/integrations/mysql) - 数据管道即服务，可将MySQL等数据源移动到数据仓库中.

## Service Programming

* [Akka Toolkit](http://akka.io/) -  JVM上的分布式和容错事件驱动应用程序的运行时.
* [Apache Avro](http://avro.apache.org/) - 数据序列化系统.
* [Apache Curator](http://curator.apache.org/) -  Apache ZooKeeper的Java库.
* [Apache Karaf](http://karaf.apache.org/) - 在任何OSGi框架之上运行的OSGi运行时.
* [Apache Thrift](http://thrift.apache.org//) - 构建二进制协议的框架.
* [Apache Zookeeper](http://zookeeper.apache.org/) - 流程管理的集中服务.
* [Google Chubby](https://research.google.com/archive/chubby.html) - 松散耦合分布式系统的锁定服务.
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - 用于将Apache Spark分析作业和机器学习模型公开为实时，批处理或响应式Web服务的服务.
* [Linkedin Norbert](https://engineering.linkedin.com/data) - 集群经理.
* [Mara](https://github.com/mara/data-integration) - 简单易懂的ETL框架，介于普通脚本和Apache Airflow之间
* [OpenMPI](https://www.open-mpi.org/) - 消息传递框架.
* [Serf](https://www.serf.io/) - 用于服务发现和编排的分散式解决方案.
* [Spotify Luigi](https://github.com/spotify/luigi)   - 用于构建批处理作业的复杂管道的Python包.  它处理依赖项解析，工作流管理，可视化，处理故障，命令行集成等等.
* [Spring XD](https://github.com/spring-projects/spring-xd) - 分布式和可扩展的系统，用于数据摄取，实时分析，批处理和数据导出.
* [Twitter Elephant Bird](https://github.com/twitter/elephant-bird) - 用于处理LZOP压缩数据的库.
* [Twitter Finagle](https://twitter.github.io/finagle/) -  JVM的异步网络堆栈.

## Scheduling

* [Apache Airflow](https://github.com/apache/incubator-airflow) - 以编程方式编写，安排和监控工作流程的平台.
* [Apache Aurora](http://aurora.apache.org/) - 是一个在Apache Mesos上运行的服务调度程序.
* [Apache Falcon](http://falcon.apache.org/) - 数据管理框架.
* [Apache Oozie](http://oozie.apache.org/) - 工作流作业调度程序.
* [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/data-factory-introduction) - 用于本地，云和HDInsight的基于云的管道编排
* [Chronos](http://mesos.github.io/chronos/) - 分布式和容错调度程序.
* [Linkedin Azkaban](https://azkaban.github.io/) - 批处理工作流作业调度程序.
* [Schedoscope](https://github.com/ottogroup/schedoscope) - 用于敏捷安排Hadoop作业的Scala DSL.
* [Sparrow](https://github.com/radlab/sparrow) - 调度平台.


## Machine Learning

* [Azure ML Studio](https://studio.azureml.net/) - 基于云的AzureML，R，Python机器学习平台
* [brain](https://github.com/harthur/brain) -  JavaScript中的神经网络.
* [Cloudera Oryx](https://github.com/cloudera/oryx) - 实时大规模机器学习.
* [Concurrent Pattern](http://www.cascading.org/projects/pattern/) -  Cascading的机器学习库.
* [convnetjs](https://github.com/karpathy/convnetjs)   - 在Javascript中深度学习.  在您的浏览器中训练卷积神经网络（或普通的）.
* [DataVec](https://github.com/deeplearning4j/DataVec)   - 用于Java和Scala深度学习的矢量化和数据预处理库.  Deeplearning4j生态系统的一部分. 
* [Deeplearning4j](https://github.com/deeplearning4j)   - 快速，开放的JVM深度学习（Java，Scala，Clojure）.  由C ++库提供支持的神经网络配置层.  使用Spark和Hadoop在多个GPU和CPU上训练网络.
* [Decider](https://github.com/danielsdeleo/Decider) -  Ruby中的灵活和可扩展的机器学习.
* [ENCOG](http://www.heatonresearch.com/encog/) - 机器学习框架，支持各种高级算法，以及支持类来规范化和处理数据.
* [etcML](http://www.etcml.com/) - 机器学习的文本分类.
* [Etsy Conjecture](https://github.com/etsy/Conjecture) - 可扩展的机器学习在烫伤.
* [GraphLab Create](https://dato.com/products/create/) -  Python中的机器学习平台，具有广泛的ML工具包，数据工程和部署工具.
* [H2O](https://github.com/h2oai/h2o-3/)   - 使用Hadoop进行统计，机器学习和数学运行时.  R和Python.
* [Keras](https://github.com/fchollet/keras) - 受Torch启发的直观神经网络API，在Theano和Tensorflow之上运行.
* [Lambdo](https://github.com/asavinov/lambdo) 是一个工作流引擎，通过在一个分析管道中组合（i）特征工程和机器学习（ii）模型训练和预测（iii）表格填充和通过用户定义（Python）函数的列评估，显着简化数据处理和分析.
* [Mahout](http://mahout.apache.org/) - 用于Hadoop的Apache支持的机器学习库.
* [MLbase](http://www.mlbase.org/) - 用于BDAS堆栈的分布式机器学习库.
* [MLPNeuralNet](https://github.com/nikolaypavlov/MLPNeuralNet) - 适用于iOS和Mac OS X的快速多层感知器神经网络库.
* [MOA](http://moa.cms.waikato.ac.nz) -  MOA实时进行大数据流挖掘，并进行大规模机器学习.
* [MonkeyLearn](https://monkeylearn.com/)   - 文本挖掘变得简单.  从文本中提取和分类数据.
* [ND4J](https://github.com/deeplearning4j/nd4j)   -  JVM的矩阵库.  Numpy for Java. 
* [nupic](https://github.com/numenta/nupic) - 用于智能计算的Numenta平台：一个基于大脑的机器智能平台，以及基于皮层学习算法的生物精确神经网络.
* [PredictionIO](http://predictionio.incubator.apache.org/index.html) -  Hadoop，Mahout和Cascading上的机器学习服务器buit.
* [RL4J](https://github.com/deeplearning4j/rl4j)   -  Java和Scala的强化学习.  包括Deep-Q学习和A3C算法，并与Open AI的健身房集成.  在Deeplearning4j生态系统中运行. 
* [SAMOA](http://samoa.incubator.apache.org/) - 分布式流媒体机器学习框架.
* [scikit-learn](https://github.com/scikit-learn/scikit-learn) -  scikit-learn：Python中的机器学习.
* [Spark MLlib](http://spark.apache.org/docs/0.9.0/mllib-guide.html) - 一些常见的机器学习（ML）功能的Spark实现.
* [Sibyl](https://users.soe.ucsc.edu/~niejiazhong/slides/chandra.pdf) -  Google大规模机器学习系统.
* [TensorFlow](https://github.com/tensorflow/tensorflow) - 来自Google的图书馆，用于使用数据流图进行机器学习.
* [Theano](https://github.com/theano) - 蒙特利尔大学支持的以Python为中心的机器学习库.
* [Torch](https://github.com/torch) - 由纽约大学和Facebook支持的具有Lua API的深度学习库.
* [Velox](https://github.com/amplab/velox-modelserver) - 用于提供机器学习预测的系统.
* [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/wiki) - 由微软和雅虎赞助的学习系统！
* [WEKA](http://www.cs.waikato.ac.nz/ml/weka/) - 机器学习软件套件.
* [BidMach](https://github.com/BIDData/BIDMach) -  CPU和GPU加速的机器学习库.

## Benchmarking

* [Apache Hadoop Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-3561) - 用于测试Hadoop性能的微基准测试.
* [Berkeley SWIM Benchmark](https://github.com/SWIMProjectUCB/SWIM/wiki) - 真实世界的大数据工作负载基准.
* [Intel HiBench](https://github.com/intel-hadoop/HiBench) -  Hadoop基准测试套件.
* [PUMA Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-5116) -  MapReduce应用程序的基准套件.
* [Yahoo Gridmix3](http://yahoohadoop.tumblr.com/post/98294079296/gridmix3-emulating-production-workload-for) - 来自雅虎工程师团队的Hadoop集群基准测试.
* [Deeplearning4j Benchmarks](https://github.com/deeplearning4j/dl4j-benchmark)

## Security
* [Apache Ranger](http://ranger.apache.org/) - 中央安全管理员和Hadoop的细粒度授权
* [Apache Eagle](http://eagle.apache.org/) - 实时监控解决方案
* [Apache Knox Gateway](http://knox.apache.org/) -  Hadoop集群的单点安全访问.
* [Apache Sentry](http://incubator.apache.org/projects/sentry.html) - 存储在Hadoop中的数据的安全模块.
* [BDA](https://github.com/kotobukki/BDA/) -  Hadoop和Spark的漏洞检测程序

## System Deployment

* [Apache Ambari](http://ambari.apache.org/) -  Hadoop管理的运营框架.
* [Apache Bigtop](http://bigtop.apache.org//) -  Hadoop生态系统的系统部署框架.
* [Apache Helix](http://helix.apache.org/) - 集群管理框架.
* [Apache Mesos](http://mesos.apache.org/) - 集群经理.
* [Apache Slider](https://github.com/apache/incubator-slider) - 是一个YARN应用程序，用于在YARN上部署现有的分布式应用程序.
* [Apache Whirr](http://whirr.apache.org/) - 用于运行云服务的库集.
* [Apache YARN](https://hortonworks.com/hadoop/yarn/) - 集群管理器.
* [Brooklyn](http://brooklyncentral.github.io/) - 简化应用程序部署和管理的库.
* [Buildoop](http://buildoop.github.io/) - 类似于基于Groovy语言的Apache BigTop.
* [Cloudera HUE](http://gethue.com/) - 用于与Hadoop交互的Web应用程序.
* [Facebook Prism](http://www.wired.com/2012/08/facebook-prism/) - 多数据中心复制系统.
* [Google Borg](https://www.wired.com/2013/03/google-borg-twitter-mesos/all/) - 工作安排和监测系统.
* [Google Omega](https://www.youtube.com/watch?v=0ZFMlO98Jkc) - 工作安排和监测系统.
* [Hortonworks HOYA](https://hortonworks.com/blog/introducing-hoya-hbase-on-yarn/) - 可以在YARN上部署HBase集群的应用程序.
* [Kubernetes](https://kubernetes.io/) - 用于自动化容器化应用程序的部署，扩展和管理的系统.
* [Marathon](https://github.com/mesosphere/marathon) - 用于长期运行服务的Mesos框架.

## Applications

* [411](https://github.com/etsy/411) - 由于计划搜索Elasticsearch而导致的警报管理Web应用程序.
* [Adobe spindle](https://github.com/adobe-research/spindle) - 使用Scala，Spark和Parquet进行下一代Web分析处理.
* [Apache Kiji](http://www.kiji.org.s3-website-us-east-1.amazonaws.com) - 基于HBase实时收集和分析数据的框架.
* [Apache Metron](http://metron.apache.org/) - 集成各种开源大数据技术的平台，为安全监控和分析提供集中的工具.
* [Apache Nutch](http://nutch.apache.org/) - 开源网络爬虫.
* [Apache OODT](http://oodt.apache.org/) - 为NASA的科学档案捕获，处理和共享数据.
* [Argus](https://github.com/salesforce/Argus) - 时间序列监控和警报平台.
* [AthenaX](https://github.com/uber/AthenaX) - 流分析平台，使用户能够使用结构化查询语言（SQL）运行生产质量的大规模流分析.
* [Atlas](https://github.com/Netflix/atlas) - 用于管理维度时间序列数据的后端.
* [Countly](https://count.ly/) - 基于Node.js和MongoDB的开源移动和网络分析平台.
* [Domino](https://www.dominodatalab.com/) - 运行，扩展，共享和部署模型 - 无需任何基础架构.
* [Eclipse BIRT](http://www.eclipse.org/birt/) - 基于Eclipse的报告系统.
* [ElastAert](https://github.com/Yelp/elastalert) -  ElastAlert是一个简单的框架，用于警告ElasticSearch中的数据中的异常，尖峰或其他感兴趣的模式.
* [Eventhub](https://github.com/Codecademy/EventHub) - open source event analytics platform.
* [Hermes](https://github.com/allegro/hermes) - 构建在Kafka之上的异步消息代理.
* [HIPI Library](http://hipi.cs.virginia.edu/) - 用于在Hadoop的MapReduce上执行图像处理任务的API.
* [Hunk](https://www.splunk.com/en_us/download/hunk.html) - 针对Hadoop的Splunk分析.
* [Imhotep](http://opensource.indeedeng.io/imhotep/) - 确实是大规模分析平台.
* [MADlib](http://madlib.incubator.apache.org/community/) - 用于分析数据的RDBMS的数据处理库.
* [Kapacitor](https://github.com/influxdata/kapacitor) - 用于处理，监控和警告时间序列数据的开源框架.
* [Kylin](http://kylin.apache.org/) - 来自eBay的开源分布式分析引擎.
* [PivotalR](https://github.com/pivotalsoftware/PivotalR) - 关于Pivotal HD / HAWQ和PostgreSQL的R.
* [Rakam](https://github.com/rakam-io/rakam) - 由Postgresql，Kinesis和PrestoDB提供支持的开源实时自定义分析平台. 
* [Qubole](https://www.qubole.com/) - 自动扩展Hadoop集群，内置数据连接器.
* [Sense](https://sense.io/) - 用于数据科学和大数据分析的云平台.
* [SnappyData](https://github.com/SnappyDataInc/snappydata) - 用于实时运营分析的分布式内存数据存储，在单个集成集群中提供基于Spark构建的流分析，OLTP（在线事务处理）和OLAP（在线分析处理）.
* [Snowplow](https://github.com/snowplow/snowplow) - 由Hadoop，Kinesis，Redshift和Postgres提供支持的企业级Web和事件分析.
* [SparkR](http://amplab-extras.github.io/SparkR-pkg/) -  Spark的R前端.
* [Splunk](https://www.splunk.com/) - 机器生成数据的分析器.
* [Sumo Logic](https://www.sumologic.com/) - 基于云的分析器，用于机器生成的数据.
* [Talend](http://www.talend.com/products/big-data/) -  YARN，Hadoop，HBASE，Hive，HCatalog和Pig的统一开源环境.
* [Warp](https://warp.one//) - 通过示例工具查询大数据（OS X app）

## Search engine and framework

* [Apache Lucene](http://lucene.apache.org/) - 搜索引擎库.
* [Apache Solr](http://lucene.apache.org/solr/) -  Apache Lucene的搜索平台.
* [Elassandra](https://github.com/strapdata/elassandra) - 是一个Elasticsearch的分支，经过修改，可以在Apache Cassandra上运行，具有可扩展且灵活的对等体系结构.
* [ElasticSearch](https://www.elastic.co/) - 基于Apache Lucene的搜索和分析引擎.
* [Enigma.io](https://www.enigma.com/) - 免费增强的Web应用程序，用于浏览，过滤，分析，搜索和导出从Web上抓取的大量数据集.
* [Facebook Unicorn](https://www.facebook.com/publications/219621248185635/) - 社交图搜索平台.
* [Google Caffeine](https://googleblog.blogspot.it/2010/06/our-new-search-index-caffeine.html) - 连续索引系统.
* [Google Percolator](https://research.google.com/pubs/pub36726.html) - 连续索引系统.
* [TeraGoogle]（） - 大型搜索索引.
* [HBase Coprocessor](https://blogs.apache.org/hbase/entry/coprocessor_introduction) - 实施Percolator，HBase的一部分.
* [LinkedIn Bobo](http://senseidb.github.io/bobo/) - 是纯粹用Java编写的分面搜索实现，是Apache Lucene的扩展.
* [LinkedIn Cleo](https://github.com/linkedin/cleo) - 是一个灵活的软件库，用于实现部分，无序和实时预先搜索的快速开发.
* [LinkedIn Galene](https://engineering.linkedin.com/search/did-you-mean-galene) -  LinkedIn的搜索架构.
* [LinkedIn Zoie](https://github.com/senseidb/zoie) - 是一个用Java编写的实时搜索/索引系统.
* [MG4J](http://mg4j.di.unimi.it/)   -  MG4J（管理Gigabytes for Java）是一个用Java编写的大型文档集的全文搜索引擎.  它具有高度可定制性，高性能，并提供最先进的功能和新的研究算法.
* [Sphinx Search Server](http://sphinxsearch.com/) - 全文搜索引擎.
* [Vespa](http://vespa.ai/)   - 是大数据集上低延迟计算的引擎.  它存储和索引您的数据，以便可以在服务时执行对数据的查询，选择和处理.

## MySQL forks and evolutions

* [Amazon RDS](https://aws.amazon.com/rds/) - 亚马逊云中的MySQL数据库.
* [Drizzle](http://www.drizzle.org/) -  MySQL 6.0的演变.
* [Google Cloud SQL](https://cloud.google.com/sql/docs/) - 谷歌云中的MySQL数据库.
* [MariaDB](https://mariadb.org/) - 增强的，直接替代MySQL.
* [MySQL Cluster](https://www.mysql.com/products/cluster/) - 使用NDB Cluster存储引擎的MySQL实现.
* [Percona Server](https://www.percona.com/software/mysql-database/percona-server) - 增强的，直接替代MySQL.
* [ProxySQL](https://github.com/renecannao/proxysql) -  MySQL的高性能代理.
* [TokuDB](https://www.percona.com/) -  TokuDB是MySQL和MariaDB的存储引擎.
* [WebScaleSQL](http://webscalesql.org/) - 是来自几家公司的工程师之间的合作，这些公司在大规模运行MySQL时面临类似的挑战.

## PostgreSQL forks and evolutions

* [HadoopDB](http://db.cs.yale.edu/hadoopdb/hadoopdb.html) -  MapReduce和DBMS的混合体.
* [IBM Netezza](http://www-01.ibm.com/software/data/netezza/) - 高性能数据仓库设备.
* [Postgres-XL](http://www.postgres-xl.org/) - 基于PostgreSQL的可扩展开源数据库集群.
* [RecDB](http://www-users.cs.umn.edu/~sarwat/RecDB/) - 完全在PostgreSQL内部构建的开源推荐引擎.
* [Stado](http://www.stormdb.com/community/stado) - 仅针对数据仓库和数据集市应用的开源MPP数据库系统.
* [Yahoo Everest](https://www.scribd.com/doc/3159239/70-Everest-PGCon-RT) - 由PostgreSQL派生的多peta字节数据库/ MPP.
* [TimescaleDB](http://www.timescale.com/) - 针对快速摄取和复杂查询而优化的开源时间序列数据库
* [PipelineDB](https://www.pipelinedb.com/)   - 流式SQL数据库.  一个开源关系数据库，它在流上连续运行SQL查询，逐步将结果存储在表中

## Memcached forks and evolutions

* [Facebook McDipper](https://www.facebook.com/notes/facebook-engineering/mcdipper-a-key-value-cache-for-flash-storage/10151347090423920) - 闪存存储的键/值缓存.
* [Facebook Memcached](https://www.facebook.com/notes/facebook-engineering/scaling-memcache-at-facebook/10151411410803920) -  Memcache的分支.
* [Twemproxy](https://github.com/twitter/twemproxy) -  memcached和redis的快速，轻量级代理.
* [Twitter Fatcache](https://github.com/twitter/fatcache) - 闪存存储的键/值缓存.
* [Twitter Twemcache](https://github.com/twitter/twemcache) -  Memcache的分支.

## Embedded Databases

* [Actian PSQL](http://www.actian.com/products/operational-databases/) -  Pervasive Software开发的符合ACID标准的DBMS，针对嵌入应用程序进行了优化.
* [BerkeleyDB](https://www.oracle.com/database/berkeley-db/index.html) - 一个软件库，为键/值数据提供高性能的嵌入式数据库.
* [HanoiDB](https://github.com/krestenkrab/hanoidb) -  Erlang LSM BTree Storage.
* [LevelDB](https://github.com/google/leveldb) - 在Google编写的快速键值存储库，提供从字符串键到字符串值的有序映射.
* [LMDB](https://symas.com/mdb/) -  Symas开发的超快速，超紧凑的键值嵌入式数据存储.
* [RocksDB](http://rocksdb.org/) - 基于LevelDB的可嵌入持久键值存储，用于快速存储.

## Business Intelligence

* [BIME Analytics](https://www.bimeanalytics.com/?lang=en) - 云中的商业智能平台.
* [Chartio](https://chartio.com) - 精益商业智能平台，可视化和探索您的数据.
* [datapine](https://www.datapine.com/) - 云中的自助商业智能工具.
* [GoodData](https://www.gooddata.com/) - 数据产品和嵌入式分析平台.
* [Jaspersoft](https://www.jaspersoft.com/) - 强大的商业智能套件.
* [Jedox Palo](https://www.jedox.com/en/) - 可定制的商业智能平台.
* [Jethrodata](https://jethro.io/) - 互动大数据分析.
* [Metabase](https://github.com/metabase/metabase) - 向公司中的每个人提供商业智能和分析的最简单，最快捷的方法.
* [Microsoft](http://www.microsoft.com/en-us/server-cloud/solutions/business-intelligence/default.aspx) - 商业智能软件和平台.
* [Microstrategy](https://www.microstrategy.com/) - 用于商业智能，移动智能和网络应用的软件平台.
* [Numeracy](https://numeracy.co/) - 快速，干净的SQL客户端和商业智能.
* [Pentaho](http://www.pentaho.com/) - 商业智能平台.
* [Qlik](http://www.qlik.com/us/) - 商业智能和分析平台.
* [Redash](https://redash.io/) - 开源商业智能平台，支持多个数据源和计划查询.
* [Saiku](http://www.meteorite.bi/) - 开源分析平台.
* [SpagoBI](http://www.spagobi.org/) - 开源商业智能平台.
* [SparklineData SNAP](http://sparklinedata.com/) - 由Apache Spark提供支持的现代BI平台.
* [Tableau](https://www.tableau.com/) - 商业智能平台.
* [Zoomdata](https://www.zoomdata.com/) - 大数据分析.


## Data Visualization

* [Airpal](https://github.com/airbnb/airpal) -  PrestoDB的Web UI.
* [AnyChart](http://www.anychart.com) - fast, simple and flexible JavaScript (HTML5) charting library featuring pure JS API.
* [Arbor](https://github.com/samizdatco/arbor) - 使用web worker和jQuery的图形可视化库.
* [Banana](https://github.com/LucidWorks/banana)   - 可视化存储在Solr中的日志和带时间戳的数据.  Kibana港.
* [Bloomery](https://github.com/ufukomer/bloomery) -  Impala的Web UI.
* [Bokeh](http://bokeh.pydata.org/en/latest/) - 功能强大的Python交互式可视化库，面向现代Web浏览器进行演示，目标是以D3.js的风格提供优雅，简洁的新颖图形构造，同时通过非常大或流式传输提供高性能交互功能数据集.
* [C3](http://c3js.org/) - 基于D3的可重用图表库
* [CartoDB](https://github.com/CartoDB/cartodb) - 地理空间数据库的开源或免费增值托管，具有强大的前端编辑功能和强大的API.
* [chartd](http://chartd.co/) - 仅具有img标签的响应式视网膜兼容图表.
* [Chart.js](http://www.chartjs.org/) - 开源HTML5图表可视化.
* [Chartist.js](https://github.com/gionkunz/chartist-js) - 另一个开源HTML5图表可视化.
* [Crossfilter](http://square.github.io/crossfilter/)   - 用于在浏览器中探索大型多变量数据集的JavaScript库.  适用于dc.js和d3.js.
* [Cubism](https://github.com/square/cubism) - 用于时间序列可视化的JavaScript库.
* [Cytoscape](http://cytoscape.github.io/) - 用于可视化复杂网络的JavaScript库.
* [DC.js](http://dc-js.github.io/dc.js/)   - 使用d3.js生成的使用crossfilter本地工作的维度图表.  非常适合将图表/其他元数据连接到D3中的悬停事件.
* [D3](https://d3js.org/) - 用于操作文档的javaScript库.
* [D3.compose](https://github.com/CSNW/d3.compose) - 从可重用的图表和组件中构建复杂的，数据驱动的可视化.
* [D3Plus](http://d3plus.org) -  d3.js的一组相当强大的可重用图表和样式.
* [Echarts](https://github.com/ecomfe/echarts) -  Baidus企业图表.
* [Envisionjs](https://github.com/HumbleSoftware/envisionjs) - 动态HTML5可视化.
* [FnordMetric](https://metrictools.org/) - 编写返回SVG图表而不是表格的SQL查询
* [Frappe Charts](https://frappe.io/charts) -  GitHub启发的简单和现代SVG图表，为Web提供零依赖.
* [Freeboard](https://github.com/Freeboard/freeboard) - 用于物联网和其他网络混搭的笔源实时仪表板构建器.
* [Gephi](https://github.com/gephi/gephi)   - 屡获殊荣的开源平台，用于可视化和操作大型图形和网络连接.  这就像Photoshop，但对于图表.  适用于Windows和Mac OS X.
* [Google Charts](https://developers.google.com/chart/) - 简单的图表API.
* [Grafana](https://grafana.com/) - 石墨仪表板前端，编辑器和图形作曲家.
* [Graphite](http://graphiteapp.org/) - 可扩展的实时图形.
* [Highcharts](https://www.highcharts.com/) - 简单灵活的图表API.
* [IPython](http://ipython.org/) - 为交互式计算提供丰富的架构.
* [Kibana](https://www.elastic.co/products/kibana) - 可视化日志和带时间戳的数据
* [Lumify](http://lumify.io/) - 开源大数据分析和可视化平台
* [Matplotlib](https://github.com/matplotlib/matplotlib) - 用Python绘图.
* [Metricsgraphic.js](https://metricsgraphicsjs.org/) - 基于D3构建的库，针对时间序列数据进行了优化
* [NVD3](http://nvd3.org/) -  d3.js的图表组件
* [Peity](https://github.com/benpickles/peity) - 渐进式SVG条形图，折线图和饼图.
* [Plot.ly](https://plot.ly/)   - 易于使用的Web服务，可以快速创建复杂的图表，从热图到直方图.  使用Plotly的在线电子表格上传数据以创建和设置图表.  分叉别人的情节.
* [Plotly.js](https://github.com/plotly/plotly.js) 开源的javascript图形库，可以提供强大的功能.
* [Recline](https://github.com/okfn/recline) - 简单但功能强大的库，用于在纯Javascript和HTML中构建数据应用程序.
* [Redash](https://github.com/getredash/redash) - 用于查询和可视化数据的开源平台.
* [ReCharts](http://recharts.org/) - 基于React组件构建的可组合图表库
* [Shiny](http://shiny.rstudio.com/) -  R的Web应用程序框架
* [Sigma.js](https://github.com/jacomyal/sigma.js) - 专用于图形绘制的JavaScript库.
* [Superset](https://github.com/apache/incubator-superset) - 数据探索平台，设计为直观，直观和交互式，可以轻松切片，切块和可视化数据，并以思维速度执行分析.
* [Vega](https://github.com/vega/vega) - 可视化语法.
* [Zeppelin](https://github.com/ZEPL/zeppelin) - 笔记本式协作数据分析.
* [Zing Charts](https://www.zingchart.com/) - 用于大数据的JavaScript图表库.


## Internet of things and sensor data
* [Apache Edgent (Incubating)](http://edgent.apache.org/) - 编程模型和微内核样式运行时，可嵌入网关和小型边缘设备，在边缘设备上实现本地，实时分析.
* [Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) - 基于云的双向监控和消息中心
* [TempoIQ](https://www.tempoiq.com/) - 基于云的传感器分析.
* [2lemetry](http://2lemetry.com/) - 物联网平台.
* [Pubnub](https://www.pubnub.com/) - 数据流网络
* [ThingWorx](https://www.thingworx.com/) - 智能系统的快速开发和连接
* [IFTTT](https://ifttt.com/) - 如果这样那么
* [Evrything](https://evrythng.com/)- 使产品变得聪明
* [NetLytics](https://github.com/marty90/netlytics/) - 用于处理Spark网络数据的分析平台.

## Interesting Readings

* [Big Data Benchmark](https://amplab.cs.berkeley.edu/benchmark/) -  Redshift，Hive，Shark，Impala和Stiger / Tez的基准.
* [NoSQL Comparison](https://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis) -  Cassandra vs MongoDB vs CouchDB vs Redis vs Riak vs HBase vs Couchbase vs Neo4j vs Hypertable vs ElasticSearch vs Accumulo vs VoltDB vs Scalaris比较.
* [Monitoring Kafka performance](https://www.datadoghq.com/blog/monitoring-kafka-performance-metrics?ref=awesome) - 监控Apache Kafka的指南，包括用于度量收集的本机方法.
* [Monitoring Hadoop performance](https://www.datadoghq.com/blog/monitor-hadoop-metrics?ref=awesome) - 监控Hadoop的指南，概述了Hadoop架构，以及用于度量收集的本机方法.
* [Monitoring Cassandra performance](https://www.datadoghq.com/blog/how-to-monitor-cassandra-performance-metrics/?ref=awesome) - 监测Cassandra指南，包括指标收集的本地方法.

## Interesting Papers

### 2015 - 2016
* [2015](http://www.vldb.org/pvldb/vol8/p1804-ching.pdf) -  ** Facebook **  - 一万亿边缘：Facebook规模的图形处理.

### 2013 - 2014
* [2014](http://infolab.stanford.edu/~ullman/mmds/book.pdf) -  **斯坦福**  - 大规模数据集的挖掘.
* [2013](http://research.microsoft.com/pubs/200169/now-vldb.pdf) -  ** Microsoft **  - 云中大数据的可扩展渐进式分析.
* [2013](http://static.druid.io/docs/druid.pdf) -  ** Metamarkets **  - 德鲁伊：一个实时分析数据存储.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p764-rae.pdf) -  ** Google **  - 在线，F1中的异步架构更改.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p734-akidau.pdf) -  ** Google **  -  MillWheel：Internet规模的容错流处理.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p767-wiener.pdf) -  ** Facebook **  -  Scuba：在Facebook上潜入数据.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p871-curtiss.pdf) -  ** Facebook **  - 独角兽：搜索社交图的系统.
* [2013](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf) -  ** Facebook **  - 在Facebook上扩展Memcache.

### 2011 - 2012

* [2012](http://vldb.org/pvldb/vol5/p1771_georgelee_vldb2012.pdf) -  ** Twitter **  - 统一记录基础设施
在Twitter上进行数据分析.
* [2012](https://www.usenix.org/system/files/login/articles/zaharia.pdf) -  ** AMPLab **  - 使用Spark快速和交互式分析Hadoop数据.
* [2012](https://www.usenix.org/legacy/event/nsdi11/tech/full_papers/Bolosky.pdf) -  ** Microsoft **  -  Paxos复制状态机作为高性能数据存储的基础.
* [2012](http://research.microsoft.com/pubs/178045/ppaoxs-paper29.pdf) -  **微软**  -  Paxos Made Parallel.
* [2012](https://arxiv.org/pdf/1203.5485.pdf) -  ** AMPLab **  -  BlinkDB：​​对超大数据的有界错误和有限响应时间的查询.
* [2012](http://vldb.org/pvldb/vol5/p1436_alexanderhall_vldb2012.pdf) -  ** Google **  - 每次点击鼠标处理一万亿个单元格.

### 2001 - 2010

* [2010](https://www.usenix.org/legacy/event/osdi10/tech/full_papers/Beaver.pdf) -  ** Facebook **  - 在Haystack找到一针：Facebook的照片存储.
* [2010](http://kowshik.github.io/JPregel/pregel_paper.pdf) -  ** Google **  -  Pregel：用于大规模图形处理的系统.
* [2010](http://leoneu.github.io/) -  ** Yahoo **  -  S4：分布式流计算平台.
* [2009](http://www.vldb.org/pvldb/2/vldb09-861.pdf) - HadoopDB: An Architectural Hybrid of MapReduce and DBMS Technologies for Analytical Workloads.
* [2008](http://www.cca08.org/papers/Paper-13-Ariel-Rabkin.pdf) -  ** AMPLab **  -  Chukwa：一个大型监控系统.
* [2007](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/decandia07dynamo.pdf) -  **亚马逊**  -  Dynamo：亚马逊的高可用键值商店.

## Videos

* [Spark in Motion](https://www.manning.com/livevideo/spark-in-motion) -  Spark in Motion教您如何使用Spark进行批处理和流式数据分析.

## Books

#### Streaming
* [Data Science at Scale with Python and Dask](https://www.manning.com/books/data-science-at-scale-with-python-and-dask) - 使用Python和Dask进行规模化的数据科学教会您如何构建可处理大量数据的分布式数据项目.
* [Streaming Data](https://www.manning.com/books/streaming-data) -  Streaming Data介绍了流媒体和实时数据系统的概念和要求.
* [Storm Applied](https://www.manning.com/books/storm-applied) -  Storm Applied是使用Apache Storm处理与处理和分析实时数据流相关的实际任务的实用指南.
* [Fundamentals of Stream Processing: Application Design, Systems, and Analytics](http://www.cambridge.org/us/academic/subjects/engineering/communications-and-signal-processing/fundamentals-stream-processing-application-design-systems-and-analytics) - 这一全面的实用指南结合了基本构建模块和流处理方面的新兴研究，是应用程序设计人员，系统构建人员，分析开发人员以及该领域的学生和研究人员的理想选择.
* [Stream Data Processing: A Quality of Service Perspective](http://www.springer.com/us/book/9780387710020) - 提出适用于流和复杂事件处理的新范例.
* [Unified Log Processing](https://www.manning.com/books/event-streams-in-action) - 统一日志处理是实现业务中事件流（Kafka或Kinesis）统一日志的实用指南
* [Kafka Streams in Action](https://www.manning.com/books/kafka-streams-in-action) -  Kafka Streams in Action教您了解流入Kafka平台的数据流处理所需的一切，让您专注于从数据中获取更多信息，而不会浪费时间或精力.
* [Big Data](https://www.manning.com/books/big-data) - 大数据教您使用一种架构来构建大数据系统，该架构利用集群硬件以及专门用于捕获和分析Web级数据的新工具.
* [Spark in Action](https://www.manning.com/books/spark-in-action)   -  Spark in Action教您使用Spark有效处理批量和流数据所需的理论和技能.  完全更新Spark 2.0.
* [Kafka in Action](https://www.manning.com/books/kafka-in-action) -  Kafka in Action是一个快节奏的介绍，与Kafka合作的每个方面都需要真正获益.
* [Fusion in Action](https://www.manning.com/books/fusion-in-action) -  Fusion in Action教您构建功能齐全的数据分析管道，包括文档和数据搜索以及分布式数据集群.
* [Reactive Data Handling](https://www.manning.com/books/reactive-data-handling) -  Reactive Data Handling是由Manuel Bernhardt选择的五个精心挑选的章节的集合，它们向您介绍构建能够处理大数据负载的实时处理的反应式应用程序 - 免费电子书！ 

#### Distributed systems
* [Distributed Systems for fun and profit](http://book.mixu.net/distsys/)   - 分布式系统理论.  包括有关时间和排序，复制和不可能性结果的部分.

#### Graph Based approach
* [Graph-Powered Machine Learning](https://www.manning.com/books/graph-powered-machine-learning)   - 亚历山德罗·内格罗  结合图论和模型来改进机器学习项目

### Data Visualization
 * [The beauty of data visualization](https://www.youtube.com/watch?v=5Zg-C8AAIGg)
 * [Designing Data Visualizations with Noah Iliinsky](https://www.youtube.com/watch?v=R-oiKt7bUU8)
 * [Hans Rosling's 200 Countries, 200 Years, 4 Minutes](https://www.youtube.com/watch?v=jbkSRLYSojo)
 * [Ice Bucket Challenge Data Visualization](https://www.youtube.com/watch?v=qTEchen97rQ)


## Other Awesome Lists
- 其他很棒的清单 [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).
- 更多清单 [awesome](https://github.com/sindresorhus/awesome).
- 另一个清单？ [list](https://github.com/jnv/lists).
-  WTF！ [awesome-awesome-awesome](https://github.com/t3chnoboy/awesome-awesome-awesome).
- 分析 [awesome-analytics](https://github.com/onurakpolat/awesome-analytics).
- 公共数据集 [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets).
- 图形嵌入 [awesome-graph-embedding](https://github.com/benedekrozemberczki/awesome-graph-embedding).
- 网络嵌入 [awesome-network-embedding](https://github.com/chihming/awesome-network-embedding).
- 社区检测 [awesome-community-detection](https://github.com/benedekrozemberczki/awesome-community-detection).
