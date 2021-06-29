<div class="github-widget" data-repo="desiderantes/awesome-vala"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Vala [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/desiderantes/awesome-vala/master/vala.svg?sanitize=true" align="right" width="100">](https://wiki.gnome.org/Projects/Vala/)

 通过依赖 GLib 和 GObject，一种使用现代高级抽象而不强加额外运行时要求的编程语言.



## Data Structures & Data Types

- [Libgee](https://wiki.gnome.org/Projects/Libgee) - 一个实用程序库，为常用数据结构（列表、地图、队列、树等）提供基于 GObject 的接口和类.
- [Graphene](https://github.com/ebassi/graphene)  - 图形库类型的薄层. 它提供了处理 3D 变换所需的常见类型：点、三角形、矩形、四边形、四元数、向量、矩阵、球体等.
- [Numeric-GLib](https://github.com/arteymix/numeric-glib)  - 通过 GCC 扩展为 GLib（和 Vala）收集的数字数据类型. 它包括 128 位整数和浮点数、复杂类型、向量化运算和十进制类型.
- [United](https://github.com/lcallarec/united) - 用于单位操作的库（如千克、米等）.

## Editor Plugins

- [Vala Code](https://github.com/thiagoabreu/vala-code) - VIsual Studio Code 的插件，可为 Vala 启用基本的自动完成和语法高亮显示.
- [Vala-TMBundle](https://github.com/technosophos/Vala-TMBundle) - 提供 Vala 语法高亮、代码补全等的 TextMate 包.Sublime Text 3 也可以使用这个插件.
- [language-vala-modern](https://atom.io/packages/language-vala-modern)  - 在 Atom 中提供 Vala 语言支持. 它是未维护的“language-vala 包”的一个分支.
- [Vala Syntax 4 Sublime Text](https://launchpad.net/valasyntax4sublimetext) - Sublime Text 3 的基本插件，提供语法高亮.

## Language Servers

- [GVLS](https://gitlab.gnome.org/esodan/gvls)  - 为 Vala 提供代码完成和格式化的服务. 由于缺少 lsp 实现的细节，这当前不适用于 Visual Studio Code，但它适用于 GNOME Builder.
- [vala-language-server](https://github.com/benwaffle/vala-language-server) - 一种语言服务器，旨在根据语言服务器规范提供代码完成、格式设置、语法突出显示以及其他所有内容.

## Graphic Libraries

- [Cairo](https://cairographics.org/)  - 支持多种输出设备的 2D 图形库. 这几乎是您在 Vala 中获得的默认库.
- [SDL2](https://www.libsdl.org/)  - 一个跨平台开发库，旨在通过 OpenGL、Direct3D 和 Vulkan 提供对音频、键盘、鼠标、操纵杆和图形硬件的低级访问. 绑定包含在 Vala 中，将从 Vala 0.52 开始提供.
- [GRX](https://github.com/ev3dev/grx)  - 用于简单图形显示的图形库（想想 1 位显示或 Adafruit 的 PiTFT 显示）. 它还包括键盘、鼠标、操纵杆和触摸屏输入支持.
- [GEGL](http://gegl.org/)  - 基于数据流的图像处理框架，提供浮点处理和无损图像处理能力. 将其视为“图像的反应式编程”.
- [Babl](http://gegl.org/babl/) - 一个动态的、任意到任意的像素格式转换库.

## GUI Programming

- [GTK](https://www.gtk.org/)  - Vala 中用于 GUI 开发的事实上的库. 绑定包含在 vala 编译器中.

## Multimedia Processing

- [GStreamer](http://gstreamer.freedesktop.org/) - 创建多媒体应用程序的强大框架.

## XML & Data Serialization

- [GXML](https://gitlab.gnome.org/GNOME/gxml/) - 用于操作 XML 的 GObject API 和从 GObject 到 XML 的可序列化框架.
- [Json-GLib](https://gitlab.gnome.org/GNOME/json-glib/) - 使用 GLib 和 GObject 实现完整的 JSON 解析器和生成器，并将 JSON 与 GLib 数据类型集成.
- [libyaml-glib](https://github.com/rainwoodman/libyaml-glib) - libyaml 的 GLib 绑定​​，以及理解 YAML 的 GObject 构建器.

## Templating

- [Compose](https://github.com/arteymix/compose) - Vala 的功能模板库.
- [template-glib](https://gitlab.gnome.org/GNOME/template-glib) - 支持从模板调用 GObject Introspection 的模板扩展库.

## Numerical Computation

- [vast](https://github.com/rainwoodman/vast)  - Vala 中的生成式建模项目. 想想用 Vala 重写的 TensorFlow.
- [balistica](https://github.com/fusilero/libbalistica)  - 一个开源弹道模拟库. 有一个完整的计算器 [here](https://github.com/fusilero/balistica).

## Crypto & Security

- [GnuTLS](https://www.gnutls.org/) - A secure communications library implementing the SSL, TLS and DTLS protocols and technologies around them. It provides a simple API to access the secure communications protocols as well as APIs to parse and write X.509, PKCS #12, and other required structures.

## Web Development

- [Valum](https://github.com/valum-framework/valum) - 完全用 Vala 编写的 Web 微框架.
- [Ambition](https://github.com/AmbitionFramework/ambition)  - 用 Vala 编写的 Web 框架，并考虑到 MVC 模式. 有点无人维护（有人可以重构它以在引擎盖下使用 Valum，也许将它移到 Meson ）

## IoC and Dependency Injection

- [Vadi](https://github.com/nahuelwexd/Vadi) - 为方便 Vala 开发人员使用依赖注入而开发的 IoC 容器.
