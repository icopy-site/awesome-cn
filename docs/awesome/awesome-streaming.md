<div class="github-widget" data-repo="manuzhang/awesome-streaming"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Streaming  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://github.com/manuzhang/awesome-streaming/workflows/build/badge.svg)](https://github.com/manuzhang/awesome-streaming/actions)

A curated list of awesome [streaming (stream processing)](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) frameworks, applications, readings and other resources. Inspired by [other awesome projects](https://github.com/sindresorhus/awesome). 

## Website

[https://manuzhang.github.io/awesome-streaming/](https://manuzhang.github.io/awesome-streaming/) 是一个更具活力的网站，您可以在这里找到精彩项目的**更新**.



### Streaming Engine

- [Apache Apex](https://github.com/apache/apex-core) [Java] - unified platform for big data stream and batch processing.
- [Apache Ballista](https://github.com/apache/arrow-datafusion/tree/master/ballista) [Rust] - 由 Apache Arrow 提供支持的分布式计算平台.
- [Apache Flink](https://github.com/apache/flink) [Java] - 支持有状态计算、数据驱动的窗口语义和迭代流处理的高吞吐量、低延迟数据流处理系统.
- [Apache Heron (incubating)](https://github.com/apache/incubator-heron) [Java] - 来自 Twitter 的实时、分布式、容错流处理引擎.
- [Apache Samza](https://github.com/apache/samza) [Scala/Java] - 基于 Kafka（消息传递、存储）和 YARN（容错、处理器隔离、安全和资源管理）的分布式流处理框架.
- [Apache Spark Streaming](https://github.com/apache/spark) [Scala] - makes it easy to build scalable fault-tolerant streaming applications.
- [Apache Storm](https://github.com/apache/storm)  [Clojure/Java] - 分布式实时计算系统.  Storm 之于流处理就像 Hadoop 之于批处理. 
- [AthenaX](https://github.com/uber/AthenaX) [Java] - Uber's Stream Analytics Framework used in production
- [Faust](https://github.com/robinhood/faust) [Python] - 流处理库，将 Kafka Streams 的想法移植到 Python
- [Gearpump](https://github.com/gearpump/gearpump) [Scala] - 基于 Akka 构建的轻量级实时分布式流引擎.
- [Hazelcast Jet](https://github.com/hazelcast/hazelcast-jet) [Java] - A general purpose distributed data processing engine, built on top of Hazelcast.
- [hailstorm](https://github.com/hailstorm-hs/hailstorm) [Haskell] - 基于 Storm 的具有精确一次语义的分布式流处理.
- [Maki Nage](https://github.com/maki-nage/makinage) [Python] - A stream processing framework for data scientists, based on Kafka and ReactiveX.
- [mantis](https://github.com/Netflix/mantis) [Java] - Netflix 构建实时流处理应用生态系统的平台
- [mupd8(muppet)](https://github.com/walmartlabs/mupd8) [Scala/Java] - mapReduce 风格的框架，用于处理快速/流数据.
- [Onyx](https://github.com/onyx-platform/onyx) [Clojure] - 分布式、无主控、高性能、容错数据处理.
- [s4](https://github.com/apache/incubator-s4) [Java] - general-purpose, distributed, scalable, fault-tolerant, pluggable platform that allows programmers to easily develop applications for processing continuous unbounded streams of data.
- [SABER](https://github.com/lsds/Saber) [Java/C] - 基于窗口的混合 CPU/GPU 流处理引擎.
- [Scramjet Transform Hub](https://github.com/scramjetorg/transform-hub) [JavaScript/Node.js] - 用于运行用 JavaScript 或 TypeScript 编写的多个数据处理应用程序（序列）的数据处理引擎  
- [SPQR](https://github.com/ottogroup/SPQR) [Java] - 通过管道处理大量数据流的动态框架.
- [tigon](https://github.com/caskdata/tigon) [C++/Java] - high throughput real-time streaming processing framework built on Hadoop and HBase.
- [Teknek](https://github.com/edwardcapriolo/teknek-core) [Java] - 使用交互式原型外壳 SOL（流操作符语言）的简单优雅的流处理
Mesos, designed for high performance data processing jobs that require flexibility & control.
- [Trill](https://github.com/Microsoft/trill) [.NET/C#] - Trill is a high-performance one-pass in-memory streaming analytics engine from Microsoft Research.
- [Wallaroo](https://github.com/WallarooLabs/wallaroo) [Python] - A fast, stream-processing framework. Wallaroo makes it easy to react to data in real-time. By eliminating infrastructure complexity, going from prototype to production has never been simpler.
- [LightSaber](https://github.com/lsds/LightSaber)  [C++] - 基于多核窗口的流处理引擎.  LightSaber 使用代码生成来实现高效的窗口聚合.
- [HStreamDB](https://github.com/hstreamdb/hstream) [Haskell] - 为物联网数据存储和实时处理而构建的流式数据库.
- [Kuiper](https://github.com/emqx/kuiper) [Golang] - An edge lightweight IoT data analytics/streaming software implemented by Golang, and it can be run at all kinds of resource-constrained edge devices.
- [WindFlow](https://paragroup.github.io/WindFlow) [C++] - 用于多核和 GPU 的 C++17 数据流处理并行库

### Streaming Library

- [Apache Kafka Streams](https://github.com/apache/kafka) [Java] - lightweight stream processing library included in Apache Kafka (since 0.10 version).
- [Akka Streams](https://github.com/akka/akka) [Scala] - stream processing library on Akka Actors.
- [Daggy](https://github.com/synacker/daggy) [C++] - real-time streams aggregation and catching. 
- [Benthos](https://github.com/Jeffail/benthos) [Go] - Benthos 是一种高性能和弹性的消息流服务，能够连接各种源和接收器，并对有效负载执行任意操作、转换和过滤器
- [FS2(prev. 'Scalaz-Stream')](https://github.com/functional-streams-for-scala/fs2) [Scala] - Scala 的组合式流式 I/O 库.
- [monix](https://github.com/monix/monix) [Scala] - 用于编写异步和基于事件的程序的高性能 Scala / Scala.js 库.
- [Scramjet Framework](https://github.com/scramjetorg/scramjet) - functional reactive stream programming framework written on top of Node.js object streams.
- [Streamline](https://github.com/hortonworks/streamline)  [Java] - Hortonworks 的流分析框架，设计为围绕现有流解决方案（如 Storm）的包装器. 旨在允许用户拖放流组件以专注于业务逻辑.
- [StreamAlert](https://github.com/airbnb/streamalert) [Python] - Airbnb's Real-time Data Analysis and Alerting.
- [Swave](https://github.com/sirthias/swave) [Scala] - 用于 Scala 的轻量级反应式流基础设施工具包.
- [Streamz](https://github.com/python-streamz/streamz)  [Python] - 用于构建管道以管理连续数据流的轻量级库； 支持涉及分支、连接、流量控制、反馈、背压等复杂管道.
- [Stream Ops](https://github.com/nanosai/stream-ops-java) [Java] - A fully embeddable data streaming engine and stream processing API for Java.
- [Tributary](https://github.com/timkpaine/tributary)  [Python] - 用于构建数据流图的 Python 库. 支持使用模仿复杂事件处理器的 python 生成器构建的同步、反应性数据流，以及惰性求值的无环图和函数式柯里化流.
- [YoMo](https://github.com/yomorun/yomo)  [Go] - 用于构建低延迟地理分布式系统的开源流式无服务器框架.  YoMo 建在上面 [QUIC Transport Protocol](https://en.wikipedia.org/wiki/QUIC) 和功能响应式编程接口. 

### Streaming Application

- [straw](https://github.com/rwalk/straw) [Python/Java] - A platform for real-time streaming search.
- [storm-crawler](https://github.com/DigitalPebble/storm-crawler) [Java] - Web crawler SDK based on Apache Storm.

### IoT

- [sensorbee](https://github.com/sensorbee/sensorbee) [Go] - lightweight stream processing engine for IoT.
- [Apache Edgent](https://github.com/apache/incubator-edgent) [Java] - 一种编程模型和运行时，可在网关和边缘设备上实现持续流分析，这些设备可以与集中式系统一起使用，在整个物联网生态系统中提供高效和及时的分析：从中心到边缘，由 IBM 开源.
- [Apache StreamPipes](https://github.com/apache/incubator-streampipes) [Java] - a self-service (Industrial) IoT toolbox to enable non-technical users to connect, analyze and explore IoT data streams.

### DSL

- [Apache Beam](https://github.com/apache/beam) [Java, Python, SQL, Scala, Go] - unified model and set of language-specific SDKs for defining and executing data processing workflows, and also data ingestion and integration flows, supporting Enterprise Integration Patterns (EIPs) and Domain Specific Languages (DSLs), open sourced by Google.
- [coast](https://github.com/bkirwi/coast) [Scala] - 在 Samza 之上构建 DAG 并提供精确一次语义的 DSL.
- [Esper](https://github.com/espertechinc/esper) [Java] - 用于复杂事件处理 (CEP) 和事件序列分析的组件.
- [Streamparse](https://github.com/Parsely/streamparse) [Python] - lets you run Python code against real-time streams of data via Apache Storm.
- [summingbird](https://github.com/twitter/summingbird) [Scala] - 允许您编写类似于原生 Scala 或 Java 集合转换的 MapReduce 程序并在许多著名的分布式 MapReduce 平台（包括 Storm 和 Scalding）上执行它们的库.

### Data Pipeline

- [Apache Kafka](https://github.com/apache/kafka) [Scala/Java] - distributed, partitioned, replicated commit log service, which provides the functionality of a messaging system, but with a unique design.
- [Apache Pulsar](https://github.com/apache/incubator-pulsar) [Java] - distributed pub-sub messaging platform with a very flexible messaging model and an intuitive client API.
- [brooklin](https://github.com/linkedin/Brooklin/) [Java] - 一种分布式系统，用于在各种异构源和目标系统之间流式传输数据，具有高可靠性和大规模吞吐量，来自 Linkedin（替换数据总线）.
- [camus](https://github.com/linkedin/camus) [Java] - Linkedin 的 Kafka -&gt; HDFS 管道.
- [databus](https://github.com/linkedin/databus) [Java] - Linkedin 的与源无关的分布式变更数据捕获系统。
- [flume](https://github.com/apache/flume) [Java] - 用于高效收集、聚合和移动大量日志数据的分布式、可靠且可用的服务.
- [fluvio](https://github.com/infinyon/fluvio) [Rust/WASM] - 具有在线计算能力的实时可编程数据流平台.
- [Gazette](https://github.com/gazette/core) [golang] - 基于云存储的分布式流媒体基础设施，可以轻松混合和匹配批处理和流媒体范例.
- [LogDevice](https://logdevice.io/) [C++] - Facebook 的高性能分布式系统，用于流式传输和存储顺序数据，使用日志结构.
- [metaq](https://github.com/killme2008/Metamorphosis) [Java] - Taobao's high available, high performance distributed messaging system
- [NATS streaming](https://github.com/nats-io/nats-streaming-server) [Go] - 快速的磁盘支持消息传递解决方案
- [nsq](https://github.com/nsqio/nsq) [Go] - realtime distributed messaging platform designed to operate at scale, handling billions of messages per day.
- [RudderStack](https://github.com/rudderlabs/rudder-server) [Go] - an open source customer data infrastructure (segment, mparticle alternative).
- [suro](https://github.com/Netflix/suro) [Java] - data pipeline service for collecting, aggregating, and dispatching large volume of application events including log data.
- [StreamSets Data Collector](https://github.com/streamsets/datacollector-oss) [Java] - continuous big data ingestion infrastructure that reads from and writes to a large number of end-points, including S3, JDBC, Hadoop, Kafka, Cassandra and many others.

### Online Machine Learning 

- [Apache Samoa](https://github.com/apache/incubator-samoa) [Java] - 分布式流式机器学习 (ML) 框架，包含分布式流式 ML 算法的编程抽象.
- [DataSketches](https://github.com/DataSketches/sketches-core) [Java] - 来自 Yahoo! 的草图库.
- [streamDM](https://github.com/huawei-noah/streamDM) [Scala] - mining Big Data streams using Spark Streaming from Huawei.
- [StreamingBandit](https://github.com/Nth-iteration-labs/streamingbandit) [Python] - 提供一个网络服务器来快速设置和评估上下文多臂老虎机 (cMAB) 问题的可能解决方案.
- [StormCV](https://github.com/sensorstorm/StormCV) [Java] - enables the use of Apache Storm for video processing by adding computer vision (CV) specific operations and data model.
- [trident-ml](https://github.com/pmerienne/trident-ml) [Java] - 基于 Trident 的实时在线机器学习库.
- [yurita](https://github.com/paypal/yurita) [Scala] - 基于 Paypal 的 Spark Structured Streaming 构建的异常检测框架.

### Streaming SQL

- [pipelinedb](https://github.com/pipelinedb/pipelinedb) [C] - An open-source relational database that runs SQL queries continuously on streams, incrementally storing results in tables.
- [squall](https://github.com/epfldata/squall) [Java] - Squall executes SQL queries on top of Storm for doing online processing.
- [StreamCQL](https://github.com/Zhiqiang-He/StreamCQL) [Java] - 实时计算系统上的连续查询语言.
- [ksqlDB](https://github.com/confluentinc/ksql) [Java] - A cloud-native, source-available [database](https://ksqldb.io/) 专为流处理应用而设计
- [Materialize](https://materialize.com) [Rust] - 一个源可用的流式 SQL 引擎，用于维护来自消息代理和数据库的数据的物化视图.
- [Siddhi](https://github.com/siddhi-io/siddhi) [Java] - 云原生 Streaming 和复杂事件处理引擎，它了解 Streaming SQL 查询，以便捕获来自不同数据源的事件、处理它们、检测复杂条件并将输出实时发布到各种端点.

### Benchmark

- [storm-perf-test](https://github.com/yahoo/storm-perf-test) [Java] - 一个简单的风暴性能/压力测试.
- [streaming-benchmarks](https://github.com/yahoo/streaming-benchmarks) [Java] - Benchmarks for Low Latency (Streaming) solutions including Apache Storm, Apache Spark, Apache Flink, etc.
- [flotilla](https://github.com/tylertreat/Flotilla) [Go] - Automated message queue orchestration for scaled-up benchmarking.

### Toolkit

- [akka](https://github.com/akka/akka) [Scala] - 用于在 JVM 上构建高度并发、分布式和弹性的消息驱动应用程序的工具包和运行时.
- [pulsar](https://github.com/quantmind/pulsar/) [Python] - 基于 Actor 的事件驱动 Python 并发框架.
- [aeron](https://github.com/real-logic/Aeron) [Java/C++] - 高效可靠的单播和多播消息传输.
- [StreamFlow](https://github.com/lmco/streamflow) [Java] - 流处理工具，旨在帮助构建和监控处理工作流.
- [samza-luwak](https://github.com/romseygeek/samza-luwak) [Java] - uses Luwak, a stored-query engine built on Lucene, to implement full-text search on streams.
- [Turbine](https://github.com/Netflix/Turbine) [Java] - tool for aggregating streams of Server-Sent Event (SSE) JSON data into a single stream.

### Closed Source

- [Amazon Kinesis Streams](https://aws.amazon.com/kinesis/) [Java] - real-time, fully managed and scalable data stream engine provided by AWS. 
- [Azure Stream Analytics](https://azure.microsoft.com/en-us/services/stream-analytics/) [.NET] a massively scalable, fully managed, real-time, data stream engine provided by Microsoft Azure.
- [Cloud Dataflow](https://cloud.google.com/dataflow/)[Java, Python, SQL, Scala] - Google's managed stream and batch data processing engine. Supports running Beam pipelines.
- [concord](https://www.slideshare.net/concord-io/may-2016-data-by-the-bay-concord-simple-flexible-stream-processing-on-apache-mesos) [C++] - a distributed stream processing framework built in C++ on top of Apache.
- [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/)  [Python/Java/Scala] - 分布式处理和实时分析平台. 提供开箱即用的高级分析工具包，如地理空间、时间序列等.
- [jubatus](http://jubat.us/en/) [C++] - distributed processing framework and streaming machine learning library.
- [millwheel](http://research.google.com/pubs/pub41378.html) - framework for building low-latency data-processing applications that is widely used at Google.


### Readings

1. [In-Stream Big Data Processing](https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/)
2. [The world beyond batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) 由泰勒 Akidau. 
3. [Real Time Analytics: Algorithms and Systems (VLDB 2015)](http://www.vldb.org/pvldb/vol8/p2040-Kejariwal.pdf)
4. [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems) by Josh Fischer & Ning Wang
5. [Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing](https://www.oreilly.com/library/view/streaming-systems/9781491983867/) by Reuven Lax, Slava Chernyak, and Tyler Akidau
6. [Data Pipelines with Apache Airflow](https://www.manning.com/books/data-pipelines-with-apache-airflow) Bas P. Harenslak 和 Julian Rutger de Ruiter

## License

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)

Licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
