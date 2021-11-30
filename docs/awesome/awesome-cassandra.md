<div class="github-widget" data-repo="Anant/awesome-cassandra"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cassandra [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
<a href="http://cassandra.apache.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Cassandra_logo.svg" align="right" width="140"></a>

 Cassandra 是一个免费、开源、分布式、广泛的列存储 NoSQL 数据库管理系统，旨在处理跨许多商品服务器的大量数据，提供高可用性且无单点故障.  Cassandra 由 Apache 软件基金会支持，也称为 Apache Cassandra.

这是一个很棒的精选列表 [Cassandra](https://github.com/apache/cassandra) 包和资源. 由 Rahul Singh 维护 [Anant](http://anant.us) . 如果您想在此列表和其他很棒的列表上进行协作，请随时与我联系. [Awesome Cassandra](https://github.com/Anant/awesome-cassandra) , [Awesome Solr](https://github.com/Anant/awesome-solr), [Awesome Lucene](https://github.com/Anant/awesome-lucene) . 这为 *Resources* 部分提供了动力 [Cassandra.Link](https://cassandra.link)、丰富的博客提要和精选链接作为可搜索的知识库.



  
## General

### Cassandra

- [Apache Cassandra](http://cassandra.apache.org/) - 快速管理海量数据，不会失眠.

### Cassandra History


- [IDG: 10 Years of Apache Cassandra](https://www.idgconnect.com/article/3580401/10-years-of-apache-cassandra.html) - 回顾讨论 Cassandra 历史的前 10 年.
- [ZDNet: Cassandra Turns 10](https://www.zdnet.com/article/apache-cassandra-turns-10/) - Cassandra 在前 10 年的发展亮点.

### Cassandra Use Cases

- [Datastax Academy: What is Cassandra?](https://www.datastax.com/cassandra) - Cassandra 是什么、它来自哪里以及它的一些好处的介绍.
- [Kaa application based on Raspberry Pi and DHT11 sensor](https://github.com/pyroalf/kaa-cassandra-sample) - 带有 Raspberry Pi 和 DHT11 传感器的 Cassandra IoT 用例.
- [Simple Node.js Express 4 Cassandra Application](https://github.com/bradtraversy/mysubscribers)  - MySubscribers 是一个非常简单的应用程序（应用程序的启动），它允许您创建、读取、更新和删除用户/订阅者. 此应用程序仅用于帮助 YouTube 课程.

### Cassandra Distributions

#### Cassandra Compliant Databases on JVM

- [DataStax Enterprise](https://dtsx.io/3DkP5sN) - Cassandra 使用最广泛的商业发行版，与 Apache Spark（用于 SparkSQL、分析）、Apache Solr（用于二级索引）、存储在 Cassandra 中的基于 Apache TinkerPop 的 Graph 和 OpsCenter 集成.
- [DDAC/Luna](https://luna.datastax.com/)  - Cassandra 的 Datastax Distribution，一个生产就绪的发行版，带有 Datastax 支持的批量加载器.  DDAC 现在已弃用，但 Datastax 仍通过其新的 Luna 服务支持 Cassandra.

#### Cassandra Compliant Databases on C++

- [ScyllaDB](https://github.com/scylladb/scylla) - 使用 seastar 框架的 NoSQL 数据存储，与 Cassandra 兼容.
- [YugaByte Database](https://github.com/YugaByte/yugabyte-db)  - YugaByteDB 是用于构建分布式云服务的事务性高性能数据库. 它支持与 Cassandra 兼容和 Redis 兼容的 API，以及 Beta 版的 PostgreSQL.

#### Cassandra as a Service / Managed Cassandra Based on Open Source Cassandra

- [DataStax Astra](https://dtsx.io/38htEun) - DataStax Astra Cassandra 即服务，在 AWS 和 GCP 上可用的 Kubernetes 运营商 Cassandra 上运行.
- [IBM Cloud Databases for DataStax](https://www.ibm.com/cloud/databases-for-datastax) - 适用于 DataStax Enterprise 的 IBM Cloud Managed Service.
- [Instaclustr Managed Cassandra as a Service](https://www.instaclustr.com/solutions/managed-apache-cassandra/) - Instaclustr 为 AWS、Azure、GCP 和 IBM Cloud 上的 Cassandra® 提供完全托管和 SOC 2 认证的托管和托管服务.
- [Aiven for Cassandra](https://aiven.io/cassandra/)  - Aiven for Cassandra 是一个托管和托管的分布式 NoSQL 数据库，提供可扩展性、高可用性和出色的容错能力.  Cassandra 即服务可在 Google Cloud Platform、Amazon Web Services、Microsoft Azure、DigitalOcean 和 UpCloud 上使用.
- [Microsoft Azure Managed Instance for Cassandra](https://docs.microsoft.com/en-us/azure/managed-instance-apache-cassandra/)  - 适用于 Cassandra 的 Azure 托管实例为托管开源 Cassandra 数据中心提供自动化部署和缩放操作. 它可以加速混合场景并减少持续维护.

#### Cassandra as a Service / Managed Cassandra Based on Proprietary Technology

- [Microsoft Azure Cosmos DB: Cassandra API](https://docs.microsoft.com/en-us/azure/cosmos-db/cassandra-introduction) - Azure Cosmos DB 为为需要高级功能的 Cassandra 编写的应用程序提供 Cassandra API（预览版）.
- [Amazon Keyspaces for Cassandra](https://aws.amazon.com/keyspaces) - 适用于 Cassandra 的 Amazon Web Services (AWS) Amazon Keyspaces 提供对“无服务器”自动扩展数据存储的符合 CQL 的访问.

### Using Cassandra

<!-- - TODO:: cassandra installation tutorials in local, docker, cloud (do, aws, azure, gcp)) -->
<!-- - TODO:: compiling cassandra -->
<!-- - TODO:: running cassandra -->
<!-- - TODO:: using cql -->
<!-- - TODO:: using zeppelin with cassandra -->
<!-- - TODO:: getting data in / out of cassandra -->
<!-- - TODO:: using spark with cassandra -->

- [Installing the Cassandra / Spark OSS Stack](https://tobert.github.io/post/2014-07-15-installing-cassandra-spark-stack.html) - Cassandra / Spark OSS Stack 的安装过程和用户​​指南.
- [The Cassandra Query Language](http://cassandra.apache.org/doc/latest/cql/) - CQL 文档.
- [The LIMIT Clause in Cassandra might not work as you think](http://thelastpickle.com/blog/2017/03/07/The-limit-clause-in-cassandra-might-not-work-as-you-think.html) - 关于 LIMIT 子句效率的考虑的博客文章.
- [Building a Performant API using Go and Cassandra](https://getstream.io/blog/building-a-performant-api-using-go-and-cassandra/) - 记录如何使用 Go 和 Cassandra 构建 RESTful API 的教程.
- [Cassandra Data Copy Tool](https://github.com/wildengineer/cassandra-data-copy-tool) - 将数据从一个 cassandra 表复制到另一个的 Java 工具.
- [Spring Data Cassandra Examples](https://github.com/jxblum/spring-data-cassandra-examples) - Spring Data Cassandra 项目的示例.
- [Introduction to Spark & Cassandra](http://rustyrazorblade.com/post/2015/2015-01-02-intro-to-spark-and-cassandra/) - 关于设置一个非常简单的 Spark 作业的博客文章，该作业为 Cassandra 执行数据迁移.
- [From Cassandra to S3, with Spark](https://objectpartners.com/2016/11/30/from-cassandra-to-s3-with-spark/) - 博客文章展示了如何将 Spark 连接到 Cassandra，分析来自 Cassandra 的事件数据，并将分析结果存储到 S3，使其可用于报告或进一步分析.
- [Import CSV files with spark](https://github.com/markthebault/importCSVSparkCassandra) - 如何使用 Spark 将文件从 S3 导入 cassandra.
- [Top 5 reasons to use the Cassandra Database](https://towardsdatascience.com/top-5-reasons-to-use-the-apache-cassandra-database-d541c6448557) - 您想考虑 Cassandra 的理由很少.
- [Cloud DevOps with Cassandra](http://cloudurable.com/blog/aws-ansible-packer-ssh-for-devops/index.html) - 使用 Packer、Ansible/SSH 和 AWS 命令​​行工具在 AWS 中创建和 DBA 管理 EC2 Cassandra 实例.
- [How to install Cassandra 2 on CentOS 7 / RHEL 7](https://sharadchhetri.com/2015/04/25/how-to-install-cassandra-2-on-centos-7-rhel-7/) - 关于如何在流行的 Linux 发行版 RedHat 和 CentOS 上安装 Cassandra 的指南.
- [Cassandra Use Cases: When to use and when not to use Cassandra](https://blog.pythian.com/cassandra-use-cases/) - 何时使用和何时不使用 Cassandra 的实用指南.
- [Cassandra Database (Guide)](https://www.instaclustr.com/education/apache-cassandra-database) - 从 Instaclustr 了解 Cassandra 的绝佳指南.

<!-- - TODO:: sql v. cql-->
<!-- - TODO:: query driven methodology -->
<!-- - TODO:: schema designs / examples-->
<!-- - TODO:: data modeling problems -->

### Cassandra from Relational

- [RDBMS to NoSQL](http://www.datastax.com/relational-database-to-nosql) - 了解 NoSQL 是否适合您的路线图.
- [Cassandra Schemas for Beginners (like me)](https://medium.com/@jochasinga/cassandra-schemas-for-beginners-like-me-9714cee9236a) - 适合 Cassandra 新开发人员的好文章.
- [Cassandra Query Language: CQL vs SQL](https://medium.com/@alexbmeng/cassandra-query-language-cql-vs-sql-7f6ed7706b4c) - 记录 CQL 和 SQL 之间的异同的博客文章.
- [Real-Time Replication from MySQL to Cassandra](https://planet.mcb.guru/?p=6890) - 将数据从 MySQL 迁移到 Cassandra 的演示.
- [Cassandra Tutorial for Beginners](https://www.guru99.com/cassandra-tutorial.html) - 刚开始使用 Cassandra 的用户的课程计划.

### Cassandra Data Modeling

- [Basic Rules Of Cassandra Data Modeling](http://www.datastax.com/dev/blog/basic-rules-of-cassandra-data-modeling)  - 选择正确的数据模型是使用 Cassandra 最困难的部分. 如果您有关系背景，CQL 会看起来很熟悉，但您使用它的方式可能会大不相同.
- [CQL: This is not the SQL you are Looking For](https://www.slideshare.net/aploetz/cql-this-is-not-the-sql-you-are-loooking-for) - 探索和解释 CQL 和 SQL 语言之间差异的演示文稿.
- [A Deep Look at the CQL Where Clause](https://www.datastax.com/dev/blog/a-deep-look-to-the-cql-where-clause) - 描述 CQL WHERE 子句支持的内容以及它与普通 SQL 不同的原因的博客文章.
- [killrvideo-sample-schema](https://github.com/pmcfadin/killrvideo-sample-schema) - YouTube 克隆的示例 Cassandra CQL 架构.
- [Spring Data Cassandra Examples](https://github.com/jxblum/spring-data-cassandra-examples/blob/master/src/main/resources/cassandra-example-schema.cql) - Maven 项目，其中包含展示 Spring Data Cassandra 项目特性和功能的示例.
- [Common Problems in Cassandra Data Models](https://blog.anant.us/common-problems-cassandra-data-models/) - 关于宽分区、墓碑和数据倾斜的演示文稿和文章.
- [Casandra Time Series Data Modeling for Massive Scale](http://thelastpickle.com/blog/2017/08/02/time-series-data-modeling-massive-scale.html) - 讨论称为分桶的常见 Cassandra 数据建模技术的博客文章.
- [Cassandra Data Modeling Notes](https://miguelperez.xyz/blog/2017/2/13/cassandra-data-modeling-notes) - 关于如何估计集群大小的简单说明.
- [Scalar DB](https://github.com/scalar-labs/scalardb) - Cassandra 的事务库，使非 ACID 分布式数据库/存储符合 ACID.
- [Cassandra Data Modeling Best Practices Guide](https://www.instaclustr.com/cassandra-data-modeling/) - 解释了五个 Cassandra 数据建模最佳实践.

<!-- - TODO: - Data Centers and Racks -->
<!-- - TODO: - Gossip and Failure Detection -->
<!-- - TODO: - Snitches -->
<!-- - TODO: - Rings and Tokens -->
<!-- - TODO: - Virtual Nodes -->
<!-- - TODO: - Partitioners -->
<!-- - TODO: - Replication Strategies -->
<!-- - TODO: - Consistency Levels -->
<!-- - TODO: - Queries and Coordinator Nodes -->
<!-- - TODO: - Memtables, SSTables, and Commit Logs -->
<!-- - TODO: - Caching -->
<!-- - TODO: - Hinted Handoff -->
<!-- - TODO: - Lightweight Transactions and Paxos -->
<!-- - TODO: - Tombstones -->
<!-- - TODO: - Bloom Filters -->
<!-- - TODO: - Compaction -->
<!-- - TODO: - Anti-Entropy, Repair, and Merkle Trees -->
<!-- - TODO: - Staged Event-Driven Architecture (SEDA) -->
<!-- - TODO: - Managers and Services -->
<!-- - TODO: - System Keyspaces -->

### Cassandra Architecture

- [The Gossip Protocol - Inside Cassandra.](https://www.linkedin.com/pulse/gossip-protocol-inside-apache-cassandra-soham-saha) - Cassandra 如何保持一致的良好视觉解释.
- [Introduction To The Cassandra 3.x Storage Engine](http://thelastpickle.com/blog/2016/03/04/introductiont-to-the-apache-cassandra-3-storage-engine.html) - 3.x 存储引擎使 Cassandra 更容易从磁盘中获取字节.
- [Dropping columns in Cassandra 3.0](http://thelastpickle.com/blog/2016/02/18/dropping-columns.html) - 描述删除列时 Cassandra 采取的步骤的博客文章.
- [Hinted Handoff and GC Grace Demystified](http://thelastpickle.com/blog/2018/03/21/hinted-handoff-gc-grace-demystified.html) - 调整 GC Grace 和 Hinted Handoff 之间的平衡.
- [Deletes and Tombstones](http://thelastpickle.com/blog/2011/05/15/Deletes-and-Tombstones.html) - 解释删除如何在 Cassandra 中创建墓碑以及它们是什么.
- [About Deletes and Tombstones in Cassandra](http://thelastpickle.com/blog/2016/07/27/about-deletes-and-tombstones.html) - 从 Cassandra 等系统中删除分布式和复制的数据比在关系数据库中要复杂得多.
- [Null bindings on prepared statements and undesired tombstone creation](http://thelastpickle.com/blog/2016/09/15/Null-bindings-on-prepared-statements-and-undesired-tombstone-creation.html) - 对上一篇关于墓碑的文章进行了很好的跟进.
- [Undetectable tombstones in Cassandra](http://thelastpickle.com/blog/2018/07/05/undetectable-tombstones-in-apache-cassandra.html) - 深入分析单元格和范围墓碑.
- [Common Problems with Cassandra Tombstones](https://opencredo.com/cassandra-tombstones-common-issues/) - 大量墓碑导致延迟和堆压力.
- [Curious Case of Tombstones](https://medium.com/cassandra-tombstones-clearing-use-case/the-curios-case-of-tombstones-d897f681a378) - 有人如何处理墓碑问题并在集群中回收空间.
- [Understanding the Nuance of Compaction in Cassandra](http://thelastpickle.com/blog/2017/03/16/compaction-nuance.html) - Cassandra 如何管理磁盘数据的概述.
- [Guide to Cassandra Thread Pools](https://blog.pythian.com/guide-to-cassandra-thread-pools/)  - 提供不同线程池描述以及如何监控它们的指南. 包括要提醒的内容、常见问题和解决方案. 旧但非常有用的参考.
- [Cassandra Architecture and Operations](https://miguelperez.xyz/blog/2017/2/13/cassandra-architecture-and-operation) - 在一页中对 Cassandra 的工作原理进行了高级概述.
- [Improving Cassandra's Front Door and Backpressure](https://dzone.com/articles/improving-apache-cassandras-front-door-and-backpre) - 探索 Cassandra 之前如何处理传入请求，查看它们发生了什么变化，并查看可用的新相关配置旋钮.
- [Cassandra Architecture](https://www.instaclustr.com/cassandra-architecture/) - Instaclustr 对 Cassandra 的高级概述.
- [The 10 Things I hate about Cassandra](https://blog.pythian.com/the-things-i-hate-about-apache-cassandra/)  - 你真的要使用 Cassandra 吗？ 了解为什么不使用它.

### Cassandra Monitoring

- [Resources for Monitoring Datastax, Cassandra, Spark, & Solr Performance](https://blog.anant.us/resources-for-monitoring-datastax-cassandra-spark-solr-performance/) - 详细介绍不同类型的监控工具及其用途的博客文章.
- [How to Monitor Cassandra](https://www.datadoghq.com/blog/how-to-monitor-cassandra-performance-metrics/) - 帮助您监控 Cassandra 性能和工作指标的指南，无论您选择使用哪种监控工具.
- [Cassandra metrics and their use in Grafana](https://medium.com/@mlowicki/cassandra-metrics-and-their-use-in-grafana-1f0dc33f9cca) - 在 Grafana 中使用 Cassandra 指标的案例研究.
- [Monitoring Cassandra with Prometheus](https://www.robustperception.io/monitoring-cassandra-with-prometheus) - 将 Cassandra 与 Prometheus 结合使用的快速设置指南.
- [Monitoring Cassandra With Grafana And Influx DB](https://blog.pythian.com/monitoring-cassandra-grafana-influx-db/) - 博客文章解释了如何使用 influxDB 和 Grafana 设置 Cassandra 监控.
- [Cassandra Monitoring - Introduction (1/2)](https://softwaremill.com/cassandra-monitoring-part-1/) - 详细介绍如何收集 Cassandra 指标的博客文章.
- [Cassandra Monitoring - Graphite/InfluxDB & Grafana on Docker (2/2)](https://softwaremill.com/cassandra-monitoring-part-2/) - 继续探索第一部分中提到的 Cassandra 指标报告器的主题.目标是配置一个将指标发送到外部时间序列数据库的报告器.
- [Monitoring Cassandra using Intel Snap and Grafana](http://thelastpickle.com/blog/2017/04/13/monitoring-cassandra-using-intel-snap.html) - 描述如何使用 Intel Snap 开源遥测框架监控 Cassandra 的博客文章.
- [Cassandra Monitoring Best Practice Guide](https://www.instaclustr.com/cassandra-monitoring-best-practice-guide/) - 旨在触及 Cassandra 监控所有重要方面的博客文章.

<!-- - TODO:: Health Check -->
<!-- - TODO:: Basic Maintenance -->
<!-- - TODO:: Adding Nodes -->
<!-- - TODO:: Handling Node Failure -->
<!-- - TODO:: Upgrading Cassandra -->
<!-- - TODO:: Backup and Recovery -->
<!-- - TODO:: SSTable Utilities -->
<!-- - TODO:: Maintenance Tools  -->
<!--  - OpsCenter  -->
<!--  - Reaper  -->
<!--  - TableAnalyzer  -->

### Cassandra Maintenance

- [Running commands cluster-wide without any management tool](http://thelastpickle.com/blog/2016/03/21/running-commands-cluster-wide.html) - 在不使用 Chef、Ansible 或 Salt 等工具的情况下执行基本集群操作的一些技巧和窍门.
- [Limiting Nodetool Parallel Threads](http://thelastpickle.com/blog/2017/08/14/limiting-nodetool-parallel-threads.html) - 鲜为人知的工具，可以用较少的资源进行 nodetool 操作.
- [Bootstrapping Cassandra Nodes](http://thelastpickle.com/blog/2017/05/23/auto-bootstrapping-part1.html) - 关于如何将节点添加到正在运行的 Cassandra 集群的深入文章.
- [Node Replacement without Bootstrapping](http://thelastpickle.com/blog/2018/02/21/replace-node-without-bootstrapping.html) - 如何避免漫长的引导过程.
- [Cassandra Backup and Restore - Backup in AWS using EBS Volumes](http://thelastpickle.com/blog/2018/04/03/cassandra-backup-and-restore-aws-ebs.html) - 关于 AWS 中的备份和恢复的深入文章.
- [Backup Strategies for Cassandra](https://blog.pythian.com/backup-strategies-cassandra/) - 对 Cassandra 的不同备份和恢复策略进行了很好的比较.
- [Cassandra backup util](https://github.com/instaclustr/cassandra-backup) - Instaclustr 的 cassandra 备份工具.
- [Cassy](https://github.com/scalar-labs/cassy) - 简单且集成的 Cassandra 备份工具.
- [Intro to CStar](https://thelastpickle.com/blog/2018/10/01/introduction-to-cstar.html) - 关于如何使用 CStar 的教程.
- [Medusa](https://github.com/thelastpickle/cassandra-medusa) - Cassandra 备份系统.

<!-- - TODO:: Managing Performance -->
<!-- - TODO:: Caching -->
<!-- - TODO:: Memtables -->
<!-- - TODO:: Commit Logs -->
<!-- - TODO:: SSTables -->
<!-- - TODO:: Hinted Handoff -->
<!-- - TODO:: Compaction -->
<!-- - TODO:: Concurrency and Threading -->
<!-- - TODO:: Networking and Timeouts -->
<!-- - TODO:: JVM Settings -->
<!-- - TODO:: Using cassandra-stress -->
<!-- - TODO:: Using Gatling -->

### Cassandra Performance Tuning

- [Jon Haddad: Cassandra Summit Recap - Diagnosing Problems in Production](http://rustyrazorblade.com/2014/09/cassandra-summit-recap-diagnosing-problems-in-production/)
- [Ryan Svihla's Cassandra 2.0 checklist](https://medium.com/@foundev/my-cassandra-diagnostics-checklist-brain-dump-599a2b95b118) - 用于确定 Cassandra 数据库效率的清单.
- [Amy's Cassandra 2.1 tuning guide](https://tobert.github.io/pages/als-cassandra-21-tuning-guide.html) - 在生产级 Cassandra 集群中跟踪性能问题的指南.
- [Secret HotSpot option improving GC pauses on large heaps](http://blog.ragozin.info/2012/03/secret-hotspot-option-improving-gc.html)
- [DSE 5.1: Tuning Java Resource](https://docs.datastax.com/en/dse/5.1/dse-admin/datastax_enterprise/operations/opsTuneJVM.html) - 调整 JVM 的文档.
- [Analyzing Cassandra Performance with Flame Graphs](http://thelastpickle.com/blog/2018/01/16/cassandra-flame-graphs.html) - 使用火焰图直观地检查 Cassandra 的性能.
- [Garbage Collection Tuning for Cassandra](http://thelastpickle.com/blog/2018/04/11/gc-tuning.html) - 优化垃圾收集以获得更好的性能.
- [Cassandra Node Diagnostics Tools](https://github.com/smartcat-labs/cassandra-diagnostics) - Cassandra 的监控和审计电源套件.
- [TWCS part 1 - how does it work and when should you use it?](http://thelastpickle.com/blog/2016/12/08/TWCS-part1.html) - 最适合过期的时间序列数据，时间窗口压缩策略带有一些警告.
- [Performing User Defined Compactions in Cassandra](http://thelastpickle.com/blog/2016/10/18/user-defined-compaction.html) - 记录我们告诉 Cassandra 为一个或多个表显式创建压缩任务的过程.
- [Graphing cassandra-stress](http://thelastpickle.com/blog/2015/10/23/cassandra-stress-and-graphs.html) - 使用 cassandra-stress 工具对架构和配置更改进行基准测试，然后将此类更改推送到生产环境是每个 Cassandra 开发人员应该知道并定期练习的事情之一.
- [Modeling real life workloads with cassandra-stress is hard](http://thelastpickle.com/blog/2017/02/08/Modeling-real-life-workloads-with-cassandra-stress.html) - Blog post detailing caveats with cassandra-stress when modeling real workloads.
- [Gatling DSE Stress](https://github.com/datastax/gatling-dse-stress) - 压力测试 DSE 的工具.
- [Gatling DSE Plugin for Gatling Load injector](https://github.com/datastax/gatling-dse-plugin)  - Gatling 负载注入器的插件. 它在 Gatling 中为 Datastax Enterprise 添加了 CQL 支持. 它允许对 Datastax Enterprise 功能进行基准测试，包括 DSE Graph Fluent API.
- [Gatling DSE Stress Simulation Catalog](https://github.com/datastax/gatling-dse-simcatalog)  - repo 的目标是提供 Gatling DSE Stress Framework 的使用示例. 随意提交带有示例模拟的拉取请求.
<!-- !Now just redirects to https://www.datastax.com/dev - [A Deeper Dive - Diagnosing DSE Performance Issues with Ttop and Multidump](https://academy.datastax.com/support-blog/deeper-dive-diagnosing-dse-performance-issues-ttop-and-multidump)  - 关于如何更深入地了解 Cassandra 线程的良好回顾.  --&gt;

<!-- - TODO:: Authentication and Authorization -->
<!-- - TODO:: Encryption -->
<!-- - TODO:: JMX Security -->
<!-- - TODO:: Disk -->
<!-- - TODO:: System -->
<!-- - TODO:: Network -->

### Cassandra Security

- [Securing Cassandra with Application Level Encryption](https://www.instaclustr.com/securing-apache-cassandra-with-application-level-encryption/) - 讨论如何进行应用级数据加密以正确管理 Cassandra 中的安全信息.
- [Hardening Cassandra Step by Step: Part 1](http://thelastpickle.com/blog/2015/09/30/hardening-cassandra-step-by-step-part-1-server-to-server.html) - 节点间加密（以及对证书的温和介绍）.
- [LDAP Authenticator for Cassandra](https://github.com/instaclustr/cassandra-ldap) - Cassandra 的可插入身份验证实现，提供了一种基于配置的 LDAP 服务器进行身份验证和创建用户的方法.
- [Encrypting EC2 ephemeral volumes with LUKS and AWS KMS](https://www.whaletech.co/2016/04/07/encryption-ephemeral-volumes-with-kms.html) - 此处使用的示例是存储在临时磁盘上的 Cassandra 数据.

<!-- - TODO:: Container Deployment -->
<!-- - TODO:: Container Orchestration -->
<!-- - TODO:: Cloud Deployment -->
<!-- - TODO:: Cloud Automations -->

### Cassandra Deployment

- [An Introduction to Cassandra Multi-Data Centers: Part 1](https://www.instaclustr.com/around-the-world-in-approximately-8-data-centres-globally-distributed-storage-streaming-and-search-part-1/) - 了解如何规划和实施多数据中心：第 1 部分.
- [An Introduction to Cassandra Multi-Data Centers: Part 2](https://www.instaclustr.com/around-the-world-globally-distributed-storage-streaming-and-search-an-introduction-to-cassandra-multi-data-centers-part-2/) - 了解如何规划和实施多数据中心：第 2 部分.
- [How To Setup A Highly Available Multi-AZ Cassandra Cluster On AWS EC2](http://highscalability.com/blog/2016/8/1/how-to-setup-a-highly-available-multi-az-cassandra-cluster-o.html)
- [tlp-cluster, a tool for launching Cassandra clusters in AWS](https://github.com/thelastpickle/tlp-cluster)  - Cassandra 的配置工具，专为希望对 Cassandra 的正确性进行基准测试和测试的开发人员而设计. 它有助于在 AWS 上构建和启动实例.
- [Setting Up Cassandra Cluster Through Ansible](https://blog.knoldus.com/setting-up-cassandra-cluster-through-ansible/) - 详细介绍如何使用 Ansible 通过自动化设置 Cassandra 集群的指南.
- [Running Cassandra on DC/OS (Mesos)](http://thelastpickle.com/blog/2016/05/07/dcos.html) - 展示如何在 Amazon 云中设置 DC/OS、如何在 DC/OS 集群上安装 Cassandra 以及安装后与 Cassandra 交互的新方法的博客.
- [Benchmarking Cassandra with Local Storage on Azure](https://www.instaclustr.com/benchmarking-cassandra-with-local-storage-on-azure/) - 了解在具有本地存储和远程存储的 Azure VM 上比较 Cassandra.

#### Cassandra Deployment on Docker / Containerized Cassandra

- [Docker Meet Cassandra. Cassandra Meet Docker](http://thelastpickle.com/blog/2018/01/23/docker-meet-cassandra.html) - 文章回顾了如何设置一个完整的 Cassandra 应用程序，并在 Docker 上进行监控.
- [Example code from the Docker Meet Cassandra Article](https://github.com/thelastpickle/docker-cassandra-bootstrap)
- [Docker-Cassandra](https://github.com/nicolasff/docker-cassandra) - Set of scripts and config files to run a Cassandra cluster from Docker.
- [Cassandra & Zeppelin Notebook on Docker](https://github.com/academyofdata/cassandra-zeppelin) - 用于 Cassandra + Zeppelin 设置的 Docker-Compose 脚本.
- [Packer: Cassandra Image](https://github.com/cloudurable/cassandra-image)  - Cassandra 映像使用 Packer 用于 Docker 和 EC2 AMI. 涵盖使用 Ansible 管理 EC2 Cassandra 集群.
- [Cassandra Docker](https://github.com/instaclustr/cassandra-docker)  - Cassandra 的 Instaclustr 公共 docker 镜像. 它包含 Cassandra 3.0 和 3.11.1 的 docker 镜像.
- [Cassandra / Elassandra Docker](https://github.com/zegelin/cassandra-docker) - Cassandra 和 Elassandra docker 图像.Cass Operator 由 DataStax 的一个团队维护，它是 DataStax Astra 的一部分.

#### Cassandra Deployment on Kubernetes / Kubernetized Cassandra

- [K8ssandra.io - Kubernetes + Cassandra](https://k8ssandra.io/)  - K8ssandra 为在 Kubernetes 上运行 Cassandra 提供了一个生产就绪平台. 这包括维修、备份和监控等操作任务的自动化.
- [Datastax - Cassandra Kubernetes Operator](https://github.com/datastax/cass-operator) - Datastax 的 Cassandra Kubernetes Operator，它支持 Datastax 以及 Kubernetes 上的开源 Cassandra 容器.
- [Instaclustr - Kubernetes Operator for Cassandra](https://github.com/instaclustr/cassandra-operator) - Cassandra 操作员管理部署到 Kubernetes 的 Cassandra 集群，并自动执行与操作 Cassandra 集群相关的任务.
- [Sky UK - Cassandra Kubernetes Operator](https://github.com/sky-uk/cassandra-operator)  - Kubernetes 操作员，用于管理 Kubernetes 内的 Cassandra 集群. 精心设计和组织.
- [CassKop - Cassandra operator for Kubernetes](https://github.com/Orange-OpenSource/cassandra-k8s-operator)  - Kubernetes operator 自动执行 Cassandra 操作，例如部署新的机架感知集群、添加/删除节点、配置 C 和 JVM 参数、升级 JVM 和 C 版本. 用 Go 编写.
- [Strapdata - Elassandra Operator for Kubernetes](https://github.com/strapdata/elassandra-operator) - Elassandra Kubernetes Operator 自动部署和管理部署在多个 Kubernetes 集群中的 Elassandra 集群.
- [Rook.io - Cassandra on Kubernetes](https://rook.io/docs/rook/v1.4/cassandra.html)  - Rook 是一个开源云原生存储编排器，为各种存储解决方案提供平台、框架和支持，以与云原生环境进行原生集成. 他们在其他提供商中为 Cassandra 提供了一个特殊的运营商.
- [Kudo Cassandar Operator](https://github.com/mesosphere/kudo-cassandra-operator) - KUDO Cassandra Operator 使在 Kubernetes 上部署和管理 Cassandra 变得容易.

### Integrating with Cassandra

- [Building a Streaming Data Hub with Elasticsearch, Kafka and Cassandra](http://thenewstack.io/building-streaming-data-hub-elasticsearch-kafka-cassandra/) - 详细介绍如何在开源大数据组件之上构建流分析系统的博客文章.
- [Docker container for Kafka - Spark streaming - Cassandra](https://github.com/Yannael/kafka-sparkstreaming-cassandra) - Dockerfile 设置完整的流环境，用于试验 Kafka、Spark 流 (PySpark) 和 Cassandra.
- [sample KafkaSparkCassandra](https://github.com/instaclustr/sample-KafkaSparkCassandra) - 介绍性示例 scala 应用程序使用 Apache Spark Streaming 接受来自 Kafka 的数据并将摘要写入 Cassandra.
- [sample Spark Cassandra with SSL](https://github.com/instaclustr/sample-SparkCassandrawithSSL) - 简单的示例作业，说明如何使用 Spark 通过 SSL 连接通过 Cassandra 执行 Apache Spark 分析.

<!-- - TODO:: ESB -->
<!-- - TODO:: Streaming -->
<!-- - TODO:: ETL -->
<!-- - TODO:: CDC -->

#### .NET and Cassandra

- [Cassandra API with .NET](https://docs.microsoft.com/en-us/azure/cosmos-db/cassandra/manage-data-dotnet) - 有关如何使用 .NET 和 Azure Cosmos DB Cassandra API 构建配置文件应用程序的快速入门指南.
- [DataStax C# Driver](https://github.com/datastax/csharp-driver) - C# Driver for Cassandra from DataStax.
- [DataStax C# Driver Documentation](https://docs.datastax.com/en/developer/csharp-driver/3.4/) - Documentation on the C# Driver for Cassandra from DataStax.
- [CQL data types to C# types](https://docs.datastax.com/en/developer/csharp-driver/3.4/features/datatypes/) - Documentation on CQL data types to C# types.
- [Connect to Cassandra with C#](https://www.instaclustr.com/support/documentation/cassandra/using-cassandra/connect-to-cassandra-with-c-sharp/#) - Instaclustr article on how to connect to Cassandra with C#.
- [Access Amazon Keyspaces with a Cassandra .NET Core Driver](https://docs.aws.amazon.com/keyspaces/latest/devguide/using_dotnetcore_driver.html) - 文章展示了如何使用 .NET Core 客户端驱动程序连接到 Amazon Keyspaces.
- [Cassandra ADO.NET Driver](https://www.cdata.com/drivers/cassandra/ado/) - Cassandra ADO.NET 数据提供程序使用户能够轻松地从 .NET 应用程序连接到 Cassandra 数据.
- [Cassandra Pagination with ASP.NET Core C#](https://bhonemyintkyaw777.medium.com/cassandra-pagination-with-asp-net-core-c-a85fd58f6b2b) - Article covering how to create infinite scroll pagination with Cassandra and ASP.NET Core C#.

#### Spark

- [DataStax Spark Cassandra Connector](https://github.com/datastax/spark-cassandra-connector) - 允许您将 Cassandra 表公开为 Spark RDD、将 Spark RDD 写入 Cassandra 表以及在 Spark 应用程序中执行任意 CQL 查询的库.
- [sample Spark Job Server Cassandra](https://github.com/instaclustr/sample-SparkJobserverCassandra) - 简单的示例作业，说明如何使用 Spark Jobserver 通过 Cassandra 执行 Apache Spark 分析.
- [fluxcapacitor/pipeline](https://github.com/fluxcapacitor/pipeline) - 使用 Spark、Spark SQL、Spark ML、GraphX、Spark Streaming、Kafka、NiFi、Cassandra、ElasticSearch、Redis、Tachyon、HDFS、Zeppelin、iPython/Jupyter 的端到端、实时、高级分析大数据参考管道笔记本、Tableau、Twitter 代鸟.
- [Spark + Cassandra Best Practices](https://blog.pythian.com/spark-cassandra-best-practices/) - 一起概述 Spark 和 Cassandra 的一般用例和最佳实践.

#### Search / Secondary Indexes

- [Tuning DSE Search](http://www.datastax.com/dev/blog/tuning-dse-search) - 调整 DSE 搜索 - 索引延迟和查询延迟.
- [Cassandra Lucene Index](https://github.com/Stratio/cassandra-lucene-index) - 基于 Lucene 的 Cassandra 二级索引.
- [Elassandra](http://www.elassandra.io/) - Elassandra = Elasticsearch 作为 Cassandra 二级索引.
- [cassandra-trigger](https://github.com/gradeup/cassandra-trigger) - Cassandra 触发器将实时更新推送到 elasticsearch.

## Databases

### Timeseries Databases

#### Monitoring / Metrics

- [cortexproject/cortex](https://github.com/cortexproject/cortex) - 水平可扩展、高可用、多租户、长期 Prometheus 存储.
- [filodb/FiloDB](https://github.com/filodb/FiloDB) - 与 Prometheus 查询兼容的分布式 Prometheus 时间序列数据库.
- [cybem/cyanite-iow](https://github.com/cybem/cyanite-iow)  - Cassandra 支持 Carbon 守护进程和度量网络服务.  IPONWEB 存储库，与 Carbon 兼容.

#### Custom Time Series

- [kairosdb/kairosdb](https://github.com/kairosdb/kairosdb) - 快速可扩展的时间序列数据库. 
- [Cassandra Schema — KairosDB 1.0.1 documentation](https://kairosdb.github.io/docs/build/html/CassandraSchema.html) - KairosDB 文档.
- [Newts](https://opennms.github.io/newts/) - 基于 Cassandra 的时间序列数据存储.
- [OpenNMS/newts](https://github.com/OpenNMS/newts) - 支持 OpenNMS 的新型时间序列数据存储.
- [Hawkular.org](https://www.hawkular.org/) - 由 Redhat 提供的 Cassandra 支持的时间序列/分布式跟踪数据库.
- [Hawkular GitHub](https://github.com/hawkular) - Hawkular 的 GitHub 资源.
- [OpenTSDB/opentsdb](https://github.com/OpenTSDB/opentsdb) - GitHub resources for OpenTSDB. A Distributed, Scalable Monitoring System built on a Time Series Database.

### Graph

- [DSE Graph | Datastax](https://www.datastax.com/products/datastax-graph) - TitanDB 的继承者，商业 Tinkerpop / Gremlin 兼容 DSE 上的大规模图形数据库.
- [Thinkaurelius/Titan](https://github.com/thinkaurelius/titan) - 分布式图数据库，DSE Graph、JanusGraph 和现在的 HugeGraph 的前身.
- [Introduction to TitanDB](https://www.slideshare.net/knoldus/introduction-to-titandb) - 关于 TitanDB 的介绍性幻灯片.
- [JanusGraph/janusgraph](https://github.com/JanusGraph/janusgraph) - JanusGraph：一个开源的分布式图形数据库，TitanDB 的继承者.
- [Large Scale Graph Analytics with JanusGraph](https://www.slideshare.net/Hadoop_Summit/large-scale-graph-analytics-with-janusgraph-77153443) - 幻灯片详细介绍了 JanusGraph 的部署选项和技术方面.
- [Hugegraph/Hugegraph](https://github.com/hugegraph/hugegraph) - HugeGraph 数据库核心组件，包括图形引擎、API 和内置后端.
- [Architecture Overview · GitBook](https://hugegraph.github.io/hugegraph-doc/guides/architectural.html) - HugeGraph 的文档.

### Miscellaneous

- [Cassandra vs MongoDB](https://www.spec-india.com/blog/cassandra-vs-mongodb) - 文章比较了两种流行的 NoSQL 数据库.
- [Stargate](https://github.com/stargate/stargate) - Stargate 是一个开源数据网关，为 Cassandra 提供 REST、GraphQL 和无模式 JSON 接口.
- [Meet Stargate, DataStax's GraphQL for databases. First stop - Cassandra](https://www.zdnet.com/article/meet-stargate-datastaxs-graphql-for-databases-first-stop-cassandra/) - 星际之门的介绍和高级概述.
- [Apache/Usergrid](https://github.com/apache/usergrid) - Cassandra 上的开源后端即服务 (BaaS)、Elasticsearch 以及适用于 iOS/Android/.NET/Java 的客户端 SDK.
- [Building Your Own BaaS With Apache Usergrid &amp; Docker: Lessons Learned At Scale](http://events17.linuxfoundation.org/sites/events/files/slides/Building%20Your%20Own%20BaaS%20With%20Apache%20Usergrid%20%26%20Docker.pdf) - Apache UserGrid 的介绍性介绍.
- [Scalar-labs/Scalardl](https://github.com/scalar-labs/scalardl) - 防篡改和可扩展的分布式账本平台.
- [Wikimedia/Restbase](https://github.com/wikimedia/restbase) - 具有 REST API 和调度程序的分布式存储，用于后端服务.
- [Wikimedia/restbase-mod-table-spec](https://github.com/wikimedia/restbase-mod-table-spec) - RESTBase 表存储的共享规范和测试.

## Packages

### Libraries

- [express-cassandra](https://github.com/masumsoft/express-cassandra) - Node.js 的 Cassandra ORM/ODM/OGM，可选支持 Elassandra 和 JanusGraph.
- [DataStax Java Driver](https://github.com/datastax/java-driver) - Cassandra 的 Java 客户端驱动程序.
- [DataStax C++ Driver](https://github.com/datastax/cpp-driver) - 适用于 Cassandra (1.2+) 和 DataStax Enterprise (3.1+) 的现代、功能丰富且高度可调的 C/C++ 客户端库，专门使用 Cassandra 的本机协议和 Cassandra 查询语言 v3.
- [DataStax Python Driver](https://github.com/datastax/python-driver) - 用于 Cassandra (2.1+) 的现代、功能丰富且高度可调的 Python 客户端库，专门使用 Cassandra 的二进制协议和 Cassandra 查询语言 v3.
- [DataStax Ruby Driver](https://github.com/datastax/ruby-driver)  - 用于 Cassandra 的 Ruby 客户端驱动程序. 此驱动程序专门用于 Cassandra 查询语言版本 3 (CQL3) 和 Cassandra 的本机协议.
- [DataStax Node.js Driver](https://github.com/datastax/nodejs-driver) - 适用于 Cassandra (1.2+) 和 DataStax Enterprise (3.1+) 的现代、功能丰富且高度可调的 Node.js 客户端库，专门使用 Cassandra 的二进制协议和 Cassandra 查询语言 v3.
- [DataStax C# Driver](https://github.com/datastax/csharp-driver) - Modern, feature-rich and highly tunable C# client library for Cassandra (1.2+) and DataStax Enterprise (3.1+) using exclusively Cassandra's binary protocol and Cassandra Query Language v3.
- [DataStax PHP Driver](https://github.com/datastax/php-driver) - 适用于 Cassandra 的 DataStax PHP 驱动程序.
- [Achilles](http://doanduyhai.github.io/Achilles/) - Achilles 是 Cassandra 的开源持久化管理器，具有高级 bean 映射（复合主键、复合分区键、timeUUID 等）、本机集合和映射支持等功能.
- [phpcassa](https://github.com/thobbs/phpcassa) - Cassandra 的 PHP 客户端库.
- [Caffinitas](https://bitbucket.org/snazy/caffinitas/src/develop/) - Caffinitas 是 Cassandra 的高级对象映射器，专门设计用于与 Datastax Java Driver 2.1+ 配合使用，以对抗 Cassandra 2.1、2.0 或 1.2.
- [Spring Data for Cassandra](http://projects.spring.io/spring-data-cassandra/) - Spring Data for Cassandra 为过去使用过其他 Spring Data 模块的人提供了熟悉的界面.
- [gocql](https://github.com/gocql/gocql) - 包 gocql 为 Go 编程语言实现了一个快速而健壮的 Cassandra 客户端.

### Tools

- [Hackolade](https://hackolade.com) - 用于 NoSQL 数据库和 Cassandra、ElasticSearch、Graph DB、JSON、API 等结构的可视化数据建模工具.  
- [JetBrains Datagrip DB IDE](https://www.jetbrains.com/datagrip/) - JetBrains 用于数据库和 SQL 的跨平台 IDE，支持 Cassandra.
- [Datastax - Management API for Cassandra](https://github.com/datastax/management-api-for-apache-cassandra) - 管理 API 是一个 sidecar 服务层，它试图在 Cassandra® 节点上构建一组支持良好的操作操作，这些操作可以集中管理.
- [DataStax OpsCenter](http://www.datastax.com/what-we-offer/products-services/datastax-opscenter) - 简化了对 DataStax Enterprise 和 Cassandra 数据库集群的管理.
- [CassandraCAS](https://github.com/Datomic/CassandraCAS) - 由 Datomic 创建的用于 Cassandra 的比较和交换工具.
- [Peloton](https://github.com/uber/peloton)  - 由 Uber 创建的统一资源调度程序. 该工具可以通过资源管理和可扩展性来处理许多节点和集群.
- [Ansible-Galaxy: Cassandra GitHub](https://github.com/ansible-collections/community.cassandra) - 名为 cassandra 的集合，旨在提供允许与 Cassandra 交互的所有 Ansible 模块. 
- [Ansible-Galaxy: Cassandra](https://galaxy.ansible.com/community/cassandra) - Ansible-Galaxy 的文档：Cassandra.
- [Ansible-dse](https://github.com/rackerlabs/ansible-dse) - 将构建 Datastax Enterprise 集群的一组 Ansible 剧本.
- [dseansible](https://github.com/yabinmeng/dseansible) - Ubuntu Linux 的 DSE 安装和升级 Ansible 剧本/角色.
- [DbSchema - Cassandra Designer](https://dbschema.com/database-designer/Cassandra.html) - DbSchema：Cassandra 图表设计器和 GUI 管理工具，可以在其他数据库中执行 Cassandra.
- [DBeaver - Free Universal Database Tool](https://dbeaver.io/) - 用于处理包括 Cassandra 在内的各种数据库的第三方工具.
- [RazorSQL - Multi DB Manager Tool](https://razorsql.com/) - 适用于 Cassandra 的 Linux、Mac 和 Windows 多数据库工具.
- [Cassandra Reaper](http://cassandra-reaper.io/)  - Cassandra 的自动修复. 支持所有版本.
- [cstar perf](https://github.com/datastax/cstar_perf) - Cassandra 性能测试平台.
- [Spark Cassandra Stress](https://github.com/datastax/spark-cassandra-stress) - 针对 Cassandra 或 DSE 测试 DataStax Spark 连接器的工具.
- [cqlmigrate](https://github.com/sky-uk/cqlmigrate)  - Cassandra CQL 迁移工具.  cqlmigrate 是一个用于在 cassandra 集群上执行模式迁移的库.
- [cassandra-migration-tool-java](https://github.com/smartcat-labs/cassandra-migration-tool-java) - Java Cassandra 迁移工具是一个轻量级的工具，用于在 Cassandra 数据库上执行架构和数据迁移.
- [Cassalog](https://github.com/hawkular/cassalog) - Cassalog 是 Cassandra 的模式更改管理库和工具，可与在 JVM 上运行的应用程序一起使用.
- [cdeploy](https://github.com/rackerlabs/cdeploy) - Cdeploy 是一个简单的工具，用于以 dbdeploy 的风格管理您的 Cassandra 模式迁移.
- [Web: Cassandra Calculator](https://www.ecyrd.com/cassandracalculator/) - 用于查看大小/复制因子如何影响系统一致性的简单计算器.
- [Cassandra-web](http://avalanche123.com/cassandra-web/) - Cassandra 的 Web 界面.
- [CassanddraRestfulAPI](https://github.com/rohitsakala/CassandraRestfulAPI) - CassandraRestfulAPI 项目借助 Restful API 公开 cassandra 数据表.
- [Netflix: Staash](https://github.com/Netflix/staash) - 与语言和存储无关的 Web 界面，用于将数据存储到持久存储系统中，元数据层抽象了大量存储细节，模式自动化 API 负责自动化常见的数据访问模式.
- [cql-vim](https://github.com/elubow/cql-vim) - 用于 Vim 的 Cassandra CQL 语法荧光笔.
- [Presto](https://prestodb.io/)  - 用于大数据的分布式 SQL 查询引擎.  Presto 允许查询数据所在的位置，包括 Hive、Cassandra、关系数据库甚至专有数据存储.
- [SSTable Tools](https://github.com/tolbertam/sstable-tools) - 使用 Cassandra 3.x SSTables 解析、创建和做其他有趣事情的工具包.
- [Cassandra-Exporter](https://github.com/masumsoft/cassandra-exporter) - Simple Tool to Export / Import Cassandra Tables into JSON.
- [Cassandra SStable Tools](https://github.com/instaclustr/cassandra-sstable-tools) - 多种不同的工具合二为一，帮助管理员获取摘要、元数据、分区信息、单元信息.
- [Cassandra-Client](https://github.com/Kindrat/cassandra-client) - 用于在 Cassandra 中浏览表格和数据的简单 gui 工具.
- [CQL Data Modeler](https://www.sestevez.com/sestevez/CassandraDataModeler/) - 非常有用的工具，用于测试 CQL 模式并可视化分区与列和行的关系.
- [Cassandra Snapshot Backup](https://github.com/avinash-mishra/cassandra_snapshot_backup) - 在 Cassandra 数据库中对文件进行快照并使用 Ansible 进行备份的快速简便方法.
- [Slothsandra](https://github.com/MacKittipat/slothsandra) - Cassandra 与 Slack 应用程序的集成，该应用程序存储 Slack 不再自行处理的旧消息.
- [sandraREST](https://github.com/aksakalli/sandraREST) - 带有用于 RESTful API 的 Web UI 的 Cassandra 管理器.
- [Cassandra Leadership](https://github.com/paradoxical-io/cassandra.leadership)  - 使用 cassandra 帮助选举领导人的图书馆. 使用paxos构建领导选举模块.
- [Terraform Cassandra](https://github.com/conrad-mukai/terraform-cassandra) - 创建 Cassandra 集群的 Terraform 模块.
- [Datadog](https://www.datadoghq.com/blog/monitoring-cassandra-with-datadog/) - 允许对 Cassandra 节点和集群进行监控和度量的第三方工具.
- [tlp-cluster](http://thelastpickle.com/tlp-cluster/)  - Cassandra 配置工具，专为希望对 Cassandra 进行基准测试和测试的开发人员而设计. 它有助于在 AWS 上构建和启动实例.
- [Helenos](https://github.com/tomekkup/helenos) - 免费的基于 Web 的环境，使用 Cassandra 数据库简化了数据探索和模式管理.
- [ValuStor](https://github.com/Sensaphone/ValuStor) - ValuStor 是一个键值对数据库解决方案.
- [Cassandra-Migration](https://github.com/hhandoko/cassandra-migration) - Cassandra / DataStax Enterprise 数据库迁移（架构演化）库.
- [JanuesGraph-Utils](https://github.com/IBM/janusgraph-utils) - 开发图形数据库应用程序的工具.
- [Scylla-Migrator](https://github.com/scylladb/scylla-migrator) - 使用 Spark 将数据提取迁移到 Scylla，通常来自 Cassandra.
- [Cassandra CA Manager](https://github.com/eevans/cassandra-ca-manager) - 创建并签署 Java 密钥库.
- [Zipkin](https://github.com/openzipkin/zipkin) - 分布式追踪系统.
- [Instaclustr Kerberos plugin](https://github.com/instaclustr/cassandra-kerberos) - Cassandra 的 GSSAPI 身份验证提供程序.
- [Instaclustr Java Driver for Kerberos](https://github.com/instaclustr/cassandra-java-driver-kerberos) - Cassandra Java 驱动程序的 GSSAPI 身份验证提供程序.
- [Instaclustr Minotaur](https://github.com/instaclustr/instaclustr-minotaur) - 用于一致重建 Cassandra 集群的命令行工具.
- [Instaclustr TTL Remover](https://github.com/instaclustr/cassandra-ttl-remover) - 用于重写 SSTable 以删除 TTL 的命令行工具.
- [Instaclustr SSTable Generator](https://github.com/instaclustr/cassandra-sstable-generator) - 用于以编程方式生成 Cassandra SSTable 的 CLI 工具.
- [Instaclustr Exporter](https://github.com/instaclustr/cassandra-exporter) - 将 Cassandra 指标导出到 Prometheus 的 Java 代理.
- [Instaclustr Go Client for Instaclustr Icarus](https://github.com/instaclustr/instaclustr-icarus-go-client) - 去 Instaclustr Icarus sidecar 的客户端.

### Open Source Applications

- [Twissandra](https://github.com/twissandra/twissandra)  - Twissandra 是一个示例项目，旨在学习和演示如何使用 Cassandra. 运行该项目将显示一个与 Twitter 具有类似功能的网站.
- [ChronoServer](https://github.com/cyngn/ChronoServer) - 测试服务器以采样移动和网络客户端向执行常见请求模式的服务器发出各种类型的请求所需的时间.
- [Cassandra Cluster Admin](https://github.com/sebgiroux/Cassandra-Cluster-Admin) - Cassandra Cluster Admin 是一个 GUI 工具，可帮助人们管理他们的 Cassandra 集群.
- [Cassandra-Tools](https://github.com/CrowdStrike/cassandra-tools) - Python Fabric 脚本可帮助在 AWS 上自动启动和管理集群测试.
- [Cassandra Opstools](https://github.com/spotify/cassandra-opstools) - 用于审查和监控 cassandra 的通用脚本，来自 Spotify.  
- [CCM: Cassandra Cluster Manager)](https://github.com/pcmanus/ccm) - 在本地主机上创建、启动和删除 Cassandra 集群的脚本/库.
- [Netflix-Priam](https://github.com/Netflix/Priam) - 用于 Cassandra 的备份/恢复、令牌管理和集中配置管理的协同处理.
- [CStar](https://github.com/spotify/cstar) - 用于命令行的 Cassandra 集群编排工具.
- [CMB](https://github.com/Comcast/cmb) - 与 AWS SQS 和 SNS 兼容的高度可用、水平可扩展的排队和通知服务.
- [CassieQ](https://github.com/paradoxical-io/cassieq) - 基于 Cassandra 构建的分布式队列.
- [Cherami](https://eng.uber.com/cherami/) - 分布式、可扩展、持久且高可用的消息队列系统.
- [Scheduler](https://github.com/PagerDuty/scheduler) - Scala 库，用于安排任意代码在任意时间运行.

### Logging /Metrics

- [cassandra-log4j-appender](https://github.com/datastax/cassandra-log4j-appender) - 用于 Log4j 的 Cassandra 附加程序.
- [Metrics Collector for Cassandra](https://github.com/datastax/metric-collector-for-apache-cassandra)  - Cassandra（2.2、3.0、3.11、4.0）集群的指标集合和仪表板. 带有用于 Graphana 的仪表板.
- [Cassandra Log Tools](https://github.com/erickramirezDSE/cass_log_tools) - 用于处理 Cassandra 日志的简单脚本.
- [Cassandra CFStats to CSV Parser](https://github.com/jlacefie/cfstats-csv-parser) - 将 CFStats 的输出转换为 CSV.
- [Cassandra Nagios](https://github.com/causes/cassandra-nagios) - 基于 Perl 的脚本，用于获取使用 Jolokia 进行监控的指标.
- [ctop](https://github.com/pixonic/ctop) - 非常简单的控制台工具，用于监控远程 cassandra 主机上的列族读/写活动.
- [Cassandra StatD Agent](https://github.com/lookout/cassandra-statsd-agent) - Cassandra 与 StatsD 集成的 Java 代理.

## Resources

### Documentation

- [Cassandra Documentation](http://cassandra.apache.org/doc/) - 所有已发布版本的最终文档.
- [DataStax Documentation](http://docs.datastax.com/en/landing_page/doc/landing_page/current.html) - 来自 DataStax 的文档和驱动程序.

### Books

- [Cassandra: The Definitive Guide, 3rd Edition](https://www.amazon.com/gp/product/1098115163/)
- [Cassandra: The Definitive Guide, 2nd Edition](https://www.amazon.com/gp/product/1491933666/)
- [Cassandra High Availability](https://www.packtpub.com/big-data-and-business-intelligence/cassandra-high-availability)
- [Expert Apache Cassandra Administration](https://link.springer.com/book/10.1007/978-1-4842-3126-5)

### Courses

- [DataStax Academy](https://academy.datastax.com/) - 关于 Cassandra 的免费在线课程.

### Communities

- [Cassandra Users Mailing List](http://www.mail-archive.com/user@cassandra.apache.org/)
- [Cassandra Developers Mailing List](http://www.mail-archive.com/dev@cassandra.apache.org/)
- [Cassandra Commits Mailing List](http://www.mail-archive.com/commits@cassandra.apache.org/)
- [Apache Software Foundation Slack](https://s.apache.org/slack-invite) - The #cassandra and #cassandra-dev channels are official slack channels migrating from IRC.
- [Cassandra Slack](https://cassandra-slack.herokuapp.com/)
- [Stack Overflow: Cassandra](https://stackoverflow.com/questions/tagged/cassandra)
- [Stack Overflow: cql](https://stackoverflow.com/questions/tagged/cql)
- [Stack Overflow: spark-cassandra-connector](https://stackoverflow.com/questions/tagged/spark-cassandra-connector)
- [Stack Overflow: Astra DataStax - ASP.NET Core](https://stackoverflow.com/questions/66506642/astra-datastax-asp-net-core-secure-connect-bundle-zip-file-working-in-loca) - 回答了有关连接 DataStax Astra 和发布到 Microsoft Azure 的 ASP.NET Core API 的问题.
- [Quora: Cassandra](https://www.quora.com/topic/Cassandra-database)
- [Meetups: Cassandra](https://www.meetup.com/topics/cassandra/?_cookie-check=mHgLvBy3N6Cke1RU)

### Blogs

- [Datastax](https://www.datastax.com/blog) - DataStax, Inc. 是一家数据管理公司，提供基于 Cassandra 的商业支持、软件和云数据库即服务.
- [Codecentric: Cassandra](https://blog.codecentric.de/en/tag/cassandra/) - Codecentric 是一家 IT 咨询公司，这些是他们围绕 Cassandra 主题的博客文章.
- [Pythian: Cassandra](https://blog.pythian.com/technical-track/cassandra-2/)  - Pythian 提供数据和云相关服务. 该公司为 Oracle、SQL Server、MySQL、Hadoop、Cassandra 等数据库及其配套基础设施提供服务.
- [Instaclustr](https://www.instaclustr.com/blog/) - 管理和支持 Cassandra、Kafka、Elasticsearch 和 Redis 的开源解决方案.
- [OpenCredo:Cassandra](https://opencredo.com/tag/cassandra/) - OpenCredo 是一家咨询公司，可帮助客户围绕云原生和开源技术以及公共云服务做出明智的决策.
- [DOAN DuyHai's Blog: Cassandra](http://www.doanduyhai.com/blog/?cat=57) - Duyhai Doan 是一名自由大数据和云架构师，他重视分享知识并为技术社区做出贡献.
- [Amy Tobert](https://tobert.github.io/)  - Amy Tobert 是一名全栈工程师和领导者，对可持续系统和以人为本的领导充满热情. 她的博客详细介绍了不同的 Cassandra 部署以及其他主题.
- [Christopher Batey: Cassandra](http://batey.info/cassandra.html) - Christopher Batey 是一名拥有超过 15 年经验的软件工程师，是 Akka 的主要贡献者，偶尔也为 Cassandra 做出贡献.
- [Distributed Bytes: Cassandra](https://distributedbytes.timojo.com/search/label/cassandra)  - Tim Ojo 是分布式字节的创建者和 Capital one 的软件工程师. 这些是他围绕 Cassandra 主题的帖子集.
- [The Netflix Tech Blog](https://medium.com/netflix-techblog) - 了解 Netflix 世界一流的工程工作、公司文化、产品开发等.
- [Spotify R&D / Engineering Blog : Cassandra](https://engineering.atspotify.com/tag/apache-cassandra/) - Spotify 官方技术博客上的 Cassandra 相关帖子.
- [Ryan Svilha](https://lostechies.com/ryansvihla/tags)  - Ryan Svilha 是 DataStax 的首席工程师. 他的博客文章涵盖了围绕 Cassandra 和相关工具的主题.
- [Anant](https://blog.anant.us/) - Anant 构建和管理业务平台，将客户体验和信息系统与实时数据平台连接起来.

### Videos

- [Best Practices for Running Cassandra on AWS](https://www.youtube.com/watch?v=IuJldwJLyFM) - 亚马逊网络服务 (AWS) 和 AWS 技术合作伙伴 Stackdriver 之间的联合网络研讨会，学习适用于存储、分析和管理相当于每天超过 10 亿次测量的查询的最佳实践.
- [Monitoring Cassandra: Don't Miss a Thing (Alain Rodriguez, The Last Pickle) | C* Summit 2016](https://www.youtube.com/watch?v=Q9AAR4UQzMk) - The Last Pickle 的顾问 Alain Rodriguez 发表的演讲，讨论了在 Cassandra 中要监控的内容、方式和原因.
- [Tuning the Spark Cassandra Connector](https://www.youtube.com/watch?v=cKIHRD6kUOc&feature=youtu.be) - Spark Cassandra 连接器的维护者 Russell Spitzer 的精彩演讲.
- [Cassandra.Lunch](https://github.com/Anant/Cassandra.Lunch) - 过去所有 Cassandra.Lunch 网络研讨会的集合，包括围绕 Cassandra 的所有主题的视频、幻灯片和博客文章.
- [Working with .NET and Cassandra/DataStax Enterprise](https://www.youtube.com/watch?v=7W1tOmfREnw) - Getting a C# .NET core application started to work against a Cassandra or DSE database.

### Slides

- [Cassandra DataTables Using Restful API](https://www.slideshare.net/SimranKedia2/cassandra-datatables-using-restful-api) - 如何使用 Python / Flash 创建高性能 API.
- [HAPI Cassandra](https://github.com/victorcouste/hapi-cassandra) - 在 Cassandra 数据库之上带有 hapi Node.js 框架的简单 REST API.
- [GumGum: Multi-Region Cassandra in AWS](https://www.slideshare.net/planetcassandra/gumgum-multiregion-cassandra-in-aws) - 详细介绍 Gumgum 如何从一个本地 Cassandra 数据中心扩展到多数据中心 Cassandra 集群的演示文稿，以及他们在实施过程中遇到的所有问题和做出的选择.
- [Hardening Cassandra for Compliance or Paranoia](https://www.slideshare.net/zznate/hardening-cassandra-for-compliance-or-paranoia) - 包括有关配置 SSL、设置证书颁发机构以及为 JVM 创建证书和信任链的详细信息.
- [Securing Cassandra](https://www.slideshare.net/planetcassandra/securing-cassandra-the-right-way) - Instaclustr 的首席技术官 Ben Bromhead 将探索可以针对威胁环境适当设置和保护 Cassandra 的各种方法.
- [Tuning the Spark Cassandra Connector](https://www.slideshare.net/DataStax/maximum-overdrive-tuning-the-spark-cassandra-connector-russell-spitzer-datastax-c-summit-2016) - 由 Spark Cassandra 连接器的维护者 Russell Spitzer 提供的幻灯片.
