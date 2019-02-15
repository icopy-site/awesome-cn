## Awesome HBase [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cdn.rawgit.com/rayokota/awesome-hbase/c197f415/hbase_logo_with_orca-2.png" align="right" width="150">](http://hbase.apache.org/)

精选的HBase项目和资源的精选列表.

[HBase](http://hbase.apache.org) 是一个分布式，可扩展的大数据存储.

## Contents

- [Projects](#projects)
    - [Clients](#clients)
    - [Cloud](#cloud)
    - [Frameworks](#frameworks)
        - [Datasets](#datasets)
        - [Document](#document)
        - [Entity/JPA](#entityjpa)
        - [Geospatial](#geospatial)
        - [Graph](#graph)
        - [SQL/OLAP](#sqlolap)
        - [Time Series](#time-series)
    - [Infrastructure](#infrastructure)
        - [Secondary Indices](#secondary-indices)
        - [Transactions](#transactions)
    - [Integrations](#integrations)
    - [Tools](#tools)
    - [Miscellaneous](#miscellaneous)

- [Resources](#resources)
    - [Books](#books)
    - [Papers](#papers)
    - [Community](#community)

    
## Projects

### Clients

* [asynchbase](https://github.com/OpenTSDB/asynchbase) - 完全异步，无阻塞的HBase客户端.
* [gohbase](https://github.com/tsuna/gohbase) -  HBase的Pure Go客户端.
* [happybase](https://github.com/wbolster/happybase) -  HBase的Python客户端.


### Cloud

* [Amazon EMR](https://aws.amazon.com/emr/) -  AWS上的亚马逊Hadoop / HBase产品.
* [Azure HDInsight](https://azure.microsoft.com/en-us/services/hdinsight/) -  Azure上的Microsoft Hadoop / HBase产品.
* [Cloudera Director](https://www.cloudera.com/products/product-components/cloudera-director.html) - 在AWS，Azure或Google Cloud上运行Hadoop / HBase集群.
* [Google Cloud Bigtable](https://cloud.google.com/bigtable/) - 可通过HBase客户端API访问的高性能NoSQL数据库服务.
* [Hortonworks Cloudbreak](https://hortonworks.com/open-source/cloudbreak/) - 在AWS，Azure，Google Cloud或OpenStack上提供Hadoop / HBase群集.

### Frameworks

#### Datasets

* [Kite](http://kitesdk.org) -  Hadoop / HBase的高级数据层.

#### Document

* [HDocDB](https://github.com/rayokota/hdocdb) -  HBase作为JSON文档数据库.

#### Entity/JPA

* [DataNucleus](http://www.datanucleus.org) - 支持HBase的JPA持久层.
* [Gora](http://gora.apache.org) - 支持HBase的大数据持久性库.
* [HEntityDB](https://github.com/rayokota/hentitydb) -  HBase作为实体数据库.
* [Kundera](https://github.com/impetus-opensource/Kundera) - 支持HBase的JPA客户端.

#### Geospatial

* [GeoMesa](http://www.geomesa.org/) - 支持Accumulo，HBase，Cassandra和Kafka的时空数据库.

#### Graph
* [Gradoop](https://github.com/dbs-leipzig/gradoop) - 基于Flink和HBase构建的可扩展图形分析的研究框架.
* [HGraphDB](https://github.com/rayokota/hgraphdb) -  HBase作为TinkerPop图数据库.
* [JanusGraph](http://janusgraph.org/) - 可扩展的图形数据库，支持Cassandra，HBase，Google Cloud Bigtable和BerkeleyDB.
* [S2Graph](http://s2graph.incubator.apache.org) - 基于HBase构建的高性能分布式图形数据库.

#### SQL/OLAP

* [AntsDB](http://antsdb.com/) -  AntsDB是HBase的低延迟，高并发，MySQL兼容的SQL层.
* [EsgynDB](https://esgyn.com/) - 商业SQL引擎，基于Trafodian在Hadoop之上提供ACID事务和BI分析.
* [Kylin](http://kylin.apache.org) - 用于在HBase中存储数据的大数据的Extreme OLAP引擎.
* [LeanXScale](http://www.leanxcale.com) - 基于Hadoop / HBase构建的商业完整ACID完整SQL产品.
* [Phoenix](https://phoenix.apache.org) -  HBase顶部的SQL层.
* [Splice Machine](https://www.splicemachine.com) - 基于HBase构建的商业RDBMS.
* [Trafodian](http://trafodion.apache.org) - 事务性SQL-on-Hadoop / HBase.

#### Time Series

* [Axibase](http://axibase.com/products/axibase-time-series-database/) - 基于HBase构建的分布式时间序列数据库.
* [OpenTSDB](http://opentsdb.net) - 基于HBase构建的可扩展时间序列数据库.
* [Warp 10](http://www.warp10.io) - 传感器数据的时间序列数据库.

### Infrastructure

#### Secondary Indices

* [hindex](https://github.com/Huawei-Hadoop/hindex) -  HBase的二级索引.
* [Lily HBase Indexer](http://ngdata.github.io/hbase-indexer/) - 快速轻松地搜索存储在HBase中的内容.

#### Transactions

* [Haeinsa](https://github.com/VCNC/haeinsa) -  HBase的多行/多表事务库.
* [Omid](https://github.com/yahoo/omid) -  HBase的交易支持.
* [Tephra](http://tephra.incubator.apache.org) -  HBase之上的全球一致性交易.
* [Themis](https://github.com/XiaoMi/themis) - 基于Google Percolator的HBase的跨行/跨表交易.

### Integrations

* [Apex](https://github.com/apache/apex-malhar/tree/master/contrib/src/main/java/com/datatorrent/contrib/hbase) -  Apex-HBase连接器.
* [Beam](https://github.com/apache/beam/tree/master/sdks/java/io/hbase) - 梁HBase集成.
* [Camel](http://camel.apache.org/hbase.html) -  Camel HBase组件.
* [Cascading](https://github.com/Cascading/cascading.hbase) - 用于级联的HBase适配器.
* [Cascalog](https://github.com/sorenmacbeth/hbase-cascalog) -  Cascading.HBase周围的包装用于Cascalog.
* [Crunch](https://github.com/apache/crunch/tree/master/crunch-hbase) - 用于Crunch的HBase适配器.
* [Drill](https://drill.apache.org/docs/querying-hbase/) -  Drill的HBase存储插件.
* [Elasticsearch](https://github.com/mallocator/Elasticsearch-HBase-River) - 用于HBase的Elasticsearch导入河.
* [Flink](https://github.com/apache/flink/tree/master/flink-connectors/flink-hbase) -  Flink-HBase连接器.
* [Gearpump](https://github.com/apache/incubator-gearpump/tree/master/external/hbase) - 用于HBase的Gearpump集成.
* [Giraph](https://github.com/apache/giraph/tree/trunk/giraph-hbase) -  HBase的Giraph输入和输出格式.
* [HAWQ](http://pivotalhd-210.docs.pivotal.io/tutorial/getting-started/hawq/pxf-hbase-external-tables.html) -  HBase上的HAWQ PXF外部表.
* [Hive](https://cwiki.apache.org/confluence/display/Hive/HBaseIntegration) -  Hive HBase集成.
* [Impala](https://www.cloudera.com/documentation/enterprise/latest/topics/impala_hbase.html) -  Impala支持查询HBase表.
* [Kafka](https://github.com/apache/hbase-connectors/tree/master/kafka) -  HBase Kafka代理.
* [Pig](https://github.com/apache/pig/tree/trunk/src/org/apache/pig/backend/hadoop/hbase) - 猪HBase集成.
* [Spark](https://github.com/hortonworks-spark/shc) -  Spark-HBase连接器.
* [Spring for Apache Hadoop](https://projects.spring.io/spring-hadoop/) -  Spring-Hadoop集成，包括HBase支持.
* [Storm](https://github.com/apache/storm/tree/master/external/storm-hbase) -  HBase的Storm / Trident集成.
* [Tajo](https://tajo.apache.org/docs/current/hbase_integration.html) -  Tajo与HBase集成.
* [Zeppelin](https://zeppelin.apache.org/docs/0.6.2/interpreter/hbase.html) -  Apache Zeppelin的HBase shell解释器.

### Tools

* [Ambari](https://ambari.apache.org) - 用于配置，管理和监控Hadoop / HBase集群的软件.
* [Cloudera Manager](https://www.cloudera.com/products/product-components/cloudera-manager.html) - 用于管理生产中的Hadoop / HBase的工具.
* [DbSchema](http://www.dbschema.com/index.html) - 支持HBase的面向图的数据库设计器.
* [Hannibal](https://github.com/sentric/hannibal) - 监视和维护HBase集群的工具.
* [h-rider](https://github.com/NiceSystems/hrider) - 用于查看和操作HBase中的数据的GUI.
* [Hue](http://gethue.com) - 包含HBase浏览器的智能分析工作台.
* [Sematext SPM](http://sematext.com/spm) - 工具 [monitoring HBase](http://sematext.com/spm/integrations/hbase-monitoring)，HDFS等

### Miscellaneous

* [HubSpot HBase support](https://github.com/HubSpot/hbase-support) -  HubSpot上HBase的配置和工具，包括Hystrix集成和协处理器.

## Resources

### Books

* [HBase in Action](https://www.manning.com/books/hbase-in-action) - 体验驱动的指南，向您展示如何使用HBase.
* [HBase: The Definitive Guide](http://shop.oreilly.com/product/0636920014348.do) -  HBase综合指南.
* [Architecting HBase Applications](http://shop.oreilly.com/product/0636920035688.do) - 包括HBase原则，集群指南和深入的案例研究.
* [HBase Administration Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/hbase-administration-cookbook) - 如何掌握HBase配置和管理.
* [HBase Essentials](https://www.packtpub.com/big-data-and-business-intelligence/hbase-essentials) - 使用HBase的实用指南.
* [HBase Design Patterns](https://www.packtpub.com/big-data-and-business-intelligence/hbase-design-patterns) - 使用HBase开发可扩展应用程序的成功模式.
* [Learning HBase](https://www.packtpub.com/big-data-and-business-intelligence/learning-hbase) - 了解HBase管理和开发的基础知识.
* [HBase High Performance Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/hbase-high-performance-cookbook) - 令人兴奋的项目，教你如何使用HBase.
* [Apache HBase Primer](http://www.apress.com/us/book/9781484224236) -  HBase必需品的紧凑指南.
* [Pro Apache Phoenix](http://www.apress.com/us/book/9781484223697) - 使用Phoenix的基本和最佳实践.

### Papers

* [Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf) -  HBase的灵感来源.
* [Apache Hadoop Goes Realtime at Facebook](https://pdfs.semanticscholar.org/865a/215390cd49af9e4941e03107120e631dcaa0.pdf) -  Facebook如何将HBase部署到生产中.

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
      style =“border-style：none;”  alt =“公共域标记”/&gt;
</a>
