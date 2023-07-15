<div class="github-widget" data-repo="ripienaar/free-for-dev"></div>
## free-for.dev

开发人员和开源作者现在拥有大量提供免费套餐的服务，但很难找到所有这些服务来做出明智的决策.

这是为开发人员提供免费套餐的软件（SaaS、PaaS、IaaS 等）和其他产品的列表.

此特定列表的范围仅限于基础设施开发人员（系统管理员、DevOps 从业人员等）可能会发现有用的内容. 我们喜欢所有的免费服务，但最好保持主题. 有时这有点灰线，所以这有点固执己见； 如果我不接受您的贡献，请不要生气.

该列表是 1100 多人的 Pull Request、评论、想法和工作的结果. 您也可以通过发送来提供帮助 [Pull Requests](https://github.com/ripienaar/free-for-dev) 添加更多服务或删除其产品已更改或已停用的服务.

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

 **注意**：此列表仅适用于即服务产品，不适用于自托管软件. 一项服务要符合资格，必须提供免费套餐，而不仅仅是免费试用. 如果免费套餐有时间限制，则必须至少持续一年. 我们还从安全角度考虑免费层，因此 SSO 很好，但我不会接受将 TLS 限制为仅限付费层的服务.



## Major Cloud Providers

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 每天 28 个前端实例小时，每天 9 个后端实例小时
    * Cloud Firestore - 1GB 存储，每天 50,000 次读取、20,000 次写入、20,000 次删除
    * 计算引擎 - 1 个非抢占式 e2-micro、30GB HDD、5GB 快照存储（仅限某些区域）、每月从北美到所有区域目的地（不包括中国和澳大利亚）的 1 GB 网络出站流量
    * 云存储 - 5GB、1GB 网络出口
     * Cloud Shell - 基于 Web 的 Linux shell/基本 IDE，具有 5GB 持久存储空间. 每周限制 60 小时
    * Cloud Pub/Sub - 每月 10GB 消息
    * 云函数 - 每月 200 万次调用（包括后台调用和 HTTP 调用）
    * Cloud Run - 每月 200 万个请求、360,000 GB 秒内存、180,000 vCPU 秒计算时间、每月来自北美的 1 GB 网络出站流量
     * Google Kubernetes Engine - 一个区域集群无需集群管理费. 每个用户节点均按标准 Compute Engine 定价收费
    * BigQuery - 每月 1 TB 查询，每月 10 GB 存储
    * 云构建 - 每天 120 分钟构建
    * 云源存储库 - 最多 5 个用户、50 GB 存储、50 GB 出口
    * [Google Colab](https://colab.research.google.com/) - 免费的 Jupyter Notebooks 开发环境.
    * 完整、详细的列表 - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * [CloudFront](https://aws.amazon.com/cloudfront/) - 每月 1TB 出站量和每月 2M 次函数调用
    * [Cloudwatch](https://aws.amazon.com/cloudwatch/) - 10 个自定义指标和 10 个警报
    * [CodeBuild](https://aws.amazon.com/codebuild/) - 每月 100 分钟的构建时间
    * [CodeCommit](https://aws.amazon.com/codecommit/) - 5 个活跃用户、50GB 存储空间和每月 10000 个请求
    * [CodePipeline](https://aws.amazon.com/codepipeline/) - 每月 1 个活跃管道
    * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL 数据库
     * [EC2](https://aws.amazon.com/ec2/)  - 每月 750 小时的 t2.micro 或 t3.micro（12 个月）. 每月 100GB 出站流量
    * [EBS](https://aws.amazon.com/ebs/) - 每月 30GB 通用 (SSD) 或磁性 (12mo)
    * [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) - 每月 750 小时（12 个月）
    * [RDS](https://aws.amazon.com/rds/) - 每月 750 小时的 db.t2.micro、db.t3.micro 或 db.t4g.micro、20GB 通用 (SSD) 存储、20GB 存储备份
    * [Glacier](https://aws.amazon.com/glacier) - 10GB长期对象存储
    * [Lambda](https://aws.amazon.com/lambda/) - 每月 100 万个请求
    * [SNS](https://aws.amazon.com/sns/) - 每月 100 万次发布
    * [SES](https://aws.amazon.com/ses/) - 每月 62,000 条消息
    * [SQS](https://aws.amazon.com/sqs/) - 100万个消息队列请求
    * 完整、详细的列表 - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1 个 B1S Linux 虚拟机、1 个 B1S Windows 虚拟机（12 个月）
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 个网络、移动或 API 应用程序（60 CPU 分钟/天）
    * [Functions](https://azure.microsoft.com/services/functions/) - 每月 100 万个请求
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - 实现快速、简单且精益的开发测试环境
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 个对象
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 每月存储 50,000 个用户
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 个活跃用户，无限的私人 Git 存储库
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10 个免费并行作业，时间不限，适用于 Linux、macOS 和 Windows 开源软件
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 每天 8,000 条消息
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1个免费公共负载均衡IP（VIP）
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 100万条推送通知
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 每月 15GB 入站流量（12 个月）和 5GB 出站流量
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 5GB 存储和 400 RU 的预配置吞吐量
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) — 使用免费 SSL、身份验证/授权和自定义域构建、部署和托管静态应用程序和无服务器功能
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS 文件或 Blob 存储（12 个月）
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML API（计算机视觉、翻译器、人脸检测、机器人...），提供免费套餐，包括有限的交易
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - 基于人工智能的搜索和索引服务，免费搜索 10,000 个文档
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - 托管Kubernetes服务，免费集群管理
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 100K 次操作/月
    * 完整、详细的列表 - https://azure.microsoft.com/free/

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * 计算
       - 2 AMD based Compute VMs with 1/8 OCPU and 1 GB memory eachs
       - 4 个基于 Arm 的 Ampere A1 内核和 24 GB 内存，可用作一台虚拟机或最多 4 台虚拟机
       - 实例将在以下情况下被回收： [deemed idle](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances)
    * 块卷 - 2 个卷，总计 200 GB（用于计算）
    * 对象存储 - 10 GB
    * 负载均衡器 - 1 个 10 Mbps 实例
    * 数据库 - 2 个 DB，每个 20 GB
    * 监控 - 5 亿个摄取数据点、10 亿个检索数据点
    * 带宽 - 每月 10 TB 出口，基于 x64 的 VM 上的速度限制为 50 Mbps，基于 ARM 的 VM 上的核心数为 500 Mbps
    * 公共 IP - 2 个用于虚拟机的 IPv4，1 个用于负载均衡器的 IPv4
    * 通知 - 每月 100 万个传递选项，每月发送 1000 封电子邮件
    * 完整、详细的列表 - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * 云函数 - 每月 500 万次执行
    * 对象存储 - 每月 25GB
    * Cloudant 数据库 - 1 GB 数据存储
    * Db2 数据库 - 100MB 数据存储
    * API Connect - 每月 50,000 次 API 调用
    * 可用性监控 - 每月 300 万个数据点
    * 日志分析 - 500MB 每日日志
    * 完整、详细的列表 - https://www.ibm.com/cloud/free/


## Cloud management solutions
  * [Brainboard](https://www.brainboard.co) - 端到端可视化构建和管理云基础设施的协作解决方案.
  * [Pulumi](https://www.pulumi.com/) — 现代基础设施即代码平台，允许您使用熟悉的编程语言和工具来构建、部署和管理云基础设施.
  * [Selefra](https://www.selefra.io/) - Selefra 免费套餐为个人用户提供扫描单一来源连接的功能，以发现云/基础设施/SaaS 配置级别的安全性和合规性问题.
  * [terraform.io](https://www.terraform.io/)  — 地形云. 最多 500 个资源的免费远程状态管理和团队协作.
  * [scalr.com](https://scalr.com/)  - Scalr 是一款 Terraform 自动化和协作 (TACO) 产品，用于在 Terraform 管理的基础设施和配置上更好地协作和自动化. 完全支持 Terraform CLI、与 OPA 集成和分层配置模型. 没有 SSO 税. 所有功能均包含在内. 每月最多免费运行 50 次.


## Source Code Repos

  * [Bitbucket](https://bitbucket.org/) — 使用 CI/CD 管道为最多 5 个用户提供无限的公共和私人 Git 存储库
  * [chiselapp.com](https://chiselapp.com/) — 无限的公共和私人化石存储库
  * [codebasehq.com](https://www.codebasehq.com/) — 1 个免费项目，拥有 100 MB 空间和 2 个用户
  * [Codeberg.org](https://codeberg.org/)  - 免费和开源项目的无限公共和私人 Git 存储库. 静态网站托管 [Codeberg Pages](https://codeberg.page/).
  * [GitGud](https://gitgud.io)  — 无限的私人和公共存储库. 永远免费. 由 GitLab 和 Sapphire 提供支持. 未提供 CI/CD.
  * [GitHub](https://github.com/)  — 无限的公共存储库和无限的私有存储库（具有无限的协作者）. 除此之外，还提供其他一些免费服务（还有更多，但我们在这里列出了主要的服务）：
       - [CI/CD](https://github.com/features/actions)（公共回购免费，私人回购免费 2000 分钟/月）
       - [Codespaces](https://github.com/codespaces)  - 托管在云中的开发环境. 每月免费提供 120 个核心小时和 15 GB 代码空间存储.
       - [Static Website Hosting](https://pages.github.com) （公共回购免费）
       - [Package Hosting & Container Registry](https://github.com/features/packages) （公共仓库免费，私人仓库免费使用 CI/CD 之外的 500 MB 存储空间和 1GB 带宽）
       - 项目管理和问题跟踪.
       - [GitHub Copilot](https://github.com/features/copilot)  — 由 OpenAI Codex 提供支持的 AI 配对编程器和完成工具. 提供代码审查、自动完成、文档和重构. 通过 GitHub 学生开发包向学生免费提供.
  * [gitlab.com](https://about.gitlab.com/)  — 无限的公共和私人 Git 存储库，最多可容纳 5 名协作者. 还提供以下功能：
       - [CI/CD](https://about.gitlab.com/product/continuous-integration) （公共回购免费，私人回购每月 400 分钟）
       - 静态站点 [GitLab Pages](https://about.gitlab.com/product/pages).
       - 每个存储库的容器注册表限制为 10 GB.
       - 项目管理和问题跟踪.
  * [heptapod.net](https://foss.heptapod.net/) — Heptapod 是 GitLab 社区版的友好分支，为 Mercurial 提供支持
  * [ionicframework.com](https://ionicframework.com/appflow) - 使用 Ionic 开发应用程序的存储库和工具，您还有一个离子存储库
  * [NotABug](https://notabug.org) — NotABug.org 是一个免费软件代码协作平台，适用于免费许可的项目，基于 Git
  * [OSDN](https://osdn.net/) - OSDN.net 是为开源软件开发人员提供的免费服务，提供 SVN/Git/Mercurial/Bazaar/CVS 存储库等.
  * [Pagure.io](https://pagure.io) — Pagure.io 是一个免费开源软件代码协作平台，适用于 FOSS 许可的项目，基于 Git
  * [perforce.com](https://www.perforce.com/products/helix-teamhub) — 免费 1GB 云和 Git、Mercurial 或 SVN 存储库.
  * [pijul.com](https://pijul.com/)  - 无限制的免费开源分布式版本控制系统. 它的显着特点是基于完善的补丁理论，这使得它易于学习和使用，并且真正分布式. 解决了git/hg/svn/darcs的很多问题.
  * [plasticscm.com](https://plasticscm.com/) — 对个人、OSS 和非营利组织免费
  * [projectlocker.com](https://projectlocker.com) — 一个免费的私人项目（Git 和 Subversion），拥有 50 MB 空间
  * [RocketGit](https://rocketgit.com)  — 基于 Git 的存储库托管. 无限的公共和私人存储库.
  * [savannah.gnu.org](https://savannah.gnu.org/) - 用作免费软件项目（GNU 项目）的协作软件开发管理系统
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - 用作免费软件项目（针对非 GNU 项目）的协作软件开发管理系统


## APIs, Data and ML

  * [IP.City](https://ip.city) — 每天 100 个免费 IP 地理定位请求
  * [A11yWatch](https://a11ywatch.com)  - 强大的大规模网络可访问性工具. 免费的站点范围内的网络可访问性测试及其他测试每天都会重置.
  * [Abstract API](https://www.abstractapi.com) — 适用于各种用例的 API 套件，包括 IP 地理定位、性别检测甚至电子邮件验证.
  * [algorithmia.com](https://algorithmia.com/)  — 免费托管算法. 包括运行算法的每月免费津贴. 现在有 CLI 支持.
  * [Apify](https://www.apify.com/)  — 网络抓取和自动化平台，可为任何网站创建 API 并提取数据. 现成的抓取工具、集成代理和定制解决方案. 免费计划，每月包含 5 美元的平台积分.
  * [API Mocha](https://apimocha.com)  - 完全免费的在线 API 模拟，用于测试和原型设计. 每天最多发出 500 个请求，完全可定制的 API 响应，下载模拟规则作为 Postman 集合.
  * [APITemplate.io](https://apitemplate.io)  - 使用简单的 API 或 Zapier 和 Airtable 等自动化工具自动生成图像和 PDF 文档. 无需 CSS/HTML. 免费计划包含 50 张图像/月和 3 个模板.
  * [APIToolkit.io](https://apitoolkit.io)  - 充分了解 API 和后端情况所需的所有工具. 具有自动 API 合同验证和监控功能. 免费计划涵盖每月最多 20,000 个请求的服务器.
  * [Arize AI](https://arize.com/)  - 用于模型监控和数据质量和性能漂移等根本问题的机器学习可观察性. 最多可免费使用两个模型.
  * [Atlas toolkit](https://atlastk.org/)  - 用于开发可立即访问的单页 Web 应用程序的轻量级库. 适用于 Java、Node.js、Perl、Python 和 Ruby.
  * [Beeceptor](https://beeceptor.com)  - 在几秒钟内模拟休息 API、伪造 API 响应等等. 每天免费 50 个请求、公共仪表板、开放端点（任何拥有仪表板链接的人都可以查看请求和响应）.
  * [bigml.com](https://bigml.com/)  — 托管机器学习算法. 无限免费开发任务，每个任务限制 16 MB 数据.
  * [Bruzu](https://bruzu.com/)  — 自动化图像制作. 使用 API、集成或无代码表生成大量图像变体.  API 是免费的，带有水印.
  * [Calendarific](https://calendarific.com)  - 面向 200 多个国家/地区的企业级公共假期 API 服务. 免费计划包括每月 1000 次通话.
  * [Clarifai](https://www.clarifai.com)  — 用于自定义人脸识别和检测的图像 API. 能够训练AI模型. 免费计划每月有 5000 次通话.
  * [Cloudmersive](https://cloudmersive.com/) — 实用 API 平台，可完全访问扩展的 API 库，包括文档转换、病毒扫描等，每月调用 800 次.
  * [Colaboratory](https://colab.research.google.com) — 基于网络的免费 Python 笔记本环境，配备 Nvidia Tesla K80 GPU.
  * [Collect2](https://collect2.com)  — 创建 API 端点来测试、自动化和连接 Webhook. 免费计划允许两个数据集、2000 条记录、1 个转发器和 1 个警报.
  * [Conversion Tools](https://conversiontools.io/)  - 文档、图像、视频、音频、电子书的在线文件转换器.  REST API 可用.  Node.js、PHP、Python 的库. 支持最大 50 GB 的文件（对于付费计划）. 免费套餐受到文件大小和每天转换次数的限制.
  * [Coupler](https://www.coupler.io/)  - 在应用程序之间同步的数据集成工具. 它可以创建实时仪表板和报告、转换和操作值、收集和备份见解. 免费计划拥有无限用户、每月 100 次运行、1000 行以及无限集成.
  * [CraftMyPDF](https://craftmypdf.com)  - 使用拖放式编辑器和简单的 API，从可重复使用的模板自动生成 PDF 文档. 免费计划包含每月 100 个 PDF 和 3 个模板.
  * [CurlHub](https://curlhub.io)  — 用于检查和调试 API 调用的代理服务. 免费计划包括每月 10,000 个请求.
  * [CurrencyScoop](https://currencyscoop.com)  - 金融科技应用程序的实时货币数据 API. 免费计划包括每月 5000 次通话.
  * [Cube](https://cube.dev/)  - Cube 帮助数据工程师和应用程序开发人员从现代数据存储中访问数据，将其组织成一致的定义，并将其交付给每个应用程序. 使用 Cube 最快的方法是使用 Cube Cloud，它有免费套餐，每月可使用 1GB 数据.
  * [Data Fetcher](https://datafetcher.com)  - 无需代码即可将 Airtable 连接到任何应用程序或 API. 用于在 Airtable 中运行 API 请求的类似 Postman 的接口. 与数十个应用程序预先构建的集成. 免费计划包括每月 100 次运行.
  * [Dataimporter.io](https://www.dataimporter.io)  - 用于连接、清理数据并将其导入 Salesforce 的工具. 免费计划每月最多包含 20,000 条记录.
  * [Datalore](https://datalore.jetbrains.com)  - Jetbrains 的 Python 笔记本. 包括 10 GB 存储空间和每月 120 小时的运行时间.
  * [Data Miner](https://dataminer.io/)  - 用于从网页 CSV 或 Excel 中提取数据的浏览器扩展程序（Google Chrome、MS Edge）. 免费计划每月为您提供 500 页.
  * [Datapane](https://datapane.com) - 用于在 Python 中构建交互式报告以及将 Python 脚本和 Jupyter Notebook 部署为自助服务工具的​​ API.
  * [DB-IP](https://db-ip.com/api/free) - 免费的IP地理定位API，每个IP每天有1k个请求.CC-BY 4.0许可证下的lite数据库也是免费的.
  * [DB Designer](https://www.dbdesigner.net/) — 基于云的数据库架构设计和建模工具，包含 2 个数据库模型和每个模型 10 个表的免费入门计划.
  * [DeepAR](https://developer.deepar.ai)  — 使用一个 SDK 适用于任何平台的增强现实面部滤镜. 免费计划提供最多 10 个每月活跃用户 (MAU) 并跟踪最多 4 个面孔
  * [Deepnote](https://deepnote.com)  - 一种新型数据科学笔记本. 与 Jupyter 兼容，可实时协作并在云端运行. 免费套餐包括无限的个人项目、长达 750 小时的标准硬件以及最多 3 名编辑的团队.
  * [Diggernaut](https://www.diggernaut.com/)  — 基于云的网络抓取和数据提取平台，用于将任何网站转换为数据集或像使用 API 一样使用它. 免费计划包括每月 5K 页面请求.
  * [Disease.sh](https://disease.sh/) — 一个免费的 API，为构建 Covid-19 相关的有用应用程序提供准确的数据.
  * [dreamfactory.com](https://dreamfactory.com/)  — 适用于移动、Web 和 IoT 应用程序的开源 REST API 后端. 连接任何 SQL/NoSQL 数据库、文件存储系统或外部服务，它会立即创建一个全面的 REST API 平台，具有实时文档、用户管理等功能.
  * [DynamicDocs](https://advicement.io)  - 基于 LaTeX 模板，使用 JSON 到 PDF API 生成 PDF 文档. 免费计划允许每月 50 次 API 调用并访问模板库.
  * [DynaPictures](https://dynapictures.com)  - 设计自动化工具，可让您通过 REST API 动态生成图像. 即时更改颜色、文本、徽标和图像. 免费计划包括每月 30 张生成的图像和 3 个图像模板.
  * [Efemarai](https://efemarai.com)  - 机器学习模型和数据的测试和调试平台. 可视化任何计算图. 每月为开发人员免费提供 30 次调试会话.
  * [Einblick](https://www.einblick.ai/)  - 一个现代数据科学平台，将 Python 笔记本引入协作画布，并包含自动执行常见任务的工具，例如构建预测模型 (AutoML) 或比较群体. 免费套餐包括 5 个画布和无限个合作者.
  * [Exspanse](https://exspanse.com)  - MLOPS 平台用于构建、训练和部署 ML 模型和 AI 解决方案. 免费计划提供创建无限项目、5Gb 云存储、5 个 Docker 容器映像的能力.
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 免费的基于 Web 的 HTTP 客户端，用于发送 HTTP 请求.
  * [Export SDK](https://exportsdk.com)  - PDF 生成器 API 带有拖放模板编辑器，还提供 SDK 和无代码集成. 免费计划包含每月 250 页、无限用户和三个模板.
  * [file.coffee](https://file.coffee/) - 一个平台，您可以存储最多 15MB/文件（一个帐户可存储 30/MB 文件）.
  * [Flatirons Fuse](https://flatironsdevelopment.com/products/fuse/) - 嵌入式 CSV 和电子表格导入工具，可快速、轻松、轻松地将数据导入您的网站.
  * [FraudLabs Pro](https://www.fraudlabspro.com)  — 筛查订单交易是否存在信用卡支付欺诈行为. 该 REST API 将根据订单的输入参数检测所有可能的欺诈特征. 免费微型计划每月有 500 笔交易.
  * [FreeGeoIP.app](https://freegeoip.app/)  - 完全免费的地理 IP 信息（JSON、CSV、XML）. 无需注册，每小时 15000 次查询.
  * [Geekflare API](https://geekflare.com/api)  - Geekflare API 可让您截取屏幕截图、审核网站、TLS 扫描、DNS 查找、测试 TTFB 等等. 免费计划提供 3000 个 API 请求.
  * [GeoCod](https://geocod.xyz) — 免费地理编码 API：将邮政地址转换为地理坐标或将地理坐标转换为邮政地址（反向地理编码）.
  * [GeoDataSource](https://www.geodatasource.com)  — 使用纬度和经度坐标查找城市名称的位置搜索服务. 每月最多免费 API 查询 500 次.
  * [Glitterly](https://glitterly.app/)  - 以编程方式从基本模板生成动态图像.  Restful API 和 nocode 集成. 免费套餐每月提供 50 张图片和 5 个模板.
  * [GoodData](https://www.gooddata.com/)  - 数据即服务 - 创建交互式且富有洞察力的仪表板. 免费套餐包含 5 个工作区和 100 MB/工作区.
  * [Hex](https://hex.tech/)  - 用于笔记本、数据应用程序和知识库的协作数据平台. 免费社区版本，最多可有 3 位作者和 5 个项目. 每位作者一个具有 4GB RAM 的计算配置文件.
  * [Hook0](https://www.hook0.com/)  - Hook0 是一个开源 Webhooks 即服务 (WaaS)，可以让在线产品轻松提供 Webhooks. 每月发送多达 3,000 个事件，并免费保留 7 天的历史记录.
  * [Hoppscotch](https://hoppscotch.io) - 一个免费、快速且美观的 API 请求生成器.
  * [Hybiscus](https://hybiscus.dev/)  - 使用简单的声明式 API 构建 pdf 报告. 免费套餐包括每月最多 100 个单页报告，并且能够自定义调色板和字体.
  * [Invantive Cloud](https://cloud.invantive.com/)  — 使用 Invantive SQL 或 OData4（通常是 Power BI 或 Power Query）访问 70 多个（云）平台，例如 Exact Online、Twinfield、ActiveCampaign 或 Visma. 包括数据复制和交换. 为开发人员和实施顾问提供免费计划. 对于数据量有限的特定平台免费.
  * [ipaddress.sh](https://ipaddress.sh) — 获取不同公共IP地址的简单服务 [formats](https://about.ipaddress.sh/).
  * [Iploka](https://iploka.com/) — IP 到地理定位 API - 为开发人员提供永久免费计划，每月限制 10k 请求.
  * [IP Geolocation](https://ipgeolocation.io/) — IP 地理定位 API - 为开发人员提供永久免费计划，每月 30k 请求（1k/天）限制.
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) — 摘要中的 IP 地理定位 API - 广泛的免费计划，每月允许 20,000 个请求.
  * [IP2Location](https://www.ip2location.com)  — 免费增值 IP 地理定位服务.  LITE 数据库可供免费下载. 导入服务器数据库并进行本地查询，确定城市、坐标和ISP信息.
  * [IP2Location.io](https://www.ip2location.io/)  — 免费增值、快速可靠的 IP 地理定位 API，用于确定城市、坐标、ISP 等地理定位数据. 免费计划提供每月 30k 积分. 订阅付费计划以获取更多高级功能，或联系我们获取个性化计划.
  * [ipapi](https://ipapi.co/)  - Kloudend, Inc 的 IP 地址定位 API - 可靠的地理定位 API，基于 AWS 构建，深受财富 500 强企业信赖.免费套餐每月提供 30,000 次查找（1,000 次/天），无需注册. 联系我们获取更高限额的试用计划.
  * [IPinfo](https://ipinfo.io/)  — 快速、准确且免费（高达 50k/月）的 IP 地址数据 API. 提供包含地理位置、公司、运营商、IP 范围、域、滥用联系人等详细信息的 API. 所有付费API均可免费试用.
  * [IPList](https://www.iplist.cc)  — 查找有关任何 IP 地址的详细信息，例如 Geo IP 信息、tor 地址、主机名和 ASN 详细信息. 对个人和企业用户免费.
  * [BigDataCloud](https://www.bigdatacloud.com/) - 为现代网络提供快速、准确且免费（无限制或高达 10K-50K/月）的 API，例如 IP 地理定位、反向地理编码、网络洞察、电子邮件和电话验证、客户信息等.
  * [IPTrace](https://iptrace.io) — 一个极其简单的 API，可为您的企业提供可靠且有用的 IP 地理定位数据.
  * [JSON2Video](https://json2video.com) - 视频编辑 API，可通过编程或无代码自动化视频营销和社交媒体视频.
  * [JSON IP](https://getjsonip.com)  — 返回请求的客户端的公共 IP 地址. 免费套餐无需注册. 可以使用客户端 JS 直接从浏览器请求使用 CORS 数据. 对于监控客户端和服务器 IP 变化的服务很有用. 无限请求.
  * [konghq.com](https://konghq.com/)  — API 市场以及适用于私有和公共 API 的强大工具. 对于免费套餐，某些功能受到限制，例如监控、警报和支持.
  * [Kreya](https://kreya.app)  — 免费的 gRPC GUI 客户端，用于调用和测试 gRPC API. 可以通过服务器反射导入 gRPC API.
  * [Lightly](https://www.lightly.ai/)  — 使用正确的数据改进您的机器学习模型. 免费使用最多 1,000 个样本的数据集.
  * [LoginLlama](https://loginllama.app) - A login security API to detect fraudulent and suspicious logins and notify your customers. Free for 1,000 logins per month.
  * [MailboxValidator](https://www.mailboxvalidator.com)  — 电子邮件验证服务使用真实邮件服务器连接来确认有效电子邮件. 免费 API 计划每月有 300 次验证.
  * [Meteosource Weather API](https://www.meteosource.com/)  — 用于当前和预测天气数据的全球天气 API. 预测基于更多天气模型的机器学习组合，以实现更高的准确性. 免费套餐每天可拨打 400 个电话.
  * [microlink.io](https://microlink.io/)  – 它将任何网站转化为数据，例如元标签标准化、美容链接预览、抓取功能或屏幕截图即服务. 每天 100 个请求免费.
  * [monkeylearn.com](https://monkeylearn.com/) — 使用机器学习进行文本分析，每月免费 300 次查询.
  * [MockAPI](https://www.mockapi.io/)  — MockAPI 是一个简单的工具，可让您轻松模拟 API、生成自定义数据并使用 RESTful 接口对其执行操作.  MockAPI 旨在用作原型设计/测试/学习工具.  1 个项目/每个项目 4 个资源免费.
  * [Mocki](https://mocki.io)  - 该工具可让您创建同步到 GitHub 存储库的模拟 GraphQL 和 REST API. 简单的 REST API 无需注册即可免费创建和使用.
  * [Mocko.dev](https://mocko.dev/)  — 免费代理您的 API、选择要在云中模拟的端点并检查流量. 加快您的开发和集成测试.
  * [Mocky](https://designer.mocky.io/)  - 一个简单的 Web 应用程序，用于生成自定义 HTTP 响应以模拟 HTTP 请求. 也可用作 [open source](https://github.com/julien-lafont/Mocky).
  * [reqres.in](https://reqres.in) - 免费托管的 REST-API，可随时响应您的 AJAX 请求.
  * [microenv.com](https://microenv.com) — 为开发人员创建假 REST API，可以在 docker 容器中生成代码和应用程​​序.
  * [neptune.ai](https://neptune.ai/)  - 记录、存储、显示、组织、比较和查询您的所有 MLOps 元数据. 个人免费：1 名成员、100 GB 元数据存储、200 小时监控/月
  * [News API](https://newsapi.org)  — 使用代码在网络上搜索新闻，获取 JSON 结果. 开发人员每月免费获得 3,000 次查询.
  * [Nordigen](https://nordigen.com)  — 免费开放银行数据API.  PSD2. 将欧盟+英国的 2300 多家银行与您的应用程序/软件连接起来.
  * [Observable](https://observablehq.com/)  ——一个利用数据进行创造、协作和学习的地方. 免费：无限笔记本，无限出版，每个笔记本五位编辑.
  * [OCR.Space](https://ocr.space/)  — OCR API，可解析图像和 pdf 文件，以 JSON 格式返回文本结果. 每月 25,000 个请求免费.
  * [Duply.co](https://duply.co)  — 从 API 和 URL 创建动态图像，设计模板一次并重复使用. 免费套餐每月可通过 API 和 URL 创建 70 张图像，并通过表单创建最多 100 张图像.
  * [OpenAPI3 Designer](https://openapidesigner.com/) — 免费直观地创建 Open API 3 定义.
  * [Orchest](https://orchest.io) — 用于数据科学的可视化管道编辑器和工作流编排器，1 个免费实例，提供开源版本.
  * [parsehub.com](https://parsehub.com/) — 从动态网站中提取数据，将动态网站转换为 API，5 个项目免费.
  * [pdfEndpoint.com](https://pdfendpoint.com)  - 使用简单的 API 轻松将 html 或 url 转换为 pdf. 每月 100 次免费转换.
  * [Pixela](https://pixe.la/)  - 免费的日流数据库服务. 所有操作均通过API执行. 还可以使用热图和折线图进行可视化.
  * [Postbacks](https://postbacks.io/)  - 稍后请求 HTTP 回调. 注册后可获得 8,000 个免费请求.
  * [Postman](https://postman.com)  — 使用用于 API 开发的协作平台 Postman，简化工作流程并更快地创建更好的 API. 永久免费使用邮递员应用程序.  Postman 云功能也是永久免费的，但有一定限制.
  * [PrefectCloud](https://www.prefect.io/cloud/)  — 数据流自动化的完整平台. 所有计划均包含每月 20,000 次免费运行. 对于大多数小型企业来说，这足以支持 ETL.
  * [Preset Cloud](https://preset.io/)  - 托管 Apache Superset 服务. 对于最多 5 个用户的团队永远免费，具有无限的仪表板和图表、无代码图表生成器和协作 SQL 编辑器.
  * [PromptLeo](https://promptleo.com/)  - 为创作者和开发者提供快速的工程平台. 提供提示工程库、提示表单和提示工程API. 免费计划提供 1 个提示表单、1 个提示 API 端点、每月 30 代.
  * [PromptLoop](https://www.promptloop.com/)  - 使用 AI 和 GPT-3 等大型语言模型以及单个简单的电子表格公式来转换、理解和分析 Google 表格中的文本. 每月前 2,000 个积分免费.
  * [ProxyCrawl](https://proxycrawl.com/)  — 无需代理、基础设施或浏览器即可抓取和抓取网站. 我们为您解决验证码并防止您被屏蔽. 前 1000 次通话免费.
  * [Public-Apis Github Repo](https://github.com/public-apis/public-apis) — 免费公共 API 列表.
  * [Supportivekoala](https://supportivekoala.com/)  — 允许您通过模板输入自动生成图像. 免费计划允许您每周创建最多 100 张图像.
  * [QuickMocker](https://quickmocker.com/)  — 在您自己的子域下管理在线虚假 API 端点，将请求转发到 localhost URL 以进行 Webhook 开发和测试，使用 RegExp 和多种 HTTP 方法作为 URL 路径，确定端点的优先级，用于响应模板的 100 多个短代码（动态或虚假响应值），从 OpenAPI (Swagger) 规范导入 JSON 格式、代理请求、通过 IP 地址和授权标头限制端点. 免费帐户提供 1 个随机子域、10 个端点、5 个 RegExp URL 路径、每个端点 50 个短代码、每天 100 个请求、请求日志中的 50 条历史记录.
  * [Rapidapi](https://rapidapi.com/) - 世界上最大的 API 中心 数以百万计的开发人员发现并连接到数千个 API，使用有趣的挑战（带有解决方案！）和交互式示例进行 API 开发.
  * [RequestBin.com](https://requestbin.com)  — 创建一个可以向其发送 HTTP 请求的免费端点. 发送到该端点的任何 HTTP 请求都将与关联的负载和标头一起记录，以便您可以观察来自 Webhook 和其他服务的请求.
  * [Roboflow](https://roboflow.com)  - 创建和部署自定义计算机视觉模型，无需具备机器学习经验. 免费套餐包含最多 1,000 张免费源图像.
  * [ROBOHASH](https://robohash.org/) - 用于从任何文本生成独特（酷:）图像的网络服务.
  * [SaturnCloud](https://saturncloud.io/)  - 数据科学云环境，允许运行 Jupyter 笔记本和 Dask 集群. 每月 30 小时免费计算和 3 小时 Dask.
  * [Scraper's Proxy](https://scrapersproxy.com)  — 用于抓取的简单 HTTP 代理 API. 匿名抓取，无需担心限制、阻止或验证码. 每月成功抓取的前 100 个免费，包括 javascript 渲染（如果您联系支持人员，可以获取更多）.
  * [ScrapingAnt](https://scrapingant.com/)  — 无头 Chrome 抓取 API 和免费检查代理服务.  JavaScript 渲染、高级旋转代理、避免验证码. 提供免费计划.
  * [ScraperBox](https://scraperbox.com/)  — 使用真正的 Chrome 浏览器和代理轮换无法检测到的网页抓取 API. 使用简单的 API 调用即可抓取任何网页. 免费计划每月有 1000 个请求.
  * [ScrapingDog](https://scrapingdog.com/)  — Scrapingdog 处理数百万个代理、浏览器和验证码，以便在单个 API 调用中为您提供任何网页的 HTML. 它还提供了适用于 Chrome 和 Firefox 的 Web Scraper 以及满足即时抓取需求的软件. 提供免费计划.
  * [scrapinghub.com](https://scrapinghub.com)  — 使用可视化界面和插件进行数据抓取. 免费计划包括在共享服务器上无限制地抓取.
  * [Select Star](https://www.selectstar.com/)  - 是一个智能数据发现平台，可自动分析和记录您的数据. 免费的轻型层，具有 1 个数据源、最多 100 个表和最多 10 个用户.
  * [Sheetson](https://sheetson.com)  - 立即将任何 Google Sheets 转换为 RESTful API. 提供免费计划.
  * [Shipyard](https://www.shipyardapp.com)  — 用于云的低代码数据编排平台. 混合使用低代码模板和您的代码（Python、Node.js、Bash、SQL）进行构建. 我们的免费开发者计划每月为一名用户提供 10 小时的运行时间 - 足以自动化多个工作流程.
  * [shrtcode API](https://shrtco.de/docs) - 免费URL缩短API，无需授权，无请求限制.
  * [SerpApi](https://serpapi.com/)  - 实时搜索引擎抓取API. 返回 Google、Youtube、Bing、百度、沃尔玛和许多其他引擎的结构化 JSON 结果. 免费计划包括每月 100 次成功的 API 调用.
  * [Sofodata](https://www.sofodata.com/)  - 从 CSV 文件创建安全的 RESTful API. 上传 CSV 文件并通过其 API 立即访问数据，从而加快应用程序开发速度. 免费计划包括 2 个 API 和每月 2,500 次 API 调用. 无需信用卡.
  * [Stoplight](https://stoplight.io/)  - 用于协作设计和记录 API 的 Saas. 免费计划提供免费的设计、模拟和文档工具来帮助您入门.
  * [Svix](https://www.svix.com/)  - Webhook 即服务. 每月免费发送多达 50,000 条消息.
  * [TemplateTo](https://templateto.com)  - 使用我们的拖放式编辑器和简单的 API，从可重复使用的模板自动生成 PDF/TXT 文档. 免费计划包含 450 个 PDF/月和 3 个模板.
  * [TinyMCE](https://www.tiny.cloud)  - 富文本编辑API. 核心功能免费，无限制使用.
  * [Webhook Store](https://www.openwebhook.io)  - 用于存储第三方 Webhook 并在本地主机上调试它们的工具（ngrok 风格）. 开源且可自行托管. 免费个人域名*用户名*.github.webhook.store，免费公共域名*anything*.webhook.store.
  * [Weights & Biases](https://wandb.ai)  — 开发人员优先的 MLOps 平台. 通过实验跟踪、数据集版本控制和模型管理，更快地构建更好的模型. 免费套餐仅适用于个人项目，包含 100 GB 存储空间.
  * [wit.ai](https://wit.ai/) — 面向开发人员的 NLP.
  * [wolfram.com](https://wolfram.com/language/) — 云端内置基于知识的算法.
  * [wrapapi.com](https://wrapapi.com/)  — 将任何网站变成参数化 API. 每月 30,000 次 API 调用.
  * [ZenRows](https://www.zenrows.com/)  — Web Scraping API 和代理服务器，可绕过任何反机器人解决方案，同时提供 JavaScript 渲染、旋转代理和地理定位.  1000 次 API 调用的免费套餐.
  * [Zenscrape](https://zenscrape.com/web-scraping-api)  — 具有无头浏览器、住宅 IP 和简单定价的 Web 抓取 API. 每月 1000 次免费 API 调用，为学生和非营利组织提供额外免费积分.
  * [ip-api](https://ip-api.com) — IP 地理定位 API，免费用于非商业用途，无需 API 密钥，免费计划的同一 IP 地址限制为 45 个请求/分钟.
  * [WebScraping.AI](https://webscraping.ai)  - 简单的 Web Scraping API，具有内置解析、Chrome 渲染和代理. 每月 2000 次免费 API 调用.
  * [Zipcodebase](https://zipcodebase.com)  - 免费邮政编码 API，访问全球邮政编码数据. 每月 10000 个免费请求.
  * [huggingface.co](https://huggingface.co)  - 为 Pytorch、TensorFlow 和 JAX 构建、训练和部署 NLP 模型. 每个月可释放多达 30k 个输入字符.
  * [vatcheckapi.com](https://vatcheckapi.com)  - 简单且免费的增值税号验证 API. 每月 500 个免费请求.
  * [numlookupapi.com](https://numlookupapi.com) - 免费电话号码验证 API - 每月 10 万个免费请求.
  * [Volca](https://volca.io#api)  - 免费 API 提供编程语言和数据库系统等技术列表. 无限制的免费请求.
  * [Query.me](https://query.me) - Collaborative data notebooks that execute in a script-like fashion and allow to fetch and send data via SQL, API, and a growing number custom blocks, like Slack and Email. Free for small Teams.
* [ERD Lab](https://www.erdlab.io) — 为开发人员制作的基于云的免费实体关系图 (ERD) 工具.
* [What The Diff](https://whatthediff.ai)  - 人工智能驱动的代码审查助手. 免费计划的限制为每月 25,000 个代币（约 10 个 PR）.
* [Zipcodestack](https://zipcodestack.com)  - 免费邮政编码 API 和邮政编码验证. 每月 10000 个免费请求.


## Artifact Repos

 * [Artifactory](https://jfrog.com/start-free/)  - 一个工件存储库，支持多种包格式，例如 Maven、Docker、Cargo、Helm、PyPI、CocoaPods 和 GitLFS. 包括包扫描工具 XRay 和 CI/CD 工具 Pipelines（以前称为 Shippable），每月免费使用 2,000 CI/CD 分钟.
 * [central.sonatype.org](https://central.sonatype.org) — Apache Maven、SBT 和其他构建系统的默认工件存储库.
 * [cloudrepo.io](https://cloudrepo.io)  - 基于云的私有和公共、Maven 和 PyPi 存储库. 对于开源项目免费.
 * [cloudsmith.io](https://cloudsmith.io)  — 适用于 Java/Maven、RedHat、Debian、Python、Ruby、Vagrant 等的简单、安全且集中的存储库服务. 免费层+免费开源.
 * [jitpack.io](https://jitpack.io/) — GitHub 上 JVM 和 Android 项目的 Maven 存储库，对公共项目免费.
 * [packagecloud.io](https://packagecloud.io/users/new?plan=free_usage_plan) — 易于使用的存储库托管：Maven、RPM、DEB、PyPi、NPM 和 RubyGem 包（有免费套餐）.
 * [repsy.io](https://repsy.io) — 1 GB 免费私人/公共 Maven 存储库.
 * [Gemfury](https://gemfury.com)  — Maven、PyPi、NPM、Go Module、Nuget、APT、RPM 存储库的私有和公共工件存储库. 免费用于公共项目.
 * [paperspace](https://www.paperspace.com/) — 构建和扩展 AI 模型，开发、训练和部署 AI 应用程序，免费计划：公共项目、5Gb 存储、基本实例.


## Tools for Teams and Collaboration

  * [3Cols](https://3cols.com/) - 一个免费的基于云的代码片段管理器，用于个人和协作代码.
  * [Bitwarden](https://bitwarden.com) — 个人、团队和商业组织存储、共享和同步敏感数据的最简单、最安全的方式.
  * [Braid](https://www.braidchat.com/)  — 专为团队设计的聊天应用程序. 公共访问组免费，用户、历史记录和集成不受限制. 它还提供可自托管的开源版本.
  * [cally.com](https://cally.com/)  — 找到召开会议的最佳时间和日期. 使用简单，非常适合小型和大型团体.
  * [Calendly](https://calendly.com)  — Calendly 是连接和安排会议的工具. 免费计划为每个用户提供 1 个日历连接和无限次会议. 还提供桌面和移动应用程序.
  * [Discord](https://discord.com/)  — 与公共/私人房间聊天.  Markdown 文本、语音、视频和屏幕共享功能. 免费供无限用户使用.
  * [Telegram](https://telegram.org/)  — Telegram 适合所有想要快速可靠的消息和通话的人. 商业用户和小型团队可能喜欢大型群组、用户名、桌面应用程序和强大的文件共享选项.
  * [Duckly](https://duckly.com/)  — 与您的团队实时交谈和协作. 与任何 IDE 配对编程、终端共享、语音、视频和屏幕共享. 小团队免费.
  * [Dyte](https://dyte.io)  - 对开发人员最友好的实时视频和音频 SDK，具有协作插件以提高生产力和参与度. 免费套餐包括每月 10,000 分钟的实时视频/音频使用量.
  * [evernote.com](https://evernote.com/)  — 组织信息的工具. 分享您的笔记并与其他人一起工作
  * [Fibery](https://fibery.io/)  — 连接的工作空间平台. 单用户免费，最多 2 GB 磁盘空间.
  * [Filestash](https://www.filestash.app) — 类似 Dropbox 的文件管理器，可连接到一系列协议和平台：S3、FTP、SFTP、Minio、Git、WebDAV、Backblaze、LDAP 等.
  * [flock.com](https://flock.com)  — 为您的团队提供更快的沟通方式. 免费无限消息、频道、用户、应用程序和集成
  * [Gather](https://www.gather.town/)  - 更好的在线见面方式.  Gather 以完全可定制的空间为中心，让您与社区共度时光就像现实生活一样轻松. 最多 10 个并发用户免费.
  * [gokanban.io](https://gokanban.io)  - 基于语法，无需注册看板即可快速使用. 免费，没有任何限制.
  * [flat.social](https://flat.social)  - 用于团队会议和欢乐时光社交活动的交互式可定制空间. 无限次会议，最多可免费容纳 8 个并发用户.
  * [GitDailies](https://gitdailies.com)  - 团队在 GitHub 上的提交和拉取请求活动的每日报告. 包括推送可视化工具、同行识别系统、自定义警报生成器. 免费套餐拥有无限用户、3 个存储库、3 个警报配置.
  * [gitter.im](https://gitter.im/)  — 聊天，针对 GitHub. 无限制的公共和私人房间，最多 25 人的团队免费
  * [Hackmd.io](https://hackmd.io/)  - 用于 Markdown 格式文档/文件的实时协作和编写工具. 与 GoogleDocs 类似，但适用于 Markdown 文件. 免费无限数量的“笔记”，但私人笔记和模板的协作者（受邀者）数量 [will be limited](https://hackmd.io/pricing).
  * [hangouts.google.com](https://hangouts.google.com/) — 一个地方可以进行所有对话，免费，需要一个 Google 帐户
  * [HeySpace](https://hey.space)  - 具有聊天、日历、时间线和视频通话功能的任务管理工具. 最多 5 个用户免费.
  * [helplightning.com](https://www.helplightning.com/)  — 通过增强现实技术帮助视频. 免费，无需分析、加密、支持
  * [ideascale.com](https://ideascale.com/) — 允许客户提交想法并投票，1 个社区的 25 名成员免费
  * [Igloo](https://www.igloosoftware.com/) — 用于共享文档、博客和日历等的内部门户.最多可供 10 个用户免费.
  * [Keybase](https://keybase.io/) — Keybase 是 Slack 的一个很酷的自由开源软件替代品，它可以保证每个人的聊天和文件的安全，从家庭到社区再到公司.
  * [Google Meet](https://meet.google.com/)  — 使用 Google Meet 满足您企业的在线视频会议需求.  Meet 提供安全、易于加入的在线会议.
  * [/meet for Slack](https://meetslack.com)  - 在任何频道、群组或 DM 中使用 /meet 直接从 Slack 启动 Google 会议. 免费，没有任何限制.
  * [Livecycle](https://www.livecycle.io/) — Livecycle 是一个包容性协作平台，使跨职能产品团队和开源项目的工作流程变得顺畅.
  * [MarkUp](https://www.markup.io/) — MarkUp 可让您直接在网站、PDF 和图像上收集反馈.
  * [Visual Debug](https://visualdebug.com) - 视觉反馈工具，用于更好的客户与开发人员沟通
  * [meet.jit.si](https://meet.jit.si/) — 一键视频对话、屏幕共享，免费
  * [Microsoft Teams](https://products.office.com/microsoft-teams/free)  — Microsoft Teams 是一个基于聊天的数字中心，可通过单一体验将对话、内容和应用程序汇集到一个地方. 最多 50 万用户免费.
  * [Miro](https://miro.com/)  - 适用于分布式团队的可扩展、安全、跨设备和企业级团队协作白板. 具有免费增值计划.
  * [nootiz](https://www.nootiz.com/) - 用于收集和管理任何网站上的视觉反馈的首选工具
  * [Notion](https://www.notion.so/)  - Notion 是一款支持 Markdown 的笔记和协作应用程序，还集成了任务、wiki 和数据库. 该公司将该应用程序描述为一个用于记笔记、项目管理和任务管理的一体化工作空间. 除了跨平台应用程序之外，还可以通过大多数网络浏览器访问它.
  * [Nuclino](https://www.nuclino.com)  - 一个轻量级的协作式 wiki，包含您团队的所有知识、文档和注释. 免费计划包含所有基本功能，最多 50 个项目，5GB 总存储空间.
  * [Quidlo Timesheets](https://www.quidlo.com/timesheets)  - 适合团队的简单时间表和时间跟踪应用程序. 免费计划具有时间跟踪和生成报告功能，最多可供 10 个用户使用.
  * [PageShare.dev](https://www.pageshare.dev)  - 将视觉评论功能添加到 GitHub Pull 请求中，无需部署网站. 每月最多可免费使用 10 页，总共可免费使用 100MB 的存储空间.
  * [Pendulums](https://pendulums.io/) - Pendulums 是一款免费时间跟踪工具，通过易于使用的界面和有用的统计数据，帮助您更好地管理时间.
  * [Pumble](https://pumble.com)  - 免费团队聊天应用程序. 无限用户和消息历史记录，永久免费.
  * [Raindrop.io](https://raindrop.io)  - 适用于 macOS、Windows、Android、iOS 和 Web 的私密且安全的书签应用程序. 免费无限书签和协作.
  * [element.io](https://element.io/)  — 基于 Matrix 的去中心化开源通信工具. 群聊、直接消息传递、加密文件传输、语音和视频聊天以及与其他服务的轻松集成.
  * [Rocket.Chat](https://rocket.chat/) - 具有全渠道功能、矩阵联合、与其他应用程序桥接、无限消息传递和完整消息传递历史记录的开源通信平台.
  * [seafile.com](https://www.seafile.com/)  — 私人或云存储、文件共享、同步、讨论. 私人版本已满. 云版只有1GB
  * [Sema](https://www.semasoftware.com/) - 免费的开发人员组合工具能够将多个存储库的贡献合并并快照到单个报告中.
  * [Slab](https://slab.com/)  — 面向团队的现代知识管理服务. 最多 10 位用户免费.
  * [slack.com](https://slack.com/) — 免费供无限用户使用，但有一些功能限制
  * [Spectrum](https://spectrum.chat/) - 免费创建公共或私人社区.
  * [StatusPile](https://www.statuspile.com/)  - 状态页面的状态页面. 跟踪上游提供商的状态页面.
  * [Stickies](https://stickies.app/)  - 用于头脑风暴、内容管理和笔记的视觉协作应用程序. 最多可免费使用 3 面墙、无限用户、1 GB 存储空间.
  * [talky.io](https://talky.io/)  — 免费群组视频聊天. 匿名的. 点对点. 无需插件、注册或付款
  * [Teamhood](https://teamhood.com/)  - 免费的项目、任务和问题跟踪软件. 通过泳道和完整的 Scrum 实施支持看板. 具有集成的时间跟踪. 免费供 5 个用户和 3 个项目组合使用.
  * [Teamplify](https://teamplify.com)  - 通过团队分析和智能每日站会改进团队开发流程. 包括针对远程优先团队的全功能休假管理. 最多 5 个用户的小型团队免费.
  * [Tefter](https://tefter.io)  - 具有强大 Slack 集成的书签应用程序. 对开源团队免费.
  * [TeleType](https://teletype.oorja.io/)  — 共享终端、语音、代码、白板等. 无需登录，为开发人员提供端到端加密协作.
  * [TimeCamp](https://www.timecamp.com/)  - 无限用户的免费时间跟踪软件. 轻松与 Jira、Trello、Asana 等 PM 工具集成.
  * [twist.com](https://twist.com)  — 一款异步友好的团队沟通应用程序，对话保持井然有序且切题. 提供免费和无限制的计划. 为符合条件的团队提供折扣.
  * [tldraw.com](https://tldraw.com)  — 免费的开源白板和图表工具，具有智能箭头、捕捉、便笺和 SVG 导出等功能. 用于协作编辑的多人游戏模式. 还提供免费的官方 VS Code 扩展.
  * [BookmarkOS.com](https://bookmarkos.com) - 可定制在线桌面中的免费全合一书签管理器、选项卡管理器和任务管理器，具有文件夹协作功能.
  * [typetalk.com](https://www.typetalk.com/) — 通过网络或移动设备上的即时消息与您的团队分享和讨论想法
  * [Tugboat](https://tugboat.qa)  - 预览每个拉取请求，自动化且按需. 所有人免费，非营利组织免费获得 Nano 等级.
  * [whereby.com](https://whereby.com/) — 免费的一键视频对话（以前称为appear.in）
  * [windmill.dev](https://windmill.dev/)  - Windmill 是一个开源开发者平台，可通过最少的 Python 和 Typescript 脚本快速构建生产级多步骤自动化和内部应用程序. 您可以创建最多 3 个非高级工作区并成为免费用户.
  * [vadoo.tv](https://vadoo.tv/)  — 视频托管和营销变得简单. 只需单击一下即可上传视频. 记录、管理、分享等等. 免费套餐每月提供最多 10 个视频、1 GB 存储空间、10 GB 带宽
  * [userforge.com](https://userforge.com/)  - 相互关联的在线角色、用户故事和上下文映射. 帮助保持设计和开发同步，最多可免费供 3 个角色和 2 个协作者使用.
  * [wistia.com](https://wistia.com/) — 视频托管，具有观众分析、高清视频传输和营销工具，可帮助了解您的访客、25 个视频和 Wistia 品牌播放器
  * [wormhol.org](https://www.wormhol.org/)  — 简单的文件共享服务. 与任意数量的同伴共享高达 5GB 的无限文件.
  * [zoom.us](https://zoom.us/)  — 安全视频和网络会议，提供附加组件. 免费限时40分钟
  * [shtab.app](https://shtab.app/) - 项目管理服务，通过基于人工智能的跟踪器，使办公室协作和远程透明化.
  * [Zulip](https://zulip.com/)  — 通过独特的类似电子邮件的线程模型进行实时聊天. 免费计划包括 10,000 条搜索历史消息和高达 5 GB 的文件存储空间. 它还提供可自托管的开源版本.
  * [robocorp.com](https://robocorp.com)  - 用于为自动化运营提供动力的开源堆栈. 免费试用云功能并实施简单的自动化. 机器人工作 240 分钟/月，助手运行 10 次，存储空间 100 MB.
  * [Fleep.io](https://fleep.io/)  — Fleep 是 Slack 的替代品. 它为小型团队提供免费计划，具有完整的消息历史记录、无限的 1:1 对话、1 组对话和 1 GB 文件存储空间.
  * [Chanty.com](https://chanty.com/)  — Chanty 是 Slack 的另一种替代品. 它为小型团队（最多 10 人）提供永久免费计划，提供无限的公共和私人对话、可搜索的历史记录、无限的 1:1 音频通话、无限的语音消息、10 个集成以及每个团队 20 GB 的存储空间.
  * [ruttl.com](https://ruttl.com/) — 最好的一体化反馈工具，用于收集数字反馈并审阅网站、PDF 和图像.
  * [Mattermost](https://mattermost.com/)  — 技术团队的安全协作. 免费计划，包含无限频道、剧本、看板、用户、10GB 存储空间等.
  * [Webvizio](https://webvizio.com) — 网站反馈工具、网站审查软件和错误报告工具，用于直接在实时网站和 Web 应用程序、图像、PDF 和设计文件上简化任务的 Web 开发协作.


## CMS

  * [acquia.com](https://www.acquia.com/)  — Drupal 站点的托管. 开发者免费套餐. 还提供免费开发工具（例如 Acquia Dev Desktop）
  * [Contentful](https://www.contentful.com/)  — 无头 CMS. 云中的内容管理和交付 API. 附带 1 个免费社区空间，其中包括 5 个用户、25K 条记录、48 种内容类型、2 个区域设置.
  * [Cosmic](https://www.cosmicjs.com/)  — 无头 CMS 和 API 工具包. 为开发人员提供免费的个人计划.
  * [Crystallize](https://crystallize.com)  — 具有电子商务支持的无头 PIM. 内置 GraphQL API. 免费版本包括无限用户、1000 个目录项、5 GB/月带宽和 25k/月 API 调用.
  * [DatoCMS](https://www.datocms.com/)  - 为小型项目提供免费套餐.  DatoCMS 是一个基于 GraphQL 的 CMS. 在较低层，您每月有 10 万次通话.
  * [Directus](https://directus.io)  — 无头 CMS. 一个完全免费的开源平台，用于管理本地或云端的资产和数据库内容. 没有限制或付费墙.
  * [Forestry.io](https://forestry.io/)  — 无头 CMS. 为您的编辑提供 Git 的力量. 轻松创建和编辑基于 Markdown 的内容. 附带三个免费网站，其中包括 3 个编辑器和即时预览. 与 Netlify/GitHubpages/ 其他地方托管的博客集成
  * [FrontAid](https://frontaid.io/)  — 无头 CMS，将 JSON 内容直接存储在您自己的 Git 存储库中. 无限制.
  * [kontent.ai](https://www.kontent.ai)  - 内容即服务平台，为您提供无头 CMS 的所有优势，同时为营销人员提供支持. 开发人员计划为 2 个用户提供无限的项目，每个用户有 2 个环境、500 个内容项、2 种语言（带交付和管理 API）以及自定义元素支持. 更大的计划可满足您的需求.
  * [Prismic](https://www.prismic.io/)  — 无头 CMS. 具有完全托管和可扩展 API 的内容管理界面. 社区计划为 1 位用户提供无限的 API 调用、文档、自定义类型、资产和区域设置. 您下一个项目所需的一切. 更大的免费计划可用于开放内容/开源项目.
  * [Sanity.io](https://www.sanity.io/)  - 结构化内容平台，配备开源编辑环境和实时托管数据存储. 无限的项目. 无限的管理员用户、3 个非管理员用户、2 个数据集、500K API CDN 请求、10GB 带宽、每个项目免费包含 5GB 资源.
  * [sensenet](https://sensenet.com)  - API 优先的无头 CMS 为各种规模的企业提供企业级解决方案. 开发人员计划提供 3 个用户、500 个内容项、3 个内置角色、25+5 种内容类型、完全可访问的 REST API、文档预览生成和 Office Online 编辑.
  * [GatsbyjsCMS](https://www.gatsbyjs.com/)  - Gatsby 是一个快速、灵活的框架，使使用任何 CMS、API 或数据库构建网站再次变得有趣. 构建和部署无头网站，以吸引更多流量、更好地转化并赚取更多收入！
  * [Hygraph](https://hygraph.com/)  - 为小型项目提供免费套餐.  GraphQL 第一个 API. 从传统解决方案转向 GraphQL 原生 Headless CMS，并首先提供全渠道内容 API.
  * [Squidex](https://squidex.io/)  - 为小型项目提供免费套餐. 首先是 API/GraphQL. 开源，基于事件源（自动处理每个更改）.
  * [InstaWP](https://instawp.com/)  - 在几秒钟内启动 WordPress 网站. 免费套餐包含：5 个活动站点、500 MB 空间、48 小时站点过期.


## Code Generation

  * [Appinvento](https://appinvento.io/)  — AppInvento 是一款免费的无代码应用程序构建器. 在自动生成的后端代码中，用户可以完全访问源代码以及无限的API和路由，从而可以进行广泛的集成. 免费计划包括三个项目、五个表格和一个 Google 插件.
  * [DhiWise](https://www.dhiwise.com/) — 利用 DhiWise 的创新代码生成技术，将 Figma 设计无缝转化为动态 Flutter 和 React 应用程序，优化您的工作流程并帮助您比以往更快地打造卓越的移动和 Web 体验.
  * [Codeium](https://www.codeium.com/)  — Codeium 是一款免费的人工智能代码完成工具. 它支持 20 多种编程语言（Python、JavaScript、Java、TypeScript、PHP、C/C++、Go 等），并与所有主要的独立和 Web IDE 集成.
  * [tabnine.com](https://www.tabnine.com/)  — Tabnine 通过提供从世界上所有代码中学到的见解，帮助开发人员更快地创建更好的软件. 插件可用.


## Code Quality

  * [beanstalkapp.com](https://beanstalkapp.com/) — 编写、审查和部署代码的完整工作流程），1 个用户的免费帐户和 1 个具有 100 MB 存储空间的存储库
  * [browserling.com](https://www.browserling.com/) — 实时交互式跨浏览器测试，在 Vista 下以 1024 x 768 分辨率与 MS IE 9 进行仅 3 分钟的免费会话
  * [codacy.com](https://www.codacy.com/) — PHP、Python、Ruby、Java、JavaScript、Scala、CSS 和 CoffeeScript 的自动代码审查，免费提供无限的公共和私人存储库
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev)  - 用于 DevOps 的自动化基础设施即代码审查工具与 GitHub、Bitbucket 和 GitLab（甚至是自托管）集成. 除了标准语言之外，它还分析 Ansible、Terraform、CloudFormation、Kubernetes 等.  （开源免费）
  * [CodeBeat](https://codebeat.co)  — 可用于多种语言的自动代码审查平台. 通过 Slack 和电子邮件集成，公共存储库永久免费.
  * [codeclimate.com](https://codeclimate.com/)  — 自动代码审查，免费开放源代码和无限的组织拥有的私人存储库（最多 4 个合作者）. 学生和机构也免费.
  * [codecov.io](https://codecov.io/) — 代码覆盖率工具 (SaaS)，免费开源和 1 个免费私人存储库
  * [CodeFactor](https://www.codefactor.io)  — Git 的自动代码审查. 免费版本包括无限用户、无限公共存储库和 1 个私人存储库.
  * [codescene.io](https://codescene.io/)  - CodeScene 根据开发人员如何使用代码来确定技术债务的优先级，并可视化团队耦合和系统掌握等组织因素. 免费开源.
  * [coveralls.io](https://coveralls.io/) — 显示测试覆盖率报告，免费开源
  * [dareboost](https://dareboost.com) - 每月 5 份关于网络性能、可访问性、安全性的免费分析报告
  * [deepcode.ai](https://www.deepcode.ai)  — DeepCode 基于 AI 发现错误、安全漏洞、性能和 API 问题.  DeepCode 的分析速度使我们能够实时分析您的代码，并在您点击 IDE 中的保存按钮时提供结果. 支持的语言包括 Java、C/C++、JavaScript、Python 和 TypeScript. 与 GitHub、BitBucket 和 GitLab 集成. 对于开源和私人存储库免费，最多可免费供 30 名开发人员使用.
  * [deepscan.io](https://deepscan.io) — 高级静态分析，用于自动查找 JavaScript 代码中的运行时错误，免费开源
  * [DeepSource](https://deepsource.io/)  - DeepSource 不断分析源代码更改，查找并修复按安全性、性能、反模式、错误风险、文档和风格分类的问题. 与 GitHub、GitLab 和 Bitbucket 的本机集成.
  * [eversql.com](https://www.eversql.com/) — EverSQL - The #1 platform for database optimization. Gain critical insights into your database and SQL queries, auto-magically.
  * [gerrithub.io](https://review.gerrithub.io/) — 免费的 GitHub 存储库的 Gerrit 代码审查
  * [gocover.io](https://gocover.io/) — 任何的代码覆盖率 [Go](https://golang.org/) 包裹
  * [goreportcard.com](https://goreportcard.com/) — Go 项目的代码质量，免费开源
  * [gtmetrix.com](https://gtmetrix.com/) — 优化网站的报告和全面建议
  * [holistic.dev](https://holistic.dev/) - The #1 static code analyzer for Postgresql optimization. Performance, security, and architect database issues automatic detection service
  * [houndci.com](https://houndci.com/) — GitHub 承诺关于代码质量的评论，免费开源
  * [Moderne.io](https://app.moderne.io)  — 自动源代码重构.  Moderne 提供框架迁移、带有修复功能的代码分析以及无与伦比的大规模代码转换，因此开发人员可以将时间花在构建新事物上，而不是维护旧事物. 免费开源.
  * [reviewable.io](https://reviewable.io/) — GitHub 存储库的代码审查，免费用于公共或个人存储库
  * [parsers.dev](https://parsers.dev/) - 抽象语法树解析器和中间表示编译器作为服务
  * [scan.coverity.com](https://scan.coverity.com/) — Static code analysis for Java, C/C++, C# and JavaScript, free for Open Source
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 持续检查平台，免费开源
  * [semanticdiff.com](https://app.semanticdiff.com/) - 用于 GitHub 拉取请求和提交的编程语言感知差异，对公共存储库免费
  * [shields.io](https://shields.io) — 开源项目的质量元数据徽章
  * [sonarcloud.io](https://sonarcloud.io) — Automated source code analysis for Java, JavaScript, C/C++, C#, VB.NET, PHP, Objective-C, Swift, Python, Groovy and even more languages, free for Open Source
  * [SourceLevel](https://sourcelevel.io/)  — 自动代码审查和团队分析. 对于开源和最多 5 名合作者的组织免费.
  * [Viezly](https://viezly.com/)  - 增强的代码审查工具，更轻松地阅读和导航代码. 免费开源，免费供个人使用.
  * [webceo.com](https://www.webceo.com/) — SEO 工具，但也有代码验证和不同类型的建议
  * [zoompf.com](https://zoompf.com/) — 修复网站的性能，详细分析


## Code Search and Browsing

  * [libraries.io](https://libraries.io/) — 32 个不同的包管理器的搜索和依赖项更新通知，免费开源
  * [Namae](https://namae.dev/) - 在 github、gitlab、heroku、netlify 等各种网站上搜索您的项目名称的可用性.
  * [searchcode.com](https://searchcode.com/) — 全面的基于文本的代码搜索，免费开源
  * [sourcegraph.com](https://about.sourcegraph.com/) — Java、Go、Python、Node.js 等，代码搜索/交叉引用，免费开源
  * [tickgit.com](https://www.tickgit.com/) — 显示“TODO”注释（和其他标记）以识别值得返回以进行改进的代码区域.
  * [CodeKeep](https://codekeep.io)  - Google Keep 代码片段. 组织、发现和共享代码片段，具有强大的代码屏幕截图工具，具有预设模板和链接功能.


## CI and CD

  * [AccessLint](https://github.com/marketplace/accesslint)  — AccessLint 将自动化 Web 可访问性测试引入您的开发工作流程. 它是免费的，用于开源和教育目的.
  * [appcircle.io](https://appcircle.io)  — 适用于 iOS 和 Android 的自动化移动 CI/CD/CT，带有在线设备模拟器.  20 分钟构建超时（开源为 60 分钟），单并发免费.
  * [appveyor.com](https://www.appveyor.com/) — 适用于 Windows 的 CD 服务，免费开源
  * [Argonaut](https://argonaut.dev/)  - 只需几分钟即可在您的云上部署应用程序和基础设施. 支持 Kubernetes 和 Lambda 环境上的自定义和第三方应用程序部署. 免费套餐允许 5 个环境和 2 个用户无限应用程序和部署.
  * [bitrise.io](https://www.bitrise.io/)  — 适用于本机或混合移动应用程序的 CI/CD. 每月 200 次免费构建，构建时间为 10 分钟，团队成员为两名.  OSS 项目的构建时间为 45 分钟、+1 并发性和无限的团队规模.
  * [buddy.works](https://buddy.works/) — 一个 CI/CD，包含 5 个免费项目和 1 个并发运行（120 次执行/月）
  * [buddybuild.com](https://www.buddybuild.com/) — 在一个无缝的迭代系统中构建、部署 iOS 和 Android 应用程序并收集反馈
  * [Buildkite](https://buildkite.com)
    * 管道：免费开发人员层包括无限并发、最多 3 个用户、每月 5000 分钟工作时间和 30 天构建保留，以及更多免费包含的开源项目
    * [Test Analytics](https://buildkite.com/test-analytics)  — 充分利用您的测试套件，适用于任何 CI 平台. 免费开发人员级别包括每月 10 万次测试执行，以及更多针对开源项目的免费内容.
  * [circleci.com](https://circleci.com/) — Free for one concurrent build
  * [cirrus-ci.org](https://cirrus-ci.org) - 免费用于公共 GitHub 存储库
  * [codefresh.io](https://codefresh.io) — 终身免费计划：1 个构建、1 个环境、共享服务器、无限制的公共存储库
  * [codemagic.io](https://codemagic.io/) - 每月免费 500 分钟构建时间
  * [codeship.com](https://codeship.com/) — 每月 100 个私人构建，5 个私人项目，开源无限制
  * [deploybot.com](https://www.deploybot.com/) — 1 个存储库，包含 10 个部署，免费开源
  * [deployhq.com](https://www.deployhq.com/) — 1 个项目，每日部署 10 次（每月 30 分钟构建时间）
  * [drone](https://cloud.drone.io/) - Drone Cloud 使开发人员能够跨多种架构运行持续交付管道 - 包括 x86 和 Arm（32 位和 64 位） - 全部集中在一处
  * [LayerCI](https://layerci.com)  — 全栈项目的 CI.  1 个全栈预览环境，配备 5GB 内存和 3 个 CPU.
  * [semaphoreci.com](https://semaphoreci.com/) — 免费开源，每月 100 个私人构建
  * [Squash Labs](https://www.squash.io/) — 为每个分支创建一个虚拟机，并使您的应用程序可以通过唯一的 URL、无限的公共和私人存储库、高达 2 GB 的虚拟机大小来使用.
  * [styleci.io](https://styleci.io/) — 仅限公共 GitHub 存储库
  * [Mergify](https://mergify.io) — GitHub 的工作流程自动化和合并队列 — 免费用于公共 GitHub 存储库
  * [Make](https://www.make.com/en)  — 工作流程自动化工具可让您使用 UI 连接应用程序并自动化工作流程，它支持许多应用程序和最流行的 API. 对公共 GitHub 存储库免费，并且免费套餐具有 100 Mb、1000 次操作和 15 分钟的最小间隔.
  * [Spacelift](https://spacelift.io/)  - 基础设施即代码的管理平台. 免费计划功能：IaC 协作、Terraform 模块注册表、ChatOps 集成、开放策略代理的持续资源合规性、使用 SAML 2.0 的 SSO 以及对公共工作人员池的访问：每月最多 200 分钟
  * [microtica.com](https://microtica.com/)  - 使用现成的基础设施组件启动环境，在 AWS 上免费部署应用程序并支持您的生产工作负载. 免费套餐包括 1 个环境（在您的 AWS 账户上）、2 个 Kubernetes 服务、每月 100 分钟的构建时间以及每月 20 次部署.



## Testing

  * [Applitools.com](https://applitools.com/)  — 适用于网络、本机移动和桌面应用程序的智能视觉验证. 与几乎所有自动化解决方案（如 Selenium 和 Karma）和远程运行程序（Sauce Labs、浏览器堆栈）集成. 免费开源. 单个用户的免费套餐，每周检查点有限.
  * [Appetize](https://appetize.io)  — 直接在浏览器中在此基于云的 Android 手机/平板电脑模拟器和 iPhone/iPad 模拟器上测试您的 Android 和 iOS 应用程序. 免费套餐包括每月 1 个并发会话，使用时间为 100 分钟. 应用程序大小没有限制.
  * [Apptim](https://apptim.com)  — 一种移动测试工具，使没有性能工程技能的人能够评估应用程序的性能和用户体验 (UX). 使用您自己的设备的桌面版是 100% 免费的，并且在 iOS 和 Android 上进行无限测试.
  * [Bencher](https://bencher.dev/)  - 一套连续基准测试工具，旨在捕获 CI 中的性能回归. 所有公共项目免费.
  * [Bird Eats Bug](https://www.birdeatsbug.com/)  — 更快（更好）地报告错误. 使用 Bird 浏览器扩展程序录制您的屏幕，它会自动捕获工程师调试所需的技术数据. 免费套餐适合小型团队.
  * [BugBug](https://bugbug.io/)  - 用于 Web 应用程序的轻量级测试自动化工具. 易于学习，不需要编码. 您可以在自己的计算机上免费运行无限测试. 只需支付额外的月费，您还可以获得云监控和 CI/CD 集成.
  * [lambdatest.com](https://www.lambdatest.com/) - 对 selenium 和 cypress 进行手动、视觉、屏幕截图和自动浏览器测试， [free for Open Source](https://www.lambdatest.com/open-source-cross-browser-testing-tool)
  * [browserstack.com](https://www.browserstack.com/) - 手动和自动浏览器测试， [free for Open Source](https://www.browserstack.com/open-source?ref=pricing)
  * [checkbot.io](https://www.checkbot.io/)  — 浏览器扩展程序，用于测试您的网站是否遵循 50 多个 SEO、速度和安全最佳实践. 小型网站的免费套餐.
  * [checklyhq.com](https://checklyhq.com)  - Checkly 是现代堆栈的 API 和 E2E 监控平台：可编程、灵活且喜爱 JavaScript. 为开发者提供慷慨的免费套餐.
  * [crossbrowsertesting.com](https://crossbrowsertesting.com) - 云中的手动、可视化和 Selenium 浏览器测试 - [free for Open Source](https://crossbrowsertesting.com/open-source)
  * [cypress.io](https://www.cypress.io/)  - 对浏览器中运行的任何内容进行快速、简单且可靠的测试.  Cypress Test Runner 始终免费且开源，没有任何限制和限制.  Cypress Dashboard 对于最多 5 个用户的开源项目是免费的.
  * [Cypress Recorder by Preflight](https://cypress.preflight.com/)  - 在浏览器上创建人工智能驱动的赛普拉斯测试/POM 模型. 除了人工智能部分之外，它是开源的. 每月可免费进行 5 次测试创建，包括自我修复脚本、电子邮件和可视化测试.
  * [everystep-automation.com](https://www.everystep-automation.com/) — 记录和重播在网络浏览器中执行的所有步骤并创建脚本，...免费且选项较少
  * [Gremlin](https://www.gremlin.com/gremlin-free-software)  — Gremlin 的混沌工程工具使您能够安全、可靠、简单地将故障注入系统中，以便在弱点导致客户面临的问题之前找到弱点.  Gremlin Free 提供对最多 5 个主机或容器的关闭和 CPU 攻击的访问权限.
  * [gridlastic.com](https://www.gridlastic.com/) — Selenium Grid 测试，免费计划最多 4 个同步 Selenium 节点/10 个网格启动/4,000 测试分钟/月
  * [katalon.com](https://katalon.com) - 提供一个测试平台，可以帮助各种规模的团队达到不同的测试成熟度，包括Katalon Studio、TestOps（+免费可视化测试）、TestCloud 和 Katalon Recorder.
  * [Keploy](https://keploy.io/)  - Keploy 是面向开发人员的功能测试工具包. 它通过记录真实的 API 调用来生成 API 的 E2E 测试 (KTests) 以及模拟或存根 (KMocks). 它是免费的开源软件.
  * [loadmill.com](https://www.loadmill.com/)  - 通过分析网络流量自动创建 API 和负载测试. 每月免费模拟最多 50 个并发用户，最多 60 分钟.
  * [preflight.com](https://preflight.com) - No-code automated web testing. Record tests on your browser that are resilient to UI changes and run them on Windows machines. Integrate with your CI/CD. The free plan includes 50 test runs per month with video, HTML sessions and more.
  * [percy.io](https://percy.io)  - 将视觉测试添加到任何 Web 应用程序、静态站点、样式指南或组件库. 无限的团队成员、演示应用程序和无限的项目、每月 5,000 个快照.
  * [saucelabs.com](https://saucelabs.com/)  — 跨浏览器测试、Selenium 测试和移动测试. 免费计划包括每周 2000 个积分. 他们还为选定的开源项目提供免费许可证，可以申请 [here](https://opensource.saucelabs.com/).
  * [snippets.uilicious.com](https://snippets.uilicious.com)  - 它类似于 CodePen，但用于跨浏览器测试.  UI-licious 允许编写用户故事等测试，并提供免费平台 - UI-licious Snippets - 允许您在 Chrome 上免费运行无限数量的测试，无需注册，每次测试运行最多 3 分钟. 发现错误？ 您只需将唯一的 URL 复制到您的测试中，即可向您的开发人员准确展示如何重现该错误.
  * [testingbot.com](https://testingbot.com/) — Selenium 浏览器和设备测试， [free for Open Source](https://testingbot.com/open-source)
  * [Testspace.com](https://testspace.com/)  - 用于发布自动化测试结果的仪表板和用于使用 GitHub 将手动测试作为代码实施的框架. 服务是 [free for Open Source](https://github.com/marketplace/testspace-com) 每月有 450 个结果.
  * [tesults.com](https://www.tesults.com) — Test results reporting and test case management. Integrates with popular test frameworks. Open Source software developers, individuals, educators, and small teams getting started can request discounted and free offerings beyond basic free project.
  * [websitepulse.com](https://www.websitepulse.com/tools/) — 各种免费网络和服务器工具.
  * [qase.io](https://qase.io)  - 开发和质量保证团队的测试管理系统. 管理测试用例、编写测试运行、执行测试运行、跟踪缺陷并衡量影响. 免费套餐包括所有核心功能，可用于附件的空间为 500Mb，最多可供 3 个用户使用.
  * [knapsackpro.com](https://knapsackpro.com)  - 在任何 CI 提供商上通过最佳测试套件并行化来加快测试速度. 在并行 CI 节点上拆分 Ruby、JavaScript 测试以节省时间. 最多 10 分钟测试文件的免费计划和开源项目的免费无限制计划.
  * [webhook.site](https://webhook.site)  - 使用自定义 URL 验证 Webhook、出站 HTTP 请求或电子邮件. 临时 URL 和电子邮件地址始终免费.
  * [Vaadin](https://vaadin.com)  — 使用 Java 或 TypeScript 构建可扩展的 UI，并使用集成工具、组件和设计系统来更快地迭代、更好地设计并简化开发过程. 无限项目，5 年免费维护.


## Security and PKI

  * [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — 发现网络中受损的系统
  * [atomist.com](https://atomist.com/)  — 一种更快速、更方便的方式来自动化各种开发任务. 现在处于测试阶段.
  * [Bridgecrew](https://bridgecrew.io/) — 由开源工具提供支持的基础设施即代码 (IaC) 安全性 — [Checkov](https://github.com/bridgecrewio/checkov) .  Bridgecrew 核心平台免费提供最多 50 个 IaC 资源.
  * [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services (AWS) 安全性与合规性审计和监控
  * [CodeNotary.io](https://www.codenotary.io/) — 开源平台，具有不可磨灭的证据来公证代码、文件、目录或容器
  * [crypteron.com](https://www.crypteron.com/) — 云优先、开发人员友好的安全平台可防止 .NET 和 Java 应用程序中的数据泄露
  * [CyberChef](https://gchq.github.io/CyberChef/)  — 一个简单、直观的网络应用程序，用于分析和解码/编码数据，而无需处理复杂的工具或编程语言. 就像密码学和加密领域的瑞士军刀一样. 所有功能均可免费使用，无限制. 开源，如果您想自行托管.
  * [DAS](https://signup.styra.com/) — Styra DAS 免费、全生命周期策略管理，用于创建、部署和管理开放策略代理 (OPA) 授权
  * [Datree](https://www.datree.io/) — 开源 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及组织的策略来防止 Kubernetes 错误配置
  * [Dependabot](https://dependabot.com/) 自动更新 Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven 和 Gradle）、.NET、Go、Elm、Docker、Terraform、Git 子模块和 GitHub Actions.
  * [DJ Checkup](https://djcheckup.com)  — 使用这个免费的自动化检查工具扫描您的 Django 站点是否存在安全漏洞. 从 Pony Checkup 网站分叉.
  * [Doppler](https://doppler.com/)  — 用于应用程序机密和配置的通用机密管理器，支持同步到各种云提供商.  5 位用户免费，具有基本的访问控制.
  * [Dotenv](https://dotenv.org/)  — 快速、安全地同步您的 .env 文件. 停止通过 Slack 和电子邮件等不安全渠道共享您的 .env 文件，再也不会丢失重要的 .env 文件. 最多 3 名队友免费.
  * [GitGuardian](https://www.gitguardian.com)  — 通过自动秘密检测和修复，确保源代码中的秘密不被泄露. 扫描您的 git 存储库以查找 350 多种类型的机密和敏感文件 - 对于个人和 25 名或更少开发人员的团队免费.
  * [Have I been pwned?](https://haveibeenpwned.com) — 用于获取违规信息的 REST API.
  * [hostedscan.com](https://hostedscan.com)  — 针对 Web 应用程序、服务器和网络的在线漏洞扫描器. 每月 10 次免费扫描.
  * [Infisical](https://infisical.com/)  — 开源平台可让您管理整个团队和基础设施中的开发人员机密：从本地开发到临时/生产第三方服务. 最多 5 名开发者免费.
  * [Internet.nl](https://internet.nl) — 测试现代互联网标准，如 IPv6、DNSSEC、HTTPS、DMARC、STARTTLS 和 DANE
  * [keychest.net](https://keychest.net) - 通过集成 CT 数据库进行 SSL 到期管理和证书购买
  * [letsencrypt.org](https://letsencrypt.org/) — 免费 SSL 证书颁发机构，其证书受到所有主要浏览器的信任
  * [meterian.io](https://www.meterian.io/)  - 监控 Java、Javascript、.NET、Scala、Ruby 和 NodeJS 项目的依赖项中的安全漏洞. 一个私人项目免费，开源项目不受限制.
  * [Mozilla Observatory](https://observatory.mozilla.org/) — Find and fix security vulnerabilities in your site.
  * [opswat.com](https://www.opswat.com/) — 计算机、设备、应用程序、配置等的安全监控...免费 25 个用户和 30 天历史用户.
  * [openapi.security](https://openapi.security/)  - 免费工具可快速检查任何基于 OpenAPI / Swagger 的 API 的安全性. 无需注册.
  * [pyup.io](https://pyup.io)  — 监控 Python 依赖项是否存在安全漏洞并自动更新. 一个私人项目免费，开源项目不受限制.
  * [qualys.com](https://www.qualys.com/community-edition) — 查找 Web 应用程序漏洞，审核 OWASP 风险
  * [reCAPTCHAMe](https://recaptchame.com/)  — 免费的 reCAPTCHA 和 hCAPTCHA 后端服务. 无需服务器端编码. 适用于静态网站.
  * [report-uri.io](https://report-uri.io/) — CSP 和 HPKP 违规报告
  * [ringcaptcha.com](https://ringcaptcha.com/) — 使用电话号码作为 ID 的工具，免费提供
  * [seclookup.com](https://seclookup.com/)  - Seclookup API可以丰富SIEM中的域威胁指标，提供全面的域名信息，提高威胁检测和响应. 免费获得 50K 次查找 [here](https://account.seclookup.com/).
  * [snyk.io](https://snyk.io)  — 可以查找并修复开源依赖项中的已知安全漏洞. 对开源项目进行无限的测试和修复. 您的私人项目每月仅限 200 次测试.
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) — 对任何 SSL Web 服务器的配置进行非常深入的分析
  * [SOOS](https://soos.io)  - 免费、无限制的开源项目 SCA 扫描. 在发布前检测并修复安全威胁. 通过简单有效的解决方案保护您的项目.
  * [StackHawk](https://www.stackhawk.com/) 在整个管道中自动进行应用程序扫描，以在安全漏洞投入生产之前找到并修复它们. 单个应用程序的无限扫描和环境.
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) - 免费网站安全检查和恶意软件扫描程序
  * [Protectumus](https://protectumus.com)  - 适用于 PHP 的免费网站安全检查、网站防病毒和服务器防火墙 (WAF). 免费套餐中注册用户的电子邮件通知.
  * [TestTLS.com](https://testtls.com) - 测试 SSL/TLS 服务的安全服务器配置、证书、链等.不限于 HTTPS.
  * [threatconnect.com](https://threatconnect.com)  — 威胁情报：它是为开始了解网络威胁情报的个人研究人员、分析师和组织而设计的. 释放最多 3 个用户
  * [tinfoilsecurity.com](https://www.tinfoilsecurity.com/)  — 自动漏洞扫描. 免费计划允许每周进行 XSS 扫描
  * [Ubiq Security](https://ubiqsecurity.com/)  — 使用 3 行代码和自动密钥管理来加密和解密数据.  1 个应用程序免费，每月最多 1,000,000 次加密.
  * [Virgil Security](https://virgilsecurity.com/)  — 用于在数字解决方案中实施端到端加密、数据库保护、物联网安全等的工具和服务. 对于最多 250 个用户的应用程序免费.
  * [Virushee](https://virushee.com/)  — 面向隐私的文件/数据扫描，由混合启发式和人工智能辅助引擎提供支持. 可以使用内部动态沙箱分析. 每个文件上传限制为 50MB
  * [Escape GraphQL Quickscan](https://escape.tech/)  - 对 GraphQL 端点进行一键安全扫描. 免费，无需登录.



## Authentication, Authorization and User Management

  * [Aserto](https://www.aserto.com)  - 细粒度授权作为应用程序和 API 的服务. 释放最多 1000 个 MAU 和 100 个授权者实例.
  * [asgardeo.io](https://wso2.com/asgardeo)  - 无缝集成 SSO、MFA、无密码身份验证等. 包括前端和后端应用程序的 SDK. 免费最多 1000 个 MAU 和 5 个身份提供商.
  * [Auth0](https://auth0.com/)  — 托管 SSO. 最多 7000 名活跃用户和 2 个社交身份提供商.
  * [Authgear](https://www.authgear.com)  - 只需几分钟即可将无密码、OTP、2FA、SSO 引入您的应用程序. 包括所有前端. 释放最多 5000 个 MAU.
  * [Authress](https://authress.io/)  — 身份验证登录和访问控制，任何项目的无限身份提供商. 脸书、谷歌、推特等. 前 1000 次 API 调用免费.
  * [Authy](https://authy.com)  - 多个设备上的双因素身份验证 (2FA)，并带有备份.  Google 身份验证器的直接替代品. 最多 100 次成功的身份验证免费.
  * [Clerk](https://clerk.com)  — 用户管理、身份验证、带有预构建 UI 组件的 2FA/MFA. 免费释放最多 5,000 名每月活跃用户.
  * [Descope](https://www.descope.com/) — 高度可定制的 AuthN 流程，同时采用无代码和 API/SDK 方法，每月免费 7,500 个活跃用户，50 个租户（最多 5 个 SAML/SSO 租户）.
  * [duo.com](https://duo.com/)  — 网站或应用程序的双因素身份验证 (2FA).  10 个用户免费，所有身份验证方法，无限制，集成，硬件令牌.
  * [Jumpcloud](https://jumpcloud.com/)  — 提供类似于 Azure AD 的目录即服务、用户管理、单点登录和 RADIUS 身份验证. 最多 10 位用户免费.
  * [logintc.com](https://www.logintc.com/) — 通过推送通知进行双因素身份验证 (2FA)，免费供 10 个用户使用、VPN、网站和 SSH
  * [MojoAuth](https://mojoauth.com/) - MojoAuth 可以在几分钟内轻松地在您的网络、移动设备或任何应用程序上实施无密码身份验证.
  * [Okta](https://developer.okta.com/signup/)  — 用户管理、认证和授权. 每月最多 100 名活跃用户免费.
  * [onelogin.com](https://www.onelogin.com/) — 身份即服务 (IDaaS)、单点登录身份提供商、云 SSO IdP、3 个公司应用程序和 5 个个人应用程序、无限用户
  * [Ory](https://ory.sh/)  - AuthN/AuthZ/OAuth2.0/零信任托管安全平台. 具有所有安全功能的永久免费开发者帐户、无限的团队成员、200 个每日活跃用户和 25k/月 权限检查.
  * [SuperTokens](https://supertokens.com/)  - 原生集成到您的应用程序中的开源用户身份验证 - 使您能够快速入门，同时控制用户和开发人员体验. 最多 5000 个月活跃用户免费.
  * [Warrant](https://warrant.dev/)  — 为您的应用程序托管企业级授权和访问控制服务. 免费套餐包括每月 100 万个 API 请求和 1,000 个授权规则.
  * [ZITADEL Cloud](https://zitadel.com)  — 适合您并支持多租户 (B2B) 使用案例的交钥匙用户和访问管理. 免费最多可处理 25&#39;000 个经过身份验证的请求，并具有所有安全功能（OTP、无密码、策略等无需付费）.
  * [PropelAuth](https://propelauth.com) — 只需几行代码即可立即向任何规模的公司销售，免费最多 200 个用户和 10k 事务电子邮件（带有水印品牌：“Powered by PropelAuth”）.



## Management System

  * [bitnami.com](https://bitnami.com/)  — 在 IaaS 上部署准备好的应用程序. 免费管理 1 个 AWS 微型实例
  * [Esper](https://esper.io)  — 适用于具有 DevOps 的 Android 设备的 MDM 和 MAM.  100 台设备免费，拥有 1 个用户许可证和 25 MB 应用程序存储空间.
  * [jamf.com](https://www.jamf.com/) — iPad、iPhone 和 Mac 的设备管理，3 台设备免费
  * [Miradore](https://miradore.com) — Device Management service. Stay up-to-date with your device fleet and secure an unlimited number of devices for free. Free plan offers basic features.
  * [moss.sh](https://moss.sh)  - 帮助开发人员部署和管理他们的网络应用程序和服务器. 每月免费最多 25 次 git 部署
  * [runcloud.io](https://runcloud.io/)  - 主要针对 PHP 项目的服务器管理. 最多 1 台服务器免费.
  * [ploi.io](https://ploi.io/)  - 服务器管理工​​具可轻松管理和部署您的服务器和站点.  1台服务器免费.


## Messaging and Streaming

  * [Ably](https://www.ably.com/)  - 具有存在性、持久性和有保证的传递的实时消息传递服务. 免费计划包括每月 300 万条消息、100 个峰值连接和 100 个峰值通道.
  * [cloudamqp.com](https://www.cloudamqp.com/)  — RabbitMQ 即服务.  Little Lemur 计划：每月最多 100 万条消息，最多 20 个并发连接，最多 100 个队列，最多 10,000 条排队消息，不同可用区中的多个节点
  * [connectycube.com](https://connectycube.com)  - 无限的聊天消息、p2p 语音和视频通话、文件附件和推送通知. 对于月活跃用户数不超过 20K 的应用程序免费.
  * [courier.com](https://www.courier.com/)  — 用于推送、应用内、电子邮件、聊天、短信和其他消息传递渠道的单一 API，具有模板管理和其他功能. 免费计划包括每月 10,000 条消息.
  * [HiveMQ](https://www.hivemq.com/mqtt-cloud-broker/)  - 将您的 MQTT 设备连接到云原生 IoT 消息传递代理. 永久免费连接最多 100 个设备（无需信用卡）.
  * [knock.app](https://knock.app)  – 开发人员的通知基础设施. 通过单个 API 调用发送到多个渠道，例如应用内、电子邮件、短信、Slack 和推送. 免费计划包括每月 10,000 条消息.
  * [pusher.com](https://pusher.com/)  — 实时消息服务. 每天免费最多 100 个并发连接和 200,000 条消息
  * [scaledrone.com](https://www.scaledrone.com/)  — 实时消息服务. 每天免费最多 20 个并发连接和 100,000 个事件
  * [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io) 作为一项服务. 全球、AWS、GCP 和 Azure. 永久免费，每月 4k 消息大小、50 个活动连接和 5GB 数据.
  * [cloudkarafka.com](https://www.cloudkarafka.com/) - 免费共享Kafka集群，最多5个主题，每个主题10MB数据，数据保留28天.
  * [pubnub.com](https://www.pubnub.com/)  - Swift、Kotlin 和 React 消息传递每月处理 100 万笔交易. 事务可能包含多个消息.
  * [eyeson API](https://developers.eyeson.team/)  - 基于WebRTC（SFU、MCU）的视频通信API服务，构建视频平台. 允许实时数据注入、视频布局、录制、功能齐全的托管 Web UI（快速入门）或自定义 UI 包. 有一个 [free tier for developers](https://apiservice.eyeson.com/api-pricing) 每月 1000 会议分钟.
  * [Upstash Kafka](https://upstash.com/kafka)  - 无服务器 Kafka 云产品，按请求定价. 它有一个免费套餐，每天最多可发送 10000 条消息.
  * [webpushr](https://www.webpushr.com/) - 网络推送通知 - 最多 10,000 名订阅者免费、无限制的推送通知、浏览器内消息传递
  * [Scramjet Cloud Platform Beta](https://www.scramjet.org/#join-beta) - 免费测试版中的端到端流处理平台，测试版结束后提供 15 PB 秒的免费计算.


## Log Management

  * [bugfender.com](https://bugfender.com/) — 每天释放多达 100k 日志行，并保留 24 小时
  * [humio.com](https://www.humio.com/) — 免费高达 16 GB/天，保留 7 天
  * [logentries.com](https://logentries.com/) — 每月最多免费 5 GB，保留 7 天
  * [loggly.com](https://www.loggly.com/) — 单个用户免费，200MB/天，保留 7 天
  * [logz.io](https://logz.io/) — 免费高达 1 GB/天，保留 1 天
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-log-management)  — 由 Manage Engine 提供支持的日志管理服务. 免费计划提供 50 GB 存储空间，保留 1 个月.
  * [papertrailapp.com](https://papertrailapp.com/) — 48 小时搜索，7 天存档，50 MB/月
  * [sematext.com](https://sematext.com/logsene) — 免费最多 500 MB/天，保留 7 天
  * [sumologic.com](https://www.sumologic.com/) — 免费最多 500 MB/天，保留 7 天
  * [logflare.app](https://logflare.app/) — 每个应用每月最多可免费使用 12,960,000 个条目，保留 3 天
  * [logtail.com](https://logtail.com/)  — 基于 ClickHouse 的 SQL 兼容日志管理. 每月最多免费 1 GB，保留 3 天.
  * [logzab.com](https://logzab.com/)  — 审计追踪管理系统. 每月免费 1.000 个用户活动日志，保留 1 个月，最多可用于 5 个项目.


## Translation Management

  * [crowdin.com](https://crowdin.com/) — 无限的项目、无限的字符串和开源合作者
  * [gitlocalize.com](https://gitlocalize.com) - 免费且无限制的私人和公共存储库
  * [Lecto](https://lecto.ai/)  - 具有免费层的机器翻译 API（30 个免费请求，每个请求 1000 个翻译字符）. 与 Loco Translate Wordpress 插件集成.
  * [lingohub.com](https://lingohub.com/) — 免费最多 3 个用户，始终免费开源
  * [localazy.com](https://localazy.com) - 免费提供 1000 种源语言字符串、无限语言、无限贡献者、启动和开源交易
  * [Localeum](https://localeum.com) - 免费最多 1000 个字符串、1 个用户、无限语言、无限项目
  * [localizely.com](https://localizely.com/) — 免费开源
  * [Loco](https://localise.biz/) — 免费最多 2000 种翻译、无限制翻译人员、10 种语言/项目、1000 个可翻译资产/项目
  * [oneskyapp.com](https://www.oneskyapp.com/) — 最多 5 个用户的有限免费版，免费开源
  * [POEditor](https://poeditor.com/) — 释放多达 1000 个字符串
  * [SimpleLocalize](https://simplelocalize.io/) - 免费多达 100 个翻译键、无限字符串、无限语言、启动优惠
  * [Texterify](https://texterify.com/) - 单个用户免费
  * [Tolgee](https://tolgee.io) - 免费 SaaS 产品，翻译有限，永久免费的自托管版本
  * [transifex.com](https://www.transifex.com/) — 免费开源
  * [Translation.io](https://translation.io) - 免费开源
  * [Translized](https://translized.com) - 免费最多 1000 个字符串、1 个用户、无限语言、无限项目
  * [webtranslateit.com](https://webtranslateit.com/) — 释放多达 500 个字符串
  * [weblate.org](https://weblate.org/) — It's free for libre projects up to 10,000 string source for the free tier, and Unlimited Self-hosted on-premises.
  * [Free PO editor](https://pofile.net/free-po-editor) — 对所有人免费


## Monitoring

  * [Airbrake.io](https://www.airbrake.io/)  - 开始使用免费的永久错误和性能监控 - 无需信用卡！ 免费试用期结束后，您可以选择升级到付费 Airbrake 计划，或自动转换为终身免费 Airbrake 开发帐户，其中包括 (1) 个用户、(1) 个团队、(2) 个项目、每月 7,500 个错误、50,000 个性能事件和 7 天的数据保留.
  * [Pingmeter.com](https://pingmeter.com/) - 5 uptime monitors with 10 minutes interval. Monitor SSH, HTTP, HTTPS, and any custom TCP ports.
  * [appdynamics.com](https://www.appdynamics.com/) — 24 小时免费指标，应用程序性能管理代理仅限于一种 Java、一种 .NET、一种 PHP 和一种 Node.js
  * [appneta.com](https://www.appneta.com/) — 免费，数据保留 1 小时
  * [appspector.com](https://appspector.com/)  - 任务控制，用于远程 iOS/Android/Flutter 调试. 小流量使用免费（64MB 日志）.
  * [assertible.com](https://assertible.com)  — 自动化 API 测试和监控. 为团队和个人提供免费计划.
  * [checklyhq.com](https://checklyhq.com)  - 为开发人员提供开源 E2E/综合监控和深度 API 监控. 具有 5 个用户和超过 50k 次检查运行的免费计划.
  * [circonus.com](https://www.circonus.com/) — 免费获取 20 个指标
  * [cloudsploit.com](https://cloudsploit.com)  — AWS 安全和配置监控. 免费：无限按需扫描、无限用户、无限存储帐户. 订阅：自动扫描、API访问等.
  * [cronitor.io](https://cronitor.io/)  - 针对 cron 作业、网站、API 等的性能洞察和正常运行时间监控. 具有 5 台显示器的免费套餐.
  * [datadoghq.com](https://www.datadoghq.com/) — 最多 5 个节点免费
  * [deadmanssnitch.com](https://deadmanssnitch.com/)  — 监控 cron 作业.  1 个免费告密者（监控者），如果您推荐其他人注册，则更多
  * [downtimemonkey.com](https://downtimemonkey.com/)  — 60 个正常运行时间监视器，间隔 5 分钟. 电子邮件、Slack 警报.
  * [economize.cloud](https://economize.cloud)  — Economize 通过组织云资源、优化和报告云资源来帮助揭开云基础设施成本的神秘面纱. 每月在 Google Cloud Platform 上消费不超过 5000 美元即可免费.
  * [elastic.co](https://www.elastic.co/solutions/apm)  — 为 JS 开发人员提供即时性能洞察. 免费并保留 24 小时数据
  * [freeboard.io](https://freeboard.io/)  — 免费用于公共项目. 物联网 (IoT) 项目的仪表板
  * [Grafana Cloud](https://grafana.com/products/cloud/)  - Grafana Cloud 是一个可组合的可观察性平台，将指标和日志与 Grafana 集成. 免费：3 个用户、10 个仪表板、100 个警报、Prometheus 和 Graphite 中的指标存储（10,000 个系列，保留 14 天）、Loki 中的日志存储（50 GB 日志，保留 14 天）
  * [healthchecks.io](https://healthchecks.io)  — 监控您的 cron 作业和后台任务. 最多 20 张支票免费.
  * [inspector.dev](https://www.inspector.dev) - A complete Real-Time monitoring dashboard in less than one minute with free forever tier.
  * [instrumentalapp.com](https://instrumentalapp.com) - 美观且易于使用的应用程序和服务器监控，可免费提供多达 500 个指标和 3 小时的数据可见性
  * [keychest.net/speedtest](https://keychest.net/speedtest) - 针对 Digital Ocean 的独立速度测试和 TLS 握手延迟测试
  * [letsmonitor.org](https://letsmonitor.org) - SSL 监控，最多可免费支持 5 个监视器
  * [loader.io](https://loader.io/) — 免费负载测试工具，但有限制
  * [meercode.io](https://meercode.io/)  — Meercode 是 CI/CD 构建的终极监控仪表板. 免费开源和 1 个私有存储库.
  * [netdata.cloud](https://www.netdata.cloud/)  — Netdata 是一个开源工具，旨在收集实时指标.伟大的快速增长的产品.  github上也可以找到！
  * [newrelic.com](https://www.newrelic.com)  — 新的 Relic 可观测平台旨在帮助工程师创建更完美的软件. 从单体应用到无服务器，您可以检测所有内容，然后分析、排除故障并优化整个软件堆栈. 免费套餐提供 100GB/月的免费数据摄取、1 个免费完全访问用户和无限制的免费基本用户.
  * [Middleware.io](https://middleware.io/)  - 中间件可观察性平台提供对应用程序和堆栈的完整可见性，因此您可以大规模监控和诊断问题. 他们有一个供开发社区使用的永久免费计划，允许对最多 1M 日志事件进行日志监控，对最多 2 台主机进行基础设施监控和 APM.
  * [nixstats.com](https://nixstats.com)  - 一台服务器免费. 电子邮件通知、公共状态页面、60 秒间隔等等.
  * [OnlineOrNot.com](https://onlineornot.com/)  - OnlineOrNot 是一个可靠的正常运行时间监视器，适用于基于 JS 的 Web 应用程序和网站.  5 次正常运行时间检查（针对静态网站和 API），间隔 5 分钟，1 次浏览器检查，间隔 15 分钟. 还提供自动公共状态页面（支持第 3 方正常运行时间监控）. 最多 3 位用户免费，通过 Slack、Discord 和电子邮件发出警报.
  * [opsgenie.com](https://www.opsgenie.com/)  — 强大的警报和待命管理功能，可实现始终在线的服务. 释放最多 5 个用户.
  * [paessler.com](https://www.paessler.com/)  — 强大的基础设施和网络监控解决方案，包括警报、强大的可视化功能和基本报告. 释放多达 100 个传感器.
  * [syagent.com](https://syagent.com/) — 非商业免费服务器监控服务、警报和指标.
  * [pagerly.io](https://pagerly.io/) - 在 Slack 上管理待命（与 Pagerduty、OpsGenie 集成）.免费最多 1 个团队（一个团队指一个待命）
  * [pagertree.com](https://pagertree.com/)  - 用于警报和待命管理的简单界面. 释放最多 5 个用户.
  * [pingbreak.com](https://pingbreak.com/)  — 现代正常运行时间监控服务. 检查无限的 URL 并通过 Discord、Slack 或电子邮件获取停机通知.
  * [pingpong.one](https://pingpong.one/)  — 带监控的高级状态页面平台. 免费套餐包括一个带有 SSL 子域的公共可定制状态页面.  Pro 计划免费提供给开源项目和非营利组织.
  * [robusta.dev](https://home.robusta.dev/)  — 强大的 Kubernetes 监控，基于 Prometheus. 带上您自己的 Prometheus 或安装一体化捆绑包. 免费套餐包含最多 20 个 Kubernetes 节点. 通过 Slack、Microsoft Teams、Discord 等发出警报. 与 PagerDuty、OpsGenie、VictorOps、DataDog 和许多其他工具集成.
  * [sematext.com](https://sematext.com/) — 24小时免费指标、无限数量的服务器、10个自定义指标、500,000个自定义指标数据点、无限的仪表板、用户等.
  * [sitemonki.com](https://sitemonki.com/) — 网站、域名、Cron 和 SSL 监控，每个类别 5 个免费监控器
  * [skylight.io](https://www.skylight.io/) — 前 100,000 个请求免费（仅限 Rails）
  * [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — 性能监控 API，检查 Ping、DNS 等.
  * [stathat.com](https://www.stathat.com/) — 免费开始使用 10 个统计数据，无过期时间
  * [statuscake.com](https://www.statuscake.com/) — 网站监控，无限测试，免费但有限制
  * [statusgator.com](https://statusgator.com/) — 状态页监控，3个监控空闲
  * [thousandeyes.com](https://www.thousandeyes.com/)  — 网络和用户体验监控. 免费提供主要网络服务的 3 个位置和 20 个数据源
  * [uptimerobot.com](https://uptimerobot.com/) — 网站监控，免费 50 个监控器
  * [uptimetoolbox.com](https://uptimetoolbox.com/) — 免费监控 5 个网站，60 秒间隔，公共状态页面.
  * [zenduty.com](https://www.zenduty.com/)  — 适用于网络运营、站点可靠性工程和 DevOps 团队的端到端事件管理、警报、待命管理和响应编排平台. 最多 5 个用户免费.
  * [instatus.com](https://instatus.com)  - 10秒内获得漂亮的状态页面. 永久免费，无限订阅者和无限团队.
  * [Squadcast.com](https://squadcast.com)  - Squadcast 是一款端到端事件管理软件，旨在帮助您推广 SRE 最佳实践. 永久免费计划可供最多 10 位用户使用.
  * [RoboMiri.com](https://robomiri.com/)  - RoboMiri 是一款稳定的正常运行时间监视器，提供多种监视器：cronjob、关键字、网站、端口、ping. 免费进行 25 次正常运行时间检查，每 3 分钟检查一次. 通过电话、短信、电子邮件和 Web Hook 发出警报.
  * [Better Stack](https://betterstack.com/better-uptime)  - 单一产品中的正常运行时间监控、事件管理、待命调度/警报和状态页面. 免费计划中包含 10 个显示器，每 3 分钟检查一次以及状态页面.
  * [Pulsetic](https://pulsetic.com)  - 10 个监视器、6 个月历史正常运行时间/日志、无限状态页面和自定义域！ 免费获得无限时间和无限电子邮件提醒. 无需信用卡.


## Crash and Exception Handling

  * [CatchJS.com](https://catchjs.com/)  - 通过屏幕截图和点击轨迹进行 JavaScript 错误跟踪. 对于开源项目免费.
  * [bugsnag.com](https://www.bugsnag.com/) — 初次试用后每月最多 2,000 个错误免费
  * [elmah.io](https://elmah.io/)  — Web 开发人员的错误记录和正常运行时间监控. 免费小型企业订阅开源项目.
  * [exceptionless](https://exceptionless.com)  — 实时错误、功能、日志报告等. 每月/1 位用户免费参加 3000 场活动. 开源且易于自行托管，可无限使用.
  * [GlitchTip](https://glitchtip.com/)  — 简单的开源错误跟踪. 与开源 Sentry SDK 兼容. 每月免费举办 1000 场活动，也可以无限制自行举办
  * [honeybadger.io](https://www.honeybadger.io) - Exception, uptime, and cron monitoring. Free for small teams and open-source projects (12,000 errors/month).
  * [memfault.com](https://memfault.com)  — 用于设备可观察性和调试的云平台.  100 台设备免费 [Nordic](https://app.memfault.com/register-nordic), [NXP](https://app.memfault.com/register-nxp)， 和 [Laird](https://app.memfault.com/register-laird) 设备.
  * [rollbar.com](https://rollbar.com/) — 异常和错误监控、每月 5,000 个错误的免费计划、无限用户、30 天保留
  * [sentry.io](https://sentry.io/)  — Sentry 实时跟踪应用程序异常，有一个小型免费计划. 每月 5000 个错误/1 个用户免费，如果自托管则不受限制使用
  * [Axiom](https://axiom.co/)  — 存储最多 0.5 TB 的日志，保留 30 天. 包括与 Vercel 等平台的集成以及通过电子邮件/Discord 通知程序进行高级数据查询.


## Search

  * [algolia.com](https://www.algolia.com/)  — 托管的即输入即搜索（即时）. 免费黑客计划多达 10,000 个文档和 100,000 次操作. 适用于社区/开源项目的更大免费计划
  * [bonsai.io](https://bonsai.io/) — 免费 1 GB 内存和 1 GB 存储空间
  * [CommandBar](https://www.commandbar.com/)  - 统一搜索栏即服务、基于 Web 的 UI 小部件/插件，允许您的用户在您的产品中搜索内容、导航、功能等，这有助于发现. 最多 1000 名每月活跃用户免费，命令无限制.
  * [Magny](https://magny.io) - SaaS 服务有助于实施命令面板（例如应用程序内搜索），从而显着减少用户在应用程序中查找任何内容的时间，从而充分利用用户体验和效率.
  * [searchly.com](http://www.searchly.com/) — 免费 2 个索引和 20 MB 存储空间
  * [pagedart.com](https://pagedart.com/)  - AI 搜索即服务，免费套餐包括 1000 个文档、50000 次搜索. 对于有价值的项目，可以提供更大的免费套餐.
  * [Meilisearch](https://www.meilisearch.com/)  - 一个开源、快如闪电且高度相关的搜索引擎，可轻松融入您的应用程序、网站和工作流程. 免费计划包括每月 100K 文档和 10K 搜索.


## Email

  * [10minutemail](https://10minutemail.com) - 用于测试的免费临时电子邮件.
  * [AnonAddy](https://anonaddy.com) - 开源匿名邮件转发，免费创建无限量的邮件别名
  * [Antideo](https://www.antideo.com)  — 免费套餐中每小时 10 个 API 请求，用于电子邮件验证、IP 和电话号码验证. 无需信用卡.
  * [Bump](https://bump.email/) - 免费 10 个 Bump 电子邮件地址、1 个自定义域
  * [Burnermail](https://burnermail.io/) – 免费 5 个刻录电子邮件地址、1 个邮箱、7 天邮箱历史记录
  * [Buttondown](https://buttondown.email/)  — 时事通讯服务. 最多 100 名订阅者免费
  * [CloudMailin](https://www.cloudmailin.com/) - 通过 HTTP POST 传入的电子邮件和事务性出站 - 每月 10,000 封免费电子邮件
  * [cloudmersive.com](https://www.cloudmersive.com/email-verification-api) — 为开发人员提供的电子邮件验证和验证 API，每月 800 个免费 API 请求
  * [Contact.do](https://contact.do/) — 链接中的联系表格（联系表格）- 完全免费！
  * [debugmail.io](https://debugmail.io/) — 易于开发人员使用的测试邮件服务器
  * [DNSExit](https://dnsexit.com/)  - 您的域名下最多可免费使用 2 个电子邮件地址，并拥有 100MB 的存储空间.  IMAP、POP3、SMTP、SPF/DKIM 支持.
  * [emaildrop.io](https://emaildrop.io/)  — 免费的一次性电子邮件提供商. 可以通过 GraphQL API 创建电子邮件地址.
  * [EmailLabs.io](https://emaillabs.io/en) — 每月免费发送多达 9,000 封电子邮件，每天最多发送 300 封电子邮件.
  * [EmailOctopus](https://emailoctopus.com) - 每月最多 2,500 名订阅者和 10,000 封电子邮件免费
  * [EmailJS](https://www.emailjs.com/) – 这不是一个完整的电子邮件服务器，这只是电子邮件客户端，您可以使用它直接从客户端发送电子邮件，而不会暴露您的凭据，免费套餐有：200 个每月请求，2 个电子邮件模板，最多 50Kb 的请求，有限的联系人历史.
  * [Emailvalidation.io](https://emailvalidation.io) - 每月 100 次免费电子邮件验证
  * [fakermail.com](https://fakermail.com/) — 免费的临时电子邮件，用于测试并存储最后 100 个电子邮件帐户.
  * [forwardemail.net](https://forwardemail.net)  — 自定义域的免费电子邮件转发. 使用您的域名创建和转发无限数量的电子邮件地址（**注意**：如果您使用 .casa、.cf、.click、.email、.fit、.ga、.gdn、.gq、 .loan、.london、.men、.ml、.pl、.rest、.ru、.tk、.top、.work TLD（因垃圾邮件而产生）
  * [HotTempMail](https://hottempmail.com/)  - 无限制的免费临时电子邮件或一次性临时电子邮件地址. 一天后自动过期.
  * [Imitate Email](https://imitate.email)  - 沙盒电子邮件服务器，用于跨 build/qa 和 ci/cd 测试电子邮件功能. 免费帐户每天永远收到 15 封电子邮件.
  * [ImprovMX](https://improvmx.com) – 免费电子邮件转发
  * [EForw](https://www.eforw.com)  – 1 个域名的免费电子邮件转发. 从您的域接收和发送电子邮件.
  * [inboxkitten.com](https://inboxkitten.com/)  - 免费的临时/一次性电子邮件收件箱，最多可自动删除 3 天的电子邮件. 开源，并且可以自行托管.
  * [mail-tester.com](https://www.mail-tester.com) — 测试电子邮件的 dns/spf/dkim/dmarc 设置是否正确，20 个免费/月
  * [dkimvalidator.com](https://dkimvalidator.com/) - 测试电子邮件的 dns/spf/dkim/dmarc 设置是否正确，由 roundsphere.com 提供的免费服务
  * [mailcatcher.me](https://mailcatcher.me/) — 捕获邮件并通过 Web 界面提供服务
  * [Mailcheck.ai](https://www.mailcheck.ai/) - 阻止用户使用临时电子邮件地址注册，每小时 120 个请求（每月约 86,400 个）
  * [Mailchimp](https://mailchimp.com/) — 每月免费 500 名订阅者和 1,000 封电子邮件
  * [MailerLite.com](https://www.mailerlite.com) — 1,000 名订阅者/月，12,000 封电子邮件/月免费
  * [MailerSend.com](https://www.mailersend.com) — 电子邮件 API、SMTP、每月 12,000 封电子邮件免费用于交易电子邮件
  * [mailinator.com](https://www.mailinator.com/) — 免费的公共电子邮件系统，您可以使用任何您想要的收件箱
  * [Mailjet](https://www.mailjet.com/) — 每月 6,000 封电子邮件免费（每日发送限制为 200 封电子邮件）
  * [Mailnesia](https://mailnesia.com) - 免费临时/一次性电子邮件，自动访问注册链接.
  * [mailsac.com](https://mailsac.com) - 用于临时电子邮件测试的免费 API、免费公共电子邮件托管、出站捕获、电子邮件到 slack/websocket/webhook（每月 1,500 个 API 限制）
  * [Mailtie.com](https://mailtie.com/)  - 您的域的免费电子邮件转发. 无需注册. 永远免费.
  * [Mailtrap.io](https://mailtrap.io/) — 用于开发的假 SMTP 服务器，免费计划，包含 1 个收件箱、100 条消息、无团队成员、每秒 2 封电子邮件、无转发规则
  * [Mailvalidator.io](https://mailvalidator.io/) - 每月免费验证 300 封电子邮件，实时 API，可进行批量处理
  * [Mail7.io](https://www.mail7.io/)  — 为 QA 开发人员提供的免费临时电子邮件地址. 使用 Web 界面或 API 立即创建电子邮件地址
  * [Mutant Mail](https://www.mutantmail.com/)  – 免费 10 个电子邮件 ID、1 个域名、1 个邮箱. 所有电子邮件 ID 的单一邮箱.
  * [Outlook.com](https://outlook.live.com/owa/) - 免费的个人电子邮件和日历
  * [Parsio.io](https://parsio.io) — 免费电子邮件解析器（转发电子邮件，提取数据，将其发送到您的服务器）
  * [pepipost.com](https://pepipost.com) — 第一个月免费发送 30,000 封电子邮件，然后每天免费发送前 100 封电子邮件
  * [Postmark](https://postmarkapp.com/) - 每月 100 封电子邮件免费，无限量 DMARC 每周摘要
  * [Proton Mail](https://proton.me/mail)  - 具有内置端到端加密功能的免费安全电子邮件帐户服务提供商. 免费 1GB 存储空间.
  * [Queuemail.dev](https://queuemail.dev)  — 可靠的电子邮件发送 API. 免费套餐（每月 10,000 封电子邮件）. 异步发送. 使用多个 SMTP 服务器. 黑名单、日志记录、跟踪、Webhooks 等等...
  * [QuickEmailVerification](https://quickemailverification.com) — 每天在免费套餐上免费验证 100 封电子邮件以及其他免费 API，例如 DEA Detector、DNS Lookup、SPF Detector 等.
  * [Sender](https://www.sender.net) 每月最多 15,000 封电子邮件，最多 2,500 名订阅者
  * [SendGrid](https://sendgrid.com/) — 每天 100 封电子邮件和 2,000 个联系人免费
  * [Sendinblue](https://www.sendinblue.com/) — 每月 9,000 封电子邮件，每天 300 封电子邮件免费
  * [Sendpulse](https://sendpulse.com) — 500 名订阅者/月，12,000 封电子邮件/月免费
  * [SimpleLogin](https://simplelogin.io/)  – 开源、自托管电子邮件别名/转发解决方案. 免费 5 个别名、无限带宽、无限回复/发送. 教育工作者（学生、研究人员等）免费.
  * [Skiff](https://skiff.com/) - 开源、端到端加密匿名电子邮件服务，注册时无需询问其他详细信息，免费 10GB 驱动器存储空间，您自己网站的 1 个自定义域，每个帐户为您的电子邮件地址提供 4 个免费别名.  E2EE 环境的附加加密钱包支持.
  * [Substack](https://substack.com)  — 无限制的免费新闻通讯服务. 当您收费时就开始付款.
  * [Tempmailo](https://tempmailo.com/)  - 无限制的免费临时电子邮件地址. 两天后自动过期.
  * [Takeout](https://takeout.bysourfruit.com)  - 不断更新的电子邮件服务，使发送电子邮件变得极其容易. 每月 500 封交易电子邮件免费.
  * [temp-mail.io](https://temp-mail.io) — 免费的一次性临时电子邮件服务，可同时转发多封电子邮件
  * [tinyletter.com](https://tinyletter.com/) — 每月 5,000 名订阅者免费
  * [trashmail.com](https://www.trashmail.com) - 免费的一次性电子邮件地址，具有转发功能和地址自动过期功能
  * [Tutanota](https://tutanota.com/)  - 免费的安全电子邮件帐户服务提供商，内置端到端加密，无广告，无跟踪. 免费 1GB 存储空间. 其中也部分地 [open source](https://github.com/tutao/tutanota)，因此您可以选择自行托管.
  * [Validator.Pizza](https://www.validator.pizza/) — 免费 API 用于检测一次性电子邮件
  * [Verifalia](https://verifalia.com/email-verification-api)  — 实时电子邮件验证 API，具有邮箱确认和一次性电子邮件地址检测器； 每天 25 次免费电子邮件验证.
  * [verimail.io](https://verimail.io/)  — 批量和 API 电子邮件验证服务. 每月 100 次免费验证
  * [Zoho](https://www.zoho.com)  — 最初是一家电子邮件提供商，但现在提供一套服务，其中一些服务有免费计划. 具有免费计划的服务列表：
     - [Email](https://zoho.com/mail)  5 位用户免费.  5 GB/用户和 25 MB 附件限制，1 个域.
     - [Sprints](https://zoho.com/sprints) 免费供 5 个用户、5 个项目和 500MB 存储空间.
     - [Docs](https://zoho.com/docs)  — 5 位用户免费，上传限制为 1 GB，存储空间为 5 GB.  Zoho Office 套件（Writer、Sheets 和 Show）与其捆绑在一起.
     - [Projects](https://zoho.com/projects)  — 免费供 3 个用户、2 个项目和 10 MB 附件限制. 同样的计划适用于 [Bugtracker](https://zoho.com/bugtracker).
     - [Connect](https://zoho.com/connect) — 免费为 25 位用户提供团队协作，包括 3 个组、3 个自定义应用程序、3 个看板、3 个手册、10 个集成以及渠道、活动和论坛.
     - [Meeting](https://zoho.com/meeting) — Meetings with upto 3 meeting participants & 10 Webinar attendees.
     - [Vault](https://zoho.com/vault) — 个人密码管理免费.
     - [Showtime](https://zoho.com/showtime) — 另一种会议软件，用于培训最多 5 名与会者的远程会议.
     - [Notebook](https://zoho.com/notebook) — Evernote 的免费替代品.
     - [Wiki](https://zoho.com/wiki) — 3 位用户免费，拥有 50 MB 存储空间、无限页面、zip 备份、RSS 和 Atom 提要、访问控制和可自定义 CSS.
     - [Subscriptions](https://zoho.com/subscriptions)  — 为 20 个客户/订阅和 1 个用户免费提供定期账单管理，所有付款托管均由 Zoho 自己完成. 存储最后 40 个订阅指标
     - [Checkout](https://zoho.com/checkout) — 产品账单管理，包含 3 页和最多 50 笔付款.
     - [Desk](https://zoho.com/desk)  — 拥有 3 名代理和私人知识库、电子邮件票证的客户支持管理. 集成于 [Assist](https://zoho.com/assist) 适用于 1 名远程技术人员和 5 台无人值守计算机.
     - [Cliq](https://zoho.com/cliq) — 团队聊天软件，具有 100 GB 存储空间、无限用户、每个频道 100 个用户和 SSO.
     - [Campaigns](https://zoho.com/campaigns)
     - [Forms](https://zoho.com/forms)
     - [Sign](https://zoho.com/sign)
     - [Surveys](https://zoho.com/surveys)
     - [Bookings](https://zoho.com/bookings)
     - [Analytics](https://zoho.com/analytics)
  * [Resend](https://resend.com)  - 供开发人员使用的交易电子邮件 API. 每月 3,000 封电子邮件，每天免费 100 封电子邮件，1 个自定义域.



## Font

  * [dafont](https://www.dafont.com/) - 本网站上提供的字体是其作者的财产，并且是免费软件、共享软件、演示版或公共领域.
  * [Everything Fonts](https://everythingfonts.com/)  - 提供多种工具；  @font-face，单位转换器，字体提示和字体提交器.
  * [Font Squirrel](https://www.fontsquirrel.com/)  - 获得商业作品许可的免费软件字体. 手工选择这些字体并以易于使用的格式呈现.
  * [Google Fonts](https://fonts.google.com/) - 通过下载或指向 Google CDN 的链接，可以轻松快速地在网站中安装大量免费字体.
  * [FontGet](https://www.fontget.com/) - 有多种字体可供下载，并用标签整齐地分类.
  * [Fontshare](https://www.fontshare.com/)  - 是免费字体服务. 这是一个不断增长的专业级字体集合，100% 免费供个人和商业使用.
  * [Befonts](https://befonts.com/) - 提供多种独特的字体供个人或商业用途.
  * [Font of web](https://fontofweb.com/) - 识别网站上使用的所有字体及其使用方式.
  * [Bunny](https://bunny.net)
    * [Bunny Fonts](https://fonts.bunny.net/)  - 所有具有 Google Fonts drop-in 兼容 API 的 Google Fonts. 以隐私为导向！
    * [Bunny DNS](https://bunny.net/dns/) - DNS托管，2000万次免费查询
  * [FontsKey](https://www.fontskey.com/) - 提供个人使用的免费字体和商业付费字体，并可以输入文本进行快速过滤.


## Forms
  * [Feathery](https://feathery.io)  - 功能强大、开发人员友好的表单生成器. 构建注册和登录、用户入门、支付流程、复杂的财务应用程序等. 免费计划允许每月最多 250 次提交和 5 个有效表格.
  * [Form-Data](https://form-data.com)  - 无代码表单后端. 垃圾邮件过滤器、电子邮件通知和自动回复、webhooks、zapier、重定向、AJAX 或 POST 等. 免费计划提供无限量的表单、每月 20 份提交以及带有表单数据徽章的额外 2000 份提交.
  * [FabForm](https://fabform.io/)  - 为聪明的开发者形成后端平台. 免费计划允许每月提交 250 份表格. 友好的现代图形用户界面. 与 Google Sheets、Airtable、Slack、电子邮件等集成.
  * [Form.taxi](https://form.taxi/)  — HTML 表单提交的端点. 具有通知、垃圾邮件拦截器和符合 GDPR 的数据处理功能. 基本使用的免费计划.
  * [Formcake.com](https://formcake.com)  - 开发人员的表单后端，免费计划允许无限量的表单，100 份提交，Zapier 集成. 不需要任何库或依赖项.
  * [Formcarry.com](https://formcarry.com) - HTTP POST 表单端点，免费计划允许每月 100 次提交.
  * [formingo.co](https://www.formingo.co/) - 静态网站的简单 HTML 表单，无需注册帐户即可免费开始. 免费计划允许每月 500 次提交，可自定义回复电子邮件地址.
  * [FormKeep.com](https://www.formkeep.com/)  - 每月可提交 50 份无限表单、垃圾邮件防护、电子邮件通知以及可导出 HTML 的拖放设计器. 其他功能包括自定义字段规则、团队以及与 Google Sheets、Slack、ActiveCampaign 和 Zapier 的集成.
  * [formlets.com](https://formlets.com/) — 在线表格、每月无限制的单页表格、每月 100 份提交、电子邮件通知.
  * [formspark.io](https://formspark.io/) - 表格到电子邮件服务，免费计划允许无限量的表格，每月提交 250 份，由客户支持团队提供支持.
  * [Formspree.io](https://formspree.io/)  — 使用 HTTP POST 请求发送电子邮件. 免费层级限制为每个表单每月提交 50 次.
  * [Formsubmit.co](https://formsubmit.co/)  — HTML 表单的简单表单端点. 永远免费. 无需注册.
  * [getform.io](https://getform.io/) - 设计者和开发者的表单后端平台，1个表单，50个提交，单个文件上传，100MB文件存储.
  * [HeroTofu.com](https://herotofu.com/)  - 具有机器人检测和加密存档功能的表单后端. 通过 UI 将提交转发至电子邮件、Slack 或 Zapier. 使用您自己的前端，无需服务器代码. 免费计划提供无限量的表格和每月 100 份提交.
  * [HeyForm.net](https://heyform.net/)  - 拖放在线表单生成器. 免费套餐可让您创建无限量的表单并收集无限量的提交内容. 配备预建模板、反垃圾邮件和 100MB 文件存储.
  * [Tally.so](https://tally.so/)  - 99% 的功能完全免费. 免费套餐可让您拥有以下功能：无限制的表单、无限制的提交、电子邮件通知、表单逻辑、收款、文件上传、自定义感谢页面等等.
  * [Hyperforms.app](https://hyperforms.app/)  — 在几秒钟内创建表单到电子邮件等，并且无需后端代码. 个人帐户每月最多可免费向您提交 50 份表格.
  * [Kwes.io](https://kwes.io/)  - 功能丰富的形式端点. 非常适合静态网站. 免费计划包括最多 1 个网站，每月最多提交 50 条内容.
  * [Pageclip](https://pageclip.co/) - 免费计划允许一个网站、一份表格、每月 1,000 份提交.
  * [Qualtrics Survey](https://qualtrics.com/free-account) — Create professional forms & survey using this first class tool. 50+ expert-designed survey templates. Free Account has limit of 1 active survey, 100 responses/survey & 8 response types.
  * [smartforms.dev](https://smartforms.dev/) - 强大而简单的网站表单后端，永久免费计划允许每月 50 次提交，250MB 文件存储，Zapier 集成，CSV/JSON 导出，自定义重定向，自定义响应页面，Telegram 和 Slack 机器人，单封电子邮件通知.
  * [staticforms.xyz](https://www.staticforms.xyz/)  - 免费集成 HTML 表单，无需任何服务器端代码. 用户提交表单后，一封包含表单内容的电子邮件将发送到您的注册地址.
  * [stepFORM.io](https://stepform.io)  - 测验和表格生成器. 免费计划有 5 个表格，每个表格最多 3 个步骤，每月 50 个回复.
  * [Typeform.com](https://www.typeform.com/)  — 在网站上包含设计精美的表格. 免费计划仅允许每个表单 10 个字段，每月仅允许 100 个回复.
  * [WaiverStevie.com](https://waiverstevie.com)  - 具有 REST API 的电子签名平台. 使用 webhook 接收通知. 免费计划水印签署的文件，但允许无限的信封+签名.
  * [Web3Forms](https://web3forms.com)  - 静态和 JAMStack 网站的联系表单，无需编写后端代码. 免费计划允许无限表格、无限域名和每月 250 次提交.
  * [WebAsk](https://webask.io)  - 调查和表格生成器. 免费计划每个帐户有 3 项调查，每月 100 个回复，每个调查 10 个元素.
  * [Wufoo](https://www.wufoo.com/)  - 在网站上使用的快速表格. 免费计划每月提交的数量上限为 100 份.
  * [formpost.app](https://formpost.app)  - 免费、无限制的表格到电子邮件服务. 免费设置自定义重定向、自动响应、网络钩子等.
  * [Formester.com](https://formester.com)  - 在您的网站上共享和嵌入外观独特的表单 - 创建的表单数量没有限制，也没有计划限制的功能. 每月最多可免费提交 100 份作品.
  * [SimplePDF.eu](https://simplepdf.eu/embed)  - 在您的网站上嵌入 PDF 编辑器，将任何 PDF 转换为可填写的表格. 免费计划允许无限量的 PDF，每个 PDF 可以提交 3 次.


## CDN and Protection

  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) — CDN for bootstrap, bootswatch and fontawesome.io
  * [cdnjs.com](https://cdnjs.com/)  - 简单的. 快速地. 可靠的. 最好的内容交付.  cdnjs 是一项由 Cloudflare 提供支持的免费开源 CDN 服务，受到超过 11% 的网站信任.
  * [Cloudflare](https://www.cloudflare.com/)
    * CDN 以及免费 SSL
    * 免费 DNS，域名数量不受限制
    * 防火墙规则和页面规则
    * 分析
    * 电子邮件转发
    * 免费不限流量限制 - 每个域 1 条规则
    * [Cloudflare Pages](https://pages.cloudflare.com/)  — 免费网络托管（JAMstack 平台），供前端开发人员协作和部署网站. 一次 1 个构建、每月 500 个构建、无限站点、无限请求、无限带宽.
    * [Cloudflare Workers](https://workers.cloudflare.com/)  — 在 Cloudflare 的全球网络上免费部署无服务器代码.  Workers.dev 子域每天有 100,000 个免费请求.
    * [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) - 您可以通过隧道将本地运行的 HTTP 端口公开到 trycloudflare.com 使用上的随机子域 [Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/run-tunnel/trycloudflare) ，无需帐户. 更多功能（TCP 隧道、负载均衡、VPN）位于 [Zero Trust](https://www.cloudflare.com/products/zero-trust/) 免费计划.
  * [developers.google.com](https://developers.google.com/speed/libraries/) — Google 托管库是最流行的开源 JavaScript 库的内容分发网络
  * [Stellate](https://stellate.co/) - Stellare 是适用于您的 GraphQL API 的快速、可靠的 CDN，并且免费提供 2 项服务.
  * [jsdelivr.com](https://www.jsdelivr.com/)  — 一个免费、快速、可靠的开源 CDN. 支持 npm、GitHub、WordPress、Deno 等.
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — Microsoft Ajax CDN 托管流行的第三方 JavaScript 库（例如 jQuery），使您能够轻松地将它们添加到您的 Web 应用程序中
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) — 免费 DDoS 保护和 SSL 证书
  * [PageCDN.com](https://pagecdn.com/) - 为所有人提供免费的公共 CDN，为开源/非营利组织提供免费的私人 CDN.
  * [Skypack](https://www.skypack.dev/)  — 100% 原生 ES 模块 JavaScript CDN. 每个域每月 100 万个请求免费.
  * [raw.githack.com](https://raw.githack.com/) — **rawgit.com** 的现代替代品，它仅使用 Cloudflare 托管文件
  * [section.io](https://www.section.io/)  — 一种启动和管理完整 Varnish 缓存解决方案的简单方法. 据说一个网站永远免费
  * [statically.io](https://statically.io/) — Git 存储库（GitHub、GitLab、Bitbucket）、WordPress 相关资产和图像的 CDN
  * [toranproxy.com](https://toranproxy.com/)  — Packagist 和 GitHub 的代理.  CD 永不失败. 免费供个人使用，1 名开发者，无支持
  * [UNPKG](https://unpkg.com/) — npm 上所有内容的 CDN
  * [weserv](https://images.weserv.nl/)  — 图像缓存和调整大小服务. 使用全球缓存即时处理图像.
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — 免费 DDoS 防护
  * [Gcore](https://gcorelabs.com/)
    * [CDN](https://gcorelabs.com/cdn/) — 全球内容交付网络，每月 1 TB 和 100 万个请求免费.
    * [DNS Hosting](https://gcorelabs.com/dns/) — 免费 DNS 托管.


## PaaS

  * [anvil.works](https://anvil.works)  - 仅使用 Python 进行 Web 应用程序开发. 免费套餐，无限应用程序，30 秒超时.
  * [configure.it](https://www.configure.it/) — 移动应用开发平台，免费供2个项目使用，功能有限但无资源限制
  * [codenameone.com](https://www.codenameone.com/)  — 面向 Java/Kotlin 开发人员的开源、跨平台、移动应用程序开发工具链. 免费用于商业用途，项目数量不受限制
  * [Cosmonic](https://cosmonic.com) - Feature rich WebAssembly PaaS and SDKs for low boilerplate, flexible, and secure by default microservices. Always free tier includes a managed host, 25 microservices, and included capabilities like a robust keyvalue store, load balanced public HTTP endpoints, and more.
  * [Cyclic](https://www.cyclic.sh)  - 全栈应用程序托管 - 推送到 Github 以构建和部署 Javascript/Node.js 应用程序. 包括：身份验证、Cron 作业、自定义域、数据库、存储和流日志. 付费计划包括：基于分支机构的环境、多区域部署和增加的限制.
  * [Deno Deploy](https://deno.com/deploy)  - 在全球边缘运行 JavaScript、TypeScript 和 WebAssembly 的分布式系统. 免费套餐包括每天 100,000 个请求和每月 100 GiB 数据传输.
  * [domcloud.co](https://domcloud.co)  – Linux 托管服务，还提供带有 GitHub、SSH 和 MariaDB/Postgres 数据库的 CI/CD. 免费版本有 1 GB 存储空间和 1 GB 网络/月限制，并且仅限于免费域.
  * [encore.dev](https://encore.dev/)  — 使用静态分析的后端框架提供自动化基础设施、无样板代码等. 包括用于业余爱好项目的免费云托管.
  * [gigalixir.com](https://gigalixir.com/) - Gigalixir 为 Elixir/Phoenix 应用程序提供 1 个永不休眠的免费实例，以及仅限 2 个连接、10, 000 行且无备份的免费 PostgreSQL 数据库.
  * [Glitch](https://glitch.com/) — Free public hosting with features such as code sharing and real-time collaboration. Free plan has 1000 hours/month limit.
  * [Mendix](https://www.mendix.com/)  — 企业快速应用程序开发、无限数量的免费沙箱环境支持无限用户、每个应用程序 0.5 GB 存储和 1 GB RAM. 免费套餐中还允许使用 Studio 和 Studio Pro IDE.
  * [m3o.com](https://m3o.com)  - 用于API服务开发的云平台.  M3O 是一个完全托管的微即服务产品，专注于云中的 Go 微服务开发. 免费套餐足以运行 5 项服务并与其他人协作.
  * [Okteto Cloud](https://okteto.com)  - 专为远程开发而设计的托管 Kubernetes 服务. 免费开发者帐户附带 5 个 Kubernetes 命名空间、3Gi/pod（最多 8Gi/命名空间）、1CPU/pod（最多 4CPU/命名空间）和 5GB 磁盘空间. 应用程序在 24 小时不活动后进入睡眠状态.
  * [pipedream.com](https://pipedream.com)  - 为开发人员构建的集成平台. 基于任何触发器开发任何工作流程. 工作流程是可以运行的代码 [for free](https://docs.pipedream.com/pricing/). No server or cloud resources to manage.
  * [pythonanywhere.com](https://www.pythonanywhere.com/)  — 云 Python 应用程序托管. 初学者帐户免费，1 个位于 your-username.pythonanywhere.com 域的 Python Web 应用程序，512 MB 私人文件存储，1 个 MySQL 数据库
  * [Serverless Cloud](https://www.serverless.com/cloud)  - 无服务器云允许您使用基础设施代码方法（无 yaml，无基础设施配置）构建无服务器 API、数据库和存储. 该产品由 Serverless Inc. 提供，目前处于公共预览阶段.
  * [fly.io](https://fly.io/)  - Fly是需要在全球运行的应用程序的平台. 它在靠近用户的地方运行您的代码，并在您的应用程序最繁忙的城市扩展计算. 编写代码，将其打包到 Docker 映像中，将其部署到 Fly 平台，然后让它完成所有工作，以保持应用程序的敏捷性. 免费配额包括最多 3 个共享 cpu-1x 256mb 虚拟机、3GB 持久卷存储（总计）和 160GB 出站数据传输.
  * [Divio](https://www.divio.com/)  - 仅使用 Docker 管理云应用程序部署的平台. 可免费订阅开发项目. 需要卡且无自定义域支持.
  * [Koyeb](https://www.koyeb.com)  - Koyeb 是一个开发人员友好的无服务器平台，用于在全球部署应用程序. 通过基于 git 的部署、本机自动缩放、全球边缘网络以及内置服务网格和发现，无缝运行 Docker 容器、Web 应用程序和 API.  Koyeb 提供两种 Nano 服务，通过其永久免费层运行您的应用程序，并通过免费资源赞助开源项目. 免费计划需要卡信息.
  * [Napkin](https://www.napkin.io/) - FaaS，内存 500Mb，默认超时 15 秒，每月免费 API 调用 5,000 次，速率限制为每秒 5 次调用.
  * [Meteor Cloud](https://www.meteor.com/cloud)  — 银河托管.  Meteor 自己的 Meteor 应用程序平台即服务，其中包括免费的 MongoDB 共享托管和自动 SSL.
  * [Northflank](https://northflank.com)  — 使用强大的 UI、API 和 CLI 构建和部署微服务、作业和托管数据库. 从版本控制和外部 Docker 注册表无缝扩展容器. 免费套餐包括 2 项服务、2 个 cron 作业和 1 个数据库.
  * [YepCode](https://yepcode.io)  - 用于在无服务器环境中连接 API 和服务的一体化平台. 它带来了 NoCode 工具的所有敏捷性和优势，同时也具有使用编程语言的所有功能. 免费套餐包括 [1.000 yeps](https://yepcode.io/pricing/).
  * [WunderGraph](https://cloud.wundergraph.com)  - 一个开源平台，可让您快速构建、发布和管理现代 API. 内置 CI/CD、GitHub 集成、自动 HTTPS. 最多 3 个项目、1GB 出口、每月 300 分钟的构建时间 [free plan](https://wundergraph.com/pricing)
  * [Doprax Cloud](https://www.doprax.com) — Cloud hosting for your Apps, Websites and APIs. Free for one app, with 4 * 256MB ram and 2 GB of disk. To create an app space, you need to have at least $3 in your account credit balance.
  * [Zeabur](https://zeabur.com)  - 一键部署您的服务.  3 项服务免费，每月 5 美元免费积分.


## BaaS

  * [Activepieces](https://www.activepieces.com)  - 构建自动化流程以在应用程序后端将多个应用程序连接在一起. 例如，当您的应用程序中触发事件时，发送 Slack 消息或添加 Google 表格行. 每月最多可释放 5,000 个任务.
  * [back4app.com](https://www.back4app.com) - Back4App是一个基于Parse Platform的易于使用、灵活且可扩展的后端.
  * [backendless.com](https://backendless.com/) — 移动和 Web Baas，免费提供 1 GB 文件存储空间，推送通知 50000 条/月，表中数据对象 1000 个.
  * [BMC Developer Program](https://developers.bmc.com/site/global/bmc_helix_platform/program/overview/index.gsp)  — BMC 开发人员计划提供文档和资源来为您的企业构建和部署数字创新. 访问全面的个人沙箱，其中包括平台、SDK 以及可用于构建和定制应用程序的组件库.
  * [convex.dev](https://convex.dev/)  - 反应式后端即服务，托管您的数据（具有关系的文档和可序列化的 ACID 事务）、无服务器功能和用于将更新流式传输到各种客户端的 Websockets. 对于小型项目免费 - 每月最多 1M 条记录、5M 次函数调用.
  * [darklang.com](https://darklang.com/)  - 托管语言与编辑器和基础设施相结合. 测试期间免费，测试后计划提供慷慨的免费套餐.
  * [Firebase](https://firebase.com)  — Firebase 可帮助您构建和运行成功的应用程序. 免费 Spark 计划提供身份验证、托管、Firebase ML、实时数据库、云存储、测试实验室.  A/B 测试、分析、应用程序分发、应用程序索引、云消息传递 (FCM)、Crashlytics、动态链接、应用程序内消息传递、性能监控、预测和远程配置始终免费.
  * [Flutter Flow](https://flutterflow.io)  — 无需编写任何代码即可构建您的 Flutter 应用程序 UI. 还有 Firebase 集成. 免费计划包括对 UI Builder 和免费模板的完全访问权限.
  * [getstream.io](https://getstream.io/) — 在几个小时而不是几周内构建可扩展的新闻源、活动流、聊天和消息传递
  * [hasura.io](https://hasura.io/)  — Hasura 可以扩展您现有的数据库（无论其托管在何处），并提供即时 GraphQL API，可以安全地访问 Web、移动和数据集成工作负载. 免费每月 1GB 数据传输.
  * [iron.io](https://www.iron.io/) — 异步任务处理（如 AWS Lambda），提供免费套餐和 1 个月免费试用
  * [nhost.io](https://nhost.io)  - 用于网络和移动应用程序的无服务器后端. 免费计划包括：PostgreSQL、GraphQL (Hasura)、身份验证、存储和无服务器功能.
  * [nudge-hook.net](https://nudge-hook.net/client)  — 作业调度 API（使用 swagger/openapi 客户端）. 允许您根据需要安排任意数量的 adhoc/cron/定期 webhook 交付. 所有人免费（无需注册），但无限的时间表仅限于最多 500 次“轻推”. 接受捐款.
  * [onesignal.com](https://onesignal.com/) — 无限制的免费推送通知
  * [paraio.com](https://paraio.com)  — 后端服务API，具有灵活的身份验证、全文搜索和缓存.  1 个应用程序免费，1GB 应用程序数据.
  * [progress.com](https://www.progress.com/kinvey)  — 移动后端，入门计划每秒无限制请求，具有 1 GB 数据存储空间. 企业应用支持
  * [pubnub.com](https://www.pubnub.com/) — 每月最多 100 万条消息和 100 个日常活跃设备的免费推送通知
  * [pushbots.com](https://pushbots.com/)  — 推送通知服务. 每月最多免费推送 150 万次
  * [pushcrew.com](https://pushcrew.com/)  — 推送通知服务. 最多 2000 名订阅者的无限通知
  * [pusher.com](https://pusher.com/beams)  — 为 2000 名每月活跃用户提供免费、无限制的推送通知. 适用于 iOS 和 Android 设备的单一 API.
   * [engagespot.co](https://engagespot.co/)  — 为开发人员提供的通知基础设施. 每月最多 100 名活跃用户免费.
  * [pushtechnology.com](https://www.pushtechnology.com/)  — 适用于浏览器、智能手机和每个人的实时消息传递.  100 个并发连接. 每月免费 10 GB 数据
  * [quickblox.com](https://quickblox.com/) — 用于即时消息、视频和语音通话以及推送通知的通信后端
  * [restspace.io](https://restspace.io/) - 使用身份验证、数据、文件、电子邮件 API、模板等服务配置服务器，然后组成管道并转换数据.
  * [Salesforce Developer Program](https://developer.salesforce.com/signup)  — 使用拖放工具快速构建应用程序. 通过点击自定义您的数据模型. 使用 Apex 代码更进一步. 使用强大的 API 与任何东西集成. 通过企业级安全性保持保护. 通过点击或任何领先的 Web 框架自定义 UI. 免费开发者计划可以访问完整的闪电平台.
  * [ServiceNow Developer Program](https://developer.servicenow.com/)  — 快速构建、测试和部署应用程序，使您的组织更好地工作. 免费实例并访问早期预览.
  * [simperium.com](https://simperium.com/)  — 即时、自动地将数据移动到任何地方，多平台，无限发送和存储结构化数据，最大数量.  2,500 个用户/月
  * [stackstorm.com](https://stackstorm.com/) — 应用程序、服务和工作流程的事件驱动自动化，无流量、访问控制、LDAP、...
  * [streamdata.io](https://streamdata.io/)  — 将任何 REST API 转变为事件驱动的流 API. 免费计划最多 100 万条消息和 10 个并发连接.
  * [Supabase](https://supabase.com)  — 用于构建后端的开源 Firebase 替代方案. 免费计划提供身份验证、实时数据库和对象存储.
  * [tyk.io](https://tyk.io/)  — 具有身份验证、配额、监控和分析功能的 API 管理. 免费云产品
  * [zapier.com](https://zapier.com/)  — 连接您使用的应用程序以自动执行任务.  5 次 zap，每 15 分钟一次，每月 100 项任务
  * [LeanCloud](https://leancloud.app/)  — 移动后端.  1GB 数据存储、256MB 实例、3K API 请求/天、10K 推送/天都是免费的.  （API与Parse Platform非常相似）


## Low-code Platform

  * [BudiBase](https://budibase.com/)  — Budibase 是一个开源低代码平台，可在几分钟内创建内部应用程序. 支持 PostgreSQL、MySQL、MSSQL、MongoDB、Rest API、Docker、K8s
  * [appsmith](https://www.appsmith.com/)  — 用于构建管理面板、内部工具和仪表板的低代码项目. 与超过 15 个数据库和任何 API 集成.
  * [ToolJet](https://www.tooljet.com/)  — 用于构建业务应用程序的可扩展低代码框架. 连接到数据库、云存储、GraphQL、API 端点、Airtable 等，并使用拖放应用程序生成器构建应用程序.
  * [ReTool](https://retool.com/)  — 用于构建内部应用程序的低代码平台.  Retool 是高度可破解的. 如果您可以使用 JavaScript 和 API 编写它，则可以在 Retool 中构建它. 免费套餐每月最多允许 5 个用户、无限的应用程序和 API 连接.
  * [DronaHQ](https://www.dronahq.com/) — DronaHQ - 一个低代码平台，可帮助工程团队和产品经理构建内部工具、自定义用户旅程、数字体验、自动化、自定义管理面板、操作应用程序，速度提高 10 倍.
  * [ILLA Cloud](https://www.illacloud.com/)  — ILLA Cloud - 一个强大的开源低代码平台，供开发人员构建内部工具. 通过使用 ILLA 的组件和操作库，开发人员可以节省构建工具的大量时间.  5 名团队成员免费.
  * [outsystems.com](https://www.outsystems.com/) — 适用于本地或云的企业 Web 开发 PaaS，免费的“个人环境”产品允许无限的代码和高达 1 GB 的数据库



## Web Hosting

  * [Alwaysdata](https://www.alwaysdata.com/)  — 100 MB 免费网络托管，支持 MySQL、PostgreSQL、CouchDB、MongoDB、PHP、Python、Ruby、Node.js、Elixir、Java、Deno、自定义 Web 服务器，通过 FTP、WebDAV 和 SSH 访问； 包括邮箱、邮件列表和应用程序安装程序.
  * [Awardspace.com](https://www.awardspace.com) — Free web hosting + a free short domain, PHP, MySQL, App Installer, Email Sending & No Ads.
  * [Bubble](https://bubble.io/) — 可视化编程，无需代码即可构建网络和移动应用程序，免费使用 Bubble 品牌.
  * [DigitalOcean](https://www.digitalocean.com/pricing) - 在应用程序平台入门层免费构建和部署 3 个静态站点.
  * [Drive To Web](https://drv.tw)  — 从 Google Drive 和 OneDrive 直接托管到网络. 仅静态站点. 永远免费. 每个 Google/Microsoft 帐户一个网站.
  * [DuckDocs](https://duckdocs.com)  - Markdown 支持的文档托管，有点像托管的 Docusaurus. 每个站点 10 个页面免费.
  * [Fenix Web Server](https://preview.fenixwebserver.com)  - 开发人员桌面应用程序，用于在本地托管网站并公开共享（实时）. 使用其漂亮的用户界面、API 和/或 CLI，随心所欲地工作.
  * [Free Hosting](https://freehostingnoads.net/) — 免费托管 PHP 5、Perl、CGI、MySQL、FTP、文件管理器、POP 电子邮件、免费子域、免费域托管、DNS 区域编辑器、网站统计、免费在线支持以及许多其他不提供的功能其他免费主机.
  * [Freehostia](https://www.freehostia.com)  — FreeHostia 提供免费托管服务，包括. 业界最佳的控制面板和 50 多个免费应用程序的一键安装. 即时设置. 没有强制广告.
  * [HelioHost](https://heliohost.org) — 非盈利免费网络托管，配有 Plesk 控制面板、PHP、Node.js、Python、Django、Flask、.NET、Perl、CGI、MySQL、PostgreSQL、SQLite、IMAP/POP3/SMTP 电子邮件、无限带宽、免费子域、免费 1000 MB 存储空间，并可选择升级.
  * [Lecturify](https://www.lecturify.net/index.en.html) - 具有 sftp 访问权限的网络托管，用于文件上传和下载，可使用 php.
  * [Neocities](https://neocities.org) — 静态、1 GB 可用存储空间和 200 GB 带宽.
  * [Netlify](https://www.netlify.com/) — 免费构建、部署和托管静态站点/应用程序，100 GB 数据和每月 100 GB 带宽.
  * [pantheon.io](https://pantheon.io/)  — Drupal 和 WordPress 托管、自动化 DevOps 和可扩展的基础设施. 对开发商和机构免费. 没有自定义域.
  * [readthedocs.org](https://readthedocs.org/) — 免费文档托管，包括版本控制、PDF 生成等
  * [render.com](https://render.com) — 统一云，通过免费 SSL、全球 CDN、专用网络、Git 自动部署以及完全免费的 Web 服务、数据库和静态网页计划来构建和运行应用程序和网站.
  * [SourceForge](https://sourceforge.net/) — 免费查找、创建和发布开源软件
  * [Stormkit](https://stormkit.io/)  — 将构建、部署和托管与 JAMStack 或 Node.JS 应用程序的 git 流程无缝集成. 每月免费 50 GB 带宽和 10m 请求，包括免费 SSL.
  * [surge.sh](https://surge.sh/)  — 前端开发人员的静态网络发布. 具有自定义域支持的无限站点
  * [telegra.ph](https://telegra.ph/) 使用 Quill 轻松创建网页
  * [tilda.cc](https://tilda.cc/) — 一个站点，50 个页面，50 MB 存储空间，仅 170 多个可用的主要预定义块，没有字体，没有图标，也没有自定义域
  * [Vercel](https://vercel.com/)  — 每次“git Push”时，使用免费的 SSL、全球 CDN 和独特的预览 URL 构建、部署和托管 Web 应用程序. 非常适合 Next.js 和其他静态站点生成器.
  * [Versoly](https://versoly.com/)  — 专注于 SaaS 的网站构建器 - 无限的网站、70 多个块、5 个模板、自定义 CSS、favicon、SEO 和表单. 没有自定义域.
  * [Qoddi](https://qoddi.com)  - 类似于 Heroku 的 PaaS 服务，具有以开发人员为中心的方法和全面的功能. 静态资产、暂存和开发应用程序的免费套餐.
  * [FreeFlarum](https://freeflarum.com/) - 社区支持的免费 Flarum 托管最多可容纳 250 位用户（捐赠以删除页脚水印）.
  * [fleek.co](https://fleek.co/) - 在开放网络及其协议上无缝免费构建现代网站和应用程序，无限的网站和每月 50 GB 的带宽.
  * [MDB GO](https://mdbgo.com/) - 免费托管 1 个项目，容器 TTL 为 2 周，每个项目 500mb RAM，SFTP - 1G 磁盘空间.
  * [Patr Cloud](https://patr.cloud/) — 一个易于使用的云平台，其付费服务包括免费托管 3 个静态站点.
  * [Serv00.com](https://serv00.com/)  — 3 GB 免费网络托管，每日备份（7 天）. 支持：Crontab 作业、SSH 访问、存储库（GIT、SVN 和 Mercurial），支持：MySQL、PostgreSQL、MongoDB、PHP、Node.js、Python、Ruby、Java、Perl、TCL/TK、Lua、Erlang、Rust、 Pascal、C、C++、D、R 等等.


## DNS

  * [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/)  - 由 CloudFlare 提供的免费公共 DNS 解析器，快速且安全（加密您的 DNS 查询）. 有助于绕过互联网提供商的 DNS 阻止、防止 DNS 查询间谍活动，以及 [to block adult & malware content](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families) . 也可以用 [via API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests) . 注意：只是 DNS 解析器，而不是 DNS 托管服务商.
  * [1984.is](https://www.1984.is/product/freedns/) — 带 API 的免费 DNS 服务，以及许多其他免费 DNS 功能.
  * [cloudns.net](https://www.cloudns.net/) — 免费 DNS 托管最多 1 个包含 50 条记录的域名
  * [dns.he.net](https://dns.he.net/) — 具有动态 DNS 支持的免费 DNS 托管服务
  * [Zonomi](https://zonomi.com/)  — 免费 DNS 托管服务，具有即时 DNS 传播功能. 免费计划：1 个 DNS 区域（域名），最多 10 条 DNS 记录.
  * [dnspod.com](https://www.dnspod.com/) — 免费 DNS 托管.
  * [duckdns.org](https://www.duckdns.org/)  — 免费 DDNS，免费层最多包含 5 个域. 带有各种设置的配置指南.
  * [freedns.afraid.org](https://freedns.afraid.org/)  — 免费 DNS 托管. 还基于众多公共用户提供免费子域名 [contributed domains](https://freedns.afraid.org/domain/registry/) . 注册后从“子域名”菜单获取免费子域名.
  * [luadns.com](https://www.luadns.com/) — 免费 DNS 托管，3 个域，所有功能都有合理的限制
  * [namecheap.com](https://www.namecheap.com/domains/freedns/)  — 免费 DNS. 域名数量没有限制
  * [nextdns.io](https://nextdns.io) - 基于 DNS 的防火墙，每月 30 万次免费查询
  * [noip](https://www.noip.com/) — 动态 DNS 服务，允许最多 3 个免费主机名，每 30 天确认一次
  * [ns1.com](https://ns1.com/) — 数据驱动 DNS、自动流量管理、50 万次免费查询
  * [sslip.io](https://sslip.io/) — 免费 DNS 服务，当使用嵌入 IP 地址的主机名进行查询时，会返回该 IP 地址.
  * [zilore.com](https://zilore.com/en/dns) — 免费 DNS 托管，免费 5 个域名.
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) — 免费 DNS 托管，支持动态 DNS.
  * [zonewatcher.com](https://zonewatcher.com)  — 自动备份和 DNS 更改监控.  1 个免费域名
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – 华为免费 DNS 托管
  * [Hetzner](https://www.hetzner.com/dns-console) – Hetzner 提供的免费 DNS 托管，具有 API 支持.
  * [Glauca](https://docs.glauca.digital/hexdns/) – 最多 3 个域的免费 DNS 托管和 DNSSEC 支持


## Domain

  * [eu.org](https://nic.eu.org)  — 免费 eu.org 域名. 请求通常会在 14 天内获得批准.
  * [pp.ua](https://nic.ua/) — 免费 pp.ua 子域.


## IaaS

  * [backblaze.com](https://www.backblaze.com/b2/)  — Backblaze B2 云存储. 无限期免费 10 GB（类似 Amazon S3）对象存储
  * [filebase.com](https://filebase.com/)  - 由区块链支持的 S3 兼容对象存储.  5 GB 无限期免费存储空间.
  * [scaleway](https://www.scaleway.com/en/object-storage/)  — S3 兼容的对象存储. 免费 75 GB 存储空间和外部传出流量（需要信用卡）.
  * [Storj](https://storj.io/)  — 面向应用程序和开发人员的去中心化私有云存储. 免费计划提供 1 个项目、25 GB 存储空间、每月 25 GB 带宽.
  * [Tebi](https://tebi.io/) - S3 兼容对象存储.免费 25 GB 存储和 250GB 出站传输.
  * [Idrive e2](https://www.idrive.com/e2/)  - S3 兼容性对象存储. 每月 10 GB 免费存储空间和 10 GB 下载带宽.
  * [C2 Object Storage](https://c2.synology.com/en-us/pricing/object-storage)  - S3 兼容性对象存储.  15 GB 免费存储空间和每月 15 GB 下载量.


## Managed Data Services

   * [Aiven](https://aiven.io/)  - Aiven 在其开源数据平台上提供免费的 PostgreSQL、MySQL 和 Redis 计划. 单节点、1 个 CPU、1GB RAM，对于 PostgreSQL 和 MySQL，5GB 存储. 轻松迁移到更大的计划或跨云.
   * [airtable.com](https://airtable.com/) — 看起来像电子表格，但它是一个关系数据库，无限的基数，1,200 行/基数和 1,000 个 API 请求/月
   * [Astra](https://www.datastax.com/products/datastax-astra/) — Cloud Native Cassandra as a Service with [80GB free tier](https://www.datastax.com/products/datastax-astra/pricing)
   * [codehooks.io](https://codehooks.io/)  — JavaScript 无服务器 API/后端和数据库服务，具有函数、Mongdb 式查询、键/值查找、作业系统和消息队列. 每个项目免费 1 个实例，每月免费 5000 条记录和 5000 次调用，包括 3 名开发人员. 无需信用卡.
   * [CrateDB](https://crate.io/) - 用于实时分析的分布式开源 SQL 数据库. [Free Tier CRFREE](https://crate.io/lp-crfree) ：单节点2个CPU，2GiB内存，8GiB存储. 每个组织 1 个集群，无需付款方式.
   * [elephantsql.com](https://www.elephantsql.com/) — PostgreSQL 即服务，20 MB 免费
   * [FaunaDB](https://fauna.com/) — 无服务器云数据库，具有原生 GraphQL、多模型访问和高达 100 MB 的每日免费套餐
   * [HarperDb](https://harperdb.io/) — 无服务器云数据库，具有基于 JSON 的动态模式、3000 IOPS 和 1GB 存储
   * [Upstash](https://upstash.com/) — 无服务器 Redis，免费套餐每天最多 10,000 个请求、最大数据库大小 256MB 和 20 个并发连接
   * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — 免费套餐提供 512 MB
   * [redsmin.com](https://www.redsmin.com/) — Redis在线实时监控和管理服务，免费监控1个Redis实例
   * [redislabs](https://redislabs.com/try-free/) - 免费30MB Redis实例
   * [MemCachier](https://www.memcachier.com/)  — 托管 Memcache 服务. 免费提供高达 25MB、1 个代理服务器和基本分析
   * [scalingo.com](https://scalingo.com/) — 主要是 PaaS，但提供 128MB 至 192MB 免费的 MySQL、PostgreSQL 或 MongoDB
   * [SeaTable](https://seatable.io/)  — 由 Seafile 团队构建的灵活的、类似电子表格的数据库. 无限表、2,000 行、1 个月版本控制、最多 25 名团队成员.
   * [skyvia.com](https://skyvia.com/) — 云数据平台，提供免费套餐，所有计划在测试阶段都是完全免费
   * [StackBy](https://stackby.com/)  — 一款集电子表格的灵活性、数据库的强大功能以及与您最喜爱的业务应用程序的内置集成于一体的工具. 免费计划包括无限用户、10 个堆栈、每个堆栈 2GB 附件.
   * [TiDB Cloud](https://en.pingcap.com/tidb-cloud/)  — TiDB 是一个开源的 MySQL 兼容的分布式 HTAP RDBMS.  TiDB Serverless 每月免费提供 5GB 行存储和 5GB 列存储以及 5​​000 万个请求单元（RU）.
   * [Turso by ChiselStrike](https://chiselstrike.com/)  - Turso 是边缘数据库中的 SQLite 开发人员体验.  Turso 提供永久免费入门计划、8 GB 总存储空间、最多 3 个数据库、最多 3 个位置、每月 10 亿行读取以及 SQLite 本地开发支持.
   * [InfluxDB](https://www.influxdata.com/) — Timeseries 数据库，可释放高达 3MB/5 分钟写入、30MB/5 分钟读取和 10,000 个基数系列
   * [restdb.io](https://restdb.io/)  - 快速简单的NoSQL云数据库服务. 通过restdb.io，您可以获得架构、关系、自动 REST API（带有类似 MongoDB 的查询）以及用于处理数据的高效多用户管理 UI. 免费计划允许 3 个用户、2500 条记录和每秒 1 个 API 请求.
   * [cockroachlabs.com](https://www.cockroachlabs.com/free-tier/) — 免费 CockroachDB 高达 5GB 和 1vCPU（有限 [request units](https://www.cockroachlabs.com/docs/cockroachcloud/serverless-faqs.html#what-are-the-usage-limits-of-cockroachdb-serverless-beta))
   * [Neo4j Aura](https://neo4j.com/cloud/aura/)  — 具有 Cypher 查询语言和 REST API 的托管本机图形 DBMS/分析平台. 图大小限制（50k 节点，175k 关系）.
   * [Neon](https://neon.tech/) — 托管 PostgreSQL，10 个分支，每个分支 3 GB 存储，主分支计算的活动时间没有限制，非主分支计算每月（总计）100 小时的活动时间.
   * [Dgraph Cloud](https://cloud.dgraph.io/pricing?type=free)  — 使用 GraphQL API 管理本机图形 DBMS. 每天仅限 1 MB 数据传输.
   * [Tinybird](https://tinybird.co)  - 无服务器托管 ClickHouse，通过 HTTP 进行无连接数据摄取，让您可以将 SQL 查询发布为托管 HTTP API. 免费套餐无时间限制，每天 10GB 存储 + 1000 个 API 请求.
   * [TigerGraph Cloud](https://www.tigergraph.com/cloud/)  — 托管本机图形 DBMS/分析平台，具有类似 SQL 的图形查询语言和 REST API. 一个具有 2 个 vCPU、8GB 内存和 50GB 存储空间的免费实例，在 1 小时不活动后进入休眠状态.
   * [TerminusCMS](https://terminusdb.com/pricing)  — TerminusDB 的托管免费服务，TerminusDB 是一个用 Prolog 和 Rust 编写的文档和图形数据库. 开发人员免费，企业部署和支持付费服务.
   * [Macrometa](https://www.macrometa.com/)  - 用于构建地理分布式实时应用程序的 noSQL 数据库、Pub/Sub、事件处理和无服务器边缘计算平台. 免费开发帐户可访问 10,000 次操作/天和 200MB 存储空间.
   * [Planetscale](https://planetscale.com/) - PlanetScale 是一个兼容 MySQL 的无服务器数据库平台，由 Vitess 提供支持，1 个免费数据库，包含 1 个生产分支和 1 个开发分支、5GB 存储空间、每个数据库每月读取 10 亿行、每个数据库每月写入 1000 万行.
   * [YugabyteDB](https://cloud.yugabyte.com)  - YugabyteDB 是一个与 PostgreSQL 兼容的分布式 SQL 数据库. 云免费层是 2 个 vCPU、4GB RAM、10GB 磁盘.
   * [filess.io](https://filess.io) - filess.io 是一个平台，您可以免费创建以下 DBMS 的 1 个数据库：MySQL、MariaDB、MongoDB、PostgreSQL.
   * [xata.io](https://xata.io)  - Xata 是一个无服务器数据库，具有内置的强大搜索和分析功能. 一个 API、多个类型安全的客户端库，并针对您的开发工作流程进行了优化. 永久免费套餐对于业余爱好者来说已经足够了，它附带 3 个 Xata 单位，单位定义请参阅网站.
   * [8base.com](https://www.8base.com/) - 8base 是一个全栈低代码开发平台，为 JavaScript 开发人员构建，构建在 MySQL 和 GraphQL 和无服务器后端即服务之上，它允许您使用 UI 应用程序生成器快速开始构建 Web 应用程序并轻松扩展，免费套餐包括：行数：2,500、存储：500Mb、无服务器计算：1Gb/h、客户端应用程序用户：5.




## Tunneling, WebRTC, Web Socket Servers and Other Routers

   * [Pinggy](https://pinggy.io)  — 使用单个命令即可获取本地主机的公共 URL，无需下载.  HTTPS / TCP / TLS 隧道. 免费计划的隧道使用寿命为 60 分钟.
   * [conveyor.cloud](https://conveyor.cloud/) — Visual Studio 扩展，用于将 IIS Express 公开到本地网络或通过隧道公开到公共 URL.
   * [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi 是一项托管 VPN 服务，可让您通过免费计划安全地将类似 LAN 的网络扩展到分布式团队，允许最多 5 人的无限网络
   * [localhost.run](https://localhost.run/) — 通过隧道将本地运行的服务器公开到公共 URL.
   * [localtunnel](https://theboroer.github.io/localtunnel-www/)  — 通过隧道将本地运行的服务器公开到公共 URL. 免费托管版本，以及 [open source](https://github.com/localtunnel/localtunnel).
   * [ngrok.com](https://ngrok.com/) — 通过隧道将本地运行的服务器公开到公共 URL.
   * [Radmin VPN](https://www.radmin-vpn.com/)  — 通过 VPN 将多台计算机连接在一起，从而实现类似 LAN 的网络. 无限的同行.  （Hamachi替代品）
   * [segment.com](https://segment.com/)  — 将事件转换并路由到其他第三方服务的中心. 每月 100,000 个活动免费
   * [STUN](https://en.wikipedia.org/wiki/STUN) — 用户数据报协议 [UDP] 通过网络地址转换器 [NAT] 的会话遍历
     * 谷歌 STUN — [https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302](https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302)
     * Twilio STUN — [https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp](https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp)
   * [Tailscale](https://tailscale.com/)  — 零配置 VPN，使用开源 WireGuard 协议. 安装在 MacOS、iOS、Windows、Linux 和 Android 设备上. 适合 100 台设备和 3 位用户的个人使用的免费计划.
   * [webhookrelay.com](https://webhookrelay.com)  — 管理、调试、扇出并将所有 Webhooks 代理到公共或内部（即：本地主机）目的地. 此外，通过获取公共 HTTP 端点 (`https://yoursubdomain.webrelay.io &lt;----&gt; http://localhost:8080`)，通过隧道公开在专用网络中运行的服务器.
   * [Hookdeck](https://hookdeck.com/pricing)  — 从一个地方开发、测试和监控您的 webhook. 每月 10 万次请求和 10 万次尝试，保留 3 天.
   * [Xirsys](https://www.xirsys.com/pricing/) — 无限 STUN 使用 + 每月 500 MB TURN 带宽、带宽上限、单一地理区域.
   * [ZeroTier](https://www.zerotier.com)  — 自由和开源软件管理的虚拟以太网即服务. 免费计划中 25 个客户端的无限端对端加密网络. 桌面/移动/北美客户端； 用于配置自定义路由规则和批准专用网络上的新客户端节点的 Web 界面
   * [LocalXpose](https://localxpose.io)  — 反向代理使您能够将本地主机服务器公开到互联网. 免费计划的隧道寿命为 15 分钟.
   * [Traefik-Hub](https://traefik.io/traefik-hub/)  - 通过隧道将本地运行的服务发布到公共自定义 URL，并通过访问控制保护它们. 一个集群中的 5 个服务免费.


## Issue Tracking and Project Management

   * [acunote.com](https://www.acunote.com/) — 最多可供 5 名团队成员使用的免费项目管理和 SCRUM 软件
   * [asana.com](https://asana.com/) — 与合作者的私人项目免费
   * [Backlog](https://backlog.com)  — 您的团队在一个平台上发布优秀项目所需的一切. 免费计划提供 1 个具有 10 个用户和 100MB 存储空间的项目.
   * [Basecamp](https://basecamp.com/personal)  - 待办事项列表、里程碑管理、类似论坛的消息传递、文件共享和时间跟踪. 最多 3 个项目、20 个用户和 1GB 存储空间.
   * [bitrix24.com](https://www.bitrix24.com/)  — 内联网和项目管理工具. 免费计划有 5GB，可供无限用户使用.
   * [cacoo.com](https://cacoo.com/)  — 实时在线图表：流程图、UML、网络. 自由最大.  15 个用户/图表，25 张
   * [Chpokify](https://chpokify.com/)  — 基于团队的规划扑克，可节省冲刺估算时间. 免费最多 5 个用户、免费 Jira 集成、无限视频通话、无限团队、无限会话.
   * [clickup.com](https://clickup.com/)  - 项目管理. 免费的高级版本，带有云存储. 提供移动应用程序和 Git 集成
   * [Clockify](https://clockify.me) - Time tracker and timesheet app that lets you track work hours across projects. Unlimited users, free forever.
   * [Cloudcraft](https://cloudcraft.co/)  — 使用 Cloudcraft 视觉设计器在几分钟内设计出专业的架构图，该设计器针对 AWS 进行了优化，并具有显示实时数据的智能组件. 免费计划为单个用户提供无限的私人图表.
   * [Codegiant](https://codegiant.io)  — 具有存储库托管和 CI/CD 的项目管理. 免费计划提供无限的存储库、项目和文档，由 5 名团队成员组成. 每月 500 CI/CD 分钟. 每月 30000 分钟无服务器代码运行时间.1GB 存储库存储.
   * [Confluence](https://www.atlassian.com/software/confluence)  - Atlassian 的内容协作工具用于帮助团队高效协作和共享知识. 免费计划最多 10 个用户.
   * [contriber.com](https://www.contriber.com/) — 可定制的项目管理平台、免费入门计划、5 个工作区
   * [diagrams.net](https://app.diagrams.net/)  — 在线图表存储在本地、Google Drive、OneDrive 或 Dropbox 中. 所有功能和存储级别均免费
   * [freedcamp.com](https://freedcamp.com/)  - 任务、讨论、里程碑、时间跟踪、日历、文件和密码管理器. 免费计划，项目、用户和文件存储不受限制.
   * [easyretro.io](https://www.easyretro.io/)  — 简单直观的冲刺回顾工具. 免费计划有 3 个公共板，每个板每月有 1 次调查.
   * [GForge](https://gforge.com)  — 用于具有自营和 SaaS 选项的复杂项目的项目管理和问题跟踪工具集.  SaaS 免费计划为前 5 位用户免费提供开源项目.
   * [gleek.io](https://www.gleek.io)  — 为开发人员提供的免费描述到图表工具. 使用关键字创建非正式的 UML 类、对象或实体关系图.
   * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector)  - GraphQL Inspector 输出两个 GraphQL 模式之间的更改列表. 每个更改都经过精确解释并标记为破坏性、非破坏性或危险性.
   * [huboard.com](https://huboard.com/) — 针对 GitHub 问题的即时项目管理，免费开源
   * [Hygger](https://hygger.io)  — 项目管理平台. 免费计划提供无限的用户、项目和板以及 100 MB 存储空间.
   * [Instabug](https://instabug.com) —  A comprehensive bug reporting and in-app feedback SDK for mobile apps. Free plan up to 1 app and 1 member.
   * [Ilograph](https://www.ilograph.com/)   — 交互式图表，允许用户从多个角度和详细程度查看其基础设施. 图表可以用代码来表达. 免费套餐拥有无限的私人图表，最多可容纳 3 位查看者.
   * [Jira](https://www.atlassian.com/software/jira)  — 在许多企业环境中使用的高级软件开发项目管理工具. 免费计划最多 10 个用户.
   * [kanbanflow.com](https://kanbanflow.com/)  — 基于董事会的项目管理. 免费，高级版本有更多选择
   * [kanbantool.com](https://kanbantool.com/)  — 基于看板的项目管理. 免费计划有 2 个板、2 个用户，没有附件或文件.
   * [Kitemaker.co](https://kitemaker.co)  - 在产品开发流程的所有阶段进行协作，并跟踪 Slack、Discord、Figma 和 Github 上的工作. 无限用户，无限空间. 免费计划最多 250 个工作项目.
   * [Kiter.app](https://www.kiter.app/)  - 让任何人都可以组织自己的求职并跟踪面试、机会和联系. 强大的网络应用程序和 Chrome 扩展. 完全免费.
   * [Kumu.io](https://kumu.io/)   — 带有动画、装饰、过滤器、聚类、电子表格导入等的关系图. 免费套餐允许无限的公共项目. 图形大小不受限制. 为学生提供免费的私人项目. 如果您不想将文件公开在线（上传、编辑、下载、丢弃），则可以使用沙盒模式.
   * [Linear](https://linear.app/)  — 具有简化界面的问题跟踪器. 会员免费，上传文件大小不超过 10MB，250 期（不包括存档）
   * [Lucidchart](https://www.lucidchart.com/)  - 具有协作功能的在线图表工具. 免费计划，包含 3 个可编辑文档、100 个专业模板和基本协作功能.
   * [MeisterTask](https://www.meistertask.com/)  — 团队在线任务管理. 免费最多3个项目，项目成员不受限制.
   * [MeuScrum](https://www.meuscrum.com/en) - 带看板的免费在线 Scrum 工具
   * [nTask](https://www.ntaskmanager.com/)  — 项目管理软件使您的团队能够协作、计划、分析和管理日常任务. 基本计划永久免费，100 MB 存储空间，5 个用户/团队. 无限的工作空间、会议、任务、时间表和问题跟踪.
   * [Ora](https://ora.pm/)  - 敏捷的任务管理和团队协作. 最多 3 位用户免费，文件大小限制为 10 MB.
   * [pivotaltracker.com](https://www.pivotaltracker.com/) — 免费用于无限的公共项目和两个私人项目，总共有 3 个活跃用户（读写）和无限的被动用户（只读）.
   * [Plaky](https://plaky.com)  - 免费的任务管理（看板）软件，没有任何限制. 无限用户，无限项目，永久免费.
   * [plan.io](https://plan.io/)  — 具有存储库托管和更多选项的项目管理.  2 位用户、10 位客户和 500MB 存储空间免费
   * [Plane](https://plane.so/)  - Plane 是一个简单、可扩展、开源的项目和产品管理工具. 会员免费，上传文件大小不超过 5MB，1000 期.
   * [planitpoker.com](https://www.planitpoker.com/) — 免费在线规划扑克（估算工具）
   * [point.poker](https://www.point.poker/)  - 在线规划扑克（基于共识的估计工具）. 免费提供无限用户、团队、会议、回合和投票. 无需注册.
   * [ScrumFast](https://www.scrumfast.com) - Scrum 板具有非常直观的界面，最多可免费容纳 5 个用户.
   * [Shake](https://www.shakebugs.com/)  - 适用于移动应用程序的应用程序内错误报告和反馈工具. 免费计划，每个应用程序每月 10 个错误报告.
   * [Shortcut](https://shortcut.com/)  - 项目管理平台. 最多 10 位用户永久免费.
   * [SpeedBoard](https://speedboard.app) - Board for Agile and Scrum retrospectives - Free.
   * [SuperPM](https://superpm.app/)  - 多功能项目管理平台. 最多可免费使用 3 个项目、无限用户、1 GB 存储空间.
   * [Tadum](https://tadum.app) - 专为定期会议而设计的会议议程和会议记录应用程序，可供 10 人以下的团队免费使用
   * [taiga.io](https://taiga.io/) — 面向初创公司和敏捷开发人员的项目管理平台，免费开源
   * [Tara AI](https://tara.ai/)  — 简单的冲刺管理服务. 免费计划具有无限的任务、冲刺和工作空间，没有用户限制.
   * [targetprocess.com](https://www.targetprocess.com/)  — 可视化项目管理，从看板和 Scrum 到几乎任何操作流程. 免费供无限用户使用，最多 1,000 个数据实体 {[more details](https://www.targetprocess.com/pricing/)}
   * [taskade.com](https://www.taskade.com/)  — 团队的实时协作任务列表和大纲. 免费计划有： 1 个包含无限任务和项目的工作区；  1GB文件存储空间；  1周的项目历史； 每个视频会议有 5 名与会者.
   * [taskulu.com](https://taskulu.com/)  — 基于角色的项目管理. 释放最多 5 个用户. 与 GitHub/Trello/Dropbox/Google Drive 集成
   * [teamwork.com](https://teamwork.com/)  — 项目管理和团队聊天.  5 个用户和 2 个项目免费. 提供高级计划.
   * [teleretro.com](https://www.teleretro.com/)  — 简单有趣的回顾工具，包含破冰游戏、GIF 和表情符号. 免费计划包括 3 次回顾和无限会员.
   * [testlio.com](https://testlio.com/)  — 问题跟踪、测试管理和 Beta 测试平台. 免费供私人使用
   * [terrastruct.com](https://terrastruct.com/)  — 专门用于软件架构的在线图表制作器. 每个图表最多 4 层的免费层.
   * [todoist.com](https://todoist.com/)  — 协作和个人任务管理. 免费计划有：5个活跃项目，项目中有5个用户，文件上传最多5MB，3个过滤器，1周的活动历史记录.
   * [trello.com](https://trello.com/)  — 基于董事会的项目管理. 无限个个人看板，10 个团队看板.
   * [Tweek](https://tweek.so/) — 简单的每周待办事项日历和任务管理.
   * [ubertesters.com](https://ubertesters.com/) — 测试平台、集成和众测人员、2 个项目、5 名成员
   * [vabotu](https://vabotu.com/)  - 项目管理的协作工具. 提供免费和其他计划. 自由职业计划适用于 10 位用户，包括消息传递、任务板、5GB 在线存储、工作区、导出数据.
   * [Wikifactory](https://wikifactory.com/) — Product designing Service with Projects, VCS & Issues. Free plan offers unlimited projects & collaborators and 3GB storage.
   * [Yodiz](https://www.yodiz.com/)  — 敏捷开发和问题跟踪. 最多可免费使用 3 个用户，项目不受限制.
   * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud)  — 免费托管 YouTrack (InCloud)，用于 FOSS 项目、私人项目（3 个用户免费）. 包括时间跟踪和敏捷板
   * [zenhub.com](https://www.zenhub.com)  — GitHub 内唯一的项目管理解决方案. 对公共仓库、OSS 和非营利组织免费
   * [zenkit.com](https://zenkit.com)  — 项目管理和协作工具. 最多 5 名成员免费，附件 5 GB.
   * [Zube](https://zube.io)  — 项目管理，提供 4 个项目和 4 个用户的免费计划.  GitHub 集成可用.
   * [Toggl](https://toggl.com/) — 提供 2 个免费的生产力工具. [Toggl Track](https://toggl.com/track/) 具有免费计划的时间管理和跟踪应用程序提供专为自由职业者设计的无缝时间跟踪和报告. 它拥有无限的跟踪记录、项目、客户、标签、报告等. 和 [Toggl Plan](https://toggl.com/plan/) 用于任务规划，为独立开发人员提供免费计划，具有无限的任务、里程碑和时间表.
   * [Sflow](https://sflow.io)  — sflow.io 是一款项目管理工具，专为软件敏捷开发、营销、销售和客户支持而构建，特别适用于外包项目和跨组织协作项目. 免费计划最多 3 个项目和 5 名成员.
   * [Pulse.red](https://pulse.red) — 适用于项目的免费简约时间跟踪器和时间表应用程序.


## Storage and Media Processing

   * [AndroidFileHost](https://androidfilehost.com/) - 免费文件共享平台，速度、带宽、文件数量、下载数量等不受限制.主要针对 Android 开发相关文件，如 APK 构建、自定义 ROM 和修改等.但似乎也接受任何其他文件.
   * [borgbase.com](https://www.borgbase.com/)  — 用于 Borg Backup 的简单且安全的异地备份托管.  10 GB 可用备份空间和 2 个存储库.
   * [icedrive.net](https://www.icedrive.net/)  - 简单的云存储服务.  10 GB 免费存储空间
   * [sync.com](https://www.sync.com/)  - 端到端云存储服务.  5 GB 免费存储空间
   * [pcloud.com](https://www.pcloud.com/)  - 云存储服务. 高达 10 GB 的免费存储空间
   * [sirv.com](https://sirv.com/)  — 智能图像 CDN，具有动态图像优化和调整大小功能. 免费套餐包括 500 MB 存储空间和 2 GB 带宽.
   * [cloudimage.io](https://www.cloudimage.io/en/home)  — 全面的图像优化和 CDN 服务，在全球拥有 1500 多个接入点. 多种图像缩放、压缩、水印功能. 用于响应式图像、360 度图像制作和图像编辑的开源插件. 免费包月计划，提供 25GB CDN 流量和 25GB 缓存存储以及无限转换.
   * [cloudinary.com](https://cloudinary.com/)  — 图像上传、强大的操作、网站和应用程序的存储和交付，以及 Ruby、Python、Java、PHP、Objective-C 等库. 免费套餐包括 25 个每月积分.  1 个积分相当于 1,000 次图像转换、1 GB 存储空间或 1 GB CDN 使用量.
   * [embed.ly](https://embed.ly/)  — 提供用于在网页中嵌入媒体、响应式图像缩放、从网页中提取元素的 API. 每月最多可免费访问 5,000 个 URL，每秒 15 个请求
   * [filestack.com](https://www.filestack.com/) — 文件选择器、转换和交付，免费提供 250 个文件、500 次转换和 3 GB 带宽
   * [file.io](https://www.file.io)  - 2 GB 文件存储空间. 下载 1 次后文件将自动删除. 用于与存储交互的 REST API. 速率限制 1 个请求/分钟.
   * [freetools.site](https://freetools.site/)  — 免费在线工具. 转换或编辑文档、图像、音频、视频等.
   * [GoFile.io](https://gofile.io/)  - 免费文件共享和存储平台，可以通过基于 Web 的 UI 和 API 使用. 不限制文件大小、带宽、下载次数等.但是当文件变为非活动状态（超过 10 天没有下载）时，它将被删除.
   * [gumlet.com](https://www.gumlet.com/)  — 图像调整大小即服务. 它还优化图像并通过 CDN 执行交付. 免费套餐包括 1 GB 带宽和一年内每月无限数量的图像处理.
   * [image-charts.com](https://www.image-charts.com/) — 无限量生成带有水印的图像图表
   * [Imgbot](https://github.com/marketplace/imgbot)  — Imgbot 是一个友好的机器人，可以优化您的图像并节省您的时间. 优化的图像意味着在不牺牲质量的情况下更小的文件大小. 它是免费的开源软件.
   * [imgen](https://www.jitbit.com/imgen/) - Free unlimited social cover image generation API, no watermark
   * [kraken.io](https://kraken.io/) — 网站性能图像优化即服务，免费计划最大文件大小为 1 MB
   * [kvstore.io](https://www.kvstore.io/)  — 键值存储服务. 免费套餐允许 100 个密钥、1KB/密钥、100 次调用/小时
   * [npoint.io](https://www.npoint.io/) — 具有协作模式编辑功能的 JSON 存储
   * [nitropack.io](https://nitropack.io/)  - 通过完整的前端优化（缓存、图像和代码优化、CDN），加快网站的自动运行速度. 每月最多 5,000 次浏览量免费
   * [otixo.com](https://www.otixo.com/)  — 从一处加密、共享、复制和移动所有云存储文件. 基本计划提供无限制的文件传输，最大 250 MB. 文件大小并允许 5 个加密文件
   * [packagecloud.io](https://packagecloud.io/)  — YUM、APT、RubyGem 和 PyPI 的托管包存储库. 有限的免费计划，可根据要求提供开源计划
   * [getpantry.cloud](https://getpantry.cloud/) — 一个简单的 JSON 数据存储 API，非常适合个人项目、黑客马拉松和移动应用程序！
   * [piio.co](https://piio.co/)  — 每个网站的响应式图像优化和交付. 为开发者和个人网站提供免费计划. 包括开箱即用的免费 CDN、WebP 和延迟加载.
   * [Pinata IPFS](https://pinata.cloud)  — Pinata 是在 IPFS 上上传和管理文件的最简单方法. 我们友好的用户界面与 IPFS API 相结合，使 Pinata 成为平台、创作者和收藏者最简单的 IPFS 固定服务.  1 GB 免费存储空间以及 API 访问权限.
   * [placekitten.com](https://placekitten.com/) — 一种快速简单的服务，用于获取小猫的照片以用作占位符
   * [plot.ly](https://plot.ly/)  — 绘制图表并分享您的数据. 免费套餐包括无限量的公共文件和 10 个私人文件
   * [podio.com](https://podio.com/) — 您可以与最多五人的团队一起使用 Podio，并尝试基本计划的功能（用户管理除外）
   * [QuickChart](https://quickchart.io) — 生成可嵌入的图像图表、图表和二维码
   * [redbooth.com](https://redbooth.com) — P2P 文件同步，最多 2 个用户免费
  * [resmush.it](https://resmush.it)  — reSmush.it 是一个提供图像优化的免费 API.  reSmush.it 已在最常见的 CMS 上实现，例如 Wordpress、Drupal 或 Magento.  reSmush.it 是最常用的图像优化 API，已处理超过 70 亿张图像，并且仍然免费.
   * [Shotstack](https://shotstack.io)  - 用于大规模生成和编辑视频的 API. 每月免费最多 20 分钟的渲染视频
   * [tinypng.com](https://tinypng.com/) — 用于压缩 PNG 和 JPEG 图像并调整其大小的 API，每月免费提供 500 次压缩
   * [transloadit.com](https://transloadit.com/)  — 处理视频、音频、图像、文档的文件上传和编码. 通过 GitHub 学生开发包免费向开源、慈善机构和学生开放. 商业应用程序可免费获得 2 GB 用于测试驱动
   * [twicpics.com](https://www.twicpics.com)  - 响应式图像即服务. 它提供图像 CDN、媒体处理 API 和前端库来自动优化图像. 该服务每月最多可免费使用 3GB 流量.
   * [uploadcare.com](https://uploadcare.com/hub/developers/)  — Uploadcare 为媒体管道提供基于尖端算法的终极工具包. 所有功能均完全免费供开发人员使用：文件上传 API 和 UI、图像 CDN 和源服务、自适应交付和智能压缩. 限制免费套餐具有 3000 次上传、3 GB 流量和 3 GB 存储空间.
   * [imagekit.io](https://imagekit.io)  – 具有自动优化、实时转换和存储功能的图像 CDN，您可以在几分钟内与现有设置集成. 免费计划包括每月高达 20GB 的带宽.
   * [internxt.com](https://internxt.com)  – Internxt Drive 是一种零知识文件存储服务，基于绝对隐私和毫不妥协的安全性. 注册并永久免费获得 10 GB！
   * [degoo.com](https://degoo.com/) – 基于人工智能的云存储，免费高达 20 Gb，3 台设备，5 Gb 推荐奖金（90 天帐户不活动）.



## Design and UI

  * [AllTheFreeStock](https://allthefreestock.com) - 免费库存图片、音频和视频的精选列表.
  * [Ant Design Landing Page](https://landing.ant.design/)  - Ant Design Landing Page 提供了由 Ant Motion 的运动组件构建的模板. 拥有丰富的首页模板，下载模板代码包，即可快速使用. 您还可以使用编辑器快速构建自己的专用页面.
  * [Backlight](https://backlight.dev/) — Backlight 注重开发人员和设计师之间的协作，是一个非常完整的编码平台，团队可以在其中构建、记录、发布、扩展和维护设计系统.免费计划允许最多 3 名编辑人员在 1 个设计系统上工作，且查看者数量不受限制.
  * [BoxySVG](https://boxy-svg.com/app) — 一个免费的可安装 Web 应用程序，用于绘制 SVG 并以 svg、png、jpeg 和其他格式导出.
  * [Circum Icons](https://circumicons.com) - React、Vue 和 Svelte 的一致开源图标为 SVG.
  * [clevebrush.com](https://www.cleverbrush.com/) — 免费图形设计/照片拼贴应用程序，他们还提供付费集成作为组件.
  * [cloudconvert.com](https://cloudconvert.com/)  — 将任何东西转换成任何东西.  208 种支持格式，包括视频到 gif.
  * [CodeMyUI](https://codemyui.com) - 精心挑选的网页设计和用户界面灵感与代码片段的集合.
  * [ColorKit](https://colorkit.co/) - 在线创建调色板或从顶级调色板中获取灵感.
  * [coolors](https://coolors.co/)  - 调色板生成器. 自由的.
  * [Branition](https://branition.com/colors) - 手工策划的最适合品牌的调色板.
  * [css-gradient.com](https://www.css-gradient.com/)  - 免费工具可轻松生成自定义跨浏览器 CSS 渐变.  RGB 和 HEX 格式.
  * [designer.io](https://www.designer.io/)  — 用于 UI、插图等的设计工具. 有一个本机应用程序. 自由的.
  * [easyvectors.com](https://easyvectors.com/)  — EasyVectors.com 是优质免费 SVG 矢量艺术的库存. 完全免费下载最佳矢量图形.
  * [figma.com](https://www.figma.com)  — 团队在线协作设计工具； 免费套餐包括无限的文件和查看器，最多 2 个编辑器和 3 个项目.
  * [framer.com](https://www.framer.com/)  - Framer 可帮助您为您的下一个应用程序、网站或产品迭代和动画化界面创意 - 从强大的布局开始. 对于任何验证 Framer 作为专业原型设计工具的人：无限的查看者、最多 2 名编辑、最多 3 个项目.
  * [freeforcommercialuse.net](https://freeforcommercialuse.net/) — FFCU 无忧模型/财产发布 库存照片
  * [Gradientos](https://www.gradientos.app) - 使选择渐变变得快速而简单.
  * [Icon Horse](https://icon.horse) – 通过我们简单的 API 获取任何网站的最高分辨率图标.
  * [Icons8](https://icons8.com)  — 图标、插图、照片、音乐和设计工具. 免费计划提供有限的低分辨率格式. 当您使用我们的资源时链接到 Icons8.
  * [Invision App](https://www.invisionapp.com)  - UI 设计和原型设计工具. 提供桌面和网络应用程序. 可免费与 1 个活动原型一起使用.
  * [landen.co](https://www.landen.co)  — 为您的初创企业生成、编辑和发布精美的网站和登陆页面. 全部无代码. 免费套餐允许您拥有一个完全可定制并在网络上发布的网站.
  * [lensdump.com](https://lensdump.com/) - 免费云图像托管.
  * [Lorem Picsum](https://picsum.photos/)  - 免费工具，易于使用的时尚占位符. 只需在我们的 URL 后添加您想要的图像尺寸（宽度和高度），您就会获得随机图像.
  * [LottieFiles](https://lottiefiles.com/)  - 世界上最大的在线平台，为设计师、开发人员等提供世界上最小的动画格式. 访问适用于 Android、iOS 和 Web 的 Lottie 动画工具和插件.
  * [MagicPattern](https://www.magicpattern.design/tools) — CSS 和 SVG 背景生成器以及渐变、图案和斑点工具的集合.
  * [marvelapp.com](https://marvelapp.com/) — 设计、原型制作和协作，仅限一名用户和一个项目的免费计划.
  * [Mindmup.com](https://www.mindmup.com/)  — 免费无限量思维导图，并将其存储在云端. 您的思维导图可以通过任何设备随时随地使用.
  * [Mockplus iDoc](https://www.mockplus.com/idoc)  - Mockplus iDoc是一款功能强大的设计协作和交接工具. 免费计划包括 3 个用户和 5 个项目，提供所有可用功能.
  * [mockupmark.com](https://mockupmark.com/create/free) — 为社交媒体和电子商务创建逼真的 T 恤和服装模型，40 个免费模型.
  * [Octopus.do](https://octopus.do)  — 可视化站点地图生成器. 实时构建您的网站结构并快速共享它以与您的团队或客户协作.
  * [Pencil](https://github.com/evolus/pencil) - 使用 Electron 的开源设计工具.
  * [Penpot](https://penpot.app)  - 基于网络的开源设计和原型设计工具. 支持 SVG. 完全免费.
  * [pexels.com](https://www.pexels.com/)  - 用于商业用途的免费库存照片. 拥有免费的 API，允许您通过关键字搜索照片.
  * [photopea.com](https://www.photopea.com) — 一款免费、高级的在线设计编辑器，带有 Adob​​e Photoshop UI，支持 PSD、XCF 和 Sketch 格式（Adobe Photoshop、Gimp 和 Sketch 应用程序）.
  * [pixlr.com](https://pixlr.com/) — 商业级别的免费在线浏览器编辑器.
  * [Plasmic](https://www.plasmic.app/)  - 快速、易于使用、功能强大的网页设计工具和页面构建器，可集成到您的代码库中. 构建响应式页面或复杂组件； 可选择使用代码扩展； 并发布到生产站点和应用程序.
  * [Pravatar](https://pravatar.cc/) - 生成随机/占位符假头像，该网址可以直接热链接到您的网络/应用程序中.
  * [Proto.io](https://www.proto.io)  - 无需编码即可创建完全交互式的 UI 原型. 免费试用结束后可使用免费套餐. 免费套餐包括：1 个用户、1 个项目、5 个原型、100MB 在线存储和 proto.io 应用程序中的预览.
  * [resizeappicon.com](https://resizeappicon.com/) — 一项用于调整应用程序图标大小和管理应用程序图标的简单服务.
  * [Rive](https://rive.app)  — 创建精美的动画并将其发送到任何平台. 个人永久免费. 该服务是一个编辑器，它也在其服务器上托管所有图形. 它们还为许多平台提供运行时来运行使用 Rive 制作的图形.
  * [storyset.com](https://storyset.com/) — 使用此工具为您的项目创建精彩的免费定制插图.
  * [smartmockups.com](https://smartmockups.com/) — Create product mockups, 200 free mockups.
  * [tabler-icons.io](https://tabler-icons.io/) — 超过 1500 个免费复制和粘贴 SVG 可编辑图标.
  * [UI Avatars](https://ui-avatars.com/)  - 生成带有姓名首字母缩写的头像. 这些网址可以直接热链接到您的网络/应用程序中. 支持通过url配置参数.
  * [unDraw](https://undraw.co/) - 不断更新的精美 svg 图像集合，您可以完全免费且无需归属地使用.
  * [unsplash.com](https://unsplash.com/) - 用于商业和非商业目的的免费库存照片（做任何你想做的许可）.
  * [vectr.com](https://vectr.com/) — 适用于 Web + 桌面的免费设计应用程序.
  * [walkme.com](https://www.walkme.com/) — 企业级指导和参与平台，免费计划 3 次步行，最多 5 步/步行.
  * [Webflow](https://webflow.com)  - 所见即所得的网站构建器，带有动画和网站托管.  2个项目免费.
  * [Updrafts.app](https://updrafts.app)  - 用于基于 tailwindcss 设计的所见即所得网站构建器. 免费用于非商业用途.
  * [whimsical.com](https://whimsical.com/)  - 协作流程图、线框图、便签和思维导图. 创建最多 4 个空闲板.
  * [Zeplin](https://zeplin.io/)  — 设计师和开发人员协作平台. 显示设计、资产和风格指南.  1 个项目免费.
  * [Pixelixe](https://pixelixe.com/) — 在线创建和编辑引人入胜且独特的图形和图像.
  * [Responsively App](https://responsively.app) - 一个免费的开发工具，用于更快、更精确的响应式 Web 应用程序开发.
  * [SceneLab](https://scenelab.io) - 在线模型图形编辑器，具有不断扩展的免费设计模板集合
  * [xLayers](https://xlayers.dev) - 预览 Sketch 设计文件并将其转换为 Angular、React、Vue、LitElement、Stencil、Xamarin 等（免费开源，位于 https://github.com/xlayers/xlayers）
  * [Grapedrop](https://grapedrop.com/)  — 基于 GrapesJS 框架的响应式、功能强大、SEO 优化的网页构建器. 前 5 页免费，无限的自定义域，所有功能和简单的用法.
  * [Mastershot](https://mastershot.app)  - 完全免费的基于浏览器的视频编辑器. 无水印，最高 1080p 导出选项.
  * [Unicorn Platform](https://unicornplatform.com/)  - 轻松构建具有托管功能的登陆页面.  1 个免费网站.
  * [react-favicon.com](https://react-favicon.com/) - 使用 React 和 JSX 使用任何字体和图标库为您的网站生成 Favicons.
  * [svgrepo.com](https://www.svgrepo.com/)  - 使用各种矢量库探索、搜索并找到最适合您的项目的图标或矢量. 下载免费的 SVG 矢量用于商业用途.
  * [haikei.app](https://www.haikei.app/) - Haikei 是一款 Web 应用程序，用于生成独特的 SVG 形状、背景和图案 - 随时可与您的设计工具和工作流程一起使用.
  * [Canva](https://canva.com) - 用于创建视觉内容的免费在线设计工具.
  * [Superdesigner](https://superdesigner.co) - 一系列免费设计工具，只需点击几下即可创建独特的背景、图案、形状、图像等.
  * [TeleportHQ](https://teleporthq.io/)  - 低代码前端设计和开发平台.  TeleportHQ 是一个协作前端平台，可立即创建和发布无头静态网站.  3个免费项目，无限合作者，免费代码导出.
  * [vector.express](https://vector.express) — 快速轻松地转换您的 AI、CDR、DWG、DXF、EPS、HPGL、PDF、PLT、PS 和 SVG 矢量.
  * [Vertopal](https://www.vertopal.com)  - Vertopal 是一个免费的在线平台，用于将文件转换为各种文件格式. 包括 JPG 到 SVG、GIF 到 APNG、PNG 到 WEBP、JSON 到 XML 等开发人员转换器.
  * [okso.app](https://okso.app)  - 简约的在线绘图应用程序. 允许创建快速草图和视觉笔记. 将草图导出为 PNG、JPG、SVG 和 WEBP. 也可以作为 PWA 安装. 所有人免费使用（无需注册）.
  * [Wdrfree SVG](https://wdrfree.com/free-svg) - 黑白免费 SVG 剪切文件.
  * [Lucide](https://lucide.dev) - 免费的可定制且一致的 SVG 图标工具包.
  * [MDBootstrap](https://mdbootstrap.com/) - 免费供个人和商业使用 Bootstrap、Angular、React 和 Vue UI 套件，包含 700 多个组件、令人惊叹的模板、1 分钟安装、广泛的教程和庞大的社区.
  * [Tailwind Elements](https://tailwind-elements.com/) - 使用 Tailwind CSS 重新创建的免费 Bootstrap 组件，但具有更好的设计和更多功能.
  * [DaisyUI](https://daisyui.com/)  -  自由的.  “使用 Tailwind CSS 但编写更少的类名”提供了按钮等组件.
  * [Scrollbar.app](https://scrollbar.app) -- 简单的免费网络应用程序，用于设计网络的自定义滚动条.
  * [css.glass](https://css.glass/) -- 使用 CSS 创建玻璃形态设计的免费网络应用程序.
  * [hypercolor.dev](https://hypercolor.dev/) -- Tailwind CSS 颜色渐变的精选集合，还提供各种生成器来创建您自己的.
  * [iconify.design](https://icon-sets.iconify.design/)  -- 集合了100多个图标包，界面统一. 允许您跨包搜索图标并将单个图标导出为 SVG 或流行的 Web 框架.
  * [NextUI](https://nextui.org/)  -  自由的. 漂亮、快速、现代的 React 和 Next.js UI 库.
  * [Glyphs](https://glyphs.fyi/) -- 免费、网络上最强大的图标、完全可编辑且真正的开源设计系统.
  * [ShadcnUI](https://ui.shadcn.com/)  -- 设计精美的组件，您可以将其复制并粘贴到您的应用程序中. 无障碍. 可定制. 开源.
  * [HyperUI](https://www.hyperui.dev/) -- 免费开源 Tailwind CSS 组件.


## Design Inspiration

  * [awwwards.](https://www.awwwards.com/) - [热门网站] 展示所有设计最佳的网站（由设计师投票选出）.
  * [Behance](https://www.behance.net/)  - 【设计展示】设计师展示作品的地方. 可按 UI/UX 项目的类别进行过滤.
  * [dribbble](https://dribbble.com/) - [设计展示] 独特的设计灵感，一般不是来自真实的应用.
  * [Landings](https://landings.dev/) - [网页截图] 根据您的喜好找到最适合您设计灵感的登陆页面.
 * [LovelyLanding.net](https://www.lovelylanding.net/)  - [登陆页面设计] 经常更新登陆页面截图. 包括桌面、平板电脑和移动设备的屏幕截图.
  * [Mobbin](https://mobbin.design/) - [移动屏幕截图] 使用我们包含 50,000 多个完全可搜索的移动应用屏幕截图的库，节省 UI 和 UX 研究时间.
  * [Mobile Patterns](https://www.mobile-patterns.com/) - [手机截图] 一个设计灵感库，提供最优秀的 UI UX 模式（iOS 和 Android），供设计师、开发人员和产品制造商参考.
  * [Screenlane](https://screenlane.com/)  - [手机屏幕截图] 获得灵感并跟上最新的网络和移动应用程序 UI 设计趋势. 可按模式和应用程序过滤.
  * [scrnshts](https://scrnshts.club/) - [手机屏幕截图] 精心挑选的最精美的应用商店设计屏幕截图集合.
  * [UI Garage](https://uigarage.net/) - [手机和网页截图] 每日 UI 灵感和模式，供设计师、开发人员为您的项目寻找灵感、工具和最佳资源.
  * [Refero](https://refero.design/) - [Web 屏幕截图] 来自优秀 Web 应用程序的已标记且可搜索的设计参考集合.



## Data Visualization on Maps

   * [IP Geolocation](https://ipgeolocation.io/) — 每月可提供 30K 请求的免费开发者计划.
   * [carto.com](https://carto.com/) — 根据您的数据和公共数据创建地图和地理空间 API.
   * [Clockwork Micro](https://clockworkmicro.com/)  — 像发条一样工作的地图工具. 每月 50,000 次免费查询（地图图块、db2vector、海拔）.
   * [developers.arcgis.com](https://developers.arcgis.com)  — 用于地图、地理空间数据存储、分析、地理编码、路由等的 API 和 SDK，跨 Web、桌面和移动设备.  2,000,000 个免费底图图块、20,000 个非存储地理编码、20,000 条简单路线、5,000 次行驶时间计算、每月 5GB 免费图块+数据存储.
   * [Foursquare](https://developer.foursquare.com/) - 来自 Places API 和 Pilgrim SDK 的位置发现、地点搜索和上下文感知内容.
   * [geoapify.com](https://www.geoapify.com/)  - 矢量和栅格地图图块、地理编码、地点、路线、等值线 API. 每天 3000 个免费请求.
   * [geocod.io](https://www.geocod.io/)  — 通过 API 或 CSV 上传进行地理编码. 每天 2,500 次免费查询.
   * [geocodify.com](https://geocodify.com/)  — 通过 API 或 CSV 上传进行地理编码和地理解析. 每月 10,000 次免费查询.
   * [geojs.io](https://www.geojs.io/) - 高度可用的 REST/JSON/JSONP IP 地理位置查找 API.
   * [giscloud.com](https://www.giscloud.com/) — 在线可视化、分析和共享地理数据.
   * [graphhopper.com](https://www.graphhopper.com/) 为开发人员提供了免费的路由、路线优化、距离矩阵、地理编码、地图匹配包.
   * [here](https://developer.here.com/)  — 用于地图和位置感知应用程序的 API 和 SDK. 每月 25 万笔交易免费.
   * [locationiq.com](https://locationiq.com/)  — 地理编码、地图和路线 API. 每天 5000 个请求免费.
   * [mapbox.com](https://www.mapbox.com/) — 地图、地理空间服务和用于显示地图数据的 SDK.
   * [maptiler.com](https://www.maptiler.com/cloud/)  — 用于地图可视化的矢量地图、地图服务和 SDK. 免费矢量图块，每周更新和四种地图样式.
   * [nextbillion.ai](https://nextbillion.ai/) - 地图相关服务：地理编码、导航（方向、路线、路线优化、距离矩阵）、地图 SDK（矢量、静态、移动 SDK）. [Free with specified quota](https://nextbillion.ai/pricing) 对于每项服务.
   * [opencagedata.com](https://opencagedata.com)  — 聚合 OpenStreetMap 和其他开放地理资源的地理编码 API. 每天 2,500 次免费查询.
   * [osmnames](https://osmnames.org/) — 地理编码，搜索结果按相关维基百科页面的受欢迎程度排名.
   * [positionstack](https://positionstack.com/)  - 全球地点和坐标的免费地理编码. 每月 25.000 个请求供个人使用.
   * [stadiamaps.com](https://stadiamaps.com/)  — 地图图块、路线、导航和其他地理空间 API. 每天 2,500 次免费地图视图和 API 请求，用于非商业使用和测试.
   * [maps.stamen.com](http://maps.stamen.com/) - 免费地图图块和图块托管.
   * [ipstack](https://ipstack.com/) - 通过 IP 地址定位和识别网站访问者
   * [Geokeo api](https://geokeo.com)  - 具有语言校正等功能的地理编码 api. 全球覆盖. 每日 2,500 次免费查询


## Package Build System

   * [build.opensuse.org](https://build.opensuse.org/) — 多个发行版（SUSE、EL、Fedora、Debian 等）的软件包构建服务.
   * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — 针对 Fedora 和 EL 的基于模拟的 RPM 构建服务.
   * [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu 和 Debian 构建服务.


## IDE and Code Editing

   * [3v4l](https://3v4l.org/) - 免费在线 PHP shell 和代码片段共享网站，在 300 多个 PHP 版本中运行您的代码
   * [Android Studio](https://d.android.com/studio)  — Android Studio 提供了在各种类型的 Android 设备上构建应用程序的最快工具. 开源 IDE，对所有人免费，是开发 Android 应用程序的最佳选择. 适用于 Windows、Mac、Linux 甚至 ChromeOS！
   * [Apache Netbeans](https://netbeans.apache.org/) — 开发环境、工具平台和应用框架.
   * [apiary.io](https://apiary.io/) — 协作设计 API，具有即时 API 模拟和生成文档（免费提供无限 API 蓝图和无限用户，只需一个管理员帐户和托管文档）.
   * [Binder](https://mybinder.org/)  - 将 Git 存储库转变为交互式笔记本的集合. 这是一项免费的公共服务.
   * [BlueJ](https://bluej.org)  — 专为初学者设计的免费 Java 开发环境，全球有数百万人使用. 由 Oracle 和简单的 GUI 提供支持，可以帮助初学者.
   * [Bootify.io](https://bootify.io/) - 具有自定义数据库和 REST API 的 Spring Boot 应用程序生成器.
   * [cacher.io](https://www.cacher.io) — 带标签的代码片段管理器并支持 100 多种编程语言.
   * [Code::Blocks](https://codeblocks.org)  — 免费的 Fortran 和 C/C++ IDE. 开源并可在 Windows、macOS 和 Linux 上运行.
   * [codiga.io](https://codiga.io/)  — 编码助手可让您直接在 IDE 中搜索、定义和重用代码片段. 对个人和小型组织免费.
   * [codesnip.com.br](https://codesnip.com.br)  — 带有类别、搜索和标签的简单代码片段管理器. 免费且无限制.
   * [cocalc.com](https://cocalc.com/)  —（以前称为 cloud.sagemath.com 上的 SageMathCloud）— 云端协作计算. 通过浏览器访问完整的 Ubuntu，内置协作和大量预装的数学、科学、数据科学免费软件：Python、LaTeX、Jupyter Notebooks、SageMath、scikitlearn 等.
   * [code.cs50.io](https://code.cs50.io/) - Visual Studio Code for CS50 是 code.cs50.io 上的一个 Web 应用程序，它为学生和教师调整了 GitHub Codespaces.
   * [codepen.io](https://codepen.io/) — CodePen 是网络前端的游乐场.
   * [codesandbox.io](https://codesandbox.io/) — Online Playground for React, Vue, Angular, Preact and more.
   * [Components.studio](https://webcomponents.dev/) - 独立编写组件代码，在故事中可视化它们，测试它们并在 npm 上发布它们.
   * [Eclipse Che](https://www.eclipse.org/che/)  - 面向开发团队的基于 Web 的 Kubernetes 原生 IDE，具有多语言支持. 开源和社区驱动.  Red Hat 托管的在线实例位于 [workspaces.openshift.com](https://workspaces.openshift.com/).
   * [fakejson.com](https://fakejson.com/)  — FakeJSON 可帮助您使用其 API 快速生成虚假数据. 发出 API 请求，描述您想要什么以及如何获得它.  API 以 JSON 形式返回所有内容. 加快创意进入市场的过程，并假装它直到你成功.
   * [GitPod](https://www.gitpod.io)  — GitHub 项目的即时、可立即编码的开发环境. 免费套餐包括每月 50 小时.
   * [ide.goorm.io](https://ide.goorm.io)  goormIDE 是云端的完整 IDE. 多语言支持、基于 Linux 的容器（通过功能齐全的基于 Web 的终端）、端口转发、自定义 url、实时协作和聊天、共享链接、Git/Subversion 支持. 还有更多功能（免费套餐包括每个容器 1GB RAM 和 10GB 存储空间、5 个容器插槽）.
   * [JDoodle](https://www.jdoodle.com) — 适用于 60 多种编程语言的在线编译器和编辑器，提供 REST API 代码免费计划，每天编译最多 200 个学分.
   * [jetbrains.com](https://jetbrains.com/products.html) — 生产力工具、IDE 和部署工具（又名 [IntelliJ IDEA](https://www.jetbrains.com/idea/), [PyCharm](https://www.jetbrains.com/pycharm/) ， ETC）. 学生、教师、开源和用户组的免费许可证.
   * [jsbin.com](https://jsbin.com) — JS Bin 是前端 Web 的另一个游乐场和代码共享网站（HTML、CSS 和 JavaScript.还支持 Markdown、Jade 和 Sass）.
   * [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle 是前端 Web 的游乐场和代码共享站点，也支持协作.
   * [JSONPlaceholder](https://jsonplaceholder.typicode.com/) 一些 REST API 端点以 JSON 格式返回一些虚假数据. 如果您想在本地运行服务器，也可以使用源代码.
   * [Lazarus](https://www.lazarus-ide.org/) — Lazarus 是一款兼容 Delphi 的跨平台 IDE，用于快速应用程序开发.
   * [micro-jaymock](https://micro-jaymock.now.sh/) - 用于生成假 JSON 数据的微型 API 模拟微服务.
   * [mockable.io](https://www.mockable.io/)  — Mockable 是一个简单的可配置服务，用于模拟 RESTful API 或 SOAP Web 服务. 该在线服务允许您快速定义 REST API 或 SOAP 端点并让它们返回 JSON 或 XML 数据.
   * [mockaroo](https://mockaroo.com/)  — Mockaroo 可让您生成 CSV、JSON、SQL 和 Excel 格式的真实测试数据. 您还可以为后端 API 创建模拟.
   * [Mocklets](https://mocklets.com) - 基于 HTTP 的模拟 API 模拟器，有助于模拟 API，以实现更快的并行开发和更全面的测试，并具有终身免费套餐.
   * [Paiza](https://paiza.cloud/en/)  — 在浏览器中开发 Web 应用程序，无需进行任何设置. 免费计划提供 1 台具有 24 小时使用寿命和每天 4 小时运行时间的服务器，具有 2 个 CPU 核心、2 GB RAM 和 1 GB 存储空间.
   * [Prepros](https://prepros.io/)  - Prepros 可以开箱即用地编译 Sass、Less、Stylus、Pug/Jade、Haml、Slim、CoffeeScript 和 TypeScript，重新加载您的浏览器，使开发和测试您的网站变得非常容易，以便您可以专注于使它们变得完美. 您还可以只需单击几下即可添加自己的工具.
   * [Replit](https://replit.com/) — 适用于各种程序语言的云编码环境.
   * [SoloLearn](https://code.sololearn.com)  — 非常适合运行代码片段的云编程游乐场. 支持多种编程语言. 运行代码不需要注册，但需要在其平台上保存代码时需要注册. 还为初学者和中级编码员提供免费课程.
   * [stackblitz.com](https://stackblitz.com/)  — 用于创建、编辑和部署全栈应用程序的在线/云代码 IDE. 支持任何流行的基于 NodeJs 的前端和后端框架. 创建新项目的短链接： [https://node.new](https://node.new).
   * [Visual Studio Code](https://code.visualstudio.com/)  - 代码编辑器重新定义和优化，用于构建和调试现代 Web 和云应用程序. 由微软开发.
      * [Desktop](https://code.visualstudio.com) -（Windows、macOS 和 Linux）.
      * [Online](https://vscode.dev) -（浏览器）
   * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — Fully-featured IDE with thousands of extensions, cross-platform app development (Microsoft extensions available for download for iOS and Android), desktop, web and cloud development, multi-language support (C#, C++, JavaScript, Python, PHP and more).
   * [VSCodium](https://vscodium.com/) - 社区驱动、无遥测/跟踪、免费许可的 Microsoft 编辑器 VSCode 二进制发行版
   * [wakatime.com](https://wakatime.com/) — 关于您的编码活动的量化自我指标，使用文本编辑器插件，有限的免费计划.
   * [WebComponents.dev](https://webcomponents.dev/) — 浏览器内 IDE，可使用 58 个可用模板单独编码 Web 组件，支持故事和测试.
   * [PHPSandbox](https://phpsandbox.io/) — Online developement environment for PHP.


## Analytics, Events and Statistics

   * [Hightouch](https://hightouch.com/)  - Hightouch 是一个反向 ETL 平台，可帮助您将数据仓库中的客户数据同步到 CRM、营销和支持工具. 免费套餐为您提供一个同步数据的目的地.
   * [Avo](https://avo.app/)  — 简化的分析发布工作流程. 单一真实来源跟踪计划、类型安全分析跟踪库、应用内调试器、数据可观察性，可在发布之前捕获所有数据问题. 免费提供 2 名工作区成员和 1 小时数据可观察性回顾.
   * [Branch](https://branch.io)  — 移动分析平台. 免费套餐为多达 10K 移动应用用户提供深度链接和其他服务.
   * [Cauldron](https://cauldron.io)  — 分析开源解决方案，允许用户将来自多个协作平台的信息聚合为不同类型的数据源（Git、Github、Gitlab...）. 免费套餐包括无限数量的报告.
   * [Census](https://www.getcensus.com/)  — 反向 ETL 和运营分析平台. 将数据仓库中的 10 个字段同步到 60 多个 SaaS，例如 Salesforce、Zendesk 或 Amplitude.
   * [Clicky](https://clicky.com)  — 网站分析平台. 免费计划 1 个具有 3000 次浏览次数分析的网站.
   * [Databox](https://databox.com)  — 结合其他分析和 BI 平台的业务洞察和分析. 免费计划提供 3 个用户、仪表板和数据源.  11M历史数据记录.
   * [indicative.com](https://indicative.com/)  — 客户分析平台，用于优化客户参与度、提高转化率并提高保留率. 每月释放多达 2500 万个事件，数据保留 6 个月.
   * [Panelbear.com](https://panelbear.com/) — 速度极快且私密，免费套餐包括每月 5,000 次浏览量，无限网站
   * [Hitsteps.com](https://hitsteps.com/) — 1 个网站每月 2,000 次综合浏览量
   * [amplitude.com](https://amplitude.com/) — 100 万个每月活动，最多 2 个应用程序
   * [Flagsmith](https://flagsmith.com)  - 自信地发布功能； 跨 Web、移动和服务器端应用程序管理功能标志. 使用我们的托管 API、部署到您自己的私有云或在本地运行
   * [GoatCounter](https://www.goatcounter.com/)  — GoatCounter 是一个开源网络分析平台，可作为托管服务（免费用于非商业用途）或自托管应用程序. 它的目标是提供易于使用且有意义的隐私友好型网络分析，作为 Google Analytics 或 Matomo 的替代品. 免费套餐适用于非商业用途，包括无限数量的网站、6 个月的数据保留和每月 10 万页浏览量.
   * [Google Analytics](https://analytics.google.com/) - 谷歌分析
   * [Expensify](https://www.expensify.com/) — 费用报告、免费个人报告审批工作流程
   * [getinsights.io](https://getinsights.io) - 注重隐私、无 cookie 的分析，每月最多可免费观看 5000 个事件.
   * [heap.io](https://heap.io) — Automatically captures every user action in iOS or web apps. Free for up to 5,000 visits/month
   * [Hotjar](https://hotjar.com)  — 网站分析和报告. 免费计划允许每天 2000 次浏览量. 每天 100 个快照（最大容量：300）.  3张快照热图，可保存365天. 无限的团队成员.
   * [Keen](https://keen.io/)  — 用于数据收集、分析和可视化的自定义分析. 每月 1,000 个活动免费
   * [Yandex.Metrica](https://metrica.yandex.com/) — 无限制的免费分析
   * [Mixpanel](https://mixpanel.com/) — 每月 100,000 名跟踪用户、无限数据历史记录和席位、美国或欧盟数据驻留
   * [Moesif](https://www.moesif.com)  — REST 和 GraphQL 的 API 分析.  （免费最多 500,000 次 API 调用/月）
   * [Molasses](https://www.molasses.app)  - 强大的功能标志和 A/B 测试. 释放最多 3 个环境，每个环境有 5 个功能标志.
   * [optimizely.com](https://www.optimizely.com) — A/B 测试解决方案、免费入门计划、1 个网站、1 个 iOS 和 1 个 Android 应用程序
   * [Microsoft PowerBI](https://powerbi.com)  — Microsoft 的业务洞察与分析. 免费计划提供 100 万个用户许可证的有限使用.
   * [quantcast.com](https://www.quantcast.com/products/measure-audience-insights/) — 无限制的免费分析
   * [Row Zero](https://rowzero.io)  - 速度极快、互联的电子表格. 直接连接到数据数据库、S3 和 API. 即时导入、分析、绘制图表并共享数百万行.  3 本免费（永久）的练习册.
   * [sematext.com](https://sematext.com/cloud/) — 每月最多可免费执行 50 K 操作、保留 1 天的数据、无限的仪表板、用户等.
   * [Similar Web](https://similarweb.com)  — Web 和移动应用程序分析. 免费计划为每个指标提供 5 个结果、1 个月的移动应用数据和 3 个月的网站数据.
   * [StatCounter](https://statcounter.com/)  — 网站浏览者分析. 免费计划分析 500 个最近访问者.
   * [Tableau Developer Program](https://www.tableau.com/developer)  — 创新、创造并使 Tableau 完美地适合您的组织. 免费开发者计划为 Tableau Online 提供个人开发沙盒许可证. 该版本是最新的预发布版本，因此数据开发人员可以测试这个卓越平台的每个功能.
   * [usabilityhub.com](https://usabilityhub.com/)  — 在真人身上测试设计和模型，跟踪访客. 一位用户免费，无限次测试
   * [woopra.com](https://www.woopra.com/) — 免费用户分析平台，可进行 50 万次操作、90 天数据保留、30 多个一键集成.
   * [counter.dev](https://counter.dev)  — 网络分析变得简单，因此隐私友好. 免费或通过捐赠支付您想要的费用.
   * [PostHog](https://posthog.com) - 完整的产品分析套件免费，每月最多可跟踪 100 万个事件
   * [Uptrace](https://uptrace.dev)  - 分布式跟踪工具，帮助开发人员查明故障并找到性能瓶颈. 有免费计划，提供开源项目的免费个人订阅，并且有开源版本.
   * [Microsoft Clarity](https://clarity.microsoft.com/) - Clarity 是一款免费且易于使用的工具，可以捕捉真实的人们如何实际使用您的网站.
   * [Beampipe.io](https://beampipe.io)  - Beampipe 是简单、注重隐私的网络分析. 免费最多 5 个域名和 10,000 每月页面浏览量.
   * [GrowthBook](https://growthbook.io)  - 开源功能标志和 A/B 测试提供程序，具有内置贝叶斯统计分析引擎. 最多 3 位用户免费，无限制的功能标志和实验.
   * [Aptabase](https://aptabase.com)  — 适用于移动和桌面应用程序的开源、隐私友好且简单的分析. 适用于 Swift、Kotlin、React Native、Flutter、Electron 等的 SDK. 每月最多可免费举办 20,000 场活动.


## Visitor Session Recording

   * [Visualime.com](https://www.visualime.com/) — 免费且无限制的会话录音，无流量限制
   * [Reactflow.com](https://www.reactflow.com/) — 每个站点：每天 1,000 页面浏览量、3 个热图、3 个小部件、免费错误跟踪
   * [OpenReplay.com](https://www.openreplay.com)  - 使用开发工具进行开源会话重放以重现错误、实时会话以提供实时支持以及产品分析套件. 每月 1,000 次会话，可访问所有功能并保留 7 天.
   * [LogRocket.com](https://www.logrocket.com) - 每月 1,000 次会话，保留 30 天、错误跟踪、实时模式
   * [FullStory.com](https://www.fullstory.com)  — 每月 1,000 次会话，数据保留 1 个月，拥有 3 个用户席位. 更多信息 [here](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition).
   * [hotjar.com](https://www.hotjar.com/) — 每个站点：1,050 页面浏览量/月，无限热图，数据存储 3 个月，...
   * [inspectlet.com](https://www.inspectlet.com/) — 1 个网站每月免费使用 2,500 次会话
   * [Microsoft Clarity](https://clarity.microsoft.com/) - 会话录制完全免费，“无流量限制”、无项目限制、无采样
   * [mouseflow.com](https://mouseflow.com/) — 1 个网站每月免费 500 次会话
   * [mousestats.com](https://www.mousestats.com/) — 1 个网站每月免费 100 次会话
   * [smartlook.com](https://www.smartlook.com/) — 免费网络和移动应用程序包（1500 个会话/月）、3 个热图、1 个漏斗、1 个月的数据历史记录
   * [usersurge.com](https://www.usersurge.com/) — 个人每月 25 万次会话.
   * [howuku.com](https://howuku.com)  — 跟踪用户交互、参与度和事件. 每月最多 5,000 次访问免费
   * [UXtweak.com](https://www.uxtweak.com/)  — 记录并观察访问者如何使用您的网站或应用程序. 小型项目免费无限时间


## International Mobile Number Verification API and SDK

  * [Cognalys](https://cognalys.com/)  — 通过比使用 SMS 网关更创新且可靠的方法进行免费增值手机号码验证. 每天免费 10 次尝试和 15 次验证
  * [numverify](https://numverify.com/)  — 全球电话号码验证和查找 JSON API. 每月 250 个 API 请求
  * [veriphone](https://veriphone.io/)  — 通过免费、快速、可靠的 JSON API 进行全球电话号码验证. 每月 1000 个请求


## Payment and Billing Integration

  * [Adapty.io](https://adapty.io/)  – 具有开源 SDK 的一站式解决方案，用于将移动应用内订阅集成到 iOS、Android、React Native、Flutter、Unity 或 Web 应用程序. 免费获得每月高达 10,000 美元的收入.
  * [CoinMarketCap](https://coinmarketcap.com/api/)  — 提供加密货币市场数据，包括最新的加密货币和法定货币汇率. 免费套餐每月提供 10K 通话积分.
  * [CurrencyFreaks](https://currencyfreaks.com/)  — 提供当前和历史货币汇率. 免费的开发者计划每月有 1000 个请求.
  * [CoinGecko](https://www.coingecko.com/en/api)  — 提供加密货币市场数据，包括最新的加密货币汇率和历史数据. 免费套餐需要归属.
  * [CurrencyApi](https://currencyapi.net/)  — 实物和加密货币的实时汇率，以 JSON 和 XML 形式提供. 免费套餐每月提供 1,250 个 API 请求.
  * [currencylayer](https://currencylayer.com/) — 为您的企业提供可靠的汇率和货币换算，每月免费 1,000 个 API 请求
  * [currencystack.io](https://currencystack.io/) — 154 种货币的可立即生产的实时汇率.
  * [exchangerate-api.com](https://www.exchangerate-api.com)  - 易于使用的货币转换 JSON API. 免费套餐，无请求限制.
  * [FraudLabsPRO](https://www.fraudlabspro.com)  — 帮助商户防止支付欺诈和退款. 免费微型计划每月可进行 500 次查询.
  * [MailPopin](https://mailpop.in) - 通过上下文信息充分利用您的 Stripe 通知.
  * [Nami ML](https://www.namiml.com/)  - 适用于 iOS 和 Android 上的应用内购买和订阅的完整平台，包括无代码付费专区、CRM 和分析. 免费使用运行 IAP 业务的所有基本功能.
  * [RevenueCat](https://www.revenuecat.com/)  — 用于应用内购买和订阅的托管后端（iOS 和 Android）. 免费提供高达 10,000 美元/月的跟踪收入.
  * [vatlayer](https://vatlayer.com/) — 即时增值税号验证和欧盟增值税税率 API，每月免费 100 个 API 请求
  * [Freecurrencyapi.net](https://freecurrencyapi.net/)  — 免费的货币换算和汇率数据API. 无需 API 密钥即可每小时 10 个请求，免费注册后每月可处理 50,000 个请求.


## Docker Related

  * [canister.io](https://canister.io/) — 20 个供开发人员使用的免费私有存储库，30 个供团队构建和存储 Docker 镜像的免费私有存储库
  * [Container Registry Service](https://container-registry.com/)  - 基于港口的集装箱管理解决方案. 免费套餐为私有存储库提供 1 GB 存储空间.
  * [Docker Hub](https://hub.docker.com) — 一个免费的私有存储库和无限的公共存储库，用于构建和存储 Docker 镜像
  * [Play with Docker](https://labs.play-with-docker.com/) — 一个简单、互动且有趣的 Docker 学习平台.
  * [quay.io](https://quay.io/) — 使用无限的免费公共存储库构建和存储容器映像
  * [Platform9](https://platform9.com/)  - 托管 Kubernetes 平面. 免费计划提供最多 3 个集群和 20 个节点的管理功能. 注意：您必须自行提供集群基础设施.


## Vagrant Related

  * [Vagrant Cloud](https://app.vagrantup.com)  - HashiCorp Vagrant Cloud.  Vagrant 盒子托管.
  * [Vagrantbox.es](https://www.vagrantbox.es/) — 另一种公共盒子索引


## Dev Blogging Sites

  * [BearBlog](https://bearblog.dev/) - 极简主义和 Markdown 支持的博客和网站构建器.
  * [Dev.to](https://dev.to/) - 程序员分享想法并互相帮助成长的地方.
  * [Hashnode](https://hashnode.com/) — 为开发人员提供的无忧博客软件！
  * [Medium](https://medium.com/) — 更明智地了解对您来说重要的事情.
  * [AyeDot](https://ayedot.com/) — 以现代多媒体短格式迷你博客的形式免费与世界分享您的想法、知识和故事.


## Commenting Platforms
  * [Staticman](https://staticman.net/) - Staticman 是一个 Node.js 应用程序，它接收用户生成的内容并使用 Pull 请求将其作为数据文件上传到 GitHub 和/或 GitLab 存储库.
  * [GraphComment](https://graphcomment.com/) - GraphComment 是一个评论平台，可帮助您从网站的受众中建立一个活跃的社区.
  * [Utterances](https://utteranc.es/)  - 基于 GitHub 问题构建的轻量级评论小部件. 使用 GitHub 问题进行博客评论、维基页面等！
  * [Disqus](https://disqus.com/) - Disqus 是一个网络社区平台，被网络上数十万个网站使用.


## Screenshot APIs

  * [ApiFlash](https://apiflash.com)  — 基于 Aws Lambda 和 Chrome 的屏幕截图 API. 处理整页、捕捉时间、视口尺寸……
  * [microlink.io](https://microlink.io/)  – 它将任何网站转化为数据，例如元标签标准化、美容链接预览、抓取功能或屏幕截图即服务. 每天 250 个请求免费.
  * [ScreenshotAPI.net](https://screenshotapi.net/)  - 屏幕截图 API 使用一个简单的 API 调用来生成任何网站的屏幕截图. 按比例构建并托管在 Google Cloud 上. 每月提供 100 张免费屏幕截图.
  * [screenshotlayer.com](https://screenshotlayer.com/)  — 捕获任何网站的高度可定制的快照. 每月免费 100 个快照
  * [screenshotmachine.com](https://www.screenshotmachine.com/) — 每月捕获 100 个快照，png、gif 和 jpg，包括完整长度的捕获，而不仅仅是主页
  * [PhantomJsCloud](https://PhantomJsCloud.com)  — 浏览器自动化和页面渲染. 免费套餐每天最多提供 500 页. 自 2017 年起免费套餐.
  * [Webshrinker.com](https://webshrinker.com)  — Web Shrinker 提供网站截图和域名智能 API 服务. 每月免费 100 个请求.
  * [Httpic.com](https://httpic.com)  — 将任何网站转换为 jpg、png 或 pdf. 捕获全页屏幕截图、调整视口、注入自定义代码. 免费套餐为 150 张图像/月.
  * [Screenshots](https://screenshotson.click)  — 您的屏幕截图 API. 具有高度可定制的捕捉选项. 每月免费 100 张屏幕截图.


## Flutter Related and Building IOS Apps without Mac

  * [FlutLab](https://flutlab.io/)  - FlutLab 是一个现代 Flutter 在线 IDE，也是创建、调试和构建跨平台项目的最佳场所. 使用 Flutter 构建 iOS（不含 Mac）和 Android 应用程序.
  * [CodeMagic](https://codemagic.io/)  - Codemagic 是一个针对移动应用程序的完全托管和管理的 CI/CD. 您可以使用基于 GUI 的 CI/CD 工具来构建、测试和部署. 免费套餐提供每月 500 分钟免费时间，以及配备 2.3Ghz 和 8GB RAM 的 Mac Mini 实例.
  * [FlutterFlow](https://flutterflow.io/) - FlutterFlow 是一个基于浏览器的拖放界面，用于使用 flutter 构建移动应用程序.


## Browser based hardware emulation written in Javascript

  * [JsLinux](https://bellard.org/jslinux) — 一个非常快的 x86 虚拟机，能够运行 Linux 和 Windows 2k.
  * [Jor1k](https://s-macke.github.io/jor1k/demos/main.html) — 能够在网络支持下运行 Linux 的 OpenRISC 虚拟机.
  * [v86](https://copy.sh/v86) — 能够直接在浏览器中运行 Linux 和其他操作系统的 x86 虚拟机.


## Privacy Management
  * [Bearer](https://www.bearer.sh/)  - 通过审计和连续工作流程帮助实施隐私设计，以便组织遵守 GDPR 和其他法规. 免费套餐仅限于较小的团队和 SaaS 版本.
  * [Osano](https://www.osano.com/)  - 同意管理和合规平台，涵盖从 GDPR 表示到 cookie 横幅的所有内容. 免费套餐提供基本功能.
  * [Iubenda](https://www.iubenda.com/) - Privacy and cookie policies along with consent management. Free tier offers limited privacy and cookie policy as well as cookie banners.
  * [Cookiefirst](https://cookiefirst.com/)  - Cookie 横幅、审核和多语言同意管理解决方案. 免费套餐提供一次性扫描和单个横幅.
  * [Ketch](https://www.ketch.com/)  - 同意管理和隐私框架工具. 免费套餐提供大多数功能，但访问者数量有限.


## Miscellaneous

  * [BinShare.net](https://binshare.net)  - 创建和共享代码或二进制文件. 可作为美丽的图像（例如 Twitter / Facebook 帖子）或作为链接（例如聊天或论坛）进行共享.
  * [Blynk](https://blynk.io)  — 具有 API 的 SaaS，用于控制、构建和评估 IoT 设备. 包含 5 台设备的免费开发者计划、免费云和数据存储. 还提供移动应用程序.
  * [Bricks Note Calculator](https://free.getbricks.app/) - 带有强大内置多行计算器的笔记应用程序 (PWA).
  * [Carbon.now.sh](https://carbon.now.sh)  - 以类似屏幕截图的美观图像格式创建和共享代码片段. 通常用于在 Twitter 或博客文章上美观地分享/炫耀代码片段.
  * [Code Time](https://www.software.com/code-time) - VS Code、Atom、IntelliJ、Sublime Text 等中时间跟踪和编码指标的扩展.
  * [Codepng](https://www.codepng.app) - 从您的源代码创建精彩的快照，您可以在社交媒体上分享.
  * [CodeToImage](https://codetoimage.com/) - 创建代码或文本的屏幕截图以在社交媒体上分享.
  * [ConfigCat](https://configcat.com)  - ConfigCat 是一项以开发人员为中心的功能标记服务，具有无限的团队规模、出色的支持和合理的价格标签. 每月免费计划最多 10 个标志、2 个环境、1 个产品和 500 万个请求.
  * [Cronhooks](https://cronhooks.io/)  - 按时安排或定期进行网络挂钩. 免费计划允许 5 个临时时间表.
  * [Cronit](https://cronit.app)  - 在线定时任务服务. 免费计划包括每月 100 个作业执行
  * [datelist.io](https://datelist.io)  - 在线预订/预约安排系统. 每月最多免费 5 次预订，包括 1 份日历
  * [docsapp.io](https://www.docsapp.io/) — 发布文档的最简单方法，免费开源
  * [Domain Forward](https://domain-forward.com/)  - 一种转发任何 URL 或域的简单工具. 每月免费最多 5 个域名和 20 万个请求.
  * [Elementor](https://elementor.com)  — WordPress 网站构建器. 免费计划包含 40 多个基本小部件.
  * [Form2Channel](https://form2channel.com)  — 在您的网站上放置静态 html 表单，并直接接收提交到 Google Sheets、电子邮件、Slack、Telegram 或 Http 的提交内容. 无需编码.
  * [Format Express](https://www.format-express.dev) - JSON / XML / SQL 的即时在线格式化程序.
  * [FOSSA](https://fossa.com/) - 针对第三方代码、许可证合规性和漏洞的可扩展的端到端管理.
  * [fullcontact.com](https://www.fullcontact.com/developer/pricing/)  — 通过将社交资料添加到您的应用程序中，帮助您的用户更多地了解他们的联系人. 每月 500 次免费 Person API 匹配
  * [Hook Relay](https://www.hookrelay.dev/)  - 为您的应用程序添加 Webhook 支持，无需任何麻烦：为您完成排队、退避重试和日志记录. 免费计划每天有 100 次交付、14 天保留和 3 个挂钩端点.
  * [http2.pro](https://http2.pro) — HTTP/2 协议就绪测试和客户端 HTTP/2 支持检测 API.
  * [kandi](https://kandi.openweaver.com/) — 快速启动应用程序开发：通过代码片段和开源库重用，更快地构建自定义功能、用例和完整应用程序.
  * [Base64 decoder/encoder](https://devpal.co/base64-decode/) — 用于解码和编码数据的在线免费工具.
  * [newreleases.io](https://newreleases.io/) - 接收来自 GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM、Node.js Yarn、Ruby Gems、PHP Packagist、.NET NuGet 的新版本的电子邮件、Slack、Telegram、Discord 和自定义 Webhooks 通知Rust Cargo 和 Docker Hub.
  * [OnlineExifViewer](https://onlineexifviewer.com/) — 立即在线查看照片的 EXIF 数据，包括 GPS 位置和元数据.
  * [PDFMonkey](https://www.pdfmonkey.io/)  — 在仪表板中管理 PDF 模板，使用动态数据调用 API，下载 PDF. 每月提供 300 个免费文档.
  * [Pika Code Screenshots](https://pika.style/templates/code-image) — 使用扩展从代码片段和 VSCode 创建漂亮的、可定制的屏幕截图.
  * [QuickType.io](https://quicktype.io/)  - 从 JSON、模式和 GraphQL 快速自动生成模型/类/类型/接口和序列化器，以便使用任何编程语言快速、安全地处理数据. 将 JSON 转换为任何语言的华丽、类型安全的代码.
  * [RandomKeygen](https://randomkeygen.com/) - 免费的移动设备友好工具提供各种随机生成的密钥和密码，您可以使用它们来保护任何应用程序、服务或设备的安全.
  * [ray.so](https://ray.so/) - 创建代码片段的精美图像.
  * [readme.com](https://readme.com/) — 精美的文档变得简单，免费开源.
  * [redirection.io](https://redirection.io/) — 用于管理企业、营销和 SEO 的 HTTP 重定向的 SaaS 工具.
  * [redirect.pizza](https://redirect.pizza/)  - 通过 HTTPS 支持轻松管理重定向. 免费计划包括 10 个来源和每月 100.000 次点击.
  * [ReqBin](https://www.reqbin.com/)  — 在线发布 HTTP 请求. 流行的请求方法包括 GET、POST、PUT、DELETE 和 HEAD. 支持标头和令牌身份验证. 包括用于保存您的请求的基本登录系统.
  * [Smartcar API](https://smartcar.com) - 用于汽车定位、获取油箱、电池电量、里程表、解锁/锁门等的 API.
  * [snappify](https://snappify.com)  - 使开发人员能够创建令人惊叹的视觉效果. 从漂亮的代码片段到完善的技术演示. 免费计划包括一次最多 3 个快照、无限下载和每月 5 个人工智能驱动的代码解释.
  * [Sunrise and Sunset](https://sunrisesunset.io/api/) - 获取给定经度和纬度的日出和日落时间.
  * [superfeedr.com](https://superfeedr.com/)  — 符合 PubSubHubbub 标准的实时提要、导出、分析. 免费，定制较少
  * [SurveyMonkey.com](https://www.surveymonkey.com)  — 创建在线调查. 在线分析结果. 免费计划每次调查仅允许 10 个问题和 100 个答复.
  * [Tiledesk](https://tiledesk.com)  - 创建聊天机器人和对话应用程序. 为他们带来全渠道：从您的网站（实时聊天小部件）到 WhatsApp. 具有无限聊天机器人的免费计划.
  * [Versionfeeds](https://versionfeeds.com)  — 用于发布您喜爱的软件的自定义 RSS 源. 将您的编程语言、库或喜爱的工具的最新版本集中在一个源中.  （前3次免费）
  * [videoinu](https://videoinu.com) — 在线创建和编辑屏幕录像和其他视频.


## Remote Desktop Tools

  * [Getscreen.me](https://getscreen.me) — 2台设备免费，会话次数和持续时间没有限制
  * [Apache Guacamole™](https://guacamole.apache.org/) — 开源无客户端远程桌面网关
  * [RemSupp](https://remsupp.com) — 按需支持和永久访问设备（免费每天 2 次会议）
  * [RustDesk](https://rustdesk.com/) - 适合所有人的开源虚拟/远程桌面基础设施！


## Game Development

  * [itch.io](https://itch.io/game-assets) — 免费/付费资源，如精灵、图块集、角色包……
  * [Gamefresco.com](https://gamefresco.com/) — Discover, collect and share free game assets from game artists everywhere.
  * [GameDevMarket](https://gamedevmarket.net) — 免费/付费资源，如 2D、3D、音频、GUI.
  * [OpenGameArt](https://opengameart.org) — 开源游戏资产，如音乐、声音、精灵、GIF...
  * [CraftPix](https://craftpix.net) — 免费/付费资源，如 2D、3D、音频、GUI、背景、图标、图块集、游戏套件.
  * [Game Icons](https://game-icons.net/) - 根据 CC-BY 许可提供免费的可样式 SVG/PNG 图标.
  * [LoSpec](https://lospec.com/) — 用于创建像素艺术和其他限制性数字艺术的在线工具，有大量教程/托盘列表可供您的游戏选择
  * [ArtStation](https://www.artstation.com/) - 免费/付费 2D、3D 资源和音频、图标、图块集、游戏套件等的 MarketPlace，此外，它还可用于展示您的艺术作品集.
  * [Rive](https://rive.app/community/) - 社区资产以及使用其免费计划创建您自己的游戏资产.
  * [Poly Pizza](https://poly.pizza/) - 免费低多边形 3D 资源
  * [3Dassets.one](https://3dassets.one/) - 超过 8,000 个免费/付费 3D 模型以及用于制作纹理的 PBR 材料.
  * [3DModelsCC0](https://www.3dmodelscc0.com/) - 用于游戏开发的公共领域 3D 模型库.
  * [Kenney](https://www.kenney.nl/assets/) - 免费（CC0 1.0 通用许可）2D、3D、音频和 UI 游戏资源.
  * [Poliigon](https://www.poliigon.com/)  - 免费和付费纹理（具有可变分辨率）、模型、HDRI 和画笔. 提供免费插件以导出到 Blender 等软件.


## Other Free Resources

  * [ElevateAI](https://www.elevateai.com) - 每月免费获得最多 200 小时的音频转录.
  * [get.localhost.direct](https://get.localhost.direct) — 更好的“*.localhost.direct”通配符公共 CA 签名 SSL 证书，用于具有子域支持的本地主机开发
  * [Framacloud](https://degooglisons-internet.org/en/list/) — 法国非营利组织提供的免费/Libre 开源软件和 SaaS 列表 [Framasoft](https://framasoft.org/en/).
  * [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) — 为开发者提供的免费开源软件中心.
  * [GitHub Education](https://education.github.com/pack)  — 为学生收集免费服务. 需要注册.
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program)  — 获取为 Microsoft 365 平台构建解决方案所需的免费沙箱、工具和其他资源. 订阅期限为 90 天 [Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5)  （Windows 除外）可更新. 如果您积极参与开发（使用遥测数据和算法进行测量），则会更新它.
  * [RedHat for Developers](https://developers.redhat.com)  — 专供开发人员免费使用红帽产品，包括 RHEL、OpenShift、CodeReady 等. 仅限个人计划. 还提供免费电子书供参考.
  * [smsreceivefree.com](https://smsreceivefree.com/) — 提供免费的临时和一次性电话号码.
  * [simplebackups.io](https://simplebackups.io/)  — 直接存储到云存储提供商（AWS、DigitalOcean、Backblaze...）的服务器和数据库（MySQL、PostgreSQL、MongoDB）的备份自动化服务. 提供 1 次备份的免费计划.
  * [SnapShooter](https://snapshooter.com/)  — 适用于 DigitalOcean、AWS、LightSail、Hetzner 和 Exoscale 的备份解决方案，支持将数据库、文件系统和应用程序直接备份到基于 s3 的存储. 提供免费计划，其中包含一项资源的每日备份.
  * [Themeselection](https://themeselection.com/) — 精选高品质、现代设计、专业且易于使用的免费管理仪表板模板，
HTML 主题和 UI 套件可帮助您更快地创建应用程序！
  * [Web.Dev](https://web.dev/measure/) — 这是一个免费工具，可让您查看网站的性能并改进 SEO，以在搜索引擎中获得更高的排名.
  * [SmallDev.tools](https://smalldev.tools/)  — 为开发人员提供的免费工具，允许您编码/解码各种格式、缩小 HTML/CSS/Javascript、美化、生成假/测试真实的 JSON/CSV 和多种其他格式的数据集以及更多功能. 具有令人愉快的界面.
  * [UseCSV by Layercode](https://layercode.com/usecsv) — Add CSV and Excel import to your web app in minutes. Give your users an enjoyable and robust data import experience. Get Started for Free without any credit card details, and start integrating UseCSV today. You can create unlimited Importers and upload files up to 100Mb.
  * [Buttons Generator](https://markodenic.com/tools/buttons-generator/) — 您可以在项目中使用 100 多个按钮.
  * [WrapPixel](https://www.wrappixel.com/) — 下载使用 Angular、React、VueJs、NextJs 和 NuxtJs 创建的高质量免费和高级管理仪表板模板！
  * [Utils.fun](https://utils.fun/en) — 所有基于浏览器算力的离线日常和开发工具，包括水印生成、录屏、编解码、加解密、代码格式化等，完全免费，不上传任何数据到云端进行处理.
  * [Free Code Tools](https://freecodetools.org/)  — 100% 免费的有效代码工具.  Markdown 编辑器、代码压缩器/美化器、二维码生成器、开放图谱生成器、Twitter 卡生成器等.
  * [regex101](https://regex101.com/)  — 免费此网站允许您测试和调试正则表达式 (regex). 它提供了正则表达式编辑器和测试器，以及用于学习正则表达式的有用文档和资源.
  * [Kody Tools](https://www.kodytools.com/dev-tools) — 100 多个开发工具，包括格式化程序、压缩器和转换器.
  * [AdminMart](https://adminmart.com/) — 使用 Angular、Bootstrap、React、VueJs、NextJs 和 NuxtJs 创建的高品质免费和高级管理仪表板和网站模板！
  * [Glob tester](https://globster.xyz/)  — 一个允许您设计和测试全局模式的网站. 它还提供了学习全局模式的资源.
  * [OpenUtils](https://openutils.org/) - 有多种免费工具可供开发人员使用，例如 HTML/CSS/JavaScript 格式化程序、压缩器、转换器、编码器/解码器等等.

