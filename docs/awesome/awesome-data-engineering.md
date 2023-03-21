<div class="github-widget" data-repo="igorbarinov/awesome-data-engineering"></div>
很棒的数据工程
==========================

面向软件开发人员的精选数据工程工具列表 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

内容一览


## Databases
- 关系
	* [RQLite](https://github.com/rqlite/rqlite) 使用 Raft 共识协议复制 SQLite
	* [MySQL](https://www.mysql.com/) 世界上最受欢迎的开源数据库.
		* [TiDB](https://github.com/pingcap/tidb) TiDB 是一个兼容 MySQL 协议的分布式 NewSQL 数据库
		* [Percona XtraBackup](https://www.percona.com/software/mysql-database/percona-xtrabackup) Percona XtraBackup 是一个免费、开源、完整的在线备份解决方案，适用于所有版本的 Percona Server、MySQL® 和 MariaDB®
		* [mysql_utils](https://github.com/pinterest/mysql_utils) Pinterest MySQL 管理工具
	* [MariaDB](https://mariadb.org/) MySQL 的增强型直接替代品.
	* [PostgreSQL](https://www.postgresql.org/) 世界上最先进的开源数据库.
	* [Amazon RDS](https://aws.amazon.com/rds/) Amazon RDS 使在云中设置、操作和扩展关系数据库变得容易. 
	* [Crate.IO](https://crate.io/) 具有 NOSQL 优点的可扩展 SQL 数据库.
- 核心价值
	* [Redis](https://redis.io/) 开源、BSD 许可的高级键值缓存和存储.
	* [Riak](http://docs.basho.com/riak/kv/) 一种分布式数据库，旨在通过跨多个服务器分布数据来提供最大的数据可用性.
	* [AWS DynamoDB](https://aws.amazon.com/dynamodb/) 一种快速灵活的 NoSQL 数据库服务，适用于需要在任何规模下都保持一致的个位数毫秒延迟的所有应用程序.
	* [HyperDex](https://github.com/rescrv/HyperDex)  HyperDex 是一种可扩展、可搜索的键值存储. 已弃用.
	* [SSDB](http://ssdb.io) 支持多种数据结构的高性能NoSQL数据库，Redis的替代品
	* [Kyoto Tycoon](https://github.com/alticelabs/kyoto) Kyoto Tycoon 是 Kyoto Cabinet 键值数据库之上的轻量级网络服务器，专为高性能和并发性而构建
	* [IonDB](https://github.com/iondbproject/iondb) 用于微控制器和物联网应用的键值存储
- 柱子
	* [Cassandra](https://cassandra.apache.org/) 当您需要可扩展性和高可用性而又不影响性能时的正确选择.
		* [Cassandra Calculator](https://www.ecyrd.com/cassandracalculator/) 这种简单的形式允许您为 Apache Cassandra 集群尝试不同的值，并查看对您的应用程序有何影响.
		* [CCM](https://github.com/pcmanus/ccm) 在本地主机上轻松创建和销毁 Apache Cassandra 集群的脚本
		* [ScyllaDB](https://github.com/scylladb/scylla) NoSQL数据存储使用seastar框架，兼容Apache Cassandra https://www.scylladb.com/
	* [HBase](https://hbase.apache.org/) Hadoop 数据库，一种分布式、可扩展的大数据存储.
	* [AWS Redshift](https://aws.amazon.com/redshift/) 一个快速、完全托管的 PB 级数据仓库，使用您现有的商业智能工具可以简单且经济高效地分析您的所有数据.
	* [FiloDB](https://github.com/filodb/FiloDB) 分散式. 柱状. 版本化. 流媒体.  SQL.
	* [Vertica](https://www.vertica.com) 具有广泛分析 SQL 的分布式 MPP 列式数据库.
	* [ClickHouse](https://clickhouse.tech) 用于 OLAP 的分布式列式 DBMS.  SQL.
- 文档
	* [MongoDB](https://www.mongodb.com) 一个开源的文档数据库，旨在简化开发和扩展. 
		* [Percona Server for MongoDB](https://www.percona.com/software/mongo-database/percona-server-for-mongodb) Percona Server for MongoDB® 是 MongoDB® Community Edition 的免费、增强、完全兼容、开源的直接替代品，包括企业级特性和功能.
		* [MemDB](https://github.com/rain1017/memdb) 分布式事务内存数据库（基于 MongoDB）
	* [Elasticsearch](https://www.elastic.co/) 实时搜索和分析数据.
	* [Couchbase](https://www.couchbase.com/) 性能最高的 NoSQL 分布式数据库.
	* [RethinkDB](https://rethinkdb.com/) 用于实时网络的开源数据库.
	* [RavenDB](https://ravendb.net/) 完全事务性的 NoSQL 文档数据库.
- 图
	* [Neo4j](https://neo4j.com/) 世界领先的图形数据库.
	* [OrientDB](https://orientdb.com) 2nd Generation Distributed Graph Database with the flexibility of Documents in one product with an Open Source commercial friendly license.
	* [ArangoDB](https://www.arangodb.com/) 分布式免费开源数据库，具有灵活的文档、图形和键值数据模型. 
	* [Titan](https://titan.thinkaurelius.com) 一种可扩展的图形数据库，针对存储和查询图形进行了优化，其中包含分布在多机集群中的数千亿个顶点和边.
	* [FlockDB](https://github.com/twitter-archive/flockdb)  Twitter 的分布式容错图形数据库. 已弃用.
- 分散式
	* [DAtomic](https://www.datomic.com) 完全事务性、云就绪的分布式数据库.
	* [Apache Geode](https://geode.apache.org/) 用于横向扩展应用程序的开源分布式内存数据库.
	* [Gaffer ](https://github.com/gchq/Gaffer) 一个大规模的图数据库
- 时间序列
	* [InfluxDB](https://github.com/influxdata/influxdb) 用于指标、事件和实时分析的可扩展数据存储.
	* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) 可扩展的分布式时间序列数据库.
	* [QuestDB](https://questdb.io/) 一种面向列的关系数据库，专为对时间序列和事件数据进行实时分析而设计.
	* [kairosdb](https://github.com/kairosdb/kairosdb) 快速可扩展的时间序列数据库.
	* [Heroic](https://github.com/spotify/heroic) 基于 Cassandra 和 Elasticsearch 的可扩展时间序列数据库，来自 Spotify
	* [Druid](https://github.com/apache/incubator-druid) 面向列的分布式数据存储是支持交互式应用程序的理想选择
	* [Riak-TS](http://basho.com/products/riak-ts/) Riak TS 是唯一专门针对物联网和时间序列数据优化的企业级 NoSQL 时间序列数据库
	* [Akumuli](https://github.com/akumuli/Akumuli)  Akumuli 是一个数字时间序列数据库. 它可用于实时捕获、存储和处理时间序列数据.  “akumuli”这个词可以从世界语翻译成“积累”.
	* [Rhombus](https://github.com/Pardot/Rhombus) 用于 Cassandra 的时间序列对象存储，可处理构建宽行索引的所有复杂性.
	* [Dalmatiner DB](https://github.com/dalmatinerdb/dalmatinerdb) 快速分布式指标数据库
	* [Blueflood](https://github.com/rackerlabs/blueflood) 旨在摄取和处理时间序列数据的分布式系统
	* [Timely](https://github.com/NationalSecurityAgency/timely) Timely 是一个时间序列数据库应用程序，它基于 Accumulo 和 Grafana 提供对时间序列数据的安全访问.
- 其他
	* [Tarantool](https://github.com/tarantool/tarantool/) Tarantool 是一个内存数据库和应用程序服务器.
	* [GreenPlum](https://github.com/greenplum-db/gpdb)  Greenplum 数据库 (GPDB) 是一个先进的、功能齐全的开源数据仓库. 它提供对 PB 级数据量的强大而快速的分析.
	* [cayley](https://github.com/cayleygraph/cayley) 一个开源图形数据库. 谷歌.
	* [Snappydata](https://github.com/SnappyDataInc/snappydata) SnappyData：基于 Apache Spark 构建的 OLTP + OLAP 数据库
	* [TimescaleDB](https://www.timescale.com/)：作为 PostgreSQL 之上的扩展，TimescaleDB 是一个时间序列 SQL 数据库，提供快速分析、可扩展性，并在经过验证的存储引擎上进行自动化数据管理.

## Data Ingestion
* [Kafka](https://kafka.apache.org/) 将发布-订阅消息重新考虑为分布式提交日志.
	* [BottledWater](https://github.com/confluentinc/bottledwater-pg) 将数据捕获从 PostgreSQL 更改为 Kafka. 已弃用.
	* [kafkat](https://github.com/airbnb/kafkat) Kafka 代理的简化命令行管理
	* [kafkacat](https://github.com/edenhill/kafkacat) 通用命令行非 JVM Apache Kafka 生产者和消费者
	* [pg-kafka](https://github.com/xstevens/pg_kafka) 用于向 Apache Kafka 生成消息的 PostgreSQL 扩展
	* [librdkafka](https://github.com/edenhill/librdkafka) Apache Kafka C/C++ 库
	* [kafka-docker](https://github.com/wurstmeister/kafka-docker) Docker 中的卡夫卡
	* [kafka-manager](https://github.com/yahoo/kafka-manager) 管理 Apache Kafka 的工具
	* [kafka-node](https://github.com/SOHU-Co/kafka-node) 用于 Apache Kafka 0.8 的 Node.js 客户端
	* [Secor](https://github.com/pinterest/secor) Pinterest 的 Kafka 到 S3 分布式消费者
	* [Kafka-logger](https://github.com/uber/kafka-logger) 来自 uber 的 nodejs 的 Kafka-winston 记录器
* [AWS Kinesis](https://aws.amazon.com/kinesis/) 一种完全托管的基于云的服务，用于对大型分布式数据流进行实时数据处理.
* [RabbitMQ](https://www.rabbitmq.com/) 应用程序的强大消息传递.
* [FluentD](https://www.fluentd.org) 统一日志层的开源数据收集器.
* [Embulk](https://www.embulk.org) 一种开源批量数据加载器，可帮助在各种数据库、存储、文件格式和云服务之间传输数据.
* [Apache Sqoop](https://sqoop.apache.org) 一种设计用于在 Apache Hadoop 和结构化数据存储（例如关系数据库）之间高效传输大量数据的工具.
* [Heka](https://github.com/mozilla-services/heka) 数据采集​​和处理变得简单. 已弃用.
* [Gobblin](https://github.com/apache/incubator-gobblin) 来自 Linkedin 的 Hadoop 通用数据摄取框架
* [Nakadi](https://nakadi.io) Nakadi 是一个开源事件消息传递平台，它在类似 Kafka 的队列之上提供 REST API.
* [Pravega](http://www.pravega.io) Pravega 为连续且无界的数据提供了一种新的存储抽象——流.
* [Apache Pulsar](https://pulsar.apache.org/) Apache Pulsar 是一个开源的分布式发布-订阅消息系统.
* [AWS Data Wranlger](https://github.com/awslabs/aws-data-wrangler) 用于处理 AWS 上数据的实用程序带.

## File System
* [HDFS](https://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html)
	* [Snakebite](https://github.com/spotify/snakebite) 纯python HDFS客户端
* [AWS S3](https://aws.amazon.com/s3/)
	* [smart_open](https://github.com/RaRe-Technologies/smart_open) 用于流式传输大文件的实用程序（S3、HDFS、gzip、bz2）
* [Alluxio](https://www.alluxio.org/) Alluxio 是一个以内存为中心的分布式存储系统，可以跨集群框架（例如 Spark 和 MapReduce）以内存速度实现可靠的数据共享
* [CEPH](https://ceph.com/) Ceph 是一个统一的分布式存储系统，专为卓越的性能、可靠性和可扩展性而设计
* [OrangeFS](https://www.orangefs.org/) Orange File System是Parallel Virtual File System的一个分支
* [SnackFS](https://github.com/tuplejump/snackfs-release) SnackFS 是我们基于 Cassandra 构建的小型、轻量级 HDFS 兼容文件系统
* [GlusterFS](https://www.gluster.org/) Gluster 文件系统
* [XtreemFS](http://www.xtreemfs.org/) 可满足所有存储需求的容错分布式文件系统
* [SeaweedFS](https://github.com/chrislusf/seaweedfs)  Seaweed-FS 是一个简单且高度可扩展的分布式文件系统. 有两个目标：存储数十亿个文件！ 快速提供文件！  Seaweed-FS 不支持完整的 POSIX 文件系统语义，而是选择仅实现一个 key~file 映射. 类似于“NoSQL”这个词，你可以称它为“NoFS”.
* [S3QL](https://github.com/s3ql/s3ql/) S3QL 是一个文件系统，它使用 Google Storage、Amazon S3 或 OpenStack 等存储服务在线存储所有数据.
* [LizardFS](https://lizardfs.com/) LizardFS 软件定义存储是一个分布式、并行、可扩展、容错、地理冗余和高可用的文件系统.

## Serialization format
* [Apache Avro](https://avro.apache.org) Apache Avro™ 是一个数据序列化系统
* [Apache Parquet](https://parquet.apache.org) Apache Parquet 是一种列式存储格式，适用于 Hadoop 生态系统中的任何项目，无论选择何种数据处理框架、数据模型或编程语言.
	* [Snappy](https://github.com/google/snappy) 快速压缩器/解压缩器. 与镶木地板一起使用
	* [PigZ](https://zlib.net/pigz/) 现代 gzip 的并行实现
多处理器、多核机器
* [Apache ORC](https://orc.apache.org/) 适用于 Hadoop 工作负载的最小、最快的列式存储 
* [Apache Thrift](https://thrift.apache.org) Apache Thrift 软件框架，用于可扩展的跨语言服务开发
* [ProtoBuf](https://github.com/protocolbuffers/protobuf) Protocol Buffers - Google 的数据交换格式
* [SequenceFile](https://wiki.apache.org/hadoop/SequenceFile)  SequenceFile 是由二进制键/值对组成的平面文件. 它在 MapReduce 中广泛用作输入/输出格式
* [Kryo](https://github.com/EsotericSoftware/kryo) Kryo 是一个快速高效的 Java 对象图序列化框架


## Stream Processing
* [Apache Beam](https://beam.apache.org/) Apache Beam 是一种统一的编程模型，可实现在许多执行引擎上运行的批处理和流数据处理作业.
* [Spark Streaming](https://spark.apache.org/streaming/) Spark Streaming 可以轻松构建可扩展的容错流应用程序.
* [Apache Flink](https://flink.apache.org/) Apache Flink 是一个流式数据流引擎，为数据流上的分布式计算提供数据分发、通信和容错.
* [Apache Storm](https://storm.apache.org) Apache Storm 是一个免费开源的分布式实时计算系统
* [Apache Samza](https://samza.apache.org) Apache Samza 是一个分布式流处理框架
* [Apache NiFi](https://nifi.apache.org/) 是一个易于使用、功能强大且可靠的系统来处理和分发数据
* [Apache Hudi](https://hudi.apache.org/) Apache Hudi 是一个开源框架，用于管理实时处理的存储，最有趣的功能之一是 Upsert
* [VoltDB](https://voltdb.com/) VoltDb 是一种符合 ACID 的 RDBMS，它使用 [shared nothing architecture](https://en.wikipedia.org/wiki/Shared-nothing_architecture).
* [PipelineDB](https://github.com/pipelinedb/pipelinedb) 流式 SQL 数据库
* [Spring Cloud Dataflow](https://cloud.spring.io/spring-cloud-dataflow/) Spring Boot 应用程序之间的流式处理和任务执行
* [Bonobo](https://www.bonobo-project.org/) Bonobo 是 python 3.5+ 的数据处理工具包
* [Robinhood's Faust](https://github.com/faust-streaming/faust) 永远可扩展的事件处理和内存中持久的 K/V 存储作为具有异步和静态类型的库.
* [HStreamDB](https://github.com/hstreamdb/hstream) 为物联网数据存储和实时处理而构建的流式数据库.
* [Kuiper](https://github.com/emqx/kuiper) 由 Golang 实现的边缘轻量级物联网数据分析/流媒体软件，它可以在各种资源受限的边缘设备上运行.

## Batch Processing
* [Hadoop MapReduce](https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) Hadoop MapReduce 是一个软件框架，用于轻松编写应用程序，以可靠、容错的方式在大型商用硬件集群（数千个节点）上并行处理大量数据（数 TB 数据集）
* [Spark](https://spark.apache.org/)
	* [Spark Packages](https://spark-packages.org) Apache Spark 包的社区索引
	* [Deep Spark](https://github.com/Stratio/deep-spark) 将 Apache Spark 与不同的数据存储连接起来. 已弃用.
	* [Spark RDD API Examples](http://homepage.cs.latrobe.edu.au/zhe/ZhenHeSparkRDDAPIExamples.html) by Zhen He
	* [Livy](https://livy.incubator.apache.org) Livy，REST Spark 服务器
* [AWS EMR](https://aws.amazon.com/emr/) 一种 Web 服务，可以轻松快速且经济高效地处理大量数据.
* [Tez](https://tez.apache.org/) 一个应用程序框架，允许使用复杂的有向无环图任务来处理数据.
* [Bistro](https://github.com/asavinov/bistro) 是用于通用数据处理的轻量级引擎，包括批处理和流分析. 它基于一种新颖独特的数据模型，该模型通过*函数*表示数据并通过*列操作*处理数据，而不是像 MapReduce 或 SQL 等传统方法中仅设置操作.
- 批量机器学习
	* [H2O](https://www.h2o.ai/) 用于更智能应用程序的快速可扩展机器学习 API.
	* [Mahout](https://mahout.apache.org/) 用于快速创建可扩展的高性能机器学习应用程序的环境.
	* [Spark MLlib](https://spark.apache.org/docs/latest/ml-guide.html) Spark 的可扩展机器学习库由常见的学习算法和实用程序组成，包括分类、回归、聚类、协同过滤、降维以及底层优化原语.
- 批处理图
	* [GraphLab Create](https://turi.com/products/create/docs/) 一个机器学习平台，使数据科学家和应用程序开发人员能够轻松地大规模创建智能应用程序.
	* [Giraph](https://giraph.apache.org/) 为高可扩展性而构建的迭代图形处理系统. 
	* [Spark GraphX](https://spark.apache.org/graphx/) Apache Spark's API for graphs and graph-parallel computation. 
- 批处理 SQL
	* [Presto](https://prestodb.github.io/docs/current/index.html) 一种分布式 SQL 查询引擎，旨在查询分布在一个或多个异构数据源上的大型数据集.
	* [Hive](https://hive.apache.org) 数据仓库软件有助于查询和管理驻留在分布式存储中的大型数据集. 
		* [Hivemall](https://github.com/apache/incubator-hivemall) Hive/Hadoop 的可扩展机器学习库.
		* [PyHive](https://github.com/dropbox/PyHive) Hive 和 Presto 的 Python 接口.
	* [Drill](https://drill.apache.org/) 用于 Hadoop、NoSQL 和云存储的无模式 SQL 查询引擎.

## Charts and Dashboards
* [Highcharts](https://www.highcharts.com/) 一个用纯 JavaScript 编写的图表库，提供了一种将交互式图表添加到您的网站或 Web 应用程序的简单方法.
* [ZingChart](https://www.zingchart.com/) 适用于任何数据集的快速 JavaScript 图表.
* [C3.js](https://c3js.org) 基于 D3 的可重用图表库.
* [D3.js](https://d3js.org/) 用于根据数据操作文档的 JavaScript 库.
	* [D3Plus](https://d3plus.org)  D3 的表亲更简单、更易于使用. 大多数预定义模板，您可以插入数据.
* [SmoothieCharts](http://smoothiecharts.org) 用于流数据的 JavaScript 图表库.
* [PyXley](https://github.com/stitchfix/pyxley) 使用 Flask 和 React 构建仪表板的 Python 助手
* [Plotly](https://github.com/plotly/dash) Flask、JS 和 CSS 样板，用于 Python 中基于 Web 的交互式可视化应用程序
* [Apache Superset](https://github.com/apache/incubator-superset) Apache Superset（孵化）是一个现代的、企业就绪的商业智能网络应用程序
* [Redash](https://redash.io/) 让您的公司数据驱动. 连接到任何数据源，轻松可视化和共享您的数据.
* [Metabase](https://github.com/metabase/metabase) Metabase is the easy, open source way for everyone in your company to ask questions and learn from data.
* [PyQtGraph](http://www.pyqtgraph.org/)  PyQtGraph 是一个基于 PyQt4 / PySide 和 numpy 的纯 python 图形和 GUI 库. 它旨在用于数学/科学/工程应用.


## Workflow
* [Luigi](https://github.com/spotify/luigi) Luigi 是一个 Python 模块，可帮助您构建批处理作业的复杂管道.
	* [CronQ](https://github.com/seatgeek/cronq) 一个类似 cron 的应用程序系统. [Used](https://chairnerd.seatgeek.com/building-out-the-seatgeek-data-pipeline/) 瓦特/路易格. 已弃用.
* [Cascading](https://www.cascading.org/) 基于Java的应用程序开发平台.
* [Airflow](https://github.com/apache/airflow) Airflow 是一个以编程方式编写、调度和监控数据管道的系统.
* [Azkaban](https://azkaban.github.io/)  Azkaban 是 LinkedIn 创建的批处理工作流作业调度程序，用于运行 Hadoop 作业.  Azkaban 通过作业依赖关系解决排序问题，并提供易于使用的 Web 用户界面来维护和跟踪您的工作流程. 
* [Oozie](https://oozie.apache.org/) Oozie 是一个用于管理 Apache Hadoop 作业的工作流调度系统
* [Pinball](https://github.com/pinterest/pinball) 基于 DAG 的工作流管理器. 作业流程在 Python 中以编程方式定义. 支持作业之间的输出传递.
* [Dagster](https://github.com/dagster-io/dagster) Dagster 是一个用于构建数据应用程序的开源 Python 库.
* [Dataform](https://dataform.co/) 是一个开源框架和基于 Web 的 IDE，用于管理数据集及其依赖项.  SQLX 扩展了您现有的 SQL 仓库方言以添加支持依赖关系管理、测试、文档等的功能.
* [Census](https://getcensus.com/) 是一种反向 ETL 工具，可让您将数据从云数据仓库同步到 SaaS 应用程序，如 Salesforce、Marketo、HubSpot、Zendesk 等.无需工程方面的帮助——只需 SQL.
* [dbt](https://getdbt.com/) 是一个命令行工具，使数据分析师和工程师能够更有效地转换其仓库中的数据.

## Data Lake Management
* [lakeFS](https://github.com/treeverse/lakeFS) lakeFS 是一个开源平台，可为基于对象存储的数据湖提供弹性和可管理性.

## ELK Elastic Logstash Kibana
* [docker-logstash](https://github.com/pblittle/docker-logstash) 运行 Elasticsearch (1.7.0) 和 Kibana (3.1.2) 的高度可配置的 logstash (1.4.4) docker 镜像.
* [elasticsearch-jdbc](https://github.com/jprante/elasticsearch-jdbc) Elasticsearch 的 JDBC 导入器
* [ZomboDB](https://github.com/zombodb/zombodb) 允许创建由 Elasticsearch 支持的索引的 Postgres 扩展

## Docker
* [Gockerize](https://github.com/redbooth/gockerize) 将 golang 服务打包到最小的 docker 容器中
* [Flocker](https://github.com/ClusterHQ/flocker) 轻松管理 Docker 容器及其数据
* [Rancher](https://rancher.com/rancher-os/) RancherOS 是一个 20mb 的 Linux 发行版，将整个操作系统作为 Docker 容器运行
* [Kontena](https://www.kontena.io/) 大众应用容器
* [Weave](https://github.com/weaveworks/weave) 将 Docker 容器编织到应用程序中
* [Zodiac](https://github.com/CenturyLinkLabs/zodiac) 轻量级工具，用于轻松部署和回滚 dockerized 应用程序
* [cAdvisor](https://github.com/google/cadvisor) 分析正在运行的容器的资源使用情况和性能特征
* [Micro S3 persistence](https://github.com/figadore/micro-s3-persistence) 用于将卷数据保存/恢复到 S3 的 Docker 微服务
* [Rocker-compose](https://github.com/grammarly/rocker-compose) 具有幂等特性的 Docker 组合工具，用于部署由多个容器组成的应用程序. 已弃用.
* [Nomad](https://github.com/hashicorp/nomad) Nomad 是一个集群管理器，专为长期服务和短期批处理工作负载而设计
* [ImageLayers](https://imagelayers.io/) 可视化 docker 图像和构成它们的层


## Datasets
## Realtime
* [Twitter Realtime](https://developer.twitter.com/en/docs/tweets/filter-realtime/overview) Streaming API 为开发人员提供了对 Twitter 全球推文数据流的低延迟访问.
* [Eventsim](https://github.com/Interana/eventsim) 事件数据模拟器. 从一组用户生成伪随机事件流，旨在模拟网络流量.
* [Reddit](https://www.reddit.com/r/datasets/comments/3mk1vg/realtime_data_is_available_including_comments/) 实时数据可用，包括评论、提交和发布到 reddit 的链接

## Data Dumps
* [GitHub Archive](https://www.gharchive.org/) GitHub 自 2011 年以来的公共时间线，每小时更新一次
* [Common Crawl](https://commoncrawl.org/) 网络抓取数据的开源存储库
* [Wikipedia](https://dumps.wikimedia.org/enwiki/latest/) 维基百科所有维基的完整副本，以维基文本源和嵌入 XML 的元数据的形式. 许多 SQL 形式的原始数据库表也可用.

## Monitoring

## Prometheus
* [Prometheus.io](https://github.com/prometheus/prometheus) 一个开源的服务监控系统和时间序列数据库
* [HAProxy Exporter](https://github.com/prometheus/haproxy_exporter) 抓取 HAProxy 统计数据并通过 HTTP 导出它们以供 Prometheus 使用的简单服务器

## Community

## Forums
* [/r/dataengineering](https://www.reddit.com/r/dataengineering/) 数据工程的新闻、技巧和背景
* [/r/etl](https://www.reddit.com/r/ETL/) Subreddit 专注于 ETL

## Conferences
* [Data Council](https://www.datacouncil.ai/about) 数据委员会是第一个弥合数据科学家、数据工程师和数据分析师之间差距的技术会议.

## Podcasts
* [Data Engineering Podcast](https://www.dataengineeringpodcast.com/) 关于现代数据基础设施的展示.

干杯 [The Data Engineering Ecosystem: An Interactive Map](http://xyz.insightdataengineering.com/blog/pipeline_map.html)

灵感来自 [awesome](https://github.com/sindresorhus/awesome) 列表. 由...制作 [Insight Data Engineering](https://insightdataengineering.com) 伙计们.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Igor Barinov](https://github.com/igorbarinov/) 已放弃该作品的所有版权和相关或邻接权.
