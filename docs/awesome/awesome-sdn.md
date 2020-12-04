<div class="github-widget" data-repo="sdnds-tw/awesome-sdn"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome SDN [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/sdnds-tw/awesome-sdn.svg?branch=master)](https://travis-ci.org/sdnds-tw/awesome-sdn)

关于软件定义网络（SDN）的出色列表


## Introduction
  软件定义网络（SDN）是一种计算机联网方法，允许网络管理员通过抽象更高级别的功能来管理网络服务.
  维基： [Software-Defined Networking](https://en.wikipedia.org/wiki/Software-defined_networking)

## Network Operating System

- [Beluganos](https://github.com/beluganos/beluganos) -Beluganos是专为白盒交换机（OF-DPA）设计的新网络操作系统，可以应用大型网络.
- [Cumulus Linux](https://cumulusnetworks.com) - Cumulus Linux is a powerful open network operating system that allows you to automate, customize and scale using web-scale principles like the world's largest data centers.
- [FlexSwitch](https://snaproute.com/) -第一个提供完整的layer2 / layer3功能的开源网络协议套件，用于加速白盒网络设备的开发和部署
- [Mion](https://github.com/opencomputeproject/mion) -基于ONLP API和Yocto项目的交换机OS.
- [OcNOS](https://www.ipinfusion.com/) -具有高级功能的广泛交换和路由协议支持，例如MPLS和SDN
- [Open Network Linux, ONL](https://opennetlinux.org) -用于“裸机”交换机的Linux发行版，即由商品组件构建的网络转发设备.
- [OpenSwitch](http://www.openswitch.net) -Dell EMC提供的linux网络操作系统.
- [OpenWrt](https://openwrt.org/) -是针对嵌入式设备的Linux操作系统.
- [PicOS](http://www.pica8.com/products/picos) -用于白盒的SDN操作系统切换了第2/3层功能集，并支持OpenFlow，OVSDB和其他协议.
- [SONiC](https://azure.github.io/SONiC/) -用于云SONiC中的开放网络的软件
- [Stratum](https://stratumproject.org/) -用于软件定义网络的开源，独立于硅的交换机操作系统

## Install Environment

- [ONIE](http://onie.org/) -ONIE支持裸机网络交换机生态系统，最终用户可以在不同的网络操作系统之间进行选择.

## Software Switch

- [BESS](https://github.com/NetSys/bess) -Berkeley可扩展软件交换机，BESS是用于软件交换机的模块化框架.
- [bmv2](https://github.com/p4lang/behavioral-model)-P4软件开关，通常用作验证开发人员以P4语言描述的功能的工具.
- [CPqD](https://github.com/CPqD/ofsoftswitch13)-与OpenFlow 1.3兼容的用户空间软件开关实现
- [FD.IO](https://fd.io/) -不懈地致力于数据IO速度和效率，以实现更灵活和可扩展的网络和存储
- [Indigo](https://github.com/floodlight/indigo) -Indigo是一个开源项目，旨在在物理和管理程序交换机上启用对OpenFlow的支持.
- [Lagopus](https://lagopus.github.io) -高性能软件OpenFlow 1.3交换机.
- [LINC-Switch](https://github.com/FlowForwarding/LINC-Switch) -用Erlang编写的纯OpenFlow软件开关
- [Open vSwitch](http://openvswitch.org/) -Open vSwitch是一种生产质量的多层虚拟交换机.
- [PISCES](https://www.cs.princeton.edu/~jrex/papers/pisces16.pdf) - A Programmable, Protocol-Independent Software Switch.
- [snabbswitch](https://github.com/SnabbCo/snabbswitch) -开源虚拟化以太网网络堆栈.
- [ZeroTier](https://github.com/zerotier/ZeroTierOne) -ZeroTier是用于地球的基于软件的管理型以太网交换机.

## Network Virtualization

- [FlowVisor](https://github.com/opennetworkinglab/flowvisor)  -一个OpenFlow控制器，充当交换机和多个控制器之间的管理程序/代理. 可以并行分割多个交换机，有效地分割网络.
- [OpenVirtex](https://github.com/opennetworkinglab/OpenVirteX) -网络管理程序，可以在单个物理基础架构上创建多个虚拟和可编程网络.

## Protocol

- [OpenFlow](https://www.opennetworking.org/sdn-resources/openflow) -一种通信协议，可通过网络访问网络交换机或路由器的转发平面.
- [OF-Config](https://www.opennetworking.org/technical-communities/areas/specification/of-config/) -OpenFlow管理和配置协议
- [OVSDB](https://tools.ietf.org/html/rfc7047) -用于管理OpenvSwitch数据库的通信协议.
- [NETCONF](https://en.wikipedia.org/wiki/NETCONF)
- [OpFlex](http://www.cisco.com/c/en/us/solutions/collateral/data-center-virtualization/application-centric-infrastructure/white-paper-c11-731302.html)
- [Path Computation Element Protocol, PCEP](https://www.juniper.net/documentation/en_US/junos/topics/concept/mpls-pcep-overview.html)
- [Extensible Messaging and Presence Protocol, XMPP](https://en.wikipedia.org/wiki/XMPP)
- [P4 Runtime](https://p4.org/api/p4-runtime-putting-the-control-plane-in-charge-of-the-forwarding-plane.html)
- [gNMI](https://github.com/openconfig/gnmi/) -gRPC网络管理界面
- [gNOI](https://github.com/openconfig/gnoi) -gRPC网络操作界面

## Controller

- [Beehive Network Controller](https://github.com/kandoo/beehive-netctrl)  -在Beehive之上构建的分布式SDN控制器. 它支持OpenFlow，但可以轻松扩展为其他南向协议.
- [Floodlight](https://github.com/floodlight/floodlight) -基于Java的OpenFlow控制器.
- [IRIS](http://openiris.etri.re.kr/) -由ETRI SDN研究部创建的一种递归SDN Openflow控制器.
- [lighty.io core](https://github.com/PantheonTechnologies/lighty-core) -lighty.io核心组件-用于构建基于Java的SDN控制器的开源开发框架.
- [Netrack](https://github.com/netrack/openflow) -Go中的OpenFlow控制器框架.
- [NodeFlow](https://github.com/gaberger/NodeFLow) -OpenFlow控制器节点样式.
- [NOX](https://github.com/noxrepo/nox) -一个基于C ++的软件定义网络（* SDN *）控制应用程序的开源开发平台.
- [OESS](https://github.com/globalnoc/oess) -用于配置和控制启用OpenFlow的交换机的Open Exchange软件套件.
- [ONOS](http://onosproject.org) -打开网络操作系统.
- [Open MUL](http://www.openmul.org/openmul-controller.html) -轻量级的SDN / Openflow控制器，几乎完全从头开始用C编写.
- [Open Security Controller](https://www.opensecuritycontroller.org/) -软件定义的安全协调解决方案，可自动部署虚拟化网络安全功能，例如下一代防火墙，入侵防御系统和应用程序数据控制器
- [OpenContrail](https://tungsten.io/opencontrail-is-now-tungsten-fabric/) -一个利用SDN和NFV并提供网络虚拟化所有必要组件的SDN项目.
- [OpenDaylight](https://www.opendaylight.org) -OpenDaylight平台
- [OVN](http://www.openvswitch.org//support/slides/OVN-Vancouver.pdf) -OVN：用于开放vSwitch的开放虚拟网络
- [POX](https://github.com/noxrepo/pox) -一个基于Python的软件定义网络（* SDN *）控制应用程序的开源开发平台.
- [Ravel](https://github.com/ravel-net/ravel) -使用标准SQL数据库表示网络的软件定义网络（SDN）控制器.
- [Ryu](https://ryu-sdn.org/) -基于组件的软件定义网络框架.
- [Trema](https://trema.github.io/trema/) -用于在Ruby和C中开发OpenFlow控制器的完整堆栈，易于使用的框架.
- [Vyatta](https://github.com/BRCDcomm/BVC/) -第一个直接从OpenDaylight构建的商业控制器.

## Simulator/Emulator

- [Containernet](https://github.com/containernet/containernet) -Mininet fork，允许将Docker容器用作仿真网络中的主机
- [EstiNet](http://www.estinet.com/products.php?lv1=13&sn=13) -享誉全球的网络规划软件工具
- [MaxiNet](http://maxinet.github.io)  -MaxiNet扩展了著名的Mininet仿真环境，以跨多个物理机器进行仿真. 这允许模拟非常大的软件定义的网络.
- [Mininet](http://mininet.org/) -便携式计算机（或其他PC）上的即时虚拟网络
- [ns-3](https://www.nsnam.org/) -支持OpenFlow环境的离散事件网络模拟器.
- [OpenNet](http://github.com/dlinknctu/opennet) -用于软件定义的无线局域网的模拟器
- [Tinynet](https://github.com/John-Lin/tinynet) -用于快速制作SDN的轻量级即时虚拟网络

## Language

- [Frenetic](https://github.com/frenetic-lang/frenetic) -Frenetic编程语言和运行时系统
- [NEMO](https://wiki.onosproject.org/display/ONOS/NEMO+Language) -基于网络模型的抽象和操作模式的结论的领域特定语言（DSL）.
- [P4](http://p4.org/) -一种声明性语言，用于表示如何通过网络转发元素（如交换机，NIC，路由器或网络功能设备）的管道处理数据包.
- [POF](https://dl.acm.org/citation.cfm?id=2491190) -协议遗忘转发
- [Pyretic](http://www.frenetic-lang.org/pyretic/) -Pyretic是SDN编程语言Frenetic家族的成员之一.

## Library

- [loxigen](https://github.com/floodlight/loxigen) -LoxiGen是一种工具，可为多种语言生成OpenFlow协议库.
- [nettle](https://github.com/AndreasVoellmy/openflow) -Haskell库，用于处理OpenFlow协议.
- [OCaml OpenFlow](https://github.com/frenetic-lang/ocaml-openflow) -OpenFlow的序列化和协议库.
- [oflib-node](https://github.com/TrafficLab/oflib-node)  -Oflib-node是Node的OpenFlow协议库. 它在OpenFlow有线协议消息和Javascript对象之间转换.
- [openfaucet](https://github.com/rlenglet/openfaucet) -openfaucet是基于Twisted的OpenFlow 1.0.0协议的纯Python实现.
- [OpenFlowJ](https://bitbucket.org/openflowj/openflowj) -低级OpenFlow数据包编组/解组和IO操作的Java实现.
- [Scapy](http://www.secdev.org/projects/scapy/) -Scapy是功能强大的交互式数据包处理程序.

## Test

- [Cbenech](https://github.com/mininet/oflops/tree/master/cbench) -控制器基准测试工具
- [nice-of](https://code.google.com/archive/p/nice-of/) -用于测试NOX控制器平台的OpenFlow控制器应用程序的工具.
- [oftest](https://github.com/floodlight/oftest) -OpenFlow测试框架
- [OpenSDNCore](http://www.opensdncore.org/) -NFV / SDN环境的虚拟化测试平台.
- [ptf](https://github.com/p4lang/ptf) -基于unittest的基于python的dataplane测试框架.
- [STS](https://ucb-sts.github.com/sts/) -SDN故障排除系统，模拟网络设备，以编程方式生成测试用例.

## NFV

- [OPNFV](https://www.opnfv.org) -通过集成的开放平台加速NFV的发展.

## Overlay Network

- [GENEVE](https://www.redhat.com/en/blog/what-geneve) -什么是GENEVE？
- [NVGRE](https://tools.ietf.org/html/draft-sridharan-virtualization-nvgre-00) -使用通用路由封装的NVGRE网络虚拟化
- [VXLAN](https://en.wikipedia.org/wiki/Virtual_Extensible_LAN) - Virtual Extensible LAN

## Router

- [bgp4r](https://github.com/jesnault/bgp4r)  -BGP4R是一个ruby库，可用于创建和处理BGP消息. 在BGP4R中，所有众所周知的BGP构造都是在类中定义的.
- [BGPFeeder](https://github.com/BytemarkHosting/bgpfeeder)
- [Bird](http://bird.network.cz/) -BIRD项目旨在开发一个功能齐全的动态IP路由守护程序，该守护程序主要针对（但不限于）Linux，FreeBSD和其他类似UNIX的系统，并根据GNU通用公共许可证进行分发.
- [FreeRouter](http://freerouter.nop.hu/) -基于Java的vRouter
- [FRRouting](https://frrouting.org/) -用于Linux和Unix平台的IP路由协议套件，其中包括BGP4，BGP4 +，OSPFv2，OSPFv3，RIPv1，RIPv2，RIPng，PIM-SM / MSDP和LDP的协议守护程序，以及对IS-IS，EIGRP和NHRP.
- [gobgp](https://github.com/osrg/gobgp) -GoBGP是为现代环境从头开始设计的开源BGP实现，并以现代编程语言Go编程语言实现.
- [Quagga](http://www.quagga.net/)  -Quagga是一个路由软件套件，为Unix平台（尤其是FreeBSD，Linux，Solaris和NetBSD）提供OSPFv2，OSPFv3，RIP v1和v2，RIPng和BGP-4的实现.  Quagga是由Ishiguro Kunihiro开发的GNU Zebra的叉子.
- [yabgp](https://github.com/smartbgp/yabgp)  -YABGP是BGP协议的另一个Python实现. 它可用于与各种路由器（包括真实的Cisco / HuaWei / Juniper路由器以及某些路由器模拟器，如GNS3）建立BGP连接，并接收/解析BGP消息以供将来分析.

## Misc

- [Aether Project](https://www.opennetworking.org/aether/) -第一个开源企业级5G / LTE边缘云即服务平台（ECaaS）.
- [Central Office Re-architected as a Datacenter, CORD](http://opencord.org) -提供云经济性和敏捷性的服务交付平台的参考实现.
- [Mininet Spear Narmox](http://mininet.spear.narmox.com) -在线Web服务提供Mininet拓扑的可视化
- [Open Network Automation Platform, ONAP](https://www.onap.org/) -两个项目的一致性为虚拟网络功能的实时，策略驱动的软件自动化创建了一个统一而全面的框架，这将使软件，网络，IT和云提供商以及开发人员能够快速创建新服务.
- [Open Source MANO Community, OSM](https://osm.etsi.org/welcome/)
- [OPEN-Orchestrator Project, Open-O](https://www.open-o.org)

## High Performance Network

- [ASAP2](http://www.mellanox.com/blog/2016/12/three-ways-asap2-beats-dpdk-for-cloud-and-nfv/) -ASAP2加速器基于eSwitch NIC硬件构建，并允许将整个虚拟交换机或虚拟交换机或分布式虚拟路由器（DVR）操作的重要部分卸载到Mellanox NIC
- [DPDK](http://dpdk.org/) -DPDK是一组用于快速数据包处理的库和驱​​动程序.
- [RDMA](https://en.wikipedia.org/wiki/Remote_direct_memory_access)  -远程直接内存访问（RDMA）是从一台计算机的内存到另一台计算机的内存的直接内存访问，而无需涉及任何一个操作系统. 这允许高吞吐量，低延迟的网络
- [XDP](https://www.iovisor.org/technology/xdp) -作为IO Visor项目的一部分，XDP或eXpress数据路径在Linux内核中提供了高性能的可编程网络数据路径.
它旨在在任何处理器上运行. 第一个受支持的CPU是Intel x86，现在扩展到IBM POWER和ARM.


## Userspace Network Stack

- [drv-netif-dpdk](https://github.com/rumpkernel/drv-netif-dpdk)  -drv-netif-dpdk是用于臀部内核的DPDK网络接口. 合并的结果是一个用户空间TCP / IP堆栈通过DPDK进行数据包I / O.
- [f-stack](https://github.com/F-Stack/f-stack) -F-Stack是基于DPDK，FreeBSD TCP / IP堆栈和协程API的高性能用户空间网络开发套件.
- [mTCP](https://github.com/eunyoung14/mtcp)  -mTCP是用于多核系统的高度可扩展的用户级TCP堆栈.  mTCP源代码在修改的BSD许可证下分发. 有关更多详细信息，请参阅许可.  io_engine驱动程序和移植的应用程序的许可条款可能与mTCP的许可条款不同.
- [net-next-nuse](https://github.com/libos-nuse/net-next-nuse)  -用户空间中的网络堆栈（NUSE）NUSE允许我们将Linux网络堆栈用作库，任何应用程序都可以通过链接该库来使用目录. 每个应用程序都有自己的网络堆栈，因此，它提供了除主机操作系统之外的即时虚拟化环境.
- [nff-go](https://github.com/intel-go/nff-go)  -NFF-Go成为Linux Foundation下DPDK项目保护的一部分！ 可以在以下位置找到镜像仓库：http://dpdk.org/browse/apps/nff-go/. 我们也将通过DPDK邮件列表和标准DPDK贡献过程接受补丁.

## Analytics

- [Apache Spot](http://spot.incubator.apache.org/) -从头开始构建的社区驱动的网络安全项目，旨在在开放，可扩展的平台上为所有IT遥测数据带来高级分析
- [PNDA](http://pnda.io/) -用于网络和服务的可扩展的开源大数据分析平台.
- [SNAS](http://www.snas.io/) -流网络分析系统（SNAS项目）是一个框架，可实时收集，跟踪和访问数千万个路由对象（路由器，对等方，前缀）.

## Resources
## Books

- [DevOps for Networking](https://www.packtpub.com/networking-and-servers/devops-networking)
- [Network Algorithmics：An Interdisciplinary Approach to Designing Fast Networked Devices](https://doc.lagout.org/network/Network%20Algorithmics%20An%20Interdisciplinary%20Approach%20to%20Designing%20Fast%20Networked%20Devices.pdf)
- [Network Programmability and Automation Skills for the Next-Generation Network Engineer](http://shop.oreilly.com/product/0636920042082.do)
- [SDN: Software Defined Networks: An Authoritative Review of Network Programmability Technologies](https://www.oreilly.com/library/view/sdn-software-defined/9781449342425/)
- [SDN网络指南](https://feisky.gitbooks.io/sdn/)（倪鹏飞的中文开源书）
- [SDN核心技术剖析和实战指南](http://www.sdnlab.com/book/9480.html)
- [Software Defined Networking with OpenFlow](https://www.packtpub.com/networking-and-servers/software-defined-networking-openflow)
- [圖解OpenFlow](http://www.books.com.tw/products/CN11301942)
- [重构网络-SDN架构与实现](http://www.sdnlab.com/book/18762.html)
- [深度解析SDN: 利益、战略、技术、实践](http://www.sdnlab.com/book/9470.html)
- [软件定义网络:SDN与OpenFlow解析](http://www.sdnlab.com/book/9473.html)

## Paper

- [A Guided Tour of Data-Center Networking](http://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/40404.pdf)
- [A Survey on the Security of Stateful SDN Data Planes](https://ieeexplore.ieee.org/document/7890396)
- [High Performance Datacenter Networks: Architectures, Algorithms, and Opportunities](https://static.googleusercontent.com/media/research.google.com/zh-TW//pubs/archive/37069.pdf)
- [Re-architecting datacenter networks and stacks for low latency and high performance](http://dl.acm.org/citation.cfm?id=3098825)
- [SDN A Comprehensive Survey](https://arxiv.org/pdf/1406.0440.pdf)

## Awesome Posts
- [VXLAN L3应用EVPN，呈现完整overlay网络](https://www.sdnlab.com/19879.html)
