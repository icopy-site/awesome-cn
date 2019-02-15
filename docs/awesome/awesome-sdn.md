## Awesome SDN [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/sdnds-tw/awesome-sdn.svg?branch=master)](https://travis-ci.org/sdnds-tw/awesome-sdn)

An awesome list about Software Defined Networks (SDN)

- [Awesome SDN](#awesome-sdn)
  - [Introduction](#introduction)
  - [Network Operating System](#network-operating-system)
  - [Install Environment](#install-environment)
  - [Software Switch](#software-switch)
  - [Network Virtualization](#network-virtualization)
  - [Protocol](#protocol)
  - [Controller](#controller)
  - [Simulator/Emulator](#simulatoremulator)
  - [Language](#language)
  - [Library](#library)
  - [Test](#test)
  - [NFV](#nfv)
  - [Overlay Network](#overlay-network)
  - [Router](#router)
  - [Misc](#misc)
  - [High Performacne Network](#high-performance-network)
  - [Userspace Network Stack](#userspace-network-stack)
  - [Analytics](#analytics)
- [Resources](#resources)
  - [Books](#books)
  - [Paper](#paper)

## Introduction
  Software-defined networking (SDN) is an approach to computer networking that allows network administrators to manage network services through abstraction of higher-level functionality.
  Wiki : [Software-Defined Networking](https://en.wikipedia.org/wiki/Software-defined_networking)

## Network Operating System
- [PicOS](http://www.pica8.com/products/picos) - A SDN OS for white box switches Layer-2/3 feature set with support for OpenFlow, OVSDB, and other protocols.
- [Open Network Linux, ONL](https://opennetlinux.org) - A Linux distribution for "bare metal" switches, that is, network forwarding devices built from commodity components.
- [OpenSwitch](http://www.openswitch.net) - A linux network operating system from Dell EMC.
- [Cumulus Linux](https://cumulusnetworks.com) - Cumulus Linux is a powerful open network operating system that allows you to automate, customize and scale using web-scale principles like the world's largest data centers.
- [OcNOS](https://www.ipinfusion.com/) - Extensive switching and routing protocol support with advanced
capabilities such as MPLS and SDN
- [FlexSwitch](https://snaproute.com/) - The first open source network protocol suite offering complete layer2/layer3 functionality for accelerating development and deployment of whitebox networking gear
- [beluganos](https://github.com/beluganos/beluganos) - Beluganos is a new network OS designed for white-box switches (OF-DPA), which can apply large-scale networks.
- [SONiC](https://azure.github.io/SONiC/) - Software for Open Networking in the Cloud
SONiC
- [Stratum](https://stratumproject.org/) - An open source, silicon-independent switch operating system for software-defined networks
- [OpenWrt](https://openwrt.org/) -  Is a Linux Operating System targeting embedded devices.


## Install Environment
- [ONIE](http://onie.org/) - ONIE enables a bare metal network switch ecosystem where end users have a choice among different network operating systems.

## Software Switch

- [Open vSwitch](http://openvswitch.org/) - Open vSwitch is a production quality, multilayer virtual switch.
- [Indigo](https://github.com/floodlight/indigo) - Indigo is an open source project aimed at enabling support for OpenFlow on physical and hypervisor switches.
- [CPqD](https://github.com/CPqD/ofsoftswitch13)- An OpenFlow 1.3 compatible user-space software switch implementation
- [Lagopus](https://lagopus.github.io) - A high-performance software OpenFlow 1.3 switch.
- [LINC-Switch](https://github.com/FlowForwarding/LINC-Switch) - A pure OpenFlow software switch written in Erlang
- [snabbswitch](https://github.com/SnabbCo/snabbswitch) - An open source virtualized Ethernet networking stack.
- [ZeroTier](https://github.com/zerotier/ZeroTierOne) - ZeroTier is a software-based managed Ethernet switch for planet Earth.
- [PISCES](http://pisces.cs.princeton.edu/) - A Programmable, Protocol-Independent Software Switch.
- [BESS](https://github.com/NetSys/bess) - Berkeley Extensible Software Switch, BESS is a modular framework for software switches.
- [FD.IO](https://fd.io/) - Relentlessly focused on data IO speed and efficiency for more flexible and scalable networks and storage
- [bmv2](https://github.com/p4lang/behavioral-model)-  A P4 software switch which is usually used as a tool to verify the funtions the developers describe in P4 language.

## Network Virtualization

- [FlowVisor](https://github.com/opennetworkinglab/flowvisor) - An OpenFlow controller that acts as a hypervisor/proxy between a switch and multiple controllers. Can slice multiple switches in parallel, effectively slicing a network.
- [OpenVirtex](https://github.com/opennetworkinglab/OpenVirteX) - A network hypervisor that can create multiple virtual and programmable networks on top of a single physical infrastructure.

## Protocol

- [OpenFlow](https://www.opennetworking.org/sdn-resources/openflow) - A communications protocol that gives access to the forwarding plane of a network switch or router over the network.
- [OF-Config](https://www.opennetworking.org/technical-communities/areas/specification/of-config/) - OpenFlow Management and Configuration Protocol
- [OVSDB](https://tools.ietf.org/html/rfc7047) - A communication protocol which used to manage the OpenvSwitch database.
- [NETCONF](https://en.wikipedia.org/wiki/NETCONF)
- [OpFlex](http://www.cisco.com/c/en/us/solutions/collateral/data-center-virtualization/application-centric-infrastructure/white-paper-c11-731302.html)
- [Path Computation Element Protocol, PCEP](https://www.juniper.net/documentation/en_US/junos/topics/concept/mpls-pcep-overview.html)
- [Extensible Messaging and Presence Protocol, XMPP](https://en.wikipedia.org/wiki/XMPP)
- [P4 Runtime](https://p4.org/api/p4-runtime-putting-the-control-plane-in-charge-of-the-forwarding-plane.html)

## Controller

- [NOX](https://github.com/noxrepo/nox) - An open source development platform for C++-based software-defined networking (*SDN*) control applications.
- [POX](https://github.com/noxrepo/pox) - An open source development platform for Python-based software-defined networking (*SDN*) control applications.
- [NodeFlow](https://github.com/gaberger/NodeFLow) - An OpenFlow Controller Node Style.
- [ONOS](http://onosproject.org) - Open Network Operating System.
- [OpenDaylight](https://www.opendaylight.org) - OpenDaylight Platform
- [Ryu](https://osrg.github.io/ryu) - A component-based software defined networking framework.
- [Floodlight](https://github.com/floodlight/floodlight) - A java-based OpenFlow controller.
- [Vyatta](https://github.com/BRCDcomm/BVC/) - The first commercial Controller built directly from OpenDaylight.
- [OpenContrail](http://www.opencontrail.org/) - A SDN project that utilizes SDN & NFV and provides all the necessary components for network virtualization.
- [IRIS](http://openiris.etri.re.kr/) - A Resursive SDN Openflow Controller created by SDN Research Section, ETRI.
- [Open MUL](http://www.openmul.org/openmul-controller.html) - A lightweight SDN/Openflow controller written almost entirely in C from scratch.
- [OESS](https://github.com/globalnoc/oess) - The Open Exchange Software Suite to configure and control OpenFlow Enabled switches.
- [Beehive Network Controller](https://github.com/kandoo/beehive-netctrl) - A distributed SDN controller built on top of Beehive. It supports OpenFlow but can be easily extended for other southbound protocols.
- [Ravel](https://github.com/ravel-net/ravel) - A software-defined networking (SDN) controller that uses a standard SQL database to represent the network.
- [Trema](https://trema.github.io/trema/) - A full-stack, easy-to-use framework for developing OpenFlow controllers in Ruby and C.
- [Open Security Controller](https://www.opensecuritycontroller.org/) - Software-defined security orchestration solution that automates deployment of virtualized network security functions, like next-generation firewall, intrusion prevention systems and application data controllers
- [Netrack](https://github.com/netrack/openflow) - An OpenFlow controller framework in Go.
- [OVN](http://www.openvswitch.org//support/slides/OVN-Vancouver.pdf) - OVN: Open Virtual Network for Open vSwitch

## Simulator/Emulator

- [Mininet](http://mininet.org/) - An Instant Virtual Network on your Laptop (or other PC)
- [OpenNet](http://github.com/dlinknctu/opennet) - A simulator for software-defined wireless local area network
- [EstiNet](http://www.estinet.com/products.php?lv1=13&sn=13) - A world-renowned software tool for network planning
- [ns-3](https://www.nsnam.org/) - A discrete-event network simulator that supports OpenFlow environment.
- [Containernet](https://github.com/containernet/containernet) - Mininet fork that allows to use Docker containers as hosts in emulated networks
- [Tinynet](https://github.com/John-Lin/tinynet) - A lightweight instant virtual network for rapid prototyping SDN
- [MaxiNet](http://maxinet.github.io) - MaxiNet extends the famous Mininet emulation environment to span the emulation across several physical machines. This allows to emulate very large software-defined networks.

## Language

- [P4](http://p4.org/) - A declarative language for expressing how packets are processed by the pipeline of a network forwarding element such as a switch, NIC, router or network function appliance.
- [POF](https://dl.acm.org/citation.cfm?id=2491190) - Protocol Oblivious Forwarding
- [Frenetic](https://github.com/frenetic-lang/frenetic) - The Frenetic Programming Language and Runtime System
- [Pyretic](http://www.frenetic-lang.org/pyretic/) - Pyretic is one member of the Frenetic family of SDN programming languages.
- [NEMO](https://wiki.onosproject.org/display/ONOS/NEMO+Language) - A domain specific language (DSL) based on abstraction of network models and conclusion of operation patterns.

## Library

- [loxigen](https://github.com/floodlight/loxigen) - LoxiGen is a tool that generates OpenFlow protocol libraries for a number of languages.
- [openfaucet](https://github.com/rlenglet/openfaucet) - openfaucet is a pure Python implementation of the OpenFlow 1.0.0
protocol, based on Twisted.
- [oflib-node](https://github.com/TrafficLab/oflib-node) - Oflib-node is an OpenFlow protocol library for Node. It converts between OpenFlow wire protocol messages and Javascript objects.
- [OpenFlowJ](https://bitbucket.org/openflowj/openflowj) - A Java implementation of low-level OpenFlow packet marshalling/unmarshalling and IO operations.
- [nettle](https://github.com/AndreasVoellmy/openflow) - A Haskell library for working with the OpenFlow protocol.
- [OCaml OpenFlow](https://github.com/frenetic-lang/ocaml-openflow) - A serialization and protocol library for OpenFlow.
- [Scapy](http://www.secdev.org/projects/scapy/) - Scapy is a powerful interactive packet manipulation program.

## Test

- [oftest](https://github.com/floodlight/oftest) - OpenFlow Testing Framework
- [STS](https://ucb-sts.github.com/sts/) - SDN Troubleshooting System, simulates network devices, allowing programmatically test cases generation.
- [nice-of](https://code.google.com/archive/p/nice-of/) - A tool to test OpenFlow controller application for the NOX controller platform.
- [OpenSDNCore](http://www.opensdncore.org/) - Virtualisation Testbed for NFV/SDN Environment.
- [Cbenech](https://github.com/mininet/oflops/tree/master/cbench) - Benchmarking tool for controllers
- [ptf](https://github.com/p4lang/ptf) - A python based dataplane test framework based on unittest.

## NFV

- [OPNFV](https://www.opnfv.org) - Accelerating NFV's evolution through an integrated, open platform.

## Overlay Network

- [VXLAN](https://en.wikipedia.org/wiki/Virtual_Extensible_LAN) - Virtual Extensible LAN
- [NVGRE](https://tools.ietf.org/html/draft-sridharan-virtualization-nvgre-00) - NVGRE-Network-Virtualization-using-Generic-Routing-Encapsulation
- [GENEVE](https://www.redhat.com/en/blog/what-geneve) - What is GENEVE?

## Router

- [FreeRouter](http://freerouter.nop.hu/) - Java-based vRouter
- [Bird](http://bird.network.cz/) - The BIRD project aims to develop a fully functional dynamic IP routing daemon primarily targeted on (but not limited to) Linux, FreeBSD and other UNIX-like systems and distributed under the GNU General Public License.
- [Quagga](http://www.quagga.net/) - Quagga is a routing software suite, providing implementations of OSPFv2, OSPFv3, RIP v1 and v2, RIPng and BGP-4 for Unix platforms, particularly FreeBSD, Linux, Solaris and NetBSD. Quagga is a fork of GNU Zebra which was developed by Kunihiro Ishiguro.
- [FRRouting](https://frrouting.org/) - An IP routing protocol suite for Linux and Unix platforms which includes protocol daemons for BGP4, BGP4+, OSPFv2, OSPFv3, RIPv1, RIPv2, RIPng, PIM-SM/MSDP and LDP as well as very early support for IS-IS, EIGRP and NHRP.
- [BGPFeeder](https://projects.bytemark.co.uk/projects/bgpfeeder)
- [bgp4r](https://github.com/jesnault/bgp4r) - BGP4R is a ruby library which enables the creation and manipulation of BGP messages. In BGP4R, all well-known BGP constructs are defined in classes.
- [gobgp](https://github.com/osrg/gobgp) - GoBGP is an open source BGP implementation designed from scratch for modern environment and implemented in a modern programming language, the Go Programming Language.
- [yabgp](https://github.com/smartbgp/yabgp) - YABGP is a yet another Python implementation for BGP Protocol. It can be used to establish BGP connections with all kinds of routers (include real Cisco/HuaWei/Juniper routers and some router simulators like GNS3) and receive/parse BGP messages for future analysis.

## Misc

- [Central Office Re-architected as a Datacenter, CORD](http://opencord.org) - Reference Implementation of a Service Delivery Platform that Provides Cloud Economies and Agility.
- [OPEN-Orchestrator Project, Open-O](https://www.open-o.org)
- [Open Source MANO Community, OSM](https://osm.etsi.org/welcome/)
- [Enhanced Controller Orchestration Management Policy, ECOMP](http://att.com/ecomp) - Operations management framework.
- [Open Network Automation Platform, ONAP](https://www.onap.org/) - Alignment of the two projects creates a harmonized and comprehensive framework for real-time, policy-driven software automation of virtual network functions that will enable software, network, IT and cloud providers and developers to rapidly create new services.
- [Mininet Spear Narmox](http://mininet.spear.narmox.com) - A online web service provides a visualization of Mininet Topology

## High Performance Network
- [DPDK](http://dpdk.org/) - DPDK is a set of libraries and drivers for fast packet processing.
It is designed to run on any processors. The first supported CPU was Intel x86 and it is now extended to IBM POWER and ARM.
- [RDMA](https://en.wikipedia.org/wiki/Remote_direct_memory_access) - Remote direct memory access (RDMA) is a direct memory access from the memory of one computer into that of another without involving either one's operating system. This permits high-throughput, low-latency networking
- [XDP](https://www.iovisor.org/technology/xdp) - XDP or eXpress Data Path provides a high performance, programmable network data path in the Linux kernel as part of the IO Visor Project.
- [ASAP2](http://www.mellanox.com/blog/2016/12/three-ways-asap2-beats-dpdk-for-cloud-and-nfv/) - The ASAP2 accelerator is built on top of eSwitch NIC hardware, and allows either the entire virtual switch, or significant portions of virtual switch or distributed virtual router (DVR) operations to be offloaded to the Mellanox NIC


## Userspace Network Stack
- [mTCP](https://github.com/eunyoung14/mtcp) - mTCP is a highly scalable user-level TCP stack for multicore systems. mTCP source code is distributed under the Modified BSD License. For more detail, please refer to the LICENSE. The license term of io_engine driver and ported applications may differ from the mTCP’s.
- [net-next-nuse](https://github.com/libos-nuse/net-next-nuse) - Network Stack in Userspace (NUSE) NUSE allows us to use Linux network stack as a library which any applications can directory use by linking the library. Each application has its own network stack so, it provides an instant virtualized environment apart from a host operating system.
- [drv-netif-dpdk](https://github.com/rumpkernel/drv-netif-dpdk) - drv-netif-dpdk is a DPDK network interface for rump kernels. The combined result is a userspace TCP/IP stack doing packet I/O via DPDK.
- [f-stack](https://github.com/F-Stack/f-stack) - F-Stack is an user space network development kit with high performance based on DPDK, FreeBSD TCP/IP stack and coroutine API.
- [nff-go](https://github.com/intel-go/nff-go) - NFF-Go becomes part of DPDK project umbrella under Linux Foundation! Mirror repo can be found here: http://dpdk.org/browse/apps/nff-go/. We will accept patches through DPDK mail-list and standard DPDK contribution process too.

## Analytics
- [PNDA](http://pnda.io/) - The scalable, open source big data analytics platform for networks and services.
- [SNAS](http://www.snas.io/) - Streaming Network Analytics System (project SNAS) is a framework to collect, track and access tens of millions of routing objects (routers, peers, prefixes) in real time.
- [Apache Spot](http://spot.incubator.apache.org/) - Community-driven cybersecurity project, built from the ground up, to bring advanced analytics to all IT Telemetry data on an open, scalable platform

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
- [SDN网络指南](https://feisky.gitbooks.io/sdn/)(OpenSource Book in Chinese by Pengfei Ni)
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
