<div class="github-widget" data-repo="tomodachi94/awesome-computercraft"></div>
<!--lint ignore-->

## Awesome ComputerCraft [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/tomodachi94/awesome-computercraft/master/assets/cc-tweaked-logo.png" align="right" width="100">](https://computercraft.cc)

&gt; 有用的库、程序、文献和模组 [ComputerCraft](https://computercraft.info) 和 [its forks](https://computercraft.cc).

 **ComputerCraft** 是 Minecraft 的模组，它添加了可使用 Lua 编程语言编程的计算机.  **ComputerCraft: Tweaked** 是更新版 Minecraft 模组的一个分支.

如果你想贡献，请参阅 [CONTRIBUTING.md](https://github.com/tomodachi94/awesome-computercraft/blob/master/./CONTRIBUTING.md) . 如果您还有其他问题，请参阅 [FAQ](https://github.com/tomodachi94/awesome-computercraft/wiki/FAQ).

关于缩写的说明：`CC` 是 ComputerCraft，`CC:T` 是 ComputerCraft: Tweaked，`CC:R` 是 ComputerCraft: Restitched.

<!-- TOC -->
<!-- /TOC -->

## Mods
### ComputerCraft mods

- [ComputerCraft: Tweaked](https://computercraft.cc) - 用于现代版 Minecraft 的原始 ComputerCraft 的分支.
- [ComputerCraft: Restitched](https://www.curseforge.com/minecraft/mc-mods/cc-restitched) - 一组 CC:T 补丁，允许在 Fabric 上运行它. 
- [ComputerCraft](http://computercraft.info) - 添加计算机以允许执行 Lua 程序的模组. 

### Add-on mods

- [Advanced Peripherals](https://www.curseforge.com/minecraft/mc-mods/advanced-peripherals) - 添加各种外围设备和 API 以与其他模组交互的模组. 
- [Computronics](https://wiki.vexatos.com/wiki:computronics) - 添加各种外围设备的模组，特别是用于检测世界中的事件和处理声音. 
- [Plethora](https://plethora.madefor.cc)  - 添加外围设备并允许访问许多块的模组. 此外，它还允许将播放器作为外围设备进行操作. 
- [CC:C Bridge](https://www.curseforge.com/minecraft/mc-mods/cccbridge) - 一个增加了对 [Create mod](https://ftb.fandom.com/wiki/Create) 到 ComputerCraft. 
- [Turtlematic](https://www.curseforge.com/minecraft/mc-mods/turtlematic) - 一个最终目标是让海龟变得如此有用的模组，所以你永远不需要任何其他自动化模组！
- [UnlimitedPeripheralWorks](https://www.curseforge.com/minecraft/mc-mods/unlimitedperipheralworks)  - 添加各种外围设备以扩展 CC:T 功能的模组. 还为其他模组添加了很多外围设备.

### Resource packs

- [ComputerCreate](https://modrinth.com/resourcepack/computercreate) - 一个资源包，以 [Create](https://ftb.fandom.com/wiki/Create) 反对.

## Lua programs
### Utility

- [ComputerCraft Advanced Shell (cash)](https://cash.madefor.cc) - ComputerCraft 的 Bourne 兼容外壳. 
- [Consult](https://consult.madefor.cc) - 强调易用性和与许多系统兼容的文本编辑器. 
    - [Consult: Recrafted](https://github.com/manaphoenix/CONSULT_RECRAFTED) - Recrafted 系统咨询的分支.
- [gist](https://pastebin.com/zSLPYpqs) - 一个 GitHub Gist 下载/上传程序，旨在扩展内置的 `pastebin` 程序，但用于 Gists. 
- [Howl](https://github.com/SquidDev-CC/Howl) - CC 和 CC:T 的构建系统.
- [LuaIDE](http://www.computercraft.info/forums2/index.php?/topic/12347-) - 用于在游戏中编辑 Lua 文件的成熟 IDE.
- [Mildly Better Shell (MBS)](https://github.com/SquidDev-CC/mbs) - 一个改进的外壳，包括回滚和改进的完成分辨率.
- [ModemShark](https://gist.github.com/MCJack123/56ca71555d9c0f78d4c985f1e9ad28e8) - 具有简单 UI 的调制解调器数据包嗅探器.
- [netshell](https://github.com/lyqyd/cc-netshell) - 从另一台计算机访问计算机的外壳.
- [OrangeBox](https://github.com/walksanatora/orangebox) - ComputerCraft 计算机的虚拟化支持.
- [rawshell](https://gist.github.com/MCJack123/8c8861e5e3082d2bed18d07641b5b2cc) - netshell 的现代替代品，支持 CraftOS-PC 的“原始模式”格式，具有文件传输、加密、密码、WebSockets 等功能.
- [unicornpkg](https://unicornpkg.madefor.cc) - 不错的现代包管理.
- [FSEncrypt](https://gist.github.com/MCJack123/32c56917dc61da336ec0e8ca6aae39f8) - 透明的文件系统加密.

### Library

- [Anavrins' ChaCha20](http://www.computercraft.info/forums2/index.php?/topic/25474-) - 实施 [ChaCha20](https://en.wikipedia.org/wiki/ChaCha20-Poly1305).
- Anavrins 的哈希库：
    - [MD5](https://pastebin.com/6PVSRckQ) - 实施 [MD5](https://en.wikipedia.org/wiki/MD5).
    - [SHA-1](https://pastebin.com/SfL7vxP3) - 实施 [SHA-1](https://en.wikipedia.org/wiki/SHA-1) 和 [HMAC](https://en.wikipedia.org/wiki/HMAC) 支持.
    - [SHA-256](http://www.computercraft.info/forums2/index.php?/topic/8169-) - 实施 [SHA-256](https://en.wikipedia.org/wiki/SHA-2) 支持 [HMAC](https://en.wikipedia.org/wiki/HMAC) 和 [PBKDF2](https://en.wikipedia.org/wiki/PBKDF2).
- [AUKit](https://mcjack123.github.io/AUKit/) - ComputerCraft 的典型音频处理和转换库. 
- [Basalt](https://basalt.madefor.cc/) - 强调用户体验的 GUI 库.
- [Bigfont](https://pastebin.com/3LfWxRWh) - 一个可以轻松编写不同字体大小内容的库.
- [C3D](https://c3d.madefor.cc/) - 高级 3D 渲染 API.
- [CC-Archive](https://github.com/MCJack123/CC-Archive) - 用于存档和取消存档文件的各种库.
- [dbprotect](https://gist.github.com/MCJack123/4cf6fc941a2d412b4195caafb9636363) - 对“调试”API 的保护包装，允许限制对受保护函数中上值的访问.
- [ecc.lua](https://www.computercraft.info/forums2/index.php?/topic/29803-) - 实施 [elliptic-curve cryptography](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography).
- [ecnet](https://github.com/migeyel/ecnet) - 在 ComputerCraft 中保护网络通信.
- [GuiH](https://guih.madefor.cc) - 强大的 GUI 和图形库.
- [IsometriH](https://github.com/9551-Dev/IsometriH) - 一个 [isometric rendering](https://en.wikipedia.org/wiki/Isometric_video_game_graphics) 引擎.
- [Luz](https://github.com/MCJack123/Luz) - 一种极轻的 Lua 文件压缩算法.
- [Milo](https://github.com/kepler155c/opus-apps/wiki/Milo-(crafting---storage-system) ) - 制作和库存管理系统. 请注意，这取决于 OpusOS 和 Plethora.
- [Pine3D](https://github.com/Xella37/Pine3D) - 专为快速设计的 3D 渲染引擎.
- [RedRun](https://gist.github.com/MCJack123/473475f07b980d57dd2bd818026c97e8) - 一个用于在退出程序后在 CraftOS 后台运行进程的小型库，类似于 DOS TSR.
- [Tamperer](https://github.com/Fatboychummy-CC/Tamperer) - 允许轻松创建设置菜单的库.
- [VeriCode](https://gist.github.com/MCJack123/7752c85918bcf23ada028abd615e8750) - 提供简单的代码签名功能，用于通过调制解调器安全地传输代码.

### Fun

- [AUKit austream](https://github.com/MCJack123/AUKit/blob/master/austream.lua) - 基于AUKit，一个简单的音频播放器，支持WAV、DFPWM、AIFF、AU和FLAC.
- [battleship](https://gist.github.com/MCJack123/7082da1d2ac725c33ff77389877ad7f4) - 流行的双人游戏的实现 *[Battleship](https://en.wikipedia.org/wiki/Battleship_(game))*.
- [CCDoom](https://github.com/Xella37/CCDoom) - 这 [*Doom* shooter](https://en.wikipedia.org/wiki/Doom_(1993_video_game)) 使用 Pine3D 移植到 ComputerCraft.
- [CC-Minecraft](https://github.com/Xella37/CC-Minecraft) - *Minecraft* 使用 Pine3D 移植到 ComputerCraft.
- [LuaGB](https://github.com/MCJack123/LuaGB)  - ComputerCraft 的 Game Boy（Color）模拟器端口. 在 CraftOS-PC 上效果最好.
- [lunatic86](https://github.com/MCJack123/lunatic86) - ComputerCraft 的 8086 PC 仿真器端口.
- [Musicify](https://github.com/knijn/musicify) - 用于在 ComputerCraft 上播放音乐的轻量级客户端：已调整.
	- [tracc](https://github.com/MCJack123/tracc/tree/playAudio) - ComputerCraft 的 XM 模块跟踪器/播放器，支持游戏中的 8 通道复音.
- [YahtCC](https://gist.github.com/MCJack123/4f7f1635998f44630c8440e81213d32e) - *的实施[Yahtzee](https://en.wikipedia.org/wiki/Yahtzee)* dice game.
- [YouCube](https://youcube.madefor.cc) - 在 ComputerCraft 中访问 YouTube 和其他服务.
- [YTP2CCP](https://pastebin.com/nxEMWHY3) - 转换评论的 YouTube 钢琴音符并在 CC:T 中演奏.

### Operating systems

- [LevelOS](http://install.leveloper.cc) - 旨在模仿 Windows 的现代 GUI 操作系统.
- [Opus](https://github.com/kepler155c/opus) - 包含 GUI、应用程序商店和许多与系统相关的 API 的操作系统.
- [Phoenix](https://phoenix.madefor.cc)  - 强调模块化的操作系统. 它实现了自己的内核.
    - Phoenix 目前处于 alpha 阶段.
- [Recrafted](https://github.com/ocawesome101/recrafted) - 重写 CraftOS，旨在实现完整的功能对等，同时保持“更合理的 API 设计”.
- [UnBIOS](https://gist.github.com/MCJack123/42bc69d3757226c966da752df80437dc)  - 一个“撤销”CraftOS 的程序，将系统返回到运行 BIOS 之前的相同状态. 对操作系统开发很有用.

### Economy

- [msks](https://github.com/MasonGulu/msks) - 现代、简单的 Krist 虚拟货币商店.

### Mod-specific programs

&gt; 注意：此部分包含专用于模组的程序，在实用程序部分没有意义.

- [DraconicControl](https://pastebin.com/UqVHTht5) - 允许从计算机控制 Draconic Evolution 的 Draconic Reactor.
- [ReactorControl and TurbineControl](https://pastebin.com/p4zeq7Ma) - 自动管理大型反应堆中的反应堆和涡轮机.
    - [ReactorControl patched](https://pastebin.com/2ZrbnH5w)  - 上面的程序递归地使用了 `parallel` API，这可能会导致它崩溃. 已经开发了一个补丁来解决这个问题.

## Non-Lua programs

&gt; 注意：此部分适用于不是 mod 或 Lua 程序的程序，并且**直接**与此列表的主题相关.

### Bridging

&gt; 注意：本小节适用于允许在游戏外（主要是通过互联网）访问 ComputerCraft 内容的程序.

- [Cloud Catcher](https://github.com/SquidDev-CC/cloud-catcher) - 一个程序，可以在游戏之外与计算机进行交互.
- [Ultron Control](https://gitlab.com/Merith-TK/ultron-control) - 公开用于控制海龟的 Web API 的程序.

### Emulators

- [CCEmuX](https://emux.cc) - 直接执行模组的 CC 和 CC:T 模拟器.
- [Copy Cat](https://github.com/SquidDev-CC/copy-cat) - 在网络浏览器中运行的 CC:T 模拟器.
- [CraftOS-PC](https://www.craftos-pc.cc) - 用 C++ 编写的 CC:T 模拟器，旨在提高速度.

### Plugins

- [CraftOS-PC for VS Code](https://www.craftos-pc.cc/docs/extension) - 在 VSCode 中通过 CraftOS-PC 操作和运行程序的扩展.
- [`craftos2-plugins`](https://github.com/MCJack123/craftos2-plugins) - CraftOS-PC 的小插件集合，由创建者维护.
- [VSCode Extensions for ComputerCraft](https://marketplace.visualstudio.com/items?itemName=lemmmy.computercraft-extension-pack)  - 不言自明. 包含 CC 和 CC:T 功能的自动完成，以及 Lua 语言服务器.

### Tools

- [cc-tstl-template](https://github.com/MCJack123/cc-tstl-template) - TypeScriptToLua 编译器的模板，允许在 TypeScript 中编写 ComputerCraft 程序.
- [sanjuuni](https://github.com/MCJack123/sanjuuni) - 将图像和视频文件快速转换为各种格式以便在 ComputerCraft 中播放和流式传输的程序.

### Economy

- [KristForge](https://github.com/tmpim/kristforge) - Krist 虚拟货币的矿工.
- [Krist Server](https://github.com/tmpim/Krist) - 用于 CC 和 CC:T 的虚拟货币. 
- [KristWeb2](https://github.com/tmpim/KristWeb2) - 用 React 编写的 Krist 网络钱包.

## Literature
### Essays

- [JackMacWindows's essay on ComputerCraft OSes](https://gist.github.com/MCJack123/4b2bca21bdc0cf5c67ce7177326c2154) - 包含构建适当操作系统的建议、劝阻和鼓励.
- [JackMacWindows's essay on sane APIs](https://gist.github.com/MCJack123/39ac0847579b3676cc098aca5860c758) - 提供使您的 API 易于使用的建议.

### Tutorials
#### Basics
- [Direwolf20's tutorials](https://www.youtube.com/watch?v=wrUHUhfCY5A) - 解释 ComputerCraft 编程基础知识的一系列视频. 
- [Sethbling's tutorials](https://www.youtube.com/watch?v=DSsx4VSe-Uk) - 往上看.
- Lyqyd 的*计算机基础*系列（[I](http://www.computercraft.info/forums2/index.php?/topic/15033-computer-basics-i), [II](http://www.computercraft.info/forums2/index.php?/topic/15041-computer-basics-ii/), [III](http://www.computercraft.info/forums2/index.php?/topic/20905-computer-basics-iii/)) - 虽然有点过时，但它们非常适合您开始旅程.
- [The FTB Wiki's Getting Started guide for ComputerCraft](https://ftb.fandom.com/wiki/Getting_Started_(ComputerCraft)) - 一个有用的全面入门资源.

#### Moderate or advanced
- [Bomb Bloke's *Guide to Coroutines*](http://www.computercraft.info/forums2/index.php?/topic/25670-bbs-guide-to-coroutines/) - 解释为什么你不应该使用协程，并包括使用它们的教程. 

### Charts and tables

- [JackMacWindows's coroutine flow chart](https://cdn.discordapp.com/attachments/477911902152949771/959769473437560862/Blank_Diagram_1_Page_1.png)  - 演示协程如何工作. 每列代表一个协程的代码流.
- [KingOfGameYami's event flow chart](https://media.discordapp.net/attachments/477911902152949771/729709228675301380/image.png) - 演示程序运行时的事件流.
<!--lint ignore-->
- [Wojbie's decimal font chart](https://cdn.discordapp.com/attachments/477911902152949771/933498000385400862/1642633650325141456271.png) 和 [Cake's hex font chart](https://thox.madefor.cc/_images/encodings-cc-chars.png) -  Contains decimal 和 hex mappings to ComputerCraft font characters.
- [Emma's ComputerCraft compatibility chart](https://docs.google.com/spreadsheets/d/1s4d21cL3QrUyegEzYaVXvqDr1zNorgyZ-fDWeopIC1k/edit?usp=sharing) - 显示模拟器和游戏内模组之间的兼容性.

### Other lists

- [Awesome Lua](https://github.com/LewisJEllis/awesome-lua) - 特定于 Lua 编程语言的很棒的列表.
- [Hengestone's list of languages which compile to Lua](https://github.com/hengestone/lua-languages/blob/master/README.md) - 编译为 Lua 的语言列表.

## Resources

- [Tweaked.cc documentation](https://tweaked.cc) - 包含 CC 和 CC:T 中大多数方法的文档.
- [CC's forums](https://computercraft.info/forums2) - 一个非常有价值的资源，充满了教程和程序.
- [CC:T's forums](https://forums.computercraft.cc) - 也非常有价值，但较​​新.
- [Minecraft Computer Mods Discord](https://discord.gg/H2UyJXe) - 用于在 CC 和 CC:T 中获得编程帮助的 Discord 服务器.
- [ComputerCraft's subreddit](https://reddit.com/r/computercraft) - 用于炫耀您的 ComputerCraft 创作以及获得帮助的 subreddit.
- [Lua's manual](https://www.lua.org/manual/)  - 包含有关 Tweaked.cc 中未涵盖的方法的文档. 第 5 节（辅助库）和第 6 节（标准库）特别有趣.
