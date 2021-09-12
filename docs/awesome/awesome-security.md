<div class="github-widget" data-repo="sbilly/awesome-security"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Security

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

一组很棒的软件、图书馆、文档、书籍、资源和关于安全的很酷的东西.

灵感来自 [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python).

谢谢大家 [contributors](https://github.com/sbilly/awesome-security/graphs/contributors) ，你太棒了，没有你就不可能！ 目标是建立一个由社区驱动的非常知名资源的分类集合.


------

## Network

### Scanning / Pentesting

- [OpenVAS](http://www.openvas.org/) - OpenVAS 是一个包含多种服务和工具的框架，可提供全面而强大的漏洞扫描和漏洞管理解决方案.
- [Metasploit Framework](https://github.com/rapid7/metasploit-framework) - A tool for developing and executing exploit code against a remote target machine. Other important sub-projects include the Opcode Database, shellcode archive and related research.
- [Kali](https://www.kali.org/)  - Kali Linux 是一个源自 Debian 的 Linux 发行版，专为数字取证和渗透测试而设计.  Kali Linux 预装了许多渗透测试程序，包括 nmap（端口扫描器）、Wireshark（数据包分析器）、John the Ripper（密码破解程序）和 Aircrack-ng（用于渗透测试无线 LAN 的软件套件） .
- [pig](https://github.com/rafael-santiago/pig) - Linux 数据包制作工具.
- [scapy](https://github.com/gpotter2/awesome-scapy) - Scapy：基于 python 的交互式数据包操作程序和库.
- [Pompem](https://github.com/rfunix/Pompem)  - Pompem 是一个开源工具，旨在自动搜索主要数据库中的漏洞. 用 Python 开发，具有高级搜索系统，从而促进渗透测试者和道德黑客的工作. 在其当前版本中，在数据库中执行搜索：Exploit-db、1337day、Packetstorm Security...
- [Nmap](https://nmap.org) - Nmap 是一个免费的开源实用程序，用于网络发现和安全审计.
- [Amass](https://github.com/caffix/amass) - Amass 通过抓取最大数量的不同数据源、递归暴力破解、网络档案抓取、排列和更改名称、反向 DNS 扫描和其他技术来执行 DNS 子域枚举.
- [Anevicon](https://github.com/rozgo/anevicon) - 最强大的基于 UDP 的负载生成器，用 Rust 编写.
- [Finshir](https://github.com/isgasho/finshir) - 一个协程驱动的 Low &amp; Slow 流量生成器，用 Rust 编写.
- [Legion](https://github.com/GoVanguard/legion) - 开源半自动发现和侦察网络渗透测试框架.
- [Sublist3r](https://github.com/aboul3la/Sublist3r) - 渗透测试人员的快速子域枚举工具
- [RustScan](https://github.com/RustScan/RustScan)  - 使用 Rust 进行更快的 Nmap 扫描. 将 17 分钟的 Nmap 扫描缩短到 19 秒.
- [Boofuzz](https://github.com/jtpereyda/boofuzz) - 模糊引擎和模糊测试框架.
- [monsoon](https://github.com/RedTeamPentesting/monsoon) - 非常灵活和快速的交互式 HTTP 枚举/模糊测试.
- [Netz](https://github.com/spectralops/netz)- 使用 zgrab2 和其他工具发现 Internet 范围内的错误配置.

### Monitoring / Logging

- [justniffer](http://justniffer.sourceforge.net/) - Justniffer 是一种网络协议分析器，可以捕获网络流量并以自定义方式生成日志，可以模拟 Apache Web 服务器日志文件，跟踪响应时间并从 HTTP 流量中提取所有“拦截”文件.
- [httpry](http://dumpsterventures.com/jason/httpry/)  - httpry 是一个专门的数据包嗅探器，用于显示和记录 HTTP 流量. 它本身并不用于执行分析，而是用于捕获、解析和记录流量以供以后分析. 它可以在解析流量时实时运行，显示流量，也可以作为记录到输出文件的守护进程运行. 它被编写为尽可能轻量级和灵活，以便它可以轻松适应不同的应用程序.
- [ngrep](http://ngrep.sourceforge.net/)  - ngrep 努力提供 GNU grep 的大部分共同特性，并将它们应用到网络层.  ngrep 是一个 pcap-aware 工具，它允许你指定扩展的正则或十六进制表达式来匹配数据包的数据负载. 它目前识别 IPv4/6、TCP、UDP、ICMPv4/6、IGMP 和 Raw 跨以太网、PPP、SLIP、FDDI、令牌环和空接口，并以与更常见的数据包嗅探工具相同的方式理解 BPF 过滤器逻辑，例如作为 tcpdump 和 snoop.
- [passivedns](https://github.com/gamelinux/passivedns)  - 一种被动收集 DNS 记录以帮助事件处理、网络安全监控 (NSM) 和一般数字取证的工具.  PassiveDNS 嗅探来自接口的流量或读取 pcap 文件并将 DNS 服务器响应输出到日志文件.  PassiveDNS 可以在内存中缓存/聚合重复的 DNS 答案，限制日志文件中的数据量而不会丢失 DNS 答案中的essens.
- [sagan](http://sagan.quadrantsec.com/) - Sagan 使用“类似 Snort”的引擎和规则来分析日志（系统日志/事件日志/snmptrap/netflow/等）.
- [Node Security Platform](https://nodesecurity.io/) - 与 Snyk 类似的功能集，但在大多数情况下免费，对其他人来说非常便宜.
- [ntopng](http://www.ntop.org/products/traffic-analysis/ntop/) - Ntopng 是一个显示网络使用情况的网络流量探测器，类似于流行的 top Unix 命令所做的.
- [Fibratus](https://github.com/rabbitstack/fibratus)  - Fibratus 是一个用于探索和跟踪 Windows 内核的工具. 它能够捕获大部分 Windows 内核活动 - 进程/线程创建和终止、文件系统 I/O、注册表、网络活动、DLL 加载/卸载等等.  Fibratus 有一个非常简单的 CLI，它封装了启动内核事件流收集器、设置内核事件过滤器或运行称为 filaments 的轻量级 Python 模块的机制.
- [opensnitch](https://github.com/evilsocket/opensnitch) - OpenSnitch 是 Little Snitch 应用程序防火墙的 GNU/Linux 端口

### IDS / IPS / Host IDS / Host IPS

- [Snort](https://www.snort.org/)  - Snort是Martin Roesch于1998年创建的一个免费开源的网络入侵防御系统（NIPS）和网络入侵检测系统（NIDS）.Snort现在由Sourcefire开发，Roesch是其创始人兼CTO.  2009 年，Snort 作为“有史以来最伟大的[部分] 开源软件”之一进入了 InfoWorld 的开源名人堂.
- [Zeek](https://zeek.org/) - Zeek 是一个强大的网络分析框架，它与您可能知道的典型 IDS 有很大不同.
- [OSSEC](https://ossec.github.io/)  - 全面的开源 HIDS. 不适合胆小的人. 需要一点时间来了解它的工作原理. 执行日志分析、文件完整性检查、策略监控、rootkit 检测、实时警报和主动响应. 它可以在大多数操作系统上运行，包括 Linux、MacOS、Solaris、HP-UX、AIX 和 Windows. 大量合理的文件. 甜蜜点是大中型部署.
- [Suricata](http://suricata-ids.org/)  - Suricata 是一个高性能的网络 IDS、IPS 和网络安全监控引擎. 开源并由社区运营的非营利基金会拥有，即开放信息安全基金会 (OISF).  Suricata 由 OISF 及其支持供应商开发.
- [Security Onion](http://blog.securityonion.net/)  - Security Onion 是一个用于入侵检测、网络安全监控和日志管理的 Linux 发行版. 它基于 Ubuntu，包含 Snort、Suricata、Zeek、OSSEC、Sguil、Squet、Snorby、ELSA、Xplico、NetworkMiner 和许多其他安全工具. 易于使用的设置向导可让您在几分钟内为您的企业构建大量分布式传感器！
- [sshwatch](https://github.com/marshyski/sshwatch)  - 类似于用 Python 编写的 DenyHosts 的 SSH IPS. 它还可以在日志中收集有关攻击者在攻击期间的信息.
- [Stealth](https://fbb-git.github.io/stealth/)  - 文件完整性检查器，几乎不会留下任何沉淀物. 控制器在另一台机器上运行，这使得攻击者很难知道文件系统正在通过 SSH 以定义的伪随机间隔进行检查. 强烈推荐用于中小型部署.
- [AIEngine](https://bitbucket.org/camp0/aiengine) - AIEngine 是下一代交互式/可编程 Python/Ruby/Java/Lua 数据包检查引擎，具有无需任何人工干预的学习能力、NIDS（网络入侵检测系统）功能、DNS 域分类、网络收集器、网络取证等.
- [Denyhosts](http://denyhosts.sourceforge.net/) - 阻止基于 SSH 字典的攻击和蛮力攻击.
- [Fail2Ban](http://www.fail2ban.org/wiki/index.php/Main_Page) - 扫描日志文件并对显示恶意行为的 IP 采取措施.
- [SSHGuard](http://www.sshguard.net/) - 除了 SSH 之外的保护服务的软件，用 C 编写
- [Lynis](https://cisofy.com/lynis/) - Linux/Unix 的开源安全审计工具.

### Honey Pot / Honey Net

- [awesome-honeypots](https://github.com/paralax/awesome-honeypots) - 标准的很棒的蜜罐列表.
- [HoneyPy](https://github.com/foospidy/HoneyPy)  - HoneyPy 是一个中低交互蜜罐. 它旨在易于：部署、使用插件扩展功能以及应用自定义配置.
- [Conpot](http://conpot.org/)  - ICS/SCADA 蜜罐.  Conpot 是一个低交互服务器端工业控制系统蜜罐，旨在易于部署、修改和扩展. 通过提供一系列通用工业控制协议，我们为构建您自己的系统奠定了基础，能够模拟复杂的基础设施，让对手相信他刚刚发现了一个巨大的工业综合体. 为了提高欺骗能力，我们还提供了服务自定义人机界面以增加蜜罐攻击面的可能性. 可以人为地延迟服务的响应时间，以模拟系统在恒定负载下的行为. 因为我们提供完整的协议栈，Conpot 可以通过高效的 HMI 访问或使用真实硬件进行扩展.  Conpot 是在 Honeynet 项目的保护伞下和几个非常大的巨头的肩膀上开发的.
- [Amun](https://github.com/zeroq/amun) - 基于 Amun Python 的低交互蜜罐.
- [Glastopf](http://glastopf.org/)  - Glastopf 是一个蜜罐，它模拟数千个漏洞，从针对 Web 应用程序的攻击中收集数据. 其背后的原理非常简单：对利用 Web 应用程序的攻击者做出正确的响应.
- [Kippo](https://github.com/desaster/kippo) - Kippo 是一个中等交互 SSH 蜜罐，旨在记录暴力攻击，最重要的是，攻击者执行的整个 shell 交互.
- [Kojoney](http://kojoney.sourceforge.net/)  - Kojoney 是一个模拟 SSH 服务器的低级交互蜜罐. 该守护进程是使用 Twisted Conch 库用 Python 编写的.
- [HonSSH](https://github.com/tnich/honssh)  - HonSSH 是一种高交互蜜罐解决方案.  HonSSH 将位于攻击者和蜜罐之间，在它们之间创建两个单独的 SSH 连接.
- [Bifrozt](http://sourceforge.net/projects/bifrozt/)  - Bifrozt 是一种带有 DHCP 服务器的 NAT 设备，通常部署有一个 NIC 直接连接到 Internet，一个 NIC 连接到内部网络.  Bifrozt 与其他标准 NAT 设备的不同之处在于它能够在攻击者和您的蜜罐之间充当透明的 SSHv2 代理. 如果您在 Bifrozt 的内部网络上部署了 SSH 服务器，它将以纯文本形式将所有交互记录到 TTY 文件中，以便稍后查看，并捕获下载的任何文件的副本. 您不必在内部 SSH 服务器上安装任何额外的软件、编译任何内核模块或使用特定版本或类型的操作系统来实现这一点. 它会将出站流量限制在一定数量的端口上，并在超出某些限制时开始丢弃这些端口上的出站数据包.
- [HoneyDrive](http://bruteforce.gr/honeydrive)  - HoneyDrive 是首屈一指的蜜罐 Linux 发行版. 它是一个安装了 Xubuntu Desktop 12.04.4 LTS 版本的虚拟设备 (OVA). 它包含 10 多个预安装和预配置的蜜罐软件包，例如 Kippo SSH 蜜罐、Dionaea 和 Amun 恶意软件蜜罐、Honeyd 低交互蜜罐、Glastopf 网络蜜罐和 Wordpot、Conpot SCADA/ICS 蜜罐、Thug 和 PhoneyC 蜜罐等等. 此外，它还包括许多有用的预配置脚本和实用程序，用于分析、可视化和处理它可以捕获的数据，例如 Kippo-Graph、Honeyd-Viz、DionaeaFR、ELK 堆栈等等. 最后，分发中还提供了近 90 种著名的恶意软件分析、取证和网络监控相关工具.
- [Cuckoo Sandbox](http://www.cuckoosandbox.org/)  - Cuckoo Sandbox 是一个开源软件，用于自动分析可疑文件. 为此，它使用自定义组件来监视在隔离环境中运行时恶意进程的行为.
- [T-Pot Honeypot Distro](http://dtag-dev-sec.github.io/mediator/feature/2017/11/07/t-pot-17.10.html)  - T-Pot 基于 Ubuntu Server 16/17.x LTS 的网络安装程序. 蜜罐守护进程以及其他正在使用的支持组件已使用 docker 进行容器化. 这允许我们在同一网络接口上运行多个蜜罐守护进程，同时保持较小的占用空间并将每个蜜罐限制在其自己的环境中. 在 vanilla Ubuntu 上安装 - [T-Pot Autoinstall](https://github.com/dtag-dev-sec/t-pot-autoinstall)  - 此脚本将在全新的 Ubuntu 16.04.x LTS（64 位）上安装 T-Pot 16.04/17.10. 它旨在用于托管服务器，其中提供了 Ubuntu 基础映像并且无法安装自定义 ISO 映像. 在 VMware 中的 vanilla Ubuntu 16.04.3 上成功测试.

### Full Packet Capture / Forensic

- [tcpflow](https://github.com/simsong/tcpflow)  - tcpflow 是一个程序，它捕获作为 TCP 连接（流）的一部分传输的数据，并以便于协议分析和调试的方式存储数据. 每个 TCP 流都存储在自己的文件中. 因此，典型的 TCP 流将存储在两个文件中，每个方向一个.  tcpflow 还可以处理存储的“tcpdump”数据包流.
- [Xplico](http://www.xplico.org/)  - Xplico 的目标是从互联网流量中提取包含的应用程序数据. 例如，Xplico 从 pcap 文件中提取每封电子邮件（POP、IMAP 和 SMTP 协议）、所有 HTTP 内容、每个 VoIP 呼叫 (SIP)、FTP、TFTP 等.  Xplico 不是网络协议分析器.  Xplico 是一种开源网络取证分析工具 (NFAT).
- [Moloch](https://github.com/aol/moloch)  - Moloch 是一个开源、大规模的 IPv4 数据包捕获 (PCAP)、索引和数据库系统. 为 PCAP 浏览、搜索和导出提供了一个简单的 Web 界面. 公开的 API 允许直接下载 PCAP 数据和 JSON 格式的会话数据. 通过使用 HTTPS 和 HTTP 摘要密码支持或使用前面的 apache 来实现简单的安全性.  Moloch 并不是要取代 IDS 引擎，而是与它们一起工作，以标准 PCAP 格式存储和索引所有网络流量，提供快速访问.  Moloch 旨在跨多个系统部署，并且可以扩展以处理多千兆位/秒的流量.
- [OpenFPC](http://www.openfpc.org)  - OpenFPC 是一组工具，结合起来提供一个轻量级的全包网络流量记录器和缓冲系统. 它的设计目标是允许非专家用户在 COTS 硬件上部署分布式网络流量记录器，同时集成到现有的警报和日志管理工具中.
- [Dshell](https://github.com/USArmyResearchLab/Dshell)  - Dshell 是一个网络取证分析框架. 实现插件的快速开发，以支持网络数据包捕获的剖析.
- [stenographer](https://github.com/google/stenographer) - Stenographer 是一种数据包捕获解决方案，旨在快速将所有数据包假脱机到磁盘，然后提供对这些数据包子集的简单、快速访问.

### Sniffer

- [wireshark](https://www.wireshark.org)  - Wireshark 是一个免费的开源数据包分析器. 它用于网络故障排除、分析、软件和通信协议开发以及教育.  Wireshark 与 tcpdump 非常相似，但具有图形前端，以及一些集成的排序和过滤选项.
- [netsniff-ng](http://netsniff-ng.org/)  - netsniff-ng 是一个免费的 Linux 网络工具包，如果您愿意，它是您日常 Linux 网络管道的瑞士军刀. 它的性能增益是通过零复制机制实现的，因此在数据包接收和传输时，内核不需要将数据包从内核空间复制到用户空间，反之亦然.
- [Live HTTP headers ](https://addons.mozilla.org/en-US/firefox/addon/http-header-live/)  - Live HTTP 标头是一个免费的 Firefox 插件，可以实时查看您的浏览器请求. 它显示了请求的整个标头，可用于查找实现中的安全漏洞.

### Security Information & Event Management

- [Prelude](https://www.prelude-siem.org/)  - Prelude 是一个通用的“安全信息和事件管理”(SIEM) 系统.  Prelude 收集、规范化、分类、汇总、关联和报告所有与安全相关的事件，独立于导致此类事件的产品品牌或许可；  Prelude 是“无代理”.
- [OSSIM](https://www.alienvault.com/open-threat-exchange/projects) - OSSIM 提供了安全专业人员从 SIEM 产品中需要的所有功能 - 事件收集、规范化和关联.
- [FIR](https://github.com/certsocietegenerale/FIR) - Fast Incident Response，一个网络安全事件管理平台.
- [LogESP](https://github.com/dogoncouch/LogESP) - 开源 SIEM（安全信息和事件管理系统）.

### VPN

- [OpenVPN](https://openvpn.net/)  - OpenVPN 是一个开源软件应用程序，它实现了虚拟专用网络 (VPN) 技术，用于在路由或桥接配置和远程访问设施中创建安全的点对点或站点到站点连接. 它使用使用 SSL/TLS 进行密钥交换的自定义安全协议.

### Fast Packet Processing

- [DPDK](http://dpdk.org/) - DPDK 是一组用于快速数据包处理的库和驱​​动程序.
- [PFQ](https://github.com/pfq/PFQ) - PFQ 是一个为 Linux 操作系统设计的功能网络框架，它允许高效的数据包捕获/传输（10G 及以上）、内核功能处理和跨套接字/端点的数据包转向.
- [PF_RING](http://www.ntop.org/products/packet-capture/pf_ring/) - PF_RING 是一种新型的网络套接字，可显着提高数据包捕获速度.
- [PF_RING ZC (Zero Copy)](http://www.ntop.org/products/packet-capture/pf_ring/pf_ring-zc-zero-copy/)  - PF_RING ZC (Zero Copy) 是一个灵活的数据包处理框架，允许您在任何数据包大小下实现 1/10 Gbit 线速数据包处理（RX 和 TX）. 它实现了零复制操作，包括用于进程间和 VM 间 (KVM) 通信的模式.
- [PACKET_MMAP/TPACKET/AF_PACKET](https://elixir.bootlin.com/linux/latest/source/Documentation/networking/packet_mmap.rst) - 可以使用PACKET_MMAP 来提高Linux 中捕获和传输过程的性能.
- [netmap](http://info.iet.unipi.it/~luigi/netmap/)  - netmap 是一个用于高速数据包 I/O 的框架. 与其配套的 VALE 软件开关一起，它作为单个内核模块实现，可用于 FreeBSD、Linux 和现在的 Windows.

### Firewall

- [pfSense](https://www.pfsense.org/) - 防火墙和路由器 FreeBSD 发行版.
- [OPNsense](https://opnsense.org/)  - 是一个开源的、易于使用且易于构建的基于 FreeBSD 的防火墙和路由平台.  OPNsense 包括昂贵的商业防火墙中可用的大部分功能，在许多情况下还有更多功能. 它带来了商业产品的丰富功能集以及开放和可验证来源的好处.
- [fwknop](https://www.cipherdyne.org/fwknop/) - 通过防火墙中的单包授权保护端口.

### Anti-Spam

- [Spam Scanner](https://github.com/spamscanner) - 反垃圾邮件扫描服务和反垃圾邮件 API [@niftylettuce](https://github.com/niftylettuce).
- [rspamd](https://github.com/rspamd/rspamd) - 快速、免费和开源的垃圾邮件过滤系统.
- [SpamAssassin](https://spamassassin.apache.org/) - 采用多种检测技术的强大且流行的垃圾邮件过滤器.
- [Scammer-List](https://scammerlist.now.sh/) - 一个免费的开源基于人工智能的诈骗和垃圾邮件查找器，带有免费的 API

### Docker Images for Penetration Testing & Security

- `docker pull kalilinux/kali-linux-docker` [official Kali Linux](https://hub.docker.com/r/kalilinux/kali-linux-docker/)
-`docker pull owasp/zap2docker-stable` - [official OWASP ZAP](https://github.com/zaproxy/zaproxy)
-`docker pull wpscanteam/wpscan` - [official WPScan](https://hub.docker.com/r/wpscanteam/wpscan/)
-`docker pull remnux/metasploit` - [docker-metasploit](https://hub.docker.com/r/remnux/metasploit/)
- `docker pull Citizentig/dvwa` - [Damn Vulnerable Web Application (DVWA)](https://hub.docker.com/r/citizenstig/dvwa/)
-`docker pull wpscanteam/vulnerablewordpress` - [Vulnerable WordPress Installation](https://hub.docker.com/r/wpscanteam/vulnerablewordpress/)
-`docker pull hmlio/vaas-cve-2014-6271` - [Vulnerability as a service: Shellshock](https://hub.docker.com/r/hmlio/vaas-cve-2014-6271/)
-`docker pull hmlio/vaas-cve-2014-0160` - [Vulnerability as a service: Heartbleed](https://hub.docker.com/r/hmlio/vaas-cve-2014-0160/)
-`docker pull opendns/security-ninjas` - [Security Ninjas](https://hub.docker.com/r/opendns/security-ninjas/)
-`docker pull diogomonica/docker-bench-security` - [Docker Bench for Security](https://hub.docker.com/r/diogomonica/docker-bench-security/)
- `docker pull ismisepaul/securityshepherd` - [OWASP Security Shepherd](https://hub.docker.com/r/ismisepaul/securityshepherd/)
-`docker pull danmx/docker-owasp-webgoat` - [OWASP WebGoat Project docker image](https://hub.docker.com/r/danmx/docker-owasp-webgoat/)
-`docker-compose build &amp;&amp; docker-compose up`- [OWASP NodeGoat](https://github.com/owasp/nodegoat#option-3---run-nodegoat-on-docker)
-`docker pull Citizentig/nowasp` - [OWASP Mutillidae II Web Pen-Test Practice Application](https://hub.docker.com/r/citizenstig/nowasp/)
-`docker pull bkimminich/juice-shop` - [OWASP Juice Shop](https://hub.docker.com/r/bkimminich/juice-shop)

## Endpoint

### Anti-Virus / Anti-Malware

- [Linux Malware Detect](https://www.rfxn.com/projects/linux-malware-detect/) - 针对共享托管环境中面临的威胁而设计的 Linux 恶意软件扫描程序.
- [LOKI](https://github.com/Neo23x0/Loki) - 妥协和事件响应扫描仪的简单指标
- [rkhunter](http://rkhunter.sourceforge.net/) - 适用于 Linux 的 Rootkit Hunter


- [DocBleach](https://github.com/docbleach/DocBleach) - 一个开源的内容解除和重建软件，用于清理 Office、PDF 和 RTF 文档.

### Configuration Management

- [Rudder](http://www.rudder-project.org/)  - Rudder 是一种易于使用、基于 Web 的、基于角色的 IT 基础架构自动化与合规性解决方案. 自动化常见的系统管理任务（安装、配置）； 随着时间的推移强制配置（配置一次就好，确保配置有效并自动修复它更好）； 所有受管节点的清单； 用于配置和管理节点及其配置的 Web 界面； 合规性报告，按配置和/或按节点.

### Authentication

- [google-authenticator](https://github.com/google/google-authenticator)  - Google Authenticator 项目包括用于多个移动平台的一次性密码生成器的实现，以及一个可插拔的身份验证模块 (PAM). 一次性密码是使用开放身份验证倡议 (OATH)（与 OAuth 无关）开发的开放标准生成的. 这些实现支持 RFC 4226 中指定的基于 HMAC 的一次性密码 (HOTP) 算法和 RFC 6238 中指定的基于时间的一次性密码 (TOTP) 算法. [Tutorials: How to set up two-factor authentication for SSH login on Linux](http://xmodulo.com/two-factor-authentication-ssh-login-linux.html)
- [Stegcloak](https://github.com/kurolabs/stegcloak) - 安全地将数字真实性分配给任何书面文本

### Mobile / Android / iOS

- [android-security-awesome](https://github.com/ashishb/android-security-awesome)  - 安卓安全相关资源的集合. 学术界和工业界正在开展大量工作，研究用于执行 Android 应用程序的动态分析、静态分析和逆向工程的工具.
- [SecMobi Wiki](http://wiki.secmobi.com/)  - 移动安全资源的集合，包括文章、博客、书籍、群组、项目、工具和会议.  *
- [OWASP Mobile Security Testing Guide](https://github.com/OWASP/owasp-mstg) - 移动应用安全测试和逆向工程的综合手册.
- [OSX Security Awesome](https://github.com/kai5263499/osx-security-awesome) - OSX 和 iOS 安全资源的集合
- [Themis](https://github.com/cossacklabs/themis) - 用于保护敏感数据的高级多平台加密框架：具有前向保密和安全数据存储（AES256GCM）的安全消息传递，适用于构建端到端加密应用程序.
- [Mobile Security Wiki](https://mobilesecuritywiki.com/) - 移动安全资源的集合.
- [Apktool](https://github.com/iBotPeaches/Apktool) - 逆向工程安卓apk文件的工具.
- [jadx](https://github.com/skylot/jadx) - 用于从 Android Dex 和 Apk 文件生成 Java 源代码的命令行和 GUI 工具.
- [enjarify](https://github.com/Storyyeller/enjarify) - 将 Dalvik 字节码转换为等效的 Java 字节码的工具.
- [Android Storage Extractor](https://github.com/51j0/Android-Storage-Extractor) - 一键提取Android应用程序本地数据存储的工具.
- [Quark-Engine](https://github.com/quark-engine/quark-engine) - 一个混淆忽略的 Android 恶意软件评分系统.
- [dotPeek](https://www.jetbrains.com/decompiler/) - 基于 ReSharper 捆绑反编译器的免费独立工具.
- [hardened_malloc](https://github.com/GrapheneOS/hardened_malloc)  - 专为现代系统设计的强化分配器. 它已集成到 Android 的 Bionic libc 中，并且可以在外部与 musl 和 glibc 一起用作动态库，以便在其他基于 Linux 的平台上使用. 随着时间的推移，它将获得更多的可移植性/集成性.
- [AMExtractor](https://github.com/ir193/AMExtractor) - 即使没有内核源代码，AMExtractor 也可以转储 Android 设备的物理内容.
- [frida](https://github.com/frida/frida) - 面向开发人员、逆向工程师和安全研究人员的动态检测工具包.
- [UDcide](https://github.com/UDcide/udcide) - Android 恶意软件行为编辑器.

### Forensics

- [grr](https://github.com/google/grr) - GRR Rapid Response 是一个专注于远程现场取证的事件响应框架.
- [Volatility](https://github.com/volatilityfoundation/volatility) - 基于 Python 的内存提取和分析框架.
- [mig](http://mig.mozilla.org/)  - MIG 是一个在远程端点上执行调查手术的平台. 它使调查人员能够同时从大量系统中获取信息，从而加快事件调查和日常运营安全.
- [ir-rescue](https://github.com/diogo-fernan/ir-rescue) - *ir-rescue* 是 Windows Batch 脚本和 Unix Bash 脚本，用于在事件响应期间全面收集主机取证数据.
- [Logdissect](https://github.com/dogoncouch/logdissect) - 用于分析日志文件和其他数据的 CLI 实用程序和 Python API.
- [Meerkat](https://github.com/TonyPhipps/Meerkat) - 基于 PowerShell 的 Windows 工件集合，用于威胁搜寻和事件响应.
- [Rekall](https://github.com/google/rekall) - The Rekall Framework is a completely open collection of tools, implemented in Python under the Apache and GNU General Public License, for the extraction and analysis of digital artifacts computer systems.
- [LiME](https://github.com/504ensicsLabs/LiME.git) - Linux 内存提取器

## Threat Intelligence

- [abuse.ch](https://www.abuse.ch/) - ZeuS Tracker / SpyEye Tracker / Palevo Tracker / Feodo Tracker 跟踪世界各地的命令和控制服务器（主机），并为您提供域和 IP 阻止列表.
- [Emerging Threats - Open Source](http://doc.emergingthreats.net/bin/view/Main/EmergingFAQ)  - Emerging Threats 始于 10 年前，它是一个开源社区，用于收集 Suricata 和 SNORT® 规则、防火墙规则和其他 IDS 规则集. 开源社区仍然在互联网安全方面发挥着积极作用，每天有超过 200,000 名活跃用户下载规则集.  ETOpen 规则集对任何用户或组织开放，只要您遵循一些基本准则. 我们的 ETOpen 规则集随时可供下载.
- [PhishTank](http://www.phishtank.com/)  - PhishTank 是一个协作信息交换所，用于收集有关 Internet 网络钓鱼的数据和信息. 此外，PhishTank 为开发人员和研究人员提供了一个开放的 API，可以将反网络钓鱼数据免费集成到他们的应用程序中.
- [SBL / XBL / PBL / DBL / DROP / ROKSO](http://www.spamhaus.org/) - Spamhaus Project 是一个国际非营利组织，其使命是跟踪 Internet 的垃圾邮件操作和来源，为 Internet 网络提供可靠的实时反垃圾邮件保护，与执法机构合作以识别和追查全球的垃圾邮件和恶意软件团伙，以及游说政府制定有效的反垃圾邮件立法.
- [Internet Storm Center](https://www.dshield.org/reports.html)  - 在成功检测、分析和广泛警告 Li0n 蠕虫后，ISC 于 2001 年创建. 今天，ISC 为数以千计的互联网用户和组织提供免费的分析和警告服务，并积极与互联网服务提供商合作以对抗最恶意的攻击者.
- [AutoShun](https://www.autoshun.org/) - AutoShun 是一个 Snort 插件，允许您将 Snort IDS 日志发送到中央服务器，该服务器会将来自传感器日志的攻击与来自世界各地的其他 Snort 传感器、蜜罐和邮件过滤器相关联.
- [DNS-BH](http://www.malwaredomains.com/)  - DNS-BH 项目创建并维护已知用于传播恶意软件和间谍软件的域列表. 该项目创建了 Bind 和 Windows 区域文件，为对这些请求的任何请求提供虚假回复到 localhost，从而防止许多间谍软件安装和报告.
- [AlienVault Open Threat Exchange](http://www.alienvault.com/open-threat-exchange/dashboard) - AlienVault Open Threat Exchange (OTX)，帮助您保护网络免受恶意 IP 地址造成的数据丢失、服务中断和系统危害.
- [Tor Bulk Exit List](https://metrics.torproject.org/collector.html)  - Collector，您在 Tor 网络中的友好数据收集服务.  Collector 从公共 Tor 网络中的各种节点和服务中获取数据，并将其提供给全世界. 如果您正在研究 Tor 网络，或者您正在开发使用 Tor 网络数据的应用程序，那么这就是您的起点. [TOR Node List](https://www.dan.me.uk/tornodes) /  [DNS Blacklists](https://www.dan.me.uk/dnsbl) / [Tor Node List](http://torstatus.blutmagie.de/)
- [leakedin.com](http://www.leakedin.com/)  -leakedin.com 的主要目的是让访问者了解丢失数据的风险. 该博客仅汇编了在 pastebin.com 等网站上丢失或披露的数据样本.
- [FireEye OpenIOCs](https://github.com/fireeye/iocs) - FireEye 公开共享的妥协指标 (IOC)
- [OpenVAS NVT Feed](http://www.openvas.org/openvas-nvt-feed.html)  - 网络漏洞测试 (NVT) 的公共提要. 它包含超过 35,000 个 NVT（截至 2014 年 4 月），并且每天都在增长. 此提要配置为 OpenVAS 的默认设置.
- [Project Honey Pot](http://www.projecthoneypot.org/)  - Project Honey Pot 是第一个也是唯一一个用于识别垃圾邮件发送者和他们用来从您的网站上抓取地址的垃圾邮件机器人的分布式系统. 使用 Project Honey Pot 系统，您可以安装自定义标记为您网站访问者的时间和 IP 地址的地址. 如果这些地址之一开始接收电子邮件，我们不仅可以判断这些邮件是垃圾邮件，还可以判断该地址被收集的确切时间以及收集它的 IP 地址.
- [virustotal](https://www.virustotal.com/)  - VirusTotal 是 Google 的子公司，是一项免费的在线服务，可分析文件和 URL，从而识别病毒、蠕虫、特洛伊木马和其他类型的由防病毒引擎和网站扫描程序检测到的恶意内容. 同时，它可以用作检测误报的手段，即被一个或多个扫描器检测为恶意的无害资源.
- [IntelMQ](https://github.com/certtools/intelmq/) - IntelMQ is a solution for CERTs for collecting and processing security feeds, pastebins, tweets using a message queue protocol. It's a community driven initiative called IHAP (Incident Handling Automation Project) which was conceptually designed by European CERTs during several InfoSec events. Its main goal is to give to incident responders an easy way to collect & process threat intelligence thus improving the incident handling processes of CERTs. [ENSIA Homepage](https://www.enisa.europa.eu/activities/cert/support/incident-handling-automation).
- [CIFv2](https://github.com/csirtgadgets/massive-octo-spice)  - CIF 是一个网络威胁情报管理系统.  CIF 允许您组合来自多个来源的已知恶意威胁信息，并将该信息用于识别（事件响应）、检测 (IDS) 和缓解（空路由）.
- [MISP - Open Source Threat Intelligence Platform ](https://www.misp-project.org/)  - MISP 威胁共享平台是一个免费的开源软件，有助于共享包括网络安全指标在内的威胁情报信息. 一个威胁情报平台，用于收集、共享、存储和关联目标攻击、威胁情报、金融欺诈信息、漏洞信息甚至反恐信息的妥协指标.  MISP 项目包括软件、公共库（[taxonomies](https://www.misp-project.org/taxonomies.html), [threat-actors and various malware](https://www.misp-project.org/galaxy.html))，一个广泛的数据模型，使用 [objects](https://www.misp-project.org/objects.html) 和默认 [feeds](https://www.misp-project.org/feeds/).
- [PhishStats](https://phishstats.info/) - 网络钓鱼统计，可搜索 IP、域名和网站标题.

## Social Engineering

- [Gophish](https://getgophish.com/) - 一个开源网络钓鱼框架.

## Web

### Organization

- [OWASP](http://www.owasp.org) - 开放 Web 应用程序安全项目 (OWASP) 是一个 501(c)(3) 全球非营利慈善组织，专注于提高软件的安全性.
- [Portswigger](https://portswigger.net)  - PortSwigger 提供用于 Web 应用程序安全、测试和扫描的工具. 从广泛的安全工具中进行选择并识别最新的漏洞.

### Web Application Firewall

- [ModSecurity](http://www.modsecurity.org/) - ModSecurity 是一个用于实时 Web 应用程序监控、日志记录和访问控制的工具包.
- [NAXSI](https://github.com/nbs-system/naxsi) - NAXSI 是 NGINX 的开源、高性能、低规则维护 WAF，NAXSI 的意思是 Nginx Anti Xss &amp; Sql Injection.
- [sql_firewall](https://github.com/uptimejp/sql_firewall) PostgreSQL 的 SQL 防火墙扩展
- [ironbee](https://github.com/ironbee/ironbee)  - IronBee 是一个开源项目，用于构建通用的 Web 应用程序安全传感器.  IronBee 作为开发用于保护 Web 应用程序的系统的框架 - 用于构建 Web 应用程序防火墙 (WAF) 的框架.
- [Curiefense](https://github.com/curiefense/curiefense) - Curiefense 添加了一系列广泛的自动化 Web 安全工具，包括一个 WAF 到 Envoy 代理.

### Scanning / Pentesting

- [Spyse](https://spyse.com/)  - Spyse 是一个开源情报搜索引擎，可提供有关整个网络的最新数据. 所有数据都存储在自己的数据库中，便于即时访问，并相互关联，便于灵活搜索.
提供的数据：IPv4 主机、子/域/whois、端口/横幅/协议、技术、操作系统、AS、宽 SSL/TLS 数据库等.
- [sqlmap](http://sqlmap.org/)  - sqlmap 是一种开源渗透测试工具，可自动执行检测和利用 SQL 注入缺陷以及接管数据库服务器的过程. 它配备了一个强大的检测引擎，为最终渗透测试人员提供了许多利基功能，以及从数据库指纹识别、从数据库获取数据到访问底层文件系统和通过输出在操作系统上执行命令的广泛切换.带外连接.
- [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)  - Zed Attack Proxy (ZAP) 是一种易于使用的集成渗透测试工具，用于查找 Web 应用程序中的漏洞. 它旨在供具有广泛安全经验的人使用，因此非常适合不熟悉渗透测试的开发人员和功能测试人员.  ZAP 提供自动扫描程序以及一组工具，可让您手动查找安全漏洞.
- [OWASP Testing Checklist v4](https://www.owasp.org/index.php/Testing_Checklist)  - 在 Web 漏洞评估期间要测试的一些控件列表. 可以找到降价版本 [here](https://github.com/amocrenco/owasp-testing-checklist-v4-markdown/blob/master/README.md).
- [w3af](http://w3af.org/)  - w3af 是一个 Web 应用程序攻击和审计框架. 该项目的目标是创建一个框架，通过查找和利用所有 Web 应用程序漏洞来帮助您保护 Web 应用程序.
- [Recon-ng](https://github.com/lanmaster53/recon-ng)  - Recon-ng 是一个用 Python 编写的全功能 Web 侦察框架.  Recon-ng 的外观和感觉类似于 Metasploit 框架.
- [PTF](https://github.com/trustedsec/ptf) - 渗透测试框架 (PTF) 是一种为最新工具提供模块化支持的方式.
- [Infection Monkey](https://github.com/guardicore/monkey)  - 用于映射/渗透测试网络的半自动渗透测试工具. 模拟人类攻击者.
- [ACSTIS](https://github.com/tijme/angularjs-csti-scanner)  - ACSTIS 帮助您扫描某些 Web 应用程序以进行 AngularJS 客户端模板注入（有时称为 CSTI、沙箱逃逸或沙箱绕过）. 它支持扫描单个请求，但也可以为 AngularJS CSTI 漏洞抓取整个 Web 应用程序.
- [padding-oracle-attacker](https://github.com/KishanBagaria/padding-oracle-attacker) - padding-oracle-attacker 是一个 CLI 工具和库，可以轻松执行 padding oracle 攻击（它解密以 CBC 模式加密的数据），支持并发网络请求和优雅的 UI.
- [is-website-vulnerable](https://github.com/lirantal/is-website-vulnerable) - 在网站的前端 JavaScript 库中发现公开的安全漏洞.
- [PhpSploit](https://github.com/nil0x42/phpsploit)  - 全功能的 C2 框架，它通过邪恶的 PHP oneliner 默默地保留在网络服务器上. 专为隐形持久性而构建，具有许多特权升级和后利用功能.

### Runtime Application Self-Protection

- [Sqreen](https://www.sqreen.io/)  - Sqreen 是软件团队的运行时应用程序自我保护 (RASP) 解决方案. 应用程序内代理检测和监控应用程序. 报告可疑用户活动并在运行时阻止攻击，无需修改代码或重定向流量.
- [OpenRASP](https://github.com/baidu/openrasp)  - 由百度公司积极维护的开源 RASP 解决方案.借助上下文感知检测算法，该项目几乎没有误报. 在繁重的服务器负载下观察到不到 3% 的性能下降.

### Development

- [API Security in Action](https://www.manning.com/books/api-security-in-action)  - 涵盖 API 安全性的书籍，包括安全开发、基于令牌的身份验证、JSON Web 令牌、OAuth 2 和 Macaroons.  （抢先体验，持续发布，2020 年夏季最终发布）
- [Secure by Design](https://www.manning.com/books/secure-by-design?a_aid=danbjson&a_bid=0b3fac80)  - 识别设计模式和编码风格的书，这些设计模式和编码风格使许多安全漏洞的可能性降低.  （抢先体验，持续发布，最终发布于 2017 年秋季）
- [Understanding API Security](https://www.manning.com/books/understanding-api-security) - 免费电子书采样器，通过展示 API 如何组合在一起以及如何使用 OAuth 协议来保护它们，为 API 安全在现实世界中的工作方式提供了一些背景信息.
- [OAuth 2 in Action](https://www.manning.com/books/oauth-2-in-action) - 从客户端、授权服务器和资源服务器的角度教您实际使用和部署 OAuth 2 的书.
- [OWASP ZAP Node API](https://github.com/zaproxy/zap-api-nodejs) - 通过此官方 API 在您的 NodeJS 应用程序中利用 OWASP Zed 攻击代理 (ZAP).
- [GuardRails](https://github.com/apps/guardrails) - 在拉取请求中提供安全反馈的 GitHub 应用程序.
- [Checkov](https://github.com/bridgecrewio/checkov/) - 基础设施即代码（Terraform）的静态分析工具.
- [TFSec](https://github.com/tfsec/tfsec/) - 基础设施即代码（Terraform）的静态分析工具.
- [KICS](https://github.com/Checkmarx/kics)  - 扫描 IaC 项目的安全漏洞、合规性问题和基础设施配置错误. 目前正在处理 Terraform 项目、Kubernetes 清单、Dockerfiles、AWS CloudFormation 模板和 Ansible 剧本.
- [Insider CLI](https://github.com/insidersec/insider) - A open source Static Application Security Testing tool (SAST) written in GoLang for Java (Maven and Android), Kotlin (Android), Swift (iOS), .NET Full Framework, C# and Javascript (Node.js).
- [Full Stack Python Security](https://www.manning.com/books/full-stack-python-security) - 全面了解 Python 开发人员的网络安全
- [Making Sense of Cyber Security](https://www.manning.com/books/making-sense-of-cyber-security)  - 关于网络安全的关键概念、术语和技术的无行话、实用指南，非常适合任何计划或实施安全策略的人.  （抢先体验，持续发布，2022 年初最终发布）

## Exploits & Payloads

- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - A list of useful payloads and bypass for Web Application Security and Pentest/CTF

## Red Team Infrastructure Deployment

- [Redcloud](https://github.com/khast3x/Redcloud) - 使用 Docker 的自动化红队基础设施部署.
- [Axiom](https://github.com/pry0cc/axiom) -Axiom 是一个动态基础架构框架，可有效处理多云环境，构建和部署专注于攻防安全的可重复基础架构.

## Usability

- [Usable Security Course](https://pt.coursera.org/learn/usable-security)  - 在 coursera 上可用的安全课程. 非常适合那些寻求安全性和可用性如何相交的人.

## Big Data

- [data_hacking](https://github.com/ClickSecurity/data_hacking) - 使用 IPython、Pandas 和 Scikit 的示例 学习充分利用您的安全数据.
- [hadoop-pcap](https://github.com/RIPE-NCC/hadoop-pcap) - 用于读取数据包捕获 (PCAP) 文件的 Hadoop 库.
- [Workbench](http://workbench.readthedocs.org/) - 用于安全研究和开发团队的可扩展 python 框架.
- [OpenSOC](https://github.com/OpenSOC/opensoc) - OpenSOC 集成了多种开源大数据技术，为安全监控和分析提供一个集中的工具.
- [Apache Metron (incubating)](https://github.com/apache/incubator-metron) - Metron 集成了多种开源大数据技术，为安全监控和分析提供一个集中的工具.
- [Apache Spot (incubating)](https://github.com/apache/incubator-spot) - Apache Spot 是一种开源软件，用于利用来自流和数据包分析的洞察力.
- [binarypig](https://github.com/endgameinc/binarypig)  - Hadoop 中的可扩展二进制数据提取.  Pig 上的恶意软件处理和分析，通过 Django、Twitter Bootstrap 和 Elasticsearch 进行探索.

## DevOps

- [Securing DevOps](https://manning.com/books/securing-devops) - 一本关于 DevOps 安全技术的书，回顾了用于保护 Web 应用程序及其基础设施的最先进实践.
- [ansible-os-hardening](https://github.com/dev-sec/ansible-os-hardening) - 操作系统强化的 Ansible 角色
- [bunkerized-nginx](https://github.com/bunkerity/bunkerized-nginx) - 默认情况下 nginx Docker 镜像是安全
- [Trivy](https://github.com/aquasecurity/trivy) - 一个简单而全面的容器和其他工件的漏洞扫描器，适用于 CI. 
- [Preflight](https://github.com/spectralops/preflight) - 帮助您验证脚本和可执行文件，以减轻 CI 和其他系统中的供应链攻击.
- [Teller](https://github.com/spectralops/teller) - 用于 DevOps 和开发人员的机密管理工具 - 从一个地方跨多个保险库和密钥库管理机密.

## Operating Systems

### Privacy & Security

- [Qubes OS](https://www.qubes-os.org/) - Qubes OS 是一个免费和开源的面向安全的操作系统，适用于单用户桌面计算.
- [Whonix](https://www.whonix.org) - 专为匿名而设计的操作系统.
- [Tails OS](https://tails.boum.org/) - Tails 是一种便携式操作系统，可防止监视和审查.

### Online resources

- [Security related Operating Systems @ Rawsec](http://rawsec.ml/en/security-related-os/) - 安全相关操作系统的完整列表
- [Best Linux Penetration Testing Distributions @ CyberPunk](https://www.cyberpunk.rs/category/pentest-linux-distros) - 主要渗透测试分布的描述
- [Security @ Distrowatch](http://distrowatch.com/search.php?category=Security) - 专门讨论、审查和了解开源操作系统的网站
- [Hardening Windows 10](https://www.hardenwindows10forsecurity.com/) - 强化 Windows 10 指南

## Datastores

- [databunker](https://databunker.org/)  - Databunker 是用于存储个人数据的类固醇地址簿.  GDPR 和加密是开箱即用的.
- [acra](https://github.com/cossacklabs/acra) - 数据库安全套件：具有透明“动态”数据加密、数据屏蔽和标记化、SQL 防火墙（SQL 注入预防）、入侵检测系统的数据保护代理.
- [blackbox](https://github.com/StackExchange/blackbox) - 使用 GPG 将机密安全地存储在 VCS 存储库中
- [confidant](https://github.com/lyft/confidant) - 在 AWS DynamoDB 中存储秘密，静态加密并与 IAM 集成
- [dotgpg](https://github.com/ConradIrwin/dotgpg) - 用于安全轻松地备份和版本控制您的生产机密或共享密码的工具.
- [redoctober](https://github.com/cloudflare/redoctober) - 用于两人规则风格文件加密和解密的服务器.
- [aws-vault](https://github.com/99designs/aws-vault) - 将 AWS 凭证存储在 OSX 钥匙串或加密文件中
- [credstash](https://github.com/fugue/credstash) - 使用 AWS KMS 和 DynamoDB 存储机密
- [chamber](https://github.com/segmentio/chamber) - 使用 AWS KMS 和 SSM Parameter Store 存储密钥
- [Safe](https://github.com/starkandwayne/safe) - Vault CLI，可以更轻松地读取和写入 Vault.
- [Sops](https://github.com/mozilla/sops) - 支持 YAML、JSON 和 BINARY 格式并使用 AWS KMS 和 PGP 加密的加密文件编辑器.
- [passbolt](https://www.passbolt.com/) - The password manager your team was waiting for. Free, open source, extensible, based on OpenPGP.
- [passpie](https://github.com/marcwebbie/passpie) - Multiplatform command-line password manager
- [Vault](https://www.vaultproject.io/) - 一个足够安全的加密数据存储，可以保存环境和应用程序的秘密.

## Fraud prevention

- [FingerprintJS](https://github.com/fingerprintjs/fingerprintjs)  - 识别浏览器和混合移动应用程序用户，即使他们清除数据存储. 允许您检测帐户接管、帐户共享和重复的恶意活动.
- [FingerprintJS Android](https://github.com/fingerprintjs/fingerprint-android)  - 即使在清除数据存储时也能识别 Android 应用程序用户. 允许您检测帐户接管、帐户共享和重复的恶意活动.

## EBooks

- [Holistic Info-Sec for Web Developers](https://holisticinfosecforwebdevelopers.com/) - 免费和可下载的系列丛书，涵盖了 Web 开发人员和 DevOps 工程师需要了解的内容，以便创建健壮、可靠、可维护和安全的软件、网络和其他内容，这些内容可以持续、准时、无恶意地交付惊喜
- [Docker Security - Quick Reference: For DevOps Engineers](https://binarymist.io/publication/docker-security/) - 一本关于理解 Docker 安全默认值、如何改进它们（理论和实践）以及许多工具和技术的书.  
- [How to Hack Like a Pornstar](https://books2read.com/u/bWzdBx) - 闯入银行的分步过程，Sparc Flow，2017  
- [How to Hack Like a Legend](https://amzn.to/2uWh1Up) - 黑客闯入一家秘密离岸公司的故事，Sparc Flow，2018 年  
- [How to Investigate Like a Rockstar](https://books2read.com/u/4jDWoZ) - 经历一场真正的危机，掌握取证分析的秘密，Sparc Flow，2017 年
- [Real World Cryptography](https://www.manning.com/books/real-world-cryptography) - 这本抢先体验的书教您应用加密技术来理解和应用系统和应用程序各个级别的安全性.
- [AWS Security](https://www.manning.com/books/aws-security?utm_source=github&utm_medium=organic&utm_campaign=book_shields_aws_1_31_20) - 这本抢先体验的书涵盖了常见的 AWS 安全问题以及访问策略、数据保护、审计、持续监控和事件响应的最佳实践.
- [The Art of Network Penetration Testing](https://www.manning.com/books/the-art-of-network-penetration-testing)  - 这本书是在企业网络上运行您自己的渗透测试的动手指南.  （抢先体验，持续发布，最终版 2020 年 12 月）
- [Spring Boot in Practice](https://www.manning.com/books/spring-boot-in-practice) - 这本书是一本实用指南，以方便的问题-解决方案-讨论格式呈现了数十个相关场景..（早期访问，持续发布，最终版本于 2021 年秋季发布）

## Other Awesome Lists

### Other Security Awesome Lists

- [Android Security Awesome](https://github.com/ashishb/android-security-awesome) - 安卓安全相关资源的集合.
- [Awesome ARM Exploitation](https://github.com/HenryHoggard/awesome-arm-exploitation) - ARM 开发资源的精选列表.
- [Awesome CTF](https://github.com/apsdehal/awesome-ctf) - CTF 框架、库、资源和软件的精选列表.
- [Awesome Cyber Skills](https://github.com/joe-shenouda/awesome-cyber-skills) - 精心策划的黑客环境列表，您可以在其中合法安全地培训网络技能.
- [Awesome Personal Security](https://github.com/Lissy93/personal-security-checklist) - 数字安全和隐私提示的精选列表，以及指向更多资源的链接.
- [Awesome Hacking](https://github.com/carpedm20/awesome-hacking) - 精选的精彩黑客教程、工具和资源列表.
- [Awesome Honeypots](https://github.com/paralax/awesome-honeypots) - 一个很棒的蜜罐资源列表.
- [Awesome Malware Analysis](https://github.com/rshipp/awesome-malware-analysis) - 精选的恶意软件分析工具和资源列表.
- [Awesome PCAP Tools](https://github.com/caesar0301/awesome-pcaptools) - 由计算机科学领域的其他研究人员开发的用于处理网络跟踪的工具集合.
- [Awesome Pentest](https://github.com/enaqx/awesome-pentest) - 一系列很棒的渗透测试资源、工具和其他闪亮的东西.
- [Awesome Linux Containers](https://github.com/Friz-zy/awesome-linux-containers) - 精选的优秀 Linux 容器框架、库和软件列表.
- [Awesome Incident Response](https://github.com/meirwah/awesome-incident-response) - 用于事件响应的精选资源列表.
- [Awesome Web Hacking](https://github.com/infoslack/awesome-web-hacking) - 此列表适用于希望了解 Web 应用程序安全性但没有起点的任何人.
- [Awesome Hacking](https://github.com/carpedm20/awesome-hacking) - 精选的精彩黑客教程、工具和资源列表
- [Awesome Electron.js Hacking](https://github.com/doyensec/awesome-electronjs-hacking) - 关于 Electron.js (in)security 的精选资源列表
- [Awesome Threat Intelligence](https://github.com/hslatman/awesome-threat-intelligence) - 威胁情报资源的精选列表.
- [Awesome Threat Modeling](https://github.com/redshiftzero/awesome-threat-modeling) - 威胁建模资源的精选列表.
- [Awesome Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) - 对渗透测试有用的备忘单的集合
- [Awesome Industrial Control System Security](https://github.com/mpesen/awesome-industrial-control-system-security) - 与工业控制系统 (ICS) 安全相关的资源精选列表.
- [Awesome YARA](https://github.com/InQuest/awesome-yara) - 精选的 YARA 规则、工具和人员列表.
- [Awesome Threat Detection and Hunting](https://github.com/0x4D31/awesome-threat-detection) - 精选的威胁检测和狩猎资源列表.
- [Awesome Container Security](https://github.com/kai5263499/container-security-awesome) - 与容器构建和运行时安全相关的优秀资源的精选列表
- [Awesome Crypto Papers](https://github.com/pFarb/awesome-crypto-papers) - 密码学论文、文章、教程和操作指南的精选列表.
- [Awesome Shodan Search Queries](https://github.com/jakejarvis/awesome-shodan-queries) - 可插入 Shodan.io 的一系列有趣、有趣且令人沮丧的搜索查询.
- [Awesome Anti Forensics](https://github.com/remiflavien1/awesome-anti-forensic) - 用于对抗取证活动的一系列很棒的工具.
- [Awesome Security Talks & Videos](https://github.com/PaulSec/awesome-sec-talks) - 按年份和会议组织的精彩安全会谈的精选清单.

### Other Common Awesome Lists

其他非常棒的列表：

- [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - awesome-* 或 *-awesome 列表.
- [lists](https://github.com/jnv/lists) - 在 GitHub 上策划的（很棒的）列表的最终列表.
- [Movies For Hacker](https://github.com/k4m4/movies-for-hackers) - 每个黑客和赛博朋克必须观看的精选电影列表.

## [Contributing](https://github.com/sbilly/awesome-security/blob/master/contributing.md)

随时欢迎您的贡献！
