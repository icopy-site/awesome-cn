<div class="github-widget" data-repo="fkie-cad/awesome-embedded-and-iot-security"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">
	<img width="500" height="350" src="https://raw.githubusercontent.com/fkie-cad/awesome-embedded-and-iot-security/master/iot_awesome_logo.svg?sanitize=true" alt="Awesome">
  <br />
</div>

## Awesome Embedded and IoT Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

 &gt;精选的有关嵌入式和IoT安全的优秀资源列表.  该列表包含软件和硬件工具，书籍，研究论文等.

僵尸网络喜欢 [Mirai](https://en.wikipedia.org/wiki/Mirai_(malware) ）已证明嵌入式和IoT设备需要更高的安全性.  该列表将帮助初学者和专家找到有关该主题的有用资源.  
如果您是初学者，则应该看看 [Books](#books) 和 [Case Studies](#case-studies) 部分.  
如果您想立即开始自己的分析，则应给 [Analysis Frameworks](#analysis-frameworks) 尝试一下.
它们易于使用，您无需成为专家即可获得首个有意义的结果.

&gt; *标有：euro：的物品是商业产品.*




## Software Tools
用于分析嵌入式/ IoT固件的软件工具.

### Analysis Frameworks

- [EXPLIoT](https://gitlab.com/expliot_framework/expliot) -Pentest框架，例如Metasploit，但专门用于物联网.
- [FACT - The Firmware Analysis and Comparison Tool](https://fkie-cad.github.io/FACT_core/) -功能齐全的静态分析框架，包括固件提取，使用不同插件的分析以及不同固件版本的比较.
- [FwAnalyzer](https://github.com/cruise-automation/fwanalyzer)  -根据自定义规则分析固件的安全性.  打算作为DevSecOps中的附加步骤，类似于CI.

### Analysis Tools

- [Binwalk](https://github.com/ReFirmLabs/binwalk) -在二进制文件中搜索“有趣”的东西.  
- [Firmadyne](https://github.com/firmadyne/firmadyne) -尝试模拟和渗透固件.
- [firmwalker](https://github.com/craigz28/firmwalker) -在提取的固件映像中搜索有趣的文件和信息.
- [Firmware Slap](https://github.com/ChrisTheCoolHut/Firmware_Slap) -通过概念分析和功能集群发现固件中的漏洞.
- [Ghidra](https://ghidra-sre.org/)  -软件逆向工程套件；  如果提供了二进制的CPU体系结构和字节序，则可以处理任意二进制文件.
- [Radare2](https://github.com/radare/radare2) -软件逆向工程框架，还处理流行的格式和任意二进制文件，具有广泛的命令行工具集.
- [Trommel](https://github.com/CERTCC/trommel) -在提取的固件映像中搜索有趣的文件和信息.

### Extraction Tools

- [Binwalk](https://github.com/ReFirmLabs/binwalk) -利用雕刻方法提取任意文件.
- [FACT Extractor](https://github.com/fkie-cad/fact_extractor) -自动检测容器格式并执行相应的提取工具.
- [Firmware Mod Kit](https://github.com/rampageX/firmware-mod-kit/wiki) -用于多种容器格式的提取工具.
- [The SRecord package](http://srecord.sourceforge.net/) -用于处理EPROM文件的工具集合（可以转换许多二进制格式）.

### Support Tools

- [JTAGenum](https://github.com/cyphunk/JTAGenum) -将JTAG功能添加到Arduino.
- [OpenOCD](http://openocd.org/) -免费和开放的片上调试，系统内编程和边界扫描测试.


## Hardware Tools

- [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) -检测硬件调试端口并与之交互 [UART](https://en.wikipedia.org/wiki/Universal_asynchronous_receiver-transmitter) 和 [JTAG](https://en.wikipedia.org/wiki/JTAG).
- [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) -检测硬件调试端口并与之交互，例如UART和JTAG.
- [JTAGULATOR](http://www.grandideastudio.com/jtagulator/) -快速检测JTAG引脚排列.
- [Saleae](https://www.saleae.com/) -易于使用的逻辑分析仪，支持许多协议：euro:.
- [Ikalogic](https://www.ikalogic.com/pages/logic-analyzer-sp-series-sp209) -替代Saleae逻辑分析仪：euro:.
- [HydraBus](https://hydrabus.com/hydrabus-1-0-specifications/) -类似于BusPirate的开源多工具硬件，但具有NFC功能.
- [ChipWhisperer](https://newae.com/tools/chipwhisperer/) -检测故障/侧通道攻击.
- [Glasgow](https://github.com/GlasgowEmbedded/Glasgow) -用于探索和调试不同数字接口的工具.
- [J-Link](https://www.segger.com/products/debug-probes/j-link/models/model-overview/) -J-Link提供了USB供电的JTAG调试探针，用于多个不同的CPU内核：euro:.


## Books

-2020年，贾斯珀·凡·乌登伯格（Jasper van Woudenberg），科林·奥弗林（Colin O&#39;Flynn）： [The Hardware Hacking Handbook: Breaking Embedded Security with Hardware Attacks](https://www.amazon.com/Hardware-Hacking-Handbook-Breaking-Embedded-ebook/dp/B077WZBFYL)
-2019年，Yago Hansen： [The Hacker's Hardware Toolkit: The best collection of hardware gadgets for Red Team hackers, Pentesters and security researchers](https://www.amazon.com/Hackers-Hardware-Toolkit-collection-researchers/dp/1099209463)
-2019，阿蒂亚·古普塔（Aditya Gupta）： [The IoT Hacker's Handbook: A Practical Guide to Hacking the Internet of Things](https://www.apress.com/us/book/9781484242995)
-2018年，马克·斯沃鲁普·蒂拉尼普（Mark Swarup Tehranipoor）： [Hardware Security: A Hands-on Learning Approach](https://www.elsevier.com/books/hardware-security/bhunia/978-0-12-812477-2)
-2017年，阿蒂亚·古普塔（Aditya Gupta），亚伦·古兹曼（Aaron Guzman）： [IoT Penetration Testing Cookbook](https://www.packtpub.com/networking-and-servers/iot-penetration-testing-cookbook)  
-2017年，黄宏伟： [The Hardware Hacker: Adventures in Making and Breaking Hardware](https://nostarch.com/hardwarehackerpaperback)
-2016年，克雷格·史密斯（Craig Smith）： [The Car Hacker's Handbook: A Guide for the Penetration Tester](https://nostarch.com/carhacking)
-2015年，Nitesh Dhanjan： [Abusing the Internet of Things: Blackouts, Freakouts, and Stakeouts](https://shop.oreilly.com/product/0636920033547.do)
-2014年，Debdeep Mukhopadhyay： [Hardware Security: Design, Threats, and Safeguards](https://www.taylorfrancis.com/books/9780429066900)
-2014年，杰克·甘斯勒（Jack Ganssle）： [The Firmware Handbook (Embedded Technology)](https://www.elsevier.com/books/the-firmware-handbook/ganssle/978-0-7506-7606-9)
-2013年，黄宏伟： [Hacking the XBOX](https://nostarch.com/xboxfree)



## Research Papers
<!--lint ignore match-punctuation-->
-2018年，Muench等人： [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices](http://www.eurecom.fr/en/publication/5417/download/sec-publi-5417.pdf)
-  2017年，欧米拉等人 [Embedded Device Vulnerability Analysis Case Study Using Trommel](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=509271)
-2017年，Jacob等： [How to Break Secure Boot on FPGA SoCs through Malicious Hardware](https://eprint.iacr.org/2017/625.pdf)
-2017年，Costin等人： [Towards Automated Classification of Firmware Images and Identification of Embedded Devices](http://s3.eurecom.fr/docs/ifip17_costin.pdf)
-2016年，Kammerstetter等： [Embedded Security Testing with Peripheral Device Caching and Runtime Program State Approximation](http://www.seclab.tuwien.ac.at/papers/kammerstetter_secuware2016_peripheralCache.pdf)
-2016年Chen等： [Towards Automated Dynamic Analysis for Linux-based Embedded Firmware](https://www.dcddcc.com/docs/2016_paper_firmadyne.pdf)
-2016年，Costin等人： [Automated Dynamic Firmware Analysis at Scale: A Case Study on Embedded Web Interfaces](http://s3.eurecom.fr/docs/asiaccs16_costin.pdf)
-2015年，Shoshitaishvili等人：[Firmalice - Automatic Detection of Authentication Bypass Vulnerabilities in Binary Firmware](https://seclab.cs.ucsb.edu/media/uploads/papers/firmalice.pdf)
-2015年，Papp等： [Embedded Systems Security: Threats, Vulnerabilities, and Attack Taxonomy](http://www.cse.psu.edu/~pdm12/cse597g-f15/readings/cse597g-embedded_systems.pdf)
2014年，Zaddach等人： [Avatar: A Framework to Support Dynamic Security Analysis of Embedded Systems' Firmwares](http://www.eurecom.fr/en/publication/4158/download/rs-publi-4158.pdf)
2014年，Alimi等人： [Analysis of embedded applications by evolutionary fuzzing](http://ieeexplore.ieee.org/document/6903734/)
-2014年，Costin等人：[嵌入式固件安全性的大规模分析
s](http://www.s3.eurecom.fr/docs/usenixsec14_costin.pdf)
-2013年，戴维森（Davidson）等人： [FIE on Firmware: Finding Vulnerabilities in Embedded Systems using Symbolic Execution](https://www.usenix.org/system/files/conference/usenixsecurity13/sec13-paper_davidson.pdf)

## Case Studies
<!--lint ignore no-repeat-punctuation-->
- [Binary Hardening in IoT products](https://cyber-itl.org/2019/08/26/iot-data-writeup.html)
- [Deadly Sins Of Development](https://youtu.be/nXyglaY9N9w) -会议演讲，介绍了一些关于真实不良实现的现实世界示例：tv:.
- [Hacking the DSP-W215, Again](http://www.devttys0.com/2014/05/hacking-the-dspw215-again/)
- [Multiple vulnerabilities found in the D-link DWR-932B](https://pierrekim.github.io/blog/2016-09-28-dlink-dwr-932b-lte-routers-vulnerabilities.html)
- [Pwning the Dlink 850L routers and abusing the MyDlink Cloud protocol](https://pierrekim.github.io/blog/2017-09-08-dlink-850l-mydlink-cloud-0days-vulnerabilities.html)
- [PWN Xerox Printers (...again)](https://www.fkie.fraunhofer.de/content/dam/fkie/de/documents/xerox_phaser_6700_white_paper.pdf)


## Free Training

- [Hardware Hacking 101](https://github.com/rdomanski/hardware_hacking/tree/master/my_talks/Hardware_Hacking_101) -研讨会@ BSides慕尼黑2019.
- [IoTGoat](https://github.com/scriptingxss/IoTGoat) -IoTGoat是基于OpenWrt的故意不安全的固件.
- [Rhme-2017/2018](https://github.com/Riscure/Rhme-2017) -Riscure Hack Me 3嵌入式硬件CTF 2017-2018.
- [Rhme-2016](https://github.com/Riscure/Rhme-2016) -Riscure Hack me 2是低级硬件CTF挑战.
- [Rhme-2015](https://github.com/Riscure/RHme-2015) -首先风险Hack me硬件CTF挑战.
- [Embedded Security CTF](https://microcorruption.com) -微腐败：嵌入式安全CTF.


## Websites

- [OWASP Embedded Application Security Project](https://www.owasp.org/index.php/OWASP_Embedded_Application_Security) -开发最佳做法以及硬件和软件工具列表.
- [OWASP Internet of Things Project](https://www.owasp.org/index.php/OWASP_Internet_of_Things_Project) -物联网常见漏洞和攻击面. 
- [Hacking Printers Wiki](http://hacking-printers.net/wiki/index.php/Main_Page)
- [Router Passwords](https://www.routerpasswords.com) -按制造商排序的默认登录凭据数据库.

## Conferences
会议重点讨论嵌入式和/或物联网安全.

- [Hardwear.io](https://hardwear.io/) -9月，海牙.
- [Hardwear.io USA](https://hardwear.io/) -6月，圣克拉拉. 

## Contribute

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/fkie-cad/awesome-embedded-and-iot-security/blob/master/contributing.md) 第一.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，Fraunhofer FKIE放弃了所有版权和
相关或邻接权.
