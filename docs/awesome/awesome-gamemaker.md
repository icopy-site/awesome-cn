<div class="github-widget" data-repo="bytecauldron/awesome-gamemaker"></div>
<p align="center">
    <a href="https://gamemaker.io/en/gamemaker"><img src="https://raw.githubusercontent.com/bytecauldron/awesome-gamemaker/raw/main/images/banner.png" /></a>
</p>

## Awesome GameMaker [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Made with GameMaker](https://img.shields.io/badge/Made%20with-GameMaker-000000.svg?style=flat&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAAZlBMVEX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2BrG8stAAAAIXRSTlMABg0OFBkfcn1%2Bf4CBgoOFhoeIiouWmNDa5ebp8PX2%2B%2F6o6Vq%2BAAAAY0lEQVR42k2OWQ6AIAwFn%2BIOioobrnD%2FS4o0EeanmQxNAdErRFTWtsFq6%2BiiZozz0CSnTjYBwo0RkF8DWDLf51Ni9K%2FYdq0Fy3KAfzk97M7goK1F%2F4rGH9Kk1OlboQtEDIrmC%2BU3CVxTr%2FRMAAAAAElFTkSuQmCC)](https://www.yoyogames.com/gamemaker)

&gt; GameMaker 的精彩库、片段、指南和项目的精选列表.

[GameMaker](https://gamemaker.io/) 是 YoYo Games 推出的一款用户友好的跨平台游戏引擎，它允许初学者和高级游戏开发人员为桌面、HTML5 和控制台平台创建 2D 和 3D 游戏.



## Getting Started

- [GameMaker Manual](https://manual.yoyogames.com/#t=Content.htm)
- [GameMaker Release Notes](https://gms.yoyogames.com/ReleaseNotes.html)
- [GameMaker Marketplace](https://marketplace.yoyogames.com/)
- [Beginner GameMaker Tutorials](https://www.youtube.com/watch?v=nBCDzE9MDbk&list=PLPRT_JORnIur4v19PHXCtJ5P05vaokFdP)  - 肖恩·斯伯丁的教程. 全面介绍IDE的基本功能. 如果您是初学者，强烈建议您查看完整的播放列表. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [Advanced GameMaker Tutorials](https://www.youtube.com/watch?v=n8-MuIuOQFE&list=PL_hT--4HOvrfuDcYrTufdpgwoALAczPR2)  - 来自 DragoniteSpam 的教程，深入探讨与 GML 语言相关的更高级主题. 他们还有全面的 3D 和着色器介绍视频. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)

### Recommendations

- 如果您已经有编程经验，请学习 GameMaker 语言 (GML)，而不是视觉（拖放）功能.
- 对于像素艺术， [AESprite](https://www.aseprite.org/) 是原生精灵编辑器的流行替代品.
 - 不要害怕使用其他开发者库. 其中很多都是免费的，这是有原因的. 只要注意许可证即可.
 - IDE 和运行时的更新可能会破坏您的游戏（例如 GML 的语法更改）. 如果您在一个团队中工作，请确保您运行的是相同版本的 GMS，并且仅在收到合理警告时才进行更新. 您可以在 GMS 下载页面重新安装以前版本的 IDE.
- 除非您的游戏需要复杂的物理交互，否则通常建议避免使用 GameMaker 的内置物理系统.
 - 安排项目的例行备份. 如果您在存储库中处理较大的媒体文件，请尝试 [Git LFS](https://git-lfs.github.com/).

## Utilities

- [gm-core](https://github.com/gm-core)  - 基础实用套件和新 GameMaker 项目的良好起点. 附带生活质量方法、网络工具、测试框架、增量计时等.
- [FAST](https://github.com/Hyomoto/FAST)  - 灵活的助手工具包. 与 gm-core 类似，但具有输入和分辨率处理功能.
- [Stitch](https://www.npmjs.com/package/@bscotch/stitch)  - 管道开发套件. 包括跨项目导入、批量创建/更新精灵和声音、纹理页面管理等等. 仅在 Windows 上测试.
- [DDDEditor](https://github.com/DragoniteSpam/DDDEditorGMS2) - 通用游戏编辑器.
- [handytools](https://github.com/JujuAdams/handytools/) - Juju 的库集合在一个方便的项目中.
- [GameMaker Scaffolding](https://github.com/babaganosch/GameMakerScaffolding) - 另一个很酷的包罗万象的模板，专注于构建低分辨率、基于图块的游戏.
- [Iota](https://github.com/JujuAdams/iota) - Lightweight timestep library.
- [Stopwatch](https://github.com/Lojemiru/Stopwatch) - GameMaker 警报更换.
- [wTimer](https://mors-games.itch.io/wtimer) - 强大的警报替代方案.
- [FrogAlarm](https://github.com/colmeye/FrogAlarms) - GameMaker 警报的另一个简单替代方案.
- [fuwafuwa](https://github.com/kemonologic/fuwafuwa) - 易于使用的计时器系统.
- [Timer](https://github.com/nommiin/Timers) - 基于 JS 的 setTimeout 和 setInterval 的计时器方法.
- [Broadcast](https://github.com/JulianDicken/Broadcast) - 事件处理库.
- [EventGML](https://github.com/Soves/EventGML) - 轻量级且快速的 Node.js 风格事件库.
- [Polarca](https://github.com/VitorEstevam/polarca) - 插值函数.
- [Twerp](https://pixelatedpope.itch.io/twerp) - 类似于 lerp() 的缓动函数.
- [Coroutines](https://github.com/JujuAdams/Coroutines) - GameMaker 的异步函数.
- [GML-OOP](https://github.com/Mtax-Development/GML-OOP) - 用于操作 GameMaker 主要功能的构造函数库.
- [GML-Classes](https://github.com/Nikko-the-cat/GML-Classes) - 另一个向 GameMaker 添加 OOP 功能的项目.
- [Map](https://github.com/GameMakerDiscord/Map.gml) - 哈希表实现.
- [Matrices](https://github.com/JujuAdams/matrices) - 矩阵处理脚本的集合.
- [gm-stream](https://github.com/daikon-games/gm-stream) - 数据结构操作.
- [Promises](https://github.com/YAL-GameMaker/Promise.gml) - JavaScript Promise 的改编版.
- [Destructors](https://github.com/DatZach/Destructors) - 允许您在结构内部使用 ds_* 类型，例如列表和映射.
- [SNAP](https://github.com/JujuAdams/SNAP)  - 轻松的数据格式保存和加载. 请注意，较新版本的 GameMaker 包含“json_parse”和“json_stringify”. 但是，如果您要转换 csv、ini、xml 等，您可能会发现这非常有用.
- [Dynamo](https://github.com/JujuAdams/Dynamo) - 动态数据加载器.
- [LWO](https://github.com/tabularelf/lwo) - 使用结构的轻量级对象.
- [Gumshoe](https://github.com/JujuAdams/Gumshoe) - 简单的深度文件搜索功能.
- [Lock And Key](https://github.com/AlubJ/Lock-And-Key) - 字符串和文件加密.
- [Mathematical Scripts](https://github.com/adam-rumpf/game-maker-scripts) - 数学脚本的集合.
- [Seedpod](https://github.com/daikon-games/gm-seedpod) - 用于改善 GML 编程体验的脚本集合.
- [Trixscript](https://trixelized.itch.io/trixscript) - 通过有用的功能为您的游戏注入活力.
- [CoreExtension](https://github.com/blueburncz/CoreExtension) - CC0 编程库的集合.
- [Voxeledphoton's FreeGMScripts](https://github.com/vphoton/FreeGMScripts)  - 附加 GML 辅助函数. 有些可能对于 2.3+ 语法来说已经过时了.
- [ForEach](https://github.com/KeeVeeGames/foreach.gml) - 为数组、ds_lists、ds_maps、ds_stacks、ds_queues、ds_priorities 和结构添加 foreach 实现.
- [DeepCopy](https://github.com/KeeVeeGames/DeepCopy.gml) - 深度克隆类实例/构造结构、匿名结构和以任意顺序嵌套的数组！
- [Motion Scripts](https://avis.itch.io/motion-scripts) - 提供内置运动变量的替换方法.
- [Cottonwool](https://github.com/JujuAdams/Cottonwool) - 安全表面，无内存泄漏.
- [Canvas](https://github.com/tabularelf/Canvas) - 另一个出色的表面管理解决方案.
- [zlib functions](https://yellowafterlife.itch.io/gamemaker-zlib) - 简单的压缩/解压功能.
- [Window Taskbar](https://yellowafterlife.itch.io/gamemaker-window-taskbar)  - 仅限Windows. 闪烁游戏窗口边框和/或其任务栏按钮.
- [GMSDLL](https://github.com/YAL-GameMaker/GMSDLL) - 用于为 GameMaker 构建 DLL 的模板项目.
- [Extension Collection](https://samuel-venable.itch.io/gamemaker-extension-collection) - 一套各种扩展.
- [GMLodash](https://github.com/DatZach/GMLodash) - GML 中的函数式编程.
- [Wraptor](https://github.com/Gizmo199/Wraptor) - 包装函数库.
- [Autoframer](https://github.com/mstop4/auto-framer) - 自动处理在不同的显示器和窗口尺寸上调整游戏视图的大小.
- [gameframe](https://github.com/YAL-GameMaker/gameframe) - Windows 的自定义窗口标题和边框.
- [GML+](https://xgasoft.itch.io/gmlp) - 旨在“填补 GML 空白”的脚本集合.
- [GMLive](https://yellowafterlife.itch.io/gamemaker-live) - 实时编码/交互式编程.
- [GMEdit](https://github.com/YellowAfterlife/GMEdit) - 与 GameMaker 结合使用的代码编辑器.
- [YYP Maker](https://sahaun.itch.io/yyp-maker) - 为您制作“.yyp”文件.
- [Rubber](https://github.com/GameMakerDiscord/Rubber)  - 通过命令行编译 GameMaker 项目. 这是一个 [great guide](https://www.patreon.com/posts/how-to-build-36556955) 关于如何使用它.
- [gml-highscorer](https://github.com/Grisgram/gml-highscorer) - 高分和奖杯系统.
- [SSave](https://github.com/stoozey/SSave) - 简单的文件保存系统.
- [GMD3D11](https://github.com/blueburncz/GMD3D11) - 用于与 Windows Direct3D 连接的 DLL.
- [GMTimeLine](https://github.com/TimVN/GMTimeLine) - GameMaker 时间线的纯代码替代方案.
- [Catspeak](https://github.com/katsaii/catspeak-lang) - 用于模组支持的跨平台编程语言.
- [GMBenchmark](https://github.com/DragoniteSpam/GMBenchmark) - 一个对 GML 代码进行基准测试的工具.
- [Agenda](https://github.com/benal20/Agenda.gml) - 安排和延迟回调的执行.

## Debugging

- [rt-shell](https://github.com/daikon-games/rt-shell)  - 易于使用的游戏外壳. 创建您自己的命令、命令元数据、命令建议、历史记录等.
- [Olympus](https://github.com/bscotch/olympus#readme) - 测试框架.
- [Crispy](https://github.com/bfrymire/crispy) - GameMaker 中的单元测试.
- [Snitch](https://github.com/JujuAdams/Snitch) - 崩溃和日志系统.
- [DeerLog](https://mulfok.itch.io/gamemaker-deerlog) - 小日志作家.
- [gms2-test](https://github.com/pmarincak/gms2-test) - 单元测试框架.
- [Meta](https://github.com/nommiin/meta) - 运行时资产检查器.
- [FPS Speedometer](https://dragonite.itch.io/fps-speedometer-for-gamemaker) - 漂亮的帧率显示.
- [Duck](https://github.com/imlazyeye/duck) - 快速 GML 分析器，用于强制代码样式并检测错误.

## Input Handling

- [Input](https://github.com/JujuAdams/input) - 没有废话的游戏手柄/键盘库.
- [XeroInput](https://www.reddit.com/r/gamemaker/comments/icoh6m/xeroinput_gms23_input_handler/) - 另一个库可以处理单个操作的多个输入.
- [InputCandy](https://github.com/LAGameStudio/InputCandy) - 与 Input 类似，它充当 SDL 的包装器，但也提供测试、屏幕诊断以及与外设相关的一些其他 UI 组件.
- [Good Vibes](https://github.com/mrdaneeyul/good-vibes) - 设备振动.
- [Mouse Queue](https://github.com/YAL-GameMaker/window_mouse_queue) - 高精度跟踪 Windows 鼠标指针.
- [Native Cursors](https://yellowafterlife.itch.io/gamemaker-native-cursors) - 系统级自定义光标.

## User Interface

- [Scribble](https://github.com/JujuAdams/scribble) - 高效的多效果文本渲染器.
- [Scripture](https://pixelatedpope.itch.io/scripture) - 另一种易于使用、高度兼容的文本渲染器.
- [Chatterbox](https://github.com/JujuAdams/chatterbox) - 叙事脚本工具.
- [Textboxy](https://github.com/glitchroy/textboxy) - 简单的文本框.
- [Crochet](https://github.com/FaultyFunctions/Crochet) - 适合作家和程序员的交互式对话编辑器.
- [NotificationSystem](https://github.com/babaganosch/NotificationSystem) - GameMaker 中的通知.
- [YUI](https://github.com/shdwcat/YUI) - 具有实时重新加载、模板系统、数据绑定和拖放功能的 UI 系统.
- [Guido](https://github.com/JujuAdams/Guido) - 简单的即时模式 GUI 框架.
- [GMUI-Framework](https://github.com/AlertStudios/GMUI-Framework) - 用于构建和控制菜单的纯 GML 解决方案，与 .NET UI 类似.
- [GMS2-UI-Library](https://github.com/nabilatsoulcade/GMS2-UI-Library) - 一个充满有用脚本的库，用于在 GameMaker 中实现 UI 设计.
- [Emu UI](https://github.com/DragoniteSpam/Emu) - 常见的 UI 元素（文本输入、复选框、单选按钮、对话框等）.
- [Easy And Fast Menu](https://pkgames.itch.io/easy-and-fast-menus-for-gms-23)  - 简单的实现即可在几秒钟内启动并运行菜单. 如果您不寻找像 GMUI 这样的更大解决方案，那么这似乎是一个非常合适的选择.
- [Pause Menu](https://jasontomlee.itch.io/pause-menu-gamemaker-1-2) - 另一个较小的实现，但在菜单选项之间有一个很酷的动画.
- [Shampoo](https://zackbanack.itch.io/shampoo) - 使用类似标记语言的 GUI.
- [Magpie](https://dragonite.itch.io/magpie) - 通用库存系统.
- [ImGuiGML](https://rousr.itch.io/imguigml) - Dear ImGui 的 DLL/GML 包装器.
- [GUI Framework](https://niris.itch.io/gui-framework) - GUI implementation from Niris Games.
- [Menu Tutorial](https://www.youtube.com/watch?v=1ITZOrI2qkA&list=PLSFMekK0JFgx2vmcCnttxxhrNVTjUB8R1) - 友好的宇航员. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [Smart Clickable GUI](https://www.youtube.com/watch?v=RbBgE3cUShc) - 像素化教皇. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [RTS Selection Tool](https://gentoogames.itch.io/rts-selection-tool) - 鼠标拖动功能可在实时策略游戏中选择棋子.
- [zitk](https://github.com/TandyRum1024/zitk)  - 另一个有趣的、受 Dear ImGui 启发的 GUI 工具包. 正在开发中，但值得关注.
- [gooey](https://manta-ray.itch.io/gooey) - 适用于 GameMaker LTS 的基于 Sprite 的 UI 库.

## Localization

- [polyglot](https://github.com/daikon-games/polyglot) - 本地化库.
- [gm-i18n](https://github.com/CreativeHandOficial/gm-i18n) - 使用 JSON 文件简单快速地进行文本国际化.
- [lexicon](https://github.com/tabularelf/lexicon) - 另一个专注于简化实施的本地化解决方案.
- [GMLocalize](https://github.com/DragoniteSpam/GMLocalize2)  - 不是一个完整的本地化解决方案. 从 GameMaker Studio 2 项目中提取用于本地化的文本字符串并将其保存到 JSON 文件.
- [Small Pentapop Localization Tool](https://github.com/AntonBergaker/small_pp_localization_tool) - 与 GMLocalize 类似的导出工具，但导出为 csv.

## Physics

- [Loj Hadron Collider](https://github.com/Lojemiru/Loj-Hadron-Collider) - 强大的、像素完美的碰撞引擎.
- [On Slopes and Grids](https://forum.yoyogames.com/index.php?threads/on-slopes-and-grids-subpixel-perfect-topdown-movement-and-collision-line-without-objects.4073/) - 实现 45° 斜坡的教程.
- [GMS2 Platforming System](https://benal.itch.io/basic-modern-platforming-system) - 由 Ben Allen 实施的 GameMaker 以及 Shaun Spalding 原始 1.4 平台游戏教程的扩展.
- [Inverse Kinematics Extension](https://github.com/tonystr/Inverse-Kinematics-Extension-for-Gamemaker) - 用于处理逆运动学的库.
- [Verlet Integration Library](https://jamjamteam.itch.io/verlet-integration-gamemake-studio-2) - Sarek Lambert 的 Verlet 集成.
- [GMVerlet-Integration](https://github.com/tabularelf/GMVerlet-Integration) - 用于视觉效果的 Verlet 集成示例.
- [Top-Down Movement & Collision](https://pixelatedpope.itch.io/tdmc/devlog/156556/converting-tdmc-to-use-tiles) - 来自教皇的强大的基于对象的碰撞系统.

## Sprites

- [AESnips](https://github.com/angelwire/AESnips) - 精灵播放系统.
- [phgen](https://github.com/squircledev/phgen) - 占位符资产生成.
- [Disarm](https://github.com/NuxiiGit/disarm) - 运行时的精灵骨骼动画.
- [Spritely](https://github.com/bscotch/spritely) - 2D 视频游戏精灵的图像校正和清理.
- [PixelUpscaler](https://github.com/JujuAdams/Pixel-Art-Upscaling) - 像素艺术升级着色器，为 GameMaker 提供尴尬的分辨率.
- [ASESync](https://sahaun.itch.io/asesync) - 自动同步 GameMaker 中的 aesprite 文件.
- [conveyorbelt](https://github.com/imissmyfriends/conveyorbelt)  - 与 ASESync 类似. 将 Aesprite 文件导出到 GameMaker sprite.
- [Collage](https://github.com/tabularelf/Collage)  - 纹理页面生成器和图像管理器. 模仿 GameMaker 的纹理页面打包，同时提供更高的灵活性.

## Audio

- [FML](https://github.com/Nikkilae/fml) - FMOD Studio API 的 GameMaker 绑定.
- [FMODGMS](https://github.com/mstop4/FMODGMS) - 这并不支持 FMOD 提供的所有功能，并且该项目本身已被搁置.
- [Echo/Delay Effect](https://madwolf-studios.itch.io/audio-echodelay-effect-for-gamemaker-studio-2) - 优化延迟效果.
- [wavload](https://github.com/nkrapivin/wavload) - 演示如何从外部加载 .wav 文件.
- [audioExt](https://github.com/tabularelf/audioExt) - 健全的外部装载机/卸载机管理器.
- [ExternalAudio](https://github.com/NuxiiGit/ExternalAudio) - 在运行时加载外部 .wav 文件.
- [Phonix](https://github.com/Andre-404/Phonix/)  - 紧凑型音频系统. 非常适合动感音乐！
- [Vinyl](https://github.com/JujuAdams/Vinyl) - 实时更新音频系统.
- [LineAudio](https://github.com/WangleLine/LineAudio) - 音频助手功能.
- [Bard](https://github.com/gl326/bard-audio)  - 用于在 GameMaker 中设计和实现良好音频的引擎. 已更新以利用更新的 GameMaker 音频效果.

## Levels

- [LDtk to GMS](https://shynif.itch.io/ldtk-to-gms) - LDtk 进口商.
- [LDtkParser](https://github.com/evolutionleo/LDtkParser) - 高级 LDtk 导入器.
- [Room Data Inspector](https://github.com/heygleeson/GM-RoomInspector) - 收集房间数据并将其存储为 JSON 供以后使用. 
- [Random Dungeon Generator](https://github.com/BlaXun/Random-Dungeon-Generator-GMS-2.3) - 结合用户定义的房间来创建一个地牢.
- [Random Level Generator](https://github.com/GameMakerDiscord/random-level-gen-gms2) - 使用 GameMaker 的随机关卡生成示例（类似于核王座）.
- [Wave Function Collapse](https://quadolorgames.itch.io/wfc-gml-demo) - 生成随机图块地图，但在当前状态下尚未准备好生产.
- [Draw A Dungeon](https://gentoogames.itch.io/draw-a-dungeon-gamemaker) - 将您的房间布局转换为随机的地牢.
- [Destructible Terrain](https://github.com/niksudan/gms2-destructible-terrain) - GameMaker Studio 中使用曲面和网格的可碰撞、可破坏地形的示例.
- [Cellular Automata Caves](https://alessiogamedev.itch.io/gms-cellular-automata-algorithm) - 在几百毫秒内生成巨大的洞穴.

## Particles

- [Particle Editor](https://gamemakercasts.itch.io/particle-editor) - 使用简单的 UI 创建粒子并导出为 GML 代码.
- [Particles Wrapper](https://github.com/GamemakerCasts/particles) - 一个简单的粒子系统包装器，旨在使创建粒子变得有趣和简单.
- [Advanced Particles](https://limekys.itch.io/advanced-particle-system) - 带有自己的增量计时方法的粒子实现.

## Lighting

- [Bulb](https://github.com/JujuAdams/Bulb) - 2D 照明和阴影.
- [Lighting System 2D](https://github.com/borup3/Lighting-System-2D) - 根据存储库，需要 GameMaker 2.2+.
- [GameMaker Lighting Engine](https://github.com/bilouw/Gamemaker-Lighting-Engine) - 基于图块的照明引擎，可投射阴影.
- [Lighting Systems](https://www.youtube.com/playlist?list=PLYVea5brHS8YHECGPoEp4_gWU-k6nWzUy) - GrizzliusMaximus 使用阴影投射实现非常快速的动态 2D 光照. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)

## Shaders

- [TransFX](https://short-bread.itch.io/transfx) - 过渡库.
- [Post Processing Effects](https://foxyofjungle.itch.io/post-processing-fx) - 36 种高品质、可定制的效果.
- [BJRTFX](https://zikbakguru.itch.io/bjrtfx) - Zik 的 CRT 实用着色器.
- [bktGlitch](https://odditica.itch.io/bktglitch) - 故障着色器.
- [H O R R I - F I](https://gizmo199.itch.io/horri-fi) - VHS 着色器.
- [Cyberpunk Hologram Effect](https://gentoogames.itch.io/cyberpunk-hologram-effect) - Create and customize your own holographic effect using this easy-to-implement asset.
- [Depth Sorted Sillouettes](https://pixelatedpope.itch.io/depth-sorted-silhouette-example)  - 演示基于着色器的深度排序 sillouettes 的示例项目. 在 PC、Mac、HTML5 和 Android 上进行了测试.
- [GMShaders.com](https://gmshaders.com/)  - Xor 的着色器教程. 最初托管于“xorshaders.com”.
- [1PassBlur](https://github.com/XorDev/1PassBlur/wiki) - 具有可调半径的模糊着色器.
- [Bokeh Blur](https://github.com/XorDev/Bokeh/wiki)  - 1PassBlur 的扩展，提供不同的外观. 类似于真实的镜头模糊. 虽然它比 1Pass 或 Dual-Kawase 慢很多.
- [Dual-Kawase](https://github.com/XorDev/Dual-Kawase/wiki) - 模糊着色器限制半径但非常高效.
- [Xor's Halftone](https://xordev.itch.io/halftone)  - 一个美妙的、多功能的半色调着色器. 许多可调整的设置.
- [Voronoi](https://github.com/XorDev/GMS-Voronoi-Pixels) - Voronoi 图上的采样像素.
- [Fire-Fun](https://github.com/XorDev/Fire-Fun/wiki) - 一些有趣的魔法火球.
- [Jump Flooding](https://terohannula.itch.io/jump-flooding-algorithm) - 使用着色器制作的 GameMaker 跳跃洪水算法.
- [Outline Shader](https://github.com/Grisgram/gml-outline-shader-drawer) - 轮廓着色器.
- [Chameleon](https://github.com/Lojemiru/Chameleon) - 调色板交换器.
- [Xpanda](https://github.com/GameMakerDiscord/Xpanda) - 在着色器中包含外部文件的代码.
- [Shadertoy to GameMaker](https://iarri.github.io/Shadertoy2GM/) - 转换shadertoy.com GLSL 着色器以在GameMaker 中运行.
- [Shader Tutorials](https://www.youtube.com/watch?v=ch4BYqkL1w8&list=PL0kTSdIvQNCNE-BDKOlYu628AalMmXy_P) - 游戏牧师. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [Shader Tutorials](https://www.youtube.com/watch?v=a4S7LXx6-sQ&list=PL_hT--4HOvrdkihto8Xu7hhp1-5Gj8zsa) - Dragonite垃圾邮件. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)

## 3D

- [3D-2D](https://github.com/YoYoGames/3D-2D) - 将 3D 模型转换为 2D 精灵的官方工具.
- [BBMOD](https://github.com/blueburn-cz/BBMOD)  - 3D 渲染解决方案. 附带多个模块来导入 obj、3D 相机设置、与 ColMesh 集成等.
- [ColMesh](https://forum.yoyogames.com/index.php?threads/colmesh-3d-collisions-made-easy.82765/) - 来自 TheSnidr 的 3D 碰撞库.
- [BSP 4 GMS](https://cdlegasse.itch.io/ozarq-bsp-4-gms)  - 将 BSP 文件导入 GameMaker. 目前只是一个演示，但值得关注.
- [dotobj](https://github.com/JujuAdams/dotobj) - 用原生 GML 编写的轻量级 .obj/.mtl 3D 模型加载器.
- [Bronze Box](https://github.com/cicadian/Bronze-Box) - 如何从 2D 网格构建 3D 世界模型的示例.
- [Camera3D](https://gizmo199.itch.io/camera3d) - 简单的 3D 相机设置.
- [Blender to GameMaker](https://github.com/blender-to-gmstudio) - 用于将 Blender 模型导出到 GameMaker 以及从 GameMaker 导入 Blender 模型的脚本集合.
- [DmrVBM](https://github.com/Dreamer13sq/DmrVBM-blender-to-gms2) - 导入/导出工具将顶点缓冲区数据从 Blender 加载到 GMS 中.
- [Penguin](https://dragonite.itch.io/penguin) - 3D模型转换工具.
- [Three Mice In a Trench Coat](https://github.com/XorDev/ThreeMiceInaTrenchcoat) - GameMaker 3D 游戏的来源.
- [sPart](https://marketplace.yoyogames.com/assets/7299/spart-3d-particle-system) - 来自 TheSnidr 的 3D 粒子系统.
- [Terrain Editor](https://dragonite.itch.io/terrain)  - 地形编辑器. 导出到 gm 模型、obj 或顶点缓冲区.
- [Cardboard](https://github.com/JujuAdams/Cardboard) - 等距 3D 渲染器.
- [Snowy Snow](https://dragonite.itch.io/snowy-snow) - 3D 雪着色器.
- [3D Fragment Point Lights](https://danieldavis.itch.io/ddg-point-light-shader-system) - 使用着色器的 3D 点光源.
- [3D GameMaker Playlist](https://www.youtube.com/watch?v=ojfN--tdSNM&list=PL_hT--4HOvrcML9uqHe4fwBVTm650Vy3V) - Dragonite垃圾邮件. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [3D Collisions Playlist](https://www.youtube.com/watch?v=o7kjtTEMpeU&list=PL_hT--4HOvrf_VYo26LNl3zN5uwfuC3CC) - Dragonite垃圾邮件. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [3D Optimization Playlist](https://www.youtube.com/watch?v=knfAZbJJKNY&list=PL_hT--4HOvrf_CJSA7fVU1tkjGVv5Sq2t) - Dragonite垃圾邮件. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)

## Sprite Stacking

- [Beginners Guide to Sprite Stacking](https://medium.com/@avsnoopy/beginners-guide-to-sprite-stacking-in-gamemaker-studio-2-and-magica-voxel-part-1-f7a1394569c0)  - Avis 的精灵堆叠初级读本. 另请查看 dev_dwarf 的第 2 部分.
- [Fauxton3D](https://gizmo199.itch.io/fauxton3d) - 精灵堆叠引擎.
- [Sprite Stacking Tutorials](https://www.youtube.com/watch?v=VIDN-nG3EOU&list=PL3Kbpztq9qwT9MbW_k4yyJU__or1r8P2j) - Gizmo199. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)

## Networking

- [Warp](https://github.com/evolutionleo/Warp) - 一个功能丰富的多人游戏框架，用 GameMaker 和 Node.js 编写.
- [EZ Networking](https://jasontomlee.itch.io/easy-gms-networking-platformer-build) - 具有聊天功能的主机/客户端实施.
- [Patchwire-GM](https://github.com/gm-core/patchwire-gm) - 如果您想在没有整个 gm-core 套件的情况下使用此实现，则来自 gm-core 的网络库.
- [GMHandshake](https://gist.github.com/nkrapivin/c73f5a962466a4ecb63187a009a300d8) - 演示网络握手的要点.
- [HTTP GML](https://github.com/Sidorakh/http.gml) - 接收 GET 请求并上传 GML 格式的文件.
- [GMNest](https://github.com/TimVN/GMNest) - HTML5 游戏的 Socket.IO 扩展.
- [MultiClient](https://github.com/tabularelf/MultiClient) - 用于网络开发的非 dll、多客户端启动器.
- [Multiplayer Networking Tutorial](https://www.youtube.com/watch?v=NbsXRuNijlo&list=PLxaJReoxlrY_S4MrCYjzFCSrNX1TUX626) - 巫师. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [Good GameMaker Rollback](https://springrollgames.itch.io/ggmr) - 回滚网络代码库.

## Integrations

- [DHook](https://github.com/tabularelf/DHook) - 不和谐整合.
- [GMS2_RPC](https://github.com/Mtax-Development/GMS2_RPC) - 另一个 Discord 集成.
- [NekoPresence](https://marketplace.yoyogames.com/assets/9526/nekopresence) - 哎呀，所有 Discord 集成.
- [Steamworks.gml](https://github.com/YAL-GameMaker/steamworks.gml) - GameMaker: Studio 中对 Steamworks SDK 支持的各种扩展.
- [Parworks](https://github.com/nkrapivin/Parworks) - YYG Steamworks 扩展的附加功能.
- [GOG.gml](https://github.com/GameMakerDiscord/GOG.gml) - GOG.com SDK 支持的本机扩展.
- [GMTwitch](https://github.com/GameMakerDiscord/GMTwitch) - 抽搐集成.

## Camera

- [GameMaker Cameras: As Simple as Possible](https://www.youtube.com/watch?v=_g1LQ6aIJFk) - Pope 关于 GameMaker 相机系统的指南. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [Camera System Guide](https://maddestudiosgames.com/gms2-meet-the-camera-system/) - GameMaker 中的相机入门.
- [Pixel Perfect Smooth Camera](https://github.com/YAL-GameMaker/pixel-perfect-smooth-camera) - 像素完美且流畅的相机示例.
- [Dynamic Splitscreen](https://maddestudios.itch.io/gms2-project-dynamic-splitscreen) - 本地多人分屏实现，当玩家靠近时合并摄像机.
- [STANNcam](https://github.com/jack27121/STANNcam) - 相机和分辨率管理器.
- [Camera All-In-One](https://jasontomlee.itch.io/allinone-camera) - 编辑器、屏幕抖动、视图大小调整、跟随模式、屏幕效果等.

## Sequences

- [Sequences Tutorial](https://www.youtube.com/watch?v=WO6gzhrx5b8) - 肖恩·斯伯丁. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [Making Splash Screen Sequences](https://www.youtube.com/watch?v=hTh5UpFxx1E) - 马什街机. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)

## State Machines

- [SnowState](https://github.com/sohomsahaun/SnowState) - 鲁棒的有限状态机.
- [FastSM](https://github.com/JulianDicken/FastSM) - SnowState 的轻量级替代品.
- [wFSM](https://mors-games.itch.io/wfsm) - 另一个易于使用的有限状态机库.
- [True State](https://pixelatedpope.itch.io/truestate) - 功能丰富的有限状态机来处理复杂的对象.
- [Pinocchio](https://github.com/JujuAdams/Pinocchio) - 基于状态的动画系统.

## Pathing

- [Aquila](https://dragonite.itch.io/aquila) - A* 寻路实施.
- [A-Star-Pathing](https://github.com/helloalbertdang/A-Star-Pathing) - 另一个 A* 寻路实现.
- [Grid-based Pathfinding Scripts](https://proton-squid.itch.io/pathfinding) - 灵活的寻路系统，具有 3 种不同的算法.

## Useful Extras

- [Animated Flag](https://github.com/Grisgram/gml-animated-flag) - 顶点动画标志.
- [Video Player Extension](https://forum.yoyogames.com/index.php?threads/video-player-for-windows-macos-and-ubuntu.77882/)  - 播放视频. 不过，最新版本的GMS已经支持视频了.
- [GMESCAPI](https://marketplace.yoyogames.com/assets/9529/gmescapi) - 网络摄像头捕获.
- [Smile](https://github.com/zbanack/smile) - 情绪分析.
- [Danmaku Project](https://github.com/OmegaX1000/DanmakuProject) - 弹幕地狱引擎.
- [OrbinautFramework](https://github.com/TrianglyRU/OrbinautFramework) - 制作经典索尼克游戏的精确框架.
- [Dynamic Turn System](https://gentoogames.itch.io/turn-based-combat-system-for-gamemaker) - 非常适合用作构建回合制战斗/游戏的基础.
- [Isometric Tactical RPG Framework](https://gentoogames.itch.io/isometric-tactical-rpg-framework)  - 提供入门资源来创建等距棋盘游戏. 包括动态转向系统.
- [Mouse Trail Effect](https://all-x.itch.io/gms2-mouse-trail-effect) - 展示如何使用基元追踪线条以创建彩色轨迹.
- [Starfield Generator](https://github.com/PixelProphecy/gml_starfield_generator) - 用 GameMaker 的 GML 语言生成星空的脚本.
- [CleanShapes](https://github.com/JujuAdams/Clean-Shapes) - GameMaker 的抗锯齿原语库.
- [GMLScripts.com](https://www.gmlscripts.com/script/index) - 数十个帮助程序脚本，其组织方式与官方文档类似.
- [GM48 Resources](https://gm48.net/resources) - 来自社区的免费资源，让您在 GameMaker Studio、游戏开发和游戏 Jam 方面变得更好.
- [GameMakerHow](https://gamemakerhow.com/) - 另一个很棒的网站，可作为 GameMaker 问答存储库，解答您可能在 GameMaker 中提出的各种问题.
- [obj_podcast](https://objpodcast.com/) - 以 Gamedev 为中心的播客，以 GameMaker 社区成员为特色.
- [Dracula Theme](https://github.com/dracula/gamemaker-studio) - IDE 的深色主题.
- [Gruvbox Theme](https://github.com/heygleeson/Gruvbox-GMTheme) - IDE 的复古 Groove 主题.
- [2.3 Syntax in Detail](https://yal.cc/gamemaker-2-3-syntax-in-details/) - 来自 Yal 的 GML 语法功能/变化的完整指南.
- [GameMaker Garbage Collection](https://gist.github.com/DatZach/96a30d6ae4225f8ec152719e57aed26b) - GML 中垃圾收集的工作原理.
- [GitHub Yacc to GML Fix](https://www.reddit.com/r/gamemaker/comments/n5m35l/a_simple_fix_for_github_incorrectly_detecting/) - 告诉 GitHub 你的仓库都是 GML，而不是 Yacc.
- [GameMaker Repo Badges](https://github.com/matthiaszarzecki/MadeWithGameMakerStudioBadges) - 添加到您的自述文件中的精美徽章.
- [GameMaker Discord Community GitHub](https://github.com/GameMakerDiscord)  - 你制作过想要分享的游戏制作工具吗？ 考虑将其提交到官方 Discord 的 GitHub.
- [Source Control with Git & GameMaker](https://www.youtube.com/watch?v=UZG-P68xWio&list=PLSFMekK0JFgzmyDxVxj5Cctafu5UX_vUC) - 友好的宇航员. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [Game Resolution & Aspect Ratio Management](https://www.youtube.com/watch?v=_g1LQ6aIJFk&list=PLXkVsacazW2qvdnKNzgBLkUwlgi3FU-VO) - 像素化教皇. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [Setting up a Virtual Machine for GameMaker](https://www.youtube.com/watch?v=cK5k1_zN4eM) - 疯子弥迦. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [Making Attacks Feel Good](https://www.youtube.com/watch?v=RWkMsD2WUz8) - 水滴鱼. ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)
- [vim-GML](https://github.com/JafarDakhan/vim-gml) - GameMaker 的高质量 Vim 语法突出显示.
- [List of GameMaker Games](https://steamdb.info/tech/Engine/GameMaker/) - 使用 GameMaker 发布的 Steam 游戏列表.
- [Rousr Release](https://gitlab.com/rousr-release/) - Rousr 团队未维护的项目（如果有人问 OutsideTheBox/Dissonance 去了哪里）.

## Blogs

- [RefresherTowel](https://refreshertowelgames.wordpress.com/category/tutorial/) - 包含多个关于关卡生成的帖子.
- [Tony Str](https://tonystr.net/articles) - 一些关于使用 json、正则表达式和在 gml 中绘制圆圈的精彩文章.
- [Katsaii](https://www.katsaii.com/content/blog/posts.html) - 一些关于更高级 gml 主题的文章.

## YouTube

- [Jordan Guillou](https://www.youtube.com/channel/UCBmOLRTaPrfOxnTqpCLrwdQ) - 业余爱好者独立开发者，提供一些与 GameMaker 相关的教程.
- [DragoniteSpam](https://www.youtube.com/c/DragoniteSpam) - 涵盖 GameMaker 的高技术元素，重点是 3D.
- [Shaun Spalding](https://www.youtube.com/c/ShaunSpalding)  - YoYo Games 前社区经理. 拥有各种适合初学者的 GameMaker 教程以及有关 GameMaker 新功能的有用更新.
- [FriendlyCosmonaut](https://www.youtube.com/c/FriendlyCosmonaut) - 关于在 GameMaker 中构建农业 RPG 的精彩播放列表以及其他几个教程.
- [PixelatedPope](https://www.youtube.com/c/PixelatedPope) - GameMaker 分辨率管理、相机、GUI 等指南.
- [Xor](https://www.youtube.com/c/XorDev) - 大量以 3D 为重点的着色器演示.
- [GamingEngineer](https://www.youtube.com/c/GamingEngineer)  - 一位在社区工作多年的 GameMaker 开发人员. 他们有各种各样的视频展示 GameMaker 的功能，重点是 3D.
- [TheSnidr](https://www.youtube.com/c/TheSnidr) - 许多很棒的 GameMaker 3D 展示和教程.
- [Peyton Burnham](https://www.youtube.com/channel/UCfh2Q3TsvlxM1S2GvXQ4eeQ) - 自上而下的射击游戏和角色扮演游戏的 GameMaker 教程.
- [Gaming Reverends](https://www.youtube.com/channel/UC7fkptPD1FHQyDc9Fnm9S_A) - 如果您想学习有关 GameMaker 着色器的基础材料，“Shaders for Hobby-Programmers”播放列表绝对值得一看.
- [Let's Learn This Together](https://www.youtube.com/c/LetsLearnThisTogether) - 小型独立开发公司，专注于提供 GameMaker 指南.
- [Matharoo](https://www.youtube.com/c/GameMakerStationMatharoo) - 大量免费的 GameMaker 教程和有关 GameMaker 的新闻.
- [GravityShift Games](https://www.youtube.com/c/SlasherXGAMES/) - 一些特定类型的 GameMaker 教程，将数据库集成到 GameMaker 等.
- [Slyddar](https://www.youtube.com/c/Slyddar/) - 专门提供 DnD 和 GML 教程的频道.
- [SamSpadeGameDev](https://www.youtube.com/@SamSpadeGameDev) - 为游戏爱好者提供深入的编码教程.

## Community

[![GameMaker Forums](https://img.shields.io/badge/Forums-6AA916?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAAZlBMVEX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2BrG8stAAAAIXRSTlMABg0OFBkfcn1%2Bf4CBgoOFhoeIiouWmNDa5ebp8PX2%2B%2F6o6Vq%2BAAAAY0lEQVR42k2OWQ6AIAwFn%2BIOioobrnD%2FS4o0EeanmQxNAdErRFTWtsFq6%2BiiZozz0CSnTjYBwo0RkF8DWDLf51Ni9K%2FYdq0Fy3KAfzk97M7goK1F%2F4rGH9Kk1OlboQtEDIrmC%2BU3CVxTr%2FRMAAAAAElFTkSuQmCC&&logoColor=white)](https://forum.yoyogames.com/index.php)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/gamemaker/)
[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/gamemaker)

## Special Thanks

JujuAdams、FaultyFunctions、Gleb Tsereteli、Shaun Spalding、DragoniteSpam、Nick Ver Voort、PixelatedPope、Tony Strømsnæs、HeartBeast、Xor、Gaming Reverends、Matharoo、YellowAfterlife、Gizmo199、Avis、Josh Wilson、Lojemiru

## Footnotes

- 这是基于以下列表 [GameMaker Libraries](https://github.com/FaultyFunctions/GameMakerLibraries) 以及来自 Gleb Tsereteli 的附加链接/详细信息.
 - 由于 GML 语法更改，大多数链接资源仅适用于“GameMaker 2.3+”. 然而，如果您使用 GameMaker 1.4，如果有人对其项目进行向后移植，大多数库创建者都会很感激.  ☺
- 如果您需要更多通用游戏开发资源，请查看 [Awesome Gamedev](https://notabug.或者g/Calinou/awesome-gamedev) 或者 [MagicTools](https://github.com/ellisonleao/magictools#readme).

 *GameMaker® 是 YoYo Games™ 的财产. 此列表与 YoYo Games 无关.*

## Contributing

有什么很棒的东西要分享吗？ 查看 [Contributing Guidelines](https://github.com/bytecauldron/awesome-gamemaker/blob/main/CONTRIBUTING.md).

![Keybindings](https://github.com/bytecauldron/awesome-gamemaker/raw/main/images/keybindings.png)
