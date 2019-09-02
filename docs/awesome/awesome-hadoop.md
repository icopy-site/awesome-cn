<div class="github-widget" data-repo="youngwookim/awesome-hadoop"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Hadoop [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 精选的Hadoop和Hadoop生态系统资源列表.  灵感来自 [Awesome PHP](https://github.com/ziadoz/awesome-php), [Awesome Python](https://github.com/vinta/awesome-python) 和 [Awesome Sysadmin](https://github.com/kahun/awesome-sysadmin)


## Hadoop

* [Apache Hadoop](http://hadoop.apache.org/) -  Apache Hadoop
* [Apache Hadoop Ozone](http://hadoop.apache.org/ozone/) -  Apache Hadoop的对象存储
* [Apache Tez](http://tez.apache.org/) -  Hadoop中基于YARN的数据处理应用程序框架
* [SpatialHadoop](http://spatialhadoop.cs.umn.edu/) -  SpatialHadoop是Apache Hadoop的MapReduce扩展，专门用于处理空间数据. 
* [GIS Tools for Hadoop](http://esri.github.io/gis-tools-for-hadoop/) -  Hadoop框架的大数据空间分析
* [Elasticsearch Hadoop](https://github.com/elastic/elasticsearch-hadoop)   -  Elasticsearch实时搜索和分析本地与Hadoop集成.  支持Map / Reduce，Cascading，Apache Hive和Apache Pig.
* [hadoopy](https://github.com/bwhite/hadoopy) - 用Cython编写的Python MapReduce库. 
* [mrjob](https://github.com/Yelp/mrjob/) -  mrjob是一个Python 2.5+包，可以帮助您编写和运行Hadoop Streaming作业.
* [pydoop](http://pydoop.sourceforge.net/) -  Pydoop是一个为Hadoop提供Python API的软件包.
* [hdfs-du](https://github.com/twitter/hdfs-du) -  HDFS-DU是Hadoop分布式文件系统的交互式可视化. 
* [White Elephant](https://github.com/linkedin/white-elephant) -  Hadoop日志聚合器和仪表板
* [Genie](https://github.com/Netflix/genie) -  Genie提供REST-ful API来运行Hadoop，Hive和Pig作业，以及管理多个Hadoop资源并在它们之间执行作业提交.
* [Apache Kylin](http://kylin.incubator.apache.org/) -  Apache Kylin是来自eBay Inc.的开源分布式分析引擎，它在Hadoop上提供SQL接口和多维分析（OLAP），支持极大的数据集
* [Crunch](https://github.com/jondot/crunch) - 基于Go的工具包，用于ETL和Hadoop上的特征提取
* [Apache Ignite](http://ignite.apache.org/) - 分布式内存平台

## YARN

* [Apache Slider](http://slider.incubator.apache.org/) -  Apache Slider是Apache Software Foundation的一个孵化项目，其目标是使现有应用程序可以轻松部署到YARN集群中.
* [Apache Twill](http://twill.incubator.apache.org/) -  Apache Twill是ApacheHadoop®YARN的抽象，它降低了开发分布式应用程序的复杂性，使开发人员能够更专注于他们的应用程序逻辑.
* [mpich2-yarn](https://github.com/alibaba/mpich2-yarn) - 在纱线上运行MPICH2

## NoSQL
*下一代数据库主要解决一些问题：非关系型，分布式，开源和水平可扩展.*

* [Apache HBase](http://hbase.apache.org) -  Apache HBase
* [Apache Phoenix](http://phoenix.apache.org/) - 支持二级索引的HBase上的SQL皮肤
* [happybase](https://github.com/wbolster/happybase) - 与Apache HBase交互的开发人员友好的Python库.
* [Hannibal](https://github.com/sentric/hannibal) -  Hannibal是帮助监视和维护配置为手动拆分的HBase-Clusters的工具.
* [Haeinsa](https://github.com/VCNC/haeinsa) -  Haeinsa是HBase的可线性扩展的多行，多表事务库
* [hindex](https://github.com/Huawei-Hadoop/hindex) -  HBase的二级索引
* [Apache Accumulo](https://accumulo.apache.org/) -  Apache Accumulo™分类，分布式键/值存储是一个强大，可扩展，高性能的数据存储和检索系统.
* [OpenTSDB](http://opentsdb.net/) - 可扩展时间序列数据库
* [Apache Cassandra](http://cassandra.apache.org/)

## SQL on Hadoop
* Hadoop上的SQL *

* [Apache Hive](http://hive.apache.org) -  Apache Hive数据仓库软件有助于使用SQL读取，编写和管理驻留在分布式存储中的大型数据集
* [Apache Phoenix](http://phoenix.apache.org) HBase上的SQL皮肤支持二级索引
* [Apache HAWQ (incubating)](http://hawq.incubator.apache.org/) -  Apache HAWQ是一个Hadoop本机SQL查询引擎，它结合了MPP数据库的关键技术优势和Hadoop的可扩展性和便利性
* [Lingual](http://www.cascading.org/projects/lingual/) - 用于级联的SQL接口（MR / Tez作业生成器）
* [Apache Impala](https://impala.apache.org/)   -  Apache Impala是一个开源大规模并行处理（MPP）SQL查询引擎，用于存储在运行Apache Hadoop的计算机集群中的数据.  Impala被描述为Google F1的开源版本，它激发了它在2012年的发展.
* [Presto](https://prestodb.io/)   - 用于大数据的分布式SQL查询引擎.  由Facebook开源.
* [Apache Tajo](http://tajo.apache.org/) -  Apache Hadoop的数据仓库系统
* [Apache Drill](https://drill.apache.org/) - 无架构的SQL查询引擎
* [Apache Trafodion](http://trafodion.apache.org/)

## Data Management

* [Apache Calcite](http://calcite.apache.org/) - 动态数据管理框架
* [Apache Atlas](http://atlas.incubator.apache.org/) - 元数据标记和谱系捕获，支持复杂的业务数据分类
* [Apache Kudu](https://kudu.apache.org/) -  Kudu提供快速插入/更新和高效柱状扫描的组合，可在单个存储层上实现多个实时分析工作负载，从而补充HDFS和Apache HBase.
* [Confluent Schema registry for Kafka](https://github.com/confluentinc/schema-registry)   -  Schema Registry为您的元数据提供服务层.  它提供了一个RESTful接口，用于存储和检索Avro架构.
* [Hortonworks Schema Registry](https://github.com/hortonworks/registry) - Schema Registry is a framework to build metadata repositories.

## Workflow, Lifecycle and Governance

* [Apache Oozie](http://oozie.apache.org) -  Apache Oozie
* [Azkaban](http://azkaban.github.io/)
* [Apache Falcon](http://falcon.apache.org/) - 数据管理和处理平台
* [Apache NiFi](http://nifi.apache.org/) - 数据流系统
* [Apache AirFlow](https://github.com/apache/incubator-airflow) -  Airflow是一个工作流程自动化和调度系统，可用于创作和管理数据管道
* [Luigi](http://luigi.readthedocs.org/en/latest/) -  Python包，可帮助您构建批处理作业的复杂管道

## Data Ingestion and Integration

* [Apache Flume](http://flume.apache.org) - 阿帕奇水槽
* [Suro](https://github.com/Netflix/suro) -  Netflix的分布式数据管道
* [Apache Sqoop](http://sqoop.apache.org) -  Apache Sqoop
* [Apache Kafka](http://kafka.apache.org/) - 阿帕奇卡夫卡
* [Gobblin from LinkedIn](https://github.com/linkedin/gobblin) -  Hadoop的通用数据提取框架

## DSL

* [Apache Pig](http://pig.apache.org) - 阿帕奇猪
* [Apache DataFu](http://datafu.incubator.apache.org/) - 用于在Hadoop中处理大规模数据的库集合
* [vahara](https://github.com/thedatachef/varaha) - 使用Apache Pig进行机器学习和自然语言处理
* [packetpig](https://github.com/packetloop/packetpig) - 开源大数据安全分析
* [akela](https://github.com/mozilla-metrics/akela) -  Mozilla的Hadoop，HBase，Pig等实用程序库.
* [seqpig](http://seqpig.sourceforge.net/) -  Hadoop中针对大型测序数据集（例如，生物信息）的简单且可扩展的脚本 
* [Lipstick](https://github.com/Netflix/Lipstick) -  Pig工作流可视化工具. [Introducing Lipstick on A(pache) Pig](http://techblog.netflix.com/2013/06/introducing-lipstick-on-apache-pig.html)
* [PigPen](https://github.com/Netflix/PigPen)   -  PigPen是Clojure的map-reduce，或者是分布式Clojure.  它编译为Apache Pig，但你不需要了解Pig使用它.

## Libraries and Tools

* [Kite Software Development Kit](http://kitesdk.org/) - 一组库，工具，示例和文档
* [gohadoop](https://github.com/hortonworks/gohadoop) -  Native Hadoop YARN的客户端.
* [Hue](http://gethue.com/) - 用于使用Apache Hadoop分析数据的Web界面.
* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) - 基于Web的笔记本电脑，支持交互式数据分析
* [Apache Thrift](http://thrift.apache.org/)
* [Apache Avro](http://avro.apache.org/) -  Apache Avro是一个数据序列化系统.
* [Elephant Bird](https://github.com/twitter/elephant-bird) -  Twitter收集的LZO和Protocol Buffer相关的Hadoop，Pig，Hive和HBase代码.
* [Spring for Apache Hadoop](http://projects.spring.io/spring-hadoop/)
* [hdfs - A native go client for HDFS](https://github.com/colinmarc/hdfs)
* [snakebite](https://pypi.python.org/pypi/snakebite/) - 一个纯python HDFS客户端
* [Apache Parquet](https://parquet.apache.org/) -  Apache Parquet是一种柱状存储格式，可用于Hadoop生态系统中的任何项目，无论选择何种数据处理框架，数据模型或编程语言.
* [Apache Superset (incubating)](https://superset.incubator.apache.org/) -  Apache Superset（孵化）是一个现代化的企业级商业智能Web应用程序
* [Schema Registry UI](https://github.com/Landoop/schema-registry-ui) -  Confluent Schema Registry的Web工具，用于创建/查看/搜索/演化/查看历史记录并配置Kafka群集的Avro架构.

## Realtime Data Processing

* [Apache Storm](http://storm.apache.org/)
* [Apache Samza](http://samza.apache.org/)
* [Apache Spark](http://spark.apache.org/streaming/)
* [Apache Flink](https://flink.apache.org/features.html#unified-stream-amp-batch-processing)   -  Apache Flink是一个高效，分布式，通用数据处理平台.  它只支持一次流处理.
* [Apache Pulsar (incubating)](http://pulsar.incubator.apache.org/)   -  Apache Pulsar（孵化）是一种在商用硬件上运行的高度可扩展，低延迟的消息传递平台.  它提供了关于主题的简单pub-sub语义，保证至少一次传递消息，为订阅者提供自动游标管理以及跨数据中心复制.
* [Apache Druid (incubating)](http://druid.incubator.apache.org/) - 高性能，面向列的分布式数据存储.

## Distributed Computing and Programming

* [Apache Spark](http://spark.apache.org/)
 * [Spark Packages](http://spark-packages.org/) -  Apache Spark的社区包索引
 * [SparkHub](https://sparkhub.databricks.com/) -  Apache Spark的社区站点
* [Apache Crunch](http://crunch.apache.org)
* [Cascading](http://www.cascading.org/) -  Cascading是用于在Hadoop上构建数据应用程序的成熟应用程序开发平台.
* [Apache Flink](http://flink.apache.org/) -  Apache Flink是一个高效，分布式，通用数据处理平台.
* [Apache Apex (incubating)](http://apex.incubator.apache.org/) - 企业级统一流和批处理引擎.
* [Apache Livy (incubating)](https://livy.incubator.apache.org/)   -  Apache Livy（孵化）是一种Web服务，它公开了一个REST接口，用于管理集群中长时间运行的Apache Spark上下文.  使用Livy，可以在Apache Spark之上构建新的应用程序，这需要与许多Spark上下文进行细粒度的交互.

## Packaging, Provisioning and Monitoring

* [Apache Bigtop](http://bigtop.apache.org/) -  Apache Bigtop：Apache Hadoop生态系统的打包和测试 
* [Apache Ambari](http://ambari.apache.org/) -  Apache Ambari
* [Ganglia Monitoring System](http://ganglia.sourceforge.net/)
* [ankush](https://github.com/impetus-opensource/ankush) - 一个大数据集群管理工具，可以创建和管理不同技术的集群.
* [Apache Zookeeper](http://zookeeper.apache.org/) -  Apache Zookeeper
* [Apache Curator](http://curator.apache.org/) -  ZooKeeper客户端包装器和丰富的ZooKeeper框架
* [inviso](https://github.com/Netflix/inviso) -  Inviso是一个轻量级工具，可以搜索Hadoop作业，可视化性能以及查看群集利用率.

## Search

* [ElasticSearch](https://www.elastic.co/)
* [Apache Solr](http://lucene.apache.org/solr/) -  Apache Solr是一个基于名为Lucene的Java库构建的开源搜索平台.
* [Banana](https://github.com/LucidWorks/banana) -  Apache Solr的Kibana端口

## Search Engine Framework

* [Apache Nutch](http://nutch.apache.org/) -  Apache Nutch是一个高度可扩展和可扩展的开源Web爬虫软件项目.

## Security

* [Apache Ranger](http://ranger.incubator.apache.org/) -  Ranger是一个框架，用于在Hadoop平台上启用，监控和管理全面的数据安全性.
* [Apache Sentry](https://sentry.incubator.apache.org/) -  Hadoop的授权模块
* [Apache Knox Gateway](https://knox.apache.org/) - 用于与Hadoop集群交互的REST API网关.
* [Project Rhino](https://github.com/intel-hadoop/project-rhino) - 英特尔的开源工作，旨在增强Hadoop生态系统的现有数据保护功能，以解决安全性和合规性挑战，并将代码贡献给Apache.

## Benchmark

* [Big Data Benchmark](https://amplab.cs.berkeley.edu/benchmark/)
* [HiBench](https://github.com/intel-hadoop/HiBench)
* [Big-Bench](https://github.com/intel-hadoop/Big-Data-Benchmark-for-Big-Bench)
* [YCSB](https://github.com/brianfrankcooper/YCSB)   - 雅虎！  Cloud Serving Benchmark（YCSB）是一个开源规范和程序套件，用于评估计算机程序的检索和维护功能.  它通常用于比较NoSQL数据库管理系统的相对性能.

## Machine learning and Big Data analytics

* [Apache Mahout](http://mahout.apache.org)
* [Oryx 2](https://github.com/OryxProject/oryx) -  Spark，Kafka上的Lambda架构，用于实时大规模机器学习
* [MLlib](https://spark.apache.org/mllib/) -  MLlib是Apache Spark的可扩展机器学习库.
* [R](http://www.r-project.org/) -  R是用于统计计算和图形的免费软件环境.
* [RHadoop](https://github.com/RevolutionAnalytics/RHadoop/wiki) 包括RHDFS，RHBase，RMR2，plyrmr
* [Apache Lens](http://lens.apache.org/)
* [Apache SINGA (incubating)](https://singa.incubator.apache.org/) -  SINGA是一个通用的分布式深度学习平台，用于在大型数据集上训练大型深度学习模型
* [BigDL](https://bigdl-project.github.io/)   -  BigDL是Apache Spark的分布式深度学习库;  使用BigDL，用户可以将他们的深度学习应用程序编写为标准的Spark程序，它可以直接在现有的Spark或Hadoop集群上运行.
* [Apache Hivemall (incubating)](http://hivemall.incubator.apache.org/) -  Apache Hivemall是一个可扩展的机器学习库，可在Apache Hive，Spark和Pig上运行.

## Misc.

* Hive插件
 * UDF
     * https://github.com/edwardcapriolo/hive_cassandra_udfs
     * https://github.com/livingsocial/HiveSwarm
     * https://github.com/ThinkBigAnalytics/Hive-Extensions-from-Think-Big-Analytics
     * https://github.com/twitter/elephant-bird  -  Twitter
     * https://github.com/lovelysystems/ls-hive
     * https://github.com/klout/brickhouse
 *存储处理程序
     * https://github.com/dvasilen/Hive-Cassandra
     * https://github.com/yc-huang/Hive-mongo
     * https://github.com/balshor/gdata-storagehandler
     * https://bitbucket.org/rodrigopr/redisstoragehandler
     * https://github.com/chimpler/hive-solr
     * https://github.com/bfemiano/accumulo-hive-storage-manager
 *图书馆和工具
     * https://github.com/forward3d/rbhive
     * https://github.com/synctree/activerecord-hive-adapter
     * https://github.com/hrp/sequel-hive-adapter
     * https://github.com/forward/node-hive
     * https://github.com/recruitcojp/WebHive
     * [shib](https://github.com/tagomoris/shib) - 用于查询引擎的WebUI：Hive和Presto
     * https://github.com/dmorel/Thrift-API-HiveClient2(Perl  -  HiveServer2）
     * [PyHive](https://github.com/dropbox/PyHive) -  Hive和Presto的Python接口
     * https://github.com/recruitcojp/OdbcHive
     * [Hive-Sharp](https://bitbucket.org/vadim/hive-sharp)
     * [HiveRunner](https://github.com/klarna/HiveRunner) - 基于JUnit4的hadoop配置单元查询的开源单元测试框架
     * [Beetest](https://github.com/kawaa/Beetest) - 一个非常简单的实用程序，用于在本地为非Java开发人员测试Apache Hive脚本.
     * [Hive_test](https://github.com/edwardcapriolo/hive_test)- 蜂巢和蜂巢服务的单元测试框架
* Flume插件
  * [Flume MongoDB Sink](https://github.com/leonlee/flume-ng-mongodb-sink)
  * [Flume RabbitMQ source and sink](https://github.com/jcustenborder/flume-ng-rabbitmq)
  * [Flume UDP Source](https://github.com/whitepages/flume-udp-source)
  * [.Net FlumeNG Clients](https://github.com/marksl/DotNetFlumeNG.Clients)

## Resources
各种资源，如书籍，网站和文章.

## Websites
*有用的网站和文章*

* [Hadoop Weekly](http://www.hadoopweekly.com/)
* [The Hadoop Ecosystem Table](http://hadoopecosystemtable.github.io/)
* [Apache Hadoop YARN: Yet Another Resource Negotiator](http://www.socc2013.org/home/program/a5-vavilapalli.pdf)
* [Hadoop illuminated](http://hadoopilluminated.com/) - 开源Hadoop书
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
其他惊人的令人敬畏的名单可以在 [awesome-awesomeness](https://github.com/bay和in/awesome-awesomeness) 和 [awesome](https://github.com/sindresorhus/awesome) 名单.
