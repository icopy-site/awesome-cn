<div class="github-widget" data-repo="onurakpolat/awesome-bigdata"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Big Data

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的很棒的大数据框架，资源和其他很棒的清单. 受启发 [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [awesome-ruby](https://github.com/Sdogruyol/awesome-ruby), [hadoopecosystemtable](http://hadoopecosystemtable.github.io/) & [big-data](http://usefulstuff.io/big-data/).

永远欢迎您的贡献！


## RDBMS
* [MySQL](https://www.mysql.com/) 世界上最受欢迎的开源数据库.
* [PostgreSQL](https://www.postgresql.org/) 世界上最先进的开源数据库.
* [Oracle Database](http://www.oracle.com/us/corporate/features/database-12c/index.html) -对象关系数据库管理系统.
* [Teradata](http://www.teradata.com/products-and-services/teradata-database/) -高性能MPP数据仓库平台.

## Frameworks

* [Bistro](https://github.com/facebook/bistro)  -用于批处理和流分析的通用数据处理引擎. 它基于一种新颖的数据模型，该模型通过*函数*表示数据，并通过*列操作*处理数据，这与传统方法（如MapReduce或SQL）中仅具有设置操作相反.
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/)  -分布式处理和实时分析的平台. 与大数据生态系统中的许多流行技术集​​成（Kafka，HDFS，Spark等）
* [Apache Hadoop](http://hadoop.apache.org/)  -分布式处理的框架. 集成MapReduce（并行处理），YARN（作业调度）和HDFS（分布式文件系统）.
* [Tigon](https://github.com/caskdata/tigon) -高吞吐量实时流处理框架.
* [Pachyderm](http://pachyderm.io/) -Pachyderm是基于Docker和Kubernetes构建的数据存储平台，可提供可重现的数据处理和分析.
* [Polyaxon](https://github.com/polyaxon/polyaxon) -用于可重现和可扩展的机器学习和深度学习的平台.
* [Smooks](https://github.com/smooks/smooks) -用于构建XML和非XML（CSV，EDI，Java等）流应用程序的可扩展Java框架.

## Distributed Programming

* [AddThis Hydra](https://github.com/addthis/hydra) -最初由AddThis开发的分布式数据处理和存储系统.
* [AMPLab SIMR](http://databricks.github.io/simr/) -在Hadoop MapReduce v1上运行Spark.
* [Apache APEX](https://apex.apache.org/) -用于大数据流和批处理的统一企业平台.
* [Apache Beam](https://beam.apache.org/) -用于定义和执行数据处理工作流的统一模型和特定于语言的SDK集.
* [Apache Crunch](http://crunch.apache.org/) -一个简单的Java API，用于执行诸如加入和数据聚合之类的任务，这些任务很难在普通的MapReduce上实现.
* [Apache DataFu](http://incubator.apache.org/projects/datafu.html) -LinkedIn开发的Hadoop和Pig用户定义功能集合.
* [Apache Flink](http://flink.apache.org/) -高性能运行时和自动程序优化.
* [Apache Gearpump](http://gearpump.apache.org/) -基于Akka的实时大数据流引擎.
* [Apache Gora](http://gora.apache.org/) -内存中数据模型和持久性的框架.
* [Apache Hama](http://hama.apache.org/) -BSP（批量同步并行）计算框架.
* [Apache MapReduce](https://wiki.apache.org/hadoop/MapReduce/) -用于在集群上使用并行分布式算法处理大型数据集的编程模型.
* [Apache Pig](https://pig.apache.org/) -用于表达Hadoop数据分析程序的高级语言.
* [Apache REEF](http://reef.apache.org/) -可保留的评估程序执行框架，以简化和统一大数据系统的较低层.
* [Apache S4](http://incubator.apache.org/projects/s4.html) -用于流处理的框架，实现S4.
* [Apache Spark](http://spark.apache.org/) -内存中群集计算的框架.
* [Apache Spark Streaming](https://spark.apache.org/docs/latest/streaming-programming-guide.html) -流处理框架，Spark的一部分.
* [Apache Storm](http://storm.apache.org) -也可以在YARN上通过Twitter处理流的框架.
* [Apache Samza](http://samza.apache.org/) -基于Kafka和YARN的流处理框架.
* [Apache Tez](http://tez.apache.org/) -基于YARN构建的用于执行任务的复杂DAG（有向无环图）的应用程序框架.
* [Apache Twill](https://incubator.apache.org/projects/twill.html) -基于YARN的抽象，降低了开发分布式应用程序的复杂性.
* [Baidu Bigflow](http://bigflow.cloud/en/index.html) -允许编写分布式计算程序的接口，该程序提供许多简单，灵活，功能强大的API，可轻松处理任何规模的数据.
* [Cascalog](http://cascalog.org/) -数据处理和查询库.
* [Cheetah](http://vldbarc.org/pvldb/vldb2010/pvldb_vol3/I08.pdf) -基于MapReduce的高​​性能，自定义数据仓库.
* [Concurrent Cascading](http://www.cascading.org/) -Hadoop上的数据管理/分析框架.
* [Damballa Parkour](https://github.com/damballa/parkour) -Clojure的MapReduce库.
* [Datasalt Pangool](https://github.com/datasalt/pangool) -替代MapReduce范例.
* [DataTorrent StrAM](https://www.datatorrent.com/) -实时引擎旨在以尽可能不受阻碍的方式启用分布式，异步，实时内存中大数据计算，而开销却最小，并且对性能没有影响.
* [Facebook Corona](https://www.facebook.com/notes/facebook-engineering/under-the-hood-scheduling-mapreduce-jobs-more-efficiently-with-corona/10151142560538920) -Hadoop增强功能，可消除单点故障.
* [Facebook Peregrine](http://peregrine_mapreduce.bitbucket.org/) -Map Reduce框架.
* [Facebook Scuba](https://www.facebook.com/notes/facebook-engineering/under-the-hood-data-diving-with-scuba/10150599692628920) -分布式内存数据存储.
* [Google Dataflow](https://googledevelopers.blogspot.it/2014/06/cloud-platform-at-google-io-new-big.html) -创建数据管道以帮助他们评估，转换和分析数据.
* [Google MapReduce](https://research.google.com/archive/mapreduce.html) -地图减少框架.
* [Google MillWheel](https://research.google.com/pubs/pub41378.html) -容错流处理框架.
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/)  -分布式处理和实时分析的平台. 提供了用于高级分析（如地理空间，时间序列等）的工具箱.
* [JAQL](https://code.google.com/p/jaql/) -用于处理结构化，半结构化和非结构化数据的声明性编程语言.
* [Kite](http://kitesdk.org/docs/current/) -是一组库，工具，示例和文档，旨在简化在Hadoop生态系统之上构建系统的过程.
* [Metamarkets Druid](http://druid.io/) -大型数据集实时分析的框架.
* [Netflix PigPen](https://github.com/Netflix/PigPen) -Clojure的map-reduce，可编译为Apache Pig.
* [Nokia Disco](http://discoproject.org/) -诺基亚开发的MapReduce框架.
* [Onyx](http://www.onyxplatform.org/) -面向云的分布式计算.
* [Pinterest Pinlater](https://medium.com/@Pinterest_Engineering/pinlater-an-asynchronous-job-execution-system-b8664cb8aa7d) -异步作业执行系统.
* [Pydoop](http://crs4.github.io/pydoop/) -适用于Hadoop的Python MapReduce和HDFS API.
* [Ray](https://github.com/ray-project/ray) -用于构建和运行分布式应用程序的快速，简单的框架. 
* [Rackerlabs Blueflood](http://blueflood.io/) -多租户分布式度量处理系统
* [Skale](https://github.com/skale-me/skale-engine) -NodeJS中的高性能分布式数据处理.
* [Stratosphere](http://stratosphere.eu/) -通用集群计算框架.
* [Streamdrill](https://streamdrill.com/) -可用于统计事件流在不同时间窗口内的活动并找到最活跃的事件流.
* [streamsx.topology](https://github.com/IBMStreams/streamsx.topology) -支持在Java，Python或Scala中构建IBM Streams应用程序的库.
* [Tuktu](https://github.com/UnderstandLingBV/Tuktu) -使用Scala，Akka和Play构建的易于使用的批处理和流计算平台！
* [Twitter Heron](https://github.com/twitter/heron) -Heron是Twitter的实时，分布式，容错流处理引擎，取代了Storm.
* [Twitter Scalding](https://github.com/twitter/scalding) -基于Cascading构建的用于Map Reduce作业的Scala库.
* [Twitter Summingbird](https://github.com/twitter/summingbird) -通过Twitter流式传输带有缩放和风暴的MapReduce.
* [Twitter TSAR](https://blog.twitter.com/engineering/en_us/a/2014/tsar-a-timeseries-aggregator.html) -Twitter的TimeSeries AggregatoR.
* [Wallaroo](http://www.wallaroolabs.com/community)  -超快速，弹性的数据处理引擎. 大数据或快速数据-不必大惊小怪，不需要Java.

## Distributed Filesystem

* [Ambry](https://github.com/linkedin/ambry) -分布式对象存储，支持存储数万亿个小的不可变对象以及数十亿个大对象.
* [Apache HDFS](http://hadoop.apache.org/) -一种在多台计算机上存储大文件的方法.
* [Apache Kudu](http://kudu.apache.org/) -Hadoop的存储层，可对快速数据进行快速分析.
* [Ceph Filesystem](http://ceph.com/ceph-storage/file-system/) -设计了软件存储平台.
* [Disco DDFS](http://disco.readthedocs.org/en/latest/howto/ddfs.html) -分布式文件系统.
* [Facebook Haystack](https://www.facebook.com/note.php?note_id=76191543919) -对象存储系统.
* [Google Megastore](https://research.google.com/pubs/pub36971.html) -可扩展的高可用性存储.
* [GridGain](https://www.gridgain.com/) -GGFS，符合Hadoop的内存中文件系统.
* [Lustre file system](http://wiki.lustre.org/) -高性能的分布式文件系统.
* [Microsoft Azure Data Lake Store](https://hadoop.apache.org/docs/current/hadoop-azure-datalake/index.html) -Azure云中与HDFS兼容的存储
* [Quantcast File System QFS](https://www.quantcast.com/about-us/quantcast-file-system/) -开源分布式文件系统.
* [Red Hat GlusterFS](http://gluster.org/) -横向扩展网络附加存储文件系统.
* [Seaweed-FS](https://github.com/chrislusf/seaweedfs) -简单且高度可扩展的分布式文件系统.
* [Alluxio](http://www.alluxio.org/) -在群集框架之间以内存速度可靠地共享文件.
* [Tahoe-LAFS](https://www.tahoe-lafs.org/trac/tahoe-lafs) -分散式云存储系统.
* [Baidu File System](https://github.com/baidu/bfs) -分布式文件系统.

## Distributed Index

* [Pilosa](https://github.com/pilosa/pilosa) 开源分布式位图索引，可极大地加速跨多个海量数据集的查询. 

## Document Data Model

* [Actian Versant](https://www.actian.com/data-management/ingres-sql-rdbms/) -商业面向对象的数据库管理系统.
* [Crate Data](https://crate.io/)  -是开源的大规模可扩展数据存储. 它需要零管理.
* [Facebook Apollo](http://www.infoq.com/news/2014/06/facebook-apollo) -Facebook的类似Paxos的NoSQL数据库.
* [jumboDB](http://comsysto.github.io/jumbodb/) -通过Hadoop面向文档的数据存储.
* [LinkedIn Espresso](https://engineering.linkedin.com/data) -水平可扩展的面向文档的NoSQL数据存储.
* [MarkLogic](http://www.marklogic.com/) -与模式无关的企业NoSQL数据库技术.
* [Microsoft Azure DocumentDB](https://azure.microsoft.com/en-us/services/cosmos-db/) -带有对MongoDB的协议支持的NoSQL云数据库服务 
* [MongoDB](https://www.mongodb.com/) -面向文档的数据库系统.
* [RavenDB](https://ravendb.net/) -事务性，开放源代码的文档数据库.
* [RethinkDB](https://rethinkdb.com/) -支持诸如表联接和分组依据之类的查询的文档数据库.

## Key Map Data Model

 **注意**：行业中存在一些术语混乱，有两种不同的名称称为“列式数据库”. 这里列出的一些分布式持久数据库是围绕“键映射”数据模型构建的：所有数据都有一个（可能是复合的）键，键-值对映射与之关联. 在某些系统中，多个这样的值映射可以与一个键相关联，并且这些映射被称为“列族”（值映射键被称为“列”）.

另一组也可以称为“列数据库”的技术的区别在于，它是如何在磁盘或内存上存储数据的-而不是像传统方式那样将数据存储在给定键的所有列值彼此相邻的位置上，即“逐行”，这些系统将所有*列*值彼此相邻存储. 因此，需要更多的工作来获取给定键的所有列，但是需要更少的工作来获取给定列的所有值.

前一组在此称为“键映射数据模型”. 这些与 [Key-value Data Model](#key-value-data-model) 商店相当模糊.

后者是关于存储格式而不是数据模型，在下面列出 [Columnar Databases](#columnar-databases).

您可以在Daniel Abadi教授的博客上了解有关此区别的更多信息： [Distinguishing two major types of Column Stores](http://dbmsmusings.blogspot.com/2010/03/distinguishing-two-major-types-of_29.html).

* [Apache Accumulo](http://accumulo.apache.org/) -建立在Hadoop上的分布式键/值存储.
* [Apache Cassandra](http://cassandra.apache.org/) -受BigTable启发的面向列的分布式数据存储.
* [Apache HBase](http://hbase.apache.org/) -受BigTable启发的面向列的分布式数据存储.
* [Baidu Tera](https://github.com/baidu/tera) -受BigTable启发的互联网规模的数据库.
* [Facebook HydraBase](https://code.facebook.com/posts/321111638043166/hydrabase-the-evolution-of-hbase-facebook/) -Facebook开发的HBase的演变.
* [Google Cloud Datastore](https://cloud.google.com/datastore/docs/concepts/overview) -是一个完全托管的无模式数据库，用于通过BigTable存储非关系数据.
* [Hypertable](http://www.hypertable.org/) -受BigTable启发的面向列的分布式数据存储.
* [InfiniDB](https://github.com/infinidb/infinidb/) -通过MySQL接口访问，并使用大量并行处理来并行化查询.
* [Tephra](https://github.com/caskdata/tephra) -HBase的交易.
* [Twitter Manhattan](https://blog.twitter.com/engineering/en_us/a/2014/manhattan-our-real-time-multi-tenant-distributed-database-for-twitter-scale.html) -用于Twitter规模的实时，多租户分布式数据库.
* [ScyllaDB](http://www.scylladb.com/) -用C ++编写的面向列的分布式数据存储，与Apache Cassandra完全兼容.


## Key-value Data Model

* [Aerospike](http://www.aerospike.com/)  -NoSQL闪存优化的内存. 开源和“对C语言中的服务器代码（不是J​​ava或Erlang）进行了精确调整，以避免上下文切换和内存复制.”
* [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) -分布式键/值存储，Dynamo纸的实现.
* [Badger](https://open.dgraph.io/post/badger/) -使用Go原生编写的快速，简单，高效且持久的键值存储.
* [Bolt](https://github.com/boltdb/bolt) -Go的嵌入式键值数据库.
* [BTDB](https://github.com/Bobris/BTDB) -具有对象数据库层，RPC，动态IL等的.Net中的键值数据库
* [BuntDB](https://github.com/tidwall/buntdb) -Go的快速，可嵌入的内存中键/值数据库，具有自定义索引和地理空间支持.
* [Edis](https://github.com/cbd/edis) -是Redis的协议兼容服务器替代品.
* [ElephantDB](https://github.com/nathanmarz/elephantdb) -专门用于从Hadoop导出数据的分布式数据库.
* [EventStore](https://geteventstore.com/) -分布式时间序列数据库.
* [GhostDB](https://github.com/jakekgrog/GhostDB) -分布式，内存中的通用键值数据存储，可在任何规模上提供微秒级的性能.
* [Graviton](https://github.com/deroproject/graviton) -一个纯Go（lang）中的简单，快速，版本控制，已认证，可嵌入的键值存储数据库.
* [GridDB](https://github.com/griddb/griddb_nosql) -适用于按时间序列存储的传感器数据.
* [HyperDex](https://github.com/rescrv/HyperDex) -具有各种功能（包括一致性，容错性和高性能）的可扩展的下一代键值和文档存储.
* [Ignite](https://ignite.apache.org/index.html) -是一个内存中的键值数据存储，提供了完全符合SQL的数据访问权限，可以选择由磁盘存储支持.
* [LinkedIn Krati](https://github.com/linkedin-sna/sna-page/tree/master/krati) -是一个简单的持久数据存储，具有非常低的延迟和高吞吐量.
* [Linkedin Voldemort](http://www.project-voldemort.com/voldemort/) -分布式键/值存储系统.
* [Oracle NoSQL Database](http://www.oracle.com/technetwork/database/database-technologies/nosqldb/overview/index.html) -由Oracle Corporation提供的分布式键值数据库.
* [Redis](https://redis.io/) -在内存键值数据存储区中.
* [Riak](https://github.com/basho/riak) -分散的数据存储.
* [Storehaus](https://github.com/twitter/storehaus) -通过Twitter与异步键值存储一起使用的库.
* [SummitDB](https://github.com/tidwall/summitdb) -内存中的NoSQL键/值数据库，具有磁盘持久性并使用Raft共识算法.
* [Tarantool](https://github.com/tarantool/tarantool) -高效的NoSQL数据库和Lua应用程序服务器.
* [TiKV](https://github.com/pingcap/tikv) -由Rust提供动力并受Google Spanner和HBase启发的分布式键值数据库.
* [Tile38](https://github.com/tidwall/tile38) -地理位置数据存储，空间索引和实时地理围栏，支持多种对象类型，包括纬度/经度点，边界框，XYZ磁贴，地理哈希和GeoJSON
* [TreodeDB](https://github.com/Treode/store) -键值存储，已复制和分片，并提供原子多行写入.


## Graph Data Model

* [AgensGraph](http://www.agensgraph.com/) -用于现代复杂数据环境的新一代多模型图形数据库.
* [Apache Giraph](http://giraph.apache.org/) -基于Hadoop的Pregel的实现.
* [Apache Spark Bagel](http://spark.apache.org/docs/0.7.3/bagel-programming-guide.html) -实现Pregel（Spark的一部分）.
* [ArangoDB](https://www.arangodb.com/) -多模型分布式数据库.
* [DGraph](https://github.com/dgraph-io/dgraph) -可扩展，分布式，低延迟，高吞吐量的图形数据库，旨在提供Google生产级别的规模和吞吐量，并具有足够低的延迟以服务于TB级结构化数据的实时用户查询.
* [EliasDB](https://github.com/krotik/eliasdb) -基于轻量级图的数据库，不需要任何第三方库.
* [Facebook TAO](https://www.facebook.com/notes/facebook-engineering/tao-the-power-of-the-graph/10151525983993920) -TAO是分布式数据存储，在Facebook上广泛用于存储和服务社交图.
* [GCHQ Gaffer](https://github.com/gchq/Gaffer) -GCHQ的Gaffer是一个框架，可以轻松存储其中节点和边具有统计信息的大规模图形.
* [Google Cayley](https://github.com/cayleygraph/cayley) -开源图形数据库.
* [Google Pregel](http://kowshik.github.io/JPregel/pregel_paper.pdf) -图形处理框架.
* [GraphLab PowerGraph](https://turi.com/products/create/docs/) -核心C ++ GraphLab API和在GraphLab API之上构建的高性能机器学习和数据挖掘工具包的集合.
* [GraphX](https://amplab.cs.berkeley.edu/publication/graphx-grades/) -Spark上的弹性分布式图系统.
* [Gremlin](https://github.com/tinkerpop/gremlin) -图形遍历语言.
* [Infovore](https://github.com/paulhoule/infovore) -以RDF为中心的Map / Reduce框架.
* [Intel GraphBuilder](https://01.org/graphbuilder/) -在Hadoop之上构建大规模图形的工具.
* [JanusGraph](http://janusgraph.org) -开源的分布式图形数据库
  具有用于存储后端的多个选项（Bigtable，HBase，Cassandra等）
  和索引后端（Elasticsearch，Solr，Lucene）.
* [MapGraph](https://www.blazegraph.com/mapgraph-technology/) -在GPU上进行大规模并行图处理.
* [Microsoft Graph Engine](https://github.com/Microsoft/GraphEngine) -分布式内存数据处理引擎，以强类型的内存键值存储和通用分布式计算引擎为基础.
* [Neo4j](https://neo4j.com/) -图形数据库完全用Java编写.
* [OrientDB](http://orientdb.com/) -文档和图形数据库.
* [Phoebus](https://github.com/xslogic/phoebus) -大规模图形处理的框架.
* [Titan](http://thinkaurelius.github.io/titan/) -基于Cassandra构建的分布式图形数据库.
* [Twitter FlockDB](https://github.com/twitter-archive/flockdb) -分布式图形数据库.
* [NodeXL](https://nodexl.codeplex.com/) -适用于Microsoft®Excel®2007、2010、2013和2016的免费开放源代码模板，可轻松浏览网络图.


## Columnar Databases

**注意**请阅读以下说明 [Key-Map Data Model](#key-map-data-model) 部分.

* [Columnar Storage](http://the-paper-trail.org/blog/columnar-storage/) -关于什么是柱状存储以及何时需要的说明.
* [Actian Vector](http://www.actian.com/) - column-oriented analytic database.
* [ClickHouse](https://clickhouse.yandex/) -面向列的开源数据库管理系统，可实时生成分析数据报告.
* [EventQL](http://eventql.io/) -为大型事件收集和分析而构建的分布式，面向列的数据库.
* [MonetDB](https://www.monetdb.org/) -列存储数据库.
* [Parquet](http://parquet.apache.org/) -Hadoop的列式存储格式.
* [Pivotal Greenplum](https://pivotal.io/pivotal-greenplum) -专用的专用分析数据仓库，提供了列式引擎以及传统的基于行的引擎.
* [Vertica](https://www.vertica.com/) -用于管理大量，快速增长的数据，并在用于数据仓库时提供非常快的查询性能.
* [SQream DB](http://sqream.com/) -由GPU驱动的大数据数据库，专为分析和数据仓库而设计，具有符合ANSI-92的SQL，适用于从10TB到1PB的数据集.
* [Google BigQuery](https://cloud.google.com/bigquery/what-is-bigquery) -Google在Dremel上的开拓性工作为后盾的云产品.
* [Amazon Redshift](https://aws.amazon.com/redshift/) -亚马逊的云产品，也基于列式数据存储后端.
* [IndexR](https://github.com/shunfei/indexr) -一种开源的列式存储格式，用于大数据的快速实时分析.
* [LocustDB](https://github.com/cswinter/LocustDB) -实验性分析数据库，旨在为商品硬件的查询性能树立新标准. 

## NewSQL Databases

* [Actian Ingres](http://www.actian.com/products/operational-databases/) -商业支持的开源SQL关系数据库管理系统.
* [ActorDB](https://github.com/biokoda/actordb) -具有KV存储可伸缩性的分布式SQL数据库，同时保留了关系数据库的查询功能.
* [Amazon RedShift](http://aws.amazon.com/redshift/) -基于PostgreSQL的数据仓库服务.
* [BayesDB](https://github.com/probcomp/BayesDB) -面向统计的SQL数据库.
* [Bedrock](http://bedrockdb.com/) -建立在SQLite之上的简单，模块化，网络化和分布式事务层.
* [CitusDB](https://www.citusdata.com/) -通过分片和复制来扩展PostgreSQL.
* [Cockroach](https://github.com/cockroachdb/cockroach) -可扩展，地理复制，事务性数据存储.
* [Comdb2](https://github.com/bloomberg/comdb2) -基于乐观并发控制技术构建的集群RDBMS.
* [Datomic](http://www.datomic.com/) -旨在支持可扩展，灵活和智能应用程序的分布式数据库.
* [FoundationDB](https://foundationdb.com/) -受F1启发的分布式数据库.
* [Google F1](https://research.google.com/pubs/pub41344.html) -建立在Spanner上的分布式SQL数据库.
* [Google Spanner](https://research.google.com/archive/spanner.html) -全球分布的半关系数据库.
* [H-Store](http://hstore.cs.brown.edu/) -是一个实验性的主内存并行数据库管理系统，针对在线事务处理（OLTP）应用进行了优化.
* [Haeinsa](https://github.com/VCNC/haeinsa) -基于Percolator的HBase的线性可扩展多行，多表事务库.
* [HandlerSocket](https://www.percona.com/doc/percona-server/5.5/performance/handlersocket.html) -适用于MySQL / MariaDB的NoSQL插件.
* [InfiniSQL](http://www.infinisql.org/) -无限可扩展的RDBMS.
* [KarelDB](https://github.com/rayokota/kareldb) -由Apache Kafka支持的关系数据库.
* [Map-D](https://www.mapd.com/) -GPU内存数据库，大数据分析和可视化平台.
* [MemSQL](http://www.memsql.com/) -内存中的SQL数据库，具有优化的Flash列式存储.
* [NuoDB](http://www.nuodb.com/) -符合SQL / ACID的分布式数据库.
* [Oracle TimesTen in-Memory Database](http://www.oracle.com/technetwork/database/database-technologies/timesten/overview/index.html) -具有持久性和可恢复性的内存中关系数据库管理系统.
* [Pivotal GemFire XD](http://gemfirexd.docs.pivotal.io/latest/)  -低延迟，内存中的分布式SQL数据存储. 提供内存中表数据的SQL接口，可持久存储在HDFS中.
* [SAP HANA](https://hana.sap.com/abouthana.html) -是一个内存，面向列的关系数据库管理系统.
* [SenseiDB](http://senseidb.github.io/sensei/) -分布式，实时，半结构化数据库.
* [Sky](http://skydb.io/) -用于行为数据的灵活，高性能分析的数据库.
* [SymmetricDS](http://www.symmetricds.org/) -用于文件和数据库同步的开源软件.
* [TiDB](https://github.com/pingcap/tidb)  -TiDB是分布式SQL数据库. 受到Google F1设计的启发.
* [VoltDB](https://www.voltdb.com/) -声称是最快的内存数据库.
* [yugabyteDB](https://github.com/YugaByte/yugabyte-db) - open source, high-performance, distributed SQL database compatible with PostgreSQL.

## Time-Series Databases

* [Axibase Time Series Database](http://axibase.com/products/axibase-time-series-database/) -在HBase之上的集成时间序列数据库，具有内置的可视化，规则引擎和SQL支持.
* [Chronix](http://chronix.io/) -时间序列存储，用于存储高度压缩的时间序列和快速访问时间.
* [Cube](http://square.github.io/cube/) -使用MongoDB存储时间序列数据.
* [Heroic](https://spotify.github.io/heroic/#!/index) -是基于Cassandra和Elasticsearch的可伸缩时间序列数据库.
* [InfluxDB](https://questdb.io/) -具有优化的IO和查询的时间序列数据库，支持pgsql和influx有线协议.
* [QuestDB](https://www.influxdata.com/) -分布式时间序列数据库.
* [IronDB](https://www.circonus.com/irondb/) -可扩展的通用时间序列数据库.
* [Kairosdb](https://github.com/kairosdb/kairosdb) -与OpenTSDB相似，但允许使用Cassandra.
* [M3DB](http://m3db.github.io/m3/m3db/) -分布式时间序列数据库，可用于长时间保留存储实时指标.
* [Newts](https://opennms.github.io/newts/) -基于Apache Cassandra的时间序列数据库.
* [TDengine](https://github.com/taosdata/TDengine/) -利用IoT的独特功能以C语言编写的时间序列数据库，以提高读/写吞吐量并减少存储数据所需的空间
* [OpenTSDB](http://opentsdb.net) -在HBase之上的分布式时间序列数据库.
* [Prometheus](https://prometheus.io/) -时间序列数据库和服务监视系统.
* [Beringei](https://github.com/facebookincubator/beringei) -Facebook的内存时间序列数据库.
* [TrailDB](http://traildb.io/) -用于存储和查询一系列事件的有效工具.
* [Druid](https://github.com/druid-io/druid/) 面向列的分布式数据存储，是为交互式应用程序提供动力的理想选择
* [Riak-TS](http://basho.com/products/riak-ts/) Riak TS是唯一专门针对IoT和时间序列数据进行优化的企业级NoSQL时间序列数据库.
* [Akumuli](https://github.com/akumuli/Akumuli)  Akumuli是一个数字时间序列数据库. 它可以用于实时捕获，存储和处理时间序列数据. 单词“ akumuli”可以从世界语翻译为“积累”.
* [Rhombus](https://github.com/Pardot/Rhombus) Cassandra的时间序列对象存储，处理构建宽行索引的所有复杂性.
* [Dalmatiner DB](https://github.com/dalmatinerdb/dalmatinerdb) 快速分布式指标数据库
* [Blueflood](https://github.com/rackerlabs/blueflood) 旨在吸收和处理时间序列数据的分布式系统
* [Timely](https://github.com/NationalSecurityAgency/timely) Timely是一个时间序列数据库应用程序，可提供对Accumulo和Grafana的时间序列数据的安全访问.
* [SiriDB](https://github.com/transceptor-technology/siridb-server) 具有集群功能的高度可扩展，健壮和快速的开源时间序列数据库.
* [Thanos](https://github.com/improbable-eng/thanos) -Thanos是一组组件，可使用多个（现有）Prometheus部署来创建具有无限存储容量的高可用性度量标准系统.
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics)  -与Prometheus兼容的快速，可扩展且资源有效的开源TSDB. 包括单节点和集群版本

## SQL-like processing

* [Actian SQL for Hadoop](http://www.actian.com/analytic-database/vectorh-sql-hadoop) -对所有Hadoop数据的高性能交互式SQL访问.
* [Apache Drill](http://drill.apache.org/) -互动分析的框架，受Dremel的启发.
* [Apache HCatalog](https://cwiki.apache.org/confluence/display/Hive/HCatalog) -Hadoop的表和存储管理层.
* [Apache Hive](http://hive.apache.org/) -用于Hadoop的类似SQL的数据仓库系统.
* [Apache Calcite](http://calcite.apache.org/) -允许有效翻译涉及异构数据和联合数据的查询的框架.
* [Apache Phoenix](http://phoenix.apache.org/index.html) -HBase上的SQL外观.
* [Aster Database](http://www.teradata.com/products-and-services/Teradata-Aster/teradata-aster-database) -MapReduce的类似SQL的分析处理.
* [Cloudera Impala](https://www.cloudera.com/products/apache-hadoop/impala.html) -互动分析框架，受Dremel启发.
* [Concurrent Lingual](http://www.cascading.org/projects/lingual/) -级联的类似SQL的查询语言.
* [Datasalt Splout SQL](http://www.datasalt.com/products/splout-sql/) -适用于大型数据集的完整SQL查询引擎.
* [Dremio](https://www.dremio.com/) -基于Apache Arrow的开源，类似SQL的数据即服务平台.
* [Facebook PrestoDB](https://prestodb.io/) -分布式SQL查询引擎.
* [Google BigQuery](https://research.google.com/pubs/pub36632.html) -交互式分析框架，实现Dremel.
* [Materialize](https://github.com/materializeinc/materialize) -是使用SQL进行查询并支持大部分PostgreSQL的实时应用程序的流数据库.
* [Invantive SQL](https://documentation.invantive.com/2017R2/invantive-sql-grammar/invantive-sql-grammar-17.30.html) -在线和本地使用的SQL引擎，带有集成的本地数据复制和70多个连接器.
* [PipelineDB](https://www.pipelinedb.com/) -一个开放源代码关系数据库，该数据库在流上连续运行SQL查询，并将结果增量存储在表中.
* [Pivotal HDB](https://pivotal.io/pivotal-hdb) -用于Hadoop的类似SQL的数据仓库系统.
* [RainstorDB](http://rainstor.com/products/rainstor-database/) -用于存储PB级结构化和半结构化数据量的数据库.
* [Spark Catalyst](https://github.com/apache/spark/tree/master/sql) -是Spark和Shark的查询优化框架.
* [SparkSQL](https://databricks.com/blog/2014/03/26/spark-sql-manipulating-structured-data-using-spark-2.html) -使用Spark操纵结构化数据.
* [Splice Machine](https://www.splicemachine.com/) -具有ACID事务的全功能SQL-on-Hadoop RDBMS.
* [Stinger](https://hortonworks.com/innovation/stinger/) -Hive的交互式查询.
* [Tajo](http://tajo.apache.org/) -Hadoop上的分布式数据仓库系统.
* [Trafodion](https://wiki.trafodion.org/wiki/index.php/Main_Page) -针对大数据事务或运营工作负载的企业级HBase on SQL on HBase解决方案.

## Data Ingestion
* [redpanda](https://vectorized.io/redpanda)  -用于关键任务系统的Kafka®替代品； 快10倍. 用C ++编写.
* [Amazon Kinesis](https://aws.amazon.com/kinesis/) -大规模实时处理流数据.
* [Amazon Web Services Glue](https://aws.amazon.com/glue/) -无服务器的完全托管的提取，转换和加载（ETL）服务
* [Census](https://getcensus.com/)  -反向ETL产品，使您可以将数据仓库中的数据同步到SaaS应用程序. 不需要任何工程支持，只需SQL.
* [Apache Chukwa](http://chukwa.apache.org/) -数据收集系统.
* [Apache Flume](http://flume.apache.org/) -用于管理大量日志数据的服务.
* [Apache Kafka](http://kafka.apache.org/) -分布式发布-订阅消息系统.
* [Apache NiFi](https://nifi.apache.org/) -Apache NiFi是一个集成的数据物流平台，用于自动化不同系统之间的数据移动.
* [Apache Pulsar](https://github.com/apache/pulsar) -具有非常灵活的消息传递模型和直观的客户端API的分布式pub-sub消息传递平台.
* [Apache Sqoop](http://sqoop.apache.org/) -在Hadoop和结构化数据存储之间传输数据的工具.
* [Embulk](http://www.embulk.org) -开源批量数据加载器，可帮助在各种数据库，存储，文件格式和云服务之间进行数据传输.
* [Facebook Scribe](https://github.com/facebookarchive/scribe) -流式日志数据聚合器.
* [Fluentd](http://www.fluentd.org) -收集事件和日志的工具.
* [Gazette](https://github.com/gazette/core) -建立在云存储上的分布式流式基础架构，可轻松混合和匹配批处理和流式范例.
* [Google Photon](https://research.google.com/pubs/pub41318.html) -地理上分散的系统，用于以高可伸缩性和低延迟实时地连接多个连续流动的数据流.
* [Heka](https://github.com/mozilla-services/heka) -开源流处理软件系统.
* [HIHO](https://github.com/sonalgoyal/hiho) -用于将不同的数据源与Hadoop连接的框架.
* [Kestrel](https://github.com/papertrail/kestrel) -分布式消息队列系统.
* [LinkedIn Databus](https://engineering.linkedin.com/data) -数据库的更改捕获事件流.
* [LinkedIn Kamikaze](https://github.com/linkedin/kamikaze) -用于压缩排序的整数数组的实用程序包.
* [LinkedIn White Elephant](https://github.com/linkedin/white-elephant) -日志聚合器和仪表板.
* [Logstash](https://www.elastic.co/products/logstash) -用于管理事件和日志的工具.
* [Netflix Suro](https://github.com/Netflix/suro) -基于Chukwa的日志聚合器，例如Storm和Samza.
* [Pinterest Secor](https://github.com/pinterest/secor) -是实现Kafka日志持久性的服务.
* [Linkedin Gobblin](https://github.com/linkedin/gobblin) -linkedin的通用数据摄取框架.
* [Skizze](https://github.com/skizzehq/skizze) -草图数据存储区，用于处理使用概率数据结构进行计数和草图绘制时遇到的所有问题.
* [StreamSets Data Collector](https://github.com/streamsets/datacollector) -使用简单易用的IDE连续获取大数据.
* [Alooma](https://www.alooma.com/integrations/mysql) -数据管道即服务，可将MySQL等数据源移动到数据仓库中.
* [RudderStack](https://github.com/rudderlabs/rudder-server) -用go语言编写的开源客户数据基础结构（细分，mParticle替代品）.

## Service Programming

* [Akka Toolkit](http://akka.io/) -JVM上分布式和容错事件驱动的应用程序的运行时.
* [Apache Avro](http://avro.apache.org/) -数据序列化系统.
* [Apache Curator](http://curator.apache.org/) -Apache ZooKeeper的Java库.
* [Apache Karaf](http://karaf.apache.org/) -在任何OSGi框架之上运行的OSGi运行时.
* [Apache Thrift](http://thrift.apache.org//) -建立二进制协议的框架.
* [Apache Zookeeper](http://zookeeper.apache.org/) -用于流程管理的集中服务.
* [Google Chubby](https://research.google.com/archive/chubby.html) -松耦合的分布式系统的锁定服务.
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) -一种用于将Apache Spark分析作业和机器学习模型公开为实时，批处理或反应式Web服务的服务.
* [Linkedin Norbert](https://engineering.linkedin.com/data) -集群管理器.
* [Mara](https://github.com/mara/data-integration) -轻量级的，有思想的ETL框架，介于纯脚本和Apache Airflow之间
* [OpenMPI](https://www.open-mpi.org/) -消息传递框架.
* [Serf](https://www.serf.io/) -用于服务发现和编排的分散式解决方案.
* [Spotify Luigi](https://github.com/spotify/luigi)  -一个Python软件包，用于构建批处理作业的复杂管道. 它处理依赖关系解析，工作流管理，可视化，处理故障，命令行集成等.
* [Spring XD](https://github.com/spring-projects/spring-xd) -用于数据提取，实时分析，批处理和数据导出的分布式和可扩展系统.
* [Twitter Elephant Bird](https://github.com/twitter/elephant-bird) -用于处理LZOP压缩数据的库.
* [Twitter Finagle](https://twitter.github.io/finagle/) -JVM的异步网络堆栈.

## Scheduling

* [Apache Airflow](https://github.com/apache/incubator-airflow) -以编程方式创作，安排和监视工作流的平台.
* [Apache Aurora](http://aurora.apache.org/) -是在Apache Mesos之上运行的服务调度程序.
* [Apache Falcon](http://falcon.apache.org/) -数据管理框架.
* [Apache Oozie](http://oozie.apache.org/) -工作流程作业计划程序.
* [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/data-factory-introduction) -用于本地，云和HDInsight的基于云的管道编排
* [Chronos](http://mesos.github.io/chronos/) -分布式且容错的调度程序.
* [Cronicle](https://github.com/jhuckaby/Cronicle) -分布式，易于安装，基于NodeJS的任务计划程序
* [Dagster](https://github.com/dagster-io/dagster) -用于机器学习，分析和ETL的数据协调器.
* [Linkedin Azkaban](https://azkaban.github.io/) -批处理工作流作业计划程序.
* [Schedoscope](https://github.com/ottogroup/schedoscope) -Scala DSL，用于Hadoop作业的敏捷调度.
* [Sparrow](https://github.com/radlab/sparrow) -调度平台.


## Machine Learning

* [Azure ML Studio](https://studio.azureml.net/) -基于云的AzureML，R，Python机器学习平台
* [brain](https://github.com/harthur/brain) -JavaScript中的神经网络.
* [Oryx](https://github.com/OryxProject/oryx) -Apache Spark，Apache Kafka上的Lambda体系结构，用于实时大规模机器学习.
* [Concurrent Pattern](http://www.cascading.org/projects/pattern/) -用于级联的机器学习库.
* [convnetjs](https://github.com/karpathy/convnetjs)  -使用Java进行深度学习. 在浏览器中训练卷积神经网络（或普通的）.
* [DataVec](https://github.com/deeplearning4j/DataVec)  -用于Java和Scala中的深度学习的矢量化和数据预处理库.  Deeplearning4j生态系统的一部分. 
* [Deeplearning4j](https://github.com/deeplearning4j)  -JVM（Java，Scala，Clojure）的快速，开放式深度学习. 由C ++库提供支持的神经网络配置层. 使用Spark和Hadoop在多个GPU和CPU上训练网络.
* [Decider](https://github.com/danielsdeleo/Decider) -Ruby中的灵活和可扩展的机器学习.
* [ENCOG](http://www.heatonresearch.com/encog/) -支持各种高级算法的机器学习框架，以及支持对数据进行规范化和处理的类.
* [etcML](http://www.etcml.com/) -通过机器学习进行文本分类.
* [Etsy Conjecture](https://github.com/etsy/Conjecture) -可扩展的可扩展机器学习.
* [Feast](https://github.com/gojek/feast)  -用于管理，发现和访问机器学习功能的功能存储.  Feast可为模型训练和模型服务提供一致的特征数据视图.
* [GraphLab Create](https://dato.com/products/create/) -Python中的机器学习平台，其中包含大量ML工具包，数据工程和部署工具.
* [H2O](https://github.com/h2oai/h2o-3/)  -使用Hadoop进行统计，机器学习和数学运行时.  R和Python.
* [Karate Club](https://github.com/benedekrozemberczki/karateclub)  -用于图形结构化数据的无监督机器学习库.  Python
* [Keras](https://github.com/fchollet/keras) -受Torch启发的直观神经网络API，运行在Theano和Tensorflow之上.
* [Lambdo](https://github.com/johnsonc/lambdo) -Lambdo是一种工作流程引擎，通过统一特征工程和机器学习操作，大大简化了分析过程.
* [Little Ball of Fur](https://github.com/benedekrozemberczki/littleballoffur)  -用于图结构化数据的子采样库.  Python
* [Mahout](http://mahout.apache.org/) -Apache支持的Hadoop机器学习库.
* [MLbase](http://www.mlbase.org/) -用于BDAS堆栈的分布式机器学习库.
* [MLPNeuralNet](https://github.com/nikolaypavlov/MLPNeuralNet) -适用于iOS和Mac OS X的快速多层感知器神经网络库.
* [ML Workspace](https://github.com/ml-tooling/ml-workspace) -专为机器学习和数据科学而设计的基于Web的多合一IDE.
* [MOA](http://moa.cms.waikato.ac.nz) -MOA实时执行大数据流挖掘，并进行大规模机器学习.
* [MonkeyLearn](https://monkeylearn.com/)  -文本挖掘变得容易. 从文本中提取和分类数据.
* [ND4J](https://github.com/deeplearning4j/nd4j)  -JVM的矩阵库.  Numpy for Java. 
* [nupic](https://github.com/numenta/nupic) -Numenta智能计算平台：一个受大脑启发的机器智能平台，以及基于皮层学习算法的生物精确的神经网络.
* [PredictionIO](http://predictionio.incubator.apache.org/index.html) -在Hadoop，Mahout和Cascading上的机器学习服务器.
* [PyTorch Geometric Temporal](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) -PyTorch几何图形的时间扩展库.
* [RL4J](https://github.com/deeplearning4j/rl4j)  -Java和Scala的强化学习. 包括Deep-Q学习和A3C算法，并与Open AI的Gym集成. 在Deeplearning4j生态系统中运行. 
* [SAMOA](http://samoa.incubator.apache.org/) -分布式流机器学习框架.
* [scikit-learn](https://github.com/scikit-learn/scikit-learn) -scikit-learn：Python中的机器学习.
* [Shapley](https://github.com/benedekrozemberczki/shapley) -数据驱动的框架，用于量化机器学习集合中分类器的价值. 
* [Spark MLlib](http://spark.apache.org/docs/0.9.0/mllib-guide.html) -一些常见机器学习（ML）功能的Spark实现.
* [Sibyl](https://users.soe.ucsc.edu/~niejiazhong/slides/chandra.pdf) -Google的大规模机器学习系统.
* [TensorFlow](https://github.com/tensorflow/tensorflow) -Google的库，用于使用数据流图进行机器学习.
* [Theano](https://github.com/theano) -蒙特利尔大学支持的以Python为中心的机器学习库.
* [Torch](https://github.com/torch) -带有Lua API的深度学习库，由纽约大学和Facebook支持.
* [Velox](https://github.com/amplab/velox-modelserver) -用于提供机器学习预测的系统.
* [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/wiki) -由Microsoft和Yahoo!赞助的学习系统.
* [WEKA](http://www.cs.waikato.ac.nz/ml/weka/) -机器学习软件套件.
* [BidMach](https://github.com/BIDData/BIDMach) -CPU和GPU加速的机器学习库.

## Benchmarking

* [Apache Hadoop Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-3561) -用于测试Hadoop性能的微型基准.
* [Berkeley SWIM Benchmark](https://github.com/SWIMProjectUCB/SWIM/wiki) -实际的大数据工作负载基准.
* [Intel HiBench](https://github.com/intel-hadoop/HiBench) -Hadoop基准套件.
* [PUMA Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-5116) -适用于MapReduce应用程序的基准套件.
* [Yahoo Gridmix3](http://yahoohadoop.tumblr.com/post/98294079296/gridmix3-emulating-production-workload-for) -来自Yahoo工程师团队的Hadoop集群基准测试.
* [Deeplearning4j Benchmarks](https://github.com/deeplearning4j/dl4j-benchmark)

## Security
* [Apache Ranger](http://ranger.apache.org/) - Central security admin & fine-grained authorization for Hadoop
* [Apache Eagle](http://eagle.apache.org/) -实时监控解决方案
* [Apache Knox Gateway](http://knox.apache.org/) -Hadoop集群的单点安全访问.
* [Apache Sentry](http://incubator.apache.org/projects/sentry.html) -用于存储在Hadoop中的数据的安全模块.
* [BDA](https://github.com/kotobukki/BDA/) -Hadoop和Spark的漏洞检测器

## System Deployment

* [Apache Ambari](http://ambari.apache.org/) -Hadoop管理的操作框架.
* [Apache Bigtop](http://bigtop.apache.org//) -Hadoop生态系统的系统部署框架.
* [Apache Helix](http://helix.apache.org/) -集群管理框架.
* [Apache Mesos](http://mesos.apache.org/) -集群管理器.
* [Apache Slider](https://github.com/apache/incubator-slider) -是一个YARN应用程序，用于在YARN上部署现有的分布式应用程序.
* [Apache Whirr](http://whirr.apache.org/) -用于运行云服务的库集.
* [Apache YARN](https://hortonworks.com/hadoop/yarn/) -集群管理器.
* [Brooklyn](http://brooklyncentral.github.io/) -简化应用程序部署和管理的库.
* [Buildoop](http://buildoop.github.io/) -与基于Groovy语言的Apache BigTop相似.
* [Cloudera HUE](http://gethue.com/) -用于与Hadoop交互的Web应用程序.
* [Facebook Prism](http://www.wired.com/2012/08/facebook-prism/) -多数据中心复制系统.
* [Google Borg](https://www.wired.com/2013/03/google-borg-twitter-mesos/all/) -作业计划和监控系统.
* [Google Omega](https://www.youtube.com/watch?v=0ZFMlO98Jkc) -作业计划和监控系统.
* [Hortonworks HOYA](https://hortonworks.com/blog/introducing-hoya-hbase-on-yarn/) -可以在YARN上部署HBase群集的应用程序.
* [Kubernetes](https://kubernetes.io/) -用于自动化容器化应用程序的部署，扩展和管理的系统.
* [Marathon](https://github.com/mesosphere/marathon) -用于长期运行服务的Mesos框架.
* [Linkis](https://github.com/WeBankFinTech/Linkis) -Linkis帮助轻松连接到各种后端计算/存储引擎.

## Applications

* [411](https://github.com/etsy/411) -用于按计划搜索Elasticsearch而产生的警报管理的Web应用程序.
* [Adobe spindle](https://github.com/adobe-research/spindle) -使用Scala，Spark和Parquet进行下一代Web分析处理.
* [Apache Metron](http://metron.apache.org/) -集成了各种开源大数据技术的平台，以提供用于安全监控和分析的集中式工具.
* [Apache Nutch](http://nutch.apache.org/) -开源网络爬虫.
* [Apache OODT](http://oodt.apache.org/) -捕获，处理和共享NASA科学档案的数据.
* [Argus](https://github.com/salesforce/Argus) -时间序列监视和警报平台.
* [AthenaX](https://github.com/uber/AthenaX) -流分析平台，使用户能够使用结构化查询语言（SQL）运行生产质量的大规模流分析.
* [Atlas](https://github.com/Netflix/atlas) -用于管理维时间序列数据的后端.
* [Countly](https://count.ly/) -基于Node.js和MongoDB的开源移动和Web分析平台.
* [Domino](https://www.dominodatalab.com/) -运行，扩展，共享和部署模型-无需任何基础架构.
* [Eclipse BIRT](http://www.eclipse.org/birt/) -基于Eclipse的报告系统.
* [ElastAert](https://github.com/Yelp/elastalert) -ElastAlert是一个简单的框架，用于从ElasticSearch中的数据中发出异常，尖峰或其他感兴趣的模式的警报.
* [Eventhub](https://github.com/Codecademy/EventHub) -开源事件分析平台.
* [HASH](https://hash.ai) -开源仿真和可视化平台.
* [Hermes](https://github.com/allegro/hermes) -建立在Kafka之上的异步消息代理.
* [Hunk](https://www.splunk.com/en_us/download/hunk.html) -用于Hadoop的Splunk分析.
* [Imhotep](http://opensource.indeedeng.io/imhotep/) -确实是大型分析平台.
* [Indicative](https://www.indicative.com/) -具有数据仓库（AWS，BigQuery）集成的Web和移动分析工具.
* [Jupyter](https://jupyter.org/) -用于所有编程语言的交互式数据科学和科学计算的笔记本和项目应用程序.
* [MADlib](http://madlib.incubator.apache.org/community/) -RDBMS的数据处理库，用于分析数据.
* [Kapacitor](https://github.com/influxdata/kapacitor) -用于处理，监视和警告时间序列数据的开源框架.
* [Kylin](http://kylin.apache.org/) -来自eBay的开源分布式分析引擎.
* [PivotalR](https://github.com/pivotalsoftware/PivotalR) -在Pivotal HD / HAWQ和PostgreSQL上使用R.
* [Rakam](https://github.com/rakam-io/rakam) -由Postgresql，Kinesis和PrestoDB支持的开源实时自定义分析平台. 
* [Qubole](https://www.qubole.com/) -自动扩展Hadoop集群，内置数据连接器.
* [SnappyData](https://github.com/SnappyDataInc/snappydata) -用于实时运营分析的分布式内存数据存储，在单个集成集群中构建基于Spark的流分析，OLTP（在线事务处理）和OLAP（在线分析处理）.
* [Snowplow](https://github.com/snowplow/snowplow) -由Hadoop，Kinesis，Redshift和Postgres支持的企业级Web和事件分析.
* [SparkR](http://amplab-extras.github.io/SparkR-pkg/) -Spark的R前端.
* [Splunk](https://www.splunk.com/) -用于机器生成的数据的分析器.
* [Sumo Logic](https://www.sumologic.com/) -基于云的分析器，用于机器生成的数据.
* [Talend](http://www.talend.com/products/big-data/) -YARN，Hadoop，HBASE，Hive，HCatalog和Pig的统一开源环境.

## Search engine and framework

* [Apache Lucene](http://lucene.apache.org/) -搜索引擎库.
* [Apache Solr](http://lucene.apache.org/solr/) -Apache Lucene的搜索平台.
* [Elassandra](https://github.com/strapdata/elassandra) -是Elasticsearch的一个分支，经过修改可在可扩展且具有弹性的对等体系结构中运行在Apache Cassandra之上.
* [ElasticSearch](https://www.elastic.co/) -基于Apache Lucene的搜索和分析引擎.
* [Enigma.io](https://www.enigma.com/) – Freemium健壮的Web应用程序，用于浏览，过滤，分析，搜索和导出从整个Web抓取的海量数据集.
* [Google Caffeine](https://googleblog.blogspot.it/2010/06/our-new-search-index-caffeine.html) -连续索引系统.
* [Google Percolator](https://research.google.com/pubs/pub36726.html) -连续索引系统.
* [HBase Coprocessor](https://blogs.apache.org/hbase/entry/coprocessor_introduction) -实现Percolator，它是HBase的一部分.
* [LinkedIn Bobo](http://senseidb.github.io/bobo/) -是完全用Java编写的Faceted Search实现，它是Apache Lucene的扩展.
* [LinkedIn Cleo](https://github.com/linkedin/cleo) -是一个灵活的软件库，可用于快速开发部分，无序和实时的预输入搜索.
* [LinkedIn Galene](https://engineering.linkedin.com/search/did-you-mean-galene) -LinkedIn的搜索架构.
* [LinkedIn Zoie](https://github.com/senseidb/zoie) -是用Java编写的实时搜索/索引系统.
* [MG4J](http://mg4j.di.unimi.it/) - MG4J (Managing Gigabytes for Java) is a full-text search engine for large document collections written in Java. It is highly customisable, high-performance and provides state-of-the-art features and new research algorithms.
* [Sphinx Search Server](http://sphinxsearch.com/) -全文搜索引擎.
* [Vespa](http://vespa.ai/)  -是用于对大型数据集进行低延迟计算的引擎. 它存储和索引您的数据，以便可以在服务时执行对数据的查询，选择和处理.
* [Facebook Faiss](https://github.com/facebookresearch/faiss)  -是用于密集向量的高效相似性搜索和聚类的库. 它包含可搜索任意大小的向量集的算法，最多可搜索不适合RAM的向量. 它还包含用于评估和参数调整的支持代码.  Faiss用C ++编写，带有完整的Python / numpy包装器.
* [Annoy](https://github.com/spotify/annoy)  -是具有Python绑定的C ++库，用于搜索空间中与给定查询点接近的点. 它还会创建大型的基于文件的只读数据结构，这些数据结构被映射到内存中，以便许多进程可以共享相同的数据.
* [Weaviate](https://github.com/semi-technologies/weaviate) -Weaviate是基于GraphQL的语义搜索引擎，具有嵌入式（单词）嵌入.

## MySQL forks and evolutions

* [Amazon RDS](https://aws.amazon.com/rds/) -亚马逊云中的MySQL数据库.
* [Drizzle](http://www.drizzle.org/) -MySQL 6.0的演变.
* [Google Cloud SQL](https://cloud.google.com/sql/docs/) -Google云中的MySQL数据库.
* [MariaDB](https://mariadb.org/) -增强的，可替换的MySQL替代品.
* [MySQL Cluster](https://www.mysql.com/products/cluster/) -使用NDB群集存储引擎的MySQL实现.
* [Percona Server](https://www.percona.com/software/mysql-database/percona-server) -增强的，可替换的MySQL替代品.
* [ProxySQL](https://github.com/renecannao/proxysql) -MySQL的高性能代理.
* [TokuDB](https://www.percona.com/) -TokuDB是MySQL和MariaDB的存储引擎.
* [WebScaleSQL](http://webscalesql.org/) -是来自多家公司的工程师之间的协作，这些公司在大规模运行MySQL时面临类似的挑战.

## PostgreSQL forks and evolutions

* [HadoopDB](http://db.cs.yale.edu/hadoopdb/hadoopdb.html) -MapReduce和DBMS的混合体.
* [IBM Netezza](http://www-01.ibm.com/software/data/netezza/) -高性能数据仓库设备.
* [Postgres-XL](http://www.postgres-xl.org/) -可扩展的开源基于PostgreSQL的数据库集群.
* [RecDB](http://www-users.cs.umn.edu/~sarwat/RecDB/) -完全内置在PostgreSQL中的开源推荐引擎.
* [Stado](http://www.stormdb.com/community/stado) -仅针对数据仓库和数据集市应用程序的开源MPP数据库系统.
* [Yahoo Everest](https://www.scribd.com/doc/3159239/70-Everest-PGCon-RT) -PostgreSQL派生的多PB的数据库/ MPP.
* [TimescaleDB](http://www.timescale.com/) -为快速提取和复杂查询而优化的开源时间序列数据库
* [PipelineDB](https://www.pipelinedb.com/)  -流式SQL数据库. 一个开源关系数据库，该数据库在流上连续运行SQL查询，并将结果增量存储在表中

## Memcached forks and evolutions

* [Facebook McDipper](https://www.facebook.com/notes/facebook-engineering/mcdipper-a-key-value-cache-for-flash-storage/10151347090423920) -闪存的键/值缓存.
* [Facebook Memcached](https://www.facebook.com/notes/facebook-engineering/scaling-memcache-at-facebook/10151411410803920) -Memcache的分叉.
* [Twemproxy](https://github.com/twitter/twemproxy) -用于memcached和redis的快速，轻量级代理.
* [Twitter Fatcache](https://github.com/twitter/fatcache) -闪存的键/值缓存.
* [Twitter Twemcache](https://github.com/twitter/twemcache) -Memcache的分叉.

## Embedded Databases

* [Actian PSQL](http://www.actian.com/products/operational-databases/) -由Pervasive Software开发的符合ACID的DBMS，针对嵌入应用程序进行了优化.
* [BerkeleyDB](https://www.oracle.com/database/berkeley-db/index.html) -一个软件库，可为键/值数据提供高性能的嵌入式数据库.
* [HanoiDB](https://github.com/krestenkrab/hanoidb) -Erlang LSM BTree存储.
* [LevelDB](https://github.com/google/leveldb) -由Google编写的快速键值存储库，提供了从字符串键到字符串值的有序映射.
* [LMDB](https://symas.com/mdb/) -Symas开发的超快速，超紧凑键值嵌入式数据存储.
* [RocksDB](http://rocksdb.org/) -可嵌入的持久键值存储，用于基于LevelDB的快速存储.

## Business Intelligence

* [BIME Analytics](https://www.bimeanalytics.com/?lang=en) -云中的商业智能平台.
* [Blazer](https://github.com/ankane/blazer) -商业智能变得简单.
* [Chartio](https://chartio.com) -精益的商业智能平台，以可视化和探索您的数据.
* [Count](https://count.co) -使用SQL或拖放功能的基于笔记本的分析和可视化平台.
* [datapine](https://www.datapine.com/) -云中的自助式商业智能工具.
* [Dekart](https://dekart.xyz/) -基于Kepler.gl的Google BigQuery的大规模地理空间分析.
* [GoodData](https://www.gooddata.com/) -数据产品和嵌入式分析平台.
* [Jaspersoft](https://www.jaspersoft.com/) -强大的商务智能套件.
* [Jedox Palo](https://www.jedox.com/en/) -可定制的商业智能平台.
* [Jethrodata](https://jethro.io/) -交互式大数据分析.
* [intermix.io](https://intermix.io/) -Amazon Redshift的性能监控
* [Metabase](https://github.com/metabase/metabase) -向公司中的每个人提供商业智能和分析的最简单，最快的方法.
* [Microsoft](http://www.microsoft.com/en-us/server-cloud/solutions/business-intelligence/default.aspx) -商业智能软件和平台.
* [Microstrategy](https://www.microstrategy.com/) -用于商业智能，移动智能和网络应用程序的软件平台.
* [Numeracy](https://numeracy.co/) -快速，干净的SQL客户端和商业智能.
* [Pentaho](http://www.pentaho.com/) -商业智能平台.
* [Qlik](http://www.qlik.com/us/) -商业智能和分析平台.
* [Redash](https://redash.io/) -开源商业智能平台，支持多个数据源和计划的查询.
* [Saiku Analytics](https://www.meteorite.bi/) -开源分析平台.
* [Knowage](https://www.knowage-suite.com/)  -开源商业智能平台.  （前任 [SpagoBi](http://www.spagobi.org/))
* [SparklineData SNAP](http://sparklinedata.com/) -由Apache Spark支持的现代BI平台.
* [Tableau](https://www.tableau.com/) -商业智能平台.
* [Zoomdata](https://www.zoomdata.com/) -大数据分析.


## Data Visualization

* [Airpal](https://github.com/airbnb/airpal) -PrestoDB的Web UI.
* [AnyChart](http://www.anychart.com) -具有纯JS API的快速，简单和灵活的JavaScript（HTML5）图表库.
* [Arbor](https://github.com/samizdatco/arbor) -使用Web Worker和jQuery的图形可视化库.
* [Banana](https://github.com/LucidWorks/banana)  -可视化存储在Solr中的日志和带时间戳的数据. 基巴纳港口.
* [Bloomery](https://github.com/ufukomer/bloomery) -Impala的Web UI.
* [Bokeh](http://bokeh.pydata.org/en/latest/) -一个功能强大的Python交互式可视化库，该库针对现代Web浏览器进行演示，目标是以D3.js样式优雅，简洁地构造新颖的图形，同时还可以通过超大型或流式传输提供高性能的交互性数据集.
* [C3](http://c3js.org/) -基于D3的可重用图表库
* [CartoDB](https://github.com/CartoDB/cartodb) -具有强大的前端编辑功能和强大的API的地理空间数据库的开源或免费增值托管.
* [chartd](http://chartd.co/) -仅带有img标签的自适应视网膜兼容图表.
* [Chart.js](http://www.chartjs.org/) -开源HTML5图表可视化.
* [Chartist.js](https://github.com/gionkunz/chartist-js) -另一个开源的HTML5图表可视化.
* [Crossfilter](http://square.github.io/crossfilter/)  -JavaScript库，用于在浏览器中浏览大型多元数据集. 与dc.js和d3.js配合良好.
* [Cubism](https://github.com/square/cubism) -用于时间序列可视化的JavaScript库.
* [Cytoscape](http://cytoscape.github.io/) -用于可视化复杂网络的JavaScript库.
* [DC.js](http://dc-js.github.io/dc.js/)  -建立尺寸图以与使用d3.js渲染的交叉过滤器一起使用. 非常适合将图表/其他元数据连接到D3中的悬停事件.
* [D3](https://d3js.org/) -用于处理文档的javaScript库.
* [D3.compose](https://github.com/CSNW/d3.compose) -从可重复使用的图表和组件组成复杂的，数据驱动的可视化文件.
* [D3Plus](http://d3plus.org) -d3.js的一组相当强大的可重用图表和样式.
* [Dash](https://github.com/plotly/dash)  -适用于Python，R，Julia和Jupyter的分析型Web应用程序. 构建在plotly之上，不需要JS
* [Dekart](https://dekart.xyz/) -基于Kepler.gl的Google BigQuery的大规模地理空间分析.
* [DevExtreme React Chart](https://devexpress.github.io/devextreme-reactive/react/chart/) -用于Bootstrap和Material Design的基于插件的高性能React图表.
* [Echarts](https://github.com/ecomfe/echarts) -百度企业排行榜.
* [Envisionjs](https://github.com/HumbleSoftware/envisionjs) -动态HTML5可视化.
* [FnordMetric](https://metrictools.org/) -编写返回SVG图表而不是表的SQL查询
* [Frappe Charts](https://frappe.io/charts) - GitHub-inspired simple and modern SVG charts for the web with zero dependencies.
* [Freeboard](https://github.com/Freeboard/freeboard) -用于物联网和其他Web混搭的笔源实时仪表板构建器.
* [Gephi](https://github.com/gephi/gephi)  -屡获殊荣的开源平台，用于可视化和处理大型图形和网络连接. 它就像Photoshop，但用于图形. 适用于Windows和Mac OSX.
* [Google Charts](https://developers.google.com/chart/) -简单的图表API.
* [Grafana](https://grafana.com/) -石墨仪表板前端，编辑器和图形编辑器.
* [Graphite](http://graphiteapp.org/) -可扩展的实时绘图.
* [Highcharts](https://www.highcharts.com/) -简单灵活的图表API.
* [IPython](http://ipython.org/) -为交互式计算提供了丰富的体系结构.
* [Kibana](https://www.elastic.co/products/kibana) -可视化日志和时间戳数据
* [Lumify](http://lumify.io/) -开源大数据分析和可视化平台
* [Matplotlib](https://github.com/matplotlib/matplotlib) -使用Python进行绘图.
* [Metricsgraphic.js](https://metricsgraphicsjs.org/) -建立在D3之上的库，该库针对时间序列数据进行了优化
* [NVD3](http://nvd3.org/) -d3.js的图表组件.
* [Peity](https://github.com/benpickles/peity) -渐进式SVG条形图，折线图和饼图.
* [Plot.ly](https://plot.ly/)  -易于使用的Web服务，可快速创建从热图到直方图的复杂图表. 使用Plotly的在线电子表格上传数据以创建图表并设置样式. 分叉其他人的地块.
* [Plotly.js](https://github.com/plotly/plotly.js) 绘图功能强大的开源javascript图形库.
* [Recline](https://github.com/okfn/recline) -简单但功能强大的库，用于以纯Javascript和HTML构建数据应用程序.
* [Redash](https://github.com/getredash/redash) - open-source platform to query and visualize data.
* [ReCharts](http://recharts.org/) -基于React组件的可组合图表库
* [Shiny](http://shiny.rstudio.com/) -R的Web应用程序框架.
* [Sigma.js](https://github.com/jacomyal/sigma.js) -专门用于图形绘制的JavaScript库.
* [Superset](https://github.com/apache/incubator-superset) -旨在可视，直观和交互式的数据探索平台，可轻松将数据切片，切块和可视化，并以思想的速度进行分析.
* [Vega](https://github.com/vega/vega) -可视化语法.
* [Zeppelin](https://github.com/ZEPL/zeppelin) -笔记本式协作数据分析.
* [Zing Charts](https://www.zingchart.com/) -大数据的JavaScript图表库.
* [DataSphere Studio](https://github.com/WeBankFinTech/DataSphereStudio) -一站式数据应用程序开发管理门户.

## Internet of things and sensor data
* [Apache Edgent (Incubating)](http://edgent.apache.org/) -可以嵌入到网关和占用空间小的边缘设备中的编程模型和微内核样式运行时，可以在边缘设备上进行本地实时分析.
* [Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) -基于云的双向监视和消息传递中心
* [TempoIQ](https://www.tempoiq.com/) -基于云的传感器分析.
* [2lemetry](http://2lemetry.com/) -物联网平台.
* [Pubnub](https://www.pubnub.com/) -数据流网络
* [ThingWorx](https://www.thingworx.com/) -智能系统的快速开发与连接
* [IFTTT](https://ifttt.com/) -如果是这样的话
* [Evrything](https://evrythng.com/)-使产品智能化
* [NetLytics](https://github.com/marty90/netlytics/) -用于在Spark上处理网络数据的分析平台.

## Interesting Readings

* [Big Data Benchmark](https://amplab.cs.berkeley.edu/benchmark/) -Redshift，Hive，Shark，Impala和Stiger / Tez的基准.
* [NoSQL Comparison](https://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis) -Cassandra，MongoDB，CouchDB，Redis，Riak，HBase，Couchbase，Neo4j，Hypertable，ElasticSearch，Accumulo，VoltDB和Scalaris比较.
* [Monitoring Kafka performance](https://www.datadoghq.com/blog/monitoring-kafka-performance-metrics?ref=awesome) -监控Apache Kafka的指南，包括用于指标收集的本机方法.
* [Monitoring Hadoop performance](https://www.datadoghq.com/blog/monitor-hadoop-metrics?ref=awesome) -监视Hadoop的指南，其中概述了Hadoop体系结构以及用于收集指标的本机方法.
* [Monitoring Cassandra performance](https://www.datadoghq.com/blog/how-to-monitor-cassandra-performance-metrics/?ref=awesome) -监控Cassandra的指南，包括度量标准收集的本机方法.

## Interesting Papers

### 2015 - 2016
* [2015](http://www.vldb.org/pvldb/vol8/p1804-ching.pdf) -** Facebook **-万亿边缘：Facebook规模的图形处理.

### 2013 - 2014
* [2014](http://infolab.stanford.edu/~ullman/mmds/book.pdf) -**斯坦福**-大量数据集的挖掘.
* [2013](http://research.microsoft.com/pubs/200169/now-vldb.pdf) -** Microsoft **-云中大数据的可扩展渐进分析.
* [2013](http://static.druid.io/docs/druid.pdf) -** Metamarkets **-德鲁伊：实时分析数据存储.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p764-rae.pdf) -** Google **-F1中的在线，异步架构更改.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p734-akidau.pdf) -** Google **-MillWheel：Internet规模的容错流处理.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p767-wiener.pdf) -** Facebook **-Scuba：在Facebook上潜入数据.
* [2013](http://db.disi.unitn.eu/pages/VLDBProgram/pdf/industry/p871-curtiss.pdf) -** Facebook **-独角兽：一种用于搜索社交图谱的系统.
* [2013](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf) -** Facebook **-在Facebook上扩展Memcache.

### 2011 - 2012

* [2012](http://vldb.org/pvldb/vol5/p1771_georgelee_vldb2012.pdf) -** Twitter **-统一日志记录基础结构
Twitter上的数据分析.
* [2012](https://www.usenix.org/system/files/login/articles/zaharia.pdf) -** AMPLab **-使用Spark对Hadoop数据进行快速且交互式的分析.
* [2012](https://www.usenix.org/legacy/event/nsdi11/tech/full_papers/Bolosky.pdf) -** Microsoft **-Paxos复制状态机作为高性能数据存储的基础.
* [2012](http://research.microsoft.com/pubs/178045/ppaoxs-paper29.pdf) -**微软**-Paxos并行.
* [2012](https://arxiv.org/pdf/1203.5485.pdf) -** AMPLab **-BlinkDB：​​对非常大的数据具有有限错误和有限响应时间的查询.
* [2012](http://vldb.org/pvldb/vol5/p1436_alexanderhall_vldb2012.pdf) -** Google **-每次鼠标点击可处理1万亿个单元格.

### 2001 - 2010

* [2010](https://www.usenix.org/legacy/event/osdi10/tech/full_papers/Beaver.pdf) -** Facebook **-在干草堆中找到一个亮点：Facebook的照片存储.
* [2010](http://kowshik.github.io/JPregel/pregel_paper.pdf) -** Google **-Pregel：用于大规模图形处理的系统.
* [2010](http://leoneu.github.io/) -** Yahoo **-S4：分布式流计算平台.
* [2009](http://www.cs.umd.edu/~abadi/papers/hadoopdb.pdf) -HadoopDB：MapReduce和DBMS技术的架构混合，用于分析工作负载.	
* [2008](https://cwiki.apache.org/confluence/download/attachments/120729877/chukwa_cca08.pdf?version=1&modificationDate=1562667399000&api=v2) - **AMPLab** - Chukwa: A large-scale monitoring system.
* [2007](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/decandia07dynamo.pdf) -** Amazon **-Dynamo：Amazon的高可用键值存储.

## Videos

* [Spark in Motion](https://www.manning.com/livevideo/spark-in-motion) -Spark in Motion教您如何使用Spark进行批处理和流数据分析.
* [Machine Learning, Data Science and Deep Learning with Python ](https://www.manning.com/livevideo/machine-learning-data-science-and-deep-learning-with-python) -LiveVideo教程，涵盖了机器学习，Tensorflow，人工智能和神经网络.
* [Data warehouse schema design - dimensional modeling and star schema](https://snir.dev/talks/data-warehouse-schema-design) -使用星型模式方法的数据仓库模式设计简介.
* [Elasticsearch 7 and Elastic Stack](https://www.manning.com/livevideo/elasticsearch-7-and-elastic-stack) -LiveVideo教程，内容包括使用Elasticsearch，Logstash，Beats，Kibana等在集群上搜索，分析和可视化大数据.

## Books

#### Streaming
* [Data Science at Scale with Python and Dask](https://www.manning.com/books/data-science-at-scale-with-python-and-dask) -使用Python和Dask进行大规模数据科学教学，教您如何构建可以处理大量数据的分布式数据项目.
* [Streaming Data](https://www.manning.com/books/streaming-data) -流数据介绍了流和实时数据系统的概念和要求.
* [Storm Applied](https://www.manning.com/books/storm-applied) -Storm Applied是将Apache Storm用于与处理和分析实时数据流相关的实际任务的实用指南.
* [Fundamentals of Stream Processing: Application Design, Systems, and Analytics](http://www.cambridge.org/us/academic/subjects/engineering/communications-and-signal-processing/fundamentals-stream-processing-application-design-systems-and-analytics) -该综合的动手指南结合了流处理中的基本构建块和新兴研究，非常适合应用程序设计人员，系统构建人员，分析开发人员以及该领域的学生和研究人员.
* [Stream Data Processing: A Quality of Service Perspective](http://www.springer.com/us/book/9780387710020) -提出了适用于流和复杂事件处理的新范例.
* [Unified Log Processing](https://www.manning.com/books/event-streams-in-action) -统一日志处理是在企业中实施事件流（Kafka或Kinesis）的统一日志的实用指南
* [Kafka Streams in Action](https://www.manning.com/books/kafka-streams-in-action) -Kafka Streams in Action教会您在流向Kafka平台的数据上实现流处理所需的一切知识，使您可以专注于从数据中获取更多信息而无需花费时间或精力.
* [Big Data](https://www.manning.com/books/big-data) -大数据可教您使用一种体系结构来构建大数据系统，该体系结构利用群集硬件以及专门为捕获和分析Web规模数据而设计的新工具.
* [Spark in Action](https://www.manning.com/books/spark-in-action) & [Spark in Action 2nd Ed.](https://www.manning.com/books/spark-in-action-second-edition)  -Spark in Action可以教您使用Spark有效处理批处理和流式数据所需的理论和技能. 针对Spark 2.0进行了全面更新.
* [Kafka in Action](https://www.manning.com/books/kafka-in-action) -《行动中的卡夫卡》快速介绍了与卡夫卡合作的各个方面，您确实需要从中受益.
* [Fusion in Action](https://www.manning.com/books/fusion-in-action) -“行动中的融合”教您建立功能齐全的数据分析管道，包括文档和数据搜索以及分布式数据集群.
* [Reactive Data Handling](https://www.manning.com/books/reactive-data-handling) -Reactive Data Handling是由Manuel Bernhardt选择的五个精选章节的集合，向您介绍构建能够处理大数据负载实时处理的反应式应用程序-免费电子书！ 
* [Azure Data Engineering](https://www.manning.com/books/azure-data-engineering) -有关一般数据工程和专门针对Azure平台的书 
* [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems)  -Grokking流媒体系统可帮助您了解什么是流媒体系统，它们如何工作以及它们是否适合您的业务. 编写成与工具无关的，无论选择哪种框架，您都可以应用所学的知识.

#### Distributed systems
* [Distributed Systems for fun and profit](http://book.mixu.net/distsys/)  –分布式系统理论. 包括有关时间和顺序，复制和不可能结果的部分.

#### Graph Based approach
* [Graph-Powered Machine Learning](https://www.manning.com/books/graph-powered-machine-learning)  -亚历山德罗·内格罗（Alessandro Negro）. 结合图论和模型以改善机器学习项目

### Data Visualization
 * [The beauty of data visualization](https://www.youtube.com/watch?v=5Zg-C8AAIGg)
 * [Designing Data Visualizations with Noah Iliinsky](https://www.youtube.com/watch?v=R-oiKt7bUU8)
 * [Hans Rosling's 200 Countries, 200 Years, 4 Minutes](https://www.youtube.com/watch?v=jbkSRLYSojo)
 * [Ice Bucket Challenge Data Visualization](https://www.youtube.com/watch?v=qTEchen97rQ)


## Other Awesome Lists
-其他很棒的清单 [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).
-更多清单 [awesome](https://github.com/sindresorhus/awesome).
-另一个清单？ [list](https://github.com/jnv/lists).
-WTF！ [awesome-awesome-awesome](https://github.com/t3chnoboy/awesome-awesome-awesome).
-分析 [awesome-analytics](https://github.com/onurakpolat/awesome-analytics).
-公共数据集 [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets).
-图分类 [awesome-graph-classification](https://github.com/benedekrozemberczki/awesome-graph-classification).
- Network Embedding [awesome-network-embedding](https://github.com/chihming/awesome-network-embedding).
-社区检测 [awesome-community-detection](https://github.com/benedekrozemberczki/awesome-community-detection).
-决策树文件 [awesome-decision-tree-papers](https://github.com/benedekrozemberczki/awesome-decision-tree-papers).
-欺诈检测文件 [awesome-fraud-detection-papers](https://github.com/benedekrozemberczki/awesome-fraud-detection-papers).
-梯度提升论文 [awesome-gradient-boosting-papers](https://github.com/benedekrozemberczki/awesome-gradient-boosting-papers).
-蒙特卡罗树搜索文件 [awesome-monte-carlo-tree-search-papers](https://github.com/benedekrozemberczki/awesome-monte-carlo-tree-search-papers).
-卡夫卡 [awesome-kafka](https://github.com/monksy/awesome-kafka).
- [Google Bigtable](https://github.com/zrosenbauer/awesome-bigtable).
