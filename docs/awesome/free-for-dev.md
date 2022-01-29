<div class="github-widget" data-repo="ripienaar/free-for-dev"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## free-for.dev

Developers and Open Source authors now have a massive amount of services offering free tiers, but it can be hard to find them all to make informed decisions.

这是为开发人员提供免费套餐的软件（SaaS、PaaS、IaaS 等）和其他产品的列表.

The scope of this particular list is limited to things that infrastructure developers (System Administrator, DevOps Practitioners, etc.) are likely to find useful. We love all the free services out there, but it would be good to keep it on topic. It's a bit of a grey line at times so this is a bit opinionated; do not be offended if I do not accept your contribution.

This list is the result of Pull Requests, reviews, ideas and work done by 1000+ people. You too can help by sending [Pull Requests](https://github.com/ripienaar/free-for-dev) 添加更多服务或删除其产品已更改或已停用的服务.

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

 *注意：* 此列表仅适用于即服务产品，不适用于自托管软件. 要使一项服务符合条件，它必须提供免费套餐，而不仅仅是免费试用. 如果免费套餐有时间限制，则必须至少为一年. 我们还从安全角度考虑免费层，因此 SSO 很好，但我不会接受将 TLS 限制为仅付费层的服务.

Table of Contents
=================


## Major Cloud Providers

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 每天 28 个前端实例小时，每天 9 个后端实例小时
    * Cloud Firestore - 1GB 存储，50,000 次读取，20,000 次写入，每天 20,000 次删除
    * Compute Engine - 1 个不可抢占式 e2-micro、30GB 硬盘、5GB 快照存储（仅限某些地区）、每月从北美到所有地区目的地（不包括中国和澳大利亚）的 1GB 网络出口
    * 云存储 - 5GB、1GB 网络出口
     * Cloud Shell - 具有 5GB 持久存储的基于 Web 的 Linux shell/基本 IDE. 每周 60 小时限制
    * Cloud Pub/Sub - 10GB of messages per month
    * Cloud Functions - 每月 200 万次调用（包括后台和 HTTP 调用）
    * Cloud Run - 2 million requests per month, 360,000 GB-seconds memory, 180,000 vCPU-seconds of compute time, 1 GB network egress from North America per month
    * Google Kubernetes Engine - No cluster management fee for one zonal cluster. Each user node is charged at standard Compute Engine pricing
    * BigQuery - 1 TB of querying per month, 10 GB of storage each month
    * Cloud Build - 120 build-minutes per day
    * Cloud Source Repositories - Up to 5 Users, 50 GB Storage, 50 GB Egress
    * 完整的详细列表 - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * Amazon CloudFront - 每月 1TB 出口
    * Amazon DynamoDB - 25GB NoSQL DB
    * Amazon EC2 - 100GB aggregated egress per month
    * Amazon EC2 - t2.micro 或 t3.micro 每月 750 小时
    * Amazon EBS - 30GB per month of General Purpose (SSD) or Magnetic
    * Amazon ELB - 750 hours per month
    * Amazon Lambda - 每月 100 万次请求
    * Amazon SNS - 1 million publishes per month
    * Amazon SES - 每月 62,000 条消息
    * Amazon Cloudwatch - 10 个自定义指标和 10 个警报
    * Amazon Glacier - 10GB long-term object storage
    * Amazon SQS - 1 million messaging queue requests
    * Amazon CodeBuild - 100min of build time per month
    * Amazon CodeCommit - 5 active users per month
    * Amazon CodePipeline - 1 active pipeline per month
    * Full, detailed list - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1 个 B1S Linux 虚拟机，1 个 B1S Windows 虚拟机
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 个网络、移动或 API 应用程序
    * [Functions](https://azure.microsoft.com/services/functions/) - 每月 100 万次请求
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - 实现快速、简单和精益的开发测试环境
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 objects
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 50,000 monthly stored users
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 active users, unlimited private Git repos
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10 free parallel jobs with unlimited minutes for open source for Linux, macOS, and Windows
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 每天 8,000 条消息
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1 个免费的公共负载平衡 IP (VIP)
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 1 million push notifications
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 5GB egress per month
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 5GB storage and 400 RUs of provisioned throughput
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) — 使用免费 SSL、身份验证/授权和自定义域构建、部署和托管静态应用程序和无服务器功能
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS 文件或 Blob 存储
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML API（计算机视觉、翻译器、人脸检测、机器人......）免费层级，包括有限交易
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - AI-based search and indexation service, free for 10,000 documents
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - Managed Kubernetes service, free cluster management
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 100K 操作/月
    * Full, detailed list - [https://azure.microsoft.com/free/](https://azure.microsoft.com/free/)

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * 计算 - 2 个基于 x64，每个具有 1 GB RAM，4 个基于 Arm 的 Ampere A1 内核和 24 GB 内存，可用作一个 VM 或最多 4 个 VM
    * 块卷 - 4 个卷，总共 200 GB（用于计算）
    * Object Storage - 10 GB
    * Load balancer - 1 instance with 10 Mbps
    * Databases - 2 DBs, 20 GB each
    * Monitoring - 500 million ingestion datapoints, 1 billion retrieval datapoints
    * Bandwidth - 10 TB egress per month, speed limited to 50 Mbps on x64 based VM, 500 Mbps * core count on ARM based VM
    * 公共 IP - 2 个 IPv4 用于 VM，1 个 IPv4 用于负载平衡器
    * Notifications - 1 million delivery options per month, 1000 emails sent per month
    * 完整、详细的列表 - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloud Functions - 每月执行 500 万次
    * 对象存储 - 每月 25GB
    * Cloudant 数据库 - 1 GB 数据存储
    * Db2 数据库 - 100MB 数据存储
    * API Connect - 50,000 API calls per month
    * 可用性监控 - 每月 300 万个数据点
    * Log Analysis - 500MB of daily log
    * 完整的详细列表 - https://www.ibm.com/cloud/free/


## Cloud management solutions
  * [Brainboard](https://www.brainboard.co) - Collaborative solution to visually build and manage cloud infrastructures from end-to-end.
  * [terraform.io](https://www.terraform.io/)  — Terraform 云. 免费远程状态管理和团队协作，最多可容纳 5 个用户.


## Source Code Repos

  * [Bitbucket](https://bitbucket.org/) — 使用 Pipelines for CI/CD 为最多 5 个用户提供无限的公共和私有 Git 存储库
  * [chiselapp.com](http://chiselapp.com/) — Unlimited public and private Fossil repositories
  * [codebasehq.com](https://www.codebasehq.com/) — One free project with 100 MB space and 2 users
  * [Codeberg.org](https://codeberg.org/) - Unlimited public and private Git repos for free and open-source projects. Static website hosting with [Codeberg Pages](https://codeberg.page/).
  * [Gitea.com](https://www.gitea.com/) - Unlimited public and private Git repos
  * [GitGud](https://gitgud.io) — Unlimited private and public repositories. Free forever. Powered by GitLab & Sapphire. CI/CD not provided.
  * [GitHub](https://github.com/) — Unlimited public repositories and unlimited private repositories (with unlimited collaborators). Apart from this some other free services(there are much more but we list the main ones here) provided are :
       - [CI/CD](https://github.com/features/actions)(Free for Public Repos, 2000 min/month for private repos free)
       - [Static Website Hosting](https://pages.github.com) (Free for Public Repos)
       - [Package Hosting & Container Registry](https://github.com/features/packages) （公共存储库免费，500 MB 存储空间和 CI/CD 之外的 1GB 带宽免费用于私人存储库）
       - Project Management & Issue Tracking.
  * [gitlab.com](https://about.gitlab.com/)  — 无限的公共和私有 Git 存储库，拥有无限的协作者. 还提供以下功能：
       - [CI/CD](https://about.gitlab.com/product/continuous-integration) (Free for Public Repos, 400 mins/month for private repos)
       - Static Sites with [GitLab Pages](https://about.gitlab.com/product/pages).
       - Container Registry with 10 GB limit per repo.
       - Project Management & Issue Tracking.
  * [heptapod.net](https://foss.heptapod.net/) — Heptapod 是 GitLab 社区版的友好分支，为 Mercurial 提供支持
  * [ionicframework.com](https://ionicframework.com/appflow) - 使用 Ionic 开发应用程序的回购和工具，你也有一个离子回购
  * [NotABug](https://notabug.org) — NotABug.org is a free-software code collaboration platform for freely licensed projects, Git-based
  * [OSDN](https://osdn.net/) - OSDN.net 是为开源软件开发人员提供的免费服务，提供 SVN/Git/Mercurial/Bazaar/CVS 存储库等.
  * [Pagure.io](https://pagure.io) — Pagure.io is a free and open source software code collaboration platform for FOSS-licensed projects, Git-based
  * [perforce.com](https://www.perforce.com/products/helix-teamhub) — Free 1GB Cloud and  Git, Mercurial, or SVN repositories.
  * [pijul.com](https://pijul.com/)  - 无限免费和开源的分布式版本控制系统. 它的显着特点是建立在完善的补丁理论基础上，易于学习和使用，真正的分布式. 解决了 git/hg/svn/darcs 的很多问题.
  * [plasticscm.com](https://plasticscm.com/) — Free for individuals, OSS and nonprofit organizations
  * [projectlocker.com](https://projectlocker.com) — 一个 50 MB 空间的免费私人项目（Git 和 Subversion）
  * [RocketGit](https://rocketgit.com)  — 基于 Git 的存储库托管. 无限的公共和私人存储库.
  * [savannah.gnu.org](https://savannah.gnu.org/) - Serves as a collaborative software development management system for free Software projects (for GNU Projects)
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - Serves as a collaborative software development management system for free Software projects (for non-GNU projects)


## APIs, Data and ML

  * [IP.City](https://ip.city) — 100 free IP geolocation requests per day
  * [Abstract API](https://www.abstractapi.com) — 适用于各种用例的 API 套件，包括 IP 地理定位、性别检测甚至电子邮件验证.
  * [algorithmia.com](https://algorithmia.com/)  — 免费托管算法. 包括运行算法的免费每月津贴. 现在有了 CLI 支持.
  * [Apify](https://www.apify.com/) — Web scraping and automation platform to create an API for any website and extract data. Ready-made scrapers, integrated proxies, and custom solutions. Free plan with $5 platform credits included every month.
  * [API Mocha](https://apimocha.com) - Completely free online API mocking for testing and prototyping.  Make up to 500 requests per day, fully customizable API responses, download mock rules as a Postman collection.
  * [APITemplate.io](https://apitemplate.io)  - 使用简单的 API 或 Zapier 和 Airtable 等自动化工具自动生成图像和 PDF 文档. 不需要 CSS/HTML. 免费计划附带 50 张图片/月和 3 个模板.
  * [Atlas toolkit](https://atlastk.org/) - Lightweight library to develop single-page web applications that are instantly accessible. Available for Java, Node.js, Perl, Python and Ruby.
  * [Beeceptor](https://beeceptor.com)  - 在几秒钟内模拟一个休息 API，伪造 API 响应等等. 每天免费 50 个请求，公共仪表板，开放端点（任何拥有仪表板链接的人都可以查看请求和响应）.
  * [bigml.com](https://bigml.com/) — Hosted machine learning algorithms. Unlimited free tasks for development, limit of 16 MB data/task.
  * [Bruzu](https://bruzu.com/) — Automate Image production. Generate tons of Image variants with API, Integrations or nocode sheet. API is FREE with watermark.
  * [Calendarific](https://calendarific.com) - Enterprise-grade Public holiday API service for over 200 countries. Free plan includes 1000 calls per month.
  * [Clarifai](https://www.clarifai.com)  — 用于自定义人脸识别和检测的图像 API. 能够训练人工智能模型. 免费计划每月有 5000 个电话.
  * [Cloudmersive](https://cloudmersive.com/) — 实用 API 平台，可完全访问广泛的 API 库，包括文档转换、病毒扫描等，每月调用 800 次.
  * [Colaboratory](https://colab.research.google.com) — 带有 Nvidia Tesla K80 GPU 的基于 Web 的免费 Python 笔记本环境.
  * [Collect2](https://collect2.com)  — 创建一个 API 端点来测试、自动化和连接 webhook. 免费计划允许两个数据集、2000 条记录、1 个转发器和 1 个警报.
  * [Conversion Tools](https://conversiontools.io/)  - 用于文档、图像、视频、音频、电子书的在线文件转换器.  REST API 可用.  Node.js、PHP、Python 的库. 支持最大 50 GB 的文件（用于付费计划）. 免费套餐受文件大小和每天转换次数的限制.
  * [Coupler](https://www.coupler.io/)  - 在应用程序之间同步的数据集成工具. 它可以创建实时仪表板和报告、转换和操作值、收集和备份见解. 免费计划有无限用户，每月 100 次运行 1000 行和无限集成.
  * [CraftMyPDF](https://craftmypdf.com)  - 使用拖放式编辑器和简单的 API 从可重复使用的模板自动生成 PDF 文档. 免费计划附带 100 个 PDF/月和 3 个模板.
  * [CurlHub](https://curlhub.io)  — 用于检查和调试 API 调用的代理服务. 免费计划包括每月 10,000 个请求.
  * [CurrencyScoop](https://currencyscoop.com) - Realtime currency data API for fintech apps. Free plan includes 5000 calls per month.
  * [Datapane](https://datapane.com) - API for building interactive reports in Python and deploying Python scripts and Jupyter Notebooks as self-service tools.
  * [DB Designer](https://www.dbdesigner.net/) — Cloud based Database schema design and modeling tool with a free starter plan of 2 Database models and 10 tables per model.
  * [DeepAR](https://developer.deepar.ai)  — 适用于任何平台的增强现实面部过滤器，只需一个 SDK. 免费计划提供多达 10 个每月活跃用户 (MAU) 并跟踪多达 4 个面孔
  * [Deepnote](https://deepnote.com) - A new kind of data science notebook. Jupyter-compatible with real-time collaboration and running in the cloud. Free tier includes unlimited personal projects, up to 750 hours of standard hardware and teams with up to 3 editors.
  * [Diggernaut](https://www.diggernaut.com/) — Cloud based web scraping and data extraction platform for turning any website to the dataset or to work with it as with an API. Free plan includes 5K page requests monthly.
  * [Disease.sh](https://disease.sh/) — A free API providing accurate data for building the Covid-19 related useful Apps.
  * [dominodatalab.com](https://www.dominodatalab.com) — 支持 Python、R、Spark、Hadoop、MATLAB 等的数据科学.
  * [dreamfactory.com](https://dreamfactory.com/) — Open source REST API backend for mobile, web, and IoT applications. Hook up any SQL/NoSQL database, file storage system, or external service and it instantly creates a comprehensive REST API platform with live documentation, user management,...
  * [DynaPictures](https://dynapictures.com) - Design automation tool which lets you dynamically generate images over REST API. Change colors, texts, logos and images on the fly. Free plan includes 30 generated images per month and 3 image templates.
  * [Efemarai](https://efemarai.com) - Testing and debugging platform for ML models and data. Visualize any computational graph. Free 30 debugging sessions per month for developers.
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) - Free web-based HTTP client to send HTTP requests.
  * [Export SDK](https://exportsdk.com) - PDF generator API with drag and drop template editor that also provides an SDK and no-code integrations. Free plan comes with 250 pages per month, unlimited users and three templates.
  * [FraudLabs Pro](https://www.fraudlabspro.com)  — 筛选信用卡支付欺诈的订单交易. 此 REST API 将根据订单的输入参数检测所有可能的欺诈特征. 免费微型计划每月有 500 笔交易.
  * [FreeGeoIP.app](https://freegeoip.app/) - Completely free Geo IP information (JSON, CSV, XML). No registration required, 15000 queries per hour rate limit.
  * [GeoDataSource](https://www.geodatasource.com) — Location search service lookup for city name by using latitude and longitude coordinate. Free API queries up to 500 times per month.
  * [Glitterly](https://glitterly.app/)  - 以编程方式从基本模板生成动态图像.  Restful API 和 nocode 集成. 免费套餐每月提供 50 张图片和 5 个模板.
  * [GoodData](https://www.gooddata.com/) - Data as a Service - Create interactive and insightful dashboards. Free tier comes with 5 workspaces and 100 MB/workspace.
  * [Hookbin](https://hookbin.com/)  - 创建唯一（公共或私有）端点来收集、解析和检查 HTTP 请求. 检查标头、正文、查询字符串、cookie、上传的文件等.对于测试/检查 webhook 很有用. 类似于 RequestBin 和 Webhook.site.
  * [Hoppscotch](https://hoppscotch.io) - 免费、快速、美观的 API 请求生成器。
  * [Hybiscus](https://hybiscus.dev/) - Build pdf reports using a simple declarative API. Free tier includes upto 100 single page reports per month with the ability to customise color pallet and fonts.
  * [Invantive Cloud](https://cloud.invantive.com/)  — 使用 Invantive SQL 或 OData4（通常是 Power BI 或 Power Query）访问 70 多个（云）平台，例如 Exact Online、Twinfield、ActiveCampaign 或 Visma. 包括数据复制和交换. 开发人员和实施顾问的免费计划. 对数据量有限制的特定平台免费.
  * [ipaddress.sh](https://ipaddress.sh) — 获取不同公共 IP 地址的简单服务 [formats](https://about.ipaddress.sh/).
  * [Iploka](https://iploka.com/) — IP to Geolocation API - Forever free plan for developers with 10k requests per month limit.
  * [IP Geolocation](https://ipgeolocation.io/) — IP Geolocation API - Forever free plan for developers with 30k requests per month (1k/day) limit.
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) — IP Geolocation API from Abstract - Extensive free plan allowing 200,000 requests per month.
  * [IP2Location](https://www.ip2location.com) — Freemium IP geolocation service. LITE database is available for free download. Import the database in server and perform local query to determine city, coordinates and ISP information.
  * [ipapi](https://ipapi.co/) - IP Address Location API by Kloudend, Inc - A reliable geolocation API, built on AWS, trusted by Fortune 500. Free tier offers 30k lookups/month (1k/day) without signup. Contact us for a higher limit trial plan.
  * [IPinfo](https://ipinfo.io/) — Fast, accurate, and free (up to 50k/month) IP address data API. Offers APIs with details on geolocation, companies, carriers, IP ranges, domains, abuse contacts, and more. All paid APIs can be trialed for free.
  * [IPFast](https://ip-fast.com/) — Find out your IP Address and related detailed information using the free, fastest and simple lookup tool.
  * [IPList](https://www.iplist.cc)  — 查找有关任何 IP 地址的详细信息，例如 Geo IP 信息、Tor 地址、主机名和 ASN 详细信息. 个人和企业用户免费.
  * [BigDataCloud](https://www.bigdatacloud.com/) - Provides fast, accurate and free (Unlimited or up to 10K-50K/month) APIs for modern web like IP Geolocation, Reverse Geocoding, Networking Insights, Email and Phone Validation, Client Info and more.
  * [IPTrace](https://iptrace.io) — An embarrassingly simple API that provides reliable and useful IP geolocation data for your business.
  * [JSON IP](https://getjsonip.com)  — 返回请求它的客户端的公共 IP 地址. 免费层无需注册. 可以使用客户端 JS 直接从浏览器请求使用 CORS 数据. 对于监控客户端和服务器 IP 变化的服务很有用. 无限请求.
  * [konghq.com/](https://konghq.com/) — API Marketplace and powerful tools for private and public APIs. With the free tier, some features are limited such as monitoring, alerting and support.
  * [Kreya](https://kreya.app)  — 用于调用和测试 gRPC API 的免费 gRPC GUI 客户端. 可以通过服务器反射导入 gRPC API.
  * [KSoft.Si](https://api.ksoft.si/) — 免费歌词 api 主要针对不和谐机器人.还提供广泛的图像和用户数据库
  * [Lightly](https://www.lightly.ai/) — Improve your machine learning models by using the right data. Use datasets of up to 1'000 samples for free.
  * [MailboxValidator](https://www.mailboxvalidator.com)  — 电子邮件验证服务使用真实的邮件服务器连接来确认有效的电子邮件. 免费 API 计划每月有 300 次验证.
  * [microlink.io](https://microlink.io/) – It turns any website into data such as metatags normalization, beauty link previews, scraping capabilities or screenshots as a service. 100 reqs/day every day free.
  * [monkeylearn.com](https://monkeylearn.com/) — Text analysis with machine learning, free 300 queries/month.
  * [MockAPI](https://www.mockapi.io/)  — MockAPI 是一个简单的工具，可让您轻松地模拟 API、生成自定义数据并使用 RESTful 接口对其执行操作.  MockAPI 旨在用作原型设计/测试/学习工具. 每个项目免费 1 个项目/50 个资源.
  * [Mocki](https://mocki.io) - A tool that lets you create mock GraphQL and REST APIs synced to a GitHub repository. Simple REST APIs are free to create and use without signup.
  * [Mocko.dev](https://mocko.dev/) — Proxy your API, choose which endpoints to mock in the cloud and inspect traffic, for free. Speed up your development and integrations tests.
  * [Mocky](https://designer.mocky.io/) - A simple web app to generate custom HTTP responses for mocking HTTP request. Also available as [open source](https://github.com/julien-lafont/Mocky).
  * [reqres.in](https://reqres.in) - 一个免费托管的 REST-API 准备好响应您的 AJAX 请求.
  * [microenv.com](https://microenv.com) —  Create fake REST API for developers with possibility to generate code and app in docker container.
  * [neptune.ai](https://neptune.ai/)  - 记录、存储、显示、组织、比较和查询所有 MLOps 元数据. 个人免费：1 名成员、100 GB 元数据存储、200 小时监控/月
  * [News API](https://newsapi.org) — Search news on the web with code, get JSON results. Developers get 3,000 queries free each month.
  * [OCR.Space](https://ocr.space/) — An OCR API which parses image and pdf files returning the text results in JSON format. 25,000 requests per month free.
  * [Duply.co](https://duply.co)  — 从 API 和 URL 创建动态图像，设计模板一次并重复使用. 免费套餐每月通过 API 和 URL 创建 70 张图片，通过 Form 创建最多 100 张图片.
  * [OpenAPI3 Designer](https://openapidesigner.com/) — 免费直观地创建 Open API 3 定义.
  * [parsehub.com](https://parsehub.com/) — Extract data from dynamic sites, turn dynamic websites into APIs, 5 projects free.
  * [Pixela](https://pixe.la/)  - 免费日流数据库服务. 所有操作均由 API 执行. 也可以使用热图和折线图进行可视化.
  * [Postbacks](https://postbacks.io/) - Request HTTP callbacks for a later time. 8,000 free requests on signup.
  * [Postman](https://postman.com)  — 使用用于 API 开发的协作平台 Postman，简化工作流程并更快地创建更好的 API. 永久免费使用 Postman 应用程序. 邮递员云功能也永远免费，但有一定的限制.
  * [PrefectCloud](https://www.prefect.io/cloud/)  — 一个完整的数据流自动化平台. 所有计划都包括每月 20,000 次免费运行. 这足以支持大多数小型企业的 ETL.
  * [ProxyCrawl](https://proxycrawl.com/) — Crawl and scrape websites without the need of proxies, infrastructure or browsers. We solve captchas for you and prevent you being blocked. The first 1000 calls are free of charge.
  * [Public-Apis Github Repo](https://github.com/public-apis/public-apis) — A list of free public APIs.
  * [Supportivekoala](http://supportivekoala.com/) <i>— Allows you to autogenerate images by your input via templates.</i> <b>— 允许您通过模板输入自动生成图像。</b> <i>Free plan allows you to create up to 100 images per week.</i><b>免费计划允许您每周创建多达 100 张图像。</b>
  * [QuickMocker](https://quickmocker.com/)  — 在您自己的子域下管理在线虚假 API 端点，将请求转发到 localhost URL 以进行 webhook 开发和测试，使用 RegExp 和多种 HTTP 方法作为 URL 路径，优先考虑端点，100 多个短代码（动态或虚假响应值）用于响应模板，从 JSON 格式的 OpenAPI (Swagger) 规范导入，代理请求，通过 IP 地址和授权标头限制端点. 免费帐户提供 1 个随机子域、10 个端点、5 个 RegExp URL 路径、每个端点 50 个短代码、每天 100 个请求、请求日志中的 50 个历史记录.
  * [RequestBin.com](https://requestbin.com) <i>— Create a free endpoint to which you can send HTTP requests.</i> <b>— 创建一个可以向其发送 HTTP 请求的免费端点。</b> <i>Any HTTP requests sent to that endpoint will be recorded with the associated payload and headers so you can observe requests from webhooks and other services.</i><b>发送到该端点的任何 HTTP 请求都将与相关的有效负载和标头一起记录，以便您可以观察来自 webhook 和其他服务的请求。</b>
  * [restlet.com](https://restlet.com/products/apispark/) — APISpark 使任何 API、应用程序或数据所有者能够通过直观的浏览器界面在几分钟内成为 API 提供者.
  * [Roboflow](https://roboflow.com) - create and deploy a custom computer vision model with no prior machine learning experience required. Free tier includes up to 1,000 free source images.
  * [ROBOHASH](https://robohash.org/) - Web service to generate unique (cool :) images from any text.
  * [Scraper.AI](https://scraper.ai)  - SaaS 可将任何网站转变为可消耗的 API，供您构建. 每月免费 50 次提取和 10000 次 API 调用.
  * [Scraper's Proxy](https://scrapersproxy.com)  — 用于抓取的简单 HTTP 代理 API. 匿名抓取，而不必担心限制、阻止或验证码. 每月前 100 次成功抓取免费，包括 javascript 渲染（如果您联系支持人员可以获得更多）.
  * [ScrapingAnt](https://scrapingant.com/)  — 无头 Chrome 抓取 API 和免费检查代理服务.  Javascript 渲染、高级轮换代理、避免验证码. 提供免费计划.
  * [ScraperBox](https://scraperbox.com/) — Undetectable web scraping API using real Chrome browsers and proxy rotation. Use a simple API call to scrape any web page. Free plan has 1000 requests per month.
  * [ScrapingDog](https://scrapingdog.com/) — Scrapingdog handles millions of proxies, browsers and CAPTCHAs to provide you with HTML of any web page in a single API call. It also provides Web Scraper for Chrome & Firefox and a software for instant scraping demand. Free plans available.
  * [scrapinghub.com](https://scrapinghub.com)  — 使用可视化界面和插件进行数据抓取. 免费计划包括在共享服务器上无限制抓取.
  * [ScrapingNinja](https://www.scrapingninja.co/) — Handle JS rendering, Chrome Headless, Proxy rotation and CAPTCHAs solving all in one place. The first 1000 are free of charge, no credit card required.
  * [Sheetson](https://sheetson.com) <i>- Instantly turn any Google Sheets into RESTful API.</i> <b>- 立即将任何 Google 表格转换为 RESTful API。</b> <i>Free plan available.</i><b>提供免费计划。</b>
  * [shrtcode API](https://shrtco.de/docs) - Free URL Shortening API without authorization and no request limits.
  * [SerpApi](https://serpapi.com/)  - 实时搜索引擎抓取 API. 返回 Google、Youtube、Bing、百度、沃尔玛和许多其他引擎的结构化 JSON 结果. 免费计划包括每月 100 次成功的 API 调用.
  * [Similar Words API](https://word-simi.herokuapp.com/) — 一个查找相似词的 API，拥有大约 400 万个词的词汇.
  * [Sofodata](https://www.sofodata.com/) - Create secure RESTful APIs from CSV files. Upload a CSV file and instantly access the data via its API allowing faster application development. Free plan includes 2 APIs and 2,500 API calls per month. No credit card required.
  * [tamber](https://tamber.com)  — 在您的应用中加入深度学习驱动的推荐. 免费 5k 月活跃用户.
  * [Time Door](https://timedoor.io) - 时间序列分析 API.
  * [TinyMCE](https://www.tiny.cloud) - rich text editing API. Core features free for unlimited usage.
  * [Unixtime](https://unixtime.co.za) - Free API to convert Unixtime to DateTime and vice versa.
  * [Webhook.site](https://webhook.site) - Easily test HTTP webhooks with this handy tool that displays requests instantly.
  * [wit.ai](https://wit.ai/) — NLP for developers.
  * [wolfram.com](http://wolfram.com/language/) — Built-in knowledge-based algorithms in the cloud.
  * [wrapapi.com](https://wrapapi.com/) — Turn any website into a parameterized API. 30k API calls per month.
  * [ZenRows](https://www.zenrows.com/) — Web Scraping API & proxy server that bypasses any anti-bot solution while offering javascript rendering, rotating proxies, and geotargeting. Free tier of 1000 API calls.
  * [Zenscrape](https://zenscrape.com/web-scraping-api) — Web scraping API with headless browsers, residentials IPs and simple pricing. 1000 free API calls/month, extra free credits for students and non-profits.
  * [ip-api](https://ip-api.com) — IP Geolocation API，免费用于非商业用途，无需 API 密钥，免费计划的同一 IP 地址限制为 45 次/分钟.
  * [WebScraping.AI](https://webscraping.ai)  - 带有内置解析、Chrome 渲染和代理的简单 Web Scraping API. 每月 2000 次免费 API 调用.
  * [Zipcodebase](https://zipcodebase.com)  - 免费邮政编码 API，访问全球邮政编码数据.  10000 个免费请求/月.
  * [EVA](http://eva.pingutil.com/) - Free email validator API, which helps to identify whether an email is disposable and having valid MX records.
  * [happi.dev](https://happi.dev)  - 免费增值 api 服务集合（音乐、汇率、键值存储、语言检测、密码生成器、二维码生成器、歌词）. 每月 8000 次免费 API 调用.
  * [huggingface.co](https://huggingface.co)  - 为 Pytorch、TensorFlow 和 JAX 构建、训练和部署 NLP 模型. 每月最多可释放 30k 个输入字符.
  * [vatcheckapi.com](https://vatcheckapi.com) - Simple and free VAT number validation API. 500 free requests per month.
  * [numlookupapi.com](https://numlookupapi.com) - Free phone number validation API - 100k free requests / month.
  * [geojs.io](https://www.geojs.io/) - Highly available REST/JSON/JSONP IP Geolocation lookup API.


## Artifact Repos

 * [Artifactory](https://jfrog.com/start-free/) - An artifact repository that supports numerous package formats like Maven, Docker, Cargo, Helm, PyPI, CocoaPods, and GitLFS. Incudes package scanning tool XRay and CI/CD tool Pipelines (formerly Shippable) with a free tier of 2,000 CI/CD minutes per month.
 * [central.sonatype.org](https://central.sonatype.org) — The default artifact repository for Apache Maven, SBT and other build systems.
 * [cloudrepo.io](https://cloudrepo.io) - Cloud based, private and public, Maven and PyPi repositories. Free for open source projects.
 * [cloudsmith.io](https://cloudsmith.io) — Simple, secure and centralised repository service for Java/Maven, RedHat, Debian, Python, Ruby, Vagrant +more. Free tier + free for open source.
 * [jitpack.io](https://jitpack.io/) — Maven repository for JVM and Android projects on GitHub, free for public projects.
 * [packagecloud.io](https://packagecloud.io/users/new?plan=free_usage_plan) — Easy to use repository hosting for: Maven, RPM, DEB, PyPi, NPM, and RubyGem packages (has free tier).
 * [repsy.io](https://repsy.io) — 1 GB Free private/public Maven Repository.


## Tools for Teams and Collaboration

  * [3Cols](https://3cols.com/) - 一个免费的基于云的代码片段管理器，用于个人和协作代码.
  * [Bitwarden](https://bitwarden.com) — The easiest and safest way for individuals, teams, and business organizations to store, share, and sync sensitive data.
  * [Braid](https://www.braidchat.com/)  — 专为团队设计的聊天应用程序. 对公共访问组、无限用户、历史记录和集成免费. 它还提供自托管的开源版本.
  * [cally.com](https://cally.com/) — Find the perfect time and date for a meeting. Simple to use, works great for small and large groups.
  * [Calendly](https://calendly.com) — Calendly is the tool for connecting and scheduling meetings. Free plan provides 1 Calendar connection per user and Unlimited meetings. Desktop and Mobile apps also provided.
  * [Discord](https://discord.com/)  — 与公共/私人房间聊天.  Markdown 文本、语音、视频和屏幕共享功能. 无限用户免费.
  * [Telegram](https://telegram.org/)  — Telegram 适用于所有想要快速可靠的消息传递和通话的人. 企业用户和小型团队可能喜欢大型群组、用户名、桌面应用程序和强大的文件共享选项.
  * [Duckly](https://duckly.com/) — Talk and collaborate in real-time with your team. Pair programming with any IDE, terminal sharing, voice, video and screen sharing. Free for small teams.
  * [evernote.com](https://evernote.com/) — Tool for organizing information. Share your notes and work together with others
  * [Fibery](https://fibery.io/)  — 连接的工作空间平台. 单用户免费，最多 2 GB 磁盘空间.
  * [Filestash](https://www.filestash.app) — A Dropbox-like file manager that connects to a range of protocols and platforms: S3, FTP, SFTP, Minio, Git, WebDAV, Backblaze, LDAP and more.
  * [flock.com](https://flock.com) — A faster way for your team to communicate. Free Unlimited Messages, Channels, Users, Apps & Integrations
  * [Flowdash](https://flowdash.com/)  — 自动化业务工作流程. 免费套餐最多可容纳 3 个用户、1000 个任务和 3 个工作流.
  * [flowdock.com](https://www.flowdock.com/) — 聊天和收件箱，最多 5 人的团队免费
  * [GitDailies](https://gitdailies.com)  - 您团队在 GitHub 上的提交和拉取请求活动的每日报告. 包括推送可视化工具、对等识别系统、自定义警报生成器. 免费层有无限用户、3 个存储库、3 个警报配置.
  * [gitter.im](https://gitter.im/)  — 聊天，用于 GitHub. 无限制的公共和私人房间，最多 25 人的团队免费
  * [hangouts.google.com](https://hangouts.google.com/) — 一个可以免费进行所有对话的地方，需要一个 Google 帐户
  * [HeySpace](https://hey.space) - Task management tool with chat, calendar, timeline and video calls. Free for up to 5 users.
  * [helplightning.com](https://www.helplightning.com/)  — 通过增强现实帮助视频. 免费，无需分析、加密、支持
  * [ideascale.com](https://ideascale.com/) — Allow clients to submit ideas and vote, free for 25 members in 1 community
  * [Igloo](https://www.igloosoftware.com/) — Internal portal for sharing documents, blogs and calendars etc. Free for up to 10 users.
  * [Keybase](https://keybase.io/) — Keybase 是 Slack 的一个很酷的 FOSS 替代品，它确保每个人的聊天和文件安全，从家庭到社区再到公司.
  * [Google Meet](https://meet.google.com/) — Use Google Meet for your business's online video meeting needs. Meet provides secure, easy-to-join online meetings.
  * [/meet for Slack](https://meetslack.com)  - 在任何频道、组或 DM 中使用 /meet 直接从 Slack 启动 Google 会议. 免费，没有任何限制.
  * [MarkUp](https://www.markup.io/) — MarkUp lets you collect feedback directly on top of your websites, PDFs and images.
  * [meet.jit.si](https://meet.jit.si/) — One click video conversations, screen sharing, for free
  * [Microsoft Teams](https://products.office.com/microsoft-teams/free)  — Microsoft Teams 是一个基于聊天的数字中心，可通过单一体验将对话、内容和应用程序集中在一个地方. 最多 50 万用户免费.
  * [Miro](https://miro.com/) - Scalable, secure, cross-device and enterprise-ready team collaboration whiteboard for distributed teams. With freemium plan.
  * [nootiz](https://www.nootiz.com/) - The go-to tool for gathering and managing visual feedback on any website
  * [Notion](https://www.notion.so/)  - Notion 是一个笔记和协作应用程序，支持 Markdown，还集成了任务、wiki 和数据库. 该公司将该应用程序描述为用于记笔记、项目管理和任务管理的一体化工作区. 除了跨平台应用程序外，它还可以通过大多数网络浏览器访问.
  * [Nuclino](https://www.nuclino.com)  - 一个轻量级的协作 wiki，包含您团队的所有知识、文档和笔记. 具有所有基本功能的免费计划，最多 50 个项目，5GB 总存储空间.
  * [PageShare.dev](https://www.pageshare.dev) - Adds visual reviews capabilities into GitHub Pull Requests with no need to deploy websites. Free for up to 10 pages each month and 100MB of storage in total.
  * [Pendulums](https://pendulums.io/) - Pendulums is a free time tracking tool which helps you to manage your time in a better manner with an easy to use interface and useful statistics.
  * [Raindrop.io](https://raindrop.io) - Private and secure bookmarking app for macOS, Windows, Android, iOS and Web. Free Unlimited Bookmarks and Collaboration.
  * [element.io](https://element.io/)  — 一个基于 Matrix 的去中心化开源通信工具. 群聊、直接消息、加密文件传输、语音和视频聊天以及与其他服务的轻松集成.
  * [Rocket.Chat](https://rocket.chat/) - Shared inbox for teams, secure, unlimited and open source.
  * [seafile.com](https://www.seafile.com/)  — 私有或云存储、文件共享、同步、讨论. 私人版已满. 云版本只有 1 GB
  * [Slab](https://slab.com/) <i>— A modern knowledge management service for teams.</i> <b>— 面向团队的现代知识管理服务。</b> <i>Free for up to 10 users.</i><b>最多 10 个用户免费。</b>
  * [slack.com](https://slack.com/) — 对无限用户免费，但有一些功能限制
  * [Spectrum](https://spectrum.chat/) - Create public or private communities for free.
  * [StatusPile](https://www.statuspile.com/)  - 状态页面的状态页面. 跟踪上游提供商的状态页面.
  * [talky.io](https://talky.io/)  — 免费群视频聊天. 匿名的. 点对点. 无需插件、注册或付款
  * [Tefter](https://tefter.io)  - 具有强大 Slack 集成的书签应用程序. 对开源团队免费.
  * [TeleType](https://teletype.oorja.io/) — share terminals, voice, code, whiteboard and more. no sign-in required, end-to-end encrypted collaboration for developers.
  * [TimeCamp](https://www.timecamp.com/) - Free time tracking software for unlimited users. Easily integrates with PM tools like Jira, Trello, Asana, etc.
  * [Tree Schema](https://treeschema.com/)  — 使用 API 进行数据目录和元数据管理，将数据沿袭作为代码进行管理. 最多 5 名用户的团队免费.
  * [twist.com](https://twist.com)  — 一个异步友好的团队通信应用程序，其中对话保持有条理和主题. 提供免费和无限计划. 为符合条件的团队提供折扣.
  * [BookmarkOS.com](https://bookmarkos.com) - Free all-on-one bookmark manager, tab manager, and task manager in a customizable online desktop with folder collaboration.
  * [typetalk.com](https://www.typetalk.com/) — 通过网络或手机上的即时消息与您的团队分享和讨论想法
  * [Tugboat](https://tugboat.qa) - Preview every pull request, automated and on-demand. Free for all, complimentary Nano tier for non-profits.
  * [whereby.com](https://whereby.com/) — One click video conversations, for free (formerly known as appear.in)
  * [vadoo.tv](https://vadoo.tv/)  — 视频托管和营销变得简单. 一键上传视频. 记录、管理、分享等等. 免费套餐最多提供 10 个视频、1 GB 存储空间、10 GB 带宽/月
  * [vspace](https://vvv.space/) — Free links manager with private/public spaces, includes slack and google docs integration and chrome plugin.
  * [userforge.com](https://userforge.com/) - Interconnected online personas, user stories and context mapping.  Helps keep design and dev in sync, free for up to 3 personas and 2 collaborators.
  * [wistia.com](https://wistia.com/) — Video hosting with viewer analytics, HD video delivery and marketing tools to help understand your visitors, 25 videos and Wistia branded player
  * [wormhol.org](https://www.wormhol.org/) — Straightforward file sharing service. Share unlimited files up to 5GB to as many peers as you want.
  * [zoom.us](https://zoom.us/)  — 安全的视频和网络会议，可用的附加组件. 免费限时 40 分钟
  * [shtab.app](https://shtab.app/) - 项目管理服务，通过基于 AI 的跟踪器使办公室协作和远程透明化.
  * [zdoo.co](https://www.zdoo.co)  — 借助 CRM、OA 和项目管理套件，zdoo 非常适合团队协作. 提供有限用户和空间的免费云版本，高级版本免费试用一个月.
  * [Zulip](https://zulip.com/) — Real-time chat with unique email-like threading model. Free plan includes 10,000 messages of search history and File storage up to 5 GB. also it provides self-hostable open-source version.
  * [Automate.io](https://automate.io)  - 简单和复杂的自动化工作流程工具，具有 200 多个应用程序集成. 每月 300 次操作和 5 个机器人是免费
  * [robocorp.com](https://robocorp.com) - Open-source stack for powering Automation Ops. Try out Cloud features and implement simple automations for free. Robot work 240 min/month, 10 Assistant runs, Storage of 100 MB.
  * [Fleep.io](https://fleep.io/) — Fleep an alternative to Slack. It has a free plan for small teams with full message history, unlimited 1:1 conversations, 1 group conversation and 1 GB file storage.
  * [Chanty.com](https://chanty.com/) — Chanty is another alternative to Slack. It has a free forever plan for small teams (up to 10) with unlimited public and private conversations, searchable history, unlimited 1:1 audio calls, unlimited voice messages, 10 integrations and 20 GB storage per team.


## CMS

  * [acquia.com](https://www.acquia.com/) — Hosting for Drupal sites. Free tier for developers. Free development tools (such as Acquia Dev Desktop) also available
  * [Contentful](https://www.contentful.com/)  — 无头 CMS. 云中的内容管理和交付 API. 附带一个免费社区空间，其中包括 5 个用户、25K 条记录、48 种内容类型、2 个语言环境.
  * [Cosmic](https://www.cosmicjs.com/) — Headless CMS and API toolkit. Free personal plans for developers.
  * [Crystallize](https://crystallize.com) — Headless PIM with ecommerce support. Built-in GraphQL API. Free version includes unlimited users, 1000 catalogue items, 5 GB/month bandwidth and 25k/month API calls.
  * [DatoCMS](https://www.datocms.com/) - Offers free tier for small projects. DatoCMS is a GraphQL based CMS. On the lower tier you have 100k/month calls.
  * [Directus](https://directus.io) — Headless CMS. A completely free and open-source platform for managing assets and database content on-prem or in the Cloud. No limitations or paywalls.
  * [Forestry.io/](https://forestry.io/)  — 无头 CMS. 为您的编辑提供 Git 的强大功能. 轻松创建和编辑基于 Markdown 的内容. 附带三个免费网站，其中包括 3 个编辑器、即时预览. 与托管在 Netlify/GitHubpages/ 其他地方的博客集成
  * [FrontAid](https://frontaid.io/) <i>— Headless CMS that stores JSON content directly in your own Git repository.</i> <b>— 将 JSON 内容直接存储在您自己的 Git 存储库中的无头 CMS。</b> <i>No restrictions.</i><b>无限制。</b>
  * [kontent.ai](https://www.kontent.ai) - A Content-as-a-Service platform that gives you all the headless CMS benefits while empowering marketers at the same time. Developer plan provides 2 users with unlimited projects with 2 environments for each, 500 content items, 2 languages with Delivery and Management API, and Custom elements support. Larger plans available to meet your needs.
  * [Prismic](https://www.prismic.io/) — Headless CMS. Content management interface with fully hosted and scalable API. The Community Plan provides 1 user with unlimited API calls, documents, custom types, assets, and locales. Everything that you need for your next project. Bigger free plans available for Open Content/Open Source projects.
  * [Sanity.io](https://www.sanity.io/)  - 带有开源编辑环境和实时托管数据存储的结构化内容平台. 无限的项目. 无限的管理员用户、3 个非管理员用户、2 个数据集、500K API CDN 请求、10GB 带宽、每个项目免费包含 5GB 资产.
  * [sensenet](https://sensenet.com) - API-first headless CMS providing enterprise-grade solutions for businesses of all size. The Developer plan provides 3 users, 500 content items, 3 built-in roles, 25+5 content types, fully accessible REST API, document preview generation and Office Online editing.
  * [GraphCMS](https://graphcms.com/) - Offers free tier for small projects. GraphQL first API. Move away from legacy solutions to the GraphQL native Headless CMS - and deliver omnichannel content API first.
  * [Squidex](https://squidex.io/) - Offers free tier for small projects. API / GraphQL first. Open source, and based on event sourcing (versing every changes automatically).


## Code Quality

  * [SoftaCheck](https://www.softacheck.com/) — An online tool that performs static analysis for C/C++ code using open source tools such as cppcheck and clang-tidy and automatically generates code documentation for users using doxygen. This tool is free for use.
  * [beanstalkapp.com](https://beanstalkapp.com/) — A complete workflow to write, review and deploy code), free account for 1 user and 1 repository with 100 MB of storage
  * [browserling.com](https://www.browserling.com/) — Live interactive cross-browser testing, free only 3 minutes sessions with MS IE 9 under Vista at 1024 x 768 resolution
  * [codacy.com](https://www.codacy.com/) — Automated code reviews for PHP, Python, Ruby, Java, JavaScript, Scala, CSS and CoffeeScript, free for unlimited public and private repositories
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev) - Automated Infrastructure as Code review tool for DevOps integrates with GitHub, Bitbucket and GitLab (even self-hosted). In addition to standard languages, it analyzes also Ansible, Terraform, CloudFormation, Kubernetes, and more. (open-source free)
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
  * [gerrithub.io](https://review.gerrithub.io/) — Gerrit code review for GitHub repositories for free
  * [gocover.io](https://gocover.io/) — Code coverage for any [Go](https://golang.org/) 包裹
  * [goreportcard.com](https://goreportcard.com/) — Code Quality for Go projects, free for Open Source
  * [gtmetrix.com](https://gtmetrix.com/) — Reports and thorough recommendations to optimize websites
  * [holistic.dev](https://holistic.dev/) - The #1 static code analyzer for Postgresql optimization. Performance, security, and architect database issues automatic detection service
  * [houndci.com](https://houndci.com/) — Comments on GitHub commits about code quality, free for Open Source
  * [Imgbot](https://github.com/marketplace/imgbot) — Imgbot is a friendly robot that optimizes your images and saves you time. Optimized images mean smaller file sizes without sacrificing quality. It's free for open source.
  * [Kritika](https://kritika.io/)  — Perl 的静态代码分析与 GitHub 的集成. 免费用于无限的公共存储库.
  * [resmush.it](https://resmush.it) — reSmush.it is a FREE API that provides image optimization. reSmush.it has been implemented on the most common CMS such as Wordpress, Drupal or Magento. reSmush.it is the most used image optimization API with more than 7 billions images already treated, and is still Free of charge.
  * [insight.sensiolabs.com](https://insight.sensiolabs.com/) — Code Quality for PHP/Symfony projects, free for Open Source
  * [lgtm.com](https://lgtm.com) — Continuous security analysis for Java, Python, JavaScript, TypeScript, C#, C and C++, free for Open Source
  * [Moderne.io](https://app.moderne.io) — Automatic source code refactoring. Moderne offers framework migrations, code analysis with remediation, and unrivaled code transformation at scale, so developers can spend their time building new things instead of maintaining the old. Free for Open Source.
  * [reviewable.io](https://reviewable.io/) — Code review for GitHub repositories, free for public or personal repos
  * [parsers.dev](https://parsers.dev/) - Abstract syntax tree parsers and intermediate representation compilers as a service
  * [scan.coverity.com](https://scan.coverity.com/) — Static code analysis for Java, C/C++, C# and JavaScript, free for Open Source
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) — Continuous inspection platform, free for Open Source
  * [shields.io](https://shields.io) — Quality metadata badges for open source projects
  * [Sider](https://sider.review)  — 多种语言的代码审查平台. 支持与 GitHub 集成. 对拥有无限用户的公共存储库免费.
  * [sonarcloud.io](https://sonarcloud.io) — Automated source code analysis for Java, JavaScript, C/C++, C#, VB.NET, PHP, Objective-C, Swift, Python, Groovy and even more languages, free for Open Source
  * [SourceLevel](https://sourcelevel.io/) — Automated Code Review and Team Analytics. Free for Open Source and organizations up to 5 collaborators.
  * [Typo CI](https://github.com/marketplace/typo-ci) — Typo CI reviews your Pull Requests and commits for spelling mistakes, free for Open Source.
  * [Viezly](https://viezly.com/) - Enhanced code review tool for easier code reading and navigation. Free for Open Source and free for personal usage.
  * [webceo.com](https://www.webceo.com/) — SEO tools but with also code verifications and different type of advices
  * [zoompf.com](https://zoompf.com/) — 修复您网站的性能，详细分析


## Code Search and Browsing

  * [codota.com](https://www.codota.com/)  — Codota 通过提供从世界上所有代码中学到的见解，帮助开发人员更快地创建更好的软件. 插件可用.
  * [libraries.io](https://libraries.io/) — Search and dependency update notifications for 32 different package managers, free for open source
  * [Namae](https://namae.dev/) - Search across various websites like github,gitlab,heroku,netlify and many more for availabilty of your project name.
  * [searchcode.com](https://searchcode.com/) — 全面的基于文本的代码搜索，对开源免费
  * [sourcegraph.com](https://about.sourcegraph.com/) — Java, Go, Python, Node.js, etc., code search/cross-references, free for Open Source
  * [tickgit.com](https://www.tickgit.com/) — Surfaces `TODO` comments (and other markers) to identify areas of code worth returning to for improvement.
  * [CodeKeep](https://codekeep.io) - Google Keep for Code Snippets. Organize,Discover and share code snippets, featuring a powerful code screenshot tool with preset templates and linking feature.


## CI and CD

  * [AccessLint](https://github.com/marketplace/accesslint) — AccessLint brings automated web accessibility testing into your development workflow. It's free for open source and education purposes.
  * [appcircle.io](https://appcircle.io)  — 适用于 iOS 和 Android 的自动化移动 CI/CD/CT，带有在线设备模拟器.  20 分钟构建超时（开源为 60 分钟），单并发免费.
  * [appveyor.com](https://www.appveyor.com/) — CD service for Windows, free for Open Source
  * [bitrise.io](https://www.bitrise.io/) — A CI/CD for mobile apps, native or hybrid. With 200 free builds/month 10 min build time and two team members. OSS projects get 45 min build time, +1 concurrency and unlimited team size.
  * [buddy.works](https://buddy.works/) — 包含 5 个免费项目和 1 个并发运行的 CI/CD（120 次执行/月）
  * [buddybuild.com](https://www.buddybuild.com/) — 在一个无缝的迭代系统中为您的 iOS 和 Android 应用程序构建、部署和收集反馈
  * [circleci.com](https://circleci.com/) — 一个并发构建免费
  * [cirrus-ci.org](https://cirrus-ci.org) - Free for public GitHub repositories
  * [codefresh.io](https://codefresh.io) — 终身免费计划：1 个构建、1 个环境、共享服务器、无限制的公共存储库
  * [codemagic.io](https://codemagic.io/) - Free 500 build minutes/month
  * [codeship.com](https://codeship.com/) — 每月 100 个私有构建，5 个私有项目，开源无限制
  * [Continuous PHP](https://continuousphp.com/)  — Continuousphp 是第一个也是唯一一个在同一工作流程中构建、打包、测试和部署应用程序的以 PHP 为中心的平台. 免费用于社区项目，即 OSS/公共/教育项目.
  * [deployhq.com](https://www.deployhq.com/) — 1 个项目，每天进行 10 次部署（每月 30 分钟构建）
  * [drone](https://cloud.drone.io/) - Drone Cloud 使开发人员能够在多个架构上运行持续交付管道 - 包括 x86 和 Arm（32 位和 64 位） - 所有这些都在一个地方
  * [LayerCI](https://layerci.com) — CI for full stack projects. 1 full stack preview environment with 5GB memory & 3 CPUs .
  * [ligurio/awesome-ci](https://github.com/ligurio/awesome-ci) — 持续集成服务的比较
  * [Octopus Deploy](https://octopus.com) - Automated deployment and release-management. Free for <= 10 deployment targets.
  * [scalr.com](https://scalr.com/) - Remote state & operations backend for Terraform with full CLI support, integration with OPA and a hierarchical configuration model. Free up to 5 users.
  * [semaphoreci.com](https://semaphoreci.com/) — Free for Open Source, 100 private builds per month
  * [Squash Labs](https://www.squash.io/) — creates a VM for each branch and makes your app available from a unique URL, Unlimited public & private repos, Up to 2 GB VM Sizes.
  * [stackahoy.io](https://stackahoy.io) — 100% free. Unlimited deployments, branches and builds
  * [styleci.io](https://styleci.io/) — 仅限公共 GitHub 存储库
  * [Mergify](https://mergify.io) — workflow automation and merge queue for GitHub — Free for public GitHub repositories
  * [Integromat](https://www.integromat.com) — Workflow automation tool which lets you connect apps and automate workflows using UI, it supports many apps and most popular APIs. Free for public GitHub repositories, and free tier with 100 Mb, 1000 Operations and 15 minutes of minimum interval.



## Testing

  * [Applitools.com](https://applitools.com/) — Smart visual validation for web, native mobile and desktop apps. Integrates with almost all automation solutions (like Selenium and Karma) and remote runners (Sauce Labs, Browser Stack). free for open source. A free tier for a single user with limited checkpoints per week.
  * [Appetize](https://appetize.io) — Test your Android & iOS apps on this Cloud Based Android Phone/Tablets emulators and iPhone/iPad simulators directly in your browser. Free tier includes 1 concurrent session with 100 minutes usage per month. No limit on app size.
  * [Bird Eats Bug](https://www.birdeatsbug.com/) — Report bugs faster (and better). Record your screen with Bird browser extension, it will auto-capture technical data that engineers need to debug. Free tier suitable for small teams.
  * [lambdatest.com](https://www.lambdatest.com/) — selenium 和 cypress 的手动、可视化、屏幕截图和自动浏览器测试， [free for Open Source](https://www.lambdatest.com/open-source-cross-browser-testing-tool)
  * [browserstack.com](https://www.browserstack.com/) — 手动和自动浏览器测试， [free for Open Source](https://www.browserstack.com/open-source?ref=pricing)
  * [checkbot.io](https://www.checkbot.io/) — Browser extension that tests if your website follows 50+ SEO, speed and security best practices. Free tier for smaller websites.
  * [checklyhq.com](https://checklyhq.com) - Checkly is the API & E2E monitoring platform for the modern stack: programmable, flexible and loving JavaScript. Generous free tier for devs.
  * [crossbrowsertesting.com](https://crossbrowsertesting.com) - 云中的手动、可视化和 Selenium 浏览器测试 - [free for Open Source](https://crossbrowsertesting.com/open-source)
  * [cypress.io](https://www.cypress.io/)  - 对在浏览器中运行的任何东西进行快速、简单和可靠的测试.  Cypress Test Runner 始终是免费和开源的，没有任何限制和限制.  Cypress Dashboard 对最多 5 个用户的开源项目是免费的.
  * [everystep-automation.com](https://www.everystep-automation.com/) — Records and replays all steps made in a web browser and creates scripts,... free with fewer options
  * [Gremlin](https://www.gremlin.com/gremlin-free-software)  — Gremlin 的混沌工程工具允许您安全、可靠、简单地将故障注入您的系统，以便在它们导致面向客户的问题之前发现弱点.  Gremlin Free 提供对多达 5 个主机或容器的关闭和 CPU 攻击的访问权限.
  * [gridlastic.com](https://www.gridlastic.com/) — Selenium Grid testing with free plan up to 4 simultaneous selenium nodes/10 grid starts/4,000 test minutes/month
  * [loadmill.com](https://www.loadmill.com/) - Automatically create API and load tests by analyzing network traffic. Simulate up to 50 concurrent users for up to 60 minutes for free every month.
  * [percy.io](https://percy.io)  - 将可视化测试添加到任何 Web 应用程序、静态站点、样式指南或组件库. 无限的团队成员，演示应用程序和无限的项目，5,000 个快照/月.
  * [reflect.run](https://reflect.run)  - Web 应用程序的无代码自动化测试. 测试可以在应用程序内安排或从 CI/CD 工具执行. 每次测试运行都包括完整的视频记录以及控制台和网络日志. 免费套餐包括无限数量的已保存测试，每月运行 25 次测试，最多 3 位用户.
  * [saucelabs.com](https://saucelabs.com/) — Cross browser testing, Selenium testing and mobile testing, [free for Open Source](https://saucelabs.com/open-source)
  * [snippets.uilicious.com](https://snippets.uilicious.com) - It's like CodePen, but for cross browser testing. UI-licious lets write tests like user stories, and offers a free platform - UI-licious Snippets - that allows you to run unlimited number of tests on Chrome for free with no sign up requred, for up to 3 minutes per test run. Found a bug? You can simply copy the unique url to your test to show your devs exactly how to reproduce the bug.
  * [testingbot.com](https://testingbot.com/) — Selenium Browser and Device Testing, [free for Open Source](https://testingbot.com/open-source)
  * [Testspace.com](https://testspace.com/) - A Dashboard for publishing automated test results and a Framework for implementing manual tests as code using GitHub. The service is [free for Open Source](https://github.com/marketplace/testspace-com) accounts for 450 results per month.
  * [tesults.com](https://www.tesults.com)  — 测试结果报告和测试用例管理. 与流行的测试框架集成. 开源软件开发人员、个人、教育工作者和小团队入门可以要求超出基本免费项目的折扣和免费产品.
  * [websitepulse.com](https://www.websitepulse.com/tools/) — 各种免费的网络和服务器工具.
  * [qase.io](https://qase.io) - Test management system for Dev and QA teams. Manage test cases, compose test runs, perform test runs, track defects and measure impact. The free tier includes all core features, with 500Mb available for attachments and up to 3 users.
  * [knapsackpro.com](https://knapsackpro.com) - Speed up your tests with optimal test suite parallelisation on any CI provider. Split Ruby, JavaScript tests on parallel CI nodes to save time. Free plan for up to 10 minutes test files and free unlimited plan for Open Source projects.
  * [webhook.site](https://webhook.site) - Verify webhooks, outbound HTTP requests, or emails with a custom URL.  Temporary URL and email address is always free.
  * [Vaadin](https://vaadin.com) — Build scalable UIs in Java or TypeScript, and use the integrated tooling, components and design system to iterate faster, design better and simplify the development process. Unlimited Projects with 5 years free maintenance.
  * [Foresight](https://thundra.io/foresight) — Thundra Foresight 是一种工具，用于立即调试和排除测试故障，并优化 CI 管道中的构建持续时间和性能.


## Security and PKI

  * [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — Uncovers compromised systems in your network
  * [atomist.com](https://atomist.com/) — A quicker and more convenient way to automate a variety of development tasks. Now in beta.
  * [auth0.com](https://auth0.com/)  — 为开发 SSO 免费托管. 最多 2 个用于闭源项目的社交身份提供者.
  * [Authgear](https://www.authgear.com) - Bring Passwordless, OTPs, 2FA, SSO to your apps in minutes. All Front-end included. Free up to 5000 MAUs.
  * [Authress](https://authress.io/) — Authentication login and access control, unlimited identity providers for any project. Facebook, Google, Twitter and more. First 1000 API calls are free.
  * [Authy](https://authy.com) - Two-factor authentication (2FA) on multiple devices, with backups. Drop-in replacement for Google Authenticator. Free for up to 100 successful authentications.
  * [Bridgecrew](https://bridgecrew.io/) — Infrastructure as code (IaC) security powered by the open source tool - [Checkov](https://github.com/bridgecrewio/checkov) . 核心 Bridgecrew 平台可免费使用多达 50 个 IaC 资源.
  * [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services (AWS) security and compliance auditing and monitoring
  * [Cmd](https://cmd.com/) — Security platform providing real-time access control and dynamic policy enforcement on every Linux instance in your cloud or datacenter
  * [CodeNotary.io](https://www.codenotary.io/) — Open Source platform with indelible proof to notarize code, files, directories or container
  * [crypteron.com](https://www.crypteron.com/) — Cloud-first, developer-friendly security platform prevents data breaches in .NET and Java applications
  * [Datree](https://www.datree.io/) — Open Source CLI tool to prevent Kubernetes misconfigurations by ensuring that manifests and Helm charts follow best practices as well as your organization’s policies
  * [Dependabot](https://dependabot.com/) Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven 和 Gradle）、.NET、Go、Elm、Docker、Terraform、Git 子模块和 GitHub Actions 的自动依赖项更新.
  * [DJ Checkup](https://djcheckup.com)  — 使用这款免费、自动化的检查工具扫描您的 Django 站点是否存在安全漏洞. 从 Pony Checkup 网站分叉.
  * [Doppler](https://doppler.com/) — Universal Secrets Manager for application secrets and config, with support for syncing to various cloud providers. Free for unlimited users with basic access controls.
  * [duo.com](https://duo.com/)  — 网站或应用程序的双因素身份验证 (2FA).  10 个用户免费，所有身份验证方法，无限制，集成，硬件令牌.
  * [GitGuardian](https://www.gitguardian.com)  — 通过自动化的秘密检测和修复，将秘密远离源代码. 扫描您的 git 存储库以查找 350 多种类型的机密和敏感文件 - 免费供 25 名或更少开发人员的个人和团队使用.
  * [globalsign.com](https://www.globalsign.com/en/ssl/ssl-open-source/) — Free SSL certificates for Open Source
  * [Have I been pwned?](https://haveibeenpwned.com) — 用于获取违规信息的 REST API.
  * [hostedscan.com](https://hostedscan.com) — Online vulnerability scanner for web applications, servers, and networks. 10 free scans per month.
  * [Internet.nl](https://internet.nl) — Test for modern Internet Standards like IPv6, DNSSEC, HTTPS, DMARC, STARTTLS and DANE
  * [Jumpcloud](https://jumpcloud.com/) — Provides directory as a service similar to Azure AD, user management, single sign-on, and RADIUS authentication. Free for up to 10 users.
  * [keychest.net](https://keychest.net) - SSL 到期管理和证书购买与集成 CT 数据库
  * [letsencrypt.org](https://letsencrypt.org/) — 免费的 SSL 证书颁发机构，其证书受到所有主要浏览器的信任
  * [LoginRadius](https://www.loginradius.com/)  — 免费的托管用户身份验证服务. 电子邮件注册和 3 个社交服务提供商.
  * [logintc.com](https://www.logintc.com/) — Two-factor authentication (2FA) by push notifications, free for 10 users, VPN, Websites and SSH
  * [meterian.io](https://www.meterian.io/)  - 监控 Java、Javascript、.NET、Scala、Ruby 和 NodeJS 项目的依赖项中的安全漏洞. 一个私人项目免费，开源项目无限.
  * [MojoAuth](https://mojoauth.com/) - MojoAuth 可以在几分钟内轻松地在您的 Web、移动设备或任何应用程序上实施无密码身份验证.
  * [Mozilla Observatory](https://observatory.mozilla.org/) — 查找并修复您网站中的安全漏洞.
  * [Okta](https://developer.okta.com/) — User management, authentication and authorization. Free for up to 1000 monthly active users.
  * [onelogin.com](https://www.onelogin.com/) — 身份即服务 (IDaaS)、单点登录身份提供商、云 SSO IdP、3 个公司应用程序和 5 个个人应用程序、无限用户
  * [Operous](https://operous.dev/)  — 云实例测试工具，具有一套全面、自动化的最佳实践、性能和安全性测试套件. 免费套餐为 1 位用户提供 100 分钟测试时间、10 个测试套件和最多 5 个实例.
  * [opswat.com](https://www.opswat.com/) — 计算机、设备、应用程序、配置等的安全监控... 免费 25 位用户和 30 天历史用户.
  * [pyup.io](https://pyup.io) — Monitor Python dependencies for security vulnerabilities and update them automatically. Free for one private project, unlimited projects for open source.
  * [qualys.com](https://www.qualys.com/community-edition) — Find web app vulnerabilities, audit for OWASP Risks
  * [reCAPTCHAMe](https://recaptchame.com/)  — 免费的 reCAPTCHA 和 hCAPTCHA 后端服务. 无需服务器端编码. 适用于静态网站.
  * [report-uri.io](https://report-uri.io/) — CSP 和 HPKP 违规报告
  * [ringcaptcha.com](https://ringcaptcha.com/) — Tools to use phone number as id, available for free
  * [sawolabs.com](https://sawolabs.com/) - Simplify login and improve user experience by integrating passwordless authentication in your app. 5000 free authentications per month.
  * [snyk.io](https://snyk.io) — Can find and fix known security vulnerabilities in your open source dependencies. Unlimited tests and remediation for open source projects. Limited to 200 tests/month for your private projects.
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) — Very deep analysis of the configuration of any SSL web server
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
  * [Escape GraphQL Quickscan](https://escape.tech/quickscan)  - 一键安全扫描您的 GraphQL 端点. 免费，无需登录.


## Management System

  * [bitnami.com](https://bitnami.com/) — Deploy prepared apps on IaaS. Management of 1 AWS micro instance free
  * [Esper](https://esper.io)  — 适用于具有 DevOps 的 Android 设备的 MDM 和 MAM.  100 台设备免费，1 个用户许可证和 25 MB 应用程序存储.
  * [jamf.com](https://www.jamf.com/) — iPad、iPhone 和 Mac 的设备管理，3 台设备免费
  * [Miradore](https://miradore.com) — Device Management service. Stay up-to-date with your device fleet and secure an unlimited number of devices for free. Free plan offers basic features.
  * [moss.sh](https://moss.sh) - Help developers deploy and manage their web apps and servers. Free up to 25 git deployments per month
  * [runcloud.io](https://runcloud.io/) - Server management focusing mainly on PHP projects. Free for up to 1 server.
  * [ploi.io](https://ploi.io/)  - 服务器管理工​​具，可轻松管理和部署您的服务器和站点.  1台服务器免费.


## Messaging and Streaming

  * [Ably](https://www.ably.com/)  - 具有存在、持久性和保证交付的实时消息传递服务. 免费计划包括每月 300 万条消息、100 个高峰连接和 100 个高峰频道.
  * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ as a Service. Little Lemur plan: max 1 million messages/month, max 20 concurrent connections, max 100 queues, max 10,000 queued messages, multiple nodes in different AZ's
  * [connectycube.com](https://connectycube.com) - Unlimited chat messages, p2p voice & video calls, files attachments and push notifications. Free for apps up to 20K MAU.
  * [courier.com](https://www.courier.com/) — Single API for push, in-app, email, chat, SMS, and other messaging channels with template management and other features. Free plan includes 10,000 messages/mo.
  * [pusher.com](https://pusher.com/)  — 实时消息服务. 免费提供多达 100 个同时连接和 200,000 条消息/天
  * [scaledrone.com](https://www.scaledrone.com/)  — 实时消息服务. 免费提供多达 20 个同时连接和 100,000 个事件/天
  * [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io) 作为一项服务. 全球、AWS、GCP 和 Azure. 每月 4k 消息大小、50 个活动连接和 5GB 数据，永久免费.
  * [cloudkarafka.com](https://www.cloudkarafka.com/) - Free Shared Kafka cluster, up to 5 topics, 10MB data per topic and 28 days of data retention.
  * [pubnub.com](https://www.pubnub.com/)  - 每月 100 万笔交易的 Swift、Kotlin 和 React 消息传递. 事务可能包含多条消息.
  * [eyeson API](https://developers.eyeson.team/) - A video communication API service based on WebRTC (SFU, MCU) to build video platforms. Allows RealTime Data Injection, Video Layouts, Recordings, a fully featured hosted web UI (quickstart) or packages for custom UIs. Has a [free tier for developers](https://apiservice.eyeson.com/api-pricing) with 1000 meeting minutes a month.
  * [Upstash Kafka](https://upstash.com/kafka)  - 按请求定价的无服务器 Kafka 云产品. 它有一个免费层，每天最多 10000 条消息.



## Log Management

  * [bugfender.com](https://bugfender.com/) — Free up to 100k log lines/day with 24 hours retention
  * [humio.com](https://www.humio.com/) — 每天最多免费 2 GB，保留 7 天
  * [logdna.com](https://logdna.com) - Free for a single user, no retention, unlimited hosts and sources
  * [logentries.com](https://logentries.com/) — 每月最多免费 5 GB，保留 7 天
  * [loggly.com](https://www.loggly.com/) — Free for a single user, see the lite option
  * [logz.io](https://logz.io/) — Free up to 3 GB/day, 3 days retention
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-log-management) — Log Management service powered by Manage Engine. Free Plan offers 50 GB storage with 1 Month retention.
  * [papertrailapp.com](https://papertrailapp.com/) — 48 小时搜索，7 天存档，100 MB/月
  * [sematext.com](https://sematext.com/logsene) — Free up to 500 MB/day, 7 days retention
  * [sumologic.com](https://www.sumologic.com/) — Free up to 500 MB/day, 7 days retention
  * [logflare.app](https://logflare.app/) — Free for upto 12,960,000 enteries per app per month, 3 days retention
  * [logtail.com](https://logtail.com/)  — 基于 ClickHouse 的 SQL 兼容日志管理. 每月最多免费 1 GB，保留 3 天.


## Translation Management

  * [crowdin.com](https://crowdin.com/) — Unlimited projects, unlimited strings and collaborators for Open Source
  * [gitlocalize.com](https://gitlocalize.com) - Free and unlimited for both private and public repositories
  * [lingohub.com](https://lingohub.com/) — Free up to 3 users, always free for Open Source
  * [localazy.com](https://localazy.com) - Free for 1000 source language strings, unlimited languages, unlimited contributors, startup and open source deals
  * [Localeum](https://localeum.com) - Free up to 1000 strings, 1 user, unlimited languages, unlimited projects
  * [localizely.com](https://localizely.com/) — Free for Open Source
  * [Loco](https://localise.biz/) — Free up to 2000 translations, Unlimited translators, 10 languages/project, 1000 translatable assets/project
  * [oneskyapp.com](https://www.oneskyapp.com/) — Limited free edition for up to 5 users, free for Open Source
  * [POEditor](https://poeditor.com/) — 最多释放 1000 个字符串
  * [SimpleLocalize](https://simplelocalize.io/) - Free up to 100 translation keys, unlimited strings, unlimited languages, startup deals
  * [Texterify](https://texterify.com/) - 单个用户免费
  * [transifex.com](https://www.transifex.com/) — Free for Open Source
  * [Translation.io](https://translation.io) - Free for Open Source
  * [webtranslateit.com](https://webtranslateit.com/) — Free up to 500 strings
  * [weblate.org](https://weblate.org/) — It's free for libre projects up to 10,000 string source for the free tier, and Unlimited Self-hosted on-premises.
  * [Free PO editor](https://pofile.net/free-po-editor) — 对所有人免费


## Monitoring

  * [Pingmeter.com](https://pingmeter.com/)  - 5 个正常运行时间监视器，间隔 10 分钟. 监控 SSH、HTTP、HTTPS 和任何自定义 TCP 端口.
  * [amixr.io](https://amixr.io/) - Developer-friendly alerting and on-call management with brilliant Slack Integration, API and Terraform. Free phone call, SMS, Telegram, Slack and E-Mail packages.
  * [appdynamics.com](https://www.appdynamics.com/) — 24 小时免费指标，应用程序性能管理代理仅限于一种 Java、一种 .NET、一种 PHP 和一种 Node.js
  * [appneta.com](https://www.appneta.com/) — Free with 1-hour data retention
  * [assertible.com](https://assertible.com)  — 自动化 API 测试和监控. 团队和个人的免费计划.
  * [blackfire.io](https://blackfire.io/)  — Blackfire 是 SaaS 交付的应用程序性能解决方案. 免费黑客计划（仅限 PHP）
  * [checklyhq.com](https://checklyhq.com)  - 面向开发人员的开源 E2E / 综合监控和深度 API 监控. 包含 5 个用户和 50k+ 检查运行的免费计划.
  * [circonus.com](https://www.circonus.com/) — Free for 20 metrics
  * [cloudsploit.com](https://cloudsploit.com)  — AWS 安全和配置监控. 免费：无限制的按需扫描、无限制的用户、无限制的存储帐户. 订阅：自动扫描、API访问等.
  * [datadoghq.com](https://www.datadoghq.com/) — 最多 5 个节点免费
  * [deadmanssnitch.com](https://deadmanssnitch.com/)  — 监控 cron 作业.  1 个免费告密者（监视器），如果您推荐其他人注册，则更多
  * [economize.cloud](https://economize.cloud) — Economize helps demystify cloud infrastructure costs by organizing cloud resources, optimize and report the same. Free for up to $5000 spends on Google Cloud Platform every month.
  * [elastic.co](https://www.elastic.co/solutions/apm)  — 为 JS 开发人员提供即时性能洞察. 免费提供 24 小时数据保留
  * [freeboard.io](https://freeboard.io/) — Free for public projects. Dashboards for your Internet of Things (IoT) projects
  * [freshworks.com](https://www.freshworks.com/website-monitoring/) — 以 1 分钟的间隔监控 50 个 URL，包含 10 个全球位置和 5 个免费的公共状态页面
  * [gitential.com](https://gitential.com)  — 软件开发分析平台. 免费：无限的公共存储库，无限的用户，私人存储库的免费试用. 可用于企业的本地版本.
  * [Grafana Cloud](https://grafana.com/products/cloud/) - Grafana Cloud is a composable observability platform, integrating metrics and logs with Grafana. Free: 3 users, 10 dashboards, 100 alerts, metrics storage in Prometheus and Graphite (10,000 series, 14 days retention), logs storage in Loki (50 GB of logs, 14 days retention)
  * [healthchecks.io](https://healthchecks.io) — Monitor your cron jobs and background tasks. Free for up to 20 checks.
  * [inspector.dev](https://www.inspector.dev) - 不到一分钟即可获得完整的实时监控仪表板，永久免费.
  * [instrumentalapp.com](https://instrumentalapp.com) - Beautiful and easy-to-use application and server monitoring with up to 500 metrics and 3 hours of data visibility for free
  * [keychest.net/speedtest](https://keychest.net/speedtest) - 针对 Digital Ocean 的独立速度测试和 TLS 握手延迟测试
  * [letsmonitor.org](https://letsmonitor.org) - SSL monitoring, free for up to 5 monitors
  * [loader.io](https://loader.io/) — 有限制的免费负载测试工具
  * [meercode.io](https://meercode.io/) — Meercode is the ultimate monitoring dashboard for your CI/CD builds. Free for open-source and 1 private repository.
  * [netdata.cloud](https://www.netdata.cloud/)  — Netdata 是一个开源工具，旨在收集实时指标.快速增长的产品. 也可以在github上找到！
  * [newrelic.com](https://www.newrelic.com)  — 为帮助工程师创建更完美的软件而构建的新 Relic 可观察性平台. 从单体应用到无服务器，您可以检测所有内容，然后分析、排除故障并优化您的整个软件堆栈. 免费套餐提供每月 100GB 的免费数据摄取、1 个免费的完全访问用户和无限的免费基本用户.
  * [nixstats.com](https://nixstats.com) - Free for one server. E-Mail Notifications, public status page, 60 second interval and more.
  * [OnlineOrNot.com](https://onlineornot.com/) - OnlineOrNot is a reliable uptime monitor for both JS-based web apps and websites. 10 uptime checks (for static websites and APIs) with a 5 minute interval, 1 browser check with a 15 minute interval. Free for up to 3 users, alerts via Slack, Discord, and Email.
  * [opsgenie.com](https://www.opsgenie.com/) — Powerful alerting and on-call management for operating always-on services. Free up to 5 users.
  * [paessler.com](https://www.paessler.com/)  — 强大的基础设施和网络监控解决方案，包括警报、强大的可视化功能和基本报告. 释放多达 100 个传感器.
  * [syagent.com](https://syagent.com/) — Non commercial free server monitoring service, alerts and metrics.
  * [pagertree.com](https://pagertree.com/)  - 用于警报和待命管理的简单界面. 最多释放 5 个用户.
  * [pingbreak.com](https://pingbreak.com/) — Modern uptime monitoring service. Check unlimited URLs and get downtime notifications via Discord, Slack or email.
  * [pingpong.one](https://pingpong.one/) — Advanced status page platform with monitoring. Free tier includes one public customizable status page with SSL subdomain. Pro plan is offered to open-source projects and non-profits free of charge.
  * [sematext.com](https://sematext.com/) — Free for 24 hours metrics, unlimited number of servers, 10 custom metrics, 500,000 custom metrics data points, unlimited dashboards, users, etc.
  * [sitemonki.com](https://sitemonki.com/) — Website, domain, Cron & SSL monitoring, 5 monitors in each category for free
  * [skylight.io](https://www.skylight.io/) — 前 100,000 个请求免费（仅限 Rails）
  * [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — 性能监控 API，检查 Ping、DNS 等.
  * [stathat.com](https://www.stathat.com/) — 免费开始使用 10 个统计数据，没有过期
  * [statuscake.com](https://www.statuscake.com/) — Website monitoring, unlimited tests free with limitations
  * [statusgator.com](https://statusgator.com/) — Status page monitoring, 3 monitors free
  * [thousandeyes.com](https://www.thousandeyes.com/) — Network and user experience monitoring. 3 locations and 20 data feeds of major web services free
  * [thundra.io/apm](https://www.thundra.io/apm) — Application monitoring and debugging. Has a free tier up to 250k monthly invocations.
  * [uptimerobot.com](https://uptimerobot.com/) — 网站监控，免费 50 台显示器
  * [uptimetoolbox.com](https://uptimetoolbox.com/) — 免费监控 5 个网站，60 秒间隔，公开状态页.
  * [zenduty.com](https://www.zenduty.com/)  — 用于网络运营、站点可靠性工程和 DevOps 团队的端到端事件管理、警报、待命管理和响应编排平台. 最多 5 位用户免费.
  * [asayer.io](https://asayer.io/pricing.html)  — openreplay 的托管版本，一种开源会话重播（FullStory 和 LogRocket 的替代品）. 每月免费 1k 次会话，保留 14 天
  * [lean20.com](https://lean20.com/product/status/)  - 事件报告的公共状态页面.  100% 免费.
  * [instatus.com](https://instatus.com) - Get a beautiful status page in 10 seconds. Free forever with unlimited subs and unlimited teams.
  * [Squadcast.com](https://squadcast.com) - Squadcast is an end-to-end incident management software that's designed to help you promote SRE best practices. Free forever plan available for upto 10 users.


## Crash and Exception Handling

  * [CatchJS.com](https://catchjs.com/) - JavaScript error tracking with screenshots and click trails. Free for open source projects.
  * [bugsnag.com](https://www.bugsnag.com/) — Free for up to 2,000 errors/month after the initial trial
  * [exceptionless](https://exceptionless.com)  — 实时错误、功能、日志报告等. 每月/1 位用户可免费参加 3k 次活动. 开源且易于自托管，可无限使用.
  * [GlitchTip](https://glitchtip.com/) — Simple, open source error tracking. Compatible with open-source Sentry SDKs. 1000 events per month for free, or can self-host with no limits
  * [honeybadger.io](https://www.honeybadger.io)  - 异常、正常运行时间和 cron 监控. 小型团队和开源项目免费（每月 12,000 个错误）.
  * [rollbar.com](https://rollbar.com/) — Exception and error monitoring, free plan with 5,000 errors/month, unlimited users, 30 days retention
  * [sentry.io](https://sentry.io/) — Sentry tracks app exceptions in real-time, has a small free plan. Free for 5k errors per month/ 1 user, unrestricted use if self-hosted


## Search

  * [algolia.com](https://www.algolia.com/) — Hosted search-as-you-type (instant). Free hacker plan up to 10,000 documents and 100,000 operations. Bigger free plans available for community/Open Source projects
  * [bonsai.io](https://bonsai.io/) — 免费 1 GB 内存和 1 GB 存储空间
  * [searchly.com](http://www.searchly.com/) — Free 2 indices and 20 MB storage
  * [pagedart.com](https://pagedart.com/) - AI search as a service the free tier includes 1000 Documents, 50000 searches. Larger free tiers are possible for worthwhile projects.


## Email

  * [10minutemail](https://10minutemail.com) - Free, temporary email for testing.
  * [AnonAddy](https://anonaddy.com) - Open-source anonymous email forwarding, create unlimited email aliases for free
  * [Antideo](https://www.antideo.com) — 10 API requests per hour for email verification, IP and phone number validation in free tier. No Credit Cards required.
  * [biz.mail.ru](https://biz.mail.ru/) — 5,000 mailboxes with 25 GB each per custom domain with DNS hosting
  * [Bump](https://bump.email/) - Free 10 Bump email addresses, 1 custom domain
  * [Burnermail](https://burnermail.io/) – 免费 5 个 Burner 电子邮件地址、1 个邮箱、7 天邮箱历史记录
  * [Buttondown](https://buttondown.email/)  — 通讯服务. 多达 1,000 名免费订阅者
  * [CloudMailin](https://www.cloudmailin.com/) - Incoming email via HTTP POST and transactional outbound - 10,000 free emails/month
  * [cloudmersive.com](https://www.cloudmersive.com/email-verification-api) — 面向开发人员的电子邮件验证和验证 API，每月 2,000 个免费 API 请求
  * [Contact.do](https://contact.do/) - 链接中的联系表格（联系表格有点） - 完全免费！
  * [debugmail.io](https://debugmail.io/) — 易于开发人员使用的测试邮件服务器
  * [Email Temporanee](https://emailtemporanee.com/)  - 易于使用的免费无限一次性临时电子邮件地址（临时电子邮件）. 自动过期，即使你可以设置它的一天.
  * [elasticemail.com](https://elasticemail.com)  — 每天 100 封免费电子邮件. 通过 API 以 0.09 美元的价格发送 1,000 封电子邮件（即用即付）.
  * [EmailOctopus](https://emailoctopus.com) - Up to 2,500 subscribers and 10,000 emails per month free
  * [Eva](https://eva.pingutil.com)  — 每天使用 REST API 免费验证 500 万封电子邮件. 无需注册.
  * [fakermail.com](https://fakermail.com/) — 用于测试的免费临时电子邮件，存储了最后 100 个电子邮件帐户.
  * [forwardemail.net](https://forwardemail.net) — Free email forwarding for custom domains. Create and forward an unlimited amount of email addresses with your domain name (**note**: You must pay if you use .casa, .cf, .click, .email, .fit, .ga, .gdn, .gq, .loan, .london, .men, .ml, .pl, .rest, .ru, .tk, .top, .work TLDs due to spam)
  * [ImprovMX](https://improvmx.com) – Free email forwarding
  * [inboxkitten.com](https://inboxkitten.com/)  - 免费的临时/一次性电子邮件收件箱，最多可自动删除 3 天的电子邮件. 开源，可以自托管.
  * [inumbo.com](http://inumbo.com/) — 基于 SMTP 的垃圾邮件过滤器，10 位用户免费
  * [kickbox.io](https://kickbox.io/) — 免费验证 100 封电子邮件，提供实时 API
  * [mail.gw](https://mail.gw) — 10 Minute Mail. Free anonymous temporary email without obligations.
  * [mail.tm](https://mail.tm) — Disposable e-mail with user friendly interface. No registration needed.
  * [mailazy.com](https://mailazy.com/) — Mailazy is the only simple transactional email service you’ll need. 15,000 emails/month free forever (500 emails/day sending limit).
  * [mail-tester.com](https://www.mail-tester.com) — Test if email's dns/spf/dkim/dmarc settings are correct, 20 free/month
  * [dkimvalidator.com](https://dkimvalidator.com/) - 测试电子邮件的 dns/spf/dkim/dmarc 设置是否正确，roundsphere.com 提供免费服务
  * [mailboxlayer.com](https://mailboxlayer.com/) — Email validation and verification JSON API for developers. 1,000 free API requests/month
  * [mailcatcher.me](https://mailcatcher.me/) — Catches mail and serves it through a web interface
  * [mailchimp.com](https://mailchimp.com/) — 2,000 subscribers and 12,000 emails/month free
  * [MailerLite.com](https://www.mailerlite.com) — 1,000 名订阅者/月，12,000 封电子邮件/月免费
  * [mailinator.com](https://www.mailinator.com/) — 免费的公共电子邮件系统，您可以在其中使用任何您想要的收件箱
  * [mailjet.com](https://www.mailjet.com/) — 6,000 emails/month free (200 emails daily sending limit)
  * [mailkitchen](https://www.mailkitchen.com/) — Free for life without commitment, 10,000 emails/month, 1,000 emails/day
  * [mailmenot.io](http://mailmenot.io) — 免费的一次性临时电子邮件服务，能够添加多个电子邮件地址
  * [Mailnesia](https://mailnesia.com) - Free temporary/disposable email, which auto visit registration link.
  * [mailsac.com](https://mailsac.com) - Free API for temporary email testing, free public email hosting, outbound capture, email-to-slack/websocket/webhook (1,500 monthly API limit)
  * [Mailtie.com](https://mailtie.com/) - Free Email Forwarding for Your Domain. No registration required. Free Forever.
  * [mailtrap.io](https://mailtrap.io/) — Fake SMTP server for development, free plan with 1 inbox, 50 messages, no team member, 2 emails/second, no forward rules
  * [mailvalidator.io](https://mailvalidator.io/) - Verify 300 emails/month for free, real-time API with bulk processing available
  * [mail7.io](https://www.mail7.io/)  — QA 开发人员的免费临时电子邮件地址. 使用 Web 界面或 API 立即创建电子邮件地址
  * [mohmal.com](https://www.mohmal.com/en) — Disposable temporary email
  * [moosend.com](https://moosend.com/) — Mailing list management service. Free account for 6 months for startups
  * [Outlook.com](https://outlook.live.com/owa/) - Free personal email and calendar
  * [Parsio.io](https://parsio.io) — Free email parser (Forward email, extract the data, send it to your server)
  * [pepipost.com](https://pepipost.com) — 第一个月免费发送 30k 封电子邮件，然后每天免费发送前 100 封电子邮件
  * [phplist.com](https://phplist.com/) — Hosted version allow 300 emails/month free
  * [postmarkapp.com](https://postmarkapp.com/) - 100 封电子邮件/月免费，无限制的 DMARC 每周摘要
  * [QuickEmailVerification](https://quickemailverification.com) — Verify 100 emails daily for free on a free tier along with other free APIs like DEA Detector, DNS Lookup, SPF Detector and more.
  * [Sender](https://www.sender.net) 每月最多 15 000 封电子邮件 - 最多 2 500 名订阅者
  * [sendgrid.com](https://sendgrid.com/) — 每天 100 封电子邮件和 2,000 个免费联系人
  * [sendinblue.com](https://www.sendinblue.com/) — 9,000 emails/month free
  * [sendpulse.com](https://sendpulse.com) — 50 封电子邮件/小时免费，前 12,000 封电子邮件/月免费
  * [socketlabs.com](https://www.socketlabs.com) - 第一个月免费发送 40k 封电子邮件，然后每月免费发送前 2000 封电子邮件
  * [sparkpost.com](https://www.sparkpost.com/) — First 500 emails/month free
  * [Substack](https://substack.com) — Unlimited free newsletter service. Start paying when you charge for it.
  * [Tempmailo](https://tempmailo.com/)  - 无限的免费临时电子邮件地址. 两天后自动过期.
  * [HotTempMail](https://hottempmail.com/) - Unlimited free temp email or disposable temporary email addresses. Autoexpires in one day.
  * [temp-mail.io](https://temp-mail.io) — Free disposable temporary email service with multiple emails at once and forwarding
  * [temp-mail.org](https://temp-mail.org) — Temporary, secure, anonymous, free, disposable email address with REST API for fetching 100 emails from its disposable mailbox per day for free.
  * [testmail.app](https://testmail.app/)  - 使用无限邮箱和 GraphQL API 自动化端到端电子邮件测试.  100 封电子邮件/月永久免费，开源无限免费.
  * [tinyletter.com](https://tinyletter.com/) — 5,000 subscribers/month free
  * [trashmail.com](https://www.trashmail.com) - Free disposable email addresses with forwarding and automatic address expiration
  * [Validator.Pizza](https://www.validator.pizza/) — Free API to detect disposable emails
  * [Verifalia](https://verifalia.com/email-verification-api)  — 带有邮箱确认和一次性电子邮件地址检测器的实时电子邮件验证 API； 每天 25 次免费电子邮件验证.
  * [verimail.io](https://verimail.io/)  — 批量和 API 电子邮件验证服务.  100 次免费验证/月
  * [Yandex.Connect](https://connect.yandex.com/pdd/) — Free email and DNS hosting for up to 1,000 users
  * [yopmail.fr](http://www.yopmail.fr/en/) — Disposable email addresses
  * [Zoho](https://www.zoho.com) — Started as an e-mail provider but now provides a suite of services out of which some of them have free plans. List of services having free plans :
     - [Email](https://zoho.com/mail) Free for 5 users. 5GB/user & 25 MB attachment limit, 1 domain.
     - [Sprints](https://zoho.com/sprints) 5 个用户、5 个项目和 500MB 存储空间免费.
     - [Docs](https://zoho.com/docs)  — 5 位用户免费，具有 1 GB 上传限制和 5 GB 存储空间.  Zoho Office Suite (Writer,Sheets &amp; Show) 与它捆绑在一起.
     - [Projects](https://zoho.com/projects) — Free for 3 users, 2 projects & 10 MB attachment limit. Same plan applies to [Bugtracker](https://zoho.com/bugtracker).
     - [Connect](https://zoho.com/connect) — 25 位用户的团队协作免费，包含 3 个组、3 个自定义应用程序、3 个板、3 个手册、10 个集成以及渠道、活动和论坛.
     - [Meeting](https://zoho.com/meeting) — Meetings with upto 3 meeting participants & 10 Webinar attendees.
     - [Vault](https://zoho.com/vault) — 个人密码管理免费.
     - [Showtime](https://zoho.com/showtime) — Yet another Meeting software for training for a remote session upto 5 attendees.
     - [Notebook](https://zoho.com/notebook) — A free alternative to Evernote.
     - [Wiki](https://zoho.com/wiki) — Free for 3 users with 50 MB storage, unlimited pages, zip backups, RSS & Atom feed, access controls & customisable CSS.
     - [Subscriptions](https://zoho.com/subscriptions) — Recurring Billing management free for 20 customers/subscriptions & 1 user with all the payment hosting done by Zoho themselves. Last 40 subscription metrics are stored
     - [Checkout](https://zoho.com/checkout) — Product Billing management with 3 pages & up to 50 payments.
     - [Desk](https://zoho.com/desk)  — 具有 3 个代理和私人知识库、电子邮件票证的客户支持管理. 与集成 [Assist](https://zoho.com/assist) for 1 remote technician & 5 unattended computers.
     - [Cliq](https://zoho.com/cliq) — Team chat software with 100 GB storage, unlimited users, 100 users per channel & SSO.
     - [Campaigns](https://zoho.com/campaigns)
     - [Forms](https://zoho.com/forms)
     - [Sign](https:/zoho.com/sign)
     - [Surveys](https://zoho.com/surveys)
     - [Bookings](https://zoho.com/bookings)
     - [Analytics](https://zoho.com/analytics)
  * [SimpleLogin](https://simplelogin.io/) – Open source, self-hostable email alias/forwarding solution. Free 5 Aliases, unlimited bandwith, unlimited reply/send. Free for educational staffs (student, researcher, etc).
  * [EmailJS](https://www.emailjs.com/) – This is not a full email server, this is just email client which you can use to send emails right from client send without exposing your credentials, the free tier has: 200 monthly requests, 2 email templates, Requests up to 50Kb, Limited contacts history.



## Font

  * [dafont](https://www.dafont.com/) - 本网站上呈现的字体是其作者的财产，并且是免费软件、共享软件、演示版或公共领域.
  * [Everything Fonts](https://everythingfonts.com/) - Offers multiple tools; @font-face, Units Converter, Font Hinter and Font Submitter.
  * [Font Squirrel](https://www.fontsquirrel.com/) - Freeware fonts that is licensed for commercial work. Hand-selected these typefaces and presenting them in an easy-to-use format.
  * [Google Fonts](https://fonts.google.com/) - 许多免费字体可以通过下载或指向 Google CDN 的链接轻松快速地安装在网站中.
  * [FontGet](https://www.fontget.com/) - Has a variety of fonts available to download and sorted neatly with tags.
  * [Fontshare](https://www.fontshare.com/) - is a free fonts service. It’s a growing collection of professional grade fonts that are 100% free for personal and commercial use.


## Forms

  * [99inbound.com](https://www.99inbound.com/)  - 建立表格并在线分享. 为每次提交获取电子邮件或 Slack 消息. 免费计划有 2 种表格，每月 100 个条目，基本电子邮件和 Slack.
  * [Form.taxi](https://form.taxi/)  — HTML 表单提交的端点. 通过通知、垃圾邮件拦截器和符合 GDPR 的数据处理. 基本使用的免费计划.
  * [Formcake.com](https://formcake.com) - Form backend for devs, free plan allows unlimited forms, 100 submissions, Zapier integration. No libraries or dependencies required.
  * [Formcarry.com](https://formcarry.com) - HTTP POST 表单端点，免费计划允许每月提交 100 次.
  * [formingo.co](https://www.formingo.co/)- Easy HTML forms for static websites, get started for free without registering an account. Free plan allows 500 submissions per month, customizable reply-to email address.
  * [formlets.com](https://formlets.com/) — Online forms, unlimited single page forms/month, 100 submissions/month, email notifications.
  * [formrocket.me](https://www.formrocket.me)  - HTML 表单变得简单，无限制的表单和响应. 附带 Discord 通知等.
  * [formspark.io](https://formspark.io/) -  Form to Email service, free plan allows unlimited forms, 250 submissions per month, support by Customer assistance team.
  * [Formspree.io](https://formspree.io/)  — 使用 HTTP POST 请求发送电子邮件. 免费层级限制为每个表单每月 50 次提交.
  * [Formsubmit.co](https://formsubmit.co/) — Easy form endpoints for your HTML forms. Free Forever. No registration required.
  * [getform.io](https://getform.io/) - Form backend platform for designers and developers, 1 form, 50 submissions, Single file upload, 100MB file storage.
  * [HeroTofu.com](https://herotofu.com/)  - 带有机器人检测和加密存档的表单后端. 通过 UI 将提交转发到电子邮件、Slack 或 Zapier. 使用您自己的前端，无需服务器代码. 免费计划每月提供无限的表格和 100 次提交.
  * [HeyForm.net](https://heyform.net/)  - 拖放在线表单生成器. 免费层可让您创建无限的表单并收集无限的提交. 带有预建模板、反垃圾邮件和 100MB 文件存储.
  * [Hyperforms.app](https://hyperforms.app/) — Create form to email and more in seconds and without backend code. The Personal account gives you up to 50 form submissions per month for free.
  * [Kwes.io](https://kwes.io/) - Feature rich form endpoint. Works great with static sites. Free plan includes up 1 website with up to 50 submissions per month.
  * [Pageclip](https://pageclip.co/) - 免费计划允许一个站点、一个表单、每月 1,000 次提交.
  * [Qualtrics Survey](https://qualtrics.com/free-account)  — 使用这个一流的工具创建专业的表格和调查.  50 多个专家设计的调查模板. 免费帐户限制为 1 个活动调查、100 个回复/调查和 8 种回复类型.
  * [smartforms.dev](https://smartforms.dev/) - 为您的网站提供强大而简单的表单后端，永久免费计划允许每月提交 50 次，250MB 文件存储，Zapier 集成，CSV/JSON 导出，自定义重定向，自定义响应页面，Telegram 和 Slack 机器人，单个电子邮件通知.
  * [staticforms.xyz](https://www.staticforms.xyz/) - Integrate HTML forms easily without any server side code for free. After user submits the form an email will be sent to your registered address with form content.
  * [stepFORM.io](https://stepform.io)  - 测验和表格生成器. 免费计划有 5 个表格，每个表格最多 3 个步骤，每月 50 个回复.
  * [Typeform.com](https://www.typeform.com/) — Include beautifully designed forms on websites.  Free plan allows only 10 fields per form and 100 responses per month.
  * [WaiverStevie.com](https://waiverstevie.com) - Electronic Signature platform with a REST API. Receive notifications with webhooks. Free plan watermarks signed documents, but allows unlimited envelopes + signatures.
  * [Web3Forms](https://web3forms.com)  - 静态和 JAMStack 网站的联系表格，无需编写后端代码. 免费计划允许每月不限表格、不限域和 250 次提交.
  * [WebAsk](https://webask.io) - Survey and Form Builder. Free plan has 3 surveys per account, 100 responses per month, 10 elements per survey.
  * [Wufoo](https://www.wufoo.com/)  - 在网站上使用的快速表格. 免费计划每月有 100 次提交的限制.
  * [formpost.app](https://formpost.app) - Free, unlimited Form to Email service. Setup custom redirect, auto response, webhooks etc for free.


## CDN and Protection

  * [Arvan Cloud](https://arvancloud.com/)  — 提供云相关服务（CDN、Cloud DNS、PaaS、安全等）. 免费计划提供：
     - 带有免费 SSL 的 CDN.  50 GB 流量 + 100 万个 HTTP(S) 请求.
    - Free Cloud DNS for unlimited domains.
    - Free Cloud Security with Basic DDoS Protection + 5 Firewall Rules.
    - 具有 10 GB 存储 + 50 GB 流量的免费 VoD（视频点播）平台.
  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) — CDN for bootstrap, bootswatch and fontawesome.io
  * [cdnjs.com](https://cdnjs.com/) — Simple. Fast. Reliable. Content delivery at its finest. cdnjs is a free and open-source CDN service trusted by over 11% of all websites, powered by Cloudflare.
  * [Cloudflare](https://www.cloudflare.com/)
    * CDN along with free SSL
    * Free DNS for unlimited number of domains
    * Firewall rules and pagerules
    * Analytics
    * [Cloudflare Pages](https://pages.cloudflare.com/)  — 免费网络托管（JAMstack 平台），供前端开发人员协作和部署网站. 一次构建 1 个，每月 500 个构建，无限站点，无限请求，无限带宽.
    * [Cloudflare Workers](https://workers.cloudflare.com/)  — 在 Cloudflare 的全球网络上免费部署无服务器代码. 每天有 100,000 个使用 workers.dev 子域的免费请求.
    * [Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/run-tunnel/trycloudflare) — Create a tunnel from your server to a publically accessible, randomly-generated trycloudflare.com domain. No account required.
  * [Combinatronics](https://combinatronics.com/) - Convert your Github hosted assets (images, CSS, JS, etc.) into CDN assets. Can even render HTML files, for [example from this repo](https://combinatronics.com/ripienaar/free-for-dev/master/index.html). Similar to rawgit.com and raw.githack.com.
  * [ddos-guard.net](https://ddos-guard.net/store/web) — 免费 CDN、DDoS 保护和 SSL 证书
  * [developers.google.com](https://developers.google.com/speed/libraries/) — Google 托管库是最流行的开源 JavaScript 库的内容分发网络
  * [GraphCDN](https://graphcdn.io/)  - 扩展、检查和保护您的 GraphQL API. 每月 500 万次免费请求.
  * [jare.io](http://www.jare.io)  — 图像 CDN. 使用 AWS CloudFront
  * [jsdelivr.com](https://www.jsdelivr.com/)  — 一个免费、快速、可靠的开源 CDN. 支持 npm、GitHub、WordPress、Deno 等.
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — The Microsoft Ajax CDN hosts popular third-party JavaScript libraries such as jQuery and enables you to easily add them to your Web application
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) — Free DDoS protection and SSL certificate
  * [PageCDN.com](https://pagecdn.com/) - Offers free Public CDN for everyone, and free Private CDN for opensource / nonprofits.
  * [Skypack](https://www.skypack.dev/)  — 100% 原生 ES 模块 JavaScript CDN. 每个域每月 100 万次请求免费.
  * [raw.githack.com](https://raw.githack.com/) — A modern replacement of **rawgit.com** which simply hosts file using Cloudflare
  * [section.io](https://www.section.io/)  — 一种启动和管理完整 Varnish Cache 解决方案的简单方法. 据说一个网站永久免费
  * [speeder.io](https://speeder.io/) — Uses KeyCDN. Automatic image optimization and free CDN boost. Free and does not require any server changes
  * [statically.io](https://statically.io/) — Git repos（GitHub、GitLab、Bitbucket）、WordPress 相关资产和图像的 CDN
  * [toranproxy.com](https://toranproxy.com/)  — Packagist 和 GitHub 的代理. 永远不会失败的CD. 免费供个人使用，1个开发者，不支持
  * [UNPKG](https://unpkg.com/) — npm 上所有内容的 CDN
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — Free DDoS protection


## PaaS

  * [anvil.works](https://anvil.works) - Web app development with nothing but Python. Free tier with unlimited apps.
  * [appharbor.com](https://appharbor.com/) — A .Net PaaS that provides 1 free worker
  * [configure.it](https://www.configure.it/) — Mobile app development platform, free for 2 projects, limited features but no resource limits
  * [codenameone.com](https://www.codenameone.com/) — Open source, cross platform, mobile app development toolchain for Java/Kotlin developers. Free for commercial use with unlimited number of projects
  * [Deta](https://www.deta.sh)  – 免费部署无限数量的 Node.js 和 Python 应用程序. 包括免费的数据库、身份验证和电子邮件.
  * [encore.dev](https://encore.dev/) — Backend framework using static analysis to provide automatic infrastructure, boilerplate free code, and more. Includes free cloud hosting for hobby projects.
  * [gigalixir.com](https://gigalixir.com/) - Gigalixir 为 Elixir/Phoenix 应用程序提供 1 个永不休眠的免费实例，以及限制为 2 个连接、10、000 行且无备份的免费层级 PostgreSQL 数据库.
  * [Glitch](https://glitch.com/)  — 具有代码共享和实时协作等功能的免费公共托管. 免费计划有 1000 小时/月的限制.
  * [Heroku](https://www.heroku.com/) — Host your apps in the cloud, free for single process apps
  * [Krucible](https://usekrucible.com)  — Krucible 是一个用于创建用于测试和开发的 Kubernetes 集群的平台. 免费套餐帐户每月提供 25 个集群小时.
  * [Mendix](https://www.mendix.com/)  — 企业快速应用程序开发、支持无限用户的无限数量的免费沙盒环境、每个应用程序 0.5 GB 存储和 1 GB RAM. 免费层也允许使用 Studio 和 Studio Pro IDE.
  * [m3o.com](https://m3o.com) - A cloud platform for API services development. M3O is a fully managed Micro as a Service offering focusing on Go microservices development in the Cloud. Free tier provides enough to run 5 services and collaborate with others.
  * [Okteto Cloud](https://okteto.com)  - 专为远程开发设计的托管 Kubernetes 服务. 免费的开发者账户有 5 个 Kubernetes 命名空间，3Gi/pod 最多 8Gi/命名空间，1CPU/pod 最多 4CPU/命名空间和 5GB 磁盘空间. 应用程序在 24 小时不活动后进入睡眠状态.
  * [opeNode](https://openode.io)  — 用于开源项目的免费 Node.js 托管.  100 GB 带宽/月，100 MB 内存和 1000 MB 存储空间. 使用 CLI 或现有 Git 存储库进行部署.
  * [outsystems.com](https://www.outsystems.com/) — 用于本地或云的企业 Web 开发 PaaS，免费的“个人环境”产品允许无限的代码和高达 1 GB 的数据库
  * [pipedream.com](https://pipedream.com)  - 为开发人员构建的集成平台. 基于任何触发器开发任何工作流. 工作流是可以运行的代码 [for free](https://docs.pipedream.com/pricing/). No server or cloud resources to manage.
  * [pythonanywhere.com](https://www.pythonanywhere.com/) — Cloud Python app hosting. Beginner account is free, 1 Python web application at your-username.pythonanywhere.com domain, 512 MB private file storage, one MySQL database
  * [scn.sap.com](https://scn.sap.com/docs/DOC-56411)  — SAP 的内存平台即服务产品. 免费的开发者帐户附带 1 GB 结构化、1 GB 非结构化、1 GB Git 数据，并允许您运行 HTML5、Java 和 HANA XS 应用程序
  * [Serverless Cloud](https://www.serverless.com/cloud)  - 无服务器云让您可以使用基础架构 _from_ 代码方法（无 yaml，无基础架构配置）构建无服务器 API、数据库和存储. 该产品由 Serverless Inc. 提供，目前处于公共预览阶段. 
  * [fly.io](https://fly.io/)  - Fly 是一个面向需要在全球范围内运行的应用程序的平台. 它在靠近用户的地方运行您的代码，并在您的应用程序最繁忙的城市扩展计算. 编写您的代码，将其打包成 Docker 映像，将其部署到 Fly 的平台，并让其完成所有工作以保持您的应用程序快速运行. 辅助项目免费，每月 10 美元的服务信用额度自动适用于任何付费服务. 而且，如果您运行非常小的虚拟机，那么积分将大有帮助.
  * [Divio](https://www.divio.com/) - A platform to manage cloud application deploying only using Docker. Available free subscription for development projects, Requires card and no custom domain support.  
  * [Koyeb](https://www.koyeb.com) - Koyeb is a developer-friendly serverless platform to deploy apps globally. Seamlessly run Docker containers, web apps, and APIs with git-based deployment, native autoscaling, a global edge network, and built-in service mesh and discovery. Koyeb provides two nano services to run your apps with its forever-free tier and also sponsors open-source projects with free resources.
  * [Railway](https://railway.app)  - 铁路是一个基础架构平台，您可以在其中配置基础架构，在本地使用该基础架构进行开发，然后部署到云端.  1GB 磁盘，512 MB RAM，每月限用 5 美元免费提供.
  * [Napkin](https://www.napkin.io/) - 具有 1Gb 内存的 FaaS，默认超时 15 秒和每月 1,000,000 次免费 API 调用.
  * [Meteor Cloud](https://www.meteor.com/cloud) — Galaxy hosting. Meteor's own platform-as-a-service for Meteor apps which includes a free MongoDB Shared Hosting and automatic SSL.
  * [Northflank](https://northflank.com) — Build and deploy microservices, jobs and managed databases with a powerful UI, API & CLI. Seamlessly scale containers from version control and external Docker registries. Free tier includes 2 services, 2 cron jobs and 1 database.


## BaaS

  * [ably.com](https://www.ably.com)  - 用于实时消息传递、推送通知和事件驱动 API 创建的 API. 免费计划有 300 万条消息/月，100 个并发连接，100 个并发通道.
  * [back4app.com](https://www.back4app.com) - Back4App is an easy-to-use, flexible and scalable backend based on Parse Platform.
  * [backendless.com](https://backendless.com/) — 移动和 Web Baas，提供 1 GB 的免费文件存储空间，每月推送通知 50000 个，表中包含 1000 个数据对象。
  * [BMC Developer Program](https://developers.bmc.com/site/global/bmc_helix_platform/program/overview/index.gsp) — The BMC Developer Program provides documentation and resources to build and deploy digital innovations for your enterprise. Access to a comprehensive, personal sandbox which includes the platform, SDK, and a library of components that can be used to build and tailor apps.
  * [darklang.com](https://darklang.com/)  - 托管语言与编辑器和基础设施相结合.  Beta 期间免费，Beta 后计划提供慷慨的免费套餐.
  * [Firebase](https://firebase.com) — Firebase helps you build and run successful apps. Free Spark Plan offers Authentication, Hosting, Firebase ML , Realtime Database,Cloud Storage,Testlab. A/B Testing, Analytics, App Distribution, App Indexing, Cloud Messaging (FCM), Crashlytics, Dynamic Links, In-App Messaging, Performance Monitoring, Predictions, and Remote Config are always-free.
  * [Flutter Flow](https://flutterflow.io) — Build your Flutter App UI without writing a single line of code. Also has a Firebase integration. Free plan includes full access to UI Builder and Free templates.
  * [getstream.io](https://getstream.io/) — 在几小时而不是几周内构建可扩展的新闻源、活动流、聊天和消息传递
  * [hasura.io](https://hasura.io/)  — Hasura 可将您现有的数据库扩展至任何托管位置，并提供即时 GraphQL API，可安全访问 Web、移动和数据集成工作负载. 免费获得 1GB/月的数据直通.
  * [iron.io](https://www.iron.io/) — Async task processing (like AWS Lambda) with free tier and 1-month free trial
  * [netlicensing.io](https://netlicensing.io) - A cost-effective and integrated Licensing-as-a-Service (LaaS) solution for your software on any platform from Desktop to IoT and SaaS. Basic Plan for *FREE* while you are a student.
  * [nhost.io](https://nhost.io) - Serverless backend for web and mobile apps. Free plan includes: PostgreSQL, GraphQL (Hasura), Authentication, Storage, and Serverless Functions.
  * [onesignal.com](https://onesignal.com/) — 无限制的免费推送通知
  * [paraio.com](https://paraio.com) — Backend service API with flexible authentication, full-text search and caching. Free for 1 app, 1GB app data.
  * [posthook.io](https://posthook.io/) — Job Scheduling Service. Allows you to schedule requests for specific times. 500 scheduled requests/month free.
  * [progress.com](https://www.progress.com/kinvey) — Mobile backend, starter plan has unlimited requests/second, with 1 GB of data storage. Enterprise application support
  * [pubnub.com](https://www.pubnub.com/) — Free push notifications for up to 1 million messages/month and 100 active daily devices
  * [pushbots.com](https://pushbots.com/) — Push notification service. Free for up to 1.5 million pushes/month
  * [pushcrew.com](https://pushcrew.com/)  — 推送通知服务. 多达 2000 个订阅者的无限通知
  * [pusher.com](https://pusher.com/beams) — Free, unlimited push notifications for 2000 monthly active users. A single API for iOS and Android devices.
  * [pushtechnology.com](https://www.pushtechnology.com/) — Real-time Messaging for browsers, smartphones and everyone. 100 concurrent connections. Free 10 GB data/month
  * [quickblox.com](https://quickblox.com/) — 用于即时消息、视频和语音通话以及推送通知的通信后端
  * [restspace.io](https://restspace.io/) - 为服务器配置身份验证、数据、文件、电子邮件 API、模板等服务，然后组合成管道并转换数据.
  * [Salesforce Developer Program](https://developer.salesforce.com/signup)  — 使用拖放工具快速构建应用程序. 通过点击自定义您的数据模型. 使用 Apex 代码更进一步. 使用强大的 API 与任何东西集成. 保持企业级安全保护. 通过点击或任何领先的 Web 框架自定义 UI. 免费开发者计划可让您访问完整的闪电平台.
  * [ServiceNow Developer Program](https://developer.servicenow.com/)  — 快速构建、测试和部署应用程序，使您的组织更好地工作. 免费实例和访问早期预览.
  * [simperium.com](https://simperium.com/)  — 即时自动移动数据，多平台，无限发送和存储结构化数据，最大.  2,500 个用户/月
  * [stackstorm.com](https://stackstorm.com/) — 应用程序、服务和工作流的事件驱动自动化，免费无流、访问控制、LDAP...
  * [streamdata.io](https://streamdata.io/) — Turns any REST API into an event-driven streaming API. Free plan up to 1 million messages and 10 concurrent connections.
  * [Supabase](https://supabase.io)  — 构建后端的开源 Firebase 替代方案. 免费计划提供身份验证、实时数据库和对象存储.
  * [tyk.io](https://tyk.io/) — API management with authentication, quotas, monitoring and analytics. Free cloud offering
  * [zapier.com](https://zapier.com/)  — 连接您使用的应用程序，以自动执行任务.  5 zaps，每 15 分钟和 100 个任务/月
  * [LeanCloud](https://leancloud.app/)  — 移动后端.  1GB 数据存储、256MB 实例、3K API 请求/天、10K 推送/天免费.  （API 与 Parse Platform 非常相似）
  * [Liteflow](https://liteflow.com/) - 构建的低代码开发工具包可帮助您专注于应用程序的真正价值.
  * [BudiBase](https://budibase.com/)  - Budibase 是一个开源低代码平台，可在几分钟内创建内部应用程序. 支持 PostgreSQL、MySQL、MSSQL、MongoDB、Rest API、Docker、K8s 


## Web Hosting

  * [Alwaysdata](https://www.alwaysdata.com/)  — 100 MB 免费网络托管，支持 MySQL、PostgreSQL、CouchDB、MongoDB、PHP、Python、Ruby、Node.js、Elixir、Java、Deno、自定义网络服务器，可通过 FTP、WebDAV 和 SSH 访问； 包括邮箱、邮件列表和应用程序安装程序.
  * [Awardspace.com](https://www.awardspace.com) — Free web hosting + a free short domain, PHP, MySQL, App Installer, Email Sending & No Ads.
  * [Bubble](https://bubble.io/) — Visual programming to build web and mobile apps without code, free with Bubble branding.
  * [cloudno.de](https://cloudno.de/) — Free cloud hosting for Node.js apps.
  * [Deploy Now](https://deploynow.space)  — 更智能地部署. 部署更快. 立即部署.  - 从您的 GitHub 存储库免费部署多达 3 个 Web 项目.
  * [Drive To Web](https://drv.tw) — Host directly to the web from Google Drive & OneDrive. Static sites only. Free forever. One site per Google/Microsoft account.
  * [Fenix Web Server](https://preview.fenixwebserver.com) - A developer desktop app for hosting sites locally and sharing them publically (in realtime). Work however you like, using its beautiful user interface, API, and/or CLI.
  * [Free Hosting](http://freehostingnoads.net/) — 使用 PHP 5、Perl、CGI、MySQL、FTP、文件管理器、POP 电子邮件、免费子域、免费域托管、DNS 区域编辑器、网站统计信息、免费在线支持和许多其他功能不提供的免费托管其他免费主机.
  * [Freehostia](https://www.freehostia.com)  — FreeHostia 提供免费托管服务，包括. 业界最佳的控制面板和 50 多个免费应用程序的一键安装. 即时设置. 没有强制广告.
  * [hostman.com](https://hostman.com) — 从您的 GitHub 存储库免费部署多达 3 个静态站点.
  * [Neocities](https://neocities.org) — Static, 1 GB free storage with 200 GB Bandwidth.
  * [Netlify](https://www.netlify.com/) — 免费构建、部署和托管静态站点/应用程序，提供 100 GB 数据和 100 GB/月带宽.
  * [Layer0](https://layer0.co/) 在全球 CDN 上部署快速动态 Jamstack 网站 [Limelight](https://www.limelight.com/) 免费提供 100GB/月带宽和 3 个环境.
  * [pantheon.io](https://pantheon.io/)  — Drupal 和 WordPress 托管、自动化 DevOps 和可扩展的基础架构. 开发商和代理商免费
  * [readthedocs.org](https://readthedocs.org/) — Free documentation hosting with versioning, PDF generation and more
  * [render.com](https://render.com) — 统一云，使用免费 SSL、全球 CDN、专用网络、从 Git 自动部署以及完全免费的 Web 服务、数据库和静态网页计划来构建和运行应用程序和站点.
  * [SourceForge](https://sourceforge.net/) — Find, Create and Publish Open Source software for free
  * [Stormkit](https://stormkit.io/)  — 将构建、部署和托管与 JAMStack 或 Node.JS 应用程序的 git 流无缝集成. 每月免费 50 GB 带宽和 1000 万个请求，包括免费 SSL.
  * [surge.sh](https://surge.sh/)  — 面向前端开发人员的静态 Web 发布. 具有自定义域支持的无限站点
  * [tilda.cc](https://tilda.cc/) — One site, 50 pages, 50 MB storage, only the main pre-defined blocks among 170+ available, no fonts, no favicon and no custom domain
  * [txti.es](https://txti.es/) — 使用 Markdown 快速创建网页.
  * [Vercel](https://vercel.com/)  — 每次执行“git push”时，使用免费的 SSL、全球 CDN 和唯一的预览 URL 构建、部署和托管 Web 应用程序. 非常适合 Next.js 和其他静态站点生成器.
  * [Versoly](https://versoly.com/) — SaaS focussed website builder - unlimited websites, 70+ blocks, 5 templates, custom CSS, favicon, SEO and forms. No custom domain.
  * [Qovery](https://www.qovery.com) — Qovery is the simplest way to deploy your full-stack apps on AWS, GCP and Azure. It is free web hosting for developers with Database, SSL, a global CDN, and auto deploys from Git.
  * [Qoddi](https://qoddi.com)  - 类似于 Heroku 的 PaaS 服务，具有以开发人员为中心的方法和全包功能. 静态资产、登台和开发人员应用程序的免费套餐.
  * [FreeFlarum](https://freeflarum.com/) - 社区支持的免费 Flarum 托管，最多可容纳 250 个用户（捐赠以从页脚中删除水印）.


## DNS
  * [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) - Free public DNS Resolver which is fast and secure (encrypt your DNS query), provided by CloudFlare. Useful to bypass your internet provider's DNS blocking, prevent DNS query spying, and [to block adult & malware content](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families) . 也可以使用 [via API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests). Note: Just a DNS resolver, not a DNS hoster.
  * [1984.is](https://www.1984.is/product/freedns/) — Free DNS service with API, and lots of other free DNS features included.
  * [biz.mail.ru](https://biz.mail.ru) — 最多可容纳 5,000 名用户的免费电子邮件和 DNS 托管
  * [cloudns.net](https://www.cloudns.net/) — 免费 DNS 托管最多 1 个包含 50 条记录的域
  * [dns.he.net](https://dns.he.net/) — Free DNS hosting service with Dynamic DNS Support
  * [dnspod.com](https://www.dnspod.com/) — Free DNS hosting.
  * [duckdns.org](https://www.duckdns.org/)  — 免费 DDNS，免费套餐最多包含 5 个域. 带有各种设置的配置指南.
  * [dynu.com](https://www.dynu.com/) — Free dynamic DNS service
  * [fosshost.org](https://fosshost.org/) - Free open source hosting VPS, web, storage and mirror hosting
  * [freedns.afraid.org](https://freedns.afraid.org/)  — 免费 DNS 托管. 还提供基于众多公众用户的免费子域 [contributed domains](https://freedns.afraid.org/domain/registry/) . 注册后从“子域”菜单中获取免费子域.
  * [luadns.com](https://www.luadns.com/) — 免费 DNS 托管，3 个域，所有功能都有合理的限制
  * [namecheap.com](https://www.namecheap.com/domains/freedns/) — Free DNS. No limit on number of domains
  * [nextdns.io](https://nextdns.io) - 基于 DNS 的防火墙，每月 30 万次免费查询
  * [noip](https://www.noip.com/) — 动态 dns 服务，最多允许 3 个免费主机名，每 30 天确认一次
  * [ns1.com](https://ns1.com/) — Data Driven DNS, automatic traffic management, 500k free queries
  * [nsupdate.info](https://www.nsupdate.info/) — Free and open-source Dynamic DNS service
  * [pointhq.com](https://pointhq.com/developer) — Free DNS hosting on Heroku.
  * [selectel.com](https://selectel.com/services/dns/) — Free DNS hosting with unlimited records, anycast
  * [web.gratisdns.dk](https://web.gratisdns.dk/domaener/dns/) — Free DNS hosting.
  * [Yandex.Connect](https://connect.yandex.com/pdd/) — Free email and DNS hosting for up to 1,000 users
  * [zilore.com](https://zilore.com/en/dns) — Free DNS hosting.
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) — 具有动态 DNS 支持的免费 DNS 托管.
  * [zonewatcher.com](https://zonewatcher.com)  — 自动备份和 DNS 更改监控.  1 个免费域名
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – Free DNS hosting by Huawei
  * [Hetzner](https://www.hetzner.com/dns-console) – Hetzner 提供的免费 DNS 托管，支持 API
  * [Glauca](https://docs.glauca.digital/hexdns/) – 最多 3 个域的免费 DNS 托管和 DNSSEC 支持


## IaaS

  * [filebase.com](https://filebase.com/) - S3 Compatible Object Storage Powered by Blockchain. 5 GB free storage for unlimited duration.
  * [backblaze.com](https://www.backblaze.com/b2/)  — Backblaze B2 云存储. 无限时间的免费 10 GB（类似 Amazon S3）对象存储
  * [scaleway.com](https://www.scaleway.com/en/object-storage/) — S3-Compatible Object Storage. Free 75 GB storage and external outgoing traffic
  * [terraform.io](https://www.terraform.io/)  — Terraform 云. 免费远程状态管理和团队协作，最多可容纳 5 个用户.


## DBaaS

   * [airtable.com](https://airtable.com/) — 看起来像一个电子表格，但它是一个关系数据库、无限的基数、1,200 行/基数和 1,000 个 API 请求/月
   * [Astra](https://www.datastax.com/products/datastax-astra/) — 云原生 Cassandra 即服务 [80GB free tier](https://www.datastax.com/products/datastax-astra/pricing)
   * [bit.io](https://bit.io) — PostgreSQL managed database service. Unlimited repos, 10GB storage, 10M queried rows/month.
   * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ as a Service, up to 1M messages/month and 20 connections free
   * [elephantsql.com](https://www.elephantsql.com/) — PostgreSQL 即服务，20 MB 免费
   * [FaunaDB](https://fauna.com/) — Serverless cloud database, with native GraphQL, multi-model access and daily free tiers up to 100 MB
   * [HarperDb](https://harperdb.io/) — Serverless cloud database, with dynamic schema based on JSON, 3000 IOPS with 1GB storage
   * [heroku.com](https://www.heroku.com/) — PostgreSQL 即服务，最多 10,000 行和 20 个免费连接（作为“插件”提供，但可以附加到其他空的应用程序并从外部访问）
   * [Upstash](https://upstash.com/) — 无服务器 Redis，每天最多可处理 10,000 个请求，最大数据库大小为 256MB，并发连接数为 20
   * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — free tier gives 512 MB
   * [redsmin.com](https://www.redsmin.com/) — Online real-time monitoring and administration service for Redis, Monitoring for 1 Redis instance free
   * [redislabs](https://redislabs.com/try-free/) - Free 30Mb redis instance
   * [MemCachier](https://www.memcachier.com/)  — 托管 Memcache 服务. 免费提供高达 25MB 的空间、1 个代理服务器和基本分析
   * [scalingo.com](https://scalingo.com/) — Primarily a PaaS but offers a 128MB to 192MB free tier of MySQL, PostgreSQL or MongoDB
   * [SeaTable](https://seatable.io/) — Flexible, Spreadsheet-like Database built by Seafile team. unlimited tables, 2,000 lines, 1-month versioning, up to 25 team members.
   * [skyvia.com](https://skyvia.com/) — 云数据平台，提供免费套餐，所有计划在测试阶段完全免费
   * [StackBy](https://stackby.com/)  — 一种工具，将电子表格的灵活性、数据库的强大功能以及与您最喜欢的业务应用程序的内置集成结合在一起. 免费计划包括无限用户、10 个堆栈、每个堆栈 2GB 附件.
   * [InfluxDB](https://www.influxdata.com/) — Timeseries database, free up to 3MB/5 minutes writes, 30MB/5 minutes reads and 10,000 cardinalities series
   * [Quickmetrics](https://www.quickmetrics.io/) — 包含仪表板的时间序列数据库，每天最多释放 10,000 个事件和总共 5 个指标.
   * [restdb.io](https://restdb.io/)  - 快速简单的 NoSQL 云数据库服务. 使用 restdb.io，您可以获得模式、关系、自动 REST API（带有类似 MongoDB 的查询）和用于处理数据的高效多用户管理 UI. 免费计划每秒允许 3 个用户、2500 条记录和 1 个 API 请求.
   * [cockroachlabs.com](https://www.cockroachlabs.com/free-tier/) — Free CockroachDB up to 5GB and 1vCPU (limited [request units](https://www.cockroachlabs.com/docs/cockroachcloud/serverless-faqs.html#what-are-the-usage-limits-of-cockroachdb-serverless-beta))
   * [Neo4j Aura](https://neo4j.com/cloud/aura/)  — 具有 Cypher 查询语言和 REST API 的托管原生 Graph DBMS/分析平台. 图大小限制（50k 节点，175k 关系）.
   * [Dgraph Cloud](https://cloud.dgraph.io/pricing?type=free) — Managed native Graph DBMS with a GraphQL API. Limited to 1 MB data transfer per day.
   * [TigerGraph Cloud](https://www.tigergraph.com/cloud/)  — 使用类似 SQL 的图形查询语言和 REST API 的托管原生图形 DBMS/分析平台.  AWS（4 个 vCPU，7.5 GB 内存，50 GB 磁盘）或 GCP（2 个 vCPU，8 GB 内存，128 GB 磁盘）上的 1 个 TG.Free 实例. 免费实例在闲置 1 小时后休眠.
   * [Macrometa](https://www.macrometa.com/)  - 用于构建地理分布式和实时应用程序的 noSQL 数据库、Pub/Sub、事件处理和无服务器边缘计算平台. 免费开发帐户可访问 10,000 次操作/天和 200MB 存储.
   * [Planetscale](https://planetscale.com/) - PlanetScale is a MySQL compatible, serverless database platform powered by Vitess, 3 databases for free with 10GB storage, 100 Million rows read/mo per database, and 10 Million rows written/mo per database.
   * [YugabyteDB](http://cloud.yugabyte.com)  - YugabyteDB 是一个与 PostgresSQL 兼容的分布式 SQL 数据库. 云免费层是 2 个 vCPU、4GB RAM、10GB 磁盘.


## Tunneling, WebRTC, Web Socket Servers and Other Routers

   * [conveyor.cloud](https://conveyor.cloud/) — Visual Studio 扩展，用于将 IIS Express 公开到本地网络或通过隧道到公共 URL.
   * [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi 是一项托管 VPN 服务，可让您安全地将类似 LAN 的网络扩展到分布式团队，免费计划允许最多 5 人的无限网络
   * [localhost.run](https://localhost.run/) — Expose locally running servers over a tunnel to a public URL.
   * [localtunnel](https://theboroer.github.io/localtunnel-www/) — Expose locally running servers over a tunnel to a public URL. Free hosted version, and [open source](https://github.com/localtunnel/localtunnel).
   * [ngrok.com](https://ngrok.com/) — Expose locally running servers over a tunnel to a public URL.
   * [Radmin VPN](https://www.radmin-vpn.com/)  — 通过启用类似 LAN 的网络的 VPN 将多台计算机连接在一起. 无限同行.  （Hamachi 替代品）
   * [segment.com](https://segment.com/)  — 将事件翻译和路由到其他第三方服务的集线器.  100,000 个事件/月免费
   * [STUN](https://en.wikipedia.org/wiki/STUN) — Session Traversal of User Datagram Protocol [UDP] Through Network Address Translators [NATs])
     * Google STUN — [https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302](https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302)
     * Twilio STUN — [https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp](https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp)
   * [Tailscale](https://tailscale.com/) — Zero config VPN, using the open source WireGuard protocol. Installs on MacOS, iOS, Windows, Linux, and Android devices. Free plan for personal use with 20 devices.
   * [webhookrelay.com](https://webhookrelay.com) <i>— Manage, debug, fan-out and proxy all your webhooks to public or internal (ie: localhost) destinations.</i> <b>— 管理、调试、扇出和代理所有 webhook 到公共或内部（即：localhost）目的地。</b> <i>Also, expose servers running in a private network over a tunnel by getting a public HTTP endpoint (`https://yoursubdomain.webrelay.io &lt;----&gt; http://localhost:8080`).</i><b>此外，通过获取公共 HTTP 端点（`https://yoursubdomain.webrelay.io &lt;----&gt; http://localhost:8080`），通过隧道公开在专用网络中运行的服务器。</b>
   * [Xirsys](https://www.xirsys.com) — Global network of STUN / TURN servers with a generous free tier.
   * [ZeroTier](https://www.zerotier.com) — FOSS managed virtual Ethernet as a service. Unlimited end-to-end encrypted networks of 100 clients on free plan. Clients for desktop/mobile/NA; web interface for configuration of custom routing rules and approval of new client nodes on private networks.


## Issue Tracking and Project Management

   * [acunote.com](https://www.acunote.com/) — 最多 5 名团队成员的免费项目管理和 SCRUM 软件
   * [asana.com](https://asana.com/) — 与合作者的私人项目免费
   * [Backlog](https://backlog.com)  — 您的团队在一个平台上发布伟大项目所需的一切. 免费计划提供 1 个具有 10 个用户和 100MB 存储空间的项目.
   * [Basecamp](https://basecamp.com/personal)  - 待办事项列表、里程碑管理、类似论坛的消息传递、文件共享和时间跟踪. 最多 3 个项目、20 个用户和 1GB 的存储空间.
   * [bitrix24.com](https://www.bitrix24.com/) — 免费的内网和项目管理工具
   * [cacoo.com](https://cacoo.com/) — Online diagrams in real-time: flowchart, UML, network. Free max. 15 users/diagram, 25 sheets
   * [Chpokify](https://chpokify.com/) — Teams based Planning Poker that saves time of sprint estimation. Free up to 5 users, free Jira integrations, unlimited video calls, unlimited teams, unlimited sessions.
   * [clickup.com](https://clickup.com/) — Project management. Free, premium version with cloud storage. Mobile applications and Git integrations available
   * [Cloudcraft](https://cloudcraft.co/) — 使用 Cloudcraft 可视化设计器在几分钟内设计出专业的架构图，针对 AWS 进行了优化，智能组件也显示实时数据.
   * [Codegiant](https://codegiant.io)  — 使用存储库托管和 CI/CD 进行项目管理. 免费计划提供无限的存储库、项目和文档，有 5 名团队成员. 每月 500 CI/CD 分钟. 每月 30000 分钟无服务器代码运行时间.1GB 存储库存储.
   * [Confluence](https://www.atlassian.com/software/confluence)  - Atlassian 的内容协作工具，用于帮助团队高效协作和共享知识. 免费计划最多 10 个用户.
   * [contriber.com](https://www.contriber.com/) — 可定制的项目管理平台，免费入门计划，5 个工作区
   * [draw.io](https://www.draw.io/) — Online diagrams stored locally, in Google Drive, OneDrive or Dropbox. Free for all features and storage levels
   * [freedcamp.com](https://freedcamp.com/)  - 任务、讨论、里程碑、时间跟踪、日历、文件和密码管理器. 免费计划，无限项目、用户和文件存储.
   * [easyretro.io](https://www.easyretro.io/) — 免费简单直观的 sprint 回顾工具
   * [GForge](https://gforge.com)  — 用于具有自建和 SaaS 选项的复杂项目的项目管理和问题跟踪工具集.  SaaS 免费计划为前 5 名用户免费提供开源项目.
   * [gleek.io](https://www.gleek.io) — Free description-to-diagrams tool for developers. Create informal, UML class, object, or entity-relationship diagrams using your keyword.
   * [gliffy.com](https://www.gliffy.com/) — Online diagrams: flowchart, UML, wireframe,... Also plugins for Jira and Confluence. 5 diagrams and 2 MB free
   * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector)  - GraphQL Inspector 输出两个 GraphQL 模式之间的更改列表. 每个更改都被精确解释并标记为破坏性、非破坏性或危险性.
   * [huboard.com](https://huboard.com/) — Instant project management for your GitHub issues, free for Open Source
   * [Hygger](https://hygger.io) — Project management platform. Free plan offers unlimited users,projects & boards with 100 MB Storage.
   * [Instabug](https://instabug.com)  — 适用于移动应用的全面错误报告和应用内反馈 SDK. 免费计划最多 1 个应用程序和 1 个成员.
   * [Ilograph](https://www.ilograph.com/)  — interactive diagrams that allow users to see their infrastructure from multiple perspectives and levels of detail. Diagrams can be expressed in code. Free tier has unlimited private diagrams with up to 3 viewers.
   * [Issue Embed](https://issueembed.dev/)  - 用于网站直接进入您的 Github 问题的错误报告工具. 个人存储库的免费计划，每月最多 500 个问题和 10,000 个页面浏览量/月.
   * [Jira](https://www.atlassian.com/software/jira)  — 在许多企业环境中使用的高级软件开发项目管理工具. 免费计划最多 10 个用户.
   * [kanbanflow.com](https://kanbanflow.com/) — Board-based project management. Free, premium version with more options
   * [kanbantool.com](https://kanbantool.com/) — Kanban board-based project management. Free, paid plans with more options
   * [Kitemaker.co](https://kitemaker.co) - Collaborate through all phases of the product development process and keep track of work across Slack, Discord, Figma, and Github. Unlimited users, unlimited spaces. Free plan up to 250 work items.
   * [Kumu.io](https://kumu.io/)   — 包含动画、装饰、过滤器、聚类、电子表格导入等的关系图. 免费层允许无限的公共项目. 图表大小不受限制. 为学生提供免费的私人项目. 如果您不想让文件公开在线（上传、编辑、下载、丢弃），则可以使用沙盒模式.
   * [LeanBoard](https://www.leanboard.io) — Collaborative whiteboard with sticky notes for your GitHub issues (Useful for Example Mapping and other techniques)
   * [Linear](https://linear.app/) — Issue tracker with streamlined interface. Free for unlimited members, up to 10MB file upload size, 250 issues (excluding Archive)
   * [MeisterTask](https://www.meistertask.com/) — Online task management for teams. Free up to 3 projects, unlimited project members.
   * [MeuScrum](https://www.meuscrum.com/en) - Free online scrum tool with kanban board
   * [nTask](https://www.ntaskmanager.com/)  — 项目管理软件，使您的团队能够协作、计划、分析和管理日常任务. 基本计划永久免费，具有 100 MB 存储空间，5 个用户/团队. 无限的工作空间、会议、任务、时间表和问题跟踪.
   * [Ora](https://ora.pm/) - Agile task management & team collaboration. Free for up to 3 users and files are limited to 10 MB.
   * [pivotaltracker.com](https://www.pivotaltracker.com/) — 对无限的公共项目和两个私人项目免费，总共有 3 个活跃用户（读写）和无限的被动用户（只读）.
   * [plan.io](https://plan.io/) — Project Management with Repository Hosting and more options. Free for 2 users with 10 customers and 500MB Storage
   * [planitpoker.com](https://www.planitpoker.com/) — 免费在线规划扑克（估算工具）
   * [saas.zentao.pm](https://saas.zentao.pm/) - An Application Lifecycle Management solution for Issue Tracking and Project Management, on-premise and open source version are available as well.
   * [ScrumFast](https://www.scrumfast.com) - Scrum 板具有非常直观的界面，最多可释放 5 个用户.
   * [Shortcut](https://shortcut.com/) - Project management platform. Free for up to 10 users forever.
   * [SpeedBoard](https://speedboard.app) - 敏捷和 Scrum 回顾委员会 - 免费.
   * [Shake](https://www.shakebugs.com/) - In-app bug reporting and feedback tool for mobile apps. Free plan, 10 bug reports per app/per month.
   * [Tadum](https://tadum.app) - 专为定期会议设计的会议议程和会议记录应用程序，最多 10 人的团队可免费使用
   * [taiga.io](https://taiga.io/) — Project management platform for startups and agile developers, free for Open Source
   * [Tara AI](https://tara.ai/)  — 简单的冲刺管理服务. 免费计划有无限的任务、冲刺和工作空间，没有用户限制.
   * [targetprocess.com](https://www.targetprocess.com/) — Visual project management, from Kanban and Scrum to almost any operational process. Free for unlimited users, up to 1,000 data entities {[more details](https://www.targetprocess.com/pricing/)}
   * [taskade.com](https://www.taskade.com/) — Real-time collaborative task lists and outlines for teams
   * [taskulu.com](https://taskulu.com/) — Role based project management. Free up to 5 users. Integration with GitHub/Trello/Dropbox/Google Drive
   * [teamwork.com](https://teamwork.com/)  — 项目管理和团队聊天.  5 个用户和 2 个项目免费. 提供高级计划.
   * [testlio.com](https://testlio.com/)  — 问题跟踪、测试管理和beta测试平台. 免费供私人使用
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
   * [zenhub.com](https://www.zenhub.com) — The only project management solution inside GitHub. Free for public repos, OSS and nonprofit organizations
   * [zepel.io](https://zepel.io/)  - 项目管理工具，可让您规划功能、跨学科协作以及共同构建软件. 最多释放 5 名成员. 没有功能限制.
   * [zenkit.com](https://zenkit.com) — Project management and collaboration tool. Free for up to 5 members, 5 GB attachments.
   * [Zube](https://zube.io)  — 为 4 个项目和 4 个用户提供免费计划的项目管理.  GitHub 集成可用.
   * [Toggl](https://toggl.com/) — Provides 2 free productivity tools. [Toggl Track](https://toggl.com/track/) 具有免费计划的时间管理和跟踪应用程序提供了专为自由职业者设计的无缝时间跟踪和报告. 它具有无限的跟踪记录、项目、客户、标签、报告等. 和 [Toggl Plan](https://toggl.com/plan/) for task planning that comes with a free plan for solo developers with unlimited tasks, milestones and timelines.


## Storage and Media Processing

   * [borgbase.com](https://www.borgbase.com/)  — Borg Backup 的简单安全的异地备份托管.  10 GB 可用备份空间和 2 个存储库.
   * [icedrive.net](https://www.icedrive.net/) - Simple cloud storage service. 10 GB free storage
   * [sync.com](https://www.sync.com/) - End-to-End cloud storage service. 5 GB free storage
   * [pcloud.com](https://www.pcloud.com/) <i>- Cloud storage service.</i> <b>- 云存储服务。</b> <i>Up to 10 GB free storage</i><b>高达 10 GB 的免费存储空间</b>
   * [sirv.com](https://sirv.com/) — Smart Image CDN with on-the-fly image optimization and resizing. Free tier includes 500 MB of storage and 2 GB bandwidth.
   * [image4.io](https://image4.io/) — Image upload, powerful manipulations, storage and delivery for websites and apps, with SDK's, integrations and migration tools. Free tier includes 25 credits. 1 credit is equal to 1 GB of CDN usage, 1GB of storage or 1000 image transformations.
   * [cloudimage.com](https://cloudimage.com/) — Full image optimization and CDN service with 1500+ Points of Presence around the world. A variety of image resizing, compression, watermarking functions. Open source plugins for responsive images, 360 image making and image editing. Free monthly plan with 25GB of CDN traffic and 25GB of cache storage and unlimited transformations.
   * [cloudinary.com](https://cloudinary.com/)  — 用于网站和应用程序的图像上传、强大的操作、存储和交付，以及用于 Ruby、Python、Java、PHP、Objective-C 等的库. 免费套餐包括 25 个每月积分.  1 个积分等于 1,000 个图像转换、1 GB 的存储空间或 1 GB 的 CDN 使用量.
   * [easyDB.io](https://easydb.io/)  — 一键式托管数据库提供商. 它们为您选择的用于开发目的的编程语言提供数据库. 该数据库是短暂的，将在免费层 24 或 72 小时后删除.
   * [embed.ly](https://embed.ly/) — Provides APIs for embedding media in a webpage, responsive image scaling, extracting elements from a webpage. Free for up to 5,000 URLs/month at 15 requests/second
   * [filestack.com](https://www.filestack.com/) — File picker, transform and deliver, free for 250 files, 500 transformations and 3 GB bandwidth
   * [gumlet.com](https://www.gumlet.com/)  — 图像调整大小即服务. 它还优化图像并通过 CDN 执行交付. 免费套餐包括 1 GB 带宽和 1 年内每月不限次数的图像处理.
   * [image-charts.com](https://www.image-charts.com/) — 带水印的无限图像图表生成
   * [imgen](https://www.jitbit.com/imgen/) - 免费无限社交封面图片生成API，无水印
   * [jsonbin.io](https://jsonbin.io/) — Free JSON data storage service, ideal for small-scale web apps, website, mobile apps.
   * [kraken.io](https://kraken.io/) — 图像优化网站性能即服务，免费计划高达 1 MB 文件大小
   * [npoint.io](https://www.npoint.io/) — JSON store with collaborative schema editing
   * [otixo.com](https://www.otixo.com/) — Encrypt, share, copy and move all your cloud storage files from one place. Basic plan provides unlimited files transfer with 250 MB max. file size and allows 5 encrypted files
   * [packagecloud.io](https://packagecloud.io/)  — YUM、APT、RubyGem 和 PyPI 的托管包存储库. 有限的免费计划，可根据要求提供开源计划
   * [piio.co](https://piio.co/)  — 每个网站的响应式图像优化和交付. 开发人员和个人网站的免费计划. 包括开箱即用的免费 CDN、WebP 和延迟加载.
   * [Pinata IPFS](https://pinata.cloud)  — Pinata 是在 IPFS 上上传和管理文件的最简单方法. 我们友好的用户界面与我们的 IPFS API 相结合，使 Pinata 成为平台、创建者和收集者最简单的 IPFS 固定服务.  1 GB 免费存储以及对 API 的访问.
   * [placeholder.com](https://placeholder.com/) — A quick and simple image placeholder service
   * [placekitten.com](https://placekitten.com/) — A quick and simple service for getting pictures of kittens for use as placeholders
   * [plot.ly](https://plot.ly/)  — 绘制和分享您的数据. 免费套餐包括无限的公共文件和 10 个私人文件
   * [podio.com](https://podio.com/) — 您可以与最多五人的团队一起使用 Podio，并试用基本计划的功能，但用户管理除外
   * [QuickChart](https://quickchart.io) — Generate embeddable image charts, graphs, and QR codes
   * [redbooth.com](https://redbooth.com) — P2P file syncing, free for up to 2 users
   * [Skynet](https://siasky.net) — An open protocol for hosting data and web applications on the decentralized web using [Sia](https://sia.tech/) . 免费层提供高达 100GB 的存储空间.
   * [Storj](https://storj.io) — Decentralised Private Cloud Storage for Apps and Developers. Free plan provides 3 Projects, 50 GB storage per project/month , 50 GB bandwidth per project/month.
   * [tinypng.com](https://tinypng.com/) — API to compress and resize PNG and JPEG images, offers 500 compressions for free each month
   * [transloadit.com](https://transloadit.com/) — Handles file uploads and encoding of video, audio, images, documents. Free for Open source, charities, and students via the GitHub Student Developer Pack. Commercial applications get 2 GB free for test driving
   * [twicpics.com](https://www.twicpics.com) - Responsive images as a service. It provides an image CDN, a media processing API and frontend library to automate image optimization. The service is free up to 3GB trafic/month.
   * [uploadcare.com](https://uploadcare.com/hub/developers/)  — Uploadcare 为媒体管道提供基于尖端算法的终极工具包. 开发人员可以完全免费使用所有功能：文件上传 API 和 UI、图像 CDN 和源服务、自适应交付和智能压缩. 限制免费层有 3000 次上传、3 GB 流量和 3 GB 存储空间.
   * [imagekit.io](https://imagekit.io) – Image CDN with automatic optimization, real-time transformation, and storage that you can integrate with existing setup in minutes. Free plan includes up to 20GB bandwidth per month.
   * [internxt.com](https://internxt.com)  – Internxt Drive 是一种基于绝对隐私和毫不妥协的安全性的零知识文件存储服务. 注册并永久免费获得 2 GB！
   * [degoo.com](https://degoo.com/) – 基于 AI 的云存储，最多可免费使用 100 Gb、5 台设备、500 Gb 推荐奖金（365 天帐户不活动）.



## Design and UI

  * [AllTheFreeStock](https://allthefreestock.com) - 精选的免费库存图片、音频和视频列表.
  * [Ant Design Landing Page](https://landing.ant.design/)  - Ant Design Landing Page 提供了由 Ant Motion 的运动组件构建的模板. 拥有丰富的首页模板，模板代码包下载，快速上手. 您还可以使用编辑器快速构建自己的专用页面.
  * [Backlight](https://backlight.dev/) — Backlight 以开发人员和设计师之间的协作为核心，是一个非常完整的编码平台，团队可以在其中构建、记录、发布、扩展和维护设计系统.免费计划允许多达 3 位编辑在一个设计系统上工作，且查看者不受限制.
  * [BoxySVG](https://boxy-svg.com/app) — A free installable Web app for drawing SVGs and exporting in svg,png,jpeg an other formats.
  * [clevebrush.com](https://www.cleverbrush.com/) — Free Graphics Design / Photo Collage App, also they offer paid integration of it as component.
  * [cloudconvert.com](https://cloudconvert.com/) — Convert anything to anything. 208 supported formats including videos to gif.
  * [CodeMyUI](https://codemyui.com) - 精选的网页设计和 UI 灵感与代码片段集合.
  * [coolors](https://coolors.co/)  - 调色板生成器. 自由.
  * [designer.io](https://www.designer.io/)  — UI、插图等的设计工具. 有一个本机应用程序. 自由.
  * [figma.com](https://www.figma.com) — Online, collaborative design tool for teams; free tier includes unlimited files and viewers with a max of 2 editors and 3 projects.
  * [framer.com](https://www.framer.com/)  - Framer 帮助您为您的下一个应用程序、网站或产品迭代和动画界面创意——从强大的布局开始. 对于任何将 Framer 验证为专业原型制作工具的人：无限的查看器、最多 2 个编辑器、最多 3 个项目.
  * [Gradientos](https://www.gradientos.app) - Makes choosing a gradient fast and easy.
  * [Icon Horse](https://icon.horse) – Get the highest resolution favicon for any website from our simple API.
  * [Icons8](https://icons8.com) — Icons, illustrations, photos, music, and design tools. Free Plan offers Limited formats in lower resolution. Link to Icons8 when you use our assets.
  * [imagebin.ca](https://imagebin.ca/) — Pastebin for images.
  * [Invision App](https://www.invisionapp.com)  - UI 设计和原型制作工具. 桌面和网络应用程序可用. 免费使用 1 个活动原型.
  * [landen.co](https://www.landen.co) — Generate, edit and publish beautiful websites and landing pages for your startup. All without code. Free tier allows you to have one website, fully customizable and published on the web.
  * [lensdump.com](https://lensdump.com/) - Free cloud image hosting.
  * [Lorem Picsum](https://picsum.photos/) - A Free tool, easy to use stylish placeholders. Just add your desired image size (width & height) after our URL, and you'll get a random image.
  * [LottieFiles](https://lottiefiles.com/) - The world’s largest online platform for the world’s smallest animation format for designers, developers, and more. Access Lottie animation tools and plugins for Android, iOS, and Web.
  * [MagicPattern](https://www.magicpattern.design/tools) — 用于渐变、图案和 blob 的 CSS 和 SVG 背景生成器和工具的集合.
  * [marvelapp.com](https://marvelapp.com/) — 设计、原型制作和协作，免费计划仅限于一个用户和一个项目.
  * [Mindmup.com](https://www.mindmup.com/)  — 免费无限的思维导图，并将它们存储在云端. 您的思维导图随处可用，可通过任何设备即时访问.
  * [Mockplus iDoc](https://www.mockplus.com/idoc)  - Mockplus iDoc 是一个强大的设计协作和交接工具. 免费计划包括 3 个用户和 5 个具有所有可用功能的项目.
  * [mockupmark.com](https://mockupmark.com/create/free) — Create realistic t-shirt and clothing mockups for social media and E-commerce, 40 free mockups.
  * [Octopus.do](https://octopus.do)  — 视觉站点地图生成器. 实时构建您的网站结构并快速共享它以与您的团队或客户协作.
  * [Pencil](https://github.com/evolus/pencil) - Open source design tool using Electron.
  * [Penpot](https://penpot.app)  - 基于 Web 的开源设计和原型制作工具. 支持 SVG. 完全免费.
  * [pexels.com](https://www.pexels.com/) - Free stock photos for commercial use. Has free API that allows you to search photos by keywords.
  * [photopea.com](https://www.photopea.com) — 一款免费的高级在线设计编辑器，带有支持 PSD、XCF 和 Sketch 格式（Adobe Photoshop、Gimp 和 Sketch 应用程序）的 Adob​​e Photoshop UI.
  * [pixlr.com](https://pixlr.com/) — 商业级别的免费在线浏览器编辑器.
  * [Plasmic](https://www.plasmic.app/) - A fast, easy to use, powerful web design tool and page builder that integrates into your codebase. Build responsive pages or complex components; optionally extend with code; and publish to production sites and apps.
  * [Pravatar](https://pravatar.cc/) - Generate random/placeholder fake avatar, which url can be directly hotlinked in your web/app.
  * [Proto.io](https://www.proto.io) - Create fully interactive UI prototypes without coding. Free tier available when free trial ends. Free tier includes: 1 user, 1 project, 5 prototypes, 100MB online storage and preview in proto.io app.
  * [resizeappicon.com](https://resizeappicon.com/) — A simple service to resize and manage your app icons.
  * [Rive](https://rive.app) — Create and ship beautiful animations to any platform. Free forever for Individuals. The service is a editor which hosts all the graphics on their servers as well. They also provide runtimes for many platforms to run graphics made using Rive.
  * [smartmockups.com](https://smartmockups.com/) — Create product mockups, 200 free mockups.
  * [tabler-icons.io](https://tabler-icons.io/) — 超过 1500 个免费复制和粘贴 SVG 可编辑图标.
  * [UI Avatars](https://ui-avatars.com/) - Generate avatars with initials from names. Which the urls can be directly hotlinked in your web/app. Support config parameters via the url.
  * [unDraw](https://undraw.co/) - 不断更新的精美 svg 图像集合，您可以完全免费使用，无需署名.
  * [unsplash.com](https://unsplash.com/) - Free stock photos for commercial and noncommercial purposes (do-whatever-you-want license).
  * [vectr.com](https://vectr.com/) — Free Design App for Web + Desktop.
  * [walkme.com](https://www.walkme.com/) — Enterprise Class Guidance and Engagement Platform, free plan 3 walk-thrus up to 5 steps/walk.
  * [Webflow](https://webflow.com) - WYSIWYG web site builder with animations and website hosting. Free for 2 projects.
  * [Updrafts.app](https://updrafts.app) - WYSIWYG web site builder for tailwindcss based designs. Free for non-commercial usage.
  * [whimsical.com](https://whimsical.com/) - Collaborative flowcharts, wireframes, sticky notes and mind maps. Create up to 4 free boards.
  * [Zeplin](https://zeplin.io/)  — 设计师和开发者协作平台. 展示设计、资产和风格指南.  1 个项目免费.
  * [Pixelixe](https://pixelixe.com/) — Create and edit engaging and unique graphics and images online.
  * [Responsively App](https://responsively.app) - A free dev-tool for faster and precise responsive web application development.
  * [SceneLab](https://scenelab.io) - Online mockup graphics editor with an ever-expanding collection of free design templates
  * [xLayers](https://xlayers.dev) - 预览 Sketch 设计文件并将其转换为 Angular、React、Vue、LitElement、Stencil、Xamarin 等（在 https://github.com/xlayers/xlayers 上免费和开源）
  * [Grapedrop](https://grapedrop.com/) — Responsive, powerful, SEO optimized web page builder based on GrapesJS Framework. Free for first 5 pages, unlimited custom domains, all features and simple usage.
  * [Mastershot](https://mastershot.app) - Completely free browser-based video editor. No watermark, up to 1080p export options.
  * [Unicorn Platform](https://unicornplatform.com/) - Effortless landing page builder with hosting. 1 website for free.
  * [react-favicon.com](https://react-favicon.com/) - Generate Favicons for your web site using React and JSX using any font and icon library.


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

   * [IP Geolocation](https://ipgeolocation.io/) — Free DEVELOPER plan available with 30K requests/month.
   * [carto.com](https://carto.com/) — 根据您的数据和公共数据创建地图和地理空间 API.
   * [developers.arcgis.com](https://developers.arcgis.com) — APIs and SDKs for maps, geospatial data storage, analysis, geocoding, routing, and more across web, desktop, and mobile. 2,000,000 free basemap tiles, 20,000 non-stored geocodes, 20,000 simple routes, 5,000 drive time calculations, 5GB free tile+data storage per month.
   * [Foursquare](https://developer.foursquare.com/) - Location discovery, venue search, and context-aware content from Places API and Pilgrim SDK.
   * [geoapify.com](https://www.geoapify.com/) - Vector and raster map tiles, geocoding, places, routing, isolines APIs. 3000 free requests / day.
   * [geocod.io](https://www.geocod.io/)  — 通过 API 或 CSV 上传进行地理编码. 每天 2,500 次免费查询.
   * [geocodify.com](https://geocodify.com/)  — 通过 API 或 CSV 上传进行地理编码和地理解析.  10k 免费查询/月.
   * [giscloud.com](https://www.giscloud.com/) — Visualize, analyze and share geo data online.
   * [gogeo.io](https://gogeo.io/) — Maps and geospatial services with an easy to use API and support for big data.
   * [graphhopper.com](https://www.graphhopper.com/) 为开发人员提供了一个免费包，用于路由、路线优化、距离矩阵、地理编码、地图匹配.
   * [here](https://developer.here.com/)  — 用于地图和位置感知应用的 API 和 SDK.  250k 交易/月免费.
   * [mapbox.com](https://www.mapbox.com/) — 地图、地理空间服务和用于显示地图数据的 SDK.
   * [maptiler.com](https://www.maptiler.com/cloud/) — Vector maps, map services and SDKs for map visualisation. Free vector tiles with weekly update and four map styles.
   * [opencagedata.com](https://opencagedata.com)  — 聚合 OpenStreetMap 和其他开放地理资源的地理编码 API. 每天 2,500 次免费查询.
   * [osmnames](https://osmnames.org/) — 地理编码，搜索结果按相关维基百科页面的受欢迎程度排名.
   * [positionstack](https://positionstack.com/) - Free geocoding for global places and coordinates. 25.000 Requests per month for personal use.
   * [stadiamaps.com](https://stadiamaps.com/) — Map tiles, routing, navigation, and other geospatial APIs. 2,500 free map views and API requests / day for non-commercial usage and testing.
   * [maps.stamen.com](http://maps.stamen.com/) - Free map tiles and tile hosting.
   * [GeocodeAPI](https://geocodeapi.io) - Geocode API: Address to Coordinate Conversion & Geoparsing based on Pelias. Batch geocoding via CSV. 350000 free requests/month.
   * [Geokeo api](https://geokeo.com)  - 具有语言校正等功能的地理编码 API. 全球覆盖. 每日 2,500 次免费查询


## Package Build System

   * [build.opensuse.org](https://build.opensuse.org/) — Package build service for multiple distros (SUSE, EL, Fedora, Debian etc).
   * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — Mock-based RPM build service for Fedora and EL.
   * [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu and Debian build service.


## IDE and Code Editing

   * [3v4l](https://3v4l.org/) - Free online PHP shell and snippet sharing site, runs your code in 300+ PHP versions
   * [Android Studio](https://d.android.com/studio) — Android Studio provides the fastest tools for building apps on every type of Android device. Open Source IDE, free for everyone and the best to develop Android apps. Available for Windows,Mac,Linux and even ChromeOS!
   * [Apache Netbeans](https://netbeans.apache.org/) — 开发环境、工具平台和应用框架.
   * [apiary.io](https://apiary.io/) — 具有即时 API 模拟和生成文档的协作设计 API（无限的 API 蓝图和无限的用户免费提供一个管理员帐户和托管文档）.
   * [Atom](https://atom.io/) - Atom is a hackable text editor built on Electron.
   * [Binder](https://mybinder.org/) - Turn a Git repo into a collection of interactive notebooks. It is a free, public service.
   * [BlueJ](https://bluej.org)  — 专为初学者设计的免费 Java 开发环境，全球数百万人使用. 由 Oracle 和简单的 GUI 提供支持，以帮助初学者.
   * [Bootify.io](https://bootify.io/) - 具有自定义数据库和 REST API 的 Spring Boot 应用程序生成器.
   * [cacher.io](https://www.cacher.io) — Code snippet organizer with labels and support for 100+ programming languages.
   * [Code::Blocks](https://codeblocks.org) — Free Fortran & C/C++ IDE. Open Source and runs on Windows,macOS & Linux.
   * [codiga.io](https://codiga.io/)  — 编码助手，可让您直接在 IDE 中搜索、定义和重用代码片段. 个人和小型组织免费.
   * [codesnip.com.br](https://codesnip.com.br) — Simple code snippets manager with categories, search and tags. free and unlimited.
   * [cocalc.com](https://cocalc.com/)  —（以前位于 cloud.sagemath.com 的 SageMathCloud）— 云中的协作计算. 浏览器访问具有内置协作功能的完整 Ubuntu，以及许多用于数学、科学、数据科学的免费软件，预装：Python、LaTeX、Jupyter Notebooks、SageMath、scikitlearn 等.
   * [ide.cs50.io](https://ide.cs50.io/) - 由哈佛大学提供的由 AWS Cloud9 提供支持的免费 IDE.
   * [codepen.io](https://codepen.io/) — CodePen is a playground for the front end side of the web.
   * [codesandbox.io](https://codesandbox.io/) — Online Playground for React, Vue, Angular, Preact and more.
   * [Components.studio](https://webcomponents.dev/) - Code components in isolation, visualize them in stories, test them and publish them on npm.
   * [Eclipse Che](https://www.eclipse.org/che/)  - 基于 Web 的 Kubernetes 原生 IDE，适用于具有多语言支持的开发团队. 开源和社区驱动.  Red Hat 托管的在线实例可在以下位置获得 [workspaces.openshift.com](https://workspaces.openshift.com/).
   * [fakejson.com](https://fakejson.com/) — FakeJSON helps you quickly generate fake data using its API. Make an API request describing what you want and how you want it. The API returns it all in JSON. Speed up the go to market process for ideas and fake it till you make it.
   * [gitpod.io](https://www.gitpod.io)  — 用于 GitHub 项目的即时、可编写代码的开发环境. 开源免费.
   * [ide.goorm.io](https://ide.goorm.io)  goormIDE 是完整的云端 IDE. 多语言支持、基于 linux 的容器（通过功能齐全的基于 Web 的终端）、端口转发、自定义 url、实时协作和聊天、共享链接、Git/Subversion 支持. 还有更多功能（免费层包括每个容器 1GB RAM 和 10GB 存储，5 个容器插槽）.
   * [JDoodle](https://www.jdoodle.com) — 超过 60 种编程语言的在线编译器和编辑器，提供免费的 REST API 代码计划，每天最多编译 200 个积分.
   * [jetbrains.com](https://jetbrains.com/products.html) — Productivity tools, IDEs and deploy tools (aka [IntelliJ IDEA](https://www.jetbrains.com/idea/), [PyCharm](https://www.jetbrains.com/pycharm/) ， 等等）. 学生、教师、开源和用户组的免费许可证.
   * [jsbin.com](https://jsbin.com) — JS Bin 是另一个前端 Web（HTML、CSS 和 JavaScript.也支持 Markdown、Jade 和 Sass）的游乐场和代码共享站点.
   * [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle is a playground and code sharing site of front end web, support collaboration as well.
   * [JSONPlaceholder](http://jsonplaceholder.typicode.com/) 一些 REST API 端点以 JSON 格式返回一些虚假数据. 如果您想在本地运行服务器，也可以使用源代码.
   * [Katacoda](https://katacoda.com) — 软件工程师的交互式学习和培训平台，帮助开发人员学习和公司提高采用率.
   * [Lazarus](https://www.lazarus-ide.org/) — Lazarus 是一个兼容 Delphi 的跨平台 IDE，用于快速应用程序开发.
   * [micro-jaymock](https://micro-jaymock.now.sh/) - Tiny API mocking microservice for generating fake JSON data.
   * [mockable.io](https://www.mockable.io/) — Mockable is a simple configurable service to mock out RESTful API or SOAP web-services. This online service allows you to quickly define REST API or SOAP endpoints and have them return JSON or XML data.
   * [mockaroo](https://mockaroo.com/)  — Mockaroo 让您可以生成 CSV、JSON、SQL 和 Excel 格式的真实测试数据. 您还可以为后端 API 创建模拟.
   * [Mocklets](https://mocklets.com) - a HTTP-based mock API simulator, which helps simulate APIs for faster parallel development and more comprehensive testing, with lifetime free tier.
   * [Paiza](https://paiza.cloud/en/) — Develop Web apps in Browser without having the need to setup anything. Free Plan offers 1 server with 24 hours lifetime and 4 hours running time per day with 2 CPU cores, 2 GB RAM and 1 GB storage.
   * [Prepros](https://prepros.io/)  - Prepros 可以开箱即用地编译 Sass、Less、Stylus、Pug/Jade、Haml、Slim、CoffeeScript 和 TypeScript，重新加载您的浏览器并使开发和测试您的网站变得非常容易，因此您可以专注于使它们变得完美. 只需单击几下，您也可以添加自己的工具.
   * [Replit](https://replit.com/) — 适用于各种程序语言的云编码环境.
   * [SoloLearn](https://code.sololearn.com) — A cloud programming playground well-suited for running code snippets. Supports various programming languages. No registration required for running code but required when you need to save code on their platform. Also offers free courses for begginers and intermediate level coders.
   * [stackblitz.com](https://stackblitz.com/) — Online/Cloud Code IDE to create, edit, & deploy fullstack apps. Support any popular NodeJs based frontend & backend frameworks. Shortlink to create new project: [https://node.new](https://node.new).
   * [Visual Studio Code](https://code.visualstudio.com/)  - 代码编辑器重新定义和优化，用于构建和调试现代 Web 和云应用程序. 由 Microsoft 为 Windows、macOS 和 Linux 开发.
   * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — Fully-featured IDE with thousands of extensions, cross-platform app development (Microsoft extensions available for download for iOS and Android), desktop, web and cloud development, multi-language support (C#, C++, JavaScript, Python, PHP and more).
   * [VSCodium](https://vscodium.com/) - Community-driven, without telemetry/tracking, and freely-licensed binary distribution of Microsoft’s editor VSCode
   * [wakatime.com](https://wakatime.com/) — 关于您的编码活动的量化自我指标，使用文本编辑器插件，免费的有限计划.
   * [WebComponents.dev](https://webcomponents.dev/) — 浏览器内的 IDE 可独立地编写 Web 组件，提供 58 个模板，支持故事和测试.


## Analytics, Events and Statistics

   * [Statvoo Analytics](https://analytics.statvoo.com/) — 为您的所有网站提供永久免费的客户分析，每月无限次活动
   * [Avo](https://avo.app/) — Simplified analytics release workflow. Single-source-of-truth tracking plan, type safe analytics tracking library, in-app debuggers, data observability to catch all data issues before you release. Free for 2 workspace members and 1 hour data observability lookback.
   * [Branch](https://branch.io) — Mobile Analytics Platform. Free Tier offers upto 10K Mobile App Users with deep-linking & other services.
   * [Clicky](https://clicky.com)  — 网站分析平台.  1 个网站的免费计划，包含 3000 次浏览分析.
   * [Databox](https://databox.com) — Business Insights & Analytics by combining other analytics & BI platforms. Free Plan offers 3 users, dashboards & data sources. 11M historical data records.
   * [indicative.com](https://indicative.com/) — Customer analytics platform to optimize customer engagement, increase conversion, and improve retention. Free up to 50M events/month.
   * [Panelbear.com](https://panelbear.com/) — Blazingly fast and private, free tier includes 5,000 pageviews per month for unlimited websites
   * [Hitsteps.com](https://hitsteps.com/) — 2,000 pageviews per month for 1 website
   * [amplitude.com](https://amplitude.com/) — 1 million monthly events, up to 2 apps
   * [Flagsmith](https://www.molasses.app) - Release features with confidence; manage feature flags across web, mobile, and server side applications. Use our hosted API, deploy to your own private cloud, or run on-premise
   * [GoatCounter](https://www.goatcounter.com/) — GoatCounter is an open source web analytics platform available as a hosted service (free for non-commercial use) or self-hosted app. It aims to offer easy to use and meaningful privacy-friendly web analytics as an alternative to Google Analytics or Matomo. Free tier is for non-commerical use and includes unlimited number of sites, 6 months of data retention, and 100k pageviews/month.
   * [Google Analytics](https://analytics.google.com/) - 谷歌分析
   * [Expensify](https://www.expensify.com/) — 费用报告，免费的个人报告审批流程
   * [getinsights.io](https://getinsights.io) - 以隐私为重点的无 cookie 分析，每月最多可免费处理 5k 个事件.
   * [heap.io](https://heap.io)  — 自动捕获 iOS 或 Web 应用程序中的每个用户操作. 每月最多 5,000 次访问免费
   * [Hotjar](https://hotjar.com) — Website Analytics and Reports . Free Plan allows 2000 pageviews/day. 100 snapshots/day (max capacity: 300). 3 snapshot heatmaps which can be stored for 365 days. Unlimited Team Members.
   * [Keen](https://keen.io/)  — 用于数据收集、分析和可视化的自定义分析.  50,000 个事件/月免费
   * [Yandex.Metrica](https://metrica.yandex.com/) — 无限制的免费分析
   * [Mixpanel](https://mixpanel.com/) — 100,000 monthly tracked users, unlimited data history and seats, US or EU data residency
   * [Moesif](https://www.moesif.com) — API analytics for REST and GraphQL. (Free up to 500,000 API calls/mo)
   * [Molasses](https://www.molasses.app)  - 强大的功能标志和 A/B 测试. 最多释放 3 个环境，每个环境有 5 个功能标志.
   * [optimizely.com](https://www.optimizely.com) — A/B Testing solution, free starter plan, 1 website, 1 iOS and 1 Android app
   * [Microsoft PowerBI](https://powerbi.com) — Business Insights & Analytics by Microsoft. Free Plan offers limited use with 1 Million User licenses.
   * [quantcast.com](https://www.quantcast.com/products/measure-audience-insights/) — 无限制的免费分析
   * [sematext.com](https://sematext.com/cloud/) — Free for up to 50 K actions/month, 1-day data retention, unlimited dashboards, users, etc.
   * [Similar Web](https://similarweb.com) — Analytics for Web & Mobile Apps. Free Plan offers 5 results per metric, 1 month of mobile app data & 3 months of website data.
   * [StatCounter](https://statcounter.com/) — Website Viewer Analytics. Free plan for analytics of 500 most recent visitors.
   * [Tableau Developer Program](https://www.tableau.com/developer) — Innovate, create, and make Tableau work perfectly for your organization. Free developer program gives a personal development sandbox license for Tableau Online. The version is the latest pre-release version so Data Devs can test each & every feature of this superb platform.
   * [usabilityhub.com](https://usabilityhub.com/) — Test designs and mockups on real people, track visitors. Free for one user, unlimited tests
   * [woopra.com](https://www.woopra.com/) — Free user analytics platform for 500K actions, 90 day data retention, 30+ one click integration.
   * [counter.dev](https://counter.dev)  — 网络分析变得简单，因此对隐私友好. 免费或通过捐赠支付您想要的东西.
   * [PostHog](https://posthog.com) - Full Product Analytics suite free for up to 1m tracked events per month


## Visitor Session Recording

   * [Visualime.com](https://www.visualime.com/) — Free and unlimited session recordings, no traffic limits
   * [Reactflow.com](https://www.reactflow.com/) — 每个站点：每天 1,000 个页面浏览量、3 个热图、3 个小部件、免费的错误跟踪
   * [LogRocket.com](https://www.logrocket.com) - 1,000 sessions/month with 30 day retention, error tracking, live mode
   * [FullStory.com](https://www.fullstory.com)  — 1,000 次会话/月，1 个月的数据保留期和 3 个用户席位. 更多信息 [here](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition).
   * [hotjar.com](https://www.hotjar.com/) — Per site: 2,000 pages views/day, 3 heatmaps, data stored for 3 months,...
   * [inspectlet.com](https://www.inspectlet.com/) — 2,500 sessions/month free for 1 website
   * [livesession.io](https://livesession.io/) — 5,000 sessions/month free for 1 website
   * [Microsoft Clarity](https://clarity.microsoft.com/) - 会话录制完全免费，“无流量限制”、无项目限制、无采样
   * [mouseflow.com](https://mouseflow.com/) — 1 个网站每月免费 500 次会话
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
  * [currencylayer](https://currencylayer.com/) — Reliable Exchange Rates and Currency Conversion for your Business, 1,000 API requests/month free
  * [currencystack.io](https://currencystack.io/) — 154 种货币的生产就绪实时汇率.
  * [exchangerate-api.com](https://www.exchangerate-api.com)  - 一个易于使用的货币转换 JSON API. 免费套餐，没有请求限制.
  * [FraudLabsPRO](https://www.fraudlabspro.com) — Help merchants to prevent payment fraud and chargebacks. Free Micro Plan available with 500 queries/month.
  * [MailPopin](https://mailpop.in) - 通过上下文信息充分利用您的 Stripe 通知.
  * [Nami ML](https://www.namiml.com/) - Complete platform for in-app purchases and subscriptions on iOS and Android, including no-code paywalls, CRM, and analytics.  Free for all base features to run an IAP business.
  * [RevenueCat](https://www.revenuecat.com/) — Hosted backend for in-app purchases and subscriptions (iOS and Android). Free up to $10k/mo in tracked revenue.
  * [vatlayer](https://vatlayer.com/) — 即时增值税号验证和欧盟增值税率 API，每月免费 100 个 API 请求
  * [Freecurrencyapi.net](https://freecurrencyapi.net/)  — 免费的货币换算和汇率数据API.  10 个请求/小时，没有 API 密钥，当您免费注册时，每月 50 000 个请求.


## Docker Related

  * [canister.io](https://canister.io/) — 20 free private repositories for developers, 30 free private repositories for teams to build and store Docker images
  * [Container Registry Service](https://container-registry.com/)  - 基于港口的集装箱管理解决方案. 免费套餐为私有存储库提供 1 GB 存储空间.
  * [Docker Hub](https://hub.docker.com) — 一个免费的私有存储库和无限的公共存储库，用于构建和存储 Docker 映像
  * [Play with Docker](https://labs.play-with-docker.com/) — A simple, interactive and fun playground to learn Docker.
  * [quay.io](https://quay.io/) — Build and store container images with unlimited free public repositories
  * [TreeScale.com](https://treescale.com/)  — 使用组权限托管和管理容器镜像. 免费套餐为私有存储库提供 1 GB 存储空间.
  * [Platform9](https://platform9.com/) - Managed Kubernetes plane. Free plan offers management capabilities up to 3 clusters & 20 nodes. Note: you must provide cluster infrastructure by yourself.


## Vagrant Related

  * [Vagrant Cloud](https://app.vagrantup.com) - HashiCorp Vagrant Cloud. Vagrant box hosting.
  * [Vagrantbox.es](https://www.vagrantbox.es/) — An alternative public box index


## Dev Blogging Sites

  * [BearBlog](https://bearblog.dev/) - 极简主义和 Markdown 驱动的博客和网站构建器.
  * [Dev.to](https://dev.to/) - 程序员分享想法并互相帮助成长的地方.
  * [Hashnode](https://hashnode.com/) — 面向开发人员的无忧博客软件！.
  * [Medium](https://medium.com/) — 更聪明地了解对您而言重要的事情.


## Commenting Platforms
  * [Staticman](https://staticman.net/) - Staticman is a Node.js application that receives user-generated content and uploads it as data files to a GitHub and/or GitLab repository, using Pull Requests.
  * [GraphComment](https://graphcomment.com/) - GraphComment is a comments platform that helps you build an active community from website’s audience.
  * [Utterances](https://utteranc.es/) - A lightweight comments widget built on GitHub issues. Use GitHub issues for blog comments, wiki pages and more!
  * [Disqus](https://disqus.com/) - Disqus is a networked community platform used by hundreds of thousands of sites all over the web.


## Screenshot APIs

  * [24browser.com](https://www.24browser.com) – 使用强大的 API 大规模捕获渲染精美的网站屏幕截图.
  * [ApiFlash](https://apiflash.com) — A screenshot API based on Aws Lambda and Chrome. Handles full page, capture timing, viewport dimensions, ...
  * [microlink.io](https://microlink.io/) – It turns any website into data such as metatags normalization, beauty link previews, scraping capabilities or screenshots as a service. 250 reqs/day every day free.
  * [ScreenshotAPI.net](https://screenshotapi.net/)  - 截图 API 使用一个简单的 API 调用来生成任何网站的截图. 构建以扩展并托管在 Google Cloud 上. 每月提供 100 个免费截图.
  * [screenshotlayer.com](https://screenshotlayer.com/)  — 捕获任何网站的高度可定制的快照. 每月免费 100 张快照
  * [screenshotmachine.com](https://www.screenshotmachine.com/) — Capture 100 snapshots/month, png, gif and jpg, including full-length captures, not only home page
  * [PhantomJsCloud](https://PhantomJsCloud.com) — Browser automation and page rendering.  Free Tier offers up to 500 pages/day.  Free Tier since 2017.
  * [Webshrinker.com](https://webshrinker.com) — Web Shrinker provides web site screenshot and domain intelligence API services. Free 100 requests/month.


## Browser based hardware emulation written in Javascript

  * [JsLinux](https://bellard.org/jslinux) — 一个真正快速的 x86 虚拟机，能够运行 Linux 和 Windows 2k.
  * [Jor1k](http://s-macke.github.io/jor1k/demos/main.html) — 一个能够在网络支持下运行 Linux 的 OpenRISC 虚拟机.
  * [v86](https://copy.sh/v86) — 能够在浏览器中直接运行 Linux 和其他操作系统的 x86 虚拟机.


## Privacy Management
  * [Bearer](https://www.bearer.sh/) - Helps implement privacy by design via audits and continuous workflows so that organizations comply with GDPR and other regulations. Free tier is limited to smaller teams and SaaS version only.
  * [Osano](https://www.osano.com/) - Consent management and compliance platform with everything from GDPR representation to cookie banners. Free tier offers basic features.
  * [Iubenda](https://www.iubenda.com/) - Privacy and cookie policies along with consent management. Free tier offers limited privacy and cookie policy as well as cookie banners.
  * [Cookiefirst](https://cookiefirst.com/) - Cookie banners, auditing, and multi-language consent management solution. Free tier offers a one-time scan and a single banner.
  * [Ketch](https://www.ketch.com/) - Consent management and privacy framework tool. Free tier offers most features with a limited visitor count.


## Miscellaneous

  * [Smartcar API](https://smartcar.com) - An API for cars to locate, get fuel tank, battery levels, odometer, unlock/lock doors, etc.
  * [Blynk](https://blynk.io) — A SaaS with API to control, build & evaluate IoT devices. Free Developer Plan with 5 devices,Free Cloud & data storage. Mobile Apps also available.
  * [Bricks Note Calculator](https://free.getbricks.app/) - a note-taking app (PWA) with a powerful built-in multiline calculator.
  * [Carbon.now.sh](https://carbon.now.sh)  - 以美观的类似屏幕截图的图像格式创建和共享代码片段. 通常用于在 Twitter 或博客文章上美观地分享/炫耀代码片段.
  * [Code Time](https://www.software.com/code-time) - an extension for time-tracking and coding metrics in VS Code, Atom, IntelliJ, Sublime Text, and more.
  * [Codepng](https://www.codepng.app) - Create awesome snapshots from your source code that you can share on social media.
  * [ConfigCat](https://configcat.com)  - 跨平台功能标志服务. 适用于所有主要语言的 SDK. 免费计划每月最多 10 个标志、2 个环境、1 个产品和 500 万个请求. 无限用户席位. 学生每月免费获得 100 个标志和 1 亿个请求.
  * [datelist.io](https://datelist.io) - Online booking / appointment scheduling system. Free up to 5 bookings per month, includes 1 calendar
  * [docsapp.io](https://www.docsapp.io/) — 发布文档的最简单方式，对开源免费
  * [Elementor](https://elementor.com) — WordPress website builder. Free plan available with 40+ Basic Widgets.
  * [Form2Channel](https://form2channel.com)  — 在您的网站上放置一个静态 html 表单，并直接接收提交到 Google 表格、电子邮件、Slack、Telegram 或 Http 的内容. 无需编码.
  * [FOSSA](https://fossa.com/) - 对第三方代码、许可证合规性和漏洞进行可扩展的端到端管理.
  * [fullcontact.com](https://www.fullcontact.com/developer/pricing/) — Help your users know more about their contacts by adding social profile into your app. 500 free Person API matches/month
  * [http2.pro](https://http2.pro) — HTTP/2 protocol readiness test and client HTTP/2 support detection API.
  * [JWT Decoder](https://jwt.ssotools.com/) — 用于解码 JWT（JSON Web 令牌）并验证其签名的在线免费工具.
  * [Base64 decoder/encoder](https://devpal.co/base64-decode/) — 用于解码和编码数据的在线免费工具.
  * [newreleases.io](https://newreleases.io/) - 通过电子邮件、Slack、Telegram、Discord 和自定义 webhook 接收来自 GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM、Node.js Yarn、Ruby Gems、PHP Packagist、.NET NuGet 的新版本通知， Rust Cargo 和 Docker Hub.
  * [PDFMonkey](https://www.pdfmonkey.io/)  — 在仪表板中管理 PDF 模板，使用动态数据调用 API，下载您的 PDF. 每月提供 1000 个免费文档.
  * [QuickType.io](https://quicktype.io/) - Quickly auto generate models/class/type/interface and serializers from JSON, schema, and GraphQL for working with data quickly & safely in any programming language. Convert JSON into gorgeous, typesafe code in any language.
  * [ray.so](https://ray.so/) - 为您的代码片段创建漂亮的图像.
  * [readme.com](https://readme.com/) — 美丽的文档让开源变得简单，免费.
  * [redirection.io](https://redirection.io/) — SaaS tool for managing HTTP redirections for businesses, marketing and SEO.
  * [redirect.pizza](https://redirect.pizza/) - Easily manage redirects with HTTPS support. Free plan includes 10 sources and 100.000 hits per month.
  * [ReqBin](https://www.reqbin.com/)  — 在线发布 HTTP 请求. 流行的请求方法包括 GET、POST、PUT、DELETE 和 HEAD. 支持标头和令牌身份验证. 包括用于保存您的请求的基本登录系统.
  * [superfeedr.com](https://superfeedr.com/)  — 实时 PubSubHubbub 兼容的订阅源、导出、分析. 免费，定制更少
  * [SurveyMonkey.com](https://www.surveymonkey.com) — Create online surveys. Analyze the results online.  Free plan allows only 10 questions and 100 responses per survey.
  * [videoinu](https://videoinu.com) — Create and edit screen recordings and other videos online.
  * [RandomKeygen](https://randomkeygen.com/) - A free mobile-friendly tool offers a variety of randomly generated keys and passwords you can use to secure any application, service or device.
  * [Cronhooks](https://cronhooks.io/) - Replace your cron jobs with webhooks. Invoke any webhook at a given date time or repeatedly using cron expressions. Free plan allows 1 webhook schedule.
  * [Hook Relay](https://www.hookrelay.dev/) - Add webhook support to your app without the hassles: done-for-you queueing, retries with backoff, and logging. The free plan has 100 deliveries per day, 14-day retention, and 3 hook endpoints.
  * [Format Express](https://www.format-express.dev) - Instant online formatter for JSON / XML / SQL.


## Remote Desktop Tools

  * [Getscreen.me](https://getscreen.me) —  Free for 2 devices, no limits on the number and duration of sessions
  * [Apache Guacamole™](https://guacamole.apache.org/) — 开源无客户端远程桌面网关


## Other Free Resources

  * [get.localhost.direct](https://get.localhost.direct) — A better *.localhost.direct Wildcard public CA signed SSL cert for localhost development with sub-domain support  
  * [eu.org](https://nic.eu.org) — Free eu.org domain. Request is usually approved in 14 days.
  * [js.org](https://js.org) - 用于 JavaScript 社区的 GitHub Pages 的免费 js.org 子域.
  * [pp.ua](https://nic.ua/) — Free pp.ua subdomains.
  * [Framacloud](https://degooglisons-internet.org/en/list/) — A list of Free/Libre Open Source Software and SaaS by the French non-profit [Framasoft](https://framasoft.org/en/).
  * [getawesomeness](https://getawesomeness.herokuapp.com) — Retrieve all amazing awesomeness from GitHub... a must see
  * [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) — 面向开发人员的免费和开源软件中心.
  * [GitHub Education](https://education.github.com/pack)  — 为学生收集免费服务. 需要注册.
  * [is-a.dev](https://www.is-a.dev/) — Free `*.is-a.dev` subdomain for developers.
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program) — Get a free sandbox, tools, and other resources you need to build solutions for the Microsoft 365 platform. The subscription is a 90-day [Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5)  （Windows 除外）这是可更新的. 如果您积极参与开发（使用遥测数据和算法测量），它会被更新.
  * [RedHat for Developers](https://developers.redhat.com)  — 专为开发人员免费访问红帽产品，包括 RHEL、OpenShift、CodeReady 等. 仅限个人计划. 还提供免费电子书以供参考.
  * [smsreceivefree.com](https://smsreceivefree.com/) — Provides free temporary and disposable phone numbers.
  * [simplebackups.io](https://simplebackups.io/)  — 直接存储在云存储提供商（AWS、DigitalOcean、Backblaze...）中的服务器和数据库（MySQL、PostgreSQL、MongoDB）的备份自动化服务. 提供 1 个备份的免费计划.
  * [SnapShooter](https://snapshooter.com/) — Backup solution for DigitalOcean, AWS, LightSail, Hetzner and Exoscale, with support for direct database, file system and application backups to s3 based storage. Provides a free plan with daily backups for one resource.
  * [thedev.id](https://thedev.id) — A free thedev.id subdomain for developers.
  * [Themeselection](https://themeselection.com/) — 精选高品质、现代设计、专业且易于使用的免费管理仪表板模板，
HTML Themes and UI Kits to create your applications faster!
  * [Web.Dev](https://web.dev/measure/) — This is a free tool that allows you to see the performance of your website and improve the SEO to get higher rank list in search engines.
  * [SmallDev.tools](https://smalldev.tools/) — A free tool for developers that allows you to Encode/Decode various formats, Minify HTML/CSS/Javascript, Beautify, Generate Fake/Testing real like dataset in JSON/CSV & multiple other formats and many more features. With a delightful interface.
