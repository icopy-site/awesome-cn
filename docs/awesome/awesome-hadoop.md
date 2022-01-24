<div class="github-widget" data-repo="youngwookim/awesome-hadoop"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Hadoop [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

令人惊叹的 Hadoop 和 Hadoop 生态系统资源的精选列表. 灵感来自 [Awesome PHP](https://github.com/ziadoz/awesome-php), [Awesome Python](https://github.com/vinta/awesome-python) 和 [Awesome Sysadmin](https://github.com/kahun/awesome-sysadmin)


## Hadoop

* [Apache Hadoop](http://hadoop.apache.org/) - 阿帕奇Hadoop
* [Apache Hadoop Ozone](http://hadoop.apache.org/ozone/) - Apache Hadoop 的对象存储
* [Apache Tez](http://tez.apache.org/) - Hadoop 中基于 YARN 的数据处理应用程序框架
* [SpatialHadoop](http://spatialhadoop.cs.umn.edu/) - SpatialHadoop 是 Apache Hadoop 的 MapReduce 扩展，专门设计用于处理空间数据. 
* [GIS Tools for Hadoop](http://esri.github.io/gis-tools-for-hadoop/) - Hadoop 框架的大数据空间分析
* [Elasticsearch Hadoop](https://github.com/elastic/elasticsearch-hadoop)  - Elasticsearch 实时搜索和分析与 Hadoop 原生集成. 支持 Map/Reduce、级联、Apache Hive 和 Apache Pig.
* [hadoopy](https://github.com/bwhite/hadoopy) - 用 Cython 编写的 Python MapReduce 库. 
* [mrjob](https://github.com/Yelp/mrjob/) - mrjob 是一个 Python 2.5+ 包，可帮助您编写和运行 Hadoop Streaming 作业.
* [pydoop](http://pydoop.sourceforge.net/) - Pydoop 是一个为 Hadoop 提供 Python API 的包.
* [hdfs-du](https://github.com/twitter/hdfs-du) - HDFS-DU 是 Hadoop 分布式文件系统的交互式可视化. 
* [White Elephant](https://github.com/linkedin/white-elephant) - Hadoop 日志聚合器和仪表板
* [Genie](https://github.com/Netflix/genie) - Genie 提供 REST-ful API 来运行 Hadoop、Hive 和 Pig 作业，并管理多个 Hadoop 资源并在它们之间执行作业提交.
* [Apache Kylin](http://kylin.incubator.apache.org/) - Apache Kylin 是来自 eBay Inc. 的开源分布式分析引擎，它在支持超大型数据集的 Hadoop 上提供 SQL 接口和多维分析 (OLAP)
* [Crunch](https://github.com/jondot/crunch) - 基于 Go 的 ETL 工具包和 Hadoop 上的特征提取
* [Apache Ignite](http://ignite.apache.org/) - 分布式内存平台

## YARN

* [Apache Slider](http://slider.incubator.apache.org/) - Apache Slider 是 Apache 软件基金会的一个孵化项目，其目标是使现有应用程序能够轻松地部署到 YARN 集群上.
* [Apache Twill](http://twill.incubator.apache.org/) - Apache Twill 是对 Apache Hadoop® YARN 的抽象，它降低了开发分布式应用程序的复杂性，使开发人员能够更多地关注他们的应用程序逻辑.
* [mpich2-yarn](https://github.com/alibaba/mpich2-yarn) - 在 Yarn 上运行 MPICH2

## NoSQL
*下一代数据库主要解决一些问题：非关系型、分布式、开源和水平可扩展.*

* [Apache HBase](http://hbase.apache.org) - Apache HBase
* [Apache Phoenix](http://phoenix.apache.org/) - 支持二级索引的 HBase 上的 SQL 皮肤
* [happybase](https://github.com/wbolster/happybase) - 一个开发人员友好的 Python 库，用于与 Apache HBase 交互.
* [Hannibal](https://github.com/sentric/hannibal) - Hannibal 是帮助监控和维护配置为手动拆分的 HBase-Cluster 的工具.
* [Haeinsa](https://github.com/VCNC/haeinsa) - Haeinsa 是用于 HBase 的线性可扩展多行、多表事务库
* [hindex](https://github.com/Huawei-Hadoop/hindex) - HBase 的二级索引
* [Apache Accumulo](https://accumulo.apache.org/) - Apache Accumulo™ 排序的分布式键/值存储是一个健壮的、可扩展的、高性能的数据存储和检索系统.
* [OpenTSDB](http://opentsdb.net/) - 可扩展的时间序列数据库
* [Apache Cassandra](http://cassandra.apache.org/)

## SQL on Hadoop
*Hadoop 上的 SQL*

* [Apache Hive](http://hive.apache.org) - Apache Hive 数据仓库软件有助于使用 SQL 读取、写入和管理驻留在分布式存储中的大型数据集
* [Apache Phoenix](http://phoenix.apache.org) 支持二级索引的 HBase 上的 SQL 皮肤
* [Apache HAWQ (incubating)](http://hawq.incubator.apache.org/) - Apache HAWQ 是一个 Hadoop 原生 SQL 查询引擎，结合了 MPP 数据库的关键技术优势和 Hadoop 的可扩展性和便利性
* [Lingual](http://www.cascading.org/projects/lingual/) - 级联的 SQL 接口（MR/Tez 作业生成器）
* [Apache Impala](https://impala.apache.org/)  - Apache Impala 是一个开源的大规模并行处理 (MPP) SQL 查询引擎，用于存储在运行 Apache Hadoop 的计算机集群中的数据.  Impala 被描述为 Google F1 的开源等价物，它在 2012 年激发了它的开发.
* [Presto](https://prestodb.io/)  - 用于大数据的分布式 SQL 查询引擎. 由 Facebook 开源.
* [Apache Tajo](http://tajo.apache.org/) - Apache Hadoop的数据仓库系统
* [Apache Drill](https://drill.apache.org/) - 无模式 SQL 查询引擎
* [Apache Trafodion](http://trafodion.apache.org/)

## Data Management

* [Apache Calcite](http://calcite.apache.org/) - 动态数据管理框架
* [Apache Atlas](http://atlas.incubator.apache.org/) - 支持复杂业务数据分类的元数据标记和沿袭捕获
* [Apache Kudu](https://kudu.apache.org/) - Kudu 提供快速插入/更新和高效列扫描的组合，以支持跨单个存储层的多个实时分析工作负载，补充 HDFS 和 Apache HBase.
* [Confluent Schema registry for Kafka](https://github.com/confluentinc/schema-registry)  - Schema Registry 为您的元数据提供服务层. 它提供了一个 RESTful 接口来存储和检索 Avro 模式.
* [Hortonworks Schema Registry](https://github.com/hortonworks/registry) - Schema Registry is a framework to build metadata repositories.

## Workflow, Lifecycle and Governance

* [Apache Oozie](http://oozie.apache.org) - 阿帕奇奥齐
* [Azkaban](http://azkaban.github.io/)
* [Apache Falcon](http://falcon.apache.org/) - 数据管理和处理平台
* [Apache NiFi](http://nifi.apache.org/) - 数据流系统
* [Apache AirFlow](https://github.com/apache/incubator-airflow) - Airflow 是一个工作流自动化和调度系统，可用于创作和管理数据管道
* [Luigi](http://luigi.readthedocs.org/en/latest/) - Python 包，可帮助您构建复杂的批处理作业管道

## Data Ingestion and Integration

* [Apache Flume](http://flume.apache.org) - 阿帕奇水槽
* [Suro](https://github.com/Netflix/suro) - Netflix 的分布式数据管道
* [Apache Sqoop](http://sqoop.apache.org) - Apache Sqoop
* [Apache Kafka](http://kafka.apache.org/) - 阿帕奇卡夫卡
* [Gobblin from LinkedIn](https://github.com/linkedin/gobblin) - Hadoop的通用数据摄取框架

## DSL

* [Apache Pig](http://pig.apache.org) - 阿帕奇猪
* [Apache DataFu](http://datafu.incubator.apache.org/) - 用于在 Hadoop 中处理大规模数据的库集合
* [vahara](https://github.com/thedatachef/varaha) - 使用 Apache Pig 进行机器学习和自然语言处理
* [packetpig](https://github.com/packetloop/packetpig) - 开源大数据安全分析
* [akela](https://github.com/mozilla-metrics/akela) - Mozilla 用于 Hadoop、HBase、Pig 等的实用程序库.
* [seqpig](http://seqpig.sourceforge.net/) - Hadoop 中大型测序数据集（例如：生物信息）的简单且可扩展的脚本 
* [Lipstick](https://github.com/Netflix/Lipstick) - 猪工作流可视化工具. [Introducing Lipstick on A(pache) Pig](http://techblog.netflix.com/2013/06/introducing-lipstick-on-apache-pig.html)
* [PigPen](https://github.com/Netflix/PigPen)  - PigPen 是 Clojure 的 map-reduce，或分布式 Clojure. 它编译为 Apache Pig，但您不需要对 Pig 有太多了解即可使用它.

## Libraries and Tools

* [Kite Software Development Kit](http://kitesdk.org/) - 一组库、工具、示例和文档
* [gohadoop](https://github.com/hortonworks/gohadoop) - Apache Hadoop YARN 的本地 go 客户端.
* [Hue](http://gethue.com/) - 使用 Apache Hadoop 分析数据的 Web 界面.
* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) - 一个基于网络的笔记本，可以进行交互式数据分析
* [Apache Thrift](http://thrift.apache.org/)
* [Apache Avro](http://avro.apache.org/) - Apache Avro 是一个数据序列化系统.
* [Elephant Bird](https://github.com/twitter/elephant-bird) - Twitter 收集的 LZO 和 Protocol Buffer 相关的 Hadoop、Pig、Hive 和 HBase 代码.
* [Spring for Apache Hadoop](http://projects.spring.io/spring-hadoop/)
* [hdfs - A native go client for HDFS](https://github.com/colinmarc/hdfs)
* [snakebite](https://pypi.python.org/pypi/snakebite/) - 一个纯 python HDFS 客户端
* [Apache Parquet](https://parquet.apache.org/) - Apache Parquet 是一种列式存储格式，适用于 Hadoop 生态系统中的任何项目，无论选择何种数据处理框架、数据模型或编程语言.
* [Apache Superset (incubating)](https://superset.incubator.apache.org/) - Apache Superset (incubating) 是一个现代化的企业级商业智能网络应用程序
* [Schema Registry UI](https://github.com/Landoop/schema-registry-ui) - 用于 Confluent Schema Registry 的 Web 工具，用于创建/查看/搜索/演变/查看历史记录并配置 Kafka 集群的 Avro 模式.

## Realtime Data Processing

* [Apache Storm](http://storm.apache.org/)
* [Apache Samza](http://samza.apache.org/)
* [Apache Spark](http://spark.apache.org/streaming/)
* [Apache Flink](https://flink.apache.org)  - Apache Flink 是一个用于高效、分布式、通用数据处理的平台. 它只支持一次流处理.
* [Apache Pulsar (incubating)](http://pulsar.incubator.apache.org/)  - Apache Pulsar (incubating) 是一个在商用硬件上运行的高度可扩展、低延迟的消息传递平台. 它提供了简单的主题发布-订阅语义，保证至少一次的消息传递，订阅者的自动游标管理和跨数据中心复制.
* [Apache Druid (incubating)](http://druid.incubator.apache.org/) - 高性能、面向列的分布式数据存储.

## Distributed Computing and Programming

* [Apache Spark](http://spark.apache.org/)
 * [Spark Packages](http://spark-packages.org/) - Apache Spark 包的社区索引
 * [SparkHub](https://sparkhub.databricks.com/) - Apache Spark 的社区站点
* [Apache Crunch](http://crunch.apache.org)
* [Cascading](http://www.cascading.org/) - Cascading 是经过验证的应用程序开发平台，用于在 Hadoop 上构建数据应用程序.
* [Apache Flink](http://flink.apache.org/) - Apache Flink 是一个用于高效、分布式、通用数据处理的平台.
* [Apache Apex (incubating)](http://apex.incubator.apache.org/) - 企业级统一流和批处理引擎.
* [Apache Livy (incubating)](https://livy.incubator.apache.org/)  - Apache Livy（孵化）是一种 Web 服务，它公开了一个 REST 接口，用于管理集群中长时间运行的 Apache Spark 上下文. 使用 Livy，可以在 Apache Spark 之上构建需要与许多 Spark 上下文进行细粒度交互的新应用程序.

## Packaging, Provisioning and Monitoring

* [Apache Bigtop](http://bigtop.apache.org/) - Apache Bigtop：Apache Hadoop 生态系统的打包和测试 
* [Apache Ambari](http://ambari.apache.org/) - 阿帕奇安巴里
* [Ganglia Monitoring System](http://ganglia.sourceforge.net/)
* [ankush](https://github.com/impetus-opensource/ankush) - 一种大数据集群管理工具，可创建和管理不同技术的集群.
* [Apache Zookeeper](http://zookeeper.apache.org/) - 阿帕奇动物园管理员
* [Apache Curator](http://curator.apache.org/) - ZooKeeper 客户端包装器和丰富的 ZooKeeper 框架
* [inviso](https://github.com/Netflix/inviso) - Inviso 是一个轻量级工具，提供搜索 Hadoop 作业、可视化性能和查看集群利用率的能力.
* [Logit.io](https://logit.io/) - 将日志从 Hadoop 发送到 Elasticsearch 以进行监控和警报.


## Search

* [ElasticSearch](https://www.elastic.co/)
* [Apache Solr](http://lucene.apache.org/solr/) - Apache Solr 是一个基于名为 Lucene 的 Java 库构建的开源搜索平台.
* [Banana](https://github.com/LucidWorks/banana) - Apache Solr 的 Kibana 端口

## Search Engine Framework

* [Apache Nutch](http://nutch.apache.org/) - Apache Nutch 是一个高度可扩展和可扩展的开源网络爬虫软件项目.

## Security

* [Apache Ranger](http://ranger.incubator.apache.org/) - Ranger 是一个框架，用于启用、监控和管理跨 Hadoop 平台的综合数据安全性.
* [Apache Sentry](https://sentry.incubator.apache.org/) - Hadoop的授权模块
* [Apache Knox Gateway](https://knox.apache.org/) - 用于与 Hadoop 集群交互的 REST API 网关.

## Benchmark

* [Big Data Benchmark](https://amplab.cs.berkeley.edu/benchmark/)
* [HiBench](https://github.com/intel-hadoop/HiBench)
* [YCSB](https://github.com/brianfrankcooper/YCSB)  - 雅虎！ 云服务基准 (YCSB) 是一个开源规范和程序套件，用于评估计算机程序的检索和维护能力. 它通常用于比较 NoSQL 数据库管理系统的相对性能.

## Machine learning and Big Data analytics

* [Apache Mahout](http://mahout.apache.org)
* [Oryx 2](https://github.com/OryxProject/oryx) - Spark、Kafka 上的 Lambda 架构，用于实时大规模机器学习
* [MLlib](https://spark.apache.org/mllib/) - MLlib 是 Apache Spark 的可扩展机器学习库.
* [R](http://www.r-project.org/) - R 是用于统计计算和图形的免费软件环境.
* [RHadoop](https://github.com/RevolutionAnalytics/RHadoop/wiki) 包括 RHDFS、RHBase、RMR2、plyrmr
* [Apache Lens](http://lens.apache.org/)
* [Apache SINGA (incubating)](https://singa.incubator.apache.org/) - SINGA 是一个通用的分布式深度学习平台，用于在大型数据集上训练大型深度学习模型
* [BigDL](https://bigdl-project.github.io/)  - BigDL 是 Apache Spark 的分布式深度学习库； 使用 BigDL，用户可以将他们的深度学习应用程序编写为标准的 Spark 程序，这些程序可以直接在现有的 Spark 或 Hadoop 集群上运行.
* [Apache Hivemall (incubating)](http://hivemall.incubator.apache.org/) - Apache Hivemall 是一个可扩展的机器学习库，可在 Apache Hive、Spark 和 Pig 上运行.

## Misc.

* Hive 插件
 * UDF
     * https://github.com/edwardcapriolo/hive_cassandra_udfs
     * https://github.com/livingsocial/HiveSwarm
     * https://github.com/ThinkBigAnalytics/Hive-Extensions-from-Think-Big-Analytics
     * https://github.com/twitter/elephant-bird - 推特
     * https://github.com/lovelysystems/ls-hive
     * https://github.com/klout/brickhouse
 * 存储处理器
     * https://github.com/dvasilen/Hive-Cassandra
     * https://github.com/yc-huang/Hive-mongo
     * https://github.com/balshor/gdata-storagehandler
     * https://github.com/chimpler/hive-solr
     * https://github.com/bfemiano/accumulo-hive-storage-manager
 * 库和工具
     * https://github.com/forward3d/rbhive
     * https://github.com/synctree/activerecord-hive-adapter
     * https://github.com/hrp/sequel-hive-adapter
     * https://github.com/forward/node-hive
     * https://github.com/recruitcojp/WebHive
     * [shib](https://github.com/tagomoris/shib) - 查询引擎的 WebUI：Hive 和 Presto
     * https://github.com/dmorel/Thrift-API-HiveClient2 (Perl - HiveServer2)
     * [PyHive](https://github.com/dropbox/PyHive) - Hive 和 Presto 的 Python 接口
     * https://github.com/recruitcojp/OdbcHive
     * [HiveRunner](https://github.com/klarna/HiveRunner) - 基于 JUnit4 的 hadoop hive 查询的开源单元测试框架
     * [Beetest](https://github.com/kawaa/Beetest) - 一个超级简单的实用程序，用于为非 Java 开发人员在本地测试 Apache Hive 脚本.
     * [Hive_test](https://github.com/edwardcapriolo/hive_test)- hive 和 hive-service 的单元测试框架
* 水槽插件
  * [Flume MongoDB Sink](https://github.com/leonlee/flume-ng-mongodb-sink)
  * [Flume RabbitMQ source and sink](https://github.com/jcustenborder/flume-ng-rabbitmq)
  * [Flume UDP Source](https://github.com/whitepages/flume-udp-source)
  * [.Net FlumeNG Clients](https://github.com/marksl/DotNetFlumeNG.Clients)

## Resources
Various resources, such as books, websites and articles.

## Websites
*有用的网站和文章*

* [Hadoop Weekly](http://www.hadoopweekly.com/)
* [The Hadoop Ecosystem Table](http://hadoopecosystemtable.github.io/)
* [Hadoop illuminated](http://hadoopilluminated.com/) - 开源 Hadoop 书籍
* [AWS BigData Blog](http://blogs.aws.amazon.com/bigdata/)
* [Hadoop360](http://www.hadoop360.com/)
* [How to monitor Hadoop metrics](https://www.datadoghq.com/blog/monitor-hadoop-metrics/)

## Presentations

* [Apache Hadoop In Theory And Practice](http://www.slideshare.net/AdamKawa/hadoop-intheoryandpractice)
* [Hadoop Operations at LinkedIn](http://www.slideshare.net/allenwittenauer/2013-hadoopsummitemea)
* [Hadoop Performance at LinkedIn](http://www.slideshare.net/allenwittenauer/2012-lihadoopperf)
* [Docker based Hadoop provisioning](http://www.slideshare.net/JanosMatyas/docker-based-hadoop-provisioning)

## Books

* [Hadoop: The Definitive Guide](http://www.amazon.com/gp/product/1449311520/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1449311520&linkCode=as2&tag=matratsblo-20)
* [Hadoop Operations](http://www.amazon.com/gp/product/1449327052/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1449327052&linkCode=as2&tag=matratsblo-20)
* [Apache Hadoop Yarn](http://www.amazon.com/dp/0321934504?tag=matratsblo-20)
* [HBase: The Definitive Guide](http://shop.oreilly.com/product/0636920014348.do)
* [Programming Pig](http://shop.oreilly.com/product/0636920018087.do)
* [Programming Hive](http://shop.oreilly.com/product/0636920023555.do)
* [Hadoop in Practice, Second Edition](http://www.manning.com/holmes2/)
* [Hadoop in Action, Second Edition](http://www.manning.com/lam2/)

## Hadoop and Big Data Events
* [ApacheCon](http://www.apachecon.com/)
* [Strata + Hadoop World](http://conferences.oreilly.com/strata)
* [DataWorks Summit](https://dataworkssummit.com/)
* [Spark Summit](https://databricks.com/sparkaisummit)

## Other Awesome Lists
其他令人惊叹的列表可以在 [awesome-awesomeness](https://github.com/bay和in/awesome-awesomeness) 和 [awesome](https://github.com/sindresorhus/awesome) 列表.
