<div class="github-widget" data-repo="robinrodricks/awesome-actionscript3"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
[<img src="https://rawgit.com/hgupta9/awesome-actionscript3/master/AS3_AIR.png" align="right" width="150">](https://www.adobe.com/products/air.html)

## Awesome ActionScript 3 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 适用于 ActionScript 3 和 Adob​​e AIR 的出色库和组件的精选列表.

[Adobe AIR](https://en.wikipedia.org/wiki/Adobe_AIR) 提供一组 API 来构建跨平台的桌面/移动应用程序和游戏. [ActionScript 3](https://en.wikipedia.org/wiki/ActionScript) 是 AIR 的编程语言. 默认包含强大的原生功能，例如文件系统、SQLite、传感器. 要添加缺少的功能，您可以构建以本地语言（例如 Windows 的 VC++、Android 的 Java、iOS 的 Swift/Objective-C）编码的 ANE（Air Native Extensions）. 要使用 GPU 渲染的图形构建移动应用程序/游戏，请使用 [Starling](https://gamua.com/starling/) 框架和可选 [Feathers UI](https://feathersui.com/) .  Adobe AIR 在移动游戏领域非常流行.

欢迎投稿. 要添加一个有用的项目，只需创建一个 [Issue](https://github.com/hgupta9/awesome-actionscript3/issues).


	

## Development Tools
*本节包括商业工具以及免费/开源工具.*

#### Code Editors
* [FlashDevelop](http://flashdevelop.org/) - 首映适用于 AS3 和 AIR 的免费和开源 IDE，具有代码完成、调试等功能.
* [Adobe Flash Builder](https://www.adobe.com/products/flash-builder.html) - 用于在 Flex 框架上构建应用程序的商业 IDE（带有高级调试工具）.
* [Moonshine IDE](http://moonshine-ide.com/) - Moonshine 是使用 ActionScript 3 构建的免费开源中量级 IDE，用于 ActionScript 3、Apache Flex®、Apache FlexJS® 和 Feathers 开发，支持云和桌面.
* [IntelliJ IDEA](https://www.jetbrains.com/help/idea/building-actionscript-and-flex-applications.html) - 支持多种不同语言（包括 AS3）的商业 IDE.
* [Visual Studio Code](https://as3mxml.com/)  - Visual Studio Code 的 AS3 和 MXML 语言扩展. 在 Windows、macOS 和 Linux 上运行.

#### Live Debuggers
* [Adobe Scout](https://www.adobe.com/products/scout.html) - 用于 AIR 应用程序和游戏的高级可视化分析和调试工具（支持 Stage3D）.
* [De-Monster Debugger](https://github.com/MrTact/monsterdebugger) - 从实时 AIR 应用程序调试图形和数据的高级工具.
* [De-Monster Debugger (Starling)](https://github.com/joshtynjala/monsterdebugger-client-starling) - 支持 Starling 框架的 De-Monster 调试器的分支.

#### Asset Creators
* [Adobe Animate CC](https://www.adobe.com/products/animate.html) - 用于矢量/精灵表创建的首映矢量图形和动画工具集.
* [TILED Map Editor](http://www.mapeditor.org/) - 灵活的瓷砖地图编辑器兼容各种 AS3 游戏引擎.
* [FlashMovieClipConverter](https://github.com/zenrobin/FlashMovieClipConverter) - 将 Flash 影片剪辑转换为 Starling IAnimatable Sprite.

#### SWF Obfuscators
* [secureSWF](http://www.kindi.com/) - 具有重命名、资产加密和自动代码优化的商业 AS3/AIR 混淆器.
* [irrFuscator](http://www.ambiera.com/irrfuscator/) - 用于 Flash 和 Flex SWF 文件的商业 AS3 混淆器.

#### SWF Inspectors
* [SWFWire](https://github.com/magicalhobo/SWFWire) - 高级 SWF 反编译器、检查器和调试器工具（[website](http://www.swfwire.com/)).
* [Velocity9](https://github.com/velocity9/Inspector) - 基本 SWF 检查员.

#### SWF Decompilers
* [AS3Sorcerer](http://www.as3sorcerer.com/) - Premiere AS3 反编译器具有 99% 的反编译精度（支持 SWF/SWC、Alchemy 操作码）.
* [Sothink Decompiler](http://www.sothink.com/product/flashdecompiler/) - 用于 AS2/AS3 的高级反编译器（支持资产提取和 SWF 到 FLA/Flex 的转换）.

#### ANE Dev Tools
* [FreSharp](https://github.com/tuarua/FreSharp) - Build ANEs using C# with this C# wrapper for FlashRuntimeExtensions .
* [Swift-IOS-ANE](https://github.com/tuarua/Swift-IOS-ANE) - 用 Swift 3 为 iOS 10 编写的 ANE 入门工具包.

## Frameworks
#### MVC Frameworks

* [PureMVC](https://github.com/PureMVC/puremvc-as3-standard-framework) - 适用于 Flash 的行业标准 MVC 框架（[multicore](https://github.com/PureMVC/puremvc-as3-multicore-framework)).
* [Robotlegs](https://github.com/robotlegs/robotlegs-framework) - Flash 的依赖注入、模块/视图/命令管理框架.
* [Hummingbird](https://github.com/flashapi/hummingbird) - 为 AS3、Mobile 和 Starling Framework 构建和部署强大的 MVC 应用程序.
* [Apollo](https://github.com/LaurentZuijdwijk/Apollo) - 依赖注入和消息传递框架，可作为 MVC 项目的基础.
* [Somacore](https://github.com/soundstep/somacore_framework) - 轻量级的基于事件的 AS3 MVC 框架.
* [Kote](https://github.com/whitered/Kote) - 快速、轻量级的 MVC 框架，汇集了 PureMVC 和 as3 信号的精华.
* [StarlingMVC](https://github.com/CreativeBottle/starlingMVC) - 基于 Starling 的游戏的 IOC 框架.

#### UI Frameworks

* [Starling](https://gamua.com/starling/)  - 基于 Stage3D 构建的高性能 2D 图形引擎.  API 与 Flash API 相同.  ([github](https://github.com/Gamua/Starling-Framework), [help](http://wiki.starling-framework.org/start)).
* [Feathers UI](https://feathersui.com/) - Starling Framework 的用户界面组件（[github](https://github.com/BowlerHatLLC/feathers), [help](https://feathersui.com/help/index.html)).
* [Flow](https://github.com/artman/Flow) - 代替 Flex 使用布局、效果、数据绑定和远程处理框架.
* [AS3Commons UI](https://github.com/AS3Commons/as3commons-ui) - 布局、焦点和键盘管理框架.
* [Swiz](https://github.com/swiz/swiz-framework) - 极其简单的微架构，用于使用 AS3 和 Adob​​e Flex 创建 RIA.
* [Hiddenwood](https://github.com/raweden/Project-Hiddenwood) - 为 Web 应用程序项目开发的用户界面库，用 AS3 和 MVC 模式编写.
* [Elastic-Lists](https://github.com/MoritzStefaner/Elastic-Lists) - 用于分面浏览的流畅而强大的界面.
* [Apache Flex®](https://flex.apache.org/)  - Apache Flex® SDK 是流行的 Adob​​e Flex SDK 的演变.  Apache Flex® SDK 是一个应用程序开发框架，用于为移动设备、Web 浏览器和桌面平台轻松构建基于 Flash 的应用程序.
* [Apache Royale®](http://royale.apache.org/)  - Apache Royale® 项目正在开发下一代 Apache Flex® SDK.  Royale 的目标是允许以 MXML 和 ActionScript 开发的应用程序不仅可以在 Flash/AIR 运行时中运行，而且还可以在没有 Flash 的浏览器中、在移动设备上作为 PhoneGap/Cordova 应用程序以及在嵌入式 JS 环境中运行作为 Chromium 嵌入式框架.  Royale 有可能允许您的 MXML 和 ActionScript 代码在比 Flash 目前更多的地方运行.

#### Game Frameworks

* [CitrusEngine](http://citrusengine.com/) - 基于 Starling &amp; Away3D 构建的专业级游戏引擎.
* [StarlingPunk](https://github.com/asaia/StarlingPunk) - 基于 Starling 构建的框架，可为您的游戏项目添加结构和组织.
* [FlashPunk](https://github.com/useflashpunk/FlashPunk)  - 构建 2D 游戏的框架. 提供图形、事件、输入、动画等.
* [Flixel](https://github.com/AdamAtomic/flixel) - 有用的基类，您可以扩展这些基类来制作自己的游戏对象.
* [Tetragon](https://github.com/NothingInteractive/tetragon)  - 构建任何类型游戏的跨平台框架. 提供资源管理、调试工具、多语言环境支持、分层可扩展性、面向游戏的数据结构等.
* [Pixelizer](https://github.com/johanp/Pixelizer)  - 基于组件的游戏引擎来构建 2D 游戏. 提供渲染、动画、输入等.
* [AS3isolib](https://github.com/as3isolib/as3isolib.v1) - 等轴测库开发以协助创建等轴测投影游戏.
* [IsoHill](https://github.com/jadbox/IsoHill-Game-Engine) - 基于 GPU 的 Isometric 引擎基于 Starling，具有 TILED 地图解析器、图层等（[website](http://www.isohill.com/)).
* [YCanvas](https://github.com/jozefchutka/YCanvas) - 高性能 2D 平铺渲染器和世界地图渲染器.
* [ND2D](https://github.com/lrrrs/nd2d) - 使用 Stage3D 的 GPU 加速 2D 游戏引擎（[ND2Dx](https://github.com/NoRabbit/ND2Dx)).
* [Nexus](https://github.com/tversteeg/Nexus) - 使用 Stage3D 的 GPU 加速 2D 游戏引擎.

#### 3D Frameworks

* [AwayBuilder](http://awaytools.com/awaybuilder/) - Visual workflow tool to import, optimise and bake 3D assets from a variety of sources.
* [Away3D](https://github.com/away3d/away3d-core-fp11) - 用于 Flash Player 11+ 的开源 GPU 加速 3D 引擎（[examples](https://github.com/away3d/away3d-examples-fp11)).
* [Away3D OpenFL](https://github.com/away3d/away3d-core-openfl)  - 用于 Neko、HTML5 和原生 CPP 的 Away3D.  ([examples](https://github.com/away3d/away3d-examples-openfl)).
* [AwayPhysics FP11](https://github.com/away3d/awayphysics-core-fp11) - Away Physics - Away3D FP 11 的 3D 物理库（[examples](https://github.com/away3d/awayphysics-examples-fp11)).
* [Alternativa3D](https://github.com/AlternativaPlatform/Alternativa3D) - Alternativa3D GPU 加速 3D 引擎（[examples](https://github.com/AlternativaPlatform/Alternativa3DExamples)).
* [Flare3D](http://flare3d.com/) - 具有高性能引擎和关卡编辑器 IDE 的商业 3D 平台.
* [Zen3D](https://github.com/hgupta9/Zen3D) - 用于 Adob​​e Flash 和 AIR（基于 GPU）的高性能 3D 引擎.

#### Animation

* [GreenSock GSAP](https://greensock.com/gsap-as) - 业界标准的 Flash 动画库（TweenLite、TweenMax）（[github](https://github.com/greensock/GreenSock-AS3)).
* [GTween](http://gskinner.com/libraries/gtween/) - 用于程序化补间、动画和过渡的小而强大的库.
* [DragonBones](http://dragonbones.github.io/) - 使用 Starling 的高速骨骼动画，以及从 Flash Pro 导出动画的工具.
* [FlashEff2](http://www.flasheff.com/) - 具有 100 多种过渡和文本效果的 Premiere 程序化动画库.
* [FlashEffNano](http://www.flasheffnano.com/) - 针对移动设备优化的 FlashEff 过渡库，具有 750 种样式的 20 多种过渡.
* [StarlingGAFPlayer](https://github.com/zenrobin/StarlingGAFPlayer) - 使用 Starling（在 Flash Pro 中创作的动画）播放 GAF 动画.

#### Signals

* [AS3-signals](https://github.com/robertpenner/as3-signals) - New approach for AS3 events inspired by C# events and signals/slots in Qt.
* [react-as3](https://github.com/tconkling/react-as3) - 信号/插槽和功能反应式编程库.
* [Signaller](https://github.com/whitered/Signaller) - 具有限制调度权限的信号实现.
* [Fa-as3](https://github.com/fabrikagency/fa-as3) - 少写，多做框架，像 jQuery 一样建模.

#### Functional

* [AS3FP](https://github.com/jadbox/AS3FP) - 基于 Haskell 和 Coffeescript 的功能习语集合.
* [Raix](https://github.com/richardszalay/raix) - 反应式和交互式扩展简化了使用交互式数据（数组）或反应式数据（事件）.
* [Fxp-as3](https://github.com/j3k0/fxp-as3) - 受“最充分指南”启发的功能库.

#### Unit Testing

* [AS3unit](https://github.com/Hoten/as3unit) - ActionScript 3 的单元测试框架.
* [hamcrest-as3](https://github.com/drewbourne/hamcrest-as3) - Matcher 对象允许以声明方式定义“匹配”规则.
* [expect.as](https://github.com/krzysztof-o/expect.as) - 适用于 ActionScript 3 的 BDD 样式断言库.
* [AS3spec](https://github.com/f1337/as3spec) - 受 Bacon 和 RSpec 启发的用于 AS3 的微型 BDD 框架.
* [Flexunit](https://github.com/flexunit/flexunit) - 用于 Actionscript 3 和 Flex 项目的 FlexUnit 项目.
* [ASunit](https://github.com/patternpark/asunit) - 唯一支持 Flash Player 6、7、8、9 和 10 的单元测试框架.
* [RobotEyes](https://github.com/Stray/RobotEyes)  - TDD 的端到端测试.  WindowLicker 和 Drew Bourne 的 Mockolate 的混合体.

## User Interface
#### UI Components

* [MinimalComps](https://github.com/minimalcomps/minimalcomps) - 用于 Flash 的最小 ActionScript 3.0 UI 组件.
* [MadComponents](https://github.com/danfreeman/MadComponents) - 适用于 AS3 / AIR 的流行移动 UI 框架.
* [AsWing](https://github.com/dreamsxin/AsWing) - 开源 Flash ActionScript GUI 框架.
* [GPUI](https://github.com/inspirit/GPUI) - 基于 Stage3D (GPU) 的微型 GUI 库.
* [Falcon](https://github.com/HendrixString/Falcon) - Feathers 的响应式/灵活的移动 ui 控件.
* [Flex-maps](https://github.com/igorcosta/flex-maps) - Apache Flex 中地图的最终解决方案.
* [FlexBook](https://github.com/blvz/FlexBook) - 很棒的 Flex 页面翻转组件.
* [Flex-Android-Material-Skins](https://github.com/quick6black/flex-Android-Material-Skins) - 适用于 Flex Mobile 组件的 Android Material Design 皮肤.

#### Starling Components

* [TabbedApplication](https://github.com/pol2095/Feathers-Extension-Tabbed-Application) - 基于视图的导航模型，通过滑动导航选项卡.
* [DataGrid](https://github.com/pol2095/Feathers-Extension-DataGrid) - 显示带有列标题和平滑滚动的数据网格.
* [DataTree](https://github.com/pol2095/Feathers-Extension-Tree) - 显示排列为可扩展树的分层数据.
* [Canvas](https://github.com/pol2095/Feathers-Extension-Canvas) - 支持基本的矢量绘图功能.
* [CircleProgress](https://github.com/pol2095/Feathers-Extension-CircleProgress) - 使用径向进度条显示进度.
* [ZoomableControl](https://github.com/pol2095/Feathers-Extension-ZoomableControl) - 允许使用多点触控输入进行缩放.
* [Toaster](https://github.com/pol2095/Feathers-Extension-Toaster)  - 在一个小弹出窗口中关于操作的简单反馈.  .
* [Google Maps](https://github.com/ZwickTheGreat/feathers-maps) - 适用于 Starling 的 Google 地图，针对移动设备进行了优化.

#### Layout

* [Adobe TLF](https://github.com/apache/flex-tlf) - Adob​​e/Apache Flex 文本布局框架 (TLF).
* [TinyTLF](https://github.com/joelhooks/tinytlf) - 基于 Flash/Flex 的 Flash 文本引擎构建的多功能文本布局框架.
* [TransformManager](https://greensock.com/TransformManager)  - 格林索克.  DisplayObjects 的交互式缩放/旋转/移动.
* [TransformTool](https://github.com/senocular/TransformTool) - 用于在 2D 空间中操作对象的免费变换工具（AS、JS）.
* [Argilla-Mosaic](https://github.com/folletto/Argilla-Mosaic) - 动态布局库.
* [xrope](https://github.com/evan-liu/xrope) - 原生 AS3 显示对象的简单布局库.
* [miglayout-as](https://github.com/develar/miglayout-as) - MigLayout 的端口，一个超级通用的 Flash/Flex/FlashCocoa (SWT/Swing/JavaFX) 布局管理器.

#### Multi Touch

* [TUIO Client](https://github.com/lagerkoller/tuio-as3) - 多点触控硬件通用框架，支持 TUIO/FLC 和 TUIO/TCP ([web](http://www.tuio.org/?flash)).
* [Gestouch](https://github.com/fljot/Gestouch) - 用于构建更好的自然用户界面的多点触控手势识别库.
* [Gestures.IO](https://github.com/GesturesIO/gesturesio-as3) - 简化您创建基于手势的自然交互的方式.
* [TouchScript](https://github.com/TouchScript/TouchScript.as3) - 多点触控框架，可以更轻松地处理大型触控表面上的复杂手势交互.

#### Game Controllers

* [AS3dpad](https://github.com/duckleg/as3dpad) - 专为 Adob​​e AIR Mobile (Android/iOS) 设计的虚拟触摸屏游戏手柄.
* [Gamepad](https://github.com/iainlobb/Gamepad) - 使用键盘模拟模拟操纵杆输入.
* [Advanced_Joystick](https://github.com/justjoeyuk/Advanced_Joystick) - Starling Framework 的操纵杆，专为 Adob​​e AIR Mobile 设计.
* [AS3-Controller-Input](https://github.com/arkeus/as3-controller-input) - 与 Adob​​e AIR 的 Ouya 和 Xbox360 游戏控制器交互.

## Multimedia

#### Augmented Reality

* [FLARToolKit](https://github.com/Saqoosha/FLARToolKit) - 行业标准 ARToolkit 库的 AS3 端口，用于 Flash Player 11.（[website](http://www.libspark.org/wiki/saqoosha/FLARToolKit/en)).
* [FLAREmulator](https://github.com/theflashbum/FLAREmulator) - 测试 AR 演示，看看有无网络摄像头哪些有效，哪些无效.
* [FLARManager](http://words.transmote.com/wp/flarmanager/) - 用于构建增强现实应用程序的轻量级框架，使用 FLARToolkit/flare.tracker/flare.NFT.
* [NyARToolkitAS3](https://github.com/nyatla/NyARToolkitAS3)  - NyARToolkit AS3 版. 基于标记的增强现实库.
* [EZFLAR](https://github.com/tcha-tcho/EZFLAR) - 一个小包装来简化 AR 的工作方式.
* [IN2AR](https://github.com/inspirit/IN2ARSDKExamples) - 适用于 IN2AR 跨平台增强现实引擎的 SDK.

#### Data Visualization

* [Axiis](https://github.com/hgupta9/AxiisCharts) - 具有线、条、楔、柱、簇、区域、史密斯和树形图的数据可视化框架.
* [Open Flash Charts](https://sourceforge.net/projects/openflashchart/) - 折线图、面积图、条形图、饼图、散点图.
* [Flare](https://github.com/prefuse/Flare) - 图表和图形，支持数据管理、视觉编码、动画和交互技术.
* [clearmaps](https://github.com/sunlightlabs/clearmaps) - 数据可视化的映射框架.
* [redada](https://github.com/geraldo/redada) - 使用 GraphML 文件对加权图进行交互式可视化.
* [Flextreemap](https://github.com/joshtynjala/flextreemap) - Adob​​e Flex 的 TreeMap 数据可视化组件.
* [GraphVisualizer](https://github.com/armisael/GraphVisualizer) - 用于绘制动态图形的 Flex 3 + ActionScript 3 网络软件.
* [Weave](https://github.com/WeaveTeam/Weave) - 基于网络的分析和可视化环境.
* [Social-grid](https://github.com/Instrument/social-grid) - 社交媒体的抽象网格可视化.

#### Camera

* [CameraDetection](https://github.com/cataclysmicrewind/CameraDetection) - 相机检测.
* [Fluocam](https://github.com/Fluocode/Fluocam) - Starling 应用程序的虚拟相机.
* [WebcamRecorder](https://github.com/Stupeflix/WebcamRecorder) - 从网络摄像头录制无铬视频/音频/静止图像.
* [FlashyWrappers](https://github.com/rainbowcreatures/FlashyWrappers) - 从 Windows/Android/iOS/OSX 上的 AIR 应用程序录制视频.

#### Image

* [Scale9Image](https://github.com/Tibus/Scale9Image) - 优化了八哥的 scale9Grid 图像.
* [ASImageLib](https://github.com/terrynoya/ASImageLib) - 动作脚本的 BMP/PNG 解码器.
* [Async-Image-Encoders](https://github.com/LeeBurrows/Async-Image-Encoders) - 将 BitmapData 对象异步编码为图像文件格式.
* [Flip-Planes-AS3](https://github.com/jamesflorentino/Flip-Planes-AS3) - 照片幻灯片效果.
* [AS3-transitions-lib](https://github.com/foo123/as3-transitions-lib) - 图像过渡库.
* [Inspirit Image](https://github.com/hgupta9/InspiritImage) - FFT、SURF、边缘检测、流体求解器等.
* [Inspirit GPUImage](https://github.com/inspirit/GPUImage) - 基于 GPU 的图像处理框架.
* [AS3potrace](https://github.com/PowerflasherBR/as3potrace) - POTrace 实现，将位图图像跟踪到矢量.
* [ATF-Encoder](https://github.com/plepers/ATF-Encoder) - 在纯 AS3 中编码/解码 ATF（Adobe 纹理格式）文件.
* [AS3-klt](https://github.com/motemen/as3-klt) - Kanade-Lucas-Tomasi 特征跟踪器实现.
* [BlurHash](https://github.com/roipeker/as3-blurhash) - ActionScript 3.0 中的 BlurHash 编码器/解码器实现.

#### Font

* [Firetype](https://github.com/MaxDidIt/firetype) - 解析 OpenType 字体并使用 Stage3D 渲染它们.
* [BMFontRenderer](https://github.com/bengarney/BMFontRenderer) - BMFont 格式的位图字体数据的 AS3 渲染器.
* [HanFont](https://github.com/kyoji2/HanFont) - 用于在 ActionScript 中嵌入中文字体的 AIR 应用程序.
* [Ficon.as](https://github.com/dv/Ficon.as) - 轻松包含图标字体的库.

#### Particle

* [Flint](https://github.com/richardlord/Flint) - Flash 和 Flex 的粒子引擎.
* [Desuade Partigen](http://desuade.com/partigen) - Desuade Partigen 粒子生成系统（[github](https://github.com/andrewfitz/desuade)).
* [Angulex](https://github.com/cosmindolha/ParticleDesigner) - Starling 框架的粒子设计器（ActionScript 3）.
* [SAP](https://github.com/gonchar/SAP) - Starling 的粒子系统.
* [Starling-Particles](https://github.com/Gamua/Starling-Extension-Particle-System) - Starling 框架的粒子系统，与 71squared.com 的“粒子设计器”兼容.
* [MotionParticleSprite](https://github.com/bjeld/motionparticlesprite) - 在 Flash Pro 中设计运动路径并使用它来引导 Starling 粒子.

#### Panorama Viewer

* [Pantaloons](https://github.com/EyeSee360/Pantaloons) - 在 Flash Player 中全景查看.
* [SaladoPlayer](https://github.com/mstandio/SaladoPlayer) - 全景查看器.
* [PanoramicViewer](https://github.com/BrianMehrman/PanoramicViewer) - 3D 全景查看器.
* [Sphere_panorama](https://github.com/suzumura-ss/flash_sphere_panorama) - 具有用 AS3 (Alternativa3D) 编写的 equirectangular 纹理的全景播放器.
* [CuTy](https://github.com/fieldOfView/CuTy) - 基于 Flash 10 的 QTVR 全景查看器.

#### QR Code

* [Zxing AS3](https://github.com/zxing/zxing/tree/c1df162b95e07928afbd4830798cc1408af1ac67/actionscript) - 二维码检测和生成（[docs](https://zxing.github.io/zxing/)).
* [AS3-qrcode-encoder](https://github.com/jbpin/as3-qrcode-encoder) - as3中的二维码编码器.
* [qrcode-as](https://github.com/yanbe/qrcode-as) - 二维码阅读器，支持 Windows、Mac 和 Linux 上的网络摄像头.

#### Sound

* [SoundAS](https://github.com/treefortress/SoundAS) - 适用于 AS3 的现代轻量级声音管理器.
* [Standingwave3](https://github.com/maxl0rd/standingwave3) - 动态音频库.
* [Standingwave3-addons](https://github.com/charlesclements/standingwave3-addons) - SW3 的插件.
* [Soundtouch-as3](https://github.com/also/soundtouch-as3) - SoundTouch 声音处理库的 AS3 端口.
* [SeiON](https://github.com/cardin/SeiON) - 声音管理库.
* [AS3-Sound-Manager](https://github.com/GrupoW/as3-Sound-Manager)- Matt Przybylski 的声音管理器类的升级版.
* [AS3sfxr](https://github.com/SFBTom/as3sfxr) - 将 sfxr 从 C++ 移植到 AS3，使用 Flash Player 10 的新声音和文件功能.
* [AS3-audio](https://github.com/singuerinc/as3-audio) - Actionscript 中的音频管理.
* [SiON](https://github.com/keim/SiON) - Flash 软件合成器.
* [FlashWavRecorder](https://github.com/michalstocki/FlashWavRecorder) - Recording audio and saving as a WAV.
* [Local-recorder](https://github.com/pauln/local-audio-recorder)  - 本地录音机（无需流媒体服务器）. 目前需要 Flash Player 10.1 或更高版本.
* [Jukebox](https://github.com/AlwynW/Jukebox) - Actionscript 3 项目的音乐经理.
* [Flod](https://github.com/photonstorm/Flod) - Amiga SoundTracker (MOD) 和 FastTracker (XM) 回放库.

#### Video Player

* [Flowplayer](https://github.com/flowplayer/flash) - Flowplayer Flash，网络视频播放器.
* [Goplayer](https://github.com/dbrock/goplayer) - 用 ActionScript 3 编写的现代开源视频播放器.
* [OSFlashVideoPlayer](https://github.com/FlashJunior/OSFlashVideoPlayer) - 开源 Flash 视频播放器.
* [F4player](https://github.com/gokercebeci/f4player) - 开源 AS3 Flash 视频播放器.
* [dashas](https://github.com/castlabs/dashas) - 用 ActionScript 编写的 MPEG-DASH 播放器.
* [hlsplayer](https://github.com/erlyvideo/hlsplayer) - OSMF flash 框架的 HLS 播放器.
* [vgaplayer](https://github.com/euske/vgaplayer) - Adob​​e Flash Media Server 流 (RTMP) 的开源播放器.

## Database

#### SQLite
* [AS3Query](https://github.com/kemsky/as3Query) - ActionScript 的另一个 SQLite ORM 和查询 DSL.
* [AIRdb](https://github.com/dkeskar/airdb)  - AIR ORM 用于在 AIR 和 Flex 应用程序中使用客户端 SQLite. 支持 ActiveRecord 风格的模型、迁移和关联.
* [Flexine](https://github.com/riadvice/Flexine) - 用于 AIR 的 SQLite ORM.
* [AIR-sqlite](https://github.com/probertson/air-sqlite) - 在 AIR 中使用 SQLite 数据库的实用程序.

#### MongoDB
* [MongoAS3](https://github.com/s9tpepper/MongoAS3) - MongoDB 驱动程序.
* [ActionMongo](https://github.com/RIAlizer/ActionMongo) - MongoDB 驱动程序.

#### CouchDB
* [AS3couchdb](https://github.com/bustardcelly/as3couchdb) - 用于与 CouchDB 实例交互的客户端 API.
* [Soup](https://github.com/dima/soup) - 混合 CouchDB、Sinatra、AIR 和 RestfulX 以创建具有撤消/重做功能的离线/在线就绪应用程序.

#### MySQL
* [AS3mysql](https://github.com/hgupta9/as3mysql) - MySQL 开源数据库的驱动程序.

#### PostgreSQL
* [Pegasus](https://github.com/uhoh-itsmaciek/pegasus) - PostgreSQL 开源数据库的驱动程序.

#### DynamoDB
* [AWS-dynamodb](https://github.com/ferf/aws-dynamodb-actionscript) - 用于访问亚马逊 AWS DynamoDB 的驱动程序.

#### Redis
* [AS3redis](https://github.com/zhangq0355/as3redis) - Redis 驱动程序.

## File Formats

#### Archives

* [FZip](https://github.com/claus/fzip) - 加载、修改和创建标准 ZIP 档案的成熟库.
* [ASZip](https://code.google.com/archive/p/aszip/) - 从 AS3 生成 ZIP 档案.
* [Untar-Worker](https://github.com/mesmotronic/as3-worker-untar) - 使用 AS3 Worker（后台线程）提取 TAR.

#### 3D Formats

* [AsCollada](https://github.com/timknip/ascollada) - 解析 COLLADA 3D 模型行（[fork](https://github.com/david-gregory/ascollada)).
* [AsBlender](https://github.com/timknip/asblender) - 解析 Blender .BLEND 文件.
* [AS3-bvh-parser](https://github.com/rkn14/as3-bvh-parser) - 解析 BVH 文件.
* [EasyAGAL](https://github.com/Barliesque/EasyAGAL) - 通过代码完成、代码提示、宏等简化 AGAL 着色器的开发.

#### CSV

* [CSV4AS3](https://github.com/lizardon/CSV4AS3) - 从 Apache Commons CSV 移植的 CSV 库.
* [Csvlib](https://github.com/51systems/csvlib) - CSV 解析器.

#### CSS

* [AS3csslib](https://github.com/heyfrench/as3csslib) - ActionScript 3.0 的 CSS3 解析器、选择器和样式引擎.
* [Fcss](https://github.com/theflashbum/fcss) - Flash 级联样式表库.
* [Stylekit-as3](https://github.com/videojuicer/stylekit-as3) - 使用 CSS3 的可换肤用户界面.
* [Sass4as](https://github.com/jeremyruppel/sass4as) - ActionScript 3 的语法很棒的样式表.
* [Jakute-CSS](https://github.com/kakenbok/Jakute-Styling-Engine) - Jakute 是 ActionScript/Flash 的 CSS 框架.
* [CSS.as](https://gist.github.com/trxcllnt/1161266) - 单文件 CSS 解析器，TinyTLF 项目的一部分.

#### BSON

* [ActionBSON](https://github.com/fminzoni/ActionBSON) - BSON 数据编码器/解码器.
* [MongoAS3](https://github.com/s9tpepper/MongoAS3) - 包括 BSON I/O 的 MongoDB 驱动程序.

#### EXIF

* [AS3-exif-lib](https://github.com/unstoppable/actionscript-exif-reading-lib) - 解析 JPEG EXIF 数据.
* [Exif-as3](https://github.com/bashi/exif-as3) - 解析 JPEG EXIF 数据.

#### FXG

* [Fxg-as3-lib](https://github.com/pixelami/fxg-as3-lib) - 纯 AS3 FXG 渲染库（支持运行时渲染和 mxml）.
* [Fxg2as3](https://github.com/ZackPierce/fxg2as3) - 将 FXG 标记转换为可执行的 Actionscript 3 代码.

#### GIF

* [AS3gif](https://github.com/audreyt/as3gif) - 播放和编码动画 GIF.
* [GIF Player](https://github.com/theturtle32/Flash-Animated-GIF-Library) - 在 Flash 中播放动画 GIF.
* [Async-gif-decoder](https://github.com/honzabrecka/async-gif-decoder) - 异步 GIF 解码器和播放器.

#### ICAL

* [AS3iCAL](https://github.com/nicolai86/as3.iCal) - iCal 解析器基于 RFC2445 规范.

#### JSON

* [Actionjson](https://github.com/mherkender/actionjson) - 更快、更高级的 ActionScript 3 JSON 库.
* [Jameson](https://github.com/mattupstate/jameson) - JSON 文档对象映射器.
* [Serialkiller](https://github.com/benbjohnson/serialkiller) - JSON &amp; XML 序列化库.
* [JsonMapper](https://github.com/kemsky/JsonMapper) - 类型化的 JSON 解析器.
* [JSONTools](https://github.com/s9tpepper/JSONTools) - JSON 错误、JSWoof JSON 库的速度以及称为 E4J 的 E4X 样式查询.

#### Markdown

* [Showdown.as](https://gist.github.com/cstrahan/648771) - showdown.js 的端口.
* [Actiondown](https://github.com/bbeaumont/Actiondown) - Javascript Showdown 的端口.
* [Markdownlib](https://github.com/Corsaair/markdownlib) - Implementation of Markdown.

#### MP3

* [AS3id3lib](https://github.com/devxoul/as3id3lib) - 解析 MP3 ID3 数据.
* [AS3Icy](https://github.com/claus/as3icy) - 解码和播放来自 Shoutcast、Icecast 和 Limewire 的实时 MP3 流.

#### PDF

* [AlivePDF](https://code.google.com/archive/p/alivepdf/) - 客户端PDF生成（[github](https://github.com/riadvice/alivepdf)).
* [PurePDF](https://github.com/sephiroth74/purePDF) - 完整的 PDF 库，Java iText 的端口.
* [HalcyonPDF](https://github.com/systemed/halcyon_pdf) - OpenStreetMap PDF 渲染器.
* [PDFCase](https://github.com/dickclaus/pdfcase) - PDF 库.
* [PDFView](https://github.com/jankapunkt/PDFView) - 从头开始​​构建的 PDF 查看器.

#### PSD

* [AS3-psd-parser](https://github.com/warrenseine/as3-psd-parser) - 解析 Photoshop PSD 文件并渲染为 BitmapData 对象.

#### SWF

* [AS3swf](https://github.com/claus/as3swf) - 用于解析、创建、修改和发布 SWF 文件的低级库.
* [AS3abc](https://github.com/imcj/as3abc) - 用于解析、创建、修改和发布 ABC（Actionscript 块代码）文件的低级库.
* [SWFWire](https://github.com/magicalhobo/SWFWire) - SWF 反编译器和检查器工具.
* [Abc-abstraction](https://github.com/krilnon/abc-abstraction) - 允许对 ABC 进行分析、操作、打包回 SWF 并运行.

#### SVG

* [AS3SVGRenderer](https://github.com/LucasLorentz/AS3SVGRenderer) - 用于 Flash Player 的 SVG 渲染器.
* [SVGParser](https://github.com/millermedeiros/SVGParser) - SVG 解析器和渲染器到 FIVe3D 和 HTML5 画布.

#### XML

* [XMLSerializer](https://github.com/vapesolius/XMLSerializer) - 允许从 ActionScript 到 XML 以及从 XML 到 ActionScript 的数据序列化的库.
* [Nudge](https://github.com/pluglimited/Nudge) - 将对象序列化/反序列化为 XML 的框架.
* [AStream](https://github.com/kokorin/AStream)  - 用 AS3 编写的 XML 到对象（反之亦然）映射库. 与 XStream 兼容.

#### XLSX

* [AS3-xlsx-reader](https://github.com/childoftv/as3-xlsx-reader) - 解析 Open XML Excel (.XLSX) 或 Open Office 电子表格.


## Networking
#### Data Loader

* [GreenSock LoaderMax](https://github.com/greensock/GreenSock-AS3) - 提供了一种在运行时加载资产的简单而强大的方法.
* [BulkLoader](https://github.com/arthur-debert/BulkLoader) - Actionscript 的批量资产加载库.
* [AssetLoader](https://github.com/Matan/AssetLoader) - 基于 AS3Signals 的 AS3 多文件/资产加载器.

#### Hardware

* [AS3midilib](https://github.com/heyfrench/as3midilib) - 使用 MIDI 文件和 MIDI 输入/输出设备.
* [AS3glue](https://code.google.com/archive/p/as3glue/) - Arduino 板的通信.
* [AS3-arduino](https://github.com/quetwo/as3-arduino-connector) - 将 Arduino 原型板连接到 Adob​​e AIR.
* [AIRkinect](https://github.com/AS3NUI/airkinect-2-core)  - 用于与 Microsoft Kinect 集成的 ANE.  ([examples](https://github.com/AS3NUI/airkinect-2-examples)).
* [KinectGate](https://github.com/cleoag/KinectGate) - KinectSDK 到 AS3 插座门.
* [Kinect-Gestures](https://github.com/tonybeltramelli/Air-Kinect-Gesture-Lib) - AIR Kinect 手势库.
* [OpenTSPS](https://github.com/labatrockwell/openTSPS)  - TSPS 是用于感知空间人员的跨平台工具包. 它对实时视频（Kinect、网络摄像头等）执行 openCV 操作，并将其作为 JSON（通过 WebSockets）、OSC、TUIO 或 TCP 发送到客户端.
* [LeapMotionAS3](https://github.com/logotype/LeapMotionAS3) - 与 LeapMotion 传感器集成（提供手势、图像、骨骼/骨骼 @ 210 FPS）.

#### Servers

* [AIRhttp](https://github.com/leopoldodonnell/airhttp) - Adob​​e AIR 的 HTTP 服务器.
* [AIR-Server](https://github.com/wouterverweirder/AIR-Server) - Adob​​e AIR 的套接字服务器库.

#### OAuth

* [Actionscript-oauth2](https://github.com/charlesbihis/actionscript-oauth2) - 与 OAuth 2.0 服务交互.
* [oauth-flex](https://github.com/oauth-io/oauth-flex) - 用于 Apache Flex/ActionScript 的 OAuth.io 插件.
* [oauth-as3](https://github.com/mlepicki/oauth-as3) - Mavenized，RSL 版本的 oauth-as3 库 - ActionScript 3 的 OAuth.

#### HTTP

* [Hendrix-HTTP](https://github.com/HendrixString/Hendrix-HttP-AiR) - 受 Square 的 OkHttp 启发的用于 ActionScript 3 (as3) 的轻量级 HTTP 库.
* [HTTPForm](https://github.com/dv/HTTPForm) - 模拟多部分/表单数据 HTML 表单提交请求，包括文件上传.
* [AS3httpclient](https://github.com/abdul/as3httpclient) - HTTP 客户端实现.
* [AS3httpclient](https://github.com/gabriel/as3httpclient) - HTTP 客户端实现.
* [Amazon Web Services](https://github.com/satoshi7/ActionScript-API-for-AWS-Amazon-Web-Services-) - 适用于 AWS 的 AS3 API.

#### P2P

* [P2Plocal](https://github.com/palkan/as3_p2plocal) - 本地 RTMFP 连接.
* [Android-Flash-P2P](https://github.com/beautifycode/Android-Flash-P2P) - Client.swf 和带有 AIR 的 Android 设备之间的 P2P 通信.
* [NetGrouper](https://github.com/walpolea/NetGrouper) - 用于 NetGroup 和 RTMFP 多播功能的包装器，可通过本地网络或 Adob​​e Cirrus 创建快速的 P2P 多人游戏.
* [HydraP2P](https://github.com/devboy/HydraP2P) - 简化了 Flash Player 10.1 中引入的点对点 API.
* [GroupP2P](https://github.com/oohazard/GroupP2P) - 基于 P2P 的网络组.
* [HLS-P2P](https://github.com/lava-tech/hls-p2p) - 基于 Flash OSMF 的混合 cdn&amp;p2p hls 解决方案.
* [P2Pmessaging](https://github.com/dreamsocket/actionscript-p2p_messaging) - 在 Flash 中进行 P2P 的简单消息传递框架.
* [ArcusNode](https://github.com/OpenRTMFP/ArcusNode) - RTMFP Rendevouz 服务，用于在 Node JS 上使用 Adob​​e Flash 进行对等辅助网络.

#### Sockets

* [AS3WebSocket](https://github.com/theturtle32/AS3WebSocket) - 最终 WebSocket Draft RFC6455 的 WebSocket 客户端实现.
* [SmartSocket](https://github.com/XaeroDegreaz/SmartSocket) - SmartSocket 是一个 Java 和 PHP 套接字服务器引擎，可以快速轻松地创建多用户应用程序.
* [FlashSocket.IO](https://github.com/simb/FlashSocket.IO) - 客户端从 AS3/AIR 客户端连接到 Socket.IO 服务器.
* [Socket.io](https://github.com/ascorbic/socket-io-actionscript) - Socket.IO Actionscript 3 客户端.
* [AMFsocket](https://github.com/chadrem/amf_socket) - 用于高性能网络通信的双向 RPC 库.
* [Sockpuppet](https://github.com/rjungemann/sockpuppet) - 使用 AMF 完成 Ruby/ActionScript 套接字客户端/服务器.
* [Socket.io-flash](https://github.com/sinnus/socket.io-flash) - 与 Socket.IO v.0.8+ 服务器的通信.
* [ws-flash-client](https://github.com/youurayy/ws-flash-client) - 可靠的简约 WebSocket 客户端（在本地 WebSocket 不可用的情况下使用 Adob​​e Flash）.

#### Protocols

* [GIT](https://github.com/nexussays/git-as3) - Git 的客户端实现.
* [AIRplay](https://github.com/mikkoh/AS3-Airplay) - Client-side implementation of Apple's Airplay.
* [TeaTime](https://github.com/aemoncannon/croqodile) - Croquet 项目的 TeaTime 协议的 AS3/Erlang 实现.
* [XMPP](https://github.com/lyokato/as3xmppclient) - XMPP 库的客户端实现.
* [XMPP](https://github.com/bluef/kuching) - XMPP 库的轻量级实现.
* [AMQP](https://github.com/0x6e6562/as3-amqp) - AMQP 0-8 版本的客户端实现.
* [NTP](https://github.com/charlespalen/AS3-NTP-Implementation) - NTP 客户端（网络时间协议）的客户端实现.
* [FUDI](https://github.com/matthiasbreuer/FUDI-as3) - Puredata FUDI 协议的客户端实现.
* [BDD Cucumber](https://github.com/flashquartermaster/Cuke4AS3) - Flash ActionScript 的 BDD Cucumber 有线协议实现.

#### Email

* [AIRXMail](https://github.com/hgupta9/AirXMail) - 完整的客户端电子邮件库，支持 SMTP、POP3 和 IMAP4.
* [AS3Mailer](https://github.com/Matan/AS3Mailer) - 使用服务器脚本发送电子邮件或调用 mailto.

## Utilities

#### Artificial Intelligence

* [FiniteStateMachine](https://github.com/pzUH/FiniteStateMachine) - 人工智能机器人/代理的有限状态机.
* [N-GramPredictor](https://github.com/pzUH/N-GramPredictor) - 人工智能机器人/代理的 n-Gram 预测器.
* [Naive-BayesPredictor](https://github.com/pzUH/Naive-BayesPredictor) - AI 机器人/代理的朴素贝叶斯预测器.
* [HierarchicalStateMachine](https://github.com/pzUH/HierarchicalStateMachine) - 用于 AI 机器人/代理的分层状态机.
* [Godmode-as3](https://github.com/tconkling/godmode-as3) - 行为树实现（人工智能）.
* [DecisionTree](https://github.com/pzUH/DecisionTree) - 人工智能机器人/代理的二元决策树.
* [FuzzyStateMachine](https://github.com/pzUH/FuzzyStateMachine) - 用于 AI 机器人/代理的模糊状态机 (FuSM).
* [SmartKid](https://github.com/skyfeiyun/SmartKid) - 用于 2D 和 3D 游戏的强大 AI 引擎.

#### Async

* [EasyAS-Worker](https://github.com/myflashlab/easyAS-Worker) - AIR Worker 的简化包装.
* [Worker-from-class](https://github.com/bortsen/worker-from-class) - 从类定义创建工人.

#### Crypto

* [BlooddyCrypto](https://github.com/blooddy/blooddy_crypto)  - 用于处理二进制数据的高性能库. 该库包含 MD5、SHA-1、SHA-2、Base64、CRC32、JSON、PNG/JPEG 编码器.
* [AS3Crypto](https://github.com/timkurvers/as3-crypto) - Henri Torgemane 优秀密码库的分叉（[patched](https://github.com/lyokato/as3crypto_patched)).
* [AS3corelib](https://github.com/mikechambers/as3corelib) - MD5 和 SHA1 散列、图像编码器和 JSON 序列化.
* [ASCrypt](https://github.com/Meychi/ASCrypt) - 具有用于多种语言的类似 API 的加密库.
* [Nexuslib](https://github.com/nexussays/nexuslib-as3) - 反射、序列化、种子随机数生成、密码学、网络等.
* [Hashlib](https://github.com/Corsaair/hashlib) - 超过 30 种不同的散列函数.
* [XXTEA-AS3](https://github.com/xxtea/xxtea-as3) - 适用于 ActionScript 3 的 XXTEA 加密算法库.
* [Gibberish-AES](https://github.com/NordMike/gibberish-aes-as3) - 用于 AES 加密的完全符合 OpenSSL 的 ActionScript 3 库.

#### Data	

 * [AS3Commons Collections](https://github.com/AS3Commons/as3commons-collections) - 用于 AS3 的复杂且高性能的集合和迭代器.
 
#### Geometry

* [AS3geometry](https://github.com/alecmce/as3geometry) - 基元、多边形、交叉点等.
* [AS3GeomAlgo](https://github.com/azrafe7/as3GeomAlgo)  - 几何算法的集合.  hxGeomAlgo 的端口.
* [Coral](https://github.com/richardlord/Coral) - 3D 数学的高性能课程（点、向量、矩阵、四元数）.
* [Csg.as](https://github.com/timknip/csg.as) - 3D 网格上的构造实体几何.
* [PathUtils](https://github.com/alinakipoglu/Actionscript-PathUtils) - 使用二次、贝塞尔曲线和线序列.
* [Hilbert](https://github.com/nodename/Hilbert) - 来自 cortesi/scurve 的希尔伯特曲线端口.
* [AS3AStar](https://github.com/tomnewton/AS3AStar) - 快速 A-Star 寻路算法.
* [A-star_pathfinder](https://github.com/kevhiggins/a-star_pathfinder) - 基于图块的地图的 A-Star 寻路界面.
* [As3Pathfinder](https://github.com/azakhary/As3Pathfinder) - 使用 Dijkstra 算法编写的网格路径查找库.

#### Math

* [AS3Units](https://github.com/erussell/AS3Units)  - NGUnits 端口. 测量单位之间的解析、格式化和转换.
* [AS3LinAlg](https://github.com/inspirit/AS3LinAlg) - 线性代数库（Jacobi SVD、特征向量/值、Cholesky LU 等）.
* [Performance Primitives](https://github.com/martinkallman/performance-as3) - 以英特尔性能原语为模型的高性能数学.
* [Zexpression](https://github.com/Xorcerer/zexpression) - 使用函数和变量解析和评估数学表达式.
* [FlexibleMatrix](https://github.com/Lukx/FlexibleMatrix) - 一个多用途的矩阵类.
* [AS3eval](http://eval.hurlant.com/)  - 打包 Tamarin ESC 编译器以在 Flash Player 中工作.  ([alternate](https://github.com/SimonRichardson/as3-eval)).
* [FlashFormulaEditor](https://github.com/zasdfgbnm/FlashFormulaEditor) - 用 Adob​​e Flex 制作的公式编辑器.

#### Text

* [Linkify-as3](https://github.com/CodeCatalyst/linkify-as3) - 将 URL、电子邮件地址、电话号码转换为可点击的链接.
* [AS3hyphenation](https://github.com/gka/as3hyphenation) - Javascript 文本连字库 Hyphenator.js 的端口.

## Runtimes

#### Emulators

* [NES Emulator](https://github.com/nesbox/emulator) - NES、Super Nintendo、Sega Mega Drive、GameBoy 视频控制台的模拟器.
* [Commodore 64 Emulator](https://github.com/claus/fc64) - 用 Actionscript 3 编写的低级 Commodore 64 模拟器.
* [8080 Emulator](https://github.com/ozipi/As3_SpaceInvaders_Emulator) - 基于英特尔 8080 处理器的 actionscript 3 太空侵略者模拟器.
* [8-bit VM](https://github.com/OutOfTheVoid/AS3-8-bit-VM) - 一个用 actionscript 编写的 8 位虚拟机.

#### Interpreters

* [JS](https://github.com/theturtle32/RhinoAS3) - RhinoJS，Mozilla 的 Rhino JavaScript 解释器端口.
* [Simple JS](https://github.com/sixsided/Simplified-JavaScript-Interpreter) - 基于 AS3 的 Javascript 解释器.
* [MIL](https://github.com/ser1zw/MIL) - 用 ActionScript 编写的 MIL 语言 VM 和解释器.
* [TALES](https://github.com/oaubert/tales4as) - ActionScript 的 TALES 解释器.
* [Scheme](https://github.com/hrundik/fScheme) - ActionScript 中的方案解释器.
* [Lisp](https://github.com/rzubek/as_lisp) - 用 Actionscript 编写的 Lisp 方言，带有编译器和字节码解释器.
* [Lisp Compiler](https://github.com/aemoncannon/las3r) - AVM2 的 lisp 编译器.
* [CannonML](https://github.com/abiyasa/cannonml_as3) - keim 的 CannonML（shmup 脚本语言）解释器.

## AIR Native Extensions

#### Audio ANE
* [SongPicker](https://github.com/richpixel/SongPickerANE) - 适用于 iOS 和 Android 的歌曲选择器/播放器 ANE.
* [SilentSwitch](https://github.com/StickSports/ANE-Silent-Switch) - 如果硬件静音开关打开，iOS 的 ANE 可以静音.
* [VolumePro](https://github.com/myflashlab/VolumePro-ANE) - 控制原生音乐流音量，您可以收听音量变化.
* [SystemVolume](https://github.com/nweber/SystemVolumeNativeExtension) - 与 iOS 和 Android 设备的系统音量交互.

#### Multimedia ANE
* [WebView (Tuarua)](https://github.com/tuarua/WebViewANE)  - 适用于 OSX 10.10+、Windows 桌面、iOS 9.0+ 和 Android 21+ 的现代 WebView. 在 Windows 上使用 CEF（Chromium Embedded Framework），在 iOS/OSX 上使用 WKWebView，在 Android 上使用 WebView.
* [WebView (FlashLab)](https://github.com/myflashlab/webView-ANE) - 替换 StageWebView，允许从 AIR 调用 Javascript 函数.
* [AVANE](https://github.com/tuarua/AVANE) - 用于使用 FFmpeg 构建视频编码应用程序.
* [PDF](https://github.com/myflashlab/PDF-ANE)  - 允许您从 AIR 移动应用程序打开 PDF 文件. 支持 Android 和 iOS.
* [VideoPlayer](https://github.com/myflashlab/videoPlayer-ANE) - 在 Android 或 iOS 原生视频播放器中播放视频文件.
* [SurfaceVideoPlayer](https://github.com/myflashlab/surfaceVideoPlayer-ANE) - SurfacePlayer ANE 可帮助您在空中移动项目中播放视频文件.
* [Speech](https://github.com/myflashlab/speech-ANE) - 在后台完全将字符串转换为语音文件，反之亦然.
* [MyAR](https://github.com/myflashlab/AR-ANE-Samples) - AR ANE 基于 Metaio 的 SDK 支持 Android 和 iOS 64 位.
* [QR-zbar](https://github.com/saumitrabhave/qr-zbar-ane) - 用于 QR 码阅读器的 ANE.
* [Barcode](https://github.com/myflashlab/barcode-ANE) - 使用这款超快速条码扫描仪 ANE 扫描几乎所有类型的条码.
* [Bullet](https://github.com/mziwisky/bullet-ane) - 子弹物理模拟库.

#### File System ANE
* [FileChooser](https://github.com/myflashlab/fileChooser-ANE) - 使用户能够从设备文件系统中选择文件.
* [ZipManager](https://github.com/myflashlab/zipManager-ANE) - 在 Android 和 iOS 上使用本机进程超级快速地压缩或解压缩大型 zip 档案.

#### Networking ANE
* [Firebase](https://github.com/myflashlab/Firebase-ANE) - 适用于 Android 和 iOS 上的 Google Firebase 的 API，具有 100% 相同的 ActionScript API.
* [DownloadManager](https://github.com/myflashlab/downloadManager-ANE) - 下载带有暂停/恢复支持的大数据文件.
* [BitTorrent](https://github.com/tuarua/BitTorrentANE) - 用于构建支持 BitTorrent 的应用程序.

#### Hardware ANE
* [Bluetooth](https://github.com/myflashlab/bluetooth-ANE) - 扫描其他设备，连接并与它们配对并在它们之间传输数据.
* [GPS](https://github.com/myflashlab/GPS-ANE) - 通过自动检查可用的最佳提供商，尽快获取当前设备的 GPS 位置.
* [GoogleVR](https://github.com/myflashlab/GoogleVR-ANE) - AIR 开发人员可以使用 Google 虚拟现实 SDK.
* [Joystick-ANE](https://github.com/StackAndHeap/joystick-ane) - ANE 操纵杆库.
* [AIRControl](https://github.com/AlexanderOMara/AIRControl) - Adob​​e AIR 游戏控制器 ANE.
* [AIROUYAController](https://github.com/gaslightgames/AIROUYAController) - OUYA 控制器的 ANE.
* [AIRKinectv2](https://github.com/Tastenkunst/AIRKinectv2) - 适用于 Windows SDK 的 Microsoft Kinect v2 的 ANE.
* [Serial/MIDI/DMX](https://github.com/benkuper/AIR-NativeExtensions) - AIRBonjour、NativeSerial、NativeDMXController、NativeMIDI、VirtualMIDI、ExtendedMouse.
* [LeapMotionAS3](https://github.com/logotype/LeapMotionAS3) - LeapMotion 传感器的 ANE（提供手势、图像、骨骼/骨骼 @ 210 FPS）.

#### System ANE
* [TaskbarProgress](https://github.com/tuarua/TaskbarProgressANE) - 在 OSX 和 Windows 7/8/10 上显示任务栏进度.
* [DesktopToast](https://github.com/tuarua/DesktopToastANE) - 在 Windows 8/10 和 OSX 中显示交互式 toast 通知.
* [AlarmManager](https://github.com/myflashlab/alarmManager-ANE) - 即使您的 AIR 应用程序已关闭，也可以运行计划任务.
* [InAppPayments](https://github.com/myflashlab/inAppPayments-ANE) - 适用于 Android 和 iOS 的相同应用内计费和应用内购买 ANE.
* [PermissionCheck](https://github.com/myflashlab/PermissionCheck-ANE) - 在您的 Adob​​e Air 应用程序中检查并请求权限.
* [RateMe](https://github.com/myflashlab/RateMe-ANE) - 让您的用户以最有效的方式对您的应用进行评分.
* [Statusbar](https://github.com/myflashlab/Statusbar-ANE) - 在运行时控制 AIR 应用程序中的状态栏.
* [Badge](https://github.com/myflashlab/Badge-ANE) - 控制 iOS 徽章值.
* [WinDebug](http://www.henke37.cjb.net/windebug/) - Windows ANE 用于控制应用程序、窗口、内存、断点、元数据、注册表等.
* [Can-Open-URL](https://github.com/StickSports/ANE-Can-Open-URL) - 适用于 iOS 的 ANE 检测是否安装了应用程序以处理特定的 URL 方案.

#### Social ANE
* [Facebook](https://github.com/myflashlab/facebook-ANE) - 将 Facebook SDK 集成到您的 AIR 应用程序中.
* [GCM](https://github.com/myflashlab/GCM-ANE)  - 在 Android 和 iOS 上使用 Google Cloud 消息传递.  .
* [Baidu](https://github.com/lilili87222/baidu-ane-for-ios-and-android) - 适用于 iOS 和 Android 的百度 ANE.

#### Analytics ANE
* [Admob](https://github.com/myflashlab/Admob-ANE) - Admob ANE.
* [GameServices](https://github.com/myflashlab/GameServices-ANE) - 适用于 Android+iOS 的 Google 游戏服务.
* [MoPub](https://github.com/StickSports/MoPub-ANE) - 用于 MoPub 广告的 ANE.
* [UMAnalytics](https://github.com/ColerYu/ANE-UMAnalytics) - 用于 UMAnalytics SDK（iOS 和 Android）的 ANE.
* [Localytics](https://github.com/randori/ANE-Localytics) - 移动 Adob​​e AIR 应用程序（iOS 和 Android）的 Localytics 分析.
* [Testflight](https://github.com/jlopez/ane-testflight) - Apple TestFlight ANE.
* [HockeyApp](https://github.com/airext/hockeyapp) - 用于 Hockeyapp 测试和分发平台的 ANE.
* [Chartboost](https://github.com/ChartBoost/air) - 带有编译脚本的 Chartboost SDK 的 ANE.
* [Devtodev](https://github.com/devtodev-analytics/air-sdk) - 面向游戏开发者的全周期分析解决方案.
