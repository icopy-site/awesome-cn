<div class="github-widget" data-repo="rayokota/awesome-hbase"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome HBase [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cdn.rawgit.com/rayokota/awesome-hbase/c197f415/hbase_logo_with_orca-2.png" align="right" width="150">](http://hbase.apache.org/)

很棒的 HBase 项目和资源的精选列表.

[HBase](http://hbase.apache.org) 是一个分布式、可扩展的大数据存储.




    
## Projects

### Clients

* [asynchbase](https://github.com/OpenTSDB/asynchbase) - 完全异步、非阻塞的 HBase 客户端.
* [gohbase](https://github.com/tsuna/gohbase) - HBase 的纯 Go 客户端.
* [happybase](https://github.com/wbolster/happybase) - HBase 的 Python 客户端.


### Cloud

* [Amazon EMR](https://aws.amazon.com/emr/) - Amazon 在 AWS 上的 Hadoop/HBase 产品.
* [Azure HDInsight](https://azure.microsoft.com/en-us/services/hdinsight/) - Microsoft 在 Azure 上的 Hadoop/HBase 产品.
* [Cloudera Director](https://www.cloudera.com/products/product-components/cloudera-director.html) - 在 AWS、Azure 或 Google Cloud 上运行 Hadoop/HBase 集群.
* [Google Cloud Bigtable](https://cloud.google.com/bigtable/) - 可通过 HBase 客户端 API 访问的高性能 NoSQL 数据库服务.
* [Hortonworks Cloudbreak](https://hortonworks.com/open-source/cloudbreak/) - 在 AWS、Azure、Google Cloud 或 OpenStack 上配置 Hadoop/HBase 集群.

### Frameworks

#### Datasets

* [Kite](http://kitesdk.org) - Hadoop/HBase 的高级数据层.

#### Document

* [HDocDB](https://github.com/rayokota/hdocdb) - HBase 作为 JSON 文档数据库.

#### Entity/JPA

* [DataNucleus](http://www.datanucleus.org) - 支持 HBase 的 JPA 持久层.
* [Gora](http://gora.apache.org) - 支持 HBase 的大数据持久性库.
* [HBase ORM](https://github.com/flipkart-incubator/hbase-orm) - 生产级 HBase ORM 库.
* [HEntityDB](https://github.com/rayokota/hentitydb) - HBase 作为实体数据库.
* [Kundera](https://github.com/impetus-opensource/Kundera) - 支持 HBase 的 JPA 客户端.

#### Geospatial

* [GeoMesa](http://www.geomesa.org/) - 时空数据库，支持 Accumulo、HBase、Cassandra 和 Kafka.

#### Graph
* [Gradoop](https://github.com/dbs-leipzig/gradoop) - 基于 Flink 和 HBase 的可扩展图形分析研究框架.
* [HGraphDB](https://github.com/rayokota/hgraphdb) - HBase 作为 TinkerPop 图形数据库.
* [HugeGraph](https://github.com/apache/incubator-hugegraph) - 支持超过 10+ 亿数据、高性能和可扩展性的图形数据库.
* [JanusGraph](http://janusgraph.org/) - 可扩展的图形数据库，支持 Cassandra、HBase、Google Cloud Bigtable 和 BerkeleyDB.
* [NebulaGraph](https://github.com/vesoft-inc/nebula) - 一个高性能的分布式图数据库.
* [S2Graph](http://s2graph.incubator.apache.org) - 基于 HBase 构建的高性能分布式图数据库.

#### SQL/OLAP

* [AntsDB](http://antsdb.com/) - AntsDB 是用于 HBase 的低延迟、高并发、符合 MySQL 的 SQL 层.
* [EsgynDB](https://esgyn.com/) - 基于 Trafodian 在 Hadoop 之上提供 ACID 事务和 BI 分析的商业 SQL 引擎.
* [Kylin](http://kylin.apache.org) - 用于将数据存储在 HBase 中的大数据的极限 OLAP 引擎.
* [LeanXScale](http://www.leanxcale.com) - 基于 Hadoop/HBase 构建的商业全 ACID 全 SQL 产品.
* [Phoenix](https://phoenix.apache.org) - HBase 之上的 SQL 层.
* [Splice Machine](https://www.splicemachine.com) - 基于 HBase 构建的商业 RDBMS.
* [Trafodian](http://trafodion.apache.org) - 事务性 SQL-on-Hadoop/HBase.

#### Time Series

* [Axibase](http://axibase.com/products/axibase-time-series-database/) - 基于 HBase 构建的分布式时间序列数据库.
* [OpenTSDB](http://opentsdb.net) - 基于 HBase 构建的可扩展时间序列数据库.
* [Warp 10](http://www.warp10.io) - 传感器数据的时间序列数据库.

### Infrastructure

#### Secondary Indices

* [hindex](https://github.com/Huawei-Hadoop/hindex) - HBase 的二级索引.

#### Transactions

* [Haeinsa](https://github.com/VCNC/haeinsa) - HBase 的多行/多表事务库.
* [HBase-QoD](https://github.com/algarecu/hbase-0.94.8-qod) - HBase 细粒度事务间 DC 复制的矢量字段一致性.
* [Omid](https://github.com/apache/incubator-omid) - 对 HBase 的事务性支持.
* [Tephra](http://tephra.incubator.apache.org) - 基于 HBase 的全局一致事务.
* [Themis](https://github.com/XiaoMi/themis) - 基于 Google 的 Percolator 的 HBase 上的跨行/跨表事务.

### Integrations

* [Apex](https://github.com/apache/apex-malhar/tree/master/contrib/src/test/java/org/apache/apex/malhar/contrib/hbase) - Apex-HBase 连接器.
* [Beam](https://github.com/apache/beam/tree/master/sdks/java/io/hbase) - Beam HBase 集成.
* [Camel](http://camel.apache.org/hbase.html) - Camel HBase 组件.
* [Cascading](https://github.com/Cascading/cascading.hbase) - 用于级联的 HBase 适配器.
* [Cascalog](https://github.com/sorenmacbeth/hbase-cascalog) - 在 Cascalog 中使用的 Cascading.HBase 包装器.
* [Crunch](https://github.com/apache/crunch/tree/master/crunch-hbase) - 用于 Crunch 的 HBase 适配器.
* [Drill](https://drill.apache.org/docs/querying-hbase/) - Drill 的 HBase 存储插件.
* [Elasticsearch](https://github.com/mallocator/Elasticsearch-HBase-River) - HBase 的 Elasticsearch 导入河.
* [Flink](https://github.com/apache/flink/tree/master/flink-connectors/flink-connector-hbase-2.2) - Flink HBase 连接器.
* [Gearpump](https://github.com/apache/incubator-gearpump/tree/master/external/hbase) - HBase 的齿轮泵集成.
* [Giraph](https://github.com/apache/giraph/tree/trunk/giraph-hbase) - HBase 的 Giraph 输入和输出格式.
* [HAWQ](https://hawq.apache.org/docs/userguide/2.3.0.0-incubating/pxf/HBasePXF.html) - HBase 上的 HAWQ PXF 外部表.
* [Hive](https://cwiki.apache.org/confluence/display/Hive/HBaseIntegration) - Hive HBase 集成.
* [Impala](https://www.cloudera.com/documentation/enterprise/latest/topics/impala_hbase.html) - Impala 支持查询 HBase 表.
* [Kafka](https://github.com/apache/hbase-connectors/tree/master/kafka) - HBase Kafka 代理.
* [Pig](https://github.com/apache/pig/tree/trunk/src/org/apache/pig/backend/hadoop/hbase) - 猪 HBase 集成.
* [Presto](https://github.com/analysys/presto-hbase-connector) - Presto-HBase 连接器.
* [Pulsar](http://pulsar.apache.org/docs/en/io-hbase/) - Pulsar 的 HBase 连接器.
* [Ranger](https://cwiki.apache.org/confluence/display/RANGER/HBase+Plugin) - Apache Ranger 的 HBase 插件.
* [Spark](https://github.com/hortonworks-spark/shc) - Spark-HBase 连接器.
* [Spring for Apache Hadoop](https://projects.spring.io/spring-hadoop/) - Spring-Hadoop 集成，包括 HBase 支持.
* [Storm](https://github.com/apache/storm/tree/master/external/storm-hbase) - HBase 的 Storm/Trident 集成.
* [Tajo](https://tajo.apache.org/docs/current/hbase_integration.html) - Tajo 与 HBase 的集成.
* [Zeppelin](https://zeppelin.apache.org/docs/0.6.2/interpreter/hbase.html) - Apache Zeppelin 的 HBase shell 解释器.

### Tools

* [Ambari](https://ambari.apache.org) - 用于配置、管理和监控 Hadoop/HBase 集群的软件.
* [Cloudera Manager](https://www.cloudera.com/products/product-components/cloudera-manager.html) - 用于在生产中管理 Hadoop/HBase 的工具.
* [DbSchema](http://www.dbschema.com/index.html) - 面向图表的数据库设计器，支持 HBase.
* [Hannibal](https://github.com/sentric/hannibal) - 监控和维护 HBase 集群的工具.
* [h-rider](https://github.com/NiceSystems/hrider) - 用于在 HBase 中查看和操作数据的 GUI.
* [Hue](http://gethue.com) - 包含 HBase 浏览器的智能分析工作台.
* [Sematext SPM](http://sematext.com/spm) - 工具 [monitoring HBase](http://sematext.com/spm/integrations/hbase-monitoring), HDFS 等

### Miscellaneous

* [HubSpot HBase support](https://github.com/HubSpot/hbase-support) - HubSpot 的 HBase 配置和工具，包括 Hystrix 集成和协处理器.

## Resources

### Books

* [HBase in Action](https://www.manning.com/books/hbase-in-action) - 以体验为导向的指南，向您展示如何使用 HBase.
* [HBase: The Definitive Guide](http://shop.oreilly.com/product/0636920014348.do) - HBase 综合指南.
* [Architecting HBase Applications](http://shop.oreilly.com/product/0636920035688.do) - 包括 HBase 原则、集群指南和深入的案例研究.
* [HBase Administration Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/hbase-administration-cookbook) - 如何掌握 HBase 配置和管理.
* [HBase Essentials](https://www.packtpub.com/big-data-and-business-intelligence/hbase-essentials) - 使用 HBase 的实用指南.
* [HBase Design Patterns](https://www.packtpub.com/big-data-and-business-intelligence/hbase-design-patterns) - 使用 HBase 开发可扩展应用程序的成功模式.
* [Learning HBase](https://www.packtpub.com/big-data-and-business-intelligence/learning-hbase) - 学习 HBase 管理和开发的基础知识.
* [HBase High Performance Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/hbase-high-performance-cookbook) - 令人兴奋的项目，教您如何使用 HBase.
* [Apache HBase Primer](http://www.apress.com/us/book/9781484224236) - HBase 要点的紧凑指南.
* [Pro Apache Phoenix](http://www.apress.com/us/book/9781484223697) - 使用 Phoenix 的基本和最佳实践.

### Papers

* [Apache Hadoop Goes Realtime at Facebook](https://pdfs.semanticscholar.org/865a/215390cd49af9e4941e03107120e631dcaa0.pdf) - Facebook 如何将 HBase 部署到生产环境.

### Community

* [Blog](https://blogs.apache.org/hbase/)
* [Mailing Lists](http://hbase.apache.org/mail-lists.html)
* [Reddit](https://www.reddit.com/r/hbase/)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/hbase)
* [Twitter](https://twitter.com/HBase)

## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/publicdomain.svg"
     样式=“边框样式：无；”  alt=&quot;公共域标记&quot; /&gt;
</a>
