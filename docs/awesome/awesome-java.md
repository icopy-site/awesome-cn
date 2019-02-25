<div class="github-widget" data-repo="akullpp/awesome-java"></div>
## Awesome Java [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

精选的Java框架，库和软件的精选列表.



## Projects

### Bean Mapping

*简化bean映射的框架.*

- [dOOv](https://github.com/doov-io/doov)   - 为类型安全域模型验证和映射提供流畅的API.  它使用注释，代码生成和类型安全的DSL来快速简便地进行bean验证和映射.
- [Dozer](https://github.com/DozerMapper/dozer) - 使用注释和API或XML配置将数据从一个对象复制到另一个对象的映射器.
- [JMapper](https://jmapper-framework.github.io/jmapper-core)   - 使用字节代码操作进行闪电般的快速映射.  支持注释和API或XML配置.
- [MapStruct](https://github.com/mapstruct/mapstruct) - 代码生成器，基于配置约定方法，简化不同bean类型之间的映射.
- [ModelMapper](https://github.com/jhalterman/modelmapper) - 智能对象映射库，可自动将对象相互映射.
- [Orika](https://github.com/orika-mapper/orika) -  JavaBean映射框架，用于递归地将数据（以及其他功能）从一个对象复制到另一个对象.
- [Selma](https://github.com/xebia-france/selma) - 基于注释处理器的bean映射器.

### Build

*处理应用程序的构建周期和依赖关系的工具.*

- [Apache Maven](https://maven.apache.org)   - 声明式构建和依赖性管理，有利于约定优于配置.  它可能更适合Apache Ant，它使用相当程序化的方法并且难以维护.
- [Bazel](https://bazel.io) - 来自Google的工具，可以快速可靠地构建代码.
- [Buck](https://github.com/facebook/buck) - 鼓励创建由代码和资源组成的小型可重用模块.
- [Gradle](https://gradle.org)   - 通过Groovy编程的增量构建，而不是声明XML.  适用于Maven的依赖管理.

### Bytecode Manipulation

*库以编程方式操作字节码.*

- [ASM](http://asm.ow2.org) - 通用的低级字节码操作和分析.
- [Byte Buddy](http://bytebuddy.net) - 使用流畅的API进一步简化字节码生成.
- [bytecode-viewer](https://github.com/Konloch/bytecode-viewer) -  Java 8 Jar＆Android APK逆向工程套件.
- [Byteman](https://byteman.jboss.org)   - 通过DSL（规则）在运行时处理字节码;  主要用于测试/故障排除.
- [cglib](https://github.com/cglib/cglib) - 字节码生成库.
- [Javassist](https://jboss-javassist.github.io/javassist) - Tries to simplify bytecode editing.
- [Mixin](https://github.com/SpongePowered/Mixin) - 使用真实Java代码在运行时处理字节码.

### Caching

*提供缓存设施的图书馆.*

- [cache2k](https://cache2k.org) - 内存中的高性能缓存库.
- [Caffeine](https://github.com/ben-manes/caffeine) - 高性能，接近最佳的缓存库.
- [Ehcache](http://www.ehcache.org) - 分布式通用缓存.
- [Infinispan](http://infinispan.org) - 用于缓存的高度并发键/值数据存储.

### CLI

*与CLI相关的所有库.*

- [ASCII Table](https://github.com/vdmeer/asciitable) - 用ASCII绘制表格的库.
- [Airline](https://github.com/airlift/airline) - 用于解析类似Git的命令行参数的基于注释的框架.
- [args4j](http://args4j.kohsuke.org) - 用于解析命令行参数的小型库.
- [Jansi](https://github.com/fusesource/jansi) -  ANSI转义码，用于格式化控制台输出.
- [Java ASCII Render](https://github.com/indvd00m/java-ascii-render) - 控制台的图形基元.
- [JCommander](http://jcommander.org) - 具有自定义类型的命令行参数解析框架和通过实现接口的验证.
- [jbock](https://github.com/h908714124/jbock) -  Typesafe，无反射，基于注释的命令行解析器 
- [JLine](https://github.com/jline/jline3) - 包括现代贝壳的功能，如完成或历史.
- [JOpt Simple](https://pholser.github.io/jopt-simple) - Fluent parser that uses the POSIX#getopt and GNU#getopt_long syntaxes.
- [picocli](http://picocli.info) - 使用的ANSI颜色和样式有助于基于注释的POSIX / GNU /任何语法，子命令，强选键入选项和位置参数.
- [Text-IO](https://github.com/beryx/text-io) - 帮助创建完整的基于控制台的应用程序.
- [Lanterna](https://github.com/mabe02/lanterna) - 简单的控制台文本GUI库，类似于curses.

### Cluster Management

*可以动态管理集群内部应用程序的框架.*

- [Apache Aurora](https://aurora.apache.org) - 用于长期运行服务和cron作业的Mesos框架.
- [Apache Mesos](https://mesos.apache.org) - 从机器中提取CPU，内存，存储和其他计算资源.
- [Singularity](http://getsingularity.com)   -  Mesos框架，使部署和操作变得简单.  它支持Web服务，后台工作程序，预定作业和一次性任务.

### Code Analysis

*提供指标和质量测量的工具.*

- [Checkstyle](https://github.com/checkstyle/checkstyle) - 编码约定和标准的静态分析.
- [Error Prone](https://github.com/google/error-prone) - 将常见的编程错误作为编译时错误.
- [Infer](https://github.com/facebook/infer) - 用于验证代码正确性的现代静态分析工具.
- [jQAssistant](https://jqassistant.org) - 使用基于Neo4J的查询语言进行静态代码分析.
- [NullAway](https://github.com/uber/NullAway) - 以低构建时开销消除NullPointerExceptions.
- [PMD](https://github.com/pmd/pmd) - 用于查找错误编码实践的源代码分析.
- [SonarJava](https://github.com/SonarSource/sonar-java) -  SonarQube和SonarLint的静态分析仪.
-  [Sourcetrail！[c]]（https://www.sourcetrail.com） - 可视源代码导航器.
- [Spoon](https://github.com/INRIA/spoon) - 用于分析和转换Java源代码的库.
- [Spotbugs](https://github.com/spotbugs/spotbugs) - 字节码的静态分析，以发现潜在的错误.

### Code Coverage

*框架和工具，支持测试套件的代码覆盖度量标准收集.*

-  [Clover！[c]]（https://www.atlassian.com/software/clover/overview） - 依靠源代码检测而不是字节码检测.
- [Cobertura](https://cobertura.github.io/cobertura) - 依靠离线（或静态）字节码检测和类加载来收集代码覆盖率指标.
- [JaCoCo](http://eclemma.org/jacoco) - 使用脱机和运行时字节码检测功能，可以收集代码覆盖率指标的框架.

### Code Generators

*为重复代码生成模式的工具，以减少冗长和错误倾向.*

- [ADT4J](https://github.com/sviperll/adt4j) - 用于代数数据类型的JSR-269代码生成器.
- [Auto](https://github.com/google/auto) - 生成工厂，服务和值类.
- [FreeBuilder](https://github.com/google/FreeBuilder) - 自动生成Builder模式.
- [Immutables](https://immutables.github.io) - 注释处理器，用于生成简单，安全和一致的值对象.
- [JavaPoet](https://github.com/square/javapoet) - 用于生成源文件的API.
- [JHipster](https://github.com/jhipster/generator-jhipster) - 用于Spring Boot和AngularJS的Yeoman源代码生成器.
- [Joda-Beans](http://www.joda.org/joda-beans) - 小型框架，为Java添加可查询属性，增强JavaBeans.
- [Lombok](https://projectlombok.org) - 旨在减少冗长的代码生成器.

### Compiler-compiler

*有助于创建解析器，解释器或编译器的框架.*

- [ANTLR](http://www.antlr.org) - 用于自顶向下解析的复杂全功能框架.
- [JavaCC](https://javacc.org)   - 解析器生成器，生成自上而下的解析器.  允许词法状态切换并允许扩展BNF规范.
- [JFlex](http://jflex.de) - 词法分析器生成器.

### Configuration

*提供外部配置的库.*

- [centraldogma](https://github.com/line/centraldogma) - 基于Git，ZooKeeper和HTTP / 2的高度可用的版本控制服务配置存储库.
- [cfg4j](https://github.com/cfg4j/cfg4j) - Modern configuration library for distributed apps written in Java.
- [config](https://github.com/typesafehub/config) -  JVM语言的配置库.
- [dotenv](https://github.com/shyiko/dotenv) - 用于Java的十二因素配置库.
- [ini4j](http://ini4j.sourceforge.net) - 提供用于处理Windows&#39;INI文件的API.
- [KAConf](https://github.com/mariomac/kaconf) - 用于Java和Kotlin的基于注释的配置系统.
- [owner](https://github.com/lviggiano/owner) - 减少属性的样板.

### Constraint Satisfaction Problem Solver

*有助于实现优化和可满足性问题的库.*

- [Choco](http://choco-solver.org) - 使用约束编程技术的现成约束满足问题求解器.
- [JaCoP](https://github.com/radsz/jacop) - 包括FlatZinc语言的界面，使其能够执行MiniZinc模型.
- [OptaPlanner](https://www.optaplanner.org) - 业务规划和资源调度优化求解器.

### CSV

*简化读取/写入CSV数据的框架和库.*

- [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv) - 杰克逊扩展用于读写CSV.
- [opencsv](http://opencsv.sourceforge.net) - 简单的CSV解析器.
- [Super CSV](https://super-csv.github.io/super-csv) - 功能强大的CSV解析器，支持Dozer，Joda-Time和Java 8.
- [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers)   - 最快速，功能最强大的解析器之一.  还提供TSV和固定宽度记录的解析器.

### Database

*简化与数据库交互的一切.*

- [Apache Phoenix](https://phoenix.apache.org) - 针对低延迟应用程序的HBase上的高性能关系数据库层.
- [AranoDB](https://github.com/arangodb/arangodb-java-driver) -  ArangoDB Java驱动程序.
- [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map) - 高效的内存（选择持久化到磁盘），堆外键值存储.
- [druid](http://druid.io) - 高性能，面向列的分布式数据存储.
- [eXist](https://github.com/eXist-db/exist) -  NoSQL文档数据库和应用程序平台.
- [FlexyPool](https://github.com/vladmihalcea/flexy-pool) - 将指标和故障转移策略引入最常见的连接池解决方案.
- [Flyway](https://flywaydb.org) - 简单的数据库迁移工具.
- [H2](https://h2database.com) - 小型SQL数据库，因其内存功能而着名.
- [HikariCP](https://github.com/brettwooldridge/HikariCP) - 高性能JDBC连接池.
- [jasync-sql](https://github.com/jasync-sql/jasync-sql) -  MySQL和PostgreSQL的异步数据库驱动程序.
- [JDBI](http://jdbi.org) - 方便的JDBC抽象.
- [Jedis](https://github.com/xetorthio/jedis) - 与Redis交互的小客户端，具有命令方法.
- [Jest](https://github.com/searchbox-io/Jest) -  Elasticsearch REST API的客户端.
- [jetcd](https://github.com/justinsb/jetcd) -  etcd的客户端库.
- [Jinq](https://github.com/my2iu/Jinq) - 通过符号执行Java 8 Lambdas（在JPA或jOOQ之上）来输入数据库查询.
- [jOOQ](https://www.jooq.org) - 基于SQL模式生成类型安全代码.
- [Liquibase](http://www.liquibase.org) - 独立于数据库的库，用于跟踪，管理和应用数据库模式更改.
- [MapDB](http://www.mapdb.org) - 嵌入式数据库引擎，提供磁盘或堆外内存支持的并发集合.
- [MariaDB4j](https://github.com/vorburger/MariaDB4j) -  MariaDB的启动器，不需要安装或外部依赖.
- [OrientDB](https://orientdb.com/orientdb) - 在Hazelcast之上编写的可嵌入分布式数据库.
- [Presto](https://github.com/prestodb/presto) - 用于大数据的分布式SQL查询引擎.
- [Querydsl](http://www.querydsl.com) -  Typesafe统一查询.
- [Realm](https://github.com/realm/realm-java) - 移动数据库直接在手机，平板电脑或可穿戴设备内运行.
- [Redisson](https://github.com/mrniko/redisson) - 允许在Redis服务器上部分布式和可扩展的数据结构.
- [requery](https://github.com/requery/requery)   - 一个现代，轻量级但功能强大的对象映射和SQL生成器.  轻松映射或创建数据库，或从任何使用Java的平台执行查询和更新.
- [Speedment](https://github.com/speedment/speedment) - 使用Java 8的Stream API进行查询的数据库访问库.
- [sql2o](https://sql2o.org) - 精简的JDBC包装器，简化了数据库访问，并提供了ResultSet到POJO的简单映射.
- [Vibur DBCP](https://www.vibur.org) - 具有高级性能监视功能的JDBC连接池库.
- [Xodus](https://jetbrains.github.io/xodus) - 高度并发的事务模式和符合ACID的嵌入式数据库.

### Data Structures

*Efficient and specific data structures.*

- [Apache Avro](https://avro.apache.org) - 具有动态类型，未标记数据和缺少手动分配ID的数据交换格式.
- [Apache Orc](https://orc.apache.org) - 基于Hadoop的工作负载的快速高效的列式存储格式.
- [Apache Parquet](https://parquet.apache.org) - 基于Google关于Dremel的论文中的汇编算法的列式存储格式.
- [Apache Thrift](https://thrift.apache.org) - 源自Facebook的数据交换格式.
- [Big Queue](https://github.com/bulldog2011/bigqueue) - 基于内存映射文件的大型，快速且持久的队列.
- [Hyper MinHash](https://github.com/LiveRamp/HyperMinHash-java) - 用于计算loglog空间中的并集，交集和集基数的概率数据结构. 
- [Persistent Collection](https://pcollections.org) -  Java Collections Framework的持久且不可变的模拟.
- [Protobuf](https://github.com/google/protobuf) - 谷歌的数据交换格式.
- [SBE](https://github.com/real-logic/simple-binary-encoding) - 简单的二进制编码，是最快的消息格式之一.
- [Tape](https://github.com/square/tape) - 闪电般快速，事务性，基于文件的FIFO.
- [Wire](https://github.com/square/wire) - 干净，轻量级的协议缓冲区.

### Date and Time

*与处理日期和时间相关的图书馆.*

- [Almanac Converter](https://github.com/hypotemoose/almanac-converter) - 不同日历系统之间的简单转换.
- [iCal4j](https://github.com/ical4j/ical4j) - 解析并构建iCalendar [RFC 5545](https://tools.ietf.org/html/rfc5545) 数据模型.
- [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra) - 补充JDK 8中的日期时间类.
- [Time4J](https://github.com/MenoData/Time4J) - 高级日期和时间库.

### Dependency Injection

*有助于实现这一目标的图书馆 [Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) 范例.*

- [Apache DeltaSpike](https://deltaspike.apache.org) -  CDI扩展框架.
- [Dagger2](https://google.github.io/dagger) - 没有反射的编译时注入框架.
- [Feather](https://github.com/zsoltherpai/feather) - 超轻量级，符合JSR-330标准的依赖注入库.
- [Governator](https://github.com/Netflix/governator) - 增强Google Guice的扩展程序和实用程序.
- [Guice](https://github.com/google/guice) - 完善Dagger的轻量级和自以为是的框架.
- [HK2](https://javaee.github.io/hk2) - 轻量级和动态依赖注入框架.
- [JayWire](https://github.com/vanillasource/jaywire) - 轻量级依赖注入框架.

### Development

*从根本上扩大发展进程.*

- [AspectJ](https://eclipse.org/aspectj) - 无缝面向方面的编程扩展.
- [DCEVM](https://dcevm.github.io) -  JVM修改，允许在运行时无限制地重新定义已加载的类.
- [Faux Pas](https://github.com/zalando/faux-pas) - 通过规避Java Runtime中的任何功能接口都不允许抛出已检查异常的问题来简化错误处理的库.
- [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent) - 无限的运行时类和资源重新定义.
- [JavaParser](https://github.com/javaparser/javaparser) - 解析，修改和生成Java代码.
- [JavaSymbolSolver](https://github.com/javaparser/javasymbolsolver) -  Java的符号求解器.
-  [JRebel！[c]]（https://zeroturnaround.com/software/jrebel） - 即时重新加载代码和配置更改，无需重新部署.
- [NoException](https://noexception.machinezoo.com) - 允许在功能接口中检查异常并将异常转换为可选返回.
- [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow)   - 忽略没有字节码操作的已检查异常.  也可以在Java 8流操作中使用.

### Distributed Applications

*用于编写分布式和容错应用程序的库和框架.*

- [Apache Geode](https://geode.apache.org) - 内存数据管理系统，提供可靠的异步事件通知和有保证的消息传递.
- [Apache Storm](https://storm.apache.org) - 实时计算系统.
- [Apache ZooKeeper](https://zookeeper.apache.org) - 具有分布式配置，同步和大型分布式系统命名注册表的协调服务.
- [Atomix](http://atomix.io/) - 容错分布式协调框架.
- [Axon Framework](http://www.axonframework.org) - 用于创建CQRS应用程序的框架.
- [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker) -  Dropwizard的断路器设计模式.
- [Failsafe](https://github.com/jhalterman/failsafe) - 通过重试和断路器进行简单的故障处理.
-  [Hazelcast！[c]]（https://hazelcast.org） - 具有免费开源版本的高度可扩展的内存数据网格.
- [Hystrix](https://github.com/Netflix/Hystrix) - 提供延迟和容错能力.
- [JGroups](http://www.jgroups.org) - 用于可靠消息传递和集群创建的工具包.
- [Orbit](http://www.orbit.cloud)   - 虚拟演员;  为传统演员增加了另一层次的抽象.
- [Quasar](https://www.paralleluniverse.co/quasar) -  JVM的轻量级线程和actor.
- [resilience4j](https://github.com/resilience4j/resilience4j) - 功能容错库.
- [ScaleCube](https://github.com/scalecube/scalecube) - 基于SWIM和八卦协议的可嵌入集群成员库.
- [Zuul](https://github.com/Netflix/zuul) - 提供动态路由，监控，弹性，安全性等的网关服务.

### Distributed Transactions

*分布式事务提供了一种机制，可确保在存在并发访问和部分故障时数据更新的一致性.*

- [Atomikos](https://www.atomikos.com) - 为REST，SOA和微服务提供事务，并支持JTA和XA.
- [Bitronix](https://github.com/bitronix/btm) -  JTA 1.1 API的简单但完整的实现.
- [Narayana](http://narayana.io) - 为传统的ACID和补偿交易提供支持，也符合JTA，JTS和其他标准.

### Distribution

*处理本机格式应用程序分发的工具.*

  -  [Bintray！[c]]（https://bintray.com） - 处理发布的二进制文件的版本控制.  与Maven或Gradle兼容，提供免费的开源软件计划以及多个商业计划.
- [Boxfuse](https://boxfuse.com) - 使用不可变基础架构的原则将JVM应用程序部署到AWS.
- [Capsule](http://www.capsule.io)   - 简单而强大的打包和部署.  类固醇上的胖JAR，或支持JVM优化容器的“Docker for Java”.
- [Central Repository](https://search.maven.org)   - 最大的二进制组件存储库，可作为开源社区的免费服务.  默认情况下由Apache Maven使用，并且可在所有其他构建工具中使用.
-  [Cloudsmith！[c]]（https://cloudsmith.io） - 完全托管的包管理SaaS，支持Maven / Gradle / SBT.
- [IzPack](http://izpack.org) - 用于跨平台部署的安装创作工具.
- [JitPack](https://jitpack.io)   -  GitHub易于使用的软件包存储库.  按需构建Maven / Gradle项目并发布即用型软件包.
-  [Nexus！[c]]（https://www.sonatype.com/nexus/solution-overview） - 具有代理和缓存功能的二进制管理.
- [packr](https://github.com/libgdx/packr) - 在Windows，Linux和Mac OS X上打包JAR，资产和JVM以进行本机分发.
- [really-executable-jars-maven-plugin](https://github.com/brianm/really-executable-jars-maven-plugin) - 用于制作自动执行JAR的Maven插件.

### Document Processing

*协助处理办公文档格式的图书馆.*

- [Apache POI](https://poi.apache.org/) - 支持OOXML（XLSX，DOCX，PPTX）以及OLE2（XLS，DOC或PPT）.
- [documents4j](http://documents4j.com) - 使用MS Word等第三方转换器进行文档格式转换的API.
- [docx4j](https://www.docx4java.org/trac/docx4j) - 创建和操作Microsoft Open XML文件.
- [zerocell](https://github.com/creditdatamw/zerocell) - 基于注释的API，用于将Excel工作表中的数据读入POJO，重点是减少开销.

### Formal Verification

*正式方法工具：证明助理，模型检查，符号执行等*

- [CATG](https://github.com/ksen007/janala2)   -  Concolic单元测试引擎.  使用正式方法自动生成单元测试.
- [Checker Framework](https://types.cs.washington.edu/checker-framework)   - 可插拔式系统.  包括空值类型，物理单位，不变性类型等.
- [Daikon](https://plse.cs.washington.edu/daikon) - 检测可能的程序不变量，并根据这些不变量生成JML规范.
- [Java Path Finder (JPF)](https://babelfish.arc.nasa.gov/trac/jpf)   - 包含模型检查器等的JVM形式验证工具.  由美国宇航局创建.
- [JMLOK 2.0](http://massoni.computacao.ufcg.edu.br/home/jmlok) - 通过反馈导向的随机测试生成检测代码和JML规范之间的不一致性，并建议检测到每个不合格的可能原因.
- [KeY](https://key-project.org)   - 正式的软件开发工具，旨在尽可能无缝地集成面向对象软件的设计，实现，形式规范和形式验证.  使用JML进行规范和符号执行以进行验证.
- [OpenJML](https://openjml.github.io) - 将JML规范转换为SMT-LIB格式，并将程序隐含的证明问题传递给后端求解器.

### Functional Programming

*促进功能编程的库.*

- [cyclops-react](https://github.com/aol/cyclops-react) -  Monad和流实用程序，理解，模式匹配，所有JDK集合的功能扩展，未来流，蹦床等等.
- [derive4j](https://github.com/derive4j/derive4j) -  Java 8注释处理器和框架，用于派生代数数据类型构造函数，模式匹配和态射.
- [Fugue](https://bitbucket.org/atlassian/fugue) - 番石榴的功能扩展.
- [Functional Java](http://www.functionaljava.org) - 实现许多基本和高级编程抽象，有助于面向组合的开发.
- [jOOλ](https://github.com/jOOQ/jOOL) - 扩展到Java 8，旨在通过提供众多缺失类型和一组丰富的顺序Stream API添加来修复lambda中的空白.
- [protonpack](https://github.com/poetix/protonpack) - 流实用程序的集合.
- [StreamEx](https://github.com/amaembo/streamex) - 增强Java 8 Streams.
- [Vavr](http://www.vavr.io) - 功能组件库，提供持久数据类型和功能控制结构.

### Game Development

*支持游戏开发的框架.*

- [FXGL](https://almasb.github.io/FXGL) -  JavaFX游戏开发框架.
- [jMonkeyEngine](http://jmonkeyengine.org) - 用于现代3D开发的游戏引擎.
- [libGDX](https://libgdx.badlogicgames.com) - 全方位的跨平台，高级框架.
- [LWJGL](https://www.lwjgl.org) - 强大的框架，抽象出像OpenGL / CL / AL这样的库.

### Geospatial

*用于处理地理空间数据和算法的库.*

- [Apache SIS](https://sis.apache.org) - 用于开发地理空间应用程序的库.
- [Geo](https://github.com/davidmoten/geo) -  Java中的GeoHash实用程序.
- [Geotoolkit.org](http://www.geotoolkit.org)   - 用于开发地理空间应用程序的库.  建立在Apache SIS项目之上.
- [GeoTools](http://geotools.org) - 为地理空间数据提供工具的库.
- [GraphHopper](https://github.com/graphhopper/graphhopper)   - 道路路由引擎.  用作Java库或独立Web服务.
- [H2GIS](http://www.h2gis.org) -  H2数据库的空间扩展.
- [Jgeohash](https://astrapi69.github.io/jgeohash) - 使用GeoHash算法的库.
- [Mapsforge](https://github.com/mapsforge/mapsforge) - 基于OpenStreetMap数据的地图渲染.
- [Spatial4j](https://github.com/locationtech/spatial4j) - 通用空间/地理空间图书馆.

### GUI

*Libraries to create modern graphical user interfaces.*

- [JavaFX](https://www.oracle.com/technetwork/java/javase/overview/javafx-overview-2158620.html) -  Swing的继任者.
- [Scene Builder](https://gluonhq.com/open-source/scene-builder) -  JavaFX应用程序的可视化布局工具.
- [SWT](https://www.eclipse.org/swt) - 标准窗口小部件工具包，图形窗口小部件工具包.

### High Performance

*关于高性能计算的一切，从集合到特定的库.*

- [Agrona](https://github.com/real-logic/Agrona) - 高性能应用程序中常见的数据结构和实用程序方法.
- [Disruptor](https://lmax-exchange.github.io/disruptor) - 线程间消息库.
- [Eclipse Collections](https://github.com/eclipse/eclipse-collections) - 受Smalltalk启发的收藏框架.
- [fastutil](http://fastutil.di.unimi.it) - 快速和紧凑的特定类型集合.
- [HPPC](https://labs.carrotsearch.com/hppc.html) - 原始收藏品.
- [JCTools](https://github.com/JCTools/JCTools) -  JDK目前​​缺少并发工具.
- [Koloboke](https://github.com/OpenHFT/Koloboke) - 哈希集和哈希映射.

### HTTP Clients

*协助创建HTTP请求和/或绑定响应的库.*

- [Async Http Client](https://github.com/AsyncHttpClient/async-http-client) - 异步HTTP和WebSocket客户端库.
- [Feign](https://github.com/Netflix/feign) - 受Retrofit，JAXRS-2.0和WebSocket启发的HTTP客户端绑定器.
- [OkHttp](https://square.github.io/okhttp) -  HTTP + SPDY客户端.
- [Play WS](https://github.com/playframework/play-ws) - 具有反应流和缓存的Typesafe客户端.
- [restQL-core](https://github.com/B2W-BIT/restQL-core) - 从多个服务获取信息的微服务查询语言.
- [Retrofit](https://square.github.io/retrofit) -  Typesafe REST客户端.
- [Ribbon](https://github.com/Netflix/ribbon) - 在云中经过实战测试的客户端IPC库.
- [Riptide](https://github.com/zalando/riptide) -  Spring的RestTemplate的客户端响应路由.

### Hypermedia Types

*处理超媒体类型序列化的库.*

- [JSON-LD](https://github.com/jsonld-java/jsonld-java) -  JSON-LD实现.
- [Siren4J](https://github.com/eserating/siren4j) -  Siren规范库.

### IDE

*集成开发环境，试图简化开发的几个方面.*

- [Eclipse](https://www.eclipse.org) - 建立开源项目，支持大量插件和语言.
  -  [IntelliJ IDEA！[c]]（https://www.jetbrains.com/idea） - 支持多种JVM语言，为Android开发提供了很好的选择.  商业版面向企业部门.
- [NetBeans](https://netbeans.org) - 提供从数据库访问到HTML5的多个Java SE和EE功能的集成.
- [Visual Studio Code](https://code.visualstudio.com/docs/languages/java) - 通过使用内部市场的扩展，通过简单，现代的工作流为轻量级项目提供Java支持.

### Imagery

*协助创建，评估或处理图形图像的库.*

- [Imgscalr](https://github.com/thebuzzmedia/imgscalr) - 在纯Java 2D中实现的简单，高效且硬件加速的图像缩放库.
- [Tess4J](https://github.com/nguyenq/tess4j) -  Tesseract OCR API的JNA包装器.
- [Thumbnailator](https://github.com/coobird/thumbnailator) - 高质量的缩略图生成库.
- [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys) - 插件集合，扩展了支持的图像文件格式的数量.
- [ZXing](https://github.com/zxing/zxing) - 多格式1D / 2D条形码图像处理库.

### JSON

*用于将JSON序列化和反序列化为Java对象的库.*

- [DSL-JSON](https://github.com/ngs-doo/dsl-json) - 具有高级编译时数据绑定的JSON库.
- [Genson](https://owlike.github.io/genson) - 功能强大且易于使用的Java-to-JSON转换库.
- [Gson](https://github.com/google/gson)   - 将对象序列化为JSON，反之亦然.  即时使用具有良好的性能.
- [HikariJSON](https://github.com/brettwooldridge/HikariJSON) - 高性能JSON解析器，比Jackson快2倍.
- [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8) - 用于Java 8数据类型和功能的Jackson模块集.
- [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money) - 开源Jackson模块，支持JSON序列化和JavaMoney数据类型的反序列化.
- [Jackson](https://github.com/FasterXML/jackson) - 与GSON类似，但如果需要更频繁地实例化库，则可以提高性能.
- [JSON-io](https://github.com/jdereg/json-io)   - 将Java转换为JSON.  将JSON转换为Java.  漂亮的印刷JSON.  Java JSON序列化程序.
- [jsoniter](http://jsoniter.com) - 具有迭代器和延迟解析API的快速灵活的库.
- [LoganSquare](https://github.com/bluelinelabs/LoganSquare)   - 基于Jackson的流API的JSON解析和序列化库.  优于GSON＆Jackson的图书馆.
- [Moshi](https://github.com/square/moshi) - 现代JSON库，不那么自以为是，并使用List和Map等内置类型.
- [Yasson](https://github.com/eclipse/yasson) - 类和JSON文档之间的绑定层，类似于JAXB.

### JSON Processing

*用于处理JSON格式数据的库.*

- [fastjson](https://github.com/alibaba/fastjson) - 非常快的处理器，没有额外的依赖性和完整的数据绑定.
- [Jolt](https://github.com/bazaarvoice/jolt) -  JSON到JSON转换工具.
- [JsonPath](https://github.com/jayway/JsonPath) - 使用类似XPATH的语法从JSON中提取数据.
- [JsonSurfer](https://github.com/jsurfer/JsonSurfer) - 流JasonPath处理器，专用于处理大而复杂的JSON数据.

### JVM and JDK

* JVM / JDK的当前实现.*

- [Adopt Open JDK](https://adoptopenjdk.net) -  OpenJDK构建，允许在HotSpot和OpenJ9之间进行选择.
- [Avian](https://github.com/ReadyTalk/avian) - 具有JIT，AOT模式和iOS端口的JVM.
- [Corretto](https://aws.amazon.com/corretto) - 亚马逊的免费，多平台，生产就绪的OpenJDK分发.
- [Graal](https://github.com/oracle/graal) -  Polyglot可嵌入JVM.
- [Liberica JDK](https://www.bell-sw.com/java.html) - 由OpenJDK构建，经过全面测试并通过了JCK.
- [OpenJ9](https://github.com/eclipse/openj9) - 高性能，企业级，灵活许可，开放式管理的跨平台JVM，可扩展和扩充Eclipse OMR和OpenJDK项目中的运行时技术组件.
- [Open JDK](https://openjdk.java.net) - 打开由Oracle分发的JDK.
- [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm) - 适用于iOS的非阻塞并发GC的VM.
- [RedHat Open JDK](https://developers.redhat.com/products/openjdk/overview) -  RedHat的OpenJDK发行版.
- [Zulu](https://www.azul.com/downloads/zulu) - 适用于Windows，Linux和Mac OS X的OpenJDK版本.

### Logging

*记录应用程序行为的库.*

- [Apache Log4j 2](https://logging.apache.org/log4j) - 使用强大的插件和配置架构完成重写.
- [Graylog](https://www.graylog.org) - 适用于扩展角色和权限管理的开源聚合器.
- [Kibana](https://www.elastic.co/products/kibana)   - 分析和可视化日志文件.  某些功能需要付款.
- [Logback](https://logback.qos.ch) - 通过Groovy提供有趣配置选项的强大日志库.
- [Logbook](https://github.com/zalando/logbook) - 用于HTTP请求和响应记录的可扩展开源库.
- [Logstash](https://www.elastic.co/products/logstash) - 用于管理日志文件的工具.
- [p6spy](https://github.com/p6spy/p6spy) - 无需更改代码即可为所有JDBC事务记录日志.
- [SLF4J](https://www.slf4j.org) - 抽象层/简单的伐木门面.
- [tinylog](http://www.tinylog.org) - 具有静态记录器类的轻量级日志记录框架.
- [Tracer](https://github.com/zalando/tracer) - 在分布式系统中调用跟踪和日志关联.

### Machine Learning

*提供用于从数据中学习的特定统计算法的工具.*

- [Apache Flink](https://flink.apache.org) - 快速，可靠，大规模的数据处理引擎.
- [Apache Mahout](https://mahout.apache.org) - 可扩展的算法，侧重于协同过滤，聚类和分类.
- [Apache Spark](https://spark.apache.org) - 数据分析集群计算框架.
- [DatumBox](http://www.datumbox.com) - 为自然语言处理提供多种算法和预训练模型.
- [DeepDive](http://deepdive.stanford.edu) - 从非结构化数据创建结构化信息，并将其集成到现有数据库中.
- [Deeplearning4j](https://deeplearning4j.org) - 分布式和多线程深度学习库.
- [H2O](https://www.h2o.ai) - 用于统计大数据的分析引擎.
- [JSAT](https://github.com/EdwardRaff/JSAT) - 支持多线程执行的预处理，分类，回归和聚类算法.
- [Oryx 2](https://github.com/OryxProject/oryx)   - 构建实时，大规模机器学习应用程序的框架.  包括用于协作过滤，分类，回归和群集的端到端应用程序.
- [Smile](https://haifengl.github.io/smile) - 统计机器智能和学习引擎提供一组机器学习算法和可视化库.
- [Weka](https://www.cs.waikato.ac.nz/ml/weka) - 从预处理到可视化的数据挖掘任务的算法集合.

### Messaging

*有助于在客户端之间发送消息以确保协议独立性的工具.*

- [Aeron](https://github.com/real-logic/Aeron) - 高效，可靠，单播和多播消息传输.
- [Apache ActiveMQ](https://activemq.apache.org) - 实现JMS并将同步转换为异步通信的消息代理.
- [Apache Camel](https://camel.apache.org) - 通过企业集成模式将不同的传输API粘合在一起.
- [Apache Kafka](https://kafka.apache.org) - 高吞吐量分布式消息传递系统.
- [Apache Pulsar](https://pulsar.apache.org) - 分布式发布/子消息系统.
- [Apache RocketMQ](https://rocketmq.apache.org/) - 快速，可靠，可扩展的分布式消息传递平台.
- [Apache Qpid](https://qpid.apache.org) -  Apache Qpid使消息传递工具可以说AMQP并支持多种语言和平台.
- [EventBus](https://github.com/greenrobot/EventBus) - 简单的发布/订阅事件总线.
- [Hermes](http://hermes.allegro.tech) - 建立在Kafka之上的快速可靠的消息代理.
- [JeroMQ](https://github.com/zeromq/jeromq) -  ZeroMQ的实施.
- [Nakadi](https://github.com/zalando/nakadi) - 在Kafka之上提供RESTful API.
- [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client) -  RabbitMQ客户端.
- [Smack](https://github.com/igniterealtime/Smack) - 跨平台XMPP客户端库.
- [NATS client](https://github.com/nats-io/java-nats) -  NATS客户端.

### Miscellaneous

*其他一切.*

- [Codename One](https://www.codenameone.com) - 用于编写本机移动应用程序的跨平台解决方案.
- [CQEngine](https://github.com/npgall/cqengine) -  Java集合上的超快速，类似SQL的查询.
- [Design Patterns](https://github.com/iluwatar/java-design-patterns) - 实施和解释最常见的设计模式.
- [Failsafe](https://github.com/jhalterman/failsafe) - 通过重试和断路器进行简单的故障处理.
- [FF4J](https://github.com/ff4j/ff4j) -  Java的功能标志.
- [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) - 为严肃的商业目的严肃的商人制作的FizzBu​​zz的严肃实施.
- [J2ObjC](https://github.com/google/j2objc) - 用于将Android库移植到iOS的Java-to-Objective-C转换器.
- [JavaCV](https://github.com/bytedeco/javacv) -  OpenCV，FFmpeg等Java接口.
- [JavaX](http://javax.ai1.lol) - 重点发展Java，重点是简单性.
- [JBake](http://jbake.org) - 静态网站生成器.
- [JBot](https://github.com/ramswaroop/jbot) - 构建聊天机器人的框架.
- [JCuda](http://jcuda.org) -  JCuda为CUDA和CUDA相关库提供Java绑定.
- [Jimfs](https://github.com/google/jimfs) - 内存文件系统.
- [Joda-Money](http://www.joda.org/joda-money) -  JDK未提供的基本货币和金钱类以及算法.
- [JPad](http://jpad.io) - 片段转轮.
- [LightAdmin](http://lightadmin.org) - 可插拔的CRUD UI库，用于快速应用程序开发.
- [Maven Wrapper](https://github.com/takari/maven-wrapper) -  Maven的Gradle Wrapper模拟，允许在不安装maven的情况下构建项目.
- [Membrane Service Proxy](https://github.com/membrane/service-proxy) - 用Java编写的开源反向代理框架.
- [MinimalFTP](https://github.com/Guichaguri/MinimalFTP) - 轻量级，小型和可定制的FTP服务器.
- [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial) - 流行的Java 8指南.
- [Modernizer](https://github.com/andrewgaul/modernizer-maven-plugin) - 检测旧Java API的使用.
- [Multi-OS Engine](https://software.intel.com/en-us/multi-os-engine) - 开发本地移动（iOS，Android等）应用程序的开源跨平台引擎.
- [OpenRefine](http://openrefine.org) - 处理凌乱数据的工具：清理，转换，使用Web服务扩展它并将其链接到数据库.
- [PipelinR](https://github.com/sizovs/pipelinr) - 用于在管道中使用处理程序和命令的小型实用程序库. 
- [Polyglot for Maven](https://github.com/takari/polyglot-maven) -  Maven 3.3.1+的扩展，允许用XML以外的方言编写POM模型.
- [Smooks](https://github.com/smooks/smooks) - 用于构建处理数据的应用程序的可扩展框架，这意味着绑定，转换，消息处理和丰富.
- [Togglz](https://www.togglz.org) -  Feature Toggles模式的实现.
- [TypeTools](https://github.com/jhalterman/typetools) - 用于解析泛型类型的工具.
- [XMLBeam](https://github.com/SvenEwald/xmlbeam) - 在代码中使用注释或XPath处理XML.
- [OctoLinker](https://github.com/OctoLinker/browser-extension) - 浏览器扩展，允许更有效地浏览GitHub上的代码.

### Microservice

*用于创建和管理微服务的工具.*

- [Apollo](https://spotify.github.io/apollo) - 用于编写可组合微服务的库.
- [consul-api](https://github.com/Ecwid/consul-api) - 客户 [Consul](https://www.consul.io) API：分布式，高可用性和数据中心感知的注册表/发现服务.
- [Eureka](https://github.com/Netflix/eureka) - 基于REST的服务注册表，用于弹性负载平衡和故障转移.
- [Helidon](https://helidon.io) - 用于编写微服务的双向方法：功能反应和作为实现 [MicroProfile](https://microprofile.io).
- [Lagom](https://www.lightbend.com/lagom) - 用于创建基于微服务的系统的框架.
- [Micronaut](http://micronaut.io) - 现代全栈框架，专注于模块化，最小内存占用和启动时间.

### Monitoring

*监控生产中应用程序的工具.*

-  [AppDynamics！[c]]（https://www.appdynamics.com） - 性能监视器.
- [Automon](https://github.com/stevensouza/automon) - 将AOP的强大功能与监控和/或记录工具相结合.
-  [BugSnag！[c]]（https://www.bugsnag.com） - 异常和错误监控，集成了多个第三方工具，可实现更好的工作流程和免费的业余爱好者层.
- [LeakCanary](https://github.com/square/leakcanary) - 内存泄漏检测.
- [Failsafe Actuator](https://github.com/zalando-incubator/failsafe-actuator) - 在Spring-Boot环境中开箱即用监控故障安全断路器.
- [Glowroot](https://glowroot.org) - 开源Java APM.
- [inspectIT](http://www.inspectit.rocks)   - 通过可以即时更改的挂钩捕获详细的运行时信息.  它支持通过OpenTracing API跟踪多个系统，并可以将数据与最终用户监控相关联.
- [Instrumental ![c]](https://instrumentalapp.com) - Real-time Java application performance monitoring. A commercial service with free development accounts.
- [JavaMelody](https://github.com/javamelody/javamelody) - 绩效监测和分析.
- [Jaeger client](https://github.com/jaegertracing/jaeger-client-java) -  Jaeger客户.
- [jmxtrans](https://github.com/jmxtrans/jmxtrans)   - 连接到多个JVM并通过JMX查询它们的属性.  它的查询语言基于JSON，允许非Java程序员访问JVM属性.  支持不同的输出写入，包括Graphite，Ganglia和StatsD.
- [Jolokia](https://jolokia.org) -  JMX over REST.
- [Kamon](http://www.kamon.io) - 用于监视在JVM上运行的应用程序的工具.
- [Metrics](http://metrics.dropwizard.io) - 通过JMX或HTTP公开指标并将其发送到数据库.
-  [New Relic！[c]]（https://newrelic.com） - 性能监视器.
-  [Datadog！[c]]（https://docs.datadoghq.com/tracing/setup/java/） - 现代监控和分析.
- [nudge4j](https://github.com/lorenzoongithub/nudge4j) - 通过字节码注入从Java 8浏览器远程开发人员控制台.
-  [OverOps！[c]]（https://www.overops.com） - 生产中错误监控和调试.
- [Pinpoint](https://github.com/naver/pinpoint) - 开源APM工具.
- [Prometheus](https://prometheus.io) - 提供多维数据模型，DSL，自治服务器节点等等.
-  [SPM！[c]]（https://sematext.com/spm） - 具有JVM应用程序分发事务跟踪的性能监视器.
- [Stagemonitor](https://github.com/stagemonitor/stagemonitor) -  JVM应用程序的开源性能监视和事务跟踪.
- [Sysmon](https://github.com/palantir/Sysmon) - 适用于Java VM的轻量级平台监控工具.
- [zipkin](https://zipkin.io) - 分布式跟踪系统，它收集解决微服务架构中的延迟问题所需的时序数据.

### Native
*用于使用特定于平台的本机库.*

- [JavaCPP](https://github.com/bytedeco/javacpp) - 提供对原生C ++的高效和轻松访问.
- [JNA](https://github.com/java-native-access/jna)   - 无需编写JNI即可使用本机库.  还提供了通用系统库的接口.
- [JNR](https://github.com/jnr/jnr-ffi)   - 无需编写JNI即可使用本机库.  还提供了通用系统库的接口.  与JNA目标相同，但更快，并作为即将到来的基础 [Project Panama](http://openjdk.java.net/projects/panama).

### Natural Language Processing

*专门处理文本的图书馆.*

- [CogCompNLP](https://github.com/CogComp/cogcomp-nlp) - 为纯文本输入提供通用注释器.
- [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml) - 为标记，命名实体识别和情感分析等任务提供一组基本工具.
- [DKPro](https://dkpro.github.io) - 收集可重复使用的NLP工具，用于语言预处理，机器学习，词汇资源等.
- [Lingua](https://github.com/pemistahl/lingua) - 自然语言检测库，特别适用于短文本段落.
- [LingPipe](http://alias-i.com/lingpipe) - 用于从POS标记到情感分析的任务的工具包.

### Networking

*用于构建网络服务器的库.*

- [AkkaGRPC](https://github.com/akka/akka-grpc) - 支持在Akka Streams之上构建流式gRPC服务器和客户端.
- [Comsat](https://github.com/puniverse/comsat) - 将标准的Java Web相关API与Quasar光纤和actor集成.
- [Dubbo](https://github.com/alibaba/dubbo) - 高性能RPC框架.
- [Finagle](https://github.com/twitter/finagle)   - 用于构建高并发服务器的可扩展RPC系统.  它为多个协议实现统一的客户端和服务器API，并且与协议无关，以简化新协议的实现.
- [Grizzly](https://javaee.github.io/grizzly)   -  NIO框架.  用作Glassfish中的网络层.
- [gRPC](https://github.com/grpc/grpc-java) - 基于protobuf和HTTP / 2的RPC框架.
- [KryoNet](https://github.com/EsotericSoftware/kryonet) - 使用NIO和Kryo​​为高效的TCP和UDP客户端/服务器网络通信提供简洁的API.
- [MINA](https://mina.apache.org) - 抽象的，事件驱动的异步I / O API，用于通过Java NIO进行TCP / IP和UDP / IP上的网络操作.
- [Netty](https://netty.io) - 构建高性能网络应用程序的框架.
- [Nifty](https://github.com/facebook/nifty) - 在Netty上实施Thrift客户端和服务器.
- [sshj](https://github.com/hierynomus/sshj) - 以编程方式使用SSH，SCP或SFTP.
- [TLS Channel](https://github.com/marianobarrios/tls-channel) - 通过SSLEngine实现ByteChannel接口，实现易于使用（类似套接字）的TLS.
- [Undertow](http://undertow.io) - Web server providing both blocking and non-blocking APIs based on NIO. Used as a network layer in WildFly.
- [urnlib](https://github.com/slub/urnlib) - 表示，解析和编码URN，如RFC 2141中所述.

### ORM

*处理对象持久性的API.*

- [Apache Cayenne](https://cayenne.apache.org)   - 为数据访问提供干净，静态的API.  还包括用于处理数据库映射的GUI Modeler，以及DB逆向工程和生成.
- [Ebean](https://ebean-orm.github.io) - 提供简单快速的数据访问.
- [EclipseLink](https://www.eclipse.org/eclipselink) - 支持许多持久性标准：JPA，JAXB，JCA和SDO.
- [Hibernate](http://hibernate.org/orm) - 健壮且广泛使用，拥有活跃的社区.
- [MyBatis](http://www.mybatis.org/mybatis-3) - 使用存储过程或SQL语句耦合对象.
- [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper) - 简单的数据库和CSV映射器.

### PaaS

* Java平台即服务.*

-  [AWS Elastic Beanstalk！[c]]（https://aws.amazon.com/elasticbeanstalk） - 基于AWS，支持Tomcat和Jetty.
-  [AWS Lambda！[c]]（https://aws.amazon.com/lambda） - 无服务器计算.
-  [Google App Engine！[c]]（https://cloud.google.com） -  Google基础架构上的PaaS.
-  [Heroku！[c]]（https://www.heroku.com） - 抽象的计算环境.
-  [Jelastic！[c]]（https://jelastic.com） - 支持Tomcat，Jetty，GlassFish，JBoss，TomEE和WildFly.
-  [OpenShift Enterprise！[c]]（https://www.openshift.com） - 内部部署解决方案.

### PDF

*帮助创建PDF文件的工具.*

- [Apache FOP](https://xmlgraphics.apache.org/fop) - 从XSL-FO创建PDF.
- [Apache PDFBox](https://pdfbox.apache.org) - 用于创建和操作PDF的工具箱.
- [Dynamic Jasper](http://dynamicjasper.com) -  JasperReports的抽象层.
- [DynamicReports](http://dynamicreports.org) - 简化JasperReports.
- [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer) -  XML / XHTML和CSS 2.1渲染器.
-  [iText！[c]]（https://itextpdf.com） - 以编程方式创建PDF文件.
- [JasperReports](https://community.jaspersoft.com/project/jasperreports-library) - 复杂的报告引擎.

### Performance analysis

*用于性能分析，分析和基准测试的工具.*

-  [fastThread！[c]]（http://fastthread.io） - 使用免费的基于云的上传界面分析和可视化线程转储.
  -  [GCeasy！[c]]（http://gceasy.io） - 分析和可视化GC日志的工具.  它提供免费的基于云的上传界面.
- [honest-profiler](https://github.com/RichardWarburton/honest-profiler) - 低开销，无偏置采样分析器.
- [jHiccup](https://github.com/giltene/jHiccup) - 记录和记录平台JVM停顿.
- [JITWatch](https://github.com/AdoptOpenJDK/jitwatch) - 分析HotSpot JVM所做的JIT编译器优化.
- [JMH](http://openjdk.java.net/projects/code-tools/jmh) - 用于构建，运行和分析用Java和其他语言编写的针对JVM的nano / micro / milli / macro基准测试的Java工具.
-  [JProfiler！[c]]（https://www.ej-technologies.com/products/jprofiler/overview.html） -  JDBC，JPA和NoSQL的数据库分析，支持JEE.
- [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils) - 用于延迟测量和报告的实用程序.
-  [XRebel！[c]]（https://zeroturnaround.com/software/xrebel） - 使用浏览器内部小部件对Web应用程序进行实时分析.
-  [YourKit Java Profiler！[c]]（https://www.yourkit.com/features） - 在JVM上运行的任何应用程序的Profiler.

### Platform

*框架是包含多个类别的多个库的套件.*

#### Apache Commons

- [BCEL](http://commons.apache.org/proper/commons-bcel) - 字节代码工程库 - 分析，创建和操作Java类文件.
- [BeanUtils](http://commons.apache.org/proper/commons-beanutils) - 围绕Java反射和内省API的易于使用的包装器.
- [BeanUtils2](http://commons.apache.org/sandbox/commons-beanutils2) - 重新设计Commons BeanUtils.
- [BSF](http://commons.apache.org/proper/commons-bsf) -  Bean Scripting Framework  - 脚本语言的接口，包括JSR-223.
- [Chain](http://commons.apache.org/proper/commons-chain) - 责任链模式实施.
- [ClassScan](http://commons.apache.org/sandbox/commons-classscan) - 无需加载即可查找类接口，方法，字段和注释.
- [CLI](http://commons.apache.org/proper/commons-cli) - 命令行参数解析器.
- [CLI2](http://commons.apache.org/sandbox/commons-cli2) 重新设计Commons CLI.
- [Codec](http://commons.apache.org/proper/commons-codec) - 通用编码/解码算法（例如语音，base64，URL）.
- [Collections](http://commons.apache.org/proper/commons-collections) - 扩展或扩充Java Collections Framework.
- [Compress](http://commons.apache.org/proper/commons-compress) - 定义用于处理tar，zip和bzip2文件的API.
- [Configuration](http://commons.apache.org/proper/commons-configuration) - 以各种格式读取配置/首选项文件.
- [Convert](http://commons.apache.org/sandbox/commons-convert) -  Commons-Convert旨在提供一个专门用于将一种类型的对象转换为另一种类型的任务的库.
- [CSV](http://commons.apache.org/proper/commons-csv) - 用于读取和写入逗号分隔值文件的组件.
- [Daemon](http://commons.apache.org/proper/commons-daemon) - 类似于unix-daemon的java代码的替代调用机制.
- [DBCP](http://commons.apache.org/proper/commons-dbcp) - 数据库连接池服务.
- [DbUtils](http://commons.apache.org/proper/commons-dbutils) -  JDBC帮助程序库.
- [Digester](http://commons.apache.org/proper/commons-digester) -  XML-to-Java-object映射实用程序.
- [Email](http://commons.apache.org/proper/commons-email) - 用于从Java发送电子邮件的库.
- [Exec](http://commons.apache.org/proper/commons-exec) - 用于在Java中处理外部流程执行和环境管理的API.
- [FileUpload](http://commons.apache.org/proper/commons-fileupload) -  servlet和Web应用程序的文件上载功能.
- [Finder](http://commons.apache.org/sandbox/commons-finder) - 受UNIX find命令启发的Java库.
- [Flatfile](http://commons.apache.org/sandbox/commons-flatfile) - 用于处理平面数据结构的Java库.
- [Functor](http://commons.apache.org/proper/commons-functor) - 仿函数是一种可以作为对象操作的函数，或者是表示单个通用函数的对象.
- [Graph](http://commons.apache.org/sandbox/commons-graph) - 通用图形API和算法.
- [I18n](http://commons.apache.org/sandbox/commons-i18n) - 添加由一个或多个属于一起的本地化文本组成的本地化消息包的功能.
- [Id](http://commons.apache.org/sandbox/commons-id) -  Id是用于生成标识符的组件.
- [Imaging](http://commons.apache.org/proper/commons-imaging) - 纯Java图像库.
- [IO](http://commons.apache.org/proper/commons-io) -  I / O实用程序的集合.
- [Javaflow](http://commons.apache.org/sandbox/commons-javaflow) - 继续实施以捕获应用程序的状态.
- [JCI](http://commons.apache.org/proper/commons-jci) -  Java编译器接口.
- [JCS](http://commons.apache.org/proper/commons-jcs) -  Java缓存系统.
- [Jelly](http://commons.apache.org/proper/commons-jelly) - 基于XML的脚本和处理引擎.
- [Jexl](http://commons.apache.org/proper/commons-jexl) - 表达语言，它扩展了JSTL的表达式语言.
- [JNet](http://commons.apache.org/sandbox/commons-jnet) -  JNet允许通过java.net API动态注册url流处理程序.
- [JXPath](http://commons.apache.org/proper/commons-jxpath) - 使用XPath语法操作Java Bean的实用程序.
- [Lang](http://commons.apache.org/proper/commons-lang) - 为java.lang中的类提供额外的功能.
- [Logging](https://en.wikipedia.org/wiki/Apache_Commons_Logging) 围绕各种日志API实现的包装器.
- [Math](http://commons.apache.org/proper/commons-math) - 轻量级，独立的数学和统计组件.
- [Monitoring](http://commons.apache.org/sandbox/commons-monitoring) - 监控旨在为Java应用程序提供简单但可扩展的监控解决方案.
- [Nabla](http://commons.apache.org/sandbox/commons-nabla) -  Nabla提供自动差异类，可以生成以Java语言实现的任何函数的派生.
- [Net](http://commons.apache.org/proper/commons-net) - 网络实用程序和协议实现的集合.
- [OGNL](http://commons.apache.org/proper/commons-ognl) - 对象图导航语言.
- [OpenPGP](http://commons.apache.org/sandbox/commons-openpgp) - 使用OpenPGP签名和验证数据的接口.
- [Performance](http://commons.apache.org/sandbox/commons-performance) - 用于microbenchmark客户端的小型框架，具有Commons DBCP和Pool的实现.
- [Pipeline](http://commons.apache.org/sandbox/commons-pipeline) - 提供一组围绕工作队列设计的管道实用程序，这些工作队列并行运行以顺序处理数据对象.
- [Pool](http://commons.apache.org/proper/commons-pool) - 通用对象池组件.
- [Proxy](http://commons.apache.org/proper/commons-proxy) - 用于创建动态代理的库.
- [RDF](https://commons.apache.org/proper/commons-rdf) - 可以由JVM上的系统实现的RDF 1.1的通用实现.
- [RNG](https://commons.apache.org/proper/commons-rng) -  Commons Rng提供伪随机数生成器的实现.
- [SCXML](http://commons.apache.org/proper/commons-scxml) - 旨在创建和维护Java SCXML引擎的State Chart XML规范的实现.
- [Validator](http://commons.apache.org/proper/commons-validator) - 用于在xml文件中定义验证器和验证规则的框架.
- [VFS](http://commons.apache.org/proper/commons-vfs) - 虚拟文件系统组件，用于将文件，FTP，SMB，ZIP等视为单个逻辑文件系统.
- [Weaver](http://commons.apache.org/proper/commons-weaver) - 提供一种简单的方法来增强（编织）编译的字节码.

#### Other

- [CUBA Platform](https://cuba-platform.com) - 基于Spring，EclipseLink和Vaadin开发具有丰富Web界面的企业应用程序的高级框架.
- [Light-Java](https://github.com/networknt/light-java) - 内置的快速，轻量级和高效的微服务框架 [security](https://github.com/networknt/light-oauth2).
- [Orienteer](https://github.com/OrienteerBAP/Orienteer) - 用于快速配置/开发CRM，ERP，LMS和其他应用程序的开源业务应用程序平台.
- [Spring](https://spring.io/projects) - 提供许多用于依赖注入，面向方面编程，安全性等的包.

### Processes

*帮助管理操作系统进程的库.*

- [ch.vorburger.exec](https://github.com/vorburger/ch.vorburger.exec) - 围绕Apache Commons Exec的便捷API.
- [zt-exec](https://github.com/zeroturnaround/zt-exec) - 为Apache Commons Exec和ProcessBuilder提供统一的API.
- [zt-process-killer](https://github.com/zeroturnaround/zt-process-killer) - 通过PID停止从Java或系统进程启动的进程.

### Reactive libraries

*用于开发反应性应用程序的库.*

- [Akka](https://akka.io) - 用于构建并发，分布式，容错和事件驱动应用程序的工具包和运行时.
- [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm) - 为具有无阻塞背压的异步流处理提供标准.
- [Reactor](https://projectreactor.io) - 用于构建反应式快速数据应用程序的库.
- [RxJava](https://github.com/ReactiveX/RxJava) - 允许使用可观察序列组成异步和基于事件的程序.
- [vert.x](http://vertx.io) -  Polyglot事件驱动的应用程序框架.

### REST Frameworks

*专门用于创建RESTful服务的框架.*

- [Dropwizard](https://dropwizard.github.io/dropwizard) - 使用Jetty，Jackson，Jersey和Metrics建立现代Web应用程序的意见框架.
- [Elide](http://elide.io/) - 基于JPA数据模型的JSON或GraphQL-API的观点框架.
- [javalin](https://javalin.io) -  Javalin在Jetty上只有几千行代码，这意味着它的性能几乎相当于纯Jetty.
- [Jersey](https://jersey.github.io) -  JAX-RS参考实现.
- [Microserver](https://github.com/aol/micro-server)   - 一个方便，可扩展的微服务插件系统，用于Spring和Spring Boot.  它拥有超过30个插件并且不断增长，它支持微型单块和纯微型服务.
- [Rapidoid](https://www.rapidoid.org) - 一个简单，安全且极其快速的框架，由嵌入式HTTP服务器，GUI组件和依赖注入组成.
- [rest.li](https://github.com/linkedin/rest.li) - 使用类型安全绑定和异步，非阻塞IO构建强大，可扩展的RESTful架构的框架，其中包含端到端开发人员工作流程，可促进清洁实践，统一界面设计和一致的数据建模.
- [RESTEasy](https://resteasy.jboss.org) -  JAX-RS规范的完全认证和可移植实现.
- [RestExpress](https://github.com/RestExpress/RestExpress) -  JBoss Netty HTTP堆栈上的瘦包装器，提供扩展和性能.
- [Restlet Framework](https://github.com/restlet/restlet-framework-java) - 具有强大路由和过滤功能的先锋框架，以及统一的客户端和服务器API.
- [Spark](http://sparkjava.com) -  Sinatra灵感的框架.
- [Crnk](http://www.crnk.io) - 实施JSON API规范，以构建面向资源的REST端点，包括排序，过滤，分页，链接，对象图，类型安全，批量更新，集成等.
- [Swagger](https://swagger.io) - 与REST API的标准，语言无关的接口.

### Science

*用于科学计算，分析和可视化的图书馆.*

- [DataMelt](http://jwork.org/dmelt) - 科学计算，数据分析和数据可视化的环境.
- [Erdos](https://github.com/Erdos-Graph-Framework/Erdos) - 用于理论算法的模块化，轻便且易于图形的框架.
- [GraphStream](http://graphstream-project.org) - 用于建模和分析动态图的库.
- [JFreeChart](http://www.jfree.org/jfreechart) - 用于Swing，JavaFX和服务器端应用程序的2D图表库.
- [JGraphT](https://github.com/jgrapht/jgrapht) - 图形库，提供数学图论理论对象和算法.
- [JGraphX](https://github.com/jgraph/jgraphx) - 用于可视化的库（主要是Swing）并与节点边图交互.
- [Mines Java Toolkit](https://github.com/MinesJTK/jtk) - 用于地球物理科学计算，可视化和数字信号分析的库.
- [Morpheus](http://www.zavtech.com/morpheus/docs) - 提供通用的二维内存高效表格数据结构，称为DataFrame，以便为JVM上的科学计算实现高效的内存分析.
- [Orson-Charts](https://github.com/jfree/orson-charts) - 生成各种3D图表，可以使用Swing和JavaFX显示或导出为PDF，SVG，PNG和JPEG.
- [Tablesaw](https://github.com/lwhite1/tablesaw) - 包括数据框架，嵌入式列存储以及数百种转换，汇总或过滤数据的方法.
- [XChart](https://github.com/knowm/XChart)   - 用于绘制数据的轻量级库.  可以使用许多可自定义的图表类型.

### Search

*索引文档的引擎，用于搜索和分析.*

- [Apache Lucene](https://lucene.apache.org) - 高性能，功能齐全的跨平台文本搜索引擎库.
- [Apache Solr](https://lucene.apache.org/solr) - 针对大容量流量进行了优化的企业搜索引擎.
- [Elasticsearch](https://www.elastic.co) - 具有RESTful Web界面和无架构JSON文档的分布式，多租户能力的全文搜索引擎.
- [Indexer4j](https://github.com/haeungun/indexer4j) - 简单轻便的全文索引和搜索库.

### Security

*处理安全性，身份验证，授权或会话管理的库.*

- [Apache Shiro](https://shiro.apache.org) - 执行身份验证，授权，加密和会话管理.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - 通用加密库和JCA提供程序，提供从基本帮助程序到PGP / SMIME操作的各种功能.
- [Cryptomator](https://cryptomator.org) - 云中文件的多平台，透明，客户端加密.
- [Hdiv](https://github.com/hdiv/hdiv) - 运行时应用程序，可以排除OWASP Top 10中包含的应用程序安全风险，包括SQL注入，跨站点脚本，跨站点请求伪造，数据篡改和暴力攻击.
- [jjwt](https://github.com/jwtk/jjwt) - 适用于Java和Android的JSON Web令牌.
- [Jwks RSA](https://github.com/auth0/jwks-rsa-java) - JSON Web Key Set parser.
- [Kalium](https://github.com/abstractj/kalium) - 绑定网络和密码（NaCl）库.
- [Keycloak](https://keycloak.jboss.org) - 用于浏览器应用程序和RESTful Web服务的集成SSO和IDM.
- [Keyczar](https://github.com/google/keyczar) - 易于使用，安全的加密框架，带有密钥版本.
- [Keywhiz](https://github.com/square/keywhiz) - 分发和管理秘密的系统.
- [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz) - 高级密码强度估计.
- [OACC](http://oaccframework.org) - 提供基于权限的授权服务.
- [pac4j](https://github.com/pac4j/pac4j) - 安全引擎.
- [PicketLink](http://picketlink.org) - 用于安全和身份管理的伞项目.
- [SecurityBuilder](https://github.com/tersesystems/securitybuilder) - 用于JCA和JSSE类的Fluent Builder API，尤其是X.509证书.
- [Themis](https://github.com/cossacklabs/themis)   - 多平台高级加密库提供易于使用的加密，用于保护敏感数据：具有前向保密的安全消息，安全数据存储（AES256GCM）;  适合构建端到端加密应用程序.
- [Tink](http://github.com/google/tink) - 为常见的加密任务提供简单且防误用的API.
- [Vault](https://www.vaultproject.io)   - 保护，存储和严格控制对令牌，密码，证书，API密钥和其他机密的访问.  它处理租赁，密钥撤销，密钥滚动和审计.  通过统一的API，用户可以访问加密的Key / Value存储和网络加密即服务，或生成AWS IAM / STS凭证，SQL / NoSQL数据库，X.509证书，SSH凭据等.

### Serialization

*高效处理序列化的库.*

- [FlatBuffers](https://github.com/google/flatbuffers) - 内存高效的序列化库，可以访问序列化数据而无需解压缩和解析.
- [FST](https://github.com/RuedigerMoeller/fast-serialization) -  JDK兼容的高性能对象图序列化.
- [Kryo](https://github.com/EsotericSoftware/kryo) - 快速有效的对象图序列化框架.
- [MessagePack](https://github.com/msgpack/msgpack-java) - 高效的二进制序列化格式.
- [PHP Serializer](https://github.com/marcospassos/java-php-serializer) - 以PHP序列化格式序列化对象.

### Server

*专门用于部署应用程序的服务器.*

- [Apache Tomcat](https://tomcat.apache.org) - 用于Servlet和JSP的强大，全面的服务器.
- [Apache TomEE](https://tomee.apache.org) -  Tomcat和Java EE.
- [Jetty](https://www.eclipse.org/jetty) - 提供Web服务器和javax.servlet容器，以及对HTTP / 2，WebSocket，OSGi，JMX，JNDI，JAAS和许多其他集成的支持.
- [nanohttpd](https://github.com/NanoHttpd/nanohttpd) - 小巧，易于嵌入的HTTP服务器.
- [WebSphere Liberty](https://developer.ibm.com/wasdev) - 由IBM开发的轻量级模块化服务器.
- [WildFly](http://www.wildfly.org) - 以前称为JBoss，由Red Hat开发，具有广泛的Java EE支持.

### Template Engine

*替换模板中表达式的工具.*

- [Handlebars.java](https://jknack.github.io/handlebars.java) - 无逻辑和语义的胡须模板.
- [Jade4J](https://github.com/neuland/jade4j) - 实施帕格（以前称为翡翠）.
- [Jtwig](http://jtwig.org) - 模块化，可配置且经过全面测试的模板引擎.
- [Pebble](http://www.mitchellbosecke.com/pebble/home)   - 受Twig的启发，并以其继承功能和易于阅读的语法分离.  它附带内置自动安全功能，用于安全性，并包含对国际化的集成支持.
- [Thymeleaf](http://www.thymeleaf.org) - 旨在成为JSP的替代品并适用于XML文件.

### Testing

*从模型到视图进行测试的工具.*

#### Asynchronous

*简化测试异步服务的工具.*

- [Awaitility](https://github.com/jayway/awaitility) - 用于同步异步操作的DSL.
- [ConcurrentUnit](https://github.com/jhalterman/concurrentunit) - 用于测试多线程和异步应用程序的工具包.
- [GreenMail](http://www.icegreen.com/greenmail)   - 用于集成测试的内存中电子邮件服务器.  支持SMTP，POP3和IMAP，包括SSL.
- [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java) -  Hoverfly的本机绑定，一种允许您模拟HTTP服务的代理.
- [REST Assured](https://github.com/jayway/rest-assured) - 用于轻松测试REST / HTTP服务的DSL.

#### BDD

*测试TDD出现的软件开发过程，受DDD和OOAD的影响很大.*

- [Cucumber](https://github.com/cucumber/cucumber-jvm) - 提供一种用简单语言描述功能的方法，客户可以理解.
- [Cukes-REST](https://github.com/ctco/cukes-rest) - 使用Cucumber进行REST服务测试的Gherkin步骤集合.
- [J8Spec](https://github.com/j8spec/j8spec) - 遵循类似Jasmine的语法.
- [JBehave](http://jbehave.org) - 广泛可配置的框架，用于描述故事.
- [JGiven](http://jgiven.org) - 提供流畅的API，允许更简单的组合.
- [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave) - 旨在提供一个流畅的API，用长而简洁的句子写出测试，读起来像普通的英语.

#### Fixtures

*与随机数据的创建和处理相关的一切.*

- [Beanmother](https://github.com/keepcosmos/beanmother) - 从YAML灯具设置bean.
- [Fixture Factory](https://github.com/six2six/fixture-factory) - 从模板生成假对象.
- [JFairy](https://github.com/Codearte/jfairy) - 假数据生成器.
- [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) -  JUnit测试运行器和用于以伪随机方式运行JUnit测试的插件.
- [Java Faker](https://github.com/DiUS/java-faker) -  Ruby的虚假数据生成器的端口.

#### Frameworks

*提供环境以运行特定用例的测试.*

- [ArchUnit](https://github.com/TNG/ArchUnit) - 用于指定和断言体系结构规则的测试库.
- [Apache JMeter](http://jmeter.apache.org) - 功能测试和性能测量.
- [Arquillian](http://arquillian.org) -  Java EE容器的集成和功能测试平台.
- [Citrus](https://citrusframework.org) - 集成测试框架，侧重于客户端和服务器端消息传递.
- [Gatling](https://gatling.io) - 负载测试工具，易于使用，可维护性和高性能.
- [JUnit](http://junit.org) - 通用测试框架.
- [Pact JVM](https://github.com/DiUS/pact-jvm) - 消费者驱动的合同测试.
- [PIT](http://pitest.org) - 快速变异测试框架，用于评估现有JUnit或TestNG测试套件的故障检测能力.

#### Matchers

*提供自定义匹配器的库.*

- [AssertJ](https://joel-costigliola.github.io/assertj) - Fluent assertions that improve readability.
- [JSONAssert](http://jsonassert.skyscreamer.org) - 简化测试JSON字符串.
- [Truth](https://github.com/google/truth) - 谷歌的断言和主张框架.

#### Miscellaneous

*与测试有关的其他内容.*

- [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector) - 报告给定类的实例是否是不可变的.
- [raml-tester](https://github.com/nidi3/raml-tester) - 测试请求/响应是否与给定的RAML定义匹配.
- [TestContainers](https://github.com/testcontainers/testcontainers-java) - 提供常用数据库，Selenium Web浏览器或可在Docker容器中运行的任何其他内容的一次性实例.
- [pojo-tester](http://www.pojo.pl) - 自动执行基本POJO方法的测试.

#### Mocking

*模拟合作者帮助测试单个隔离单元的工具.*

- [JMockit](http://jmockit.github.io) - 集成测试，API模拟和伪造以及代码覆盖.
- [Mockito](https://github.com/mockito/mockito) - 模拟框架，允许您使用简洁的API编写测试.
- [MockServer](https://www.mock-server.com) - 允许模拟与HTTPS集成的系统.
- [Moco](https://github.com/dreamhead/moco) - 存根和模拟的简洁Web服务.
- [PowerMock](https://github.com/jayway/powermock) - 模拟静态方法，构造函数，最终类和方法，私有方法以及静态初始化程序的删除.
- [WireMock](http://wiremock.org) - 存根和模拟Web服务.

#### Parameterization

*简化参数化测试的编写.*

- [Burst](https://github.com/square/burst) - 用于改变测试数据的单元测试库.
- [junit-dataprovider](https://github.com/TNG/junit-dataprovider) -  JUnit的类似TestNG的数据提供者/运行者.
- [JUnitParams](https://pragmatists.github.io/JUnitParams) - 创建可读和可维护的参数化测试.

### Utility

*提供一般实用功能的库.*

- [bucket4j](https://github.com/vladimir-bukhtoyarov/bucket4j) - Rate limiting library based on token-bucket algorithm.
- [cactoos](http://www.cactoos.org) - 面向对象原语的集合.
- [CRaSH](http://www.crashub.org)   - 为运行CRaSH的JVM提供shell.  由Spring Boot和其他人使用.
- [Dex](https://github.com/PatMartin/Dex) - 具有强大ETL和数据可视化功能的Java / JavaFX工具.
- [Embulk](http://www.embulk.org) - 批量数据加载器，可帮助在各种数据库，存储，文件格式和云服务之间进行数据传输.
- [fswatch](https://github.com/vorburger/ch.vorburger.fswatch) - 用于监视目录文件系统更改的微库，简化了java.nio.file.WatchService
- [Gephi](https://github.com/gephi/gephi) - 用于可视化和操纵大型图形网络的跨平台.
- [Guava](https://github.com/google/guava) - 集合，缓存，基元支持，并发库，通用注释，字符串处理，I / O等.
- [JADE](http://jade.tilab.com) - 用于构建和调试多代理系统的框架和环境.
- [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions) - 有助于构建困难的正则表达式的库.
- [JGit](https://eclipse.org/jgit) - 实现Git版本控制系统的轻量级纯Java库.
- [minio-java](https://github.com/minio/minio-java) - 提供简单的API以访问任何与Amazon S3兼容的对象存储服务器.
- [Protégé](https://protege.stanford.edu) - 提供本体编辑器和构建基于知识的系统的框架.
- [Underscore-java](https://github.com/javadev/underscore-java) -  Underscore.js函数的端口.

### Version Managers

*有助于创建开发shell环境并在不同Java版本之间切换的实用程序.*

- [jabba](https://github.com/shyiko/jabba) - Java Version Manager inspired by nvm. Supports Mac OS X, Linux and Windows.
- [jenv](https://github.com/gcuisinier/jenv)   - 受rbenv启发的Java Version Manager.  可以全局配置还是按项目配置.  在Debian和Mac OS X上测试过.
- [SDKMan](https://github.com/sdkman/sdkman-cli)   - 受RVM和rbenv启发的Java Version Manager.  支持基于UNIX的平台和Windows.

### Web Crawling


- [Apache Nutch](https://nutch.apache.org) - 适用于生产环境的高度可扩展，高度可扩展的Web爬虫.
- [Crawler4j](https://github.com/yasserg/crawler4j) - 简单轻便的网络爬虫.
- [jsoup](https://jsoup.org) -  Scrapes，解析，操作和清理HTML.
- [StormCrawler](http://stormcrawler.net) - 用于构建低延迟和可扩展的Web爬网程序的SDK.
- [webmagic](https://github.com/code4craft/webmagic) - 具有下载，URL管理，内容提取和持久性的可扩展爬虫.

### Web Frameworks

*处理Web应用程序各层之间通信的框架.*

- [Apache Tapestry](https://tapestry.apache.org) - 面向组件的框架，用于创建动态，健壮，高度可扩展的Web应用程序.
- [Apache Wicket](https://wicket.apache.org) - 类似于Tapestry的基于组件的Web应用程序框架，具有状态GUI.
- [Blade](https://github.com/biezhi/blade) - 轻巧，模块化的框架，旨在优雅和简单.
- [Bootique](http://bootique.io) - 可运行应用程序的最小观点框架.
- [Firefly](http://www.fireflysource.com) - 用于快速开发高性能Web应用程序的异步框架.
- [Grails](https://grails.org) -  Groovy框架，通过优于配置，不支持XML和支持mixin，提供高效的环境.
- [Jooby](http://jooby.org) - 可扩展，快速和模块化的微框架，提供多种编程模型.
- [Ninja](http://www.ninjaframework.org) - 全栈Web框架.
- [Pippo](http://www.pippo.ro) - 小型，高度模块化，类似Sinatra的框架.
- [Play](https://www.playframework.com) - 基于Akka，它为Java和Scala中的高度可伸缩应用程序提供可预测且最小的资源消耗（CPU，内存，线程）.
- [PrimeFaces](https://primefaces.org) - 具有免费和商业/支持版本以及前端组件的JSF框架.
- [Ratpack](https://ratpack.io) - 一组库，可以促进快速，高效，可演化和经过良好测试的HTTP应用程序.
- [Takes](https://github.com/yegor256/takes) - 基于真实面向对象编程和不变性概念构建的意见Web框架.
- [Vaadin Flow](https://vaadin.com/flow)   - 使用标准Web组件的事件驱动框架.  在客户端使用Ajax的服务器端架构.

## Resources

### Awesome Lists

*与Java和JVM生态系统相关的令人敬畏的列表.*

- [Awesome Gradle Plugins](https://github.com/ksoichiro/awesome-gradle)
- [AwesomeJavaFX](https://github.com/mhrimaz/AwesomeJavaFX)
- [Awesome JVM](https://github.com/deephacks/awesome-jvm)
- [Awesome Microservices](https://github.com/mfornos/awesome-microservices)
- [Awesome REST](https://github.com/marmelab/awesome-rest)
- [Awesome Selenium](https://github.com/christian-bromann/awesome-selenium)
- [ciandcd](https://github.com/ciandcd/awesome-ciandcd)
- [Useful Java Links](https://github.com/Vedenin/useful-java-links)

### Communities

*积极讨论.*

- [r/java](https://www.reddit.com/r/java) -  Java社区的Subreddit.
- [stackoverflow](https://stackoverflow.com/questions/tagged/java) - 问答平台.
- [VirtualJUG](https://virtualjug.com) - 虚拟Java用户组.

### Frontends

 *为此列表提供前端的网站.  请注意，不会有官方网站.  我们不与特定网站关联，每个人都可以创建一个.*

- [java.libhunt.com](https://java.libhunt.com)

### Influential Books

*产生重大影响但仍值得阅读的书籍.*

- [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
- [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
- [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
- [Thinking in Java](https://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

### Podcasts and Screencasts

*编程时要注意或听的东西.*

- [Java Off Heap](http://www.javaoffheap.com)
- [Marco Behler's Screencasts](https://www.marcobehler.com/series) - 关于现代Java开发的截屏视频.
- [The Java Council](https://virtualjug.com/#podcast)
- [The Java Posse](http://www.javaposse.com) - 自2015年2月起停产.

### Twitter

 *积极的帐户，以遵循.  来自Twitter的描述.*

- [Adam Bien](https://twitter.com/AdamBien) - 自由撰稿人，JavaOne Rockstar演讲者，顾问，Java Champion.
- [Aleksey Shipilëv](https://twitter.com/shipilev) - 性能极客，基准测试沙皇，并发bug猎人.
- [Antonio Goncalves](https://twitter.com/agoncal) -  Java Champion，JUG Leader，Devoxx France，Java EE 6/7，JCP，作者.
- [Arun Gupta](https://twitter.com/arungupta) -  Java Champion，JavaOne Rockstar，JUG Leader，Devoxx4Kids-er，Couchbase开发人员倡导副总裁.
- [Brian Goetz](https://twitter.com/BrianGoetz) -  Oracle的Java语言架构师.
- [Bruno Borges](https://twitter.com/brunoborges) -  Oracle的产品经理/ Java Jock.
- [Chris Richardson](https://twitter.com/crichardson) - 软件架构师，顾问和连续企业家，Java Champion，JavaOne Rock Star，* POJO in Action-作者.
- [Ed Burns](https://twitter.com/edburns) -  Oracle技术人员的咨询成员.
- [Eugen Paraschiv](https://twitter.com/baeldung) - 春季安全课程的作者.
- [Heinz Kabutz](https://twitter.com/heinzkabutz) -  Java Champion，演讲者，Java专家通讯的作者，并发性能专家.
- [Holly Cummins](https://twitter.com/holly_cummins) -  IBM London的Bluemix Garage，Java Champion，开发人员，作者，JavaOne rockstar的技术负责人.
- [James Weaver](https://twitter.com/JavaFXpert) -  Java / JavaFX / IoT开发人员，作者和演讲者.
- [Java EE](https://twitter.com/Java_EE) - 官方Java EE Twitter帐户.
- [Java Magazine](https://twitter.com/Oraclejavamag) -  Java Magazine官方帐号.
- [Java](https://twitter.com/java) - 官方Java Twitter帐户.
- [Javin Paul](https://twitter.com/javinpaul) - 着名的Java博主.
- [Josh Long](https://twitter.com/starbuxman) -  Pivotal的Spring Advocate，O&#39;Reilly的Cloud Native Java-和Spring Boot的构建微服务，JavaOne Rock Star的作者.
- [Lukas Eder](https://twitter.com/lukaseder) -  Java Champion，演讲嘉宾，JUG.ch联合领导人，创始人兼首席执行官Data Geekery（jOOQ）.
- [Mario Fusco](https://twitter.com/mariofusco) -  RedHatter，JUG协调员，经常发言人和作者.
- [Mark Heckler](https://twitter.com/MkHeck) -  Pivotal首席技术专家和开发者倡导者，会议发言人，出版作者和Java Champion，专注于物联网和云计算.
- [Mark Reinhold](https://twitter.com/mreinhold) -  Java平台组首席架构师，Oracle.
- [Markus Eisele](https://twitter.com/myfear) -  Java EE布道者，Red Hat.
- [Martijn Verburg](https://twitter.com/karianna) - 伦敦JUG联合领导人，演讲者，作家，Java冠军等等.
- [Martin Thompson](https://twitter.com/mjpt777) -  Pasty面对表演黑帮.
- [Monica Beckwith](https://twitter.com/mon_beck) - 性能顾问，JavaOne Rock Star.
- [OpenJDK](https://twitter.com/OpenJDK) -  OpenJDK官方账号.
- [Peter Lawrey](https://twitter.com/PeterLawrey) -  Java性能专家Peter Lawrey.
- [Randy Shoup](https://twitter.com/randyshoup) -  Stitch Fix VP工程，演讲者，JavaOne摇滚明星.
- [Reza Rahman](https://twitter.com/reza_rahman) -  Java EE / GlassFish / WebLogic布道者，作者，演讲者，开源黑客.
- [Simon Maple](https://twitter.com/sjmaple) -  Java Champion，VirtualJUG创始人，LJC领导者，RebelLabs作者.
- [Stephen Colebourne](https://twitter.com/jodastephen) -  Java冠军，演讲者.
- [Trisha Gee](https://twitter.com/trisha_gee) -  Java冠军和演讲者.
- [Venkat Subramaniam](https://twitter.com/venkat_s) - 作者，休斯顿大学教授，MicroSoft MVP奖获得者，JavaOne摇滚明星，Java冠军.

### Websites

*网站阅读.*

- [Baeldung](https://www.baeldung.com)
- [Dzone](https://dzone.com)
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

贡献非常欢迎！

请看看 [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) 准则.

[c]：https：//cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg
