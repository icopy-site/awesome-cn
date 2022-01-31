<div class="github-widget" data-repo="ripienaar/free-for-dev"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## free-for.dev

开发人员和开源作者现在拥有大量提供免费层级的服务，但很难找到所有这些服务来做出明智的决定.

这是为开发人员提供免费套餐的软件（SaaS、PaaS、IaaS 等）和其他产品的列表.

The scope of this particular list is limited to things that infrastructure developers (System Administrator, DevOps Practitioners, etc.) are likely to find useful. We love all the free services out there, but it would be good to keep it on topic. It's a bit of a grey line at times so this is a bit opinionated; do not be offended if I do not accept your contribution.

此列表是 1000 多人的 Pull Requests、评论、想法和工作的结果. 您也可以通过发送来提供帮助 [Pull Requests](https://github.com/ripienaar/free-for-dev) 添加更多服务或删除其产品已更改或已停用的服务.

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

*NOTE:* This list is only for as-a-Service offerings, not for self-hosted software. For a service to be eligible it has to offer a free tier and not just a free trial. If the free tier is time-bucketed it has to be for at least a year. We also consider the free tier from a security perspective, so SSO is fine but I will not accept services that restrict TLS to paid-only tiers.

目录
=================


## Major Cloud Providers

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 每天 28 个前端实例小时，每天 9 个后端实例小时
    * Cloud Firestore - 1GB 存储，50,000 次读取，20,000 次写入，每天 20,000 次删除
    * Compute Engine - 1 non-preemptible e2-micro, 30GB HDD, 5GB snapshot storage (restricted to certain regions), 1 GB network egress from North America to all region destinations (excluding China and Australia) per month
    * 云存储 - 5GB、1GB 网络出口
     * Cloud Shell - 具有 5GB 持久存储的基于 Web 的 Linux shell/基本 IDE. 每周 60 小时限制
    * Cloud Pub/Sub - 10GB of messages per month
    * Cloud Functions - 每月 200 万次调用（包括后台和 HTTP 调用）
    * Cloud Run - 每月 200 万次请求、360,000 GB 秒内存、180,000 秒 vCPU 计算时间、每月从北美的 1 GB 网络出口
    * Google Kubernetes Engine - No cluster management fee for one zonal cluster. Each user node is charged at standard Compute Engine pricing
    * BigQuery - 1 TB of querying per month, 10 GB of storage each month
    * Cloud Build - 120 build-minutes per day
    * Cloud Source Repositories - Up to 5 Users, 50 GB Storage, 50 GB Egress
    * Full, detailed list - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * Amazon CloudFront - 1TB egress per month
    * Amazon DynamoDB - 25GB NoSQL DB
    * Amazon EC2 - 100GB aggregated egress per month
    * Amazon EC2 - t2.micro 或 t3.micro 每月 750 小时
    * Amazon EBS - 每月 30GB 通用型 (SSD) 或磁性
    * Amazon ELB - 750 hours per month
    * Amazon Lambda - 每月 100 万次请求
    * Amazon SNS - 每月 100 万次发布
    * Amazon SES - 62.000 messages per month
    * Amazon Cloudwatch - 10 个自定义指标和 10 个警报
    * Amazon Glacier - 10GB long-term object storage
    * Amazon SQS - 1 million messaging queue requests
    * Amazon CodeBuild - 100min of build time per month
    * Amazon CodeCommit - 每月 5 个活跃用户
    * Amazon CodePipeline - 每月 1 个活动管道
    * 完整、详细的列表 - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1 个 B1S Linux 虚拟机，1 个 B1S Windows 虚拟机
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 web, mobile or API apps
    * [Functions](https://azure.microsoft.com/services/functions/) - 每月 100 万次请求
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - Enable fast, easy, and lean dev-test environments
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 objects
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 50,000 monthly stored users
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 个活跃用户，无限的私人 Git 存储库
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10 个免费的并行作业，时间不受限制，适用于 Linux、macOS 和 Windows 的开源
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 8,000 messages per day
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1 free public load balanced IP (VIP)
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 100 万条推送通知
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 5GB egress per month
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 5GB 存储和 400 RU 的预置吞吐量
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) — Build, deploy and host static apps and serverless functions, with free SSL, Authentication/Authorization and custom domains
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS File or Blob storage
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML APIs (Computer Vision, Translator, Face detection, Bots...) with free tier including limited transactions
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - 基于人工智能的搜索和索引服务，10,000 份文档免费
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - Managed Kubernetes service, free cluster management
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 100K 操作/月
    * Full, detailed list - [https://azure.microsoft.com/free/](https://azure.microsoft.com/free/)

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * 计算 - 2 个基于 x64，每个具有 1 GB RAM，4 个基于 Arm 的 Ampere A1 内核和 24 GB 内存，可用作一个 VM 或最多 4 个 VM
    * 块卷 - 4 个卷，总共 200 GB（用于计算）
    * Object Storage - 10 GB
    * Load balancer - 1 instance with 10 Mbps
    * 数据库 - 2 个数据库，每个 20 GB
    * 监控 - 5 亿个摄取数据点，10 亿个检索数据点
    * Bandwidth - 10 TB egress per month, speed limited to 50 Mbps on x64 based VM, 500 Mbps * core count on ARM based VM
    * 公共 IP - 2 个 IPv4 用于 VM，1 个 IPv4 用于负载平衡器
    * Notifications - 1 million delivery options per month, 1000 emails sent per month
    * Full, detailed list - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloud Functions - 每月执行 500 万次
    * 对象存储 - 每月 25GB
    * Cloudant database - 1 GB of data storage
    * Db2 数据库 - 100MB 数据存储
    * API Connect - 每月 50,000 次 API 调用
    * Availability Monitoring - 3 million data points per month
    * Log Analysis - 500MB of daily log
    * 完整的详细列表 - https://www.ibm.com/cloud/free/


## Cloud management solutions
  * [Brainboard](https://www.brainboard.co) - 从端到端可视化构建和管理云基础架构的协作解决方案.
  * [terraform.io](https://www.terraform.io/) — Terraform Cloud. Free remote state management and team collaboration for teams up to 5 users.


## Source Code Repos

  * [Bitbucket](https://bitbucket.org/) — Unlimited public and private Git repos for up to 5 users with Pipelines for CI/CD
  * [chiselapp.com](http://chiselapp.com/) — Unlimited public and private Fossil repositories
  * [codebasehq.com](https://www.codebasehq.com/) — One free project with 100 MB space and 2 users
  * [Codeberg.org](https://codeberg.org/) - Unlimited public and private Git repos for free and open-source projects. Static website hosting with [Codeberg Pages](https://codeberg.page/).
  * [Gitea.com](https://www.gitea.com/) - 无限的公共和私人 Git 存储库
  * [GitGud](https://gitgud.io) — Unlimited private and public repositories. Free forever. Powered by GitLab & Sapphire. CI/CD not provided.
  * [GitHub](https://github.com/) — Unlimited public repositories and unlimited private repositories (with unlimited collaborators). Apart from this some other free services(there are much more but we list the main ones here) provided are :
       - [CI/CD](https://github.com/features/actions)(Free for Public Repos, 2000 min/month for private repos free)
       - [Static Website Hosting](https://pages.github.com) (Free for Public Repos)
       - [Package Hosting & Container Registry](https://github.com/features/packages) （公共存储库免费，500 MB 存储空间和 CI/CD 之外的 1GB 带宽免费用于私人存储库）
       - 项目管理和问题跟踪.
  * [gitlab.com](https://about.gitlab.com/) — Unlimited public and private Git repos with unlimited collaborators. Also offers the following features :
       - [CI/CD](https://about.gitlab.com/product/continuous-integration) (Free for Public Repos, 400 mins/month for private repos)
       - Static Sites with [GitLab Pages](https://about.gitlab.com/product/pages).
       - 每个 repo 限制为 10 GB 的容器注册表.
       - 项目管理和问题跟踪.
  * [heptapod.net](https://foss.heptapod.net/) — Heptapod 是 GitLab 社区版的友好分支，为 Mercurial 提供支持
  * [ionicframework.com](https://ionicframework.com/appflow) - Repo and tools to develop applications with Ionic, also you have an ionic repo
  * [NotABug](https://notabug.org) — NotABug.org is a free-software code collaboration platform for freely licensed projects, Git-based
  * [OSDN](https://osdn.net/) - OSDN.net 是为开源软件开发人员提供的免费服务，提供 SVN/Git/Mercurial/Bazaar/CVS 存储库等.
  * [Pagure.io](https://pagure.io) — Pagure.io is a free and open source software code collaboration platform for FOSS-licensed projects, Git-based
  * [perforce.com](https://www.perforce.com/products/helix-teamhub) — Free 1GB Cloud and  Git, Mercurial, or SVN repositories.
  * [pijul.com](https://pijul.com/)  - 无限免费和开源的分布式版本控制系统. 它的显着特点是建立在完善的补丁理论基础上，易于学习和使用，真正的分布式. 解决了 git/hg/svn/darcs 的很多问题.
  * [plasticscm.com](https://plasticscm.com/) — Free for individuals, OSS and nonprofit organizations
  * [projectlocker.com](https://projectlocker.com) — 一个 50 MB 空间的免费私人项目（Git 和 Subversion）
  * [RocketGit](https://rocketgit.com)  — 基于 Git 的存储库托管. 无限的公共和私人存储库.
  * [savannah.gnu.org](https://savannah.gnu.org/) - Serves as a collaborative software development management system for free Software projects (for GNU Projects)
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - 作为自由软件项目（非 GNU 项目）的协作软件开发管理系统


## APIs, Data and ML

  * [IP.City](https://ip.city) — 100 free IP geolocation requests per day
  * [Abstract API](https://www.abstractapi.com) — 适用于各种用例的 API 套件，包括 IP 地理定位、性别检测甚至电子邮件验证.
  * [algorithmia.com](https://algorithmia.com/) — Host algorithms for free. Includes free monthly allowance for running algorithms. Now with CLI support.
  * [Apify](https://www.apify.com/) — Web scraping and automation platform to create an API for any website and extract data. Ready-made scrapers, integrated proxies, and custom solutions. Free plan with $5 platform credits included every month.
  * [API Mocha](https://apimocha.com) - Completely free online API mocking for testing and prototyping.  Make up to 500 requests per day, fully customizable API responses, download mock rules as a Postman collection.
  * [APITemplate.io](https://apitemplate.io) - Auto-generate images and PDF documents with a simple API or automation tools like Zapier & Airtable. No CSS/HTML required. Free plan comes with 50 images/month and 3 templates.
  * [Atlas toolkit](https://atlastk.org/)  - 用于开发可立即访问的单页 Web 应用程序的轻量级库. 适用于 Java、Node.js、Perl、Python 和 Ruby.
  * [Beeceptor](https://beeceptor.com)  - 在几秒钟内模拟一个休息 API，伪造 API 响应等等. 每天免费 50 个请求，公共仪表板，开放端点（任何拥有仪表板链接的人都可以查看请求和响应）.
  * [bigml.com](https://bigml.com/)  — 托管机器学习算法. 无限的免费开发任务，16 MB 数据/任务的限制.
  * [Bruzu](https://bruzu.com/) — Automate Image production. Generate tons of Image variants with API, Integrations or nocode sheet. API is FREE with watermark.
  * [Calendarific](https://calendarific.com)  - 超过 200 个国家的企业级公共假期 API 服务. 免费计划包括每月 1000 次通话.
  * [Clarifai](https://www.clarifai.com)  — 用于自定义人脸识别和检测的图像 API. 能够训练人工智能模型. 免费计划每月有 5000 个电话.
  * [Cloudmersive](https://cloudmersive.com/) — Utility API platform with full access to expansive API Library including Document Conversion, Virus Scanning, and more with 800 calls/month.
  * [Colaboratory](https://colab.research.google.com) — Free web-based Python notebook environment with Nvidia Tesla K80 GPU.
  * [Collect2](https://collect2.com) — Create an API endpoint to test, automate, and connect webhooks. Free plan allows for two datasets, 2000 records, 1 forwarder, and 1 alert.
  * [Conversion Tools](https://conversiontools.io/)  - 用于文档、图像、视频、音频、电子书的在线文件转换器.  REST API 可用.  Node.js、PHP、Python 的库. 支持最大 50 GB 的文件（用于付费计划）. 免费套餐受文件大小和每天转换次数的限制.
  * [Coupler](https://www.coupler.io/) - Data integration tool that syncs between apps. It can create live dashboards and reports, transform and manipulate values, collect and back up insights. The free plan has unlimited users, 100 runs with 1000 rows a month and unlimited integrations.
  * [CraftMyPDF](https://craftmypdf.com) - Auto-Generate PDF documents from reusable templates with a drop-and-drop editor and a simple API. Free plan comes with 100 PDFs/month and 3 templates.
  * [CurlHub](https://curlhub.io) — Proxy service for inspecting and debugging API calls. Free plan includes 10,000 requests per month.
  * [CurrencyScoop](https://currencyscoop.com)  - 用于金融科技应用的实时货币数据 API. 免费计划包括每月 5000 次通话.
  * [Datapane](https://datapane.com) - 用于在 Python 中构建交互式报告并将 Python 脚本和 Jupyter Notebooks 部署为自助服务工具的​​ API.
  * [DB Designer](https://www.dbdesigner.net/) — Cloud based Database schema design and modeling tool with a free starter plan of 2 Database models and 10 tables per model.
  * [DeepAR](https://developer.deepar.ai) — Augmented reality face filters for any platform with one SDK. Free plan provides up to 10 monthly active users (MAU) and tracking up to 4 faces
  * [Deepnote](https://deepnote.com)  - 一种新型的数据科学笔记本.  Jupyter 兼容实时协作并在云中运行. 免费套餐包括无限的个人项目、长达 750 小时的标准硬件和最多 3 名编辑的团队.
  * [Diggernaut](https://www.diggernaut.com/) — Cloud based web scraping and data extraction platform for turning any website to the dataset or to work with it as with an API. Free plan includes 5K page requests monthly.
  * [Disease.sh](https://disease.sh/) — A free API providing accurate data for building the Covid-19 related useful Apps.
  * [dominodatalab.com](https://www.dominodatalab.com) — 支持 Python、R、Spark、Hadoop、MATLAB 等的数据科学.
  * [dreamfactory.com](https://dreamfactory.com/) — Open source REST API backend for mobile, web, and IoT applications. Hook up any SQL/NoSQL database, file storage system, or external service and it instantly creates a comprehensive REST API platform with live documentation, user management,...
  * [DynaPictures](https://dynapictures.com)  - 设计自动化工具，可让您通过 REST API 动态生成图像. 即时更改颜色、文本、徽标和图像. 免费计划包括每月 30 个生成的图像和 3 个图像模板.
  * [Efemarai](https://efemarai.com) - Testing and debugging platform for ML models and data. Visualize any computational graph. Free 30 debugging sessions per month for developers.
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) - Free web-based HTTP client to send HTTP requests.
  * [Export SDK](https://exportsdk.com) - PDF generator API with drag and drop template editor that also provides an SDK and no-code integrations. Free plan comes with 250 pages per month, unlimited users and three templates.
  * [FraudLabs Pro](https://www.fraudlabspro.com)  — 筛选信用卡支付欺诈的订单交易. 此 REST API 将根据订单的输入参数检测所有可能的欺诈特征. 免费微型计划每月有 500 笔交易.
  * [FreeGeoIP.app](https://freegeoip.app/)  - 完全免费的地理 IP 信息（JSON、CSV、XML）. 无需注册，每小时 15000 次查询的速率限制.
  * [GeoDataSource](https://www.geodatasource.com) — Location search service lookup for city name by using latitude and longitude coordinate. Free API queries up to 500 times per month.
  * [Glitterly](https://glitterly.app/)  - 以编程方式从基本模板生成动态图像.  Restful API 和 nocode 集成. 免费套餐每月提供 50 张图片和 5 个模板.
  * [GoodData](https://www.gooddata.com/)  - 数据即服务 - 创建交互式且富有洞察力的仪表板. 免费层包含 5 个工作区和 100 MB/工作区.
  * [Hookbin](https://hookbin.com/)  - 创建唯一（公共或私有）端点来收集、解析和检查 HTTP 请求. 检查标头、正文、查询字符串、cookie、上传的文件等.对于测试/检查 webhook 很有用. 类似于 RequestBin 和 Webhook.site.
  * [Hoppscotch](https://hoppscotch.io) - 免费、快速、美观的 API 请求生成器。
  * [Hybiscus](https://hybiscus.dev/) - Build pdf reports using a simple declarative API. Free tier includes upto 100 single page reports per month with the ability to customise color pallet and fonts.
  * [Invantive Cloud](https://cloud.invantive.com/)  — 使用 Invantive SQL 或 OData4（通常是 Power BI 或 Power Query）访问 70 多个（云）平台，例如 Exact Online、Twinfield、ActiveCampaign 或 Visma. 包括数据复制和交换. 开发人员和实施顾问的免费计划. 对数据量有限制的特定平台免费.
  * [ipaddress.sh](https://ipaddress.sh) — Simple service to get public IP address in different [formats](https://about.ipaddress.sh/).
  * [Iploka](https://iploka.com/) — IP to Geolocation API - Forever free plan for developers with 10k requests per month limit.
  * [IP Geolocation](https://ipgeolocation.io/) — IP Geolocation API - Forever free plan for developers with 30k requests per month (1k/day) limit.
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) — IP Geolocation API from Abstract - Extensive free plan allowing 200,000 requests per month.
  * [IP2Location](https://www.ip2location.com)  — 免费增值 IP 地理定位服务.  LITE 数据库可免费下载. 将数据库导入服务器，进行本地查询，确定城市、坐标和ISP信息.
  * [ipapi](https://ipapi.co/) - IP Address Location API by Kloudend, Inc - A reliable geolocation API, built on AWS, trusted by Fortune 500. Free tier offers 30k lookups/month (1k/day) without signup. Contact us for a higher limit trial plan.
  * [IPinfo](https://ipinfo.io/) — Fast, accurate, and free (up to 50k/month) IP address data API. Offers APIs with details on geolocation, companies, carriers, IP ranges, domains, abuse contacts, and more. All paid APIs can be trialed for free.
  * [IPFast](https://ip-fast.com/) — Find out your IP Address and related detailed information using the free, fastest and simple lookup tool.
  * [IPList](https://www.iplist.cc) — Lookup details about any IP address, such as Geo IP information, tor addresses, hostnames and ASN details. Free for personal and business users.
  * [BigDataCloud](https://www.bigdatacloud.com/) - Provides fast, accurate and free (Unlimited or up to 10K-50K/month) APIs for modern web like IP Geolocation, Reverse Geocoding, Networking Insights, Email and Phone Validation, Client Info and more.
  * [IPTrace](https://iptrace.io) — An embarrassingly simple API that provides reliable and useful IP geolocation data for your business.
  * [JSON IP](https://getjsonip.com)  — 返回请求它的客户端的公共 IP 地址. 免费层无需注册. 可以使用客户端 JS 直接从浏览器请求使用 CORS 数据. 对于监控客户端和服务器 IP 变化的服务很有用. 无限请求.
  * [konghq.com/](https://konghq.com/) — API Marketplace and powerful tools for private and public APIs. With the free tier, some features are limited such as monitoring, alerting and support.
  * [Kreya](https://kreya.app) — Free gRPC GUI client to call and test gRPC APIs. Can import gRPC APIs via server reflection.
  * [KSoft.Si](https://api.ksoft.si/) — 免费歌词 api 主要针对不和谐机器人.还提供广泛的图像和用户数据库
  * [Lightly](https://www.lightly.ai/)  — 使用正确的数据改进您的机器学习模型. 免费使用多达 1&#39;000 个样本的数据集.
  * [MailboxValidator](https://www.mailboxvalidator.com) — Email verification service using real mail server connection to confirm valid email. Free API plan has 300 verifications per month.
  * [microlink.io](https://microlink.io/)  – 它将任何网站转化为数据，例如元标记标准化、美容链接预览、抓取功能或屏幕截图即服务. 每天 100 个请求/天免费.
  * [monkeylearn.com](https://monkeylearn.com/) — 使用机器学习进行文本分析，每月免费 300 次查询.
  * [MockAPI](https://www.mockapi.io/)  — MockAPI 是一个简单的工具，可让您轻松地模拟 API、生成自定义数据并使用 RESTful 接口对其执行操作.  MockAPI 旨在用作原型设计/测试/学习工具. 每个项目免费 1 个项目/50 个资源.
  * [Mocki](https://mocki.io) - A tool that lets you create mock GraphQL and REST APIs synced to a GitHub repository. Simple REST APIs are free to create and use without signup.
  * [Mocko.dev](https://mocko.dev/) — Proxy your API, choose which endpoints to mock in the cloud and inspect traffic, for free. Speed up your development and integrations tests.
  * [Mocky](https://designer.mocky.io/) - A simple web app to generate custom HTTP responses for mocking HTTP request. Also available as [open source](https://github.com/julien-lafont/Mocky).
  * [reqres.in](https://reqres.in) - A Free hosted REST-API ready to respond to your AJAX requests.
  * [microenv.com](https://microenv.com) —  Create fake REST API for developers with possibility to generate code and app in docker container.
  * [neptune.ai](https://neptune.ai/)  - 记录、存储、显示、组织、比较和查询所有 MLOps 元数据. 个人免费：1 名成员、100 GB 元数据存储、200 小时监控/月
  * [News API](https://newsapi.org)  — 使用代码在网络上搜索新闻，获取 JSON 结果. 开发人员每月免费获得 3,000 个查询.
  * [OCR.Space](https://ocr.space/)  — 一个 OCR API，它解析图像和 pdf 文件，以 JSON 格式返回文本结果. 每月免费 25,000 个请求.
  * [Duply.co](https://duply.co) — Create dynamic images from API & URL, design template once and reuse it. Free tier offers 70 images/month creation from API & URL and Up to 100 through Form.
  * [OpenAPI3 Designer](https://openapidesigner.com/) — 免费直观地创建 Open API 3 定义.
  * [parsehub.com](https://parsehub.com/) — Extract data from dynamic sites, turn dynamic websites into APIs, 5 projects free.
  * [Pixela](https://pixe.la/) - Free daystream database service. All operations are performed by API. Visualization with heat maps and line graphs is also possible.
  * [Postbacks](https://postbacks.io/)  - 稍后请求 HTTP 回调. 注册时有 8,000 个免费请求.
  * [Postman](https://postman.com)  — 使用用于 API 开发的协作平台 Postman，简化工作流程并更快地创建更好的 API. 永久免费使用 Postman 应用程序. 邮递员云功能也永远免费，但有一定的限制.
  * [PrefectCloud](https://www.prefect.io/cloud/) — A complete platform for dataflow automation. All plans include 20,000 free runs every month. That's enough to power ETL for most small businesses.
  * [ProxyCrawl](https://proxycrawl.com/)  — 无需代理、基础设施或浏览器即可抓取网站. 我们为您解决验证码并防止您被阻止. 前 1000 次通话是免费的.
  * [Public-Apis Github Repo](https://github.com/public-apis/public-apis) — A list of free public APIs.
  * [Supportivekoala](http://supportivekoala.com/) <i>— Allows you to autogenerate images by your input via templates.</i> <b>— 允许您通过模板输入自动生成图像。</b> <i>Free plan allows you to create up to 100 images per week.</i><b>免费计划允许您每周创建多达 100 张图像。</b>
  * [QuickMocker](https://quickmocker.com/)  — 在您自己的子域下管理在线虚假 API 端点，将请求转发到 localhost URL 以进行 webhook 开发和测试，使用 RegExp 和多种 HTTP 方法作为 URL 路径，优先考虑端点，100 多个短代码（动态或虚假响应值）用于响应模板，从 JSON 格式的 OpenAPI (Swagger) 规范导入，代理请求，通过 IP 地址和授权标头限制端点. 免费帐户提供 1 个随机子域、10 个端点、5 个 RegExp URL 路径、每个端点 50 个短代码、每天 100 个请求、请求日志中的 50 条历史记录.
  * [RequestBin.com](https://requestbin.com)  — 创建一个可以向其发送 HTTP 请求的免费端点. 发送到该端点的任何 HTTP 请求都将与相关的有效负载和标头一起记录，以便您可以观察来自 webhook 和其他服务的请求.
  * [restlet.com](https://restlet.com/products/apispark/) — APISpark 使任何 API、应用程序或数据所有者能够通过直观的浏览器界面在几分钟内成为 API 提供者.
  * [Roboflow](https://roboflow.com) - create and deploy a custom computer vision model with no prior machine learning experience required. Free tier includes up to 1,000 free source images.
  * [ROBOHASH](https://robohash.org/) - Web service to generate unique (cool :) images from any text.
  * [Scraper.AI](https://scraper.ai)  - SaaS 可将任何网站转变为可消耗的 API，供您构建. 每月免费 50 次提取和 10000 次 API 调用.
  * [Scraper's Proxy](https://scrapersproxy.com)  — 用于抓取的简单 HTTP 代理 API. 匿名抓取，而不必担心限制、阻止或验证码. 每月前 100 次成功抓取免费，包括 javascript 渲染（如果您联系支持人员可以获得更多）.
  * [ScrapingAnt](https://scrapingant.com/)  — 无头 Chrome 抓取 API 和免费检查代理服务.  Javascript 渲染、高级轮换代理、避免验证码. 提供免费计划.
  * [ScraperBox](https://scraperbox.com/) — Undetectable web scraping API using real Chrome browsers and proxy rotation. Use a simple API call to scrape any web page. Free plan has 1000 requests per month.
  * [ScrapingDog](https://scrapingdog.com/)  — Scrapingdog 处理数百万个代理、浏览器和验证码，通过单个 API 调用为您提供任何网页的 HTML. 它还提供适用于 Chrome 和 Firefox 的 Web Scraper 以及用于即时抓取需求的软件. 提供免费计划.
  * [scrapinghub.com](https://scrapinghub.com)  — 使用可视化界面和插件进行数据抓取. 免费计划包括在共享服务器上无限制抓取.
  * [ScrapingNinja](https://www.scrapingninja.co/) — Handle JS rendering, Chrome Headless, Proxy rotation and CAPTCHAs solving all in one place. The first 1000 are free of charge, no credit card required.
  * [Sheetson](https://sheetson.com)  - 立即将任何 Google 表格转换为 RESTful API. 提供免费计划.
  * [shrtcode API](https://shrtco.de/docs) - Free URL Shortening API without authorization and no request limits.
  * [SerpApi](https://serpapi.com/)  - 实时搜索引擎抓取 API. 返回 Google、Youtube、Bing、百度、沃尔玛和许多其他引擎的结构化 JSON 结果. 免费计划包括每月 100 次成功的 API 调用.
  * [Similar Words API](https://word-simi.herokuapp.com/) — 一个查找相似词的 API，拥有大约 400 万个词的词汇.
  * [Sofodata](https://www.sofodata.com/) - Create secure RESTful APIs from CSV files. Upload a CSV file and instantly access the data via its API allowing faster application development. Free plan includes 2 APIs and 2,500 API calls per month. No credit card required.
  * [tamber](https://tamber.com)  — 在您的应用中加入深度学习驱动的推荐. 免费 5k 月活跃用户.
  * [Time Door](https://timedoor.io) - 时间序列分析 API.
  * [TinyMCE](https://www.tiny.cloud) - rich text editing API. Core features free for unlimited usage.
  * [Unixtime](https://unixtime.co.za) - 将 Unixtime 转换为 DateTime 的免费 API，反之亦然.
  * [Webhook.site](https://webhook.site) - Easily test HTTP webhooks with this handy tool that displays requests instantly.
  * [wit.ai](https://wit.ai/) — 面向开发人员的 NLP.
  * [wolfram.com](http://wolfram.com/language/) — Built-in knowledge-based algorithms in the cloud.
  * [wrapapi.com](https://wrapapi.com/)  — 将任何网站变成参数化 API. 每月 30k API 调用.
  * [ZenRows](https://www.zenrows.com/) — Web Scraping API & proxy server that bypasses any anti-bot solution while offering javascript rendering, rotating proxies, and geotargeting. Free tier of 1000 API calls.
  * [Zenscrape](https://zenscrape.com/web-scraping-api) — Web scraping API with headless browsers, residentials IPs and simple pricing. 1000 free API calls/month, extra free credits for students and non-profits.
  * [ip-api](https://ip-api.com) — IP Geolocation API，免费用于非商业用途，无需 API 密钥，免费计划的同一 IP 地址限制为 45 次/分钟.
  * [WebScraping.AI](https://webscraping.ai)  - 带有内置解析、Chrome 渲染和代理的简单 Web Scraping API. 每月 2000 次免费 API 调用.
  * [Zipcodebase](https://zipcodebase.com)  - 免费邮政编码 API，访问全球邮政编码数据.  10000 个免费请求/月.
  * [EVA](http://eva.pingutil.com/) - Free email validator API, which helps to identify whether an email is disposable and having valid MX records.
  * [happi.dev](https://happi.dev) - Freemium api services collection (Music, Exchange Rate, Key value store, Language Detection, Password Generator, QRCode Generator, Lyrics). 8000 free API calls per month.
  * [huggingface.co](https://huggingface.co) - Build, train and deploy NLP models for Pytorch, TensorFlow, and JAX. Free up to 30k input characters/mo.
  * [vatcheckapi.com](https://vatcheckapi.com)  - 简单且免费的增值税号码验证 API. 每月 500 个免费请求.
  * [numlookupapi.com](https://numlookupapi.com) - 免费电话号码验证 API - 每月 10 万次免费请求.
  * [geojs.io](https://www.geojs.io/) - Highly available REST/JSON/JSONP IP Geolocation lookup API.


## Artifact Repos

 * [Artifactory](https://jfrog.com/start-free/)  - 支持多种包格式的工件存储库，如 Maven、Docker、Cargo、Helm、PyPI、CocoaPods 和 GitLFS. 包括包扫描工具 XRay 和 CI/CD 工具 Pipelines（以前称为 Shippable），每月免费提供 2,000 CI/CD 分钟.
 * [central.sonatype.org](https://central.sonatype.org) — The default artifact repository for Apache Maven, SBT and other build systems.
 * [cloudrepo.io](https://cloudrepo.io) - Cloud based, private and public, Maven and PyPi repositories. Free for open source projects.
 * [cloudsmith.io](https://cloudsmith.io)  — 适用于 Java/Maven、RedHat、Debian、Python、Ruby、Vagrant 等的简单、安全和集中的存储库服务. 免费层 + 免费用于开源.
 * [jitpack.io](https://jitpack.io/) — GitHub 上 JVM 和 Android 项目的 Maven 存储库，公共项目免费.
 * [packagecloud.io](https://packagecloud.io/users/new?plan=free_usage_plan) — Easy to use repository hosting for: Maven, RPM, DEB, PyPi, NPM, and RubyGem packages (has free tier).
 * [repsy.io](https://repsy.io) — 1 GB Free private/public Maven Repository.


## Tools for Teams and Collaboration

  * [3Cols](https://3cols.com/) - A free cloud based code snippet manager for personal and collaborative code.
  * [Bitwarden](https://bitwarden.com) — 个人、团队和企业组织存储、共享和同步敏感数据的最简单、最安全的方式.
  * [Braid](https://www.braidchat.com/)  — 专为团队设计的聊天应用程序. 对公共访问组、无限用户、历史记录和集成免费. 它还提供自托管的开源版本.
  * [cally.com](https://cally.com/) — Find the perfect time and date for a meeting. Simple to use, works great for small and large groups.
  * [Calendly](https://calendly.com) — Calendly is the tool for connecting and scheduling meetings. Free plan provides 1 Calendar connection per user and Unlimited meetings. Desktop and Mobile apps also provided.
  * [Discord](https://discord.com/)  — 与公共/私人房间聊天.  Markdown 文本、语音、视频和屏幕共享功能. 无限用户免费.
  * [Telegram](https://telegram.org/) — Telegram is for everyone who wants fast and reliable messaging and calls. Business users and small teams may like the large groups, usernames, desktop apps and powerful file sharing options.
  * [Duckly](https://duckly.com/)  — 与您的团队实时交谈和协作. 与任何 IDE 配对编程、终端共享、语音、视频和屏幕共享. 小团队免费.
  * [evernote.com](https://evernote.com/) — Tool for organizing information. Share your notes and work together with others
  * [Fibery](https://fibery.io/)  — 连接的工作空间平台. 单用户免费，最多 2 GB 磁盘空间.
  * [Filestash](https://www.filestash.app) — A Dropbox-like file manager that connects to a range of protocols and platforms: S3, FTP, SFTP, Minio, Git, WebDAV, Backblaze, LDAP and more.
  * [flock.com](https://flock.com)  — 一种更快的团队沟通方式. 免费无限的消息、渠道、用户、应用程序和集成
  * [Flowdash](https://flowdash.com/)  — 自动化业务工作流程. 免费套餐最多可容纳 3 个用户、1000 个任务和 3 个工作流.
  * [flowdock.com](https://www.flowdock.com/) — Chat and inbox, free for teams up to 5
  * [GitDailies](https://gitdailies.com) - Daily reports of your team's Commit and Pull Request activity on GitHub. Includes Push visualizer, peer recognition system, custom alert builder. Free tier has unlimited users, 3 repos, 3 alert configs.
  * [gitter.im](https://gitter.im/) — Chat, for GitHub. Unlimited public and private rooms, free for teams up to 25
  * [hangouts.google.com](https://hangouts.google.com/) — 一个可以免费进行所有对话的地方，需要一个 Google 帐户
  * [HeySpace](https://hey.space) - Task management tool with chat, calendar, timeline and video calls. Free for up to 5 users.
  * [helplightning.com](https://www.helplightning.com/) — Help over video with augmented reality. Free without analytics, encryption, support
  * [ideascale.com](https://ideascale.com/) — Allow clients to submit ideas and vote, free for 25 members in 1 community
  * [Igloo](https://www.igloosoftware.com/) — 用于共享文档、博客和日历等的内部门户.最多可供 10 位用户免费使用.
  * [Keybase](https://keybase.io/) — Keybase is a cool FOSS alternative to Slack, it keeps everyone's chats and files safe, from families to communities to companies.
  * [Google Meet](https://meet.google.com/)  — 使用 Google Meet 满足您企业的在线视频会议需求.  Meet 提供安全、易于加入的在线会议.
  * [/meet for Slack](https://meetslack.com) - Start Google Meetings directly from Slack by using /meet in any channel, group or DM. Free without any limitations.
  * [MarkUp](https://www.markup.io/) — MarkUp lets you collect feedback directly on top of your websites, PDFs and images.
  * [meet.jit.si](https://meet.jit.si/) — One click video conversations, screen sharing, for free
  * [Microsoft Teams](https://products.office.com/microsoft-teams/free) — Microsoft Teams is a chat-based digital hub that brings conversations, content, and apps together in one place all from a single experience. Free for up to 500k users.
  * [Miro](https://miro.com/) - Scalable, secure, cross-device and enterprise-ready team collaboration whiteboard for distributed teams. With freemium plan.
  * [nootiz](https://www.nootiz.com/) - The go-to tool for gathering and managing visual feedback on any website
  * [Notion](https://www.notion.so/)  - Notion 是一款支持 Markdown 的笔记和协作应用程序，它还集成了任务、wiki 和数据库. 该公司将该应用程序描述为用于记笔记、项目管理和任务管理的一体化工作区. 除了跨平台应用程序外，它还可以通过大多数网络浏览器访问.
  * [Nuclino](https://www.nuclino.com)  - 一个轻量级的协作 wiki，包含您团队的所有知识、文档和笔记. 具有所有基本功能的免费计划，最多 50 个项目，5GB 总存储空间.
  * [PageShare.dev](https://www.pageshare.dev) - Adds visual reviews capabilities into GitHub Pull Requests with no need to deploy websites. Free for up to 10 pages each month and 100MB of storage in total.
  * [Pendulums](https://pendulums.io/) - Pendulums 是一款免费的时间跟踪工具，它通过易于使用的界面和有用的统计数据帮助您以更好的方式管理您的时间.
  * [Raindrop.io](https://raindrop.io)  - 适用于 macOS、Windows、Android、iOS 和 Web 的私密且安全的书签应用程序. 免费无限书签和协作.
  * [element.io](https://element.io/)  — 一个基于 Matrix 的去中心化开源通信工具. 群聊、直接消息、加密文件传输、语音和视频聊天以及与其他服务的轻松集成.
  * [Rocket.Chat](https://rocket.chat/) - 团队共享收件箱，安全、无限制和开源.
  * [seafile.com](https://www.seafile.com/)  — 私有或云存储、文件共享、同步、讨论. 私人版已满. 云版本只有 1 GB
  * [Slab](https://slab.com/) <i>— A modern knowledge management service for teams.</i> <b>— 面向团队的现代知识管理服务。</b> <i>Free for up to 10 users.</i><b>最多 10 个用户免费。</b>
  * [slack.com](https://slack.com/) — Free for unlimited users with some feature limitations
  * [Spectrum](https://spectrum.chat/) - Create public or private communities for free.
  * [StatusPile](https://www.statuspile.com/)  - 状态页面的状态页面. 跟踪上游提供商的状态页面.
  * [talky.io](https://talky.io/)  — 免费群视频聊天. 匿名的. 点对点. 无需插件、注册或付款
  * [Tefter](https://tefter.io) - Bookmarking app with a powerful Slack integration. Free for open-source teams.
  * [TeleType](https://teletype.oorja.io/) — share terminals, voice, code, whiteboard and more. no sign-in required, end-to-end encrypted collaboration for developers.
  * [TimeCamp](https://www.timecamp.com/) - Free time tracking software for unlimited users. Easily integrates with PM tools like Jira, Trello, Asana, etc.
  * [Tree Schema](https://treeschema.com/) — Data catalog and metadata management with APIs to manage data lineage as code. Free for teams of up to 5 users.
  * [twist.com](https://twist.com)  — 一个异步友好的团队通信应用程序，其中对话保持有条理和主题. 提供免费和无限计划. 为符合条件的团队提供折扣.
  * [BookmarkOS.com](https://bookmarkos.com) - Free all-on-one bookmark manager, tab manager, and task manager in a customizable online desktop with folder collaboration.
  * [typetalk.com](https://www.typetalk.com/) — Share and discuss ideas with your team through instant messaging on the web or on your mobile
  * [Tugboat](https://tugboat.qa)  - 预览每个拉取请求，自动化和按需. 对所有人免费，为非营利组织提供免费的 Nano 层级.
  * [whereby.com](https://whereby.com/) — 一键视频对话，免费（以前称为appear.in）
  * [vadoo.tv](https://vadoo.tv/) — Video hosting and marketing made simple. Upload videos with a single click. Record, manage, share & more. Free tier provides upto 10 videos, 1 GB storage, 10 GB bandwidth/month
  * [vspace](https://vvv.space/) — Free links manager with private/public spaces, includes slack and google docs integration and chrome plugin.
  * [userforge.com](https://userforge.com/) - Interconnected online personas, user stories and context mapping.  Helps keep design and dev in sync, free for up to 3 personas and 2 collaborators.
  * [wistia.com](https://wistia.com/) — 带有观众分析、高清视频交付和营销工具的视频托管，以帮助了解您的访问者、25 个视频和 Wistia 品牌播放器
  * [wormhol.org](https://www.wormhol.org/)  — 简单的文件共享服务. 与尽可能多的同行共享不超过 5GB 的无限文件.
  * [zoom.us](https://zoom.us/)  — 安全的视频和网络会议，可用的附加组件. 免费限时 40 分钟
  * [shtab.app](https://shtab.app/) - Project management service that makes collaboration in the office and remotely transparent with tracker based on AI.
  * [zdoo.co](https://www.zdoo.co) — With CRM, OA, and Project management suites, zdoo is so powerful for team collaboration. Free cloud version with limited users and space offered, one-month free trial for premium versions.
  * [Zulip](https://zulip.com/) — Real-time chat with unique email-like threading model. Free plan includes 10,000 messages of search history and File storage up to 5 GB. also it provides self-hostable open-source version.
  * [Automate.io](https://automate.io)  - 简单和复杂的自动化工作流程工具，具有 200 多个应用程序集成. 每月 300 次操作和 5 个机器人是免费
  * [robocorp.com](https://robocorp.com) - Open-source stack for powering Automation Ops. Try out Cloud features and implement simple automations for free. Robot work 240 min/month, 10 Assistant runs, Storage of 100 MB.
  * [Fleep.io](https://fleep.io/) — Fleep an alternative to Slack. It has a free plan for small teams with full message history, unlimited 1:1 conversations, 1 group conversation and 1 GB file storage.
  * [Chanty.com](https://chanty.com/)  — Chanty 是 Slack 的另一种选择. 它为小型团队（最多 10 个）提供永久免费计划，具有无限的公共和私人对话、可搜索的历史记录、无限的 1:1 音频通话、无限的语音消息、10 次集成和每个团队 20 GB 的存储空间.


## CMS

  * [acquia.com](https://www.acquia.com/) — Hosting for Drupal sites. Free tier for developers. Free development tools (such as Acquia Dev Desktop) also available
  * [Contentful](https://www.contentful.com/) — Headless CMS. Content management and delivery APIs in the cloud. Comes with one free Community space that includes 5 users, 25K records, 48 Content Types, 2 locales.
  * [Cosmic](https://www.cosmicjs.com/)  — 无头 CMS 和 API 工具包. 开发人员的免费个人计划.
  * [Crystallize](https://crystallize.com)  — 具有电子商务支持的无头 PIM. 内置 GraphQL API. 免费版包括无限用户、1000 个目录项、5 GB/月带宽和 25k/月 API 调用.
  * [DatoCMS](https://www.datocms.com/) - Offers free tier for small projects. DatoCMS is a GraphQL based CMS. On the lower tier you have 100k/month calls.
  * [Directus](https://directus.io) — Headless CMS. A completely free and open-source platform for managing assets and database content on-prem or in the Cloud. No limitations or paywalls.
  * [Forestry.io/](https://forestry.io/) — Headless CMS. Give your editors the power of Git. Create and edit Markdown-based content with ease. Comes with three free sites that includes 3 editors, Instant Previews. Integrates with blogs hosted on Netlify/GitHubpages/ elsewhere
  * [FrontAid](https://frontaid.io/) — Headless CMS that stores JSON content directly in your own Git repository. No restrictions.
  * [kontent.ai](https://www.kontent.ai)  - 一个内容即服务平台，可为您提供所有无头 CMS 优势，同时为营销人员提供支持. 开发人员计划为 2 个用户提供无限项目，每个用户有 2 个环境、500 个内容项、2 种语言以及交付和管理 API，以及自定义元素支持. 更大的计划可满足您的需求.
  * [Prismic](https://www.prismic.io/) — Headless CMS. Content management interface with fully hosted and scalable API. The Community Plan provides 1 user with unlimited API calls, documents, custom types, assets, and locales. Everything that you need for your next project. Bigger free plans available for Open Content/Open Source projects.
  * [Sanity.io](https://www.sanity.io/) - Platform for structured content that comes with an open-source editing environment and a real-time hosted data store. Unlimited projects. Unlimited admin users, 3 non-admin users, 2 datasets, 500K API CDN requests, 10GB bandwidth, 5GB assets included for free per project.
  * [sensenet](https://sensenet.com) - API-first headless CMS providing enterprise-grade solutions for businesses of all size. The Developer plan provides 3 users, 500 content items, 3 built-in roles, 25+5 content types, fully accessible REST API, document preview generation and Office Online editing.
  * [GraphCMS](https://graphcms.com/) - Offers free tier for small projects. GraphQL first API. Move away from legacy solutions to the GraphQL native Headless CMS - and deliver omnichannel content API first.
  * [Squidex](https://squidex.io/)  - 为小型项目提供免费套餐. 首先是 API/GraphQL. 开源，基于事件溯源（自动处理每一个变化）.


## Code Quality

  * [SoftaCheck](https://www.softacheck.com/) — An online tool that performs static analysis for C/C++ code using open source tools such as cppcheck and clang-tidy and automatically generates code documentation for users using doxygen. This tool is free for use.
  * [beanstalkapp.com](https://beanstalkapp.com/) — A complete workflow to write, review and deploy code), free account for 1 user and 1 repository with 100 MB of storage
  * [browserling.com](https://www.browserling.com/) — 实时交互式跨浏览器测试，在 Vista 下使用 MS IE 9 以 1024 x 768 分辨率免费进行 3 分钟会话
  * [codacy.com](https://www.codacy.com/) — PHP、Python、Ruby、Java、JavaScript、Scala、CSS 和 CoffeeScript 的自动代码审查，对无限的公共和私有存储库免费
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev)  - DevOps 的自动化基础设施即代码审查工具与 GitHub、Bitbucket 和 GitLab（甚至是自托管）集成. 除了标准语言，它还分析 Ansible、Terraform、CloudFormation、Kubernetes 等.  （开源免费）
  * [CodeBeat](https://codebeat.co) — Automated Code Review Platform available for many languages. Free forever for public repositories with Slack & E-mail integration.
  * [codeclimate.com](https://codeclimate.com/)  — 自动代码审查，开源免费和无限的组织拥有的私人回购（最多 4 个合作者）. 对学生和机构也免费.
  * [codecov.io](https://codecov.io/) — 代码覆盖工具 (SaaS)，对开源免费和 1 个免费私人仓库
  * [CodeFactor](https://www.codefactor.io)  — Git 的自动代码审查. 免费版包括无限用户、无限公共存储库和 1 个私人存储库.
  * [codescene.io](https://codescene.io/)  - CodeScene 根据开发人员使用代码的方式确定技术债务的优先级，并可视化团队耦合和系统掌握等组织因素. 开源免费.
  * [coveralls.io](https://coveralls.io/) — Display test coverage reports, free for Open Source
  * [dareboost](https://dareboost.com) - 5 free analysis report for web performance, accessibility, security each month
  * [deepcode.ai](https://www.deepcode.ai)  — DeepCode 基于 AI 发现错误、安全漏洞、性能和 API 问题.  DeepCode 的分析速度使我们能够实时分析您的代码并在您点击 IDE 中的保存按钮时提供结果. 支持的语言有 Java、C/C++、JavaScript、Python 和 TypeScript. 与 GitHub、BitBucket 和 GitLab 集成. 对开源和私人存储库免费，最多可释放 30 名开发人员.
  * [deepscan.io](https://deepscan.io) — Advanced static analysis for automatically finding runtime errors in JavaScript code, free for Open Source
  * [DeepSource](https://deepsource.io/) - DeepSource continuously analyzes source code changes, finds and fixes issues categorized under security, performance, anti-patterns, bug-risks, documentation and style. Native integration with GitHub, GitLab and Bitbucket.
  * [eversql.com](https://www.eversql.com/) — EverSQL - The #1 platform for database optimization. Gain critical insights into your database and SQL queries, auto-magically.
  * [gerrithub.io](https://review.gerrithub.io/) — 免费对 GitHub 存储库进行 Gerrit 代码审查
  * [gocover.io](https://gocover.io/) — Code coverage for any [Go](https://golang.org/) 包裹
  * [goreportcard.com](https://goreportcard.com/) — Code Quality for Go projects, free for Open Source
  * [gtmetrix.com](https://gtmetrix.com/) — Reports and thorough recommendations to optimize websites
  * [holistic.dev](https://holistic.dev/) - The #1 static code analyzer for Postgresql optimization. Performance, security, and architect database issues automatic detection service
  * [houndci.com](https://houndci.com/) — Comments on GitHub commits about code quality, free for Open Source
  * [Imgbot](https://github.com/marketplace/imgbot) — Imgbot is a friendly robot that optimizes your images and saves you time. Optimized images mean smaller file sizes without sacrificing quality. It's free for open source.
  * [Kritika](https://kritika.io/) — Static Code Analysis for Perl with integration for GitHub. Free for unlimited public repositories.
  * [resmush.it](https://resmush.it)  — reSmush.it 是一个提供图像优化的免费 API.  reSmush.it 已在 Wordpress、Drupal 或 Magento 等最常见的 CMS 上实现.  reSmush.it 是最常用的图像优化 API，已经处理了超过 70 亿张图像，并且仍然是免费的.
  * [insight.sensiolabs.com](https://insight.sensiolabs.com/) — Code Quality for PHP/Symfony projects, free for Open Source
  * [lgtm.com](https://lgtm.com) — Continuous security analysis for Java, Python, JavaScript, TypeScript, C#, C and C++, free for Open Source
  * [Moderne.io](https://app.moderne.io) — Automatic source code refactoring. Moderne offers framework migrations, code analysis with remediation, and unrivaled code transformation at scale, so developers can spend their time building new things instead of maintaining the old. Free for Open Source.
  * [reviewable.io](https://reviewable.io/) — Code review for GitHub repositories, free for public or personal repos
  * [parsers.dev](https://parsers.dev/) - 抽象语法树解析器和中间表示编译器即服务
  * [scan.coverity.com](https://scan.coverity.com/) — Static code analysis for Java, C/C++, C# and JavaScript, free for Open Source
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 持续检测平台，开源免费
  * [shields.io](https://shields.io) — Quality metadata badges for open source projects
  * [Sider](https://sider.review) — Code review platform for many languages. Supports integration with GitHub. Free for public repositories with unlimited users.
  * [sonarcloud.io](https://sonarcloud.io) — Automated source code analysis for Java, JavaScript, C/C++, C#, VB.NET, PHP, Objective-C, Swift, Python, Groovy and even more languages, free for Open Source
  * [SourceLevel](https://sourcelevel.io/) — Automated Code Review and Team Analytics. Free for Open Source and organizations up to 5 collaborators.
  * [Typo CI](https://github.com/marketplace/typo-ci) — Typo CI 审查您的 Pull Requests 和提交的拼写错误，对开源免费.
  * [Viezly](https://viezly.com/)  - 增强的代码审查工具，便于代码阅读和导航. 开源免费，个人使用免费.
  * [webceo.com](https://www.webceo.com/) — SEO tools but with also code verifications and different type of advices
  * [zoompf.com](https://zoompf.com/) — 修复您网站的性能，详细分析


## Code Search and Browsing

  * [codota.com](https://www.codota.com/)  — Codota 通过提供从世界上所有代码中学到的见解，帮助开发人员更快地创建更好的软件. 插件可用.
  * [libraries.io](https://libraries.io/) — Search and dependency update notifications for 32 different package managers, free for open source
  * [Namae](https://namae.dev/) - Search across various websites like github,gitlab,heroku,netlify and many more for availabilty of your project name.
  * [searchcode.com](https://searchcode.com/) — 全面的基于文本的代码搜索，对开源免费
  * [sourcegraph.com](https://about.sourcegraph.com/) — Java、Go、Python、Node.js 等，代码搜索/交叉引用，开源免费
  * [tickgit.com](https://www.tickgit.com/) — Surfaces `TODO` comments (and other markers) to identify areas of code worth returning to for improvement.
  * [CodeKeep](https://codekeep.io) - Google Keep for Code Snippets. Organize,Discover and share code snippets, featuring a powerful code screenshot tool with preset templates and linking feature.


## CI and CD

  * [AccessLint](https://github.com/marketplace/accesslint) — AccessLint brings automated web accessibility testing into your development workflow. It's free for open source and education purposes.
  * [appcircle.io](https://appcircle.io)  — 适用于 iOS 和 Android 的自动化移动 CI/CD/CT，带有在线设备模拟器.  20 分钟构建超时（开源为 60 分钟），单并发免费.
  * [appveyor.com](https://www.appveyor.com/) — CD service for Windows, free for Open Source
  * [bitrise.io](https://www.bitrise.io/)  — 适用于原生或混合移动应用程序的 CI/CD. 每月 200 次免费构建 10 分钟构建时间和两名团队成员.  OSS 项目获得 45 分钟的构建时间、+1 并发和无限的团队规模.
  * [buddy.works](https://buddy.works/) — A CI/CD with 5 free projects and 1 concurrent runs (120 executions/month)
  * [buddybuild.com](https://www.buddybuild.com/) — Build, deploy and gather feedback for your iOS and Android apps in one seamless, iterative system
  * [circleci.com](https://circleci.com/) — 一个并发构建免费
  * [cirrus-ci.org](https://cirrus-ci.org) - 公共 GitHub 存储库免费
  * [codefresh.io](https://codefresh.io) — Free-for-Life plan: 1 build, 1 environment, shared servers, unlimited public repos
  * [codemagic.io](https://codemagic.io/) - Free 500 build minutes/month
  * [codeship.com](https://codeship.com/) — 100 private builds/month, 5 private projects, unlimited for Open Source
  * [Continuous PHP](https://continuousphp.com/)  — Continuousphp 是第一个也是唯一一个在同一工作流程中构建、打包、测试和部署应用程序的以 PHP 为中心的平台. 免费用于社区项目，即 OSS/公共/教育项目.
  * [deployhq.com](https://www.deployhq.com/) — 1 个项目，每天进行 10 次部署（每月 30 分钟构建）
  * [drone](https://cloud.drone.io/) - Drone Cloud enables developers to run Continuous Delivery pipelines across multiple architectures - including x86 and Arm (both 32 bit and 64 bit) - all in one place
  * [LayerCI](https://layerci.com) — CI for full stack projects. 1 full stack preview environment with 5GB memory & 3 CPUs .
  * [ligurio/awesome-ci](https://github.com/ligurio/awesome-ci) — 持续集成服务的比较
  * [Octopus Deploy](https://octopus.com) - Automated deployment and release-management. Free for <= 10 deployment targets.
  * [scalr.com](https://scalr.com/)  - Terraform 的远程状态和操作后端，具有完整的 CLI 支持、与 OPA 的集成和分层配置模型. 最多释放 5 个用户.
  * [semaphoreci.com](https://semaphoreci.com/) — Free for Open Source, 100 private builds per month
  * [Squash Labs](https://www.squash.io/) — 为每个分支创建一个 VM，并使您的应用程序可从唯一的 URL、无限的公共和私有存储库、高达 2 GB 的 VM 大小.
  * [stackahoy.io](https://stackahoy.io) — 100% free. Unlimited deployments, branches and builds
  * [styleci.io](https://styleci.io/) — 仅限公共 GitHub 存储库
  * [Mergify](https://mergify.io) — workflow automation and merge queue for GitHub — Free for public GitHub repositories
  * [Integromat](https://www.integromat.com)  — 工作流程自动化工具，可让您使用 UI 连接应用程序并自动化工作流程，它支持许多应用程序和最流行的 API. 公共 GitHub 存储库免费，免费层级为 100 Mb、1000 次操作和 15 分钟的最小间隔.



## Testing

  * [Applitools.com](https://applitools.com/)  — 针对 Web、本地移动和桌面应用程序的智能视觉验证. 与几乎所有自动化解决方案（如 Selenium 和 Karma）和远程运行器（Sauce Labs、Browser Stack）集成. 免费用于开源. 每周检查点有限的单个用户的免费套餐.
  * [Appetize](https://appetize.io) — Test your Android & iOS apps on this Cloud Based Android Phone/Tablets emulators and iPhone/iPad simulators directly in your browser. Free tier includes 1 concurrent session with 100 minutes usage per month. No limit on app size.
  * [Bird Eats Bug](https://www.birdeatsbug.com/)  — 更快（更好）地报告错误. 使用 Bird 浏览器扩展记录您的屏幕，它将自动捕获工程师需要调试的技术数据. 适合小型团队的免费套餐.
  * [lambdatest.com](https://www.lambdatest.com/) — selenium 和 cypress 的手动、可视化、屏幕截图和自动浏览器测试， [free for Open Source](https://www.lambdatest.com/open-source-cross-browser-testing-tool)
  * [browserstack.com](https://www.browserstack.com/) — Manual and automated browser testing, [free for Open Source](https://www.browserstack.com/open-source?ref=pricing)
  * [checkbot.io](https://www.checkbot.io/) — Browser extension that tests if your website follows 50+ SEO, speed and security best practices. Free tier for smaller websites.
  * [checklyhq.com](https://checklyhq.com)  - Checkly 是现代堆栈的 API 和 E2E 监控平台：可编程、灵活和热爱 JavaScript. 为开发人员提供的免费套餐.
  * [crossbrowsertesting.com](https://crossbrowsertesting.com) - Manual, Visual, and Selenium Browser Testing in the cloud - [free for Open Source](https://crossbrowsertesting.com/open-source)
  * [cypress.io](https://www.cypress.io/) - Fast, easy and reliable testing for anything that runs in a browser. Cypress Test Runner is always free and open source with no restrictions and limitations. Cypress Dashboard is free for open source projects for up to 5 users.
  * [everystep-automation.com](https://www.everystep-automation.com/) — 记录和回放在 Web 浏览器中进行的所有步骤并创建脚本，... 免费且选项更少
  * [Gremlin](https://www.gremlin.com/gremlin-free-software)  — Gremlin 的混沌工程工具允许您安全、可靠、简单地将故障注入您的系统，以便在它们导致面向客户的问题之前发现弱点.  Gremlin Free 提供对多达 5 个主机或容器的关闭和 CPU 攻击的访问权限.
  * [gridlastic.com](https://www.gridlastic.com/) — Selenium Grid testing with free plan up to 4 simultaneous selenium nodes/10 grid starts/4,000 test minutes/month
  * [loadmill.com](https://www.loadmill.com/) - Automatically create API and load tests by analyzing network traffic. Simulate up to 50 concurrent users for up to 60 minutes for free every month.
  * [percy.io](https://percy.io)  - 将可视化测试添加到任何 Web 应用程序、静态站点、样式指南或组件库. 无限的团队成员，演示应用程序和无限的项目，5,000 个快照/月.
  * [reflect.run](https://reflect.run) - Codeless automated tests for web apps. Tests can be scheduled in-app or executed from a CI/CD tool. Each test run includes a full video recording along with console and network logs. The free tier includes an unlimited number of saved tests, with 25 test runs per month and up to 3 users.
  * [saucelabs.com](https://saucelabs.com/) — Cross browser testing, Selenium testing and mobile testing, [free for Open Source](https://saucelabs.com/open-source)
  * [snippets.uilicious.com](https://snippets.uilicious.com)  - 类似于 CodePen，但用于跨浏览器测试.  UI-licious 允许编写用户故事之类的测试，并提供免费平台 - UI-licious Snippets - 允许您在 Chrome 上免费运行无限数量的测试，无需注册，每次测试运行最多 3 分钟. 发现错误？ 您可以简单地将唯一的 url 复制到您的测试中，以准确地向您的开发人员展示如何重现错误.
  * [testingbot.com](https://testingbot.com/) — Selenium Browser and Device Testing, [free for Open Source](https://testingbot.com/open-source)
  * [Testspace.com](https://testspace.com/)  - 用于发布自动化测试结果的仪表板和用于使用 GitHub 将手动测试作为代码实施的框架. 服务是 [free for Open Source](https://github.com/marketplace/testspace-com) 每月有 450 个结果.
  * [tesults.com](https://www.tesults.com)  — 测试结果报告和测试用例管理. 与流行的测试框架集成. 开源软件开发人员、个人、教育工作者和小团队入门可以请求基本免费项目之外的折扣和免费产品.
  * [websitepulse.com](https://www.websitepulse.com/tools/) — 各种免费的网络和服务器工具.
  * [qase.io](https://qase.io) - Test management system for Dev and QA teams. Manage test cases, compose test runs, perform test runs, track defects and measure impact. The free tier includes all core features, with 500Mb available for attachments and up to 3 users.
  * [knapsackpro.com](https://knapsackpro.com)  - 在任何 CI 提供商上使用最佳测试套件并行化加速您的测试. 在并行 CI 节点上拆分 Ruby、JavaScript 测试以节省时间. 长达 10 分钟测试文件的免费计划和开源项目的免费无限计划.
  * [webhook.site](https://webhook.site)  - 使用自定义 URL 验证 webhook、出站 HTTP 请求或电子邮件. 临时 URL 和电子邮件地址始终免费.
  * [Vaadin](https://vaadin.com) — Build scalable UIs in Java or TypeScript, and use the integrated tooling, components and design system to iterate faster, design better and simplify the development process. Unlimited Projects with 5 years free maintenance.
  * [Foresight](https://thundra.io/foresight) — Thundra Foresight is a tool for debugging and troubleshooting test failures in no time and optimizing build duration and performance in your CI pipeline.


## Security and PKI

  * [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — 发现网络中的受损系统
  * [atomist.com](https://atomist.com/) — A quicker and more convenient way to automate a variety of development tasks. Now in beta.
  * [auth0.com](https://auth0.com/)  — 为开发 SSO 免费托管. 最多 2 个用于闭源项目的社交身份提供者.
  * [Authgear](https://www.authgear.com)  - 在几分钟内为您的应用程序带来无密码、OTP、2FA、SSO. 包括所有前端. 释放多达 5000 个 MAU.
  * [Authress](https://authress.io/) — Authentication login and access control, unlimited identity providers for any project. Facebook, Google, Twitter and more. First 1000 API calls are free.
  * [Authy](https://authy.com) - Two-factor authentication (2FA) on multiple devices, with backups. Drop-in replacement for Google Authenticator. Free for up to 100 successful authentications.
  * [Bridgecrew](https://bridgecrew.io/) — Infrastructure as code (IaC) security powered by the open source tool - [Checkov](https://github.com/bridgecrewio/checkov). The core Bridgecrew platform is free for up to 50 IaC resources.
  * [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services (AWS) 安全性和合规性审计和监控
  * [Cmd](https://cmd.com/) — 安全平台在您的云或数据中心中的每个 Linux 实例上提供实时访问控制和动态策略实施
  * [CodeNotary.io](https://www.codenotary.io/) — 具有不可磨灭证据的开源平台，可对代码、文件、目录或容器进行公证
  * [crypteron.com](https://www.crypteron.com/) — Cloud-first, developer-friendly security platform prevents data breaches in .NET and Java applications
  * [Datree](https://www.datree.io/) — Open Source CLI tool to prevent Kubernetes misconfigurations by ensuring that manifests and Helm charts follow best practices as well as your organization’s policies
  * [Dependabot](https://dependabot.com/) Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven 和 Gradle）、.NET、Go、Elm、Docker、Terraform、Git 子模块和 GitHub Actions 的自动依赖项更新.
  * [DJ Checkup](https://djcheckup.com) — Scan your Django site for security flaws with this free, automated, checkup tool. Forked from the Pony Checkup site.
  * [Doppler](https://doppler.com/) — Universal Secrets Manager for application secrets and config, with support for syncing to various cloud providers. Free for unlimited users with basic access controls.
  * [duo.com](https://duo.com/)  — 网站或应用程序的双因素身份验证 (2FA).  10 个用户免费，所有身份验证方法，无限制，集成，硬件令牌.
  * [GitGuardian](https://www.gitguardian.com) — Keep secrets out of your source code with automated secrets detection and remediation. Scan your git repos for 350+ types of secrets and sensitive files – Free for individuals and teams of 25 developers or less.
  * [globalsign.com](https://www.globalsign.com/en/ssl/ssl-open-source/) — 开源的免费 SSL 证书
  * [Have I been pwned?](https://haveibeenpwned.com) — 用于获取违规信息的 REST API.
  * [hostedscan.com](https://hostedscan.com) — Online vulnerability scanner for web applications, servers, and networks. 10 free scans per month.
  * [Internet.nl](https://internet.nl) — 测试现代互联网标准，如 IPv6、DNSSEC、HTTPS、DMARC、STARTTLS 和 DANE
  * [Jumpcloud](https://jumpcloud.com/) — Provides directory as a service similar to Azure AD, user management, single sign-on, and RADIUS authentication. Free for up to 10 users.
  * [keychest.net](https://keychest.net) - SSL 到期管理和证书购买与集成 CT 数据库
  * [letsencrypt.org](https://letsencrypt.org/) — Free SSL Certificate Authority with certs trusted by all major browsers
  * [LoginRadius](https://www.loginradius.com/) — Managed User Authentication service for free. Email registration and 3 social providers.
  * [logintc.com](https://www.logintc.com/) — 通过推送通知进行的两因素身份验证 (2FA)，10 位用户、VPN、网站和 SSH 免费
  * [meterian.io](https://www.meterian.io/)  - 监控 Java、Javascript、.NET、Scala、Ruby 和 NodeJS 项目的依赖项中的安全漏洞. 一个私人项目免费，开源项目无限.
  * [MojoAuth](https://mojoauth.com/) - MojoAuth 可以在几分钟内轻松地在您的 Web、移动设备或任何应用程序上实施无密码身份验证.
  * [Mozilla Observatory](https://observatory.mozilla.org/) — 查找并修复您网站中的安全漏洞.
  * [Okta](https://developer.okta.com/) — User management, authentication and authorization. Free for up to 1000 monthly active users.
  * [onelogin.com](https://www.onelogin.com/) — 身份即服务 (IDaaS)、单点登录身份提供商、云 SSO IdP、3 个公司应用程序和 5 个个人应用程序、无限用户
  * [Operous](https://operous.dev/) — Cloud instance testing tool with a comprehensive and automated set of test-suites of best practices, performance, and security. Free tier offers 100 testing minutes, 10 Test Suites, and up to 5 instances to 1 user.
  * [opswat.com](https://www.opswat.com/) — Security Monitoring of computers, devices, applications, configurations,... Free 25 users and 30 days history users.
  * [pyup.io](https://pyup.io) — Monitor Python dependencies for security vulnerabilities and update them automatically. Free for one private project, unlimited projects for open source.
  * [qualys.com](https://www.qualys.com/community-edition) — Find web app vulnerabilities, audit for OWASP Risks
  * [reCAPTCHAMe](https://recaptchame.com/)  — 免费的 reCAPTCHA 和 hCAPTCHA 后端服务. 无需服务器端编码. 适用于静态网站.
  * [report-uri.io](https://report-uri.io/) — CSP and HPKP violation reporting
  * [ringcaptcha.com](https://ringcaptcha.com/) — Tools to use phone number as id, available for free
  * [sawolabs.com](https://sawolabs.com/)  - 通过在您的应用程序中集成无密码身份验证来简化登录并改善用户体验. 每月 5000 次免费认证.
  * [snyk.io](https://snyk.io)  — 可以在您的开源依赖项中找到并修复已知的安全漏洞. 开源项目的无限测试和修复. 您的私人项目每月限制为 200 次测试.
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) — 对任何 SSL Web 服务器的配置进行非常深入的分析
  * [StackHawk](https://www.stackhawk.com/) Automate application scanning throughout your pipeline to find and fix security bugs before they hit production. Unlimited scans and environments for a single app.
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) - Free website security check and malware scanner
  * [Protectumus](https://protectumus.com) - Free website security check, site antivirus and server firewall (WAF) for PHP. Email notifications for registered users in free tier.
  * [TestTLS.com](https://testtls.com) - Test a SSL/TLS service for secure server configuration, certificates, chains etc. Not limited to HTTPS.
  * [threatconnect.com](https://threatconnect.com) — Threat intelligence: It is designed for individual researchers, analysts and organizations who are starting to learn about cyber threat intelligence. Free up to 3 Users
  * [tinfoilsecurity.com](https://www.tinfoilsecurity.com/) — Automated vulnerability scanning. Free plan allows weekly XSS scans
  * [Ubiq Security](https://ubiqsecurity.com/)  — 使用 3 行代码和自动密钥管理加密和解密数据.  1 个应用程序和每月最多 1,000,000 次加密免费.
  * [Virgil Security](https://virgilsecurity.com/)  — 用于在您的数字解决方案中实施端到端加密、数据库保护、物联网安全等的工具和服务. 最多 250 个用户的应用程序免费.
  * [Virushee](https://virushee.com/) — Privacy-oriented file/data scanning powered by hybrid heuristic and AI-assisted engine. Possible to use internal dynamic sandbox analysis. Limited to 50MB per file upload
  * [Warrant](https://warrant.dev/) — Hosted enterprise-grade authorization and access control service for your apps. Free tier includes 5,000 API requests per month.
  * [Escape GraphQL Quickscan](https://escape.tech/quickscan) - One-click security scan of your GraphQL endpoints. Free, no login required.


## Management System

  * [bitnami.com](https://bitnami.com/) — Deploy prepared apps on IaaS. Management of 1 AWS micro instance free
  * [Esper](https://esper.io) <i>— MDM and MAM for Android Devices with DevOps.</i> <b>— 适用于具有 DevOps 的 Android 设备的 MDM 和 MAM。</b> <i>100 devices free with 1 user license and 25 MB Application Storage.</i> <b>100 台设备免费，1 个用户许可证和 25 MB 应用程序存储。</b>
  * [jamf.com](https://www.jamf.com/) — iPad、iPhone 和 Mac 的设备管理，3 台设备免费
  * [Miradore](https://miradore.com) — Device Management service. Stay up-to-date with your device fleet and secure an unlimited number of devices for free. Free plan offers basic features.
  * [moss.sh](https://moss.sh) - Help developers deploy and manage their web apps and servers. Free up to 25 git deployments per month
  * [runcloud.io](https://runcloud.io/)  - 服务器管理主要集中在 PHP 项目上. 最多可免费使用 1 台服务器.
  * [ploi.io](https://ploi.io/)  - 服务器管理工​​具，可轻松管理和部署您的服务器和站点.  1台服务器免费.


## Messaging and Streaming

  * [Ably](https://www.ably.com/)  - 具有存在、持久性和保证交付的实时消息传递服务. 免费计划包括每月 300 万条消息、100 个高峰连接和 100 个高峰频道.
  * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ as a Service. Little Lemur plan: max 1 million messages/month, max 20 concurrent connections, max 100 queues, max 10,000 queued messages, multiple nodes in different AZ's
  * [connectycube.com](https://connectycube.com)  - 无限的聊天消息、p2p 语音和视频通话、文件附件和推送通知. 免费提供高达 20K MAU 的应用程序.
  * [courier.com](https://www.courier.com/)  — 用于推送、应用内、电子邮件、聊天、短信和其他消息渠道的单一 API，具有模板管理和其他功能. 免费计划包括 10,000 条消息/月.
  * [pusher.com](https://pusher.com/)  — 实时消息服务. 免费提供多达 100 个同时连接和 200,000 条消息/天
  * [scaledrone.com](https://www.scaledrone.com/) — Realtime messaging service. Free for up to 20 simultaneous connections and 100,000 events/day
  * [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io) 作为一项服务. 全球、AWS、GCP 和 Azure. 每月 4k 消息大小、50 个活动连接和 5GB 数据，永久免费.
  * [cloudkarafka.com](https://www.cloudkarafka.com/) - Free Shared Kafka cluster, up to 5 topics, 10MB data per topic and 28 days of data retention.
  * [pubnub.com](https://www.pubnub.com/)  - 每月 100 万笔交易的 Swift、Kotlin 和 React 消息传递. 事务可能包含多条消息.
  * [eyeson API](https://developers.eyeson.team/)  - 基于WebRTC（SFU，MCU）构建视频平台的视频通信API服务. 允许实时数据注入、视频布局、录制、功能齐全的托管 Web UI（快速入门）或自定义 UI 包. 有一个 [free tier for developers](https://apiservice.eyeson.com/api-pricing) with 1000 meeting minutes a month.
  * [Upstash Kafka](https://upstash.com/kafka)  - 按请求定价的无服务器 Kafka 云产品. 它有一个免费层，每天最多 10000 条消息.



## Log Management

  * [bugfender.com](https://bugfender.com/) — 每天最多释放 10 万条日志行，24 小时保留
  * [humio.com](https://www.humio.com/) — Free up to 2 GB/day with 7 days retention
  * [logdna.com](https://logdna.com) - Free for a single user, no retention, unlimited hosts and sources
  * [logentries.com](https://logentries.com/) — 每月最多免费 5 GB，保留 7 天
  * [loggly.com](https://www.loggly.com/) — Free for a single user, see the lite option
  * [logz.io](https://logz.io/) — Free up to 3 GB/day, 3 days retention
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-log-management) — Log Management service powered by Manage Engine. Free Plan offers 50 GB storage with 1 Month retention.
  * [papertrailapp.com](https://papertrailapp.com/) — 48 小时搜索，7 天存档，100 MB/月
  * [sematext.com](https://sematext.com/logsene) — 每天最多释放 500 MB，保留 7 天
  * [sumologic.com](https://www.sumologic.com/) — 每天最多释放 500 MB，保留 7 天
  * [logflare.app](https://logflare.app/) — 每个应用每月最多可免费获得 12,960,000 个条目，保留 3 天
  * [logtail.com](https://logtail.com/)  — 基于 ClickHouse 的 SQL 兼容日志管理. 每月最多免费 1 GB，保留 3 天.


## Translation Management

  * [crowdin.com](https://crowdin.com/) — Unlimited projects, unlimited strings and collaborators for Open Source
  * [gitlocalize.com](https://gitlocalize.com) - Free and unlimited for both private and public repositories
  * [lingohub.com](https://lingohub.com/) — Free up to 3 users, always free for Open Source
  * [localazy.com](https://localazy.com) - 免费提供 1000 种源语言字符串、无限语言、无限贡献者、启动和开源交易
  * [Localeum](https://localeum.com) - Free up to 1000 strings, 1 user, unlimited languages, unlimited projects
  * [localizely.com](https://localizely.com/) — Free for Open Source
  * [Loco](https://localise.biz/) — 免费提供多达 2000 个翻译，无限翻译，10 种语言/项目，1000 个可翻译资产/项目
  * [oneskyapp.com](https://www.oneskyapp.com/) — 最多 5 位用户的有限免费版，开源免费
  * [POEditor](https://poeditor.com/) — 最多释放 1000 个字符串
  * [SimpleLocalize](https://simplelocalize.io/) - Free up to 100 translation keys, unlimited strings, unlimited languages, startup deals
  * [Texterify](https://texterify.com/) - Free for a single user
  * [transifex.com](https://www.transifex.com/) — Free for Open Source
  * [Translation.io](https://translation.io) - 开源免费
  * [webtranslateit.com](https://webtranslateit.com/) — 最多释放 500 个字符串
  * [weblate.org](https://weblate.org/) — It's free for libre projects up to 10,000 string source for the free tier, and Unlimited Self-hosted on-premises.
  * [Free PO editor](https://pofile.net/free-po-editor) — Free for everybody


## Monitoring

  * [Pingmeter.com](https://pingmeter.com/)  - 5 个正常运行时间监视器，间隔 10 分钟. 监控 SSH、HTTP、HTTPS 和任何自定义 TCP 端口.
  * [amixr.io](https://amixr.io/)  - 通过出色的 Slack 集成、API 和 Terraform 对开发人员友好的警报和待命管理. 免费电话、短信、电报、Slack 和电子邮件套餐.
  * [appdynamics.com](https://www.appdynamics.com/) — 24 小时免费指标，应用程序性能管理代理仅限于一种 Java、一种 .NET、一种 PHP 和一种 Node.js
  * [appneta.com](https://www.appneta.com/) — 免费，数据保留 1 小时
  * [assertible.com](https://assertible.com)  — 自动化 API 测试和监控. 团队和个人的免费计划.
  * [blackfire.io](https://blackfire.io/)  — Blackfire 是 SaaS 交付的应用程序性能解决方案. 免费黑客计划（仅限 PHP）
  * [checklyhq.com](https://checklyhq.com) - Open source E2E / Synthetic monitoring and deep API monitoring for developers. Free plan with 5 users and 50k+ check runs.
  * [circonus.com](https://www.circonus.com/) — Free for 20 metrics
  * [cloudsploit.com](https://cloudsploit.com) — AWS security and configuration monitoring. Free: unlimited on-demand scans, unlimited users, unlimited stored accounts. Subscription: automated scanning, API access, etc.
  * [datadoghq.com](https://www.datadoghq.com/) — Free for up to 5 nodes
  * [deadmanssnitch.com](https://deadmanssnitch.com/)  — 监控 cron 作业.  1 个免费告密者（监视器），如果您推荐其他人注册，则更多
  * [economize.cloud](https://economize.cloud) — Economize helps demystify cloud infrastructure costs by organizing cloud resources, optimize and report the same. Free for up to $5000 spends on Google Cloud Platform every month.
  * [elastic.co](https://www.elastic.co/solutions/apm)  — 为 JS 开发人员提供即时性能洞察. 免费提供 24 小时数据保留
  * [freeboard.io](https://freeboard.io/) — Free for public projects. Dashboards for your Internet of Things (IoT) projects
  * [freshworks.com](https://www.freshworks.com/website-monitoring/) — 以 1 分钟的间隔监控 50 个 URL，包括 10 个全球位置和 5 个免费的公共状态页面
  * [gitential.com](https://gitential.com)  — 软件开发分析平台. 免费：无限的公共存储库，无限的用户，私人存储库的免费试用. 可用于企业的本地版本.
  * [Grafana Cloud](https://grafana.com/products/cloud/) - Grafana Cloud is a composable observability platform, integrating metrics and logs with Grafana. Free: 3 users, 10 dashboards, 100 alerts, metrics storage in Prometheus and Graphite (10,000 series, 14 days retention), logs storage in Loki (50 GB of logs, 14 days retention)
  * [healthchecks.io](https://healthchecks.io)  — 监控您的 cron 作业和后台任务. 最多可免费进行 20 次检查.
  * [inspector.dev](https://www.inspector.dev) - A complete Real-Time monitoring dashboard in less than one minute with free forever tier.
  * [instrumentalapp.com](https://instrumentalapp.com) - 美观且易于使用的应用程序和服务器监控，多达 500 个指标和 3 小时的免费数据可见性
  * [keychest.net/speedtest](https://keychest.net/speedtest) - 针对 Digital Ocean 的独立速度测试和 TLS 握手延迟测试
  * [letsmonitor.org](https://letsmonitor.org) - SSL monitoring, free for up to 5 monitors
  * [loader.io](https://loader.io/) — 有限制的免费负载测试工具
  * [meercode.io](https://meercode.io/)  — Meercode 是您的 CI/CD 构建的终极监控仪表板. 免费提供开源和 1 个私有存储库.
  * [netdata.cloud](https://www.netdata.cloud/)  — Netdata 是一个开源工具，旨在收集实时指标.快速增长的产品. 也可以在github上找到！
  * [newrelic.com](https://www.newrelic.com)  — 为帮助工程师创建更完美的软件而构建的新 Relic 可观察性平台. 从单体应用到无服务器，您可以检测所有内容，然后分析、排除故障并优化您的整个软件堆栈. 免费套餐提供每月 100GB 的免费数据摄取、1 个免费的完全访问用户和无限的免费基本用户.
  * [nixstats.com](https://nixstats.com)  - 一台服务器免费. 电子邮件通知、公共状态页面、60 秒间隔等.
  * [OnlineOrNot.com](https://onlineornot.com/)  - OnlineOrNot 是基于 JS 的 Web 应用程序和网站的可靠正常运行时间监视器.  10 次正常运行时间检查（针对静态网站和 API），间隔 5 分钟，1 次浏览器检查，间隔 15 分钟. 最多 3 位用户免费，通过 Slack、Discord 和电子邮件发送警报.
  * [opsgenie.com](https://www.opsgenie.com/) — Powerful alerting and on-call management for operating always-on services. Free up to 5 users.
  * [paessler.com](https://www.paessler.com/) — Powerful infrastructure and network monitoring solution including alerting, strong visualization capabilities and basic reporting. Free up to 100 sensors.
  * [syagent.com](https://syagent.com/) — 非商业免费服务器监控服务、警报和指标.
  * [pagertree.com](https://pagertree.com/)  - 用于警报和待命管理的简单界面. 最多释放 5 个用户.
  * [pingbreak.com](https://pingbreak.com/) — Modern uptime monitoring service. Check unlimited URLs and get downtime notifications via Discord, Slack or email.
  * [pingpong.one](https://pingpong.one/) — Advanced status page platform with monitoring. Free tier includes one public customizable status page with SSL subdomain. Pro plan is offered to open-source projects and non-profits free of charge.
  * [sematext.com](https://sematext.com/) — 免费提供 24 小时指标、无限数量的服务器、10 个自定义指标、500,000 个自定义指标数据点、无限的仪表板、用户等.
  * [sitemonki.com](https://sitemonki.com/) — Website, domain, Cron & SSL monitoring, 5 monitors in each category for free
  * [skylight.io](https://www.skylight.io/) — 前 100,000 个请求免费（仅限 Rails）
  * [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — 性能监控 API，检查 Ping、DNS 等.
  * [stathat.com](https://www.stathat.com/) — 免费开始使用 10 个统计数据，没有过期
  * [statuscake.com](https://www.statuscake.com/) — Website monitoring, unlimited tests free with limitations
  * [statusgator.com](https://statusgator.com/) — 状态页面监控，3台免费监控
  * [thousandeyes.com](https://www.thousandeyes.com/) — Network and user experience monitoring. 3 locations and 20 data feeds of major web services free
  * [thundra.io/apm](https://www.thundra.io/apm)  — 应用程序监控和调试. 拥有每月最多 25 万次调用的免费套餐.
  * [uptimerobot.com](https://uptimerobot.com/) — 网站监控，免费 50 台显示器
  * [uptimetoolbox.com](https://uptimetoolbox.com/) — 免费监控 5 个网站，60 秒间隔，公开状态页.
  * [zenduty.com](https://www.zenduty.com/)  — 用于网络运营、站点可靠性工程和 DevOps 团队的端到端事件管理、警报、待命管理和响应编排平台. 最多 5 位用户免费.
  * [asayer.io](https://asayer.io/pricing.html)  — openreplay 的托管版本，一种开源会话重播（FullStory 和 LogRocket 的替代品）. 每月免费 1k 次会话，保留 14 天
  * [lean20.com](https://lean20.com/product/status/)  - 事件报告的公共状态页面.  100% 免费.
  * [instatus.com](https://instatus.com) - Get a beautiful status page in 10 seconds. Free forever with unlimited subs and unlimited teams.
  * [Squadcast.com](https://squadcast.com) - Squadcast is an end-to-end incident management software that's designed to help you promote SRE best practices. Free forever plan available for upto 10 users.


## Crash and Exception Handling

  * [CatchJS.com](https://catchjs.com/) - JavaScript error tracking with screenshots and click trails. Free for open source projects.
  * [bugsnag.com](https://www.bugsnag.com/) — 初次试用后每月最多 2,000 个错误免费
  * [exceptionless](https://exceptionless.com)  — 实时错误、功能、日志报告等. 每月/1 位用户可免费参加 3k 次活动. 开源且易于自托管，可无限使用.
  * [GlitchTip](https://glitchtip.com/)  — 简单的开源错误跟踪. 与开源 Sentry SDK 兼容. 每月免费举办 1000 场活动，或者可以不受限制地自行举办活动
  * [honeybadger.io](https://www.honeybadger.io)  - 异常、正常运行时间和 cron 监控. 小型团队和开源项目免费（每月 12,000 个错误）.
  * [rollbar.com](https://rollbar.com/) — Exception and error monitoring, free plan with 5,000 errors/month, unlimited users, 30 days retention
  * [sentry.io](https://sentry.io/) — Sentry tracks app exceptions in real-time, has a small free plan. Free for 5k errors per month/ 1 user, unrestricted use if self-hosted


## Search

  * [algolia.com](https://www.algolia.com/)  — 托管搜索即键入（即时）. 免费黑客计划多达 10,000 个文档和 100,000 次操作. 更大的免费计划可用于社区/开源项目
  * [bonsai.io](https://bonsai.io/) — Free 1 GB memory and 1 GB storage
  * [searchly.com](http://www.searchly.com/) — Free 2 indices and 20 MB storage
  * [pagedart.com](https://pagedart.com/) - AI search as a service the free tier includes 1000 Documents, 50000 searches. Larger free tiers are possible for worthwhile projects.


## Email

  * [10minutemail](https://10minutemail.com) - Free, temporary email for testing.
  * [AnonAddy](https://anonaddy.com) - Open-source anonymous email forwarding, create unlimited email aliases for free
  * [Antideo](https://www.antideo.com) — 10 API requests per hour for email verification, IP and phone number validation in free tier. No Credit Cards required.
  * [biz.mail.ru](https://biz.mail.ru/) — 5,000 个邮箱，每个邮箱 25 GB，每个自定义域使用 DNS 托管
  * [Bump](https://bump.email/) - 免费 10 个 Bump 电子邮件地址，1 个自定义域
  * [Burnermail](https://burnermail.io/) – 免费 5 个 Burner 电子邮件地址、1 个邮箱、7 天邮箱历史记录
  * [Buttondown](https://buttondown.email/)  — 通讯服务. 多达 1,000 名免费订阅者
  * [CloudMailin](https://www.cloudmailin.com/) - 通过 HTTP POST 和事务出站接收电子邮件 - 每月 10,000 封免费电子邮件
  * [cloudmersive.com](https://www.cloudmersive.com/email-verification-api) — 面向开发人员的电子邮件验证和验证 API，每月 2,000 个免费 API 请求
  * [Contact.do](https://contact.do/) - 链接中的联系表格（联系表格有点） - 完全免费！
  * [debugmail.io](https://debugmail.io/) — Easy to use testing mail server for developers
  * [Email Temporanee](https://emailtemporanee.com/) - Easy to use free Unlimited disposable temporary email addresses (temp email). Autoexpires even you can set it day.
  * [elasticemail.com](https://elasticemail.com) — 100 free emails/day. 1,000 emails for $0.09 through API (pay as you go).
  * [EmailOctopus](https://emailoctopus.com) - 每月免费订阅多达 2,500 名订阅者和 10,000 封电子邮件
  * [Eva](https://eva.pingutil.com) — Verify 5 million emails per day for free using REST API. No sign-ups required.
  * [fakermail.com](https://fakermail.com/) — 用于测试的免费临时电子邮件，存储了最后 100 个电子邮件帐户.
  * [forwardemail.net](https://forwardemail.net) — Free email forwarding for custom domains. Create and forward an unlimited amount of email addresses with your domain name (**note**: You must pay if you use .casa, .cf, .click, .email, .fit, .ga, .gdn, .gq, .loan, .london, .men, .ml, .pl, .rest, .ru, .tk, .top, .work TLDs due to spam)
  * [ImprovMX](https://improvmx.com) – Free email forwarding
  * [inboxkitten.com](https://inboxkitten.com/) - Free temporary/disposable email inbox, with up-to 3 day email auto-deletes. Open sourced, and can be self-hosted.
  * [inumbo.com](http://inumbo.com/) — SMTP based spam filter, free for 10 users
  * [kickbox.io](https://kickbox.io/) — 免费验证 100 封电子邮件，提供实时 API
  * [mail.gw](https://mail.gw) — 10 Minute Mail. Free anonymous temporary email without obligations.
  * [mail.tm](https://mail.tm) — Disposable e-mail with user friendly interface. No registration needed.
  * [mailazy.com](https://mailazy.com/) — Mailazy is the only simple transactional email service you’ll need. 15,000 emails/month free forever (500 emails/day sending limit).
  * [mail-tester.com](https://www.mail-tester.com) — Test if email's dns/spf/dkim/dmarc settings are correct, 20 free/month
  * [dkimvalidator.com](https://dkimvalidator.com/) - 测试电子邮件的 dns/spf/dkim/dmarc 设置是否正确，roundsphere.com 提供免费服务
  * [mailboxlayer.com](https://mailboxlayer.com/)  — 面向开发人员的电子邮件验证和验证 JSON API.  1,000 个免费 API 请求/月
  * [mailcatcher.me](https://mailcatcher.me/) — Catches mail and serves it through a web interface
  * [mailchimp.com](https://mailchimp.com/) — 2,000 subscribers and 12,000 emails/month free
  * [MailerLite.com](https://www.mailerlite.com) — 1,000 名订阅者/月，12,000 封电子邮件/月免费
  * [mailinator.com](https://www.mailinator.com/) — Free, public, email system where you can use any inbox you want
  * [mailjet.com](https://www.mailjet.com/) — 6,000 emails/month free (200 emails daily sending limit)
  * [mailkitchen](https://www.mailkitchen.com/) — 终身免费，无需承诺，每月 10,000 封电子邮件，每天 1,000 封电子邮件
  * [mailmenot.io](http://mailmenot.io) — 免费的一次性临时电子邮件服务，能够添加多个电子邮件地址
  * [Mailnesia](https://mailnesia.com) - Free temporary/disposable email, which auto visit registration link.
  * [mailsac.com](https://mailsac.com) - Free API for temporary email testing, free public email hosting, outbound capture, email-to-slack/websocket/webhook (1,500 monthly API limit)
  * [Mailtie.com](https://mailtie.com/)  - 您的域的免费电子邮件转发. 无需注册. 永远免费.
  * [mailtrap.io](https://mailtrap.io/) — Fake SMTP server for development, free plan with 1 inbox, 50 messages, no team member, 2 emails/second, no forward rules
  * [mailvalidator.io](https://mailvalidator.io/) - 每月免费验证 300 封电子邮件，提供批量处理的实时 API
  * [mail7.io](https://www.mail7.io/)  — QA 开发人员的免费临时电子邮件地址. 使用 Web 界面或 API 立即创建电子邮件地址
  * [mohmal.com](https://www.mohmal.com/en) — Disposable temporary email
  * [moosend.com](https://moosend.com/)  — 邮件列表管理服务. 为初创公司提供 6 个月的免费帐户
  * [Outlook.com](https://outlook.live.com/owa/) - Free personal email and calendar
  * [Parsio.io](https://parsio.io) — Free email parser (Forward email, extract the data, send it to your server)
  * [pepipost.com](https://pepipost.com) — 第一个月免费发送 30k 封电子邮件，然后每天免费发送前 100 封电子邮件
  * [phplist.com](https://phplist.com/) — Hosted version allow 300 emails/month free
  * [postmarkapp.com](https://postmarkapp.com/) - 100 封电子邮件/月免费，无限制的 DMARC 每周摘要
  * [QuickEmailVerification](https://quickemailverification.com) — Verify 100 emails daily for free on a free tier along with other free APIs like DEA Detector, DNS Lookup, SPF Detector and more.
  * [Sender](https://www.sender.net) 每月最多 15 000 封电子邮件 - 最多 2 500 名订阅者
  * [sendgrid.com](https://sendgrid.com/) — 每天 100 封电子邮件和 2,000 个免费联系人
  * [sendinblue.com](https://www.sendinblue.com/) — 9,000 封电子邮件/月免费
  * [sendpulse.com](https://sendpulse.com) — 50 封电子邮件/小时免费，前 12,000 封电子邮件/月免费
  * [socketlabs.com](https://www.socketlabs.com) - 40k emails free for first month, then first 2000 emails/month free
  * [sparkpost.com](https://www.sparkpost.com/) — First 500 emails/month free
  * [Substack](https://substack.com) — Unlimited free newsletter service. Start paying when you charge for it.
  * [Tempmailo](https://tempmailo.com/)  - 无限的免费临时电子邮件地址. 两天后自动过期.
  * [HotTempMail](https://hottempmail.com/) - Unlimited free temp email or disposable temporary email addresses. Autoexpires in one day.
  * [temp-mail.io](https://temp-mail.io) — 免费一次性临时电子邮件服务，一次发送多封电子邮件并转发
  * [temp-mail.org](https://temp-mail.org) — 具有 REST API 的临时、安全、匿名、免费、一次性电子邮件地址，每天可免费从其一次性邮箱中获取 100 封电子邮件.
  * [testmail.app](https://testmail.app/) - Automate end-to-end email tests with unlimited mailboxes and a GraphQL API. 100 emails/month free forever, unlimited free for open source.
  * [tinyletter.com](https://tinyletter.com/) — 5,000 subscribers/month free
  * [trashmail.com](https://www.trashmail.com) - Free disposable email addresses with forwarding and automatic address expiration
  * [Validator.Pizza](https://www.validator.pizza/) — 检测一次性电子邮件的免费 API
  * [Verifalia](https://verifalia.com/email-verification-api)  — 带有邮箱确认和一次性电子邮件地址检测器的实时电子邮件验证 API； 每天 25 次免费电子邮件验证.
  * [verimail.io](https://verimail.io/)  — 批量和 API 电子邮件验证服务.  100 次免费验证/月
  * [Yandex.Connect](https://connect.yandex.com/pdd/) — 最多可容纳 1,000 名用户的免费电子邮件和 DNS 托管
  * [yopmail.fr](http://www.yopmail.fr/en/) — Disposable email addresses
  * [Zoho](https://www.zoho.com) — Started as an e-mail provider but now provides a suite of services out of which some of them have free plans. List of services having free plans :
     - [Email](https://zoho.com/mail) Free for 5 users. 5GB/user & 25 MB attachment limit, 1 domain.
     - [Sprints](https://zoho.com/sprints) Free for 5 users,5 Projects & 500MB storage.
     - [Docs](https://zoho.com/docs)  — 5 位用户免费，具有 1 GB 上传限制和 5 GB 存储空间.  Zoho Office Suite (Writer,Sheets &amp; Show) 与它捆绑在一起.
     - [Projects](https://zoho.com/projects)  — 3 个用户、2 个项目和 10 MB 附件限制免费. 同样的计划适用于 [Bugtracker](https://zoho.com/bugtracker).
     - [Connect](https://zoho.com/connect) — 25 位用户的团队协作免费，包含 3 个组、3 个自定义应用程序、3 个板、3 个手册、10 个集成以及渠道、活动和论坛.
     - [Meeting](https://zoho.com/meeting) — Meetings with upto 3 meeting participants & 10 Webinar attendees.
     - [Vault](https://zoho.com/vault) — 个人密码管理免费.
     - [Showtime](https://zoho.com/showtime) — Yet another Meeting software for training for a remote session upto 5 attendees.
     - [Notebook](https://zoho.com/notebook) — Evernote 的免费替代品.
     - [Wiki](https://zoho.com/wiki) — Free for 3 users with 50 MB storage, unlimited pages, zip backups, RSS & Atom feed, access controls & customisable CSS.
     - [Subscriptions](https://zoho.com/subscriptions) — Recurring Billing management free for 20 customers/subscriptions & 1 user with all the payment hosting done by Zoho themselves. Last 40 subscription metrics are stored
     - [Checkout](https://zoho.com/checkout) — Product Billing management with 3 pages & up to 50 payments.
     - [Desk](https://zoho.com/desk) — Customer Support management with 3 agents and private knowledge base, email tickets. Integrates with [Assist](https://zoho.com/assist) 适用于 1 名远程技术人员和 5 台无人值守的计算机.
     - [Cliq](https://zoho.com/cliq) — Team chat software with 100 GB storage, unlimited users, 100 users per channel & SSO.
     - [Campaigns](https://zoho.com/campaigns)
     - [Forms](https://zoho.com/forms)
     - [Sign](https:/zoho.com/sign)
     - [Surveys](https://zoho.com/surveys)
     - [Bookings](https://zoho.com/bookings)
     - [Analytics](https://zoho.com/analytics)
  * [SimpleLogin](https://simplelogin.io/) – Open source, self-hostable email alias/forwarding solution. Free 5 Aliases, unlimited bandwith, unlimited reply/send. Free for educational staffs (student, researcher, etc).
  * [EmailJS](https://www.emailjs.com/) – 这不是一个完整的电子邮件服务器，这只是电子邮件客户端，您可以使用它直接从客户端发送电子邮件而不会暴露您的凭据，免费层有：200 个每月请求，2 个电子邮件模板，请求高达 50Kb，有限的联系人历史.



## Font

  * [dafont](https://www.dafont.com/) - 本网站上呈现的字体是其作者的财产，并且是免费软件、共享软件、演示版或公共领域.
  * [Everything Fonts](https://everythingfonts.com/) - Offers multiple tools; @font-face, Units Converter, Font Hinter and Font Submitter.
  * [Font Squirrel](https://www.fontsquirrel.com/) - Freeware fonts that is licensed for commercial work. Hand-selected these typefaces and presenting them in an easy-to-use format.
  * [Google Fonts](https://fonts.google.com/) - 许多免费字体可以通过下载或指向 Google CDN 的链接轻松快速地安装在网站中.
  * [FontGet](https://www.fontget.com/) - 有多种字体可供下载，并带有标签整齐地排序.
  * [Fontshare](https://www.fontshare.com/) - is a free fonts service. It’s a growing collection of professional grade fonts that are 100% free for personal and commercial use.


## Forms

  * [99inbound.com](https://www.99inbound.com/)  - 建立表格并在线分享. 为每次提交获取电子邮件或 Slack 消息. 免费计划有 2 种表格，每月 100 个条目，基本电子邮件和 Slack.
  * [Form.taxi](https://form.taxi/)  — HTML 表单提交的端点. 通过通知、垃圾邮件拦截器和符合 GDPR 的数据处理. 基本使用的免费计划.
  * [Formcake.com](https://formcake.com) - Form backend for devs, free plan allows unlimited forms, 100 submissions, Zapier integration. No libraries or dependencies required.
  * [Formcarry.com](https://formcarry.com) - HTTP POST Form endpoint, Free plan allows 100 submissions per month.
  * [formingo.co](https://www.formingo.co/)- Easy HTML forms for static websites, get started for free without registering an account. Free plan allows 500 submissions per month, customizable reply-to email address.
  * [formlets.com](https://formlets.com/) — Online forms, unlimited single page forms/month, 100 submissions/month, email notifications.
  * [formrocket.me](https://www.formrocket.me)  - HTML 表单变得简单，无限制的表单和响应. 附带 Discord 通知等.
  * [formspark.io](https://formspark.io/) -  Form to Email service, free plan allows unlimited forms, 250 submissions per month, support by Customer assistance team.
  * [Formspree.io](https://formspree.io/) — Send email using an HTTP POST request. Free tier limits to 50 submissions per form per month.
  * [Formsubmit.co](https://formsubmit.co/) — Easy form endpoints for your HTML forms. Free Forever. No registration required.
  * [getform.io](https://getform.io/) - Form backend platform for designers and developers, 1 form, 50 submissions, Single file upload, 100MB file storage.
  * [HeroTofu.com](https://herotofu.com/) - Forms backend with bot detection and encrypted archive. Forward submissions via UI to email, Slack, or Zapier. Use your own frontend, no server code required. Free plan gives unlimited forms and 100 submissions per month.
  * [HeyForm.net](https://heyform.net/)  - 拖放在线表单生成器. 免费层可让您创建无限的表单并收集无限的提交. 带有预建模板、反垃圾邮件和 100MB 文件存储.
  * [Hyperforms.app](https://hyperforms.app/) — Create form to email and more in seconds and without backend code. The Personal account gives you up to 50 form submissions per month for free.
  * [Kwes.io](https://kwes.io/) - Feature rich form endpoint. Works great with static sites. Free plan includes up 1 website with up to 50 submissions per month.
  * [Pageclip](https://pageclip.co/) - 免费计划允许一个站点、一个表单、每月 1,000 次提交.
  * [Qualtrics Survey](https://qualtrics.com/free-account) — Create professional forms & survey using this first class tool. 50+ expert-designed survey templates. Free Account has limit of 1 active survey, 100 responses/survey & 8 response types.
  * [smartforms.dev](https://smartforms.dev/) - 为您的网站提供强大而简单的表单后端，永久免费计划允许每月提交 50 次，250MB 文件存储，Zapier 集成，CSV/JSON 导出，自定义重定向，自定义响应页面，Telegram 和 Slack 机器人，单个电子邮件通知.
  * [staticforms.xyz](https://www.staticforms.xyz/) - Integrate HTML forms easily without any server side code for free. After user submits the form an email will be sent to your registered address with form content.
  * [stepFORM.io](https://stepform.io)  - 测验和表格生成器. 免费计划有 5 个表格，每个表格最多 3 个步骤，每月 50 个回复.
  * [Typeform.com](https://www.typeform.com/) — Include beautifully designed forms on websites.  Free plan allows only 10 fields per form and 100 responses per month.
  * [WaiverStevie.com](https://waiverstevie.com) - Electronic Signature platform with a REST API. Receive notifications with webhooks. Free plan watermarks signed documents, but allows unlimited envelopes + signatures.
  * [Web3Forms](https://web3forms.com) - Contact forms for Static & JAMStack Websites without writing backend code. Free plan allows Unlimited Forms, Unlimited Domains & 250 Submissions per month.
  * [WebAsk](https://webask.io) - Survey and Form Builder. Free plan has 3 surveys per account, 100 responses per month, 10 elements per survey.
  * [Wufoo](https://www.wufoo.com/)  - 在网站上使用的快速表格. 免费计划每月有 100 次提交的限制.
  * [formpost.app](https://formpost.app) - Free, unlimited Form to Email service. Setup custom redirect, auto response, webhooks etc for free.


## CDN and Protection

  * [Arvan Cloud](https://arvancloud.com/)  — 提供云相关服务（CDN、Cloud DNS、PaaS、安全等）. 免费计划提供：
    - CDN with Free SSL. 50 GB Traffic + 1 Million HTTP(S) Requests.
    - 无限域的免费云 DNS.
    - Free Cloud Security with Basic DDoS Protection + 5 Firewall Rules.
    - 具有 10 GB 存储 + 50 GB 流量的免费 VoD（视频点播）平台.
  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) — bootstrap、bootswatch 和 fontawesome.io 的 CDN
  * [cdnjs.com](https://cdnjs.com/) — Simple. Fast. Reliable. Content delivery at its finest. cdnjs is a free and open-source CDN service trusted by over 11% of all websites, powered by Cloudflare.
  * [Cloudflare](https://www.cloudflare.com/)
    * CDN 以及免费 SSL
    * Free DNS for unlimited number of domains
    * Firewall rules and pagerules
    * 分析
    * [Cloudflare Pages](https://pages.cloudflare.com/) — Free web hosting (JAMstack platform) for frontend developers to collaborate and deploy websites. 1 build at a time, 500 builds/month, unlimited sites, unlimited requests, unlimited bandwidth.
    * [Cloudflare Workers](https://workers.cloudflare.com/)  — 在 Cloudflare 的全球网络上免费部署无服务器代码. 每天有 100,000 个使用 workers.dev 子域的免费请求.
    * [Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/run-tunnel/trycloudflare)  — 创建从您的服务器到可公开访问、随机生成的 trycloudflare.com 域的隧道. 无需帐户.
  * [Combinatronics](https://combinatronics.com/) - Convert your Github hosted assets (images, CSS, JS, etc.) into CDN assets. Can even render HTML files, for [example from this repo](https://combinatronics.com/ripienaar/free-for-dev/master/index.html). Similar to rawgit.com and raw.githack.com.
  * [ddos-guard.net](https://ddos-guard.net/store/web) — Free CDN, DDoS protection and SSL certificate
  * [developers.google.com](https://developers.google.com/speed/libraries/) — Google 托管库是最流行的开源 JavaScript 库的内容分发网络
  * [GraphCDN](https://graphcdn.io/) - Scale, inspect & protect your GraphQL API. 5m requests per month for free.
  * [jare.io](http://www.jare.io)  — 图像 CDN. 使用 AWS CloudFront
  * [jsdelivr.com](https://www.jsdelivr.com/)  — 一个免费、快速、可靠的开源 CDN. 支持 npm、GitHub、WordPress、Deno 等.
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — The Microsoft Ajax CDN hosts popular third-party JavaScript libraries such as jQuery and enables you to easily add them to your Web application
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) — Free DDoS protection and SSL certificate
  * [PageCDN.com](https://pagecdn.com/) - Offers free Public CDN for everyone, and free Private CDN for opensource / nonprofits.
  * [Skypack](https://www.skypack.dev/)  — 100% 原生 ES 模块 JavaScript CDN. 每个域每月 100 万次请求免费.
  * [raw.githack.com](https://raw.githack.com/) — A modern replacement of **rawgit.com** which simply hosts file using Cloudflare
  * [section.io](https://www.section.io/) <i>— A simple way to spin up and manage a complete Varnish Cache solution.</i> <b>— 一种启动和管理完整 Varnish Cache 解决方案的简单方法。</b> <i>Supposedly free forever for one site</i><b>据说一个网站永久免费</b>
  * [speeder.io](https://speeder.io/) — Uses KeyCDN. Automatic image optimization and free CDN boost. Free and does not require any server changes
  * [statically.io](https://statically.io/) — Git repos（GitHub、GitLab、Bitbucket）、WordPress 相关资产和图像的 CDN
  * [toranproxy.com](https://toranproxy.com/) — Proxy for Packagist and GitHub. Never fail CD. Free for personal use, 1 developer, no support
  * [UNPKG](https://unpkg.com/) — npm 上所有内容的 CDN
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — Free DDoS protection


## PaaS

  * [anvil.works](https://anvil.works)  - 仅使用 Python 进行 Web 应用程序开发. 无限应用的免费套餐.
  * [appharbor.com](https://appharbor.com/) — A .Net PaaS that provides 1 free worker
  * [configure.it](https://www.configure.it/) — Mobile app development platform, free for 2 projects, limited features but no resource limits
  * [codenameone.com](https://www.codenameone.com/) — Open source, cross platform, mobile app development toolchain for Java/Kotlin developers. Free for commercial use with unlimited number of projects
  * [Deta](https://www.deta.sh)  – 免费部署无限数量的 Node.js 和 Python 应用程序. 包括免费的数据库、身份验证和电子邮件.
  * [encore.dev](https://encore.dev/) — Backend framework using static analysis to provide automatic infrastructure, boilerplate free code, and more. Includes free cloud hosting for hobby projects.
  * [gigalixir.com](https://gigalixir.com/) - Gigalixir provide 1 free instance that never sleeps, and free-tier PostgreSQL database limited to 2 connections, 10, 000 rows and no backups, for Elixir/Phoenix apps.
  * [Glitch](https://glitch.com/) — Free public hosting with features such as code sharing and real-time collaboration. Free plan has 1000 hours/month limit.
  * [Heroku](https://www.heroku.com/) — Host your apps in the cloud, free for single process apps
  * [Krucible](https://usekrucible.com)  — Krucible 是一个用于创建用于测试和开发的 Kubernetes 集群的平台. 免费套餐帐户每月提供 25 个集群小时.
  * [Mendix](https://www.mendix.com/) — Rapid Application Development for Enterprises, unlimited number of free sandbox environments supporting unlimited users, 0.5 GB storage and 1 GB RAM per app. Also Studio and Studio Pro IDEs are allowed in free tier.
  * [m3o.com](https://m3o.com)  - API 服务开发的云平台.  M3O 是一个完全托管的微即服务产品，专注于云中的 Go 微服务开发. 免费套餐足以运行 5 项服务并与他人协作.
  * [Okteto Cloud](https://okteto.com)  - 专为远程开发设计的托管 Kubernetes 服务. 免费的开发者账户自带 5 个 Kubernetes 命名空间，3Gi/pod 最多 8Gi/命名空间，1CPU/pod 最多 4CPU/命名空间和 5GB 磁盘空间. 应用程序在 24 小时不活动后进入睡眠状态.
  * [opeNode](https://openode.io) — Free Node.js hosting for Open Source projects. 100 GB Bandwidth/month with 100 MB memory & 1000 MB storage. Deploy using CLI or existing Git repository.
  * [outsystems.com](https://www.outsystems.com/) — Enterprise web development PaaS for on-premise or cloud, free "personal environment" offering allows for unlimited code and up to 1 GB database
  * [pipedream.com](https://pipedream.com)  - 为开发人员构建的集成平台. 基于任何触发器开发任何工作流. 工作流是可以运行的代码 [for free](https://docs.pipedream.com/pricing/) . 无需管理服务器或云资源.
  * [pythonanywhere.com](https://www.pythonanywhere.com/)  — 云 Python 应用程序托管. 初学者帐户是免费的，在 your-username.pythonanywhere.com 域中有 1 个 Python Web 应用程序，512 MB 私人文件存储，一个 MySQL 数据库
  * [scn.sap.com](https://scn.sap.com/docs/DOC-56411)  — SAP 的内存平台即服务产品. 免费的开发者帐户附带 1 GB 结构化、1 GB 非结构化、1 GB Git 数据，并允许您运行 HTML5、Java 和 HANA XS 应用程序
  * [Serverless Cloud](https://www.serverless.com/cloud)  - 无服务器云让您可以使用基础架构 _from_ 代码方法（无 yaml，无基础架构配置）构建无服务器 API、数据库和存储. 该产品由 Serverless Inc. 提供，目前处于公共预览阶段. 
  * [fly.io](https://fly.io/)  - Fly 是一个面向需要在全球范围内运行的应用程序的平台. 它在靠近用户的地方运行您的代码，并在您的应用程序最繁忙的城市扩展计算. 编写您的代码，将其打包成 Docker 映像，将其部署到 Fly 的平台，并让其完成所有工作以保持您的应用程序快速运行. 辅助项目免费，每月 10 美元的服务信用额度自动适用于任何付费服务. 而且，如果您运行非常小的虚拟机，那么积分将大有帮助.
  * [Divio](https://www.divio.com/)  - 管理仅使用 Docker 部署的云应用程序的平台. 可免费订阅开发项目，需要卡且无自定义域支持.  
  * [Koyeb](https://www.koyeb.com) - Koyeb is a developer-friendly serverless platform to deploy apps globally. Seamlessly run Docker containers, web apps, and APIs with git-based deployment, native autoscaling, a global edge network, and built-in service mesh and discovery. Koyeb provides two nano services to run your apps with its forever-free tier and also sponsors open-source projects with free resources.
  * [Railway](https://railway.app)  - 铁路是一个基础架构平台，您可以在其中配置基础架构，在本地使用该基础架构进行开发，然后部署到云端.  1GB 磁盘，512 MB RAM，每月限用 5 美元免费提供.
  * [Napkin](https://www.napkin.io/) - 具有 1Gb 内存的 FaaS，默认超时 15 秒和每月 1,000,000 次免费 API 调用.
  * [Meteor Cloud](https://www.meteor.com/cloud) — Galaxy hosting. Meteor's own platform-as-a-service for Meteor apps which includes a free MongoDB Shared Hosting and automatic SSL.
  * [Northflank](https://northflank.com)  — 使用强大的 UI、API 和 CLI 构建和部署微服务、作业和托管数据库. 从版本控制和外部 Docker 注册表无缝扩展容器. 免费套餐包括 2 个服务、2 个 cron 作业和 1 个数据库.


## BaaS

  * [ably.com](https://www.ably.com) - APIs for realtime messaging, push notifications, and event-driven API creation. Free plan has 3m messages/mo, 100 concurrent connections, 100 concurrent channels.
  * [back4app.com](https://www.back4app.com) - Back4App is an easy-to-use, flexible and scalable backend based on Parse Platform.
  * [backendless.com](https://backendless.com/) — 移动和 Web Baas，提供 1 GB 的免费文件存储空间，每月推送通知 50000 个，表中包含 1000 个数据对象.
  * [BMC Developer Program](https://developers.bmc.com/site/global/bmc_helix_platform/program/overview/index.gsp)  — BMC 开发人员计划提供文档和资源来为您的企业构建和部署数字创新. 访问一个全面的个人沙箱，其中包括平台、SDK 和可用于构建和定制应用程序的组件库.
  * [darklang.com](https://darklang.com/)  - 托管语言与编辑器和基础设施相结合.  Beta 期间免费，Beta 后计划提供慷慨的免费套餐.
  * [Firebase](https://firebase.com)  — Firebase 可帮助您构建和运行成功的应用程序. 免费 Spark 计划提供身份验证、托管、Firebase ML、实时数据库、云存储、测试实验室.  A/B 测试、分析、应用分发、应用索引、云消息传递 (FCM)、Crashlytics、动态链接、应用内消息传递、性能监控、预测和远程配置始终免费.
  * [Flutter Flow](https://flutterflow.io)  — 无需编写任何代码即可构建您的 Flutter App UI. 还具有 Firebase 集成. 免费计划包括对 UI Builder 和免费模板的完全访问权限.
  * [getstream.io](https://getstream.io/) — 在几小时而不是几周内构建可扩展的新闻源、活动流、聊天和消息传递
  * [hasura.io](https://hasura.io/) — Hasura extends your existing databases wherever it is hosted and provides an instant GraphQL API that can be securely accessed for web, mobile, and data integration workloads. Free for 1GB/month of data pass-through.
  * [iron.io](https://www.iron.io/) — 具有免费套餐和 1 个月免费试用的异步任务处理（如 AWS Lambda）
  * [netlicensing.io](https://netlicensing.io)  - 一种经济高效的集成许可即服务 (LaaS) 解决方案，适用于从桌面到物联网和 SaaS 的任何平台上的软件. 学生期间*免费*的基本计划.
  * [nhost.io](https://nhost.io) - Serverless backend for web and mobile apps. Free plan includes: PostgreSQL, GraphQL (Hasura), Authentication, Storage, and Serverless Functions.
  * [onesignal.com](https://onesignal.com/) — 无限制的免费推送通知
  * [paraio.com](https://paraio.com)  — 具有灵活身份验证、全文搜索和缓存的后端服务 API.  1 个应用程序免费，1GB 应用程序数据.
  * [posthook.io](https://posthook.io/)  — 作业调度服务. 允许您安排特定时间的请求.  500 个预定请求/月免费.
  * [progress.com](https://www.progress.com/kinvey) — Mobile backend, starter plan has unlimited requests/second, with 1 GB of data storage. Enterprise application support
  * [pubnub.com](https://www.pubnub.com/) — 每月最多 100 万条消息和 100 台活跃的日常设备的免费推送通知
  * [pushbots.com](https://pushbots.com/) — Push notification service. Free for up to 1.5 million pushes/month
  * [pushcrew.com](https://pushcrew.com/) — Push notification service. Unlimited notifications up to 2000 Subscribers
  * [pusher.com](https://pusher.com/beams)  — 为 2000 名每月活跃用户提供免费、无限制的推送通知. 适用于 iOS 和 Android 设备的单一 API.
  * [pushtechnology.com](https://www.pushtechnology.com/)  — 适用于浏览器、智能手机和所有人的实时消息传递.  100 个并发连接. 免费 10 GB 数据/月
  * [quickblox.com](https://quickblox.com/) — A communication backend for instant messaging, video and voice calling and push notifications
  * [restspace.io](https://restspace.io/) - 为服务器配置身份验证、数据、文件、电子邮件 API、模板等服务，然后组合成管道并转换数据.
  * [Salesforce Developer Program](https://developer.salesforce.com/signup)  — 使用拖放工具快速构建应用程序. 通过点击自定义您的数据模型. 使用 Apex 代码更进一步. 使用强大的 API 与任何东西集成. 保持企业级安全保护. 通过点击或任何领先的 Web 框架自定义 UI. 免费开发者计划可让您访问完整的闪电平台.
  * [ServiceNow Developer Program](https://developer.servicenow.com/) — Rapidly build, test, and deploy applications that make work better for your organization. Free Instance & access early previews.
  * [simperium.com](https://simperium.com/)  — 即时自动移动数据，多平台，无限发送和存储结构化数据，最大.  2,500 个用户/月
  * [stackstorm.com](https://stackstorm.com/) — 应用程序、服务和工作流的事件驱动自动化，免费无流、访问控制、LDAP...
  * [streamdata.io](https://streamdata.io/)  — 将任何 REST API 转变为事件驱动的流式 API. 免费计划多达 100 万条消息和 10 个并发连接.
  * [Supabase](https://supabase.io)  — 构建后端的开源 Firebase 替代方案. 免费计划提供身份验证、实时数据库和对象存储.
  * [tyk.io](https://tyk.io/) — API management with authentication, quotas, monitoring and analytics. Free cloud offering
  * [zapier.com](https://zapier.com/)  — 连接您使用的应用程序，以自动执行任务.  5 zaps，每 15 分钟和 100 个任务/月
  * [LeanCloud](https://leancloud.app/) — Mobile backend. 1GB of data storage, 256MB instance, 3K API requests/day, 10K pushes/day are free. (API is very similar to Parse Platform)
  * [Liteflow](https://liteflow.com/) - 构建的低代码开发工具包可帮助您专注于应用程序的真正价值.
  * [BudiBase](https://budibase.com/) - Budibase is an open-source low-code platform for creating internal apps in minutes. Supports PostgreSQL, MySQL, MSSQL, MongoDB, Rest API, Docker, K8s 


## Web Hosting

  * [Alwaysdata](https://www.alwaysdata.com/) — 100 MB free web hosting with support for MySQL, PostgreSQL, CouchDB, MongoDB, PHP, Python, Ruby, Node.js, Elixir, Java, Deno, custom web servers, access via FTP, WebDAV and SSH; mailbox, mailing list and app installer included.
  * [Awardspace.com](https://www.awardspace.com) — Free web hosting + a free short domain, PHP, MySQL, App Installer, Email Sending & No Ads.
  * [Bubble](https://bubble.io/) — Visual programming to build web and mobile apps without code, free with Bubble branding.
  * [cloudno.de](https://cloudno.de/) — Free cloud hosting for Node.js apps.
  * [Deploy Now](https://deploynow.space)  — 更智能地部署. 部署更快. 立即部署.  - 从您的 GitHub 存储库免费部署多达 3 个 Web 项目.
  * [Drive To Web](https://drv.tw)  — 从 Google Drive 和 OneDrive 直接托管到网络. 仅限静态站点. 永远免费. 每个 Google/Microsoft 帐户一个站点.
  * [Fenix Web Server](https://preview.fenixwebserver.com) - A developer desktop app for hosting sites locally and sharing them publically (in realtime). Work however you like, using its beautiful user interface, API, and/or CLI.
  * [Free Hosting](http://freehostingnoads.net/) — 使用 PHP 5、Perl、CGI、MySQL、FTP、文件管理器、POP 电子邮件、免费子域、免费域托管、DNS 区域编辑器、网站统计信息、免费在线支持和许多其他功能不提供的免费托管其他免费主机.
  * [Freehostia](https://www.freehostia.com)  — FreeHostia 提供免费托管服务，包括. 业界最佳的控制面板和 50 多个免费应用程序的一键安装. 即时设置. 没有强制广告.
  * [hostman.com](https://hostman.com) — 从您的 GitHub 存储库免费部署多达 3 个静态站点.
  * [Neocities](https://neocities.org) — 静态、1 GB 免费存储和 200 GB 带宽.
  * [Netlify](https://www.netlify.com/) — 免费构建、部署和托管静态站点/应用程序，提供 100 GB 数据和 100 GB/月带宽.
  * [Layer0](https://layer0.co/) 在全球 CDN 上部署快速动态 Jamstack 网站 [Limelight](https://www.limelight.com/) for free with 100GB/month bandwidth and 3 environments.
  * [pantheon.io](https://pantheon.io/) — Drupal and WordPress hosting, automated DevOps and scalable infrastructure. Free for developers and agencies
  * [readthedocs.org](https://readthedocs.org/) — 带有版本控制、PDF 生成等功能的免费文档托管
  * [render.com](https://render.com) — Unified cloud to build and run apps and sites with free SSL, a global CDN, private networks, auto-deploys from Git, and completely free plans for web services, databases, and static web pages.
  * [SourceForge](https://sourceforge.net/) — 免费查找、创建和发布开源软件
  * [Stormkit](https://stormkit.io/) — Integrate building, deploying and hosting seamlessly with your git flow of your JAMStack or Node.JS app. 50 GB bandwith and 10m requests for free per month including free SSL.
  * [surge.sh](https://surge.sh/) — Static web publishing for Front-End developers. Unlimited sites with custom domain support
  * [tilda.cc](https://tilda.cc/) — 一个站点，50 个页面，50 MB 存储空间，只有 170 多个可用的主要预定义块，没有字体，没有网站图标，没有自定义域
  * [txti.es](https://txti.es/) — 使用 Markdown 快速创建网页.
  * [Vercel](https://vercel.com/)  — 每次执行“git push”时，使用免费的 SSL、全球 CDN 和唯一的预览 URL 构建、部署和托管 Web 应用程序. 非常适合 Next.js 和其他静态站点生成器.
  * [Versoly](https://versoly.com/) — SaaS focussed website builder - unlimited websites, 70+ blocks, 5 templates, custom CSS, favicon, SEO and forms. No custom domain.
  * [Qovery](https://www.qovery.com)  — Qovery 是在 AWS、GCP 和 Azure 上部署全栈应用程序的最简单方法. 它是面向具有数据库、SSL、全球 CDN 和 Git 自动部署的开发人员的免费 Web 托管.
  * [Qoddi](https://qoddi.com) - PaaS service similar to Heroku with a developer-centric approach and all inclusive features. Free tier for static assets, staging and developer apps.
  * [FreeFlarum](https://freeflarum.com/) - 社区支持的免费 Flarum 托管，最多可容纳 250 个用户（捐赠以从页脚中删除水印）。


## DNS
  * [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) - Free public DNS Resolver which is fast and secure (encrypt your DNS query), provided by CloudFlare. Useful to bypass your internet provider's DNS blocking, prevent DNS query spying, and [to block adult & malware content](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families) . 也可以使用 [via API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests). Note: Just a DNS resolver, not a DNS hoster.
  * [1984.is](https://www.1984.is/product/freedns/) — 带有 API 的免费 DNS 服务，以及许多其他免费的 DNS 功能.
  * [biz.mail.ru](https://biz.mail.ru) — Free email and DNS hosting for up to 5,000 users
  * [cloudns.net](https://www.cloudns.net/) — Free DNS hosting up to 1 domain with 50 records
  * [dns.he.net](https://dns.he.net/) — 具有动态 DNS 支持的免费 DNS 托管服务
  * [dnspod.com](https://www.dnspod.com/) — 免费 DNS 托管.
  * [duckdns.org](https://www.duckdns.org/)  — 免费 DDNS，免费套餐最多包含 5 个域. 带有各种设置的配置指南.
  * [dynu.com](https://www.dynu.com/) — Free dynamic DNS service
  * [fosshost.org](https://fosshost.org/) - Free open source hosting VPS, web, storage and mirror hosting
  * [freedns.afraid.org](https://freedns.afraid.org/) — Free DNS hosting. Also provide free subdomain based on numerous public user [contributed domains](https://freedns.afraid.org/domain/registry/) . 注册后从“子域”菜单中获取免费子域.
  * [luadns.com](https://www.luadns.com/) — Free DNS hosting, 3 domains, all features with reasonable limits
  * [namecheap.com](https://www.namecheap.com/domains/freedns/)  — 免费 DNS. 域名数量没有限制
  * [nextdns.io](https://nextdns.io) - 基于 DNS 的防火墙，每月 30 万次免费查询
  * [noip](https://www.noip.com/) — 一种动态 dns 服务，最多允许 3 个免费主机名，每 30 天确认一次
  * [ns1.com](https://ns1.com/) — 数据驱动的 DNS、自动流量管理、50 万次免费查询
  * [nsupdate.info](https://www.nsupdate.info/) — 免费和开源的动态 DNS 服务
  * [pointhq.com](https://pointhq.com/developer) — Free DNS hosting on Heroku.
  * [selectel.com](https://selectel.com/services/dns/) — Free DNS hosting with unlimited records, anycast
  * [web.gratisdns.dk](https://web.gratisdns.dk/domaener/dns/) — 免费 DNS 托管.
  * [Yandex.Connect](https://connect.yandex.com/pdd/) — 最多可容纳 1,000 名用户的免费电子邮件和 DNS 托管
  * [zilore.com](https://zilore.com/en/dns) — 免费 DNS 托管.
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) — Free DNS hosting with Dynamic DNS Support.
  * [zonewatcher.com](https://zonewatcher.com)  — 自动备份和 DNS 更改监控.  1 个免费域名
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – 华为提供的免费 DNS 托管
  * [Hetzner](https://www.hetzner.com/dns-console) – Free DNS hosting from Hetzner with API support
  * [Glauca](https://docs.glauca.digital/hexdns/) – Free DNS hosting for up to 3 domains and DNSSEC support


## IaaS

  * [filebase.com](https://filebase.com/) - S3 Compatible Object Storage Powered by Blockchain. 5 GB free storage for unlimited duration.
  * [backblaze.com](https://www.backblaze.com/b2/) — Backblaze B2 cloud storage. Free 10 GB (Amazon S3-like) object storage for unlimited time
  * [scaleway.com](https://www.scaleway.com/en/object-storage/) — S3-Compatible Object Storage. Free 75 GB storage and external outgoing traffic
  * [terraform.io](https://www.terraform.io/) — Terraform Cloud. Free remote state management and team collaboration for teams up to 5 users.


## DBaaS

   * [airtable.com](https://airtable.com/) — 看起来像一个电子表格，但它是一个关系数据库、无限的基数、1,200 行/基数和 1,000 个 API 请求/月
   * [Astra](https://www.datastax.com/products/datastax-astra/) — 云原生 Cassandra 即服务 [80GB free tier](https://www.datastax.com/products/datastax-astra/pricing)
   * [bit.io](https://bit.io) — PostgreSQL managed database service. Unlimited repos, 10GB storage, 10M queried rows/month.
   * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ as a Service, up to 1M messages/month and 20 connections free
   * [elephantsql.com](https://www.elephantsql.com/) — PostgreSQL 即服务，20 MB 免费
   * [FaunaDB](https://fauna.com/) — Serverless cloud database, with native GraphQL, multi-model access and daily free tiers up to 100 MB
   * [HarperDb](https://harperdb.io/) — 无服务器云数据库，具有基于 JSON 的动态模式，3000 IOPS 和 1GB 存储
   * [heroku.com](https://www.heroku.com/) — PostgreSQL 即服务，最多 10,000 行和 20 个免费连接（作为“插件”提供，但可以附加到其他空的应用程序并从外部访问）
   * [Upstash](https://upstash.com/) — Serverless Redis with free tier up to 10,000 requests per day, 256MB max database size, and 20 concurrent connections
   * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — free tier gives 512 MB
   * [redsmin.com](https://www.redsmin.com/) — Redis在线实时监控和管理服务，免费监控1个Redis实例
   * [redislabs](https://redislabs.com/try-free/) - 免费 30Mb redis 实例
   * [MemCachier](https://www.memcachier.com/) — Managed Memcache service. Free for up to 25MB, 1 Proxy Server and basic analytics
   * [scalingo.com](https://scalingo.com/) — 主要是 PaaS，但提供 128MB 到 192MB 的 MySQL、PostgreSQL 或 MongoDB 免费层
   * [SeaTable](https://seatable.io/) — Flexible, Spreadsheet-like Database built by Seafile team. unlimited tables, 2,000 lines, 1-month versioning, up to 25 team members.
   * [skyvia.com](https://skyvia.com/) — Cloud Data Platform, offers free tier and all plans are completely free while in beta
   * [StackBy](https://stackby.com/)  — 一款将电子表格的灵活性、数据库的强大功能以及与您最喜欢的业务应用程序的内置集成相结合的工具. 免费计划包括无限用户、10 个堆栈、每个堆栈 2GB 附件.
   * [InfluxDB](https://www.influxdata.com/) — Timeseries database, free up to 3MB/5 minutes writes, 30MB/5 minutes reads and 10,000 cardinalities series
   * [Quickmetrics](https://www.quickmetrics.io/) — 包含仪表板的时间序列数据库，每天最多释放 10,000 个事件和总共 5 个指标.
   * [restdb.io](https://restdb.io/)  - 快速简单的 NoSQL 云数据库服务. 使用 restdb.io，您可以获得模式、关系、自动 REST API（带有类似 MongoDB 的查询）和用于处理数据的高效多用户管理 UI. 免费计划每秒允许 3 个用户、2500 条记录和 1 个 API 请求.
   * [cockroachlabs.com](https://www.cockroachlabs.com/free-tier/) — Free CockroachDB up to 5GB and 1vCPU (limited [request units](https://www.cockroachlabs.com/docs/cockroachcloud/serverless-faqs.html#what-are-the-usage-limits-of-cockroachdb-serverless-beta))
   * [Neo4j Aura](https://neo4j.com/cloud/aura/) — Managed native Graph DBMS / analytics platform with a Cypher query language and a REST API. Limits on graph size (50k nodes, 175k relationships).
   * [Dgraph Cloud](https://cloud.dgraph.io/pricing?type=free)  — 使用 GraphQL API 托管本机 Graph DBMS. 每天限制为 1 MB 数据传输.
   * [TigerGraph Cloud](https://www.tigergraph.com/cloud/)  — 使用类似 SQL 的图形查询语言和 REST API 的托管原生图形 DBMS/分析平台.  AWS（4 个 vCPU，7.5 GB 内存，50 GB 磁盘）或 GCP（2 个 vCPU，8 GB 内存，128 GB 磁盘）上的 1 个 TG.Free 实例. 免费实例在闲置 1 小时后休眠.
   * [TerminusX](https://terminusdb.com/) — Managed free service for TerminusDB, a document and graph database written in Prolog and Rust. Free for dev, paid service for enterprise deployments and support.
   * [Macrometa](https://www.macrometa.com/) - a noSQL database, Pub/Sub, event processing, and serverless edge computing platform for building geo-distributed and real-time applications. Free dev account gives access to 10,000 Operations/Day & 200MB Storage.
   * [Planetscale](https://planetscale.com/) - PlanetScale is a MySQL compatible, serverless database platform powered by Vitess, 3 databases for free with 10GB storage, 100 Million rows read/mo per database, and 10 Million rows written/mo per database.
   * [YugabyteDB](http://cloud.yugabyte.com) - YugabyteDB is a distributed SQL database compatible with PostgresSQL. The cloud free tier is a 2 vCPU, 4GB RAM, 10GB Disk.


## Tunneling, WebRTC, Web Socket Servers and Other Routers

   * [conveyor.cloud](https://conveyor.cloud/) — Visual Studio extension to expose IIS Express to the local network or over a tunnel to a public URL.
   * [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi is a hosted VPN service that lets you securely extend LAN-like networks to distributed teams with free plan allows unlimited networks with up to 5 peoples
   * [localhost.run](https://localhost.run/) — Expose locally running servers over a tunnel to a public URL.
   * [localtunnel](https://theboroer.github.io/localtunnel-www/) — Expose locally running servers over a tunnel to a public URL. Free hosted version, and [open source](https://github.com/localtunnel/localtunnel).
   * [ngrok.com](https://ngrok.com/) — Expose locally running servers over a tunnel to a public URL.
   * [Radmin VPN](https://www.radmin-vpn.com/) — Connect multiple computers together via a VPN enabling LAN-like networks. Unlimited peers. (Hamachi alternative)
   * [segment.com](https://segment.com/) — Hub to translate and route events to other third-party services. 100,000 events/month free
   * [STUN](https://en.wikipedia.org/wiki/STUN) — Session Traversal of User Datagram Protocol [UDP] Through Network Address Translators [NATs])
     * Google STUN — [https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302](https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302)
     * Twilio STUN — [https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp](https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp)
   * [Tailscale](https://tailscale.com/)  — 零配置 VPN，使用开源 WireGuard 协议. 安装在 MacOS、iOS、Windows、Linux 和 Android 设备上.  20 台设备供个人使用的免费计划.
   * [webhookrelay.com](https://webhookrelay.com) <i>— Manage, debug, fan-out and proxy all your webhooks to public or internal (ie: localhost) destinations.</i> <b>— 管理、调试、扇出和代理所有 webhook 到公共或内部（即：localhost）目的地。</b> <i>Also, expose servers running in a private network over a tunnel by getting a public HTTP endpoint (`https://yoursubdomain.webrelay.io &lt;----&gt; http://localhost:8080`).</i><b>此外，通过获取公共 HTTP 端点（`https://yoursubdomain.webrelay.io &lt;----&gt; http://localhost:8080`），通过隧道公开在专用网络中运行的服务器。</b>
   * [Xirsys](https://www.xirsys.com) — Global network of STUN / TURN servers with a generous free tier.
   * [ZeroTier](https://www.zerotier.com) — FOSS managed virtual Ethernet as a service. Unlimited end-to-end encrypted networks of 100 clients on free plan. Clients for desktop/mobile/NA; web interface for configuration of custom routing rules and approval of new client nodes on private networks.


## Issue Tracking and Project Management

   * [acunote.com](https://www.acunote.com/) — Free project management and SCRUM software for up to 5 team members
   * [asana.com](https://asana.com/) — 与合作者的私人项目免费
   * [Backlog](https://backlog.com)  — 您的团队在一个平台上发布伟大项目所需的一切. 免费计划提供 1 个具有 10 个用户和 100MB 存储空间的项目.
   * [Basecamp](https://basecamp.com/personal) - To-do lists, milestone management, forum-like messaging, file sharing, and time tracking. Up to 3 projects, 20 users, and 1GB of storage space.
   * [bitrix24.com](https://www.bitrix24.com/) — 免费的内网和项目管理工具
   * [cacoo.com](https://cacoo.com/)  — 实时在线图表：流程图、UML、网络. 免费最大.  15 个用户/图表，25 张
   * [Chpokify](https://chpokify.com/) — Teams based Planning Poker that saves time of sprint estimation. Free up to 5 users, free Jira integrations, unlimited video calls, unlimited teams, unlimited sessions.
   * [clickup.com](https://clickup.com/) — Project management. Free, premium version with cloud storage. Mobile applications and Git integrations available
   * [Cloudcraft](https://cloudcraft.co/) — Design a professional architecture diagram in minutes with the Cloudcraft visual designer, optimized for AWS with smart components that show live data too.
   * [Codegiant](https://codegiant.io)  — 使用存储库托管和 CI/CD 进行项目管理. 免费计划提供无限的存储库、项目和文档，有 5 名团队成员. 每月 500 CI/CD 分钟. 每月 30000 分钟无服务器代码运行时间.1GB 存储库存储.
   * [Confluence](https://www.atlassian.com/software/confluence)  - Atlassian 的内容协作工具，用于帮助团队高效协作和共享知识. 免费计划最多 10 个用户.
   * [contriber.com](https://www.contriber.com/) — 可定制的项目管理平台，免费入门计划，5 个工作区
   * [draw.io](https://www.draw.io/)  — 存储在本地、Google Drive、OneDrive 或 Dropbox 中的在线图表. 免费提供所有功能和存储级别
   * [freedcamp.com](https://freedcamp.com/) - tasks, discussions, milestones, time tracking, calendar, files and password manager. Free plan with unlimited projects, users and files storage.
   * [easyretro.io](https://www.easyretro.io/) — Free simple and intuitive sprint retrospective tool
   * [GForge](https://gforge.com)  — 用于具有自建和 SaaS 选项的复杂项目的项目管理和问题跟踪工具集.  SaaS 免费计划为前 5 名用户免费提供开源项目.
   * [gleek.io](https://www.gleek.io)  — 面向开发人员的免费描述到图表工具. 使用关键字创建非正式的 UML 类、对象或实体关系图.
   * [gliffy.com](https://www.gliffy.com/) — Online diagrams: flowchart, UML, wireframe,... Also plugins for Jira and Confluence. 5 diagrams and 2 MB free
   * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - GraphQL Inspector ouputs a list of changes between two GraphQL schemas. Every change is precisely explained and marked as breaking, non-breaking or dangerous.
   * [huboard.com](https://huboard.com/) — Instant project management for your GitHub issues, free for Open Source
   * [Hygger](https://hygger.io) — Project management platform. Free plan offers unlimited users,projects & boards with 100 MB Storage.
   * [Instabug](https://instabug.com) —  A comprehensive bug reporting and in-app feedback SDK for mobile apps. Free plan up to 1 app and 1 member.
   * [Ilograph](https://www.ilograph.com/)  — interactive diagrams that allow users to see their infrastructure from multiple perspectives and levels of detail. Diagrams can be expressed in code. Free tier has unlimited private diagrams with up to 3 viewers.
   * [Issue Embed](https://issueembed.dev/) - A bug reporting tool for websites to go directly into your Github Issues. Free plan for personal repositories with up to 500 issues/month and 10,000 page views/month.
   * [Jira](https://www.atlassian.com/software/jira) — Advanced software development project management tool used in many corporate environments. Free plan up to 10 users.
   * [kanbanflow.com](https://kanbanflow.com/) — Board-based project management. Free, premium version with more options
   * [kanbantool.com](https://kanbantool.com/)  — 基于看板的项目管理. 免费的付费计划，有更多选择
   * [Kitemaker.co](https://kitemaker.co) - Collaborate through all phases of the product development process and keep track of work across Slack, Discord, Figma, and Github. Unlimited users, unlimited spaces. Free plan up to 250 work items.
   * [Kumu.io](https://kumu.io/)  — Relationship maps with animation, decorations, filters, clustering, spreadsheet imports and more. Free tier allows unlimited public projects. Graph size unlimited. Free private projects for students. Sandbox mode is available if you prefer to not leave your file publicly online (upload, edit, download, discard).
   * [LeanBoard](https://www.leanboard.io) — 为您的 GitHub 问题提供便签的协作白板（适用于示例映射和其他技术）
   * [Linear](https://linear.app/) — Issue tracker with streamlined interface. Free for unlimited members, up to 10MB file upload size, 250 issues (excluding Archive)
   * [MeisterTask](https://www.meistertask.com/) — Online task management for teams. Free up to 3 projects, unlimited project members.
   * [MeuScrum](https://www.meuscrum.com/en) - Free online scrum tool with kanban board
   * [nTask](https://www.ntaskmanager.com/) — Project management software that enables your teams tn collaborate, plan, analyze and manage everyday tasks. Basic Plan free forever with 100 MB storage, 5 users/team. Unlimited workspaces, meetings,tasks, timesheets and issue tracking.
   * [Ora](https://ora.pm/) - Agile task management & team collaboration. Free for up to 3 users and files are limited to 10 MB.
   * [pivotaltracker.com](https://www.pivotaltracker.com/) — 对无限的公共项目和两个私人项目免费，总共有 3 个活跃用户（读写）和无限的被动用户（只读）.
   * [plan.io](https://plan.io/)  — 使用存储库托管和更多选项进行项目管理.  2 位用户免费，10 位客户和 500MB 存储空间
   * [planitpoker.com](https://www.planitpoker.com/) — Free online planning poker (estimation tool)
   * [saas.zentao.pm](https://saas.zentao.pm/) - An Application Lifecycle Management solution for Issue Tracking and Project Management, on-premise and open source version are available as well.
   * [ScrumFast](https://www.scrumfast.com) - Scrum 板具有非常直观的界面，最多可释放 5 个用户.
   * [Shortcut](https://shortcut.com/) - Project management platform. Free for up to 10 users forever.
   * [SpeedBoard](https://speedboard.app) - Board for Agile and Scrum retrospectives - Free.
   * [Shake](https://www.shakebugs.com/)  - 适用于移动应用的应用内错误报告和反馈工具. 免费计划，每个应用程序/每月 10 个错误报告.
   * [Tadum](https://tadum.app) - 专为定期会议设计的会议议程和会议记录应用程序，最多 10 人的团队可免费使用
   * [taiga.io](https://taiga.io/) — 面向初创公司和敏捷开发人员的项目管理平台，开源免费
   * [Tara AI](https://tara.ai/)  — 简单的冲刺管理服务. 免费计划有无限的任务、冲刺和工作空间，没有用户限制.
   * [targetprocess.com](https://www.targetprocess.com/)  — 可视化项目管理，从看板和 Scrum 到几乎任何操作流程. 无限用户免费，最多 1,000 个数据实体 {[more details](https://www.targetprocess.com/pricing/)}
   * [taskade.com](https://www.taskade.com/) — 团队的实时协作任务列表和大纲
   * [taskulu.com](https://taskulu.com/) — Role based project management. Free up to 5 users. Integration with GitHub/Trello/Dropbox/Google Drive
   * [teamwork.com](https://teamwork.com/)  — 项目管理和团队聊天.  5 个用户和 2 个项目免费. 提供高级计划.
   * [testlio.com](https://testlio.com/) — Issue tracking, test management and beta testing platform. Free for private use
   * [terrastruct.com](https://terrastruct.com/) — Online diagram maker specifically for software architecture. Free tier up to 4 layers per diagram.
   * [todoist.com](https://todoist.com/) — Collaborative and individual task management. Free, Premium and Team plans are available. Discounts provided for eligible users.
   * [trello.com](https://trello.com/)  — 基于董事会的项目管理. 无限的个人板，10 个团队板.
   * [Tweek](https://tweek.so/) — Simple Weekly To-Do Calendar & Task Management.
   * [ubertesters.com](https://ubertesters.com/) — 测试平台、集成和众测者，2 个项目，5 名成员
   * [vabotu](https://vabotu.com/) - A collaborative tool for project management. Free and other plans are available. The Freelance plan is for 10 users, include messaging, task-boards, 5GB online storage, workspaces, export data.
   * [vivifyscrum.com](https://www.vivifyscrum.com/)  — 敏捷项目管理的免费工具.  Scrum 兼容
   * [Wikifactory](https://wikifactory.com/) — Product designing Service with Projects, VCS & Issues. Free plan offers unlimited projects & collaborators and 3GB storage.
   * [Yodiz](https://www.yodiz.com/)  — 敏捷开发和问题跟踪. 最多释放 3 个用户，无限项目.
   * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) — Free hosted YouTrack (InCloud) for FOSS projects, private projects (free for 3 users). Includes time tracking and agile boards
   * [zenhub.com](https://www.zenhub.com)  — GitHub 内唯一的项目管理解决方案. 公共存储库、OSS 和非营利组织免费
   * [zepel.io](https://zepel.io/)  - 项目管理工具，可让您规划功能、跨学科协作以及共同构建软件. 最多释放 5 名成员. 没有功能限制.
   * [zenkit.com](https://zenkit.com)  — 项目管理和协作工具. 最多 5 名成员免费，5 GB 附件.
   * [Zube](https://zube.io)  — 为 4 个项目和 4 个用户提供免费计划的项目管理.  GitHub 集成可用.
   * [Toggl](https://toggl.com/) — Provides 2 free productivity tools. [Toggl Track](https://toggl.com/track/) 具有免费计划的时间管理和跟踪应用程序提供了专为自由职业者设计的无缝时间跟踪和报告. 它具有无限的跟踪记录、项目、客户、标签、报告等. 和 [Toggl Plan](https://toggl.com/plan/) 为独立开发者提供免费计划的任务计划，具有无限的任务、里程碑和时间表.


## Storage and Media Processing

   * [borgbase.com](https://www.borgbase.com/)  — Borg Backup 的简单安全的异地备份托管.  10 GB 可用备份空间和 2 个存储库.
   * [icedrive.net](https://www.icedrive.net/) - Simple cloud storage service. 10 GB free storage
   * [sync.com](https://www.sync.com/) - End-to-End cloud storage service. 5 GB free storage
   * [pcloud.com](https://www.pcloud.com/) <i>- Cloud storage service.</i> <b>- 云存储服务。</b> <i>Up to 10 GB free storage</i><b>高达 10 GB 的免费存储空间</b>
   * [sirv.com](https://sirv.com/) — Smart Image CDN with on-the-fly image optimization and resizing. Free tier includes 500 MB of storage and 2 GB bandwidth.
   * [image4.io](https://image4.io/) — Image upload, powerful manipulations, storage and delivery for websites and apps, with SDK's, integrations and migration tools. Free tier includes 25 credits. 1 credit is equal to 1 GB of CDN usage, 1GB of storage or 1000 image transformations.
   * [cloudimage.com](https://cloudimage.com/)  — 全面的图像优化和 CDN 服务，在全球拥有 1500 多个入网点. 多种图像缩放、压缩、水印功能. 用于响应式图像、360 度图像制作和图像编辑的开源插件. 免费的月度计划，包含 25GB 的 CDN 流量和 25GB 的缓存存储和无限转换.
   * [cloudinary.com](https://cloudinary.com/)  — 用于网站和应用程序的图像上传、强大的操作、存储和交付，以及用于 Ruby、Python、Java、PHP、Objective-C 等的库. 免费套餐包括 25 个每月积分.  1 个积分等于 1,000 个图像转换、1 GB 的存储空间或 1 GB 的 CDN 使用量.
   * [easyDB.io](https://easydb.io/)  — 一键式托管数据库提供商. 它们为您选择的用于开发目的的编程语言提供数据库. 该数据库是短暂的，将在免费层 24 或 72 小时后删除.
   * [embed.ly](https://embed.ly/) — Provides APIs for embedding media in a webpage, responsive image scaling, extracting elements from a webpage. Free for up to 5,000 URLs/month at 15 requests/second
   * [filestack.com](https://www.filestack.com/) — 文件选择器、转换和交付，免费提供 250 个文件、500 个转换和 3 GB 带宽
   * [gumlet.com](https://www.gumlet.com/)  — 图像调整大小即服务. 它还优化图像并通过 CDN 执行交付. 免费套餐包括 1 GB 带宽和 1 年内每月不限次数的图像处理.
   * [image-charts.com](https://www.image-charts.com/) — 带水印的无限图像图表生成
   * [imgen](https://www.jitbit.com/imgen/) - Free unlimited social cover image generation API, no watermark
   * [jsonbin.io](https://jsonbin.io/) — Free JSON data storage service, ideal for small-scale web apps, website, mobile apps.
   * [kraken.io](https://kraken.io/) — 图像优化网站性能即服务，免费计划高达 1 MB 文件大小
   * [npoint.io](https://www.npoint.io/) — 具有协作模式编辑的 JSON 存储
   * [otixo.com](https://www.otixo.com/) — Encrypt, share, copy and move all your cloud storage files from one place. Basic plan provides unlimited files transfer with 250 MB max. file size and allows 5 encrypted files
   * [packagecloud.io](https://packagecloud.io/) — Hosted Package Repositories for YUM, APT, RubyGem and PyPI.  Limited free plans, open source plans available via request
   * [piio.co](https://piio.co/)  — 每个网站的响应式图像优化和交付. 开发人员和个人网站的免费计划. 包括开箱即用的免费 CDN、WebP 和延迟加载.
   * [Pinata IPFS](https://pinata.cloud) — Pinata is the simplest way to upload and manage files on IPFS. Our friendly user interface combined with our IPFS API makes Pinata the easiest IPFS pinning service for platforms, creators, and collectors. 1 GB storage free along with access to API.
   * [placeholder.com](https://placeholder.com/) — A quick and simple image placeholder service
   * [placekitten.com](https://placekitten.com/) — A quick and simple service for getting pictures of kittens for use as placeholders
   * [plot.ly](https://plot.ly/) — Graph and share your data. Free tier includes unlimited public files and 10 private files
   * [podio.com](https://podio.com/) — 您可以与最多五人的团队一起使用 Podio，并试用基本计划的功能，但用户管理除外
   * [QuickChart](https://quickchart.io) — Generate embeddable image charts, graphs, and QR codes
   * [redbooth.com](https://redbooth.com) — P2P 文件同步，最多 2 位用户免费
   * [Skynet](https://siasky.net) — An open protocol for hosting data and web applications on the decentralized web using [Sia](https://sia.tech/). Free tier provides storage upto 100GB.
   * [Storj](https://storj.io) — Decentralised Private Cloud Storage for Apps and Developers. Free plan provides 3 Projects, 50 GB storage per project/month , 50 GB bandwidth per project/month.
   * [tinypng.com](https://tinypng.com/) — API to compress and resize PNG and JPEG images, offers 500 compressions for free each month
   * [transloadit.com](https://transloadit.com/)  — 处理文件上传和视频、音频、图像、文档的编码. 通过 GitHub 学生开发包免费为开源、慈善机构和学生提供. 商业应用程序可免费获得 2 GB 用于试驾
   * [twicpics.com](https://www.twicpics.com) - Responsive images as a service. It provides an image CDN, a media processing API and frontend library to automate image optimization. The service is free up to 3GB trafic/month.
   * [uploadcare.com](https://uploadcare.com/hub/developers/) — Uploadcare provides media pipeline  with ultimate toolkit based on cutting-edge algorithms. All features are available for developers absolutely for free: File Uploading API and UI, Image CDN and Origin Services, Adaptive Delivery and Smart Compression. Limit free tier has 3000 uploads, 3 GB traffic and 3 GB storage.
   * [imagekit.io](https://imagekit.io)  – 具有自动优化、实时转换和存储功能的图像 CDN，您可以在几分钟内与现有设置集成. 免费计划包括每月高达 20GB 的带宽.
   * [internxt.com](https://internxt.com)  – Internxt Drive 是一种基于绝对隐私和毫不妥协的安全性的零知识文件存储服务. 注册并永久免费获得 2 GB！
   * [degoo.com](https://degoo.com/) – 基于 AI 的云存储，最多可免费使用 100 Gb、5 台设备、500 Gb 推荐奖金（365 天帐户不活动）.



## Design and UI

  * [AllTheFreeStock](https://allthefreestock.com) - a curated list of free stock images, audio and videos.
  * [Ant Design Landing Page](https://landing.ant.design/)  - Ant Design Landing Page 提供了由 Ant Motion 的运动组件构建的模板. 拥有丰富的首页模板，模板代码包下载，快速上手. 您还可以使用编辑器快速构建自己的专用页面.
  * [Backlight](https://backlight.dev/) — Backlight 以开发人员和设计师之间的协作为核心，是一个非常完整的编码平台，团队可以在其中构建、记录、发布、扩展和维护设计系统.免费计划允许多达 3 位编辑在一个设计系统上工作，且查看者不受限制.
  * [BoxySVG](https://boxy-svg.com/app) — A free installable Web app for drawing SVGs and exporting in svg,png,jpeg an other formats.
  * [clevebrush.com](https://www.cleverbrush.com/) — Free Graphics Design / Photo Collage App, also they offer paid integration of it as component.
  * [cloudconvert.com](https://cloudconvert.com/)  — 将任何东西转换为任何东西.  208 种支持的格式，包括视频到 gif.
  * [CodeMyUI](https://codemyui.com) - Handpicked collection of Web Design & UI Inspiration with Code Snippets.
  * [coolors](https://coolors.co/)  - 调色板生成器. 自由.
  * [designer.io](https://www.designer.io/) — Design tool for UI, illustrations and more. Has a native app. Free.
  * [figma.com](https://www.figma.com)  — 用于团队的在线协作设计工具； 免费层包括无限的文件和查看器，最多 2 个编辑器和 3 个项目.
  * [framer.com](https://www.framer.com/) - Framer helps you iterate and animate interface ideas for your next app, website, or product—starting with powerful layouts. For anyone validating Framer as a professional prototyping tool: unlimited viewers, up to 2 editors, up to 3 projects.
  * [Gradientos](https://www.gradientos.app) - 使选择渐变变得快速而简单.
  * [Icon Horse](https://icon.horse) – Get the highest resolution favicon for any website from our simple API.
  * [Icons8](https://icons8.com) — Icons, illustrations, photos, music, and design tools. Free Plan offers Limited formats in lower resolution. Link to Icons8 when you use our assets.
  * [imagebin.ca](https://imagebin.ca/) — Pastebin for images.
  * [Invision App](https://www.invisionapp.com)  - UI 设计和原型制作工具. 桌面和网络应用程序可用. 免费使用 1 个活动原型.
  * [landen.co](https://www.landen.co)  — 为您的创业公司生成、编辑和发布精美的网站和登录页面. 全部没有代码. 免费套餐允许您拥有一个完全可定制并在网络上发布的网站.
  * [lensdump.com](https://lensdump.com/) - 免费云图像托管.
  * [Lorem Picsum](https://picsum.photos/)  - 免费工具，易于使用的时尚占位符. 只需在我们的 URL 后添加您想要的图像尺寸（宽度和高度），您就会得到一张随机图像.
  * [LottieFiles](https://lottiefiles.com/) - The world’s largest online platform for the world’s smallest animation format for designers, developers, and more. Access Lottie animation tools and plugins for Android, iOS, and Web.
  * [MagicPattern](https://www.magicpattern.design/tools) — 用于渐变、图案和 blob 的 CSS 和 SVG 背景生成器和工具的集合.
  * [marvelapp.com](https://marvelapp.com/) — 设计、原型制作和协作，免费计划仅限于一个用户和一个项目.
  * [Mindmup.com](https://www.mindmup.com/) — Unlimited mind maps for free, and store them in the cloud. Your mind maps are available everywhere, instantly, from any device.
  * [Mockplus iDoc](https://www.mockplus.com/idoc)  - Mockplus iDoc 是一个强大的设计协作和交接工具. 免费计划包括 3 个用户和 5 个具有所有可用功能的项目.
  * [mockupmark.com](https://mockupmark.com/create/free) — 为社交媒体和电子商务创建逼真的 T 恤和服装模型，40 个免费模型.
  * [Octopus.do](https://octopus.do)  — 视觉站点地图生成器. 实时构建您的网站结构并快速共享它以与您的团队或客户协作.
  * [Pencil](https://github.com/evolus/pencil) - Open source design tool using Electron.
  * [Penpot](https://penpot.app)  - 基于 Web 的开源设计和原型制作工具. 支持 SVG. 完全免费.
  * [pexels.com](https://www.pexels.com/) - Free stock photos for commercial use. Has free API that allows you to search photos by keywords.
  * [photopea.com](https://www.photopea.com) — A Free, Advanced online design editor with Adobe Photoshop UI supporting PSD, XCF & Sketch formats (Adobe Photoshop, Gimp and Sketch App).
  * [pixlr.com](https://pixlr.com/) — Free online browser editor on the level of commercial ones.
  * [Plasmic](https://www.plasmic.app/)  - 一个快速、易于使用、功能强大的网页设计工具和页面构建器，可集成到您的代码库中. 构建响应式页面或复杂组件； 可选用代码扩展； 并发布到生产站点和应用程序.
  * [Pravatar](https://pravatar.cc/) - 生成随机/占位符假头像，该网址可以直接在您的网络/应用程序中进行热链接.
  * [Proto.io](https://www.proto.io)  - 无需编码即可创建完全交互式的 UI 原型. 免费试用期结束时可用的免费层级. 免费套餐包括：1 个用户、1 个项目、5 个原型、100MB 在线存储和 proto.io 应用程序中的预览.
  * [resizeappicon.com](https://resizeappicon.com/) — 一个简单的服务来调整和管理您的应用程序图标.
  * [Rive](https://rive.app)  — 创建精美的动画并将其发送到任何平台. 个人永久免费. 该服务是一个编辑器，它也在其服务器上托管所有图形. 它们还为许多平台提供运行时以运行使用 Rive 制作的图形.
  * [smartmockups.com](https://smartmockups.com/) — 创建产品模型，200 个免费模型.
  * [tabler-icons.io](https://tabler-icons.io/) — Over 1500 free copy and paste SVG editable icons.
  * [UI Avatars](https://ui-avatars.com/) - Generate avatars with initials from names. Which the urls can be directly hotlinked in your web/app. Support config parameters via the url.
  * [unDraw](https://undraw.co/) - A constantly updated collection of beautiful svg images that you can use completely free and without attribution.
  * [unsplash.com](https://unsplash.com/) - Free stock photos for commercial and noncommercial purposes (do-whatever-you-want license).
  * [vectr.com](https://vectr.com/) — Free Design App for Web + Desktop.
  * [walkme.com](https://www.walkme.com/) — Enterprise Class Guidance and Engagement Platform, free plan 3 walk-thrus up to 5 steps/walk.
  * [Webflow](https://webflow.com)  - 具有动画和网站托管的所见即所得网站构建器.  2个项目免费.
  * [Updrafts.app](https://updrafts.app)  - 所见即所得网站构建器，用于基于 tailwindcss 的设计. 免费用于非商业用途.
  * [whimsical.com](https://whimsical.com/) - Collaborative flowcharts, wireframes, sticky notes and mind maps. Create up to 4 free boards.
  * [Zeplin](https://zeplin.io/) — Designer and developer collaboration platform. Show designs, assets and styleguides. Free for 1 project.
  * [Pixelixe](https://pixelixe.com/) — 在线创建和编辑引人入胜且独特的图形和图像.
  * [Responsively App](https://responsively.app) - A free dev-tool for faster and precise responsive web application development.
  * [SceneLab](https://scenelab.io) - Online mockup graphics editor with an ever-expanding collection of free design templates
  * [xLayers](https://xlayers.dev) - Preview and convert Sketch design files into Angular, React, Vue, LitElement, Stencil, Xamarin and more (free and open source at https://github.com/xlayers/xlayers)
  * [Grapedrop](https://grapedrop.com/) — Responsive, powerful, SEO optimized web page builder based on GrapesJS Framework. Free for first 5 pages, unlimited custom domains, all features and simple usage.
  * [Mastershot](https://mastershot.app) - Completely free browser-based video editor. No watermark, up to 1080p export options.
  * [Unicorn Platform](https://unicornplatform.com/) - Effortless landing page builder with hosting. 1 website for free.
  * [react-favicon.com](https://react-favicon.com/) - Generate Favicons for your web site using React and JSX using any font and icon library.
  * [svgrepo.com](https://www.svgrepo.com/) - Explore, search and find the best fitting icons or vectors for your projects using wide variety vector library. Download free SVG Vectors for commercial use.


## Design Inspiration

  * [awwwards.](https://www.awwwards.com/) - [Top websites] A showcases of all the best designed websites (voted on by designers).
  * [Behance](https://www.behance.net/)  - [设计展示]设计师展示作品的地方. 可使用 UI/UX 项目的类别进行过滤.
  * [dribbble](https://dribbble.com/) - [Design showcase] Unique design inspiration, generally not from real applications.
  * [Mobbin](https://mobbin.design/) - [Mobile screenshots] Save hours of UI & UX research with our library of 50,000+ fully searchable mobile app screenshots.
  * [Mobile Patterns](https://www.mobile-patterns.com/) - [手机截图] 一个设计灵感库，包含最好的 UI UX 模式（iOS 和 Android），供设计师、开发人员和产品制造商参考.
  * [Screenlane](https://screenlane.com/)  - [手机截屏] 获取灵感并紧跟最新的网络和移动应用程序 UI 设计趋势. 可按模式和应用过滤.
  * [scrnshts](https://scrnshts.club/) - [手机截图] 精选的最好的应用商店设计截图集合.
  * [UI Garage](https://uigarage.net/) - [Mobile and web screenshots] Daily UI inspiration & patterns for designers, developers to find inspiration, tools and the best resources for your project.


## Data Visualization on Maps

   * [IP Geolocation](https://ipgeolocation.io/) — 每月有 30K 请求提供免费的 DEVELOPER 计划.
   * [carto.com](https://carto.com/) — 根据您的数据和公共数据创建地图和地理空间 API.
   * [developers.arcgis.com](https://developers.arcgis.com)  — 用于跨网络、桌面和移动设备的地图、地理空间数据存储、分析、地理编码、路由等的 API 和 SDK.  2,000,000 个免费底图切片，20,000 个非存储地理编码，20,000 条简单路线，5,000 次行驶时间计算，每月 5GB 免费切片+数据存储.
   * [Foursquare](https://developer.foursquare.com/) - Location discovery, venue search, and context-aware content from Places API and Pilgrim SDK.
   * [geoapify.com](https://www.geoapify.com/)  - 矢量和栅格地图切片、地理编码、地点、路线、等值线 API. 每天 3000 个免费请求.
   * [geocod.io](https://www.geocod.io/) — Geocoding via API or CSV Upload. 2,500 free queries/day.
   * [geocodify.com](https://geocodify.com/) — Geocoding and Geoparsing via API or CSV Upload. 10k free queries/month.
   * [giscloud.com](https://www.giscloud.com/) — Visualize, analyze and share geo data online.
   * [gogeo.io](https://gogeo.io/) — Maps and geospatial services with an easy to use API and support for big data.
   * [graphhopper.com](https://www.graphhopper.com/) 为开发人员提供了一个免费包，用于路由、路线优化、距离矩阵、地理编码、地图匹配.
   * [here](https://developer.here.com/)  — 用于地图和位置感知应用的 API 和 SDK.  250k 交易/月免费.
   * [mapbox.com](https://www.mapbox.com/) — Maps, geospatial services and SDKs for displaying map data.
   * [maptiler.com](https://www.maptiler.com/cloud/)  — 用于地图可视化的矢量地图、地图服务和 SDK. 具有每周更新和四种地图样式的免费矢量瓷砖.
   * [opencagedata.com](https://opencagedata.com)  — 聚合 OpenStreetMap 和其他开放地理资源的地理编码 API. 每天 2,500 次免费查询.
   * [osmnames](https://osmnames.org/) — Geocoding, search results ranked by the popularity of related Wikipedia page.
   * [positionstack](https://positionstack.com/)  - 全球地点和坐标的免费地理编码. 每月 25.000 个供个人使用的请求.
   * [stadiamaps.com](https://stadiamaps.com/)  — 地图图块、路线、导航和其他地理空间 API. 每天 2,500 次免费地图视图和 API 请求，用于非商业用途和测试.
   * [maps.stamen.com](http://maps.stamen.com/) - Free map tiles and tile hosting.
   * [GeocodeAPI](https://geocodeapi.io) - Geocode API: Address to Coordinate Conversion & Geoparsing based on Pelias. Batch geocoding via CSV. 350000 free requests/month.
   * [Geokeo api](https://geokeo.com) - Geocoding api with language correction and more. Worldwide coverage. 2,500 free daily queries


## Package Build System

   * [build.opensuse.org](https://build.opensuse.org/) — Package build service for multiple distros (SUSE, EL, Fedora, Debian etc).
   * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — Fedora 和 EL 的基于 Mock 的 RPM 构建服务.
   * [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu 和 Debian 构建服务.


## IDE and Code Editing

   * [3v4l](https://3v4l.org/) - Free online PHP shell and snippet sharing site, runs your code in 300+ PHP versions
   * [Android Studio](https://d.android.com/studio)  — Android Studio 为在各种类型的 Android 设备上构建应用程序提供了最快的工具. 开源 IDE，对所有人免费，是开发 Android 应用程序的最佳选择. 适用于 Windows、Mac、Linux 甚至 ChromeOS！
   * [Apache Netbeans](https://netbeans.apache.org/) — Development Environment, Tooling Platform and Application Framework.
   * [apiary.io](https://apiary.io/) — 具有即时 API 模拟和生成文档的协作设计 API（无限的 API 蓝图和无限的用户免费提供一个管理员帐户和托管文档）.
   * [Atom](https://atom.io/) - Atom is a hackable text editor built on Electron.
   * [Binder](https://mybinder.org/) - Turn a Git repo into a collection of interactive notebooks. It is a free, public service.
   * [BlueJ](https://bluej.org)  — 专为初学者设计的免费 Java 开发环境，全球数百万人使用. 由 Oracle 和简单的 GUI 提供支持，以帮助初学者.
   * [Bootify.io](https://bootify.io/) - 具有自定义数据库和 REST API 的 Spring Boot 应用程序生成器.
   * [cacher.io](https://www.cacher.io) — Code snippet organizer with labels and support for 100+ programming languages.
   * [Code::Blocks](https://codeblocks.org)  — 免费的 Fortran 和 C/C++ IDE. 开源并在 Windows、macOS 和 Linux 上运行.
   * [codiga.io](https://codiga.io/)  — 编码助手，可让您直接在 IDE 中搜索、定义和重用代码片段. 个人和小型组织免费.
   * [codesnip.com.br](https://codesnip.com.br)  — 带有类别、搜索和标签的简单代码片段管理器. 免费且无限制.
   * [cocalc.com](https://cocalc.com/) — (formerly SageMathCloud at cloud.sagemath.com) — Collaborative calculation in the cloud. Browser access to full Ubuntu with built-in collaboration and lots of free software for mathematics, science, data science, preinstalled: Python, LaTeX, Jupyter Notebooks, SageMath, scikitlearn, etc.
   * [ide.cs50.io](https://ide.cs50.io/) - A free IDE powered by AWS Cloud9 by Harvard University.
   * [codepen.io](https://codepen.io/) — CodePen 是 Web 前端的游乐场.
   * [codesandbox.io](https://codesandbox.io/) — React、Vue、Angular、Preact 等的在线游乐场.
   * [Components.studio](https://webcomponents.dev/) - Code components in isolation, visualize them in stories, test them and publish them on npm.
   * [Eclipse Che](https://www.eclipse.org/che/) - Web based and Kubernetes-Native IDE for Developer Teams with multi-language support. Open Source and community driven. A online instance hosted by Red Hat is available at [workspaces.openshift.com](https://workspaces.openshift.com/).
   * [fakejson.com](https://fakejson.com/) — FakeJSON helps you quickly generate fake data using its API. Make an API request describing what you want and how you want it. The API returns it all in JSON. Speed up the go to market process for ideas and fake it till you make it.
   * [gitpod.io](https://www.gitpod.io)  — 用于 GitHub 项目的即时、可编写代码的开发环境. 开源免费.
   * [ide.goorm.io](https://ide.goorm.io)  goormIDE 是完整的云端 IDE. 多语言支持、基于 linux 的容器（通过功能齐全的基于 Web 的终端）、端口转发、自定义 url、实时协作和聊天、共享链接、Git/Subversion 支持. 还有更多功能（免费层包括每个容器 1GB RAM 和 10GB 存储，5 个容器插槽）.
   * [JDoodle](https://www.jdoodle.com) — Online compiler and editor for more than 60 programming languages with a free plan for REST API code compiling up to 200 credits per day.
   * [jetbrains.com](https://jetbrains.com/products.html) — Productivity tools, IDEs and deploy tools (aka [IntelliJ IDEA](https://www.jetbrains.com/idea/), [PyCharm](https://www.jetbrains.com/pycharm/), etc). Free license for students, teachers, Open Source and user groups.
   * [jsbin.com](https://jsbin.com) — JS Bin 是另一个前端 Web（HTML、CSS 和 JavaScript.也支持 Markdown、Jade 和 Sass）的游乐场和代码共享站点.
   * [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle 是前端 web 的游乐场和代码共享站点，也支持协作.
   * [JSONPlaceholder](http://jsonplaceholder.typicode.com/) Some REST API endpoints that return some fake data in JSON format. The source code is also available if you would like to run the server locally.
   * [Katacoda](https://katacoda.com) — Interactive learning and training platform for software engineers helping developers learn and companies increase adoption.
   * [Lazarus](https://www.lazarus-ide.org/) — Lazarus is a Delphi compatible cross-platform IDE for Rapid Application Development.
   * [micro-jaymock](https://micro-jaymock.now.sh/) - Tiny API mocking microservice for generating fake JSON data.
   * [mockable.io](https://www.mockable.io/)  — Mockable 是一个简单的可配置服务，用于模拟 RESTful API 或 SOAP Web 服务. 此在线服务允许您快速定义 REST API 或 SOAP 端点并让它们返回 JSON 或 XML 数据.
   * [mockaroo](https://mockaroo.com/) — Mockaroo lets you generate realistic test data in CSV, JSON, SQL, and Excel formats. You can also create mocks for back-end API.
   * [Mocklets](https://mocklets.com) - a HTTP-based mock API simulator, which helps simulate APIs for faster parallel development and more comprehensive testing, with lifetime free tier.
   * [Paiza](https://paiza.cloud/en/)  — 在浏览器中开发 Web 应用程序，无需进行任何设置. 免费计划提供 1 台服务器，其使用寿命为 24 小时，每天运行时间为 4 小时，配备 2 个 CPU 内核、2 GB RAM 和 1 GB 存储空间.
   * [Prepros](https://prepros.io/)  - Prepros 可以开箱即用地编译 Sass、Less、Stylus、Pug/Jade、Haml、Slim、CoffeeScript 和 TypeScript，重新加载您的浏览器并使开发和测试您的网站变得非常容易，因此您可以专注于使它们变得完美. 只需单击几下，您也可以添加自己的工具.
   * [Replit](https://replit.com/) — 适用于各种程序语言的云编码环境.
   * [SoloLearn](https://code.sololearn.com)  — 一个非常适合运行代码片段的云编程游乐场. 支持各种编程语言. 运行代码不需要注册，但当您需要在他们的平台上保存代码时需要. 还为初学者和中级编码人员提供免费课程.
   * [stackblitz.com](https://stackblitz.com/) — Online/Cloud Code IDE to create, edit, & deploy fullstack apps. Support any popular NodeJs based frontend & backend frameworks. Shortlink to create new project: [https://node.new](https://node.new).
   * [Visual Studio Code](https://code.visualstudio.com/) - Code editor redefined and optimized for building and debugging modern web and cloud applications. Developed by Microsoft for Windows, macOS and Linux.
   * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — Fully-featured IDE with thousands of extensions, cross-platform app development (Microsoft extensions available for download for iOS and Android), desktop, web and cloud development, multi-language support (C#, C++, JavaScript, Python, PHP and more).
   * [VSCodium](https://vscodium.com/) - Community-driven, without telemetry/tracking, and freely-licensed binary distribution of Microsoft’s editor VSCode
   * [wakatime.com](https://wakatime.com/) — 关于您的编码活动的量化自我指标，使用文本编辑器插件，免费的有限计划.
   * [WebComponents.dev](https://webcomponents.dev/) — 浏览器内的 IDE 可独立地编写 Web 组件，提供 58 个模板，支持故事和测试。


## Analytics, Events and Statistics

   * [Statvoo Analytics](https://analytics.statvoo.com/) — 为您的所有网站提供永久免费的客户分析，每月无限次活动
   * [Avo](https://avo.app/)  — 简化的分析发布工作流程. 单一真实来源跟踪计划、类型安全分析跟踪库、应用内调试器、数据可观察性，以便在发布之前捕获所有数据问题.  2 个工作区成员和 1 小时数据可观察性回溯免费.
   * [Branch](https://branch.io) — Mobile Analytics Platform. Free Tier offers upto 10K Mobile App Users with deep-linking & other services.
   * [Clicky](https://clicky.com) — Website Analytics Platform. Free Plan for 1 website with 3000 views analytics.
   * [Databox](https://databox.com) — Business Insights & Analytics by combining other analytics & BI platforms. Free Plan offers 3 users, dashboards & data sources. 11M historical data records.
   * [indicative.com](https://indicative.com/) — Customer analytics platform to optimize customer engagement, increase conversion, and improve retention. Free up to 50M events/month.
   * [Panelbear.com](https://panelbear.com/) — 极快且私密的免费套餐，包括每月 5,000 次网页浏览量，可用于无限网站
   * [Hitsteps.com](https://hitsteps.com/) — 1 个网站每月 2,000 次浏览量
   * [amplitude.com](https://amplitude.com/) — 每月 100 万个事件，最多 2 个应用程序
   * [Flagsmith](https://www.molasses.app)  - 自信地发布功能； 跨 Web、移动和服务器端应用程序管理功能标志. 使用我们的托管 API，部署到您自己的私有云，或在本地运行
   * [GoatCounter](https://www.goatcounter.com/)  — GoatCounter 是一个开源网络分析平台，可作为托管服务（非商业用途免费）或自托管应用程序提供. 它旨在提供易于使用且有意义的隐私友好型网络分析，以替代 Google Analytics 或 Matomo. 免费套餐用于非商业用途，包括无限数量的网站、6 个月的数据保留期和 10 万次/月的网页浏览量.
   * [Google Analytics](https://analytics.google.com/) — Google Analytics
   * [Expensify](https://www.expensify.com/) — 费用报告，免费的个人报告审批流程
   * [getinsights.io](https://getinsights.io) - 以隐私为重点的无 cookie 分析，每月最多可免费处理 5k 个事件.
   * [heap.io](https://heap.io) — Automatically captures every user action in iOS or web apps. Free for up to 5,000 visits/month
   * [Hotjar](https://hotjar.com) — Website Analytics and Reports . Free Plan allows 2000 pageviews/day. 100 snapshots/day (max capacity: 300). 3 snapshot heatmaps which can be stored for 365 days. Unlimited Team Members.
   * [Keen](https://keen.io/)  — 用于数据收集、分析和可视化的自定义分析.  50,000 个事件/月免费
   * [Yandex.Metrica](https://metrica.yandex.com/) — 无限制的免费分析
   * [Mixpanel](https://mixpanel.com/) — 100,000 月度跟踪用户、无限数据历史记录和席位、美国或欧盟数据驻留
   * [Moesif](https://www.moesif.com)  — REST 和 GraphQL 的 API 分析.  （每月最多免费调用 500,000 次 API 调用）
   * [Molasses](https://www.molasses.app)  - 强大的功能标志和 A/B 测试. 最多释放 3 个环境，每个环境有 5 个功能标志.
   * [optimizely.com](https://www.optimizely.com) — A/B Testing solution, free starter plan, 1 website, 1 iOS and 1 Android app
   * [Microsoft PowerBI](https://powerbi.com) — Business Insights & Analytics by Microsoft. Free Plan offers limited use with 1 Million User licenses.
   * [quantcast.com](https://www.quantcast.com/products/measure-audience-insights/) — 无限制的免费分析
   * [sematext.com](https://sematext.com/cloud/) — Free for up to 50 K actions/month, 1-day data retention, unlimited dashboards, users, etc.
   * [Similar Web](https://similarweb.com) — Analytics for Web & Mobile Apps. Free Plan offers 5 results per metric, 1 month of mobile app data & 3 months of website data.
   * [StatCounter](https://statcounter.com/)  — 网站查看者分析. 用于分析 500 位最近访问者的免费计划.
   * [Tableau Developer Program](https://www.tableau.com/developer)  — 创新、创建并让 Tableau 完美地为您的组织工作. 免费的开发人员计划为 Tableau Online 提供了个人开发沙盒许可证. 该版本是最新的预发布版本，因此数据开发人员可以测试这个一流平台的每一个功能.
   * [usabilityhub.com](https://usabilityhub.com/) — Test designs and mockups on real people, track visitors. Free for one user, unlimited tests
   * [woopra.com](https://www.woopra.com/) — Free user analytics platform for 500K actions, 90 day data retention, 30+ one click integration.
   * [counter.dev](https://counter.dev) — Web analytics made simple and therefore privacy friendly. Free or pay what you want by donation.
   * [PostHog](https://posthog.com) - Full Product Analytics suite free for up to 1m tracked events per month


## Visitor Session Recording

   * [Visualime.com](https://www.visualime.com/) — Free and unlimited session recordings, no traffic limits
   * [Reactflow.com](https://www.reactflow.com/) — 每个站点：每天 1,000 个页面浏览量、3 个热图、3 个小部件、免费的错误跟踪
   * [LogRocket.com](https://www.logrocket.com) - 1,000 sessions/month with 30 day retention, error tracking, live mode
   * [FullStory.com](https://www.fullstory.com) — 1,000 sessions/month with 1 month data retention and 3 user seats. More information [here](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition).
   * [hotjar.com](https://www.hotjar.com/) — Per site: 2,000 pages views/day, 3 heatmaps, data stored for 3 months,...
   * [inspectlet.com](https://www.inspectlet.com/) — 2,500 sessions/month free for 1 website
   * [livesession.io](https://livesession.io/) — 5,000 sessions/month free for 1 website
   * [Microsoft Clarity](https://clarity.microsoft.com/) - 会话录制完全免费，“无流量限制”、无项目限制、无采样
   * [mouseflow.com](https://mouseflow.com/) — 500 sessions/month free for 1 website
   * [mousestats.com](https://www.mousestats.com/) — 1 个网站每月免费 100 次会话
   * [smartlook.com](https://www.smartlook.com/) — Web 和移动应用程序的免费包（1500 个会话/月）、3 个热图、1 个漏斗、1 个月的数据历史记录
   * [usersurge.com](https://www.usersurge.com/) — 个人每月 25 万次会话.
   * [howuku.com](https://howuku.com) — Track user interaction, engagement, and event. Free for up to 5,000 visits/month
   * [UXtweak.com](https://www.uxtweak.com/)  — 记录并观察访问者如何使用您的网站或应用程序. 小项目的免费无限时间


## International Mobile Number Verification API and SDK

  * [Cognalys](https://cognalys.com/)  — 通过一种创新且可靠的方法验证免费增值手机号码，而不是使用 SMS 网关. 每天免费 10 次尝试和 15 次验证
  * [numverify](https://numverify.com/) — Global phone number validation and lookup JSON API. 250 API requests/month
  * [veriphone](https://veriphone.io/) — Global phone number verification in a free, fast, reliable JSON API. 1000 requests/month


## Payment and Billing Integration

  * [CurrencyFreaks](https://currencyfreaks.com/)  — 提供当前和历史货币汇率. 免费的 DEVELOPER 计划可用于每月 1000 个请求.
  * [CurrencyApi](https://currencyapi.net/) — Live Currency Rates for Physical and Crypto currencies, delivered in JSON and XML. Free tier offers 1,250 API requests/month.
  * [currencylayer](https://currencylayer.com/) — 为您的业务提供可靠的汇率和货币转换，每月免费 1,000 个 API 请求
  * [currencystack.io](https://currencystack.io/) — Production-ready real-time exchange rates for 154 currencies.
  * [exchangerate-api.com](https://www.exchangerate-api.com)  - 一个易于使用的货币转换 JSON API. 免费套餐，没有请求限制.
  * [FraudLabsPRO](https://www.fraudlabspro.com) — Help merchants to prevent payment fraud and chargebacks. Free Micro Plan available with 500 queries/month.
  * [MailPopin](https://mailpop.in) - Get the most of your Stripe notifications with contextualized information.
  * [Nami ML](https://www.namiml.com/)  - 适用于 iOS 和 Android 上的应用内购买和订阅的完整平台，包括无代码付费墙、CRM 和分析. 免费提供所有基本功能以运行 IAP 业务.
  * [RevenueCat](https://www.revenuecat.com/) — Hosted backend for in-app purchases and subscriptions (iOS and Android). Free up to $10k/mo in tracked revenue.
  * [vatlayer](https://vatlayer.com/) — Instant VAT number validation and EU VAT rates API, free 100 API requests/month
  * [Freecurrencyapi.net](https://freecurrencyapi.net/)  — 免费的货币换算和汇率数据API.  10 个请求/小时，没有 API 密钥，当您免费注册时，每月 50 000 个请求.


## Docker Related

  * [canister.io](https://canister.io/) — 20 free private repositories for developers, 30 free private repositories for teams to build and store Docker images
  * [Container Registry Service](https://container-registry.com/)  - 基于港口的集装箱管理解决方案. 免费套餐为私有存储库提供 1 GB 存储空间.
  * [Docker Hub](https://hub.docker.com) — One free private repository and unlimited public repositories to build and store Docker images
  * [Play with Docker](https://labs.play-with-docker.com/) — 一个简单、互动且有趣的 Docker 学习平台.
  * [quay.io](https://quay.io/) — Build and store container images with unlimited free public repositories
  * [TreeScale.com](https://treescale.com/) — Host and manage container images with group permissions. Free tier offers 1 GB storage for private repositories.
  * [Platform9](https://platform9.com/) - Managed Kubernetes plane. Free plan offers management capabilities up to 3 clusters & 20 nodes. Note: you must provide cluster infrastructure by yourself.


## Vagrant Related

  * [Vagrant Cloud](https://app.vagrantup.com)  - HashiCorp 流浪云. 流浪盒托管.
  * [Vagrantbox.es](https://www.vagrantbox.es/) — An alternative public box index


## Dev Blogging Sites

  * [BearBlog](https://bearblog.dev/) - 极简主义和 Markdown 驱动的博客和网站构建器.
  * [Dev.to](https://dev.to/) - 程序员分享想法并互相帮助成长的地方.
  * [Hashnode](https://hashnode.com/) — Hassle-free Blogging Software for Developers!.
  * [Medium](https://medium.com/) — 更聪明地了解对您而言重要的事情.


## Commenting Platforms
  * [Staticman](https://staticman.net/) - Staticman is a Node.js application that receives user-generated content and uploads it as data files to a GitHub and/or GitLab repository, using Pull Requests.
  * [GraphComment](https://graphcomment.com/) - GraphComment 是一个评论平台，可帮助您从网站的受众中建立一个活跃的社区.
  * [Utterances](https://utteranc.es/) - A lightweight comments widget built on GitHub issues. Use GitHub issues for blog comments, wiki pages and more!
  * [Disqus](https://disqus.com/) - Disqus 是一个网络社区平台，被网络上成千上万的网站使用.


## Screenshot APIs

  * [24browser.com](https://www.24browser.com) – Capture beautifully rendered website screenshots at scale with powerful API.
  * [ApiFlash](https://apiflash.com) — A screenshot API based on Aws Lambda and Chrome. Handles full page, capture timing, viewport dimensions, ...
  * [microlink.io](https://microlink.io/) – It turns any website into data such as metatags normalization, beauty link previews, scraping capabilities or screenshots as a service. 250 reqs/day every day free.
  * [ScreenshotAPI.net](https://screenshotapi.net/)  - 截图 API 使用一个简单的 API 调用来生成任何网站的截图. 构建以扩展并托管在 Google Cloud 上. 每月提供 100 个免费截图.
  * [screenshotlayer.com](https://screenshotlayer.com/) — Capture highly customizable snapshots of any website. Free 100 snapshots/month
  * [screenshotmachine.com](https://www.screenshotmachine.com/) — Capture 100 snapshots/month, png, gif and jpg, including full-length captures, not only home page
  * [PhantomJsCloud](https://PhantomJsCloud.com) — Browser automation and page rendering.  Free Tier offers up to 500 pages/day.  Free Tier since 2017.
  * [Webshrinker.com](https://webshrinker.com) — Web Shrinker provides web site screenshot and domain intelligence API services. Free 100 requests/month.


## Browser based hardware emulation written in Javascript

  * [JsLinux](https://bellard.org/jslinux) — 一个真正快速的 x86 虚拟机，能够运行 Linux 和 Windows 2k.
  * [Jor1k](http://s-macke.github.io/jor1k/demos/main.html) — 一个能够在网络支持下运行 Linux 的 OpenRISC 虚拟机.
  * [v86](https://copy.sh/v86) — 能够在浏览器中直接运行 Linux 和其他操作系统的 x86 虚拟机.


## Privacy Management
  * [Bearer](https://www.bearer.sh/)  - 通过审计和持续的工作流程帮助通过设计实现隐私，以便组织遵守 GDPR 和其他法规. 免费套餐仅限于较小的团队和 SaaS 版本.
  * [Osano](https://www.osano.com/) - Consent management and compliance platform with everything from GDPR representation to cookie banners. Free tier offers basic features.
  * [Iubenda](https://www.iubenda.com/) - Privacy and cookie policies along with consent management. Free tier offers limited privacy and cookie policy as well as cookie banners.
  * [Cookiefirst](https://cookiefirst.com/)  - Cookie 横幅、审核和多语言同意管理解决方案. 免费套餐提供一次性扫描和单个横幅.
  * [Ketch](https://www.ketch.com/) - Consent management and privacy framework tool. Free tier offers most features with a limited visitor count.


## Miscellaneous

  * [Smartcar API](https://smartcar.com) - An API for cars to locate, get fuel tank, battery levels, odometer, unlock/lock doors, etc.
  * [Blynk](https://blynk.io) — A SaaS with API to control, build & evaluate IoT devices. Free Developer Plan with 5 devices,Free Cloud & data storage. Mobile Apps also available.
  * [Bricks Note Calculator](https://free.getbricks.app/) - 带有强大的内置多行计算器的笔记应用程序 (PWA).
  * [Carbon.now.sh](https://carbon.now.sh) - create and share code snippet in an aesthetic screenshot-like image format. Usually used to aesthetically share/show-off code snippet on Twitter or blog posts.
  * [Code Time](https://www.software.com/code-time) - VS Code、Atom、IntelliJ、Sublime Text 等中时间跟踪和编码指标的扩展.
  * [Codepng](https://www.codepng.app) - Create awesome snapshots from your source code that you can share on social media.
  * [ConfigCat](https://configcat.com) - Cross-platform feature flag service. SDKs for all major languages. Free plan up to 10 flags, 2 environments, 1 product and 5 Million requests per month. Unlimited user seats. Students get 100 flags and 100 Million requests per month for free.
  * [datelist.io](https://datelist.io)  - 在线预约/预约调度系统. 每月最多可免费预订 5 次，包括 1 个日历
  * [docsapp.io](https://www.docsapp.io/) — Easiest way to publish documentation, free for Open Source
  * [Elementor](https://elementor.com)  — WordPress 网站建设者. 免费计划提供 40 多个基本小部件.
  * [Form2Channel](https://form2channel.com)  — 在您的网站上放置一个静态 html 表单，并直接接收提交到 Google 表格、电子邮件、Slack、Telegram 或 Http 的内容. 无需编码.
  * [FOSSA](https://fossa.com/) - 对第三方代码、许可证合规性和漏洞进行可扩展的端到端管理.
  * [fullcontact.com](https://www.fullcontact.com/developer/pricing/) — Help your users know more about their contacts by adding social profile into your app. 500 free Person API matches/month
  * [http2.pro](https://http2.pro) — HTTP/2 协议就绪测试和客户端 HTTP/2 支持检测 API.
  * [JWT Decoder](https://jwt.ssotools.com/) — 用于解码 JWT（JSON Web 令牌）并验证其签名的在线免费工具.
  * [Base64 decoder/encoder](https://devpal.co/base64-decode/) — 用于解码和编码数据的在线免费工具.
  * [newreleases.io](https://newreleases.io/) - Receive notifications on email, Slack, Telegram, Discord and custom webhooks for new releases from GitHub, GitLab, Bitbucket, Python PyPI, Java Maven, Node.js NPM, Node.js Yarn, Ruby Gems, PHP Packagist, .NET NuGet, Rust Cargo and Docker Hub.
  * [PDFMonkey](https://www.pdfmonkey.io/) — Manage PDF templates in a dashboard, call the API with dynamic data, download your PDF. Offers 1000 free documents per month.
  * [QuickType.io](https://quicktype.io/)  - 从 JSON、模式和 GraphQL 快速自动生成模型/类/类型/接口和序列化程序，以便以任何编程语言快速安全地处理数据. 将 JSON 转换为任何语言的华丽、类型安全的代码.
  * [ray.so](https://ray.so/) - Create beautiful images of your code snippets.
  * [readme.com](https://readme.com/) — 美丽的文档让开源变得简单，免费.
  * [redirection.io](https://redirection.io/) — 用于管理企业、营销和 SEO 的 HTTP 重定向的 SaaS 工具.
  * [redirect.pizza](https://redirect.pizza/) - Easily manage redirects with HTTPS support. Free plan includes 10 sources and 100.000 hits per month.
  * [ReqBin](https://www.reqbin.com/) — Post HTTP Requests Online. Popular Request Methods include GET, POST, PUT, DELETE, and HEAD. Supports Headers and Token Authentication. Includes a basic login system for saving your requests.
  * [superfeedr.com](https://superfeedr.com/)  — 实时 PubSubHubbub 兼容的订阅源、导出、分析. 免费，定制更少
  * [SurveyMonkey.com](https://www.surveymonkey.com) — Create online surveys. Analyze the results online.  Free plan allows only 10 questions and 100 responses per survey.
  * [videoinu](https://videoinu.com) — 在线创建和编辑屏幕录像和其他视频.
  * [RandomKeygen](https://randomkeygen.com/) - 免费的移动友好工具提供各种随机生成的密钥和密码，可用于保护任何应用程序、服务或设备的安全.
  * [Cronhooks](https://cronhooks.io/) - Replace your cron jobs with webhooks. Invoke any webhook at a given date time or repeatedly using cron expressions. Free plan allows 1 webhook schedule.
  * [Hook Relay](https://www.hookrelay.dev/) - Add webhook support to your app without the hassles: done-for-you queueing, retries with backoff, and logging. The free plan has 100 deliveries per day, 14-day retention, and 3 hook endpoints.
  * [Format Express](https://www.format-express.dev) - Instant online formatter for JSON / XML / SQL.


## Remote Desktop Tools

  * [Getscreen.me](https://getscreen.me) — 2 台设备免费，会话数量和持续时间没有限制
  * [Apache Guacamole™](https://guacamole.apache.org/) — 开源无客户端远程桌面网关


## Other Free Resources

  * [get.localhost.direct](https://get.localhost.direct) — 更好的 *.localhost.direct 通配符公共 CA 签名 SSL 证书，用于 localhost 开发，支持子域  
  * [eu.org](https://nic.eu.org)  — 免费 eu.org 域. 请求通常在 14 天内获得批准.
  * [js.org](https://js.org) - Free js.org subdomains for GitHub Pages for the JavaScript community.
  * [pp.ua](https://nic.ua/) — 免费 pp.ua 子域.
  * [Framacloud](https://degooglisons-internet.org/en/list/) — 法国非营利组织的免费/自由开源软件和 SaaS 列表 [Framasoft](https://framasoft.org/en/).
  * [getawesomeness](https://getawesomeness.herokuapp.com) — Retrieve all amazing awesomeness from GitHub... a must see
  * [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) — A hub of free and Open Source software for developers.
  * [GitHub Education](https://education.github.com/pack)  — 为学生收集免费服务. 需要注册.
  * [is-a.dev](https://www.is-a.dev/) — 为开发人员提供免费的 `*.is-a.dev` 子域.
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program) — Get a free sandbox, tools, and other resources you need to build solutions for the Microsoft 365 platform. The subscription is a 90-day [Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5) (Windows excluded) which is renewable. It is renewed if you're active in development(measured using telemetry data & algorithms).
  * [RedHat for Developers](https://developers.redhat.com)  — 专为开发人员免费访问红帽产品，包括 RHEL、OpenShift、CodeReady 等. 仅限个人计划. 还提供免费电子书以供参考.
  * [smsreceivefree.com](https://smsreceivefree.com/) — 提供免费的临时和一次性电话号码.
  * [simplebackups.io](https://simplebackups.io/) — Backup automation service for servers and databases (MySQL, PostgreSQL, MongoDB) stored directly into cloud storage providers (AWS, DigitalOcean, Backblaze...). Provides free plan for 1 backup.
  * [SnapShooter](https://snapshooter.com/) — Backup solution for DigitalOcean, AWS, LightSail, Hetzner and Exoscale, with support for direct database, file system and application backups to s3 based storage. Provides a free plan with daily backups for one resource.
  * [thedev.id](https://thedev.id) — A free thedev.id subdomain for developers.
  * [Themeselection](https://themeselection.com/) — 精选高品质、现代设计、专业且易于使用的免费管理仪表板模板，
HTML 主题和 UI 工具包可以更快地创建您的应用程序！
  * [Web.Dev](https://web.dev/measure/) — 这是一个免费工具，可让您查看网站的性能并改善 SEO 以在搜索引擎中获得更高的排名列表.
  * [SmallDev.tools](https://smalldev.tools/) — A free tool for developers that allows you to Encode/Decode various formats, Minify HTML/CSS/Javascript, Beautify, Generate Fake/Testing real like dataset in JSON/CSV & multiple other formats and many more features. With a delightful interface.
