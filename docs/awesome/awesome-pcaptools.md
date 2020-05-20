<div class="github-widget" data-repo="caesar0301/awesome-pcaptools"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
Introduction
------------

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/caesar0301/awesome-pcaptools.svg)](https://travis-ci.org/caesar0301/awesome-pcaptools)

 该项目不包含任何源代码或文件.  我只想列出用于处理网络流量研究中的pcap文件的工具列表.  有关更多很棒的列表，请参见https://github.com/sindresorhus/awesome

**许可证**：Apache许可证v2.





Linux命令<a name="linuxcmds"></a>
--------------------------------------


 * ** Bwm-ng ** ：（下一代带宽监视器）是另一种非常简单的实时网络负载监视器，它报告有关数据在系统中所有可用网络接口中进出传输速度的摘要.  [截图]（）


 * ** Collectl **：以类似于dstat的样式报告系统统计信息，像dstat一样，它收集有关各种不同系统资源（例如cpu，内存，网络等）的统计信息.在这里是一个简单的示例，介绍了如何使用它报告网络使用情况/带宽.  [截图]（）

 * ** Dstat **：是一种多功能工具（用python编写），可以监视不同的系统统计数据并以批处理样式模式将其报告或将数据记录到csv或类似文件中.  本示例说明如何使用dstat报告网络带宽[截屏]（）

 * ** Ifstat **：以批处理方式报告网络带宽.  输出的格式易于使用其他程序或实用程序进行记录和解析.  [截图]（）



* ** Jettettop **： [Jnettop](http://jnettop.kubs.info/wiki/) 是流量可视化工具，它捕获通过其运行的主机的流量并显示按其使用的带宽排序的流. [Screenshot](http://jnettop.kubs.info/wiki/?binary=internal%3A%2F%2F76195466cc3bca92f8de7b404e240844.gif)










 * ** Vnstat **：与大多数其他工具有点不同.  它实际上运行一个后台服务/守护程序，并一直记录着数据传输的大小.  接下来，它可以用于生成网络使用历史记录的报告.  [截图]（）



流量捕获<a name="capture"></a>
---------------

* [Libpcap/Tcpdump](http://www.tcpdump.org/) ：tcpdump的官方站点，一个功能强大的命令行数据包分析器；  和libpcap，一个用于网络流量捕获的便携式C / C ++库.

* [Ngrep](http://ngrep.sourceforge.net/) ：努力提供GNU grep的大多数通用功能，并将其应用于网络层.  ngrep是可识别pcap的工具，可让您指定扩展的正则表达式或十六进制表达式以与数据包的数据有效载荷匹配.  目前，它可以识别以太网，PPP，SLIP，FDDI，令牌环和空接口上的TCP，UDP和ICMP，并以与更常见的数据包嗅探工具（例如tcpdump和snoop）相同的方式理解bpf过滤器逻辑.

* [clj-net-pcap](https://github.com/ruedigergad/clj-net-pcap) ：`clj-net-pcap`是Clojure的数据包捕获库.  clj-net-pcap使用jNetPcap并在jNetPcap周围添加了便利功能，以简化可用性.  一个 [paper on clj-net-pcap](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?tp=&arnumber=6903107) was published in scope of COMPSACW 2014.

* [jNetPcap](http://jnetpcap.com) ：jNetPcap是Java的数据包捕获库，可用于Linux和Windows.  jNetPcap分别利用libpcap和WinPcap，并使用Java本机接口（JNI）来使用libpcap / WinPcap提供的功能.

* [Moloch](https://github.com/aol/moloch)：Moloch是一个开源的大规模完整PCAP捕获，索引和数据库系统.

* [n2disk](http://www.ntop.org/products/n2disk/)  （商业）：具有索引功能的多千兆位网络流量记录器.  n2disk是一个网络流量记录器应用程序.  使用n2disk，您可以从实时网络接口以几千兆位的速率（在足够的硬件上以10 Gb / s的速率）捕获完整的网络数据包，并将其写入文件中而不会丢失任何数据包.

* [Netis Packet Agent](https://github.com/Netis/packet-agent)：这是通过GRE隧道的远程数据捕获实用程序，它使您可以轻松地从NIC接口捕获数据包，将它们与GRE封装在一起，然后将其发送到远程计算机进行监视和分析.

* [OpenFPC](http://www.openfpc.org/) ：OpenFPC是一组脚本，它们组合在一起提供了轻量级的全包网络流量记录器和缓冲工具.  其设计目标是允许非专家用户在集成到现有警报和日志工具的同时，在COTS硬件上部署分布式网络流量记录器.

* [PF_RING](http://www.ntop.org/products/pf_ring/) ：PF_RING是一种新型的网络套接字，可显着提高数据包捕获速度.  适用于Linux内核2.6.32及更高版本.  无需修补内核.  支持PF_RING的驱动程序，可提高数据包捕获速度.

* [TTT](http://www.csl.sony.co.jp/person/kjc/kjc/software.html#ttt) ：（Tele Traffic Tapper）是tcpdump的另一个后代，但是它能够进行实时，图形和远程流量监控.  ttt不会替代tcpdump，而是可以帮助您了解tcpdump的内容.  ttt监视网络并在时间窗口内自动选择流量的主要贡献者.  默认情况下，图形每秒更新一次.

* [Yaf](https://tools.netsa.cert.org/yaf/yaf.html) ：这是一个可靠的软件，功能强大，能够从pcap生成流量记录.  这对于索引巨大的pcap甚至进行数据包捕获非常有用.  最新版本甚至可以提取有效载荷并放入流记录中.


流量分析/检查<a name="analysis"></a>
--------------------------------------------------

* [AIEngine](https://bitbucket.org/camp0/aiengine) ：是下一代交互式/可编程数据包检查引擎，具有无需任何人工干预，NIDS功能，DNS域分类，网络收集器等的学习功能.  AIEngine还可以帮助网络/安全专业人员识别流量并开发签名，以在NIDS，防火墙，流量分类器等上使用它们.

* [Bro](http://bro-ids.org/) ：是一个基于Unix的开源网络入侵检测系统（NIDS），它可以被动地监视网络流量并查找可疑活动.  Bro通过首先解析网络流量以提取其应用程序级语义，然后执行面向事件的分析器来对入侵进行检测，这些分析器将活动与被认为有问题的模式进行比较.  它的分析包括检测特定攻击（包括由签名定义的攻击，也包括根据事件定义的攻击）和异常活动（例如，某些主机连接到某些服务，或尝试失败的连接模式）.

* [CapAnalysis](http://www.capanalysis.net/ca/)  -CapAnalysis是面向信息安全专家，系统管理员和需要分析大量捕获的网络流量的每个人的Web可视工具.  实时网络演示是 [available](http://pcap.capanalysis.net/) 用于检测.

* [CapTipper](https://github.com/omriher/CapTipper)：恶意HTTP流量浏览器

* [Chopshop](https://github.com/MITRECND/chopshop)：是MITER开发的框架，可帮助分析人员创建和执行基于APT贸易器的基于Pynid的解码器和检测器.

* [CoralReef](http://www.caida.org/tools/measurement/coralreef/) ：是由CAIDA开发的软件套件，用于分析被动Internet流量监视器收集的数据.  它提供了一个编程库libcoral，类似于libpcap，带有对ATM和其他网络类型的扩展，可以从C和Perl中获得.

* [DPDK](http://dpdk.org/) ：是用于快速数据包处理的一组库和驱动程序.  它旨在在任何处理器上运行.  第一个受支持的CPU是Intel x86，现在扩展到IBM Power 8，EZchip TILE-Gx和ARM.  它主要在Linux用户环境中运行.  FreeBSD端口可用于DPDK功能的子集.

* [DPKT](https://github.com/kbandla/dpkt)：Python数据包创建/解析库.

* [ECap](https://bitbucket.org/nathanj/ecap/wiki) ：（外部捕获）是具有Web前端的分布式网络嗅探器.  Ecap是在2005年写的，但在tcpdump-workers邮件列表上的一则帖子也请求了类似的应用程序.  如果有兴趣，对其进行更新并再次进行处理将很有趣.

* [EtherApe](http://etherape.sourceforge.net/) ：是一个以etherman建模的Unix图形网络监视器.  具有链接层，ip和TCP模式，它以图形方式显示网络活动.  主机和链接的大小随流量而变化.  显示颜色编码的协议.  它支持以太网，FDDI，令牌环，ISDN，PPP和SLIP设备.  它可以过滤要显示的流量，并且可以从文件读取流量以及从网络实时读取流量.

* [HttpSniffer](https://github.com/caesar0301/http-sniffer) ：一种多线程工具，用于从PCAP文件中嗅探TCP流统计信息和嵌入式HTTP标头.  每个带有HTTP的TCP流都以JSON格式导出到文本文件.


* [ITA](http://ita.ee.lbl.gov/) ：Internet流量存档是由ACM SIGCOMM赞助的经过审核的存储库，用于支持广泛访问Internet网络流量的痕迹.  这些跟踪可用于研究网络动态，使用特性和增长模式，并为跟踪驱动的仿真提供依据.  该档案库还向程序开放，用于将原始跟踪数据减少为更易于管理的形式，生成合成跟踪以及分析跟踪.

* [Joy](https://github.com/cisco/joy) ：joy是开发的流量分析和解析工具.  在某种程度上有助于分类加密的流量，例如HTTPS流量.  它能够将pcap文件解析为可用的json文件，其中包含有关捕获统计信息和功能的详细信息.

* [Libcrafter](http://code.google.com/p/libcrafter/) ：是C ++的高级库，旨在简化网络数据包的创建和解码.  它能够处理或解码最常见的网络协议的数据包，在线发送它们，捕获它们，并匹配请求和答复.

* [Libnet](http://libnet.sourceforge.net/) ：是例程的集合，以帮助构建和处理网络数据包.  它提供了用于底层网络数据包整形，处理和注入的可移植框架.  Libnet在IP层和链路层具有可移植的数据包创建接口，并具有许多补充和补充功能.  使用libnet，可以轻松快速地完成快速简单的数据包组装应用程序.

* [Libnids](http://libnids.sourceforge.net/) ：由Rafal Wojtczuk设计，是网络入侵检测系统的电子组件的实现.  它模拟Linux 2.0.x的IP堆栈.  Libnids提供IP碎片整理，TCP流组装和TCP端口扫描检测.  libnids最有价值的功能是可靠性.  进行了许多测试，证明libnids尽可能地预测受保护的Linux主机的行为.

* [Multitail](http://www.vanheusden.com/multitail) ：现在包含用于监视tcpdump输出的colorcheme.  它还可以过滤，将时间戳转换为时间字符串等.

* [Netsniff-ng](https://github.com/caesar0301/awesome-pcaptools/blob/master/www.github.com/borkmann/netsniff-ng)：Netsniff-ng是免费的Linux网络实用程序的工具包，如果您愿意的话，它是您日常使用Linux网络管道的瑞士军刀.

* [NetDude](http://netdude.sourceforge.net/) ：（网络DUmp数据显示和编辑器）.  在他们的网页上，“这是一个基于GUI的工具，可让您对tcpdump跟踪文件中的数据包进行详细更改.”

* [Network Expect](http://www.netexpect.org/) ：是一个允许轻松构建可与网络流量进行交互的工具的框架.  遵循脚本，可以将流量注入网络，并可以基于接收到的网络流量来做出决定并采取行动.  解释语言提供分支和高级控制结构，以指导与网络的交互.  Network Expect使用libpcap进行数据包捕获，并使用libwireshark（来自Wireshark项目）进行数据包分解任务.  （GPL，BSD / Linux / OSX）.

* [Ntop](http://www.ntop.org/) ：Ntop是一个网络流量探测器，它显示网络使用情况，类似于流行的top Unix命令所执行的操作.  ntop基于libpcap，并且以可移植的方式编写，以便实际上可以在每个Unix平台和Win32上运行.

* [Ntopng](http://www.ntop.org/products/ntop/) ：Ntopng是原始ntop的下一代版本，它是一个显示网络使用情况的网络流量探测器，类似于流行的top Unix命令所执行的操作.  ntop基于libpcap，并且以可移植的方式编写，以便实际上可以在每个Unix平台，MacOSX和Win32上运行.

* [PacketQ](https://github.com/dotse/PacketQ) ：一种为PCAP文件提供基本SQL前端的工具.  输出JSON，CSV和XML，并包括带有JSON-api和漂亮的AJAX GUI的内置Web服务器.

* [Pcap2har](https://github.com/andrewf/pcap2har)：使用库dpkt将.pcap网络捕获文件转换为HTTP存档文件的程序.

* [PcapPlusPlus](https://github.com/seladb/PcapPlusPlus) ：PcapPlusPlus是一个多平台C ++网络嗅探以及数据包解析和处理框架.  它意味着轻巧，高效且易于使用.  它是流行引擎（如libpcap，WinPcap，DPDK和PF_RING）的C ++包装器.  它还包含对许多协议的解析和编辑功能，包括以太网，IPv4，IPv6，ARP，VLAN，MPLS，PPPoE，GRE，TCP，UDP，ICMP，DNS以及第7层协议（如HTTP和SSL / TLS）

* [pkt2flow](https://github.com/caesar0301/pkt2flow) ：一个简单的实用程序，将数据包分类为流.  如此简单，以仅完成一项任务为目标.  对于深度包检查或流分类，分析一种特定流的功能非常普遍.  我已经尝试使用现成的工具，例如tcpflows，tcpslice，tcpsplit，但是所有这些工具都试图减少跟踪量（在需要时）或将数据包类似于流有效负载（在需求时）.  我没有找到一种简单的工具，无需进一步处理即可将数据包分类为流.

* [potiron](https://github.com/CIRCL/potiron)：规范化，索引化，丰富化和可视化网络捕获.

* [pyshark](http://kiminewt.github.io/pyshark/) ：tshark的Python包装器，允许使用Wireshark Dissector解析python数据包.  有很多python数据包解析模块，这是不同的，因为它实际上并不解析任何数据包，它只是使用tshark的（wireshark命令行实用程序）功能来导出XML以使用其解析.


* [Scapy](http://www.secdev.org/projects/scapy/): Scapy is a powerful interactive packet manipulation program. It is able to forge or decode packets of a wide number of protocols, send them on the wire, capture them, match requests and replies, and much more. It can easily handle most classical tasks like scanning, tracerouting, probing, unit tests, attacks or network discovery (it can replace hping, 85% of nmap, arpspoof, arp-sk, arping, tcpdump, tethereal, p0f, etc.). It also performs very well at a lot of other specific tasks that most other tools can't handle, like sending invalid frames, injecting your own 802.11 frames, combining technics (VLAN hopping+ARP cache poisoning, VOIP decoding on WEP encrypted channel, ...), etc.

* [Sniff](http://www.thedumbterminal.co.uk/software/sniff.html)：使tcpdump程序的输出更易于阅读和解析.

* [Snort](http://www.snort.org/) ：Snort是由Sourcefire开发的开源网络入侵防御和检测系统（IDS / IPS），现在归Cisco所有.  结合了签名，协议和基于异常的检查的优势，Snort是全球部署最广泛的IDS / IPS技术.  通过数百万的下载量和大约50万注册用户，Snort已成为IPS的事实上的标准.

* [Socket Sentry](http://code.google.com/p/socket-sentry)：Socket Sentry是KDE Plasma的实时网络流量监控器，其精神与iftop和netstat之类的工具相同.

* [Suricata](https://suricata-ids.org) ：Suricata是一个免费，开源，成熟，快速且强大的网络威胁检测引擎.  Suricata引擎能够进行实时入侵检测（IDS），内联入侵防御（IPS），网络安全监控（NSM）和离线pcap处理.


* [Tcpdpriv](http://ita.ee.lbl.gov/html/contrib/tcpdpriv.html) ：Tcpdpriv是用于从网络接口上收集的数据包（或使用tcpdump的-w参数创建的跟踪文件中）清除机密信息（用户数据和地址）的程序.  Tcpdpriv删除TCP和UDP的有效负载，以及其他协议的整个IP有效负载.  它实现了几种地址加扰方法.  顺序编号方法及其变体，以及保留地址前缀的哈希方法.

* [Tcpflow](https://github.com/simsong/tcpflow) ：一种程序，捕获作为TCP连接（流）一部分传输的数据，并以便于协议分析或调试的方式存储数据.  诸如“ tcpdump”之类的程序显示了网络上可见的数据包摘要，但通常不存储实际传输的数据.  相反，tcpflow会重建实际的数据流，并将每个流存储在单独的文件中，以供以后分析.  但是，可选地，它可以隔离每个tcp流的pcap流以进行粒度检查. [Original link](http://www.circlemud.org/jelson/software/tcpflow/).


* [Tcpreplay](http://tcpreplay.synfin.net/)：使用libnet在接口上重放pcap文件.

* [Tcpslice](https://github.com/caesar0301/awesome-pcaptools/blob/master/https://github.com/caesar0301/awesome-pcaptools/blob/master/ftp://ftp.ee.lbl.gov/tcpslice.tar.gz): Tcpslice is a tool for extracting portions of packet trace files generated using tcpdump's -w flag. It can combine multiple trace files, and/or extract portions of one or more traces based on time. [From the tcpdump CVS server](https://github.com/caesar0301/awesome-pcaptools/blob/master/https://github.com/caesar0301/awesome-pcaptools/blob/master/ftp://ftp.ee.lbl.gov/tcpslice.tar.gz).

* [Tcpsplit](http://www.icir.org/mallman/software/tcpsplit/) ：一种工具，可将单个libpcap数据包跟踪分为若干子跟踪，沿TCP连接边界中断跟踪，以使TCP连接最终不会拆分成两个子跟踪.  这对于使大型跟踪文件易于处理以进行深入分析以及为跟踪设置子集以仅对部分跟踪进行分析很有用.

* [Tcpstat](http://www.frenchfries.net/paul/tcpstat/) ：Tcpstat报告某些网络接口统计信息，就像vmstat进行系统统计一样.  tcpstat通过监视特定接口或通过从文件读取先前保存的tcpdump数据来获取其信息.

* [Tcptrace](https://github.com/blitz/tcptrace) ：由俄亥俄州大学的Shawn Ostermann编写的用于分析TCP转储文件的工具.  它可以将几种流行的数据包捕获程序（包括tcpdump，snoop，etherpeek，HP Net Metrix和WinDump）生成的文件作为输入.  tcptrace可以产生几种不同类型的输出，其中包含有关所看到的每个连接的信息，例如经过时间，发送和接收的字节和段，重传，往返时间，窗口广告，吞吐量等.  它还可以生成许多图形以供进一步分析.

* [TraceWrangler](https://www.tracewrangler.com/) ：TraceWrangler是在Windows（或在Linux，使用WINE的Linux上）上运行的网络捕获文件工具包，支持PCAP以及新的PCAPng文件格式，该格式现在是Wireshark使用的标准文件格式.  TraceWrangler最突出的用例是对PCAP和PCAPng文件（有时称为“跟踪文件”，“捕获文件”或“数据包捕获”）的易于清理和匿名化，在易于使用的同时删除或替换敏感数据.

* [Tstat](http://tstat.tlc.polito.it/)：一种被动嗅探器，能够通过大量流功能提供有关网络和传输级别的流量模式的几种见解.

* [WAND](http://research.wand.net.nz/) ：怀卡托大学（University of Waikato）上建立在libtrace上的一组出色的工具来处理网络流量.  我喜欢这个项目！

* [WinPcap](http://www.tcpdump.org/wpcap.html)：摘自Guy Harris关于WinPcap和WinDump状态的消息.

* [WireEdit](https://wireedit.com/) ：WireEdit是用于网络数据包的免费桌面WYSIWYG编辑器.  它允许将任何堆栈层都编辑为“富文本”，而无需了解数据包语法和编码规则.  输入和输出文件格式为Pcap.

* [Wireshark suit](http://wiki.wireshark.org/Tools) ：著名的工具套件，支持数据包分析器和协议解码器.  它还包括一些实用工具和脚本来支持大多数常用用法.

* [Xplot](http://www.xplot.org/)：xplot程序编写于1980年代后期，以支持对TCP数据包跟踪的分析.

* [yaraPcap](https://github.com/kevthehermit/YaraPcap)：使用YARA处理HTTP Pcap

* [yaraprocessor](https://github.com/MITRECND/yaraprocessor) ：使用yaraprocessor，YARA可以针对单个数据包有效负载以及部分或全部有效负载的串联运行.  它最初是为在Chopshop中使用而编写的，但也可以在没有它的情况下使用.


DNS实用程序<a name="dnstools"></a>
--------------------------------------------

* [dnsgram](https://doc.powerdns.com/md/manpages/dnsgram.1/) ：dnsgram是用于间歇性解析器故障的调试工具.  它需要一个或多个输入的PCAP文件，并生成5秒段的统计信息，从而可以研究间歇性解析程序问题.

* [dnsreplay](https://doc.powerdns.com/md/manpages/dnsreplay.1/) ：Dnsreplay记录已记录的问题和答案，然后将其重播到指定的名称服务器，然后报告匹配的答案的百分比是差还是好.  然后将答案和其他一些指标与转储文件中找到的实际指标进行比较.

* [dnsscan](https://doc.powerdns.com/md/manpages/dnsscan.1/)：dnsscan接受一个或多个PCAP格式的INFILE，并生成每种查询类型的查询数量列表.

* [dnsscope](https://doc.powerdns.com/md/manpages/dnsscope.1/)：dnsscope接受输入PCAP并生成一些简单的统计信息，并将其输出到控制台.

* [dnswasher](https://doc.powerdns.com/md/manpages/dnswasher.1/) 注意：dnswasher会获取PCAP格式的输入文件并写出PCAP文件，同时混淆最终用户的IP地址.  在尝试保护用户隐私时与第三方共享数据很有用.


文件提取<a name="fileextraction"></a>
--------------------------------------------


* [Dsniff](http://www.monkey.org/~dugsong/dsniff/) ：Dsniff是用于网络审核和渗透测试的工具的集合.  dsniff，filesnarf，mailsnarf，msgsnarf，urlsnarf和webspy被动监视网络中是否有有趣的数据（密码，电子邮件，文件等）.  arpspoof，dnsspoof和macof有助于拦截攻击者通常不可用的网络流量（例如，由于第2层交换所致）.  sshmitm和webmitm通过利用临时PKI中的弱绑定，对重定向的SSH和HTTPS会话实施主动的中间猴子攻击.

* [Foremost](http://foremost.sourceforge.net/) ：是一个控制台程序，用于根据文件头，页脚和内部数据结构恢复文件.  此过程通常称为数据雕刻.  最重要的是可以处理图像文件，例如dd，Safeback，Encase等生成的文件，也可以直接在驱动器上工作.  页眉和页脚可以由配置文件指定，也可以使用命令行开关指定内置文件类型.  这些内置类型查看给定文件格式的数据结构，从而实现更可靠和更快的恢复.

* [Justniffer](http://justniffer.sourceforge.net/)：Justniffer是一种网络协议分析器，可以捕获网络流量并以自定义方式生成日志，可以模拟Apache Web服务器日志文件，跟踪响应时间并从HTTP流量中提取所有“被拦截”的文件.

* [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) ：NetworkMiner是Windows的网络取证分析工具（NFAT）（但在Linux / Mac OS X / FreeBSD中也可以使用）.  NetworkMiner可用作被动网络嗅探器/数据包捕获工具，以便检测操作系统，会话，主机名，开放端口等，而无需在网络上放置任何流量.  NetworkMiner还可以解析PCAP文件以进行离线分析，并从PCAP文件重新生成/重组传输的文件和证书.

* [pcapfex](https://github.com/vikwin/pcapfex)  -数据包捕获取证证据提取器（pcapfex）是一种从数据包捕获文件中查找和提取文件的工具.  它的强大之处在于易于使用.  只需提供一个pcap文件，它将尝试提取所有文件.  它是一个可扩展的平台，因此可以轻松添加识别和提取文件的其他类型.

* [scalpel](https://github.com/sleuthkit/scalpel)：Scalpel是一个开源的数据雕刻工具.

* [Snort](http://www.snort.org/) ：是由Sourcefire开发的开源网络入侵防御和检测系统（IDS / IPS），现在由Cisco拥有.  结合了签名，协议和基于异常的检查的优势，Snort是全球部署最广泛的IDS / IPS技术.

* [Tcpick](http://tcpick.sourceforge.net/): is a textmode sniffer libpcap-based that can track, reassemble and reorder tcp streams. Tcpick is able to save the captured flows in different files or displays them in the terminal, and so it is useful to sniff files that are transmitted via ftp or http. It can display all the stream on the terminal, when the connection is closed in different display modes like hexdump, hexdump + ascii, only printable characters, raw mode and so on.

* [Tcpxtract](http://tcpxtract.sourceforge.net/) ：是一种基于文件签名从网络流量中提取文件的工具.  基于文件类型的页眉和页脚（有时称为“雕刻”）提取文件是一种古老的数据恢复技术.


USB
---
### Capture tools
* [usbmon](https://www.kernel.org/doc/Documentation/usb/usbmon.txt) -Linux内核的子系统，用于捕获USB数据包.
* [USBPcap](https://github.com/desowin/usbpcap) -Windows的解决方案.

### Analysis
* [USBPcapOdinDumper](https://github.com/KOLANICH/USBPcapOdinDumper) -通过使用Odin或Flash刷新Android手机的捕获的“ usbmon”和“ USBPcap”帧格式转换.pcap文件 [Heimdall](https://gitlab.com/BenjaminDobell/Heimdall)  放入具有帧有效载荷的一组文件中.  对逆向工程很有用.  具有易于转换为其他应用程序格式的模块化体系结构.


相关项目<a name="others"></a>
--------------------------------------

* [BPF for Ultrix](http://www.tcpdump.org/other/bpfext42.tar.Z)：用于Ultrix 4.2的BPF发行版，包括源代码和二进制模块.

* [BPF+](http://www.cs.berkeley.edu/~abegel/sigcomm99/bpf+.ps)：在通用数据包过滤器体系结构中利用全局数据流优化作者：Andrew Begel，Steven McCanne和Susan Graham.

* [FFT-FGN-C](http://ita.ee.lbl.gov/html/contrib/fft_fgn_c.html) ：是用于合成一种称为分数高斯噪声的自相似过程的程序.  该程序是快速但近似的.  分数高斯噪声只是自相似过程的一种.  使用此程序合成网络流量时，必须记住，可能是使用其他过程之一更好地模拟了要寻找的流量.

* [Haka](http://www.haka-security.org/) ：一种面向开源安全性的语言，它可以描述协议并将安全策略应用于（实时）捕获的流量.  哈卡语的范围是双重的.  首先，它允许编写安全规则以过滤/更改/丢弃不需要的数据包，并记录和报告恶意活动.  其次，Haka具有一种语法，可以指定网络协议及其底层状态机.

* [RIPE-NCC Hadoop for PCAP](https://github.com/RIPE-NCC/hadoop-pcap) ：一个Hadoop库，用于读取数据包捕获（PCAP）文件.  捆绑用于读取PCAP的代码.  可以在MapReduce作业中使用，以本地读取PCAP文件.  还具有Hive序列化器/反序列化器（SerDe），可使用类似SQL的命令查询PCAP.

* [Traffic Data Repository at the WIDE Project](http://www.sonycsl.co.jp/person/kjc/papers/freenix2000/) ：对于网络研究人员和运营商而言，了解网络流量趋势并发现其网络流量异常都变得越来越重要.  本文介绍了WIDE项目中正在进行的一项工作，该工作旨在收集一组免费工具来构建包含我们骨干网流量详细信息的流量数据库.  流量跟踪由tcpdump收集，并且在删除隐私信息之后，这些跟踪将向公众开放.  我们将审查有关用户隐私的问题，然后是用于构建WIDE流量存储库的工具.  我们将在IPv6部署的早期阶段报告当前状态和发现.

* [Usenix93 Paper on BPF](https://github.com/caesar0301/awesome-pcaptools/blob/master/ftp://ftp.ee.lbl.gov/papers/bpf-usenix93.ps.Z) ：libpcap接口支持基于BSD数据包过滤器中的体系结构的过滤机制.  BPF在1993年冬季的Usenix论文“ BSD数据包过滤器：用于用户级数据包捕获的新体系结构”中进行了描述.
