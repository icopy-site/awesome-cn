<div class="github-widget" data-repo="sbilly/awesome-security"></div>
## Awesome Security

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

一系列令人敬畏的软件，库，文档，书籍，资源和关于安全性的很酷的东西.

灵感来自 [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python).

Thanks to all [contributors](https://github.com/sbilly/awesome-security/graphs/contributors) ，你很棒，没有你就不可能！  目标是建立一个由知名资源组成的分类社区驱动集合.


------

## Network

### Scanning / Pentesting

- [OpenVAS](http://www.openvas.org/) -  OpenVAS是一个由多个服务和工具组成的框架，提供全面而强大的漏洞扫描和漏洞管理解决方案.
- [Metasploit Framework](https://github.com/rapid7/metasploit-framework)   - 用于针对远程目标计算机开发和执行漏洞利用代码的工具.  其他重要的子项目包括操作码数据库，shellcode存档和相关研究.
- [Kali](https://www.kali.org/)   -  Kali Linux是一个Debian派生的Linux发行版，专为数字取证和渗透测试而设计.  Kali Linux预装了许多渗透测试程序，包括nmap（端口扫描程序），Wireshark（数据包分析程序），John the Ripper（密码破解程序）和Aircrack-ng（用于渗透测试无线LAN的软件套件） .
- [pig](https://github.com/rafael-santiago/pig) -  Linux数据包制作工具.
- [scapy](https://github.com/secdev/scapy) -  Scapy：基于python的交互式数据包操作程序和库.
- [Pompem](https://github.com/rfunix/Pompem)   -  Pompem是一个开源工具，旨在自动搜索主要数据库中的漏洞.  用Python开发，具有高级搜索系统，从而方便了测试者和道德黑客的工作.  在其当前版本中，在数据库中执行搜索：Exploit-db，1337day，Packetstorm Security ...
- [Nmap](https://nmap.org) -  Nmap是一个免费的开源实用程序，用于网络发现和安全审计.
- [Amass](https://github.com/caffix/amass) -  Amass通过抓取最大数量的不同数据源，递归强制攻击，爬行网络存档，置换和更改名称，反向DNS扫描和其他技术来执行DNS子域枚举.
- [Anevicon](https://github.com/Gymmasssorla/anevicon) - 最强大的基于UDP的负载生成器，用Rust编写.
- [Finshir](https://github.com/Gymmasssorla/finshir) - 用Rust编写的协程驱动的低速和慢速流量发生器.
- [Legion](https://github.com/GoVanguard/legion) - 开源半自动发现和侦察网络渗透测试框架.

### Monitoring / Logging

- [justniffer](http://justniffer.sourceforge.net/) -  Justniffer是一种网络协议分析器，可以捕获网络流量并以自定义方式生成日志，可以模拟Apache Web服务器日志文件，跟踪响应时间并从HTTP流量中提取所有“截获”文件.
- [httpry](http://dumpsterventures.com/jason/httpry/)   -  httpry是一种专门用于显示和记录HTTP流量的数据包嗅探器.  它不是为了执行分析本身，而是为了捕获，解析和记录流量以供以后分析.  它可以在解析流量时实时显示流量，也可以作为记录到输出文件的守护进程运行.  它被编写为尽可能轻巧和灵活，因此它可以很容易地适应不同的应用程序.
- [ngrep](http://ngrep.sourceforge.net/)   -  ngrep努力提供GNU grep的大部分常用功能，将它们应用到网络层.  ngrep是一个支持pcap的工具，它允许您指定扩展的常规或十六进制表达式以匹配数据包的数据有效负载.  它目前通过以太网，PPP，SLIP，FDDI，令牌环和空接口识别IPv4 / 6，TCP，UDP，ICMPv4 / 6，IGMP和Raw，并且以与更常见的数据包嗅探工具相同的方式理解BPF过滤器逻辑，例如作为tcpdump和snoop.
- [passivedns](https://github.com/gamelinux/passivedns)   - 一种被动收集DNS记录的工具，用于辅助事件处理，网络安全监控（NSM）和一般数字取证.  PassiveDNS嗅探来自接口的流量或读取pcap文件并将DNS服务器答案输出到日志文件.  PassiveDNS可以在内存中缓存/聚合重复的DNS答案，限制日志文件中的数据量而不会丢失DNS答案中的基本要素.
- [sagan](http://sagan.quadrantsec.com/) -  Sagan使用&#39;Snort like&#39;引擎和规则来分析日志（syslog / event log / snmptrap / netflow / etc）.
- [Node Security Platform](https://nodesecurity.io/) - 类似的功能设置为Snyk，但在大多数情况下是免费的，而对其他人来说非常便宜.
- [ntopng](http://www.ntop.org/products/traffic-analysis/ntop/) -  Ntopng是一个网络流量探测器，显示网络使用情况，类似于流行的顶级Unix命令.
- [Fibratus](https://github.com/rabbitstack/fibratus)   -  Fibratus是一个用于探索和跟踪Windows内核的工具.  它能够捕获大部分Windows内核活动 - 进程/线程创建和终止，文件系统I / O，注册表，网络活动，DLL加载/卸载等等.  Fibratus有一个非常简单的CLI，它封装了启动内核事件流收集器，设置内核事件过滤器或运行名为filaments的轻量级Python模块的机制.
- [opensnitch](https://github.com/evilsocket/opensnitch) - OpenSnitch is a GNU/Linux port of the Little Snitch application firewall

### IDS / IPS / Host IDS / Host IPS

- [Snort](https://www.snort.org/)  --Snort是一个免费的开源网络入侵防御系统（NIPS）和网络入侵检测系统（NIDS），由Martin Roesch于1998年创建.Snort现在由Sourcefire开发，Roesch是其创始人兼首席技术官.  2009年，Snort进入InfoWorld的开源名人堂，成为“有史以来最伟大的开源软件之一”.
- [Bro](https://www.bro.org/) -  Bro是一个功能强大的网络分析框架，与您可能知道的典型IDS有很大不同.
- [OSSEC](https://ossec.github.io/)   - 全面的开源HIDS.  不适合胆小的人.  需要稍微了解一下它是如何工作的.  执行日志分析，文件完整性检查，策略监控，rootkit检测，实时警报和主动响应.  它可在大多数操作系统上运行，包括Linux，MacOS，Solaris，HP-UX，AIX和Windows.  大量合理的文档.  最佳点是大中型部署.
- [Suricata](http://suricata-ids.org/)   -  Suricata是一种高性能的网络IDS，IPS和网络安全监控引擎.  开源并由社区运营的非营利基金会开放信息安全基金会（OISF）所有.  Suricata由OISF及其支持供应商开发.
- [Security Onion](http://blog.securityonion.net/)   -  Security Onion是用于入侵检测，网络安全监控和日志管理的Linux发行版.  它基于Ubuntu，包含Snort，Suricata，Bro，OSSEC，Sguil，Squert，Snorby，ELSA，Xplico，NetworkMiner和许多其他安全工具.  易于使用的安装向导允许您在几分钟内为您的企业构建大量分布式传感器！
- [sshwatch](https://github.com/marshyski/sshwatch)   - 用于SSH的IPS，类似于用Python编写的DenyHosts.  它还可以在日志中收集攻击期间的攻击者信息.
- [Stealth](https://fbb-git.github.io/stealth/)   - 文件完整性检查器，几乎没有沉淀物.  控制器从另一台计算机运行，这使得攻击者很难知道通过SSH以定义的伪随机间隔检查文件系统.  强烈建议用于中小型部署.
- [AIEngine](https://bitbucket.org/camp0/aiengine) -  AIEngine是下一代交互式/可编程Python / Ruby / Java / Lua数据包检测引擎，具有学习功能，无需人工干预，NIDS（网络入侵检测系统）功能，DNS域分类，网络收集器，网络取证等等.
- [Denyhosts](http://denyhosts.sourceforge.net/) - 阻止基于SSH字典的攻击和暴力攻击.
- [Fail2Ban](http://www.fail2ban.org/wiki/index.php/Main_Page) - 扫描日志文件并对显示恶意行为的IP采取措施.
- [SSHGuard](http://www.sshguard.net/) - 用SSH编写的用于保护服务的软件，用C语言编写
- [Lynis](https://cisofy.com/lynis/) - 适用于Linux / Unix的开源安全审计工具.

### Honey Pot / Honey Net

- [awesome-honeypots](https://github.com/paralax/awesome-honeypots) - 规范的令人敬畏的蜜罐列表.
- [HoneyPy](https://github.com/foospidy/HoneyPy)   -  HoneyPy是一种低到中等交互蜜罐.  它易于：使用插件部署，扩展功能，以及应用自定义配置.
- [Dionaea](https://www.edgis-security.org/honeypot/dionaea/) -  Dionaea应该是一个nepenthes继承者，将python作为脚本语言嵌入，使用libemu检测shellcode，支持ipv6和tls.
- [Conpot](http://conpot.org/)   -  ICS / SCADA蜜罐.  Conpot是一款低交互式服务器端工业控制系统蜜罐，易于部署，修改和扩展.  通过提供一系列常见的工业控制协议，我们创建了构建您自己的系统的基础知识，能够模拟复杂的基础设施，以说服对手他刚刚找到了一个巨大的工业综合体.  为了提高欺骗性能力，我们还提供了服务器自定义人机界面以增加蜜罐攻击面的可能性.  可以人为地延迟服务的响应时间以模拟系统在恒定负载下的行为.  因为我们提供完整的协议栈，所以可以使用高效的HMI访问Conpot，也可以使用真实硬件进行扩展.  Conpot是在Honeynet项目的保护下开发的，并且是在一些非常大的巨头的肩膀上开发的.
- [Amun](https://github.com/zeroq/amun) - 基于Amun Python的低交互蜜罐.
- [Glastopf](http://glastopf.org/)   -  Glastopf是一个蜜罐，可模拟数千个漏洞，从针对Web应用程序的攻击中收集数据.  其背后的原理非常简单：回复利用Web应用程序的攻击者的正确响应.
- [Kippo](https://github.com/desaster/kippo) -  Kippo是一个中等交互式SSH蜜罐，用于记录暴力攻击，最重要的是，攻击者执行的整个shell交互.
- [Kojoney](http://kojoney.sourceforge.net/)   -  Kojoney是一个模拟SSH服务器的低级交互蜜罐.  守护进程使用Twisted Conch库用Python编写.
- [HonSSH](https://github.com/tnich/honssh)   -  HonSSH是一种高度互动的Honey Pot解决方案.  HonSSH将位于攻击者和蜜罐之间，在他们之间创建两个独立的SSH连接.
- [Bifrozt](http://sourceforge.net/projects/bifrozt/)   -  Bifrozt是一个带有DHCP服务器的NAT设备，通常部署一个NIC直接连接到Internet，一个NIC连接到内部网络.  Bifrozt与其他标准NAT设备的区别在于它能够在攻击者和蜜罐之间作为透明的SSHv2代理工作.  如果您在Bifrozt的内部网络上部署了SSH服务器，它会以明文形式将所有交互记录到TTY文件中，以后可以查看并捕获已下载的任何文件的副本.  您无需在内部SSH服务器上安装任何其他软件，编译任何内核模块或使用特定版本或类型的操作系统即可.  它会将出站流量限制为一定数量的端口，并在超过某些限制时开始丢弃这些端口上的出站数据包.
- [HoneyDrive](http://bruteforce.gr/honeydrive)   -  HoneyDrive是首屈一指的蜜罐Linux发行版.  它是安装了Xubuntu Desktop 12.04.4 LTS版本的虚拟设备（OVA）.  它包含10多个预安装和预配置的蜜罐软件包，如Kippo SSH蜜罐，Dionaea和Amun恶意软件蜜罐，Honeyd低交互蜜罐，Glastopf web蜜罐和Wordpot，Conpot SCADA / ICS蜜罐，Thug和PhoneyC蜜客等等.  此外，它还包括许多有用的预配置脚本和实用程序，用于分析，可视化和处理它可以捕获的数据，例如Kippo-Graph，Honeyd-Viz，DionaeaFR，ELK堆栈等等.  最后，在分发中也出现了近90种着名的恶意软件分析，取证和网络监控相关工具.
- [Cuckoo Sandbox](http://www.cuckoosandbox.org/)   -  Cuckoo Sandbox是一个开源软件，用于自动分析可疑文件.  为此，它使用自定义组件来监视恶意进程在隔离环境中运行时的行为.
- [T-Pot Honeypot Distro](http://dtag-dev-sec.github.io/mediator/feature/2017/11/07/t-pot-17.10.html)   -  T-Pot基于Ubuntu Server 16 / 17.x LTS的网络安装程序.  蜜罐守护程序以及正在使用的其他支持组件已使用docker进行集装箱化.  这允许我们在同一网络接口上运行多个蜜罐守护进程，同时保持较小的占用空间并限制每个蜜罐在其自己的环境中.  安装在香草Ubuntu上 -  [T-Pot Autoinstall](https://github.com/dtag-dev-sec/t-pot-autoinstall)   - 这个脚本将在新的Ubuntu 16.04.x LTS（64位）上安装T-Pot 16.04 / 17.10.  它旨在用于托管服务器，其中提供了Ubuntu基本映像，并且无法安装自定义ISO映像.  在VMware上的vanilla Ubuntu 16.04.3上成功测试.

### Full Packet Capture / Forensic

- [tcpflow](https://github.com/simsong/tcpflow)   -  tcpflow是一个程序，它捕获作为TCP连接（流）的一部分传输的数据，并以便于协议分析和调试的方式存储数据.  每个TCP流都存储在自己的文件中.  因此，典型的TCP流将存储在两个文件中，每个文件对应一个方向.  tcpflow还可以处理存储的&#39;tcpdump&#39;数据包流.
- [Xplico](http://www.xplico.org/)   -  Xplico的目标是从互联网流量中提取捕获包含的应用程序数据.  例如，从pcap文件中，Xplico提取每个电子邮件（POP，IMAP和SMTP协议），所有HTTP内容，每个VoIP呼叫（SIP），FTP，TFTP等.  Xplico不是网络协议分析器.  Xplico是一个开源网络取证分析工具（NFAT）.
- [Moloch](https://github.com/aol/moloch)   -  Moloch是一个开源的，大规模的IPv4数据包捕获（PCAP），索引和数据库系统.  提供了一个简单的Web界面，用于PCAP浏览，搜索和导出.  公开了API，允许直接下载PCAP数据和JSON格式的会话数据.  通过使用HTTPS和HTTP摘要密码支持或使用前面的apache实现简单的安全性.  Moloch并不是要取代IDS引擎，而是与它们一起工作，以标准PCAP格式存储和索引所有网络流量，从而提供快速访问.  Moloch可以部署在许多系统中，可以扩展以处理多个千兆位/秒的流量.
- [OpenFPC](http://www.openfpc.org)   -  OpenFPC是一组工具，结合起来提供轻量级的全包网络流量记录和缓冲系统.  它的设计目标是允许非专家用户在COTS硬件上部署分布式网络流量记录器，同时集成到现有的警报和日志管理工具中.
- [Dshell](https://github.com/USArmyResearchLab/Dshell)   -  Dshell是一个网络取证分析框架.  支持快速开发插件，以支持解析网络数据包捕获.
- [stenographer](https://github.com/google/stenographer) -  Stenographer是一种数据包捕获解决方案，旨在快速将所有数据包假脱机到磁盘，然后提供对这些数据包子集的简单，快速访问.

### Sniffer

- [wireshark](https://www.wireshark.org)   -  Wireshark是一款免费的开源数据包分析器.  它用于网络故障排除，分析，软件和通信协议开发以及教育.  Wireshark与tcpdump非常相似，但它有一个图形前端，以及一些集成的排序和过滤选项.
- [netsniff-ng](http://netsniff-ng.org/)   -  netsniff-ng是一个免费的Linux网络工具包，如果你愿意的话，它是你日常Linux网络管道的瑞士军刀.  通过零复制机制实现其性能提升，因此在数据包接收和传输时，内核不需要将数据包从内核空间复制到用户空间，反之亦然.
- [Live HTTP headers](https://addons.mozilla.org/de/firefox/addon/live-http-headers/)   - 实时HTTP标头是一个免费的firefox插件，可以实时查看您的浏览器请求.  它显示了请求的整个标头，可用于查找实现中的安全漏洞.

### Security Information & Event Management

- [Prelude](https://www.prelude-siem.org/)   -  Prelude是一个通用的“安全信息和事件管理”（SIEM）系统.  Prelude收集，规范化，分类，汇总，关联和报告所有与安全相关的事件，而不受产生此类事件的产品品牌或许可证的影响;  序曲是“无代理人”.
- [OSSIM](https://www.alienvault.com/open-threat-exchange/projects) -  OSSIM提供安全专业人员从SIEM产品中获得的所有功能 - 事件收集，规范化和关联.
- [FIR](https://github.com/certsocietegenerale/FIR) - 快速事件响应，一个网络安全事件管理平台.
- [LogESP](https://github.com/dogoncouch/LogESP) - 开源SIEM（安全信息和事件管理系统）.

### VPN

- [OpenVPN](https://openvpn.net/)   -  OpenVPN是一种开源软件应用程序，它实现虚拟专用网络（VPN）技术，用于在路由或桥接配置和远程访问设施中创建安全的点对点或站点到站点连接.  它使用自定义安全协议，利用SSL / TLS进行密钥交换.

### Fast Packet Processing

- [DPDK](http://dpdk.org/) -  DPDK是一组用于快速数据包处理的库和驱​​动程序.
- [PFQ](https://github.com/pfq/PFQ) -  PFQ是一个专为Linux操作系统设计的功能性网络框架，允许高效的数据包捕获/传输（10G及更高版本），内核功能处理和跨套接字/端点的数据包控制.
- [PF_RING](http://www.ntop.org/products/packet-capture/pf_ring/) -  PF_RING是一种新型网络套接字，可显着提高数据包捕获速度.
- [PF_RING ZC (Zero Copy)](http://www.ntop.org/products/packet-capture/pf_ring/pf_ring-zc-zero-copy/)   -  PF_RING ZC（零拷贝）是一种灵活的数据包处理框架，允许您以任何数据包大小实现1/10 Gbit线速数据包处理（RX和TX）.  它实现零拷贝操作，包括进程间和VM间（KVM）通信的模式.
- [PACKET_MMAP/TPACKET/AF_PACKET](http://lxr.free-electrons.com/source/Documentation/networking/packet_mmap.txt) - 使用PACKET_MMAP来提高Linux中捕获和传输过程的性能是很好的.
- [netmap](http://info.iet.unipi.it/~luigi/netmap/)   -  netmap是高速数据包I / O的框架.  与其配套的VALE软件开关一起，它作为单个内核模块实现，可用于FreeBSD，Linux和Windows.

### Firewall
- [pfSense](https://www.pfsense.org/) - 防火墙和路由器FreeBSD分发.
- [OPNsense](https://opnsense.org/)   - 是一个开源，易于使用且易于构建的基于FreeBSD的防火墙和路由平台.  OPNsense包括昂贵的商业防火墙中提供的大多数功能，在许多情况下更多.  它带来了丰富的商业产品功能集，具有开放和可验证来源的优势.
- [fwknop](https://www.cipherdyne.org/fwknop/) - 通过防火墙中的单数据包授权保护端口.

### Anti-Spam
- [SpamAssassin](https://spamassassin.apache.org/) - 功能强大且流行的垃圾邮件过滤器，采用多种检测技术.


### Docker Images for Penetration Testing & Security
- `docker pull kalilinux / kali-linux-docker` [official Kali Linux](https://hub.docker.com/r/kalilinux/kali-linux-docker/)
- `docker pull owasp / zap2docker-stable`  -  [official OWASP ZAP](https://github.com/zaproxy/zaproxy)
- `docker pull wpscanteam / wpscan`  -  [official WPScan](https://hub.docker.com/r/wpscanteam/wpscan/)
- `docker pull remnux / metasploit`  -  [docker-metasploit](https://hub.docker.com/r/remnux/metasploit/)
- `docker pull citizenstig/dvwa` - [Damn Vulnerable Web Application (DVWA)](https://hub.docker.com/r/citizenstig/dvwa/)
- `docker pull wpscanteam / vulnerabilitywordpress`  -  [Vulnerable WordPress Installation](https://hub.docker.com/r/wpscanteam/vulnerablewordpress/)
- `docker pull hmlio / vaas-cve-2014-6271`  -  [Vulnerability as a service: Shellshock](https://hub.docker.com/r/hmlio/vaas-cve-2014-6271/)
- `docker pull hmlio / vaas-cve-2014-0160`  -  [Vulnerability as a service: Heartbleed](https://hub.docker.com/r/hmlio/vaas-cve-2014-0160/)
- `docker pull opendns / security-ninjas`  -  [Security Ninjas](https://hub.docker.com/r/opendns/security-ninjas/)
- `docker pull diogomonica / docker-bench-security`  -  [Docker Bench for Security](https://hub.docker.com/r/diogomonica/docker-bench-security/)
- `docker pull ismisepaul / securityshepherd`  -  [OWASP Security Shepherd](https://hub.docker.com/r/ismisepaul/securityshepherd/)
- `docker pull danmx / docker-owasp-webgoat`  -  [OWASP WebGoat Project docker image](https://hub.docker.com/r/danmx/docker-owasp-webgoat/)
- `docker-compose build &amp;&amp; docker-compose up`  -  [OWASP NodeGoat](https://github.com/owasp/nodegoat#option-3---run-nodegoat-on-docker)
- `docker pull citizenstig / nowasp`  -  [OWASP Mutillidae II Web Pen-Test Practice Application](https://hub.docker.com/r/citizenstig/nowasp/)
- `docker pull bkimminich / juice-shop`  -  [OWASP Juice Shop](https://hub.docker.com/r/bkimminich/juice-shop)


## Endpoint

### Anti-Virus / Anti-Malware

- [Linux Malware Detect](https://www.rfxn.com/projects/linux-malware-detect/) - 围绕共享托管环境中面临的威胁设计的针对Linux的恶意软件扫描程序.
- [LOKI](https://github.com/Neo23x0/Loki) - 妥协和事件响应扫描仪的简单指标


- [DocBleach](https://github.com/docbleach/DocBleach) - 开源内容撤防和重建软件，对Office，PDF和RTF文档进行清理.

### Configuration Management

- [Rudder](http://www.rudder-project.org/)   -  Rudder是一种易于使用，基于Web的，基于角色的IT基础架构自动化与合规性解决方案.  自动执行常见的系统管理任务（安装，配置）;  随着时间的推移实施配置（配置一次是好的，确保配置有效并自动修复它更好）;  所有受管节点的清单;  用于配置和管理节点及其配置的Web界面;  符合性报告，按配置和/或按节点.

### Authentication

- [google-authenticator](https://github.com/google/google-authenticator)   -  Google Authenticator项目包括针对多个移动平台的一次性密码生成器的实现，以及可插入的身份验证模块（PAM）.  使用由开放认证倡议（OATH）开发的开放标准（与OAuth无关）生成一次性密码.  这些实现支持RFC 4226中指定的基于HMAC的一次性密码（HOTP）算法和RFC 6238中指定的基于时间的一次性密码（TOTP）算法. [Tutorials: How to set up two-factor authentication for SSH login on Linux](http://xmodulo.com/two-factor-authentication-ssh-login-linux.html)

### Mobile / Android / iOS

- [android-security-awesome](https://github.com/ashishb/android-security-awesome)   -  android安全相关资源的集合.  学术界和工业界正在开展大量工作，用于执行Android应用程序的动态分析，静态分析和逆向工程.
- [SecMobi Wiki](http://wiki.secmobi.com/)   - 移动安全资源的集合，包括文章，博客，书籍，小组，项目，工具和会议.  *
- [OWASP Mobile Security Testing Guide](https://github.com/OWASP/owasp-mstg) - 移动应用安全测试和逆向工程的综合手册.
- [OSX Security Awesome](https://github.com/kai5263499/osx-security-awesome) -  OSX和iOS安全资源的集合
- [Themis](https://github.com/cossacklabs/themis) - 用于保护敏感数据的高级多平台加密框架：具有前向保密和安全数据存储的安全消息（AES256GCM），适用于构建端到端加密应用程序.
- [Mobile Security Wiki](https://mobilesecuritywiki.com/) - 移动安全资源的集合.
- [Apktool](https://github.com/iBotPeaches/Apktool) - 用于逆向工程Android apk文件的工具.
- [jadx](https://github.com/skylot/jadx) - 用于从Android Dex和Apk文件生成Java源代码的命令行和GUI工具.
- [enjarify](https://github.com/Storyyeller/enjarify) - 用于将Dalvik字节码转换为等效Java字节码的工具.
- [Android Storage Extractor](https://github.com/51j0/Android-Storage-Extractor) - 一键提取Android应用程序的本地数据存储的工具.

### Forensics

- [grr](https://github.com/google/grr) -  GRR快速响应是一个专注于远程实时取证的事件响应框架.
- [Volatility](https://github.com/volatilityfoundation/volatility) - 基于Python的内存提取和分析框架.
- [mig](http://mig.mozilla.org/)   -  MIG是一个在远程终端上进行调查手术的平台.  它使调查人员能够并行获取大量系统的信息，从而加快对事件和日常操作安全性的调查.
- [ir-rescue](https://github.com/diogo-fernan/ir-rescue) -  * ir-rescue *是Windows Batch脚本和Unix Bash脚本，用于在事件响应期间全面收集主机取证数据.
- [Logdissect](https://github.com/dogoncouch/logdissect) - 用于分析日志文件和其他数据的CLI实用程序和Python API.

## Threat Intelligence

- [abuse.ch](https://www.abuse.ch/) -  ZeuS Tracker / SpyEye Tracker / Palevo Tracker / Feodo Tracker跟踪世界各地的命令和控制服务器（主机），并为您提供域名和IP阻止列表.
- [Emerging Threats - Open Source](http://doc.emergingthreats.net/bin/view/Main/EmergingFAQ)   - 新兴威胁于10年前开始，作为收集Suricata和SNORT®规则，防火墙规则和其他IDS规则集的开源社区.  开源社区仍然在互联网安全方面发挥积极作用，每天有超过200,000名活跃用户下载规则集.  只要您遵循一些基本准则，ETOpen规则集对任何用户或组织开放.  我们的ETOpen规则集可随时下载.
- [PhishTank](http://www.phishtank.com/)   -  PhishTank是一个协作清算中心，用于处理有关互联网上网络钓鱼的数据和信息.  此外，PhishTank为开发人员和研究人员提供了一个开放的API，可以免费将反网络钓鱼数据集成到他们的应用程序中.
- [SBL / XBL / PBL / DBL / DROP / ROKSO](http://www.spamhaus.org/) - The Spamhaus Project is an international nonprofit organization whose mission is to track the Internet's spam operations and sources, to provide dependable realtime anti-spam protection for Internet networks, to work with Law Enforcement Agencies to identify and pursue spam and malware gangs worldwide, and to lobby governments for effective anti-spam legislation.
- [Internet Storm Center](https://www.dshield.org/reports.html)   - 在成功检测，分析和广泛警告Li0n蠕虫后，ISC于2001年创建.  今天，ISC为成千上万的互联网用户和组织提供免费的分析和警告服务，并积极与互联网服务提供商合作，以打击最恶意的攻击者.
- [AutoShun](https://www.autoshun.org/) -  AutoShun是一个Snort插件，允许您将Snort IDS日志发送到集中式服务器，该服务器将来自传感器日志的攻击与来自世界各地的其他snort传感器，蜜罐和邮件过滤器相关联.
- [DNS-BH](http://www.malwaredomains.com/)   -  DNS-BH项目创建并维护已知用于传播恶意软件和间谍软件的域列表.  此项目创建了对localhost的虚假回复所需的Bind和Windows区域文件，以获取对这些文件的任何请求，从而防止许多间谍软件安装和报告.
- [AlienVault Open Threat Exchange](http://www.alienvault.com/open-threat-exchange/dashboard) -  AlienVault开放式威胁交换（OTX），可帮助您保护网络免受恶意IP地址导致的数据丢失，服务中断和系统损害.
- [Tor Bulk Exit List](https://metrics.torproject.org/collector.html)   -  CollecTor，您在Tor网络中友好的数据收集服务.  CollecTor从公共Tor网络中的各种节点和服务中获取数据，并将其提供给全世界.  如果您正在研究Tor网络，或者您正在开发使用Tor网络数据的应用程序，那么这是您的起点. [TOR Node List](https://www.dan.me.uk/tornodes) /  [DNS Blacklists](https://www.dan.me.uk/dnsbl) / [Tor Node List](http://torstatus.blutmagie.de/)
- [leakedin.com](http://www.leakedin.com/)   -  leakedin.com的主要目的是让访问者了解丢失数据的风险.  此博客只汇编丢失或在pastebin.com等网站上披露的数据样本.
- [FireEye OpenIOCs](https://github.com/fireeye/iocs) - FireEye Publicly Shared Indicators of Compromise (IOCs)
- [OpenVAS NVT Feed](http://www.openvas.org/openvas-nvt-feed.html)   - 网络漏洞测试（NVT）的公共源.  它包含超过35,000个NVT（截至2014年4月），每天都在增长.  此Feed被配置为OpenVAS的默认值.
- [Project Honey Pot](http://www.projecthoneypot.org/)   -  Project Honey Pot是第一个也是唯一一个用于识别垃圾邮件发送者和垃圾邮件程序的分布式系统，用于从您的网站获取地址.  使用Project Honey Pot系统，您可以安装自定义标记为您站点访问者的时间和IP地址的地址.  如果其中一个地址开始接收电子邮件，我们不仅可以告知邮件是垃圾邮件，还可以告知收到地址的确切时刻以及收集邮件的IP地址.
- [virustotal](https://www.virustotal.com/)   -  Google的子公司VirusTotal是一项免费在线服务，可分析文件和URL，以识别由防病毒引擎和网站扫描程序检测到的病毒，蠕虫，特洛伊木马和其他类型的恶意内容.  同时，它可以用作检测误报的手段，即由一个或多个扫描仪检测为恶意的无害资源.
- [IntelMQ](https://github.com/certtools/intelmq/)   -  IntelMQ是CERT的解决方案，用于使用消息队列协议收集和处理安全提要，pastebins和推文.  这是一个名为IHAP（事件处理自动化项目）的社区驱动计划，该计划由欧洲CERT在几个InfoSec活动期间进行概念设计.  其主要目标是为事件响应人员提供一种简单的方法来收集和处理威胁情报，从而改善CERT的事件处理流程. [ENSIA Homepage](https://www.enisa.europa.eu/activities/cert/support/incident-handling-automation).
- [CIFv2](https://github.com/csirtgadgets/massive-octo-spice)   -  CIF是一个网络威胁情报管理系统.  CIF允许您组合来自许多来源的已知恶意威胁信息，并使用该信息进行识别（事件响应），检测（IDS）和缓解（空路由）.
- [CriticalStack](https://intel.criticalstack.com/) - 针对Bro网络安全监控平台的免费聚合威胁情报.
- [MISP - Open Source Threat Intelligence Platform ](https://www.misp-project.org/)   -  MISP威胁共享平台是一个免费的开源软件，可帮助共享威胁情报，包括网络安全指标.  用于收集，共享，存储和关联目标攻击，威胁情报，财务欺诈信息，漏洞信息甚至反恐信息的妥协指标的威胁情报平台.  MISP项目包括软件，通用库（[taxonomies](https://www.misp-project.org/taxonomies.html), [threat-actors and various malware](https://www.misp-project.org/galaxy.html)），一个广泛的数据模型，用于分享新信息 [objects](https://www.misp-project.org/objects.html) 和默认 [feeds](https://www.misp-project.org/feeds/).
- [PhishStats](https://phishstats.info/) - 网络钓鱼统计信息，搜索IP，域名和网站标题.

## Web

### Organization

- [OWASP](http://www.owasp.org) - 开放式网络应用安全项目（OWASP）是一家501（c）（3）全球非营利性慈善组织，致力于提高软件的安全性.

### Web Application Firewall

- [ModSecurity](http://www.modsecurity.org/) -  ModSecurity是用于实时Web应用程序监视，日志记录和访问控制的工具包.
- [NAXSI](https://github.com/nbs-system/naxsi) -  NAXSI是NGINX的开源，高性能，低规则维护WAF，NAXSI意味着Nginx Anti Xss和Sql Injection.
- [sql_firewall](https://github.com/uptimejp/sql_firewall) PostgreSQL的SQL防火墙扩展
- [ironbee](https://github.com/ironbee/ironbee)   -  IronBee是一个开源项目，用于构建通用Web应用程序安全传感器.  IronBee作为开发用于保护Web应用程序的系统的框架 - 用于构建Web应用程序防火墙（WAF）的框架.

### Scanning / Pentesting

- [sqlmap](http://sqlmap.org/)   -  sqlmap是一个开源的渗透测试工具，可以自动检测和利用SQL注入漏洞并接管数据库服务器.  它配备了强大的检测引擎，为终极渗透测试仪提供了许多利基功能，以及从数据库指纹识别，从数据库中获取数据到访问底层文件系统以及在操作系统上执行命令的各种交换机.带连接.
- [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)   -  Zed攻击代理（ZAP）是一种易于使用的集成渗透测试工具，用于查找Web应用程序中的漏洞.  它旨在供具有广泛安全经验的人员使用，因此非常适合那些不熟悉渗透测试的开发人员和功能测试人员.  ZAP提供自动扫描程序以及一组允许您手动查找安全漏洞的工具.
- [OWASP Testing Checklist v4](https://www.owasp.org/index.php/Testing_Checklist)   - 在Web漏洞评估期间要测试的一些控件列表.  可以找到Markdown版本 [here](https://github.com/amocrenco/owasp-testing-checklist-v4-markdown/blob/master/README.md).
- [w3af](http://w3af.org/)   -  w3af是一个Web应用程序攻击和审计框架.  该项目的目标是创建一个框架，通过查找和利用所有Web应用程序漏洞来帮助您保护Web应用程序.
- [Recon-ng](https://bitbucket.org/LaNMaSteR53/recon-ng)   -  Recon-ng是一个用Python编写的功能齐全的Web Reconnaissance框架.  Recon-ng的外观和感觉类似于Metasploit Framework.
- [PTF](https://github.com/trustedsec/ptf) -  Penetration Testers Framework（PTF）是一种模块化支持最新工具的方法.
- [Infection Monkey](https://github.com/guardicore/monkey)   - 用于绘图/笔测试网络的半自动笔测试工具.  模拟人类攻击者.
- [ACSTIS](https://github.com/tijme/angularjs-csti-scanner)   -  ACSTIS可帮助您扫描某些Web应用程序以获取AngularJS客户端模板注入（有时称为CSTI，沙箱转义或沙箱旁路）.  它支持扫描单个请求，但也为AngularJS CSTI漏洞爬网整个Web应用程序.

### Runtime Application Self-Protection

- [Sqreen](https://www.sqreen.io/)   -  Sqreen是面向软件团队的运行时应用程序自我保护（RASP）解决方案.  应用程序内代理程序可以监控应用程序.  报告可疑用户活动，并在运行时阻止攻击，无需修改代码或重定向流量.
- [OpenRASP](https://github.com/baidu/openrasp)   - 百度公司积极维护的开源RASP解决方案.通过上下文感知检测算法，该项目几乎没有误报.  在服务器负载较重的情况下，性能降低不到3％.

### Development

- [API Security in Action](https://www.manning.com/books/api-security-in-action)   - 书籍API安全性，包括安全开发，基于令牌的身份验证，JSON Web令牌，OAuth 2和Macaroons.  （早期访问，连续发布，2020年夏季最终发布）
- [Secure by Design](https://www.manning.com/books/secure-by-design?a_aid=danbjson&a_bid=0b3fac80)   - 书中标识了设计模式和编码样式，使得许多安全漏洞不太可能发生.  （早期访问，连续发布，2017年秋季发布）
- [Securing DevOps](https://www.manning.com/books/securing-devops)   - 本书探讨了如何将DevOps和Security的技术应用于一起，以使云服务更安全.  （早期访问，连续发布，最终发布于2018年1月）
- [Understanding API Security](https://www.manning.com/books/understanding-api-security) - 免费电子书采样器，通过展示如何将API组合在一起以及如何使用OAuth协议来保护它们，为API安全在现实世界中的工作方式提供了一些背景.
- [OAuth 2 in Action](https://www.manning.com/books/oauth-2-in-action) - 从客户端，授权服务器和资源服务器的角度教您实际使用和部署OAuth 2的书.
- [OWASP ZAP Node API](https://github.com/zaproxy/zap-api-nodejs) - 利用此官方API，在您的NodeJS应用程序中利用OWASP Zed攻击代理（ZAP）.
- [GuardRails](https://github.com/apps/guardrails) - 一个GitHub应用程序，在Pull请求中提供安全反馈.


## Usability

- [Usable Security Course](https://pt.coursera.org/learn/usable-security)   - 课程中可用的安全课程.  非常适合那些寻求安全性和可用性如何交叉的人.


## Big Data

- [data_hacking](https://github.com/ClickSecurity/data_hacking) - 使用IPython，Pandas和Scikit的示例了解如何充分利用安全数据.
- [hadoop-pcap](https://github.com/RIPE-NCC/hadoop-pcap) -  Hadoop库读取数据包捕获（PCAP）文件.
- [Workbench](http://workbench.readthedocs.org/) - 面向安全研究和开发团队的可扩展python框架.
- [OpenSOC](https://github.com/OpenSOC/opensoc) -  OpenSOC集成了各种开源大数据技术，以便为安全监控和分析提供集中的工具.
- [Apache Metron (incubating)](https://github.com/apache/incubator-metron) -  Metron集成了各种开源大数据技术，为安全监控和分析提供了集中的工具.
- [Apache Spot (incubating)](https://github.com/apache/incubator-spot) -  Apache Spot是一个开源软件，用于利用流量和数据包分析的洞察力.
- [binarypig](https://github.com/endgameinc/binarypig)   -  Hadoop中可扩展的二进制数据提取.  通过Django，Twitter Bootstrap和Elasticsearch进行恶意软件处理和分析.

## DevOps

- [Securing DevOps](https://manning.com/books/securing-devops?a_aid=securingdevops&a_bid=1353bcd8) - 一本关于DevOps安全技术的书，它回顾了保护Web应用程序及其基础结构所使用的最新实践.

## Operating Systems

### Online resources

- [Security related Operating Systems @ Rawsec](http://rawsec.ml/en/security-related-os/) - 完整的安全相关操作系统列表
- [Best Linux Penetration Testing Distributions @ CyberPunk](https://n0where.net/best-linux-penetration-testing-distributions/) - 主要渗透测试分布的描述
- [Security @ Distrowatch](http://distrowatch.com/search.php?category=Security) - 致力于讨论，审查和跟上开源操作系统的网站


## Datastores

- [blackbox](https://github.com/StackExchange/blackbox) - 使用GPG在VCS仓库中安全存储机密
- [confidant](https://github.com/lyft/confidant) - 在AWS DynamoDB中存储机密，在静态时加密并与IAM集成
- [dotgpg](https://github.com/ConradIrwin/dotgpg) - 一种安全，轻松地备份和版本化生产机密或共享密码的工具.
- [redoctober](https://github.com/cloudflare/redoctober) - 用于双人规则样式文件加密和解密的服务器.
- [aws-vault](https://github.com/99designs/aws-vault) - 将AWS凭证存储在OSX Keychain或加密文件中
- [credstash](https://github.com/fugue/credstash) - 使用AWS KMS和DynamoDB存储机密
- [chamber](https://github.com/segmentio/chamber) - 使用AWS KMS和SSM参数存储来存储机密
- [Safe](https://github.com/starkandwayne/safe) - 一个Vault CLI，可以更容易地读取和写入Vault.
- [Sops](https://github.com/mozilla/sops) - 使用AWS KMS和PGP支持YAML，JSON和BINARY格式和加密的加密文件编辑器.
- [passbolt](https://www.passbolt.com/)   - 您的团队正在等待的密码管理器.  基于OpenPGP的免费，开源，可扩展.
- [passpie](https://github.com/marcwebbie/passpie) - 多平台命令行密码管理器
- [Vault](https://www.vaultproject.io/) - 加密的数据存储，足以保存环境和应用程序机密.

## EBooks

- [Holistic Info-Sec for Web Developers](https://holisticinfosecforwebdevelopers.com/) - 免费和可下载的书籍系列，对Web开发人员和DevOps工程师需要了解的内容进行广泛而深入的介绍，以便创建稳定，可靠，可维护和安全的软件，网络和其他，按时交付，没有讨厌惊喜
- [Docker Security - Quick Reference: For DevOps Engineers](https://binarymist.io/publication/docker-security/) - 一本关于理解Docker安全性默认值，如何改进它们（理论和实践）以及许多工具和技术的书.  
- [How to Hack Like a Pornstar](https://books2read.com/u/bWzdBx) - 分步进入BANK的一步一步流程，Sparc Flow，2017  
- [How to Hack Like a Legend](https://amzn.to/2uWh1Up) - 一个黑客的故事闯入一个秘密的离岸公司，Sparc Flow，2018年  
- [How to Investigate Like a Rockstar](https://books2read.com/u/4jDWoZ) - 实现真正的危机，掌握法医分析的秘密，Sparc Flow，2017
- [Real World Cryptography](https://www.manning.com/books/real-world-cryptography) - 这本早期访问的书籍教您应用加密技术，以便在系统和应用程序的各个层面理解和应用安全性.

## Other Awesome Lists

### Other Security Awesome Lists

- [Android Security Awesome](https://github.com/ashishb/android-security-awesome) -  android安全相关资源的集合.
- [Awesome ARM Exploitation](https://github.com/HenryHoggard/awesome-arm-exploitation) -  ARM开发资源的精选列表.
- [Awesome CTF](https://github.com/apsdehal/awesome-ctf) -  CTF框架，库，资源和软件的精选列表.
- [Awesome Cyber Skills](https://github.com/joe-shenouda/awesome-cyber-skills) - 精选的黑客环境列表，您可以合法安全地训练您的网络技能.
- [Awesome Hacking](https://github.com/carpedm20/awesome-hacking) - 精选黑客教程，工具和资源的精选列表.
- [Awesome Honeypots](https://github.com/paralax/awesome-honeypots) - 一个很棒的蜜罐资源列表.
- [Awesome Malware Analysis](https://github.com/rshipp/awesome-malware-analysis) - 精选恶意软件分析工具和资源的精选列表.
- [Awesome PCAP Tools](https://github.com/caesar0301/awesome-pcaptools) - 计算机科学领域其他研究人员开发的一系列工具，用于处理网络痕迹.
- [Awesome Pentest](https://github.com/enaqx/awesome-pentest) - 一系列令人敬畏的渗透测试资源，工具和其他闪亮的东西.
- [Awesome Linux Containers](https://github.com/Friz-zy/awesome-linux-containers) - 精选的Linux容器框架，库和软件的精选列表.
- [Awesome Incident Response](https://github.com/meirwah/awesome-incident-response) - 事件响应资源的策划列表.
- [Awesome Web Hacking](https://github.com/infoslack/awesome-web-hacking) - 此列表适用于希望了解Web应用程序安全性但没有起点的任何人.
- [Awesome Threat Intelligence](https://github.com/hslatman/awesome-threat-intelligence) - 策划的威胁情报资源列表.
- [Awesome Threat Modeling](https://github.com/redshiftzero/awesome-threat-modeling) - 威胁建模资源的策划列表.
- [Awesome Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) - 收集用于测试的备忘单
- [Awesome Industrial Control System Security](https://github.com/mpesen/awesome-industrial-control-system-security) - 与工业控制系统（ICS）安全相关的精选资源列表.
- [Awesome YARA](https://github.com/InQuest/awesome-yara) - A curated list of awesome YARA rules, tools, and people.
- [Awesome Threat Detection and Hunting](https://github.com/0x4D31/awesome-threat-detection) - 精选威胁检测和狩猎资源的精选列表.
- [Awesome Container Security](https://github.com/kai5263499/container-security-awesome) - 与容器构建和运行时安全性相关的精彩资源的策划列表
- [Awesome Crypto Papers](https://github.com/pFarb/awesome-crypto-papers) - 密码学论文，文章，教程和howtos的精选列表.
- [Awesome Shodan Search Queries](https://github.com/jakejarvis/awesome-shodan-queries) - 一系列有趣，有趣，令人沮丧的搜索查询，可插入Shodan.io.

### Other Common Awesome Lists

其他令人惊讶的精彩列表：

- [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) -  awesome- *或* -awesome列表.
- [lists](https://github.com/jnv/lists) - 在GitHub上策划的（真棒）列表的最终列表.
- [Movies For Hacker](https://github.com/k4m4/movies-for-hackers) - 每个黑客和赛博朋克必须观看的精选电影列表.

## [Contributing](https://github.com/sbilly/awesome-security/blob/master/contributing.md)

欢迎您的贡献！
