<div class="github-widget" data-repo="Fr0sT-Brutal/awesome-pascal"></div>
## Awesome Pascal [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 精选的Delphi，FreePascal和其他* Pascal框架，库，资源和闪亮的东西的精选列表.  受到令人敬畏的......的启发.

 **请注意，只考虑开源项目.  死亡项目（未更新3年或更长时间）必须非常棒或独一无二.**
随意通过评论或拉取请求建议其他缺少的好项目.

这个很棒的收藏品也可用 [Delphi.ZEEF.com](https://delphi.zeef.com/anton.frost)

:exclamation: **Note on compiler compatibility**. There are compiler/language dialect compatibility badges for all projects based on a project's description. No real compatibility with compilers not officially supported is checked. Often a code could be used with non-supported compiler/language dialect with minor modifications but there could be exceptions.


- [Awesome Delphi](#awesome-delphi)
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
	- [Non-visual Classes/Utils](#non-visual-classesutils)
		- [Compression](#compression)
		- [Encryption](#encryption)
		- [XML/JSON/YAML](#xmljsonyaml)
		- [Language](#language)
		- [Memory managers](#memory-managers)
		- [System](#system)
		- [Template](#template)
		- [Logging](#logging)
		- [Math](#math)
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

----------------------------------------------------------------------------------------------------------------

## General Libraries ##
*大型通用图书馆*

* [JCL](https://github.com/project-jedi/jcl) .  `[Delphi]``[FPC]`一套经过全面测试和完全记录的实用程序函数和非可视类，可以在Delphi和C ++ Builder项目中立即重用.  该库分为几个类别，如字符串，文件和I / O，安全性，数学等等.

* [JVCL](https://github.com/project-jedi/jvcl) .  `[Delphi]`由“JEDI项目”成员开发的600多个Delphi组件库.
// * GUI，算法，类，API头等.*

* [Alcinoe](http://sourceforge.net/projects/alcinoe) ([mirror at GH](https://github.com/Zeus64/alcinoe) ）.  `[Delphi]`Delphi的可视和非可视组件库.
 // *网络：FTP / Http / NNTP / POP3 / SMTP，ISAPI，WinInet Http / FTP客户端;  DB：Firebird / MySQL / SQLite3 / Memcached / MongoDb / SphinxQL;  XML / JSON解析器;  ZLIB;  密码学：AES，Blowfish，MD5，SHA，安全密钥MD5 / SHA;  opengl视频播放器;  FireMonkey控件;  其他：自平衡二叉树，表达式评估器*

* [Fundamentals Code Library](http://sourceforge.net/projects/fundementals) （被遗弃，更近期的分叉是 [here](https://github.com/fundamentalslib/fundamentals4)   - 虽然它在单位集中略有不同，但是f.ex.  没有XML.  最近的主要版本5 [here](https://github.com/fundamentalslib/fundamentals5) ）.  `[Delphi]``[FPC]`Delphi / FreePascal代码单元的集合.  包括用于Unicode，字符串，数据结构，套接字和数学的库.
 // * Utils：ZLIB压缩;  JSON;  XML;  ProtocolBuffers;  Unicode例程;  数据结构;  哈希：XOR，CRC，Adler，MD5，SHA，安全密钥MD5 / SHA等;  网络：通过SSL3 / TLS1.0 / TLS1.1 / TLS1.2（完全原生）阻止TCP客户端/服务器，HTTP（S）;  SQL解析器;  BitCoin MtGox客户端;  Blaise脚本引擎;  密码：AES，DES，FUNE，RC2，RC4，RSA，Diffie-Hellman;  数学：矩阵，复杂，统计，数字庞大*

* [Spring4D](https://bitbucket.org/sglienke/spring4d) .  `[Delphi]`Embarcadero Delphi 2010及更高版本的开源代码库.  它由许多不同的模块组成，这些模块包含基类库（通用类型，基于接口的集合类型，反射扩展）和依赖注入框架.  包括加密库.
// *Collections and other containers using Generics and based on IEnumerable, probably more accurate and featured than RTL analogs; crypto: CRC, DES, MD5, SHA; file utils etc*

* [TheUnknownOnes](https://github.com/chaosben/theunknownones) .  `[Delphi]`用于几乎所有目的的巨大的类，组件，实用程序堆.  几乎没有文件记录，但似乎不是最新的.

* [CNVCL](https://github.com/cnpack/cnvcl) .  `[Delphi]`CnPack组件包.  大量可视组件，类和实用程序.  // *很多有用的东西;  文件和评论主要以中文*

* [mORMot](https://github.com/synopse/mORMot) .  `[Delphi]``[FPC]`用于Delphi 6及更高版本的客户端 - 服务器ORM / ODM SOA MVC框架，或FPC 2.7.  直接SQL / NoSQL数据库访问，ORM / ODM over对象，RESTful ORM和SOA服务，通过高性能HTTP服务器，MVC / MVVM网站上的接口，测试包括模拟和存根，日志记录，加密，压缩，大量文档.

* [MARS - Curiosity](https://github.com/andrea-magni/MARS) .  `[Delphi]`Delphi REST Library.  纯REST方法，熟悉的Delphi风格的标准概念（包括基于组件的客户端库）.  已知兼容性：从XE到10 Seattle的Delphi版本.  某些功能需要FireDAC.

* [ADAPT](https://github.com/LaKraven/ADAPT) .  `[Delphi]`高级开发人员异步编程工具包，基础库旨在用于项目的核心，以提供极其强大的多线程（和线程安全）功能.  事件引擎 - 一个非常强大的系统，用于生成多线程，异步和事件驱动的程序.  泛型集合 - 高效的集合类型（列表，树，地图等）.  数学库 - 用于单位转换，特殊计算和其他有用的数学例程的库.  Package Engine  -  Streamables Engine的扩展，支持将文件打包在一起（各种VFS）.  共享流库 -  100％线程安全流类（也是接口）允许从多个线程读/写.  流处理库 - 使得使用Streams变得更加容易！  处理删除，插入，读取和写入数据.

* [Redux Delphi](https://github.com/pierrejean-coudert/ReduxDelphi) .  `[Delphi]`使用单向数据流的Delphi应用程序的可预测状态容器.  灵感来自ReduxJS.  附带不可变通用列表.

* [GrijjyFoundation](https://github.com/grijjy/GrijjyFoundation) .  `[Delphi]`在其他Grijjy存储库中使用的基础类和实用程序.
// * BSON / JSON，IOCP / EPOLL套接字，套接字池，HTTP，HTTP / 2，OpenSSL，ProtocolBuffers.*

* [unRxLib](http://www.micrel.cz/RxLib/dfiles.htm) .  `[Delphi]`努力使RxLibrary（60多个组件的库）保持实际.

* [QuickLib](https://github.com/exilon/QuickLib) .  `[Delphi]``[FPC]`Delphi / freepascal（Windows / Linux）库，用于快速开发和跨平台支持（Json Serialize，AutoMapper，Chronometer，Threads，Lists，Config，Console服务等）.

* [KOL](https://sourceforge.net/projects/kolmck) .  `[Delphi]``[FPC]`（[KOL-CE](https://sourceforge.net/p/kol-ce) port to FPC) KEY OBJECTS LIBRARY for Delphi (and FPC) - to make applications small and power. This library is freeware and open source. MCK is a kit of mirror classes for the VISUAL project development in Delphi environment using KOL library.


## Multimedia ##


## Audio

* [Audio Tools Library](http://mac.sourceforge.net/atl) .  `[Delphi]`用于处理许多音频格式的文件信息.
// **自2005年以来被遗弃.**

* [Delphi ASIO & VST Project](http://sourceforge.net/projects/delphiasiovst) .  `[Delphi]`使用ASIO接口和VST插件编写应用程序的框架.  它附带了无数的DSP算法，这些算法都在几十个例子中得到了证明.
//*Not very active lately, but the trunk is in a usable state*

* [NewAC - New Audio Components](http://code.google.com/p/newac) （废弃，GH的分叉清单 [here](https://github.com/search?l=Pascal&o=desc&q=newac&s=updated&type=Repositories) ）.  `[Delphi]`旨在帮助您的Delphi程序执行不同的声音处理任务.  使用NewAC，您可以播放以多种格式存储的音频（wav，Ogg Vorbis，FLAC，Monkey Audio，WavPack，MP3，Windows WMA，DTS，AC-3（Dolby Surround），VOB（DVD文件））.
// *播放，录制，标签读/写，一些音频编辑任务和转换*

* [Audorra](https://sourceforge.net/projects/audorra) .  `[Delphi]``[FPC]`用于Delphi和Freepascal的数字音频库.  使用灵活的插件架构，它允许您交换音频后端（例如WaveOut，OpenAL），添加协议类（例如文件，http）和解码器.


## Video

* [DSPack](https://code.google.com/p/dspack) （被遗弃的，活跃的叉子是 [here](https://github.com/micha137/dspack-continued-mirror-for-delphinus) ）.  `[Delphi]`使用MS Direct Show和DirectX技术编写多媒体应用程序的一组组件和类.

* [Delphi-OpenCV](https://github.com/Laex/Delphi-OpenCV) .  `[Delphi]`在Delphi中翻译OpenCV库头文件
// *包括FFMPEG标头*

* [FFmpeg Delphi/Pascal Headers](http://www.delphiffmpeg.com/headers) .  `[Delphi]``[FPC]`FFMPEG头的开源翻译.

* [PasLibVlc](http://prog.olsztyn.pl/paslibvlc) .  `[Delphi]``[FPC]`基于VideoLAN的VideoLAN libvlc.dll接口和Delphi / FreePascal的VCL播放器组件

* [fevh264](https://github.com/dpethes/fevh264). `[FPC]` Baseline h.264 encoder. Windows and Linux are supported


## Graphic

* [Graphics32](https://github.com/graphics32/graphics32) .  `[Delphi]``[FPC]`专为Delphi，Kylix和Lazarus的快速32位图形处理而设计.  它针对32位像素格式进行了优化，可提供像素和图形基元的快速操作，在大多数情况下，Graphics32优于标准的TCanvas类.  每像素访问速度快几百倍，绘制线速度快约2-5倍.

* [GraphicEx](https://github.com/mike-lischke/GraphicEx) .  `[Delphi]`Delphi的Graphics.pas附录，使您的应用程序能够加载许多常见的图像格式.  该库主要用于将图像作为背景（按钮，表格，工具栏）和纹理（DirectX，OpenGL）加载，或者用于图像浏览和编辑目的，只要您不需要保存图像即可.

* [Vampyre Imaging Library](http://imaginglib.sourceforge.net) .  `[Delphi]``[FPC]`跨平台原生Object Pascal（Delphi和Free Pascal）图像加载，保存和操作库.

* [CCR-EXIF](https://code.google.com/p/ccr-exif) （似乎放弃了GH的分叉列表 [here](https://github.com/search?l=Pascal&o=desc&q=ccr-exif&s=updated&type=Repositories) ）.  `[Delphi]`用于从JPEG，TIFF和PSD图像读取和写入Exif，IPTC和XMP元数据的库.

* [KIcon](http://www.tkweb.eu/en/delphicomp/kicon.html) .  `[Delphi]```[FPC]`如果需要使用图标（或更好的图标文件* .ico）进行更复杂的操作，这个组件是有意义的.  完整的PNG图标图像支持，正确的渲染，带alpha通道的图标.

* [Delphi Twain](http://www.kluug.net/delphitwain.php) .  `[Delphi]``[FPC]`该库允许您轻松访问Delphi和Lazarus的扫描功能.

* [Synopse PDF](https://github.com/synopse/SynPDF) .  `[Delphi]``[FPC]`用于Delphi的全功能开源PDF文档创建库，嵌入在一个单元中.  纯Delphi代码，Delphi 5最高可达Delphi 10.3 Rio（以及最新版本的FPC），适用于Win32和Win64平台.

* [PowerPDF](https://github.com/TurboPack/PowerPDF) .  `[Delphi]`VCL组件可视化创建PDF文档.  与Forms一样，您可以在Delphi或C ++ Builder IDE上轻松设计PDF文档.

* [IGDI+](https://sourceforge.net/projects/igdiplus) .  `[Delphi]`免费的开源库允许使用自然的Delphi友好代码快速轻松地实现复杂的GDI +应用程序.

* [GLScene](https://sourceforge.net/projects/glscene) .  `[Delphi]``[FPC]`基于OpenGL的3D库，适用于Delphi，C ++ Builder和Lazarus.  它提供了可视化组件和对象，允许以简单，轻松，强大的方式描述和渲染3D场景.  GLScene不仅仅是一个OpenGL包装器或实用程序库，它已经发展成为一个基于快速应用程序开发的通用3D引擎的创建类.  GLScene允许您快速设计和渲染3D场景，而无需了解OpenGL的复杂性，如果您知道如何设计TForm，您将轻松掌握GLScene的基本操作.  该库附带了大量演示，展示了易用性，并且演示RAD并未以牺牲CPU / GPU马力为代价.


* [Andorra 2D](http://sourceforge.net/projects/andorra) .  `[Delphi]``[FPC]`适用于Delphi和Lazarus的新一代2D引擎.  安道尔2D能够通过图形插件使用DirectX或OpenGL.  安道尔2D采用非常模块化的方式构建，易于使用.

* [Transparent-canvas](https://github.com/vintagedave/transparent-canvas) .  `[Delphi]`用于绘制半透明alphablended图形的Delphi VCL / Windows项目.  它提供了类似于TCanvas的类.

* [Fully-justified-text](https://github.com/vintagedave/fully-justified-text) .  `[Delphi]`用于文本输出的Delphi VCL / Windows项目，允许使用各种选项打印完全对齐的文本.

* [AsciiImage](https://github.com/Memnarch/AsciiImage) .  `[Delphi]`AsciiImage-由Alexander Benikowski执行Delphi，基于Charles Parnot的AsciiImage.  了解更多 [his article](http://cocoamine.net/blog/2015/03/20/replacing-photoshop-with-nsstring).
// *从ASCII像素图创建可缩放的单色图像*

* [PngComponents](https://bitbucket.org/uweraabe/pngcomponents) .  `[Delphi]`PngComponents是一组组件，允许您在应用程序中包含真正的PNG文件.  PNG文件本身并不会带来极大的优势，但它们对alpha通道的支持确实具有相当大的魅力.

* [AggPasMod](https://github.com/CWBudde/AggPasMod) .  `[Delphi]`现代化Pascal抗粒几何.  基于AggPas，它本身基于Anti-Grain Geometry，该项目提供对最新Delphi版本（XE及更高版本）的支持，并包含一些辅助类（VCL组件和FireMonkey接口）.  2D矢量图形库.  基本上，您可以将AggPas视为渲染引擎，该引擎从某些矢量数据在内存中生成像素图像.  但当然，AGG可以做的远不止这些.
// *矢量图形库，渲染SVG等等*

* [delphi-shader](https://github.com/WouterVanNifterick/delphi-shader) .  `[Delphi]`数百种图形效果，以及以纯Delphi代码提供GLSL功能的库.  该项目生成一个具有一百多个实时图形效果的可执行文件.  所有这些都是100％pascal实现，无需使用外部库或硬件加速.

* [dglOpenGL](https://github.com/SaschaWillems/dglOpenGL) .  `[Delphi]``[FPC]`Delphi / Pascal OpenGL头文件翻译.

* [DelphiZXingQRCodeEx](https://github.com/MichaelDemidov/DelphiZXingQRCodeEx) .  `[Delphi]``[FPC]`QR码的Delphi / Lazarus端口，ZXing生成功能，ZXing是一个开源条码图像处理库.

* [ZXing.Delphi](https://github.com/Spelt/ZXing.Delphi) .  `[Delphi]`用于Delphi XE到10.2东京的本机对象Pascal库，它基于众所周知的开源条码扫描库ZXing（Zebra Crossing）.  它针对所有FireMonkey移动平台，从v3.1开始，它完全支持Windows VCL应用程序（不依赖于FMX.Graphics单元）.

* [QuickImageFX](https://github.com/exilon/QuickImageFX) .  `[Delphi]`Delphi库，用于简化图像加载/保存，转换和转换.  加载/保存png，jpg，gif和bmp.  从不同的资源获取图像：文件，流，http，图像列表，关联的窗口图标，可执行文件图标等...旋转，翻转，灰度和许多其他转换.

* [NativeJpg](https://code.google.com/p/simdesign) .  `[Delphi]`完全面向对象的Pascal实现，允许读写Jpeg文件.  您可以使用此软件从文件或流中读取和写入Jpeg图像.  它支持基线和渐进式Jpeg，对元数据的支持，以及所有可能的无损操作.


## Game dev ##

* [RecastNavigation](https://github.com/Kromster80/RecastNavigationDelphi) .  `[Delphi]`用于游戏的导航网格构建工具集.  重铸伴随着Detour，路径寻找和空间推理工具包.  您可以使用Detour的任何导航网格，但当然使用Recast生成的数据非常适合.  这是用C ++编写的原始RecastNavigation的端口.

* [Kraft Physics Engine](https://github.com/BeRo1985/kraft). `[Delphi]` `[FPC]` Open source Object Pascal physics engine library that can be used in 3D games. Compatible with: Delphi 7-XE7 (but not with the Android and iOS targets), FreePascal >= 2.6.2 (with almost all FPC-supported targets including Android and iOS)

* [ZenGL](https://github.com/andru-kun/zengl). `[Delphi]` `[FPC]` OpenGL Cross-platform game development library written in Pascal, designed to provide necessary functionality for rendering 2D-graphics, handling input, sound output, etc.
// *最近没有更新，但工作正常*

* [Asphyre aka Platform eXtended Library (PXL)](https://sourceforge.net/projects/asphyre) .  `[Delphi]``[FPC]`用于开发2D / 3D视频游戏，交互式和科学应用的跨平台框架.  它帮助开发人员进行数学，硬件控制，资源管理，显示实时图形和文本，处理用户输入和网络通信功能.

* [CrystalPathFinding](https://github.com/d-mozulyov/CrystalPathFinding) .  `[Delphi]``[FPC]`一个开源的简单有效的库，用于通过算法A * / WA *搜索最短路径，用于基于4（简单），8（对角线/ diagonalex）的图块的地图或6（六角形）邻居.

* [Allegro-Pas](https://sourceforge.net/projects/allegro-pas) ([GitHub](https://github.com/niuniomartinez/allegro-pas) ）.  `[Delphi]``[FPC]`Wrapper使用Pasle / Delphi的Allegro游戏库.

* [Castle Engine](https://github.com/castle-engine/castle-engine) .  `[FPC]`完整的Pascal游戏引擎.  具有大量图形效果的跨平台3D和2D游戏引擎以及基于X3D的场景图.

* [TileEngine](http://www.tilengine.org). ([GitHub](https://github.com/turric4n/PascalTileEngine) ）`[Delphi]``[FPC]`OOP Pascal Wrapper和Tilengine 2D复古图形引擎的绑定.  Tilengine是一个跨平台的2D图形引擎，用于创建带有tilemaps，sprite和palettes的经典/复古游戏.  其基于扫描线的渲染算法使光栅效果成为核心功能，这是许多在真实2D图形芯片上运行的游戏所使用的技术.

* [SDL2](http://www.freepascal-meets-sdl.net/) ([GitHub](https://github.com/ev1313/Pascal-SDL-2-Headers) ）.  `[Delphi]``[FPC]`Pascal SDL 2 Headers.  简单的DirectMedia Layer是一个跨平台开发库，旨在通过OpenGL和Direct3D提供对音频，键盘，鼠标，操纵杆和图形硬件的低级访问.

* [SFML](https://github.com/CWBudde/PasSFML) .  `[Delphi]``[FPC]`Pascal SFML Headers.  SFML为PC的各个组件提供简单的界面，以简化游戏和多媒体应用程序的开发.  它由五个模块组成：系统，窗口，图形，音频和网络.  目前支持Delphi和FPC / Lazarus.  但是，由于编译器与Delphi编译器不兼容（通过解决方法解决），目前建议使用FPC.

* [pasvulkan](https://github.com/BeRo1985/pasvulkan) .  `[Delphi]``[FPC]`Vulkan头生成器，OOP风格的API包装器，框架和用于Object Pascal的基于Vulkan的潜在游戏引擎.

* [DarkGlass](https://github.com/chapmanworld/DarkGlass) .  `[Delphi]`DarkGlass是一个使用Delphi编写的通用游戏引擎.

* [JEDI-SDL](https://sourceforge.net/projects/jedi-sdl) .  `[Delphi]``[FPC]`来自JEDI的SDL的Pascal头.  适用于Delphi，Kylix，Free Pascal，Gnu Pascal和TMT Pascal.


## Communications ##


## Network
*套接字通信，网络协议，编码等*

* [Internet Component Suite](http://www.overbyte.be/frame_index.html) .  `[Delphi]`基于异步的库，由各种Internet组件和应用程序组成.  用于TCP，UDP，原始套接字，FTP，SMTP，POP3，NNTP，HTTP，Telnet等的客户端/服务器.  在OpenSSL的帮助下支持SSL和TLS.  还包括Mime Decoder，SHA1 / MD4 / MD5哈希，DES加密.

* [Indy](https://github.com/IndySockets/Indy) .  `[Delphi]``[FPC]`用于Delphi，C ++ Builder，Delphi.NET和FreePascal的网络组件
 // *基于阻塞套接字和线程的一体化网络库.  自2006年起默认安装RAD工作室.*

* [Ararat Synapse](https://sourceforge.net/p/synalist). `[Delphi]` `[FPC]` Pascal TCP/IP Library for Delphi, C++Builder, Kylix and FreePascal. Deals with network communication by means of blocking (synchronous) sockets or with limited non-blocking mode. This project not using asynchronous sockets! The Project contains simple low level non-visual objects for easiest programming without problems (no required multithread synchronisation, no need for windows message processing,...) Great for command line utilities, visual projects, NT services,...
 // * TCP，UDP，ICMP，RAW;  ICMP，DNS，SMTP，HTTP，SNMP，NTP，FTP，LDAP，NNTP，Telnet;  IPv6的;  SOCKS代理;  SSL / TLS（通过OpenSSL或Windows CryptoApi）;  PING;  字符代码转码;  MIME编码和解码;  CRC16，CRC32，MD5和HMAC-MD5.*

* [Internet Professional](http://sourceforge.net/projects/tpipro2010) .  `[Delphi]`一组VCL组件，为Borland Delphi和C ++ Builder提供Internet连接.  iPRO包括POP3，SMTP，NNTP，FTP，HTTP，Instant Messaging和HTML查看器组件，以及用于低级套接字访问的组件.
 // *似乎已被遗弃但包含相当多的功能，包括ICMP，POP，SMTP，HTTP，NNTP，NTP，FTP，SMTP;  HTML解析器和查看器;  MIME utils;  cookie，证书，缓存，加密等*

* [SynCrtSock](https://github.com/synopse/mORMot/blob/master/SynCrtSock.pas) .  `[Delphi]``[FPC]`有几个套接字和HTTP客户端 - 服务器类，包括Windows下的高性能基于http.sys的服务器，以及一个新的基于线程池的套接字服务器.
// *还在Windows下实现http.sys绑定，在nix下实现cURL绑定*

* [TML Messaging Suite](http://www.libtml.org/docs/libtml-pascal) .  `[Delphi]``[FPC]`网络消息库，用于快速开发可扩展和可扩展的接口.  基于点对点标准协议 [BEEP (Blocks Extensible Exchange Protocol)](http://www.beepcore.org)，定义于 [RFC3080](https://tools.ietf.org/html/rfc3080) 和 [RFC3081](https://tools.ietf.org/html/rfc3081). libTML is suitable for many use cases 和 communication patterns. Equipped with a type safe data API, TML can transport hierarchical data structures fast 和 reliable.
// * libTML对象Pascal组件不仅是一种绑定到核心库的语言，而且是一组完整的非可视组件，用于简化Embarcadero RAD Studio和Lazarus对libTML的使用.*

* [DMVCFramework](https://github.com/danieleteti/delphimvcframework) .  `[Delphi]`Delphi中流行且强大的Web解决方案框架.

* [Delphi IOCP](https://github.com/ymofen/diocp-v5) .  `[Delphi]`基于Windows IOCP技术实现多个网络类.  套接字，HTTP，Ntrip服务器和客户端.
// *相当好的文档和良好的样式代码，但只有中文.*

* [delphi-aws-ses](https://github.com/monde-sistemas/delphi-aws-ses) .  `[Delphi]`适用于Delphi应用程序的Amazon Simple Email Service（AWS SES）库.

* [delphi-slackbot](https://github.com/monde-sistemas/delphi-slackbot) .  `[Delphi]`Delphi库发送消息 [Slack](https://slack.com) 使用slackbot.

* [Kitto](https://github.com/EtheaDev/kitto) .  `[Delphi]`允许基于可以映射到任何数据库的数据模型创建富Internet应用程序.  客户端部分使用ExtJS（通过ExtPascal库）创建一个完全AJAX应用程序，允许您在很短的时间内构建标准和高级数据操作表单.  Kitto针对Delphi开发人员，他们需要创建Web应用程序而无需深入研究HTML，CSS，Javascript的复杂性或学习使用ExtJS等特定库，但如果需要，它允许访问裸机.

* [Daraja Framework](https://github.com/michaelJustin/daraja-framework) .  `[Delphi]``[FPC]`Object Pascal的轻量级HTTP服务器框架（Delphi 2009+ / Free Pascal 3.0）.  通过支持实现RESTful服务 [daraja-restful](https://github.com/michaelJustin/daraja-restful) 延期.

* [Alcinoe](#general-libraries) .  FTP / Http / NNTP / POP3 / SMTP，ISAPI，WinInet Http / FTP客户端.

* [Fundamentals Code Library](#general-libraries) .  通过SSL3 / TLS1.0 / TLS1.1 / TLS1.2（完全本机）阻止TCP客户端/服务器，HTTP（S）.

* [mORMot](#general-libraries) .  通过高性能HTTP服务器，MVC / MVVM网站上的接口实现RESTful ORM和SOA服务

* [SDriver](https://github.com/andrea-magni/SDriver) .  `[Delphi]`Delphi包装器 [Slack](https://slack.com) API.

* [Hprose for Delphi/Lazarus](https://github.com/hprose/hprose-delphi) .  `[Delphi]``[FPC]`高性能远程对象服务引擎.  它是一种现代，轻量级，跨语言，跨平台，面向对象，高性能，远程动态通信的中间件.  它不仅易于使用，而且功能强大.  该项目是Hprose for Delphi / Lazarus的实现.

* [TelegAPI](https://github.com/ms301/TelegAPI) .  `[Delphi]`用于在Delphi中使用Telegram messenger Bot API的库.

* [DelphiZeroMQ](https://github.com/grijjy/DelphiZeroMQ) .  `[Delphi]`Delphi实现了ZeroMQ Majordomo协议和CZMQ高级绑定.

* [GrijjyFoundation](#general-libraries) .  IOCP / EPOLL套接字，套接字池，HTTP，HTTP / 2，OpenSSL，ProtocolBuffers.

* [Rest-Dataware-Componentes](https://github.com/Rest-Dataware/RDW-Componente) .  `[Delphi]``[FPC]`的创建是为了便于在我们为Client / Server Database创建应用程序的模型中创建CRUD.  使用REST DW，您不再需要担心通过Webservice创建SQL插入，删除，读取和执行方法;  只需添加一个RESTDataBase连接组件，并添加一个RESTClientSQL组件，该组件已经使您的SQL解决方案完全正常运行，并且具有现代REST / JSON技术的所有功能，包括数据压缩和语言提供的所有功能.

* [STOMP Client](https://github.com/danieleteti/delphistompclient) .  用于Embarcadero Delphi和FreePascal的`[Delphi]``[FPC]`STOMP客户端.  该项目可以使用INDY（Delphi）或Synapse（Delphi或FreePascal）.

* [delphiXero](https://github.com/littleearth/delphiXERO) .  `[Delphi]`用于Delphi的XERO云计算API.

* [BesaSoap](https://github.com/besasoftware/besasoap). `[Delphi]` The BesaSoap library is designed to help programmers develop faster and more native web service client applications. Represents C# or Java like native class support, nullable data types and custom attributes.

* [IndySoap](https://sourceforge.net/projects/indysoap) .  `[Delphi]`开源库，用于使用Delphi / CBuilder编译器实现Web服务.  IndySoap并不与Indy的运输服务联系在一起，但包括Indy的运输服务.

* [Fano Framework](https://fanoframework.github.io) .  `[FPC]`现代Pascal编程语言的Web应用程序框架.  它是用Free Pascal编写的.

* [Internet Tools](#xmljsonyaml) .  的XPath / XQuery的/ JSONiq / CSS / HTML;  用于在Windows / Linux / MacOSX / Android上执行HTTP / S请求的功能，这是一种受XSLT启发的Webscraping语言和自动更新类.

* [Delphi Cross Socket](https://github.com/winddriver/Delphi-Cross-Socket/) .  `[Delphi]`Delphi跨平台套接字库（中文）.  针对不同平台使用不同的IO模型：IOCP（Windows），KQUEUE（FreeBSD（MacOSX，iOS ...）），EPOLL（Linux（Linux，Android ...））.

* [ToroKernel](https://github.com/torokernel/torokernel) .  `[FPC]`这是一个库内核，允许freepascal应用程序专门移植到系统中独立运行.  Toro在用户的应用程序中编译，因此产生一个单独的二进制文件，可以在裸机上或作为现代管理程序中的客户机启动，例如hyperv，kvm，qemu，firecraker.  ToroKernel通过提供专用API来解决微服务的开发问题.  


## Serial port

* [Synaser](http://sourceforge.net/p/synalist/code/HEAD/tree/trunk/synaser.pas) .  `[Delphi]``[FPC]`用于阻止串口通信的库.  它是Synapse中的非可视类，程序员界面与Synapse非常相似.

* [Async Professional](http://sourceforge.net/projects/tpapro) ([Newest](https://github.com/TurboPack/AsyncPro)  并维护最新编译器版本的版本）.  `[Delphi]`Embarcadero Delphi，C ++ Builder和ActiveX环境的综合通信工具包.  它提供对串行端口，TAPI和Microsoft Speech API（TTS /语音识别）的直接访问.  它支持传真，终端仿真，VOIP，RAS拨号等.
 // *似乎已过时（2011年最后一次更新）但适用于XE，应该易于在较新版本中使用.  该项目也有完整的文件记录.  第二个链接指向适用于最新编译器版本的版本.*

* [TComPort](https://sourceforge.net/projects/comport) .  `[Delphi]`Delphi / C ++ Builder串口通信组件.  它通常易于用于基本的串行通信目的.
// *自2011年以来被遗弃*


## GUI ##
*视觉组件*


## Control packs
*大量GUI控件*

* [Cindy components](http://sourceforge.net/projects/tcycomponents) .  `[Delphi]`具有71个组件的包：VCL控件（标签，按钮，面板，编辑，TabControls，StaticText）具有背景渐变，彩色斜面，壁纸，阴影文本，标题方向等功能......

* [Orpheus](http://sourceforge.net/projects/tporpheus) ([Newest](https://github.com/TurboPack/Orpheus)  并维护最新编译器版本的版本）.  `[Delphi]`获奖的Borland Delphi和C ++ Builder UI工具包.  它包含120多个组件，涵盖从数据输入到日历和时钟的所有内容.  其他值得注意的组件包括Object Inspector，LookOut栏和报告视图.
 // *高级编辑，组合框，网格+组件（反）序列化器.  GUI组件看起来相当旧式，主题支持可能有限.  包中包含许多演示，但似乎没有可用的文档.  第二个链接指向适用于最新编译器版本的版本.*

* [KControls](http://www.tkweb.eu/en/delphicomp/kcontrols.html) .  `[Delphi]``[FPC]`控制组件.  编写所有控件的目的是成为跨IDE兼容（Delphi / C ++ Builder VCL和Lazarus LCL）以及Lazarus中的跨平台兼容.
 // *最有用的是TKGrid及其DB-aware遗产TKDBGrid？  一个非常全功能的网格实现包括.  现场编辑.  还有十六进制编辑器，打印预览，编辑器，标签，按钮等.*

* [D.P.F Delphi Android](http://sourceforge.net/projects/dpfdelphiandroid) / [D.P.F Delphi iOS](http://sourceforge.net/projects/dpfdelphiios)  本机组件.  `[Delphi]`DPF Delphi Native Components，100％iOS性能和样式.  以快速的原生性能和原生风格开发iPhone＆iPad和iPod Touch应用程序.  使用原生Android控件和服务.  快速原生性能.  与FM VCL控件混合使用.  可以使用最新的Android控件和功能快速更新.

* [Essentials](https://github.com/TurboPack/Essentials) .  `[Delphi]`包含13个用于Embarcadero Delphi和C ++ Builder的原生VCL控件.  控件包括下拉日历和计算器，汇总对话框，三维标签，平铺背景，滚动消息，菜单按钮等.

* [FreeEsVCLComponents](https://github.com/errorcalc/FreeEsVCLComponents) .  `[Delphi]`用于Delphi和C ++ Builder的免费VCL组件库.  这种新的控件和组件可以改善外观应用程序并改善用户体验.  组件支持视觉风格，具有现代风格.  所有组件都具有最佳支持透明度，而不是闪烁，并且支持TGraphicControl继承人双重缓冲的有趣可能性.

* [SpTBXLib](https://github.com/SilverpointDev/sptbxlib) .  `[Delphi]`添加Toolbar2000组件包，它增加了以下功能：皮肤，Unicode支持，自定义绘画事件等等.


## Single controls

* [EasyListView](http://code.google.com/p/mustangpeakeasylistview) （似乎放弃了，积极地对待GH [here](https://github.com/TurboPack/MustangpeakEasyListview) ）.  `[Delphi]`ListView的VirtualShellTools的一部分，但可以用于更快，更可定制的TListview替换.
// *功能丰富的Listview实现虚拟（基于回调的）MVC范例.*

* [VirtualTreeView](https://github.com/Virtual-TreeView/Virtual-TreeView) .  `[Delphi]`（[VirtualTreeView-Lazarus](https://github.com/blikblum/VirtualTreeView-Lazarus)  端口到FPC`[FPC]`）.  Treeview控件从头开始构建.  多年的开发使其成为当今最灵活，最先进的树形控件之一.
 // *极其灵活的可视化组件实现虚拟（基于回调的）MVC范例.  也可以用作列表视图或网格.  用于RAD Studio GUI.*

* [Delphi Chromium Embedded](https://github.com/hgourvest/dcef3) .  `[Delphi]`在Delphi中嵌入Chromium，在Delphi 2010，XE，XE2，Delphi 7上测试.
// *需要几个Chromium DLL *

* [TChromeTabs](https://github.com/norgepaul/tchrometabs) .  `[Delphi]`全面实施谷歌Chrome的Delphi 6标签 -  Delphi 10.1柏林

* [TFrameStand](https://github.com/andrea-magni/TFrameStand) .  `[Delphi]`在FireMonkey（FMX）应用程序中轻松使用TFrame，通过整个用户体验获得视觉一致性，并轻松添加现实元素，如效果和过渡.

* [TPrintPreview](https://github.com/landrix/TPrintPreview-for-Delphi) .  `[Delphi]`用于Delphi Vcl Win32 / Win64的打印预览组件

* [VolgaDB](https://sourceforge.net/projects/volgadb) .  `[Delphi]`适用于Delphi的可定制DBgrid.  TCustomGrid后裔.  CheckBox，ComboBox列样式.  还包括TVolgaDBEdit，它在一个组件中替换TDBEdit，TDBComboBox，TDBLookupCombo，TDBLookupTree和TDBDatePicker.  TVolgaDBEdit可能是DB-aware和非DB-aware.
// *自2013年以来被遗弃*

* [TTreeListView](http://github.com/benibela/treelistview) .  `[Delphi]``[FPC]`这个组件是TTreeView和TListView之间的混合，可以绘制一个树，其节点有按列排序的附加信息.

* [neTabControl](https://github.com/jkour/neTabControl) .  `[Delphi]`用于Delphi的FireMonkey控件.  它构建在本机TabControl之上，并添加了许多功能.

* [ATTabs](https://github.com/Alexey-T/ATTabs) .  `[Delphi]``[FPC]`精简版标签的Delphi / Lazarus组件.  OS独立，完全自定义绘制.


## Editors

* [SynEdit](https://sourceforge.net/projects/synedit) ([mirror at GitHub](https://github.com/TurboPack/SynEdit) ）.  `[Delphi]`突出显示编辑控件的语法，不基于Windows常用控件.  SynEdit与Delphi和Kylix兼容

* [BCEditor](https://github.com/bonecode/BCEditor) .  `[Delphi]`语法突出显示编辑控件，包括代码折叠，迷你地图，外部JSON荧光笔和配色方案文件等.
 // *似乎被遗弃了.  开发人员建议使用SynEdit *

* [LazEdit](https://svn.code.sf.net/p/lazarus-ccr/svn/applications/lazedit) .  `[FPC]`带语法高亮的常规文本编辑器和帮助编辑HTML的工具.


## Viewers

* [ATViewer](https://sourceforge.net/projects/atviewer) ([mirror at GitHub](https://github.com/Alexey-T/ATViewer) ）.  `[Delphi]`用于查看各种文件类型的Delphi组件：文本，二进制，图像，多媒体，网页等.
 // *用于Universal Viewer软件.  可用于显示十六进制转储，功能快速显示无限大小的文件/流.  支持Total Commander Lister插件.*

* [ATImageMap](https://sourceforge.net/projects/atviewer/files/ATImageMap) ([mirror at GitHub](https://github.com/Alexey-T/ATViewer) ）.  `[Delphi]`用于将许多图像（整个图像的一部分）显示为单个地图的组件.  例如，您可能有图像数组，200乘X，100乘Y，控件将它们显示为单个地图.  组件还允许绘制路径：每个路径由许多线，点和图标组成.

* [HtmlViewer](https://github.com/BerndGabriel/HtmlViewer) .  `[Delphi]``[FPC]`Delphi / Lazarus HtmlViewer / FrameViewer.
// * Html visualiser支持大多数标签，内联样式和CSS.*

* [SciDe](https://github.com/da-baranov/SciDe) .  `[Delphi]``[FPC]` [Sciter](https://sciter.com) （可嵌入的HTML / CSS /脚本引擎）Delphi的包装器.

* [ATBinHex for Delphi](https://github.com/Alexey-T/ATViewer/blob/master/Source/ATBinHex.pas) `[德尔福]`， [ATBinHex for Laz](https://github.com/Alexey-T/ATBinHex-Lazarus) .  `[FPC]`查看器，用于无限大小的文件，如Total Commander.

* [ATImageBox for Delphi](https://github.com/Alexey-T/ATViewer/blob/master/Source/ATImageBox.pas) `[德尔福]`， [ATImageBox for Laz](https://github.com/Alexey-T/ATImageBox-Lazarus) .  `[FPC]`带嵌入式TImage的TScrollBox.  控制可以自动定位图像.


## Other GUI

* [GMLib](https://code.google.com/p/gmlibrary) （谷歌地图图书馆）（似乎被遗弃，积极分叉GH [here](https://github.com/bero/GMLibrary) 和 [here](https://github.com/cadetill/gmlib_v1) ）.  `[Delphi]`用于Delphi / C ++ Builder的组件，它封装了GoogleMaps API来管理地图，标记，多边形，矩形，折线，...所有可以放入地图的对象.

* [VCL Styles Utils](https://github.com/rruz/vcl-styles-utils) .  `[Delphi]`类和样式钩子的集合，它们扩展，修复QC报告并为VCL样式添加新功能.
 // *补充/增强功能的集合，将库存VCL样式引擎提升到一个新的水平.  Inno Setup和NSIS的样式也可用.*

* [TaskbarListComponents](https://github.com/chaosben/theunknownones/tree/master/Components/TaskBarList) .  `[Delphi]`为Windows 7 Taskbarlist接口设计的Delphi包装器组件（例如ITaskbarlist3）
// *需要JVCL *

* [TFireMonkeyContainer](https://github.com/vintagedave/firemonkey-container) .  `[Delphi]`Delphi VCL组件，用于托管FMX HD或3D表格.  这意味着您可以在VCL表单中嵌入FireMonkey（FMX）表单作为控件，因此您可以设计FMX表单并在VCL应用程序中使用它.

* [PascalSCADA](http://sourceforge.net/projects/pascalscada) .  `[Delphi]``[FPC]`Delphi / Lazarus的组件（框架）集，使工业应用程序的开发变得简单（HMI =人机界面/ SCADA =系统控制和数据采集）.  它运行在Windows，Linux和FreeBSD上.

* [Windows Ribbon Framework for Delphi](https://github.com/turbopack/ribbonframework) .  `[Delphi]`这个Delphi库允许Delphi开发人员在他们的Delphi应用程序中使用Windows Ribbon Framework.  此库使用本机Windows库来实现功能区功能.  它不像其他Delphi组件集那样模拟Ribbon用户界面（或Delphi的内置Ribbon模拟组件）.

* [DKLang](https://github.com/yktoo/dklang) .  `[Delphi]`DKLang Localization Package是一组用于简化Delphi编写的应用程序本地化的类.

* [GNU Gettext for Delphi, C++ and Kylix](https://sourceforge.net/projects/dxgettext/) .  `[Delphi]`用于Borland Delphi和Borland C ++ Builder的GNU GetText翻译工具.

* [OpenWire](https://sourceforge.net/projects/openwireproject) .  `[Delphi]`该库允许编写高级VCL和FireMonkey组件，以实现快速无代码应用程序开发.  使用库开发的组件允许创建具有零行程序代码的复杂应用程序.

* [SynTaskDialog](https://github.com/synopse/mORMot/blob/master/SynTaskDialog.pas) .  `[Delphi]``[FPC]`实现TaskDialog窗口（原生于Vista / Seven，在XP上模拟）

* [AnyiQuack](https://github.com/WladiD/AnyiQuack) .  `[Delphi]`类jQuery控件动画框架.

* [TLanguages](https://github.com/albertodev01/TLanguages) .  `[Delphi]`VCL和FMX的本地化工具.


## Database ##

* [ZeosLib](http://sourceforge.net/projects/zeoslib) .  `[Delphi]``[FPC]`用于MySQL，PostgreSQL，Interbase，Firebird，MS SQL，Sybase，Oracle和SQLite的数据库组件集.

* [Unified Interbase](https://github.com/hgourvest/uib) .  `[Delphi]`使用Interbase，FireBird和YAFFIL的组件集.  这些组件源于在多线程环境（例如服务器）中尽可能快地使用Interbase，FireBird或Yaffil的需要.

* [ASQLite](https://github.com/remobjects/ASQLite3) .  `[Delphi]`来自aducom软件的Delphi SQLite DAC组件，基于他们最新的Delphi 2009版本，并更新为支持Delphi的RemObjects Data Abstract中包含的Delphi的新版本.

* [TxQuery](https://github.com/ccy/txquery) .  `[Delphi]`TDataSet后代组件，可用于使用SQL语句查询一个或多个TDataSet后代组件.  它是用Delphi 100％源代码实现的，不需要DLL，因为它实现了自己的SQL语法分析器和SQL引擎.

* [Delphi-ORM](https://github.com/danieleteti/delphi-orm) .  `[Delphi]`Delphi XE2-7（Win32）的对象关系映射.  支持FirebirdSQL，SQLServer和SQLite3.

* [delphimemcache](https://code.google.com/p/delphimemcache) .  `[Delphi]`为memcached实现一个线程安全客户端.
// *需要Indy 10 *

* [SynDB](https://github.com/synopse/mORMot) ([docs](http://synopse.info/files/html/Synopse%20mORMot%20Framework%20SAD%201.18.html#TITL_126) ）.  `[Delphi]``[FPC]`高性能直接访问SQLite3，Oracle，MSSQL，PostgreSQL，Firebird，MySQL，ODBC，OleDB，包括远程HTTP连接和直接JSON支持.

* [SynMongoDB](https://github.com/synopse/mORMot/blob/master/SynMongoDB.pas) ([docs](http://blog.synopse.info/post/2014/05/07/MongoDB-database-access) ）.  `[Delphi]``[FPC]`提供对任何MongoDB服务器，其自定义数据类型，JSON或通过`TDocVariant`自定义变体文档存储的直接低级访问.

* [DSharp](https://bitbucket.org/sglienke/dsharp) .  `[Delphi]`用于在Delphi中提供数据绑定的小型库.  数据绑定到属性不需要特殊组件.  它还提供依赖注入，MVVM和更有趣的实用程序.

* [ghORM](https://github.com/leledumbo/ghORM) .  `[FPC]`对象关系映射单元，通过抽象后端和简单数据检索（带过滤），插入和更新，简化Free Pascal的数据库访问.

* [tDBF](http://sourceforge.net/p/tdbf/code/HEAD/tree) .  `[Delphi]``[FPC]`Native dBASE III +，dBase IV和dBase 2k数据访问组件，用于Delphi，BCB，Kylix，FreePascal.  它允许您创建非常紧凑的数据库程序，不需要任何特殊的安装程序.  数据库引擎代码编译到您的可执行文件中.

* [Redis client](https://github.com/danieleteti/delphiredisclient)  `[Delphi]`Delphi Redis Client版本2兼容Delphi 10.1 Berlin和更好.  警告！  如果您使用较旧的Delphi版本，则必须使用 [Delphi Redis Client Version 1](https://github.com/danieleteti/delphiredisclient/tree/DELPHI_REDIS_CLIENT_VERSION_1)  适用于Delphi 10 Seattle，XE8，XE7，XE6和XE5（也适用于旧版本）.  此客户端能够发送所有Redis命令并使用内部解析器读取响应.

* [QDAC3](http://blog.qdac.cc/?page_id=139)  （SVN：svn：//www.qdac.cc/QDAC3）.  `[Delphi]`代表快速数据访问组件.  有用的单位，如QJson（易于使用的json单位），QWorker（工作交付）等.
 // *中文描述和评论，作者不擅长英语.  我自己没有测试过这个库.*

* [InstantObjects](https://github.com/EtheaDev/InstantObjects) .  `[Delphi]`用于在Delphi中开发面向对象业务解决方案的集成框架.  该框架为开发过程以及为最终应用程序提供动力的引擎提供了基础.  InstantObjects提供：通过集成的双向工具在Delphi IDE中实现模型;  最常见的关系数据库或基于XML的平面文件中的对象持久性;  通过标准数据感知控件进行对象呈现.

* [Alcinoe](#general-libraries) .  火鸟/ MySQL的/ sqlite3的/ Memcached的/的MongoDB / SphinxQL.

* [SynBigTable](https://github.com/synopse/mORMot/blob/master/SynBigTable.pas) .  `[Delphi]``[FPC]`用于存储大量数据并快速检索的类.

* [tiOPF](https://github.com/graemeg/tiopf) .  `[Delphi]``[FPC]`用Object Pascal编写的Object Persistent Framework，用于Delphi和Free Pascal（FPC）编译器.  tiOPF简化了面向对象的业务模型到关系数据库的映射.  持久层可用于Firebird，Oracle，MS SQL Server，MySQL，PostgreSQL，SQLite，NexusDB，XML，CSV，TAB，Remote（通过HTTP）等等.  它还允许您使用您选择的数据库连接组件，如IBX，dbExpress，DOA，SqlDB，FBLib等.

* [hcOPF](https://sourceforge.net/projects/larryhengensopf) .  `[Delphi]`用Embarcadero的Delphi（Object Pascal）编写的Object Persistent Framework.  此值类型框架提供了一个由属性对象组成的基类（ThcObject），这些属性对象可以自动持久保存到对象存储（通常是RDBMS）.

* [Marshmallow](https://bitbucket.org/soundvibe/marshmallow/wiki/Home) .  `[Delphi]`Delphi XE2-7（Win32）的对象关系映射，受.NET micro ORM（主要是PetaPoco）和Java Hibernate的启发.  由Linas Naginionis开发.  支持SQLite，Sybase ASA，SQL Server，Firebird，Oracle，MySQL，PostgreSQL，MongoDB.  用途 [Spring](http://code.google.com/p/delphi-spring-framework/)  框架.  积极发展.

* [DelphiCassandra](https://github.com/grijjy/DelphiCassandra) .  `[Delphi]`Delphi驱动程序类与Cassandra数据库进行通信.

* [DelphiCouchbase](https://github.com/grijjy/DelphiCouchbase) .  `[Delphi]`Delphi驱动程序类与Couchbase数据库进行通信.

* [DelphiMongoDB](https://github.com/grijjy/DelphiMongoDB). `[Delphi]` Delphi driver classes to communicate with MongoDB database.

* [QuickORM](https://github.com/exilon/QuickORM) .  `[Delphi]``[FPC]`QuickORM是一个基于mORMot框架的简单RestServer和Restclient.  在几分钟内提供客户端 - 服务器应用程序的快速实现.


## Scripting ##
*在您的应用程序中使用脚本引擎*

* [Pascal Script](https://github.com/remobjects/pascalscript) .  `[Delphi]``[FPC]`自由脚本引擎，允许您在运行时使用Delphi或Free Pascal项目中的大部分Object Pascal语言.  它完全用Delphi编写，由一组可以编译成可执行文件的单元组成，无需分发任何外部文件.  Pascal Script开始时需要一个好的工作脚本，当时没有可用的脚本.

* [DWScript](https://bitbucket.org/egrange/dwscript) .  `[Delphi]`面向对象的Delphi脚本引擎，基于Delphi语言，扩展借用其他Pascal语言（FreePascal，Prism等）.  它还引入了一些自己的Pascal语言扩展.

* [Delphi-Javascript](https://code.google.com/p/delphi-javascript) .  `[Delphi]`用于delphi的Javascript引擎，基于Mozilla的Spidermonkey.
// *需要Spidermonkey DLL *

* [Blaise](http://sourceforge.net/projects/blaise) .  `[Delphi]`开源的面向对象的脚本语言.  语言特征：面向对象;  Unicode支持;  可选输入，即动态或静态输入;  丰富的打字;  高级数学支持，例如复数，有理数和矩阵;  虚拟机架构;  协程;  熟悉的语言语法，受Object Pascal，Python和Ada的影响.

* [SpiderMonkey](https://github.com/synopse/mORMot/blob/master/SynSM.pas) .  `[Delphi]``[FPC]`绑定Mozilla JavaScript引擎，包括JIT和多线程，通过Delphi变体轻松访问对象.
// *需要Spidermonkey DLL *

* [BESEN](https://github.com/BeRo1985/besen) .  `[Delphi]``[FPC]`Object Pascal中的完整ECMAScript第五版实现，可与Delphi&gt; = 7和Free Pascal&gt; = 2.5.1（也可能是2.4.1）编译.

* [Python for Delphi (P4D)](https://github.com/pyscripter/python4delphi) .  `[Delphi]``[FPC]`将Python dll包装成Delphi和Lazarus（FPC）的免费组件集.  它们可以让您轻松执行Python脚本，创建新的Python模块和新的Python类型.  您可以创建Python扩展作为dll等等

* [CrystalLUA](https://github.com/d-mozulyov/CrystalLUA) .  `[Delphi]`Lua绑定（Delphi6-2007）.
// *需要LUA DLL *

* [lua4delphi](https://github.com/danieleteti/lua4delphi) .  `[Delphi]`用于Lua 5.1语言的Delphi绑定.
// *需要LUA DLL *

* [chakracore-delphi](https://github.com/tondrej/chakracore-delphi) .  `[Delphi]``[FPC]`用于Microsoft的ChakraCore JavaScript引擎库的Delphi和Free Pascal绑定和类.

* [VerySimple.Lua](https://github.com/Dennis1000/verysimplelua) .  `[Delphi]`Lua Wrapper for Delphi XE5-D10.1，它自动为Delphi &lt; - &gt; Lua创建OOP回调函数.
// *需要LUA DLL *


## Non-visual Classes/Utils ##


## Compression

* [FWZip](https://github.com/AlexanderBagel/FWZip) .  `[Delphi]`使用Store和Deflate方法处理Zip存档的类，支持ZIP64，DataDescryptors，PKWARE加密，NTFS属性，文件名中的Utf8.
 // *使用编译成二进制文件的库存ZLIB.obj.  俄语的评论和描述.*

* [Abbrevia](http://sourceforge.net/p/tpabbrevia) ([Newest](https://github.com/TurboPack/Abbrevia)  并维护最新编译器版本的版本）.  `[Delphi]`用于Delphi和C ++ Builder的高级数据压缩工具包.  支持PKZIP，Microsoft CAB，tar，gzip和bzip2存档，并可以创建自解压可执行文件.  在Windows上，它还为LZMA，Bzip2和WavPack SDK以及PPMd解压缩提供Delphi包装.  Abbrevia还有几个简化显示和操作档案的视觉控件，包括treeview和listview组件.  功能：所有存档格式的Unicode文件名;  解压缩大多数.zipx和legacy（PKZIP v1）拉链;  ZIP64支持大于2GB的档案;  跨区和分割拉链档案;  跨平台（Windows，OS X和Linux）;  不需要DLL;  包括COM组件;  丰富的文档
// *第二个链接指向最新编译器版本的改编版本.*

* [SynLZ SynLZO SynZip PasZip](https://github.com/synopse/mORMot) .  `[Delphi]``[FPC]`几种高速压缩单元，采用ZIP / LZ77 Deflate / Inflate，LZO和SynLZ算法，采用pascal和优化汇编程序.

* [Delphi zlib](http://www.base2ti.com/?id=delphi.zlib) .  `[Delphi]`最初由Borland使用的zlib.obj包装器.  Delphi最高支持XE3.

* [DIUcl](http://www.yunqa.de/delphi/products/ucl/index) .  `[Delphi]`DIUcl是一个无损压缩库，具有极快和小（仅200字节！）的ASM解压缩器.  压缩时间和比率与deflate / zip和bzip2类似.  流行的UCL压缩库的Delphi端口，也被流行的和众所周知的UPX Ultimate Packer用于eXecutables.


## Encryption

* [Delphi Encryption Compendium (DEC)](https://github.com/winkelsdorf/DelphiEncryptionCompendium) .  `[Delphi]`用于Delphi和C ++ Builder的加密库.  对称密码函数：Blowfish，Twofish，IDEA，Cast128，Cast256，Mars，RC2，RC4，RC5，RC6，Rijndael / AES，Square，SCOP，Sapphire，1DES，2DES，3DES，2DDES，3DDES，3TDES，3Way，Gost， Misty，NewDES，Q128，SAFER，Shark，Skipjack，TEA，TEAN;  分组密码操作模式：CTSx，CBCx，CFB8，CFBx，OFB8，OFBx，CFSx，ECBx;  哈希：MD2，MD4，MD5，RipeMD128，RipeMD160，RipeMD256，RipeMD320，SHA，SHA1，SHA256，SHA384，SHA512，Haval128，Haval160，Haval192，Haval224，Haval256，Tiger，Panama，Whirlpool，Whirlpool1，Square，Snefru128，Snefru256，蓝宝石.
 // *自2010年以来没有更新，一些活动始于2018年**开发**分支.  无论如何功能列表如此巨大，以至于不容忽视*

* [LockBox](http://sourceforge.net/projects/tplockbox) ([Newest](https://github.com/TurboPack/LockBox3)  并维护最新编译器版本的版本）.  `[Delphi]`用于加密的Delphi库.  目前支持Delphi XE6.  它支持AES，DES，3DES，Blowfish，Twofish，SHA2（包括新的SHA-512/224和SHA-512/256），MD5;  ECB，CBC，CFB8，CFB，CTR，ECB，OFB，PCBC链接模式，RSA数字签名和验证.  具有OpenSSL库的接口.
// *查看 [this](https://github.com/jarto/lockbox2) 页面以及替代版本.*

* [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas) .  `[Delphi]``[FPC]`快速加密例程（散列和密码），实现AES，XOR，RC4，ADLER32，MD5，SHA1，SHA256算法，针对速度进行了优化（调整汇编程序和VIA PADLOCK可选支持）.

* [TForge](https://bitbucket.org/sergworks/tforge) .  `[Delphi]``[FPC]`用Delphi编写的开源加密库，与Free Pascal Compiler兼容.  MD5，SHA1，SHA256，CRC32，Jenkins-One-At-Time，HMAC，PBKDF1，PBKDF2，AES，DES，RC4，RC5，Salsa20.

* [Spring4D](#general-libraries)CRC，DES，MD5，SHA

* [Fundamentals Code Library](#general-libraries) .  哈希：XOR，CRC，Adler，MD5，SHA，安全密钥MD5 / SHA等;  密码：AES，DES，FUNE，RC2 / 4，RSA.

* [Alcinoe](#general-libraries) .  AES，Blowfish，MD5，SHA，安全密钥MD5 / SHA.

* [DCPcrypt (fork #1)](https://sourceforge.net/projects/dcpcrypt), [DCPcrypt (fork #2)](https://bitbucket.org/wpostma/dcpcrypt2010) .  `[Delphi]`Delphi的加密组件套件.

* [HashLib4Pascal](https://github.com/Xor-el/HashLib4Pascal) .  `[Delphi]``[FPC]`Delphi / FreePascal兼容库，它提供了一个易于使用的接口，用于计算字符串的哈希和校验和（具有指定的编码），文件，流，字节数组和无类型数据，但仅举几例.  它还支持增量散列.

* [CRC/Hash](http://www.wolfgang-ehrhardt.de/crchash_en.html) .  `[Delphi]``[FPC]`与CRC，哈希和HMAC计算相关的Pascal / Delphi源和二进制文件.  CRC，Adler，BJ查找，MD5，SHA，Whirlpool，Blake

* [Crypto](http://www.wolfgang-ehrhardt.de/crypt_en.html) .  `[Delphi]``[FPC]`几种密码算法：128位块密码AES和Twofish，64位分组密码Blowfish，流密码Salsa20 / XSalsa20 / ChaCha和Sosemanuk.


## XML/JSON/YAML

* [dataset-serialize](https://github.com/viniciussanchez/dataset-serialize) .  `[Delphi]`这个组件是Delphi的DataSet组件的JSON序列化器.  允许您将JSON转换为DataSet，将DataSet转换为JSON，并以JSON格式导出和加载DataSet字段的结构.  兼容VCL项目，FMX和uniGUI（框架）.

* [OmniXML](https://github.com/mremec/omnixml) .  `[Delphi]`用Delphi编写的XML解析器.  完全支持文档对象模型（DOM）1级规范;  支持可扩展标记语言（XML）1.0（第二版）规范;  内置支持不同的代码页（主要的8位代码页，UTF-8，UTF-16）;  与MS XML解析器兼容;  快速解析大型高度结构化的文档;  包含辅助函数以简化XML文档的处理;  简化的XPath支持.

* [SAX for Pascal](http://sourceforge.net/projects/saxforpascal) .  `[Delphi]``[FPC]`旨在为Pascal / Delphi中的XML解析实现Simple API.
 // *基于回调的XML解析器，对处理大量XML流非常有用.  自2004年以来被遗弃，但几乎是唯一可用的SAX实施.*

* [KDS XML](http://sourceforge.net/projects/kdsxml) .  `[Delphi]`用于流式解析，验证和生成XML的类库.  它是用Object Pascal / Delphi编写的，适用于Win32（Delphi）和Linux（Kylix）.  部分内容取决于SAX for Pascal接口规范.
// *Seems dead.*

* [XML Partner](http://sourceforge.net/projects/tpxmlpartner) .  `[Delphi]`通过本机易于使用的VCL和CLX组件，帮助将Borland Delphi，C ++ Builder和Kylix项目的XML功能增加.  这些功能强大的组件简化了创建，修改和解析XML数据文档的过程.
// *好像死了，退房 [this](http://www.songbeamer.com/delphi) 可能是更新版本的页面.*

* [Open XML](http://www.philo.de/xml/downloads.shtml) .  `[Delphi]`提供各种方法，组件和基础类.  它可以用于Win32 / Kylix以及.NET开发.

* [SuperObject](https://github.com/hgourvest/superobject) .  `[Delphi]``[FPC]`用于JSON数据格式的解析器/编写器.  此工具包旨在与Delphi和FreePascal（win32，win64，linux32，linux64，MacOSX Intel）配合使用.  支持读/写XML.

* [Libxml2 for pascal](https://sourceforge.net/projects/libxml2-pas) .  `[Delphi]``[FPC]`Pascal单元访问Daniel Veillard的流行XML API.  这应该至少可以从Kylix和Delphi中使用，但希望也可以从其他Pascal编译器（如freepascal）中使用.

* [NativeXml](https://code.google.com/p/simdesign) .  `[Delphi]`这个组件包含一个小型的Object Pascal（Delphi）XML实现，它允许读写XML文档.  您基本上只需要一个单元，您只需将其添加到“uses”子句中即可.  您可以使用此软件从文件，流或字符串中读取XML文档.  加载例程生成可用于动态显示加载进度的事件.  您还可以使用它来创建和保存XML文档.

* [Delphi-XmlLite](https://github.com/the-Arioch/Delphi-XmlLite) .  `[Delphi]`Microsoft XmlLite的头文件翻译.  XmlLite是.NET XmlReader + Writer的本机C ++实现，用于基于流的，仅向前XML解析和创建.  XmlLite.dll是必需的.  它包含在所有新版本的Windows中，以及旧版本的Service Pack.  XmlReader的基于拉式的界面比SAX基于事件的界面更清晰.
// *似乎被遗弃并且据报道有些马车.*

* [Chimera](https://bitbucket.org/sivv/chimera) .  用于Delphi XE2的`[Delphi]`开源（MIT许可证）库，它提供了一个快速且跨平台的JSON生成器/解析器（序列化器/解串器），其许可证并不吸引人.

* [SynCommons](https://github.com/synopse/mORMot/blob/master/SynCommons.pas) .  `[Delphi]``[FPC]`高速JSON库，使用`TDocVariant`自定义变量类型进行存储和访问.

* [SynCrossPlatformJSON](https://github.com/synopse/mORMot/blob/master/CrossPlatform/SynCrossPlatformJSON.pas) .  `[Delphi]``[FPC]`高速跨平台JSON库，使用`TJSONVariant`自定义变体类型进行存储和访问.

* [Json Data Objects](https://github.com/ahausladen/JsonDataObjects) .  `[Delphi]`这个Delphi单元包含一个JSON解析器，支持Delphi 2009-10Seattle和平台Win32，Win64和ARM Android（MacOS和iOS可能有效）.

* [TinyJSON](http://sourceforge.net/projects/tiny-json) ([mirror at GH](https://github.com/tmcdos/tiny-json) ）.  `[Delphi]`这是一个小而干净的库，用于具有Boolean / Integer / Float / WideString值的关联数组.  允许从（到）JSON文本导入（导出）.  广泛的错误检查.  使用FunHash（由Sokolov Yura提供），HatTrie（由Daniel C. Jones提供），FastInt64和FastMove（由FastCode项目提供）.

* [JSON delphi library](http://sourceforge.net/projects/lkjson) .  `[Delphi]`这是一个实现JSON数据格式和对象结构的delphi库.  轻巧快速.

* [dwsJSON](https://bitbucket.org/egrange/dwscript/src/b9f99d4b8187defac3f3713e2ae0f7b83b63d516/Source/dwsJSON.pas?at=master) .  `[Delphi]``[FPC]`dwsJSON是一个支持JSON解析/创建的单元，它是DWScript的一部分但是相对“独立”，因为如果你在Delphi（或FPC）项目中添加它，它就不会拉动整个DWScript库，因此可以在任何需要的地方使用.

* [Fundamentals Code Library](#general-libraries) .  JSON，XML.

* [Alcinoe](#general-libraries). XML/JSON Parser.

* [delphi-yaml](https://bitbucket.org/OCTAGRAM/delphi-yaml) .  `[Delphi]`用于在C中实现的libyaml，YAML解析器和发射器库的Delphi 7兼容绑定.提出了四层绑定.

* [GrijjyFoundation](#general-libraries) .  JSON / BSON.

* [VerySimpleXML](https://github.com/Dennis1000/verysimplexml) .  `[Delphi]`用于Delphi 2010的轻量级，单机，跨平台XML读写器 -  10.2.2东京

* [XSuperObject](https://github.com/onryldz/x-superobject) .  `[Delphi]`Delphi Cross Platform Rapid JSON

* [Internet Tools](https://github.com/benibela/internettools) .  `[Delphi]``[FPC]`Package提供标准的符合XPath 2.0，XQuery 1.0和XPath / XQuery 3.0解释器，其中包括JSONiq，模式匹配，CSS和HTML等扩展.  以及在Windows / Linux / MacOSX / Android上执行HTTP / S请求的功能，XSLT启发的Webscraping语言和自动更新类.

* [Delphi-JsonToDelphiClass](https://github.com/PKGeorgiev/Delphi-JsonToDelphiClass) .  `[Delphi]`基于JSON字符串生成Delphi类（Json To Delphi类生成器/ JSON数据绑定工具）.  还包括与GitHub交互的单元.

* [XML Parser](http://www.destructor.de/xmlparser) .  `[Delphi]``[FPC]`用于Delphi和FreePascal的轻量级ObjectPascal XML解析器.  通过省略语法检查，良构性检查和/或验证，以及通过选择逐行扫描技术，该解析器非常快.

* [HTML parser](https://github.com/ying32/htmlparser) .  `[Delphi]`HTML解析器.  支持Windows，MacOSX，iOS，Android平台.  ÑommentsinChinese 


## Language
* Pascal和其他语言的工具*

* [Next Delphi Yacc & Lex](https://github.com/RomanYankovsky/ndyacclex) .  `[Delphi]`用于Delphi的解析器生成器工具集.

* [Abstract Syntax Tree Builder](https://github.com/RomanYankovsky/DelphiAST) .  `[Delphi]`使用DelphiAST，您可以获取真正的Delphi代码并获得抽象语法树.  一个单位在时间，但没有符号表.

* [Castalia-Delphi-Parser](https://github.com/jacobthurman/Castalia-Delphi-Parser) .  `[Delphi]`这些文件组成了一个手写的高速解析器，用于Object Pascal方言，称为“Delphi”.  最初的工作是由Martin Waldenburg在20世纪90年代末完成的，该项目在2003年之前的某个时候被废弃，当时我找到了代码并开始研究它.  我已经根据需要更新了我的项目，名为“Castalia”.

* [CrossPascal](https://github.com/BeRo1985/crosspascal) .  `[Delphi]`旨在成为Delphi 7兼容的跨平台源到源编译器（连同XE3的新unicode字符串类型，但其中ansistring仍然是仍然是Delphi 7兼容的默认字符串类型），它生成中间C代码.
// *相当有趣的项目虽然似乎被遗弃*

* [pas2js](https://svn.freepascal.org/svn/projects/pas2js/trunk), [docs](http://wiki.freepascal.org/pas2js) .  `[Delphi]``[FPC]`一个开源的Pascal到JavaScript的转换器.  它解析Object Pascal并发出JavaScript.  JavaScript目前的级别为ECMAScript 5，应该可以在任何浏览器或Node.js（目标“nodejs”）中运行.  基本上，支持Delphi 7语法.  用于TMS WebCore和Elevate Web Builder等工具.


## Memory managers
*实现动态内存分配的库*

* [FastMM](https://github.com/pleriche/FastMM4) .  `[Delphi]`用于Embarcadero Delphi Win32和Win64应用程序的Lightning快速替换内存管理器，它不容易出现内存碎片，并且在不使用外部.DLL文件的情况下支持共享内存.
 // *自2006年起用作库存内存管理器，但采用简化版.  提供强大的内存泄漏/损坏检测工具.*

* [ScaleMM](https://github.com/andremussche/scalemm) .  `[Delphi]`用于Delphi的快速扩展内存管理器

* [BrainMM](https://github.com/d-mozulyov/BrainMM) .  `[Delphi]`Delphi非常快的内存管理器.
// *高级内存分配功能，可实现更快的对齐操作.*

* [FastMM4-AVX](https://github.com/maximmasiutin/FastMM4-AVX) .  `[Delphi]``[FPC]`FastMM4 fork，支持AVX和多线程增强（更快锁定）


## System
*低级助手：内存，线程等*

* [OmniThreadLibrary](https://github.com/gabr42/OmniThreadLibrary) .  `[Delphi]`简单易用的Delphi线程库.
// *在您的应用中轻松集成异步流程*

* [Delphi Detours Library](https://github.com/mahdisafsafi/delphi-detours-library) .  `[Delphi]``[FPC]`库允许你挂钩Delphi函数和对象方法以及Windows API函数.  它提供了一种插入和移除钩子的简便方法.
// *支持x64，调用原始函数，多重挂钩，COM /接口/ win32api，对象方法挂钩，完全线程安全，Delphi 7 / 2005-2010 / XE-XE7和Lazarus / FPC，支持64位地址.*

* [MemoryModule](https://github.com/Fr0sT-Brutal/Delphi_MemoryModule) .  `[Delphi]``[FPC]`使用MemoryModule引擎，您可以在二进制文件中存储所有必需的DLL，以使其保持独立.  额外的挂钩单元允许透明使用MM引擎，从而允许切换MM / WinAPI加载以及启用不了解MM的第三方动态加载DLL接口（使用Interbase Express组件和Firebird客户端库进行测试）.  MemoryModule是Joachim Bauch的C MemoryModule的Pascal端口.

* [DirectoryWatcher](https://github.com/Wosi/DirectoryWatcher) .  `[Delphi]`观察不同平台（Windows / Linux / Mac OS）上目录的变化.


## Template
*引擎根据模板生成文本输出*

* [SynMustache](https://github.com/synopse/dmustache) .  `[Delphi]```[FPC]`Delphi实现的Mustache模板语言，支持Delphi 6高达Delphi 10 Seattle（和FPC / Lazarus编译）.

* [Delphi Template Engine](http://sourceforge.net/projects/delphi-templeng) .  `[Delphi]`模板引擎，设计用作Delphi（主要是Delphi 7）应用程序中的库，允许开发人员在他们的软件上使用模板而不用担心实现它.

* [MustaPAS](https://github.com/leledumbo/mustapas) .  `[Delphi]``[FPC]`简单程序Pascal中的Mustache实现.


## Logging

* [Log4d](https://github.com/landrix/Log4d-for-Delphi) .  `[Delphi]``[FPC]`基于Log4j的Delphi日志系统的实现.

* [TraceTool](http://tracetool.sourceforge.net/). `[Delphi]` C#, C++, Delphi, ActiveX and Java trace framework and a trace viewer.

* [LoggerPro](https://github.com/danieleteti/loggerpro) .  `[Delphi]`Delphi的现代可插拔日志框架.

* [SynLog](https://github.com/synopse/mORMot/blob/master/SynLog.pas) .  `[Delphi]``[FPC]`Synopse项目使用的记录功能.

* [slf4p](https://github.com/michaelJustin/slf4p) .  `[Delphi]``[FPC]`一个简单的日志记录，支持LazLogger，Log4D和其他日志框架.

* [GrijjyCloudLogger](https://github.com/grijjy/GrijjyCloudLogger) .  `[Delphi]`远程日志记录工具，允许您通过Intranet或Internet从Windows，Linux，iOS，Android和macOS设备向Windows上运行的查看器发送日志消息.  除了发送消息以及任何数据外，它还具有众多功能，包括自定义实时监视，对象的远程实时视图，跟踪实时内存使用，对象分配，增长泄漏等.

* [QuickLogger](https://github.com/exilon/QuickLogger) .  `[Delphi]``[FPC]`Delphi / freepascal / .NET（Windows / Linux）库，用于登录文件，控制台，内存，电子邮件，休息，电报，松弛，事件日志，redis，ide调试消息和抛出事件. .


## Math

* [Big Decimal Math](https://github.com/benibela/bigdecimalmath) .  `[Delphi]`这个单元提供任意精度的BCD浮点数类型.  它可以像任何数字类型一样使用并支持：至少10-2147483647到102147483647之间的数字，带有2147483647十进制数字精度;  所有标准算术和比较运算符;  舍入功能（floor，ceil，to-even，..）;  一些更高级的操作，例如power和sqrt.

* [TIntX](https://github.com/Xor-el/IntXLib4Pascal) .  `[Delphi]``[FPC]`Pascal端口的IntX任意精度整数库用快速，约O（N * log N）乘法/除法算法实现.  它提供了对整数的所有基本算术运算，比较，按位移位等.它还允许解析不同基数中的数字并将它们转换为字符串，也可以在任何基数中.  该库的优势在于其快速乘法，除法和基本/基本转换算法.  算法的所有快速版本都基于使用快速哈特利变换的大整数的快速乘法，快速哈特利变换运行O（N * log N * log log N）时间而不是经典O（N ^ 2）.

* [DelphiBigNumberXLib](https://github.com/Xor-el/DelphiBigNumberXLib) .  `[Delphi]`Delphi的任意精度库，支持整数和浮点计算.

* [FastMath](https://github.com/neslib/FastMath) .  `[Delphi]`Delphi数学库，针对快速性能进行了优化（有时以不执行错误检查或丢失一点精度为代价）.  它使用手动优化的汇编代码，以获得比Delphi RTL提供的等效功能更好的性能.
// *浮点，向量，矩阵运算.*

* [MPArith](http://www.wolfgang-ehrhardt.de/misc_en.html#mparith) .  `[Delphi]`多精度整数，有理，真实和复杂的算术.

* [AMath](http://www.wolfgang-ehrhardt.de/misc_en.html#amath) 和 [DAMath](http://www.wolfgang-ehrhardt.de/misc_en.html#damath). `[Delphi]` Accurate mathematical methods without using multi precision arithmetic 和 double precision accurate mathematical methods without using multi precision arithmetic or assembler respectively.

* [ALGLIB](http://www.alglib.net/download.php) .  `[Delphi]``[FPC]`跨平台数值分析和数据处理库.  它支持多种操作系统（Windows和POSIX，包括Linux）.  ALGLIB功能包括：数据分析（分类/回归，统计）;  优化和非线性求解器;  插值和线性/非线性最小二乘拟合;  线性代数（直接算法，EVD / SVD），直接和迭代线性求解器;  快速傅里叶变换和许多其他算法.
//免费版是Delphi，包含许可用于个人和学术用途的通用C核.


## Other non-visual

* [TRegExpr](https://github.com/ashumkin/RegExpr) .  `[Delphi]`易于使用且功能强大的工具，用于复杂的搜索和替换以及基于模板的文本输入检查.
// *自2004年以来被遗弃但不同于RAD Studio的实现不使用添加对msvcrt.dll *的依赖的PCRE obj文件

* [FLRE](https://github.com/BeRo1985/flre) .  `[Delphi]``[FPC]`FLRE（F ast Light R egular E xpressions）是一个快速，安全，高效的正则表达式库，它在Object Pascal（Delphi和Free Pascal）中实现，但它甚至可以从其他语言如C / C ++等.

* [OnGuard](http://sourceforge.net/projects/tponguard) ([Alternate](https://github.com/TurboPack/OnGuard-VCL) and maintained version for recent compiler version only). `[Delphi]` Library to create demo versions of your Borland Delphi & C++Builder applications. Create demo versions that are time-limited, feature-limited, limited to a certain number of uses, or limited to a certain # of concurrent network users.
// *第二个链接指向最新编译器版本的改编版本.*

* [StringSimilarity](https://github.com/chaosben/theunknownones) .  `[Delphi]`为一些模糊和语音字符串比较算法设计的包.  到目前为止实施的是以下算法：DamerauLevenshtein，Koelner Phonetik，SoundEx，Metaphone，DoubleMetaphone，NGram，Dice，JaroWinkler，NeedlemanWunch，SmithWatermanGotoh，MongeElkan.

* [PubSub Chimera](https://code.google.com/p/pubsubchimera) .  用于Delphi的`[Delphi]`开源（MIT许可）库，它提供了一个快速且跨平台的PubSub和Message Queue实现，其许可证无法实现.

* [DuckDuckDelphi](https://code.google.com/p/duckduckdelphi) .  `[Delphi]`为Delphi Objects添加简单的鸭子类型，并提供一个RTTI助手类来简化许多常见的RTTI任务.

* [byterage](https://github.com/quartexNOR/byterage) .  `[Delphi]`Object pascal类库旨在消除流的一些限制.  该框架使用起来非常简单，只有一个共同的祖先类（TBRBuffer），它定义了一组存储不可知机制，用于分配，缩放，插入，删除和操作一段原始二进制数据.

* [stateless](https://github.com/SirRufo/stateless) .  `[Delphi]`用于在Delphi代码中创建状态机的简单库.

* [GenericTree](https://github.com/davidberneda/GenericTree) .  `[Delphi]`Delphi实现了一个通用的Tree结构.

* [Delphi Event Bus](https://github.com/spinettaro/delphi-event-bus)  （简称DEB）.  `[Delphi]`Delphi的Event Bus框架.

* [DelphiEventBus](https://github.com/BitecSPB/DelphiEventBus) .  `[Delphi]`另一个Delphi的事件总线框架，带有注释和丰富的事件过滤.

* [DHibernate](https://github.com/thecocce/delphi-hibernate) .  `[Delphi]`基于Hibernate和NHibernate for Delphi的Object Persistent Framework.
// *自2012年起放弃*

* [UniConv](https://github.com/d-mozulyov/UniConv). `[Delphi]` `[FPC]` Universal text conversion library is a universal quick and compact library intended for conversion, comparison and change of the register of text in concordance with the latest standards of the Unicode Consortium. The librarys function greatly resembles ICU, libiconv and Windows.kernel which are de facto standard for popular operating systems.

* [CachedBuffers](https://github.com/d-mozulyov/CachedBuffers) .  `[Delphi]``[FPC]`该库对于顺序数据读取或写入的任务是不可替代的，特别是如果性能要求增加且数据量很大的话.

* [CachedTexts](https://github.com/d-mozulyov/CachedTexts) .  `[Delphi]``[FPC]`功能强大且紧凑的跨平台库，旨在以最大可能的性能解析和生成文本数据.  取决于其他两个库：CachedBuffers和UniConv.

* [ZEXMLSS](https://github.com/Avemey/zexmlss) .  `[Delphi]``[FPC]`Lazarus / Delphi组件，用于读/写ods，excel xml，xlsx.

* [PasMP](https://github.com/BeRo1985/pasmp) .  `[Delphi]``[FPC]`Object Pascal的并行处理/多处理库.

* [TCommandLineReader](https://github.com/benibela/rcmdline) .  `[Delphi]``[FPC]`这个单元为Lazarus和Delphi提供了一个高级的，独立于平台的命令行解析器.  它检查允许的选项，自动打印一个包含所有这些选项的帮助，并且 - 与rtl中的解析器相反 - 在Windows和Linux上的行为相同.

* [ICU4PAS](http://www.crossgl.com/icu4pas/index.html) .  `[Delphi]``[FPC]`Object Pascal，跨平台，Direct Class Wrapper，覆盖成熟且广泛使用的C / C ++ ICU库集，提供Unicode支持，软件国际化（i18n）和全球化（g11n），为应用程序提供所有平台上的结果相同.  您可以在Windows上使用Delphi和FreePascal，在Linux上使用Kylix和FreePascal.
// *自2007年以来没有更新，但ICU界面可能保持不变...... *

* [CommandLineParser](https://github.com/VSoftTechnologies/VSoft.CommandLineParser) .  `[Delphi]`简单的命令行选项解析器 - 来自DUnitX项目.

* [GpCommandLineParser](https://github.com/gabr42/GpDelphiUnits/blob/master/src/GpCommandLineParser.pas) .  `[Delphi]`基于属性的命令行解析器.

* [GpDelphiUnits](https://github.com/gabr42/GpDelphiUnits) .  `[Delphi]`有用的Delphi单元的集合.  各种TList后代，TList兼容和TList类似的类.  动态分配，O（1）入队和出队，线程安全，microlocking队列.  与64位文件功能的接口，具有一些附加功能.  字符串哈希，表和字典.  Win32 / Win64包装器和帮助器功能的集合.  时区例程.  嵌入式文件系统.

* [BaseNcodingPascal](https://github.com/Xor-el/BaseNcodingPascal) .  `[Delphi]``[FPC]`用于使用base32，base85，base128和其他FPC和Delphi算法将二进制数据编码成字符串的库.

* [ByteSizeLibPascal](https://github.com/Xor-el/ByteSizeLibPascal) .  `[Delphi]``[FPC]`TByteSize是一个实用程序“记录”，通过消除所表示的值的模糊性，使代码中的字节大小表示更容易.

* [EmailValidationPascal](https://github.com/Xor-el/EmailValidationPascal) .  `[Delphi]``[FPC]`用于验证Pascal / Delphi中电子邮件地址语法的简单类.

* [PRNG](http://www.wolfgang-ehrhardt.de/misc_en.html#prng) .  `[Delphi]`七个快速伪随机数发生器，周期长度远大于Pascal的随机函数.  所有都是使用上下文记录实现的，因此可以同时使用多个独立的生成器，它们不具有加密安全性.  此外，还有三个加密生成器.

* [CSV File and String Reader](https://www.codeproject.com/Tips/783493/Delphi-CSV-File-and-String-Reader-Classes) .  `[Delphi]`TnvvCSVFileReader和TnvvCSVStringReader是轻量级和快速类，类似于单向数据集.

* [HTMLBuilder](https://github.com/guitorres/htmlbuilder) .  `[Delphi]`使用pascal代码构建简化的html.

* [Marvin.IA](https://github.com/marvinbraga/Marvin.IA) .  `[Delphi]`机器学习面向对象的Pascal原语的集合（只有接口和类）.

* [FreePascal Generics.Collections](https://github.com/maciej-izak/generics.collections) .  `[FPC]`FreePascal Generics.Collections库（TList，TDictionary，THashMap等等）

* [FuzzyWuzzy.pas](https://github.com/DavidMoraisFerreira/FuzzyWuzzy.pas) .  `[FPC]`众所周知的Python模糊字符串匹配包的端口，它使用Levenshtein距离来计算字符串序列之间的差异.


## OS ##
*有助于处理特定于操作系统的内部的工具*

* [GLibWMI](http://sourceforge.net/projects/glibwmi) .  `[Delphi]`Delphi的组件库，用于封装用于在一组VCL中访问Windows WMI的类.  BiosInfo，PrinterInfo，DiskInfo，...允许访问WMI类：WIN32_Bios，WIN32_Printers，WIN32_DiskDrive.

* [MemoryMap](https://github.com/AlexanderBagel/ProcessMemoryMap/tree/master/MemoryMap) .  `[Delphi]`一组类，用于获取有关正在运行的进程的内存的所有信息.

* [The new Drag and Drop Component Suite](https://github.com/DelphiPraxis/The-Drag-and-Drop-Component-Suite-for-Delphi) .  `[Delphi]`VCL组件库，使您的Delphi和C ++ Builder应用程序能够支持基于COM的拖放并与Windows剪贴板集成.

* [TSMBIOS](https://github.com/RRUZ/tsmbios) .  `[Delphi]``[FPC]`允许使用Object Pascal语言（Delphi或Free Pascal）访问系统管理BIOS（SMBIOS）.  SMBIOS（系统管理BIOS）是DMTF开发的标准.  存储在SMBIOS中的信息包括设备制造商，型号名称，序列号，BIOS版本，资产标签，处理器，端口和安装的设备内存.

* [VersionInfo for Delphi](http://melander.dk/articles/versioninfo) .  `[Delphi]`该库使得从Windows可执行文件和DLL的Version Info资源中读取值非常容易.  （可选）通过类助手扩展TApplication类的版本信息属性.

* [Magenta Systems WMI and SMART Component](http://www.magsys.co.uk/delphi/magwmi.asp) .  `[Delphi]`包含WMI，SMART和SCSI PassThrough函数，特别用于获取硬盘信息和配置网络适配器，还用于许多其他一般用途.  MagWMI使用SQL命令提供对任何WMI信息的一般视图访问，还提供与TCP / IP配置相关的许多专用功能，例如设置适配器IP地址，计算机名称，域/工作组，BIOS和磁盘驱动器信息.

* [madKernel](http://help.madshi.net/madKernel.htm) .  `[Delphi]`这个包最重要的是关于内核对象.  最重要的对象类型包含在接口中，利用所有特定的kernel32 API.  具有以下接口包装：事件，互斥锁，线程，进程，Windows，模块，托盘图标，共享内存缓冲区.
// *免费提供非商业用途的资源（仅限） [conditions](http://help.madshi.net/License.htm) .  可以作为`madCollection`安装程序的一部分下载.  相当好记录.  需要`madBasic`包.*

* [madSecurity](http://help.madshi.net/madSecurity.htm) .  `[Delphi]`该软件包可以轻松处理共享和其他安全对象，如文件安全性或注册表安全性.  为了能够这样做，该软件包还具有围绕帐户和ACE以及ACL的功能.
// *免费提供非商业用途的资源（仅限） [conditions](http://help.madshi.net/License.htm) .  可以作为`madCollection`安装程序的一部分下载.  相当好记录.  需要`madBasic`包.*

* [madShell](http://help.madshi.net/madShell.htm) .  `[Delphi]`该软件包实现了经常需要的shell功能，从特殊文件夹开始，如“Windows”文件夹或“Program Files”文件夹，继续使用Shell ID Lists，Shell Objects和Shell Events.  然后，您将找到有关ShortCuts / ShellLinks的功能以及有关显示模式的所有信息.
// *免费提供非商业用途的资源（仅限） [conditions](http://help.madshi.net/License.htm) .  可以作为`madCollection`安装程序的一部分下载.  相当好记录.  需要`madBasic`包.*

* [WindowsAutorun](https://github.com/ms301/WindowsAutorun) .  `[Delphi]`帮助您在Windows操作系统中管理自动加载.


## Report generating ##

* [Report Manager](http://reportman.sourceforge.net) .  `[Delphi]`报表管理器是一个报表应用程序（Report Manager Designer）和一组用于预览，导出或打印报表的库和实用程序.  包括原生.Net和Delphi / C ++ Builder库，ActiveX组件以及标准动态链接库，可用于任何语言，如GNU C.

* [FortesReport](https://github.com/fortesinformatica/fortesreport-ce) .  `[Delphi]`FortesReport是一个功能强大的报表生成器，可作为Delphi的一个组件包.

* [mORMotReport](https://github.com/synopse/mORMot/blob/master/SQLite3/mORMotReport.pas) ([docs](http://synopse.info/files/html/api-1.18/mORMotReport.html) ）.  `[Delphi]`快速高效的基于代码的报告组件，具有预览表格和PDF导出功能.


## Unit Testing ##

* [DUnitX](https://github.com/VSoftTechnologies/DUnitX) .  `[Delphi]`新的测试框架，从DUnit，NUnit和其他测试框架中获取思路.  它旨在与Delphi 2010或更高版本一起使用，它使用了旧版本Delphi中不具备的语言/ RTL功能.

* [DUnit](http://dunit.sourceforge.net) .  单元测试框架，多年来一直是标准的测试框架，Delphi IDE现在附带了这个库.
 // *自XE以来包含，自XE8以来不赞成使用DUnitX;  似乎被遗弃了.*

* [DUnit2](http://dunit2.sourceforge.net) .  `[Delphi]`DUnit项目的分支，增加了几个新功能.
// *似乎被遗弃，缺少上一个DUnit版本的一些功能.*

* [DelphiSpec](https://github.com/RomanYankovsky/DelphiSpec) .  `[Delphi]`用于运行用简单语言编写的自动化测试的库.  因为它们是用简单的语言编写的，所以团队中的任何人都可以阅读它们.  因为任何人都可以阅读它们，您可以使用它们来帮助改善团队的沟通，协作和信任.

* [Delphi-Mocks](https://github.com/VSoftTechnologies/Delphi-Mocks) .  `[Delphi]`Delphi XE2或更高版本的简单模拟框架.  允许您模拟用于测试的类和接口.

* [DUnit-XML](https://github.com/VSoftTechnologies/DUnit-XML) .  `[Delphi]`测试运行器，允许DUnit测试输出NUnit兼容的XML.

* [Smoketest](https://github.com/deltics/delphi.libs/tree/master/smoketest) .  `[Delphi]`使用Delphi语言为Microsoft Windows编写测试和性能基准的框架.  它已经在7到2010年的所有版本的Delphi上进行了测试.

* [SynTests](https://github.com/synopse/mORMot/blob/master/SynTests.pas) .  `[Delphi]``[FPC]`单元测试函数，包括模拟和存根.

* [OpenCTF](http://openctf.sourceforge.net) .  Embarcadero Delphi的测试框架附件，它自动检查Forms（或DataModules）中的所有组件.  它提供了一种简单的方法来为大型项目构建自动质量检查，其中许多组件必须通过重复测试.  OpenCTF基于DUnit开源测试框架，并通过专门的测试类和辅助函数进行扩展.

* [DelphiUIAutomation](https://github.com/jhc-systems/DelphiUIAutomation) .  `[Delphi]`包装MS UIAutomation库的Delphi类.  DelphiUIAutomation是一个基于Win32自动化富客户端应用程序的框架（特别是使用Delphi XE5进行测试）.  它是用Delphi XE5编写的，不需要使用脚本语言.  它提供了一致的面向对象的API，隐藏了Microsoft的UIAutomation库和Windows消息的复杂性.


## Debugging / error handling ##

* [Delphi LeakCheck](https://bitbucket.org/shadow_cs/delphi-leakcheck) .  `[Delphi]`用于检查DUnit和DUnit2测试中内存泄漏的免费代码库.  支持Delphi XE-XE7.

* [FastMM](#memory-managers) .  提供强大的内存泄漏/损坏检测工具.

* [JclDebug (part of Project JEDI)](https://github.com/project-jedi/jcl/blob/master/jcl/source/windows/JclDebug.pas) .  `[Delphi]``[FPC]`跟踪，MAP文件解析器，异常报告生成，异常堆栈跟踪.


## Utilities ##
*此处允许免费的非开源产品.*


## RAD Studio IDE plugins/wizards

* [Delphi IDE theme editor / Delphi IDE Colorizer](https://github.com/rruz/delphi-ide-theme-editor) .  用于更改几个Object Pascal IDE的IDE颜色突出显示的工具，如Delphi（RAD Studio），Appmethod，Lazarus和Smart Mobile Studio.  DITE支持Delphi 5-7,2005-2010，XE-XE8，Appmethod 1.13-1.14，Lazarus v1.0.1.3和Smart Mobile Studio IDE v1.1.2.17.  Delphi IDE Colorizer（DIC）是一个插件，允许自定义RAD Studio IDE和Appmethod工作区的外观.

* [DDevExtensions](http://andy.jgknet.de/blog/ide-tools/ddevextensions) .  通过添加一些新的生产力功能来扩展Delphi / C ++ Builder IDE
// *Many useful IDE tweaks, must have.*

* [VCL Fix Pack](http://andy.jgknet.de/blog/bugfix-units/vclfixpack-10) .  Delphi单元，通过修补原始函数在运行时修复VCL和RTL错误.  如果您想在应用程序中修复所有IDE Fix Pack，则可以使用此单元.  将单元添加到项目中（Delphi和C ++ Builder）会自动安装可用于Delphi / C ++ Builder版本的修补程序.
// * Delphi / C ++ 6..2009的实际值*

* [IDE Fix Pack](http://andy.jgknet.de/blog/ide-tools/ide-fix-pack) .  收集RAD Studio IDE，Win32 / Win64编译器和Win32调试器的非官方错误修复和性能优化.  IDE Fix Pack是RAD Studio 2009-XE6的IDE插件，可在运行时修复IDE错误.  所有更改都在内存中完成.  磁盘上没有文件被修改.  除了编译速度更快之外，您的项目都没有被修改或受益于IDE修订包.  只有IDE才能获得修复和优化.
 // *支持自2007年以来的所有RAD Studio版本.删除了EMBT多年未修复的许多烦人的错误.  好极了！*

* [GExperts](https://sourceforge.net/projects/gexperts) .  通过向IDE添加多个功能来构建免费工具集，以提高Delphi和C ++ Builder程序员的工作效率.  GExperts是作为开源软件开发的，我们鼓励用户为项目做出贡献.  Grep搜索并替换支持的unicode文件，DFM等;  自动重命名组件，插入文本宏，打开最近的文件;  使用自定义附加文件列表轻松备份项目;  保留最喜欢文件的嵌套列表以便快速访问;  跟踪项目中单元之间的依赖关系;  快速跳转到当前单位的任何程序;  还有更多......

* [CnWizards](https://github.com/cnpack) .  Delphi / C ++ Builder / CodeGear RAD Studio的免费插件工具集，可提高开发效率.

* [Delphi Package Installer (DelphiPI)](https://bitbucket.org/idursun/delphipi) .  帮助您将组件安装到Delphi IDE的工具.  DelphiPI自动解析包之间的依赖关系，编译，安装和添加IDE的源路径.

* [ResEd](https://github.com/chaosben/theunknownones) .  Delphi 2005,2006,2007,2009,2010和XE专家.  此专家用于编辑链接到活动项目的资源文件（.res; .resx）.  它将自动搜索所有{$ R xyz.res}行，并为它们打开/创建资源文件.  专家在View下的Delphi菜单中注册.

* [Parnassus Bookmarks](https://parnassus.co/delphi-tools/bookmarks). IDE plugin that extends bookmark functionality.

* [DelphiSettingManager](https://github.com/Arvur/DelphiSettingManager) .  Delphi的多个IDE配置文件（最多XE6）.  允许为不同的项目安装同一组件的多个版本或不同的组件集.

* [Delphinus](https://github.com/Memnarch/Delphinus) .  新的Packagemanager在Delphi XE和更新版本上运行，并使用Gi​​thub作为后端来提供软件包.

* [Parnassus Bookmarks](https://parnassus.co/delphi-tools/bookmarks). IDE plugin that extends bookmark functionality.

* [TestInsight](https://bitbucket.org/sglienke/testinsight/wiki/Home) .  单元测试Delphi的IDE插件.  它支持从XE到10 Seattle的所有版本.  支持DUnit，DUnit2，DUnitX框架.

* [Delphi IDE Explorer](https://github.com/DGH2112/Delphi-IDE-Explorer) .  向导/专家/插件，允许您浏览IDE的内部字段，方法，属性和事件.
// *主要对IDE专家的开发人员有用*

* [Multi-RAD Studio IDE Expert Manager](http://www.davidghoyle.co.uk/WordPress/?page_id=1361) .  应用程序用于在机器上编辑所有版本的RAD Studio（以及旧的Delphi和C ++ Builder）中的已安装专家.

* [OTA Interface Search](https://github.com/DGH2112/OTA-Interface-Search) .  应用程序有助于查找Open Tools API（OTA）接口，方法和属性，并了解如何获取接口的接口或方法/属性.

* [AutoSave](https://github.com/DGH2112/Auto-Save) .  专家定期自动保存所有打开的已修改IDE文件.

* [Browse and Doc It](http://www.davidghoyle.co.uk/WordPress/?page_id=872) .  插件允许您从IDE中记录和浏览代码.

* [Integrated Testing Helper](http://www.davidghoyle.co.uk/WordPress/?page_id=874) .  Delphi和RAD Studio的插件，允许您在编译项目之前和之后运行命令行应用程序.  它还提供了将项目文件压缩到每个编译/构建的存档中的能力，并管理应用程序的版本信息.

* [Project Magician](https://www.uweraabe.de/Blog/2018/05/17/keep-your-project-files-clean-with-project-magician) .  用于高级项目选项操作的向导.

* [Selective Debugging](http://www.uweraabe.de/Blog/2015/05/08/selective-debugging/) .  允许调整将使用其调试版本的单元的向导.

* [MMX Code Explorer](https://www.mmx-delphi.de) .  功能丰富的生产力增强插件.  包括重构，类浏览器，高级编辑，metrict等等.

* [FormResource](http://chapmanworld.com/2017/03/22/formresource-a-free-delphi-component-for-organizing-product-dependencies) .  有助于将各种数据存储为表单资源的向导.

* [Delphi Library Helper](https://github.com/littleearth/delphi-library-helper) 帮助Delphi开发人员配置库文件夹的工具.

* [Mobile Image Creator](https://github.com/littleearth/mobile-image-creator)  为Delphi移动应用程序创建图标和启动器映像（Firemonkey）.  这是由Mobile Gfx创建的一个分支 [Thomas Grubb of RiverSoftAVG](http://riversoftavg.com/blogs/index.php/2014/02/03/creating-icons-and-launchers-for-delphi-mobile-applications/).

* [Delphi-Adb-WiFi](https://github.com/ms301/Delphi-Adb-WiFi) .  RAD Studio插件，允许在Android设备上启动和调试，无需通过USB连接到计算机.  适用于WiFi.

* [RADSplit](https://github.com/LaKraven/RADSplit) .  适用于RAD Studio的可停靠分屏编辑器（Delphi和C ++ Builder）


## Plugins for other IDE's

* [Delphi IDE theme editor / Delphi IDE Colorizer](#rad-studio-ide-pluginswizards) .  支持Appmethod，Lazarus和Smart Mobile Studio.


## Documentation

* [SynProject](https://github.com/synopse/SynProject) ([docs](http://synopse.info/fossil/wiki?name=SynProject) ）.  用于代码源版本控制和Delphi项目自动化文档的工具.

* [PasDoc](https://sourceforge.net/projects/pasdoc) .  `[Delphi]``[FPC]`ObjectPascal（FreePascal和Delphi）的文档工具源代码.  文档由源代码中的注释生成.  可用的输出格式有HTML，HtmlHelp，LaTeX，latex2rtf，simplexml.  将来可能会添加更多输出格式.

* [DIPasDoc](http://www.yunqa.de/delphi/products/pasdoc/index) .  `[Delphi]``[FPC]`从Pascal源代码文件中的注释生成HTML文档.  它输出可浏览的帮助作为标准HTML文件或可自定义的MS HTML帮助项目.


## Code check/review, debug

* [GpProfiler2017](https://github.com/ase379/gpprofile2017) .  `[Delphi]`用于Delphi XE及更高版本的源代码检测分析器.  其他叉子支持旧版本.

* [SamplingProfiler](https://www.delphitools.info/samplingprofiler) .  `[Delphi]`用于Delphi 5到32位Delphi XE4的性能分析工具.  它的目的是帮助找到瓶颈，即使是在全速运行的最终优化代码中也是如此.

* [Delphi Code Coverage](https://sourceforge.net/projects/delphicodecoverage) .  `[Delphi]`Delphi的简单代码覆盖率工具，可根据详细的MAP文件创建代码覆盖率报告.

* [Pascal Analyzer](http://www.peganza.com/products_pal.html)  （免费精简版）.  `[Delphi]`Pascal Analyzer，简称PAL，解析Delphi或Borland Pascal源代码.  它构建大型内部标识符表，并收集其他信息，如子程序之间的调用.  解析完成后，会生成大量报告.  这些报告包含大量有关源代码的重要信息.  此信息将帮助您更好地理解源代码，并帮助您生成更高质量和可靠性的代码.

* [madExcept](http://madshi.net/madExceptShop.htm) .  `[Delphi]`madExcept旨在帮助您找到软件中的错误.  每当程序中出现崩溃/异常时，madExcept将自动捕获，分析，收集大量有用信息，并为最终用户提供向您发送完整错误报告的可能性.  madExcept还能够为您找到内存泄漏，资源泄漏和缓冲区溢出.
// **免费**无源**仅供非商业用途（仅限） [conditions](http://help.madshi.net/License.htm) .  可以作为`madCollection`安装程序的一部分下载（你需要安装`madExcept`项）.  相当好记录.*

* [delphiunitsizes](https://github.com/VilleKrumlinde/delphiunitsizes) .  `[Delphi]`用于在Delphi可执行文件中显示每个单元大小的工具.  显示Delphi exe文件中包含的每个单元的大小.  它还显示单元中每个符号（类，方法，过程等）的大致大小.

* [MapFileStats](https://www.delphitools.info/other-tools/mapfilestats) .  `[Delphi]`提供.MAP文件（任何Delphi版本至少至Delphi XE5）的简单二进制大小统计信息的工具.

* [Spider](https://github.com/yavfast/dbg-spider) .  `[Delphi]`Delphi应用程序的实时分析器

* [AsmProfiler](https://github.com/andremussche/asmprofiler) .  `[Delphi]`全跟踪32位分析器（仪器和采样），用Delphi编写和一些程序集

## Setup

* [Lazy Delphi Builder](https://bitbucket.org/tdelphi/lazy-delphi-builder-downloads) .  为Delphi构建工具.  从具有所有依赖关系的源重新编译项目/包，而无需乱搞配置.  从源代码快速（重新）安装组件到IDE，无需更改库路径.
 // *强大的自动化工具.  免费软件但不是开源软件*

* [Inno Setup](http://www.jrsoftware.org/isinfo.php) .  Windows程序的免费安装程序.  Inno Setup于1997年首次推出，今天在功能集和稳定性方面与众多商业安装商相媲美甚至超越.

* [WinSparkle](https://winsparkle.org) 和它 [Delphi wrapper](https://github.com/jkour/neSparkleComponent) .  WinSparkle是一个易于使用的Windows开发人员软件更新库.  WinSparkle的灵感来自于最初由Andy Matuschak创建的Sparkle框架，后者成为macOS上软件更新的事实标准.

* [Silverpoint MultiInstaller](http://www.silverpointdevelopment.com/multiinstaller/index.htm) .  Embarcadero Delphi和C ++ Builder的多组件包安装程序，它是为了简化IDE上的组件安装而创建的.


## Other


* [Delphi Preview Handler](https://github.com/RRUZ/delphi-preview-handler) .  Windows Vista，7和8的预览处理程序，允许您在编辑器中使用语法高亮显示而无需在编辑器中打开来读取对象pascal，C ++和汇编代码

* [Delphi Dev. Shell Tools](https://github.com/RRUZ/delphi-dev-shell-tools) .  Windows shell扩展，包含Object Pascal Developers（Delphi，Free Pascal）的有用任务.

* [Delphi.gitignore](https://github.com/github/gitignore) .  .dit的.gitignore模板.  拉撒路还有一个.

* [OmniPascal](http://omnipascal.com) .  使Delphi和Free Pascal开发人员能够使用现代编辑器编写和维护代码的项目 [Visual Studio Code](https://code.visualstudio.com).

* [Delphi Unit Tests](https://bitbucket.org/NickHodges/delphi-unit-tests) .  Delphi库的单元测试集.  鼓励Delphi社区成员分叉存储库，添加测试并创建拉取请求.  特别鼓励Embarcadero员工在使用官方Delphi构建版本运行的内部测试中添加测试.

// *免费**无源**仅供非商业用途（仅限） [conditions](http://help.madshi.net/License.htm) .  可以作为`madCollection`安装程序的一部分下载（你需要安装`madExcept`项）.  相当好记录.*

* [Chet - C Header Translator for Delphi](https://github.com/neslib/Chet) .  Chet是一个.h-to-.pas翻译器，由libclang为Delphi提供支持.  使用Clang编译器解析头文件，从而产生更准确的翻译，需要更少的手动调整.


## License ##

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0)
