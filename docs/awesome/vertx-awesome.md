<div class="github-widget" data-repo="vert-x3/vertx-awesome"></div>
## Awesome Vert.x [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/logo-sm.png" align="right" width="250">](http://vertx.io)

* Awesome Vert.x *是一个很棒的框架，库或其他组件的列表，供使用或使用
[Vert.x](https://github.com/eclipse/vert.x) 版本3.

如果您希望组件显示在此处，请向此存储库发送拉取请求以添加它.

请注意，除非有，否则我们无法保证此列表中所有内容的稳定性或生产性
图标 <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px">
 在它的旁边.  此图标表示该组件是官方的一部分
[Vert.x stack](https://vertx.io/docs/).

对于Vert.x版本2检查 [this page](https://github.com/vert-x3/vertx-awesome/blob/master/./vert-x2.md).



## Books

* [A gentle guide to asynchronous programming with Eclipse Vert.x for Java developers](http://vertx.io/docs/guide-for-java-devs/) 作者：Julien Ponge，Thomas Segismont和Julien Viet
* [Building Reactive Microservices in Java](https://developers.redhat.com/promotions/building-reactive-microservices-in-java/) 作者：ClémentEscoffier
* [Vert.x in Action](https://www.manning.com/books/vertx-in-action) 作者Julien Ponge

## Build tools

* [Vert.x Maven plugin](https://github.com/fabric8io/vertx-maven-plugin)
* [Vert.x Gradle plugin](https://plugins.gradle.org/plugin/io.vertx.vertx-plugin)

## Web Frameworks

* [Vert.x Jersey](https://github.com/englishtown/vertx-jersey) - 创建JAX-RS [Jersey](https://jersey.java.net/) Vert.x中的资源.
* [Kovert](https://github.com/kohesive/kovert) -  Kotlin + Vert.x Web的隐形REST框架.
* [Handlers](https://github.com/spriet2000/vertx-handlers-http) - 为Vert.x打开Web框架.
* [QBit](https://github.com/advantageous/qbit) -  REST和WebSocket方法调用编组和反应库.
* [vertx-rest-storage](https://github.com/swisspush/vertx-rest-storage) - 文件系统或redis数据库中REST资源的持久性.
* [Jubilee](https://github.com/isaiah/jubilee) - 基于Vert.x 3构建的机架兼容Ruby HTTP服务器.
* [Knot.x](https://github.com/Cognifide/knotx) - 基于Vert.x 3构建的现代网站的高效和高性能集成平台.
* [Vert.x Jspare](https://github.com/jspare-projects/vertx-jspare) - 使用Jspare Framework改善Vert.x 3体验.
* [Irked](https://github.com/GreenfieldTech/irked) -  Vert.x 3 Web和控制器框架的基于注释的配置.
* [REST.VertX](https://github.com/zandero/rest.vertx) - 轻量级JAX-RS（RestEasy），用于Vert.x垂直的注释处理器.
* [Atmosphere Vert.x](https://github.com/Atmosphere/atmosphere-vertx) -  JVM的实时客户端服务器框架，支持跨浏览器回退的WebSockets和服务器发送事件.
* [Vert.x Vaadin](https://github.com/mcollovati/vertx-vaadin) - 在Vert.x上运行应用程序.

## Authentication Authorisation


* [Vert.x-Pac4j](https://github.com/pac4j/vertx-pac4j) - 使用执行Vert.x身份验证/授权 [pac4j](http://www.pac4j.org/).

## Database Clients

*连接数据库的客户*

*关系数据库
  * [JDBC](https://raw.githubusercontent.com/vert-x3/vertx-jdbc-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - 围绕JDBC数据源的异步接口.
  * [MySQL / PostgreSQL](https://raw.githubusercontent.com/vert-x3/vertx-mysql-postgresql-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -  MySQL / PostgreSQL的异步客户端.
  * [PostgreSQL](https://github.com/vietj/reactive-pg-client) - 反应性PostgreSQL客户端.
  * [database](https://github.com/susom/database) -  Oracle，PostgreSQL，SQL Server，HyperSQL等客户端，旨在提高安全性，正确性和易用性.
  * [jOOQ](https://github.com/jklingsporn/vertx-jooq) - 使用jOOQ执行类型安全的异步SQL并生成代码.

* NoSQL数据库
  * [MongoDB](https://raw.githubusercontent.com/vert-x3/vertx-mongo-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - 用于与MongoDB数据库交互的异步客户端.
  * [Redis](https://raw.githubusercontent.com/vert-x3/vertx-redis-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - 与Redis交互的异步API.
  * [Cassandra](https://raw.githubusercontent.com/vert-x3/vertx-cassandra-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -  Vert.x客户端，允许应用程序与Cassandra服务进行交互.
  * [Cassandra](https://github.com/englishtown/vertx-cassandra) - 与Cassandra和Cassandra Mapping交互的异步API.
  * [OrientDB](https://github.com/cstamas/vertx-orientdb) - 非阻塞OrientDB服务器集成.
  * [Bitsy](https://github.com/cstamas/vertx-bitsy) - 非阻塞Bitsy Graph服务器集成.
  * [MarkLogic](https://github.com/etourdot/vertx-marklogic) -  Marklogic数据库服务器的异步客户端.
  * [SirixDB](https://github.com/sirixdb/sirix/tree/master/bundles/sirix-rest-api) - 非阻塞SirixDB HTTP服务器.

* [vertx-pojo-mapper](https://github.com/BraintagsGmbH/vertx-pojo-mapper) -  MySQL和MongoDB的非阻塞POJO映射.
* [vertx-mysql-binlog-client](https://github.com/guoyu511/vertx-mysql-binlog-client) - 用于访问MySQL复制流的Vert.x客户端.
* [vertx-mongo-streams](https://github.com/st-h/vertx-mongo-streams) - 帮助使用MongoDB异步驱动程序将Vert.x流传输到MongoDB GridFS或从MongoDB GridFS传输.

## Integration

*服务器发送的事件
  * [jEaSSE](https://github.com/mariomac/jeasse)   -  Java Easy SSE.  一个简单，轻量级的SSE实现.
  * [vertx-sse](https://github.com/aesteve/vertx-sse) -  Vert.x SSE实现+事件总线SSE桥.

*邮件
  * [SMTP](https://raw.githubusercontent.com/vert-x3/vertx-mail-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - 异步SMTP客户端.
  * [vertx-smtp-server](https://github.com/cinterloper/vertx-smtp-server) -  SMTP服务器桥接到EventBus.

* REST
  * [Vert.x REST Client](https://github.com/hubrick/vertx-rest-client) -  Vert.x的REST客户端，支持RxJava和请求缓存.
  * [Retrofit adapter for Vert.x](https://github.com/vietj/retrofit-vertx) - 使用Vert.x进行Retrofit的高度可扩展的适配器.

*消息
  * [AMQP 1.0](https://raw.githubusercontent.com/vert-x3/vertx-amqp-bridge) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - 使用Vert.x Producer和Consumer API与AMQP 1.0服务器交互.
  * [MQTT](https://raw.githubusercontent.com/vert-x3/vertx-mqtt) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - 提供两个不同的组件：MQTT服务器，用于处理与客户端的所有MQTT通信和消息交换; MQTT客户端，用于发送和接收针对MQTT代理的消息.
  * [RabbitMQ](https://raw.githubusercontent.com/vert-x3/vertx-rabbitmq-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -  RabbitMQ客户端（AMQP 0.9.1）.
  * [Kafka Client](https://raw.githubusercontent.com/vert-x3/vertx-kafka-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -  Kafka客户.
  * [kafka](https://github.com/cyngn/vertx-kafka) - 用于消费和生成消息的Kafka客户端.
  * [Kafka Service](https://github.com/hubrick/vertx-kafka-service) - 具有重试逻辑的Kafka制作人和消费者.
  * [SaltStack](https://github.com/cinterloper/vertx-salt) -  SaltStack事件系统和Vert.x事件总线之间的双向桥接.
  * [STOMP](https://raw.githubusercontent.com/vert-x3/vertx-stomp) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -  Kafka客户端和服务器.
  * [ZeroMQ](https://github.com/dano/vertx-zeromq) -  ZeroMQ事件总线桥.
  * [MQTT Broker](https://github.com/GruppoFilippetti/vertx-mqtt-broker) -  MQTT Broker（MQTT版本3.1.1和3.1兼容）.
  * [Azure ServiceBus](https://github.com/TextBack/vertx-azure-servicebus) -  Azure [ServiceBus](https://azure.microsoft.com/en-us/services/service-bus/) producer and consumer (fully async, doesn't use Microsoft Azure SDK).
  * [AMQP 1.0 - Kafka bridge](https://github.com/rhiot/amqp-kafka-bridge) - 使用AMQP 1.0协议向Apache Kafka发送/接收消息的桥接器.
  * [Vert.x Kafka Client](https://raw.githubusercontent.com/vert-x3/vertx-kafka-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -  Apache Kafka客户端，用于从/向Apache Kafka集群读取和发送消息.

* JavaEE
  * [JCA adaptor](https://raw.githubusercontent.com/vert-x3/vertx-jca) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - 用于Vert.x事件总线的Java Connector Architecture Adapter.
  * [Weld](https://github.com/weld/weld-vertx) - 将CDI编程模型引入Vert.x生态系统（将CDI观察者方法注册为Vert.x消息使用者，CDI驱动的Verticle，以声明方式定义路由等）.

*流星
  * [Meteor](https://github.com/jmusacchio/vertxbus/) - 通过Vert.x事件总线支持流星集成.

*指标
  * [Hawkular metrics](https://github.com/tsegismont/vertx-monitor) - [Hawkular](http://www.hawkular.org/) Vert.x Metrics SPI的实现.
  * [DropWizard metrics](https://raw.githubusercontent.com/vert-x3/vertx-dropwizard-metrics) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - 使用DropWizard指标实现指标.
  * [Micrometer metrics](https://raw.githubusercontent.com/vert-x3/vertx-micrometer-metrics) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - 使用Micrometer指标实施指标.
  * [OpenTsDb Metrics](https://github.com/cyngn/vertx-opentsdb) - [OpenTsDb](http://opentsdb.net/) Vert.x的指标客户端.
  * [Bosun Monitoring](https://github.com/cyngn/vertx-bosun) - [Bosun](https://bosun.org/) Vert.x的客户端库.

* Netflix  -  Hystrix
  * [Hystrix Metrics Stream](https://github.com/kennedyoliveira/hystrix-vertx-metrics-stream.git) - 使用Vert.x应用程序发送Hystrix仪表板的指标 [Hystrix](https://github.com/Netflix/Hystrix).

*飞镖
  * [Vert.x Dart SockJS](https://github.com/wem/vertx-dart-sockjs) - [Dart](https://www.dartlang.org/) 整合 [Vert.x SockJS bridge](http://vertx.io/docs/vertx-web/java/#_sockjs_event_bus_bridge) 和简单的SockJS使用dart：js.

* 推送通知
  * [Onesignal](https://github.com/jklingsporn/vertx-push-onesignal) - 使用Vert.x应用程序向（移动/网络）应用程序发送推送通知 [OneSignal](https://onesignal.com/).

* CNCF CloudEvents
  * [CloudEvents.io Java SDK](https://github.com/cloudevents/sdk-java) - 发送和接收 [CloudEvents](https://cloudevents.io/) 使用 [Vert.x HTTP Transport](https://github.com/cloudevents/sdk-java/blob/master/http/vertx/README.md) 对于CloudEvents.

## Middleware

* [Apache Camel](https://github.com/apache/camel/blob/master/components/camel-vertx/src/main/docs/vertx-component.adoc) - [Apache Camel](http://camel.apache.org/) 用于使用Vert.x事件总线桥接Camel的组件.
* [Gateleen](https://github.com/swisspush/gateleen) - 基于Vert.x的中间件库，用于构建高级JSON / REST通信服务器.
* [Gravitee.io](https://gravitee.io) -  OSS API平台，包括API网关和基于Vert.x Core / Vert.x Web和其他模块的OAuth2 / OIDC授权服务器.

## Language Support

* Vert.x *的编程语言支持

* [Python](https://github.com/vert-x3/vertx-lang-python) -  Python支持.
* [TypeScript](https://github.com/michel-kraemer/vertx-lang-typescript) -  TypeScript支持.
* [EcmaScript](https://github.com/reactiverse/es4x) -  EcmaScript&gt; = 6（JavaScript）支持.

*语言扩展*

* [Grooveex](https://github.com/aesteve/grooveex) - 语法糖+实用程序（DSL构建器等） [vertx-lang-groovy](https://github.com/vert-x3/vertx-lang-groovy).

## Reactive

* [vertx-util](https://github.com/cyngn/vertx-util) -  Vert.x的轻量级承诺和锁存器.
* [QBit](https://github.com/advantageous/qbit)   - 在Vert.x Async Callbacks中轻松运行的异步类型的类似actor的lib.  回调管理.
* [VxRifa](https://nsforth.github.io/vxrifa) -  Vert.X的实用程序库，允许在通过EventBus进行通信时使用强类型接口.

## Sync Thread Non Block

* [Sync](https://github.com/vert-x3/vertx-sync) - 同步但非OS线程阻塞的Verticle.

## Vert.x Event Bus Clients

*客户端将应用程序连接到Vert.x事件总线*

* [JavaScript](https://www.npmjs.com/package/vertx3-eventbus-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> -  JavaScript事件总线客户端.
* [C++11](https://github.com/julien3/vertxbuspp) -  C ++ 11事件总线客户端.
* [Java](https://github.com/saffron-technology/vertx-eventbusbridge) -  vertxbus.js的Java实现.
* [Java](https://github.com/abdlquadri/vertx-eventbus-java) -  Java和Android事件总线客户端.
* [Java](https://github.com/danielstieger/javaxbus) - 使用普通TCP套接字I / O的简单Java事件总线客户端.
* [CLI](https://github.com/cinterloper/vxc) -  Vert.x事件总线的命令行二进制客户端 -  JSON管道，发出JSON.
* [Swift](https://github.com/tobias/vertx-swift-eventbus) - 活动巴士客户端 [Apple's Swift](https://swift.org) 使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Python](https://github.com/jaymine/TCP-eventbus-client-Python) - 使用Python的事件总线客户端 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C#](https://github.com/jaymine/TCP-eventbus-client-C-Sharp) - Event bus client for C# using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C](https://github.com/jaymine/TCP-eventbus-client-C) - 使用C99的C99事件总线客户端 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Go](https://github.com/jponge/vertx-go-tcp-eventbus-bridge)-  Go-lang的活动巴士客户端 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Smalltalk](https://github.com/mumez/VerStix)- 活动巴士客户端 [Pharo Smalltalk](http://pharo.org/) 使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Java](https://github.com/nielsbaloe/vertxui/tree/master/vertxui-core/src/main/java/live/connector/vertxui/client/transport) - 通过Java代码在JavaScript中支持事件总线.

## Cluster Managers

* Vert.x集群管理器SPI *的实现

* [JGroups Cluster Manager](https://github.com/vert-x3/vertx-jgroups) -  JGroups集群管理器.
* [Atomix Cluster Manager](https://github.com/atomix/atomix-vertx) - 安 [Atomix](http://atomix.io) 基于Vert.x 3的集群管理器实现.
* [Consul Cluster Manager](https://github.com/romalev/vertx-consul-cluster-manager) -  Consul集群经理.

## Cloud Support

* [S3](https://github.com/hubrick/vertx-s3-client) - 适用于S3的全功能Vert.x客户端.

## Docker


## Microservices

* [Vert.x GraphQL Service Discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - [GraphQL](http://graphql.org/) 服务发现和查询Vert.x微服务.
* [HTTP Request Multiplexer - Kalfor](https://github.com/derveloper/kalfor)   - 将多个HTTP GET请求合并到一个POST中.  Facebook的简单替代品 [GraphQL](http://graphql.org/) 和Netflix [Falcor](http://netflix.github.io/falcor/).
* [Resilience4j](https://github.com/resilience4j/resilience4j)   -  Resilience4j是一个专为Java8和函数式编程而设计的容错库.  Resilience4j提供用于断路，速率限制，Bulkheading，自动重试，响应缓存和度量测量的模块.

## Search Engines

* [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service) -  Green.x 3 [Elasticsearch](https://www.elastic.co/) 事件总线代理服务.
* [Vert.x Elasticsearch Service (redesign)](https://github.com/hubrick/vertx-elasticsearch-service) -  Green.x 3 [Elasticsearch](https://www.elastic.co/)  事件总线代理服务.  重新设计 [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service) .  在事件总线上大量使用DTO而不再使用JsonObjects.  添加了对ES插件的支持.
* [Vert.x Solr Service](https://github.com/englishtown/vertx-solr-service) - 使用事件总线代理的Vert.x 3 Solr服务.

## Service Factory

* [Node.js Service Factory](https://github.com/mellster2012/vertx-nodejs-service-factory) -  Vert.x Node.js服务工厂.
* [Eclipse SISU Service Factories](https://github.com/cstamas/vertx-sisu) -  Vert.x集成 [Eclipse SISU](https://www.eclipse.org/sisu/) DI容器为`vertx-service-factory`和`vertx-maven-service-factory`提供替代品.

## Config

* [Vert.x Config AWS SSM Store](https://github.com/Finovertech/vertx-config-aws-ssm) - 一个 [config store](http://vertx.io/docs/vertx-config/java/) 从中检索配置值的实现 [AWS EC2 SSM Parameter Store](https://aws.amazon.com/ec2/systems-manager/parameter-store/).
* [Vert.x Boot](https://github.com/jponge/vertx-boot) - 从HOCON配置部署Verticle.

## Dependency Injection

* [Vert.x Guice](https://github.com/englishtown/vertx-guice) - 用于Guice依赖注入的Vert.x verticle工厂.
* [Vert.x HK2](https://github.com/englishtown/vertx-hk2) - 用于HK2依赖注入的Vert.x verticle工厂.
* [Spring Vert.x Extension](https://github.com/amoAHCP/spring-vertx-ext) - 用于Spring DI注射的Vert.x Verticle工厂.
* [Vert.x Beans](https://github.com/rworsnop/vertx-beans) - 将Vert.x对象作为bean注入Spring应用程序.
* [QBit](https://github.com/advantageous/qbit)   -  QBit适用于Spring DI和Spring Boot（当然还有Vert.x）.  允许您在同一个应用程序中使用QBit，Vert.x，Spring DI和Spring Boot.
* [Vert.x Eclipse SISU](https://github.com/cstamas/vertx-sisu) -  Vert.x集成 [Eclipse SISU](https://www.eclipse.org/sisu/) 在容器中.
* [Vert.x Spring Verticle Factory](https://github.com/juanavelez/vertx-spring-verticle-factory) -  Vert.x Verticle Factory，它使用Spring来获取和配置Verticle.

## Testing


## Development Tools

* [Vert.x health check](https://github.com/vert-x3/vertx-health-check) - 允许Vert.x项目中的远程运行状况检查.
* [Vert.x Hot](https://github.com/dazraf/vertx-hot) - 用于热部署Maven Vert.x项目的Maven插件.
* [slush-vertx](https://www.npmjs.com/package/slush-vertx) - 用于不同语言和构建工具的模板驱动的Vert.x项目生成器.
* [Vert.x for Visual Studio Code](https://github.com/pmlopes/VertxSnippet)   -  Vert.x的Visual Studio代码（多语言）插件.  也可以从 [Marketplace](https://marketplace.visualstudio.com/items?itemName=pmlopes.vertxsnippet).
* [Vert.x Starter](http://www.jetdrone.xyz/vertx-starter/) - A browser-based project starter and project templates for Vert.x applications.
* [Vert.x LiveReload](https://github.com/ybonnel/vertx-livereload) -  Vert.x应用程序的简单实时加载服务器.

## Miscellaneous

* [Vert.x Child Process](https://github.com/vietj/vertx-childprocess) - 来自Vert.x的Spawn子进程.
* [vertx-redisques](https://github.com/swisspush/vertx-redisques) -  Vert.x的高度可扩展的redis-persistent排队系统.
* [Simple File Server](https://github.com/pitchpoint-solutions/sfs) - 一个OpenStack Swift兼容的分布式对象存储服务器，可以使用Vert.x实现的最少资源服务并安全地存储数十亿个大小文件.
* [Vert.x Boot](https://github.com/jponge/vertx-boot) - 从HOCON配置部署Verticle.
* [GDH](https://github.com/maxamel/GDH) - 基于Vert.x构建的通用Diffie-Hellman密钥交换Java库.

## Distribution


## Examples

* [Vert.x feeds](https://github.com/aesteve/vertx-feeds) - 使用Vert.x，Gradle，MongoDB，Redis，Handlebars模板，AngularJS，事件总线和SockJS构建的RSS聚合器示例.
* [Vert.x Markdown service](https://github.com/aesteve/vertx-markdown-service) - 关于如何使用的示例 [service-proxy](https://github.com/vert-x3/vertx-service-proxy) 与Gradle.
* [Example using event bus and service proxies to connect vertx and node](https://github.com/advantageous/vertx-node-ec2-eventbus-example) -  wiki描述的分步示例，显示如何使用事件总线和服务代理连接Vert.x和Node.
* [Vert.x Todo-Backend implementation](https://github.com/aesteve/todo-backend-vertx)   -  Todo MVC后端的纯Java 8实现.  使用Vert.x LocalMap进行存储.
* [Kotlin Todo-Backend implementation](https://github.com/aesteve/vertx-kotlin-todomvc) -  Kotlin实现了Todo MVC后端.
* [Scala Todo-Backend implementation](https://github.com/aesteve/vertx-scala-todomvc) -  Scala实现Todo MVC后端.
* [Grooveex Todo-Backend implementation](https://github.com/aesteve/todo-backend-grooveex) - 使用Vert.x + Groovy +一些语法糖+ DSL路由设施的Todo MVC后端实现.
* [Vert.x Gradle Starter](https://github.com/yyunikov/vertx-gradle-starter) -  Java 8入门应用程序，其中包含使用Vert.x和Gradle构建系统，配置文件配置和SLF4J的示例.
* [Vert.x Gentics Mesh Example](https://github.com/gentics/mesh-vertx-example) - 有关如何使用Gentics Mesh和把手构建基于模板的Web服务器的示例.
* [HTTP/2 showcase](https://github.com/aesteve/http2-showcase) - 一个简单的演示，展示了当涉及巨大的延迟时，HTTP / 2如何能够显着改善用户体验.
* [Vert.x Music Store](https://github.com/tsegismont/vertx-musicstore) - 关于如何使用RxJava构建Vert.x应用程序的示例应用程序.
* [Crabzilla](https://github.com/crabzilla/crabzilla)   - 又一个事件采购实验.  探索Vert.x以开发Event Sourcing / CQRS应用程序的项目.
* [Vert.x PostgreSQL Starter](https://github.com/BillyYccc/vertx-postgresql-starter) - 使用Vert.x堆栈和PostgreSQL构建单一的CRUD RESTful Web服务的入门者.
* [Cloud Foundry](https://github.com/amdelamar/vertx-cloudfoundry) - 用于部署到a的Vert.x示例 [Cloud Foundry](https://www.cloudfoundry.org/) 服务提供者.
* [Knative](https://github.com/knative/docs/tree/master/serving/samples/helloworld-vertx) - 关于如何使用的示例应用程序 [Reactive Extensions Vert.x](https://github.com/vert-x3/vertx-rx) 同 [Knative](https://github.com/knative).
## Deployment

* [Vert.x Deploy Application](https://github.com/msoute/vertx-deploy-tools) - （无缝）部署到基于AWS的Vert.x应用程序集群.

## Utilities

* [Chime](https://github.com/LisiLisenok/Chime) - 使用Vert.x事件总线的时间调度程序，允许使用_cron-style_和_interval_计时器进行调度.
* [Vert.x Cron](https://github.com/diabolicallabs/vertx-cron)   - 使用cron规范安排事件.  有事件总线和Observable版本.
* [Vert.x POJO config](https://github.com/aesteve/vertx-pojo-config)   - 允许在标准JSON配置和（类型安全）配置Java bean之间进行映射.  还允许通过JSR 303验证配置bean.
* [Vert.x Async](https://github.com/gchauvet/vertx-async) - 将caolan / async nodejs模块移植到Vert.x框架，为常见的异步模式提供帮助程序方法.
* [Vert.x JOLT](https://github.com/lusoalex/vertx-jolt)   - 基于原始bazaarvoice JOLT项目的JSON到JSON转换工具.  有助于将不同的json结构转换为预期的json格式.
* [Vert.x Dependent Verticle Deployer](https://github.com/juanavelez/vertx-dependent-verticle-deployer) -  Vert.x Verticle旨在部署Verticle及其依赖Verticle.
* [Vert.x Dataloader](https://github.com/engagingspaces/vertx-dataloader)   - 用于Vert.x的Facebook Dataloader的Java端口.  为数据层提供高效的批处理和缓存.
* [Vert.x Util](https://github.com/juanavelez/vertx-util) -  Vert.x实用程序方法的集合.
* [Vert.x Web Accesslog](https://github.com/romanpierson/vertx-web-accesslog) - 只是一个在Vert.x Web中用于生成访问日志的简单处理程序.
* [Vert.x GraphQL Utils](http://github.com/tibor-kocsis/vertx-graphql-utils) - 路径处理程序和Vert.x兼容接口，用于处理Vert.x和Vert.x Web中的GraphQL查询.
* [Nannoq-Tools](https://noriginmedia.github.io/nannoq-tools/) -  Nannoq-Tools是一个工具包，用于构建利用Vert.x的强大，可扩展和分布式应用程序，包括用于身份验证，集群管理，Firebase云消息传递，DynamoDB，完全通用查询，REST等的模块.

## Community

- [User Group](https://groups.google.com/forum/?fromgroups#!forum/vertx) - 讨论与使用* Vert.x相关的所有用户问题.
- [Developer Group](https://groups.google.com/forum/?fromgroups#!forum/vertx-dev) -  Vert.x核心*开发人员*和*贡献者*的组.
- [Gitter chat](https://gitter.im/eclipse-vertx/vertx-users) Vert.x相关聊天的一般聊天.
- [Issues](https://github.com/vert-x3/issues/issues) -  Vert.x核心问题跟踪器.
- [Wiki](https://github.com/vert-x3/wiki/wiki) - 包含有关Vert.x的有用信息.
- [Learning Materials](http://vertx.io/materials/) -  Vert.x上的文章和演示文稿列表.
- [Blog](http://vertx.io/blog/) - 官方Vert.x博客，包含许多教程和其他信息.
- [2017 Events](https://github.com/vert-x3/wiki/wiki/Vert.x-2017-Events) -  2017年Vert.x会谈和演示清单.

## Social events / Meetups

- [Amsterdam/The Netherlands](https://www.meetup.com/Vert-x-NL)
- [Paris](https://www.meetup.com/Paris-vert-x-Meetup/)

## Front-End

* [VertxUI](https://github.com/nielsbaloe/vertxui) - 纯Java前端工具包，具有描述性流畅的模型视图，POJO流量，虚拟DOM上的JUnit测试或真实DOM上的混合语言等.

## Contribute

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/vert-x3/vertx-awesome/blob/master/CONTRIBUTING.md) 第一.
