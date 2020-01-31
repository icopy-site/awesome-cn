<div class="github-widget" data-repo="desiderantes/awesome-vala"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Vala [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/desiderantes/awesome-vala/master/vala.svg?sanitize=true" align="right" width="100">](https://wiki.gnome.org/Projects/Vala/)

 通过依靠GLib和GObject，使用现代高级抽象的编程语言，而没有施加其他运行时要求.



## Data Structures & Data Types

- [Libgee](https://wiki.gnome.org/Projects/Libgee) -实用程序库，为常用的数据结构（列表，地图，队列，树等）提供基于GObject的接口和类.
- [Graphene](https://github.com/ebassi/graphene)  -图形库类型的薄层.  它提供了处理3D转换所需的常见类型：点，三角形，矩形，四边形，四元数，向量，矩阵，球体等.
- [Numeric-GLib](https://github.com/arteymix/numeric-glib)  -通过GCC扩展集合GLib（和Vala）的数字数据类型.  它包括128位整数和浮点数，复杂类型，向量化操作和十进制类型.

## Editor Plugins

- [Vala Code](https://github.com/thiagoabreu/vala-code) -VIsual Studio代码的插件，可为Vala启用基本的自动完成和语法突出显示功能.
- [Vala-TMBundle](https://github.com/technosophos/Vala-TMBundle) -TextMate捆绑包，提供Vala语法突出显示，代码完成等功能.Sublime Text 3也可以使用此插件.
- [language-vala-modern](https://atom.io/packages/language-vala-modern)  -在Atom中提供Vala语言支持.  它是未维护的“语言-值包”的分支.
- [Vala Syntax 4 Sublime Text](https://launchpad.net/valasyntax4sublimetext) -Sublime Text 3的基本插件，可突出显示语法.

## Language Servers

- [GVLS](https://gitlab.gnome.org/esodan/gvls)  -为Vala提供代码完成和格式设置的服务.  由于缺少lsp实现的详细信息，因此当前不适用于Visual Studio Code，但适用于GNOME Builder.
- [vala-language-server](https://github.com/benwaffle/vala-language-server) -语言服务器，旨在根据语言服务器规范提供代码完成，格式设置，语法突出显示以及其他所有功能.

## Graphic Libraries

- [Cairo](https://cairographics.org/)  -具有支持多个输出设备的2D图形库.  这几乎是您在Vala中获得的默认库.
- [SDL2](https://www.libsdl.org/)  -跨平台开发库，旨在通过OpenGL，Direct3D和Vulkan提供对音频，键盘，鼠标，操纵杆和图形硬件的低级访问.  社区绑定可用 [here](https://github.com/sdl2-vapi/sdl2-vapi).
- [GRX](https://github.com/ev3dev/grx)  -用于简单图形显示的图形库（请考虑使用1位显示或Adafruit的PiTFT显示）.  它还包括键盘，鼠标，操纵杆和触摸屏输入支持.
- [GEGL](http://gegl.org/)  -基于数据流的图像处理框架，提供浮点处理和无损图像处理功能.  可以将其视为“图像的反应式编程”.
- [Babl](http://gegl.org/babl/) -动态的任何像素格式的转换库.

## GUI Programming

- [GTK+](https://www.gtk.org/)  -在Vala中用于GUI开发的事实库.  绑定包含在vala编译器中.

## Multimedia Processing

- [GStreamer](http://gstreamer.freedesktop.org/) -用于创建多媒体应用程序的强大框架.

## XML & Data Serialization

- [GXML](https://gitlab.gnome.org/GNOME/gxml/) -用于处理XML的GObject API和从GObject到XML的可序列化框架.
- [Json-GLib](https://gitlab.gnome.org/GNOME/json-glib/) -使用GLib和GObject实现完整的JSON解析器和生成器，并将JSON与GLib数据类型集成.
- [libyaml-glib](https://github.com/rainwoodman/libyaml-glib) -libyaml的GLib绑定，以及可理解YAML的GObject构建器.

## Templating

- [Compose](https://github.com/arteymix/compose) -Vala的功能性模板库.
- [template-glib](https://gitlab.gnome.org/GNOME/template-glib) -模板扩展库，支持从模板调用GObject Introspection.

## Numerical Computation

- [vast](https://github.com/rainwoodman/vast)  -Vala的生成建模项目.  想想用Vala重写的TensorFlow.

## Crypto & Security

- [GnuTLS](https://www.gnutls.org/) - A secure communications library implementing the SSL, TLS and DTLS protocols and technologies around them. It provides a simple API to access the secure communications protocols as well as APIs to parse and write X.509, PKCS #12, and other required structures.

## Web Development

- [Valum](https://github.com/valum-framework/valum) -完全用Vala编写的Web微框架.
- [Ambition](https://github.com/AmbitionFramework/ambition)  -用Vala编写的Web框架，并牢记MVC模式.  Kinda无需维护（有人可以将其重构为在后台使用Valum，甚至可以将其移至Meson）

## Contribute

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/desiderantes/awesome-vala/blob/master/contributing.md) 第一.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，Mario Daniel Ruiz Saavedra和其他贡献者放弃了所有版权和
相关或邻接权.
