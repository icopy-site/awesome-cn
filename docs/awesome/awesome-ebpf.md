<div class="github-widget" data-repo="zoidbergwill/awesome-ebpf"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome eBPF [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 与 eBPF 相关的精彩项目的精选列表.

 BPF，就像在_Berkeley Packet Filter_中一样，是一个运行从用户空间传递的程序的内核虚拟机. 最初在 BSD 上实现，然后在 Linux 上实现，（现在是传统的）“经典 BPF”或 cBPF 机器将与 tcpdump 等工具一起用于过滤内核中的数据包以避免对用户空间的无用副本. 最近，Linux 中的 BPF 基础架构已经完全重新设计并赋予“扩展 BPF”或 eBPF 生命，它获得了新特性（安全和终止检查、程序的 JIT 编译、持久映射、标准库、硬件卸载支持等），现在用于许多任务. 在非常低的级别（XDP）处理数据包，跟踪和监视系统上的事件，或者对 cgroup 实施访问控制只是 eBPF 带来性能、可编程性和灵活性的几个例子.

Recently [Cilium](https://cilium.io) 推出了一个很棒的关于 eBPF 的网站，叫做 [ebpf.io](https://ebpf.io/) . 它与此列表的目的相似，具有 [an introduction to eBPF](https://ebpf.io/what-is-ebpf) 和链接到 [related projects](https://ebpf.io/projects).

 &gt; 注意：eBPF 是一项令人兴奋的技术，其生态系统在不断发展. 我们希望 _you_ 提供帮助，以使这个很棒的列表保持最新状态，并尽我们所能提高其信噪比. 请随时离开 [any feedback](https://github.com/zoidbergwill/awesome-ebpf/issues).



## Reference Documentation

### eBPF Essentials

- [ebpf.io](https://ebpf.io/) - 一个发现所有 eBPF 基础知识的门户，包括主要相关项目和社区资源的列表.
- [Cilium's BPF and XDP Reference Guide](http://docs.cilium.io/en/latest/bpf/) - 关于 eBPF 的大多数特性和方面的深入文档.

### Kernel Documentation

- [BPF Documentation](https://www.kernel.org/doc/html/latest/bpf/index.html) - Index for BPF-related documentation coming with the Linux kernel.
- [linux/Documentation/networking/filter.rst](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/networking/filter.rst) - eBPF 规范（有些过时；信息应该仍然有效，但并不详尽）.
- [BPF Design Q&A](https://www.kernel.org/doc/html/latest/bpf/bpf_design_QA.html) - 关于 BPF 基础架构背后决策的常见问题.
- [HOWTO interact with BPF subsystem](https://www.kernel.org/doc/html/latest/bpf/bpf_devel_QA.html) - 关于为 eBPF 开发做贡献的常见问题.

### Manual Pages

- [`bpf(2)`](http://man7.org/linux/man-pages/man2/bpf.2.html) - 关于 `bpf()` 系统调用的手册页，用于从用户空间管理 BPF 程序和映射.
- [`tc-bpf(8)`](http://man7.org/linux/man-pages/man8/tc-bpf.8.html) - 关于在 tc 中使用 BPF 的手册页，包括示例命令和代码示例.
- [`bpf-helpers(7)` man page](http://man7.org/linux/man-pages/man7/bpf-helpers.7.html) - 描述构成 BPF 标准库的内核辅助函数.

### Other

- [IO Visor's Unofficial eBPF spec](https://github.com/iovisor/bpf-docs/blob/master/eBPF.md) - eBPF 语法和操作代码摘要.
- [Jesper Dangaard Brouer's documentation](https://prototype-kernel.readthedocs.io/en/latest/bpf/index.html) - 正在进行中，欢迎贡献.
- 从大卫米勒的电子邮件到 [xdp-newbies](http://vger.kernel.org/vger-lists.html#xdp-newbies) 邮件列表：

  - [bpf.h and you...](https://www.spinics.net/lists/xdp-newbies/msg00179.html)
  - [Contextually speaking...](https://www.spinics.net/lists/xdp-newbies/msg00181.html)
  - [BPF Verifier Overview](https://www.spinics.net/lists/xdp-newbies/msg00185.html)

- [List of BPF features per kernel version](https://github.com/iovisor/bcc/blob/master/docs/kernel-versions.md)

## Articles and Presentations

### Generic eBPF Presentations and Articles

如果您是 eBPF 的新手，您可能想尝试本节中描述为“介绍”的链接.

- [A brief introduction to XDP and eBPF](https://blogs.igalia.com/dpino/2019/01/07/introduction-to-xdp-and-ebpf/) - 易于理解的介绍，提供有关 eBPF 功能的背景、历史和详细信息.
- An eBPF Overview - Adrian Ratiu 的博客系列，涵盖 eBPF 基础设施的许多方面：

  - [Part 1: Introduction](https://www.collabora.com/news-and-blog/blog/2019/04/05/an-ebpf-overview-part-1-introduction/)
  - [Part 2: Machine & Bytecode](https://www.collabora.com/news-and-blog/blog/2019/04/15/an-ebpf-overview-part-2-machine-and-bytecode/)

- [Ferris Ellis's blog posts about eBPF](https://ferrisellis.com/tags/ebpf/) - 他们有一些关于 eBPF 的帖子：
  - [Part 1: Past, Present, and Future](https://ferrisellis.com/content/ebpf_past_present_future/)
  - [Part 2: Syscall and Map Types](https://ferrisellis.com/content/ebpf_syscall_and_maps/)
- [A BPF reference guide](https://github.com/iovisor/bcc/blob/master/docs/reference_guide.md) - 关于 BPF C 和 bcc Python 助手，来自 bcc 存储库.
- [Making the Kernel's Networking Data Path Programmable with BPF and XDP](http://schd.ws/hosted_files/ossna2017/da/BPFandXDP.pdf) - 一组幻灯片，涵盖有关 eBPF 和 XDP 的所有基础知识（主要用于网络处理）.
- [The BSD Packet Filter](https://speakerdeck.com/tuxology/the-bsd-packet-filter) - 介绍主要涵盖跟踪方面.
- [BPF: tracing and more](http://www.slideshare.net/brendangregg/bpf-tracing-and-more) - 介绍主要涵盖跟踪方面.
- [Linux BPF Superpowers](http://www.slideshare.net/brendangregg/linux-bpf-superpowers) - 介绍主要涵盖跟踪方面，第一部分是火焰图.
- [IO Visor](https://www.socallinuxexpo.org/sites/default/files/presentations/Room%20211%20-%20IOVisor%20-%20SCaLE%2014x.pdf) - 还介绍了 [IO Visor project](https://www.iovisor.org/).
- [BPF -- in-kernel virtual machine](http://vger.kernel.org/netconf2015Starovoitov-bpf_collabsummit_2015feb20.pdf) - eBPF 作者的介绍.
- [Extending extended BPF](https://lwn.net/Articles/603983/) - 2014 年的一篇关于 BPF 开发的博客文章，并通过将 eBPF 程序附加到套接字来使用有状态套接字过滤的示例演示可以用它做什么.
- Greg Marsden 制作了一些关于 eBPF 的文档：
  - [A Tour of Program Types](https://blogs.oracle.com/linux/notes-on-bpf-1) - 对 BPF 程序类型的所有现有钩子及其兴趣的描述.
  - [BPF helper functions](https://blogs.oracle.com/linux/notes-on-bpf-2) - 回顾可以从 eBPF 程序中调用的内核函数.
  - [Communicating with Userspace](https://blogs.oracle.com/linux/notes-on-bpf-3) - BPF 如何与用户空间通信 - BPF 映射、性能事件、bpf_trace_printk.
  - [Building BPF Programs](https://blogs.oracle.com/linux/notes-on-bpf-4) - 设置环境以构建 BPF 程序.
  - [The BPF Bytecode and the BPF Verifier](https://blogs.oracle.com/linux/notes-on-bpf-5) - BPF 如何确保程序安全？
  - [Using BPF to do Packet Transformation](https://blogs.oracle.com/linux/notes-on-bpf-6) - 一种关于数据包转换的 eBPF 用法.
- [Linux Kernel Observability through eBPF](https://sematext.com/blog/linux-kernel-observability-ebpf/) - 一篇博文，涵盖 eBPF 的基础知识以及 Go 中的代码示例，介绍如何构建最小的 eBPF 程序并将其加载到内核中.
- [eBPF - From a Programmer's Perspective](https://www.researchgate.net/publication/349173667_eBPF_-_From_a_Programmer's_Perspective) - 一篇简短的论文，描述了 eBPF 的基础知识以及如何开始编写 eBPF 程序.
- [Cloudflare's blog posts on eBPF](https://blog.cloudflare.com/tag/ebpf/) - 关于网络用例和 eBPF 低级方面的不同博客文章.
- [Linux Extended BPF (eBPF) Tracing Tools](https://www.brendangregg.com/ebpf.html)  - 深入收集有关使用 eBPF 的性能分析工具示例的信息. 页面末尾还包含有关其他资源的部分.
- [Beginner's guide to eBPF](https://github.com/lizrice/ebpf-beginners) - 一组实时编码讲座和随附的代码示例，介绍使用各种库和程序类型的 eBPF 编程.

### BPF Internals

- Daniel Borkmann 做了几篇关于 eBPF 内部的演讲和论文，特别是关于它与 tc 的使用.

  - [eBPF and XDP walkthrough and recent (2017) updates](https://fosdem.org/2017/schedule/event/ebpf_xdp/)
  - [Advanced programmability and recent updates with tc's cls_bpf](http://netdevconf.org/1.2/session.html?daniel-borkmann) - 有关 eBPF 的详细信息，它用于隧道和封装、直接数据包访问等.
  - [cls_bpf/eBPF updates since netdev 1.1](http://netdevconf.org/1.2/slides/oct5/07_tcws_daniel_borkmann_2016_tcws.pdf) - 部分 [this tc workshop](http://netdevconf.org/1.2/session.html?jamal-tc-workshop).
  - [On getting tc classifier fully programmable with cls_bpf](http://www.netdevconf.org/1.1/proceedings/slides/borkmann-tc-classifier-cls-bpf.pdf)  - eBPF 简介，包括几个功能（地图管理、尾调用、验证器）. 全文 [is also available here](http://www.netdevconf.org/1.1/proceedings/papers/On-getting-tc-classifier-fully-programmable-with-cls-bpf.pdf).
  - [Linux tc and eBPF](https://archive.fosdem.org/2016/schedule/event/ebpf/attachments/slides/1159/export/events/attachments/ebpf/slides/1159/ebpf.pdf)

- [IO Visor blog](https://www.iovisor.org/resources/blog)
- [Linux Networking Explained](http://www.slideshare.net/ThomasGraf5/linux-networking-explained) - Linux 网络内部结构，其中一部分是关于 eBPF.

### Kernel Tracing

- [Full-system dynamic tracing on Linux using eBPF and bpftrace](https://www.joyfulbikeshedding.com/blog/2019-01-31-full-system-dynamic-tracing-on-linux-using-ebpf-and-bpftrace.html) - 详细介绍使用 eBPF 进行跟踪，从列出可用的跟踪点到运行 bpftrace 程序.
- [Meet-cute between eBPF and Kernel Tracing](http://www.slideshare.net/vh21/meet-cutebetweenebpfandtracing) - Kprobes、uprobes、ftrace.
- [Linux Kernel Tracing](http://www.slideshare.net/vh21/linux-kernel-tracing) - Systemtap、Kernelshark、trace-cmd、LTTng、perf-tool、ftrace、hist-trigger、perf、函数跟踪器、tracepoint、kprobe/uprobe 等等.
- Brendan Gregg 的博客，尤其是 [Linux BPF Superpowers](http://www.brendangregg.com/blog/2016-03-05/linux-bpf-superpowers.html) 文章.

### XDP

- [The eXpress Data Path](https://blogs.igalia.com/dpino/2019/01/10/the-express-data-path/) - 一个非常容易理解的 XDP 介绍，提供示例代码来展示如何处理数据包.
- 技术论文中的所有 XDP 详细信息： [The eXpress Data Path: Fast Programmable Packet Processing in the Operating System Kernel](https://github.com/tohojo/xdp-paper)，作者 Toke Høiland-Jørgensen、Jesper Dangaard Brouer、Daniel Borkmann、John Fastabend、Tom Herbert、David Ahern 和 David Miller，他们都是 eBPF 和 XDP 的重要贡献者.
- [Work-in-progress documentation for XDP](https://prototype-kernel.readthedocs.io/en/latest/networking/XDP/index.html)
- [BPF and XDP Reference Guide](http://docs.cilium.io/en/latest/bpf/) - Cilium 项目的指南.
- [XDP Project overview](https://www.iovisor.org/technology/xdp)
- [eXpress Data Path (XDP)](https://github.com/iovisor/bpf-docs/raw/master/Express_Data_Path.pdf) - 关于 XDP 的第一次演示.
- [BoF - What Can BPF Do For You?](https://events.linuxfoundation.org/sites/events/files/slides/iovisor-lc-bof-2016.pdf)
- [eXpress Data Path](http://www.slideshare.net/IOVisor/express-data-path-linux-meetup-santa-clara-july-2016) - 包含使用 mlx4 驱动程序获得的一些基准测试结果.
- Jesper Dangaard Brouer 有几组幻灯片描述了 XDP 的内部结构：

  - [XDP − eXpress Data Path, Intro and future use-cases](http://people.netfilter.org/hawk/presentations/xdp2016/xdp_intro_and_use_cases_sep2016.pdf) - Linux Kernel's fight against DPDK. Future plans (as of this writing) for XDP and comparison with DPDK.
  - [Network Performance Workshop](http://netdevconf.org/1.2/session.html?jesper-performance-workshop) - 关于 XDP 内部结构和预期演变的附加提示.
  - [XDP – eXpress Data Path, Used for DDoS protection](http://people.netfilter.org/hawk/presentations/OpenSourceDays2017/XDP_DDoS_protecting_osd2017.pdf) - 有关 XDP 的详细信息和用例，带有基准测试结果和代码片段，用于基准测试以及使用 eBPF/XDP（基于 IP 黑名单方案）进行基本 DDoS 保护.
  - [Memory vs. Networking, Provoking and fixing memory bottlenecks](http://people.netfilter.org/hawk/presentations/MM-summit2017/MM-summit2017-JesperBrouer.pdf) - 有关 XDP 开发人员当前面临的内存问题的高级详细信息.
  - [XDP for the Rest of Us](http://netdevconf.org/2.1/session.html?gospodarek)  - 如何开始为普通人使用 eBPF 和 XDP. 也由 Julia Evans 总结 [her blog](http://jvns.ca/blog/2017/04/07/xdp-bpf-tutorial/).
  - [XDP now with REDIRECT](http://people.netfilter.org/hawk/presentations/LLC2018/XDP_LLC2018_redirect.pdf) - 更新 XDP，特别是重定向操作.

- [XDP workshop -- Introduction, experience, and future development (Video)](http://netdevconf.org/1.2/session.html?herbert-xdp-workshop)
- [High Speed Packet Filtering on Linux](https://cdn.shopify.com/s/files/1/0177/9886/files/phv2017-gbertin.pdf) - 关于 Linux 上的包过滤、DDoS 保护、内核中的包处理、内核绕过、XDP 和 eBPF.
- [How to drop 10 million packets per second](https://blog.cloudflare.com/how-to-drop-10-million-packets/) - Cloudflare 的博客文章谈论他们转向使用 XDP 进行数据包过滤.

### AF_XDP

- [AF_XDP](https://www.kernel.org/doc/html/latest/networking/af_xdp.html) - 关于 AF_XDP 地址系列的内核文档.
- [Fast Packet Processing in Linux with AF_XDP](https://archive.fosdem.org/2018/schedule/event/af_xdp/)

### bpfilter

- [Why is the kernel community replacing iptables with BPF?](https://cilium.io/blog/2018/04/17/why-is-the-kernel-community-replacing-iptables/) - Cilium 发表的一篇关于 eBPF 和 bpfilter 背后动机的博客文章，其中包含几个示例以及使用 eBPF 和 bpfilter 的其他项目的链接.
- [bpfilter: Linux firewall with eBPF sauce](https://qmo.fr/docs/talk_20180316_frnog_bpfilter.pdf) - 来自 Quentin Monnet 演讲的幻灯片，具有 eBPF 的背景并将 bpfilter 与 iptables 进行比较.

### BTF

- [BPF Type Format (BTF)](https://www.kernel.org/doc/html/latest/bpf/btf.html) - 关于 BTF 的内核文档，解释如何使用它.
- [Enhancing the Linux kernel with BTF type information](https://facebookmicrosites.github.io/bpf/blog/2018/11/14/btf-enhancement.html) - 描述使用 BTF 为 BPF 程序提供调试信息所做的工作.

### cBPF

- [The BSD Packet Filter: A New Architecture for User-level Packet Capture](http://www.tcpdump.org/papers/bpf-usenix93.pdf) - 关于（经典）BPF 的原始论文.
- [The FreeBSD manual page about BPF](https://www.freebsd.org/cgi/man.cgi?query=bpf&sektion=4)
- [Linux' packet mmap(2), BPF, and Netsniff-NG](http://borkmann.ch/talks/2013_devconf.pdf)
- [tc and cls bpf: lightweight packet classifying with BPF](http://borkmann.ch/talks/2014_devconf.pdf)
- [Introducing Cloudflare's BPF Tools](https://blog.cloudflare.com/introducing-the-bpf-tools/) - 将 BPF 字节码与 iptables 的 `xt_bpf` 模块一起使用.
- [Libpcap filters syntax](http://biot.com/capstats/bpf.html)

### Hardware Offload

- [eBPF/XDP hardware offload to SmartNICs](http://netdevconf.org/1.2/session.html?jakub-kicinski) - Netronome 引入的使用 TC 或 XDP（Linux 内核 4.9+）的 eBPF 的硬件卸载.
- [Comprehensive XDP offload---Handling the edge cases](https://www.netdevconf.org/2.2/session.html?viljoen-xdpoffload-talk) - 关于上述主题的更新.
- [hBPF - eBPF in hardware](https://github.com/rprinz08/hBPF) - 为 FPGA 编写的 eBPF CPU.
- [OpenCSD eBPF SSD offloading](https://github.com/Dantali0n/qemu-csd) - 具有 FUSE LFS 文件系统的计算存储模拟 (QEMU) 平台，用于分区命名空间 NVMe SSD，使用 uBPF 进行计算内核卸载，所有这些都在用户空间中.

## Tutorials

- [bcc Reference Guide](https://github.com/iovisor/bcc/blob/master/docs/reference_guide.md) - 开始使用 bcc 和 eBPF 的许多增量步骤，主要集中在跟踪和监控上.
- [bcc Python Developer Tutorial](https://github.com/iovisor/bcc/blob/master/docs/tutorial_bcc_python_developer.md) - 带有密件抄送，但针对 17 个“课程”中的 Python 位.
- [Building BPF applications with libbpf-bootstrap](https://nakryiko.com/posts/libbpf-bootstrap/) - 帮助生成最小或高级模板来引导您自己的应用程序（地图和程序的内核端和用户空间管理），具有 CO-RE、全局变量和环形缓冲区等功能.
- [How I ended up writing opensnoop in pure C using eBPF](https://bolinfest.github.io/opensnoop-native/) - 如何编写 eBPF 程序的全面演练，首先仅使用 bpf() 系统调用，然后使用 libbpf 库，并带有可重现的代码示例.
- [Linux Tracing Workshops Materials](https://github.com/goldshtn/linux-tracing-workshop) - 涉及使用几个 BPF 工具进行跟踪.
- [Tracing a packet journey using Linux tracepoints, perf and eBPF](https://blog.yadutaf.fr/2017/07/28/tracing-a-packet-journey-using-linux-tracepoints-perf-ebpf/) - 使用 perf 和 bcc 程序对 ping 请求和回复进行故障排除.
- [Open NFP platform](https://open-nfp.org/dataplanes-ebpf/technical-papers/) - 由 Netronome 运营：一些与网络相关的 eBPF 用例教程，包括 eBPF 卸载入门指南.
- [XDP for the Rest of Us](http://netdevconf.org/2.1/session.html?gospodarek) - 第一版的 XDP 入门研讨会.
- [XDP for the Rest of Us](https://www.netdevconf.org/2.2/session.html?gospodarek-xdp-workshop) - 第二版，新内容.
- [Load XDP programs using the ip (iproute2) command](https://medium.com/@fntlnz/load-xdp-programs-using-the-ip-iproute2-command-502043898263)
- [XDP Hands-On Tutorial](https://github.com/xdp-project/xdp-tutorial) - 学习如何使用 XDP 处理数据包的渐进式（三个难度级别）教程.
- [All your tracing are belong to BPF](https://www.trailofbits.com/post/all-your-tracing-are-belong-to-bpf) - 将 C++ 应用程序中的跟踪功能与 LLVM 库集成的分步演练.

## Examples

- [linux/samples/bpf/](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/samples/bpf) - 在内核树中：一些示例 eBPF 程序.
- [linux/tools/testing/selftests/bpf](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/tools/testing/selftests/bpf) - 在内核树中：Linux BPF 自测，带有许多 eBPF 程序.
- [prototype-kernel/kernel/samples/bpf](https://github.com/netoptimizer/prototype-kernel/tree/master/kernel/samples/bpf) - Jesper Dangaard Brouer 的原型内核存储库包含一些可以在内核基础架构之外编译的附加示例.
- [iproute2/examples/bpf/](https://git.kernel.org/pub/scm/network/iproute2/iproute2-next.git/tree/examples/bpf) - 一些连接到 TC 接口的网络程序.
- [Netronome sample network applications](https://github.com/Netronome/bpf-samples/) - 提供基本但完整的 eBPF 应用程序示例，也与硬件卸载兼容.
- [bcc/examples](https://github.com/iovisor/bcc/tree/master/examples) - 与密件抄送工具一起提供的示例，主要是关于跟踪.
- [bcc/tools](https://github.com/iovisor/bcc/tree/master/tools)  - 这些工具本身可以被视为 BPF 程序的示例用例，主要用于跟踪和监控.  bcc 工具已被打包用于某些 Linux 发行版.
- [MPLSinIP sample](https://github.com/fzakaria/eBPF-mpls-encap-decap)  - 一个备受评论的示例，展示了如何在 IP 中封装和解封装 MPLS. 该代码是为那些刚接触 BPF 开发的人注释的.
- [ebpf-samples](https://github.com/vbpf/ebpf-samples) - 从多个项目收集的已编译（作为 ELF 目标文件）样本的集合，主要用作用户空间验证者的测试用例.
- [ebpf-kill-example](https://github.com/niclashedam/ebpf-kill-example) - 一个完整记录和测试的 eBPF 探针示例，记录所有强制终止并在用户空间中打印出来.
- [redbpf examples](https://github.com/foniod/redbpf/tree/main/examples) - 使用 RedBPF 在 Rust 中编写 eBPF 程序的示例程序.

## eBPF Workflow: Tools and Utilities

### bcc

- [bcc](https://github.com/iovisor/bcc/)  - 框架和工具集 - 处理 BPF 程序的一种方法，特别是用于跟踪和监控. 还包括一些可以帮助检查系统上的地图或程序的实用程序.
- [Lua front-end for BCC](https://github.com/iovisor/bcc/tree/master/src/lua) - C 的另一种替代方法，甚至是 bcc 中使用的大多数 Python 代码的替代方法.

### iproute2

- [iproute2](https://git.kernel.org/pub/scm/network/iproute2/iproute2.git)  - 包含 Linux 网络管理工具的软件包. 特别是，它包含用于管理 eBPF 过滤器和操作的 `tc` 和用于管理 XDP 程序的 `ip`. 大多数与 BPF 相关的代码都在 lib/bpf.c 中.
- [iproute2-next](https://git.kernel.org/pub/scm/network/iproute2/iproute2-next.git) - 开发树，与 net-next 同步.

### LLVM

- [LLVM](https://llvm.org/)  - 包含 eBPF 工作流中使用的几个工具.  Ubuntu/Debian 最新版本的快照可以从 [here](http://apt.llvm.org/).

   - clang 用于将 C 编译为 ELF 格式的 eBPF 目标文件（clang v3.7.1+）.  BPF 后端添加了 [this commit](https://reviews.llvm.org/D6494).
  - llvm-objdump 用于以人类可读的格式转储目标文件的内容，可能带有初始 C 源代码 (llvm-objdump v4.0+).
  - llvm-mc 用于从 LLVM 中间表示编译为 eBPF 目标文件，这样就可以从 C 编译到 eBPF 程序集，修改程序集，然后编译为 ELF 文件.

### libbpf

- [libbpf](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git/tree/tools/lib/bpf)  - AC 库用于处理 BPF 对象（程序和映射），以及操作包含它们的 ELF 对象文件. 它随内核一起提供，并且 [mirrored on GitHub](https://github.com/libbpf/libbpf).
- [libbpf-bootstrap](https://github.com/libbpf/libbpf-bootstrap) - 使用 libbpf 和 BPF CO-RE 开发 BPF 应用程序的脚手架.

### Aya

- [aya](https://github.com/aya-rs/aya)  - 一个纯 Rust 库，用于编写、加载和管理 eBPF 对象，专注于开发人员体验和可操作性. 它支持用 Rust 编写 eBPF 程序，并通过 crates.io 分发库代码以在 eBPF 程序之间共享.  Aya 不依赖于 libbpf.
- [aya-template](https://github.com/aya-rs/aya-template) - 用于在 Aya 中编写 BPF 应用程序的模板，可与 [`cargo generate`](https://github.com/cargo-generate/cargo-generate).

### oxidebpf

- [oxidebpf](https://github.com/redcanaryco/oxidebpf)  - 用于管理 eBPF 程序的纯 Rust 库，专为安全用例而设计. 该功能集比其他库更受限制，但强调跨广泛内核的稳定性和向后兼容的 compile-once-run-most-places.

### bpftool and Other Tools from the Kernel Tree

- [bpftool](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpftool) - 内核树中还有一些其他工具，位于 [linux/tools/net/](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/tools/net?h=v4.14) 对于 4.15 之前的版本，或 [linux/tools/bpf/](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git/tree/tools/bpf) 之后：

  - [`bpftool`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpftool) - 一个通用实用程序，可用于与来自用户空间的 eBPF 程序和地图交互，例如显示、转储、加载、反汇编、固定程序，或显示、创建、固定、更新、删除地图，或附加和分离程序到 cgroups.
  - [`bpf_asm`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpf_asm.c) - 一个最小的 cBPF 汇编器.
  - [`bpf_dbg`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpf_dbg.c) - 用于 cBPF 程序的小型调试器.
  - [`bpf_jit_disasm`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpf_jit_disasm.c) - 两种 BPF 风格的反汇编器，对 JIT 调试非常有用.

### User Space eBPF

- [uBPF](https://github.com/iovisor/ubpf/) - 用 C 编写.包含一个解释器、一个用于 x86_64 架构的 JIT 编译器、一个汇编器和一个反汇编器.
- [A generic implementation](https://github.com/YutaroHayakawa/generic-ebpf)  - 支持 FreeBSD 内核、FreeBSD 用户空间、Linux 内核、Linux 用户空间和 macOS 用户空间. 用于 [VALE software switch](https://www.unix.com/man-page/freebsd/4/vale/)'s [BPF extension module](https://github.com/YutaroHayakawa/vale-bpf).
- [rbpf](https://github.com/qmonnet/rbpf)  - 用 Rust 编写.  Linux、macOS 和 Windows 的解释器，以及 Linux 下 x86_64 的 JIT 编译器.
- [PREVAIL](https://github.com/vbpf/ebpf-verifier) - eBPF 的用户空间验证器 [using an abstract interpretation layer](https://elazarg.github.io/pldi19main-final.pdf)，支持循环.
- [oster](https://github.com/grantseltzer/oster)  - 用 Go 编写. 通过将 eBPF 附加到 uprobes 来跟踪 Go 程序执行的工具.
- [wachy](https://rubrikinc.github.io/wachy/)  - 一个跟踪分析器，旨在使基于 eBPF uprobe 的调试更易于使用. 这是通过在源代码旁边的 UI 中显示跟踪并允许交互式深入分析来完成的.

### Testing in Virtual Environments

- [A Vagrant setup](https://github.com/iovisor/xdp-vagrant)  - 轻松测试 XDP. 现在通用 XDP（独立于驱动程序，主要用于测试）的存在不太有用.
- [bcc in a Docker container](https://github.com/zlim/bcc-docker)

## Projects Related to eBPF

- P4 与 eBPF 有一些交互：

  - [P4 on the Edge](https://schd.ws/hosted_files/2016p4workshop/1d/Intel%20Fastabend-P4%20on%20the%20Edge.pdf) - 使用 eBPF 的 P4 创建高性能可编程交换机.
  - [OvS Orbit episode (#11), called P4 on the Edge](https://ovsorbit.org/#e11)  - 与前一项有关.  Open vSwitch 的核心维护者之一 Ben Pfaff 对 John Fastabend 的音频采访.
  - [P4, EBPF and Linux TC Offload](https://open-nfp.org/m/documents/Open_NFP_P4_EBPF_Linux_TC_Offload_FINAL_5JHLETS.pdf) - P4 与 Netronome 的 NFP（网络流处理器）架构上的 eBPF 硬件卸载相关的一些元素.
  - [Old documentation for P4 usage with eBPF](https://github.com/iovisor/bcc/tree/master/src/cc/frontends/p4)  - 来自密件抄送库； 已被下面链接的 P4_16 后端弃用.
  - [P4_16 backend for eBPF](https://github.com/p4lang/p4c/blob/master/backends/ebpf/README.md)

- [Cilium](https://cilium.io/) 项目 （[GitHub repository](https://github.com/cilium/cilium) ) 是一项依靠 BPF 和 XDP 提供“基于动态生成的 eBPF 程序的容器的快速内核网络和安全策略实施”的技术. 许多可用的演示文稿（有重叠）：

  - [Cilium: Networking & Security for Containers with BPF & XDP](http://www.slideshare.net/ThomasGraf5/clium-container-networking-with-bpf-xdp) - 还具有负载均衡器用例
  - [Cilium: Networking & Security for Containers with BPF & XDP](http://www.slideshare.net/Docker/cilium-bpf-xdp-for-containers-66969823) - [video](https://www.youtube.com/watch?v=TnJF7ht3ZYc&list=PLkA60AVN3hh8oPas3cq2VA9xB7WazcIgs)
  - [Cilium: Fast IPv6 container Networking with BPF and XDP](http://www.slideshare.net/ThomasGraf5/cilium-fast-ipv6-container-networking-with-bpf-and-xdp)
  - [Cilium: BPF & XDP for containers](https://fosdem.org/2017/schedule/event/cilium/)
  - [OvS Orbit episode (#4)](https://ovsorbit.benpfaff.org/) - Ben Pfaff 对 Thomas Graf 的采访.
  - [A generic introduction to Cilium](https://opensource.googleblog.com/2016/11/cilium-networking-and-security.html)
  - [A podcast interviewing Thomas Graf](http://blog.ipspace.net/2016/10/fast-linux-packet-forwarding-with.html) - Ivan Pepelnjak 在 2016 年 10 月就 eBPF、P4、XDP 和 Cilium 采访 Thomas.

- Open vSwitch（OvS）及其相关项目 Open Virtual Network（OVN，一种开源网络虚拟化解决方案）正在考虑在各个层面使用 eBPF：

  - [Offloading OVS Flow Processing using eBPF](http://openvswitch.org/support/ovscon2016/7/1120-tu.pdf)
  - [Coupling the Flexibility of OVN with the Efficiency of IOVisor](http://openvswitch.org/support/ovscon2016/7/1245-bertrone.pdf)

- [Katran](https://code.fb.com/open-source/open-sourcing-katran-a-scalable-network-load-balancer/) - 基于 XDP 的第 4 层负载均衡器，由 Facebook 开源.
- [XDP in practice: integrating XDP in our DDoS mitigation pipeline](http://netdevconf.org/2.1/session.html?bertin) - 在 Cloudflare 使用 XDP 防御 DDoS.
- [Droplet: DDoS countermeasures powered by BPF + XDP](http://netdevconf.org/2.1/session.html?zhou) - 在 Facebook 使用 XDP 防御 DDoS.
- [DPDK has a poll-mode driver (PMD) based on AF_XDP](https://dpdkuserspace2018.sched.com/event/G45Z/dpdk-pmd-for-afxdp)
- [CETH for XDP](http://www.slideshare.net/IOVisor/ceth-for-xdp-linux-meetup-santa-clara-july-2016) - 用于更快网络 I/O 的通用以太网驱动程序框架，这是 Mellanox 发起的一项技术.
- Suricata，一个开源入侵检测系统， [relies on eBPF components](https://www.stamus-networks.com/2016/09/28/suricata-bypass-feature/) 因其“捕获绕过”功能：

  - ["eBPF and XDP" section of Suricata documentation](http://suricata.readthedocs.io/en/latest/capture-hardware/ebpf-xdp.html?highlight=XDP#ebpf-and-xdp)
  - [SEPTun-Mark-II](https://github.com/pevma/SEPTun-Mark-II) - 极限性能调优指南 - Mark II.
  - [A blog post introducing the feature](https://www.stamus-networks.com/2016/09/28/suricata-bypass-feature/)
  - [The adventures of a Suricate in eBPF land](http://netdevconf.org/1.2/slides/oct6/10_suricata_ebpf.pdf)
  - [eBPF and XDP seen from the eyes of a meerkat](https://www.slideshare.net/ennael/kernel-recipes-2017-ebpf-and-xdp-eric-leblond)

- [InKeV: In-Kernel Distributed Network Virtualization for DCN](https://github.com/iovisor/bpf-docs/blob/master/university/sigcomm-ccr-InKev-2016.pdf)
- [gobpf - utilizing eBPF from Go](https://fosdem.org/2017/schedule/event/go_bpf/) - 从 Go 创建、加载和使用 eBPF 程序的库.
- [ply](https://wkz.github.io/ply/) - A small but flexible open source dynamic tracer for Linux, with features similar to the bcc tools, but with a simpler language inspired by awk and DTrace.
- [bpftrace](https://bpftrace.org/)  - 使用自己的高级跟踪语言进行跟踪的工具. 它足够灵活，可以设想为 DTrace 和 SystemTap 的 Linux 替代品.
  - [bpftrace Cheat Sheet](https://www.brendangregg.com/BPF/bpftrace-cheat-sheet.html)  - 在 bpftrace 中编程的总结和备忘单. 包含有关语法、探测类型、变量和函数的信息.
- [kubectl trace](https://github.com/iovisor/kubectl-trace) - 用于在 Kubernetes 集群中执行 bpftrace 程序的 kubectl 插件.
- [bpfd](https://github.com/genuinetools/bpfd)  - 在 Linux 上作为守护进程运行带有规则的 BPF 程序的框架. 容器感知.
- [BPFd](https://github.com/joelagnel/bpfd) - 一个独特的 BPF 守护进程，试图利用 bcc 工具的灵活性来跟踪和调试远程目标，特别是运行 Android 的设备.
- [adeb](https://github.com/joelagnel/adeb) - 一个 Linux shell 环境，用于在带有 BPFd 的 Android 上使用跟踪工具.
- [greggd](https://github.com/olcf/greggd) - 系统守护进程将 eBPF 程序编译并加载到内核中，并将程序输出转发到套接字以进行度量聚合.
- [FUSE](https://events.linuxfoundation.org/wp-content/uploads/2017/11/When-eBPF-Meets-FUSE-Improving-Performance-of-User-File-Systems-Ashish-Bijlani-Georgia-Tech.pdf) - 考虑使用 eBPF.
- [DEEP-mon](https://www.slideshare.net/necstlab/deepmon-dynamic-and-energy-efficient-power-monitoring-for-containerbased-infrastructures) - 帮助测量服务器的功耗，并使用 eBPF 程序进行内核内数据聚合.
- [upf-bpf](https://github.com/navarrothiago/upf-bpf) - 基于 XDP 的 5G UPF 内核解决方案.
- [redbpf](https://github.com/foniod/redbpf) - 用 Rust 高效编写 eBPF 代码的工具和框架.
- [pixie](https://github.com/pixie-io/pixie)  - 使用 eBPF 的 Kubernetes 可观察性. 功能包括协议跟踪、应用程序分析和对分布式 bpftrace 部署的支持.
- [Project Calico](https://projectcalico.docs.tigera.io/about/about-calico)  - Calico 是一个开源网络和网络安全解决方案，适用于容器、虚拟机和基于本地主机的工作负载.  Calico 的 eBPF 数据平面通过丰富的网络安全策略模型提供低延迟、高吞吐量的数据平面.
  - [Enabling eBPF data plane with Calico](https://projectcalico.docs.tigera.io/maintenance/ebpf/enabling-bpf)
- [Falco](https://falco.org/) - 用作 Kubernetes 威胁检测引擎的云原生运行时安全项目.
- [Sysmon for Linux](https://github.com/Sysinternals/SysmonForLinux)  - 一个安全监控工具. 这取决于 [SysinternalsEBPF](https://github.com/Sysinternals/SysinternalsEBPF).
- [Red Canary Linux Agent](https://redcanary.com/blog/ebpf-for-security) - Red Canary 已经开始将 eBPF 整合到他们的 Linux 安全传感器中. 
- [Tracee](https://github.com/aquasecurity/tracee) - 适用于 Linux 的运行时安全和取证工具，它使用 eBPF 技术在运行时跟踪系统和应用程序，并分析收集的事件以检测可疑行为模式.
- [eBPF for Windows](https://github.com/microsoft/ebpf-for-windows) - 该项目正在进行中，允许在 Windows 上使用 Linux 生态系统中熟悉的现有 eBPF 工具链和 API.
- [redcanary-ebpf-sensor](https://github.com/redcanaryco/redcanary-ebpf-sensor)  - 一组从 Linux 内核收集安全相关事件数据的 BPF 程序.  BPF 程序被组合成一个单独的 ELF 文件，根据运行的操作系统和内核版本，可以有选择地从中加载各个探测器.
- [bpflock - Lock Linux machines](https://github.com/linux-lock/bpflock) - 一个 eBPF 驱动的安全工具，用于锁定和审计 Linux 机器.

## eBPF in Security

- [Embrace The Red: Offensive BPF!](https://embracethered.com/blog/tags/ebpf)  - 一系列关于 BPF 介绍的帖子，重点是攻击性设置，以及如何检测其滥用. 帖子包括关于 eBPF 的 rootkit 功能的讨论，或者关于不同用例需要哪种跟踪类型的讨论.
- [eBPF: Block Linux Fileless Payload "Malware" Execution with BPF LSM](https://djalal.opendz.org/post/ebpf-block-linux-fileless-payload-execution-with-bpf-lsm/) - 关于 BPF 如何帮助检测和阻止无文件恶意软件的博客文章.
- [Blackhat 2021: With Friends Like eBPF, Who Needs Enemies?](https://www.blackhat.com/us-21/briefings/schedule/#with-friends-like-ebpf-who-needs-enemies-23619)  - 谈论 eBPF rootkit 以及如何滥用 eBPF 的功能.  rootkit 也是 Defcon 演讲的对象， [eBPF, I thought we were friends !](https://defcon.org/html/defcon-29/dc-29-speakers.html#fournier).
- [ebpfkit](https://github.com/Gui774ume/ebpfkit) - 一个利用多个 eBPF 功能来实施攻击性安全技术的 rootkit.
- [ebpfkit-monitor](https://github.com/Gui774ume/ebpfkit-monitor)  - 在运行时静态分析 eBPF 字节码或监控可疑 eBPF 活动的实用程序. 它是专门为检测 ebpfkit 而设计的.
- [Bad BPF](https://github.com/pathtofile/bad-bpf) - 恶意 eBPF 程序的集合，它们利用 eBPF 在用户模式程序和内核之间读取和写入用户数据的能力.

## The Code

- [linux/include/linux/bpf.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/linux/bpf.h) - 和 [linux/include/uapi/bpf.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/uapi/linux/bpf.h)：与 eBPF 相关的定义，分别在内核中使用并与用户空间程序接口.
- [linux/include/linux/filter.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/linux/filter.h) - 和 [linux/include/uapi/filter.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/uapi/linux/filter.h)：用于运行 BPF 程序本身的信息.
- [linux/kernel/bpf/](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf)  - 该目录包含大部分与 BPF 相关的代码. 特别是，这些文件值得关注：

  - [`syscall.c`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf/syscall.c) - 系统调用允许的不同操作，例如程序加载或地图管理.
  - [`core.c`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf/core.c) - BPF 解释器.
  - [`verifier.c`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf/verifier.c) - BPF 验证器.

- [linux/net/core/filter.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/net/core/filter.c)  - 与网络相关的功能和 eBPF 助手（TC、XDP 等）； 还包含将 cBPF 字节码迁移到 eBPF 的代码（所有 cBPF 程序在最近的内核中都被转换为 eBPF）.
- [linux/kernel/trace/bpf_trace.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/kernel/trace/bpf_trace.c) - 与跟踪和监控相关的函数和 eBPF 助手（kprobes、tracepoints 等）.
- JIT 编译器在各自架构的目录下，例如文件 [linux/arch/x86/net/bpf_jit_comp.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/arch/x86/net/bpf_jit_comp.c) 对于 x86\. 用于硬件卸载的 JIT 编译器例外，位于其驱动程序中，例如 [linux/drivers/net/ethernet/netronome/nfp/bpf/jit.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/drivers/net/ethernet/netronome/nfp/bpf/jit.c) 用于 Netronome NFP.
- [linux/net/sched/](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/net/sched) - 特别是在文件 `act_bpf.c` (action) 和 `cls_bpf.c` (filter) 中：与 BPF 操作和 TC 过滤器相关的代码.
- [linux/kernel/seccomp.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/kernel/seccomp.c)
- [linux/net/core/dev.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/net/core/dev.c)  - 包含函数 `dev_change_xdp_fd()`，在从用户空间加载到内核后，通过 Netlink 命令调用该函数以将 XDP 程序挂接到设备. 该函数依次使用来自相关驱动程序的回调.

## Development and Community

- [The bpf-next tree](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/)  - BPF 补丁落在这棵树上. 它定期合并到 [net-next](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git)，它本身为每个版本合并到 Linus 的树.
- [Kernel documentation](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git/tree/Documentation/bpf/bpf_devel_QA.rst) - 关于对 BPF 的贡献.
- [The netdev mailing list](http://lists.openwall.net/netdev/)  - Linux 内核网络堆栈开发的邮件列表. 所有补丁都被发送到那里进行审查和包含.
- [XDP-newbies](http://vger.kernel.org/vger-lists.html#xdp-newbies) - 专门用于 XDP 编程的邮件列表（用于架构或寻求帮助）.
- [IO Visor mailing list](http://lists.iovisor.org/pipermail/iovisor-dev/) - BPF 是项目的核心，并在邮件列表中定期讨论.
- [@IOVisor Twitter account](https://twitter.com/IOVisor)
- [The XDP Collaboration Project](https://github.com/xdp-project/xdp-project) - 一个 GitHub 存储库，其中包含有关 XDP 未来发展的注释和想法.

## Other Lists of Resources on eBPF

- [IO Visor's bcc documentation](https://github.com/iovisor/bcc/tree/master/docs)
- [IO Visor's bpf-docs repository](https://github.com/iovisor/bpf-docs/)
- [Dive into BPF: A List of Reading Material](https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/)

## Acknowledgement

感谢 Quentin Monnet 和 Daniel Borkmann 的原创作品 [Dive into BPF: A List of Reading Material](https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/) 这成为了这份清单的基础.

## Contributing

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/zoidbergwill/awesome-ebpf/blob/master/contributing.md) 第一的.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，zoidbergwill 已放弃本作品的所有版权和相关或邻接权.
