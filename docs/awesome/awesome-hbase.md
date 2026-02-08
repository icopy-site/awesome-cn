<div class="github-widget" data-repo="rayokota/awesome-hbase"></div>
## Awesome HBase [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cdn.rawgit.com/rayokota/awesome-hbase/c197f415/hbase_logo_with_orca-2.png" align="right" width="150">](http://hbase.apache.org/)

A curated list of awesome HBase projects and resources.

[HBase](http://hbase.apache.org) is a distributed, scalable, big data store.




    
## Projects

### Clients

* [asynchbase](https://github.com/OpenTSDB/asynchbase) - Fully asynchronous, non-blocking HBase client.
* [gohbase](https://github.com/tsuna/gohbase) - Pure Go client for HBase.
* [happybase](https://github.com/wbolster/happybase) - Python client for HBase.


### Cloud

* [Amazon EMR](https://aws.amazon.com/emr/) - Amazon's Hadoop/HBase offering on AWS.
* [Azure HDInsight](https://azure.microsoft.com/en-us/services/hdinsight/) - Microsoft's Hadoop/HBase offering on Azure.
* [Cloudera Director](https://www.cloudera.com/products/product-components/cloudera-director.html) - Run Hadoop/HBase clusters on AWS, Azure or Google Cloud.
* [Google Cloud Bigtable](https://cloud.google.com/bigtable/) - High-performance NoSQL database service accessible via HBase client API.
* [Hortonworks Cloudbreak](https://hortonworks.com/open-source/cloudbreak/) - Provision Hadoop/HBase clusters on AWS, Azure, Google Cloud, or OpenStack.

### Frameworks

#### Datasets

* [Kite](http://kitesdk.org) - High-level data layer for Hadoop/HBase.

#### Document

* [HDocDB](https://github.com/rayokota/hdocdb) - HBase as a JSON document database.

#### Entity/JPA

* [DataNucleus](http://www.datanucleus.org) - JPA persistence layer with support for HBase.
* [Gora](http://gora.apache.org) - Persistence library for big data with support for HBase.
* [HBase ORM](https://github.com/flipkart-incubator/hbase-orm) - A production-grade HBase ORM library.
* [HEntityDB](https://github.com/rayokota/hentitydb) - HBase as an entity database.
* [Kundera](https://github.com/impetus-opensource/Kundera) - JPA client with support for HBase.

#### Geospatial

* [GeoMesa](http://www.geomesa.org/) - Spatial-temporal database with support for Accumulo, HBase, Cassandra, and Kafka.

#### Graph
* [Gradoop](https://github.com/dbs-leipzig/gradoop) - Research framework for scalable graph analytics built on Flink and HBase.
* [HGraphDB](https://github.com/rayokota/hgraphdb) - HBase as a TinkerPop graph database.
* [HugeGraph](https://github.com/apache/incubator-hugegraph) - A graph database that supports more than 10+ billion data, high performance and scalability.
* [JanusGraph](http://janusgraph.org/) - Scalable graph database with support for Cassandra, HBase, Google Cloud Bigtable, and BerkeleyDB.
* [NebulaGraph](https://github.com/vesoft-inc/nebula) - A high performance distributed Graph database.
* [S2Graph](http://s2graph.incubator.apache.org) - High-performance distributed graph database built on HBase.
* [Actionbase](https://github.com/kakao/actionbase) - A database for user interactions (likes, views, follows) represented as graphs, with precomputed reads served in real-time.

#### SQL/OLAP

* [AntsDB](http://antsdb.com/) - AntsDB is a low latency, high concurrency, MySQL compliant SQL layer for HBase.
* [EsgynDB](https://esgyn.com/) - Commercial SQL engine providing ACID transactions and BI analytics on top of Hadoop, based on Trafodian.
* [Kylin](http://kylin.apache.org) - Extreme OLAP engine for big data that stores data in HBase.
* [LeanXScale](http://www.leanxcale.com) - Commercial full ACID full SQL product built on Hadoop/HBase.
* [Phoenix](https://phoenix.apache.org) - SQL layer on top of HBase.
* [Splice Machine](https://www.splicemachine.com) - Commercial RDBMS built on top of HBase.
* [Trafodian](http://trafodion.apache.org) - Transactional SQL-on-Hadoop/HBase.

#### Time Series

* [Axibase](http://axibase.com/products/axibase-time-series-database/) - Distributed time series database built on HBase.
* [OpenTSDB](http://opentsdb.net) - Scalable time series database built on HBase.
* [Warp 10](http://www.warp10.io) - Time series database for sensor data.

### Infrastructure

#### Secondary Indices

* [hindex](https://github.com/Huawei-Hadoop/hindex) - Secondary index for HBase.

#### Transactions

* [Haeinsa](https://github.com/VCNC/haeinsa) - Multi-row/multi-table transaction library for HBase.
* [HBase-QoD](https://github.com/algarecu/hbase-0.94.8-qod) - Vector-field consistency for HBase fine-grained transactional inter-DC replication.
* [Omid](https://github.com/apache/incubator-omid) - Transactional support for HBase.
* [Tephra](http://tephra.incubator.apache.org) - Globally consistent transactions on top of HBase.
* [Themis](https://github.com/XiaoMi/themis) - Cross-row/cross-table transactions on HBase based on Google's Percolator.

### Integrations

* [Apex](https://github.com/apache/apex-malhar/tree/master/contrib/src/test/java/org/apache/apex/malhar/contrib/hbase) - Apex-HBase connector.
* [Beam](https://github.com/apache/beam/tree/master/sdks/java/io/hbase) - Beam HBase integration.
* [Camel](http://camel.apache.org/hbase.html) - Camel HBase component.
* [Cascading](https://github.com/Cascading/cascading.hbase) - HBase adapters for Cascading.
* [Cascalog](https://github.com/sorenmacbeth/hbase-cascalog) - Wrapper around Cascading.HBase for use in Cascalog.
* [Crunch](https://github.com/apache/crunch/tree/master/crunch-hbase) - HBase adapters for Crunch.
* [Drill](https://drill.apache.org/docs/querying-hbase/) - HBase storage plugin for Drill.
* [Elasticsearch](https://github.com/mallocator/Elasticsearch-HBase-River) - Elasticsearch import river for HBase.
* [Flink](https://github.com/apache/flink/tree/master/flink-connectors/flink-connector-hbase-2.2) - Flink-HBase connector.
* [Gearpump](https://github.com/apache/incubator-gearpump/tree/master/external/hbase) - Gearpump integration for HBase.
* [Giraph](https://github.com/apache/giraph/tree/trunk/giraph-hbase) - Giraph input and output formats for HBase.
* [HAWQ](https://hawq.apache.org/docs/userguide/2.3.0.0-incubating/pxf/HBasePXF.html) - HAWQ PXF external tables on HBase.
* [Hive](https://cwiki.apache.org/confluence/display/Hive/HBaseIntegration) - Hive HBase integration.
* [Impala](https://www.cloudera.com/documentation/enterprise/latest/topics/impala_hbase.html) - Impala support for querying HBase tables.
* [Kafka](https://github.com/apache/hbase-connectors/tree/master/kafka) - HBase Kafka proxy.
* [Pig](https://github.com/apache/pig/tree/trunk/src/org/apache/pig/backend/hadoop/hbase) - Pig HBase integration.
* [Presto](https://github.com/analysys/presto-hbase-connector) - Presto-HBase connector.
* [Pulsar](http://pulsar.apache.org/docs/en/io-hbase/) - HBase connector for Pulsar.
* [Ranger](https://cwiki.apache.org/confluence/display/RANGER/HBase+Plugin) - HBase plugin for Apache Ranger.
* [Spark](https://github.com/hortonworks-spark/shc) - Spark-HBase connector.
* [Spring for Apache Hadoop](https://projects.spring.io/spring-hadoop/) - Spring-Hadoop integration, including HBase support.
* [Storm](https://github.com/apache/storm/tree/master/external/storm-hbase) - Storm/Trident integration for HBase.
* [Tajo](https://tajo.apache.org/docs/current/hbase_integration.html) - Tajo integration with HBase.
* [Zeppelin](https://zeppelin.apache.org/docs/0.6.2/interpreter/hbase.html) - HBase shell interpreter for Apache Zeppelin.

### Tools

* [Ambari](https://ambari.apache.org) - Software for provisioning, managing, and monitor Hadoop/HBase clusters.
* [Cloudera Manager](https://www.cloudera.com/products/product-components/cloudera-manager.html) - Tool for managing Hadoop/HBase in production.
* [DbSchema](http://www.dbschema.com/index.html) - Diagram-oriented database designer with support for HBase.
* [Hannibal](https://github.com/sentric/hannibal) - Tool to monitor and maintain HBase clusters.
* [h-rider](https://github.com/NiceSystems/hrider) - GUI for viewing and manipulating data in HBase.
* [Hue](http://gethue.com) - Smart analytics workbench that includes an HBase browser.
* [Sematext SPM](http://sematext.com/spm) - Tool for [monitoring HBase](http://sematext.com/spm/integrations/hbase-monitoring), HDFS, etc.

### Miscellaneous

* [HubSpot HBase support](https://github.com/HubSpot/hbase-support) - Configs and tools for HBase at HubSpot, including Hystrix integration and coprocessors.

## Resources

### Books

* [HBase in Action](https://www.manning.com/books/hbase-in-action) - Experience-driven guide that shows you how to use HBase.
* [HBase: The Definitive Guide](http://shop.oreilly.com/product/0636920014348.do) - Comprehensive guide to HBase.
* [Architecting HBase Applications](http://shop.oreilly.com/product/0636920035688.do) - Includes HBase principles, cluster guidelines, and in-depth case studies.
* [HBase Administration Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/hbase-administration-cookbook) - How to master HBase configuration and administration.
* [HBase Essentials](https://www.packtpub.com/big-data-and-business-intelligence/hbase-essentials) - A practical guide to using HBase.
* [HBase Design Patterns](https://www.packtpub.com/big-data-and-business-intelligence/hbase-design-patterns) - Successful patterns to develop scalable applications with HBase.
* [Learning HBase](https://www.packtpub.com/big-data-and-business-intelligence/learning-hbase) - Learn the fundamentals of HBase administration and development.
* [HBase High Performance Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/hbase-high-performance-cookbook) - Exciting projects that teach you how to use HBase.
* [Apache HBase Primer](http://www.apress.com/us/book/9781484224236) - A compact guide to HBase essentials.
* [Pro Apache Phoenix](http://www.apress.com/us/book/9781484223697) - Basic and best practices for using Phoenix.

### Papers

* [Apache Hadoop Goes Realtime at Facebook](https://pdfs.semanticscholar.org/865a/215390cd49af9e4941e03107120e631dcaa0.pdf) - How Facebook deployed HBase to production.

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
     style="border-style: none;" alt="Public Domain Mark" />
</a>
