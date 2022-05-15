<div class="github-widget" data-repo="golemfactory/awesome-golem"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Golem [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![awesome-lint](https://github.com/golemfactory/awesome-golem/actions/workflows/main.yml/badge.svg)](https://github.com/golemfactory/awesome-golem/actions/workflows/main.yml/badge.svg)

[<img src="https://raw.githubusercontent.com/golemfactory/awesome-golem/master/golem-logo.svg?sanitize=true" align="right" width="150">](https://golem.network/)

&gt; 欢迎来到 **Awesome Golem**，这是一个社区策划的 Golem 资源、链接、项目、工具和应用程序列表！

 Golem 的用户以 Rust 实现 Yagna 的形式运行参考实现. 用户共同组成了 Golem 网络，这是一个计算资源的 P2P 市场，个人可以在其中充当两个非排他性角色之一； 出售闲置资源的提供者，或购买资源以运行任务的请求者.



## Golem

- [Golem Network Platform](https://www.golem.network/platform) - 在 Golem Network 官方网站上了解 Golem 平台.
- [Golem Factory GitHub](https://github.com/golemfactory) - 在哪里可以找到 Golem 的所有东西的开源代码.
- [Yagna GitHub](https://github.com/golemfactory/yagna) - Golem 的官方 Rust 实现.
- [Golem Community Chat](https://chat.golem.network/) - 加入社区和团队在 Discord 上公开讨论.
- [Reddit](https://reddit.com/r/GolemProject) - Reddit 平台上的 Golem Network 讨论.
- [Twitter](https://twitter.com/golemproject) - 魔像项目推特.
- [Blog](http://blog.golemproject.net/) - 官方博客，您可以在其中找到有关公告、摘要和更新的最可靠信息.

## Thorg

- [About Thorg](https://www.thorg.io/about) - Learn what the Thorg miner does.
- [Thorg Usage](https://www.thorg.io/usage) - 了解 Thorg 的深处.
- [Twitter](https://twitter.com/minewiththorg) - Thorg 的官方推特.

## Network Statistics

- [Golem Network Stats](https://stats.golem.network) - Golem 网络中的统计跟踪任务和提供者资源利用率.
- [Golem Stats backend](https://github.com/cryptobench/golem-stats-backend) - Golem 网络统计页面的后端，包括 API 端点 URL.
- [Stats API Documentation](https://docs.stats.golem.network/) - Golem Network Stats 页面用于显示其数据的 API 端点.

## Apps

- [Golem SLATE](https://golem-slate.xyz/)  - 托管代码笔 SPA，用于编写请求者脚本以由网络计算工作. 利用 dockerized yagna 环境在后台与 Golem 网络进行通信.
- [Chess On Golem](https://chessongolem.app/) - 托管国际象棋应用程序，与利用 Stockfish 开源国际象棋引擎的网络提供商对战.
- [Go le' Machin](https://github.com/DEUTSCHKLUB/go-le-m) - 基于 Web 的批量图像编辑器，允许用户上传多个图像并对它们应用批量操作.

### Docker

- [Golem Requestor Node](https://github.com/DerekJarvis/general-golem)  - Dockerized 请求者环境. 传入 py 脚本，它会设置守护进程并运行它.

### Testing

- [Golem Test Harness (Goth)](https://github.com/golemfactory/goth) - 旨在加快您的开发过程并使应用程序创建者更愉快的工具.
- [Golem-afl](https://github.com/sladecek/golem-afl)  - 一个实验性的测试模糊框架. 协助发现安全漏洞.
- [Golem Cargo Test](https://github.com/sladecek/golem_cargo_test) - 适用于 Rust 项目的自适应分布式测试执行器.
- [Golem CI](https://github.com/hhio618/golem-ci) - 分散的任务管道.
- [Golem SLATE](https://github.com/deutschklub/golem-slate) - 上述应用部分中描述的 Golem SLATE 的开源存储库.
- [ThorgPress](https://github.com/figurestudios/thorgpress) - 一种对供应商进行基准测试并揭示其真实能力的工具，超出了市场所能看到的范围.

### VPN

- [Yagna httpx client](https://github.com/golemfactory/ya-httpx-client/tree/johny-b/vpn) - Yagna 上的 VPN 使用演示了与基于提供程序的 HTTP 服务器的通信，就像您与任何其他 HTTP 服务器进行通信一样.
- [Golem Provider with network access](https://github.com/jedbrooke/golem-network-requestor) - 作为运行提供商的 http 代理的请求者，允许他们访问更广泛的互联网.

### Games

- [Golem Sudoku](https://github.com/Dodecane/golem-sudoku) - 具有大小变体的数独游戏.
- [HSOG-requester](https://github.com/ChrisHelmsC/hsog-requestor) - 通过运行大量模拟游戏，帮助炉石社区设计和构建套牌.
- [ChessOnGolem](https://github.com/broadcastmonkey/ChessOnGolem)  - 第一个应用程序部分中描述的国际象棋开源存储库. 包括 2 个 AI 通过 Golem 后端相互对抗的 React 前端.
- [Golem Fleet Battle Simulator](https://github.com/UnfortuN8/Golem-Fleet-Battle-Simulator)  - 计算两艘敌对星舰舰队之间战斗结果的系统. 在 iOS 游戏 Rock Paper Frigate 中用于确定 PvP 舰队战的结果.

### CLI Tools

- [Golem Completion Engine](https://github.com/krunch3r76/gc__enhanced_completion) - 增强的 bash 补全引擎，通过为 golemsp 和 yagna 提供上下文帮助来扩展内置补全.
- [Golocity](https://github.com/davidstyers/golocity) - 只需两个命令即可在 Golem 网络上构建和部署您的 dockerized 应用程序.

### Video Transcoding and Editing

- [Golem Network Video Transcoder](https://github.com/Doc-Saintly/golem-video)  - 用于转码视频的示例应用程序. 选择您的转码配置文件，然后上传您的视频.
- [Golem Transcoding requestor](https://github.com/Edhendil/golem-transcoding) - 基于 React + Spring 的 webapp 接受视频文件作为输入并将这些文件转码为不同的格式.
- [Golem Auto Editor](https://github.com/jedbrooke/golem-auto-editor) - 运行 Auto-Editor 自动执行一些视频编辑功能，将视频处理卸载到 Golem.

### Data Analysis

- [Flan](https://github.com/nestorbonilla/flan) - 为企业家提供对全球数百万条贸易价值记录进行定制分析的工具，为他们提供有关需要更多关注的领域的大胆指导.
- [Golem Lorenz-attractor](https://github.com/hhio618/golem-lorenz-attractor) - 一个由三个耦合的一阶非线性微分方程组成的系统，用于描述粒子随时间的轨迹.
- [Golem Geomandel](https://github.com/Edhendil/golem-geomandel) - 用于生成以单个点为中心的 Mandelbrot 图像序列的 Python 脚本，每个图像的缩放增加.
- [Golem COVID](https://github.com/iRhonin/golem-covid)  - 创建与 COVID 相关的每百万新死亡人数的图像. 生成所有图像后，它将收集它们并创建一个 gif.
- [Golem Parallel Matplotlib](https://github.com/CoeJoder/golem-parallel-matplotlib) - 对人体测试对象的昼夜节律测量进行各种统计分析.
- [Full-Text Search Engine](https://github.com/niklr/golem-fulltext-search) - 通过文本文件的搜索引擎服务.

### Data Simulation

- [cadCAD Golem](https://github.com/rogervs/cadcadgolem)  - 用于 cadCAD 的封装包装器，用于将模拟工作负载分派到多个 Golem 节点. 支持 Jupyter 笔记本.
- [Golem Array](https://github.com/johngrantuk/golem-array) - 天线阵列设计和仿真.
- [Limit visualization](https://github.com/vporton/limit-visualization)  - 绘制具有各种限制的图表. 支持不连续图.
- [GolemGraphWavePair](https://github.com/smiley1983/golemGraphWavePair) - 生成图形帧，然后将它们组合成动画.
- [Golemized strong-gravitational-lense](https://github.com/rezahsnz/golemized-strong-gravitational-lense) - 模拟称为引力透镜的物理现象的简单分布式计算黑客.

### Data Optimization

- [Golem or-tools](https://github.com/Doc-Saintly/golem-ortools) - 使用 or-tools 约束编程库来解决问题.
- [No more COFUD](https://github.com/DEUTSCHKLUB/no-more-COFUD) - 计算如何在彼此之间保持 2 米距离的情况下将最多的人放入空间中.
- [Mutta Puffs](https://github.com/DeveloperInProgress/Mutta-Puffs) - 体育联赛调度程序，使用基于人口的模拟退火解决给定团队的巡回锦标赛问题.

### Finance
- [ZKSync .csv export](https://github.com/blue-notes-robot/zksync-csv-export) - 抓取 ZKSync 以在 .csv 文件中生成财务数据.

### Machine Learning
- [DeML-Golem](https://github.com/anshuman73/DeML-Golem) - 分散式机器学习使用联邦学习来组合子步骤模型，它在不同的提供者节点上训练成一个完整的模型.
- [Golem Image Classifier](https://github.com/ControlCplusControlV/Golem-Image-Classifier) - 通过主动服务训练和分类图像.

### Deep Learning
- [Mlg](https://github.com/rezahsnz/mlg) - CNN 预测服务，一种深度学习应用程序，用于分发使用 ImageNet 数据集预训练的流行 CNN.
- [Deepart Golem](https://github.com/echinocacti/deepart_golem) - 通过运行 tensorflow 应用程序，上传您的内容和风格图片，使用分布式计算制作艺术.

### RNG
- [Gandom](https://github.com/rezahsnz/gandom)  - 从提供者那里提取随机流. 支持两种 PRNG，一种基于 Chaos 机器，另一种使用 Sodium.
- [Entropythief](https://github.com/krunch3r76/entropythief) - 利用 linux entropy 源或 Intel 的 RDRAND cpu 指令（受 Gandom 启发），从多个供应商处获取随机熵.

### Password Recovery
- [Golem-JTR](https://github.com/hhio618/golem-jtr) - 运行 John The Ripper 以恢复密码.
- [Yacat](https://handbook.golem.network/requestor-tutorials/task-processing-development/task-example-2-hashcat) - Hashcat 密码恢复步骤.

### DeFi

- [Golem Staking Pool incentivize system for GLM holders](https://github.com/masaun/GLM-stake-pool) - 一个智能合约，为 GLM 代币持有者提供收益农业的机会.
- [Magic-doll](https://github.com/bakaoh/magic-doll)  - Sumer 是一个 DeFi 应用程序，人们可以委托他们的 Splinterland 卡来赚取被动收入. 它的核心是“Kyle”，这是一个 Golem 应用程序，它会执行所有计算来为每场比赛挑选最好的球队.

### User Interfaces

- [Golem UI](https://github.com/shri4net/golem-hackathon-2020) - Yagna 的电子用户界面.

### Miscellaneous

- [Gc__ListOffers](https://github.com/krunch3r76/gc__listoffers) - 使用 GUI 列出 Golem 网络上提供商的报价.
- [Gc__gvmi_hash](https://github.com/krunch3r76/gc__gvmi_hash)  - 重新计算 gvmi 图像文件的哈希值. 解决了丢失先前上传图像的哈希或不确定密钥是否对应于特定图像的问题.
- [gvm-vim](https://github.com/canokaue/gvm-vim) - 用于编译 VIM 编辑器的 Golemized docker 映像.
- [YaJSapi fork with greeting example](https://github.com/rezahsnz/yajsapi)  - 简单的 Node.js 请求者应用程序，欢迎您. 它将一些重要消息写入文件，然后为您下载它，这是请求者应用程序的基本骨架. 查看“示例/问候”.
- [Golem Image Sharpening](https://github.com/visualNext/golem) - 锐化图像的工具.
- [Filterms](https://github.com/krunch3r76/filterms) - 将 Golem 请求者 (yapapi) 列入白名单或列入黑名单的市场策略.
- [golem-bulk-image-handler](https://github.com/figurestudios/golem-bulk-image-handler) - 获取输入图像并使用 Pillow 库以多种不同方式对其进行处理.

## Bounties and Rewards

- [GLM Rewards Program](https://blog.golemproject.net/community-incentives-program/) - 激励开发、支持、内容创建等活动的计划.
- [Gitcoin Bounties](https://gitcoin.co/golemfactory/bounties) - 在 Gitcoin 上托管的一系列开放赏金和黑客马拉松.

## Developer and Requestor Resources

- [Yagna handbook](https://handbook.golem.network/) - 魔像手册，实现名称，Yagna.
- [Yagna Python API docs](https://yapapi.readthedocs.io/) - 重复文档.
- [Releases List](https://github.com/golemfactory/yagna/releases) - Yagna 的 GitHub 版本.
- [Requestor flash tutorial](https://handbook.golem.network/requestor-tutorials/flash-tutorial-of-requestor-development) - 快速开始并在 Golem 上创建您的第一个任务/请求.
- [Yagna tag on Stack Overflow](https://stackoverflow.com/questions/tagged/yagna) - 如果您有一个有趣的问题想要回答，请使用 Yagna 标签.
- [Breakdown of blender.js](https://docs.google.com/document/d/e/2PACX-1vRONc0RRaqImJumYQ3SmILtLo4jiCYgtE0AO3JfpMy0b0-BjAU8TvlIHdtbrs5cDrMbuPFv7khE47MO/pub) - 为开发人员提供的 JS 指南，以更好地了解如何使用 JavaScript API 运行任务.
- [EasyYagnaJS](https://github.com/figurestudios/easy-yagna-js) - 将 Node.js 依赖项直接复制到提供程序，使开发人员不必在其工作流程中使用 Docker.

## Provider Resources

- [Provider Tutorial](https://handbook.golem.network/provider-tutorials/provider-tutorial) - 使用手册开始作为 Golem 网络上的提供者.
- [Provider FAQ](https://github.com/figurestudios/community-golem-docs/blob/main/providing/provider-faq.md) - 社区策划的常见问题和答案列表.
- [Yagna-binaries for aarch64](https://github.com/MarijnStevens/yagna-binaries) - 为 64 位 arm 架构构建，以便能够在 Raspberry Pi 等系统上作为提供程序运行.
- [Automatically update provider node prices](https://gist.github.com/sv3t0sl4v/28f896752edc9e20347ffc6d8cefe74c) - 检查 stats.golem.network 上价格中位数并更新与价格相关的提供者节点上的所有 3 个值的脚本.
- [Golem Price Updater](https://github.com/jedbrooke/golem-price-updater) - 根据 GLM 的当前价格自动调整您的 Golem 节点的价格.

### Monitoring

- [Golem Provider dashboard](https://github.com/vciancio/golem-dashboard) - ReactJS 仪表板可快速从您的提供程序节点收集状态，而无需通过 SSH 连接到它们.
- [Golem Provider dashboard backend / GolemBar](https://github.com/vciancio/golem-node-server) - Flask 后端，它从提供者那里收集数据，然后与上面的仪表板项目一起使用.

### Provisioning

- [Ansible ya_provider](https://galaxy.ansible.com/golemfactory/ya_provider) - Ansible 角色自动部署 Golem 提供程序，所需配置最少.
- [WSL](https://github.com/r34x/WSL)  - 允许 Windows 用户在 Linux 的 Windows 子系统中运行 Golem. 消除需要使用虚拟机的 Windows 用户的要求.
- [Golem Provider Terraform](https://github.com/nemani/golem-provider-terraform) - Terraform script to automatically deploy a Golem Provider on a cloud provider and setup monitoring using prometheus.
- [Automatic Golem](https://github.com/r34x/Automatic-Golem) - 使用简单的说明和日志设置 Golem 提供程序，指导您完成整个过程.
- [Golem Provider Node](https://github.com/alexandre-abrioux/golem-node) - Docker 版本的节点可帮助您快速开始作为 Docker 容器中的提供者运行.
- [Golem Provider node](https://github.com/blue-notes-robot/golem-node) - 上面的 Alxexandre-abrioux 项目的分支，它允许从 ENV 变量动态生成配置文件并指定您想要生成多少个副本.
- [Scalable golem provider](https://github.com/cryptobench/scaleable-golem-provider) - 使用 Docker 生成 x 数量的提供者.

## Learning Resources

### Presentations and Workshop Material

- [Golem: Architecture, SDKs and tips with Jakub Mazurek at 0xHack](https://youtu.be/1UoZWC9XI2g) - 现场研讨会深入探讨任何具有 Python 或 JS 编码经验的开发人员如何开始构建在 Golem 上运行的应用程序.
- [Golem: Growing an ecosystem the Golem way with María Paula Fernández at 0xHack](https://youtu.be/FmrdyU90NVE) - Golem 作为一个项目的高级概述和介绍.
- [Golem Workshop at H3LLO Decentralization](https://gist.github.com/zakaprov/5366bffa49b3c116748bf9b5b73c602c) - 包含实时编码黑客马拉松研讨会和相关资源的资源列表，以帮助开发人员了解和请求 Golem.
- [Mainnet Requestor quickstart Walk-through](https://youtu.be/GcdTq3i_wdY) - 使用 Yagna Python API 在 Golem 网络测试网和主网上获取请求的请求者快速入门手册指南的视频演练.
- [Mainnet Provider quickstart Walk-through](https://youtu.be/RITdKtEOV_E) - 提供者手册指南的视频演练，开始在 Golem 网络中共享计算资源.

### Unraveling Golem's The Next Milestone Blog Series

- [Unraveling Golem's The Next Milestone](https://blog.golemproject.net/next-milestone) - 介绍 Golem 的 Yagna 实现.
- [Unraveling Golem's The Next Milestone, Part II](https://blog.golemproject.net/next-milestone-part-ii/) - 构成 Golem，Yagna 新实施基础的基本建筑概念.
- [Unraveling Golem's The Next Milestone, Part III](https://blog.golemproject.net/next-milestone-part-iii/) - Golem 参考架构的元素，并说明它们如何交互以形成一个工作生态系统，即 Golem 网络.

### GitHub Digest Blog Series

- [Golem GitHub Digest #1](https://blog.golemproject.net/golem-github-digest-1/) - 了解 Golem 存储库.
- [Golem GitHub Digest #2](https://blog.golemproject.net/golem-github-digest-2/) - 潜入 Golem 存储库.
- [Golem GitHub Digest #3](https://blog.golemproject.net/golem-github-digest-3/) - 深入研究 Golem 存储库的拉取请求.
- [Golem GitHub Digest #4](https://blog.golemproject.net/golem-github-digest-4/) - 深入了解 Golem 存储库中的最新版本.
- [Golem GitHub Digest #5](https://blog.golemproject.net/golem-github-digest-5/) - 潜入 Golem alpha 测试网.
- [Golem GitHub Digest #6](https://blog.golemproject.net/golem-github-digest-6/) - 新交所 Golem 的概念验证.
- [Golem GitHub Digest #7](https://blog.golemproject.net/golem-github-digest-7/) - Golem 市场的去中心化.
- [Golem GitHub Digest #8](https://blog.golemproject.net/golem-github-digest-8/) - 令人敬畏的魔像和 Alpha 3 的后续步骤.
- [Golem GitHub Digest #9](https://blog.golemproject.net/golem-github-digest-9/) - AMD 提供商支持、网络指标和改进的提案处理.
- [Golem GitHub Digest #10](https://blog.golemproject.net/golem-github-digest-10/) - 来自社区反馈的改进.
- [Golem GitHub Digest #11](https://blog.golemproject.net/golem-github-digest-11/) - 简单的日志收集.
- [Golem GitHub Digest #12](https://blog.golemproject.net/golem-github-digest-12/) - 我们在 MAINNET 上并收集反馈.
- [Golem GitHub Digest #13](https://blog.golemproject.net/golem-github-digest-13/) - 在 Golem 社区的帮助下进步更快.
- [Golem GitHub Digest #14](https://blog.golemproject.net/golem-github-digest-14/) - 迈向下一个主要版本.
- [Golem GitHub Digest #15](https://blog.golemproject.net/golem-github-digest-15/) - 令人敬畏的哥特式改进并迈向 Beta 3.
- [Golem GitHub Digest #16](https://blog.golemproject.net/golem-github-digest-16/) - 请求者的 VPN、ARM 二进制文件和自定义使用计数器.


## Community

- [Golem Network Discussion Group](https://t.me/GolemProject) - 社区驱动的电报频道.
- [Reddit Golem Stat Bot](https://github.com/figurestudios/golem-stat-bot) - 删除 /r/GolemProject 上的 Reddit 帖子，并在找到特定关键字/命令时回复.
- [Golem God](https://github.com/Shreyas-Dev-ITB/Golem-God) - 发放“机器人币”进行活动，并让用户在有足够的情况下兑换和提取代币.

## Contributing

欢迎向 Awesome Golem 提出拉取请求和问题建议！ 请阅读 [contributing](https://github.com/golemfactory/awesome-golem/blob/master/contributing.md) 提交 PR 前的指南.
