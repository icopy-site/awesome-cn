<div class="github-widget" data-repo="sbilly/awesome-security"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Security

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

很棒的软件，库，文档，书籍，资源和有关安全性的一些不错的东西的集合.

受启发 [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python).

谢谢大家 [contributors](https://github.com/sbilly/awesome-security/graphs/contributors) ，您真棒，没有您就不可能！  目标是建立由社区驱动的非常知名资源的分类集合.


------

## Network

### Scanning / Pentesting

- [OpenVAS](http://www.openvas.org/) -OpenVAS是多种服务和工具的框架，可提供全面而强大的漏洞扫描和漏洞管理解决方案.
- [Metasploit Framework](https://github.com/rapid7/metasploit-framework)  -用于针对远程目标计算机开发和执行漏洞利用代码的工具.  其他重要的子项目包括操作码数据库，shellcode存档和相关研究.
- [Kali](https://www.kali.org/)  -Kali Linux是Debian衍生的Linux发行版，专门用于数字取证和渗透测试.  Kali Linux预装了许多渗透测试程序，包括nmap（端口扫描程序），Wireshark（数据包分析器），John Ripper（密码破解程序）和Aircrack-ng（用于渗透测试无线LAN的软件套件） .
- [pig](https://github.com/rafael-santiago/pig) -Linux数据包制作工具.
- [scapy](https://github.com/gpotter2/awesome-scapy) -Scapy：基于python的交互式数据包处理程序和库.
- [Pompem](https://github.com/rfunix/Pompem)  -Pompem是一个开放源代码工具，旨在自动搜索主要数据库中的漏洞利用程序.  用Python开发的系统具有高级搜索系统，因此可以促进渗透测试人员和道德黑客的工作.  在当前版本中，在数据库中执行搜索：Exploit-db，1337day，Packetstorm Security ...
- [Nmap](https://nmap.org) -Nmap是一个免费的开源实用程序，用于网络发现和安全审核.
- [Amass](https://github.com/caffix/amass) -Amass通过抓取最多数量的不同数据源，递归暴力破解，网络档案的爬网，排列和更改名称，反向DNS扫描和其他技术来执行DNS子域枚举.
- [Anevicon](https://github.com/rozgo/anevicon) -用Rust编写的最强大的基于UDP的负载生成器.
- [Finshir](https://github.com/isgasho/finshir) -用协程驱动的低速和慢速流量生成器，用Rust编写.
- [Legion](https://github.com/GoVanguard/legion) -开源半自动发现和侦察网络渗透测试框架.
- [Sublist3r](https://github.com/aboul3la/Sublist3r) -渗透测试人员的快速子域枚举工具

### Monitoring / Logging

- [justniffer](http://justniffer.sourceforge.net/) -Justniffer是一种网络协议分析器，可以捕获网络流量并以自定义方式生成日志，可以模拟Apache Web服务器日志文件，跟踪响应时间并从HTTP流量中提取所有“被拦截”的文件.
- [httpry](http://dumpsterventures.com/jason/httpry/)  -httpry是专门用于显示和记录HTTP流量的专用数据包嗅探器.  它并不是要自己执行分析，而是要捕获，解析和记录流量以供以后分析.  它可以实时运行，以显示解析后的流量，也可以将其记录为输出文件的守护进程.  它被编写为尽可能轻巧和灵活，以便可以轻松地适应不同的应用程序.
- [ngrep](http://ngrep.sourceforge.net/)  -ngrep致力于提供GNU grep的大多数通用功能，并将其应用于网络层.  ngrep是可识别pcap的工具，可让您指定扩展的正则或十六进制表达式以与数据包的数据有效载荷匹配.  目前，它可以通过以太网，PPP，SLIP，FDDI，令牌环和空接口识别IPv4 / 6，TCP，UDP，ICMPv4 / 6，IGMP和Raw，并以与更常见的数据包嗅探工具相同的方式理解BPF过滤器逻辑，例如作为tcpdump和snoop.
- [passivedns](https://github.com/gamelinux/passivedns)  -被动收集DNS记录的工具，以帮助事件处理，网络安全监视（NSM）和常规数字取证.  PassiveDNS会从接口嗅探流量或读取pcap文件，然后将DNS服务器答案输出到日志文件.  PassiveDNS可以在内存中缓存/聚合重复的DNS答案，从而限制了日志文件中的数据量，而不会丢失DNS答案中的信息.
- [sagan](http://sagan.quadrantsec.com/) -Sagan使用“类似Snort”引擎和规则来分析日志（syslog /事件日志/ snmptrap / netflow / etc）.
- [Node Security Platform](https://nodesecurity.io/) -与Snyk相似的功能，但在大多数情况下是免费的，而对于其他人则非常便宜.
- [ntopng](http://www.ntop.org/products/traffic-analysis/ntop/) -Ntopng是一个网络流量探测器，它显示网络使用情况，类似于流行的top Unix命令所执行的操作.
- [Fibratus](https://github.com/rabbitstack/fibratus)  -Fibratus是用于Windows内核探索和跟踪的工具.  它能够捕获大部分Windows内核活动-进程/线程创建和终止，文件系统I / O，注册表，网络活动，DLL加载/卸载等等.  Fibratus有一个非常简单的CLI，该CLI封装了用于启动内核事件流收集器，设置内核事件过滤器或运行称为“细丝”的轻量级Python模块的机制.
- [opensnitch](https://github.com/evilsocket/opensnitch) -OpenSnitch是Little Snitch应用程序防火墙的GNU / Linux端口

### IDS / IPS / Host IDS / Host IPS

- [Snort](https://www.snort.org/)  -Snort是由Martin Roesch于1998年创建的免费开放源代码网络入侵防御系统（NIPS）和网络入侵检测系统（NIDS）.Snort现在由Sourcefire开发，其中Roesch是其创始人兼CTO.  2009年，Snort作为“有史以来最伟大的开源软件之一”进入InfoWorld的开源名人堂.
- [Bro](https://www.bro.org/) -Bro是功能强大的网络分析框架，与您可能知道的典型IDS有很大不同.
- [OSSEC](https://ossec.github.io/) - Comprehensive Open Source HIDS. Not for the faint of heart. Takes a bit to get your head around how it works. Performs log analysis, file integrity checking, policy monitoring, rootkit detection, real-time alerting and active response. It runs on most operating systems, including Linux, MacOS, Solaris, HP-UX, AIX and Windows. Plenty of reasonable documentation. Sweet spot is medium to large deployments.
- [Suricata](http://suricata-ids.org/)  -Suricata是高性能的网络IDS，IPS和网络安全监视引擎.  开源，由社区运营的非营利基金会开放信息安全基金会（OISF）拥有.  Suricata由OISF及其支持供应商开发.
- [Security Onion](http://blog.securityonion.net/)  -Security Onion是一个Linux发行版，用于入侵检测，网络安全监视和日志管理.  它基于Ubuntu，包含Snort，Suricata，Bro，OSSEC，Sguil，Squit，Snorby，ELSA，Xplico，NetworkMiner和许多其他安全工具.  易于使用的设置向导使您可以在几分钟内为企业构建一支由分布式传感器组成的队伍！
- [sshwatch](https://github.com/marshyski/sshwatch)  -SSH的IPS，类似于用Python编写的DenyHosts.  它还可以在日志中收集有关攻击过程中攻击者的信息.
- [Stealth](https://fbb-git.github.io/stealth/)  -文件完整性检查程序，几乎没有沉积物.  控制器从另一台计算机上运行，​​这使攻击者很难知道正在通过SSH以定义的伪随机间隔检查文件系统.  强烈建议用于中小型部署.
- [AIEngine](https://bitbucket.org/camp0/aiengine) -AIEngine是下一代交互式/可编程Python / Ruby / Java / Lua数据包检查引擎，具有无需任何人工干预即可学习的功能，NIDS（网络入侵检测系统）功能，DNS域分类，网络收集器，网络取证等.
- [Denyhosts](http://denyhosts.sourceforge.net/) -阻止基于SSH字典的攻击和蛮力攻击.
- [Fail2Ban](http://www.fail2ban.org/wiki/index.php/Main_Page) -扫描日志文件并对显示恶意行为的IP采取措施.
- [SSHGuard](http://www.sshguard.net/) -用C编写的用于保护除SSH之外的服务的软件
- [Lynis](https://cisofy.com/lynis/) -Linux / Unix的开源安全审核工具.

### Honey Pot / Honey Net

- [awesome-honeypots](https://github.com/paralax/awesome-honeypots) -令人敬畏的经典蜜罐清单.
- [HoneyPy](https://github.com/foospidy/HoneyPy)  -HoneyPy是一种中低互动的蜜罐.  它易于实现：部署，使用插件扩展功能以及应用自定义配置.
- [Conpot](http://conpot.org/)  -ICS / SCADA蜜罐.  Conpot是一种交互性较低的服务器端工业控制系统蜜罐，其设计易于部署，修改和扩展.  通过提供一系列通用的工业控制协议，我们创建了构建您自己的系统的基础，能够模拟复杂的基础结构以说服对手他刚刚发现了一个巨大的工业综合体.  为了提高欺骗性，我们还提供了服务器自定义人机界面的可能性，以增加蜜罐的攻击面.  可以人为地延迟服务的响应时间，以模仿恒定负载下系统的行为.  因为我们提供了协议的完整堆栈，所以可以使用高效的HMI来访问Conpot，也可以使用真实的硬件对其进行扩展.  Conpot是在Honeynet项目的保护下并在几个非常大的巨头的肩膀上开发的.
- [Amun](https://github.com/zeroq/amun) -基于Amun Python的低交互性Honeypot.
- [Glastopf](http://glastopf.org/)  -Glastopf是一个蜜罐，它可以模拟成千上万个漏洞，从针对Web应用程序的攻击中收集数据.  其背后的原理非常简单：向利用Web应用程序的攻击者回复正确的响应.
- [Kippo](https://github.com/desaster/kippo) -Kippo是一种中等交互性SSH蜜罐，旨在记录暴力攻击，最重要的是，记录攻击者执行的整个外壳交互.
- [Kojoney](http://kojoney.sourceforge.net/)  -Kojoney是模拟SSH服务器的低级交互蜜罐.  该守护程序是使用Twisted Conch库以Python编写的.
- [HonSSH](https://github.com/tnich/honssh)  -HonSSH是一种高交互性的Honey Pot解决方案.  HonSSH将位于攻击者和蜜罐之间，从而在它们之间创建两个单独的SSH连接.
- [Bifrozt](http://sourceforge.net/projects/bifrozt/)  -Bifrozt是带有DHCP服务器的NAT设备，通常将其部署为将一个NIC直接连接到Internet，将一个NIC连接到内部网络.  Bifrozt与其他标准NAT设备的不同之处在于，它可以充当攻击者和蜜罐之间的透明SSHv2代理.  如果您在Bifrozt的内部网络上部署了SSH服务器，它将以纯文本格式将所有交互记录到TTY文件中，以便以后查看，并捕获所有已下载文件的副本.  您无需在内部SSH服务器上安装任何其他软件，编译任何内核模块或使用特定版本或类型的操作系统，即可正常工作.  它将出站流量限制为一定数量的端口，并且在超出某些限制时将开始丢弃这些端口上的出站数据包.
- [HoneyDrive](http://bruteforce.gr/honeydrive)  -HoneyDrive是主要的蜜罐Linux发行版.  它是安装了Xubuntu Desktop 12.04.4 LTS版的虚拟设备（OVA）.  它包含10多个预安装和预配置的蜜罐软件包，例如Kippo SSH蜜罐，Dionaea和Amun恶意软件蜜罐，Honeyd低交互蜜罐，Glastopf Web蜜罐和Wordpot，Conpot SCADA / ICS蜜罐，Thug和PhoneyC蜜罐等. .  此外，它包括许多有用的预配置脚本和实用程序，以分析，可视化和处理它可以捕获的数据，例如Kippo-Graph，Honeyd-Viz，DionaeaFR，ELK堆栈等等.  最后，分发中还提供了将近90种著名的恶意软件分析，取证和网络监控相关工具.
- [Cuckoo Sandbox](http://www.cuckoosandbox.org/)  -Cuckoo Sandbox是一款用于自动分析可疑文件的开源软件.  为此，它利用自定义组件监视在隔离环境中运行时恶意进程的行为.
- [T-Pot Honeypot Distro](http://dtag-dev-sec.github.io/mediator/feature/2017/11/07/t-pot-17.10.html)  -T-Pot基于Ubuntu Server 16 / 17.x LTS的网络安装程序.  honeypot守护程序以及正在使用的其他支持组件已使用docker进行了容器化.  这使我们可以在同一网络接口上运行多个honeypot守护程序，同时保持较小的占用空间并将每个honeypot限制在其自己的环境中.  通过香草Ubuntu进行安装- [T-Pot Autoinstall](https://github.com/dtag-dev-sec/t-pot-autoinstall)  -该脚本将在新的Ubuntu 16.04.x LTS（64位）上安装T-Pot 16.04 / 17.10.  它打算在托管服务器上使用，在托管服务器上会提供Ubuntu基本映像，并且无法安装自定义ISO映像.  已在VMware的原始Ubuntu 16.04.3上成功测试.

### Full Packet Capture / Forensic

- [tcpflow](https://github.com/simsong/tcpflow)  -tcpflow是一个程序，可捕获作为TCP连接（流）一部分传输的数据，并以便于协议分析和调试的方式存储数据.  每个TCP流都存储在其自己的文件中.  因此，典型的TCP流将存储在两个文件中，每个方向一个.  tcpflow还可以处理存储的“ tcpdump”数据包流.
- [Xplico](http://www.xplico.org/)  -Xplico的目标是从互联网流量中提取捕获的应用程序数据.  例如，Xplico从pcap文件中提取每个电子邮件（POP，IMAP和SMTP协议），所有HTTP内容，每个VoIP呼叫（SIP），FTP，TFTP等.  Xplico不是网络协议分析器.  Xplico是一个开源的网络取证分析工具（NFAT）.
- [Moloch](https://github.com/aol/moloch)  -Moloch是一个开源的大规模IPv4数据包捕获（PCAP），索引和数据库系统.  提供了一个简单的Web界面，用于PCAP浏览，搜索和导出.  公开的API允许直接下载PCAP数据和JSON格式的会话数据.  通过使用HTTPS和HTTP摘要密码支持或在前面使用apache，可以实现简单的安全性.  Moloch并不是要取代IDS引擎，而是与它们一起工作，以标准PCAP格式存储和索引所有网络流量，从而提供快速访问.  Moloch构建为可跨许多系统部署，并且可以扩展以处理每秒数千兆位的流量.
- [OpenFPC](http://www.openfpc.org)  -OpenFPC是一组工具，可以组合提供轻量级的完整数据包网络流量记录器和缓冲系统.  它的设计目标是允许非专家用户在集成到现有警报和日志管理工具的同时，在COTS硬件上部署分布式网络流量记录器.
- [Dshell](https://github.com/USArmyResearchLab/Dshell)  -Dshell是网络取证分析框架.  支持插件的快速开发，以支持对网络数据包捕获的剖析.
- [stenographer](https://github.com/google/stenographer) -Stenographer是一种数据包捕获解决方案，旨在将所有数据包快速后台处理到磁盘，然后提供对这些数据包子集的简单，快速访问.

### Sniffer

- [wireshark](https://www.wireshark.org)  -Wireshark是一个免费的开源数据包分析器.  它用于网络故障排除，分析，软件和通信协议开发以及培训.  Wireshark与tcpdump非常相似，但是具有图形化的前端以及一些集成的排序和过滤选项.
- [netsniff-ng](http://netsniff-ng.org/)  -netsniff-ng是一个免费的Linux网络工具包，如果您愿意的话，它是您日常使用Linux网络管道的瑞士军刀.  零复制机制可提高其性能，因此，在数据包接收和传输时，内核无需将数据包从内核空间复制到用户空间，反之亦然.
- [Live HTTP headers ](https://addons.mozilla.org/en-US/firefox/addon/http-header-live/)  -Live HTTP标头是一个免费的firefox插件，可实时查看您的浏览器请求.  它显示了请求的整个标头，可用于查找实现中的安全漏洞.

### Security Information & Event Management

- [Prelude](https://www.prelude-siem.org/)  -Prelude是通用的“安全信息和事件管理”（SIEM）系统.  Prelude收集，归一化，分类，汇总，关联和报告所有与安全相关的事件，而与引起该事件的产品品牌或许可证无关；  前奏是“无代理”.
- [OSSIM](https://www.alienvault.com/open-threat-exchange/projects) -OSSIM提供了SIEM产品中安全专业人员需要的所有功能-事件收集，规范化和关联.
- [FIR](https://github.com/certsocietegenerale/FIR) -快速事件响应，一种网络安全事件管理平台.
- [LogESP](https://github.com/dogoncouch/LogESP) -开源SIEM（安全信息和事件管理系统）.

### VPN

- [OpenVPN](https://openvpn.net/)  -OpenVPN是一种开源软件应用程序，它实现了虚拟专用网（VPN）技术，用于在路由或桥接配置以及远程访问设施中创建安全的点对点或站点对站点连接.  它使用定制安全协议，该协议利用SSL / TLS进行密钥交换.

### Fast Packet Processing

- [DPDK](http://dpdk.org/) -DPDK是一组用于快速数据包处理的库和驱​​动程序.
- [PFQ](https://github.com/pfq/PFQ) -PFQ是为Linux操作系统设计的功能性网络框架，该框架允许高效的数据包捕获/传输（10G及更高版本），内核内功能处理以及跨套接字/端点的数据包控制.
- [PF_RING](http://www.ntop.org/products/packet-capture/pf_ring/) -PF_RING是一种新型的网络套接字，可显着提高数据包捕获速度.
- [PF_RING ZC (Zero Copy)](http://www.ntop.org/products/packet-capture/pf_ring/pf_ring-zc-zero-copy/)  -PF_RING ZC（零复制）是一种灵活的数据包处理框架，可让您在任何数据包大小下实现1/10 Gbit线速数据包处理（RX和TX）.  它实现了零复制操作，包括用于进程间和VM间（KVM）通信的模式.
- [PACKET_MMAP/TPACKET/AF_PACKET](http://lxr.free-electrons.com/source/Documentation/networking/packet_mmap.txt) -使用PACKET_MMAP可以改善Linux中捕获和传输过程的性能.
- [netmap](http://info.iet.unipi.it/~luigi/netmap/)  -netmap是用于高速数据包I / O的框架.  连同其配套的VALE软件开关，它被实现为单个内核模块，并且可用于FreeBSD，Linux和现在的Windows.

### Firewall
- [pfSense](https://www.pfsense.org/) -防火墙和路由器FreeBSD分发.
- [OPNsense](https://opnsense.org/)  -是一个基于FreeBSD的开源，易于使用和易于构建的防火墙和路由平台.  OPNsense包含昂贵的商用防火墙中可用的大多数功能，并且在许多情况下还包含更多功能.  它带来了具有开放性和可验证资源优势的商业产品的丰富功能集.
- [fwknop](https://www.cipherdyne.org/fwknop/) -通过防火墙中的“单包授权”保护端口.

### Anti-Spam
- [SpamAssassin](https://spamassassin.apache.org/) -使用各种检测技术的强大而流行的电子邮件垃圾邮件过滤器.


### Docker Images for Penetration Testing & Security
-`docker pull kalilinux / kali-linux-docker` [official Kali Linux](https://hub.docker.com/r/kalilinux/kali-linux-docker/)
-`docker pull owasp / zap2docker-stable`- [official OWASP ZAP](https://github.com/zaproxy/zaproxy)
-`docker pull wpscanteam / wpscan`- [official WPScan](https://hub.docker.com/r/wpscanteam/wpscan/)
-`docker pull remnux / metasploit`- [docker-metasploit](https://hub.docker.com/r/remnux/metasploit/)
-`码头工人拉公民tig / dvwa`- [Damn Vulnerable Web Application (DVWA)](https://hub.docker.com/r/citizenstig/dvwa/)
-`docker pull wpscanteam / vulnerablewordpress`- [Vulnerable WordPress Installation](https://hub.docker.com/r/wpscanteam/vulnerablewordpress/)
-`docker pull hmlio / vaas-cve-2014-6271`- [Vulnerability as a service: Shellshock](https://hub.docker.com/r/hmlio/vaas-cve-2014-6271/)
-`docker pull hmlio / vaas-cve-2014-0160`- [Vulnerability as a service: Heartbleed](https://hub.docker.com/r/hmlio/vaas-cve-2014-0160/)
-`docker pull opendns / security-ninjas`- [Security Ninjas](https://hub.docker.com/r/opendns/security-ninjas/)
-`docker pull diogomonica / docker-bench-security`- [Docker Bench for Security](https://hub.docker.com/r/diogomonica/docker-bench-security/)
-`docker pull ismisepaul / securityshepherd`- [OWASP Security Shepherd](https://hub.docker.com/r/ismisepaul/securityshepherd/)
-`docker pull danmx / docker-owasp-webgoat`- [OWASP WebGoat Project docker image](https://hub.docker.com/r/danmx/docker-owasp-webgoat/)
-`docker-compose build &amp;&amp; docker-compose up-- [OWASP NodeGoat](https://github.com/owasp/nodegoat#option-3---run-nodegoat-on-docker)
-`码头工人拉公民tig / nowasp`- [OWASP Mutillidae II Web Pen-Test Practice Application](https://hub.docker.com/r/citizenstig/nowasp/)
-`docker pull bkimminich / juice-shop`- [OWASP Juice Shop](https://hub.docker.com/r/bkimminich/juice-shop)


## Endpoint

### Anti-Virus / Anti-Malware

- [Linux Malware Detect](https://www.rfxn.com/projects/linux-malware-detect/) -针对Linux的恶意软件扫描程序，旨在针对共享托管环境中面临的威胁进行设计.
- [LOKI](https://github.com/Neo23x0/Loki) -威胁和事件响应扫描程序的简单指示


- [DocBleach](https://github.com/docbleach/DocBleach) -开源的内容撤防和重建软件，可对Office，PDF和RTF文档进行消毒.

### Configuration Management

- [Rudder](http://www.rudder-project.org/)  -Rudder是一个易于使用的，基于Web的，基于角色的解决方案，用于IT基础架构自动化和合规性.  自动执行常见的系统管理任务（安装，配置）；  随着时间的推移强制执行配置（一次配置是好的，确保配置有效并自动修复会更好）；  所有管理节点的清单；  Web界面，用于配置和管理节点及其配置；  合规性报告，按配置和/或按节点.

### Authentication

- [google-authenticator](https://github.com/google/google-authenticator)  -Google Authenticator项目包括用于多个移动平台的一次性密码生成器的实现，以及可插拔的身份验证模块（PAM）.  一次性密码是使用开放身份验证倡议（OATH）开发的开放标准（与OAuth无关）生成的.  这些实现支持RFC 4226中指定的基于HMAC的一次性密码（HOTP）算法和RFC 6238中指定的基于时间的一次性密码（TOTP）算法. [Tutorials: How to set up two-factor authentication for SSH login on Linux](http://xmodulo.com/two-factor-authentication-ssh-login-linux.html)

### Mobile / Android / iOS

- [android-security-awesome](https://github.com/ashishb/android-security-awesome)  -android安全相关资源的集合.  学术界和工业界正在开展许多工作，以执行对Android应用程序进行动态分析，静态分析和反向工程的工具.
- [SecMobi Wiki](http://wiki.secmobi.com/)  -移动安全资源的集合，包括文章，博客，书籍，小组，项目，工具和会议.  *
- [OWASP Mobile Security Testing Guide](https://github.com/OWASP/owasp-mstg) -有关移动应用程序安全性测试和逆向工程的综合手册.
- [OSX Security Awesome](https://github.com/kai5263499/osx-security-awesome) -OSX和iOS安全资源的集合
- [Themis](https://github.com/cossacklabs/themis) -用于保护敏感数据的高级多平台加密框架：具有前向保密性和安全数据存储（AES256GCM）的安全消息传递，适合构建端到端加密应用程序.
- [Mobile Security Wiki](https://mobilesecuritywiki.com/) -移动安全资源的集合.
- [Apktool](https://github.com/iBotPeaches/Apktool) -反向工程Android apk文件的工具.
- [jadx](https://github.com/skylot/jadx) -用于从Android Dex和Apk文件生成Java源代码的命令行和GUI工具.
- [enjarify](https://github.com/Storyyeller/enjarify) -一种将Dalvik字节码转换为等效Java字节码的工具.
- [Android Storage Extractor](https://github.com/51j0/Android-Storage-Extractor) -一键提取Android应用程序的本地数据存储的工具.
- [Quark-Engine](https://github.com/quark-engine/quark-engine) -一个忽略了Android恶意软件的评分系统.

### Forensics

- [grr](https://github.com/google/grr) -GRR快速响应是一个针对远程实时取证的事件响应框架.
- [Volatility](https://github.com/volatilityfoundation/volatility) - Python based memory extraction and analysis framework.
- [mig](http://mig.mozilla.org/)  -MIG是在远程端点上进行调查性手术的平台.  它使研究人员可以并行地从大量系统中获取信息，从而加快事件调查和日常运营安全性.
- [ir-rescue](https://github.com/diogo-fernan/ir-rescue) -* ir-rescue *是Windows Batch脚本和Unix Bash脚本，用于在事件响应期间全面收集主机取证数据.
- [Logdissect](https://github.com/dogoncouch/logdissect) -CLI工具和Python API，用于分析日志文件和其他数据.
- [Meerkat](https://github.com/TonyPhipps/Meerkat) -基于PowerShell的Windows工件收集，用于威胁搜寻和事件响应.

## Threat Intelligence

- [abuse.ch](https://www.abuse.ch/) -ZeuS跟踪器/ SpyEye跟踪器/ Palevo跟踪器/ Feodo跟踪器跟踪世界各地的Command＆Control服务器（主机），并为您提供域和IP阻止列表.
- [Emerging Threats - Open Source](http://doc.emergingthreats.net/bin/view/Main/EmergingFAQ)  -新兴威胁始于10年前，它是一个开放源代码社区，用于收集Suricata和SNORT®规则，防火墙规则以及其他IDS规则集.  开源社区在Internet安全中仍然发挥着积极作用，每天有200,000多位活跃用户下载该规则集.  ETOpen规则集对任何用户或组织开放，只要您遵循一些基本准则即可.  我们的ETOpen规则集可随时下载.
- [PhishTank](http://www.phishtank.com/)  -PhishTank是一个协作式票据交换所，用于收集有关Internet上网络钓鱼的数据和信息.  此外，PhishTank为开发人员和研究人员提供了一个开放的API，可将反网络钓鱼数据免费集成到其应用程序中.
- [SBL / XBL / PBL / DBL / DROP / ROKSO](http://www.spamhaus.org/) - The Spamhaus Project is an international nonprofit organization whose mission is to track the Internet's spam operations and sources, to provide dependable realtime anti-spam protection for Internet networks, to work with Law Enforcement Agencies to identify and pursue spam and malware gangs worldwide, and to lobby governments for effective anti-spam legislation.
- [Internet Storm Center](https://www.dshield.org/reports.html)  -ISC是在成功检测，分析并广泛传播Li0n蠕虫之后于2001年创建的.  如今，ISC为成千上万的Internet用户和组织提供了免费的分析和警告服务，并且正在与Internet服务提供商积极合作，以对抗最恶意的攻击者.
- [AutoShun](https://www.autoshun.org/) -AutoShun是一个Snort插件，可让您将Snort IDS日志发送到集中式服务器，该服务器会将来自传感器日志的攻击与来自世界各地的其他Snort传感器，蜜罐和邮件过滤器相关联.
- [DNS-BH](http://www.malwaredomains.com/)  -DNS-BH项目创建并维护一个已知用于传播恶意软件和间谍软件的域的列表.  该项目创建了绑定和Windows区域文件，这些文件用于对对localhost的任何请求提供对本地主机的虚假答复，从而防止了许多间谍软件的安装和报告.
- [AlienVault Open Threat Exchange](http://www.alienvault.com/open-threat-exchange/dashboard) -AlienVault开放式威胁交换（OTX），可帮助您保护网络免受恶意IP地址引起的数据丢失，服务中断和系统损害.
- [Tor Bulk Exit List](https://metrics.torproject.org/collector.html)  -CollecTor，Tor网络中您友好的数据收集服务.  CollecTor从公共Tor网络中的各个节点和服务中获取数据，并将其提供给全世界.  如果您正在研究Tor网络，或者正在开发使用Tor网络数据的应用程序，那么这是您的起点. [TOR Node List](https://www.dan.me.uk/tornodes) /  [DNS Blacklists](https://www.dan.me.uk/dnsbl) / [Tor Node List](http://torstatus.blutmagie.de/)
- [leakedin.com](http://www.leakedin.com/)  -Leakedin.com的主要目的是使访问者了解丢失数据的风险.  该博客仅收集在pastebin.com等网站上丢失或披露的数据样本.
- [FireEye OpenIOCs](https://github.com/fireeye/iocs) - FireEye Publicly Shared Indicators of Compromise (IOCs)
- [OpenVAS NVT Feed](http://www.openvas.org/openvas-nvt-feed.html)  -网络漏洞测试（NVT）的公共提要.  它包含超过35,000个NVT（截至2014年4月），并且每天都在增长.  此提要配置为OpenVAS的默认设置.
- [Project Honey Pot](http://www.projecthoneypot.org/)  -蜜罐计划（Project Honey Pot）是第一个也是唯一的分布式系统，用于识别垃圾邮件发送者和垃圾邮件发送者用以从您的网站抓取地址.  使用Project Honey Pot系统，您可以安装根据您的站点访问者的时间和IP地址自定义标记的地址.  如果这些地址之一开始接收电子邮件，我们不仅可以告诉您该邮件是垃圾邮件，还可以告诉您该地址被收集的确切时间以及收集该地址的IP地址.
- [virustotal](https://www.virustotal.com/)  -VirusTotal是Google的子公司，是一项免费的在线服务，可分析文件和URL，以识别由防病毒引擎和网站扫描程序检测到的病毒，蠕虫，特洛伊木马和其他种类的恶意内容.  同时，它可以用作检测误报的手段，即被一个或多个扫描仪检测为恶意的无害资源.
- [IntelMQ](https://github.com/certtools/intelmq/)  -IntelMQ是用于CERT的解决方案，用于使用消息队列协议收集和处理安全性提要，pastebin，推文.  这是一个由社区推动的举措，称为IHAP（突发事件处理自动化项目），由欧洲CERT在几次InfoSec活动期间进行概念设计.  其主要目标是为事件响应者提供一种收集和处理威胁情报的简便方法，从而改善CERT的事件处理流程. [ENSIA Homepage](https://www.enisa.europa.eu/activities/cert/support/incident-handling-automation).
- [CIFv2](https://github.com/csirtgadgets/massive-octo-spice)  -CIF是网络威胁情报管理系统.  CIF允许您组合来自许多来源的已知恶意威胁信息，并将该信息用于标识（事件响应），检测（IDS）和缓解（无效路由）.
- [CriticalStack](https://intel.criticalstack.com/) -用于Bro网络安全监控平台的免费汇总威胁情报.
- [MISP - Open Source Threat Intelligence Platform ](https://www.misp-project.org/)  -MISP威胁共享平台是一个免费的开源软件，可帮助共享威胁情报（包括网络安全指标）的信息.  一个威胁情报平台，用于收集，共享，存储和关联目标攻击的危害指标，威胁情报，财务欺诈信息，漏洞信息，甚至是反恐信息.  MISP项目包括软件，通用库（[taxonomies](https://www.misp-project.org/taxonomies.html), [threat-actors and various malware](https://www.misp-project.org/galaxy.html)），一个广泛的数据模型，可以使用 [objects](https://www.misp-project.org/objects.html) 和默认 [feeds](https://www.misp-project.org/feeds/).
- [PhishStats](https://phishstats.info/) -包含IP，域名和网站标题的网络钓鱼统计信息.

## Web

### Organization

- [OWASP](http://www.owasp.org) -开放式Web应用程序安全性项目（OWASP）是一家致力于提高软件安全性的全球性501（c）（3）非营利慈善组织.

### Web Application Firewall

- [ModSecurity](http://www.modsecurity.org/) -ModSecurity是用于实时Web应用程序监视，日志记录和访问控制的工具包.
- [NAXSI](https://github.com/nbs-system/naxsi) -NAXSI是NGINX的开源，高性能，低规则维护WAF，NAXSI表示Nginx Anti Xss＆Sql Injection.
- [sql_firewall](https://github.com/uptimejp/sql_firewall) PostgreSQL的SQL防火墙扩展
- [ironbee](https://github.com/ironbee/ironbee)  -IronBee是一个开源项目，旨在构建通用的Web应用程序安全传感器.  IronBee作为用于开发用于保护Web应用程序安全的系统的框架-用于构建Web应用程序防火墙（WAF）的框架.

### Scanning / Pentesting

- [Spyse](https://spyse.com/)  -Spyse是OSINT搜索引擎，可提供有关整个Web的最新数据.  所有数据都存储在其自己的数据库中以进行即时访问，并相互互连以进行灵活的搜索.
提供的数据：IPv4主机，子/域/ whois，端口/横幅/协议，技术，操作系统，AS，广泛的SSL / TLS DB等.
- [sqlmap](http://sqlmap.org/)  -sqlmap是一个开放源代码渗透测试工具，可自动检测和利用SQL注入漏洞并接管数据库服务器的过程.  它配备了强大的检测引擎，针对最终渗透测试仪的众多细分功能以及从数据库指纹识别，从数据库获取数据到访问基础文件系统以及通过外出在操作系统上执行命令的广泛开关带内连接.
- [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)  -Zed攻击代理（ZAP）是易于使用的集成渗透测试工具，用于发现Web应用程序中的漏洞.  它被设计为具有广泛的安全经验的人使用，因此，它是渗透测试新手的开发人员和功能测试人员的理想选择.  ZAP提供了自动扫描程序以及一系列工具，可让您手动查找安全漏洞.
- [OWASP Testing Checklist v4](https://www.owasp.org/index.php/Testing_Checklist)  -在网络漏洞评估期间要测试的一些控件的列表.  可以找到降价版本 [here](https://github.com/amocrenco/owasp-testing-checklist-v4-markdown/blob/master/README.md).
- [w3af](http://w3af.org/)  -w3af是一个Web应用程序攻击和审核框架.  该项目的目标是创建一个框架，以通过查找和利用所有Web应用程序漏洞来帮助您保护Web应用程序.
- [Recon-ng](https://github.com/lanmaster53/recon-ng)  -Recon-ng是用Python编写的功能齐全的Web侦察框架.  侦查的外观与Metasploit框架相似.
- [PTF](https://github.com/trustedsec/ptf) -渗透测试器框架（PTF）是一种模块化支持最新工具的方式.
- [Infection Monkey](https://github.com/guardicore/monkey)  -用于地图/笔测试网络的半自动笔测试工具.  模拟人类攻击者.
- [ACSTIS](https://github.com/tijme/angularjs-csti-scanner)  -ACSTIS可帮助您扫描某些Web应用程序以进行AngularJS客户端模板注入（有时称为CSTI，沙箱转义或沙箱绕过）.  它支持扫描单个请求，还可以爬网整个Web应用程序以查找AngularJS CSTI漏洞.
- [padding-oracle-attacker](https://github.com/KishanBagaria/padding-oracle-attacker) -padding-oracle-attacker是一个CLI工具和库，可轻松执行padding oracle攻击（解密以CBC模式加密的数据），并支持并发网络请求和优雅的UI.

### Runtime Application Self-Protection

- [Sqreen](https://www.sqreen.io/)  -Sqreen是针对软件团队的运行时应用程序自我保护（RASP）解决方案.  应用内代理对应用进行检测和监控.  报告可疑的用户活动，并且在运行时阻止了攻击，而无需修改代码或重定向流量.
- [OpenRASP](https://github.com/baidu/openrasp)  -百度公司积极维护的开源RASP解决方案.借助上下文感知检测算法，该项目几乎没有出现误报.  在高服务器负载下，性能下降不到3％.

### Development

- [API Security in Action](https://www.manning.com/books/api-security-in-action)  -涵盖API安全性的书籍，包括安全开发，基于令牌的身份验证，JSON Web令牌，OAuth 2和Macaroons.  （早期访问，持续发布，最终发布于2020年夏季）
- [Secure by Design](https://www.manning.com/books/secure-by-design?a_aid=danbjson&a_bid=0b3fac80)  -标识可减少许多安全漏洞的设计模式和编码样式的书.  （早期访问，持续发布，最终版本于2017年秋季）
- [Securing DevOps](https://www.manning.com/books/securing-devops)  -本书探讨了如何将DevOps和Security的技术一起应用，以使云服务更加安全.  （早期访问，持续发布，最终版本2018年1月）
- [Understanding API Security](https://www.manning.com/books/understanding-api-security) -免费的电子书采样器，通过显示API的组合方式以及OAuth协议可用于保护它们的方式，提供了一些有关API安全性在现实世界中如何工作的上下文.
- [OAuth 2 in Action](https://www.manning.com/books/oauth-2-in-action) -本书从客户端，授权服务器和资源服务器的角度教您OAuth 2的实际使用和部署.
- [OWASP ZAP Node API](https://github.com/zaproxy/zap-api-nodejs) -使用此官方API在NodeJS应用程序中利用OWASP Zed攻击代理（ZAP）.
- [GuardRails](https://github.com/apps/guardrails) -GitHub应用程序，可在请求请求中提供安全性反馈.
- [Checkov](https://github.com/bridgecrewio/checkov/) -用于基础结构作为代码的静态分析工具（Terraform）.

## Usability

- [Usable Security Course](https://pt.coursera.org/learn/usable-security)  -在Coursera的可用安全课程.  对于那些寻求安全性和可用性如何相交的人来说，这是非常好的.


## Big Data

- [data_hacking](https://github.com/ClickSecurity/data_hacking) -使用IPython，Pandas和Scikit的示例了解如何最大程度地利用安全数据.
- [hadoop-pcap](https://github.com/RIPE-NCC/hadoop-pcap) -Hadoop库，用于读取数据包捕获（PCAP）文件.
- [Workbench](http://workbench.readthedocs.org/) -用于安全研发团队的可扩展python框架.
- [OpenSOC](https://github.com/OpenSOC/opensoc) -OpenSOC集成了各种开源大数据技术，以提供用于安全监控和分析的集中式工具.
- [Apache Metron (incubating)](https://github.com/apache/incubator-metron) -Metron集成了各种开源大数据技术，以提供用于安全监视和分析的集中式工具.
- [Apache Spot (incubating)](https://github.com/apache/incubator-spot) -Apache Spot是开源软件，可利用流量和数据包分析中的洞察力.
- [binarypig](https://github.com/endgameinc/binarypig)  -Hadoop中的可扩展二进制数据提取.  Pig上的恶意软件处理和分析，通过Django，Twitter Bootstrap和Elasticsearch进行的探索.

## DevOps

- [Securing DevOps](https://manning.com/books/securing-devops?a_aid=securingdevops&a_bid=1353bcd8) -有关DevOps的安全技术的书，其中回顾了用于保护Web应用程序及其基础结构的最新实践.

## Operating Systems

### Online resources

- [Security related Operating Systems @ Rawsec](http://rawsec.ml/en/security-related-os/) -与安全相关的操作系统的完整列表
- [Best Linux Penetration Testing Distributions @ CyberPunk](https://n0where.net/best-linux-penetration-testing-distributions/) -主要渗透测试分布的说明
- [Security @ Distrowatch](http://distrowatch.com/search.php?category=Security) -致力于讨论，审查和保持与开源操作系统同步的网站


## Datastores

- [blackbox](https://github.com/StackExchange/blackbox) -使用GPG将机密安全存储在VCS存储库中
- [confidant](https://github.com/lyft/confidant) -将机密存储在AWS DynamoDB中，静态加密并与IAM集成
- [dotgpg](https://github.com/ConradIrwin/dotgpg) -一种用于安全轻松地备份和版本化生产机密或共享密码的工具.
- [redoctober](https://github.com/cloudflare/redoctober) -两人规则样式文件加密和解密的服务器.
- [aws-vault](https://github.com/99designs/aws-vault) -将AWS凭证存储在OSX钥匙串或加密文件中
- [credstash](https://github.com/fugue/credstash) - Store secrets using AWS KMS and DynamoDB
- [chamber](https://github.com/segmentio/chamber) -使用AWS KMS和SSM参数存储存储机密
- [Safe](https://github.com/starkandwayne/safe) -Vault CLI，使对Vault的读写更加容易.
- [Sops](https://github.com/mozilla/sops) -支持YAML，JSON和BINARY格式并使用AWS KMS和PGP加密的加密文件的编辑器.
- [passbolt](https://www.passbolt.com/)  -您的团队正在等待的密码管理器.  免费，开源，可扩展，基于OpenPGP.
- [passpie](https://github.com/marcwebbie/passpie) -多平台命令行密码管理器
- [Vault](https://www.vaultproject.io/) -足以保护环境和应用程序机密的加密数据存储区.

## EBooks

- [Holistic Info-Sec for Web Developers](https://holisticinfosecforwebdevelopers.com/) -免费和可下载的书籍系列，涵盖了Web开发人员和DevOps工程师需要广泛了解的内容，以创建健壮，可靠，可维护和安全的软件，网络等，这些内容可以按时连续交付，不会带来麻烦.惊喜
- [Docker Security - Quick Reference: For DevOps Engineers](https://binarymist.io/publication/docker-security/) -一本关于理解Docker安全默认设置，如何改进它们（理论和实践）以及许多工具和技术的书.  
- [How to Hack Like a Pornstar](https://books2read.com/u/bWzdBx) -分步进入BANK的流程，Sparc Flow，2017年  
- [How to Hack Like a Legend](https://amzn.to/2uWh1Up) -骇客闯入一家秘密的离岸公司的故事，Sparc Flow，2018年  
- [How to Investigate Like a Rockstar](https://books2read.com/u/4jDWoZ) -活着一场真正的危机，以掌握法医分析的秘密，Sparc Flow，2017年
- [Real World Cryptography](https://www.manning.com/books/real-world-cryptography) -这本抢先体验的书教您应用密码技术来理解和应用系统和应用程序各个级别的安全性.

## Other Awesome Lists

### Other Security Awesome Lists

- [Android Security Awesome](https://github.com/ashishb/android-security-awesome) -android安全相关资源的集合.
- [Awesome ARM Exploitation](https://github.com/HenryHoggard/awesome-arm-exploitation) -精选的ARM开发资源列表.
- [Awesome CTF](https://github.com/apsdehal/awesome-ctf) -CTF框架，库，资源和软件的精选列表.
- [Awesome Cyber Skills](https://github.com/joe-shenouda/awesome-cyber-skills) -精选的黑客环境列表，您可以在其中合法安全地培训网络技能.
- [Awesome Personal Security](https://github.com/Lissy93/personal-security-checklist) -精选的数字安全和隐私提示列表，以及指向更多资源的链接.
- [Awesome Hacking](https://github.com/carpedm20/awesome-hacking) -精选的很棒的Hacking教程，工具和资源列表.
- [Awesome Honeypots](https://github.com/paralax/awesome-honeypots) -很棒的蜜罐资源列表.
- [Awesome Malware Analysis](https://github.com/rshipp/awesome-malware-analysis) -精选的出色恶意软件分析工具和资源列表.
- [Awesome PCAP Tools](https://github.com/caesar0301/awesome-pcaptools) -计算机科学领域其他研究人员开发的用于处理网络跟踪的工具的集合.
- [Awesome Pentest](https://github.com/enaqx/awesome-pentest) -很棒的渗透测试资源，工具和其他闪亮内容的集合.
- [Awesome Linux Containers](https://github.com/Friz-zy/awesome-linux-containers) -精选的Linux容器框架，库和软件的精选清单.
- [Awesome Incident Response](https://github.com/meirwah/awesome-incident-response) -精选的事件响应资源列表.
- [Awesome Web Hacking](https://github.com/infoslack/awesome-web-hacking) -此列表适用于希望了解Web应用程序安全性但没有起点的任何人.
- [Awesome Threat Intelligence](https://github.com/hslatman/awesome-threat-intelligence) -精选的威胁情报资源列表.
- [Awesome Threat Modeling](https://github.com/redshiftzero/awesome-threat-modeling) -威胁建模资源的精选列表.
- [Awesome Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) -收集有用的备忘单
- [Awesome Industrial Control System Security](https://github.com/mpesen/awesome-industrial-control-system-security) -与工业控制系统（ICS）安全相关的资源精选清单.
- [Awesome YARA](https://github.com/InQuest/awesome-yara) - A curated list of awesome YARA rules, tools, and people.
- [Awesome Threat Detection and Hunting](https://github.com/0x4D31/awesome-threat-detection) -精选的出色威胁检测和狩猎资源列表.
- [Awesome Container Security](https://github.com/kai5263499/container-security-awesome) -与容器构建和运行时安全性相关的精选资源精选列表
- [Awesome Crypto Papers](https://github.com/pFarb/awesome-crypto-papers) -精选的密码学论文，文章，教程和howtos清单.
- [Awesome Shodan Search Queries](https://github.com/jakejarvis/awesome-shodan-queries) -一组有趣，有趣且令人沮丧的搜索查询，可插入Shodan.io.

### Other Common Awesome Lists

其他很棒的清单：

- [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) -真棒-*或*-真棒列表.
- [lists](https://github.com/jnv/lists) -在GitHub上整理的（很棒的）列表的最终列表.
- [Movies For Hacker](https://github.com/k4m4/movies-for-hackers) -每个黑客和赛博朋克都必须看的电影精选清单.

## [Contributing](https://github.com/sbilly/awesome-security/blob/master/contributing.md)

永远欢迎您的贡献！
