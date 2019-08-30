<div class="github-widget" data-repo="apsdehal/awesome-ctf"></div>
## Awesome CTF [![Build Status](https://travis-ci.org/apsdehal/awesome-ctf.svg?branch=master)](https://travis-ci.org/apsdehal/awesome-ctf) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的清单 [Capture The Flag](https://en.wikipedia.org/wiki/Capture_the_flag#Computer_security)  （CTF）框架，库，资源，软件和教程.  此列表旨在帮助初学者和经验丰富的CTF玩家在一个地方找到与CTF相关的所有内容.

### Contributing

请快速浏览一下 [contribution guidelines](https://github.com/apsdehal/ctf-tools/blob/master/CONTRIBUTING.md) 第一.

#### _If you know a tool that isn't present here, feel free to open a pull request._

### Why?

 构建ctf中使用的工具集合需要时间并记住它们.  这个回购有助于将所有这些分散的工具保存在一个地方.





## Create

*用于创建CTF挑战的工具*

- [Kali Linux CTF Blueprints](https://doc.lagout.org/security/Packt.Kali.Linux.CTF.Blueprints.Jul.2014.ISBN.1783985984.pdf) - 有关构建，测试和自定义自己捕获旗帜挑战的在线书籍.


## Forensics

*用于创建取证挑战的工具*

- [Dnscat](https://wiki.skullsecurity.org/Dnscat) - 通过DNS主持通信
- [Registry Dumper](http://www.kahusecurity.com/downloads/RegistryDumper_v0.2.7z) - 转储您的注册表

## Platforms

*可用于托管CTF的项目*

- [CTFd](https://github.com/isislab/CTFd) - 从纽约大学Tandon的ISISLab主持危险风格CTF的平台
- [FBCTF](https://github.com/facebook/fbctf) - 举办Facebook旗帜比赛的平台
- [Haaukins](https://github.com/aau-network-security/haaukins)- 用于安全教育的高度可访问和自动化虚拟化平台
- [HackTheArch](https://github.com/mcpa-stlouis/hack-the-arch) -  CTF评分平台
- [Mellivora](https://github.com/Nakiami/mellivora) - 用PHP编写的CTF引擎
- [NightShade](https://github.com/UnrealAkama/NightShade) - 一个简单的安全CTF框架
- [OpenCTF](https://github.com/easyctf/openctf)   -  CTF在一个盒子里.  需要最少的设置
- [PicoCTF Platform 2](https://github.com/picoCTF/picoCTF-Platform-2) -  picoCTF 2014的通用版本，可轻松适应主持CTF或编程竞赛.
- [PyChallFactory](https://github.com/pdautry/py_chall_factory) - 创建/管理/打包危险的CTF挑战的小框架
- [RootTheBox](https://github.com/moloch--/RootTheBox) - 黑客游戏（CTF记分牌和游戏管理器）
- [Scorebot](https://github.com/legitbs/scorebot) -  Legitbs（Defcon）的CTF平台
- [SecGen](https://github.com/cliffe/SecGen)   - 安全场景生成器.  创建随机易受攻击的虚拟机


## Steganography

*用于制造隐秘挑战的工具*

检查隐写术的解决部分.


## Web

*用于创建Web挑战的工具*

* JavaScript Obfustcators *

- [Metasploit JavaScript Obfuscator](https://github.com/rapid7/metasploit-framework/wiki/How-to-obfuscate-JavaScript-in-Metasploit)
- [Uglify](http://marijnhaverbeke.nl//uglifyjs)


## Solve

*用于解决CTF挑战的工具*

## Attacks

*Tools used for performing various kinds of attacks*

- [Bettercap](https://github.com/bettercap/bettercap) - 执行MITM（中间人）攻击的框架.
- [Layer 2 attacks](https://github.com/tomac/yersinia) - 攻击第2层上的各种协议

## Crypto

*用于解决加密挑战的工具*

- [FeatherDuster](https://github.com/nccgroup/featherduster) - 自动化模块化密码分析工具
- [Hash Extender](https://github.com/iagox86/hash_extender) - 用于执行散列长度扩展攻击的实用工具
- [PkCrack](https://www.unix-ag.uni-kl.de/~conrad/krypto/pkcrack.html) - 破解PkZip加密的工具
- [RSACTFTool](https://github.com/Ganapati/RsaCtfTool) - 用于恢复具有各种攻击的RSA私钥的工具
- [RSATool](https://github.com/ius/rsatool) - 生成具有p和q知识的私钥
- [XORTool](https://github.com/hellman/xortool) - 分析多字节xor密码的工具

## Bruteforcers

*用于各种强制执行的工具（密码等）*

- [Hashcat](https://hashcat.net/hashcat/) - 密码破解者
- [John The Jumbo](https://github.com/magnumripper/JohnTheRipper) -  John the Ripper的社区增强版
- [John The Ripper](http://www.openwall.com/john/) - 密码破解者
- [Nozzlr](https://github.com/intrd/nozzlr) -  Nozzlr是一个强大的框架，模块化和脚本友好.
- [Ophcrack](http://ophcrack.sourceforge.net/) - 基于彩虹表的Windows密码破解程序.
- [Patator](https://github.com/lanjelot/patator) -  Patator是一款多功能的粗暴式设计，采用模块化设计.

## Exploits

*用于解决漏洞利用挑战的工具*

- [DLLInjector](https://github.com/OpenSecurityResearch/dllinjector) - 在进程中注入dll
- [libformatstr](https://github.com/hellman/libformatstr) - 简化格式字符串利用.
- [Metasploit](http://www.metasploit.com/) - 渗透测试软件
- [one_gadget](https://github.com/david942j/one_gadget) - 找到一个小工具`execve（&#39;/ bin / sh&#39;，NULL，NULL）`调用的工具
  - `gem install one_gadget`
- [Pwntools](https://github.com/Gallopsled/pwntools) - 用于编写漏洞的CTF框架
- [Qira](https://github.com/BinaryAnalysisPlatform/qira) -  QEMU交互式运行时分析器
- [ROP Gadget](https://github.com/JonathanSalwan/ROPgadget) -  ROP开发框架
- [V0lt](https://github.com/P1kachu/v0lt) - 安全CTF工具包

## Forensics

*用于解决取证挑战的工具*

- [Aircrack-Ng](http://www.aircrack-ng.org/) - 破解802.11 WEP和WPA-PSK密钥
  - `apt-get install aircrack-ng`
- [Audacity](http://sourceforge.net/projects/audacity/) - 分析声音文件（mp3，m4a，等等）
  - `apt-get install audacity`
- [Bkhive and Samdump2](http://sourceforge.net/projects/ophcrack/files/samdump2/) - 转储SYSTEM和SAM文件
  - `apt-get install samdump2 bkhive`
- [CFF Explorer](http://www.ntcore.com/exsuite.php) -  PE编辑
- [Creddump](https://github.com/moyix/creddump) - 转储窗口凭据
- [DVCS Ripper](https://github.com/kost/dvcs-ripper) - 翻录Web可访问（分布式）版本控制系统
- [Exif Tool](http://www.sno.phy.queensu.ca/~phil/exiftool/) - 读取，写入和编辑文件元数据
- [Extundelete](http://extundelete.sourceforge.net/) - 用于从可安装映像恢复丢失的数据
- [Fibratus](https://github.com/rabbitstack/fibratus) - 用于探索和跟踪Windows内核的工具
- [Foremost](http://foremost.sourceforge.net/) - 使用标题提取特定类型的文件
  - `apt-get install foremost`
- [Fsck.ext4](http://linux.die.net/man/8/fsck.ext3) - 用于修复损坏的文件系统
- [Malzilla](http://malzilla.sourceforge.net/) - 恶意软件狩猎工具
- [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - 网络取证分析工具
- [PDF Streams Inflater](http://malzilla.sourceforge.net/downloads.html) - 查找并提取以PDF文件压缩的​​zlib文件
- [ResourcesExtract](http://www.nirsoft.net/utils/resources_extract.html) - 从exes中提取各种文件类型
- [Shellbags](https://github.com/williballenthin/shellbags) - 调查NT \ _USER.dat文件
- [UsbForensics](http://www.forensicswiki.org/wiki/USB_History_Viewing) - 包含许多用于usb取证的工具
- [Volatility](https://github.com/volatilityfoundation/volatility) - 调查内存转储


*注册表查看器*
- [RegistryViewer](http://www.gaijin.at/en/getitpage.php?id=regview) - 用于查看Windows注册表
- [Windows Registry Viewers](http://www.forensicswiki.org/wiki/Windows_Registry) - 更多注册表查看器


## Networking

*用于解决网络挑战的工具*

- [Bro](https://www.bro.org/) - 开源网络安全监视器.
- [Masscan](https://github.com/robertdavidgraham/masscan) -  Mass IP端口扫描器，TCP端口扫描器.
- [Monit](https://linoxide.com/monitoring-2/monit-linux/) - 用于检查网络上主机（以及其他非网络活动）的linux工具. 
- [Nipe](https://github.com/GouveaHeitor/nipe) -  Nipe是一个使Tor Network成为默认网关的脚本.
- [Nmap](https://nmap.org/) - 用于网络发现和安全审核的开源实用程序.
- [Wireshark](https://www.wireshark.org/) - 分析网络转储.
  - `apt-get install wireshark`
- [Zmap](https://zmap.io/) - 开源网络扫描仪.


## Reversing

*用于解决逆转挑战的工具*

- [Androguard](https://github.com/androguard/androguard) - 反向设计Android应用程序
- [Angr](https://github.com/angr/angr) - 平台无关的二进制分析框架
- [Apk2Gold](https://github.com/lxdvs/apk2gold) - 另一个Android反编译器
- [ApkTool](http://ibotpeaches.github.io/Apktool/) -  Android Decompiler
- [Barf](https://github.com/programa-stic/barf-project) - 二元分析和逆向工程框架
- [Binary Ninja](https://binary.ninja/) - 二进制分析框架
- [BinUtils](http://www.gnu.org/software/binutils/binutils.html) - 二进制工具的集合
- [BinWalk](https://github.com/devttys0/binwalk) - 分析，反向工程和提取固件映像.
- [Boomerang](https://github.com/nemerle/boomerang) - 将x86二进制文件反编译为C.
- [ctf_import](https://github.com/docileninja/ctf_import) - 从剥离的二进制跨平台运行基本功能
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) -  cwe_checker在二进制可执行文件中查找易受攻击的模式
- [Frida](https://github.com/frida/) - 动态代码注入
- [GDB](https://www.gnu.org/software/gdb/) -  GNU项目调试器
- [GEF](https://github.com/hugsy/gef) -  GDB插件
- [Ghidra](https://ghidra-sre.org/)   - 开源逆向工程工具套件.  与IDA Pro类似.
- [Hopper](http://www.hopperapp.com/) -  OSX和Linux的逆向工程工具（反汇编程序）
- [IDA Pro](https://www.hex-rays.com/products/ida/) - 最常用的Reversing软件
- [Jadx](https://github.com/skylot/jadx) - 反编译Android文件
- [Java Decompilers](http://www.javadecompilers.com) - 适用于Java和Android APK的在线反编译器
- [Krakatau](https://github.com/Storyyeller/Krakatau) -  Java反编译器和反汇编程序
- [Objection](https://github.com/sensepost/objection) - 运行时移动探索
- [PEDA](https://github.com/longld/peda) -  GDB插件（仅限python2.7）
- [Pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool) 英特尔的动态二进制仪器工具
- [Plasma](https://github.com/joelpx/plasma) -  x86 / ARM / MIPS的交互式反汇编程序，可以生成带有彩色语法的缩进伪代码.
- [Pwndbg](https://github.com/pwndbg/pwndbg) - 一个GDB插件，提供了一套实用程序，可以轻松地破解GDB. 
- [radare2](https://github.com/radare/radare2) - 便携式倒车架
- [Triton](https://github.com/JonathanSalwan/Triton/) - 动态二进制分析（DBA）框架
- [Uncompyle](https://github.com/gstarnberger/uncompyle) - 反编译Python 2.7二进制文件（.pyc）
- [WinDbg](http://www.windbg.org/) - 由Microsoft分发的Windows调试程序
- [Xocopy](http://reverse.lostrealm.com/tools/xocopy.html) - 可以使用execute复制可执行文件但没有读取权限的程序
- [Z3](https://github.com/Z3Prover/z3) - 微软研究院的一个定理证明者

* JavaScript反混淆器*

- [Detox](http://relentless-coding.org/projects/jsdetox/install) - 一个Javascript恶意软件分析工具
- [Revelo](http://www.kahusecurity.com/tools/Revelo_v0.6.zip) - 分析混淆的Javascript代码

* SWF分析仪*
- [RABCDAsm](https://github.com/CyberShadow/RABCDAsm) - 包括ActionScript 3汇编程序/反汇编程序的实用程序集合.
- [Swftools](http://www.swftools.org/) - 收集使用SWF文件的实用程序
- [Xxxswf](https://bitbucket.org/Alexander_Hanel/xxxswf) - 用于分析Flash文件的Python脚本.

## Services

*互联网上提供各种有用的服务*

- [CSWSH](http://ironwasp.org/cswsh.html) - 跨站点WebSocket劫持测试程序
- [Request Bin](http://requestb.in/) - 允许您检查对特定URL的http请求

## Steganography

*用于解决隐写术挑战的工具*

- [Convert](http://www.imagemagick.org/script/convert.php) - 转换图像黑白格式并应用过滤器
- [Exif](http://manpages.ubuntu.com/manpages/trusty/man1/exif.1.html) - 以JPEG文件显示EXIF信息
- [Exiftool](https://linux.die.net/man/1/exiftool) - 在文件中读取和写入元信息
- [Exiv2](http://www.exiv2.org/manpage.html) - 图像元数据操作工具
- [ImageMagick](http://www.imagemagick.org/script/index.php) - 用于处理图像的工具
- [Outguess](https://www.freebsd.org/cgi/man.cgi?query=outguess+&apropos=0&sektion=0&manpath=FreeBSD+Ports+5.1-RELEASE&format=html) - 通用隐写工具
- [Pngtools](http://www.stillhq.com/pngtools/) - 有关PNG的各种分析
  - `apt-get install pngtools`
- [SmartDeblur](https://github.com/Y-Vladimir/SmartDeblur) - 用于deblur和修复散焦图像
- [Steganabara](https://www.openhub.net/p/steganabara) - 用Java编写的用于隐写分析的工具
- [Stegbreak](https://linux.die.net/man/1/stegbreak) - 对JPG图像启动暴力字典攻击
- [StegCracker](https://github.com/Paradoxis/StegCracker) - 用于发现文件内隐藏数据的Steganography强力实用程序 
- [stegextract](https://github.com/evyatarmeged/stegextract) - 检测图像中的隐藏文件和文本 
- [Steghide](http://steghide.sourceforge.net/) - 隐藏各种图像中的数据
- [Stegsolve](http://www.caesum.com/handbook/Stegsolve.jar) - 对图像应用各种隐写技术
- [Zsteg](https://github.com/zed-0xff/zsteg/) -  PNG / BMP分析

## Web

*用于解决Web挑战的工具*

-  [BurpSuite]（） - 测试网站安全性的图形工具. 
- [Commix](https://github.com/commixproject/commix) - 自动化一体化操作系统命令注入和利用工具.
- [Hackbar](https://addons.mozilla.org/en-US/firefox/addon/hackbar/) -  Firefox插件，便于网络利用
- [OWASP ZAP](https://www.owasp.org/index.php/Projects/OWASP_Zed_Attack_Proxy_Project) - 拦截代理以重放，调试和模糊HTTP请求和响应
- [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) - 添加chrome以调试网络请求
- [Raccoon](https://github.com/evyatarmeged/Raccoon) - 用于侦察和漏洞扫描的高性能攻击性安全工具
- [SQLMap](https://github.com/sqlmapproject/sqlmap) - 自动SQL注入和数据库接管工具
- [W3af](https://github.com/andresriancho/w3af) -  Web应用程序攻击和审计框架.
- [XSSer](http://xsser.sourceforge.net/) - 自动XSS测试器


## Resources

*哪里可以找到CTF *

## Operating Systems

*渗透测试和安全实验室操作系统*

- [Android Tamer](https://androidtamer.com/) - 基于Debian
- [BackBox](https://backbox.org/) - 基于Ubuntu
- [BlackArch Linux](https://blackarch.org/) - 基于Arch Linux
- [Fedora Security Lab](https://labs.fedoraproject.org/security/) - 基于Fedora
- [Kali Linux](https://www.kali.org/) - 基于Debian
- [Parrot Security OS](https://www.parrotsec.org/) - 基于Debian
- [Pentoo](http://www.pentoo.ch/) - 基于Gentoo
- [URIX OS](http://urix.us/) - 基于openSUSE
- [Wifislax](http://www.wifislax.com/) - 基于Slackware

*恶意软件分析师和逆向工程*

- [Flare VM](https://github.com/fireeye/flare-vm/) - 基于Windows
- [REMnux](https://remnux.org/) - 基于Debian

## Starter Packs

*安装程序脚本的集合，有用的工具*

- [CTF Tools](https://github.com/zardus/ctf-tools) - 收集安装脚本以安装各种安全研究工具.
- [LazyKali](https://github.com/jlevitsk/lazykali) -  2016年刷新LazyKali，简化了工具和配置的安装.

## Tutorials

*教程学习如何玩CTF *

- [CTF Field Guide](https://trailofbits.github.io/ctf/) - 比特小径的实地指南
- [CTF Resources](http://ctfs.github.io/resources/) - 社区维护的入门指南
- [Damn Vulnerable Web Application](http://www.dvwa.co.uk/) PHP / MySQL Web应用程序非常容易受到攻击
- [How to Get Started in CTF](https://www.endgame.com/blog/how-get-started-ctf) -  Endgame的CTF初学者简短指南
- [MIPT CTF](https://github.com/xairy/mipt-ctf) -  CTF初学者的小课程（俄语）

## Wargames

*始终在线CTF *

- [Backdoor](https://backdoor.sdslabs.co/) -  SDSLabs的安全平台.
- [Crackmes](https://crackmes.one/) - 逆向工程挑战
- [Ctfs.me](http://ctfs.me) -  CTF一直以来
- [Exploit Exercises](https://exploit-exercises.com/) - 各种虚拟机，以学习各种计算机安全问题.
- [Gracker](http://gracker.org) - 具有缓慢学习曲线的二元挑战，以及每个级别的写作.
- [Hack The Box](https://www.hackthebox.eu) - 适用于所有类型的安全爱好者的每周CTF.
- [Hack This Site](https://www.hackthissite.org/) - 黑客训练场.
- [Hacking-Lab](https://hacking-lab.com/) - 道德黑客，计算机网络和安全挑战平台.
- [Hone Your Ninja Skills](https://honeyourskills.ninja/) -  Web挑战从基础挑战开始.
- [IO](http://io.netgarage.org/) - 二战挑战的战争游戏.
- [Microcorruption](https://microcorruption.com) - 嵌入式安全CTF
- [Over The Wire](http://overthewire.org/wargames/) - 由OvertheWire社区维护的战争游戏
- [Pwnable.kr](http://pwnable.kr/) -  Pwn Game
- [Pwnable.tw](https://pwnable.tw/) - 二元战争游戏
- [Pwnable.xyz](https://pwnable.xyz/) - 二元开发战争游戏
- [Reversin.kr](http://reversing.kr/) - 扭转挑战
- [Ringzer0Team](https://ringzer0team.com/) -  Ringzer0 Team Online CTF
- [Root-Me](https://www.root-me.org/) - 黑客和信息安全学习平台.
- [ROP Wargames](https://game.rop.sh/) -  ROP战争游戏
- [SmashTheStack](http://smashthestack.org/) -  SmashTheStack社区维护的各种战争游戏.
- [VulnHub](https://www.vulnhub.com/) - 基于VM，适用于数字安全，计算机应用和网络管理.
- [W3Challs](https://w3challs.com) - 渗透测试培训平台，提供各种类别的各种计算机挑战.
- [WebHacking](http://webhacking.kr) - 克服网络挑战.
- [WeChall](https://www.wechall.net/) - 始终在线挑战网站.
- [WTHack OnlineCTF](https://onlinectf.com) - 针对各级网络安全爱好者的CTF实践平台. 


*自托管的CTF *

- [Juice Shop CTF](https://github.com/bkimminich/juice-shop-ctf) - 用于托管CTF的脚本和工具 [OWASP Juice Shop](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project) 容易.

## Websites

*有关ctf的各种一般网站*

- [CTF Time](https://ctftime.org/) - 关于世界各地发生的CTF的一般信息
- [Reddit Security CTF](http://www.reddit.com/r/securityctf) -  Reddit CTF类别

## Wikis

*可用于学习CTF的各种Wiki *

- [Bamboofox](https://bamboofox.torchpad.com/) - 学习CTF的中国资源
- [ISIS Lab](https://github.com/isislab/Project-Ideas/wiki) -  Isis实验室的CTF Wiki
- [OpenToAll](http://wiki.opentoallctf.com/) - 向所有知识库开放

## Writeups Collections

* CTF写作集*

- [Captf](http://captf.com/) - 通过psifertex倾倒CTF挑战和材料
- [CTF write-ups (community)](https://github.com/ctfs/) - 由社区维护的CTF挑战+写作档案
- [CTFTime Scrapper](https://github.com/abdilahrf/CTFWriteupScrapper) - 从ctf时间中删除所有写入并组织首先读取的内容
- [pwntools writeups](https://github.com/Gallopsled/pwntools-write-ups) - 所有使用pwntools的CTF写作集合
- [Shell Storm](http://shell-storm.org/repo/CTF/) - 由Jonathan Salwan维护的CTF挑战档案
- [Smoke Leet Everyday](https://github.com/smokeleeteveryday/CTF_WRITEUPS) - 由SmokeLeetEveryday团队维护的CTF写作报告.


### LICENSE

CC0 :)
