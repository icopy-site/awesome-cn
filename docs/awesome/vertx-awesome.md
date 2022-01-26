<div class="github-widget" data-repo="vert-x3/vertx-awesome"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Vert.x [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-logo.svg?sanitize=true" align="right" width="250">](http://vertx.io)

*Awesome Vert.x* is a list of awesome frameworks, libraries or other components for use with or that use
[Vert.x](https://github.com/eclipse/vert.x) 版本.

If you want your component to appear here send a pull request to this repository to add it.

请注意，我们不能保证此列表中所有内容的稳定性或生产价值，除非它具有
图标 <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px">
next to it. This icon means the component is part of the official
[Vert.x stack](https://vertx.io/docs/).

对于 Vert.x 版本 2 检查 [this page](https://github.com/vert-x3/vertx-awesome/blob/master/./vert-x2.md).



## Books

* [A gentle guide to asynchronous programming with Eclipse Vert.x for Java developers](http://vertx.io/docs/guide-for-java-devs/) Julien Ponge、Thomas Segismont 和 Julien Viet
* [Building Reactive Microservices in Java](https://developers.redhat.com/promotions/building-reactive-microservices-in-java/) 克莱门特·埃斯科菲
* [Vert.x in Action](https://www.manning.com/books/vertx-in-action) 朱利安·庞格

## Build tools

* [Vert.x Maven plugin](https://github.com/fabric8io/vertx-maven-plugin)
* [Vert.x Gradle plugin](https://plugins.gradle.org/plugin/io.vertx.vertx-plugin)
* [Vert.x Codegen Gradle plugin](https://github.com/bulivlad/vertx-codegen-plugin) - 一个 Gradle 插件，用于促进 Vert.x Java 项目的 codegen 使用.

## Web Frameworks

* [Vert.x Jersey](https://github.com/englishtown/vertx-jersey) - Create JAX-RS [Jersey](https://jersey.java.net/) Vert.x 中的资源.
* [Kovert](https://github.com/kohesive/kovert) - Kotlin + Vert.x Web 的隐形 REST 框架.
* [Handlers](https://github.com/spriet2000/vertx-handlers-http) - Open web framework for Vert.x.
* [QBit](https://github.com/advantageous/qbit) - REST 和 WebSocket 方法调用编组和反应库.
* [vertx-rest-storage](https://github.com/swisspush/vertx-rest-storage) - 文件系统或 redis 数据库中 REST 资源的持久性.
* [Jubilee](https://github.com/isaiah/jubilee) - 基于 Vert.x 3 构建的机架兼容 Ruby HTTP 服务器.
* [Knot.x](https://github.com/Cognifide/knotx) - 基于 Vert.x 3 构建的现代网站的高效和高性能集成平台.
* [Irked](https://github.com/GreenfieldTech/irked) - Vert.x 3 Web 和控制器框架的基于注释的配置.
* [REST.VertX](https://github.com/zandero/rest.vertx) - Lightweight JAX-RS (RestEasy) like annotation processor for Vert.x verticals.
* [Atmosphere Vert.x](https://github.com/Atmosphere/atmosphere-vertx) - Realtime Client Server Framework for the JVM, supporting WebSockets and Server Sent Events with Cross-Browser Fallbacks.
* [Vert.x Vaadin](https://github.com/mcollovati/vertx-vaadin) - 在 Vert.x 上运行 Vaadin 应用程序.
* [Serverx](https://github.com/lukehutch/serverx) - 允许您仅使用路由处理程序注释快速轻松地设置 Vert.x 驱动的服务器.
* [Cloudopt Next](https://github.com/cloudoptlab/cloudopt-next) - Cloudopt Next 是一个非常轻量级和现代的、基于 JVM 的全栈 kotlin 框架，旨在构建模块化、易于测试的 JVM 应用程序，支持 Java、Kotlin 语言，由最好的 Java 库和标准制作而成.
* [Donkey](https://github.com/AppsFlyer/donkey) - 为易于使用和性能而构建的现代 Clojure HTTP 服务器和客户端.
* [SCX](https://github.com/scx567888/scx) - 一个开放且易于使用的Web框架，大多数功能都基于注释.

## Authentication Authorisation


* [Vert.x-Pac4j](https://github.com/pac4j/vertx-pac4j) - Vert.x 认证/授权使用实现 [pac4j](http://www.pac4j.org/).

## Database Clients

*用于连接数据库的客户端*

* 关系数据库
  * [Reactive SQL Client](https://github.com/eclipse-vertx/vertx-sql-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 高性能反应式 SQL 客户端.
  * [JDBC](https://github.com/vert-x3/vertx-jdbc-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 围绕 JDBC 数据源的异步接口.
  * [MySQL / PostgreSQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous Client for MySQL/PostgreSQL.
  * [PostgreSQL](https://github.com/vietj/reactive-pg-client) - Reactive PostgreSQL Client.
  * [database](https://github.com/susom/database) - Oracle、PostgreSQL、SQL Server、HyperSQL 等的客户端，专为安全性、正确性和易用性而设计.
  * [jOOQ](https://github.com/jklingsporn/vertx-jooq) - 使用 jOOQ 执行类型安全、异步 SQL 并生成代码。
  * [jOOQx](https://github.com/zero88/jooqx) - 利用来自 `jOOQ DSL` 的类型安全 SQL 的强大功能，并使用来自 Vert.x 的反应式和非阻塞 SQL 驱动程序.

* NoSQL 数据库
  * [MongoDB](https://github.com/vert-x3/vertx-mongo-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 用于与 MongoDB 数据库交互的异步客户端.
  * [Redis](https://github.com/vert-x3/vertx-redis-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous API to interact with Redis.
  * [Cassandra](https://github.com/vert-x3/vertx-cassandra-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 一个允许应用程序与 Cassandra 服务交互的 Vert.x 客户端.
  * [Cassandra](https://github.com/englishtown/vertx-cassandra) - 与 Cassandra 和 Cassandra 映射交互的异步 API.
  * [OrientDB](https://github.com/cstamas/vertx-orientdb) - 非阻塞 OrientDB 服务器集成.
  * [Bitsy](https://github.com/cstamas/vertx-bitsy) - Non-blocking Bitsy Graph server integration.
  * [MarkLogic](https://github.com/etourdot/vertx-marklogic) - Marklogic 数据库服务器的异步客户端.
  * [SirixDB](https://github.com/sirixdb/sirix/tree/master/bundles/sirix-rest-api) - 非阻塞 SirixDB HTTP 服务器.
  * [DGraph](https://github.com/aesteve/vertx-dgraph-client)  - 关于如何构建符合 Vert.x gRPC 的客户端的示例. 这里定位 [dgraph](https://dgraph.io)
  * [RxFirestore](https://github.com/pjgg/rxfirestore) - Non-blocking Firestore SDK written in a reactive way.
  * [MongoDB](https://github.com/imrafaelmerino/vertx-mongodb-effect) - 纯功能和反应式 MongoDB 客户端 [Vert.x Effect](https://github.com/imrafaelmerino/vertx-mongodb-effect). Full support for retry, fallback and recovery operations.
  * [Aerospike](https://github.com/dream11/vertx-aerospike-client)  - 与 Aerospike 服务器交互的异步和非阻塞 API. 用途 [AerospikeClient's](https://github.com/aerospike/aerospike-client-java) async 内部命令并在 Vert.x 上下文中处理结果.

* [vertx-pojo-mapper](https://github.com/BraintagsGmbH/vertx-pojo-mapper) - MySQL 和 MongoDB 的非阻塞 POJO 映射.
* [vertx-mysql-binlog-client](https://github.com/guoyu511/vertx-mysql-binlog-client) - A Vert.x client for tapping into MySQL replication stream.

## Integration

* 服务器发送的事件
  * [jEaSSE](https://github.com/mariomac/jeasse)  - Java 简易 SSE.  SSE 的一个简单、轻量级的实现.
  * [vertx-sse](https://github.com/aesteve/vertx-sse) - Vert.x SSE implementation + event-bus SSE bridge.

* 邮件
  * [SMTP](https://github.com/vert-x3/vertx-mail-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 异步 SMTP 客户端.
  * [vertx-smtp-server](https://github.com/cinterloper/vertx-smtp-server) - SMTP 服务器桥接到 EventBus.

* 休息
  * [Vert.x REST Client](https://github.com/hubrick/vertx-rest-client) - A REST client for Vert.x with support for RxJava and request caching.
  * [Retrofit adapter for Vert.x](https://github.com/vietj/retrofit-vertx) - 一个高度可扩展的适配器，用于使用 Vert.x 进行改造.
  * [openapi4j adapter for Vert.x](https://github.com/openapi4j/openapi4j/tree/master/openapi-operation-adapters/openapi-operation-vertx) - OpenAPI 3 请求验证器和路由器工厂替代方案.
  * [Vert.x Effect HTTP client](https://github.com/imrafaelmerino/vertx-effect) - 纯功能和反应式 HTTP 客户端使用 [Vert.x Effect](https://github.com/imrafaelmerino/vertx-effect) with OAuth support and retry, fallback and recovery operations.

* File Server
  * [Vert.x TFTP Client](https://github.com/OneManCrew/vertx-tftp-client) - Vert.x 的 TFTP 客户端支持下载/上传文件.
* Messaging
  * [AMQP 1.0](https://github.com/vert-x3/vertx-amqp-bridge) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 使用 Vert.x 生产者和消费者 API 与 AMQP 1.0 服务器交互.
  * [MQTT](https://github.com/vert-x3/vertx-mqtt) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - Provides two different components: an MQTT server for handling all the MQTT communication and messages exchanges with clients and an MQTT client for sending and receiving messages against an MQTT broker.
  * [RabbitMQ](https://github.com/vert-x3/vertx-rabbitmq-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - RabbitMQ 客户端 (AMQP 0.9.1).
  * [Kafka Client](https://github.com/vert-x3/vertx-kafka-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 卡夫卡客户端.
  * [kafka](https://github.com/cyngn/vertx-kafka) - 用于消费和生产消息的 Kafka 客户端.
  * [Kafka Service](https://github.com/hubrick/vertx-kafka-service) - 具有重试逻辑的 Kafka 生产者和消费者.
  * [STOMP](https://github.com/vert-x3/vertx-stomp) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - Kafka 客户端和服务器.
  * [ZeroMQ](https://github.com/dano/vertx-zeromq) - ZeroMQ 事件总线桥.
  * [MQTT Broker](https://github.com/GruppoFilippetti/vertx-mqtt-broker) - MQTT Broker (MQTT ver. 3.1.1 and 3.1 compliant).
  * [Azure ServiceBus](https://github.com/TextBack/vertx-azure-servicebus) - Azure [ServiceBus](https://azure.microsoft.com/en-us/services/service-bus/) 生产者和消费者（完全异步，不使用 Microsoft Azure SDK）.
  * [AMQP 1.0 - Kafka bridge](https://github.com/rhiot/amqp-kafka-bridge) - Bridge for sending/receiving messages to/from Apache Kafka using the AMQP 1.0 protocol.
  * [Vert.x Kafka Client](https://github.com/vert-x3/vertx-kafka-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 用于从/向 Apache Kafka 集群读取和发送消息的 Apache Kafka 客户端.
  * [The White Rabbit](https://github.com/viartemev/the-white-rabbit) - An asynchronous RabbitMQ (AMQP) client based on Kotlin coroutines.
  * [WAMP Broker](https://github.com/i22-digitalagentur/vertx-wamp) - 一个可以嵌入到 Vert.x 应用程序中的 WAMP 代理.

* JavaEE
  * [JCA adaptor](https://github.com/vert-x3/vertx-jca) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - Java Connector Architecture Adaptor for the Vert.x event bus.
  * [Weld](https://github.com/weld/weld-vertx) - 将 CDI 编程模型引入 Vert.x 生态系统（将 CDI 观察者方法注册为 Vert.x 消息消费者、CDI 驱动的 Verticles、以声明性方式定义路由等）.

* Meteor
  * [Meteor](https://github.com/jmusacchio/vertxbus/) - 通过 Vert.x 事件总线支持 Meteor 集成.

* 指标
  * [Hawkular metrics](https://github.com/tsegismont/vertx-monitor) - [Hawkular](http://www.hawkular.org/) Vert.x Metrics SPI 的实现.
  * [DropWizard metrics](https://github.com/vert-x3/vertx-dropwizard-metrics) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 使用 DropWizard 指标的指标实施.
  * [Micrometer metrics](https://github.com/vert-x3/vertx-micrometer-metrics) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 使用千分尺指标的指标实施.
  * [OpenTsDb Metrics](https://github.com/cyngn/vertx-opentsdb) - [OpenTsDb](http://opentsdb.net/) Vert.x 的指标客户端.
  * [Bosun Monitoring](https://github.com/cyngn/vertx-bosun) - [Bosun](https://bosun.org/) Vert.x 的客户端库.

* Netflix - Hystrix
  * [Hystrix Metrics Stream](https://github.com/kennedyoliveira/hystrix-vertx-metrics-stream.git) - 从 Vert.x 应用程序发出 Hystrix Dashboard 的指标 [Hystrix](https://github.com/Netflix/Hystrix).

* Dart
  * [Vert.x Dart SockJS](https://github.com/wem/vertx-dart-sockjs) - [Dart](https://www.dartlang.org/) 整合为 [Vert.x SockJS bridge](http://vertx.io/docs/vertx-web/java/#_sockjs_event_bus_bridge) 和使用 dart:js 的普通 SockJS.

* 推送通知
  * [Onesignal](https://github.com/jklingsporn/vertx-push-onesignal) - 从您的 Vert.x 应用程序向（移动/网络）应用程序发送推送通知 [OneSignal](https://onesignal.com/).

* CNCF 云事件
  * [CloudEvents.io Java SDK](https://github.com/cloudevents/sdk-java) - 发送和接收 [CloudEvents](https://cloudevents.io/) 使用 [Vert.x HTTP Transport](https://github.com/cloudevents/sdk-java/blob/master/http/vertx/README.md) 对于云事件.

## Middleware

* [Apache Camel](https://github.com/apache/camel/blob/master/components/camel-vertx/src/main/docs/vertx-component.adoc) - [Apache Camel](http://camel.apache.org/) 用于将 Camel 与 Vert.x 事件总线桥接的组件.
* [Gateleen](https://github.com/swisspush/gateleen) - Middleware library based on Vert.x to build advanced JSON/REST communication servers.
* [Gravitee.io](https://gravitee.io) - An OSS API Platform including an API Gateway and an OAuth2 / OIDC authorization server based on Vert.x Core / Vert.x Web and other modules.
* [API Framework](https://github.com/vinscom/api-framework)  - 基于 Vert.x 和 Glue 的微服务框架消除了独立应用程序和无服务应用程序之间的区别. 所有服务都可以在独立服务器中运行，但如果需要，可以使用相同的代码库将任何服务作为无服务器应用程序运行.


## Language Support

*对 Vert.x 的编程语言支持*

* [Python](https://github.com/vert-x3/vertx-lang-python) - Python 支持.
* [EcmaScript](https://github.com/reactiverse/es4x) - EcmaScript >=6 (JavaScript) support.
* [Php](https://github.com/vert-x-cn/vertx-lang-jphp) - PHP 支持.

*语言扩展*

* [Grooveex](https://github.com/aesteve/grooveex) - Syntactic sugar + utilities (DSL builders, etc.) on top of [vertx-lang-groovy](https://github.com/vert-x3/vertx-lang-groovy).

## Reactive

* [vertx-util](https://github.com/cyngn/vertx-util) - Light weight promises & latches for Vert.x.
* [QBit](https://github.com/advantageous/qbit)  - 在 Vert.x Async Callbacks 中轻松运行的异步类型 actor-like lib. 回调管理.
* [VxRifa](https://nsforth.github.io/vxrifa) - Vert.X 的实用程序库，允许在通过 EventBus 进行通信时使用强类型接口.
* [Vert.x Effect](https://github.com/imrafaelmerino/vertx-effect)  - 基于 IO Monad 的纯函数式和反应式库，用于实现任何复杂的流程. 完全支持重试、回退和恢复操作. 

## Sync Thread Non Block

* [Sync](https://github.com/vert-x3/vertx-sync) - Synchronous but non-OS-thread-blocking verticles.

## Vert.x Event Bus Clients

*将应用程序连接到 Vert.x 事件总线的客户端*

* [C++11](https://github.com/julien3/vertxbuspp) - C++11 事件总线客户端.
* [Java](https://github.com/saffron-technology/vertx-eventbusbridge) - vertxbus.js 的 Java 实现.
* [Java](https://github.com/abdlquadri/vertx-eventbus-java) - Java 和 Android 事件总线客户端.
* [Java](https://github.com/danielstieger/javaxbus) - Simple Java Event Bus Client using plain TCP socket I/O.
* [CLI](https://github.com/cinterloper/vxc) - Vert.x 事件总线的命令行二进制客户端 - JSON 中的管道，发出 JSON.
* [Swift](https://github.com/tobias/vertx-swift-eventbus) - 事件总线客户端 [Apple's Swift](https://swift.org) 使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Python](https://github.com/jaymine/TCP-eventbus-client-Python) - 使用 Python 的事件总线客户端 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C#](https://github.com/jaymine/TCP-eventbus-client-C-Sharp) - Event bus client for C# using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C](https://github.com/jaymine/TCP-eventbus-client-C) - 使用 C99 的事件总线客户端 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Go](https://github.com/jponge/vertx-go-tcp-eventbus-bridge)- Event bus client for Go-lang using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Smalltalk](https://github.com/mumez/VerStix)- 事件总线客户端 [Pharo Smalltalk](http://pharo.org/) 使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Java](https://github.com/nielsbaloe/vertxui/tree/master/vertxui-core/src/main/java/live/connector/vertxui/client/transport) - Event bus support in JavaScript through Java code.
* [Elixir](https://github.com/PharosProduction/ExVertx) - 使用 TCP 套接字的 Elixir 应用程序的事件总线支持.
* [Rust](https://github.com/aesteve/vertx-eventbus-client-rs) - 通过 TCP 用于 Rust 应用程序的事件总线客户端.

## Vert.x Event Bus Extensions

* [Eventbus Service](https://github.com/wowselim/eventbus-service) - Code generator for type-safe event bus communication via simple Kotlin interfaces.

## Cluster Managers

*Implementations of the Vert.x cluster manager SPI*

* [JGroups Cluster Manager](https://github.com/vert-x3/vertx-jgroups) - JGroups 集群管理器.
* [Atomix Cluster Manager](https://github.com/atomix/atomix-vertx) - 一个 [Atomix](http://atomix.io) Vert.x 3 的基于集群管理器的实现.
* [Consul Cluster Manager](https://github.com/reactiverse/consul-cluster-manager) - 领事集群管理器.

## Cloud Support

* [S3](https://github.com/hubrick/vertx-s3-client) - A fully functional Vert.x client for S3.
* [AWS SDK](https://github.com/reactiverse/aws-sdk) - 将 AWS Java SDK v2（异步）与 Vert.x 结合使用

## Docker


## Microservices

* [Vert.x GraphQL Service Discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - [GraphQL](http://graphql.org/) 服务发现和查询您的 Vert.x 微服务.
* [Resilience4j](https://github.com/resilience4j/resilience4j)  - Resilience4j 是为 Java8 和函数式编程设计的容错库.  Resilience4j 提供了用于断路器、速率限制、隔板、自动重试、响应缓存和度量测量的模块.
* [Autonomous Services](https://github.com/mikand13/autonomous-services)  - 用于创建自治服务的工具包. 一种利用 vert.x 和 nannoq-tools 提供基于事件的反应式架构的架构，无需集中组件，既不用于通信也不用于数据，提供跨架构的理论上的线性可扩展性.
* [Apache ServiceComb Java Chassis](https://github.com/apache/servicecomb-java-chassis) - ServiceComb Java Chassis is a Software Development Kit (SDK) for rapid development of microservices in Java, providing service registration, service discovery, dynamic routing, and service management features.

## Search Engines

* [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service) - 垂直 x 3 [Elasticsearch](https://www.elastic.co/) service with event bus proxying.
* [Vert.x Elasticsearch Service (redesign)](https://github.com/hubrick/vertx-elasticsearch-service) - 垂直 x 3 [Elasticsearch](https://www.elastic.co/) service with event bus proxying. Redesign of the [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service) . 在事件总线上大量使用 DTO，不再使用 JsonObjects. 添加了对 ES 插件的支持.
* [Vert.x Solr Service](https://github.com/englishtown/vertx-solr-service) - 带有事件总线代理的 Vert.x 3 Solr 服务.

## Template Engines

* [KorTE Template Engine](https://github.com/korlibs/korte) - Kotlin 模板引擎类似于 Twig/Django/Liquid，支持调用 Kotlin 挂起方法.

## Service Factory

* [Node.js Service Factory](https://github.com/mellster2012/vertx-nodejs-service-factory) - Vert.x Node.js 服务工厂.
* [Eclipse SISU Service Factories](https://github.com/cstamas/vertx-sisu) - Vert.x integration with [Eclipse SISU](https://www.eclipse.org/sisu/) DI 容器为 `vertx-service-factory` 和 `vertx-maven-service-factory` 提供替代方案.

## Config

* [Vert.x Config AWS SSM Store](https://github.com/Finovertech/vertx-config-aws-ssm) - 一个 [config store](http://vertx.io/docs/vertx-config/java/) implementation for retrieving configuration values from the [AWS EC2 SSM Parameter Store](https://aws.amazon.com/ec2/systems-manager/parameter-store/).
* [Vert.x Boot](https://github.com/jponge/vertx-boot) - 从 HOCON 配置部署 Verticle.

## Dependency Injection

* [Vert.x Guice](https://github.com/englishtown/vertx-guice) - 用于 Guice 依赖注入的 Vert.x 垂直工厂.
* [Vert.x HK2](https://github.com/englishtown/vertx-hk2) - 用于 HK2 依赖注入的 Vert.x 垂直工厂.
* [Spring Vert.x Extension](https://github.com/amoAHCP/spring-vertx-ext) - 用于 Spring DI 注入的 Vert.x 垂直工厂.
* [Vert.x Beans](https://github.com/rworsnop/vertx-beans) - 将 Vert.x 对象作为 bean 注入到您的 Spring 应用程序中.
* [QBit](https://github.com/advantageous/qbit) - QBit works with Spring DI and Spring Boot (and of course Vert.x). Allows you to use QBit, Vert.x, Spring DI and Spring Boot in the same application.
* [Vert.x Eclipse SISU](https://github.com/cstamas/vertx-sisu) - Vert.x integration with [Eclipse SISU](https://www.eclipse.org/sisu/) DI container.
* [Vert.x Spring Verticle Factory](https://github.com/juanavelez/vertx-spring-verticle-factory) - 一个 Vert.x Verticle Factory，它使用 Spring 来获取和配置 Verticle.
* [Glue](https://github.com/vinscom/glue)  - 基于 Java 和 Vert.x 的应用程序的经过验证和自以为是的编程和配置模型. 受 ATG Nucleus 启发，使用简单的属性文件提供强大的层基础配置管理.

## Testing

* [Vert.x WireMongo](https://github.com/noenv/vertx-wiremongo) - Vert.x 的轻量级 MongoDB 模拟

## Development Tools

* [Vert.x health check](https://github.com/vert-x3/vertx-health-check) - Allows for remote health checking in Vert.x projects.
* [Vert.x Hot](https://github.com/dazraf/vertx-hot) - A Maven plugin for the hot-deploy of Maven Vert.x projects.
* [slush-vertx](https://www.npmjs.com/package/slush-vertx) - 用于不同语言和构建工具的模板驱动的 Vert.x 项目生成器.
* [Vert.x for Visual Studio Code](https://github.com/pmlopes/VertxSnippet)  - 适用于 Vert.x 的 Visual Studio Code（多语言）插件. 也可从 [Marketplace](https://marketplace.visualstudio.com/items?itemName=pmlopes.vertxsnippet).
* [Vert.x Starter](http://www.jetdrone.xyz/vertx-starter/) - Vert.x 应用程序的基于浏览器的项目启动器和项目模板.
* [Vert.x LiveReload](https://github.com/ybonnel/vertx-livereload) - 用于 Vert.x 应用程序的简单 livereload 服务器.
* [openapi-generator](https://github.com/OpenAPITools/openapi-generator) - OpenAPI 生成器允许根据 OpenAPI 规范（v2、v3）自动生成 API 客户端库（SDK 生成）、服务器存根、文档和配置.

## Miscellaneous

* [Vert.x Child Process](https://github.com/vietj/vertx-childprocess) - 从 Vert.x 生成子进程.
* [vertx-redisques](https://github.com/swisspush/vertx-redisques) - Vert.x 的高度可扩展的 redis-persistent 排队系统.
* [Simple File Server](https://github.com/pitchpoint-solutions/sfs) - 一个兼容 OpenStack Swift 的分布式对象存储服务器，可以使用使用 Vert.x 实现的最少资源来服务和安全地存储数十亿个大小文件.
* [Vert.x Boot](https://github.com/jponge/vertx-boot) - 从 HOCON 配置部署 Verticle.
* [GDH](https://github.com/maxamel/GDH) - 基于 Vert.x 构建的通用 Diffie-Hellman 密钥交换 Java 库.

## Distribution


## Examples

* [Vert.x feeds](https://github.com/aesteve/vertx-feeds) - 使用 Vert.x、Gradle、MongoDB、Redis、Handlebars 模板、AngularJS、事件总线和 SockJS 构建的 RSS 聚合器示例.
* [Vert.x Markdown service](https://github.com/aesteve/vertx-markdown-service) - Example on how to use [service-proxy](https://github.com/vert-x3/vertx-service-proxy) 与 Gradle.
* [Example using event bus and service proxies to connect vertx and node](https://github.com/advantageous/vertx-node-ec2-eventbus-example) - Step by step example with wiki description showing how to connect Vert.x and Node using event bus and service proxies.
* [Vert.x Todo-Backend implementation](https://github.com/aesteve/todo-backend-vertx)  - Todo MVC 后端的纯 Java 8 实现. 使用 Vert.x LocalMap 进行存储.
* [Kotlin Todo-Backend implementation](https://github.com/aesteve/vertx-kotlin-todomvc) - Todo MVC 后端的 Kotlin 实现.
* [Scala Todo-Backend implementation](https://github.com/aesteve/vertx-scala-todomvc) - Todo MVC 后端的 Scala 实现.
* [Grooveex Todo-Backend implementation](https://github.com/aesteve/todo-backend-grooveex) - 使用 Vert.x + Groovy + 一些语法糖 + DSL 路由工具的 Todo MVC 后端实现.
* [Vert.x Gradle Starter](https://github.com/yyunikov/vertx-gradle-starter) - Java 8 入门应用程序，带有使用 Vert.x 和 Gradle 构建系统、配置文件配置和 SLF4J 的示例.
* [Vert.x Gentics Mesh Example](https://github.com/gentics/mesh-vertx-example) - 关于如何使用 Gentics Mesh 和车把构建基于模板的 Web 服务器的示例.
* [HTTP/2 showcase](https://github.com/aesteve/http2-showcase) - 一个简单的演示，展示了 HTTP/2 如何在涉及巨大延迟时显着改善用户体验.
* [Vert.x Music Store](https://github.com/tsegismont/vertx-musicstore) - 关于如何使用 RxJava 构建 Vert.x 应用程序的示例应用程序.
* [Crabzilla](https://github.com/crabzilla/crabzilla)  - 又一个事件溯源实验. 一个探索 Vert.x 以开发 Event Sourcing / CQRS 应用程序的项目.
* [Vert.x PostgreSQL Starter](https://github.com/BillyYccc/vertx-postgresql-starter) - A starter to build a monolithic CRUD RESTful Web Service with Vert.x stack and PostgreSQL.
* [Cloud Foundry](https://github.com/amdelamar/vertx-cloudfoundry) - 用于部署到的示例 Vert.x [Cloud Foundry](https://www.cloudfoundry.org/) 服务提供者.
* [Knative](https://github.com/knative/docs/tree/master/serving/samples/helloworld-vertx) - An example application on how to use [Reactive Extensions Vert.x](https://github.com/vert-x3/vertx-rx) 和 [Knative](https://github.com/knative).
* [Starter Single Verticle API](https://github.com/jgarciasm/ssv-api) - REST API Starter 和项目模板可随时部署，其中包含大量管道代码、示例和文档，可在几乎不了解 vert.x 且不浪费任何时间的情况下快速开发 API.
## Deployment

* [Vert.x Deploy Application](https://github.com/msoute/vertx-deploy-tools) - （无缝）部署到基于 AWS 的 Vert.x 应用程序集群.

## Utilities

* [Chime](https://github.com/LisiLisenok/Chime) - Time scheduler working on Vert.x event bus allowing for scheduling with _cron-style_ and _interval_ timers.
* [Vert.x Cron](https://github.com/diabolicallabs/vertx-cron)  - 安排具有 cron 规范的事件. 具有事件总线和 Observable 版本.
* [Vert.x CronUtils](https://github.com/NoEnv/vertx-cronutils) - An abstraction of cron-utils for the vertx scheduler. Unix, Cron4j and Quartz style expressions are supported.
* [Vert.x Scheduler](https://github.com/zero88/vertx-scheduler) - A lightweight plugable scheduler based on plain Vert.x core without any external libs for scheduling with _cron-style_ and _interval_ timers with a detail _monitor_ on both sync and async task.
* [Vert.x POJO config](https://github.com/aesteve/vertx-pojo-config) - Allows for mapping between standard JSON configuration and a (type-safe) configuration Java bean. Also allows the configuration bean to be validated through JSR 303.
* [Vert.x Async](https://github.com/gchauvet/vertx-async) - 将 caolan/async nodejs 模块移植到 Vert.x 框架，为常见的异步模式提供辅助方法.
* [Vert.x JOLT](https://github.com/lusoalex/vertx-jolt)  - 基于原始 bazaarvoice JOLT 项目的 JSON 到 JSON 转换工具. 有助于将不同的 json 结构转换为预期的 json 格式.
* [Vert.x Dependent Verticle Deployer](https://github.com/juanavelez/vertx-dependent-verticle-deployer) - 一个 Vert.x Verticle，用于部署 Verticle 及其依赖的 Verticle.
* [Vert.x Dataloader](https://github.com/engagingspaces/vertx-dataloader) - Java port of Facebook Dataloader for Vert.x. Efficient batching and caching for your data layer.
* [Vert.x Util](https://github.com/juanavelez/vertx-util) - Vert.x 实用方法的集合.
* [Vert.x Web Accesslog](https://github.com/romanpierson/vertx-web-accesslog) - Just a simple handler to be used in Vert.x Web to generate access logs.
* [Vert.x GraphQL Utils](http://github.com/tibor-kocsis/vertx-graphql-utils) - A route handler and Vert.x compatible interfaces to handle GraphQL queries in Vert.x and Vert.x Web.
* [Nannoq-Tools](https://noriginmedia.github.io/nannoq-tools/) - Nannoq-Tools is a toolkit for constructing robust, scalable and distributed applications leveraging Vert.x including modules for authentication, cluster management, Firebase Cloud Messaging, DynamoDB, fully generic queries, REST, and more.
* [Contextual logging](https://github.com/reactiverse/reactiverse-contextual-logging) - Mapped Diagnostic Context (MDC) that works with the Vert.x event-loop model.

## Presentations

- [Vert.x Youtube channel](https://www.youtube.com/channel/UCGN6L3tRhs92Uer3c6VxOSA)

## Community

- [User Group](https://groups.google.com/forum/?fromgroups#!forum/vertx) - Discuss all user issues related to *using* Vert.x.
- [Developer Group](https://groups.google.com/forum/?fromgroups#!forum/vertx-dev) - A group for Vert.x core *developers* and *contributors*.
- [Discord Server](https://discord.gg/KzEMwP2) - 讨论任何与 Vert.x 相关的话题.
- [Issues](https://github.com/vert-x3/issues/issues) - Vert.x core issue tracker.
- [Wiki](https://github.com/vert-x3/wiki/wiki) - 包含有关 Vert.x 的有用信息.
- [Blog](http://vertx.io/blog/) - 包含许多教程和其他信息的官方 Vert.x 博客.

## Articles

- [Going reactive with Eclipse Vert.x and RX Java ](https://blogs.oracle.com/javamagazine/going-reactive-with-eclipse-vertx-and-rxjava)
- [First Steps With Vert.x and Infinispan - Part 2: PUSH API ](https://dzone.com/articles/first-steps-with-vertx-and-infinispan-push-api-par)
- [First Steps With Vert.x and Infinispan - Part 1: REST API ](https://dzone.com/articles/first-steps-with-vertx-and-infinispan-rest-api)
- [Location Transparency With Vert.x ](https://dzone.com/articles/location-transparency-with-vertx)
- [Reactive Microservices and Service Discovery with Vert.x ](https://dzone.com/articles/reactive-microservices-and-service-discovery-with)
- [https://dzone.com/articles/vertx-330-development-automation](https://dzone.com/articles/vertx-330-development-automation)
- [Vert.x 3.3.0 Features Enhanced Networking Microservices, Testing and More ](https://www.infoq.com/news/2016/06/Vert.x-3.3.0-release-features)
- [Launching Vert.x Dynamically](https://dzone.com/articles/vertx-launcher)
- [Secure Your Vertx 3 App With Pac4j](https://dzone.com/articles/secure-your-vertx)
- [Interview with Tim Fox About Vert.x 3, the Original Reactive, Microservice Toolkit for the JVM ](http://www.infoq.com/articles/vertx-3-tim-fox)

## Tutorials

- [Vert.x - From zero to (micro-) hero](http://escoffier.me/vertx-hol)
- [Introduction to Vert.x](https://vertx.io/get-started/)

## Social events / Meetups

- [Amsterdam/The Netherlands](https://www.meetup.com/Vert-x-NL)
- [Paris](https://www.meetup.com/Paris-vert-x-Meetup/)

## Front-End

* [VertxUI](https://github.com/nielsbaloe/vertxui) - A pure Java front-end toolkit with descriptive fluent views-on-models, POJO traffic, JUnit testing on the virtual DOM or mixed-language on a real DOM, and more.

## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/vert-x3/vertx-awesome/blob/master/CONTRIBUTING.md) 第一的.
