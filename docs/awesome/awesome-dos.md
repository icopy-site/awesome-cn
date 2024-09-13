<div class="github-widget" data-repo="balintkissdev/awesome-dos"></div>
## Awesome DOS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Family of operating systems for x86-based personal computers including IBM PC DOS and MS-DOS that were popular during the 1980s and early 1990s.

[<img src="https://raw.githubusercontent.com/balintkissdev/awesome-dos/master/logo.svg?sanitize=true" align="right" width="100">](https://github.com/balintkissdev/awesome-dos)

A curated list of references for development of DOS applications and learning
about the system itself. This includes list of compilers, tutorials, videos,
links to free and paid books and source code to DOS operating systems and DOS
games. The goal of this list is to collect information and act as a starting
point for someone who wants to start out retro-programming for the DOS
platform.



## Development tools

- [bcc - Bruce's Compiler](https://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/bcc.html) - Bruce's C compiler is a simple C compiler that produces 8086 assembler for tiny/small memory models.
- [DJGPP](http://www.delorie.com/djgpp/) - DJ Delorie's complete 32-bit C/C++ development environment for Intel 80386. Used for Quake.
- [GCC IA-16 toolchain](https://gitlab.com/tkchia/build-ia16/-/releases) - A 16-bit counterpart to DJGPP, a GCC-based toolchain for developing 16-bit (8086 to 80286, a.k.a. IA-16) DOS applications, currently maintained by TK Chia.
- [Open Watcom](https://web.archive.org/web/20220627162043/http://www.openwatcom.org/) - Formerly commercial C/C++ development environment for 16- and 32-bit DOS and
  Windows. The current official version is 1.9. A GitHub fork is also available. Used for Doom I-II, Warcraft I-II, Duke Nukem 3D, Full Throttle, Dark Forces and Retro City Rampage.
  - The [documentation](https://web.archive.org/web/20220630162351/http://www.openwatcom.org/doc.php) is very valuable in order to understand working with both version 1.9 and the V2 fork.
  - [Arch Wiki page](https://wiki.archlinux.org/index.php/Open_Watcom)
- [Open Watcom V2](https://github.com/open-watcom/open-watcom-v2) - GitHub fork which is actively maintained and is
  ported to 64-bit Windows and Linux.
- [Turbo C 2.01](http://www.doshaven.eu/wp-content/uploads/2014/08/tc201.zip) - C IDE and compiler from Borland first released in 1987.
- [Turbo C++ 1.01](http://www.doshaven.eu/wp-content/uploads/2014/08/tcpp101.zip) - C++ IDE and compiler from Borland released in 1991.
- [Turbo C++ 3.0](https://archive.org/details/tcc_20210425) - C++ IDE and compiler from Borland released in 1992.
  - [Online version.](https://turboc.pages.dev/)
- [DIV Games Studio 2](https://archive.org/details/div2_iso) - IDE to develop DOS games in 2d, mode 7 and 3d. Released in 1998.
  - [Online version.](http://js.mikedx.co.uk/DIV1.html)
- [T3X](https://t3x.org/t3x/#t3x7) - A small, portable, procedural, block-structured, recursive, almost typeless, and to some degree object-oriented programming language by Nils M. Holm.
- [SmallerC](https://github.com/alexfru/SmallerC.git) - Portable self-hosting C compiler capable of producing executables for a number of platforms, including real and protected mode DOS programs, by Alexei A. Frounze.
- [Small-C Toolkit](https://github.com/humbertocsjr/Small-C.git) - A self-hosting Small-C Compiler Toolkit for DOS(8086) with: K&R C Compiler, Make, Linker, Assembler. First released in 1982 by Jim E. Hendrix.

### Memory managers

- [386MAX](https://github.com/sudleyplace/386MAX) - Memory manager for DOS PCs with 386 or higher CPUs, [released by Qualitas company in 1992](https://winworldpc.com/product/386max/6x). Source code was released in June 2022 on GitHub with GPL-3.0 license.

### Scripting languages and interpreters for DOS

- [DOjS](https://github.com/SuperIlu/DOjS) - JavaScript programming environment for MS-DOS, FreeDOS or any DOS-based Windows (like 95, 98, ME).
- [Lua for DOS](https://archive.org/details/lua5.3.5) - Online demo of Lua 5.3.5, compiled for MS-DOS on the Intel 80486 processor.
- [Micropython for FreeDOS](https://github.com/pohmelie/micropython-freedos) - FreeDOS ad-hoc module for [micropython](https://github.com/micropython/micropython).
- [perldos](https://perldoc.perl.org/perldos) - Perl for DOS.
- [PythonD](http://www.caddit.net/pythond/) - Python for DOS, including multi-threading, networking and OpenGL.

## Tutorials and programming resources

### History

- [The Life of MS-DOS by Brendan Byers](https://b13rg.github.io/Life-of-MS-DOS/) - History of the DOS family including CP/M, Q-DOS/86-DOS, MS-DOS and PC-DOS. Article also includes a diagram of the timeline and family tree of DOS
  operating systems.

### Compiling

- [80x86 16-bit Compiling How-to by Alexei A. Frounze](http://alexfru.narod.ru/os/c16/c16.html) - 16-bit compilation tutorial for Borland/Turbo C/C++ and Open Watcom. Goes into depth of memory addressing and memory models.
- [32bit DOS development with Open Watcom](http://tuttlem.github.io/2015/10/04/32bit-dos-development-with-open-watcom.html) - 32-bit compilation tutorial for Open Watcom.
- [How to build DOS COM files with GCC by Chris Wellons](https://nullprogram.com/blog/2014/12/09/) - Build process of Chris Wellons's DOS Defender game using DJGPP. Goal was to create a 32-bit 80386 COM executable.

### General

- [David Brackeen - 256-Color VGA Programming in C](http://www.brackeen.com/vga/) - Tutorial series to learn how to create graphics on DOS.
- [640k Really is Enough for Anyone by Robert W. Oliver II](https://blog.sourcerer.io/640k-really-is-enough-for-anyone-314f393ca5b8) - Short article about getting Turbo C running on FreeDOS and moving a pixel around.
<!--lint disable no-repeat-punctuation-->
- [Just keeping it real... old skool style - Scali's OpenBlog](https://scalibq.wordpress.com/2011/11/23/just-keeping-it-real-old-skool-style/) - Blog post about Scali's journey of doing CGA, EGA and VGA programming.
<!--lint enable no-repeat-punctuation-->
- [Alex Russell's Dos Game Programming in C for Beginners](https://web.archive.org/web/20201112023702/http://www3.telus.net/alexander_russell/course/introduction.htm) - DOS game programming tutorial series including a primer on C, graphics, animation, input handling and collision detection. This series contains a tutorial for making [buffered input handling](https://web.archive.org/web/20200203195410/http://www3.telus.net/alexander_russell/course/chapter_4.htm). Last chapter contains full source code of a Break Out game on DOS.
- [The Artevida Game Programming Tutorials](http://web.archive.org/web/20201031021650/http://atrevida.comprenica.com/) - Kevin Matz's almost book-length treatment of DOS system programming and VGA programming fundamentals using C/C++ and 80x86 assembly. Unfortunately it is incomplete and was abandoned since 2001.
- [PC Game Programmer's Encyclopedia](https://web.archive.org/web/20201111164240/http://bespin.org/~qz/pc-gpe/) - Collection of guides covering assembly, sound (Sound Blaster, Gravis UltraSound, PC Speaker, GameBlaster, Adlib), input, memory (EMS, XMS, DMA Transfers), PIT, VGA, SVGA, algorithms and file formats.
- [The Art of Demomaking by flipcode](http://web.archive.org/web/20190123060222/http://www.flipcode.com/archives/The_Art_of_Demomaking-Issue_02_Introduction_To_Computer_Graphics.shtml) - Series from 1999 that introduces to graphics programming under DOS. The home site contains other late 90s/early 2000s game programming articles as well.
- [Programming MS-DOS with Power - DOS Programming, Undocumented DOS, and DOS Secrets](http://web.archive.org/web/20200626182822/http://www.fysnet.net/) - System programming tutorials like disk handling, interrupts, inputs, sound, graphics.
- [Programmer's Heaven (InfoMagic)(March 1997) CD-ROM](http://discmaster.textfiles.com/view/4555/Programmer%27s%20Heaven%20%28InfoMagic%29%28March%201997%29.BIN%2Fmain.htm) - Source code and files for the following topics: MS-DOS, networking, C, C++, Pascal, Visual Basic, Delphi, 3D, PC speaker, Soundblaster, Gravis Ultrasound, MIDI and many more.

### DOS API

- [bios.h header documentation by Digital Mars](https://digitalmars.com/rtl/bios.html) - API documentation for routines accessing BIOS operations directly (disk operations, BIOS keyboard, printer, time, memory, serial, interrupts).
- dos.h header documentation by Digital Mars [Part 1](https://digitalmars.com/rtl/dos.html) [Part 2](https://digitalmars.com/rtl/dos2.html) - API documentation of functions for interfacing with the DOS operating system itself.

### Interrupts

- [Ralph Brown's Interrupt List - HTML version](https://web.archive.org/web/20201111162212/http://www.ctyme.com/rbrown.htm) - List of every documented and undocumented interrupt call known, accessible through search, categories and interrupt numbers.
  - Original in downloadable .zip files from [Ralph Brown's website](https://web.archive.org/web/20201108093425/http://www.cs.cmu.edu/~ralf/files.html)

### Memory

- [A look back at memory models in 16-bit MS-DOS](https://devblogs.microsoft.com/oldnewthing/20200728-00/?p=104012) - Raymond Chen's explanation of segmented memory, including near- and far pointers.

### Video

- [Values for standard video mode](https://web.archive.org/web/20200214123701/http://www.columbia.edu/~em36/wpdos/videomodes.txt) - List of all known video modes including BIOS interrupt numbers, text/pixel resolution, number of colors and video memory addresses.

#### CGA

- [Color Graphics Adapter: Notes](https://web.archive.org/web/20201112020351/https://www.seasip.info/VintagePC/cga.html) - Document describing the hardware, memory map, register I/O and hardware clones of the IBM's original CGA.

#### VGA

- [VGA Hardware - OSDev wiki](https://wiki.osdev.org/VGA_Hardware) - Hardware guide for VGA cards that is also relevant for modern graphics cards including NVidia and ATI.
- [Graphical programming in Assembly (DOS)](http://web.archive.org/web/20201112040702/http://www.wagemakers.be/english/doc/vga) - A VGA programming tutorial that also shows the list of video modes (text, CGA, EGA, VGA, SVGA) in a table at the beginning.
- [VGA programming lessons](http://joco.homeserver.hu/vgalessons/) - VGA programming tutorial series in Pascal and Assembly.

#### SVGA

- [DOS Super VGA / VESA programming notes - by Myles](https://web.archive.org/web/20200724153658/http://www.faqs.org/faqs/pc-hardware-faq/supervga-programming/) - VESA article with history at the beginning and short mention of the VESA VBE standard, but unfortunately the example codes aren't even available through Wayback Machine.
- [VESA Video Modes - OSDev wiki](https://wiki.osdev.org/Getting_VBE_Mode_Info) - Tutorial about querying VESA modes.
- [DJGPP VESA guide](http://www.delorie.com/djgpp/doc/ug/graphics/vesa.html.en) - Tutorial about querying VESA modes.
- [High-res high-speed VESA tutorial](https://web.archive.org/web/20200128180543/http://www.monstersoft.com/tutorial1/) - Series of tutorials that include drawing pixels in VESA mode (protected or real).
- [C code sample for drawing in VESA 2.0 mode](https://web.archive.org/web/20200121065447/http://www.codenet.ru/progr/video/vesa20ex.php) - Just code listing for drawing an ellipse in VESA mode.

### Sound

- [Programming Sound Cards CD](http://discmaster.textfiles.com/browse/63/Programming%20Sound%20Cards.iso) - A 1995 CD-ROM containing source code for Adlib, Gravis, Pro-Audio, Roland and Sound Blaster sound cards. The description for the folders on the CD-ROM is listed [on the back of the CD-ROM case.](https://archive.org/details/programming-sound-cards/Programming%20Sound%20Cards_back.jpg)

#### PC Speaker

- [Making some noise with the PC speaker! - by Mark Feldman](https://web.archive.org/web/20150302161648/http://heim.ifi.uio.no/~inf3150/grupper/1/pcspeaker.html) - Very short tutorial on using the PIT for generating PC speaker frequency.
- [Frequencies of Musical Notes](https://web.archive.org/web/20201129091353/https://pages.mtu.edu/~suits/notefreqs.html) - Freqency table usable to parameterize the PC speaker.
- [Sound Programming with PC Speaker - Chapter 23 of A to Z of C](https://web.archive.org/web/20171115162742/http://guideme.itgo.com/atozofc/ch23.pdf) - PC speaker programming chapter of the "A to Z of C" book with source code.

#### AdLib/OPL2

- [Yamaha YM3812 (OPL2) sound chip Wikipedia article](https://en.wikipedia.org/wiki/Yamaha_YM3812) - Best starting point to learn about the OPL2 sound chip besides 8-bit guy's YouTube video.
- [The Ad Lib Music Synthesizer Card Programming Guide - by Tero Töttö](https://web.archive.org/web/20200427145810/http://www.vgmpf.com/Wiki/images/4/48/AdLib_-_Programming_Guide.pdf) - Reference of OPL2 operations and registers.

#### Sound Blaster/OPL3

- [Programmer's Guide to the Yamaha YMF 262/OPL3 FM Music Synthesizer](https://web.archive.org/web/20200509082459/http://www.fit.vutbr.cz/~arnost/opl/opl3.html) - Reverse-engineered reference on OPL3.
- [Sound Blaster 16 Programming Document 3.5 by Ethan Brodsky](https://web.archive.org/web/20201130110457/http://homepages.cae.wisc.edu/~brodskye/sb16doc/sb16doc.html) - Programming the Sound Blaster 16 DSP CT1341 chip for recording and playback of digitized audio.
  - version 3.4 on [GameDev.net archive](https://web.archive.org/web/20180507161514/http://archive.gamedev.net/archive/reference/articles/article444.html)
- [Soundblaster Programming Information v0.90](https://web.archive.org/web/20191020222313/http://www.intel-assembler.it/portale/5/soundblaster-programming-information/sb-reference-for-programming-sound.asp) - List of Sound Blaster models and registers.

### Other

- [Table of DOSBox cyclecounts according to processor types](https://web.archive.org/web/20201112012244/https://www.alternatewars.com/Games/DOSBox/DOSBox.htm) - A table for setting the appropriate DOSBox cycle count according to CPU types (IBM XT 88, 286, 386, 486, Pentium I, Pentium II). Comes handy when you are developing a DOS game and want to simulate the environment where you intend to execute it.

## Books

### Free

- [Game Engine Black Book: Wolfenstein 3D - by Fabien Sanglard](https://web.archive.org/web/20221226120420/https://fabiensanglard.net/b/gebbwolf3d.pdf) - Fabien Sanglard's walkthrough on the game engine architecture of id Software's Wolfenstein 3D on the IBM PC's hardware. Contains forewords by John Carcmack, Tom Hall and John Romero.
- [Game Engine Black Book: Doom - by Fabien Sanglard](https://web.archive.org/web/20221225164613/https://fabiensanglard.net/b/gebbdoom.pdf) - Fabien Sanglard's walkthrough on the game engine architecture of id Software's original Doom on Intel 486 system and game console ports. Contains forewords by John Carcmack, Dave Taylor and John Romero.
- [A to Z of C - a book on C/DOS programming by K. Joseph Wesley and R. Rajesh Jeba Anbiah](https://web.archive.org/web/20201109033646/http://guideme.itgo.com/atozofc/) - Non-profit book on programming in C on DOS. DOS system programming starts from Part II.
- [Michael Abrash's Graphics Programming Black Book Special Edition](https://www.drdobbs.com/parallel/graphics-programming-black-book/184404919) - Collection of Michael Abrash's Dr. Dobb's Journal graphics programming articles and his work on the graphics subsystem of Quake ([mirror](https://web.archive.org/web/20201112020812/http://www.phatcode.net/res/224/files/html/index.html)).

### Paid

- [Tricks of the Game-Programming Gurus - by Andre Lamothe, John Ratcliff and Denise Tyler](https://www.amazon.com/Tricks-Game-Programming-Gurus-Andre-Lamothe/dp/0672305070/) - Comprehensive DOS game development book about starting out, creating 2D and basic 3D graphics, I/O and game algorithms.

## Videos

- [Why DOS Was (and Is) a Thing - FreeDOS](https://www.youtube.com/watch?v=3E5Hog5OnIM) - Historical talk starting from Unix, going through CPM, DOS 1.x, DOS 2.x, DOS 3.x, DOS 4.x, DOS 6.x, Windows 3.1, Windows 95 and ending with FreeDOS.
- [CGA Graphics - Not as bad as you thought! - by 8-bit Guy](https://www.youtube.com/watch?v=niKblgZupOc) - History and technical details about IBM's CGA system. Also describes 4-color RGBI and 16-color Composite modes.
- [How Oldschool Sound/Music worked - by 8-bit Guy](https://www.youtube.com/watch?v=q_3d1x2VPxk) - Video about PC speaker, FM synthesizers in NES and Commodore 64, Yamaha OPL chip in AdLib and Sound Blaster sound cards, PCM samples and MOD music.
- [Let's Code - MS DOS - by root42](https://www.youtube.com/playlist?list=PLGJnX2KGgaw2L7Uv5NThlL48G9y4rJx1X) - DOS programming tutorial series including VGA, SoundBlaster and VGA Mode X.
- [LGR - Evolution of PC Audio - As Told by Secret of Monkey Island](https://www.youtube.com/watch?v=a324ykKV-7Y) - Comparison of playing the intro theme of Secret of Monkey Island through PC speaker, IBM PCjr/Tandy, AdLib, Game Blaster, Roland LAPC-1/MT-32, Gravis Ultrasound, Roland SCC-1 MIDI, SB16 Waveblaster/AWE32 and CD quality digital audio.
- [Porting Retro City Rampage to MS-DOS: From PS4 to 1.44MB Floppy](https://www.youtube.com/watch?v=kSKeWH4TY9Y) - GDC talk. Brian Provinciano's presentation on porting Retro City Rampage from PlayStation 4 to DOS. Topics include optimization, using interrupts, timing, PC speaker sound, joystick, memory management and fixed-point math.
- [DOS Executables Explained - Nostalgia Nerd](https://www.youtube.com/watch?v=6j947U4xl5I) - Video about DOS executable formats including `.COM`, `.BAT` and `.EXE`.
- [Why does DOS use 8.3 Filenames? - Nostalgia Nerd](https://www.youtube.com/watch?v=eGIyCD2_qA8) - Video about the 8.3 limitation of filenames under DOS, FAT partitioning scheme, NTFS, VFAT, FatGo, and `LFN.EXE`.
- [What is DOS Protected Mode? / DOS Extenders- Nostalgia Nerd](https://www.youtube.com/watch?v=XAyQLV5bbb0) - Video about how PC memory looks like, conventional memory, extender memory and reasons for the need of DOS Protected Mode Interface (DPMI) and extenders like DOS/4GW.
- [MS-DOS has been Open-Sourced! We Build and Run it! - Dave's Garage](https://www.youtube.com/watch?v=BR6F0EdyulA) - Former Microsoft employee David Plummer tells stories about development of MS-DOS and compiles MS-DOS 4.00 source code which has been open-sourced by Microsoft.

## Source code

### Open source DOS operating systems

- [MS-DOS](https://github.com/microsoft/MS-DOS) - GitHub repository of the original source code for MS-DOS v1.25, v2.0 and v4.0, open-sourced by Microsoft.
- [FreeDOS](https://www.freedos.org/) - FreeDOS is an open source DOS-compatible operating system that you can use to play classic DOS games, run legacy business software, or develop embedded systems. Any program that works on MS-DOS should also run on FreeDOS.

### Open source DOS libraries

- [Allegro 4.2](https://www.allegro.cc/files/?v=4.2) - Game development library for DOS, Windows and Linux.
- [LoveDOS](https://github.com/rxi/lovedos) - A framework for making 2D DOS games in Lua. API based on a subset of the LÖVE API.
- [DOS-VGA-Game](https://github.com/marcomarrero/DOS-VGA-Game) - Marco A. Marrero's DOS VGA/hardware library implemented in assembly and Turbo Pascal.
- [DIGPAK sound drivers source code](https://github.com/jratcliff63367/digpak) - Original source code for the DIGPAK sound drivers uploaded to GitHub by John W. Ratcliff.

### Open source DOS games

#### Homebrew games with source code

List of all homebrew DOS games: http://www.doshaven.eu

- [DOS Defender](https://github.com/skeeto/dosdefender-ld31) - Christopher Wellons's x86 real mode DOS Asteroids clone created as an entry for Lundum Dare #31.
- [Dungeons of Noudar](https://github.com/TheFakeMontyOnTheRun/dungeons-of-noudar) - First-person 2.5D dungeon-crawler on protected mode. Written in C++, includes software rendering, fixed point math, test coverage and sound (PC speaker, Adlib, OPL2LPT).
- [Emeritus Pong](https://sourceforge.net/projects/empong/) - Pong clone for DOS, Windows and Linux. Uses PC speaker for sound on DOS.
- [Floppy Bird](https://github.com/icebreaker/floppybird) - Flappy Bird clone written in 16 bit assembly. Not a DOS program, but a PC-Booter application instead (although it's also possible to build a COM executable for DOS).
- [George M. Tzoumas's collection of MS-DOS games and utilities](http://web.archive.org/web/20191225101138/http://cgi.di.uoa.gr/~geotz/dos/) - Turbo Pascal with few games in C and C++. Games include Nibbles, Connect Four, Ms Pacman clone and two arcade/platform games. One of them (ra2) was written using Allegro. Utilities are all written in Turbo Pascal, these include game system routines, file and disk utilities and terminate-and-stay-resident programs (TSR).
- [Gold Mine Run!](https://www.usebox.net/jjm/gold-mine-run/) - Platformer written in C using DJGPP.
- [Gridfighter 3D](https://porta2note.itch.io/gridfighter-3d) - '80s style arcade shooter written in Quickbasic. Also the very first known DOS game that supports Oculus Rift VR headset.
  - [GitHub repository](https://github.com/porta2note/gridfighter3d)
- [Hangman](https://sourceforge.net/projects/hangman-dos/) - Hangman clone written in Basic. Runs on at least 80286 processors and uses EGA graphics.
- [Magenta's Maze](https://archive.org/details/MAGSMAZE) - 3D maze game using CGA graphics with algebra as theme.
  - [Source code download link](http://www.doshaven.eu/downloads/537)
- [Mario](http://www.wieringsoftware.nl/mario/index.html) - Super Mario Bros clone written in Turbo Pascal.
- [NetHack](https://github.com/NetHack/NetHack) - Descendant of the original [NetHack](https://en.wikipedia.org/wiki/NetHack) rougelike game first released in 1987 available on multiple platforms.
- [Piskworks](https://github.com/berk76/piskworks) - Gomoku clone written in C. Works on DOS, ZX Spectrum, ZX81, ZX80, APPLE1, AS400 and Windows.
- [Plutonium Caverns](https://github.com/jani-nykanen/plutonium-caverns) - Overhead puzzle game written in C. Web version uses [DOSBox ported to Emscripten](https://github.com/dreamlayers/em-dosbox) to embed DOSBox into HTML5. However, the original executable is also downloadable and buildable with Open Watcom.
- [Ptakovina](https://github.com/berk76/tetris) - Tetris clone written in C. Runs on DOS, Unix/Linux, ZX Spectrum and Windows.
- [sudoku86](https://sourceforge.net/projects/sudoku86/) - Sudoku clone written in C. Runs on 8086/8088 CPU, uses CGA, MCGA or VGA graphics and uses a mouse.
- [Tetris](http://www.doshaven.eu/game/tetris/) - Tetris clone written in assembly.
  - [Source code download link](http://www.doshaven.eu/downloads/373)
- [Towers of Hanoi](https://github.com/sblendorio/hanoi-dos) - [Tower of Hanoi](https://en.wikipedia.org/wiki/Tower_of_Hanoi) puzzle game written in Turbo Pascal. Originally released in 1996.
- [x86 pong](https://github.com/spacerace/x86-pong) - Text-mode Pong clone written in C. Runs as PC-Booter game and under DOS.
- [zmiy](https://sourceforge.net/projects/zmiy/) - Text-mode Snake clone written in C. Runs on 8086 DOS.

#### Freeware games with source code

- [Cyberdogs](https://web.archive.org/web/20190222022411/https://www.classicdosgames.com/game/Cyberdogs.html) - Top-down 2D shooter playing as a mercenary to earn money. Written in Turbo Pascal. Supports two player mode.
  - [Source code download link](https://web.archive.org/web/20180120123425/https://www.classicdosgames.com/files/source/dogs_src.zip)
  - [C-Dogs](https://en.wikipedia.org/wiki/C-Dogs) - Sequel to the original Cyberdogs. Ronny Wester, the original creator no longer maintains the website for the original C-Dogs, but multiple ports exists, including [cdogs-sdl](https://congusbongus.itch.io/cdogs-sdl).

#### Commercial games with published source code

- [Abuse](https://web.archive.org/web/20190801083909/https://www.classicdosgames.com/game/Abuse.html) - Sci-fi side-scrolling platform game. Regarded as an innovative cult classic by most people. Supports SVGA mode up to 1280x1024 resolution. Written in C, the architecture includes a Lisp-scripting engine.
  - [Source code download link](https://web.archive.org/web/20160402141350/http://www.classicdosgames.com/files/source/abuse_pd.tgz)
- [Beneath a Steel Sky](https://web.archive.org/web/20200721064209/https://www.classicdosgames.com/game/Beneath_a_Steel_Sky.html) - Point-and-click adventure game set in a dystopian future. Written in assembly.
  - [Source code download link](https://web.archive.org/web/20200721083621/https://www.classicdosgames.com/files/source/sky-source.zip)
- [Catacomb](https://github.com/CatacombGames/Catacomb) - 2D top-down shooter developed by Softdisk (later becoming id Software). Supports EGA and CGA graphics. Written in Turbo Pascal and assembly.
- [Catacomb 3D](https://github.com/CatacombGames/Catacomb3D) - First-person shooter in fantasy setting developed by Softdisk (later becoming id Software). Features pseudo-3D graphics with raycasting technique. Supports EGA graphics. Written in C and assembly. Compiled with Borland C++ 3.1.
- [Commander Keen in Keen Dreams](https://github.com/keendreams/keen) - Side-scrolling platform game developed by id Software. Keen Dreams is the Commander Keen game created between Keen 3 and Keen 4 (often considered "Keen 3.5"), but was not widely released. Written in C and assembly.
- [Descent](https://github.com/videogamepreservation/descent) - First sci-fi FPS/space shooter to feature entirely true 3D graphics. Written in C and assembly.
- [Descent II](https://github.com/videogamepreservation/descent2) - Sequel to Descent. Written in C and assembly.
- [Doom](https://github.com/id-Software/DOOM) - Sci-fi FPS developed by id Software where you fight demons from hell on Mars. The DOS-specific code for Doom could not be published because of a dependency to the licensed DMX sound library, hence why it's cleaned up and only the Linux source is there. However, the Heretic and Hexen projects contain the original DOS code in a way where DMX-related code is removed.
- [Duke Nukem 3D](https://web.archive.org/web/20190304015745/https://www.classicdosgames.com/game/Duke_Nukem_3D.html) - FPS developed by Apogee featuring the iconic character Duke Nukem. Written in C. Compiled with Watcom C/C++ 10.0.
  - [Source code download link](https://web.archive.org/web/20160403223736/http://www.classicdosgames.com/files/source/duke3dsource.zip)
- [Heretic](https://github.com/OpenSourcedGames/Heretic) - Dark fantasy FPS running on id Software's Doom engine.
- [Hexen: Beyond Heretic](https://github.com/OpenSourcedGames/Hexen) - Indirect sequel to Heretic.
  - Original [SourceForge link](https://sourceforge.net/projects/heretic/files/) for Heretic/Hexen.
- [Hovertank 3D](https://github.com/FlatRockSoft/Hovertank3D) - FPS developed by id Software. Features pseudo-3D graphics with raycasting technique, before Catacomb 3D and Wolfeinstein 3D. Written in C and assembly.
- [Quake](https://github.com/id-Software/Quake) - FPS developed by id Software set in a fully 3D world. Written in C. Compiled with DJGPP for DOS.
  - [Quake Engine Code Review series](https://fabiensanglard.net/quakeSource/index.php) - Code analysis by Fabien Sanglard.
- [Rise of the Triad: Dark War](https://github.com/videogamepreservation/rott) - FPS developed by Apogee. It was developed as a follow-up to Wolfenstein 3D, but was altered and became a standalone game instead. Uses a heavily modified Wolfenstein 3D engine. Written in C.
- [Sopwith](https://web.archive.org/web/20200131222432/http://davidlclark.com/page/sopwith) - Side-scrolling shoot 'em up created by David L. Clark in 1984. The game involves piloting a Sopwith biplane, attempting to bomb enemy buildings while avoiding fire from enemy planes and various other obstacles.
  - [MaiZure's Projects - Decoded: Sopwith](https://web.archive.org/web/20201211175311/https://www.maizure.org/projects/decoded-sopwith/) - Code analysis by MaiZure.
- [Wolfenstein 3D](https://github.com/id-Software/wolf3d) - FPS developed by id Software set in the Nazi German prison Castle Wolfenstein. Features pseudo-3D graphics with raycasting technique. Written in C and assembly.
