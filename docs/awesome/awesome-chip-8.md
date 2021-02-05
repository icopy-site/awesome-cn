<div class="github-widget" data-repo="tobiasvl/awesome-chip-8"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome CHIP-8 [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/tobiasvl/awesome-chip-8/master/c8.png" align="right" width="100">](https://chip-8.github.io)

&gt; 70年代的虚拟计算机游戏机 

精选的CHIP-8资源，工具，文档，相关项目和开源ROM的精选列表.

创建于1977年， [CHIP-8](https://en.wikipedia.org/wiki/CHIP-8) 是原始的幻想游戏机. 最初旨在简化COSMAC VIP套件计算机的游戏开发，但在过去几十年中，它因新的令人兴奋的平台而经历了几次复兴. 如今，对于任何有兴趣学习仿真的人来说，创建CHIP-8实现都是一个礼拜式.

要将某物添加到此列表，请参阅 [contribution guidelines](https://github.com/tobiasvl/awesome-chip-8/blob/master/CONTRIBUTING.md).



## Community

* [COSMAC Elf Group](https://groups.io/g/cosmacelf) -讨论COSMAC Elf以及与RCA 1802相关的任何其他事项的小组，包括COSMAC VIP和CHIP-8.
* [#chip8 channel on the Emulation Development Discord server](https://discordapp.com/invite/Gf7cP3w) -讨论CHIP-8仿真器/解释器的开发.
* [OctoJam](http://octojam.com/) -每年十月举行一次以八度为中心的比赛.

## Documentation

* [Mastering CHIP-8](http://mattmik.com/files/chip8/mastering/chip8.html) -CHIP-8指令集的深入概述.
* [CHIP-8 Instruction Set](http://johnearnest.github.io/Octo/docs/chip8ref.pdf) -快速备忘单，用于CHIP-8说明.
* [CHIP-8 Instruction Set](https://github.com/mattmikolay/chip-8/wiki/CHIP%E2%80%908-Instruction-Set) -全面的指令/操作码表.
* [CHIP-8 Technical Reference](https://github.com/mattmikolay/chip-8/wiki/CHIP%E2%80%908-Technical-Reference) -CHIP-8解释器的工作原理概述.
* [CHIP-8 Extensions Reference](https://github.com/mattmikolay/chip-8/wiki/CHIP%E2%80%908-Extensions-Reference) -CHIP-8变体和扩展列表.
* [Chip-8 on the COSMAC VIP](https://laurencescotford.com/chip-8-on-the-cosmac-vip-index/) -在COSMAC VIP上对原始CHIP-8解释程序的深入分解和分析.
* [HP48-Superchip](https://github.com/Chromatophore/HP48-Superchip) -对HP48计算器的CHIP48和Super-CHIP进行了深入研究，并进行了改进使其与CHIP-8兼容.
* [Octo Extensions](http://johnearnest.github.io/Octo/docs/XO-ChipSpecification.html) -Octo的XO-CHIP扩展规范.

## Emulator/interpreter development

* [How to write an emulator (CHIP-8 interpreter)](http://www.multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/) -在C / C ++中开发CHIP-8解释器的指南.
* [Emulator 101: CHIP-8](http://www.emulator101.com/introduction-to-chip-8.html) -在C语言中开发CHIP-8反汇编程序和解释程序的指南.
* [Chip 8 Instruction Scheduling and Frequency](https://jackson-s.me/2019/07/13/Chip-8-Instruction-Scheduling-and-Frequency.html) -COSMAC VIP上CHIP-8指令的计时.
* [High-level guide to making a CHIP-8 emulator](https://tobiasvl.github.io/blog/write-a-chip-8-emulator/) -无需代码即可开发CHIP-8解释器的指南.

### Testing

* [chip8-test-rom](https://github.com/corax89/chip8-test-rom) -corax89的CHIP-8测试程序，用于测试大多数指令的正确行为（符合Super-CHIP）.
* [Delay timer test](https://github.com/mattmikolay/chip-8/tree/master/delaytimer) -检查延迟计时器行为的测试程序.
* [Random number test](https://github.com/mattmikolay/chip-8/tree/master/randomnumber) -测试程序，检查扩展和掩码以生成随机数.

## Emulators/interpreters

* [Octo](http://johnearnest.github.io/Octo/) -用于开发CHIP-8，Super-CHIP和XO-Chip游戏的IDE.
* [Emma02](https://www.emma02.hobby-site.com/) -适用于许多旧微型计算机的仿真器，包括COSMAC VIP，Telmac 1800和ETI 660，它们运行早期的CHIP-8解释器（包含在仿真器中）.
* [Super-Chip8x](https://github.com/Ersanio/Super-Chip8x) -SNES的CHIP-8模拟器.
* [CHIP-8 console on FPGA](https://github.com/pwmarcz/fpga-chip8) -用于TinyFPGA BX芯片的CHIP-8仿真器.
* [Vinegar](http://benryves.com/bin/vinegar/) -适用于TI-83（Plus）计算器的CHIP-8 / Super-CHIP解释器.
* [LowResNX](https://lowresnx.inutilis.com/topic.php?id=1648) -在另一个复古式幻想控制台中用BASIC编程的CHIP-8解释器和调试器.

## Software development

### Tools

* [Octo](http://github.com/johnearnest/Octo/) -CHIP-8，Super-CHIP和XO-CHIP的高级汇编器，配有用于测试程序的环境以及用于共享创作的工​​具.
* [wernsey chip8](https://github.com/wernsey/chip8) -CHIP-8汇编器/反汇编器.
* [EZ-Bake Animator](http://beyondloom.com/tools/ezbake.html) -创建XOR版本动画的图形准备工具.
* [EZ-Writer](http://beyondloom.com/tools/ezwriter.html) -用于将文本转换为CHIP-8子画面的工具.
* [EZ-Pack](http://beyondloom.com/tools/ezpack.html) -图像切片/重新分割工具.
* [Chipify](http://johnearnest.github.io/Octo/tools/Chipify/) -将单通道WAV音频过滤并编码为XO-CHIP音频的脚本.
* [octofont](https://github.com/jdeeny/octofont/) -将TrueType（ttf）字体转换为CHIP-8的Octo代码.

### Guides and snippets

* [Octo manual](https://johnearnest.github.io/Octo/docs/Manual.html) -Octo手册.
* [A Beginner's Guide to Programming with Chip8](http://johnearnest.github.io/Octo/docs/BeginnersGuide.html) -Octo中的CHIP-8编程入门指南.
* [An Intermediate Guide to Game Development with Chip8](http://johnearnest.github.io/Octo/docs/IntermediateGuide.html) -在Octo为CHIP-8重制Atari 2600游戏“ Outlaw”.
* [Chip8 Programming Techniques](http://johnearnest.github.io/Octo/docs/Chip8%20Programming.html) -CHIP-8的许多不同编程技巧.
* [Octo Metaprogramming Cookbook](http://johnearnest.github.io/Octo/docs/MetaProgramming.html) -如何使用Octo的汇编指令进行元编程.
* [Mastering SuperChip](http://johnearnest.github.io/Octo/docs/SuperChip.html) -如何使游戏与CHIP-8和Super-CHIP兼容，以及某些Super-CHIP特定技术.
* [Adventures in Sorting](https://johnearnest.github.io/Octo/docs/Sorting.html) -在Octo中为CHIP-8实现高效的排序算法.
* [chip8-multiply](https://github.com/jdeeny/chip8-multiply) -用Octo编写的CHIP-8乘法例程.

### Postmortems

由开发人员编写的尸体详细介绍了特定游戏的开发.

* [Inside Eaty the Alien](http://johnearnest.github.io/Octo/docs/EatyTheAlien.html)
* [Octopeg Post Mortem](http://www.awfuljams.com/octojam-ii/games/octopeg)
* [CosmacCalc: The COSMAC VIP's place in Spreadsheet History](https://abitoutofplace.wordpress.com/2015/05/02/cosmaccalc-the-cosmac-vip-s-place-in-spreadsheet-history/)
* [Inside Cave Explorer](http://johnearnest.github.io/Octo/docs/CaveExplorer.html)
* [Inside Black Rainbow](http://johnearnest.github.io/Octo/docs/BlackRainbow.html)
* [Postmortem: Mini Lights Out](https://tobiasvl.itch.io/mini-lights-out/devlog/102679/postmortem-mini-lights-out)

## Games

* [CHIP-8 Archive](https://johnearnest.github.io/chip8Archive/) -一系列可在线玩的公共领域（CC0）游戏.
* [A collection of CHIP-8 programs and documentation](https://github.com/mattmikolay/chip-8) -Matt Mikolay的游戏，程序和文档.
