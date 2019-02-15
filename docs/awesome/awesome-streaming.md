<div class="github-widget" data-repo="manuzhang/awesome-streaming"></div>
## Awesome Streaming  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/manuzhang/awesome-streaming.svg?branch=master)](https://travis-ci.org/manuzhang/awesome-streaming)

精彩的精选列表 [streaming (stream processing)](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html)  框架，应用程序，读数和其他资源.  灵感来自 [other awesome projects](https://github.com/sindresorhus/awesome). 



### Streaming Engine

* [Amazon Kinesis Streams](https://aws.amazon.com/kinesis/) [Java]  -  AWS提供的实时，完全托管和可扩展的数据流引擎 
* [Apache Apex](https://github.com/apache/apex-core) [Java]  - 大数据流和批处理的统一平台.
* [Apache Flink](https://github.com/apache/flink) [Java]  - 用于高吞吐量，低延迟数据流处理的系统，支持有状态计算，数据驱动窗口语义和迭代流处理.
* [Apache Gearpump](https://github.com/apache/incubator-gearpump) [Scala]  - 基于Akka构建的轻量级实时分布式流媒体引擎.
* [Apache Samza](https://github.com/apache/samza) [Scala / Java]  - 基于Kafka（消息传递，存储）和YARN（容错，处理器隔离，安全性和资源管理）构建的分布式流处理框架.
* [Apache Spark Streaming](https://github.com/apache/spark) [Scala]  - 可以轻松构建可扩展的容错流应用程序.
* [Apache Storm](https://github.com/apache/storm)  [Clojure / Java]  - 分布式实时计算系统.  Storm是对Hadoop进行批量处理的流处理. 
* [Faust](https://github.com/robinhood/faust) [Python]  - 流处理库，将想法从Kafka Streams移植到Python
* [Hazelcast Jet](https://github.com/hazelcast/hazelcast-jet) [Java]  - 基于Hazelcast构建的通用分布式数据处理引擎.
* [heron](https://github.com/apache/incubator-heron)   -  Twitter的实时分析平台，与Storm完全API兼容.  在Twitter上，风暴已被Heron取代.
* [mantis](http://www.slideshare.net/g9yuayon/qcon-talk-on-netflix-mantis-a-stream-processing-system), [tech-blog](https://medium.com/netflix-techblog/stream-processing-with-mantis-78af913f51a6) -  Netflix的事件流处理系统.
* [millwheel](http://research.google.com/pubs/pub41378.html) - 用于构建广泛用于Google的低延迟数据处理应用程序的框架.
* [mupd8(muppet)](https://github.com/walmartlabs/mupd8) [Scala / Java]  - 用于处理快速/流数据的mapReduce风格框架.
* [s4](https://github.com/apache/incubator-s4) [Java]  - 通用，分布式，可扩展，容错，可插拔的平台，允许程序员轻松开发用于处理连续无界数据流的应用程序.
* [SPQR](https://github.com/ottogroup/SPQR) [Java]  - 通过管道处理高容量数据流的动态框架.
* [tigon](https://github.com/caskdata/tigon) [C ++ / Java]  - 基于Hadoop和HBase构建的高吞吐量实时流处理框架.
* [hailstorm](https://github.com/hailstorm-hs/hailstorm) [Haskell]  - 基于Storm的精确一次语义的分布式流处理.
* [Teknek](https://github.com/edwardcapriolo/teknek-core) [Java]  - 使用交互式prototying shell SOL（Stream Operator Language）进行简单优雅的流处理
* [concord](https://www.slideshare.net/concord-io/may-2016-data-by-the-bay-concord-simple-flexible-stream-processing-on-apache-mesos) [C ++]  - 在Apache Mesos之上用C ++构建的分布式流处理框架，专为需要灵活性和控制的高性能数据处理作业而设计.
* [StreamBox](https://engineering.purdue.edu/~xzl/xsel/p/streambox/) - 一个现代流处理引擎，可以处理无序流数据，并以低延迟实现高吞吐量.
* [Wallaroo](https://github.com/WallarooLabs/wallaroo)  [Python]  - 超快速弹性数据处理引擎.  大数据或快速数据 - 无需大惊小怪，无需Java.
* [SABER](https://github.com/lsds/Saber) [Java / C]  - 基于窗口的混合CPU / GPU流处理引擎.
* [Onyx](https://github.com/onyx-platform/onyx) [Clojure]  - 分布式，无主，高性能，容错数据处理.
* [AthenaX](https://github.com/uber/AthenaX) [Java]  - 优步在生产中使用的流分析框架

### Streaming Library
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/)  [Python / Java / Scala]  - 用于分布式处理和实时分析的平台.  提供开箱即用的高级分析工具包，如地理空间，时间序列等.
* [Apache Kafka Streams](https://github.com/apache/kafka) [Java]  -  Apache Kafka中包含的轻量级流处理库（自0.10版本起）.
* [Akka Streams](https://github.com/akka/akka) [Scala]  -  Akka Actors上的流处理库. 
* [Swave](https://github.com/sirthias/swave) [Scala]  -  Scala的轻量级Reactive Streams基础架构工具包.
* [FS2(prev. 'Scalaz-Stream')](https://github.com/functional-streams-for-scala/fs2) [Scala]  -  Scala的组合流式I / O库.
* [monix](https://github.com/monix/monix) [Scala]  - 用于组合异步和基于事件的程序的高性能Scala / Scala.js库.
* [Benthos](https://github.com/Jeffail/benthos) [Go]  -  Benthos是一种高性能且有弹性的消息流服务，能够连接各种源和接收器，并对有效负载执行任意操作，转换和过滤
* [Bistro Streams](https://github.com/asavinov/bistro) [Java]  - 一个轻量级流处理库，用于流分析，通过从根本上改变处理方式（流）数据，列存储为数据库做了什么.
* [Streamline](https://github.com/hortonworks/streamline) [Java] - Stream Analytics Framework by Hortonworks, designed as a wrapper around existing streaming solutions like Storm. Aimed to allow users to drag-and-drop streaming components to focus on business logic.
* [StreamAlert](https://github.com/airbnb/streamalert) [Python]  -  Airbnb的实时数据分析和警报.

### Streaming Application

* [straw](https://github.com/rwalk/straw) [Python / Java]  - 实时流式搜索的平台.
* [storm-crawler](https://github.com/DigitalPebble/storm-crawler) [Java]  - 基于Apache Storm的Web爬虫SDK.

### IoT

* [sensorbee](https://github.com/sensorbee/sensorbee) [Go]  - 物联网的轻量级流处理引擎.
* [Apache Edgent](https://github.com/apache/incubator-edgent) [Java]  - 一种编程模型和运行时，可在网关和边缘设备上实现连续流分析，可与集中式系统协同工作，在整个物联网生态系统中提供高效，及时的分析：从中心到边缘，由IBM开源.

### DSL
* [summingbird](https://github.com/twitter/summingbird) [Scala]  - 允许您编写看起来像本机Scala或Java集合转换的MapReduce程序的库，并在许多着名的分布式MapReduce平台上执行它们，包括Storm和Scalding.
* [coast](https://github.com/bkirwi/coast) [Scala]  - 一种在Samza之上构建DAG并提供完全一次语义的DSL.
* [Apache Beam](https://github.com/apache/beam) [Java]  - 统一模型和一组特定于语言的SDK，用于定义和执行数据处理工作流，以及数据提取和集成流程，支持企业集成模式（EIP）和域特定语言（DSL），由Google开源.
* [Esper](https://github.com/espertechinc/esper) [Java]  - 用于复杂事件处理（CEP）和事件序列分析的组件.
* [Streamparse](https://github.com/Parsely/streamparse) [Python]  - 允许您通过Apache Storm针对实时数据流运行Python代码.

### Data Pipeline

* [Apache Kafka](https://github.com/apache/kafka) [Scala / Java]  - 分布式，分区，复制的提交日志服务，它提供消息传递系统的功能，但具有独特的设计.
* [Apache Pulsar](https://github.com/apache/incubator-pulsar) [Java]  - 分布式pub-sub消息传递平台，具有非常灵活的消息传递模型和直观的客户端API.
* [metaq](https://github.com/killme2008/Metamorphosis) [Java]  - 淘宝网高可用，高性能的分布式邮件系统
* [nsq](https://github.com/nsqio/nsq) [Go]  - 旨在大规模运营的实时分布式消息传递平台，每天处理数十亿条消息.
* [NATS streaming](https://github.com/nats-io/nats-streaming-server) [Go]  - 快速磁盘支持的消息传递解决方案
* [camus](https://github.com/linkedin/camus) [Java]  -  Linkedin的Kafka  - &gt; HDFS管道.
* [databus](https://github.com/linkedin/databus) [Java]  -  Linkedin的源不可分的变更数据捕获系统.
* [flume](https://github.com/apache/flume) [Java]  - 分布式，可靠且可用的服务，用于高效收集，聚合和移动大量日志数据.
* [Redis Streams](http://antirez.com/news/114) -  Redis实现统一的日志结构
* [suro](https://github.com/Netflix/suro) [Java]  - 用于收集，聚合和分派大量应用程序事件（包括日志数据）的数据管道服务.
* [StreamSets Data Collector](https://github.com/streamsets/datacollector) [Java]  - 连续的大数据摄取基础设施，可读取和写入大量端点，包括S3，JDBC，Hadoop，Kafka，Cassandra等等.
* [LogDevice](https://logdevice.io/) [C ++]  -  Facebook的一个高性能分布式系统，用于使用日志结构流式传输和存储顺序数据

### Online Machine Learning 

* [streamDM](https://github.com/huawei-noah/streamDM) [Scala]  - 使用华为的Spark Streaming挖掘大数据流.
* [jubatus](http://jubat.us/en/) [C ++]  - 分布式处理框架和流媒体机器学习库.
* [Apache Samoa](https://github.com/apache/incubator-samoa) [Java]  - 分布式流机器学习（ML）框架，包含分布式流ML算法的编程抽象.
* [trident-ml](https://github.com/pmerienne/trident-ml) [Java]  - 基于Trident的实时在线机器学习库.
* [StormCV](https://github.com/sensorstorm/StormCV) [Java]  - 通过添加计算机视觉（CV）特定操作和数据模型，支持使用Apache Storm进行视频处理.
* [DataSketches](https://github.com/DataSketches/sketches-core) [Java]  - 来自雅虎的草图库！
* [StreamingBandit](https://github.com/Nth-iteration-labs/streamingbandit) [Python]  - 提供一个网络服务器，以快速设置和评估上下文多臂强盗（cMAB）问题的可能解决方案.

### Streaming SQL

* [pipelinedb](https://github.com/pipelinedb/pipelinedb) [C]  - 一个开源的关系数据库，它在流上连续运行SQL查询，逐步将结果存储在表中.
* [squall](https://github.com/epfldata/squall) [Java]  -  Squall在Storm之上执行SQL查询以进行在线处理.
* [StreamCQL](https://github.com/HuaweiBigData/StreamCQL) [Java]  - 实时计算系统上的连续查询语言.
* [KSQL](https://github.com/confluentinc/ksql) [Java]  -  Apache Kafka的流式SQL引擎.


### Benchmark

* [storm-benchmark](https://github.com/intel-hadoop/storm-benchmark) [Java]  - 一组测试Storm性能的基准测试.
* [storm-perf-test](https://github.com/yahoo/storm-perf-test) [Java]  - 简单的风暴性能/压力测试.
* [streaming-benchmarks](https://github.com/yahoo/streaming-benchmarks) [Java]  - 低延迟（流媒体）解决方案的基准测试，包括Apache Storm，Apache Spark，Apache Flink等.
* [flotilla](https://github.com/tylertreat/Flotilla) [Go]  - 用于扩大基准测试的自动消息队列编排.




### Toolkit

* [akka](https://github.com/akka/akka) [Scala]  - 用于在JVM上构建高度并发，分布式和弹性的消息驱动应用程序的工具包和运行时.
* [pulsar](https://github.com/quantmind/pulsar/) [Python]  - 基于Actor的事件驱动的Python并发框架.
* [aeron](https://github.com/real-logic/Aeron) [Java / C ++]  - 高效可靠的单播和多播消息传输.
* [StreamFlow](https://github.com/lmco/streamflow) [Java]  - 流处理工具，旨在帮助构建和监控处理工作流程.
* [samza-luwak](https://github.com/romseygeek/samza-luwak) [Java]  - 使用Luwak，一个基于Lucene构建的存储查询引擎，实现对流的全文搜索.
* [Turbine](https://github.com/Netflix/Turbine) [Java]  - 用于将服务器发送事件（SSE）JSON数据流聚合到单个流中的工具.

### Readings

1. [In-Stream Big Data Processing](https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/)
2. [The world beyond batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) 作者：Tyler Akidau. 
3. [Real Time Analytics: Algorithms and Systems (VLDB 2015)](http://www.vldb.org/pvldb/vol8/p2040-Kejariwal.pdf)


## License 

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png) 

获得许可 [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
