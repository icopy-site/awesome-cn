<div class="github-widget" data-repo="sdnds-tw/awesome-sdn"></div>
## Awesome SDN [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/sdnds-tw/awesome-sdn.svg?branch=master)](https://travis-ci.org/sdnds-tw/awesome-sdn)

关于软件定义网络（SDN）的精彩列表


## Introduction
  软件定义网络（SDN）是一种计算机网络方法，允许网络管理员通过抽象更高级别的功能来管理网络服务.
  维基： [Software-Defined Networking](https://en.wikipedia.org/wiki/Software-defined_networking)

## Network Operating System
- [PicOS](http://www.pica8.com/products/picos) - 用于白盒的SDN OS切换第2层/第3层功能集，支持OpenFlow，OVSDB和其他协议.
- [Open Network Linux, ONL](https://opennetlinux.org) - 用于“裸机”交换机的Linux发行版，即由商品组件构建的网络转发设备.
- [OpenSwitch](http://www.openswitch.net) - 来自Dell EMC的Linux网络操作系统.
- [Cumulus Linux](https://cumulusnetworks.com) -  Cumulus Linux是一个功能强大的开放式网络操作系统，允许您使用世界上最大的数据中心等网络规模原则进行自动化，自定义和扩展.
- [OcNOS](https://www.ipinfusion.com/) - 先进的广泛切换和路由协议支持
MPLS和SDN等功能
- [FlexSwitch](https://snaproute.com/) - 第一个开源网络协议套件，提供完整的layer2 / layer3功能，用于加速白盒网络设备的开发和部署
- [beluganos](https://github.com/beluganos/beluganos) -  Beluganos是专为白盒交换机（OF-DPA）设计的新型网络操作系统，可应用大规模网络.
- [SONiC](https://azure.github.io/SONiC/) - 云中开放网络的软件
SONiC
- [Stratum](https://stratumproject.org/) - 用于软件定义网络的开源，独立于硅的交换机操作系统
- [OpenWrt](https://openwrt.org/) - 是针对嵌入式设备的Linux操作系统.


## Install Environment
- [ONIE](http://onie.org/) -  ONIE实现了裸机网络交换机生态系统，终端用户可以在不同的网络操作系统中进行选择.

## Software Switch

- [Open vSwitch](http://openvswitch.org/) -  Open vSwitch是一款生产品质的多层虚拟交换机.
- [Indigo](https://github.com/floodlight/indigo) -  Indigo是一个开源项目，旨在支持物理和虚拟机管理程序交换机上的OpenFlow.
- [CPqD](https://github.com/CPqD/ofsoftswitch13)- 与OpenFlow 1.3兼容的用户空间软件交换机实现
- [Lagopus](https://lagopus.github.io) - 高性能软件OpenFlow 1.3交换机.
- [LINC-Switch](https://github.com/FlowForwarding/LINC-Switch) - 用Erlang编写的纯OpenFlow软件开关
- [snabbswitch](https://github.com/SnabbCo/snabbswitch) - 开源虚拟化以太网网络堆栈.
- [ZeroTier](https://github.com/zerotier/ZeroTierOne) -  ZeroTier是一款基于软件的行星地球管理以太网交换机.
- [PISCES](http://pisces.cs.princeton.edu/) - 可编程，独立于协议的软件交换机.
- [BESS](https://github.com/NetSys/bess) -  Berkeley可扩展软件交换机，BESS是软件交换机的模块化框架.
- [FD.IO](https://fd.io/) - 坚定不移地专注于数据IO速度和效率，以实现更灵活，可扩展的网络和存储
- [bmv2](https://github.com/p4lang/behavioral-model)-  P4软件开关，通常用作验证开发人员用P4语言描述的功能的工具.

## Network Virtualization

- [FlowVisor](https://github.com/opennetworkinglab/flowvisor)   -  OpenFlow控制器，充当交换机和多个控制器之间的管理程序/代理.  可以并行切片多个交换机，有效切片网络.
- [OpenVirtex](https://github.com/opennetworkinglab/OpenVirteX) - 网络管理程序，可以在单个物理基础架构上创建多个虚拟和可编程网络.

## Protocol

- [OpenFlow](https://www.opennetworking.org/sdn-resources/openflow) - 通过网络访问网络交换机或路由器的转发平面的通信协议.
- [OF-Config](https://www.opennetworking.org/technical-communities/areas/specification/of-config/) -  OpenFlow管理和配置协议
- [OVSDB](https://tools.ietf.org/html/rfc7047) - 用于管理OpenvSwitch数据库的通信协议.
- [NETCONF](https://en.wikipedia.org/wiki/NETCONF)
- [OpFlex](http://www.cisco.com/c/en/us/solutions/collateral/data-center-virtualization/application-centric-infrastructure/white-paper-c11-731302.html)
- [Path Computation Element Protocol, PCEP](https://www.juniper.net/documentation/en_US/junos/topics/concept/mpls-pcep-overview.html)
- [Extensible Messaging and Presence Protocol, XMPP](https://en.wikipedia.org/wiki/XMPP)
- [P4 Runtime](https://p4.org/api/p4-runtime-putting-the-control-plane-in-charge-of-the-forwarding-plane.html)

## Controller

- [NOX](https://github.com/noxrepo/nox) - 基于C ++的软件定义网络（* SDN *）控制应用程序的开源开发平台.
- [POX](https://github.com/noxrepo/pox) - 基于Python的软件定义网络（* SDN *）控制应用程序的开源开发平台.
- [NodeFlow](https://github.com/gaberger/NodeFLow) -  OpenFlow控制器节点样式.
- [ONOS](http://onosproject.org) - 开放网络操作系统.
- [OpenDaylight](https://www.opendaylight.org) -  OpenDaylight平台
- [Ryu](https://osrg.github.io/ryu) - 基于组件的软件定义网络框架.
- [Floodlight](https://github.com/floodlight/floodlight) - 基于java的OpenFlow控制器.
- [Vyatta](https://github.com/BRCDcomm/BVC/) - 直接从OpenDaylight构建的第一个商业控制器.
- [OpenContrail](http://www.opencontrail.org/) - 利用SDN和NFV的SDN项目，为网络虚拟化提供所有必要的组件.
- [IRIS](http://openiris.etri.re.kr/) - 由ETRI的SDN研究部门创建的Resurive SDN Openflow Controller.
- [Open MUL](http://www.openmul.org/openmul-controller.html) - 从头开始​​几乎完全用C语言编写的轻量级SDN / Openflow控制器.
- [OESS](https://github.com/globalnoc/oess) - 用于配置和控制OpenFlow Enabled交换机的Open Exchange Software Suite.
- [Beehive Network Controller](https://github.com/kandoo/beehive-netctrl)   - 基于Beehive构建的分布式SDN控制器.  它支持OpenFlow，但可以轻松扩展到其他南向协议.
- [Ravel](https://github.com/ravel-net/ravel) - 软件定义网络（SDN）控制器，使用标准SQL数据库来表示网络.
- [Trema](https://trema.github.io/trema/) - 用于在Ruby和C中开发OpenFlow控制器的全栈，易于使用的框架.
- [Open Security Controller](https://www.opensecuritycontroller.org/) - 软件定义的安全编排解决方案，可自动部署虚拟化网络安全功能，如下一代防火墙，入侵防御系统和应用数据控制器
- [Netrack](https://github.com/netrack/openflow) -  Go中的OpenFlow控制器框架.
- [OVN](http://www.openvswitch.org//support/slides/OVN-Vancouver.pdf) -  OVN：为Open vSwitch打开虚拟网络

## Simulator/Emulator

- [Mininet](http://mininet.org/) - 笔记本电脑（或其他PC）上的即时虚拟网络
- [OpenNet](http://github.com/dlinknctu/opennet) - 用于软件定义的无线局域网的模拟器
- [EstiNet](http://www.estinet.com/products.php?lv1=13&sn=13) - 世界知名的网络规划软件工具
- [ns-3](https://www.nsnam.org/) - 支持OpenFlow环境的离散事件网络模拟器.
- [Containernet](https://github.com/containernet/containernet) -  Mininet fork允许在模拟网络中使用Docker容器作为主机
- [Tinynet](https://github.com/John-Lin/tinynet) - 用于快速原型设计SDN的轻量级即时虚拟网络
- [MaxiNet](http://maxinet.github.io)   -  MaxiNet扩展了着名的Mininet仿真环境，以跨越多个物理机器的仿真.  这允许模拟非常大的软件定义网络.

## Language

- [P4](http://p4.org/) - 一种声明性语言，用于表示如何通过网络转发元件（如交换机，NIC，路由器或网络功能设备）的管道处理数据包.
- [POF](https://dl.acm.org/citation.cfm?id=2491190) - 协议不经意转发
- [Frenetic](https://github.com/frenetic-lang/frenetic) - 狂热编程语言和运行时系统
- [Pyretic](http://www.frenetic-lang.org/pyretic/) -  Pyretic是Frenetic SDN编程语言系列的一员.
- [NEMO](https://wiki.onosproject.org/display/ONOS/NEMO+Language) - 基于网络模型抽象和操作模式结论的领域特定语言（DSL）.

## Library

- [loxigen](https://github.com/floodlight/loxigen) -  LoxiGen是一种为多种语言生成OpenFlow协议库的工具.
- [openfaucet](https://github.com/rlenglet/openfaucet) -  openfaucet是OpenFlow 1.0.0的纯Python实现
协议，基于Twisted.
- [oflib-node](https://github.com/TrafficLab/oflib-node) - Oflib-node is an OpenFlow protocol library for Node. It converts between OpenFlow wire protocol messages and Javascript objects.
- [OpenFlowJ](https://bitbucket.org/openflowj/openflowj) - 低级OpenFlow数据包编组/解组和IO操作的Java实现.
- [nettle](https://github.com/AndreasVoellmy/openflow) - 用于处理OpenFlow协议的Haskell库.
- [OCaml OpenFlow](https://github.com/frenetic-lang/ocaml-openflow) -  OpenFlow的序列化和协议库.
- [Scapy](http://www.secdev.org/projects/scapy/) -  Scapy是一个功能强大的交互式数据包操作程序.

## Test

- [oftest](https://github.com/floodlight/oftest) -  OpenFlow测试框架
- [STS](https://ucb-sts.github.com/sts/) -  SDN故障排除系统，模拟网络设备，允许以编程方式生成测试用例.
- [nice-of](https://code.google.com/archive/p/nice-of/) - 用于测试NOX控制器平台的OpenFlow控制器应用程序的工具.
- [OpenSDNCore](http://www.opensdncore.org/) - 经过NFV / SDN环境测试测试.
- [Cbenech](https://github.com/mininet/oflops/tree/master/cbench) - Benchmarking tool for controllers
- [ptf](https://github.com/p4lang/ptf) - 基于单元测试的基于python的数据平面测试框架.

## NFV

- [OPNFV](https://www.opnfv.org) - 通过集成的开放平台加速NFV的发展.

## Overlay Network

- [VXLAN](https://en.wikipedia.org/wiki/Virtual_Extensible_LAN) - 虚拟可扩展LAN
- [NVGRE](https://tools.ietf.org/html/draft-sridharan-virtualization-nvgre-00) -  NVGRE-Network-Virtualization-using-Generic-Routing-Encapsulation
- [GENEVE](https://www.redhat.com/en/blog/what-geneve) - 什么是GENEVE？

## Router

- [FreeRouter](http://freerouter.nop.hu/) - 基于Java的vRouter
- [Bird](http://bird.network.cz/) -  BIRD项目旨在开发一个功能齐全的动态IP路由守护进程，主要针对（但不限于）Linux，FreeBSD和其他类UNIX系统，并在GNU通用公共许可证下分发.
- [Quagga](http://www.quagga.net/)   -  Quagga是一个路由软件套件，为Unix平台提供OSPFv2，OSPFv3，RIP v1和v2，RIPng和BGP-4的实现，特别是FreeBSD，Linux，Solaris和NetBSD.  Quagga是由Kunihiro Ishiguro开发的GNU Zebra的分支.
- [FRRouting](https://frrouting.org/) - 适用于Linux和Unix平台的IP路由协议套件，包括BGP4，BGP4 +，OSPFv2，OSPFv3，RIPv1，RIPv2，RIPng，PIM-SM / MSDP和LDP的协议守护程序，以及对IS-IS，EIGRP和IS-IS的早期支持. NHRP.
- [BGPFeeder](https://projects.bytemark.co.uk/projects/bgpfeeder)
- [bgp4r](https://github.com/jesnault/bgp4r)   -  BGP4R是一个ruby库，可以创建和操作BGP消息.  在BGP4R中，所有众所周知的BGP构造都在类中定义.
- [gobgp](https://github.com/osrg/gobgp) -  GoBGP是一个开源的BGP实现，从头开始设计用于现代环境，并用现代编程语言Go编程语言实现.
- [yabgp](https://github.com/smartbgp/yabgp)   -  YABGP是BGP协议的另一个Python实现.  它可用于与各种路由器（包括真实的Cisco / HuaWei / Juniper路由器和一些路由器模拟器，如GNS3）建立BGP连接，并接收/解析BGP消息以供将来分析.

## Misc

- [Central Office Re-architected as a Datacenter, CORD](http://opencord.org) - 参考实施提供云经济和敏捷性的服务交付平台.
- [OPEN-Orchestrator Project, Open-O](https://www.open-o.org)
- [Open Source MANO Community, OSM](https://osm.etsi.org/welcome/)
- [Enhanced Controller Orchestration Management Policy, ECOMP](http://att.com/ecomp) - 运营管理框架.
- [Open Network Automation Platform, ONAP](https://www.onap.org/) - 两个项目的协调为虚拟网络功能的实时，政策驱动的软件自动化创建了一个协调和全面的框架，使软件，网络，IT和云提供商和开发人员能够快速创建新服务.
- [Mininet Spear Narmox](http://mininet.spear.narmox.com) - 在线Web服务提供Mininet拓扑的可视化

## High Performance Network
- [DPDK](http://dpdk.org/) -  DPDK是一组用于快速数据包处理的库和驱​​动程序.
 它可以在任何处理器上运行.  第一个支持的CPU是Intel x86，现在扩展到IBM POWER和ARM.
- [RDMA](https://en.wikipedia.org/wiki/Remote_direct_memory_access)   - 远程直接内存访问（RDMA）是从一台计算机的内存到另一台计算机的内存的直接内存访问，不涉及任何一个操作系统.  这允许高吞吐量，低延迟的网络
- [XDP](https://www.iovisor.org/technology/xdp) - 作为IO Visor项目的一部分，XDP或eXpress数据路径在Linux内核中提供高性能，可编程的网络数据路径.
- [ASAP2](http://www.mellanox.com/blog/2016/12/three-ways-asap2-beats-dpdk-for-cloud-and-nfv/) -  ASAP2加速器构建于eSwitch NIC硬件之上，允许将整个虚拟交换机或虚拟交换机或分布式虚拟路由器（DVR）操作的重要部分卸载到Mellanox NIC


## Userspace Network Stack
- [mTCP](https://github.com/eunyoung14/mtcp)   -  mTCP是用于多核系统的高度可扩展的用户级TCP堆栈.  mTCP源代码在Modified BSD License下分发.  有关更多详细信息，请参阅许可证.  io_engine驱动程序和移植应用程序的许可条款可能与mTCP不同.
- [net-next-nuse](https://github.com/libos-nuse/net-next-nuse)   - 用户空间中的网络堆栈（NUSE）NUSE允许我们将Linux网络堆栈用作库，通过链接库，任何应用程序都可以使用该库.  每个应用程序都有自己的网络堆栈，因此它提供了除主机操作系统之外的即时虚拟化环境.
- [drv-netif-dpdk](https://github.com/rumpkernel/drv-netif-dpdk)   -  drv-netif-dpdk是臀部内核的DPDK网络接口.  合并后的结果是通过DPDK进行数据包I / O的用户空间TCP / IP堆栈.
- [f-stack](https://github.com/F-Stack/f-stack) -  F-Stack是一种用户空间网络开发套件，具有基于DPDK，FreeBSD TCP / IP协议栈和协程API的高性能.
- [nff-go](https://github.com/intel-go/nff-go)   -  NFF-Go成为Linux Foundation下DPDK项目伞的一部分！  Mirror repo可以在这里找到：http：//dpdk.org/browse/apps/nff-go/.  我们也将通过DPDK邮件列表和标准DPDK贡献流程接受补丁.

## Analytics
- [PNDA](http://pnda.io/) - 适用于网络和服务的可扩展的开源大数据分析平台.
- [SNAS](http://www.snas.io/) - 流网络分析系统（项目SNAS）是一个实时收集，跟踪和访问数千万个路由对象（路由器，对等体，前缀）的框架.
- [Apache Spot](http://spot.incubator.apache.org/) - 社区驱动的网络安全项目，从头开始构建，在开放，可扩展的平台上为所有IT遥测数据提供高级分析

## Resources
## Books

- [SDN: Software Defined Networks: An Authoritative Review of Network Programmability Technologies](https://www.amazon.com/SDN-Software-Networks-Thomas-Nadeau/dp/1449342302/&tag=eltale-20)
- [圖解OpenFlow](http://www.books.com.tw/products/CN11301942)
- [重构网络-SDN架构与实现](http://www.sdnlab.com/book/18762.html)
- [深度解析SDN: 利益、战略、技术、实践](http://www.sdnlab.com/book/9470.html)
- [SDN核心技术剖析和实战指南](http://www.sdnlab.com/book/9480.html)
- [软件定义网络:SDN与OpenFlow解析](http://www.sdnlab.com/book/9473.html)
- [Network Algorithmics：An Interdisciplinary Approach to Designing Fast Networked Devices](https://doc.lagout.org/network/Network%20Algorithmics%20An%20Interdisciplinary%20Approach%20to%20Designing%20Fast%20Networked%20Devices.pdf)
- [Network Programmability and Automation Skills for the Next-Generation Network Engineer](http://shop.oreilly.com/product/0636920042082.do)
- [SDN网络指南](https://feisky.gitbooks.io/sdn/)（Pengfei Ni的OpenSource中文版）
- [DevOps for Networking](https://www.packtpub.com/networking-and-servers/devops-networking)
- [Software Defined Networking with OpenFlow](https://www.packtpub.com/networking-and-servers/software-defined-networking-openflow)

## Paper
- [SDN A Comprehensive Survey](https://pdfs.semanticscholar.org/d8bd/4c1e92420200bd29cb1a233bd81eb3c28bba.pdf)
- [A Guided Tour of Data-Center Networking](http://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/40404.pdf)
- [High Performance Datacenter Networks: Architectures, Algorithms, and Opportunities](https://static.googleusercontent.com/media/research.google.com/zh-TW//pubs/archive/37069.pdf)
- [Re-architecting datacenter networks and stacks for low latency and high performance](http://dl.acm.org/citation.cfm?id=3098825)
- [A Survey on the Security of Stateful SDN Data Planes](https://ieeexplore.ieee.org/document/7890396)

## Awesome Posts
- [VXLAN L3应用EVPN，呈现完整overlay网络](https://www.sdnlab.com/19879.html)
