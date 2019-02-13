## ![GameboyIcon](http://i.imgur.com/ROUq7NT.gif) Awesome Game Boy Development

#### [Join us on Discord](https://discord.gg/gpBxq85) [![Discord Badge](https://img.shields.io/badge/dynamic/json.svg?label=chat&colorB=green&suffix=%20online&query=count&uri=https%3A%2F%2Fgbhh.avivace.com%2Fapi%2Fdiscord)](https://discord.gg/gpBxq85)

 精彩的Game Boy（Color）开发资源，工具，文档，相关项目和开源ROM的精选列表.  灵感来自于 [awesome](https://github.com/sindresorhus/awesome) 列出的东西.

## Contents

- [Introduction](#introduction)
    + [Disambiguation](#disambiguation)
- [Community](#community)
- [Documentation](#documentation)
    + [Misc](#misc)
    + [Cheatsheets, Tables](#cheatsheets--tables)
  * [Game Boy Color](#game-boy-color)
  * [Hardware](#hardware)
  * [Peripherals](#peripherals)
  * [Cartridges](#cartridges)
- [Emulator Development](#emulator-development)
  * [Testing](#testing)
- [Software Development](#software-development)
  * [Assemblers](#assemblers)
  * [Compilers](#compilers)
    + [Experimental/Proof of Concepts](#experimentalproof-of-concepts)
  * [Emulators](#emulators)
  * [Tools](#tools)
- [Programming](#programming)
  * [ASM](#asm)
    + [Sources](#sources)
    + [Timings](#timings)
    + [Boilerplates](#boilerplates)
    + [Syntax highlighting packages](#syntax-highlighting-packages)
  * [C](#c)
- [Homebrews](#homebrews)
  * [ASM](#asm-1)
  * [C](#c-1)
  * [Demos](#demos)
- [Reverse Engineering](#reverse-engineering)
  * [Game Disassemblies](#game-disassemblies)
- [Related projects](#related-projects)
  * [Directories](#directories)
  * [Websites](#websites)
- [About](#about)
  * [Contribute](#contribute)
  * [License](#license)
  * [Acknowledgements](#acknowledgements)
  * [Sponsors](#sponsors)

## Introduction

- [The Game Boy, a hardware autopsy](https://www.youtube.com/playlist?list=PLu3xpmdUP-GRDp8tknpXC_Y4RUQtMMqEu).
- [The Ultimate Game Boy Talk](https://media.ccc.de/v/33c3-8029-the_ultimate_game_boy_talk).
- [Emulation of Nintendo Game Boy](https://github.com/Baekalfen/PyBoy/blob/master/PyBoy.pdf) -  Game Boy硬件概述，以及构建模拟器的视角.


> #### Disambiguation
>
&gt;虽然本文档主要关注原始（1989）Game Boy（DMG），但* Game Boy Color *（GBC）和* Super Game Boy *（SGB）是非常相似的系统，几乎没有重要的区别，例如：
>
&gt;  - 不同的硬件规格
&gt;  - 特定的硬件和软件功能
&gt;  - 特定寄存器
&gt;  - 特定的错误和可利用的行为
>
&gt;如果您的目标是为SGB或GBC开发软件，或者您想知道它在其他系统上的运行方式，您可能希望利用并适应这些差异，检查 [Game Boy Color](#game-boy-color) 类别并查找对GBC / CGB和SGB的特定引用.

## Community

- [gbdev Discord Server](https://discord.gg/gpBxq85)
- [`#gbdev` on EFnet](http://chat.efnet.org/?channels=gbdev) -  IRC频道.
- [gbdev.gg8.se Wiki](http://gbdev.gg8.se/wiki/articles/Main_Page)
- [devrs.com/gb](http://devrs.com/gb) - 现场的旧家：示例，来源，完整的文档，指南，教程和各种工具.


## Documentation

- **[Game Boy Programming Manual](https://archive.org/download/GameBoyProgManVer1.1/GameBoyProgManVer1.1.pdf)**  - 任天堂官方Game Boy编程和硬件手册.
- [Pan Docs](http://gbdev.gg8.se/wiki/articles/Pan_Docs) - 历史综合技术参考，wikified，更正和更新.
- [The Cycle-Accurate Game Boy Docs](https://github.com/AntonioND/giibiiadvance/blob/master/docs/TCAGBD.pdf) -  AntonioND的精确文档，可以制作出精确周期的Game Boy模拟器.
- [Game Boy: Complete Technical Reference](https://gekkio.fi/files/gb-docs/gbctr.pdf) 通过Gekkio.

#### Misc

- [Introduction to Game Boy Hacking](http://pepijndevos.nl/sha2017/workshop.pdf) - 讲习班介绍基本装配，调试和逆向工程.
- [Everything You Always Wanted To Know About GAME BOY](http://www.emulatronia.com/doctec/consolas/gameboy/gameboy.txt) - 但不敢问
- [GBSOUND.txt](https://github.com/bwhitman/pushpin/blob/master/src/gbsound.txt) - 详细介绍Game Boy声音引擎的文档.
- [GB Instructions](https://raw.githubusercontent.com/gb-archive/salvage/master/txt-files/gb-instructions.txt) Game Boy程序集命令.
- [GB ASM Tips](https://raw.githubusercontent.com/gb-archive/salvage/master/txt-files/gb-asm-tips.txt) -  Jeff Frohwein在Assembly中编写的一些提示.
- [gbdev FAQs](http://www.devrs.com/gb/files/faqs.html) - 必须由Jeff Frohwein阅读.
- [Game Boy Bootrom](http://www.neviksti.com/DMG/DMG_ROM.asm) -  DMG bootrom的评论转储.
- [GB Technical Information](http://fms.komkon.org/GameBoy/Tech/) - 一些旧的代码资源.
- [Differences between the Z80 and the gameboy's processor](http://www.z80.info/z80gboy.txt)
- [Gameboy 2BPP Graphics Format](http://www.huderlem.com/demos/gameboy2bpp.html) - 有关Game Boy如何将VRAM图块数据解释为彩色像素的信息.

#### Cheatsheets, Tables

- [Game Boy Crib Sheet](https://github.com/JustinLloyd/Gameboy-Cribsheet/raw/master/Current%20Release/Gameboy%20Crib%20Sheet%20990823-0325.pdf) - 一个方便的可打印参考表，带有ASM操作码，存储位置等等（[repository](https://github.com/JustinLloyd/Gameboy-Cribsheet)).
- [OP Codes cheatsheet](http://pastraiser.com/cpu/gameboy/gameboy_opcodes.html)
- [rednex gbz80 opcode reference](https://rednex.github.io/rgbds/gbz80.7.html)
- [Opcode table](http://goldencrystal.free.fr/GBZ80Opcodes.pdf)
- [Opcode table with timings and flags](http://www.devrs.com/gb/files/opcodes.html)
- [Game Boy CPU Instruction Set Sheet (GCISheet)](http://www.devrs.com/gb/files/GBCPU_Instr.html) - 可用指令集的备忘单.

### Game Boy Color

- [Game Boy Color Bootstrap ROM](https://tcrf.net/Game_Boy_Color_Bootstrap_ROM)
- [Unused Palettes](https://tcrf.net/Notes:Game_Boy_Color_Bootstrap_ROM)
- [GBC colorization palettes in the BIOS](https://forums.nesdev.com/viewtopic.php?p=114388&sid=c3d4ce08cfd9d9c834958d4f148750c3#p114388)
- [High resolution GBC schematics](https://drive.google.com/file/d/1a0HTmBiRxoZw4XgLEDzwGCugfTfdIQwT/view?usp=sharing)
- [GameBoy Color Boot ROM Disassembly](https://gist.github.com/drhelius/6063265)

### Hardware

- [DMG Schematics](http://gbdev.gg8.se/wiki/articles/DMG_Schematics) - 硬件原理图.
- [The Game Boy Project](http://marc.rawer.de/Gameboy/Docs/GBProject.pdf) - 提供有关实现三个8位双向并行端口的硬件和详细结构信息的研究.
- [Related custom hardware](https://github.com/Gekkio/gb-hardware) - 由Gekkio.
- [ESP8266 GB Dev Board](https://github.com/applefreak/esp8266-gameboy-dev-board) - 开发Game Boy配件开发板，由ESP8266驱动.
- [ESP8266 GB Printer](https://github.com/applefreak/esp8266-gameboy-printer) - 模拟GB打印机并允许您使用WiFi检索图像的设备.
- [fruttenboel](http://verhoeven272.nl/fruttenboel/Gameboy/index.html) - 包含硬件信息的页面，与控制台连接的定制板以及其他相关项目.
- [Game Boy hardware database](https://gbhwdb.gekkio.fi/) - 各种类型的Game Boy游戏机的数据和照片.

### Peripherals

- [Dan Docs](https://shonumi.github.io/dandocs.html) - 模糊Game Boy硬件文档.
- [Edge of Emulation](https://shonumi.github.io/articles.html) ，一系列关于模仿和调查Game Boy配件的文章.  也可作为 [technical documents](https://github.com/shonumi/gbe-plus/tree/master/src/docs/technical) 在GBE +模拟器文档中.
    * [Mobile Adapter GB](https://shonumi.github.io/articles/art14.html) -  Game Boy Color上的互联网连接和DLC.
    * [The Game Boy Printer](https://shonumi.github.io/articles/art2.html)
    * [Pocket Sonar](https://shonumi.github.io/articles/art13.html) - 内置声纳硬件的蓝色推车.
    * [Zok Zok Heroes](https://shonumi.github.io/articles/art8.html)  -  Zok Zok Heroes的Full Changer，动作激活配件.
    * [Infrared Madness](https://shonumi.github.io/articles/art11.html) -  Game Boy Color上的红外通信.
    * [Game Boy 4-Player Adapter](https://shonumi.github.io/articles/art9.html) -  DMG-07.
    * [Barcode Boy](https://shonumi.github.io/articles/art7.html) - 第一款Game Boy卡片扫描仪.
    * [Barcode Taisen Bardigun](https://shonumi.github.io/articles/art6.html) -  90年代末DMG-GBC条形码阅读器.
- [DMG-07 Technical Documentation](https://raw.githubusercontent.com/shonumi/gbe-plus/master/src/docs/technical/DMG_07.txt)
- [Game Boy Camera RE](https://github.com/AntonioND/gbcam-rev-engineer) - 有关GB Camera的文档以及使用Arduino UNO对其进行逆向工程的工具.
- [Creating photo realistic images with neural networks and a Gameboy Camera](http://www.pinchofintelligence.com/photorealistic-neural-network-gameboy/)
- [The Game Boy Printer](https://shonumi.github.io/articles/art2.html) - 有关打印机硬件，通信协议以及游戏用于实现打印功能的常规例程的深入技术文档.
- [Ben Heck Reverse Engineers Game Boy Printer](https://www.youtube.com/watch?v=43FfJvd-YP4) （勘误：使用过的热敏纸已过期，4种颜色实际上是可打印的）.
- [Arduino Game Boy Printer Emulator](https://github.com/mofosyne/arduino-gameboy-printer-emulator) - 通过带有Arduino Nano的Game Boy Link电缆模拟Game Boy打印机.
- [Mobile Game Boy Adapter](https://bulbapedia.bulbagarden.net/wiki/Mobile_Game_Boy_Adapter)
- [GB KISS LINK MODEM](http://nectaris.tg-16.com/GB-KISS-LINK-FAQ-hudson-gameboy-nectaris.html)

### Cartridges

- [AntonioND's docs](https://github.com/AntonioND/giibiiadvance/tree/master/docs) - 更正了墨盒标题数据的原理图和信息.
- [Gekkio's Game Boy cartridge types](http://gekkio.fi/blog/2015-02-14-mooneye-gb-gameboy-cartridge-types.html) - 有关现有墨盒类型的概述.
-  Gekkio的墨盒分析：
  + [DMG-BEAN-02](http://gekkio.fi/blog/2015-05-18-mooneye-gb-cartridge-analysis-dmg-bean-02.html);
  + [MBC1](http://gekkio.fi/blog/2015-05-17-mooneye-gb-cartridge-analysis-fortress-of-fear.html);
  + [no MBC](http://gekkio.fi/blog/2015-02-28-mooneye-gb-cartridge-analysis-tetris.html).
- [Game Boy Cartridges Schematics](http://www.devrs.com/gb/files/gb.html) -  MBC2和MBC3类型的原理图.
- [Cartridges PCB photos](https://imgur.com/a/D5bpC)
- [Reiner Ziegler's Game Boy page](http://reinerziegler.de.mirrors.gg8.se/)   - 商用和自制可编程墨盒和编程系统.  提供了教程，接线和原理图.
- [MBC1+RAM+Battery cartridge Schematic](http://www.devrs.com/gb/files/mbc1.gif) -  Jeff Frohwein的第一张原理图.
- [MBC1 and MBC2 cartridges circuits](http://fms.komkon.org/GameBoy/Tech/Carts.html) 并解释这些MBC如何实际存储开关和控制RAM.
- [GB Rom List](CartridgeList.csv) - 每个游戏的可导航表格，其中包含有关其墨盒的详细信息.
- [Game Boy cartridge PCB photos](http://gekkio.fi/blog/2016-03-19-game-boy-cartridge-pcb-photos.html)
- [Emulating a GameBoy Cartridge](https://dhole.github.io/post/gameboy_cartridge_emu_1/) - 使用开发板STM32F4模拟Game Boy盒式磁带的功能.
- [Wolf](http://www.happydaze.se/wolf/) - 带有协处理器的Game Boy墨盒.
- [Homebrew-Gameboy-Cartridge](https://github.com/dwaq/Homebrew-Gameboy-Cartridge) - 使用Atmel AT49F040作为ROM的盒式PCB的Eagle库，原理图和电路板文件.
- [Homebrew Gameboy Color Cartridge](https://github.com/Xyl2k/Gameboy-Color-Cartridge) -  EEPROM供电盒式磁带的电路板布局.

## Emulator Development

- [Reverse Engineering fine details of Game Boy hardware](https://www.youtube.com/watch?v=GBYwjch6oEE) ([errata](https://gekkio.fi/blog/2018-02-05-errata-for-reverse-engineering-fine-details-of-game-boy-hardware.html)） -  Gekkio在Disobey 2018上的43分钟谈话.
- [DMG-01](http://blog.ryanlevick.com/DMG-01/public/book/)   -  Rust中的教育Gameboy模拟器和一本解释其发展的配套书.  *[Oh Boy! Creating a Game Boy Emulator in Rust](https://media.ccc.de/v/rustfest-rome-3-gameboy-emulator)*是Rust Fest 18就此发表的演讲.
- [Building a Game Boy emulator in JavaScript](http://imrannazar.com/gameboy-Emulation-in-JavaScript) - 一步一步的教程.
- [Writing a Game Boy emulator, Cinoop](https://cturt.github.io/cinoop.html)
- [RealBoy Emulator](https://realboyemulator.wordpress.com/posts/) - 关于RealBoy仿真器设计和实现的一系列帖子.
- [Codeslinger](http://www.codeslinger.co.uk/pages/projects/gameboy.html) - 记录构建模拟器的另一系列帖子.
- [Why did I spend 1.5 months creating a Gameboy emulator?](http://blog.rekawek.eu/2017/02/09/coffee-gb/) - 博客文章.
- [binjgb rewind](https://binji.github.io/2017/12/31/binjgb-rewind.html) - 实现*倒带*功能.
- [binjgb on the web](https://binji.github.io/2017/02/26/binjgb-on-the-web-part-1.html) - 将binjgb仿真器移植到Web Assembly. [(Part 2)](https://binji.github.io/2017/02/27/binjgb-on-the-web-part-2.html)
- [binjgb debugging hangs](https://binji.github.io/2017/05/03/debugging-hangs.html) - 调查仿真怪癖
- [Emulation Accuracy](https://github.com/Gekkio/mooneye-gb/blob/master/docs/accuracy.markdown)
- [Decoding Gameboy Z80 opcodes](https://gb-archive.github.io/salvage/decoding_gbz80_opcodes/Decoding%20Gamboy%20Z80%20Opcodes.html) - 如何对Game Boy指令进行算法解码，而不是为500多条指令编写一个巨大的switch-case语句.
- [Porting a GO Game Boy emulator to WebAssembly](https://djhworld.github.io/post/2018/09/21/i-ported-my-gameboy-color-emulator-to-webassembly/)
- [List of open source emulators](EMULATORS.md)

### Testing

- [Blargg's test roms](http://gbdev.gg8.se/files/roms/blargg-gb-tests/)
- [Gekkio's test roms](https://gekkio.fi/files/mooneye-gb/latest/)
- [SameSuite](https://github.com/LIJI32/SameSuite)
- [GB Accuracy Tests](http://tasvideos.org/EmulatorResources/GBAccuracyTests.html)
- [144p Test Suite](https://github.com/pinobatch/240p-test-mini/tree/master/gameboy) - Port of Artemio Urbina's 240p Test Suite to the Game Boy.

## Software Development

The [To C Or Not To C](https://gist.github.com/ISSOtm/4f4d335c3fd258ad0dfc7d4d615409fd) 本文概述了Game Boy的功能，讨论了可用开发工具的优缺点，并提供了编写更高效代码的技巧.

### Assemblers

- [RGBDS](https://github.com/rednex/rgbds) - 汇编程序和链接程序包. [Documentation](https://rednex.github.io/rgbds/).
- [ASMotor](https://github.com/csoren/asmotor)   - 针对Game Boy以及其他CPU的汇编引擎和开发系统.  由原始RGBDS作者撰写. [Documentation](https://github.com/csoren/asmotor/blob/develop/doc/documentation.pdf).
- [wla-dx](https://github.com/vhelin/wla-dx) - 另一种GB-Z80 / Z80 / ..多平台交叉汇编程序包. [Documentation](http://www.villehelin.com/wla.txt).

### Compilers

- [GBDK](http://gbdk.sourceforge.net/)   - 一组能够在** C **中开发的工具.  包括一组用于最常见要求的库，并生成就绪ROM文件. [Documentation](http://gbdk.sourceforge.net/doc/gbdk-doc.pdf).
    + [gbdk-osx](https://github.com/x43x61x69/gbdk-osx) - 为OS X上的最新编译器修补GBDK 2.96a.
    + [gbdk-n](https://github.com/rotmoset/gbdk-n)   - 旨在更新gbdk库以与SDCC的新版本兼容，并为构建roms提供帮助.  不支持ROM存储，因此将ROM大小限制为32K.

#### Experimental/Proof of Concepts

- [Wiz](https://github.com/wiz-lang/wiz) - 用于在复古控制台平台上编写自制软件的高级汇编语言（Game Boy，NES，Atari 2600等）.
- [gbforth](https://github.com/ams-hackers/gbforth) - A Forth-based Game Boy development kit.
- [gbasm](https://github.com/BonsaiDen/gbasm) - 用于Game Boy z80汇编代码的基于JavaScript的编译器.
- [tniASM](http://www.tni.nl/products/tniasm.html) - 宏组装.
- [Assembler](https://github.com/ulrikdamm/Assembler) - 用Swift编写的汇编程序.
- [llvm-gbz80](https://github.com/Bevinsky/llvm-gbz80) / [clang-gbz80](https://github.com/Bevinsky/clang-gbz80) -  Clang / LLVM端口到GBZ80 CPU（类似于不推荐使用 [euclio/llvm-gbz80](https://github.com/euclio/llvm-gbz80)).

### Emulators

- [BGB](http://bgb.bircd.org/)   - 强大的仿真器和调试器.  提供准确的硬件仿真.
- [SameBoy](https://github.com/LIJI32/SameBoy) - 精确的仿真器，具有广泛的强大调试功能.
- [Mooneye GB](https://github.com/Gekkio/mooneye-gb) -  Rust的研究项目和模拟器.
- [mGBA](https://github.com/mgba-emu/mgba) - 现代跨平台GBA模拟器，也运行GB / GBC游戏.
- [Binjgb](https://github.com/binji/binjgb)   - 通过大多数测试的5Kloc仿真器.  *倒带*功能.  使用WebAssembly在浏览器中运行.
- [Gambatte](https://github.com/sinamas/gambatte) - 跨平台和准确的模拟器.

[Complete list of open source emulators](EMULATORS.md)

### Tools

- [ZGB](https://github.com/Zal0/ZGB) - 为原始Game Boy创建游戏的小引擎（扩展gbdk，更多信息 [here](http://zalods.blogspot.com/2017/01/zgb-little-engine-for-game-boy.html)).
- [DevSound](https://github.com/DevEd2/DevSound) - 可插入自制软件中的声音驱动程序，支持脉冲宽度操作，琶音和多个波形.
- [Carillon Player](http://gbdev.gg8.se/files/musictools/Aleksi%20Eeben/Carillon%20Editor.zip) - 游戏男孩和游戏男孩颜色的音乐引擎.
- [Game Boy Tile Data Generator](https://github.com/chrisantonellis/gbtdg) -  HTML5 / JS Web应用程序，它将位图图像转换为适用于基于图块的图形应用程序（尤其是GB）的十六进制数据.
- [Harry Mulder's GB Development](http://www.devrs.com/gb/hmgd/intro.html) -  Game Boy Tile Designer和Game Boy Map Builder工具的一些来源和主页.
- [GBTiles](https://github.com/bashaus/gbtiles) - 将使用Harry Mulder的平铺设计器（GBTD）创建的.GBR文件和使用Harry Mulder的地图生成器（GBMB）创建的.GBM文件转换为不同的格式，以便与Game Boy和GBDK一起使用.
- [GBT PLAYER](https://github.com/AntonioND/gbt-player) - 适用于Game Boy的音乐播放器库和转换器套件，可与RGBDS配合使用.
- [ROM Header Utility](http://catskull.net/GB-Logo-Generator/) - 一种在线工具，用于检查和修改ROM​​的标题数据，包括徽标.
- [gbcamextract](https://github.com/jkbenaim/gbcamextract) - 从Game Boy Camera保存中提取照片.
- [GBExtended](http://www.tensi.eu/thomas/programming/gameboy/gbextended.html) - 扩展gbdk的C库.
- [bmp2cgb](https://github.com/gitendo/bmp2cgb) - 用于Game Boy Color开发的图形转换器，提供实时调色板调整.
- [png2gb](https://github.com/LuckyLights/png2gb) - 用于将图像文件转换为游戏boy .c数组的CLI工具.
- [gbdk-lib-extension](https://github.com/ProGM/gbdk-lib-extension) -  Michael Hope为Game Boy Development Kit提供的一小部分资源和工具.
- [GB-convert](https://github.com/exezin/gb-convert) -  Game Boy平铺转换和地图编辑工具（转换为装配）.
- [cart-dumper](https://github.com/Palmr/cart-dumper) -  Game Boy Cartridge Dumper ROM.
- [Game Boy LCD sniffing](https://github.com/svendahlstrand/game-boy-lcd-sniffing) - 使用逻辑分析仪嗅探Game Boy的LCD.
- [Dot Matrix Game Editor](http://www.dotmatrixgame.com/) - 用于类似C语言的游戏男孩编程的IDE，称为GBL，具有许多其他功能，如平铺和地图提取，WLA-DX组装等.
- [brewtool](http://make.vg/brewtool/) - 一组原始编辑器/转换器工具，用于制作与自制ROM开发一起使用的资产.
- [Game Boy Text Tools](https://github.com/raphaklaus/gameboy-text-tools) - 用NodeJS编写的Game Boy ROM的文本操作和翻译工具集
- [mmlgb](https://github.com/SimonLarsen/mmlgb) -  Nintendo Game Boy的MML解析器和GBDK声音驱动程序.
- [XPMCK](https://github.com/bazzinotti/XPMCK) - 基于MML的音乐编译器，支持Game Boy和Game Boy Color.
- [mgbdis](https://github.com/mattcurrie/mgbdis) - 具有RGBDS兼容输出的Game Boy ROM反汇编程序.
- [Retr0 GB](https://bitbucket.org/HellSuffering/retr0-gb/) - 用于创建游戏的引擎（扩展GBDK）.
- [awake](https://github.com/devdri/awake) -  Game Boy反编译器.
- [swapdump](https://github.com/sanqui/swapdump) -  Game Boy手机的诊断实用程序.
- [Gameboy-LinkUp](https://github.com/JustinLloyd/Gameboy-LinkUp) -  Game Boy LinkUp串行有线网络项目.
- [vtGBte](https://github.com/paul-arutyunov/vtGBte) - 简约的ncurses拼贴编辑器.
- [tpp1](https://github.com/TwitchPlaysPokemon/tpp1) - 自定义GB / GBC内存/硬件映射器的定义和规范，作为MBC的功能超集.
- [libstdgb](https://github.com/delwink/libstdgb) - 有用的Game Boy操作（SDCC）的AC库.

## Programming

使用开发工具链为Game Boy开发软件的指南，教程和工具 [Software Development](#software-development) 章节.

### ASM

- **[gb asm tutorial](https://eldred.fr/gb-asm-tutorial)**  - 逐步教程，构建几个ROM以配合其解释.
- [ASMSchool](http://gameboy.mongenel.com/asmschool.html) -  Duo关于GB / GBC装配和拆卸编码的一系列课程.
- [hardware.inc](https://github.com/tobiasvl/hardware.inc) - 包含用于RGBDS项目的Game Boy硬件定义的标准包含文件.
- [Assembly tutorial by David Pello](https://gb-archive.github.io/salvage/tutorial_de_ensamblador/tutorial_de_ensamblador%20[La%20decadence].html)   - 学习生成gb的asm代码的好文档.  许多重要主题的简要说明.  许多带注释源代码的示例.
- [assemblydigest](https://github.com/assemblydigest/gameboy) - 探索Game Boy编程技巧：
  - [Making an Empty Game Boy ROM (in Wiz)](http://assemblydigest.tumblr.com/post/77203696711/tutorial-making-an-empty-game-boy-rom-in-wiz)
  - [Making Art for the Game Boy](http://assemblydigest.tumblr.com/post/77404621743/tutorial-making-art-for-the-game-boy)
- [Beginner's Guide to Reverse Engineering GB](http://web.archive.org/web/20150511145100/http://www.bennvenn.com/Beginners_Guide_To_Reverse_Engineering.htm) - 关于拆卸和逆向工程的一些启动技巧.
- [FlappyBoy: Making a simple Game Boy Game](http://voidptr.io/blog/2017/01/21/GameBoy.html)
- [Super Game Boy development](https://imanoleasgames.blogspot.no/2016/12/games-aside-1-super-game-boy.html) - 一步一步的教程，以实现超级游戏男孩功能（框架和调色板）.
- [GameBoy programming tutorial: Hello World!](http://peterwynroberts.com/?p=10) - 一步一步的教程.
- [DMGreport](https://github.com/lancekindle/DMGreport) - 汇编中的游戏编程教程.

#### Sources

代码，效果，概念证明和一般非完整游戏的碎片.

- [dev'rs ASM section](http://www.devrs.com/gb/asmcode.php) - 许多工作演示和来源.
- [EmmaEwert's experiments](https://github.com/EmmaEwert/gameboy)   - 原型程序的集合，大多数只是玩弄.  其中包括日光效果，透明度和天气效果.

#### Timings

- [Game Boy DMA transfer routines](http://exez.in/gameboy-dma) - 了解和使用DMA例程.
- [Nitty Gritty Gameboy Cycle Timing](http://blog.kevtris.org/blogfiles/Nitty%20Gritty%20Gameboy%20VRAM%20Timing.txt)
- [Mode3 Sprite Timing](https://www.reddit.com/r/EmuDev/comments/59pawp/gb_mode3_sprite_timing/)
- [GameBoy Color DMA-Transfers v0.0.1](http://gameboy.mongenel.com/dmg/gbc_dma_transfers.txt)
- [STAT interrupt timings](http://gameboy.mongenel.com/dmg/istat98.txt)
- [Video Timing](https://github.com/jdeblese/gbcpu/wiki/Video-Timing)

#### Boilerplates

- [gb-template](https://github.com/exezin/gb-template) - 具有基本功能的模板，例如游戏手柄输入，DMA传输和地图/平铺数据加载.
- [rgbds-template](https://github.com/nezticle/rgbds-template) - 使用RGBDS的Game Boy的基本hello-world示例.
- [Game Boy Assembly Language Primer](http://www.devrs.com/gb/files/galp.zip) - 具有内存定义，复制例程和IBM字体tilemap的简单模板代码.
- [bootstrap.gb](https://github.com/yenatch/bootstrap.gb) - 一个示例Game Boy项目.
- [Gameboy Boilerplate](https://github.com/junebug12851/GameboyBoilerplateProj) -  Boilerplate项目，可以更快地进入游戏的实际汇编代码.

#### Syntax highlighting packages

- [Atom language package for RGBASM](https://atom.io/packages/language-rgbasm) -  RGBDS程序集的Atom语法高亮显示.
- [gbz80-highlight](https://github.com/ISSOtm/gbz80-highlight) - 用于RGBDS程序集的Notepad ++和gedit语法高亮显示文件.
- [Vim syntax file for the Game Boy assembler RGBASM](http://www.vim.org/scripts/script.php?script_id=819) - 用于RGBDS组装的Vim语法高亮显示.
- [Vim syntax file for RGBDS](https://github.com/Leandros/dotfiles/blob/master/.vim/syntax/rgbds.vim) - 用于RGBDS程序集的另一个Vim语法高亮文件.
- [rgbds_textmate](https://github.com/Bananattack/rgbds_textmate)   - 一些语法高亮的规则，用于在Z80程序集中编码为Textmate语言插件.  适用于Sublime Text 2和3 \.  该语法专为RGBDS和Game Boy特定的Z80指令而设计.
- [Z80 Assembly support for Visual Studio Code](https://github.com/Imanolea/z80asm-vscode)
- [rgbds-vscode](https://github.com/DonaldHays/rgbds-vscode) -  RGBDS GBZ80汇编的Visual Studio代码语言扩展
- [rgbds-mode](https://github.com/japanoise/rgbds-mode) - 用于RGBDS组装的Emacs主要模式.

### C

- [8-Bit Wonderland](http://belial.blarzwurst.de/gbpaper/paper.pdf) - 关于Game Boy如何工作以及如何开始为其开发工作代码的精心编写的介绍性文档.
- [Grooves Game Boy Programming](https://github.com/gbdk-salvage/grooves-game-boy-programming) - 关于在Game Boy游戏中实现各种游戏机制的完整课程.
- [How to Write a Simple Side Scrolling Game](http://pastebin.com/F3tHLj68) - 旧的（但仍然相关）教程.
- [Just another simple tutorial](http://pastebin.com/gzT47MPJ)
- [GBDK Tutorial](https://refreshgames.co.uk/2016/04/18/gameboy-tutorial-rom/) - 开始使用GBDK的相当简单的游戏演示.
- [GBDK Sprite](http://gbdev.gg8.se/wiki/articles/GBDK_Sprite_Tutorial) - 提供用于获取多个精灵以显示和制作动画的工作流程.
- [GBDK Color](http://gbdev.gg8.se/wiki/articles/GBDK_Color_Tutorial) - 通过为精灵，背景和窗口层添加颜色，扩展您对Game Boy的基本精灵的了解.
- [GBDK Joypad](http://gbdev.gg8.se/wiki/articles/GBDK_Joypad_Tutorial) - 详细说明了使用GBDK的游戏手柄.
- [Game Boy home of Flavor](http://www.personal.triticom.com/~erm/GameBoy/) - 一些完整的游戏和来源.
- [GBDK Configuring and Programming Tutorial](https://videlais.com/2016/07/03/programming-game-boy-games-using-gbdk-part-1-configuring-programming-and-compiling/) - 配置GBDK，使用平铺，碰撞精灵，GBTD，GBMB，内存管理和ROM银行.
- [Simplified GBDK examples](https://github.com/mrombout/gbdk_playground)
- [GBDK Programming Video Tutorials](https://www.youtube.com/playlist?list=PLeEj4c2zF7PaFv5MPYhNAkBGrkx4iPGJo) - 一系列视频教程，介绍初学者使用GBDK进行编程

## Homebrews

完整的开源游戏.

- [Homebrew Hub](https://gbhh.avivace.com) - 为Game Boy制作的每个非官方自制软件（可移动/触摸）：社区领导尝试收集，存档和保存社区制作的Game Boy（Color）的每个非官方游戏，自制程序，演示，补丁，hackrom通过多年的激情工作.
- [Infinity](https://github.com/infinity-gbc/infinity)   - 由Affinix Software开发的RPG主要在1999年至2001年之间.游戏从未找到过出版商，最终被取消.  最近发布了完整的源代码，开发工具和工作流程.

### ASM

- [Tuff](https://github.com/BonsaiDen/Tuff.gb)
- [2048-gb](https://github.com/Sanqui/2048-gb)
- [Snake](https://bitbucket.org/Sanqui/snake/src/?at=master)
- [PlantBoy](https://github.com/siObyte/PlantBoy)
- [Lazerpong](https://github.com/huderlem/lazerpong)
- [Geometrix](https://github.com/AntonioND/geometrix)
- [µCity](https://github.com/AntonioND/ucity)
- [Carazu](https://github.com/mholtkamp/carazu)
- [Snake-gb](https://github.com/DonaldHays/snake-gb)
- [GB303](https://github.com/furrtek/GB303) - 用于Nintendo Game Boy的GB303基于波表的TB-303型合成器.
- [Sushi](https://github.com/JustSid/Sushi)
- [Flappy-boy-asm](https://github.com/bitnenfer/flappy-boy-asm)
- [kupman](https://github.com/dubvulture/gbdev) 和其他一些项目
- [Adjustris](https://github.com/tbsp/Adjustris)
- [exeman](https://github.com/exezin/exeman/)
- [Aevilia](https://github.com/ISSOtm/Aevilia-GB)
- [GBSlides](https://github.com/Kartones/gameboy) - 一个简单的Game Boy Powerpoint-like幻灯片查看器.
- [Pokered-gbc](https://github.com/dannye/pokered-gbc) - 神奇宝贝红色重拍，完全支持GBC.
- [ToyToy](https://github.com/tslanina/Retro-GameBoyColor-ToyToy)
- [StefaN](https://github.com/tslanina/Retro-GameBoyColor-StefaN) -  Fourway Breakout克隆.
- [Galaxia](https://github.com/tslanina/Retro-GameBoyColor-Galaxia)
- [desgb](https://github.com/sanqui/desgb) - 加密.
- [superhappyfunbubbletime](https://github.com/l0k1/superhappyfunbubbletime)
- [minesweepGB](https://github.com/lancekindle/minesweepGB)
- [Libbet and the Magic Floor](https://github.com/pinobatch/libbet)
- [waveform-gb](https://github.com/dannye/waveform-gb) - Program visualizing the wave form used by the wave channel. The wave form can be edited freely and playback of the wave is updated immediately.

### C

- [FlappyBoy](https://github.com/bitnenfer/FlappyBoy)
- [flappybird-gameboy](https://github.com/pashutk/flappybird-gameboy)
- [fbgb](https://github.com/gb-archive/fbgb)
- [Novascape](http://ludumdare.com/compo/ludum-dare-34/?action=preview&uid=6823)
- [Squishy the Turtle](https://github.com/cppchriscpp/SquishyTheTurtle)
- [Quadratino](https://github.com/avivace/quadratino)
- [Doctor How](https://github.com/elfgames/doctorhow)
- [Super Princess' 2092 Exodus](https://github.com/Zal0/gbjam2016)
- [GBsnake](https://github.com/brovador/GBsnake)
- [gb-mines](https://github.com/andreasjhkarlsson/gb-mines)
- [oranges](http://www.atari2600land.com/gameboy/oranges.html)
- [red hot princess carnage](https://github.com/Imanolea/bitbitjam3_red_hot_princess_carnage)
- [loderunner](http://www.tensi.eu/thomas/programming/gameboy/loderunner.html)
- [Hives](https://refreshgames.co.uk/2017/04/24/ludum-dare-38-entry-hives/)
- [Bubble Factory](https://github.com/DonaldHays/bubblefactory) -  *香草* SDCC（没有gbdk）.
- [GBC Atari Boxing](https://github.com/rubfi/gbc-atari-boxing) -  Atari 2600拳击克隆游戏男孩（颜色）.
- [GB raycaster, Vision-8](https://github.com/haroldo-ok/really-old-stuff/tree/master/gameboy) 和其他一些项目
- [Tobu Tobu Girl](https://github.com/SimonLarsen/tobutobugirl) -  Game Boy的街机平台游戏.
- [Burly Bear vs. The Mean Foxes](http://sebastianmihai.com/main.php?t=18&) ([GBC](http://sebastianmihai.com/main.php?t=55&n=Gameboy-Color-development-Burly-Bear-vs-The-Mean-Foxes-GBC-version) 港口）
- [PostBot](https://github.com/MasterIV/PostBot)
- [Guns & Riders](https://github.com/kanfor/gunsridersgameboy)
- [Dino's Offline Adventure](https://github.com/gingemonster/DinosOfflineAdventure) -  Google Chrome离线游戏的克隆版
- [dino-gb](https://github.com/rnegron/dino-gb) -  Chrome游戏的另一个克隆版本

### Demos

- [Back to Color](https://github.com/AntonioND/back-to-color)
- [beach-gbc](https://github.com/vegard/beach-gbc)
- [CUTE DEMO](https://github.com/mills32/CUTE_DEMO)
- [`10 PRINT` Game Boy](https://github.com/svendahlstrand/10-print-game-boy)
- [Roboto Demo](https://github.com/naavis/roboto-demo)
- [matrix-rain-gb](https://github.com/wtjones/matrix-rain-gb) - 汇编程序中的Matrix数字雨效应.
- [GBVideoPlayer](https://github.com/LIJI32/GBVideoPlayer) - 一个技术演示，展示Game Boy LCD控制器如何被黑客攻击，以使Game Boy Color与音乐一起播放全动态视频.
- [GBVideoPlayer2](https://github.com/LIJI32/GBVideoPlayer2) - 上述演示的第二次迭代，增加了分辨率，增加了* stereo * PCM音频，并引入了视频压缩.

## Reverse Engineering

- [Reverse engineering Kirby's Dreamland 2](http://ecc-comp.blogspot.it/2016/03/reverse-engineering-kirbys-dreamland-2.html)
- [pokemontools](https://github.com/pret/pokemon-reverse-engineering-tools) - 一个python模块，为各种神奇宝贝游戏提供各种逆向工程组件.
- [Reverse Engineering a Gameboy ROM with radare2](https://www.megabeets.net/reverse-engineering-a-gameboy-rom-with-radare2) - 使用radare2对Game Boy ROM挑战进行逆向工程的演练.
- [Disassembling Link's Awakening](http://kemenaran.winosx.com/posts/category-disassembling-links-awakening/) - 关于拆解Link的Awakening DX的一系列博客文章.
- [Reverse Engineering the GameBoy Tetris](https://github.com/h3nnn4n/Reverse-Engineering-the-GameBoy-Tetris)
- [DMA hijacking](https://github.com/avivace/awesome-gbdev/blob/master/articles/dma_hijacking.md) - 一种简单的技术，允许您在大多数GB / SGB / CGB游戏中运行自定义代码，前提是您拥有ACE漏洞.

### Game Disassemblies

- [Pokémon Red/Blue](https://github.com/pret/pokered)
- [Pokémon Crystal](https://github.com/pret/pokecrystal)
- [Pokémon Yellow](https://github.com/pret/pokeyellow)
- [Pokémon Gold and Silver](https://github.com/pret/pokegold)
- [Pokémon Pinball](https://github.com/pret/pokepinball)
- [Pokémon TCG](https://github.com/pret/poketcg)
- [pokegold-spaceworld](https://github.com/pret/pokegold-spaceworld) - 神奇宝贝金银1997空间世界演示.
- [Link's Awakening DX](https://github.com/mojobojo/LADX-Disassembly)
- [Oracle of Ages](https://github.com/drenn1/ages-disasm)
- [Tetris](https://github.com/osnr/tetris) - 基于Jeff Frohwein的原始拆卸.
- [FX Hammer](https://github.com/DevEd2/FXHammer-Disasm)
- [Harvest Moon 3](https://github.com/sanqui/hm3)
- [RedPlusPlus](https://github.com/TheFakeMateo/RedPlusPlus)   - 升级为神奇宝贝红.  修复了几个错误并添加了许多新功能.

## Related projects

- [ArduinoBoy](https://github.com/trash80/Arduinoboy) - 从Arduino到Game Boy的串行通信（MIDI），用于LittleSoundDJ，Nanoloop和mGB等音乐应用.
- [papiGB](https://github.com/diegovalverde/papiGB) -  Game Boy Classic全功能FPGA实现从头开始.
- [fpgaboy](https://github.com/trun/fpgaboy) - 在FPGA上实现任天堂的Game Boy控制台.
- [Piglet](https://github.com/danShumway/Piglet)   -  LUA驱动的AI，使用实验播放经典的Game Boy彩色游戏.  积极发展.
- [Gatesboy](https://web.archive.org/web/*/http://www.gatesboy.com/) - 非游戏目的应用程序开发.
- [Ostrich](https://github.com/PumpMagic/ostrich) - 用Swift编写的Game Boy Sound System播放器.
- [mGB](https://github.com/trash80/mGB) -  Game Boy墨盒程序，使Game Boy可以充当MIDI支持的完整声音模块.
- [GBVisualizer](https://github.com/LIJI32/GBVisualizer) - 演示使用两个未记载的Game Boy Color寄存器，昵称为PCM12（FF76）和PCM34（FF77），可用于读取4个APU通道的当前PCM幅度.
- [ArduinoGameBoy](https://github.com/drhelius/arduinogameboy) - 基于Arduino的Game Boy墨盒读写器.
- [gameboy-brainfuck](https://github.com/bitnenfer/gameboy-brainfuck) -  Brainf * ck翻译.
- [gbfk](https://github.com/elseyf/gbfk) -  Brainf * ck解释器，带输入.
- [gb-save-states](https://github.com/mattcurrie/gb-save-states) - 在原始硬件上播放时，为Game Boy游戏添加保存状态支持的补丁.
- [gbcpu](https://github.com/jdeblese/gbcpu) - 实现Game Boy指令集和功能的CPU和外围设备.
- [Digitized Speech in Game Boy Games](https://youtube.com/watch?v=1lzHfLYzyRM)
- [Sniffing Game Boy serial traffic with an STM32F4](https://dhole.github.io/post/gameboy_serial_1/)
- [Virtual Game Boy Printer with an STM32F4](https://dhole.github.io/post/gameboy_serial_2/)
- [Printing on the Game Boy Printer using an STM32F4](https://dhole.github.io/post/gameboy_serial_3/)
- [Pokemon Pocket Computer:](https://tilde.town/~minerobber/techwriteups/pokemonpc.html) - 它是什么以及如何使用它来制作作弊码.
- [Booting the Game Boy with a custom logo](https://dhole.github.io/post/gameboy_custom_logo/) - 绕过任天堂徽标检查.
  - 在2017年制作一款Game Boy游戏：“绵羊吧！”  死后（[part 1](https://www.gamasutra.com/blogs/DoctorLudos/20171207/311143/), [part 2](https://www.gamasutra.com/blogs/DoctorLudos/20180213/314554/))
- [Nintendo's fake logos](http://fuji.drillspirits.net/?post=87) - 每个墨盒必须显示真实的徽标才能被认为有效并且可以运行，但显然有些公司设法利用了检查系统.
- [liblsdj](https://github.com/stijnfrishert/liblsdj) - 用于与LSDj保存格式（.sav），歌曲文件（.lsdsng）等进行交互的实用程序库.
- [lsdpatch](https://github.com/jkotlinski/lsdpatch) - 用于修改LSDj ROM映像上的样本，字体和调色板的工具.
- [Game Boy video effects](https://github.com/ChaosCabbage/crazy-gameboy-video-experiments) - 使用STAT中断做一些有趣的视频操作的一些小实验.
- [gbos](https://github.com/ekimekim/gbos) -  Game Boy的基本操作系统.


### Directories

- [Archive of related files](http://gbdev.gg8.se/files/)
- [The Game Boy Archive](https://github.com/gb-archive)   -  Game Boy相关软件，硬件和文献库.  旨在反映和保存过去三十年来陈旧和分散的贡献.
- [The Game Boy Archive - Salvage](https://github.com/gb-archive/salvage) - 软件，旧文章，常见问题解答和各种文件的历史档案.

### Websites

- [GBDK Developers](http://gbdk-developers.com/)   - 关于与场景相关的所有内容的活跃博客.  包括功能，见解和访谈.
- [pdroms.de](http://pdroms.de/news/gameboy/) Game Boy发布.
- [Game Boy Demospotting](http://gameboy.modermodemet.se/en) - 一系列演示.
- [Handheld Underground](http://hhug.me) - 未经许可的游戏，关于Game Boy的博客帖子，hhugboy模拟器的主页.


## About

### Contribute

看一眼 [Contribution Guidelines](CONTRIBUTING.md).

### License

根据** GPLv3 **许可.
See [LICENSE](LICENSE) 欲获得更多信息.

### Acknowledgements

谢谢 [every](https://github.com/avivace/awesome-gbdev/graphs/contributors) 这个项目的贡献者，Jeff Frohwein，Pascal Felber，KOOPa，Pan of Anthrox，GABY，Marat Fayzullin，Paul Robson，BOWSER，neviksti，Martin“nocash”Korth，Nitro2k01，Duo，Chris Antonellis，Michael Hope，当心，Jonathan“Lord梦魇“Gevaryahu，Carsten Sorense，SindreAamås，Otaku No Zoku，GeeBee.

### Sponsors

特别感谢我们的朋友们 [DigitalOcean](https://www.digitalocean.com/)，赞助我们的Game Boy Development社区的开源活动（[announcement](https://twitter.com/avivace4/status/992188011990409216)).
