<div class="github-widget" data-repo="aleksandar-todorovic/awesome-c"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-c [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)[![List Status](https://api.travis-ci.org/aleksandar-todorovic/awesome-c.svg?branch=master)](https://travis-ci.org/aleksandar-todorovic/awesome-c)

 精选的C好的东西列表.  此列表仅包含* [free software](https://en.wikipedia.org/wiki/Free_software) 代码，以及对物质资源没有恶意的卖方.

 **寻找维护人员：**该列表当前处于非活动状态.  我正在寻找可以使其再次变得出色的维护者.  看到 [#26](https://github.com/aleksandar-todorovic/awesome-c/issues/26) 以获得更多信息，但过程很简单：在此列表中添加或修复几件事，您将成为850+星列表的贡献者.

此列表先前由 [@kozross](https://github.com/kozross) .  他决定将清单切换为 [new platform](https://notabug.org/koz.ross/awesome-c)，因此我决定将其分叉，以便我们可以将其保留在GitHub上.

Contents
========



## Build Systems ##

这些是使C中项目的构建和测试自动化的工具.

* [aimake](http://nethack4.org/projects/aimake/) -旨在避免复杂配置的构建工具. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Autoconf](https://www.gnu.org/software/autoconf/autoconf.html)  -可扩展的M4宏程序包，可产生外壳程序脚本以自动配置软件源代码程序包.  自动工具的一部分. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Automake](https://www.gnu.org/software/automake/automake.html)  -自动生成符合GNU编码标准的`Makefile.in`文件的工具.  需要使用Autoconf.  自动工具的一部分. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [CMake](https://cmake.org/) -用于跨平台构建，测试和打包的工具. [`3-clause BSD`](https://gitlab.kitware.com/cmake/cmake/raw/master/Copyright.txt)
* [Jam](https://www.perforce.com/documentation/jam-documentation)  -构建系统，设计起来比制造容易.  隐含地理解C构建规则. [`Jam License`](https://en.wikipedia.org/wiki/Perforce_Jam#License)
* [Libtool](https://www.gnu.org/software/libtool/)  -通用库支持脚本.  自动工具的一部分. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Meson](https://mesonbuild.com/)  -极其快速，用户友好的构建系统.  基于忍者. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [Premake](https://github.com/premake/premake-core) -为Visual Studio，Xcode或GNU Make等工具集构建脚本生成器. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [Ninja](https://github.com/ninja-build/ninja) -小型，简单的构建系统，注重速度. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [Bazel](https://bazel.build/) -为各种操作系统和目标构建系统. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [Buck](https://buck.build/) -由Facebook创建和使用的构建系统. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [Qbs](https://doc.qt.io/qbs/) -用于软件项目的现代构建工具. [`LGPL3`](https://code.qt.io/cgit/qbs/qbs.git/tree/LICENSE.LGPLv3)
* [qmake](https://doc.qt.io/qt-5/qmake-manual.html) -Qt Framework附带的构建系统. [`GNU GPL3 with Qt Exception`](https://github.com/qt/qtbase/blob/5.11/LICENSE.GPL3-EXCEPT)
* [xmake](https://xmake.io/) -基于lua的跨平台构建实用程序. [`Apache 2.0`](https://github.com/xmake-io/xmake/blob/master/LICENSE.md )

## Compilers ##

* [Clang](http://clang.llvm.org/)  -LLVM的C编译器.  支持C11. [`NCSA`](https://directory.fsf.org/wiki/License:NCSA)
* [CompCert](http://compcert.inria.fr/)  -完全验证的C编译器.  支持几乎所有的C89. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [GCC](https://gcc.gnu.org/)  -提供C编译器作为其编译器集的一部分.  支持C11和OpenMP. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [PCC](http://pcc.ludd.ltu.se/)  -杰出的C编译器.  支持C99. [`Various free licenses`](http://pcc.ludd.ltu.se/licenses/)
* [TCC](https://bellard.org/tcc/)  -Tiny C编译器；  一个小型，快速的C编译器.  支持C99（复杂类型除外）. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [Intel SPMD](http://ispc.github.io/) -C语言变体的编译器，用于单个程序，多个数据编程. [`Various licenses`](https://github.com/ispc/ispc/blob/master/LICENSE.txt)
* [ccache](https://ccache.dev/) -旨在加快重新编译速度的编译器缓存. [`GNU GPL3 or later`](https://ccache.dev/license.html)

## Compiler libraries ##

用于编译器，解释器和基于低级项目的库.

* [yasm](http://yasm.tortall.net/) -Yasm模块化组装项目. [`2-clause BSD`](https://directory.fsf.org/wiki/License:BSD-2-Clause)

## Compression ##

* [libzip](https://libzip.org/) -用于读取，创建和修改zip存档的AC库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [lzo](http://www.oberhumer.com/opensource/lzo/) -非常快速的数据压缩库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [zlib](http://zlib.net/) -庞大而精致的压缩库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [bzip2](http://www.bzip.org/) -免专利的高质量数据压缩器. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [lz4](https://lz4.github.io/lz4/) -快速压缩算法.
* [snappy](https://github.com/google/snappy) -快速压缩库（在C ++中实现，对C的本地绑定）.
* [zstd](http://facebook.github.io/zstd/) -快速的实时压缩算法 [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [quicklz](http://www.quicklz.com/index.php) -快速压缩库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [pixz](https://github.com/vasi/pixz) -Pixz（发音为pixie）是`xz`的并行索引版本. [`2-clause BSD`](https://directory.fsf.org/wiki/License:BSD-2-Clause)

## Crypto ##

* [GnuTLS](https://www.gnutls.org/) -安全的通信库，实现SSL，TLS和DTLS. [`GNU LGPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [libgcrypt](https://gnupg.org/related_software/libgcrypt/) -具有多种可用密码的通用密码库. [`GNU LGPL2.1or later (code)`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) 和 [`GNU GPL2.1 or later (manual 和 tools)`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [OpenSSL](https://www.openssl.org/) -SSL和TLS协议的实现，还包括一个加密库. [`Dual Licensed under the OpenSSL License and the SSLeay License`](https://www.openssl.org/source/license.html)
* [libsodium](https://download.libsodium.org/doc/) -现代且易于使用的加密库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libtomcrypt](https://www.libtom.net/) -非常全面，模块化和便携式的加密工具包. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [mbed TLS](https://tls.mbed.org/) -C的另一种加密实现. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [libressl](https://www.libressl.org/) -OpenSSL的现代化分支. [`Various Licenses`](https://cvsweb.openbsd.org/cgi-bin/cvsweb/~checkout~/src/lib/libssl/LICENSE?rev=1.12)

## Database ##

这列出了带有C API的数据库和数据存储.

* [BerkeleyDB](https://www.oracle.com/database/berkeley-db/) -用于键值数据的高性能嵌入式数据库的库. [`GNU AGPLv3`](https://www.gnu.org/licenses/agpl-3.0.html)
* [Hiredis](https://github.com/redis/hiredis) -Redis的简约客户端库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [LMDB](https://github.com/LMDB/lmdb) -超快速，超紧凑的键值嵌入式数据存储. [`OpenLDAP License`](https://directory.fsf.org/wiki/License:OLDAP-2.7)
* [MariaDB](https://mariadb.com/) -健壮，可扩展且可靠的SQL Server，旨在替代MySQL. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [mongo-c-driver](http://mongoc.org/) -的高性能客户端库 [MongoDB](https://www.mongodb.com/). [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [PostgreSQL](https://www.postgresql.org/) -强大的对象关系数据库系统. [`PostgreSQL licence`](https://opensource.org/licenses/postgresql)
* [recutils](https://www.gnu.org/software/recutils/) -一组工具和一个C库，用于访问可编辑的纯文本数据库文件，称为recfiles. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Redis](https://redis.io/) -高级键值存储. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [sophia](http://sophia.systems/) -现代化的可嵌入键值数据库. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [SQLite](https://www.sqlite.org/about.html) -具有C接口的自包含，无服务器，零配置的事务型SQL数据库引擎. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [UnQLite](https://unqlite.org/) -具有C接口的自包含，无服务器，零配置，事务型NoSQL引擎. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)

## Deep Learning ##
* [Darknet](https://pjreddie.com/darknet/)  -用C和CUDA编写的开源神经网络框架.  它快速，易于安装，并支持CPU和GPU计算.

## Documentation Generation ##

* [Cxref](http://www.gedanken.org.uk/software/cxref/) -生成LaTeX，HTML，RTF或SGML中C程序的文档. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [DocOnce](https://hplgit.github.io/doconce/doc/web/index.html) -标记适度的标记语言，可用于生成多种格式. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [Doxygen](http://www.doxygen.nl/)  -用于从带注释的源生成C文档的事实上的标准工具.  可以生成各种格式. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [GTK-Doc](https://www.gtk.要么g/gtk-doc/)  -用于从带注释的源生成C文档的工具.  支持自动工具. [`GNU GPL2.1 (code)`](http://www.gnu.要么g/licenses/old-licenses/lgpl-2.1.html) 要么 [`GNU FDL1.1`](https://www.gnu.要么g/licenses/old-licenses/fdl-1.1.html)

## Editors ##

 这些是特别高级的IDE类型的编辑器.  如果需要程序员的文本编辑器，请在其他地方查找.  此外，无论您做出何种选择，无论如何都支持C.

* [Anjuta DevStudio](http://anjuta.org/) -GNOME IDE. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [Code::Blocks](http://www.codeblocks.org/) -支持C的可扩展，可配置的IDE. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [CodeLite](https://codelite.org/) -跨平台IDE. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Eclipse](http://www.eclipse.org/ide/) -用Java编写的IDE. [`EPL`](https://directory.fsf.org/wiki/License:EPL-1.0)
* [Geany](https://www.geany.org/) -非常小而快速的IDE. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [KDevelop](https://www.kdevelop.org/) -KDE IDE. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Qt Creator](https://www.qt.io/qt-features-libraries-apis-tools-and-ide/#ide)  -用C ++和Qt（Qt SDK的一部分）编写的跨平台IDE.  支持C语代码模型. [`GNU GPL3 with Qt exception`](https://github.com/qt-creator/qt-creator/blob/master/LICENSE.GPL3-EXCEPT)
* [Visual Studio Code](https://code.visualstudio.com/)  -代码编辑，重新定义.  Visual Studio代码.

## Embedded Systems ##

这些项目使人们可以使用微控制器和其他资源受限的体系结构.

### RTOS ###

实时操作系统（RTOS）旨在为处理延迟低延迟的数据的实时应用程序提供服务.

* [Amazon FreeRTOS](https://aws.amazon.com/freertos/) -用于微控制器的RTOS，使小型，低功耗边缘设备易于编程. [`MIT`](https://github.com/aws/amazon-freertos/blob/master/LICENSE)
* [ChibiOS](http://www.chibios.org/dokuwiki/doku.php) -具有完整开发环境（HAL，驱动程序，支持文件和工具）的RTOS. [`Various Licenses`](http://www.chibios.org/dokuwiki/doku.php?id=chibios:licensing:start)
* [Contiki](http://www.contiki-os.org/) -将低成本，低功耗的微控制器连接到Internet. [`3-clause BSD`](https://github.com/contiki-os/contiki/blob/master/LICENSE)
* [Zephyr Project](https://www.zephyrproject.org/) -可扩展的实时RTOS，支持多种硬件体系结构，针对资源受限的设备进行了优化. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [RIOT OS](https://www.riot-os.org/) -实时多线程操作系统，它支持物联网中通常存在的一系列设备. [`LGPL-2.1`](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html)

## Environments ##

这是旨在将Windows引入C语言支持的21世纪的技术列表.

* [Cygwin](https://cygwin.com/) -旨在在Windows下广泛模拟POSIX兼容环境. [`Various Licenses`](https://cygwin.com/licensing.html)
* [MinGW-w64](http://mingw-w64.yaxm.org/doku.php/start) -在Windows上具有64位支持的C开发的极简环境. [`Various Licenses`](http://mingw.org/license)

## Frameworks ##

本部分包含大型库，这些库提供了数据结构和您期望的“现代”标准库的其他内容.

* [APR](http://apr.apache.org/)  -Apache可移植运行时；  另一个跨平台实用程序函数库. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [C Algorithms](https://fragglet.github.io/c-algorithms/) -收集C的通用算法和数据结构. [`ISC`](https://directory.fsf.org/wiki/License:ISC)
* [C Macro Collections](https://github.com/LeoVen/C-Macro-Collections) -仅标头，在C中由宏生成，泛型和类型安全的Collections. [`MIT`](https://spdx.org/licenses/MIT.html)
* [CPL](http://www.eso.org/sci/software/cpl/)  -通用管道库；  一组库，旨在成为一个全面，高效且强大的软件工具包. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [EFL](https://www.enlightenment.org/) -收集了大量有用的数据结构和功能.
* [GLib](https://wiki.gnome.org/Projects/GLib) -实用程序功能和结构库，旨在实现便携式，高效和强大. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [GIO](https://developer.gnome.org/gio/) -现代且易于使用的VFS API. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [GObject](https://developer.gnome.org/gobject/stable/) -C语言的面向对象系统和对象模型. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [libnih](https://github.com/keybuk/libnih) -C函数和结构的轻量级库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [libU](http://www.koanlogic.com/libu/) -基本实用程序的小型库，包括内存分配，字符串操作和日志记录. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [PBL](http://www.mission-base.com/peter/source/) -大型实用程序库，其中包括数据结构. [`GNU LGPL2.1 要么 later (library)`](http://www.gnu.要么g/licenses/old-licenses/lgpl-2.1.html) 要么 [`GNU GPL2.1 要么 later (test code)`](http://www.gnu.要么g/licenses/old-licenses/gpl-2.0.html)
* [qlibc](http://wolkykim.github.io/qlibc/) -简单而强大的C库，旨在替代GLib，同时注重体积小巧. [`qLib license`](https://github.com/wolkykim/qlibc/blob/master/LICENSE) （如同 [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD))
* [stb](https://github.com/nothings/stb) -C的单文件库范围. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [libsrt](https://faragon.github.io/libsrt.html) -C的安全实时库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)


## Game Programming ##

### Engines ###

这些作为C游戏编程代码的示例提供.

* [Corange](https://github.com/orangeduck/Corange) -纯C语言的游戏引擎. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [Darkplaces](https://icculus.org/twilight/darkplaces/) -Quake2引擎的修改版. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [ioquake3](https://ioquake3.org/) -Quake3引擎，终于释放了. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Orx](http://orx-project.org/) -便携式，轻便，基于插件，数据驱动，面向2D的游戏引擎. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [Quake](https://github.com/id-Software/Quake) -雷神之锤引擎. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Quake2](https://github.com/id-Software/Quake-2) -Quake2引擎. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Spearmint](https://clover.moe/spearmint/) -专为FPS游戏设计的引擎. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)

### Resources ###

These are libraries of all sorts that are useful for game programming.

* [Allegro](https://liballeg.org/) -跨平台，视频游戏开发和多媒体库. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [Chipmunk2D](http://chipmunk-physics.net/) -快速，轻量的2D游戏物理库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [CSFML](https://www.sfml-dev.org/download/csfml/) -绑定 [SFML](https://www.sfml-dev.org/index.php) 在C中 [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [FreeGLUT](http://freeglut.sourceforge.net/)  -替代OpenGL Utility Toolkit.  允许使用OpenGL上下文创建和管理窗口. [`X11`](https://directory.fsf.org/wiki/License:X11)
* [GLFW](https://www.glfw.org/) -用于使用OpenGL上下文创建窗口的多平台库. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [libao](https://xiph.org/ao/) -具有多种输出的跨平台音频库. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [RetroArch](https://www.libretro.com/) -的参考前端 [libretro](https://www.libretro.com/). [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [SDL and SDL2](https://www.libsdl.org/)  -跨平台开发库，旨在通过OpenGL提供对音频，键盘，鼠标，操纵杆和图形硬件的低级访问.  SDL2是最新版本. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [raylib](https://www.raylib.com/) -简单易用的库，用于学习视频游戏编程. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)

## Generic Programming ##

* [klib](http://attractivechaos.github.io/klib/#About) -通用算法和数据结构的小型轻量级实现. [`MIT`](https://en.wikipedia.org/wiki/MIT_License)

## Graphics ##

* [Cairo](https://www.cairographics.要么g/) -2D图形库. [`GNU LGPL2.1`](http://www.gnu.要么g/licenses/old-licenses/lgpl-2.1.html) 要么 [`MPLv1.1`](https://direct要么y.fsf.要么g/wiki/License:MPL-1.1)
* [Cogl](https://github.com/rib/cogl-web/wiki) -GPU图形和实用程序API. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [Clutter](https://blogs.gnome.org/clutter/get-it/) -基于OpenGL的UI库. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [giflib](https://sourceforge.net/projects/giflib/) -用于读取和写入gif图像的库. [`MIT`](https://spdx.org/licenses/MIT.html)
* [heman](https://github.com/prideout/heman) -处理高度图，法线图，距离场等的图像实用程序的微型库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libcaca](https://github.com/cacalabs/libcaca) -用于基于终端的接口的ASCII渲染器. [`WTFPLv2`](http://www.wtfpl.net/txt/copying/)
* [libimagequant](https://pngquant.org/lib/) -小型便携式库，可将RGBA图像高质量转换为8位索引彩色图像. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [libjpeg-turbo](https://libjpeg-turbo.org/) -更快的用于读取和写入JPEG文件的库. [`Various Licenses`](https://libjpeg-turbo.org/About/License)
* [libpng](http://www.libpng.org) -官方的PNG参考库. [`libpng license`](http://www.libpng.org/pub/png/src/libpng-LICENSE.txt)
* [libxmi](https://www.gnu.org/software/libxmi/) -用于2D矢量图形栅格化的函数库. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [mozjpeg](https://github.com/mozilla/mozjpeg) -改进的JPEG编码器. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)

### Graphic APIs ###

* [OpenGL](https://www.opengl.org/)  -行业采用2D和3D图形API.  的更多资源 [awesome-opengl](https://github.com/eug/awesome-opengl).
* [OpenGL ES](https://www.khronos.org/opengles/) -工业界为移动和嵌入式设备采用了2D和3D图形API.
* [OpenGL SC](https://www.khronos.org/openglsc/) -适用于需要系统安全认证的行业的图形和计算标准.
* [Vulkan](https://www.khronos.org/vulkan/)  -用于现代跨平台开发的显式图形和计算API.  的更多资源 [awesome-vulkan](https://github.com/vinjn/awesome-vulkan).

## Graphical User Interface ##

这些是专门 [widget toolkits](https://en.wikipedia.org/wiki/Widget_toolkit).

* [GTK+](https://www.gtk.org/) -跨平台的小部件工具包. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/) -另一个跨平台的小部件工具包. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [Tk](http://www.tcl.tk/)  -基本的小部件工具包.  Tcl / Tk的一部分. [`Tcl/Tk License`](http://www.tcl.tk/software/tcltk/license.html)
* [XForms Toolkit](http://xforms-toolkit.org/) -专为XWindow系统设计的小部件工具包. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [nuklear](https://github.com/vurtun/nuklear) -单头ANSI C gui库. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [libui](https://github.com/andlabs/libui) -简单，可移植（但不固定）的GUI库. [`MIT`](https://github.com/andlabs/libui/blob/master/LICENSE)
* [LCUI](https://github.com/lc-soft/LCUI/) -小型C库，用于使用C，XML和CSS构建用户界面. [`MIT`](https://github.com/lc-soft/LCUI/blob/develop/LICENSE.TXT)

## Hashing ##

所有与哈希相关的库，无论是否加密.

* [jwHash](https://github.com/watmough/jwHash) -快速哈希表实现. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [xxHash](http://cyan4973.github.io/xxHash/) -极快的非加密哈希算法. [`2-clause BSD`](https://directory.fsf.org/wiki/License:BSD-2-Clause)
* [murmur](https://github.com/ispc/ispc) -MurMur哈希的C实现. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [t1ha](https://github.com/leo-yuriev/t1ha) -快速正哈希库. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)

## Image Processing ##

* [libccv](http://libccv.org) -现代计算机视觉库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)

## JSON ##

* [Jansson](http://www.digip.org/jansson/) -C库，用于编码，解码和处理JSON. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [jsmn](https://zserge.com/jsmn.html) -简约的JSON解析器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [json-c](https://github.com/json-c/json-c/wiki) -使用JSON的库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [WJElement](https://github.com/netmail-open/wjelement/wiki) -高级JSON操作库，支持JSON Schema. [`LGPL, any version`](https://github.com/netmail-open/wjelement/)
* [YAJL](https://lloyd.github.io/yajl/) -快速的C JSON流解析器库. [`ISC`](https://directory.fsf.org/wiki/License:ISC)

## Learning, Reference and Tutorials ##

这是用于一般学习C编程的资源列表，或与C编程有关的有用信息.

### Online ###

#### Reference ####

* [SEI CERT C Coding Standard](https://wiki.sei.cmu.edu/confluence/display/c/SEI+CERT+C+Coding+Standard)
* [C FAQ - comp.lang.c Frequently Asked Questions](http://c-faq.com/)
* [Comparison of C/POSIX standard library implementations for GNU/Linux](http://www.etalabs.net/compare_libcs.html)
* [GNU C Reference Manual](https://www.gnu.org/software/gnu-c-manual/)
* [Robert Pike's notes on programming in C](http://www.lysator.liu.se/c/pikestyle.html)
* [Draft ANSI C Rationale](http://port70.net/~nsz/c/c89/rationale/)
* [Draft C99 Rationale](http://port70.net/~nsz/c/c99/C99RationaleV5.10.pdf)

##### Language Standards #####
* [Draft ANSI C (C89) standard](http://port70.net/~nsz/c/c89/c89-draft.txt)
* [Draft C99 standard](http://www.open-std.org/jtc1/sc22/wg14/www/docs/n1256.pdf)
* [Draft C11 standard](http://www.open-std.org/JTC1/SC22/WG14/)

#### Beginner ####

* [Tutorial on pointers](http://www.cs.ucsb.edu/~mikec/cs16/misc/ptrtut12/index.htm)
* [Building C Projects](http://nethack4.org/blog/building-c.html)
* [C Programming Wikibook](https://en.wikibooks.org/wiki/C_Programming)
* [Introduction to 'fun' C](https://gist.github.com/eatonphil/21b3d6569f24ad164365)
* [Learning C with GDB](https://www.recurse.com/blog/5-learning-c-with-gdb)
* [POSIX Threads Programming tutorial](https://computing.llnl.gov/tutorials/pthreads/) （有一点过时，但大多数仍然有效且有用）
* [The GNU C Programming Tutorial](http://www.crasseux.com/books/ctut.pdf) （在线PDF）
* [Templating in C](http://blog.pkh.me/p/20-templating-in-c.html)

#### Intermediate ####

* [8 gdb tricks you should know](https://blogs.oracle.com/linux/8-gdb-tricks-you-should-know-v2)
* [10 C99 tricks](https://blog.noctua-software.com/c-tricks.html)
* [Diving into concurrency: trying out mutexes and atomics](https://jvns.ca/blog/2014/12/14/fun-with-threads/)
* [Introduction to OpenMP](https://www.youtube.com/playlist?list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG) （视频）
* [OpenMP tutorial](https://computing.llnl.gov/tutorials/openMP/) （对于OpenMP3标准）
* [memcpy vs memmove](https://web.archive.org/web/20170620131430/https://www.tedunangst.com/flak/post/memcpy-vs-memmove)
* [MPI tutorial](https://computing.llnl.gov/tutorials/mpi/)
* [Some unknown features or tricks in C language](https://proprogramming.org/some-unknown-features-or-tricks-in-c-language/)
* [The lost art of C structure packing](http://www.catb.org/esr/structure-packing/)
* [What a C programmer should know about memory](https://marek.vavrusa.com/memory/)
* [What every C programmer should know about undefined behaviour](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html)

#### Advanced ####

* [Advanced metaprogramming in C](http://250bpm.com/blog:56)
* [Quick tutorial on implementing and debugging malloc, free, calloc, and realloc](http://danluu.com/malloc-tutorial/)
* [Bit twiddling hacks](https://graphics.stanford.edu/~seander/bithacks.html)
* [I do not know C](https://kukuruku.co/post/i-do-not-know-c/)
* [Implementing smart pointers for the C programming language](https://snai.pe/c/c-smart-pointers/)
* [Inline functions in C](http://www.greenend.org.uk/rjk/tech/inline.html)
* [Metaprogramming custom control structures in C](https://www.chiark.greenend.org.uk/~sgtatham/mp/)
* [Some dark corners of C](https://docs.google.com/presentation/d/1h49gY3TSiayLMXYmRMaAEMl05FaJ-Z6jDOWOz3EsqqQ/edit?pli=1#slide=id.gaf50702c_0153)
* [Writing efficient C and C code optimization](https://www.codeproject.com/articles/6154/writing-efficient-c-and-c-code-optimization)
* [What every programmer should know about memory](https://www.akkadia.org/drepper/cpumemory.pdf)

#### Self-study courses ####

* [C Programming Language Certified Associate preparation course](https://cppinstitute.com/study-resources )

### Physical ###

#### Reference ####

* [C: A Reference Manual 5E](http://careferencemanual.com/) -C99的完整参考书.
* [C Pocket Reference](http://shop.oreilly.com/product/9780596004361.do) -精简的C99参考书.
* [The C Programming Language 2E](https://en.wikipedia.org/wiki/The_C_Programming_Language) -由创作者撰写的有关C的原始书籍.

#### Beginner ####

* [C Primer Plus 6E](https://www.pearson.com/us/higher-education/program/Prata-C-Primer-Plus-6th-Edition/PGM4399.html) -有关C11编程的完整教程.
* [C Programming: A Modern Approach](http://knking.com/books/c2/index.html) -优秀的书籍，学习C的基础知识.
* [Head First C](http://shop.oreilly.com/product/0636920015482.do) -学习C的“以人为本”风格的书.

#### Intermediate ####

* [21st Century C](http://shop.oreilly.com/product/0636920033677.do) -关于C的非常好的第二本书.
* [Understanding and Using C Pointers](http://shop.oreilly.com/product/0636920028000.do) -有关C语言中指针的深入资源.
* [ZeroMQ](http://shop.oreilly.com/product/0636920026136.do) -有关在C语言中使用ZeroMQ的书.

#### Advanced ####

* [Expert C Programming: Deep C Secrets](https://dl.acm.org/citation.cfm?id=179241) -有趣，深入而有趣的C语言的内在特性.

## Macros ##

* [P99](http://p99.gforge.inria.fr/) -宏套件，用于实现高级功能，例如默认函数参数，作用域绑定的资源等（要求C99） [`Q Public License`](https://tldrlegal.com/license/q-public-license-1.0-(qpl-1.0)#summary)

## Memory Allocators ##

用于各种系统和平台的内存分配器的实现.

* [jemalloc](http://jemalloc.net/) -通用malloc（3）实现，强调实现避免碎片化和可伸缩的并发支持，通常在生产系统中使用. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [dlmalloc](http://g.oswego.edu/pub/misc/malloc.c) -Doug Lea的malloc（3）实现，可用于学术和研究目的. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [Hoard](http://hoard.org/) -适用于Linux，Windows，Mac和Solaris的快速，可扩展和内存高效的Malloc. [`GNU GPL2`](http://www.gnu.org/licenses/gpl-3.0.html)
* [nedmalloc](http://www.nedprod.com/programs/portable/nedmalloc/) -用C语言编写的EXTREMELY FAST便携式线程缓存malloc（3）实现. [`GNU GPL2`](http://www.gnu.org/licenses/gpl-3.0.html)
* [rpmalloc](https://github.com/rampantpixels/rpmalloc) -跨平台，无锁的内存分配器. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)


## Multimedia ##

* [FFMPEG](https://www.ffmpeg.要么g/) -完整的跨平台解决方案，用于记录，转换和流式传输音频和视频. [`GNU LGPL2.1 要么 later`](http://www.gnu.要么g/licenses/old-licenses/lgpl-2.1.html) 要么 [`GNU GPL2.1 要么 later (some parts)`](http://www.gnu.要么g/licenses/old-licenses/gpl-2.0.html)
* [GStreamer](https://gstreamer.freedesktop.org/) -音频和视频媒体的框架. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [lodepng](https://lodev.org/lodepng/) -简单的PNG图像解码器和编码器，不需要其他依赖项. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [libsoup](https://wiki.gnome.org/action/show/Projects/libsoup?action=show&redirect=LibSoup)  -GNOME HTTP客户端/服务器库.  使用GObject. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [libmpv](https://mpv.io/)  -音乐播放库.  用``./waf configure --disable-cplayer --enable-libmpv-shared&#39;&#39;编译以没有音乐播放器. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [libsoundio](http://libsound.io/)  -用于跨平台，实时音频输入和输出的库.  具有一系列后端. [`Expat`](https://directory.fsf.org/wiki/License:Expat)


## Networking and Internet ##

* [asnlc](http://lionet.info/asn1c/compiler.html) -将ASN.1规范编译为C源代码. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [czmq](http://czmq.zeromq.org/) -ZeroMQ的高级绑定. [`MPL2.0`](https://www.gnu.org/licenses/license-list.html#MPL-2.0)
* [GNU adns](https://www.gnu.org/software/adns/) -先进的，易于使用的，具有联盟能力的DNS客户端库和实用程序. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GNU SASL](https://www.gnu.org/software/gsasl/) -实现简单身份验证和安全层以及一些通用的SASL机制. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GnuTLS](https://www.gnutls.org/) -安全的通信库，实现SSL，TLS和DTLS. [`GNU LGPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [gumbo-parser](https://github.com/google/gumbo-parser) -C99中的HTML5解析库. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [http-parser](https://github.com/nodejs/http-parser) -HTTP请求/响应解析器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [ldns](https://www.nlnetlabs.nl/projects/ldns/index.html) -简化DNS编程的库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [libcurl](https://curl.haxx.se/libcurl/) -客户端URL传输库，支持多种格式. [`curl license`](https://curl.haxx.se/docs/copyright.html)
* [LibEtPan](http://www.etpan.org/) -邮件库为IMAP，SMTP，POP和NNTP提供了有效的网络. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [libev](http://software.schmorp.de/pkg/libev.html) -另一个事件循环. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [libuv](http://libuv.org/) -跨平台异步I / O. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libevent](http://libevent.org/) -网络服务器的事件循环替换. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [libgss](https://www.gnu.org/software/gss/) -通用安全服务. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [libhttpd](https://hughes.com.au/products/libhttpd/) -将基本Web服务器功能添加到应用程序或嵌入式设备的库. [`GNU GPL2`](http://www.gnu.org/licenses/gpl-3.0.html)
* [libidn](https://www.gnu.org/software/libidn/) -实施Stringprep，Punycode和IDNA规范. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [libmicrohttpd](https://www.gnu.org/software/libmicrohttpd/) -小型C库，可轻松将HTTP服务器作为另一个应用程序的一部分运行. [`GNU LGPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [libsagui](https://risoflora.github.io/libsagui/) -Sagui是一个跨平台的C库，可帮助开发Web服务器或框架. [`GNU LGPL3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [libvldmail](https://github.com/dertuxmalwieder/libvldmail) -您友好的电子邮件地址验证库. [`WTFPLv2`](http://www.wtfpl.net/txt/copying/)
* [lwan](https://lwan.ws/) -实验性，可扩展的高性能HTTP服务器. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [mongoose](https://cesanta.com/) -用于C的嵌入式Web服务器. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [nanomsg](https://github.com/nanomsg/nanomsg) -基于C的ZeroMQ实现. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [OpenSSL](https://www.openssl.org/) -SSL和TLS协议的实现，还包括一个加密库. [`Dual Licensed under the OpenSSL License and the SSLeay License`](https://www.openssl.org/source/license.html)
* [oSip](https://www.gnu.org/software/osip/) -C中的SIP实现，没有其他依赖关系. [`GNU LGPLv2.1 or later`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [pig](https://github.com/rafael-santiago/pig) -Linux数据包制作工具. [`GPL2`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [s2n](https://github.com/awslabs/s2n) -TLS / SSL协议的C99实现，旨在简单，快速且以安全性为优先. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [socket99](https://github.com/silentbicycle/socket99) -BSD套接字API的C99包装器. [`ISC`](https://directory.fsf.org/wiki/License:ISC)
* [Tox](https://tox.chat/) -旨在成为Skype杀手的通信平台. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [twitc](https://github.com/sinemetu1/twitc) -用于与Twitter OAuth API进行交互的Mini C库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [librg](https://github.com/librg/librg) -用于构建简单，优雅的跨平台mmo客户端-服务器解决方案的库. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)

### Web Frameworks ###

* [balde](https://balde.rgm.io/) -基于GLib的C的微框架. [`GNU LGPLv2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [onion](https://www.coralbits.com/libonion/) -C库创建简单的HTTP服务器和Web应用程序. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [kore](https://kore.io/) -易于使用，可扩展且安全的Web应用程序框架，用于用C编写Web API.
* [klone](http://www.koanlogic.com/klone/) -KLone是功能齐全的多平台Web应用程序开发框架.
* [duda](http://duda.io/) -Duda I / O是一个用C编写的事件驱动的高性能Web服务框架. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)

## Numerical ##

* [apophenia](http://apophenia.info/) -统计和科学计算图书馆. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [ATLAS](http://math-atlas.sourceforge.net/) -自动调整的线性代数软件. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [BLAS](http://www.netlib.org/blas/)  -基本的线性代数子程序；  一组提供矢量和矩阵运算的例程. [`BLAS license`](http://www.netlib.org/blas/#_licensing)
* [CDFLIB](https://people.sc.fsu.edu/~jburkardt/c_src/cdflib/cdflib.html)  -带有例程的库，用于评估各种标准概率分布的累积密度函数.  给定其他参数，也可以计算CDF的一个参数.  （未提供许可证）
* [cmathl](https://scientificc.github.io/cmathl/)  -具有多种数学功能和CMake构建支持的Pure-C Math库.  似乎很符合C89 / C90的可移植性. [`MIT`](https://github.com/ScientificC/cmathl/blob/master/LICENSE)
* [Cuba](http://www.feynarts.de/cuba/) -多维数值积分库. [`GNU LGPLv3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [FFTW](http://www.fftw.org/)  -西方最快的傅立叶变换；  高度优化的快速傅立叶变换例程. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [FLINT](http://flintlib.org/)  -数字理论快速图书馆；  支持数字，多项式，幂级数和矩阵等算法的库. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [GLPK](https://www.gnu.org/software/glpk/)  -GNU线性编程套件；  设计用于解决大规模线性规划，混合整数规划和其他相关问题的软件包. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GMP](https://gmplib.org/)  -GNU多精度算法库；  一个用于任意精度算术的库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 和 [`GNU LGPLv3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [GNU MPC](http://www.multiprecision.org/mpc/) -复数算法库. [`GNU LGPL3 or later`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [GNU MPFR](https://www.mpfr.要么g/index.html) -用于任意精度浮点运算的库. [`GNU LGPL3 要么 later`](http://www.gnu.要么g/licenses/lgpl-3.0.html) 要么 [`GNU LGPL2.1 要么 later (until version 2.4.x)`](http://www.gnu.要么g/licenses/old-licenses/lgpl-2.1.html)
* [GNU MPRIA](https://www.gnu.org/software/mpria/) -便携式数学库，用于多精度有理区间算术. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GSL](http://www.gnu.org/software/gsl/)  -GNU科学图书馆；  复杂的数值库. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [igraph](https://igraph.org/) -用于创建和处理大型图形的库. [`GNU GPL2`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [KISS FFT](https://sourceforge.net/projects/kissfft/) -非常简单的快速傅立叶变换库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [LAPACKE](http://www.netlib.org/lapack/lapacke.html) -C接口 [LAPACK](http://www.netlib.org/lapack/). [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [PARI/GP](http://pari.math.u-bordeaux.fr/)  -用于数论的计算机代数系统；  包括C语言的编译器. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [PETSc](https://www.mcs.anl.gov/petsc/) -通过偏微分方程建模的科学应用的可扩展并行解决方案的数据结构和例程套件. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [PROB](https://people.sc.fsu.edu/~jburkardt/c_src/prob/prob.html) -处理各种离散和连续概率密度函数的库.  [`GNU LGPL3`](https://people.sc.fsu.edu/~jburkardt/txt/gnu_lgpl.txt)
* [Yeppp!](https://bitbucket.org/MDukhan/yeppp) -非常快速，SIMD优化的数学库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)

## Parallel Programming ##

* [cchan](http://repo.hu/projects/cchan/) -用于通道间通信的通道构造的小型库. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [ck](http://concurrencykit.org/) -并发原语，安全内存回收机制和非阻塞数据结构. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [mill](http://libmill.org/) -C语言中的Go风格并发. [`X11`](https://directory.fsf.org/wiki/License:X11)
* [libdill](http://libdill.org/) -C中的结构化并发. [`X11`](https://directory.fsf.org/wiki/License:X11)
* [MPICH](http://www.mpich.org/) -MPI的另一种实现. [`MPICH licence`](http://git.mpich.org/mpich.git/blob_plain/6aab201f58d71fc97f2c044d250389ba86ac1e3c:/COPYRIGHT)
* [OpenMP](https://www.openmp.org/) -C语言编译工具集，旨在简化代码的并行化. [`3-clause BSD`](https://opensource.org/licenses/BSD-3-Clause)
* [OpenMPI](https://github.com/open-mpi/ompi) -消息传递接口的实现. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [pth](https://www.gnu.org/software/pth/) -可移植的实现，用于对多个执行线程进行基于非抢占式优先级的调度. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [pthreads](https://en.wikipedia.org/wiki/POSIX_Threads) -POSIX线程库.
* [SLEPc](https://bitbucket.org/slepc/slepc) -用于在并行计算机上解决大型稀疏特征值问题的软件库. [`GNU LGPL3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [TinyCThread](https://tinycthread.github.io/) -可移植的C11线程API的小型实现. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)

## Parsers ##

* [hammer](https://github.com/abiggerhammer/hammer) -二进制格式的解析器组合器. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [iniparser](https://github.com/ndevilla/iniparser) -.ini文件的解析器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libconfini](https://github.com/madmurphy/libconfini) -另一个解析器. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [libYAML](https://pyyaml.org/wiki/LibYAML) -YAML 1.1解析器和发射器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [mpc](https://github.com/orangeduck/mpc) -解析器组合器库. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [libucl](https://github.com/vstakhov/libucl) -通用配置库解析器. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)


## Regex ##

 &gt;“有些人遇到问题时会想，&#39;我知道，我会使用正则表达式.&#39;现在他们有两个问题.”  -杰米·扎温斯基.

* [PCRE](http://www.pcre.org/) -与Perl 5相同的正则表达式的实现. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [regexp4](https://github.com/nasciiboy/recursiveregexpraptor-4) -具有自己的sintax的正则表达式的简单而完整的实现. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [SLRE](https://github.com/cesanta/slre)  -超轻型正则表达式库；  Perl regex语法子集的非常小的实现. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [sregex](https://github.com/openresty/sregex) -非回溯基于NFA / DFA的Perl兼容正则表达式引擎库. [`3-clause BSD`](https://opensource.org/licenses/BSD-3-Clause)
* [TRE](https://github.com/laurikari/tre/) -符合POSIX的功能齐全的正则表达式库. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)

## Serialization ##

* [binn](https://github.com/liteserver/binn) -二进制序列化格式意味着紧凑，快速且易于使用. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [c-capnproto](https://github.com/jmckaskill/c-capnproto) -Cap&#39;n Proto序列化协议的实现. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [cmp](https://github.com/camgunz/cmp) -实施 [MessagePack](https://msgpack.org/) 序列化协议. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libavro](http://avro.apache.org/docs/current/api/c/index.html#_introduction_to_avro_c) -Avro数据序列化系统的C实现. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [mpack](https://github.com/ludocode/mpack) -的另一种实现 [MessagePack](https://msgpack.org/) 序列化协议. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [netstring-c](https://github.com/liteserver/netstring-c) -Netstring编码器和解码器. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [protobuf-c](https://github.com/protobuf-c/protobuf-c) -在C中实现Google协议缓冲区. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [xdr](https://en.wikipedia.org/wiki/External_Data_Representation) - External Data Representation; a standard for data serialization.


## Source Code Collections ##

 这包含小型源代码的集合.  如果您需要大型集成产品，请查看“框架”部分.

* [CCAN](http://ccodearchive.net/)  -以Perl的CPAN为模型，这是大量可以完成工作的C代码集合.  完整列表是 [here](http://ccodearchive.net/list.html).
* [clib](https://github.com/clibs/clib) -C的软件包管理器.附带 [bunch of libraries of its own](https://github.com/clibs/clib/wiki/Packages). [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [gnulib](https://www.gnu.org/software/gnulib/) -通用GNU代码的集合.
* [libdjb](http://www.fefe.de/djb/) -做各种事情的图书馆的集合. [`(Apparently) Public Domain`](https://creativecommons.org/share-your-work/public-domain/)

## Standard Libraries ##

它包含标准的C库.

* [Bionic](https://github.com/aosp-mirror/platform_bionic) -为Android开发的Google C标准库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [dietlibc](http://www.fefe.de/dietlibc/) -为最小的二进制文件设计的C标准库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [glibc](http://www.gnu.org/software/libc/)  -GNU C库；  C标准库的实现. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [musl](http://www.musl-libc.org/)  -标准C库，与POSIX 2008和C11兼容.  专为静态链接而设计. [`Expat`](https://directory.fsf.org/wiki/License:Expat)

## String Manipulation ##

* [bstrlib](http://bstring.sourceforge.net/) -更好的字符串库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause) 和 [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [ICU](http://site.icu-project.org/)  -Unicode的国际组件；  一个支持Unicode的库. [`ICU license`](http://source.icu-project.org/repos/icu/icu/tags/latest/LICENSE)
* [libunistring](https://www.gnu.org/software/libunistring/) -用于在C语言中处理Unicode字符串的库. [`GNU LGPL3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [libgiconv](https://www.gnu.要么g/software/libiconv/) -文本转换库. [`GNU LGPL2.1 (library)`](http://www.gnu.要么g/licenses/old-licenses/lgpl-2.1.html) 要么 [`GNU GPL3 (*iconv* program)`](http://www.gnu.要么g/licenses/gpl-3.0.html)
* [SDS](https://github.com/antirez/sds)  -简单的动态字符串；  一种用于以更简单的方式处理C字符串的库，但该库与普通C字符串函数兼容.  可通过 [clib](https://github.com/clibs/clib). [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [shoco](http://ed-von-schleck.github.io/shoco/) -小文本字符串的压缩器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [smaz](https://github.com/antirez/smaz) -高效的字符串压缩库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [utf8.h](https://github.com/sheredom/utf8.h) -单头utf8字符串函数. [`Unlicense`](https://unlicense.org/)
* [utf8proc](https://github.com/JuliaStrings/utf8proc) -小型干净的库，用于处理UTF-8 Unicode数据. [`License`](https://github.com/JuliaStrings/utf8proc/blob/master/LICENSE.md)

## Testing ##

* [CHEAT](http://users.jyu.fi/~sapekiis/cheat/) -非常简单的单元测试框架. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [Check](https://libcheck.github.io/check/) -C的单元测试框架. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [CMock](http://www.throwtheswitch.org/) -C语言的模拟/存根生成器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [cmocka](https://cmocka.org/) -带有模拟对象支持的单元测试框架. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [Criterion](https://criterion.readthedocs.io/en/master/) -KISS，非侵入式C测试框架. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [CUnit](http://cunit.sourceforge.net/) -C的另一个单元测试框架. [`GNU LGPL2.0`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [Cutest](https://github.com/rafael-santiago/cutest) -用于带有内存泄漏检测的单元测试的库（Linux，freeBSD和Windows）. [`GPL2`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [minunit](https://github.com/siu/minunit) -C的最小单元测试框架. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [Unity](http://www.throwtheswitch.org/) -C的简单单元测试框架. [`Expat`](https://directory.fsf.org/wiki/License:Expat)

## Text Editor Extensions ##

 尽管几乎任何体面的程序员的文本编辑器都支持C，但仍有一些扩展使其更令人愉悦.  这是由编辑器分类的.

### Atom ###

### Emacs ###

* [CEDET](http://cedet.sourceforge.net/)  -Emacs开发环境工具集合；  旨在为Emacs提供类似IDE的功能.  内置 [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Flycheck](https://github.com/flycheck/flycheck)  -现代语法检查.  对于C，它可以使用GCC或Clang作为后端. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Yasnippet](https://github.com/joaotavora/yasnippet) -模板系统，带有用于通用代码段的C模板. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)

### Vim ###

* [Syntastic](https://github.com/vim-syntastic/syntastic) -语法检查和整理. [`Do What The Fuck You Want To license`](https://github.com/vim-syntastic/syntastic/blob/master/LICENCE)
* [YouCompleteMe](http://valloric.github.io/YouCompleteMe/) -Vim的代码完成引擎. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)

## Tools ##

这是有用的程序列表，可帮助您编写和调试不是***编辑器，库或编译器的C代码.

* [Artistic Style](http://astyle.sourceforge.net/) -支持C的快速小型自动源代码格式化程序. [`GNU LGPL3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [address-sanitizer](https://github.com/google/sanitizers) -快速内存错误检测器. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [biicode](https://biicode.github.io/biicode/) -C的现代依赖项管理器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [c](https://github.com/ryanmjacobs/c)  -在命令行中一次编译并执行C个“脚本”.  也有shebang的支持. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [c99sh](https://github.com/RhysU/c99sh) -使用hash-bang运行C文件. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [CBMC](http://www.cprover.org/cbmc/)  -C绑定模型检查器；  用于验证数组边界，指针安全性和用户指定的断言的工具. [`Original BSD`](https://directory.fsf.org/wiki/License:BSD-4-Clause)
* [cdecl](https://cdecl.org/) -在线服务，可将C声明翻译成英文，反之亦然. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [cinclude2dot](https://www.flourish.org/cinclude2dot/) -图形包含使用Graphviz的C项目中的依赖项. [`Any GNU GPL version (due to underspecification in the file)`](https://directory.fsf.org/wiki/Cinclude2dot#tab=Details)
* [Complexity](https://www.gnu.org/software/complexity/) -用于测量C源代码复杂度的工具. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [CScout](https://www.spinellis.gr/cscout/) -用于C程序集合的源代码分析器和重构浏览器. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [DDD](https://www.gnu.org/software/ddd/ddd.html) -一系列命令行调试器的图形前端. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GDB](http://www.gnu.org/software/gdb/)  -GNU项目调试器；  C的调试器. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Glade](https://glade.gnome.org/) -RAD工具，可快速开发GTK + GUI. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [GMSL](https://gmsl.sourceforge.io/)  -GNU Make标准库；  GNU Make的其他功能的集合. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [GNU Global](https://www.gnu.org/software/global/) -与C一起使用的源代码标记工具. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [gprof](http://www.gnu.org/software/binutils/)  -性能分析工具.  GNU binutils的一部分. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Highlight](http://www.andre-simon.de/index.php) -将源代码转换为带有突出显示格式的文本. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [include-what-you-use](https://github.com/include-what-you-use/include-what-you-use)  -帮助找到不必要的内含物并提出修复建议.  基于LLVM / Clang（且仅适用于LLVM / Clang）. [`NCSA`](https://directory.fsf.org/wiki/License:NCSA)
* [indent](https://www.gnu.org/software/indent/)  -自动格式化C源代码，使其更易于阅读.  也可以从一种样式的源转换为另一种样式. [`GNU GPLv3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [rr](https://rr-project.org/) -记录非确定性执行以进行确定性调试的调试器. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [tup](http://gittup.org/tup/index.html) -非常快速的基于文件的跨平台构建系统. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [unifdef](http://dotat.at/prog/unifdef/) - Removes #ifdef 和 #if directives with their delimited text without touching any other part of the file. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause) 和 [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [Valgrind](http://www.valgrind.org/) -一系列动态分析工具，包括泄漏检查器. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)

## Utilities ##

这是“包罗万象”的类别，用于在其他任何地方都不适合的内容.

* [ApeTagLibs](https://github.com/jeremyevans/ape_tag_libs/tree/master/c) -用于处理APEv2标签的C库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [bfd](http://sourceware.org/binutils/docs/bfd/)  -用于处理二进制目标文件的库.  GNU binutils的一部分. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [cf4ocl](https://fakenmc.github.io/cf4ocl/)  -OpenCL的C框架；  用于开发和基准测试的跨平台面向对象框架  [OpenCL](https://www.khronos.要么g/opencl/) 项目. [`GNU LGPL3 (library)`](http://www.gnu.要么g/licenses/lgpl-3.0.html) 要么 [`GNU GPL3 (project code)`](http://www.gnu.要么g/licenses/gpl-3.0.html)
* [CommonMark](https://github.com/commonmark/commonmark-spec) -CommonMark规范的C实现. [`Various Licenses`](https://github.com/commonmark/commonmark-spec/blob/master/LICENSE)
* [CException](https://github.com/ThrowTheSwitch/CException) -C的异常实现. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [docopt.c](https://github.com/docopt/docopt.c) -命令行选项解析器的C实现. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [dyncall](http://www.dyncall.org/) -另一个外部函数接口库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [FANN](http://leenissen.dk/fann/wp/) - Fast Artifical Neural Network library; an implementation of neural networks. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Firm](https://pp.ipd.kit.edu/firm/)  -C库，提供适合在编译器中使用的基于图形的中间表示，优化和汇编代码生成.  带有相同许可证下的示例C前端. [`GNU LGPLv2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [Genann](https://github.com/codeplea/genann) -C语言中的简单神经网络库. [`Zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [gjrand](https://sourcef要么ge.net/projects/gjrand/) -随机数生成例程库. [`GNU GPL2.1`](http://www.gnu.要么g/licenses/old-licenses/gpl-2.0.html) 要么 [`GNU GPLv3`](http://www.gnu.要么g/licenses/gpl-3.0.html)
* [GNU FreeIPMI](https://www.gnu.org/software/freeipmi/index.html) -带内和带外IPMI实施. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GNU gperf](https://www.gnu.org/software/gperf/)  -完美的哈希函数生成器，给出了字符串列表.  输出C代码. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GNU Libffcall](https://www.gnu.org/software/libffcall/) -收集用于构建外部功能接口的库. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [gperftools](https://github.com/gperftools/gperftools) -收集用于测量和改进性能的实用程序. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [huffandpuff](https://github.com/adamierymenko/huffandpuff) -最小的霍夫曼编码器和解码器. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [kdtree](https://github.com/jtsiomb/kdtree) -用于KD树的简单库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [Kitsune](http://kitsune-dsu.com/) -用于动态软件更新的高效通用框架. [`GNU LGPL3 or later`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [libavl](http://adtinfo.org/libavl.html/index.html) -包含一系列自平衡二叉树的库. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [libbson](https://github.com/mongodb/libbson) -BSON实用程序库. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [libCello](http://libcello.org/) -向C语言引入高级编程的库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [libffi](https://github.com/libffi/libffi) -便携式外部功能接口库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libgit2](https://libgit2.org/) -Git的纯C实现. [`GNU GPL2 only, with a linking exception`](https://github.com/libgit2/libgit2/blob/master/COPYING)
* [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) -与iThings通信的跨平台协议库. [`GNU LGPLv2.1 要么 later (library)`](http://www.gnu.要么g/licenses/old-licenses/lgpl-2.1.html) 要么 [`GNU GPL2.1 要么 later (tools)`](http://www.gnu.要么g/licenses/old-licenses/gpl-2.0.html)
* [libnfc](https://github.com/nfc-tools/libnfc) -独立于平台的近场通信库. [`GNU LGPL3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [libPhenom](https://github.com/facebookarchive/libphenom)  -已弃用，此处用于存档.  用于构建高可扩展性和高性能系统的事件框架. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [ncurses](https://www.gnu.org/software/ncurses/) -彩色终端用户界面库. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [nope.c](https://github.com/riolet/WAFer) -基于C语言的超轻量软件平台，用于可扩展的服务器端和网络应用程序（对于C程序员，请考虑一下node.js）. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [pbc](https://github.com/cloudwu/pbc) -协议缓冲区库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [rabbitmq-c](https://github.com/alanxz/rabbitmq-c) -的客户端库 [RabbitMQ](https://www.rabbitmq.com/). [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [Ragel](http://www.colm.net/open-source/ragel/) -用于编译为C的状态机的DSL. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Tinyexpr](https://github.com/codeplea/tinyexpr) -微小的递归下降解析器，编译器和评估引擎，用于简单的数学表达式. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [uthash](http://troydhanson.github.io/uthash/) -哈希表实现，允许将现有结构轻松存储在哈希表中. [`1-clause BSD`](http://troydhanson.github.io/uthash/license.html)
* [cpu_features](https://github.com/google/cpu_features) -跨平台C99库，可在运行时获取cpu功能. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [pblog](https://github.com/google/pblog) - Small, low overhead, structured logging library intended for logging formware events.[`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [libelf](https://github.com/WolfgangSt/libelf) -C语言中的ELF目标文件访问库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [mcpp](http://mcpp.sourceforge.net/) -便携式C预处理器. [`2-clause BSD`](https://opensource.org/licenses/BSD-2-Clause)
* [libusb](https://libusb.info/) -通用访问USB设备. [`LGPL2.1`](https://github.com/libusb/libusb/blob/master/COPYING)
* [alsa-lib](https://www.alsa-project.org/main/index.php/Main_Page ) -用户空间库，可与ALSA进行交互. [`LGPL2.1`](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html)
* [Capstone](https://github.com/aquynh/capstone) -Dissasembly /反汇编程序框架. [`BSD 3-clause`](https://github.com/aquynh/capstone/blob/master/LICENSE.TXT)

## XML ##

 &gt;“ XML是废话.真的.没有任何借口.XML对于人类而言是令人讨厌的解析，甚至对于计算机而言也是解析的灾难.根本没有理由存在这种可怕的废话.”  -莱纳斯·托瓦尔兹

* [Expat](http://www.libexpat.org/) -面向流的XML解析器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libxml2](http://xmlsoft.org/) -符合标准的可移植XML解析器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [mini-xml](https://github.com/michaelrsweet/mxml)  -小型XML读写库.  除了C标准库外，没有任何依赖关系. [`Apache 2.0 with exceptions`](https://github.com/michaelrsweet/mxml/blob/master/LICENSE)
