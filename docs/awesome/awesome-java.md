<div class="github-widget" data-repo="akullpp/awesome-java"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Java [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

精选的Java框架，库和软件清单.



## Projects

### Bean Mapping

_简化bean映射的框架.

- [dOOv](https://github.com/doov-io/doov)  -提供用于类型安全域模型验证和映射的流畅API.  它使用注释，代码生成和类型安全的DSL来使bean验证和映射变得快速而容易.
- [Dozer](https://github.com/DozerMapper/dozer) -映射器，它使用注释和API或XML配置将数据从一个对象复制到另一个对象.
- [JMapper](https://github.com/jmapper-framework/jmapper-core)  -使用字节码操作实现闪电般的快速映射.  支持注释和API或XML配置.
- [MapStruct](https://github.com/mapstruct/mapstruct) -代码生成器，它基于配置约定惯例简化了不同bean类型之间的映射.
- [ModelMapper](https://github.com/modelmapper/modelmapper) -智能对象映射库，可自动将对象相互映射.
- [Orika](https://github.com/orika-mapper/orika) -JavaBean映射框架，将数据（除其他功能外）从一个对象递归复制到另一个对象.
- [reMap](https://github.com/remondis-it/remap) -基于Lambda和方法句柄的映射，如果对象具有不同的名称，则需要代码，而无需注释.
- [Selma](https://github.com/xebia-france/selma) -基于注释处理器的bean映射器.

### Build

_处理应用程序的构建周期和依赖关系的工具.

- [Apache Maven](https://maven.apache.org)  -声明式的构建和依赖项管理，它使约定优于配置.  它可能比Apache Ant更可取，后者使用一种相当程序性的方法并且可能难以维护.
- [Bazel](https://bazel.build) -Google提供的工具，可快速，可靠地构建代码.
- [Buck](https://github.com/facebook/buck) -鼓励创建由代码和资源组成的小型可重用模块.
- [Gradle](https://gradle.org)  -通过Groovy编程的增量构建，而不是声明XML.  与Maven的依赖项管理配合良好.

### Bytecode Manipulation

_库以编程方式操作字节码

- [ASM](https://asm.ow2.io) -通用的低级字节码操作和分析.
- [Byte Buddy](https://bytebuddy.net) -通过流利的API进一步简化了字节码的生成.
- [bytecode-viewer](https://github.com/Konloch/bytecode-viewer)  -Java 8 Jar和Android APK逆向工程套件.  （仅限GPL-3.0）
- [Byteman](https://byteman.jboss.org)  -在运行时通过DSL处理字节码（规则）；  主要用于测试/故障排除.  （LGPL-2.1或更高版本）
- [cglib](https://github.com/cglib/cglib) -字节码生成库.
- [Javassist](https://github.com/jboss-javassist/javassist) -尝试简化字节码编辑.
- [Mixin](https://github.com/SpongePowered/Mixin) -使用真实的Java代码在运行时处理字节码.
- [Perses](https://github.com/nicolasmanic/perses) -根据混沌工程原理，在字节码级别动态注入故障/延迟.

### Caching

_提供缓存功能的库.

- [cache2k](https://cache2k.org) -内存中高性能缓存库.
- [Caffeine](https://github.com/ben-manes/caffeine) -高性能，接近最佳的缓存库.
- [Ehcache](http://www.ehcache.org) -分布式通用缓存.
- [Infinispan](https://infinispan.org) -用于缓存的高度并发的键/值数据存储.

### CLI

_与CLI相关的所有库.

- [ASCII Table](https://github.com/vdmeer/asciitable) -以ASCII格式绘制表格的库.
- [Airline](https://github.com/airlift/airline) -基于注释的框架，用于解析类似Git的命令行参数.
- [args4j](http://args4j.kohsuke.org) -小型库，用于解析命令行参数.
- [Jansi](https://github.com/fusesource/jansi) -ANSI转义码，用于格式化控制台输出.
- [Java ASCII Render](https://github.com/indvd00m/java-ascii-render) -控制台的图形基元.
- [JCommander](http://jcommander.org) -具有自定义类型和通过实现接口进行验证的命令行参数解析框架.
- [jbock](https://github.com/h908714124/jbock) -类型安全，无反射，基于注释的命令行解析器.
- [Jexer](https://gitlab.com/klamonte/jexer)  -先进的控制台（和Swing）文本用户界面（TUI）库，带有可拖动鼠标的窗口，内置的终端窗口管理器和sixel图像支持.  好像 [Turbo Vision](https://en.wikipedia.org/wiki/Turbo_Vision).
- [JLine](https://github.com/jline/jline3) -包括来自现代炮弹的功能，例如完成或历史记录.
- [JOpt Simple](https://jopt-simple.github.io/jopt-simple/) - Fluent parser that uses the POSIX#getopt and GNU#getopt_long syntaxes.
- [picocli](https://picocli.info) -使用中的ANSI颜色和样式有助于基于注释的POSIX / GNU /任何语法，子命令，选项和位置参数的强类型化.
- [Text-IO](https://github.com/beryx/text-io) -帮助创建完整的基于控制台的应用程序.
- [Lanterna](https://github.com/mabe02/lanterna)  -简单的控制台文本GUI库，类似于curses.  （仅限LGPL-3.0）

### Cluster Management

_可以动态管理集群内部应用程序的框架.

- [Apache Aurora](https://aurora.apache.org) -用于长期服务和cron作业的Mesos框架.
- [Apache Mesos](https://mesos.apache.org) -从计算机上提取CPU，内存，存储和其他计算资源.
- [Singularity](http://getsingularity.com)  -使部署和操作变得容易的Mesos框架.  它支持Web服务，后台工作人员，计划的作业和一次性任务.

### Code Analysis

_提供指标和质量度量的工具._

- [Checkstyle](https://github.com/checkstyle/checkstyle)  -对编码约定和标准的静态分析.  （LGPL-2.1或更高版本）
- [Error Prone](https://github.com/google/error-prone) -将常见的编程错误捕获为编译时错误.
- [Infer](https://github.com/facebook/infer) -用于验证代码正确性的现代静态分析工具.
- [jQAssistant](https://jqassistant.org)  -使用基于Neo4J的查询语言进行静态代码分析.  （仅限GPL-3.0）
- [NullAway](https://github.com/uber/NullAway) -以较低的构建时间开销消除了NullPointerExceptions.
- [PMD](https://github.com/pmd/pmd) -查找不良编码实践的源代码分析.
- [SonarJava](https://github.com/SonarSource/sonar-java)  -SonarQube和SonarLint的静态分析仪.  （仅限LGPL-3.0）
- [Sourcetrail](https://www.sourcetrail.com) -可视化源代码导航器.
- [Spoon](https://github.com/INRIA/spoon) -用于分析和转换Java源代码的库.
- [Spotbugs](https://github.com/spotbugs/spotbugs)  -字节码的静态分析以查找潜在的错误.  （仅限LGPL-2.1）

### Code Coverage

_可为测试套件启用代码覆盖率度量标准的框架和工具._

- [Clover](https://www.atlassian.com/software/clover) -依靠源代码检测而不是字节码检测.
- [Cobertura](https://cobertura.github.io/cobertura/)  -依靠离线（或静态）字节码检测和类加载来收集代码覆盖率指标.  （仅限GPL-2.0）
- [JaCoCo](https://www.eclemma.org/jacoco/) -使用脱机和运行时字节码检测工具能够收集代码覆盖率度量的框架.

### Code Generators

_为重复代码生成模式以减少冗长和易于出错的工具.

- [ADT4J](https://github.com/sviperll/adt4j) -用于代数数据类型的JSR-269代码生成器.
- [Auto](https://github.com/google/auto) -生成工厂，服务和价值类.
- [FreeBuilder](https://github.com/inferred/FreeBuilder) -自动生成Builder模式.
- [Immutables](https://immutables.github.io) -注释处理器生成简单，安全和一致的值对象.
- [JavaPoet](https://github.com/square/javapoet) -生成源文件的API.
- [JHipster](https://github.com/jhipster/generator-jhipster) -Spring Boot和AngularJS的Yeoman源代码生成器.
- [Joda-Beans](https://www.joda.org/joda-beans/) -小型框架，可向Java添加可查询的属性，从而增强了JavaBeans.
- [Lombok](https://projectlombok.org) -旨在减少冗长程度的代码生成器.

### Compiler-compiler

_有助于创建解析器，解释器或编译器的框架.

- [ANTLR](https://www.antlr.org) -用于自上而下解析的复杂的全功能框架.
- [JavaCC](https://javacc.github.io/javacc/)  -解析器生成器，用于生成自上而下的解析器.  允许进行词法状态切换，并允许扩展BNF规范.
- [JFlex](https://jflex.de) -词法分析器生成器.

### Configuration

_提供外部配置的库.

- [centraldogma](https://github.com/line/centraldogma) -基于Git，ZooKeeper和HTTP / 2的高可用性版本控制服务配置存储库.
- [cfg4j](https://github.com/cfg4j/cfg4j) -用于用Java编写的分布式应用程序的现代配置库.
- [config](https://github.com/lightbend/config) -JVM语言的配置库.
- [dotenv](https://github.com/shyiko/dotenv) -十二因子配置库，使用特定于环境的文件.
- [ini4j](http://ini4j.sourceforge.net) -提供用于处理Windows的INI文件的API.
- [KAConf](https://github.com/mariomac/kaconf) -用于Java和Kotlin的基于注释的配置系统.
- [owner](https://github.com/lviggiano/owner) -减少属性的样板.

### Constraint Satisfaction Problem Solver

_有助于实现优化和可满足性问题的库.

- [Choco](https://choco-solver.org) -使用约束编程技术的现成的约束满足问题解决程序.
- [JaCoP](https://github.com/radsz/jacop)  -包括FlatZinc语言的界面，使其能够执行MiniZinc模型.  （AGPL-3.0）
- [OptaPlanner](https://www.optaplanner.org) -业务计划和资源调度优化求解器.

### CSV

_简化了读写CSV数据的框架和库.

- [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv) -用于读取和写入CSV的Jackson扩展.
- [opencsv](http://opencsv.sourceforge.net) -简单的CSV解析器.
- [Super CSV](https://super-csv.github.io/super-csv/) -强大的CSV解析器，支持Dozer，Joda-Time和Java 8.
- [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers)  -最快，功能最齐全的解析器之一.  还带有用于TSV和固定宽度记录的解析器.

### Data Structures

_高效而具体的数据结构.

- [Apache Avro](https://avro.apache.org) -具有动态类型输入，无标签数据和缺少手动分配ID的数据交换格式.
- [Apache Orc](https://orc.apache.org) -快速，高效的列式存储格式，用于基于Hadoop的工作负载.
- [Apache Parquet](https://parquet.apache.org) -基于Google关于Dremel的论文中的汇编算法的列式存储格式.
- [Apache Thrift](https://thrift.apache.org) -源自Facebook的数据交换格式.
- [Big Queue](https://github.com/bulldog2011/bigqueue) -基于内存映射文件的快速持久队列.
- [HyperMinHash-java](https://github.com/LiveRamp/HyperMinHash-java) -用于计算对数日志空间中的联合，交集和集合基数的概率数据结构.
- [Persistent Collection](https://github.com/hrldcpr/pcollections) -Java Collections Framework的持久且不变的类似物.
- [Protobuf](https://github.com/protocolbuffers/protobuf) -Google的数据交换格式.
- [SBE](https://github.com/real-logic/simple-binary-encoding) -简单的二进制编码，这是最快的消息格式之一.
- [Tape](https://github.com/square/tape) -闪电般的，基于事务的，基于文件的FIFO.
- [Wire](https://github.com/square/wire) -干净，轻便的协议缓冲区.

### Database

_简化与数据库交互的所有内容._

- [Apache Drill](https://drill.apache.org) -用于大数据探索的分布式，架构动态的ANSI SQL查询引擎.
- [Apache Phoenix](https://phoenix.apache.org) -HBase上的高性能关系数据库层，用于低延迟应用程序.
- [AranoDB](https://github.com/arangodb/arangodb-java-driver) -ArangoDB Java驱动程序.
- [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map) -高效的内存中（优化选项持久存储到磁盘），堆外键值存储.
- [druid](https://druid.apache.org) -高性能，面向列的分布式数据存储.
- [eXist](https://github.com/eXist-db/exist)  -NoSQL文档数据库和应用程序平台.  （仅限LGPL-2.1）
- [FlexyPool](https://github.com/vladmihalcea/flexy-pool) -将指标和故障转移策略带入最常见的连接池解决方案.
- [Flyway](https://flywaydb.org) -简单的数据库迁移工具.
- [H2](https://h2database.com) -小型SQL数据库以其内存功能而著称.
- [HikariCP](https://github.com/brettwooldridge/HikariCP) -高性能JDBC连接池.
- [jasync-sql](https://github.com/jasync-sql/jasync-sql) -适用于MySQL和PostgreSQL的异步DB驱动程序.
- [JDBI](http://jdbi.org) - Convenient abstraction of JDBC.
- [Jedis](https://github.com/xetorthio/jedis) -用于与Redis交互的小型客户端，带有命令方法.
- [Jest](https://github.com/searchbox-io/Jest) -Elasticsearch REST API的客户端.
- [jetcd](https://github.com/justinsb/jetcd) -etcd的客户端库.
- [Jinq](https://github.com/my2iu/Jinq) -通过Java 8 Lambda的符号执行（在JPA或jOOQ之上）进行类型安全的数据库查询.
- [jOOQ](https://www.jooq.org) -根据SQL模式生成类型安全代码.
- [Leaf](https://github.com/Meituan-Dianping/Leaf) -分布式ID生成服务.
- [Liquibase](http://www.liquibase.org) -独立于数据库的库，用于跟踪，管理和应用数据库架构更改.
- [MapDB](http://www.mapdb.org) - Embedded database engine that provides concurrent collections backed on disk or in off-heap memory.
- [MariaDB4j](https://github.com/vorburger/MariaDB4j) -适用于MariaDB的启动器，无需安装或外部依赖项.
- [Presto](https://prestosql.io) -用于大数据的分布式SQL查询引擎.
- [Querydsl](http://www.querydsl.com) -Typesafe统一查询.
- [Realm](https://github.com/realm/realm-java) -移动数据库可直接在手机，平板电脑或可穿戴设备中运行.
- [Redisson](https://github.com/redisson/redisson) -允许在Redis服务器之上提供分布式和可伸缩的数据结构.
- [requery](https://github.com/requery/requery)  -现代，轻便但功能强大的对象映射和SQL生成器.  轻松映射到数据库或创建数据库，或从任何使用Java的平台执行查询和更新.
- [Speedment](https://github.com/speedment/speedment) -利用Java 8的Stream API进行查询的数据库访问库.
- [sql2o](https://www.sql2o.org) -瘦JDBC包装器，可简化数据库访问并提供ResultSets到POJO的简单映射.
- [Vibur DBCP](https://www.vibur.org) -具有高级性能监视功能的JDBC连接池库.
- [Xodus](https://jetbrains.github.io/xodus/) -高度并发的无事务模式且符合ACID的嵌入式数据库.

### Date and Time

_与处理日期和时间有关的库.

- [Almanac Converter](https://github.com/chrisengelsma/almanac-converter) -不同日历系统之间的简单转换.
- [iCal4j](https://github.com/ical4j/ical4j) -解析并建立iCalendar [RFC 5545](https://tools.ietf.org/html/rfc5545) 数据模型.
- [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra) -补充JDK 8中的日期时间类的其他日期时间类.
- [Time4J](https://github.com/MenoData/Time4J)  -高级日期和时间库.  （仅限LGPL-2.1）

### Dependency Injection

_有助于实现 [Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) 范例._

- [Apache DeltaSpike](https://deltaspike.apache.org) -CDI扩展框架.
- [Dagger](https://dagger.dev/) -编译时注入框架，无需反思.
- [Feather](https://github.com/zsoltherpai/feather) -符合JSR-330的超轻量级依赖注入库.
- [Governator](https://github.com/Netflix/governator) -扩展了Google Guice的扩展程序和实用程序.
- [Guice](https://github.com/google/guice) -轻巧而自以为是的框架，完善了Dagger.
- [HK2](https://javaee.github.io/hk2/) -轻量级和动态依赖注入框架.
- [JayWire](https://github.com/vanillasource/jaywire)  -轻量级依赖注入框架.  （仅限LGPL-3.0）

### Development

_从根本上增强开发过程.

- [AspectJ](https://www.eclipse.org/aspectj/) -无缝的面向方面的编程扩展.
- [DCEVM](https://dcevm.github.io)  -JVM修改，允许在运行时无限制地重新定义已加载的类.  （仅限GPL-2.0）
- [Faux Pas](https://github.com/zalando/faux-pas) -通过避开默认情况下不允许Java运行时中的任何功能接口引发已检查异常的问题来简化错误处理的库.
- [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent)  -无限的运行时类和资源重新定义.  （仅限GPL-2.0）
- [JavaParser](https://github.com/javaparser/javaparser) -解析，修改和生成Java代码.
- [JavaSymbolSolver](https://github.com/javaparser/javasymbolsolver) -符号求解器.
- [Manifold](https://github.com/manifold-systems/manifold) -通过强大的功能（如类型安全的元编程，结构化类型化和扩展方法）重新激发Java的活力.
- [NoException](https://noexception.machinezoo.com) -允许在功能接口中检查异常并将异常转换为可选返回.
- [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow)  -无需字节码操作即可忽略检查的异常.  也可以在Java 8流操作中使用.

### Distributed Applications

_用于编写分布式和容错应用程序的库和框架.

- [Apache Geode](https://geode.apache.org) -内存数据管理系统，可提供可靠的异步事件通知和有保证的消息传递.
- [Apache Storm](https://storm.apache.org) -实时计算系统.
- [Apache ZooKeeper](https://zookeeper.apache.org) -具有用于大型分布式系统的分布式配置，同步和命名注册表的协调服务.
- [Atomix](https://atomix.io) -容错的分布式协调框架.
- [Axon](https://axoniq.io) -用于创建CQRS应用程序的框架.
- [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker)  -Dropwizard的断路器设计模式.  （仅限GPL-2.0）
- [Failsafe](https://github.com/jhalterman/failsafe) -通过重试和断路器进行简单的故障处理.
- [Hazelcast](https://hazelcast.org/) -带有免费开源版本的高度可扩展的内存数据网格.
- [JGroups](http://www.jgroups.org) -用于可靠消息传递和集群创建的工具包.
- [Orbit](http://www.orbit.cloud)  -虚拟演员；  为传统参与者增加了另一个层次的抽象.
- [Quasar](http://docs.paralleluniverse.co/quasar/) -JVM的轻量级线程和参与者.
- [resilience4j](https://github.com/resilience4j/resilience4j) -功能容错库.
- [ScaleCube Services](https://github.com/scalecube/scalecube-services) -基于SWIM和八卦协议的可嵌入集群成员库.
- [Zuul](https://github.com/Netflix/zuul) -网关服务，提供动态路由，监视，弹性，安全性等.

### Distributed Transactions

_分布式事务提供了一种机制，用于确保在存在并发访问和部分故障的情况下数据更新的一致性.

- [Atomikos](https://www.atomikos.com) -提供对REST，SOA和微服务的事务，并支持JTA和XA.
- [Bitronix](https://github.com/bitronix/btm) -JTA 1.1 API的简单但完整的实现.
- [Narayana](https://narayana.io)  -提供对传统ACID和补偿交易的支持，还符合JTA，JTS和其他标准.  （仅限LGPL-2.1）
- [Seata](https://seata.io) -在微服务架构下提供高性能且易于使用的分布式事务服务.

### Distribution

_以本机格式处理应用程序分发的工具._

-[Boxfuse！[c]]（https://boxfuse.com）-使用不可变基础结构原理将JVM应用程序部署到AWS.
- [Capsule](https://github.com/puniverse/capsule)  -简单而强大的打包和部署.  类固醇上的胖JAR，或支持JVM优化的容器的“ Java Docker”.
- [Central Repository](https://search.maven.org)  -最大的二进制组件存储库，可作为开源社区的免费服务.  Apache Maven使用的默认值，并且在所有其他构建工具中可用.
- [IzPack](http://izpack.org) -用于跨平台部署的安装创作工具.
- [jlink.online](https://github.com/cilki/jlink.online) -通过HTTP构建优化的运行时.
-[Nexus！[c]]（https://www.sonatype.com）-具有代理和缓存功能的二进制管理.
- [packr](https://github.com/libgdx/packr) -打包JAR，资产和JVM，以便在Windows，Linux和macOS上进行本机分发.
- [really-executable-jars-maven-plugin](https://github.com/brianm/really-executable-jars-maven-plugin) -用于制作自动执行的JAR的Maven插件.

### Document Processing

_协助处理Office文档格式的库.

- [Apache POI](https://poi.apache.org) -支持OOXML（XLSX，DOCX，PPTX）以及OLE2（XLS，DOC或PPT）.
- [documents4j](https://documents4j.com/#/) -使用第三方转换器（例如MS Word）进行文档格式转换的API.
- [docx4j](https://www.docx4java.org/trac/docx4j) -创建和操作Microsoft Open XML文件.
- [zerocell](https://github.com/creditdatamw/zerocell) -基于注释的API，用于将数据从Excel工作表读取到POJO中，以减少开销为重点.

### Financial

_与金融领域有关的图书馆._

- [Parity](https://github.com/paritytrading/parity) -交易场所的平台.
- [Philadelphia](https://github.com/paritytrading/philadelphia) -低延迟财务信息交换.
- [Square](https://github.com/square/connect-java-sdk) -与Square API集成.
- [Stripe](https://github.com/stripe/stripe-java) -与Stripe API集成.

### Formal Verification

_正式方法工具：证明助手，模型检查，符号执行等_

- [CATG](https://github.com/ksen007/janala2)  -Concolic单元测试引擎.  使用形式化方法自动生成单元测试.
- [Checker Framework](https://checkerframework.org)  -可插拔式系统.  包括无效类型，物理单位，不变性类型等.  （仅限GPL-2.0，带Classpath-exception-2.0）
- [Daikon](https://plse.cs.washington.edu/daikon/) -检测可能的程序不变式，并根据这些不变式生成JML规范.
- [Java Path Finder (JPF)](https://github.com/javapathfinder/jpf-core)  -JVM正式验证工具，其中包含模型检查器等.  由NASA创建.
- [JMLOK 2.0](https://massoni.computacao.ufcg.edu.br/home/jmlok)  -通过反馈定向的随机测试生成来检测代码与JML规范之间的不一致，并为每个检测到的不一致提出可能的原因.  （仅限GPL-3.0）
- [KeY](https://www.key-project.org)  -正式的软件开发工具，旨在尽可能无缝地集成面向对象软件的设计，实现，形式规范和形式验证.  使用JML进行规范，使用符号执行进行验证.  （GPL-2.0或更高版本）
- [OpenJML](http://www.openjml.org)  -将JML规范转换为SMT-LIB格式，并将程序隐含的证明问题传递给后端求解器.  （仅限GPL-2.0）

### Functional Programming

_促进函数式编程的库.

- [cyclops-react](https://github.com/aol/cyclops-react) -Monad和流实用程序，理解力，模式匹配，所有JDK集合的功能扩展，未来的流，蹦床等.
- [derive4j](https://github.com/derive4j/derive4j)  -Java 8注释处理器和框架，用于导出代数数据类型的构造函数，模式匹配和态射.  （仅限GPL-3.0）
- [Fugue](https://bitbucket.org/atlassian/fugue) -番石榴的功能扩展.
- [Functional Java](http://www.functionaljava.org) -实现许多基本和高级编程抽象，以协助面向合成的开发.
- [jOOλ](https://github.com/jOOQ/jOOL) -对Java 8的扩展，旨在通过提供许多缺失的类型和一组丰富的顺序Stream API添加来弥补lambda中的空白.
- [protonpack](https://github.com/poetix/protonpack) -流实用程序的集合.
- [StreamEx](https://github.com/amaembo/streamex) -增强了Java 8流.
- [Vavr](http://www.vavr.io) -提供持久数据类型和功能控制结构的功能组件库.

### Game Development

_支持游戏开发的框架._

- [FXGL](https://almasb.github.io/FXGL) -JavaFX游戏开发框架.
- [jMonkeyEngine](http://jmonkeyengine.org) -用于现代3D开发的游戏引擎.
- [libGDX](https://libgdx.badlogicgames.com) -全方位的跨平台高级框架.
- [LWJGL](https://www.lwjgl.org) -健壮的框架，可提取OpenGL / CL / AL等库.

### Geospatial

_用于处理地理空间数据和算法的库.

- [Apache SIS](https://sis.apache.org) -用于开发地理空间应用程序的库.
- [Geo](https://github.com/davidmoten/geo) -Java中的GeoHash实用程序.
- [Geotoolkit.org](http://www.geotoolkit.org)  -用于开发地理空间应用程序的库.  建立在Apache SIS项目之上.  （仅限LGPL-2.1）
- [GeoTools](https://geotools.org)  -提供地理空间数据工具的库.  （仅限LGPL-2.1）
- [GraphHopper](https://github.com/graphhopper/graphhopper)  -道路路由引擎.  用作Java库或独立的Web服务.
- [H2GIS](http://www.h2gis.org)  -H2数据库的空间扩展.  （仅限LGPL-3.0）
- [Jgeohash](https://astrapi69.github.io/jgeohash) -使用GeoHash算法的库.
- [Mapsforge](https://github.com/mapsforge/mapsforge)  -基于OpenStreetMap数据的地图渲染.  （仅限LGPL-3.0）
- [Spatial4j](https://github.com/locationtech/spatial4j) -通用空间/地理空间库.

### GUI

_创建现代图形用户界面的库.

- [JavaFX](https://wiki.openjdk.java.net/display/OpenJFX/Main) -Swing的后继者.
- [Scene Builder](https://gluonhq.com/open-source/scene-builder) -JavaFX应用程序的可视布局工具.
- [SWT](https://www.eclipse.org/swt) -图形小部件工具包.

### High Performance

_有关从集合到特定库的高性能计算的所有内容.

- [Agrona](https://github.com/real-logic/Agrona) -高性能应用程序中常见的数据结构和实用程序方法.
- [Disruptor](https://lmax-exchange.github.io/disruptor) -线程间消息传递库.
- [Eclipse Collections](https://github.com/eclipse/eclipse-collections) -受Smalltalk启发的收藏框架.
- [fastutil](http://fastutil.di.unimi.it) -快速而紧凑的类型专用集合.
- [HPPC](https://labs.carrotsearch.com/hppc.html) -原始集合.
- [JCTools](https://github.com/JCTools/JCTools) -JDK当前缺少并发工具.
- [Koloboke](https://koloboke.com) -哈希集和哈希图.

### HTTP Clients

_协助创建HTTP请求和/或绑定响应的库.

- [Async Http Client](https://github.com/AsyncHttpClient/async-http-client) -异步HTTP和WebSocket客户端库.
- [Feign](https://github.com/Netflix/feign) -受Retrofit，JAXRS-2.0和WebSocket启发的HTTP客户端绑定程序.
- [OkHttp](https://square.github.io/okhttp) -HTTP和SPDY客户端.
- [Play WS](https://github.com/playframework/play-ws) -具有反应式流和缓存的Typesafe客户端.
- [restQL-core-java](https://github.com/B2W-BIT/restQL-java) -微服务查询语言，可从多个服务中获取信息.
- [Retrofit](https://square.github.io/retrofit) -Typesafe REST客户端.
- [Ribbon](https://github.com/Netflix/ribbon) -在云中经过实战测试的客户端IPC库.
- [Riptide](https://github.com/zalando/riptide) -Spring的RestTemplate的客户端响应路由.
- [unirest-java](https://github.com/Kong/unirest-java) -简化的轻量级HTTP客户端库.

### Hypermedia Types

_处理到超媒体类型的序列化的库.

- [JSON-LD](https://github.com/jsonld-java/jsonld-java) -JSON-LD实现.
- [Siren4J](https://github.com/eserating/siren4j) -警笛规范库.

### IDE

_试图简化开发多个方面的集成开发环境.

- [Eclipse](https://www.eclipse.org) -建立了支持许多插件和语言的开源项目.
 -[IntelliJ IDEA！[c]]（https://www.jetbrains.com/idea）-支持许多JVM语言，并为Android开发提供了不错的选择.  商业版针对企业部门.
- [jGRASP](https://www.jgrasp.org) -创建用于提供与调试器结合使用的软件可视化效果，例如控件结构图，UML类图和对象查看器.
- [NetBeans](https://netbeans.apache.org) -提供从数据库访问到HTML5的多个Java SE和EE功能的集成.
- [Visual Studio Code](https://code.visualstudio.com/docs/languages/java) -通过使用内部市场的扩展，以简单，现代的工作流程为轻量项目提供Java支持.

### Imagery

_协助创建，评估或处理图形图像的库.

- [Imgscalr](https://github.com/thebuzzmedia/imgscalr) -以纯Java 2D实现的简单，高效且硬件加速的图像缩放库.
- [Tess4J](https://github.com/nguyenq/tess4j) -Tesseract OCR API的JNA包装器.
- [Thumbnailator](https://github.com/coobird/thumbnailator) -高质量的缩略图生成库.
- [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys) -扩展了支持的图像文件格式数量的插件集合.
- [ZXing](https://github.com/zxing/zxing) -多格式1D / 2D条码图像处理库.
- [image-comparison](https://github.com/romankh3/image-comparison) -比较两个大小相同的图像，并通过绘制矩形直观地显示差异.

### Introspection

_帮助简化和更快使用Java自省和反射API的库.

- [ClassGraph](https://github.com/classgraph/classgraph) -ClassGraph（以前称为FastClasspathScanner）是适用于Java，Scala，Kotlin和其他JVM语言的超快速，超轻量，并行化的类路径扫描器和模块扫描器.
- [jOOR](https://github.com/jOOQ/jOOR)  -jOOR代表面向对象的反射.  它是java.lang.reflect包的简单包装.
- [Mirror](http://projetos.vidageek.net/mirror/mirror) -创建Mirror是为了解决一个简单的问题，通常称为ReflectionUtil，该问题几乎在所有依赖反射来执行高级任务的项目上.
- [Objenesis](http://objenesis.org) -允许没有默认构造函数的动态实例化，例如，具有必需参数，副作用或抛出异常的构造函数.
- [ReflectASM](https://github.com/EsotericSoftware/reflectasm) -ReflectASM是一个非常小的Java库，它通过使用代码生成提供高性能的反射.
- [Reflections](https://github.com/ronmamo/reflections) -Reflections扫描您的类路径，为元数据建立索引，使您可以在运行时对其进行查询，并可以保存和收集项目中许多模块的信息.

### Job Scheduling

_用于调度后台作业的库.

- [Quartz](https://github.com/quartz-scheduler/quartz) -功能丰富的开源作业调度库，几乎可以集成在任何Java应用程序中.
- [Sundial](https://github.com/knowm/Sundial) -轻型框架，可以简单地定义作业，定义触发器和启动调度程序.
- [Wisp](https://github.com/Coreoz/Wisp) -具有最少资源占用和简单API的简单库.
- [db-scheduler](https://github.com/kagkarlsson/db-scheduler) -持久且群集友好的调度程序.

### JSON

_用于在Java对象之间进行JSON序列化和反序列化的库.

- [DSL-JSON](https://github.com/ngs-doo/dsl-json) -具有高级编译时数据绑定的JSON库.
- [Genson](https://owlike.github.io/genson) -强大且易于使用的Java到JSON转换库.
- [Gson](https://github.com/google/gson)  -将对象序列化为JSON，反之亦然.  即时使用性能良好.
- [HikariJSON](https://github.com/brettwooldridge/HikariJSON) -高性能JSON解析器，比Jackson快2倍.
- [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8) -用于Java 8数据类型和功能的Jackson模块集.
- [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money) -开源Jackson模块，支持JSON序列化和JavaMoney数据类型的反序列化.
- [Jackson](https://github.com/FasterXML/jackson) -与GSON相似，但是如果您需要更频繁地实例化库，则可以提高性能.
- [JSON-io](https://github.com/jdereg/json-io)  -将Java转换为JSON.  将JSON转换为Java.  漂亮的打印JSON.  Java JSON序列化器.
- [jsoniter](http://jsoniter.com) -具有迭代器和惰性分析API的快速灵活的库.
- [LoganSquare](https://github.com/bluelinelabs/LoganSquare)  -基于Jackson的流API的JSON解析和序列化库.  优于GSON和Jackson的资料库.
- [Moshi](https://github.com/square/moshi) -现代化的JSON库，不那么固执己见，并使用内置类型（如List和Map）.
- [Yasson](https://github.com/eclipse/yasson) -类和JSON文档之间的绑定层类似于JAXB.
- [fastjson](https://github.com/alibaba/fastjson) -非常快速的处理器，没有其他依赖项和完整的数据绑定.
- [Jolt](https://github.com/bazaarvoice/jolt) -JSON到JSON转换工具.
- [JsonPath](https://github.com/jayway/JsonPath) -使用类似XPATH的语法从JSON提取数据.
- [JsonSurfer](https://github.com/jsurfer/JsonSurfer) -专用于处理大型和复杂的JSON数据的流JsonPath处理器.

### JVM and JDK

_JVM / JDK的当前实现.

- [Adopt Open JDK](https://adoptopenjdk.net) -社区驱动的OpenJDK构建，包括HotSpot和OpenJ9.
- [Avian](https://github.com/ReadyTalk/avian) -具有JIT，AOT模式和iOS端口的JVM.
- [Corretto](https://aws.amazon.com/corretto)  -亚马逊提供的免费，多平台，生产就绪的OpenJDK发行.  （仅限GPL-2.0，带Classpath-exception-2.0）
- [Graal](https://github.com/oracle/graal)  -Polyglot嵌入式JVM.  （仅限GPL-2.0，带Classpath-exception-2.0）
- [Liberica JDK](https://www.bell-sw.com/java.html)  -由OpenJDK构建，经过全面测试并通过了JCK.  （仅限GPL-2.0，带Classpath-exception-2.0）
- [OpenJ9](https://github.com/eclipse/openj9) -高性能，企业级，灵活许可，开放式跨平台JVM，可扩展和增强Eclipse OMR和OpenJDK项目中的运行时技术组件.
- [Open JDK](https://openjdk.java.net)  -打开JDK社区主页.  （仅限GPL-2.0，带Classpath-exception-2.0）
- [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm)  -具有无阻塞并发GC（适用于iOS）的VM.  （仅限GPL-2.0，带Classpath-exception-2.0）
- [RedHat Open JDK](https://developers.redhat.com/products/openjdk/overview)  -RedHat的OpenJDK发行版.  （仅限GPL-2.0，带Classpath-exception-2.0）
- [SAP Machine](https://sap.github.io/SapMachine)  -SAP的免费，经过严格测试和JCK验证的OpenJDK友好fork.  （仅限GPL-2.0，带Classpath-exception-2.0）
- [Zulu](https://www.azul.com/downloads/zulu)  -OpenJDK为Windows，Linux和macOS构建.  （仅限GPL-2.0，带Classpath-exception-2.0）

### Logging

_记录应用程序行为的库.

- [Apache Log4j 2](https://logging.apache.org/log4j) -使用功能强大的插件和配置架构完全重写.
- [Graylog](https://www.graylog.org)  -适用于扩展角色和权限管理的开源聚合器.  （仅限GPL-3.0）
- [Kibana](https://www.elastic.co/products/kibana)  -分析和可视化日志文件.  某些功能需要付费.
- [Logback](https://logback.qos.ch) -健壮的日志库，通过Groovy具有有趣的配置选项.
- [Logbook](https://github.com/zalando/logbook) -可扩展的开放源代码库，用于HTTP请求和响应日志记录.
- [Logstash](https://www.elastic.co/products/logstash) -用于管理日志文件的工具.
- [p6spy](https://github.com/p6spy/p6spy) -启用所有JDBC事务的日志记录，而无需更改代码.
- [SLF4J](http://www.slf4j.org) -抽象层/简单的日志外观.
- [tinylog](http://www.tinylog.org) -具有静态记录器类的轻量级记录框架.
- [Tracer](https://github.com/zalando/tracer) -分布式系统中的呼叫跟踪和日志关联.

### Machine Learning

_提供用于从数据中学习的特定统计算法的工具._

- [Apache Flink](https://flink.apache.org) -快速，可靠的大规模数据处理引擎.
- [Apache Mahout](https://mahout.apache.org) - Scalable algorithms focused on collaborative filtering, clustering and classification.
- [Apache Spark](https://spark.apache.org) -数据分析集群计算框架.
- [DatumBox](http://www.datumbox.com) -提供几种用于自然语言处理的算法和预先训练的模型.
- [DeepDive](http://deepdive.stanford.edu) -从非结构化数据创建结构化信息，并将其集成到现有数据库中.
- [Deeplearning4j](https://deeplearning4j.org) - Distributed and multi-threaded deep learning library.
- [H2O](https://www.h2o.ai) -用于大数据统计的分析引擎.
- [JSAT](https://github.com/EdwardRaff/JSAT)  -用于预处理，分类，回归和聚类的算法，支持多线程执行.  （仅限GPL-3.0）
- [Oryx 2](https://github.com/OryxProject/oryx)  -用于构建实时，大规模机器学习应用程序的框架.  包括用于协同过滤，分类，回归和集群化的端到端应用程序.
- [Smile](https://github.com/haifengl/smile) -统计机器智能和学习引擎提供了一组机器学习算法和可视化库.
- [Synapses](https://mrdimosthenis.github.io/Synapses) -用于神经网络的轻量级库.
- [Weka](https://www.cs.waikato.ac.nz/ml/weka)  -收集用于从预处理到可视化的数据挖掘任务的算法.  （仅限GPL-3.0）

### Messaging

_帮助客户端之间发送消息以确保协议独立性的工具._

- [Aeron](https://github.com/real-logic/Aeron) -高效，可靠的单播和多播消息传输.
- [Apache ActiveMQ](https://activemq.apache.org) -实现JMS并将同步转换为异步通信的消息代理.
- [Apache Camel](https://camel.apache.org) -通过企业集成模式将不同的传输API粘合在一起.
- [Apache Kafka](https://kafka.apache.org) -高吞吐量的分布式消息传递系统.
- [Apache Pulsar](https://pulsar.apache.org) -分布式发布/子消息系统.
- [Apache RocketMQ](https://rocketmq.apache.org) -快速，可靠和可扩展的分布式消息传递平台.
- [Apache Qpid](https://qpid.apache.org) -Apache Qpid开发了使用AMQP并支持多种语言和平台的消息传递工具.
- [EventBus](https://github.com/greenrobot/EventBus) -简单的发布/订阅事件总线.
- [Hermes](http://hermes.allegro.tech) -建立在Kafka之上的快速可靠的消息代理.
- [JeroMQ](https://github.com/zeromq/jeromq) -实施ZeroMQ.
- [Nakadi](https://github.com/zalando/nakadi) -在Kafka之上提供RESTful API.
- [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client) -RabbitMQ客户端.
- [Smack](https://github.com/igniterealtime/Smack) - Cross-platform XMPP client library.
- [NATS client](https://github.com/nats-io/java-nats) -NATS客户.

### Microservice

_用于创建和管理微服务的工具.

- [Apollo](https://spotify.github.io/apollo) -用于编写可组合微服务的库.
- [Armeria](https://github.com/line/armeria) -基于Java 8，Netty，HTTP / 2，Thrift和gRPC构建的异步RPC / REST客户端/服务器库.
- [consul-api](https://github.com/Ecwid/consul-api) -Consul API的客户端：分布式的，高度可用的和数据中心感知的注册表/发现服务.
- [Eureka](https://github.com/Netflix/eureka) -基于REST的服务注册表，可实现弹性负载平衡和故障转移.
- [Helidon](https://helidon.io) -两种编写微服务的方式：功能响应型和作为MicroProfile的实现.
- [Lagom](https://www.lightbend.com/lagom) -用于创建基于微服务的系统的框架.
- [Micronaut](http://micronaut.io) -现代全栈框架，重点放在模块化，最小的内存占用和启动时间上.
- [Nacos](https://nacos.io) -用于构建云本机应用程序的动态服务发现，配置和服务管理平台.
- [Quarkus](https://quarkus.io) -为HotSpot和Graal VM量身定制的Kubernetes堆栈.

### Miscellaneous

_其他一切._

- [Codename One](https://www.codenameone.com)  -用于编写本机移动应用程序的跨平台解决方案.  （仅限GPL-2.0，带Classpath-exception-2.0）
- [CQEngine](https://github.com/npgall/cqengine) -对Java集合的超快速，类似SQL的查询.
- [Design Patterns](https://github.com/iluwatar/java-design-patterns) -实施和解释最常见的设计模式.
- [Failsafe](https://github.com/jhalterman/failsafe) -通过重试和断路器进行简单的故障处理.
- [FF4J](https://github.com/ff4j/ff4j) -Java的功能标志.
- [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition)  -认真的商人出于认真的商业目的而实施的FizzBu​​zz，这是胡说八道.  （无明确许可）
- [J2ObjC](https://github.com/google/j2objc) -Java-to-Objective-C转换器，用于将Android库移植到iOS.
- [JavaCV](https://github.com/bytedeco/javacv) -OpenCV，FFmpeg等的Java接口.
- [JavaX](http://javax.botcompany.de)  -重新设计和扩展Java，重点放在简单性上.  （无明确许可）
- [JBake](http://jbake.org) -静态网站生成器.
- [JBot](https://github.com/ramswaroop/jbot)  -构建聊天机器人的框架.  （仅限GPL-3.0）
- [JCuda](http://jcuda.org) -JCuda为CUDA和与CUDA相关的库提供Java绑定.
- [Jimfs](https://github.com/google/jimfs) -内存文件系统.
- [Joda-Money](http://www.joda.org/joda-money) -JDK未提供的基本货币和货币类以及算法.
- [JPad](http://jpad.io) -摘要跑步者.
- [Maven Wrapper](https://github.com/takari/maven-wrapper) -用于Maven的Gradle Wrapper的类比，允许在不安装maven的情况下构建项目.
- [Membrane Service Proxy](https://github.com/membrane/service-proxy) -开源的反向代理框架.
- [MinimalFTP](https://github.com/Guichaguri/MinimalFTP) -轻巧，小型且可自定义的FTP服务器.
- [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial) -流行的Java 8指南.
- [Modernizer](https://github.com/andrewgaul/modernizer-maven-plugin) -检测旧版Java API的使用.
- [Multi-OS Engine](https://multi-os-engine.org) -开源，跨平台引擎，用于开发本机移动（iOS，Android等）应用程序.
- [OctoLinker](https://github.com/OctoLinker/browser-extension) -浏览器扩展，可更有效地浏览GitHub上的代码.
- [OpenRefine](http://openrefine.org) -处理混乱数据的工具：清理，转换，使用Web服务扩展它并将其链接到数据库.
- [PipelinR](https://github.com/sizovs/pipelinr) -用于在管道中使用处理程序和命令的小型实用程序库.
- [Polyglot for Maven](https://github.com/takari/polyglot-maven) -Maven 3.3.1+的扩展，允许使用除XML以外的方言编写POM模型.
- [Simple Java Mail](https://github.com/bbottema/simple-java-mail) -使用干净流畅的API进行邮件发送.
- [Smooks](https://github.com/smooks/smooks)  -用于构建处理数据的应用程序的可扩展框架，这意味着绑定，转换，消息处理和扩充.  （仅限LGPL-3.0）
- [Togglz](https://www.togglz.org) -实现“功能切换”模式.
- [TypeTools](https://github.com/jhalterman/typetools) -解决泛型类型的工具.
- [XMLBeam](https://github.com/SvenEwald/xmlbeam) -通过在代码中使用注释或XPath处理XML.
- [yGuard](https://github.com/yWorks/yGuard) -通过重命名和缩小进行混淆.

### Monitoring

_监视生产中的应用程序的工具.

- [Automon](https://github.com/stevensouza/automon) -将AOP的功能与监视和/或记录工具结合在一起.
- [LeakCanary](https://github.com/square/leakcanary) -内存泄漏检测.
- [Failsafe Actuator](https://github.com/zalando-incubator/failsafe-actuator) -在弹簧引导环境中对故障安全断路器进行开箱即用的监视.
- [Glowroot](https://glowroot.org) -开源Java APM.
- [inspectIT](http://www.inspectit.rocks)  -通过可随时更改的钩子捕获详细的运行时信息.  它支持通过OpenTracing API跟踪多个系统，并且可以将数据与最终用户监视相关联.
 -[Instrumental！[c]]（https://instrumentalapp.com）-实时Java应用程序性能监视.  具有免费开发帐户的商业服务.
- [JavaMelody](https://github.com/javamelody/javamelody) -性能监控和性能分析.
- [Jaeger client](https://github.com/jaegertracing/jaeger-client-java) -Jaeger客户.
- [jmxtrans](https://github.com/jmxtrans/jmxtrans)  -连接到多个JVM，并通过JMX查询它们的属性.  它的查询语言基于JSON，它允许非Java程序员访问JVM属性.  支持不同的输出写入，包括Graphite，Ganglia和StatsD.
- [Jolokia](https://jolokia.org) -通过REST的JMX.
-[Kamon！[c]]（https://kamon.io）-用于监视在JVM上运行的应用程序的工具.
- [Metrics](http://metrics.dropwizard.io) -通过JMX或HTTP公开指标并将其发送到数据库.
-[Datadog！[C]]（https://www.datadoghq.com）-现代监控和分析.
- [nudge4j](https://github.com/lorenzoongithub/nudge4j) -Java 8浏览器通过字节码注入从远程开发者控制台.
- [Pinpoint](https://github.com/naver/pinpoint) -开源APM工具.
- [Prometheus](https://prometheus.io) - Provides a multi-dimensional data model, DSL, autonomous server nodes and much more.
-[SPM！[c]]（https://sematext.com/spm）-具有针对JVM应用程序分发事务跟踪的性能监视器.
- [Stagemonitor](https://github.com/stagemonitor/stagemonitor) -JVM应用程序的开源性能监视和事务跟踪.
- [Sysmon](https://github.com/palantir/Sysmon) -用于Java VM的轻量级平台监视工具.
- [zipkin](https://zipkin.io) -分布式跟踪系统，该系统收集解决微服务体系结构中的延迟问题所需的时序数据.

### Native

_用于使用特定于平台的本机库.

- [JavaCPP](https://github.com/bytedeco/javacpp) -提供对本地C ++的高效便捷访问.
- [JNA](https://github.com/java-native-access/jna)  -使用本机库而无需编写JNI.  还提供了常见系统库的接口.
- [JNR](https://github.com/jnr/jnr-ffi)  -使用本机库而无需编写JNI.  还提供了常见系统库的接口.  与JNA的目标相同，但速度更快，并且是即将到来的基础 [Project Panama](http://openjdk.java.net/projects/panama).

### Natural Language Processing

_专门处理文本的库.

- [Beagle](https://github.com/tokenmill/beagle) -存储全文本搜索查询引擎.
- [CogCompNLP](https://github.com/CogComp/cogcomp-nlp)  -提供用于普通文本输入的通用注释器.  （研究和学术使用许可）
- [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml)  -为标记，命名实体识别和情感分析等任务提供了一组基本工具.  （GPL-3.0或更高版本）
- [DKPro](https://dkpro.github.io) -收集可重复使用的NLP工具，用于语言预处理，机器学习，词汇资源等.
- [Lingua](https://github.com/pemistahl/lingua) -自然语言检测库，特别适合短文本段.
- [LingPipe](http://alias-i.com/lingpipe) -用于从POS标记到情感分析的任务的工具包.

### Networking

_用于构建网络服务器的库.

- [AkkaGRPC](https://github.com/akka/akka-grpc) -支持在Akka Streams上构建流gRPC服务器和客户端.
- [Comsat](https://github.com/puniverse/comsat) -将标准Java Web相关的API与Quasar光纤和参与者集成在一起.
- [Dubbo](https://github.com/alibaba/dubbo) -高性能RPC框架.
- [Finagle](https://github.com/twitter/finagle)  -用于构建高并发服务器的可扩展RPC系统.  它为几种协议实现统一的客户端和服务器API，并且与协议无关，以简化新协议的实现.
- [Grizzly](https://javaee.github.io/grizzly)  -NIO框架.  在Glassfish中用作网络层.
- [gRPC](https://github.com/grpc/grpc-java) -基于protobuf和HTTP / 2的RPC框架.
- [KryoNet](https://github.com/EsotericSoftware/kryonet) -使用NIO和Kryo​​提供干净，简单的API，以实现有效的TCP和UDP客户端/服务器网络通信.
- [MINA](https://mina.apache.org) -抽象的，事件驱动的异步I / O API，用于通过Java NIO在TCP / IP和UDP / IP上进行网络操作.
- [Netty](https://netty.io) -构建高性能网络应用程序的框架.
- [Nifty](https://github.com/facebook/nifty) -在Netty上实现Thrift客户端和服务器.
- [ServiceTalk](https://github.com/apple/servicetalk) -基于Netty构建的框架，具有针对特定协议量身定制的API，并支持多种编程范例.
- [sshj](https://github.com/hierynomus/sshj) - Programatically use SSH, SCP or SFTP.
- [TLS Channel](https://github.com/marianobarrios/tls-channel) -通过SSLEngine实现ByteChannel接口，从而启用易于使用的（类似于套接字的）TLS.
- [Undertow](http://undertow.io)  -提供基于NIO的阻塞和非阻塞API的Web服务器.  在WildFly中用作网络层.  （仅限LGPL-2.1）
- [urnlib](https://github.com/slub/urnlib) -表示，解析和编码URN，如RFC 2141中所示.（仅GPL-3.0）

### ORM

_处理对象持久性的API.

- [Apache Cayenne](https://cayenne.apache.org)  -提供干净的静态API进行数据访问.  还包括一个GUI Modeler，用于处理数据库映射以及数据库反向工程和生成.
- [Doma 2](https://doma.readthedocs.io) -数据库访问框架，使用注释处理以及称为双向SQL的本机SQL模板在编译时验证和生成源代码.
- [Ebean](https://ebean-orm.github.io) -提供简单快速的数据访问.
- [EclipseLink](https://www.eclipse.org/eclipselink) -支持多种持久性标准：JPA，JAXB，JCA和SDO.
- [Hibernate](http://hibernate.org/orm)  -健壮且广泛使用，拥有活跃的社区.  （仅限LGPL-2.1）
- [MyBatis](http://www.mybatis.org/mybatis-3) -将对象与存储过程或SQL语句耦合.
- [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper) -简单的数据库和CSV映射器.

### PaaS

_Java平台即服务._

-[AWS Elastic Beanstalk！[c]]（https://aws.amazon.com/elasticbeanstalk）-基于AWS的，支持Tomcat和Jetty.
-[AWS Lambda！[c]]（https://aws.amazon.com/lambda）-无服务器计算.
-[Google Cloud！[c]]（https://cloud.google.com）-Google的云基础架构.
-[Heroku！[c]]（https://www.heroku.com）-抽象计算环境.
-[Microsoft Azure！[c]]（https://azure.microsoft.com）-微软的云基础架构.
-[OpenShift！[c]]（https://www.openshift.com）-另外提供了本地解决方案.

### PDF

_帮助创建PDF文件的工具._

- [Apache FOP](https://xmlgraphics.apache.org/fop) -从XSL-FO创建PDF.
- [Apache PDFBox](https://pdfbox.apache.org) -用于创建和处理PDF的工具箱.
- [Dynamic Jasper](http://dynamicjasper.com)  -JasperReports的抽象层.  （仅限LGPL-3.0）
- [DynamicReports](https://github.com/dynamicreports/dynamicreports)  -简化JasperReports.  （仅限LGPL-3.0）
- [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer)  -XML / XHTML和CSS 2.1渲染器.  （LGPL-2.1或更高版本）
-[iText！[c]]（https://itextpdf.com）-以编程方式创建PDF文件.
- [JasperReports](https://community.jaspersoft.com/project/jasperreports-library)  -复杂的报告引擎.  （仅限LGPL-3.0）
- [Open HTML to PDF](https://github.com/danfickle/openhtmltopdf) -正确地支持基于flysaucer和Apache PDFBox的现代PDF标准.
- [OpenPDF](https://github.com/LibrePDF/OpenPDF)  -开源iText分支.  （仅限LGPL-3.0和MPL-2.0）

### Performance analysis

_用于性能分析，性能分析和基准测试的工具.

-[fastThread！[c]]（http://fastthread.io）-使用免费的基于云的上传界面分析和可视化线程转储.
 -[GCeasy！[c]]（http://gceasy.io）-分析和可视化GC日志的工具.  它提供了一个免费的基于云的上传界面.
- [honest-profiler](https://github.com/jvm-profiling-tools/honest-profiler) -低开销，无偏差的采样分析器.
- [jHiccup](https://github.com/giltene/jHiccup) -记录和记录平台JVM停顿.
- [JITWatch](https://github.com/AdoptOpenJDK/jitwatch) -分析HotSpot JVM进行的JIT编译器优化.
- [JMH](http://openjdk.java.net/projects/code-tools/jmh)  -用于构建，运行和分析以Java和其他针对JVM的其他语言编写的nano / micro / milli / macro基准测试的工具.  （仅GPL-2.0和Classpath-exception-2.0）
- [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils) -延迟测量和报告实用程序.

### Platform

_Frameworks that are suites of multiple libraries encompassing several categories._

#### Apache Commons

- [BCEL](http://commons.apache.org/proper/commons-bcel) -字节码工程库-分析，创建和操作Java类文件.
- [BeanUtils](http://commons.apache.org/proper/commons-beanutils) -围绕Java反射和自省API的易于使用的包装器.
- [BeanUtils2](http://commons.apache.org/sandbox/commons-beanutils2) -重新设计Commons BeanUtils.
- [BSF](http://commons.apache.org/proper/commons-bsf) -Bean脚本框架-脚本语言（包括JSR-223）的接口.
- [Chain](http://commons.apache.org/proper/commons-chain) -责任链模式实施.
- [ClassScan](http://commons.apache.org/sandbox/commons-classscan) -查找类接口，方法，字段和注释而无需加载.
- [CLI](http://commons.apache.org/proper/commons-cli) -命令行参数解析器.
- [CLI2](http://commons.apache.org/sandbox/commons-cli2) -重新设计Commons CLI.
- [Codec](http://commons.apache.org/proper/commons-codec) -通用的编码/解码算法，例如语音，base64或URL.
- [Collections](http://commons.apache.org/proper/commons-collections) -扩展或扩充Java Collections Framework.
- [Compress](http://commons.apache.org/proper/commons-compress) -定义用于处理tar，zip和bzip2文件的API.
- [Configuration](http://commons.apache.org/proper/commons-configuration) -读取各种格式的配置/首选项文件.
- [Convert](http://commons.apache.org/sandbox/commons-convert) -Commons-Convert旨在提供一个单一的库，专门用于将一种类型的对象转换为另一种类型的对象.
- [CSV](http://commons.apache.org/proper/commons-csv) -用于读取和写入逗号分隔值文件的组件.
- [Daemon](http://commons.apache.org/proper/commons-daemon) -类似于Unix守护程序的Java代码的替代调用机制.
- [DBCP](http://commons.apache.org/proper/commons-dbcp) -数据库连接池服务.
- [DbUtils](http://commons.apache.org/proper/commons-dbutils) -JDBC帮助程序库.
- [Digester](http://commons.apache.org/proper/commons-digester) -XML到Java对象的映射实用程序.
- [Email](http://commons.apache.org/proper/commons-email) -用于从Java发送电子邮件的库.
- [Exec](http://commons.apache.org/proper/commons-exec) -用Java处理外部流程执行和环境管理的API.
- [FileUpload](http://commons.apache.org/proper/commons-fileupload) -用于Servlet和Web应用程序的文件上传功能.
- [Finder](http://commons.apache.org/sandbox/commons-finder) -受UNIX find命令启发的Java库.
- [Flatfile](http://commons.apache.org/sandbox/commons-flatfile) -用于处理平面数据结构的Java库.
- [Functor](http://commons.apache.org/proper/commons-functor) -可以作为对象或代表单个通用函数的对象进行操作的函数.
- [Graph](http://commons.apache.org/sandbox/commons-graph) -通用图形API和算法.
- [I18n](http://commons.apache.org/sandbox/commons-i18n) -添加了由一个或多个属于一起的本地化文本组成的本地化消息包的功能.
- [Id](http://commons.apache.org/sandbox/commons-id) -ID是用于生成标识符的组件.
- [Imaging](http://commons.apache.org/proper/commons-imaging) -图片库.
- [IO](http://commons.apache.org/proper/commons-io) -I / O实用程序的集合.
- [Javaflow](http://commons.apache.org/sandbox/commons-javaflow) -继续实施以捕获应用程序的状态.
- [JCI](http://commons.apache.org/proper/commons-jci) -Java编译器接口.
- [JCS](http://commons.apache.org/proper/commons-jcs) -Java缓存系统.
- [Jelly](http://commons.apache.org/proper/commons-jelly) -基于XML的脚本和处理引擎.
- [Jexl](http://commons.apache.org/proper/commons-jexl) -扩展JSTL的表达语言的表达语言.
- [JNet](http://commons.apache.org/sandbox/commons-jnet) -JNet允许通过java.net API动态使用注册的URL流处理程序.
- [JXPath](http://commons.apache.org/proper/commons-jxpath) -使用XPath语法处理Java Bean的实用程序.
- [Lang](http://commons.apache.org/proper/commons-lang) -为java.lang中的类提供额外的功能.
- [Logging](https://en.wikipedia.org/wiki/Apache_Commons_Logging) -各种日志API实现的包装器.
- [Math](http://commons.apache.org/proper/commons-math) -轻巧，独立的数学和统计组件.
- [Monitoring](http://commons.apache.org/sandbox/commons-monitoring) -监视旨在为Java应用程序提供一个简单但可扩展的监视解决方案.
- [Nabla](http://commons.apache.org/sandbox/commons-nabla) -Nabla提供了自动区分类，可以生成以Java语言实现的任何功能的派生类.
- [Net](http://commons.apache.org/proper/commons-net) -网络实用程序和协议实现的集合.
- [OGNL](http://commons.apache.org/proper/commons-ognl) -对象图导航语言.
- [OpenPGP](http://commons.apache.org/sandbox/commons-openpgp) -使用OpenPGP签名和验证数据的接口.
- [Performance](http://commons.apache.org/sandbox/commons-performance) -微型基准客户端的小型框架，具有Commons DBCP和Pool的实现.
- [Pipeline](http://commons.apache.org/sandbox/commons-pipeline) -提供一组围绕工作队列设计的管道实用程序，这些并行运行以顺序处理数据对象.
- [Pool](http://commons.apache.org/proper/commons-pool) -通用对象池组件.
- [Proxy](http://commons.apache.org/proper/commons-proxy) -用于创建动态代理的库.
- [RDF](https://commons.apache.org/proper/commons-rdf) -RDF 1.1的通用实现，可以由JVM上的系统实现.
- [RNG](https://commons.apache.org/proper/commons-rng) -Commons Rng提供了伪随机数生成器的实现.
- [SCXML](http://commons.apache.org/proper/commons-scxml) -旨在创建和维护Java SCXML引擎的State Chart XML规范的实现.
- [Validator](http://commons.apache.org/proper/commons-validator) -在xml文件中定义验证器和验证规则的框架.
- [VFS](http://commons.apache.org/proper/commons-vfs) -虚拟文件系统组件，用于将文件，FTP，SMB，ZIP等视为单个逻辑文件系统.
- [Weaver](http://commons.apache.org/proper/commons-weaver) -提供一种简单的方法来增强（编织）已编译的字节码.

#### Other

- [CUBA Platform](https://cuba-platform.com) -基于Spring，EclipseLink和Vaadin的具有丰富Web界面的企业应用程序开发高级框架.
- [Light-Java](https://github.com/networknt/light-java) -内置的快速，轻量级和高效的微服务框架 [security](https://github.com/networknt/light-oauth2).
- [Orienteer](https://github.com/OrienteerBAP/Orienteer) -开源业务应用程序平台，用于快速配置/开发CRM，ERP，LMS和其他应用程序.
- [Spring](https://spring.io/projects) -提供许多用于依赖项注入，面向方面的编程，安全性等的程序包.

### Processes

_帮助管理操作系统进程的库.

- [ch.vorburger.exec](https://github.com/vorburger/ch.vorburger.exec) -围绕Apache Commons Exec的便捷API.
- [zt-exec](https://github.com/zeroturnaround/zt-exec) -为Apache Commons Exec和ProcessBuilder提供统一的API.
- [zt-process-killer](https://github.com/zeroturnaround/zt-process-killer) -停止从Java启动的进程或通过PID的系统进程.

### Reactive libraries

_用于开发响应式应用程序的库.

- [Akka](https://akka.io) -用于构建并发，分布式，容错和事件驱动的应用程序的工具包和运行时.
- [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm) -为无阻塞背压的异步流处理提供标准.
- [Reactor](https://projectreactor.io) -用于建立反应快速数据应用程序的库.
- [RxJava](https://github.com/ReactiveX/RxJava) -允许使用可观察的序列组成异步和基于事件的程序.
- [vert.x](https://vertx.io) -Polyglot事件驱动的应用程序框架.

### REST Frameworks

_专门用于创建RESTful服务的框架.

- [Dropwizard](https://dropwizard.github.io/dropwizard) -通过Jetty，Jackson，Jersey和Metrics建立现代Web应用程序的自觉框架.
- [Elide](http://elide.io) -基于JPA数据模型的JSON-或GraphQL-API的框架.
- [javalin](https://javalin.io) -Javalin只是Jetty上的几千行代码，这意味着它的性能几乎等同于纯Jetty.
- [Jersey](https://jersey.github.io) -JAX-RS参考实现.
- [Microserver](https://github.com/aol/micro-server)  -用于Spring和Spring Boot的便捷，可扩展的微服务插件系统.  随着30多个插件的不断发展，它支持微独石和纯微服务样式.
- [Rapidoid](https://www.rapidoid.org) -简单，安全且快速的框架，由嵌入式HTTP服务器，GUI组件和依赖项注入组成.
- [rest.li](https://github.com/linkedin/rest.li) -使用端到端开发人员工作流的类型安全绑定和异步，无阻塞IO构建健壮，可扩展的RESTful架构的框架，该端到端开发人员工作流可促进简洁的做法，统一的界面设计和一致的数据建模.
- [RESTEasy](https://resteasy.jboss.org) -JAX-RS规范的完全认证和可移植的实现.
- [RestExpress](https://github.com/RestExpress/RestExpress) -JBoss Netty HTTP堆栈上的精简包装，可提供扩展和性能.
- [Restlet Framework](https://github.com/restlet/restlet-framework-java) -具有强大的路由和过滤功能以及统一的客户端和服务器API的开拓性框架.
- [Spark](http://sparkjava.com) -Sinatra启发框架.
- [Crnk](http://www.crnk.io) -实施JSON API规范，以建立具有排序，过滤，分页，链接，对象图，类型安全，批量更新，集成等功能的面向资源的REST端点.
- [springdoc-openapi](https://github.com/springdoc/springdoc-openapi) -使用Spring Boot项目自动生成API文档.
- [Swagger](https://swagger.io) -REST API的标准，与语言无关的接口.

### Science

_用于科学计算，分析和可视化的库.

- [DataMelt](http://jwork.org/dmelt)  -科学计算，数据分析和数据可视化的环境.  （GPL-3.0或更高版本）
- [Erdos](https://github.com/Erdos-Graph-Framework/Erdos) -用于理论算法的模块化，轻巧易用的图形框架.
- [GraphStream](http://graphstream-project.org) -用于建模和分析动态图的库.
- [JFreeChart](http://www.jfree.org/jfreechart)  -用于Swing，JavaFX和服务器端应用程序的2D图表库.  （仅限LGPL-2.1）
- [JGraphT](https://github.com/jgrapht/jgrapht) -提供数学图形理论对象和算法的图形库.
- [JGraphX](https://github.com/jgraph/jgraphx) -用于可视化（主要是Swing）并与节点边缘图进行交互的库.
- [Mines Java Toolkit](https://github.com/MinesJTK/jtk) -用于地球物理科学计算，可视化和数字信号分析的库.
- [Morpheus](http://www.zavtech.com/morpheus/docs) -提供称为DataFrame的通用二维内存高效表格式数据结构，以实现对JVM上的科学计算进行高效的内存中分析.
- [Orson-Charts](https://github.com/jfree/orson-charts)  -生成各种3D图表，这些图表可以与Swing和JavaFX一起显示，也可以导出到PDF，SVG，PNG和JPEG.  （仅限GPL-3.0）
- [Tablesaw](https://github.com/lwhite1/tablesaw) -包括数据框，嵌入式列存储以及数百种转换，汇总或过滤数据的方法.
- [XChart](https://github.com/knowm/XChart)  -用于绘制数据的轻型库.  有许多可定制的图表类型.

### Search

_将文档编入索引以进行搜索和分析的引擎._

- [Apache Lucene](https://lucene.apache.org) -高性能，全功能，跨平台的文本搜索引擎库.
- [Apache Solr](https://lucene.apache.org/solr) -针对大流量进行了优化的企业搜索引擎.
- [Elasticsearch](https://www.elastic.co) -具有RESTful Web界面和无模式JSON文档的分布式，多租户，全文本搜索引擎.
- [Indexer4j](https://github.com/haeungun/indexer4j) -简单轻巧的全文本索引编制和搜索库.

### Security

_处理安全性，身份验证，授权或会话管理的库.

- [Apache Shiro](https://shiro.apache.org) -执行身份验证，授权，加密和会话管理.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) -通用的加密库和JCA提供程序，提供从基本帮助程序到PGP / SMIME操作的广泛功能.
- [Cryptomator](https://cryptomator.org)  -云中文件的多平台，透明，客户端加密.  （仅限GPL-3.0）
- [Hdiv](https://github.com/hdiv/hdiv) -排除OWASP Top 10中包含的应用程序安全风险的运行时应用程序，包括SQL注入，跨站点脚本，跨站点请求伪造，数据篡改和暴力攻击.
- [jjwt](https://github.com/jwtk/jjwt) -适用于Java和Android的JSON网络令牌.
- [Jwks RSA](https://github.com/auth0/jwks-rsa-java) -JSON Web密钥集解析器.
- [Kalium](https://github.com/abstractj/kalium) -绑定网络和密码学（NaCl）库.
- [Keycloak](https://www.keycloak.org) -用于浏览器应用程序和RESTful Web服务的集成SSO和IDM.
- [Keywhiz](https://github.com/square/keywhiz) -分发和管理机密的系统.
- [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz) -高级密码强度估算.
- [OACC](http://oaccframework.org) -提供基于权限的授权服务.
- [pac4j](https://github.com/pac4j/pac4j) -安全引擎.
- [SecurityBuilder](https://github.com/tersesystems/securitybuilder) -用于JCA和JSSE类的Fluent Builder API，尤其是X.509证书.
- [Themis](https://github.com/cossacklabs/themis)  多平台高级密码库提供了易于使用的加密来保护敏感数据：具有前向保密性的安全消息传递，安全数据存储（AES256GCM）；  适用于构建端到端的加密应用程序.
- [Tink](https://github.com/google/tink) -为常见的加密任务提供了一个简单且防误用的API.
- [Vault](https://www.vaultproject.io)  -保护，存储和严格控制对令牌，密码，证书，API密钥和其他机密的访问.  它处理租赁，密钥撤销，密钥滚动和审计.  通过统一的API，用户可以访问加密的密钥/值存储和网络加密即服务，或生成AWS IAM / STS凭证，SQL / NoSQL数据库，X.509证书，SSH凭证等.

### Serialization

_高效处理序列化的库.

- [FlatBuffers](https://github.com/google/flatbuffers) -内存高效的序列化库，可以访问序列化的数据而无需解压缩和分析它们.
- [FST](https://github.com/RuedigerMoeller/fast-serialization) -兼容JDK的高性能对象图序列化.
- [Kryo](https://github.com/EsotericSoftware/kryo) -快速高效的对象图序列化框架.
- [MessagePack](https://github.com/msgpack/msgpack-java) -高效的二进制序列化格式.
- [PHP Serializer](https://github.com/marcospassos/java-php-serializer) -以PHP序列化格式序列化对象.

### Server

_专门用于部署应用程序的服务器.

- [Apache Tomcat](https://tomcat.apache.org) -用于Servlet和JSP的功能强大的全方位服务器.
- [Apache TomEE](https://tomee.apache.org) -Tomcat和Java EE.
- [Jetty](https://www.eclipse.org/jetty) -提供Web服务器和javax.servlet容器，以及对HTTP / 2，WebSocket，OSGi，JMX，JNDI，JAAS和许多其他集成的支持.
- [nanohttpd](https://github.com/NanoHttpd/nanohttpd) -微型，易于嵌入的HTTP服务器.
- [WildFly](http://www.wildfly.org)  -原名JBoss，由Red Hat开发，具有广泛的Java EE支持.  （仅限LGPL-2.1）

### Template Engine

_在模板中替换表达式的工具._

- [Handlebars.java](https://jknack.github.io/handlebars.java) -无逻辑和语义的Moustache模板.
- [Jade4J](https://github.com/neuland/jade4j) -实施Pug（以前称为Jade）.
- [Jtwig](http://jtwig.org) -模块化，可配置且经过全面测试的模板引擎.
- [Pebble](https://pebbletemplates.io)  -受到Twig的启发，并以其继承功能和易于阅读的语法而与众不同.  它带有内置的自动转义功能以确保安全性，并且包括对国际化的集成支持.
- [Rocker](https://github.com/fizzed/rocker) -优化，内存高效且快速的模板引擎，可生成静态类型的普通对象.
- [Thymeleaf](http://www.thymeleaf.org) -旨在替代JSP并适用于XML文件.

### Testing

_从模型到视图进行测试的工具._

#### Asynchronous

_简化异步服务测试的工具._

- [Awaitility](https://github.com/jayway/awaitility) -用于同步异步操作的DSL.
- [ConcurrentUnit](https://github.com/jhalterman/concurrentunit) -用于测试多线程和异步应用程序的工具包.
- [GreenMail](http://www.icegreen.com/greenmail)  -用于集成测试的内存电子邮件服务器.  支持SMTP，POP3和IMAP（包括SSL）.  （仅限GPL-2.0）
- [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java) -Hoverfly的本机绑定，Hoverfly是一个代理，可用于模拟HTTP服务.
- [REST Assured](https://github.com/jayway/rest-assured) -DSL，可轻松测试REST / HTTP服务.
- [Karate](https://github.com/intuit/karate) -结合了API测试自动化，模拟和性能测试的DSL，使测试REST / HTTP服务变得容易.

#### BDD

_对TDD中出现的，受DDD和OOAD严重影响的软件开发过程进行测试.

- [Cucumber](https://github.com/cucumber/cucumber-jvm) -提供一种以普通语言描述功能的方法，客户可以理解.
- [Cukes-REST](https://github.com/ctco/cukes-rest) -收集使用黄瓜进行REST服务测试的Gherkin步骤.
- [J8Spec](https://github.com/j8spec/j8spec) -遵循类似Jasmine的语法.
- [JBehave](http://jbehave.org) -描述故事的可广泛配置的框架.
- [JGiven](http://jgiven.org) -提供流利的API，可以简化组成.
- [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave) -旨在提供流利的API，以长而描述性的句子编写测试，使句子看起来像普通英语.
- [Serenity BDD](https://www.thucydides.info) -与Cucumber，JBehave和JUnit一起使用的自动验收测试和报告库，使编写高质量的可执行规范变得更加容易.

#### Fixtures

_与创建和处理随机数据有关的一切._

- [Beanmother](https://github.com/keepcosmos/beanmother) -从YAML固定装置设置bean.
- [Fixture Factory](https://github.com/six2six/fixture-factory) -从模板生成伪造的对象.
- [jFairy](https://github.com/Devskiller/jfairy) -伪数据生成器.
- [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) -JUnit测试运行程序和用于以伪随机性运行JUnit测试的插件.
- [Java Faker](https://github.com/DiUS/java-faker) -Ruby的伪造数据生成器的端口.

#### Frameworks

_提供环境以针对特定用例运行测试.

- [ArchUnit](https://github.com/TNG/ArchUnit) -用于指定和声明体系结构规则的测试库.
- [Apache JMeter](http://jmeter.apache.org) -功能测试和性能测量.
- [Arquillian](http://arquillian.org) -Java EE容器的集成和功能测试平台.
- [Citrus](https://citrusframework.org) -集中于客户端和服务器端消息传递的集成测试框架.
- [Gatling](https://gatling.io) -旨在简化易用性，可维护性和高性能的负载测试工具.
- [JUnit](http://junit.org) -通用的测试框架.
- [jqwik](https://jqwik.net) -基于JUnit 5的基于属性的测试引擎.
- [Pact JVM](https://github.com/DiUS/pact-jvm) -消费者驱动的合同测试.
- [PIT](http://pitest.org) -快速的突变测试框架，用于评估现有JUnit或TestNG测试套件的故障检测能力.

#### Matchers

_提供自定义匹配项的库.

- [AssertJ](https://joel-costigliola.github.io/assertj) -流利的断言，可提高可读性.
- [Hamcrest](http://hamcrest.org/JavaHamcrest) -可以组合以创建灵活的意图表达的匹配器.
- [JSONAssert](http://jsonassert.skyscreamer.org) -简化了JSON字符串的测试.
- [Truth](https://truth.dev) -Google的流利断言和主张框架.
- [XMLUnit](https://github.com/xmlunit/xmlunit) -简化了XML输出的测试.

#### Miscellaneous

_与测试有关的其他内容._

- [junit-dataprovider](https://github.com/TNG/junit-dataprovider) -JUnit的类似TestNG的数据提供程序/运行程序.
- [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector) -报告给定类的实例是否不可变.
- [raml-tester](https://github.com/nidi3/raml-tester) -测试请求/响应是否匹配给定的RAML定义.
- [TestContainers](https://github.com/testcontainers/testcontainers-java) -提供普通数据库，Selenium Web浏览器或可以在Docker容器中运行的任何其他东西的一次性实例.
- [pojo-tester](http://www.pojo.pl)  -自动对基本的POJO方法执行测试.  （仅限LGPL-3.0）

#### Mocking

_模拟合作者以帮助测试单个隔离单元的工具.

- [JMockit](http://jmockit.github.io) -集成测试，API模拟和伪造以及代码覆盖率.
- [Mockito](https://github.com/mockito/mockito) -模拟框架，可让您使用干净简单的API编写测试.
- [MockServer](https://www.mock-server.com) -允许模拟与HTTPS集成的系统.
- [Moco](https://github.com/dreamhead/moco) -存根和模拟的简洁Web服务.
- [PowerMock](https://github.com/jayway/powermock) -嘲笑静态方法，构造函数，最终类和方法，私有方法以及静态初始化程序的删除.
- [WireMock](http://wiremock.org) -存根和模拟网络服务.

### Utility

_提供一般实用程序功能的库.

- [bucket4j](https://github.com/vladimir-bukhtoyarov/bucket4j) -基于令牌桶算法的速率限制库.
- [cactoos](http://www.cactoos.org) -面向对象原语的集合.
- [CRaSH](http://www.crashub.org)  -为运行CRaSH的JVM提供外壳程序.  由Spring Boot和其他人使用.  （LGPL-2.1或更高版本）
- [Dex](https://github.com/PatMartin/Dex) -具备强大的ETL和数据可视化功能的Java / JavaFX工具.
- [Embulk](http://www.embulk.org) -批量数据加载器，可帮助在各种数据库，存储，文件格式和云服务之间进行数据传输.
- [fswatch](https://github.com/vorburger/ch.vorburger.fswatch) -微型库，用于监视目录文件系统的更改，从而简化了java.nio.file.WatchService.
- [Gephi](https://github.com/gephi/gephi)  -用于可视化和操纵大型图形网络的跨平台.  （仅限GPL-3.0）
- [Guava](https://github.com/google/guava) -集合，缓存，原语支持，并发库，通用批注，字符串处理，I / O等.
- [JADE](http://jade.tilab.com)  -用于构建和调试多代理系统的框架和环境.  （仅限LGPL-2.0）
- [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions) -帮助构建困难的正则表达式的库.
- [JGit](https://eclipse.org/jgit) -实施Git版本控制系统的轻量级纯Java库.
- [minio-java](https://github.com/minio/minio-java) -提供简单的API来访问任何与Amazon S3兼容的对象存储服务器.
- [Protégé](https://protege.stanford.edu) -提供本体编辑器和框架来构建基于知识的系统.
- [Underscore-java](https://github.com/javadev/underscore-java) -Underscore.js函数的端口.

### Version Managers

_Utilities that help create the development shell environment and switch between different Java versions._

- [jabba](https://github.com/shyiko/jabba)  -受nvm启发的Java版本管理器.  支持macOS，Linux和Windows.
- [jenv](https://github.com/gcuisinier/jenv)  -受rbenv启发的Java版本管理器.  可以全局配置或按项目配置.  在Debian和macOS上测试.
- [SDKMan](https://github.com/sdkman/sdkman-cli)  -受RVM和rbenv启发的Java版本管理器.  支持基于UNIX的平台和Windows.

### Web Crawling

_分析网站内容的图书馆.

- [Apache Nutch](https://nutch.apache.org) -用于生产环境的高度可扩展，高度可扩展的Web搜寻器.
- [Crawler4j](https://github.com/yasserg/crawler4j) -简单轻巧的网络爬虫.
- [jsoup](https://jsoup.org) -刮，解析，处理和清除HTML.
- [StormCrawler](http://stormcrawler.net) -用于构建低延迟和可扩展的Web搜寻器的SDK.
- [webmagic](https://github.com/code4craft/webmagic) -具有下载，URL管理，内容提取和持久性的可扩展爬虫.

### Web Frameworks

_处理Web应用程序各层之间的通信的框架.

- [Apache Tapestry](https://tapestry.apache.org) -用于创建动态，健壮，高度可伸缩的Web应用程序的面向组件的框架.
- [Apache Wicket](https://wicket.apache.org) -与Tapestry类似的基于组件的Web应用程序框架，带有状态GUI.
- [Blade](https://github.com/biezhi/blade) -轻巧的模块化框架，旨在变得优雅和简单.
- [Bootique](https://bootique.io) -可运行的应用程序的最低限度的框架.
- [Firefly](http://www.fireflysource.com) -用于快速开发高性能Web应用程序的异步框架.
- [Grails](https://grails.org) -Groovy框架通过支持约定优于配置，不提供XML和对mixins的支持来提供高效的环境.
- [Jooby](http://jooby.org) -可扩展，快速和模块化的微框架，提供多种编程模型.
- [Ninja](http://www.ninjaframework.org) -全栈Web框架.
- [Pippo](http://www.pippo.ro) -小型，高度模块化的，类似于Sinatra的框架.
- [Play](https://www.playframework.com) -建立在Akka之上，它为Java和Scala中的高度可扩展应用程序提供了可预测的最小资源消耗（CPU，内存，线程）.
- [PrimeFaces](https://primefaces.org) -包含免费和商业/支持版本以及前端组件的JSF框架.
- [Ratpack](https://ratpack.io) -促进快速，高效，可发展且经过测试的HTTP应用程序的库集.
- [Takes](https://github.com/yegor256/takes) -固执己见的Web框架，它围绕真实的面向对象编程和不变性的概念构建.
- [Vaadin Flow](https://vaadin.com/flow)  -使用标准Web组件的事件驱动框架.  客户端具有Ajax的服务器端体系结构.

## Resources

### Awesome Lists

_与Java和JVM生态系统相关的很棒的清单.

- [Awesome Annotation Processing](https://github.com/gunnarmorling/awesome-annotation-processing)
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

_积极的讨论.

- [r/java](https://www.reddit.com/r/java) -Java社区的Subreddit.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/java) -问题/答案平台.
- [VirtualJUG](https://virtualjug.com) -虚拟Java用户组.

### Frontends

 _为此列表提供前端的网站.  请注意，不会有一个官方网站.  我们不与特定网站关联，每个人都可以创建一个网站._

- [java.libhunt.com](https://java.libhunt.com)

### Influential Books

_影响深远的书仍然值得一读.

- [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
- [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
- [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
- [Thinking in Java](https://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

### Podcasts and Screencasts

_编程时要看或听的东西._

- [Java Off Heap](http://www.javaoffheap.com)
- [Marco Behler's Screencasts](https://www.marcobehler.com/series) -有关现代Java开发的屏幕录像.
- [The Java Council](https://virtualjug.com/#podcast)
- [The Java Posse](http://www.javaposse.com) -自2015年2月起停产.

### Twitter

 _要跟踪的有效帐户.  来自Twitter的说明._

- [Adam Bien](https://twitter.com/AdamBien) -自由作者，JavaOne Rockstar发言人，顾问，Java Champion.
- [Aleksey Shipilëv](https://twitter.com/shipilev) -性能极客，基准沙皇，并发漏洞猎人.
- [Antonio Goncalves](https://twitter.com/agoncal) -Java冠军，JUG负责人，法国Devoxx，Java EE 6/7，JCP，作者.
- [Arun Gupta](https://twitter.com/arungupta) -Java冠军，JavaOne Rockstar，JUG负责人，Devoxx4Kids-er，Couchbase开发人员宣传副总裁.
- [Brian Goetz](https://twitter.com/BrianGoetz) -Oracle的Java语言架构师.
- [Bruno Borges](https://twitter.com/brunoborges) -Oracle产品经理/ Java Jock.
- [Chris Richardson](https://twitter.com/crichardson) -软件架构师，顾问和连续企业家，Java Champion，JavaOne Rock Star和\ * POJO in Action-作者.
- [Ed Burns](https://twitter.com/edburns) -Oracle技术人员的咨询成员.
- [Eugen Paraschiv](https://twitter.com/baeldung) -春季安全课程的作者.
- [Heinz Kabutz](https://twitter.com/heinzkabutz) -Java冠军，演讲者，《 Java专家通讯》的作者，并发性能专家.
- [Holly Cummins](https://twitter.com/holly_cummins) -IBM伦敦Bluemix Garage的技术负责人，Java冠军，开发人员，作家JavaOne摇滚明星.
- [James Weaver](https://twitter.com/JavaFXpert) -Java / JavaFX / IoT开发人员，作者和发言人.
- [Java EE](https://twitter.com/Java_EE) -官方Java EE Twitter帐户.
- [Java Magazine](https://twitter.com/Oraclejavamag) -官方Java杂志帐户.
- [Java](https://twitter.com/java) -官方Java Twitter帐户.
- [Javin Paul](https://twitter.com/javinpaul) -著名的Java博客.
- [Josh Long](https://twitter.com/starbuxman) -Pivotal的Spring Advocate，是O&#39;Reilly的Cloud Native Java和使用Spring Boot构建微服务JavaOne Rock Star的作者.
- [Lukas Eder](https://twitter.com/lukaseder) -Java冠军，演讲者，JUG.ch联合负责人，Data Geekery（jOOQ）的创始人兼首席执行官.
- [Mario Fusco](https://twitter.com/mariofusco) -RedHatter，JUG协调员，常任发言人和作家.
- [Mark Heckler](https://twitter.com/MkHeck) -Pivotal首席技术专家兼开发倡导者，会议发言人，已发表的作者，以及Java Champion，专注于物联网和云.
- [Mark Reinhold](https://twitter.com/mreinhold) -Oracle Java平台组首席架构师.
- [Markus Eisele](https://twitter.com/myfear) -Java EE传播者，Red Hat.
- [Martijn Verburg](https://twitter.com/karianna) -伦敦JUG联合领导人，发言人，作家，Java冠军等等.
- [Martin Thompson](https://twitter.com/mjpt777) -面对表现performance徒.
- [Monica Beckwith](https://twitter.com/mon_beck) -JavaOne Rock Star性能顾问.
- [OpenJDK](https://twitter.com/OpenJDK) -官方OpenJDK帐户.
- [Peter Lawrey](https://twitter.com/PeterLawrey) -Java性能专家Peter Lawrey.
- [Randy Shoup](https://twitter.com/randyshoup) -Stitch Fix副总裁，JavaOne Rock Star演讲者.
- [Reza Rahman](https://twitter.com/reza_rahman) -Java EE / GlassFish / WebLogic传播者，作者，演讲者，开源黑客.
- [Sander Mak](https://twitter.com/Sander_Mak) -Java冠军，作家.
- [Simon Maple](https://twitter.com/sjmaple) -Java冠军，VirtualJUG创始人，LJC负责人，RebelLabs作者.
- [Spencer Gibb](https://twitter.com/spencerbgibb) - Software Engineer, Dad, Geek, Co-founder and Lead of Spring Cloud Core @pivotal.
- [Stephen Colebourne](https://twitter.com/jodastephen) -Java Champion，演讲者.
- [Trisha Gee](https://twitter.com/trisha_gee) -Java Champion和演讲者.
- [Venkat Subramaniam](https://twitter.com/venkat_s) -作者，休斯顿大学教授，MicroSoft MVP获奖者，JavaOne Rock Star，Java Champion.
- [Vlad Mihalcea](https://twitter.com/vlad_mihalcea) -从事Hypersistence Optimizer的Java Champion，数据库爱好者，《高性能Java持久性》一书的作者.

### Websites

_要阅读的网站._

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

欢迎捐款！

请看看 [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) 准则和 [the validation tools](https://github.com/akullpp/awesome-java-validation).

[c]：https：//cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg
