<div class="github-widget" data-repo="akullpp/awesome-java"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Java [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

精选的 Java 框架、库和软件的精选列表.



## Projects

### Bean Mapping

_简化 bean 映射的框架._

- [dOOv](https://github.com/doov-io/doov)  - 为类型安全域模型验证和映射提供流畅的 API. 它使用注释、代码生成和类型安全的 DSL 使 bean 验证和映射变得快速而简单.
- [JMapper](https://github.com/jmapper-framework/jmapper-core)  - 使用字节码操作进行闪电般的映射. 支持注解和 API 或 XML 配置.
- [MapStruct](https://github.com/mapstruct/mapstruct) - 代码生成器，基于约定优于配置的方法，简化了不同 bean 类型之间的映射.
- [ModelMapper](https://github.com/modelmapper/modelmapper) - 自动将对象相互映射的智能对象映射库.
- [Orika](https://github.com/orika-mapper/orika) - JavaBean 映射框架，递归地将数据（以及其他功能）从一个对象复制到另一个对象.
- [reMap](https://github.com/remondis-it/remap) - 基于 Lambda 和方法句柄的映射，如果对象具有不同的名称，则需要代码而不是注释.
- [Selma](https://github.com/xebia-france/selma) - 基于注释处理器的 bean 映射器.

### Build

_处理应用程序的构建周期和依赖项的工具._

- [Apache Maven](https://maven.apache.org)  - 声明式构建和依赖管理，支持约定优于配置. 它可能比 Apache Ant 更可取，后者使用相当程序化的方法并且可能难以维护.
- [Bazel](https://bazel.build) - 来自 Google 的工具，可快速可靠地构建代码.
- [Buck](https://github.com/facebook/buck) - 鼓励创建由代码和资源组成的小型、可重用模块.
- [Gradle](https://gradle.org)  - 通过 Groovy 编程的增量构建，而不是声明 XML. 与 Maven 的依赖管理配合得很好.

### Bytecode Manipulation

_以编程方式操作字节码的库._

- [ASM](https://asm.ow2.io) - 通用的低级字节码操作和分析.
- [Byte Buddy](https://bytebuddy.net) - 使用流畅的 API 进一步简化字节码生成.
- [bytecode-viewer](https://github.com/Konloch/bytecode-viewer)  - Java 8 Jar 和 Android APK 逆向工程套件.  （仅限 GPL-3.0）
- [Byteman](https://byteman.jboss.org)  - 在运行时通过 DSL（规则）操作字节码； 主要用于测试/故障排除.  （LGPL-2.1 或更高版本）
- [cglib](https://github.com/cglib/cglib) - 字节码生成库.
- [Javassist](https://github.com/jboss-javassist/javassist) - 尝试简化字节码编辑.
- [Mixin](https://github.com/SpongePowered/Mixin) - 在运行时使用真正的 Java 代码操作字节码.
- [Perses](https://github.com/nicolasmanic/perses) - 根据混沌工程原理在字节码级别动态注入故障/延迟.

### Caching

_提供缓存设施的库._

- [cache2k](https://cache2k.org) - 内存中的高性能缓存库.
- [Caffeine](https://github.com/ben-manes/caffeine) - 高性能、近乎最优的缓存库.
- [Ehcache](http://www.ehcache.org) - 分布式通用缓存.
- [Infinispan](https://infinispan.org) - 用于缓存的高并发键/值数据存储.

### CLI

_与 CLI 相关的所有内容的库._

- [ASCII Table](https://github.com/vdmeer/asciitable) - 用 ASCII 绘制表格的库.
- [Airline](https://github.com/airlift/airline) - 基于注释的框架，用于解析类似 Git 的命令行参数.
- [args4j](http://args4j.kohsuke.org) - 用于解析命令行参数的小型库.
- [Jansi](https://github.com/fusesource/jansi) - 用于格式化控制台输出的 ANSI 转义码.
- [Java ASCII Render](https://github.com/indvd00m/java-ascii-render) - 控制台的图形原语.
- [JCommander](http://jcommander.org) - 通过实现接口具有自定义类型和验证的命令行参数解析框架.
- [jbock](https://github.com/jbock-java/jbock) - 无反射命令行解析器.
- [Jexer](https://gitlab.com/klamonte/jexer)  - 高级控制台（和 Swing）文本用户界面 (TUI) 库，具有鼠标可拖动窗口、内置终端窗口管理器和六像素图像支持. 看起来像 [Turbo Vision](https://en.wikipedia.org/wiki/Turbo_Vision).
- [JLine](https://github.com/jline/jline3) - 包括现代 shell 的功能，如完成或历史.
- [JOpt Simple](https://jopt-simple.github.io/jopt-simple/) - Fluent parser that uses the POSIX#getopt and GNU#getopt_long syntaxes.
- [picocli](https://picocli.info) - ANSI 颜色和样式的使用有助于基于注释的 POSIX/GNU/any 语法、子命令、选项和位置参数的强类型.
- [Text-IO](https://github.com/beryx/text-io) - 帮助创建完整的基于控制台的应用程序.
- [Lanterna](https://github.com/mabe02/lanterna)  - 简单的控制台文本图形用户界面库，类似于诅咒.  （仅限 LGPL-3.0）

### Cluster Management

_可以动态管理集群内应用程序的框架._

- [Apache Aurora](https://aurora.apache.org) - 用于长期运行的服务和 cron 作业的 Mesos 框架.
- [Singularity](http://getsingularity.com)  - 使部署和操作变得简单的 Mesos 框架. 它支持 Web 服务、后台工作者、计划作业和一次性任务.

### Code Analysis

_提供指标和质量测量的工具._

- [Checkstyle](https://github.com/checkstyle/checkstyle)  - 编码约定和标准的静态分析.  （LGPL-2.1 或更高版本）
- [Error Prone](https://github.com/google/error-prone) - 捕获常见的编程错误作为编译时错误.
- [Infer](https://github.com/facebook/infer) - 用于验证代码正确性的现代静态分析工具.
- [jQAssistant](https://jqassistant.org)  - 使用基于 Neo4J 的查询语言进行静态代码分析.  （仅限 GPL-3.0）
- [NullAway](https://github.com/uber/NullAway) - 以低构建时间开销消除 NullPointerExceptions.
- [PMD](https://github.com/pmd/pmd) - 用于查找不良编码实践的源代码分析.
- [SonarJava](https://github.com/SonarSource/sonar-java)  - SonarQube 和 SonarLint 的静态分析器.  （仅限 LGPL-3.0）
- [Sourcetrail](https://www.sourcetrail.com) - 可视化源代码导航器.
- [Spoon](https://github.com/INRIA/spoon) - 用于分析和转换 Java 源代码的库.
- [Spotbugs](https://github.com/spotbugs/spotbugs)  - 字节码的静态分析以发现潜在的错误.  （仅限 LGPL-2.1）

### Code Coverage

_为测试套件启用代码覆盖率指标收集的框架和工具._

- [Clover](https://www.atlassian.com/software/clover) - 依赖于源代码检测而不是字节码检测.
- [Cobertura](https://cobertura.github.io/cobertura/)  - 依靠离线（或静态）字节码检测和类加载来收集代码覆盖率指标.  （仅限 GPL-2.0）
- [JaCoCo](https://www.eclemma.org/jacoco/) - 支持使用离线和运行时字节码检测来收集代码覆盖率指标的框架.

### Code Generators

_为重复代码生成模式以减少冗长和容易出错的工具._

- [ADT4J](https://github.com/sviperll/adt4j) - 代数数据类型的 JSR-269 代码生成器.
- [Auto](https://github.com/google/auto) - 生成工厂、服务和值类.
- [Bootify ![c]](https://bootify.io) - 使用 JPA 模型和 REST API 生成基于浏览器的 Spring Boot 应用程序.
- [FreeBuilder](https://github.com/inferred/FreeBuilder) - 自动生成构建器模式.
- [Immutables](https://immutables.github.io) - 用于生成简单、安全和一致的值对象的注释处理器.
- [JavaPoet](https://github.com/square/javapoet) - 用于生成源文件的 API.
- [JHipster](https://github.com/jhipster/generator-jhipster) - 用于 Spring Boot 和 AngularJS 的 Yeoman 源代码生成器.
- [Joda-Beans](https://www.joda.org/joda-beans/) - 向 Java 添加可查询属性的小型框架，增强了 JavaBeans.
- [Lombok](https://projectlombok.org) - 旨在减少冗长的代码生成器.
- [Telosys](https://www.telosys.org/) - 简单轻便的代码生成器可作为 Eclipse 插件和 CLI 使用.

### Compiler-compiler

_帮助创建解析器、解释器或编译器的框架._

- [ANTLR](https://www.antlr.org) - 用于自顶向下解析的复杂的全功能框架.
- [JavaCC](https://javacc.github.io/javacc/)  - 生成自顶向下解析器的解析器生成器. 允许词法状态切换并允许扩展 BNF 规范.
- [JFlex](https://jflex.de) - 词法分析器生成器.

### Computer Vision

_寻求从图像和视频中获取高级信息的图书馆._

- [BoofCV](https://boofcv.org) - 用于图像处理、相机校准、跟踪、SFM、MVS、3D 视觉、二维码等的库.
- [ImageJ](https://imagej.net/ImageJ) - 带有 API 的医学图像处理应用程序.
- [JavaCV](https://github.com/bytedeco/javacv) - OpenCV、FFmpeg 等的 Java 接口.

### Configuration

_提供外部配置的库._

- [centraldogma](https://github.com/line/centraldogma) - 基于 Git、ZooKeeper 和 HTTP/2 的高可用版本控制服务配置存储库.
- [cfg4j](https://github.com/cfg4j/cfg4j) - 用 Ja​​va 编写的分布式应用程序的现代配置库.
- [config](https://github.com/lightbend/config) - 支持 Java 属性、JSON 或其人工优化超集 HOCON 的配置库.
- [Configurate](https://github.com/SpongePowered/Configurate) - 支持各种配置格式和转换的配置库.
- [dotenv](https://github.com/shyiko/dotenv) - 使用特定于环境的文件的十二因素配置库.
- [ini4j](http://ini4j.sourceforge.net) - 提供用于处理 Windows 的 INI 文件的 API.
- [KAConf](https://github.com/mariomac/kaconf) - 基于注解的 Java 和 Kotlin 配置系统.
- [microconfig](https://microconfig.io)  - 为微服务设计的配置系统，有助于将配置与代码分开. 不同服务的配置可以有共同的和特定的部分，并且可以动态分布.
- [owner](https://github.com/lviggiano/owner) - 减少属性样板.

### Constraint Satisfaction Problem Solver

_帮助实现优化和可满足性问题的库._

- [Choco](https://choco-solver.org) - 使用约束编程技术的现成约束满足问题求解器.
- [JaCoP](https://github.com/radsz/jacop)  - 包括 FlatZinc 语言的接口，使其能够执行 MiniZinc 模型.  (AGPL-3.0)
- [OptaPlanner](https://www.optaplanner.org) - 业务规划和资源调度优化求解器.

### CSV

_简化读取/写入 CSV 数据的框架和库._

- [FastCSV](https://github.com/osiegmar/FastCSV) - 性能优化、无依赖性且符合 RFC 4180.
- [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv) - 用于读取和写入 CSV 的 Jackson 扩展.
- [opencsv](http://opencsv.sourceforge.net) - 简单的 CSV 解析器.
- [Super CSV](https://super-csv.github.io/super-csv/) - 强大的 CSV 解析器，支持 Dozer、Joda-Time 和 Java 8.
- [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers)  - 最快和功能最完整的解析器之一. 还带有用于 TSV 和固定宽度记录的解析器.

### Data Structures

_高效且具体的数据结构._

- [Apache Avro](https://avro.apache.org) - 具有动态类型、未标记数据和没有手动分配 ID 的数据交换格式.
- [Apache Orc](https://orc.apache.org) - 快速高效的列式存储格式，适用于基于 Hadoop 的工作负载.
- [Apache Parquet](https://parquet.apache.org) - 基于谷歌关于 Dremel 论文的汇编算法的列式存储格式.
- [Apache Thrift](https://thrift.apache.org) - 源自 Facebook 的数据交换格式.
- [Big Queue](https://github.com/bulldog2011/bigqueue) - 基于内存映射文件的快速持久队列.
- [HyperMinHash-java](https://github.com/LiveRamp/HyperMinHash-java) - 用于计算日志空间中并集、交集和集合基数的概率数据结构.
- [Persistent Collection](https://github.com/hrldcpr/pcollections) - 持久且不可变的 Java 集合框架类似物.
- [Protobuf](https://github.com/protocolbuffers/protobuf) - 谷歌的数据交换格式.
- [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap) - 快速高效的压缩位图.
- [SBE](https://github.com/real-logic/simple-binary-encoding) - 简单的二进制编码，最快的消息格式之一.
- [Tape](https://github.com/square/tape) - 闪电般快速的、事务性的、基于文件的 FIFO.
- [Wire](https://github.com/square/wire) - 干净、轻量级的协议缓冲区.

### Database

_简化与数据库交互的一切._

- [Apache Calcite](https://calcite.apache.org)  - 动态数据管理框架. 它包含构成典型数据库管理系统的许多部分.
- [Apache Drill](https://drill.apache.org) - 用于大数据探索的分布式、动态模式、ANSI SQL 查询引擎.
- [Apache Phoenix](https://phoenix.apache.org) - 基于 HBase 的高性能关系数据库层，用于低延迟应用程序.
- [AranoDB](https://github.com/arangodb/arangodb-java-driver) - ArangoDB Java 驱动程序.
- [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map) - 高效、内存中（选择持久化到磁盘）、堆外键值存储.
- [Debezium](https://debezium.io/) - 用于更改数据捕获的低延迟数据流平台.
- [druid](https://druid.apache.org) - 高性能、面向列的分布式数据存储.
- [eXist](https://github.com/eXist-db/exist)  - NoSQL 文档数据库和应用平台.  （仅限 LGPL-2.1）
- [FlexyPool](https://github.com/vladmihalcea/flexy-pool) - 为最常见的连接池解决方案带来指标和故障转移策略.
- [Flyway](https://flywaydb.org) - 简单的数据库迁移工具.
- [H2](https://h2database.com) - Small SQL database notable for its in-memory functionality.
- [HikariCP](https://github.com/brettwooldridge/HikariCP) - 高性能 JDBC 连接池.
- [JDBI](http://jdbi.org) - JDBC 的方便抽象.
- [Jedis](https://github.com/xetorthio/jedis) - 与 Redis 交互的小客户端，带有命令方法.
- [Jest](https://github.com/searchbox-io/Jest) - Elasticsearch REST API 的客户端.
- [jetcd](https://github.com/justinsb/jetcd) - etcd 的客户端库.
- [Jinq](https://github.com/my2iu/Jinq) - 通过符号执行 Java 8 Lambdas（在 JPA 或 jOOQ 之上）进行类型安全的数据库查询.
- [jOOQ](https://www.jooq.org) - 基于 SQL 模式生成类型安全代码.
- [Leaf](https://github.com/Meituan-Dianping/Leaf) - 分布式 ID 生成服务.
- [Liquibase](http://www.liquibase.org) - 用于跟踪、管理和应用数据库架构更改的独立于数据库的库.
- [MapDB](http://www.mapdb.org) - 嵌入式数据库引擎，提供支持磁盘或堆外内存的并发集合.
- [MariaDB4j](https://github.com/vorburger/MariaDB4j) - 无需安装或外部依赖项的 MariaDB 启动器.
- [Modality](https://github.com/arkanovicz/modality) - 具有数据库逆向工程功能的轻量级 ORM.
- [Spring Data JPA MongoDB Expressions](https://github.com/mhewedy/spring-data-jpa-mongodb-expressions) - 允许您使用 MongoDB 查询语言来查询您的关系数据库.
- [Trino](https://trino.io) - 用于大数据的分布式 SQL 查询引擎.
- [QueryStream](https://github.com/querystream/querystream) - 使用类似 Stream 的 API 构建 JPA Criteria 查询.
- [Querydsl](http://www.querydsl.com) - 类型安全的统一查询.
- [Realm](https://github.com/realm/realm-java) - 直接在手机、平板电脑或可穿戴设备中运行的移动数据库.
- [Redisson](https://github.com/redisson/redisson) - 允许在 Redis 服务器上使用分布式和可扩展的数据结构.
- [requery](https://github.com/requery/requery)  - 现代、轻量级但功能强大的对象映射和 SQL 生成器. 轻松映射或创建数据库，或从任何使用 Java 的平台执行查询和更新.
- [Speedment](https://github.com/speedment/speedment) - 利用 Java 8 的 Stream API 进行查询的数据库访问库.
- [Vibur DBCP](https://www.vibur.org) - 具有高级性能监控功能的 JDBC 连接池库.
- [Xodus](https://github.com/JetBrains/xodus) - 高并发事务性无架构且符合 ACID 的嵌入式数据库.

### Date and Time

_与处理日期和时间相关的库._

- [Almanac Converter](https://github.com/chrisengelsma/almanac-converter) - 不同日历系统之间的简单转换.
- [iCal4j](https://github.com/ical4j/ical4j) - 解析和构建 iCalendar [RFC 5545](https://tools.ietf.org/html/rfc5545) 数据模型.
- [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra) - 补充 JDK 8 中的日期时间类的其他日期时间类.
- [Time4J](https://github.com/MenoData/Time4J)  - 高级日期和时间库.  （仅限 LGPL-2.1）

### Dependency Injection

_图书馆有助于实现 [Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) 范例._

- [Apache DeltaSpike](https://deltaspike.apache.org) - CDI 扩展框架.
- [Dagger](https://dagger.dev/) - 没有反射的编译时注入框架.
- [Feather](https://github.com/zsoltherpai/feather) - 超轻量级、符合 JSR-330 的依赖注入库.
- [Governator](https://github.com/Netflix/governator) - 增强 Google Guice 的扩展和实用程序.
- [Guice](https://github.com/google/guice) - 完成 Dagger 的轻量级和自以为是的框架.
- [HK2](https://javaee.github.io/hk2/) - 轻量级的动态依赖注入框架.
- [JayWire](https://github.com/vanillasource/jaywire)  - 轻量级依赖注入框架.  （仅限 LGPL-3.0）

### Development

_从根本上加强开发过程._

- [AspectJ](https://www.eclipse.org/aspectj/) - 无缝的面向方面的编程扩展.
- [DCEVM](https://dcevm.github.io)  - JVM 修改，允许在运行时无限制地重新定义加载的类.  （仅限 GPL-2.0）
- [Faux Pas](https://github.com/zalando/faux-pas) - 通过规避默认情况下不允许 Java 运行时中的任何功能接口抛出已检查异常的问题，从而简化错误处理的库.
- [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent)  - 无限制的运行时类和资源重新定义.  （仅限 GPL-2.0）
- [JavaParser](https://github.com/javaparser/javaparser) - 解析、修改和生成 Java 代码.
- [JavaSymbolSolver](https://github.com/javaparser/javasymbolsolver) - 符号求解器.
- [Manifold](https://github.com/manifold-systems/manifold) - 使用类型安全的元编程、结构类型和扩展方法等强大功能重新激活 Java.
- [NoException](https://noexception.machinezoo.com) - 允许在功能接口中检查异常并将异常转换为可选返回.
- [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow)  - 在没有字节码操作的情况下忽略已检查的异常. 也可以在 Java 8 流操作中使用.
- [Tail](https://kag0.github.io/tail) - 使用尾调用优化启用无限递归.

### Distributed Applications

_用于编写分布式和容错应用程序的库和框架._

- [Apache Geode](https://geode.apache.org) - 内存数据管理系统，提供可靠的异步事件通知和有保证的消息传递.
- [Apache Storm](https://storm.apache.org) - 实时计算系统.
- [Apache ZooKeeper](https://zookeeper.apache.org) - 为大型分布式系统提供分布式配置、同步和命名注册表的协调服务.
- [Atomix](https://atomix.io) - 容错分布式协调框架.
- [Axon](https://axoniq.io) - 创建 CQRS 应用程序的框架.
- [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker)  - Dropwizard 的断路器设计模式.  （仅限 GPL-2.0）
- [Failsafe](https://github.com/jhalterman/failsafe) - 使用重试和断路器进行简单的故障处理.
- [Hazelcast](https://github.com/hazelcast/hazelcast) - 具有免费开源版本的高度可扩展的内存数据网格.
- [JGroups](http://www.jgroups.org) - 用于可靠消息传递和集群创建的工具包.
- [Quasar](http://docs.paralleluniverse.co/quasar/) - JVM 的轻量级线程和参与者.
- [resilience4j](https://github.com/resilience4j/resilience4j) - 功能容错库.
- [ScaleCube Services](https://github.com/scalecube/scalecube-services) - 基于 SWIM 和八卦协议的可嵌入集群成员库.
- [Zuul](https://github.com/Netflix/zuul) - 提供动态路由、监控、弹性、安全性等的网关服务.

### Distributed Transactions

_分布式事务提供了一种机制，可在并发访问和部分故障的情况下确保数据更新的一致性._

- [Atomikos](https://www.atomikos.com) - 为 REST、SOA 和微服务提供事务并支持 JTA 和 XA.
- [Bitronix](https://github.com/bitronix/btm) - JTA 1.1 API 的简单但完整的实现.
- [Narayana](https://narayana.io)  - 提供对传统ACID和补偿事务的支持，也符合JTA、JTS等标准.  （仅限 LGPL-2.1）
- [Seata](https://github.com/seata/seata) - 在微服务架构下提供高性能和易于使用的分布式事务服务.

### Distribution

_以原生格式处理应用程序分发的工具._

- [Artipie](https://github.com/artipie/artipie) - 二进制工件管理工具包，将它们托管在文件系统或 S3 上.
- [Boxfuse ![c]](https://boxfuse.com) - 使用不可变基础设施的原则将 JVM 应用程序部署到 AWS.
- [Capsule](https://github.com/puniverse/capsule)  - 简单而强大的打包和部署. 类固醇上的胖 JAR，或支持 JVM 优化容器的“Docker for Java”.
- [Central Repository](https://search.maven.org)  - 最大的二进制组件存储库作为开源社区的免费服务提供.  Apache Maven 使用的默认值，并在所有其他构建工具中可用.
- [Cloudsmith ![c]](https://cloudsmith.io) - 完全托管的包管理 SaaS，支持 Maven/Gradle/SBT 和免费层.
- [Getdown](https://github.com/threerings/getdown) - A system for deploying Java applications to end-user computers and keeping them up to date. Developed as an alternative to Java Web Start.
- [IzPack](http://izpack.org) - 为跨平台部署设置创作工具.
- [JavaPackager](https://github.com/fvarrui/JavaPackager) - Maven 和 Gradle 插件，它提供了一种在原生 Windows、Mac OS X 或 GNU/Linux 可执行文件中打包 Java 应用程序并为它们生成安装程序的简单方法.
- [jlink.online](https://github.com/cilki/jlink.online) - 通过 HTTP 构建优化的运行时.
- [Nexus ![c]](https://www.sonatype.com) - 具有代理和缓存功能的二进制管理.
- [packr](https://github.com/libgdx/packr) - 为 Windows、Linux 和 macOS 上的本机分发打包 JAR、资产和 JVM.
- [really-executable-jars-maven-plugin](https://github.com/brianm/really-executable-jars-maven-plugin) - 用于制作自执行 JAR 的 Maven 插件.

### Document Processing

_协助处理办公文件格式的图书馆._

- [Apache POI](https://poi.apache.org) - 支持 OOXML（XLSX、DOCX、PPTX）以及 OLE2（XLS、DOC 或 PPT）.
- [documents4j](https://documents4j.com/#/) - 使用第三方转换器（如 MS Word）进行文档格式转换的 API.
- [docx4j](https://www.docx4java.org/trac/docx4j) - 创建和操作 Microsoft Open XML 文件.
- [fastexcel](https://github.com/dhatim/fastexcel) - 用于读取和写入大型 Excel (XLSX) 工作表的高性能库.
- [zerocell](https://github.com/creditdatamw/zerocell) - 基于注释的 API，用于将数据从 Excel 工作表读取到 POJO 中，重点是减少开销.

### Financial

_金融领域相关图书馆._

- [Parity](https://github.com/paritytrading/parity) - 交易场所平台.
- [Philadelphia](https://github.com/paritytrading/philadelphia) - 低延迟的金融信息交换.
- [Square](https://github.com/square/connect-java-sdk) - 与 Square API 集成.
- [Stripe](https://github.com/stripe/stripe-java) - 与 Stripe API 集成.
- [ta4j](https://github.com/ta4j/ta4j) - 技术分析库.

### Formal Verification

_形式化方法工具：证明助手、模型检查、符号执行等_

- [CATG](https://github.com/ksen007/janala2)  - Concolic 单元测试引擎. 使用形式化方法自动生成单元测试.
- [Checker Framework](https://checkerframework.org)  - 可插拔类型系统. 包括空值类型、物理单位、不变性类型等.  (GPL-2.0-only WITH Classpath-exception-2.0)
- [Daikon](https://plse.cs.washington.edu/daikon/) - 检测可能的程序不变量并根据这些不变量生成 JML 规范.
- [Java Path Finder (JPF)](https://github.com/javapathfinder/jpf-core)  - 包含模型检查器等的 JVM 形式验证工具. 由美国宇航局创建.
- [JMLOK 2.0](https://massoni.computacao.ufcg.edu.br/home/jmlok) - Detects inconsistencies between code and JML specification through feedback-directed random tests generation, and suggests a likely cause for each nonconformance detected. (GPL-3.0-only)
- [KeY](https://www.key-project.org)  - 正式软件开发工具，旨在尽可能无缝地集成面向对象软件的设计、实现、正式规范和形式验证. 使用 JML 进行规范和符号执行进行验证.  （GPL-2.0 或更高版本）
- [OpenJML](http://www.openjml.org)  - 将 JML 规范转换为 SMT-LIB 格式，并将程序隐含的证明问题传递给后端求解器.  （仅限 GPL-2.0）

### Functional Programming

_促进函数式编程的库._

- [Cyclops](https://github.com/aol/cyclops) - Monad and stream utilities, comprehensions, pattern matching, functional extensions for all JDK collections, future streams, trampolines and much more.
- [derive4j](https://github.com/derive4j/derive4j)  - 用于派生代数数据类型构造函数、模式匹配和态射的 Java 8 注释处理器和框架.  （仅限 GPL-3.0）
- [Fugue](https://bitbucket.org/atlassian/fugue) - 对番石榴的功能扩展.
- [Functional Java](http://www.functionaljava.org) - 实现了许多有助于面向组合开发的基本和高级编程抽象.
- [jOOλ](https://github.com/jOOQ/jOOL) - Java 8 的扩展，旨在通过提供大量缺失的类型和一组丰富的顺序 Stream API 添加来修复 lambda 中的差距.
- [protonpack](https://github.com/poetix/protonpack) - 流实用程序的集合.
- [StreamEx](https://github.com/amaembo/streamex) - 增强了 Java 8 Streams.
- [Vavr](https://www.vavr.io) - 提供持久数据类型和功能控制结构的功能组件库.

### Game Development

_支持游戏开发的框架._

- [FXGL](https://almasb.github.io/FXGL/) - JavaFX 游戏开发框架.
- [JBox2D](http://www.jbox2d.org/) - 著名的 C++ 2D 物理引擎的端口.
- [jMonkeyEngine](https://jmonkeyengine.org) - 用于现代 3D 开发的游戏引擎.
- [libGDX](https://libgdx.com) - 全方位跨平台，高层框架.
- [Litiengine](https://litiengine.com/) - 基于 AWT 的轻量级 2D 游戏引擎.
- [LWJGL](https://www.lwjgl.org) - 强大的框架，可以抽象 OpenGL/CL/AL 等库.
- [Mini2Dx](https://mini2dx.org) - 初学者友好型，大师级框架，用于快速原型制作和构建 2D 游戏.

### Geospatial

_用于处理地理空间数据和算法的库._

- [Apache SIS](https://sis.apache.org) - 用于开发地理空间应用程序的库.
- [Geo](https://github.com/davidmoten/geo) - Java 中的 GeoHash 实用程序.
- [GeoTools](https://geotools.org)  - 为地理空间数据提供工具的库.  （仅限 LGPL-2.1）
- [GraphHopper](https://github.com/graphhopper/graphhopper)  - 道路路由引擎. 用作 Java 库或独立 Web 服务.
- [H2GIS](http://www.h2gis.org)  - H2 数据库的空间扩展.  （仅限 LGPL-3.0）
- [Jgeohash](https://astrapi69.github.io/jgeohash/) - 使用 GeoHash 算法的库.
- [Mapsforge](https://github.com/mapsforge/mapsforge)  - 基于 OpenStreetMap 数据的地图渲染.  （仅限 LGPL-3.0）
- [Spatial4j](https://github.com/locationtech/spatial4j) - 通用空间/地理空间库.

### GUI

_用于创建现代图形用户界面的库._

- [JavaFX](https://wiki.openjdk.java.net/display/OpenJFX/Main) - Swing的继任者.
- [Scene Builder](https://gluonhq.com/products/scene-builder/) - JavaFX 应用程序的可视化布局工具.
- [SWT](https://www.eclipse.org/swt/) - 图形小部件工具包.

### High Performance

_关于高性能计算的一切，从集合到特定库._

- [Agrona](https://github.com/real-logic/Agrona) - 高性能应用程序中常见的数据结构和实用方法.
- [Disruptor](https://lmax-exchange.github.io/disruptor/) - 线程间消息传递库.
- [Eclipse Collections](https://github.com/eclipse/eclipse-collections) - 受 Smalltalk 启发的集合框架.
- [fastutil](http://fastutil.di.unimi.it) - 快速且紧凑的特定于类型的集合.
- [HPPC](https://labs.carrotsearch.com/hppc.html) - 原始收藏.
- [JCTools](https://github.com/JCTools/JCTools) - JDK 中目前缺少并发工具.
- [Koloboke](https://github.com/leventov/Koloboke) - 精心设计的 Java Collections Framework 扩展，具有原始专业化等等.

### HTTP Clients

_帮助创建 HTTP 请求和/或绑定响应的库._

- [Apache HttpComponents](https://hc.apache.org/) - 专注于 HTTP 和相关协议的低级 Java 组件工具集.
- [Async Http Client](https://github.com/AsyncHttpClient/async-http-client) - 异步 HTTP 和 WebSocket 客户端库.
- [Feign](https://github.com/OpenFeign/feign) - 受 Retrofit、JAXRS-2.0 和 WebSocket 启发的 HTTP 客户端绑定器.
- [Google HTTP Client](https://github.com/googleapis/google-http-java-client) - 可插入的 HTTP 传输抽象，支持 java.net.HttpURLConnection、Apache HTTP 客户端、Android、Google App Engine、XML、Gson、Jackson 和 Protobuf.
- [methanol](https://github.com/mizosoft/methanol) - HTTP 客户端扩展库.
- [restQL-java](https://github.com/b2wdigital/restQL-java) - 从多个服务中获取信息的微服务查询语言.
- [Retrofit](https://square.github.io/retrofit/) - 类型安全的 REST 客户端.
- [Ribbon](https://github.com/Netflix/ribbon) - 在云中经过实战测试的客户端 IPC 库.
- [Riptide](https://github.com/zalando/riptide) - Spring 的 RestTemplate 的客户端响应路由.
- [unirest-java](https://github.com/Kong/unirest-java) - 简化、轻量级的 HTTP 客户端库.

### Hypermedia Types

_处理超媒体类型序列化的库._

- [hate](https://github.com/blackdoor/hate) - 根据 HAL 规范构建超媒体友好对象.
- [JSON-LD](https://github.com/jsonld-java/jsonld-java) - JSON-LD 实现.
- [Siren4J](https://github.com/eserating-chwy/siren4j) - Siren 规范的库.

### IDE

_试图简化开发的几个方面的集成开发环境._

- [Eclipse](https://www.eclipse.org) - 建立了支持大量插件和语言的开源项目.
- [IntelliJ IDEA ![c]](https://www.jetbrains.com/idea/) - Supports many JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.
- [jGRASP](https://www.jgrasp.org) - Created to provide software visualizations that work in conjunction with the debugger such as Control Structure Diagrams, UML class diagrams and Object Viewer.
- [NetBeans](https://netbeans.apache.org) - 为多个 Java SE 和 EE 功能提供集成，从数据库访问到 HTML5.
- [Recaf](https://www.coley.software/Recaf/) - 字节码编辑器.
- [Visual Studio Code](https://code.visualstudio.com/docs/languages/java) - 通过使用来自内部市场的扩展，以简单、现代的工作流程为轻量级项目提供 Java 支持.

### Imagery

_帮助创建、评估或处理图形图像的库._

- [Imgscalr](https://github.com/rkalla/imgscalr) - 在纯 Java 2D 中实现的简单、高效和硬件加速的图像缩放库.
- [Tess4J](https://github.com/nguyenq/tess4j) - Tesseract OCR API 的 JNA 包装器.
- [Thumbnailator](https://github.com/coobird/thumbnailator) - 高质量的缩略图生成库.
- [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys) - 扩展支持的图像文件格式数量的插件集合.
- [ZXing](https://github.com/zxing/zxing) - 多格式一维/二维条码图像处理库.
- [image-comparison](https://github.com/romankh3/image-comparison)  - 比较具有相同大小的 2 个图像并通过绘制矩形直观地显示差异的库. 图像的某些部分可以从比较中排除. 可用于自动化 qa 测试.

### Introspection

_有助于使 Java 内省和反射 API 更容易和更快使用的库._

- [ClassGraph](https://github.com/classgraph/classgraph) - ClassGraph（以前称为 FastClasspathScanner）是用于 Java、Scala、Kotlin 和其他 JVM 语言的超快速、超轻量级、并行化类路径扫描器和模块扫描器.
- [jOOR](https://github.com/jOOQ/jOOR)  - jOOR 代表 jOOR 面向对象的反射. 它是 java.lang.reflect 包的简单包装器.
- [Mirror](http://projetos.vidageek.net/mirror/mirror/) - 创建 Mirror 是为了解决一个简单的问题，通常称为 ReflectionUtil，几乎所有依赖反射来完成高级任务的项目都使用它.
- [Objenesis](http://objenesis.org) - 允许在没有默认构造函数的情况下动态实例化，例如具有必需参数、副作用或抛出异常的构造函数.
- [ReflectASM](https://github.com/EsotericSoftware/reflectasm) - ReflectASM 是一个非常小的 Java 库，它通过使用代码生成来提供高性能的反射.
- [Reflections](https://github.com/ronmamo/reflections) - 反射扫描你的类路径，索引元数据，允许你在运行时查询它，并可以保存和收集项目中许多模块的信息.

### Job Scheduling

_用于调度后台作业的库._

- [JobRunr](https://github.com/jobrunr/jobrunr)  - 作业调度库，它利用 lambdas 进行即发即忘、延迟和重复性作业. 使用乐观锁定保证单个调度程序实例的执行. 具有持久性、最小依赖性和可嵌入的特性.
- [Quartz](https://github.com/quartz-scheduler/quartz) - 功能丰富的开源作业调度库，几乎可以集成到任何 Java 应用程序中.
- [Sundial](https://github.com/knowm/Sundial) - 简单定义作业、定义触发器和启动调度程序的轻量级框架.
- [Wisp](https://github.com/Coreoz/Wisp) - 具有最小占用空间和简单 API 的简单库.
- [db-scheduler](https://github.com/kagkarlsson/db-scheduler) - 持久且集群友好的调度程序.
- [easy-batch](https://github.com/j-easy/easy-batch)  - 使用简单的处理管道设置批处理作业. 记录从数据源按顺序读取，在管道中处理并批量写入数据接收器.
- [shedlock](https://github.com/lukas-krecan/ShedLock)  - 确保您的计划任务最多同时执行一次. 如果一个任务正在一个节点上执行，它会获取一个锁，以防止从另一个节点或线程执行相同的任务.

### JSON

_用于在 Java 对象之间序列化和反序列化 JSON 的库._

- [DSL-JSON](https://github.com/ngs-doo/dsl-json) - 具有高级编译时数据绑定的 JSON 库.
- [Genson](http://genson.io) - 强大且易于使用的 Java 到 JSON 转换库.
- [Gson](https://github.com/google/gson)  - 将对象序列化为 JSON，反之亦然. 即时使用的良好性能.
- [HikariJSON](https://github.com/brettwooldridge/HikariJSON) - 高性能 JSON 解析器，比 Jackson 快 2 倍.
- [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8) - 用于 Java 8 数据类型和功能的 Jackson 模块集.
- [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money) - 开源 Jackson 模块，支持 JavaMoney 数据类型的 JSON 序列化和反序列化.
- [Jackson](https://github.com/FasterXML/jackson) - 与 GSON 类似，但如果您需要更频繁地实例化库，则可以提高性能.
- [JSON-io](https://github.com/jdereg/json-io)  - 将 Java 转换为 JSON. 将 JSON 转换为 Java. 漂亮的打印 JSON.  Java JSON 序列化程序.
- [jsoniter](http://jsoniter.com) - 具有迭代器和惰性解析 API 的快速灵活的库.
- [LoganSquare](https://github.com/bluelinelabs/LoganSquare)  - 基于 Jackson 的流 API 的 JSON 解析和序列化库. 优于 GSON &amp; Jackson 的库.
- [Moshi](https://github.com/square/moshi) - 现代 JSON 库，较少自以为是并使用内置类型，如 List 和 Map.
- [Yasson](https://github.com/eclipse-ee4j/yasson) - 类和 JSON 文档之间的绑定层，类似于 JAXB.
- [fastjson](https://github.com/alibaba/fastjson) - 非常快的处理器，没有额外的依赖和完整的数据绑定.
- [Jolt](https://github.com/bazaarvoice/jolt) - JSON 到 JSON 转换工具.
- [JsonPath](https://github.com/json-path/JsonPath) - 使用类似 XPATH 的语法从 JSON 中提取数据.
- [JsonSurfer](https://github.com/jsurfer/JsonSurfer) - 专门用于处理大而复杂的 JSON 数据的流式 JsonPath 处理器.

### JVM and JDK

_JVM/JDK 的当前实现._

- [Adopt Open JDK](https://adoptopenjdk.net) - 社区驱动的 OpenJDK 构建，包括 HotSpot 和 OpenJ9.
- [Avian](https://github.com/ReadyTalk/avian) - 带有 JIT、AOT 模式和 iOS 端口的 JVM.
- [Corretto](https://aws.amazon.com/corretto/)  - 亚马逊提供的免费、多平台、生产就绪的 OpenJDK 发行版.  (GPL-2.0-only WITH Classpath-exception-2.0)
- [Dragonwell8](https://github.com/alibaba/dragonwell8) - 针对在线电子商务、金融、物流应用优化的 OpenJDK 下游版本.
- [Graal](https://github.com/oracle/graal)  - 多语言可嵌入 JVM.  (GPL-2.0-only WITH Classpath-exception-2.0)
- [Liberica JDK](https://bell-sw.com)  - 基于 OpenJDK 构建，经过全面测试并通过了 JCK.  (GPL-2.0-only WITH Classpath-exception-2.0)
- [OpenJ9](https://github.com/eclipse/openj9) - 高性能、企业级、灵活许可、开放管理的跨平台 JVM，扩展和增强了来自 Eclipse OMR 和 OpenJDK 项目的运行时技术组件.
- [Open JDK](https://openjdk.java.net)  - 打开 JDK 社区主页.  (GPL-2.0-only WITH Classpath-exception-2.0)
- [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm)  - 适用于 iOS 的具有非阻塞并发 GC 的 VM.  (GPL-2.0-only WITH Classpath-exception-2.0)
- [RedHat Open JDK](https://developers.redhat.com/products/openjdk/overview)  - RedHat 的 OpenJDK 发行版.  (GPL-2.0-only WITH Classpath-exception-2.0)
- [SAP Machine](https://sap.github.io/SapMachine/)  - SAP 的免费、经过严格测试和 JCK 验证的 OpenJDK 友好分支.  (GPL-2.0-only WITH Classpath-exception-2.0)
- [Zulu](https://www.azul.com/products/zulu-community/)  - OpenJDK 为 Windows、Linux 和 macOS 构建.  (GPL-2.0-only WITH Classpath-exception-2.0)

### Logging

_记录应用程序行为的库._

- [Apache Log4j 2](https://logging.apache.org/log4j/) - 使用强大的插件和配置架构完全重写.
- [Graylog](https://www.graylog.org)  - 适用于扩展角色和权限管理的开源聚合器.  （仅限 GPL-3.0）
- [Kibana](https://www.elastic.co/kibana)  - 分析和可视化日志文件. 某些功能需要付费.
- [Logback](http://logback.qos.ch) - 强大的日志库，通过 Groovy 提供有趣的配置选项.
- [Logbook](https://github.com/zalando/logbook) - 用于 HTTP 请求和响应日志记录的可扩展开源库.
- [Logstash](https://www.elastic.co/logstash) - 管理日志文件的工具.
- [p6spy](https://github.com/p6spy/p6spy) - 无需更改代码即可为所有 JDBC 事务启用日志记录.
- [SLF4J](http://www.slf4j.org) - 抽象层/简单的日志外观.
- [tinylog](https://tinylog.org/v2/) - 带有静态记录器类的轻量级日志框架.
- [OpenTracing Toolbox](https://github.com/zalando/opentracing-toolbox) - 建立在 OpenTracing 之上并为现有仪器提供扩展和插件的库集合.

### Machine Learning

_提供特定统计算法以从数据中学习的工具._

- [Apache Flink](https://flink.apache.org) - 快速、可靠、大规模的数据处理引擎.
- [Apache Mahout](https://mahout.apache.org) - 专注于协同过滤、聚类和分类的可扩展算法.
- [DatumBox](http://www.datumbox.com) - 为自然语言处理提供多种算法和预训练模型.
- [Deeplearning4j](https://deeplearning4j.org) - 分布式和多线程深度学习库.
- [DJL](https://djl.ai) - 用于深度学习的高级且与引擎无关的框架.
- [H2O ![c]](https://www.h2o.ai) - 大数据统计分析引擎.
- [JSAT](https://github.com/EdwardRaff/JSAT)  - 支持多线程执行的预处理、分类、回归和聚类算法.  （仅限 GPL-3.0）
- [oj! Algorithms](https://www.ojalgo.org/) - 数据科学、机器学习和科学计算所需的高性能数学、线性代数和优化.
- [Oryx 2](https://github.com/OryxProject/oryx)  - 构建实时、大规模机器学习应用程序的框架. 包括用于协同过滤、分类、回归和聚类的端到端应用程序.
- [Siddhi](https://github.com/siddhi-io/siddhi) - 云原生流媒体和复杂的事件处理引擎.
- [Smile](https://github.com/haifengl/smile) - 统计机器智能和学习引擎提供了一组机器学习算法和一个可视化库.
- [Tribuo](https://tribuo.org/) - 提供用于分类、回归、聚类、模型开发的工具以及与其他库（如 scikit-learn、pytorch 和 TensorFlow）的接口.
- [Weka](https://www.cs.waikato.ac.nz/ml/weka/)  - 用于从预处理到可视化的数据挖掘任务的算法集合.  （仅限 GPL-3.0）

### Messaging

_帮助在客户端之间发送消息以确保协议独立性的工具._

- [Aeron](https://github.com/real-logic/Aeron) - 高效、可靠、单播和多播消息传输.
- [Apache ActiveMQ](https://activemq.apache.org) - 实现 JMS 并将同步通信转换为异步通信的消息代理.
- [Apache Camel](https://camel.apache.org) - 通过企业集成模式将不同的传输 API 粘合在一起.
- [Apache Kafka](https://kafka.apache.org) - 高吞吐量分布式消息传递系统.
- [Apache Pulsar](https://pulsar.apache.org) - 分布式发布/子消息系统.
- [Apache RocketMQ](https://rocketmq.apache.org) - 快速、可靠且可扩展的分布式消息传递平台.
- [Apache Qpid](https://qpid.apache.org) - Apache Qpid 制作使用 AMQP 并支持多种语言和平台的消息传递工具.
- [EventBus](https://github.com/greenrobot/EventBus) - 简单的发布/订阅事件总线.
- [Hermes](http://hermes.allegro.tech) - 建立在 Kafka 之上的快速可靠的消息代理.
- [JeroMQ](https://github.com/zeromq/jeromq) - ZeroMQ 的实现.
- [Nakadi](https://github.com/zalando/nakadi) - 在 Kafka 之上提供 RESTful API.
- [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client) - RabbitMQ 客户端.
- [Smack](https://github.com/igniterealtime/Smack) - 跨平台 XMPP 客户端库.
- [NATS client](https://github.com/nats-io/nats.java) - NATS 客户端.

### Microservice

_用于创建和管理微服务的工具._

- [ActiveRPC](https://rpc.activej.io) - 用于复杂的高负载分布式应用程序和类似 Memcached 的解决方案的轻量级和快速库.
- [Apollo](https://spotify.github.io/apollo/) - 用于编写可组合微服务的库.
- [Armeria](https://github.com/line/armeria) - 建立在 Java 8、Netty、HTTP/2、Thrift 和 gRPC 之上的异步 RPC/REST 客户端/服务器库.
- [consul-api](https://github.com/Ecwid/consul-api) - Consul API 客户端：分布式、高可用性和数据中心感知的注册/发现服务.
- [Eureka](https://github.com/Netflix/eureka) - 基于 REST 的服务注册表，用于弹性负载平衡和故障转移.
- [Helidon](https://helidon.io) - 两种编写微服务的方法：功能反应式和作为 MicroProfile 的实现.
- [Micronaut](https://micronaut.io) - 专注于模块化、最小内存占用和启动时间的现代全栈框架.
- [Nacos](https://nacos.io) - 用于构建云原生应用程序的动态服务发现、配置和服务管理平台.
- [Quarkus](https://quarkus.io) - 为 HotSpot 和 Graal VM 量身定制的 Kubernetes 堆栈.
- [Sentinel](https://github.com/alibaba/Sentinel) - 流量控制组件可实现微服务的可靠性、弹性和监控.

### Miscellaneous

_其他一切._

- [CQEngine](https://github.com/npgall/cqengine) - 对 Java 集合的超快速、类似 SQL 的查询.
- [Design Patterns](https://github.com/iluwatar/java-design-patterns) - 最常见的设计模式的实现和解释.
- [FF4J](https://github.com/ff4j/ff4j) - Java 的功能标志.
- [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition)  - 严肃的商人为严肃的商业目的制作的 FizzBu​​zz 的严肃实施.  （无明确许可）
- [J2ObjC](https://github.com/google/j2objc) - 用于将 Android 库移植到 iOS 的 Java-to-Objective-C 转换器.
- [JBake](https://jbake.org) - 静态网站生成器.
- [JBot](https://github.com/rampatra/jbot)  - 构建聊天机器人的框架.  （仅限 GPL-3.0）
- [JCuda](http://jcuda.org) - JCuda 为 CUDA 和 CUDA 相关库提供 Java 绑定.
- [Jimfs](https://github.com/google/jimfs) - 内存文件系统.
- [Joda-Money](https://www.joda.org/joda-money/) - JDK 未提供的基本货币和货币类和算法.
- [JPad](http://jpad.io) - 片段赛跑者.
- [jsweet](https://github.com/cincheo/jsweet) - 到 TypeScript/JavaScript 的源代码转换器.
- [Maven Wrapper](https://github.com/takari/maven-wrapper) - 类似于 Maven 的 Gradle Wrapper，允许在不安装 Maven 的情况下构建项目.
- [Membrane Service Proxy](https://github.com/membrane/service-proxy) - 开源的反向代理框架.
- [MinimalFTP](https://github.com/Guichaguri/MinimalFTP) - 轻量级、小型和可定制的 FTP 服务器.
- [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial) - 流行的 Java 8 指南.
- [Modernizer](https://github.com/gaul/modernizer-maven-plugin) - 检测遗留 Java API 的使用.
- [OctoLinker](https://github.com/OctoLinker/OctoLinker) - 浏览器扩展允许更有效地浏览 GitHub 上的代码.
- [OpenRefine](http://openrefine.org) - 处理杂乱数据的工具：清理、转换、使用 Web 服务扩展它并将其链接到数据库.
- [PipelinR](https://github.com/sizovs/pipelinr) - 用于将处理程序和命令与管道一起使用的小型实用程序库.
- [Polyglot for Maven](https://github.com/takari/polyglot-maven) - Maven 3.3.1+ 的扩展，允许用 XML 以外的方言编写 POM 模型.
- [Simple Java Mail](https://github.com/bbottema/simple-java-mail) - 使用干净流畅的 API 发送邮件.
- [Smooks](https://github.com/smooks/smooks)  - 基于片段的消息处理框架.  （Apache-2.0 或 LGPL-3.0 或更高版本）
- [Togglz](https://www.togglz.org) - 功能切换模式的实现.
- [TypeTools](https://github.com/jhalterman/typetools) - 用于解析泛型类型的工具.
- [XMLBeam](https://github.com/SvenEwald/xmlbeam) - 通过在代码中使用注释或 XPath 处理 XML.
- [yGuard](https://github.com/yWorks/yGuard) - 通过重命名和缩小进行混淆.

### Mobile Development

_用于创建或管理移动应用程序的工具._

- [Codename One](https://www.codenameone.com)  - 用于编写本机移动应用程序的跨平台解决方案.  (GPL-2.0-only WITH Classpath-exception-2.0)
- [MobileUI](https://mobileui.dev) - 用于在 Java 和 Kotlin 中使用本机 UI 开发移动应用程序的跨平台框架.
- [Multi-OS Engine](https://multi-os-engine.org) - 用于开发原生移动（iOS、Android 等）应用程序的开源跨平台引擎.

### Monitoring

_监控生产应用程序的工具._

- [Automon](https://github.com/stevensouza/automon) - 将 AOP 的强大功能与监控和/或日志记录工具相结合.
- [Failsafe Actuator](https://github.com/zalando/failsafe-actuator) - 在 Spring-Boot 环境中对故障安全断路器进行开箱即用的监控.
- [Glowroot](https://glowroot.org) - 开源 Java APM.
- [inspectIT](https://www.inspectit.rocks)  - 通过可以动态更改的钩子捕获详细的运行时信息. 它支持通过 OpenTracing API 跟踪多个系统，并且可以将数据与最终用户监控相关联.
 - [Instrumental ![c]](https://instrumentalapp.com) - 实时 Java 应用程序性能监控. 具有免费开发帐户的商业服务.
- [JavaMelody](https://github.com/javamelody/javamelody) - 性能监控和分析.
- [Jaeger client](https://github.com/jaegertracing/jaeger-client-java) - Jaeger 客户.
- [jmxtrans](https://github.com/jmxtrans/jmxtrans)  - 连接到多个 JVM 并通过 JMX 查询它们的属性. 它的查询语言基于 JSON，它允许非 Java 程序员访问 JVM 属性. 支持不同的输出写入，包括 Graphite、Ganglia 和 StatsD.
- [Jolokia](https://jolokia.org) - 基于 REST 的 JMX.
- [Metrics](https://github.com/dropwizard/metrics) - 通过 JMX 或 HTTP 公开指标并将它们发送到数据库.
- [Datadog ![c]](https://github.com/DataDog/dd-trace-java) - 现代监控和分析.
- [nudge4j](https://github.com/lorenzoongithub/nudge4j) - 通过字节码注入从 Java 8 浏览器远程开发者控制台.
- [Pinpoint](https://github.com/naver/pinpoint) - 开源 APM 工具.
- [Prometheus](https://github.com/prometheus/client_java) - 提供多维数据模型、DSL、自治服务器节点等等.
- [SPM ![c]](https://github.com/sematext/sematext-agent-java) - 为 JVM 应用程序分发事务跟踪的性能监视器.
- [Stagemonitor](https://github.com/stagemonitor/stagemonitor) - JVM 应用程序的开源性能监控和事务跟踪.
- [Sysmon](https://github.com/palantir/Sysmon) - Java VM 的轻量级平台监控工具.
- [zipkin](https://zipkin.io) - 分布式跟踪系统，用于收集解决微服务架构中的延迟问题所需的计时数据.

### Native

_用于使用特定于平台的本机库._

- [Aparapi](https://github.com/Syncleus/aparapi) - 将字节码转换为 OpenCL，允许在 GPU 上执行.
- [JavaCPP](https://github.com/bytedeco/javacpp) - 提供对本机 C++ 的高效和轻松访问.
- [JNA](https://github.com/java-native-access/jna)  - 无需编写 JNI 即可使用本机库. 还提供通用系统库的接口.
- [JNR](https://github.com/jnr/jnr-ffi)  - 无需编写 JNI 即可使用本机库. 还提供通用系统库的接口. 与 JNA 的目标相同，但速度更快，并为即将到来 [Project Panama](http://openjdk.java.net/projects/panama).

### Natural Language Processing

_专门处理文本的库._

- [CogCompNLP](https://github.com/CogComp/cogcomp-nlp)  - 为纯文本输入提供通用注释器.  （研究和学术使用许可）
- [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml)  - 为标记、命名实体识别和情感分析等任务提供一组基本工具.  （GPL-3.0 或更高版本）
- [DKPro](https://dkpro.github.io) - 用于语言预处理、机器学习、词汇资源等的可重用 NLP 工具的集合.
- [LingPipe](http://alias-i.com/lingpipe/) - 用于从 POS 标记到情感分析等任务的工具包.

### Networking

_用于构建网络服务器的库._

- [Commons-networking](https://github.com/CiscoSE/commons-networking) - 服务器发送事件的客户端 (SSE).
- [Comsat](https://github.com/puniverse/comsat) - 将标准 Java Web 相关 API 与 Quasar 光纤和参与者集成.
- [Dubbo](https://github.com/apache/dubbo) - 高性能 RPC 框架.
- [Grizzly](https://javaee.github.io/grizzly/)  - 蔚来框架. 在 Glassfish 中用作网络层.
- [gRPC](https://github.com/grpc/grpc-java) - 基于 protobuf 和 HTTP/2 的 RPC 框架.
- [KryoNet](https://github.com/EsotericSoftware/kryonet) - 为使用 NIO 和 Kryo 的高效 TCP 和 UDP 客户端/服务器网络通信提供干净简单的 API.
- [MINA](https://mina.apache.org) - 抽象的、事件驱动的异步 I/O API，用于通过 Java NIO 通过 TCP/IP 和 UDP/IP 进行网络操作.
- [Netty](https://netty.io) - 构建高性能网络应用程序的框架.
- [Drift](https://github.com/airlift/drift) - 易于使用、基于注释的库，用于创建 Thrift 客户端和可序列化类型.
- [ServiceTalk](https://github.com/apple/servicetalk) - 基于 Netty 构建的框架，具有针对特定协议定制的 API，并支持多种编程范式.
- [sshj](https://github.com/hierynomus/sshj) - 以编程方式使用 SSH、SCP 或 SFTP.
- [TLS Channel](https://github.com/marianobarrios/tls-channel) - 在 SSLEngine 上实现 ByteChannel 接口，启用易于使用的（类套接字）TLS.
- [Undertow](http://undertow.io)  - 基于 NIO 提供阻塞和非阻塞 API 的 Web 服务器. 在 WildFly 中用作网络层.  （仅限 LGPL-2.1）
- [urnlib](https://github.com/slub/urnlib) - 表示、解析和编码 URN，如 RFC 2141.（仅限 GPL-3.0）

### ORM

_处理对象持久性的API._

- [Apache Cayenne](https://cayenne.apache.org)  - 为数据访问提供干净、静态的 API. 还包括一个用于处理数据库映射以及数据库逆向工程和生成的 GUI 建模器.
- [Doma](https://github.com/domaframework/doma) - 使用注释处理以及称为双向 SQL 的本机 SQL 模板在编译时验证和生成源代码的数据库访问框架.
- [Ebean](https://ebean.io) - 提供简单快速的数据访问.
- [EclipseLink](https://www.eclipse.org/eclipselink/) - 支持多种持久性标准：JPA、JAXB、JCA 和 SDO.
- [Hibernate](http://hibernate.org/orm/)  - 强大且广泛使用，拥有活跃的社区.  （仅限 LGPL-2.1）
- [MyBatis](https://github.com/mybatis/mybatis-3) - Couples objects with stored procedures or SQL statements.
- [ObjectiveSql](https://github.com/braisdom/ObjectiveSql) - ActiveRecord ORM 用于快速开发和约定优于配置.
- [Permazen](https://github.com/permazen/permazen) - 语言自然持久层.
- [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper) - 简单的数据库和 CSV 映射器.

### PaaS

_Java 平台即服务._

- [AWS Elastic Beanstalk ![c]](https://aws.amazon.com/elasticbeanstalk/) - 基于 AWS，支持 Tomcat 和 Jetty.
- [AWS Lambda ![c]](https://aws.amazon.com/lambda/) - 无服务器计算.
- [Google Cloud ![c]](https://cloud.google.com) - Google 的云基础架构.
- [Heroku ![c]](https://www.heroku.com) - 抽象计算环境.
- [Microsoft Azure ![c]](https://azure.microsoft.com/en-us/) - Microsoft 的云基础架构.
- [OpenShift ![c]](https://www.openshift.com) - 额外提供内部部署解决方案.

### PDF

_帮助处理 PDF 文件的工具._

- [Apache FOP](https://xmlgraphics.apache.org/fop/) - 从 XSL-FO 创建 PDF.
- [Apache PDFBox](https://pdfbox.apache.org) - 用于创建和操作 PDF 的工具箱.
- [Dynamic Jasper](http://dynamicjasper.com)  - JasperReports 的抽象层.  （仅限 LGPL-3.0）
- [DynamicReports](https://github.com/dynamicreports/dynamicreports)  - 简化 JasperReports.  （仅限 LGPL-3.0）
- [Eclipse BIRT](https://www.eclipse.org/birt) - 使用基于 Eclipse 的可视化编辑器创建 PDF 和其他格式（DOCX、XLSX、HTML 等）的报告引擎.
- [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer)  - XML/XHTML 和 CSS 2.1 渲染器.  （LGPL-2.1 或更高版本）
- [iText ![c]](https://itextpdf.com/en) - 以编程方式创建 PDF 文件.
- [JasperReports](https://community.jaspersoft.com/project/jasperreports-library)  - 复杂的报告引擎.  （仅限 LGPL-3.0）
- [Open HTML to PDF](https://github.com/danfickle/openhtmltopdf) - 正确支持基于 flysaucer 和 Apache PDFBox 的现代 PDF 标准.
- [OpenPDF](https://github.com/LibrePDF/OpenPDF)  - 开源 iText 分支.  （仅限 LGPL-3.0 和 MPL-2.0）
- [Tabula](https://github.com/tabulapdf/tabula-java) - 从 PDF 文件中提取表格.

### Performance analysis

_性能分析、剖析和基准测试的工具._

- [fastThread ![c]](https://fastthread.io) - 使用基于云的免费上传界面分析和可视化线程转储.
 - [GCeasy ![c]](https://gceasy.io) - 分析和可视化 GC 日志的工具. 它提供了一个免费的基于云的上传接口.
- [honest-profiler](https://github.com/jvm-profiling-tools/honest-profiler) - 低开销、无偏差的采样分析器.
- [jHiccup](https://github.com/giltene/jHiccup) - 记录和记录平台 JVM 停顿.
- [JITWatch](https://github.com/AdoptOpenJDK/jitwatch) - 分析由 HotSpot JVM 进行的 JIT 编译器优化.
- [JMH](http://openjdk.java.net/projects/code-tools/jmh/)  - 利用 Java 和其他针对 JVM 的语言编写的用于构建、运行和分析 nano/micro/milli/macro 基准测试的工具.  （GPL-2.0 仅 WITH Classpath-exception-2.0）
- [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils) - 用于延迟测量和报告的实用程序.

### Platform

_框架是包含多个类别的多个库的套件._

#### Apache Commons

- [BCEL](http://commons.apache.org/proper/commons-bcel/) - 字节码工程库 - 分析、创建和操作 Java 类文件.
- [BeanUtils](http://commons.apache.org/proper/commons-beanutils/) - 围绕 Java 反射和内省 API 的易于使用的包装器.
- [BeanUtils2](http://commons.apache.org/sandbox/commons-beanutils2/) - 重新设计 Commons BeanUtils.
- [BSF](http://commons.apache.org/proper/commons-bsf/) - Bean Scripting Framework - 脚本语言接口，包括 JSR-223.
- [Chain](http://commons.apache.org/proper/commons-chain/) - 责任链模式实现.
- [ClassScan](http://commons.apache.org/sandbox/commons-classscan/) - 无需加载即可查找类接口、方法、字段和注释.
- [CLI](http://commons.apache.org/proper/commons-cli/) - 命令行参数解析器.
- [CLI2](http://commons.apache.org/sandbox/commons-cli2/) - 重新设计 Commons CLI.
- [Codec](http://commons.apache.org/proper/commons-codec/) - 通用编码/解码算法，例如语音、base64 或 URL.
- [Collections](http://commons.apache.org/proper/commons-collections/) - 扩展或增强了 Java 集合框架.
- [Compress](http://commons.apache.org/proper/commons-compress/) - 定义用于处理 tar、zip 和 bzip2 文件的 API.
- [Configuration](http://commons.apache.org/proper/commons-configuration/) - 读取各种格式的配置/首选项文件.
- [Convert](http://commons.apache.org/sandbox/commons-convert/) - Commons-Convert 旨在提供一个单一的库，专门用于将一种类型的对象转换为另一种类型的任务.
- [CSV](http://commons.apache.org/proper/commons-csv/) - 用于读取和写入逗号分隔值文件的组件.
- [Daemon](http://commons.apache.org/proper/commons-daemon/) - unix-daemon-like java 代码的替代调用机制.
- [DBCP](http://commons.apache.org/proper/commons-dbcp/) - 数据库连接池服务.
- [DbUtils](http://commons.apache.org/proper/commons-dbutils/) - JDBC 帮助程序库.
- [Digester](http://commons.apache.org/proper/commons-digester/) - XML 到 Java 对象的映射实用程序.
- [Email](http://commons.apache.org/proper/commons-email/) - 用于从 Java 发送电子邮件的库.
- [Exec](http://commons.apache.org/proper/commons-exec/) - 用于处理 Java 中外部进程执行和环境管理的 API.
- [FileUpload](http://commons.apache.org/proper/commons-fileupload/) - 您的 servlet 和 Web 应用程序的文件上传功能.
- [Finder](http://commons.apache.org/sandbox/commons-finder/) - 受 UNIX find 命令启发的 Java 库.
- [Flatfile](http://commons.apache.org/sandbox/commons-flatfile/) - 用于处理平面数据结构的 Java 库.
- [Functor](http://commons.apache.org/proper/commons-functor/) - 可以作为对象操作的函数，或表示单个通用函数的对象.
- [Graph](http://commons.apache.org/sandbox/commons-graph/) - 通用图形 API 和算法.
- [I18n](http://commons.apache.org/sandbox/commons-i18n/) - 添加了本地化消息包的功能，这些消息包由一个或多个属于一起的本地化文本组成.
- [Id](http://commons.apache.org/sandbox/commons-id/) - Id 是用于生成标识符的组件.
- [Imaging](http://commons.apache.org/proper/commons-imaging/) - 图像库.
- [IO](http://commons.apache.org/proper/commons-io/) - I/O 实用程序的集合.
- [Javaflow](http://commons.apache.org/sandbox/commons-javaflow/) - 继续实现以捕获应用程序的状态.
- [JCI](http://commons.apache.org/proper/commons-jci/) - Java 编译器接口.
- [JCS](http://commons.apache.org/proper/commons-jcs/) - Java缓存系统.
- [Jelly](http://commons.apache.org/proper/commons-jelly/) - XML based scripting and processing engine.
- [Jexl](http://commons.apache.org/proper/commons-jexl/) - 表达式语言，它扩展了 JSTL 的表达式语言.
- [JNet](http://commons.apache.org/sandbox/commons-jnet/) - JNet 允许通过 java.net API 使用动态注册的 url 流处理程序.
- [JXPath](http://commons.apache.org/proper/commons-jxpath/) - 使用 XPath 语法操作 Java Bean 的实用程序.
- [Lang](http://commons.apache.org/proper/commons-lang/) - 为 java.lang 中的类提供额外的功能.
- [Logging](https://commons.apache.org/proper/commons-logging/) - 围绕各种日志 API 实现的包装.
- [Math](http://commons.apache.org/proper/commons-math/) - 轻量级、自包含的数学和统计组件.
- [Monitoring](http://commons.apache.org/sandbox/commons-monitoring/) - Monitoring 旨在为 Java 应用程序提供简单但可扩展的监控解决方案.
- [Nabla](http://commons.apache.org/sandbox/commons-nabla/) - Nabla 提供了自动微分类，可以生成在 Java 语言中实现的任何函数的派生类.
- [Net](http://commons.apache.org/proper/commons-net/) - 网络实用程序和协议实现的集合.
- [OGNL](http://commons.apache.org/proper/commons-ognl/) - 对象图导航语言.
- [OpenPGP](http://commons.apache.org/sandbox/commons-openpgp/) - 使用 OpenPGP 签名和验证数据的接口.
- [Performance](http://commons.apache.org/sandbox/commons-performance/) - 用于微基准测试客户端的小型框架，具有 Commons DBCP 和 Pool 的实现.
- [Pipeline](http://commons.apache.org/sandbox/commons-pipeline/) - 提供一组围绕并行运行以顺序处理数据对象的工作队列设计的管道实用程序.
- [Pool](http://commons.apache.org/proper/commons-pool/) - 通用对象池组件.
- [Proxy](http://commons.apache.org/proper/commons-proxy/) - 用于创建动态代理的库.
- [RDF](https://commons.apache.org/proper/commons-rdf/) - 可以由 JVM 上的系统实现的 RDF 1.1 的通用实现.
- [RNG](https://commons.apache.org/proper/commons-rng/) - Commons Rng 提供了伪随机数生成器的实现.
- [SCXML](http://commons.apache.org/proper/commons-scxml/) - 旨在创建和维护 Java SCXML 引擎的 State Chart XML 规范的实现.
- [Validator](http://commons.apache.org/proper/commons-validator/) - 在 xml 文件中定义验证器和验证规则的框架.
- [VFS](http://commons.apache.org/proper/commons-vfs/) - 虚拟文件系统组件，用于将文件、FTP、SMB、ZIP 等视为单个逻辑文件系统.
- [Weaver](http://commons.apache.org/proper/commons-weaver/) - 提供一种简单的方法来增强（编织）已编译的字节码.

#### Other

- [CUBA Platform](https://www.cuba-platform.com/) - 用于开发具有丰富 Web 界面的企业应用程序的高级框架，基于 Spring、EclipseLink 和 Vaadin.
- [Light-4J](https://github.com/networknt/light-4j/) - 内置快速、轻量级和高效的微服务框架 [security](https://github.com/networknt/light-oauth2/).
- [Orienteer](https://github.com/OrienteerBAP/Orienteer/) - 开源业务应用平台，用于CRM、ERP、LMS等应用的快速配置/开发.
- [Spring](https://spring.io/projects/) - 为依赖注入、面向方面编程、安全性等提供了许多包.

### Processes

_帮助管理操作系统进程的库._

- [ch.vorburger.exec](https://github.com/vorburger/ch.vorburger.exec) - 围绕 Apache Commons Exec 的便捷 API.
- [zt-exec](https://github.com/zeroturnaround/zt-exec) - 为 Apache Commons Exec 和 ProcessBuilder 提供统一的 API.
- [zt-process-killer](https://github.com/zeroturnaround/zt-process-killer) - 停止从 Java 启动的进程或通过 PID 的系统进程.

### Reactive libraries

_用于开发反应式应用程序的库._

- [Akka](https://akka.io) - 用于构建并发、分布式、容错和事件驱动应用程序的工具包和运行时.
- [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm) - 为具有非阻塞背压的异步流处理提供标准.
- [Reactor](https://github.com/reactor/reactor-core) - 用于构建反应式快速数据应用程序的库.
- [RxJava](https://github.com/ReactiveX/RxJava) - 允许使用可观察序列编写异步和基于事件的程序.
- [vert.x](https://vertx.io) - 多语言事件驱动的应用程序框架.

### REST Frameworks

_专门用于创建 RESTful 服务的框架._

- [Dropwizard](https://github.com/dropwizard/dropwizard) - 用于使用 Jetty、Jackson、Jersey 和 Metrics 设置现代 Web 应用程序的意见框架.
- [Elide](https://elide.io) - 基于 JPA 数据模型的 JSON 或 GraphQL API 的有意见框架.
- [Jersey](https://jersey.github.io) - JAX-RS 参考实现.
- [Microserver](https://github.com/aol/micro-server)  - 方便、可扩展的 Spring 和 Spring Boot 微服务插件系统. 它拥有 30 多个插件并且还在不断增长，它支持微单体和纯微服务风格.
- [Rapidoid](https://www.rapidoid.org) - 简单、安全且速度极快的框架，由嵌入式 HTTP 服务器、GUI 组件和依赖注入组成.
- [rest.li](https://github.com/linkedin/rest.li) - 使用类型安全绑定和异步、非阻塞 IO 和端到端开发人员工作流构建健壮、可扩展的 RESTful 架构的框架，该工作流促进干净的实践、统一的接口设计和一致的数据建模.
- [RESTEasy](https://resteasy.github.io) - JAX-RS 规范的完全认证和可移植实现.
- [RestExpress](https://github.com/RestExpress/RestExpress) - JBoss Netty HTTP 堆栈上的瘦包装器，可提供可扩展性和性能.
- [Restlet Framework](https://github.com/restlet/restlet-framework-java) - 具有强大路由和过滤能力的开创性框架，以及统一的客户端和服务器 API.
- [Spark](http://sparkjava.com) - Sinatra 启发的框架.
- [Crnk](http://www.crnk.io) - 实施 JSON API 规范以构建面向资源的 REST 端点，具有排序、过滤、分页、链接、对象图、类型安全、批量更新、集成等功能.
- [springdoc-openapi](https://github.com/springdoc/springdoc-openapi) - 使用 Spring Boot 项目自动生成 API 文档.
- [Swagger](https://swagger.io) - REST API 的标准、与语言无关的接口.

### Science

_用于科学计算、分析和可视化的库._

- [BioJava](https://biojava.org/) - 通过提供生物信息学中常用的算法、文件格式解析器、测序和 3D 可视化来促进生物数据的处理.
- [Chart-FX](https://github.com/GSI-CS-CO/chart-fx) - 科学图表库，专注于以 25 Hz 更新速率为大型数据集优化性能的实时数据可视化.
- [DataMelt](https://jwork.org/dmelt/)  - 科学计算、数据分析和数据可视化的环境.  （GPL-3.0 或更高版本）
- [Erdos](https://github.com/Erdos-Graph-Framework/Erdos) - 用于理论算法的模块化、轻量级和简单的图形框架.
- [GraphStream](http://graphstream-project.org) - 用于建模和分析动态图的库.
- [JFreeChart](http://www.jfree.org/jfreechart/)  - 用于 Swing、JavaFX 和服务器端应用程序的 2D 图表库.  （仅限 LGPL-2.1）
- [JGraphT](https://github.com/jgrapht/jgrapht) - 提供数学图论对象和算法的图库.
- [JGraphX](https://github.com/jgraph/jgraphx) - 用于可视化（主要是 Swing）和与节点边缘图交互的库.
- [LogicNG](https://github.com/logic-ng/LogicNG) - 用于创建、操作和求解布尔和伪布尔公式的库.
- [Mines Java Toolkit](https://github.com/MinesJTK/jtk) - 用于地球物理科学计算、可视化和数字信号分析的库.
- [Morpheus](https://github.com/zavtech/morpheus-core) - 提供称为 DataFrame 的通用二维内存高效表格数据结构，以支持 JVM 上科学计算的高效内存分析.
- [Orson-Charts](https://github.com/jfree/orson-charts)  - 生成各种 3D 图表，可以使用 Swing 和 JavaFX 显示或导出为 PDF、SVG、PNG 和 JPEG.  （仅限 GPL-3.0）
- [Tablesaw](https://github.com/jtablesaw/tablesaw) - 包括数据框、嵌入式列存储和数百种转换、汇总或过滤数据的方法.
- [XChart](https://github.com/knowm/XChart)  - 用于绘制数据的轻量级库. 许多可定制的图表类型可用.

### Search

_为搜索和分析索引文档的引擎._

- [Apache Lucene](https://lucene.apache.org) - 高性能、全功能、跨平台的文本搜索引擎库.
- [Apache Solr](https://lucene.apache.org/solr/) - 针对高流量优化的企业搜索引擎.
- [Elasticsearch](https://www.elastic.co) - 具有 RESTful Web 界面和无模式 JSON 文档的分布式、支持多租户的全文搜索引擎.
- [Indexer4j](https://github.com/haeungun/indexer4j) - 简单轻便的全文索引和搜索库.

### Security

_处理安全、身份验证、授权或会话管理的库._

- [Apache Shiro](https://shiro.apache.org) - 执行身份验证、授权、加密和会话管理.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - 通用加密库和 JCA 提供程序，提供从基本帮助程序到 PGP/SMIME 操作的广泛功能.
- [Cryptomator](https://cryptomator.org)  - 云中文件的多平台、透明、客户端加密.  （仅限 GPL-3.0）
- [Hdiv](https://github.com/hdiv/hdiv) - 运行时应用程序可以抵御 OWASP Top 10 中包含的应用程序安全风险，包括 SQL 注入、跨站点脚本、跨站点请求伪造、数据篡改和暴力攻击.
- [jjwt](https://github.com/jwtk/jjwt) - 用于 Java 和 Android 的 JSON 网络令牌.
- [Jwks RSA](https://github.com/auth0/jwks-rsa-java) - JSON Web 密钥集解析器.
- [Kalium](https://github.com/abstractj/kalium) - 网络和密码学 (NaCl) 库的绑定.
- [Keycloak](https://www.keycloak.org) - 用于浏览器应用程序和 RESTful Web 服务的集成 SSO 和 IDM.
- [Keywhiz](https://github.com/square/keywhiz) - 用于分发和管理机密的系统.
- [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz) - 高级密码强度估计.
- [OACC](http://oaccframework.org) - 提供基于权限的授权服务.
- [OTP-Java](https://github.com/BastiaanJansen/OTP-Java) - 符合 RFC 4226 (HOTP) 和 RFC 6238 (TOTP) 的一次性密码生成器库.
- [pac4j](https://github.com/pac4j/pac4j) - 安全引擎.
- [Password4j](https://github.com/Password4j/password4j) - 用户友好的加密库，支持 Argon2、Bcrypt、Scrypt、PBKDF2 和各种其他加密哈希函数.
- [SecurityBuilder](https://github.com/tersesystems/securitybuilder) - 用于 JCA 和 JSSE 类的 Fluent Builder API，尤其是 X.509 证书.
- [SSLContext-Kickstart](https://github.com/Hakky54/sslcontext-kickstart) - 高级 SSL 上下文构建器，用于使用 SSL/TLS 配置 HTTP 客户端.
- [Themis](https://github.com/cossacklabs/themis)  - 多平台高级密码库为保护敏感数据提供易于使用的加密：具有前向保密的安全消息传递，安全数据存储（AES256GCM）； 适合构建端到端的加密应用程序.
- [Tink](https://github.com/google/tink) - 为常见的加密任务提供简单且防误用的 API.

### Serialization

_高效处理序列化的库._

- [FlatBuffers](https://github.com/google/flatbuffers) - 内存高效的序列化库，无需解包和解析即可访问序列化数据.
- [FST](https://github.com/RuedigerMoeller/fast-serialization) - 兼容 JDK 的高性能对象图序列化.
- [Kryo](https://github.com/EsotericSoftware/kryo) - 快速高效的对象图序列化框架.
- [MessagePack](https://github.com/msgpack/msgpack-java) - 高效的二进制序列化格式.
- [PHP Serializer](https://github.com/marcospassos/java-php-serializer) - 以 PHP 序列化格式序列化对象.

### Server

_专门用于部署应用程序的服务器._

- [Apache Tomcat](https://tomcat.apache.org) - 适用于 Servlet 和 JSP 的强大、全面的服务器.
- [Apache TomEE](https://tomee.apache.org) - Tomcat 加 Java EE.
- [Jetty](https://www.eclipse.org/jetty/) - 提供 Web 服务器和 javax.servlet 容器，以及对 HTTP/2、WebSocket、OSGi、JMX、JNDI、JAAS 和许多其他集成的支持.
- [nanohttpd](https://github.com/NanoHttpd/nanohttpd) - 小巧、易于嵌入的 HTTP 服务器.
- [WildFly](https://www.wildfly.org)  - 以前称为 JBoss，由 Red Hat 开发，具有广泛的 Java EE 支持.  （仅限 LGPL-2.1）

### Template Engine

_在模板中替换表达式的工具._

- [Freemarker](https://freemarker.apache.org) - 基于模板和不断变化的数据生成文本输出（HTML 网页、电子邮件、配置文件、源代码等）的库.
- [Handlebars.java](https://jknack.github.io/handlebars.java/) - 无逻辑和语义的 Mustache 模板.
- [Jade4J](https://github.com/neuland/jade4j) - 实现 Pug（以前称为 Jade）.
- [jte](https://github.com/casid/jte) - 编译为类并使用简单的语法、多种功能使开发更容易，并提供快速执行和较小的占用空间.
- [Jtwig](https://github.com/jtwig/jtwig) - 模块化、可配置且经过全面测试的模板引擎.
- [Pebble](https://pebbletemplates.io)  - 受 Twig 的启发，并以其继承功能和易于阅读的语法将自己分开. 它带有内置的安全自动转义，并且包括对国际化的集成支持.
- [Rocker](https://github.com/fizzed/rocker) - 优化、内存高效且快速的模板引擎，可生成静态类型的普通对象.
- [StringTemplate](https://github.com/antlr/stringtemplate4) - 用于生成源代码、网页、电子邮件或任何其他格式化文本输出的模板引擎.
- [Thymeleaf](https://www.thymeleaf.org) - 旨在替代 JSP，适用于 XML 文件.

### Testing

_从模型到视图测试的工具._

#### Asynchronous

_简化异步服务测试的工具._

- [Awaitility](https://github.com/awaitility/awaitility) - 用于同步异步操作的 DSL.
- [ConcurrentUnit](https://github.com/jhalterman/concurrentunit) - Toolkit for testing multi-threaded and asynchronous applications.
- [GreenMail](http://www.icegreen.com/greenmail/)  - 用于集成测试的内存电子邮件服务器. 支持 SMTP、POP3 和 IMAP，包括 SSL.  （仅限 GPL-2.0）
- [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java) - Hoverfly 的本机绑定，一个允许您模拟 HTTP 服务的代理.
- [Karate](https://github.com/intuit/karate) - 结合 API 测试自动化、模拟和性能测试的 DSL，使测试 REST/HTTP 服务变得容易.
- [REST Assured](https://github.com/rest-assured/rest-assured) - 用于轻松测试 REST/HTTP 服务的 DSL.

#### BDD

_测试从 TDD 出现并深受 DDD 和 OOAD 影响的软件开发过程._

- [Cucumber](https://github.com/cucumber/cucumber-jvm) - 提供一种用客户可以理解的通俗语言描述功能的方法.
- [Cukes-REST](https://github.com/ctco/cukes) - 使用 Cucumber 收集用于 REST 服务测试的 Gherkin 步骤.
- [J8Spec](https://github.com/j8spec/j8spec) - 遵循类似 Jasmine 的语法.
- [JBehave](https://jbehave.org) - 描述故事的可广泛配置的框架.
- [JGiven](http://jgiven.org) - 提供流畅的 API，允许更简单的组合.
- [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave) - 旨在提供流畅的 API 以编写长句和描述性句子的测试，读起来像简单的英语.
- [Serenity BDD](https://github.com/serenity-bdd/serenity-core) - 与 Cucumber、JBehave 和 JUnit 配合使用的自动化验收测试和报告库，可以更轻松地编写高质量的可执行规范.

#### Fixtures

_与随机数据的创建和处理相关的一切._

- [Beanmother](https://github.com/keepcosmos/beanmother) - 从 YAML 装置设置 bean.
- [Fixture Factory](https://github.com/six2six/fixture-factory) - 从模板生成假对象.
- [jFairy](https://github.com/Devskiller/jfairy) - 假数据生成器.
- [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) - JUnit 测试运行器和插件，用于以伪随机性运行 JUnit 测试.
- [Java Faker](https://github.com/DiUS/java-faker) - Ruby 的假数据生成器的端口.

#### Frameworks

_提供环境以针对特定用例运行测试._

- [ArchUnit](https://github.com/TNG/ArchUnit) - 用于指定和断言架构规则的测试库.
- [Apache JMeter](http://jmeter.apache.org) - 功能测试和性能测量.
- [Arquillian](http://arquillian.org) - Java EE 容器的集成和功能测试平台.
- [Citrus](https://citrusframework.org) - 专注于客户端和服务器端消息传递的集成测试框架.
- [Gatling](https://gatling.io) - 负载测试工具专为易用性、可维护性和高性能而设计.
- [JUnit](https://junit.org/junit5/) - 通用测试框架.
- [jqwik](https://jqwik.net) - 基于 JUnit 5 的基于属性的测试引擎.
- [Pact JVM](https://github.com/DiUS/pact-jvm) - 消费者驱动的合同测试.
- [PIT](http://pitest.org) - 用于评估现有 JUnit 或 TestNG 测试套件的故障检测能力的快速突变测试框架.

#### Matchers

_提供自定义匹配器的库._

- [AssertJ](https://joel-costigliola.github.io/assertj/) - 提高可读性的流畅断言.
- [Hamcrest](http://hamcrest.org/JavaHamcrest/) - 可以组合以创建灵活的意图表达的匹配器.
- [JSONAssert](http://jsonassert.skyscreamer.org) - 简化了 JSON 字符串的测试.
- [Truth](https://truth.dev) - 谷歌流畅的断言和命题框架.
- [XMLUnit](https://github.com/xmlunit/xmlunit) - 简化对 XML 输出的测试.

#### Miscellaneous

_其他与测试相关的东西._

- [junit-dataprovider](https://github.com/TNG/junit-dataprovider) - JUnit 的类似 TestNG 的数据提供程序/运行程序.
- [LogCaptor](https://github.com/Hakky54/log-captor) - 为单元测试目的捕获日志条目.
- [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector) - 报告给定类的实例是否不可变.
- [raml-tester](https://github.com/nidi3/raml-tester) - 测试请求/响应是否与给定的 RAML 定义匹配.
- [TestContainers](https://github.com/testcontainers/testcontainers-java) - 提供通用数据库、Selenium Web 浏览器或任何其他可以在 Docker 容器中运行的一次性实例.
- [pojo-tester](https://www.pojo.pl)  - 自动对基本 POJO 方法执行测试.  （仅限 LGPL-3.0）

#### Mocking

_模拟协作者以帮助测试单个孤立单元的工具._

- [JMockit](http://jmockit.github.io) - 集成测试、API 模拟和伪造以及代码覆盖率.
- [Mockito](https://github.com/mockito/mockito) - 模拟框架，可让您使用干净简单的 API 编写测试.
- [MockServer](https://www.mock-server.com) - 允许模拟与 HTTPS 集成的系统.
- [Moco](https://github.com/dreamhead/moco) - 用于存根和模拟的简洁网络服务.
- [PowerMock](https://github.com/powermock/powermock) - 模拟静态方法、构造函数、final 类和方法、私有方法以及静态初始值设定项的删除.
- [WireMock](http://wiremock.org) - 存根和模拟网络服务.

### Utility

_提供通用实用功能的库._

- [Arthas](https://github.com/alibaba/arthas) - 允许在不修改代码或重新启动服务器的情况下解决应用程序的生产问题.
- [bucket4j](https://github.com/vladimir-bukhtoyarov/bucket4j) - 基于令牌桶算法的速率限制库.
- [cactoos](https://github.com/yegor256/cactoos) - 面向对象原语的集合.
- [CRaSH](http://www.crashub.org)  - 为运行 CRaSH 的 JVM 提供一个 shell. 由 Spring Boot 和其他人使用.  （LGPL-2.1 或更高版本）
- [Dex](https://github.com/PatMartin/Dex) - 具有强大 ETL 和数据可视化能力的 Java/JavaFX 工具.
- [Embulk](https://github.com/embulk/embulk) - 批量数据加载器，有助于在各种数据库、存储、文件格式和云服务之间传输数据.
- [fswatch](https://github.com/vorburger/ch.vorburger.fswatch) - Micro library to watch for directory file system changes, simplifying java.nio.file.WatchService.
- [Gephi](https://github.com/gephi/gephi)  - 用于可视化和操作大型图形网络的跨平台.  （仅限 GPL-3.0）
- [Guava](https://github.com/google/guava) - 集合、缓存、原语支持、并发库、通用注释、字符串处理、I/O 等.
- [JADE](http://jade.tilab.com)  - 构建和调试多代理系统的框架和环境.  （仅限 LGPL-2.0）
- [Java Diff Utils](https://java-diff-utils.github.io/java-diff-utils/) - 用于文本或数据比较和修补的实用程序.
- [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions) - 有助于构建困难正则表达式的库.
- [JGit](https://www.eclipse.org/jgit/) - 实现 Git 版本控制系统的轻量级纯 Java 库.
- [minio-java](https://github.com/minio/minio-java) - 提供简单的 API 来访问任何与 Amazon S3 兼容的对象存储服务器.
- [Protégé](https://protege.stanford.edu) - 提供本体编辑器和构建基于知识的系统的框架.
- [Underscore-java](https://github.com/javadev/underscore-java) - Underscore.js 函数的端口.

### Version Managers

_帮助创建开发 shell 环境并在不同 Java 版本之间切换的实用程序._

- [jabba](https://github.com/shyiko/jabba)  - 受 nvm 启发的 Java 版本管理器. 支持 macOS、Linux 和 Windows.
- [jenv](https://github.com/jenv/jenv)  - 受 rbenv 启发的 Java 版本管理器. 可以配置全局或每个项目. 在 Debian 和 macOS 上测试.
- [SDKMan](https://github.com/sdkman/sdkman-cli)  - 受 RVM 和 rbenv 启发的 Java 版本管理器. 支持基于 UNIX 的平台和 Windows.

### Web Crawling

_分析网站内容的库._

- [Apache Nutch](https://nutch.apache.org) - 用于生产环境的高度可扩展、高度可扩展的网络爬虫.
- [Crawler4j](https://github.com/yasserg/crawler4j) - 简单轻量级的网络爬虫.
- [jsoup](https://jsoup.org) - 抓取、解析、操作和清理 HTML.
- [StormCrawler](http://stormcrawler.net) - SDK for building low-latency and scalable web crawlers.
- [webmagic](https://github.com/code4craft/webmagic) - 具有下载、网址管理、内容提取和持久性的可扩展爬虫.

### Web Frameworks

_处理 Web 应用程序各层之间通信的框架._

- [ActiveJ](https://activej.io) - 从头开始​​构建的轻量级异步框架，用于开发高性能 Web 应用程序.
- [Apache Tapestry](https://tapestry.apache.org) - 面向组件的框架，用于创建动态、健壮、高度可扩展的 Web 应用程序.
- [Apache Wicket](https://wicket.apache.org) - 基于组件的 Web 应用程序框架类似于 Tapestry，具有有状态的 GUI.
- [Blade](https://github.com/lets-blade/blade) - 旨在优雅和简单的轻量级模块化框架.
- [Bootique](https://bootique.io) - 可运行应用程序的最小自以为是的框架.
- [Firefly](http://www.fireflysource.com) - 用于快速开发高性能 Web 应用程序的异步框架.
- [Jooby](http://www.jooby.org) - 提供多种编程模型的可扩展、快速和模块化的微框架.
- [Ninja](http://www.ninjaframework.org) - 全栈网络框架.
- [Pippo](http://www.pippo.ro) - 小型、高度模块化、类似 Sinatra 的框架.
- [Play](https://www.playframework.com) - 基于 Akka，它为 Java 和 Scala 中的高度可扩展应用程序提供可预测且最小的资源消耗（CPU、内存、线程）.
- [PrimeFaces](https://www.primefaces.org) - 具有免费和商业/支持版本以及前端组件的 JSF 框架.
- [Ratpack](https://ratpack.io) - 一组库，可促进快速、高效、可进化且经过良好测试的 HTTP 应用程序.
- [Takes](https://github.com/yegor256/takes) - 围绕真正面向对象编程和不变性的概念构建的有意见的 Web 框架.
- [Vaadin](https://vaadin.com)  - 使用标准 Web 组件的事件驱动框架. 在客户端使用 Ajax 的服务器端架构.

### Workflow Orchestration Engines

- [Cadence](https://cadenceworkflow.io) - 来自 Uber 的有状态代码平台.
- [Temporal](https://temporal.io) - 微服务编排平台，从 Cadence 分叉，但基于 gRPC.

## Resources

### Awesome Lists

_与 Java 和 JVM 生态系统相关的很棒的列表._

- [Awesome Annotation Processing](https://github.com/gunnarmorling/awesome-annotation-processing)
- [Awesome Graal](https://github.com/neomatrix369/awesome-graal)
- [Awesome Gradle Plugins](https://github.com/ksoichiro/awesome-gradle)
- [AwesomeJavaFX](https://github.com/mhrimaz/AwesomeJavaFX)
- [Awesome JVM](https://github.com/deephacks/awesome-jvm)
- [Awesome Microservices](https://github.com/mfornos/awesome-microservices)
- [Awesome REST](https://github.com/marmelab/awesome-rest)
- [Awesome Selenium](https://github.com/christian-bromann/awesome-selenium)
- [ciandcd](https://github.com/ciandcd/awesome-ciandcd)
- [Useful Java Links](https://github.com/Vedenin/useful-java-links)
- [Java Concurrency Checklist](https://github.com/code-review-checklists/java-concurrency)
- [Java Developer Roadmap](https://github.com/s4kibs4mi/java-developer-roadmap)

### Communities

_积极讨论._

- [r/java](https://www.reddit.com/r/java/) - Java 社区的子版块.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/java) - 问答平台.
- [VirtualJUG](https://virtualjug.com) - 虚拟 Java 用户组.

### Frontends

 _为此列表提供前端的网站. 请注意，不会有官方网站. 我们不与特定网站关联，每个人都可以创建一个._

- [java.libhunt.com](https://java.libhunt.com)

### Influential Books

_影响很大并且仍然值得一读的书._

- [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
- [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
- [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
- [Thinking in Java](https://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

### Podcasts and Screencasts

_编程时看或听的东西._

- [A Bootiful Podcast](https://bootifulpodcast.fm)
- [Inside Java](https://inside.java/podcast) （官方的）
- [Java Off Heap](http://www.javaoffheap.com)
- [The Java Council](https://virtualjug.com/#podcast)
- [The Java Posse](http://www.javaposse.com) - 自 2015 年 2 月起停产.

### Twitter

 _要关注的活动帐户. 来自推特的描述._

- [Adam Bien](https://twitter.com/AdamBien) - 自由作家、JavaOne Rockstar 演讲者、顾问、Java Champion.
- [Aleksey Shipilëv](https://twitter.com/shipilev) - 性能极客、基准测试沙皇、并发漏洞猎手.
- [Antonio Goncalves](https://twitter.com/agoncal) - Java Champion、JUG Leader、Devoxx France、Java EE 6/7、JCP、作者.
- [Arun Gupta](https://twitter.com/arungupta) - Java Champion、JavaOne Rockstar、JUG 负责人、Devoxx4Kids-er、Couchbase 开发者宣传副总裁.
- [Brian Goetz](https://twitter.com/BrianGoetz) - Oracle 的 Java 语言架构师.
- [Bruno Borges](https://twitter.com/brunoborges) - Oracle 产品经理/Java Jock.
- [Chris Richardson](https://twitter.com/crichardson) - 软件架构师、顾问和连续创业者、Java Champion、JavaOne Rock Star、\*POJOs in Action-作者.
- [Ed Burns](https://twitter.com/edburns) - Oracle 技术人员的咨询成员.
- [Eugen Paraschiv](https://twitter.com/baeldung) - Spring 安全课程的作者.
- [Heinz Kabutz](https://twitter.com/heinzkabutz) - Java Champion，演讲者，The Java Specialists&#39; Newsletter 的作者，并发性能专家.
- [Holly Cummins](https://twitter.com/holly_cummins) - IBM 伦敦 Bluemix Garage 的技术主管，Java Champion，开发人员，作者，JavaOne 摇滚明星.
- [James Weaver](https://twitter.com/JavaFXpert) - Java/JavaFX/IoT 开发人员、作者和演讲者.
- [Java EE](https://twitter.com/Java_EE) - 官方 Java EE Twitter 帐户.
- [Java Magazine](https://twitter.com/Oraclejavamag) - 官方 Java 杂志帐户.
- [Java](https://twitter.com/java) - 官方 Java Twitter 帐户.
- [Javin Paul](https://twitter.com/javinpaul) - 著名的 Java 博主.
- [Josh Long](https://twitter.com/starbuxman) - Pivotal 的 Spring Advocate，O&#39;Reilly 的 Cloud Native Java 和 Building Microservices with Spring Boot 的作者，JavaOne Rock Star.
- [Lukas Eder](https://twitter.com/lukaseder) - Java Champion、演讲者、JUG.ch 联合领导人、创始人兼首席执行官 Data Geekery (jOOQ).
- [Mani Sarkar](https://twitter.com/theNeomatrix369)  - Java 冠军、Polyglot、参与@graalvm 的 Software Crafter、AI/ML/DL、数据科学、开发者社区、演讲者和博主. 像这样的几个很棒的列表的创建者.
- [Mario Fusco](https://twitter.com/mariofusco) - RedHatter，JUG 协调员，经常演讲者和作者.
- [Mark Heckler](https://twitter.com/MkHeck) - Pivotal 首席技术专家和开发倡导者、会议发言人、出版作家和 Java Champion，专注于物联网和云.
- [Mark Reinhold](https://twitter.com/mreinhold) - 首席架构师，Java 平台组，Oracle.
- [Markus Eisele](https://twitter.com/myfear) - Java EE 布道者，Red Hat.
- [Martijn Verburg](https://twitter.com/karianna) - 伦敦 JUG 联合领导者、演讲者、作者、Java Champion 等等.
- [Martin Thompson](https://twitter.com/mjpt777) - 面无表情的表演黑帮.
- [Monica Beckwith](https://twitter.com/mon_beck) - 性能顾问，JavaOne Rock Star.
- [OpenJDK](https://twitter.com/OpenJDK) - 官方 OpenJDK 帐户.
- [Peter Lawrey](https://twitter.com/PeterLawrey) - Peter Lawrey，Java 性能专家.
- [Randy Shoup](https://twitter.com/randyshoup) - Stitch Fix 工程副总裁、演讲者、JavaOne Rock Star.
- [Reza Rahman](https://twitter.com/reza_rahman) - Java EE/GlassFish/WebLogic 布道者、作者、演讲者、开源黑客.
- [Sander Mak](https://twitter.com/Sander_Mak) - Java Champion，作者.
- [Simon Maple](https://twitter.com/sjmaple) - Java Champion，VirtualJUG 创始人，LJC 负责人，RebelLabs 的作者.
- [Spencer Gibb](https://twitter.com/spencerbgibb) - 软件工程师，老爸，极客，Spring Cloud Core @pivotal 的联合创始人和负责人.
- [Stephen Colebourne](https://twitter.com/jodastephen) - Java Champion，演讲者.
- [Trisha Gee](https://twitter.com/trisha_gee) - Java冠军和演讲者.
- [Venkat Subramaniam](https://twitter.com/venkat_s) - 作者，休斯顿大学教授，MicroSoft MVP 奖获得者，JavaOne Rock Star，Java 冠军.
- [Vlad Mihalcea](https://twitter.com/vlad_mihalcea) - 致力于 Hypersistence Optimizer 的 Java Champion，数据库爱好者，High-Performance Java Persistence 一书的作者.

### Websites

_要阅读的网站._

- [Baeldung](https://www.baeldung.com)
- [Dzone](https://dzone.com)
- [foojay.io](https://foojay.io)
- [Google Java Style](https://google.github.io/styleguide/javaguide.html)
- [InfoQ](https://www.infoq.com)
- [Java Algorithms and Clients](https://algs4.cs.princeton.edu/code)
- [Java, SQL, and jOOQ](https://blog.jooq.org)
- [Java.net](https://community.oracle.com/community/java)
- [Javalobby](https://dzone.com/java-jdk-development-tutorials-tools-news)
- [JavaWorld](https://www.javaworld.com)
- [JAXenter](https://jaxenter.com)
- [RebelLabs](https://zeroturnaround.com/rebellabs)
- [OverOps Blog](https://blog.overops.com)
- [TheServerSide.com](http://www.theserverside.com)
- [Vanilla Java](https://vanilla-java.github.io)
- [Voxxed](https://www.voxxed.com)

## Contributing

非常欢迎投稿！

请看一下 [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) 指导方针和 [the validation tools](https://github.com/akullpp/awesome-java-lint).

[c]: https://cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg
