<div class="github-widget" data-repo="inputsh/awesome-c"></div>
## awesome-c [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)[![List Status](https://api.travis-ci.org/aleksandar-todorovic/awesome-c.svg?branch=master)](https://travis-ci.org/aleksandar-todorovic/awesome-c)

 C 好东西的精选列表. 此列表包含*仅* [free software](https://en.wikipedia.org/wiki/Free_software) 对于代码，以及对物理资源不邪恶的卖家.

 **寻找维护者：**这个列表目前几乎不活跃. 我正在寻找可以让它再次变得伟大的维护者. 看 [#26](https://github.com/aleksandar-todorovic/awesome-c/issues/26) 了解更多信息，但过程很简单：添加或修复此列表中的一些内容，您将成为 850+ 星列表的贡献者.

此列表以前由维护 [@kozross](https://github.com/kozross) . 他决定将列表切换为 [new platform](https://notabug.org/koz.ross/awesome-c)，所以我决定分叉它，这样我们就可以将它保存在 GitHub 上.

Contents
========



## Build Systems ##

这些是用于自动构建和测试 C 项目的工具.

* [aimake](http://nethack4.org/projects/aimake/) - 旨在避免复杂配置的构建工具. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Autoconf](https://www.gnu.org/software/autoconf/autoconf.html)  - 可扩展的 M4 宏包，可生成 shell 脚本以自动配置软件源代码包.  Autotools 的一部分. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Automake](https://www.gnu.org/software/automake/automake.html)  - 自动生成符合 GNU 编码标准的“Makefile.in”文件的工具. 需要使用 Autoconf.  Autotools 的一部分. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [CMake](https://cmake.org/) - 用于跨平台构建、测试和打包的工具. [`3-clause BSD`](https://gitlab.kitware.com/cmake/cmake/raw/master/Copyright.txt)
* [Jam](https://www.perforce.com/documentation/jam-documentation)  - 构建系统，旨在比制作更容易. 隐式理解 C 构建规则. [`Jam License`](https://en.wikipedia.org/wiki/Perforce_Jam#License)
* [Libtool](https://www.gnu.org/software/libtool/)  - 通用库支持脚本.  Autotools 的一部分. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Meson](https://mesonbuild.com/)  - 极其快速、用户友好的构建系统. 基于忍者. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [Premake](https://github.com/premake/premake-core) - 为 Visual Studio、Xcode 或 GNU Make 等工具集构建脚本生成器. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [Ninja](https://github.com/ninja-build/ninja) - 专注于速度的小型、简单的构建系统. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [Bazel](https://bazel.build/) - 为各种操作系统和目标构建系统. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [Buck](https://buck.build/) - 构建由 Facebook 创建和使用的系统. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [Qbs](https://doc.qt.io/qbs/) - 用于软件项目的现代构建工具. [`LGPL3`](https://code.qt.io/cgit/qbs/qbs.git/tree/LICENSE.LGPLv3)
* [qmake](https://doc.qt.io/qt-5/qmake-manual.html) - 构建包含在 Qt 框架中的系统. [`GNU GPL3 with Qt Exception`](https://github.com/qt/qtbase/blob/5.11/LICENSE.GPL3-EXCEPT)
* [xmake](https://xmake.io/) - 基于 lua 的跨平台构建实用程序. [`Apache 2.0`](https://github.com/xmake-io/xmake/blob/master/LICENSE.md )

## Compilers ##

* [Clang](http://clang.llvm.org/)  - 用于 LLVM 的 C 编译器. 支持 C11. [`NCSA`](https://directory.fsf.org/wiki/License:NCSA)
* [CompCert](http://compcert.inria.fr/)  - 完全验证的 C 编译器. 支持几乎所有的C89. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [GCC](https://gcc.gnu.org/)  - 提供 C 编译器作为其编译器集的一部分. 支持 C11 和 OpenMP. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [PCC](http://pcc.ludd.ltu.se/)  - 可敬的 C 编译器. 支持 C99. [`Various free licenses`](http://pcc.ludd.ltu.se/licenses/)
* [TCC](https://bellard.org/tcc/)  - 微型 C 编译器； 一个小而快速的 C 编译器. 支持 C99（复杂类型除外）. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [Intel SPMD](http://ispc.github.io/) - C 语言变体的编译器，用于单程序、多数据编程. [`Various licenses`](https://github.com/ispc/ispc/blob/master/LICENSE.txt)
* [ccache](https://ccache.dev/) - 旨在加速重新编译的编译器缓存. [`GNU GPL3 or later`](https://ccache.dev/license.html)

## Compiler libraries ##

用于编译器、解释器和低级别项目的库.

* [yasm](http://yasm.tortall.net/) - Yasm Modular Assembler Project. [`2-clause BSD`](https://directory.fsf.org/wiki/License:BSD-2-Clause)

## Compression ##

* [libzip](https://libzip.org/) - 用于读取、创建和修改 zip 存档的 AC 库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [lzo](http://www.oberhumer.com/opensource/lzo/) - 非常快速的数据压缩库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [zlib](http://zlib.net/) - 非常漂亮但精致不显眼的压缩库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [bzip2](http://www.bzip.org/) - 无专利的高质量数据压缩器. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [lz4](https://lz4.github.io/lz4/) - 快速压缩算法.
* [snappy](https://github.com/google/snappy) - 快速压缩库（在 C++ 中实现，本地绑定到 C）.
* [zstd](http://facebook.github.io/zstd/) - 快速实时压缩算法 [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [quicklz](http://www.quicklz.com/index.php) - 快速压缩库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [pixz](https://github.com/vasi/pixz) - Pixz（发音为 pixie）是 `xz` 的并行索引版本. [`2-clause BSD`](https://directory.fsf.org/wiki/License:BSD-2-Clause)

## Crypto ##

* [GnuTLS](https://www.gnutls.org/) - 安全通信库，实现 SSL、TLS 和 DTLS. [`GNU LGPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [libgcrypt](https://gnupg.org/related_software/libgcrypt/) - 通用密码学库，具有一系列可用密码. [`GNU LGPL2.1or later (code)`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) 和 [`GNU GPL2.1 or later (manual 和 tools)`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [OpenSSL](https://www.openssl.org/) - SSL 和 TLS 协议的实施，还包括一个加密库. [`Dual Licensed under the OpenSSL License and the SSLeay License`](https://www.openssl.org/source/license.html)
* [libsodium](https://download.libsodium.org/doc/) - 现代且易于使用的加密库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libtomcrypt](https://www.libtom.net/) - 相当全面、模块化和便携的加密工具包. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [mbed TLS](https://tls.mbed.org/) - C 的另一个加密实现. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [libressl](https://www.libressl.org/) - OpenSSL 的现代化分支. [`Various Licenses`](https://cvsweb.openbsd.org/cgi-bin/cvsweb/~checkout~/src/lib/libssl/LICENSE?rev=1.12)

## Database ##

这列出了具有 C API 的数据库和数据存储.

* [BerkeleyDB](https://www.oracle.com/database/berkeley-db/) - 用于键值数据的高性能嵌入式数据库库. [`GNU AGPLv3`](https://www.gnu.org/licenses/agpl-3.0.html)
* [Hiredis](https://github.com/redis/hiredis) - Redis 的简约客户端库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [LMDB](https://github.com/LMDB/lmdb) - 超快速、超紧凑的键值嵌入式数据存储. [`OpenLDAP License`](https://directory.fsf.org/wiki/License:OLDAP-2.7)
* [MariaDB](https://mariadb.com/) - 强大、可扩展且可靠的 SQL 服务器，旨在成为 MySQL 的直接替代品. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [mongo-c-driver](http://mongoc.org/) - 高性能客户端库 [MongoDB](https://www.mongodb.com/). [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [PostgreSQL](https://www.postgresql.org/) - 强大的对象关系数据库系统. [`PostgreSQL licence`](https://opensource.org/licenses/postgresql)
* [recutils](https://www.gnu.org/software/recutils/) - 一组工具和一个 C 库，用于访问称为 recfiles 的人类可编辑的纯文本数据库文件. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Redis](https://redis.io/) - 高级键值存储. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [sophia](http://sophia.systems/) - 现代、可嵌入的键值数据库. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [SQLite](https://www.sqlite.org/about.html) - 具有 C 接口的独立、无服务器、零配置、事务性 SQL 数据库引擎. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [UnQLite](https://unqlite.org/) - 具有 C 接口的独立、无服务器、零配置、事务性 NoSQL 引擎. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)

## Deep Learning ##
* [Darknet](https://pjreddie.com/darknet/)  - 用 C 和 CUDA 编写的开源神经网络框架. 它速度快，易于安装，并支持 CPU 和 GPU 计算.

## Documentation Generation ##

* [Cxref](http://www.gedanken.org.uk/software/cxref/) - 生成 LaTeX、HTML、RTF 或 SGML 格式的 C 程序文档. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [DocOnce](https://hplgit.github.io/doconce/doc/web/index.html) - 适度标记的标记语言，可用于生成一系列格式. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [Doxygen](http://www.doxygen.nl/)  - 用于从注释源生成 C 文档的实际标准工具. 可以生成多种格式. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [GTK-Doc](https://www.gtk.或者g/gtk-doc/)  - 用于从注释源生成 C 文档的工具. 支持 Autotools. [`GNU GPL2.1 (code)`](http://www.gnu.或者g/licenses/old-licenses/lgpl-2.1.html) 或者 [`GNU FDL1.1`](https://www.gnu.或者g/licenses/old-licenses/fdl-1.1.html)

## Editors ##

这些是特别高级的 IDE 类型的编辑器. 如果您想要程序员的文本编辑器，请查看其他地方. 此外，无论您做出什么选择，最有可能支持 C.

* [Anjuta DevStudio](http://anjuta.org/) - GNOME IDE. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [Code::Blocks](http://www.codeblocks.org/) - 支持 C 的可扩展、可配置 IDE. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [CodeLite](https://codelite.org/) - 跨平台集成开发环境. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Eclipse](http://www.eclipse.org/ide/) - 用 Ja​​va 编写的 IDE. [`EPL`](https://directory.fsf.org/wiki/License:EPL-1.0)
* [Geany](https://www.geany.org/) - 非常小而快速的 IDE. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [KDevelop](https://www.kdevelop.org/) - 它的去向. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Qt Creator](https://www.qt.io/qt-features-libraries-apis-tools-and-ide/#ide)  - 使用 C++ 和 Qt 编写的跨平台 IDE，是 Qt SDK 的一部分. 支持 Clang 代码模型. [`GNU GPL3 with Qt exception`](https://github.com/qt-creator/qt-creator/blob/master/LICENSE.GPL3-EXCEPT)
* [Visual Studio Code](https://code.visualstudio.com/)  - 代码编辑，重新定义. 视觉工作室代码.

## Embedded Systems ##

这些项目允许人们使用微控制器和其他资源受限的架构.

### RTOS ###

实时操作系统 (RTOS) 旨在服务于以低延迟延迟处理数据的实时应用程序.

* [Amazon FreeRTOS](https://aws.amazon.com/freertos/) - 用于微控制器的 RTOS，可使小型低功耗边缘设备易于编程. [`MIT`](https://github.com/aws/amazon-freertos/blob/master/LICENSE)
* [ChibiOS](http://www.chibios.org/dokuwiki/doku.php) - 具有完整开发环境（HAL、驱动程序、支持文件和工具）的 RTOS. [`Various Licenses`](http://www.chibios.org/dokuwiki/doku.php?id=chibios:licensing:start)
* [Contiki](http://www.contiki-os.org/) - 将低成本、低功耗的微控制器连接到互联网. [`3-clause BSD`](https://github.com/contiki-os/contiki/blob/master/LICENSE)
* [Zephyr Project](https://www.zephyrproject.org/) - 可扩展的实时 RTOS，支持多种硬件架构，针对资源受限的设备进行了优化. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [RIOT OS](https://www.riot-os.org/) - 实时多线程操作系统，支持物联网中常见的一系列设备. [`LGPL-2.1`](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html)

## Environments ##

这是一个技术列表，旨在将 Windows 带入 21 世纪，支持 C.

* [Cygwin](https://cygwin.com/) - 旨在在 Windows 下广泛模拟 POSIX 兼容环境. [`Various Licenses`](https://cygwin.com/licensing.html)
* [MinGW-w64](http://mingw-w64.yaxm.org/doku.php/start) - 支持 64 位的 Windows 上 C 语言开发的极简环境. [`Various Licenses`](http://mingw.org/license)

## Frameworks ##

本节有大型库，提供数据结构和您期望“现代”标准库提供的其他内容.

* [APR](http://apr.apache.org/)  - Apache 便携式运行时； 另一个跨平台实用函数库. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [C Algorithms](https://fragglet.github.io/c-algorithms/) - C的常用算法和数据结构的集合. [`ISC`](https://directory.fsf.org/wiki/License:ISC)
* [C Macro Collections](https://github.com/LeoVen/C-Macro-Collections) - 仅标头、宏生成、通用且类型安全的 C 集合. [`MIT`](https://spdx.org/licenses/MIT.html)
* [CPL](http://www.eso.org/sci/software/cpl/)  - 通用管道库； 一组库，旨在成为一个全面、高效和强大的软件工具包. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [EFL](https://www.enlightenment.org/) - 大量有用的数据结构和函数.
* [GLib](https://wiki.gnome.org/Projects/GLib) - 实用功能和结构库，旨在便携、高效和强大. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [GIO](https://developer.gnome.org/gio/) - 现代且易于使用的 VFS API. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [GObject](https://developer.gnome.org/gobject/stable/) - C 的面向对象系统和对象模型. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [libnih](https://github.com/keybuk/libnih) - C 函数和结构的轻量级库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [libU](http://www.koanlogic.com/libu/) - 基本实用程序的小型库，包括内存分配、字符串操作和日志记录. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [PBL](http://www.mission-base.com/peter/source/) - 大型实用程序库，具有数据结构等功能. [`GNU LGPL2.1 或者 later (library)`](http://www.gnu.或者g/licenses/old-licenses/lgpl-2.1.html) 或者 [`GNU GPL2.1 或者 later (test code)`](http://www.gnu.或者g/licenses/old-licenses/gpl-2.0.html)
* [qlibc](http://wolkykim.github.io/qlibc/) - 简单而强大的 C 库，旨在作为 GLib 的替代品，同时专注于小巧轻便. [`qLib license`](https://github.com/wolkykim/qlibc/blob/master/LICENSE) （如同 [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD))
* [stb](https://github.com/nothings/stb) - C 的单文件库范围. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [libsrt](https://faragon.github.io/libsrt.html) - C 的安全实时库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)


## Game Programming ##

### Engines ###

这些是作为 C 游戏编程代码的示例提供的.

* [Corange](https://github.com/orangeduck/Corange) - 纯 C 语言的游戏引擎. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [Darkplaces](https://icculus.org/twilight/darkplaces/) - Quake2 引擎的修改版本. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [ioquake3](https://ioquake3.org/) - Quake3 引擎，终于解放了. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Orx](http://orx-project.org/) - 便携式、轻量级、基于插件、数据驱动、面向 2D 的游戏引擎. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [Quake](https://github.com/id-Software/Quake) - 地震引擎. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Quake2](https://github.com/id-Software/Quake-2) - Quake2 引擎. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Spearmint](https://clover.moe/spearmint/) - 专为 FPS 游戏设计的引擎. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)

### Resources ###

这些是对游戏编程有用的各种库.

* [Allegro](https://liballeg.org/) - 跨平台、视频游戏开发和多媒体库. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [Chipmunk2D](http://chipmunk-physics.net/) - 快速轻量级的 2D 游戏物理库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [CSFML](https://www.sfml-dev.org/download/csfml/) - 绑定 [SFML](https://www.sfml-dev.org/index.php) 在 C. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [FreeGLUT](http://freeglut.sourceforge.net/)  - 替代 OpenGL 实用工具包. 允许使用 OpenGL 上下文创建和管理窗口. [`X11`](https://directory.fsf.org/wiki/License:X11)
* [GLFW](https://www.glfw.org/) - 用于使用 OpenGL 上下文创建窗口的多平台库. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [libao](https://xiph.org/ao/) - 具有多种输出的跨平台音频库. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [RetroArch](https://www.libretro.com/) - 参考前端 [libretro](https://www.libretro.com/). [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [SDL and SDL2](https://www.libsdl.org/)  - 跨平台开发库，旨在通过 OpenGL 提供对音频、键盘、鼠标、操纵杆和图形硬件的低级访问.  SDL2 是最新版本. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [raylib](https://www.raylib.com/) - 用于学习视频游戏编程的简单易用的库. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)

## Generic Programming ##

* [klib](http://attractivechaos.github.io/klib/#About) - 通用算法和数据结构的小型轻量级实现. [`MIT`](https://en.wikipedia.org/wiki/MIT_License)

## Graphics ##

* [Cairo](https://www.cairographics.或者g/) -2D图形库. [`GNU LGPL2.1`](http://www.gnu.或者g/licenses/old-licenses/lgpl-2.1.html) 或者 [`MPLv1.1`](https://direct或者y.fsf.或者g/wiki/License:MPL-1.1)
* [Cogl](https://github.com/rib/cogl-web/wiki) - GPU 图形和实用程序 API. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [Clutter](https://blogs.gnome.org/clutter/get-it/) - 基于 OpenGL 的 UI 库. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [giflib](https://sourceforge.net/projects/giflib/) - 用于阅读和编写 gif 图像的库. [`MIT`](https://spdx.org/licenses/MIT.html)
* [heman](https://github.com/prideout/heman) - 处理高度贴图、法线贴图、距离场等的小型图像实用程序库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libcaca](https://github.com/cacalabs/libcaca) - 用于基于终端的界面的 ASCII 渲染器. [`WTFPLv2`](http://www.wtfpl.net/txt/copying/)
* [libimagequant](https://pngquant.org/lib/) - 用于将 RGBA 图像高质量转换为 8 位索引彩色图像的小型便携式库. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [libjpeg-turbo](https://libjpeg-turbo.org/) - 用于读取和写入 JPEG 文件的更快的库. [`Various Licenses`](https://libjpeg-turbo.org/About/License)
* [libpng](http://www.libpng.org) - 官方 PNG 参考库. [`libpng license`](http://www.libpng.org/pub/png/src/libpng-LICENSE.txt)
* [libxmi](https://www.gnu.org/software/libxmi/) - 用于光栅化 2D 矢量图形的函数库. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [mozjpeg](https://github.com/mozilla/mozjpeg) - 改进的 JPEG 编码器. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)

### Graphic APIs ###

* [OpenGL](https://www.opengl.org/)  - 行业采用 2D 和 3D 图形 API. 更多资源在 [awesome-opengl](https://github.com/eug/awesome-opengl).
* [OpenGL ES](https://www.khronos.org/opengles/) - 业界为移动和嵌入式设备采用了 2D 和 3D 图形 API.
* [OpenGL SC](https://www.khronos.org/openglsc/) - 需要系统安全认证的行业的图形和计算标准.
* [Vulkan](https://www.khronos.org/vulkan/)  - 用于现代跨平台开发的显式图形和计算 API. 更多资源在 [awesome-vulkan](https://github.com/vinjn/awesome-vulkan).

## Graphical User Interface ##

这些是专门 [widget toolkits](https://en.wikipedia.org/wiki/Widget_toolkit).

* [GTK+](https://www.gtk.org/) - 跨平台小部件工具包. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/) - 另一个跨平台小部件工具包. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [Tk](http://www.tcl.tk/)  - 基本的小部件工具包.  Tcl/Tk 的一部分. [`Tcl/Tk License`](http://www.tcl.tk/software/tcltk/license.html)
* [XForms Toolkit](http://xforms-toolkit.org/) - 为 XWindow 系统设计的 Widget 工具包. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [nuklear](https://github.com/vurtun/nuklear) - 单头 ANSI C gui 库. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [libui](https://github.com/andlabs/libui) - 简单且可移植（但并非不灵活）的 GUI 库. [`MIT`](https://github.com/andlabs/libui/blob/master/LICENSE)
* [LCUI](https://github.com/lc-soft/LCUI/) - 用于使用 C、XML 和 CSS 构建用户界面的小型 C 库. [`MIT`](https://github.com/lc-soft/LCUI/blob/develop/LICENSE.TXT)

## Hashing ##

所有与哈希相关的库，无论是否加密.

* [jwHash](https://github.com/watmough/jwHash) - 快速哈希表实现. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [xxHash](http://cyan4973.github.io/xxHash/) - 极快的非加密散列算法. [`2-clause BSD`](https://directory.fsf.org/wiki/License:BSD-2-Clause)
* [murmur](https://github.com/ispc/ispc) - MurMur 散列的 C 实现. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [t1ha](https://github.com/leo-yuriev/t1ha) - 快速正哈希库. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)

## Image Processing ##

* [libccv](http://libccv.org) - 现代计算机视觉库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)

## JSON ##

* [Jansson](http://www.digip.org/jansson/) - 用于编码、解码和操作 JSON 的 C 库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [jsmn](https://zserge.com/jsmn.html) - 简约的 JSON 解析器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [json-c](https://github.com/json-c/json-c/wiki) - 用于处理 JSON 的库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [WJElement](https://github.com/netmail-open/wjelement/wiki) - 高级 JSON 操作库，支持 JSON Schema. [`LGPL, any version`](https://github.com/netmail-open/wjelement/)
* [YAJL](https://lloyd.github.io/yajl/) - 快速 C JSON 流解析器库. [`ISC`](https://directory.fsf.org/wiki/License:ISC)

## Learning, Reference and Tutorials ##

This is a list of resources for learning C programming in general, or something useful relating to C programming.

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
* [POSIX Threads Programming tutorial](https://computing.llnl.gov/tutorials/pthreads/) （有点过时，但大部分仍然有效且有用）
* [The GNU C Programming Tutorial](http://www.crasseux.com/books/ctut.pdf) （在线PDF）
* [Templating in C](http://blog.pkh.me/p/20-templating-in-c.html)

#### Intermediate ####

* [8 gdb tricks you should know](https://blogs.oracle.com/linux/8-gdb-tricks-you-should-know-v2)
* [10 C99 tricks](https://blog.noctua-software.com/c-tricks.html)
* [Diving into concurrency: trying out mutexes and atomics](https://jvns.ca/blog/2014/12/14/fun-with-threads/)
* [Introduction to OpenMP](https://www.youtube.com/playlist?list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG) （视频）
* [OpenMP tutorial](https://computing.llnl.gov/tutorials/openMP/) （针对 OpenMP3 标准）
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

* [C: A Reference Manual 5E](http://careferencemanual.com/) - C99 的完整参考书.
* [C Pocket Reference](http://shop.oreilly.com/product/9780596004361.do) - C99 简明参考书.
* [The C Programming Language 2E](https://en.wikipedia.org/wiki/The_C_Programming_Language) - 关于 C 语言的原著，由其作者编写.

#### Beginner ####

* [C Primer Plus 6E](https://www.pearson.com/us/higher-education/program/Prata-C-Primer-Plus-6th-Edition/PGM4399.html) - 完整的 C11 编程教程.
* [C Programming: A Modern Approach](http://knking.com/books/c2/index.html) - 学习 C 基础知识的优秀书籍.
* [Head First C](http://shop.oreilly.com/product/0636920015482.do) - 学习 C 的“Head-first”风格书籍.

#### Intermediate ####

* [21st Century C](http://shop.oreilly.com/product/0636920033677.do) - 非常好的*第二本* C 编程书籍.
* [Understanding and Using C Pointers](http://shop.oreilly.com/product/0636920028000.do) - 关于 C 中指针的深入资源.
* [ZeroMQ](http://shop.oreilly.com/product/0636920026136.do) - 将 ZeroMQ 与 C 结合使用的书籍.

#### Advanced ####

* [Expert C Programming: Deep C Secrets](https://dl.acm.org/citation.cfm?id=179241) - 有趣、深入和*有趣*地了解 C 的内部结构.

## Macros ##

* [P99](http://p99.gforge.inria.fr/) - 用于实现高级功能的宏套件，例如默认函数参数、范围绑定资源等（需要 C99） [`Q Public License`](https://tldrlegal.com/license/q-public-license-1.0-(qpl-1.0)#summary)

## Memory Allocators ##

各种系统和平台的内存分配器的实现.

* [jemalloc](http://jemalloc.net/) - 强调避免碎片和可扩展并发支持的通用 malloc(3) 实现，常用于生产系统. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [dlmalloc](http://g.oswego.edu/pub/misc/malloc.c) - Doug Lea 的 malloc(3) 实现，可用于学术和研究目的. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [Hoard](http://hoard.org/) - 适用于 Linux、Windows、Mac 和 Solaris 的快速、可扩展且内存高效的 Malloc. [`GNU GPL2`](http://www.gnu.org/licenses/gpl-3.0.html)
* [nedmalloc](http://www.nedprod.com/programs/portable/nedmalloc/) - 用 C 编写的极其快速的可移植线程缓存 malloc(3) 实现. [`GNU GPL2`](http://www.gnu.org/licenses/gpl-3.0.html)
* [rpmalloc](https://github.com/rampantpixels/rpmalloc) - 跨平台，无锁内存分配器. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)


## Multimedia ##

* [FFMPEG](https://www.ffmpeg.或者g/) - 完整的跨平台解决方案，用于录制、转换和流式传输音频和视频. [`GNU LGPL2.1 或者 later`](http://www.gnu.或者g/licenses/old-licenses/lgpl-2.1.html) 或者 [`GNU GPL2.1 或者 later (some parts)`](http://www.gnu.或者g/licenses/old-licenses/gpl-2.0.html)
* [GStreamer](https://gstreamer.freedesktop.org/) - 音频和视频媒体框架. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [lodepng](https://lodev.org/lodepng/) - 简单的 PNG 图像解码器和编码器，不需要其他依赖项. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [libsoup](https://wiki.gnome.org/action/show/Projects/libsoup?action=show&redirect=LibSoup)  - GNOME HTTP 客户端/服务器库. 使用 GObject. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [libmpv](https://mpv.io/)  - 音乐播放库. 使用 ``./waf configure --disable-cplayer --enable-libmpv-shared`` 进行编译，使其没有音乐播放器. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [libsoundio](http://libsound.io/)  - 用于跨平台、实时音频输入和输出的库. 有一系列的后端. [`Expat`](https://directory.fsf.org/wiki/License:Expat)


## Networking and Internet ##

* [asnlc](http://lionet.info/asn1c/compiler.html) - 将 ASN.1 规范编译成 C 源代码. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [czmq](http://czmq.zeromq.org/) - ZeroMQ 的高级绑定. [`MPL2.0`](https://www.gnu.org/licenses/license-list.html#MPL-2.0)
* [GNU adns](https://www.gnu.org/software/adns/) - 高级、易于使用、支持异步的 DNS 客户端库和实用程序. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GNU SASL](https://www.gnu.org/software/gsasl/) - 简单认证和安全层的实现以及一些常见的 SASL 机制. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GnuTLS](https://www.gnutls.org/) - 安全通信库，实现 SSL、TLS 和 DTLS. [`GNU LGPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [gumbo-parser](https://github.com/google/gumbo-parser) - C99 中的 HTML5 解析库. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [http-parser](https://github.com/nodejs/http-parser) - HTTP 请求/响应解析器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [ldns](https://www.nlnetlabs.nl/projects/ldns/index.html) - 简化 DNS 编程的库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [libcurl](https://curl.haxx.se/libcurl/) - 客户端 URL 传输库，支持多种格式. [`curl license`](https://curl.haxx.se/docs/copyright.html)
* [LibEtPan](http://www.etpan.org/) - 为 IMAP、SMTP、POP 和 NNTP 提供高效网络的邮件库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [libev](http://software.schmorp.de/pkg/libev.html) - 另一个事件循环. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [libuv](http://libuv.org/) - 跨平台异步 I/O. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libevent](http://libevent.org/) - 网络服务器的事件循环替换. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [libgss](https://www.gnu.org/software/gss/) - 通用安全服务. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [libhttpd](https://hughes.com.au/products/libhttpd/) - 用于向应用程序或嵌入式设备添加基本 Web 服务器功能的库. [`GNU GPL2`](http://www.gnu.org/licenses/gpl-3.0.html)
* [libidn](https://www.gnu.org/software/libidn/) - Stringprep、Punycode 和 IDNA 规范的实施. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [libmicrohttpd](https://www.gnu.org/software/libmicrohttpd/) - 小型 C 库，可以轻松地将 HTTP 服务器作为另一个应用程序的一部分运行. [`GNU LGPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [libsagui](https://risoflora.github.io/libsagui/) - Sagui 是一个跨平台的 C 库，有助于开发 Web 服务器或框架. [`GNU LGPL3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [libvldmail](https://github.com/dertuxmalwieder/libvldmail) - 您友好的电子邮件地址验证库. [`WTFPLv2`](http://www.wtfpl.net/txt/copying/)
* [lwan](https://lwan.ws/) - 实验性、可扩展、高性能的 HTTP 服务器. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [mongoose](https://cesanta.com/) - 用于 C 语言的嵌入式 Web 服务器. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [nanomsg](https://github.com/nanomsg/nanomsg) - ZeroMQ 的基于 C 的实现. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [OpenSSL](https://www.openssl.org/) - SSL 和 TLS 协议的实施，还包括一个加密库. [`Dual Licensed under the OpenSSL License and the SSLeay License`](https://www.openssl.org/source/license.html)
* [oSip](https://www.gnu.org/software/osip/) - C 中的 SIP 实现，无需额外的依赖项. [`GNU LGPLv2.1 or later`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [pig](https://github.com/rafael-santiago/pig) - Linux 数据包制作工具. [`GPL2`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [s2n](https://github.com/awslabs/s2n) - TLS/SSL 协议的 C99 实现，旨在简单、快速且将安全性作为优先事项. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [socket99](https://github.com/silentbicycle/socket99) - BSD 套接字 API 的 C99 包装器. [`ISC`](https://directory.fsf.org/wiki/License:ISC)
* [Tox](https://tox.chat/) - Communication platform, designed to be a Skype-killer. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [twitc](https://github.com/sinemetu1/twitc) - 用于与 Twitter OAuth API 交互的迷你 C 库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [librg](https://github.com/librg/librg) - 用于构建简单而优雅的跨平台 mmo 客户端-服务器解决方案的库. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)

### Web Frameworks ###

* [balde](https://balde.rgm.io/) - 基于 GLib 的 C 微框架. [`GNU LGPLv2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [onion](https://www.coralbits.com/libonion/) - 用于创建简单 HTTP 服务器和 Web 应用程序的 C 库. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [kore](https://kore.io/) - 易于使用、可扩展且安全的 Web 应用程序框架，用于用 C 语言编写 Web API.
* [klone](http://www.koanlogic.com/klone/) - KLone 是一个功能齐全的多平台 Web 应用程序开发框架.
* [duda](http://duda.io/) - Duda I/O 是一个事件驱动的高性能 Web 服务框架，用 C 语言编写. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)

## Numerical ##

* [apophenia](http://apophenia.info/) - 统计和科学计算库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [ATLAS](http://math-atlas.sourceforge.net/) - 自动调整的线性代数软件. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [BLAS](http://www.netlib.org/blas/)  - 基本线性代数子程序； 一组提供向量和矩阵运算的例程. [`BLAS license`](http://www.netlib.org/blas/#_licensing)
* [CDFLIB](https://people.sc.fsu.edu/~jburkardt/c_src/cdflib/cdflib.html)  - 具有评估各种标准概率分布的累积密度函数的例程的库. 也可以在给定其他参数的情况下计算 CDF 的一个参数.  （未颁发许可证）
* [cmathl](https://scientificc.github.io/cmathl/)  - 具有多种数学函数和 CMake 构建支持的纯 C 数学库. 寻求接近 C89/C90 的可移植性. [`MIT`](https://github.com/ScientificC/cmathl/blob/master/LICENSE)
* [Cuba](http://www.feynarts.de/cuba/) - 多维数值积分库. [`GNU LGPLv3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [FFTW](http://www.fftw.org/)  - 西方最快的傅里叶变换； 高度优化的快速傅里叶变换例程. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [FLINT](http://flintlib.org/)  - 数论快速库； 一个支持数字、多项式、幂级数和矩阵等算术的库. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [GLPK](https://www.gnu.org/software/glpk/)  - GNU 线性规划工具包； 为解决大规模线性规划、混合整数规划和其他相关问题而设计的软件包. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GMP](https://gmplib.org/)  - GNU 多重精度算术库； 一个用于任意精度算术的库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 和 [`GNU LGPLv3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [GNU MPC](http://www.multiprecision.org/mpc/) - 复数算术库. [`GNU LGPL3 or later`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [GNU MPFR](https://www.mpfr.或者g/index.html) - 任意精度浮点运算库. [`GNU LGPL3 或者 later`](http://www.gnu.或者g/licenses/lgpl-3.0.html) 或者 [`GNU LGPL2.1 或者 later (until version 2.4.x)`](http://www.gnu.或者g/licenses/old-licenses/lgpl-2.1.html)
* [GNU MPRIA](https://www.gnu.org/software/mpria/) - 用于多精度有理区间运算的便携式数学库. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GSL](http://www.gnu.org/software/gsl/)  - GNU 科学图书馆； 一个复杂的数值库. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [igraph](https://igraph.org/) - 用于创建和操作大型图形的库. [`GNU GPL2`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [KISS FFT](https://sourceforge.net/projects/kissfft/) - 非常简单的快速傅立叶变换库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [LAPACKE](http://www.netlib.org/lapack/lapacke.html) - C interface to [LAPACK](http://www.netlib.org/lapack/). [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [PARI/GP](http://pari.math.u-bordeaux.fr/)  - 数论计算机代数系统； 包括 C 的编译器. [`GNU GPL2.1 or later`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [PETSc](https://www.mcs.anl.gov/petsc/) - 一套数据结构和例程，用于由偏微分方程建模的科学应用程序的可扩展并行解决方案. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [PROB](https://people.sc.fsu.edu/~jburkardt/c_src/prob/prob.html) - 处理各种离散和连续概率密度函数的库.  [`GNU LGPL3`](https://people.sc.fsu.edu/~jburkardt/txt/gnu_lgpl.txt)
* [Yeppp!](https://bitbucket.org/MDukhan/yeppp) - 速度非常快，SIMD 优化的数学库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)

## Parallel Programming ##

* [cchan](http://repo.hu/projects/cchan/) - 用于线程间通信的通道构造的小型库. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [ck](http://concurrencykit.org/) - 并发原语、安全内存回收机制和非阻塞数据结构. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [mill](http://libmill.org/) - C 中的 Go 风格并发. [`X11`](https://directory.fsf.org/wiki/License:X11)
* [libdill](http://libdill.org/) - C 中的结构化并发. [`X11`](https://directory.fsf.org/wiki/License:X11)
* [MPICH](http://www.mpich.org/) - MPI 的另一个实现. [`MPICH licence`](http://git.mpich.org/mpich.git/blob_plain/6aab201f58d71fc97f2c044d250389ba86ac1e3c:/COPYRIGHT)
* [OpenMP](https://www.openmp.org/) - 一组 C 编译指示，旨在实现代码的轻松并行化. [`3-clause BSD`](https://opensource.org/licenses/BSD-3-Clause)
* [OpenMPI](https://github.com/open-mpi/ompi) - 消息传递接口实现. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [pth](https://www.gnu.org/software/pth/) - 用于多线程执行的基于优先级的非抢占式调度的便携式实现. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [pthreads](https://en.wikipedia.org/wiki/POSIX_Threads) - POSIX 线程库.
* [SLEPc](https://bitbucket.org/slepc/slepc) - 用于在并行计算机上解决大型、稀疏特征值问题的软件库. [`GNU LGPL3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [TinyCThread](https://tinycthread.github.io/) - C11 线程 API 的可移植、小型实现. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)

## Parsers ##

* [hammer](https://github.com/abiggerhammer/hammer) - 二进制格式的解析器组合器. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [iniparser](https://github.com/ndevilla/iniparser) - `.ini` 文件的解析器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libconfini](https://github.com/madmurphy/libconfini) - 另一个 INI 解析器. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [libYAML](https://pyyaml.org/wiki/LibYAML) - YAML 1.1 解析器和发射器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [mpc](https://github.com/orangeduck/mpc) - 解析器组合器库. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [libucl](https://github.com/vstakhov/libucl) - 通用配置库解析器. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)


## Regex ##

 &gt; “有些人在遇到问题时会想‘我知道，我会使用正则表达式’.现在他们有两个问题.”  - 杰米扎温斯基.

* [PCRE](http://www.pcre.org/) - 与 Perl 5 相同的正则表达式的实现. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [regexp4](https://github.com/nasciiboy/recursiveregexpraptor-4) - 使用自己的语法简单而完整地实现正则表达式. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [SLRE](https://github.com/cesanta/slre)  - 超轻正则​​表达式库；  Perl 正则表达式语法子集的一个非常小的实现. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [sregex](https://github.com/openresty/sregex) - 非回溯基于 NFA/DFA 的 Perl 兼容正则表达式引擎库. [`3-clause BSD`](https://opensource.org/licenses/BSD-3-Clause)
* [TRE](https://github.com/laurikari/tre/) - 符合 POSIX 标准、功能齐全的正则表达式库. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)

## Serialization ##

* [binn](https://github.com/liteserver/binn) - 二进制序列化格式意味着紧凑、快速和易于使用. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [c-capnproto](https://github.com/jmckaskill/c-capnproto) - Cap&#39;n Proto 序列化协议的实施. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [cmp](https://github.com/camgunz/cmp) - 实施 [MessagePack](https://msgpack.org/) 序列化协议. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libavro](http://avro.apache.org/docs/current/api/c/index.html#_introduction_to_avro_c) - Avro 数据序列化系统的 C 实现. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [mpack](https://github.com/ludocode/mpack) - 的另一个实现 [MessagePack](https://msgpack.org/) 序列化协议. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [netstring-c](https://github.com/liteserver/netstring-c) - 网络字符串编码器和解码器. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [protobuf-c](https://github.com/protobuf-c/protobuf-c) - 在 C 中实现 Google Protocol Buffer. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [xdr](https://en.wikipedia.org/wiki/External_Data_Representation)  - 外部数据表示； 数据序列化的标准.


## Source Code Collections ##

这包含小源代码的集合. 如果您想要大而集成的东西，请查看框架部分.

* [CCAN](http://ccodearchive.net/)  - 以 Perl 的 CPAN 为模型，这是一大堆 C 代码的集合. 完整列表是 [here](http://ccodearchive.net/list.html).
* [clib](https://github.com/clibs/clib) - C 的包管理器.带有 [bunch of libraries of its own](https://github.com/clibs/clib/wiki/Packages). [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [gnulib](https://www.gnu.org/software/gnulib/) - 通用 GNU 代码的集合.
* [libdjb](http://www.fefe.de/djb/) - 做各种事情的图书馆集合. [`(Apparently) Public Domain`](https://creativecommons.org/share-your-work/public-domain/)

## Standard Libraries ##

这包含标准 C 库.

* [Bionic](https://github.com/aosp-mirror/platform_bionic) - 谷歌的 C 标准库，为 Android 开发. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [dietlibc](http://www.fefe.de/dietlibc/) - 为尽可能小的二进制文件设计的 C 标准库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [glibc](http://www.gnu.org/software/libc/)  - GNU C 库；  C 标准库的实现. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [musl](http://www.musl-libc.org/)  - 标准 C 库，兼容 POSIX 2008 和 C11. 专为静态链接而设计. [`Expat`](https://directory.fsf.org/wiki/License:Expat)

## String Manipulation ##

* [bstrlib](http://bstring.sourceforge.net/) - 更好的字符串库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause) 和 [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [ICU](http://site.icu-project.org/)  - Unicode 的国际组件； 支持 Unicode 的库. [`ICU license`](http://source.icu-project.org/repos/icu/icu/tags/latest/LICENSE)
* [libunistring](https://www.gnu.org/software/libunistring/) - 用于在 C 中操作 Unicode 字符串的库. [`GNU LGPL3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [libgiconv](https://www.gnu.或者g/software/libiconv/) - 文本转换库. [`GNU LGPL2.1 (library)`](http://www.gnu.或者g/licenses/old-licenses/lgpl-2.1.html) 或者 [`GNU GPL3 (*iconv* program)`](http://www.gnu.或者g/licenses/gpl-3.0.html)
* [SDS](https://github.com/antirez/sds)  - 简单的动态字符串； 一个以更简单的方式处理 C 字符串的库，但它与普通的 C 字符串函数兼容. 可通过 [clib](https://github.com/clibs/clib). [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [shoco](http://ed-von-schleck.github.io/shoco/) - 小文本字符串的压缩器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [smaz](https://github.com/antirez/smaz) - 高效的字符串压缩库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [utf8.h](https://github.com/sheredom/utf8.h) - 单头 utf8 字符串函数. [`Unlicense`](https://unlicense.org/)
* [utf8proc](https://github.com/JuliaStrings/utf8proc) - 用于处理 UTF-8 Unicode 数据的小型、干净的库. [`License`](https://github.com/JuliaStrings/utf8proc/blob/master/LICENSE.md)

## Testing ##

* [CHEAT](http://users.jyu.fi/~sapekiis/cheat/) - 非常简单的单元测试框架. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [Check](https://libcheck.github.io/check/) - C 的单元测试框架. [`GNU LGPL2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [CMock](http://www.throwtheswitch.org/) - C 的模拟/存根生成器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [cmocka](https://cmocka.org/) - 支持模拟对象的单元测试框架. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [Criterion](https://criterion.readthedocs.io/en/master/) - KISS，非侵入式 C 测试框架. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [CUnit](http://cunit.sourceforge.net/) - C 的另一个单元测试框架. [`GNU LGPL2.0`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [Cutest](https://github.com/rafael-santiago/cutest) - 带有内存泄漏检测的单元测试库（Linux、freeBSD 和 Windows）. [`GPL2`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [minunit](https://github.com/siu/minunit) - C 的最小单元测试框架. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [Unity](http://www.throwtheswitch.org/) - C 的简单单元测试框架. [`Expat`](https://directory.fsf.org/wiki/License:Expat)

## Text Editor Extensions ##

虽然几乎任何体面的程序员的文本编辑器都支持 C，但有一些扩展使其更令人愉快. 这是按编辑器分类的.

### Atom ###

### Emacs ###

* [CEDET](http://cedet.sourceforge.net/)  - Emacs开发环境工具合集； 旨在为 Emacs 提供类似 IDE 的功能. 内置. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Flycheck](https://github.com/flycheck/flycheck)  - 现代语法检查. 对于 C，它可以使用 GCC 或 Clang 作为后端. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Yasnippet](https://github.com/joaotavora/yasnippet) - 模板系统，带有通用代码片段的 C 模板. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)

### Vim ###

* [Syntastic](https://github.com/vim-syntastic/syntastic) - 语法检查和 linting. [`Do What The Fuck You Want To license`](https://github.com/vim-syntastic/syntastic/blob/master/LICENCE)
* [YouCompleteMe](http://valloric.github.io/YouCompleteMe/) - Vim 的代码完成引擎. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)

## Tools ##

这是一个有用的程序列表，可帮助您编写和调试 C 代码，它们*不是*编辑器、库或编译器.

* [Artistic Style](http://astyle.sourceforge.net/) - 支持 C 的快速小型自动源代码格式化程序. [`GNU LGPL3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [address-sanitizer](https://github.com/google/sanitizers) - 快速内存错误检测器. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [biicode](https://biicode.github.io/biicode/) - C 的现代依赖管理器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [c](https://github.com/ryanmjacobs/c)  - 在命令行上一次性编译和执行 C“脚本”. 也有 shebang 支持. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [c99sh](https://github.com/RhysU/c99sh) - 使用 hash-bang 运行 C 文件. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [CBMC](http://www.cprover.org/cbmc/)  - C 有界模型检查器； 用于验证数组边界、指针安全和用户指定断言的工具. [`Original BSD`](https://directory.fsf.org/wiki/License:BSD-4-Clause)
* [cdecl](https://cdecl.org/) - 将 C 声明翻译成英文的在线服务，反之亦然. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [cinclude2dot](https://www.flourish.org/cinclude2dot/) - 图包括使用 Graphviz 的 C 项目中的依赖项. [`Any GNU GPL version (due to underspecification in the file)`](https://directory.fsf.org/wiki/Cinclude2dot#tab=Details)
* [Complexity](https://www.gnu.org/software/complexity/) - 用于测量 C 源代码复杂性的工具. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [CScout](https://www.spinellis.gr/cscout/) - 用于 C 程序集合的源代码分析器和重构浏览器. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [DDD](https://www.gnu.org/software/ddd/ddd.html) - 一系列命令行调试器的图形前端. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GDB](http://www.gnu.org/software/gdb/)  - GNU 项目调试器；  C的调试器. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Glade](https://glade.gnome.org/) - 支持快速开发 GTK+ GUI 的 RAD 工具. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [GMSL](https://gmsl.sourceforge.io/)  - GNU Make 标准库；  GNU Make 附加功能的集合. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [GNU Global](https://www.gnu.org/software/global/) - 与 C 一起使用的源代码标记工具. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [gprof](http://www.gnu.org/software/binutils/)  - 性能分析工具.  GNU binutils 的一部分. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [Highlight](http://www.andre-simon.de/index.php) - 将源代码转换为带漂亮突出显示的格式化文本. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [include-what-you-use](https://github.com/include-what-you-use/include-what-you-use)  - 帮助找到不必要的夹杂物并提出修复它们的建议. 基于 LLVM/Clang（并且只适用于它）. [`NCSA`](https://directory.fsf.org/wiki/License:NCSA)
* [indent](https://www.gnu.org/software/indent/)  - 自动格式化 C 源代码以使其更易于阅读. 还可以从一种源样式转换为另一种样式. [`GNU GPLv3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [rr](https://rr-project.org/) - 记录非确定性执行以允许确定性调试的调试器. [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [tup](http://gittup.org/tup/index.html) - 非常快速、基于文件的跨平台构建系统. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [unifdef](http://dotat.at/prog/unifdef/) - Removes #ifdef 和 #if directives with their delimited text without touching any other part of the file. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause) 和 [`FreeBSD`](https://directory.fsf.org/wiki?title=License:FreeBSD)
* [Valgrind](http://www.valgrind.org/) - 一系列动态分析工具，包括泄漏检查器. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)

## Utilities ##

这是一个“包罗万象”的类别，适用于任何不适合其他地方的东西.

* [ApeTagLibs](https://github.com/jeremyevans/ape_tag_libs/tree/master/c) - 用于处理 APEv2 标签的 C 库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [bfd](http://sourceware.org/binutils/docs/bfd/)  - 用于操作二进制目标文件的库.  GNU binutils 的一部分. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [cf4ocl](https://fakenmc.github.io/cf4ocl/)  - OpenCL 的 C 框架； 用于开发和基准测试的跨平台面向对象框架  [OpenCL](https://www.khronos.或者g/opencl/) 项目. [`GNU LGPL3 (library)`](http://www.gnu.或者g/licenses/lgpl-3.0.html) 或者 [`GNU GPL3 (project code)`](http://www.gnu.或者g/licenses/gpl-3.0.html)
* [CommonMark](https://github.com/commonmark/commonmark-spec) - CommonMark 规范的 C 实现. [`Various Licenses`](https://github.com/commonmark/commonmark-spec/blob/master/LICENSE)
* [CException](https://github.com/ThrowTheSwitch/CException) - C 异常的实现. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [docopt.c](https://github.com/docopt/docopt.c) - 命令行选项解析器的 C 实现. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [dyncall](http://www.dyncall.org/) - 另一个外部函数接口库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [FANN](http://leenissen.dk/fann/wp/)  - 快速人工神经网络库； 神经网络的实现. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Firm](https://pp.ipd.kit.edu/firm/)  - C 库，提供适合在编译器中使用的基于图形的中间表示、优化和汇编代码生成. 在相同的许可证下附带一个示例 C 前端. [`GNU LGPLv2.1`](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
* [Genann](https://github.com/codeplea/genann) - C 中的简单神经网络库. [`Zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [gjrand](https://sourcef或者ge.net/projects/gjrand/) - 随机数生成程序库. [`GNU GPL2.1`](http://www.gnu.或者g/licenses/old-licenses/gpl-2.0.html) 或者 [`GNU GPLv3`](http://www.gnu.或者g/licenses/gpl-3.0.html)
* [GNU FreeIPMI](https://www.gnu.org/software/freeipmi/index.html) - 带内和带外 IPMI 实施. [`GNU GPL3`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GNU gperf](https://www.gnu.org/software/gperf/)  - 完美的哈希函数生成器，给定一个字符串列表. 输出 C 代码. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [GNU Libffcall](https://www.gnu.org/software/libffcall/) - 用于构建外部函数接口的库集合. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [gperftools](https://github.com/gperftools/gperftools) - 用于测量和改进性能的实用程序集合. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [huffandpuff](https://github.com/adamierymenko/huffandpuff) - 最小霍夫曼编码器和解码器. [`Public Domain`](https://creativecommons.org/share-your-work/public-domain/)
* [kdtree](https://github.com/jtsiomb/kdtree) - 用于处理 KD 树的简单库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [Kitsune](http://kitsune-dsu.com/) - 用于动态软件更新的高效通用框架. [`GNU LGPL3 or later`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [libavl](http://adtinfo.org/libavl.html/index.html) - 包含一系列自平衡二叉树的库. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [libbson](https://github.com/mongodb/libbson) - BSON 实用程序库. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [libCello](http://libcello.org/) - 将高级编程引入 C 的库. [`3-clause BSD`](https://directory.fsf.org/wiki/License:BSD-3-Clause)
* [libffi](https://github.com/libffi/libffi) - 便携式外部函数接口库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libgit2](https://libgit2.org/) - Git 的纯 C 实现. [`GNU GPL2 only, with a linking exception`](https://github.com/libgit2/libgit2/blob/master/COPYING)
* [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) - 与 iThings 通信的跨平台协议库. [`GNU LGPLv2.1 或者 later (library)`](http://www.gnu.或者g/licenses/old-licenses/lgpl-2.1.html) 或者 [`GNU GPL2.1 或者 later (tools)`](http://www.gnu.或者g/licenses/old-licenses/gpl-2.0.html)
* [libnfc](https://github.com/nfc-tools/libnfc) - 独立于平台的近场通信库. [`GNU LGPL3`](http://www.gnu.org/licenses/lgpl-3.0.html)
* [libPhenom](https://github.com/facebookarchive/libphenom)  - 已弃用，此处用于存档目的. 用于构建高可扩展性和高性能系统的事件框架. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [ncurses](https://www.gnu.org/software/ncurses/) - 彩色终端 UI 库. [`GNU GPL3 or later`](http://www.gnu.org/licenses/gpl-3.0.html)
* [nope.c](https://github.com/riolet/WAFer) - 基于 C 语言的超轻型软件平台，用于可扩展的服务器端和网络应用程序（想想 C 程序员的 node.js）. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [pbc](https://github.com/cloudwu/pbc) - 协议缓冲区库. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [rabbitmq-c](https://github.com/alanxz/rabbitmq-c) - 客户端库 [RabbitMQ](https://www.rabbitmq.com/). [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [Ragel](http://www.colm.net/open-source/ragel/) - 用于编译为 C 的状态机的 DSL. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [Tinyexpr](https://github.com/codeplea/tinyexpr) - 用于简单数学表达式的小型递归下降解析器、编译器和评估引擎. [`zlib`](https://directory.fsf.org/wiki/License:Zlib)
* [uthash](http://troydhanson.github.io/uthash/) - 哈希表实现，允许将现有结构轻松存储在哈希表中. [`1-clause BSD`](http://troydhanson.github.io/uthash/license.html)
* [cpu_features](https://github.com/google/cpu_features) - 一个跨平台的 C99 库，用于在运行时获取 cpu 功能. [`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [pblog](https://github.com/google/pblog) - 用于记录 formware 事件的小型、低开销、结构化的日志记录库.[`Apache 2.0`](https://directory.fsf.org/wiki/License:Apache-2.0)
* [libelf](https://github.com/WolfgangSt/libelf) - C 中的 ELF 目标文件访问库. [`GNU GPL2.1`](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
* [mcpp](http://mcpp.sourceforge.net/) - 便携式 C 预处理器. [`2-clause BSD`](https://opensource.org/licenses/BSD-2-Clause)
* [libusb](https://libusb.info/) - 通用访问 USB 设备. [`LGPL2.1`](https://github.com/libusb/libusb/blob/master/COPYING)
* [alsa-lib](https://www.alsa-project.org/main/index.php/Main_Page ) - 与 ALSA 交互的用户空间库. [`LGPL2.1`](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html)
* [Capstone](https://github.com/aquynh/capstone) - 反汇编/反汇编框架. [`BSD 3-clause`](https://github.com/aquynh/capstone/blob/master/LICENSE.TXT)

## XML ##

 &gt; “XML 是废话.真的.没有任何借口.XML 对人类来说很难解析，即使对计算机来说解析也是一场灾难.没有理由存在这种可怕的废话.”  - 莱纳斯·托沃兹

* [Expat](http://www.libexpat.org/) - 面向流的 XML 解析器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [libxml2](http://xmlsoft.org/) - 符合标准的可移植 XML 解析器. [`Expat`](https://directory.fsf.org/wiki/License:Expat)
* [mini-xml](https://github.com/michaelrsweet/mxml)  - 小型 XML 读写库. 除了 C 标准库之外，没有依赖项. [`Apache 2.0 with exceptions`](https://github.com/michaelrsweet/mxml/blob/master/LICENSE)
