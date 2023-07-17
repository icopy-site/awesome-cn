<div class="github-widget" data-repo="Friz-zy/awesome-linux-containers"></div>
## Awesome Linux Containers

[![#StandWithBelarus](https://img.shields.io/badge/Belarus-red?label=%23%20Stand%20With&labelColor=white&color=red)
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ea/Presidential_Standard_of_Belarus_%28fictional%29.svg/240px-Presidential_Standard_of_Belarus_%28fictional%29.svg.png" width="20" height="20" alt="Voices From Belarus" />](https://bysol.org/en/) [![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/StandWithUkraine.svg)](https://vshymanskyy.github.io/StandWithUkraine)

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)



## About the Author

大家好！ 我叫 Filipp，自 2012 年以来一直从事高负载分发系统和服务、安全、监控、持续部署和发布管理（DevOps 领域）方面的工作.

我的热情之一是开发 DevOps 解决方案并为开源社区做出贡献. 通过分享我的知识和经验，我努力为自己和他人节省时间，同时培养协作和学习的文化.

由于参加活动，我不得不离开我的祖国白俄罗斯 [protests against the oppressive regime of dictator Lukashenko](https://en.wikipedia.org/wiki/2020%E2%80%932021_Belarusian_protests)与普京保持着密切的联系. 从那时起，我开始在其他国家尝试从零开始建立自己的生活.

如果您正在寻找熟练的 DevOps 领导或架构师来增强您的项目，我邀请您与我联系 [LinkedIn](https://www.linkedin.com/in/filipp-frizzy-289a0360/) 或探索我的宝贵贡献 [GitHub](https://github.com/Friz-zy/) . 让我们合作并共同创建一些很酷的解决方案:)

## Foundations

* [OPEN CONTAINER INITIATIVE](https://www.opencontainers.org/)  
开放容器计划是一个轻量级的开放治理结构，将在 Linux 基金会的支持下形成，其明确目的是围绕容器格式和运行时创建开放行业标准.
* [Cloud Native Computing Foundation](https://cncf.io/)  
云原生计算基金会将创建并推动采用一组新的通用容器技术，这些技术以技术优点和最终用户价值为基础，并受到互联网规模计算的启发.
* [Cloud Foundry Foundation](https://www.cloudfoundry.org/foundation/)  
The Cloud is our foundry.

## Specifications

* [Open Container Specifications](https://github.com/opencontainers/specs)  
该项目是开放容器计划规范的编写地. 这是一个正在进行的工作. 
* [App Container basics](https://github.com/coreos/rkt/blob/master/Documentation/app-container.md)  
应用程序容器 (appc) 是一个开放规范，定义了如何在容器中运行应用程序的几个方面：图像格式、运行时环境和发现协议.
* [Systemd Container Interface](https://wiki.freedesktop.org/www/Software/systemd/ContainerInterface/)  
 Systemd 是 Linux 系统的一套基本构建块. 它提供了一个以 PID 1 运行并启动系统其余部分的系统和服务管理器. 如果您编写容器解决方案，请考虑支持以下接口.
* [Nulecule Specification](https://github.com/projectatomic/atomicapp/tree/master/docs/spec)  
Nulecule 定义了一种用于打包复杂的多容器应用程序和服务的模式和模型，引用其所有依赖项，包括容器映像中用于构建、部署、监控和主动管理的编排元数据.
* [Oracle microcontainer manifesto](https://blogs.oracle.com/developers/the-microcontainer-manifesto)  
这并不是一种新的容器格式，而只是一种构建容器的特定方法，可以提供更好的安全性和稳定性.
* [Cloud Native Application Bundle Specification](https://github.com/deislabs/cnab-spec)  
一种包格式规范，描述了用于捆绑、安装和管理分布式应用程序的技术，这些应用程序在设计上与云无关.

## Clouds

* [Amazon EC2 Container Service ](https://aws.amazon.com/ecs/)   
容器管理服务支持 Docker 容器，并允许您在托管的 Amazon EC2 实例集群上轻松运行应用程序.
* [Google Cloud Platform](https://cloud.google.com/container-engine/)  
Run Docker containers on Google Cloud Platform, powered by Kubernetes. Google Container Engine actively schedules your containers, based on declared needs, on a managed cluster of virtual machines. 
* [Jelastic](http://jelastic.com/)  
针对 DevOps 的联合云解决方案中的无限 PaaS 和基于容器的 IaaS.
* [Joyent](https://www.joyent.com/)  
适用于当今要求严格的实时 Web 和移动应用程序的高性能容器原生基础设施.
* [Kubernetes](http://kubernetes.io/)  
将 Linux 容器集群作为单个系统进行管理，以加速开发并简化运维.
* [Mesosphere](https://mesosphere.com/)  
 Mesosphere 数据中心操作系统 (DCOS) 是一种新型操作系统，涵盖数据中心或云中的所有计算机. 它提供了一种在共享资源上部署应用程序、服务和大数据基础设施的高度弹性和高度可扩展的方式.
* [OpenShift Origin](https://www.openshift.org/)  
OpenShift Origin 是一个发行版 [Kubernetes](http://kubernetes.io/) 针对持续应用程序开发和多租户部署进行了优化.  Origin 在 Kubernetes 之上添加了以开发人员和运营为中心的工具，以便为小型和大型团队提供快速应用程序开发、轻松部署和扩展以及长期生命周期维护.
* [Warden](https://github.com/cloudfoundry/warden)  
管理隔离、短暂且资源受控的环境.  Cloud Foundry 的一部分 - 开放平台即服务项目.
* [Virtuozzo](https://virtuozzo.com)  
一个基于 Virtuozzo 容器构建的平台，可以在任何公共或私有云中的任何裸机或虚拟服务器上轻松运行，以自动化、优化和加速内部 IT 和开发流程.
* [Rancher](http://rancher.com/)  
 Rancher 是一个完整的开源平台，用于在生产中部署和管理容器. 它包括商业支持的 Kubernetes、Mesos 和 Docker Swarm 发行版，使您可以轻松地在任何基础设施上运行容器化应用程序.
* [Docker Swarm](https://docs.docker.com/engine/swarm/)  
Docker Swarm 是 Docker 的原生集群.
* [Azure Container Service](https://azure.microsoft.com/en-us/services/container-service/)  
Azure 容器服务专门针对 Azure 优化了流行的开源工具和技术的配置.
* [CIAO](https://ciao-project.github.io/)  
 适用于英特尔 Clear Linux 操作系统的云集成高级编排器. 
* [Alibaba Cloud Container Service](https://www.alibabacloud.com/fr/product/container-service)  
容器服务是一种高性能、可扩展的容器应用管理服务，支持您使用Docker和Kubernetes来管理容器化应用的生命周期.
* [Nomad](https://www.nomadproject.io/)  
  HashiCorp Nomad 是一个单一二进制文件，可在 Linux、Windows 和 Mac 上调度应用程序和服务. 它是一个开源调度程序，使用声明性作业文件来调度虚拟化、容器化和独立应用程序.

## Operating Systems

* [CoreOs](https://coreos.com/)  
专为集群部署而设计的轻量级 Linux 操作系统，为您最关键的应用程序提供自动化、安全性和可扩展性.
* [RancherOS](http://rancher.com/rancher-os/)  
RancherOS 是一个小型 Linux 发行版，它将整个操作系统作为 Docker 容器运行.
* [Project Atomic](http://www.projectatomic.io/)  
 Project Atomic 为您的 Linux Docker Kubernetes (LDK) 应用程序堆栈提供最佳平台. 使用不可变的基础设施来部署和扩展容器化应用程序.
* [Snappy Ubuntu Core](https://www.ubuntu.com/cloud/snappy)  
Ubuntu Core is the perfect system for large-scale cloud container deployments, bringing transactional updates to the world’s favourite container platform.
* [ResinOS](https://resinos.io/)  
专为容器量身定制的主机操作系统，专为可靠性而设计，并已在生产中得到验证.
* [Photon](https://github.com/vmware/photon)  
 Photon OS 是一个最小的 Linux 容器主机，设计占用空间小，并针对 VMware 平台进行了调整.  Photon 旨在邀请围绕在虚拟化环境中运行容器化和 Linux 应用程序进行协作.
* [Clear Linux Project](https://clearlinux.org)  
适用于英特尔架构的 Clear Linux 项目是专为各种云用例构建的发行版.
* [CargOS](https://cargos.io/)  
 CargOS 是一个适用于 Docker 主机的新型轻量级开源平台，旨在提高速度、可管理性和安全性. 版本是针对 64 位 Intel/AMD CPU 构建的.
* [OSv](http://osv.io/)  
 OSv是专为云设计的开源操作系统. 从头开始构建，可轻松部署和管理，并具有卓越的性能.
* [HypriotOS](http://blog.hypriot.com/about/)  
基于 Debian 的最小操作系统，针对运行 Docker 进行了优化. 它使得在任何 Raspberry Pi 上使用 Docker 变得非常容易. 
* [MCL](https://mcl.host)  
 MCL（*最小容器 Linux*）是一个专门为运行容器而设计的从头开始的最小 Linux 操作系统. 它占用空间小，约为 50MB，并且可在几秒钟内启动. 目前它已针对运行 Docker 进行了优化.

## Hypervisors

* [Docker](https://github.com/veggiemonk/awesome-docker#cloud-infrastructure)  
面向开发人员和系统管理员的分布式应用程序的开放平台.  **事实上的标准**.
* [LXD](https://github.com/lxc/lxd)  
基于 liblxc 的守护进程提供 REST API 来管理 LXC 容器.
* [OpenVZ](https://openvz.org/)  
 OpenVZ 是适用于 Linux 的基于容器的虚拟化.  OpenVZ 在单个物理服务器上创建多个安全、隔离的 Linux 容器（也称为 VE 或 VPS），从而实现更好的服务器利用率并确保应用程序不会发生冲突.
* [MultiDocker](https://github.com/marty90/multidocker)  
创建一个安全的多用户 Docker 机器，其中每个用户都被隔离到一个独立的容器中.
* [Lithos](https://github.com/tailhook/lithos/)  
 Lithos 是一个用于运行服务的进程管理器和容器化器. 它并不是要成为系统初始化工具，而是试图成为构建容器编排的基本工具.
* [containerd](https://containerd.io/)  
容器运行时可以管理完整的容器生命周期 - 从图像传输/存储到容器执行、监管和网络.

## Containers

* [runc](https://github.com/opencontainers/runc)  
runc 是一个 CLI 工具，用于根据 OCS 规范生成和运行容器.
* [Bocker](https://github.com/p8952/bocker)  
Docker 在大约 100 行 bash 中实现.
* [Rocket](https://github.com/coreos/rkt)  
 rkt（发音为“rock-it”）是一个用于在 Linux 上运行应用程序容器的 CLI.  rkt 被设计为可组合、安全且快速. 基于AppC规范.
* [LXC](https://github.com/lxc/lxc)  
 LXC 是众所周知的工具、模板、库和语言绑定集. 它的级别相当低，非常灵活，几乎涵盖了上游内核支持的所有遏制功能.
* [Vagga](https://github.com/tailhook/vagga)  
Vagga 是一个完全用户空间的容器引擎，受到 Vagrant 和 Docker 的启发，专门用于开发环境.
* [libct](https://github.com/xemul/libct)  
Libct 是一个容器管理库，它为前端程序提供方便的 API，以在容器的整个生命周期中管理容器.
* [libvirt](https://libvirt.org/drvlxc.html)  
一个与最新版本的 Linux（和其他操作系统）的虚拟化功能进行交互的大型工具包.
* [systemd-nspawn](https://wiki.archlinux.org/index.php/Systemd-nspawn)  
生成用于调试、测试和构建的命名空间容器. 部分 [systemd](https://wiki.freedesktop.org/www/Software/systemd/).
* [porto](https://github.com/yandex/porto)  
Porto 的主要目标是在多种 Linux 内核机制（例如 cgroup、命名空间、挂载、网络等）上创建一个方便、可靠的接口.
* [udocker](https://github.com/indigo-dc/udocker)  
一个基本的用户工具，无需root权限即可在批处理或交互式系统中执行简单的容器.
* [Let Me Contain That For You](https://github.com/google/lmctfy)  
LMCTFY 是 Google 容器堆栈的开源版本，提供 Linux 应用程序容器.
* [cc-oci-runtime](https://github.com/01org/cc-oci-runtime)  
Intel Clear Linux OCI（开放容器计划）兼容运行时.
* [railcar](https://github.com/oracle/railcar)  
 Railcar 是 opencontainers 计划运行时规范的 Rust 实现. 它与参考实现 runc 类似，但为了内存安全，它完全在 Rust 中实现，不需要垃圾收集器或多线程的开销.
* [Kata Containers](https://katacontainers.io/)  
Kata Containers 是一个新的开源项目，构建可无缝插入容器生态系统的极其轻量级的虚拟机.
* [plash](https://github.com/ihucos/plash/)  
轻量级、无根容器.
* [runv](https://github.com/hyperhq/runv)  
用于 OCI 的基于虚拟机管理程序（KVM、Xen、QEMU）的运行时. 隔离确保安全.
* [podman](https://github.com/containers/libpod)  
容器生命周期的全面管理.
* [firecracker](https://github.com/firecracker-microvm/firecracker)  
Firecracker 在称为 microVM 的轻量级虚拟机中运行工作负载，该虚拟机将硬件虚拟化技术提供的安全性和隔离特性与容器的速度和灵活性相结合.
* [sysbox](https://github.com/nestybox/sysbox)  
Sysbox 是一个“runc”，它创建安全（无根）容器/pod，不仅运行微服务，还无缝运行在虚拟机（例如 systemd、Docker 和 Kubernetes）中的大多数工作负载.
* [youki](https://github.com/containers/youki)  
用 Rust 编写的容器运行时.
* [footloose](https://github.com/weaveworks/footloose)  
看起来像虚拟机的容器.

## Sandboxes

* [Firejail](https://l3net.wordpress.com/projects/firejail/)  
Firejail 是一个 SUID 沙箱程序，它通过使用 Linux 命名空间、seccomp-bpf 和 Linux 功能来限制不受信任的应用程序的运行环境，从而降低安全漏洞的风险.
* [NsJail](https://github.com/google/nsjail)  
 NsJail 是 Linux 的进程隔离工具. 它利用 Linux 内核的命名空间、资源控制和 seccomp-bpf 系统调用过滤器子系统.
* [Subuser](https://github.com/subuser-security/subuser)  
使用 Docker 保护 Linux 桌面.
* [Snappy](https://wiki.ubuntu.com/SecurityTeam/Specifications/SnappyConfinement)  
Snappy Ubuntu Core 是带有事务性更新的 Ubuntu 的新版本 - 一个最小的服务器映像，具有与今天的 Ubuntu 相同的库，但应用程序是通过更简单的机制提供的.
* [xdg-app](https://wiki.gnome.org/Projects/SandboxedApps)  
xdg-app 是一个用于在 Linux 上构建、分发和运行沙盒桌面应用程序的系统.
* [Bubblewrap](https://github.com/projectatomic/bubblewrap)  
使用 Linux 命名空间在沙箱中运行应用程序，无需 root 权限，用户命名空间通过 setuid 二进制文件提供.
* [singularity](https://github.com/singularityware/singularity)  
Linux 的通用应用程序容器.
* [Lxroot](https://github.com/parke/lxroot)  
对于 Linux 上的非 root 用户来说，Lxroot 是 chroot 和/或 Docker 的灵活、轻量且更安全的替代方案.

## Partial Access

* [nsenter](http://man7.org/linux/man-pages/man1/nsenter.1.html)  
使用其他进程的命名空间运行程序.  util-linux 的一部分.
* [ip-netns](http://man7.org/linux/man-pages/man8/ip-netns.8.html)  
进程网络命名空间管理.  iproute2 的一部分.
* [unshare](http://man7.org/linux/man-pages/man1/unshare.1.html)  
使用与父级不共享的某些名称空间运行程序.  util-linux 的一部分.
* [python-nsenter](https://github.com/zalando/python-nsenter)  
这个Python包允许通过执行“setns”系统调用进入Linux内核命名空间（mount、IPC、net、PID、user和UTS）.
* [butter](https://pypi.python.org/pypi/butter)  
Python 库，用于连接低级 Linux 功能（inotify、fanotify、timerfd、signalfd、eventfd、容器），并支持 asyncio.
* [pyspaces](https://github.com/Friz-zy/pyspaces)  
通过 glibc 和纯 python 与 Linux 命名空间配合使用.
* [CRIU](https://criu.org/Main_Page)  
 Checkpoint/Restore In Userspace 是一款适用于 Linux 操作系统的软件工具. 使用此工具，您可以冻结正在运行的应用程序（或其一部分）并将其作为文件集合检查点到硬盘驱动器.  CRIU与Docker、LXC集成，实现容器的实时迁移.
* [Moby](https://github.com/moby/moby)  
由 Docker 创建的容器软件的工具包组件的“乐高集”.

## Filesystem

* [container-diff](https://github.com/GoogleCloudPlatform/container-diff)  
用于分析和比较容器镜像的工具.
* [buildah](https://github.com/projectatomic/buildah)  
一个有助于构建 OCI 容器镜像的工具.
* [skopeo](https://github.com/projectatomic/skopeo)  
使用远程图像注册表 - 检索信息、图像、签名内容.
* [img](https://github.com/jessfraz/img)  
独立、无守护程序、无特权的 Dockerfile 和 OCI 兼容容器映像生成器.
* [dgr](https://github.com/blablacar/dgr)  
命令行实用程序旨在基于约定优于配置在运行时构建和配置应用程序容器映像 (ACI) 和应用程序容器 Pod (POD).
* [Whaler](https://github.com/P3GLEG/Whaler)  
Whaler 旨在将 Docker 镜像逆向工程到创建它的 Dockerfile 中.
* [dive](https://github.com/wagoodman/dive)  
用于探索 docker 镜像中每一层的工具.
* [go-containerregistry](https://github.com/google/go-containerregistry)  
用于处理容器注册表的 Go 库和 CLI.
* [kaniko](https://github.com/GoogleContainerTools/kaniko)  
Kaniko 是一个在容器或 Kubernetes 集群内从 Dockerfile 构建容器映像的工具.
* [umoci](https://umo.ci/)  
Umoci 是一个操作 OCI 容器镜像的工具，可以用作基本的构建工具.
* [docker pushrm](https://github.com/christian-korneck/docker-pushrm)  
一个 Docker CLI 插件，可让您将 README.md 文件从当前目录推送到容器注册表. 支持 Docker Hub、Quay 和 Harbor.


## Dashboard

* [LXC-Web-Panel](https://lxc-webpanel.github.io/)  
Ubuntu 上 LXC 的 Web 面板.
* [Liman](https://github.com/salihciftci/liman)  
基本的 docker 监控 Web 应用程序.
* [portainer](https://github.com/portainer/portainer)  
轻量级 Docker 管理 UI.
* [swarmpit](https://github.com/swarmpit/swarmpit)  
轻量级、适合移动设备的 Docker Swarm 管理 UI.

## Best practices

* [The Twelve-Factor App](https://12factor.net/)  
十二要素应用程序是一种构建软件即服务应用程序的方法.
* [Container Best Practices](http://docs.projectatomic.io/container-best-practices/)  
一个协作项目，用于记录 Project Atomic 中基于容器的应用程序架构、创建和管理.

## Security

### Tools

* [Docker bench security](https://github.com/docker/docker-bench-security)  
Docker Bench for Security 是一个脚本，用于检查在生产中部署 Docker 容器的数十种常见最佳实践.
* [CoreOS Clair](https://coreos.com/blog/vulnerability-analysis-for-containers/)  
容器的开源漏洞分析.
* [bane](https://github.com/jfrazelle/bane)  
用于 Docker 容器的自定义 AppArmor 配置文件生成器.
* [OpenSCAP](https://github.com/OpenSCAP/container-compliance)  
OpenSCAP 生态系统提供多种工具来协助管理员和审计员评估、测量和执行安全基线.
* [drydock](https://github.com/zuBux/drydock)  
Drydock 提供了一种使用可编辑审核模板评估 Docker 守护进程配置和容器安全性的灵活方法.
* [trireme](https://www.aporeto.com/trireme/)  
Docker 和 Kubernetes 的分段安全性.
* [goss](https://github.com/aelsabbahy/goss)  
快速、简单的服务器测试/验证.
* [sockguard](https://github.com/buildkite/sockguard)  
docker.sock 的代理，强制执行访问控制和隔离特权.
* [gvisor](https://github.com/google/gvisor)  
 gVisor 是一个用 Go 编写的用户空间内核，它实现了 Linux 系统表面的很大一部分. 它包括一个名为 runsc 的开放容器计划 (OCI) 运行时，它在应用程序和主机内核之间提供隔离边界.  runsc 运行时与 Docker 和 Kubernetes 集成，使运行沙盒容器变得简单.
* [docker-explorer](https://github.com/google/docker-explorer/)  
一个帮助取证离线 docker 收购的工具.
* [oci-seccomp-bpf-hook](https://github.com/containers/oci-seccomp-bpf-hook)  
用于跟踪系统调用并生成 seccomp 配置文件的 OCI 挂钩.

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
* [Don't expose the Docker socket (not even to a container)](https://www.lvh.io/posts/dont-expose-the-docker-socket-not-even-to-a-container/)
* [RedHat Blog](http://rhelblog.redhat.com/?s=container&submit=Search)
  - [Introduction to Linux Containers](https://access.redhat.com/articles/1353593)
  - [What’s Next for Containers? User Namespaces](http://rhelblog.redhat.com/2015/07/07/whats-next-for-containers-user-namespaces/#more-1004)
  - [Architecting Containers Part 1: Why Understanding User Space vs. Kernel Space Matters](http://rhelblog.redhat.com/2015/07/29/architecting-containers-part-1-user-space-vs-kernel-space/)
  - [Architecting Containers Part 2: Why the User Space Matters](http://rhelblog.redhat.com/2015/09/17/architecting-containers-part-2-why-the-user-space-matters-2/)
  - [Secure Your Containers with this One Weird Trick](http://rhelblog.redhat.com/2016/10/17/secure-your-containers-with-this-one-weird-trick/)
* [Why you shouldn't use ENV variables for secret data](https://diogomonica.com/2017/03/27/why-you-shouldnt-use-env-variables-for-secret-data/)
* [When to use-Docker alternatives rkt and LXD](http://searchitoperations.techtarget.com/tip/When-to-use-Docker-alternatives-rkt-and-LXD)
* [The container is a lie](https://platform.sh/blog/2020/the-container-is-a-lie/)

### Levels of security problems

1）常规申请

* 总是不受信任 -&gt; 知道这一点
* suid 位 -&gt; 使用 nosuid 挂载
* 限制可用的系统调用 -&gt; seccomp-bpf, grsec
 * 泄漏到另一个容器（命名空间、文件系统中的错误） -&gt; 每个容器内部具有不同 uid 的用户命名空间：容器内 1000 - 外部 14293 和 15398； 安全模块，如 selinux 或 apparmor

2）系统服务，如cron、ssh

* 以 root 身份运行 -&gt; 通过堡垒主机或虚拟机隔离
* 使用/dev -&gt;“设备”控制组  
容器中默认创建以下设备节点.  
Docker 镜像也使用 nodev 挂载，这意味着即使在镜像中预先创建了设备节点，容器内的进程也无法使用它与内核进行通信.  
/dev/console,/dev/null,/dev/zero,/dev/full,/dev/tty*,/dev/urandom,/dev/random,/dev/fuse
* root 调用 -&gt; 功能（cap_sys_admin 警告！）  
以下是 Docker 使用的当前功能列表：chown、dac_override、fowner、kill、setgid、setuid、setpcap、net_bind_service、net_raw、sys_chroot、mknod、setfcap 和audit_write.  
Docker 删除了其中一些功能，包括：  
CAP_SETPCAP 修改进程能力  
CAP_SYS_MODULE 插入/删除内核模块   
CAP_SYS_RAWIO 修改内核内存  
CAP_SYS_PACCT 配置进程记帐  
CAP_SYS_NICE 修改进程优先级  
CAP_SYS_RESOURCE 覆盖资源限制  
CAP_SYS_TIME 修改系统时钟  
CAP_SYS_TTY_CONFIG 配置 tty 设备  
CAP_AUDIT_WRITE 写入审核日志  
CAP_AUDIT_CONTROL 配置审计子系统  
CAP_MAC_OVERRIDE 忽略内核 MAC 策略  
CAP_MAC_ADMIN 配置 MAC 配置  
CAP_SYSLOG 修改内核 printk 行为  
CAP_NET_ADMIN 配置网络  
CAP_SYS_ADMIN 捕获所有  
使用 /proc、/sys -&gt; 重新挂载 ro、删除 cap_sys_admin； 安全模块，如 selinux 或 apparmor； 该文件系统的某些部分是“命名空间感知的”  
Docker 将这些文件系统作为“只读”挂载点挂载到容器中.  
 .  /系统  
 .  /进程/系统  
 .  /proc/sysrq-触发器  
 .  /进程/中断  
 .  /进程/总线  
写时复制文件系统  
 Docker 使用写时复制文件系统. 这意味着容器可以使用相同的文件系统映像作为容器的基础. 当容器将内容写入映像时，它会被写入容器特定的文件系统. 这可以防止一个容器看到另一个容器的更改，即使它们写入同一文件系统映像也是如此. 同样重要的是，一个容器不能更改图像内容来影响另一个容器中的进程.
* uid 0 -&gt; 用户命名空间，uid 0 映射到外部的随机 uid

3）系统服务，如设备、网络、文件系统

 * root -&gt; 更多的服务应该在主机外部运行； 隔离敏感函数，作为非特权上下文运行
* 完全权限 -&gt; 在内核级别隔离

4）内核驱动、网络堆栈、安全策略

* 绝对权限 -&gt; 在单独的虚拟机中运行

5）一般的不可变基础设施

* 集装箱是滚装
* 写入小的单独的 rw nosuid 部分

[src](http://www.slideshare.net/jpetazzo/docker-linux-containers-lxc-and-security)  
[src](https://opensource.com/business/14/9/security-for-docker)

### Technologies for security

事情好多了. 例如，大多数现代容器技术可以利用 Linux 的内置安全工具，例如：  
[AppArmor](http://wiki.apparmor.net/index.php/Main_Page), [SELinux](http://selinuxproject.org/page/Main_Page) 和 [Seccomp](http://man7.org/linux/man-pages/man2/seccomp.2.html) 政策；  
[Grsecurity](https://grsecurity.net/);  
[Control groups (cgroups)](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Resource_Management_Guide/ch01.html);  
[Kernel namespaces](http://man7.org/linux/man-pages/man7/namespaces.7.html)  
[src](http://www.itworld.com/article/2920349/security/for-containers-security-is-problem-1.html)

当然，您正在部署 seccomp，但您不能在容器内使用 selinux，因为该策略不是针对每个命名空间的（?? lxc 对每个容器使用 apparmore...）  
[sVirt](http://selinuxproject.org/page/SVirt) - kvm 的 selinux  
[src](https://mjg59.dreamwidth.org/33170.html)

主要内核子系统没有命名空间，如下所示：  
-SELinux  
- C组  
- /sys下的文件系统  
- /proc/sys、/proc/sysrq-trigger、/proc/irq、/proc/bus

设备没有命名空间：  
- /dev/mem  
- /dev/sd* 文件系统设备  
- 内核模块

如果您可以将其中一个作为特权进程进行通信或攻击，您就可以拥有该系统.  
[src](https://opensource.com/business/14/7/docker-security-selinux)

## Another Information Sources

* [sysdig-container-ecosystem](https://github.com/draios/sysdig-container-ecosystem)  
至少可以说，围绕容器和微服务涌现的令人惊叹的新技术生态系统可能有点让人不知所措. 我们认为我们可以提供帮助：欢迎来到容器生态系统项目.
* [doger.io](http://doger.io/)  
本页试图记录 Linux 上容器的细节. 这不仅限于希望在自己的代码中实现容器或使用类似容器的功能的程序员，还包括希望更多地了解容器如何“在幕后”工作的系统管理员和用户. 
