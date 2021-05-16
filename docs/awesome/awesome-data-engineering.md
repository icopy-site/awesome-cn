<div class="github-widget" data-repo="igorbarinov/awesome-data-engineering"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
很棒的数据工程
==========================

面向软件开发人员的精选数据工程工具清单 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

内容清单


## Databases
-关系
	* [RQLite](https://github.com/rqlite/rqlite) 使用Raft共识协议复制SQLite
	* [MySQL](https://www.mysql.com/) 世界上最受欢迎的开源数据库.
		* [TiDB](https://github.com/pingcap/tidb) TiDB是与MySQL协议兼容的分布式NewSQL数据库
		* [Percona XtraBackup](https://www.percona.com/software/mysql-database/percona-xtrabackup) Percona XtraBackup是针对所有版本的Percona Server，MySQL®和MariaDB®的免费，开源，完整的在线备份解决方案
		* [mysql_utils](https://github.com/pinterest/mysql_utils) Pinterest MySQL管理工具
	* [MariaDB](https://mariadb.org/) MySQL的增强的直接替代品.
	* [PostgreSQL](https://www.postgresql.org/) 世界上最先进的开源数据库.
	* [Amazon RDS](https://aws.amazon.com/rds/) Amazon RDS使在云中轻松建立，操作和扩展关系数据库变得容易. 
	* [Crate.IO](https://crate.io/) 具有NOSQL优点的可扩展SQL数据库.
- 核心价值
	* [Redis](https://redis.io/) 开源的，BSD许可的高级键值缓存和存储.
	* [Riak](http://docs.basho.com/riak/kv/) 分布式数据库旨在通过在多个服务器之间分布数据来提供最大的数据可用性.
	* [AWS DynamoDB](https://aws.amazon.com/dynamodb/) 快速和灵活的NoSQL数据库服务，适用于所有规模的，需要一致的单位毫秒毫秒延迟的应用程序.
	* [HyperDex](https://github.com/rescrv/HyperDex)  HyperDex是可扩展的，可搜索的键值存储. 不推荐使用.
	* [SSDB](http://ssdb.io) 高性能NoSQL数据库，支持许多数据结构，是Redis的替代方案
	* [Kyoto Tycoon](https://github.com/alticelabs/kyoto) Kyoto Tycoon是在Kyoto Cabinet键值数据库之上的轻型网络服务器，旨在实现高性能和并发性
	* [IonDB](https://github.com/iondbproject/iondb) 微控制器和物联网应用的键值存储
- 柱子
	* [Cassandra](https://cassandra.apache.org/) 当您需要可扩展性和高可用性而又不影响性能时的正确选择.
		* [Cassandra Calculator](https://www.ecyrd.com/cassandracalculator/) 这种简单的形式使您可以为Apache Cassandra集群尝试不同的值，并查看对您的应用程序有什么影响.
		* [CCM](https://github.com/pcmanus/ccm) 轻松在本地主机上创建和销毁Apache Cassandra集群的脚本
		* [ScyllaDB](https://github.com/scylladb/scylla) 使用seastar框架的NoSQL数据存储，与Apache Cassandra兼容https://www.scylladb.com/
	* [HBase](https://hbase.apache.org/) Hadoop数据库，一个分布式，可扩展的大数据存储.
	* [AWS Redshift](https://aws.amazon.com/redshift/) 快速的，完全托管的，PB级的数据仓库，使使用现有的商业智能工具分析所有数据变得简单且经济高效.
	* [FiloDB](https://github.com/filodb/FiloDB) 分散式. 柱状. 版本化. 流媒体.  SQL.
	* [Vertica](https://www.vertica.com) 带有广泛分析SQL的分布式MPP列式数据库.
- 文档
	* [MongoDB](https://www.mongodb.com) 一个开放源代码的文档数据库，旨在简化开发和扩展. 
		* [Percona Server for MongoDB](https://www.percona.com/software/mongo-database/percona-server-for-mongodb) Percona Server forMongoDB®是MongoDB®Community Edition的免费，增强，完全兼容，开源的直接替代，其中包括企业级功能.
		* [MemDB](https://github.com/rain1017/memdb) 分布式事务性内存数据库（基于MongoDB）
	* [Elasticsearch](https://www.elastic.co/) 实时搜索和分析数据.
	* [Couchbase](https://www.couchbase.com/) 性能最高的NoSQL分布式数据库.
	* [RethinkDB](https://rethinkdb.com/) 实时Web的开源数据库.
	* [RavenDB](https://ravendb.net/) 完全事务性NoSQL文档数据库.
-图
	* [Neo4j](https://neo4j.com/) 世界领先的图形数据库.
	* [OrientDB](https://orientdb.com) 2nd Generation Distributed Graph Database with the flexibility of Documents in one product with an Open Source commercial friendly license.
	* [ArangoDB](https://www.arangodb.com/) 具有用于文档，图形和键值的灵活数据模型的分布式免费开放源数据库. 
	* [Titan](https://titan.thinkaurelius.com) 可扩展的图形数据库经过优化，可用于存储和查询包含分布在多计算机集群中的数千亿个顶点和边的图形.
	* [FlockDB](https://github.com/twitter-archive/flockdb)  Twitter的分布式容错图数据库. 不推荐使用.
- 分散式
	* [DAtomic](https://www.datomic.com) 完全事务化，可用于云的分布式数据库.
	* [Apache Geode](https://geode.apache.org/) 一个用于横向扩展应用程序的开源，分布式内存数据库.
	* [Gaffer ](https://github.com/gchq/Gaffer) 大型图形数据库
- 时间序列
	* [InfluxDB](https://github.com/influxdata/influxdb) 可扩展的数据存储区，用于度量标准，事件和实时分析.
	* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) 可扩展的分布式时间序列数据库.
	* [kairosdb](https://github.com/kairosdb/kairosdb) 快速可扩展的时间序列数据库.
	* [Heroic](https://github.com/spotify/heroic) Spotify基于Cassandra和Elasticsearch的可伸缩时间序列数据库
	* [Druid](https://github.com/apache/incubator-druid) 面向列的分布式数据存储，是为交互式应用程序提供动力的理想选择
	* [Riak-TS](http://basho.com/products/riak-ts/) Riak TS是唯一专门针对IoT和时间序列数据进行优化的企业级NoSQL时间序列数据库
	* [Akumuli](https://github.com/akumuli/Akumuli)  Akumuli是一个数字时间序列数据库. 它可以用于实时捕获，存储和处理时间序列数据. 单词“ akumuli”可以从世界语翻译为“积累”.
	* [Rhombus](https://github.com/Pardot/Rhombus) Cassandra的时间序列对象存储，处理构建宽行索引的所有复杂性.
	* [Dalmatiner DB](https://github.com/dalmatinerdb/dalmatinerdb) 快速分布式指标数据库
	* [Blueflood](https://github.com/rackerlabs/blueflood) 旨在吸收和处理时间序列数据的分布式系统
	* [Timely](https://github.com/NationalSecurityAgency/timely) Timely是一个时间序列数据库应用程序，可提供对Accumulo和Grafana的时间序列数据的安全访问.
- 其他
	* [Tarantool](https://github.com/tarantool/tarantool/) Tarantool是内存数据库和应用程序服务器.
	* [GreenPlum](https://github.com/greenplum-db/gpdb)  Greenplum数据库（GPDB）是先进的，功能齐全的开源数据仓库. 它提供了对PB级数据量的强大而快速的分析.
	* [cayley](https://github.com/cayleygraph/cayley) An open-source graph database. Google.
	* [Snappydata](https://github.com/SnappyDataInc/snappydata) SnappyData：基于Apache Spark构建的OLTP + OLAP数据库
	* [TimescaleDB](https://www.timescale.com/)：TimescaleDB是作为PostgreSQL之上的扩展而构建的，是一个时序SQL数据库，提供快速的分析，可伸缩性，并在经过验证的存储引擎上进行自动数据管理.

## Data Ingestion
* [Kafka](https://kafka.apache.org/) 重新考虑发布-订阅消息传递为分布式提交日志.
	* [BottledWater](https://github.com/confluentinc/bottledwater-pg) 将数据捕获从PostgreSQL更改为Kafka. 不推荐使用.
	* [kafkat](https://github.com/airbnb/kafkat) Kafka经纪人的简化命令行管理
	* [kafkacat](https://github.com/edenhill/kafkacat) 通用命令行非JVM Apache Kafka生产者和使用者
	* [pg-kafka](https://github.com/xstevens/pg_kafka) PostgreSQL扩展，用于向Apache Kafka生成消息
	* [librdkafka](https://github.com/edenhill/librdkafka) Apache Kafka C / C ++库
	* [kafka-docker](https://github.com/wurstmeister/kafka-docker) Docker中的Kafka
	* [kafka-manager](https://github.com/yahoo/kafka-manager) 一种管理Apache Kafka的工具
	* [kafka-node](https://github.com/SOHU-Co/kafka-node) 适用于Apache Kafka 0.8的Node.js客户端
	* [Secor](https://github.com/pinterest/secor) Pinterest的Kafka到S3分布式消费者
	* [Kafka-logger](https://github.com/uber/kafka-logger) 来自Uber的Nodef的Kafka-Winston记录器
* [AWS Kinesis](https://aws.amazon.com/kinesis/) 全面管理的基于云的服务，用于对大型分布式数据流进行实时数据处理.
* [RabbitMQ](https://www.rabbitmq.com/) 强大的应用程序消息传递.
* [FluentD](https://www.fluentd.org) 一个用于统一日志记录层的开源数据收集器.
* [Embulk](https://www.embulk.org) 开源的批量数据加载器，可帮助在各种数据库，存储，文件格式和云服务之间进行数据传输.
* [Apache Sqoop](https://sqoop.apache.org) 该工具旨在在Apache Hadoop和结构化数据存储（例如关系数据库）之间高效地传输批量数据.
* [Heka](https://github.com/mozilla-services/heka) 数据采集​​和处理变得容易. 不推荐使用.
* [Gobblin](https://github.com/apache/incubator-gobblin) 来自Linkedin的Hadoop通用数据提取框架
* [Nakadi](https://nakadi.io) Nakadi是一个开源事件消息平台，在类似于Kafka的队列上提供了REST API.
* [Pravega](http://www.pravega.io) Pravega为连续和无限制的数据提供了新的存储抽象-流.
* [Apache Pulsar](https://pulsar.apache.org/) Apache Pulsar是一个开源的分布式pub-sub消息传递系统.
* [AWS Data Wranlger](https://github.com/awslabs/aws-data-wrangler) 在AWS上处理数据的工具带.

## File System
* [HDFS](https://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html)
	* [Snakebite](https://github.com/spotify/snakebite) 一个纯Python HDFS客户端
* [AWS S3](https://aws.amazon.com/s3/)
	* [smart_open](https://github.com/RaRe-Technologies/smart_open) 实用程序，用于流传输大文件（S3，HDFS，gzip，bz2）
* [Alluxio](https://www.alluxio.org/) Alluxio是一个以内存为中心的分布式存储系统，可以跨集群框架（例如Spark和MapReduce）以内存速度可靠地共享数据.
* [CEPH](https://ceph.com/) Ceph是一个统一的分布式存储系统，旨在提供出色的性能，可靠性和可扩展性
* [OrangeFS](https://www.orangefs.org/) 橙色文件系统是并行虚拟文件系统的一个分支
* [SnackFS](https://github.com/tuplejump/snackfs-release) SnackFS是我们通过Cassandra构建的一口大小，轻量级HDFS兼容文件系统.
* [GlusterFS](https://www.gluster.org/) Gluster文件系统
* [XtreemFS](http://www.xtreemfs.org/) 容错的分布式文件系统，可满足所有存储需求
* [SeaweedFS](https://github.com/chrislusf/seaweedfs)  Seaweed-FS是一个简单且高度可扩展的分布式文件系统. 有两个目标：存储数十亿个文件！ 快速提供文件！ 除了支持完整的POSIX文件系统语义之外，Seaweed-FS选择仅实现密钥文件映射. 与单词“ NoSQL”相似，您可以将其称为“ NoFS”.
* [S3QL](https://github.com/s3ql/s3ql/) S3QL是一个文件系统，使用诸如Google Storage，Amazon S3或OpenStack之类的存储服务在线存储其所有数据.
* [LizardFS](https://lizardfs.com/) LizardFS软件定义的存储是一个分布式，并行，可伸缩，容错，地理冗余且高度可用的文件系统.

## Serialization format
* [Apache Avro](https://avro.apache.org) Apache Avro™是数据序列化系统
* [Apache Parquet](https://parquet.apache.org) Apache Parquet是Hadoop生态系统中任何项目均可使用的列式存储格式，而与数据处理框架，数据模型或编程语言的选择无关.
	* [Snappy](https://github.com/google/snappy) 快速压缩器/解压缩器. 与镶木地板一起使用
	* [PigZ](https://zlib.net/pigz/) gzip的并行实现，适用于现代
多处理器，多核机器
* [Apache ORC](https://orc.apache.org/) 适用于Hadoop工作负载的最小，最快的列式存储 
* [Apache Thrift](https://thrift.apache.org) Apache Thrift软件框架，用于可扩展的跨语言服务开发
* [ProtoBuf](https://github.com/protocolbuffers/protobuf) 协议缓冲区-Google的数据交换格式
* [SequenceFile](https://wiki.apache.org/hadoop/SequenceFile)  SequenceFile是一个平面文件，由二进制键/值对组成. 它在MapReduce中广泛用作输入/输出格式
* [Kryo](https://github.com/EsotericSoftware/kryo) Kryo是用于Java的快速高效的对象图序列化框架


## Stream Processing
* [Apache Beam](https://beam.apache.org/) Apache Beam是一个统一的编程模型，可实现在许多执行引擎上运行的批处理和流数据处理作业.
* [Spark Streaming](https://spark.apache.org/streaming/) Spark Streaming使构建可扩展的容错流应用程序变得容易.
* [Apache Flink](https://flink.apache.org/) Apache Flink是一个流数据流引擎，为数据流上的分布式计算提供数据分发，通信和容错能力.
* [Apache Storm](https://storm.apache.org) Apache Storm是一个免费的开源分布式实时计算系统
* [Apache Samza](https://samza.apache.org) Apache Samza是一个分布式流处理框架
* [Apache NiFi](https://nifi.apache.org/) 是一个易于使用，功能强大且可靠的系统，用于处理和分发数据
* [Apache Hudi](https://hudi.apache.org/) Apache Hudi是一个用于管理存储以进行实时处理的开源框架，最有趣的功能之一是Upsert
* [VoltDB](https://voltdb.com/) VoltDb是符合ACID的RDBMS，它使用 [shared nothing architecture](https://en.wikipedia.org/wiki/Shared-nothing_architecture).
* [PipelineDB](https://github.com/pipelinedb/pipelinedb) 流式SQL数据库
* [Spring Cloud Dataflow](https://cloud.spring.io/spring-cloud-dataflow/) Spring Boot应用之间的流传输和任务执行
* [Bonobo](https://www.bonobo-project.org/) Bonobo是适用于python 3.5+的数据处理工具包
* [Robinhood's Faust](https://github.com/robinhood/faust) 永久可扩展的事件处理和内存中持久性K / V存储，具有异步和静态类型的库.
* [HStreamDB](https://github.com/hstreamdb/hstream) 为物联网数据存储和实时处理而构建的流数据库.
* [Kuiper](https://github.com/emqx/kuiper) 由Golang实施的边缘轻量级IoT数据分析/流软件，可以在各种资源受限的边缘设备上运行.

## Batch Processing
* [Hadoop MapReduce](https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) Hadoop MapReduce是一个软件框架，用于轻松编写应用程序，以可靠，容错的方式并行处理大型硬件集群（数千个节点）上的大量数据（多TB数据集）.
* [Spark](https://spark.apache.org/)
	* [Spark Packages](https://spark-packages.org) Apache Spark软件包的社区索引
	* [Deep Spark](https://github.com/Stratio/deep-spark) 将Apache Spark与不同的数据存储连接. 不推荐使用.
	* [Spark RDD API Examples](http://homepage.cs.latrobe.edu.au/zhe/ZhenHeSparkRDDAPIExamples.html) 甄和
	* [Livy](https://livy.incubator.apache.org) Livy，REST Spark服务器
* [AWS EMR](https://aws.amazon.com/emr/) 一种Web服务，可轻松快速且经济高效地处理大量数据.
* [Tez](https://tez.apache.org/) 一个应用程序框架，允许使用复杂的有向无环图来处理数据.
* [Bistro](https://github.com/asavinov/bistro) 是用于通用数据处理（包括批处理和流分析）的轻量级引擎. 它基于新颖的独特数据模型，与通过MapReduce或SQL等传统方法仅设置操作相反，该模型通过*函数*表示数据，并通过*列操作*处理数据.
-批量ML
	* [H2O](https://www.h2o.ai/) 快速扩展的机器学习API，适用于更智能的应用程序.
	* [Mahout](https://mahout.apache.org/) 快速创建可扩展的高性能机器学习应用程序的环境.
	* [Spark MLlib](https://spark.apache.org/docs/latest/ml-guide.html) Spark的可扩展机器学习库由常见的学习算法和实用程序组成，包括分类，回归，聚类，协作过滤，降维和基础优化原语.
-批处理图
	* [GraphLab Create](https://turi.com/products/create/docs/) 一个机器学习平台，使数据科学家和应用程序开发人员可以轻松地大规模创建智能应用程序.
	* [Giraph](https://giraph.apache.org/) 为实现高可伸缩性而构建的迭代图处理系统. 
	* [Spark GraphX](https://spark.apache.org/graphx/) 用于图形和图形并行计算的Apache Spark API. 
-批处理SQL
	* [Presto](https://prestodb.github.io/docs/current/index.html) 一种分布式SQL查询引擎，用于查询分布在一个或多个异构数据源上的大型数据集.
	* [Hive](https://hive.apache.org) 数据仓库软件有助于查询和管理驻留在分布式存储中的大型数据集. 
		* [Hivemall](https://github.com/apache/incubator-hivemall) 适用于Hive / Hadoop的可扩展机器学习库.
		* [PyHive](https://github.com/dropbox/PyHive) Hive和Presto的Python接口.
	* [Drill](https://drill.apache.org/) 适用于Hadoop，NoSQL和云存储的无模式SQL查询引擎.

## Charts and Dashboards
* [Highcharts](https://www.highcharts.com/) 用纯JavaScript编写的图表库，提供了一种向网站或Web应用程序添加交互式图表的简便方法.
* [ZingChart](https://www.zingchart.com/) 适用于任何数据集的快速JavaScript图表.
* [C3.js](https://c3js.org) 基于D3的可重用图表库.
* [D3.js](https://d3js.org/) 一个JavaScript库，用于根据数据处理文档.
	* [D3Plus](https://d3plus.org)  D3更简单，更易于使用的表弟. 通常，您可以插入数据的预定义模板.
* [SmoothieCharts](http://smoothiecharts.org) 用于流数据的JavaScript图表库.
* [PyXley](https://github.com/stitchfix/pyxley) 使用Flask和React构建仪表板的Python帮助器
* [Plotly](https://github.com/plotly/dash) Flask，JS和CSS样板，用于Python中基于Web的交互式交互式可视化应用
* [Apache Superset](https://github.com/apache/incubator-superset) Apache Superset（孵化中）是一种现代的，可用于企业的商业智能Web应用程序
* [Redash](https://redash.io/) 使您的公司数据驱动. 连接到任何数据源，轻松可视化并共享您的数据.
* [Metabase](https://github.com/metabase/metabase) Metabase是公司中每个人都可以提出问题并从数据中学习的一种简单，开源的方式.
* [PyQtGraph](http://www.pyqtgraph.org/)  PyQtGraph是基于PyQt4 / PySide和numpy构建的纯Python图形和GUI库. 它旨在用于数学/科学/工程应用.


## Workflow
* [Luigi](https://github.com/spotify/luigi) Luigi是一个Python模块，可帮助您构建批处理作业的复杂管道.
	* [CronQ](https://github.com/seatgeek/cronq) 类似cron的应用程序系统. [Used](https://chairnerd.seatgeek.com/building-out-the-seatgeek-data-pipeline/)  w /路易丝. 不推荐使用.
* [Cascading](https://www.cascading.org/) 基于Java的应用程序开发平台.
* [Airflow](https://github.com/apache/airflow) Airflow是一个用于以编程方式编写，计划和监视数据管道的系统.
* [Azkaban](https://azkaban.github.io/)  Azkaban是在LinkedIn上创建的用于运行Hadoop作业的批处理工作流作业调度程序.  Azkaban通过工作依赖性解决订购问题，并提供易于使用的Web用户界面来维护和跟踪您的工作流程. 
* [Oozie](https://oozie.apache.org/) Oozie是一个工作流调度程序系统，用于管理Apache Hadoop作业
* [Pinball](https://github.com/pinterest/pinball) 基于DAG的工作流管理器. 作业流是使用Python编程定义的. 支持作业之间传递的输出.
* [Dagster](https://github.com/dagster-io/dagster) Dagster是用于构建数据应用程序的开源Python库.
 * [Dataform]（https://dataform.co/）是一个开放源代码框架和基于Web的IDE，用于管理数据集及其依赖项.  SQLX扩展了您现有的SQL仓库方言，以添加支持依赖关系管理，测试，文档等的功能.
* [Census](https://getcensus.com/) 是一个反向ETL工具，使您可以将云数据仓库中的数据同步到SaaS应用程序（如Salesforce，Marketo，HubSpot，Zendesk等）.
* [dbt](https://getdbt.com/) 是一个命令行工具，使数据分析人员和工程师可以更有效地转换仓库中的数据.

## Data Lake Management
* [lakeFS](https://github.com/treeverse/lakeFS) lakeFS是一个开放源代码平台，可为基于对象存储的数据湖提供弹性和可管理性.

## ELK Elastic Logstash Kibana
* [docker-logstash](https://github.com/pblittle/docker-logstash) 运行Elasticsearch（1.7.0）和Kibana（3.1.2）的高度可配置的logstash（1.4.4）docker映像.
* [elasticsearch-jdbc](https://github.com/jprante/elasticsearch-jdbc) 用于Elasticsearch的JDBC导入器
* [ZomboDB](https://github.com/zombodb/zombodb) Postgres扩展，允许创建由Elasticsearch支持的索引

## Docker
* [Gockerize](https://github.com/redbooth/gockerize) 将golang服务打包到最小的docker容器中
* [Flocker](https://github.com/ClusterHQ/flocker) 轻松管理Docker容器及其数据
* [Rancher](https://rancher.com/rancher-os/) RancherOS是一个20mb的Linux发行版，可将整个操作系统作为Docker容器运行
* [Kontena](https://www.kontena.io/) 大众应用容器
* [Weave](https://github.com/weaveworks/weave) 将Docker容器编织到应用程序中
* [Zodiac](https://github.com/CenturyLinkLabs/zodiac) 轻量级工具，可轻松部署和回滚dockerized应用程序
* [cAdvisor](https://github.com/google/cadvisor) Analyzes resource usage and performance characteristics of running containers
* [Micro S3 persistence](https://github.com/figadore/micro-s3-persistence) 用于将卷数据保存/还原到S3的Docker微服务
* [Rocker-compose](https://github.com/grammarly/rocker-compose) 具有幂等功能的Docker组合工具，可用于部署由多个容器组成的应用程序. 不推荐使用.
* [Nomad](https://github.com/hashicorp/nomad) Nomad是一个集群管理器，设计用于长期服务和短期批处理工作负载
* [ImageLayers](https://imagelayers.io/) 对Docker映像及其组成的图层进行Vizualize


## Datasets
## Realtime
* [Twitter Realtime](https://developer.twitter.com/en/docs/tweets/filter-realtime/overview) 流API使开发人员可以低延迟访问Twitter的全球Tweet数据流.
* [Eventsim](https://github.com/Interana/eventsim) 事件数据模拟器. 从一组用户生成伪随机事件流，用于模拟Web流量.
* [Reddit](https://www.reddit.com/r/datasets/comments/3mk1vg/realtime_data_is_available_including_comments/) 提供实时数据，包括评论，提交和发布到reddit的链接

## Data Dumps
* [GitHub Archive](https://www.gharchive.org/) 自2011年以来GitHub的公开时间表，每小时更新一次
* [Common Crawl](https://commoncrawl.org/) Web爬网数据的开源存储库
* [Wikipedia](https://dumps.wikimedia.org/enwiki/latest/)  Wikipedia所有Wiki的完整副本，形式为Wikitext源和嵌入在XML中的元数据. 还提供了许多SQL形式的原始数据库表.

## Monitoring

## Prometheus
* [Prometheus.io](https://github.com/prometheus/prometheus) 开源服务监视系统和时间序列数据库
* [HAProxy Exporter](https://github.com/prometheus/haproxy_exporter) 简单的服务器，可抓取HAProxy统计信息并通过HTTP导出以供Prometheus使用

## Community

## Forums
* [/r/dataengineering](https://www.reddit.com/r/dataengineering/) 数据工程的新闻，技巧和背景
* [/r/etl](https://www.reddit.com/r/ETL/) Subreddit专注于ETL

## Conferences
* [DataEngConf](https://www.datacouncil.ai/about) DataEngConf是第一个弥合数据科学家，数据工程师和数据分析师之间鸿沟的技术会议.

## Podcasts
* [Data Engineering Podcast](https://www.dataengineeringpodcast.com/) 关于现代数据基础架构的展示.

欢呼 [The Data Engineering Ecosystem: An Interactive Map](http://xyz.insightdataengineering.com/blog/pipeline_map.html)

受启发 [awesome](https://github.com/sindresorhus/awesome) 列表. 由...制作 [Insight Data Engineering](https://insightdataengineering.com) 研究员.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Igor Barinov](https://github.com/igorbarinov/) 放弃了此作品的所有版权以及相关或邻近的权利.
