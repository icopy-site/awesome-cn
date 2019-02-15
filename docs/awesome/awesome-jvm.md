## Awesome JVM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的JVM低级，性能和非框架相关内容的精选列表.

- [Awesome JVM](#awesome-jvm)
    - [Bytecode](#bytecode)
    - [Garbage collectors](#garbage-collectors)
    - [Load tools](#load-tools)
    - [Languages](#languages)
    - [Machine Learning](#machine-learning)
    - [Memory and Concurrency](#memory-and-concurrency)
    - [Metaprogramming](#metaprogramming)
    - [Native](#native)
    - [Network](#network)
    - [Nix tools](#nix-tools)
    - [Profilers](#profilers)
    - [Runtimes](#runtimes)
    - [Virtual Machines](#virtual-machines)
- [Resources](#resources)
    - [Communities](#communities)    
    - [Documentation](#documentation)
    - [Media](#media)
    - [People](#people)
- [Contributing](#contributing)


## Bytecode

*用于字节码操作和分析的工具.*

* [asmtools](https://wiki.openjdk.java.net/display/CodeTools/asmtools) - 用于开发用于生成Java .class文件的工具.
* [Byte Buddy](http://bytebuddy.net) - 代码生成库在运行时无需编译器的帮助即可创建Java类.
* [Jitescript](https://github.com/qmx/jitescript) - 类似于BiteScript的字节码生成库. 

## Garbage collectors

* JVM的垃圾收集器.*

* [Azul Pauseless Garbage Collection](https://www.azul.com/files/wp_pgc_zing_v52.pdf) - 为Java应用程序提供连续，无间歇的操作.
* [Balanced GC](http://www.ibm.com/developerworks/websphere/techjournal/1108_sciampacone/1108_sciampacone.html) - 用于IBM WebSphere Application Server V8的Java虚拟机中提供的GC策略.
* [Epsilon GC](http://openjdk.java.net/jeps/318) - 完全被动的GC实现，具有有限的分配限制，并且可能具有最低的运行时性能开销.
* [G1](http://www.oracle.com/technetwork/java/javase/tech/g1-intro-jsp-135488.html) -  Garbage-First垃圾收集器.
* [Shenandoah](http://openjdk.java.net/jeps/189) - 超低暂停时间垃圾收集器.
* [The Garbage Collection Handbook](http://gchandbook.org) - 预定了最近硬件和软件方面的垃圾收集新挑战.
* [ZGC](http://mail.openjdk.java.net/pipermail/announce/2017-October/000237.html) - 垃圾收集器针对低延迟和非常大的堆进行了优化.

## Load tools

*生成负载并精确测量系统的工具，无需协调遗漏*

* [Gatling](http://gatling.io) - 用于测试HTTP服务器的异步非阻塞方案驱动的负载测试工具.
* [wrk2](https://github.com/giltene/wrk2) -  wrk的恒定吞吐量，正确延迟记录变体.

## Languages

*在JVM上运行的语言.*
* [Ceylon](http://ceylon-lang.org/) - 由Red Hat创建的面向对象的强大而静态的编程语言，强调不变性.
* [Clojure](http://clojure.org/)   -  Rich Hickey创作的Lisp方言.  动态类型，强调函数式编程.
* [Erjang](http://www.erjang.org) - 基于JVM的Erlang VM.
* [Eta](http://eta-lang.org/) -  JVM上纯粹，懒惰，强类型的函数式编程语言.
* [Frege](https://github.com/Frege/frege) -  Haskell精神中的纯函数式编程语言.
* [gojava](https://github.com/sridharv/gojava) -  Go包的Java绑定.
* [Golo](http://golo-lang.org/) - 一种简单的动态语言，广泛使用`invokedynamic`.
* [Groovy](http://www.groovy-lang.org/) - 可选的类型和动态语言，具有静态类型和静态编译功能.
* [Java](http://www.oracle.com/technetwork/java/javase/overview/index.html) - 通用，并发，强类型，基于类的面向对象语言.
* [JRuby](http://jruby.org) - 在JVM上实现Ruby语言.
* [JPHP](https://github.com/jphp-group/jphp) -  Java VM上的PHP.
* [Jython](http://www.jython.org) - 用于Java平台的Python.
* [Kawa](http://www.gnu.org/software/kawa/) -  Scheme语言的扩展，它是Lisp系列编程语言.
* [Kotlin](http://kotlinlang.org/) - 用于JVM，Android和浏览器的静态类型编程语言.
* [LuaJ](http://www.luaj.org/luaj/3.0/README.html) - 以Java为中心的lua vm实现，旨在利用标准Java功能.
* [Nashorn](http://openjdk.java.net/projects/nashorn/) - 使用本机JVM的Java轻量级高性能JavaScript运行时.
* [OCaml-Java](http://www.ocamljava.org/)   - 支持OCaml语言v4.  生成普通的Java字节码并与Java无缝集成.
* [Rembulan](https://github.com/mjanicek/rembulan) -  Rembulan是JVM的Lua 5.3实现，用纯Java编写，具有最小的依赖性.
* [Renjin](http://www.renjin.org/) - 用于R语言的基于JVM的解释器，用于统计分析
* [Scala](http://www.scala-lang.org/) - 强大而静态的编程语言，结合了面向对象和函数式编程思想.
* [Xtend](http://www.eclipse.org/xtend/) -  Java的灵活和富有表现力的方言，它编译成Java 5源代码.

## Machine Learning
* [Deeplearning4j](https://deeplearning4j.org/) - 用于JVM的开源，分布式深度学习库.
* [H2O](https://www.h2o.ai/) - 快速统计，机器学习和数学运行时.
* [Smile](https://github.com/haifengl/smile) - 统计机器智能和学习引擎.

## Memory and concurrency

*用于高效内存布局和并发访问的工具和数据结构.*

* [Agera](https://github.com/google/agera) -  Google的Android反应式编程.
* [Agrona](https://github.com/real-logic/Agrona) - 构建高性能应用程序时常见的数据结构和实用程序方法库.
* [Apache Arrow](http://arrow.apache.org/) - 用于柱状内存分析的高性能跨系统数据层.
* [bloofi](https://github.com/lemire/bloofi) - 多维Bloom过滤器的Java实现
* [Cap’n Proto](https://capnproto.org/) - 疯狂快速的数据交换格式和基于功能的RPC系统.
* [caffeine](https://github.com/ben-manes/caffeine) -  Java 8的高性能缓存库.
* [Chronicle-Bytes](https://github.com/OpenHFT/Chronicle-Bytes) - 低级内存访问包装器.
* [Chronicle-Queue](https://github.com/OpenHFT/Chronicle-Queue) - 微秒存储，将所有内容存储到磁盘.
* [Chronicle-Map](https://github.com/OpenHFT/Chronicle-Map) - 为低延迟和/或多进程应用程序设计的内存中键值存储.
* [clj-ds](https://github.com/krukow/clj-ds) -  Clojure的数据结构被修改为在Clojure之外使用.
* [colfer](https://github.com/pascaldekloe/colfer) - 二进制序列化格式和类生成器.
* [commons-math](http://commons.apache.org/proper/commons-math) - 轻量级，独立的数学和统计组件库.
* [CuckooFilter4J](https://github.com/MGunlogson/CuckooFilter4J) -  Bloom过滤器替换近似集合成员资格查询.
* [cyclops](https://github.com/aol/cyclops) - 用于RxJava，Reactor，FunctionalJava，Guava和Javascript的集成模块.
* [Eclipse Collections](https://github.com/eclipse/eclipse-collections) -  Java的集合框架.
* [externalsortinginjava](https://github.com/lemire/externalsortinginjava) - 使用多核和外部存储器算法对非常大的文件进行排序.
* [failsafe](https://github.com/jhalterman/failsafe) - 用于处理故障的轻量级零依赖库.
* [fasttuple](https://github.com/boundary/fasttuple) - 在堆内和堆外内存中相邻布局的集合.
* [fast-uuid](https://github.com/jchambers/fast-uuid) - 用于快速有效地解析和编写UUID的Java库.
* [FlatBuffers](http://google.github.io/flatbuffers/) - Efficient cross platform serialization library for C++, C#, Go, Java, JavaScript, PHP, and Python.
* [geohash](https://github.com/davidmoten/geo) - 用于geohashing的Java实用程序方法.
* [gs-collections](https://github.com/goldmansachs/gs-collections) - 高盛集合框架.
* [hollow](https://github.com/Netflix/hollow) - 用于利用小到中等大小的内存数据集的Java库和综合工具集.
* [high-scale-lib](https://github.com/boundary/high-scale-lib) -  Cliff Click的高级图书馆.
* [hppc](https://github.com/carrotsearch/hppc) - 高性能原始集合.
* [injector](https://github.com/belliottsmith/injector) - 一个新的Java Executor.
* [java-concurrent-hash-trie-map](https://github.com/romix/java-concurrent-hash-trie-map) - 来自Scala集合的并发trie哈希映射实现的Java端口.
* [java-hll](https://github.com/aggregateknowledge/java-hll) - Java library for the HyperLogLog algorithm.
* [JavaFastPFOR](https://github.com/lemire/JavaFastPFOR) - 库可以非常快速地压缩和解压缩整数数组.
* [java-string-similarity](https://github.com/tdebatty/java-string-similarity) - 字符串相似度和距离度量，包括Levenshtein编辑距离和sibbling，Jaro-Winkler，最长公共子序列，余弦相似度等.
* [JCTools](http://jctools.github.io/JCTools/) -  JDK目前​​缺少并发数据结构.
* [DSL-JSON](http://github.com/ngs-doo/dsl-json) - 具有高级编译时数据绑定的高性能JSON库.
* [jsoniter](http://jsoniter.com/) - 声称是有史以来最快的JSON解析器（DSL-JSON的副本）.
* [jOOL](https://github.com/jOOQ/jOOL) -  Java 8 lambdas的有用扩展.
* [Koloboke](https://github.com/OpenHFT/Koloboke) -  Java Collections直到内存和性能的最后一个痕迹.
* [LevelDB](https://github.com/dain/leveldb) - 用Java重写LevelDB（端口）.
* [lightweight_trie](https://github.com/bryanduxbury/lightweight_trie) - 一种非常节省内存的trie（基数树）实现.
* [lmdbjni](https://github.com/deephacks/lmdbjni) -  LMDB的Java API（HawtJNI），这是一个用C语言编写的超快速，超紧凑的键值嵌入式数据存储.
* [lmdbjava](https://github.com/lmdbjava/lmdbjava) - 用于LMDB的Java API（JNR），它是用C编写的超快速，超紧凑的键值嵌入式数据存储.
* [low-gc-membuffers](https://github.com/cowtowncoder/low-gc-membuffers) - 使用直接ByteBuffers的内存循环缓冲区，以最大限度地减少GC开销.
* [lwjgl3](https://github.com/LWJGL/lwjgl3) -  Java库，支持跨平台访问流行的本机API，可用于开发图形（OpenGL），音频（OpenAL）和并行计算（OpenCL）应用程序.
* [MapDB](http://www.mapdb.org) - 由堆外或磁盘存储支持的集合.
* [mph-table](https://github.com/indeedeng/mph-table) -  Minimal Perfect Hash Tables是一个不可变的键/值存储，具有高效的空间利用率和快速读取.
* [mug](https://google.github.io/mug/) - 源自Google的小型，零功能的util库. 
* [netty-buffers](http://netty.io/wiki/using-as-a-generic-library.html#wiki-h2-1) - 内存缓冲池实现类似于jemalloc.
* [ObjectLayout](http://objectlayout.org) - 布局优化的Java数据结构包.
* [ohc](https://github.com/snazy/ohc) - 为Apache Cassandra 3.0开发的Java大型堆缓存.
* [okio](https://github.com/square/okio) - 现代Java IO库，可以做出巧妙的事情来节省CPU和内存.
* [onyx-java](https://github.com/onyx-platform/onyx-java) - 通过为Onyx工作流的每个组件提供Java等效项来镜像Onyx Platform核心API.
* [parquet](https://parquet.apache.org/) - 使用Dremel文件中描述的记录粉碎和汇编算法的列式存储格式.
* [PauselessHashMap](https://github.com/giltene/PauselessHashMap) - 一个java.util.HashMap兼容的映射，在调整大小时不会停止放置或获取.
* [pcollections](https://github.com/hrldcpr/pcollections) - 持久Java集合库.
* [protobuf](https://developers.google.com/protocol-buffers) - 谷歌的数据交换格式.
* [Quasar](http://www.paralleluniverse.co/quasar/) -  JVM的轻量级线程和actor.
* [rtree](https://github.com/davidmoten/rtree) -  Java中具有反应式api的不可变内存中的R树和R * -tree实现.
* [RTree2D](https://github.com/Sizmek/rtree2d) -  RTree2D是一个2D不可变R树，具有STR（Sort-Tile-Recursive）打包，用于平面和球面上的超快速最近和交叉查询.
* [Reactive Streams](http://www.reactive-streams.org/) - 具有无阻塞背压的异步流处理标准.
* [Reactive Streams Utilities](https://github.com/lightbend/reactive-streams-utils) -  Reactive Streams的未来标准实用程序库.
* [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap) -  Java中更好的压缩位集.
* [rollinghashjava](https://github.com/lemire/rollinghashjava) - 在Java中滚动哈希函数.
* [Reactor](http://projectreactor.io/) -  JVM for Java，Groovy，Clojure等上的反应性数据应用程序.
* [RxJava](https://github.com/ReactiveX/RxJava) - 用于使用可观察序列组合异步和基于事件的程序的库.
* [SmoothieMap](https://github.com/OpenHFT/SmoothieMap) -  java.util.Map impl，最差put延迟比java.util.HashMap小100多倍.
* [Simple Binary Encoding](https://github.com/real-logic/simple-binary-encoding) - High Performance Message Codec.
* [splitmap](https://github.com/richardstartin/splitmap/) - 并行位图实现.
* [DataSketches](https://datasketches.github.io/) - 随机流算法的Java软件库.
* [stormpot](https://github.com/chrisvest/stormpot) -  JVM的快速对象池.
* [stream-lib](https://github.com/addthis/stream-lib) - 用于汇总流中数据的Java库，用于存储所有事件是不可行的.
* [streamvbyte](https://github.com/lemire/streamvbyte) - 使用StreamVByte编解码器在C中进行快速整数压缩.
* [TraneIO](http://trane.io/) -  Future抽象的高性能实现.
* [transducers-java](https://github.com/cognitect-labs/transducers-java) - 可组合的算法转换，独立于其输入和输出源的上下文.
* [VarInt](https://github.com/bazelbuild/bazel/blob/master/src/main/java/com/google/devtools/build/lib/util/VarInt.java) - 没有deps的No-deps变量int实现（由Bazel提供）.
* [vavr](http://www.vavr.io/) -  Java 8+功能库.
* [wire](https://github.com/square/wire) - 适用于Android和Java的简洁轻量级协议缓冲区.
* [Zero-Allocation-Hashing](https://github.com/OpenHFT/Zero-Allocation-Hashing) - 在Java中散列任何字节序列，包括各种原始数组，缓冲区，CharSequences等.

## Metaprogramming

*针对JVM的解析器，解释器，编译器和源代码生成.*

* [Antlr](http://www.antlr.org/) - 用于读取，处理，执行或翻译结构化文本或二进制文件的分析器生成器.
* [auto](https://github.com/google/auto) -  Java的源代码生成器集合.
* [Apache Calcite](http://calcite.apache.org/docs/) - 动态数据管理框架和SQL解析器插件.
* [Checker Framework](http://types.cs.washington.edu/checker-framework/) - 编译器插件，可以发现错误或验证其缺失.
* [compile-testing](https://github.com/google/compile-testing) -  javac和注释处理器的测试工具.
* [derive4j](https://github.com/derive4j/derive4j) - 代数数据类型构造函数，模式匹配，态射，光学和类型类.
* [error-prone](https://github.com/google/error-prone) - 将常见的Java错误作为编译时错误捕获.
* [GHCVM](https://github.com/rahulmutt/ghcvm) - 支持GHC Haskell的Haskell到JVM编译器.
* [Graal](http://openjdk.java.net/projects/graal/) - 与HotSpot虚拟机集成的新的Java实时即时编译器.
* [grappa](https://github.com/fge/grappa)   -  Parboiled的Java分支.  编写没有预处理阶段的语法.
* [immutables](http://immutables.github.io/) - 生成简单，安全且一致的值对象.
* [javacc](https://javacc.java.net/) - 用于Java的分析器生成器.
* [javaparser](https://github.com/javaparser/javaparser) - 用于Java的Java 1.8分析器和抽象语法树.
* [JavaPoet](https://github.com/square/javapoet) - 用于生成.java源文件的Java API.
* [jparsec](https://github.com/jparsec/jparsec) - 使用纯Java和Haskell Parsec构建迷你解析器.
* [JSweet](http://www.jsweet.org/) - 从Java到TypeScript / JavaScript的转换器.
* [MPS](https://www.jetbrains.com/mps/) - 设计和构建可扩展的DSL和编辑器.
* [lombok](https://projectlombok.org/) - 减少通常为Java类编写的样板代码量.
* [parboiled](https://github.com/sirthias/parboiled) - 基于解析表达式语法解析任意输入文本.
* [Sulong](https://github.com/graalvm/sulong) - 使用Truffle和Graal用Java编写的LLVM IR解释器.
* [TeaVM](https://github.com/konsoletyper/teavm) - 从Java字节码到JavaScript的提前翻译编译器（转换器）.
* [Truffle](https://github.com/graalvm/truffle) - 将语言实现为简单解释器的框架.
* [Xtext](https://eclipse.org/Xtext/) - 编程语言和DSL开发框架.

## Native

*互连JVM和本机代码* 

* [hawtjni](https://github.com/fusesource/hawtjni) - 基于Eclipse SWT中使用的JNI生成器的JNI代码生成器.
* [Java Grinder](https://github.com/mikeakohn/java_grinder) - 将Java字节码编译为微控制器组件.
* [j2v8](https://github.com/eclipsesource/j2v8) - 用于Google V8 JavaScript引擎的Java API.
* [JavaCPP](https://github.com/bytedeco/javacpp) -  JavaCPP提供对Java内部本机C ++的高效访问.
* [jnr-ffi](https://github.com/jnr/jnr-ffi) - 无需手动编写JNI代码即可加载本机库.
* [jssembly](https://github.com/dvx/jssembly) - 从Java执行本机程序集.
* [NuProcess](https://github.com/brettwooldridge/NuProcess) - 用于Java的低开销，非阻塞I / O，外部流程执行实现.
* [Project Panama](http://openjdk.java.net/projects/panama/) - 丰富C程序员使用的JVM和API之间的连接.

## Network

*用于网络编程，数据包捕获，监控，测试和弹性的工具.*

* [Aeron](https://github.com/real-logic/Aeron) - 高效可靠的UDP单播，UDP多播和IPC消息传输.
* [armeria](https://github.com/line/armeria) - 基于Java 8，Netty 4.1，HTTP / 2和Thrift构建的异步RPC / API客户端/服务器库.
* [Chronicle-Network](https://github.com/OpenHFT/Chronicle-Network) - 高性能网络库.
* [comcast](https://github.com/tylertreat/comcast) - 模拟糟糕的网络连接.
* [gor](https://github.com/buger/gor) - 实时HTTP流量重放.
* [gRPC](http://www.grpc.io/) - 高性能，开源，通用的RPC框架，将移动和HTTP / 2放在第一位.
* [jRT](https://github.com/LatencyUtils/jRT) - 测量java应用程序对基于套接字的请求的响应时间.
* [JXIO](https://github.com/accelio/JXIO) -  AccelIO上的Java API（C库），一种针对硬件加速优化的高性能异步可靠消息传递和RPC库.
* [K3PO](https://github.com/k3po/k3po) - 创建任意网络流量和行为，以验证网络端点是否正常运行.
* [muxy](https://github.com/mefellows/muxy) - 模拟真实的分布式系统故障.
* [Netty](http://netty.io/) - 用于高性能协议服务器和客户端的异步事件驱动网络库.
* [okhttp](https://github.com/square/okhttp) - 适用于Android和Java应用程序的HTTP + HTTP / 2客户端.
* [one-nio](https://github.com/odnoklassniki/one-nio) - 用于构建高性能Java服务器的库.
* [proteus-java](https://github.com/netifi-proteus/proteus-java) - 基于RSocket的Proteus Java Client.
* [reactive-grpc](https://github.com/salesforce/reactive-grpc) - 反应性gRPC是一套用于将gRPC与Reactive Streams编程库一起使用的库.
* [RSocket](http://rsocket.io/) -  RSocket是一种二进制协议，用于字节流传输，如TCP，WebSockets和Aeron.
* [SimianArmy](https://github.com/Netflix/SimianArmy) - 弹性工具，有助于确保您的应用程序可以容忍随机实例故障.
* [pcap4j](https://github.com/kaitoy/pcap4j) - 使用libpcap捕获，制作和发送数据包的Java库.
* [pig](https://github.com/rafael-santiago/pig) -  Linux数据包制作工具.
* [tcpdump](http://www.tcpdump.org/) - 用于网络流量捕获的数据包分析器
* [tcpflow](https://github.com/simsong/tcpflow) - 以便于协议分析和调试的方式捕获TCP连接流.
* [tcpreplay](https://github.com/appneta/tcpreplay) -  Pcap编辑和重播工具.

## Nix tools

*分析JVM和与主机环境交互时有用的* nix工具*
* [atoptool](http://www.atoptool.nl/) - 记录系统和过程活动以进行长期分析，突出显示过载系统.
* [bcc](https://github.com/iovisor/bcc) - 基于BPF的Linux IO分析，网络，监控等工具.
* [Flame Graphs](http://www.brendangregg.com/flamegraphs.html) - 可视化的配置软件，允许快速准确地识别最频繁的代码路径.
* [ioping](https://github.com/koct9i/ioping) - 简单的磁盘I / 0延迟测量工具.
* [javap](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/javap.html) - 将类文件反汇编为反映java字节码的代码.
* [jhat](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/jhat.html) -  Java堆分析工具
* [jhsdb](https://docs.oracle.com/javase/9/tools/jhsdb.htm) - 启动postmortem调试器以分析崩溃的JVM中的核心转储内容.
* [jinfo](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/jinfo.html) - 打印给定进程的配置信息.
* [jstack](http://docs.oracle.com/javase/8/docs/technotes/tools/unix/jstack.html) - 为给定的Java进程打印线程的堆栈跟踪.
* [jstat](https://docs.oracle.com/javase/8/docs/technotes/tools/unix/jstat.html) - 监视JVM中的GC和编译器统计信息.
* [hwloc](http://linux.die.net/man/7/hwloc) - 报告处理器的结构，核心数，超线程和高速缓存大小.
* [likwid](https://github.com/RRZE-HPC/likwid) - 读取Intel和AMD处理器上的硬件性能计数器.
* [numactl](http://linux.die.net/man/8/numactl) - 控制进程或共享内存的NUMA策略.
* [oprofile](http://oprofile.sourceforge.net/news/) - 系统范围的硬件性能监控，易于使用的接口，开销低.
* [perf](https://perf.wiki.kernel.org/index.php/Main_Page) - 使用性能计数器进行Linux分析.
* [perf-tools](https://github.com/brendangregg/perf-tools) - 基于Linux perf_events（aka perf）和ftrace的性能分析工具.
* [sysdig](http://www.sysdig.org/) - 从正在运行的Linux实例捕获系统状态和活动，然后保存，过滤和分析.
* [sysstat](http://sebastien.godard.pagesperso-orange.fr) -  Linux的性能监视工具.
* [taskset/process-affinity](https://www.glennklockwood.com/hpc-howtos/process-affinity.html) - 检索或设置进程的CPU亲和性.
* [tiptop](http://tiptop.gforge.inria.fr/) - 像顶部一样，但也显示每个周期的指令（IPC）.

## Profilers

*提供分析和跟踪信息以帮助程序优化的工具*

* [allocation-instrumenter](https://github.com/google/allocation-instrumenter) - 将字节码重写为仪器分配站点的Java代理.
* [aprof](https://github.com/Devexperts/aprof) -  Java内存分配分析器.
* [async-profiler](https://github.com/jvm-profiling-tools/async-profiler) - 采用AsyncGetCallTrace + perf_events的Java采样CPU探测器.
* [BTrace](https://github.com/jbachorik/btrace) -  Java平台的安全动态跟踪工具.
* [Byteman](http://byteman.jboss.org/) - 用于Java的跟踪，监视和测试工具
* [bytestacks](https://github.com/cl4es/bytestacks) - 将JVM字节码执行转换为火焰图. 
* [Chronon](http://chrononsystems.com)   - 记录整个java程序.  在任何机器上重播.
* [GCeasy](http://gceasy.io/)   - 机器学习指导垃圾收集日志分析工具.  自动检测JVM GC日志中的问题并为其推荐解决方案.
* [GCViewer](https://github.com/chewiebug/GCViewer) -  GCViewer是一个可视化详细GC输出的工具.
* [grav](https://github.com/epickrram/grav) - 一组帮助可视化流程执行的工具.
* [hawkshaw](https://github.com/jClarity/hawkshaw) - 用于跟踪内存/ JVM问题并生成可预测的VM行为的工具.
* [HdrHistogram](http://hdrhistogram.github.io/HdrHistogram/) - 支持记录和分析采样数据值计数的直方图.
* [hdrhistogram-metrics-reservoir](https://bitbucket.org/marshallpierce/hdrhistogram-metrics-reservoir) - 由HdrHistogram支持的度量水库实施.
* [HdrLogProcessing](https://github.com/nitsanw/HdrLogProcessing) - 用于HDR直方图日志操作的实用程序.
* [heapster](https://github.com/mariusae/heapster) -  JVM的生产堆分析.
* [honest-profiler](https://github.com/RichardWarburton/honest-profiler) - 在没有安全点样本偏差的情况下采样JVM分析器.
* [jamm](https://github.com/jbellis/jamm) - 测量实际对象内存使用情况，包括JVM开销.
* [Java Flight Recorder (JFR)](http://www.oracle.com/technetwork/java/javaseproducts/mission-control/java-mission-control-1998576.html) - 用于收集有关正在运行的Java应用程序的诊断和分析数据的工具，几乎没有性能开销.
* [java-sizeof](https://github.com/dweiss/java-sizeof) -  Java的内存消耗估算器.
* [jcstress](http://openjdk.java.net/projects/code-tools/jcstress/) - 实验性工具和测试，以帮助研究JVM，类库和硬件中的并发支持的正确性.
* [jfr-flame-graph](https://github.com/chrishantha/jfr-flame-graph) - 将JFR方法分析样本转换为FlameGraph兼容格式.
* [jfr-report-tool](https://github.com/lhotari/jfr-report-tool) - 用于从Java Flight Recorder转储创建报告的工具.
* [jitwatch](https://github.com/AdoptOpenJDK/jitwatch) - 日志分析/可视化Java HotSpot JIT编译.
* [jitwatch-intellij](https://github.com/yole/jitwatch-intellij) -  IntelliJ IDEA的JITWatch插件.
* [jHiccup](http://www.azul.com/jhiccup/) -  jHiccup是一个开源工具，旨在测量与应用程序底层Java运行时平台相关的暂停和停顿.
* [jmh](http://openjdk.java.net/projects/code-tools/jmh/) - 用Java和其他语言编写的针对JVM的微基准测试.
* [jmh-compare-gui](https://github.com/akarnokd/jmh-compare-gui) - 用于比较JMH结果的GUI.
* [JOL](http://openjdk.java.net/projects/code-tools/jol/) - Analyze actual object layout schemes, footprint, and references in JVMs.
* [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html) - 帮助解决性能瓶颈，确定内存泄漏并了解线程问题.
* [JVMTI](https://docs.oracle.com/javase/8/docs/technotes/guides/jvmti/) - 提供本机API以检查状态并控制在JVM中运行的应用程序的执行.
* [jvmtop](https://github.com/patric-r/jvmtop) - 轻量级控制台应用程序，以最顶级的方式监视机器上运行的jvms.
* [jvm-profiler](https://github.com/uber-common/jvm-profiler) -  Java Agent以分布式方式收集Hadoop / Spark JVM进程的各种指标和堆栈跟踪.
* [MAT](https://eclipse.org/mat/) -  Java堆分析器，帮助查找内存泄漏并减少内存消耗.
* [leakcanary](https://github.com/square/leakcanary) - 适用于Android和Java的内存泄漏检测库.
* [metrics](http://metrics.dropwizard.io/) - 测量生产环境中关键组件的行为.
* [micrometer](https://github.com/micrometer-metrics/micrometer) - 最流行的监控工具的应用程序指标外观.
* [osquery](https://osquery.io/) -  osquery是一个将操作系统公开为高性能关系数据库的工具框架.
* [Overseer](http://www.peternier.com/projects/overseer/overseer.php) -  Java的低级硬件监控和管理.
* [OpenTracing](http://opentracing.io/) - 分布式跟踪的供应商中立开放标准.
* [perf-map-agent](https://github.com/jrudolph/perf-map-agent) - 生成方法映射以与linux`per`工具一起使用.
* [perfj](https://github.com/coderplay/perfj) - 针对java程序的Linux perf.
* [polarbear](https://github.com/Cue/polarbear) - 帮助诊断OutOfMemoryError条件的工具.
* [Riemann JVM Profiler](https://github.com/riemann/riemann-jvm-profiler) -  JVM代理，它将功能级分析器遥测发送到Riemann服务器进行分析，可视化和存储.
* [statsd-jvm-profiler](https://github.com/etsy/statsd-jvm-profiler) - 将分析数据发送到StatsD的JVM代理分析器.
* [Swiss Java Knife](https://github.com/aragozin/jvm-tools) - 用于JVM故障排除，监控和分析的小型工具集.
* [Takipi](https://www.takipi.com/) - 告诉您代码在生产中何时以及为何中断.
* [Tracer](https://github.com/zalando/tracer) - 管理自定义跟踪标识符并通过分布式系统进行管理.
* [YourKit](https://www.yourkit.com/) - 功能齐全，易于使用，低架构探测器.
* [Zipkin](https://github.com/openzipkin/zipkin) - 分布式跟踪系统收集Twitter开发的不同服务的时间数据.


## Runtimes

*用于管理jvm运行时进程的工具*
* [Capsule](https://github.com/puniverse/capsule) - 针对JVM应用程序的简单打包和部署.
* [CRaSH](http://www.crashub.org/) -  Java平台的shell.
* [Drip](https://github.com/ninjudd/drip) - 快速启动JVM，无需持久JVM的麻烦.
* [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent) - 在运行时重新定义类并跳过重新部署过程.
* [jvmkill](https://github.com/airlift/jvmkill) - 无法分配内存或创建线程时强制终止JVM的代理.
* [Nailgun](http://martiansoftware.com/nailgun/) -  Nailgun是一个客户端，协议和服务器，用于从命令行运行Java程序，而不会产生JVM启动开销.

## Virtual Machines

*实现JVM规范或部分规范的虚拟机.*
* [Avian](https://github.com/ReadyTalk/avian) - 轻量级，高度可移植的JVM，可选择AOT编译.
* [Dalvik](https://source.android.com/devices/tech/dalvik/) -  Android运行时（ART）是Android上的应用程序和某些系统服务使用的托管运行时.
* [DCEVM](http://dcevm.github.io) - 修改Java HotSwap VM，无限制地支持在运行时重新加载类.
* [HotSpot](http://openjdk.java.net/groups/hotspot/) -  Oracle Corporation维护和分发的HotSpot虚拟机.
* [IBM J9](http://www.ibm.com/developerworks/java/jdk/) - 由IBM开发的JVM.
* [Eclipse OpenJ9](https://github.com/eclipse/openj9) -  Eclipse OpenJ9.
* [J2ObjC](https://github.com/google/j2objc)   - 从Java源代码到Objective-C代码的转换器.  在iOS原生应用和Android原生应用之间保留共享代码. 
* [jvm.go](https://github.com/zxh0/jvm.go) - 用Go编写的JVM.
* [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm)   - 用于iOS本机开发的C源转换器的开源Java字节码.  设计作为一部分 [Codename One](https://www.codenameone.com/) WORA为移动项目.
* [MobiDevelop's RoboVM Fork](https://github.com/MobiVM/robovm) - 提前针对iOS，Mac OSX和Linux的JVM字节码编译器.
* [Zing](https://www.azul.com/products/zing/) - 唯一可以消除大型堆大小的Java垃圾收集暂停的JVM.
* [Zulu](https://www.azul.com/products/zulu/) - 唯一经过认证的OpenJDK多平台版本：免费，100％开源Java.

## Resources

## Documentation

*与JVM *相关的​​文档
* [TCP Tracepoints](http://www.brendangregg.com/blog/2018-03-22/tcp-tracepoints.html) Linux bcc / BPF使用Brendan Gregg的tcplife
* [Linux tracing workshop](https://github.com/goldshtn/linux-tracing-workshop) - 使用BPF进行JVM监控，示例和用于Linux跟踪工具研讨会的动手实验.
* [JVM Anatomy Park](https://shipilev.net/jvm-anatomy-park/) - 迷你帖系列，每个帖子都深入到AlekseyShipilёv的一个主题.
* [Coordinated Omission problem](https://groups.google.com/forum/#!msg/mechanical-sympathy/icNZJejUHfE/BfDekfBEs_sJ) - 关于机械同情的讨论.
* [False sharing](http://mechanical-sympathy.blogspot.se/2011/07/false-sharing.html)   - 在修改共享同一缓存行的独立变量时，线程会影响彼此的性能.  马丁汤普森
* [The JVM specification](https://docs.oracle.com/javase/specs/jvms/se8/jvms8.pdf) -  Java虚拟
机器规格Java SE 8版.
* [The Java Memory Model](http://www.cs.umd.edu/~pugh/java/memoryModel/) - 有关Java内存模型的讨论和信息的起点.
* [The JSR-133 Cookbook for Compiler Writers](http://gee.cs.oswego.edu/dl/jmm/cookbook.html) - 实现JSR-133指定的新Java内存模型（JMM）的非官方指南.
* [Garbage Collection Tuning Guide](http://docs.oracle.com/javase/8/docs/technotes/guides/vm/gctuning/) -  HotSpot虚拟机垃圾收集调整指南.
* [Safepoints](http://psy-lob-saw.blogspot.se/2014/03/where-is-my-safepoint.html)   - 我的安全点在哪里？  Nitsan Wakart.
* [Topics in High-Performance Messaging](https://www.informatica.com/downloads/1568_high_perf_messaging_wp/Topics-in-High-Performance-Messaging.htm) - 高性能消息传递系统中解释的设计决策，经验和约束.
* [Top 10 Performance Mistakes](http://www.infoq.com/articles/top-10-performance-mistakes) -  Martin Thompson在制作中看到的十大与业绩相关的错误摘要.
* [The USE method](http://www.brendangregg.com/usemethod.html)   - 利用率饱和度和误差（USE）方法是一种分析任何系统性能的方法.  布兰登格雷格
* [An introduction to distributed systems](https://github.com/aphyr/distsys-class) - 凯尔金斯伯里（杰普森的作者）.
* [Using JDK 9 Memory Order Modes](http://gee.cs.oswego.edu/dl/html/j9mm.html) - 对于熟悉Java并发的专业程序员，但不熟悉VarHandles提供的JDK 9中可用的内存顺序模式.
* [CPU Utilization is Wrong](http://www.brendangregg.com/blog/2017-05-09/cpu-utilization-is-wrong.html)   - 测量每个周期的指令（IPC）以获得CPU利用率.  布兰登格雷格
* [Linux Load Averages: Solving the Mystery](http://www.brendangregg.com/blog/2017-08-08/linux-load-averages.html) - 布兰登格雷格
* [What every programmer should know about solid-state drives](http://codecapsule.com/2014/02/12/coding-for-ssds-part-6-a-summary-what-every-programmer-should-know-about-solid-state-drives/) -  Emmanuel Goossaert.
* [Quick Tips for Fast Code on the JVM](https://gist.github.com/djspiewak/464c11307cabc80171c90397d4ec34ef) -  Daniel Spiewak.
## Communities

*积极讨论.*

* [concurrency-interest](http://altair.cs.oswego.edu/mailman/listinfo/concurrency-interest) -  JSR-166的讨论列表.
* [hotspot-compiler-dev](http://mail.openjdk.java.net/mailman/listinfo/hotspot-compiler-dev) - 关于HotSpot字节码编译器开发的技术讨论.
* [hotspot-dev](http://mail.openjdk.java.net/mailman/listinfo/hotspot-dev) -  HotSpot开发邮件列表.
* [hotspot-gc-dev](http://mail.openjdk.java.net/mailman/listinfo/hotspot-gc-dev) - 关于HotSpot垃圾收集器开发的技术讨论.
* [mechanical-sympathy](https://groups.google.com/forum/#!forum/mechanical-sympathy) - 讨论如何以同情的方式编码并测量底层堆栈/平台，以便提取出良好的性能.
* [Performance Java User's Group](https://plus.google.com/u/0/communities/107178245817384004088/) - 对于希望将系统推向新水平的专业Java *开发人员*
* [Virtual Machine Meetup 2017](http://vmmeetup.github.io/2017/) - 讨论托管语言执行领域的最新研究和发展的场所. 

## Media

*与JVM相关的视频，播客和其他媒体*
* [FOSDEM 2018](https://fosdem.org/2018/schedule/track/free_java/) -  FOSDEM 2018免费Java开发室.
* [JFokus 2018](https://www.youtube.com/playlist?list=PL2ekzZZrxVUkhrcMKuPMbiKoghc777plr)   -  GC版.  Shenandoah，ZGC，Zing，Fibers，Falcon等
* [G1 Garbage Collector in Java 8/9](http://nighthacking.com/g1-gc-with-kirk-pepperdine/) - 柯克佩珀代因.
* [Extreme Profiling: Digging Into Hotspots](https://youtu.be/7PkkxDaFDj8?list=PLKuh52zVrL6l6jzeSwNce77yLdfKmHAgD) -  Nitsan Wakart.
* [Java vs. C Performance](http://www.infoq.com/presentations/java-vs-c-performance) - 悬崖点击.
* [Why JNI is slow?](https://www.youtube.com/watch?v=LoyBTqkSkZk) - 悬崖点击
* [A Crash Course in Modern Hardware](https://www.youtube.com/watch?v=OFgxAFdxYAQ) - 悬崖点击
* [Java Profiling from the Ground Up](https://www.youtube.com/watch?v=_6vJyciXkwo) -  Nitsan Wakart.
* [The Illusion of Execution](https://www.youtube.com/watch?v=3g9R-RVIkOE) -  Nitsan Wakart.
* [Mythbusting Modern Hardware to Gain 'Mechanical Sympathy'](https://www.youtube.com/watch?v=MC1EKLQ2Wmg) - 马丁汤普森
* [Designing for Performance](https://www.youtube.com/watch?v=fDGWWpHlzvw) - 马丁汤普森
* [How NOT to Measure Latency](https://www.youtube.com/watch?v=lJ8ydIuPFeU) -  Gil Tene.
* [JVM Language Summit 2015](http://openjdk.java.net/projects/mlvm/jvmlangsummit/) -  2015年JVM语言峰会.
* [JVM Language Summit 2016](https://www.youtube.com/playlist?list=PLX8CzqL3ArzUY6rQAQTwI_jKvqJxrRrP_) -  2016年JVM语言峰会.
* [JVM Language Summit 2017](https://www.youtube.com/playlist?list=PLX8CzqL3ArzXJ2EGftrmz4SzS6NRr6p2n) - JVM Language Summit 2017.
* [Bits of advice for VM writers](https://www.youtube.com/watch?v=vzzABBxo44g) - 悬崖点击.
* [Understanding Java garbage collection ...](https://www.youtube.com/watch?v=_e5hujoTkgY) -  Gil Tene.
* [Faster Object Arrays](https://www.youtube.com/watch?v=bZuPTCaciLU) -  GOTO会议上的Gil Tene.
* [Java Memory Model Pragmatics](https://www.youtube.com/watch?v=TxqsKzxyySo) -  Aleksey Shipilev.
* [With GC Solved, What Else Makes a JVM Pause?](https://www.youtube.com/watch?v=Y39kllzX1P8) -  John Cuthbertson
* [JVM Mechanics](https://vimeo.com/120533011) - 道格拉斯霍金斯.
* [Give me 15 minutes and I'll change your view of Linux tracing](https://www.youtube.com/watch?v=GsMs3n8CB6g) - 布兰登格雷格
* [Kernel Recipes 2017: Performance Analysis with BPF](https://www.slideshare.net/brendangregg/kernel-recipes-2017-performance-analysis-with-bpf) - 布兰登格雷格
* [Shenandoah deep talk](https://shipilev.net/talks/vmm-Sep2017-shenandoah.pdf) - AlekseyShipilëv在2017年虚拟机大会上略微超过平常的Shenandoah演讲.
* [Shenandoah: The Garbage Collector That Could](https://www.youtube.com/watch?v=VCeHkcwfF9Q) -  Aleksey Shipilev  -  Devoxx 2017/11
* [Analyzing and Debugging the Java HotSpot VM at the OS Level](https://www.youtube.com/watch?v=k7IX_diKCEo) -  Volker Simonis.
* [Cliff Click podcast 2017/09/16](http://www.cliffc.org/blog/2017/09/16/programming-and-performance-intro/) - 编程和性能介绍.
* [Cliff Click podcast 2017/09/16](http://www.cliffc.org/blog/2017/09/16/of-bugs-and-coding-styles/) - 错误和编码样式.
* [Cliff Click podcast 2017/09/18](http://www.cliffc.org/blog/2017/09/18/java-vs-cc-the-podcast/) -  Java vs C / C ++.
* [Cliff Click podcast 2017/09/21](http://www.cliffc.org/blog/2017/09/21/debugging-data-races/) - 调试数据竞争.
* [Cliff Click podcast 2017/09/24](http://www.cliffc.org/blog/2017/09/24/fast-bytecodes-for-funny-languages/) - 有趣语言的快速字节码.
* [Cliff Click podcast 2017/09/28](http://www.cliffc.org/blog/2017/09/28/struct-of-arrays-vs-array-of-structs/) - 阵列结构与结构数组.
* [Cliff Click podcast 2017/10/04](http://www.cliffc.org/blog/2017/10/04/the-3-hardest-problems-in-programming/) - 编程中最难的三个问题.
* [Cliff Click podcast 2017/11/05](http://cliffc.org/blog/2017/11/05/modern-hardware-performance-cache-lines/) - 现代硬件性能和缓存线.
* [Cliff Click podcast 2017/11/09](http://cliffc.org/blog/2017/11/09/queuing-in-practice/) - 在实践中排队.
* [Which technique do programming language parsers and interpreters use?](https://www.quora.com/Which-technique-do-programming-language-parsers-and-interpreters-use/answer/Cliff-Click-1?srid=dZAx) - 悬崖点击.
* [Everything about Stack Traces and Heap Dumps](https://vimeo.com/233820012) -  Andrei Pangin
* [Fast and safe production monitoring of JVM with BPF tools](http://s.sashag.net/velny17-jvm) -  Sasha Goldshtein.
* [The Future of the Linux Page Cache](https://www.youtube.com/watch?time_continue=1&v=xxWaa-lPR-8) - 马修威尔考克斯

## People

*分享来自JVM内部工作的来之不易的，通常无证的知识和数据的人*
* [Aleksey Shipilëv](http://shipilev.net/) - 开发Oracle / Open JDK / Hotspot和其他与Java相关的技术.
* [Andrey Breslav](https://twitter.com/abreslav) -  Kotlin @ JetBrains的首席语言设计师.
* [Brian Goetz](https://twitter.com/BrianGoetz) -  Oracle的Java语言架构师.
* [Ben Christensen](https://twitter.com/benjchristensen) -  Facebook，Netflix，Apple工程.
* [Brendan Gregg](http://www.brendangregg.com) - 云性能，内核工程师，演讲者，作者.
* [Charles Nutter](https://twitter.com/headius) -  JRuby的家伙.
* [Claes Redestad](https://twitter.com/cl4es) - 使用OpenJDK的东西@ Oracle.
* [Cliff Click](http://www.cliffc.org/blog/) -  HotSpot服务器编译器的创建者.
* [Dave Dice](https://blogs.oracle.com/dave/) -  Oracle内可扩展同步研究小组的高级研究员.
* [Dávid Karnok](http://akarnokd.blogspot.se/) - 关于高级RxJava博客的RxJava提交者.
* [Doug Lea](http://g.oswego.edu/) -  Java内存模型的作者.
* [Gil Tene](https://twitter.com/giltene) -  Azul Systems.
* [Heinz Kabutz](https://twitter.com/heinzkabutz) -  250多位Java专家通讯的作者.
* [Ivan Krylov](https://twitter.com/JohnWings) -  JVM专家.
* [Jake Wharton](https://twitter.com/JakeWharton) -  Square，谷歌，开源黑客.
* [John Rose](https://blogs.oracle.com/jrose/) -  HotSpot开发人员.
* [Jonas Bonér](https://twitter.com/jboner) -  Lightbend的创始人兼首席技术官.
* [Lukas Eder](https://twitter.com/lukaseder)   -  Blogger.  JOOQ的作者.
* [Marcus Lagergren](https://twitter.com/lagergren) -  Java语言团队的校友.
* [Mark Reinhold](https://twitter.com/mreinhold) -  Java平台组首席架构师，Oracle.
* [Martin Thompson](http://mechanical-sympathy.blogspot.se/) -  Pasty面对表演黑帮.
* [Martijn Verburg](https://twitter.com/karianna) -  Java冠军.
* [Kirk Pepperdine](https://twitter.com/javaperftuning) - 从事高性能和分布式计算近20年.
* [Nitsan Wakart](http://psy-lob-saw.blogspot.se/2014/03/where-is-my-safepoint.html) -  Azul Systems.
* [Norman Maurer](https://twitter.com/normanmaurer) -  Netty开发者.
* [Paul Phillips](https://twitter.com/contrarivariant) - 永远无可争议的SLOC Scala编译器开发.
* [Per Liden](https://twitter.com/perliden) - 在Oracle上攻击HotSpot JVM.
* [Peter Lawrey](https://twitter.com/PeterLawrey) - 高性能Java系统的创新开发人员，以获得竞争优势.
* [Rafael Winterhalter](https://twitter.com/rafaelcodes) -  ByteBuddy的作者.
* [Richard Warburton](https://twitter.com/RichardWarburto) - 开发人员，演讲者，作者.
* [Richard Startin](http://richardstartin.uk/) - 性能分析师，开发人员，博主.
* [Ron Pressler](https://twitter.com/pressron)  - 平行宇宙.  JVM的主要光纤和延续.
* [Stephen Colebourne](https://twitter.com/jodastephen)   -  Java冠军.  偶尔的博主和演讲者.  以Joda项目和JSR-310而闻名.
* [Todd L. Montgomery](https://twitter.com/toddlmontgomery) - 前任首席技术官，前NASA研究员，网络极客，消息中间件设计师.
* [Stéphane Maldini](https://twitter.com/smaldini) -  Project Reactor Lead @Pivotal.
* [Stuart Marks](https://twitter.com/stuartmarks)   -  Deprecator医生.  Java / JDK / OpenJDK开发人员 
* [Vladimir Ivanov](https://twitter.com/iwan0www) - 黑客HotSpot JVM @ Oracle.
* [Viktor Klang](https://twitter.com/viktorklang) -  Typesafe Inc.的副首席技术官


## Contributing

贡献非常欢迎！

请看看 [contributing.md](https://github.com/deephacks/awesome-jvm/blob/master/contributing.md) 指导方针.
