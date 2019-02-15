<div class="github-widget" data-repo="igorbarinov/awesome-data-engineering"></div>
令人敬畏的数据工程
==========================

为软件开发人员提供的精选数据工程工具列表 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

内容清单


## Databases
- 关系
	* [RQLite](https://github.com/rqlite/rqlite) 使用Raft共识协议复制SQLite
	* [MySQL](https://www.mysql.com/) 世界上最流行的开源数据库.
		* [TiDB](https://github.com/pingcap/tidb) TiDB是一个与MySQL协议兼容的分布式NewSQL数据库
		* [Percona XtraBackup](https://www.percona.com/software/mysql-database/percona-xtrabackup) Percona XtraBackup是一款免费的开源完整在线备份解决方案，适用于Percona Server，MySQL®和MariaDB®的所有版本
		* [mysql_utils](https://github.com/pinterest/mysql_utils) Pinterest MySQL管理工具
	* [MariaDB](https://mariadb.org/) MySQL的增强型替代品.
	* [PostgreSQL](https://www.postgresql.org/) 世界上最先进的开源数据库.
	* [Amazon RDS](https://aws.amazon.com/rds/) Amazon RDS使您可以轻松地在云中设置，操作和扩展关系数据库. 
	* [Crate.IO](https://crate.io/) 具有NOSQL好处的可扩展SQL数据库.
- 核心价值
	* [Redis](https://redis.io/) 开源，BSD许可，高级键值缓存和存储.
	* [Riak](http://docs.basho.com/riak/kv/) 分布式数据库，旨在通过跨多个服务器分发数据来提供最大的数据可用性
	* [AWS DynamoDB](https://aws.amazon.com/dynamodb/) 快速灵活的NoSQL数据库服务，适用于任何需要一致，单位数毫秒延迟的所有应用程序.
	* [HyperDex](https://github.com/rescrv/HyperDex)  HyperDex是一个可扩展，可搜索的键值存储.  已过时.
	* [SSDB](http://ssdb.io) 支持许多数据结构的高性能NoSQL数据库，是Redis的替代品
	* [Kyoto Tycoon](https://github.com/alticelabs/kyoto) Kyoto Tycoon是一个轻量级的网络服务器，位于Kyoto Cabinet键值数据库之上，专为高性能和并发而构建
	* [IonDB](https://github.com/iondbproject/iondb) 微控制器和物联网应用的键值存储
- 专栏
	* [Cassandra](https://cassandra.apache.org/) 当您需要可扩展性和高可用性而不影响性能时，这是正确的选择.
		* [Cassandra Calculator](https://www.ecyrd.com/cassandracalculator/) 这个简单的表单允许您为Apache Cassandra集群尝试不同的值，并查看对您的应用程序有何影响.
		* [CCM](https://github.com/pcmanus/ccm) 一个在localhost上轻松创建和销毁Apache Cassandra集群的脚本
		* [ScyllaDB](https://github.com/scylladb/scylla) 使用海星框架的NoSQL数据存储，与Apache Cassandra兼容https://www.scylladb.com/
	* [HBase](https://hbase.apache.org/) Hadoop数据库，一个分布式，可扩展的大数据存储.
	* [AWS Redshift](https://aws.amazon.com/redshift/) 一个快速，完全托管，PB级数据仓库，使用现有的商业智能工具分析所有数据，简单且经济高效.
	* [FiloDB](https://github.com/filodb/FiloDB)  分散式.  柱状.  版本控制.  流.  SQL.
	* [Vertica](https://www.vertica.com) 分布式，MPP柱状数据库，具有广泛的分析SQL.
- 文件
	* [MongoDB](https://www.mongodb.com) 一个开源的文档数据库，旨在简化开发和扩展. 
		* [Percona Server for MongoDB](https://www.percona.com/software/mongo-database/percona-server-for-mongodb) Percona ServerforMongoDB®是MongoDB®CommunityEdition的免费，增强，完全兼容，开源，替代品，包括企业级特性和功能.
		* [MemDB](https://github.com/rain1017/memdb) 分布式事务内存数据库（基于MongoDB）
	* [Elasticsearch](https://www.elastic.co/) 实时搜索和分析数据.
	* [Couchbase](https://www.couchbase.com/) 性能最高的NoSQL分布式数据库.
	* [RethinkDB](https://rethinkdb.com/) 实时网络的开源数据库.
	* [RavenDB](https://ravendb.net/) 完全事务性的NoSQL文档数据库.
- 图表
	* [Neo4j](https://neo4j.com/) 世界领先的图形数据库.
	* [OrientDB](https://orientdb.com) 第二代分布式图形数据库，具有文档的灵活性，在一个产品中具有开源商业友好许可证.
	* [ArangoDB](https://www.arangodb.com/) 分布式免费和开源数据库，具有用于文档，图形和键值的灵活数据模型. 
	* [Titan](https://titan.thinkaurelius.com) 可扩展的图形数据库，针对存储和查询包含分布在多机群集中的数百亿个顶点和边缘的图形进行了优化.
	* [FlockDB](https://github.com/twitter-archive/flockdb)  Twitter提供的分布式容错图数据库.  已过时.
- 分散式
	* [DAtomic](https://www.datomic.com) 完全事务性，云就绪的分布式数据库.
	* [Apache Geode](https://geode.apache.org/) 用于横向扩展应用程序的开源，分布式内存数据库.
	* [Gaffer ](https://github.com/gchq/Gaffer) 一个大型的图形数据库
- 时间序列
	* [InfluxDB](https://github.com/influxdata/influxdb) 可扩展的数据存储区，用于指标，事件和实时分析.
	* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) 可扩展的分布式时间序列数据库.
	* [kairosdb](https://github.com/kairosdb/kairosdb) 快速可扩展的时间序列数据
	* [Heroic](https://github.com/spotify/heroic) Spotify基于Cassandra和Elasticsearch的可扩展时间序列数据库
	* [Druid](https://github.com/apache/incubator-druid) 面向列的分布式数据存储非常适合为交互式应用程
	* [Riak-TS](http://basho.com/products/riak-ts/) Riak TS是唯一专门针对物联网和时间序列数据进行优化的企业级NoSQL时间序列数据库
	* [Akumuli](https://github.com/akumuli/Akumuli)  Akumuli是一个数字时间序列数据库.  它可用于实时捕获，存储和处理时间序列数据.  “akumuli”这个词可以从世界语翻译为“积累”.
	* [Rhombus](https://github.com/Pardot/Rhombus) Cassandra的时间序列对象存储库，用于处理构建宽行索引的所有复杂性.
	* [Dalmatiner DB](https://github.com/dalmatinerdb/dalmatinerdb) 快速分布式度量数据库
	* [Blueflood](https://github.com/rackerlabs/blueflood) 用于摄取和处理时间序列数据的分布式系统
	* [Timely](https://github.com/NationalSecurityAgency/timely) Timely是一个时间序列数据库应用程序，提供基于Accumulo和Grafana的时间序列数据的安全访问.
- 其他
	* [Tarantool](https://github.com/tarantool/tarantool/) Tarantool是一个内存数据库和应用程序服务器.
	* [GreenPlum](https://github.com/greenplum-db/gpdb)  Greenplum数据库（GPDB）是一个高级，功能齐全的开源数据仓库.  它提供了对PB级数据量的强大而快速的分析.
	* [cayley](https://github.com/cayleygraph/cayley)  一个开源图形数据库.  谷歌.
	* [Snappydata](https://github.com/SnappyDataInc/snappydata) SnappyData：基于Apache Spark构建的OLTP + OLAP数据库

## Data Ingestion
* [Kafka](https://kafka.apache.org/) 发布 - 订阅消息传递作为分布式提交日志重新考虑.
	* [BottledWater](https://github.com/confluentinc/bottledwater-pg)  将数据捕获从PostgreSQL更改为Kafka.  已过时.
	* [kafkat](https://github.com/airbnb/kafkat) 简化了Kafka代理的命令行管理
	* [kafkacat](https://github.com/edenhill/kafkacat) 通用命令行非JVM Apache Kafka生产者和消费者
	* [pg-kafka](https://github.com/xstevens/pg_kafka) PostgreSQL扩展，用于向Apache Kafka生成消息
	* [librdkafka](https://github.com/edenhill/librdkafka) Apache Kafka C / C ++库
	* [kafka-docker](https://github.com/wurstmeister/kafka-docker) Docker中的卡夫卡
	* [kafka-manager](https://github.com/yahoo/kafka-manager) 用于管理Apache Kafka的工具
	* [kafka-node](https://github.com/SOHU-Co/kafka-node) Apache Kafka 0.8的Node.js客户端
	* [Secor](https://github.com/pinterest/secor) Pinterest的Kafka向S3分销消费者
	* [Kafka-logger](https://github.com/uber/kafka-logger) 来自uber的nodejs的Kafka-winston记录器
* [AWS Kinesis](https://aws.amazon.com/kinesis/) 一种完全托管的基于云的服务，用于在大型分布式数据流上进行实时数据处理.
* [RabbitMQ](https://www.rabbitmq.com/) 应用程序的强大消息传递.
* [FluentD](https://www.fluentd.org) 用于统一日志记录层的开源数据收集器.
* [Embulk](https://www.embulk.org) 一种开源批量数据加载器，可帮助在各种数据库，存储，文件格式和云服务之间进行数据传输.
* [Apache Sqoop](https://sqoop.apache.org) 一种工具，用于在Apache Hadoop和结构化数据存储（如关系数据库）之间高效传输批量数据.
* [Heka](https://github.com/mozilla-services/heka)  数据采集​​和处理变得简单.  已过时.
* [Gobblin](https://github.com/apache/incubator-gobblin) 来自Linkedin的Hadoop通用数据提取框架
* [Nakadi](https://nakadi.io) Nakadi是一个开源事件消息传递平台，它在类似Kafka的队列之上提供REST API.
* [Pravega](http://www.pravega.io) Pravega为连续和无界数据提供了一种新的存储抽象 - 流.
* [Apache Pulsar](https://pulsar.apache.org/) Apache Pulsar是一个开源的分布式pub-sub消息系统.

## File System
* [HDFS](https://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html)
	* [Snakebite](https://github.com/spotify/snakebite) 一个纯python HDFS客户端
* [AWS S3](https://aws.amazon.com/s3/)
	* [smart_open](https://github.com/RaRe-Technologies/smart_open) 用于流式传输大型文件的工具（S3，HDFS，gzip，bz2）
* [Alluxio](https://www.alluxio.org/) Alluxio是一个以内存为中心的分布式存储系统，可以跨群集框架以内存速度实现可靠的数据共享，例如Spark和MapReduce
* [CEPH](https://ceph.com/) Ceph是一个统一的分布式存储系统，旨在实现出色的性能，可靠性和可扩展性
* [OrangeFS](https://www.orangefs.org/) Orange File System是并行虚拟文件系统的一个分支
* [SnackFS](https://github.com/tuplejump/snackfs-release) SnackFS是我们在Cassandra上构建的一口大小，轻量级的HDFS兼容文件系统
* [GlusterFS](https://www.gluster.org/) Gluster文件系统
* [XtreemFS](http://www.xtreemfs.org/) fault-tolerant distributed file system for all storage needs
* [SeaweedFS](https://github.com/chrislusf/seaweedfs)  Seaweed-FS是一个简单且高度可扩展的分布式文件系统.  有两个目标：存储数十亿个文件！  快速提供文件！  Seaweed-FS选择仅实现一个key~文件映射，而不是支持完整的POSIX文件系统语义.  与“NoSQL”一词类似，您可以将其称为“NoFS”.
* [S3QL](https://github.com/s3ql/s3ql/) S3QL是一个文件系统，使用Google Storage，Amazon S3或OpenStack等存储服务在线存储其所有数据.
* [LizardFS](https://lizardfs.com/) LizardFS软件定义存储是一种分布式，并行，可扩展，容错，Geo-Redundant和高可用性文件系统.

## Serialization format
* [Apache Avro](https://avro.apache.org) Apache Avro™是一种数据序列化系统
* [Apache Parquet](https://parquet.apache.org) Apache Parquet是一种柱状存储格式，可用于Hadoop生态系统中的任何项目，无论选择何种数据处理框架，数据模型或编程语言.
	* [Snappy](https://github.com/google/snappy)  快速压缩器/解压缩器.  与Parquet一起使用
	* [PigZ](https://zlib.net/pigz/) 现代gzip的并行实现
多处理器，多核机器
* [Apache ORC](https://orc.apache.org/) 适用于Hadoop工作负载的最小，最快的柱状存储 
* [Apache Thrift](https://thrift.apache.org) Apache Thrift软件框架，用于可扩展的跨语言服务开发
* [ProtoBuf](https://github.com/protocolbuffers/protobuf) 协议缓冲区 - 谷歌的数据交换格式
* [SequenceFile](https://wiki.apache.org/hadoop/SequenceFile)  SequenceFile是一个由二进制键/值对组成的平面文件.  它广泛用于MapReduce作为输入/输出格式
* [Kryo](https://github.com/EsotericSoftware/kryo) Kryo是一个快速有效的Java对象图序列化框架


## Stream Processing
* [Apache Beam](https://beam.apache.org/) Apache Beam是一种统一的编程模型，可以实现在许多执行引擎上运行的批处理和流数据处理作业.
* [Spark Streaming](https://spark.apache.org/streaming/) Spark Streaming可以轻松构建可扩展的容错流应用程序.
* [Apache Flink](https://flink.apache.org/) Apache Flink是一种流数据流引擎，可为数据流上的分布式计算提供数据分发，通信和容错.
* [Apache Storm](https://storm.apache.org) Apache Storm是一个免费的开源分布式实时计算系统
* [Apache Samza](https://samza.apache.org) Apache Samza是一个分布式流处理框架
* [Apache NiFi](https://nifi.apache.org/) 是一个易于使用，功能强大，可靠的系统来处理和分发数据
* [VoltDB](https://voltdb.com/) VoltDb是一个符合ACID标准的RDBMS，它使用了 [shared nothing architecture](https://en.wikipedia.org/wiki/Shared-nothing_architecture).
* [PipelineDB](https://github.com/pipelinedb/pipelinedb) 流式SQL数据库
* [Spring Cloud Dataflow](https://cloud.spring.io/spring-cloud-dataflow/) Spring Boot应用程序之间的流和任务执行
* [Bonobo](https://www.bonobo-project.org/) Bonobo是python 3.5+的数据处理工具包
* [Robinhood's Faust](https://github.com/robinhood/faust) 永久可扩展的事件处理和内存持久的K / V存储作为具有asyncio和静态类型的库.

## Batch Processing
* [Hadoop MapReduce](https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) Hadoop MapReduce是一个软件框架，用于轻松编写应用程序，以可靠，容错的方式在大型集群（数千个节点）的商用硬件上并行处理大量数据（多TB数据集）
* [Spark](https://spark.apache.org/)
	* [Spark Packages](https://spark-packages.org) Apache Spark的包的社区索引
	* [Deep Spark](https://github.com/Stratio/deep-spark)  将Apache Spark与不同的数据存储连接起来.  已过时.
	* [Spark RDD API Examples](http://homepage.cs.latrobe.edu.au/zhe/ZhenHeSparkRDDAPIExamples.html) 由何和
	* [Livy](https://livy.incubator.apache.org) Livy，REST Spark服务器
* [AWS EMR](https://aws.amazon.com/emr/) 一种Web服务，可以轻松快速，经济高效地处理大量数据.
* [Tez](https://tez.apache.org/) 一个应用程序框架，允许处理数据的任务的复杂的有向非循环图.
* [Bistro](https://github.com/asavinov/bistro)  是一种轻量级引擎，用于通用数据处理，包括批处理和流分析.  它基于一种新颖的独特数据模型，它通过* functions *表示数据，并通过* columns操作*处理数据，而不是只在MapReduce或SQL等传统方法中设置操作.
- 批量ML
	* [H2O](https://www.h2o.ai/) Fast scalable machine learning API for smarter applications.
	* [Mahout](https://mahout.apache.org/) 一种快速创建可扩展的高性能机器学习应用程序的环境.
	* [Spark MLlib](https://spark.apache.org/docs/latest/ml-guide.html) Spark的可扩展机器学习库由通用学习算法和实用程序组成，包括分类，回归，聚类，协同过滤，降维，以及底层优化原语.
- 批量图
	* [GraphLab Create](https://turi.com/products/create/docs/) 机器学习平台，使数据科学家和应用程序开发人员能够轻松地大规模创建智能应用程序
	* [Giraph](https://giraph.apache.org/) 为高可扩展性而构建的迭代图处理系统. 
	* [Spark GraphX](https://spark.apache.org/graphx/) Apache Spark用于图形和图形并行计算的API. 
- 批处理SQL
	* [Presto](https://prestodb.github.io/docs/current/index.html) 一种分布式SQL查询引擎，用于查询分布在一个或多个异构数据源上的大型数据集.
	* [Hive](https://hive.apache.org) 数据仓库软件有助于查询和管理驻留在分布式存储中的大型数据集. 
		* [Hivemall](https://github.com/apache/incubator-hivemall) 适用于Hive / Hadoop的可扩展机器学习库.
		* [PyHive](https://github.com/dropbox/PyHive) Hive和Presto的Python接口.
	* [Drill](https://drill.apache.org/) 用于Hadoop，NoSQL和云存储的无架构SQL查询引擎.

## Charts and Dashboards
* [Highcharts](https://www.highcharts.com/) 使用纯JavaScript编写的图表库，提供了一种向您的网站或Web应用程序添加交互式图表的简便方法.
* [ZingChart](https://www.zingchart.com/) 任何数据集的快速JavaScript图表.
* [C3.js](https://c3js.org) 基于D3的可重用图表库.
* [D3.js](https://d3js.org/) 用于根据数据操作文档的JavaScript库.
	* [D3Plus](https://d3plus.org)  D3更简单，更易于使用.  大多数预定义的模板，您只需插入数据即可.
* [SmoothieCharts](http://smoothiecharts.org) 用于流数据的JavaScript图表库.
* [PyXley](https://github.com/stitchfix/pyxley) 用于使用Flask和React构建仪表板的Python助手
* [Plotly](https://github.com/plotly/dash) Flask，JS和CSS样板，用于Python中基于Web的交互式可视化应用程序
* [Apache Superset](https://github.com/apache/incubator-superset) Apache Superset（孵化）是一个现代化的企业级商业智能Web应用程序
* [Redash](https://redash.io/)  使您的公司数据受到驱动.  连接到任何数据源，轻松可视化和共享您的数据.
* [Metabase](https://github.com/metabase/metabase) Metabase是一种简单，开源的方式，可供公司中的每个人提问并从数据中学习.
* [PyQtGraph](http://www.pyqtgraph.org/)  PyQtGraph是一个基于PyQt4 / PySide和numpy的纯python图形和GUI库.  它适用于数学/科学/工程应用.


## Workflow
* [Luigi](https://github.com/spotify/luigi) Luigi是一个Python模块，可帮助您构建批处理作业的复杂管道.
	* [CronQ](https://github.com/seatgeek/cronq) 应用程序类似cron的系统. [Used](https://chairnerd.seatgeek.com/building-out-the-seatgeek-data-pipeline/)  W / Luige.  已过时.
* [Cascading](https://www.cascading.org/) 基于Java的应用程序开发平台
* [Airflow](https://github.com/apache/airflow) Airflow是一个程序化编写，计划和监控数据管道的系统.
* [Azkaban](https://azkaban.github.io/)  Azkaban是在LinkedIn上创建的批处理工作流作业调度程序，用于运行Hadoop作业.  Azkaban通过作业依赖性解决订单，并提供易于使用的Web用户界面来维护和跟踪您的工作流程. 
* [Oozie](https://oozie.apache.org/) Oozie是一个用于管理Apache Hadoop作业的工作流程调度程序系统
* [Pinball](https://github.com/pinterest/pinball)  基于DAG的工作流管理器.  工作流程在Python中以编程方式定义.  支持在作业之间传递输出.

## ELK Elastic Logstash Kibana
* [docker-logstash](https://github.com/pblittle/docker-logstash) 一个高度可配置的logstash（1.4.4）docker镜像，运行Elasticsearch（1.7.0）和Kibana（3.1.2）.
* [elasticsearch-jdbc](https://github.com/jprante/elasticsearch-jdbc) Elasticsearch的JDBC导入器
* [ZomboDB](https://github.com/zombodb/zombodb) Postgres扩展，允许创建由Elasticsearch支持的索引

## Docker
* [Gockerize](https://github.com/redbooth/gockerize) 将golang服务打包成最小的docker容器
* [Flocker](https://github.com/ClusterHQ/flocker) 轻松管理Docker容器及其数据
* [Rancher](https://rancher.com/rancher-os/) RancherOS是一个20mb的Linux发行版，它将整个操作系统作为Docker容器运行
* [Kontena](https://www.kontena.io/) 大众应用容器
* [Weave](https://github.com/weaveworks/weave) 将Docker容器编织到应用程序中
* [Zodiac](https://github.com/CenturyLinkLabs/zodiac) 轻量级工具，可轻松部署和回滚dockerized应用程序
* [cAdvisor](https://github.com/google/cadvisor) 分析正在运行的容器的资源使用情况和性能特征
* [Micro S3 persistence](https://github.com/figadore/micro-s3-persistence) Docker微服务，用于将卷数据保存/恢复到S3
* [Rocker-compose](https://github.com/grammarly/rocker-compose)  具有idempotency功能的Docker组合工具，用于部署由多个容器组成的应用程序.  已过时.
* [Nomad](https://github.com/hashicorp/nomad) Nomad是一个集群管理器，专为长期服务和短期批处理工作负载而设计
* [ImageLayers](https://imagelayers.io/) Vizualize docker图像和组成它们的图层


## Datasets
## Realtime
* [Twitter Realtime](https://developer.twitter.com/en/docs/tweets/filter-realtime/overview) Streaming API为开发人员提供了对Twitter全球Tweet数据流的低延迟访问.
* [Eventsim](https://github.com/Interana/eventsim)  事件数据模拟器.  从一组用户生成伪随机事件流，旨在模拟Web流量.
* [Reddit](https://www.reddit.com/r/datasets/comments/3mk1vg/realtime_data_is_available_including_comments/) 提供实时数据，包括发布到reddit的评论，提交和链接

## Data Dumps
* [GitHub Archive](https://www.gharchive.org/) GitHub自2011年以来的公共时间表，每小时更新一次
* [Common Crawl](https://commoncrawl.org/) Web爬网数据的开源存储库
* [Wikipedia](https://dumps.wikimedia.org/enwiki/latest/)  维基百科所有wiki的完整副本，以wikitext源和XML中嵌入的元数据的形式.  还提供了许多SQL表单的原始数据库表.

## Monitoring

## Prometheus
* [Prometheus.io](https://github.com/prometheus/prometheus) 开源服务监控系统和时间序列数据库
* [HAProxy Exporter](https://github.com/prometheus/haproxy_exporter) 简单的服务器，用于擦除HAProxy统计信息并通过HTTP导出它们以供Prometheus使用

## Community

## Forums
* [/r/dataengineering](https://www.reddit.com/r/dataengineering/) 数据工程的新闻，技巧和背景
* [/r/etl](https://www.reddit.com/r/ETL/) Subreddit专注于ETL

## Conferences
* [DataEngConf](https://www.datacouncil.ai/about) DataEngConf是第一个弥合数据科学家，数据工程师和数据分析师之间差距的技术会议.

## Podcasts
* [Data Engineering Podcast](https://www.dataengineeringpodcast.com/) 关于现代数据基础设施的展示.

干杯 [The Data Engineering Ecosystem: An Interactive Map](http://xyz.insightdataengineering.com/blog/pipeline_map.html)

灵感来自于 [awesome](https://github.com/sindresorhus/awesome)  名单.  由...制作 [Insight Data Engineering](https://insightdataengineering.com) 研究员.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Igor Barinov](https://github.com/igorbarinov/) 已放弃对此作品的所有版权及相关或相邻权利.
