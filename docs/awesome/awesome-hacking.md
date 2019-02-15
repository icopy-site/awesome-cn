## Awesome Hacking [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 精彩黑客的精选列表.  灵感来自 [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning/)

如果您想参与此列表（请执行），请发送拉取请求或与我联系 [@carpedm20](https://twitter.com/carpedm20)

有关可供下载的免费黑客书籍列表，请转到 [here](https://github.com/Hack-with-Github/Free-Security-eBooks)


## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [System](#system)
    - [Tutorials](#tutorials)
    - [Tools](#tools)
    - [Docker](#docker-images-for-penetration-testing--security)
    - [General](#general)
- [Reverse Engineering](#reverse-engineering)
    - [Tutorials](#tutorials-1)
    - [Tools](#tools-1)
    - [General](#general-1)
- [Web](#web)
    - [Tools](#tools-2)
- [Network](#network)
    - [Tools](#tools-3)
- [Forensic](#forensic)
    - [Tools](#tools-4)
- [Cryptography](#cryptography)
    - [Tools](#tools-5)
- [Wargame](#wargame)
    - [System](#system-1)
    - [Reverse Engineering](#reverse-engineering-1)
    - [Web](#web-1)
    - [Cryptography](#cryptography-1)
    - [Bug bounty](#bug-bounty)
- [CTF](#ctf)
    - [Competition](#competition)
    - [General](#general-2)
- [OS](#os)
    - [Online resources](#online-resources)
- [ETC](#etc)

<!-- /MarkdownTOC -->

## System

## Tutorials
 * [Corelan Team's Exploit writing tutorial](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)
 * [Exploit Writing Tutorials for Pentesters](http://www.punter-infosec.com/exploit-writing-tutorials-for-pentesters/)
 * [Understanding the basics of Linux Binary Exploitation](https://github.com/r0hi7/BinExp)

## Tools
 * [Metasploit](https://github.com/rapid7/metasploit-framework) 计算机安全项目，提供有关安全漏洞的信息，并有助于渗透测试和IDS签名开发.
 * [mimikatz](https://github.com/gentilkiwi/mimikatz) - 一个与Windows安全性相关的小工具

### Docker Images for Penetration Testing & Security
 *`docker pull kalilinux / kali-linux-docker` [official Kali Linux](https://hub.docker.com/r/kalilinux/kali-linux-docker/)
 *`docker pull owasp / zap2docker-stable`  -  [official OWASP ZAP](https://github.com/zaproxy/zaproxy)
 *`docker pull wpscanteam / wpscan`  -  [official WPScan](https://hub.docker.com/r/wpscanteam/wpscan/)
 *`docker pull pandrew / metasploit`  -  [docker-metasploit](https://hub.docker.com/r/pandrew/metasploit/)
 *`docker pull citizenstig / dvwa`  -  [Damn Vulnerable Web Application (DVWA)](https://hub.docker.com/r/citizenstig/dvwa/)
 *`docker pull wpscanteam / vulnerabilitywordpress`  -  [Vulnerable WordPress Installation](https://hub.docker.com/r/wpscanteam/vulnerablewordpress/)
 *`docker pull hmlio / vaas-cve-2014-6271`  -  [Vulnerability as a service: Shellshock](https://hub.docker.com/r/hmlio/vaas-cve-2014-6271/)
 *`docker pull hmlio / vaas-cve-2014-0160`  -  [Vulnerability as a service: Heartbleed](https://hub.docker.com/r/hmlio/vaas-cve-2014-0160/)
 *`docker pull opendns / security-ninjas`  -  [Security Ninjas](https://hub.docker.com/r/opendns/security-ninjas/)
 *`docker pull usertaken / archlinux-pentest-lxde`  -  [Arch Linux Penetration Tester](https://hub.docker.com/r/usertaken/archlinux-pentest-lxde/)
 *`docker pull diogomonica / docker-bench-security`  -  [Docker Bench for Security](https://hub.docker.com/r/diogomonica/docker-bench-security/)
 *`docker pull ismisepaul / securityshepherd`  -  [OWASP Security Shepherd](https://hub.docker.com/r/ismisepaul/securityshepherd/)
 *`docker pull danmx / docker-owasp-webgoat`  -  [OWASP WebGoat Project docker image](https://hub.docker.com/r/danmx/docker-owasp-webgoat/)
 *`docker-compose build &amp;&amp; docker-compose up`  -  [OWASP NodeGoat](https://github.com/owasp/nodegoat#option-3---run-nodegoat-on-docker)
 *`docker pull citizenstig / nowasp`  -  [OWASP Mutillidae II Web Pen-Test Practice Application](https://hub.docker.com/r/citizenstig/nowasp/)
 *`docker pull bkimminich / juice-shop`  -  [OWASP Juice Shop](https://github.com/bkimminich/juice-shop#docker-container--)

## General
 * [Exploit database](https://www.exploit-db.com/) - 漏洞和易受攻击软件的终极存档


## Reverse Engineering

## Tutorials
* [Lenas Reversing for Newbies](https://tuts4you.com/download.php?list.17)
* [Malware Analysis Tutorials: a Reverse Engineering Approach](http://fumalwareanalysis.blogspot.kr/p/malware-analysis-tutorials-reverse.html)

## Tools
 * [nudge4j](https://github.com/lorenzoongithub/nudge4j) - 让浏览器与JVM通信的Java工具
 * [IDA](https://www.hex-rays.com/products/ida/) -  IDA是Windows，Linux或Mac OS X托管的多处理器反汇编程序和调试程序
 * [OllyDbg](http://www.ollydbg.de/) - 用于Windows的32位汇编程序级别分析调试程序
 * [x64dbg](http://x64dbg.com/) - 适用于Windows的开源x64 / x32调试器
 * [dex2jar](https://github.com/pxb1988/dex2jar) - 使用Android .dex和Java .class文件的工具
 * [JD-GUI](http://jd.benow.ca/) - 一个独立的图形实用程序，显示“.class”文件的Java源代码
 * [procyon](https://bitbucket.org/mstrobel/procyon/wiki/Java%20Decompiler) - 一个现代的开源Java反编译器
 * [androguard](https://code.google.com/p/androguard/) -  Android应用程序的逆向工程，恶意软件和良好软件分析
 * [JAD](http://varaneckas.com/jad/) -  JAD Java Decompiler（闭源，无保留）
 * [dotPeek](https://www.jetbrains.com/decompiler/) - a free-of-charge .NET decompiler from JetBrains
 * [ILSpy](https://github.com/icsharpcode/ILSpy/) - 一个开源.NET程序集浏览器和反编译器
 * [dnSpy](https://github.com/0xd4d/dnSpy) -  .NET汇编编辑器，反编译器和调试器
 * [de4dot](https://github.com/0xd4d/de4dot) -  .NET反混淆器和解包器.
 * [antinet](https://github.com/0xd4d/antinet) -  .NET反托管调试器和反剖析器代码
 * [UPX](http://upx.sourceforge.net/) -  eXecutables的终极包装工具
 * [radare2](https://github.com/radare/radare2) - 便携式倒车架
 * [plasma](https://github.com/joelpx/plasma)   - 用于x86 / ARM / MIPS的交互式反汇编程序.  使用彩色语法代码生成缩进的伪代码.
 * [Hopper](https://www.hopperapp.com) - 适用于32/64位Windows / Mac / Linux / iOS可执行文件的OS X和Linux反汇编程序/反编译程序.
 * [ScratchABit](https://github.com/pfalcon/ScratchABit) - 使用IDAPython兼容的插件API轻松重定向和可破解的交互式反汇编程序



## General
 * [Open Malware](http://www.offensivecomputing.net/)


## Web

## Tools
 * [sqlmap](https://github.com/sqlmapproject/sqlmap) - 自动SQL注入和数据库接管工具
 * [NoSQLMap](https://github.com/codingo/NoSQLMap) - 自动NoSQL数据库枚举和Web应用程序开发工具.
 * [tools.web-max.ca](http://tools.web-max.ca/encode_decode.php) -  base64 base85 md4,5 hash，sha1 hash编码/解码
 * [VHostScan](https://github.com/codingo/VHostScan) - 执行反向查找的虚拟主机扫描程序，可与数据透视工具一起使用，检测全能方案，别名和动态默认页面.
 * [SubFinder](https://github.com/subfinder/subfinder) -  SubFinder是一个子域发现工具，可使用被动在线源为任何目标发现有效的子域.

## Network

## Tools
 * [Wireshark](https://www.wireshark.org/) - 免费的开源数据包分析器
 * [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - 网络取证分析工具（NFAT）
 * [tcpdump](http://www.tcpdump.org/)   - 功能强大的命令行数据包分析器;  和libpcap，一个用于网络流量捕获的可移植C / C ++库
 * [Paros](http://sourceforge.net/projects/paros/) - 用于评估Web应用程序漏洞的基于Java的HTTP / HTTPS代理
 * [pig](https://github.com/rafael-santiago/pig) -  Linux数据包制作工具
 * [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) -  Zed攻击代理（ZAP）是一种易于使用的集成渗透测试工具，用于查找Web应用程序中的漏洞
 * [mitmproxy](https://mitmproxy.org/) - 具有控制台界面的HTTP交互式，具有SSL功能的中间人工代理
 * [mitmsocks4j](https://github.com/Akdeniz/mitmsocks4j) - 用于Java的中间人SOCKS代理
 * [ssh-mitm](https://github.com/jtesta/ssh-mitm) -  SSH / SFTP中间人工具，用于记录交互式会话和密码.
 * [nmap](https://nmap.org/) -  Nmap（Network Mapper）是一种安全扫描程序
 * [Aircrack-ng](http://www.aircrack-ng.org/) -  802.11 WEP和WPA-PSK密钥破解程序
 * [Charles Proxy](https://charlesproxy.com) - 跨平台GUI Web调试代理，用于查看截获的HTTP和HTTPS / SSL实时流量
 * [Nipe](https://github.com/GouveaHeitor/nipe) - 使Tor网络成为默认网关的脚本.
 * [Habu](https://github.com/portantier/habu) -  Python网络黑客工具包
 * [Wifi Jammer](https://n0where.net/wifijammer/) - 免费程序，以阻止范围内的所有WiFi客户端
 * [Firesheep](https://codebutler.github.io/firesheep/) -  HTTP会话劫持攻击的免费程序.
 * [Scapy](https://github.com/secdev/scapy) - 用于低级数据包创建和操作的Python工具和库
 * [Amass](https://github.com/OWASP/Amass) - 深入的子域枚举工具，可执行抓取，递归暴力破解，抓取Web存档，更改名称和反向DNS扫描


## Forensic

## Tools
 * [Autopsy](http://www.sleuthkit.org/autopsy/) - 数字取证平台和图形界面 [The Sleuth Kit](http://www.sleuthkit.org/sleuthkit/index.php) 和其他数字取证工具
 * [sleuthkit](https://github.com/sleuthkit/sleuthkit) - 图书馆和命令行数字取证工具的集合
 * [EnCase](https://www.guidancesoftware.com/products/Pages/encase-forensic/overview.aspx) -  Guidance Software提供的一套数字调查产品中的共享技术
 * [malzilla](http://malzilla.sourceforge.net/) - 恶意软件狩猎工具
 * [PEview](http://wjradburn.com/software/) - 查看32位可移植可执行文件（PE）和组件对象文件格式（COFF）文件的结构和内容的快速简便方法
 * [HxD](http://mh-nexus.de/en/hxd/) - 十六进制编辑器，除原始磁盘编辑和主存储器（RAM）修改外，还可处理任何大小的文件
 * [WinHex](http://www.winhex.com/winhex/) - 十六进制编辑器，有助于计算机取证，数据恢复，低级数据处理和IT安全领域
 * [BinText](http://www.mcafee.com/kr/downloads/free-tools/bintext.aspx) - 一个小型，非常快速且功能强大的文本提取器，对程序员来说是特别感兴趣


## Cryptography

### Tools
 * [xortool](https://github.com/hellman/xortool) - 分析多字节XOR密码的工具
 * [John the Ripper](http://www.openwall.com/john/) - 快速密码破解程序
 * [Aircrack](http://www.aircrack-ng.org/) -  Aircrack是802.11 WEP和WPA-PSK密钥破解程序.


## Wargame

## System
 * [OverTheWire - Semtex](http://overthewire.org/wargames/semtex/)
 * [OverTheWire - Vortex](http://overthewire.org/wargames/vortex/)
 * [OverTheWire - Drifter](http://overthewire.org/wargames/drifter/)
 * [pwnable.kr](http://pwnable.kr/) - 提供有关系统安全性的各种pwn挑战
 * [Exploit Exercises - Nebula](https://exploit-exercises.com/nebula/)
 * [SmashTheStack](http://smashthestack.org/)

## Reverse Engineering
 * [Reversing.kr](http://www.reversing.kr/) - 该网站测试您的破解和反向代码工程的能力
 * [CodeEngn](http://codeengn.com/challenges/) - （韩国）
 * [simples.kr](http://simples.kr/) - （韩国）
 * [Crackmes.de](http://crackmes.de/) - 世界上第一个也是最大的社区网站，用于破解和逆转.

## Web
 * [Hack This Site!](https://www.hackthissite.org/) - 为黑客提供免费，安全和合法的培训基地，以测试和扩展他们的黑客技能
 * [Hack The Box](https://www.hackthebox.eu) - 在各种不同系统中执行pentesting的免费网站.
 * [Webhacking.kr](http://webhacking.kr/)
 * [0xf.at](https://0xf.at/) - 没有登录或广告的网站，您可以在其中解决密码谜语（所谓的hackits）.
 * [Gruyere](https://google-gruyere.appspot.com/)
 * [Others](https://www.owasp.org/index.php/OWASP_Vulnerable_Web_Applications_Directory_Project#tab=On-Line_apps)

## Cryptography
 * [OverTheWire - Krypton](http://overthewire.org/wargames/krypton/)

## Bug bounty
  * [Awesome bug bounty resources by EdOverflow](https://github.com/EdOverflow/bugbounty-cheatsheet)

## CTF

## Competition
 * [DEF CON](https://legitbs.net/)
 * [CSAW CTF](https://ctf.isis.poly.edu/)
 * [hack.lu CTF](http://hack.lu/)
 * [Pliad CTF](http://www.plaidctf.com/)
 * [RuCTFe](http://ructf.org/e/)
 * [Ghost in the Shellcode](http://ghostintheshellcode.com/)
 * [PHD CTF](http://www.phdays.com/)
 * [SECUINSIDE CTF](http://secuinside.com/)
 * [Codegate CTF](http://ctf.codegate.org/html/Main.html?lang=eng)
 * [Boston Key Party CTF](http://bostonkeyparty.net/)
 * [ZeroDays CTF](https://zerodays.ie/)
 * [Insomni’hack](https://insomnihack.ch/)
 * [Picp CTF](https://picoctf.com/) 
 * [prompt(1) to win](http://prompt.ml/) -  XSS Challeges

## General
 * [Hack+](http://hack.plus) - 智能网络机器人，可获取最新的InfoSec内容.
 * [CTFtime.org](https://ctftime.org/) - 所有关于CTF（夺旗）
 * [WeChall](http://www.wechall.net/)
 * [CTF archives (shell-storm)](http://shell-storm.org/repo/CTF/)
 * [Rookit Arsenal](https://amzn.com/144962636X) -  OS RE和rootkit开发
 * [Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) - 收集用于测试的备忘单
 * [Movies For Hackers](https://github.com/k4m4/movies-for-hackers) - 每个黑客和赛博朋克必须观看的精选电影列表.

## OS

## Online resources
 * [Security related Operating Systems @ Rawsec](http://rawsec.ml/en/security-related-os/) - 完整的安全相关操作系统列表
 * [Best Linux Penetration Testing Distributions @ CyberPunk](https://n0where.net/best-linux-penetration-testing-distributions/) - 主要渗透测试分布的描述
 * [Security @ Distrowatch](http://distrowatch.com/search.php?category=Security) - 致力于讨论，审查和跟上开源操作系统的网站

## ETC
 * [SecTools](http://sectools.org/) - 排名前125的网络安全工具
