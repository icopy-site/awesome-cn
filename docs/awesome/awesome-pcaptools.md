<div class="github-widget" data-repo="caesar0301/awesome-pcaptools"></div>
Introduction
------------

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/caesar0301/awesome-pcaptools.svg)](https://travis-ci.org/caesar0301/awesome-pcaptools)

该项目不包含任何源代码或文件. 我只想列一个工具列表来处理网络流量研究中的 pcap 文件. 更多精彩列表，请参见 https://github.com/sindresorhus/awesome

**许可证**：CC0 1.0 通用版 (CC0 1.0).





Linux 命令<a name="linuxcmds"></a>
--------------------------------------


* **Bwm-ng**：（下一代带宽监视器）是另一个非常简单的实时网络负载监视器，它报告系统上所有可用网络接口进出数据传输速度的摘要. [Screenshot](https://a.fsdn.com/con/app/proj/bwmng/screenshots/10965.jpg/245/183/1)


* **Collectl**: reports system statistics in a style that is similar to dstat, and like dstat it gathers statistics about various different system resources like cpu, memory, network etc. Over here is a simple example of how to use it to report network usage/bandwidth. [Screenshot](https://www.cse.wustl.edu/~jain/cse567-08/ftp/hw/collectl.png)


 * **Ifstat**：以批处理方式报告网络带宽. 输出采用易于使用其他程序或实用程序记录和解析的格式. [Screenshot](https://community.linuxmint.com/img/screenshots/ifstat.png)


 * **Iptraf-ng**：是一个交互式和丰富多彩的 IP 局域网监控器. 它显示了主机之间的各个连接和数据流量. 已失效 iptraf 的维护分支. [Screenshot](https://wiki.ipfire.org/addons/iptraf-ng/iptraf-ng_monitor.png)

* **Jnettop**: [Jnettop](https://sourceforge.net/projects/jnettop/) 是一个流量可视化工具，它捕获流经主机的流量并显示按它们使用的带宽排序的流. [Screenshot](https://web.archive.org/web/20130509072433if_/http://jnettop.kubs.info/wiki/?binary=internal%3A%2F%2F76195466cc3bca92f8de7b404e240844.gif)










 * **Vnstat**：与大多数其他工具有点不同. 它实际上运行一个后台服务/守护进程，并一直记录数据传输的大小. 接下来，它可用于生成网络使用历史报告. [Screenshot](https://www.howtoforge.com/images/vnstat/big/vnstat9.png)



流量抓取<a name="capture"></a>
---------------

* [Libpcap/Tcpdump](https://www.tcpdump.org/) ：tcpdump 的官方网站，一个强大的命令行数据包分析器； 和 libpcap，一个用于网络流量捕获的可移植 C/C++ 库.

* [Deepfence PacketStreamer](https://github.com/deepfence/PacketStreamer): 高性能的远程数据包捕获和收集工具，用于云原生环境的分布式tcpdump.

* [Ngrep](https://github.com/jpr5/ngrep/) : 力求提供 GNU grep 的大部分通用功能，并将它们应用到网络层.  ngrep 是一种 pcap 感知工具，可让您指定扩展的正则或十六进制表达式以匹配数据包的数据有效负载. 它目前可以跨以太网、PPP、SLIP、FDDI、令牌环和空接口识别 TCP、UDP 和 ICMP，并以与更常见的数据包嗅探工具（如 tcpdump 和 snoop）相同的方式理解 bpf 过滤器逻辑. [Screenshot](https://www.cyberciti.biz/media/new/cms/2012/12/ngrep.png)

* [clj-net-pcap](https://github.com/ruedigergad/clj-net-pcap) : `clj-net-pcap` 是 Clojure 的数据包捕获库.  clj-net-pcap 使用 jNetPcap 并围绕 jNetPcap 添加便利功能以简化可用性.  A [paper on clj-net-pcap](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?tp=&arnumber=6903107) 发表在 COMPSACW 2014 的范围内.

* [jNetPcap](https://sourceforge.net/projects/jnetpcap/) : jNetPcap 是一个适用于 Linux 和 Windows 的 Java 数据包捕获库.  jNetPcap 分别利用 libpcap 和 WinPcap，并使用 Java 本机接口 (JNI) 来使用 libpcap/WinPcap 提供的功能.

* [Arkime](https://arkime.com/) Arkime（以前称为 Moloch）是一种大规模、开源、索引数据包捕获和搜索工具.

* [n2disk](https://www.ntop.org/products/traffic-recording-replay/n2disk/)  （商业）：具有索引功能的多千兆位网络流量记录器.  n2disk 是一个网络流量记录器应用程序. 使用 n2disk，您可以从实时网络接口以多千兆比特率（在适当的硬件上超过 10 Gigabit/s）捕获全尺寸网络数据包，并将它们写入文件而不会丢失任何数据包.

* [Netis Packet Agent](https://github.com/Netis/packet-agent)：它是一个通过GRE隧道的远程数据捕获实用程序，它使您可以轻松地从NIC接口捕获数据包，将它们用GRE封装并发送到远程机器进行监控和分析.

* [OpenFPC](https://github.com/leonward/OpenFPC) : OpenFPC 是一组脚本，它们结合起来提供了一个轻量级的全包网络流量记录器和缓冲工具. 它的设计目标是允许非专家用户在 COTS 硬件上部署分布式网络流量记录器，同时集成到现有的警报和日志工具中.

* [PCAPdroid](https://github.com/emanuele-f/PCAPdroid) : PCAPdroid 是一款 Android 应用程序，可让您无需 root 即可监控和导出设备的网络流量. 流量可以以 PCAP 格式转储，以便使用 Wireshark 等流行工具进行分析，甚至可以进行实时分析. 内置流量监视器可让您检测用户和系统应用程序建立的可疑连接.

* [PF_RING](https://www.ntop.org/products/packet-capture/pf_ring/) : PF_RING 是一种新型的网络套接字，可以显着提高数据包捕获速度. 适用于 Linux 内核 2.6.32 及更新版本. 无需修补内核.  PF_RING 感知驱动程序，用于增加数据包捕获加速.

* [TTT](https://www2.sonycsl.co.jp/person/kjc/kjc/software.html#ttt) : (Tele Traffic Tapper) 是 tcpdump 的另一个后代，但它能够进行实时、图形化和远程流量监控.  ttt 不会取代 tcpdump，相反，它可以帮助您找出使用 tcpdump 可以查看的内容.  ttt 监控网络并自动获取时间窗口内流量的主要贡献者. 默认情况下，图表每秒更新一次.

* [Yaf](https://tools.netsa.cert.org/yaf/yaf.html) : 很靠谱的一款软件，很扎实，可以pcap生成流量记录. 这对于索引巨大的 pcap 甚至进行数据包捕获非常有用. 最近的版本甚至可以提取有效载荷并放入流记录中.

* [sharppcap](https://github.com/dotpcap/sharppcap) ：完全托管的跨平台（Windows、Mac、Linux）.NET 库，用于从实时和基于文件的设备捕获数据包.  libpcap 和 npcap 的可靠且健壮的包装器.

流量分析/检查<a name="analysis"></a>
--------------------------------------------------
* [Brim](https://www.brimsecurity.com/) ：Brim 将 Zeek 日志的丰富性与数据包的详细信息融合在一起. 这是两全其美的. 虽然 Zeek 日志可以快速回答您的大部分问题，但当您需要深入了解细节时，您仍然可以快速访问数据包.  Wireshark 总是只需点击一下即可. 

* [BruteShark](https://github.com/odedshimon/BruteShark) : 是一个开源的、跨平台的网络取证分析工具，具有很多特点. 它包括：密码提取、显示可视化网络地图、重建 TCP 会话、提取加密密码的哈希值，甚至将它们转换为 Hashcat 格式以执行离线暴力攻击.

* [AIEngine](https://bitbucket.org/camp0/aiengine) ：是下一代交互式/可编程数据包检测引擎，具有无需任何人为干预的学习能力、NIDS 功能、DNS 域分类、网络收集器等.  AIEngine 还帮助网络/安全专业人员识别流量并开发签名，以便在 NIDS、防火墙、流量分类器等上使用它们.

* [CapAnalysis](http://www.capanalysis.net/ca/)  - CapAnalysis 是一个网络可视化工具，适用于信息安全专家、系统管理员和需要分析大量捕获的网络流量的每个人. 现场网络演示是 [available](http://pcap.capanalysis.net/) 供测试用.

* [CapTipper](https://github.com/omriher/CapTipper): 恶意 HTTP 流量浏览器

* [Chopshop](https://github.com/MITRECND/chopshop)：是一个 MITRE 开发的框架，用于帮助分析师创建和执行基于 Pynids 的 APT tradecraft 解码器和检测器.

* [CoralReef](https://www.caida.org/tools/measurement/coralreef/) : 是 CAIDA 开发的一个软件套件，用于分析被动互联网流量监视器收集的数据. 它提供了一个编程库 libcoral，类似于 libpcap，具有 ATM 和其他网络类型的扩展，可从 C 和 Perl 获得.

* [DPDK](https://www.dpdk.org/) : 是一组用于快速数据包处理的库和驱​​动程序. 它被设计为在任何处理器上运行. 第一个支持的 CPU 是 Intel x86，现在扩展到 IBM Power 8、EZchip TILE-Gx 和 ARM. 它主要运行在 Linux 用户区.  FreeBSD 端口可用于 DPDK 功能的子集.

* [DPKT](https://github.com/kbandla/dpkt): Python数据包创建/解析库.

* [ECap](https://web.archive.org/web/20170715080351/https://bitbucket.org/nathanj/ecap/wiki/Home) : (External Capture) 是一个带有网络前端的分布式网络嗅探器.  Ecap 是在很多年前的 2005 年编写的，但是 tcpdump-workers 邮件列表上的一篇帖子要求类似的应用程序......所以在这里. 如果有任何兴趣，更新它并再次处理它会很有趣.

* [EtherApe](https://etherape.sourceforge.io/) : 是一个以 etherman 为模型的 Unix 图形网络监视器. 它具有链路层、IP 和 TCP 模式，以图形方式显示网络活动. 主机和链接的大小随流量而变化. 颜色编码协议显示. 它支持以太网、FDDI、令牌环、ISDN、PPP 和 SLIP 设备. 它可以过滤要显示的流量，并且可以从文件中读取流量以及从网络中实时读取流量.

* [HttpSniffer](https://github.com/caesar0301/http-sniffer) : 一个多线程工具，用于从 PCAP 文件中嗅探 TCP 流量统计信息和嵌入式 HTTP 标头. 每个携带 HTTP 的 TCP 流都以 JSON 格式导出到文本文件.


* [ITA](https://web.archive.org/web/20181016104652/http://ita.ee.lbl.gov/html/traces.html) ：Internet Traffic Archive 是由 ACM SIGCOMM 赞助的一个托管存储库，用于支持对 Internet 网络流量痕迹的广泛访问. 跟踪可用于研究网络动态、使用特性和增长模式，以及为跟踪驱动的模拟提供基础. 该档案还对用于将原始跟踪数据减少为更易于管理的形式、用于生成合成跟踪和用于分析跟踪的程序开放.

* [Joy](https://github.com/cisco/joy) :joy是开发的一款流量分析解析工具. 部分是为了帮助对加密流量流进行分类，例如 HTTPS 流量. 它能够将 pcap 文件解析为可用的 json 文件，其中包含有关捕获统计信息和功能的详细信息.

* [Libcrafter](https://github.com/pellegre/libcrafter) : 是一个高级 C++ 库，旨在简化网络数据包的创建和解码. 它能够制作或解码大多数常见网络协议的数据包，通过网络发送它们，捕获它们并匹配请求和回复.

* [Libnet](https://github.com/libnet/libnet) : 是一组有助于构建和处理网络数据包的例程. 它为低级网络数据包整形、处理和注入提供了一个可移植的框架.  Libnet 在 IP 层和链路层具有可移植的数据包创建接口，以及许多补充和补充功能. 使用 libnet，可以轻而易举地创建快速简单的数据包组装应用程序.

* [Libnids](http://libnids.sourceforge.net/) ：由 Rafal Wojtczuk 设计，是网络入侵检测系统电子组件的实现. 它模拟 Linux 2.0.x 的 IP 堆栈.  Libnids 提供 IP 碎片整理、TCP 流组装和 TCP 端口扫描检测.  libnids 最有价值的特性是可靠性. 进行了大量测试，证明 libnids 尽可能准确地预测了受保护 Linux 主机的行为.

* [Multitail](https://www.vanheusden.com/multitail/) ：现在包含一个用于监视 tcpdump 输出的颜色方案. 它还可以过滤、将时间戳转换为时间字符串等等.

* [Netsniff-ng](https://www.github.com/borkmann/netsniff-ng)：Netsniff-ng 是一个免费的 Linux 网络实用程序工具包，如果您愿意的话，它是您日常 Linux 网络管道的瑞士军刀.

* [NetDude](http://netdude.sourceforge.net/) : (NETwork DUmp 数据显示和编辑器). 在他们的网页上，“这是一个基于 GUI 的工具，允许您对 tcpdump 跟踪文件中的数据包进行详细更改.”

* [Network Expect](https://www.netexpect.org/) : 是一个允许轻松构建可以与网络流量交互的工具的框架. 按照脚本，可以将流量注入网络，并且可以根据接收到的网络流量做出决定并采取行动. 解释性语言提供分支和高级控制结构来指导与网络的交互.  Network Expect 使用 libpcap 进行数据包捕获，使用 libwireshark（来自 Wireshark 项目）进行数据包分解任务.  （GPL、BSD/Linux/OSX）.

* [NFStream](https://github.com/nfstream/nfstream) : 是一个 Python 框架，提供快速、灵活和富有表现力的数据结构，旨在使在线或离线网络数据的处理既简单又直观. 它的目标是成为用 Python 进行实用的、真实世界的网络数据分析的基本高级构建块. 此外，它还有一个更广泛的目标，即成为一个通用的网络数据分析框架，为研究人员提供跨实验的数据可重复性.

* [Ntop](http://www.ntop.org/) : Ntop 是一个网络流量探测器，显示网络使用情况，类似于流行的 top Unix 命令所做的.  ntop 基于 libpcap，并且以可移植的方式编写，以便在每个 Unix 平台和 Win32 上虚拟运行.

* [Ntopng](https://www.ntop.org/products/traffic-analysis/ntop/) : Ntopng 是原始 ntop 的下一代版本，它是一个显示网络使用情况的网络流量探测器，类似于流行的 top Unix 命令所做的.  ntop 基于 libpcap，它以可移植的方式编写，以便在每个 Unix 平台、MacOSX 和 Win32 上虚拟运行.

* [PacketQ](https://github.com/dotse/PacketQ) : 为 PCAP 文件提供基本 SQL 前端的工具. 输出 JSON、CSV 和 XML，包括一个带有 JSON-api 的内置网络服务器和一个漂亮的 AJAX GUI.

* [Pcap2har](https://github.com/andrewf/pcap2har): 一个使用库 dpkt 将 .pcap 网络捕获文件转换为 HTTP 存档文件的程序.

* [PcapPlusPlus](https://github.com/seladb/PcapPlusPlus) : PcapPlusPlus 多平台 C++ 网络嗅探和数据包解析和操作框架. 它旨在轻巧、高效且易于使用. 它是 libpcap、WinPcap、DPDK 和 PF_RING 等流行引擎的 C++ 包装器. 它还包含许多协议的解析和编辑功能，包括以太网、IPv4、IPv6、ARP、VLAN、MPLS、PPPoE、GRE、TCP、UDP、ICMP、DNS 以及第 7 层协议，如 HTTP 和 SSL/TLS

* [pkt2flow](https://github.com/caesar0301/pkt2flow) ：一个简单的实用程序，用于将数据包分类为流. 它是如此简单，以至于只有一项任务旨在完成. 对于深度包检测或流分类，分析一个特定流的特征是很常见的. 我已经尝试使用现成的工具，如 tcpflows、tcpslice、tcpsplit，但所有这些工具都试图减少跟踪量（低于要求）或类似于将数据包转化为流负载（超过要求）. 我还没有找到一个简单的工具来将数据包分类为流而无需进一步处理.

* [potiron](https://github.com/CIRCL/potiron)：规范化、索引、丰富和可视化网络捕获.

* [pyshark](https://kiminewt.github.io/pyshark/) ：tshark 的 Python 包装器，允许使用 wireshark 解析器解析 python 数据包. 有很多 python 数据包解析模块，这个是不同的，因为它实际上不解析任何数据包，它只是使用 tshark（wireshark 命令行实用程序）导出 XML 的能力来使用它的解析.


* [Scapy](http://www.secdev.org/projects/scapy/) : Scapy 是一个强大的交互式数据包操作程序. 它能够伪造或解码大量协议的数据包、在线发送它们、捕获它们、匹配请求和回复等等. 它可以轻松处理大多数经典任务，如扫描、跟踪路由、探测、单元测试、攻击或网络发现（它可以替代 hping、85% 的 nmap、arpspoof、arp-sk、arping、tcpdump、tethereal、p0f 等）. 它在大多数其他工具无法处理的许多其他特定任务上也表现出色，例如发送无效帧、注入您自己的 802.11 帧、结合技术（VLAN 跳跃+ARP 缓存投毒、WEP 加密通道上的 VOIP 解码、. ..）， ETC.

* [Sniff](http://www.thedumbterminal.co.uk/software/sniff.html)：使 tcpdump 程序的输出更易于阅读和解析.

* [Snort](https://www.snort.org/) : Snort 是由 Sourcefire 开发的开源网络入侵防御和检测系统 (IDS/IPS)，现归思科所有. 结合签名、协议和基于异常的检查的优点，Snort 是全球部署最广泛的 IDS/IPS 技术. 凭借数百万的下载量和大约 500,000 名注册用户，Snort 已成为 IPS 的事实标准.

* [Socket Sentry](https://github.com/rhasselbaum/socket-sentry)：Socket Sentry 是 KDE Plasma 的实时网络流量监视器，与 iftop 和 netstat 等工具具有相同的精神.

* [Suricata](https://suricata-ids.org): Suricata is a free and open source, mature, fast and robust network threat detection engine.  The Suricata engine is capable of real time intrusion detection (IDS), inline intrusion prevention (IPS), network security monitoring (NSM) and offline pcap processing.


* [Tcpdpriv](http://ita.ee.lbl.gov/html/contrib/tcpdpriv.html) : Tcpdpriv 是一个程序，用于从网络接口上收集的数据包（或者从使用 tcpdump 的 -w 参数创建的跟踪文件）中删除机密信息（用户数据和地址）.  Tcpdpriv 删除 TCP 和 UDP 的负载，以及其他协议的整个 IP 负载. 它实现了多种地址加扰方法； 顺序编号法及其变体，保留地址前缀的哈希法.

* [Tcpflow](https://github.com/simsong/tcpflow) ：一种程序，它捕获作为 TCP 连接（流）的一部分传输的数据，并以便于协议分析或调试的方式存储数据. 像“tcpdump”这样的程序显示了在线路上看到的数据包的摘要，但通常不存储实际传输的数据. 相反，tcpflow 重建实际的数据流并将每个流存储在单独的文件中以供以后分析. 然而，可选地，它可以隔离每个 tcp 流的 pcap 流以进行粒度检查. [Original link](http://www.circlemud.org/jelson/software/tcpflow/).


* [Tcpreplay](https://github.com/appneta/tcpreplay)：使用 libnet 在接口上重播 pcap 文件.

* [Tcpslice](https://github.com/pyke369/tcpsplice) : Tcpslice 是一个工具，用于提取使用 tcpdump 的 -w 标志生成的数据包跟踪文件的一部分. 它可以组合多个跟踪文件，和/或根据时间提取一个或多个跟踪的部分内容.

* [Tcpsplit](https://github.com/pmcgleenon/tcpsplit) ：一种将单个 libpcap 数据包跟踪分解为一定数量的子跟踪的工具，沿着 TCP 连接边界打破跟踪，这样 TCP 连接就不会最终分裂成两个子跟踪. 这对于使大型跟踪文件易于处理以进行深入分析以及对跟踪进行子集化以仅对部分跟踪进行分析很有用.

* [Tcpstat](https://frenchfries.net/paul/tcpstat/) : tcpstat 报告某些网络接口统计信息，就像 vmstat 报告系统统计信息一样.  tcpstat 通过监视特定接口或从文件中读取先前保存的 tcpdump 数据来获取其信息.

* [Tcptrace](https://github.com/blitz/tcptrace) : 由俄亥俄大学的 Shawn Ostermann 编写的工具，用于分析 TCP 转储文件. 它可以将几个流行的数据包捕获程序生成的文件作为输入，包括 tcpdump、snoop、etherpeek、HP Net Metrix 和 WinDump.  tcptrace 可以产生几种不同类型的输出，其中包含有关每个看到的连接的信息，例如经过的时间、发送和接收的字节和段、重传、往返时间、窗口广告、吞吐量等. 它还可以生成大量图表以供进一步分析.

* [TraceWrangler](https://www.tracewrangler.com/) : TraceWrangler 是一个运行在 Windows 上（或在 Linux 上，使用 WINE）的网络捕获文件工具包，它支持 PCAP 以及新的 PCAPng 文件格式，这是现在 Wireshark 使用的标准文件格式.  TraceWrangler 最突出的用例是 PCAP 和 PCAPng 文件（有时称为“跟踪文件”、“捕获文件”或“数据包捕获”）的轻松清理和匿名化，删除或替换敏感数据，同时易于使用.

* [Tstat](http://tstat.tlc.polito.it/)：一个被动嗅探器，能够通过大量的流特征提供对网络和传输级别的流量模式的多种洞察.

* [WAND](https://research.wand.net.nz/) ：基于 libtrace 构建的用于处理网络流量的精彩工具集合，来自怀卡托大学. 我喜欢这个项目！

* [WinPcap](https://www.winpcap.org/)：Guy Harris 关于 WinPcap 和 WinDump 状态的消息的摘录.

* [WireEdit](https://wireedit.com/) ：WireEdit 是一款免费的桌面所见即所得网络数据包编辑器. 它允许在不了解数据包语法和编码规则的情况下将任何堆栈层编辑为“富文本”. 输入和输出文件格式为 Pcap.

* [Wireshark suit](https://wiki.wireshark.org/Tools) : 知名工具套装，支持包分析器和协议解码器. 它还包括一些实用工具和脚本来支持大多数常见用法.

* [Xplot](http://www.xplot.org/)：程序 xplot 是在 80 年代后期编写的，用于支持 TCP 数据包跟踪分析.

* [yaraPcap](https://github.com/kevthehermit/YaraPcap): 使用 YARA 处理 HTTP Pcaps

* [yaraprocessor](https://github.com/MITRECND/yaraprocessor) ：使用 yaraprocessor，YARA 可以针对单个数据包有效负载运行，也可以针对部分或全部有效负载的串联运行. 它最初是为在 Chopshop 中使用而编写的，但也可以在没有它的情况下使用.

“Zeek 为网络流量分析提供了一个全面的平台，特别关注大规模的语义安全监控.虽然经常与经典的入侵检测/预防系统进行比较，但 Zeek 采取了一种截然不同的方法，为用户提供了一个灵活的框架，有助于定制，深入监控远远超出传统系统的能力.Zeek 的初始版本在 90 年代中期已经投入运营部署，Zeek 发现自己立足于 20 多年的研究.有关更多信息，请参阅 Zeek 概述和我们的宣传文件，为什么选择 Zeek？”

DNS 实用程序<a name="dnstools"></a>
--------------------------------------------

* [dnsgram](https://doc.powerdns.com/authoritative/manpages/dnsgram.1.html) : dnsgram 是间歇性解析器故障的调试工具. 它需要一个或多个输入 PCAP 文件并生成 5 秒段的统计数据，允许研究间歇性解析器问题.

* [dnsreplay](https://doc.powerdns.com/authoritative/manpages/dnsreplay.1.html) ：Dnsreplay 获取记录的问题和答案并将它们重播到指定的名称服务器，然后报告匹配的答案百分比，更差或更好. 然后将答案和其他一些指标与实际指标与转储文件中找到的指标进行比较.

* [dnsscan](https://doc.powerdns.com/authoritative/manpages/dnsscan.1.html): dnsscan 采用一个或多个 PCAP 格式的 INFILE，并生成每种查询类型的查询数量列表.

* [dnsscope](https://doc.powerdns.com/authoritative/manpages/dnsscope.1.html): dnsscope 接受一个输入 PCAP 并生成一些简单的统计数据输出到控制台.

* [dnswasher](https://doc.powerdns.com/authoritative/manpages/dnswasher.1.html) ：dnswasher 获取 PCAP 格式的输入文件并写出 PCAP 文件，同时混淆最终用户的 IP 地址. 这对于在尝试保护用户隐私的同时与第三方共享数据很有用.


文件提取<a name="fileextraction"></a>
--------------------------------------------


* [Dsniff](https://www.monkey.org/~dugsong/dsniff/) : Dsniff 是网络审计和渗透测试工具的集合.  dsniff、filesnarf、mailsnarf、msgsnarf、urlsnarf 和 webspy 被动地监视网络以获取有趣的数据（密码、电子邮件、文件等）.  arpspoof、dnsspoof 和 macof 有助于拦截攻击者通常无法访问的网络流量（例如，由于第 2 层交换）.  sshmitm 和 webmitm 通过利用临时 PKI 中的弱绑定，对重定向的 SSH 和 HTTPS 会话实施主动的中间猴子攻击.

* [Foremost](https://github.com/jonstewart/foremost) : 是一个控制台程序，用于根据文件的页眉、页脚和内部数据结构恢复文件. 这个过程通常被称为数据雕刻.  Foremost 可以处理图像文件，例如由 dd、Safeback、Encase 等生成的图像文件，或直接在驱动器上处理. 页眉和页脚可以由配置文件指定，或者您可以使用命令行开关指定内置文件类型. 这些内置类型查看给定文件格式的数据结构，以实现更可靠和更快的恢复.

* [Justniffer](https://onotelli.github.io/justniffer/): Justniffer is a network protocol analyzer that captures network traffic and produces logs in a customized way, can emulate Apache web server log files, track response times and extract all "intercepted" files from the HTTP traffic.

* [NetworkMiner](https://www.netresec.com/index.ashx?page=NetworkMiner) : NetworkMiner 是一个适用于 Windows 的网络取证分析工具 (NFAT)（但也适用于 Linux / Mac OS X / FreeBSD）.  NetworkMiner 可用作被动网络嗅探器/数据包捕获工具，以检测操作系统、会话、主机名、开放端口等，而无需在网络上放置任何流量.  NetworkMiner 还可以解析 PCAP 文件以进行离线分析，并从 PCAP 文件重新生成/重组传输的文件和证书.

* [pcapfex](https://github.com/vikwin/pcapfex)  - Packet CAPture Forensic Evidence eXtractor (pcapfex) 是一种从数据包捕获文件中查找和提取文件的工具. 它的强大之处在于它的易用性. 只需向它提供一个 pcap 文件，它就会尝试提取所有文件. 它是一个可扩展的平台，因此可以轻松添加要识别和提取的其他文件类型.

* [scalpel](https://github.com/sleuthkit/scalpel): Scalpel 是一个开源的数据雕刻工具.

* [Snort](https://www.snort.org/) : 是由 Sourcefire 开发的开源网络入侵防御和检测系统 (IDS/IPS)，现归思科所有. 结合签名、协议和基于异常的检查的优点，Snort 是全球部署最广泛的 IDS/IPS 技术.

* [Tcpick](http://tcpick.sourceforge.net/) : 是一个基于 libpcap 的文本模式嗅探器，可以跟踪、重组和重新排序 tcp 流.  tcpick 能够将捕获的流保存在不同的文件中或在终端中显示它们，因此它对于嗅探通过 ftp 或 http 传输的文件很有用. 它可以在终端上显示所有流，当连接关闭时以 hexdump、hexdump + ascii、仅可打印字符、原始模式等不同的显示模式.

* [Tcpxtract](http://tcpxtract.sourceforge.net/) : 是一种基于文件签名从网络流量中提取文件的工具. 根据文件类型的页眉和页脚提取文件（有时称为“雕刻”）是一种古老的数据恢复技术.


USB
---
### Capture tools
* [usbmon](https://www.kernel.org/doc/Documentation/usb/usbmon.txt) - Linux 内核子系统，用于捕获 usb 数据包.
* [USBPcap](https://github.com/desowin/usbpcap) - 适用于 Windows 的解决方案.

### Analysis
* [USBPcapOdinDumper](https://github.com/KOLANICH/USBPcapOdinDumper) - 从使用 Odin 或 [Heimdall](https://gitlab.com/BenjaminDobell/Heimdall) 到一组具有帧负载的文件中. 对逆向工程很有用. 具有可轻松转换为其他应用程序格式的模块化架构.


相关项目<a name="others"></a>
--------------------------------------

* [BPF for Ultrix](https://www.tcpdump.org/other/bpfext42.tar.Z): Ultrix 4.2 的 BPF 发行版，包含源代码和二进制模块.

* [BPF+](https://andrewbegel.com/papers/bpf.pdf)：利用通用数据包过滤器架构中的全局数据流优化，作者：Andrew Begel、Steven McCanne 和 Susan Graham.

* [FFT-FGN-C](https://github.com/caesar0301/awesome-pcaptools/blob/master/ftp://ita.ee.lbl.gov/html/contrib/fft_fgn_c.html) : 是一个用于合成一种称为分数高斯噪声的自相似过程的程序. 该程序速度快但近似. 分数阶高斯噪声只是一种自相似过程. 当使用这个程序来合成网络流量时，您必须记住，使用其他进程之一可能可以更好地为您寻求的流量建模.

* [Haka](http://www.haka-security.org/) ：一种面向安全的开源语言，它允许描述协议并对（实时）捕获的流量应用安全策略. 哈卡语的范围是双重的. 首先，它允许编写安全规则以过滤/更改/丢弃不需要的数据包并记录和报告恶意活动. 其次，Haka 具有能够指定网络协议及其底层状态机的语法.

* [RIPE-NCC Hadoop for PCAP](https://github.com/RIPE-NCC/hadoop-pcap) ：用于读取数据包捕获 (PCAP) 文件的 Hadoop 库. 捆绑用于读取 PCAP 的代码. 可以在 MapReduce 作业中使用以本地读取 PCAP 文件. 还具有一个 Hive 序列化器/反序列化器 (SerDe)，可以使用类似 SQL 的命令查询 PCAP.

* [Traffic Data Repository at the WIDE Project](https://www2.sonycsl.co.jp/person/kjc/papers/freenix2000/) ：对于网络研究人员和运营商而言，了解网络流量趋势并发现网络流量异常变得越来越重要. 本文描述了 WIDE 项目中正在进行的一项工作，该项目旨在收集一组免费工具来构建包含我们骨干流量详细信息的流量数据存储库. 流量轨迹由 tcpdump 收集，并在删除隐私信息后向公众开放. 我们审查了有关用户隐私的问题，然后是用于构建 WIDE 流量存储库的工具. 我们将在 IPv6 部署的早期阶段报告当前状态和发现.

* [Usenix93 Paper on BPF](https://www.tcpdump.org/papers/bpf-usenix93.pdf) : libpcap 接口支持基于 BSD 数据包过滤器架构的过滤机制.  BPF 在 1993 年 Winter Usenix 论文“The BSD Packet Filter: A New Architecture for User-level Packet Capture”中有所描述.
