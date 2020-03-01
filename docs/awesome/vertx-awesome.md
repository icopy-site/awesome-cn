<div class="github-widget" data-repo="vert-x3/vertx-awesome"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Vert.x [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/logo-sm.png" align="right" width="250">](http://vertx.io)

* Awesome Vert.x *是一系列令人敬畏的框架，库或其他组件，它们可以一起使用或
[Vert.x](https://github.com/eclipse/vert.x) 版本3.

如果要在此处显示组件，请向该存储库发送拉取请求以将其添加.

请注意，我们无法保证此清单上所有内容的稳定性或生产价值，除非它具有
图标 <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px">
 在它的旁边.  此图标表示该组件是官方的一部分
[Vert.x stack](https://vertx.io/docs/).

对于Vert.x版本2，请检查 [this page](https://github.com/vert-x3/vertx-awesome/blob/master/./vert-x2.md).



## Books

* [A gentle guide to asynchronous programming with Eclipse Vert.x for Java developers](http://vertx.io/docs/guide-for-java-devs/) 朱利安·蓬吉，托马斯·塞吉斯蒙特和朱利安·越
* [Building Reactive Microservices in Java](https://developers.redhat.com/promotions/building-reactive-microservices-in-java/) 由克莱门特·埃斯科菲耶（ClémentEscoffier）
* [Vert.x in Action](https://www.manning.com/books/vertx-in-action) 通过朱利安蓬吉

## Build tools

* [Vert.x Maven plugin](https://github.com/fabric8io/vertx-maven-plugin)
* [Vert.x Gradle plugin](https://plugins.gradle.org/plugin/io.vertx.vertx-plugin)
* [Vert.x Codegen Gradle plugin](https://github.com/bulivlad/vertx-codegen-plugin) -Gradle插件，可简化Vert.x Java项目的代码生成用法

## Web Frameworks

* [Vert.x Jersey](https://github.com/englishtown/vertx-jersey) -创建JAX-RS [Jersey](https://jersey.java.net/) Vert.x中的资源.
* [Kovert](https://github.com/kohesive/kovert) -Kotlin + Vert.x Web的不可见REST框架.
* [Handlers](https://github.com/spriet2000/vertx-handlers-http) -Vert.x的开放式Web框架.
* [QBit](https://github.com/advantageous/qbit) -REST和WebSocket方法调用封送处理和反应式库.
* [vertx-rest-storage](https://github.com/swisspush/vertx-rest-storage) -文件系统或redis数据库中REST资源的持久性.
* [Jubilee](https://github.com/isaiah/jubilee) -建立在Vert.x 3上的机架兼容Ruby HTTP服务器.
* [Knot.x](https://github.com/Cognifide/knotx) -建立在Vert.x 3上的现代网站的高效，高性能集成平台.
* [Vert.x Jspare](https://github.com/jspare-projects/vertx-jspare) -使用Jspare Framework改善Vert.x 3体验.
* [Irked](https://github.com/GreenfieldTech/irked) -Vert.x 3 Web和控制器框架的基于注释的配置.
* [REST.VertX](https://github.com/zandero/rest.vertx) -轻量级的JAX-RS（RestEasy），例如Vert.x垂直版本的注释处理器.
* [Atmosphere Vert.x](https://github.com/Atmosphere/atmosphere-vertx) -用于JVM的实时客户端服务器框架，支持WebSocket和具有跨浏览器后备功能的服务器发送事件.
* [Vert.x Vaadin](https://github.com/mcollovati/vertx-vaadin) -运行我在Vert.x上寻找应用程序.
* [Serverx](https://github.com/lukehutch/serverx) -允许您仅使用路由处理程序注释即可快速轻松地设置支持Vert.x的服务器.

## Authentication Authorisation


* [Vert.x-Pac4j](https://github.com/pac4j/vertx-pac4j) -使用以下工具实施Vert.x身份验证/授权 [pac4j](http://www.pac4j.org/).

## Database Clients

*用于连接数据库的客户端*

*关系数据库
  * [Reactive SQL Client](https://raw.githubusercontent.com/eclipse-vertx/vertx-sql-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -高性能反应式SQL客户端.
  * [JDBC](https://raw.githubusercontent.com/vert-x3/vertx-jdbc-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -围绕JDBC数据源的异步接口.
  * [MySQL / PostgreSQL](https://raw.githubusercontent.com/vert-x3/vertx-mysql-postgresql-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -MySQL / PostgreSQL的异步客户端.
  * [PostgreSQL](https://github.com/vietj/reactive-pg-client) -反应性PostgreSQL客户端.
  * [database](https://github.com/susom/database) -面向Oracle，PostgreSQL，SQL Server，HyperSQL等的客户端，旨在确保安全性，正确性和易用性.
  * [jOOQ](https://github.com/jklingsporn/vertx-jooq) -执行类型安全的异步SQL，并使用jOOQ生成代码.

* NoSQL数据库
  * [MongoDB](https://raw.githubusercontent.com/vert-x3/vertx-mongo-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -用于与MongoDB数据库进行交互的异步客户端.
  * [Redis](https://raw.githubusercontent.com/vert-x3/vertx-redis-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -与Redis进行交互的异步API.
  * [Cassandra](https://raw.githubusercontent.com/vert-x3/vertx-cassandra-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -Vert.x客户端，允许应用程序与Cassandra服务进行交互.
  * [Cassandra](https://github.com/englishtown/vertx-cassandra) -与Cassandra和Cassandra映射进行交互的异步API.
  * [OrientDB](https://github.com/cstamas/vertx-orientdb) -无阻塞OrientDB服务器集成.
  * [Bitsy](https://github.com/cstamas/vertx-bitsy) -非阻塞Bitsy Graph服务器集成.
  * [MarkLogic](https://github.com/etourdot/vertx-marklogic) -Marklogic数据库服务器的异步客户端.
  * [SirixDB](https://github.com/sirixdb/sirix/tree/master/bundles/sirix-rest-api) -非阻塞SirixDB HTTP服务器.
  * [DGraph](https://github.com/aesteve/vertx-dgraph-client)  -有关如何构建Vert.x gRPC兼容客户端的示例.  此处定位 [dgraph](https://dgraph.io)
  * [RxFirestore](https://github.com/pjgg/rxfirestore) -以反应方式编写的非阻塞Firestore SDK.

* [vertx-pojo-mapper](https://github.com/BraintagsGmbH/vertx-pojo-mapper) -MySQL和MongoDB的非阻塞POJO映射.
* [vertx-mysql-binlog-client](https://github.com/guoyu511/vertx-mysql-binlog-client) -一个Vert.x客户端，用于接入MySQL复制流.

## Integration

*服务器发送的事件
  * [jEaSSE](https://github.com/mariomac/jeasse)  -Java Easy SSE.  SSE的简单，轻量级实现.
  * [vertx-sse](https://github.com/aesteve/vertx-sse) -Vert.x SSE实现+事件总线SSE桥.

*邮件
  * [SMTP](https://raw.githubusercontent.com/vert-x3/vertx-mail-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -异步SMTP客户端.
  * [vertx-smtp-server](https://github.com/cinterloper/vertx-smtp-server) -桥接到EventBus的SMTP服务器.

*休息
  * [Vert.x REST Client](https://github.com/hubrick/vertx-rest-client) -Vert.x的REST客户端，支持RxJava和请求缓存.
  * [Retrofit adapter for Vert.x](https://github.com/vietj/retrofit-vertx) -用于Vert.x改造的高度可扩展适配器.
  * [openapi4j adapter for Vert.x](https://github.com/openapi4j/openapi4j/tree/master/openapi-operation-adapters/openapi-operation-vertx) -OpenAPI 3请求验证器和路由器工厂替代品.

*文件服务器
  * [Vert.x TFTP Client](https://github.com/OneManCrew/vertx-tftp-client) -Vert.x的TFTP客户端支持下载/上传文件.
*消息
  * [AMQP 1.0](https://raw.githubusercontent.com/vert-x3/vertx-amqp-bridge) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -使用Vert.x Producer和Consumer API与AMQP 1.0服务器进行交互.
  * [MQTT](https://raw.githubusercontent.com/vert-x3/vertx-mqtt) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -提供两个不同的组件：用于处理与客户端的所有MQTT通信和消息交换的MQTT服务器，以及用于针对MQTT代理发送和接收消息的MQTT客户端.
  * [RabbitMQ](https://raw.githubusercontent.com/vert-x3/vertx-rabbitmq-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -RabbitMQ客户端（AMQP 0.9.1）.
  * [Kafka Client](https://raw.githubusercontent.com/vert-x3/vertx-kafka-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -Kafka客户.
  * [kafka](https://github.com/cyngn/vertx-kafka) -Kafka客户端，用于消费和产生消息.
  * [Kafka Service](https://github.com/hubrick/vertx-kafka-service) -具有重试逻辑的Kafka生产者和消费者.
  * [STOMP](https://raw.githubusercontent.com/vert-x3/vertx-stomp) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -Kafka客户端和服务器.
  * [ZeroMQ](https://github.com/dano/vertx-zeromq) -ZeroMQ事件总线桥.
  * [MQTT Broker](https://github.com/GruppoFilippetti/vertx-mqtt-broker) -MQTT Broker（符合MQTT 3.1.1和3.1版）.
  * [Azure ServiceBus](https://github.com/TextBack/vertx-azure-servicebus) -天蓝色 [ServiceBus](https://azure.microsoft.com/en-us/services/service-bus/) 生产者和使用者（完全异步，不使用Microsoft Azure SDK）.
  * [AMQP 1.0 - Kafka bridge](https://github.com/rhiot/amqp-kafka-bridge) -使用AMQP 1.0协议向Apache Kafka发送消息/从Apache Kafka接收消息的桥.
  * [Vert.x Kafka Client](https://raw.githubusercontent.com/vert-x3/vertx-kafka-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -Apache Kafka客户端，用于从Apache Kafka集群读取消息或向Apache Kafka集群发送消息.
  * [The White Rabbit](https://github.com/viartemev/the-white-rabbit) -基于Kotlin协程的异步RabbitMQ（AMQP）客户端.

* JavaEE
  * [JCA adaptor](https://raw.githubusercontent.com/vert-x3/vertx-jca) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -用于Vert.x事件总线的Java连接器体系结构适配器.
  * [Weld](https://github.com/weld/weld-vertx) -将CDI编程模型引入Vert.x生态系统（将CDI观察者方法注册为Vert.x消息使用者，CDI支持的Verticles，以声明的方式定义路由等）.

*流星
  * [Meteor](https://github.com/jmusacchio/vertxbus/) -通过Vert.x事件总线的流星集成支持.

*指标
  * [Hawkular metrics](https://github.com/tsegismont/vertx-monitor) - [Hawkular](http://www.hawkular.org/) Vert.x Metrics SPI的实现.
  * [DropWizard metrics](https://raw.githubusercontent.com/vert-x3/vertx-dropwizard-metrics) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -使用DropWizard指标的指标实现.
  * [Micrometer metrics](https://raw.githubusercontent.com/vert-x3/vertx-micrometer-metrics) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -使用千分尺指标的指标实施.
  * [OpenTsDb Metrics](https://github.com/cyngn/vertx-opentsdb) - [OpenTsDb](http://opentsdb.net/) Vert.x的指标客户端.
  * [Bosun Monitoring](https://github.com/cyngn/vertx-bosun) - [Bosun](https://bosun.org/) Vert.x的客户端库.

* Netflix-Hystrix
  * [Hystrix Metrics Stream](https://github.com/kennedyoliveira/hystrix-vertx-metrics-stream.git) -通过Vert.x应用程序为Hystrix仪表板发出指标 [Hystrix](https://github.com/Netflix/Hystrix).

*飞镖
  * [Vert.x Dart SockJS](https://github.com/wem/vertx-dart-sockjs) - [Dart](https://www.dartlang.org/) 整合 [Vert.x SockJS bridge](http://vertx.io/docs/vertx-web/java/#_sockjs_event_bus_bridge) 以及使用dart：js的普通SockJS.

* 推送通知
  * [Onesignal](https://github.com/jklingsporn/vertx-push-onesignal) -通过以下方式从您的Vert.x应用程序向（移动/网络）应用程序发送推送通知： [OneSignal](https://onesignal.com/).

* CNCF CloudEvents
  * [CloudEvents.io Java SDK](https://github.com/cloudevents/sdk-java) -发送和接收 [CloudEvents](https://cloudevents.io/) 使用 [Vert.x HTTP Transport](https://github.com/cloudevents/sdk-java/blob/master/http/vertx/README.md) 用于CloudEvents.

## Middleware

* [Apache Camel](https://github.com/apache/camel/blob/master/components/camel-vertx/src/main/docs/vertx-component.adoc) - [Apache Camel](http://camel.apache.org/) 使用Vert.x事件总线桥接Camel的组件.
* [Gateleen](https://github.com/swisspush/gateleen) -基于Vert.x的中间件库，用于构建高级JSON / REST通信服务器.
* [Gravitee.io](https://gravitee.io) -OSS API平台，包括基于Vert.x Core / Vert.x Web和其他模块的API网关和OAuth2 / OIDC授权服务器.
* [API Framework](https://github.com/vinscom/api-framework)  -基于Vertx和Glue的微服务框架，消除了独立应用程序和无服务应用程序之间的区别.  所有服务都可以在独立服务器上运行，但是，如果需要，可以将相同的代码库用作无服务器应用程序来运行任何服务.


## Language Support

*对Vert.x的编程语言支持*

* [Python](https://github.com/vert-x3/vertx-lang-python) -Python支持.
* [TypeScript](https://github.com/michel-kraemer/vertx-lang-typescript) -TypeScript支持.
* [EcmaScript](https://github.com/reactiverse/es4x) -EcmaScript&gt; = 6（JavaScript）支持.
* [Php](https://github.com/vert-x-cn/vertx-lang-jphp) -PHP支持.

*语言扩展*

* [Grooveex](https://github.com/aesteve/grooveex) -语法糖+实用程序（DSL构建器等）之上 [vertx-lang-groovy](https://github.com/vert-x3/vertx-lang-groovy).

## Reactive

* [vertx-util](https://github.com/cyngn/vertx-util) -轻质的承诺和闩锁Vert.x.
* [QBit](https://github.com/advantageous/qbit)  -异步类型的类似于actor的库，可以在Vert.x异步回调中轻松运行.  回调管理.
* [VxRifa](https://nsforth.github.io/vxrifa) -Vert.X的实用程序库，该库允许在通过EventBus进行通信时使用强类型接口.

## Sync Thread Non Block

* [Sync](https://github.com/vert-x3/vertx-sync) -同步但非OS线程阻塞的顶点.

## Vert.x Event Bus Clients

*将应用程序连接到Vert.x事件总线的客户端*

* [JavaScript](https://www.npmjs.com/package/vertx3-eventbus-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -JavaScript事件总线客户端.
* [C++11](https://github.com/julien3/vertxbuspp) -C ++ 11事件总线客户端.
* [Java](https://github.com/saffron-technology/vertx-eventbusbridge) -vertxbus.js的Java实现.
* [Java](https://github.com/abdlquadri/vertx-eventbus-java) -Java和Android事件总线客户端.
* [Java](https://github.com/danielstieger/javaxbus) -使用纯TCP套接字I / O的简单Java事件总线客户端.
* [CLI](https://github.com/cinterloper/vxc) -Vert.x事件总线的命令行二进制客户端-JSON中的管道，发出JSON.
* [Swift](https://github.com/tobias/vertx-swift-eventbus) -的事件总线客户端 [Apple's Swift](https://swift.org) 使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Python](https://github.com/jaymine/TCP-eventbus-client-Python) -使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C#](https://github.com/jaymine/TCP-eventbus-client-C-Sharp) - Event bus client for C# using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C](https://github.com/jaymine/TCP-eventbus-client-C) -使用C99的事件总线客户端 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Go](https://github.com/jponge/vertx-go-tcp-eventbus-bridge)-Go语言的事件总线客户端，使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Smalltalk](https://github.com/mumez/VerStix)-的事件总线客户端 [Pharo Smalltalk](http://pharo.org/) 使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Java](https://github.com/nielsbaloe/vertxui/tree/master/vertxui-core/src/main/java/live/connector/vertxui/client/transport) -通过Java代码在JavaScript中支持事件总线.
* [Elixir](https://github.com/PharosProduction/ExVertx) -使用TCP套接字的Elixir应用程序的事件总线支持.

## Cluster Managers

* Vert.x集群管理器SPI的实现*

* [JGroups Cluster Manager](https://github.com/vert-x3/vertx-jgroups) -JGroups集群管理器.
* [Atomix Cluster Manager](https://github.com/atomix/atomix-vertx) -一个 [Atomix](http://atomix.io) 基于Vert.x 3的群集管理器实现.
* [Consul Cluster Manager](https://github.com/reactiverse/consul-cluster-manager) -领事群集管理器.

## Cloud Support

* [S3](https://github.com/hubrick/vertx-s3-client) -适用于S3的功能齐全的Vert.x客户端.
* [AWS SDK](https://github.com/reactiverse/aws-sdk) -将AWS Java SDK v2（异步）与Vert.x一起使用

## Docker


## Microservices

* [Vert.x GraphQL Service Discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - [GraphQL](http://graphql.org/) 服务发现和查询您的Vert.x微服务.
* [HTTP Request Multiplexer - Kalfor](https://github.com/derveloper/kalfor)  -将多个HTTP GET请求合并到一个POST中.  Facebook的替代品 [GraphQL](http://graphql.org/) 和Netflix [Falcor](http://netflix.github.io/falcor/).
* [Resilience4j](https://github.com/resilience4j/resilience4j)  -Resilience4j是为Java8和功能编程设计的容错库.  Resilience4j提供用于断路，速率限制，隔离，自动重试，响应缓存和度量标准测量的模块.
* [Autonomous Services](https://github.com/mikand13/autonomous-services)  -用于创建自主服务的工具包.  利用vert.x和nannoq工具的体系结构提供了基于事件的反应式体系结构，而没有用于通信或数据的集中式组件，从而在整个体系结构上提供了理论上的线性可伸缩性.
* [Apache ServiceComb Java Chassis](https://github.com/apache/servicecomb-java-chassis) -ServiceComb Java Chassis是一个软件开发套件（SDK），用于在Java中快速开发微服务，提供服务注册，服务发现，动态路由和服务管理功能.

## Search Engines

* [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service) -Vert.x 3 [Elasticsearch](https://www.elastic.co/) 事件总线代理的服务.
* [Vert.x Elasticsearch Service (redesign)](https://github.com/hubrick/vertx-elasticsearch-service) -Vert.x 3 [Elasticsearch](https://www.elastic.co/)  事件总线代理的服务.  重新设计 [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service) .  通过事件总线大量使用DTO，而不再使用JsonObjects.  添加了对ES插件的支持.
* [Vert.x Solr Service](https://github.com/englishtown/vertx-solr-service) -具有事件总线代理的Vert.x 3 Solr服务.

## Template Engines

* [KorTE Template Engine](https://github.com/korlibs/korte) -与Twig / Django / Liquid类似的Kotlin模板引擎，支持调用Kotlin暂停方法.

## Service Factory

* [Node.js Service Factory](https://github.com/mellster2012/vertx-nodejs-service-factory) -Vert.x Node.js服务工厂.
* [Eclipse SISU Service Factories](https://github.com/cstamas/vertx-sisu) -与Vert.x集成 [Eclipse SISU](https://www.eclipse.org/sisu/) 为“ vertx-service-factory”和“ vertx-maven-service-factory”提供替代品的DI容器.

## Config

* [Vert.x Config AWS SSM Store](https://github.com/Finovertech/vertx-config-aws-ssm) - 一种 [config store](http://vertx.io/docs/vertx-config/java/) 从中检索配置值的实现 [AWS EC2 SSM Parameter Store](https://aws.amazon.com/ec2/systems-manager/parameter-store/).
* [Vert.x Boot](https://github.com/jponge/vertx-boot) -从HOCON配置中部署垂直.

## Dependency Injection

* [Vert.x Guice](https://github.com/englishtown/vertx-guice) -用于Guice依赖项注入的Vert.x顶点工厂.
* [Vert.x HK2](https://github.com/englishtown/vertx-hk2) -用于HK2依赖项注入的Vert.x垂直工厂.
* [Spring Vert.x Extension](https://github.com/amoAHCP/spring-vertx-ext) -Vert.x垂直工厂用于春季DI注入.
* [Vert.x Beans](https://github.com/rworsnop/vertx-beans) -将Vert.x对象作为bean注入到Spring应用程序中.
* [QBit](https://github.com/advantageous/qbit)  -QBit可用于Spring DI和Spring Boot（当然还有Vert.x）.  允许您在同一应用程序中使用QBit，Vert.x，Spring DI和Spring Boot.
* [Vert.x Eclipse SISU](https://github.com/cstamas/vertx-sisu) -与Vert.x集成 [Eclipse SISU](https://www.eclipse.org/sisu/) 在容器中.
* [Vert.x Spring Verticle Factory](https://github.com/juanavelez/vertx-spring-verticle-factory) -Vert.x Verticle工厂，该工厂利用Spring获取和配置Verticles.
* [Glue](https://github.com/vinscom/glue)  -久经考验的编程和基于Java和Vertx的应用程序的配置模型.  受ATG Nucleus的启发，它使用简单的属性文件提供了强大的基于层的配置管理.

## Testing

* [Vert.x WireMongo](https://github.com/noenv/vertx-wiremongo) -Vert.x的轻量级mongo模拟

## Development Tools

* [Vert.x health check](https://github.com/vert-x3/vertx-health-check) -允许在Vert.x项目中进行远程运行状况检查.
* [Vert.x Hot](https://github.com/dazraf/vertx-hot) -一个用于Maven Vert.x项目热部署的Maven插件.
* [slush-vertx](https://www.npmjs.com/package/slush-vertx) -模板驱动的Vert.x项目生成器，用于不同的语言和构建工具.
* [Vert.x for Visual Studio Code](https://github.com/pmlopes/VertxSnippet)  -用于Vert.x的Visual Studio代码（多语言）插件.  也可以从 [Marketplace](https://marketplace.visualstudio.com/items?itemName=pmlopes.vertxsnippet).
* [Vert.x Starter](http://www.jetdrone.xyz/vertx-starter/) -基于浏览器的Vert.x应用程序的项目启动器和项目模板.
* [Vert.x LiveReload](https://github.com/ybonnel/vertx-livereload) -用于Vert.x应用程序的简单livereload服务器.
* [openapi-generator](https://github.com/OpenAPITools/openapi-generator) -OpenAPI Generator可以根据给定的OpenAPI规范（v2，v3）自动生成API客户端库（SDK生成），服务器存根，文档和配置.

## Miscellaneous

* [Vert.x Child Process](https://github.com/vietj/vertx-childprocess) -从Vert.x生成子进程.
* [vertx-redisques](https://github.com/swisspush/vertx-redisques) -用于Vert.x的高度可扩展的Redis持久队列系统.
* [Simple File Server](https://github.com/pitchpoint-solutions/sfs) -与OpenStack Swift兼容的分布式对象存储服务器，该服务器可以使用Vert.x实现的最少资源来服务和安全存储数十亿个大小文件.
* [Vert.x Boot](https://github.com/jponge/vertx-boot) -从HOCON配置中部署垂直.
* [GDH](https://github.com/maxamel/GDH) -建立在Vert.x之上的通用Diffie-Hellman密钥交换Java库.

## Distribution


## Examples

* [Vert.x feeds](https://github.com/aesteve/vertx-feeds) -使用Vert.x，Gradle，MongoDB，Redis，Handlebars模板，AngularJS，事件总线和SockJS构建的RSS聚合器示例.
* [Vert.x Markdown service](https://github.com/aesteve/vertx-markdown-service) -使用方法示例 [service-proxy](https://github.com/vert-x3/vertx-service-proxy) 与摇篮.
* [Example using event bus and service proxies to connect vertx and node](https://github.com/advantageous/vertx-node-ec2-eventbus-example) -带有Wiki描述的分步示例，显示了如何使用事件总线和服务代理连接Vert.x和Node.
* [Vert.x Todo-Backend implementation](https://github.com/aesteve/todo-backend-vertx)  -Todo MVC后端的纯Java 8实现.  使用Vert.x LocalMap进行存储.
* [Kotlin Todo-Backend implementation](https://github.com/aesteve/vertx-kotlin-todomvc) -Kotlin实施Todo MVC后端.
* [Scala Todo-Backend implementation](https://github.com/aesteve/vertx-scala-todomvc) -Todo MVC后端的Scala实现.
* [Grooveex Todo-Backend implementation](https://github.com/aesteve/todo-backend-grooveex) -使用Vert.x + Groovy +一些语法糖+ DSL路由工具的Todo MVC后端实现.
* [Vert.x Gradle Starter](https://github.com/yyunikov/vertx-gradle-starter) -Java 8入门应用程序，并带有在Gradle构建系统，配置文件配置和SLF4J中使用Vert.x的示例.
* [Vert.x Gentics Mesh Example](https://github.com/gentics/mesh-vertx-example) -有关如何使用Gentics Mesh和车把构建基于模板的Web服务器的示例.
* [HTTP/2 showcase](https://github.com/aesteve/http2-showcase) -一个简单的演示，展示了当涉及大量延迟时HTTP / 2如何极大地改善用户体验.
* [Vert.x Music Store](https://github.com/tsegismont/vertx-musicstore) -有关如何使用RxJava构建Vert.x应用程序的示例应用程序.
* [Crabzilla](https://github.com/crabzilla/crabzilla)  -另一个事件搜寻实验.  一个探索Vert.x的项目，以开发Event Sourcing / CQRS应用程序.
* [Vert.x PostgreSQL Starter](https://github.com/BillyYccc/vertx-postgresql-starter) -使用Vert.x堆栈和PostgreSQL构建整体CRUD RESTful Web服务的入门者.
* [Cloud Foundry](https://github.com/amdelamar/vertx-cloudfoundry) -示例Vert.x，用于部署到 [Cloud Foundry](https://www.cloudfoundry.org/) 服务提供者.
* [Knative](https://github.com/knative/docs/tree/master/serving/samples/helloworld-vertx) -有关如何使用的示例应用程序 [Reactive Extensions Vert.x](https://github.com/vert-x3/vertx-rx) 与 [Knative](https://github.com/knative).
## Deployment

* [Vert.x Deploy Application](https://github.com/msoute/vertx-deploy-tools) - (Seamless) deploy to AWS based Vert.x application clusters.

## Utilities

* [Chime](https://github.com/LisiLisenok/Chime) -在Vert.x事件总线上工作的时间计划程序，允许使用_cron-style_和_interval_定时器进行计划.
* [Vert.x Cron](https://github.com/diabolicallabs/vertx-cron)  -安排cron规格的事件.  具有事件总线和可观察的版本.
* [Vert.x CronUtils](https://github.com/NoEnv/vertx-cronutils)  -用于vertx调度程序的cron-utils的抽象.  支持Unix，Cron4j和Quartz样式表达式.
* [Vert.x POJO config](https://github.com/aesteve/vertx-pojo-config)  -允许在标准JSON配置和（类型安全的）配置Java bean之间进行映射.  还允许通过JSR 303验证配置bean.
* [Vert.x Async](https://github.com/gchauvet/vertx-async) -将caolan / async nodejs模块移植到Vert.x框架，该框架为常见的异步模式提供了辅助方法.
* [Vert.x JOLT](https://github.com/lusoalex/vertx-jolt)  -基于原始bazaarvoice JOLT项目的JSON到JSON转换工具.  有助于将不同的json结构转换为预期的json格式.
* [Vert.x Dependent Verticle Deployer](https://github.com/juanavelez/vertx-dependent-verticle-deployer) -Vert.x Verticle，用于部署顶点及其从属顶点.
* [Vert.x Dataloader](https://github.com/engagingspaces/vertx-dataloader)  -适用于Vert.x的Facebook Dataloader的Java端口.  数据层的高效批处理和缓存.
* [Vert.x Util](https://github.com/juanavelez/vertx-util) - A collection of Vert.x utility methods.
* [Vert.x Web Accesslog](https://github.com/romanpierson/vertx-web-accesslog) -只需在Vert.x Web中使用一个简单的处理程序即可生成访问日志.
* [Vert.x GraphQL Utils](http://github.com/tibor-kocsis/vertx-graphql-utils) -路由处理程序和Vert.x兼容的接口，用于处理Vert.x和Vert.x Web中的GraphQL查询.
* [Nannoq-Tools](https://noriginmedia.github.io/nannoq-tools/) -Nannoq-Tools是用于利用Vert.x构建健壮，可扩展和分布式应用程序的工具包，包括用于身份验证，集群管理，Firebase Cloud Messaging，DynamoDB，完全通用查询，REST等的模块.

## Community

- [User Group](https://groups.google.com/forum/?fromgroups#!forum/vertx) -讨论与*使用* Vert.x相关的所有用户问题.
- [Developer Group](https://groups.google.com/forum/?fromgroups#!forum/vertx-dev) -Vert.x核心*开发人员*和*贡献者*的小组.
- [Gitter chat](https://gitter.im/eclipse-vertx/vertx-users) Vert.x相关聊天的常规聊天.
- [Issues](https://github.com/vert-x3/issues/issues) -Vert.x核心问题跟踪器.
- [Wiki](https://github.com/vert-x3/wiki/wiki) -包含有关Vert.x的有用信息.
- [Learning Materials](http://vertx.io/materials/) -Vert.x上的文章和演示列表.
- [Blog](http://vertx.io/blog/) -官方的Vert.x博客，其中包含许多教程和其他信息.
- [2017 Events](https://github.com/vert-x3/wiki/wiki/Vert.x-2017-Events) -2017 Vert.x演讲和演示的列表.

## Social events / Meetups

- [Amsterdam/The Netherlands](https://www.meetup.com/Vert-x-NL)
- [Paris](https://www.meetup.com/Paris-vert-x-Meetup/)

## Front-End

* [VertxUI](https://github.com/nielsbaloe/vertxui) -一个纯Java前端工具包，具有描述性的流利的模型视图，POJO流量，虚拟DOM上的JUnit测试或真实DOM上的混合语言等.

## Contribute

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/vert-x3/vertx-awesome/blob/master/CONTRIBUTING.md) 第一.
