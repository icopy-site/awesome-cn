<div class="github-widget" data-repo="balintkissdev/awesome-dos"></div>
## Awesome DOS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

用于基于 x86 的个人计算机的操作系统，在 1980 年代和 90 年代初期流行.

[<img src="https://raw.githubusercontent.com/balintkissdev/awesome-dos/master/logo.svg?sanitize=true" align="right" width="100">](https://github.com/balintkissdev/awesome-dos)

用于开发 DOS 应用程序和了解系统本身的精选参考列表. 这包括
编译器列表、教程、视频、免费和付费书籍的链接以及 DOS 游戏的源代码. 这个列表的目标
是收集信息并作为想要开始为 DOS 进行逆向编程的人的起点
platform.



## Development tools

- [bcc - Bruce's Compiler](https://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/bcc.html) - Bruce 的 C 编译器是一个简单的 C 编译器，可为微型/小型内存模型生成 8086 汇编器.
- [DJGPP](http://www.delorie.com/djgpp/) - DJ Delorie 针对 Intel 80386 的完整 32 位 C/C++ 开发环境.用于 Quake.
- [Open Watcom](https://web.archive.org/web/20220627162043/http://www.openwatcom.org/) - 以前用于 16 位和 32 位 DOS 的商业 C/C++ 开发环境和
  视窗. 目前正式版为1.9.  GitHub 分支也可用. 用于 Doom I-II、Warcraft I-II、Duke Nukem 3D、Full Throttle、Dark Forces 和 Retro City Rampage.
  - 这 [documentation](https://web.archive.org/web/20220630162351/http://www.openwatcom.org/doc.php) 对于理解使用 1.9 版和 V2 分支来说非常有价值.
  - [Arch Wiki page](https://wiki.archlinux.org/index.php/Open_Watcom)
- [Open Watcom V2](https://github.com/open-watcom/open-watcom-v2) - 积极维护的 GitHub 分支
  移植到 64 位 Windows 和 Linux.
- [Turbo C 2.01](http://www.doshaven.eu/wp-content/uploads/2014/08/tc201.zip) - Borland 的 C IDE 和编译器于 1987 年首次发布.
- [Turbo C++ 1.01](http://www.doshaven.eu/wp-content/uploads/2014/08/tcpp101.zip) - Borland 于 1991 年发布的 C++ IDE 和编译器.
- [DIV Games Studio 2](https://archive.org/details/div2_iso)  - 用于开发 2d、模式 7 和 3d 的 DOS 游戏的 IDE.  1998 年上映.
  - [Online version.](http://js.mikedx.co.uk/DIV1.html)
- [T3X](https://t3x.org/t3x/#t3x7) - Nils M. Holm 的一种小型、可移植、过程化、块结构、递归、几乎无类型且在某种程度上面向对象的编程语言.
- [SmallerC](https://github.com/alexfru/SmallerC.git) - 能够为多种平台生成可执行文件的便携式自托管 C 编译器，包括实模式和保护模式 DOS 程序，由 Alexei A. Frounze 编写.

### Memory managers

- [386MAX](https://github.com/sudleyplace/386MAX) - 具有 386 或更高 CPU 的 DOS PC 的内存管理器， [released by Qualitas company in 1992](https://winworldpc.com/product/386max/6x) . 源代码于 2022 年 6 月在 GitHub 上以 GPL-3.0 许可发布.

### Scripting languages and interpreters for DOS

- [DOjS](https://github.com/SuperIlu/DOjS) - 适用于 MS-DOS、FreeDOS 或任何基于 DOS 的 Windows（如 95、98、ME）的 JavaScript 编程环境.
- [Lua for DOS](https://archive.org/details/lua5.3.5) - Lua 5.3.5 的在线演示，在 Intel 80486 处理器上为 MS-DOS 编译.
- [Micropython for FreeDOS](https://github.com/pohmelie/micropython-freedos) - FreeDOS ad-hoc 模块 [micropython](https://github.com/micropython/micropython).
- [perldos](https://perldoc.perl.org/perldos) - 适用于 DOS 的 Perl.
- [PythonD](http://www.caddit.net/pythond/) - 适用于 DOS 的 Python，包括多线程、网络和 OpenGL.

## Tutorials and programming resources

### History

- [The Life of MS-DOS by Brendan Byers](https://b13rg.github.io/Life-of-MS-DOS/)  - DOS 家族的历史，包括 CP/M、Q-DOS/86-DOS、MS-DOS 和 PC-DOS. 文章还包括 DOS 的时间线和家谱图
  操作系统.

### Compiling

- [80x86 16-bit Compiling How-to by Alexei A. Frounze](http://alexfru.narod.ru/os/c16/c16.html)  - Borland/Turbo C/C++ 和 Open Watcom 的 16 位编译教程. 进入内存寻址和内存模型的深度.
- [32bit DOS development with Open Watcom](http://tuttlem.github.io/2015/10/04/32bit-dos-development-with-open-watcom.html) - Open Watcom 的 32 位编译教程.
- [How to build DOS COM files with GCC by Chris Wellons](https://nullprogram.com/blog/2014/12/09/)  - 使用 DJGPP 构建 Chris Wellons 的 DOS Defender 游戏的过程. 目标是创建一个 32 位 80386 COM 可执行文件.

### General

- [David Brackeen - 256-Color VGA Programming in C](http://www.brackeen.com/vga/) - 学习如何在 DOS 上创建图形的教程系列.
- [640k Really is Enough for Anyone by Robert W. Oliver II](https://blog.sourcerer.io/640k-really-is-enough-for-anyone-314f393ca5b8) - 关于让 Turbo C 在 FreeDOS 上运行并四处移动像素的短文.
<!--lint disable no-repeat-punctuation-->
- [Just keeping it real... old skool style - Scali's OpenBlog](https://scalibq.wordpress.com/2011/11/23/just-keeping-it-real-old-skool-style/) - 关于 Scali 进行 CGA、EGA 和 VGA 编程的博客文章.
<!--lint enable no-repeat-punctuation-->
- [Alex Russell's Dos Game Programming in C for Beginners](https://web.archive.org/web/20201112023702/http://www3.telus.net/alexander_russell/course/introduction.htm)  - DOS 游戏编程教程系列，包括 C 语言入门、图形、动画、输入处理和碰撞检测. 本系列包含制作教程 [buffered input handling](https://web.archive.org/web/20200203195410/http://www3.telus.net/alexander_russell/course/chapter_4.htm) . 最后一章包含 DOS 上 Break Out 游戏的完整源代码.
- [The Artevida Game Programming Tutorials](http://web.archive.org/web/20201031021650/http://atrevida.comprenica.com/)  - Kevin Matz 对使用 C/C++ 和 80x86 汇编的 DOS 系统编程和 VGA 编程基础的几乎整本书的处理. 不幸的是，它并不完整，自 2001 年以来就被废弃了.
- [PC Game Programmer's Encyclopedia](https://web.archive.org/web/20201111164240/http://bespin.org/~qz/pc-gpe/) - 指南集合，涵盖装配、声音（Sound Blaster、Gravis UltraSound、PC 扬声器、GameBlaster、Adlib）、输入、内存（EMS、XMS、DMA 传输）、PIT、VGA、SVGA、算法和文件格式.
- [The Art of Demomaking by flipcode](http://web.archive.org/web/20190123060222/http://www.flipcode.com/archives/The_Art_of_Demomaking-Issue_02_Introduction_To_Computer_Graphics.shtml)  - 1999 年的系列，介绍 DOS 下的图形编程. 主页还包含其他 90 年代末/2000 年代初的游戏编程文章.
- [Programming MS-DOS with Power - DOS Programming, Undocumented DOS, and DOS Secrets](http://web.archive.org/web/20200626182822/http://www.fysnet.net/) - 系统编程教程，如磁盘处理、中断、输入、声音、图形.
- [Programmer's Heaven (InfoMagic)(March 1997) CD-ROM](http://discmaster.textfiles.com/view/4555/Programmer%27s%20Heaven%20%28InfoMagic%29%28March%201997%29.BIN%2Fmain.htm) - 以下主题的源代码和文件：MS-DOS、网络、C、C++、Pascal、Visual Basic、Delphi、3D、PC 扬声器、Soundblaster、Gravis Ultrasound、MIDI 等等.

### DOS API

- [bios.h header documentation by Digital Mars](https://digitalmars.com/rtl/bios.html) - 直接访问 BIOS 操作（磁盘操作、BIOS 键盘、打印机、时间、内存、串行、中断）的例程的 API 文档.
- Digital Mars 的 dos.h 头文档 [Part 1](https://digitalmars.com/rtl/dos.html) [Part 2](https://digitalmars.com/rtl/dos2.html) - 与 DOS 操作系统本身接口的函数的 API 文档.

### Interrupts

- [Ralph Brown's Interrupt List - HTML version](https://web.archive.org/web/20201111162212/http://www.ctyme.com/rbrown.htm) - 已知的每个记录和未记录的中断调用的列表，可通过搜索、类别和中断编号访问.
  - 原始的可下载 .zip 文件来自 [Ralph Brown's website](https://web.archive.org/web/20201108093425/http://www.cs.cmu.edu/~ralf/files.html)

### Video

- [Values for standard video mode](https://web.archive.org/web/20200214123701/http://www.columbia.edu/~em36/wpdos/videomodes.txt) - 所有已知视频模式的列表，包括 BIOS 中断号、文本/像素分辨率、颜色数和视频内存地址.

#### CGA

- [Color Graphics Adapter: Notes](https://web.archive.org/web/20201112020351/https://www.seasip.info/VintagePC/cga.html) - 描述 IBM 原始 CGA 的硬件、内存映射、寄存器 I/O 和硬件克隆的文档.

#### VGA

- [VGA Hardware - OSDev wiki](https://wiki.osdev.org/VGA_Hardware) - VGA 卡的硬件指南，也适用于包括 NVidia 和 ATI 在内的现代显卡.
- [Graphical programming in Assembly (DOS)](http://web.archive.org/web/20201112040702/http://www.wagemakers.be/english/doc/vga) - VGA 编程教程，还在开头的表格中显示视频模式列表（文本、CGA、EGA、VGA、SVGA）.

#### SVGA

- [DOS Super VGA / VESA programming notes - by Myles](https://web.archive.org/web/20200724153658/http://www.faqs.org/faqs/pc-hardware-faq/supervga-programming/) - VESA 文章开头有历史，并简短提及 VESA VBE 标准，但不幸的是，示例代码甚至无法通过 Wayback Machine 获得.
- [VESA Video Modes - OSDev wiki](https://wiki.osdev.org/Getting_VBE_Mode_Info) - 关于查询 VESA 模式的教程.
- [DJGPP VESA guide](http://www.delorie.com/djgpp/doc/ug/graphics/vesa.html.en) - 关于查询 VESA 模式的教程.
- [High-res high-speed VESA tutorial](https://web.archive.org/web/20200128180543/http://www.monstersoft.com/tutorial1/) - 系列教程，包括在 VESA 模式下绘制像素（受保护或真实）.
- [C code sample for drawing in VESA 2.0 mode](https://web.archive.org/web/20200121065447/http://www.codenet.ru/progr/video/vesa20ex.php) - 只是在 VESA 模式下绘制椭圆的代码清单.

### Sound

- [Programming Sound Cards CD](http://discmaster.textfiles.com/browse/63/Programming%20Sound%20Cards.iso)  - 一张 1995 CD-ROM，包含 Adlib、Gravis、Pro-Audio、Roland 和 Sound Blaster 声卡的源代码. 列出了 CD-ROM 上文件夹的说明 [on the back of the CD-ROM case.](https://archive.org/details/programming-sound-cards/Programming%20Sound%20Cards_back.jpg)

#### PC Speaker

- [Making some noise with the PC speaker! - by Mark Feldman](https://web.archive.org/web/20150302161648/http://heim.ifi.uio.no/~inf3150/grupper/1/pcspeaker.html) - 关于使用 PIT 生成 PC 扬声器频率的非常简短的教程.
- [Frequencies of Musical Notes](https://web.archive.org/web/20201129091353/https://pages.mtu.edu/~suits/notefreqs.html) - 可用于参数化 PC 扬声器的频率表.
- [Sound Programming with PC Speaker - Chapter 23 of A to Z of C](https://web.archive.org/web/20171115162742/http://guideme.itgo.com/atozofc/ch23.pdf) - 带有源代码的“A to Z of C”一书的 PC 扬声器编程章节.

#### AdLib/OPL2

- [Yamaha YM3812 (OPL2) sound chip Wikipedia article](https://en.wikipedia.org/wiki/Yamaha_YM3812) - Best starting point to learn about the OPL2 sound chip besides 8-bit guy's YouTube video.
- [The Ad Lib Music Synthesizer Card Programming Guide - by Tero Töttö](https://web.archive.org/web/20200427145810/http://www.vgmpf.com/Wiki/images/4/48/AdLib_-_Programming_Guide.pdf) - OPL2 操作和寄存器的参考.

#### Sound Blaster/OPL3

- [Programmer's Guide to the Yamaha YMF 262/OPL3 FM Music Synthesizer](https://web.archive.org/web/20200509082459/http://www.fit.vutbr.cz/~arnost/opl/opl3.html) - OPL3 上的逆向工程参考.
- [Sound Blaster 16 Programming Document 3.5 by Ethan Brodsky](https://web.archive.org/web/20201130110457/http://homepages.cae.wisc.edu/~brodskye/sb16doc/sb16doc.html) - 对 Sound Blaster 16 DSP CT1341 芯片进行编程，以录制和播放数字化音频.
  - 版本 3.4 [GameDev.net archive](https://web.archive.org/web/20180507161514/http://archive.gamedev.net/archive/reference/articles/article444.html)
- [Soundblaster Programming Information v0.90](https://web.archive.org/web/20191020222313/http://www.intel-assembler.it/portale/5/soundblaster-programming-information/sb-reference-for-programming-sound.asp) - Sound Blaster 型号和寄存器列表.

### Other

- [Table of DOSBox cyclecounts according to processor types](https://web.archive.org/web/20201112012244/https://www.alternatewars.com/Games/DOSBox/DOSBox.htm)  - 根据 CPU 类型（IBM XT 88、286、386、486、奔腾 I、奔腾 II）设置适当的 DOSBox 循环计数的表格. 当您正在开发 DOS 游戏并想要模拟您打算执行它的环境时，它会派上用场.

## Books

### Free

- [Game Engine Black Book: Wolfenstein 3D - by Fabien Sanglard](https://fabiensanglard.net/b/gebbwolf3d.pdf)  - Fabien Sanglard 在 IBM PC 硬件上演练 id Software 的 Wolfenstein 3D 游戏引擎架构. 包含 John Carcmack、Tom Hall 和 John Romero 的前言.
- [Game Engine Black Book: Doom - by Fabien Sanglard](https://fabiensanglard.net/b/gebbdoom.pdf)  - Fabien Sanglard 在英特尔 486 系统和游戏控制台端口上演练了 id Software 的原始 Doom 的游戏引擎架构. 包含 John Carcmack、Dave Taylor 和 John Romero 的前言.
- [A to Z of C - a book on C/DOS programming by K. Joseph Wesley and R. Rajesh Jeba Anbiah](https://web.archive.org/web/20201109033646/http://guideme.itgo.com/atozofc/)  - 关于在 DOS 上使用 C 语言编程的非营利书籍.  DOS系统编程从第二部分开始.
- [Michael Abrash's Graphics Programming Black Book Special Edition](https://web.archive.org/web/20201112020812/http://www.phatcode.net/res/224/files/html/index.html) - Michael Abrash 的 Dr. Dobb&#39;s Journal 图形编程文章和他在 Quake 图形子系统方面的工作的集合.

### Paid

- [Tricks of the Game-Programming Gurus - by Andre Lamothe, John Ratcliff and Denise Tyler](https://www.amazon.com/Tricks-Game-Programming-Gurus-Andre-Lamothe/dp/0672305070/) - 关于入门、创建 2D 和基本 3D 图形、I/O 和游戏算法的综合 DOS 游戏开发书籍.

## Videos

- [Why DOS Was (and Is) a Thing - FreeDOS](https://www.youtube.com/watch?v=3E5Hog5OnIM) - 历史谈话从 Unix 开始，经过 CPM、DOS 1.x、DOS 2.x、DOS 3.x、DOS 4.x、DOS 6.x、Windows 3.1、Windows 95 并以 FreeDOS 结束.
- [CGA Graphics - Not as bad as you thought! - by 8-bit Guy](https://www.youtube.com/watch?v=niKblgZupOc)  - 有关 IBM CGA 系统的历史和技术细节. 还描述了 4 色 RGBI 和 16 色复合模式.
- [How Oldschool Sound/Music worked - by 8-bit Guy](https://www.youtube.com/watch?v=q_3d1x2VPxk) - 有关 PC 扬声器、NES 和 Commodore 64 中的 FM 合成器、AdLib 和 Sound Blaster 声卡中的 Yamaha OPL 芯片、PCM 样本和 MOD 音乐的视频.
- [Let's Code - MS DOS - by root42](https://www.youtube.com/playlist?list=PLGJnX2KGgaw2L7Uv5NThlL48G9y4rJx1X) - DOS 编程教程系列，包括 VGA、SoundBlaster 和 VGA Mode X.
- [LGR - Evolution of PC Audio - As Told by Secret of Monkey Island](https://www.youtube.com/watch?v=a324ykKV-7Y) - 通过 PC 扬声器、IBM PCjr/Tandy、AdLib、Game Blaster、Roland LAPC-1/MT-32、Gravis Ultrasound、Roland SCC-1 MIDI、SB16 Waveblaster/AWE32 和 CD 播放《猴岛的秘密》前奏曲的比较优质的数字音频.
- [Porting Retro City Rampage to MS-DOS: From PS4 to 1.44MB Floppy](https://www.youtube.com/watch?v=kSKeWH4TY9Y)  - GDC 谈话.  Brian Provinciano 关于将 Retro City Rampage 从 PlayStation 4 移植到 DOS 的演讲. 主题包括优化、使用中断、定时、PC 扬声器声音、操纵杆、内存管理和定点数学.
- [DOS Executables Explained - Nostalgia Nerd](https://www.youtube.com/watch?v=6j947U4xl5I) - 有关 DOS 可执行文件格式的视频，包括 .COM、.BAT 和 .EXE.
- [Why does DOS use 8.3 Filenames? - Nostalgia Nerd](https://www.youtube.com/watch?v=eGIyCD2_qA8) - 有关 DOS、FAT 分区方案、NTFS、VFAT、FatGo 和 `LFN.EXE` 下文件名 8.3 限制的视频.
- [What is DOS Protected Mode? / DOS Extenders- Nostalgia Nerd](https://www.youtube.com/watch?v=XAyQLV5bbb0) - 有关 PC 内存的外观、常规内存、扩展内存以及需要 DOS 保护模式接口 (DPMI) 和 DOS/4GW 等扩展程序的原因的视频.

## Open source DOS libraries

- [Allegro 4.2](https://www.allegro.cc/files/?v=4.2) - 适用于 DOS、Windows 和 Linux 的游戏开发库.
- [LoveDOS](https://github.com/rxi/lovedos)  - 在 Lua 中制作 2D DOS 游戏的框架.  API 基于 LÖVE API 的一个子集.
- [DOS-VGA-Game](https://github.com/marcomarrero/DOS-VGA-Game) - Marco A. Marrero 在汇编和 Turbo Pascal 中实现的 DOS VGA/硬件库.
- [DIGPAK sound drivers source code](https://github.com/jratcliff63367/digpak) - 由 John W. Ratcliff 上传到 GitHub 的 DIGPAK 声音驱动程序的原始源代码.

## Open source DOS games

### Homebrew games with source code

所有自制 DOS 游戏列表：http://www.doshaven.eu

- [DOS Defender](https://github.com/skeeto/dosdefender-ld31) - Christopher Wellons's x86 real mode DOS Asteroids clone created as an entry for Lundum Dare #31.
- [Dungeons of Noudar](https://github.com/TheFakeMontyOnTheRun/dungeons-of-noudar)  - 保护模式下的第一人称 2.5D 地牢探索者. 用 C++ 编写，包括软件渲染、定点数学、测试范围和声音（PC 扬声器、Adlib、OPL2LPT）.
- [Emeritus Pong](https://sourceforge.net/projects/empong/)  - 适用于 DOS、Windows 和 Linux 的 Pong 克隆. 在 DOS 上使用 PC 扬声器播放声音.
- [Floppy Bird](https://github.com/icebreaker/floppybird)  - 用 16 位汇编编写的 Flappy Bird 克隆. 不是 DOS 程序，而是 PC-Booter 应用程序（尽管也可以为 DOS 构建 COM 可执行文件）.
- [George M. Tzoumas's collection of MS-DOS games and utilities](http://web.archive.org/web/20191225101138/http://cgi.di.uoa.gr/~geotz/dos/)  - Turbo Pascal，带有少量 C 和 C++ 游戏. 游戏包括 Nibbles、Connect Four、Ms Pacman clone 和两款街机/平台游戏. 其中之一 (ra2) 是使用 Allegro 编写的. 实用程序全部用 Turbo Pascal 编写，包括游戏系统例程、文件和磁盘实用程序以及终止和驻留程序 (TSR).
- [Gridfighter 3D](https://porta2note.itch.io/gridfighter-3d)  - 用 Quickbasic 编写的 80 年代风格街机射击游戏. 也是已知的第一个支持 Oculus Rift VR 耳机的 DOS 游戏.
  - [GitHub repository](https://github.com/porta2note/gridfighter3d)
- [Hangman](https://sourceforge.net/projects/hangman-dos/)  - 用 Basic 编写的 Hangman 克隆. 在至少 80286 处理器上运行并使用 EGA 图形.
- [Magenta's Maze](https://archive.org/details/MAGSMAZE) - 以代数为题材的CGA图形3D迷宫游戏.
  - [Source code download link](http://www.doshaven.eu/downloads/537)
- [NetHack](https://github.com/NetHack/NetHack) - 原始人的后代 [NetHack](https://en.wikipedia.org/wiki/NetHack) rougelike 游戏于 1987 年首次发布，可在多个平台上使用.
- [Piskworks](https://github.com/berk76/piskworks) - 用 C 编写的 Gomoku 克隆.适用于 DOS、ZX Spectrum、ZX81、ZX80、APPLE1、AS400 和 Windows.
- [Plutonium Caverns](https://github.com/jani-nykanen/plutonium-caverns) - 用C编写的架空益智游戏.网页版使用 [DOSBox ported to Emscripten](https://github.com/dreamlayers/em-dosbox) 将 DOSBox 嵌入到 HTML5 中. 但是，原始可执行文件也可以使用 Open Watcom 下载和构建.
- [Ptakovina](https://github.com/berk76/tetris) - 用 C 语言编写的俄罗斯方块克隆版.可在 DOS、Unix/Linux、ZX Spectrum 和 Windows 上运行.
- [sudoku86](https://sourceforge.net/projects/sudoku86/) - 用 C 编写的数独克隆.在 8086/8088 CPU 上运行，使用 CGA、MCGA 或 VGA 图形并使用鼠标.
- [Tetris](http://www.doshaven.eu/game/tetris/) - 用汇编编写的俄罗斯方块克隆.
  - [Source code download link](http://www.doshaven.eu/downloads/373)
- [Towers of Hanoi](https://github.com/sblendorio/hanoi-dos) - [Tower of Hanoi](https://en.wikipedia.org/wiki/Tower_of_Hanoi) 用 Turbo Pascal 编写的益智游戏. 最初于 1996 年发布.
- [x86 pong](https://github.com/spacerace/x86-pong) - 用 C 编写的文本模式 Pong 克隆.在 DOS 下作为 PC-Booter 游戏运行.
- [zmiy](https://sourceforge.net/projects/zmiy/) - 用 C 编写的文本模式 Snake 克隆.在 8086 DOS 上运行.

### Freeware games with source code

- [Cyberdogs](https://web.archive.org/web/20190222022411/https://www.classicdosgames.com/game/Cyberdogs.html)  - 自上而下的 2D 射手扮演雇佣兵来赚钱. 用 Turbo Pascal 编写. 支持两种播放器模式.
  - [Source code download link](https://web.archive.org/web/20180120123425/https://www.classicdosgames.com/files/source/dogs_src.zip)
  - [C-Dogs](https://en.wikipedia.org/wiki/C-Dogs)  - 原版 Cyber​​dogs 的续集. 原作者 Ronny Wester 不再维护原 C-Dogs 的网站，但存在多个端口，包括 [cdogs-sdl](https://congusbongus.itch.io/cdogs-sdl).

### Commercial games with published source code

- [Abuse](https://web.archive.org/web/20190801083909/https://www.classicdosgames.com/game/Abuse.html)  - 科幻横向卷轴平台游戏. 被大多数人视为创新的邪教经典. 支持高达 1280x1024 分辨率的 SVGA 模式. 该架构以 C 语言编写，包括一个 Lisp 脚本引擎.
  - [Source code download link](https://web.archive.org/web/20160402141350/http://www.classicdosgames.com/files/source/abuse_pd.tgz)
- [Beneath a Steel Sky](https://web.archive.org/web/20200721064209/https://www.classicdosgames.com/game/Beneath_a_Steel_Sky.html)  - 设置在反乌托邦未来的点击式冒险游戏. 写在汇编中.
  - [Source code download link](https://web.archive.org/web/20200721083621/https://www.classicdosgames.com/files/source/sky-source.zip)
- [Catacomb](https://github.com/CatacombGames/Catacomb)  - 由 Softdisk（后来成为 id Software）开发的 2D 俯视射击游戏. 支持 EGA 和 CGA 图形. 用 Turbo Pascal 和汇编语言编写.
- [Catacomb 3D](https://github.com/CatacombGames/Catacomb3D)  - 由 Softdisk（后来成为 id Software）开发的第一人称射击游戏. 具有采用光线投射技术的伪 3D 图形. 支持 EGA 图形. 用 C 语言和汇编语言编写. 用 Borland C++ 3.1 编译.
- [Commander Keen in Keen Dreams](https://github.com/keendreams/keen)  - id Software 开发的横向卷轴平台游戏.  Keen Dreams 是在 Keen 3 和 Keen 4（通常被认为是“Keen 3.5”）之间创建的指挥官 Keen 游戏，但并未广泛发布. 用 C 语言和汇编语言编写.
- [Descent](https://github.com/videogamepreservation/descent)  - 第一款具有完全真实 3D 图形的科幻 FPS/太空射击游戏. 用 C 语言和汇编语言编写.
- [Descent II](https://github.com/videogamepreservation/descent2)  - 后裔的续集. 用 C 语言和汇编语言编写.
- [Doom](https://github.com/id-Software/DOOM)  - 由 id Software 开发的科幻第一人称射击游戏，您可以在其中与来自火星地狱的恶魔作战. 由于依赖于获得许可的 DMX 声音库，因此无法发布 Doom 的特定于 DOS 的代码，因此它被清理并且只有 Linux 源代码在那里. 但是，Heretic 和 Hexen 项目包含原始 DOS 代码，其中删除了与 DMX 相关的代码.
- [Duke Nukem 3D](https://web.archive.org/web/20190304015745/https://www.classicdosgames.com/game/Duke_Nukem_3D.html)  - 由 Apogee 开发的第一人称射击游戏，主角是毁灭公爵. 用 C 语言编写.使用 Watcom C/C++ 10.0 编译.
  - [Source code download link](https://web.archive.org/web/20160403223736/http://www.classicdosgames.com/files/source/duke3dsource.zip)
- [Heretic](https://github.com/OpenSourcedGames/Heretic) - 在 id Software 的 Doom 引擎上运行的黑暗幻想 FPS.
- [Hexen: Beyond Heretic](https://github.com/OpenSourcedGames/Hexen) - Heretic 的间接续集.
  - 原来 [SourceForge link](https://sourceforge.net/projects/heretic/files/) for Heretic/Hexen.
- [Hovertank 3D](https://github.com/FlatRockSoft/Hovertank3D)  - 由 id Software 开发的 FPS. 在 Catacomb 3D 和 Wolfeinstein 3D 之前，采用光线投射技术的伪 3D 图形. 用 C 语言和汇编语言编写.
- [Quake](https://github.com/id-Software/Quake)  - 由 id Software 开发的 FPS 设置在全 3D 世界中. 用 C 编写.用 DJGPP 为 DOS 编译.
  - [Quake Engine Code Review series](https://fabiensanglard.net/quakeSource/index.php) - Fabien Sanglard 的代码分析.
- [Rise of the Triad: Dark War](https://github.com/videogamepreservation/rott)  - Apogee 开发的第一人称射击游戏. 它是作为 Wolfenstein 3D 的后续游戏开发的，但经过修改并成为一款独立游戏. 使用经过大量修改的 Wolfenstein 3D 引擎. 用C写的.
- [Sopwith](https://web.archive.org/web/20200131222432/http://davidlclark.com/page/sopwith) - 由 David L. Clark 于 1984 年创建的横向卷轴射击游戏.该游戏涉及驾驶 Sopwith 双翼飞机，试图轰炸敌方建筑物，同时避开敌机和各种其他障碍物的火​​力.
  - [MaiZure's Projects - Decoded: Sopwith](https://web.archive.org/web/20201211175311/https://www.maizure.org/projects/decoded-sopwith/) - MaiZure 的代码分析.
- [Wolfenstein 3D](https://github.com/id-Software/wolf3d)  - 由 id Software 开发的第一人称射击游戏，场景设置在纳粹德国监狱德军总部. 具有采用光线投射技术的伪 3D 图形. 用 C 语言和汇编语言编写.
