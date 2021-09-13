<div class="github-widget" data-repo="tindzk/awesome-scala-native"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Scala Native [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href="http://www.scala-native.org/"><img alt="Scala Native" align="right" width="250" height="250" src="https://raw.githubusercontent.com/tindzk/awesome-scala-native/master/logo.png"></a>

[Scala Native](http://www.scala-native.org/) 是一个优化的提前编译器 [Scala programming language](https://www.scala-lang.org/) . 传统上，虚拟机， [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine) , 是运行 Scala 程序所必需的.  Scala Native 利用编译器来发出 [LLVM intermediate representation](http://llvm.org/docs/LangRef.html) 而不是 JVM 字节码. 然后，该 [LLVM](http://llvm.org/) 编译器基础结构用于生成本机库和可执行文件. 鉴于 Scala Native 可执行文件是独立程序，它们通常具有较短的启动时间和较低的内存消耗. 这开辟了部署 Scala 程序的新途径，而以前虚拟机是限制因素. 例如，开发人员可以为命令行或嵌入式设备编写程序.


## Tutorials and Examples
* [Giter8 template for a minimal Scala Native project](https://github.com/scala-native/scala-native.g8) - 官方 [Giter8](http://www.foundweekends.org/giter8/) 用于最小 Scala Native 项目的模板.
* [Hands on Scala Native](https://github.com/MasseGuillaume/hands-on-scala-native) - 使用 Ncurses 实现带宽监视器的教程.
* [Starter for Scala Native](https://github.com/GnaneshKunal/scala-native-starter) - 链接到自定义 C 库的 Scala 本机项目.
* [Building C code using sbt-jni](https://github.com/nadavwr/scala-native-sbt-jni-example) - 使用在 Scala Native 项目中编译 C 代码的示例 [sbt-jni](https://github.com/jodersky/sbt-jni).
* [Example project with external dependencies](https://github.com/lihaoyi/scala-native-example-app) - 使用外部依赖项生成 HTML 并运行测试套件的示例项目.
* [Starter for Gtk+ Projects](https://github.com/jokade/scalanative-gtk-seed.g8) - [Giter8](http://www.foundweekends.org/giter8/) Scala Native GUI 项目的模板使用 [Gtk+](https://developer.gnome.org/gtk3/stable/index.html).
* [Modern systems programming with scala native](https://pragprog.com/titles/rwscala/modern-systems-programming-with-scala-native/) 书.
* [Write a simple CLI application in Scala Native](https://github.com/ItoYo16u/prettytable-native)
## Build Tools
* [sbt](https://www.scala-sbt.org/) - Scala 的标准构建工具.
* [Mill](https://github.com/lihaoyi/mill) - 构建工具力求简单，灵感来自 [Bazel](https://www.bazel.build/).
* [Bloop](https://github.com/scalacenter/bloop) - 用于快速开发人员工作流程的 Scala 构建服务器和命令行工具.
* [Seed](https://github.com/tindzk/seed)  - 基于 Bloop 的构建工具. 专注于用户体验和跨平台构建，灵感来自 [Cargo](https://github.com/rust-lang/cargo).

## Functional Programming
* [Shapeless](https://github.com/milessabin/shapeless) - 通用编程库.
* [Squants](https://github.com/typelevel/squants) - 用于数量、测量单位和尺寸分析的 DSL.
* [scalaz](https://github.com/scalaz/scalaz) - 数据结构的类型类和实例.
* [nobox](https://github.com/xuwei-k/nobox) - 不可变的原始数组包装器，无需装箱.
* [PPrint](https://github.com/lihaoyi/PPrint) - 漂亮的打印值和类型.
* [SourceCode](https://github.com/lihaoyi/sourcecode) - 隐式提供类似于 C 中`__LINE__` 的元数据.
* [reactify](https://github.com/outr/reactify) - Scala 的函数式响应式编程框架.
* [chimney](https://github.com/scalalandio/chimney) - 无样板数据转换.
* [Quicklens](https://github.com/softwaremill/quicklens) - 修改深度嵌套的案例类字段.

## Unit Tests
* [µTest](https://github.com/lihaoyi/utest) - 单元测试库.
* [minitest](https://github.com/monix/minitest) - 轻量级测试库.
* [scalaprops](https://github.com/scalaprops/scalaprops) - 用于基于属性的测试的库.
  * [scalaprops-shapeless](https://github.com/scalaprops/scalaprops-shapeless) - 生成任意 ADT 实例.
  * [scalaprops-cross-example](https://github.com/scalaprops/scalaprops-cross-example) - 跨平台示例.
* [ScalaCheck](https://github.com/typelevel/scalacheck) - 基于属性的 Scala 测试.
* [ScalaTest](https://github.com/scalatest/scalatest) - 测试库.
* [specs2](https://github.com/etorreborre/specs2) - Scala 的软件规范.
* [Makeshift](https://github.com/nadavwr/makeshift) - 单元测试库.
* [MUnit](https://github.com/scalameta/munit) - 带有可操作错误和可扩展 API 的 Scala 测试库.

## Bindings
* [cmark](https://github.com/sparsetech/cmark-scala) - 绑定 [cmark](https://github.com/commonmark/cmark) CommonMark 解析器库.
* [libuv](https://github.com/TimothyKlim/scala-native-libuv) - 绑定 [libuv](https://github.com/libuv/libuv)，用于异步 I/O 的库.
* [SDL2 和 OpenGL](https://github.com/regb/scalanative-graphics-bindings) - 图形框架的绑定 [SDL2](https://www.libsdl.org/) 和 [OpenGL](https://www.opengl.org).
* [Cocoa](https://github.com/jokade/scalanative-cocoa) - macOS 图形框架的绑定 [Cocoa](https://en.wikipedia.org/wiki/Cocoa_(API)).
* [GNU Scientific Library](https://github.com/ruivieira/scala-gsl) - 绑定 [GNU Scientific Library (GSL)](https://www.gnu.org/software/gsl).
* [BLAS](https://github.com/ekrich/sblas) - 绑定 [BLAS](http://www.netlib.org/blas/)，线性代数库.
* [Gtk+](https://github.com/jokade/scalanative-gtk) - 绑定 [GTK+](https://www.gtk.org/) 图形工具包.
* [libsoup](https://github.com/jokade/scalanative-libsoup) - 绑定 [libsoup](https://wiki.gnome.org/Projects/libsoup) HTTP 客户端/服务器库.
* [libui](https://github.com/lolgab/scalaui) - 基于GUI框架 [libui](https://github.com/andlabs/libui).
* [GStreamer](https://github.com/jokade/scalanative-gstreamer) - 绑定 [GStreamer](https://gstreamer.freedesktop.org) 多媒体框架.
* [Qt](https://github.com/jokade/scalanative-qt5) - 绑定 [Qt](https://www.qt.io).
* [ncurses](https://github.com/edadma/ncurses) - 绑定 [GNU Ncurses Library](https://www.gnu.org/software/ncurses/).
* [readline](https://github.com/edadma/readline) - 绑定 [GNU Readline Library](https://www.gnu.org/software/readline/).
* [libsndfile](https://github.com/edadma/libsndfile) - 绑定 [Libsndfile](https://tiswww.cwru.edu/php/chet/libsndfile/rltop.html) 用于采样声音操作的 C 库.
* [libpng](https://github.com/edadma/libpng) - 绑定 [libpng](http://www.libpng.org/) 用于读取和写入 PNG 的 C 参考库.
* [libcairo](https://github.com/edadma/libcairo) - 绑定 [Cairo](https://www.cairographics.org/) 2D 图形 C 库.
* [cairo-xlib](https://github.com/edadma/cairo-xlib) - 绑定 [Cairo](https://www.cairographics.org/) 二维图形 [XLib Surfaces](https://www.cairographics.org/manual/cairo-XLib-Surfaces.html) 与绑定 [XLib](https://www.x.org/releases/current/doc/libX11/libX11/libX11.html) 以及.

## File Formats and Parsers
* [msgpack4z](https://github.com/msgpack4z/msgpack4z-native) - 实施 [MessagePack](https://msgpack.org/)，一种二进制序列化格式.
* [FastParse](https://github.com/lihaoyi/fastparse) - 用于定义和运行解析器的库.
* [scalatags](https://github.com/lihaoyi/scalatags) - HTML/XML 构造和渲染.
* [Pine](https://github.com/sparsetech/pine) - HTML/XML 解析、操作和呈现.
* [scala-json](https://github.com/MediaMath/scala-json) - JSON 解析器.
* [uJson](http://www.lihaoyi.com/upickle/#uJson) - 用于 Scala 的快速、灵活和直观的 JSON
* [toml-scala](https://github.com/sparsetech/toml-scala) - [TOML](https://github.com/toml-lang/toml) 带有编解码器派生的解析器.
* [argonaut](https://github.com/argonaut-io/argonaut) - 纯功能的 JSON 解析器和库.
* [ScalaPB](https://github.com/scalapb/ScalaPB) - [Protocol Buffer](https://developers.google.com/protocol-buffers/) Scala 编译器.
  * [scalapb-argonaut](https://github.com/scalapb-json/scalapb-argonaut) - 基于 ScalaPB 的 JSON 和协议缓冲区转换器 [Argonaut](http://argonaut.io).
* [sconfig](https://github.com/ekrich/sconfig) - [HOCON](https://github.com/ekrich/sconfig/blob/master/docs/original/HOCON.md) 解析器.

## Databases
* [JDBC](https://github.com/jokade/scalanative-jdbc) - 数据库访问层端口 [JDBC](https://en.wikipedia.org/wiki/Java_Database_Connectivity) 到 Scala 原生.
* [SQLite4S](https://github.com/david-bouyssie/sqlite4s) - Java 库的端口 [Sqlite4java](https://bitbucket.org/almworks/sqlite4java) . 包括 SQLite 本机库的绑定.

## Web Development
* [Trail](https://github.com/sparsetech/trail) - 路由库.
* [sttp](https://github.com/softwaremill/sttp) - HTTP 客户端库.
* [snunit](https://github.com/lolgab/snunit) - 基于 NGINX 单元的 Scala 原生 HTTP 服务器.

## Concurrency
* [scala-native-loop](https://github.com/scala-native/scala-native-loop) - Scala Native 的事件循环和面向异步的 IO
* [castor](https://github.com/lihaoyi/castor) - 用于 Scala 的轻量级类型化 Actor 库.

## Logging
* [scribe](https://github.com/outr/scribe) - 快速简单的日志库.
* [slogging](https://github.com/jokade/slogging) - [Typesafe-logging](https://github.com/lightbend/scala-logging) 和 [SLF4J](https://www.slf4j.org/)-基于宏的兼容日志库.

## Console
* [fansi](https://github.com/lihaoyi/fansi) - 用于创建的库 [ANSI-coloured strings](https://en.wikipedia.org/wiki/ANSI_escape_code).
* [scopt](https://github.com/scopt/scopt) - 命令行参数解析器.
* [scala-optparse-applicative](https://github.com/xuwei-k/optparse-applicative) - Haskell 的 CLI 参数解析库的端口 [optparse-applicative](https://hackage.haskell.org/package/optparse-applicative).
* [scallop](https://github.com/scallop/scallop) - 一个简单的 Scala CLI 解析库.

## Robotics
* [Potassium](https://github.com/Team846/potassium) - 编写机器人软件的框架.
* [WPILib](https://github.com/Team846/scala-native-wpilib) - 重新实施 [FIRST Robotics WPILib libraries](http://first.wpi.edu/FRC/roborio/release/docs/java/).

## Programs
* [sglgears](https://github.com/Milyardo/sglgears) - GL 港口 [gears.c](https://github.com/JoakimSoderberg/mesademos/blob/master/src/xdemos/glxgears.c).
* [k8s-cli](https://github.com/fsat/k8s-cli) - CLI 工具生成 [Kubernetes](https://kubernetes.io/) 资源 [Akka](https://akka.io/), [Play Framework](https://www.playframework.com/) 和 [Lagom](https://www.lagomframework.com/)基于应用程序.
* [Coursier](https://github.com/coursier/coursier) - 快递员 [`bootstrap` command](https://get-coursier.io/docs/cli-native-bootstrap) 生成本机启动器.
* [fractals](https://github.com/Rusty-Bike/fractals) - 具有基本动画支持的自相似分形生成器.
## Infrastructure
* [Seed Docker image](https://hub.docker.com/r/tindzk/seed/tags) - 用于跨平台构建的 Docker 镜像 [Seed](https://github.com/tindzk/seed).
* [scala-native-sbt-docker](https://github.com/ScalaWilliam/scala-native-sbt-docker) - 用于 Scala Native 和 sbt 的 Docker 镜像.

## Licence
<a rel="licence" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg" /><br />本作品已根据<a rel="licence" href="http://creativecommons.org/licenses/by/4.0/">知识共享署名 4.0 国际许可协议获得许可</a>.
