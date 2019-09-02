<div class="github-widget" data-repo="zoidbergwill/awesome-ebpf"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome eBPF [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;与eBPF相关的精彩项目的精选列表.

 与_Berkeley Packet Filter_中一样，BPF是运行从用户空间传递的程序的内核虚拟机.  最初在BSD上实现，然后Linux，（现在遗留的）“经典BPF”或cBPF机器将与tcpdump等工具一起使用，用于过滤内核中的数据包，以避免无用的副本到用户空间.  最近，Linux中的BPF基础架构已经完全重新设计并赋予“扩展BPF”或eBPF生命，后者获得了新功能（安全和终止检查，程序的JIT编译，持久映射，标准库，硬件卸载）支持等）现在用于许多任务.  处理非常低级别的数据包（XDP），跟踪和监视系统上的事件，或者对cgroup实施访问控制只是eBPF带来性能，可编程性和灵活性的几个例子.

 &gt;注意：eBPF是一项令人兴奋的技术，其生态系统也在不断发展.  我们非常乐意帮助_you_保持这个令人敬畏的清单，并尽可能提高其信噪比.  请随时离开 [any feedback](https://github.com/zoidbergwill/awesome-ebpf/issues).



## Reference Documentation

### Cilium Guide

- [Cilum's BPF and XDP Reference Guide](http://docs.cilium.io/en/latest/bpf/) - 关于eBPF大多数功能的通用文档.

### Kernel Documentation

- [BPF Documentation](https://www.kernel.org/doc/html/latest/bpf/index.html) -  Linux内核附带的BPF相关文档的索引.
- [linux/Documentation/networking/filter.txt](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/networking/filter.txt) -  eBPF规范（有些过时;信息应该仍然有效，但不是详尽无遗的）.
- [BPF Design Q&A](https://www.kernel.org/doc/html/latest/bpf/bpf_design_QA.html) - 关于BPF基础设施背后的决策的常见问题.
- [HOWTO interact with BPF subsystem](https://www.kernel.org/doc/html/latest/bpf/bpf_devel_QA.html) - 关于促进eBPF发展的常见问题.

### Manual Pages

- [`bpf(2)`](http://man7.org/linux/man-pages/man2/bpf.2.html) - 关于`bpf（）`系统调用的手册页，用于管理来自用户空间的BPF程序和映射.
- [`tc-bpf(8)`](http://man7.org/linux/man-pages/man8/tc-bpf.8.html) - 关于将BPF与tc一起使用的手册页，包括示例命令和代码示例.
- [`bpf-helpers(7)` man page](http://man7.org/linux/man-pages/man7/bpf-helpers.7.html) - 描述形成BPF标准库的内核辅助函数.

### Other

- [IO Visor's Unofficial eBPF spec](https://github.com/iovisor/bpf-docs/blob/master/eBPF.md) -  eBPF语法和操作代码摘要.
- [Jesper Dangaard Brouer's documentation](https://prototype-kernel.readthedocs.io/en/latest/bpf/index.html) - 正在进行中，欢迎捐款.
- 从David Miller到电子邮件的电子邮件 [xdp-newbies](http://vger.kernel.org/vger-lists.html#xdp-newbies) 邮件列表：

  - [bpf.h and you...](https://www.spinics.net/lists/xdp-newbies/msg00179.html)
  - [Contextually speaking...](https://www.spinics.net/lists/xdp-newbies/msg00181.html)
  - [BPF Verifier Overview](https://www.spinics.net/lists/xdp-newbies/msg00185.html)

- [List of BPF features per kernel version](https://github.com/iovisor/bcc/blob/master/docs/kernel-versions.md)

## Articles and Presentations

### Generic eBPF presentations

如果您是eBPF的新手，您可能需要尝试本节中描述为“介绍”的链接.

- [A brief introduction to XDP and eBPF](https://blogs.igalia.com/dpino/2019/01/07/introduction-to-xdp-and-ebpf/) - 可访问的介绍，提供有关eBPF功能的背景，历史和详细信息.
-  eBPF概述 -  Adrian Ratiu的博客系列，涵盖了eBPF基础设施的许多方面：

  - [Part 1: Introduction](https://www.collabora.com/news-and-blog/blog/2019/04/05/an-ebpf-overview-part-1-introduction/)
  - [Part 2: Machine & Bytecode](https://www.collabora.com/news-and-blog/blog/2019/04/15/an-ebpf-overview-part-2-machine-and-bytecode/)

- [Ferris Ellis's blog posts about eBPF](https://ferrisellis.com/tags/ebpf/) - 他们有一些关于eBPF的帖子：
  - [Part 1: Past, Present, and Future](https://ferrisellis.com/content/ebpf_past_present_future/)
  - [Part 2: Syscall and Map Types](https://ferrisellis.com/content/ebpf_syscall_and_maps/)
- [A BPF reference guide](https://github.com/iovisor/bcc/blob/master/docs/reference_guide.md) - 关于BPF C和bcc Python助手，来自bcc存储库.
- [Making the Kernel's Networking Data Path Programmable with BPF and XDP](http://schd.ws/hosted_files/ossna2017/da/BPFandXDP.pdf) - 一组幻灯片，涵盖了有关eBPF和XDP的所有基础知识（主要用于网络处理）.
- [The BSD Packet Filter](https://speakerdeck.com/tuxology/the-bsd-packet-filter) - 介绍主要涉及追踪方面.
- [BPF: tracing and more](http://www.slideshare.net/brendangregg/bpf-tracing-and-more) - 介绍主要涉及追踪方面.
- [Linux BPF Superpowers](http://www.slideshare.net/brendangregg/linux-bpf-superpowers) - 介绍主要涉及跟踪方面，第一部分是火焰图.
- [IO Visor](https://www.socallinuxexpo.org/sites/default/files/presentations/Room%20211%20-%20IOVisor%20-%20SCaLE%2014x.pdf) - 还介绍 [IO Visor project](https://www.iovisor.org/).
- [BPF -- in-kernel virtual machine](https://events.linuxfoundation.org/sites/events/files/slides/bpf_collabsummit_2015feb20.pdf) -  eBPF作者的介绍.
- [Extending extended BPF](https://lwn.net/Articles/603983/) -  2014年关于BPF开发的博客文章，并通过将eBPF程序附加到套接字，使用状态套接字过滤示例演示了可以用它做什么.
- 格雷格马斯登制作了一些关于eBPF的文件：
  - [A Tour of Program Types](https://blogs.oracle.com/linux/notes-on-bpf-1) -  BPF程序类型的所有现有挂钩及其感兴趣的描述.
  - [BPF helper functions](https://blogs.oracle.com/linux/notes-on-bpf-2) - 回顾可以在eBPF程序中调用的内核函数.
  - [Communicating with Userspace](https://blogs.oracle.com/linux/notes-on-bpf-3) -  BPF如何与用户空间通信 -  BPF地图，perf事件，bpf_trace_printk.
  - [Building BPF Programs](https://blogs.oracle.com/linux/notes-on-bpf-4) - 设置环境以构建BPF程序.
  - [The BPF Bytecode and the BPF Verifier](https://blogs.oracle.com/linux/notes-on-bpf-5) -  BPF如何确保程序安全？
  - [Using BPF to do Packet Transformation](https://blogs.oracle.com/linux/notes-on-bpf-6) - 关于数据包转换的一个eBPF用法.
- [Linux Kernel Observability through eBPF](https://sematext.com/blog/linux-kernel-observability-ebpf/) - 一篇关于eBPF基础知识的博客文章以及关于如何构建内核并将最小eBPF程序加载到内核中的代码示例.

### BPF Internals

-  Daniel Borkmann做了几篇关于eBPF内部的演讲和论文，特别是关于它与tc的使用.

  - [eBPF and XDP walkthrough and recent (2017) updates](https://fosdem.org/2017/schedule/event/ebpf_xdp/)
  - [Advanced programmability and recent updates with tc's cls_bpf](http://netdevconf.org/1.2/session.html?daniel-borkmann) - 有关eBPF，其用于隧道和封装，直接数据包访问等的详细信息.
  - [cls_bpf/eBPF updates since netdev 1.1](http://netdevconf.org/1.2/slides/oct5/07_tcws_daniel_borkmann_2016_tcws.pdf) - 部分 [this tc workshop](http://netdevconf.org/1.2/session.html?jamal-tc-workshop).
  - [On getting tc classifier fully programmable with cls_bpf](http://www.netdevconf.org/1.1/proceedings/slides/borkmann-tc-classifier-cls-bpf.pdf)   -  eBPF简介，包括几个功能（地图管理，尾调用，验证器）.  全文 [is also available here](http://www.netdevconf.org/1.1/proceedings/papers/On-getting-tc-classifier-fully-programmable-with-cls-bpf.pdf).
  - [Linux tc and eBPF](https://archive.fosdem.org/2016/schedule/event/ebpf/attachments/slides/1159/export/events/attachments/ebpf/slides/1159/ebpf.pdf)

- [IO Visor blog](https://www.iovisor.org/resources/blog)
- [Linux Networking Explained](http://www.slideshare.net/ThomasGraf5/linux-networking-explained) -  Linux网络内部，部分关于eBPF.

### Kernel Tracing

- [Full-system dynamic tracing on Linux using eBPF and bpftrace](https://www.joyfulbikeshedding.com/blog/2019-01-31-full-system-dynamic-tracing-on-linux-using-ebpf-and-bpftrace.html) - 详细介绍了使用eBPF进行跟踪，从列出可用的跟踪点到运行bpftrace程序.
- [Meet-cute between eBPF and Kernel Tracing](http://www.slideshare.net/vh21/meet-cutebetweenebpfandtracing) -  Kprobes，uprobes，ftrace.
- [Linux Kernel Tracing](http://www.slideshare.net/vh21/linux-kernel-tracing) -  Systemtap，Kernelshark，trace-cmd，LTTng，perf-tool，ftrace，hist-trigger，perf，function tracer，tracepoint，kprobe / uprobe等.
-  Brendan Gregg的博客，特别是 [Linux BPF Superpowers](http://www.brendangregg.com/blog/2016-03-05/linux-bpf-superpowers.html) 文章.

### XDP

- [The eXpress Data Path](https://blogs.igalia.com/dpino/2019/01/10/the-express-data-path/) - 一个非常容易获得的XDP简介，提供示例代码以显示如何处理数据包.
- 技术论文中的所有XDP详细信息： [The eXpress Data Path: Fast Programmable Packet Processing in the Operating System Kernel](https://github.com/tohojo/xdp-paper)作者：TokeHøiland-Jørgensen，Jesper Dangaard Brouer，Daniel Borkmann，John Fastabend，Tom Herbert，David Ahern和David Miller，他们都是eBPF和XDP的重要贡献者.
- [Work-in-progress documentation for XDP](https://prototype-kernel.readthedocs.io/en/latest/networking/XDP/index.html)
- [BPF and XDP Reference Guide](http://docs.cilium.io/en/latest/bpf/) - 来自Cilium项目的指南.
- [XDP Project overview](https://www.iovisor.org/technology/xdp)
- [eXpress Data Path (XDP)](https://github.com/iovisor/bpf-docs/raw/master/Express_Data_Path.pdf) - 关于XDP的第一个演讲.
- [BoF - What Can BPF Do For You?](https://events.linuxfoundation.org/sites/events/files/slides/iovisor-lc-bof-2016.pdf)
- [eXpress Data Path](http://www.slideshare.net/IOVisor/express-data-path-linux-meetup-santa-clara-july-2016) - 包含使用mlx4驱动程序获得的一些基准测试结果.
-  Jesper Dangaard Brouer有几套幻灯片描述了XDP的内部结构：

  - [XDP − eXpress Data Path, Intro and future use-cases](http://people.netfilter.org/hawk/presentations/xdp2016/xdp_intro_and_use_cases_sep2016.pdf)   -  Linux Kernel与DPDK的斗争.  XDP的未来计划（撰写本文时）以及与DPDK的比较.
  - [Network Performance Workshop](http://netdevconf.org/1.2/session.html?jesper-performance-workshop) - 关于XDP内部和预期演变的其他提示.
  - [XDP – eXpress Data Path, Used for DDoS protection](http://people.netfilter.org/hawk/presentations/OpenSourceDays2017/XDP_DDoS_protecting_osd2017.pdf) - 有关XDP的详细信息和用例，基准测试结果以及用于基准测试的代码片段以及使用eBPF / XDP（基于IP黑名单方案）的基本DDoS保护.
  - [Memory vs. Networking, Provoking and fixing memory bottlenecks](http://people.netfilter.org/hawk/presentations/MM-summit2017/MM-summit2017-JesperBrouer.pdf) - 有关XDP开发人员面临的当前内存问题的高级详细信息.
  - [XDP for the Rest of Us](http://netdevconf.org/2.1/session.html?gospodarek)   - 如何为普通人开始使用eBPF和XDP.  朱莉娅埃文斯也总结了 [her blog](http://jvns.ca/blog/2017/04/07/xdp-bpf-tutorial/).
  - [XDP now with REDIRECT](http://people.netfilter.org/hawk/presentations/LLC2018/XDP_LLC2018_redirect.pdf) - 更新XDP，特别是重定向操作.

- [XDP workshop -- Introduction, experience, and future development (Video)](http://netdevconf.org/1.2/session.html?herbert-xdp-workshop)
- [High Speed Packet Filtering on Linux](https://cdn.shopify.com/s/files/1/0177/9886/files/phv2017-gbertin.pdf) - 关于Linux上的包过滤，DDoS保护，内核中的包处理，内核旁路，XDP和eBPF.

### AF_XDP

- [AF_XDP](https://www.kernel.org/doc/html/latest/networking/af_xdp.html) -  AF_XDP地址族的内核文档.
- [Fast Packet Processing in Linux with AF_XDP](https://archive.fosdem.org/2018/schedule/event/af_xdp/)

### bpfilter

- [Why is the kernel community replacing iptables with BPF?](https://cilium.io/blog/2018/04/17/why-is-the-kernel-community-replacing-iptables/) -  Cilium关于eBPF和bpfilter背后动机的博客文章，其中有一些示例以及使用eBPF和bpfilter的其他项目的链接.
- [bpfilter: Linux firewall with eBPF sauce](https://qmo.fr/docs/talk_20180316_frnog_bpfilter.pdf) - 来自Quentin Monnet的演讲中的幻灯片，其背景是eBPF，并将bpfilter与iptables进行比较.

### BTF

- [BPF Type Format (BTF)](https://www.kernel.org/doc/html/latest/bpf/btf.html) - 关于BTF的内核文档，解释如何使用它.
- [Enhancing the Linux kernel with BTF type information](https://facebookmicrosites.github.io/bpf/blog/2018/11/14/btf-enhancement.html) -  BTF为BPF程序提供调试信息所做工作的描述.

### cBPF

- [The BSD Packet Filter: A New Architecture for User-level Packet Capture](http://www.tcpdump.org/papers/bpf-usenix93.pdf) - 关于（经典）BPF的原始论文.
- [The FreeBSD manual page about BPF](http://www.gsp.com/cgi-bin/man.cgi?topic=bpf)
- [Linux' packet mmap(2), BPF, and Netsniff-NG](http://borkmann.ch/talks/2013_devconf.pdf)
- [tc and cls bpf: lightweight packet classifying with BPF](http://borkmann.ch/talks/2014_devconf.pdf)
- [Introducing Cloudflare's BPF Tools](https://blog.cloudflare.com/introducing-the-bpf-tools/) - 使用带有&#39;xt_bpf`模块的BPF字节码用于iptables.
- [Libpcap filters syntax](http://biot.com/capstats/bpf.html)

### Hardware Offload

- [eBPF/XDP hardware offload to SmartNICs](http://netdevconf.org/1.2/session.html?jakub-kicinski) - 由Netronome引入的带有TC或XDP（Linux内核4.9+）的eBPF的硬件卸载.
- [Comprehensive XDP offload---Handling the edge cases](https://www.netdevconf.org/2.2/session.html?viljoen-xdpoffload-talk) - 上述主题的更新.

## Tutorials

- [bcc Reference Guide](https://github.com/iovisor/bcc/blob/master/docs/reference_guide.md) - 开始使用bcc和eBPF的许多增量步骤，主要集中在跟踪和监控.
- [bcc Python Developer Tutorial](https://github.com/iovisor/bcc/blob/master/docs/tutorial_bcc_python_developer.md) - 附带密件抄送，但针对的是十七个“课程”中的Python位.
- [Linux Tracing Workshops Materials](https://github.com/goldshtn/linux-tracing-workshop) - 涉及使用多个BPF工具进行跟踪.
- [Tracing a packet journey using Linux tracepoints, perf and eBPF](https://blog.yadutaf.fr/2017/07/28/tracing-a-packet-journey-using-linux-tracepoints-perf-ebpf/) - 使用perf和bcc程序对ping请求和回复进行故障诊断.
- [Open NFP platform](https://open-nfp.org/dataplanes-ebpf/technical-papers/) - 由Netronome运营：一些与网络相关的eBPF用例的教程，包括eBPF卸载启动指南.
- [XDP for the Rest of Us](http://netdevconf.org/2.1/session.html?gospodarek) - 第一版开始使用XDP的研讨会.
- [XDP for the Rest of Us](https://www.netdevconf.org/2.2/session.html?gospodarek-xdp-workshop) - 第二版，新内容.
- [Load XDP programs using the ip (iproute2) command](https://medium.com/@fntlnz/load-xdp-programs-using-the-ip-iproute2-command-502043898263)
- [XDP Hands-On Tutorial](https://github.com/xdp-project/xdp-tutorial) - 一个渐进式（三级难度）教程，学习如何使用XDP处理数据包.

## Examples

- [linux/samples/bpf/](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/samples/bpf) - 在内核树中：一些示例eBPF程序.
- [linux/tools/testing/selftests/bpf](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/tools/testing/selftests/bpf) - 在内核树中：Linux BPF自我测试，包含许多eBPF程序.
- [prototype-kernel/kernel/samples/bpf](https://github.com/netoptimizer/prototype-kernel/tree/master/kernel/samples/bpf) -  Jesper Dangaard Brouer的原型内核存储库包含一些可以在内核基础结构之外编译的其他示例.
- [iproute2/examples/bpf/](https://git.kernel.org/pub/scm/network/iproute2/iproute2-next.git/tree/examples/bpf) - 一些连接到TC接口的网络程序.
- [Netronome sample network applications](https://github.com/Netronome/bpf-samples/) - 提供与硬件卸载兼容的eBPF应用程序的基本但完整的示例.
- [bcc/examples](https://github.com/iovisor/bcc/tree/master/examples) -  bcc工具附带的示例，主要是关于跟踪.
- [bcc/tools](https://github.com/iovisor/bcc/tree/master/tools)   - 这些工具本身可以看作BPF程序的示例用例，主要用于跟踪和监视.  已经为某些Linux发行版打包了bcc工具.
- [MPLSinIP sample](https://github.com/fzakaria/eBPF-mpls-encap-decap)   - 一个评论很多的样本，演示了如何在IP中封装和解封装MPLS.  该代码针对那些刚接触BPF开发的人进行了评论.
- [ebpf-samples](https://github.com/vbpf/ebpf-samples) - 从多个项目收集的已编译（作为ELF目标文件）样本的集合，主要用作用户空间验证器的测试用例.

## eBPF Workflow: Tools and Utilities

### bcc

- [bcc](https://github.com/iovisor/bcc/)   - 框架和工具集 - 处理BPF程序的一种方法，特别是用于跟踪和监视.  还包括一些可能有助于检查系统上的地图或程序的实用程序.
- [P4 compiler for BPF targets for bcc](https://github.com/iovisor/bcc/tree/master/src/cc/frontends/p4/compiler) - 限制C.的替代方案.
- [Lua front-end for BCC](https://github.com/iovisor/bcc/tree/master/src/lua) -  C的另一种替代方案，甚至是bcc中使用的大多数Python代码.

### iproute2

- [iproute2](https://git.kernel.org/pub/scm/network/iproute2/iproute2.git)   - 包含用于Linux上的网络管理的工具的包.  特别是，它包含用于管理eBPF过滤器和操作的`tc`，以及用于管理XDP程序的`ip`.  与BPF相关的大多数代码都在lib / bpf.c中.
- [iproute2-next](https://git.kernel.org/pub/scm/network/iproute2/iproute2-next.git) - 开发树，与net-next同步.

### LLVM

- [LLVM](https://llvm.org/)   - 包含eBPF工作流程中使用的几个工具.  可以从中检索Ubuntu / Debian的最新版本的快照 [here](http://apt.llvm.org/).

    -  clang用于以ELF格式（clang v3.7.1 +）将C编译为eBPF目标文件.  BPF后端添加了 [this commit](https://reviews.llvm.org/D6494).
  -  llvm-objdump用于以人类可读的格式转储目标文件的内容，可能使用初始C源代码（llvm-objdump v4.0 +）.
  -  llvm-mc用于从LLVM中间表示编译到eBPF目标文件，这样一个人可以从C编译到eBPF程序集，修改程序集，然后编译成ELF文件.

### libbpf

- [libbpf](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git/tree/tools/lib/bpf)   - 用于处理BPF对象（程序和映射）的AC库，以及操作包含它们的ELF目标文件.  它随内核一起提供 [mirrored on GitHub](https://github.com/libbpf/libbpf).

### bpftool and Other Tools from the Kernel Tree

- [bpftool](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpftool) - 还有内核树中的一些其他工具 [linux/tools/net/](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/tools/net?h=v4.14) 对于早于4.15的版本，或 [linux/tools/bpf/](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git/tree/tools/bpf) 之后：

  - [`bpftool`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpftool) - 可用于与用户空间中的eBPF程序和地图交互的通用实用程序，例如显示，转储，加载，反汇编，固定程序，或显示，创建，固定，更新，删除地图或附加和分离程序到cgroups.
  - [`bpf_asm`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpf_asm.c) - 最小的cBPF汇编程序.
  - [`bpf_dbg`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpf_dbg.c) - 用于cBPF程序的小型调试器.
  - [`bpf_jit_disasm`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpf_jit_disasm.c) - 两种BPF风格的反汇编程序，对于JIT调试非常有用.

### User Space eBPF

- [uBPF](https://github.com/iovisor/ubpf/) - 用C语言编写.包含一个解释器，一个用于x86_64架构的JIT编译器，一个汇编器和一个反汇编器.
- [A generic implementation](https://github.com/YutaroHayakawa/generic-ebpf)   - 支持FreeBSD内核，FreeBSD用户空间，Linux内核，Linux用户空间和macOS用户空间.  用于 [VALE software switch](https://www.unix.com/man-page/freebsd/4/vale/)'s [BPF extension module](https://github.com/YutaroHayakawa/vale-bpf).
- [rbpf](https://github.com/qmonnet/rbpf)   - 写在Rust.  Linux，macOS和Windows的解释器，以及Linux下的x86_64的JIT编译器.
- [PREVAIL](https://github.com/vbpf/ebpf-verifier) -  eBPF的用户空间验证程序 [using an abstract interpretation layer](https://elazarg.github.io/pldi19main-final.pdf)，支持循环.

### Testing in Virtual Environments

- [A Vagrant setup](https://github.com/iovisor/xdp-vagrant)   - 轻松测试XDP.  现在不太有用，因为存在通用XDP（独立于驱动程序，主要用于测试）.
- [bcc in a Docker container](https://github.com/zlim/bcc-docker)

## Projects Related to eBPF

-  P4与eBPF有一些互动：

  - [P4 on the Edge](https://schd.ws/hosted_files/2016p4workshop/1d/Intel%20Fastabend-P4%20on%20the%20Edge.pdf) -  P4与eBPF一起创建高性能可编程开关.
  - [OvS Orbit episode (#11), called P4 on the Edge](https://ovsorbit.org/#e11)   - 与前一项有关.  由John vfwiff的核心维护者之一Ben Pfaff对John Fastabend进行音频采访.
  - [P4, EBPF and Linux TC Offload](https://open-nfp.org/m/documents/Open_NFP_P4_EBPF_Linux_TC_Offload_FINAL_5JHLETS.pdf) -  P4与Netronome的NFP（网络流处理器）架构上的eBPF硬件卸载相关的一些元素.
  - [Old documentation for P4 usage with eBPF](https://github.com/iovisor/bcc/tree/master/src/cc/frontends/p4)   - 来自bcc存储库;  由以下链接的P4_16后端弃用.
  - [P4_16 backend for eBPF](https://github.com/p4lang/p4c/blob/master/backends/ebpf/README.md)

- 谁是项目（[GitHub repository](https://github.com/cilium/cilium) ）是一种依靠BPF和XDP的技术，为基于eBPF程序生成的容器提供“快速的内核网络和安全策略实施”.  提供了许多演示文稿（重叠）：

  - [Cilium: Networking & Security for Containers with BPF & XDP](http://www.slideshare.net/ThomasGraf5/clium-container-networking-with-bpf-xdp) - 还具有负载平衡器用例
  - [Cilium: Networking & Security for Containers with BPF & XDP](http://www.slideshare.net/Docker/cilium-bpf-xdp-for-containers-66969823) - [video](https://www.youtube.com/watch?v=TnJF7ht3ZYc&list=PLkA60AVN3hh8oPas3cq2VA9xB7WazcIgs)
  - [Cilium: Fast IPv6 container Networking with BPF and XDP](http://www.slideshare.net/ThomasGraf5/cilium-fast-ipv6-container-networking-with-bpf-and-xdp)
  - [Cilium: BPF & XDP for containers](https://fosdem.org/2017/schedule/event/cilium/)
  - [OvS Orbit episode (#4)](https://ovsorbit.benpfaff.org/) -  Ben Pfaff对Thomas Graf的采访.
  - [A generic introduction to Cilium](https://opensource.googleblog.com/2016/11/cilium-networking-and-security.html)
  - [A podcast interviewing Thomas Graf](http://blog.ipspace.net/2016/10/fast-linux-packet-forwarding-with.html) -  Ivan Pepelnjak在2016年10月采访了Thomas，关于eBPF，P4，XDP和Cilium.

- 开放vSwitch（OvS）及其相关项目Open Virtual Network（OVN，一种开源网络虚拟化解决方案）正在考虑在各个层面使用eBPF：

  - [Offloading OVS Flow Processing using eBPF](http://openvswitch.org/support/ovscon2016/7/1120-tu.pdf)
  - [Coupling the Flexibility of OVN with the Efficiency of IOVisor](http://openvswitch.org/support/ovscon2016/7/1245-bertrone.pdf)

- [Katran](https://code.fb.com/open-source/open-sourcing-katran-a-scalable-network-load-balancer/) - 基于XDP的第4层负载均衡器，由Facebook开源.
- [XDP in practice: integrating XDP in our DDoS mitigation pipeline](http://netdevconf.org/2.1/session.html?bertin) - 使用Cloudflare的XDP防御DDoS.
- [Droplet: DDoS countermeasures powered by BPF + XDP](http://netdevconf.org/2.1/session.html?zhou) - 在Facebook上使用XDP保护DDoS.
- [DPDK has a poll-mode driver (PMD) based on AF_XDP](https://dpdkuserspace2018.sched.com/event/G45Z/dpdk-pmd-for-afxdp)
- [CETH for XDP](http://www.slideshare.net/IOVisor/ceth-for-xdp-linux-meetup-santa-clara-july-2016) - 用于更快网络I / O的通用以太网驱动程序框架，这是Mellanox发起的一项技术.
-  Suricata，一种开源入侵检测系统， [relies on eBPF components](https://www.stamus-networks.com/2016/09/28/suricata-bypass-feature/) 因其“捕获旁路”功能：

  - ["eBPF and XDP" section of Suricata documentation](http://suricata.readthedocs.io/en/latest/capture-hardware/ebpf-xdp.html?highlight=XDP#ebpf-and-xdp)
  - [SEPTun-Mark-II](https://github.com/pevma/SEPTun-Mark-II) - 极端性能调整指南 -  Mark II.
  - [A blog post introducing the feature](https://www.stamus-networks.com/2016/09/28/suricata-bypass-feature/)
  - [The adventures of a Suricate in eBPF land](http://netdevconf.org/1.2/slides/oct6/10_suricata_ebpf.pdf)
  - [eBPF and XDP seen from the eyes of a meerkat](https://www.slideshare.net/ennael/kernel-recipes-2017-ebpf-and-xdp-eric-leblond)

- [Sysdig](https://github.com/draios/sysdig) - 用于“通过容器本机支持实现通用系统可见性”的工具，现在支持eBPF.
- [InKeV: In-Kernel Distributed Network Virtualization for DCN](https://github.com/iovisor/bpf-docs/blob/master/university/sigcomm-ccr-InKev-2016.pdf)
- [gobpf - utilizing eBPF from Go](https://fosdem.org/2017/schedule/event/go_bpf/) - 用于从Go创建，加载和使用eBPF程序的库.
- [ply](https://wkz.github.io/ply/) - 适用于Linux的小型但灵活的开源动态跟踪器，具有与bcc工具类似的功能，但具有受awk和DTrace启发的简单语言.
- [bpftrace](https://github.com/iovisor/bpftrace)   - 用于跟踪的工具，再次使用自己的DSL.  它足够灵活，可以被设想为DTrace和SystemTap的Linux替代品.
- [kubectl trace](https://github.com/iovisor/kubectl-trace) - 用于在Kubernetes集群中执行bpftrace程序的kubectl插件.
- [bpfd](https://github.com/genuinetools/bpfd)   - 使用Linux作为守护进程的规则运行BPF程序的框架.  容器意识到.
- [BPFd](https://github.com/joelagnel/bpfd) - 一个独特的BPF守护程序，试图利用bcc工具的灵活性来跟踪和调试远程目标，特别是运行Android的设备.
- [adeb](https://github.com/joelagnel/adeb) - 用于在Android上使用BPFd的跟踪工具的Linux shell环境.
- [FUSE](https://events.linuxfoundation.org/wp-content/uploads/2017/11/When-eBPF-Meets-FUSE-Improving-Performance-of-User-File-Systems-Ashish-Bijlani-Georgia-Tech.pdf) - 考虑使用eBPF.
- [DEEP-mon](https://www.slideshare.net/necstlab/deepmon-dynamic-and-energy-efficient-power-monitoring-for-containerbased-infrastructures) - 帮助测量服务器的功耗，并使用eBPF程序进行内核中的数据聚合.

## The Code

- [linux/include/linux/bpf.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/linux/bpf.h) - 与 [linux/include/uapi/bpf.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/uapi/linux/bpf.h)：与eBPF相关的定义，分别在内核中使用，与用户空间程序接口.
- [linux/include/linux/filter.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/linux/filter.h) - 与 [linux/include/uapi/filter.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/uapi/linux/filter.h)：用于自行运行BPF程序的信息.
- [linux/kernel/bpf/](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf)   - 此目录包含大多数与BPF相关的代码.  特别是，这些文件值得关注：

  - [`syscall.c`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf/syscall.c) - 系统调用允许的不同操作，例如程序加载或映射管理.
  - [`core.c`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf/core.c) -  BPF口译员.
  - [`verifier.c`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf/verifier.c) -  BPF验证程序.

- [linux/net/core/filter.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/net/core/filter.c)   - 与网络相关的功能和eBPF助手（TC，XDP等）;  还包含将cBPF字节码迁移到eBPF的代码（所有cBPF程序都在最近的内核中转换为eBPF）.
- [linux/kernel/trace/bpf_trace.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/kernel/trace/bpf_trace.c) - 与跟踪和监控（kprobes，跟踪点等）相关的功能和eBPF帮助程序.
-  JIT编译器位于各自体系结构的目录下，例如文件 [linux/arch/x86/net/bpf_jit_comp.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/arch/x86/net/bpf_jit_comp.c)  对于x86 \.  用于硬件卸载的JIT编译器是例外，它们位于驱动程序中，例如 [linux/drivers/net/ethernet/netronome/nfp/bpf/jit.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/drivers/net/ethernet/netronome/nfp/bpf/jit.c) 对于Netronome NFP.
- [linux/net/sched/](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/net/sched) - 特别是在文件`act_bpf.c`（动作）和`cls_bpf.c`（过滤器）中：与BPF动作相关的代码和TC过滤器.
- [linux/kernel/seccomp.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/kernel/seccomp.c)
- [linux/net/core/dev.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/net/core/dev.c)   - 包含函数`dev_change_xdp_fd（）`，该函数通过Netlink命令调用，以便在从用户空间加载到内核之后将XDP程序挂钩到设备.  该函数依次使用相关驱动程序的回调.

## Development and Community

- [The bpf-next tree](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/)   -  BPF补丁登陆这棵树.  它经常合并到 [net-next](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git)，每个版本本身都合并到Linus的树上.
- [Kernel documentation](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git/tree/Documentation/bpf/bpf_devel_QA.rst) - 关于对BPF的贡献.
- [The netdev mailing list](http://lists.openwall.net/netdev/)   -  Linux内核网络堆栈开发的邮件列表.  所有补丁都会发送到那里进行审核和收录.
- [XDP-newbies](http://vger.kernel.org/vger-lists.html#xdp-newbies) - A mailing list specially dedicated to XDP programming (both for architecture or for asking for help).
- [IO Visor mailing list](http://lists.iovisor.org/pipermail/iovisor-dev/) -  BPF是项目的核心，并定期在邮件列表中进行讨论.
- [@IOVisor Twitter account](https://twitter.com/IOVisor)
- [The XDP Collaboration Project](https://github.com/xdp-project/xdp-project) -  GitHub存储库，包含有关XDP未来发展的注释和想法.

## Other Lists of Resources on eBPF

- [IO Visor's bcc documentation](https://github.com/iovisor/bcc/tree/master/docs)
- [IO Visor's bpf-docs repository](https://github.com/iovisor/bpf-docs/)
- [Dive into BPF: A List of Reading Material](https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/)

## Acknowledgement

感谢Quentin Monnet和Daniel Borkmann的原创作品 [Dive into BPF: A List of Reading Material](https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/) 这成为这份名单的基础.

## Contributing

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/zoidbergwill/awesome-ebpf/blob/master/contributing.md) 第一.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, zoidbergwill has waived all copyright and related or neighboring rights to this work.
