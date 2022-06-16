<div class="github-widget" data-repo="Fr0sT-Brutal/awesome-pascal"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Pascal [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

很棒的 Delphi、FreePascal 和其他 *Pascal 框架、库、资源和闪亮的东西的精选列表. 灵感来自 awesome-xxx 的东西.

 **请注意，仅考虑开源项目. 死项目（3 年或更长时间未更新）必须非常棒或独特才能被包括在内.**
随意通过评论或拉取请求建议其他缺少的好项目.

这个很棒的收藏也可以在 [Delphi.ZEEF.com](https://delphi.zeef.com/anton.frost)

 :exclamation: **关于编译器兼容性的说明**. 根据项目的描述，所有项目都有编译器/语言方言兼容性徽章. 没有检查与未正式支持的编译器的真正兼容性. 通常，代码可以与不受支持的编译器/语言方言一起使用，只需稍作修改，但可能会有例外.


- [General Libraries](#general-libraries)
- [Multimedia](#multimedia)
	- [Audio](#audio)
	- [Video](#video)
	- [Graphic](#graphic)
- [Game dev](#game-dev)
- [Communications](#communications)
	- [Network](#network)
	- [Serial port](#serial-port)
- [GUI](#gui)
	- [Control packs](#control-packs)
	- [Single controls](#single-controls)
	- [Editors](#editors)
	- [Viewers](#viewers)
	- [Other GUI](#other-gui)
- [Database](#database)
- [Scripting](#scripting)
- [Machine Learning](#machine-learning)
- [Non-visual Classes/Utils](#non-visual-classesutils)
	- [Compression](#compression)
	- [Encryption](#encryption)
	- [XML/JSON/YAML/HTML](#xmljsonyamlhtml)
	- [Language](#language)
	- [Memory managers](#memory-managers)
	- [System](#system)
	- [Template](#template)
	- [Logging](#logging)
	- [Math](#math)
	- [Command-line](#command-line)
	- [Other non-visual](#other-non-visual)
- [OS](#os)
- [Report generating](#report-generating)
- [Unit Testing](#unit-testing)
- [Debugging / error handling](#debugging--error-handling)
- [Utilities](#utilities)
	- [RAD Studio IDE plugins/wizards](#rad-studio-ide-pluginswizards)
	- [Plugins for other IDE's](#plugins-for-other-ides)
	- [Documentation](#documentation)
	- [Code check/review, debug](#code-checkreview-debug)
	- [Setup](#setup)
	- [Other](#other)

---

## General Libraries ##

*大型通用库*

* [JCL](https://github.com/project-jedi/jcl) .  `[Delphi]` `[FPC]` 一组经过全面测试和完整记录的实用程序函数和非可视类，可以立即在您的 Delphi 和 C++ Builder 项目中重用. 该库分为几个类别，例如字符串、文件和 I/O、安全性、数学等等.

* [JVCL](https://github.com/project-jedi/jvcl) .  `[Delphi]` 由“Project JEDI”成员开发的 600 多个 Delphi 组件库.
// *GUI、算法、类、API 标头等*

* [Alcinoe](http://sourceforge.net/projects/alcinoe) ([mirror at GH](https://github.com/Zeus64/alcinoe) ）.  `[Delphi]` Delphi 的可视化和非可视化组件库.
 // *网络：FTP/Http/NNTP/POP3/SMTP、ISAPI、WinInet Http/FTP客户端； 数据库：火鸟/MySQL/SQLite3/Memcached/MongoDb/SphinxQL；  XML/JSON 解析器；  ZLIB； 密码学：AES、Blowfish、MD5、SHA、安全密钥 MD5/SHA；  opengl 视频播放器；  FireMonkey 控件； 其他：自平衡二叉树、表达式求值器*

* [Fundamentals Code Library](http://sourceforge.net/projects/fundementals) （被遗弃，最近的分叉是 [here](https://github.com/fundamentalslib/fundamentals4)  - 虽然它的单位设置略有不同，f.ex. 没有 XML. 最近的主要版本 5 [here](https://github.com/fundamentalslib/fundamentals5) ）.  `[Delphi]` `[FPC]` Delphi / FreePascal 代码单元的集合. 包括用于 Unicode、字符串、数据结构、套接字和数学的库.
 // *Utils: ZLIB 压缩；  JSON；  XML； 协议缓冲区；  Unicode 例程； 数据结构; 哈希：XOR、CRC、Adler、MD5、SHA、安全密钥MD5/SHA等； 网络：通过 SSL3/TLS1.0/TLS1.1/TLS1.2（完全原生）阻塞 TCP 客户端/服务器、HTTP(S)；  SQL解析器； 比特币 MtGox 客户端； 布莱斯脚本引擎； 密码：AES、DES、FUNE、RC2、RC4、RSA、Diffie-Hellman； 数学：矩阵、复数、统计、大数*

* [Spring4D](https://bitbucket.org/sglienke/spring4d) .  `[Delphi]` Embarcadero Delphi 2010 及更高版本的开源代码库. 它由许多不同的模块组成，这些模块包含一个基类库（通用类型、基于接口的集合类型、反射扩展）和一个依赖注入框架. 包括加密库.
 // *使用泛型和基于 IEnumerable 的集合和其他容器，可能比 RTL 类似物更准确和更有特色； 加密：CRC、DES、MD5、SHA； 文件工具等*

* [TheUnknownOnes](https://github.com/chaosben/theunknownones) .  `[Delphi]` 几乎所有用途的大量类、组件和实用程序. 几乎没有记录，但似乎不是最新的.

* [CNVCL](https://github.com/cnpack/cnvcl) .  `[Delphi]` CnPack 组件包. 大量可视化组件、类和实用程序.  // *很多有用的东西； 以中文为主的文档和评论*

* [mORMot](https://github.com/synopse/mORMot) .  `[Delphi]` `[FPC]` 适用于 Delphi 6 及更高版本或 FPC 2.7 的客户端-服务器 ORM/ODM SOA MVC 框架. 直接 SQL/NoSQL 数据库访问、对象上的 ORM/ODM、RESTful ORM 和 SOA 服务，通过高性能 HTTP 服务器上的接口、MVC/MVVM 网站、测试包括模拟和存根、日志记录、密码学、压缩、大量文档.

* [MARS - Curiosity](https://github.com/andrea-magni/MARS) .  `[Delphi]` Delphi REST 库. 纯 REST 方法，熟悉的 Delphi 风格的标准概念（包括基于组件的客户端库）. 已知兼容性：从 XE 到 10 Seattle 的 Delphi 版本. 某些功能需要 FireDAC.

* [ADAPT](https://github.com/LaKraven/ADAPT). `[Delphi]` Advanced Developer Async Programming Toolkit, foundation library intended to be used at the heart of your projects for the purpose of providing extremely powerful, multi-threaded (and thread-safe) capabilities. Event Engine - a very powerful system for producing Multi-Threaded, Asynchronous and Event-Driven programs. Generics Collections - highly efficient Collection Types (Lists, Trees, Maps etc.). Math Library - a library for Unit Conversion, special calculation and other useful mathematics routines. Package Engine - extension of the Streamables Engine supporting the packaging of files together (a VFS of sorts). Shared Streams Library - 100% Thread-Safe Stream Classes (Interfaced too) allowing read/write from multiple Threads. Stream Handling Library - makes working with Streams much easier! Handles Deleting, Inserting, Reading and Writing data.

* [Redux Delphi](https://github.com/pierrejean-coudert/ReduxDelphi) .  `[Delphi]` 使用单向数据流的 Delphi 应用程序的可预测状态容器. 受 ReduxJS 启发. 带有不可变的通用列表.

* [GrijjyFoundation](https://github.com/grijjy/GrijjyFoundation) .  `[Delphi]` 在其他 Grijjy 存储库中使用的基础类和实用程序.
// *BSON/JSON、IOCP/EPOLL 套接字、套接字池、HTTP、HTTP/2、OpenSSL、ProtocolBuffers.*

* [unRxLib](http://www.micrel.cz/RxLib/dfiles.htm) .  `[Delphi]` 努力保持 RxLibrary（60 多个组件的库）实际.

* [QuickLib](https://github.com/exilon/QuickLib) .  `[Delphi]` `[FPC]` 跨平台支持的快速开发库（AutoMapper、LinQ、IOC 依赖注入、MemoryCache、计划任务、配置、序列化程序、Json 序列化、计时码表、线程、列表、配置、控制台服务等） Delphi/Firemonkey (Windows,Linux,macOS/IOS/Android) 和 freepascal (Windows/Linux).

* [KOL](https://sourceforge.net/projects/kolmck) .  `[德尔福]` `[FPC]` ([KOL-CE](https://sourceforge.net/p/kol-ce) 端口到 FPC）Delphi（和 FPC）的 KEY OBJECTS LIBRARY - 使应用程序小而强大. 这个库是免费软件和开源的.  MCK 是一个镜像类套件，用于在 Delphi 环境中使用 KOL 库进行 VISUAL 项目开发.

* [cwRuntime](https://chapmanworld.com/cwRuntime/) .  `[Delphi]` `[FPC]` Delphi 和 FreePascal 实用程序库的编译器无关和跨平台集合. 它基于接口，提供基于 ARC 的内存管理功能和灵活的实现抽象，旨在为熟悉两种支持的编译器的开发人员形成源桥. 单元测试、集合/容器、用于加载动态库的多平台接口、Unicode 实用程序、用于处理流和缓冲区的接口、日志记录、线程、高精度计时器、套接字.

* [minilib](https://github.com/parmaja/minilib) .  `[Delphi]` `[FPC]` 跨平台库、Socket wrapper（包括 SSL 和 TLS）、数据库连接（SQLite、PostgeeSQL、FirebirdSQL、MariaDB）、XML 读写器、ComPort（COM1、COM2 等）.


## Multimedia ##


## Audio

* [Audio Tools Library](http://mac.sourceforge.net/atl) .  `[Delphi]` 用于处理多种音频格式的文件信息.
// *自 2005 年以来被遗弃.*

* [Delphi ASIO & VST Project](http://sourceforge.net/projects/delphiasiovst) .  `[Delphi]` 使用 ASIO 接口和 VST 插件编写应用程序的框架. 它带有无数的 DSP 算法，所有这些算法都在数十个示例中得到了展示.
// *最近不是很活跃，但是主干处于可用状态*

* [NewAC - New Audio Components](http://code.google.com/p/newac) （被遗弃，GH 上的分叉列表 [here](https://github.com/search?l=Pascal&o=desc&q=newac&s=updated&type=Repositories) ）.  `[Delphi]` 旨在帮助您的 Delphi 程序执行不同的声音处理任务. 使用 NewAC，您可以播放以多种格式存储的音频（wav、Ogg Vorbis、FLAC、Monkey Audio、WavPack、MP3、Windows WMA、DTS、AC-3（杜比环绕声）、VOB（DVD 文件））.
// *播放、录音、标签读/写、一些音频编辑任务和转换*

* [Audorra](https://sourceforge.net/projects/audorra) .  `[Delphi]` `[FPC]` Delphi 和 Freepascal 的数字音频库. 使用灵活的插件架构，它允许您交换音频后端（例如 WaveOut、OpenAL）、添加协议类（例如文件、http）和解码器.

* [Delphi-BASS](https://github.com/TDDung/Delphi-BASS) .  `[Delphi]` Delphi 的 FMX 和 VCL 标头/包装单元，用于 [BASS](https://www.un4seen.com) 音频库和附加组件.


## Video

* [DSPack](https://code.google.com/p/dspack) （被遗弃的，活跃的分叉是 [here](https://github.com/micha137/dspack-continued-mirror-for-delphinus) ）.  `[Delphi]` 使用 MS Direct Show 和 DirectX 技术编写多媒体应用程序的组件和类集.

* [Delphi-OpenCV](https://github.com/Laex/Delphi-OpenCV) .  `[Delphi]` Delphi中OpenCV库头文件的翻译
// *包括 FFMPEG 标头*

* [FFmpeg Delphi/Pascal Headers](http://www.delphiffmpeg.com/headers) .  `[Delphi]` `[FPC]` FFMPEG 标头的开源翻译.

* [PasLibVlc](http://prog.olsztyn.pl/paslibvlc). `[Delphi]` `[FPC]` Interface to VideoLAN libvlc.dll and VCL player component for Delphi / FreePascal based on VideoLAN

* [fevh264](https://github.com/dpethes/fevh264) .  `[FPC]` 基线 h.264 编码器. 支持 Windows 和 Linux


## Graphic

*图像文件，免费绘图，条形码等.还有一些绘图引擎在 [Game dev](#game-dev) 部分*

* [Graphics32](https://github.com/graphics32/graphics32) .  `[Delphi]` `[FPC]` 专为在 Delphi、Kylix 和 Lazarus 上进行快速 32 位图形处理而设计. 针对 32 位像素格式进行了优化，它提供了像素和图形基元的快速操作，并且在大多数情况下，Graphics32 优于标准 TCanvas 类. 它在每像素访问方面快了近 100 倍，在画线方面快了大约 2-5 倍.

* [GraphicEx](https://github.com/mike-lischke/GraphicEx) .  `[Delphi]` Delphi 的 Graphics.pas 附录，使您的应用程序能够加载许多常见的图像格式. 该库主要用于加载图像作为背景（按钮、表单、工具栏）和纹理（DirectX、OpenGL）或用于图像浏览和编辑目的，只要您不需要保存图像.

* [Vampyre Imaging Library](https://github.com/galfar/imaginglib) .  `[Delphi]` `[FPC]` 跨平台原生 Object Pascal（Delphi 和 Free Pascal）图像加载、保存和操作库.

* [CCR-EXIF](https://code.google.com/p/ccr-exif) （似乎被遗弃了，GH 上的分叉列表 [here](https://github.com/search?l=Pascal&o=desc&q=ccr-exif&s=updated&type=Repositories) ）.  `[Delphi]` 库，用于从 JPEG、TIFF 和 PSD 图像中读取和写入 Exif、IPTC 和 XMP 元数据.

* [KIcon](https://github.com/ThomasJaeger/KControls) .  `[Delphi]` `[FPC]` 如果需要对图标（或更好的图标文件 *.ico）进行更复杂的操作而不仅仅是查看，则此组件是有意义的. 完整的 PNG 图标图像支持，正确的渲染，带有 alpha 通道的图标.

* [Delphi Twain](http://www.kluug.net/delphitwain.php) .  `[Delphi]` `[FPC]` 该库允许您轻松访问 Delphi 和 Lazarus 的扫描功能.

* [Synopse PDF](https://github.com/synopse/SynPDF) .  `[Delphi]` `[FPC]` 用于 Delphi 的全功能开源 PDF 文档创建库，嵌入在一个单元中. 纯 Delphi 代码，Delphi 5 到 Delphi 10.3 Rio（和最新版本的 FPC），适用于 Win32 和 Win64 平台.

* [PowerPDF](https://github.com/TurboPack/PowerPDF) .  `[Delphi]` 可视化创建PDF文档的VCL组件. 与 Forms 一样，您可以在 Delphi 或 C++Builder IDE 上轻松设计 PDF 文档.

* [IGDI+](https://sourceforge.net/projects/igdiplus) .  `[Delphi]` 免费的开源库允许以自然的 Delphi 友好代码快速轻松地实现复杂的 GDI+ 应用程序.

* [GLScene](https://sourceforge.net/projects/glscene) .  `[Delphi]` `[FPC]` 用于 Delphi、C++Builder 和 Lazarus 的基于 OpenGL 的 3D 库. 它提供视觉组件和对象，允许以简单、轻松但功能强大的方式描述和渲染 3D 场景.  GLScene 不仅仅是一个 OpenGL 包装器或实用程序库，它已经发展成为一套通用 3D 引擎的基础类，并考虑到了快速应用程序开发.  GLScene 让您无需学习复杂的 OpenGL 即可快速设计和渲染 3D 场景，如果您知道如何设计 TForm，您将轻松掌握 GLScene 的基本操作. 该库带有大量演示集，展示了易用性，并展示了 RAD 并没有以牺牲 CPU/GPU 马力为代价.


* [Andorra 2D](http://sourceforge.net/projects/andorra) .  `[Delphi]` `[FPC]` 适用于 Delphi 和 Lazarus 的新一代 2D 引擎.  Andorra 2D 能够通过图形插件使用 DirectX 或 OpenGL.  Andorra 2D 以非常模块化的方式构建，并且易于使用.

* [Transparent-canvas](https://github.com/vintagedave/transparent-canvas) .  `[Delphi]` 用于绘制半透明字母混合图形的Delphi VCL/Windows 项目. 它提供了一个类似于 TCanvas 的类.

* [Fully-justified-text](https://github.com/vintagedave/fully-justified-text) .  `[Delphi]` 用于文本输出的 Delphi VCL / Windows 项目，允许使用多种选项打印完全对齐的文本.

* [AsciiImage](https://github.com/Memnarch/AsciiImage) .  `[Delphi]` AsciiImage-Delphi 的实现，Alexander Benikowski 基于 Charles Parnot 的 AsciiImage. 阅读更多 [his article](http://cocoamine.net/blog/2015/03/20/replacing-photoshop-with-nsstring).
// *从 ASCII 像素图创建可缩放的单色图像*

* [PngComponents](https://github.com/UweRaabe/PngComponents) .  `[Delphi]` PngComponents 是一组允许您在应用程序中包含真实 PNG 文件的组件.  PNG 文件本身并不会产生巨大的优势，但它们对 alpha 通道的支持确实具有相当大的魅力.

* [AggPasMod](https://github.com/CWBudde/AggPasMod) .  `[Delphi]` 现代化的 Pascal 反粒度几何. 该项目基于 AggPas，它本身基于 Anti-Grain Geometry，提供对最新 Delphi 版本（XE 及以上）的支持，并包含一些帮助类（VCL 组件和 FireMonkey 接口）. 二维矢量图形库. 基本上，您可以将 AggPas 视为一种渲染引擎，它从一些矢量数据在内存中生成像素图像. 但当然，AGG 可以做的远不止这些.
// *矢量图形库，渲染 SVG 等等*

* [delphi-shader](https://github.com/WouterVanNifterick/delphi-shader) .  `[Delphi]` 数以百计的图形效果，以及在纯 Delphi 代码中提供 GLSL 功能的库. 该项目生成一个可执行文件，具有一百多个实时图形效果. 所有这些都是 100% 的帕斯卡实现，无需使用外部库或硬件加速.

* [dglOpenGL](https://github.com/SaschaWillems/dglOpenGL) .  `[Delphi]` `[FPC]` Delphi / Pascal OpenGL 头文件翻译.

* [DelphiZXingQRCodeEx](https://github.com/MichaelDemidov/DelphiZXingQRCodeEx) .  `[Delphi]` `[FPC]` 来自 ZXing 的二维码生成功能的 Delphi/Lazarus 端口，ZXing 是一个开源条形码图像处理库.

* [ZXing.Delphi](https://github.com/Spelt/ZXing.Delphi) .  `[Delphi]` 用于 Delphi XE 到 10.2 Tokyo 的 Native Object Pascal 库，它基于众所周知的开源条码扫描库 ZXing（斑马线）. 它面向所有 FireMonkey 移动平台，从 v3.1 开始，它还完全支持 Windows VCL 应用程序（不依赖于 FMX.Graphics 单元）.

* [Zint-Barcode-Generator-for-Delphi](https://github.com/landrix/Zint-Barcode-Generator-for-Delphi) .  `[Delphi]` Zint-Barcode-Generator 的原生 Delphi 端口.

* [QuickImageFX](https://github.com/exilon/QuickImageFX) .  `[Delphi]` Delphi 库，用于简化图像加载/保存、转换和转换. 加载/保存 png、jpg、gif 和 bmp. 从不同的资源获取图像：文件、流、http、imagelist、关联的窗口图标、可执行文件图标等.旋转、翻转、灰度和许多其他转换.

* [NativeJpg](https://code.google.com/p/simdesign) .  `[Delphi]` 完全面向对象的 Pascal 实现，允许读写 Jpeg 文件. 您可以使用此软件从文件或流中读取和写入 Jpeg 图像. 它支持基线和渐进式 Jpeg，支持元数据，以及所有可以想象的无损操作.

* [OpenGL Pascal Toolkit](https://github.com/daar/GLPT) .  `[FPC]` 易于使用的本地 pascal 工具包，允许以独立于平台的方式创建和管理 OpenGL 上下文.

* [BGRAbitmap](https://github.com/edivando-fpc/BGRABitmap) .  `[Delphi]` `[FPC]` 使用 Lazarus 绘制具有透明度和抗锯齿的例程. 还提供各种变换. 这些例程允许以 BGRA 格式或 RGBA 格式（取决于平台）操作 32 位图像.

* [Clipper](http://angusj.com/delphi/clipper.php) .  `[Delphi]` 库执行线和多边形裁剪 - 交集、联合、差异和异或，以及线和多边形偏移

* [dexif](https://github.com/cutec-chris/dexif) .  `[Delphi]` `[FPC]` Delphi EXIF 库的 Lazarus 端口，用于从图像中提取 Exif 信息

* [FontIconEditor](https://github.com/lminuti/FontIconEditor) .  `[Delphi]` 简单的组件编辑器，允许您将图标从字体添加到 TImageList. 你可以使用任何你想要的字体.

* [IconFontsImageList](https://github.com/EtheaDev/IconFontsImageList) .  `[Delphi]` 扩展了 Delphi（VCL 和 FMX）的 ImageList 以简单使用和管理图标字体（支持 GDI+）

* [Mundus](https://github.com/Memnarch/Mundus) .  `[Delphi]` 用 Delphi 编写的软件渲染器. 当前仅支持 Win32，因为它使用了一些内联汇编程序.

* [Image32](https://sourceforge.net/projects/image32) .  `[德尔福]` `[FPC]` ([Website](http://www.angusj.com/delphi/image32/Docs/_Body.htm) ) 用 Delphi Pascal 编写的 2D 图形库. 它提供了广泛的图像处理功能，并包括支持各种画笔填充选项的线和多边形渲染器.

* [SVGIconImageList](https://github.com/EtheaDev/SVGIconImageList) .  `[Delphi]` 四个渲染 SVG 的引擎（Delphi TSVG、Delphi Image32、Direct2D 或 Cairo）和四个简化 SVG 图像使用的组件（调整大小、固定颜色、灰度等）.

* [Skia4Delphi](https://github.com/viniciusfbb/skia4delphi) .  `[Delphi]` 基于 Google 的 Skia 图形库的 Delphi 平台的跨平台 2D 图形 API. 它提供了一个全面的 2D API，可以跨移动、服务器和桌面模型使用来渲染图像.

* [PdfiumLib](https://github.com/ahausladen/PdfiumLib) .  `[Delphi]` 使用 PDFium 的 PDF VCL 控件示例

* [llPDFLib](https://github.com/SybrexSys/llPDFLib) .  `[Delphi]` Pure Object Pascal 库，用于创建 PDF 文档. 该库不使用任何 DLL 或外部第三方软件来生成 PDF 文件. 库包括具有属性和方法的 TPDFDocument 组件，如 Delphi 的 TPrinter，但旨在生成 PDF 文件.


## Game dev ##

*也有一些适合游戏开发的绘图引擎 [Graphic](#graphic) 部分*

* [RecastNavigation](https://github.com/Kromster80/RecastNavigationDelphi) .  `[Delphi]` 用于游戏的导航网格构建工具集.  Recast 附带 Detour、路径查找和空间推理工具包. 您可以将任何导航网格与 Detour 一起使用，但使用 Recast 生成的数据当然非常适合. 这是用 C++ 编写的原始 RecastNavigation 的一个端口.

* [Kraft Physics Engine](https://github.com/BeRo1985/kraft) .  `[Delphi]` `[FPC]` 可用于 3D 游戏的开源 Object Pascal 物理引擎库. 兼容：Delphi 7-XE7（但不支持 Android 和 iOS 目标），FreePascal &gt;= 2.6.2（支持几乎所有 FPC 支持的目标，包括 Android 和 iOS）

* [ZenGL](https://github.com/andru-kun/zengl) .  `[Delphi]` `[FPC]` OpenGL 用 Pascal 编写的跨平台游戏开发库，旨在为渲染 2D 图形、处理输入、声音输出等提供必要的功能.
// *最近没有更新，但工作正常*

* [Asphyre aka Platform eXtended Library (PXL)](https://sourceforge.net/projects/asphyre) .  `[Delphi]` `[FPC]` 用于开发 2D/3D 视频游戏、交互式和科学应用程序的跨平台框架. 它在数学、硬件控制、资源管理、显示实时图形和文本、处理用户输入和网络通信能力方面帮助开发人员.

* [CrystalPathFinding](https://github.com/d-mozulyov/CrystalPathFinding) .  `[Delphi]` `[FPC]` 简单而有效的开源库，旨在通过算法 A*/WA* 搜索基于 4（简单）、8（对角线/对角线）图块的地图的最短路径或 6 个（六边形）邻居.

* [Allegro-Pas](https://sourceforge.net/projects/allegro-pas) ([GitHub](https://github.com/niuniomartinez/allegro-pas) ）.  `[Delphi]` `[FPC]` Wrapper 使用 Pascal/Delphi 的 Allegro 游戏库.

* [Castle Game Engine](https://github.com/castle-engine/castle-engine) .  `[Delphi]` `[FPC]` 完整的 Pascal 游戏引擎. 跨平台的 3D 和 2D 游戏引擎，具有大量图形效果和基于 X3D 的场景图.

* [TileEngine](http://www.tilengine.org). ([GitHub](https://github.com/turric4n/PascalTileEngine)) `[Delphi]` `[FPC]` OOP Pascal Wrapper and bindings for Tilengine 2D retro graphics engine. Tilengine is a cross-platform 2D graphics engine for creating classic/retro games with tilemaps, sprites and palettes. Its scanline-based rendering algorithm makes raster effects a core feature, a technique used by many games running on real 2D graphics chips.

* [SDL2](http://www.freepascal-meets-sdl.net/) ([GitHub](https://github.com/ev1313/Pascal-SDL-2-Headers) ）.  `[Delphi]` `[FPC]` Pascal SDL 2 标头.  Simple DirectMedia Layer 是一个跨平台开发库，旨在通过 OpenGL 和 Direct3D 提供对音频、键盘、鼠标、游戏杆和图形硬件的低级访问.

* [SFML](https://github.com/CWBudde/PasSFML) .  `[Delphi]` `[FPC]` Pascal SFML 标头.  SFML 为您的 PC 的各种组件提供了一个简单的界面，以简化游戏和多媒体应用程序的开发. 它由五个模块组成：系统、窗口、图形、音频和网络. 目前支持 Delphi 和 FPC/Lazarus. 但是，由于编译器与 Delphi 编译器不兼容（通过变通方法解决），目前建议使用 FPC.

* [pasvulkan](https://github.com/BeRo1985/pasvulkan) .  `[Delphi]` `[FPC]` Vulkan 标头生成器、OOP 风格的 API 包装器、框架和未来的基于 Vulkan 的 Object Pascal 游戏引擎.

* [DarkGlass](https://github.com/kenjones007/DarkGlass) .  `[Delphi]` DarkGlass 是使用 Delphi 编写的通用游戏引擎.

* [JEDI-SDL](https://sourceforge.net/projects/jedi-sdl) .  `[Delphi]` `[FPC]` 来自 JEDI 的 SDL 的 Pascal 标头. 适用于 Delphi、Kylix、Free Pascal、Gnu Pascal 和 TMT Pascal.

* [Apus Game Engine](https://github.com/Cooler2/ApusGameEngine) .  `[Delphi]` `[FPC]` 用于制作大多数 2D 游戏、GUI 应用程序和 Web 服务的跨平台库. 支持 UI、文本渲染、即时定位、粒子、基本脚本和许多较低级别的子系统. 使用 OpenGL/GLES 和 DirectX.

* [Delphi3D Engine](https://github.com/BrokenGamesUG/delphi3d-engine) .  `[Delphi]` 用于 Delphi 和 Windows 的 3D 图形和游戏引擎

* [Ray4Laz](https://github.com/GuvaCode/Ray4Laz) .  `[FPC]` 一个完整的头文件翻译（绑定） [raylib 4.0](https://www.raylib.com/) 给帕斯卡.


## Communications ##


## Network

*套接字通信、网络协议、编码等*

* [Internet Component Suite](http://www.overbyte.be/frame_index.html) .  `[Delphi]` 由各种互联网组件和应用程序组成的基于异步的库. 用于 TCP、UDP、原始套接字、FTP、SMTP、POP3、NNTP、HTTP、Telnet 等的客户端/服务器. 在 OpenSSL 的帮助下支持 SSL 和 TLS. 还包括 Mime 解码器、SHA1/MD4/MD5 哈希、DES 加密.

* [Indy](https://github.com/IndySockets/Indy) .  `[Delphi]` `[FPC]` 用于 Delphi、C++Builder、Delphi.NET 和 FreePascal 的网络组件
 // *基于阻塞套接字和线程的多合一网络库. 自 2006 年起包含在默认 RAD 工作室安装中.*

* [Ararat Synapse](https://sourceforge.net/p/synalist) .  `[Delphi]` `[FPC]` 适用于 Delphi、C++Builder、Kylix 和 FreePascal 的 Pascal TCP/IP 库. 通过阻塞（同步）套接字或有限的非阻塞模式处理网络通信. 这个项目不使用异步套接字！ 该项目包含简单的低级非可视对象，用于最简单的编程而没有问题（不需要多线程同步，不需要 Windows 消息处理等）非常适合命令行实用程序、可视项目、NT 服务等
 // *TCP、UDP、ICMP、RAW；  ICMP、DNS、SMTP、HTTP、SNMP、NTP、FTP、LDAP、NNTP、Telnet；  IPv6； 袜子代理；  SSL/TLS（通过 OpenSSL 或 Windows CryptoApi）； 平； 字符代码转码；  MIME编解码；  CRC16、CRC32、MD5 和 HMAC-MD5.*

* [Internet Professional](http://sourceforge.net/projects/tpipro2010) .  `[Delphi]` 为 Borland Delphi 和 C++Builder 提供 Internet 连接的 VCL 组件集.  iPRO 包括 POP3、SMTP、NNTP、FTP、HTTP、即时消息和 HTML 查看器组件，以及用于低级套接字访问的组件.
 // *似乎已被放弃，但包含大量功能，包括 ICMP、POP、SMTP、HTTP、NNTP、NTP、FTP、SMTP；  HTML解析器和查看器；  MIME 工具；  cookie、证书、缓存、加密等*

* [SynCrtSock](https://github.com/synopse/mORMot/blob/master/SynCrtSock.pas) .  `[Delphi]` `[FPC]` 具有多个套接字和 HTTP 客户端-服务器类，包括 Windows 下基于 http.sys 的高性能服务器，以及新的线程池驱动的套接字服务器.
// *还实现了Windows下的http.sys绑定和nix下的cURL绑定*

* [TML Messaging Suite](http://www.libtml.org/docs/libtml-pascal) .  `[Delphi]` `[FPC]` 用于快速开发可扩展和可扩展接口的网络消息传递库. 基于点对点标准协议 [BEEP (Blocks Extensible Exchange Protocol)](http://www.beepcore.org), 定义在 [RFC3080](https://tools.ietf.org/html/rfc3080) 和 [RFC3081](https://tools.ietf.org/html/rfc3081). libTML is suitable for many use cases 和 communication patterns. Equipped with a type safe data API, TML can transport hierarchical data structures fast 和 reliable.
// *libTML Object Pascal 组件不仅是与核心库的语言绑定，而且是一套完整的非可视化组件，用于简化 libTML 与 Embarcadero RAD Studio 和 Lazarus 的使用.*

* [DMVCFramework](https://github.com/danieleteti/delphimvcframework) .  `[Delphi]` Delphi中流行且强大的Web解决方案框架.

* [Delphi IOCP](https://github.com/ymofen/diocp-v5) .  `[Delphi]` 实现了几个基于Windows IOCP 技术的网络类. 套接字、HTTP、Ntrip 服务器和客户端.
// *有很好的文档和样式的代码，但只有中文.*

* [delphi-aws-ses](https://github.com/monde-sistemas/delphi-aws-ses) .  `[Delphi]` 适用于 Delphi 应用程序的 Amazon Simple Email Service (AWS SES) 库.

* [delphi-slackbot](https://github.com/monde-sistemas/delphi-slackbot) .  `[Delphi]` 发送消息的 Delphi 库 [Slack](https://slack.com) 使用 slackbot.

* [Kitto](https://github.com/EtheaDev/kitto). `[Delphi]` Allows to create Rich Internet Applications based on a data model that can be mapped onto any database. The client-side part uses ExtJS (through the ExtPascal library) to create a fully AJAX application, allowing you to build standard and advanced data-manipulating forms in a fraction of the time. Kitto is aimed at Delphi developers that need to create web application without delving into the intricacies of HTML, CSS, JavaScript or learning to use a particular library such as ExtJS, yet it allows access to the bare metal if required.

* [Daraja Framework](https://github.com/michaelJustin/daraja-framework) .  `[Delphi]` `[FPC]` Object Pascal 的轻量级 HTTP 服务器框架（Delphi 2009+ / Free Pascal 3.0）. 通过以下方式支持实现 RESTful 服务 [daraja-restful](https://github.com/michaelJustin/daraja-restful) 扩大.

* [Alcinoe](#general-libraries) .  FTP/Http/NNTP/POP3/SMTP、ISAPI、WinInet Http/FTP 客户端.

* [Fundamentals Code Library](#general-libraries) . 通过 SSL3/TLS1.0/TLS1.1/TLS1.2（完全原生）阻止 TCP 客户端/服务器、HTTP(S).

* [mORMot](#general-libraries) . 通过高性能 HTTP 服务器、MVC/MVVM 网站上的接口提供 RESTful ORM 和 SOA 服务

* [SDriver](https://github.com/andrea-magni/SDriver) .  `[Delphi]` Delphi 包装器 [Slack](https://slack.com) API.

* [Hprose for Delphi/Lazarus](https://github.com/hprose/hprose-delphi) .  `[Delphi]` `[FPC]` 高性能远程对象服务引擎. 它是一个现代的、轻量级的、跨语言的、跨平台的、面向对象的、高性能的、远程动态通信中间件. 它不仅易于使用，而且功能强大. 该项目是 Hprose for Delphi/Lazarus 的实现.

* [TelegAPI](https://github.com/ms301/TelegAPI) .  `[Delphi]` 在 Delphi 中使用 Telegram messenger Bot API 的库.

* [fp-telegram](https://github.com/Al-Muhandis/fp-telegram) .  `[FPC]` 库，用于在 FreePascal/Lazarus 中使用 Telegram 机器人 API.

* [DelphiZeroMQ](https://github.com/grijjy/DelphiZeroMQ) .  `[Delphi]` ZeroMQ Majordomo 协议和 CZMQ 高级绑定的 Delphi 实现.

* [GrijjyFoundation](#general-libraries) .  IOCP/EPOLL 套接字、套接字池、HTTP、HTTP/2、OpenSSL、ProtocolBuffers.

* [STOMP Client](https://github.com/danieleteti/delphistompclient) .  `[Delphi]` `[FPC]` Embarcadero Delphi 和 FreePascal 的 STOMP 客户端. 该项目可以使用 INDY (Delphi) 或 Synapse (Delphi 或 FreePascal).

* [delphiXero](https://github.com/littleearth/delphiXERO) .  `[Delphi]` Delphi 的 XERO 云会计 API.

* [BesaSoap](https://github.com/besasoftware/besasoap). `[Delphi]` The BesaSoap library is designed to help programmers develop faster and more native web service client applications. Represents C# or Java like native class support, nullable data types and custom attributes.

* [IndySoap](https://sourceforge.net/projects/indysoap) .  `[Delphi]` 使用 Delphi/CBuilder 编译器实现 Web 服务的开源库.  IndySoap 与 Indy 的运输服务无关，但包括基于 Indy 的运输服务.

* [Fano Framework](https://fanoframework.github.io) .  `[FPC]` 现代 Pascal 编程语言的 Web 应用程序框架. 它是用 Free Pascal 编写的.

* [Internet Tools](#xmljsonyaml) .  XPath/XQuery/JSONiq/CSS/HTML； 在 Windows/Linux/macOS/Android 上执行 HTTP/S 请求的函数，一种受 XSLT 启发的网络抓取语言和一个自动更新类.

* [Delphi Cross Socket](https://github.com/winddriver/Delphi-Cross-Socket/) .  `[Delphi]` Delphi 跨平台套接字库（中文）. 针对不同的平台使用不同的 IO 模型：IOCP (Windows)、KQUEUE (FreeBSD(macOS, iOS, etc))、EPOLL (Linux(Linux, Android)).

* [ToroKernel](https://github.com/torokernel/torokernel) .  `[FPC]` 这是一个库内核，允许专门移植的 freepascal 应用程序在系统中单独运行.  Toro 在用户的应用程序中编译，从而生成一个可以在裸机上启动或作为现代虚拟机管理程序（例如 hyperv、kvm、qemu、firecraker）中的来宾的二进制文件.  ToroKernel 通过提供专用 API 来解决微服务的开发问题.

* [Horse](https://github.com/HashLoad/horse) .  `[Delphi]` `[FPC]` 快速且极简的网络框架.  Horse 允许毫不费力地创建强大的 RESTful 服务器. 专注于微服务.

* [Bauglir WebSocket](https://github.com/MFernstrom/Bauglir-WebSocket-2) .  `[Delphi]` `[FPC]` 基于 Ararat Synapse 的 WebSocket 服务器/客户端实现.

* [Delphi-RabbitMQ](https://github.com/HeZiHang/Delphi-RabbitMQ) .  `[Delphi]` 用于 Delphi 的 RabbitMQ 驱动程序

* [DelphiGrpc](https://github.com/ultraware/DelphiGrpc) .  `[Delphi]` 实时流式gRPC协议的实现

* [Google API for Delphi](https://github.com/googleapi/googleapi) .  `[Delphi]` Google API for Delphi

* [Delphi JOSE and JWT Library](https://github.com/paolo-rossi/delphi-jose-jwt) .  `[Delphi]` JOSE（JSON Object Signing and Encryption）和JWT（JSON Web Token）的Delphi实现

* [WiRL](https://github.com/delphi-blocks/WiRL) .  `[Delphi]` 项目的创建是为了简化在 Delphi 中的 RESTful 服务实现，但更重要的是，为了实现与用其他语言和工具编写的 REST 客户端的最大互操作性

* [OpenSSL](https://github.com/lminuti/Delphi-OpenSSL) .  `[Delphi]` OpenSSL 的 Delphi 包装器

* [Thrift Delphi Software Library](https://github.com/apache/thrift/tree/master/lib/delphi) .  `[Delphi]` 用于点对点 RPC 实现的轻量级、独立于语言的软件堆栈.  Thrift 为数据传输、数据序列化和应用程序级处理提供了清晰的抽象和实现. 代码生成系统将简单的定义语言作为输入，并生成跨编程语言的代码，这些编程语言使用抽象堆栈来构建可互操作的 RPC 客户端和服务器.  Thrift 使以不同编程语言编写的程序可以轻松共享数据和调用远程过程.  Thrift 支持 28 种编程语言，很有可能支持您当前使用的语言.

* [Delphi Modbus](https://github.com/coassoftwaresystems/delphi-modbus). `[Delphi]` `[FPC]` Implementation of a ModbusTCP protocol master and slave over TCP/IP.

* [RESTRequest4Delphi](https://github.com/viniciussanchez/RESTRequest4Delphi) .  `[Delphi]` RESTRequest4Delphi 是一个使用任何编程语言编写的 REST 服务的 API. 旨在以简单和极简的方式促进开发.

* [LazWebsockets](https://github.com/Warfley/LazWebsockets) .  `[FPC]` 这提供了一个为 FPC 和 Lazarus 编写的小型 Websocket 服务器和客户端实现. 它完全基于 fcl 套接字单元，因此独立于除 FCL 之外的任何其他依赖项.

* [NetCom7](https://github.com/DelphiBuilder/NetCom7) .  `[Delphi]` 这组组件是任何语言中最快的套接字通信实现； 这是一个在 TCP/IP 套接字上极其优化的代码.

* [VK API](https://github.com/HemulGM/VK_API) .  `[Delphi]` 在 Delphi 中使用 Vkontakte（俄罗斯社交网络）API 的库. 完整的 API（带有 Bot 示例）.

* [AWS SDK for Dephi](https://github.com/landgraf-dev/aws-sdk-delphi) .  `[Delphi]` 用于 Delphi 的非官方 AWS（亚马逊网络服务）开发工具包.
 **警告！ 需要来自 TMS 的付费库**

* [Voice Communication](https://github.com/terrylao/voice_communication) .  `[Delphi]` 语音通讯器组件.
// *实现RTP、RTSP、SHOUT、SNTP、STUN协议和多种音频格式编码/解码*

* [libPasCURL](https://github.com/isemenkov/libpascurl) .  `[Delphi]` `[FPC]` cURL 库的绑定和包装.  libcurl 是用于传输指定 URL 语法的数据的库，支持 HTTP、HTTPS、FTP、FTPS、GOPHER、TFTP、SCP、SFTP、SMB、TELNET、DICT、LDAP、LDAPS、FILE、IMAP、SMTP、POP3、RTSP和RTMP.

* [Delphi_SChannelTLS](https://github.com/Fr0sT-Brutal/Delphi_SChannelTLS) .  `[Delphi]` 辅助函数和套接字类通过 WinAPI (SChannel) 执行 TLS 通信. 包括 Overbyte ICS TWSocket 后代类.

* [Delphi-Kafka](https://github.com/HeZiHang/Delphi-Kafka) .  `[Delphi]` 基于 Librdkafka 的高性能 Delphi 客户端，具有完整的协议支持.

* [DelphiKafkaClient](https://github.com/norgepaul/DelphiKafkaClient) .  `[Delphi]` Apache Kafka 的跨平台 Delphi 客户端/包装器. 支持 Windows (i386/x64) 和 Linux (x64). 在 Delphi 10.4 上测试，但应该适用于所有现代 Delphi 版本. 虽然它似乎按预期工作，但该项目是一个概念证明，从未在生产中进行过测试.

* [KafkaGate](https://github.com/dinmil/KafkaGate) .  `[FPC]` 使用 librdkafka 和 ZeroMQ 的 Apache Kafka Free Pascal 绑定.

* [delphi-mqtt](https://github.com/pjde/delphi-mqtt) .  `[Delphi]` 基于 ICS 网络组件的 Delphi MQTT 服务器和客户端组件.

* [mqtt](https://github.com/bkeevil/mqtt) .  `[FPC]` 带有演示应用程序的 Lazarus/FPC 的消息队列遥测传输 (MQTT) 客户端和服务器组件包. 对于客户端和服务器演示应用程序，使用 LNet 组件.

* [LNet](https://github.com/almindor/lnet) .  `[FPC]` 用 Free Pascal 编写的轻量级网络库. 异步、TCP/UDP 通信类.  LTCP、LUDP、LTELNET、LFTP 和 LSMTP 是示例程序.

* [NamedPipeExchange](https://github.com/kami-soft/NamedPipeExchange) .  `[Delphi]` 服务器和客户端类通过命名管道进行通信. 基于
[FWIOCompletionPipes](http://rouse.drkb.ru/network.php#fwiocompletionpipe) 单元.

* [delphizmq](https://github.com/bvarga/delphizmq) .  `[Delphi]` `[FPC]` 这是 ZeroMQ 的绑定. 应该适用于 Delphi7+ 版本和 FPC 2.6.0. 该包包含一个包装器 (zmq.pas) 和一个更高级别的 api (zmqapi.pas). 它应该适用于 ZMQ 2.2.x 和 3.2.x. 对于 2.2.x 版本，在 zmq.inc 中取消定义 zmq3. 该 dll 不属于此 repo，您​​可以从官方发行版下载相应的，并将其重命名为 libzmq.dll.


## Serial port

* [Synaser](http://sourceforge.net/p/synalist/code/HEAD/tree/trunk/synaser.pas) .  `[Delphi]` `[FPC]` 用于阻止串行端口通信的库. 它是 Synapse 中的非可视类，程序员界面与 Synapse 非常相似.

* [Async Professional](http://sourceforge.net/projects/tpapro) ([Newest](https://github.com/TurboPack/AsyncPro) 和维护版本仅适用于最近的编译器版本）.  `[Delphi]` 用于 Embarcadero Delphi、C++Builder 和 ActiveX 环境的综合通信工具包. 它提供对串行端口、TAPI 和 Microsoft Speech API（TTS/语音识别）的直接访问. 它支持传真、终端仿真、VOIP、RAS 拨号等.
 // *似乎已过时（2011 年最后一次更新），但已适应 XE，并且应该易于在较新版本中使用. 该项目的文档也非常详尽. 第二个链接指向最新编译器版本的改编版本.*

* [TComPort](https://sourceforge.net/projects/comport) .  `[Delphi]` Delphi/C++ Builder 串行通讯组件. 它通常很容易用于基本的串行通信目的.
// *Seems abandoned since 2011*


## GUI ##

*视觉组件*


## Control packs

*大量的 GUI 控件*

* [Cindy components](http://sourceforge.net/projects/tcycomponents) .  `[Delphi]` 包含 71 个组件的包：VCL 控件（标签、按钮、面板、Edits、TabControls、StaticText），具有背景渐变、彩色斜面、墙纸、shadowText、标题方向等功能.

* [Orpheus](http://sourceforge.net/projects/tporpheus) ([Newest](https://github.com/TurboPack/Orpheus) 和维护版本仅适用于最近的编译器版本）.  `[Delphi]` 屡获殊荣的用于 Borland Delphi 和 C++Builder 的 UI 工具包. 它包含 120 多个组件，涵盖从数据输入到日历和时钟的所有内容. 其他值得注意的组件包括对象检查器、LookOut 栏和报告视图.
 // *高级编辑、组合框、网格 + 组件（反）序列化器.  GUI 组件看起来相当老式，主题支持可能会受到限制. 包包含许多演示，但似乎没有可用的文档. 第二个链接指向最新编译器版本的改编版本.*

* [KControls](https://github.com/ThomasJaeger/KControls) .  `[Delphi]` `[FPC]` 控制组件. 所有控件的编写都是为了在 Lazarus 中实现跨 IDE 兼容（Delphi/C++Builder VCL 和 Lazarus LCL）和跨平台兼容.
 // *最有用的是 TKGrid，它具有 DB 感知的传统 TKDBGrid — 一个功能非常齐全的网格实现，包括. 就地编辑. 还有十六进制编辑器、打印预览、编辑器、标签、按钮等*

* [D.P.F Delphi Android](http://sourceforge.net/projects/dpfdelphiandroid) / [D.P.F Delphi iOS](http://sourceforge.net/projects/dpfdelphiios) 原生组件.  `[Delphi]` DPF Delphi 原生组件，100% iOS 性能和样式. 开发具有快速原生性能和原生风格的 iPhone、iPad 和 iPod Touch 应用程序. 使用原生 Android 控件和服务. 快速的本机性能. 与 FM VCL 控件混合. 可以使用最新的 Android 控件和功能快速更新.

* [Essentials](https://github.com/TurboPack/Essentials) .  `[Delphi]` 包含 13 个用于 Embarcadero Delphi 和 C++Builder 的原生 VCL 控件. 这些控件包括下拉日历和计算器、滚动对话框、3-D 标签、平铺背景、滚动消息、菜单按钮等.

* [FreeEsVCLComponents](https://github.com/errorcalc/FreeEsVCLComponents) .  `[Delphi]` 用于 Delphi 和 C++Builder 的免费 VCL 组件库. 这种新的控件和组件改善了应用程序的外观并提供了更好的用户体验. 组件支持视觉样式并具有现代风格. 所有组件都具有最佳支持透明度，而不是闪烁，并且具有支持 TGraphicControl 继承者双缓冲的有趣可能性.

* [SpTBXLib](https://github.com/SilverpointDev/sptbxlib) .  `[Delphi]` 为 Toolbar2000 组件添加了包，它增加了以下功能：皮肤、Unicode 支持、自定义绘画事件等等.

* [Kastri](https://github.com/DelphiWorlds/Kastri) .  `[Delphi]` 基于 Delphi 中现有 RTL 和 FMX 库的跨平台库. 支持在 FMX/RTL 中找不到的许多较新的 API，以及缺失 API 的“回填”

* [DelphiUCL](https://github.com/VuioVuio/DelphiUCL) .  `[Delphi]` 用于 Delphi VCL 的 UWP 控件.

* [JPPack](https://github.com/jackdp/JPPack) .  `[Delphi]` `[FPC]` Delphi 的 VCL 组件和 Lazarus 和 CodeTyphon 的 LCL 组件的集合 - 按钮、面板、LinkLabel、ProgressBar、ColorComboBox、ColorListBox、Timer 等

* [DDuce](https://github.com/beNative/dduce) .  `[Delphi]` 组件、模块、扩展和原语使用 Delphi 新的语言特性，如运算符重载、属性、泛型、匿名方法和扩展 RTTI，提供了一些新的强大工具来扩展开发人员的创造力.
// *属性编辑器、网格、XML 树等*


## Single controls

* [EasyListView](http://code.google.com/p/mustangpeakeasylistview) （似乎被遗弃了，GH 上的活跃分叉 [here](https://github.com/TurboPack/MustangpeakEasyListview) ）.  `[Delphi]` 是 Listview 的 VirtualShellTools 的一部分，但可用于更快且更可定制的 TListview 替换.
// *功能丰富的 Listview 实现虚拟（基于回调）MVC 范例.*

* [VirtualTreeView](https://github.com/Virtual-TreeView/Virtual-TreeView). `[Delphi]` ([VirtualTreeView-Lazarus](https://github.com/blikblum/VirtualTreeView-Lazarus) 端口到 FPC `[FPC]`）. 从头开始构建的 Treeview 控件. 多年的发展使其成为当今可用的最灵活和最先进的树控件之一.
 // *非常灵活的可视化组件实现虚拟（基于回调）MVC范例. 也可以用作列表视图或网格. 在 RAD Studio GUI 中使用.*

* [Delphi Chromium Embedded](https://github.com/hgourvest/dcef3) .  `[Delphi]` 在 Delphi 中嵌入 Chromium，在 Delphi 2010、XE、XE2、Delphi 7 上测试.
// *需要几个 Chromium DLL*

* [TChromeTabs](https://github.com/norgepaul/tchrometabs) .  `[Delphi]` Delphi 6 全面实现谷歌浏览器的标签页 - Delphi 10.1 Berlin

* [TFrameStand](https://github.com/andrea-magni/TFrameStand) .  `[Delphi]` 在您的 FireMonkey (FMX) 应用程序中轻松使用 TFrame，以获得整个用户体验的视觉一致性，并轻松添加现代外观元素，如效果和过渡.

* [TPrintPreview](https://github.com/landrix/TPrintPreview-for-Delphi) .  `[Delphi]` Delphi Vcl Win32/Win64 打印预览组件

* [VolgaDB](https://sourceforge.net/projects/volgadb) .  `[Delphi]` 非常适合 Delphi 的可定制 DBgrid.  TCustomGrid 后代.  CheckBox、ComboBox 列样式. 还包括 TVolgaDBEdit，它在一个组件中替换了 TDBEdit、TDBComboBox、TDBLookupCombo、TDBLookupTree 和 TDBDatePicker.  TVolgaDBEdit 可能是 DB-aware 和非 DB-aware.
// *似乎自 2013 年以来就被放弃了*

* [TTreeListView](http://github.com/benibela/treelistview) .  `[Delphi]` `[FPC]` 这个组件是 TTreeView 和 TListView 的混合体，可以绘制一棵树，其节点具有按列排序的附加信息.

* [neTabControl](https://github.com/jkour/neTabControl) .  `[Delphi]` Delphi 的 FireMonkey 控件. 它建立在本机 TabControl 之上并添加了许多功能.

* [ATTabs](https://github.com/Alexey-T/ATFlatControls) .  `[Delphi]` `[FPC]` 用于 lite 选项卡的 Delphi/Lazarus 组件. 独立于操作系统，完全自定义绘制.

* [zControls](https://github.com/MahdiSafsafi/zcontrols) .  `[Delphi]` 包含 TzObjectInspector - 具有许多功能的强大对象检查器.

* [RiverSoftAVG Charting Component Suite](http://www.riversoftavg.com/charting.htm) .  `[Delphi]` 免费（用于非商业用途），带有源图表套件，用于将图表和图形添加到您的程序中. 对于 Delphi 2010-Tokyo (Win32/Win64/macOS/iOS/Android) 和 Appmethod (Object Pascal).

* [DzHTMLText](https://github.com/digao-dalpiaz/DzHTMLText) .  `[Delphi]` `[FPC]` 允许您在标签中指定格式化文本的可视组件，使用几乎与 HTML 代码中使用的语法相同.

* [SMDBGrid component](http://www.scalabium.com/smdbgrid.htm) .  `[Delphi]` 具有扩展功能的 TDBGrid 的继承者. 能够显示多行自动换行列标题、布尔字段复选框、通过复选框从键盘和鼠标方便地选择记录、扩展指示器列、列固定、排除在 DBGrid 中插入和删除记录的机会、自己的标准PopupMenu、列状态的保存/恢复、附加事件的处理等.多语言资源.

* [decTreeView](https://github.com/DenisAnisimov/decTreeView) .  `[Delphi]` decTreeView 库是 TreeView (SysTreeView32) 控件的替代实现

* [TeeGrid](https://github.com/Steema/TeeGrid). `[Delphi]` `[FPC]` Lightweight full-featured Grid / Tabular control. For Embarcadero RAD Studio 2009 and up to Sydney 10.4, Delphi and C++, VCL and Firemonkey frameworks (all platforms: Windows 32 and 64 bit, Mac OSX, Android and iOS), and Lazarus FreePascal (Windows, Linux, etc)

* [AXW Ribbon](https://www.axolot.com/axwribbon.htm) .  `[Delphi]` Office 2016 风格的功能区组件. 适用于 Delphi 7 及当前的 Delphi 版本. 可能会与 Delphi 6 和可能的 Delphi 5 一起编译.


## Editors

* [SynEdit](https://sourceforge.net/projects/synedit) ([mirror at GitHub](https://github.com/TurboPack/SynEdit) ）.  `[Delphi]`语法高亮编辑控件，不基于Windows常用控件.  SynEdit 与 Delphi 和 Kylix 兼容

* [LazEdit](https://svn.code.sf.net/p/lazarus-ccr/svn/applications/lazedit) .  `[FPC]` 具有语法高亮显示和帮助编辑 HTML 的工具的通用文本编辑器.

* [ATSynEdit](https://github.com/Alexey-T/ATSynEdit) .  `[FPC]` 用于 Lazarus 的多行编辑器控件，包括语法高亮.

* [QDSEquations](https://github.com/karser/QDSEquations) .  `[Delphi]` Delphi 和 Lazarus 的方程编辑器，允许您输入和显示任何复杂的数学公式，从简单的希腊符号到矩阵和复杂的积分表达式.

* [TBCEditor](https://github.com/LaKraven/TBCEditor) .  `[Delphi]` 用于 RAD Studio (Delphi/C++ Builder) 的语法高亮编辑控件，具有代码折叠、完成建议、匹配对、小地图、同步编辑、自动换行等功能.外部荧光笔和配色方案文件采用 JSON 格式也可以从流中加载.


## Viewers

* [ATViewer](https://sourceforge.net/projects/atviewer) ([mirror at GitHub](https://github.com/Alexey-T/ATViewer) ）.  `[Delphi]` Delphi 组件查看各种文件类型：文本、二进制、图像、多媒体、网页等.
 // *用于 Universal Viewer 软件. 可用于显示十六进制转储，具有无限大小文件/流的快速显示. 支持 Total Commander Lister 插件.*

* [ATImageMap](https://sourceforge.net/projects/atviewer/files/ATImageMap) ([mirror at GitHub](https://github.com/Alexey-T/ATViewer) ）.  `[Delphi]` 组件旨在将许多图像（整个图像的一部分）显示为单个地图. 例如，您可能有一组图像，X 为 200，Y 为 100，控件会将它们显示为单个地图. 组件还允许绘制路径：每条路径由许多线、点和图标组成.

* [HtmlViewer](https://github.com/BerndGabriel/HtmlViewer) .  `[Delphi]` `[FPC]` Delphi/Lazarus HtmlViewer/FrameViewer.
// *支持大多数标签、内联样式和 CSS 的 Html 可视化工具.*

* [SciDe](https://github.com/da-baranov/SciDe) .  `[德尔福]` `[FPC]` [Sciter](https://sciter.com) （可嵌入的 HTML/CSS/脚本引擎）Delphi 的包装器.

* [ATBinHex for Delphi](https://github.com/Alexey-T/ATViewer/blob/master/Source/ATBinHex.pas) `[德尔福]`， [ATBinHex for Laz](https://github.com/Alexey-T/ATBinHex-Lazarus) .  `[FPC]` 无限大小文件的查看器，例如 Total Commander.

* [ATImageBox for Delphi](https://github.com/Alexey-T/ATViewer/blob/master/Source/ATImageBox.pas) `[德尔福]`， [ATImageBox for Laz](https://github.com/Alexey-T/ATImageBox-Lazarus) .  `[FPC]` 带有嵌入式 TImage 的 TScrollBox. 控件可以在内部自动定位图像.

* [CEF4Delphi](https://github.com/salvadordf/CEF4Delphi) .  `[Delphi]` `[FPC]` 项目将基于 Chromium 的浏览器嵌入到使用 Delphi 或 Lazarus/FPC 制作的应用程序中

* [WebView4Delphi](https://github.com/salvadordf/WebView4Delphi) .  `[Delphi]` `[FPC]` 将基于 Chromium 的浏览器嵌入到使用 Delphi 或 Lazarus/FPC for Windows 制作的应用程序中的项目.


## Other GUI

* [GMLib](https://code.google.com/p/gmlibrary) （谷歌地图库）（似乎被遗弃，GH 上的活跃分叉 [here](https://github.com/bero/GMLibrary) 和 [here](https://github.com/cadetill/gmlib_v1) ）.  `[Delphi]` 用于 Delphi/C++ Builder 的组件，它封装了 GoogleMaps API 以管理地图、标记、多边形、矩形、折线等.您可以放入地图中的所有对象.

* [VCL Styles Utils](https://github.com/rruz/vcl-styles-utils) .  `[Delphi]` 类和样式挂钩的集合，它们扩展、修复 QC 报告并向 VCL 样式添加新功能.
 // *补丁/增强的集合，将股票 VCL 风格引擎提升到一个新的水平.  Inno Setup 和 NSIS 的样式也可用. *

* [TaskbarListComponents](https://github.com/chaosben/theunknownones/tree/master/Components/TaskBarList) .  `[Delphi]` 为 Windows 7 任务栏列表接口（例如 ITaskbarlist3）设计为 Delphi 包装器的一组组件
// *需要 JVCL*

* [TFireMonkeyContainer](https://github.com/vintagedave/firemonkey-container) .  `[Delphi]` 用于托管 FMX HD 或 3D 表单的 Delphi VCL 组件. 这意味着您可以将 FireMonkey (FMX) 表单作为控件嵌入到 VCL 表单中，因此您可以设计 FMX 表单并在您的 VCL 应用程序中使用它.

* [PascalSCADA](http://sourceforge.net/projects/pascalscada). `[Delphi]` `[FPC]` Set of components (framework) for Delphi/Lazarus to make easy the development of industrial applications (HMI=Human Machine Interface/SCADA=System Control And Data Acquisition). It runs on Windows, Linux and FreeBSD.

* [Windows Ribbon Framework for Delphi](https://github.com/turbopack/ribbonframework) .  `[Delphi]` 这个Delphi 库允许Delphi 开发人员在他们的Delphi 应用程序中使用Windows Ribbon Framework. 此库使用本机 Windows 库来实现功能区功能. 它不像其他 Delphi 组件集（或 Delphi 的内置 Ribbon 仿真组件）那样模拟 Ribbon 用户界面.

* [DKLang](https://github.com/yktoo/dklang) .  `[Delphi]` DKLang 本地化包是一组旨在简化用 Delphi 编写的应用程序本地化的类.

* [GNU Gettext for Delphi, C++ and Kylix](https://sourceforge.net/projects/dxgettext/) .  `[Delphi]` 用于 Borland Delphi 和 Borland C++ Builder 的 GNU GetText 翻译工具.

* [OpenWire](https://sourceforge.net/projects/openwireproject) .  `[Delphi]` 该库允许编写高级 VCL 和 FireMonkey 组件以进行快速无代码应用程序开发. 使用该库开发的组件允许使用零行程序代码创建复杂的应用程序.

* [SynTaskDialog](https://github.com/synopse/mORMot/blob/master/SynTaskDialog.pas) .  `[Delphi]` `[FPC]` 实现 TaskDialog 窗口（Vista/Seven 原生，XP 模拟）

* [AnyiQuack](https://github.com/WladiD/AnyiQuack) .  `[Delphi]` 类jQuery控制动画框架.

* [TLanguages](https://github.com/albertodev01/TLanguages) .  `[Delphi]` VCL 和 FMX 的本地化工具.

* [BitMapEditor - Delphi](https://github.com/EverestSoftwareLLC/BitMapEdtior-Delphi) .  `[Delphi]` Delphi 的单一格式、简单的位图编辑器.

* [BearLibTerminal](https://github.com/cfyzium/bearlibterminal) .  `[Delphi]` 提供了一个带有字符单元网格的伪终端窗口和一个简单而强大的 API，用于灵活的文本输出和简单的输入处理.
*// 具有 Delphi 绑定的多平台动态库*

* [Dam](https://github.com/digao-dalpiaz/Dam) .  `[Delphi]` `[FPC]` 带有格式化文本的 Delphi 和 Lazarus 消息对话框.

* [Windows 7 Taskbar Components](https://delphi.fsprolabs.com/) .  `[Delphi]` Windows 7 中最显着的功能之一是新的 Windows 任务栏. 它提供了一种控制桌面、管理窗口和启动应用程序的新方法.


## Database ##

* [ZeosLib](http://sourceforge.net/projects/zeoslib) .  `[Delphi]` `[FPC]` 用于 MySQL、PostgreSQL、Interbase、Firebird、MS SQL、Sybase、Oracle 和 SQLite 的数据库组件集.

* [Unified Interbase](https://github.com/hgourvest/uib) .  `[Delphi]` 使用 Interbase、FireBird 和 YAFFIL 的组件集. 这些组件的诞生是为了在多线程环境（例如服务器）中尽可能快地使用 Interbase、FireBird 或 Yaffil.

* [ASQLite](https://github.com/remobjects/ASQLite3) .  `[Delphi]` 来自 aducom 软件的 Delphi SQLite DAC 组件集，基于 Delphi 2009 的最新版本，并更新以支持 Delphi 的 RemObjects Data Abstract for Delphi 中包含的较新版本.

* [TxQuery](https://github.com/ccy/txquery) .  `[Delphi]` TDataSet 后代组件，可用于使用 SQL 语句查询一个或多个 TDataSet 后代组件. 它在 Delphi 100% 源代码中实现，不需要 DLL，因为它实现了自己的 SQL 语法解析器和 SQL 引擎.

* [Delphi-ORM](https://github.com/danieleteti/delphi-orm) .  `[Delphi]` Delphi XE2-7 (Win32) 的对象关系映射. 支持 FirebirdSQL、SQLServer 和 SQLite3.

* [delphimemcache](https://code.google.com/p/delphimemcache) .  `[Delphi]` 为 memcached 实现线程安全客户端.
// *需要 Indy 10*

* [SynDB](https://github.com/synopse/mORMot) ([docs](http://synopse.info/files/html/Synopse%20mORMot%20Framework%20SAD%201.18.html#TITL_126) ）.  `[Delphi]` `[FPC]` 高性能直接访问 SQLite3、Oracle、MSSQL、PostgreSQL、Firebird、MySQL、ODBC、OleDB，包括远程 HTTP 连接和直接 JSON 支持.

* [SynMongoDB](https://github.com/synopse/mORMot/blob/master/SynMongoDB.pas) ([docs](http://blog.synopse.info/post/2014/05/07/MongoDB-database-access) ）.  `[Delphi]` `[FPC]` 提供对任何 MongoDB 服务器、其自定义数据类型、JSON 或通过 `TDocVariant` 自定义变体文档存储的直接低级访问.

* [DSharp](https://bitbucket.org/sglienke/dsharp) .  `[Delphi]` 用于在 Delphi 中提供数据绑定的小型库. 它不需要特殊的组件来将数据绑定到属性. 它还提供依赖注入、MVVM 和更多有趣的实用程序.

* [ghORM](https://github.com/leledumbo/ghORM) .  `[FPC]` 对象关系映射单元通过抽象后端和简单的数据检索（带过滤）、插入和更新来简化从 Free Pascal 的数据库访问.

* [tDBF](http://sourceforge.net/p/tdbf/code/HEAD/tree) .  `[Delphi]` `[FPC]` 适用于 Delphi、BCB、Kylix、FreePascal 的原生 dBASE III+、dBase IV 和 dBase 2k 数据访问组件. 它允许您创建不需要任何特殊安装程序的非常紧凑的数据库程序. 数据库引擎代码直接编译到您的可执行文件中.

* [Redis client](https://github.com/danieleteti/delphiredisclient)  `[Delphi]` Delphi Redis Client 版本 2 与 Delphi 10.1 Berlin 及更高版本兼容. 警告！ 如果您使用较旧的 Delphi 版本，则必须使用 [Delphi Redis Client Version 1](https://github.com/danieleteti/delphiredisclient/tree/DELPHI_REDIS_CLIENT_VERSION_1) 适用于 Delphi 10 Seattle、XE8、XE7、XE6 和 XE5（应该也适用于旧版本）. 该客户端能够发送所有 Redis 命令并使用内部解析器读取响应.

* [QDAC3](http://blog.qdac.cc/?page_id=139)  （SVN：svn://www.qdac.cc/QDAC3）.  `[Delphi]` 代表快速数据访问组件. 有用的单元，例如 QJson（易于使用的 json 单元）、QWorker（作业交付）等.
 // *中文描述和评论，作者不擅长英文. 我自己还没有测试过这个库.*

* [InstantObjects](https://github.com/EtheaDev/InstantObjects) .  `[Delphi]` 用于在 Delphi 中开发面向对象的业务解决方案的集成框架. 该框架为开发过程以及为最终应用程序提供动力的引擎提供了基础.  InstantObjects 提供： 通过集成的双向工具在 Delphi IDE 中实现模型； 最常见的关系数据库或基于 XML 的平面文件中的对象持久性； 通过标准数据感知控件呈现对象.

* [Alcinoe](#general-libraries) . 火鸟/MySQL/SQLite3/Memcached/MongoDb/SphinxQL.

* [SynBigTable](https://github.com/synopse/mORMot/blob/master/SynBigTable.pas) .  `[Delphi]` `[FPC]` 类用于存储大量数据并快速检索.

* [tiOPF](https://github.com/graemeg/tiopf) .  `[Delphi]` `[FPC]` Object Persistent Framework 用 Object Pascal 编写，用于 Delphi 和 Free Pascal (FPC) 编译器.  tiOPF 简化了面向对象的业务模型到关系数据库的映射. 持久层可用于 Firebird、Oracle、MS SQL Server、MySQL、PostgreSQL、SQLite、NexusDB、XML、CSV、TAB、Remote（通过 HTTP）等等. 它还允许您使用您选择的数据库连接组件，如 IBX、dbExpress、DOA、SqlDB、FBLib 等.

* [hcOPF](https://sourceforge.net/projects/larryhengensopf) .  `[Delphi]` 用 Embarcadero 的 Delphi (Object Pascal) 编写的 Object Persistent Framework. 这个值类型框架提供了一个由属性对象组成的基类（ThcObject），这些属性对象可以自动持久化到对象存储（通常是 RDBMS）中.

* [Marshmallow](https://bitbucket.org/soundvibe/marshmallow/wiki/Home) .  `[Delphi]` 受 .NET micro ORM（主要来自 PetaPoco）和 Java Hibernate 启发的 Delphi XE2-7 (Win32) 的对象关系映射. 由 Linas Naginionis 开发. 支持 SQLite、Sybase ASA、SQL Server、Firebird、Oracle、MySQL、PostgreSQL、MongoDB. 用途 [Spring](http://code.google.com/p/delphi-spring-framework/) 框架. 在积极发展中.

* [DelphiCassandra](https://github.com/grijjy/DelphiCassandra) .  `[Delphi]` 与Cassandra 数据库通信的Delphi 驱动程序类.

* [DelphiCouchbase](https://github.com/grijjy/DelphiCouchbase) .  `[Delphi]` 与 Couchbase 数据库通信的 Delphi 驱动程序类.

* [DelphiMongoDB](https://github.com/grijjy/DelphiMongoDB) .  `[Delphi]` 与 MongoDB 数据库通信的 Delphi 驱动程序类.

* [QuickORM](https://github.com/exilon/QuickORM) .  `[Delphi]` `[FPC]` QuickORM 是一个基于mORMot 框架的简单RestServer 和Restclient. 在几分钟内提供客户端-服务器应用程序的快速实现.

* [iORM](https://github.com/mauriziodm/iORM) .  `[Delphi]` 基于Delphi ORM 接口，对开发桌面和移动应用很有用.

* [d-ORModel](https://github.com/ultraware/d-ORModel) .  `[Delphi]` 基于模型和对象字段的 Delphi ORM.  LINQ 支持、完全类型化和编译时检查.


## Scripting ##

*在您的应用程序中使用脚本引擎*

* [Pascal Script](https://github.com/remobjects/pascalscript) .  `[Delphi]` `[FPC]` 免费脚本引擎，允许您在运行时在 Delphi 或 Free Pascal 项目中使用大部分 Object Pascal 语言. 它完全用 Delphi 编写，由一组可以编译成可执行文件的单元组成，无需分发任何外部文件.  Pascal Script 最初是为了需要一个好的工作脚本，当时还没有可用的脚本.

* [DWScript](https://bitbucket.org/egrange/dwscript) .  `[Delphi]` 面向对象的 Delphi 脚本引擎，基于 Delphi 语言，扩展自其他 Pascal 语言（FreePascal、Prism 等）. 它还引入了一些自己的 Pascal 语言扩展.

* [Delphi-JavaScript](https://code.google.com/p/delphi-javascript) .  `[Delphi]` 基于 Mozilla 的 Spidermonkey 的 delphi JavaScript 引擎.
// *需要Spidermonkey DLL*

* [Blaise](http://sourceforge.net/projects/blaise) .  `[Delphi]` 开源的面向对象的脚本语言. 语言特点：面向对象；  Unicode 支持； 可选类型，即动态或静态类型； 丰富的类型； 高级数学支持，例如复数、有理数和矩阵； 虚拟机架构； 协同程序； 熟悉的语言语法，受 Object Pascal、Python 和 Ada 的影响.

* [SpiderMonkey](https://github.com/synopse/mORMot/blob/master/SynSM.pas) .  `[Delphi]` `[FPC]` Mozilla JavaScript 引擎的绑定，包括 JIT 和多线程，通过 Delphi 变体轻松访问对象.
// *需要Spidermonkey DLL*

* [BESEN](https://github.com/BeRo1985/besen) .  `[Delphi]` `[FPC]` 在 Object Pascal 中完成 ECMAScript 第五版实现，可与 Delphi &gt;=7 和 Free Pascal &gt;= 2.5.1（可能也是 2.4.1）编译.

* [Python for Delphi (P4D)](https://github.com/pyscripter/python4delphi) .  `[Delphi]` `[FPC]` 将 Python dll 封装到 Delphi 和 Lazarus (FPC) 中的一组免费组件. 它们让您轻松执行 Python 脚本、创建新的 Python 模块和新的 Python 类型. 您可以将 Python 扩展创建为 dll 等等

* [CrystalLUA](https://github.com/d-mozulyov/CrystalLUA) .  `[Delphi]` Lua 绑定 (Delphi6-2007).
// *需要LUA DLL*

* [lua4delphi](https://github.com/danieleteti/lua4delphi) .  `[Delphi]` Lua 5.1 语言的 Delphi 绑定.
// *需要LUA DLL*

* [chakracore-delphi](https://github.com/tondrej/chakracore-delphi) .  `[Delphi]` `[FPC]` 用于 Microsoft 的 ChakraCore JavaScript 引擎库的 Delphi 和 Free Pascal 绑定和类.

* [VerySimple.Lua](https://github.com/Dennis1000/verysimplelua) .  `[Delphi]` Delphi XE5-D10.1 的 Lua 包装器，它自动为 Delphi &lt;-&gt; Lua 创建 OOP 回调函数.
// *需要LUA DLL*

* [QuickJS-Engine](https://github.com/Coldzer0/QuickJS-Pascal) .  `[Delphi]` `[FPC]` 用于 Bellard 的 Delphi 和 Free Pascal 绑定 [QuickJS](https://bellard.org/quickjs) JavaScript 引擎.


## Machine Learning ##

*机器学习和神经网络*

* [noe](https://github.com/ariaghora/noe) .  `[FPC]` 在纯对象帕斯卡中构建神经网络的框架.


## Non-visual Classes/Utils ##


## Compression

* [FWZip](https://github.com/AlexanderBagel/FWZip) .  `[Delphi]` 使用 Store 和 Deflate 方法处理 Zip 存档的类，支持 ZIP64、DataDescryptors、PKWARE 加密、NTFS 属性、文件名中的 Utf8.
 // *使用被编译成二进制的股票 ZLIB.obj. 俄语评论和描述.*

* [Abbrevia](http://sourceforge.net/p/tpabbrevia) ([Newest](https://github.com/TurboPack/Abbrevia) 和维护版本仅适用于最近的编译器版本）.  `[Delphi]` 用于 Delphi 和 C++Builder 的高级数据压缩工具包. 支持 PKZIP、Microsoft CAB、tar、gzip 和 bzip2 存档，并且可以创建自解压的可执行文件. 在 Windows 上，它还为 LZMA、Bzip2 和 WavPack SDK 以及 PPMd 解压缩提供了 Delphi 包装器.  Abbrevia 还具有多个可视化控件，可简化归档的显示和操作，包括树视图和列表视图组件. 特点：所有存档格式的 Unicode 文件名； 解压缩大多数 .zipx 和旧版 (PKZIP v1) zip；  ZIP64 支持大于 2GB 的档案； 跨区和拆分 zip 档案； 跨平台（Windows、OS X 和 Linux）； 不需要 DLL； 包括 COM 组件； 广泛的文档
// *第二个链接指向最新编译器版本的改编版本.*

* [SynLZ SynLZO SynZip PasZip](https://github.com/synopse/mORMot) .  `[Delphi]` `[FPC]` 几个高速压缩单元，具有 ZIP/LZ77 Deflate/Inflate、LZO 和 SynLZ 算法，采用帕斯卡和优化的汇编程序.

* [Delphi zlib](http://www.base2ti.com/?id=delphi.zlib) .  `[Delphi]` 最初由 Borland 使用的 zlib.obj 包装器. 支持 Delphi 到 XE3.

* [DIUcl](http://www.yunqa.de/delphi/products/ucl/index) .  `[Delphi]` DIUcl 是一个无损压缩库，具有极快和极小的（仅 200 字节！）ASM 解压缩器. 压缩时间和比率类似于 deflate/zip 和 bzip2. 流行的 UCL 压缩库的 Delphi 端口，它也被流行和知名的 UPX Ultimate Packer 用于 eXecutables.


## Encryption

* [Delphi Encryption Compendium (DEC)](https://github.com/MHumm/DelphiEncryptionCompendium) .  `[Delphi]` `[FPC]` Delphi &amp; C++ Builder 的加密库. 对称加密函数：Blowfish、Twofish、IDEA、Cast128、Cast256、Mars、RC2、RC4、RC5、RC6、Rijndael / AES、Square、SCOP、Sapphire、1DES、2DES、3DES、2DDES、3DDES、3TDES、3Way、Gost、 Misty、NewDES、Q128、SAFER、鲨鱼、鲣鱼、TEA、TEAN； 分组密码操作模式：CTSx、CBCx、CFB8、CFBx、OFB8、OFBx、CFSx、ECBx、GCM； 哈希：MD2、MD4、MD5、RipeMD128、RipeMD160、RipeMD256、RipeMD320、SHA、SHA1、SHA224、SHA256、SHA384、SHA512、SHA3-224、SHA3-256、SHA3-384、SHA3-512、Shake128、Shake256、Haval128、哈弗160、哈弗192、哈弗224、哈弗256、虎牌、巴拿马、惠而浦、惠而浦1、惠而浦T、方形、Snefru128、Snefru256、蓝宝石.

* [LockBox](http://sourceforge.net/projects/tplockbox) ([Newest](https://github.com/TurboPack/LockBox3) 和维护版本仅适用于最近的编译器版本）.  `[Delphi]` 用于密码学的 Delphi 库. 目前支持 Delphi XE6. 它提供对 AES、DES、3DES、Blowfish、Twofish、SHA2（包括新的 SHA-512/224 和 SHA-512/256）、MD5 的支持；  ECB、CBC、CFB8、CFB、CTR、ECB、OFB、PCBC链接模式、RSA数字签名和验证. 具有 OpenSSL 库的接口.
// *查看 [this](https://github.com/jarto/lockbox2) 页面以及替代版本.*

* [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas) .  `[Delphi]` `[FPC]` 快速加密例程（散列和密码），实现 AES、XOR、RC4、ADLER32、MD5、SHA1、SHA256 算法，针对速度进行了优化（调整汇编器和 VIA PADLOCK 可选支持）.

* [TForge](https://bitbucket.org/sergworks/tforge) .  `[Delphi]` `[FPC]` Delphi 编写的开源密码库，兼容 Free Pascal 编译器.  MD5、SHA1、SHA256、CRC32、Jenkins-One-At-Time、HMAC、PBKDF1、PBKDF2、AES、DES、RC4、RC5、Salsa20.

* [Spring4D](#general-libraries) .  CRC、DES、MD5、SHA

* [Fundamentals Code Library](#general-libraries) . 哈希：XOR、CRC、Adler、MD5、SHA、安全密钥MD5/SHA等； 密码：AES、DES、FUNE、RC2/4、RSA.

* [Alcinoe](#general-libraries) .  AES、Blowfish、MD5、SHA、安全密钥 MD5/SHA.

* [DCPcrypt (fork #1)](https://sourceforge.net/projects/dcpcrypt), [DCPcrypt (fork #2)](https://bitbucket.org/wpostma/dcpcrypt2010) .  `[Delphi]` Delphi 的加密组件套件.

* [bcrypt](https://github.com/viniciussanchez/bcrypt) .  `[Delphi]` 一个帮助你散列密码的库.

* [MurMur-Delphi](https://github.com/thibmo/murmur-delphi) .  `[Delphi]` MurMur1/2/3 以纯帕斯卡格式移植的快速种子哈希算法.

* [HashLib4Pascal](https://github.com/Xor-el/HashLib4Pascal) .  `[Delphi]` `[FPC]` Object Pascal 散列库在宽松的 MIT 许可证下发布，它提供了一个易于使用的接口来计算数据的散列和校验和. 它还支持基于状态的（增量）散列.  CRC、Adler、Murmur、Jenkins、MD5、SHA、Blake 等等.

* [SimpleBaseLib4Pascal](https://github.com/Xor-el/SimpleBaseLib4Pascal) .  `[Delphi]` `[FPC]` 简单易用的用于 Delphi/FreePascal 编译器的基本编码包，目前支持编码和解码各种基础，例如 Base16、Base32（各种变体）、Base58（各种变体）和 Base64 （各种变体）和 Base85（各种变体）.

* [CryptoLib4Pascal](https://github.com/Xor-el/CryptoLib4Pascal) .  `[Delphi]` `[FPC]` 在宽松的 MIT 许可下发布的 Object Pascal 密码库. 密码：AES（128、192 和 256）、Rijndael、Blowfish、Speck、ChaCha、(X)Salsa20、DSA、(DET)ECDSA（支持的曲线：NIST、X9.62、SEC2、Brainpool）、ECNR、ECSchnorr、 EdDSA (Ed25519, Ed25519Blake2B)


## XML/JSON/YAML/HTML

* [dataset-serialize](https://github.com/viniciussanchez/dataset-serialize) .  `[Delphi]` `[FPC]` 该组件是 DataSet 组件的 JSON 序列化程序. 允许您将 JSON 转换为 DataSet，将 DataSet 转换为 JSON，并以 JSON 格式导出和加载 DataSet 字段的结构. 兼容 VCL 项目、FMX 和 uniGUI（框架）.

* [OmniXML](https://github.com/mremec/omnixml) .  `[Delphi]` 用 Delphi 编写的 XML 解析器. 完全支持文档对象模型 (DOM) Level 1 规范； 支持可扩展标记语言（XML）1.0（第二版）规范； 内置支持不同的代码页（主要的 8 位代码页、UTF-8、UTF-16）； 兼容 MS XML 解析器； 快速解析大型和高度结构化的文档； 包括辅助函数以简化 XML 文档的处理； 简化的 XPath 支持.

* [SAX for Pascal](http://sourceforge.net/projects/saxforpascal) .  `[Delphi]` `[FPC]` 设计用于在 Pascal/Delphi 中实现 XML 解析的简单 API.
 // *基于回调的 XML 解析器，用于处理巨大的 XML 流. 自 2004 年以来被放弃，但几乎是唯一可用的 SAX 实现.*

* [KDS XML](http://sourceforge.net/projects/kdsxml) .  `[Delphi]` 用于流式解析、验证和生成 XML 的类库. 它是用 Object Pascal/Delphi 编写的，适用于 Win32 (Delphi) 和 Linux (Kylix). 它的一部分依赖于 SAX for Pascal 接口规范.
// *似乎死了.*

* [XML Partner](http://sourceforge.net/projects/tpxmlpartner) .  `[Delphi]` 通过易于使用的原生 VCL 和 CLX 组件，帮助将 XML 的功能添加到 Borland Delphi、C++ Builder 和 Kylix 项目中. 这些强大的组件简化了创建、修改和解析 XML 数据文档的过程.
// *好像死了，看看 [this](http://www.songbeamer.com/delphi) 可能是较新版本的页面.*

* [Open XML](http://www.philo.de/xml/downloads.shtml) .  `[Delphi]` 提供了广泛的方法、组件和基础类. 它可用于 Win32/Kylix 以及 .NET 开发.

* [SuperObject](https://github.com/hgourvest/superobject) .  `[Delphi]` `[FPC]` JSON 数据格式的解析器/编写器. 该工具包旨在与 Delphi 和 FreePascal（win32、win64、linux32、linux64、macOS Intel）一起使用. 也支持读/写 XML.

* [Libxml2 for pascal](https://sourceforge.net/projects/libxml2-pas) .  `[Delphi]` `[FPC]` Pascal 单元从 Daniel Veillard 访问流行的 XML API. 这应该至少可以从 Kylix 和 Delphi 中使用，但希望也可以从其他 Pascal 编译器（如 freepascal）中使用.

* [NativeXml](https://code.google.com/p/simdesign) .  `[Delphi]` 该组件包含一个占用空间小的 Object Pascal (Delphi) XML 实现，允许读取和写入 XML 文档. 你基本上只需要一个单元，你可以简单地将它添加到“uses”子句中. 您可以使用该软件从文件、流或字符串中读取 XML 文档. 加载例程生成可用于动态显示加载进度的事件. 您还可以使用它来创建和保存 XML 文档.

* [Delphi-XmlLite](https://github.com/the-Arioch/Delphi-XmlLite) .  `[Delphi]` Microsoft XmlLite 的标头翻译.  XmlLite 是 .NET XmlReader+Writer 的原生 C++ 实现，用于基于流的、只进的 XML 解析和创建.  XmlLite.dll 是必需的. 它包含在所有新版本的 Windows 和旧版本的服务包中.  XmlReader 的基于拉取的接口比 SAX 的基于事件的接口更易于使用.
// *Seems abandoned and reported to be somewhat buggy.*

* [Chimera](https://bitbucket.org/sivv/chimera). `[Delphi]` Open Source (MIT License) library for Delphi XE2 which provides a fast and cross platform JSON generator/parser (serializer/deserializer) under a license that doesn't suck.

* [SynCommons](https://github.com/synopse/mORMot/blob/master/SynCommons.pas) .  `[Delphi]` `[FPC]` 高速 JSON 库，使用 `TDocVariant` 自定义变体类型进行存储和访问.

* [SynCrossPlatformJSON](https://github.com/synopse/mORMot/blob/master/CrossPlatform/SynCrossPlatformJSON.pas) .  `[Delphi]` `[FPC]` 高速跨平台 JSON 库，使用 `TJSONVariant` 自定义变体类型进行存储和访问.

* [Json Data Objects](https://github.com/ahausladen/JsonDataObjects) .  `[Delphi]` 这个 Delphi 单元包含一个 JSON 解析器，支持 Delphi 2009-10Seattle 和平台 Win32、Win64 和 ARM Android（MacOS 和 iOS 可能工作）.

* [TinyJSON](http://sourceforge.net/projects/tiny-json) ([mirror at GH](https://github.com/tmcdos/tiny-json)). `[Delphi]` This is a small and clean library for associative arrays with Boolean / Integer / Float / WideString values. Allows import (export) from (to) JSON text. Extensive error-checking. Uses FunHash (by Sokolov Yura), HatTrie (by Daniel C. Jones), FastInt64 and FastMove (by FastCode project).

* [JSON delphi library](http://sourceforge.net/projects/lkjson) .  `[Delphi]` 这是一个实现JSON数据格式和对象结构的delphi库. 轻巧快速.

* [dwsJSON](https://bitbucket.org/egrange/dwscript/src/b9f99d4b8187defac3f3713e2ae0f7b83b63d516/Source/dwsJSON.pas?at=master) .  `[Delphi]` `[FPC]` dwsJSON 是一个支持 JSON 解析/创建的单元，它是 DWScript 的一部分，但相对“独立”，如果你将它添加到你的 Delphi（或 FPC）项目中，它不会拉出整个 DWScript 库，因此可以在您需要的任何地方使用.

* [Fundamentals Code Library](#general-libraries) .  JSON、XML.

* [Alcinoe](#general-libraries) .  XML/JSON 解析器.

* [delphi-yaml](https://bitbucket.org/OCTAGRAM/delphi-yaml) .  `[Delphi]` Delphi 7 兼容的 libyaml 绑定、YAML 解析器和用 C 实现的发射器库.提出了四层绑定.

* [GrijjyFoundation](#general-libraries) .  JSON/BSON.

* [VerySimpleXML](https://github.com/Dennis1000/verysimplexml) .  `[Delphi]` 用于 Delphi 2010 - 10.2.2 Tokyo 的轻量级、单单元、跨平台 XML 读取器/写入器

* [XSuperObject](https://github.com/onryldz/x-superobject) .  `[Delphi]` Delphi 跨平台快速 JSON

* [Internet Tools](https://github.com/benibela/internettools) .  `[Delphi]` `[FPC]` 包提供符合标准的 XPath 2.0、XQuery 1.0 和 XPath/XQuery 3.0 解释器，其中包括 JSONiq、模式匹配、CSS 和 HTML 的扩展； 以及在 Windows/Linux/macOS/Android 上执行 HTTP/S 请求的功能、受 XSLT 启发的网络抓取语言和自动更新类.

* [Delphi-JsonToDelphiClass](https://github.com/PKGeorgiev/Delphi-JsonToDelphiClass) ([Newer fork](https://github.com/JensBorrisholt/Delphi-JsonToDelphiClass) .  `[Delphi]` 基于 JSON 字符串生成 Delphi 类（Json To Delphi Class Generator / JSON Data Binding Tool）. 还包括与 GitHub 交互的单元.

* [XML Parser](http://www.destructor.de/xmlparser) .  `[Delphi]` `[FPC]` Delphi 和 FreePascal 的轻量级 ObjectPascal XML 解析器. 通过省略语法检查、格式良好检查和/或验证，并选择渐进式扫描技术，这个解析器非常快.

* [HTML parser](https://github.com/ying32/htmlparser) .  `[Delphi]` HTML 解析器. 支持Windows、macOS、iOS、Android平台. 中文评论

* [Neslib](https://github.com/neslib/Neslib.Xml) .  `[Delphi]` Delphi 的超轻量级跨平台 XML 库.

* [DJSON](https://github.com/mauriziodm/DJSON) .  `[Delphi]` Delphi JSON 对象映射器

* [fast-html-parser](https://github.com/z505/fast-html-parser) .  `[Delphi]` `[FPC]` 快速 HTML 解析器

* [THTMLWriter](https://github.com/NickHodges/delphihtmlwriter) .  `[Delphi]` 使开发人员能够创建 HTML 和 HTML 文档的类库. 它使用流畅的界面使创建 HTML 文本变得轻松自然.


## Language

*Pascal 和其他语言的工具*

* [Next Delphi Yacc & Lex](https://github.com/RomanYankovsky/ndyacclex) .  `[Delphi]` Delphi 的解析器生成器工具集.

* [Abstract Syntax Tree Builder](https://github.com/RomanYankovsky/DelphiAST) .  `[Delphi]` 使用 DelphiAST，您可以获取真正的 Delphi 代码并获得抽象语法树. 一次一个单位，但没有符号表.

* [Castalia-Delphi-Parser](https://github.com/jacobthurman/Castalia-Delphi-Parser) .  `[Delphi]` 这些文件构成了一个手写的高速解析器，用于称为“Delphi”的 Object Pascal 方言. 最初的工作是由 Martin Waldenburg 在 1990 年代后期完成的，该项目在 2003 年之前的某个时候被放弃了，当时我找到了代码并开始研究它. 我已根据需要对其进行了更新，以便与我的项目“Castalia”一起工作.

* [CrossPascal](https://github.com/BeRo1985/crosspascal) .  `[Delphi]` 旨在成为一个兼容 Delphi 7 的跨平台源到源编译器（连同来自 XE3 的新 unicode 字符串类型，但其中 ansistring 仍然是默认字符串类型，以便仍然与 Delphi 7 兼容），它生成中间 C 代码.
// *相当有趣的项目虽然似乎被放弃了*

* [pas2js](https://gitlab.com/freepascal.org/fpc/pas2js), [docs](http://wiki.freepascal.org/pas2js) .  `[Delphi]` `[FPC]` 一个开源的 Pascal 到 JavaScript 转译器. 它解析 Object Pascal 并发出 JavaScript.  JavaScript 当前是 ECMAScript 5 级别，应该在任何浏览器或 Node.js（目标“nodejs”）中运行. 基本上，支持 Delphi 7 语法. 用于 TMS WebCore 和 Elevate Web Builder 等工具.


## Memory managers

*实现动态内存分配的库*

* [FastMM](https://github.com/pleriche/FastMM4) .  `[Delphi]` Embarcadero Delphi Win32 和 Win64 应用程序的闪电快速替换内存管理器，不易出现内存碎片，并且支持共享内存，无需使用外部 .DLL 文件.
 // *自 2006 年以来用作库存内存管理器，但在简化版本中. 提供强大的内存泄漏/损坏检测工具.*

* [ScaleMM](https://github.com/andremussche/scalemm) .  `[Delphi]` Delphi 的快速扩展内存管理器

* [BrainMM](https://github.com/d-mozulyov/BrainMM) .  `[Delphi]` Delphi 极快的内存管理器.
// *用于更快对齐操作的高级内存分配功能.*

* [FastMM4-AVX](https://github.com/maximmasiutin/FastMM4-AVX) .  `[Delphi]` `[FPC]` FastMM4 fork 支持 AVX 和多线程增强（更快的锁定）

* [FastMM5](https://github.com/pleriche/FastMM5) .  `[Delphi]` Embarcadero Delphi 应用程序的快速替换内存管理器，可以很好地跨多个线程和 CPU 内核扩展，不易出现内存碎片，并且支持共享内存，无需使用外部 .DLL 文件. 版本 5 是对 FastMM 的完全重写.


## System

*低级助手的东西：内存，线程等*

* [OmniThreadLibrary](https://github.com/gabr42/OmniThreadLibrary) .  `[Delphi]` 简单易用的 Delphi 线程库.
// *在您的应用程序中轻松集成异步进程*

* [Delphi Detours Library](https://github.com/mahdisafsafi/delphi-detours-library) .  `[Delphi]` `[FPC]` 库允许您挂钩 Delphi 函数和对象方法以及 Windows API 函数. 它提供了一种插入和移除钩子的简单方法.
// *支持x64，调用原始函数，多钩子，COM/Interfaces/win32api，对象方法钩子，完全线程安全，Delphi 7/2005-2010/XE-XE7 &amp; Lazarus/FPC，支持64位地址*

* [MemoryModule](https://github.com/Fr0sT-Brutal/Delphi_MemoryModule) .  `[Delphi]` `[FPC]` 使用 MemoryModule 引擎，您可以将所有需要的 DLL 存储在二进制文件中，以使其保持独立. 附加的钩子单元允许透明地使用 MM 引擎，从而允许切换 MM/WinAPI 加载以及启用不知道 MM 的第 3 方动态加载 DLL 接口（使用 Interbase Express 组件和 Firebird 客户端库进行测试）.  MemoryModule 是 Joachim Bauch 的 C MemoryModule 的 Pascal 端口.

* [DirectoryWatcher](https://github.com/Wosi/DirectoryWatcher) .  `[Delphi]` 观察不同平台（Windows/Linux/Mac OS）上目录的变化.

* [ezthreads](https://github.com/mr-highball/ezthreads) .  `[FPC]` 简单易用的线程库

* [AsyncCalls](https://github.com/ahausladen/AsyncCalls) .  `[Delphi]` 异步函数调用框架


## Template

*基于模板生成文本输出的引擎*

* [SynMustache](https://github.com/synopse/dmustache) .  `[Delphi]` `[FPC]` Mustache 模板语言的 Delphi 实现，支持 Delphi 6 到 Delphi 10 Seattle（和 FPC/Lazarus 编译）.

* [Delphi Template Engine](http://sourceforge.net/projects/delphi-templeng) .  `[Delphi]` 模板引擎旨在用作 Delphi（主要是 Delphi 7）应用程序中的库，允许开发人员在他们的软件上使用模板，而无需担心实现它.

* [MustaPAS](https://github.com/leledumbo/mustapas) .  `[Delphi]` `[FPC]` 简单程序 Pascal 中的 Mustache 实现.

* [Sempare Template Engine](https://github.com/sempare/sempare-delphi-template-engine) .  `[Delphi]` 模板引擎允许灵活的文本操作. 它可以用于生成电子邮件、html、源代码、xml、配置等.它非常易于使用，灵活且可扩展，模板可读且可维护. 它支持：条件、循环、自定义函数和通过 RTTI 引用数据.  XE4、XE8+

* [DVD Chief Template Engine](https://github.com/Fr0sT-Brutal/TemplateEngine) .  `[Delphi]` `[FPC]` Delphi 废弃 PHP Smarty 模板引擎实现的分叉 [DVD Chief](http://dvdchief.com/delphi).

* [liquid-delphi](https://github.com/arimateia/liquid-delphi) .  `[Delphi]` 流行的Delphi端口 [Ruby Liquid templating language](https://shopify.github.io/liquid) 和 dotLiquid 实现. 这是一个单独的项目，旨在保留与原始模板语法相同的模板语法，同时尽可能使用 delphi 编码约定.


## Logging

* [Log4d](https://github.com/landrix/Log4d-for-Delphi) .  `[Delphi]` `[FPC]` 基于Log4j的Delphi日志系统实现.

* [TraceTool](http://tracetool.sourceforge.net/). `[Delphi]` C#, C++, Delphi, ActiveX and Java trace framework and a trace viewer.

* [LoggerPro](https://github.com/danieleteti/loggerpro) .  `[Delphi]` 一个现代的、可插入的 Delphi 日志框架.

* [SynLog](https://github.com/synopse/mORMot/blob/master/SynLog.pas) .  `[Delphi]` `[FPC]` Synopse 项目使用的日志记录功能.

* [slf4p](https://github.com/michaelJustin/slf4p) .  `[Delphi]` `[FPC]` 一个简单的日志外观，支持 LazLogger、Log4D 和其他日志框架.

* [GrijjyCloudLogger](https://github.com/grijjy/GrijjyCloudLogger) .  `[Delphi]` 远程日志记录工具，允许您通过 Intranet 或 Internet 从 Windows、Linux、iOS、Android 和 macOS 设备将日志消息发送到在 Windows 上运行的查看器. 除了与任何数据一起发送消息外，它还具有许多功能，包括自定义实时监视、对象的远程实时视图、跟踪实时内存使用情况、对象分配、增长泄漏等.

* [QuickLogger](https://github.com/exilon/QuickLogger) .  `[Delphi]` `[FPC]` Delphi/freepascal/.NET (Windows/Linux) 库，用于记录文件、控制台、内存、电子邮件、休息、电报、松弛、事件日志、redis、ide 调试消息和抛出事件. .

* [jachLog](https://github.com/jachguate/jachLogMgr) .  `[Delphi]` 纯帕斯卡，灵活，可扩展和轻量级的库，为您的 Delphi 应用程序添加日志记录功能. 支持多个日志目的地. 该库支持多线程应用程序，并且本身是多线程的，以最大限度地减少写入日志可能对关键任务应用程序的性能产生的影响.

## Math

* [Big Decimal Math](https://github.com/benibela/bigdecimalmath) .  `[Delphi]` 该单元提供任意精度的 BCD 浮点数类型. 它可以像任何数字类型一样使用并支持： 至少 10-2147483647 到 102147483647 之间的数字，精度为 2147483647； 所有标准算术和比较运算符； 舍入函数（floor、ceil、to-even、..）； 一些更高级的操作，例如 power 和 sqrt.

* [TIntX](https://github.com/Xor-el/IntXLib4Pascal) .  `[Delphi]` `[FPC]` IntX 任意精度整数库的 Pascal 端口，具有快速、约 O(N * log N) 的乘法/除法算法实现. 它提供了关于整数的所有基本算术运算、比较、按位移位等.它还允许解析不同基数的数字并将它们转换为字符串，也可以在任何基数中. 这个库的优点是它的快速乘法、除法和从基数到基数的转换算法. 所有算法的快速版本都基于使用快速哈特利变换的大整数的快速乘法，该变换运行时间为 O(N * log N * log log N)，而不是经典的 O(N^2).

* [DelphiBigNumberXLib](https://github.com/Xor-el/DelphiBigNumberXLib) .  `[Delphi]` Delphi 的任意精度库，支持整数和浮点计算.

* [FastMath](https://github.com/neslib/FastMath) .  `[Delphi]` Delphi 数学库，针对快速性能进行了优化（有时以不执行错误检查或失去一点准确性为代价）. 它使用手动优化的汇编代码来实现比 Delphi RTL 提供的等效功能更好的性能.
// *浮点、向量、矩阵运算.*

* [MPArith](http://www.wolfgang-ehrhardt.de/misc_en.html#mparith) .  `[Delphi]` 多精度整数、有理数、实数和复数算术.

* [AMath](http://www.wolfgang-ehrhardt.de/misc_en.html#amath) 和 [DAMath](http://www.wolfgang-ehrhardt.de/misc_en.html#damath). `[Delphi]` Accurate mathematical methods without using multi precision arithmetic 和 double precision accurate mathematical methods without using multi precision arithmetic or assembler respectively.

* [ALGLIB](http://www.alglib.net/download.php) .  `[Delphi]` `[FPC]` 跨平台数值分析和数据处理库. 它支持多种操作系统（Windows 和 POSIX，包括 Linux）.  ALGLIB 功能包括： 数据分析（分类/回归、统计）； 优化和非线性求解器； 插值和线性/非线性最小二乘拟合； 线性代数（直接算法，EVD/SVD），直接和迭代线性求解器； 快速傅立叶变换和许多其他算法.
// 免费版是针对个人和学术用途许可的通用 C 内核的 D​​elphi 包装器.

* [CAI NEURAL API](https://github.com/joaopauloschuler/neural-api) .  `[FPC]` `[Delphi]` 针对 AVX、AVX2 和 AVX512 指令集以及支持 OpenCL 的设备（包括 AMD、Intel 和 NVIDIA）进行了优化的跨平台神经网络 API.

* [DFF Library](http://www.delphiforfun.org/programs/library/Default.htm) .  `[Delphi]` `[FPC]` 大浮点、大整数、天文计算


## Command-line

*用于解析命令行参数的库*

* [TCommandLineReader](https://github.com/benibela/rcmdline) .  `[Delphi]` `[FPC]` 这个单元为 Lazarus 和 Delphi 提供了一个先进的、独立于平台的命令行解析器. 它检查允许的选项，自动打印包含所有选项列表的帮助，并且 - 与 rtl 中的解析器相反 - 在 Windows 和 Linux 上的行为相同.

* [CommandLineParser](https://github.com/VSoftTechnologies/VSoft.CommandLineParser) .  `[Delphi]` 简单命令行选项解析器 - 源自 DUnitX 项目.

* [GpCommandLineParser](https://github.com/gabr42/GpDelphiUnits/blob/master/src/GpCommandLineParser.pas) .  `[Delphi]` 基于属性的命令行解析器.

* [JPL.CmdLineParser](https://github.com/jackdp/JPLib/blob/master/Base/JPL.CmdLineParser.pas) .  `[Delphi]` `[FPC]` Delphi 和 Free Pascal 的命令行解析器

* [Nullpobug.ArgumentParser](https://github.com/tokibito/delphi-argparse) .  `[Delphi]` `[FPC]` Delphi 和 Free Pascal 的命令行解析器


## Other non-visual

* [TRegExpr](https://github.com/andgineer/TRegExpr) .  `[Delphi]` `[FPC]` 纯 Object Pascal 中的正则表达式引擎.

* [FLRE](https://github.com/BeRo1985/flre) .  `[Delphi]` `[FPC]` FLRE (Fast Light R egular E expressions) 是一个快速、安全和高效的正则表达式库，它在 Object Pascal（Delphi 和 Free Pascal）中实现，但它甚至可以从其他语言，如 C/C++ 等.

* [OnGuard](http://sourceforge.net/projects/tponguard) ([Alternate](https://github.com/TurboPack/OnGuard-VCL) and maintained version for recent compiler version only). `[Delphi]` Library to create demo versions of your Borland Delphi & C++Builder applications. Create demo versions that are time-limited, feature-limited, limited to a certain number of uses, or limited to a certain # of concurrent network users.
// *第二个链接指向最新编译器版本的改编版本.*

* [StringSimilarity](https://github.com/chaosben/theunknownones) .  `[Delphi]` 包设计用于一些模糊和语音字符串比较算法. 到目前为止，实现了以下算法：DamerauLevenshtein、Koelner Phonetik、SoundEx、Metaphone、DoubleMetaphone、NGram、Dice、JaroWinkler、NeedlemanWunch、SmithWatermanGotoh、MongeElkan.

* [PubSub Chimera](https://code.google.com/p/pubsubchimera) .  `[Delphi]` 用于 Delphi 的开源（MIT 许可证）库，它提供了一个快速且跨平台的 PubSub 和 Message Queue 实现，其许可证并不糟糕.

* [DuckDuckDelphi](https://code.google.com/p/duckduckdelphi) .  `[Delphi]` 为 Delphi 对象添加了简单的鸭子类型，并提供了一个 RTTI 助手类来简化许多常见的 RTTI 任务.

* [byterage](https://github.com/quartexNOR/byterage) .  `[Delphi]` Object pascal 类库旨在消除流的一些限制. 该框架使用起来非常简单，只有一个公共祖先类 (TBRBuffer)，它定义了一组与存储无关的机制，用于分配、缩放、插入、删除和以其他方式操作一段原始二进制数据.

* [stateless](https://github.com/SirRufo/stateless) .  `[Delphi]` 用于在 Delphi 代码中创建状态机的简单库.

* [GenericTree](https://github.com/davidberneda/GenericTree) .  `[Delphi]` Delphi 实现了一个通用的Tree 结构.

* [Delphi Event Bus](https://github.com/spinettaro/delphi-event-bus)  （简称 DEB）.  `[Delphi]` Delphi 的事件总线框架.

* [DelphiEventBus](https://github.com/BitecSPB/DelphiEventBus) .  `[Delphi]` Delphi 的另一个事件总线框架，带有注释和丰富的事件过滤.

* [DHibernate](https://github.com/thecocce/delphi-hibernate) .  `[Delphi]` 基于 Hibernate 和 NHibernate for Delphi 的对象持久化框架.
// *自 2012 年以来被遗弃*

* [UniConv](https://github.com/d-mozulyov/UniConv) .  `[Delphi]` `[FPC]` 通用文本转换库是一个通用的快速和紧凑的库，旨在根据 Unicode 联盟的最新标准对文本寄存器进行转换、比较和更改. 库函数非常类似于 ICU、libiconv 和 Windows.kernel，它们是流行操作系统的事实上的标准.

* [CachedBuffers](https://github.com/d-mozulyov/CachedBuffers) .  `[Delphi]` `[FPC]` 该库对于顺序数据读取或写入的任务是不可替代的，特别是在对性能要求提高且数据量大的情况下.

* [CachedTexts](https://github.com/d-mozulyov/CachedTexts) .  `[Delphi]` `[FPC]` 强大而紧凑的跨平台库，旨在以最大可能的性能解析和生成文本数据. 取决于另外两个库：CachedBuffers 和 UniConv.

* [ZEXMLSS](https://github.com/Avemey/zexmlss) .  `[Delphi]` `[FPC]` Lazarus/Delphi 组件，用于读/写 ods、excel xml、xlsx.

* [PasMP](https://github.com/BeRo1985/pasmp) .  `[Delphi]` `[FPC]` Object Pascal 的并行处理/多处理库.

* [ICU4PAS](http://www.crossgl.com/icu4pas/index.html) .  `[Delphi]` `[FPC]` Object Pascal，跨平台，直接类包装器，基于成熟且广泛使用的 C/C++ ICU 库集，提供 Unicode 支持、软件国际化 (i18n) 和全球化 (g11n)，为应用程序提供所有平台上的结果相同. 您可以在 Windows 上使用 Delphi 和 FreePascal 以及在 Linux 上使用 Kylix 和 FreePascal.
// *自 2007 年以来没有更新，但 ICU 界面可能保持不变*

* [GpDelphiUnits](https://github.com/gabr42/GpDelphiUnits) .  `[Delphi]` 有用的 Delphi 单元集合. 各种 TList 后代、TList-compatible 和 TList-similar 类. 动态分配，O(1) 入队和出队，线程安全，微锁队列. 与一些附加功能的 64 位文件函数的接口. 字符串哈希、表和字典.  Win32/Win64 包装器和帮助函数的集合. 时区例程. 嵌入式文件系统.

* [BaseNcodingPascal](https://github.com/Xor-el/BaseNcodingPascal) .  `[Delphi]` `[FPC]` 使用 base32、base85、base128 和其他 FPC 和 Delphi 算法将二进制数据编码为字符串的库.

* [ByteSizeLibPascal](https://github.com/Xor-el/ByteSizeLibPascal) .  `[Delphi]` `[FPC]` TByteSize 是一个实用“记录”，通过消除所表示值的歧义，使代码中的字节大小表示更容易.

* [EmailValidationPascal](https://github.com/Xor-el/EmailValidationPascal) .  `[Delphi]` `[FPC]` 在 Pascal/Delphi 中验证电子邮件地址语法的简单类.

* [PRNG](http://www.wolfgang-ehrhardt.de/misc_en.html#prng) .  `[Delphi]` 七个快速伪随机数生成器，周期长度远大于 Pascal 的随机函数. 所有这些都是用上下文记录实现的，因此可以同时使用几个独立的生成器，它们不是密码安全的. 此外还有三个密码生成器.

* [CSV File and String Reader](https://www.codeproject.com/Tips/783493/Delphi-CSV-File-and-String-Reader-Classes) .  `[Delphi]` TnvvCSVFileReader 和 TnvvCSVStringReader 是类似于单向数据集的轻量级和快速类.

* [HTMLBuilder](https://github.com/guitorres/htmlbuilder). `[Delphi]` Build simplified html with pascal code.

* [Marvin.IA](https://github.com/marvinbraga/Marvin.IA) .  `[Delphi]` 面向对象的 Pascal 原语（仅接口和类）的机器学习集合.

* [FreePascal Generics.Collections](https://github.com/maciej-izak/generics.collections) .  `[FPC]` FreePascal Generics.Collections 库（TList、TDictionary、THashMap 等）

* [FuzzyWuzzy.pas](https://github.com/DavidMoraisFerreira/FuzzyWuzzy.pas) .  `[FPC]` 著名的 Python 模糊字符串匹配包的端口，它使用 Levenshtein 距离来计算字符串序列之间的差异.

* [GS.Core](https://github.com/VincentGsell/GS.Core) .  `[Delphi]` `[FPC]` 几个项目共享的核心功能.
// *线程池、文件操作、Key&lt;&gt;Value 数据库、JSON 库等*
* [PascalTZ](https://github.com/dezlov/PascalTZ) .  `[FPC]` 帕斯卡时区允许您在不同时区的当地时间和 GMT/UTC 之间进行转换，同时考虑到时区规则的历史变化.

* [Charset Enigma](https://github.com/ms301/charset-enigma) .  `[Delphi]` Delphi 字符集检测器社区版

* [DelphiPatterns](https://github.com/jimmckeeth/DelphiPatterns) .  `[Delphi]` 用Delphi语言实现的全套设计模式

* [Markdown Processor for Pascal](https://github.com/grahamegrieve/delphi-markdown) .  `[Delphi]` `[FPC]` 这是一个 Pascal (Delphi) 库，用于处理 Markdown 到 HTML

* [Coroutine-based multithreading library](https://github.com/Purik/AIO) .  `[Delphi]` AIO 在 Delphi 中实现面向过程的编程 (POP) 风格. 这意味着开发人员可以结合 OOP 和 POP 的优势，将逻辑拆分为多个状态机，将它们调度到线程，通过 GoLang 等通信通道连接它们

* [Rapid.Generics](https://github.com/d-mozulyov/Rapid.Generics) .  `[Delphi]` 用于 Delphi (XE8+) 的 Rapid 泛型/默认等效类

* [Keras4Delphi](https://github.com/Pigrecos/Keras4Delphi) .  `[Delphi]` 高级神经网络 API，用 Pascal 和 Python 绑定编写

* [TZDB](https://github.com/pavkam/tzdb) .  `[Delphi]` `[FPC]` 用于 Delphi/FreePascal 的 IANA 时区数据库

* [PascalUtils](https://github.com/isemenkov/pascalutils) .  `[Delphi]` `[FPC]` Delphi 和 utils 数据结构的 object pascal 库

* [libPasC-Algorithms](https://github.com/isemenkov/libpasc-algorithms) .  `[Delphi]` `[FPC]` 通用数据结构和算法的Delphi和object pascal库. 从 c 算法存储库和其他来源重写的库.

* [VSoft.Messaging](https://github.com/VSoftTechnologies/VSoft.Messaging) .  `[Delphi]` 为 Delphi 应用程序提供内部同步/异步发布/订阅消息系统的库.

* [Delphi-Hunspell](https://github.com/darianmiller/Delphi-Hunspell) .  `[Delphi]` 简单 [Hunspell](http://hunspell.github.io) Delphi 的拼写检查引擎包装器.

* [CocinAsync](https://bitbucket.org/sivv/cocinasync) .  `[Delphi]` Delphi 的高性能库，用于简化编码并提高异步和多线程应用程序的性能.

* [Delphi LightSaber](https://github.com/GodModeUser/Delphi-LightSaber) .  `[Delphi]` Jedi 库的轻量级替代品.
简单、清晰、无混淆、完全注释的代码. 没有外部依赖. 数百个超级有用的功能，用于文件/文件夹/磁盘操作、快速（缓冲）二进制文件访问、字符串转换、操作系统版本检测等.

* [LAMW](https://github.com/jmpessoa/lazandroidmodulewizard) .  `[FPC]` Lazarus Android Module Wizard 使用 Lazarus/Free Pascal 创建 JNI Android 可加载模块 (.so) 和 Android Apk.


## OS ##

*有助于处理特定于操作系统内部的工具*

* [GLibWMI](http://sourceforge.net/projects/glibwmi) .  `[Delphi]` Delphi 组件库，将用于访问 Windows 的 WMI 的类封装在一组 VCL 中.  BiosInfo、PrinterInfo、DiskInfo 等.允许访问 WMI 类：WIN32_Bios、WIN32_Printers、WIN32_DiskDrive.

* [MemoryMap](https://github.com/AlexanderBagel/ProcessMemoryMap/tree/master/MemoryMap) .  `[Delphi]` 一组类，用于获取有关正在运行的进程的内存的所有信息.

* [The Drag and Drop Component Suite](https://github.com/landrix/The-Drag-and-Drop-Component-Suite-for-Delphi) .  `[Delphi]` VCL 组件库，使您的 Delphi 和 C++Builder 应用程序支持基于 COM 的拖放并与 Windows 剪贴板集成.

* [TSMBIOS](https://github.com/RRUZ/tsmbios) .  `[Delphi]` `[FPC]` 允许使用 Object Pascal 语言（Delphi 或 Free Pascal）访问系统管理 BIOS (SMBIOS).  SMBIOS（系统管理BIOS）是DMTF开发的标准. 存储在 SMBIOS 中的信息包括设备制造商、型号名称、序列号、BIOS 版本、资产标签、处理器、端口和安装的设备内存.

* [VersionInfo for Delphi](http://melander.dk/articles/versioninfo) .  `[Delphi]` 该库使从 Windows 可执行文件和 DLL 的版本信息资源中读取值变得非常容易. 可选地通过类帮助器使用版本信息属性扩展 TApplication 类.

* [Magenta Systems WMI and SMART Component](http://www.magsys.co.uk/delphi/magwmi.asp) .  `[Delphi]` 包含 WMI、SMART 和 SCSI PassThrough 功能，特别适用于获取硬盘信息和配置网络适配器，但也适用于许多其他一般用途.  MagWMI 使用类似 SQL 的命令提供对任何 WMI 信息的一般视图访问，以及许多与 TCP/IP 配置相关的专用功能，例如设置适配器 IP 地址、计算机名称、域/工作组、BIOS 和磁盘驱动器信息.

* [madKernel](http://help.madshi.net/madKernel.htm) .  `[Delphi]` 这个包主要是关于内核对象的. 最重要的对象类型封装在接口中，利用所有特定的 kernel32 API. 具有以下接口包装器：事件、互斥体、线程、进程、Windows、模块、托盘图标、共享内存缓冲区.
// *免费提供非商业用途的源代码（仅限）与一些 [conditions](http://help.madshi.net/License.htm) . 可作为“madCollection”安装程序的一部分下载. 相当有据可查. 需要 `madBasic` 包.*

* [madSecurity](http://help.madshi.net/madSecurity.htm) .  `[Delphi]` 该软件包可以轻松处理共享和其他安全对象，如文件安全或注册表安全. 为了能够做到这一点，该软件包还具有围绕帐户、ACE 和 ACL 的功能.
// *免费提供非商业用途的源代码（仅限）与一些 [conditions](http://help.madshi.net/License.htm) . 可作为“madCollection”安装程序的一部分下载. 相当有据可查. 需要 `madBasic` 包.*

* [madShell](http://help.madshi.net/madShell.htm) .  `[Delphi]` 该包实现了经常需要的 shell 功能，从“Windows”文件夹或“Program Files”文件夹等特殊文件夹开始，然后是 Shell ID 列表、Shell 对象和 Shell 事件. 然后你会发现关于 ShortCuts/ShellLinks 的功能，最后是关于显示模式的一切.
// *免费提供非商业用途的源代码（仅限）与一些 [conditions](http://help.madshi.net/License.htm) . 可作为“madCollection”安装程序的一部分下载. 相当有据可查. 需要 `madBasic` 包.*

* [WindowsAutorun](https://github.com/ms301/WindowsAutorun) .  `[Delphi]` 帮助您管理 Windows 操作系统中的自动加载.

* [ActiveDirectory4Delphi](https://github.com/EdZava/VCL-ActiveDirectory4Delphi) .  `[Delphi]` Delphi 基本库，用于在 Active Directory 中验证和验证 LDAP 用户.


## Report generating ##

* [Report Manager](http://reportman.sourceforge.net) .  `[Delphi]` 报表管理器是一个报表应用程序（报表管理器设计器）和一组用于预览、导出或打印报表的库和实用程序. 包括原生 .Net 和 Delphi/C++Builder 库、ActiveX 组件以及标准动态链接库，可用于任何语言，如 GNU C.

* [FortesReport](https://github.com/fortesinformatica/fortesreport-ce) .  `[Delphi]` FortesReport 是一个功能强大的报告生成器，可作为 Delphi 的组件包使用.

* [mORMotReport](https://github.com/synopse/mORMot/blob/master/SQLite3/mORMotReport.pas) ([docs](http://synopse.info/files/html/api-1.18/mORMotReport.html) ）.  `[Delphi]` 快速高效的基于代码的报表组件，带有预览表格和PDF导出.


## Unit Testing ##

* [DUnitX](https://github.com/VSoftTechnologies/DUnitX) .  `[Delphi]` 新的测试框架，借鉴了DUnit、NUnit等测试框架的思想. 它旨在与 Delphi 2010 或更高版本一起使用，它利用了旧版本 Delphi 中不可用的语言/RTL 功能.

* [DUnit](http://dunit.sourceforge.net) .  `[Delphi]` 单元测试框架，多年来一直是标准测试框架，Delphi IDE 现在附带这个库.
 // *自 XE 起包含，自 XE8 起弃用，有利于 DUnitX； 似乎被遗弃了.*

* [DUnit2](http://dunit2.sourceforge.net) .  `[Delphi]` DUnit 项目的分叉，添加了几个新功能.
// *似乎被遗弃了，缺少上一个 DUnit 版本的一些功能.*

* [DelphiSpec](https://github.com/RomanYankovsky/DelphiSpec) .  `[Delphi]` 用于运行以简单语言编写的自动化测试的库. 因为它们是用通俗易懂的语言编写的，所以团队中的任何人都可以阅读它们. 因为任何人都可以阅读它们，所以您可以使用它们来帮助改善团队的沟通、协作和信任.

* [Delphi-Mocks](https://github.com/VSoftTechnologies/Delphi-Mocks) .  `[Delphi]` Delphi XE2 或更高版本的简单模拟框架. 允许您模拟类和接口以进行测试.

* [DUnit-XML](https://github.com/VSoftTechnologies/DUnit-XML). `[Delphi]` Test runner that allows DUnit Tests to output NUnit compatible XML.

* [Smoketest](https://github.com/deltics/delphi.libs/tree/master/smoketest) .  `[Delphi]` 使用 Delphi 语言为 Microsoft Windows 编写测试和性能基准测试的框架. 它已经在从 7 到 2010 的所有版本的 Delphi 上进行了测试.

* [SynTests](https://github.com/synopse/mORMot/blob/master/SynTests.pas) .  `[Delphi]` `[FPC]` 单元测试功能，包括模拟和存根.

* [OpenCTF](http://openctf.sourceforge.net) .  `[Delphi]` Embarcadero Delphi 的测试框架插件，它自动检查表单（或数据模块）中的所有组件. 它为许多组件必须通过重复测试的大型项目构建自动质量检查提供了一种简单的方法.  OpenCTF 基于 DUnit 开源测试框架，并通过专门的测试类和辅助函数对其进行了扩展.

* [DelphiUIAutomation](https://github.com/jhc-systems/DelphiUIAutomation) .  `[Delphi]` 封装了 MS UIAutomation 库的 Delphi 类.  DelphiUIAutomation 是一个用于自动化基于 Win32 的富客户端应用程序的框架（并专门使用 Delphi XE5 进行了测试）. 它是用 Delphi XE5 编写的，不需要使用脚本语言. 它提供了一致的面向对象的 API，隐藏了 Microsoft 的 UIAutomation 库和 Windows 消息的复杂性.


## Debugging / error handling ##

* [Delphi LeakCheck](https://bitbucket.org/shadow_cs/delphi-leakcheck) .  `[Delphi]` 免费代码库，用于检查 DUnit 和 DUnit2 测试中的内存泄漏. 支持德尔福 XE-XE7.

* [FastMM](#memory-managers) . 提供强大的内存泄漏/损坏检测工具.

* [JclDebug (part of Project JEDI)](https://github.com/project-jedi/jcl/blob/master/jcl/source/windows/JclDebug.pas) .  `[Delphi]` `[FPC]` 跟踪、MAP 文件解析器、异常报告生成、异常堆栈跟踪.

* [DebugEngine](https://github.com/MahdiSafsafi/DebugEngine) .  `[Delphi]` 与调试相关的实用程序集合（堆栈跟踪、CPU 寄存器快照、调试信息等）. 访问 Delphi 调试信息、从符号名称中获取符号地址、Delphi 映射解析和映射转换为二进制格式、智能堆栈跟踪、Delphi 异常堆栈跟踪挂钩等.

* [ObjectDebugger](https://github.com/marcocantu/ObjectDebugger) .  `[Delphi]` Delphi VCL 应用程序的运行时对象检查器.


## Utilities ##

*此处允许免费的非开源产品.*


## RAD Studio IDE plugins/wizards

* [Delphi IDE theme editor / Delphi IDE Colorizer](https://github.com/rruz/delphi-ide-theme-editor) . 用于更改几个 Object Pascal IDE 的 IDE 颜色突出显示的工具，例如 Delphi (RAD Studio)、Appmethod、Lazarus 和 Smart Mobile Studio.  DITE 支持 Delphi 5-7、2005-2010、XE-XE8、Appmethod 1.13-1.14、Lazarus v1.0.1.3 和 Smart Mobile Studio IDE v1.1.2.17.  Delphi IDE Colorizer (DIC) 是一个插件，它允许自定义 RAD Studio IDE 和 Appmethod 的工作区的外观和感觉.

* [DDevExtensions](https://github.com/ahausladen/DDevExtensions) . 通过添加一些新的生产力特性来扩展 Delphi/C++Builder IDE.
// *许多有用的 IDE 调整，必须有.*

* [VCL Fix Pack](https://www.idefixpack.de/blog/bugfix-units/vclfixpack-10/) .  Delphi 单元通过修补原始函数在运行时修复 VCL 和 RTL 错误. 如果您想要在您的应用程序中进行所有 IDE Fix Pack 修复，那么这个单元就是您要找的. 将单元添加到您的项目（Delphi 和 C++Builder）会自动安装适用于您的 Delphi/C++Builder 版本的补丁.
// *实际适用于 Delphi/C++ 6..2009*

* [IDE Fix Pack](https://www.idefixpack.de/blog/ide-tools/ide-fix-pack/) .  RAD Studio IDE、Win32/Win64 编译器和 Win32 调试器的非官方错误修复和性能优化集合.  IDE Fix Pack 是 RAD Studio 2009-XE6 的 IDE 插件，可在运行时修复 IDE 错误. 所有更改都在内存中完成. 磁盘上没有文件被修改. 除了更快地编译之外，您的任何项目都不会被修改或受益于 IDE Fix Pack. 只有 IDE 才能获得修复和优化.
 // *支持自 2007 年以来的所有 RAD Studio 版本.删除了许多 EMBT 多年未修复的烦人错误. 耶！*

* [GExperts](https://sourceforge.net/projects/gexperts) . 一套免费的工具，旨在通过向 IDE 添加多项功能来提高 Delphi 和 C++Builder 程序员的工作效率.  GExperts 是作为开源软件开发的，我们鼓励用户对该项目做出贡献.  grep 搜索和替换支持的 unicode 文件、DFM 等； 自动重命名组件、插入文本宏、打开最近的文件； 使用自定义附加文件列表轻松备份您的项目； 保留收藏文件的嵌套列表以便快速访问； 跟踪项目中单元之间的依赖关系； 快速跳转到当前单元中的任何程序； 还有很多很多.

* [CnWizards](https://github.com/cnpack) .  Delphi/C++ Builder/CodeGear RAD Studio的免费插件工具集，提高开发效率.

* [Delphi Package Installer (DelphiPI)](https://bitbucket.org/idursun/delphipi) . 帮助您将组件安装到 Delphi IDE 的工具.  DelphiPI 自动解析包之间的依赖关系，编译、安装并将源路径添加到您的 IDE.

* [ResEd](https://github.com/chaosben/theunknownones) .  Delphi 2005、2006、2007、2009、2010 和 XE 专家. 该专家设计用于编辑链接到活动项目的资源文件 (.res; .resx). 它将自动搜索所有出现的 {$R xyz.res} 行，并为它们打开/创建资源文件. 专家在 Delphi 的菜单栏中的 View 下注册自己.

* [Parnassus Bookmarks](https://parnassus.co/delphi-tools/bookmarks). IDE plugin that extends bookmark functionality.

* [DelphiSettingManager](https://github.com/Arvur/DelphiSettingManager) .  Delphi 的多个 IDE 配置文件（最高 XE6）. 允许为不同的项目安装相同组件的多个版本或不同的组件集.

* [Delphinus](https://github.com/Memnarch/Delphinus) . 新的 Packagemanager 在 Delphi XE 和更新版本上运行，并使用 GitHub 作为后端来提供包.

* [TestInsight](https://bitbucket.org/sglienke/testinsight/wiki/Home) .  Delphi 的单元测试 IDE 插件. 它支持从 XE 到 10 Seattle 的所有版本. 支持 DUnit、DUnit2、DUnitX 框架.

* [Delphi IDE Explorer](https://github.com/DGH2112/Delphi-IDE-Explorer) . 允许您浏览 IDE 的内部字段、方法、属性和事件的向导/专家/插件.
// *主要对IDE专家的开发者有用*

* [Multi-RAD Studio IDE Expert Manager](http://www.davidghoyle.co.uk/WordPress/?page_id=1361) . 应用程序用于编辑机器上所有版本的 RAD Studio（以及较旧的 Delphi 和 C++ Builder）中已安装的专家.

* [OTA Interface Search](https://github.com/DGH2112/OTA-Interface-Search) . 应用程序有助于找到开放工具 API (OTA) 接口、方法和属性，并了解如何访问这些接口或接口的方法/属性.

* [AutoSave](https://github.com/DGH2112/Auto-Save) . 定期自动保存所有打开的修改过的 IDE 文件的专家.

* [Browse and Doc It](http://www.davidghoyle.co.uk/WordPress/?page_id=872) . 插件允许您在 IDE 中记录和浏览代码.

* [Integrated Testing Helper](http://www.davidghoyle.co.uk/WordPress/?page_id=874) .  Delphi 和 RAD Studio 的插件，允许您在项目编译之前和之后运行命令行应用程序. 它还提供了在每次编译/构建时将项目文件压缩到存档并管理应用程序版本信息的能力.

* [Project Magician](https://www.uweraabe.de/Blog/2018/05/17/keep-your-project-files-clean-with-project-magician) . 高级项目选项操作向导.

* [Selective Debugging](http://www.uweraabe.de/Blog/2015/05/08/selective-debugging/) . 允许调整将使用其调试版本的单元的向导.

* [MMX Code Explorer](https://www.mmx-delphi.de) . 功能丰富的生产力增强插件. 包括重构、类浏览器、高级编辑、metrict 等等.

* [FormResource](http://chapmanworld.com/2017/03/22/formresource-a-free-delphi-component-for-organizing-product-dependencies) . 帮助将各种数据存储为表单资源的向导.

* [Delphi Library Helper](https://github.com/littleearth/delphi-library-helper) 帮助 Delphi 开发人员配置库文件夹的工具.

* [Mobile Image Creator](https://github.com/littleearth/mobile-image-creator) 为 Delphi 移动应用程序 (Firemonkey) 创建图标和启动器图像. 这是 Mobile Gfx 创建的一个分支 [Thomas Grubb of RiverSoftAVG](http://riversoftavg.com/blogs/index.php/2014/02/03/creating-icons-and-launchers-for-delphi-mobile-applications/).

* [Delphi-Adb-WiFi](https://github.com/ms301/Delphi-Adb-WiFi) .  RAD Studio 插件，允许在 Android 设备上启动和调试，而无需通过 USB 连接到计算机. 通过 WiFi 工作.

* [RADSplit](https://github.com/LaKraven/RADSplit) . 用于 RAD Studio（Delphi 和 C++ Builder）的可停靠分屏编辑器.

* [DzNoteEditor](https://github.com/digao-dalpiaz/DzNoteEditor) .  Delphi Property Editor for TStrings 支持带语法高亮显示的格式化语言.


## Plugins for other IDE's

* [Delphi IDE theme editor / Delphi IDE Colorizer](#rad-studio-ide-pluginswizards) . 支持 Appmethod、Lazarus 和 Smart Mobile Studio.

* [Pascal](https://github.com/alefragnani/vscode-language-pascal) 和 [Pascal Formatter](https://github.com/alefragnani/vscode-pascal-formatter) . 为添加 Pascal 支持的 Visual Studio Code 创建的开源扩展.


## Documentation

* [SynProject](https://github.com/synopse/SynProject) ([docs](http://synopse.info/fossil/wiki?name=SynProject) ）.  Delphi 项目的代码源版本控制和自动化文档工具.

* [PasDoc](https://sourceforge.net/projects/pasdoc) .  `[Delphi]` `[FPC]` ObjectPascal（FreePascal 和 Delphi）源代码的文档工具. 文档是从源代码中的注释生成的. 可用的输出格式有 HTML、HtmlHelp、LaTeX、latex2rtf、simplexml. 将来可能会添加更多输出格式.


## Code check/review, debug

* [GpProfiler2017](https://github.com/ase379/gpprofile2017) .  `[Delphi]` Delphi XE 及更高版本的源代码检测分析器. 其他分叉支持旧版本.

* [SamplingProfiler](https://www.delphitools.info/samplingprofiler) .  `[Delphi]` Delphi 5 到 32 位 Delphi XE4 的性能分析工具. 其目的是帮助定位瓶颈，即使是在全速运行的最终优化代码中也是如此.

* [Delphi Code Coverage](https://github.com/DelphiCodeCoverage/DelphiCodeCoverage) .  `[Delphi]` Delphi 的简单代码覆盖率工具，可根据详细的 MAP 文件创建代码覆盖率报告.

* [Pascal Analyzer](http://www.peganza.com/products_pal.html)  （提供免费的精简版）.  `[Delphi]` Pascal Analyzer，简称 PAL，解析 Delphi 或 Borland Pascal 源代码. 它构建标识符的大型内部表，并收集其他信息，例如子程序之间的调用. 解析完成后，会生成大量报告. 这些报告包含大量有关源代码的重要信息. 这些信息将帮助您更好地理解您的源代码，并帮助您生成更高质量和可靠性的代码.

* [madExcept](http://madshi.net/madExceptShop.htm) .  `[Delphi]` madExcept 旨在帮助您定位软件中的错误. 每当您的程序出现崩溃/异常时，madExcept 会自动捕捉、分析它，收集大量有用信息，并让最终用户可以向您发送完整的错误报告.  madExcept 还能够为您查找内存泄漏、资源泄漏和缓冲区溢出.
// *免费**无源**用于非商业用途（仅）与一些 [conditions](http://help.madshi.net/License.htm) . 可作为 `madCollection` 安装程序的一部分下载（您需要安装 `madExcept` 项）. 记录良好. *

* [delphiunitsizes](https://github.com/VilleKrumlinde/delphiunitsizes) .  `[Delphi]` 用于在 Delphi 可执行文件中显示每个单元大小的工具. 显示 Delphi exe 文件中包含的每个单元的大小. 它还显示了一个单元中每个符号（类、方法、过程等）的大致大小.

* [MapFileStats](https://www.delphitools.info/other-tools/mapfilestats) .  `[Delphi]` 从 .MAP 文件（任何 Delphi 版本至少到 Delphi XE5）提供简单二进制大小统计的工具.

* [Spider](https://github.com/yavfast/dbg-spider) .  `[Delphi]` Delphi 应用程序的实时分析器

* [AsmProfiler](https://github.com/andremussche/asmprofiler) .  `[Delphi]` 完全跟踪 32 位分析器（仪器和采样），用 Delphi 和一些程序集编写

* [map2pdb](https://bitbucket.org/anders_melander/map2pdb) .  `[Delphi]` 工具用于将 Delphi 和 C++ Builder 编译器生成的 MAP 文件转换为 Microsoft PDB 文件，以便在支持该格式的工具中使用.


## Setup

* [Lazy Delphi Builder](https://bitbucket.org/tdelphi/lazy-delphi-builder-downloads) .  Delphi 的构建工具. 从具有所有依赖项的源重新编译项目/包，而无需弄乱配置. 快速（重新）将组件从源代码安装到 IDE 中，无需更改库路径.
 // *强大的自动化工具. 免费软件但非开源*

* [Inno Setup](http://www.jrsoftware.org/isinfo.php) .  Windows 程序的免费安装程序.  Inno Setup 于 1997 年首次推出，如今在功能集和稳定性方面可与甚至超过许多商业安装程序相媲美.

* [WinSparkle](https://winsparkle.org) 及其 [Delphi wrapper](https://github.com/jkour/neSparkleComponent) .  WinSparkle 是一个易于使用的软件更新库，适用于 Windows 开发人员.  WinSparkle 是一个深受 Andy Matuschak 最初由 Sparkle 框架启发的（几乎是它的移植版），该框架成为 macOS 上软件更新的事实上的标准.

* [Silverpoint MultiInstaller](http://www.silverpointdevelopment.com/multiinstaller/index.htm) .  Embarcadero Delphi 和 C++Builder 的多组件包安装程序，它的创建是为了简化 IDE 上的组件安装.

* [Grijjy Deployment Manager](https://github.com/grijjy/GrijjyDeployMan) . 用于简化用 Delphi 编写的 iOS 和 Android 应用程序的文件和文件夹部署的工具. 如果您需要部署大量文件，例如 3rd 方 SDK，它特别有用.


## Other


* [Delphi Preview Handler](https://github.com/RRUZ/delphi-preview-handler) . 适用于 Windows Vista、7 和 8 的预览处理程序，允许您读取对象 pascal、C++ 和汇编代码，无需在编辑器中打开语法突出显示

* [Delphi Dev. Shell Tools](https://github.com/RRUZ/delphi-dev-shell-tools) .  Windows shell 扩展，为 Object Pascal 开发人员提供有用的任务（Delphi，Free Pascal）.

* [Delphi.gitignore](https://github.com/github/gitignore) .  Delphi 的 .gitignore 模板. 拉撒路也有一个.

* [OmniPascal](http://omnipascal.com) . 使 Delphi 和 Free Pascal 开发人员能够使用现代编辑器编写和维护代码的项目 [Visual Studio Code](https://code.visualstudio.com).

* [Delphi Unit Tests](https://bitbucket.org/NickHodges/delphi-unit-tests) .  Delphi 库的一组单元测试. 鼓励 Delphi 社区成员分叉存储库、添加测试并创建拉取请求. 特别鼓励 Embarcadero 员工从使用官方 Delphi 构建运行的内部测试中添加测试.

// *免费**无源**用于非商业用途（仅）与一些 [conditions](http://help.madshi.net/License.htm) . 可作为 `madCollection` 安装程序的一部分下载（您需要安装 `madExcept` 项）. 记录良好. *

* [Chet - C Header Translator for Delphi](https://github.com/neslib/Chet) .  Chet 是一个 .h 到 .pas 的翻译器，由用于 Delphi 的 libclang 提供支持. 使用 Clang 编译器解析头文件，从而产生更准确的翻译，需要更少的手动调整.

* [Boss](https://github.com/HashLoad/boss). Dependency Manager for Delphi projects.

* [C-To-Delphi](https://github.com/WouterVanNifterick/C-To-Delphi) .  `[Delphi]` 这个工具将转换你的大部分标准 C 代码.

* [Better Translation Manager](https://bitbucket.org/anders_melander/better-translation-manager) .  `[Delphi]` 翻译管理器

* [dzBdsLauncher](https://osdn.net/projects/dzbdslauncher/) .  `[Delphi]` Delphi IDE 的启动器，它根据传递给它的 dproj 文件的后缀来决定启动多个 IDE 中的哪一个.

* [DFMJSON](https://github.com/masonwheeler/DFMJSON) .  `[Delphi]` 库，用于在 Delphi 的 .DFM（或 .FMX）格式和 JSON 之间进行转换. 它可用于将 DFM 文件解析为 JSON 格式的抽象语法树，然后可以对其进行编辑并将结果转回 DFM 格式.
