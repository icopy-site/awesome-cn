<div class="github-widget" data-repo="veggiemonk/awesome-docker"></div>
## Awesome Docker [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)][sindresorhus] [![Netlify Status](https://api.netlify.com/api/v1/badges/8ca86717-11ba-46d4-9d0a-700d8527f13b/deploy-status)](https://app.netlify.com/sites/awesome-docker/deploys)<!-- omit in toc -->

&gt; 精选的 Docker 资源和项目列表

If you would like to contribute, please read [CONTRIBUTING.md][contributing] first.
它包含许多提示和指南，有助于让事情井井有条.
只需单击 [README.md][editreadme] 即可提交 [pull request][editreadme].
如果这个列表不完整，你可以 [contribute][editreadme] 来完成. 这是一个很棒的视频教程，可以学习如何 [contribute on Github](https://egghead.io/lessons/javascript-identifying-how-to-contribute-to-an-open-source-project-on-github).

**_你可以看到更新 [TWITTER](https://twitter.com/awesome_docker)_**

 &gt; **请**帮助整理这些资源，以便新手可以_轻松找到_和_理解_. 查看如何 **[贡献][贡献]** 获取提示！

 **_如果您在此处看到一个链接（不再）适合，您可以通过提交 [pull request][editreadme] 来修复它以改进此文件. 谢谢你！_**

The creators and maintainers of this list do not receive any form of payment to accept a change made by any contributor. This page is not an official Docker product in any way. It is a list of links to projects and is maintained by volunteers. Everybody is welcome to contribute. The goal of this repo is to index open-source projects, not to advertise for profit.

所有环节均通过自家烘焙监控和测试 [Node.js script](https://github.com/veggiemonk/awesome-docker/blob/master/.github/workflows/pull_request.yml)


<!-- TOC -->


<!-- /TOC -->

## Legend

- 被遗弃：头骨：
- 测试版：建设：
- 货币化：heavy_dollar_sign：

## What is Docker

 &gt; Docker 是一个供开发人员和系统管理员构建、发布和运行分布式应用程序的开放平台.  Docker 由便携式轻量级运行时和打包工具 Docker Engine 以及用于共享应用程序和自动化工作流的云服务 Docker Hub 组成，Docker 使应用程序能够从组件快速组装起来，并消除了开发、QA 和生产环境之间的摩擦. 因此，IT 可以更快地交付并在笔记本电脑、数据中心 VM 和任何云上运行相同的应用程序，无需更改.

_Source:_ [What is Docker](https://www.docker.com/why-docker/)

## Where to start

-   [Benefits of using Docker](https://semaphoreci.com/blog/docker-benefits) 用于开发和交付，并附有实用的采用路线图.
-   [Bootstrapping Microservices](https://www.manning.com/books/bootstrapping-microservices-with-docker-kubernetes-and-terraform) 经过 [Ashley Davis](https://twitter.com/ashleydavis75) - A practical and project-based guide to building applications with microservices, starts 经过 building a Docker image for a single microservice and publishing it to a private container registry, finishes 经过 deploying a complete microservices application to a production Kubernetes cluster.
-   [Docker Curriculum](https://github.com/prakhar1989/docker-curriculum) ：Docker 入门综合教程. 教授如何使用 Docker 以及如何通过 Elastic Beanstalk 和 Elastic Container Service 在 AWS 上部署 dockerized 应用程序.
-   [Docker Documentation](https://docs.docker.com/): 官方文档.
-   [Docker for beginners](https://github.com/groda/big_data/blob/master/docker_for_beginners.md) : 面向需要学习 Docker 基础知识的初学者的教程——来自“Hello world!” 到与容器的基本交互，以及对基本概念的简单解释.
-   [Docker for novices](https://www.youtube.com/watch?v=xsjSadjKXns) 为从未使用过 Docker 的开发人员和测试人员介绍 Docker.  （视频 1h40，录制于 linux.conf.au 2019 — 新西兰基督城），作者：Alex Clews.
-  [Docker Latest Tutorial](https://www.techgeekbuzz.com/tutorial/docker/what-is-docker/) — 这是一系列最新的 docker 教程，在这里您可以了解什么是 docker、docker 生命周期、如何在 Docker 中运行 Nginx Web Server？、如何在 docker 容器上运行 mysql、如何在 doceker 上使用 Python 以及许多其他重要主题.  
-   [Docker simplified in 55 seconds](https://www.youtube.com/watch?v=vP_4DlOH1G4) ：Docker 的动画高级介绍. 将其视为视觉 tl;dr，可以更轻松地研究更复杂的学习材料.
-   [Docker Training](https://training.mirantis.com) :heavy_dollar_sign:
-   [Docker Tutorial for Beginners (Updated 2019 version)](https://hashnode.com/post/docker-tutorial-for-beginners-cjrj2hg5001s2ufs1nker9he2)  — 在本 Docker 教程中，您将学习所有基础知识并学习如何容器化 Node.js 和 Go 应用程序. 即使您不熟悉这些语言，您也应该可以轻松地按照本教程进行操作并使用任何其他语言.
-   [Learn Docker](https://github.com/dwyl/learn-docker)：分步教程和更多资源（视频、文章、备忘单），作者： [@dwyl](https://github.com/dwyl)
-   [Play With Docker](https://training.play-with-docker.com/) ：PWD 是从初学者到高级用户开始使用 Docker 的好方法.  Docker 直接在您的浏览器中运行.
-   [Practical Guide about Docker Commands in Spanish](https://github.com/brunocascio/docker-espanol) 本西班牙语指南包含基本 docker 命令的使用和现实生活中的示例.
-   [Practical Introduction to Container Terminology](https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction) 容器技术的前景不仅仅局限于 docker. 如果不能很好地掌握术语，就很难掌握 docker 和（选择你最喜欢的 CRI-O、rkt、lxc/lxd）之间的主要区别，或者理解 Open Container Initiative 正在做些什么来标准化容器技术.
-   [The Docker Handbook](https://docker-handbook.farhan.dev/) 一本教您基础知识、最佳实践和一些中级 Docker 功能的开源书籍. 本书托管于 [fhsinchy/the-docker-handbook](https://github.com/fhsinchy/the-docker-handbook) 并且项目托管在 [fhsinchy/docker-handbook-projects](https://github.com/fhsinchy/docker-handbook-projects) 存储库.
   

**备忘单**

-   [@eon01](https://github.com/eon01/DockerCheatSheet)
-   [@dimonomid](https://github.com/dimonomid/docker-quick-ref) (PDF)
-   [@JensPiegsa](https://github.com/JensPiegsa/docker-cheat-sheet)
-   [@wsargent](https://github.com/wsargent/docker-cheat-sheet) （最受欢迎）

## Where to start (Windows)

-   [A Comparative Study of Docker Engine on Windows Server vs Linux Platform](https://collabnix.com/a-comparative-study-of-docker-engine-on-windows-server-vs-linux-platform/) 比较 Docker 在 Windows 和 Linux 上的功能集和实现
-   [Docker on Windows behind a firewall](https://toedter.com/2015/05/11/docker-on-windows-behind-a-firewall/) 经过 [@kaitoedter](https://twitter.com/kaitoedter)
-   [Docker Quick Tutorial](https://vegibit.com/docker-quick-tutorial/) Introduces you to the official Getting Started Tutorial using Windows 10 and Hyper-V.
-   [Docker Reference Architecture: Modernizing Traditional .NET Framework Applications](https://docs.mirantis.com/containers/v3.0/dockeree-ref-arch/app-dev/modernize-dotnet-apps.html) - 您将学习识别适合容器化的 .NET Framework 应用程序类型，容器化的“提升和转移”方法.
-   [Docker with Microsoft SQL 2016 + ASP.NET](https://blog.alexellis.io/docker-does-sql2016-aspnet/) 在 Docker 中运行 ASP.NET 和 SQL Server 工作负载的演示
-   [Exploring ASP.NET Core with Docker in both Linux and Windows Containers](https://www.hanselman.com/blog/exploring-aspnet-core-with-docker-in-both-linux-and-windows-containers) 使用 [Docker for Windows][docker-for-windows] 在 Linux 和 Windows 容器中运行 ASP.NET Core 应用程序
-   [Running a Legacy ASP.NET App in a Windows Container](https://blog.sixeyed.com/dockerizing-nerd-dinner-part-1-running-a-legacy-asp-net-app-in-a-windows-container/) 对旧版 ASP.NET 应用进行 Docker 化并作为 Windows 容器运行的步骤
-   [Windows Containers and Docker: The 101](https://www.youtube.com/watch?v=N7SG2wEyQtM) :movie_camera: - 20 分钟的概述，使用 Docker 运行 PowerShell、ASP.NET Core 和 ASP.NET 应用程序
-   [Windows Containers Quick Start](https://learn.microsoft.com/en-us/virtualization/windowscontainers/about/) Windows 容器概述，深入了解 Windows 10 和 Windows Server 2016 快速入门

---

## Projects

- Moby = 开源开发
- Docker CE = 基于 Moby 的免费产品发布
- Docker EE = 基于 Docker CE 的商业产品发布.

&gt; Docker EE 与 Docker CE 在相同的代码库上，因此也是从 Moby 构建的，添加了商业组件，例如“docker 数据中心/通用控制平面”

-   [Moby](https://github.com/moby/moby)
-   [Docker Images](https://hub.docker.com)
-   [Docker Compose](https://github.com/docker/compose/) （使用 Docker 定义和运行多容器应用程序）
-   [Docker Machine](https://github.com/docker/machine) （以容器为中心的世界的机器管理）
- [Docker Registry][distribution]（用于打包、运送、存储和交付内容的 Docker 工具集）
-   [Docker Swarm](https://github.com/docker/swarm) （Swarm：Docker 原生集群系统）

## Container Operations

### Container Composition

-   [bocker](https://github.com/icy/bocker)  (2) :skull: - 完全用 Bash 编写 Dockerfile. 可扩展且简单.  --&gt; 可重复使用 [@icy](https://github.com/icy)
-   [bocker](https://github.com/p8952/bocker) (1) :skull: - Docker 在 100 行 bash 中实现 [p8952](https://github.com/p8952)
-   [box](https://github.com/box-builder/box) ：skull： - 使用 mruby DSL 构建 Dockerfile 图像，包括展平和层操作
-   [Capitan](https://github.com/byrnedo/capitan) - 可组合的 docker 编排，增加了 [@byrnedo] 的脚本支持.
-   [compose_plantuml](https://github.com/funkwerk/compose_plantuml) :skull: - 通过 docker-compose 文件生成 Plantuml 图 [@funkwerk](https://github.com/funkwerk)
-   [Composerize](https://github.com/magicmark/composerize) - 将 docker run 命令转换为 docker-compose 文件
-   [crowdr](https://github.com/polonskiy/crowdr) - 用于管理多个 Docker 容器的工具（`docker-compose` 替代方案） [@polonskiy](https://github.com/polonskiy/)
-   [ctk](https://github.com/ctk-hq/ctk)  ：构造： - 用于基于容器的工作负载的可视化作曲家. 经过 [@corpulent](https://github.com/corpulent)
-   [docker-compose-graphviz](https://github.com/abesto/docker-compose-graphviz) :skull: - 将 docker-compose.yml 文件转换为 Graphviz .dot 文件 [@abesto](https://github.com/abesto)
-   [docker-config-update](https://github.com/sudo-bmitch/docker-config-update) - 用于更新 docker 配置和秘密的实用程序，用于在撰写文件中部署 [@sudo-bmitch](https://github.com/sudo-bmitch)
-   [draw-compose](https://github.com/Alexis-benoist/draw-compose) :skull: - 绘制 docker 架构的实用程序 [@Alexis-benoist](https://github.com/Alexis-benoist)
-   [elsy](https://github.com/cisco/elsy) - 基于 Docker 和 Docker Compose 的自以为是的多语言构建工具
-   [habitus](https://github.com/cloud66-oss/habitus) - Docker 的构建流程工具，作者： [@cloud66](https://github.com/cloud66)
-   [kompose](https://github.com/kubernetes/kompose) - 从 Docker Compose 到 Kubernetes
-   [Maestro](https://github.com/toscanini/maestro) :skull: -Maestro 提供了将多个 Docker 容器作为一个单元轻松启动、编排和管理的能力 [@tascanini](https://github.com/toscanini)
-   [percheron](https://github.com/ashmckenzie/percheron) :skull: - 用肌肉和智慧组织你的 Docker 容器 [@ashmckenzie](https://github.com/ashmckenzie)
-   [plash](https://github.com/ihucos/plash) - 容器运行和构建引擎 - 在 docker 中运行.
-   [podman-compose](https://github.com/containers/podman-compose) - [@containers][containers] 使用 podman 运行 docker-compose.yml 的脚本
-   [rocker-compose](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/grammarly/rocker-compose)  ：skull： - 具有幂等特性的 Docker 组合工具，用于部署由多个容器组成的应用程序. 经过[@https://github.com/veggiemonk/awesome-docker/blob/master/grammarly](https://github.com/veggiemonk/awesome-docker/blob/master/grammarly).
-   [rocker](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/grammarly/rocker)  :skull: - 扩展的 Dockerfile 生成器. 支持多个 FROM、MOUNTS、模板等，通过 [@https://github.com/veggiemonk/awesome-docker/blob/master/grammarly](https://github.com/veggiemonk/awesome-docker/blob/master/grammarly).
-   [Smalte](https://github.com/roquie/smalte)  – 在 docker 容器中动态配置需要静态配置的应用程序. 经过 [@roquie](https://github.com/roquie)
-   [Stacker](https://github.com/stacker/stacker-cli)  ：头骨： - Docker 撰写模板.  Stacker 提供了一个基于 Docker Compose 的抽象层和更好的 DX（开发人员体验）.
-   [Stitchocker](https://github.com/alexaandrov/stitchocker)  - 一个轻量级且快速的命令行实用程序，用于方便地对您的 docker-compose 多个容器服务进行分组. 经过 [@alexaandrov](https://github.com/alexaandrov)
-   [Zodiac](https://github.com/CenturyLinkLabs/zodiac)  :skull: - 一种轻量级工具，用于轻松部署和回滚 dockerized 应用程序. 通过 [@CenturyLinkLabs][centurylinklabs]

### Deployment and Infrastructure

-   [awesome-stacks](https://github.com/ethibox/awesome-stacks) - 使用一个 Docker 命令部署 80 多个开源 Web 应用程序
-   [blackfish](https://gitlab.com/blackfish/blackfish) - 一个 CoreOS VM，用于为开发和生产构建 swarm 集群 [@blackfish](https://gitlab.com/blackfish/)
-   [BosnD](https://gitlab.com/n0r1sk/bosnd) - BosnD，boatswain 守护进程 - 用于动态更改容器环境的动态配置文件编写器和服务重新加载器.
-   [Centurion](https://github.com/newrelic/centurion)  - Centurion 是 Docker 舰队的大规模部署工具. 它从 Docker 注册表中获取容器，并在具有正确环境变量、主机卷映射和端口映射的一组主机上运行它们. 经过 [@newrelic](https://github.com/newrelic)
-   [Clocker](https://github.com/brooklyncentral/clocker)  - Clocker 创建和管理 Docker 云基础设施.  Clocker 支持在 Docker 和 Marathon 上作为分布在多个主机上的容器运行的多节点应用程序的单击部署和运行时管理. 它利用 [Calico][calico] 和 [Weave][weave] 进行联网和 [Brooklyn](https://brooklyn.apache.org/) 用于应用程序蓝图. 经过 [@brooklyncentral](https://github.com/brooklyncentral)
-   [Conduit](https://github.com/ehazlett/conduit) - Docker 的实验部署系统 [@ehazlett](https://github.com/ehazlett)
-   [depcon](https://github.com/ContainX/depcon)  - Depcon 是用 Go 编写的，允许您轻松地将 Docker 容器部署到 Apache Mesos/Marathon、Amazon ECS 和 Kubernetes. 通过 [@ContainX][containx]
-   [deploy](https://github.com/ttiny/deploy)  :skull: -Git 和 Docker 部署工具. 介于简单的 Docker 组合工具和成熟的集群编排之间的中间地带 [@ttiny](https://github.com/ttiny)
-   [dockit](https://github.com/humblec/dockit)  :skull: - 执行 docker 操作并部署 gluster 容器！ 经过 [@humblec](https://github.com/humblec)
-   [gitkube](https://github.com/hasura/gitkube)  - Gitkube 是一个使用 `git push` 在 Kubernetes 上构建和部署 docker 镜像的工具. 经过 [@Hasura](https://github.com/hasura/).
-   [Grafeas](https://github.com/grafeas/grafeas)  - 关于容器元数据的通用 API，从图像和构建细节到安全漏洞. 经过 [grafeas](https://github.com/grafeas)
-   [Longshoreman](https://github.com/longshoreman/longshoreman)  ：skull： - Longshoreman 使用 Docker 自动化应用程序部署. 只需创建一个 Docker 存储库（或使用服务），使用 AWS 或 Digital Ocean（或任何你喜欢的）配置集群，并使用类似 Heroku 的 CLI 工具部署应用程序. 经过 [longshoreman](https://github.com/longshoreman)
-   [SwarmManagement](https://github.com/hansehe/SwarmManagement)  - Swarm Management 是一个 python 应用程序，使用 pip 安装. 该应用程序通过配置单个 yaml 文件来轻松管理 Docker Swarm，该文件描述要部署的堆栈以及要创建的网络、配置或机密.
-   [werf](https://github.com/werf/werf) - werf 是一个 CI/CD 工具，用于高效构建 Docker 镜像并使用 GitOps 将它们部署到 Kubernetes [@flant](https://github.com/flant)

### Monitoring

- [Autoheal](https://github.com/willfarrell/docker-autoheal) - 自动监控并重启不健康的 docker 容器.
- [Axibase Collector](https://github.com/axibase/docker-axibase-collector) - Axibase Collector streams performance counters, configuration changes and lifecycle events from the Docker engine(s) into Axibase Time Series Database for roll-up dashboards and integration with upstream monitoring systems.
- [cAdvisor](https://github.com/google/cadvisor)  - 分析正在运行的容器的资源使用情况和性能特征. 由 [@Google][google] 创建
- [Docker-Alertd](https://github.com/deltaskelta/docker-alertd) - 根据 docker 容器资源使用/统计数据监控和发送警报
- [Docker-Flow-Monitor](https://github.com/docker-flow/docker-flow-monitor) - 当 [@docker-flow][docker-flow] 自动更新或部署新服务时重新配置 Prometheus
- [Dockerana](https://github.com/dockerana/dockerana) :skull: - Graphite 和 Grafana 的打包版本，专门针对 Docker 的指标.
- [DockProc](https://gitlab.com/n0r1sk/dockproc) - 进程级容器的 I/O 监控.
- [dockprom](https://github.com/stefanprodan/dockprom) - 使用 Prometheus、Grafana、cAdvisor、NodeExporter 和 AlertManager 监控 Docker 主机和容器 [@stefanprodan](https://github.com/stefanprodan)
- [Doku](https://github.com/amerkurev/doku) - Doku 是一个简单的基于 Web 的应用程序，可让您监控 Docker 磁盘使用情况. [@amerkurev](https://github.com/amerkurev)
- [Dozzle](https://github.com/amir20/dozzle) - 使用浏览器或移动设备实时监控容器日志. [@amir20](https://github.com/amir20)
- [Dynatrace](https://www.dynatrace.com/solutions/container-monitoring/) ：heavy_dollar_sign：- 在不安装代理或修改运行命令的情况下监控容器化应用程序
- [Glances](https://github.com/nicolargo/glances) - 一个跨平台的基于 curses 的系统监控工具，由 Python 编写 [@nicolargo](https://github.com/nicolargo)
- [Grafana Docker Dashboard Template](https://grafana.com/grafana/dashboards/179-docker-prometheus-monitoring/) - Docker、Grafana 和 Prometheus 堆栈的模板 [@vegasbrianc][vegasbrianc]
- [HertzBeat](https://github.com/dromara/hertzbeat) - 具有自定义监控和无代理功能的开源实时监控系统.  
- [InfluxDB, cAdvisor, Grafana](https://github.com/vegasbrianc/docker-monitoring) - InfluxDB 时间序列数据库与 Grafana 和 cAdvisor 结合 [@vegasbrianc][vegasbrianc]
- [LogJam](https://github.com/gocardless/logjam) - Logjam 是一个日志转发器，旨在侦听本地端口，通过 UDP 接收日志条目，并将这些消息转发到日志收集服务器（例如 logstash） [@gocardless](https://github.com/gocardless)
- [Logspout](https://github.com/gliderlabs/logspout) - Docker 容器日志的日志路由 [@gliderlabs][gliderlabs]
- [monit-docker](https://github.com/decryptus/monit-docker)  - 监控 docker 容器资源使用情况或状态，并执行 docker 命令或在容器内部.  [@decryptus][解密]
- [NexClipper](https://github.com/NexClipper/NexClipper) - NexClipper 是专门针对 Docker、Apache Mesos、Marathon、DC/OS、Mesosphere、Kubernetes 的容器监控和性能管理解决方案 [@Nexclipper](https://github.com/NexClipper)
- [Out-of-the-box Host/Container Monitoring/Logging/Alerting Stack](https://github.com/uschtwill/docker_monitoring_logging_alerting)  - 开箱即用的 Docker 主机和容器监控、日志记录和警报，使用 cAdvisor、Prometheus、Grafana 进行监控，使用 Elasticsearch、Kibana 和 Logstash 进行日志记录，使用 elastalert 和 Alertmanager 进行警报.  5 分钟内完成设置. 用于生产的安全模式，内置 [Automated Nginx Reverse Proxy (jwilder&#39;s)][nginxproxy].
- [Sidekick](https://github.com/runsidekick/sidekick)  - 用于后端的开源实时应用程序调试器，如 Chrome DevTools. 收集跟踪并按需生成日志，而无需停止和重新部署您的应用程序.
- [SuperVisor CPM](https://t0xic0der.medium.com/simply-accessible-container-performance-monitoring-with-supervisor-7fb47f925f3b) [Frontend Service](https://github.com/t0xic0der/supervisor-frontend-service/) 和 [Driver Service](https://github.com/t0xic0der/supervisor-driver-service/) :construction: - A simple 和 accessible FOSS container performance monitoring service written in Python by [@t0xic0der](https://github.com/t0xic0der/)
- [SwarmAlert](https://github.com/gpulido/SwarmAlert) - 监控 Docker Swarm 并在发现没有运行健康服务任务的容器时发送 Pushover 警报.
- [Zabbix Docker module](https://github.com/monitoringartist/Zabbix-Docker-Monitoring)  - Zabbix 模块，提供正在运行的容器、CPU/内存/blk IO/网络容器指标的发现. 还支持 Systemd Docker 和 LXC 执行驱动程序. 它是一个动态链接的共享对象库，因此它的性能比任何脚本解决方案都要好 (~10x).
- [Zabbix Docker](https://github.com/gomex/docker-zabbix) - 使用 zabbix LLD 功能自动监控容器.

### Networking

- [Calico][calico] - Calico 是一个纯第 3 层虚拟网络，它允许多个 docker 主机上的容器相互通信.
-   [Flannel](https://github.com/coreos/flannel/)  - Flannel 是一个虚拟网络，它为每个主机提供一个子网以用于容器运行时. 通过 [@coreos][coreos]
-   [Freeflow](https://github.com/Microsoft/Freeflow)  - Linux 上的高性能容器覆盖网络. 启用 RDMA（在 InfiniBand 和 RoCE 上）并加速 TCP 到裸机的性能. 经过 [@Microsoft](https://github.com/Microsoft)
-   [netshoot](https://github.com/nicolaka/netshoot) - netshoot 容器具有一组强大的网络工具，可通过以下方式帮助解决 Docker 网络问题 [@nicolaka](https://github.com/nicolaka)
-   [Pipework](https://github.com/jpetazzo/pipework)  - 用于 Linux 容器的软件定义网络，Pipework 可与“普通”LXC 容器以及出色的 Docker 一起使用. 通过 [@jpetazzo][jpetazzo]
- [Weave][weave]（Docker 网络）- Weave 创建一个虚拟网络，连接部署在多个主机上的 Docker 容器.

### Orchestration

-   [athena](https://github.com/athena-oss/athena) - 具有插件架构的自动化平台，可让您轻松创建和共享服务.
-   [blimp](https://github.com/tubes和lube/blimp) :skull: - 使用 Docker Machine 轻松地将容器从一个 Docker 主机移动到另一个 Docker 主机，显示针对所有主机运行的容器，跨多个主机复制容器等等 [@defermat](https://github.com/defermat) 和 [@schvin](https://github.com/schvin)
-   [CloudSlang](https://github.com/CloudSlang/cloud-slang) - CloudSlang 是创建 Docker 流程​​自动化的工作流引擎
-   [clusterdock](https://github.com/clusterdock/clusterdock) - Docker 容器编排以启用对长时间运行的集群部署的测试
-   [Crane](https://github.com/Dataman-Cloud/crane) - 基于docker内置swarm的控制平面 [@Dataman-Cloud](https://github.com/Dataman-Cloud)
-   [Docker Flow Swarm Listener](https://github.com/docker-flow/docker-flow-swarm-listener)  - Docker Flow Swarm Listener 项目用于监听 Docker Swarm 事件并在发生变化时发送请求. 通过 [@docker-flow][docker-flow]
-   [docker rollout](https://github.com/Wowu/docker-rollout) - Docker Compose 服务的零停机部署 [@Wowu](https://github.com/Wowu)
-   [gantryd](https://github.com/DevTable/gantryd) :skull: - 一个框架，用于跨机器轻松管理基于 docker 的组件 [@DevTable](https://github.com/DevTable)
-   [Haven](https://github.com/codeabovelab/haven-platform)  - Haven 是一个集容器、应用、集群、镜像、注册管理于一体的简化容器管理平台. 经过 [@codeabovelab](https://github.com/codeabovelab)
-   [Helios](https://github.com/spotify/helios) :skull: - 一个简单的平台，用于在整个服务器群中部署和管理容器 [@spotify][spotify]
-   [Kontena](https://github.com/kontena/kontena)  :skull: - 开发人员友好的容器和微服务平台. 适用于任何云，易于设置，易于使用.
-   [Kubernetes](https://github.com/kubernetes/kubernetes) - Google 的 Docker 容器开源编排系统
-   [ManageIQ](https://github.com/ManageIQ/manageiq)  - 发现、优化和控制您的混合 IT. 经过 [ManageIQ](https://github.com/ManageIQ)
-   [Mantl](https://github.com/mantl/mantl) - Mantl 是一个用于快速部署全球分布式服务的现代平台
-   [Marathon](https://github.com/mesosphere/marathon)  - Marathon 是一个基于 Mesos 构建的私有 PaaS. 它会自动处理硬件或软件故障并确保应用程序“始终在线”
-   [Mesos](https://github.com/apache/mesos) - 容器、虚拟机和物理主机的资源/作业调度程序 [@apache](https://mesos.apache.org/)
-   [Nebula](https://github.com/nebula-orchestrator) - 旨在管理大规模分布式集群的 Docker 编排工具.
-   [Nomad](https://github.com/hashicorp/nomad)  - 轻松部署任何规模的应用程序. 一个分布式的、高可用的、数据中心感知的调度器 [@hashicorp](https://github.com/hashicorp)
-   [Panamax](https://github.com/CenturyLinkLabs/panamax-ui) :skull: - 一个开源项目，使部署复杂的容器化应用程序像 [@CenturyLinkLabs][centurylinklabs] 的拖放一样简单.
-   [Rancher](https://github.com/rancher/rancher) - 一个开源项目，由 [@rancher][rancher] 提供用于在生产中运行 Docker 的完整平台.
-   [RedHerd Framework](https://github.com/redherd-project/redherd-framework)  - RedHerd 是一个协作和无服务器框架，用于协调地理分布的资产组，能够模拟复杂的进攻性网络空间操作. 经过 [@RedHerdProject](https://github.com/redherd-project).
-   [Swarm-cronjob](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max/swarm-cronjob) - 在 Swarm 上按基于时间的时间表创建工作 [@https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max](https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max)

### PaaS

-   [Atlantis](https://github.com/ooyala/atlantis) ：skull： - Atlantis 是一个开源 PaaS，用于基于 Docker 构建并用 Go 编写的 HTTP 应用程序
-   [caprover](https://github.com/caprover/caprover) - [以前称为 CaptainDuckDuck] 自动化可扩展网络服务器包（自动化 Docker+nginx）- Heroku on Steroids
-   [Convox Rack](https://github.com/convox/rack) - Convox Rack 是建立在专家基础设施自动化和 devops 最佳实践之上的开源 PaaS.
-   [Dcw](https://github.com/pbertera/dcw) - Docker-compose SSH wrapper：一个非常可怜的 PaaS，公开容器标签中定义的 docker-compose 和 custom-container 命令.
-   [Dokku](https://github.com/dokku/dokku) - Docker 驱动的 mini-Heroku，可帮助您构建和管理应用程序的生命周期（最初来自 [@progrium][progrium]）
-   [Empire](https://github.com/remind101/empire) - 构建在 Amazon EC2 容器服务 (ECS) 之上的 PaaS
-   [Exoframe](https://github.com/exoframejs/exoframe) - 一种自托管工具，允许使用 Docker 进行简单的单命令部署
-   [Flynn](https://github.com/flynn/flynn) :skull: - 下一代开源平台即服务
-   [Hephy Workflow](https://github.com/teamhephy/workflow)  - Kubernetes 的开源 PaaS，它向任何 Kubernetes 集群添加了一个开发人员友好的层，使部署和管理应用程序变得容易. 的叉子 [Deis Workflow](https://github.com/deis/workflow)
-   [Krane](https://github.com/krane/krane) - 用于管理远程服务器上的容器工作负载的工具集
-   [Nanobox](https://github.com/nanobox-io/nanobox) ：heavy_dollar_sign：- 一个应用程序开发平台，可创建本地环境，然后可以在云中部署和扩展.
- [OpenShift][openshift] - 基于 [Kubernetes][kubernetes] 构建的开源 PaaS，并针对 Dockerized 应用程序开发和部署进行了优化 [Red Hat](https://www.redhat.com/en)
-   [Tsuru](https://github.com/tsuru/tsuru) - Tsuru 是一个可扩展的开源平台即服务软件

### Reverse Proxy

-   [bunkerized-nginx](https://github.com/bunkerity/bunkerized-nginx)  - 默认情况下安全的 Web 应用程序托管和反向代理. 经过 [@bunkerity](https://github.com/bunkerity)
-   [Docker Dnsmasq Updater](https://github.com/moonbuggy/docker-dnsmasq-updater) - 使用 Docker 容器主机名更新远程 dnsmasq 服务器.
-   [docker-flow-proxy](https://github.com/docker-flow/docker-flow-proxy)  - 每次部署新服务或扩展服务时重新配置代理. 通过 [@docker-flow][docker-flow]
-   [docker-proxy](https://github.com/silarsis/docker-proxy)  ：skull： - docker 容器的透明代理，在 docker 容器中运行. 经过 [@silarsis](https://github.com/silarsis)
-   [fabio](https://github.com/fabiolb/fabio)  - 一种快速、现代、零配置的负载平衡 HTTP(S) 路由器，用于部署由 consul 管理的微服务. 经过 [@magiconair](https://github.com/magiconair) （弗兰克施罗德）
-   [h2o-proxy](https://github.com/zchee/h2o-proxy)  ：skull：- Docker 容器的自动 H2O 反向代理.  [jwilder/nginx-proxy][nginxproxy] 的替代方法 [@zchee](https://github.com/zchee)
-   [Let's Encrypt Nginx-proxy Companion](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion)  - 用于 nginx-proxy 的轻量级配套容器. 它允许自动创建/更新 Let&#39;s Encrypt 证书. 经过 [@JrCs](https://github.com/JrCs)
-   [muguet](https://github.com/mattallty/muguet)  ：skull： - Docker 环境的 DNS 服务器和反向代理. 经过 [@mattallty](https://github.com/mattallty)
-   [Nginx Proxy Manager](https://github.com/jc21/nginx-proxy-manager)  - 一个漂亮的 web 界面，用于使用 SSL 代理基于 web 的服务. 经过 [@jc21](https://github.com/jc21)
- [nginx-proxy][nginxproxy] - [@jwilder][jwilder] 使用 docker-gen 为 Docker 容器自动代理 nginx
-   [Swarm Ingress Router](https://github.com/tpbowden/swarm-ingress-router)  :skull: - 根据标签将 DNS 名称路由到 Swarm 服务. 经过 [@tpbowden](https://github.com/tpbowden/)
-   [Swarm Router](https://github.com/flavioaiello/swarm-router)  - 基于“零配置”服务名称的路由器，用于 docker swarm 模式，采用全新且更安全的方法. 经过 [@flavioaiello](https://github.com/flavioaiello)
-   [Træfɪk](https://github.com/containous/traefik) - Docker、Mesos、Consul、Etcd 的自动反向代理和负载均衡器... [@EmileVauge](https://github.com/emilevauge)

### Runtime

-   [aind](https://github.com/aind-containers/aind) - AinD 通过在 Docker 中嵌套 Anbox 容器在 Docker 中启动 Android 应用程序 [@aind-containers](https://github.com/aind-containers)
-   [cri-o](https://github.com/cri-o/cri-o) - 基于 Open Container Initiative 的 Kubernetes 容器运行时接口实现 [cri-o](https://github.com/cri-o)
-   [lxc](https://github.com/lxc/lxc) - LXC - Linux 容器
-   [podman](https://github.com/containers/libpod)  - libpod 是用于创建容器 pod 的库.  [@containers][containers] 的 Podman 之家
-   [rlxc](https://github.com/brauner/rlxc) - 用 Rust 编写的 LXC 二进制文件 [@brauner](https://github.com/brauner)
-   [runtime-tools](https://github.com/opencontainers/runtime-tools) - oci-runtime-tool 是一组用于处理 OCI 运行时规范的工具 [@opencontainers](https://github.com/opencontainers)

### Security

-   [Anchor Engine](https://github.com/anchore/anchore) - 分析 CVE 漏洞和自定义安全策略的图像 [@Anchor](https://github.com/anchore)
-   [Aqua Security](https://www.aquasec.com) ：heavy_dollar_sign：- 在任何平台上保护基于容器的应用程序从开发到生产
-   [bane](https://github.com/genuinetools/bane) - [@genuinetools][genuinetools] 的 Docker 容器 AppArmor 配置文件生成器
-   [CetusGuard](https://github.com/hectorm/cetusguard) - CetusGuard 是一种通过过滤对其 API 端点的调用来保护 Docker 守护程序套接字的工具
-   [CIS Docker Benchmark](https://github.com/dev-sec/cis-docker-benchmark)  - 此 [InSpec][inspec] 合规配置文件以自动化方式实施 CIS Docker 1.12.0 基准测试，以在生产环境中提供围绕 Docker 守护程序和容器的安全最佳实践测试. 经过 [@dev-sec](https://github.com/dev-sec)
-   [Checkov](https://github.com/bridgecrewio/checkov)  - 基础设施作为代码清单（Terraform、Kubernetes、Cloudformation、Helm、Dockerfile、Kustomize）的静态分析发现安全错误配置并修复它们. 经过 [@bridgecrew](https://github.com/bridgecrewio)
-   [Clair](https://github.com/quay/clair)  - Clair 是一个开源项目，用于对 appc 和 docker 容器中的漏洞进行静态分析. 通过 [@coreos][coreos]
-   [Dagda](https://github.com/eliasgranderubio/dagda)  - Dagda 是一种工具，用于对 docker 镜像/容器中的已知漏洞、木马、病毒、恶意软件和其他恶意威胁进行静态分析，并监控 docker 守护进程和运行的 docker 容器以检测异常活动. 经过 [@eliasgranderubio](https://github.com/eliasgranderubio)
-   [Deepfence Enterprise](https://https://github.com/veggiemonk/awesome-docker/blob/master/deepfence.io)  ：heavy_dollar_sign：- 用于 kubernetes、虚拟机和无服务器的完整生命周期云原生工作负载保护平台. 经过 [@https://github.com/veggiemonk/awesome-docker/blob/master/deepfence](https://github.com/veggiemonk/awesome-docker/blob/master/deepfence)
-   [Deepfence Threat Mapper](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/deepfence/ThreatMapper)  - 适用于 kubernetes、虚拟机和无服务器的强大运行时漏洞扫描器. 经过 [@https://github.com/veggiemonk/awesome-docker/blob/master/deepfence](https://github.com/veggiemonk/awesome-docker/blob/master/deepfence)
-   [docker-bench-security](https://github.com/docker/docker-bench-security)  - 检查有关在生产中部署 Docker 容器的数十种常见最佳实践的脚本. 通过 [@docker][docker]
-   [docker-explorer](https://github.com/google/docker-explorer) - [@Google][google] 帮助取证离线 docker 收购的工具
-   [docker-lock](https://github.com/safe-waters/docker-lock)  - 一个用于 docker 的 cli 插件，通过在单独的 Lockfile 中跟踪它们来自动管理图像摘要. 通过 [@safe-waters][safe-waters]
-   [KICS](https://github.com/checkmarx/kics)  - 基础设施即代码扫描工具，在开发周期的早期发现安全漏洞、合规性问题和基础设施配置错误. 可以延长额外的政策. 经过 [Checkmarx](https://github.com/Checkmarx)
-   [notary](https://github.com/theupdateframework/notary)  - 用于运行可信集合并与之交互的服务器和客户端. 经过 [@TUF](https://github.com/theupdateframework)
-   [oscap-docker](https://github.com/OpenSCAP/openscap)  - OpenSCAP 提供了用于扫描 Docker 容器和镜像的 oscap-docker 工具. 经过 [OpenSCAP](https://github.com/OpenSCAP)
-   [Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud) :heavy_dollar_sign: -（以前的 Twistlock 安全套件）检测漏洞，强化容器映像，并在应用程序的整个生命周期中实施安全策略.
-   [Sysdig Falco](https://github.com/falcosecurity/falco)  - Sysdig Falco 是一个开源容器安全监视器. 它可以监控应用程序、容器、主机和网络活动，并对未经授权的活动发出警报.
-   [Sysdig Secure](https://sysdig.com/use-cases/cloud-threat-detection-and-response/) ：heavy_dollar_sign：-Sysdig Secure 通过行为监控和防御解决运行时安全问题，并提供基于开源 Sysdig 的深度取证以进行事件响应.
-   [Trend Micro DeepSecurity](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/deep-security.html) :heavy_dollar_sign: - Trend Micro DeepSecurity 为容器工作负载和主机提供运行时保护，以及图像的运行前扫描以识别漏洞、恶意软件和硬编码秘密等内容.
-   [Trivy](https://github.com/aquasecurity/trivy) - Aqua Security 的开源简单而全面的容器漏洞扫描器（适用于 CI）.

### Service Discovery

-   [docker-consul](https://github.com/gliderlabs/docker-consul) 通过 [@progrium][progrium]
-   [etcd](https://github.com/etcd-io/etcd) - 分布式系统最关键数据的分布式可靠键值存储 [@etcd-io](https://github.com/etcd-io) （CoreOS 的前一部分）
-   [https://github.com/veggiemonk/awesome-docker/blob/master/istio](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/istio/https://github.com/veggiemonk/awesome-docker/blob/master/istio) - 一个连接、管理和保护微服务的开放平台 [@IstioMesh](https://github.com/veggiemonk/awesome-docker/blob/master/istio)
-   [proxy](https://github.com/factorish/proxy)  :skull: - 基于轻量级 nginx 的负载均衡器，使用注册商提供的服务发现. 经过 [@factorish](https://github.com/factorish)
-   [registrator](https://github.com/gliderlabs/registrator) - Service registry bridge for Docker by [@gliderlabs][gliderlabs] and [@progrium][progrium]

### Volume Management / Data

-   [Blockbridge](https://github.com/blockbridge/blockbridge-docker-volume)  :heavy_dollar_sign:- Blockbridge 插件是一个卷插件，它提供对一组可扩展的基于容器的持久存储选项的访问. 它支持单主机和多主机 Docker 环境，具有租户隔离、自动配置、加密、安全删除、快照和 QoS 等功能. 经过 [@blockbridge](https://github.com/blockbridge)
-   [Convoy](https://github.com/rancher/convoy)  :skull: - 一个开源 Docker 卷驱动程序，可以在任何地方快照、备份和恢复 Docker 卷. 通过 [@rancher][牧场主]
-   [Docker Machine NFS](https://github.com/adlogix/docker-machine-nfs) 为通过 OS X 上的 Docker Machine 创建的现有 boot2docker box 激活 NFS.
-   [Docker Unison](https://github.com/leighmcculloch/docker-unison) 使用 Unison 进行快速双向文件夹同步的 docker 卷容器. 创建为 OS X 上缓慢的 boot2docker 卷的替代方法. [@leighmcculloch](https://github.com/leighmcculloch)
-   [Docker Volume Backup](https://github.com/offen/docker-volume-backup) 在本地或任何 S3 兼容存储中备份 Docker 卷. 经过 [@offen](https://github.com/offen)
-   [Local Persist](https://github.com/MatchbookLab/local-persist) 为您的本地卷（通过 `docker volume create` 创建）指定一个挂载点，这样文件将始终存在，这样您就可以挂载到不同容器中的不同目录.
-   [Minio](https://github.com/minio/minio) - Docker 容器中的 S3 兼容对象存储服务器
-   [Netshare](https://github.com/ContainX/docker-volume-netshare)  Docker NFS、AWS EFS、Ceph 和 Samba/CIFS 卷插件. 通过 [@ContainX][containx]
-   [portworx](https://portworx.com) ：heavy_dollar_sign：- 用于持久、共享和复制卷的分散存储解决方案.
-   [quobyte](https://www.quobyte.com/) :heavy_dollar_sign: - 具有 docker 卷驱动程序的完全容错分布式文件系统
-   [REX-Ray](https://github.com/rexray/rexray) 提供与供应商无关的存储编排引擎. 主要设计目标是为 Docker、Kubernetes 和 Mesos 提供持久存储. 经过[@thecodeteam](https://github.com/thecodeteam) （戴尔科技）
-   [Storidge](https://github.com/Storidge/quick-start) ：heavy_dollar_sign：- 用于 Kubernetes 和 Docker Swarm 的软件定义持久存储

### User Interface

#### IDE integrations

- JetBrains IDE（IntelliJ IDEA、GoLand、WebStorm、CLion 等）具有 [built-in Docker plugin](https://www.jetbrains.com/help/idea/docker.html#managing-images)
- 日蚀 [Docker Tooling plugin](https://www.eclipse.org/community/eclipse_newsletter/2016/july/article2.php)
-   [docker.vim](https://github.com/skanehira/docker.vim)  - 在 Vim 中管理 docker 容器和图像. 通过 [@skanehira]
-   [docker.el](https://github.com/Silex/docker.el) 通过 Emacs 管理 docker [@Silex](https://github.com/Silex)

#### Desktop

用于管理和监控 docker 主机和集群的本地桌面应用程序

-   [Docker Desktop](https://www.docker.com/products/docker-desktop/)  - 官方原生应用. 仅适用于 Windows 和 MacOS
-   [Dockeron](https://github.com/dockeron/dockeron) - 一个基于 Electron + Vue.js 构建的项目，适用于桌面上的 Docker. [@fluency03](https://github.com/fluency03)
-   [DockStation](https://github.com/DockStation/dockstation) - 以开发人员为中心的 UI，用于配置、监控和管理服务和容器 [@dock_station](https://twitter.com/dock_station)
-   [Lifeboat](https://github.com/jplhomer/lifeboat) - 在 Mac 上使用图形界面启动 Docker 项目的简单方法. [@jplhomer](https://github.com/jplhomer)
-   [Simple Docker UI](https://github.com/felixgborrego/simple-docker-ui)  - 建立在电子之上. 经过 [@felixgborrego](https://github.com/felixgborrego/)
-   [Stevedore](https://github.com/slonopotamus/stevedore)  - 适用于 Windows 的良好 Docker 桌面替代品. 支持 Linux 和 Windows 容器. [@slonopotamus](https://github.com/slonopotamus)

#### Terminal

##### Terminal UI

-   [ctop (1)](https://github.com/yadutaf/ctop) - :skull: 一个基于命令行/文本的 Linux 容器监控工具，其工作方式与您预期的一样 (Python) [@yadutaf](https://github.com/yadutaf)
-   [ctop (2)](https://github.com/bcicen/ctop) - 容器指标（Golang）的顶级接口 [@bcicen](https://github.com/bcicen/)
-   [dive](https://github.com/wagoodman/dive)  - 用于探索 docker 图像中每一层的工具. 经过 [wagoodman](https://github.com/wagoodman).
-   [dockdash](https://github.com/byrnedo/dockdash) 详细的统计数据. 通过 [@byrnedo]
-   [Docker-mon](https://github.com/icecrime/docker-mon) ：头骨： - 基于控制台的 Docker 监控 [@icecrime](https://github.com/icecrime)
-   [dockly](https://github.com/lirantal/dockly) - 用于管理 Docker 容器的交互式 shell UI [@lirantal](https://github.com/lirantal)
-   [DockSTARTer](https://github.com/GhostWriters/DockSTARTer) - DockSTARter 帮助您开始使用在 Docker 中运行的家庭服务器应用程序 [GhostWriters](https://github.com/GhostWriters)
-   [docui](https://github.com/skanehira/docui)  - :skull: 用于管理 Docker 容器的交互式 shell UI. 也适用于 Windows. 通过 [@skanehira]
-   [dry](https://github.com/moncho/dry) - 用于 Docker 容器的交互式 CLI [@moncho](https://github.com/moncho)
-   [lazydocker](https://github.com/jesseduffield/lazydocker)  - 管理一切 docker 的更懒惰的方式.  docker 和 docker-compose 的简单终端 UI，使用 gocui 库用 Go 编写. 经过 [@jesseduffield](https://github.com/jesseduffield)
-   [sen](https://github.com/TomasTomecek/sen) - :skull: docker 引擎的终端用户界面，作者：[@TomasTomecek][tomastomecek]

##### CLI tools

-   [captain](https://github.com/jenssegers/captain)  - 从任何目录轻松启动和停止 docker compose 项目. 经过 [@jenssegers](https://github.com/jenssegers)
-   [dcinja](https://github.com/Falldog/dcinja)  - 用于 docker 命令行环境的模板引擎的强大和最小的二进制大小. 经过 [@Falldog](https://github.com/Falldog)
-   [dcp](https://github.com/exdx/dcp)  - 从容器文件系统复制文件的简单工具. 经过 [@exdx](https://github.com/exdx)
-   [docker-ls](https://github.com/mayflower/docker-ls) - 用于浏览和操作 docker 注册表的 CLI 工具 [@mayflower](https://github.com/mayflower)
-   [docker pushrm](https://github.com/christian-korneck/docker-pushrm) - A Docker CLI plugin that lets you push the README.md file from the current directory to Docker Hub. Also supports Quay and Harbor. By [@christian-korneck](https://github.com/christian-korneck)
-   [dockersql](https://github.com/crosbymichael/dockersql) - :skull: 使用 SQL 查询 Docker 的命令行界面 [@crosbymichael](https://github.com/crosbymichael)
-   [DVM](https://github.com/howtowhale/dvm) - Docker 版本管理器 [@howtowhale](https://github.com/howtowhale)
-   [goinside](https://github.com/iamsoorena/goinside)  - 轻松进入正在运行的 docker 容器. 经过 [@iamsoorena](https://github.com/iamsoorena)
-   [ns-enter](https://github.com/jpetazzo/nsenter) - :skull: 不再使用 ssh，通过 [@jpetazzo][jpetazzo] 输入容器的名称空间
-   [Pdocker](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/g31s/Pdocker) - 为个人项目管理和维护Docker的简单工具 [@https://github.com/veggiemonk/awesome-docker/blob/master/g31s](https://github.com/veggiemonk/awesome-docker/blob/master/g31s)
-   [proco](https://github.com/shiwaforce/poco)  - Proco 将帮助您使用简单的 YAML 配置文件组织和管理任何复杂的 Docker、Docker-Compose、Kubernetes 项目，以缩短从找到项目到在本地环境中初始化项目的路径. 经过 [@shiwaforce](https://github.com/shiwaforce)
-   [reg](https://github.com/genuinetools/reg) - :skull: [@genuinetools][genuinetools] 的 Docker registry v2 命令行客户端
-   [scuba](https://github.com/JonathonReinhart/scuba) - 透明地使用 Docker 容器来封装软件构建环境，通过 [@JonathonReinhart](https://github.com/JonathonReinhart)
-   [skopeo](https://github.com/containers/skopeo) - 与远程图像注册中心合作 - 通过 [@containers][containers] 检索信息、图像、签署内容
-   [supdock](https://github.com/segersniels/supdock)  - 允许通过交互式提示稍微更直观地使用 Docker. 经过 [@segersniels](https://github.com/segersniels)
-   [tsaotun](https://github.com/qazbnm456/tsaotun) - 基于 Python 的 Docker 帮助 [@qazbnm456](https://github.com/qazbnm456)
-   [wharfee](https://github.com/j-bennet/wharfee)  - :skull: Docker 命令的自动完成和语法突出显示. 经过 [@j-bennet](https://github.com/j-bennet)

##### Other

-   [dext-docker-registry-plugin](https://github.com/vutran/dext-docker-registry-plugin)  - 使用 Dext 智能启动器搜索 Docker Registry. 经过 [@vutran](https://github.com/vutran)
-   [docker-ssh](https://github.com/jeroenpeeters/docker-ssh)  - 用于 Docker 容器的 SSH 服务器 ~ 因为每个容器都应该可以访问. 经过 [@jeroenpeeters](https://github.com/jeroenpeeters)
-   [dockercraft](https://github.com/docker/dockercraft) - Docker + Minecraft = Dockercraft by [@docker][docker]
-   [dockerfile-mode](https://github.com/spotify/dockerfile-mode) [@spotify][spotify] 处理 Dockerfile 的 emacs 模式
-   [MultiDocker](https://github.com/marty90/multidocker) - 创建一个安全的多用户 Docker 机器，其中每个用户都被隔离到一个独立的容器中.
-   [Powerline-Docker](https://github.com/adrianmo/powerline-docker) - 用于显示 Docker 容器状态的电力线段 [@adrianmo](https://github.com/adrianmo)

#### Web

-   [Admiral](https://github.com/vmware/admiral)  Admiral™ 是一个高度可扩展且非常轻量级的容器管理平台，用于部署和管理基于容器的应用程序. 通过 [VMWare][vmware]
-   [CASA](https://github.com/knrdl/casa) - 将少数容器的管理外包给你的同事，通过 [@knrdl](https://github.com/knrdl)
-   [Container Web TTY](https://github.com/wrfly/container-web-tty) - Connect your containers via a web-tty [@wrfly](https://github.com/wrfly)
-   [Docker Compose UI](https://github.com/francescou/docker-compose-ui)  - 通过 HTTP 管理 docker-compose.  docker-compose-ui 在 Docker 容器中运行，安装主机 docker 套接字并公开 RESTful API 和 AngularJS GUI
-   [Docker Registry Browser](https://github.com/klausmeyer/docker-registry-browser) - Docker Registry HTTP API v2 的 Web 界面，作者： [@klausmeyer](https://github.com/klausmeyer)
-   [Docker Registry UI (Joxit)](https://github.com/Joxit/docker-registry-ui) - 私有注册表最简单、最干净的用户界面 [@Joxit](https://github.com/Joxit)
-   [Docker Registry UI](https://github.com/atcol/docker-registry-ui) - 一个用于简单私有/本地 Docker Registry 集成的 Web UI [@atcol](https://github.com/atcol)
-   [docker-registry-web](https://github.com/mkuchin/docker-registry-web) - 私有 docker registry v2 的 Web UI、身份验证服务和事件记录器 [@mkuchin](https://github.com/mkuchin)
-   [docker-swarm-visualizer](https://github.com/dockersamples/docker-swarm-visualizer) - 在 Docker Swarm 上可视化 Docker 服务（用于运行演示）.
-   [dockering-on-rails](https://github.com/Electrofenster/dockerding-on-rails) :skull: - 具有许多功能的 Docker 简单 Web 界面 by [@Electrofenster](https://github.com/Electrofenster/)
-   [DockerSurfer](https://github.com/Simone-Erba/DockerSurfer) ：skull： - 用于分析和浏览 Docker 注册表中 Docker 图像之间依赖关系的 Web 服务，通过 [@Simone-Erba](https://github.com/Simone-Erba/)
-   [Kubevious](https://github.com/kubevious/kubevious) - 一个高度可视化的 Kubernetes 网络用户界面，以应用程序为中心的方式呈现配置和状态 [@rubenhak](https://github.com/rubenhak).
-   [netdata](https://github.com/netdata/netdata) - 实时性能监控
-   [OctoLinker](https://github.com/OctoLinker/OctoLinker) - GitHub 的浏览器扩展，使 `Dockerfile` 中的图像名称可点击并将您重定向到相关的 Docker Hub 页面.
-   [Portainer](https://github.com/portainer/portainer) - 用于管理 Docker 主机或 Docker Swarm 集群的轻量级管理 UI [@portainer](https://github.com/portainer)
-   [Rapid Dashboard](https://github.com/ozlerhakan/rapid) - 一个使用 Docker Remote API 的简单查询仪表板 [@ozlerhakan](https://github.com/ozlerhakan/)
-   [Seagull](https://github.com/tobegit3hub/seagull)  - 用于监控 docker 守护进程的友好 Web UI. 经过 [@tobegit3hub](https://github.com/tobegit3hub)
-   [Swarmpit](https://github.com/swarmpit/swarmpit)  - Swarmpit 为您的 Docker Swarm 集群提供简单易用的界面. 您可以管理您的堆栈、服务、机密、卷、网络等.
-   [Swirl](https://github.com/cuigh/swirl) - Swirl 是 Docker 的 web 管理工具，专注于 swarm 集群 [@cuigh](https://github.com/cuigh/)
-   [Theia](https://github.com/eclipse-theia/theia) - 可扩展平台，用于使用最先进的网络技术开发成熟的多语言云和桌面 IDE 类产品.
-   [Yacht](https://github.com/SelfhostedPro/Yacht)  :construction: - 一个用于 docker 的 Web UI，专注于模板和易用性，以使部署尽可能简单. 经过 [@SelfhostedPro](https://github.com/SelfhostedPro)

## Docker Images

### Base Tools

安装在容器内或设计为作为容器运行的工具和应用程序 [sidecar](https://learn.microsoft.com/en-us/azure/architecture/patterns/sidecar)

-   [amicontained](https://github.com/genuinetools/amicontained)  - 容器内省工具. 找出正在使用的容器运行时以及 [@genuinetools][genuinetools] 提供的功能
-   [autodock](https://github.com/prologic/autodock) - 用于 Docker 自动化的守护进程 [@prologic](https://github.com/prologic)
-   [Chaperone](https://github.com/garywiz/chaperone)  - 为 docker 容器设计的单个 PID1 进程. 用户管理、日志管理、启动、僵尸收割，都在一个小包里. 经过 [@garywiz](https://github.com/garywiz)
-   [ckron](https://github.com/nicomt/ckron) - 用于 docker 的 cron 风格的作业调度程序，由 [@nicomt](https://github.com/nicomt)
- [CoreOS][coreos] - 用于大规模服务器部署的 Linux
-   [distroless](https://github.com/GoogleContainerTools/distroless) - 以语言为中心的 docker 图像，减去操作系统，来自 [@GoogleContainerTools][googlecontainertools]
-   [docker-alpine](https://github.com/gliderlabs/docker-alpine) - [@gliderlabs][gliderlabs] 使用 Alpine Linux 的超小型 Docker 基础映像 _(5MB)_
-   [docker-gen](https://github.com/jwilder/docker-gen) - 通过 [@jwilder][jwilder] 从 docker 容器元数据生成文件
-   [dockerize](https://github.com/powerman/dockerize) - [@jwilder][jwilder]、[@powerman][powerman] 简化在 docker 容器中运行应用程序的实用程序
-   [GoSu](https://github.com/tianon/gosu) - 以该特定用户身份运行该特定应用程序并通过以下方式退出管道（入口点脚本工具） [@tianon](https://github.com/tianon)
-   [is-docker](https://github.com/sindresorhus/is-docker) - 通过 [@sindresorhus][sindresorhus] 检查进程是否在 Docker 容器内运行
-   [lstags](https://github.com/ivanilves/lstags) - 跨注册表同步 Docker 镜像 [@ivanilves](https://github.com/ivanilves)
-   [NVIDIA-Docker](https://github.com/NVIDIA/nvidia-docker) - [@NVIDIA][nvidia] 的 Docker NVIDIA 容器运行时
-   [su-exec](https://github.com/ncopa/su-exec)  - 这是一个简单的工具，可以简单地执行具有不同权限的程序. 该程序将直接执行，而不是像 su 和 sudo 那样作为子程序运行，从而避免了 TTY 和信号问题. 为什么要重塑 gosu？ 这或多或少与 gosu 完全相同，但它只有 10kb 而不是 1.8MB. 经过 [ncopa](https://github.com/ncopa)
-   [sue](https://github.com/theAkito/sue)  - 以与运行 sue 的用户不同的用户身份执行程序. 这是 ncopa/su-exec 的可维护替代品，后者是更好的 tianon/gosu. 这个比原来的 gosu 好得多（性能更高，体积更小），但是它比用普通 C 编写的 su-exec 更容易维护.由 [Akito][akito] 制作
-   [supercronic](https://github.com/aptible/supercronic) - 与 crontab 兼容的作业运行器，专为在容器中运行而设计 [@aptible](https://github.com/aptible/)
-   [TrivialRC](https://github.com/vorakl/TrivialRC) - 容器的简约运行时配置系统和进程管理器 [@vorakl](https://github.com/vorakl)

### Builder

旨在帮助或简化构建**新**图像的应用程序

-   [ansible-bender](https://github.com/ansible-community/ansible-bender) - [@TomasTomecek][tomastomecek] 使用 `ansible` 和 `buildah` 的工具
-   [buildah](https://github.com/containers/buildah) - 通过 [@containers][containers] 促进构建 OCI 图像的工具
-   [BuildKit](https://github.com/moby/buildkit) - 并发、高速缓存高效且与 Dockerfile 无关的构建器工具包，作者： [@moby project](https://github.com/moby)
-   [cekit](https://github.com/cekit/cekit) - openshift 使用不同的构建引擎构建基础镜像的工具 [@cekit](https://github.com/cekit).
-   [container-diff](https://github.com/GoogleContainerTools/container-diff) - [@GoogleContainerTools][googlecontainertools] 用于比较和分析容器图像的图像工具
-   [container-factory](https://github.com/mutable/container-factory) - 从应用程序源代码的压缩包中生成 Docker 镜像 [@mutable](https://github.com/mutable)
-   [copy-docker-image](https://github.com/mdlavin/copy-docker-image) - 在没有完整 Docker 安装的情况下在注册表之间复制 Docker 映像 [@mdlavin](https://github.com/mdlavin)
-   [Derrick](https://github.com/alibaba/derrick)  - 一个工具可以帮助您通过扫描代码自动生成 Dockerfile 和 dockerize 应用程序. 经过 [@alibaba](https://github.com/alibaba).
-   [dlayer](https://github.com/orisano/dlayer) - docker层分析器 [@orisano](https://github.com/orisano)
-   [docker-companion](https://github.com/mudler/docker-companion) - 用 Golang 编写的命令行工具，用于压缩和解压 docker 图像 [@mudler](https://github.com/mudler/)
-   [docker-make](https://github.com/CtripCloud/docker-make) - 通过单个命令构建、标记和推送一堆相关的 docker 图像.
-   [docker-replay](https://github.com/bcicen/docker-replay)  - 从正在运行的容器生成`docker run`命令和选项. 经过 [bcicen](https://github.com/bcicen)
-   [DockerMake](https://github.com/avirshup/DockerMake)  - 用于复杂软件堆栈的可重现 Docker 映像构建系统. 经过 [@avirshup](https://github.com/avirshup)
-   [DockerSlim](https://github.com/docker-slim/docker-slim) 缩小胖 Docker 图像，创建尽可能小的图像.
-   [Dockly](https://github.com/swipely/dockly) - Dockly 是一个 gem，旨在减轻在 Docker 中打包应用程序的痛苦 [@swipely](https://github.com/swipely/)
-   [dockramp](https://github.com/jlhawn/dockramp) :skull: - 概念证明：客户端驱动的 Docker 镜像生成器 [@jlhawn](https://github.com/jlhawn)
-   [essex](https://github.com/utensils/essex) - 基于 Docker 的项目的样板：Essex 是一个用 bash 编写的 CLI 实用程序，用于使用 Makefile 驱动的工作流快速设置干净且一致的 Docker 项目. [@jamesbrink](https://github.com/jamesbrink)
-   [HPC Container Maker](https://github.com/NVIDIA/hpc-container-maker) - 从高级 Python 配方生成 Dockerfile，包括 [@NVIDIA][nvidia] 的高性能计算组件构建块
-   [img](https://github.com/genuinetools/img) - [@genuinetools][genuinetools] 的独立、无守护程序、非特权 Dockerfile 和 OCI 兼容容器映像生成器
-   [kaniko](https://github.com/GoogleContainerTools/kaniko)  - 在 Kubernetes 中构建容器镜像. 通过 [@GoogleContainerTools][googlecontainertools]
-   [makisu](https://github.com/uber/makisu)  - Uber 用于 Mesos 和 Kubernetes 的快速灵活的非特权图像生成器，具有分布式缓存支持. 经过 [@uber](https://github.com/uber)
-   [packer](https://developer.hashicorp.com/packer/plugins/builders/docker) - 用于构建机器映像的 Hashicorp 工具，包括与 chef、puppet、ansible 等配置管理工具集成的 docker 映像
-   [portainer](https://github.com/duedil-ltd/portainer) - 用于构建 Docker 镜像的 Apache Mesos 框架 [@duedil-ltd](https://github.com/duedil-ltd)
-   [Production-Ready Python Containers :heavy_dollar_sign:](https://pythonspeed.com/products/pythoncontainer/) - 用于为 Python 应用程序创建生产就绪 Docker 映像的模板.
-   [RAUDI](https://github.com/cybersecsi/RAUDI)  - 一种工具，可在有新版本/更新/提交时自动更新（并可选择推送到 Docker Hub）用于第 3 方软件的 Docker 图像. 经过 [@SecSI](https://github.com/cybersecsi)
-   [runlike](https://github.com/lavie/runlike) - 通过运行容器生成`docker run`命令和选项 [@lavie](https://github.com/lavie)
-   [SkinnyWhale](https://github.com/djosephsen/skinnywhale) :skull: -Skinnywhale 帮助您制作更小的（以兆字节为单位）Docker 容器.
-   [Smith](https://github.com/oracle/smith) - 一个 Micocontainer Builder，可以在镜像构建后执行多阶段构建 [Oracle][oracle]
-   [userdef](https://github.com/theAkito/userdef)  - 用于基于 Alpine 的 Docker 映像的高级“adduser”.  [Akito][akito]制作
-   [Whaler](https://github.com/P3GLEG/Whaler) - 将 Docker 镜像反转为 Dockerfiles 的程序 [@P3GLEG](https://github.com/P3GLEG/).
-   [Whales](https://github.com/Gueils/whales) - 一个自动对接你的应用程序的工具 [@icalialabs](https://github.com/IcaliaLabs).

### Dockerfile

-   [chaperone-docker](https://github.com/garywiz/chaperone-docker) - 一组使用 Chaperone 流程管理器的图像，包括精益 Alpine 图像、LAMP、LEMP 和基本的基础套件.
-   [Dockerfile Generator](https://github.com/ozankasikci/dockerfile-generator) `dfg` 既是一个 Go 库，也是一个使用各种输入通道生成有效 Dockerfile 的可执行文件.
-   [Dockerfile Project](https://dockerfile.github.io/)  - 可信的自动化 Docker 构建.  Dockerfile 项目为可在 Docker 容器上运行的各种流行的开源软件服务维护 Dockerfile 的中央存储库.
-   [dockerfilegraph](https://github.com/patrickhoefler/dockerfilegraph)  - 可视化您的多阶段 Dockerfile. 经过 [@PatrickHoefler](https://github.com/patrickhoefler)
-   [Dockershelf](https://github.com/Dockershelf/dockershelf)  - 一个存储库，用作通用、高效和苗条的 docker 食谱的收集器. 图像通过 Travis cron 作业每天更新、测试和发布. 维护者 [@CollageLabs](https://github.com/CollageLabs).
-   [dockmoor](https://github.com/MeneDev/dockmoor)  ：构造： - 管理 docker 图像引用并帮助使用 Docker 创建可重现的构建. 经过 [@MeneDev](https://github.com/MeneDev)
-   [Vektorcloud](https://github.com/vektorcloud) - 一组最小的、基于 Alpine 的 Docker 图像

示例：

-   [@arun-gupta](https://github.com/arun-gupta/docker-images)
-   [@awesome-startup](https://github.com/awesome-startup/docker-compose)
-   [@crosbymichael](https://github.com/crosbymichael/Dockerfiles)
-   [@jessfraz](https://github.com/jessfraz/dockerfiles)
-   [@komljen](https://github.com/komljen/dockerfile-examples)
-   [@kstaken](https://github.com/kstaken/dockerfile-examples)
-   [@ondrejmo](https://github.com/ondrejmo/Dockerfiles)
-   [@pandrew](https://gitlab.com/pandrew/dockerfiles)
-   [@vimagick](https://github.com/vimagick/dockerfiles)

### Linter

-   [docker-image-size-limit](https://github.com/wemake-services/docker-image-size-limit) - 一个关注你的 docker 镜像大小的工具.
-   [Dockerfile Linter action](https://github.com/buddy-works/dockerfile-linter) - linter 可让您验证 Dockerfile 语法，以确保它遵循构建高效 Docker 映像的最佳实践.
-   [dockfmt](https://github.com/jessfraz/dockfmt) :construction: - [@jessfraz][jessfraz] 的 Dockerfile 格式化程序和解析器
-   [FROM:latest](https://github.com/replicatedhq/dockerfilelint) - 一个自以为是的 Dockerfile linter [@replicatedhq](https://github.com/replicatedhq)
-   [Hadolint](https://github.com/hadolint/hadolint)  - 一个 Dockerfile linter，用于检查最佳实践、常见错误，还能够对任何用“RUN”指令编写的 bash 进行 lint； 经过 [@lukasmartinelli](https://github.com/lukasmartinelli)
-   [Whale-linter](https://github.com/jeromepin/whale-linter) - 一个简单而小巧的 Dockerfile linter，用 Python3+ 编写，没有依赖性 [@jeromepin](https://github.com/jeromepin)

### Metadata

-   [opencontainer](https://github.com/opencontainers/image-spec/blob/master/annotations.md) - 由 OCI Image Spec 定义的 Docker 标签的约定和共享命名空间.

### Registry

用于安全存储 Docker 映像的服务.

-   [Amazon Elastic Container Registry :heavy_dollar_sign:](https://aws.amazon.com/ecr/) - Amazon Elastic Container Registry (ECR) 是一个完全托管的 Docker 容器注册表，使开发人员可以轻松存储、管理和部署 Docker 容器映像.
-   [Azure Container Registry :heavy_dollar_sign:](https://azure.microsoft.com/en-us/products/container-registry/#overview) - 将 Docker 私有注册表作为一流的 Azure 资源进行管理
-   [CargoOS](https://github.com/RedCoolBeans/cargos-buildroot)  - 用于在裸机或云上运行 Docker 引擎的基本操作系统. 经过 [@RedCoolBeans](https://github.com/RedCoolBeans)
-   [cleanreg](https://github.com/hcguersoy/cleanreg) - 一个小工具，用于从实现 API v2 的 Docker Registry 中删除图像清单，通过以下方式为 GC 取消引用它们 [@hcguersoy](https://github.com/hcguersoy)
-   [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.com/docker-registry/)  - 完全托管的包管理 SaaS，对公共和私有 Docker 注册表（以及许多其他注册表，包括 Kubernetes 生态系统的 Helm 图表）提供一流的支持. 有一个慷慨的免费层，也是完全免费的开源.
-   [Container Registry Service :heavy_dollar_sign:](https://container-registry.com/)  - 基于港口的容器管理解决方案作为团队和组织的服务. 免费层为私有存储库提供 1 GB 存储空间.
-   [Cycle.io :heavy_dollar_sign:](https://cycle.io/) - 裸机容器托管.
-   [DigitalOcean :heavy_dollar_sign:](https://www.digitalocean.com/products/container-registry) - DigitalOcean 容器注册表.
-   [Docker Hub](https://hub.docker.com/) 由 Docker Inc. 提供
- [Docker Registry v2][distribution] - 用于打包、运送、存储和交付内容的 Docker 工具集
-   [Docket](https://github.com/netvarun/docket) - 允许通过 bittorrent 进行闪电般快速部署的自定义 docker 注册表 [@netvarun](https://github.com/netvarun/)
-   [Dragonfly](https://github.com/dragonflyoss/Dragonfly2) - 基于p2p技术提供高效、稳定、安全的文件分发和图片加速.
-   [GCE Container Registry :heavy_dollar_sign:](https://cloud.google.com/container-registry/) Google Cloud Platform 上快速、私有的 Docker 镜像存储
-   [GitLab Container Registry](https://docs.gitlab.com/ee/user/packages/container_registry/) - Registry 专注于在 GitLab CI 中使用其图像
-   [Harbor](https://github.com/goharbor/harbor) 一个开源的可信云原生注册表项目，用于存储、签名和扫描内容. 支持复制、用户管理、访问控制和活动审计. 经过 [CNCF](https://github.com/veggiemonk/awesome-docker/blob/master/Sandbox) 以前是 [VMWare][vmware]
-   [JFrog Artifactory :heavy_dollar_sign:](https://jfrog.com/artifactory/) - Artifact Repository Manager，也可以用作私有 Docker Registry
-   [Kraken](https://github.com/uber/kraken) - Uber 的高度可扩展的 P2P docker 注册表，能够在几秒钟内分发 TB 的数据.
-   [Portus](https://github.com/SUSE/Portus) - Docker 注册表（v2）的授权服务和前端 [@SUSE](https://github.com/SUSE)
-   [Quay.io :heavy_dollar_sign:](https://quay.io/) （CoreOS 的一部分）- 私有 Docker 存储库的安全托管
-   [Registryo](https://github.com/inmagik/registryo) - 用于本地 docker 注册表的基于 UI 和令牌的身份验证服务器
-   [Rescoyl](https://github.com/noteed/rescoyl) - 私有 Docker 注册表（免费和开源） [@noteed](https://github.com/noteed)
-   [Sonatype Nexus Repository](https://www.sonatype.com/products/nexus-repository) - 管理二进制文件并在整个软件供应链中构建工件.
-   [TreeScale](https://github.com/treescale)  - 构建和分发基于容器的应用程序. 经过 [@tigranbs](https://github.com/tigranbs)

## Development with Docker

### API Client

-   [ahab](https://github.com/instacart/ahab) - 使用 Python 处理 Docker 事件 [@instacart](https://github.com/instacart)
-   [clj-docker-client](https://github.com/into-docker/clj-docker-client)  :skull: - Docker 远程 API 的惯用 Clojure 客户端. 通过 [@lispyclouds][lispyclouds]
-   [contajners](https://github.com/lispyclouds/contajners)  - 用于 OCI 容器引擎的惯用的、数据驱动的、REPL 友好的 Clojure 客户端. 通过 [@lispyclouds][lispyclouds]
-   [Docker Client for JVM](https://github.com/gesellix/docker-client) - 用于 JVM 的 Docker 远程 api 客户端库，由 [@gesellix][gesellix] 用 Groovy 编写
-   [Docker Client TypeScript](https://gitlab.com/masaeedu/docker-client)  - 用于 JavaScript 的 Docker API 客户端，从 moby 存储库的 Swagger API 定义自动生成. 经过 [@masaeedu](https://github.com/masaeedu)
-   [docker-client](https://github.com/spotify/docker-client)  :skull: - Docker 远程 API 的 Java 客户端. 通过 [@spotify][spotify]
-   [docker-it-scala](https://github.com/whisklabs/docker-it-scala) - 与 Scala 的 Docker 集成测试套件 [@whisklabs](https://github.com/whisklabs)
-   [docker-java-api](https://github.com/amihaiemil/docker-java-api)  - 用于 Docker API 的轻量级、真正面向对象的 Java 客户端. 经过 [@amihaiemil](https://github.com/amihaiemil)
-   [docker-maven-plugin](https://github.com/fabric8io/docker-maven-plugin) - 用于运行和创建 Docker 图像的 Maven 插件 [@fabric8io](https://github.com/fabric8io)
-   [Docker-PowerShell](https://github.com/Microsoft/Docker-PowerShell) - 用于 Docker 的 PowerShell 模块
-   [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - C#/.NET HTTP client for the Docker remote API by [@https://github.com/veggiemonk/awesome-docker/blob/master/ahmetalpbalkan](https://github.com/veggiemonk/awesome-docker/blob/master/ahmetalpbalkan)
-   [Docker.Registry.DotNet](https://github.com/ChangemakerStudios/Docker.Registry.DotNet) - .NET (C#) Client Library for interacting with a Docker Registry API (v2) [@rquackenbush](https://github.com/rquackenbush)
-   [dockerfile-maven](https://github.com/spotify/dockerfile-maven) - [@spotify][spotify] 用于构建和推送 Docker 图像的 Maven 插件
-   [dockerode](https://github.com/apocas/dockerode) - Docker 远程 API node.js 模块 [@apocas](https://github.com/apocas)
-   [DoMonit](https://github.com/eon01/DoMonit) - 用于 Docker API 的简单 Docker 监控包装器
-   [go-dockerclient](https://github.com/fsouza/go-dockerclient/) - 通过 Docker 远程 API 的 HTTP 客户端 [@fsouza](https://github.com/fsouza/)
-   [Gradle Docker plugin](https://github.com/gesellix/gradle-docker-plugin) - [@gesellix][gesellix] 的 Gradle Docker 远程 api 插件
-   [libcompose](https://github.com/docker/libcompose) - 用于 Docker Compose 的 Go 库.
-   [Portainer stack utils](https://github.com/greenled/portainer-stack-utils)  ：构造： - Bash 脚本，用于从 docker-compose yaml 文件部署/更新/取消部署 Portainer 实例中的 Docker 堆栈. 经过 [@greenled](https://github.com/greenled).
-   [sbt-docker-compose](https://github.com/Tapad/sbt-docker-compose) - 将 Docker Compose 功能集成到 sbt 中 [@kurtkopchik](https://github.com/kurtkopchik/)
-   [sbt-docker](https://github.com/marcuslonnberg/sbt-docker) - 通过 sbt 直接创建 Docker 镜像 [@marcuslonnberg](https://github.com/marcuslonnberg)

### CI/CD

-   [Buddy :heavy_dollar_sign:](https://buddy.works) - 最好的 Git、构建和部署工具组合成一个强大的工具，推动了我们的开发.
-   [Captain](https://github.com/harbur/captain) - 将您的 Git 工作流转换为 Docker 容器，准备好持续交付 [@harbur](https://github.com/harbur).
-   [Cyclone](https://github.com/caicloud/cyclone) - 强大的工作流引擎和端到端的管道解决方案，通过原生 Kubernetes 资源实现 [@caicloud](https://github.com/caicloud).
-   [Depot :heavy_dollar_sign:](https://depot.dev)  - 在云端快速构建 Docker 镜像. 极速计算、自动智能缓存和零配置. [Done in seconds](https://depot.dev/#benchmarks).
-   [Diun](https://github.com/https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max/diun) - 在 Docker 注册表上更新图像或存储库时接收通知 [@https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max](https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max).
-   [Docker plugin for Jenkins](https://github.com/jenkinsci/docker-plugin/) - docker 插件的目的是能够使用 docker 主机动态配置从站，运行单个构建，然后拆除该从站.
-   [Dockupdater](https://github.com/dockupdater/dockupdater) - 自动使您的码头服务和码头容器保持最新
-   [Drone](https://github.com/drone/drone) - 基于 Docker 构建并使用 YAML 文件配置的持续集成服务器.
-   [GitLab Runner](https://gitlab.com/gitlab-org/gitlab-runner) - GitLab 集成了 CI 以使用 GitLab runners 测试、构建和部署您的代码.
-   [GOCD-Docker](https://github.com/gocd/gocd-docker) :skull: - 在 docker 容器中转到服务器和代理进行配置.
-   [Jaypore CI](https://github.com/theSage21/jaypore_ci)  - 在 Python 中配置的简单、非常灵活、强大的 CI/CD/自动化系统. 离线和本地优先.
-   [Kraken CI](https://github.com/Kraken-CI/kraken)  - 高度可扩展且专注于测试的现代 CI/CD、开源、本地系统. 它的执行者之一是 Docker. 由开发 [@Kraken-CI](https://github.com/Kraken-CI).
-   [Microservices Continuous Deployment](https://github.com/francescou/docker-continuous-deployment) - 持续部署微服务应用程序.
-   [mu](https://github.com/stelligent/mu) - 通过 AWS CodePipeline、CodeBuild 和 ECS 配置容器应用程序的 CI/CD 的工具 [@Stelligent](https://github.com/stelligent)
-   [Ouroboros](https://github.com/pyouroboros/ouroboros) ：skull： - 使用通知自动更新正在运行的 Docker 容器
-   [Popper](https://github.com/systemslab/popper) - Github 操作工作流（HCL 语法）执行引擎.
-   [Screwdriver :heavy_dollar_sign:](https://screwdriver.cd/) - 为持续交付而设计的雅虎开源构建平台.
-   [Skipper](https://github.com/Stratoscale/skipper) - 轻松将您的 Git 存储库 docker 化 [@Stratoscale](https://github.com/Stratoscale)
-   [SwarmCI](https://github.com/ghostsquad/swarmci) - 在您的 Docker Swarm 中创建分布式、隔离的任务管道.
-   [Watchtower](https://github.com/containrrr/watchtower) - 自动更新正在运行的 Docker 容器

### Development Environment

-   [batect](https://github.com/batect/batect) - 构建和测试环境作为代码工具：Dockerised 构建和测试环境变得容易 [@charleskorn](https://github.com/charleskorn)
-   [Binci](https://github.com/binci/binci)  - 容器化您的开发工作流程.  （以前是 DevLab [@TechnologyAdvice](https://github.com/TechnologyAdvice))
-   [Boot2Docker](https://github.com/boot2docker/boot2docker) :skull: - 适用于 OSX 和 Windows 的 Docker
-   [coder](https://github.com/coder/coder) - 由 Terraform 或 Docker 提供支持的远程开发机器 [@coder](https://github.com/coder)
-   [construi](https://github.com/lstephen/construi) - 在 Docker 定义的环境中运行您的构建 [@lstephen](https://github.com/lstephen)
-   [Crashcart](https://github.com/oracle/crashcart) - 将 Linux 二进制文件旁加载到正在运行的容器中，以便 [@Oracle][oracle] 进行故障排除
-   [dde](https://github.com/whatwedo/dde)  :construction: - 基于 Docker 的本地开发环境工具集. 经过 [@whatwedo](https://github.com/whatwedo)
-   [Devstep](https://github.com/fgrehm/devstep) :skull: - 由 [@fgrehm][fgrehm] 提供支持的 Docker 和 buildpacks 开发环境
-   [Dinghy](https://github.com/codekitchen/dinghy) - 在 Mac OS X 上使用 Docker Machine 和 virtualbox、vmware、xhyve 或 parallels 的另一种方法
-   [DIP](https://github.com/bibendi/dip)  - CLI 实用程序，用于直接配置和与 docker-compose 配置的应用程序交互. 经过 [@bibendi](https://github.com/bibendi)
-   [DLite](https://github.com/nlf/dlite)  :skull: - 在 OSX 上使用 Docker 的最简单方法，不需要 VM. 经过 [@nlf](https://github.com/nlf)
-   [dobi](https://github.com/dnephin/dobi)  - 用于 Docker 应用程序的构建自动化工具. 经过 [@dnephin](https://github.com/dnephin)
-   [Docker Missing Tools](https://github.com/nandoquintana/docker-missing-tools)  - 一组 bash 命令，用于简化典型的 docker dev-ops. 在代码存储库中创建典型的帮助程序脚本（如“build.sh”和“deploy.sh”）的替代方法. 经过 [@NandoQuintana](https://github.com/nandoquintana).
-   [Docker osx dev](https://github.com/brikis98/docker-osx-dev) :skull: - A productive development environment with Docker on OS X by [@brikis98](https://github.com/brikis98)
-   [Docker-Arch](https://github.com/Ph3nol/Docker-Arch)  - 从 1 个简单的 YAML 文件生成 Web/CLI 项目 Dockerized 开发环境. 经过 [@Ph3nol](https://github.com/ph3nol)
-   [docker-setup](https://github.com/nicholasdille/docker-setup)  - 安装、配置和更新容器工具. 经过 [@nicholasdille](https://twitter.com/nicholasdille)
-   [Docker-sync](https://github.com/EugenMayer/docker-sync) - 显着提高性能（[50-70x](https://github.com/EugenMayer/docker-sync/wiki/4.-Performance) ) 在 Mac OS X/Windows 和 Linux 上使用 Docker 进行开发，同时将代码共享到容器. 经过 [@EugenMayer](https://github.com/EugenMayer)
-   [docker-vm](https://github.com/shyiko/docker-vm) - boot2docker 的简单透明替代方案（由 Vagrant 支持） [@shyiko](https://github.com/shyiko)
-   [DockerBuildManagement](https://github.com/DIPSAS/DockerBuildManagement)  - Build Management 是一个 python 应用程序，使用 pip 安装. 该应用程序通过配置描述如何构建、测试、运行或发布容器化解决方案的单个 yaml 文件，可以轻松管理基于 Docker 的构建系统.
-   [DockerDL](https://github.com/matifali/dockerdl)  - 深度学习 Docker 图像. 当您可以获得预装了所有内容的深度学习环境时，不要浪费时间设置深度学习环境.
-   [Dusty](https://github.com/gamechanger/dusty) - OS X 上的托管 Docker 开发环境
-   [Eclipse Che](https://github.com/eclipse/che) - 具有 Docker 运行时、云 IDE、下一代 Eclipse IDE 的开发人员工作区服务器
-   [EnvCLI](https://github.com/EnvCLI/EnvCLI)  - 用项目特定的 docker 容器替换本地安装的 Node、Go 等. 经过 [@EnvCLI](https://github.com/EnvCLI)
-   [footloose](https://github.com/weaveworks/footloose) - 旋转看起来像虚拟机的容器 - 作者 [@dlespiau](https://github.com/dlespiau)
-   [forward2docker](https://github.com/bsideup/forward2docker) :skull: - 将端口从本地主机自动转发到在 boot2docker VM 中运行的 Docker 容器上的端口的实用程序 [@bsideup](https://github.com/bsideup)
-   [Gebug](https://github.com/moshebe/gebug) - 通过无缝启用调试器和热重载功能，使 Dockerized Go 应用程序的调试变得超级容易的工具.
-   [Kitt](https://github.com/senges/kitt)  - 基于 Docker 和 Nix 的便携式一次性 Shell 环境. 经过 [@senges](https://github.com/senges)
-   [Lando](https://github.com/lando/lando)  - Lando 适用于希望快速指定并轻松启动开发项目所需的服务和工具的开发人员. 经过 [Tandem](https://thinktandem.io/)
-   [Vagga](https://github.com/tailhook/vagga)  - Vagga 是一个没有守护进程的容器化工具. 它是受 Vagrant 和 Docker 启发的全用户空间容器引擎，专门用于开发环境 [@tailhook](https://github.com/tailhook/)
-   [Zsh-in-Docker](https://github.com/deluan/zsh-in-docker)  - 只需一行即可在 Docker 容器中安装 Zsh、Oh-My-Zsh 和插件！ 经过 [Deluan](https://www.deluan.com)

### Garbage Collection

-   [caduc](https://github.com/tjamet/caduc) - 一个 docker 垃圾收集器清理你最近没有使用的东西
-   [Docker Clean](https://github.com/ZZROTDesign/docker-clean) - 一个清理 Docker 容器、镜像和卷的脚本 [@zzrotdesign](https://github.com/ZZROTDesign)
-   [docker_gc](https://github.com/pdacity/docker_gc)  - 用于自动删除未使用的 Docker Swarm 对象的图像. 也像 Docker 服务一样工作 [@pdacity](https://github.com/pdacity)
-   [Docker-cleanup](https://github.com/meltwater/docker-cleanup) :skull: - 自动 Docker 映像、容器和卷清理 [@meltwater](https://github.com/meltwater)
-   [docker-custodian](https://github.com/Yelp/docker-custodian)  - 保持 docker 主机整洁. 经过 [@Yelp](https://github.com/Yelp)
-   [docker-garby](https://github.com/konstruktoid/docker-garby) - Docker垃圾收集脚本 [@konstruktoid](https://github.com/konstruktoid).
-   [docker-gc](https://github.com/spotify/docker-gc) :skull: - 一个 cron 作业，将删除旧的已停止容器和 [@spotify][spotify] 未使用的图像
-   [sherdock](https://github.com/rancher/sherdock) :skull: - 基于正则表达式的图像自动 GC by [@rancher][rancher]

### Serverless

-   [AMP](https://github.com/appcelerator-archive/amp)  ：skull： - 用于 Docker 的开源统一 CaaS / FaaS 平台，包括电池. 经过 [@Appcelerator](https://github.com/appcelerator-archive)
-   [Apache OpenWhisk](https://github.com/apache/openwhisk)  - 一个无服务器的开源云平台，可执行功能以响应任何规模的事件. 经过 [@apache](https://github.com/apache)
-   [Docker-Lambda](https://github.com/lambci/docker-lambda)  - 复制实时 AWS Lambda 环境的 Docker 图像和测试运行器. 经过 [@lamb-ci](https://github.com/lambci)
-   [Funker](https://github.com/bfirsh/funker-example-voting-app)  - 用作 Docker 容器示例投票应用程序. 经过 [@bfirsh](https://github.com/bfirsh)
-   [IronFunctions](https://github.com/iron-io/functions) - 无服务器微服务平台 FaaS（函数即服务），它使用 Docker 容器运行任何语言或 AWS Lambda 函数
-   [Koyeb](https://www.koyeb.com/)  ：heavy_dollar_sign： - Koyeb 是一个对开发人员友好的无服务器平台，用于在全球部署应用程序. 借助基于 git 的部署、本机自动缩放、全球边缘网络以及内置服务网格和发现，无缝运行 Docker 容器、Web 应用程序和 API.
-   [OpenFaaS](https://github.com/openfaas/faas)  - 适用于 Docker 和 Kubernetes 的完整无服务器功能框架. 经过 [OpenFaaS](https://github.com/openfaas)
-   [SCAR](https://github.com/grycap/scar) - 无服务器容器感知架构 (SCAR) 是一个无服务器框架，允许在无服务器环境（如 Lambda）中轻松部署和执行容器（如 Docker） [@grycap](https://github.com/grycap)

### Testing

-   [Container Structure Test](https://github.com/GoogleContainerTools/container-structure-test)  - 通过检查命令的输出或文件系统的内容来验证图像结构的框架. 通过 [@GoogleContainerTools][googlecontainertools]
-   [dgoss](https://github.com/aelsabbahy/goss/tree/master/extras/dgoss) - 一种基于 YAML 的快速工具，用于验证 docker 容器.
-   [DockerSpec](https://github.com/zuazo/dockerspec)  - 一个小的 Ruby Gem，可以轻松地针对 Dockerfiles 或 Docker 图像运行 RSpec 和 Serverspec、Infrataster 和 Capybara 测试. 经过 [@zuazo](https://github.com/zuazo)
-   [Dockunit](https://github.com/dockunit/platform)  :skull: - 基于 Docker 的集成测试. 一个简单的基于节点的实用程序，用于运行基于 Docker 的单元测试. 经过 [@dockunit](https://github.com/dockunit)
 - [InSpec][inspec] - InSpec 是一个用于基础设施的开源测试框架，具有用于指定合规性、安全性和策略要求的人类和机器可读语言. 经过 [@chef](https://github.com/chef)
-   [Pull Dog](https://github.com/apps/pull-dog)  - 一个 GitHub 应用程序，可从您的 docker-compose 文件自动为您的拉取请求创建基于 Docker 的测试环境. 不开源.
-   [Pumba](https://github.com/alexei-led/pumba)  - Docker 混沌测试工具. 可以部署在kubernetes和CoreOS集群上. 经过 [@alexei-led](https://github.com/alexei-led)

### Wrappers

-   [Ansible](https://docs.ansible.com/ansible/latest/collections/community/general/docker_container_module.html)  - 管理 Docker 容器的生命周期. 通过红帽
-   [Azk](https://github.com/azukiapp/azk) - 通过以下方式在本地计算机上编排开发环境 [@azukiapp](https://github.com/azukiapp)
-   [Beluga](https://github.com/cortexmedia/Beluga)  ：skull： - CLI 用于在单个服务器或少量服务器上部署 docker 容器. 经过 [@cortextmedia](https://github.com/cortexmedia)
-   [dexec](https://github.com/docker-exec/dexec) - 用 Go 编写的命令行界面，用于使用 Docker Exec 图像运行代码.
-   [dockerized](https://github.com/benzaita/dockerized-cli) - 在容器中无缝执行命令.
-   [Dray](https://github.com/CenturyLinkLabs/dray) - [@CenturyLinkLabs][centurylinklabs] 用于管理基于容器的工作流执行的引擎
-   [FuGu](https://github.com/mattes/fugu) :skull: - Docker 在没有编排的情况下运行包装器 [@mattes](https://github.com/mattes)
-   [Hokusai](https://github.com/artsy/hokusai)  - 面向应用程序开发人员的 Docker + Kubernetes CLI； 用于容器化应用程序并在整个开发、测试和发布周期中管理其生命周期. 从 [@artsy](https://github.com/artsy)
-   [Shutit](https://github.com/ianmiell/shutit) - 用于构建和维护复杂 Docker 部署的工具 [@ianmiell](https://github.com/ianmiell)
-   [subuser](https://github.com/subuser-security/subuser) - 使在 Docker 中安全且可移植地运行图形桌面应用程序变得容易
-   [T.A.D.S. boilerplate](https://github.com/Thomvaill/tads-boilerplate)  - Ansible 和 Terraform 的强大功能 + Docker Swarm 的简单性 = 基础架构即代码和 DevOps 最佳实践. 经过 [@Thomvaill](https://github.com/Thomvaill)
-   [Terraform cloud-init config](https://github.com/christippett/terraform-cloudinit-container-server) - 用于将单个 Docker 映像或“docker-compose.yaml”文件部署到任何 Cloud™ VM 的 Terraform 模块
-   [Turbo](https://github.com/ramitsurana/turbo)  - 简单而强大的 docker 实用程序. 通过 [@ramitsurana][ramitsurana]
-   [udocker](https://github.com/indigo-dc/udocker) - 一种在没有 root 权限的情况下在批处理或交互式系统中执行简单 docker 容器的工具 [@inidigo-dc](https://github.com/indigo-dc)
-   [Vagrant - Docker provider](https://developer.hashicorp.com/vagrant/docs/providers/docker/basics) - 好的起点是 [vagrant-docker-example](https://github.com/bubenkoff/vagrant-docker-example) 经过 [@bubenkoff](https://github.com/bubenkoff)

## Services based on Docker (mostly :heavy_dollar_sign:)

### CI Services

-   [CircleCI](https://circleci.com/) ：heavy_dollar_sign：- 从您的构建环境中推送或拉取 Docker 图像，或者直接在 CircleCI 上构建和运行容器.
-   [CodeFresh](https://codefresh.io)  :heavy_dollar_sign: - 构建、测试和共享 Docker 应用程序所需的一切. 提供自动化的端到端测试.
-   [CodeShip](https://www.cloudbees.com/products/codeship) :heavy_dollar_sign: - 使用您已建立的 Docker 工作流程，同时使用我们专用于速度和安全性的托管平台自动化您的测试和部署任务.
-   [ConcourseCI](https://concourse-ci.org) ：heavy_dollar_sign： - 面向开发人员和 DevOps 团队的 CI SaaS 平台.
-   [Semaphore CI](https://semaphoreci.com/) :heavy_dollar_sign: — 一种高性能的云解决方案，可以轻松构建、测试容器并将其运送到生产环境.
-   [TravisCI](https://www.travis-ci.com/) ：heavy_dollar_sign：- 一个免费的 github 项目，用于开发人员和 Devops 的持续集成 SaaS 平台.

### CaaS

-   [Amazon ECS](https://aws.amazon.com/ecs/) ：heavy_dollar_sign： - EC2 上支持 Docker 容器的管理服务.
-   [Appfleet](https://appfleet.com/)  ：heavy_dollar_sign：- 用于在全球部署和管理容器化服务的边缘平台. 系统会将流量路由到最近的位置以降低延迟.
-   [Azure AKS](https://azure.microsoft.com/en-us/products/kubernetes-service/)  ：heavy_dollar_sign：- 简化 Kubernetes 管理、部署和操作. 使用完全托管的 Kubernetes 容器编排服务.
-   [Cloud 66](https://www.cloud66.com) ：heavy_dollar_sign：- 全栈托管容器管理即服务
-   [Dockhero](https://dockhero.io/)  ：heavy_dollar_sign： - Dockhero 是一个 Heroku 附加组件，它将 Docker 映像转换为附加到 Heroku 应用程序的微服务. 目前处于测试阶段.
-   [Giant Swarm](https://www.giantswarm.io/)  ：heavy_dollar_sign： - 简单的微服务基础设施. 在几秒钟内部署您的容器.
-   [Google Container Engine](https://cloud.google.com/kubernetes-engine/docs/) ：heavy_dollar_sign： - 由 [Kubernetes][kubernetes] 提供支持的 Google Cloud Computing 上的 Docker 容器.
-   [Mesosphere DC/OS Platform](https://d2iq.com/products/dcos) ：heavy_dollar_sign：- 基于 Apache Mesos 构建的数据和容器集成平台 [@mesosphere](https://d2iq.com)
-   [Red Hat CodeReady Workspaces](https://developers.redhat.com/products/openshift-dev-spaces/overview) - A collaborative Kubernetes-native solution for rapid application development that delivers consistent developer environments on Red Hat OpenShift to allow anyone with a browser to contribute code in under two minutes.
-   [Red Hat OpenShift Dedicated](https://www.redhat.com/en/technologies/cloud-computing/openshift/dedicated) ：heavy_dollar_sign：- Amazon Web Services 和 Google Cloud 上的完全托管的 Red Hat® OpenShift® 服务
-   [Sloppy.io](https://sloppy.io/en/) :heavy_dollar_sign: - 用于容器部署和托管的多合一解决方案 – 在德国制造和托管
-   [Triton](https://www.joyent.com/) ：heavy_dollar_sign： - Joyent 的弹性容器原生基础设施.
-   [Virtuozzo Application Platform](https://www.virtuozzo.com/application-platform-partners/) ：heavy_dollar_sign：- 在广泛的可靠服务提供商网络中使用交钥匙 PaaS 部署和管理您的项目

### Monitoring Services

-   [AppDynamics](https://github.com/Appdynamics/docker-monitoring-extension) - Docker Monitoring 扩展使用 Unix Socket 或 TCP 从 Docker Remote API 收集指标.
-   [Broadcom Docker Monitoring](https://www.broadcom.com/info/aiops/docker-monitoring)  ：heavy_dollar_sign：- Broadcom 的敏捷运营解决方案提供现代 Docker 监控业务，以加速和优化微服务的性能以及运行它们的动态 Docker 环境. 监控 Docker 环境和在其中运行的应用程序.  （前CA Technologies）
-   [Collecting docker logs and stats with Splunk](https://www.splunk.com/en_us/blog/tips-and-tricks/collecting-docker-logs-and-stats-with-splunk.html)
-   [Datadog](https://www.datadoghq.com/)  ：heavy_dollar_sign：-Datadog 是一种针对大规模云环境的全栈监控服务，可聚合来自服务器、数据库和应用程序的指标/事件. 它包括对 Docker、Kubernetes 和 Mesos 的支持.
-   [Prometheus](https://prometheus.io/) ：heavy_dollar_sign：- 开源服务监控系统和时间序列数据库
-   [Site24x7](https://www.site24x7.com/docker-monitoring.html) ：heavy_dollar_sign：- 用于 DevOps 和 IT 的 Docker 监控是按主机模型付费的 SaaS
-   [SPM for Docker](https://github.com/sematext/sematext-agent-docker)  ：heavy_dollar_sign：- 监控主机和容器指标、Docker 事件和日志. 自动日志解析器. 指标和日志的异常检测和警报. [@sematext](https://github.com/sematext)
-   [Sysdig Monitor](https://sysdig.com/products/monitor/)  ：heavy_dollar_sign：-Sysdig Monitor 可以用作软件或 SaaS 服务，以使用系统调用来监视、警报和排除容器故障. 它具有适用于 Docker 和 Kubernetes 的容器特定功能.

## Useful Resources

-   **[Valuable Docker Links](http://nane.kratzke.pages.mylab.th-luebeck.de/about/blog/2014/08/24/valuable-docker-links/) ** 关于docker的高质量文章！  **必看**
-   [Become a Docker Power User with Visual Studio Code](https://www.thebyte.io/become-docker-power-user-with-vs-code) - :heavy_dollar_sign: 帮助你成为 Visual Studio Code 的 Docker Power 用户的培训课程
-   [Cloud Native Landscape](https://github.com/cncf/landscape)
-   [Docker Certification](https://intellipaat.com/docker-training-course/?US) :heavy_dollar_sign: 将帮助您通过实践项目和案例研究学习 Docker 容器化、运行 Docker 容器、图像创建、Dockerfile、Docker 编排、安全最佳实践等，并有助于清除 Docker Certified Associate.
-   [Docker Community on Hashnode](https://hashnode.com/n/docker)
-   [Docker dev bookmarks](https://www.codever.dev/search?q=docker) - 使用标签 [docker](https://www.codever.dev/bookmarks/t/docker)
-   [Docker in Action, Second Edition](https://www.manning.com/books/docker-in-action-second-edition)
-   [Docker in Practice, Second Edition](https://www.manning.com/books/docker-in-practice-second-edition)
-   [Docker Newsletter](https://www.docker.com/newsletter-subscription/) 定期更新的 Docker 时事通讯
-   [Docker packaging guide for Python](https://pythonspeed.com/docker/) - 一系列关于 Python 的 Docker 打包细节的详细文章.
-   [Learn Docker in a Month of Lunches](https://www.manning.com/books/learn-docker-in-a-month-of-lunches)
-   [Learn Docker](https://coursesity.com/blog/best-docker-tutorials/) - 学习 Docker - 顶级在线 Docker 教程和课程的精选列表.
-   [Programming Community Curated Resources for learning Docker](https://hackr.io/tutorials/learn-docker)

## Awesome Lists

-   [Awesome CI/CD](https://github.com/cicdops/awesome-ciandcd) - 不特定于 docker 但相关.
-   [Awesome Compose](https://github.com/docker/awesome-compose) - Docker 组合示例
-   [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes) 通过 [@ramitsurana][ramitsurana]
-   [Awesome Linux Container](https://github.com/Friz-zy/awesome-linux-containers) 关于容器比这个 repo 更一般，通过 [@Friz-zy](https://github.com/Friz-zy).
-   [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) 自由软件网络服务和 Web 应用程序的列表，它们可以通过以经典方式运行（设置本地 Web 服务器并从那里运行应用程序）或在 Docker 容器中运行来本地托管. 经过 [@Kickball](https://github.com/Kickball)
-   [Awesome Sysadmin](https://github.com/n1trux/awesome-sysadmin) 经过 [@n1trux](https://github.com/n1trux)
-   [ToolsOfTheTrade](https://github.com/cjbarber/ToolsOfTheTrade) SaaS 和本地应用程序列表 [@cjbarber](https://github.com/cjbarber)

## Demos and Examples

-   [An Annotated Docker Config for Frontend Web Development](https://nystudio107.com/blog/an-annotated-docker-config-for-frontend-web-development) 使用 Docker 的本地开发环境允许您将项目所需的 devops 收缩包装为配置，从而使入职变得顺畅.
-   [Local Docker DB](https://github.com/alexmacarthur/local-docker-db) 许多数据库的 docker-compose 示例列表 [@alexmacarthur](https://github.com/alexmacarthur)
-   [Webstack-micro](https://github.com/ferbs/webstack-micro) 演示网络应用程序展示了如何使用 Docker Compose 将 API 网关、集中式身份验证、后台工作人员和 WebSockets 设置为容器化服务.

## Good Tips

-   [Docker Caveats](http://docker-saigon.github.io/post/Docker-Caveats/) 关于在生产环境中运行 Docker 你应该知道什么（写于 2016 年 4 月 11 日）**必看**
-   [Docker Containers on the Desktop](https://blog.jessfraz.com/post/docker-containers-on-the-desktop/) - [@jessfraz][jessfraz] 以**最有趣的方式**了解 docker，他还提供了 [presentation](https://www.youtube.com/watch?v=1qlLUf7KtAw) 关于它@DockerCon 2015
-   [Docker vs. VMs? Combining Both for Cloud Portability Nirvana](https://www.flexera.com/blog/cloud/docker-vs-vms-combining-both-for-cloud-portability-nirvana/)
-   [Dockerfile best practices](https://github.com/hexops/dockerfile) - 这个存储库有编写 Dockerfiles 的最佳实践
-   [Don't Repeat Yourself with Anchors, Aliases and Extensions in Docker Compose Files](https://medium.com/@kinghuang/docker-compose-anchors-aliases-extensions-a1e4105d70bd) 经过 [@King Chung Huang](https://github.com/kinghuang)
-   [GUI Apps with Docker](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/) 通过 [@fgrehm][fgrehm]

## Raspberry Pi & ARM

-   [Docker Pirates ARMed with explosive stuff](https://blog.hypriot.com/) 关于集群、swarm、docker、Raspberry Pi 上 SD 卡预装映像的大量资源
-   [Get Docker up and running on the RaspberryPi in three steps](https://github.com/umiddelb/armhf/wiki/Get-Docker-up-and-running-on-the-RaspberryPi-%28ARMv6%29-in-three-steps)
-   [git push docker containers to linux devices](https://www.balena.io) 物联网的现代 DevOps，利用 git 和 Docker.
-   [Installing, running, using Docker on armhf (ARMv7) devices](https://github.com/umiddelb/armhf/wiki/Installing,-running,-using-docker-on-armhf-%28ARMv7%29-devices)

## Security

-   [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
-   [CVE Scanning Alpine images with Multi-stage builds in Docker 17.05](https://github.com/tomwillfixit/alpine-cvecheck) 经过 [@tomwillfixit](https://twitter.com/tomwillfixit)
-   [Docker Secure Deployment Guidelines](https://github.com/AonCyberLabs/Docker-Secure-Deployment-Guidelines)
-   [Docker Security - Quick Reference](https://binarymist.io/publication/docker-security/)
-   [Docker Security Cheat Sheet](https://github.com/konstruktoid/Docker/blob/master/Security/CheatSheet.adoc)
-   [Docker Security: Are Your Containers Tightly Secured to the Ship? SlideShare](https://fr.slideshare.net/MichaelBoelen/docker-security-are-your-containers-tightly-secured-to-the-ship)
-   [How CVE's are handled on Offical Docker Images](https://github.com/docker-library/official-images/issues/1448)
-   [Lynis is an open source security auditing tool including Docker auditing](https://cisofy.com/lynis/)
-   [Security Best Practices for Building Docker Images](https://linux-audit.com/tag/docker/)
-   [Software Engineering Radio interview of Docker Security Team Lead (Diogo Mónica)](https://www.se-radio.net/2017/05/se-radio-episode-290-diogo-monica-on-docker-security/)
-   [Ten Docker Image Security Best Practices Cheat Sheet](https://snyk.io/blog/10-docker-image-security-best-practices/)
-   [Top ten most popular docker images each contain at least 30 vulnerabilities](https://snyk.io/blog/top-ten-most-popular-docker-images-each-contain-at-least-30-vulnerabilities/)
-   [Tuning Docker with the newest security enhancements](https://opensource.com/business/15/3/docker-security-tuning)
-   [10 best practices to containerize Node.js web applications with Docker](https://snyk.io/blog/10-best-practices-to-containerize-nodejs-web-applications-with-docker/)

## Videos

-   [Contributing to Docker by Andrew "Tianon" Page (InfoSiftr)](https://www.youtube.com/watch?v=1jwo8-1HYYg) (34:31)
-   [Deploying and scaling applications with Docker, Swarm, and a tiny bit of Python magic](https://www.youtube.com/watch?v=GpHMTR7P2Ms) (3:11:06) [@jpetazzo][jpetazzo]
-   [Docker and SELinux by Daniel Walsh from Red Hat](https://www.youtube.com/watch?v=zWGFqMuEHdw) (40:23)
-   [Docker Course](https://www.youtube.com/watch?v=UZpyvK6UGFo) （西班牙语）由 [@pablokbs](https://github.com/pablokbs)
-   [Docker for Developers](https://www.youtube.com/watch?v=FdkNAjjO5yQ) (54:26) by [@jpetazzo][jpetazzo] &lt;== 很好的介绍、上下文、演示
-   [Docker from scratch](https://www.youtube.com/playlist?list=PLLhEJK7fQIxD-btrjrqdEfQHbkZnQrmqE) (1:22:01) 在 YouTube 上，Paris Nakita Kejser
-   [Docker: How to Use Your Own Private Registry](https://www.youtube.com/watch?v=CAewZCBT4PI) (15:01)
-   [Docker in Production](https://www.youtube.com/watch?v=Glk5d5WP6MI) 通过 [@jpetazzo][jpetazzo] (36:05)
-   [Docker Primer to Docker Compose](https://www.youtube.com/watch?v=G-s2GXGAjTk) (1:56:45) 在 YouTube 上由 LoginRadius
-   [Docker Registry from scratch](https://www.youtube.com/playlist?list=PLLhEJK7fQIxAz3d4Fj3edq7UcxEhdTCBm) (44:40) 在 YouTube 上，Paris Nakita Kejser
-   [Docker Swarm from scratch](https://www.youtube.com/playlist?list=PLLhEJK7fQIxAY4gZd1Wl-GsLvg-e9Ap1e) (1:41:28) 在 YouTube 上，Paris Nakita Kejser
-   [Extending Docker with Plugins](https://vimeo.com/110835013) (15:21)
-   [From Local Docker Development to Production Deployments](https://www.youtube.com/watch?v=7CZFpHUPqXw) 作者：[@jpetazzo][jpetazzo] @AWS re:Invent 2015
-   [Immutable Infrastructure with Docker and EC2 by Michael Bryzek (Gilt)](https://www.youtube.com/watch?v=GaHzdqFithc) (42:04)
-   [Introduction to Docker and containers](https://www.youtube.com/watch?v=ZVaRK10HBjo) (3:09:00) [@jpetazzo][jpetazzo]
-   [Logging on Docker: What You Need to Know](https://vimeo.com/123341629) (51:27)
-   [Performance Analysis of Docker - Jeremy Eder](https://www.youtube.com/watch?v=6f2E6PKYb0w) (1:36:58)
-   [Scalable Microservices with Kubernetes](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615) 免费优达学城课程
-   [State of containers: a debate with CoreOS, VMware and Google](https://www.youtube.com/watch?v=IiITP3yIRd8) (27:38)
-   [List of online courses (free and paid) about Docker](https://skillcombo.com/topic/docker/)

## Communities and Meetups

## Brazilian

-   [Docker BR on Slack](http://docker-br.herokuapp.com) - 自动邀请网址
-   [Docker BR on Telegram](https://telegram.me/dockerbr)

## Chinese

-   [DockerOne](http://dockone.io/) Docker 社区（中文） by [@LiYingJie](http://dockone.io/people/%E6%9D%8E%E9%A2%96%E6%9D%B0)

## English

-   [Docker Community](https://www.docker.com/community/)
-   [Docker Events](https://www.docker.com/events/)
-   [Docker Online Meetup](https://www.meetup.com/en-AU/Docker-Online-Meetup/)
-   [Docker Reddit Community](https://www.reddit.com/r/docker/)

## Russian

-   [Docker Russian-speaking Community](https://t.me/docker_ru)

## Spanish

-   [Docker Tips](https://dockertips.com/)

## Stargazers over time

[![Stargazers over time](https://starchart.cc/veggiemonk/awesome-docker.svg)](https://starchart.cc/veggiemonk/awesome-docker)

## Contributor over time

[贡献]：https://github.com/veggiemonk/awesome-docker/blob/master/.github/CONTRIBUTING.md
[akito]: https://github.com/theAkito
[印花布]：https://github.com/projectcalico/calico
[世纪互联实验室]：https://github.com/CenturyLinkLabs
[containx]：https://github.com/ContainX
[容器]：https://github.com/containers
[核心]：https://github.com/cores
[cncf]：https://www.cncf.io
[疯狂最大]：https://github.com/crazy-max
[深度防护]：https://github.com/deepfence
[分发]：https://github.com/docker/distribution
[码头流程]：https://github.com/docker-flow
[docker-for-windows]：https://docs.docker.com/desktop/install/windows-install/
[泊坞窗]：https://github.com/docker
[editreadme]：https://github.com/veggiemonk/awesome-docker/edit/master/README.md
[fgrehm]：https://github.com/fgrehm
[gesellschaftlix]：https://github.com/gesellschaftlix
[genuinetools]: https://github.com/genuinetools
[滑翔机实验室]：https://github.com/gliderlabs
[语法]：https://github.com/grammarly
[谷歌]：https://github.com/google
[googlecontainertools]：https://github.com/GoogleContainerTools
[检查]：https://github.com/inspec/inspec
[jessfraz]: https://github.com/jessfraz
[jpetazzo]：https://github.com/jpetazzo
[jwilder]：https://github.com/jwilder
[kubernetes]：https://kubernetes.io
[lispyclouds]：https://github.com/lispyclouds
[英伟达]：https://github.com/nvidia
[nginxproxy]: https://github.com/nginx-proxy/nginx-proxy
[开班]：https://www.okd.io
[甲骨文]：https://github.com/oracle
[powerman]：https://github.com/powerman
[progrium]：https://github.com/progrium
[ramitsurana]：https://github.com/ramitsurana
[牧场主]：https://github.com/rancher
[安全水域]：https://github.com/safe-waters
[sindresorhus]：https://github.com/sindresorhus/awesome
[音乐]：https://github.com/spotify
[tomastomecek]：https://github.com/TomasTomecek
[vegasbrianc]：https://github.com/vegasbrianc
[编织]：https://github.com/weaveworks/weave
[vmware]：https://github.com/vmware
[@byrnedo]：https://github.com/byrnedo
[@skanehira]：https://github.com/skanehira
