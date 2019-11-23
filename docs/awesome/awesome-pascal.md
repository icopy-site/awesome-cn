<div class="github-widget" data-repo="Fr0sT-Brutal/awesome-pascal"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Pascal [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 精选的Delphi，FreePascal和其他* Pascal框架，库，资源和精美内容的精选列表.  受到令人敬畏的东西的启发.

**Note that only open-source projects are considered. Dead projects (not updated for 3 years or more) must be really awesome or unique to be included.**
随时通过评论或请求请求来建议其他缺少的好项目.

这个很棒的收藏也可以在 [Delphi.ZEEF.com](https://delphi.zeef.com/anton.frost)

 ：惊叹号：**关于编译器兼容性的注意事项**.  根据项目描述，所有项目都有编译器/语言方言兼容性标记.  没有检查与未正式支持的编译器的真正兼容性.  通常，可以对代码进行与不支持的编译器/语言方言一起使用的修改，但是可能会有例外.


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

----------------------------------------------------------------------------------------------------------------

## General Libraries ##
*大型通用库*

* [JCL](https://github.com/project-jedi/jcl). `[Delphi]` `[FPC]` Set of thoroughly tested and fully documented utility functions and non-visual classes which can be instantly reused in your Delphi and C++ Builder projects. The library is grouped into several categories such as Strings, Files and I/O, Security, Math and many, many more.

* [JVCL](https://github.com/project-jedi/jvcl) .  “ Delphi”库，由“ JEDI项目”成员开发了600多个Delphi组件.
// * GUI，算法，类，API标头等*

* [Alcinoe](http://sourceforge.net/projects/alcinoe) ([mirror at GH](https://github.com/Zeus64/alcinoe) ）.  Delphi的可视组件和非可视组件库.
 // *网络：FTP / Http / NNTP / POP3 / SMTP，ISAPI，WinInet Http / FTP客户端；  DB：Firebird / MySQL / SQLite3 / Memcached / MongoDb / SphinxQL；  XML / JSON解析器；  ZLIB;  密码：AES，河豚，MD5，SHA，安全密钥MD5 / SHA；  opengl视频播放器；  FireMonkey控件；  其他：自平衡二叉树，表达式评估器*

* [Fundamentals Code Library](http://sourceforge.net/projects/fundementals) （被遗弃的是，最近的分叉是 [here](https://github.com/fundamentalslib/fundamentals4)  -尽管单位设置略有不同，f.ex.  没有XML.  最新主要版本5 [here](https://github.com/fundamentalslib/fundamentals5) ）.  Delphi / FreePascal代码单元的`[Delphi]``[FPC]`集合.  包括Unicode，字符串，数据结构，套接字和数学的库.
 // *实用工具：ZLIB压缩；  JSON;  XML;  ProtocolBuffers;  Unicode例程；  数据结构;  哈希：XOR，CRC，Adler，MD5，SHA，安全密钥MD5 / SHA等；  网络：通过SSL3 / TLS1.0 / TLS1.1 / TLS1.2（完全本机）阻止TCP客户端/服务器，HTTP（S）；  SQL解析器  比特币MtGox客户端;  Blaise脚本引擎；  密码：AES，DES，FUNE，RC2，RC4，RSA，Diffie-Hellman；  数学：矩阵，复数，统计量，大量*

* [Spring4D](https://bitbucket.org/sglienke/spring4d) .  “ [Delphi]” Embarcadero Delphi 2010及更高版本的开源代码库.  它由许多不同的模块组成，这些模块包含基类库（通用类型，基于接口的集合类型，反射扩展）和依赖项注入框架.  包括加密库.
 // *使用泛型并基于IEnumerable的集合和其他容器，可能比RTL类似物更准确，功能更丰富；  加密：CRC，DES，MD5，SHA;  文件工具等*

* [TheUnknownOnes](https://github.com/chaosben/theunknownones) .  `[Delphi]`适用于几乎所有用途的大量类，组件，实用程序.  几乎没有文档记录，但似乎不是最新的.

* [CNVCL](https://github.com/cnpack/cnvcl) .  [Delphi] CnPack组件包.  大量的视觉组件，类和实用程序.  // *很多有用的东西；  文档和注释主要为中文*

* [mORMot](https://github.com/synopse/mORMot) .  Delphi 6及更高版本或FPC 2.7的客户端服务器ORM / ODM SOA MVC框架.  直接SQL / NoSQL数据库访问，对象上的ORM / ODM，通过高性能HTTP服务器，MVC / MVVM网站上的接口的RESTful ORM和SOA服务，测试（包括模拟和存根），日志记录，加密，压缩，庞大的文档.

* [MARS - Curiosity](https://github.com/andrea-magni/MARS) .  `[Delphi]`Delphi REST库.  纯REST方法，一种熟悉的Delphi风格的标准概念（包括基于组件的客户端库）.  已知兼容性：从XE到10 Seattle的Delphi版本.  某些功能需要FireDAC.

* [ADAPT](https://github.com/LaKraven/ADAPT) .  “ [Delphi]”高级开发人员异步编程工具包，基础库，旨在提供给您的项目核心，以提供极其强大的多线程（和线程安全）功能.  事件引擎-一个非常强大的系统，用于生成多线程，异步和事件驱动程序.  泛型集合-高效的集合类型（列表，树，地图等）.  数学库-用于单位换算，特殊计算和其他有用的数学例程的库.  打包引擎-Streamables引擎的扩展，支持将文件打包在一起（一种VFS）.  共享流库-100％线程安全的流类（也可以接口）允许从多个线程进行读/写.  流处理库-使使用流更加容易！  处理删除，插入，读取和写入数据.

* [Redux Delphi](https://github.com/pierrejean-coudert/ReduxDelphi) .  Delphi应用程序的可预测状态容器，该容器使用单向数据流.  受ReduxJS启发.  带有不可变的通用列表.

* [GrijjyFoundation](https://github.com/grijjy/GrijjyFoundation) .  在其他Grijjy存储库中使用的`[Delphi]`基础类和实用程序.
// * BSON / JSON，IOCP / EPOLL套接字，套接字池，HTTP，HTTP / 2，OpenSSL，ProtocolBuffers.*

* [unRxLib](http://www.micrel.cz/RxLib/dfiles.htm) .  “ Delphi”努力保持RxLibrary（包含60多个组件的库）为实际状态.

* [QuickLib](https://github.com/exilon/QuickLib) .  Delphi / freepascal（Windows / Linux）库，用于快速开发和跨平台支持（Json Serialize，AutoMapper，Chronometer，线程，列表，配置，控制台服务等）.

* [KOL](https://sourceforge.net/projects/kolmck) .  `[Delphi]``[FPC]`（[KOL-CE](https://sourceforge.net/p/kol-ce)  Delphi（和FPC）的主要对象库-使应用程序小巧，功能强大.  该库是免费软件和开放源代码.  MCK是使用KOL库在Delphi环境中用于VISUAL项目开发的镜像类工具包.


## Multimedia ##


## Audio

* [Audio Tools Library](http://mac.sourceforge.net/atl) .  `[Delphi]`用于处理许多音频格式的文件信息.
// **自2005年起废弃.**

* [Delphi ASIO & VST Project](http://sourceforge.net/projects/delphiasiovst) .  “ [Delphi]”框架，用于使用ASIO接口和VST插件编写应用程序.  它带有无数的DSP算法，所有这些算法都在数十个示例中得到了证明.
// *最近不太活跃，但是中继线处于可用状态*

* [NewAC - New Audio Components](http://code.google.com/p/newac) （废弃，GH上的货叉清单 [here](https://github.com/search?l=Pascal&o=desc&q=newac&s=updated&type=Repositories) ）.  `[Delphi]`旨在帮助您的Delphi程序执行不同的声音处理任务.  使用NewAC，您可以播放以多种格式存储的音频（wav，Ogg Vorbis，FLAC，Monkey Audio，WavPack，MP3，Windows WMA，DTS，AC-3（杜比环绕声），VOB（DVD文件））.
// *播放，录制，标签读/写，一些音频编辑任务和转换*

* [Audorra](https://sourceforge.net/projects/audorra) .  `[Delphi]``[FPC]`用于Delphi和Freepascal的数字音频库.  使用灵活的插件架构，它允许您交换音频后端（例如WaveOut，OpenAL），添加协议类（例如文件，http）和解码器.


## Video

* [DSPack](https://code.google.com/p/dspack) （被遗弃的主动叉是 [here](https://github.com/micha137/dspack-continued-mirror-for-delphinus) ）.  [Delphi]使用MS Direct Show和DirectX技术编写多媒体应用程序的一组组件和类.

* [Delphi-OpenCV](https://github.com/Laex/Delphi-OpenCV) .  `[Delphi]`OpenCV库头文件在Delphi中的翻译
// *包括FFMPEG标头*

* [FFmpeg Delphi/Pascal Headers](http://www.delphiffmpeg.com/headers) .  `[Delphi]``[FPC]`FFMPEG标头的开源翻译.

* [PasLibVlc](http://prog.olsztyn.pl/paslibvlc) .  VideoLAN libvlc.dll和基于VideoLAN的Delphi / FreePascal的VCL播放器组件的接口[[Delphi]`[FPC]`

* [fevh264](https://github.com/dpethes/fevh264) .  `[FPC]`基准h.264编码器.  支持Windows和Linux


## Graphic

* [Graphics32](https://github.com/graphics32/graphics32) .  `[Delphi]``[FPC]`设计用于在Delphi，Kylix和Lazarus上进行快速的32位图形处理.  它针对32位像素格式进行了优化，可提供像素和图形基元的快速操作，并且在大多数情况下，Graphics32优于标准TCanvas类.  每像素访问速度快将近一百倍，绘图线速度快将近2-5倍.

* [GraphicEx](https://github.com/mike-lischke/GraphicEx) .  Delphi的Graphics.pas的[Delphi]附录，使您的应用程序可以加载许多常见的图像格式.  该库主要用于将图像作为背景（按钮，表单，工具栏）和纹理（DirectX，OpenGL）加载，或者用于图像浏览和编辑目的，只要您不需要保存图像即可.

* [Vampyre Imaging Library](http://imaginglib.sourceforge.net) .  `[Delphi]``[FPC]`跨平台本机对象Pascal（Delphi和Free Pascal）图像加载，保存和操作库.

* [CCR-EXIF](https://code.google.com/p/ccr-exif) （似乎已废弃，GH上的货叉清单 [here](https://github.com/search?l=Pascal&o=desc&q=ccr-exif&s=updated&type=Repositories) ）.  “ Delphi”库，用于从JPEG，TIFF和PSD图像读取和写入Exif，IPTC和XMP元数据.

* [KIcon](http://www.tkweb.eu/en/delphicomp/kicon.html) .  `[Delphi]``[FPC]`如果需要对图标（或更好的图标文件* .ico）进行比仅查看更复杂的操作，则此组件有意义.  完整的PNG图标图像支持，正确的渲染，带有Alpha通道的图标.

* [Delphi Twain](http://www.kluug.net/delphitwain.php) .  `[Delphi]``[FPC]`该库使您可以轻松访问来自Delphi和Lazarus的扫描功能.

* [Synopse PDF](https://github.com/synopse/SynPDF) .  `[Delphi]``[FPC]`用于Delphi的功能齐全的开源PDF文档创建库，嵌入在一个单元中.  适用于Win32和Win64平台的纯Delphi代码，从Delphi 5到Delphi 10.3 Rio（以及最新版本的FPC）.

* [PowerPDF](https://github.com/TurboPack/PowerPDF) .  [Delphi] VCL组件可直观地创建PDF文档.  与Forms一样，您可以在Delphi或C ++ Builder IDE上轻松设计PDF文档.

* [IGDI+](https://sourceforge.net/projects/igdiplus) .  `[Delphi]`免费的开放源代码库允许以自然的Delphi友好代码轻松快速地实现复杂的GDI +应用程序.

* [GLScene](https://sourceforge.net/projects/glscene) .  [Delphi]`[FPC]`基于OpenGL的3D库，用于Delphi，C ++ Builder和Lazarus.  它提供了可视化的组件和对象，允许以简单，轻松而强大的方式描述和渲染3D场景.  GLScene不仅是OpenGL包装程序或实用程序库，它还已经发展成为考虑到“快速应用程序开发”的通用3D引擎的基础类集.  GLScene允许您快速设计和渲染3D场景，而无需学习OpenGL的复杂性.如果您知道如何设计TForm，则可以轻松掌握GLScene的基本操作.  该库附带了大量演示，展示了易用性，并且演示RAD并没有牺牲CPU / GPU的功能.


* [Andorra 2D](http://sourceforge.net/projects/andorra) .  `[Delphi]``[FPC]`用于Delphi和Lazarus的新一代2D引擎.  安道尔2D能够通过图形插件使用DirectX或OpenGL.  安道尔2D以非常模块化的方式构建，并且易于使用.

* [Transparent-canvas](https://github.com/vintagedave/transparent-canvas) .  Delphi VCL / Windows项目，用于绘制半透明的alphablended图形.  它提供类似于TCanvas的类.

* [Fully-justified-text](https://github.com/vintagedave/fully-justified-text) .  Delphi VCL / Windows项目，用于文本输出，允许使用多种选项打印完全对齐的文本.

* [AsciiImage](https://github.com/Memnarch/AsciiImage) .  Alexander Benikowski基于Delphi的Delphi的AsciiImage-Implementation，基于Charles Parnot的AsciiImage.  阅读更多 [his article](http://cocoamine.net/blog/2015/03/20/replacing-photoshop-with-nsstring).
// *从ASCII像素图创建可缩放的单色图像*

* [PngComponents](https://bitbucket.org/uweraabe/pngcomponents) .  [Delphi] PngComponents是一组组件，允许您在应用程序中包含实际的PNG文件.  PNG文件本身并不能带来巨大的优势，但是它们对alpha通道的支持确实具有很大的魅力.

* [AggPasMod](https://github.com/CWBudde/AggPasMod) .  `[Delphi]`现代化的Pascal反谷物几何.  该项目基于AggPas，而AggPas本身又是基于“反谷物几何”，该项目提供对最新Delphi版本（XE和更高版本）的支持，并包含一些帮助程序类（VCL组件和FireMonkey接口）.  2D矢量图形库.  基本上，您可以将AggPas视为一个渲染引擎，该引擎根据某些矢量数据在内存中生成像素图像.  但是，当然，AGG可以做的还不止这些.
// *矢量图形库，呈现SVG等*

* [delphi-shader](https://github.com/WouterVanNifterick/delphi-shader) .  “ Delphi”数百种图形效果，以及一个以纯Delphi代码提供GLSL功能的库.  该项目产生具有一百多个实时图形效果的可执行文件.  所有这些都是100％Pascal的实现，无需使用外部库或硬件加速.

* [dglOpenGL](https://github.com/SaschaWillems/dglOpenGL) .  `[Delphi]``[FPC]`Delphi / Pascal OpenGL标头转换.

* [DelphiZXingQRCodeEx](https://github.com/MichaelDemidov/DelphiZXingQRCodeEx) .  `Delphi`` [FPC]`来自开放源代码条形码图像处理库ZXing的QR Code生成功能的Delphi / Lazarus端口.

* [ZXing.Delphi](https://github.com/Spelt/ZXing.Delphi) .  Delphi XE到10.2 Tokyo的“ Delphi”本机对象Pascal库，它基于著名的开源条形码扫描库ZXing（斑马线）.  它针对所有FireMonkey移动平台，从v3.1开始，它还完全支持Windows VCL应用程序（不依赖FMX.Graphics单元）.

* [QuickImageFX](https://github.com/exilon/QuickImageFX) .  Delphi库，用于简化图像加载/保存，转换和转换.  加载/保存png，jpg，gif和bmp.  从不同的资源获取图像：文件，流，http，图像列表，关联的Windows图标，可执行文件图标等.旋转，翻转，灰度和许多其他转换.

* [NativeJpg](https://code.google.com/p/simdesign) .  `[Delphi]`完全面向对象的Pascal实现，允许读取和写入Jpeg文件.  您可以使用此软件从文件或流读取和写入Jpeg图像.  它支持基线和渐进式Jpeg，对元数据的支持以及所有可能的无损操作.

* [OpenGL Pascal Toolkit](https://github.com/daar/GLPT) .  `[FPC]`易于使用的本地pascal工具包，允许以独立于平台的方式创建和管理OpenGL上下文.

* [BGRAbitmap](https://github.com/edivando-fpc/BGRABitmap) .  `[Delphi]``[FPC]`绘制具有透明度的例程，并使用Lazarus进行抗锯齿.  还提供各种转换.  这些例程允许处理BGRA格式或RGBA格式的32位图像（取决于平台）.

* [Clipper](http://angusj.com/delphi/clipper.php) .  `[Delphi]`库执行线和面裁剪-相交，并集，差和异或以及线和面偏移


## Game dev ##

* [RecastNavigation](https://github.com/Kromster80/RecastNavigationDelphi) .  `[Delphi]`游戏的导航网格构建工具集.  重铸随附了Detour，路径查找和空间推理工具包.  您可以将任何导航网格与Detour一起使用，但是使用Recast生成的数据当然非常合适.  这是用C ++编写的原始RecastNavigation的端口.

* [Kraft Physics Engine](https://github.com/BeRo1985/kraft) .  `[Delphi]``[FPC]`开源对象Pascal物理引擎库，可以在3D游戏中使用.  兼容：Delphi 7-XE7（但不适用于Android和iOS目标），FreePascal&gt; = 2.6.2（几乎所有FPC支持的目标，包括Android和iOS）

* [ZenGL](https://github.com/andru-kun/zengl) .  `[Delphi]`[FPC]`用Pascal编写的OpenGL跨平台游戏开发库，旨在提供渲染2D图形，处理输入，声音输出等所需的功能.
// *最近未更新，但是可以正常*

* [Asphyre aka Platform eXtended Library (PXL)](https://sourceforge.net/projects/asphyre) .  `[Delphi]``[FPC]`跨平台框架，用于开发2D / 3D视频游戏，交互式和科学应用程序.  它可以帮助开发人员进行数学，硬件控制，资源管理，显示实时图形和文本，处理用户输入和网络通信功能.

* [CrystalPathFinding](https://github.com/d-mozulyov/CrystalPathFinding) .  `[Delphi]`[FPC]`简单有效的开放源代码库，旨在通过算法A * / WA *对基于4（简单），8（对角线/ diagonalex）图块的地图进行最短路径搜索或6个（六边形）邻居.

* [Allegro-Pas](https://sourceforge.net/projects/allegro-pas) ([GitHub](https://github.com/niuniomartinez/allegro-pas) ）.  “ [Delphi]``[FPC]`包装器将Passcal / Delphi使用Allegro游戏库.

* [Castle Game Engine](https://github.com/castle-engine/castle-engine) .  `[FPC]`完整的Pascal游戏引擎.  具有许多图形效果和基于X3D的场景图的跨平台3D和2D游戏引擎.

* [TileEngine](http://www.tilengine.org). ([GitHub](https://github.com/turric4n/PascalTileEngine) ）[[Delphi]`[FPC]`OOP Pascal包装程序和Tilengine 2D复古图形引擎的绑定.  Tilengine是跨平台的2D图形引擎，用于创建带有图块图，子画面和调色板的经典/复古游戏.  其基于scanline的渲染算法使栅格效果成为一项核心功能，许多在真正的2D图形芯片上运行的游戏都使用该技术.

* [SDL2](http://www.freepascal-meets-sdl.net/) ([GitHub](https://github.com/ev1313/Pascal-SDL-2-Headers) ）.  `[Delphi]``[FPC]`Pascal SDL 2标头.  Simple DirectMedia Layer是一个跨平台开发库，旨在通过OpenGL和Direct3D提供对音频，键盘，鼠标，操纵杆和图形硬件的低级访问.

* [SFML](https://github.com/CWBudde/PasSFML) .  `[Delphi]``[FPC]`Pascal SFML标头.  SFML为您的PC的各种组件提供了一个简单的界面，以简化游戏和多媒体应用程序的开发.  它由五个模块组成：系统，窗口，图形，音频和网络.  目前支持Delphi和FPC / Lazarus.  但是，由于编译器与Delphi编译器不兼容（已通过变通办法解决），目前建议使用FPC.

* [pasvulkan](https://github.com/BeRo1985/pasvulkan) .  [Delphi]`[FPC]`Vulkan标头生成器，OOP风格的API包装器，框架和面向对象Pascal的基于Vulkan的预期游戏引擎.

* [DarkGlass](https://github.com/chapmanworld/DarkGlass) .  “ [Delphi]” DarkGlass是使用Delphi编写的通用游戏引擎.

* [JEDI-SDL](https://sourceforge.net/projects/jedi-sdl) .  JEDI的SDL的[Delphi]`[FPC]`Pascal标头.  与Delphi，Kylix，Free Pascal，Gnu Pascal和TMT Pascal一起使用.


## Communications ##


## Network
*套接字通信，网络协议，编码等*

* [Internet Component Suite](http://www.overbyte.be/frame_index.html). `[Delphi]` Asynchronous-based library composed of various Internet components and applications. Clients/servers for TCP, UDP, raw sockets, FTP, SMTP, POP3, NNTP, HTTP, Telnet and more. Supports SSL and TLS with the help of OpenSSL. Also includes Mime Decoder, SHA1/MD4/MD5 hashes, DES encryption.

* [Indy](https://github.com/IndySockets/Indy) .  Delphi，C ++ Builder，Delphi.NET和FreePascal的`[Delphi]``[FPC]`网络组件
 // *基于阻塞套接字和线程的多合一网络库.  自2006年以来已包括在RAD Studio的默认安装中.*

* [Ararat Synapse](https://sourceforge.net/p/synalist) .  用于Delphi，C ++ Builder，Kylix和FreePascal的Pascal TCP / IP库.  通过阻塞（同步）套接字或受限的非阻塞模式来处理网络通信.  该项目不使用异步套接字！  该项目包含简单的低级非可视对象，可实现最简单的编程而不会出现问题（不需要多线程同步，不需要Windows消息处理，...）非常适合命令行实用程序，可视项目，NT服务，...
 // * TCP，UDP，ICMP，RAW;  ICMP，DNS，SMTP，HTTP，SNMP，NTP，FTP，LDAP，NNTP，Telnet;  IPv6；  SOCKS代理；  SSL / TLS（通过OpenSSL或Windows CryptoApi）；  PING；  字符代码转码；  MIME编码和解码；  CRC16，CRC32，MD5和HMAC-MD5.*

* [Internet Professional](http://sourceforge.net/projects/tpipro2010) .  `[Delphi]`VCL组件集，可为Borland Delphi＆C ++ Builder提供Internet连接.  iPRO包括POP3，SMTP，NNTP，FTP，HTTP，即时消息和HTML查看器组件，以及用于低级套接字访问的组件.
 // *似乎已废弃，但包含相当多的功能集，包括ICMP，POP，SMTP，HTTP，NNTP，NTP，FTP，SMTP；  HTML解析器和查看器；  MIME实用程序；  Cookie，证书，缓存，加密等*

* [SynCrtSock](https://github.com/synopse/mORMot/blob/master/SynCrtSock.pas) .  `[Delphi]``[FPC]`具有几个套接字和HTTP客户端-服务器类，包括Windows下的基于http.sys的高性能服务器，以及新的线程池供电的套接字服务器.
// *还实现了Windows下的http.sys绑定和nix下的cURL绑定*

* [TML Messaging Suite](http://www.libtml.org/docs/libtml-pascal) .  `[Delphi]``[FPC]`网络消息库，用于快速开发可扩展和可扩展的接口.  基于对等标准协议 [BEEP (Blocks Extensible Exchange Protocol)](http://www.beepcore.org)，定义于 [RFC3080](https://tools.ietf.org/html/rfc3080) 和 [RFC3081](https://tools.ietf.org/html/rfc3081). libTML is suitable for many use cases 和 communication patterns. Equipped with a type safe data API, TML can transport hierarchical data structures fast 和 reliable.
// * libTML对象Pascal组件不仅是绑定到核心库的语言，而且是一整套非可视组件，可简化Embarcadero RAD Studio和Lazarus对libTML的使用.

* [DMVCFramework](https://github.com/danieleteti/delphimvcframework) .  `[Delphi]`Delphi中流行且功能强大的Web解决方案框架.

* [Delphi IOCP](https://github.com/ymofen/diocp-v5) .  `[Delphi]`基于Windows IOCP技术实现几个网络类.  套接字，HTTP，Ntrip服务器和客户端.
// *很好的文档记录和良好样式的代码，但仅中文.*

* [delphi-aws-ses](https://github.com/monde-sistemas/delphi-aws-ses) .  用于Delphi应用程序的Amazon Simple Email Service（AWS SES）库.

* [delphi-slackbot](https://github.com/monde-sistemas/delphi-slackbot) .  `[Delphi]`Delphi库，用于发送消息 [Slack](https://slack.com) 使用slackbot.

* [Kitto](https://github.com/EtheaDev/kitto). `[Delphi]` Allows to create Rich Internet Applications based on a data model that can be mapped onto any database. The client-side part uses ExtJS (through the ExtPascal library) to create a fully AJAX application, allowing you to build standard and advanced data-manipulating forms in a fraction of the time. Kitto is aimed at Delphi developers that need to create web application without delving into the intricacies of HTML, CSS, Javascript or learning to use a particular library such as ExtJS, yet it allows access to the bare metal if required.

* [Daraja Framework](https://github.com/michaelJustin/daraja-framework) .  [Delphi]`[FPC]`用于对象Pascal的轻量级HTTP服务器框架（Delphi 2009 + /免费Pascal 3.0）.  通过以下方式支持实施RESTful服务 [daraja-restful](https://github.com/michaelJustin/daraja-restful) 延期.

* [Alcinoe](#general-libraries) .  FTP / Http / NNTP / POP3 / SMTP，ISAPI，WinInet Http / FTP客户端.

* [Fundamentals Code Library](#general-libraries) .  通过SSL3 / TLS1.0 / TLS1.1 / TLS1.2（完全本机）阻止TCP客户端/服务器，HTTP（S）.

* [mORMot](#general-libraries) .  通过高性能HTTP服务器，MVC / MVVM网站上的接口提供RESTful ORM和SOA服务

* [SDriver](https://github.com/andrea-magni/SDriver) .  `[Delphi]`Delphi包装器 [Slack](https://slack.com) API.

* [Hprose for Delphi/Lazarus](https://github.com/hprose/hprose-delphi) .  `[Delphi]``[FPC]`高性能远程对象服务引擎.  它是一种现代，轻便，跨语言，跨平台，面向对象，高性能，远程动态通信中间件.  它不仅易于使用，而且功能强大.  这个项目是Hprose在Delphi / Lazarus的实现.

* [TelegAPI](https://github.com/ms301/TelegAPI) .  `[Delphi]`库，用于在Delphi中使用Telegram Messenger Bot API.

* [fp-telegram](https://github.com/Al-Muhandis/fp-telegram) .  `[FPC]`库，用于在FreePascal / Lazarus中使用Telegram机器人API.

* [DelphiZeroMQ](https://github.com/grijjy/DelphiZeroMQ) .  ZeroMQ Majordomo协议和CZMQ高级绑定的Delphi实现.

* [GrijjyFoundation](#general-libraries) .  IOCP / EPOLL套接字，套接字池，HTTP，HTTP / 2，OpenSSL，ProtocolBuffers.

* [Rest-Dataware-Componentes](https://github.com/Rest-Dataware/RDW-Componente) .  创建了[Delphi]`[FPC]`以促进创建CRUD的方式与我们为客户端/服务器数据库创建应用程序的方式相同.  使用REST DW，您不再需要担心通过Webservice创建SQL插入，删除，读取和执行方法.  只需添加一个RESTDataBase连接组件，然后添加一个RESTClientSQL组件，即可像以前一样使您的SQL解决方案完全发挥作用，并具有数据压缩和该语言可以提供的一切功能的现代REST / JSON技术的所有功能.

* [STOMP Client](https://github.com/danieleteti/delphistompclient) .  Embarcadero Delphi和FreePascal的`[Delphi]``[FPC]`STOMP客户端.  该项目可以使用INDY（Delphi）或Synapse（Delphi或FreePascal）.

* [delphiXero](https://github.com/littleearth/delphiXERO) .  用于Delphi的XERO云计费API.

* [BesaSoap](https://github.com/besasoftware/besasoap). `[Delphi]` The BesaSoap library is designed to help programmers develop faster and more native web service client applications. Represents C# or Java like native class support, nullable data types and custom attributes.

* [IndySoap](https://sourceforge.net/projects/indysoap) .  `[Delphi]`开源库，用于使用Delphi / CBuilder编译器实现Web服务.  尽管包括基于Indy的运输服务，但IndySoap与Indy的运输服务并不相关.

* [Fano Framework](https://fanoframework.github.io) .  用于现代Pascal编程语言的Web应用程序框架.  它用Free Pascal编写.

* [Internet Tools](#xmljsonyaml) .  XPath / XQuery / JSONiq / CSS / HTML;  在Windows / Linux / MacOSX / Android上执行HTTP / S请求的功能，受XSLT启发的网络抓取语言和自动更新类.

* [Delphi Cross Socket](https://github.com/winddriver/Delphi-Cross-Socket/) .  Delphi跨平台套接字库（中文）.  针对不同平台使用不同的IO模型：IOCP（Windows），KQUEUE（FreeBSD（MacOSX，iOS ...）），EPOLL（Linux（Linux，Android ...））.

* [ToroKernel](https://github.com/torokernel/torokernel) .  `[FPC]`这是一个库内核，它允许特别移植的freepascal应用程序在系统中单独运行.  Toro在用户的应用程序中进行编译，因此生成了一个可以在裸机上启动或作为现代管理程序（例如hyperv，kvm，qemu，firecraker）中的访客启动的二进制文件.  ToroKernel通过提供专用的API来解决微服务的开发.

* [Horse](https://github.com/HashLoad/horse) .  `[Delphi]`快速而简约的Web框架.  Horse允许轻松创建强大的RESTful服务器.  专注于微服务.

* [Bauglir WebSocket](https://github.com/MFernstrom/Bauglir-WebSocket-2) .  基于Ararat Synapse的WebSocket服务器/客户端实现.

* [Delphi-RabbitMQ](https://github.com/HeZiHang/Delphi-RabbitMQ). `[Delphi]` RabbitMQ driver for Delphi


## Serial port

* [Synaser](http://sourceforge.net/p/synalist/code/HEAD/tree/trunk/synaser.pas) .  `[Delphi]``[FPC]`库，用于阻止串行端口上的通信.  与Synapse中一样，它是非可视类，并且程序员界面与Synapse非常相似.

* [Async Professional](http://sourceforge.net/projects/tpapro) ([Newest](https://github.com/TurboPack/AsyncPro)  和维护的版本（仅适用于最新的编译器版本）.  `[Delphi]`用于Embarcadero Delphi，C ++ Builder和ActiveX环境的综合通信工具包.  它提供对串行端口，TAPI和Microsoft语音API（TTS /语音识别）的直接访问.  它支持传真，终端仿真，VOIP，RAS拨号等等.
 // *似乎已过时（2011年的最新更新），但适用于XE，在新版本中应易于使用.  该项目也非常详尽地记录在案.  第二个链接指向适用于最新编译器版本的适应版本.*

* [TComPort](https://sourceforge.net/projects/comport) .  Delphi / C ++ Builder串行通信组件.  通常，它很容易用于基本的串行通信目的.
// *自2011年以来似乎已被放弃*


## GUI ##
*视觉组件*


## Control packs
*大量的GUI控件*

* [Cindy components](http://sourceforge.net/projects/tcycomponents) .  `[Delphi]`包含71个组件的软件包：VCL控件（标签，按钮，面板，编辑，TabControls，StaticText），具有背景渐变，彩色斜角，墙纸，shadowText，字幕方向等功能.

* [Orpheus](http://sourceforge.net/projects/tporpheus) ([Newest](https://github.com/TurboPack/Orpheus)  和维护的版本（仅适用于最新的编译器版本）.  Borland Delphi＆C ++ Builder的[[Delphi]]屡获殊荣的UI工具包.  它包含超过120个组件，涵盖从数据输入到日历和时钟的所有内容.  其他值得注意的组件包括对象检查器，LookOut条和报告视图.
 // *高级编辑，组合框，网格+组件（反）序列化器.  GUI组件看起来有些过时，主题支持可能会受到限制.  程序包包含许多演示，但似乎没有可用的文档.  第二个链接指向适用于最新编译器版本的适应版本.*

* [KControls](http://www.tkweb.eu/en/delphicomp/kcontrols.html) .  `[Delphi]``[FPC]`控制组件.  编写所有控件的目的都是为了实现跨IDE兼容（Delphi / C ++ Builder VCL和Lazarus LCL）以及在Lazarus中跨平台兼容.
 // *最有用的是TKGrid，它具有可识别数据库的传统知识TKDBGrid-一种非常全面的网格实现，包括.  就地编辑.  还有十六进制编辑器，打印预览，编辑器，标签，按钮等.*

* [D.P.F Delphi Android](http://sourceforge.net/projects/dpfdelphiandroid) / [D.P.F Delphi iOS](http://sourceforge.net/projects/dpfdelphiios)  本机组件.  “ [Delphi]” DPF Delphi本机组件，100％的iOS性能和样式.  开发具有快速本机性能和本机样式的iPhone＆iPad＆iPod Touch应用程序.  使用原生的Android控件和服务.  快速的本机性能.  与FM VCL控件混合使用.  可以使用最新的Android控件和功能快速更新.

* [Essentials](https://github.com/TurboPack/Essentials) .  “ [Delphi]”包含用于Embarcadero Delphi和C ++ Builder的13个本机VCL控件.  控件包括下拉日历和计算器，上滚对话框，3-D标签，平铺背景，滚动消息，菜单按钮等.

* [FreeEsVCLComponents](https://github.com/errorcalc/FreeEsVCLComponents) .  `[Delphi]`用于Delphi和C ++ Builder的VCL组件的免费库.  这种新的控件和组件改善了外观应用程序并改善了用户体验.  组件支持视觉样式并具有现代风格.  所有组件都具有最佳的支持透明度，而不是闪烁，并且为TGraphicControl继承人提供了双重缓冲的有趣支持.

* [SpTBXLib](https://github.com/SilverpointDev/sptbxlib) .  `[Delphi]`用于Toolbar2000组件的附加软件包，它添加了以下功能：外观，Unicode支持，自定义绘画事件等.

* [Kastri library free](https://github.com/DelphiWorlds/KastriFree) .  “ [Delphi]” Kastri库的免费版本，这是一个跨平台的库，它建立在Delphi中现有的RTL和FMX库的基础上.  支持在FMX / RTL中找不到的许多较新的API，并为缺少的API提供“回填”


## Single controls

* [EasyListView](http://code.google.com/p/mustangpeakeasylistview) （似乎被抛弃，主动叉在GH [here](https://github.com/TurboPack/MustangpeakEasyListview) ）.  ListView的VirtualShellTools的[Delphi]部分，但可以用于更快速，更可定制的TListview替换.
// *功能丰富的Listview实现虚拟（基于回调）的MVC范例.*

* [VirtualTreeView](https://github.com/Virtual-TreeView/Virtual-TreeView) .  `[Delphi]`（[VirtualTreeView-Lazarus](https://github.com/blikblum/VirtualTreeView-Lazarus)  FPC`[FPC]`的端口）.  从头开始构建Treeview控件.  多年的发展使其成为当今最灵活，最先进的树控件之一.
 // *极其灵活的可视化组件，实现虚拟（基于回调）的MVC范例.  也可以用作列表视图或网格.  在RAD Studio GUI中使用.*

* [Delphi Chromium Embedded](https://github.com/hgourvest/dcef3) .  在Delphi中嵌入铬的“ Delphi”，已在Delphi 2010，XE，XE2和Delphi 7上进行了测试.
// *需要几个Chromium DLL *

* [TChromeTabs](https://github.com/norgepaul/tchrometabs) .  `[Delphi]`针对Delphi 6的Google Chrome浏览器选项卡的全面实现-Delphi 10.1 Berlin

* [TFrameStand](https://github.com/andrea-magni/TFrameStand) .  `[Delphi]`可以在您的FireMonkey（FMX）应用程序中轻松使用TFrame，以通过整个用户体验获得视觉一致性，并轻松添加诸如效果和过渡之类的现代元素.

* [TPrintPreview](https://github.com/landrix/TPrintPreview-for-Delphi) .  Delphi Vcl Win32 / Win64的[Delphi]打印预览组件

* [VolgaDB](https://sourceforge.net/projects/volgadb) .  `[Delphi]`用于Delphi的漂亮的可定制DBgrid.  TCustomGrid的后代.  CheckBox，ComboBox列样式.  还包括TVolgaDBEdit，它在一个组件中替代了TDBEdit，TDBComboBox，TDBLookupCombo，TDBLookupTree和TDBDatePicker.  TVolgaDBEdit可能支持DB，也可能不支持DB.
// *自2013年以来似乎已被放弃*

* [TTreeListView](http://github.com/benibela/treelistview) .  `[Delphi]``[FPC]`该组件是TTreeView和TListView之间的混合，可以绘制一棵树，其节点具有按列排序的其他信息.

* [neTabControl](https://github.com/jkour/neTabControl) .  Delphi的[Delphi] FireMonkey控件.  它以本机TabControl为基础，并添加了许多功能.

* [ATTabs](https://github.com/Alexey-T/ATTabs) .  `[Delphi]``[FPC]`精简标签的Delphi / Lazarus组件.  独立于操作系统，完全定制绘制.

* [zControls](https://github.com/MahdiSafsafi/zcontrols) .  `[Delphi]`包含TzObjectInspector-具有许多功能的强大对象检查器.

* [RiverSoftAVG Charting Component Suite](http://www.riversoftavg.com/charting.htm) .  带有源图表套件的免费[Delphi]（用于非商业用途），用于向程序添加图表.  适用于Delphi 2010-Tokyo（Win32 / Win64 / OSX / iOS / Android）和Appmethod（Object Pascal）.

* [DzHTMLText](https://github.com/digao-dalpiaz/DzHTMLText) .  `[Delphi]``[FPC]`可视组件，允许您使用与HTML代码几乎相同的语法在标签中指定带格式的文本.


## Editors

* [SynEdit](https://sourceforge.net/projects/synedit) ([mirror at GitHub](https://github.com/TurboPack/SynEdit) ）.  “ [Delphi]”语法高亮显示编辑控件，而不是基于Windows通用控件.  SynEdit与Delphi和Kylix兼容

* [BCEditor](https://github.com/bonecode/BCEditor) .  `[Delphi]`语法高亮显示带有代码折叠，小地图，外部JSON高亮显示和配色方案文件的编辑控件.
 // *似乎被遗弃了.  开发人员建议改为使用SynEdit *

* [LazEdit](https://svn.code.sf.net/p/lazarus-ccr/svn/applications/lazedit). `[FPC]` General text editor with syntax highlighting and tools to help edit HTML.


## Viewers

* [ATViewer](https://sourceforge.net/projects/atviewer) ([mirror at GitHub](https://github.com/Alexey-T/ATViewer) ）.  Delphi组件可用于查看各种文件类型：文本，二进制文件，图像，多媒体，网页等.
 // *在Universal Viewer软件中使用.  可用于显示十六进制转储，具有快速显示无限大小的文件/流的功能.  支持Total Commander Lister插件.*

* [ATImageMap](https://sourceforge.net/projects/atviewer/files/ATImageMap) ([mirror at GitHub](https://github.com/Alexey-T/ATViewer) ）.  “ Delphi”组件设计为将多个图像（整个图像的一部分）显示为单个地图.  例如，您可能有一个图像数组，X的图像为200，Y的图像为100，并且控件会将它们显示为单个地图.  该组件还允许绘制路径：每个路径由许多线，点和图标组成.

* [HtmlViewer](https://github.com/BerndGabriel/HtmlViewer) .  `[Delphi]``[FPC]`Delphi / Lazarus HtmlViewer / FrameViewer.
// * HTML可视化工具支持大多数标签，内联样式和CSS.*

* [SciDe](https://github.com/da-baranov/SciDe) .  `[Delphi]``[FPC]` [Sciter](https://sciter.com) （可嵌入的HTML / CSS / script引擎）Delphi的包装器.

* [ATBinHex for Delphi](https://github.com/Alexey-T/ATViewer/blob/master/Source/ATBinHex.pas) `[Delphi]`, [ATBinHex for Laz](https://github.com/Alexey-T/ATBinHex-Lazarus) .  `[FPC]`查看器，用于无限大小的文件，如Total Commander.

* [ATImageBox for Delphi](https://github.com/Alexey-T/ATViewer/blob/master/Source/ATImageBox.pas) `[Delphi]`, [ATImageBox for Laz](https://github.com/Alexey-T/ATImageBox-Lazarus) .  具有嵌入式TImage的T [FPC] TScrollBox.  控件可以在其中自动定位图像.


## Other GUI

* [GMLib](https://code.google.com/p/gmlibrary) （Google Maps Library）（似乎已废弃，GH上的活动fork [here](https://github.com/bero/GMLibrary) 和 [here](https://github.com/cadetill/gmlib_v1) ）.  Delphi / C ++ Builder的[Delphi]组件，封装了GoogleMaps API以管理地图，标记，多边形，矩形，折线等.您可以放入地图中的所有对象.

* [VCL Styles Utils](https://github.com/rruz/vcl-styles-utils) .  “ [Delphi]”类和样式挂钩的集合，它们扩展，修复了QC报告并向VCL样式添加了新功能.
 // *修补程序/增强功能的集合，将库存VCL样式引擎提升到一个新的水平.  还提供Inno Setup和NSIS的样式.*

* [TaskbarListComponents](https://github.com/chaosben/theunknownones/tree/master/Components/TaskBarList) .  `[Delphi]`设计为Windows 7 Taskbarlist接口（例如ITaskbarlist3）的Delphi包装器的一组组件
// *需要JVCL *

* [TFireMonkeyContainer](https://github.com/vintagedave/firemonkey-container) .  Delphi VCL组件，用于托管FMX HD或3D表单.  这意味着您可以将FireMonkey（FMX）表单作为控件嵌入到VCL表单中，因此您可以设计FMX表单并将其在VCL应用程序中使用.

* [PascalSCADA](http://sourceforge.net/projects/pascalscada) .  Delphi / Lazarus的一组组件（框架），以简化工业应用程序的开发（HMI =人机界面/ SCADA =系统控制和数据采集）.  它可以在Windows，Linux和FreeBSD上运行.

* [Windows Ribbon Framework for Delphi](https://github.com/turbopack/ribbonframework) .  `[Delphi]`此Delphi库允许Delphi开发人员在其Delphi应用程序中使用Windows Ribbon Framework.  该库使用本机Windows库来实现Ribbon功能.  它不会像其他Delphi组件集（或Delphi的内置Ribbon模拟组件）那样模拟Ribbon用户界面.

* [DKLang](https://github.com/yktoo/dklang) .  “ [Delphi]” DKLang本地化软件包是一组旨在简化用Delphi编写的应用程序的本地化的类.

* [GNU Gettext for Delphi, C++ and Kylix](https://sourceforge.net/projects/dxgettext/) .  Borland Delphi和Borland C ++ Builder的[[Delphi]] GNU GetText转换工具.

* [OpenWire](https://sourceforge.net/projects/openwireproject) .  “ [Delphi]”该库允许编写高级VCL和FireMonkey组件，以进行快速的无代码应用程序开发.  使用该库开发的组件允许使用零行程序代码创建复杂的应用程序.

* [SynTaskDialog](https://github.com/synopse/mORMot/blob/master/SynTaskDialog.pas) .  `[Delphi]``[FPC]`实施TaskDialog窗口（在Vista / Seven上为本地，在XP上为模拟）

* [AnyiQuack](https://github.com/WladiD/AnyiQuack) .  `[Delphi]`类似于jQuery的控制动画框架.

* [TLanguages](https://github.com/albertodev01/TLanguages) .  用于VCL和FMX的“ [Delphi]”本地化工具.

* [Dam](https://github.com/digao-dalpiaz/Dam) .  `[Delphi]`带有格式化文本的Delphi消息对话框.

 * [BitMapEditor-Delphi]（https://github.com/EverestSoftwareLLC/BitMapEdtior-Delphi）.  [Delphi]用于Delphi的单一形式的简单位图编辑器.


## Database ##

* [ZeosLib](http://sourceforge.net/projects/zeoslib) .  `[Delphi]``[FPC]`用于MySQL，PostgreSQL，Interbase，Firebird，MS SQL，Sybase，Oracle和SQLite的数据库组件集.

* [Unified Interbase](https://github.com/hgourvest/uib) .  `[Delphi]`使用Interbase，FireBird和YAFFIL的一组组件.  这些组件源于在多线程环境（例如服务器）中尽可能快地使用Interbase，FireBird或Yaffil的需求.

* [ASQLite](https://github.com/remobjects/ASQLite3) .  [Delphi]来自aducom软件的DAC组件的Delphi SQLite集，基于其针对Delphi 2009的最新版本，并进行了更新以支持Delphi的RemObjects Data Abstract中包含的较新版本的Delphi.

* [TxQuery](https://github.com/ccy/txquery) .  [Delphi] TDataSet后代组件，可用于使用SQL语句查询一个或多个TDataSet后代组件.  它使用Delphi 100％源代码实现，不需要DLL，因为它实现了自己的SQL语法解析器和SQL引擎.

* [Delphi-ORM](https://github.com/danieleteti/delphi-orm) .  Delphi XE2-7（Win32）的“ [Delphi]”对象关系映射.  支持FirebirdSQL，SQLServer和SQLite3.

* [delphimemcache](https://code.google.com/p/delphimemcache) .  `[Delphi]`为memcached实现线程安全客户端.
// *需要印第10 *版

* [SynDB](https://github.com/synopse/mORMot) ([docs](http://synopse.info/files/html/Synopse%20mORMot%20Framework%20SAD%201.18.html#TITL_126) ）.  `[Delphi]``[FPC]`高性能直接访问SQLite3，Oracle，MSSQL，PostgreSQL，Firebird，MySQL，ODBC，OleDB，包括远程HTTP连接和直接JSON支持.

* [SynMongoDB](https://github.com/synopse/mORMot/blob/master/SynMongoDB.pas) ([docs](http://blog.synopse.info/post/2014/05/07/MongoDB-database-access) ）.  `[Delphi]``[FPC]`提供对任何MongoDB服务器，其自定义数据类型，JSON或通过`TDocVariant`自定义变量文档存储的直接低级访问.

* [DSharp](https://bitbucket.org/sglienke/dsharp) .  `[Delphi]`用于在Delphi中提供数据绑定的小型库.  它不需要特殊的组件即可将数据绑定到属性.  它还提供了依赖注入，MVVM和更多有趣的实用程序.

* [ghORM](https://github.com/leledumbo/ghORM) .  “ [FPC]”对象关系映射单元通过抽象后端和简单的数据检索（带有过滤），插入和更新，简化了Free Pascal的数据库访问.

* [tDBF](http://sourceforge.net/p/tdbf/code/HEAD/tree) .  用于Delphi，BCB，Kylix和FreePascal的本机dBASE III +，dBase IV和dBase 2k数据访问组件.  它允许您创建非常紧凑的数据库程序，不需要任何特殊的安装程序.  数据库引擎代码直接编译到您的可执行文件中.

* [Redis client](https://github.com/danieleteti/delphiredisclient)  “ [Delphi]” Delphi Redis Client版本2与Delphi 10.1 Berlin兼容，并且更好.  警告！  如果您使用较旧的Delphi版本，则必须使用 [Delphi Redis Client Version 1](https://github.com/danieleteti/delphiredisclient/tree/DELPHI_REDIS_CLIENT_VERSION_1)  可以用于Delphi 10 Seattle，XE8，XE7，XE6和XE5（也应与旧版本一起使用）.  该客户端能够发送所有Redis命令并使用内部解析器读取响应.

* [QDAC3](http://blog.qdac.cc/?page_id=139)  （SVN：svn：//www.qdac.cc/QDAC3）.  `[Delphi]`代表快速数据访问组件.  有用的单位，例如QJson（易于使用的json单位），QWorker（作业交付）等.
 // *中文描述和注释，作者不擅长英语.  尚未亲自测试此库.*

* [InstantObjects](https://github.com/EtheaDev/InstantObjects) .  “ [Delphi]”用于在Delphi中开发面向对象的业务解决方案的集成框架.  该框架为开发过程以及为最终应用程序提供动力的引擎提供了基础.  InstantObjects提供：通过集成的双向工具在Delphi IDE中实现模型；  最常见的关系数据库或基于XML的平面文件中的对象持久性；  通过标准的数据感知控件进行对象呈现.

* [Alcinoe](#general-libraries) .  Firebird / MySQL / SQLite3 / Memcached / MongoDb / SphinxQL.

* [SynBigTable](https://github.com/synopse/mORMot/blob/master/SynBigTable.pas) .  `[Delphi]``[FPC]`类用于通过快速检索存储大量数据.

* [tiOPF](https://github.com/graemeg/tiopf) .  `[Delphi]`[FPC]`用对象Pascal编写的对象持久性框架，可用于Delphi和Free Pascal（FPC）编译器.  tiOPF简化了面向对象的业务模型到关系数据库的映射.  持久层适用于Firebird，Oracle，MS SQL Server，MySQL，PostgreSQL，SQLite，NexusDB，XML，CSV，TAB，远程（通过HTTP）等等.  它还允许您使用数据库连接组件的选择，例如IBX，dbExpress，DOA，SqlDB，FBLib等.

* [hcOPF](https://sourceforge.net/projects/larryhengensopf) .  用Embarcadero的Delphi（对象Pascal）编写的“ [Delphi]”对象持久性框架.  此值类型框架提供了由属性对象组成的基类（ThcObject），这些属性对象可以自动持久保存到对象存储（通常是RDBMS）.

* [Marshmallow](https://bitbucket.org/soundvibe/marshmallow/wiki/Home) .  Delphi XE2-7（Win32）的对象关系映射受.NET micro ORM（主要是PetaPoco）和Java Hibernate的启发.  由Linas Naginionis开发.  支持SQLite，Sybase ASA，SQL Server，Firebird，Oracle，MySQL，PostgreSQL，MongoDB.  用途 [Spring](http://code.google.com/p/delphi-spring-framework/)  框架.  在积极发展中.

* [DelphiCassandra](https://github.com/grijjy/DelphiCassandra) .  Delphi驱动程序类，用于与Cassandra数据库进行通信.

* [DelphiCouchbase](https://github.com/grijjy/DelphiCouchbase) .  Delphi驱动程序类，用于与Couchbase数据库进行通信.

* [DelphiMongoDB](https://github.com/grijjy/DelphiMongoDB) .  Delphi驱动程序类，用于与MongoDB数据库进行通信.

* [QuickORM](https://github.com/exilon/QuickORM) .  `[Delphi]``[FPC]`QuickORM是基于mORMot框架的简单RestServer和Restclient.  在几分钟内提供客户端服务器应用程序的快速实现.

* [iORM](https://github.com/mauriziodm/iORM) .  基于Delphi ORM接口的[Delphi]对开发桌面和移动应用程序很有用.


## Scripting ##
*在您的应用程序中使用脚本引擎*

* [Pascal Script](https://github.com/remobjects/pascalscript) .  `[Delphi]``[FPC]`免费脚本引擎，可让您在运行时使用Delphi或Free Pascal项目中的大多数Object Pascal语言.  它完全用Delphi编写，由一组可以编译成可执行文件的单元组成，从而无需分发任何外部文件.  当当时尚无可用的Pascal Script时，它是对一个好的脚本的需求.

* [DWScript](https://bitbucket.org/egrange/dwscript). `[Delphi]` Object-oriented scripting engine for Delphi based on the Delphi language, with extensions borrowed from other Pascal languages (FreePascal, Prism, etc.). It introduces a few Pascal language extensions of its own as well.

* [Delphi-Javascript](https://code.google.com/p/delphi-javascript) .  Delphi的Java引擎，基于Mozilla的Spidermonkey.
// *需要Spidermonkey DLL *

* [Blaise](http://sourceforge.net/projects/blaise) .  `[Delphi]`开源的面向对象脚本语言.  语言功能：面向对象；  Unicode支持；  可选类型，即动态或静态类型；  打字丰富；  更高级别的数学支持，例如复数，有理数和矩阵；  虚拟机架构；  协同例程；  熟悉的语言语法，受对象Pascal，Python和Ada的影响.

* [SpiderMonkey](https://github.com/synopse/mORMot/blob/master/SynSM.pas) .  Mozilla JavaScript引擎的[Delphi]`[FPC]绑定，包括JIT和多线程，可通过Delphi变体轻松访问对象.
// *需要Spidermonkey DLL *

* [BESEN](https://github.com/BeRo1985/besen) .  “ [Delphi]`[FPC]”在对象Pascal中完整的ECMAScript第五版实现，可通过Delphi&gt; = 7和Free Pascal&gt; = 2.5.1（也可能是2.4.1）进行编译.

* [Python for Delphi (P4D)](https://github.com/pyscripter/python4delphi) .  `[Delphi]``[FPC]`一组免费组件，将Python dll包装为Delphi和Lazarus（FPC）.  它们使您可以轻松执行Python脚本，创建新的Python模块和新的Python类型.  您可以将Python扩展创建为dll等

* [CrystalLUA](https://github.com/d-mozulyov/CrystalLUA) .  Lua绑定（Delphi6-2007）.
// *需要LUA DLL *

* [lua4delphi](https://github.com/danieleteti/lua4delphi) .  用于Lua 5.1语言的Delphi绑定.
// *需要LUA DLL *

* [chakracore-delphi](https://github.com/tondrej/chakracore-delphi) .  Microsoft的ChakraCore JavaScript引擎库的Delphi和Free Pascal绑定和类.

* [VerySimple.Lua](https://github.com/Dennis1000/verysimplelua) .  用于Delphi XE5-D10.1的`[Delphi]`Lua包装器，它自动为Delphi &lt;-&gt; Lua创建OOP回调函数.
// *需要LUA DLL *

* [QuickJS-Engine](https://github.com/Coldzer0/QuickJS-Pascal) .  `[Delphi]``[FPC]`Delphi和Bellard的免费Pascal绑定 [QuickJS](https://bellard.org/quickjs) JavaScript引擎.


## Non-visual Classes/Utils ##


## Compression

* [FWZip](https://github.com/AlexanderBagel/FWZip) .  `[Delphi]`类可使用Store和Deflate方法与Zip存档一起使用，支持ZIP64，DataDescryptors，PKWARE加密，NTFS属性和文件名中的Utf8.
 // *使用被编译成二进制文件的股票ZLIB.obj.  注释和俄语说明.*

* [Abbrevia](http://sourceforge.net/p/tpabbrevia) ([Newest](https://github.com/TurboPack/Abbrevia)  和维护的版本（仅适用于最新的编译器版本）.  “ [Delphi]”用于Delphi和C ++ Builder的高级数据压缩工具包.  支持PKZIP，Microsoft CAB，tar，gzip和bzip2存档，并且可以创建自解压的可执行文件.  在Windows上，它还提供用于LZMA，Bzip2和WavPack SDK的Delphi包装程序以及PPMd解压缩功能.  Abbrevia还具有一些可视控件，可简化显示和操作档案的过程，包括树视图和列表视图组件.  功能：所有存档格式的Unicode文件名；  解压缩大多数.zipx和旧版（PKZIP v1）zip；  ZIP64支持大于2GB的档案；  跨区和拆分的zip存档；  跨平台（Windows，OS X和Linux）；  不需要DLL；  包括COM组件；  广泛的文档
// *第二个链接指向最新编译器版本的适应版本.*

* [SynLZ SynLZO SynZip PasZip](https://github.com/synopse/mORMot) .  `[Delphi]`[FPC]`几个高速压缩单元，采用pascal和优化的汇编程序，具有ZIP / LZ77 Deflate / Inflate，LZO和SynLZ算法.

* [Delphi zlib](http://www.base2ti.com/?id=delphi.zlib) .  最初由Borland使用的zlib.obj的[Delphi]包装器.  Delphi最高支持XE3.

* [DIUcl](http://www.yunqa.de/delphi/products/ucl/index) .  “ [Delphi]” DIUcl是一种无损压缩库，具有极快且体积很小（仅200字节！）的ASM解压缩器.  压缩时间和压缩率与deflate / zip和bzip2相似.  流行的UCL压缩库的Delphi端口，流行和著名的UPX Ultimate Packer也将其用于eXecutables.


## Encryption

* [Delphi Encryption Compendium (DEC)](https://github.com/winkelsdorf/DelphiEncryptionCompendium) .  Delphi＆C ++ Builder的[[Delphi]`加密库.  对称加密功能：河豚，Twofish，IDEA，Cast128，Cast256，火星，RC2，RC4，RC5，RC6，Rijndael / AES，Square，SCOP，蓝宝石，1DES，2DES，3DES，2DDES，3DDES，3TDES，3Way，Gost， Misty，NewDES，Q128，SAFER，Shark，Skipjack，TEA，TEAN；  块密码操作模式：CTSx，CBCx，CFB8，CFBx，OFB8，OFBx，CFSx，ECBx；  哈希值：MD2，MD4，MD5，RichMD128，RichMD160，RichMD256，RichMD320，SHA，SHA1，SHA256，SHA384，SHA512，Haval128，Haval160，Haval192，Haval224，Haval256，Tiger，Panama，Whirlpool，Whirlpool1，Square，Snefru128，Snefru256，蓝宝石.
 // *自2010年以来没有更新，一些活动于2018年在** development **分支开始.  无论如何，功能列表是如此之大，以至于不能忽略*

* [LockBox](http://sourceforge.net/projects/tplockbox) ([Newest](https://github.com/TurboPack/LockBox3)  和维护的版本（仅适用于最新的编译器版本）.  `[Delphi]`用于加密的Delphi库.  当前支持的Delphi XE6.  它支持AES，DES，3DES，Blowfish，Twofish，SHA2（包括新的SHA-512 / 224和SHA-512 / 256），MD5；  ECB，CBC，CFB8，CFB，CTR，ECB，OFB，PCBC链接模式，RSA数字签名和验证.  具有与OpenSSL库的接口.
// *查看 [this](https://github.com/jarto/lockbox2) 页面以及其他版本.*

* [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas) .  “ [Delphi]” [FPC]`快速加密例程（哈希和密码），实现AES，XOR，RC4，ADLER32，MD5，SHA1和SHA256算法，并针对速度进行了优化（汇编程序和VIA PADLOCK可选支持）.

* [TForge](https://bitbucket.org/sergworks/tforge) .  `[Delphi]``[FPC]`用Delphi编写的开放源代码加密库，与Free Pascal Compiler兼容.  MD5，SHA1，SHA256，CRC32，詹金斯一次性，HMAC，PBKDF1，PBKDF2，AES，DES，RC4，RC5，Salsa20.

* [Spring4D](#general-libraries)CRC，DES，MD5，SHA

* [Fundamentals Code Library](#general-libraries) .  哈希：XOR，CRC，Adler，MD5，SHA，安全密钥MD5 / SHA等；  密码：AES，DES，FUNE，RC2 / 4，RSA.

* [Alcinoe](#general-libraries) .  AES，河豚，MD5，SHA，安全密钥MD5 / SHA.

* [DCPcrypt (fork #1)](https://sourceforge.net/projects/dcpcrypt), [DCPcrypt (fork #2)](https://bitbucket.org/wpostma/dcpcrypt2010) .  `[Delphi]`用于Delphi的加密组件套件.

* [HashLib4Pascal](https://github.com/Xor-el/HashLib4Pascal) .  Delphi / FreePascal兼容库，提供了易于使用的接口，用于计算字符串（具有指定编码），文件，流，字节数组和无类型数据的哈希和校验和. .  它还支持增量哈希.

* [CRC/Hash](http://www.wolfgang-ehrhardt.de/crchash_en.html) .  Pascal / Delphi源文件和与CRC，哈希和HMAC计算有关的二进制文件.  CRC，Adler，BJ查找，MD5，SHA，Whirlpool，Blake

* [Crypto](http://www.wolfgang-ehrhardt.de/crypt_en.html) .  [Delphi]`[FPC]`几种密码算法：128位分组密码AES和Twofish，64位分组密码Blowfish以及流密码Salsa20 / XSalsa20 / ChaCha和Sosemanuk.


## XML/JSON/YAML

* [dataset-serialize](https://github.com/viniciussanchez/dataset-serialize) .  `[Delphi]`该组件是Delphi的DataSet组件的JSON序列化器.  允许您将JSON转换为DataSet，将DataSet转换为JSON，并以JSON格式导出和加载DataSet字段的结构.  与VCL项目，FMX和uniGUI（框架）兼容.

* [OmniXML](https://github.com/mremec/omnixml) .  用Delphi编写的XML XML解析器.  完全支持文档对象模型（DOM）1级规范；  支持可扩展标记语言（XML）1.0（第二版）规范；  内置支持不同的代码页（主要的8位代码页，UTF-8，UTF-16）；  与MS XML解析器兼容；  快速解析甚至大型和高度结构化的文档；  包括帮助程序功能以简化XML文档的处理；  简化的XPath支持.

* [SAX for Pascal](http://sourceforge.net/projects/saxforpascal) .  `[Delphi]``[FPC]`设计用于在Pascal / Delphi中实现XML解析的简单API.
 // *基于回调的XML解析器，对于处理巨大的XML流非常有用.  自2004年以来已被放弃，但几乎是唯一可用的SAX实现.*

* [KDS XML](http://sourceforge.net/projects/kdsxml) .  “ [Delphi]”类库，用于流解析，验证和生成XML.  它用Object Pascal / Delphi编写，可在Win32（Delphi）和Linux（Kylix）上运行.  它的一部分取决于Pascal接口规格的SAX.
// *似乎已死.*

* [XML Partner](http://sourceforge.net/projects/tpxmlpartner) .  `[Delphi]`通过易于使用的本机VCL和CLX组件，帮助将XML的功能添加到Borland Delphi，C ++ Builder和Kylix项目中.  这些强大的组件简化了创建，修改和解析XML数据文档的过程.
// *似乎已死，请退房 [this](http://www.songbeamer.com/delphi) 可能是较新版本的页面.*

* [Open XML](http://www.philo.de/xml/downloads.shtml) .  “ [Delphi]”提供了广泛的方法，组件和基础类.  它可以用于Win32 / Kylix以及.NET开发.

* [SuperObject](https://github.com/hgourvest/superobject) .  `[Delphi]``[FPC]`解析器/编写器，用于JSON数据格式.  该工具包旨在与Delphi和FreePascal（win32，win64，linux32，linux64，MacOSX Intel）一起使用.  也支持读/写XML.

* [Libxml2 for pascal](https://sourceforge.net/projects/libxml2-pas) .  Pascal单元访问Daniel Veillard流行的XML API.  至少应该在Kylix和Delphi中可用，但希望也可以在其他Pascal编译器（如freepascal）中使用.

* [NativeXml](https://code.google.com/p/simdesign) .  `[Delphi]`此组件包含一个占地面积小的对象Pascal（Delphi）XML实现，该实现允许读取和写入XML文档.  基本上，您只需要一个单元，就可以简单地将其添加到“ uses”子句中.  您可以使用此软件从文件，流或字符串中读取XML文档.  加载例程生成事件，这些事件可用于动态显示加载进度.  您也可以使用它来创建和保存XML文档.

* [Delphi-XmlLite](https://github.com/the-Arioch/Delphi-XmlLite) .  Microsoft XmlLite的[[Delphi]]标头翻译.  XmlLite是.NET XmlReader + Writer的本机C ++实现，用于基于流的仅转发XML解析和创建.  XmlLite.dll是必需的.  它包含在Windows的所有新版本以及旧版本的Service Pack中.  XmlReader的基于pull的接口比SAX的基于事件的接口更易于使用.
// *似乎被遗弃，并报告为有故障.*

* [Chimera](https://bitbucket.org/sivv/chimera). `[Delphi]` Open Source (MIT License) library for Delphi XE2 which provides a fast and cross platform JSON generator/parser (serializer/deserializer) under a license that doesn't suck.

* [SynCommons](https://github.com/synopse/mORMot/blob/master/SynCommons.pas) .  `[Delphi]``[FPC]`高速JSON库，使用TDocVariant自定义变量类型进行存储和访问.

* [SynCrossPlatformJSON](https://github.com/synopse/mORMot/blob/master/CrossPlatform/SynCrossPlatformJSON.pas) .  `[Delphi]``[FPC]`高速跨平台JSON库，使用TJSONVariant自定义变量类型进行存储和访问.

* [Json Data Objects](https://github.com/ahausladen/JsonDataObjects) .  `[Delphi]`该Delphi单元包含一个JSON解析器，该解析器支持Delphi 2009-10Seattle和平台Win32，Win64和ARM Android（MacOS和iOS可以工作）.

* [TinyJSON](http://sourceforge.net/projects/tiny-json) ([mirror at GH](https://github.com/tmcdos/tiny-json) ）.  [Delphi]这是一个小而干净的库，用于具有布尔值/整数/浮点数/ WideString值的关联数组.  允许从（到）JSON文本导入（导出）.  广泛的错误检查.  使用FunHash（由Sokolov Yura编写），HatTrie（由Daniel C. Jones编写），FastInt64和FastMove（由FastCode项目编写）.

* [JSON delphi library](http://sourceforge.net/projects/lkjson) .  `[Delphi]`这是一个实现JSON数据格式和对象结构的delphi库.  轻巧快速.

* [dwsJSON](https://bitbucket.org/egrange/dwscript/src/b9f99d4b8187defac3f3713e2ae0f7b83b63d516/Source/dwsJSON.pas?at=master) .  `[Delphi]``[FPC]`dwsJSON是支持JSON解析/创建的单元，它是DWScript的一部分，但相对“独立”，因为如果将其添加到Delphi（或FPC）项目中，则不会拉整个DWScript库，因此可以在您需要的任何地方使用.

* [Fundamentals Code Library](#general-libraries) .  JSON，XML.

* [Alcinoe](#general-libraries) .  XML / JSON解析器.

* [delphi-yaml](https://bitbucket.org/OCTAGRAM/delphi-yaml) .  用于在Windows中实现的libyaml，YAML解析器和发射器库的Delphi 7兼容绑定.提出了四层绑定.

* [GrijjyFoundation](#general-libraries). JSON/BSON.

* [VerySimpleXML](https://github.com/Dennis1000/verysimplexml) .  `[Delphi]`适用于Delphi 2010的轻型，一个单元，跨平台XML读/写器-10.2.2东京

* [XSuperObject](https://github.com/onryldz/x-superobject) .  `[Delphi]`Delphi跨平台快速JSON

* [Internet Tools](https://github.com/benibela/internettools) .  `[Delphi]`[FPC]`软件包提供符合标准的XPath 2.0，XQuery 1.0和XPath / XQuery 3.0解释器，并具有JSONiq，模式匹配，CSS和HTML等扩展.  以及在Windows / Linux / MacOSX / Android上执行HTTP / S请求的功能，受XSLT启发的网络抓取语言和自动更新类.

* [Delphi-JsonToDelphiClass](https://github.com/PKGeorgiev/Delphi-JsonToDelphiClass) .  `[Delphi]`基于JSON字符串生成Delphi类（Json To Delphi类生成器/ JSON数据绑定工具）.  还包括与GitHub交互的单元.

* [XML Parser](http://www.destructor.de/xmlparser) .  `[Delphi]``[FPC]`用于Delphi和FreePascal的轻量级ObjectPascal XML解析器.  通过省略语法检查，格式正确的检查和/或验证，以及选择渐进式扫描技术，此解析器非常快.

* [HTML parser](https://github.com/ying32/htmlparser) .  `[Delphi]`HTML解析器.  支持Windows，MacOSX，iOS，Android平台.  中文注释


## Language
*用于Pascal和其他语言的工具*

* [Next Delphi Yacc & Lex](https://github.com/RomanYankovsky/ndyacclex) .  Delphi的解析器生成器工具集.

* [Abstract Syntax Tree Builder](https://github.com/RomanYankovsky/DelphiAST) .  `[Delphi]`使用DelphiAST，您可以获取真实的Delphi代码并获得抽象的语法树.  一次只有一个单位，但没有符号表.

* [Castalia-Delphi-Parser](https://github.com/jacobthurman/Castalia-Delphi-Parser) .  “ [Delphi]”这些文件构成了对象Pascal方言（称为“ Delphi”）的手​​写高速解析器.  最初的工作是由马丁·沃尔登堡（Martin Waldenburg）在1990年代后期完成的，而该项目在2003年之前的某个时候被放弃了，那时我找到了代码并开始进行开发.  我已根据需要对它进行了更新，以处理名为“ Castalia”的项目.

* [CrossPascal](https://github.com/BeRo1985/crosspascal) .  “ Delphi”旨在成为与Delphi 7兼容的跨平台源到源编译器（以及XE3中的新unicode字符串类型，但其中ansistring仍然是仍与Delphi 7兼容的默认字符串类型）中间C代码.
// *相当有趣的项目，但似乎已被放弃*

* [pas2js](https://svn.freepascal.org/svn/projects/pas2js/trunk), [docs](http://wiki.freepascal.org/pas2js) .  `[Delphi]``[FPC]`开源的Pascal到JavaScript编译器.  它解析对象Pascal并发出JavaScript.  JavaScript当前为ECMAScript 5级，应在任何浏览器或Node.js（目标“ nodejs”）中运行.  基本上，支持Delphi 7语法.  用于TMS WebCore和Elevate Web Builder等工具.


## Memory managers
*实现动态内存分配的库*

* [FastMM](https://github.com/pleriche/FastMM4) .  “ [Delphi]”用于Embarcadero Delphi Win32和Win64应用程序的闪电快速替换内存管理器，该内存管理器不易出现内存碎片，并支持共享内存，而无需使用外部.DLL文件.
 // *自2006年起用作库存管理器，但为简化版本.  提供强大的内存泄漏/损坏检测工具.*

* [ScaleMM](https://github.com/andremussche/scalemm) .  `[Delphi]`Delphi的快速扩展内存管理器

* [BrainMM](https://github.com/d-mozulyov/BrainMM) .  Delphi极快的内存管理器.
// *高级内存分配功能可加快对齐速度.*

* [FastMM4-AVX](https://github.com/maximmasiutin/FastMM4-AVX) .  [Delphi]`[FPC]`FastMM4 fork，具有AVX支持和多线程增强功能（更快的锁定）


## System
*低级助手：内存，线程等*

* [OmniThreadLibrary](https://github.com/gabr42/OmniThreadLibrary) .  `[Delphi]`简单易用的Delphi线程库.
// *轻松将异步流程集成到您的应用中*

* [Delphi Detours Library](https://github.com/mahdisafsafi/delphi-detours-library) .  `[Delphi]``[FPC]`库可让您挂钩Delphi函数和对象方法以及Windows API函数.  它提供了一种简单的方法来插入和移除挂钩.
// *支持x64，调用原始函数，多钩子，COM / Interfaces / win32api，对象方法钩子，完全线程安全，Delphi 7 / 2005-2010 / XE-XE7和Lazarus / FPC，支持64位地址.

* [MemoryModule](https://github.com/Fr0sT-Brutal/Delphi_MemoryModule) .  `[Delphi]``[FPC]`使用MemoryModule引擎，您可以在二进制文件中存储所有必需的DLL，以使其独立.  附加的挂钩单元允许透明地使用MM引擎，从而允许切换MM / WinAPI加载，并启用不了解MM的第三方动态加载DLL接口（已通过Interbase Express组件和Firebird客户端库进行了测试）.  MemoryModule是Joachim Bauch的C MemoryModule的Pascal端口.

* [DirectoryWatcher](https://github.com/Wosi/DirectoryWatcher) .  `[Delphi]`监视不同平台（Windows / Linux / Mac OS）上目录的更改.

* [ezthreads](https://github.com/mr-highball/ezthreads) .  `[FPC]`易于使用的线程库

* [AsyncCalls](https://github.com/ahausladen/AsyncCalls) .  `[Delphi]`异步函数调用框架


## Template
*根据模板生成文本输出的引擎*

* [SynMustache](https://github.com/synopse/dmustache) .  `[Delphi]`[FPC]`Mustache模板语言的Delphi实现，支持Delphi 6到Delphi 10 Seattle（以及FPC / Lazarus编译）.

* [Delphi Template Engine](http://sourceforge.net/projects/delphi-templeng) .  “ [Delphi]”模板引擎旨在用作Delphi（主要是Delphi 7）应用程序中的库，允许开发人员在其软件上使用模板，而不必担心实现它.

* [MustaPAS](https://github.com/leledumbo/mustapas) .  `[Delphi]``[FPC]`简单过程Pascal中的髭须实现.


## Logging

* [Log4d](https://github.com/landrix/Log4d-for-Delphi) .  `[Delphi]``[FPC]`基于Log4j的Delphi日志记录系统的实现.

* [TraceTool](http://tracetool.sourceforge.net/). `[Delphi]` C#, C++, Delphi, ActiveX and Java trace framework and a trace viewer.

* [LoggerPro](https://github.com/danieleteti/loggerpro) .  “ [Delphi]”一种用于Delphi的现代可插入日志记录框架.

* [SynLog](https://github.com/synopse/mORMot/blob/master/SynLog.pas) .  Synopse项目使用的`[Delphi]``[FPC]`日志记录功能.

* [slf4p](https://github.com/michaelJustin/slf4p) .  `[Delphi]``[FPC]`一个简单的日志外观，支持LazLogger，Log4D和其他日志框架.

* [GrijjyCloudLogger](https://github.com/grijjy/GrijjyCloudLogger) .  `[Delphi]`远程日志记录工具，使您可以通过Intranet或Internet从Windows，Linux，iOS，Android和macOS设备向运行Windows的查看器发送日志消息.  除了发送消息和任何数据外，它还具有众多功能，包括自定义实时监视，对象的远程实时视图，跟踪实时内存使用情况，对象分配，增长泄漏等.

* [QuickLogger](https://github.com/exilon/QuickLogger) .  Delphi / freepascal / .NET（Windows / Linux）库，用于登录文件，控制台，内存，电子邮件，休息，电报，松弛，事件日志，redis，ide调试消息和引发事件. .


## Math

* [Big Decimal Math](https://github.com/benibela/bigdecimalmath) .  “ Delphi”该单元提供任意精度的BCD浮点数类型.  它可以像任何数字类型一样使用，并支持：至少10-2147483647到102147483647之间的数字，精度为2147483647小数位；  所有标准算术和比较运算符；  舍入函数（floor，ceil，to-even，..）；  一些更高级的操作，例如电源和sqrt.

* [TIntX](https://github.com/Xor-el/IntXLib4Pascal) .  IntX任意精度Integer库的Pascal端口，具有大约O（N * log N）个乘法/除法算法的实现.  它提供了整数的所有基本算术运算，比较，按位移位等.它还允许解析不同基数的数字并将它们转换为字符串（也可以是任意基数）.  该库的优点是其快速的乘法，除法以及从基/到基的转换算法.  该算法的所有快速版本均基于使用快速Hartley变换的大整数快速乘法，该变换运行时间为O（N * log N * log log N）次，而不是经典的O（N ^ 2）.

* [DelphiBigNumberXLib](https://github.com/Xor-el/DelphiBigNumberXLib) .  用于Delphi的`[Delphi]`任意精度库，支持整数和浮点计算.

* [FastMath](https://github.com/neslib/FastMath) .  “ Delphi” Delphi数学库已针对快速性能进行了优化（有时会以不执行错误检查或失去一点准确性为代价）.  它使用手动优化的汇编代码来实现比Delphi RTL提供的等效功能更好的性能.
// *浮点，向量，矩阵运算*

* [MPArith](http://www.wolfgang-ehrhardt.de/misc_en.html#mparith) .  “ [Delphi]”多精度整数，有理数，实数和复数算术.

* [AMath](http://www.wolfgang-ehrhardt.de/misc_en.html#amath) 和 [DAMath](http://www.wolfgang-ehrhardt.de/misc_en.html#damath). `[Delphi]` Accurate mathematical methods without using multi precision arithmetic 和 double precision accurate mathematical methods without using multi precision arithmetic or assembler respectively.

* [ALGLIB](http://www.alglib.net/download.php) .  `[Delphi]``[FPC]`跨平台数值分析和数据处理库.  它支持多种操作系统（Windows和POSIX，包括Linux）.  ALGLIB的功能包括：数据分析（分类/回归，统计）；  优化和非线性求解器；  插值和线性/非线性最小二乘拟合；  线性代数（直接算法，EVD / SVD），直接和迭代线性求解器；  快速傅立叶变换和许多其他算法.
//免费版是Delphi封装的，被许可用于个人和学术用途的通用C核.

* [CAI NEURAL API](https://github.com/joaopauloschuler/neural-api) .  [FPC]`[Delphi]跨平台神经网络API已针对AVX，AVX2和AVX512指令集以及支持OpenCL的设备（包括AMD，Intel和NVIDIA）进行了优化.


## Command-line
*用于解析命令行参数的库*

* [TCommandLineReader](https://github.com/benibela/rcmdline) .  `[Delphi]``[FPC]`此单元为Lazarus和Delphi提供了一个高级的，独立于平台的命令行解析器.  它检查允许的选项，自动打印所有选项的帮助，并且-与rtl中的解析器相反-在Windows和Linux上的行为相同.

* [CommandLineParser](https://github.com/VSoftTechnologies/VSoft.CommandLineParser) .  [Delphi]简单命令行选项解析器-从DUnitX项目产生.

* [GpCommandLineParser](https://github.com/gabr42/GpDelphiUnits/blob/master/src/GpCommandLineParser.pas) .  `[Delphi]`基于属性的命令行解析器.

* [JPL.CmdLineParser](https://github.com/jackdp/JPLib/blob/master/Base/JPL.CmdLineParser.pas) .  `[Delphi]``[FPC]`命令行解析器，用于Delphi和Free Pascal


## Other non-visual

* [TRegExpr](https://github.com/ashumkin/RegExpr) .  `[Delphi]`简单易用且功能强大的工具，用于复杂的搜索和替换以及基于模板的文本输入检查.
// *自2004年以来已被废弃，但与现有的RAD Studio实现不同的是，它不使用添加对msvcrt.dll的依赖的PCRE obj文件*

* [FLRE](https://github.com/BeRo1985/flre) .  “ [Delphi]`[FPC]`FLRE（快速常规表达式）是一种快速，安全且有效的正则表达式库，已在Object Pascal（Delphi和Free Pascal）中实现，但甚至可以从其他语言，例如C / C ++等.

* [OnGuard](http://sourceforge.net/projects/tponguard) ([Alternate](https://github.com/TurboPack/OnGuard-VCL) and maintained version for recent compiler version only). `[Delphi]` Library to create demo versions of your Borland Delphi & C++Builder applications. Create demo versions that are time-limited, feature-limited, limited to a certain number of uses, or limited to a certain # of concurrent network users.
// *第二个链接指向最新编译器版本的适应版本.*

* [StringSimilarity](https://github.com/chaosben/theunknownones) .  “ [Delphi]”软件包，用于某些模糊和语音字符串比较算法.  到目前为止，已实现以下算法：DamerauLevenshtein，Koelner Phonetik，SoundEx，Metaphone，DoubleMetaphone，NGram，Dice，JaroWinkler，NeedlemanWunch，SmithWatermanGotoh和MongeElkan.

* [PubSub Chimera](https://code.google.com/p/pubsubchimera) .  Delphi的[Delphi]开放源代码（麻省理工学院许可）库，在不吸引用户的许可下，提供了一个快速且跨平台的PubSub和Message Queue实现.

* [DuckDuckDelphi](https://code.google.com/p/duckduckdelphi). `[Delphi]` Adds simple duck typing to Delphi Objects and provides an RTTI helper class to simplify many common RTTI tasks.

* [byterage](https://github.com/quartexNOR/byterage) .  “ Delphi”对象Pascal类库旨在消除流的某些限制.  该框架非常易于使用，只有一个公共祖先类（TBRBuffer）定义了一组存储不可知机制，用于分配，缩放，插入，删除以及以其他方式处理原始二进制数据的一部分.

* [stateless](https://github.com/SirRufo/stateless) .  `[Delphi]`用于在Delphi代码中创建状态机的简单库.

* [GenericTree](https://github.com/davidberneda/GenericTree) .  通用树结构的Delphi实现.

* [Delphi Event Bus](https://github.com/spinettaro/delphi-event-bus)  （简称DEB）.  Delphi的事件总线框架.

* [DelphiEventBus](https://github.com/BitecSPB/DelphiEventBus) .  Delphi的另一个事件总线框架，带有注释和丰富的事件过滤.

* [DHibernate](https://github.com/thecocce/delphi-hibernate) .  基于Hibernate和NHibernate的Delphi对象持久性框架.
// *自2012年起废弃*

* [UniConv](https://github.com/d-mozulyov/UniConv) .  `[Delphi]`[FPC]`通用文本转换库是一个通用的快速而紧凑的库，旨在按照Unicode联盟的最新标准进行转换，比较和更改文本寄存器.  这些库的功能非常类似于ICU，libiconv和Windows.kernel，它们实际上是流行操作系统的标准.

* [CachedBuffers](https://github.com/d-mozulyov/CachedBuffers) .  “ [Delphi]`[FPC]”该库对于顺序读取或写入数据的任务是不可替代的，尤其是在对性能的要求提高并且数据很多的情况下.

* [CachedTexts](https://github.com/d-mozulyov/CachedTexts) .  `[Delphi]`[FPC]`强大而紧凑的跨平台库，旨在解析和生成具有最大可能性能的文本数据.  依赖于其他两个库：CachedBuffers和UniConv.

* [ZEXMLSS](https://github.com/Avemey/zexmlss) .  `[Delphi]``[FPC]`用于读取/写入ods，excel xml，xlsx的Lazarus / Delphi组件.

* [PasMP](https://github.com/BeRo1985/pasmp) .  `[Delphi]``[FPC]`对象Pascal的并行处理/多处理库.

* [ICU4PAS](http://www.crossgl.com/icu4pas/index.html) .  `[Delphi]`[FPC]`对象Pascal，跨平台，Direct Class Wrapper，位于成熟且广泛使用的C / C ++ ICU库集上，提供Unicode支持，软件国际化（i18n）和全球化（g11n），为应用程序提供了在所有平台上的结果相同.  您可以在带有Delphi和FreePascal的Windows上以及在带有Kylix和FreePascal的Linux上使用它.
// *自2007年以来未进行过更新，但ICU接口可能保持不变... *

* [GpDelphiUnits](https://github.com/gabr42/GpDelphiUnits) .  `[Delphi]`有用的Delphi单元的集合.  各种TList后代，兼容TList和类似TList的类.  动态分配的O（1）入队和出队，线程安全的微锁定队列.  具有一些附加功能的64位文件功能的接口.  字符串哈希，表和字典.  Win32 / Win64包装器和辅助函数的集合.  时区例程.  嵌入式文件系统.

* [BaseNcodingPascal](https://github.com/Xor-el/BaseNcodingPascal) .  `[Delphi]`[FPC]`库，用于使用base32，base85，base128和其他FPC和Delphi算法将二进制数据编码为字符串.

* [ByteSizeLibPascal](https://github.com/Xor-el/ByteSizeLibPascal) .  `[Delphi]`[FPC]`TByteSize是一种实用程序“记录”，通过消除要表示的值的歧义，可以使代码中的字节大小表示更加容易.

* [EmailValidationPascal](https://github.com/Xor-el/EmailValidationPascal) .  `[Delphi]``[FPC]`用于在Pascal / Delphi中验证电子邮件地址语法的简单类.

* [PRNG](http://www.wolfgang-ehrhardt.de/misc_en.html#prng) .  “德尔福”七个快速伪随机数生成器，其周期长度比Pascal的随机函数大得多.  所有这些都使用上下文记录实现，因此可以同时使用几个独立的生成器，它们在密码上并不安全.  此外，还有三个密码生成器.

* [CSV File and String Reader](https://www.codeproject.com/Tips/783493/Delphi-CSV-File-and-String-Reader-Classes) .  “ [Delphi]” TnvvCSVFileReader和TnvvCSVStringReader是轻量级且快速的类，类似于单向数据集.

* [HTMLBuilder](https://github.com/guitorres/htmlbuilder) .  `[Delphi]`用Pascal代码构建简化的html.

* [Marvin.IA](https://github.com/marvinbraga/Marvin.IA) .  “ [Delphi]”面向对象的Pascal基元（仅接口和类）的机器学习集合.

* [FreePascal Generics.Collections](https://github.com/maciej-izak/generics.collections) .  FreePascal Generics.Collections库（TList，TDictionary，THashMap等）.

* [FuzzyWuzzy.pas](https://github.com/DavidMoraisFerreira/FuzzyWuzzy.pas) .  [FPC]`著名的Python模糊字符串匹配软件包的端口，该软件包使用Levenshtein距离来计算字符串序列之间的差异.

* [GS.Core](https://github.com/VincentGsell/GS.Core) .  `[Delphi]``[FPC]`几个项目共享核心功能.
//线程池，文件操作，Key &lt;&gt; Value数据库，JSON lib等
* [PascalTZ](https://github.com/dezlov/PascalTZ) .  “ [FPC]” Pascal时区允许您在考虑时区规则的历史更改的情况下，在各个时区的本地时间与GMT / UTC之间进行转换.

* [Charset Enigma](https://github.com/ms301/charset-enigma) .  `[Delphi]`Delphi字符集检测器社区版


## OS ##
*Tools that help dealing with OS-specific internals*

* [GLibWMI](http://sourceforge.net/projects/glibwmi) .  Delphi的[Delphi]组件库，将一组用于访问Windows WMI的类封装在一组VCL中.  BiosInfo，PrinterInfo，DiskInfo等...允许访问WMI类：WIN32_Bios，WIN32_Printers，WIN32_DiskDrive.

* [MemoryMap](https://github.com/AlexanderBagel/ProcessMemoryMap/tree/master/MemoryMap) .  `[Delphi]`一组类，用于获取有关正在运行的进程的内存的所有信息.

* [The new Drag and Drop Component Suite](https://github.com/DelphiPraxis/The-Drag-and-Drop-Component-Suite-for-Delphi) .  “ [Delphi]” VCL组件库，使您的Delphi和C ++ Builder应用程序能够支持基于COM的拖放并与Windows剪贴板集成.

* [TSMBIOS](https://github.com/RRUZ/tsmbios) .  `[Delphi]``[FPC]`允许使用对象Pascal语言（Delphi或Free Pascal）访问系统管理BIOS（SMBIOS）.  SMBIOS（系统管理BIOS）是DMTF开发的标准.  存储在SMBIOS中的信息包括设备制造商，型号名称，序列号，BIOS版本，资产标签，处理器，端口和已安装的设备内存.

* [VersionInfo for Delphi](http://melander.dk/articles/versioninfo) .  “ [Delphi]”该库使从Windows可执行文件和DLL的“版本信息”资源中读取值变得非常容易.  （可选）通过类帮助器使用版本信息属性扩展TApplication类.

* [Magenta Systems WMI and SMART Component](http://www.magsys.co.uk/delphi/magwmi.asp) .  “ [Delphi]”包含WMI，SMART和SCSI PassThrough函数，这些函数特别用于获取硬盘信息和配置网络适配器，还用于许多其他常规用途.  MagWMI使用类似于SQL的命令提供对任何WMI信息的常规视图访问，以及与TCP / IP配置有关的许多专用功能，例如设置适配器IP地址，计算机名称，域/工作组，BIOS和磁盘驱动器信息.

* [madKernel](http://help.madshi.net/madKernel.htm) .  `[Delphi]`该软件包最大一部分是关于内核对象的.  最重要的对象类型利用所有特定的kernel32 API封装在接口中.  具有以下接口包装器：事件，互斥对象，线程，进程，Windows，模块，任务栏图标，共享内存缓冲区.
// *免费提供用于非商业用途的资源（仅） [conditions](http://help.madshi.net/License.htm) .  可作为madCollection安装程序的一部分下载.  有据可查.  需要`madBasic`软件包.*

* [madSecurity](http://help.madshi.net/madSecurity.htm) .  `[Delphi]`该软件包使处理共享和其他安全对象（例如文件安全性或注册表安全性）变得容易.  为此，此程序包还具有“帐户”，“ ACE”和“ ACL”的功能.
// *免费提供用于非商业用途的资源（仅） [conditions](http://help.madshi.net/License.htm) .  可作为madCollection安装程序的一部分下载.  有据可查.  需要`madBasic`软件包.*

* [madShell](http://help.madshi.net/madShell.htm) .  “ [Delphi]”软件包实现了常用的shell功能，从特殊文件夹（例如“ Windows”文件夹或“ Program Files”文件夹）开始，再到Shell ID列表，Shell对象和Shell事件.  然后，您将发现有关ShortCuts / ShellLinks的功能，最后是有关显示模式的所有信息.
// *免费提供用于非商业用途的资源（仅） [conditions](http://help.madshi.net/License.htm) .  可作为madCollection安装程序的一部分下载.  有据可查.  需要`madBasic`软件包.*

* [WindowsAutorun](https://github.com/ms301/WindowsAutorun) .  `[Delphi]`帮助您管理Windows操作系统中的自动加载.


## Report generating ##

* [Report Manager](http://reportman.sourceforge.net) .  `[Delphi]`报表管理器是一个报表应用程序（Report Manager Designer）和一组用于预览，导出或打印报表的库和实用程序.  包括本机.Net和Delphi / C ++ Builder库，ActiveX组件以及标准动态链接库，可用于任何语言（例如GNU C）.

* [FortesReport](https://github.com/fortesinformatica/fortesreport-ce). `[Delphi]` The FortesReport is a powerful report generator available as a package of components for Delphi.

* [mORMotReport](https://github.com/synopse/mORMot/blob/master/SQLite3/mORMotReport.pas) ([docs](http://synopse.info/files/html/api-1.18/mORMotReport.html) ）.  `[Delphi]`快速有效的基于代码的报告组件，具有预览表单和PDF导出功能.


## Unit Testing ##

* [DUnitX](https://github.com/VSoftTechnologies/DUnitX). `[Delphi]` New test framework, taking ideas from DUnit, NUnit and other test frameworks. It is designed to work with Delphi 2010 or later, it makes use of language/RTL features that are not available in older versions of Delphi.

* [DUnit](http://dunit.sourceforge.net) .  “ [Delphi]”单元测试框架，多年来一直是标准测试框架，Delphi IDE现在随该库一起提供.
 // *自XE起包含，自XE8起不推荐使用DUnitX；  似乎被遗弃了.*

* [DUnit2](http://dunit2.sourceforge.net) .  DUnit项目的`[Delphi]`分支，添加了几个新功能.
// *似乎已废弃，缺少DUnit最新版本的某些功能.*

* [DelphiSpec](https://github.com/RomanYankovsky/DelphiSpec) .  `[Delphi]`库，用于运行以简单语言编写的自动化测试.  因为它们是用普通语言编写的，所以您团队中的任何人都可以阅读它们.  由于任何人都可以阅读它们，因此您可以使用它们来帮助改善团队之间的沟通，协作和信任.

* [Delphi-Mocks](https://github.com/VSoftTechnologies/Delphi-Mocks) .  Delphi XE2或更高版本的简单模拟框架.  允许您模拟类和接口以进行测试.

* [DUnit-XML](https://github.com/VSoftTechnologies/DUnit-XML) .  “ Delphi”测试运行程序，它允许DUnit测试输出与NUnit兼容的XML.

* [Smoketest](https://github.com/deltics/delphi.libs/tree/master/smoketest) .  `[Delphi]`框架，用于使用Microsoft Windows的Delphi语言编写测试和性能基准.  从7到2010年，它已经在所有版本的Delphi中进行了测试.

* [SynTests](https://github.com/synopse/mORMot/blob/master/SynTests.pas) .  `[Delphi]``[FPC]`单元测试功能，包括模拟和存根.

* [OpenCTF](http://openctf.sourceforge.net) .  用于Embarcadero Delphi的[Delphi]测试框架附加组件，它可以自动检查Forms（或DataModules）中的所有组件.  它为大型项目（其中许多组件必须通过重复测试）建立自动质量检查提供了一种简便的方法.  OpenCTF基于DUnit开源测试框架，并通过专门的测试类和帮助程序功能对其进行了扩展.

* [DelphiUIAutomation](https://github.com/jhc-systems/DelphiUIAutomation) .  封装了MS UIAutomation库的Delphi类.  DelphiUIAutomation是一个用于基于Win32自动化富客户端应用程序的框架（并已通过Delphi XE5进行了专门测试）.  它是用Delphi XE5编写的，不需要使用脚本语言.  它提供了一致的面向对象的API，隐藏了Microsoft的UIAutomation库和Windows消息的复杂性.


## Debugging / error handling ##

* [Delphi LeakCheck](https://bitbucket.org/shadow_cs/delphi-leakcheck) .  `[Delphi]`免费代码库，用于检查DUnit和DUnit2测试中的内存泄漏.  支持Delphi XE-XE7.

* [FastMM](#memory-managers) .  提供功能强大的内存泄漏/损坏检测工具.

* [JclDebug (part of Project JEDI)](https://github.com/project-jedi/jcl/blob/master/jcl/source/windows/JclDebug.pas) .  `[Delphi]``[FPC]`跟踪，MAP文件解析器，异常报告生成，异常堆栈跟踪.


## Utilities ##
*此处允许免费的非开源产品.*


## RAD Studio IDE plugins/wizards

* [Delphi IDE theme editor / Delphi IDE Colorizer](https://github.com/rruz/delphi-ide-theme-editor) .  用于更改多个对象Pascal IDE（例如Delphi（RAD Studio），Appmethod，Lazarus和Smart Mobile Studio）的IDE颜色突出显示的工具.  DITE支持Delphi 5-7、2005-2010，XE-XE8，Appmethod 1.13-1.14，Lazarus v1.0.1.3和Smart Mobile Studio IDE v1.1.2.17.  Delphi IDE Colorizer（DIC）是一个插件，可以自定义RAD Studio IDE和Appmethod的工作区的外观.

* [DDevExtensions](http://andy.jgknet.de/blog/ide-tools/ddevextensions) .  通过添加一些新的生产力功能来扩展Delphi / C ++ Builder IDE
// *必须进行许多有用的IDE调整.*

* [VCL Fix Pack](http://andy.jgknet.de/blog/bugfix-units/vclfixpack-10) .  Delphi单元通过修补原始功能来在运行时修复VCL和RTL错误.  如果您想在应用程序中找到所有IDE Fix Pack修复程序，则需要该单元.  将单元添加到项目中（Delphi和C ++ Builder）会自动安装可用于Delphi / C ++ Builder版本的修补程序.
// *实际适用于Delphi / C ++ 6..2009 *

* [IDE Fix Pack](http://andy.jgknet.de/blog/ide-tools/ide-fix-pack) .  收集了RAD Studio IDE，Win32 / Win64编译器和Win32调试器的非官方错误修复和性能优化.  IDE Fix Pack是RAD Studio 2009-XE6的IDE插件，可在运行时修复IDE错误.  所有更改都在内存中完成.  磁盘上没有文件被修改.  除了可以更快地进行编译之外，没有任何项目可以修改或从IDE Fix Pack中受益.  只有IDE才能获得修复和优化.
 // *支持自2007年以来的所有RAD Studio版本.删除了许多EMBT多年未解决的烦人的bug.  好极了！*

* [GExperts](https://sourceforge.net/projects/gexperts) .  通过向IDE添加一些功能来构建免费工具集，以提高Delphi和C ++ Builder程序员的生产率.  GExperts是作为开源软件开发的，我们鼓励用户为该项目做出贡献.  Grep搜索并替换支持的unicode文件，DFM等；  自动重命名组件，插入文本宏，打开最近的文件；  使用自定义的其他文件列表轻松备份您的项目；  保留喜爱的文件的嵌套列表，以便快速访问；  跟踪项目中各个单元之间的依赖关系；  快速跳转到当前单元中的任何过程；  还有更多...

* [CnWizards](https://github.com/cnpack) .  用于Delphi / C ++ Builder / CodeGear RAD Studio的免费插件工具集，可提高开发效率.

* [Delphi Package Installer (DelphiPI)](https://bitbucket.org/idursun/delphipi) .  该工具可帮助您将组件安装到Delphi IDE.  DelphiPI自动解决程序包之间的依赖关系，编译，安装并将源路径添加到您的IDE.

* [ResEd](https://github.com/chaosben/theunknownones) .  Delphi 2005、2006、2007、2009、2010和XE的专家.  该专家旨在编辑链接到活动项目的资源文件（.res; .resx）.  它将自动搜索所有出现的{$ R xyz.res}行，并将为它们打开/创建资源文件.  专家将自己注册到“视图”下的Delphi菜单栏中.

* [Parnassus Bookmarks](https://parnassus.co/delphi-tools/bookmarks) .  扩展书签功能的IDE插件.

* [DelphiSettingManager](https://github.com/Arvur/DelphiSettingManager) .  Delphi的多个IDE配置文件（最多XE6）.  允许为不同项目安装相同组件或不同组件集的多个版本.

* [Delphinus](https://github.com/Memnarch/Delphinus) .  新的Packagemanager运行在Delphi XE及更高版本上，并使用Gi​​thub作为后端来提供软件包.

* [Parnassus Bookmarks](https://parnassus.co/delphi-tools/bookmarks) .  扩展书签功能的IDE插件.

* [TestInsight](https://bitbucket.org/sglienke/testinsight/wiki/Home) .  用于Delphi的单元测试IDE插件.  它支持从XE到10 Seattle的所有版本.  支持DUnit，DUnit2，DUnitX框架.

* [Delphi IDE Explorer](https://github.com/DGH2112/Delphi-IDE-Explorer) .  向导/专家/插件，使您可以浏览IDE的内部字段，方法，属性和事件.
// *主要对IDE专家的开发人员有用*

* [Multi-RAD Studio IDE Expert Manager](http://www.davidghoyle.co.uk/WordPress/?page_id=1361) .  该应用程序用于在计算机上编辑所有版本的RAD Studio（以及较旧的Delphi和C ++ Builder）中已安装的专家.

* [OTA Interface Search](https://github.com/DGH2112/OTA-Interface-Search) .  应用程序有助于找到Open Tools API（OTA）的接口，方法和属性，并了解如何访问这些接口或方法/接口的属性.

* [AutoSave](https://github.com/DGH2112/Auto-Save) .  定期自动保存所有打开的已修改IDE文件的专家.

* [Browse and Doc It](http://www.davidghoyle.co.uk/WordPress/?page_id=872) .  插件使您可以在IDE中记录和浏览代码.

* [Integrated Testing Helper](http://www.davidghoyle.co.uk/WordPress/?page_id=874) .  Delphi和RAD Studio插件，使您可以在项目编译之前和之后运行命令行应用程序.  它还提供了将您的项目文件压缩到每个编译/构建中的归档文件中并管理应用程序的版本信息的功能.

* [Project Magician](https://www.uweraabe.de/Blog/2018/05/17/keep-your-project-files-clean-with-project-magician) .  用于高级项目选项操作的向导.

* [Selective Debugging](http://www.uweraabe.de/Blog/2015/05/08/selective-debugging/) .  向导，用于调整调试版本将用于哪些单元.

* [MMX Code Explorer](https://www.mmx-delphi.de) .  功能丰富的生产力增强插件.  包括重构，类浏览器，高级编辑，度量标准等等.

* [FormResource](http://chapmanworld.com/2017/03/22/formresource-a-free-delphi-component-for-organizing-product-dependencies) .  该向导有助于将各种数据存储为表单资源.

* [Delphi Library Helper](https://github.com/littleearth/delphi-library-helper) 协助Delphi开发人员配置库文件夹的工具.

* [Mobile Image Creator](https://github.com/littleearth/mobile-image-creator)  为Delphi移动应用程序（Firemonkey）创建图标和启动器图像.  这是由创建的Mobile Gfx的分支 [Thomas Grubb of RiverSoftAVG](http://riversoftavg.com/blogs/index.php/2014/02/03/creating-icons-and-launchers-for-delphi-mobile-applications/).

* [Delphi-Adb-WiFi](https://github.com/ms301/Delphi-Adb-WiFi) .  RAD Studio插件，它允许在Android设备上启动和调试，而无需通过USB连接到计算机.  通过WiFi工作.

* [RADSplit](https://github.com/LaKraven/RADSplit) .  RAD Studio的可停靠分屏编辑器（Delphi和C ++ Builder）.

* [DzNoteEditor](https://github.com/digao-dalpiaz/DzNoteEditor) .  用于TString的Delphi属性编辑器，支持带语法突出显示的格式化语言.


## Plugins for other IDE's

* [Delphi IDE theme editor / Delphi IDE Colorizer](#rad-studio-ide-pluginswizards) .  支持Appmethod，Lazarus和Smart Mobile Studio.


## Documentation

* [SynProject](https://github.com/synopse/SynProject) ([docs](http://synopse.info/fossil/wiki?name=SynProject) ）.  用于Delphi项目的代码源版本控制和自动文档编制的工具.

* [PasDoc](https://sourceforge.net/projects/pasdoc) .  `[Delphi]``[FPC]`用于ObjectPascal（FreePascal和Delphi）源代码的文档工具.  根据源代码中的注释生成文档.  可用的输出格式为HTML，HtmlHelp，LaTeX，latex2rtf，simplexml.  将来可能会添加更多输出格式.

* [DIPasDoc](http://www.yunqa.de/delphi/products/pasdoc/index) .  `[Delphi]``[FPC]`从Pascal源代码文件中的注释生成HTML文档.  它将可浏览的帮助输出为标准HTML文件或可自定义的MS HTML帮助项目.


## Code check/review, debug

* [GpProfiler2017](https://github.com/ase379/gpprofile2017) .  Delphi XE及更高版本的源代码检测分析器.  其他fork支持较旧的版本.

* [SamplingProfiler](https://www.delphitools.info/samplingprofiler) .  Delphi 5至32位Delphi XE4的性能分析工具.  其目的是帮助找到瓶颈，甚至在全速运行的最终优化代码中也是如此.

* [Delphi Code Coverage](https://sourceforge.net/projects/delphicodecoverage) .  Delphi的[Delphi]简单代码覆盖率工具，可基于详细的MAP文件创建代码覆盖率报告.

* [Pascal Analyzer](http://www.peganza.com/products_pal.html)  （提供免费的精简版）.  “ Delphi” Pascal分析器（简称PAL）解析Delphi或Borland Pascal源代码.  它构建大型的标识符内部表，并收集其他信息，例如子程序之间的调用.  解析完成后，将生成大量报告.  这些报告包含有关源代码的大量重要信息.  这些信息将帮助您更好地理解源代码，并帮助您生成更高质量和可靠性的代码.

* [madExcept](http://madshi.net/madExceptShop.htm) .  `[Delphi]`madExcept旨在帮助您查找软件中的错误.  只要程序中出现崩溃/异常，madExcept就会自动捕获它，对其进行分析，收集大量有用的信息，并使最终用户可以向您发送完整的错误报告.  madExcept还可以为您查找内存泄漏，资源泄漏和缓冲区溢出.
// **免费**没有来源**用于非商业用途（仅） [conditions](http://help.madshi.net/License.htm) .  可作为madCollection安装程序的一部分进行下载（您需要安装madExcept项）.  有据可查.*

* [delphiunitsizes](https://github.com/VilleKrumlinde/delphiunitsizes) .  “ Delphi”工具，用于显示Delphi可执行文件中每个单位的大小.  显示Delphi exe文件中包含的每个单元的大小.  它还显示一个单元中每个符号（类，方法，过程等）的近似大小.

* [MapFileStats](https://www.delphitools.info/other-tools/mapfilestats) .  “ Delphi”工具，可从.MAP文件（任何Delphi版本，至少到Delphi XE5）提供简单的二进制大小统计信息.

* [Spider](https://github.com/yavfast/dbg-spider) .  `[Delphi]`用于Delphi应用程序的实时分析器

* [AsmProfiler](https://github.com/andremussche/asmprofiler) .  “ [Delphi]”全跟踪32位分析器（仪表和采样），用Delphi和一些汇编语言编写

## Setup

* [Lazy Delphi Builder](https://bitbucket.org/tdelphi/lazy-delphi-builder-downloads) .  Delphi的构建工具.  从具有所有依赖项的源重新编译项目/程序包，而无需弄乱配置.  快速将源中的组件（重新）安装到IDE中，而无需更改库路径.
 // *强大的自动化工具.  免费软件，但不是开源*

* [Inno Setup](http://www.jrsoftware.org/isinfo.php) .  Windows程序的免费安装程序.  Inno Setup于1997年首次推出，如今在功能和稳定性方面可与甚至超过许多商业安装程序媲美.

* [WinSparkle](https://winsparkle.org) 及其 [Delphi wrapper](https://github.com/jkour/neSparkleComponent) .  WinSparkle是Windows开发人员易于使用的软件更新库.  WinSparkle是一个受Andy Matuschak最初启发的Sparkle框架（在事实上已成为macOS上软件更新的标准）的灵感的主要来源（几乎是端口）.

* [Silverpoint MultiInstaller](http://www.silverpointdevelopment.com/multiinstaller/index.htm) .  用于Embarcadero Delphi和C ++ Builder的多组件软件包安装程序，是为了简化IDE上的组件安装而创建的.


## Other


* [Delphi Preview Handler](https://github.com/RRUZ/delphi-preview-handler) .  适用于Windows Vista，7和8的预览处理程序，使您可以在语法高亮的情况下读取对象pascal，C ++和汇编代码，而无需在编辑器中打开

* [Delphi Dev. Shell Tools](https://github.com/RRUZ/delphi-dev-shell-tools) .  Windows Shell扩展，带有对对象Pascal开发人员有用的任务（Delphi，Free Pascal）.

* [Delphi.gitignore](https://github.com/github/gitignore) .  .gitignore用于Delphi的模板.  拉撒路也有一个.

* [OmniPascal](http://omnipascal.com) .  该项目使Delphi和Free Pascal开发人员能够使用现代编辑器编写和维护代码 [Visual Studio Code](https://code.visualstudio.com).

* [Delphi Unit Tests](https://bitbucket.org/NickHodges/delphi-unit-tests) .  用于Delphi库的单元测试集.  鼓励Delphi社区成员分叉存储库，添加测试并创建请求请求.  特别鼓励Embarcadero员工从使用官方Delphi版本运行的内部测试中添加测试.

// *免费**无源**用于非商业用途（仅） [conditions](http://help.madshi.net/License.htm) .  可作为madCollection安装程序的一部分进行下载（您需要安装madExcept项）.  有据可查.*

* [Chet - C Header Translator for Delphi](https://github.com/neslib/Chet) .  Chet是一个由libclang为Delphi支持的.h-to..pas转换器.  使用Clang编译器解析头文件，从而产生更准确的翻译，而需要的手动调整较少.

* [Boss](https://github.com/HashLoad/boss) .  德尔福项目的依赖管理器.


## License ##

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0)
