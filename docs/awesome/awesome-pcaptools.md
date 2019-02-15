<div class="github-widget" data-repo="caesar0301/awesome-pcaptools"></div>
Introduction
------------

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/caesar0301/awesome-pcaptools.svg)](https://travis-ci.org/caesar0301/awesome-pcaptools)

 此项目不包含任何源代码或文件.  我只是想列出一些工具来处理网络流量研究中的pcap文件.  有关更多精彩列表，请参阅https://github.com/sindresorhus/awesome

**许可证**：Apache许可证v2.





Linux命令<a name="linuxcmds"></a>
--------------------------------------


 * ** Bwm-ng ** :(下一代带宽监视器）是另一种非常简单的实时网络负载监视器，它报告数据传输进出系统所有可用网络接口的速度摘要.  [截图]（）


* **Collectl**: reports system statistics in a style that is similar to dstat, and like dstat it is gathers statistics about various different system resources like cpu, memory, network etc. Over here is a simple example of how to use it to report network usage/bandwidth. [Screenshot]()

 * ** Dstat **：是一个多功能工具（用python编写），可以监视不同的系统统计信息并以批处理方式模式报告它们，或者将数据记录到csv或类似文件中.  此示例显示如何使用dstat报告网络带宽[Screenshot]（）

 * ** Ifstat **：以批处理方式模式报告网络带宽.  输出的格式很容易使用其他程序或实用程序进行记录和解析.  [截图]（）



* ** Jettettop **： [Jnettop](http://jnettop.kubs.info/wiki/) 是一个流量可视化器，它捕获通过其运行的主机的流量，并显示按其使用的带宽排序的流. [Screenshot](http://jnettop.kubs.info/wiki/?binary=internal%3A%2F%2F76195466cc3bca92f8de7b404e240844.gif)










 * ** Vnstat **：与大多数其他工具略有不同.  它实际上运行后台服务/守护进程，并始终记录数据传输的大小.  接下来，它可用于生成网络使用历史的报告.  [截图]（）



交通捕获<a name="capture"></a>
---------------

* [Libpcap/Tcpdump](http://www.tcpdump.org/) ：tcpdump的官方网站，一个功能强大的命令行数据包分析器;  和libpcap，一个用于网络流量捕获的可移植C / C ++库.

* [Ngrep](http://ngrep.sourceforge.net/) ：努力提供大多数GNU grep的常用功能，将它们应用到网络层.  ngrep是一个支持pcap的工具，它允许您指定扩展的常规或十六进制表达式以匹配数据包的数据有效负载.  它目前通过以太网，PPP，SLIP，FDDI，令牌环和空接口识别TCP，UDP和ICMP，并以与更常见的数据包嗅探工具（如tcpdump和snoop）相同的方式理解bpf过滤器逻辑.

* [clj-net-pcap](https://github.com/ruedigergad/clj-net-pcap) ：`clj-net-pcap`是Clojure的数据包捕获库.  clj-net-pcap使用jNetPcap并在jNetPcap周围增加了便利功能，以提高可用性.  一个 [paper on clj-net-pcap](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?tp=&arnumber=6903107) 发表在COMPSACW 2014的范围内.

* [jNetPcap](http://jnetpcap.com) ：jNetPcap是适用于Java的数据包捕获库，可用于Linux和Windows.  jNetPcap分别利用libpcap和WinPcap，并使用Java Native Interface（JNI）来使用libpcap / WinPcap提供的功能.

* [Moloch](https://github.com/aol/moloch)：Moloch是一个开源的大规模完整PCAP捕获，索引和数据库系统.

* [n2disk](http://www.ntop.org/products/n2disk/)  （商用）：具有索引功能的多千兆网络流量记录器.  n2disk是一个网络流量记录器应用程序.  使用n2disk，您可以从实时网络接口以千兆位速率（在适当硬件上超过10千兆位/秒）捕获全尺寸网络数据包，并将其写入文件而不会丢失任何数据包.

* [OpenFPC](http://www.openfpc.org/) ：OpenFPC是一组脚本，它们结合起来提供轻量级的全包网络流量记录和缓冲工具.  其设计目标是允许非专家用户在COTS硬件上部署分布式网络流量记录器，同时集成到现有的警报和日志工具中.

* [PF_RING](http://www.ntop.org/products/pf_ring/) ：PF_RING是一种新型网络套接字，可显着提高数据包捕获速度.  适用于Linux内核2.6.32及更高版本.  无需修补内核.  PF_RING感知驱动程序，用于增加数据包捕获加速.

* [TTT](http://www.csl.sony.co.jp/person/kjc/kjc/software.html#ttt) :( Tele Traffic Tapper）是tcpdump的另一个后代，但它能够进行实时，图形和远程流量监控.  ttt不会取代tcpdump，相反，它可以帮助你找到用tcpdump查看的内容.  ttt监视网络并在时间窗口内自动选择流量的主要贡献者.  默认情况下，图表每秒更新一次.

* [Yaf](https://tools.netsa.cert.org/yaf/yaf.html) ：它是一个可靠的软件，非常可靠，能够从pcap生成流记录.  这非常适合索引巨大的pcap甚至数据包捕获.  最近的版本甚至可以提取有效载荷并输入流记录.


交通分析/检查<a name="analysis"></a>
--------------------------------------------------

* [AIEngine](https://bitbucket.org/camp0/aiengine) ：是下一代交互式/可编程数据包检测引擎，具有学习功能，无需人工干预，NIDS功能，DNS域分类，网络收集器等等.  AIEngine还帮助网络/安全专业人员识别流量并开发签名，以便在NIDS，防火墙，流量分类器等上使用它们.

* [Bro](http://bro-ids.org/) ：是一个基于Unix的开源网络入侵检测系统（NIDS），可被动监控网络流量并查找可疑活动.  Bro通过首先解析网络流量以提取其应用程序级语义，然后执行面向事件的分析器来检测入侵，这些分析器将活动与被认为麻烦的模式进行比较.  其分析包括检测特定攻击（包括由签名定义的攻击，以及根据事件定义的攻击）和异常活动（例如，连接到某些服务的某些主机或连接尝试失败的模式）.

* [CapTipper](https://github.com/omriher/CapTipper)：恶意HTTP流量资源管理器

* [Chopshop](https://github.com/MITRECND/chopshop)：是MITRE开发的框架，用于帮助分析人员创建和执行基于pynids的解码器和APT交易系统的探测器.

* [CoralReef](http://www.caida.org/tools/measurement/coralreef/) ：是由CAIDA开发的软件套件，用于分析被动Internet流量监视器收集的数据.  它提供了一个编程库libcoral，类似于libpcap，具有ATM和其他网络类型的扩展，可以从C和Perl获得.

* [DPDK](http://dpdk.org/) ：是一组用于快速数据包处理的库和驱​​动程序.  它被设计为在任何处理器上运行.  第一个支持的CPU是Intel x86，现在扩展到IBM Power 8，EZchip TILE-Gx和ARM.  它主要在Linux用户区运行.  FreeBSD端口可用于DPDK功能的子集.

* [DPKT](http://code.google.com/p/dpkt/)：Python数据包创建/解析库.

* [ECap](https://bitbucket.org/nathanj/ecap/wiki) :(外部捕获）是一个带有Web前端的分布式网络嗅探器.  Ecap是多年前在2005年写的，但tcpdump-workers邮件列表上的一篇文章要求提供类似的应用程序......所以这就是它.  如果有任何兴趣，更新它并再次进行处理会很有趣.

* [EtherApe](http://etherape.sourceforge.net/): is a graphical network monitor for Unix modeled after etherman. Featuring link layer, ip and TCP modes, it displays network activity graphically. Hosts and links change in size with traffic. Color coded protocols display. It supports Ethernet, FDDI, Token Ring, ISDN, PPP and SLIP devices. It can filter traffic to be shown, and can read traffic from a file as well as live from the network.

* [HttpSniffer](https://github.com/caesar0301/http-sniffer) ：一种多线程工具，用于从PCAP文件中嗅探TCP流统计信息和嵌入式HTTP标头.  每个携带HTTP的TCP流都以JSON格式导出到文本文件.


* [ITA](http://ita.ee.lbl.gov/) ：Internet流量存档是一个经过审核的存储库，支持广泛访问Internet网络流量的痕迹，由ACM SIGCOMM赞助.  这些迹线可用于研究网络动态，使用特性和增长模式，以及为跟踪驱动模拟提供基础.  该存档还可用于将原始跟踪数据减少为更易于管理的表单，生成合成跟踪以及分析跟踪的程序.

* [Libcrafter](http://code.google.com/p/libcrafter/) ：是一个C ++高级库，旨在简化网络数据包的创建和解码.  它能够制作或解码大多数常见网络协议的数据包，通过线路发送，捕获它们并匹配请求和回复.

* [Libnet](http://libnet.sourceforge.net/) ：是一组例程，用于帮助构建和处理网络数据包.  它为低级网络数据包整形，处理和注入提供了一个可移植的框架.  Libnet在IP层和链路层提供便携式数据包创建接口，以及一系列补充和补充功能.  使用libnet，可以轻松快速地完成快速简单的数据包组装应用程序.

* [Libnids](http://libnids.sourceforge.net/) ：由Rafal Wojtczuk设计，是网络入侵检测系统的电子组件的实现.  它模拟Linux 2.0.x的IP堆栈.  Libnids提供IP碎片整理，TCP流组装和TCP端口扫描检测.  libnids最有价值的特征是可靠性.  进行了大量测试，证明libnids尽可能地预测受保护Linux主机的行为.

* [Multitail](http://www.vanheusden.com/multitail) ：现在有一个colorscheme包含用于监视tcpdump输出.  它还可以过滤，将时间戳转换为时间串等等.

* [Netsniff-ng](https://github.com/caesar0301/awesome-pcaptools/blob/master/www.github.com/borkmann/netsniff-ng): Netsniff-ng is a toolkit of free Linux networking utilities, a Swiss army knife for your daily Linux network plumbing if you will.

* [NetDude](http://netdude.sourceforge.net/) :( NETwork DUmp数据显示器和编辑器）.  在他们的网页上，“它是一个基于GUI的工具，允许您对tcpdump跟踪文件中的数据包进行详细更改.”

* [Network Expect](http://www.netexpect.org/) ：是一个框架，允许轻松构建可与网络流量交互的工具.  在脚本之后，可以将流量注入到网络中，并且可以基于所接收的网络流量来做出决策并采取行动.  解释语言提供分支和高级控制结构，以指导与网络的交互.  Network Expect使用libpcap进行数据包捕获，使用libwireshark（来自Wireshark项目）进行数据包解析任务.  （GPL，BSD / Linux / OSX）.

* [Ntop](http://www.ntop.org/) ：Ntop是一个网络流量探测器，显示网络使用情况，类似于流行的顶级Unix命令.  ntop基于libpcap，它以可移植的方式编写，以便在每个Unix平台和Win32上运行.

* [Ntopng](http://www.ntop.org/products/ntop/) ：Ntopng是原始ntop的下一代版本，它是一个显示网络使用情况的网络流量探测器，类似于流行的顶级Unix命令.  ntop基于libpcap，它以可移植的方式编写，以便在每个Unix平台，MacOSX和Win32上运行.

* [Pcap2har](https://github.com/andrewf/pcap2har)：使用库dpkt将.pcap网络捕获文件转换为HTTP存档文件的程序.

* [pkt2flow](https://github.com/caesar0301/pkt2flow) ：一个简单的实用程序，用于将数据包分类为流.  这很简单，只有一项任务旨在完成.  对于深度包检测或流分类，分析一个特定流的特征是如此常见.  我尝试使用像tcpflows，tcpslice，tcpsplit这样的现成工具，但所有这些工具都试图减少跟踪量（根据要求）或将数据包类似于流有效负载（超过要求）.  我还没有找到一个简单的工具来将数据包分类为流而无需进一步处理.

* [potiron](https://github.com/CIRCL/potiron)：规范化，索引，丰富和可视化网络捕获.

* [pyshark](http://kiminewt.github.io/pyshark/) ：tshark的Python包装器，允许使用wireshark解析器进行python数据包解析.  有很多python数据包解析模块，这一个是不同的，因为它实际上并不解析任何数据包，它只是使用tshark（wireshark命令行实用程序）能力导出XML来使用它的解析.


* [Scapy](http://www.secdev.org/projects/scapy/) ：Scapy是一个功能强大的交互式数据包操作程序.  它能够伪造或解码大量协议的数据包，通过线路发送，捕获它们，匹配请求和回复等等.  它可以轻松处理大多数经典任务，如扫描，跟踪路由，探测，单元测试，攻击或网络发现（它可以取代hping，85％的nmap，arpspoof，arp-sk，arping，tcpdump，tethereal，p0f等）.  它在许多其他工具无法处理的许多其他特定任务中也表现良好，例如发送无效帧，注入自己的802.11帧，组合技术（VLAN跳跃+ ARP缓存中毒，WEP加密通道上的VOIP解码，等等）. ..）等

* [Sniff](http://www.thedumbterminal.co.uk/software/sniff.html)：使tcpdump程序的输出更易于读取和解析.

* [Snort](http://www.snort.org/) ：Snort是由Sourcefire开发的开源网络入侵防御和检测系统（IDS / IPS），现在由思科拥有.  结合签名，协议和基于异常的检查的优势，Snort是全球部署最广泛的IDS / IPS技术.  凭借数百万的下载量和大约500,000名注册用户，Snort已成为IPS的事实标准.

* [Socket Sentry](http://code.google.com/p/socket-sentry)：Socket Sentry是KDE Plasma的实时网络流量监控器，与iftop和netstat等工具的精神相同.


* [Tcpdpriv](http://ita.ee.lbl.gov/html/contrib/tcpdpriv.html) ：Tcpdpriv是用于从网络接口上收集的数据包（或从使用-w参数创建的跟踪文件到tcpdump）中删除机密信息（用户数据和地址）的程序.  Tcpdpriv删除TCP和UDP的有效负载，以及其他协议的整个IP有效负载.  它实现了几种地址加扰方法;  顺序编号方法及其变体，以及保留地址前缀的哈希方法.

* [Tcpflow](https://github.com/simsong/tcpflow) ：一种程序，捕获作为TCP连接（流）的一部分传输的数据，并以便于协议分析或调试的方式存储数据.  像&#39;tcpdump&#39;这样的程序显示了在线上看到的数据包的摘要，但通常不会存储实际传输的数据.  相反，tcpflow重建实际数据流并将每个流存储在单独的文件中以供以后分析. [Original link](http://www.circlemud.org/jelson/software/tcpflow/).


* [Tcpreplay](http://tcpreplay.synfin.net/): Replays a pcap file on an interface using libnet.

* [Tcpslice](https://github.com/caesar0301/awesome-pcaptools/blob/master/https://github.com/caesar0301/awesome-pcaptools/blob/master/ftp://ftp.ee.lbl.gov/tcpslice.tar.gz) ：Tcpslice是一个工具，用于提取使用tcpdump的-w标志生成的数据包跟踪文件的部分.  它可以组合多个跟踪文件，和/或基于时间提取一个或多个跟踪的部分. [From the tcpdump CVS server](https://github.com/caesar0301/awesome-pcaptools/blob/master/https://github.com/caesar0301/awesome-pcaptools/blob/master/ftp://ftp.ee.lbl.gov/tcpslice.tar.gz).

* [Tcpsplit](http://www.icir.org/mallman/software/tcpsplit/) ：将单个libpcap数据包跟踪分解为若干子跟踪的工具，打破沿TCP连接边界的跟踪，以便TCP连接不会最终分裂为两个子跟踪.  这对于使大型跟踪文件易于进行深入分析以及对跟踪进行子集化以仅在跟踪的一部分上进行分析非常有用.

* [Tcpstat](http://www.frenchfries.net/paul/tcpstat/) ：Tcpstat报告某些网络接口统计信息，就像vmstat用于系统统计信息一样.  tcpstat通过监视特定接口或从文件中读取以前保存的tcpdump数据来获取其信息.

* [Tcptrace](http://tcptrace.org/index.html) ：俄亥俄大学Shawn Ostermann编写的一个工具，用于分析TCP转储文件.  它可以将几个流行的数据包捕获程序生成的文件作为输入，包括tcpdump，snoop，etherpeek，HP Net Metrix和WinDump.  tcptrace可以生成几种不同类型的输出，其中包含有关每个连接的信息，例如已用时间，发送和接收的字节和段，重新传输，往返时间，窗口广告，吞吐量等.  它还可以生成许多图表以供进一步分析.

* [TraceWrangler](https://www.tracewrangler.com/) ：TraceWrangler是一个网络捕获文件工具包，运行在Windows（或在Linux上，使用WINE），支持PCAP以及新的PCAPng文件格式，现在是Wireshark使用的标准文件格式.  TraceWrangler最突出的用例是简单清理和匿名化PCAP和PCAPng文件（有时称为“跟踪文件”，“捕获文件”或“数据包捕获”），删除或替换敏感数据，同时易于使用.

* [Tstat](http://tstat.tlc.polito.it/)：被动嗅探器，能够通过大量流量功能提供对网络和传输级别的流量模式的多种了解.

* [WAND](http://research.wand.net.nz/) ：基于libtrace处理网络流量的精彩工具集，来自怀卡托大学.  我喜欢这个项目！

* [WinPcap](http://www.tcpdump.org/wpcap.html)：Guy Harris关于WinPcap和WinDump状态的消息摘录.

* [Wireshark suit](http://wiki.wireshark.org/Tools) ：众所周知的工具适合支持数据包分析器和协议解码器.  它还包括一些实用工具和脚本，以支持大多数常见用法.

* [Xplot](http://www.xplot.org/)：程序xplot是在20世纪80年代后期编写的，用于支持TCP数据包跟踪的分析.

* [yaraPcap](https://github.com/kevthehermit/YaraPcap)：使用YARA处理HTTP Pcaps

* [yaraprocessor](https://github.com/MITRECND/yaraprocessor) ：使用yaraprocessor YARA可以针对单个数据包有效负载以及部分或全部有效负载的串联运行.  它最初是为在Chopshop中使用而编写的，但也可以在没有它的情况下使用.


DNS实用程序<a name="dnstools"></a>
--------------------------------------------

* [dnsgram](https://doc.powerdns.com/md/manpages/dnsgram.1/) ：dnsgram是间歇性解析器故障的调试工具.  它需要一个或多个输入PCAP文件并生成5秒段的统计数据，以便研究间歇性的解析器问题.

* [dnsreplay](https://doc.powerdns.com/md/manpages/dnsreplay.1/) ：Dnsreplay记录问题和答案，并将它们重播到指定的名称服务器，然后报告匹配的答案百分比，更糟或更好.  然后将答案和其他一些指标与实际的指标与转储文件中的指标进行比较.

* [dnsscan](https://doc.powerdns.com/md/manpages/dnsscan.1/)：dnsscan采用PCAP格式的一个或多个INFILE，并生成每个查询类型的查询数列表.

* [dnsscope](https://doc.powerdns.com/md/manpages/dnsscope.1/)：dnsscope接受输入PCAP并生成一些简单的统计信息输出到控制台.

* [dnswasher](https://doc.powerdns.com/md/manpages/dnswasher.1/) ：dnswasher采用PCAP格式的输入文件并写出PCAP文件，同时模糊最终用户的IP地址.  在尝试保护用户隐私的同时，这对于与第三方共享数据非常有用.


文件提取<a name="fileextraction"></a>
--------------------------------------------


* [Dsniff](http://www.monkey.org/~dugsong/dsniff/) ：Dsniff是一系列用于网络审计和渗透测试的工具.  dsniff，filesnarf，mailsnarf，msgsnarf，urlsnarf和webspy被动地监视网络以获取有趣的数据（密码，电子邮件，文件等）.  arpspoof，dnsspoof和macof有助于拦截攻击者通常无法获得的网络流量（例如，由于第2层交换）.  sshmitm和webmitm通过利用ad-hoc PKI中的弱绑定，实现针对重定向的SSH和HTTPS会话的活跃的中间人攻击.

* [Foremost](http://foremost.sourceforge.net/) ：是一个控制台程序，用于根据页眉，页脚和内部数据结构恢复文件.  这个过程通常被称为数据雕刻.  Foremost可以处理图像文件，例如由dd，Safeback，Encase等生成的图像文件，或直接在驱动器上.  页眉和页脚可以由配置文件指定，也可以使用命令行开关指定内置文件类型.  这些内置类型查看给定文件格式的数据结构，从而实现更可靠，更快速的恢复.

* [Justniffer](http://justniffer.sourceforge.net/)：Justniffer是一种网络协议分析器，可以捕获网络流量并以自定义方式生成日志，可以模拟Apache Web服务器日志文件，跟踪响应时间并从HTTP流量中提取所有“截获”文件.

* [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) ：NetworkMiner是Windows的网络取证分析工具（NFAT）（但也适用于Linux / Mac OS X / FreeBSD）.  NetworkMiner可用作被动网络嗅探器/数据包捕获工具，以便检测操作系统，会话，主机名，开放端口等，而无需在网络上放置任何流量.  NetworkMiner还可以解析PCAP文件以进行离线分析，并从PCAP文件重新生成/重新组合传输的文件和证书.

* [pcapfex](https://github.com/vikwin/pcapfex)   -  Packet CAPture Forensic Evidence eXtractor（pcapfex）是一种从数据包捕获文件中查找和提取文件的工具.  它的强大功能在于它的易用性.  只需提供一个pcap文件，它就会尝试提取所有文件.  它是一个可扩展的平台，因此可以轻松添加要识别和提取的其他文件类型.

* [scalpel](https://github.com/sleuthkit/scalpel)：Scalpel是一个开源数据雕刻工具.

* [Snort](http://www.snort.org/) ：是由Sourcefire开发的开源网络入侵防御和检测系统（IDS / IPS），现在由思科拥有.  结合签名，协议和基于异常的检查的优势，Snort是全球部署最广泛的IDS / IPS技术.

* [Tcpick](http://tcpick.sourceforge.net/) ：是一个基于libmcap的文本模式嗅探器，可以跟踪，重组和重新排序tcp流.  Tcpick能够将捕获的流保存在不同的文件中或在终端中显示它们，因此嗅探通过ftp或http传输的文件很有用.  当连接在不同的显示模式下关闭时，它可以显示终端上的所有流，如hexdump，hexdump + ascii，仅可打印字符，原始模式等.

* [Tcpxtract](http://tcpxtract.sourceforge.net/) ：是一种基于文件签名从网络流量中提取文件的工具.  基于文件类型页眉和页脚（有时称为“雕刻”）提取文件是一种古老的数据恢复技术.




相关项目<a name="others"></a>
--------------------------------------

* [BPF for Ultrix](http://www.tcpdump.org/other/bpfext42.tar.Z)：Ultrix 4.2的BPF分发，包含源代码和二进制模块.

* [BPF+](http://www.cs.berkeley.edu/~abegel/sigcomm99/bpf+.ps)：在广义包过滤器体系结构中利用全局数据流优化作者：Andrew Begel，Steven McCanne和Susan Graham.

* [FFT-FGN-C](http://ita.ee.lbl.gov/html/contrib/fft_fgn_c.html) ：是一种用于合成一种称为分数高斯噪声的自相似过程的程序.  该计划很快但近似.  分数高斯噪声只是一种类似的自相似过程.  使用此程序来合成网络流量时，您必须记住，您搜索的流量可能更好地使用其他流程之一进行建模.

* [Haka](http://www.haka-security.org/) ：一种开源安全导向语言，允许描述协议并对（实时）捕获的流量应用安全策略.  哈卡语的范围是双重的.  首先，它允许编写安全规则，以便过滤/更改/丢弃不需要的数据包，并记录和报告恶意活动.  其次，Haka具有一种语法，可以指定网络协议及其底层状态机.

* [RIPE-NCC Hadoop for PCAP](https://github.com/RIPE-NCC/hadoop-pcap) ：用于读取数据包捕获（PCAP）文件的Hadoop库.  捆绑用于读取PCAP的代码.  可以在MapReduce作业中用于本机读取PCAP文件.  还有一个Hive Serializer / Deserializer（SerDe），可以使用SQL命令查询PCAP.

* [Traffic Data Repository at the WIDE Project](http://www.sonycsl.co.jp/person/kjc/papers/freenix2000/) ：对网络研究人员和运营商来说，了解网络流量的趋势并发现网络流量异常变得越来越重要.  本文描述了WIDE项目中正在进行的一项工作，即收集一组免费工具来构建包含骨干流量详细信息的流量数据存储库.  流量跟踪由tcpdump收集，并在删除隐私信息后，向公众开放跟踪.  我们回顾了有关用户隐私的问题，然后介绍了用于构建WIDE流量存储库的工具.  我们将在IPv6部署的早期阶段报告当前状态和结果.

* [Usenix93 Paper on BPF](https://github.com/caesar0301/awesome-pcaptools/blob/master/ftp://ftp.ee.lbl.gov/papers/bpf-usenix93.ps.Z) ：libpcap接口支持基于BSD数据包过滤器中的体系结构的过滤机制.  BPF在1993年Winter Usenix论文“BSD数据包过滤器：用户级数据包捕获的新架构”中有所描述.
