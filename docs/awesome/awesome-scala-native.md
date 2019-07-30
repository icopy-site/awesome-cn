<div class="github-widget" data-repo="tindzk/awesome-scala-native"></div>
## Awesome Scala Native [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href="http://www.scala-native.org/"><img alt="Scala Native" align="right" width="250" height="250" src="https://raw.githubusercontent.com/tindzk/awesome-scala-native/master/logo.png"></a>

[Scala Native](http://www.scala-native.org/) 是一个优化的提前编译器 [Scala programming language](https://www.scala-lang.org/) .  传统上，虚拟机， [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine) ，是运行Scala程序所必需的.  Scala Native点击编译器发出 [LLVM intermediate representation](http://llvm.org/docs/LangRef.html)  而不是JVM字节码.  然后， [LLVM](http://llvm.org/)  编译器基础结构用于生成本机库和可执行文件.  鉴于Scala Native可执行文件是独立程序，它们通常具有较短的启动时间和较低的内存消耗.  这开辟了部署Scala程序的新途径，以前虚拟机将成为限制因素.  例如，开发人员可以为命令行或嵌入式设备编写程序.


## Tutorials and Examples
* [Giter8 template for a minimal Scala Native project](https://github.com/scala-native/scala-native.g8) - 官方 [Giter8](http://www.foundweekends.org/giter8/) 最小的Scala Native项目的模板.
* [Hands on Scala Native](https://github.com/MasseGuillaume/hands-on-scala-native) - 使用Ncurses实现带宽监视器的教程.
* [Starter for Scala Native](https://github.com/GnaneshKunal/scala-native-starter) - 链接到自定义C库的Scala Native项目.
* [Building C code using sbt-jni](https://github.com/nadavwr/scala-native-sbt-jni-example) - 使用编译Scala Native项目中的C代码的示例 [sbt-jni](https://github.com/jodersky/sbt-jni).
* [Example project with external dependencies](https://github.com/lihaoyi/scala-native-example-app) - 使用外部依赖项生成HTML并运行测试套件的示例项目.
* [Starter for Gtk+ Projects](https://github.com/jokade/scalanative-gtk-seed.g8) - [Giter8](http://www.foundweekends.org/giter8/) 使用的Scala Native GUI项目模板 [Gtk+](https://developer.gnome.org/gtk3/stable/index.html).

## Build Tools
* [sbt](https://www.scala-sbt.org/) -  Scala的标准构建工具.
* [Mill](https://github.com/lihaoyi/mill) - 构建工具力求简单，灵感来自 [Bazel](https://www.bazel.build/).
* [Bloop](https://github.com/scalacenter/bloop) -  Scala构建服务器和命令行工具，用于快速开发人员工作流程.
* [Seed](https://github.com/tindzk/seed)   - 基于Bloop的构建工具.  专注于用户体验和跨平台构建，受到启发 [Cargo](https://github.com/rust-lang/cargo).

## Functional Programming
* [Shapeless](https://github.com/milessabin/shapeless) - 通用编程库.
* [Squants](https://github.com/typelevel/squants) - 用于数量，测量单位和尺寸分析的DSL.
* [scalaz](https://github.com/scalaz/scalaz) - 键入数据结构的类和实例.
* [nobox](https://github.com/xuwei-k/nobox) - 不带拳击的不可变原始数组包装器.
* [PPrint](https://github.com/lihaoyi/PPrint) - 漂亮的打印值和类型.
* [SourceCode](https://github.com/lihaoyi/sourcecode) - 隐含在C中提供类似于`__LINE__`的元数据.
* [reactify](https://github.com/outr/reactify) -  Scala的功能反应式编程框架.
* [chimney](https://github.com/scalalandio/chimney) - 无Boilerplate的数据转换.

## Unit Tests
* [utest](https://github.com/lihaoyi/utest) - 用于单元测试的库.
* [minitest](https://github.com/monix/minitest) - 轻量级测试库.
* [scalaprops](https://github.com/scalaprops/scalaprops) - 基于财产的测试库.
  * [scalaprops-shapeless](https://github.com/scalaprops/scalaprops-shapeless) - 生成任意ADT实例.
  * [scalaprops-cross-example](https://github.com/scalaprops/scalaprops-cross-example) - 跨平台示例.
* [Makeshift](https://github.com/nadavwr/makeshift) - 用于单元测试的库.

## Bindings
* [cmark](https://github.com/sparsetech/cmark-scala) - 绑定 [cmark](https://github.com/commonmark/cmark) CommonMark解析器库.
* [libuv](https://github.com/TimothyKlim/scala-native-libuv) - 绑定 [libuv](https://github.com/libuv/libuv)，一个异步I / O库.
* [SDL2 和 OpenGL](https://github.com/regb/scalanative-graphics-bindings) - 图形框架的绑定 [SDL2](https://www.libsdl.org/) 和 [OpenGL](https://www.opengl.org/).
* [Cocoa](https://github.com/jokade/scalanative-cocoa) -  macOS图形框架的绑定 [Cocoa](https://en.wikipedia.org/wiki/Cocoa_(API)).
* [GNU Scientific Library](https://github.com/ruivieira/scala-gsl) - 绑定 [GNU Scientific Library (GSL)](https://www.gnu.org/software/gsl/).
* [BLAS](https://github.com/ekrich/scala-native-ml) - 绑定 [BLAS](http://www.netlib.org/blas/)，线性代数的库.
* [Gtk+](https://github.com/jokade/scalanative-gtk) - 绑定 [GTK+](https://www.gtk.org/) 图形工具包.
* [libsoup](https://github.com/jokade/scalanative-libsoup) - 绑定 [libsoup](https://wiki.gnome.org/Projects/libsoup) HTTP客户端/服务器库.
* [libui](https://github.com/lolgab/scalaui) - 基于GUI的GUI框架 [libui](https://github.com/andlabs/libui).
* [GStreamer](https://github.com/jokade/scalanative-gstreamer) - 绑定 [GStreamer](https://gstreamer.freedesktop.org) 多媒体框架.
* [Qt](https://github.com/jokade/scalanative-qt5) - 绑定 [Qt](https://www.qt.io).

## File Formats and Parsers
* [msgpack4z](https://github.com/msgpack4z/msgpack4z-native) - 实施 [MessagePack](https://msgpack.org/)，二进制序列化格式.
* [FastParse](https://github.com/lihaoyi/fastparse) - 用于定义和运行解析器的库.
* [scalatags](https://github.com/lihaoyi/scalatags) -  HTML / XML构造和渲染.
* [Pine](https://github.com/sparsetech/pine) -  HTML / XML解析，操作和渲染.
* [scala-json](https://github.com/MediaMath/scala-json) -  JSON解析器.
* [toml-scala](https://github.com/sparsetech/toml-scala) - [TOML](https://github.com/toml-lang/toml) 具有编解码器派生的解析器.
* [argonaut](https://github.com/argonaut-io/argonaut) - 纯功能的JSON解析器和库.
* [ScalaPB](https://github.com/scalapb/ScalaPB) - [Protocol Buffer](https://developers.google.com/protocol-buffers/) Scala的编译器.
  * [scalapb-argonaut](https://github.com/scalapb-json/scalapb-argonaut) - 基于ScalaPB的JSON和协议缓冲转换器 [Argonaut](http://argonaut.io/).
* [sconfig](https://github.com/ekrich/sconfig/) - [HOCON](https://github.com/ekrich/sconfig/blob/master/docs/original/HOCON.md) 解析器.

## Databases
* [JDBC](https://github.com/jokade/scalanative-jdbc) - 数据库访问层的端口 [JDBC](https://en.wikipedia.org/wiki/Java_Database_Connectivity) Scala Native.

## Web Development
* [Trail](https://github.com/sparsetech/trail) - 路由库.

## Logging
* [scribe](https://github.com/outr/scribe) - 快速简单的日志库.
* [slogging](https://github.com/jokade/slogging) - [Typesafe-logging](https://github.com/lightbend/scala-logging) 和 [SLF4J](https://www.slf4j.org/)兼容的基于宏的日志库.

## Console
* [fansi](https://github.com/lihaoyi/fansi) - 用于创建的库 [ANSI-coloured strings](https://en.wikipedia.org/wiki/ANSI_escape_code).
* [scopt](https://github.com/scopt/scopt) - 命令行参数解析器.
* [scala-optparse-applicative](https://github.com/xuwei-k/optparse-applicative) -  Haskell端口的CLI参数解析库 [optparse-applicative](https://hackage.haskell.org/package/optparse-applicative).
* [scallop](https://github.com/scallop/scallop) - 一个简单的Scala CLI解析库.

## Robotics
* [Potassium](https://github.com/Team846/potassium) - 编写机器人软件的框架.
* [WPILib](https://github.com/Team846/scala-native-wpilib) - 重新实现 [FIRST Robotics WPILib libraries](http://first.wpi.edu/FRC/roborio/release/docs/java/).

## Programs
* [sglgears](https://github.com/Milyardo/sglgears) -  GL港口 [gears.c](https://github.com/JoakimSoderberg/mesademos/blob/master/src/xdemos/glxgears.c).
* [k8s-cli](https://github.com/fsat/k8s-cli) - 用于生成的CLI工具 [Kubernetes](https://kubernetes.io/) 资源 [Akka](https://akka.io/), [Play Framework](https://www.playframework.com/) 和 [Lagom](https://www.lagomframework.com/)基于应用程序.
* [Coursier](https://github.com/coursier/coursier) -  Coursier&#39;s [`bootstrap` command](https://get-coursier.io/docs/cli-native-bootstrap) 生成原生发射器.

## Infrastructure
* [Seed Docker image](https://hub.docker.com/r/tindzk/seed/tags) - 用于跨平台构建的Docker镜像 [Seed](https://github.com/tindzk/seed).
* [scala-native-sbt-docker](https://github.com/ScalaWilliam/scala-native-sbt-docker) -  Scala Native和sbt的Docker镜像.

## Licence
<a rel="licence" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg" /><br />本作品采用<a rel="licence" href="http://creativecommons.org/licenses/by/4.0/">知识共享署名4.0国际许可协议授权</a> .
