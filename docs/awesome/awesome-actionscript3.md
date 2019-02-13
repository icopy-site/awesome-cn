[<img src="https://rawgit.com/hgupta9/awesome-actionscript3/master/AS3_AIR.png" align="right" width="150">](https://www.adobe.com/products/air.html)

## Awesome ActionScript 3 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; ActionScript 3和Adobe AIR的精选库和组件的精选列表.

[Adobe AIR](https://en.wikipedia.org/wiki/Adobe_AIR) 提供一组API来构建跨平台的桌面/移动应用程序和游戏. [ActionScript 3](https://en.wikipedia.org/wiki/ActionScript)  是AIR的编程语言.  默认情况下包含强大的本机功能，如文件系统，SQLite，传感器.  要添加缺少的功能，您可以构建以本机语言编码的ANE（Air Native Extensions）（例如，用于Windows的VC ++，用于Android的Java，用于iOS的Swift / Objective-C）.  要使用GPU渲染图形构建移动应用/游戏，请使用 [Starling](https://gamua.com/starling/) 框架和可选 [Feathers UI](https://feathersui.com/) .  Adobe AIR在移动游戏领域非常受欢迎.

 欢迎捐款.  要添加有用的项目，只需创建一个 [Issue](https://github.com/hgupta9/awesome-actionscript3/issues).

## Contents

* [Development Tools](#development-tools)
* [Frameworks](#frameworks)
* [User Interface](#user-interface)
* [Multimedia](#multimedia)
* [Database](#database)
* [File Formats](#file-formats)
* [Networking](#networking)
* [Utilities](#utilities)
* [Runtimes](#runtimes)
* [AIR Native Extensions](#air-native-extensions)
	

## Development Tools
*此部分包括商业工具以及免费/开源工具.*

#### Code Editors
* [FlashDevelop](http://flashdevelop.org/) - 用于AS3和AIR的Premiere免费和开源IDE，具有代码完成，调试等功能.
* [Powerflasher FDT](http://fdt.powerflasher.com/) - 基于Eclipse平台构建的商业IDE，用于开发Adobe Flash / AIR内容.
* [Adobe Flash Builder](https://www.adobe.com/products/flash-builder.html) - 用于在Flex框架上构建应用程序的商业IDE（使用高级调试工具）.
* [Moonshine IDE](http://moonshine-ide.com/) -  Moonshine是一个免费的开源中量级IDE，使用ActionScript 3构建，适用于ActionScript 3，ApacheFlex®，ApacheFlexJS®和Feathers开发，支持云和桌面.
* [IntelliJ IDEA](https://www.jetbrains.com/help/idea/building-actionscript-and-flex-applications.html) - 商业IDE，支持许多不同的语言，包括AS3

#### Live Debuggers
* [Adobe Scout](https://www.adobe.com/products/scout.html) -  AIR应用程序和游戏的高级可视化分析和调试工具（支持Stage3D）.
* [De-Monster Debugger](https://github.com/MrTact/monsterdebugger) - 用于调试实时AIR应用程序中的图形和数据的高级工具.
* [De-Monster Debugger (Starling)](https://github.com/joshtynjala/monsterdebugger-client-starling) - 支持Starling Framework的De-Monster调试器分支.

#### Asset Creators
* [Adobe Animate CC](https://www.adobe.com/products/animate.html) - 用于矢量/ spritesheet创建的首映矢量图形和动画工具集.
* [TILED Map Editor](http://www.mapeditor.org/) - 灵活的瓷砖地图编辑器兼容各种AS3游戏引擎.
* [FlashMovieClipConverter](https://github.com/zenrobin/FlashMovieClipConverter) - 将Flash MovieClip转换为Starling IAnimatable Sprite.

#### SWF Obfuscators
* [secureSWF](http://www.kindi.com/) - 具有重命名，资产加密和自动代码优化的商用AS3 / AIR混淆器.
* [irrFuscator](http://www.ambiera.com/irrfuscator/) - 用于Flash和Flex SWF文件的商用AS3混淆器.

#### SWF Inspectors
* [SWFWire](https://github.com/magicalhobo/SWFWire) - 高级SWF反编译器，检查器和调试器工具（[website](http://www.swfwire.com/)).
* [Velocity9](https://github.com/velocity9/Inspector) - 基本SWF检查员.

#### SWF Decompilers
* [AS3Sorcerer](http://www.as3sorcerer.com/) - 具有99％反编译精度的Premiere AS3反编译器（支持SWF / SWC，Alchemy操作码）.
* [Sothink Decompiler](http://www.sothink.com/product/flashdecompiler/) -  AS2 / AS3的高级反编译器（支持资产提取和SWF到FLA / Flex的转换）.

#### ANE Dev Tools
* [FreSharp](https://github.com/tuarua/FreSharp) - Build ANEs using C# with this C# wrapper for FlashRuntimeExtensions .
* [Swift-IOS-ANE](https://github.com/tuarua/Swift-IOS-ANE) - 用于iOS 10的Swift 3编写的ANE入门套件.

## Frameworks
#### MVC Frameworks

* [PureMVC](https://github.com/PureMVC/puremvc-as3-standard-framework) -  Flash的行业标准MVC框架（[multicore](https://github.com/PureMVC/puremvc-as3-multicore-framework)).
* [Robotlegs](https://github.com/robotlegs/robotlegs-framework) - 依赖注入，Flash的模块/视图/命令管理框架.
* [Hummingbird](https://github.com/flashapi/hummingbird) - 为AS3，Mobile和Starling Framework构建和部署强大的MVC应用程序.
* [Apollo](https://github.com/LaurentZuijdwijk/Apollo) - 依赖注入和消息传递框架，可用作MVC项目的基础.
* [Somacore](https://github.com/soundstep/somacore_framework) - 基于事件的轻量级AS3 MVC框架.
* [Kote](https://github.com/whitered/Kote) - 快速轻巧的MVC框架，汇集了最好的PureMVC和as3信号.
* [StarlingMVC](https://github.com/CreativeBottle/starlingMVC) - 基于Starling游戏的IOC框架.

#### UI Frameworks

* [Starling](https://gamua.com/starling/)   - 基于Stage3D构建的高性能2D图形引擎.  API与Flash API相同.  （[github](https://github.com/Gamua/Starling-Framework), [help](http://wiki.starling-framework.org/start)).
* [Feathers UI](https://feathersui.com/) -  Starling Framework的用户界面组件（[github](https://github.com/BowlerHatLLC/feathers), [help](https://feathersui.com/help/index.html)).
* [Flow](https://github.com/artman/Flow) - 使用布局，效果，数据绑定和远程处理框架代替Flex.
* [AS3Commons UI](https://github.com/AS3Commons/as3commons-ui) - 布局，焦点和键盘管理框架（[site](http://sibirjak.com/osflash/projects/as3commons-ui/)).
* [Swiz](https://github.com/swiz/swiz-framework) - 使用AS3和Adobe Flex创建RIA的简单微架构.
* [Hiddenwood](https://github.com/raweden/Project-Hiddenwood) - 为Web应用程序项目开发的用户界面库，以AS3和MVC模式编写.
* [Elastic-Lists](https://github.com/MoritzStefaner/Elastic-Lists) - 用于构面浏览的流畅且强大的界面.
* [Apache Flex®](https://flex.apache.org/)   - ApacheFlex®SDK是流行的Adobe Flex SDK的演变.  ApacheFlex®SDK是一个应用程序开发框架，可轻松为移动设备，Web浏览器和桌面平台构建基于Flash的应用程序.
* [Apache Royale®](http://royale.apache.org/)   - ApacheRoyale®项目正在开发下一代ApacheFlex®SDK.  Royale的目标是允许在MXML和ActionScript中开发的应用程序不仅可以在Flash / AIR运行时运行，还可以在没有Flash的浏览器中本地运行，在移动设备上作为PhoneGap / Cordova应用程序运行，以及在嵌入式JS环境中运行作为Chromium Embedded Framework.  Royale有可能允许您的MXML和ActionScript代码在比Flash目前更多的地方运行.

#### Game Frameworks

* [CitrusEngine](http://citrusengine.com/) - 基于Starling和Away3D构建的专业级游戏引擎.
* [StarlingPunk](https://github.com/asaia/StarlingPunk) - 基于Starling的框架，为您的游戏项目添加结构和组织.
* [FlashPunk](https://github.com/useflashpunk/FlashPunk)   - 构建2D游戏的框架.  提供图形，事件，输入，动画等.
* [Flixel](https://github.com/AdamAtomic/flixel) - 有用的基类，您可以扩展它们来制作自己的游戏对象.
* [Tetragon](https://github.com/NothingInteractive/tetragon)   - 构建任何类型游戏的跨平台框架.  提供资源管理，调试工具，多语言环境支持，分层可扩展性，面向游戏的数据结构等.
* [Pixelizer](https://github.com/johanp/Pixelizer)   - 基于组件的游戏引擎，用于构建2D游戏.  提供渲染，动画，输入等.
* [AS3isolib](https://github.com/as3isolib/as3isolib.v1) - 开发等距图书馆以协助创建等距投影游戏.
* [IsoHill](https://github.com/jadbox/IsoHill-Game-Engine) - 基于GPU的等距引擎，基于Starling构建，具有TILED地图解析器，图层等（[website](http://www.isohill.com/)).
* [YCanvas](https://github.com/jozefchutka/YCanvas) - 高性能2D平铺渲染器和世界地图渲染器.
* [ND2D](https://github.com/lrrrs/nd2d) - 使用Stage3D的GPU加速2D游戏引擎（[ND2Dx](https://github.com/NoRabbit/ND2Dx)).
* [Nexus](https://github.com/tversteeg/Nexus) - 使用Stage3D的GPU加速2D游戏引擎.

#### 3D Frameworks

* [AwayBuilder](http://awaytools.com/awaybuilder/) - 用于从各种来源导入，优化和烘焙3D资产的可视化工作流工具.
* [Away3D](https://github.com/away3d/away3d-core-fp11) - 适用于Flash Player 11+的开源GPU加速3D引擎（[examples](https://github.com/away3d/away3d-examples-fp11)).
* [Away3D OpenFL](https://github.com/away3d/away3d-core-openfl)   - 用于Neko，HTML5和本地CPP的Away3D.  （[examples](https://github.com/away3d/away3d-examples-openfl)).
* [AwayPhysics FP11](https://github.com/away3d/awayphysics-core-fp11) -  Away Physics  -  Away3D FP 11的3D物理库（[examples](https://github.com/away3d/awayphysics-examples-fp11)).
* [Alternativa3D](https://github.com/AlternativaPlatform/Alternativa3D) -  Alternativa3D GPU加速3D引擎（[examples](https://github.com/AlternativaPlatform/Alternativa3DExamples)).
* [Flare3D](http://flare3d.com/) - 具有高性能引擎和Level-editor IDE的商业3D平台.
* [Zen3D](https://github.com/hgupta9/Zen3D) - 适用于Adobe Flash和AIR（基于GPU）的高性能3D引擎.

#### Animation

* [GreenSock GSAP](https://greensock.com/gsap-as) - 用于Flash的行业标准动画库（TweenLite，TweenMax）（[github](https://github.com/greensock/GreenSock-AS3)).
* [GTween](http://gskinner.com/libraries/gtween/) - 用于编程补间，动画和过渡的小而强大的库.
* [DragonBones](http://dragonbones.github.io/) - 使用Starling的高速骨骼动画，以及从Flash Pro导出动画的工具.
* [FlashEff2](http://www.flasheff.com/) - 具有100多种过渡和文本效果的首映程序化动画库.
* [FlashEffNano](http://www.flasheffnano.com/) - 针对移动设备优化的FlashEff转换库，包含750种样式的20多种转换.
* [StarlingGAFPlayer](https://github.com/zenrobin/StarlingGAFPlayer) - 使用Starling（在Flash Pro中创作的动画）播放GAF动画.

#### Signals

* [AS3-signals](https://github.com/robertpenner/as3-signals) - New approach for AS3 events inspired by C# events and signals/slots in Qt.
* [react-as3](https://github.com/tconkling/react-as3) - 信号/插槽和功能反应式编程库.
* [Signaller](https://github.com/whitered/Signaller) - 具有受限制的调度权限的信号实施.
* [Fa-as3](https://github.com/fabrikagency/fa-as3) - 写得更少，做更多的框架，像jQuery一样建模.

#### Functional

* [AS3FP](https://github.com/jadbox/AS3FP) - 基于Haskell和Coffeescript的功能习语的集合.
* [Raix](https://github.com/richardszalay/raix) -  Reactive和Interactive eXtensions简化了交互式数据（阵列）或反应数据（事件）的使用.
* [Fxp-as3](https://github.com/j3k0/fxp-as3) - 功能性图书馆的灵感来自“大多数适当的指南”.

#### Unit Testing

* [AS3unit](https://github.com/Hoten/as3unit) -  ActionScript 3的单元测试框架.
* [hamcrest-as3](https://github.com/drewbourne/hamcrest-as3) -  Matcher对象允许以声明方式定义“匹配”规则.
* [expect.as](https://github.com/krzysztof-o/expect.as) - 用于ActionScript 3的BDD样式断言库.
* [AS3spec](https://github.com/f1337/as3spec) - 针对AS3的微小BDD框架，受到培根和RSpec的启发.
* [Flexunit](https://github.com/flexunit/flexunit) -  Actionscript 3和Flex项目的FlexUnit项目.
* [ASunit](https://github.com/patternpark/asunit) - 唯一支持Flash Player 6,7,8,9和10的单元测试框架.
* [RobotEyes](https://github.com/Stray/RobotEyes)   -  TDD的端到端测试.  WindowLicker和Drew Bourne的Mockolate的混合体.

## User Interface
#### UI Components

* [MinimalComps](https://github.com/minimalcomps/minimalcomps) - 适用于Flash的最小ActionScript 3.0 UI组件.
* [Extended-MinimalComps](https://github.com/turbosqel/Extended-MinimalComps) - 升级了数据绑定，相对大小调整，ASML构建器等.
* [MadComponents](https://github.com/danfreeman/MadComponents) - 适用于AS3 / AIR的流行移动UI框架.
* [AsWing](https://github.com/dreamsxin/AsWing) - 开源Flash ActionScript GUI框架.
* [GPUI](https://github.com/inspirit/GPUI) - 基于Stage3D（GPU）的微小GUI库.
* [Falcon](https://github.com/HendrixString/Falcon) - 针对Feathers的响应/灵活移动ui控件.
* [Flex-maps](https://github.com/igorcosta/flex-maps) -  Apache Flex中地图的最终解决方案.
* [FlexBook](https://github.com/blvz/FlexBook) -  Flex的Awesome Page Flip组件.

#### Starling Components

* [TabbedApplication](https://github.com/pol2095/Feathers-Extension-Tabbed-Application) - 基于视图的导航模型，使用滑动来导航选项卡.
* [DataGrid](https://github.com/pol2095/Feathers-Extension-DataGrid) - 显示具有列标题和平滑滚动的数据网格.
* [DataTree](https://github.com/pol2095/Feathers-Extension-Tree) - 显示排列为可扩展树的分层数据.
* [Canvas](https://github.com/pol2095/Feathers-Extension-Canvas) - 支持基本矢量绘图功能.
* [CircleProgress](https://github.com/pol2095/Feathers-Extension-CircleProgress) - 使用径向进度条显示进度.
* [ZoomableControl](https://github.com/pol2095/Feathers-Extension-ZoomableControl) - 允许使用多点触控输入进行缩放.
* [Toaster](https://github.com/pol2095/Feathers-Extension-Toaster)   - 关于小弹出窗口中的操作的简单反馈.  .
* [Google Maps](https://github.com/ZwickTheGreat/feathers-maps) - 针对Starling的Google地图，针对移动设备进行了优化.

#### Layout

* [Adobe TLF](https://github.com/apache/flex-tlf) -  Adob​​e / Apache Flex文本布局框架（TLF）.
* [TinyTLF](https://github.com/joelhooks/tinytlf) - 基于Flash文本引擎的Flash / Flex构建的多功能文本布局框架.
* [TransformManager](https://greensock.com/TransformManager)   - 格林索克.  交互式缩放/旋转/移动DisplayObjects.
* [TransformTool](https://github.com/senocular/TransformTool) - 用于操纵2D空间中的对象的自由变换工具（AS，JS）.
* [Argilla-Mosaic](https://github.com/folletto/Argilla-Mosaic) - 动态布局库.
* [xrope](https://github.com/evan-liu/xrope) - 用于本机AS3显示对象的简单布局库.
* [miglayout-as](https://github.com/develar/miglayout-as) -  MigLayout端口，一个功能多样的Flash / Flex / FlashCocoa（SWT / Swing / JavaFX）布局管理器.

#### Multi Touch

* [AS3TouchLib](https://github.com/turbosqel/AS3TouchLib) - 触摸库，用于从其他设备读取CCV TCP / FlashXML数据，TUIO UDP / TCP或TouchEvent.
* [TUIO Client](https://github.com/lagerkoller/tuio-as3) - 多点触控硬件的通用框架，支持TUIO / FLC和TUIO / TCP（[web](http://www.tuio.org/?flash)).
* [Gestouch](https://github.com/fljot/Gestouch) - 多点触控手势识别库，用于构建更好的自然用户界面.
* [Gestures.IO](https://github.com/GesturesIO/gesturesio-as3) - 简化您创建基于手势的自然交互的方式.
* [TouchScript](https://github.com/TouchScript/TouchScript.as3) - 多点触控框架，可以更轻松地处理大型触摸表面上复杂的手势交互.

#### Game Controllers

* [AS3dpad](https://github.com/duckleg/as3dpad) - 专为Adobe AIR Mobile（Android / iOS）设计的虚拟触摸屏游戏手柄.
* [Gamepad](https://github.com/iainlobb/Gamepad) - 使用键盘模拟模拟操纵杆输入.
* [Advanced_Joystick](https://github.com/justjoeyuk/Advanced_Joystick) - 为Adobe AIR Mobile设计的Starling Framework操纵杆.
* [AS3-Controller-Input](https://github.com/arkeus/as3-controller-input) - 与Adobe AIR的Ouya和Xbox360游戏控制器交互.

## Multimedia

#### Augmented Reality

* [FLARToolKit](https://github.com/Saqoosha/FLARToolKit) - 适用于Flash Player 11的行业标准ARToolkit库的AS3端口.（[website](http://www.libspark.org/wiki/saqoosha/FLARToolKit/en)).
* [FLAREmulator](https://github.com/theflashbum/FLAREmulator) - 测试AR演示以查看有或没有网络摄像头的情况.
* [FLARManager](http://words.transmote.com/wp/flarmanager/) - 使用FLARToolkit / flare.tracker / flare.NFT构建增强现实应用程序的轻量级框架.
* [NyARToolkitAS3](https://github.com/nyatla/NyARToolkitAS3)   -  NyARToolkit AS3版.  基于标记的增强现实库.
* [EZFLAR](https://github.com/tcha-tcho/EZFLAR) - 一个小包装，以减轻AR的工作方式.
* [IN2AR](https://github.com/inspirit/IN2ARSDKExamples) - 适用于IN2AR跨平台增强现实引擎的SDK.

#### Data Visualization

* [Degrafa](https://github.com/lancejpollard/degrafa) -  Flex的强大声明性图形框架.
* [Axiis](https://github.com/hgupta9/AxiisCharts) - 数据可视化框架，包括直线，条形，楔形，柱形，聚类，面积，史密斯和树形图.
* [Open Flash Charts](https://sourceforge.net/projects/openflashchart/) - 折线图，面积图，条形图，饼图，散点图.
* [Flare](https://github.com/prefuse/Flare) - 图表和图形，支持数据管理，可视编码，动画和交互技术.
* [clearmaps](https://github.com/sunlightlabs/clearmaps) - 数据可视化的映射框架.
* [redada](https://github.com/geraldo/redada) - 使用GraphML文件对加权图形进行交互式可视化.
* [Flextreemap](https://github.com/joshtynjala/flextreemap) - 用于Adobe Flex的TreeMap数据可视化组件.
* [GraphVisualizer](https://github.com/armisael/GraphVisualizer) - 用于绘制动态图形的Flex 3 + ActionScript 3 Web软件.
* [Weave](https://github.com/WeaveTeam/Weave) - 基于Web的分析和可视化环境.
* [Social-grid](https://github.com/Instrument/social-grid) - 社交媒体的抽象网格可视化.

#### Camera

* [CameraDetection](https://github.com/cataclysmicrewind/CameraDetection) - 相机检测.
* [Fluocam](https://github.com/Fluocode/Fluocam) - Virtual camera for Starling applications.
* [WebcamRecorder](https://github.com/Stupeflix/WebcamRecorder) - 来自网络摄像头的无铬视频/音频/静态图像录制.
* [FlashyWrappers](https://github.com/rainbowcreatures/FlashyWrappers) - 在Windows / Android / iOS / OSX上录制AIR应用程序的视频.

#### Image

* [Scale9Image](https://github.com/Tibus/Scale9Image) - 针对椋鸟的优化scale9Grid图像.
* [ASImageLib](https://github.com/terrynoya/ASImageLib) - 动作脚本的BMP / PNG解码器.
* [Async-Image-Encoders](https://github.com/LeeBurrows/Async-Image-Encoders) - 将BitmapData对象异步编码为图像文件格式.
* [Flip-Planes-AS3](https://github.com/jamesflorentino/Flip-Planes-AS3) - 照片幻灯片效果.
* [AS3-transitions-lib](https://github.com/foo123/as3-transitions-lib) - 图像过渡库.
* [Inspirit Image](https://github.com/hgupta9/InspiritImage) -  FFT，SURF，边缘检测，流体求解器等
* [Inspirit GPUImage](https://github.com/inspirit/GPUImage) - 基于GPU的图像处理框架.
* [AS3potrace](https://github.com/PowerflasherBR/as3potrace) -  POTrace实现，将位图图像跟踪到矢量.
* [ATF-Encoder](https://github.com/plepers/ATF-Encoder) - 在纯AS3中编码/解码ATF（Adobe纹理格式）文件.
* [AS3-klt](https://github.com/motemen/as3-klt) - Kanade-Lucas-Tomasi feature tracker implementation.

#### Font

* [Firetype](https://github.com/MaxDidIt/firetype) - 解析OpenType字体并使用Stage3D渲染它们.
* [BMFontRenderer](https://github.com/bengarney/BMFontRenderer) - 用于BMFont格式的位图字体数据的AS3渲染器.
* [HanFont](https://github.com/kyoji2/HanFont) - 用于在ActionScript中嵌入中文字体的AIR应用程序.
* [Ficon.as](https://github.com/dv/Ficon.as) - 库可轻松包含图标字体.

#### Particle

* [Flint](https://github.com/richardlord/Flint) - 用于Flash和Flex的粒子引擎.
* [Desuade Partigen](http://desuade.com/partigen) -  Desuade Partigen粒子生成系统（[github](https://github.com/andrewfitz/desuade)).
* [Angulex](https://github.com/cosmindolha/ParticleDesigner) -  Starling框架的粒子设计器（ActionScript 3）.
* [SAP](https://github.com/gonchar/SAP) -  Starling的粒子系统.
* [Starling-Particles](https://github.com/Gamua/Starling-Extension-Particle-System) -  Starling框架的粒子系统，与71squared.com的“Particle Designer”兼容.
* [MotionParticleSprite](https://github.com/bjeld/motionparticlesprite) - 在Flash Pro中设计运动路径并使用它来指导Starling粒子.

#### Panorama Viewer

* [Pantaloons](https://github.com/EyeSee360/Pantaloons) - 在Flash Player中全景观看.
* [SaladoPlayer](https://github.com/mstandio/SaladoPlayer) - 全景查看器.
* [PanoramicViewer](https://github.com/BrianMehrman/PanoramicViewer) -  3D全景查看器.
* [Sphere_panorama](https://github.com/suzumura-ss/flash_sphere_panorama) - 在AS3（Alternativa3D）中编写的equirectangular纹理的全景播放器.
* [CuTy](https://github.com/fieldOfView/CuTy) - 基于Flash 10的QTVR Panorama查看器.

#### QR Code

* [Zxing AS3](https://github.com/zxing/zxing/tree/c1df162b95e07928afbd4830798cc1408af1ac67/actionscript) -  QR码检测和生成（[docs](https://zxing.github.io/zxing/)).
* [AS3-qrcode-encoder](https://github.com/jbpin/as3-qrcode-encoder) -  as3中的QR码编码器.
* [qrcode-as](https://github.com/yanbe/qrcode-as) -  QR码阅读器，支持Windows，Mac和Linux上的网络摄像头.

#### Sound

* [SoundAS](https://github.com/treefortress/SoundAS) -  AS3的现代轻量级声音管理器.
* [Standingwave3](https://github.com/maxl0rd/standingwave3) - 动态音频库.
* [Standingwave3-addons](https://github.com/charlesclements/standingwave3-addons) -  SW3的插件.
* [Soundtouch-as3](https://github.com/also/soundtouch-as3) -  SoundTouch声音处理库的AS3端口.
* [SeiON](https://github.com/cardin/SeiON) - 声音管理库.
* [AS3-Sound-Manager](https://github.com/GrupoW/as3-Sound-Manager)-  Matt Przybylski的升级版Sound Manager Class.
* [AS3sfxr](https://github.com/SFBTom/as3sfxr) - 使用Flash Player 10的新声音和文件功能，从C ++到AS3的sfxr端口.
* [AS3-audio](https://github.com/singuerinc/as3-audio) -  Actionscript中的音频管理.
* [SiON](https://github.com/keim/SiON) -  Flash软件合成器.
* [FlashWavRecorder](https://github.com/michalstocki/FlashWavRecorder) - 录制音频并保存为WAV.
* [Local-recorder](https://github.com/pauln/local-audio-recorder)   - 本地录音机（无需流媒体服务器）.  目前需要Flash Player 10.1或更高版本.
* [Jukebox](https://github.com/AlwynW/Jukebox) -  Actionscript 3项目的音乐经理.
* [Flod](https://github.com/photonstorm/Flod) -  Amiga SoundTracker（MOD）和FastTracker（XM）重播库.

#### Video Player

* [Flowplayer](https://github.com/flowplayer/flash) -  Flowplayer Flash，Web的视频播放器.
* [Goplayer](https://github.com/dbrock/goplayer) - 使用ActionScript 3编写的现代开源视频播放器.
* [OSFlashVideoPlayer](https://github.com/FlashJunior/OSFlashVideoPlayer) - 开源Flash视频播放器.
* [F4player](https://github.com/gokercebeci/f4player) - 开源AS3 Flash视频播放器.
* [dashas](https://github.com/castlabs/dashas) - 用ActionScript编写的MPEG-DASH播放器.
* [hlsplayer](https://github.com/erlyvideo/hlsplayer) -  OSMF Flash框架的HLS播放器.
* [vgaplayer](https://github.com/euske/vgaplayer) -  Adob​​e Flash Media Server流（RTMP）的开源播放器.

## Database

#### SQLite
* [AS3Query](https://github.com/kemsky/as3Query) -  ActionScript的另一个SQLite ORM和查询DSL.
* [AIRdb](https://github.com/dkeskar/airdb)   -  AIR ORM在AIR和Flex应用程序中使用客户端SQLite.  支持ActiveRecord样式模型，迁移和关联.
* [Flexine](https://github.com/riadvice/Flexine) - 用于AIR的SQLite ORM.
* [AIR-sqlite](https://github.com/probertson/air-sqlite) - 用于在AIR中使用SQLite数据库的实用程序.

#### MongoDB
* [MongoAS3](https://github.com/s9tpepper/MongoAS3) -  MongoDB驱动程序.
* [ActionMongo](https://github.com/RIAlizer/ActionMongo) -  MongoDB驱动程序.

#### CouchDB
* [AS3couchdb](https://github.com/bustardcelly/as3couchdb) - 用于与CouchDB实例交互的客户端API.
* [Soup](https://github.com/dima/soup) - 混合使用CouchDB，Sinatra，AIR和RestfulX创建具有撤消/重做功能的离线/在线就绪应用程序.

#### MySQL
* [AS3mysql](https://github.com/hgupta9/as3mysql) -  MySQL开源数据库的驱动程序.

#### PostgreSQL
* [Pegasus](https://github.com/uhoh-itsmaciek/pegasus) -  PostgreSQL开源数据库的驱动程序.

#### DynamoDB
* [AWS-dynamodb](https://github.com/ferf/aws-dynamodb-actionscript) - 用于访问亚马逊AWS DynamoDB的驱动程序.

#### Redis
* [AS3redis](https://github.com/zhangq0355/as3redis) -  Redis的驱动程序.

## File Formats

#### Archives

* [FZip](https://github.com/claus/fzip) - 用于加载，修改和创建标准ZIP存档的成熟库.
* [ASZip](https://code.google.com/archive/p/aszip/)   - 从AS3生成ZIP存档.  （[post](http://www.bytearray.org/?p=105)).
* [Untar-Worker](https://github.com/mesmotronic/as3-worker-untar) - 使用AS3 Workers（后台线程）进行TAR提取.

#### 3D Formats

* [AsCollada](https://github.com/timknip/ascollada) - 解析COLLADA 3D模型文件（[fork](https://github.com/david-gregory/ascollada)).
* [AsBlender](https://github.com/timknip/asblender) - 解析Blender .BLEND文件.
* [AS3-bvh-parser](https://github.com/rkn14/as3-bvh-parser) - 解析BVH文件.
* [EasyAGAL](https://github.com/Barliesque/EasyAGAL) - 通过代码完成，代码提示，宏等简化AGAL着色器的开发.

#### CSV

* [CSV4AS3](https://github.com/lizardon/CSV4AS3) - 从Apache Commons CSV移植的CSV库.
* [Csvlib](https://github.com/51systems/csvlib) -  CSV解析器.

#### CSS

* [AS3csslib](https://github.com/heyfrench/as3csslib) -  ActionScript 3.0的CSS3解析器，选择器和样式引擎.
* [Fcss](https://github.com/theflashbum/fcss) -  Flash级联样式表库.
* [Stylekit-as3](https://github.com/videojuicer/stylekit-as3) - 使用CSS3的Skinnable用户界面.
* [Sass4as](https://github.com/jeremyruppel/sass4as) -  ActionScript 3的Syntactically Awesome Stylesheets.
* [Jakute-CSS](https://github.com/kakenbok/Jakute-Styling-Engine) -  Jakute是ActionScript / Flash的CSS框架.
* [CSS.as](https://gist.github.com/trxcllnt/1161266) - 单文件CSS解析器，TinyTLF项目的一部分.

#### BSON

* [ActionBSON](https://github.com/fminzoni/ActionBSON) -  BSON数据编码器/解码器.
* [MongoAS3](https://github.com/s9tpepper/MongoAS3) - 包含BSON I / O的MongoDB驱动程序.

#### EXIF

* [AS3-exif-lib](https://github.com/unstoppable/actionscript-exif-reading-lib) - 解析JPEG EXIF数据.
* [Exif-as3](https://github.com/bashi/exif-as3) - 解析JPEG EXIF数据.

#### FXG

* [Fxg-as3-lib](https://github.com/pixelami/fxg-as3-lib) - 纯AS3 FXG渲染库（支持运行时渲染和mxml）.
* [Fxg2as3](https://github.com/ZackPierce/fxg2as3) - 将FXG标记转换为可执行的Actionscript 3代码.

#### GIF

* [AS3gif](https://github.com/audreyt/as3gif) - 播放和编码动画GIF.
* [GIF Player](https://github.com/theturtle32/Flash-Animated-GIF-Library) - 在Flash中播放动画GIF.
* [Async-gif-decoder](https://github.com/honzabrecka/async-gif-decoder) - 异步GIF解码器和播放器.

#### ICAL

* [AS3iCAL](https://github.com/nicolai86/as3.iCal) - 基于RFC2445规范的iCal解析器.

#### JSON

* [Actionjson](https://github.com/mherkender/actionjson) - 更快，更高级的ActionScript 3 JSON库.
* [Jameson](https://github.com/mattupstate/jameson) -  JSON文档对象映射器.
* [Serialkiller](https://github.com/benbjohnson/serialkiller) -  JSON和XML序列化库.
* [JsonMapper](https://github.com/kemsky/JsonMapper) - 键入的JSON解析器.
* [JSONTools](https://github.com/s9tpepper/JSONTools) -  JSON错误，JSWoof JSON库的速度以及被称为E4J的E4X样式查询.

#### Markdown

* [Showdown.as](https://gist.github.com/cstrahan/648771) -  showdown.js的端口.
* [Actiondown](https://github.com/bbeaumont/Actiondown) -  Javascript摊牌端口.
* [Markdownlib](https://github.com/Corsaair/markdownlib) -  Markdown的实施.

#### MP3

* [AS3id3lib](https://github.com/devxoul/as3id3lib) - 解析MP3 ID3数据.
* [AS3Icy](https://github.com/claus/as3icy) - 从Shoutcast，Icecast和Limewire解码并播放实时MP3流.

#### PDF

* [AlivePDF](https://code.google.com/archive/p/alivepdf/) - 客户端PDF生成（[docs](http://alivepdf.bytearray.org/), [github](https://github.com/riadvice/alivepdf)).
* [PurePDF](https://github.com/sephiroth74/purePDF) - 完整的PDF库，Java iText的端口.
* [HalcyonPDF](https://github.com/systemed/halcyon_pdf) -  OpenStreetMap PDF渲染器.
* [PDFCase](https://github.com/dickclaus/pdfcase) -  PDF库.
* [PDFView](https://github.com/jankapunkt/PDFView) - 从头开始​​构建的PDF查看器.

#### PSD

* [AS3-psd-parser](https://github.com/warrenseine/as3-psd-parser) - 解析Photoshop PSD文件并渲染为BitmapData对象.

#### SWF

* [AS3swf](https://github.com/claus/as3swf) - 用于解析，创建，修改和发布SWF文件的低级库.
* [AS3abc](https://github.com/imcj/as3abc) - 用于解析，创建，修改和发布ABC（Actionscript Block Code）文件的低级库.
* [SWFWire](https://github.com/magicalhobo/SWFWire) -  SWF反编译器和检查器工具.
* [Abc-abstraction](https://github.com/krilnon/abc-abstraction) - 允许对ABC进行分析，操作，打包回SWF并运行.

#### SVG

* [AS3SVGRenderer](https://github.com/LucasLorentz/AS3SVGRenderer) - 适用于Flash Player的SVG渲染器.
* [SVGParser](https://github.com/millermedeiros/SVGParser) -  SVG解析器和渲染器到FIVe3D和HTML5画布.

#### XML

* [XMLSerializer](https://github.com/vapesolius/XMLSerializer) - 允许从ActionScript到XML以及从XML到ActionScript的数据序列化的库.
* [DynamicXMLParser](https://github.com/lmgerhard/DynamicXMLParser) - 动态将xml内容解析为预定义的数据类（actionscript 3）.
* [Nudge](https://github.com/pluglimited/Nudge) - 将对象序列化/反序列化为XML的框架.
* [AStream](https://github.com/kokorin/AStream)   - 用AS3编写的XML到Object（反之亦然）映射库.  与XStream兼容.

#### XLSX

* [AS3-xlsx-reader](https://github.com/childoftv/as3-xlsx-reader) - 解析Open XML Excel（.XLSX）或Open Office电子表格.


## Networking
#### Data Loader

* [GreenSock LoaderMax](https://github.com/greensock/GreenSock-AS3) - 提供一种在运行时加载资产的简单而强大的方法.
* [BulkLoader](https://github.com/arthur-debert/BulkLoader) -  Actionscript的批量资产加载库.
* [AssetLoader](https://github.com/Matan/AssetLoader) - 基于AS3Signals构建的AS3多文件/资产加载程序.

#### Hardware

* [AS3midilib](https://github.com/heyfrench/as3midilib) - 使用MIDI文件和MIDI输入/输出设备.
* [AS3glue](https://code.google.com/archive/p/as3glue/) -  Arduino板的通信.
* [AS3-arduino](https://github.com/quetwo/as3-arduino-connector) - 将Arduino原型开发板连接到Adobe AIR.
* [AIRkinect](https://github.com/AS3NUI/airkinect-2-core)   - 与Microsoft Kinect集成的ANE.  （[examples](https://github.com/AS3NUI/airkinect-2-examples)).
* [KinectGate](https://github.com/cleoag/KinectGate) -  KinectSDK到AS3插座门.
* [Kinect-Gestures](https://github.com/tonybeltramelli/Air-Kinect-Gesture-Lib) -  AIR Kinect手势库.
* [OpenTSPS](https://github.com/labatrockwell/openTSPS)   -  TSPS是一个用于感知空间人员的跨平台工具包.  它对实时视频（Kinect，网络摄像头等）执行openCV操作，并以JSON（通过WebSockets），OSC，TUIO或TCP的形式发送给客户端.
* [LeapMotionAS3](https://github.com/logotype/LeapMotionAS3) - 与LeapMotion传感器集成（提供手势，图像，骨架/骨骼@ 210 FPS）.

#### Servers

* [AIRhttp](https://github.com/leopoldodonnell/airhttp) - 用于Adobe AIR的HTTP Server.
* [AIR-Server](https://github.com/wouterverweirder/AIR-Server) - 用于Adobe AIR的套接字服务器库.

#### OAuth

* [Actionscript-oauth2](https://github.com/charlesbihis/actionscript-oauth2) - 与OAuth 2.0服务连接.
* [oauth-flex](https://github.com/oauth-io/oauth-flex) -  Apache Flex / ActionScript的OAuth.io插件.
* [oauth-as3](https://github.com/mlepicki/oauth-as3) -  Mavenized，RSL版本的oauth-as3库 -  OAuth for ActionScript 3.

#### HTTP

* [Hendrix-HTTP](https://github.com/HendrixString/Hendrix-HttP-AiR) - 由Square的OkHttp启发的ActionScript 3（as3）的轻量级HTTP库.
* [HTTPForm](https://github.com/dv/HTTPForm) - 模拟多部分/表单数据HTML表单提交请求，包括文件上载.
* [AS3httpclient](https://github.com/abdul/as3httpclient) -  HTTP客户端实现.
* [AS3httpclient](https://github.com/gabriel/as3httpclient) -  HTTP客户端实现.
* [Amazon Web Services](https://github.com/satoshi7/ActionScript-API-for-AWS-Amazon-Web-Services-) -  AWS的AS3 API.

#### P2P

* [P2Plocal](https://github.com/palkan/as3_p2plocal) - 本地RTMFP连接.
* [Android-Flash-P2P](https://github.com/beautifycode/Android-Flash-P2P) -  Client.swf与具有AIR的Android设备之间的P2P通信.
* [GogduNet](https://github.com/Siyania/GogduNet) - 用于TCP和UDP和P2P的通信库.
* [NetGrouper](https://github.com/walpolea/NetGrouper) - 用于NetGroup和RTMFP多播功能的包装器，可通过本地网络或Adobe Cirrus创建快速P2P多人游戏.
* [HydraP2P](https://github.com/devboy/HydraP2P) - 简化Flash Player 10.1中引入的对等API.
* [GroupP2P](https://github.com/oohazard/GroupP2P) - 基于P2P的网络组.
* [HLS-P2P](https://github.com/lava-tech/hls-p2p) - 基于Flash OSMF的混合cdn和p2p hls解决方案.
* [P2Pmessaging](https://github.com/dreamsocket/actionscript-p2p_messaging) - 用于在Flash中执行P2P的简单消息传递框架.
* [ArcusNode](https://github.com/OpenRTMFP/ArcusNode) - 用于节点JS上的Adobe Flash的对等辅助网络的RTMFP Rendevouz服务.

#### Sockets

* [AS3WebSocket](https://github.com/theturtle32/AS3WebSocket) - 最终WebSocket Draft RFC6455的WebSocket客户端实现.
* [SmartSocket](https://github.com/XaeroDegreaz/SmartSocket) -  SmartSocket是一个Java和PHP套接字服务器引擎，可以快速轻松地创建多用户应用程序.
* [FlashSocket.IO](https://github.com/simb/FlashSocket.IO) - 客户端从AS3 / AIR客户端连接到Socket.IO服务器.
* [Socket.io](https://github.com/ascorbic/socket-io-actionscript) -  Socket.IO Actionscript 3客户端.
* [AMFsocket](https://github.com/chadrem/amf_socket) - 用于高性能网络通信的双向RPC库.
* [Sockpuppet](https://github.com/rjungemann/sockpuppet) - 使用AMF完成Ruby / ActionScript套接字客户端/服务器.
* [Socket.io-flash](https://github.com/sinnus/socket.io-flash) - 与Socket.IO v.0.8 +服务器的通信.
* [ws-flash-client](https://github.com/youurayy/ws-flash-client) - Reliable minimalistic WebSocket client (uses Adobe Flash where native WebSocket is not available).

#### Protocols

* [GIT](https://github.com/nexussays/git-as3) -  Git的客户端实现.
* [AIRplay](https://github.com/mikkoh/AS3-Airplay) -  Apple的Airplay的客户端实施.
* [TeaTime](https://github.com/aemoncannon/croqodile) - 针对Croquet项目的TeaTime协议的AS3 / Erlang实现.
* [XMPP](https://github.com/lyokato/as3xmppclient) -  XMPP库的客户端实现.
* [XMPP](https://github.com/bluef/kuching) -  XMPP库的轻量级实现.
* [AMQP](https://github.com/0x6e6562/as3-amqp) - 客户端实施0-8版AMQP.
* [NTP](https://github.com/charlespalen/AS3-NTP-Implementation) -  NTP客户端（网络时间协议）的客户端实现.
* [FUDI](https://github.com/matthiasbreuer/FUDI-as3) -  Puredata FUDI协议的客户端实现.
* [BDD Cucumber](https://github.com/flashquartermaster/Cuke4AS3) - 用于Flash ActionScript的BDD Cucumber线协议实现.

#### Email

* [AIRXMail](https://github.com/hgupta9/AirXMail) - 完整的客户端电子邮件库，支持SMTP，POP3和IMAP4.
* [AS3Mailer](https://github.com/Matan/AS3Mailer) - 使用服务器脚本发送电子邮件或调用mailto.

## Utilities

#### Artificial Intelligence

* [FiniteStateMachine](https://github.com/pzUH/FiniteStateMachine) - 用于AI bot / agent的有限状态机.
* [N-GramPredictor](https://github.com/pzUH/N-GramPredictor) - n-Gram predictor for AI bot/agent.
* [Naive-BayesPredictor](https://github.com/pzUH/Naive-BayesPredictor) -  AI bot / agent的Naive-Bayes预测器.
* [HierarchicalStateMachine](https://github.com/pzUH/HierarchicalStateMachine) -  AI bot / agent的分层状态机.
* [Godmode-as3](https://github.com/tconkling/godmode-as3) - 行为树实施（人工智能）.
* [DecisionTree](https://github.com/pzUH/DecisionTree) -  AI bot / agent的二进制决策树.
* [FuzzyStateMachine](https://github.com/pzUH/FuzzyStateMachine) - 用于AI机器人/代理的模糊状态机（FuSM）.
* [SmartKid](https://github.com/skyfeiyun/SmartKid) - 用于2D和3D游戏的强大AI引擎.

#### Async

* [EasyAS-Worker](https://github.com/myflashlab/easyAS-Worker) -  AIR Workers的简化包装器.
* [Worker-from-class](https://github.com/bortsen/worker-from-class) - 从类定义创建Worker.
* [AS3Futures](https://github.com/brianheylin/AS3Futures) - 简化了一系列异步函数调用.

#### Crypto

* [BlooddyCrypto](https://github.com/blooddy/blooddy_crypto)   - 用于处理二进制数据的高性能库.  该库包含MD5，SHA-1，SHA-2，Base64，CRC32，JSON，PNG / JPEG编码器.
* [AS3Crypto](https://github.com/timkurvers/as3-crypto) -  Henri Torgemane的优秀密码库（[patched](https://github.com/lyokato/as3crypto_patched)).
* [AS3corelib](https://github.com/mikechambers/as3corelib) -  MD5和SHA1散列，图像编码器和JSON序列化.
* [ASCrypt](https://github.com/Meychi/ASCrypt) - 具有用于多种语言的类似API的加密库​​.
* [Nexuslib](https://github.com/nexussays/nexuslib-as3) - 反射，序列化，种子随机数生成，加密，网络等.
* [Hashlib](https://github.com/Corsaair/hashlib) - 超过30种不同的散列函数.
* [XXTEA-AS3](https://github.com/xxtea/xxtea-as3) - 用于ActionScript 3的XXTEA加密算法库.
* [Gibberish-AES](https://github.com/NordMike/gibberish-aes-as3) - 完全符合OpenSSL标准的ActionScript 3库，用于AES加密.

#### Data

* [AS3Commons Collections](https://github.com/AS3Commons/as3commons-collections) -  AS3的复杂和高性能集合和迭代器（[website](http://sibirjak.com/osflash/projects/as3commons-collections/)).

#### Geometry

* [AS3geometry](https://github.com/alecmce/as3geometry) - 基元，多边形，交叉点等
* [AS3GeomAlgo](https://github.com/azrafe7/as3GeomAlgo)   - 几何算法的集合.  hxGeomAlgo的端口.
* [Coral](https://github.com/richardlord/Coral) -  3D数学的高性能课程（Point，Vector，Matrix，Quaternion）.
* [Csg.as](https://github.com/timknip/csg.as) - 三维网格上的构造实体几何.
* [PathUtils](https://github.com/alinakipoglu/Actionscript-PathUtils) - 使用二次，贝塞尔和线序列.
* [Hilbert](https://github.com/nodename/Hilbert) - 来自cortesi / scurve的Hilbert曲线.
* [AS3AStar](https://github.com/tomnewton/AS3AStar) - 快速A-Star寻路算法.
* [A-star_pathfinder](https://github.com/kevhiggins/a-star_pathfinder) - 基于图块的地图的A-Star寻路接口.
* [As3Pathfinder](https://github.com/azakhary/As3Pathfinder) - 使用Dijkstra算法编写的网格路径查找库.

#### Math

* [AS3Units](https://github.com/erussell/AS3Units)   -  NGUnits端口.  在度量单位之间进行解析，格式化和转换.
* [AS3LinAlg](https://github.com/inspirit/AS3LinAlg) - 线性代数库（Jacobi SVD，特征向量/值，Cholesky LU等）.
* [Performance Primitives](https://github.com/martinkallman/performance-as3) - 以Intel Performance Primitives为模型的高性能数学.
* [Zexpression](https://github.com/Xorcerer/zexpression) - 使用函数和变量解析和扩展数学表达式.
* [FlexibleMatrix](https://github.com/Lukx/FlexibleMatrix) - 多用途Matrix类.
* [AS3eval](http://eval.hurlant.com/)   - 将Tamarin ESC编译器打包到Flash Player中.  （[alternate](https://github.com/SimonRichardson/as3-eval)).
* [FlashFormulaEditor](https://github.com/zasdfgbnm/FlashFormulaEditor) - 使用Adobe Flex制作的公式编辑器.

#### Text

* [Linkify-as3](https://github.com/CodeCatalyst/linkify-as3) - 将URL，电子邮件地址，电话号码转换为可点击的链接.
* [AS3hyphenation](https://github.com/gka/as3hyphenation) -  Javascript文本连字库Hyphenator.js的端口.

## Runtimes

#### Emulators

* [NES Emulator](https://github.com/nesbox/emulator) -  NES模拟器，超级任天堂，世嘉超级驱动器，GameBoy视频控制台.
* [Commodore 64 Emulator](https://github.com/claus/fc64) - 一个用ActionScript 3编写的低级Commodore 64仿真器.
* [8080 Emulator](https://github.com/ozipi/As3_SpaceInvaders_Emulator) - 基于intel 8080处理器的actionscript 3空间入侵者模拟器.
* [8-bit VM](https://github.com/OutOfTheVoid/AS3-8-bit-VM) - 用actionscript编写的八位虚拟机.

#### Interpreters

* [JS](https://github.com/theturtle32/RhinoAS3) -  RhinoJS，Mozilla的Rhino JavaScript口译员.
* [Simple JS](https://github.com/sixsided/Simplified-JavaScript-Interpreter) - 基于AS3的Javascript解释器.
* [MIL](https://github.com/ser1zw/MIL) - 使用ActionScript编写的MIL语言VM和解释器.
* [TALES](https://github.com/oaubert/tales4as) -  ActionScript的TALES解释器.
* [Scheme](https://github.com/hrundik/fScheme) -  ActionScript中的Scheme解释器.
* [Lisp](https://github.com/rzubek/as_lisp) - 用ActionScript编写的Lisp方言，带有编译器和字节码解释器.
* [Lisp Compiler](https://github.com/aemoncannon/las3r) -  AVM2的lisp编译器.
* [CannonML](https://github.com/abiyasa/cannonml_as3) -  keim的CannonML（shmup脚本语言）解释器.

## AIR Native Extensions

#### Audio ANE
* [SongPicker](https://github.com/richpixel/SongPickerANE) - 适用于iOS和Android的歌曲选择器/播放器ANE.
* [SilentSwitch](https://github.com/StickSports/ANE-Silent-Switch) - 如果硬件静音开关打开，则ANE用于iOS静音.
* [VolumePro](https://github.com/myflashlab/VolumePro-ANE) - 控制本机音乐流量，您可以收听音量变化.
* [SystemVolume](https://github.com/nweber/SystemVolumeNativeExtension) - 与iOS和Android设备的系统卷交互.

#### Multimedia ANE
* [WebView (Tuarua)](https://github.com/tuarua/WebViewANE)   - 适用于OSX 10.10 +，Windows桌面，iOS 9.0+和Android 21+的现代WebView.  在Windows上使用CEF（Chromium Embedded Framework），在iOS / OSX上使用WKWebView，在Android上使用WebView.
* [WebView (FlashLab)](https://github.com/myflashlab/webView-ANE) -  StageWebView的替换，允许从AIR调用Javascript函数.
* [AVANE](https://github.com/tuarua/AVANE) - 使用FFmpeg构建视频编码应用程序.
* [PDF](https://github.com/myflashlab/PDF-ANE)   - 允许您从AIR移动应用程序打开PDF文件.  在Android和iOS上受支持.
* [VideoPlayer](https://github.com/myflashlab/videoPlayer-ANE) - 在Android或iOS原生视频播放器中播放视频文件.
* [SurfaceVideoPlayer](https://github.com/myflashlab/surfaceVideoPlayer-ANE) -  SurfacePlayer ANE可帮助您在空中移动项目中播放视频文件.
* [Speech](https://github.com/myflashlab/speech-ANE) - 在后台完全将字符串转换为语音文件，反之亦然.
* [MyAR](https://github.com/myflashlab/AR-ANE-Samples) -  AR ANE支持基于Metaio SDK的Android和iOS 64位.
* [QR-zbar](https://github.com/saumitrabhave/qr-zbar-ane) -  QR码阅读器的ANE.
* [Barcode](https://github.com/myflashlab/barcode-ANE) - 使用这款超快速条码扫描仪ANE扫描几乎所有条形码类型.
* [Bullet](https://github.com/mziwisky/bullet-ane) - 子弹物理模拟库.

#### File System ANE
* [FileChooser](https://github.com/myflashlab/fileChooser-ANE) - 允许用户从设备文件系统中选择文件.
* [ZipManager](https://github.com/myflashlab/zipManager-ANE) - 在Android和iOS上使用本机进程快速压缩或解压缩大型zip存档.
* [Spotlight](https://github.com/myflashlab/Spotlight-ANE) - 与iOS 9 Spotlight搜索集成，以索引搜索项和用户生成的内容.

#### Networking ANE
* [Firebase](https://github.com/myflashlab/Firebase-ANE) - 适用于Android和iOS的Google Firebase API，具有100％相同的ActionScript API.
* [DownloadManager](https://github.com/myflashlab/downloadManager-ANE) - 下载具有暂停/恢复支持的大数据文件.
* [BitTorrent](https://github.com/tuarua/BitTorrentANE) - 用于构建启用BitTorrent的应用程序.

#### Hardware ANE
* [Bluetooth](https://github.com/myflashlab/bluetooth-ANE) - 扫描其他设备，连接并配对，并在它们之间传输数据.
* [GPS](https://github.com/myflashlab/GPS-ANE) - 通过自动检查最佳可用提供商，尽快获取当前设备的GPS位置.
* [GoogleVR](https://github.com/myflashlab/GoogleVR-ANE) -  AIR开发人员可以使用Google Virtual Reality SDK.
* [Joystick-ANE](https://github.com/StackAndHeap/joystick-ane) -  ANE操纵杆库
* [AIRControl](https://github.com/AlexanderOMara/AIRControl) -  Adob​​e AIR游戏控制器ANE.
* [AIROUYAController](https://github.com/gaslightgames/AIROUYAController) -  OUYA控制器的ANE.
* [AIRKinectv2](https://github.com/Tastenkunst/AIRKinectv2) - 适用于Windows SDK的Microsoft Kinect v2的ANE.
* [Serial/MIDI/DMX](https://github.com/benkuper/AIR-NativeExtensions) -  AIRBonjour，NativeSerial，NativeDMXController，NativeMIDI，VirtualMIDI，ExtendedMouse.
* [LeapMotionAS3](https://github.com/logotype/LeapMotionAS3) - 用于LeapMotion传感器的ANE（提供手势，图像，骨架/骨骼@ 210 FPS）.

#### System ANE
* [TaskbarProgress](https://github.com/tuarua/TaskbarProgressANE) - 在OSX和Windows 7/8/10上显示任务栏进度.
* [DesktopToast](https://github.com/tuarua/DesktopToastANE) - 在Windows 8/10和OSX中显示交互式Toast通知.
* [AlarmManager](https://github.com/myflashlab/alarmManager-ANE) - 即使您的AIR应用程序已关闭，也要运行计划任务.
* [InAppPayments](https://github.com/myflashlab/inAppPayments-ANE) - 适用于Android和iOS的相同的应用内结算和应用内购买ANE.
* [PermissionCheck](https://github.com/myflashlab/PermissionCheck-ANE) - 检查并请求Adobe Air应用程序的权限.
* [RateMe](https://github.com/myflashlab/RateMe-ANE) - 要求您的用户以最有效的方式为您的应用评分.
* [Statusbar](https://github.com/myflashlab/Statusbar-ANE) - 在运行时控制AIR应用程序中的状态栏.
* [Badge](https://github.com/myflashlab/Badge-ANE) - 控制iOS徽章值.
* [WinDebug](http://www.henke37.cjb.net/windebug/) -  Windows ANE来控制应用程序，窗口，内存，断点，元数据，注册表等.
* [Can-Open-URL](https://github.com/StickSports/ANE-Can-Open-URL) - 用于iOS的ANE，用于检测是否安装了应用程序以处理特定的URL方案.

#### Social ANE
* [Facebook](https://github.com/myflashlab/facebook-ANE) - 将Facebook SDK集成到AIR应用程序中.
* [GCM](https://github.com/myflashlab/GCM-ANE)   - 在Android和iOS上使用Google Cloud消息.  .
* [Baidu](https://github.com/lilili87222/baidu-ane-for-ios-and-android) - 适用于iOS和Android的百度ANE.

#### Analytics ANE
* [Admob](https://github.com/myflashlab/Admob-ANE) -  Admob ANE
* [GameServices](https://github.com/myflashlab/GameServices-ANE) - 适用于Android + iOS的Google游戏服务.
* [MoPub](https://github.com/StickSports/MoPub-ANE) - 针对MoPub广告的ANE
* [UMAnalytics](https://github.com/ColerYu/ANE-UMAnalytics) - 针对UMAnalytics SDK（iOS和Android）的ANE.
* [Localytics](https://github.com/randori/ANE-Localytics) - 针对移动Adobe AIR应用程序（iOS和Android）的Localytics分析.
* [Testflight](https://github.com/jlopez/ane-testflight) -  Apple TestFlight ANE.
* [Chartboost](https://github.com/ChartBoost/air) - 带有编译脚本的Chartboost SDK的ANE.
