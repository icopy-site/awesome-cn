<div class="github-widget" data-repo="tobiasvl/awesome-chip-8"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome CHIP-8 [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/tobiasvl/awesome-chip-8/master/c8.png" align="right" width="100">](https://chip-8.github.io)

&gt; 70 年代的虚拟电脑游戏机 

精选的 CHIP-8 资源、工具、文档、相关项目和开源 ROM 的精选列表.

创建于 1977 年， [CHIP-8](https://en.wikipedia.org/wiki/CHIP-8) 是最初的幻想控制台. 最初旨在简化 COSMAC VIP 套件计算机的游戏开发，几十年来，它在新的和令人兴奋的平台上得到了几次复兴. 今天，对于任何有兴趣学习仿真的人来说，创建一个 CHIP-8 实现是一种通过仪式.

要将某些内容添加到此列表中，请参阅 [contribution guidelines](https://github.com/tobiasvl/awesome-chip-8/blob/master/CONTRIBUTING.md).



## Community

* [COSMAC Elf Group](https://groups.io/g/cosmacelf) - 讨论 COSMAC Elf 以及与 RCA 1802 相关的任何其他内容的小组，包括 COSMAC VIP 和 CHIP-8.
* [#chip8 channel on the Emulation Development Discord server](https://discordapp.com/invite/Gf7cP3w) - 讨论 CHIP-8 仿真器/解释器开发的聊天.
* [OctoJam](http://octojam.com/) - 每年 10 月举行的以 Octo 为中心的 Game Jam.

## Documentation

* [Mastering CHIP-8](https://github.com/mattmikolay/chip-8/wiki/Mastering-CHIP%E2%80%908) - 深入了解 CHIP-8 指令集.
* [CHIP-8 Instruction Set](http://johnearnest.github.io/Octo/docs/chip8ref.pdf) - CHIP-8 说明的快速备忘单.
* [CHIP-8 Instruction Set](https://github.com/mattmikolay/chip-8/wiki/CHIP%E2%80%908-Instruction-Set) - 一个全面的指令/操作码表.
* [CHIP-8 Technical Reference](https://github.com/mattmikolay/chip-8/wiki/CHIP%E2%80%908-Technical-Reference) - CHIP-8 解释器如何工作的概述.
* [CHIP-8 Extensions Reference](https://github.com/mattmikolay/chip-8/wiki/CHIP%E2%80%908-Extensions-Reference) - CHIP-8 变体和扩展列表.
* [Chip-8 on the COSMAC VIP](https://laurencescotford.com/chip-8-on-the-cosmac-vip-index/) - COSMAC VIP原版CHIP-8解释器深度拆解分析.
* [HP48-Superchip](https://github.com/Chromatophore/HP48-Superchip) - 深入了解 HP48 计算器的 CHIP48 和 Super-CHIP，以及使它们兼容 CHIP-8 的修改.
* [Octo Extensions](http://johnearnest.github.io/Octo/docs/XO-ChipSpecification.html) - Octo 的 XO-CHIP 扩展规范.

## Emulator/interpreter development

* [How to write an emulator (CHIP-8 interpreter)](http://www.multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/) - 在 C/C++ 中开发 CHIP-8 解释器的指南.
* [Emulator 101: CHIP-8](http://www.emulator101.com/introduction-to-chip-8.html) - 用 C 语言开发 CHIP-8 反汇编器和解释器的指南.
* [Chip 8 Instruction Scheduling and Frequency](https://jackson-s.me/2019/07/13/Chip-8-Instruction-Scheduling-and-Frequency.html) - COSMAC VIP 上 CHIP-8 指令的时间安排.
* [High-level guide to making a CHIP-8 emulator](https://tobiasvl.github.io/blog/write-a-chip-8-emulator/) - 无需代码即可开发 CHIP-8 解释器的指南.

### Testing

* [chip8-test-rom](https://github.com/corax89/chip8-test-rom) - corax89 的 CHIP-8 测试程序，它测试大多数指令的正确（符合超级芯片）行为.
* [Delay timer test](https://github.com/mattmikolay/chip-8/tree/master/delaytimer) - 检查延迟计时器行为的测试程序.
* [Random number test](https://github.com/mattmikolay/chip-8/tree/master/randomnumber) - 检查随机数生成的传播和掩码的测试程序.

## Emulators/interpreters

* [Octo](http://johnearnest.github.io/Octo/) - 用于开发 CHIP-8、Super-CHIP 和 XO-Chip 游戏的 IDE.
* [Emma02](https://www.emma02.hobby-site.com/) - 许多旧微型计算机的模拟器，包括 COSMAC VIP、Telmac 1800 和 ETI 660，它们运行早期的 CHIP-8 解释器（包含在模拟器中）.
* [Super-Chip8x](https://github.com/Ersanio/Super-Chip8x) - SNES 的 CHIP-8 模拟器.
* [CHIP-8 console on FPGA](https://github.com/pwmarcz/fpga-chip8) - TinyFPGA BX 芯片的 CHIP-8 仿真器.
* [Vinegar](http://benryves.com/bin/vinegar/) - 用于 TI-83 (Plus) 计算器的 CHIP-8/Super-CHIP 解释器.
* [LowResNX](https://lowresnx.inutilis.com/topic.php?id=1648) - CHIP-8 解释器和调试器在另一个复古幻想控制台中用 BASIC 编程.

## Software development

### Tools

* [Octo](http://github.com/johnearnest/Octo/) - 用于 CHIP-8、Super-CHIP 和 XO-CHIP 的高级汇编程序，配有用于测试程序的环境和用于共享您的创作的工具.
* [wernsey chip8](https://github.com/wernsey/chip8) - 一个 CHIP-8 汇编器/反汇编器.
* [EZ-Bake Animator](http://beyondloom.com/tools/ezbake.html) - 创建异或动画的图形准备工具.
* [EZ-Writer](http://beyondloom.com/tools/ezwriter.html) - 将文本转换为 CHIP-8 精灵的工具.
* [EZ-Pack](http://beyondloom.com/tools/ezpack.html) - 图像切片/重新调色工具.
* [Chipify](http://johnearnest.github.io/Octo/tools/Chipify/) - 将单声道 WAV 音频过滤和编码为 XO-CHIP 音频的脚本.
* [octofont](https://github.com/jdeeny/octofont/) - 将 TrueType (ttf) 字体转换为 CHIP-8 的 Octo 代码.

### Guides and snippets

* [Octo manual](https://johnearnest.github.io/Octo/docs/Manual.html) - Octo 的手册.
* [A Beginner's Guide to Programming with Chip8](http://johnearnest.github.io/Octo/docs/BeginnersGuide.html) - Octo 中 CHIP-8 编程的介绍指南.
* [An Intermediate Guide to Game Development with Chip8](http://johnearnest.github.io/Octo/docs/IntermediateGuide.html) - 在 Octo 中为 CHIP-8 重新制作 Atari 2600 游戏“Outlaw”.
* [Chip8 Programming Techniques](http://johnearnest.github.io/Octo/docs/Chip8%20Programming.html) - 许多不同的 CHIP-8 编程技巧.
* [Octo Metaprogramming Cookbook](http://johnearnest.github.io/Octo/docs/MetaProgramming.html) - 如何使用 Octo 的汇编指令进行元编程.
* [Mastering SuperChip](http://johnearnest.github.io/Octo/docs/SuperChip.html) - 如何使游戏兼容 CHIP-8 和 Super-CHIP，以及一些 Super-CHIP 特定技术.
* [Adventures in Sorting](https://johnearnest.github.io/Octo/docs/Sorting.html) - 在 Octo 中为 CHIP-8 实现高效的排序算法.
* [chip8-multiply](https://github.com/jdeeny/chip8-multiply) - CHIP-8 的乘法例程，用 Octo 编写.

### Postmortems

由开发人员编写的详细说明特定游戏开发的事后分析.

* [Inside Eaty the Alien](http://johnearnest.github.io/Octo/docs/EatyTheAlien.html)
* [Octopeg Post Mortem](http://www.awfuljams.com/octojam-ii/games/octopeg)
* [CosmacCalc: The COSMAC VIP's place in Spreadsheet History](https://abitoutofplace.wordpress.com/2015/05/02/cosmaccalc-the-cosmac-vip-s-place-in-spreadsheet-history/)
* [Inside Cave Explorer](http://johnearnest.github.io/Octo/docs/CaveExplorer.html)
* [Inside Black Rainbow](http://johnearnest.github.io/Octo/docs/BlackRainbow.html)
* [Postmortem: Mini Lights Out](https://tobiasvl.itch.io/mini-lights-out/devlog/102679/postmortem-mini-lights-out)

## Games

* [CHIP-8 Archive](https://johnearnest.github.io/chip8Archive/) - 一系列公共领域 (CC0) 游戏，均可在线玩.
* [A collection of CHIP-8 programs and documentation](https://github.com/mattmikolay/chip-8) - Matt Mikolay 的游戏、程序和文档.
