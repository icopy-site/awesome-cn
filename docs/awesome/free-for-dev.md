<div class="github-widget" data-repo="ripienaar/free-for-dev"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## free-for.dev

开发人员和开源作者现在拥有大量提供免费套餐的服务，但很难找到所有这些服务来做出明智的决定.

这是一个软件（SaaS、PaaS、IaaS 等）和其他为开发人员提供免费层的产品列表.

此特定列表的范围仅限于基础架构开发人员（系统管理员、DevOps 从业人员等）可能会发现有用的内容. 我们喜欢那里的所有免费服务，但最好将其放在主题上. 有时它有点灰线，所以这有点自以为是； 如果我不接受你的贡献，请不要生气.

此列表是 900 多人完成的拉取请求、评论、想法和工作的结果. 您也可以通过发送来提供帮助 [Pull Requests](https://github.com/ripienaar/free-for-dev) 添加更多服务或删除其产品已更改或已停用的服务.

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

 *注意：* 此列表仅适用于即服务产品，不适用于自托管软件. 要使服务符合条件，它必须提供免费套餐，而不仅仅是免费试用. 如果免费套餐是有时间限制的，则必须至少持续一年. 我们还从安全角度考虑免费层，因此 SSO 很好，但我不会接受将 TLS 限制为仅付费层的服务.

目录
=================


## Major Cloud Providers

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 每天 28 个前端实例小时，每天 9 个后端实例小时
    * Cloud Firestore - 1GB 存储空间，每天 50,000 次读取，20,000 次写入，20,000 次删除
    * Compute Engine - 1 non-preemptible e2-micro, 30GB HDD, 5GB snapshot storage (restricted to certain regions), 1 GB network egress from North America to all region destinations (excluding China and Australia) per month
    * 云存储 - 5GB、1GB 网络出口
     * Cloud Shell - 基于 Web 的 Linux shell/基本 IDE，具有 5GB 的持久存储. 每周 60 小时限制
    * Cloud Pub/Sub - 每月 10GB 的消息
    * Cloud Functions - 每月 200 万次调用（包括后台调用和 HTTP 调用）
    * Cloud Run - 每月 200 万个请求，360,000 GB 秒的内存，180,000 个 vCPU 秒的计算时间，每月来自北美的 1 GB 网络出口
     * Google Kubernetes Engine - 一个区域集群无需集群管理费. 每个用户节点按标准 Compute Engine 价格收费
    * BigQuery - 每月 1 TB 查询，每月 10 GB 存储
    * Cloud Build - 每天 120 分钟的构建时间
    * 云源存储库 - 最多 5 个用户，50 GB 存储空间，50 GB 出口
    * 完整的详细列表 - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * Amazon DynamoDB - 25GB NoSQL 数据库
    * Amazon Lambda - 每月 100 万个请求
    * Amazon SNS - 每月发布 100 万次
    * Amazon Cloudwatch - 10 个自定义指标和 10 个警报
    * Amazon Glacier - 10GB 长期对象存储
    * Amazon SQS - 100 万个消息队列请求
    * Amazon CodeBuild - 每月 100 分钟的构建时间
    * 亚马逊代码提交 - 每月 5 个活跃用户
    * Amazon Code Pipeline - 每月 1 个活动管道
    * 完整的详细列表 - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1 个 B1S Linux 虚拟机，1 个 B1S Windows 虚拟机
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 个网络、移动或 API 应用程序
    * [Functions](https://azure.microsoft.com/services/functions/) - 每月 100 万个请求
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - 启用快速、简单和精益的开发测试环境
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 个对象
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 50,000 每月存储用户
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 个活跃用户，无限的私人 Git 存储库
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10 个免费的并行作业，时间不受限制，适用于 Linux、macOS 和 Windows 的开源
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 每天 8,000 条消息
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1 个免费公共负载均衡 IP (VIP)
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 1 million push notifications
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 每月 5GB 出站流量
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 5GB 存储和 400 RU 的预配置吞吐量
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) — 使用免费 SSL、身份验证/授权和自定义域构建、部署和托管静态应用程序和无服务器功能
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS 文件或 Blob 存储
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - 人工智能/机器学习 API（计算机视觉、翻译器、人脸检测、机器人...）具有免费层，包括有限的交易
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - 基于人工智能的搜索和索引服务，免费提供 10,000 个文档
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - 托管Kubernetes服务，免费集群管理
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 10 万次操作/月
    * 完整、详细的清单 - [https://azure.microsoft.com/free/](https://azure.microsoft.com/free/)

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * 计算 - 2 个基于 x64，每个具有 1 GB RAM、4 个基于 Arm 的 Ampere A1 内核和 24 GB 内存，可用作一个 VM 或最多 4 个 VM
    * 块卷 - 4 个卷，总共 200 GB（用于计算）
    * 对象存储 - 10 GB
    * 负载均衡器 - 1 个 10 Mbps 的实例
    * 数据库 - 2 个 DB，每个 20 GB
    * 监控 - 5 亿个摄取数据点，10 亿个检索数据点
    * 带宽 - 每月 10 TB 出口，基于 x64 的 VM 速度限制为 50 Mbps，500 Mbps * 基于 ARM 的 VM 的核心数
    * 公共 IP - 2 个用于 VM 的 IPv4，1 个用于负载均衡器的 IPv4
    * 通知 - 每月 100 万个递送选项，每月发送 1000 封电子邮件
    * 完整的详细列表 - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloud Functions - 每月执行 500 万次
    * 对象存储 - 每月 25GB
    * Cloudant 数据库 - 1 GB 的数据存储
    * Db2 数据库 - 100MB 的数据存储
    * API Connect - 每月 50,000 次 API 调用
    * 可用性监控 - 每月 300 万个数据点
    * 日志分析 - 500MB 的每日日志
    * 完整的详细列表 - https://www.ibm.com/cloud/free/


## Cloud management solutions
  * [Brainboard](https://www.brainboard.co) - 从端到端可视化构建和管理云基础架构的协作解决方案.
  * [terraform.io](https://www.terraform.io/)  — Terraform 云. 为最多 5 个用户的团队提供免费的远程状态管理和团队协作.


## Source Code Repos

  * [bitbucket.org](https://bitbucket.org/) — 使用 CI/CD 管道为最多 5 个用户提供无限的公共和私有 Git 存储库
  * [chiselapp.com](http://chiselapp.com/) — 无限制的公共和私人 Fossil 存储库
  * [codebasehq.com](https://www.codebasehq.com/) — 一个具有 100 MB 空间和 2 个用户的免费项目
  * [codeberg.org](https://codeberg.org/)  - 用于免费和开源项目的无限公共和私人 Git 存储库. 静态网站托管 [Codeberg Pages](https://codeberg.page/).
  * [gitea.com](https://www.gitea.com/) - 无限的公共和私人 Git 存储库
  * [GitGud](https://gitgud.io)  — 无限的私有和公共存储库. 永远免费. 由 GitLab 和 Sapphire 提供支持. 未提供 CI/CD.
  * [github.com](https://github.com/)  — 无限的公共存储库和无限的私有存储库（与无限的合作者）. 除此之外，提供的其他一些免费服务（还有更多，但我们在这里列出了主要服务）：
       - [CI/CD](https://github.com/features/actions)（公共回购免费，私人回购免费 2000 分钟/月）
       - [Static Website Hosting](https://pages.github.com) （公共回购免费）
       - [Package Hosting & Container Registry](https://github.com/features/packages) （公共存储库免费，500 MB 存储空间和 1GB 带宽（CI/CD 之外的私有存储库免费））
       - 项目管理和问题跟踪.
  * [gitlab.com](https://about.gitlab.com/)  — 无限的公共和私有 Git 存储库，具有无限的合作者. 还提供以下功能：
       - [CI/CD](https://about.gitlab.com/product/continuous-integration) （公共回购免费，私人回购 400 分钟/月）
       - 静态网站 [GitLab Pages](https://about.gitlab.com/product/pages).
       - 每个存储库限制为 10 GB 的 Container Registry.
       - 项目管理和问题跟踪.
  * [heptapod.net](https://foss.heptapod.net/) — Heptapod 是 GitLab 社区版的一个友好分支，为 Mercurial 提供支持
  * [ionicframework.com](https://ionicframework.com/appflow) - 使用 Ionic 开发应用程序的回购和工具，您也有一个离子回购
  * [NotABug](https://notabug.org) — NotABug.org 是一个免费软件代码协作平台，用于免费许可的项目，基于 Git
  * [Pagure.io](https://pagure.io) — Pagure.io 是一个免费的开源软件代码协作平台，适用于 FOSS 许可的项目，基于 Git
  * [perforce.com](https://www.perforce.com/products/helix-teamhub) — 免费的 1GB Cloud 和 Git、Mercurial 或 SVN 存储库.
  * [pijul.com](https://pijul.com/)  - 无限制的免费和开源分布式版本控制系统. 它的显着特点是基于完善的补丁理论，这使得它易于学习和使用，并且真正分布式. 解决了git/hg/svn/darcs的很多问题.
  * [plasticscm.com](https://plasticscm.com/) — 对个人、OSS 和非营利组织免费
  * [projectlocker.com](https://projectlocker.com) — 一个 50 MB 空间的免费私人项目（Git 和 Subversion）
  * [RocketGit](https://rocketgit.com)  — 基于 Git 的存储库托管. 无限的公共和私人存储库.
  * [savannah.gnu.org](https://savannah.gnu.org/) - 用作免费软件项目（用于 GNU 项目）的协作软件开发管理系统
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - 作为自由软件项目（非 GNU 项目）的协作软件开发管理系统


## APIs, Data and ML

  * [IP.City](https://ip.city) — 每天 100 个免费 IP 地理定位请求
  * [Abstract API](https://www.abstractapi.com) — 适用于各种用例的 API 套件，包括 IP 地理定位、性别检测甚至电子邮件验证.
  * [algorithmia.com](https://algorithmia.com/)  — 免费托管算法. 包括运行算法的免费每月津贴. 现在有了 CLI 支持.
  * [Apify](https://www.apify.com/)  — 网页抓取和自动化平台，可为任何网站创建 API 并提取数据. 现成的刮板、集成代理和定制解决方案. 每月包含 5 美元平台积分的免费计划.
  * [API Mocha](https://apimocha.com)  - 用于测试和原型设计的完全免费的在线 API 模拟. 每天最多发出 500 个请求，完全可定制的 API 响应，将模拟规则下载为 Postman 集合.
  * [APITemplate.io](https://apitemplate.io)  - 使用简单的 API 或 Zapier &amp; Airtable 等自动化工具自动生成图像和 PDF 文档. 不需要 CSS/HTML. 免费计划带有 50 张图片/月和 3 个模板.
  * [Atlas toolkit](https://atlastk.org/)  - 用于开发可即时访问的单页 Web 应用程序的轻量级库. 适用于 Java、Node.js、Perl、Python 和 Ruby.
  * [Beeceptor](https://beeceptor.com)  - 在几秒钟内模拟一个休息 API，假 API 响应等等. 每天免费 50 个请求，公共仪表板，开放端点（任何拥有仪表板链接的人都可以查看请求和响应）.
  * [bigml.com](https://bigml.com/)  — 托管机器学习算法. 无限的免费开发任务，限制为 16 MB 数据/任务.
  * [Calendarific](https://calendarific.com)  - 面向 200 多个国家/地区的企业级公共假期 API 服务. 免费计划包括每月 1000 次通话.
  * [Clarifai](https://www.clarifai.com)  — 用于自定义人脸识别和检测的图像 API. 能够训练AI模型. 免费计划每月有 5000 次通话.
  * [Cloudmersive](https://cloudmersive.com/) — 实用 API 平台，可完全访问扩展 API 库，包括文档转换、病毒扫描等，每月调用 800 次.
  * [Colaboratory](https://colab.research.google.com) — 使用 Nvidia Tesla K80 GPU 的免费基于 Web 的 Python 笔记本环境.
  * [Collect2](https://collect2.com)  — 创建 API 端点以测试、自动化和连接 Webhook. 免费计划允许使用两个数据集、2000 条记录、1 个转发器和 1 个警报.
  * [Conversion Tools](https://conversiontools.io/)  - 用于文档、图像、视频、音频、电子书的在线文件转换器.  REST API 可用.  Node.js、PHP、Python 的库. 支持文件高达 50 GB（付费计划）. 免费套餐受文件大小和每天转换次数的限制.
  * [CraftMyPDF](https://craftmypdf.com)  - 使用拖放式编辑器和简单的 API 从可重复使用的模板中自动生成 PDF 文档. 免费计划带有 100 个 PDF/月和 3 个模板.
  * [CurlHub](https://curlhub.io)  — 用于检查和调试 API 调用的代理服务. 免费计划包括每月 10,000 个请求.
  * [CurrencyScoop](https://currencyscoop.com)  - 金融科技应用的实时货币数据 API. 免费计划包括每月 5000 次通话.
  * [Datapane](https://datapane.com) - 用于在 Python 中构建交互式报告并将 Python 脚本和 Jupyter Notebooks 部署为自助服务工具的​​ API.
  * [DB Designer](https://www.dbdesigner.net/) — 基于云的数据库架构设计和建模工具，具有 2 个数据库模型和每个模型 10 个表的免费入门计划.
  * [DeepAR](https://developer.deepar.ai)  — 任何平台的增强现实面部过滤器，只需一个 SDK. 免费计划提供多达 10 个每月活跃用户 (MAU) 并跟踪多达 4 张面孔
  * [Deepnote](https://deepnote.com)  - 一种新型的数据科学笔记本.  Jupyter 兼容实时协作并在云端运行. 免费套餐包括无限制的个人项目、最多 750 小时的标准硬件和最多 3 名编辑的团队.
  * [Diggernaut](https://www.diggernaut.com/)  — 基于云的网络抓取和数据提取平台，用于将任何网站转换为数据集或像使用 API 一样使用它. 免费计划包括每月 5K 的页面请求.
  * [Disease.sh](https://disease.sh/) — 一个免费的 API，为构建 Covid-19 相关的有用应用程序提供准确的数据.
  * [dominodatalab.com](https://www.dominodatalab.com) — 支持 Python、R、Spark、Hadoop、MATLAB 等的数据科学.
  * [dreamfactory.com](https://dreamfactory.com/)  — 用于移动、Web 和 IoT 应用程序的开源 REST API 后端. 连接任何 SQL/NoSQL 数据库、文件存储系统或外部服务，它会立即创建一个全面的 REST API 平台，其中包含实时文档、用户管理、...
  * [DynaPictures](https://dynapictures.com)  - 设计自动化工具，可让您通过 REST API 动态生成图像. 即时更改颜色、文本、徽标和图像. 免费计划包括每月 30 张生成的图像和 3 个图像模板.
  * [Efemarai](https://efemarai.com)  - ML 模型和数据的测试和调试平台. 可视化任何计算图. 每月为开发人员提供 30 次免费调试会话.
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 免费的基于 Web 的 HTTP 客户端发送 HTTP 请求.
  * [Export SDK](https://exportsdk.com)  - 带有拖放模板编辑器的 PDF 生成器 API，还提供 SDK 和无代码集成. 免费计划包含每月 250 页、无限用户和三个模板.
  * [FraudLabs Pro](https://www.fraudlabspro.com)  — 筛选信用卡支付欺诈的订单交易. 此 REST API 将根据订单的输入参数检测所有可能的欺诈特征. 免费微计划每月有 500 笔交易.
  * [FreeGeoIP.app](https://freegeoip.app/)  - 完全免费的地理 IP 信息（JSON、CSV、XML）. 无需注册，每小时 15000 次查询速率限制.
  * [GeoDataSource](https://www.geodatasource.com)  — 使用经纬度坐标查找城市名称的位置搜索服务. 每月最多 500 次免费 API 查询.
  * [Glitterly](https://glitterly.app/)  - 从基本模板以编程方式生成动态图像.  Restful API 和 nocode 集成. 免费套餐每月提供 50 张图片和 5 个模板.
  * [Hookbin](https://hookbin.com/)  - 创建唯一的（公共或私有）端点来收集、解析和检查 HTTP 请求. 检查标题、正文、查询字符串、cookie、上传的文件等.对于测试/检查 webhook 很有用. 类似于 RequestBin 和 Webhook.site.
  * [Hoppscotch](https://hoppscotch.io) - 免费、快速且美观的 API 请求构建器.
  * [Hybiscus](https://hybiscus.dev/)  - 使用简单的声明式 API 构建 pdf 报告. 免费套餐包括每月最多 100 个单页报告，能够自定义调色板和字体.
  * [Invantive Cloud](https://cloud.invantive.com/)  — 使用 Invantive SQL 或 OData4（通常为 Power BI 或 Power Query）访问 70 多个（云）平台，例如 Exact Online、Twinfield、ActiveCampaign 或 Visma. 包括数据复制和交换. 开发人员和实施顾问的免费计划. 对于有数据量限制的特定平台免费.
  * [ipaddress.sh](https://ipaddress.sh) — 获取不同公共 IP 地址的简单服务 [formats](https://about.ipaddress.sh/).
  * [Iploka](https://iploka.com/) — IP 到地理定位 API - 每月限制为 10k 请求的开发人员的永久免费计划.
  * [IP Geolocation](https://ipgeolocation.io/) — IP 地理定位 API - 每月 30k 请求（1k/天）限制的开发人员永久免费计划.
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) — 抽象的 IP 地理定位 API - 广泛的免费计划，每月允许 200,000 个请求.
  * [IP2Location](https://www.ip2location.com)  — 免费增值 IP 地理定位服务.  LITE 数据库可免费下载. 在服务器中导入数据库并进行本地查询以确定城市、坐标和ISP信息.
  * [ipapi](https://ipapi.co/)  - Kloudend, Inc 的 IP 地址定位 API - 一个可靠的地理定位 API，建立在 AWS 上，受到财富 500 强的信任.免费套餐提供 30k 次/月（1k/天）的查找，无需注册. 联系我们获取更高限额的试用计划.
  * [IPinfo](https://ipinfo.io/)  — 快速、准确且免费（最多 10 万/月）IP 地址数据 API. 提供包含地理位置、公司、运营商、IP 范围、域、滥用联系人等详细信息的 API. 所有付费 API 都可以免费试用.
  * [IPList](https://www.iplist.cc)  — 查找有关任何 IP 地址的详细信息，例如地理 IP 信息、tor 地址、主机名和 ASN 详细信息. 个人和企业用户免费.
  * [BigDataCloud](https://www.bigdatacloud.com/) - 为现代网络提供快速、准确和免费（无限制或高达 10K-50K/月）的 API，如 IP 地理定位、反向地理编码、网络洞察、电子邮件和电话验证、客户信息等.
  * [IPTrace](https://iptrace.io) — 非常简单的 API，可为您的企业提供可靠且有用的 IP 地理定位数据.
  * [JSON IP](https://getjsonip.com)  — 返回请求的客户端的公共 IP 地址. 免费套餐无需注册. 可以使用客户端 JS 直接从浏览器请求使用 CORS 数据. 用于监控客户端和服务器 IP 变化的服务. 无限请求.
  * [konghq.com/](https://konghq.com/)  — API 市场以及用于私有和公共 API 的强大工具. 在免费层中，某些功能受到限制，例如监控、警报和支持.
  * [Kreya](https://kreya.app)  — 免费的 gRPC GUI 客户端来调用和测试 gRPC API. 可以通过服务器反射导入 gRPC API.
  * [KSoft.Si](https://api.ksoft.si/) — 主要针对不和谐机器人的免费歌词 api.还提供了广泛的图像和用户数据库
  * [Lightly](https://www.lightly.ai/)  — 通过使用正确的数据改进您的机器学习模型. 免费使用多达 1000 个样本的数据集.
  * [MailboxValidator](https://www.mailboxvalidator.com)  — 使用真实邮件服务器连接来确认有效电子邮件的电子邮件验证服务. 免费 API 计划每月有 300 次验证.
  * [microlink.io](https://microlink.io/) – It turns any website into data such as metatags normalization, beauty link previews, scraping capabilities or screenshots as a service. 100 reqs/day every day free.
  * [monkeylearn.com](https://monkeylearn.com/) — 使用机器学习进行文本分析，每月免费 300 次查询.
  * [MockAPI](https://www.mockapi.io/)  — MockAPI 是一个简单的工具，可让您轻松地模拟 API、生成自定义数据并使用 RESTful 接口对其执行操作.  MockAPI 旨在用作原型设计/测试/学习工具.  1 个项目/每个项目 50 个资源免费.
  * [Mocki](https://mocki.io)  - 一种工具，可让您创建同步到 GitHub 存储库的模拟 GraphQL 和 REST API. 简单的 REST API 无需注册即可免费创建和使用.
  * [Mocko.dev](https://mocko.dev/)  — 代理您的 API，选择要在云中模拟的端点并免费检查流量. 加快您的开发和集成测试.
  * [Mocky](https://designer.mocky.io/)  - 一个简单的 Web 应用程序，用于为模拟 HTTP 请求生成自定义 HTTP 响应. 也可作为 [open source](https://github.com/julien-lafont/Mocky).
  * [reqres.in](https://reqres.in) - 准备好响应您的 AJAX 请求的免费托管 REST-API.
  * [microenv.com](https://microenv.com) — 为开发人员创建虚假的 REST API，可以在 docker 容器中生成代码和应用程​​序.
  * [neptune.ai](https://neptune.ai/)  - 记录、存储、显示、组织、比较和查询所有 MLOps 元数据. 个人免费：1 名成员，100 GB 元数据存储，200 小时监控/月
  * [News API](https://newsapi.org)  — 用代码在网络上搜索新闻，得到 JSON 结果. 开发人员每月可免费获得 3,000 次查询.
  * [OCR.Space](https://ocr.space/)  — 一个 OCR API，它解析图像和 pdf 文件，以 JSON 格式返回文本结果. 每月 25,000 次免费请求.
  * [Duply.co](https://duply.co)  — 从 API 和 URL 创建动态图像，设计模板一次并重复使用. 免费套餐提供每月从 API 和 URL 创建的 70 张图像，以及通过 Form 创建最多 100 张图像.
  * [OpenAPI3 Designer](https://openapidesigner.com/) — 免费以可视化方式创建 Open API 3 定义.
  * [parsehub.com](https://parsehub.com/) — 从动态站点中提取数据，将动态站点转化为 API，5 个项目免费.
  * [Pixela](https://pixe.la/)  - 免费日流数据库服务. 所有操作均由 API 执行. 也可以使用热图和折线图进行可视化.
  * [Postbacks](https://postbacks.io/)  - 稍后请求 HTTP 回调. 注册时有 8,000 个免费请求.
  * [Postman](https://postman.com)  — 使用 API 开发协作平台 Postman 简化工作流程并创建更好的 API——更快. 永久免费使用 Postman App. 邮递员云功能也永久免费，但有一定的限制.
  * [ProxyCrawl](https://proxycrawl.com/)  — 无需代理、基础设施或浏览器即可抓取和抓取网站. 我们为您解决验证码并防止您被阻止. 前 1000 个电话是免费的.
  * [QuickMocker](https://quickmocker.com/)  — 在您自己的子域下管理在线虚假 API 端点，将请求转发到 localhost URL 以进行 webhooks 开发和测试，使用 RegExp 和多种 HTTP 方法作为 URL 路径，优先考虑端点，100 多个短代码（动态或虚假响应值）用于响应模板，从 OpenAPI (Swagger) 规范中导入 JSON 格式、代理请求、通过 IP 地址和授权标头限制端点. 免费帐户提供 1 个随机子域、10 个端点、5 个 RegExp URL 路径、每个端点 50 个短代码、每天 100 个请求、请求日志中的 50 个历史记录.
  * [RequestBin.com](https://requestbin.com)  — 创建一个免费端点，您可以向其发送 HTTP 请求. 发送到该端点的任何 HTTP 请求都将与关联的负载和标头一起记录，以便您可以观察来自 Webhook 和其他服务的请求.
  * [restlet.com](https://restlet.com/products/apispark/) — APISpark 使任何 API、应用程序或数据所有者能够通过直观的浏览器界面在几分钟内成为 API 提供者.
  * [Roboflow](https://roboflow.com)  - 无需先前的机器学习经验即可创建和部署自定义计算机视觉模型. 免费套餐包括多达 1,000 张免费源图像.
  * [ROBOHASH](https://robohash.org/) - 从任何文本生成独特（酷:) 图像的 Web 服务.
  * [Scraper.AI](https://scraper.ai) - SaaS that turns any website into a consumable API for you to build on. Free 50 extractions and 10000 API calls / month.
  * [Scraper API](https://www.scraperapi.com/)  — 基于云的网络抓取 API 处理代理、浏览器和 CAPTCHA. 使用简单的 API 调用抓取任何网页. 开始使用每月 1000 次免费 API 调用.
  * [Scraper's Proxy](https://scrapersproxy.com)  — 用于抓取的简单 HTTP 代理 API. 匿名抓取，无需担心限制、阻止或验证码. 每月前 100 次成功抓取免费，包括 javascript 渲染（如果您联系支持，则可获得更多）.
  * [ScrapingAnt](https://scrapingant.com/)  — 无头 Chrome 抓取 API 和免费检查代理服务.  Javascript 渲染、高级旋转代理、避免验证码. 提供免费计划.
  * [ScraperBox](https://scraperbox.com/)  — 使用真实 Chrome 浏览器和代理轮换的无法检测的网络抓取 API. 使用简单的 API 调用来抓取任何网页. 免费计划每月有 1000 个请求.
  * [ScrapingDog](https://scrapingdog.com/)  — Scrapingdog 处理数百万个代理、浏览器和 CAPTCHA，以在单个 API 调用中为您提供任何网页的 HTML. 它还提供适用于 Chrome 和 Firefox 的 Web Scraper 和用于即时抓取需求的软件. 提供免费计划.
  * [scrapinghub.com](https://scrapinghub.com)  — 使用可视化界面和插件进行数据抓取. 免费计划包括在共享服务器上无限抓取.
  * [ScrapingNinja](https://www.scrapingninja.co/)  — 一站式处理 JS 渲染、Chrome Headless、代理旋转和 CAPTCHA 解决方案. 前 1000 个免费，无需信用卡.
  * [Sheetson](https://sheetson.com)  - 立即将任何 Google 表格转换为 RESTful API. 提供免费计划.
  * [shrtcode API](https://shrtco.de/docs) - 未经授权且无请求限制的免费 URL Shortening API.
  * [SerpApi](https://serpapi.com/)  - 实时搜索引擎抓取 API. 返回 Google、Youtube、Bing、百度、沃尔玛和许多其他引擎的结构化 JSON 结果. 免费计划包括每月 100 次成功的 API 调用.
  * [Similar Words API](https://word-simi.herokuapp.com/) — 查找相似词的 API，词汇量约 400 万个.
  * [Sofodata](https://www.sofodata.com/)  - 从 CSV 文件创建安全的 RESTful API. 上传 CSV 文件并通过其 API 立即访问数据，从而加快应用程序开发. 免费计划包括每月 2 个 API 和 2,500 个 API 调用. 不需要信用卡.
  * [tamber](https://tamber.com)  — 将深度学习驱动的推荐放入您的应用中. 每月免费 5k 活跃用户.
  * [Time Door](https://timedoor.io) - 时间序列分析 API.
  * [TinyMCE](https://www.tiny.cloud)  - 富文本编辑API. 核心功能免费无限使用.
  * [Unixtime](https://unixtime.co.za) - 用于将 Unixtime 转换为 DateTime 的免费 API，反之亦然.
  * [Vattly](https://vattly.com/)  - 高度可用、快速且安全的增值税验证 API，可提供完整的欧盟覆盖范围. 每天 10 次免费 API 调用.
  * [Webhook.site](https://webhook.site) - 使用这个即时显示请求的方便工具轻松测试 HTTP webhook.
  * [wit.ai](https://wit.ai/) — 面向开发人员的 NLP.
  * [wolfram.com](http://wolfram.com/language/) — 在云中内置基于知识的算法.
  * [wrapapi.com](https://wrapapi.com/)  — 将任何网站变成参数化的 API. 每月 3 万次 API 调用.
  * [Zenscrape](https://zenscrape.com/web-scraping-api)  — 带有无头浏览器、住宅 IP 和简单定价的 Web 抓取 API. 每月 1000 次免费 API 调用，为学生和非营利组织提供额外的免费积分.
  * [ip-api](https://ip-api.com) — IP 地理定位 API，非商业用途免费，无需 API 密钥，免费计划限制为来自同一 IP 地址的 45 请求/分钟.
  * [WebScraping.AI](https://webscraping.ai)  - 带有内置解析、Chrome 渲染和代理的简单 Web Scraping API. 每月 2000 次免费 API 调用.
  * [Zipcodebase](https://zipcodebase.com)  - 免费邮政编码 API，访问全球邮政编码数据.  10000 个免费请求/月.
  * [EVA](http://eva.pingutil.com/) - 免费的电子邮件验证器 API，它有助于识别电子邮件是否是一次性的并具有有效的 MX 记录.
  * [happi.dev](https://happi.dev)  - 免费增值 api 服务集合（音乐、汇率、键值存储、语言检测、密码生成器、二维码生成器、歌词）. 每月 8000 次免费 API 调用.
  * [huggingface.co](https://huggingface.co) - Build, train and deploy NLP models for Pytorch, TensorFlow, and JAX. Free up to 30k input characters/mo.
  * [vatcheckapi.com](https://vatcheckapi.com)  - 简单且免费的增值税号验证 API. 每月 500 个免费请求.
  * [numlookupapi.com](https://numlookupapi.com) - 免费电话号码验证 API - 100k 免费请求/月.


## Artifact Repos

 * [Artifactory](https://jfrog.com/start-free/)  - 一个工件存储库，支持多种包格式，如 Maven、Docker、Cargo、Helm、PyPI、CocoaPods 和 GitLFS. 包括包扫描工具 XRay 和 CI/CD 工具 Pipelines（以前称为 Shippable），免费套餐为每月 2,000 CI/CD 分钟.
 * [central.sonatype.org](https://central.sonatype.org) — Apache Maven、SBT 和其他构建系统的默认工件存储库.
 * [cloudrepo.io](https://cloudrepo.io)  - 基于云的、私有和公共的、Maven 和 PyPi 存储库. 开源项目免费.
 * [cloudsmith.io](https://cloudsmith.io)  — 适用于 Java/Maven、RedHat、Debian、Python、Ruby、Vagrant 等的简单、安全和集中的存储库服务. 免费层 + 免费开源.
 * [jitpack.io](https://jitpack.io/) — GitHub 上 JVM 和 Android 项目的 Maven 存储库，对公共项目免费.
 * [packagecloud.io](https://packagecloud.io/users/new?plan=free_usage_plan) — 易于使用的存储库托管：Maven、RPM、DEB、PyPi、NPM 和 RubyGem 包（有免费层）.
 * [repsy.io](https://repsy.io) — 1 GB 免费的私有/公共 Maven 存储库.


## Tools for Teams and Collaboration

  * [3Cols](https://3cols.com/) - A free cloud based code snippet manager for personal and collaborative code.
  * [Bitwarden](https://bitwarden.com) — 个人、团队和商业组织存储、共享和同步敏感数据的最简单、最安全的方式.
  * [Braid](https://www.braidchat.com/)  — 专为团队设计的聊天应用程序. 公共访问组、无限用户、历史记录和集成免费. 它还提供自托管的开源版本.
  * [cally.com](https://cally.com/)  — 找到会议的最佳时间和日期. 使用简单，适用于小型和大型团体.
  * [Calendly](https://calendly.com)  — Calendly 是连接和安排会议的工具. 免费计划为每位用户提供 1 个日历连接和无限会议. 还提供桌面和移动应用程序.
  * [Discord](https://discord.com/)  — 与公共/私人房间聊天.  Markdown 文本、语音、视频和屏幕共享功能. 无限用户免费.
  * [Telegram](https://telegram.org/)  — Telegram 适用于所有需要快速可靠消息和通话的人. 商业用户和小团队可能喜欢大型群组、用户名、桌面应用程序和强大的文件共享选项.
  * [Duckly](https://duckly.com/)  — 与您的团队实时交谈和协作. 与任何IDE配对编程，终端共享，语音、视频和屏幕共享. 小团队免费.
  * [evernote.com](https://evernote.com/)  — 组织信息的工具. 分享您的笔记并与他人一起工作
  * [Fibery](https://fibery.io/)  — 连接的工作空间平台. 单用户免费，最多 2 GB 磁盘空间.
  * [Filestash](https://www.filestash.app) — 类似 Dropbox 的文件管理器，可连接到一系列协议和平台：S3、FTP、SFTP、Minio、Git、WebDAV、Backblaze、LDAP 等.
  * [flock.com](https://flock.com)  — 为您的团队提供更快捷的沟通方式. 免费无限的消息、渠道、用户、应用程序和集成
  * [Flowdash](https://flowdash.com/)  — 自动化业务工作流程. 最多 3 个用户、1000 个任务和 3 个工作流的免费套餐.
  * [flowdock.com](https://www.flowdock.com/) — 聊天和收件箱，最多 5 人的团队免费
  * [GitDailies](https://gitdailies.com)  - 团队在 GitHub 上的提交和拉取请求活动的每日报告. 包括推送可视化工具、对等识别系统、自定义警报生成器. 免费层拥有无限用户、3 个存储库、3 个警报配置.
  * [gitter.im](https://gitter.im/)  — 聊天，用于 GitHub. 无限的公共和私人房间，最多 25 人的团队免费
  * [hangouts.google.com](https://hangouts.google.com/) — 所有对话的一个地方，免费，需要一个 Google 帐户
  * [HeySpace](https://hey.space)  - 具有聊天、日历、时间线和视频通话功能的任务管理工具. 最多 5 个用户免费.
  * [helplightning.com](https://www.helplightning.com/)  — 使用增强现实技术帮助视频. 免费，无需分析、加密、支持
  * [ideascale.com](https://ideascale.com/) — 允许客户提交想法和投票，1 个社区 25 名成员免费
  * [Igloo](https://www.igloosoftware.com/) — 用于共享文档、博客和日历等的内部门户.最多 10 个用户免费.
  * [Keybase](https://keybase.io/) — Keybase 是 Slack 的一个很酷的 FOSS 替代品，它可以保护每个人的聊天和文件安全，从家庭到社区再到公司.
  * [Google Meet](https://meet.google.com/)  — 使用 Google Meet 满足您企业的在线视频会议需求.  Meet 提供安全且易于加入的在线会议.
  * [MarkUp](https://www.markup.io/) — MarkUp 可让您直接在网站、PDF 和图像上收集反馈.
  * [meet.jit.si](https://meet.jit.si/) — 一键视频对话、屏幕共享，免费
  * [Microsoft Teams](https://products.office.com/microsoft-teams/free)  — Microsoft Teams 是一个基于聊天的数字中心，可通过单一体验将对话、内容和应用程序集中在一个地方. 最多 50 万用户免费.
  * [Miro](https://miro.com/)  - 适用于分布式团队的可扩展、安全、跨设备和企业就绪的团队协作白板. 有免费增值计划.
  * [Notion](https://www.notion.so/)  - Notion 是一款笔记和协作应用程序，支持 Markdown，还集成了任务、wiki 和数据库. 该公司将该应用程序描述为用于记笔记、项目管理和任务管理的多合一工作区. 除了跨平台应用程序外，它还可以通过大多数网络浏览器访问.
  * [Nuclino](https://www.nuclino.com)  - 一个轻量级的协作维基，用于您团队的所有知识、文档和笔记. 免费计划包含所有基本功能，最多 50 个项目，总存储空间为 5GB.
  * [Pendulums](https://pendulums.io/) - Pendulums 是一款免费的时间跟踪工具，它具有易于使用的界面和有用的统计数据，可帮助您更好地管理时间.
  * [Raindrop.io](https://raindrop.io)  - 适用于 macOS、Windows、Android、iOS 和 Web 的私密且安全的书签应用程序. 免费无限书签和协作.
  * [element.io](https://element.io/)  — 基于 Matrix 的去中心化开源通信工具. 群聊、直接消息传递、加密文件传输、语音和视频聊天以及与其他服务的轻松集成.
  * [Rocket.Chat](https://rocket.chat/) - 团队共享收件箱，安全、无限制和开源.
  * [seafile.com](https://www.seafile.com/)  — 私有或云存储、文件共享、同步、讨论. 私人版已满. 云版本只有 1 GB
  * [Slab](https://slab.com/)  — 为团队提供的现代知识管理服务. 最多 10 个用户免费.
  * [slack.com](https://slack.com/) — 对于具有某些功能限制的无限制用户免费
  * [Spectrum](https://spectrum.chat/) - 免费创建公共或私人社区.
  * [StatusPile](https://www.statuspile.com/)  - 状态页面的状态页面. 跟踪上游提供商的状态页面.
  * [talky.io](https://talky.io/)  — 免费群组视频聊天. 匿名的. 点对点. 无需插件、注册或付款
  * [Tefter](https://tefter.io)  - 具有强大 Slack 集成的书签应用程序. 开源团队免费.
  * [TeleType](https://teletype.oorja.io/)  — 共享终端、语音、代码、白板等. 无需登录，面向开发人员的端到端加密协作.
  * [TimeCamp](https://www.timecamp.com/)  - 无限用户的免费时间跟踪软件. 轻松与 Jira、Trello、Asana 等 PM 工具集成.
  * [Tree Schema](https://treeschema.com/)  — 使用 API 进行数据目录和元数据管理，以将数据沿袭作为代码进行管理. 最多 5 个用户的团队免费.
  * [twist.com](https://twist.com)  — 一个异步友好的团队通信应用程序，其中的对话保持井井有条且切题. 提供免费和无限计划. 为符合条件的团队提供折扣.
  * [BookmarkOS.com](https://bookmarkos.com) - 免费的多合一书签管理器、标签管理器和任务管理器位于可自定义的在线桌面中，具有文件夹协作功能.
  * [typetalk.com](https://www.typetalk.com/) — 通过网络或手机上的即时消息与您的团队分享和讨论想法
  * [Tugboat](https://tugboat.qa)  - 预览每个拉取请求，自动和按需. 所有人免费，非营利组织的免费 Nano 层.
  * [whereby.com](https://whereby.com/) — 一键式视频对话，免费（以前称为出现.in）
  * [vadoo.tv](https://vadoo.tv/)  — 视频托管和营销变得简单. 一键上传视频. 记录、管理、分享等. 免费套餐提供多达 10 个视频、1 GB 存储空间、10 GB 带宽/月
  * [vspace](https://vvv.space/) — 带有私人/公共空间的免费链接管理器，包括 slack 和 google docs 集成以及 chrome 插件.
  * [userforge.com](https://userforge.com/)  - 相互关联的在线角色、用户故事和上下文映射. 帮助保持设计和开发同步，最多 3 个角色和 2 个协作者免费.
  * [wistia.com](https://wistia.com/) — 带有观众分析、高清视频交付和营销工具的视频托管，以帮助了解您的访客、25 个视频和 Wistia 品牌播放器
  * [wormhol.org](https://www.wormhol.org/)  — 简单的文件共享服务. 与任意数量的同行共享最大 5GB 的无限文件.
  * [zoom.us](https://zoom.us/)  — 提供安全视频和 Web 会议、附加组件. 免费限时40分钟
  * [shtab.app](https://shtab.app/) - 项目管理服务，通过基于人工智能的跟踪器使办公室协作和远程透明.
  * [zdoo.co](https://www.zdoo.co)  — 借助 CRM、OA 和项目管理套件，zdoo 非常适合团队协作. 提供有限用户和空间的免费云版本，高级版本可免费试用一个月.
  * [Zulip](https://zulip.com/)  — 使用独特的类似电子邮件的线程模型进行实时聊天. 免费计划包括 10,000 条搜索历史消息和高达 5 GB 的文件存储空间. 它还提供自托管的开源版本.
  * [Automate.io](https://automate.io)  - 具有 200 多个应用程序集成的简单和复杂的自动化工作流工具. 每月 300 次操作和 5 个机器人是免费
  * [robocorp.com](https://robocorp.com) - Open-source stack for powering Automation Ops. Try out Cloud features and implement simple automations for free. Robot work 240 min/month, 10 Assistant runs, Storage of 100 MB.
  * [Fleep.io](https://fleep.io/)  — Fleep 是 Slack 的替代品. 它为具有完整消息历史记录、无限制的 1:1 对话、1 个群组对话和 1 GB 文件存储的小型团队提供免费计划.
  * [Chanty.com](https://chanty.com/)  — Chanty 是 Slack 的另一种替代方案. 它为小型团队（最多 10 个）提供永久免费计划，具有无限的公共和私人对话、可搜索的历史记录、无限的 1:1 音频通话、无限的语音消息、10 个集成和每个团队 20 GB 的存储空间.


## CMS

  * [acquia.com](https://www.acquia.com/)  — 托管 Drupal 站点. 开发人员的免费层. 还提供免费的开发工具（例如 Acquia Dev Desktop）
  * [Contentful](https://www.contentful.com/)  — 无头 CMS. 云中的内容管理和交付 API. 附带 1 个免费社区空间，其中包括 5 个用户、25K 记录、48 种内容类型、2 个语言环境.
  * [Cosmic](https://www.cosmicjs.com/)  — 无头 CMS 和 API 工具包. 面向开发人员的免费个人计划.
  * [Crystallize](https://crystallize.com)  — 具有电子商务支持的无头 PIM. 内置 GraphQL API. 免费版包括无限用户、1000 个目录项、5 GB/月带宽和 25k/月 API 调用.
  * [Directus](https://directus.io)  — 无头 CMS. 一个完全免费的开源平台，用于管理本地或云中的资产和数据库内容. 没有限制或付费墙.
  * [Forestry.io/](https://forestry.io/)  — 无头 CMS. 为您的编辑提供 Git 的强大功能. 轻松创建和编辑基于 Markdown 的内容. 附带三个免费网站，其中包括 3 个编辑器、即时预览. 与托管在 Netlify/GitHubpages/ 其他地方的博客集成
  * [FrontAid](https://frontaid.io/)  — Headless CMS，将 JSON 内容直接存储在您自己的 Git 存储库中. 没有限制.
  * [kontent.ai](https://www.kontent.ai)  - 一个内容即服务平台，为您提供所有无头 CMS 的好处，同时为营销人员提供支持. 开发者计划为 2 个用户提供无限的项目，每个项目有 2 个环境、500 个内容项、2 种语言以及交付和管理 API，以及自定义元素支持. 更大的计划可满足您的需求.
  * [Prismic](https://www.prismic.io/)  — 无头 CMS. 具有完全托管和可扩展 API 的内容管理界面. 社区计划为 1 个用户提供无限的 API 调用、文档、自定义类型、资产和区域设置. 下一个项目所需的一切. 更大的免费计划可用于开放内容/开源项目.
  * [sanity.io](https://www.sanity.io/)  – 使用 React 构建的可定制 MIT 许可编辑器为结构化内容托管后端. 无限项目.  3 个用户、2 个数据集、50 万次 API CDN 请求、每个项目免费 5GB 资产
  * [sensenet](https://sensenet.com)  - API 优先的无头 CMS，为各种规模的企业提供企业级解决方案. 开发者计划提供 3 个用户、500 个内容项、3 个内置角色、25+5 种内容类型、完全可访问的 REST API、文档预览生成和 Office Online 编辑.
  * [GraphCMS](https://graphcms.com/)  - 为小型项目提供免费套餐.  GraphQL 第一个 API. 从传统解决方案转向 GraphQL 原生 Headless CMS - 并首先提供全渠道内容 API.
  * [Squidex](https://squidex.io/)  - 为小型项目提供免费套餐. 首先是 API / GraphQL. 开源，并基于事件源（自动处理每个更改）.


## Code Quality

  * [SoftaCheck](https://www.softacheck.com/)  — 使用cppcheck、clang-tidy等开源工具对C/C++代码进行静态分析并为使用doxygen的用户自动生成代码文档的在线工具. 这个工具是免费使用的.
  * [beanstalkapp.com](https://beanstalkapp.com/) — 编写、审查和部署代码的完整工作流程），1 个用户和 1 个存储库的免费帐户，具有 100 MB 的存储空间
  * [browserling.com](https://www.browserling.com/) — 实时交互式跨浏览器测试，在 Vista 下以 1024 x 768 分辨率免费使用 MS IE 9 仅 3 分钟
  * [codacy.com](https://www.codacy.com/) — PHP、Python、Ruby、Java、JavaScript、Scala、CSS 和 CoffeeScript 的自动代码审查，免费用于无限的公共和私有存储库
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev)  - 用于 DevOps 的自动化基础设施即代码审查工具与 GitHub、Bitbucket 和 GitLab（甚至自托管）集成. 除了标准语言，它还分析 Ansible、Terraform、CloudFormation、Kubernetes 等.  （开源免费）
  * [CodeBeat](https://codebeat.co)  — 可用于多种语言的自动代码审查平台. 与 Slack 和电子邮件集成的公共存储库永久免费.
  * [codeclimate.com](https://codeclimate.com/)  — 自动代码审查，开源免费和无限的组织拥有的私人存储库（最多 4 个合作者）. 学生和机构也免费.
  * [codecov.io](https://codecov.io/) — 代码覆盖工具 (SaaS)，开源免费和 1 个免费私人仓库
  * [CodeFactor](https://www.codefactor.io)  — Git 的自动代码审查. 免费版包括无限用户、无限公共存储库和 1 个私人存储库.
  * [codescene.io](https://codescene.io/)  - CodeScene 根据开发人员如何使用代码并可视化组织因素（如团队耦合和系统掌握）来优先考虑技术债务. 开源免费.
  * [coveralls.io](https://coveralls.io/) — 显示测试覆盖率报告，开源免费
  * [dareboost](https://dareboost.com) - 5 free analysis report for web performance, accessibility, security each month
  * [deepcode.ai](https://www.deepcode.ai)  — DeepCode 基于 AI 发现 bug、安全漏洞、性能和 API 问题.  DeepCode 的分析速度使我们能够实时分析您的代码并在您点击 IDE 中的保存按钮时提供结果. 支持的语言包括 Java、C/C++、JavaScript、Python 和 TypeScript. 与 GitHub、BitBucket 和 Gitlab 的集成. 开源和私有存储库免费，最多可免费 30 名开发人员.
  * [deepscan.io](https://deepscan.io) — 高级静态分析，用于自动查找 JavaScript 代码中的运行时错误，开源免费
  * [DeepSource](https://deepsource.io/)  - DeepSource 持续分析源代码更改，发现并修复归类为安全性、性能、反模式、错误风险、文档和风格的问题. 与 GitHub、GitLab 和 Bitbucket 的本地集成.
  * [eversql.com](https://www.eversql.com/) — EverSQL - The #1 platform for database optimization. Gain critical insights into your database and SQL queries, auto-magically.
  * [gerrithub.io](https://review.gerrithub.io/) — 免费为 GitHub 存储库进行 Gerrit 代码审查
  * [gocover.io](https://gocover.io/) — 任何代码覆盖率 [Go](https://golang.org/) 包裹
  * [goreportcard.com](https://goreportcard.com/) — Go 项目的代码质量，开源免费
  * [gtmetrix.com](https://gtmetrix.com/) — 优化网站的报告和详尽建议
  * [holistic.dev](https://holistic.dev/) - The #1 static code analyzer for Postgresql optimization. Performance, security, and architect database issues automatic detection service
  * [houndci.com](https://houndci.com/) — 对 GitHub 提交的关于代码质量的评论，开源免费
  * [Imgbot](https://github.com/marketplace/imgbot) — Imgbot is a friendly robot that optimizes your images and saves you time. Optimized images mean smaller file sizes without sacrificing quality. It's free for open source.
  * [Kritika](https://kritika.io/)  — Perl 的静态代码分析与 GitHub 的集成. 免费提供无限制的公共存储库.
  * [resmush.it](https://resmush.it)  — reSmush.it 是一个提供图像优化的免费 API.  reSmush.it 已在最常见的 CMS 上实现，例如 Wordpress、Drupal 或 Magento.  reSmush.it 是最常用的图像优化 API，已经处理了超过 70 亿张图像，并且仍然是免费的.
  * [insight.sensiolabs.com](https://insight.sensiolabs.com/) — PHP/Symfony 项目的代码质量，开源免费
  * [lgtm.com](https://lgtm.com) — Continuous security analysis for Java, Python, JavaScript, TypeScript, C#, C and C++, free for Open Source
  * [reviewable.io](https://reviewable.io/) — GitHub 存储库的代码审查，公共或个人存储库免费
  * [parsers.dev](https://parsers.dev/) - 抽象语法树解析器和中间表示编译器即服务
  * [scan.coverity.com](https://scan.coverity.com/) — Static code analysis for Java, C/C++, C# and JavaScript, free for Open Source
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 持续检测平台，开源免费
  * [shields.io](https://shields.io) — 开源项目的质量元数据徽章
  * [Sider](https://sider.review)  — 多种语言的代码审查平台. 支持与 GitHub 集成. 对于具有无限用户的公共存储库免费.
  * [sonarcloud.io](https://sonarcloud.io) — Automated source code analysis for Java, JavaScript, C/C++, C#, VB.NET, PHP, Objective-C, Swift, Python, Groovy and even more languages, free for Open Source
  * [SourceLevel](https://sourcelevel.io/)  — 自动代码审查和团队分析. 开源和最多 5 个合作者的组织免费.
  * [Typo CI](https://github.com/marketplace/typo-ci) — Typo CI 审查您的拉取请求并提交拼写错误，开源免费.
  * [Viezly](https://viezly.com/)  - 增强的代码审查工具，使代码阅读和导航更容易. 开源免费，个人使用免费.
  * [webceo.com](https://www.webceo.com/) — SEO 工具，但也有代码验证和不同类型的建议
  * [zoompf.com](https://zoompf.com/) — 修复您网站的性能，详细分析


## Code Search and Browsing

  * [codota.com](https://www.codota.com/)  — Codota 通过提供从世界上所有代码中学到的见解，帮助开发人员更快地创建更好的软件. 插件可用.
  * [libraries.io](https://libraries.io/) — 32 个不同包管理器的搜索和依赖更新通知，开源免费
  * [Namae](https://namae.dev/) - 在 github、gitlab、heroku、netlify 等各种网站上搜索您的项目名称的可用性.
  * [searchcode.com](https://searchcode.com/) — 全面的基于文本的代码搜索，开源免费
  * [sourcegraph.com](https://about.sourcegraph.com/) — Java、Go、Python、Node.js 等，代码搜索/交叉引用，开源免费
  * [tickgit.com](https://www.tickgit.com/) — 显示 `TODO` 注释（和其他标记）以识别值得返回以进行改进的代码区域.
  * [CodeKeep](https://codekeep.io)  - 用于代码片段的 Google Keep. 组织、发现和共享代码片段，具有强大的代码截图工具，具有预设模板和链接功能.


## CI and CD

  * [AccessLint](https://github.com/marketplace/accesslint)  — AccessLint 将自动化的 Web 可访问性测试带入您的开发工作流程. 出于开源和教育目的，它是免费的.
  * [appcircle.io](https://appcircle.io)  — 带有在线设备模拟器的 iOS 和 Android 自动化移动 CI/CD/CT.  20 分钟构建超时（开源为 60 分钟），单并发免费.
  * [appveyor.com](https://www.appveyor.com/) — Windows 的 CD 服务，开源免费
  * [bitrise.io](https://www.bitrise.io/)  — 适用于原生或混合移动应用程序的 CI/CD. 每月 200 次免费构建，10 分钟构建时间和两名团队成员.  OSS 项目获得 45 分钟的构建时间、+1 并发和无限的团队规模.
  * [buddy.works](https://buddy.works/) — 包含 5 个免费项目和 1 个并发运行的 CI/CD（120 次执行/月）
  * [buddybuild.com](https://www.buddybuild.com/) — 在一个无缝的迭代系统中为您的 iOS 和 Android 应用程序构建、部署和收集反馈
  * [circleci.com](https://circleci.com/) — 一次并发构建免费
  * [cirrus-ci.org](https://cirrus-ci.org) - 公共 GitHub 存储库免费
  * [codefresh.io](https://codefresh.io) — 终身免费计划：1 个构建、1 个环境、共享服务器、无限制的公共存储库
  * [codemagic.io](https://codemagic.io/) - 每月免费 500 分钟构建时间
  * [codeship.com](https://codeship.com/) — 每月 100 个私有构建，5 个私有项目，开源无限制
  * [Continuous PHP](https://continuousphp.com/)  —Continuousphp 是第一个也是唯一一个以 PHP 为中心的平台，可以在同一工作流中构建、打包、测试和部署应用程序. 免费用于社区项目，即 OSS/公共/教育项目.
  * [deployhq.com](https://www.deployhq.com/) — 1 个项目，每日部署 10 次（每月 30 分钟构建）
  * [drone](https://cloud.drone.io/) - Drone Cloud 使开发人员能够跨多个架构运行持续交付管道 - 包括 x86 和 Arm（32 位和 64 位） - 全部在一个地方
  * [LayerCI](https://layerci.com)  — 全栈项目的 CI.  1 个具有 5GB 内存和 3 个 CPU 的全栈预览环境.
  * [ligurio/awesome-ci](https://github.com/ligurio/awesome-ci) — 持续集成服务的比较
  * [Octopus Deploy](https://octopus.com)  - 自动化部署和发布管理.  &lt;= 10 个部署目标免费.
  * [scalr.com](https://scalr.com/)  - Terraform 的远程状态和操作后端，具有完整的 CLI 支持、与 OPA 的集成和分层配置模型. 最多可免费 5 个用户.
  * [semaphoreci.com](https://semaphoreci.com/) — 开源免费，每月 100 次私有构建
  * [Squash Labs](https://www.squash.io/) — 为每个分支创建一个 VM，并使您的应用程序可从唯一的 URL、无限的公共和私有存储库、高达 2 GB 的 VM 大小使用.
  * [stackahoy.io](https://stackahoy.io)  — 100% 免费. 无限制的部署、分支和构建
  * [styleci.io](https://styleci.io/) — 仅限公共 GitHub 存储库
  * [Mergify](https://mergify.io) — GitHub 的工作流自动化和合并队列 — 免费用于公共 GitHub 存储库
  * [Integromat](https://www.integromat.com)  — 工作流自动化工具，可让您使用 UI 连接应用程序和自动化工作流，它支持许多应用程序和最流行的 API. 公共 GitHub 存储库免费，免费等级为 100 Mb、1000 次操作和 15 分钟的最小间隔.



## Testing

  * [Applitools.com](https://applitools.com/) — Smart visual validation for web, native mobile and desktop apps. Integrates with almost all automation solutions (like Selenium and Karma) and remote runners (Sauce Labs, Browser Stack). free for open source. A free tier for a single user with limited checkpoints per week.
  * [Appetize](https://appetize.io)  — 直接在浏览器中在此基于云的 Android 手机/平板电脑模拟器和 iPhone/iPad 模拟器上测试您的 Android 和 iOS 应用程序. 免费套餐包括 1 个并发会话，每月使用 100 分钟. 应用程序大小没有限制.
  * [Bird Eats Bug](https://www.birdeatsbug.com/)  — 更快（更好）报告错误. 使用 Bird 浏览器扩展记录您的屏幕，它会自动捕获工程师需要调试的技术数据. 适合小团队的免费套餐.
  * [browserstack.com](https://www.browserstack.com/) — 手动和自动浏览器测试， [free for Open Source](https://www.browserstack.com/open-source?ref=pricing)
  * [checkbot.io](https://www.checkbot.io/)  — 测试您的网站是否遵循 50 多个 SEO、速度和安全最佳实践的浏览器扩展. 小型网站的免费套餐.
  * [crossbrowsertesting.com](https://crossbrowsertesting.com) - 云端手动、可视化和 Selenium 浏览器测试 - [free for Open Source](https://crossbrowsertesting.com/open-source)
  * [cypress.io](https://www.cypress.io/)  - 对浏览器中运行的任何内容进行快速、简单和可靠的测试.  Cypress Test Runner 始终是免费和开源的，没有任何限制和限制.  Cypress Dashboard 可免费用于最多 5 个用户的开源项目.
  * [everystep-automation.com](https://www.everystep-automation.com/) — 记录和重放在 Web 浏览器中执行的所有步骤并创建脚本，...免费，选项较少
  * [Gremlin](https://www.gremlin.com/gremlin-free-software)  — Gremlin 的 Chaos Engineering 工具可让您安全、可靠且简单地将故障注入您的系统，以便在它们导致面向客户的问题之前找到弱点.  Gremlin Free 提供对最多 5 个主机或容器的关闭和 CPU 攻击的访问.
  * [gridlastic.com](https://www.gridlastic.com/) — Selenium Grid 测试，免费计划最多 4 个同时 selenium 节点/10 个网格启动/4,000 测试分钟/月
  * [loadmill.com](https://www.loadmill.com/)  - 通过分析网络流量自动创建 API 和负载测试. 每月免费模拟最多 50 个并发用户最多 60 分钟.
  * [percy.io](https://percy.io)  - 向任何 Web 应用程序、静态站点、样式指南或组件库添加可视化测试. 无限的团队成员，演示应用程序和无限的项目，每月 5,000 个快照.
  * [reflect.run](https://reflect.run)  - 网络应用程序的无代码自动化测试. 测试可以在应用程序内安排或从 CI/CD 工具执行. 每次测试运行都包括完整的视频记录以及控制台和网络日志. 免费套餐包括无限数量的已保存测试，每月运行 25 次测试，最多 3 个用户.
  * [saucelabs.com](https://saucelabs.com/) — 跨浏览器测试、Selenium 测试和移动测试， [free for Open Source](https://saucelabs.com/open-source)
  * [testingbot.com](https://testingbot.com/) — Selenium 浏览器和设备测试， [free for Open Source](https://testingbot.com/open-source)
  * [Testspace.com](https://testspace.com/)  - 用于发布自动化测试结果的仪表板和用于使用 GitHub 将手动测试作为代码实现的框架. 该服务是 [free for Open Source](https://github.com/marketplace/testspace-com) 占每月 450 个结果.  
  * [tesults.com](https://www.tesults.com)  — 测试结果报告和测试用例管理. 与流行的测试框架集成. 开源软件开发人员、个人、教育工作者和小型团队可以申请基本免费项目以外的折扣和免费产品.
  * [websitepulse.com](https://www.websitepulse.com/tools/) — 各种免费的网络和服务器工具.
  * [qase.io](https://qase.io)  - 开发和 QA 团队的测试管理系统. 管理测试用例、编写测试运行、执行测试运行、跟踪缺陷和衡量影响. 免费套餐包括所有核心功能，500Mb 可用于附件和最多 3 个用户.
  * [knapsackpro.com](https://knapsackpro.com)  - 在任何 CI 提供者上通过最佳测试套件并行化加速您的测试. 在并行 CI 节点上拆分 Ruby、JavaScript 测试以节省时间. 最多 10 分钟测试文件的免费计划和开源项目的免费无限计划.
  * [webhook.site](https://webhook.site)  - 使用自定义 URL 验证网络钩子、出站 HTTP 请求或电子邮件. 临时 URL 和电子邮件地址始终免费.
  * [Vaadin](https://vaadin.com)  — 使用 Java 或 TypeScript 构建可扩展的 UI，并使用集成的工具、组件和设计系统来更快地迭代、更好地设计并简化开发过程. 无限项目，5 年免费维护.


## Security and PKI

  * [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — 发现网络中受感染的系统
  * [atomist.com](https://atomist.com/)  — 一种更快、更方便的方法来自动化各种开发任务. 现在处于测试阶段.
  * [auth0.com](https://auth0.com/)  — 为开发 SSO 免费托管. 最多 2 个用于闭源项目的社交身份提供者.
  * [Authress](https://authress.io/) — Authentication login and access control, unlimited identity providers for any project. Facebook, Google, Twitter and more. First 1000 API calls are free.
  * [Authy](https://authy.com)  - 多台设备上的双因素身份验证 (2FA)，带备份.  Google Authenticator 的替代品. 最多可免费进行 100 次成功的身份验证.
  * [Bridgecrew](https://bridgecrew.io/) — 由开源工具提供支持的基础设施即代码 (IaC) 安全性 — [Checkov](https://github.com/bridgecrewio/checkov) .  Bridgecrew 核心平台最多可免费使用 50 个 IaC 资源.
  * [cloudsploit.com](https://cloudsploit.com/) — 亚马逊网络服务 (AWS) 安全与合规审计和监控
  * [Cmd](https://cmd.com/) — 安全平台为云或数据中心中的每个 Linux 实例提供实时访问控制和动态策略执行
  * [CodeNotary.io](https://www.codenotary.io/) — 具有不可磨灭证明的开源平台，可对代码、文件、目录或容器进行公证
  * [crypteron.com](https://www.crypteron.com/) — 云优先、开发人员友好的安全平台可防止 .NET 和 Java 应用程序中的数据泄露
  * [Dependabot](https://dependabot.com/) Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven 和 Gradle）、.NET、Go、Elm、Docker、Terraform、Git 子模块和 GitHub 操作的自动依赖更新.
  * [DJ Checkup](https://djcheckup.com)  — 使用这个免费、自动化的检查工具扫描您的 Django 站点是否存在安全漏洞. 从 Pony Checkup 站点分叉.
  * [Doppler](https://doppler.com/)  — 用于应用程序机密和配置的 Universal Secrets Manager，支持同步到各种云提供商. 具有基本访问控制的无限用户免费.
  * [duo.com](https://duo.com/)  — 网站或应用程序的双因素身份验证 (2FA).  10 个用户免费，所有身份验证方法，无限制，集成，硬件令牌.
  * [globalsign.com](https://www.globalsign.com/en/ssl/ssl-open-source/) — 开源的免费 SSL 证书
  * [Have I been pwned?](https://haveibeenpwned.com) — 用于获取违规信息的 REST API.
  * [Internet.nl](https://internet.nl) — 测试现代互联网标准，如 IPv6、DNSSEC、HTTPS、DMARC、STARTTLS 和 DANE
  * [Jumpcloud](https://jumpcloud.com/)  — 提供类似于 Azure AD、用户管理、单一登录和 RADIUS 身份验证的目录即服务. 最多 10 个用户免费.
  * [keychest.net](https://keychest.net) - SSL 到期管理和证书购买与集成 CT 数据库
  * [letsencrypt.org](https://letsencrypt.org/) — 免费的 SSL 证书颁发机构，其证书受到所有主要浏览器的信任
  * [LoginRadius](https://www.loginradius.com/)  — 免费的托管用户身份验证服务. 电子邮件注册和 3 个社交提供商.
  * [logintc.com](https://www.logintc.com/) — 通过推送通知进行双因素身份验证 (2FA)，10 个用户免费，VPN、网站和 SSH
  * [meterian.io](https://www.meterian.io/)  - 监控 Java、Javascript、.NET、Scala、Ruby 和 NodeJS 项目的依赖项中的安全漏洞. 一个私人项目免费，开源项目不限.
  * [MojoAuth](https://mojoauth.com/) - MojoAuth 可以在几分钟内轻松地在您的网络、移动设备或任何应用程序上实施无密码身份验证.
  * [Mozilla Observatory](https://observatory.mozilla.org/) — 查找并修复站点中的安全漏洞.
  * [Okta](https://developer.okta.com/)  — 用户管理、认证和授权. 每月最多 1000 名活跃用户免费.
  * [onelogin.com](https://www.onelogin.com/) — 身份即服务 (IDaaS)、单点登录身份提供商、云 SSO IdP、3 个公司应用程序和 5 个个人应用程序、无限用户
  * [Operous](https://operous.dev/)  — 云实例测试工具，具有一套全面且自动化的最佳实践、性能和安全性测试套件. 免费套餐为 1 个用户提供 100 分钟的测试时间、10 个测试套件和最多 5 个实例.
  * [opswat.com](https://www.opswat.com/) — 计算机、设备、应用程序、配置等的安全监控...免费 25 位用户和 30 天历史用户.
  * [pyup.io](https://pyup.io)  — 监控 Python 依赖项的安全漏洞并自动更新它们. 一个私人项目免费，开源项目不限.
  * [qualys.com](https://www.qualys.com/community-edition) — 查找 Web 应用程序漏洞，审计 OWASP 风险
  * [reCAPTCHAMe](https://recaptchame.com/)  — 免费的 reCAPTCHA 和 hCAPTCHA 后端服务. 不需要服务器端编码. 适用于静态网站.
  * [report-uri.io](https://report-uri.io/) — CSP 和 HPKP 违规报告
  * [ringcaptcha.com](https://ringcaptcha.com/) — 使用电话号码作为 id 的工具，免费提供
  * [sawolabs.com](https://sawolabs.com/)  - 通过在您的应用程序中集成无密码身份验证，简化登录并改善用户体验. 每月 5000 次免费认证.
  * [snyk.io](https://snyk.io)  — 可以找到并修复开源依赖项中的已知安全漏洞. 开源项目的无限测试和修复. 您的私人项目限制为每月 200 次测试.
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) — 对任何 SSL Web 服务器的配置进行非常深入的分析
  * [StackHawk](https://www.stackhawk.com/) 在整个管道中自动扫描应用程序，以在安全漏洞投入生产之前找到并修复它们. 单个应用程序的无限扫描和环境.
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) - 免费的网站安全检查和恶意软件扫描程序
  * [Protectumus](https://protectumus.com)  - 用于 PHP 的免费网站安全检查、网站防病毒和服务器防火墙 (WAF). 免费层中注册用户的电子邮件通知.
  * [TestTLS.com](https://testtls.com) - 测试 SSL/TLS 服务的安全服务器配置、证书、链等.不限于 HTTPS.
  * [threatconnect.com](https://threatconnect.com)  — 威胁情报：它专为开始了解网络威胁情报的个人研究人员、分析师和组织而设计. 最多免费 3 个用户
  * [tinfoilsecurity.com](https://www.tinfoilsecurity.com/)  — 自动漏洞扫描. 免费计划允许每周进行一次 XSS 扫描
  * [Ubiq Security](https://ubiqsecurity.com/)  — 用 3 行代码和自动密钥管理加密和解密数据.  1 个应用程序免费，每月最多 1,000,000 次加密.
  * [Virgil Security](https://virgilsecurity.com/)  — 用于在您的数字解决方案中实施端到端加密、数据库保护、物联网安全等的工具和服务. 最多 250 个用户的应用程序免费.
  * [Virushee](https://virushee.com/)  — 由混合启发式和 AI 辅助引擎提供支持的面向隐私的文件/数据扫描. 可以使用内部动态沙箱分析. 每个文件上传限制为 50MB


## Management System

  * [bitnami.com](https://bitnami.com/)  — 在 IaaS 上部署准备好的应用程序. 免费管理 1 个 AWS 微型实例
  * [Esper](https://esper.io)  — 用于具有 DevOps 的 Android 设备的 MDM 和 MAM.  100 台设备免费，1 个用户许可证和 25 MB 应用程序存储.
  * [jamf.com](https://www.jamf.com/) — iPad、iPhone 和 Mac 的设备管理，3 台设备免费
  * [Miradore](https://miradore.com) — Device Management service. Stay up-to-date with your device fleet and secure an unlimited number of devices for free. Free plan offers basic features.
  * [moss.sh](https://moss.sh)  - 帮助开发人员部署和管理他们的 Web 应用程序和服务器. 每月最多免费 25 次 git 部署
  * [runcloud.io](https://runcloud.io/)  - 主要针对 PHP 项目的服务器管理. 最多 1 个服务器免费.
  * [ploi.io](https://ploi.io/)  - 服务器管理工​​具，可轻松管理和部署您的服务器和站点.  1 台服务器免费.


## Messaging

  * [Ably](https://www.ably.com/)  - 具有存在性、持久性和保证交付的实时消息传递服务. 免费计划包括每月 300 万条消息、100 个高峰连接和 100 个高峰频道.
  * [cloudamqp.com](https://www.cloudamqp.com/)  — RabbitMQ 即服务.  Little Lemur 计划：每月最多 100 万条消息，最多 20 个并发连接，最多 100 个队列，最多 10,000 个排队消息，不同可用区的多个节点
  * [connectycube.com](https://connectycube.com)  - 无限制的聊天消息、p2p 语音和视频通话、文件附件和推送通知. 对于高达 20K MAU 的应用程序免费.
  * [courier.com](https://www.courier.com/)  — 用于推送、应用程序内、电子邮件、聊天、短信和其他具有模板管理和其他功能的消息传递渠道的单一 API. 免费计划包括 10,000 条消息/月.
  * [pusher.com](https://pusher.com/)  — 实时消息服务. 最多 100 个同时连接和 200,000 条消息/天免费
  * [scaledrone.com](https://www.scaledrone.com/)  — 实时消息服务. 免费最多可同时连接 20 个和 100,000 个事件/天
  * [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io) 作为服务. 全球、AWS、GCP 和 Azure. 永久免费，每月 4k 消息大小、50 个活动连接和 5GB 数据.
  * [cloudkarafka.com](https://www.cloudkarafka.com/) - 免费共享 Kafka 集群，最多 5 个主题，每个主题 10MB 数据和 28 天数据保留期.
  * [pubnub.com](https://www.pubnub.com/)  - 每个月 100 万笔交易的 Swift、Kotlin 和 React 消息传递. 事务可能包含多个消息.


## Log Management

  * [bugfender.com](https://bugfender.com/) — 每天最多释放 10 万条日志行，保留 24 小时
  * [humio.com](https://www.humio.com/) — 每天最多免费 2 GB，保留 7 天
  * [logdna.com](https://logdna.com) - 单个用户免费，无保留，无限主机和来源
  * [logentries.com](https://logentries.com/) — 每月最多免费 5 GB，保留 7 天
  * [loggly.com](https://www.loggly.com/) — 单个用户免费，请参阅 lite 选项
  * [logz.io](https://logz.io/) — 每天最多免费 3 GB，保留 3 天
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-log-management)  — 由管理引擎提供支持的日志管理服务. 免费计划提供 50 GB 存储空间和 1 个月保留期.
  * [papertrailapp.com](https://papertrailapp.com/) — 48 小时搜索，7 天存档，100 MB/月
  * [sematext.com](https://sematext.com/logsene) — 每天最多免费 500 MB，保留 7 天
  * [sumologic.com](https://www.sumologic.com/) — 每天最多免费 500 MB，保留 7 天
  * [logflare.app](https://logflare.app/) — 每个应用每月最多 12,960,000 个条目免费，保留 3 天
  * [logtail.com](https://logtail.com/)  — 基于 ClickHouse 的 SQL 兼容日志管理. 每月最多免费 1 GB，保留 3 天.


## Translation Management

  * [crowdin.com](https://crowdin.com/) — 无限的项目、无限的字符串和开源的合作者
  * [gitlocalize.com](https://gitlocalize.com) - 私人和公共存储库免费且无限制
  * [lingohub.com](https://lingohub.com/) — 最多免费 3 位用户，开源始终免费
  * [localazy.com](https://localazy.com) - 1000 个源语言字符串、无限语言、无限贡献者、初创公司和开源交易免费
  * [Localeum](https://localeum.com) - 最多免费 1000 个字符串、1 个用户、无限语言、无限项目
  * [localizely.com](https://localizely.com/) — 开源免费
  * [Loco](https://localise.biz/) — 免费多达 2000 次翻译、无限翻译、10 种语言/项目、1000 种可翻译资产/项目
  * [oneskyapp.com](https://www.oneskyapp.com/) — 最多 5 位用户的限量免费版，开源免费
  * [POEditor](https://poeditor.com/) — 释放多达 1000 个字符串
  * [SimpleLocalize](https://simplelocalize.io/) - 免费多达 100 个翻译键、无限字符串、无限语言、启动交易
  * [Texterify](https://texterify.com/) - 单个用户免费
  * [transifex.com](https://www.transifex.com/) — 开源免费
  * [Translation.io](https://translation.io) - 免费开源
  * [webtranslateit.com](https://webtranslateit.com/) — 释放多达 500 个字符串
  * [weblate.org](https://weblate.org/) — 对于免费层的最多 10,000 个字符串源的 libre 项目和无限制的本地自托管，它是免费的.
  * [Free PO editor](https://pofile.net/free-po-editor) — 所有人免费


## Monitoring

  * [Pingmeter.com](https://pingmeter.com/)  - 5 个正常运行时间监视器，间隔 10 分钟. 监控 SSH、HTTP、HTTPS 和任何自定义 TCP 端口.
  * [amixr.io](https://amixr.io/)  - 具有出色的 Slack 集成、API 和 Terraform 的开发人员友好的警报和呼叫管理. 免费电话、短信、电报、Slack 和电子邮件套餐.
  * [appdynamics.com](https://www.appdynamics.com/) — 24 小时免费指标，应用程序性能管理代理仅限于一种 Java、一种 .NET、一种 PHP 和一种 Node.js
  * [appneta.com](https://www.appneta.com/) — 免费，数据保留 1 小时
  * [assertible.com](https://assertible.com)  — 自动化 API 测试和监控. 团队和个人的免费计划.
  * [blackfire.io](https://blackfire.io/)  — Blackfire 是 SaaS 交付的应用程序性能解决方案. 免费黑客计划（仅限 PHP）
  * [checklyhq.com](https://checklyhq.com)  - 面向开发人员的开源 E2E / 综合监控和深度 API 监控.  5 个用户和 50k+ 次检查运行的免费计划.
  * [circonus.com](https://www.circonus.com/) — 20 个指标免费
  * [cloudsploit.com](https://cloudsploit.com)  — AWS 安全和配置监控. 免费：无限制的按需扫描、无限制的用户、无限制的存储帐户. 订阅：自动扫描、API访问等.
  * [datadoghq.com](https://www.datadoghq.com/) — 最多 5 个节点免费
  * [deadmanssnitch.com](https://deadmanssnitch.com/)  — 监控 cron 作业.  1 免费告密者（监控），如果您推荐其他人注册，则更多
  * [economize.cloud](https://economize.cloud)  — Economize 通过组织、优化和报告云资源，帮助揭开云基础设施成本的神秘面纱. 每月在 Google Cloud Platform 上消费高达 5000 美元即可免费.
  * [elastic.co](https://www.elastic.co/solutions/apm)  — 为 JS 开发人员提供即时性能洞察. 免费提供 24 小时数据保留
  * [freeboard.io](https://freeboard.io/)  — 公共项目免费. 物联网 (IoT) 项目的仪表板
  * [freshworks.com](https://www.freshworks.com/website-monitoring/) — 以 1 分钟为间隔监控 50 个 URL，其中包含 10 个全球位置和 5 个免费公共状态页面
  * [gitential.com](https://gitential.com)  — 软件开发分析平台. 免费：无限的公共存储库，无限的用户，私人存储库的免费试用. 适用于企业的本地版本.
  * [Grafana Cloud](https://grafana.com/products/cloud/)  - Grafana Cloud 是一个可组合的可观察性平台，将指标和日志与 Grafana 集成. 免费：3 个用户、10 个仪表板、100 个警报、Prometheus 和 Graphite 中的指标存储（10,000 个系列，保留 14 天）、Loki 中的日志存储（50 GB 日志，保留 14 天）
  * [healthchecks.io](https://healthchecks.io)  — 监控您的 cron 作业和后台任务. 最多可免费检查 20 次.
  * [inspector.dev](https://www.inspector.dev) - 不到一分钟的完整实时监控仪表板，永久免费层.
  * [instrumentalapp.com](https://instrumentalapp.com) - 美观且易于使用的应用程序和服务器监控，免费提供多达 500 个指标和 3 小时的数据可见性
  * [keychest.net/speedtest](https://keychest.net/speedtest) - 针对 Digital Ocean 的独立速度测试和 TLS 握手延迟测试
  * [letsmonitor.org](https://letsmonitor.org) - SSL 监控，最多 5 台显示器免费
  * [loader.io](https://loader.io/) — 有限制的免费负载测试工具
  * [meercode.io](https://meercode.io/)  — Meercode 是用于 CI/CD 构建的终极监控仪表板. 免费用于开源和 1 个私有存储库.
  * [newrelic.com](https://www.newrelic.com) — New Relic observability platform built to help engineers create more perfect software. From monoliths to serverless, you can instrument everything, then analyze, troubleshoot, and optimize your entire software stack. Free tier offers 100GB/month of free data ingest, 1 free full access user, and unlimited free basic users.
  * [nixstats.com](https://nixstats.com) - Free for one server. E-Mail Notifications, public status page, 60 second interval and more.
  * [nodequery.com](https://nodequery.com/) — 免费的基本服务器监控多达 10 个服务器
  * [OnlineOrNot.com](https://onlineornot.com/)  - 10 个正常运行时间监视器，间隔为 5 分钟，1 个页面速度监视器，间隔为 12 小时. 通过 Slack 和电子邮件的免费警报.
  * [opsgenie.com](https://www.opsgenie.com/)  — 强大的警报和随叫随到管理，用于操作永远在线的服务. 最多可免费 5 个用户.
  * [paessler.com](https://www.paessler.com/)  — 强大的基础设施和网络监控解决方案，包括警报、强大的可视化功能和基本报告. 释放多达 100 个传感器.
  * [syagent.com](https://syagent.com/) — 非商业免费服务器监控服务、警报和指标.
  * [pagertree.com](https://pagertree.com/)  - 用于提醒和随叫随到管理的简单界面. 最多可免费 5 个用户.
  * [pingbreak.com](https://pingbreak.com/)  — 现代正常运行时间监控服务. 检查无限的 URL 并通过 Discord、Slack 或电子邮件获取停机通知.
  * [pingpong.one](https://pingpong.one/)  — 具有监控功能的高级状态页面平台. 免费套餐包括一个带有 SSL 子域的公共可自定义状态页面. 专业计划免费提供给开源项目和非营利组织.
  * [sematext.com](https://sematext.com/) — 免费提供 24 小时指标、无限数量的服务器、10 个自定义指标、500,000 个自定义指标数据点、无限制的仪表板、用户等.
  * [sitemonki.com](https://sitemonki.com/) — 网站、域名、Cron 和 SSL 监控，每个类别 5 个免费监控器
  * [skylight.io](https://www.skylight.io/) — 前 100,000 个请求免费（仅限 Rails）
  * [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — 性能监控 API，检查 Ping、DNS 等.
  * [stathat.com](https://www.stathat.com/) — 开始免费获得 10 项统计数据，没有过期
  * [statuscake.com](https://www.statuscake.com/) - 网站监控，无限制的免费测试
  * [statusgator.com](https://statusgator.com/) — Status page monitoring, 3 monitors free
  * [thousandeyes.com](https://www.thousandeyes.com/)  — 网络和用户体验监控. 主要网络服务的 3 个位置和 20 个数据源免费
  * [thundra.io/apm](https://www.thundra.io/apm)  — 应用程序监控和调试. 拥有每月最多 25 万次调用的免费套餐.
  * [uptimerobot.com](https://uptimerobot.com/) — 网站监控，50 台免费监控
  * [uptimetoolbox.com](https://uptimetoolbox.com/) — 免费监控 5 个网站，60 秒间隔，公共状态页面.
  * [zenduty.com](https://www.zenduty.com/)  — 面向网络运营、站点可靠性工程和 DevOps 团队的端到端事件管理、警报、待命管理和响应编排平台. 最多 5 个用户免费.
  * [asayer.io](https://asayer.io/pricing.html)  — openreplay 的托管版本，一个开源会话重放（替代 FullStory 和 LogRocket）. 每月 1000 次免费会话，保留 14 天
  * [lean20.com](https://lean20.com/product/status/)  - 事件报告的公共状态页面.  100% 免费.
  * [instatus.com](https://instatus.com)  - 在 10 秒内获得漂亮的状态页面. 无限订阅和无限团队永远免费.


## Crash and Exception Handling

  * [CatchJS.com](https://catchjs.com/)  - 带有屏幕截图和点击轨迹的 JavaScript 错误跟踪. 开源项目免费.
  * [bugsnag.com](https://www.bugsnag.com/) — 初次试用后每月最多 2,000 个错误免费
  * [exceptionless](https://exceptionless.com)  — 实时错误、功能、日志报告等. 每月 3k 个事件/1 个用户免费. 开源且易于自托管，可无限使用.
  * [GlitchTip](https://glitchtip.com/)  — 简单的开源错误跟踪. 与开源 Sentry SDK 兼容. 每月免费举办 1000 场活动，或可以无限制地自行举办
  * [honeybadger.io](https://www.honeybadger.io)  - 异常、正常运行时间和 cron 监控. 小型团队和开源项目免费（每月 12,000 次错误）.
  * [rollbar.com](https://rollbar.com/) — 异常和错误监控、每月 5,000 次错误的免费计划、无限用户、30 天保留期
  * [sentry.io](https://sentry.io/)  — Sentry 实时跟踪应用程序异常，有一个小的免费计划. 每月 5000 次错误/1 位用户免费，如果自托管则无限制使用


## Search

  * [algolia.com](https://www.algolia.com/)  — 托管搜索即输入（即时）. 免费黑客计划多达 10,000 个文档和 100,000 次操作. 更大的免费计划可用于社区/开源项目
  * [bonsai.io](https://bonsai.io/) — 免费 1 GB 内存和 1 GB 存储空间
  * [searchly.com](http://www.searchly.com/) — 免费 2 个索引和 20 MB 存储空间
  * [pagedart.com](https://pagedart.com/)  - AI 搜索即服务，免费层包括 1000 个文档、50000 次搜索. 对于有价值的项目，可以使用更大的免费层.


## Email

  * [10minutemail](https://10minutemail.com) - 用于测试的免费临时电子邮件.
  * [AnonAddy](https://anonaddy.com) - 开源匿名邮件转发，免费创建无限制的邮件别名
  * [Antideo](https://www.antideo.com)  — 每小时 10 个 API 请求，用于免费层中的电子邮件验证、IP 和电话号码验证. 无需信用卡.
  * [biz.mail.ru](https://biz.mail.ru/) — 5,000 个邮箱，每个带有 DNS 托管的自定义域 25 GB
  * [Bump](https://bump.email/) - 免费 10 个 Bump 电子邮件地址，1 个自定义域
  * [Burnermail](https://burnermail.io/) – 免费 5 个 Burner 电子邮件地址、1 个邮箱、7 天邮箱历史记录
  * [Buttondown](https://buttondown.email/)  — 通讯服务. 多达 1,000 名订阅者免费
  * [CloudMailin](https://www.cloudmailin.com/) - 通过 HTTP POST 和事务性出站接收电子邮件 - 每月 10,000 封免费电子邮件
  * [cloudmersive.com](https://www.cloudmersive.com/email-verification-api) — 面向开发人员的电子邮件验证和验证 API，每月 2,000 个免费 API 请求
  * [Contact.do](https://contact.do/) - 链接中的联系表（联系表有点） - 完全免费！
  * [debugmail.io](https://debugmail.io/) — 易于使用的开发人员测试邮件服务器
  * [elasticemail.com](https://elasticemail.com)  — 每天 100 封免费电子邮件. 通过 API 以 0.09 美元的价格发送 1,000 封电子邮件（即付即用）.
  * [EmailOctopus](https://emailoctopus.com) - 每月最多 2,500 名订阅者和 10,000 封电子邮件
  * [Eva](https://eva.pingutil.com)  — 每天使用 REST API 免费验证 500 万封电子邮件. 无需注册.
  * [fakermail.com](https://fakermail.com/) — 免费的临时电子邮件，用于测试存储的最后 100 个电子邮件帐户.
  * [forwardemail.net](https://forwardemail.net)  — 自定义域的免费电子邮件转发. 使用您的域名创建和转发无限数量的电子邮件地址（**注意**：如果您使用 .casa、.cf、.click、.email、.fit、.ga、.gdn、.gq、 .loan、.london、.men、.ml、.pl、.rest、.ru、.tk、.top、.work TLD（由于垃圾邮件）
  * [ImprovMX](https://improvmx.com) – 免费电子邮件转发
  * [inboxkitten.com](https://inboxkitten.com/)  - 免费的临时/一次性电子邮件收件箱，最多可在 3 天内自动删除电子邮件. 开源，可以自托管.
  * [inumbo.com](http://inumbo.com/) — 基于 SMTP 的垃圾邮件过滤器，10 个用户免费
  * [kickbox.io](https://kickbox.io/) — 验证 100 封免费电子邮件，实时 API 可用
  * [mail.tm](https://mail.tm)  — 具有用户友好界面的一次性电子邮件. 无需注册.
  * [mailazy.com](https://mailazy.com/)  — Mailazy 是您需要的唯一简单的交易电子邮件服务.  15,000 封电子邮件/月永久免费（500 封电子邮件/天发送限制）.
  * [mail-tester.com](https://www.mail-tester.com) — 测试邮箱的dns/spf/dkim/dmarc设置是否正确，20个免费/月
  * [dkimvalidator.com](https://dkimvalidator.com/) - 测试邮箱的 dns/spf/dkim/dmarc 设置是否正确，roundsphere.com 免费服务
  * [mailboxlayer.com](https://mailboxlayer.com/)  — 面向开发人员的电子邮件验证和验证 JSON API.  1,000 个免费 API 请求/月
  * [mailcatcher.me](https://mailcatcher.me/) — 捕获邮件并通过 Web 界面提供服务
  * [mailchimp.com](https://mailchimp.com/) — 2,000 名订阅者和 12,000 封电子邮件/月免费
  * [MailerLite.com](https://www.mailerlite.com) — 1,000 名订阅者/月，12,000 封电子邮件/月免费
  * [mailinator.com](https://www.mailinator.com/) — 免费、公共的电子邮件系统，您可以在其中使用您想要的任何收件箱
  * [mailjet.com](https://www.mailjet.com/) — 每月免费 6,000 封电子邮件（每日发送限制为 200 封电子邮件）
  * [mailkitchen](https://www.mailkitchen.com/) — 终身免费，无需承诺，每月 10,000 封电子邮件，每天 1,000 封电子邮件
  * [Mailnesia](https://mailnesia.com) - 免费的临时/一次性电子邮件，自动访问注册链接.
  * [mailsac.com](https://mailsac.com) - 用于临时电子邮件测试的免费 API、免费公共电子邮件托管、出站捕获、电子邮件到 slack/websocket/webhook（每月 1,500 个 API 限制）
  * [Mailtie.com](https://mailtie.com/)  - 您的域的免费电子邮件转发. 无需注册. 永远免费.
  * [mailtrap.io](https://mailtrap.io/) — 用于开发的假 SMTP 服务器，免费计划，1 个收件箱，50 条消息，无团队成员，2 封电子邮件/秒，无转发规则
  * [mailvalidator.io](https://mailvalidator.io/) - 每月免费验证 300 封电子邮件，提供批量处理的实时 API
  * [mail7.io](https://www.mail7.io/)  — 面向 QA 开发人员的免费临时电子邮件地址. 使用 Web 界面或 API 立即创建电子邮件地址
  * [mohmal.com](https://www.mohmal.com/en) — 一次性临时邮箱
  * [moosend.com](https://moosend.com/)  — 邮件列表管理服务. 为初创公司提供 6 个月的免费帐户
  * [Outlook.com](https://outlook.live.com/owa/) - 免费的个人电子邮件和日历
  * [Parsio.io](https://parsio.io) - 免费电子邮件解析器（转发电子邮件，提取数据，将其发送到您的服务器）
  * [pepipost.com](https://pepipost.com) — 第一个月免费发送 30k 封电子邮件，然后每天免费发送 100 封电子邮件
  * [phplist.com](https://phplist.com/) — 托管版本允许每月 300 封电子邮件免费
  * [postmarkapp.com](https://postmarkapp.com/) - 每月 100 封免费电子邮件，无限制的 DMARC 每周摘要
  * [QuickEmailVerification](https://quickemailverification.com) — 每天免费验证 100 封电子邮件以及其他免费 API，如 DEA 检测器、DNS 查找、SPF 检测器等.
  * [Sender](https://www.sender.net) 每月最多 15 000 封电子邮件 - 最多 2 500 名订阅者
  * [sendgrid.com](https://sendgrid.com/) — 每天 100 封电子邮件和 2,000 个免费联系人
  * [sendinblue.com](https://www.sendinblue.com/) — 每月免费 9,000 封电子邮件
  * [sendpulse.com](https://sendpulse.com) — 每小时免费 50 封电子邮件，每月免费前 12,000 封电子邮件
  * [socketlabs.com](https://www.socketlabs.com) - 第一个月免费发送 40k 封电子邮件，然后每月免费发送 2000 封电子邮件
  * [sparkpost.com](https://www.sparkpost.com/) — 每月前 500 封电子邮件免费
  * [Substack](https://substack.com)  — 无限制的免费通讯服务. 当您收费时开始付款.
  * [Tempmailo](https://tempmailo.com/)  - 无限的免费临时电子邮件地址. 两天后自动过期.
  * [HotTempMail](https://hottempmail.com/)  - 无限的免费临时电子邮件或一次性临时电子邮件地址. 一天后自动过期.
  * [temp-mail.io](https://temp-mail.io) — 免费一次性临时电子邮件服务，一次发送多封电子邮件并转发
  * [temp-mail.org](https://temp-mail.org) — 具有 REST API 的临时、安全、匿名、免费、一次性电子邮件地址，每天免费从其一次性邮箱中获取 100 封电子邮件.
  * [testmail.app](https://testmail.app/)  - 使用无限邮箱和 GraphQL API 自动化端到端电子邮件测试.  100 封电子邮件/月永久免费，开源无限制.
  * [tinyletter.com](https://tinyletter.com/) — 5,000 名订阅者/月免费
  * [trashmail.com](https://www.trashmail.com) - 具有转发和自动地址过期功能的免费一次性电子邮件地址
  * [Validator.Pizza](https://www.validator.pizza/) — 用于检测一次性电子邮件的免费 API
  * [Verifalia](https://verifalia.com/email-verification-api)  — 带有邮箱确认和一次性电子邮件地址检测器的实时电子邮件验证 API； 每天 25 次免费电子邮件验证.
  * [verimail.io](https://verimail.io/)  — 批量和 API 电子邮件验证服务. 每月 100 次免费验证
  * [Yandex.Connect](https://connect.yandex.com/pdd/) — 最多 1,000 个用户的免费电子邮件和 DNS 托管
  * [yopmail.fr](http://www.yopmail.fr/en/) — 一次性电子邮件地址
  * [Zoho](https://www.zoho.com)  — 最初是电子邮件提供商，但现在提供一套服务，其中一些有免费计划. 有免费计划的服务列表：
     - [Email](https://zoho.com/mail) Free for 5 users. 5GB/user & 25 MB attachment limit, 1 domain.
     - [Sprints](https://zoho.com/sprints) 5 个用户、5 个项目和 500MB 存储空间免费.
     - [Docs](https://zoho.com/docs)  — 5 个用户免费，上传限制为 1 GB，存储空间为 5 GB.  Zoho Office Suite (Writer,Sheets &amp; Show) 与它捆绑在一起.
     - [Projects](https://zoho.com/projects)  — 3 个用户、2 个项目和 10 MB 附件限制免费. 同样的计划适用于 [Bugtracker](https://zoho.com/bugtracker).
     - [Connect](https://zoho.com/connect) — 25 名用户的免费团队协作，包括 3 个组、3 个自定义应用程序、3 个板、3 个手册、10 个集成以及渠道、活动和论坛.
     - [Meeting](https://zoho.com/meeting) — 最多 3 位会议参与者和 10 位网络研讨会参与者的会议.
     - [Vault](https://zoho.com/vault) — 个人免费密码管理.
     - [Showtime](https://zoho.com/showtime) — 另一个用于培训最多 5 名与会者的远程会议的会议软件.
     - [Notebook](https://zoho.com/notebook) — Evernote 的免费替代品.
     - [Wiki](https://zoho.com/wiki) — 3 位用户免费，拥有 50 MB 存储空间、无限页面、zip 备份、RSS 和 Atom 提要、访问控制和可自定义的 CSS.
     - [Subscriptions](https://zoho.com/subscriptions)  — 为 20 个客户/订阅和 1 个用户免费提供定期计费管理，所有支付托管均由 Zoho 自己完成. 存储最后 40 个订阅指标
     - [Checkout](https://zoho.com/checkout) — 具有 3 页和最多 50 笔付款的产品计费管理.
     - [Desk](https://zoho.com/desk)  — 具有 3 个代理和私人知识库、电子邮件票证的客户支持管理. 与 [Assist](https://zoho.com/assist) 1 名远程技术人员和 5 台无人值守计算机.
     - [Cliq](https://zoho.com/cliq) — 具有 100 GB 存储空间、无限用户、每个频道 100 个用户和 SSO 的团队聊天软件.
     - [Campaigns](https://zoho.com/campaigns)
     - [Forms](https://zoho.com/forms)
     - [Sign](https:/zoho.com/sign)
     - [Surveys](https://zoho.com/surveys)
     - [Bookings](https://zoho.com/bookings)
     - [Analytics](https://zoho.com/analytics)
  * [SimpleLogin](https://simplelogin.io/)  – 开源、自托管的电子邮件别名/转发解决方案. 免费 5 个别名，无限带宽，无限回复/发送. 教育人员（学生、研究员等）免费.
  * [EmailJS](https://www.emailjs.com/) – 这不是一个完整的电子邮件服务器，这只是电子邮件客户端，您可以使用它直接从客户端发送电子邮件而不会暴露您的凭据，免费层有：200 个每月请求、2 个电子邮件模板、请求高达 50Kb、联系人有限历史.



## Font

  * [dafont](https://www.dafont.com/) - 本网站上显示的字体是其作者的财产，可以是免费软件、共享软件、演示版或公共领域.
  * [Everything Fonts](https://everythingfonts.com/)  - 提供多种工具；  @font-face、单位转换器、字体提示器和字体提交器.
  * [Font Squirrel](https://www.fontsquirrel.com/)  - 获得商业作品许可的免费软件字体. 手工选择这些字体并以易于使用的格式呈现它们.
  * [Google Fonts](https://fonts.google.com/) - 许多免费字体可以通过下载或指向 Google CDN 的链接轻松快速地安装在网站中.
  * [FontGet](https://www.fontget.com/) - 有多种字体可供下载，并用标签整齐地排序.
  * [Fontshare](https://www.fontshare.com/)  - 是一项免费的字体服务. 这是一个不断增长的专业级字体集合，可 100% 免费供个人和商业使用.


## Forms

  * [99inbound.com](https://www.99inbound.com/)  - 建立表格并在线分享. 每次提交都会收到一封电子邮件或 Slack 消息. 免费计划有 2 个表格，每月 100 个条目，基本电子邮件和 Slack.
  * [Form.taxi](https://form.taxi/)  — HTML 表单提交的端点. 通过通知、垃圾邮件拦截器和符合 GDPR 的数据处理. 基本使用的免费计划.
  * [Formcake.com](https://formcake.com)  - 开发人员的表单后端，免费计划允许无限表单，100 次提交，Zapier 集成. 不需要库或依赖项.
  * [Formcarry.com](https://formcarry.com) - HTTP POST 表单端点，免费计划允许每月 100 次提交.
  * [formingo.co](https://www.formingo.co/)- Easy HTML forms for static websites, get started for free without registering an account. Free plan allows 500 submissions per month, customizable reply-to email address.
  * [formlets.com](https://formlets.com/) — 在线表格、无限单页表格/月、100 次提交/月、电子邮件通知.
  * [formspark.io](https://formspark.io/) - 表格到电子邮件服务，免费计划允许无限表格，每月 250 次提交，由客户协助团队提供支持.
  * [Formspree.io](https://formspree.io/)  — 使用 HTTP POST 请求发送电子邮件. 免费等级限制为每月每个表单 50 次提交.
  * [Formsubmit.co](https://formsubmit.co/)  — HTML 表单的简单表单端点. 永远免费. 无需注册.
  * [getform.io](https://getform.io/) - 面向设计师和开发人员的表单后端平台，1 个表单，50 个提交，单个文件上传，100MB 文件存储.
  * [HeroTofu.com](https://herotofu.com/)  - 具有机器人检测和加密存档的表单后端. 通过 UI 将提交的内容转发到电子邮件、Slack 或 Zapier. 使用您自己的前端，无需服务器代码. 免费计划提供无限的表格和每月 100 次提交.
  * [Kwes.io](https://kwes.io/) - Feature rich form endpoint. Works great with static sites. Free plan includes up 1 website with up to 50 submissions per month.
  * [Qualtrics Survey](https://qualtrics.com/free-account)  — 使用这个一流的工具创建专业的表格和调查.  50 多个专家设计的调查模板. 免费帐户限制为 1 个活动调查、100 个回复/调查和 8 个回复类型.
  * [Pageclip](https://pageclip.co/) - 免费计划允许一个站点、一个表单、每月 1,000 次提交.
  * [smartforms.dev](https://smartforms.dev/) - 强大且简单的网站表单后端，永久免费计划允许每月 50 次提交、250MB 文件存储、Zapier 集成、CSV/JSON 导出、自定义重定向、自定义响应页面、Telegram 和 Slack 机器人、单个电子邮件通知.
  * [staticforms.xyz](https://www.staticforms.xyz/)  - 无需任何服务器端代码即可轻松集成 HTML 表单. 用户提交表单后，一封包含表单内容的电子邮件将发送到您的注册地址.
  * [Typeform.com](https://www.typeform.com/)  — 在网站上包含设计精美的表格. 免费计划只允许每个表单 10 个字段和每月 100 个回复.
  * [WaiverStevie.com](https://waiverstevie.com)  - 带有 REST API 的电子签名平台. 使用网络钩子接收通知. 免费计划水印签名文件，但允许无限的信封+签名.
  * [Wufoo](https://www.wufoo.com/)  - 在网站上使用的快速表格. 免费计划每月限制为 100 次提交.
  * [Web3Forms](https://web3forms.com)  - 静态和 JAMStack 网站的联系表单，无需编写后端代码. 免费计划允许每月无限表格、无限域名和 250 次提交.


## CDN and Protection

  * [Arvan Cloud](https://arvancloud.com/)  — 提供云相关服务（CDN、Cloud DNS、PaaS、Security 等）. 免费计划优惠：
     - 带有免费 SSL 的 CDN.  50 GB 流量 + 100 万个 HTTP(S) 请求.
    - 无限域的免费云 DNS.
    - 具有基本 DDoS 保护 + 5 条防火墙规则的免费云安全.
    - 具有 10 GB 存储空间 + 50 GB 流量的免费 VoD（视频点播）平台.
  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) — 用于 bootstrap、bootswatch 和 fontawesome.io 的 CDN
  * [cdnjs.com](https://cdnjs.com/)  - 简单的. 快速地. 可靠的. 最好的内容交付.  cdnjs 是一种免费的开源 CDN 服务，受超过 11% 的网站信任，由 Cloudflare 提供支持.
  * [Cloudflare](https://www.cloudflare.com/)
    * CDN 和免费 SSL
    * 无限数量的域的免费 DNS
    * 防火墙规则和页面规则
    * 分析
    * [TryCloudflare](https://developers.cloudflare.com/argo-tunnel/trycloudflare) — 通过 Argo Tunnel 向公众公开本地 HTTP 服务器.
    * [Cloudflare Pages](https://pages.cloudflare.com/)  — 免费网络托管（JAMstack 平台），供前端开发人员协作和部署网站. 一次构建 1 个，每月 500 个构建，无限站点，无限请求，无限带宽.
    * [Cloudflare Workers](https://workers.cloudflare.com/)  - 在 Cloudflare 的全球网络上免费部署无服务器代码. 每天 100,000 个免费请求，使用 workers.dev 子域.
  * [Combinatronics](https://combinatronics.com/)  - 将您的 Github 托管资产（图像、CSS、JS 等）转换为 CDN 资产. 甚至可以渲染 HTML 文件，对于 [example from this repo](https://combinatronics.com/ripienaar/free-for-dev/master/index.html) . 类似于 rawgit.com 和 raw.githack.com.
  * [ddos-guard.net](https://ddos-guard.net/store/web) — 免费 CDN、DDoS 保护和 SSL 证书
  * [developers.google.com](https://developers.google.com/speed/libraries/) — Google Hosted Libraries 是最流行的开源 JavaScript 库的内容分发网络
  * [GraphCDN](https://graphcdn.io/)  - 扩展、检查和保护您的 GraphQL API. 每月 500 万次免费请求.
  * [jare.io](http://www.jare.io)  — 用于图像的 CDN. 使用 AWS CloudFront
  * [jsdelivr.com](https://www.jsdelivr.com/)  — 一个免费、快速、可靠的开源 CDN. 支持 npm、GitHub、WordPress、Deno 等.
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — Microsoft Ajax CDN 托管流行的第三方 JavaScript 库，例如 jQuery，并使您能够轻松地将它们添加到您的 Web 应用程序中
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) — 免费的 DDoS 保护和 SSL 证书
  * [PageCDN.com](https://pagecdn.com/) - 为所有人提供免费的公共 CDN，为开源/非营利组织提供免费的私有 CDN.
  * [Skypack](https://www.skypack.dev/)  — 100% 原生 ES 模块 JavaScript CDN. 每个域每月 100 万次请求免费.
  * [raw.githack.com](https://raw.githack.com/) — **rawgit.com** 的现代替代品，它使用 Cloudflare 简单地托管文件
  * [section.io](https://www.section.io/)  — 一种启动和管理完整 Varnish Cache 解决方案的简单方法. 据说对一个站点永久免费
  * [speeder.io](https://speeder.io/)  — 使用 KeyCDN. 自动图像优化和免费 CDN 提升. 免费且不需要任何服务器更改
  * [statically.io](https://statically.io/) — 用于 Git 存储库（GitHub、GitLab、Bitbucket）、WordPress 相关资产和图像的 CDN
  * [toranproxy.com](https://toranproxy.com/)  — Packagist 和 GitHub 的代理. 永不失败的CD. 免费供个人使用，1 个开发人员，不支持
  * [unpkg.com](https://unpkg.com/) — 用于 npm 上所有内容的 CDN
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — 免费的 DDoS 保护


## PaaS

  * [anvil.works](https://anvil.works)  - 只用 Python 开发 Web 应用程序. 具有无限应用程序的免费层.
  * [appharbor.com](https://appharbor.com/) — 提供 1 个免费工作者的 .Net PaaS
  * [configure.it](https://www.configure.it/) — 移动应用开发平台，2个项目免费，功能有限但没有资源限制
  * [codenameone.com](https://www.codenameone.com/)  — 面向 Java/Kotlin 开发人员的开源、跨平台、移动应用程序开发工具链. 免费用于商业用途，项目数量不限
  * [Deta](https://www.deta.sh)  – 免费部署无限数量的 Node.js 和 Python 应用程序. 包括免费数据库、身份验证和电子邮件.
  * [dronahq.com](https://www.dronahq.com/)  — 无代码应用开发平台，企业可视化开发应用，与现有系统集成，快速构建内部应用、流程和表单. 免费计划提供 200 个任务/月、无限草稿应用程序和 1 个已发布应用程序
  * [encore.dev](https://encore.dev/)  — 使用静态分析提供自动基础设施、无样板代码等的后端框架. 包括用于业余爱好项目的免费云托管.
  * [gigalixir.com](https://gigalixir.com/) - Gigalixir 为 Elixir/Phoenix 应用程序提供 1 个永不休眠的免费实例，以及限制为 2 个连接、10、000 行且无备份的免费层 PostgreSQL 数据库.
  * [glitch.com](https://glitch.com/)  — 免费的公共托管，具有代码共享和实时协作等功能. 免费计划有 1000 小时/月的限制.
  * [heroku.com](https://www.heroku.com/) — 在云中托管您的应用程序，单进程应用程序免费
  * [Krucible](https://usekrucible.com)  — Krucible 是一个用于创建 Kubernetes 集群以进行测试和开发的平台. 免费层帐户每月有 25 个集群小时.
  * [Mendix](https://www.mendix.com/)  — 面向企业的快速应用程序开发、无限数量的免费沙盒环境支持无限用户、每个应用程序 0.5 GB 存储空间和 1 GB RAM. 免费套餐中也允许使用 Studio 和 Studio Pro IDE.
  * [m3o.com](https://m3o.com)  - API 服务开发的云平台.  M3O 是一个完全托管的微即服务产品，专注于云中的 Go 微服务开发. 免费套餐足以运行 5 个服务并与他人协作.
  * [opeNode](https://openode.io)  — 用于开源项目的免费 Node.js 托管.  100 GB 带宽/月，100 MB 内存和 1000 MB 存储. 使用 CLI 或现有 Git 存储库进行部署.
  * [outsystems.com](https://www.outsystems.com/) — 用于本地或云的企业 Web 开发 PaaS，免费的“个人环境”产品允许无限代码和高达 1 GB 的数据库
  * [pipedream.com](https://pipedream.com)  - 为开发人员构建的集成平台. 基于任何触发器开发任何工作流程. 工作流是可以运行的代码 [for free](https://docs.pipedream.com/pricing/) . 无需管理服务器或云资源.
  * [pythonanywhere.com](https://www.pythonanywhere.com/)  — 云 Python 应用托管. 初学者帐户是免费的，1 个 Python Web 应用程序位于 your-username.pythonanywhere.com 域，512 MB 私有文件存储空间，一个 MySQL 数据库
  * [scn.sap.com](https://scn.sap.com/docs/DOC-56411)  — SAP 的内存平台即服务产品. 免费的开发者帐户包含 1 GB 结构化数据、1 GB 非结构化数据和 1 GB Git 数据，并允许您运行 HTML5、Java 和 HANA XS 应用程序
  * [staroid.com](https://staroid.com)  - 旨在为开源开发人员提供资金的托管 Kubernetes 命名空间服务. 释放 8 个 CPU 和 16GB 的 RAM 命名空间，用于测试公共存储库的分支和拉取请求. 免费测试命名空间每 30 分钟关闭一次. 最多 2 个并发测试命名空间.
  * [SUSE Developer Program](https://developer.suse.com) — Experience cloud native productivity for free. Get hands-on with the SUSE Cloud Application Platform with your own Developer Sandbox. 1 Free Application. Free subdomain provided along with API for CLI. Storage & Memory Quota of 1 GB.
  * [fly.io](https://fly.io/)  - Fly 是一个适用于需要在全球范围内运行的应用程序的平台. 它在靠近用户的地方运行您的代码，并在您的应用程序最繁忙的城市扩展计算. 编写您的代码，将其打包到 Docker 映像中，将其部署到 Fly 的平台，然后让这些工作完成所有工作以保持您的应用程序快速运行. 副项目免费，每月 10 美元的服务信用自动适用于任何付费服务. 如果您运行非常小的虚拟机，积分将大有帮助.
  * [Divio](https://www.divio.com/)  - 仅使用 Docker 管理云应用程序部署的平台. 可免费订阅开发项目.
  * [Koyeb](https://www.koyeb.com)  - Koyeb 是一个开发人员友好的无服务器平台，用于在全球部署应用程序. 通过基于 git 的部署、本机自动缩放、全球边缘网络以及内置服务网格和发现，无缝运行 Docker 容器、Web 应用程序和 API.  Koyeb 提供两种 nano 服务，以通过其永久免费层运行您的应用程序，并使用免费资源赞助开源项目.
  * [Railway](https://railway.app) - Railway is an infrastructure platform where you can provision infrastructure, develop with that infrastructure locally, and then deploy to the cloud. 1GB Disk, 512 MB RAM, limited to $5 of usage monthly available for free.
  * [Napkin](https://www.napkin.io/) - 具有 1Gb 内存、15 秒默认超时和 1,000,000 次免费 API 调用/月的 FaaS.


## BaaS

  * [ably.com](https://www.ably.com)  - 用于实时消息传递、推送通知和事件驱动 API 创建的 API. 免费计划有 300 万条消息/月，100 个并发连接，100 个并发通道.
  * [back4app.com](https://www.back4app.com) - Back4App 是一个基于 Parse 平台的易于使用、灵活和可扩展的后端.
  * [backendless.com](https://backendless.com/) — Mobile 和 Web Baas，免费提供 1 GB 文件存储，推送通知 50000/月，表中的 1000 个数据对象.
  * [BMC Developer Program](https://developers.bmc.com/site/global/bmc_helix_platform/program/overview/index.gsp)  — BMC 开发人员计划提供文档和资源，用于为您的企业构建和部署数字创新. 访问全面的个人沙箱，其中包括平台、SDK 和可用于构建和定制应用程序的组件库.
  * [darklang.com](https://darklang.com/)  - 托管语言与编辑器和基础设施相结合. 测试期间免费，测试后计划提供慷慨的免费套餐.
  * [Firebase](https://firebase.com)  — Firebase 可帮助您构建和运行成功的应用. 免费 Spark 计划提供身份验证、托管、Firebase ML、实时数据库、云存储、Testlab.  A/B 测试、分析、应用分发、应用索引、云消息传递 (FCM)、Crashlytics、动态链接、应用内消息传递、性能监控、预测和远程配置始终免费.
  * [Flutter Flow](https://flutterflow.io)  — 无需编写任何代码即可构建您的 Flutter App UI. 还具有 Firebase 集成. 免费计划包括对 UI Builder 和免费模板的完全访问.
  * [getstream.io](https://getstream.io/) — 在几小时而不是几周内构建可扩展的新闻源、活动流、聊天和消息传递
  * [hasura.io](https://hasura.io/)  — Hasura 将您现有的数据库扩展到任何托管位置，并提供即时 GraphQL API，可安全访问 Web、移动和数据集成工作负载. 每月 1GB 的数据传输免费.
  * [iron.io](https://www.iron.io/) — 异步任务处理（如 AWS Lambda），提供免费套餐和 1 个月的免费试用
  * [netlicensing.io](https://netlicensing.io)  - 经济高效且集成的许可即服务 (LaaS) 解决方案，适用于从桌面到物联网和 SaaS 的任何平台上的软件. 学生期间*免费*的基本计划.
  * [onesignal.com](https://onesignal.com/) — 无限制的免费推送通知
  * [paraio.com](https://paraio.com)  — 具有灵活身份验证、全文搜索和缓存的后端服务 API.  1 个应用免费，1GB 应用数据.
  * [posthook.io](https://posthook.io/)  — 作业调度服务. 允许您安排特定时间的请求. 每月 500 个预定请求免费.
  * [progress.com](https://www.progress.com/kinvey)  — 移动后端，入门计划具有无限请求/秒，具有 1 GB 数据存储空间. 企业应用支持
  * [pubnub.com](https://www.pubnub.com/) — 每月最多 100 万条消息和 100 个日常设备的免费推送通知
  * [pushbots.com](https://pushbots.com/)  — 推送通知服务. 每月最多 150 万次免费推送
  * [pushcrew.com](https://pushcrew.com/)  — 推送通知服务. 最多 2000 个订阅者的无限通知
  * [pusher.com](https://pusher.com/beams)  — 为 2000 名每月活跃用户提供免费、无限制的推送通知. 适用于 iOS 和 Android 设备的单一 API.
  * [pushtechnology.com](https://www.pushtechnology.com/)  — 适用于浏览器、智能手机和所有人的实时消息传递.  100 个并发连接. 每月免费 10 GB 数据
  * [quickblox.com](https://quickblox.com/) — 用于即时消息、视频和语音通话以及推送通知的通信后端
  * [restspace.io](https://restspace.io/) - 为服务器配置身份验证、数据、文件、电子邮件 API、模板等服务，然后组合成管道并转换数据.
  * [Salesforce Developer Program](https://developer.salesforce.com/signup)  — 使用拖放工具快速构建应用程序. 通过点击自定义您的数据模型. 使用 Apex 代码走得更远. 使用强大的 API 与任何东西集成. 获得企业级安全保护. 通过点击或任何领先的 Web 框架自定义 UI. 免费的开发人员计划可以访问完整的照明平台.
  * [ServiceNow Developer Program](https://developer.servicenow.com/)  — 快速构建、测试和部署使您的组织更好地工作的应用程序. 免费实例和访问早期预览.
  * [simperium.com](https://simperium.com/)  — 立即自动将数据移动到任何地方，多平台，无限制地发送和存储结构化数据，最大.  2,500 名用户/月
  * [stackstorm.com](https://stackstorm.com/) — 应用程序、服务和工作流的事件驱动自动化，无流量、访问控制、LDAP、...
  * [streamdata.io](https://streamdata.io/)  — 将任何 REST API 转换为事件驱动的流 API. 免费计划最多 100 万条消息和 10 个并发连接.
  * [Supabase](https://supabase.io)  — 构建后端的开源 Firebase 替代方案. 免费计划提供身份验证、实时数据库和对象存储.
  * [tyk.io](https://tyk.io/)  — 具有身份验证、配额、监控和分析功能的 API 管理. 免费云服务
  * [zapier.com](https://zapier.com/)  — 连接您使用的应用程序，以自动执行任务.  5 zaps，每 15 分钟和 100 个任务/月
  * [LeanCloud](https://leancloud.app/)  — 移动后端.  1GB 数据存储、256MB 实例、3K API 请求/天、10K 推送/天是免费的.  （API 与 Parse Platform 非常相似）
  * [Liteflow](https://liteflow.com/) - 旨在帮助您专注于应用程序的真正价值的低代码开发工具包.


## Web Hosting

  * [Alwaysdata](https://www.alwaysdata.com/)  — 100 MB 免费虚拟主机，支持 MySQL、PostgreSQL、CouchDB、MongoDB、PHP、Python、Ruby、Node.js、Elixir、Java、Deno、自定义网络服务器，可通过 FTP、WebDAV 和 SSH 访问； 包括邮箱、邮件列表和应用安装程序.
  * [Awardspace.com](https://www.awardspace.com) — 免费虚拟主机 + 免费短域名、PHP、MySQL、应用安装程序、电子邮件发送和无广告.
  * [Bubble](https://bubble.io/) — 无需代码即可构建 Web 和移动应用程序的可视化编程，免费使用 Bubble 品牌.
  * [cloudno.de](https://cloudno.de/) — Node.js 应用程序的免费云托管.
  * [Deploy Now](https://deploynow.space)  — 更智能地部署. 部署更快. 立即部署.  - 从您的 GitHub 存储库免费部署最多 3 个 Web 项目.
  * [Drive To Web](https://drv.tw)  — 从 Google Drive 和 OneDrive 直接托管到网络. 仅限静态网站. 永远免费. 每个 Google/Microsoft 帐户一个站点.
  * [Endless Hosting](https://theendlessweb.com/)  — 30​​0 MB 存储空间、免费 SSL、PHP、MySQL、FTP、免费子域、电子邮件、DNS、漂亮的面板 UI. 最好的之一！
  * [Fenix Web Server](https://preview.fenixwebserver.com)  - 用于在本地托管站点并公开（实时）共享它们的开发人员桌面应用程序. 使用其漂亮的用户界面、API 和/或 CLI，随心所欲地工作.
  * [Free Hosting](http://freehostingnoads.net/) — 使用 PHP 5、Perl、CGI、MySQL、FTP、文件管理器、POP 电子邮件、免费子域、免费域托管、DNS 区域编辑器、网站统计、免费在线支持和许多其他不提供的功能的免费托管其他免费主机.
  * [Freehostia](https://www.freehostia.com)  — FreeHostia 提供免费托管服务，包括. 业界最佳的控制面板和一键安装 50 多个免费应用程序. 即时设置. 没有强制广告.
  * [heliohost.org](https://www.heliohost.org) — 社区为每个人提供免费托管.
  * [hostman.com](https://hostman.com) — 从您的 GitHub 存储库免费部署最多 3 个静态站点.
  * [neocities.org](https://neocities.org) — 静态、1 GB 免费存储空间和 200 GB 带宽.
  * [netlify.com](https://www.netlify.com/) — 免费构建、部署和托管静态站点/应用程序，100 GB 数据和 100 GB/月带宽.
  * [commons.host](https://commons.host/)  - 静态网络托管和 CDN.100% 免费和开源软件 (FOSS). 使用商业上可持续的软件即服务 (SaaS) 来资助研发.
  * [pantheon.io](https://pantheon.io/)  — Drupal 和 WordPress 托管、自动化 DevOps 和可扩展的基础架构. 开发商和代理商免费
  * [readthedocs.org](https://readthedocs.org/) — 带有版本控制、PDF 生成等功能的免费文档托管
  * [render.com](https://render.com) — 用于构建和运行所有应用程序和 Web 应用程序免费 SSL、全球 CDN、私有网络和 Git 自动部署的统一平台，静态网页免费.
  * [sourceforge.net](https://sourceforge.net/) — 免费查找、创建和发布开源软件
  * [Stormkit](https://stormkit.io/)  — 将构建、部署和托管与 JAMStack 或 Node.JS 应用程序的 git 流程无缝集成. 每月免费 50 GB 带宽和 1000 万次请求，包括免费 SSL.
  * [surge.sh](https://surge.sh/)  — 面向前端开发人员的静态 Web 发布. 具有自定义域支持的无限站点
  * [tilda.cc](https://tilda.cc/) — 一个站点，50 页，50 MB 存储空间，只有 170 多个可用的主要预定义块，没有字体，没有网站图标，也没有自定义域
  * [txti.es](https://txti.es/) — 使用 Markdown 快速创建网页.
  * [Vercel](https://vercel.com/)  — 每次使用“git push”时，都使用免费的 SSL、全球 CDN 和独特的预览 URL 构建、部署和托管 Web 应用程序. 非常适合 Next.js 和其他静态站点生成器.
  * [Versoly](https://versoly.com/)  — 专注于 SaaS 的网站构建器 - 无限制的网站、70 多个块、5 个模板、自定义 CSS、网站图标、SEO 和表单. 没有自定义域.
  * [Qovery](https://www.qovery.com)  — Qovery 是在 AWS、GCP 和 Azure 上部署全栈应用程序的最简单方法. 它是为具有数据库、SSL、全球 CDN 和从 Git 自动部署的开发人员提供的免费网络托管.
  * [FlashDrive.io](https://flashdrive.io) - PaaS service similar to Heroku with a developer-centric approach and all inclusive features. Free tier for static assets, staging and developer apps.
  * [FreeFlarum](https://freeflarum.com/) - 社区支持的免费 Flarum 托管，最多可容纳 250 个用户（捐赠以从页脚中删除水印）.



## DNS
  * [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/)  - 由 CloudFlare 提供的免费公共 DNS 解析器，它快速且安全（加密您的 DNS 查询）. 有助于绕过您的互联网提供商的 DNS 阻止，防止 DNS 查询间谍活动，以及 [to block adult & malware content](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families) . 也可以使用 [via API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests) . 注意：只是一个 DNS 解析器，而不是 DNS 主机.
  * [1984.is](https://www.1984.is/product/freedns/) — 带有 API 的免费 DNS 服务，以及许多其他免费的 DNS 功能.
  * [biz.mail.ru](https://biz.mail.ru) — 最多 5,000 个用户的免费电子邮件和 DNS 托管
  * [cloudns.net](https://www.cloudns.net/) — 最多 1 个域的免费 DNS 托管，包含 50 条记录
  * [dns.he.net](https://dns.he.net/) — 具有动态 DNS 支持的免费 DNS 托管服务
  * [dnspod.com](https://www.dnspod.com/) — 免费 DNS 托管.
  * [duckdns.org](https://www.duckdns.org/)  — 免费 DDNS，免费层上最多可包含 5 个域. 带有各种设置的配置指南.
  * [dynu.com](https://www.dynu.com/) — 免费动态 DNS 服务
  * [fosshost.org](https://fosshost.org/) - 免费开源托管 VPS、网络、存储和镜像托管
  * [freedns.afraid.org](https://freedns.afraid.org/)  — 免费 DNS 托管. 还提供基于众多公共用户的免费子域 [contributed domains](https://freedns.afraid.org/domain/registry/) . 注册后从“子域”菜单中获取免费子域.
  * [luadns.com](https://www.luadns.com/) — 免费 DNS 托管，3 个域，所有功能都有合理的限制
  * [namecheap.com](https://www.namecheap.com/domains/freedns/)  — 免费 DNS. 没有域数量限制
  * [nextdns.io](https://nextdns.io) - 基于 DNS 的防火墙，每月 30 万次免费查询
  * [noip](https://www.noip.com/) — 一种动态 dns 服务，每 30 天允许最多 3 个免费主机名确认
  * [ns1.com](https://ns1.com/) — 数据驱动的 DNS、自动流量管理、50 万次免费查询
  * [pointhq.com](https://pointhq.com/developer) — Heroku 上的免费 DNS 托管.
  * [selectel.com](https://selectel.com/services/dns/) — 免费 DNS 托管，任播
  * [web.gratisdns.dk](https://web.gratisdns.dk/domaener/dns/) — 免费 DNS 托管.
  * [Yandex.Connect](https://connect.yandex.com/pdd/) — 最多 1,000 个用户的免费电子邮件和 DNS 托管
  * [zilore.com](https://zilore.com/en/dns) — 免费 DNS 托管.
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) — 具有动态 DNS 支持的免费 DNS 托管.
  * [zonewatcher.com](https://zonewatcher.com)  — 自动备份和 DNS 更改监控.  1 个域名免费
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – 华为提供的免费 DNS 托管
  * [Hetzner](https://www.hetzner.com/dns-console) – 来自 Hetzner 的免费 DNS 托管，提供 API 支持
  * [Glauca](https://docs.glauca.digital/hexdns/) – 最多 3 个域的免费 DNS 托管和 DNSSEC 支持


## IaaS

  * [backblaze.com](https://www.backblaze.com/b2/)  — Backblaze B2 云存储. 无限时间的免费 10 GB（类似 Amazon S3）对象存储
  * [scaleway.com](https://www.scaleway.com/en/object-storage/)  — S3 兼容的对象存储. 免费 75 GB 存储空间和外部传出流量
  * [terraform.io](https://www.terraform.io/)  — Terraform 云. 为最多 5 个用户的团队提供免费的远程状态管理和团队协作.


## DBaaS

   * [airtable.com](https://airtable.com/) — 看起来像一个电子表格，但它是一个关系数据库，无限的基数，1,200 行/基数和 1,000 个 API 请求/月
   * [Astra](https://www.datastax.com/products/datastax-astra/) — 云原生 Cassandra 即服务 [40GB free tier](https://www.datastax.com/products/datastax-astra/pricing)
   * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ 即服务，每月最多 100 万条消息和 20 个免费连接
   * [elephantsql.com](https://www.elephantsql.com/) — PostgreSQL 即服务，20 MB 免费
   * [FaunaDB](https://fauna.com/) — 无服务器云数据库，具有原生 GraphQL、多模型访问和高达 100 MB 的每日免费层
   * [HarperDb](https://harperdb.io/) — 无服务器云数据库，基于 JSON 的动态模式，3000 IOPS 和 1GB 存储
   * [heroku.com](https://www.heroku.com/) — PostgreSQL 即服务，最多 10,000 行和 20 个免费连接（作为“插件”提供，但可以附加到其他空应用程序并从外部访问）
   * [Upstash](https://upstash.com/) — 无服务器 Redis，免费层级高达每天 10,000 个请求，最大数据库大小为 256MB，以及 20 个并发连接
   * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — 免费套餐提供 512 MB
   * [redsmin.com](https://www.redsmin.com/) — Redis 在线实时监控和管理服务，免费监控 1 个 Redis 实例
   * [redislabs](https://redislabs.com/try-free/) - 免费 30Mb redis 实例
   * [MemCachier](https://www.memcachier.com/)  — 托管 Memcache 服务. 免费提供高达 25MB、1 个代理服务器和基本分析
   * [scalingo.com](https://scalingo.com/) — 主要是 PaaS，但提供 128MB 到 192MB 的 MySQL、PostgreSQL 或 MongoDB 免费层
   * [SeaTable](https://seatable.io/)  — 由 Seafile 团队构建的灵活的、类似电子表格的数据库. 无限表，2,000 行，1 个月版本控制，最多 25 名团队成员.
   * [skyvia.com](https://skyvia.com/) — 云数据平台，提供免费套餐，所有计划在测试阶段完全免费
   * [StackBy](https://stackby.com/)  — 一种将电子表格的灵活性、数据库的强大功能以及与您最喜爱的业务应用程序的内置集成结合在一起的工具. 免费计划包括无限用户、10 个堆栈、每个堆栈 2GB 的附件.
   * [InfluxDB](https://www.influxdata.com/) — 时间序列数据库，释放高达 3MB/5 分钟的写入、30MB/5 分钟的读取和 10,000 个基数系列
   * [Quickmetrics](https://www.quickmetrics.io/) — 包含仪表板的时间序列数据库，每天最多可释放 10,000 个事件和总共 5 个指标.
   * [restdb.io](https://restdb.io/)  - 快速简单的 NoSQL 云数据库服务. 使用 restdb.io，您可以获得架构、关系、自动 REST API（带有类似 MongoDB 的查询）和用于处理数据的高效多用户管理 UI. 免费计划允许每秒 3 个用户、2500 条记录和 1 个 API 请求.
   * [cockroachlabs.com](https://www.cockroachlabs.com/free-tier/) — 免费 CockroachDB 高达 5GB 和 1vCPU（有限 [request units](https://www.cockroachlabs.com/docs/cockroachcloud/serverless-faqs.html#what-are-the-usage-limits-of-cockroachdb-serverless-beta))
   * [Neo4j Aura](https://neo4j.com/cloud/aura/)  — 使用 Cypher 查询语言和 REST API 管理原生图形 DBMS/分析平台. 图大小限制（50k 节点，175k 关系）.
   * [Dgraph Cloud](https://cloud.dgraph.io/pricing?type=free)  — 使用 GraphQL API 管理原生 Graph DBMS. 每天限制为 1 MB 数据传输.
   * [TigerGraph Cloud](https://www.tigergraph.com/cloud/)  — 使用类似 SQL 的图形查询语言和 REST API 管理原生图形 DBMS/分析平台.  AWS（4 vCPU、7.5 GB 内存、50 GB 磁盘）或 GCP（2 vCPU、8 GB 内存、128 GB 磁盘）上的 1 个 TG.Free 实例. 免费实例在 1 小时不活动后休眠.
   * [Macrometa](https://www.macrometa.com/)  - 用于构建地理分布式和实时应用程序的 noSQL 数据库、Pub/Sub、事件处理和无服务器边缘计算平台. 免费开发帐户可访问每天 10,000 次操作和 200MB 存储.
   * [Planetscale](https://planetscale.com/) - PlanetScale 是一个兼容 MySQL 的无服务器数据库平台，由 Vitess 提供支持，3 个免费数据库，10GB 存储空间，每个数据库每月读取 1 亿行，每个数据库每月写入 1000 万行.
   * [YugabyteDB](http://cloud.yugabyte.com)  - YugabyteDB 是一个与 PostgresSQL 兼容的分布式 SQL 数据库. 云免费层是一个 2 vCPU、4GB RAM、10GB 磁盘.


## STUN, WebRTC, Web Socket Servers and Other Routers

   * [conveyor.cloud](https://conveyor.cloud/) — Visual Studio 扩展，用于将 IIS Express 公开给本地网络或通过公共 URL 的隧道公开.
   * [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi 是一项托管 VPN 服务，可让您通过免费计划将类似 LAN 的网络安全地扩展到分布式团队，允许最多 5 人的无限网络
   * [Radmin VPN](https://www.radmin-vpn.com/)  - 通过支持类似 LAN 的网络的 VPN 将多台计算机连接在一起. 无限同行.  （Hamachi 替代品）
   * [localhost.run](https://localhost.run/)  — 立即共享您的本地主机环境！ 无需下载. 在端口 8080 上运行您的应用程序，然后运行此命令并共享 URL.
   * [localtunnel](https://theboroer.github.io/localtunnel-www/)  - 轻松将本地开发机器上的 Web 服务共享到公共 Internet URL，而不会弄乱 DNS 和防火墙设置. 类似于 Ngrok. 除了免费托管版本，它也是 [open source](https://github.com/localtunnel/localtunnel).
   * [ngrok.com](https://ngrok.com/) — 通过隧道将本地运行的服务器暴露给公共 URL.
   * [segment.com](https://segment.com/)  — 将事件转换和路由到其他第三方服务的中心.  100,000 个事件/月免费
   * [https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp](https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp) — Twilio STUN
   * [https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302](https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302) — 谷歌 STUN
   * [webhookrelay.com](https://webhookrelay.com)  — 管理、调试、扇出和代理所有 webhook 到公共或内部（即：本地主机）目的地. 此外，通过获取公共 HTTP 端点（`https://yoursubdomain.webrelay.io &lt;----&gt; http://localhost:8080`），通过隧道公开在专用网络中运行的服务器.
   * [Xirsys](https://www.xirsys.com) — STUN / TURN 服务器的全球网络，提供大量免费套餐.
   * [ZeroTier](https://www.zerotier.com)  — FOSS 管理的虚拟以太网即服务. 免费计划的 100 个客户端的无限端到端加密网络. 桌面/移动/北美客户端； 用于配置自定义路由规则和批准专用网络上的新客户端节点的 Web 界面.
   * [Tailscale](https://tailscale.com/)  — 零配置 VPN，使用开源 WireGuard 协议. 安装在 MacOS、iOS、Windows、Linux 和 Android 设备上.  20 台设备供个人使用的免费计划.


## Issue Tracking and Project Management

   * [acunote.com](https://www.acunote.com/) — Free project management and SCRUM software for up to 5 team members
   * [AppFlux](https://appflux.io)  — 带有日志管理和问题的项目管理工具. 通过电子邮件让您的团队加入并忘记管理.
   * [asana.com](https://asana.com/) - 与合作者的私人项目免费
   * [Backlog](https://backlog.com)  — 您的团队在一个平台上发布伟大项目所需的一切. 免费计划提供 1 个项目，10 个用户和 100MB 存储空间.
   * [Basecamp](https://basecamp.com/personal)  - 待办事项列表、里程碑管理、类似论坛的消息传递、文件共享和时间跟踪. 最多 3 个项目、20 个用户和 1GB 的存储空间.
   * [bitrix24.com](https://www.bitrix24.com/) — 免费的内联网和项目管理工具
   * [cacoo.com](https://cacoo.com/)  — 实时在线图表：流程图、UML、网络. 免费最大.  15 个用户/图，25 页
   * [Chpokify](https://chpokify.com/)  — 基于团队的规划扑克，可节省冲刺估算时间. 最多可免费 5 个用户、免费的 Jira 集成、无限制的视频通话、无限制的团队、无限制的会话.
   * [clickup.com](https://clickup.com/)  - 项目管理. 带云存储的免费高级版. 提供移动应用程序和 Git 集成
   * [Cloudcraft](https://cloudcraft.co/) — 使用 Cloudcraft 可视化设计器在几分钟内设计出专业的架构图，并针对 AWS 进行了优化，并带有可显示实时数据的智能组件.
   * [Clubhouse](https://clubhouse.io/)  - 项目管理平台. 最多 10 位用户永远免费
   * [Codegiant](https://codegiant.io)  — 使用存储库托管和 CI/CD 进行项目管理. 免费计划为 5 名团队成员提供无限的存储库、项目和文档. 每月 500 CI/CD 分钟. 每月 30000 次无服务器代码运行分钟.1GB 存储库存储.
   * [Confluence](https://www.atlassian.com/software/confluence)  - Atlassian 的内容协作工具用于帮助团队高效协作和共享知识. 免费计划最多 10 个用户.
   * [contriber.com](https://www.contriber.com/) — 可定制的项目管理平台、免费的入门计划、5 个工作区
   * [draw.io](https://www.draw.io/)  — 本地存储在 Google Drive、OneDrive 或 Dropbox 中的在线图表. 所有功能和存储级别免费
   * [freedcamp.com](https://freedcamp.com/)  - 任务、讨论、里程碑、时间跟踪、日历、文件和密码管理器. 具有无限项目、用户和文件存储空间的免费计划.
   * [easyretro.io](https://www.easyretro.io/) — 免费的简单直观的 sprint 回顾工具
   * [GForge](https://gforge.com)  — 项目管理和问题跟踪工具集，适用于具有自营和 SaaS 选项的复杂项目.  SaaS 免费计划为开源项目提供免费和免费的前 5 位用户.
   * [gleek.io](https://www.gleek.io)  — 面向开发人员的免费描述到图表工具. 使用您的关键字创建非正式的 UML 类、对象或实体关系图.
   * [gliffy.com](https://www.gliffy.com/)  — 在线图表：流程图、UML、线框……还有 Jira 和 Confluence 的插件.  5 个图表和 2 MB 可用空间
   * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector)  - GraphQL Inspector 输出两个 GraphQL 模式之间的更改列表. 每一个变化都被精确解释并标记为破坏性、非破坏性或危险性.
   * [huboard.com](https://huboard.com/) — GitHub 问题的即时项目管理，开源免费
   * [Hygger](https://hygger.io)  ——项目管理平台. 免费计划为无限用户、项目和董事会提供 100 MB 存储空间.
   * [Instabug](https://instabug.com)  — 用于移动应用程序的全面错误报告和应用程序内反馈 SDK. 免费计划最多 1 个应用程序和 1 个成员.
   * [Ilograph](https://www.ilograph.com/)   — 交互式图表，允许用户从多个角度和详细级别查看他们的基础设施. 图表可以用代码表示. 免费层拥有最多 3 个查看者的无限私人图表.
   * [Issue Embed](https://issueembed.dev/)  - 网站的错误报告工具，可直接进入您的 Github 问题. 个人存储库的免费计划，每月最多 500 个问题和 10,000 次页面浏览量/月.
   * [Jira](https://www.atlassian.com/software/jira)  — 在许多企业环境中使用的高级软件开发项目管理工具. 免费计划最多 10 个用户.
   * [kanbanflow.com](https://kanbanflow.com/)  — 基于董事会的项目管理. 免费的高级版本有更多选择
   * [kanbantool.com](https://kanbantool.com/)  — 基于看板的项目管理. 免费的付费计划有更多选择
   * [Kitemaker.co](https://kitemaker.co)  - 在产品开发过程的所有阶段进行协作，并跟踪 Slack、Discord、Figma 和 Github 上的工作. 无限用户，无限空间. 免费计划最多 250 个工作项目.
   * [kanrails.com](https://kanrails.com/)  — 基于看板的项目管理.  3 个合作者、2 个项目和 5 个曲目免费. 付费计划适用于无限的合作者、项目和曲目.
   * [Kumu.io](https://kumu.io/)   — 带有动画、装饰、过滤器、聚类、电子表格导入等的关系图. 免费层允许无限的公共项目. 图大小无限制. 为学生提供免费的私人项目. 如果您不想将文件公开在线（上传、编辑、下载、丢弃），则可以使用沙盒模式.
   * [LeanBoard](https://www.leanboard.io) - 带有 GitHub 问题便利贴的协作白板（用于示例映射和其他技术）
   * [Linear](https://linear.app/)  — 具有简化界面的问题跟踪器. 无限会员免费，上传文件最大 10MB，250 期（不包括存档）
   * [MeisterTask](https://www.meistertask.com/)  — 团队的在线任务管理. 最多免费 3 个项目，项目成员不限.
   * [MeuScrum](https://www.meuscrum.com/en) - 带有看板的免费在线 Scrum 工具
   * [nTask](https://www.ntaskmanager.com/)  — 项目管理软件，使您的团队能够协作、计划、分析和管理日常任务. 基本计划永久免费，100 MB 存储空间，5 个用户/团队. 无限的工作空间、会议、任务、时间表和问题跟踪.
   * [Ora](https://ora.pm/)  - 敏捷任务管理和团队协作. 最多 3 个用户免费，文件大小限制为 10 MB.
   * [pivotaltracker.com](https://www.pivotaltracker.com/) — 免费用于无限制的公共项目和两个私人项目，共有 3 个活跃用户（读写）和无限制的被动用户（只读）.
   * [plan.io](https://plan.io/)  — 使用存储库托管和更多选项进行项目管理.  2 个用户、10 个客户和 500MB 存储空间免费
   * [planitpoker.com](https://www.planitpoker.com/) — 免费在线规划扑克（估算工具）
   * [saas.zentao.pm](https://saas.zentao.pm/) - 还提供用于问题跟踪和项目管理的应用程序生命周期管理解决方案、内部部署和开源版本.
   * [ScrumFast](https://www.scrumfast.com) - Scrum 板具有非常直观的界面，最多可释放 5 个用户.
   * [SpeedBoard](https://speedboard.app) - 敏捷和 Scrum 回顾委员会 - 免费.
   * [Shake](https://www.shakebugs.com/)  - 移动应用程序的应用程序内错误报告和反馈工具. 免费计划，每个应用每月 10 次错误报告.
   * [Tadum](https://tadum.app) - 会议议程和会议记录应用程序专为重复会议而设计，最多 10 人的团队免费
   * [taiga.io](https://taiga.io/) — 面向初创公司和敏捷开发人员的项目管理平台，开源免费
   * [Tara AI](https://tara.ai/)  — 简单的冲刺管理服务. 免费计划具有无限的任务、冲刺和工作空间，没有用户限制.
   * [targetprocess.com](https://www.targetprocess.com/)  — 可视化项目管理，从看板和 Scrum 到几乎所有操作流程. 无限用户免费，最多 1,000 个数据实体 {[more details](https://www.targetprocess.com/pricing/)}
   * [taskade.com](https://www.taskade.com/) — 团队的实时协作任务列表和大纲
   * [taskulu.com](https://taskulu.com/)  — 基于角色的项目管理. 最多可免费 5 个用户. 与 GitHub/Trello/Dropbox/Google Drive 集成
   * [teamwork.com](https://teamwork.com/)  — 项目管理和团队聊天.  5 个用户和 2 个项目免费. 提供高级计划.
   * [testlio.com](https://testlio.com/)  — 问题跟踪、测试管理和 Beta 测试平台. 免费供私人使用
   * [terrastruct.com](https://terrastruct.com/)  — 专门针对软件架构的在线图表制作工具. 每个图表最多 4 层的免费层.
   * [todoist.com](https://todoist.com/)  — 协作和个人任务管理. 提供免费、高级和团队计划. 为符合条件的用户提供折扣.
   * [trello.com](https://trello.com/)  — 基于董事会的项目管理. 无限个人板，10 个团队板.
   * [Tweek](https://tweek.so/) — 简单的每周待办事项日历和任务管理.
   * [ubertesters.com](https://ubertesters.com/) — 测试平台，集成和众测，2 个项目，5 名成员
   * [vabotu](https://vabotu.com/)  - 项目管理的协作工具. 提供免费和其他计划.  Freelance 计划适用于 10 个用户，包括消息传递、任务板、5GB 在线存储、工作区、导出数据.
   * [vivifyscrum.com](https://www.vivifyscrum.com/)  — 敏捷项目管理的免费工具.  Scrum 兼容
   * [Wikifactory](https://wikifactory.com/)  — 包含项目、VCS 和问题的产品设计服务. 免费计划提供无限的项目和合作者以及 3GB 的存储空间.
   * [Yodiz](https://www.yodiz.com/)  — 敏捷开发和问题跟踪. 免费最多 3 个用户，无限项目.
   * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud)  — 免费托管 YouTrack (InCloud) 用于 FOSS 项目、私人项目（3 个用户免费）. 包括时间跟踪和敏捷板
   * [zenhub.com](https://www.zenhub.com)  — GitHub 内唯一的项目管理解决方案. 对公共存储库、OSS 和非营利组织免费
   * [zepel.io](https://zepel.io/)  - 项目管理工具，可让您规划功能、跨学科协作以及一起构建软件. 最多免费 5 名成员. 没有功能限制.
   * [zenkit.com](https://zenkit.com)  — 项目管理和协作工具. 最多 5 个成员免费，5 GB 附件.
   * [Zube](https://zube.io)  — 为 4 个项目和 4 个用户提供免费计划的项目管理.  GitHub 集成可用.
   * [Toggl](https://toggl.com/) — 提供 2 个免费的生产力工具. [Toggl Track](https://toggl.com/track/) 具有免费计划的时间管理和跟踪应用程序可提供专为自由职业者设计的无缝时间跟踪和报告. 它具有无限的跟踪记录、项目、客户、标签、报告等. 和 [Toggl Plan](https://toggl.com/plan/) 用于任务计划，该计划为独立开发人员提供免费计划，具有无限的任务、里程碑和时间表.


## Storage and Media Processing

   * [borgbase.com](https://www.borgbase.com/)  — 用于 Borg Backup 的简单安全的异地备份托管.  10 GB 可用备份空间和 2 个存储库.
   * [sirv.com](https://sirv.com/)  — 具有动态图像优化和调整大小的智能图像 CDN. 免费套餐包括 500 MB 的存储空间和 2 GB 的带宽.
   * [image4.io](https://image4.io/)  — 使用 SDK、集成和迁移工具为网站和应用程序上传图像、强大的操作、存储和交付. 免费套餐包括 25 个学分.  1 个积分等于 1 GB 的 CDN 使用量、1 GB 的存储空间或 1000 次图像转换.
   * [cloudimage.com](https://cloudimage.com/)  — 全图像优化和 CDN 服务，在全球拥有 1500 多个网点. 多种图像大小调整、压缩、水印功能. 用于响应式图像、360 度图像制作和图像编辑的开源插件. 免费包月计划，25GB CDN 流量和 25GB 缓存存储和无限转换.
   * [cloudinary.com](https://cloudinary.com/)  — 网站和应用程序的图像上传、强大的操作、存储和交付，以及适用于 Ruby、Python、Java、PHP、Objective-C 等的库. 免费套餐包括 25 个月积分.  1 个积分等于 1,000 次图像转换、1 GB 存储或 1 GB CDN 使用量.
   * [easyDB.io](https://easydb.io/)  — 一键式托管数据库提供商. 它们为您选择的编程语言提供了一个数据库，用于开发目的. 数据库是短暂的，将在免费套餐 24 或 72 小时后删除.
   * [embed.ly](https://embed.ly/)  — 提供用于在网页中嵌入媒体、响应式图像缩放、从网页中提取元素的 API. 免费，每月最多 5,000 个 URL，每秒 15 个请求
   * [filestack.com](https://www.filestack.com/) — 文件选择器、转换和交付，250 个文件、500 次转换和 3 GB 带宽免费
   * [gumlet.com](https://www.gumlet.com/)  — 图像调整大小即服务. 它还优化图像并通过 CDN 执行交付. 免费套餐包括 1 GB 带宽和一年内每月无限数量的图像处理.
   * [image-charts.com](https://www.image-charts.com/) - 带水印的无限图像图表生成
   * [jsonbin.io](https://jsonbin.io/) — 免费的 JSON 数据存储服务，非常适合小型 Web 应用程序、网站、移动应用程序.
   * [kraken.io](https://kraken.io/) — 网站性能即服务的图像优化，免费计划最大 1 MB 文件大小
   * [npoint.io](https://www.npoint.io/) — 具有协作模式编辑的 JSON 存储
   * [otixo.com](https://www.otixo.com/)  — 从一处加密、共享、复制和移动所有云存储文件. 基本计划提供最大 250 MB 的无限制文件传输. 文件大小并允许 5 个加密文件
   * [packagecloud.io](https://packagecloud.io/)  — YUM、APT、RubyGem 和 PyPI 的托管包存储库. 有限的免费计划，可根据要求提供开源计划
   * [piio.co](https://piio.co/)  — 每个网站的响应式图像优化和交付. 开发人员和个人网站的免费计划. 包括开箱即用的免费 CDN、WebP 和延迟加载.
   * [Pinata IPFS](https://pinata.cloud)  — Pinata 是在 IPFS 上上传和管理文件的最简单方法. 我们友好的用户界面与我们的 IPFS API 相结合，使 Pinata 成为平台、创作者和收藏家最简单的 IPFS 固定服务.  1 GB 免费存储空间以及 API 访问权限.
   * [placeholder.com](https://placeholder.com/) — 快速简单的图像占位符服务
   * [placekitten.com](https://placekitten.com/) — 一种快速简单的服务，用于获取小猫的照片以用作占位符
   * [plot.ly](https://plot.ly/)  — 绘制并共享您的数据. 免费套餐包括无限的公共文件和 10 个私人文件
   * [podio.com](https://podio.com/) — 您可以与最多 5 人的团队一起使用跑道，并尝试基本计划的功能，但用户管理除外
   * [QuickChart](https://quickchart.io) — 生成可嵌入的图像图表、图形和二维码
   * [redbooth.com](https://redbooth.com) — P2P 文件同步，最多 2 个用户免费
   * [shrinkray.io](https://shrinkray.io/) — GitHub 存储库的免费图像优化
   * [Skynet](https://siasky.net) — 一种开放协议，用于在去中心化网络上托管数据和网络应用程序，使用 [Sia](https://sia.tech/) . 免费套餐提供高达 100GB 的存储空间.
   * [Storj](https://storj.io)  — 面向应用程序和开发人员的分散式私有云存储. 免费计划提供 3 个项目，每个项目/月 50 GB 存储空间，每个项目/月 50 GB 带宽.
   * [tinypng.com](https://tinypng.com/) — 用于压缩和调整 PNG 和 JPEG 图像大小的 API，每月免费提供 500 次压缩
   * [transloadit.com](https://transloadit.com/)  — 处理文件上传和视频、音频、图像、文档的编码. 通过 GitHub Student Developer Pack 对开源、慈善机构和学生免费. 商业应用程序免费获得 2 GB 用于试驾
   * [uploadcare.com](https://uploadcare.com/hub/developers/)  — Uploadcare 为媒体管道提供基于尖端算法的终极工具包. 开发人员可以完全免费使用所有功能：文件上传 API 和 UI、图像 CDN 和源服务、自适应交付和智能压缩. 限制免费层有 3000 次上传、3 GB 流量和 3 GB 存储空间.
   * [imagekit.io](https://imagekit.io)  – 具有自动优化、实时转换和存储功能的图像 CDN，您可以在几分钟内与现有设置集成. 免费计划包括每月高达 20GB 的带宽.
   * [internxt.com](https://internxt.com)  – Internxt Drive 是一种基于绝对隐私和不妥协安全性的零知识文件存储服务. 注册并永久免费获得 2 GB！
   * [degoo.com](https://degoo.com/) – 基于 AI 的云存储，最多可免费使用 100 Gb、5 台设备、500 Gb 推荐奖金（365 天帐户不活动）.



## Design and UI

  * [AllTheFreeStock](https://allthefreestock.com) - 精选的免费图片、音频和视频列表.
  * [Ant Design Landing Page](https://landing.ant.design/)  - Ant Design Landing Page 提供了一个由 Ant Motion 的动作组件构建的模板. 拥有丰富的首页模板，下载模板代码包，快速上手. 您还可以使用编辑器快速构建自己的专用页面.
  * [Backlight](https://backlight.dev/) — 以开发人员和设计人员之间的协作为核心，Backlight 是一个非常完整的编码平台，团队可以在其中构建、记录、发布、扩展和维护设计系统.免费计划允许最多 3 名编辑人员在 1 个设计系统上工作，并且不受限制.
  * [BoxySVG](https://boxy-svg.com/app) — 一个可免费安装的 Web 应用程序，用于绘制 SVG 并以 svg、png、jpeg 和其他格式导出.
  * [clevebrush.com](https://www.cleverbrush.com/) — 免费图形设计/照片拼贴应用程序，他们还提供将其作为组件付费集成.
  * [cloudconvert.com](https://cloudconvert.com/)  — 将任何东西转换为任何东西.  208 种支持的格式，包括视频转 gif.
  * [CodeMyUI](https://codemyui.com) - 精心挑选的带有代码片段的网页设计和 UI 灵感集合.
  * [designer.io](https://www.designer.io/)  — 用于 UI、插图等的设计工具. 有一个本地应用程序. 自由.
  * [figma.com](https://www.figma.com)  — 团队的在线协作设计工具； 免费层包括无限的文件和查看器，最多 2 个编辑器和 3 个项目.
  * [framer.com](https://www.framer.com/)  - Framer 可帮助您为下一个应用程序、网站或产品迭代和动画界面创意——从强大的布局开始. 对于任何将 Framer 验证为专业原型制作工具的人：无限制的查看者、最多 2 个编辑器、最多 3 个项目.
  * [Icon Horse](https://icon.horse) – 从我们简单的 API 中获取任何网站的最高分辨率图标.
  * [Icons8](https://icons8.com)  — 图标、插图、照片、音乐和设计工具. 免费计划以较低的分辨率提供有限的格式. 当您使用我们的资产时链接到 Icons8.
  * [imagebin.ca](https://imagebin.ca/) — 用于图像的 Pastebin.
  * [Invision App](https://www.invisionapp.com)  - UI 设计和原型制作工具. 桌面和网络应用程序可用. 免费使用 1 个活动原型.
  * [landen.co](https://www.landen.co)  — 为您的初创公司生成、编辑和发布漂亮的网站和登陆页面. 一切都没有代码. 免费套餐允许您拥有一个网站，完全可定制并在网络上发布.
  * [lensdump.com](https://lensdump.com/) - 免费云图像托管.
  * [Lorem Picsum](https://picsum.photos/)  - 免费工具，易于使用的时尚占位符. 只需在我们的 URL 后添加您想要的图像尺寸（宽度和高度），您就会得到一个随机图像.
  * [marvelapp.com](https://marvelapp.com/) — 设计、原型制作和协作，仅限一个用户和一个项目的免费计划.
  * [Mindmup.com](https://www.mindmup.com/)  — 免费无限量思维导图，并存储在云端. 您的思维导图可随时随地从任何设备使用.
  * [Mockplus iDoc](https://www.mockplus.com/idoc)  - Mockplus iDoc 是一个强大的设计协作和移交工具. 免费计划包括 3 个用户和 5 个具有所有可用功能的项目.
  * [mockupmark.com](https://mockupmark.com/create/free) — 为社交媒体和电子商务创建逼真的 T 恤和服装模型，40 个免费模型.
  * [Octopus.do](https://octopus.do)  — 可视化站点地图构建器. 实时构建您的网站结构并快速共享以与您的团队或客户协作.
  * [Pencil](https://github.com/evolus/pencil) - 使用 Electron 的开源设计工具.
  * [Penpot](https://penpot.app)  - 基于 Web 的开源设计和原型制作工具. 支持 SVG. 完全免费.
  * [pexels.com](https://www.pexels.com/)  - 用于商业用途的免费库存照片. 有免费的 API，可让您按关键字搜索照片.
  * [photopea.com](https://www.photopea.com) — 一款免费、高级的在线设计编辑器，带有 Adob​​e Photoshop UI，支持 PSD、XCF 和 Sketch 格式（Adobe Photoshop、Gimp 和 Sketch 应用程序）.
  * [pixlr.com](https://pixlr.com/) — 商业级别的免费在线浏览器编辑器.
  * [Plasmic](https://www.plasmic.app/)  - 快速、易于使用、功能强大的网页设计工具和页面构建器，可集成到您的代码库中. 构建响应式页面或复杂组件； 可选地用代码扩展； 并发布到生产站点和应用程序.
  * [Pravatar](https://pravatar.cc/) - 生成随机/占位符假头像，该网址可以直接在您的网络/应用程序中热链接.
  * [Proto.io](https://www.proto.io)  - 无需编码即可创建完全交互式的 UI 原型. 免费试用期结束时提供免费套餐. 免费套餐包括：1 个用户、1 个项目、5 个原型、100MB 在线存储和 proto.io 应用程序预览.
  * [resizeappicon.com](https://resizeappicon.com/) — 调整和管理应用程序图标的简单服务.
  * [Rive](https://rive.app)  — 创建精美的动画并将其传送到任何平台. 个人永久免费. 该服务是一个编辑器，它也在其服务器上托管所有图形. 它们还为许多平台提供运行时来运行使用 Rive 制作的图形.
  * [smartmockups.com](https://smartmockups.com/) — 创建产品模型，200 个免费模型.
  * [UI Avatars](https://ui-avatars.com/)  - 用名字的首字母生成头像. 哪些网址可以直接在您的网络/应用程序中进行热链接. 支持通过 url 配置参数.
  * [unDraw](https://undraw.co/) - 不断更新的精美 svg 图片集合，您可以完全免费使用，无需署名.
  * [unsplash.com](https://unsplash.com/) - 用于商业和非商业目的的免费库存照片（做任何你想要的许可）.
  * [vectr.com](https://vectr.com/) — 适用于 Web + 桌面的免费设计应用程序.
  * [walkme.com](https://www.walkme.com/) — 企业级指导和参与平台，免费计划 3 步行，最多 5 步/步行.
  * [Webflow](https://webflow.com)  - 具有动画和网站托管的所见即所得网站构建器.  2个项目免费.
  * [Updrafts.app](https://updrafts.app)  - WYSIWYG 网站构建器，用于基于 tailwindcss 的设计. 免费用于非商业用途.
  * [whimsical.com](https://whimsical.com/)  - 协作流程图、线框、便利贴和思维导图. 创建最多 4 个免费板.
  * [Zeplin](https://zeplin.io/)  — 设计师和开发者协作平台. 展示设计、资产和风格指南.  1 个项目免费.
  * [Pixelixe](https://pixelixe.com/) — 在线创建和编辑引人入胜且独特的图形和图像.
  * [Responsively App](https://responsively.app) - 一个免费的开发工具，用于更快、更精确的响应式 Web 应用程序开发.
  * [SceneLab](https://scenelab.io) - 具有不断扩展的免费设计模板集合的在线模型图形编辑器
  * [xLayers](https://xlayers.dev) - 预览 Sketch 设计文件并将其转换为 Angular、React、Vue、LitElement、Stencil、Xamarin 等（免费和开源在 https://github.com/xlayers/xlayers）
  * [Grapedrop](https://grapedrop.com/)  — 基于 GrapesJS 框架的响应式、强大、SEO 优化的网页构建器. 前 5 页免费，无限自定义域，所有功能和简单使用.
  * [Mastershot](https://mastershot.app)  - 完全免费的基于浏览器的视频编辑器. 无水印，高达 1080p 的导出选项.
  * [Unicorn Platform](https://unicornplatform.com/)  - 使用托管轻松登录页面构建器.  1个免费网站.


## Data Visualization on Maps

   * [IP Geolocation](https://ipgeolocation.io/) — 免费的 DEVELOPER 计划可提供 30K 请求/月.
   * [carto.com](https://carto.com/) — 根据您的数据和公共数据创建地图和地理空间 API.
   * [datamaps.world](https://datamaps.world/) — 简单但功能强大的平台，为您提供免费层级可视化地理空间数据的工具.
   * [developers.arcgis.com](https://developers.arcgis.com)  — 用于地图、地理空间数据存储、分析、地理编码、路由等跨 Web、桌面和移动设备的 API 和 SDK.  2,000,000 个免费底图切片、20,000 个非存储地理编码、20,000 条简单路线、5,000 次行驶时间计算、每月 5GB 免费切片+数据存储.
   * [Foursquare](https://developer.foursquare.com/) - 来自 Places API 和 Pilgrim SDK 的位置发现、场所搜索和上下文感知内容.
   * [geoapify.com](https://www.geoapify.com/)  - 矢量和栅格地图图块、地理编码、地点、路由、等值线 API.  3000 个免费请求/天.
   * [geocod.io](https://www.geocod.io/)  — 通过 API 或 CSV 上传进行地理编码.  2,500 次免费查询/天.
   * [geocodify.com](https://geocodify.com/)  — 通过 API 或 CSV 上传进行地理编码和地理解析.  10k 免费查询/月.
   * [giscloud.com](https://www.giscloud.com/) — 在线可视化、分析和共享地理数据.
   * [gogeo.io](https://gogeo.io/) — 具有易于使用的 API 和大数据支持的地图和地理空间服务.
   * [graphhopper.com](https://www.graphhopper.com/) 为开发人员提供了一个用于路由、路由优化、距离矩阵、地理编码、地图匹配的免费包.
   * [here](https://developer.here.com/)  — 用于地图和位置感知应用程序的 API 和 SDK. 每月 25 万笔交易免费.
   * [mapbox.com](https://www.mapbox.com/) — 地图、地理空间服务和用于显示地图数据的 SDK.
   * [maptiler.com](https://www.maptiler.com/cloud/)  — 用于地图可视化的矢量地图、地图服务和 SDK. 每周更新和四种地图样式的免费矢量瓷砖.
   * [opencagedata.com](https://opencagedata.com)  — 聚合 OpenStreetMap 和其他开放地理资源的地理编码 API.  2,500 次免费查询/天.
   * [osmnames](https://osmnames.org/) — 地理编码，搜索结果按相关维基百科页面的受欢迎程度排序.
   * [positionstack](https://positionstack.com/)  - 全球地点和坐标的免费地理编码. 每月 25.000 次个人使用请求.
   * [stadiamaps.com](https://stadiamaps.com/)  — 地图图块、路由、导航和其他地理空间 API. 每天 2,500 次免费地图视图和 API 请求，用于非商业用途和测试.
   * [http://maps.stamen.com/](http://maps.stamen.com/) - 免费地图图块和图块托管.
   * [GeocodeAPI](https://geocodeapi.io)  - 地理编码 API：基于 Pelias 的地址到坐标转换和地理解析. 通过 CSV 进行批量地理编码.  350000 个免费请求/月.
   * [Geokeo api](https://geokeo.com)  - 带有语言校正等功能的地理编码 api. 全球覆盖. 每天 2,500 次免费查询


## Package Build System

   * [build.opensuse.org](https://build.opensuse.org/) — 多个发行版（SUSE、EL、Fedora、Debian 等）的包构建服务.
   * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — 用于 Fedora 和 EL 的基于模拟的 RPM 构建服务.
   * [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu 和 Debian 构建服务.


## IDE and Code Editing

   * [3v4l](https://3v4l.org/) - 免费在线 PHP shell 和代码片段共享站点，在 300 多个 PHP 版本中运行您的代码
   * [Android Studio](https://d.android.com/studio)  — Android Studio 为在各种类型的 Android 设备上构建应用程序提供了最快的工具. 开源 IDE，对所有人免费，是开发 Android 应用程序的最佳选择. 适用于 Windows、Mac、Linux 甚至 ChromeOS！
   * [Apache Netbeans](https://netbeans.apache.org/) — 开发环境、工具平台和应用程序框架.
   * [apiary.io](https://apiary.io/) — 具有即时 API 模拟和生成文档的协作设计 API（对于具有一个管理员帐户和托管文档的无限 API 蓝图和无限用户免费）.
   * [Atom](https://atom.io/) - Atom 是一个基于 Electron 的可破解文本编辑器.
   * [BlueJ](https://bluej.org)  — 为初学者设计的免费 Java 开发环境，全球数百万人使用. 由 Oracle 和简单的 GUI 提供支持，以帮助初学者.
   * [Bootify.io](https://bootify.io/) - 带有自定义数据库和 REST API 的 Spring Boot 应用程序生成器.
   * [cacher.io](https://www.cacher.io) — 带有标签的代码片段组织器，支持 100 多种编程语言.
   * [Code::Blocks](https://codeblocks.org)  — 免费的 Fortran 和 C/C++ IDE. 开源并在 Windows、macOS 和 Linux 上运行.
   * [codesnip.com.br](https://codesnip.com.br)  — 带有类别、搜索和标签的简单代码片段管理器. 免费且无限制.
   * [cocalc.com](https://cocalc.com/)  —（以前在 cloud.sagemath.com 上的 SageMathCloud）— 云中的协作计算. 浏览器访问完整的 Ubuntu，内置协作和许多免费的数学、科学、数据科学软件，预装：Python、LaTeX、Jupyter Notebooks、SageMath、scikitlearn 等.
   * [ide.cs50.io](https://ide.cs50.io/) - 由哈佛大学 AWS Cloud9 提供支持的免费 IDE.
   * [codepen.io](https://codepen.io/) — CodePen is a playground for the front end side of the web.
   * [codesandbox.io](https://codesandbox.io/) — Online Playground for React, Vue, Angular, Preact and more.
   * [Components.studio](https://webcomponents.dev/) - 独立编码组件，在故事中可视化它们，测试它们并在 npm 上发布它们.
   * [Eclipse Che](https://www.eclipse.org/che/)  - 面向具有多语言支持的开发团队的基于 Web 的 Kubernetes 原生 IDE. 开源和社区驱动. 由 Red Hat 托管的在线实例可在 [workspaces.openshift.com](https://workspaces.openshift.com/).
   * [fakejson.com](https://fakejson.com/)  — FakeJSON 可帮助您使用其 API 快速生成假数据. 发出一个 API 请求，描述你想要什么以及你想要它的方式.  API 以 JSON 格式返回所有内容. 加快创意进入市场的过程，并伪造它直到你成功.
   * [gitpod.io](https://www.gitpod.io)  — 用于 GitHub 项目的即时、可编写代码的开发环境. 免费开源.
   * [ide.goorm.io](https://ide.goorm.io)  goormIDE 是云上的完整 IDE. 多语言支持，基于 linux 的容器，通过功能齐全的基于 Web 的终端，端口转发，自定义 url，实时协作和聊天，共享链接，Git/Subversion 支持. 还有更多功能（免费套餐包括每个容器 1GB RAM 和 10GB 存储空间，5 个容器插槽）.
   * [JDoodle](https://www.jdoodle.com) — 用于 60 多种编程语言的在线编译器和编辑器，提供免费的 REST API 代码计划，每天最多可编译 200 个学分.
   * [jetbrains.com](https://jetbrains.com/products.html) — 生产力工具、IDE 和部署工具（又名 [IntelliJ IDEA](https://www.jetbrains.com/idea/), [PyCharm](https://www.jetbrains.com/pycharm/) ， 等等）. 学生、教师、开源和用户组的免费许可证.
   * [jsbin.com](https://jsbin.com) — JS Bin 是前端 Web（HTML、CSS 和 JavaScript.也支持 Markdown、Jade 和 Sass）的另一个游乐场和代码共享站点.
   * [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle 是前端 web 的游乐场和代码共享站点，也支持协作.
   * [JSONPlaceholder](http://jsonplaceholder.typicode.com/) 一些 REST API 端点以 JSON 格式返回一些假数据. 如果您想在本地运行服务器，也可以使用源代码.
   * [Katacoda](https://katacoda.com) — 软件工程师的交互式学习和培训平台，帮助开发人员学习和公司提高采用率.
   * [Lazarus](https://www.lazarus-ide.org/) — Lazarus 是一个 Delphi 兼容的跨平台 IDE，用于快速应用程序开发.
   * [micro-jaymock](https://micro-jaymock.now.sh/) - 用于生成假 JSON 数据的微型 API 模拟微服务.
   * [mockable.io](https://www.mockable.io/)  — Mockable 是一个简单的可配置服务，用于模拟 RESTful API 或 SOAP Web 服务. 此在线服务允许您快速定义 REST API 或 SOAP 端点并让它们返回 JSON 或 XML 数据.
   * [mockaroo](https://mockaroo.com/)  — Mockaroo 可让您以 CSV、JSON、SQL 和 Excel 格式生成真实的测试数据. 您还可以为后端 API 创建模拟.
   * [Mocklets](https://mocklets.com) - 基于 HTTP 的模拟 API 模拟器，可帮助模拟 API 以实现更快的并行开发和更全面的测试，并具有终身免费层.
   * [Paiza](https://paiza.cloud/en/)  — 在浏览器中开发 Web 应用程序，无需进行任何设置. 免费计划提供 1 台服务器，具有 24 小时的使用寿命和每天 4 小时的运行时间，具有 2 个 CPU 内核、2 GB RAM 和 1 GB 存储空间.
   * [Prepros](https://prepros.io/)  - Prepros 可以开箱即用地编译 Sass、Less、Stylus、Pug/Jade、Haml、Slim、CoffeeScript 和 TypeScript，重新加载您的浏览器并使开发和测试您的网站变得非常容易，这样您就可以专注于使它们变得完美. 只需单击几下，您还可以添加自己的工具.
   * [Replit](https://replit.com/) — 适用于各种程序语言的云编码环境.
   * [SoloLearn](https://code.sololearn.com)  — 非常适合运行代码片段的云编程游乐场. 支持多种编程语言. 运行代码不需要注册，但需要在他们的平台上保存代码时需要. 还为初学者和中级编码员提供免费课程.
   * [stackblitz.com](https://stackblitz.com/)  — 用于创建、编辑和部署全栈应用程序的在线/云代码 IDE. 支持任何流行的基于 NodeJs 的前端和后端框架. 创建新项目的短链接： [https://node.new](https://node.new).
   * [Visual Studio Code](https://code.visualstudio.com/)  - 代码编辑器重新定义和优化，用于构建和调试现代 Web 和云应用程序. 由 Microsoft 为 Windows、macOS 和 Linux 开发.
   * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — Fully-featured IDE with thousands of extensions, cross-platform app development (Microsoft extensions available for download for iOS and Android), desktop, web and cloud development, multi-language support (C#, C++, JavaScript, Python, PHP and more).
   * [VSCodium](https://vscodium.com/) - 社区驱动，无遥测/跟踪，免费许可的微软编辑器 VSCode 二进制分发
   * [wakatime.com](https://wakatime.com/) — 关于您的编码活动的量化自我指标，使用文本编辑器插件，免费的有限计划.
   * [WebComponents.dev](https://webcomponents.dev/) — 浏览器内 IDE 使用 58 个可用模板对 Web 组件进行隔离编码，支持故事和测试.


## Analytics, Events and Statistics

   * [Statvoo Analytics](https://analytics.statvoo.com/) — 永久免费为您的所有网站提供客户分析，每月无限次活动
   * [Avo](https://avo.app/)  — 简化的分析发布工作流程. 单一来源的真实跟踪计划、类型安全分析跟踪库、应用内调试器、数据可观察性，可在发布之前捕获所有数据问题.  2 个工作区成员免费和 1 小时数据可观察性回顾.
   * [Branch](https://branch.io)  — 移动分析平台. 免费套餐为多达 10,000 名移动应用用户提供深层链接和其他服务.
   * [Clicky](https://clicky.com)  — 网站分析平台.  1 个网站的免费计划，具有 3000 次浏览分析.
   * [Databox](https://databox.com)  — 通过结合其他分析和 BI 平台，获得商业洞察力和分析. 免费计划提供 3 个用户、仪表板和数据源.  11M 历史数据记录.
   * [indicative.com](https://indicative.com/)  — 客户分析平台，以优化客户参与度、增加转化率并提高保留率. 免费多达 5000 万个事件/月.
   * [Panelbear.com](https://panelbear.com/) — 超快且私密的免费套餐包括每月 5,000 次无限制网站的综合浏览量
   * [Hitsteps.com](https://hitsteps.com/) — 1 个网站每月 2,000 次综合浏览量
   * [amplitude.com](https://amplitude.com/) — 每月 100 万个事件，最多 2 个应用程序
   * [Flagsmith](https://www.molasses.app)  - 自信地发布功能； 跨 Web、移动和服务器端应用程序管理功能标志. 使用我们的托管 API，部署到您自己的私有云，或在本地运行
   * [goatcounter.com](https://www.goatcounter.com/)  — GoatCounter 是一个开源网络分析平台，可作为托管服务（非商业用途免费）或自托管应用程序提供. 它旨在提供易于使用且有意义的隐私友好型网络分析，作为 Google Analytics 或 Matomo 的替代方案. 免费套餐用于非商业用途，包括无限数量的网站、6 个月的数据保留期和 10 万次/月的综合浏览量.
   * [Google Analytics](https://analytics.google.com/) - 谷歌分析
   * [expensify.com](https://www.expensify.com/) — 费用申报、免费的个人申报审批工作流程
   * [getinsights.io](https://getinsights.io) - 以隐私为中心的无 cookie 分析，每月最多可免费进行 5k 事件.
   * [heap.io](https://heap.io)  — 自动捕获 iOS 或 Web 应用程序中的每个用户操作. 每月最多 5,000 次访问免费
   * [Hotjar](https://hotjar.com)  — 网站分析和报告. 免费计划允许 2000 次网页浏览/天.  100 张快照/天（最大容量：300）.  3 张快照热图，可存储 365 天. 无限的团队成员.
   * [imprace.com](https://imprace.com/)  — 着陆页分析以及提高跳出率的建议. 免费 5 个登陆页面/域
   * [keen.io](https://keen.io/)  — 用于数据收集、分析和可视化的自定义分析.  50,000 个事件/月免费
   * [metrica.yandex.com](https://metrica.yandex.com/) — 无限制的免费分析
   * [mixpanel.com](https://mixpanel.com/) — 每月跟踪 100,000 名用户、无限数据历史记录和席位、美国或欧盟数据驻留
   * [Moesif](https://www.moesif.com)  — REST 和 GraphQL 的 API 分析.  （免费多达 500,000 个 API 调用/月）
   * [Molasses](https://www.molasses.app)  - 强大的功能标志和 A/B 测试. 最多释放 3 个环境，每个环境具有 5 个功能标志.
   * [optimizely.com](https://www.optimizely.com) — A/B 测试解决方案、免费入门计划、1 个网站、1 个 iOS 和 1 个 Android 应用
   * [Microsoft PowerBI](https://powerbi.com)  — 微软的商业洞察与分析. 免费计划提供 100 万用户许可证的有限使用.
   * [quantcast.com](https://www.quantcast.com/products/measure-audience-insights/) — 无限制的免费分析
   * [sematext.com](https://sematext.com/cloud/) — 每月最多 5 万次操作、1 天数据保留、无限制的仪表板、用户等免费.
   * [Similar Web](https://similarweb.com)  — 网络和移动应用分析. 免费计划为每个指标提供 5 个结果、1 个月的移动应用数据和 3 个月的网站数据.
   * [StatCounter](https://statcounter.com/)  — 网站浏览者分析. 免费计划分析 500 个最近的访问者.
   * [Tableau Developer Program](https://www.tableau.com/developer)  — 创新、创造并让 Tableau 完美地为您的组织工作. 免费的开发人员计划为 Tableau Online 提供个人开发沙盒许可证. 该版本是最新的预发布版本，因此数据开发人员可以测试这个卓越平台的每一个功能.
   * [usabilityhub.com](https://usabilityhub.com/)  — 在真人身上测试设计和模型，跟踪访客. 一位用户免费，无限次测试
   * [woopra.com](https://www.woopra.com/) — 用于 50 万次操作、90 天数据保留、30 多个一键集成的免费用户分析平台.
   * [counter.dev](https://counter.dev)  — 网络分析变得简单，因此隐私友好. 免费或通过捐赠支付您想要的东西.


## Visitor Session Recording

   * [Reactflow.com](https://www.reactflow.com/) — 每个站点：每天 1,000 页浏览量、3 个热图、3 个小部件、免费错误跟踪
   * [LogRocket.com](https://www.logrocket.com) - 每月 1,000 个会话，保留 30 天，错误跟踪，实时模式
   * [FullStory.com](https://www.fullstory.com)  — 1,000 个会话/月，数据保留 1 个月和 3 个用户席位. 更多信息 [here](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition).
   * [hotjar.com](https://www.hotjar.com/) — 每个站点：每天 2,000 页浏览量，3 个热图，数据存储 3 个月，...
   * [inspectlet.com](https://www.inspectlet.com/) — 1 个网站每月免费 100 次会话
   * [livesession.io](https://livesession.io/) — 1 个网站每月免费 1,000 次会话
   * [Microsoft Clarity](https://clarity.microsoft.com/) - 会话录制完全免费，“无流量限制”、无项目限制、无采样
   * [mouseflow.com](https://mouseflow.com/) — 1 个网站每月免费 100 次会话
   * [mousestats.com](https://www.mousestats.com/) — 1 个网站每月免费 100 次会话
   * [smartlook.com](https://www.smartlook.com/) — 网络和移动应用程序的免费包（1500 个会话/月）、3 个热图、1 个漏斗、1 个月的数据历史记录
   * [usersurge.com](https://www.usersurge.com/) — 个人每月 25 万次会话.
   * [howuku.com](https://howuku.com)  — 跟踪用户交互、参与和事件. 每月最多 5,000 次访问免费
   * [UXtweak.com](https://www.uxtweak.com/)  — 记录并观察访问者如何使用您的网站或应用程序. 小项目免费无限时间


## International Mobile Number Verification API and SDK

  * [cognalys.com](https://cognalys.com/) — Freemium mobile number verification through an innovative and reliable method than using SMS gateway. Free 10 tries and 15 verifications/day
  * [numverify.com](https://numverify.com/)  — 全球电话号码验证和查找 JSON API.  250 个 API 请求/月
  * [veriphone.io](https://veriphone.io/)  — 免费、快速、可靠的 JSON API 中的全球电话号码验证.  1000 次请求/月


## Payment and Billing Integration

  * [CurrencyFreaks](https://currencyfreaks.com/)  — 提供当前和历史货币汇率. 免费的 DEVELOPER 计划可提供 1000 个请求/月.
  * [currencyapi.net](https://currencyapi.net/)  — 实物和加密货币的实时汇率，以 JSON 和 XML 格式提供. 免费套餐每月提供 1,250 个 API 请求.
  * [currencylayer.com](https://currencylayer.com/) — 为您的企业提供可靠的汇率和货币转换，每月免费 1,000 个 API 请求
  * [currencystack.io](https://currencystack.io/) — 154 种货币的生产就绪实时汇率.
  * [exchangerate-api.com](https://www.exchangerate-api.com)  - 易于使用的货币转换 JSON API. 免费套餐，没有请求限制.
  * [fraudlabspro.com](https://www.fraudlabspro.com)  — 帮助商户防止支付欺诈和退款. 免费的微型计划可提供 500 次查询/月.
  * [mailpop.in](https://mailpop.in) - 通过上下文信息充分利用您的 Stripe 通知.
  * [namiml.com](https://www.namiml.com/)  - 适用于 iOS 和 Android 上的应用内购买和订阅的完整平台，包括无代码付费墙、CRM 和分析. 免费提供所有基本功能来运行 IAP 业务.
  * [revenuecat.com](https://www.revenuecat.com/)  — 用于应用内购买和订阅（iOS 和 Android）的托管后端. 每月可免费获得高达 1 万美元的跟踪收入.
  * [vatlayer.com](https://vatlayer.com/) — 即时增值税号验证和欧盟增值税税率 API，每月免费 100 个 API 请求
  * [freecurrencyapi.net](https://freecurrencyapi.net/)  — 免费货币转换和汇率数据 API.  10 个请求/小时，无需 API 密钥，免费注册时每月 50 000 个请求.


## Docker Related

  * [canister.io](https://canister.io/) — 为开发人员提供 20 个免费私有存储库，为团队构建和存储 Docker 镜像提供 30 个免费私有存储库
  * [Container Registry Service](https://container-registry.com/)  - 基于港口的集装箱管理解决方案. 免费层为私有存储库提供 1 GB 存储空间.
  * [Docker Hub](https://hub.docker.com) — 一个免费的私有存储库和无限的公共存储库来构建和存储 Docker 镜像
  * [Play with Docker](https://labs.play-with-docker.com/) — 一个简单、互动且有趣的学习 Docker 的游乐场.
  * [quay.io](https://quay.io/) — 使用无限制的免费公共存储库构建和存储容器映像
  * [TreeScale.com](https://treescale.com/)  — 使用组权限托管和管理容器映像. 免费层为私有存储库提供 1 GB 存储空间.
  * [Platform9](https://platform9.com/)  - 托管 Kubernetes 平面. 免费计划提供多达 3 个集群和 20 个节点的管理功能. 注意：您必须自己提供集群基础设施.


## Vagrant Related

  * [app.vagrantup.com](https://app.vagrantup.com)  - HashiCorp 流浪云. 流浪盒托管.
  * [vagrantbox.es](https://www.vagrantbox.es/) ——另一种公共箱索引


## Dev Blogging Sites

  * [dev.to](https://dev.to/) - 程序员在这里分享想法并帮助彼此成长.
  * [hashnode.com](https://hashnode.com/) — 面向开发人员的无忧博客软件！.
  * [medium.com](https://medium.com/) — 更明智地了解对您而言重要的事情.


## Commenting Platforms
  * [Staticman](https://staticman.net/) - Staticman 是一个 Node.js 应用程序，它接收用户生成的内容并使用拉取请求将其作为数据文件上传到 GitHub 和/或 GitLab 存储库.
  * [GraphComment](https://graphcomment.com/) - GraphComment 是一个评论平台，可帮助您从网站的受众中建立一个活跃的社区.
  * [Utterances](https://utteranc.es/)  - 基于 GitHub 问题构建的轻量级评论小部件. 将 GitHub 问题用于博客评论、维基页面等！
  * [Disqus](https://disqus.com/) - Disqus 是一个网络社区平台，被整个网络上的数十万个站点所使用.


## Screenshot APIs

  * [24browser.com](https://www.24browser.com) – 使用强大的 API 大规模捕获呈现精美的网站屏幕截图.
  * [ApiFlash](https://apiflash.com)  — 基于 Aws Lambda 和 Chrome 的屏幕截图 API. 处理整页，捕获时间，视口尺寸，...
  * [microlink.io](https://microlink.io/)  – 它将任何网站转换为数据，例如元标签规范化、美容链接预览、抓取功能或屏幕截图即服务. 每天 250 个请求/天免费.
  * [ScreenshotAPI.net](https://screenshotapi.net/)  - Screenshot API 使用一个简单的 API 调用来生成任何网站的屏幕截图. 构建以扩展并托管在 Google Cloud 上. 每月提供 100 张免费屏幕截图.
  * [screenshotlayer.com](https://screenshotlayer.com/)  — 捕获任何网站的高度可定制的快照. 每月免费 100 张快照
  * [screenshotmachine.com](https://www.screenshotmachine.com/) — 每月捕捉 100 张快照、png、gif 和 jpg，包括全长捕捉，而不仅仅是主页
  * [PhantomJsCloud](https://PhantomJsCloud.com)  — 浏览器自动化和页面渲染. 免费套餐每天最多提供 500 页. 自 2017 年以来的免费套餐.
  * [Webshrinker.com](https://webshrinker.com)  — Web Shrinker 提供网站截图和域智能 API 服务. 每月免费 100 个请求.


## Browser based hardware emulation written in Javascript

  * [JsLinux](https://bellard.org/jslinux) — 一个非常快的 x86 虚拟机，能够运行 Linux 和 Windows 2k.
  * [Jor1k](http://s-macke.github.io/jor1k/demos/main.html) — 能够在网络支持下运行 Linux 的 OpenRISC 虚拟机.
  * [v86](https://copy.sh/v86) — 能够直接在浏览器中运行 Linux 和其他操作系统的 x86 虚拟机.


## Privacy Management
  * [Bearer](https://www.bearer.sh/)  - 通过审计和持续工作流程帮助通过设计实现隐私，以便组织遵守 GDPR 和其他法规. 免费套餐仅限于较小的团队和 SaaS 版本.
  * [Osano](https://www.osano.com/)  - 同意管理和合规平台，包括从 GDPR 表示到 cookie 横幅的所有内容. 免费套餐提供基本功能.
  * [Iubenda](https://www.iubenda.com/)  - 隐私和 cookie 政策以及同意管理. 免费套餐提供有限的隐私和 cookie 政策以及 cookie 横幅.
  * [Cookiefirst](https://cookiefirst.com/)  - Cookie 横幅、审核和多语言同意管理解决方案. 免费套餐提供一次性扫描和单个横幅.
  * [Ketch](https://www.ketch.com/)  - 同意管理和隐私框架工具. 免费套餐提供大多数功能，但访问者数量有限.


## Miscellaneous

  * [Smartcar API](https://smartcar.com) - 用于汽车定位、获取油箱、电池电量、里程表、解锁/锁定车门等的 API.
  * [Blynk](https://blynk.io)  — 带有 API 的 SaaS，用于控制、构建和评估 IoT 设备. 包含 5 台设备的免费开发者计划、免费云和数据存储. 移动应用程序也可用.
  * [Bricks Note Calculator](https://free.getbricks.app/) - 带有强大的内置多行计算器的笔记应用程序 (PWA).
  * [Carbon.now.sh](https://carbon.now.sh)  - 以美观的截图式图像格式创建和共享代码片段. 通常用于在 Twitter 或博客文章上美观地共享/炫耀代码片段.
  * [Code Time](https://www.software.com/code-time) - VS Code、Atom、IntelliJ、Sublime Text 等中时间跟踪和编码指标的扩展.
  * [ConfigCat](https://configcat.com)  - 跨平台功能标志服务. 适用于所有主要语言的 SDK. 免费计划每月最多 10 个标志、2 个环境、1 个产品和 500 万个请求. 无限的用户席位. 学生每月免费获得 100 个标志和 1 亿个请求.
  * [datelist.io](https://datelist.io)  - 在线预订/预约调度系统. 每月最多免费预订 5 次，包括 1 个日历
  * [docsapp.io](https://www.docsapp.io/) — 最简单的发布文档的方式，开源免费
  * [Elementor](https://elementor.com)  — WordPress 网站建设者. 免费计划提供 40 多个基本小工具.
  * [Form2Channel](https://form2channel.com)  — 在您的网站上放置一个静态 html 表单，并直接接收提交到 Google 表格、电子邮件、Slack、Telegram 或 Http 的提交. 无需编码.
  * [FOSSA](https://fossa.com/) - 针对第三方代码、许可证合规性和漏洞的可扩展的端到端管理.
  * [fullcontact.com](https://www.fullcontact.com/developer/pricing/)  — 通过在您的应用中添加社交个人资料，帮助您的用户更多地了解他们的联系人.  500 次免费 Person API 匹配/月
  * [http2.pro](https://http2.pro) — HTTP/2 协议就绪测试和客户端 HTTP/2 支持检测 API.
  * [JWT Decoder](https://jwt.ssotools.com/) — 用于解码 JWT（JSON 网络令牌）并验证其签名的在线免费工具.
  * [Base64 decoder/encoder](https://devpal.co/base64-decode/) — 用于解码和编码数据的在线免费工具.
  * [newreleases.io](https://newreleases.io/) - 接收有关来自 GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM、Node.js Yarn、Ruby Gems、PHP Packagist、.NET NuGet 的新版本的电子邮件、Slack、Telegram、Discord 和自定义 webhook 的通知， Rust Cargo 和 Docker Hub.
  * [PDFMonkey](https://www.pdfmonkey.io/)  — 在仪表板中管理 PDF 模板，使用动态数据调用 API，下载您的 PDF. 每月提供 1000 个免费文件.
  * [QuickType.io](https://quicktype.io/)  - 从 JSON、模式和 GraphQL 快速自动生成模型/类/类型/接口和序列化程序，以便在任何编程语言中快速安全地处理数据. 将 JSON 转换为任何语言的华丽、类型安全的代码.
  * [ray.so](https://ray.so/) - 为您的代码片段创建精美的图像.
  * [readme.com](https://readme.com/) — 漂亮的文档变得简单，开源免费.
  * [redirection.io](https://redirection.io/) — 用于管理企业、营销和 SEO 的 HTTP 重定向的 SaaS 工具.
  * [redirect.pizza](https://redirect.pizza/)  - 通过 HTTPS 支持轻松管理重定向. 免费计划包括每月 10 个来源和 100.000 次点击.
  * [ReqBin](https://www.reqbin.com/)  — 在线发布 HTTP 请求. 流行的请求方法包括 GET、POST、PUT、DELETE 和 HEAD. 支持标头和令牌认证. 包括用于保存您的请求的基本登录系统.
  * [superfeedr.com](https://superfeedr.com/)  — 实时符合 PubSubHubbub 的提要、导出、分析. 免费少定制
  * [SurveyMonkey.com](https://www.surveymonkey.com)  — 创建在线调查. 在线分析结果. 免费计划每项调查仅允许 10 个问题和 100 个回复.
  * [videoinu](https://videoinu.com) — 在线创建和编辑屏幕录像和其他视频.
  * [RandomKeygen](https://randomkeygen.com/) - 一款适用于移动设备的免费工具提供各种随机生成的密钥和密码，您可以使用它们来保护任何应用程序、服务或设备.
  * [Cronhooks](https://cronhooks.io/)  - 使用 api 和 web 应用程序安排一次或重复 webhook. 免费计划允许 1 个 webhook 计划.
  * [Hook Relay](https://www.hookrelay.dev/)  - 为您的应用程序添加 webhook 支持，无需麻烦：为您完成排队、退避重试和日志记录. 免费计划每天有 100 次交付、14 天保留期和 3 个挂钩端点.
  * [Format Express](https://www.format-express.dev) - JSON/XML/SQL 的即时在线格式化程序.


## Remote Desktop Tools

  * [Getscreen.me](https://getscreen.me) — 2 台设备免费，会话数量和持续时间没有限制
  * [Apache Guacamole™](https://guacamole.apache.org/) — 开源无客户端远程桌面网关


## Other Free Resources

  * [education.github.com](https://education.github.com/pack)  — 为学生收集免费服务. 需要注册
  * [eu.org](https://nic.eu.org)  — 免费 eu.org 域. 请求通常在 14 天内获得批准.
  * [js.org](https://js.org) - GitHub Pages 的免费 js.org 域
  * [pp.ua](https://nic.ua/) — 免费 pp.ua 域名.
  * [Framacloud](https://degooglisons-internet.org/en/list/) — 法国非营利组织的免费/自由开源软件和 SaaS 列表 [Framasoft](https://framasoft.org/en/).
  * [getawesomeness](https://getawesomeness.herokuapp.com) — 从 GitHub 中检索所有令人惊叹的精彩内容......必看
  * [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) — 面向开发人员的免费开源软件中心.
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program)  — 获取为 Microsoft 365 平台构建解决方案所需的免费沙箱、工具和其他资源. 订阅期为 90 天 [Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5)  （Windows 除外）这是可再生的. 如果您积极参与开发（使用遥测数据和算法测量），它会更新.
  * [RedHat for Developers](https://developers.redhat.com)  — 免费访问 Red Hat 产品，包括 RHEL、OpenShift、CodeReady 等，专供开发人员使用. 仅限个人计划. 还提供免费电子书以供参考.
  * [smsreceivefree.com](https://smsreceivefree.com/) — 提供免费的临时和一次性电话号码.
  * [simplebackups.io](https://simplebackups.io/)  — 直接存储在云存储提供商（AWS、DigitalOcean、Backblaze...）中的服务器和数据库（MySQL、PostgreSQL、MongoDB）的备份自动化服务. 提供 1 个备份的免费计划.
  * [SnapShooter](https://snapshooter.com/)  — 适用于 DigitalOcean、AWS、LightSail、Hetzner 和 Exoscale 的备份解决方案，支持将数据库、文件系统和应用程序直接备份到基于 s3 的存储. 为一项资源提供每日备份的免费计划.
  * [thedev.id](https://thedev.id) — 为开发人员提供的免费 thedev.id 子域.
  * [Themeselection](https://themeselection.com/) — 精选高品质、现代设计、专业且易于使用的免费管理仪表板模板，
HTML 主题和 UI 套件可更快地创建您的应用程序！
  * [Web.Dev](https://web.dev/measure/) — 这是一款免费工具，可让您查看网站的性能并改进 SEO 以在搜索引擎中获得更高的排名.
  * [SmallDev.tools](https://smalldev.tools/)  — 为开发人员提供的免费工具，允许您编码/解码各种格式、缩小 HTML/CSS/Javascript、美化、以 JSON/CSV 和多种其他格式生成虚假/测试真实数据集以及更多功能. 带有令人愉快的界面.
