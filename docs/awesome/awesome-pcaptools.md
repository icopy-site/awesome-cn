<div class="github-widget" data-repo="caesar0301/awesome-pcaptools"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
Introduction
------------

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/caesar0301/awesome-pcaptools.svg)](https://travis-ci.org/caesar0301/awesome-pcaptools)

此项目不包含任何源代码或文件. 我只想列出一个工具列表来处理网络流量研究中的 pcap 文件. 有关更多精彩列表，请参阅 https://github.com/sindresorhus/awesome

**许可证**：Apache 许可证 v2.





Linux 命令<a name="linuxcmds"></a>
--------------------------------------


 * **Bwm-ng**：（下一代带宽监视器）是另一个非常简单的实时网络负载监视器，它报告数据传入和传出系统上所有可用网络接口的速度摘要.  [截图]()


 * **Collectl**：以类似于dstat的方式报告系统统计信息，和dstat一样，它收集有关各种不同系统资源的统计信息，如cpu、内存、网络等.这里是一个如何使用它的简单示例报告网络使用情况/带宽.  [截图]()

 * **Dstat**：是一个多功能工具（用python编写），可以监控不同的系统统计数据并以批处理方式报告它们或将数据记录到csv或类似文件中. 此示例显示如何使用 dstat 报告网络带宽 [屏幕截图]()

 * **Ifstat**：以批处理方式报告网络带宽. 输出采用易于使用其他程序或实用程序记录和解析的格式.  [截图]()


 * **Iptraf-ng**：是一款交互式多彩的 IP 局域网监视器. 它显示了各个连接和主机之间流动的数据量. 已不复存在的 iptraf 的维护分支. [Screenshot](https://wiki.ipfire.org/addons/iptraf-ng/iptraf-ng_monitor.png)

* **Jnettop**： [Jnettop](http://jnettop.kubs.info/wiki/) 是一个流量可视化器，它捕获通过它运行的主机的流量并显示按它们使用的带宽排序的流. [Screenshot](http://jnettop.kubs.info/wiki/?binary=internal%3A%2F%2F76195466cc3bca92f8de7b404e240844.gif)










 * **Vnstat**：与大多数其他工具略有不同. 它实际上运行一个后台服务/守护进程，并一直记录数据传输的大小. 接下来，它可用于生成网络使用历史报告.  [截图]()



Traffic Capture<a name="capture"></a>
---------------

* [Libpcap/Tcpdump](http://www.tcpdump.org/) : tcpdump 官方网站，强大的命令行数据包分析器； 和 libpcap，一个用于网络流量捕获的可移植 C/C++ 库.

* [Ngrep](http://ngrep.sourceforge.net/) : 力求提供 GNU grep 的大部分通用功能，将它们应用到网络层.  ngrep 是一个 pcap-aware 工具，它允许您指定扩展的正则或十六进制表达式以匹配数据包的数据负载. 它目前识别跨以太网、PPP、SLIP、FDDI、令牌环和空接口的 TCP、UDP 和 ICMP，并以与更常见的数据包嗅探工具（如 tcpdump 和 snoop）相同的方式理解 bpf 过滤器逻辑.

* [clj-net-pcap](https://github.com/ruedigergad/clj-net-pcap) : `clj-net-pcap` 是一个用于 Clojure 的数据包捕获库.  clj-net-pcap 使用 jNetPcap 并围绕 jNetPcap 添加便利功能以简化可用性. 一 [paper on clj-net-pcap](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?tp=&arnumber=6903107) 已在 COMPSACW 2014 范围内发布.

* [jNetPcap](https://sourceforge.net/projects/jnetpcap/) : jNetPcap 是一个用于 Java 的数据包捕获库，可用于 Linux 和 Windows.  jNetPcap 分别利用 libpcap 和 WinPcap，并采用 Java Native Interface (JNI) 来使用 libpcap/WinPcap 提供的功能.

* [Arkime](https://arkime.com/) Arkime（前身为 Moloch）是一个大规模、开源、索引的数据包捕获和搜索工具.

* [n2disk](http://www.ntop.org/products/n2disk/)  （商业）：具有索引功能的多千兆网络流量记录器.  n2disk 是一个网络流量记录器应用程序. 使用 n2disk，您可以从实时网络接口以多千兆位速率（在足够的硬件上超过 10 Gigabit/s）捕获全尺寸网络数据包，并将它们写入文件而不会丢失任何数据包.

* [Netis Packet Agent](https://github.com/Netis/packet-agent)：它是一个通过 GRE 隧道的远程数据捕获实用程序，它使您可以轻松地从 NIC 接口捕获数据包，用 GRE 封装它们并将它们发送到远程机器进行监控和分析.

* [OpenFPC](http://www.openfpc.org/) ：OpenFPC 是一组脚本，结合起来提供一个轻量级的全包网络流量记录器和缓冲工具. 它的设计目标是允许非专家用户在 COTS 硬件上部署分布式网络流量记录器，同时集成到现有的警报和日志工具中.

* [PF_RING](http://www.ntop.org/products/pf_ring/) : PF_RING 是一种新型的网络套接字，极大地提高了数据包捕获速度. 适用于 Linux 内核 2.6.32 和更新版本. 无需修补内核.  PF_RING 感知驱动程序，用于增加数据包捕获加速.

* [TTT](http://www.csl.sony.co.jp/person/kjc/kjc/software.html#ttt) : (Tele Traffic Tapper) 是 tcpdump 的另一个后代，但它能够进行实时、图形化和远程流量监控.  ttt 不会取代 tcpdump，相反，它可以帮助您找出 tcpdump 需要查看的内容.  ttt 监控网络并在时间窗口内自动挑选流量的主要贡献者. 默认情况下，图表每秒更新一次.

* [Yaf](https://tools.netsa.cert.org/yaf/yaf.html) : 这是一款可靠的软件，非常可靠，能够从 pcap 生成流量记录. 这对于索引巨大的 pcap 甚至进行数据包捕获非常有用. 最近的版本甚至可以提取有效载荷并放入流记录中.


流量分析/检查<a name="analysis"></a>
--------------------------------------------------
* [BruteShark](https://github.com/odedshimon/BruteShark) ：是一款开源、跨平台的网络取证分析工具，功能众多. 它包括：密码提取、显示可视化网络地图、重建 TCP 会话、提取加密密码的哈希值，甚至将它们转换为 Hashcat 格式以执行离线暴力攻击.

* [AIEngine](https://bitbucket.org/camp0/aiengine) : 是下一代交互式/可编程数据包检查引擎，具有无需任何人工干预的学习能力、NIDS 功能、DNS 域分类、网络收集器等.  AIEngine 还帮助网络/安全专业人员识别流量并开发用于 NIDS、防火墙、流量分类器等的签名.

* [CapAnalysis](http://www.capanalysis.net/ca/)  - CapAnalysis 是一个 Web 可视化工具，适用于信息安全专家、系统管理员和需要分析大量捕获的网络流量的每个人. 现场网络演示是 [available](http://pcap.capanalysis.net/) 用于测试.

* [CapTipper](https://github.com/omriher/CapTipper): 恶意 HTTP 流量浏览器

* [Chopshop](https://github.com/MITRECND/chopshop): 是一个 MITRE 开发的框架，用于帮助分析人员创建和执行基于 pynids 的 APT 交易解码器和检测器.

* [CoralReef](http://www.caida.org/tools/measurement/coralreef/) : 是由 CAIDA 开发的软件套件，用于分析被动 Internet 流量监视器收集的数据. 它提供了一个编程库 libcoral，类似于 libpcap，具有针对 ATM 和其他网络类型的扩展，可从 C 和 Perl 获得.

* [DPDK](http://dpdk.org/) : 是一组用于快速数据包处理的库和驱​​动程序. 它被设计为在任何处理器上运行. 第一个支持的 CPU 是 Intel x86，现在扩展到 IBM Power 8、EZchip TILE-Gx 和 ARM. 它主要在 Linux 用户区运行.  FreeBSD 端口可用于 DPDK 功能的子集.

* [DPKT](https://github.com/kbandla/dpkt)：Python 数据包创建/解析库.

* [ECap](https://bitbucket.org/nathanj/ecap/wiki) : (External Capture) 是一个带有 Web 前端的分布式网络嗅探器.  Ecap 是多年前在 2005 年编写的，但是 tcpdump-workers 邮件列表上的一个帖子请求了一个类似的应用程序......所以它在这里. 如果有任何兴趣，更新它并再次处理它会很有趣.

* [EtherApe](http://etherape.sourceforge.net/) : 是模仿 etherman 的 Unix 图形网络监视器. 具有链路层、ip 和 TCP 模式，它以图形方式显示网络活动. 主机和链接的大小随流量而变化. 彩色编码协议显示. 它支持以太网、FDDI、令牌环、ISDN、PPP 和 SLIP 设备. 它可以过滤要显示的流量，可以从文件中读取流量，也可以从网络中实时读取流量.

* [HttpSniffer](https://github.com/caesar0301/http-sniffer) ：一种多线程工具，用于从 PCAP 文件中嗅探 TCP 流统计信息和嵌入的 HTTP 标头. 每个携带 HTTP 的 TCP 流都以 JSON 格式导出为文本文件.


* [ITA](http://ita.ee.lbl.gov/) ：互联网流量档案是一个经过审核的存储库，支持广泛访问互联网网络流量的踪迹，由 ACM SIGCOMM 赞助. 跟踪可用于研究网络动态、使用特征和增长模式，以及为跟踪驱动的模拟提供基础. 该存档还对用于将原始跟踪数据减少为更易于管理的形式、生成合成跟踪和分析跟踪的程序开放.

* [Joy](https://github.com/cisco/joy) ：joy 是开发的流量分析解析工具. 部分是为了帮助对加密的流量流进行分类，例如 HTTPS 流量. 它能够将 pcap 文件解析为可用的 json 文件，其中包含有关捕获统计信息和功能的详细信息.

* [Libcrafter](http://code.google.com/p/libcrafter/) : 是 C++ 的高级库，旨在简化网络数据包的创建和解码. 它能够制作或解码大多数常见网络协议的数据包，通过网络发送它们，捕获它们并匹配请求和回复.

* [Libnet](http://libnet.sourceforge.net/) : 是帮助构建和处理网络数据包的例程集合. 它为低级网络数据包整形、处理和注入提供了一个可移植的框架.  Libnet 在 IP 层和链路层具有可移植的数据包创建接口，以及许多补充和补充功能. 使用 libnet，可以毫不费力地创建快速简单的数据包组装应用程序.

* [Libnids](http://libnids.sourceforge.net/) ：由 Rafal Wojtczuk 设计，是网络入侵检测系统 E 组件的实现. 它模拟 Linux 2.0.x 的 IP 堆栈.  Libnids 提供 IP 碎片整理、TCP 流组装和 TCP 端口扫描检测.  libnids 最有价值的特性是可靠性. 进行了大量测试，证明 libnids 尽可能接近地预测受保护 Linux 主机的行为.

* [Multitail](http://www.vanheusden.com/multitail) ：现在包含用于监视 tcpdump 输出的颜色方案. 它还可以过滤、将时间戳转换为时间字符串等等.

* [Netsniff-ng](https://github.com/caesar0301/awesome-pcaptools/blob/master/www.github.com/borkmann/netsniff-ng)：Netsniff-ng 是免费 Linux 网络实用程序的工具包，如果您愿意，它是您日常 Linux 网络管道的瑞士军刀.

* [NetDude](http://netdude.sourceforge.net/) ：（网络转储数据显示和编辑器）. 在他们的网页上，“它是一个基于 GUI 的工具，允许您对 tcpdump 跟踪文件中的数据包进行详细更改.”

* [Network Expect](http://www.netexpect.org/) : 是一个框架，允许轻松构建可以与网络流量交互的工具. 遵循脚本，可以将流量注入网络，并且可以根据接收到的网络流量做出决定并采取行动. 解释型语言提供分支和高级控制结构来指导与网络的交互.  Network Expect 使用 libpcap 进行数据包捕获，使用 libwireshark（来自 Wireshark 项目）进行数据包解析任务.  （GPL、BSD/Linux/OSX）.

* [NFStream](https://github.com/nfstream/nfstream) : 是一个 Python 框架，提供快速、灵活和富有表现力的数据结构，旨在使在线或离线网络数据的处理既简单又直观. 它旨在成为在 Python 中进行实用的、真实世界的网络数据分析的基本高级构建块. 此外，它还有一个更广泛的目标，即成为研究人员的通用网络数据分析框架，提供跨实验的数据可重复性.

* [Ntop](http://www.ntop.org/) : Ntop 是一个显示网络使用情况的网络流量探测器，类似于流行的 top Unix 命令所做的.  ntop 基于 libpcap，它以可移植的方式编写，以便在每个 Unix 平台和 Win32 上虚拟运行.

* [Ntopng](http://www.ntop.org/products/ntop/) : Ntopng 是原始 ntop 的下一代版本，一个网络流量探测器，显示网络使用情况，类似于流行的 top Unix 命令所做的.  ntop 基于 libpcap 并且以可移植的方式编写，以便在每个 Unix 平台、MacOSX 和 Win32 上虚拟运行.

* [PacketQ](https://github.com/dotse/PacketQ) ：一种为 PCAP 文件提供基本 SQL 前端的工具. 输出 JSON、CSV 和 XML，并包含一个带有 JSON-api 的内置网络服务器和一个漂亮的 AJAX GUI.

* [Pcap2har](https://github.com/andrewf/pcap2har)：使用库 dpkt 将 .pcap 网络捕获文件转换为 HTTP 存档文件的程序.

* [PcapPlusPlus](https://github.com/seladb/PcapPlusPlus) : PcapPlusPlus 一个多平台的 C++ 网络嗅探和数据包解析和操作框架. 它旨在轻巧、高效且易于使用. 它是对 libpcap、WinPcap、DPDK 和 PF_RING 等流行引擎的 C++ 包装器. 它还包含许多协议的解析和编辑功能，包括以太网、IPv4、IPv6、ARP、VLAN、MPLS、PPPoE、GRE、TCP、UDP、ICMP、DNS 以及 HTTP 和 SSL/TLS 等第 7 层协议

* [pkt2flow](https://github.com/caesar0301/pkt2flow) ：一个将数据包分类为流的简单实用程序. 它是如此简单，以至于只有一项任务旨在完成. 对于深度包检测或流分类，分析一个特定流的特征是很常见的. 我已经尝试使用现成的工具，如 tcpflows、tcpslice、tcpsplit，但所有这些工具都试图减少跟踪量（在要求下）或将数据包类似于流有效载荷（超过要求）. 我还没有找到一个简单的工具来将数据包分类为流而无需进一步处理.

* [potiron](https://github.com/CIRCL/potiron)：规范化、索引、丰富和可视化网络捕获.

* [pyshark](http://kiminewt.github.io/pyshark/) ：tshark 的 Python 包装器，允许使用wireshark 解剖器解析 python 数据包.  python 数据包解析模块有很多，这个不同，因为它实际上不解析任何数据包，它只是使用 tshark（wireshark 命令行实用程序）导出 XML 的能力来使用它的解析.


* [Scapy](http://www.secdev.org/projects/scapy/) ：Scapy 是一个强大的交互式数据包操作程序. 它能够伪造或解码多种协议的数据包，通过网络发送它们，捕获它们，匹配请求和回复等等. 它可以轻松处理大多数经典任务，如扫描、跟踪路由、探测、单元测试、攻击或网络发现（它可以替代 hping、85% 的 nmap、arpspoof、arp-sk、arping、tcpdump、tethereal、p0f 等）. 它还在大多数其他工具无法处理的许多其他特定任务中表现出色，例如发送无效帧、注入您自己的 802.11 帧、结合技术（VLAN 跳跃 + ARP 缓存中毒、WEP 加密通道上的 VOIP 解码、. ..）等.

* [Sniff](http://www.thedumbterminal.co.uk/software/sniff.html)：使 tcpdump 程序的输出更易于阅读和解析.

* [Snort](http://www.snort.org/) ：Snort 是 Sourcefire 开发的开源网络入侵防御和检测系统（IDS/IPS），现归思科所有.  Snort 结合了签名、协议和基于异常的检查的优点，是全球部署最广泛的 IDS/IPS 技术. 凭借数百万次下载和大约 500,000 名注册用户，Snort 已成为 IPS 的事实上的标准.

* [Socket Sentry](http://code.google.com/p/socket-sentry)：Socket Sentry 是 KDE Plasma 的实时网络流量监视器，其精神与 iftop 和 netstat 等工具相同.

* [Suricata](https://suricata-ids.org): Suricata is a free and open source, mature, fast and robust network threat detection engine.  The Suricata engine is capable of real time intrusion detection (IDS), inline intrusion prevention (IPS), network security monitoring (NSM) and offline pcap processing.


* [Tcpdpriv](http://ita.ee.lbl.gov/html/contrib/tcpdpriv.html) : Tcpdpriv 是一个程序，用于从网络接口上收集的数据包（或使用 tcpdump 的 -w 参数创建的跟踪文件）中消除机密信息（用户数据和地址）.  Tcpdpriv 删除 TCP 和 UDP 的有效负载，以及其他协议的整个 IP 有效负载. 它实现了几种地址加扰方法； 顺序编号方法及其变体，以及保留地址前缀的散列方法.

* [Tcpflow](https://github.com/simsong/tcpflow) ：捕获作为 TCP 连接（流）的一部分传输的数据，并以方便协议分析或调试的方式存储数据的程序. 像“tcpdump”这样的程序会显示在线路上看到的数据包的摘要，但通常不存储实际传输的数据. 相比之下，tcpflow 重建实际数据流并将每个流存储在单独的文件中以供以后分析. 然而，可选地，它可以隔离每个 tcp 流的 pcap 流以进行细化检查. [Original link](http://www.circlemud.org/jelson/software/tcpflow/).


* [Tcpreplay](http://tcpreplay.synfin.net/): 使用 libnet 在接口上重放 pcap 文件.

* [Tcpslice](https://github.com/caesar0301/awesome-pcaptools/blob/master/https://github.com/caesar0301/awesome-pcaptools/blob/master/ftp://ftp.ee.lbl.gov/tcpslice.tar.gz) : Tcpslice 是一种用于提取使用 tcpdump 的 -w 标志生成的数据包跟踪文件部分的工具. 它可以组合多个跟踪文件，和/或根据时间提取一个或多个跟踪的部分. [From the tcpdump CVS server](https://github.com/caesar0301/awesome-pcaptools/blob/master/https://github.com/caesar0301/awesome-pcaptools/blob/master/ftp://ftp.ee.lbl.gov/tcpslice.tar.gz).

* [Tcpsplit](http://www.icir.org/mallman/software/tcpsplit/) ：一种将单个 libpcap 数据包跟踪分解为若干子跟踪的工具，沿 TCP 连接边界分解跟踪，以便 TCP 连接不会最终拆分为两个子跟踪. 这对于使大型跟踪文件易于进行深入分析和对跟踪进行子集化以便仅对跟踪的一部分进行分析非常有用.

* [Tcpstat](http://www.frenchfries.net/paul/tcpstat/) : Tcpstat 报告某些网络接口统计信息，就像 vmstat 对系统统计信息所做的一样.  tcpstat 通过监视特定接口或从文件中读取先前保存的 tcpdump 数据来获取其信息.

* [Tcptrace](https://github.com/blitz/tcptrace) ：由俄亥俄大学的 Shawn Ostermann 编写的工具，用于分析 TCP 转储文件. 它可以将几种流行的数据包捕获程序生成的文件作为输入，包括 tcpdump、snoop、etherpeek、HP Net Metrix 和 WinDump.  tcptrace 可以生成几种不同类型的输出，其中包含有关所看到的每个连接的信息，例如经过的时间、发送和接收的字节和段、重传、往返时间、窗口广告、吞吐量等. 它还可以生成许多图形以供进一步分析.

* [TraceWrangler](https://www.tracewrangler.com/) ：TraceWrangler 是一个运行在 Windows（或 Linux，使用 WINE）上的网络捕获文件工具包，它支持 PCAP 以及新的 PCAPng 文件格式，它现在是 Wireshark 使用的标准文件格式.  TraceWrangler 最突出的用例是 PCAP 和 PCAPng 文件（有时称为“跟踪文件”、“捕获文件”或“数据包捕获”）的轻松清理和匿名化，在易于使用的同时删除或替换敏感数据.

* [Tstat](http://tstat.tlc.polito.it/)：一个被动嗅探器，能够提供关于网络和传输级别的流量模式的多种见解，具有大量的流量特征.

* [WAND](http://research.wand.net.nz/) ：基于 libtrace 构建的用于处理网络流量的精彩工具集合，来自怀卡托大学. 我喜欢这个项目！

* [WinPcap](http://www.tcpdump.org/wpcap.html)：来自 Guy Harris 的关于 WinPcap 和 WinDump 状态的消息摘录.

* [WireEdit](https://wireedit.com/) : WireEdit 是一个免费的桌面 WYSIWYG 网络数据包编辑器. 它允许将任何堆栈层编辑为“富文本”，而无需了解数据包语法和编码规则. 输入输出文件格式为 Pcap.

* [Wireshark suit](http://wiki.wireshark.org/Tools) : 众所周知的工具套装，支持数据包分析器和协议解码器. 它还包括一些实用的工具和脚本，以支持大多数常见用法.

* [Xplot](http://www.xplot.org/): 程序 xplot 是在 1980 年代后期编写的，用于支持 TCP 数据包跟踪的分析.

* [yaraPcap](https://github.com/kevthehermit/YaraPcap): 使用 YARA 处理 HTTP Pcaps

* [yaraprocessor](https://github.com/MITRECND/yaraprocessor) ：使用 yaraprocessor YARA 可以针对单个数据包有效载荷以及部分或全部有效载荷的串联运行. 它最初是为在 Chopshop 中使用而编写的，但也可以在没有它的情况下使用.

“Zeek 为网络流量分析提供了一个综合平台，特别关注大规模语义安全监控.虽然通常与经典的入侵检测/预防系统相比，Zeek 采取了截然不同的方法，为用户提供了一个灵活的框架，便于定制、深度监控远远超出传统系统的能力.随着初始版本在 90 年代中期已经投入运营部署，Zeek 发现自己已经建立了 20 多年的研究基础.有关更多信息，请参阅 Zeek 概述和我们的宣传文件，为什么选择Zeek？”

DNS 实用程序<a name="dnstools"></a>
--------------------------------------------

* [dnsgram](https://doc.powerdns.com/md/manpages/dnsgram.1/) : dnsgram 是用于间歇性解析器故障的调试工具. 它需要一个或多个输入 PCAP 文件并生成 5 秒段的统计数据，从而可以研究间歇性解析器问题.

* [dnsreplay](https://doc.powerdns.com/md/manpages/dnsreplay.1/) ：Dnsreplay 获取记录的问题和答案，并将它们重播到指定的名称服务器，然后报告匹配的答案百分比，是更糟还是更好. 然后将答案和其他一些指标与转储文件中找到的实际指标进行比较.

* [dnsscan](https://doc.powerdns.com/md/manpages/dnsscan.1/): dnsscan 采用 PCAP 格式的一个或多个 INFILE，并生成每个查询类型的查询数量列表.

* [dnsscope](https://doc.powerdns.com/md/manpages/dnsscope.1/): dnsscope 接受输入 PCAP 并生成一些简单的统计信息输出到控制台.

* [dnswasher](https://doc.powerdns.com/md/manpages/dnswasher.1/) : dnswasher 采用 PCAP 格式的输入文件并写出 PCAP 文件，同时混淆最终用户的 IP 地址. 这对于在尝试保护用户隐私的同时与第三方共享数据很有用.


文件提取<a name="fileextraction"></a>
--------------------------------------------


* [Dsniff](http://www.monkey.org/~dugsong/dsniff/) ：Dsniff 是用于网络审计和渗透测试的工具集合.  dsniff、filesnarf、mailsnarf、msgsnarf、urlsnarf 和 webspy 被动地监视网络以获取有趣的数据（密码、电子邮件、文件等）.  arpspoof、dnsspoof 和 macof 有助于拦截攻击者通常无法获得的网络流量（例如，由于第 2 层交换）.  sshmitm 和 webmitm 通过利用 ad-hoc PKI 中的弱绑定，对重定向的 SSH 和 HTTPS 会话实施主动中间猴子攻击.

* [Foremost](http://foremost.sourceforge.net/) : 是一个控制台程序，用于根据文件的页眉、页脚和内部数据结构恢复文件. 这个过程通常被称为数据雕刻.  Foremost 可以处理图像文件，例如由 dd、Safeback、Encase 等生成的文件，也可以直接处理驱动器. 页眉和页脚可以由配置文件指定，也可以使用命令行开关指定内置文件类型. 这些内置类型查看给定文件格式的数据结构，从而实现更可靠和更快的恢复.

* [Justniffer](http://justniffer.sourceforge.net/): Justniffer is a network protocol analyzer that captures network traffic and produces logs in a customized way, can emulate Apache web server log files, track response times and extract all "intercepted" files from the HTTP traffic.

* [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) ：NetworkMiner 是适用于 Windows 的网络取证分析工具 (NFAT)（但也适用于 Linux / Mac OS X / FreeBSD）.  NetworkMiner 可用作被动网络嗅探器/数据包捕获工具，以检测操作系统、会话、主机名、开放端口等，而无需在网络上放置任何流量.  NetworkMiner 还可以解析 PCAP 文件以进行离线分析，并从 PCAP 文件中重新生成/重组传输的文件和证书.

* [pcapfex](https://github.com/vikwin/pcapfex)  - Packet CAPture Forensic Evidence eXtractor (pcapfex) 是一种从数据包捕获文件中查找和提取文件的工具. 它的强大之处在于它的易用性. 只需提供一个 pcap 文件，它就会尝试提取所有文件. 它是一个可扩展的平台，因此可以轻松添加要识别和提取的其他文件类型.

* [scalpel](https://github.com/sleuthkit/scalpel)：Scalpel 是一个开源的数据雕刻工具.

* [Snort](http://www.snort.org/) ：是Sourcefire开发的开源网络入侵防御和检测系统（IDS/IPS），现归思科所有.  Snort 结合了签名、协议和基于异常的检查的优点，是全球部署最广泛的 IDS/IPS 技术.

* [Tcpick](http://tcpick.sourceforge.net/) : 是一个基于 libpcap 的文本模式嗅探器，可以跟踪、重组和重新排序 tcp 流.  Tcpick 能够将捕获的流保存在不同的文件中或在终端中显示它们，因此它对嗅探通过 ftp 或 http 传输的文件很有用. 它可以在终端上显示所有流，当连接关闭时，以不同的显示模式，如 hexdump、hexdump + ascii、仅可打印字符、原始模式等.

* [Tcpxtract](http://tcpxtract.sourceforge.net/) : 是一种基于文件签名从网络流量中提取文件的工具. 根据文件类型的页眉和页脚（有时称为“雕刻”）提取文件是一种古老的数据恢复技术.


USB
---
### Capture tools
* [usbmon](https://www.kernel.org/doc/Documentation/usb/usbmon.txt) - Linux 内核的一个子系统，用于捕获 USB 数据包.
* [USBPcap](https://github.com/desowin/usbpcap) - Windows 的解决方案.

### Analysis
* [USBPcapOdinDumper](https://github.com/KOLANICH/USBPcapOdinDumper) - 使用`usbmon`和`USBPcap`帧格式转换 .pcap 文件，这些帧格式来自使用 Odin 刷新 Android 手机或 [Heimdall](https://gitlab.com/BenjaminDobell/Heimdall) 到一组带有帧有效载荷的文件中. 对逆向工程很有用. 具有模块化架构，可轻松转换为其他应用程序格式.


相关项目<a name="others"></a>
--------------------------------------

* [BPF for Ultrix](http://www.tcpdump.org/other/bpfext42.tar.Z)：用于 Ultrix 4.2 的 BPF 发行版，包含源代码和二进制模块.

* [BPF+](http://www.cs.berkeley.edu/~abegel/sigcomm99/bpf+.ps)：在通用数据包过滤器架构中利用全局数据流优化 作者：Andrew Begel、Steven McCanne 和 Susan Graham.

* [FFT-FGN-C](http://ita.ee.lbl.gov/html/contrib/fft_fgn_c.html) : 是一种用于合成一种称为分数高斯噪声的自相似过程的程序. 该程序很快，但近似. 分数高斯噪声只是一种自相似过程. 使用此程序合成网络流量时，您必须记住，使用其他进程之一对您寻找的流量进行建模可能会更好.

* [Haka](http://www.haka-security.org/) ：一种面向安全的开源语言，它允许描述协议并在（实时）捕获的流量上应用安全策略. 哈卡语的范围是双重的. 首先，它允许编写安全规则以过滤/更改/删除不需要的数据包并记录和报告恶意活动. 其次，Haka 具有能够指定网络协议及其底层状态机的语法.

* [RIPE-NCC Hadoop for PCAP](https://github.com/RIPE-NCC/hadoop-pcap) ：一个用于读取数据包捕获 (PCAP) 文件的 Hadoop 库. 捆绑用于读取 PCAP 的代码. 可在 MapReduce 作业中使用以本机读取 PCAP 文件. 还具有 Hive 串行器/解串器 (SerDe) 以使用类似 SQL 的命令查询 PCAP.

* [Traffic Data Repository at the WIDE Project](http://www.sonycsl.co.jp/person/kjc/papers/freenix2000/) ：对于网络研究人员和运营商而言，了解网络流量趋势并发现网络流量异常变得越来越重要. 本文描述了 WIDE 项目中正在进行的一项工作，即收集一组免费工具来构建包含我们主干流量详细信息的流量数据存储库.  tcpdump 收集流量踪迹，去除隐私信息后，向公众公开. 我们回顾了用户隐私问题，然后是用于构建 WIDE 流量存储库的工具. 我们将在 IPv6 部署的早期阶段报告当前状态和发现.

* [Usenix93 Paper on BPF](https://github.com/caesar0301/awesome-pcaptools/blob/master/ftp://ftp.ee.lbl.gov/papers/bpf-usenix93.ps.Z) ：libpcap接口支持基于BSD包过滤器架构的过滤机制.  BPF 在 1993 年 Winter Usenix 论文“The BSD Packet Filter: A New Architecture for User-level Packet Capture”中有所描述.
