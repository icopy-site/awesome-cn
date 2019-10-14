<div class="github-widget" data-repo="Friz-zy/awesome-linux-containers"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Linux Containers

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)



## Foundations

* [OPEN CONTAINER INITIATIVE](https://www.opencontainers.org/)  
开放容器计划是一种轻量级的，开放的治理结构，将在Linux基金会的主持下形成，其明确目的是围绕容器格式和运行时创建开放的行业标准.
* [Cloud Native Computing Foundation](https://cncf.io/)  
Cloud Native Computing Foundation将创建并推动采用一组新的通用容器技术，这些技术受技术优势和最终用户价值的启发，并受到Internet规模计算的启发.
* [Cloud Foundry Foundation](https://www.cloudfoundry.org/foundation/)  
云是我们的铸造厂.

## Specifications

* [Open Container Specifications](https://github.com/opencontainers/specs)  
 该项目是编写“开放容器计划规范”的地方.  这是一个正在进行的工作. 
* [App Container basics](https://github.com/coreos/rkt/blob/master/Documentation/app-container.md)  
App Container（appc）是一个开放规范，它定义了如何在容器中运行应用程序的几个方面：图像格式，运行时环境和发现协议.
* [Systemd Container Interface](https://wiki.freedesktop.org/www/Software/systemd/ContainerInterface/)  
 Systemd是Linux系统的一组基本构建块.  它提供了一个以PID 1运行的系统和服务管理器，并启动了系统的其余部分.  如果编写容器解决方案，请考虑支持以下接口.
* [Nulecule Specification](https://github.com/projectatomic/atomicapp/tree/master/docs/spec)  
Nulecule定义了用于打包复杂的多容器应用程序和服务的模式和模型，并引用了它们的所有依赖关系，包括容器映像中的编排元数据，以进行构建，部署，监视和主动管理.
* [Oracle microcontainer manifesto](https://blogs.oracle.com/developers/the-microcontainer-manifesto)  
这不是一种新的容器格式，而只是一种构造容器的特定方法，可以提高安全性和稳定性.
* [Cloud Native Application Bundle Specification](https://github.com/deislabs/cnab-spec)  
软件包格式规范，该规范描述了一种用于捆绑，安装和管理分布式应用程序的技术，该技术在设计上是不可知的.

## Clouds

* [Amazon EC2 Container Service ](https://aws.amazon.com/ecs/)   
容器管理服务支持Docker容器，并允许您在Amazon EC2实例的托管集群上轻松运行应用程序.
* [Google Cloud Platform](https://cloud.google.com/container-engine/)  
 在由Kubernetes支持的Google Cloud Platform上运行Docker容器.  Google容器引擎会根据声明的需求，在托管的虚拟机群集上主动调度您的容器. 
* [Jelastic](http://jelastic.com/)  
适用于DevOps的联合云解决方案中的无限PaaS和基于容器的IaaS.
* [Joyent](https://www.joyent.com/)  
适用于当今苛刻的实时Web和移动应用程序的高性能容器原生基础结构.
* [Kubernetes](http://kubernetes.io/)  
将Linux容器集群作为单个系统进行管理，以加快开发速度并简化操作.
* [Mesosphere](https://mesosphere.com/)  
 Mesosphere数据中心操作系统（DCOS）是一种新型的操作系统，可跨越数据中心或云中的所有计算机.  它提供了一种高度灵活，高度可扩展的方式，可以在共享资源上部署应用程序，服务和大数据基础架构.
* [OpenShift Origin](https://www.openshift.org/)  
OpenShift Origin是 [Kubernetes](http://kubernetes.io/)  针对连续的应用程序开发和多租户部署进行了优化.  Origin在Kubernetes的基础上增加了以开发人员和操作为中心的工具，以实现快速的应用程序开发，轻松的部署和扩展以及对大小团队的长期生命周期维护.
* [Warden](https://github.com/cloudfoundry/warden)  
 管理隔离的，短暂的和资源控制的环境.  Cloud Foundry的一部分-开放平台即服务项目.
* [Virtuozzo](https://virtuozzo.com)  
一个基于Virtuozzo容器构建的平台，可以轻松地在任何公共或私有云中的任何裸机或虚拟服务器之上运行，以自动化，优化和加速内部IT和开发流程.
* [Rancher](http://rancher.com/)  
 Rancher是一个完整的开源平台，用于在生产中部署和管理容器.  它包括商业支持的Kubernetes，Mesos和Docker Swarm发行版，使在任何基础架构上轻松运行容器化应用程序变得容易.
* [Docker Swarm](https://docs.docker.com/swarm)  
Docker Swarm是Docker的本机集群.
* [Azure Container Service](https://azure.microsoft.com/en-us/services/container-service/)  
Azure容器服务优化了专门针对Azure的流行开源工具和技术的配置.
* [CIAO](https://ciao-project.github.io/)  
 适用于Intel Clear Linux OS的Cloud Integrated Advanced Orchestrator. 
 * [Kontena](http://kontena.io)  
 Kontena是开发人员友好的开源平台，用于编排在Docker容器上运行的应用程序.  它简化了在任何基础架构上部署和运行容器化应用程序的过程.
* [Hyper.sh](https://hyper.sh)  
无服务器容器平台.
* [Alibaba Cloud Container Service](https://www.alibabacloud.com/fr/product/container-service)  
容器服务是一项高性能且可扩展的容器应用程序管理服务，使您能够使用Docker和Kubernetes管理容器化应用程序的生命周期.
* [Nomad](https://www.nomadproject.io/)  
  HashiCorp Nomad是一个单一的二进制文件，可以调度Linux，Windows和Mac上的应用程序和服务.  它是一个开放源代码调度程序，它使用声明性作业文件来调度虚拟化，容器化和独立的应用程序.

## Operating Systems

* [CoreOs](https://coreos.com/)  
专为集群部署而设计的轻量级Linux操作系统，可为最关键的应用程序提供自动化，安全性和可伸缩性.
* [RancherOS](http://rancher.com/rancher-os/)  
RancherOS是一个小型Linux发行版，可将整个操作系统作为Docker容器运行.
* [Project Atomic](http://www.projectatomic.io/)  
 Project Atomic为您的Linux Docker Kubernetes（LDK）应用程序堆栈提供了最佳平台.  使用不可变的基础架构来部署和扩展您的容器化应用程序.
* [Snappy Ubuntu Core](https://www.ubuntu.com/cloud/snappy)  
Ubuntu Core是用于大规模云容器部署的理想系统，可将事务更新带入全球最受欢迎的容器平台.
* [ResinOS](https://resinos.io/)  
专为容器量身定制的主机操作系统，其可靠性经过设计并在生产中得到证明.
* [Photon](https://github.com/vmware/photon)  
 Photon OS是最小的Linux容器主机，其设计占用空间小且已针对VMware平台进行了调整.  Photon旨在邀请围绕虚拟化环境中运行的容器化和Linux应用程序进行协作.
* [Clear Linux Project](https://clearlinux.org/documentation/clear-linux/get-started)  
适用于英特尔架构的Clear Linux项目是针对各种云使用案例而构建的发行版.
* [CargOS](https://cargos.io/)  
 CargOS是面向Docker主机的新型轻量级开源平台，旨在提高速度，可管理性和安全性.  这些版本是针对64位Intel / AMD CPU构建的.
* [OSv](http://osv.io/)  
 OSv是专为云设计的开源操作系统.  从头开始构建，可轻松实现部署和管理，并具有卓越的性能.
* [HypriotOS](http://blog.hypriot.com/about/)  
 为运行Docker而优化的基于Debian的最小操作系统.  这使得在任何Raspberry Pi上使用Docker变得非常容易. 
* [MCL](https://mcl.host)  
 MCL（* Minimal Container Linux *）是专为运行容器而设计的从零开始的最小Linux操作系统.  它占用的空间约为50MB，可在几秒钟内启动.  目前已针对运行Docker进行了优化.

## Hypervisors

* [Docker](https://github.com/veggiemonk/awesome-docker#cloud-infrastructure)  
 为开发人员和系统管理员提供分布式应用程序的开放平台.  **事实上的标准**.
* [LXD](https://github.com/lxc/lxd)  
基于liblxc的守护程序提供了REST API来管理LXC容器.
* [OpenVZ](https://openvz.org/Main_Page)  
 OpenVZ是Linux的基于容器的虚拟化.  OpenVZ在单个物理服务器上创建多个安全的，隔离的Linux容器（也称为VE或VPS），以提高服务器利用率并确保应用程序不冲突.
* [MultiDocker](https://github.com/marty90/multidocker)  
创建一个安全的多用户Docker计算机，其中每个用户都被隔离到一个独立的容器中.
* [Lithos](https://github.com/tailhook/lithos/)  
Lithos is a process supervisor and containerizer for running services. It is not intended to be system init, but rather tries to be a base tool to build container orchestration.
* [containerd](https://containerd.io/)  
容器运行时可以管理完整的容器生命周期-从图像传输/存储到容器执行，监督和联网.

## Containers

* [runc](https://github.com/opencontainers/runc)  
runc是一个CLI工具，用于根据OCS规范生成和运行容器.
* [Bocker](https://github.com/p8952/bocker)  
Docker在大约100行bash中实现.
* [Rocket](https://github.com/coreos/rkt)  
 rkt（发音为“ rock-it”）是用于在Linux上运行应用程序容器的CLI.  rkt设计为可组合，安全且快速的.  基于AppC规范.
* [LXC](https://github.com/lxc/lxc)  
 LXC是众所周知的工具，模板，库和语言绑定集.  它的级别很低，非常灵活，几乎涵盖了上游内核支持的每个遏制功能.
* [Vagga](https://github.com/tailhook/vagga)  
Vagga是一个受Vagrant和Docker启发的全用户空间容器引擎，专门用于开发环境.
* [libct](https://github.com/xemul/libct)  
Libct是一个容器管理库，它为前端程序提供便捷的API，以在整个生命周期内对容器进行统治.
* [libvirt](https://libvirt.org/drvlxc.html)  
与最新版本的Linux（和其他操作系统）的虚拟化功能进行交互的大型工具包.
* [systemd-nspawn](https://wiki.archlinux.org/index.php/Systemd-nspawn)  
 生成用于调试，测试和构建的名称空间容器.  部分 [systemd](https://wiki.freedesktop.org/www/Software/systemd/).
* [porto](https://github.com/yandex/porto)  
Porto的主要目标是通过几种Linux内核机制（例如cgroup，名称空间，安装，网络等）创建一个方便，可靠的接口.
* [udocker](https://github.com/indigo-dc/udocker)  
一个基本的用户工具，无需root特权即可在批处理或交互式系统中执行简单容器.
* [Let Me Contain That For You](https://github.com/google/lmctfy)  
LMCTFY是Google容器堆栈的开源版本，它提供Linux应用程序容器.
* [cc-oci-runtime](https://github.com/01org/cc-oci-runtime)  
Intel Clear Linux OCI (Open Containers Initiative) compatible runtime.
* [railcar](https://github.com/oracle/railcar)  
 Railcar是opencontainers计划的运行时规范的生锈实现.  它与参考实现runc相似，但是出于内存安全性考虑，它完全是在rust中实现的，而不需要垃圾回收器或多个线程的开销.
* [Kata Containers](https://katacontainers.io/)  
Kata Containers是一个新的开源项目，它构建了非常轻巧的虚拟机，可以无缝地插入到容器生态系统中.
* [plash](https://github.com/ihucos/plash/)  
轻巧，无根的容器.
* [runv](https://github.com/hyperhq/runv)  
 基于虚拟机监控程序（KVM，Xen，QEMU）的OCI运行时.  通过隔离实现安全性.
* [podman](https://github.com/containers/libpod)  
全面管理容器生命周期.
* [firecracker](https://github.com/firecracker-microvm/firecracker)  
Firecracker在称为microVM的轻型虚拟机中运行工作负载，该虚拟机将硬件虚拟化技术提供的安全性和隔离属性与容器的速度和灵活性结合在一起.

## Sandboxes

* [Firejail](https://l3net.wordpress.com/projects/firejail/)  
Firejail是一个SUID沙箱程序，它使用Linux名称空间，seccomp-bpf和Linux功能来限制不受信任的应用程序的运行环境，从而降低了违反安全性的风险.
* [NsJail](https://github.com/google/nsjail)  
 NsJail是Linux的进程隔离工具.  它利用了Linux内核的命名空间，资源控制和seccomp-bpf syscall筛选器子系统.
* [Subuser](https://github.com/subuser-security/subuser)  
使用Docker保护Linux桌面.
* [Snappy](https://wiki.ubuntu.com/SecurityTeam/Specifications/SnappyConfinement)  
Snappy Ubuntu Core是具有事务更新的Ubuntu的新版本-最小的服务器映像，具有与当今Ubuntu相同的库，但是通过更简单的机制提供了应用程序.
* [xdg-app](https://wiki.gnome.org/Projects/SandboxedApps)  
xdg-app是一个用于在Linux上构建，分发和运行沙盒桌面应用程序的系统.
* [Bubblewrap](https://github.com/projectatomic/bubblewrap)  
使用没有root特权的Linux名称空间在沙箱中运行应用程序，并通过setuid二进制文件提供用户命名空间.
* [singularity](https://github.com/singularityware/singularity)  
Linux的通用应用程序容器.

## Partial Access

* [nsenter](http://man7.org/linux/man-pages/man1/nsenter.1.html)  
 使用其他进程的名称空间运行程序.  util-linux的一部分.
* [ip-netns](http://man7.org/linux/man-pages/man8/ip-netns.8.html)  
 进程网络名称空间管理.  iproute2的一部分.
* [unshare](http://man7.org/linux/man-pages/man1/unshare.1.html)  
 使用父级未共享的某些名称空间运行程序.  util-linux的一部分.
* [python-nsenter](https://github.com/zalando/python-nsenter)  
该Python软件包允许通过执行“ setns”系统调用来输入Linux内核名称空间（安装，IPC，网络，PID，用户和UTS）.
* [butter](https://pypi.python.org/pypi/butter)  
Python库可与具有异步支持的底层Linux功能（inotify，fanotify，timerfd，signalfd，eventfd，容器）接口.
* [pyspaces](https://github.com/Friz-zy/pyspaces)  
通过带有纯python的glibc与Linux名称空间配合使用.
* [CRIU](https://criu.org/Main_Page)  
 Checkpoint /在用户空间中还原是Linux操作系统的软件工具.  使用此工具，您可以冻结一个正在运行的应用程序（或其一部分），并将其作为文件集合检查到硬盘上.  CRIU与Docker和LXC集成以实现容器的实时迁移.
* [Moby](https://github.com/moby/moby)  
Docker创建的用于容器软件的工具包组件的“乐高套装”.

## Filesystem

* [container-diff](https://github.com/GoogleCloudPlatform/container-diff)  
分析和比较容器图像的工具.
* [buildah](https://github.com/projectatomic/buildah)  
有助于构建OCI容器映像的工具.
* [skopeo](https://github.com/projectatomic/skopeo)  
使用远程图像注册表-检索信息，图像，签名内容.
* [img](https://github.com/jessfraz/img)  
独立，无守护程序，无特权的Dockerfile和OCI兼容的容器映像生成器.
* [dgr](https://github.com/blablacar/dgr)  
命令行实用程序旨在基于配置约定在运行时构建和配置App Containers图像（ACI）和App Container Pod（POD）.
* [Whaler](https://github.com/P3GLEG/Whaler)  
Whaler旨在将Docker映像反向工程到创建它的Dockerfile中.
* [dive](https://github.com/wagoodman/dive)  
探索docker映像中每个图层的工具.
* [go-containerregistry](https://github.com/google/go-containerregistry)  
使用库和CLI来处理容器注册表.
* [kaniko](https://github.com/GoogleContainerTools/kaniko)  
kaniko是从容器或Kubernetes集群内部的Dockerfile构建容器映像的工具.
* [umoci](https://umo.ci/)
umoci是用于处理OCI容器图像的工具，可以用作基本的构建工具.

## Dashboard

* [LXC-Web-Panel](https://lxc-webpanel.github.io/)  
Ubuntu上LXC的Web面板.
* [Liman](https://github.com/salihciftci/liman)  
基本的docker监控Web应用程序.

## Best practices

* [The Twelve-Factor App](https://12factor.net/)  
十二要素应用程序是一种构建软件即服务应用程序的方法.
* [Container Best Practices](http://docs.projectatomic.io/container-best-practices/)  
一个协作项目，用于记录Project Atomic中基于容器的应用程序体系结构，创建和管理.

## Security

### Tools

* [Docker bench security](https://github.com/docker/docker-bench-security)  
Docker Bench for Security是一个脚本，用于检查有关在生产环境中部署Docker容器的数十种常见最佳实践.
* [CoreOS Clair](https://coreos.com/blog/vulnerability-analysis-for-containers/)  
容器的开源漏洞分析.
* [bane](https://github.com/jfrazelle/bane)  
用于Docker容器的自定义AppArmor配置文件生成器.
* [OpenSCAP](https://github.com/OpenSCAP/container-compliance)  
OpenSCAP生态系统提供了多种工具来协助管理员和审核员评估，衡量和实施安全基准.
* [drydock](https://github.com/zuBux/drydock)  
Drydock提供了使用可编辑审核模板评估Docker守护程序配置和容器安全性的灵活方法.
* [trireme](https://www.aporeto.com/trireme/)  
Docker和Kubernetes的分段安全性.
* [goss](https://github.com/aelsabbahy/goss)  
快速简便的服务器测试/验证.
* [sockguard](https://github.com/buildkite/sockguard)  
docker.sock的代理，用于执行访问控制和隔离的特权.
* [gvisor](https://github.com/google/gvisor)  
 gVisor是用Go编写的用户空间内核，它实现了Linux系统表面的很大一部分.  它包括一个名为runsc的开放式容器计划（OCI）运行时，它在应用程序和主机内核之间提供隔离边界.  runsc运行时与Docker和Kubernetes集成，使运行沙盒容器变得简单.
* [docker-explorer](https://github.com/google/docker-explorer/)  
一种帮助对离线Docker进行取证的工具.


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

* always untrusted -> know it
* suid位-&gt;用nosuid装载
*限制可用的系统调用-&gt; seccomp-bpf，grsec
 *泄漏到另一个容器（名称空间，文件系统中的错误）-&gt;每个容器内部具有不同uid的用户名称空间：容器中为1000-外部为14293和15398；  安全模块，例如selinux或apparmor

2）系统服务，例如cron，ssh

*以root身份运行-&gt;通过堡垒主机或虚拟机隔离
*使用/ dev-&gt;“设备”控制组  
默认情况下在容器中创建以下设备节点.  
Docker映像还通过nodev挂载，这意味着即使在映像中预先创建了设备节点，容器中的进程也无法使用该设备节点与内核进行通信.  
/dev/console,/dev/null,/dev/zero,/dev/full,/dev/tty*,/dev/urandom,/dev/random,/dev/fuse
* root调用-&gt;功能（cap_sys_admin警告！）  
以下是Docker使用的当前功能列表：chown，dac_override，fowner，kill，setgid，setuid，setpcap，net_bind_service，net_raw，sys_chroot，mknod，setfcap和audit_write.  
Docker删除了其中一些功能，其中包括：  
CAP_SETPCAP修改流程功能  
CAP_SYS_MODULE插入/删除内核模块   
CAP_SYS_RAWIO修改内核内存  
CAP_SYS_PACCT配置流程记帐  
CAP_SYS_NICE修改进程的优先级  
CAP_SYS_RESOURCE覆盖资源限制  
CAP_SYS_TIME修改系统时钟  
CAP_SYS_TTY_CONFIG配置tty设备  
CAP_AUDIT_WRITE写入审核日志  
CAP_AUDIT_CONTROL配置审核子系统  
CAP_MAC_OVERRIDE忽略内核MAC策略  
CAP_MAC_ADMIN配置MAC配置  
CAP_SYSLOG修改内核printk行为  
CAP_NET_ADMIN配置网络  
CAP_SYS_ADMIN全部捕获  
 使用/ proc，/ sys-&gt;重新安装ro，放下cap_sys_admin;  安全模块，例如selinux或apparmor；  这些文件系统的某些部分是“可识别命名空间的”  
Docker将这些文件系统作为“只读”安装点安装到容器中.  
 .  / sys  
 .  / proc / sys  
 .  / PROC / SysRq的触发  
 .  / proc / irq  
 .  / proc /总线  
写入时复制文件系统  
 Docker使用写时复制文件系统.  这意味着容器可以使用与容器基础相同的文件系统映像.  当容器将内容写入映像时，它将被写入特定于容器的文件系统.  这样可以防止一个容器看到另一个容器的更改，即使它们已写入同一文件系统映像.  同样重要的是，一个容器不能更改图像内容以影响另一个容器中的过程.
* uid 0-&gt;用户名称空间，uid 0映射到外面的随机uid

3）系统服务，例如设备，网络，文件系统

 * root-&gt;更多服务应在外部主机上运行；  隔离敏感功能，作为非特权上下文运行
*完整权限-&gt;在内核级别隔离

4）内核驱动程序，网络堆栈，安全策略

*绝对特权-&gt;在单独的vm中运行

5）像不变的基础设施一般

*容器是ro
*写到单独的rw nosuid小部分

[src](http://www.slideshare.net/jpetazzo/docker-linux-containers-lxc-and-security)  
[src](https://opensource.com/business/14/9/security-for-docker)

### Technologies for security

 情况更好.  例如，大多数现代容器技术都可以利用Linux的内置安全工具，例如：  
[AppArmor](http://wiki.apparmor.net/index.php/Main_Page), [SELinux](http://selinuxproject.org/page/Main_Page) 和 [Seccomp](http://man7.org/linux/man-pages/man2/seccomp.2.html) 政策；  
[Grsecurity](https://grsecurity.net/);  
[Control groups (cgroups)](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Resource_Management_Guide/ch01.html);  
[Kernel namespaces](http://man7.org/linux/man-pages/man7/namespaces.7.html)  
[src](http://www.itworld.com/article/2920349/security/for-containers-security-is-problem-1.html)

当然，您正在部署seccomp，但是您不能在容器中使用selinux，因为该策略不是按命名空间进行的（?? lxc对每个容器使用apparmore ...）  
[sVirt](http://selinuxproject.org/page/SVirt) -selinux for sqm  
[src](https://mjg59.dreamwidth.org/33170.html)

主要内核子系统的命名空间不像以下那样：  
-SELinux  
-Cgroups  
-/ sys下的文件系统  
-/ proc / sys，/ proc / sysrq触发，/ proc / irq，/ proc /总线

设备未命名空间：  
-/ dev / mem  
-/ dev / sd *文件系统设备  
-内核模块

如果您可以通过特权进程来通信或攻击其中之一，则可以拥有该系统.  
[src](https://opensource.com/business/14/7/docker-security-selinux)

## Another Information Sources

* [sysdig-container-ecosystem](https://github.com/draios/sysdig-container-ecosystem)  
 至少可以说，围绕容器和微服务出现的令人敬畏的新技术生态系统可能会让人有些不知所措.  我们认为我们可能可以提供帮助：欢迎来到容器生态系统项目.
* [doger.io](http://doger.io/)  
 此页面试图记录Linux上容器的来龙去脉.  这不仅限于希望在自己的代码中实现容器或使用类似容器的功能的程序员，而且还包括Sysadmins和Users，他们希望更多地了解容器在幕后的工作方式. 
