<div class="github-widget" data-repo="Friz-zy/awesome-linux-containers"></div>
## Awesome Linux Containers

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)



## Foundations

* [OPEN CONTAINER INITIATIVE](https://www.opencontainers.org/)  
Open Container Initiative是一个轻量级，开放的治理结构，将在Linux Foundation的支持下形成，其目的是围绕容器格式和运行时创建开放的行业标准.
* [Cloud Native Computing Foundation](https://cncf.io/)  
云原生计算基金会将创建并推动采用一套新的通用容器技术，这些技术具有技术优势和最终用户价值，并受到互联网规模计算的启发.
* [Cloud Foundry Foundation](https://www.cloudfoundry.org/foundation/)  
云是我们的代工厂.

## Specifications

* [Open Container Specifications](https://github.com/opencontainers/specs)  
 该项目是编写开放式集装箱计划规范的地方.  这是一个正在进行的工作. 
* [App Container basics](https://github.com/coreos/rkt/blob/master/Documentation/app-container.md)  
App Container（appc）是一个开放式规范，它定义了如何在容器中运行应用程序的几个方面：图像格式，运行时环境和发现协议.
* [Systemd Container Interface](https://wiki.freedesktop.org/www/Software/systemd/ContainerInterface/)  
 Systemd是Linux系统的一套基本构建块.  它提供了一个系统和服务管理器，它以PID 1的形式运行并启动系统的其余部分.  如果您编写容器解决方案，请考虑支持以下接口.
* [Nulecule Specification](https://github.com/projectatomic/atomicapp/tree/master/docs/spec)  
Nulecule定义了用于打包复杂多容器应用程序和服务的模式和模型，引用了所有依赖项，包括用于构建，部署，监视和主动管理的容器映像中的编排元数据.
* [Oracle microcontainer manifesto](https://blogs.oracle.com/developers/the-microcontainer-manifesto)  
这不是一种新的容器格式，而只是一种构建容器的特定方法，可以提供更好的安全性和稳定性.
* [Cloud Native Application Bundle Specification](https://github.com/deislabs/cnab-spec)  
一种包格式规范，描述了捆绑，安装和管理分布式应用程序的技术，这些技术是设计上的，与云无关的.

## Clouds

* [Amazon EC2 Container Service ](https://aws.amazon.com/ecs/)   
支持Docker容器的容器管理服务，允许您在Amazon EC2实例的托管集群上轻松运行应用程序.
* [Google Cloud Platform](https://cloud.google.com/container-engine/)  
 在Google Cloud Platform上运行Docker容器，由Kubernetes提供支持.  Google Container Engine会根据已声明的需求，在托管的虚拟机群集上主动调度容器. 
* [Jelastic](http://jelastic.com/)  
针对DevOps的联合云解决方案中的无限PaaS和基于容器的IaaS.
* [Joyent](https://www.joyent.com/)  
适用于当今苛刻的实时Web和移动应用程序的高性能容器 - 本机基础架构.
* [Kubernetes](http://kubernetes.io/)  
将一组Linux容器作为单个系统进行管理，以加速Dev并简化Ops.
* [Mesosphere](https://mesosphere.com/)  
 Mesosphere数据中心操作系统（DCOS）是一种新型操作系统，跨越数据中心或云中的所有计算机.  它提供了一种在共享资源上部署应用程序，服务和大数据基础架构的高度灵活且高度可扩展的方法.
* [OpenShift Origin](https://www.openshift.org/)  
OpenShift Origin是一个发行版 [Kubernetes](http://kubernetes.io/)  针对持续应用程序开发和多租户部署进行了优化.  Origin在Kubernetes之上添加了开发人员和以操作为中心的工具，以便为小型和大型团队实现快速的应用程序开发，轻松部署和扩展以及长期生命周期维护.
* [Warden](https://github.com/cloudfoundry/warden)  
 管理孤立，短暂和资源控制的环境.  Cloud Foundry的一部分 - 作为服务项目的开放平台.
* [Virtuozzo](https://virtuozzo.com)  
基于Virtuozzo容器构建的平台，可以在任何公共或私有云中的任何裸机或虚拟服务器上轻松运行，以自动化，优化和加速内部IT和开发流程.
* [Rancher](http://rancher.com/)  
 Rancher是一个完整的开源平台，用于在生产中部署和管理容器.  它包括商业支持的Kubernetes，Mesos和Docker Swarm发行版，可以轻松地在任何基础架构上运行容器化应用程序.
* [Docker Swarm](https://docs.docker.com/swarm)  
Docker Swarm是Docker的本机群集.
* [Azure Container Service](https://azure.microsoft.com/en-us/services/container-service/)  
Azure容器服务优化了专门针对Azure的流行开源工具和技术的配置.
* [CIAO](https://ciao-project.github.io/)  
 适用于Intel Clear Linux OS的Cloud Integrated Advanced Orchestrator. 
 * [Kontena](http://kontena.io)  
 Kontena是一个开发人员友好的开源平台，用于编排在Docker容器上运行的应用程序.  它简化了在任何基础架构上部署和运行容器化应用程序的过程.
* [Hyper.sh](https://hyper.sh)  
无服务器容器平台.
* [Alibaba Cloud Container Service](https://www.alibabacloud.com/fr/product/container-service)  
Container Service是一种高性能且可扩展的容器应用程序管理服务，使您可以使用Docker和Kubernetes来管理容器化应用程序的生命周期.
* [Nomad](https://www.nomadproject.io/)  
  HashiCorp Nomad是一个单一的二进制文件，可以在Linux，Windows和Mac上安排应用程序和服务.  它是一个开源调度程序，它使用声明性作业文件来调度虚拟化，容器化和独立应用程序.

## Operating Systems

* [CoreOs](https://coreos.com/)  
轻量级Linux操作系统，专为集群部署而设计，可为最关键的应用程序提供自动化，安全性和可扩展性.
* [RancherOS](http://rancher.com/rancher-os/)  
RancherOS是一个小型Linux发行版，它将整个操作系统作为Docker容器运行.
* [Project Atomic](http://www.projectatomic.io/)  
 Project Atomic为您的Linux Docker Kubernetes（LDK）应用程序堆栈提供了最佳平台.  使用不可变基础架构来部署和扩展容器化应用程序.
* [Snappy Ubuntu Core](https://www.ubuntu.com/cloud/snappy)  
Ubuntu Core是大规模云容器部署的完美系统，为世界上最受欢迎的容器平台带来了交易更新.
* [ResinOS](https://resinos.io/)  
专为容器量身定制的主机操作系统，专为可靠性而设计
* [Photon](https://github.com/vmware/photon)  
 Photon OS是一款最小的Linux容器主机，设计占用空间小，可针对VMware平台进行调整.  Photon旨在邀请在虚拟化环境中运行容器化和Linux应用程序的协作.
* [Clear Linux Project](https://clearlinux.org/documentation/clear-linux/get-started)  
适用于英特尔架构的Clear Linux项目是为各种云用例构建的分发版.
* [CargOS](https://cargos.io/)  
 CargOS是Docker主机的一个新的轻量级开源平台，旨在实现速度，可管理性和安全性.  版本适用于64位Intel / AMD CPU.
* [OSv](http://osv.io/)  
 OSv是专为云设计的开源操作系统.  从头开始构建，轻松部署和管理，具有卓越的性能.
* [HypriotOS](http://blog.hypriot.com/about/)  
 基于Debian的最小操作系统，针对运行Docker进行了优化.  它使任何Raspberry Pi上的Docker很容易使用. 
* [MCL](https://mcl.host)  
 MCL（* Minimal Container Linux *）是一个从头开始的最小的Linux操作系统，专门用于运行容器.  它占地面积小~50MB，可在几秒钟内启动.  它目前已经过优化，可以运行Docker.

## Hypervisors

* [Docker](https://github.com/veggiemonk/awesome-docker#cloud-infrastructure)  
 面向开发人员和系统管理员的分布式应用程序的开放平台.  **事实上的标准**.
* [LXD](https://github.com/lxc/lxd)  
基于liblxc的守护进程提供REST API来管理LXC容器.
* [OpenVZ](https://openvz.org/Main_Page)  
 OpenVZ是基于容器的Linux虚拟化.  OpenVZ在单个物理服务器上创建多个安全，隔离的Linux容器（也称为VE或VPS），从而提高服务器利用率并确保应用程序不会发生冲突.
* [MultiDocker](https://github.com/marty90/multidocker)  
创建一个安全的多用户Docker机器，其中每个用户被隔离到一个独立的容器中.
* [Lithos](https://github.com/tailhook/lithos/)  
 Lithos是一个用于运行服务的过程监控器和容器.  它不是用于系统初始化，而是试图成为构建容器编排的基础工具.
* [containerd](https://containerd.io/)  
一个容器运行时，可以管理一个完整的容器生命周期 - 从映像传输/存储到容器执行，监督和网络.

## Containers

* [runc](https://github.com/opencontainers/runc)  
runc是一个CLI工具，用于根据OCS规范生成和运行容器.
* [Bocker](https://github.com/p8952/bocker)  
Docker在大约100行bash中实现.
* [Rocket](https://github.com/coreos/rkt)  
 rkt（发音为“rock-it”）是一个用于在Linux上运行app容器的CLI.  rkt旨在可组合，安全且快速.  基于AppC规范.
* [LXC](https://github.com/lxc/lxc)  
 LXC是众所周知的一套工具，模板，库和语言绑定.  它非常低级，非常灵活，几乎涵盖了上游内核支持的每个包含功能.
* [Vagga](https://github.com/tailhook/vagga)  
Vagga是一个完全用户空间容器引擎，受Vagrant和Docker的启发，专门用于开发环境.
* [libct](https://github.com/xemul/libct)  
Libct是一个容器管理库，它为前端程序提供方便的API，以便在容器的整个生命周期内对其进行规则.
* [libvirt](https://libvirt.org/drvlxc.html)  
与最新版Linux（和其他操作系统）的虚拟化功能进行交互的重要工具包.
* [systemd-nspawn](https://wiki.archlinux.org/index.php/Systemd-nspawn)  
 生成用于调试，测试和构建的命名空间容器.  部分 [systemd](https://wiki.freedesktop.org/www/Software/systemd/).
* [porto](https://github.com/yandex/porto)  
Porto的主要目标是通过几个Linux内核机制（如cgroups，命名空间，挂载，网络等）创建一个方便，可靠的接口.
* [udocker](https://github.com/indigo-dc/udocker)  
用于在没有root权限的批处理或交互式系统中执行简单容器的基本用户工具.
* [Let Me Contain That For You](https://github.com/google/lmctfy)  
LMCTFY是Google容器堆栈的开源版本，它提供Linux应用程序容器.
* [cc-oci-runtime](https://github.com/01org/cc-oci-runtime)  
Intel Clear Linux OCI (Open Containers Initiative) compatible runtime.
* [railcar](https://github.com/oracle/railcar)  
 Railcar是opencontainers计划的运行时规范的生锈实现.  它类似于参考实现runc，但它完全实现了生锈以保证内存安全，而不需要垃圾收集器或多线程的开销.
* [Kata Containers](https://katacontainers.io/)  
Kata Containers是一个新的开源项目，构建了极其轻量级的虚拟机，可以无缝地插入容器生态系统.
* [plash](https://github.com/ihucos/plash/)  
轻巧，无根的容器.
* [runv](https://github.com/hyperhq/runv)  
 基于虚拟机管理程序（KVM，Xen，QEMU）的OCI运行时.  隔离安全.
* [podman](https://github.com/containers/libpod)  
全面管理容器生命周期.
* [firecracker](https://github.com/firecracker-microvm/firecracker)  
Firecracker在称为microVM的轻量级虚拟机中运行工作负载，它将硬件虚拟化技术提供的安全性和隔离性与容器的速度和灵活性相结合.

## Sandboxes

* [Firejail](https://l3net.wordpress.com/projects/firejail/)  
Firejail是一个SUID沙箱程序，它通过使用Linux命名空间，seccomp-bpf和Linux功能限制不受信任的应用程序的运行环境来降低安全漏洞的风险.
* [NsJail](https://github.com/google/nsjail)  
 NsJail是Linux的进程隔离工具.  它使用Linux内核的命名空间，资源控制和seccomp-bpf系统调用过滤器子系统.
* [Subuser](https://github.com/subuser-security/subuser)  
使用Docker保护Linux桌面.
* [Snappy](https://wiki.ubuntu.com/SecurityTeam/Specifications/SnappyConfinement)  
Snappy Ubuntu Core是Ubuntu的新版本，具有事务更新 - 一个最小的服务器映像，具有与今天的Ubuntu相同的库，但应用程序是通过更简单的机制提供的.
* [xdg-app](https://wiki.gnome.org/Projects/SandboxedApps)  
xdg-app是一个用于在Linux上构建，分发和运行沙盒桌面应用程序的系统.
* [Bubblewrap](https://github.com/projectatomic/bubblewrap)  
使用没有root权限的Linux命名空间在沙箱中运行应用程序，并通过setuid binary提供用户命名空间.
* [singularity](https://github.com/singularityware/singularity)  
Linux的通用应用程序容器.

## Partial Access

* [nsenter](http://man7.org/linux/man-pages/man1/nsenter.1.html)  
 使用其他进程的命名空间运行程序.  util-linux的一部分.
* [ip-netns](http://man7.org/linux/man-pages/man8/ip-netns.8.html)  
 处理网络名称空间管理  iproute2的一部分.
* [unshare](http://man7.org/linux/man-pages/man1/unshare.1.html)  
 运行程序，其中一些名称空间与父项取消共享.  util-linux的一部分.
* [python-nsenter](https://github.com/zalando/python-nsenter)  
这个Python包允许通过执行“setns”系统调用来输入Linux内核命名空间（mount，IPC，net，PID，user和UTS）.
* [butter](https://pypi.python.org/pypi/butter)  
Python库与asyncio支持的低级linux功能（inotify，fanotify，timerfd，signalfd，eventfd，containers）接口.
* [pyspaces](https://github.com/Friz-zy/pyspaces)  
通过glibc与纯python一起使用Linux命名空间.
* [CRIU](https://criu.org/Main_Page)  
 Checkpoint / Restore In Userspace是Linux操作系统的软件工具.  使用此工具，您可以冻结正在运行的应用程序（或其中的一部分），并将其作为文件集合检查到硬盘驱动器.  CRIU与Docker和LXC集成，实现容器的实时迁移.
* [Moby](https://github.com/moby/moby)  
Docker创建的容器软件工具包组件的“Lego set”.

## Filesystem

* [container-diff](https://github.com/GoogleCloudPlatform/container-diff)  
用于分析和比较容器图像的工具.
* [buildah](https://github.com/projectatomic/buildah)  
一种便于构建OCI容器图像的工具.
* [skopeo](https://github.com/projectatomic/skopeo)  
使用远程图像注册表 - 检索信息，图像，签名内容.
* [img](https://github.com/jessfraz/img)  
独立，无守护进程，无特权的Dockerfile和OCI兼容的容器映像构建器.
* [dgr](https://github.com/blablacar/dgr)  
命令行实用程序，用于在运行时构建和配置基于约定优于配置的应用程序容器映像（ACI）和应用程序容器窗格（POD）.
* [Whaler](https://github.com/P3GLEG/Whaler)  
Whaler旨在将Docker镜像反向工程到创建它的Dockerfile中.
* [dive](https://github.com/wagoodman/dive)  
用于探索泊坞窗图像中每个图层的工具.
* [go-containerregistry](https://github.com/google/go-containerregistry)  
使用库和CLI来处理容器注册表.

## Dashboard

* [LXC-Web-Panel](https://lxc-webpanel.github.io/)  
UXntu上LXC的Web面板.
* [Liman](https://github.com/salihciftci/liman)  
基本的docker监控Web应用程序.

## Best practices

* [The Twelve-Factor App](https://12factor.net/)  
十二因素应用程序是一种用于构建软件即服务应用程序的方法.
* [Container Best Practices](http://docs.projectatomic.io/container-best-practices/)  
一个协作项目，用于记录Project Atomic的基于容器的应用程序架构，创建和管理.

## Security

### Tools

* [Docker bench security](https://github.com/docker/docker-bench-security)  
Docker Bench for Security是一个脚本，用于检查有关在生产中部署Docker容器的许多常见最佳实践.
* [CoreOS Clair](https://coreos.com/blog/vulnerability-analysis-for-containers/)  
容器的开源漏洞分析.
* [bane](https://github.com/jfrazelle/bane)  
用于docker容器的自定义AppArmor配置文件生成器.
* [OpenSCAP](https://github.com/OpenSCAP/container-compliance)  
OpenSCAP生态系统提供了多种工具，可以帮助管理员和审计人员评估，衡量和执行安全基准.
* [drydock](https://github.com/zuBux/drydock)  
Drydock提供了一种使用可编辑审计模板评估Docker守护程序配置和容器安全性的灵活方法.
* [trireme](https://www.aporeto.com/trireme/)  
Docker和Kubernetes的分段安全性.
* [goss](https://github.com/aelsabbahy/goss)  
快速简便的服务器测试/验证.
* [sockguard](https://github.com/buildkite/sockguard)  
docker.sock的代理，用于强制实施访问控制和隔离权限.
* [gvisor](https://github.com/google/gvisor)  
 gVisor是一个用Go编写的用户空间内核，它实现了Linux系统表面的很大一部分.  它包括一个名为runsc的Open Container Initiative（OCI）运行时，它提供了应用程序和主机内核之间的隔离边界.  runsc运行时与Docker和Kubernetes集成，使得运行沙盒容器变得简单.
* [docker-explorer](https://github.com/google/docker-explorer/)  
一种帮助预防离线码头获取的工具.


### Links
* [CIS Security Benchmarks](https://benchmarks.cisecurity.org/about/)
* [Are Docker containers really secure?](https://opensource.com/business/14/7/docker-security-selinux)
* [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
* [Docker, Linux Containers (LXC), and security](http://www.slideshare.net/jpetazzo/docker-linux-containers-lxc-and-security)
* [For containers, security is problem #1](http://www.itworld.com/article/2920349/security/for-containers-security-is-problem-1.html)
* [Linux Container Security](https://mjg59.dreamwidth.org/33170.html)
* [Ask HN: Best Linux sandbox?](https://news.ycombinator.com/item?id=10030868)
* [CIS Docker 1.6 Benchmark v1.0.0](https://benchmarks.cisecurity.org/tools2/docker/CIS_Docker_1.6_Benchmark_v1.0.0.pdf)
* [Understanding docker security and best practices](https://blog.docker.com/2015/05/understanding-docker-security-and-best-practices/)
* [Update on Ubuntu Phone security issue](https://insights.ubuntu.com/2015/10/15/update-on-ubuntu-phone-security-issue/)
* [Don't expose the Docker socket (not even to a container)](https://www.lvh.io/posts/dont-expose-the-docker-socket-not-even-to-a-container.html)
* [RedHat Blog](http://rhelblog.redhat.com/?s=container&submit=Search)
  - [Introduction to Linux Containers](https://access.redhat.com/articles/1353593)
  - [What’s Next for Containers? User Namespaces](http://rhelblog.redhat.com/2015/07/07/whats-next-for-containers-user-namespaces/#more-1004)
  - [Architecting Containers Part 1: Why Understanding User Space vs. Kernel Space Matters](http://rhelblog.redhat.com/2015/07/29/architecting-containers-part-1-user-space-vs-kernel-space/)
  - [Architecting Containers Part 2: Why the User Space Matters](http://rhelblog.redhat.com/2015/09/17/architecting-containers-part-2-why-the-user-space-matters-2/)
  - [Secure Your Containers with this One Weird Trick](http://rhelblog.redhat.com/2016/10/17/secure-your-containers-with-this-one-weird-trick/)
* [Why you shouldn't use ENV variables for secret data](https://diogomonica.com/2017/03/27/why-you-shouldnt-use-env-variables-for-secret-data/)
* [When to use-Docker alternatives rkt and LXD](http://searchitoperations.techtarget.com/tip/When-to-use-Docker-alternatives-rkt-and-LXD)

### Levels of security problems

1）定期申请

*总是不信任 - &gt;知道
* suid bit  - &gt; mount with nosuid
*限制可用的系统调用 - &gt; seccomp-bpf，grsec
 *泄漏到另一个容器（名称空间，文件系统中的错误） - &gt;每个容器内部具有不同uid的用户名称空间：容器中的1000  - 外部的14293和15398;  安全模块，如selinux或apparmor

2）系统服务，如cron，ssh

*以root身份运行 - &gt;通过堡垒主机或vm隔离
*使用/ dev  - &gt;“devices”控制组  
默认情况下，在容器中创建以下设备节点.  
Docker镜像也与nodev一起安装，这意味着即使在图像中预先创建了设备节点，容器内的进程也无法使用它来与内核通信.  
/dev/console,/dev/null,/dev/zero,/dev/full,/dev/tty*,/dev/urandom,/dev/random,/dev/fuse
* root调用 - &gt;功能（cap_sys_admin警告！）  
以下是Docker使用的当前功能列表：chown，dac_override，fowner，kill，setgid，setuid，setpcap，net_bind_service，net_raw，sys_chroot，mknod，setfcap和audit_write.  
Docker删除了其中的一些功能，包括：  
CAP_SETPCAP修改流程功能  
CAP_SYS_MODULE插入/删除内核模块   
CAP_SYS_RAWIO修改内核内存  
CAP_SYS_PACCT配置进程记帐  
CAP_SYS_NICE修改进程的优先级  
CAP_SYS_RESOURCE覆盖资源限制  
CAP_SYS_TIME修改系统时钟  
CAP_SYS_TTY_CONFIG配置tty设备  
CAP_AUDIT_WRITE编写审核日志  
CAP_AUDIT_CONTROL配置审计子系统  
CAP_MAC_OVERRIDE忽略内核MAC策略  
CAP_MAC_ADMIN配置MAC配置  
CAP_SYSLOG修改内核printk行为  
CAP_NET_ADMIN配置网络  
CAP_SYS_ADMIN 	Catch all  
 使用/ proc，/ sys  - &gt; remount ro，drop cap_sys_admin;  安全模块，如selinux或apparmor;  这个fs的某些部分是“名称空间感知”  
Docker mounts these file systems into the container as "read-only" mount points.  
 .  / SYS  
 .  的/ proc / SYS  
 .  / PROC / SysRq的触发  
 .  的/ proc / IRQ  
 .  的/ proc /巴士  
写时复制文件系统  
 Docker使用copy-on-write文件系统.  这意味着容器可以使用与容器基础相同的文件系统映像.  当容器将内容写入映像时，它将被写入容器特定的文件系统.  这可以防止一个容器看到另一个容器的更改，即使它们写入同一个文件系统映像.  同样重要的是，一个容器无法更改图像内容以影响另一个容器中的进程.
* uid 0  - &gt;用户名称空间，uid 0 mappet到随机uid外面

3）系统服务，如设备，网络，文件系统

 * root  - &gt;更多服务应该在主机外工作;  隔离敏感函数，作为非特权上下文运行
*完全权限 - &gt;在内核级别上隔离

4）内核驱动程序，网络堆栈，安全策略

*绝对权限 - &gt;在单独的vm中运行它

5）一般像不可变的基础设施

*集装箱是ro
*写小的独立的rw nosuid部分

[src](http://www.slideshare.net/jpetazzo/docker-linux-containers-lxc-and-security)  
[src](https://opensource.com/business/14/9/security-for-docker)

### Technologies for security

 事情变得更好.  例如，大多数现代容器技术都可以利用Linux的内置安全工具，例如：  
[AppArmor](http://wiki.apparmor.net/index.php/Main_Page), [SELinux](http://selinuxproject.org/page/Main_Page) 和 [Seccomp](http://man7.org/linux/man-pages/man2/seccomp.2.html) 政策;  
[Grsecurity](https://grsecurity.net/);  
[Control groups (cgroups)](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Resource_Management_Guide/ch01.html);  
[Kernel namespaces](http://man7.org/linux/man-pages/man7/namespaces.7.html)  
[src](http://www.itworld.com/article/2920349/security/for-containers-security-is-problem-1.html)

当然，你正在部署seccomp，但你不能在你的容器中使用selinux，因为策略不是每个命名空间（?? lxc对每个容器使用apparmore ...）  
[sVirt](http://selinuxproject.org/page/SVirt) -  selinux for sqm  
[src](https://mjg59.dreamwidth.org/33170.html)

主要内核子系统不是命名空间，如：  
-  SELinux  
-  Cgroups  
-  / sys下的文件系统  
-  / proc / sys，/ proc / sysrq-trigger，/ proc / irq，/ proc / bus

设备未命名空间：  
-  / dev / mem  
-  / dev / sd *文件系统设备  
- 内核模块

如果您可以作为特权进程进行通信或攻击其中一个，则可以拥有该系统.  
[src](https://opensource.com/business/14/7/docker-security-selinux)

## Another Information Sources

* [sysdig-container-ecosystem](https://github.com/draios/sysdig-container-ecosystem)  
 至少可以说，围绕容器和微服务出现的令人敬畏的新技术的生态系统可能有点压倒性.  我们认为我们可以提供帮助：欢迎来到集装箱生态系统项目.
* [doger.io](http://doger.io/)  
 此页面试图记录Linux上容器的细节.  这不仅限于希望在自己的代码中实现容器或使用类似容器的程序员，还包括想要更好地处理容器如何在“引擎盖下”工作的系统管理员和用户. 
