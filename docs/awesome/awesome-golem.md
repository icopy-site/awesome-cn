<div class="github-widget" data-repo="golemfactory/awesome-golem"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Golem [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![awesome-lint](https://github.com/golemfactory/awesome-golem/actions/workflows/main.yml/badge.svg)](https://github.com/golemfactory/awesome-golem/actions/workflows/main.yml/badge.svg)

[<img src="https://raw.githubusercontent.com/golemfactory/awesome-golem/master/golem-logo.svg?sanitize=true" align="right" width="150">](https://golem.network/)

> Welcome to **Awesome Golem**, a community-curated list of resources, links, projects, tools and applications on Golem!

 Golem 的用户以 Rust 实现 Yagna 的形式运行参考实现. 用户共同组成了 Golem 网络，这是一个计算资源的 P2P 市场，个人可以在其中充当两个非排他性角色之一； 出售闲置资源的提供者，或购买资源以运行任务的请求者.



## Golem

- [Golem Network Platform](https://www.golem.network/platform) - Learn the Golem platform on the official Golem Network website.
- [Golem Factory GitHub](https://github.com/golemfactory) - Where you can find the open source code of all things Golem.
- [Yagna GitHub](https://github.com/golemfactory/yagna) - The official Rust implementation of Golem.
- [Golem Community Chat](https://chat.golem.network/) - 加入社区和团队在 Discord 上公开讨论.
- [Reddit](https://reddit.com/r/GolemProject) - Golem Network discussion on the Reddit platform.
- [Twitter](https://twitter.com/golemproject) - The Golem Project Twitter.
- [Blog](http://blog.golemproject.net/) - 官方博客，您可以在其中找到有关公告、摘要和更新的最可靠信息.

## Thorg

- [About Thorg](https://www.thorg.io/about) - Learn what the Thorg miner does.
- [Thorg Usage](https://www.thorg.io/usage) - 了解 Thorg 的深处.
- [Twitter](https://twitter.com/minewiththorg) - The official Twitter of Thorg.

## Network Statistics

- [Golem Network Stats](https://stats.golem.network) - Golem 网络中的统计跟踪任务和提供者资源利用率.
- [Golem Stats backend](https://github.com/cryptobench/golem-stats-backend) - Golem 网络统计页面的后端，包括 API 端点 URL。
- [Stats API Documentation](https://docs.stats.golem.network/) - API endpoints that the Golem Network Stats page uses to display its data.

## Apps

- [Golem SLATE](https://golem-slate.xyz/) - Hosted code pen SPA for writing a requester script to have work computed by the network. Utilizes dockerized yagna environments to communicate with the Golem Network in the background.
- [Chess On Golem](https://chessongolem.app/) - Hosted Chess app to play against the providers of the network utilizing the Stockfish open source Chess engine.
- [Go le' Machin](https://github.com/DEUTSCHKLUB/go-le-m) - 基于 Web 的批量图像编辑器，允许用户上传多个图像并对它们应用批量操作.

### Docker

- [Golem Requestor Node](https://github.com/DerekJarvis/general-golem) - Dockerized requestor environment. Pass in the py script, it sets up the daemon and runs it.

### Testing

- [Golem Test Harness (Goth)](https://github.com/golemfactory/goth) - Tool with the purpose of speeding up your development process and making it more enjoyable for application creators.
- [Golem-afl](https://github.com/sladecek/golem-afl)  - 一个实验性的测试模糊框架. 协助发现安全漏洞.
- [Golem Cargo Test](https://github.com/sladecek/golem_cargo_test) - 适用于 Rust 项目的自适应分布式测试执行器.
- [Golem CI](https://github.com/hhio618/golem-ci) - 分散的任务管道.
- [Golem SLATE](https://github.com/deutschklub/golem-slate) - 上述应用部分中描述的 Golem SLATE 的开源存储库.

### VPN

- [Yagna httpx client](https://github.com/golemfactory/ya-httpx-client/tree/johny-b/vpn) - VPN usage on Yagna demonstrating communication with a provider-based HTTP server the way you communicate with any other HTTP server.
- [Golem Provider with network access](https://github.com/jedbrooke/golem-network-requestor) - A requstor that acts as a http proxy for running providers, allowing them to access the wider internet.

### Games

- [Golem Sudoku](https://github.com/Dodecane/golem-sudoku) - Game of Sudoku with size variants.
- [HSOG-requester](https://github.com/ChrisHelmsC/hsog-requestor) - 通过运行大量模拟游戏，帮助炉石社区设计和构建套牌.
- [ChessOnGolem](https://github.com/broadcastmonkey/ChessOnGolem)  - 第一个应用程序部分中描述的国际象棋开源存储库. 包括 2 个 AI 通过 Golem 后端相互对抗的 React 前端.
- [Golem Fleet Battle Simulator](https://github.com/UnfortuN8/Golem-Fleet-Battle-Simulator) - System for calculating the results of a battle between two opposing starship fleets. Used in the iOS game Rock Paper Frigate to determine the result of PvP fleet battles.

### CLI Tools

- [Golem Completion Engine](https://github.com/krunch3r76/gc__enhanced_completion) - 增强的 bash 补全引擎，通过为 golemsp 和 yagna 提供上下文帮助来扩展内置补全.
- [Golocity](https://github.com/davidstyers/golocity) - Build and deploy your dockerized applications on the Golem Network in just two commands.

### Video Transcoding and Editing

- [Golem Network Video Transcoder](https://github.com/Doc-Saintly/golem-video)  - 用于转码视频的示例应用程序. 选择您的转码配置文件，然后上传您的视频.
- [Golem Transcoding requestor](https://github.com/Edhendil/golem-transcoding) - React + Spring based webapp accepting video files as input and transcoding these files into different formats.
- [Golem Auto Editor](https://github.com/jedbrooke/golem-auto-editor) - Run Auto-Editor to automatically perform some video editing functions, offload the video processing to Golem.

### Data Analysis

- [Flan](https://github.com/nestorbonilla/flan) - 为企业家提供对全球数百万条贸易价值记录进行定制分析的工具，为他们提供有关需要更多关注的领域的大胆指导.
- [Golem Lorenz-attractor](https://github.com/hhio618/golem-lorenz-attractor) - A system of three coupled, first-order, nonlinear differential equations which describe the trajectory of a particle through time.
- [Golem Geomandel](https://github.com/Edhendil/golem-geomandel) - Python script for generating sequences of Mandelbrot images centered on a single point and with zoom increasing in each image.
- [Golem COVID](https://github.com/iRhonin/golem-covid)  - 创建与 COVID 相关的每百万新死亡人数的图像. 生成所有图像后，它将收集它们并创建一个 gif.
- [Golem Parallel Matplotlib](https://github.com/CoeJoder/golem-parallel-matplotlib) - 对人体测试对象的昼夜节律测量进行各种统计分析.
- [Full-Text Search Engine](https://github.com/niklr/golem-fulltext-search) - 通过文本文件的搜索引擎服务.

### Data Simulation

- [cadCAD Golem](https://github.com/rogervs/cadcadgolem)  - 用于 cadCAD 的封装包装器，用于将模拟工作负载分派到多个 Golem 节点. 支持 Jupyter 笔记本.
- [Golem Array](https://github.com/johngrantuk/golem-array) - 天线阵列设计和仿真.
- [Limit visualization](https://github.com/vporton/limit-visualization) - Plots graphs with various limits. Supports discontinous graphs.
- [GolemGraphWavePair](https://github.com/smiley1983/golemGraphWavePair) - 生成图形帧，然后将它们组合成动画.
- [Golemized strong-gravitational-lense](https://github.com/rezahsnz/golemized-strong-gravitational-lense) - 模拟称为引力透镜的物理现象的简单分布式计算黑客.

### Data Optimization

- [Golem or-tools](https://github.com/Doc-Saintly/golem-ortools) - Uses the or-tools Constraint Programming library to solve problems.
- [No more COFUD](https://github.com/DEUTSCHKLUB/no-more-COFUD) - Calculates how to fit the most people into a space while keeping 2 meters distance between each other.
- [Mutta Puffs](https://github.com/DeveloperInProgress/Mutta-Puffs) - 体育联赛调度程序，使用基于人口的模拟退火解决给定团队的巡回锦标赛问题.

### Finance
- [ZKSync .csv export](https://github.com/blue-notes-robot/zksync-csv-export) - Scrapes ZKSync to generate financial data in a .csv file.

### Machine Learning
- [DeML-Golem](https://github.com/anshuman73/DeML-Golem) - Decentralised Machine Learning using Federated Learning to combine the sub-step models, it trains on different provider nodes into a full fleged model.
- [Golem Image Classifier](https://github.com/ControlCplusControlV/Golem-Image-Classifier) - Train and classify images through an active service.

### Deep Learning
- [Mlg](https://github.com/rezahsnz/mlg) - CNN 预测服务，一种深度学习应用程序，用于分发使用 ImageNet 数据集预训练的流行 CNN.
- [Deepart Golem](https://github.com/echinocacti/deepart_golem) - Makes art using distributed computing by running a tensorflow app, uploading your content and style picture.

### RNG
- [Gandom](https://github.com/rezahsnz/gandom) - Extract random streams from providers. Supports two PRNGs, one based on Chaos machines and the other that makes use of Sodium.
- [Entropythief](https://github.com/krunch3r76/entropythief) - 利用 linux entropy 源或 Intel 的 RDRAND cpu 指令（受 Gandom 启发），从多个供应商处获取随机熵.

### Password Recovery
- [Golem-JTR](https://github.com/hhio618/golem-jtr) - 运行 John The Ripper 以恢复密码.
- [Yacat](https://handbook.golem.network/requestor-tutorials/task-processing-development/task-example-2-hashcat) - Hashcat 密码恢复步骤.

### DeFi

- [Golem Staking Pool incentivize system for GLM holders](https://github.com/masaun/GLM-stake-pool) - 一个智能合约，为 GLM 代币持有者提供收益农业的机会.
- [Magic-doll](https://github.com/bakaoh/magic-doll)  - Sumer 是一个 DeFi 应用程序，人们可以委托他们的 Splinterland 卡来赚取被动收入. 它的核心是“Kyle”，这是一个 Golem 应用程序，它会执行所有计算来为每场比赛挑选最好的球队.

### User Interfaces

- [Golem UI](https://github.com/shri4net/golem-hackathon-2020) - Electron user interface for Yagna.

### Miscellaneous

- [Gc__ListOffers](https://github.com/krunch3r76/gc__listoffers) - 使用 GUI 列出 Golem 网络上提供商的报价.
- [Gc__gvmi_hash](https://github.com/krunch3r76/gc__gvmi_hash)  - 重新计算 gvmi 图像文件的哈希值. 解决了丢失先前上传图像的哈希或不确定密钥是否对应于特定图像的问题.
- [gvm-vim](https://github.com/canokaue/gvm-vim) - 用于编译 VIM 编辑器的 Golemized docker 映像.
- [YaJSapi fork with greeting example](https://github.com/rezahsnz/yajsapi) - Simple Node.js requestor app that greets you. It writes some important message to a file and then downloads it for you, the basic eskeleton of a requestor app. Look in `examples/greetings`.
- [Golem Image Sharpening](https://github.com/visualNext/golem) - A tool to sharpen images.
- [Filterms](https://github.com/krunch3r76/filterms) - 将 Golem 请求者 (yapapi) 列入白名单或列入黑名单的市场策略.
- [golem-bulk-image-handler](https://github.com/figurestudios/golem-bulk-image-handler) - 获取输入图像并使用 Pillow 库以多种不同方式对其进行处理.

## Bounties and Rewards

- [GLM Rewards Program](https://blog.golemproject.net/community-incentives-program/) - A program that incentivizes activity within development, support, content creation, and more.
- [Gitcoin Bounties](https://gitcoin.co/golemfactory/bounties) - 在 Gitcoin 上托管的一系列开放赏金和黑客马拉松.

## Developer and Requestor Resources

- [Yagna handbook](https://handbook.golem.network/) - Handbook for the Golem, implementation name, Yagna.
- [Yagna Python API docs](https://yapapi.readthedocs.io/) - Yapapi 的文档.
- [Releases List](https://github.com/golemfactory/yagna/releases) - Yagna 的 GitHub 版本.
- [Requestor flash tutorial](https://handbook.golem.network/requestor-tutorials/flash-tutorial-of-requestor-development) - 快速开始并在 Golem 上创建您的第一个任务/请求.
- [Yagna tag on Stack Overflow](https://stackoverflow.com/questions/tagged/yagna) - Use the Yagna tag if you have an interesting question you'd like answered.
- [Breakdown of blender.js](https://docs.google.com/document/d/e/2PACX-1vRONc0RRaqImJumYQ3SmILtLo4jiCYgtE0AO3JfpMy0b0-BjAU8TvlIHdtbrs5cDrMbuPFv7khE47MO/pub) - 为开发人员提供的 JS 指南，以更好地了解如何使用 JavaScript API 运行任务.

## Provider Resources

- [Provider Tutorial](https://handbook.golem.network/provider-tutorials/provider-tutorial) - Get started as a Provider on Golem Network using the handbook.
- [Provider FAQ](https://github.com/figurestudios/community-golem-docs/blob/main/providing/provider-faq.md) - Community curated list of commonly asked questions and answers.
- [Yagna-binaries for aarch64](https://github.com/MarijnStevens/yagna-binaries) - 为 64 位 arm 架构构建，以便能够在 Raspberry Pi 等系统上作为提供程序运行.
- [Automatically update provider node prices](https://gist.github.com/sv3t0sl4v/28f896752edc9e20347ffc6d8cefe74c) - 检查 stats.golem.network 上价格中位数并更新与价格相关的提供者节点上的所有 3 个值的脚本.
- [Golem Price Updater](https://github.com/jedbrooke/golem-price-updater) - Automatically adjust the price for your Golem node based on the current price of GLM.

### Monitoring

- [Golem Provider dashboard](https://github.com/vciancio/golem-dashboard) - ReactJS 仪表板可快速从您的提供程序节点收集状态，而无需通过 SSH 连接到它们.
- [Golem Provider dashboard backend / GolemBar](https://github.com/vciancio/golem-node-server) - Flask 后端，它从提供者那里收集数据，然后与上面的仪表板项目一起使用.

### Provisioning

- [Ansible ya_provider](https://galaxy.ansible.com/golemfactory/ya_provider) - Ansible 角色自动部署 Golem 提供程序，所需配置最少.
- [WSL](https://github.com/r34x/WSL)  - 允许 Windows 用户在 Linux 的 Windows 子系统中运行 Golem. 消除需要使用虚拟机的 Windows 用户的要求.
- [Golem Provider Terraform](https://github.com/nemani/golem-provider-terraform) - Terraform script to automatically deploy a Golem Provider on a cloud provider and setup monitoring using prometheus.
- [Automatic Golem](https://github.com/r34x/Automatic-Golem) - Setup a Golem Provider with simple instructions and logs guiding you through the process.
- [Golem Provider Node](https://github.com/alexandre-abrioux/golem-node) - Docker 版本的节点可帮助您快速开始作为 Docker 容器中的提供者运行.
- [Golem Provider node](https://github.com/blue-notes-robot/golem-node) - 上面的 Alxexandre-abrioux 项目的分支，允许从 ENV 变量动态生成配置文件并指定您想要生成多少副本.
- [Scaleable golem provider](https://github.com/cryptobench/scaleable-golem-provider) - 使用 Docker 生成 x 数量的提供者.

## Learning Resources

### Presentations and Workshop Material

- [Golem: Architecture, SDKs and tips with Jakub Mazurek at 0xHack](https://youtu.be/1UoZWC9XI2g) - 现场研讨会深入探讨任何具有 Python 或 JS 编码经验的开发人员如何开始构建在 Golem 上运行的应用程序.
- [Golem: Growing an ecosystem the Golem way with María Paula Fernández at 0xHack](https://youtu.be/FmrdyU90NVE) - Golem 作为一个项目的高级概述和介绍.
- [Golem Workshop at H3LLO Decentralization](https://gist.github.com/zakaprov/5366bffa49b3c116748bf9b5b73c602c) - 包含实时编码黑客马拉松研讨会和相关资源的资源列表，以帮助开发人员了解和请求 Golem.
- [Mainnet Requestor quickstart Walk-through](https://youtu.be/GcdTq3i_wdY) - 使用 Yagna Python API 在 Golem 网络测试网和主网上获取请求的请求者快速入门手册指南的视频演练.
- [Mainnet Provider quickstart Walk-through](https://youtu.be/RITdKtEOV_E) - Video walk-through of the provider handbook guide to start sharing computational resources the Golem Network.

### Unraveling Golem's The Next Milestone Blog Series

- [Unraveling Golem's The Next Milestone](https://blog.golemproject.net/next-milestone) - Introduction to the Yagna implementation of Golem.
- [Unraveling Golem's The Next Milestone, Part II](https://blog.golemproject.net/next-milestone-part-ii/) - Fundamental architectural concepts which constitute the foundations of the new implemenation of Golem, Yagna.
- [Unraveling Golem's The Next Milestone, Part III](https://blog.golemproject.net/next-milestone-part-iii/) - The elements of Golem's reference architecture, and illustrates how they interact to form a working ecosystem, being the Golem Network.

### GitHub Digest Blog Series

- [Golem GitHub Digest #1](https://blog.golemproject.net/golem-github-digest-1/) - 了解 Golem 存储库.
- [Golem GitHub Digest #2](https://blog.golemproject.net/golem-github-digest-2/) - 潜入 Golem 存储库.
- [Golem GitHub Digest #3](https://blog.golemproject.net/golem-github-digest-3/) - Diving into Pull Requests of the Golem repositories.
- [Golem GitHub Digest #4](https://blog.golemproject.net/golem-github-digest-4/) - Diving into latest releases in the Golem repositories.
- [Golem GitHub Digest #5](https://blog.golemproject.net/golem-github-digest-5/) - 潜入 Golem alpha 测试网.
- [Golem GitHub Digest #6](https://blog.golemproject.net/golem-github-digest-6/) - SGX proof-of-concept for Golem.
- [Golem GitHub Digest #7](https://blog.golemproject.net/golem-github-digest-7/) - Golem 市场的去中心化.
- [Golem GitHub Digest #8](https://blog.golemproject.net/golem-github-digest-8/) - 令人敬畏的魔像和 Alpha 3 的后续步骤.
- [Golem GitHub Digest #9](https://blog.golemproject.net/golem-github-digest-9/) - AMD 提供商支持、网络指标和改进的提案处理.
- [Golem GitHub Digest #10](https://blog.golemproject.net/golem-github-digest-10/) - Improvements from community feedback.
- [Golem GitHub Digest #11](https://blog.golemproject.net/golem-github-digest-11/) - 简单的日志收集.
- [Golem GitHub Digest #12](https://blog.golemproject.net/golem-github-digest-12/) - We are on MAINNET and gathering feedback.
- [Golem GitHub Digest #13](https://blog.golemproject.net/golem-github-digest-13/) - Progressing faster with the help of the Golem community.
- [Golem GitHub Digest #14](https://blog.golemproject.net/golem-github-digest-14/) - Towards the next major release.
- [Golem GitHub Digest #15](https://blog.golemproject.net/golem-github-digest-15/) - Awesome, Goth improvements and towards Beta 3.
- [Golem GitHub Digest #16](https://blog.golemproject.net/golem-github-digest-16/) - VPN, ARM binaries for requestors, and custom usage counters.


## Community

- [Golem Network Discussion Group](https://t.me/GolemProject) - 社区驱动的电报频道.
- [Reddit Golem Stat Bot](https://github.com/figurestudios/golem-stat-bot) - Scrapes Reddit posts on /r/GolemProject, and replies if specific keywords/commands are found.
- [Golem God](https://github.com/Shreyas-Dev-ITB/Golem-God) - 发放“机器人币”进行活动，并让用户在有足够的情况下兑换和提取代币.

## Contributing

欢迎向 Awesome Golem 提出拉取请求和问题建议！ 请阅读 [contributing](https://github.com/golemfactory/awesome-golem/blob/master/contributing.md) guidelines before submitting a PR.
