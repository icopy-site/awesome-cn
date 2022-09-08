<div class="github-widget" data-repo="manuzhang/awesome-streaming"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Streaming  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://github.com/manuzhang/awesome-streaming/workflows/build/badge.svg)](https://github.com/manuzhang/awesome-streaming/actions)

精选列表 [streaming (stream processing)](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) 框架、应用程序、阅读资料和其他资源. 灵感来自 [other awesome projects](https://github.com/sindresorhus/awesome). 

## Website

[https://manuzhang.github.io/awesome-streaming/](https://manuzhang.github.io/awesome-streaming/) 是一个更具活力的网站，您可以在这里找到精彩项目的**更新**.



### Streaming Engine

- [Apache Apex](https://github.com/apache/apex-core) [Java] - 大数据流和批处理的统一平台.
- [Apache Ballista](https://github.com/apache/arrow-ballista) [Rust] - 由 Apache Arrow 提供支持的分布式计算平台.
- [Apache Flink](https://github.com/apache/flink) [Java] - 支持有状态计算、数据驱动的窗口语义和迭代流处理的高吞吐量、低延迟数据流处理系统.
- [Apache Heron (incubating)](https://github.com/apache/incubator-heron) [Java] - a realtime, distributed, fault-tolerant stream processing engine from Twitter.
- [Apache Samza](https://github.com/apache/samza) [Scala/Java] - 基于 Kafka（消息传递、存储）和 YARN（容错、处理器隔离、安全和资源管理）的分布式流处理框架.
- [Apache Spark Streaming](https://github.com/apache/spark) [Scala] - 使构建可扩展的容错流应用程序变得容易.
- [Apache Storm](https://github.com/apache/storm)  [Clojure/Java] - 分布式实时计算系统.  Storm 之于流处理就像 Hadoop 之于批处理. 
- [AthenaX](https://github.com/uber/AthenaX) [Java] - 生产中使用的 Uber 流分析框架
- [Faust](https://github.com/robinhood/faust) [Python] - 流处理库，将 Kafka Streams 的想法移植到 Python
- [Gearpump](https://github.com/gearpump/gearpump) [Scala] - 基于 Akka 构建的轻量级实时分布式流引擎.
- [Hazelcast Jet](https://github.com/hazelcast/hazelcast-jet) [Java] - 基于 Hazelcast 构建的通用分布式数据处理引擎.
- [hailstorm](https://github.com/hailstorm-hs/hailstorm) [Haskell] - 基于 Storm 的具有精确一次语义的分布式流处理.
- [Maki Nage](https://github.com/maki-nage/makinage) [Python] - 基于 Kafka 和 ReactiveX 的数据科学家流处理框架.
- [mantis](https://github.com/Netflix/mantis) [Java] - Netflix 构建实时流处理应用生态系统的平台
- [mupd8(muppet)](https://github.com/walmartlabs/mupd8) [Scala/Java] - mapReduce 风格的框架，用于处理快速/流数据.
- [Onyx](https://github.com/onyx-platform/onyx) [Clojure] - 分布式、无主控、高性能、容错数据处理.
- [s4](https://github.com/apache/incubator-s4) [Java] - 通用的、分布式的、可扩展的、容错的、可插拔的平台，允许程序员轻松开发用于处理连续无界数据流的应用程序.
- [SABER](https://github.com/lsds/Saber) [Java/C] - 基于窗口的混合 CPU/GPU 流处理引擎.
- [Scramjet Cloud Platform](https://github.com/scramjetorg/transform-hub) [Python/JavaScript/Node.js] - 用于运行用 Python、JavaScript 或 TypeScript 编写的多个数据处理应用程序（序列）的数据处理引擎 
- [SPQR](https://github.com/ottogroup/SPQR) [Java] - 通过管道处理大量数据流的动态框架.
- [tigon](https://github.com/caskdata/tigon) [C++/Java] - 基于 Hadoop 和 HBase 构建的高吞吐量实时流处理框架.
- [Teknek](https://github.com/edwardcapriolo/teknek-core) [Java] - 使用交互式原型外壳 SOL（流操作符语言）的简单优雅的流处理
Mesos，专为需要灵活性和可控性的高性能数据处理作业而设计.
- [Trill](https://github.com/Microsoft/trill) [.NET/C#] - Trill is a high-performance one-pass in-memory streaming analytics engine from Microsoft Research.
- [Wallaroo](https://github.com/WallarooLabs/wallaroo)  [Python] - 一个快速的流处理框架.  Wallaroo 可以轻松地实时对数据做出反应. 通过消除基础架构的复杂性，从原型到生产从未如此简单.
- [LightSaber](https://github.com/lsds/LightSaber)  [C++] - 基于多核窗口的流处理引擎.  LightSaber 使用代码生成来实现高效的窗口聚合.
- [HStreamDB](https://github.com/hstreamdb/hstream) [Haskell] - 为物联网数据存储和实时处理而构建的流式数据库.
- [Kuiper](https://github.com/emqx/kuiper) [Golang] - 由 Golang 实现的边缘轻量级物联网数据分析/流媒体软件，可以在各种资源受限的边缘设备上运行.
- [WindFlow](https://paragroup.github.io/WindFlow) [C++] - 用于多核和 GPU 的 C++17 数据流处理并行库

### Streaming Library

- [Apache Kafka Streams](https://github.com/apache/kafka) [Java] - Apache Kafka 中包含的轻量级流处理库（从 0.10 版本开始）.
- [Streamiz](https://github.com/LGouellec/kafka-streams-dotnet) [C#] - a .Net Stream Processing Library for Apache Kafka
- [Akka Streams](https://github.com/akka/akka) [Scala] - Akka Actors 上的流处理库.
- [Daggy](https://github.com/synacker/daggy) [C++] - 实时流聚合和捕获. 
- [Benthos](https://github.com/Jeffail/benthos) [Go] - Benthos 是一种高性能和弹性的消息流服务，能够连接各种源和接收器，并对有效负载执行任意操作、转换和过滤器
- [FS2(prev. 'Scalaz-Stream')](https://github.com/functional-streams-for-scala/fs2) [Scala] - Scala 的组合式流式 I/O 库.
- [monix](https://github.com/monix/monix) [Scala] - 用于编写异步和基于事件的程序的高性能 Scala / Scala.js 库.
- [Scramjet Node.js](https://github.com/scramjetorg/framework-js) - [Node.js] 在 Node.js 对象流之上编写的函数式反应流编程框架 + [the legacy Scramjet.js version](https://github.com/scramjetorg/scramjet)
- [Scramjet Python](https://github.com/scramjetorg/framework-python) - [Python] 功能性反应流编程框架，从头开始编写，对对象、字符串和缓冲区流进行操作.
- [Scramjet C++](https://github.com/scramjetorg/framework-cpp) - [C++] 在 Node.js 对象流之上编写的函数式反应流编程框架.
- [Streamline](https://github.com/hortonworks/streamline)  [Java] - Hortonworks 的流分析框架，设计为围绕现有流解决方案（如 Storm）的包装器. 旨在允许用户拖放流组件以专注于业务逻辑.
- [StreamAlert](https://github.com/airbnb/streamalert) [Python] - Airbnb 的实时数据分析和警报.
- [Swave](https://github.com/sirthias/swave) [Scala] - 用于 Scala 的轻量级反应式流基础设施工具包.
- [Streamz](https://github.com/python-streamz/streamz)  [Python] - 用于构建管道以管理连续数据流的轻量级库； 支持涉及分支、连接、流量控制、反馈、背压等复杂管道.
- [Stream Ops](https://github.com/nanosai/stream-ops-java) [Java] - 一个完全可嵌入的数据流引擎和 Java 流处理 API.
- [Tributary](https://github.com/timkpaine/tributary)  [Python] - 用于构建数据流图的 Python 库. 支持使用模仿复杂事件处理器的 python 生成器构建的同步、反应性数据流，以及延迟评估的无环图和函数式柯里化流.
- [YoMo](https://github.com/yomorun/yomo)  [Go] - 用于构建低延迟地理分布式系统的开源流式无服务器框架.  YoMo 建在上面 [QUIC Transport Protocol](https://en.wikipedia.org/wiki/QUIC) 和功能响应式编程接口. 

### Streaming Application

- [straw](https://github.com/rwalk/straw) [Python/Java] - 实时流式搜索平台.
- [storm-crawler](https://github.com/DigitalPebble/storm-crawler) [Java] - 基于 Apache Storm 的网络爬虫 SDK.

### IoT

- [sensorbee](https://github.com/sensorbee/sensorbee) [Go] - 用于物联网的轻量级流处理引擎.
- [Apache Edgent](https://github.com/apache/incubator-edgent) [Java] - 一种编程模型和运行时，可在网关和边缘设备上实现持续流分析，这些设备可以与集中式系统一起使用，在整个物联网生态系统中提供高效和及时的分析：从中心到边缘，由 IBM 开源.
- [Apache StreamPipes](https://github.com/apache/incubator-streampipes) [Java] - 一个自助（工业）物联网工具箱，使非技术用户能够连接、分析和探索物联网数据流.

### DSL

- [Apache Beam](https://github.com/apache/beam) [Java、Python、SQL、Scala、Go] - 统一模型和一组特定于语言的 SDK，用于定义和执行数据处理工作流，以及数据摄取和集成流，支持企业集成模式 (EIP) 和领域特定语言 (DSL) )，由谷歌开源.
- [coast](https://github.com/bkirwi/coast) [Scala] - 在 Samza 之上构建 DAG 并提供精确一次语义的 DSL.
- [Esper](https://github.com/espertechinc/esper) [Java] - 用于复杂事件处理 (CEP) 和事件序列分析的组件.
- [Streamparse](https://github.com/Parsely/streamparse) [Python] - 允许您通过 Apache Storm 针对实时数据流运行 Python 代码.
- [summingbird](https://github.com/twitter/summingbird) [Scala] - 库，可让您编写类似于原生 Scala 或 Java 集合转换的 MapReduce 程序，并在许多著名的分布式 MapReduce 平台上执行它们，包括 Storm 和 Scalding.

### Data Pipeline

- [Apache Kafka](https://github.com/apache/kafka) [Scala/Java] - 分布式、分区、复制的提交日志服务，它提供消息系统的功能，但具有独特的设计.
- [Apache Pulsar](https://github.com/apache/incubator-pulsar) [Java] - 分布式发布-订阅消息传递平台，具有非常灵活的消息传递模型和直观的客户端 API.
- [Apache RocketMQ](https://github.com/apache/rocketmq) [Java] - 具有低延迟、高性能和可靠性、万亿级容量和灵活可扩展性的分布式消息和流媒体平台.
- [brooklin](https://github.com/linkedin/Brooklin/) [Java] - 一种分布式系统，用于在各种异构源和目标系统之间流式传输数据，具有高可靠性和大规模吞吐量，来自 Linkedin（替换数据总线）.
- [camus](https://github.com/linkedin/camus) [Java] - Linkedin 的 Kafka -&gt; HDFS 管道.
- [databus](https://github.com/linkedin/databus) [Java] - Linkedin 的与源无关的分布式变更数据捕获系统.
- [flume](https://github.com/apache/flume) [Java] - 用于高效收集、聚合和移动大量日志数据的分布式、可靠且可用的服务.
- [fluvio](https://github.com/infinyon/fluvio) [Rust/WASM] - 具有在线计算能力的实时可编程数据流平台.
- [Gazette](https://github.com/gazette/core) [golang] - 基于云存储的分布式流媒体基础设施，可以轻松混合和匹配批处理和流媒体范例.
- [LogDevice](https://logdevice.io/) [C++] - Facebook 的高性能分布式系统，用于流式传输和存储顺序数据，使用日志结构.
- [metaq](https://github.com/killme2008/Metamorphosis) [Java] - 淘宝高可用、高性能的分布式消息系统
- [NATS streaming](https://github.com/nats-io/nats-streaming-server) [Go] - 快速的磁盘支持消息传递解决方案
- [nsq](https://github.com/nsqio/nsq) [Go] - 实时分布式消息传递平台，旨在大规模运行，每天处理数十亿条消息.
- [Redpanda](https://github.com/redpanda-data/redpanda) [C++] - Redpanda 与 Kafka 兼容、无 ZooKeeper、无 JVM 且源代码可用.
- [RudderStack](https://github.com/rudderlabs/rudder-server) [Go] - 一个开源的客户数据基础设施（segment、mparticle 替代方案）.
- [suro](https://github.com/Netflix/suro) [Java] - 用于收集、聚合和调度大量应用程序事件（包括日志数据）的数据管道服务.
- [StreamSets Data Collector](https://github.com/streamsets/datacollector-oss) [Java] - 连续大数据摄取基础设施，可读取和写入大量端点，包括 S3、JDBC、Hadoop、Kafka、Cassandra 等.

### Online Machine Learning 

- [Apache Samoa](https://github.com/apache/incubator-samoa) [Java] - 分布式流式机器学习 (ML) 框架，包含分布式流式 ML 算法的编程抽象.
- [DataSketches](https://github.com/DataSketches/sketches-core) [Java] - 来自 Yahoo! 的草图库.
- [streamDM](https://github.com/huawei-noah/streamDM) [Scala] - 使用来自华为的 Spark Streaming 挖掘大数据流.
- [StreamingBandit](https://github.com/Nth-iteration-labs/streamingbandit) [Python] - 提供一个网络服务器来快速设置和评估上下文多臂老虎机 (cMAB) 问题的可能解决方案.
- [StormCV](https://github.com/sensorstorm/StormCV) [Java] - 通过添加计算机视觉 (CV) 特定操作和数据模型，可以使用 Apache Storm 进行视频处理.
- [trident-ml](https://github.com/pmerienne/trident-ml) [Java] - 基于 Trident 的实时在线机器学习库.
- [yurita](https://github.com/paypal/yurita) [Scala] - 基于 Paypal 的 Spark Structured Streaming 构建的异常检测框架.

### Streaming SQL

- [pipelinedb](https://github.com/pipelinedb/pipelinedb) [C] - 一个开源关系数据库，它在流上连续运行 SQL 查询，将结果增量存储在表中.
- [squall](https://github.com/epfldata/squall) [Java] - Squall 在 Storm 之上执行 SQL 查询以进行在线处理.
- [StreamCQL](https://github.com/Zhiqiang-He/StreamCQL) [Java] - 实时计算系统上的连续查询语言.
- [ksqlDB](https://github.com/confluentinc/ksql) [Java] - 云原生、源代码可用 [database](https://ksqldb.io/) 专为流处理应用而设计
- [Materialize](https://materialize.com) [Rust] - 一个源可用的流式 SQL 引擎，用于维护来自消息代理和数据库的数据的物化视图.
- [Siddhi](https://github.com/siddhi-io/siddhi) [Java] - 云原生 Streaming 和复杂事件处理引擎，它了解 Streaming SQL 查询，以便捕获来自不同数据源的事件、处理它们、检测复杂条件并将输出实时发布到各种端点.

### Benchmark

- [storm-perf-test](https://github.com/yahoo/storm-perf-test) [Java] - 一个简单的风暴性能/压力测试.
- [streaming-benchmarks](https://github.com/yahoo/streaming-benchmarks) [Java] - 低延迟（流）解决方案的基准，包括 Apache Storm、Apache Spark、Apache Flink 等.
- [flotilla](https://github.com/tylertreat/Flotilla) [Go] - 用于扩展基准测试的自动消息队列编排.

### Toolkit

- [akka](https://github.com/akka/akka) [Scala] - 用于在 JVM 上构建高度并发、分布式和弹性的消息驱动应用程序的工具包和运行时.
- [pulsar](https://github.com/quantmind/pulsar/) [Python] - 基于 Actor 的事件驱动 Python 并发框架.
- [aeron](https://github.com/real-logic/Aeron) [Java/C++] - 高效可靠的单播和多播消息传输.
- [StreamFlow](https://github.com/lmco/streamflow) [Java] - 流处理工具，旨在帮助构建和监控处理工作流.
- [samza-luwak](https://github.com/romseygeek/samza-luwak) [Java] - 使用 Luwak，一个基于 Lucene 构建的存储查询引擎，在流上实现全文搜索.
- [Turbine](https://github.com/Netflix/Turbine) [Java] - 用于将服务器发送事件 (SSE) JSON 数据流聚合成单个流的工具.
- [Nussknacker](https://github.com/TouK/nussknacker) [Scala] - 定义和运行实时决策算法的可视化工具.

### Closed Source

- [Amazon Kinesis Streams](https://aws.amazon.com/kinesis/) [Java] - AWS 提供的实时、完全托管和可扩展的数据流引擎. 
- [Azure Stream Analytics](https://azure.microsoft.com/en-us/services/stream-analytics/) [.NET] 由 Microsoft Azure 提供的大规模可扩展、完全托管、实时的数据流引擎.
- [Cloud Dataflow](https://cloud.google.com/dataflow/) [Java、Python、SQL、Scala] - Google 的托管流和批处理数据处理引擎. 支持运行 Beam 管道.
- [concord](https://www.slideshare.net/concord-io/may-2016-data-by-the-bay-concord-simple-flexible-stream-processing-on-apache-mesos) [C++] - a distributed stream processing framework built in C++ on top of Apache.
- [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/)  [Python/Java/Scala] - 分布式处理和实时分析平台. 提供开箱即用的高级分析工具包，如地理空间、时间序列等.
- [jubatus](http://jubat.us/en/) [C++] - 分布式处理框架和流式机器学习库.
- [millwheel](http://research.google.com/pubs/pub41378.html) - 用于构建在谷歌广泛使用的低延迟数据处理应用程序的框架.


### Readings

1. [In-Stream Big Data Processing](https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/)
2. [The world beyond batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) 由泰勒 Akidau. 
3. [Real Time Analytics: Algorithms and Systems (VLDB 2015)](http://www.vldb.org/pvldb/vol8/p2040-Kejariwal.pdf)
4. [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems) 作者：Josh Fischer &amp; Ning Wang
5. [Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing](https://www.oreilly.com/library/view/streaming-systems/9781491983867/) 作者：Reuven Lax、Slava Chernyak 和 Tyler Akidau
6. [Data Pipelines with Apache Airflow](https://www.manning.com/books/data-pipelines-with-apache-airflow) Bas P. Harenslak 和 Julian Rutger de Ruiter

## License

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)

许可下 [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
