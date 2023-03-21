<div class="github-widget" data-repo="sdnds-tw/awesome-sdn"></div>
## Awesome SDN [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/sdnds-tw/awesome-sdn.svg?branch=master)](https://travis-ci.org/sdnds-tw/awesome-sdn)

关于软件定义网络 (SDN) 的精彩列表


## Introduction
  软件定义网络 (SDN) 是一种计算机网络方法，它允许网络管理员通过抽象更高级别的功能来管理网络服务.
  星期 ： [Software-Defined Networking](https://en.wikipedia.org/wiki/Software-defined_networking)

## Network Operating System

- [Beluganos](https://github.com/beluganos/beluganos) - Beluganos是专为白盒交换机（OF-DPA）设计的新型网络操作系统，适用于大规模网络.
- [Cumulus Linux](https://cumulusnetworks.com) - Cumulus Linux 是一个强大的开放式网络操作系统，允许您使用像世界上最大的数据中心这样的网络规模原则来实现自动化、定制和扩展.
- [FlexSwitch](https://snaproute.com/) - 第一个开源网络协议套件，提供完整的第 2 层/第 3 层功能，用于加速白盒网络设备的开发和部署
- [Mion](https://github.com/opencomputeproject/mion) - 基于 ONLP API 和 Yocto 项目的交换机操作系统.
- [OcNOS](https://www.ipinfusion.com/) - 广泛的交换和路由协议支持，具有 MPLS 和 SDN 等高级功能
- [Open Network Linux, ONL](https://opennetlinux.org) - 用于“裸机”交换机的 Linux 发行版，即由商品组件构建的网络转发设备.
- [OpenSwitch](http://www.openswitch.net) - 来自 Dell EMC 的 linux 网络操作系统.
- [OpenWrt](https://openwrt.org/) -  Is a Linux Operating System targeting embedded devices.
- [PicOS](http://www.pica8.com/products/picos) - 用于白盒交换机第 2/3 层功能集的 SDN 操作系统，支持 OpenFlow、OVSDB 和其他协议.
- [SONiC](https://azure.github.io/SONiC/) - 用于云 SONiC 中的开放网络的软件
- [Stratum](https://stratumproject.org/) - 用于软件定义网络的开源、独立于硅的交换机操作系统

## Install Environment

- [ONIE](http://onie.org/) - ONIE 支持裸机网络交换机生态系统，最终用户可以在不同的网络操作系统之间进行选择.

## Software Switch

- [BESS](https://github.com/NetSys/bess) - Berkeley Extensible Software Switch，BESS 是软件交换机的模块化框架.
- [bmv2](https://github.com/p4lang/behavioral-model)- 一个P4软件开关，通常用作验证开发人员用P4语言描述的功能的工具.
- [CPqD](https://github.com/CPqD/ofsoftswitch13)- OpenFlow 1.3 兼容的用户空间软件交换机实现
- [FD.IO](https://fd.io/) - 不懈地专注于数据 IO 速度和效率，以实现更灵活和可扩展的网络和存储
- [Indigo](https://github.com/floodlight/indigo) - Indigo 是一个开源项目，旨在在物理和管理程序交换机上启用对 OpenFlow 的支持.
- [Lagopus](https://lagopus.github.io) - 高性能软件 OpenFlow 1.3 交换机.
- [LINC-Switch](https://github.com/FlowForwarding/LINC-Switch) - 用 Erlang 编写的纯 OpenFlow 软件交换机
- [Open vSwitch](http://openvswitch.org/) - Open vSwitch 是一种生产质量的多层虚拟交换机.
- [PISCES](https://www.cs.princeton.edu/~jrex/papers/pisces16.pdf) - 一个可编程的、独立于协议的软件开关.
- [snabbswitch](https://github.com/SnabbCo/snabbswitch) - 开源虚拟化以太网网络堆栈.
- [ZeroTier](https://github.com/zerotier/ZeroTierOne) - ZeroTier 是一个基于软件的地球托管以太网交换机.

## Network Virtualization

- [FlowVisor](https://github.com/opennetworkinglab/flowvisor)  - 一个 OpenFlow 控制器，充当交换机和多个控制器之间的管理程序/代理. 可以并行切片多个交换机，有效地切片网络.
- [OpenVirtex](https://github.com/opennetworkinglab/OpenVirteX) - 可以在单个物理基础设施之上创建多个虚拟和可编程网络的网络管理程序.

## Protocol

- [OpenFlow](https://www.opennetworking.org/sdn-resources/openflow) - 一种通信协议，允许通过网络访问网络交换机或路由器的转发平面.
- [OF-Config](https://www.opennetworking.org/technical-communities/areas/specification/of-config/) - OpenFlow 管理和配置协议
- [OVSDB](https://tools.ietf.org/html/rfc7047) - 用于管理 OpenvSwitch 数据库的通信协议.
- [NETCONF](https://en.wikipedia.org/wiki/NETCONF)
- [OpFlex](http://www.cisco.com/c/en/us/solutions/collateral/data-center-virtualization/application-centric-infrastructure/white-paper-c11-731302.html)
- [Path Computation Element Protocol, PCEP](https://www.juniper.net/documentation/en_US/junos/topics/concept/mpls-pcep-overview.html)
- [Extensible Messaging and Presence Protocol, XMPP](https://en.wikipedia.org/wiki/XMPP)
- [P4 Runtime](https://p4.org/api/p4-runtime-putting-the-control-plane-in-charge-of-the-forwarding-plane.html)
- [gNMI](https://github.com/openconfig/gnmi/) - gRPC 网络管理接口
- [gNOI](https://github.com/openconfig/gnoi) - gRPC 网络操作接口

## Controller

- [Beehive Network Controller](https://github.com/kandoo/beehive-netctrl)  - 基于 Beehive 构建的分布式 SDN 控制器. 它支持 OpenFlow，但可以轻松扩展到其他南向协议.
- [Floodlight](https://github.com/floodlight/floodlight) - 基于 Java 的 OpenFlow 控制器.
- [IRIS](http://openiris.etri.re.kr/) - 由 ETRI 的 SDN 研究部创建的 Resursive SDN Openflow 控制器.
- [lighty.io core](https://github.com/PantheonTechnologies/lighty-core) - lighty.io 核心组件 - 用于构建基于 Java 的 SDN 控制器的开源开发框架.
- [Netrack](https://github.com/netrack/openflow) - Go 中的 OpenFlow 控制器框架.
- [NodeFlow](https://github.com/gaberger/NodeFLow) - OpenFlow 控制器节点样式.
- [NOX](https://github.com/noxrepo/nox) - 用于基于 C++ 的软件定义网络 (*SDN*) 控制应用程序的开源开发平台.
- [OESS](https://github.com/globalnoc/oess) - 用于配置和控制支持 OpenFlow 的交换机的 Open Exchange 软件套件.
- [ONOS](http://onosproject.org) - 开放式网络操作系统.
- [Open MUL](http://www.openmul.org/openmul-controller.html) - 几乎完全用 C 从头开始​​编写的轻量级 SDN/Openflow 控制器.
- [Open Security Controller](https://www.opensecuritycontroller.org/) - 软件定义的安全编排解决方案，可自动部署虚拟化网络安全功能，如下一代防火墙、入侵防御系统和应用程序数据控制器
- [OpenContrail](https://tungsten.io/opencontrail-is-now-tungsten-fabric/) - 一个利用 SDN 和 NFV 并为网络虚拟化提供所有必要组件的 SDN 项目.
- [OpenDaylight](https://www.opendaylight.org) - OpenDaylight 平台
- [OVN](http://www.openvswitch.org//support/slides/OVN-Vancouver.pdf) - OVN：Open vSwitch 的开放虚拟网络
- [POX](https://github.com/noxrepo/pox) - An open source development platform for Python-based software-defined networking (*SDN*) control applications.
- [Ravel](https://github.com/ravel-net/ravel) - 软件定义网络 (SDN) 控制器，使用标准 SQL 数据库来表示网络.
- [Ryu](https://ryu-sdn.org/) - 基于组件的软件定义网络框架.
- [Trema](https://trema.github.io/trema/) - 用于在 Ruby 和 C 中开发 OpenFlow 控制器的全栈、易于使用的框架.
- [Vyatta](https://github.com/BRCDcomm/BVC/) - 第一个直接从 OpenDaylight 构建的商业控制器.

## Simulator/Emulator

- [Containernet](https://github.com/containernet/containernet) - 允许在模拟网络中使用 Docker 容器作为主机的 Mininet 分支
- [EstiNet](http://www.estinet.com/products.php?lv1=13&sn=13) - 享誉全球的网络规划软件工具
- [MaxiNet](http://maxinet.github.io)  - MaxiNet 扩展了著名的 Mininet 仿真环境，将仿真跨越多个物理机器. 这允许模拟非常大的软件定义网络.
- [Mininet](http://mininet.org/) - 笔记本电脑（或其他 PC）上的即时虚拟网络
- [ns-3](https://www.nsnam.org/) - 支持 OpenFlow 环境的离散事件网络模拟器.
- [OpenNet](http://github.com/dlinknctu/opennet) - 软件定义无线局域网模拟器
- [Tinynet](https://github.com/John-Lin/tinynet) - 用于快速原型设计 SDN 的轻量级即时虚拟网络

## Language

- [Frenetic](https://github.com/frenetic-lang/frenetic) - 狂热的编程语言和运行时系统
- [NEMO](https://wiki.onosproject.org/display/ONOS/NEMO+Language) - 基于网络模型抽象和操作模式结论的领域特定语言（DSL）.
- [P4](http://p4.org/) - 一种声明性语言，用于表达网络转发元素（如交换机、NIC、路由器或网络功能设备）的管道如何处理数据包.
- [POF](https://dl.acm.org/citation.cfm?id=2491190) - 协议无视转发
- [Pyretic](http://www.frenetic-lang.org/pyretic/) - Pyretic 是 SDN 编程语言 Frenetic 家族的一员.

## Library

- [loxigen](https://github.com/floodlight/loxigen) - LoxiGen 是一种为多种语言生成 OpenFlow 协议库的工具.
- [nettle](https://github.com/AndreasVoellmy/openflow) - 用于使用 OpenFlow 协议的 Haskell 库.
- [OCaml OpenFlow](https://github.com/frenetic-lang/ocaml-openflow) - OpenFlow 的序列化和协议库.
- [oflib-node](https://github.com/TrafficLab/oflib-node)  - Oflib-node 是 Node.js 的 OpenFlow 协议库. 它在 OpenFlow 有线协议消息和 Javascript 对象之间进行转换.
- [openfaucet](https://github.com/rlenglet/openfaucet) - openfaucet 是基于 Twisted 的 OpenFlow 1.0.0 协议的纯 Python 实现.
- [OpenFlowJ](https://bitbucket.org/openflowj/openflowj) - 低级 OpenFlow 数据包编组/解组和 IO 操作的 Java 实现.
- [Scapy](http://www.secdev.org/projects/scapy/) - Scapy 是一个强大的交互式数据包操作程序.

## Test

- [Cbenech](https://github.com/mininet/oflops/tree/master/cbench) - 控制器基准测试工具
- [nice-of](https://code.google.com/archive/p/nice-of/) - 用于测试 NOX 控制器平台的 OpenFlow 控制器应用程序的工具.
- [oftest](https://github.com/floodlight/oftest) - 开放流测试框架
- [OpenSDNCore](http://www.opensdncore.org/) - NFV/SDN 环境的虚拟化测试台.
- [ptf](https://github.com/p4lang/ptf) - 基于 unittest 的基于 python 的数据平面测试框架.
- [STS](https://ucb-sts.github.com/sts/) - SDN 故障排除系统，模拟网络设备，允许以编程方式生成测试用例.

## NFV

- [OPNFV](https://www.opnfv.org) - 通过集成的开放平台加速 NFV 的发展.

## Overlay Network

- [GENEVE](https://www.redhat.com/en/blog/what-geneve) - 什么是日内瓦？
- [NVGRE](https://tools.ietf.org/html/draft-sridharan-virtualization-nvgre-00) - NVGRE-Network-Virtualization-using-Generic-Routing-Encapsulation
- [VXLAN](https://en.wikipedia.org/wiki/Virtual_Extensible_LAN) - 虚拟可扩展局域网

## Router

- [bgp4r](https://github.com/jesnault/bgp4r)  - BGP4R 是一个 ruby​​ 库，可以创建和操作 BGP 消息. 在 BGP4R 中，所有众所周知的 BGP 构造都在类中定义.
- [BGPFeeder](https://github.com/BytemarkHosting/bgpfeeder)
- [Bird](http://bird.network.cz/) - BIRD 项目旨在开发功能齐全的动态 IP 路由守护程序，主要针对（但不限于）Linux、FreeBSD 和其他类 UNIX 系统，并在 GNU 通用公共许可证下分发.
- [FreeRouter](http://freerouter.nop.hu/) - 基于 Java 的 vRouter
- [FRRouting](https://frrouting.org/) - 用于 Linux 和 Unix 平台的 IP 路由协议套件，包括 BGP4、BGP4+、OSPFv2、OSPFv3、RIPv1、RIPv2、RIPng、PIM-SM/MSDP 和 LDP 的协议守护进程，以及对 IS-IS、EIGRP 和国家人权计划.
- [gobgp](https://github.com/osrg/gobgp) - GoBGP 是一种开源 BGP 实现，从头开始为现代环境设计，并以现代编程语言 Go 编程语言实现.
- [Quagga](http://www.quagga.net/)  - Quagga 是一个路由软件套件，为 Unix 平台（尤其是 FreeBSD、Linux、Solaris 和 NetBSD）提供 OSPFv2、OSPFv3、RIP v1 和 v2、RIPng 和 BGP-4 的实现.  Quagga 是由 Kunihiro Ishiguro 开发的 GNU Zebra 的一个分支.
- [yabgp](https://github.com/smartbgp/yabgp)  - YABGP 是 BGP 协议的另一个 Python 实现. 它可用于与各种路由器（包括真正的 Cisco/HuaWei/Juniper 路由器和一些路由器模拟器，如 GNS3）建立 BGP 连接，并接收/解析 BGP 消息以供将来分析.

## Misc

- [Aether Project](https://www.opennetworking.org/aether/) - 第一个开源企业 5G/LTE 边缘云即服务平台 (ECaaS).
- [Central Office Re-architected as a Datacenter, CORD](http://opencord.org) - 提供云经济性和敏捷性的服务交付平台的参考实施.
- [Mininet Spear Narmox](http://mininet.spear.narmox.com) - 在线网络服务提供 Mininet 拓扑的可视化
- [Open Network Automation Platform, ONAP](https://www.onap.org/) - 这两个项目的结合为虚拟网络功能的实时、策略驱动的软件自动化创建了一个协调和全面的框架，这将使软件、网络、IT 和云提供商和开发人员能够快速创建新服务.
- [Open Source MANO Community, OSM](https://osm.etsi.org/welcome/)
- [OPEN-Orchestrator Project, Open-O](https://www.open-o.org)

## High Performance Network

- [ASAP2](http://www.mellanox.com/blog/2016/12/three-ways-asap2-beats-dpdk-for-cloud-and-nfv/) - ASAP2 加速器建立在 eSwitch NIC 硬件之上，允许将整个虚拟交换机或虚拟交换机或分布式虚拟路由器 (DVR) 操作的重要部分卸载到 Mellanox NIC
- [DPDK](http://dpdk.org/) - DPDK 是一组用于快速数据包处理的库和驱​​动程序.
- [RDMA](https://en.wikipedia.org/wiki/Remote_direct_memory_access)  - 远程直接内存访问 (RDMA) 是从一台计算机的内存到另一台计算机的内存的直接内存访问，而不涉及任何一个操作系统. 这允许高吞吐量、低延迟的网络
- [XDP](https://www.iovisor.org/technology/xdp) - XDP 或 eXpress 数据路径在 Linux 内核中作为 IO Visor 项目的一部分提供高性能、可编程的网络数据路径.
它旨在在任何处理器上运行. 第一个支持的 CPU 是 Intel x86，现在扩展到 IBM POWER 和 ARM.


## Userspace Network Stack

- [drv-netif-dpdk](https://github.com/rumpkernel/drv-netif-dpdk)  - drv-netif-dpdk 是 rump 内核的 D​​PDK 网络接口. 组合结果是用户空间 TCP/IP 堆栈通过 DPDK 执行数据包 I/O.
- [f-stack](https://github.com/F-Stack/f-stack) - F-Stack 是一个基于 DPDK、FreeBSD TCP/IP 堆栈和协程 API 的高性能用户空间网络开发套件.
- [mTCP](https://github.com/eunyoung14/mtcp)  - mTCP 是用于多核系统的高度可扩展的用户级 TCP 堆栈.  mTCP 源代码在修改后的 BSD 许可证下分发. 有关详细信息，请参阅许可证.  io_engine 驱动程序和移植应用程序的许可条款可能与 mTCP 的不同.
- [net-next-nuse](https://github.com/libos-nuse/net-next-nuse)  - 用户空间中的网络堆栈 (NUSE) NUSE 允许我们将 Linux 网络堆栈用作一个库，任何应用程序都可以通过链接该库进行目录使用. 每个应用程序都有自己的网络堆栈，因此它提供了一个与主机操作系统不同的即时虚拟化环境.
- [nff-go](https://github.com/intel-go/nff-go)  - NFF-Go 成为 Linux 基金会下 DPDK 项目保护伞的一部分！ 可以在此处找到镜像仓库：http://dpdk.org/browse/apps/nff-go/. 我们也将通过 DPDK 邮件列表和标准 DPDK 贡献流程接受补丁.

## Analytics

- [Apache Spot](http://spot.incubator.apache.org/) - 社区驱动的网络安全项目，从头开始构建，在开放、可扩展的平台上对所有 IT 遥测数据进行高级分析
- [PNDA](http://pnda.io/) - 用于网络和服务的可扩展、开源大数据分析平台.
- [SNAS](http://www.snas.io/) - 流式网络分析系统（项目 SNAS）是一个实时收集、跟踪和访问数千万路由对象（路由器、对等点、前缀）的框架.

## Resources
## Books

- [DevOps for Networking](https://www.packtpub.com/networking-and-servers/devops-networking)
- [Network Algorithmics：An Interdisciplinary Approach to Designing Fast Networked Devices](https://doc.lagout.org/network/Network%20Algorithmics%20An%20Interdisciplinary%20Approach%20to%20Designing%20Fast%20Networked%20Devices.pdf)
- [Network Programmability and Automation Skills for the Next-Generation Network Engineer](http://shop.oreilly.com/product/0636920042082.do)
- [SDN: Software Defined Networks: An Authoritative Review of Network Programmability Technologies](https://www.oreilly.com/library/view/sdn-software-defined/9781449342425/)
- [SDN网络指南](https://feisky.gitbooks.io/sdn/)（倪鹏飞的中文开源书籍）
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
