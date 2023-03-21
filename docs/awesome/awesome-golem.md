<div class="github-widget" data-repo="golemfactory/awesome-golem"></div>
## Awesome Golem [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![awesome-lint](https://github.com/golemfactory/awesome-golem/actions/workflows/main.yml/badge.svg)](https://github.com/golemfactory/awesome-golem/actions/workflows/main.yml/badge.svg)

[<img src="https://raw.githubusercontent.com/golemfactory/awesome-golem/master/golem-logo.svg?sanitize=true" align="right" width="150">](https://golem.network/)

> Welcome to **Awesome Golem**, a community-curated list of resources, links, projects, tools and applications on Golem!

 Golem 的用户以 Rust 实现 Yagna 的形式运行参考实现. 用户共同组成了 Golem 网络，这是一个计算资源的 P2P 市场，个人可以在其中充当两个非排他性角色之一； 出售闲置资源的提供者，或购买资源以运行任务的请求者.



## Golem

- [Golem Network Platform](https://www.golem.network/platform) - 在 Golem Network 官方网站上学习 Golem 平台.
- [Golem Factory GitHub](https://github.com/golemfactory) - 在哪里可以找到 Golem 所有东西的开源代码.
- [Yagna GitHub](https://github.com/golemfactory/yagna) - Golem 的官方 Rust 实现.
- [Golem Community Chat](https://chat.golem.network/) - 加入社区和团队在 Discord 上公开讨论.
- [Reddit](https://reddit.com/r/GolemProject) - Reddit 平台上的 Golem Network 讨论.
- [Twitter](https://twitter.com/golemproject) - Golem 项目 Twitter.
- [Blog](http://blog.golemproject.net/) - 官方博客，您可以在其中找到有关公告、摘要和更新的最可靠信息.

## Thorg

- [About Thorg](https://www.thorg.io/about) - 了解 Thorg 矿工的工作.
- [Thorg Usage](https://www.thorg.io/usage) - 了解 Thorg 的深度.
- [Twitter](https://twitter.com/minewiththorg) - Thorg 的官方推特.

## Network Statistics

- [Golem Network Stats](https://stats.golem.network) - Golem 网络中的统计跟踪任务和供应商资源利用率.
- [Golem Stats backend](https://github.com/cryptobench/golem-stats-backend) - Golem 网络统计页面的后端，包括 API 端点 URL.
- [Stats API Documentation](https://docs.stats.golem.network/) - Golem 网络统计页面用于显示其数据的 API 端点.

## Apps

- [Golem SLATE](https://golem-slate.xyz/)  - 托管代码笔 SPA，用于编写请求者脚本以让网络计算工作. 利用 dockerized yagna 环境在后台与 Golem 网络通信.
- [Chess On Golem](https://chessongolem.app/) - 托管国际象棋应用程序，利用 Stockfish 开源国际象棋引擎与网络提供商对战.
- [Go le' Machin](https://github.com/DEUTSCHKLUB/go-le-m) - 基于 Web 的批量图片编辑器，允许用户上传多张图片并对其应用批量操作.

### Docker

- [Golem Requestor Node](https://github.com/DerekJarvis/general-golem)  - Dockerized 请求者环境. 传入 py 脚本，它会设置守护进程并运行它.

### Testing

- [Golem Test Harness (Goth)](https://github.com/golemfactory/goth) - 旨在加快您的开发过程并使应用程序创建者更愉快的工具.
- [Golem-afl](https://github.com/sladecek/golem-afl) - An experimental test-fuzzing framework. Assists in finding security holes.
- [Golem Cargo Test](https://github.com/sladecek/golem_cargo_test) - 用于 Rust 项目的自适应分布式测试执行器.
- [Golem CI](https://github.com/hhio618/golem-ci) - 分散的任务管道.
- [Golem SLATE](https://github.com/deutschklub/golem-slate) - 上述应用程序部分中描述的 Golem SLATE 的开源存储库.
- [ThorgPress](https://github.com/figurestudios/thorgpress) - 一种对供应商进行基准测试并揭示其超越市场可见能力的真实能力的工具.

### VPN

- [Yagna httpx client](https://github.com/golemfactory/ya-httpx-client/tree/johny-b/vpn) - Yagna 上的 VPN 使用演示了与基于提供商的 HTTP 服务器的通信，就像您与任何其他 HTTP 服务器通信的方式一样.
- [Golem Provider with network access](https://github.com/jedbrooke/golem-network-requestor) - 充当运行提供者的 http 代理的请求者，允许他们访问更广泛的互联网.

### Games

- [Golem Sudoku](https://github.com/Dodecane/golem-sudoku) - 大小不同的数独游戏.
- [HSOG-requester](https://github.com/ChrisHelmsC/hsog-requestor) - 通过运行大量模拟游戏来帮助炉石社区设计和构建套牌.
- [ChessOnGolem](https://github.com/broadcastmonkey/ChessOnGolem)  - 第一个应用程序部分中描述的国际象棋开源存储库. 包括用于 2 个 AI 通过 Golem 后端相互对战的 React 前端.
- [Golem Fleet Battle Simulator](https://github.com/UnfortuN8/Golem-Fleet-Battle-Simulator)  - 用于计算两个对立星舰舰队之间战斗结果的系统. 在 iOS 游戏 Rock Paper Frigate 中用于确定 PvP 舰队战斗的结果.

### CLI Tools

- [Golem Completion Engine](https://github.com/krunch3r76/gc__enhanced_completion) - 增强的 bash 完成引擎，通过为 golemsp 和 yagna 提供上下文帮助来扩展内置完成.
- [Golocity](https://github.com/davidstyers/golocity) - 只需两个命令即可在 Golem 网络上构建和部署您的 dockerized 应用程序.
- [gc__push_image](https://github.com/figurestudios/gc__push_image) - 将 GVMI 图像发布到 Skynet 的 CLI 工具，使用户能够在不自托管/放弃控制的情况下更改 image_url.

### Video Transcoding and Editing

- [Golem Network Video Transcoder](https://github.com/Doc-Saintly/golem-video)  - 用于转码视频的示例应用程序. 选择您的转码配置文件，然后上传您的视频.
- [Golem Transcoding requestor](https://github.com/Edhendil/golem-transcoding) - 基于 React + Spring 的 webapp 接受视频文件作为输入并将这些文件转码为不同的格式.
- [Golem Auto Editor](https://github.com/jedbrooke/golem-auto-editor) - 运行自动编辑器自动执行一些视频编辑功能，将视频处理卸载到 Golem.

### Data Analysis
- [Coacervate](https://github.com/pryce-turner/coacervate/)  - Coacervate 是一种免费的开源公共产品，可让您在成本极低的全球超级计算机上轻松运行基因组分析； 使获得开展开创性研究所需的知识和基础设施的途径民主化.
- [Flan](https://github.com/nestorbonilla/flan) - 为企业家提供的工具，提供对全球数百万贸易价值记录的定制分析，为他们提供关于他们需要更多关注哪些部门的大胆指导.
- [Golem Lorenz-attractor](https://github.com/hhio618/golem-lorenz-attractor) - 一个由三个耦合的一阶非线性微分方程组成的系统，用于描述粒子随时间的轨迹.
- [Golem Geomandel](https://github.com/Edhendil/golem-geomandel) - 用于生成以单个点为中心的 Mandelbrot 图像序列的 Python 脚本，并且每个图像的缩放比例都在增加.
- [Golem COVID](https://github.com/iRhonin/golem-covid)  - 创建与 COVID 相关的每百万新死亡人数的图像. 生成所有图像后，它将收集它们并创建一个 gif.
- [Golem Parallel Matplotlib](https://github.com/CoeJoder/golem-parallel-matplotlib) - 对人类测试对象的昼夜节律测量进行了各种统计分析.
- [Full-Text Search Engine](https://github.com/niklr/golem-fulltext-search) - 通过文本文件的搜索引擎服务.

### Data Simulation

- [cadCAD Golem](https://github.com/rogervs/cadcadgolem)  - 用于 cadCAD 的包装器，用于将模拟工作负载分派给多个 Golem 节点. 支持 Jupyter 笔记本.
- [Golem Array](https://github.com/johngrantuk/golem-array) - 天线阵列设计和仿真.
- [Limit visualization](https://github.com/vporton/limit-visualization)  - 绘制具有各种限制的图表. 支持不连续图.
- [GolemGraphWavePair](https://github.com/smiley1983/golemGraphWavePair) - 生成图形帧，然后将它们组合成动画.
- [Golemized strong-gravitational-lense](https://github.com/rezahsnz/golemized-strong-gravitational-lense) - 模拟称为引力透镜的物理现象的简单分布式计算黑客.

### Data Optimization

- [Golem or-tools](https://github.com/Doc-Saintly/golem-ortools) - 使用 or-tools 约束编程库来解决问题.
- [No more COFUD](https://github.com/DEUTSCHKLUB/no-more-COFUD) - 计算如何让最多的人进入一个空间，同时保持彼此之间 2 米的距离.
- [Mutta Puffs](https://github.com/DeveloperInProgress/Mutta-Puffs) - 体育联盟调度程序，使用基于群体的模拟退火解决一组给定团队的旅行锦标赛问题.

### Finance
- [ZKSync .csv export](https://github.com/blue-notes-robot/zksync-csv-export) - 抓取 ZKSync 以在 .csv 文件中生成财务数据.

### Machine Learning
- [DeML-Golem](https://github.com/anshuman73/DeML-Golem) - 分散式机器学习使用联合学习来组合子步骤模型，它在不同的提供者节点上训练成一个完整的模型.
- [Golem Image Classifier](https://github.com/ControlCplusControlV/Golem-Image-Classifier) - 通过主动服务对图像进行训练和分类.

### Deep Learning
- [Mlg](https://github.com/rezahsnz/mlg) - CNN 预测服务，一种深度学习应用程序，可分发使用 ImageNet 数据集预训练的流行 CNN.
- [Deepart Golem](https://github.com/echinocacti/deepart_golem) - 通过运行 tensorflow 应用程序、上传您的内容和风格图片，使用分布式计算制作艺术品.

### RNG
- [Gandom](https://github.com/rezahsnz/gandom)  - 从提供商那里提取随机流. 支持两种 PRNG，一种基于 Chaos 机器，另一种使用 Sodium.
- [Entropythief](https://github.com/krunch3r76/entropythief) - 使用 linux 熵源或 Intel 的 RDRAND cpu 指令（受 Gandom 启发）以窃取速率从多个供应商处获取随机熵.

### Password Recovery
- [Golem-JTR](https://github.com/hhio618/golem-jtr) - 运行 John The Ripper 来恢复密码.
- [Yacat](https://handbook.golem.network/requestor-tutorials/task-processing-development/task-example-2-hashcat) - 逐步恢复 Hashcat 密码.

### DeFi

- [Golem Staking Pool incentivize system for GLM holders](https://github.com/masaun/GLM-stake-pool) - 为 GLM 代币持有者提供收益农业机会的智能合约.
- [Magic-doll](https://github.com/bakaoh/magic-doll)  - Sumer 是一个 DeFi 应用程序，人们可以委托他们的 Splinterland 卡来赚取被动收入. 它的核心是“Kyle”，这是一个 Golem 应用程序，可以进行所有计算以挑选出每场比赛的最佳球队.

### User Interfaces

- [Golem UI](https://github.com/shri4net/golem-hackathon-2020) - Yagna 的电子用户界面.

### Miscellaneous

- [Gc__ListOffers](https://github.com/krunch3r76/gc__listoffers) - 使用 GUI 列出 Golem 网络上提供者的报价.
- [Gc__gvmi_hash](https://github.com/krunch3r76/gc__gvmi_hash)  - 重新计算 gvmi 图像文件的哈希值. 解决了丢失先前上传图像的哈希值或者不确定密钥是否对应于特定图像的问题.
- [gvm-vim](https://github.com/canokaue/gvm-vim) - 用于编译 VIM 编辑器的 Golemized docker 图像.
- [YaJSapi fork with greeting example](https://github.com/rezahsnz/yajsapi)  - 向您致意的简单 Node.js 请求程序. 它将一些重要消息写入文件，然后为您下载，这是请求程序应用程序的基本骨架. 查看 `examples/greetings`.
- [Golem Image Sharpening](https://github.com/visualNext/golem) - 锐化图像的工具.
- [Filterms](https://github.com/krunch3r76/filterms) - 将 Golem 请求者 (yapapi) 列入白名单或黑名单的市场策略.
- [golem-bulk-image-handler](https://github.com/figurestudios/golem-bulk-image-handler) - 获取输入图像并使用 Pillow 库以多种不同方式处理它.

## Bounties and Rewards

- [GLM Rewards Program](https://blog.golemproject.net/community-incentives-program/) - 一个激励开发、支持、内容创建等活动的计划.
- [Gitcoin Bounties](https://gitcoin.co/golemfactory/bounties) - 在 Gitcoin 上托管的一系列公开赏金和黑客马拉松.

## Developer and Requestor Resources

- [Yagna handbook](https://handbook.golem.network/) - Golem 手册，实现名称，Yagna.
- [Yagna Python API docs](https://yapapi.readthedocs.io/) - 重复文档.
- [Releases List](https://github.com/golemfactory/yagna/releases) - Yagna 的 GitHub 版本.
- [Requestor flash tutorial](https://handbook.golem.network/requestor-tutorials/flash-tutorial-of-requestor-development) - 快速开始并在 Golem 上创建您的第一个任务/请求.
- [Yagna tag on Stack Overflow](https://stackoverflow.com/questions/tagged/yagna) - 如果您有想要回答的有趣问题，请使用 Yagna 标签.
- [Breakdown of blender.js](https://docs.google.com/document/d/e/2PACX-1vRONc0RRaqImJumYQ3SmILtLo4jiCYgtE0AO3JfpMy0b0-BjAU8TvlIHdtbrs5cDrMbuPFv7khE47MO/pub) - 开发人员的 JS 指南可以更好地了解如何使用 JavaScript API 运行任务.
- [EasyYagnaJS](https://github.com/figurestudios/easy-yagna-js) - 将 Node.js 依赖项直接复制到提供程序，使开发人员不必在其工作流程中使用 Docker.
- [push-gvmi](https://github.com/figurestudios/push-gvmi) - 自动构建 GVMI 图像并将其上传到 Golem 的 GitHub 操作，以及一种为本地使用抓取最新哈希的方法.

## Provider Resources

- [Provider Tutorial](https://handbook.golem.network/provider-tutorials/provider-tutorial) - 使用手册开始作为 Golem 网络上的提供者.
- [Provider FAQ](https://github.com/figurestudios/community-golem-docs/blob/main/providing/provider-faq.md) - 社区精选的常见问题和答案列表.
- [Yagna-binaries for aarch64](https://github.com/MarijnStevens/yagna-binaries) - 为 64 位 arm 架构构建，以便能够在 Raspberry Pi 等系统上作为提供程序运行.
- [Automatically update provider node prices](https://gist.github.com/sv3t0sl4v/28f896752edc9e20347ffc6d8cefe74c) - 检查 stats.golem.network 上的价格中位数并更新提供者节点上与价格相关的所有 3 个值的脚本.
- [Golem Price Updater](https://github.com/jedbrooke/golem-price-updater) - 根据 GLM 的当前价格自动调整您的 Golem 节点的价格.

### Monitoring

- [Golem Provider dashboard](https://github.com/vciancio/golem-dashboard) - ReactJS 仪表板可以快速从您的提供者节点收集状态，而无需通过 SSH 进入它们.
- [Golem Provider dashboard backend / GolemBar](https://github.com/vciancio/golem-node-server) - Flask 后端从提供程序收集数据，然后与上面的仪表板项目一起使用.

### Provisioning

- [Ansible ya_provider](https://galaxy.ansible.com/golemfactory/ya_provider) - 以最少的配置自动部署 Golem 提供程序的 Ansible 角色.
- [WSL](https://github.com/r34x/WSL)  - 允许 Windows 用户在适用于 Linux 的 Windows 子系统中运行 Golem. 删除 Windows 用户需要使用虚拟机的要求.
- [Golem Provider Terraform](https://github.com/nemani/golem-provider-terraform) - 用于在云提供商上自动部署 Golem 提供商并使用普罗米修斯设置监控的 Terraform 脚本.
- [Automatic Golem](https://github.com/r34x/Automatic-Golem) - 使用简单的说明和日志设置一个 Golem 提供者，指导您完成整个过程.
- [Golem Provider Node](https://github.com/alexandre-abrioux/golem-node) - 节点的 Docker 版本可帮助您快速开始在 Docker 容器中作为提供者运行.
- [Golem Provider node](https://github.com/blue-notes-robot/golem-node) - 上面的 Alxexandre-abrioux 项目的分支允许从 ENV 变量动态生成配置文件并指定你想要生成多少个副本.
- [Scalable golem provider](https://github.com/cryptobench/scaleable-golem-provider) - 使用 Docker 产生 x 数量的供应商.

## Learning Resources

### Presentations and Workshop Material

- [Golem: Architecture, SDKs and tips with Jakub Mazurek at 0xHack](https://youtu.be/1UoZWC9XI2g) - 现场研讨会深入探讨任何具有 Python 或 JS 编码经验的开发人员如何开始构建在 Golem 上运行的应用程序.
- [Golem: Growing an ecosystem the Golem way with María Paula Fernández at 0xHack](https://youtu.be/FmrdyU90NVE) - 作为项目对 Golem 进行高级概述和介绍.
- [Golem Workshop at H3LLO Decentralization](https://gist.github.com/zakaprov/5366bffa49b3c116748bf9b5b73c602c) - 包含实时编码黑客马拉松研讨会和相关资源的资源列表，以帮助开发人员了解和请求 Golem.
- [Mainnet Requestor quickstart Walk-through](https://youtu.be/GcdTq3i_wdY) - 请求者快速入门手册指南的视频演练，以使用 Yagna Python API 在 Golem 网络测试网和主网上获取请求.
- [Mainnet Provider quickstart Walk-through](https://youtu.be/RITdKtEOV_E) - 供应商手册指南的视频演练，开始共享 Golem 网络的计算资源.

### Unraveling Golem's The Next Milestone Blog Series

- [Unraveling Golem's The Next Milestone](https://blog.golemproject.net/next-milestone) - Golem 的 Yagna 实现简介.
- [Unraveling Golem's The Next Milestone, Part II](https://blog.golemproject.net/next-milestone-part-ii/) - 构成 Golem Yagna 新实现基础的基本架构概念.
- [Unraveling Golem's The Next Milestone, Part III](https://blog.golemproject.net/next-milestone-part-iii/) - Golem 参考架构的元素，并说明它们如何相互作用以形成一个工作生态系统，即 Golem 网络.

### GitHub Digest Blog Series

- [Golem GitHub Digest #1](https://blog.golemproject.net/golem-github-digest-1/) - 了解 Golem 存储库.
- [Golem GitHub Digest #2](https://blog.golemproject.net/golem-github-digest-2/) - 潜入魔像库.
- [Golem GitHub Digest #3](https://blog.golemproject.net/golem-github-digest-3/) - 深入研究 Golem 存储库的 Pull Requests.
- [Golem GitHub Digest #4](https://blog.golemproject.net/golem-github-digest-4/) - 深入了解 Golem 存储库中的最新版本.
- [Golem GitHub Digest #5](https://blog.golemproject.net/golem-github-digest-5/) - 深入了解 Golem alpha 测试网.
- [Golem GitHub Digest #6](https://blog.golemproject.net/golem-github-digest-6/) - Golem 的 SGX 概念验证.
- [Golem GitHub Digest #7](https://blog.golemproject.net/golem-github-digest-7/) - Golem 市场的去中心化.
- [Golem GitHub Digest #8](https://blog.golemproject.net/golem-github-digest-8/) - 很棒的魔像和 Alpha 3 的后续步骤.
- [Golem GitHub Digest #9](https://blog.golemproject.net/golem-github-digest-9/) - AMD 提供商支持、网络指标和改进的提案处理.
- [Golem GitHub Digest #10](https://blog.golemproject.net/golem-github-digest-10/) - 社区反馈的改进.
- [Golem GitHub Digest #11](https://blog.golemproject.net/golem-github-digest-11/) - 简单的日志收集.
- [Golem GitHub Digest #12](https://blog.golemproject.net/golem-github-digest-12/) - 我们在 MAINNET 上并收集反馈.
- [Golem GitHub Digest #13](https://blog.golemproject.net/golem-github-digest-13/) - 在 Golem 社区的帮助下进步更快.
- [Golem GitHub Digest #14](https://blog.golemproject.net/golem-github-digest-14/) - 迈向下一个主要版本.
- [Golem GitHub Digest #15](https://blog.golemproject.net/golem-github-digest-15/) - 很棒的哥特式改进和 Beta 3.
- [Golem GitHub Digest #16](https://blog.golemproject.net/golem-github-digest-16/) - VPN、请求者的 ARM 二进制文件和自定义使用计数器.


## Community

- [Golem Network Discussion Group](https://t.me/GolemProject) - 社区驱动的电报频道.
- [Reddit Golem Stat Bot](https://github.com/figurestudios/golem-stat-bot) - 抓取 /r/GolemProject 上的 Reddit 帖子，并在找到特定关键字/命令时回复.
- [Golem God](https://github.com/Shreyas-Dev-ITB/Golem-God) - 为活动发放“机器人币”，让用户在足够时兑换和提现为代币.

## Contributing

欢迎向 Awesome Golem 提出请求和提出建议问题！ 请阅读 [contributing](https://github.com/golemfactory/awesome-golem/blob/master/contributing.md) 提交 PR 之前的指南.
