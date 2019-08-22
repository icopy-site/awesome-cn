<div class="github-widget" data-repo="veggiemonk/awesome-docker"></div>
## Awesome Docker [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Join the chat at https://gitter.im/veggiemonk/awesome-docker](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/veggiemonk/awesome-docker) [![Say Thanks](https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg)](https://saythanks.io/to/veggiemonk)

&gt; Docker资源和项目的精选列表
&gt;灵感来自 [@sindresorhus](https://github.com/sindresorhus)&#39;[awesome] [sindresorhus]并通过这些改进**[amazing contributors](https://github.com/veggiemonk/awesome-docker/graphs/contributors)**.

如果您想贡献，请先阅读[CONTRIBUTING.md] [贡献].
它包含许多提示和指导，以帮助保持组织有序.
只需单击[README.md] [editreadme]即可提交[pull request] [editreadme].
 如果此列表未完成，您可以[贡献] [editreadme]来完成此操作.  这是一个很棒的视频教程，可以学习如何操作 [contribute on Github](https://egghead.io/lessons/javascript-identifying-how-to-contribute-to-an-open-source-project-on-github)

** _您可以看到更新 [TWITTER](https://twitter.com/awesome_docker)_**

 &gt; **请**，帮助组织这些资源，以便他们能够轻易地找到并理解新来者.  了解如何** [贡献] [贡献] **提示！

 ** _如果您看到此处的链接不再（不再），那么您可以通过提交[pull request] [editreadme]来改进此文件来修复它.  谢谢！_**

 此列表的创建者和维护者不接受任何形式的付款以接受任何贡献者所做的更改.  此页面不是任何方式的官方Docker产品.  它是项目链接的列表，由志愿者维护.  欢迎大家贡献.  这个回购的目标是索引开源项目，而不是为了获利.

所有链接都经过监控和测试 [awesome_bot](https://github.com/dkhamsing/awesome_bot) made by [@dkhamsing](https://github.com/dkhamsing)


<!-- TOC -->


<!-- /TOC -->

## Legend

- 被遗弃：头骨：
-  Beta：建设：
- 货币化：heavy_dollar_sign：

## What is Docker

 &gt; Docker是开发人员和系统管理员构建，发布和运行分布式应用程序的开放平台.  Docker Engine是一种便携式轻量级运行时和打包工具，Docker Hub是一种用于共享应用程序和自动化工作流程的云服务，它可以通过组件快速组装应用程序，消除开发，QA和生产环境之间的摩擦.  因此，IT可以更快地发货并在笔记本电脑，数据中心虚拟机和任何云上运行相同的应用程序，不变.

_Source:_ [What is Docker](https://www.docker.com/why-docker)

## Where to start

- [Benefits of using Docker](https://semaphoreci.com/blog/docker-benefits) 用于开发和交付，具有实用的采用路线图.
- [Docker Curriculum](https://github.com/prakhar1989/docker-curriculum) ：入门Docker的综合教程.  通过Elastic Beanstalk和Elastic Container Service教授如何在AWS上使用Docker和部署dockerized应用程序.
- [Docker Documentation](https://docs.docker.com/)：官方文件
- [Docker Training](https://success.docker.com/training) ：heavy_dollar_sign：
- [Docker Tutorial for Beginners (Updated 2019 version)](https://hashnode.com/post/docker-tutorial-for-beginners-cjrj2hg5001s2ufs1nker9he2)   - 在这个Docker教程中，您将学习所有基础知识，并了解如何将Node.js和Go应用程序容纳在一起.  即使您不熟悉这些语言，也应该很容易遵循本教程并使用任何其他语言.
- [Katacoda](https://www.katacoda.com/courses/docker)：使用基于交互式浏览器的实验室学习Docker
- [Learn Docker](https://github.com/dwyl/learn-docker)：逐步教程和更多资源（视频，文章，备忘单） [@dwyl](https://github.com/dwyl)
- [Play With Docker](https://training.play-with-docker.com/) ：PWD是从初学者到高级用户开始使用Docker的好方法.  Docker直接在您的浏览器中运行.
- [Play With Moby](http://play-with-moby.com/) ：PWM是一个基于Web的Moby游乐场，可让您在几秒钟内尝试不同的平台组件.  它为您提供了在云中拥有免费的Alpine Linux虚拟机的体验，您可以在其中构建和运行Moby项目，甚至可以创建集群进行实验.
- [Practical Introduction to Container Terminology](https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction/)  容器技术的前景不仅仅是docker.  如果没有很好地掌握术语，就很难掌握docker和（选择你喜欢的，CRI-O，rkt，lxc / lxd）之间的关键差异，或者了解Open Container Initiative正在做些什么来标准化容器技术.

** Cheatsheets ** by

- [@eon01](https://github.com/eon01/DockerCheatSheet)
- [@dimonomid](https://github.com/dimonomid/docker-quick-ref) （PDF）
- [@JensPiegsa](https://github.com/JensPiegsa/docker-cheat-sheet)
- [@wsargent](https://github.com/wsargent/docker-cheat-sheet) （最受欢迎）

## Where to start (Windows)

- [A Comparative Study of Docker Engine on Windows Server vs Linux Platform](https://collabnix.com/a-comparative-study-of-docker-engine-on-windows-server-vs-linux-platform/) 比较Windows和Linux上Docker的功能集和实现
- [Build And Run Your First Docker Windows Server Container](https://blog.docker.com/2016/09/build-your-first-docker-windows-server-container/) 演练在Windows 10上安装Docker，构建Docker镜像并运行Windows容器
- [Docker on Windows behind a firewall](https://toedter.com/2015/05/11/docker-on-windows-behind-a-firewall/) 通过 [@kaitoedter](https://twitter.com/kaitoedter)
- [Docker Reference Architecture: Modernizing Traditional .NET Framework Applications](https://success.docker.com/article/modernizing-traditional-dot-net-applications) - 您将学习如何识别适合集装箱化的.NET Framework应用程序类型，即容器化的“提升 - 移位”方法.
- [Docker with Microsoft SQL 2016 + ASP.NET](https://blog.alexellis.io/docker-does-sql2016-aspnet/) 演示在Docker中运行ASP.NET和SQL Server工作负载
- [Exploring ASP.NET Core with Docker in both Linux and Windows Containers](https://www.hanselman.com/blog/ExploringASPNETCoreWithDockerInBothLinuxAndWindowsContainers.aspx) 使用[Docker for Windows] [docker-for-windows]在Linux和Windows容器中运行ASP.NET Core应用程序
- [Running a Legacy ASP.NET App in a Windows Container](https://blog.sixeyed.com/dockerizing-nerd-dinner-part-1-running-a-legacy-asp-net-app-in-a-windows-container/) Docker化旧版ASP.NET应用程序并作为Windows容器运行的步骤
- [Windows Containers and Docker: The 101](https://www.youtube.com/watch?v=N7SG2wEyQtM) ：movie_camera： - 使用Docker运行PowerShell，ASP.NET Core和ASP.NET应用程序的20分钟概述
- [Windows Containers Quick Start](https://docs.microsoft.com/en-us/virtualization/windowscontainers/about/index) Windows容器概述，深入研究Windows 10和Windows Server 2016的快速入门

---

## Projects

-  Moby =开源开发
-  Docker CE =基于Moby的免费产品发布
-  Docker EE =基于Docker CE的商业产品发布.

&gt; Docker EE与Docker CE位于相同的代码库中，因此也是从Moby构建的，添加了商业组件，例如“docker data center / universal control plane”

- [Moby](https://github.com/moby/moby)
- [Docker Images](https://hub.docker.com)
- [Docker Compose](https://github.com/docker/compose/) (Define and run multi-container applications with Docker)
- [Docker Machine](https://github.com/docker/machine) （以集装箱为中心的世界的机器管理）
-  [Docker Registry] [发布]（用于打包，发送，存储和传送内容的Docker工具集）
- [Docker Swarm](https://github.com/docker/swarm) （Swarm：一个Docker原生的集群系统）

## Container Operations

### Container Composition

- [bocker](https://github.com/icy/bocker)  （2） - 在Bash中完全写入Dockerfile.  可扩展且简单.   - &gt;可重复使用 [@icy](https://github.com/icy)
- [bocker](https://github.com/p8952/bocker) （1）：头骨： -  Docker在100行bash中实现 [p8952](https://github.com/p8952)
- [box](https://github.com/box-builder/box) - 使用mruby DSL构建Dockerfile映像，包括展平和图层处理
- [Capitan](https://github.com/byrnedo/capitan) - 可组合的docker业务流程，增加了脚本支持 [@byrnedo](https://github.com/byrnedo).
- [compose_plantuml](https://github.com/funkwerk/compose_plantuml) - 通过以下方式从docker-compose文件生成Plantuml图 [@funkwerk](https://github.com/funkwerk)
- [Composerize](https://github.com/magicmark/composerize) - 将docker run命令转换为docker-compose文件
- [crowdr](https://github.com/polonskiy/crowdr) - 用于管理多个Docker容器的工具（`docker-compose`替代） [@polonskiy](https://github.com/polonskiy/)
- [docker-compose-graphviz](https://github.com/abesto/docker-compose-graphviz) - 将docker-compose.yml文件转换为Graphviz .dot文件 [@abesto](https://github.com/abesto)
- [docker-config-update](https://github.com/sudo-bmitch/docker-config-update) - 更新docker配置和秘密的实用程序，用于在compose文件中部署 [@sudo-bmitch](https://github.com/sudo-bmitch)
- [draw-compose](https://github.com/Alexis-benoist/draw-compose) - 用于绘制docker的模式的实用程序 [@Alexis-benoist](https://github.com/Alexis-benoist)
- [elsy](https://github.com/cisco/elsy) - 基于Docker和Docker Compose的自以为是的多语言构建工具
- [habitus](https://github.com/cloud66-oss/habitus) -  Docker的构建流程工具 [@cloud66](https://github.com/cloud66)
- [Maestro](https://github.com/toscanini/maestro) ：头骨： -  Maestro提供了轻松启动，协调和管理多个Docker容器的能力 [@tascanini](https://github.com/toscanini)
- [percheron](https://github.com/ashmckenzie/percheron) ：头骨： - 用肌肉和智力组织你的Docker容器 [@ashmckenzie](https://github.com/ashmckenzie)
- [plash](https://github.com/ihucos/plash) - 容器运行和构建引擎 - 在docker中运行.
- [rocker-compose](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/grammarly/rocker-compose)  ：skull： - 具有idempotency功能的Docker组合工具，用于部署由多个容器组成的应用程序.  通过 [@https://github.com/veggiemonk/awesome-docker/blob/master/grammarly](https://github.com/veggiemonk/awesome-docker/blob/master/grammarly)
- [rocker](https://github.com/grammarly/rocker)  ：skull： - 扩展的Dockerfile构建器.  支持多个FROM，MOUNTS，模板等 [grammarly](https://github.com/grammarly).
- [Stacker](https://github.com/stacker/stacker-cli)   -  Docker撰写模板.  Stacker提供了一个基于Docker Compose的抽象层和一个更好的DX（开发人员体验）.
- [Smalte](https://github.com/roquie/smalte)   - 动态配置需要在docker容器中进行静态配置的应用程序.  通过 [@roquie](https://github.com/roquie)
- [Zodiac](https://github.com/CenturyLinkLabs/zodiac)  ：skull： - 一个轻量级工具，可轻松部署和回退dockerized应用程序.  由[@CenturyLinkLabs] [centurylinklabs]

### Deployment and Infrastructure

- [blackfish](https://gitlab.com/blackfish/blackfish) - 用于为Dev和Production构建群集集群的CoreOS VM [@blackfish](https://gitlab.com/blackfish/)
- [BosnD](https://gitlab.com/n0r1sk/bosnd) - 船长守护者BosnD  - 动态配置文件编写器和服务重新加载器，用于动态更改容器环境.
- [Centurion](https://github.com/newrelic/centurion)   -  Centurion是Docker车队的大规模部署工具.  它从Docker注册表中获取容器，并在具有正确环境变量，主机卷映射和端口映射的一组主机上运行它们.  通过 [@newrelic](https://github.com/newrelic)
- [Clocker](https://github.com/brooklyncentral/clocker)   -  Clocker创建和管理Docker云基础架构.  Clocker支持在Docker和Marathon上作为分布在多个主机上的容器运行的多节点应用程序的单击部署和运行时管理.  它利用[Calico] [calico]和[Weave] [weave]进行网络连接 [Brooklyn](https://brooklyn.apache.org/)  用于应用程序蓝图.  通过 [@brooklyncentral](https://github.com/brooklyncentral)
- [Conduit](https://github.com/ehazlett/conduit) -  Docker的实验部署系统 [@ehazlett](https://github.com/ehazlett)
- [depcon](https://github.com/ContainX/depcon)   -  Depcon是用Go编写的，允许您轻松地将Docker容器部署到Apache Mesos / Marathon，Amazon ECS和Kubernetes.  通过[@ContainX] [containsx]
- [deploy](https://github.com/ttiny/deploy)  ：skull： -  Git和Docker部署工具.  简单的Docker组合工具和完整的集群编排之间的中间地带 [@ttiny](https://github.com/ttiny)
- [dockit](https://github.com/humblec/dockit)  ：头骨： - 做泊坞行动和部署gluster容器！  通过 [@humblec](https://github.com/humblec)
- [gitkube](https://github.com/hasura/gitkube)   -  Gitkube是一个使用`git push`在Kubernetes上构建和部署docker镜像的工具.  通过 [@Hasura](https://github.com/hasura/).
- [Grafeas](https://github.com/grafeas/grafeas)   - 有关容器的元数据的通用API，从映像和构建详细信息到安全漏洞.  通过 [grafeas](https://github.com/grafeas)
- [Longshoreman](https://github.com/longshoreman/longshoreman)  ：skull： -  Longshoreman使用Docker自动化应用程序部署.  只需创建一个Docker存储库（或使用服务），使用AWS或Digital Ocean（或任何您喜欢的任何东西）配置集群，并使用类似Heroku的CLI工具部署应用程序.  通过 [longshoreman](https://github.com/longshoreman)
- [SwarmManagement](https://github.com/DIPSAS/SwarmManagement)   -  Swarm Management是一个python应用程序，随pip一起安装.  该应用程序通过配置单个yaml文件来描述要部署的堆栈以及要创建的网络，配置或机密，从而轻松管理Docker Swarm.

### Monitoring

- [Axibase Collector](https://github.com/axibase/atsd-use-cases/tree/master/integrations/docker) -  Axibase Collector将性能计数器，配置更改和生命周期事件从Docker引擎流入Axibase时间序列数据库，用于汇总仪表板和与上游监控系统的集成.
- [cAdvisor](https://github.com/google/cadvisor)   - 分析正在运行的容器的资源使用情况和性能特征.  由[@Google]创建[google]
- [dockprom](https://github.com/stefanprodan/dockprom) - 使用Prometheus，Grafana，cAdvisor，NodeExporter和AlertManager的Docker主机和容器监控 [@stefanprodan](https://github.com/stefanprodan)
- [Docker-Alertd](https://github.com/deltaskelta/docker-alertd) - 根据docker容器资源使用情况/统计信息监控和发送警报
- [Docker-Flow-Monitor](https://github.com/docker-flow/docker-flow-monitor) -  [@vfarcic] [vfarcic]自动更新或部署新服务时重新配置Prometheus
- [Dockerana](https://github.com/dockerana/dockerana) ：skull： -  Graphite和Grafana的打包版本，专门针对Docker的指标.
- [DockProc](https://gitlab.com/n0r1sk/dockproc) - 对processlevel上的容器进行I / O监控.
- [Dozzle](https://github.com/amir20/dozzle) - 使用浏览器或移动设备实时监控容器日志. [@amir20](https://github.com/amir20)
- [Dynatrace](https://www.dynatrace.com/technologies/docker-monitoring/) ：heavy_dollar_sign： - 在不安装代理或修改Run命令的情况下监视容器化应用程序
- [Glances](https://github.com/nicolargo/glances) - 一个用Python编写的跨平台基于curses的系统监视工具 [@nicolargo](https://github.com/nicolargo)
- [Grafana Docker Dashboard Template](https://grafana.com/grafana/dashboards/179) -  Docker，Grafana和Prometheus堆栈的模板[@vegasbrianc] [vegasbrianc]
- [InfluxDB, cAdvisor, Grafana](https://github.com/vegasbrianc/docker-monitoring) -  [@vegasbrianc] [vegasbrianc]将InfluxDB时间序列数据库与Grafana和cAdvisor结合使用
- [LogJam](https://github.com/gocardless/logjam) -  Logjam是一个日志转发器，用于侦听本地端口，通过UDP接收日志条目，并将这些消息转发到日志收集服务器（例如logstash）上 [@gocardless](https://github.com/gocardless)
- [Logspout](https://github.com/gliderlabs/logspout) -  [@gliderlabs] [gliderlabs]记录Docker容器日志的路由
- [monit-docker](https://github.com/decryptus/monit-docker)   - 监视docker容器资源使用情况或状态，并执行docker命令或容器内部.  [@decryptus] [decryptus]
- [NexClipper](https://github.com/NexClipper/NexClipper) -  NexClipper是专门用于Docker，Apache Mesos，Marathon，DC / OS，Mesosphere，Kubernetes的容器监控和性能管理解决方案 [@Nexclipper](https://github.com/NexClipper)
- [Out-of-the-box Host/Container Monitoring/Logging/Alerting Stack](https://github.com/uschtwill/docker_monitoring_logging_alerting)   -  Docker主机和容器监控，日志记录和开箱即用的警报，使用cAdvisor，Prometheus，Grafana进行监控，Elasticsearch，Kibana和Logstash进行日志记录，使用elastalert和Alertmanager进行警报.  设置在5分钟.  生产使用的安全模式，内置[自动Nginx反向代理（jwilder）] [nginxproxy].
- [SwarmAlert](https://github.com/gpulido/SwarmAlert) - 监视Docker Swarm并在发现没有运行正常服务任务的容器时发送Pushover警报.
- [Zabbix Docker module](https://github.com/monitoringartist/Zabbix-Docker-Monitoring)   -  Zabbix模块，提供运行容器，CPU /内存/ blk IO / net容器指标的发现.  还支持Systemd Docker和LXC执行驱动程序.  它是一个动态链接的共享对象库，因此它的性能比任何脚本解决方案都要好（~10x）.
- [Zabbix Docker](https://github.com/gomex/docker-zabbix) - 使用zabbix LLD功能自动监控容器.

### Networking

-  [Calico-Docker] [calico]  -  Calico是一个纯粹的第3层虚拟网络，允许多个泊坞主机上的容器相互通信.
- [Flannel](https://github.com/coreos/flannel/)   -  Flannel是一个虚拟网络，为每个主机提供一个子网，用于容器运行时.  由[@coreos] [coreos]
- [Freeflow](https://github.com/Microsoft/Freeflow)   -  Linux上的高性能容器覆盖网络.  启用RDMA（在InfiniBand和RoCE上）并加速TCP到裸机性能.  通过 [@Microsoft](https://github.com/Microsoft)
- [netshoot](https://github.com/nicolaka/netshoot) -  netshoot容器具有一组强大的网络工具，可帮助解决Docker网络问题 [@nicolaka](https://github.com/nicolaka)
- [Pipework](https://github.com/jpetazzo/pipework)   -  Linux容器的软件定义网络，Pipework使用“普通”LXC容器，以及令人敬畏的Docker.  由[@jpetazzo] [jpetazzo]
-  [Weave] [weave]（Docker网络） -  Weave创建一个虚拟网络，连接跨多个主机部署的Docker容器.

### Orchestration

- [athena](https://github.com/athena-oss/athena) - 具有插件架构的自动化平台，可让您轻松创建和共享服务.
- [blimp](https://github.com/tubes和lube/blimp) ：skull： - 使用Docker Machine轻松地将容器从一个Docker主机移动到另一个Docker主机，显示针对所有主机运行的容器，跨多个主机复制容器等等 [@defermat](https://github.com/defermat) 和 [@schvin](https://github.com/schvin)
- [CloudSlang](https://github.com/CloudSlang/cloud-slang) -  CloudSlang是一个用于创建Docker流程自动化的工作流引擎
- [clusterdock](https://github.com/clusterdock/clusterdock) -  Docker容器编排，用于测试长时间运行的集群部署
- [ContainerShip](https://github.com/containership/containership) 一个简单的容器管理平台
- [Crane](https://github.com/Dataman-Cloud/crane) - 基于docker内置群的控制平面 [@Dataman-Cloud](https://github.com/Dataman-Cloud)
- [Docker Flow Swarm Listener](https://github.com/vfarcic/docker-flow-swarm-listener)   -  Docker Flow Swarm Listener项目是监听Docker Swarm事件并在发生更改时发送请求.  由[@vfarcic] [vfarcic]
- [gantryd](https://github.com/DevTable/gantryd) ：skull： - 一个框架，用于轻松管理跨机器的基于docker的组件 [@DevTable](https://github.com/DevTable)
- [Haven](https://github.com/codeabovelab/haven-platform)   -  Haven是一个简化的容器管理平台，集成了容器，应用程序，集群，映像和注册表管理.  通过 [@codeabovelab](https://github.com/codeabovelab)
- [Helios](https://github.com/spotify/helios) ：skull： - 通过[@spotify] [spotify]在整个服务器队列中部署和管理容器的简单平台
- [Kontena](https://github.com/kontena/kontena) - 面向群众的应用容器 [website](https://www.kontena.io/)
- [Kubernetes](https://github.com/kubernetes/kubernetes) - Open source orchestration system for Docker containers by Google
- [ManageIQ](https://github.com/ManageIQ/manageiq)   - 发现，优化和控制您的混合IT.  通过 [ManageIQ](https://github.com/ManageIQ)
- [Mantl](https://github.com/mantl/mantl) -  Mantl是一个快速部署全球分布式服务的现代平台
- [Marathon](https://github.com/mesosphere/marathon) - Marathon is a private PaaS built on Mesos. It automatically handles hardware or software failures and ensures that an app is "always on"
- [Mesos](https://github.com/apache/mesos) - 容器，VM和物理主机的资源/作业调度程序 [@apache](https://mesos.apache.org/)
- [Nebula](https://github.com/nebula-orchestrator) - 用于管理大规模分布式集群的Docker业务流程工具.
- [Nomad](https://github.com/hashicorp/nomad)   - 以任何规模轻松部署应用程序.  分布式，高可用性，数据中心感知调度程序 [@hashicorp](https://github.com/hashicorp)
- [Panamax](https://github.com/CenturyLinkLabs/panamax-ui) ：skull： - 一个开源项目，通过[@CenturyLinkLabs] [centurylinklabs]使复杂的容器化应用程序像拖放一样简单.
- [Rancher](https://github.com/rancher/rancher) - 一个开源项目，为[@rancher] [rancher]提供了生产Docker的完整平台.
- [Swarm-cronjob](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max/swarm-cronjob) - 在Swarm上基于时间的计划创建作业 [@https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max](https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max)

### PaaS

- [Atlantis](https://github.com/ooyala/atlantis) ：skull： -  Atlantis是一个基于Docker构建的HTTP应用程序的开源PaaS，用Go编写
- [caprover](https://github.com/caprover/caprover) -  [以前称为CaptainDuckDuck]自动可扩展Web服务器包（自动Docker + nginx） -  Heroku on Steroids
- [Convox Rack](https://github.com/convox/rack) -  Convox Rack是基于专家基础架构自动化和devops最佳实践构建的开源PaaS.
- [Dcw](https://github.com/pbertera/dcw) -  Docker-compose SSH包装器：一个非常差的人PaaS，暴露了容器标签中定义的docker-compose和custom-container命令.
- [Dokku](https://github.com/dokku/dokku) -  Docker驱动的mini-Heroku，可帮助您构建和管理应用程序的生命周期（最初由[@progrium] [progrium]）
- [Empire](https://github.com/remind101/empire) - 基于Amazon EC2容器服务（ECS）构建的PaaS
- [Exoframe](https://github.com/exoframejs/exoframe) - 一个自托管工具，允许使用Docker进行简单的单命令部署
- [Flynn](https://github.com/flynn/flynn) - 下一代开源平台即服务
- [Nanobox](https://github.com/nanobox-io/nanobox) ：heavy_dollar_sign： - 一个应用程序开发平台，可创建可在云中部署和扩展的本地环境.
- [OpenShift][openshift] - An open source PaaS built on [Kubernetes][kubernetes] and optimized for Dockerized app development and deployment by [Red Hat](https://www.redhat.com/en)
- [Tsuru](https://github.com/tsuru/tsuru) -  Tsuru是一个可扩展的开源平台即服务软件
- [Workflow](https://github.com/deis/workflow) -  Kubernetes的开源PaaS [Deis](https://github.com/deis) .  以前是Deis v1.
- [ZEIT Now](https://github.com/zeit/now-cli) ：heavy_dollar_sign： -  Node.js应用程序或具有Dockerfile的任何应用程序的通用无服务器单命令部署.

### Reverse Proxy

- [docker-flow-proxy](https://github.com/vfarcic/docker-flow-proxy)   - 每次部署新服务或缩放服务时重新配置代理.  由[@vfarcic] [vfarcic]
- [docker-proxy](https://github.com/silarsis/docker-proxy)  ：skull： -  docker容器的透明代理，在docker容器中运行.  通过 [@silarsis](https://github.com/silarsis)
- [fabio](https://github.com/fabiolb/fabio)   - 一种快速，现代，零配置的负载均衡HTTP（S）路由器，用于部署由领事管理的微服务.  通过 [@magiconair](https://github.com/magiconair) （弗兰克施罗德）
- [h2o-proxy](https://github.com/zchee/h2o-proxy)  ：skull： -  Docker容器的自动H2O反向代理.  [jwilder / nginx-proxy] [nginxproxy]的替代方案 [@zchee](https://github.com/zchee)
- [Let's Encrypt Nginx-proxy Companion](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion)   -  nginx-proxy的轻量级伴随容器.  它允许自动创建/续订Let的加密证书.  通过 [@JrCs](https://github.com/JrCs)
- [muguet](https://github.com/mattallty/muguet)   -  Docker环境的DNS服务器和反向代理.  通过 [@mattallty](https://github.com/mattallty)
-  [nginx-proxy] [nginxproxy]  -  [@jwilder] [jwilder]使用docker-gen为Docker容器自动化nginx代理
- [Nginx Proxy Manager](https://github.com/jc21/nginx-proxy-manager)   - 一个漂亮的Web界面，用于使用SSL代理基于Web的服务.  通过 [@jc21](https://github.com/jc21)
- [Swarm Ingress Router](https://github.com/tpbowden/swarm-ingress-router)   - 根据标签将DNS名称路由到Swarm服务.  通过 [@tpbowden](https://github.com/tpbowden/)
- [Swarm Router](https://github.com/flavioaiello/swarm-router)   - 基于“零配置”服务名称的路由器，用于码头群模式，具有全新且更安全的方法.  通过 [@flavioaiello](https://twitter.com/flavioaiello)
- [Træfɪk](https://github.com/containous/traefik) -  Docker，Mesos，Consul，Etcd等自动反向代理和负载均衡器 [@EmileVauge](https://github.com/emilevauge)

### Security

- [Anchor Engine](https://github.com/anchore/anchore) - 分析CVE漏洞和自定义安全策略的映像 [@Anchor](https://github.com/anchore)
- [Aqua Security](https://www.aquasec.com) ：heavy_dollar_sign： - 在任何平台上保护基于容器的应用程序从Dev到Production
- [bane](https://github.com/genuinetools/bane) -  [@genuinetools]的[适用于Docker容器的AppArmor配置文件生成器[genuinetools]
- [CIS Docker Benchmark](https://github.com/dev-sec/cis-docker-benchmark)   - 此[InSpec] [inspec]合规性配置文件以自动方式实施CIS Docker 1.12.0基准测试，以便在生产环境中围绕Docker守护程序和容器提供安全性最佳实践测试.  通过 [@dev-sec](https://github.com/dev-sec)
- [Clair](https://github.com/coreos/clair)   -  Clair是一个开源项目，用于静态分析appc和docker容器中的漏洞.  由[@coreos] [coreos]
- [Dagda](https://github.com/eliasgranderubio/dagda)   -  Dagda是一种工具，用于对docker镜像/容器中的已知漏洞，特洛伊木马，病毒，恶意软件和其他恶意威胁进行静态分析，并监视docker守护程序和运行docker容器以检测异常活动.  通过 [@eliasgranderubio](https://github.com/eliasgranderubio)
- [docker-bench-security](https://github.com/docker/docker-bench-security)   - 用于检查生产中部署Docker容器的数十种常见最佳实践的脚本.  通过[@docker] [docker]
- [docker-explorer](https://github.com/google/docker-explorer) - 通过[@Google] [google]帮助预防离线码头获取的工具
- [notary](https://github.com/theupdateframework/notary)   - 用于运行和与受信任集合交互的服务器和客户端.  通过 [@TUF](https://github.com/theupdateframework)
- [oscap-docker](https://github.com/OpenSCAP/openscap)   -  OpenSCAP提供了oscap-docker工具，用于扫描Docker容器和图像.  通过 [OpenSCAP](https://github.com/OpenSCAP)
- [Sysdig Falco](https://github.com/falcosecurity/falco)   -  Sysdig Falco是一个开源容器安全监视器.  它可以监控应用程序，容器，主机和网络活动，并对未经授权的活动发出警报.
- [Sysdig Secure](https://sysdig.com/products/secure/) ：heavy_dollar_sign： -  Sysdig Secure通过行为监控和防御来解决运行时安全问题，并提供基于开源Sysdig的深度取证以进行事件响应.
- [Twistlock](https://www.twistlock.com/) ：heavy_dollar_sign： -  Twistlock Security Suite可检测漏洞，强化容器映像，并在应用程序的整个生命周期内实施安全策略.

### Service Discovery

- [docker-consul](https://github.com/gliderlabs/docker-consul) 通过[@progrium] [progrium]
- [etcd](https://github.com/etcd-io/etcd) - 分布式可靠键值存储，用于分布式系统的最关键数据 [@etcd-io](https://github.com/etcd-io) （CoreOS的前一部分）
- [https://github.com/veggiemonk/awesome-docker/blob/master/istio](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/istio/https://github.com/veggiemonk/awesome-docker/blob/master/istio) - 一个开放的平台，用于连接，管理和保护微服务 [@IstioMesh](https://github.com/veggiemonk/awesome-docker/blob/master/istio)
- [proxy](https://github.com/factorish/proxy)  ：skull： - 基于轻量级nginx的负载均衡器，使用registrator提供的服务发现.  通过 [@factorish](https://github.com/factorish)
- [registrator](https://github.com/gliderlabs/registrator) -  [@gliderlabs] [gliderlabs]和[@progrium] [progrium]的Docker服务注册表桥

### Volume Management / Data

- [Blockbridge](https://github.com/blockbridge/blockbridge-docker-volume)  ：heavy_dollar_sign： -  Blockbridge插件是一个卷插件，可以访问一组可扩展的基于容器的持久存储选项.  它支持单主机和多主机Docker环境，其功能包括租户隔离，自动配置，加密，安全删除，快照和QoS.  通过 [@blockbridge](https://github.com/blockbridge)
- [Convoy](https://github.com/rancher/convoy)   - 一个开源的Docker卷驱动程序，可以在任何地方快照，备份和恢复Docker卷.  由[@rancher] [牧场主]
- [Docker Machine NFS](https://github.com/adlogix/docker-machine-nfs) 为OS X上通过Docker Machine创建的现有boot2docker框激活NFS.
- [Docker Unison](https://github.com/leighmcculloch/docker-unison)  使用Unison进行快速双向文件夹同步的docker卷容器.  创建作为OS X上缓慢boot2docker卷的替代方法 [@leighmcculloch](https://github.com/leighmcculloch)
- [Local Persist](https://github.com/MatchbookLab/local-persist) 为本地卷指定一个挂载点（通过`docker volume create`创建），这样文件将始终保持不变，因此您可以挂载到不同容器中的不同目录.
- [Minio](https://github.com/minio/minio) -  Docker容器中的S3兼容对象存储服务器
- [Netshare](https://github.com/ContainX/docker-volume-netshare)  Docker NFS，AWS EFS，Ceph和Samba / CIFS卷插件.  通过[@ContainX] [containsx]
- [portworx](https://portworx.com) ：heavy_dollar_sign： - 用于持久，共享和复制卷的分散存储解决方案.
- [quobyte](https://www.quobyte.com/) ：heavy_dollar_sign： - 具有docker卷驱动程序的完全容错的分布式文件系统
- [REX-Ray](https://github.com/rexray/rexray)  提供与供应商无关的存储编排引擎.  主要设计目标是为Docker，Kubernetes和Mesos提供持久存储.  通过[@thecodeteam](https://github.com/thecodeteam) （戴尔科技）

### User Interface

#### Desktop

用于管理和监视docker主机和群集的本机桌面应用程序

- [Captain](https://getcaptain.co/) - 通过MacOSX菜单栏管理容器 [@RickWong](https://github.com/rickwong)
- [Dockeron](https://github.com/dockeron/dockeron) - 在桌面上为Docker构建的Electron + Vue.js项目. [@fluency03](https://github.com/fluency03)
- [DockStation](https://github.com/DockStation/dockstation) - 以开发人员为中心的UI，用于配置，监控和管理服务和容器 [@dock_station](https://twitter.com/dock_station)
- [Lifeboat](https://github.com/jplhomer/lifeboat) - 使用Mac上的图形界面启动Docker项目的简便方法. [@jplhomer](https://github.com/jplhomer)

#### Terminal

- [captain](https://github.com/jenssegers/captain)   - 轻松启动和停止任何目录中的docker compose项目.  通过 [@jenssegers](https://github.com/jenssegers)
- [ctop (1)](https://github.com/yadutaf/ctop) - 基于命令行/文本的Linux容器监视工具，可以像您期望的那样工作（Python） [@yadutaf](https://github.com/yadutaf)
- [ctop (2)](https://github.com/bcicen/ctop) - 容器指标（Golang）的类似于顶部的界面 [@bcicen](https://github.com/bcicen/)
- [dext-docker-registry-plugin](https://github.com/vutran/dext-docker-registry-plugin) - 使用Dext智能启动器搜索Docker Registry.
- [dive](https://github.com/wagoodman/dive)   - 用于探索泊坞窗图像中每个图层的工具.  通过 [wagoodman](https://github.com/wagoodman).
- [docker-ls](https://github.com/mayflower/docker-ls) - 用于浏览和操作docker注册表的CLI工具 [@mayflower](https://github.com/mayflower)
- [docker-ssh](https://github.com/jeroenpeeters/docker-ssh)   -  Docker容器的SSH服务器〜因为每个容器都应该是可访问的.  通过 [@jeroenpeeters](https://github.com/jeroenpeeters)
- [Docker-mon](https://github.com/icecrime/docker-mon) ：skull： - 基于控制台的Docker监控 [@icecrime](https://github.com/icecrime)
- [docker.el](https://github.com/Silex/docker.el) 从Emacs管理docker [Silex](https://github.com/Silex)
- [dockercraft](https://github.com/docker/dockercraft) -  Docker + Minecraft = [@docker] [docker]的Dockercraft
- [dockerfile-mode](https://github.com/spotify/dockerfile-mode) 用于处理Dockerfiles的emacs模式[@spotify] [spotify]
- [dockersql](https://github.com/crosbymichael/dockersql) - 使用SQL查询Docker的命令行界面 [@crosbymichael](https://github.com/crosbymichael)
- [DockSTARTer](https://github.com/GhostWriters/DockSTARTer) -  DockSTARTer帮助您开始使用Docker中运行的家庭服务器应用程序（[GhostWriters](https://github.com/GhostWriters))
- [dockly](https://github.com/lirantal/dockly) - 用于管理Docker容器的交互式shell UI [@lirantal](https://github.com/lirantal)
- [dry](https://github.com/moncho/dry) -  Docker容器的交互式CLI [@moncho](https://github.com/moncho)
- [DVM](https://github.com/howtowhale/dvm) -  Docker版本管理器 [@howtowhale](https://github.com/howtowhale)
- [goinside](https://github.com/iamsoorena/goinside)   - 轻松进入正在运行的docker容器.  通过 [@iamsoorena](https://github.com/iamsoorena)
- [lazydocker](https://github.com/jesseduffield/lazydocker)   - 管理所有码头工人的更懒惰的方式.  一个简单的终端UI，用于docker和docker-compose，用go写入gocui库.  通过 [@jesseduffield](https://github.com/jesseduffield)
- [MultiDocker](https://github.com/marty90/multidocker) - 创建一个安全的多用户Docker机器，将每个用户隔离到一个独立的容器中.
- [ns-enter](https://github.com/jpetazzo/nsenter) - 没有更多的ssh，通过[@jpetazzo] [jpetazzo]输入容器的名称空间
- [Powerline-Docker](https://github.com/adrianmo/powerline-docker) - 用于显示Docker容器状态的电力线段 [@adrianmo](https://github.com/adrianmo)
- [proco](https://github.com/shiwaforce/poco)   -  Proco将帮助您使用简单的YAML配置文件组织和管理任何复杂的Docker，Docker-Compose，Kubernetes项目，以缩短从查找项目到在本地环境中初始化项目的路线.  通过 [@shiwaforce](https://github.com/shiwaforce)
- [reg](https://github.com/genuinetools/reg) -  [@genuinetools] [原工具]的Docker注册表v2命令行客户端
- [scuba](https://github.com/JonathonReinhart/scuba) - 透明地使用Docker容器来封装软件构建环境 [@JonathonReinhart](https://github.com/JonathonReinhart)
- [sen](https://github.com/TomasTomecek/sen) -  docker引擎的终端用户界面，by [@TomasTomecek](https://github.com/TomasTomecek)
- [supdock](https://github.com/segersniels/supdock-ts)   - 通过交互式提示允许稍微更直观地使用Docker.  通过 [@segersniels](https://github.com/segersniels)
- [tsaotun](https://github.com/qazbnm456/tsaotun) - 基于Python的Docker帮助 [@qazbnm456](https://github.com/qazbnm456)
- [wharfee](https://github.com/j-bennet/wharfee)   -  Docker命令的自动完成和语法突出显示.  通过 [@j-bennet](https://github.com/j-bennet)

#### Web

- [Container Web TTY](https://github.com/wrfly/container-web-tty) - 通过网络连接您的容器 [@wrfly](https://github.com/wrfly)
- [Docker Compose UI](https://github.com/francescou/docker-compose-ui)   - 通过HTTP管理docker-compose.  docker-compose-ui在Docker容器中运行，安装主机docker socket并公开RESTful API和AngularJS GUI
- [Docker Registry Browser](https://github.com/klausmeyer/docker-registry-browser) -  Docker Registry HTTP API v2的Web界面 [@klausmeyer](https://github.com/klausmeyer)
- [Docker Registry UI](https://github.com/atcol/docker-registry-ui) - 用于轻松进行私有/本地Docker Registry集成的Web UI [@atcol](https://github.com/atcol)
- [Docker Registry UI (Joxit)](https://github.com/Joxit/docker-registry-ui) - 私有注册管理机构最简单，最干净的用户界面 [@Joxit](https://github.com/Joxit)
- [docker-registry-web](https://github.com/mkuchin/docker-registry-web) - 用于私有docker注册表v2的Web UI，身份验证服务和事件记录器 [@mkuchin](https://github.com/mkuchin)
- [docker-swarm-visualizer](https://github.com/dockersamples/docker-swarm-visualizer) - 在Docker Swarm上显示Docker服务（用于运行演示）.
- [dockering-on-rails](https://github.com/Electrofenster/dockerding-on-rails) ：skull： -  Docker的简单Web界面，具有很多功能 [@Electrofenster](https://github.com/Electrofenster/)
- [DockerSurfer](https://github.com/Simone-Erba/DockerSurfer) ：skull： - 用于分析和浏览Docker注册表中Docker镜像之间依赖关系的Web服务 [@Simone-Erba](https://github.com/Simone-Erba/)
- [OctoLinker](https://github.com/OctoLinker/OctoLinker) -  GitHub的浏览器扩展，使`Dockerfile`中的图像名称可单击，并将您重定向到相关的Docker Hub页面.
- [Portainer](https://github.com/portainer/portainer) - 用于管理Docker主机或Docker Swarm集群的轻量级管理UI [@portainer](https://github.com/portainer)
- [Portus](https://github.com/SUSE/Portus) -  Docker注册表（v2）的授权服务和前端 [@SUSE](https://github.com/SUSE)
- [Rapid Dashboard](https://github.com/ozlerhakan/rapid) - 一个简单的查询仪表板，用于使用Docker Remote API [@ozlerhakan](https://github.com/ozlerhakan/)
- [Seagull](https://github.com/tobegit3hub/seagull)   - 用于监控docker守护程序的友好Web UI.  通过 [@tobegit3hub](https://github.com/tobegit3hub)
- [Swarmpit](https://github.com/swarmpit/swarmpit)   -  Swarmpit为Docker Swarm集群提供简单易用的界面.  您可以管理堆栈，服务，机密，卷，网络等.
- [Swirl](https://github.com/cuigh/swirl) -  Swirl是Docker的一个Web管理工具，专注于swarm集群 [@cuigh](https://github.com/cuigh/)
- [Theia](https://github.com/theia-ide/theia) - 可扩展平台，利用最先进的Web技术开发成熟的多语言云和桌面IDE类产品.

## Docker Images

### Base Tools

安装在容器内或设计为作为容器运行的工具和应用程序 [sidecar](https://docs.microsoft.com/en-us/azure/architecture/patterns/sidecar)

- [amicontained](https://github.com/genuinetools/amicontained)   - 容器内省工具.  找出正在使用的容器运行时以及[@genuinetools] [genuinetools]提供的功能
- [autodock](https://github.com/prologic/autodock) -  Docker Automation的守护进程 [@prologic](https://github.com/prologic)
- [Chaperone](https://github.com/garywiz/chaperone)   - 为docker容器设计的单个PID1进程.  用户管理，日志管理，启动，僵尸收获，都在一个小包装中.  通过 [@garywiz](https://github.com/garywiz)
-  [CoreOS] [coreos]  - 用于大规模服务器部署的Linux
- [distroless](https://github.com/GoogleContainerTools/distroless) - 通过[@GoogleContainerTools] [googlecontainertools]减去语言的码头图像，减去操作系统
- [docker-alpine](https://github.com/gliderlabs/docker-alpine) - 一个超级小型Docker基础图像_（5MB）_使用Alpine Linux [@gliderlabs] [gliderlabs]
- [docker-gen](https://github.com/jwilder/docker-gen) -  [@jwilder] [jwilder]从docker容器元数据生成文件
- [dockerize](https://github.com/jwilder/dockerize) -  [@jwilder] [jwilder]简化在docker容器中运行应用程序的实用程序
- [GoSu](https://github.com/tianon/gosu) - 以此特定用户身份运行此特定应用程序，然后退出管道（入口点脚本工具） [@tianon](https://github.com/tianon)
- [is-docker](https://github.com/sindresorhus/is-docker) -  [@sindresorhus] [sindresorhus]检查进程是否在Docker容器内运行
- [lstags](https://github.com/ivanilves/lstags) - 通过注册表同步Docker镜像 [@ivanilves](https://github.com/ivanilves)
- [NVIDIA-Docker](https://github.com/NVIDIA/nvidia-docker) -  [@NVIDIA] [nvidia]的Docker NVIDIA Container Runtime
- [su-exec](https://github.com/ncopa/su-exec)   - 这是一个简单的工具，只需执行具有不同权限的程序.  该程序将直接执行，而不是像小孩一样运行，如su和sudo，这可以避免TTY和信号问题.  为什么重塑gosu？  这与gosu或多或少完全相同，但它只有10kb而不是1.8MB.  通过 [ncopa](https://github.com/ncopa)
- [supercronic](https://github.com/aptible/supercronic) -  crontab兼容的作业运行器，专门设计用于在容器中运行 [@aptible](https://github.com/aptible/)
- [TrivialRC](https://github.com/vorakl/TrivialRC) - 容器的简约运行时配置系统和进程管理器 [@vorakl](https://github.com/vorakl)

### Builder

旨在帮助或简化构建**新**图像的应用程序

- [buildah](https://github.com/containers/buildah) - 一种便于构建OCI图像的工具 [@containers](https://github.com/containers)
- [BuildKit](https://github.com/moby/buildkit) - 并发，缓存高效和与Dockerfile无关的构建器工具包 [@moby project](https://github.com/moby)
- [container-diff](https://github.com/GoogleContainerTools/container-diff) - 通过[@GoogleContainerTools] [googlecontainertools]比较和分析容器图像的图像工具
- [container-factory](https://github.com/mutable/container-factory) - 通过应用程序源代码的tarball生成Docker镜像 [@mutable](https://github.com/mutable)
- [copy-docker-image](https://github.com/mdlavin/copy-docker-image) - 在没有完整Docker安装的情况下，在注册表之间复制Docker镜像 [@mdlavin](https://github.com/mdlavin)
- [Derrick](https://github.com/alibaba/derrick)   - 工具可帮助您通过扫描代码自动生成Dockerfile和dockerize应用程序.  通过 [@alibaba](https://github.com/alibaba).
- [dlayer](https://github.com/wercker/dlayer) -  Docker图层的统计信息收集器 [@wercker](https://github.com/wercker)
- [docker-companion](https://github.com/mudler/docker-companion) - 用Golang编写的命令行工具，用于挤压和解包Docker镜像 [@mudler](https://github.com/mudler/)
- [docker-make](https://github.com/CtripCloud/docker-make) - 通过单个命令构建，标记和推送一堆相关的docker镜像.
- [docker-replay](https://github.com/bcicen/docker-replay) - Generate `docker run`command and options from running containers. By [bcicen](https://github.com/bcicen)
- [DockerMake](https://github.com/avirshup/DockerMake)   - 适用于复杂软件堆栈的可重现的Docker镜像构建系统.  通过 [@avirshup](https://github.com/avirshup)
- [DockerSlim](https://github.com/docker-slim/docker-slim) 缩小胖Docker图像，创建尽可能小的图像.
- [Dockly](https://github.com/swipely/dockly) -  Dockly是一个宝石，用于减轻在Docker中打包应用程序的痛苦 [@swipely](https://github.com/swipely/)
- [dockramp](https://github.com/jlhawn/dockramp) ：头骨： - 概念证明：客户端驱动的Docker Image Builder [@jlhawn](https://github.com/jlhawn)
- [essex](https://github.com/utensils/essex) - 基于Docker的项目的Boilerplate：Essex是一个用bash编写的CLI实用程序，可以使用Makefile驱动的工作流快速设置干净且一致的Docker项目. [@jamesbrink](https://github.com/jamesbrink)
- [HPC Container Maker](https://github.com/NVIDIA/hpc-container-maker) - 从高级Python配方生成Dockerfiles，包括[@NVIDIA] [nvidia]的高性能计算组件构建块
- [img](https://github.com/genuinetools/img) -  [@genuinetools] [genuinetools]的独立，无守护进程，无特权的Dockerfile和OCI兼容的容器映像构建器
- [kaniko](https://github.com/GoogleContainerTools/kaniko)   - 在Kubernetes建立容器图像.  通过[@GoogleContainerTools] [googlecontainertools]
- [makisu](https://github.com/uber/makisu) - Uber's fast and flexible unprivileged image builder for Mesos and Kubernetes, with distributed cache support. By [@uber](https://github.com/uber)
- [MicroBadger](https://microbadger.com) - 分析图像的内容并添加元数据标签
- [packer](https://www.packer.io/docs/builders/docker.html) -  Hashicorp工具，用于构建机器映像，包括与配置管理工具（如chef，puppet，ansible）集成的docker映像
- [portainer](https://github.com/duedil-ltd/portainer) - 用于构建Docker镜像的Apache Mesos框架 [@duedil-ltd](https://github.com/duedil-ltd)
- [Production-Ready Python Containers :heavy_dollar_sign:](https://pythonspeed.com/products/pythoncontainer/) - 用于为Python应用程序创建生产就绪Docker镜像的模板.
- [runlike](https://github.com/lavie/runlike) - 通过运行容器生成`docker run`命令和选项 [@lavie](https://github.com/lavie)
- [SkinnyWhale](https://github.com/djosephsen/skinnywhale) ：头骨： -  Skinnywhale帮助你制作更小的（如兆字节）Docker容器.
- [Smith](https://github.com/oracle/smith) - 一个Micocontainer Builder，可以在构建映像后执行多阶段构建[Oracle] [oracle]
- [werf](https://github.com/flant/werf) -  Werf（以前称为dapp）有助于实现和支持持续集成和持续交付 [@flant](https://github.com/flant)
- [Whaler](https://github.com/P3GLEG/Whaler) - 将Docker镜像反转为Dockerfiles的程序 [@P3GLEG](https://github.com/P3GLEG/).
- [Whales](https://github.com/Gueils/whales) - 一种自动将应用程序停靠的工具 [@icalialabs](https://github.com/IcaliaLabs).

### Dockerfile

- [chaperone-docker](https://github.com/garywiz/chaperone-docker) - 使用Chaperone流程管理器的一组图像，包括精益阿尔卑斯山图像，LAMP，LEMP和裸骨基础套件.
- [Dockerfile Generator](https://github.com/ozankasikci/dockerfile-generator) `dfg`既是Go库，也是使用各种输入通道生成有效Dockerfiles的可执行文件.
- [Dockerfile Generator](https://jrruethe.github.io/blog/2015/09/20/dockerfile-generator/)
- [Dockerfile Project](https://dockerfile.github.io/)   - 值得信赖的自动Docker构建.  Dockerfile Project为Docker容器上可运行的各种流行的开源软件服务维护着Dockerfile的中央存储库.
- [dockmoor](https://github.com/MeneDev/dockmoor)  ：构造： - 管理docker镜像引用并帮助使用Docker创建可重现的构建.  通过 [@MeneDev](https://github.com/MeneDev)
- [Vektorcloud](https://github.com/vektorcloud) - 一系列基于Alpine的最小Docker镜像

例子：

- [@arun-gupta](https://github.com/arun-gupta/docker-images)
- [@awesome-startup](https://github.com/awesome-startup/docker-compose)
- [@crosbymichael](https://github.com/crosbymichael/Dockerfiles)
- [@jessfraz](https://github.com/jessfraz/dockerfiles)
- [@komljen](https://github.com/komljen/dockerfile-examples)
- [@kstaken](https://github.com/kstaken/dockerfile-examples)
- [@ondrejmo](https://github.com/ondrejmo/Dockerfiles)
- [@pandrew](https://gitlab.com/pandrew/dockerfiles)
- [@vimagick](https://github.com/vimagick/dockerfiles)

### Linter

- [docker-image-size-limit](https://github.com/wemake-services/docker-image-size-limit) - 一种监视码头图像大小的工具.
- [dockerfile_lint](https://github.com/projectatomic/dockerfile_lint) -  Dockerfiles的基于规则的&#39;linter&#39; [@projectatomic](https://github.com/projectatomic)
- [Dockerfilelint](https://github.com/replicatedhq/dockerfilelint) - 一个节点模块，用于分析Dockerfile并查找常见的陷阱，错误并帮助实施最佳实践 [@replicatedhq](https://github.com/replicatedhq)
- [dockfmt](https://github.com/jessfraz/dockfmt) ：构造： -  [@jessfraz] [jessfraz]的Dockerfile格式化程序和解析器
- [Hadolint](https://github.com/hadolint/hadolint)   - 一个Dockerfile linter，它检查最佳实践，常见错误，并且还能够lint用`RUN`指令写入任何bash;  通过 [@lukasmartinelli](https://github.com/lukasmartinelli)
- [Whale-linter](https://github.com/jeromepin/whale-linter) - 一个简单而小巧的Dockerfile linter，用Python3 +编写，没有依赖关系 [@jeromepin](https://github.com/jeromepin)

### Metadata

- [opencontainer](https://github.com/opencontainers/image-spec/blob/master/annotations.md) -  OCI Image Spec定义的Docker标签的约定和共享命名空间.

### Registry

安全存储Docker镜像的服务.

- [Amazon EC2 Container Registry :heavy_dollar_sign:](https://aws.amazon.com/ecr/) -  Amazon EC2 Container Registry（ECR）是一个完全托管的Docker容器注册表，使开发人员可以轻松存储，管理和部署Docker容器映像.
- [Azure Container Registry :heavy_dollar_sign:](https://azure.microsoft.com/de-de/services/container-registry/) - 将Docker私有注册表作为一流的Azure资源进行管理
- [CargoOS](https://github.com/RedCoolBeans/cargos-buildroot)   - 在裸机或云上运行Docker Engine的基本操作系统.  通过 [@RedCoolBeans](https://github.com/RedCoolBeans)
- [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.io/l/docker-registry/)   - 完全托管的包管理SaaS，为公共和私有Docker注册表（以及许多其他注册表，包括Kubernetes生态系统的Helm图表）提供一流支持.  有一个慷慨的免费等级，也是完全免费的开源.
- [Cycle.io :heavy_dollar_sign:](https://cycle.io/) - 裸金属容器托管.
- [cleanreg](https://github.com/hcguersoy/cleanreg) - 一个小工具，用于删除实现API v2的Docker Registry中的图像清单，并通过它取消引用它们 [@hcguersoy](https://github.com/hcguersoy)
- [Docker Hub](https://hub.docker.com/) 由Docker Inc.提供
-  [Docker Registry v2] [distribution]  - 用于打包，发送，存储和传送内容的Docker工具集
- [Docket](https://github.com/netvarun/docket) - 自定义docker注册表，允许通过bittorrent快速部署 [@netvarun](https://github.com/netvarun/)
- [Europa :heavy_dollar_sign:](https://github.com/puppetlabs/europa)   - 支持图像管道和webhook的私有docker注册表.  通过 [@puppetlabs](https://github.com/puppetlabs)
- [GCE Container Registry :heavy_dollar_sign:](https://cloud.google.com/container-registry/) Google Cloud Platform上快速，私密的Docker图像存储
- [GitLab Container Registry](https://docs.gitlab.com/ce/user/project/container_registry.html) - 存储库专注于在GitLab CI中使用它
- [Harbor](https://github.com/goharbor/harbor)  一种开源可信云本机注册表项目，用于存储，签名和扫描内容.  支持复制，用户管理，访问控制和活动审核.  通过 [CNCF](https://github.com/veggiemonk/awesome-docker/blob/master/Sandbox) 以前 [VMWare](https://github.com/vmware)
- [JFrog Artifactory :heavy_dollar_sign:](https://jfrog.com/artifactory/) -  Artifact Repository Manager，也可以用作私有Docker Registry
- [Kraken](https://github.com/uber/kraken) -  Uber的高度可扩展的P2P docker注册表，能够在几秒钟内分发TB数据.
- [Private Docker Registry :heavy_dollar_sign:](https://private-docker-registry.com) - 专用的Conainer注册服务，具有无限的私有存储库，用户，团队，命名空间以及企业级认证LDAP / AD / OAuth / SAML.
- [Quay.io :heavy_dollar_sign:](https://quay.io/) （CoreOS的一部分） - 为私有Docker存储库提供安全托管
- [Rescoyl](https://github.com/noteed/rescoyl) - 私人Docker注册表（免费和开源） [@noteed](https://github.com/noteed)
- [Sonatype Nexus](https://www.sonatype.com/nexus-repository-oss) - 具有通用支持的存储库，也适用于Docker镜像
- [TreeScale](https://github.com/treescale)   - 构建和分发基于容器的应用程序.  通过 [@tigranbs](https://github.com/tigranbs)

## Development with Docker

### API Client

- [ahab](https://github.com/instacart/ahab) - 使用Python的Docker事件处理 [@instacart](https://github.com/instacart)
- [clj-docker-client](https://github.com/lispyclouds/clj-docker-client)  ：构造： -  Docker远程API的惯用语Clojure客户端.  通过 [@lispyclouds](https://github.com/lispyclouds)
- [Docker Client for JVM](https://github.com/gesellix/docker-client) - 用于JVM的Docker远程api客户端库，由[@gesellix] [gesellix]用Groovy编写
- [Docker Client TypeScript](https://gitlab.com/masaeedu/docker-client)   - 用于JavaScript的Docker API客户端，从moby存储库中的Swagger API定义自动生成.  通过 [@masaeedu](https://github.com/masaeedu)
- [docker-client](https://github.com/spotify/docker-client)   -  Docker远程API的Java客户端.  通过[@spotify] [spotify]
- [docker-it-scala](https://github.com/whisklabs/docker-it-scala) - 与Scala by的Docker集成测试工具包 [@whisklabs](https://github.com/whisklabs)
- [docker-java-api](https://github.com/amihaiemil/docker-java-api)   - 用于Docker API的轻量级，真正面向对象的Java客户端.  通过 [@amihaiemil](https://github.com/amihaiemil)
- [docker-maven-plugin](https://github.com/fabric8io/docker-maven-plugin) - 用于运行和创建Docker镜像的Maven插件 [@fabric8io](https://github.com/fabric8io)
- [Docker-PowerShell](https://github.com/Microsoft/Docker-PowerShell) -  Docker的PowerShell模块
- [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - C#/.NET HTTP client for the Docker remote API by [@https://github.com/veggiemonk/awesome-docker/blob/master/ahmetalpbalkan](https://github.com/veggiemonk/awesome-docker/blob/master/ahmetalpbalkan)
- [dockerfile-maven](https://github.com/spotify/dockerfile-maven) - 用于构建和推送Docker镜像的Maven插件[@spotify] [spotify]
- [dockerode](https://github.com/apocas/dockerode) -  Docker Remote API node.js模块 [@apocas](https://github.com/apocas)
- [DoMonit](https://github.com/eon01/DoMonit) -  Docker API的简单Docker Monitoring包装器
- [go-dockerclient](https://github.com/fsouza/go-dockerclient/) - 转到Docker远程API的HTTP客户端 [@fsouza](https://github.com/fsouza/)
- [Gradle Docker plugin](https://github.com/gesellix/gradle-docker-plugin) -  [@gesellix] [gesellix]为Gradle设计的Docker远程api插件
- [libcompose](https://github.com/docker/libcompose) - 去Docker Compose库.
- [Portainer stack utils](https://github.com/greenled/portainer-stack-utils)  ：构造： -  Bash脚本从docker-compose yaml文件部署/更新/取消部署Portainer实例中的Docker堆栈.  通过 [@greenled](https://github.com/greenled).
- [sbt-docker-compose](https://github.com/Tapad/sbt-docker-compose) - 将Docker Compose功能集成到sbt中 [@kurtkopchik](https://github.com/kurtkopchik/)
- [sbt-docker](https://github.com/marcuslonnberg/sbt-docker) - 直接从sbt创建Docker镜像 [@marcuslonnberg](https://github.com/marcuslonnberg)

### CI/CD

- [Buddy :heavy_dollar_sign:](https://buddy.works) - 最好的Git，构建和部署工具结合成一个强大的工具，增强了我们的开发.
- [Captain](https://github.com/harbur/captain) - 将您的Git工作流转换为Docker容器，准备进行持续交付 [@harbur](https://github.com/harbur).
- [Cyclone](https://github.com/caicloud/cyclone) - 强大的工作流引擎和端到端管道解决方案，使用原生Kubernetes资源实现 [@caicloud](https://github.com/caicloud).
- [Diun](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max/diun) - 在Docker注册表上更新映像或存储库时接收通知 [@https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max](https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max).
- [Docker plugin for Jenkins](https://github.com/jenkinsci/docker-plugin/) -  docker插件的目的是能够使用docker主机动态配置slave，运行单个构建，然后拆除该slave.
- [Dockupdater](https://github.com/dockupdater/dockupdater) - 自动使您的泊坞窗服务和泊坞窗容器保持最新状态
- [Drone](https://github.com/drone/drone) - 基于Docker构建的持续集成服务器，使用YAML文件进行配置.
- [GitLab Runner](https://gitlab.com/gitlab-org/gitlab-runner) -  GitLab已经集成了CI，可以使用GitLab运行程序来测试，构建和部署您的代码.
- [GOCD-Docker](https://github.com/gocd/gocd-docker)在docker容器中转到Server和Agent以进行配置.
- [Microservices Continuous Deployment](https://github.com/francescou/docker-continuous-deployment) - 持续部署微服务应用程序.
- [mu](https://github.com/stelligent/mu) - 通过AWS CodePipeline，CodeBuild和ECS配置容器应用程序的CI / CD的工具 [@Stelligent](https://github.com/stelligent)
- [Screwdriver :heavy_dollar_sign:](https://screwdriver.cd/) - 雅虎的OpenSource构建平台，专为持续交付而设计.
- [Skipper](https://github.com/Stratoscale/skipper) - 轻松将您的Git存储库停靠 [@Stratoscale](https://github.com/Stratoscale)
- [SwarmCI](https://github.com/ghostsquad/swarmci) - 在Docker Swarm中创建分布式，隔离的任务管道.
- [Watchtower](https://github.com/containrrr/watchtower) - 自动更新正在运行的Docker容器

### Development Environment

- [batect](https://github.com/charleskorn/batect) - 构建和测试环境作为代码工具：Docker化构建和测试环境变得简单 [@charleskorn](https://github.com/charleskorn)
- [Binci](https://github.com/binci/binci)   - 包含您的开发工作流程.  （原DevLab by [@TechnologyAdvice](https://github.com/TechnologyAdvice))
- [Boot2Docker](https://github.com/boot2docker/boot2docker) - 适用于OSX和Windows的Docker
- [construi](https://github.com/lstephen/construi) - 在Docker定义的环境中运行您的构建 [@lstephen](https://github.com/lstephen)
- [Crashcart](https://github.com/oracle/crashcart) - 通过[@Oracle] [oracle]将Linux二进制文件加载到正在运行的容器中进行故障排除
- [dde](https://github.com/whatwedo/dde)  ：构造： - 基于Docker的本地开发环境工具集.  通过 [@whatwedo](https://github.com/whatwedo)
- [Devstep](https://github.com/fgrehm/devstep) ：skull： - 开发环境由Docker和buildpacks驱动，由[@fgrehm] [fgrehm]
- [Dinghy](https://github.com/codekitchen/dinghy) - 使用Docker Machine与Virtualbox，vmware，xhyve或parallels在Mac OS X上使用Docker的另一种方法
- [DIP](https://github.com/bibendi/dip)   -  CLI实用程序，用于直接配置和与docker-compose配置的应用程序交互.  通过 [@bibendi](https://github.com/bibendi)
- [DLite](https://github.com/nlf/dlite)   - 在OSX上使用Docker的最简单方法，无需VM.  通过 [@nlf](https://github.com/nlf)
- [dobi](https://github.com/dnephin/dobi)   -  Docker应用程序的构建自动化工具.  通过 [@dnephin](https://github.com/dnephin)
- [DockerBuildManagement](https://github.com/DIPSAS/DockerBuildManagement)   -  Build Management是一个python应用程序，随pip一起安装.  该应用程序通过配置描述如何构建，测试，运行或发布容器化解决方案的单个yaml文件，可以轻松管理基于Docker的构建系统.
- [Docker Missing Tools](https://github.com/nandoquintana/docker-missing-tools)   - 一组bash命令，用于快捷典型的docker dev-ops.  在代码存储库中创建典型帮助程序脚本（如“build.sh”和“deploy.sh”）的替代方法.  通过 [@NandoQuintana](https://github.com/nandoquintana).
- [Docker osx dev](https://github.com/brikis98/docker-osx-dev) - 在OS X上使用Docker的高效开发环境 [@brikis98](https://github.com/brikis98)
- [Docker-Arch](https://github.com/Ph3nol/Docker-Arch)   - 从1个简单的YAML文件生成Web / CLI项目Dockerized开发环境.  通过 [@Ph3nol](https://github.com/ph3nol)
- [Docker-sync](https://github.com/EugenMayer/docker-sync) - 大幅提升表现（[50-70x](https://github.com/EugenMayer/docker-sync/wiki/4.-Performance) ）在Mac OS X / Windows和Linux上使用Docker进行开发时，将代码共享到容器中.  通过 [@EugenMayer](https://github.com/EugenMayer)
- [docker-vm](https://github.com/shyiko/docker-vm) - 简单而透明的替代boot2docker（由Vagrant支持） [@shyiko](https://github.com/shyiko)
- [Dusty](https://github.com/gamechanger/dusty) -  OS X上的托管Docker开发环境
- [Eclipse Che](https://github.com/eclipse/che) - 具有Docker运行时，云IDE，下一代Eclipse IDE的开发人员工作区服务器
- [EnvCLI](https://github.com/EnvCLI/EnvCLI)   - 用项目特定的docker容器替换Node，Go，...的本地安装.  通过 [@EnvCLI](https://github.com/EnvCLI)
- [footloose](https://github.com/weaveworks/footloose) - 旋转容器，看起来像虚拟机 - 通过 [@dlespiau](https://github.com/dlespiau)
- [forward2docker](https://github.com/bsideup/forward2docker) ：skull： - 用于将端口从localhost自动转发到在boot2docker VM中运行的Docker容器上的端口的实用程序 [@bsideup](https://github.com/bsideup)
- [Lando](https://github.com/lando/lando)   -  Lando适用于希望快速指定并轻松实现开发项目所需的服务和工具的开发人员.  通过 [Tandem](https://thinktandem.io/)
- [Vagga](https://github.com/tailhook/vagga)   -  Vagga是一种没有守护进程的集装箱工具.  它是一个完全用户空间容器引擎，受Vagrant和Docker的启发，专门用于开发环境 [@tailhook](https://github.com/tailhook/)

### Garbage Collection

- [caduc](https://github.com/tjamet/caduc) - 最近没有使用的码头工垃圾收集器清理工具
- [Docker Clean](https://github.com/ZZROTDesign/docker-clean) - 一个清理Docker容器，图像和卷的脚本 [@zzrotdesign](https://github.com/ZZROTDesign)
- [Docker-cleanup](https://github.com/meltwater/docker-cleanup) - 自动Docker镜像，容器和卷清理 [@meltwater](https://github.com/meltwater)
- [docker-custodian](https://github.com/Yelp/docker-custodian)   - 让docker主机保持整洁.  通过 [@Yelp](https://github.com/Yelp)
- [docker-garby](https://github.com/konstruktoid/docker-garby) -  Docker垃圾收集脚本 [@konstruktoid](https://github.com/konstruktoid).
- [docker-gc](https://github.com/spotify/docker-gc) - 一个cron作业，将通过[@spotify] [spotify]删除旧的已停止的容器和未使用的图像
- [sherdock](https://github.com/rancher/sherdock) ：头骨： -  [@rancher] [牧场主]基于正则表达式的图像自动GC

### Serverless

- [AMP](https://github.com/appcelerator-archive/amp)  ：skull： -  Docker的开源统一CaaS / FaaS平台，包括电池.  通过 [@Appcelerator](https://github.com/appcelerator-archive)
- [Apache OpenWhisk](https://github.com/apache/openwhisk)   - 无服务器的开源云平台，可响应任何规模的事件执行功能.  通过 [@apache](https://github.com/apache)
- [Docker-Lambda](https://github.com/lambci/docker-lambda)   - 复制实时AWS Lambda环境的Docker镜像和测试运行器.  通过 [@lamb-ci](https://github.com/lambci)
- [Funker](https://github.com/bfirsh/funker-example-voting-app)   - 作为Docker容器示例投票应用程序的功能.  通过 [@bfirsh](https://github.com/bfirsh)
- [IronFunctions](https://github.com/iron-io/functions) - 无服务器微服务平台FaaS（Funcitons即服务），它使用Docker容器运行任何语言或AWS Lambda函数
- [OpenFaaS](https://github.com/openfaas/faas)   -  Docker和Kubernetes的完整无服务器功能框架.  通过 [OpenFaaS](https://github.com/openfaas)
- [SCAR](https://github.com/grycap/scar) - 无服务器容器感知架构（SCAR）是一个无服务器框架，允许在无服务器环境（例如Lambda）中轻松部署和执行容器（例如Docker） [@grycap](https://github.com/grycap)

### Testing

- [Container Structure Test](https://github.com/GoogleContainerTools/container-structure-test)   - 通过检查命令的输出或文件系统的内容来验证图像结构的框架.  通过[@GoogleContainerTools] [googlecontainertools]
- [dgoss](https://github.com/aelsabbahy/goss/tree/master/extras/dgoss) - 基于YAML的快速工具，用于验证docker容器.
- [DockerSpec](https://github.com/zuazo/dockerspec)   - 一个小型的Ruby Gem，可以轻松地针对Dockerfiles或Docker镜像运行RSpec和Serverspec，Infrataster和Capybara测试.  通过 [@zuazo](https://github.com/zuazo)
- [Dockunit](https://github.com/dockunit/platform)  ：skull： - 基于Docker的集成测试.  基于节点的简单实用程序，用于运行基于Docker的单元测试.  通过 [@dockunit](https://github.com/dockunit)
  -  [InSpec] [inspec]  -  InSpec是一个基础设施的开源测试框架，具有人机阅读和机器可读语言，用于指定合规性，安全性和策略要求.  通过 [@chef](https://github.com/chef)
- [Pumba](https://github.com/alexei-led/pumba)   -  Docker的混沌测试工具.  可以部署在kubernetes和CoreOS集群上.  通过 [@alexei-led](https://github.com/alexei-led)

### Wrappers

- [Ansible](https://docs.ansible.com/ansible/latest/modules/docker_container_module.html)   - 管理Docker容器的生命周期.  通过RedHat
- [Azk](https://github.com/azukiapp/azk) - 在本地计算机上协调开发环境 [@azukiapp](https://github.com/azukiapp)
- [Beluga](https://github.com/cortexmedia/Beluga)  ：skull： - 用于在单个服务器或少量服务器上部署docker容器的CLI.  通过 [@cortextmedia](https://github.com/cortexmedia)
- [dexec](https://github.com/docker-exec/dexec) - 用Go编写的命令行界面，用于运行Docker Exec映像的代码.
- [dockerized](https://github.com/benzaita/dockerized-cli) - 在容器中无缝执行命令.
- [Dray](https://github.com/CenturyLinkLabs/dray) -  [@CenturyLinkLabs] [centurylinklabs]管理基于容器的工作流程执行的引擎
- [FuGu](https://github.com/mattes/fugu) -  Docker运行包装器而没有编排 [@mattes](https://github.com/mattes)
- [Shutit](https://github.com/ianmiell/shutit) - 用于构建和维护复杂Docker部署的工具 [@ianmiell](https://github.com/ianmiell)
- [subuser](https://github.com/subuser-security/subuser) - 使得在Docker中安全且可移植地运行图形桌面应用程序变得容易
- [Turbo](https://github.com/ramitsurana/turbo)   - 简单而强大的码头工具实用程序.  由[@ramitsurana] [ramitsurana]
- [udocker](https://github.com/indigo-dc/udocker) - 在没有root权限的批处理或交互式系统中执行简单docker容器的工具 [@inidigo-dc](https://github.com/indigo-dc)
- [Vagrant - Docker provider](https://www.vagrantup.com/docs/docker/basics.html) - 良好的起点是 [vagrant-docker-example](https://github.com/bubenkoff/vagrant-docker-example) 通过 [@bubenkoff](https://github.com/bubenkoff)

## Services based on Docker (:heavy_dollar_sign:)

### CI Services

- [CircleCI](https://circleci.com/) ：heavy_dollar_sign： - 从构建环境中推送或拉出Docker镜像，或者在CircleCI上构建和运行容器.
- [CodeFresh](https://codefresh.io)  ：heavy_dollar_sign： - 构建，测试和共享Docker应用程序所需的一切.  提供自动端到端测试.
- [CodeShip](https://cms.codeship.com/features/pro) ：heavy_dollar_sign： - 使用您已建立的Docker工作流程，同时使用专用于速度和安全性的托管平台自动执行测试和部署任务.
- [ConcourseCI](https://concourse-ci.org) ：heavy_dollar_sign： - 面向管道开发人员和DevOps团队的CI SaaS平台.
- [Semaphore CI](https://semaphoreci.com/) ：heavy_dollar_sign： - 一种高性能云解决方案，可以轻松构建，测试容器并将其运送到生产中.
- [Shippable](https://app.shippable.com/) ：heavy_dollar_sign： - 面向开发人员和DevOps团队的SaaS平台，可显着减少构建，测试和部署代码到生产所需的时间.
- [TravisCI](https://travis-ci.org/) ：heavy_dollar_sign： - 免费的github为开发人员和Devops项目提供持续集成的Saas平台.

### CaaS

- [Amazon ECS](https://aws.amazon.com/ecs/) ：heavy_dollar_sign： -  EC2上支持Docker容器的管理服务.
- [Arukas](https://arukas.io/) ：heavy_dollar_sign： - 以Heroku为灵感的CaaS
- [Azure AKS](https://azure.microsoft.com/en-us/services/kubernetes-service/)  ：heavy_dollar_sign： - 简化Kubernetes管理，部署和运营.  使用完全托管的Kubernetes容器编排服务.
- [Cloud 66](https://www.cloud66.com) ：heavy_dollar_sign： - 作为服务的全栈托管容器管理
- [Codenvy](https://codenvy.com) ：heavy_dollar_sign： - 为开发团队提供一键式Docker环境和云工作区
- [ContainerShip Cloud](https://containership.io) ：heavy_dollar_sign： - 多云容器托管自动化平台.
- [Docker Cloud](https://cloud.docker.com/) ：heavy_dollar_sign： - 前图腾
- [Dockhero](https://dockhero.io/)  ：heavy_dollar_sign： -  Dockhero是一个Heroku附加组件，它将Docker镜像转换为连接到Heroku应用程序的微服务.  目前处于测试阶段
- [Giant Swarm](https://giantswarm.io/)  ：heavy_dollar_sign： - 简单的微服务基础设施.  在几秒钟内部署您的容器.
- [Google Container Engine](https://cloud.google.com/kubernetes-engine/docs/) ：heavy_dollar_sign： - 由[Kubernetes] [kubernetes]提供支持的Google云计算上的Docker容器.
- [Jelastic Cloud](https://jelastic.cloud/)  ：heavy_dollar_sign： - “易于使用”的容器托管平台，具有自动垂直和水平缩放功能.  全球超过50家托管服务提供商.
- [Mesosphere DC/OS](https://d2iq.com/solutions/mesosphere) :heavy_dollar_sign: - Integrated platform for data and containers built on Apache Mesos by [@mesosphere](https://d2iq.com)
- [OpenShift Dedicated](https://www.openshift.com/products/dedicated/) ：heavy_dollar_sign： - 一个托管的[OpenShift] [openshift]集群，用于运行由Red Hat管理的Docker容器.
- [Sloppy.io](https://sloppy.io/en/) ：heavy_dollar_sign： - 用于容器部署和托管的一体化解决方案 - 在德国制造和托管
- [Triton](https://www.joyent.com/) ：heavy_dollar_sign： -  Joyent的弹性容器本地基础结构.

### Monitoring Services

- [AppDynamics](https://www.appdynamics.com/community/exchange/extension/docker-monitoring-extension/) ：heavy_dollar_sign： -  AppDynamics为企业提供了对应用程序性能，用户性能和业务性能的实时洞察，因此他们可以在日益复杂的软件驱动的世界中更快地移动.
- [Axibase Time-Series Database](https://axibase.com/products/axibase-time-series-database/writing-data/docker-cadvisor/)  ：heavy_dollar_sign： - 长期保留Docker的容器统计信息和内置仪表板.  使用原生Google cAdvisor存储驱动程序收集.
- [CA Technologies Docker Monitoring](https://www.ca.com/us/products/docker-monitoring.html)  ：heavy_dollar_sign： - 来自CA的敏捷运营解决方案提供了现代Docker监控企业所需的，以加速和优化微服务的性能以及运行它们的动态Docker环境.  监控Docker环境和在其中运行的应用程序.
- [Collecting docker logs and stats with Splunk](https://www.splunk.com/blog/2015/08/24/collecting-docker-logs-and-stats-with-splunk.html)
- [Datadog](https://www.datadoghq.com/)  ：heavy_dollar_sign： -  Datadog是一种用于大规模云环境的全栈监控服务，可聚合来自服务器，数据库和应用程序的指标/事件.  它包括对Docker，Kubernetes和Mesos的支持.
- [Prometheus](https://prometheus.io/) ：heavy_dollar_sign： - 开源服务监控系统和时间序列数据库
- [Site24x7](https://www.site24x7.com/docker-monitoring.html) ：heavy_dollar_sign： -  DevOps和IT的Docker监控是一种SaaS按主机付费模式
- [SPM for Docker](https://github.com/sematext/sematext-agent-docker)  ：heavy_dollar_sign： - 监控主机和容器指标，Docker事件和日志.  自动日志解析器.  异常检测和警报指标和日志. [@sematext](https://github.com/sematext)
- [Sysdig Monitor](https://sysdig.com/products/monitor/)  ：heavy_dollar_sign： -  Sysdig Monitor可用作软件或SaaS服务，以使用系统调用来监视，警报和排除容器故障.  它具有Docker和Kubernetes的容器特定功能.

## Useful Resources

- **[Valuable Docker Links](https://www.nkode.io/2014/08/24/valuable-docker-links.html) **关于码头工人的高质量文章！  **必看**
- [Cloud Native Landscape](https://github.com/cncf/landscape)
- [Docker Weekly](https://blog.docker.com/docker-weekly-archives/) 巨大的资源
- [Programming Community Curated Resources for learning Docker](https://hackr.io/tutorials/learn-docker)
- [Docker in Action, Second Edition](https://www.manning.com/books/docker-in-action-second-edition)
- [Docker Community on Hashnode](https://hashnode.com/n/docker)
- [Docker in Practice, Second Edition](https://www.manning.com/books/docker-in-practice-second-edition)
- [Docker dev bookmarks](https://www.bookmarks.dev/search?q=docker) - 使用标签 [docker](https://www.bookmarks.dev/tagged/docker)
- [Docker packaging guide for Python](https://pythonspeed.com/docker/) - 关于Python的Docker包装细节的一系列详细文章.

## Awesome Lists

- [Awesome CI/CD](https://github.com/ciandcd/awesome-ciandcd) - 不是特定于码头工具但相关.
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes) by [@ramitsurana] [ramitsurana]
- [Awesome Linux Container](https://github.com/Friz-zy/awesome-linux-containers) 关于容器的一般情况比这个回购更通用 [@Friz-zy](https://github.com/Friz-zy).
- [Awesome Selfhosted](https://github.com/Kickball/awesome-selfhosted)  可以通过以传统方式（设置本地Web服务器并从那里运行应用程序）或在Docker容器中运行的本地托管的自由软件网络服务和Web应用程序列表.  通过 [@Kickball](https://github.com/Kickball)
- [Awesome Sysadmin](https://github.com/n1trux/awesome-sysadmin) 通过 [@n1trux](https://github.com/n1trux)
- [ToolsOfTheTrade](https://github.com/cjbarber/ToolsOfTheTrade) 一个SaaS和Onfrontise应用程序列表 [@cjbarber](https://github.com/cjbarber)

## Good Tips

- [Dealing with linked containers dependency in docker-compose](http://brunorocha.org/python/dealing-with-linked-containers-dependency-in-docker-compose.html) 通过 [@rochacbruno](https://github.com/rochacbruno)
- [Docker Caveats](http://docker-saigon.github.io/post/Docker-Caveats/) 关于在生产中运行Docker你应该知道什么（2016年4月11日发布）**必须看到**
- [Docker Containers on the Desktop](https://blog.jessfraz.com/post/docker-containers-on-the-desktop/) -  [@jessfraz] [jessfraz]的最有趣的方式**了解码头工人 [presentation](https://www.youtube.com/watch?v=1qlLUf7KtAw) 关于它@ DockerCon 2015
- [Docker vs. VMs? Combining Both for Cloud Portability Nirvana](https://blogs.flexera.com/cloud/cloud-management-best-practices/docker-vs-vms-combining-both-for-cloud-portability-nirvana/)
- [Don't Repeat Yourself with Anchors, Aliases and Extensions in Docker Compose Files](https://medium.com/@kinghuang/docker-compose-anchors-aliases-extensions-a1e4105d70bd) 通过 [@King Chung Huang](https://github.com/kinghuang)
- [GUI Apps with Docker](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/) 通过[@fgrehm] [fgrehm]

## Raspberry Pi & ARM

- [Docker Pirates ARMed with explosive stuff](https://blog.hypriot.com/) 关于Raspberry Pi上SD卡的群集，群集，docker，预安装映像的巨大资源
- [Get Docker up and running on the RaspberryPi in three steps](https://github.com/umiddelb/armhf/wiki/Get-Docker-up-and-running-on-the-RaspberryPi-%28ARMv6%29-in-three-steps)
- [git push docker containers to linux devices](https://www.balena.io) 物联网的现代DevOps，利用git和Docker.
- [Installing, running, using Docker on armhf (ARMv7) devices](https://github.com/umiddelb/armhf/wiki/Installing,-running,-using-docker-on-armhf-%28ARMv7%29-devices)

## Security

- [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
- [CVE Scanning Alpine images with Multi-stage builds in Docker 17.05](https://github.com/tomwillfixit/alpine-cvecheck) 通过 [@tomwillfixit](https://twitter.com/tomwillfixit)
- [Docker and SELinux](https://www.projectatomic.io/docs/docker-and-selinux/)
- [Docker Secure Deployment Guidelines](https://github.com/GDSSecurity/Docker-Secure-Deployment-Guidelines)
- [Docker Security - Quick Reference](https://binarymist.io/publication/docker-security/)
- [Docker Security Cheat Sheet](https://github.com/konstruktoid/Docker/blob/master/Security/CheatSheet.adoc)
- [Docker Security: Are Your Containers Tightly Secured to the Ship? SlideShare](https://fr.slideshare.net/MichaelBoelen/docker-security-are-your-containers-tightly-secured-to-the-ship)
- [How CVE's are handled on Offical Docker Images](https://github.com/docker-library/official-images/issues/1448)
- [Lynis is an open source security auditing tool including Docker auditing](https://cisofy.com/lynis/)
- [Security Best Practices for Building Docker Images](https://linux-audit.com/tag/docker/)
- [Software Engineering Radio interview of Docker Security Team Lead (Diogo Mónica)](https://www.se-radio.net/2017/05/se-radio-episode-290-diogo-monica-on-docker-security/)
- [Ten Docker Image Security Best Practices Cheat Sheet](https://snyk.io/blog/10-docker-image-security-best-practices/)
- [Top ten most popular docker images each contain at least 30 vulnerabilities](https://snyk.io/blog/top-ten-most-popular-docker-images-each-contain-at-least-30-vulnerabilities/)
- [Tuning Docker with the newest security enhancements](https://opensource.com/business/15/3/docker-security-tuning)
- [Understanding Docker security and best practices](https://blog.docker.com/2015/05/understanding-docker-security-and-best-practices/) （2015年5月5日写）

## Videos

- [Contributing to Docker by Andrew "Tianon" Page (InfoSiftr)](https://www.youtube.com/watch?v=1jwo8-1HYYg) (34:31)
- [Deploying and scaling applications with Docker, Swarm, and a tiny bit of Python magic](https://www.youtube.com/watch?v=GpHMTR7P2Ms) （3:11:06）[@jpetazzo] [jpetazzo]
- [Docker and SELinux by Daniel Walsh from Red Hat](https://www.youtube.com/watch?v=zWGFqMuEHdw) (40:23)
- [Docker for Developers](https://www.youtube.com/watch?v=FdkNAjjO5yQ) （54:26）by [@jpetazzo] [jpetazzo] &lt;==好的介绍，背景，演示
- [Docker in Production](https://www.youtube.com/watch?v=Glk5d5WP6MI) 由[@jpetazzo] [jpetazzo]（36:05）
- [Docker: How to Use Your Own Private Registry](https://www.youtube.com/watch?v=CAewZCBT4PI) (15:01)
- [Extending Docker with Plugins](https://vimeo.com/110835013) (15:21)
- [From Local Docker Development to Production Deployments](https://www.youtube.com/watch?v=7CZFpHUPqXw) 通过[@jpetazzo] [jpetazzo] @ AWS re：Invent 2015
- [Immutable Infrastructure with Docker and EC2 by Michael Bryzek (Gilt)](https://www.youtube.com/watch?v=GaHzdqFithc) (42:04)
- [Introduction to Docker and containers](https://www.youtube.com/watch?v=ZVaRK10HBjo) （3:09:00）[@jpetazzo] [jpetazzo]
- [Logging on Docker: What You Need to Know](https://vimeo.com/123341629) (51:27)
- [Performance Analysis of Docker - Jeremy Eder](https://www.youtube.com/watch?v=6f2E6PKYb0w) (1:36:58)
- [Scalable Microservices with Kubernetes](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615) 免费Udacity课程
- [State of containers: a debate with CoreOS, VMware and Google](https://www.youtube.com/watch?v=IiITP3yIRd8) (27:38)
- [SysAdminCasts: Introduction to Docker](https://sysadmincasts.com/episodes/31-introduction-to-docker) (15:49)

## Communities and Meetups

## Brazilian

- [Docker BR on Slack](http://docker-br.herokuapp.com) - 自动邀请网址
- [Docker BR on Telegram](https://telegram.me/dockerbr)

## Chinese

- [DockerOne](http://dockone.io/) Docker社区（中文）by [@LiYingJie](http://dockone.io/people/%E6%9D%8E%E9%A2%96%E6%9D%B0)

## English

- [Docker Community](https://www.docker.com/docker-community)
- [Docker Events](https://events.docker.com)
- [Docker On Line Meetup](https://www.meetup.com/Docker-Online-Meetup/)
- [Docker Reddit Community](https://www.reddit.com/r/docker/)

## Russian

- [Docker Russian-speaking Community](https://t.me/docker_ru)

## Spanish

- [Docker Tips](https://dockertips.com/)

[贡献]：https：//github.com/veggiemonk/awesome-docker/blob/master/.github/CONTRIBUTING.md
[calico]：https：//github.com/projectcalico/calicoctl
[centurylinklabs]：https：//github.com/CenturyLinkLabs
[containsx]：https：//github.com/ContainX
[coreos]：https：//github.com/coreos
[cncf]：https：//www.cncf.io
[crazy-max]：https：//github.com/crazy-max
[发行]：https：//github.com/docker/distribution
[docker-for-windows]：https：//docs.docker.com/docker-for-windows/
[docker]：https：//github.com/docker
[editreadme]：https：//github.com/veggiemonk/awesome-docker/edit/master/README.md
[fgrehm]：https：//github.com/fgrehm
[gesellix]：https：//github.com/gesellix
[genuinetools]：https：//github.com/genuinetools
[gliderlabs]：https：//github.com/gliderlabs
[google]：https：//github.com/google
[googlecontainertools]：https：//github.com/GoogleContainerTools
[inspec]：https：//github.com/inspec/inspec
[jessfraz]：https：//github.com/jessfraz
[jpetazzo]：https：//github.com/jpetazzo
[jwilder]：https：//github.com/jwilder
[kubernetes]：https：//kubernetes.io
[nvidia]：https：//github.com/nvidia
[nginxproxy]：https：//github.com/jwilder/nginx-proxy
[openshift]：https：//www.okd.io
[oracle]：https：//github.com/oracle
[progrium]：https：//github.com/progrium
[ramitsurana]：https：//github.com/ramitsurana
[rancher]：https：//github.com/rancher
[sindresorhus]：https：//github.com/sindresorhus/awesome
[spotify]：https：//github.com/spotify
[vegasbrianc]：https：//github.com/vegasbrianc
[vfarcic]：https：//github.com/vfarcic
[weave]：https：//github.com/weaveworks/weave
