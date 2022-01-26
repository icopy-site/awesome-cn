<div class="github-widget" data-repo="ripienaar/free-for-dev"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## free-for.dev

开发人员和开源作者现在拥有大量提供免费层级的服务，但很难找到所有这些服务以做出明智的决定.

这是为开发人员提供免费套餐的软件（SaaS、PaaS、IaaS 等）和其他产品的列表.

The scope of this particular list is limited to things that infrastructure developers (System Administrator, DevOps Practitioners, etc.) are likely to find useful. We love all the free services out there, but it would be good to keep it on topic. It's a bit of a grey line at times so this is a bit opinionated; do not be offended if I do not accept your contribution.

此列表是 1000 多人的 Pull Requests、评论、想法和工作的结果. 您也可以通过发送来提供帮助 [Pull Requests](https://github.com/ripienaar/free-for-dev) to add more services or by remove ones whose offerings have changed or been retired.

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

*NOTE:* This list is only for as-a-Service offerings, not for self-hosted software. For a service to be eligible it has to offer a free tier and not just a free trial. If the free tier is time-bucketed it has to be for at least a year. We also consider the free tier from a security perspective, so SSO is fine but I will not accept services that restrict TLS to paid-only tiers.

Table of Contents
=================


## Major Cloud Providers

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 28 frontend instance hours per day, 9 backend instance hours per day
    * Cloud Firestore - 1GB 存储，50,000 次读取，20,000 次写入，每天 20,000 次删除
    * Compute Engine - 1 non-preemptible e2-micro, 30GB HDD, 5GB snapshot storage (restricted to certain regions), 1 GB network egress from North America to all region destinations (excluding China and Australia) per month
    * Cloud Storage - 5GB, 1GB network egress
    * Cloud Shell - Web-based Linux shell/basic IDE with 5GB of persistent storage. 60 hours limit per week
    * Cloud Pub/Sub - 10GB of messages per month
    * Cloud Functions - 2 million invocations per month (includes both background and HTTP invocations)
    * Cloud Run - 每月 200 万次请求、360,000 GB 秒内存、180,000 秒 vCPU 计算时间、每月从北美的 1 GB 网络出口
    * Google Kubernetes Engine - No cluster management fee for one zonal cluster. Each user node is charged at standard Compute Engine pricing
    * BigQuery - 1 TB of querying per month, 10 GB of storage each month
    * Cloud Build - 每天 120 分钟的构建时间
    * Cloud Source Repositories - Up to 5 Users, 50 GB Storage, 50 GB Egress
    * 完整的详细列表 - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * Amazon DynamoDB - 25GB NoSQL DB
    * Amazon Lambda - 每月 100 万次请求
    * Amazon SNS - 1 million publishes per month
    * Amazon Cloudwatch - 10 个自定义指标和 10 个警报
    * Amazon Glacier - 10GB long-term object storage
    * Amazon SQS - 1 million messaging queue requests
    * Amazon CodeBuild - 100min of build time per month
    * Amazon Code Commit - 每月 5 个活跃用户
    * Amazon Code Pipeline - 每月 1 个活动管道
    * Full, detailed list - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1 个 B1S Linux 虚拟机，1 个 B1S Windows 虚拟机
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 个网络、移动或 API 应用程序
    * [Functions](https://azure.microsoft.com/services/functions/) - 1 million requests per month
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - Enable fast, easy, and lean dev-test environments
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 个对象
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 50,000 每月存储用户
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 个活跃用户，无限的私人 Git 存储库
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10 个免费的并行作业，时间不受限制，适用于 Linux、macOS 和 Windows 的开源
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 8,000 messages per day
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1 个免费的公共负载平衡 IP (VIP)
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 100 万条推送通知
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 每月 5GB 出口
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 5GB 存储和 400 RU 的预置吞吐量
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) — Build, deploy and host static apps and serverless functions, with free SSL, Authentication/Authorization and custom domains
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS File or Blob storage
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML API（计算机视觉、翻译器、人脸检测、机器人......）免费层级，包括有限交易
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - AI-based search and indexation service, free for 10,000 documents
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - Managed Kubernetes service, free cluster management
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 100K ops/month
    * Full, detailed list - [https://azure.microsoft.com/free/](https://azure.microsoft.com/free/)

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * Compute - 2 x64-based with 1 GB RAM each, 4 Arm-based Ampere A1 cores and 24 GB of memory usable as one VM or up to 4 VMs
    * 块卷 - 4 个卷，总共 200 GB（用于计算）
    * 对象存储 - 10 GB
    * Load balancer - 1 instance with 10 Mbps
    * 数据库 - 2 个数据库，每个 20 GB
    * Monitoring - 500 million ingestion datapoints, 1 billion retrieval datapoints
    * Bandwidth - 10 TB egress per month, speed limited to 50 Mbps on x64 based VM, 500 Mbps * core count on ARM based VM
    * 公共 IP - 2 个 IPv4 用于 VM，1 个 IPv4 用于负载平衡器
    * Notifications - 1 million delivery options per month, 1000 emails sent per month
    * Full, detailed list - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloud Functions - 5 million executions per month
    * 对象存储 - 每月 25GB
    * Cloudant database - 1 GB of data storage
    * Db2 database - 100MB of data storage
    * API Connect - 每月 50,000 次 API 调用
    * 可用性监控 - 每月 300 万个数据点
    * 日志分析 - 500MB 的每日日志
    * 完整的详细列表 - https://www.ibm.com/cloud/free/


## Cloud management solutions
  * [Brainboard](https://www.brainboard.co) - Collaborative solution to visually build and manage cloud infrastructures from end-to-end.
  * [terraform.io](https://www.terraform.io/)  — Terraform 云. 免费远程状态管理和团队协作，最多可容纳 5 个用户.


## Source Code Repos

  * [Bitbucket](https://bitbucket.org/) — Unlimited public and private Git repos for up to 5 users with Pipelines for CI/CD
  * [chiselapp.com](http://chiselapp.com/) — 无限的公共和私人 Fossil 存储库
  * [codebasehq.com](https://www.codebasehq.com/) — 一个 100 MB 空间和 2 个用户的免费项目
  * [Codeberg.org](https://codeberg.org/)  - 免费和开源项目的无限公共和私人 Git 存储库. 静态网站托管 [Codeberg Pages](https://codeberg.page/).
  * [Gitea.com](https://www.gitea.com/) - Unlimited public and private Git repos
  * [GitGud](https://gitgud.io)  — 无限的私有和公共存储库. 永远免费. 由 GitLab 和蓝宝石提供支持. 未提供 CI/CD.
  * [GitHub](https://github.com/)  — 无限的公共存储库和无限的私有存储库（有无限的合作者）. 除此之外，提供的其他一些免费服务（还有更多，但我们在这里列出主要的）是：
       - [CI/CD](https://github.com/features/actions)（公共回购免费，私人回购免费 2000 分钟/月）
       - [Static Website Hosting](https://pages.github.com) （公共回购免费）
       - [Package Hosting & Container Registry](https://github.com/features/packages) （公共存储库免费，500 MB 存储空间和 CI/CD 之外的 1GB 带宽免费用于私人存储库）
       - 项目管理和问题跟踪.
  * [gitlab.com](https://about.gitlab.com/) — Unlimited public and private Git repos with unlimited collaborators. Also offers the following features :
       - [CI/CD](https://about.gitlab.com/product/continuous-integration) (Free for Public Repos, 400 mins/month for private repos)
       - 静态网站 [GitLab Pages](https://about.gitlab.com/product/pages).
       - 每个 repo 限制为 10 GB 的容器注册表.
       - 项目管理和问题跟踪.
  * [heptapod.net](https://foss.heptapod.net/) — Heptapod is a friendly fork of GitLab Community Edition providing support for Mercurial
  * [ionicframework.com](https://ionicframework.com/appflow) - Repo and tools to develop applications with Ionic, also you have an ionic repo
  * [NotABug](https://notabug.org) — NotABug.org is a free-software code collaboration platform for freely licensed projects, Git-based
  * [OSDN](https://osdn.net/) - OSDN.net 是为开源软件开发人员提供的免费服务，提供 SVN/Git/Mercurial/Bazaar/CVS 存储库等.
  * [Pagure.io](https://pagure.io) — Pagure.io is a free and open source software code collaboration platform for FOSS-licensed projects, Git-based
  * [perforce.com](https://www.perforce.com/products/helix-teamhub) — Free 1GB Cloud and  Git, Mercurial, or SVN repositories.
  * [pijul.com](https://pijul.com/) - Unlimited free and open source distributed version control system. Its distinctive feature is to be based on a sound theory of patches, which makes it easy to learn and use, and really distributed. Solves many problems of git/hg/svn/darcs.
  * [plasticscm.com](https://plasticscm.com/) — 对个人、OSS 和非营利组织免费
  * [projectlocker.com](https://projectlocker.com) — 一个 50 MB 空间的免费私人项目（Git 和 Subversion）
  * [RocketGit](https://rocketgit.com)  — 基于 Git 的存储库托管. 无限的公共和私人存储库.
  * [savannah.gnu.org](https://savannah.gnu.org/) - 作为免费软件项目的协作软件开发管理系统（用于 GNU 项目）
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - Serves as a collaborative software development management system for free Software projects (for non-GNU projects)


## APIs, Data and ML

  * [IP.City](https://ip.city) — 100 free IP geolocation requests per day
  * [Abstract API](https://www.abstractapi.com) — 适用于各种用例的 API 套件，包括 IP 地理定位、性别检测甚至电子邮件验证.
  * [algorithmia.com](https://algorithmia.com/) — Host algorithms for free. Includes free monthly allowance for running algorithms. Now with CLI support.
  * [Apify](https://www.apify.com/) — Web scraping and automation platform to create an API for any website and extract data. Ready-made scrapers, integrated proxies, and custom solutions. Free plan with $5 platform credits included every month.
  * [API Mocha](https://apimocha.com) - Completely free online API mocking for testing and prototyping.  Make up to 500 requests per day, fully customizable API responses, download mock rules as a Postman collection.
  * [APITemplate.io](https://apitemplate.io) - Auto-generate images and PDF documents with a simple API or automation tools like Zapier & Airtable. No CSS/HTML required. Free plan comes with 50 images/month and 3 templates.
  * [Atlas toolkit](https://atlastk.org/) - Lightweight library to develop single-page web applications that are instantly accessible. Available for Java, Node.js, Perl, Python and Ruby.
  * [Beeceptor](https://beeceptor.com) - Mock a rest API in seconds, fake API response and much more. Free 50 requests per day, public dashboard, open endpoints (anyone having link to the dashboard can view requests and responses).
  * [bigml.com](https://bigml.com/)  — 托管机器学习算法. 无限的免费开发任务，16 MB 数据/任务的限制.
  * [Bruzu](https://bruzu.com/) — Automate Image production. Generate tons of Image variants with API, Integrations or nocode sheet. API is FREE with watermark.
  * [Calendarific](https://calendarific.com) - Enterprise-grade Public holiday API service for over 200 countries. Free plan includes 1000 calls per month.
  * [Clarifai](https://www.clarifai.com)  — 用于自定义人脸识别和检测的图像 API. 能够训练人工智能模型. 免费计划每月有 5000 个电话.
  * [Cloudmersive](https://cloudmersive.com/) — 实用 API 平台，可完全访问广泛的 API 库，包括文档转换、病毒扫描等，每月调用 800 次.
  * [Colaboratory](https://colab.research.google.com) — 带有 Nvidia Tesla K80 GPU 的基于 Web 的免费 Python 笔记本环境.
  * [Collect2](https://collect2.com) — Create an API endpoint to test, automate, and connect webhooks. Free plan allows for two datasets, 2000 records, 1 forwarder, and 1 alert.
  * [Conversion Tools](https://conversiontools.io/)  - 用于文档、图像、视频、音频、电子书的在线文件转换器.  REST API 可用.  Node.js、PHP、Python 的库. 支持最大 50 GB 的文件（用于付费计划）. 免费套餐受文件大小和每天转换次数的限制.
  * [CraftMyPDF](https://craftmypdf.com)  - 使用拖放式编辑器和简单的 API 从可重复使用的模板自动生成 PDF 文档. 免费计划附带 100 个 PDF/月和 3 个模板.
  * [CurlHub](https://curlhub.io) — Proxy service for inspecting and debugging API calls. Free plan includes 10,000 requests per month.
  * [CurrencyScoop](https://currencyscoop.com)  - 用于金融科技应用的实时货币数据 API. 免费计划包括每月 5000 次通话.
  * [Datapane](https://datapane.com) - 用于在 Python 中构建交互式报告并将 Python 脚本和 Jupyter Notebooks 部署为自助服务工具的​​ API.
  * [DB Designer](https://www.dbdesigner.net/) — Cloud based Database schema design and modeling tool with a free starter plan of 2 Database models and 10 tables per model.
  * [DeepAR](https://developer.deepar.ai)  — 适用于任何平台的增强现实面部过滤器，只需一个 SDK. 免费计划提供多达 10 个每月活跃用户 (MAU) 并跟踪多达 4 个面孔
  * [Deepnote](https://deepnote.com)  - 一种新型的数据科学笔记本.  Jupyter 兼容实时协作并在云中运行. 免费套餐包括无限的个人项目、长达 750 小时的标准硬件和最多 3 名编辑的团队.
  * [Diggernaut](https://www.diggernaut.com/)  — 基于云的网络抓取和数据提取平台，用于将任何网站转换为数据集或像使用 API 一样使用它. 免费计划包括每月 5K 页面请求.
  * [Disease.sh](https://disease.sh/) — A free API providing accurate data for building the Covid-19 related useful Apps.
  * [dominodatalab.com](https://www.dominodatalab.com) — 支持 Python、R、Spark、Hadoop、MATLAB 等的数据科学.
  * [dreamfactory.com](https://dreamfactory.com/) — Open source REST API backend for mobile, web, and IoT applications. Hook up any SQL/NoSQL database, file storage system, or external service and it instantly creates a comprehensive REST API platform with live documentation, user management,...
  * [DynaPictures](https://dynapictures.com)  - 设计自动化工具，可让您通过 REST API 动态生成图像. 即时更改颜色、文本、徽标和图像. 免费计划包括每月 30 个生成的图像和 3 个图像模板.
  * [Efemarai](https://efemarai.com) - Testing and debugging platform for ML models and data. Visualize any computational graph. Free 30 debugging sessions per month for developers.
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 免费的基于 Web 的 HTTP 客户端发送 HTTP 请求.
  * [Export SDK](https://exportsdk.com) - PDF generator API with drag and drop template editor that also provides an SDK and no-code integrations. Free plan comes with 250 pages per month, unlimited users and three templates.
  * [FraudLabs Pro](https://www.fraudlabspro.com)  — 筛选信用卡支付欺诈的订单交易. 此 REST API 将根据订单的输入参数检测所有可能的欺诈特征. 免费微型计划每月有 500 笔交易.
  * [FreeGeoIP.app](https://freegeoip.app/) - Completely free Geo IP information (JSON, CSV, XML). No registration required, 15000 queries per hour rate limit.
  * [GeoDataSource](https://www.geodatasource.com)  — 使用经纬度坐标查找城市名称的位置搜索服务. 免费 API 查询每月最多 500 次.
  * [Glitterly](https://glitterly.app/)  - 以编程方式从基本模板生成动态图像.  Restful API 和 nocode 集成. 免费套餐每月提供 50 张图片和 5 个模板.
  * [GoodData](https://www.gooddata.com/) - Data as a Service - Create interactive and insightful dashboards. Free tier comes with 5 workspaces and 100 MB/workspace.
  * [Hookbin](https://hookbin.com/) - Create unique (public or private) endpoints to collect, parse, and inspect HTTP requests. Inspect headers, body, query strings, cookies, uploaded files, etc. Useful for testing/inspecting webhook. Similar to RequestBin, and Webhook.site.
  * [Hoppscotch](https://hoppscotch.io) - 免费、快速、美观的 API 请求生成器。
  * [Hybiscus](https://hybiscus.dev/) - Build pdf reports using a simple declarative API. Free tier includes upto 100 single page reports per month with the ability to customise color pallet and fonts.
  * [Invantive Cloud](https://cloud.invantive.com/)  — 使用 Invantive SQL 或 OData4（通常是 Power BI 或 Power Query）访问 70 多个（云）平台，例如 Exact Online、Twinfield、ActiveCampaign 或 Visma. 包括数据复制和交换. 开发人员和实施顾问的免费计划. 对数据量有限制的特定平台免费.
  * [ipaddress.sh](https://ipaddress.sh) — Simple service to get public IP address in different [formats](https://about.ipaddress.sh/).
  * [Iploka](https://iploka.com/) — IP 到 Geolocation API - 为每月 10k 请求限制的开发人员提供永久免费计划.
  * [IP Geolocation](https://ipgeolocation.io/) — IP Geolocation API - Forever free plan for developers with 30k requests per month (1k/day) limit.
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) — Abstract 的 IP Geolocation API - 广泛的免费计划，每月允许 200,000 个请求.
  * [IP2Location](https://www.ip2location.com)  — 免费增值 IP 地理定位服务.  LITE 数据库可免费下载. 将数据库导入服务器，进行本地查询，确定城市、坐标和ISP信息.
  * [ipapi](https://ipapi.co/) - IP Address Location API by Kloudend, Inc - A reliable geolocation API, built on AWS, trusted by Fortune 500. Free tier offers 30k lookups/month (1k/day) without signup. Contact us for a higher limit trial plan.
  * [IPinfo](https://ipinfo.io/)  — 快速、准确且免费（每月最多 50k）的 IP 地址数据 API. 提供有关地理位置、公司、运营商、IP 范围、域、滥用联系人等详细信息的 API. 所有付费 API 均可免费试用.
  * [IPFast](https://ip-fast.com/) — 使用免费、最快和简单的查找工具查找您的 IP 地址和相关详细信息.
  * [IPList](https://www.iplist.cc) — Lookup details about any IP address, such as Geo IP information, tor addresses, hostnames and ASN details. Free for personal and business users.
  * [BigDataCloud](https://www.bigdatacloud.com/) - Provides fast, accurate and free (Unlimited or up to 10K-50K/month) APIs for modern web like IP Geolocation, Reverse Geocoding, Networking Insights, Email and Phone Validation, Client Info and more.
  * [IPTrace](https://iptrace.io) — 一个非常简单的 API，可为您的企业提供可靠且有用的 IP 地理位置数据.
  * [JSON IP](https://getjsonip.com) — Returns the Public IP address of the client it is requested from. No registration required for free tier. Using CORS data can be requested using client side JS directly from browser. Useful for services monitoring change in client and server IPs. Unlimited Requests.
  * [konghq.com/](https://konghq.com/)  — API 市场和强大的私有和公共 API 工具. 在免费层中，某些功能会受到限制，例如监控、警报和支持.
  * [Kreya](https://kreya.app) — Free gRPC GUI client to call and test gRPC APIs. Can import gRPC APIs via server reflection.
  * [KSoft.Si](https://api.ksoft.si/) — 免费歌词 api 主要针对不和谐机器人.还提供广泛的图像和用户数据库
  * [Lightly](https://www.lightly.ai/) — Improve your machine learning models by using the right data. Use datasets of up to 1'000 samples for free.
  * [MailboxValidator](https://www.mailboxvalidator.com) — Email verification service using real mail server connection to confirm valid email. Free API plan has 300 verifications per month.
  * [microlink.io](https://microlink.io/)  – 它将任何网站转化为数据，例如元标记标准化、美容链接预览、抓取功能或屏幕截图即服务. 每天 100 个请求/天免费.
  * [monkeylearn.com](https://monkeylearn.com/) — Text analysis with machine learning, free 300 queries/month.
  * [MockAPI](https://www.mockapi.io/)  — MockAPI 是一个简单的工具，可让您轻松地模拟 API、生成自定义数据并使用 RESTful 接口对其执行操作.  MockAPI 旨在用作原型设计/测试/学习工具. 每个项目免费 1 个项目/50 个资源.
  * [Mocki](https://mocki.io) - A tool that lets you create mock GraphQL and REST APIs synced to a GitHub repository. Simple REST APIs are free to create and use without signup.
  * [Mocko.dev](https://mocko.dev/)  — 免费代理您的 API，选择要在云中模拟的端点并检查流量. 加快您的开发和集成测试.
  * [Mocky](https://designer.mocky.io/) - A simple web app to generate custom HTTP responses for mocking HTTP request. Also available as [open source](https://github.com/julien-lafont/Mocky).
  * [reqres.in](https://reqres.in) - 一个免费托管的 REST-API 准备好响应您的 AJAX 请求.
  * [microenv.com](https://microenv.com) — 为开发人员创建假的 REST API，并有可能在 docker 容器中生成代码和应用程​​序.
  * [neptune.ai](https://neptune.ai/) <i>- Log, store, display, organize, compare and query all your MLOps metadata.</i> <b>- 记录、存储、显示、组织、比较和查询所有 MLOps 元数据。</b> <i>Free for individuals: 1 member, 100 GB of metadata storage, 200h of monitoring/month</i><b>个人免费：1 名成员、100 GB 元数据存储、200 小时监控/月</b>
  * [News API](https://newsapi.org)  — 使用代码在网络上搜索新闻，获取 JSON 结果. 开发人员每月免费获得 3,000 个查询.
  * [OCR.Space](https://ocr.space/) — An OCR API which parses image and pdf files returning the text results in JSON format. 25,000 requests per month free.
  * [Duply.co](https://duply.co) — Create dynamic images from API & URL, design template once and reuse it. Free tier offers 70 images/month creation from API & URL and Up to 100 through Form.
  * [OpenAPI3 Designer](https://openapidesigner.com/) — Visually create Open API 3 definitions for free.
  * [parsehub.com](https://parsehub.com/) — 从动态网站中提取数据，将动态网站变成API，5个项目免费.
  * [Pixela](https://pixe.la/) - Free daystream database service. All operations are performed by API. Visualization with heat maps and line graphs is also possible.
  * [Postbacks](https://postbacks.io/) - Request HTTP callbacks for a later time. 8,000 free requests on signup.
  * [Postman](https://postman.com) — Simplify workflows and create better APIs – faster – with Postman, a collaboration platform for API development. Use the Postman App for free forever. Postman cloud features are also free forever with certain limits.
  * [PrefectCloud](https://www.prefect.io/cloud/) — A complete platform for dataflow automation. All plans include 20,000 free runs every month. That's enough to power ETL for most small businesses.
  * [ProxyCrawl](https://proxycrawl.com/)  — 无需代理、基础设施或浏览器即可抓取网站. 我们为您解决验证码并防止您被阻止. 前 1000 次通话是免费的.
  * [Public-Apis Github Repo](https://github.com/public-apis/public-apis) — A list of free public APIs.
  * [Supportivekoala](http://supportivekoala.com/)  — 允许您通过模板输入自动生成图像. 免费计划允许您每周创建多达 100 张图像.
  * [QuickMocker](https://quickmocker.com/) <i>— Manage online fake API endpoints under your own subdomain, forward requests to localhost URL for webhooks development and testing, use RegExp and multiple HTTP methods for URL path, prioritize endpoints, more than 100 shortcodes (dynamic or fake response values) for response templating, import from OpenAPI (Swagger) Specifications in JSON format, proxy requests, restrict endpoint by IP address and authorization header.</i> <b>— 在您自己的子域下管理在线虚假 API 端点，将请求转发到 localhost URL 以进行 webhook 开发和测试，使用 RegExp 和多种 HTTP 方法作为 URL 路径，优先考虑端点，100 多个短代码（动态或虚假响应值）用于响应模板，从 JSON 格式的 OpenAPI (Swagger) 规范导入，代理请求，通过 IP 地址和授权标头限制端点。</b> <i>Free account provides 1 random subdomain, 10 endpoints, 5 RegExp URL paths, 50 shortcodes per endpoint, 100 requests per day, 50 history records in requests log.</i><b>免费帐户提供 1 个随机子域、10 个端点、5 个 RegExp URL 路径、每个端点 50 个短代码、每天 100 个请求、请求日志中的 50 个历史记录。</b>
  * [RequestBin.com](https://requestbin.com)  — 创建一个可以向其发送 HTTP 请求的免费端点. 发送到该端点的任何 HTTP 请求都将与相关的有效负载和标头一起记录，以便您可以观察来自 webhook 和其他服务的请求.
  * [restlet.com](https://restlet.com/products/apispark/) — APISpark enables any API, application or data owner to become an API provider in minutes via an intuitive browser interface.
  * [Roboflow](https://roboflow.com)  - 无需机器学习经验即可创建和部署自定义计算机视觉模型. 免费套餐包括多达 1,000 个免费源图像.
  * [ROBOHASH](https://robohash.org/) - 从任何文本生成独特（酷 :) 图像的 Web 服务.
  * [Scraper.AI](https://scraper.ai) - SaaS that turns any website into a consumable API for you to build on. Free 50 extractions and 10000 API calls / month.
  * [Scraper's Proxy](https://scrapersproxy.com)  — 用于抓取的简单 HTTP 代理 API. 匿名抓取，而不必担心限制、阻止或验证码. 每月前 100 次成功抓取免费，包括 javascript 渲染（如果您联系支持人员可以获得更多）.
  * [ScrapingAnt](https://scrapingant.com/) — Headless Chrome scraping API and free checked proxies service. Javascript rendering, premium rotating proxies, CAPTCHAs avoiding. Free plans available.
  * [ScraperBox](https://scraperbox.com/) — Undetectable web scraping API using real Chrome browsers and proxy rotation. Use a simple API call to scrape any web page. Free plan has 1000 requests per month.
  * [ScrapingDog](https://scrapingdog.com/)  — Scrapingdog 处理数百万个代理、浏览器和验证码，通过单个 API 调用为您提供任何网页的 HTML. 它还提供适用于 Chrome 和 Firefox 的 Web Scraper 以及用于即时抓取需求的软件. 提供免费计划.
  * [scrapinghub.com](https://scrapinghub.com) — Data scraping with visual interface and plugins. Free plan includes unlimited scraping on a shared server.
  * [ScrapingNinja](https://www.scrapingninja.co/)  — 一站式处理 JS 渲染、Chrome Headless、代理旋转和验证码解决方案. 前 1000 名免费，无需信用卡.
  * [Sheetson](https://sheetson.com)  - 立即将任何 Google 表格转换为 RESTful API. 提供免费计划.
  * [shrtcode API](https://shrtco.de/docs) - Free URL Shortening API without authorization and no request limits.
  * [SerpApi](https://serpapi.com/) - Real-time search engine scraping API. Returns structured JSON results for Google, Youtube, Bing, Baidu, Walmart and many other engines. Free plan includes 100 successful API calls per month.
  * [Similar Words API](https://word-simi.herokuapp.com/) — 一个查找相似词的 API，拥有大约 400 万个词的词汇.
  * [Sofodata](https://www.sofodata.com/)  - 从 CSV 文件创建安全的 RESTful API. 上传 CSV 文件并通过其 API 立即访问数据，从而加快应用程序开发. 免费计划包括每月 2 个 API 和 2,500 个 API 调用. 无需信用卡.
  * [tamber](https://tamber.com) — Put deep-learning powered recommendations in your app. Free 5k monthly active users.
  * [Time Door](https://timedoor.io) - 时间序列分析 API.
  * [TinyMCE](https://www.tiny.cloud) - rich text editing API. Core features free for unlimited usage.
  * [Unixtime](https://unixtime.co.za) - Free API to convert Unixtime to DateTime and vice versa.
  * [Webhook.site](https://webhook.site) - 使用即时显示请求的便捷工具轻松测试 HTTP webhook.
  * [wit.ai](https://wit.ai/) — 面向开发人员的 NLP.
  * [wolfram.com](http://wolfram.com/language/) — Built-in knowledge-based algorithms in the cloud.
  * [wrapapi.com](https://wrapapi.com/)  — 将任何网站变成参数化 API. 每月 30k API 调用.
  * [ZenRows](https://www.zenrows.com/)  — Web Scraping API 和代理服务器，可绕过任何反机器人解决方案，同时提供 javascript 渲染、旋转代理和地理定位.  1000 个 API 调用的免费层级.
  * [Zenscrape](https://zenscrape.com/web-scraping-api)  — 具有无头浏览器、住宅 IP 和简单定价的 Web 抓取 API. 每月 1000 次免费 API 调用，为学生和非营利组织提供额外的免费积分.
  * [ip-api](https://ip-api.com) — IP Geolocation API, Free for non-commercial use, no API key required, limited to 45 req/minute from the same IP address for the free plan.
  * [WebScraping.AI](https://webscraping.ai)  - 带有内置解析、Chrome 渲染和代理的简单 Web Scraping API. 每月 2000 次免费 API 调用.
  * [Zipcodebase](https://zipcodebase.com)  - 免费邮政编码 API，访问全球邮政编码数据.  10000 个免费请求/月.
  * [EVA](http://eva.pingutil.com/) - Free email validator API, which helps to identify whether an email is disposable and having valid MX records.
  * [happi.dev](https://happi.dev) - Freemium api services collection (Music, Exchange Rate, Key value store, Language Detection, Password Generator, QRCode Generator, Lyrics). 8000 free API calls per month.
  * [huggingface.co](https://huggingface.co) - Build, train and deploy NLP models for Pytorch, TensorFlow, and JAX. Free up to 30k input characters/mo.
  * [vatcheckapi.com](https://vatcheckapi.com) - Simple and free VAT number validation API. 500 free requests per month.
  * [numlookupapi.com](https://numlookupapi.com) - Free phone number validation API - 100k free requests / month.
  * [geojs.io](https://www.geojs.io/) - Highly available REST/JSON/JSONP IP Geolocation lookup API.


## Artifact Repos

 * [Artifactory](https://jfrog.com/start-free/)  - 支持多种包格式的工件存储库，如 Maven、Docker、Cargo、Helm、PyPI、CocoaPods 和 GitLFS. 包括包扫描工具 XRay 和 CI/CD 工具 Pipelines（以前称为 Shippable），每月免费提供 2,000 CI/CD 分钟.
 * [central.sonatype.org](https://central.sonatype.org) — Apache Maven、SBT 和其他构建系统的默认工件存储库.
 * [cloudrepo.io](https://cloudrepo.io) - Cloud based, private and public, Maven and PyPi repositories. Free for open source projects.
 * [cloudsmith.io](https://cloudsmith.io) — Simple, secure and centralised repository service for Java/Maven, RedHat, Debian, Python, Ruby, Vagrant +more. Free tier + free for open source.
 * [jitpack.io](https://jitpack.io/) — GitHub 上 JVM 和 Android 项目的 Maven 存储库，公共项目免费.
 * [packagecloud.io](https://packagecloud.io/users/new?plan=free_usage_plan) — Easy to use repository hosting for: Maven, RPM, DEB, PyPi, NPM, and RubyGem packages (has free tier).
 * [repsy.io](https://repsy.io) — 1 GB 免费的私有/公共 Maven 存储库.


## Tools for Teams and Collaboration

  * [3Cols](https://3cols.com/) - A free cloud based code snippet manager for personal and collaborative code.
  * [Bitwarden](https://bitwarden.com) — 个人、团队和企业组织存储、共享和同步敏感数据的最简单、最安全的方式.
  * [Braid](https://www.braidchat.com/)  — 专为团队设计的聊天应用程序. 对公共访问组、无限用户、历史记录和集成免费. 它还提供自托管的开源版本.
  * [cally.com](https://cally.com/) — Find the perfect time and date for a meeting. Simple to use, works great for small and large groups.
  * [Calendly](https://calendly.com)  — Calendly 是用于连接和安排会议的工具. 免费计划为每位用户提供 1 个日历连接和无限次会议. 还提供桌面和移动应用程序.
  * [Discord](https://discord.com/)  — 与公共/私人房间聊天.  Markdown 文本、语音、视频和屏幕共享功能. 无限用户免费.
  * [Telegram](https://telegram.org/) — Telegram is for everyone who wants fast and reliable messaging and calls. Business users and small teams may like the large groups, usernames, desktop apps and powerful file sharing options.
  * [Duckly](https://duckly.com/) — Talk and collaborate in real-time with your team. Pair programming with any IDE, terminal sharing, voice, video and screen sharing. Free for small teams.
  * [evernote.com](https://evernote.com/) — Tool for organizing information. Share your notes and work together with others
  * [Fibery](https://fibery.io/)  — 连接的工作空间平台. 单用户免费，最多 2 GB 磁盘空间.
  * [Filestash](https://www.filestash.app) — 类似于 Dropbox 的文件管理器，可连接到一系列协议和平台：S3、FTP、SFTP、Minio、Git、WebDAV、Backblaze、LDAP 等.
  * [flock.com](https://flock.com)  — 一种更快的团队沟通方式. 免费无限的消息、渠道、用户、应用程序和集成
  * [Flowdash](https://flowdash.com/)  — 自动化业务工作流程. 免费套餐最多可容纳 3 个用户、1000 个任务和 3 个工作流.
  * [flowdock.com](https://www.flowdock.com/) — 聊天和收件箱，最多 5 人的团队免费
  * [GitDailies](https://gitdailies.com) - Daily reports of your team's Commit and Pull Request activity on GitHub. Includes Push visualizer, peer recognition system, custom alert builder. Free tier has unlimited users, 3 repos, 3 alert configs.
  * [gitter.im](https://gitter.im/) — Chat, for GitHub. Unlimited public and private rooms, free for teams up to 25
  * [hangouts.google.com](https://hangouts.google.com/) — One place for all your conversations, for free, need a Google account
  * [HeySpace](https://hey.space) - Task management tool with chat, calendar, timeline and video calls. Free for up to 5 users.
  * [helplightning.com](https://www.helplightning.com/)  — 通过增强现实帮助视频. 免费，无需分析、加密、支持
  * [ideascale.com](https://ideascale.com/) — Allow clients to submit ideas and vote, free for 25 members in 1 community
  * [Igloo](https://www.igloosoftware.com/) — Internal portal for sharing documents, blogs and calendars etc. Free for up to 10 users.
  * [Keybase](https://keybase.io/) — Keybase 是 Slack 的一个很酷的 FOSS 替代品，它确保每个人的聊天和文件安全，从家庭到社区再到公司.
  * [Google Meet](https://meet.google.com/) — Use Google Meet for your business's online video meeting needs. Meet provides secure, easy-to-join online meetings.
  * [/meet for Slack](https://meetslack.com)  - 在任何频道、组或 DM 中使用 /meet 直接从 Slack 启动 Google 会议. 免费，没有任何限制.
  * [MarkUp](https://www.markup.io/) — MarkUp lets you collect feedback directly on top of your websites, PDFs and images.
  * [meet.jit.si](https://meet.jit.si/) — One click video conversations, screen sharing, for free
  * [Microsoft Teams](https://products.office.com/microsoft-teams/free) — Microsoft Teams is a chat-based digital hub that brings conversations, content, and apps together in one place all from a single experience. Free for up to 500k users.
  * [Miro](https://miro.com/) - Scalable, secure, cross-device and enterprise-ready team collaboration whiteboard for distributed teams. With freemium plan.
  * [nootiz](https://www.nootiz.com/) - The go-to tool for gathering and managing visual feedback on any website
  * [Notion](https://www.notion.so/)  - Notion 是一款支持 Markdown 的笔记和协作应用程序，它还集成了任务、wiki 和数据库. 该公司将该应用程序描述为用于记笔记、项目管理和任务管理的一体化工作区. 除了跨平台应用程序外，它还可以通过大多数网络浏览器访问.
  * [Nuclino](https://www.nuclino.com)  - 一个轻量级的协作 wiki，包含您团队的所有知识、文档和笔记. 具有所有基本功能的免费计划，最多 50 个项目，5GB 总存储空间.
  * [PageShare.dev](https://www.pageshare.dev) - Adds visual reviews capabilities into GitHub Pull Requests with no need to deploy websites. Free for up to 10 pages each month and 100MB of storage in total.
  * [Pendulums](https://pendulums.io/) - Pendulums 是一款免费的时间跟踪工具，它通过易于使用的界面和有用的统计数据帮助您以更好的方式管理您的时间.
  * [Raindrop.io](https://raindrop.io) - Private and secure bookmarking app for macOS, Windows, Android, iOS and Web. Free Unlimited Bookmarks and Collaboration.
  * [element.io](https://element.io/) — A decentralized and open source communication tool built on Matrix. Group chats, direct messaging, encrypted file transfers, voice and video chats, and easy integration with other services.
  * [Rocket.Chat](https://rocket.chat/) - Shared inbox for teams, secure, unlimited and open source.
  * [seafile.com](https://www.seafile.com/) — Private or cloud storage, file sharing, sync, discussions. Private version is full. Cloud version has just 1 GB
  * [Slab](https://slab.com/)  — 面向团队的现代知识管理服务. 最多 10 个用户免费.
  * [slack.com](https://slack.com/) — Free for unlimited users with some feature limitations
  * [Spectrum](https://spectrum.chat/) - 免费创建公共或私人社区.
  * [StatusPile](https://www.statuspile.com/)  - 状态页面的状态页面. 跟踪上游提供商的状态页面.
  * [talky.io](https://talky.io/) — Free group video chat. Anonymous. Peer‑to‑peer. No plugins, signup, or payment required
  * [Tefter](https://tefter.io)  - 具有强大 Slack 集成的书签应用程序. 对开源团队免费.
  * [TeleType](https://teletype.oorja.io/)  — 共享终端、语音、代码、白板等. 无需登录，面向开发人员的端到端加密协作.
  * [TimeCamp](https://www.timecamp.com/)  - 无限用户的免费时间跟踪软件. 与 Jira、Trello、Asana 等 PM 工具轻松集成.
  * [Tree Schema](https://treeschema.com/)  — 使用 API 进行数据目录和元数据管理，将数据沿袭作为代码进行管理. 最多 5 名用户的团队免费.
  * [twist.com](https://twist.com)  — 一个异步友好的团队通信应用程序，其中对话保持有条理和主题. 提供免费和无限计划. 为符合条件的团队提供折扣.
  * [BookmarkOS.com](https://bookmarkos.com) - 在可定制的在线桌面中免费的多合一书签管理器、选项卡管理器和任务管理器，具有文件夹协作功能.
  * [typetalk.com](https://www.typetalk.com/) — 通过网络或手机上的即时消息与您的团队分享和讨论想法
  * [Tugboat](https://tugboat.qa)  - 预览每个拉取请求，自动化和按需. 对所有人免费，为非营利组织提供免费的 Nano 层级.
  * [whereby.com](https://whereby.com/) — One click video conversations, for free (formerly known as appear.in)
  * [vadoo.tv](https://vadoo.tv/)  — 视频托管和营销变得简单. 一键上传视频. 记录、管理、分享等等. 免费套餐最多提供 10 个视频、1 GB 存储空间、10 GB 带宽/月
  * [vspace](https://vvv.space/) — 带有私人/公共空间的免费链接管理器，包括 slack 和 google docs 集成以及 chrome 插件.
  * [userforge.com](https://userforge.com/)  - 相互关联的在线角色、用户故事和上下文映射. 帮助保持设计和开发同步，最多可免费供 3 个角色和 2 个协作者使用.
  * [wistia.com](https://wistia.com/) — Video hosting with viewer analytics, HD video delivery and marketing tools to help understand your visitors, 25 videos and Wistia branded player
  * [wormhol.org](https://www.wormhol.org/)  — 简单的文件共享服务. 与尽可能多的同行共享不超过 5GB 的无限文件.
  * [zoom.us](https://zoom.us/)  — 安全的视频和网络会议，可用的附加组件. 免费限时 40 分钟
  * [shtab.app](https://shtab.app/) - 项目管理服务，通过基于 AI 的跟踪器使办公室协作和远程透明化.
  * [zdoo.co](https://www.zdoo.co) — With CRM, OA, and Project management suites, zdoo is so powerful for team collaboration. Free cloud version with limited users and space offered, one-month free trial for premium versions.
  * [Zulip](https://zulip.com/) — Real-time chat with unique email-like threading model. Free plan includes 10,000 messages of search history and File storage up to 5 GB. also it provides self-hostable open-source version.
  * [Automate.io](https://automate.io)  - 简单和复杂的自动化工作流程工具，具有 200 多个应用程序集成. 每月 300 次操作和 5 个机器人是免费
  * [robocorp.com](https://robocorp.com)  - 用于支持自动化操作的开源堆栈. 免费试用云功能并实施简单的自动化. 机器人工作 240 分钟/月，10 次助手运行，100 MB 存储空间.
  * [Fleep.io](https://fleep.io/)  — 选择 Slack 的替代品. 它为具有完整消息历史记录、无限 1 对 1 对话、1 组对话和 1 GB 文件存储的小型团队提供免费计划.
  * [Chanty.com](https://chanty.com/)  — Chanty 是 Slack 的另一种选择. 它为小型团队（最多 10 个）提供永久免费计划，具有无限的公共和私人对话、可搜索的历史记录、无限的 1:1 音频通话、无限的语音消息、10 次集成和每个团队 20 GB 的存储空间.


## CMS

  * [acquia.com](https://www.acquia.com/)  — 托管 Drupal 站点. 开发人员的免费套餐. 还提供免费的开发工具（例如 Acquia Dev Desktop）
  * [Contentful](https://www.contentful.com/)  — 无头 CMS. 云中的内容管理和交付 API. 附带一个免费社区空间，其中包括 5 个用户、25K 条记录、48 种内容类型、2 个语言环境.
  * [Cosmic](https://www.cosmicjs.com/) — Headless CMS and API toolkit. Free personal plans for developers.
  * [Crystallize](https://crystallize.com) — Headless PIM with ecommerce support. Built-in GraphQL API. Free version includes unlimited users, 1000 catalogue items, 5 GB/month bandwidth and 25k/month API calls.
  * [DatoCMS](https://www.datocms.com/)  - 为小型项目提供免费套餐.  DatoCMS 是一个基于 GraphQL 的 CMS. 在较低层，您每月有 10 万次通话.
  * [Directus](https://directus.io)  — 无头 CMS. 一个完全免费的开源平台，用于在本地或云端管理资产和数据库内容. 没有限制或付费墙.
  * [Forestry.io/](https://forestry.io/)  — 无头 CMS. 为您的编辑提供 Git 的强大功能. 轻松创建和编辑基于 Markdown 的内容. 附带三个免费网站，其中包括 3 个编辑器、即时预览. 与托管在 Netlify/GitHubpages/ 其他地方的博客集成
  * [FrontAid](https://frontaid.io/) — Headless CMS that stores JSON content directly in your own Git repository. No restrictions.
  * [kontent.ai](https://www.kontent.ai) - A Content-as-a-Service platform that gives you all the headless CMS benefits while empowering marketers at the same time. Developer plan provides 2 users with unlimited projects with 2 environments for each, 500 content items, 2 languages with Delivery and Management API, and Custom elements support. Larger plans available to meet your needs.
  * [Prismic](https://www.prismic.io/) — Headless CMS. Content management interface with fully hosted and scalable API. The Community Plan provides 1 user with unlimited API calls, documents, custom types, assets, and locales. Everything that you need for your next project. Bigger free plans available for Open Content/Open Source projects.
  * [Sanity.io](https://www.sanity.io/)  - 带有开源编辑环境和实时托管数据存储的结构化内容平台. 无限的项目. 无限的管理员用户、3 个非管理员用户、2 个数据集、500K API CDN 请求、10GB 带宽、每个项目免费包含 5GB 资产.
  * [sensenet](https://sensenet.com) - API-first headless CMS providing enterprise-grade solutions for businesses of all size. The Developer plan provides 3 users, 500 content items, 3 built-in roles, 25+5 content types, fully accessible REST API, document preview generation and Office Online editing.
  * [GraphCMS](https://graphcms.com/)  - 为小型项目提供免费套餐.  GraphQL 第一个 API. 从遗留解决方案转移到 GraphQL 原生 Headless CMS - 并首先提供全渠道内容 API.
  * [Squidex](https://squidex.io/)  - 为小型项目提供免费套餐. 首先是 API/GraphQL. 开源，基于事件溯源（自动处理每一个变化）.


## Code Quality

  * [SoftaCheck](https://www.softacheck.com/)  — 一个在线工具，使用 cppcheck 和 clang-tidy 等开源工具对 C/C++ 代码进行静态分析，并自动为使用 doxygen 的用户生成代码文档. 这个工具是免费使用的.
  * [beanstalkapp.com](https://beanstalkapp.com/) — A complete workflow to write, review and deploy code), free account for 1 user and 1 repository with 100 MB of storage
  * [browserling.com](https://www.browserling.com/) — 实时交互式跨浏览器测试，在 Vista 下使用 MS IE 9 以 1024 x 768 分辨率免费进行 3 分钟会话
  * [codacy.com](https://www.codacy.com/) — Automated code reviews for PHP, Python, Ruby, Java, JavaScript, Scala, CSS and CoffeeScript, free for unlimited public and private repositories
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev)  - DevOps 的自动化基础设施即代码审查工具与 GitHub、Bitbucket 和 GitLab（甚至是自托管）集成. 除了标准语言，它还分析 Ansible、Terraform、CloudFormation、Kubernetes 等.  （开源免费）
  * [CodeBeat](https://codebeat.co) — Automated Code Review Platform available for many languages. Free forever for public repositories with Slack & E-mail integration.
  * [codeclimate.com](https://codeclimate.com/)  — 自动代码审查，开源免费和无限的组织拥有的私人回购（最多 4 个合作者）. 对学生和机构也免费.
  * [codecov.io](https://codecov.io/) — Code coverage tool (SaaS), free for Open Source and 1 free private repo
  * [CodeFactor](https://www.codefactor.io)  — Git 的自动代码审查. 免费版包括无限用户、无限公共存储库和 1 个私人存储库.
  * [codescene.io](https://codescene.io/)  - CodeScene 根据开发人员使用代码的方式确定技术债务的优先级，并可视化团队耦合和系统掌握等组织因素. 开源免费.
  * [coveralls.io](https://coveralls.io/) — 显示测试覆盖率报告，开源免费
  * [dareboost](https://dareboost.com) - 每月 5 份免费的网络性能、可访问性、安全性分析报告
  * [deepcode.ai](https://www.deepcode.ai)  — DeepCode 基于 AI 发现错误、安全漏洞、性能和 API 问题.  DeepCode 的分析速度使我们能够实时分析您的代码并在您点击 IDE 中的保存按钮时提供结果. 支持的语言有 Java、C/C++、JavaScript、Python 和 TypeScript. 与 GitHub、BitBucket 和 GitLab 集成. 对开源和私人存储库免费，最多可释放 30 名开发人员.
  * [deepscan.io](https://deepscan.io) — 高级静态分析，用于自动查找 JavaScript 代码中的运行时错误，开源免费
  * [DeepSource](https://deepsource.io/)  - DeepSource 持续分析源代码更改，发现并修复按安全、性能、反模式、错误风险、文档和样式分类的问题. 与 GitHub、GitLab 和 Bitbucket 的原生集成.
  * [eversql.com](https://www.eversql.com/) — EverSQL - The #1 platform for database optimization. Gain critical insights into your database and SQL queries, auto-magically.
  * [gerrithub.io](https://review.gerrithub.io/) — 免费对 GitHub 存储库进行 Gerrit 代码审查
  * [gocover.io](https://gocover.io/) — 任何代码覆盖率 [Go](https://golang.org/) package
  * [goreportcard.com](https://goreportcard.com/) — Go 项目的代码质量，开源免费
  * [gtmetrix.com](https://gtmetrix.com/) — Reports and thorough recommendations to optimize websites
  * [holistic.dev](https://holistic.dev/) - The #1 static code analyzer for Postgresql optimization. Performance, security, and architect database issues automatic detection service
  * [houndci.com](https://houndci.com/) — Comments on GitHub commits about code quality, free for Open Source
  * [Imgbot](https://github.com/marketplace/imgbot)  — Imgbot 是一个友好的机器人，可以优化您的图像并节省您的时间. 优化的图像意味着在不牺牲质量的情况下更小的文件大小. 它对开源是免费的.
  * [Kritika](https://kritika.io/)  — Perl 的静态代码分析与 GitHub 的集成. 免费用于无限的公共存储库.
  * [resmush.it](https://resmush.it)  — reSmush.it 是一个提供图像优化的免费 API.  reSmush.it 已在 Wordpress、Drupal 或 Magento 等最常见的 CMS 上实现.  reSmush.it 是最常用的图像优化 API，已经处理了超过 70 亿张图像，并且仍然是免费的.
  * [insight.sensiolabs.com](https://insight.sensiolabs.com/) — Code Quality for PHP/Symfony projects, free for Open Source
  * [lgtm.com](https://lgtm.com) — Continuous security analysis for Java, Python, JavaScript, TypeScript, C#, C and C++, free for Open Source
  * [Moderne.io](https://app.moderne.io) — Automatic source code refactoring. Moderne offers framework migrations, code analysis with remediation, and unrivaled code transformation at scale, so developers can spend their time building new things instead of maintaining the old. Free for Open Source.
  * [reviewable.io](https://reviewable.io/) — GitHub 存储库的代码审查，公共或个人存储库免费
  * [parsers.dev](https://parsers.dev/) - Abstract syntax tree parsers and intermediate representation compilers as a service
  * [scan.coverity.com](https://scan.coverity.com/) — Static code analysis for Java, C/C++, C# and JavaScript, free for Open Source
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) — Continuous inspection platform, free for Open Source
  * [shields.io](https://shields.io) — 开源项目的质量元数据徽章
  * [Sider](https://sider.review)  — 多种语言的代码审查平台. 支持与 GitHub 集成. 对拥有无限用户的公共存储库免费.
  * [sonarcloud.io](https://sonarcloud.io) — Automated source code analysis for Java, JavaScript, C/C++, C#, VB.NET, PHP, Objective-C, Swift, Python, Groovy and even more languages, free for Open Source
  * [SourceLevel](https://sourcelevel.io/)  — 自动代码审查和团队分析. 开放源代码和最多 5 个合作者的组织免费.
  * [Typo CI](https://github.com/marketplace/typo-ci) — Typo CI 审查您的 Pull Requests 和提交的拼写错误，对开源免费.
  * [Viezly](https://viezly.com/)  - 增强的代码审查工具，便于代码阅读和导航. 开源免费，个人使用免费.
  * [webceo.com](https://www.webceo.com/) — SEO 工具，但也有代码验证和不同类型的建议
  * [zoompf.com](https://zoompf.com/) — 修复您网站的性能，详细分析


## Code Search and Browsing

  * [codota.com](https://www.codota.com/)  — Codota 通过提供从世界上所有代码中学到的见解，帮助开发人员更快地创建更好的软件. 插件可用.
  * [libraries.io](https://libraries.io/) — 32 个不同的包管理器的搜索和依赖更新通知，开源免费
  * [Namae](https://namae.dev/) - Search across various websites like github,gitlab,heroku,netlify and many more for availabilty of your project name.
  * [searchcode.com](https://searchcode.com/) — Comprehensive text-based code search, free for Open Source
  * [sourcegraph.com](https://about.sourcegraph.com/) — Java, Go, Python, Node.js, etc., code search/cross-references, free for Open Source
  * [tickgit.com](https://www.tickgit.com/) — Surfaces `TODO` comments (and other markers) to identify areas of code worth returning to for improvement.
  * [CodeKeep](https://codekeep.io)  - 谷歌保留代码片段. 组织、发现和共享代码片段，具有强大的代码截图工具，带有预设模板和链接功能.


## CI and CD

  * [AccessLint](https://github.com/marketplace/accesslint) — AccessLint brings automated web accessibility testing into your development workflow. It's free for open source and education purposes.
  * [appcircle.io](https://appcircle.io) — Automated mobile CI/CD/CT for iOS and Android with online device emulators. 20 minutes build timeout (60 mins for Open Source) with single concurrency for free.
  * [appveyor.com](https://www.appveyor.com/) — Windows 的 CD 服务，开源免费
  * [bitrise.io](https://www.bitrise.io/) — A CI/CD for mobile apps, native or hybrid. With 200 free builds/month 10 min build time and two team members. OSS projects get 45 min build time, +1 concurrency and unlimited team size.
  * [buddy.works](https://buddy.works/) — 包含 5 个免费项目和 1 个并发运行的 CI/CD（120 次执行/月）
  * [buddybuild.com](https://www.buddybuild.com/) — 在一个无缝的迭代系统中为您的 iOS 和 Android 应用程序构建、部署和收集反馈
  * [circleci.com](https://circleci.com/) — 一个并发构建免费
  * [cirrus-ci.org](https://cirrus-ci.org) - 公共 GitHub 存储库免费
  * [codefresh.io](https://codefresh.io) — Free-for-Life plan: 1 build, 1 environment, shared servers, unlimited public repos
  * [codemagic.io](https://codemagic.io/) - 每月免费 500 分钟构建
  * [codeship.com](https://codeship.com/) — 每月 100 个私有构建，5 个私有项目，开源无限制
  * [Continuous PHP](https://continuousphp.com/) — continuousphp is the first and only PHP-centric Platform to build, package, test and deploy applications in the same workflow. Free for Community Projects i.e. OSS/Public/Educational projects.
  * [deployhq.com](https://www.deployhq.com/) — 1 个项目，每天进行 10 次部署（每月 30 分钟构建）
  * [drone](https://cloud.drone.io/) - Drone Cloud enables developers to run Continuous Delivery pipelines across multiple architectures - including x86 and Arm (both 32 bit and 64 bit) - all in one place
  * [LayerCI](https://layerci.com)  — 全栈项目的 CI.  1 个具有 5GB 内存和 3 个 CPU 的完整堆栈预览环境.
  * [ligurio/awesome-ci](https://github.com/ligurio/awesome-ci) — Comparison of Continuous Integration services
  * [Octopus Deploy](https://octopus.com) - Automated deployment and release-management. Free for <= 10 deployment targets.
  * [scalr.com](https://scalr.com/)  - Terraform 的远程状态和操作后端，具有完整的 CLI 支持、与 OPA 的集成和分层配置模型. 最多释放 5 个用户.
  * [semaphoreci.com](https://semaphoreci.com/) — Free for Open Source, 100 private builds per month
  * [Squash Labs](https://www.squash.io/) — creates a VM for each branch and makes your app available from a unique URL, Unlimited public & private repos, Up to 2 GB VM Sizes.
  * [stackahoy.io](https://stackahoy.io)  — 100% 免费. 无限的部署、分支和构建
  * [styleci.io](https://styleci.io/) — 仅限公共 GitHub 存储库
  * [Mergify](https://mergify.io) — GitHub 的工作流自动化和合并队列 — 公共 GitHub 存储库免费
  * [Integromat](https://www.integromat.com) — Workflow automation tool which lets you connect apps and automate workflows using UI, it supports many apps and most popular APIs. Free for public GitHub repositories, and free tier with 100 Mb, 1000 Operations and 15 minutes of minimum interval.



## Testing

  * [Applitools.com](https://applitools.com/)  — 针对 Web、本地移动和桌面应用程序的智能视觉验证. 与几乎所有自动化解决方案（如 Selenium 和 Karma）和远程运行器（Sauce Labs、Browser Stack）集成. 免费用于开源. 每周检查点有限的单个用户的免费套餐.
  * [Appetize](https://appetize.io)  — 直接在浏览器中在此基于云的 Android 手机/平板电脑模拟器和 iPhone/iPad 模拟器上测试您的 Android 和 iOS 应用程序. 免费套餐包括 1 个并发会话，每月使用 100 分钟. 应用程序大小没有限制.
  * [Bird Eats Bug](https://www.birdeatsbug.com/) — Report bugs faster (and better). Record your screen with Bird browser extension, it will auto-capture technical data that engineers need to debug. Free tier suitable for small teams.
  * [lambdatest.com](https://www.lambdatest.com/) — Manual, visual, screenshot and automated browser testing on selenium and cypress, [free for Open Source](https://www.lambdatest.com/open-source-cross-browser-testing-tool)
  * [browserstack.com](https://www.browserstack.com/) — 手动和自动浏览器测试， [free for Open Source](https://www.browserstack.com/open-source?ref=pricing)
  * [checkbot.io](https://www.checkbot.io/)  — 测试您的网站是否遵循 50 多个 SEO、速度和安全最佳实践的浏览器扩展. 小型网站的免费套餐.
  * [checklyhq.com](https://checklyhq.com)  - Checkly 是现代堆栈的 API 和 E2E 监控平台：可编程、灵活和热爱 JavaScript. 为开发人员提供的免费套餐.
  * [crossbrowsertesting.com](https://crossbrowsertesting.com) - 云中的手动、可视化和 Selenium 浏览器测试 - [free for Open Source](https://crossbrowsertesting.com/open-source)
  * [cypress.io](https://www.cypress.io/)  - 对在浏览器中运行的任何东西进行快速、简单和可靠的测试.  Cypress Test Runner 始终是免费和开源的，没有任何限制和限制.  Cypress Dashboard 对最多 5 个用户的开源项目是免费的.
  * [everystep-automation.com](https://www.everystep-automation.com/) — Records and replays all steps made in a web browser and creates scripts,... free with fewer options
  * [Gremlin](https://www.gremlin.com/gremlin-free-software)  — Gremlin 的混沌工程工具允许您安全、可靠、简单地将故障注入您的系统，以便在它们导致面向客户的问题之前发现弱点.  Gremlin Free 提供对多达 5 个主机或容器的关闭和 CPU 攻击的访问权限.
  * [gridlastic.com](https://www.gridlastic.com/) — Selenium Grid testing with free plan up to 4 simultaneous selenium nodes/10 grid starts/4,000 test minutes/month
  * [loadmill.com](https://www.loadmill.com/)  - 通过分析网络流量自动创建 API 和负载测试. 每月免费模拟多达 50 个并发用户长达 60 分钟.
  * [percy.io](https://percy.io)  - 将可视化测试添加到任何 Web 应用程序、静态站点、样式指南或组件库. 无限的团队成员，演示应用程序和无限的项目，5,000 个快照/月.
  * [reflect.run](https://reflect.run)  - Web 应用程序的无代码自动化测试. 测试可以在应用程序内安排或从 CI/CD 工具执行. 每次测试运行都包括完整的视频记录以及控制台和网络日志. 免费套餐包括无限数量的已保存测试，每月运行 25 次测试，最多 3 位用户.
  * [saucelabs.com](https://saucelabs.com/) — 跨浏览器测试、Selenium 测试和移动测试， [free for Open Source](https://saucelabs.com/open-source)
  * [snippets.uilicious.com](https://snippets.uilicious.com) - It's like CodePen, but for cross browser testing. UI-licious lets write tests like user stories, and offers a free platform - UI-licious Snippets - that allows you to run unlimited number of tests on Chrome for free with no sign up requred, for up to 3 minutes per test run. Found a bug? You can simply copy the unique url to your test to show your devs exactly how to reproduce the bug.
  * [testingbot.com](https://testingbot.com/) — Selenium Browser and Device Testing, [free for Open Source](https://testingbot.com/open-source)
  * [Testspace.com](https://testspace.com/) - A Dashboard for publishing automated test results and a Framework for implementing manual tests as code using GitHub. The service is [free for Open Source](https://github.com/marketplace/testspace-com) 每月有 450 个结果.
  * [tesults.com](https://www.tesults.com) — Test results reporting and test case management. Integrates with popular test frameworks. Open Source software developers, individuals, educators, and small teams getting started can request discounted and free offerings beyond basic free project.
  * [websitepulse.com](https://www.websitepulse.com/tools/) — Various free network and server tools.
  * [qase.io](https://qase.io) - Test management system for Dev and QA teams. Manage test cases, compose test runs, perform test runs, track defects and measure impact. The free tier includes all core features, with 500Mb available for attachments and up to 3 users.
  * [knapsackpro.com](https://knapsackpro.com) - Speed up your tests with optimal test suite parallelisation on any CI provider. Split Ruby, JavaScript tests on parallel CI nodes to save time. Free plan for up to 10 minutes test files and free unlimited plan for Open Source projects.
  * [webhook.site](https://webhook.site) - Verify webhooks, outbound HTTP requests, or emails with a custom URL.  Temporary URL and email address is always free.
  * [Vaadin](https://vaadin.com) — Build scalable UIs in Java or TypeScript, and use the integrated tooling, components and design system to iterate faster, design better and simplify the development process. Unlimited Projects with 5 years free maintenance.
  * [Foresight](https://thundra.io/foresight) — Thundra Foresight 是一种工具，用于立即调试和排除测试故障，并优化 CI 管道中的构建持续时间和性能.


## Security and PKI

  * [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — 发现网络中的受损系统
  * [atomist.com](https://atomist.com/)  — 一种更快、更方便的方式来自动化各种开发任务. 现在处于测试阶段.
  * [auth0.com](https://auth0.com/) — Hosted free for development SSO. Up to 2 social identity providers for closed-source projects.
  * [Authgear](https://www.authgear.com) - Bring Passwordless, OTPs, 2FA, SSO to your apps in minutes. All Front-end included. Free up to 5000 MAUs.
  * [Authress](https://authress.io/) — Authentication login and access control, unlimited identity providers for any project. Facebook, Google, Twitter and more. First 1000 API calls are free.
  * [Authy](https://authy.com) - Two-factor authentication (2FA) on multiple devices, with backups. Drop-in replacement for Google Authenticator. Free for up to 100 successful authentications.
  * [Bridgecrew](https://bridgecrew.io/) — Infrastructure as code (IaC) security powered by the open source tool - [Checkov](https://github.com/bridgecrewio/checkov). The core Bridgecrew platform is free for up to 50 IaC resources.
  * [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services (AWS) security and compliance auditing and monitoring
  * [Cmd](https://cmd.com/) — Security platform providing real-time access control and dynamic policy enforcement on every Linux instance in your cloud or datacenter
  * [CodeNotary.io](https://www.codenotary.io/) — 具有不可磨灭证据的开源平台，可对代码、文件、目录或容器进行公证
  * [crypteron.com](https://www.crypteron.com/) — Cloud-first, developer-friendly security platform prevents data breaches in .NET and Java applications
  * [Datree](https://www.datree.io/) — 开源 CLI 工具通过确保清单和 Helm 图表遵循最佳实践以及您的组织的政策来防止 Kubernetes 错误配置
  * [Dependabot](https://dependabot.com/) Automated dependency updates for Ruby, JavaScript, Python, PHP, Elixir, Rust, Java (Maven and Gradle), .NET, Go, Elm, Docker, Terraform, Git Submodules and GitHub Actions.
  * [DJ Checkup](https://djcheckup.com) — Scan your Django site for security flaws with this free, automated, checkup tool. Forked from the Pony Checkup site.
  * [Doppler](https://doppler.com/)  — 用于应用程序机密和配置的 Universal Secrets Manager，支持与各种云提供商同步. 对具有基本访问控制的无限用户免费.
  * [duo.com](https://duo.com/) — Two-factor authentication (2FA) for website or app. Free for 10 users, all authentication methods, unlimited, integrations, hardware tokens.
  * [GitGuardian](https://www.gitguardian.com)  — 通过自动化的秘密检测和修复，将秘密远离源代码. 扫描您的 git 存储库以查找 350 多种类型的机密和敏感文件 - 免费供 25 名或更少开发人员的个人和团队使用.
  * [globalsign.com](https://www.globalsign.com/en/ssl/ssl-open-source/) — 开源的免费 SSL 证书
  * [Have I been pwned?](https://haveibeenpwned.com) — REST API for fetching the information on the breaches.
  * [hostedscan.com](https://hostedscan.com) — Online vulnerability scanner for web applications, servers, and networks. 10 free scans per month.
  * [Internet.nl](https://internet.nl) — Test for modern Internet Standards like IPv6, DNSSEC, HTTPS, DMARC, STARTTLS and DANE
  * [Jumpcloud](https://jumpcloud.com/) — Provides directory as a service similar to Azure AD, user management, single sign-on, and RADIUS authentication. Free for up to 10 users.
  * [keychest.net](https://keychest.net) - SSL expiry management and cert purchase with an integrated CT database
  * [letsencrypt.org](https://letsencrypt.org/) — 免费的 SSL 证书颁发机构，其证书受到所有主要浏览器的信任
  * [LoginRadius](https://www.loginradius.com/)  — 免费的托管用户身份验证服务. 电子邮件注册和 3 个社交服务提供商.
  * [logintc.com](https://www.logintc.com/) — 通过推送通知进行的两因素身份验证 (2FA)，10 位用户、VPN、网站和 SSH 免费
  * [meterian.io](https://www.meterian.io/) - Monitor Java, Javascript, .NET, Scala, Ruby and NodeJS projects for security vulnerabilities in dependencies. Free for one private project, unlimited projects for open source.
  * [MojoAuth](https://mojoauth.com/) - MojoAuth makes it easy to implement Passwordless authentication on your web, mobile or any application in minutes.
  * [Mozilla Observatory](https://observatory.mozilla.org/) — 查找并修复您网站中的安全漏洞.
  * [Okta](https://developer.okta.com/)  — 用户管理、认证和授权. 每月最多 1000 名活跃用户免费.
  * [onelogin.com](https://www.onelogin.com/) — 身份即服务 (IDaaS)、单点登录身份提供商、云 SSO IdP、3 个公司应用程序和 5 个个人应用程序、无限用户
  * [Operous](https://operous.dev/)  — 云实例测试工具，具有一套全面、自动化的最佳实践、性能和安全性测试套件. 免费套餐为 1 位用户提供 100 分钟测试时间、10 个测试套件和最多 5 个实例.
  * [opswat.com](https://www.opswat.com/) — Security Monitoring of computers, devices, applications, configurations,... Free 25 users and 30 days history users.
  * [pyup.io](https://pyup.io)  — 监控 Python 依赖项是否存在安全漏洞并自动更新它们. 一个私人项目免费，开源项目无限.
  * [qualys.com](https://www.qualys.com/community-edition) — 查找 Web 应用程序漏洞，审核 OWASP 风险
  * [reCAPTCHAMe](https://recaptchame.com/) — free reCAPTCHA and hCAPTCHA backend service. No Server-Side coding needed. Works for static websites.
  * [report-uri.io](https://report-uri.io/) — CSP 和 HPKP 违规报告
  * [ringcaptcha.com](https://ringcaptcha.com/) — Tools to use phone number as id, available for free
  * [sawolabs.com](https://sawolabs.com/)  - 通过在您的应用程序中集成无密码身份验证来简化登录并改善用户体验. 每月 5000 次免费认证.
  * [snyk.io](https://snyk.io)  — 可以在您的开源依赖项中找到并修复已知的安全漏洞. 开源项目的无限测试和修复. 您的私人项目每月限制为 200 次测试.
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) — 对任何 SSL Web 服务器的配置进行非常深入的分析
  * [StackHawk](https://www.stackhawk.com/) 在整个管道中自动进行应用程序扫描，以在安全漏洞投入生产之前发现并修复它们. 单个应用程序的无限扫描和环境.
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) - Free website security check and malware scanner
  * [Protectumus](https://protectumus.com)  - 免费的网站安全检查、网站防病毒和 PHP 的服务器防火墙 (WAF). 免费套餐中注册用户的电子邮件通知.
  * [TestTLS.com](https://testtls.com) - Test a SSL/TLS service for secure server configuration, certificates, chains etc. Not limited to HTTPS.
  * [threatconnect.com](https://threatconnect.com) — Threat intelligence: It is designed for individual researchers, analysts and organizations who are starting to learn about cyber threat intelligence. Free up to 3 Users
  * [tinfoilsecurity.com](https://www.tinfoilsecurity.com/)  — 自动漏洞扫描. 免费计划允许每周 XSS 扫描
  * [Ubiq Security](https://ubiqsecurity.com/)  — 使用 3 行代码和自动密钥管理加密和解密数据.  1 个应用程序和每月最多 1,000,000 次加密免费.
  * [Virgil Security](https://virgilsecurity.com/) — Tools and services for implementing end-to-end encryption, database protection, IoT security and more in your digital solution. Free for applications with up to 250 users.
  * [Virushee](https://virushee.com/) — Privacy-oriented file/data scanning powered by hybrid heuristic and AI-assisted engine. Possible to use internal dynamic sandbox analysis. Limited to 50MB per file upload
  * [Warrant](https://warrant.dev/)  — 为您的应用托管企业级授权和访问控制服务. 免费套餐包括每月 5,000 个 API 请求.
  * [Escape GraphQL Quickscan](https://escape.tech/quickscan) - One-click security scan of your GraphQL endpoints. Free, no login required.


## Management System

  * [bitnami.com](https://bitnami.com/) — Deploy prepared apps on IaaS. Management of 1 AWS micro instance free
  * [Esper](https://esper.io)  — 适用于具有 DevOps 的 Android 设备的 MDM 和 MAM.  100 台设备免费，1 个用户许可证和 25 MB 应用程序存储.
  * [jamf.com](https://www.jamf.com/) — iPad、iPhone 和 Mac 的设备管理，3 台设备免费
  * [Miradore](https://miradore.com)  — 设备管理服务. 随时了解您的设备群并免费保护无限数量的设备. 免费计划提供基本功能.
  * [moss.sh](https://moss.sh)  - 帮助开发人员部署和管理他们的 Web 应用程序和服务器. 每月最多释放 25 次 git 部署
  * [runcloud.io](https://runcloud.io/)  - 服务器管理主要集中在 PHP 项目上. 最多可免费使用 1 台服务器.
  * [ploi.io](https://ploi.io/)  - 服务器管理工​​具，可轻松管理和部署您的服务器和站点.  1台服务器免费.


## Messaging and Streaming

  * [Ably](https://www.ably.com/) - Realtime messaging service with presence, persistence and guaranteed delivery. Free plan includes 3m messages per month, 100 peak connections and 100 peak channels.
  * [cloudamqp.com](https://www.cloudamqp.com/)  — RabbitMQ 即服务.  Little Lemur 计划：每月最多 100 万条消息，最多 20 个并发连接，最多 100 个队列，最多 10,000 个排队消息，不同 AZ 的多个节点
  * [connectycube.com](https://connectycube.com)  - 无限的聊天消息、p2p 语音和视频通话、文件附件和推送通知. 免费提供高达 20K MAU 的应用程序.
  * [courier.com](https://www.courier.com/)  — 用于推送、应用内、电子邮件、聊天、短信和其他消息渠道的单一 API，具有模板管理和其他功能. 免费计划包括 10,000 条消息/月.
  * [pusher.com](https://pusher.com/)  — 实时消息服务. 免费提供多达 100 个同时连接和 200,000 条消息/天
  * [scaledrone.com](https://www.scaledrone.com/)  — 实时消息服务. 免费提供多达 20 个同时连接和 100,000 个事件/天
  * [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io) 作为一项服务. 全球、AWS、GCP 和 Azure. 每月 4k 消息大小、50 个活动连接和 5GB 数据，永久免费.
  * [cloudkarafka.com](https://www.cloudkarafka.com/) - 免费共享 Kafka 集群，最多 5 个主题，每个主题 10MB 数据和 28 天数据保留.
  * [pubnub.com](https://www.pubnub.com/) - Swift, Kotlin and React messaging at 1 million transactions each month. Transactions may contain multiple messages.
  * [eyeson API](https://developers.eyeson.team/) - A video communication API service based on WebRTC (SFU, MCU) to build video platforms. Allows RealTime Data Injection, Video Layouts, Recordings, a fully featured hosted web UI (quickstart) or packages for custom UIs. Has a [free tier for developers](https://apiservice.eyeson.com/api-pricing) 每月 1000 次会议记录.


## Log Management

  * [bugfender.com](https://bugfender.com/) — 每天最多释放 10 万条日志行，24 小时保留
  * [humio.com](https://www.humio.com/) — Free up to 2 GB/day with 7 days retention
  * [logdna.com](https://logdna.com) - 单个用户免费，无保留，无限主机和来源
  * [logentries.com](https://logentries.com/) — 每月最多免费 5 GB，保留 7 天
  * [loggly.com](https://www.loggly.com/) — 单个用户免费，请参阅 lite 选项
  * [logz.io](https://logz.io/) — 每天最多免费 3 GB，保留 3 天
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-log-management) — Log Management service powered by Manage Engine. Free Plan offers 50 GB storage with 1 Month retention.
  * [papertrailapp.com](https://papertrailapp.com/) — 48 小时搜索，7 天存档，100 MB/月
  * [sematext.com](https://sematext.com/logsene) — Free up to 500 MB/day, 7 days retention
  * [sumologic.com](https://www.sumologic.com/) — Free up to 500 MB/day, 7 days retention
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
  * [oneskyapp.com](https://www.oneskyapp.com/) — Limited free edition for up to 5 users, free for Open Source
  * [POEditor](https://poeditor.com/) — 最多释放 1000 个字符串
  * [SimpleLocalize](https://simplelocalize.io/) - Free up to 100 translation keys, unlimited strings, unlimited languages, startup deals
  * [Texterify](https://texterify.com/) - Free for a single user
  * [transifex.com](https://www.transifex.com/) — Free for Open Source
  * [Translation.io](https://translation.io) - Free for Open Source
  * [webtranslateit.com](https://webtranslateit.com/) — 最多释放 500 个字符串
  * [weblate.org](https://weblate.org/) — It's free for libre projects up to 10,000 string source for the free tier, and Unlimited Self-hosted on-premises.
  * [Free PO editor](https://pofile.net/free-po-editor) — 对所有人免费


## Monitoring

  * [Pingmeter.com](https://pingmeter.com/)  - 5 个正常运行时间监视器，间隔 10 分钟. 监控 SSH、HTTP、HTTPS 和任何自定义 TCP 端口.
  * [amixr.io](https://amixr.io/) - Developer-friendly alerting and on-call management with brilliant Slack Integration, API and Terraform. Free phone call, SMS, Telegram, Slack and E-Mail packages.
  * [appdynamics.com](https://www.appdynamics.com/) — Free for 24 hours metrics, application performance management agents limited to one Java, one .NET, one PHP and one Node.js
  * [appneta.com](https://www.appneta.com/) — 免费，数据保留 1 小时
  * [assertible.com](https://assertible.com)  — 自动化 API 测试和监控. 团队和个人的免费计划.
  * [blackfire.io](https://blackfire.io/)  — Blackfire 是 SaaS 交付的应用程序性能解决方案. 免费黑客计划（仅限 PHP）
  * [checklyhq.com](https://checklyhq.com)  - 面向开发人员的开源 E2E / 综合监控和深度 API 监控. 包含 5 个用户和 50k+ 检查运行的免费计划.
  * [circonus.com](https://www.circonus.com/) — Free for 20 metrics
  * [cloudsploit.com](https://cloudsploit.com)  — AWS 安全和配置监控. 免费：无限制的按需扫描、无限制的用户、无限制的存储帐户. 订阅：自动扫描、API访问等.
  * [datadoghq.com](https://www.datadoghq.com/) — 最多 5 个节点免费
  * [deadmanssnitch.com](https://deadmanssnitch.com/) — Monitoring for cron jobs. 1 free snitch (monitor), more if you refer others to sign up
  * [economize.cloud](https://economize.cloud) — Economize helps demystify cloud infrastructure costs by organizing cloud resources, optimize and report the same. Free for up to $5000 spends on Google Cloud Platform every month.
  * [elastic.co](https://www.elastic.co/solutions/apm) — Instant performance insights for JS developers. Free with 24 hours data retention
  * [freeboard.io](https://freeboard.io/) — Free for public projects. Dashboards for your Internet of Things (IoT) projects
  * [freshworks.com](https://www.freshworks.com/website-monitoring/) — Monitor 50 URLs at 1-minute interval with 10 Global locations and 5 Public status pages for Free
  * [gitential.com](https://gitential.com) — Software Development Analytics platform. Free: unlimited public repositories, unlimited users, free trial for private repos. On-prem version available for enterprise.
  * [Grafana Cloud](https://grafana.com/products/cloud/) - Grafana Cloud is a composable observability platform, integrating metrics and logs with Grafana. Free: 3 users, 10 dashboards, 100 alerts, metrics storage in Prometheus and Graphite (10,000 series, 14 days retention), logs storage in Loki (50 GB of logs, 14 days retention)
  * [healthchecks.io](https://healthchecks.io) — Monitor your cron jobs and background tasks. Free for up to 20 checks.
  * [inspector.dev](https://www.inspector.dev) - A complete Real-Time monitoring dashboard in less than one minute with free forever tier.
  * [instrumentalapp.com](https://instrumentalapp.com) - Beautiful and easy-to-use application and server monitoring with up to 500 metrics and 3 hours of data visibility for free
  * [keychest.net/speedtest](https://keychest.net/speedtest) - 针对 Digital Ocean 的独立速度测试和 TLS 握手延迟测试
  * [letsmonitor.org](https://letsmonitor.org) - SSL 监控，最多可免费使用 5 台显示器
  * [loader.io](https://loader.io/) — 有限制的免费负载测试工具
  * [meercode.io](https://meercode.io/) — Meercode is the ultimate monitoring dashboard for your CI/CD builds. Free for open-source and 1 private repository.
  * [netdata.cloud](https://www.netdata.cloud/)  — Netdata 是一个开源工具，旨在收集实时指标.快速增长的产品. 也可以在github上找到！
  * [newrelic.com](https://www.newrelic.com) — New Relic observability platform built to help engineers create more perfect software. From monoliths to serverless, you can instrument everything, then analyze, troubleshoot, and optimize your entire software stack. Free tier offers 100GB/month of free data ingest, 1 free full access user, and unlimited free basic users.
  * [nixstats.com](https://nixstats.com) - Free for one server. E-Mail Notifications, public status page, 60 second interval and more.
  * [OnlineOrNot.com](https://onlineornot.com/)  - OnlineOrNot 是基于 JS 的 Web 应用程序和网站的可靠正常运行时间监视器.  10 次正常运行时间检查（针对静态网站和 API），间隔 5 分钟，1 次浏览器检查，间隔 15 分钟. 最多 3 位用户免费，通过 Slack、Discord 和电子邮件发送警报.
  * [opsgenie.com](https://www.opsgenie.com/) — Powerful alerting and on-call management for operating always-on services. Free up to 5 users.
  * [paessler.com](https://www.paessler.com/) — Powerful infrastructure and network monitoring solution including alerting, strong visualization capabilities and basic reporting. Free up to 100 sensors.
  * [syagent.com](https://syagent.com/) — 非商业免费服务器监控服务、警报和指标.
  * [pagertree.com](https://pagertree.com/)  - 用于警报和待命管理的简单界面. 最多释放 5 个用户.
  * [pingbreak.com](https://pingbreak.com/) — Modern uptime monitoring service. Check unlimited URLs and get downtime notifications via Discord, Slack or email.
  * [pingpong.one](https://pingpong.one/)  — 具有监控功能的高级状态页面平台. 免费套餐包括一个带有 SSL 子域的公共可定制状态页面. 专业计划免费提供给开源项目和非营利组织.
  * [sematext.com](https://sematext.com/) — 免费提供 24 小时指标、无限数量的服务器、10 个自定义指标、500,000 个自定义指标数据点、无限的仪表板、用户等.
  * [sitemonki.com](https://sitemonki.com/) — Website, domain, Cron & SSL monitoring, 5 monitors in each category for free
  * [skylight.io](https://www.skylight.io/) — 前 100,000 个请求免费（仅限 Rails）
  * [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — 性能监控 API，检查 Ping、DNS 等.
  * [stathat.com](https://www.stathat.com/) — 免费开始使用 10 个统计数据，没有过期
  * [statuscake.com](https://www.statuscake.com/) — 网站监控，无限制的免费测试
  * [statusgator.com](https://statusgator.com/) — Status page monitoring, 3 monitors free
  * [thousandeyes.com](https://www.thousandeyes.com/) — Network and user experience monitoring. 3 locations and 20 data feeds of major web services free
  * [thundra.io/apm](https://www.thundra.io/apm)  — 应用程序监控和调试. 拥有每月最多 25 万次调用的免费套餐.
  * [uptimerobot.com](https://uptimerobot.com/) — Website monitoring, 50 monitors free
  * [uptimetoolbox.com](https://uptimetoolbox.com/) — Free monitoring for 5 websites, 60 second intervals, public statuspage.
  * [zenduty.com](https://www.zenduty.com/)  — 用于网络运营、站点可靠性工程和 DevOps 团队的端到端事件管理、警报、待命管理和响应编排平台. 最多 5 位用户免费.
  * [asayer.io](https://asayer.io/pricing.html)  — openreplay 的托管版本，一种开源会话重播（FullStory 和 LogRocket 的替代品）. 每月免费 1k 次会话，保留 14 天
  * [lean20.com](https://lean20.com/product/status/) - Public status pages for incident reporting. 100% free.
  * [instatus.com](https://instatus.com) - Get a beautiful status page in 10 seconds. Free forever with unlimited subs and unlimited teams.
  * [Squadcast.com](https://squadcast.com) - Squadcast is an end-to-end incident management software that's designed to help you promote SRE best practices. Free forever plan available for upto 10 users.


## Crash and Exception Handling

  * [CatchJS.com](https://catchjs.com/)  - 带有屏幕截图和点击跟踪的 JavaScript 错误跟踪. 对开源项目免费.
  * [bugsnag.com](https://www.bugsnag.com/) — 初次试用后每月最多 2,000 个错误免费
  * [exceptionless](https://exceptionless.com)  — 实时错误、功能、日志报告等. 每月/1 位用户可免费参加 3k 次活动. 开源且易于自托管，可无限使用.
  * [GlitchTip](https://glitchtip.com/) — Simple, open source error tracking. Compatible with open-source Sentry SDKs. 1000 events per month for free, or can self-host with no limits
  * [honeybadger.io](https://www.honeybadger.io) - Exception, uptime, and cron monitoring. Free for small teams and open-source projects (12,000 errors/month).
  * [rollbar.com](https://rollbar.com/) — 异常和错误监控、每月 5,000 个错误的免费计划、无限用户、30 天保留
  * [sentry.io](https://sentry.io/) — Sentry tracks app exceptions in real-time, has a small free plan. Free for 5k errors per month/ 1 user, unrestricted use if self-hosted


## Search

  * [algolia.com](https://www.algolia.com/)  — 托管搜索即键入（即时）. 免费黑客计划多达 10,000 个文档和 100,000 次操作. 更大的免费计划可用于社区/开源项目
  * [bonsai.io](https://bonsai.io/) — Free 1 GB memory and 1 GB storage
  * [searchly.com](http://www.searchly.com/) — Free 2 indices and 20 MB storage
  * [pagedart.com](https://pagedart.com/) - AI search as a service the free tier includes 1000 Documents, 50000 searches. Larger free tiers are possible for worthwhile projects.


## Email

  * [10minutemail](https://10minutemail.com) - Free, temporary email for testing.
  * [AnonAddy](https://anonaddy.com) - 开源匿名邮件转发，免费创建无限邮件别名
  * [Antideo](https://www.antideo.com) — 10 API requests per hour for email verification, IP and phone number validation in free tier. No Credit Cards required.
  * [biz.mail.ru](https://biz.mail.ru/) — 5,000 mailboxes with 25 GB each per custom domain with DNS hosting
  * [Bump](https://bump.email/) - 免费 10 个 Bump 电子邮件地址，1 个自定义域
  * [Burnermail](https://burnermail.io/) – 免费 5 个 Burner 电子邮件地址、1 个邮箱、7 天邮箱历史记录
  * [Buttondown](https://buttondown.email/)  — 通讯服务. 多达 1,000 名免费订阅者
  * [CloudMailin](https://www.cloudmailin.com/) - 通过 HTTP POST 和事务出站接收电子邮件 - 每月 10,000 封免费电子邮件
  * [cloudmersive.com](https://www.cloudmersive.com/email-verification-api) — 面向开发人员的电子邮件验证和验证 API，每月 2,000 个免费 API 请求
  * [Contact.do](https://contact.do/) - 链接中的联系表格（联系表格有点） - 完全免费！
  * [debugmail.io](https://debugmail.io/) — 易于开发人员使用的测试邮件服务器
  * [Email Temporanee](https://emailtemporanee.com/)  - 易于使用的免费无限一次性临时电子邮件地址（临时电子邮件）. 自动过期，即使你可以设置它的一天.
  * [elasticemail.com](https://elasticemail.com) — 100 free emails/day. 1,000 emails for $0.09 through API (pay as you go).
  * [EmailOctopus](https://emailoctopus.com) - 每月免费订阅多达 2,500 名订阅者和 10,000 封电子邮件
  * [Eva](https://eva.pingutil.com) — Verify 5 million emails per day for free using REST API. No sign-ups required.
  * [fakermail.com](https://fakermail.com/) — 用于测试的免费临时电子邮件，存储了最后 100 个电子邮件帐户.
  * [forwardemail.net](https://forwardemail.net) — Free email forwarding for custom domains. Create and forward an unlimited amount of email addresses with your domain name (**note**: You must pay if you use .casa, .cf, .click, .email, .fit, .ga, .gdn, .gq, .loan, .london, .men, .ml, .pl, .rest, .ru, .tk, .top, .work TLDs due to spam)
  * [ImprovMX](https://improvmx.com) - 免费电子邮件转发
  * [inboxkitten.com](https://inboxkitten.com/)  - 免费的临时/一次性电子邮件收件箱，最多可自动删除 3 天的电子邮件. 开源，可以自托管.
  * [inumbo.com](http://inumbo.com/) — SMTP based spam filter, free for 10 users
  * [kickbox.io](https://kickbox.io/) — 免费验证 100 封电子邮件，提供实时 API
  * [mail.gw](https://mail.gw) — 10 Minute Mail. Free anonymous temporary email without obligations.
  * [mail.tm](https://mail.tm)  — 具有用户友好界面的一次性电子邮件. 无需注册.
  * [mailazy.com](https://mailazy.com/) — Mailazy is the only simple transactional email service you’ll need. 15,000 emails/month free forever (500 emails/day sending limit).
  * [mail-tester.com](https://www.mail-tester.com) — Test if email's dns/spf/dkim/dmarc settings are correct, 20 free/month
  * [dkimvalidator.com](https://dkimvalidator.com/) - 测试电子邮件的 dns/spf/dkim/dmarc 设置是否正确，roundsphere.com 提供免费服务
  * [mailboxlayer.com](https://mailboxlayer.com/) — Email validation and verification JSON API for developers. 1,000 free API requests/month
  * [mailcatcher.me](https://mailcatcher.me/) — Catches mail and serves it through a web interface
  * [mailchimp.com](https://mailchimp.com/) — 2,000 名订阅者和 12,000 封电子邮件/月免费
  * [MailerLite.com](https://www.mailerlite.com) — 1,000 名订阅者/月，12,000 封电子邮件/月免费
  * [mailinator.com](https://www.mailinator.com/) — 免费的公共电子邮件系统，您可以在其中使用任何您想要的收件箱
  * [mailjet.com](https://www.mailjet.com/) — 6,000 emails/month free (200 emails daily sending limit)
  * [mailkitchen](https://www.mailkitchen.com/) — Free for life without commitment, 10,000 emails/month, 1,000 emails/day
  * [mailmenot.io](http://mailmenot.io) — 免费的一次性临时电子邮件服务，能够添加多个电子邮件地址
  * [Mailnesia](https://mailnesia.com) - 免费的临时/一次性电子邮件，自动访问注册链接.
  * [mailsac.com](https://mailsac.com) - Free API for temporary email testing, free public email hosting, outbound capture, email-to-slack/websocket/webhook (1,500 monthly API limit)
  * [Mailtie.com](https://mailtie.com/)  - 您的域的免费电子邮件转发. 无需注册. 永远免费.
  * [mailtrap.io](https://mailtrap.io/) — Fake SMTP server for development, free plan with 1 inbox, 50 messages, no team member, 2 emails/second, no forward rules
  * [mailvalidator.io](https://mailvalidator.io/) - 每月免费验证 300 封电子邮件，提供批量处理的实时 API
  * [mail7.io](https://www.mail7.io/)  — QA 开发人员的免费临时电子邮件地址. 使用 Web 界面或 API 立即创建电子邮件地址
  * [mohmal.com](https://www.mohmal.com/en) — 一次性临时电子邮件
  * [moosend.com](https://moosend.com/) — Mailing list management service. Free account for 6 months for startups
  * [Outlook.com](https://outlook.live.com/owa/) - 免费的个人电子邮件和日历
  * [Parsio.io](https://parsio.io) - 免费电子邮件解析器（转发电子邮件，提取数据，将其发送到您的服务器）
  * [pepipost.com](https://pepipost.com) — 30k emails free for first month, then first 100 emails/day free
  * [phplist.com](https://phplist.com/) — 托管版本允许每月免费发送 300 封电子邮件
  * [postmarkapp.com](https://postmarkapp.com/) - 100 封电子邮件/月免费，无限制的 DMARC 每周摘要
  * [QuickEmailVerification](https://quickemailverification.com) — Verify 100 emails daily for free on a free tier along with other free APIs like DEA Detector, DNS Lookup, SPF Detector and more.
  * [Sender](https://www.sender.net) Up to 15 000 emails/month - Up to 2 500 subscribers
  * [sendgrid.com](https://sendgrid.com/) — 每天 100 封电子邮件和 2,000 个免费联系人
  * [sendinblue.com](https://www.sendinblue.com/) — 9,000 emails/month free
  * [sendpulse.com](https://sendpulse.com) — 50 封电子邮件/小时免费，前 12,000 封电子邮件/月免费
  * [socketlabs.com](https://www.socketlabs.com) - 40k emails free for first month, then first 2000 emails/month free
  * [sparkpost.com](https://www.sparkpost.com/) — First 500 emails/month free
  * [Substack](https://substack.com) — Unlimited free newsletter service. Start paying when you charge for it.
  * [Tempmailo](https://tempmailo.com/)  - 无限的免费临时电子邮件地址. 两天后自动过期.
  * [HotTempMail](https://hottempmail.com/) - Unlimited free temp email or disposable temporary email addresses. Autoexpires in one day.
  * [temp-mail.io](https://temp-mail.io) — Free disposable temporary email service with multiple emails at once and forwarding
  * [temp-mail.org](https://temp-mail.org) — 具有 REST API 的临时、安全、匿名、免费、一次性电子邮件地址，每天可免费从其一次性邮箱中获取 100 封电子邮件.
  * [testmail.app](https://testmail.app/) - Automate end-to-end email tests with unlimited mailboxes and a GraphQL API. 100 emails/month free forever, unlimited free for open source.
  * [tinyletter.com](https://tinyletter.com/) — 5,000 subscribers/month free
  * [trashmail.com](https://www.trashmail.com) - Free disposable email addresses with forwarding and automatic address expiration
  * [Validator.Pizza](https://www.validator.pizza/) — 检测一次性电子邮件的免费 API
  * [Verifalia](https://verifalia.com/email-verification-api)  — 带有邮箱确认和一次性电子邮件地址检测器的实时电子邮件验证 API； 每天 25 次免费电子邮件验证.
  * [verimail.io](https://verimail.io/) — Bulk and API email verification service. 100 free verifications/month
  * [Yandex.Connect](https://connect.yandex.com/pdd/) — 最多可容纳 1,000 名用户的免费电子邮件和 DNS 托管
  * [yopmail.fr](http://www.yopmail.fr/en/) — Disposable email addresses
  * [Zoho](https://www.zoho.com) — Started as an e-mail provider but now provides a suite of services out of which some of them have free plans. List of services having free plans :
     - [Email](https://zoho.com/mail) Free for 5 users. 5GB/user & 25 MB attachment limit, 1 domain.
     - [Sprints](https://zoho.com/sprints) Free for 5 users,5 Projects & 500MB storage.
     - [Docs](https://zoho.com/docs)  — 5 位用户免费，具有 1 GB 上传限制和 5 GB 存储空间.  Zoho Office Suite (Writer,Sheets &amp; Show) 与它捆绑在一起.
     - [Projects](https://zoho.com/projects) — Free for 3 users, 2 projects & 10 MB attachment limit. Same plan applies to [Bugtracker](https://zoho.com/bugtracker).
     - [Connect](https://zoho.com/connect) — Team Collaboration free for 25 users with 3 groups, 3 custom apps, 3 Boards, 3 Manuals, 10 Integrations along with channels,events & forums.
     - [Meeting](https://zoho.com/meeting) — Meetings with upto 3 meeting participants & 10 Webinar attendees.
     - [Vault](https://zoho.com/vault) — Password Management free for Individuals.
     - [Showtime](https://zoho.com/showtime) — Yet another Meeting software for training for a remote session upto 5 attendees.
     - [Notebook](https://zoho.com/notebook) — Evernote 的免费替代品.
     - [Wiki](https://zoho.com/wiki) — Free for 3 users with 50 MB storage, unlimited pages, zip backups, RSS & Atom feed, access controls & customisable CSS.
     - [Subscriptions](https://zoho.com/subscriptions)  — 为 20 位客户/订阅和 1 位用户免费提供定期计费管理，所有付款托管均由 Zoho 自己完成. 存储最后 40 个订阅指标
     - [Checkout](https://zoho.com/checkout) — 3 页和最多 50 次付款的产品计费管理.
     - [Desk](https://zoho.com/desk)  — 具有 3 个代理和私人知识库、电子邮件票证的客户支持管理. 与集成 [Assist](https://zoho.com/assist) for 1 remote technician & 5 unattended computers.
     - [Cliq](https://zoho.com/cliq) — 具有 100 GB 存储空间、无限用户、每个频道 100 个用户和 SSO 的团队聊天软件.
     - [Campaigns](https://zoho.com/campaigns)
     - [Forms](https://zoho.com/forms)
     - [Sign](https:/zoho.com/sign)
     - [Surveys](https://zoho.com/surveys)
     - [Bookings](https://zoho.com/bookings)
     - [Analytics](https://zoho.com/analytics)
  * [SimpleLogin](https://simplelogin.io/)  – 开源、可自行托管的电子邮件别名/转发解决方案. 免费5个别名，无限带宽，无限回复/发送. 教育人员（学生、研究人员等）免费.
  * [EmailJS](https://www.emailjs.com/) – 这不是一个完整的电子邮件服务器，这只是电子邮件客户端，您可以使用它直接从客户端发送电子邮件而不会暴露您的凭据，免费层有：200 个每月请求，2 个电子邮件模板，请求高达 50Kb，有限的联系人历史.



## Font

  * [dafont](https://www.dafont.com/) - 本网站上呈现的字体是其作者的财产，并且是免费软件、共享软件、演示版或公共领域.
  * [Everything Fonts](https://everythingfonts.com/) - Offers multiple tools; @font-face, Units Converter, Font Hinter and Font Submitter.
  * [Font Squirrel](https://www.fontsquirrel.com/) - Freeware fonts that is licensed for commercial work. Hand-selected these typefaces and presenting them in an easy-to-use format.
  * [Google Fonts](https://fonts.google.com/) - 许多免费字体可以通过下载或指向 Google CDN 的链接轻松快速地安装在网站中.
  * [FontGet](https://www.fontget.com/) - 有多种字体可供下载，并带有标签整齐地排序.
  * [Fontshare](https://www.fontshare.com/) - is a free fonts service. It’s a growing collection of professional grade fonts that are 100% free for personal and commercial use.


## Forms

  * [99inbound.com](https://www.99inbound.com/) - Build forms and share them online. Get an email or Slack message for each submission. Free plan has 2 forms, 100 entries per month, basic email & Slack.
  * [Form.taxi](https://form.taxi/) — Endpoint for HTML forms submissions. With notifications, spam blocker and GDPR-compliant data processing. Free plan for basic usage.
  * [Formcake.com](https://formcake.com) - Form backend for devs, free plan allows unlimited forms, 100 submissions, Zapier integration. No libraries or dependencies required.
  * [Formcarry.com](https://formcarry.com) - HTTP POST Form endpoint, Free plan allows 100 submissions per month.
  * [formingo.co](https://www.formingo.co/)- Easy HTML forms for static websites, get started for free without registering an account. Free plan allows 500 submissions per month, customizable reply-to email address.
  * [formlets.com](https://formlets.com/) — 在线表格、无限制的单页表格/月、100 个提交/月、电子邮件通知.
  * [formrocket.me](https://www.formrocket.me)  - HTML 表单变得简单，无限制的表单和响应. 附带 Discord 通知等.
  * [formspark.io](https://formspark.io/) -  Form to Email service, free plan allows unlimited forms, 250 submissions per month, support by Customer assistance team.
  * [Formspree.io](https://formspree.io/)  — 使用 HTTP POST 请求发送电子邮件. 免费层级限制为每个表单每月 50 次提交.
  * [Formsubmit.co](https://formsubmit.co/) — Easy form endpoints for your HTML forms. Free Forever. No registration required.
  * [getform.io](https://getform.io/) - 设计人员和开发人员的表单后端平台，1个表单，50个提交，单个文件上传，100MB文件存储.
  * [HeroTofu.com](https://herotofu.com/) - Forms backend with bot detection and encrypted archive. Forward submissions via UI to email, Slack, or Zapier. Use your own frontend, no server code required. Free plan gives unlimited forms and 100 submissions per month.
  * [HeyForm.net](https://heyform.net/) - Drag and drop online form builder. Free tier lets you create unlimited forms and collect unlimited submissions. Comes with pre-built templates, anti-spam, and 100MB file storage.
  * [Hyperforms.app](https://hyperforms.app/) — Create form to email and more in seconds and without backend code. The Personal account gives you up to 50 form submissions per month for free.
  * [Kwes.io](https://kwes.io/) - Feature rich form endpoint. Works great with static sites. Free plan includes up 1 website with up to 50 submissions per month.
  * [Pageclip](https://pageclip.co/) - 免费计划允许一个站点、一个表单、每月 1,000 次提交.
  * [Qualtrics Survey](https://qualtrics.com/free-account) — Create professional forms & survey using this first class tool. 50+ expert-designed survey templates. Free Account has limit of 1 active survey, 100 responses/survey & 8 response types.
  * [smartforms.dev](https://smartforms.dev/) - 为您的网站提供强大而简单的表单后端，永久免费计划允许每月提交 50 次，250MB 文件存储，Zapier 集成，CSV/JSON 导出，自定义重定向，自定义响应页面，Telegram 和 Slack 机器人，单个电子邮件通知.
  * [staticforms.xyz](https://www.staticforms.xyz/) - Integrate HTML forms easily without any server side code for free. After user submits the form an email will be sent to your registered address with form content.
  * [stepFORM.io](https://stepform.io) - Quiz and Form Builder. Free plan has 5 forms, up to 3 steps per form, 50 responses per month.
  * [Typeform.com](https://www.typeform.com/)  — 在网站上包含设计精美的表格. 免费计划每个表单只允许 10 个字段和每月 100 个响应.
  * [WaiverStevie.com](https://waiverstevie.com)  - 带有 REST API 的电子签名平台. 使用 webhook 接收通知. 免费计划水印签名文件，但允许无限信封+签名.
  * [Web3Forms](https://web3forms.com)  - 静态和 JAMStack 网站的联系表格，无需编写后端代码. 免费计划允许每月不限表格、不限域和 250 次提交.
  * [WebAsk](https://webask.io)  - 调查和表格生成器. 免费计划每个帐户有 3 个调查，每月 100 个回复，每个调查 10 个元素.
  * [Wufoo](https://www.wufoo.com/) - Quick forms to use on websites. Free plan has a limit of 100 submissions each month.
  * [formpost.app](https://formpost.app)  - 免费、无限制的表格到电子邮件服务. 免费设置自定义重定向、自动响应、webhook 等.


## CDN and Protection

  * [Arvan Cloud](https://arvancloud.com/)  — 提供云相关服务（CDN、Cloud DNS、PaaS、安全等）. 免费计划提供：
    - CDN with Free SSL. 50 GB Traffic + 1 Million HTTP(S) Requests.
    - 无限域的免费云 DNS.
    - 具有基本 DDoS 保护的免费云安全 + 5 条防火墙规则.
    - Free VoD (Video On Demand) Platform with 10 GB Storage + 50 GB Traffic.
  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) — CDN for bootstrap, bootswatch and fontawesome.io
  * [cdnjs.com](https://cdnjs.com/) — Simple. Fast. Reliable. Content delivery at its finest. cdnjs is a free and open-source CDN service trusted by over 11% of all websites, powered by Cloudflare.
  * [Cloudflare](https://www.cloudflare.com/)
    * CDN along with free SSL
    * 无限数量域的免费 DNS
    * Firewall rules and pagerules
    * Analytics
    * [Cloudflare Pages](https://pages.cloudflare.com/) — Free web hosting (JAMstack platform) for frontend developers to collaborate and deploy websites. 1 build at a time, 500 builds/month, unlimited sites, unlimited requests, unlimited bandwidth.
    * [Cloudflare Workers](https://workers.cloudflare.com/) — Deploy serverless code for free on Cloudflare's global network. 100,000 free requests per day with a workers.dev subdomain.
    * [Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/run-tunnel/trycloudflare) — Create a tunnel from your server to a publically accessible, randomly-generated trycloudflare.com domain. No account required.
  * [Combinatronics](https://combinatronics.com/) - Convert your Github hosted assets (images, CSS, JS, etc.) into CDN assets. Can even render HTML files, for [example from this repo](https://combinatronics.com/ripienaar/free-for-dev/master/index.html). Similar to rawgit.com and raw.githack.com.
  * [ddos-guard.net](https://ddos-guard.net/store/web) — Free CDN, DDoS protection and SSL certificate
  * [developers.google.com](https://developers.google.com/speed/libraries/) — Google 托管库是最流行的开源 JavaScript 库的内容分发网络
  * [GraphCDN](https://graphcdn.io/) - Scale, inspect & protect your GraphQL API. 5m requests per month for free.
  * [jare.io](http://www.jare.io)  — 图像 CDN. 使用 AWS CloudFront
  * [jsdelivr.com](https://www.jsdelivr.com/)  — 一个免费、快速、可靠的开源 CDN. 支持 npm、GitHub、WordPress、Deno 等.
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — Microsoft Ajax CDN 托管流行的第三方 JavaScript 库，例如 jQuery，使您能够轻松地将它们添加到您的 Web 应用程序中
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) — Free DDoS protection and SSL certificate
  * [PageCDN.com](https://pagecdn.com/) - Offers free Public CDN for everyone, and free Private CDN for opensource / nonprofits.
  * [Skypack](https://www.skypack.dev/) — The 100% Native ES Module JavaScript CDN. Free for 1 million requests per domain, per month.
  * [raw.githack.com](https://raw.githack.com/) — A modern replacement of **rawgit.com** which simply hosts file using Cloudflare
  * [section.io](https://www.section.io/) <i>— A simple way to spin up and manage a complete Varnish Cache solution.</i> <b>— 一种启动和管理完整 Varnish Cache 解决方案的简单方法。</b> <i>Supposedly free forever for one site</i><b>据说一个网站永久免费</b>
  * [speeder.io](https://speeder.io/)  — 使用 KeyCDN. 自动图像优化和免费 CDN 提升. 免费且不需要任何服务器更改
  * [statically.io](https://statically.io/) — CDN for Git repos (GitHub, GitLab, Bitbucket), WordPress-related assets and images
  * [toranproxy.com](https://toranproxy.com/)  — Packagist 和 GitHub 的代理. 永远不会失败的CD. 免费供个人使用，1个开发者，不支持
  * [UNPKG](https://unpkg.com/) — npm 上所有内容的 CDN
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — 免费 DDoS 保护


## PaaS

  * [anvil.works](https://anvil.works) - Web app development with nothing but Python. Free tier with unlimited apps.
  * [appharbor.com](https://appharbor.com/) — 提供 1 个免费工作人员的 .Net PaaS
  * [configure.it](https://www.configure.it/) — Mobile app development platform, free for 2 projects, limited features but no resource limits
  * [codenameone.com](https://www.codenameone.com/)  — 面向 Java/Kotlin 开发人员的开源、跨平台、移动应用程序开发工具链. 免费用于商业用途，项目数量不限
  * [Deta](https://www.deta.sh)  – 免费部署无限数量的 Node.js 和 Python 应用程序. 包括免费的数据库、身份验证和电子邮件.
  * [encore.dev](https://encore.dev/)  — 使用静态分析的后端框架提供自动基础设施、无样板代码等. 包括用于爱好项目的免费云托管.
  * [gigalixir.com](https://gigalixir.com/) - Gigalixir 为 Elixir/Phoenix 应用程序提供 1 个永不休眠的免费实例，以及限制为 2 个连接、10、000 行且无备份的免费层级 PostgreSQL 数据库.
  * [Glitch](https://glitch.com/) — Free public hosting with features such as code sharing and real-time collaboration. Free plan has 1000 hours/month limit.
  * [Heroku](https://www.heroku.com/) — 在云中托管您的应用程序，单进程应用程序免费
  * [Krucible](https://usekrucible.com) — Krucible is a platform for creating Kubernetes clusters for testing and development. Free tier accounts come with 25 cluster-hours per month.
  * [Mendix](https://www.mendix.com/) — Rapid Application Development for Enterprises, unlimited number of free sandbox environments supporting unlimited users, 0.5 GB storage and 1 GB RAM per app. Also Studio and Studio Pro IDEs are allowed in free tier.
  * [m3o.com](https://m3o.com) - A cloud platform for API services development. M3O is a fully managed Micro as a Service offering focusing on Go microservices development in the Cloud. Free tier provides enough to run 5 services and collaborate with others.
  * [Okteto Cloud](https://okteto.com)  - 专为远程开发设计的托管 Kubernetes 服务. 免费的开发者账户有 5 个 Kubernetes 命名空间，3Gi/pod 最多 8Gi/命名空间，1CPU/pod 最多 4CPU/命名空间和 5GB 磁盘空间. 应用程序在 24 小时不活动后进入睡眠状态.
  * [opeNode](https://openode.io) — Free Node.js hosting for Open Source projects. 100 GB Bandwidth/month with 100 MB memory & 1000 MB storage. Deploy using CLI or existing Git repository.
  * [outsystems.com](https://www.outsystems.com/) — Enterprise web development PaaS for on-premise or cloud, free "personal environment" offering allows for unlimited code and up to 1 GB database
  * [pipedream.com](https://pipedream.com) - An integration platform built for developers. Develop any workflow, based on any trigger. Workflows are code, which you can run [for free](https://docs.pipedream.com/pricing/). No server or cloud resources to manage.
  * [pythonanywhere.com](https://www.pythonanywhere.com/) — Cloud Python app hosting. Beginner account is free, 1 Python web application at your-username.pythonanywhere.com domain, 512 MB private file storage, one MySQL database
  * [scn.sap.com](https://scn.sap.com/docs/DOC-56411)  — SAP 的内存平台即服务产品. 免费的开发者帐户包含 1 GB 结构化、1 GB 非结构化、1 GB Git 数据，并允许您运行 HTML5、Java 和 HANA XS 应用程序
  * [Serverless Cloud](https://www.serverless.com/cloud)  - 无服务器云让您可以使用基础架构 _from_ 代码方法（无 yaml，无基础架构配置）构建无服务器 API、数据库和存储. 该产品由 Serverless Inc. 提供，目前处于公共预览阶段. 
  * [fly.io](https://fly.io/) - Fly is a platform for applications that need to run globally. It runs your code close to users and scales compute in cities where your app is busiest. Write your code, package it into a Docker image, deploy it to Fly's platform and let that do all the work to keep your app snappy. Free for side projects, $10/mo of service credit that automatically applies to any paid service. And if you ran really small virtual machines, credits will go a long way.
  * [Divio](https://www.divio.com/)  - 管理仅使用 Docker 部署的云应用程序的平台. 可免费订阅开发项目，需要卡且无自定义域支持.  
  * [Koyeb](https://www.koyeb.com) - Koyeb is a developer-friendly serverless platform to deploy apps globally. Seamlessly run Docker containers, web apps, and APIs with git-based deployment, native autoscaling, a global edge network, and built-in service mesh and discovery. Koyeb provides two nano services to run your apps with its forever-free tier and also sponsors open-source projects with free resources.
  * [Railway](https://railway.app)  - 铁路是一个基础架构平台，您可以在其中配置基础架构，在本地使用该基础架构进行开发，然后部署到云端.  1GB 磁盘，512 MB RAM，每月限用 5 美元免费提供.
  * [Napkin](https://www.napkin.io/) - 具有 1Gb 内存的 FaaS，默认超时 15 秒和每月 1,000,000 次免费 API 调用.
  * [Meteor Cloud](https://www.meteor.com/cloud) — Galaxy hosting. Meteor's own platform-as-a-service for Meteor apps which includes a free MongoDB Shared Hosting and automatic SSL.
  * [Northflank](https://northflank.com)  — 使用强大的 UI、API 和 CLI 构建和部署微服务、作业和托管数据库. 从版本控制和外部 Docker 注册表无缝扩展容器. 免费套餐包括 2 个服务、2 个 cron 作业和 1 个数据库.


## BaaS

  * [ably.com](https://www.ably.com)  - 用于实时消息传递、推送通知和事件驱动 API 创建的 API. 免费计划有 300 万条消息/月，100 个并发连接，100 个并发通道.
  * [back4app.com](https://www.back4app.com) - Back4App 是一个易于使用、灵活且可扩展的基于 Parse 平台的后端.
  * [backendless.com](https://backendless.com/) — 移动和 Web Baas，提供 1 GB 的免费文件存储空间，每月推送通知 50000 个，表中包含 1000 个数据对象。
  * [BMC Developer Program](https://developers.bmc.com/site/global/bmc_helix_platform/program/overview/index.gsp) — The BMC Developer Program provides documentation and resources to build and deploy digital innovations for your enterprise. Access to a comprehensive, personal sandbox which includes the platform, SDK, and a library of components that can be used to build and tailor apps.
  * [darklang.com](https://darklang.com/) - Hosted language combined with editor and infrastructure. Free during the beta, generous free tier planned after beta.
  * [Firebase](https://firebase.com) — Firebase helps you build and run successful apps. Free Spark Plan offers Authentication, Hosting, Firebase ML , Realtime Database,Cloud Storage,Testlab. A/B Testing, Analytics, App Distribution, App Indexing, Cloud Messaging (FCM), Crashlytics, Dynamic Links, In-App Messaging, Performance Monitoring, Predictions, and Remote Config are always-free.
  * [Flutter Flow](https://flutterflow.io) — Build your Flutter App UI without writing a single line of code. Also has a Firebase integration. Free plan includes full access to UI Builder and Free templates.
  * [getstream.io](https://getstream.io/) — Build scalable newsfeeds, activity streams, chat and messaging in a few hours instead of weeks
  * [hasura.io](https://hasura.io/) — Hasura extends your existing databases wherever it is hosted and provides an instant GraphQL API that can be securely accessed for web, mobile, and data integration workloads. Free for 1GB/month of data pass-through.
  * [iron.io](https://www.iron.io/) — 具有免费套餐和 1 个月免费试用的异步任务处理（如 AWS Lambda）
  * [netlicensing.io](https://netlicensing.io) - A cost-effective and integrated Licensing-as-a-Service (LaaS) solution for your software on any platform from Desktop to IoT and SaaS. Basic Plan for *FREE* while you are a student.
  * [nhost.io](https://nhost.io) - Serverless backend for web and mobile apps. Free plan includes: PostgreSQL, GraphQL (Hasura), Authentication, Storage, and Serverless Functions.
  * [onesignal.com](https://onesignal.com/) — 无限制的免费推送通知
  * [paraio.com](https://paraio.com)  — 具有灵活身份验证、全文搜索和缓存的后端服务 API.  1 个应用程序免费，1GB 应用程序数据.
  * [posthook.io](https://posthook.io/) — Job Scheduling Service. Allows you to schedule requests for specific times. 500 scheduled requests/month free.
  * [progress.com](https://www.progress.com/kinvey) — Mobile backend, starter plan has unlimited requests/second, with 1 GB of data storage. Enterprise application support
  * [pubnub.com](https://www.pubnub.com/) — Free push notifications for up to 1 million messages/month and 100 active daily devices
  * [pushbots.com](https://pushbots.com/)  — 推送通知服务. 每月最多 150 万次推送免费
  * [pushcrew.com](https://pushcrew.com/)  — 推送通知服务. 多达 2000 个订阅者的无限通知
  * [pusher.com](https://pusher.com/beams)  — 为 2000 名每月活跃用户提供免费、无限制的推送通知. 适用于 iOS 和 Android 设备的单一 API.
  * [pushtechnology.com](https://www.pushtechnology.com/) — Real-time Messaging for browsers, smartphones and everyone. 100 concurrent connections. Free 10 GB data/month
  * [quickblox.com](https://quickblox.com/) — A communication backend for instant messaging, video and voice calling and push notifications
  * [restspace.io](https://restspace.io/) - Configure a server with services for auth, data, files, email API, templates etc, then compose into pipelines and transform data.
  * [Salesforce Developer Program](https://developer.salesforce.com/signup) — Build apps Lightning fast with drag and drop tools. Customize your data model with clicks. Go further with Apex code. Integrate with anything using powerful APIs. Stay protected with enterprise-grade security. Customize UI with clicks or any leading-edge web framework. Free Developer Program gives access to the full Lightining Platform.
  * [ServiceNow Developer Program](https://developer.servicenow.com/) — Rapidly build, test, and deploy applications that make work better for your organization. Free Instance & access early previews.
  * [simperium.com](https://simperium.com/)  — 即时自动移动数据，多平台，无限发送和存储结构化数据，最大.  2,500 个用户/月
  * [stackstorm.com](https://stackstorm.com/) — Event-driven automation for apps, services and workflows, free without flow, access control, LDAP,...
  * [streamdata.io](https://streamdata.io/)  — 将任何 REST API 转变为事件驱动的流式 API. 免费计划多达 100 万条消息和 10 个并发连接.
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
  * [Drive To Web](https://drv.tw)  — 从 Google Drive 和 OneDrive 直接托管到网络. 仅限静态站点. 永远免费. 每个 Google/Microsoft 帐户一个站点.
  * [Fenix Web Server](https://preview.fenixwebserver.com)  - 用于在本地托管站点并公开（实时）共享它们的开发人员桌面应用程序. 使用其漂亮的用户界面、API 和/或 CLI，随心所欲地工作.
  * [Free Hosting](http://freehostingnoads.net/) — Free Hosting With PHP 5, Perl, CGI, MySQL, FTP, File Manager, POP E-Mail, free sub-domains, free domain hosting, DNS Zone Editor, Web Site Statistics, FREE Online Support and many more features not offered by other free hosts.
  * [Freehostia](https://www.freehostia.com)  — FreeHostia 提供免费托管服务，包括. 业界最佳的控制面板和 50 多个免费应用程序的一键安装. 即时设置. 没有强制广告.
  * [hostman.com](https://hostman.com) — 从您的 GitHub 存储库免费部署多达 3 个静态站点.
  * [Neocities](https://neocities.org) — Static, 1 GB free storage with 200 GB Bandwidth.
  * [Netlify](https://www.netlify.com/) — Builds, deploy and hosts static site/app free for, 100 GB data and 100 GB/month bandwidth.
  * [Layer0](https://layer0.co/) 在全球 CDN 上部署快速动态 Jamstack 网站 [Limelight](https://www.limelight.com/) 免费提供 100GB/月带宽和 3 个环境.
  * [pantheon.io](https://pantheon.io/) — Drupal and WordPress hosting, automated DevOps and scalable infrastructure. Free for developers and agencies
  * [readthedocs.org](https://readthedocs.org/) — Free documentation hosting with versioning, PDF generation and more
  * [render.com](https://render.com) — Unified cloud to build and run apps and sites with free SSL, a global CDN, private networks, auto-deploys from Git, and completely free plans for web services, databases, and static web pages.
  * [SourceForge](https://sourceforge.net/) — Find, Create and Publish Open Source software for free
  * [Stormkit](https://stormkit.io/) — Integrate building, deploying and hosting seamlessly with your git flow of your JAMStack or Node.JS app. 50 GB bandwith and 10m requests for free per month including free SSL.
  * [surge.sh](https://surge.sh/) — Static web publishing for Front-End developers. Unlimited sites with custom domain support
  * [tilda.cc](https://tilda.cc/) — One site, 50 pages, 50 MB storage, only the main pre-defined blocks among 170+ available, no fonts, no favicon and no custom domain
  * [txti.es](https://txti.es/) — 使用 Markdown 快速创建网页.
  * [Vercel](https://vercel.com/) — Build, deploy, and host web apps with free SSL, global CDN, and unique Preview URLs each time you `git push`. Perfect for Next.js and other Static Site Generators.
  * [Versoly](https://versoly.com/)  — 专注于 SaaS 的网站构建器 - 无限网站、70 多个区块、5 个模板、自定义 CSS、网站图标、搜索引擎优化和表单. 没有自定义域.
  * [Qovery](https://www.qovery.com) — Qovery is the simplest way to deploy your full-stack apps on AWS, GCP and Azure. It is free web hosting for developers with Database, SSL, a global CDN, and auto deploys from Git.
  * [Qoddi](https://qoddi.com)  - 类似于 Heroku 的 PaaS 服务，具有以开发人员为中心的方法和全包功能. 静态资产、登台和开发人员应用程序的免费套餐.
  * [FreeFlarum](https://freeflarum.com/) - Community powered free Flarum hosting for up to 250 users (donate to remove watermark from footer).


## DNS
  * [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/)  - 由 CloudFlare 提供的快速且安全的免费公共 DNS 解析器（加密您的 DNS 查询）. 有助于绕过您的互联网提供商的 DNS 阻止，防止 DNS 查询间谍，以及 [to block adult & malware content](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families). Can also be used [via API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests). Note: Just a DNS resolver, not a DNS hoster.
  * [1984.is](https://www.1984.is/product/freedns/) — 带有 API 的免费 DNS 服务，以及许多其他免费的 DNS 功能.
  * [biz.mail.ru](https://biz.mail.ru) — Free email and DNS hosting for up to 5,000 users
  * [cloudns.net](https://www.cloudns.net/) — Free DNS hosting up to 1 domain with 50 records
  * [dns.he.net](https://dns.he.net/) — 具有动态 DNS 支持的免费 DNS 托管服务
  * [dnspod.com](https://www.dnspod.com/) — Free DNS hosting.
  * [duckdns.org](https://www.duckdns.org/) — Free DDNS with up to 5 domains on the free tier. With configuration guides for various setups.
  * [dynu.com](https://www.dynu.com/) — Free dynamic DNS service
  * [fosshost.org](https://fosshost.org/) - Free open source hosting VPS, web, storage and mirror hosting
  * [freedns.afraid.org](https://freedns.afraid.org/)  — 免费 DNS 托管. 还提供基于众多公众用户的免费子域 [contributed domains](https://freedns.afraid.org/domain/registry/) . 注册后从“子域”菜单中获取免费子域.
  * [luadns.com](https://www.luadns.com/) — Free DNS hosting, 3 domains, all features with reasonable limits
  * [namecheap.com](https://www.namecheap.com/domains/freedns/)  — 免费 DNS. 域名数量没有限制
  * [nextdns.io](https://nextdns.io) - DNS based firewall, 300K free queries monthly
  * [noip](https://www.noip.com/) — 动态 dns 服务，最多允许 3 个免费主机名，每 30 天确认一次
  * [ns1.com](https://ns1.com/) — 数据驱动的 DNS、自动流量管理、50 万次免费查询
  * [nsupdate.info](https://www.nsupdate.info/) — Free and open-source Dynamic DNS service
  * [pointhq.com](https://pointhq.com/developer) — Heroku 上的免费 DNS 托管.
  * [selectel.com](https://selectel.com/services/dns/) — Free DNS hosting with unlimited records, anycast
  * [web.gratisdns.dk](https://web.gratisdns.dk/domaener/dns/) — Free DNS hosting.
  * [Yandex.Connect](https://connect.yandex.com/pdd/) — 最多可容纳 1,000 名用户的免费电子邮件和 DNS 托管
  * [zilore.com](https://zilore.com/en/dns) — Free DNS hosting.
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) — 具有动态 DNS 支持的免费 DNS 托管.
  * [zonewatcher.com](https://zonewatcher.com) — Automatic backups and DNS change monitoring. 1 domain free
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – Free DNS hosting by Huawei
  * [Hetzner](https://www.hetzner.com/dns-console) – Free DNS hosting from Hetzner with API support
  * [Glauca](https://docs.glauca.digital/hexdns/) – 最多 3 个域的免费 DNS 托管和 DNSSEC 支持


## IaaS

  * [filebase.com](https://filebase.com/) - S3 Compatible Object Storage Powered by Blockchain. 5 GB free storage for unlimited duration.
  * [backblaze.com](https://www.backblaze.com/b2/)  — Backblaze B2 云存储. 无限时间的免费 10 GB（类似 Amazon S3）对象存储
  * [scaleway.com](https://www.scaleway.com/en/object-storage/) — S3-Compatible Object Storage. Free 75 GB storage and external outgoing traffic
  * [terraform.io](https://www.terraform.io/)  — Terraform 云. 免费远程状态管理和团队协作，最多可容纳 5 个用户.


## DBaaS

   * [airtable.com](https://airtable.com/) — Looks like a spreadsheet, but it's a relational database, unlimited bases, 1,200 rows/base and 1,000 API requests/month
   * [Astra](https://www.datastax.com/products/datastax-astra/) — 云原生 Cassandra 即服务 [80GB free tier](https://www.datastax.com/products/datastax-astra/pricing)
   * [bit.io](https://bit.io) — PostgreSQL managed database service. Unlimited repos, 10GB storage, 10M queried rows/month.
   * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ 即服务，每月最多 100 万条消息和 20 个免费连接
   * [elephantsql.com](https://www.elephantsql.com/) — PostgreSQL 即服务，20 MB 免费
   * [FaunaDB](https://fauna.com/) — 无服务器云数据库，具有原生 GraphQL、多模型访问和高达 100 MB 的每日免费层
   * [HarperDb](https://harperdb.io/) — Serverless cloud database, with dynamic schema based on JSON, 3000 IOPS with 1GB storage
   * [heroku.com](https://www.heroku.com/) — PostgreSQL as a service, up to 10,000 rows and 20 connections free (provided as an "addon," but can be attached to an otherwise empty app and accessed externally)
   * [Upstash](https://upstash.com/) — Serverless Redis with free tier up to 10,000 requests per day, 256MB max database size, and 20 concurrent connections
   * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — 免费套餐提供 512 MB
   * [redsmin.com](https://www.redsmin.com/) — Online real-time monitoring and administration service for Redis, Monitoring for 1 Redis instance free
   * [redislabs](https://redislabs.com/try-free/) - Free 30Mb redis instance
   * [MemCachier](https://www.memcachier.com/)  — 托管 Memcache 服务. 免费提供高达 25MB 的空间、1 个代理服务器和基本分析
   * [scalingo.com](https://scalingo.com/) — Primarily a PaaS but offers a 128MB to 192MB free tier of MySQL, PostgreSQL or MongoDB
   * [SeaTable](https://seatable.io/) — Flexible, Spreadsheet-like Database built by Seafile team. unlimited tables, 2,000 lines, 1-month versioning, up to 25 team members.
   * [skyvia.com](https://skyvia.com/) — 云数据平台，提供免费套餐，所有计划在测试阶段完全免费
   * [StackBy](https://stackby.com/)  — 一种工具，将电子表格的灵活性、数据库的强大功能以及与您最喜欢的业务应用程序的内置集成结合在一起. 免费计划包括无限用户、10 个堆栈、每个堆栈 2GB 附件.
   * [InfluxDB](https://www.influxdata.com/) — Timeseries database, free up to 3MB/5 minutes writes, 30MB/5 minutes reads and 10,000 cardinalities series
   * [Quickmetrics](https://www.quickmetrics.io/) — 包含仪表板的时间序列数据库，每天最多释放 10,000 个事件和总共 5 个指标.
   * [restdb.io](https://restdb.io/) <i>- a fast and simple NoSQL cloud database service.</i> <b>- 快速简单的 NoSQL 云数据库服务。</b> <i>With restdb.io you get schema, relations, automatic REST API (with MongoDB-like queries) and an efficient multi-user admin UI for working with data.</i><b>使用 restdb.io，您可以获得模式、关系、自动 REST API（带有类似 MongoDB 的查询）和用于处理数据的高效多用户管理 UI。</b> <i>Free plan allows 3 users, 2500 records and 1 API requests per second.</i><b>免费计划每秒允许 3 个用户、2500 条记录和 1 个 API 请求。</b>
   * [cockroachlabs.com](https://www.cockroachlabs.com/free-tier/) — Free CockroachDB up to 5GB and 1vCPU (limited [request units](https://www.cockroachlabs.com/docs/cockroachcloud/serverless-faqs.html#what-are-the-usage-limits-of-cockroachdb-serverless-beta))
   * [Neo4j Aura](https://neo4j.com/cloud/aura/) — Managed native Graph DBMS / analytics platform with a Cypher query language and a REST API. Limits on graph size (50k nodes, 175k relationships).
   * [Dgraph Cloud](https://cloud.dgraph.io/pricing?type=free)  — 使用 GraphQL API 托管本机 Graph DBMS. 每天限制为 1 MB 数据传输.
   * [TigerGraph Cloud](https://www.tigergraph.com/cloud/)  — 使用类似 SQL 的图形查询语言和 REST API 的托管原生图形 DBMS/分析平台.  AWS（4 个 vCPU，7.5 GB 内存，50 GB 磁盘）或 GCP（2 个 vCPU，8 GB 内存，128 GB 磁盘）上的 1 个 TG.Free 实例. 免费实例在闲置 1 小时后休眠.
   * [Macrometa](https://www.macrometa.com/)  - 用于构建地理分布式和实时应用程序的 noSQL 数据库、Pub/Sub、事件处理和无服务器边缘计算平台. 免费开发帐户可访问 10,000 次操作/天和 200MB 存储.
   * [Planetscale](https://planetscale.com/) - PlanetScale is a MySQL compatible, serverless database platform powered by Vitess, 3 databases for free with 10GB storage, 100 Million rows read/mo per database, and 10 Million rows written/mo per database.
   * [YugabyteDB](http://cloud.yugabyte.com) - YugabyteDB is a distributed SQL database compatible with PostgresSQL. The cloud free tier is a 2 vCPU, 4GB RAM, 10GB Disk.


## Tunneling, WebRTC, Web Socket Servers and Other Routers

   * [conveyor.cloud](https://conveyor.cloud/) — Visual Studio 扩展，用于将 IIS Express 公开到本地网络或通过隧道到公共 URL.
   * [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi 是一项托管 VPN 服务，可让您安全地将类似 LAN 的网络扩展到分布式团队，免费计划允许最多 5 人的无限网络
   * [localhost.run](https://localhost.run/) — 通过隧道向公共 URL 公开本地运行的服务器.
   * [localtunnel](https://theboroer.github.io/localtunnel-www/)  — 通过隧道向公共 URL 公开本地运行的服务器. 免费托管版本，以及 [open source](https://github.com/localtunnel/localtunnel).
   * [ngrok.com](https://ngrok.com/) — 通过隧道向公共 URL 公开本地运行的服务器.
   * [Radmin VPN](https://www.radmin-vpn.com/)  — 通过启用类似 LAN 的网络的 VPN 将多台计算机连接在一起. 无限同行.  （Hamachi 替代品）
   * [segment.com](https://segment.com/) — Hub to translate and route events to other third-party services. 100,000 events/month free
   * [STUN](https://en.wikipedia.org/wiki/STUN) — 通过网络地址转换器 [NAT] 的用户数据报协议 [UDP] 的会话遍历）
     * Google STUN — [https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302](https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302)
     * Twilio STUN — [https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp](https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp)
   * [Tailscale](https://tailscale.com/) — Zero config VPN, using the open source WireGuard protocol. Installs on MacOS, iOS, Windows, Linux, and Android devices. Free plan for personal use with 20 devices.
   * [webhookrelay.com](https://webhookrelay.com)  — 管理、调试、扇出和代理所有 webhook 到公共或内部（即：localhost）目的地. 此外，通过获取公共 HTTP 端点（`https://yoursubdomain.webrelay.io &lt;----&gt; http://localhost:8080`），通过隧道公开在专用网络中运行的服务器.
   * [Xirsys](https://www.xirsys.com) — Global network of STUN / TURN servers with a generous free tier.
   * [ZeroTier](https://www.zerotier.com)  — FOSS 管理的虚拟以太网即服务. 免费计划的 100 个客户端的无限端到端加密网络. 桌面/移动/NA客户端； 用于配置自定义路由规则和批准专用网络上的新客户端节点的 Web 界面.


## Issue Tracking and Project Management

   * [acunote.com](https://www.acunote.com/) — 最多 5 名团队成员的免费项目管理和 SCRUM 软件
   * [asana.com](https://asana.com/) — 与合作者的私人项目免费
   * [Backlog](https://backlog.com)  — 您的团队在一个平台上发布伟大项目所需的一切. 免费计划提供 1 个具有 10 个用户和 100MB 存储空间的项目.
   * [Basecamp](https://basecamp.com/personal) - To-do lists, milestone management, forum-like messaging, file sharing, and time tracking. Up to 3 projects, 20 users, and 1GB of storage space.
   * [bitrix24.com](https://www.bitrix24.com/) — Free intranet and project management tool
   * [cacoo.com](https://cacoo.com/) — Online diagrams in real-time: flowchart, UML, network. Free max. 15 users/diagram, 25 sheets
   * [Chpokify](https://chpokify.com/)  — 基于团队的 Planning Poker，可节省 sprint 估算时间. 最多释放 5 位用户、免费 Jira 集成、无限视频通话、无限团队、无限会话.
   * [clickup.com](https://clickup.com/) — Project management. Free, premium version with cloud storage. Mobile applications and Git integrations available
   * [Cloudcraft](https://cloudcraft.co/) — Design a professional architecture diagram in minutes with the Cloudcraft visual designer, optimized for AWS with smart components that show live data too.
   * [Codegiant](https://codegiant.io)  — 使用存储库托管和 CI/CD 进行项目管理. 免费计划提供无限的存储库、项目和文档，有 5 名团队成员. 每月 500 CI/CD 分钟. 每月 30000 分钟无服务器代码运行时间.1GB 存储库存储.
   * [Confluence](https://www.atlassian.com/software/confluence)  - Atlassian 的内容协作工具，用于帮助团队高效协作和共享知识. 免费计划最多 10 个用户.
   * [contriber.com](https://www.contriber.com/) — 可定制的项目管理平台，免费入门计划，5 个工作区
   * [draw.io](https://www.draw.io/) — Online diagrams stored locally, in Google Drive, OneDrive or Dropbox. Free for all features and storage levels
   * [freedcamp.com](https://freedcamp.com/) <i>- tasks, discussions, milestones, time tracking, calendar, files and password manager.</i> <b>- 任务、讨论、里程碑、时间跟踪、日历、文件和密码管理器。</b> <i>Free plan with unlimited projects, users and files storage.</i><b>免费计划，无限项目、用户和文件存储。</b>
   * [easyretro.io](https://www.easyretro.io/) — Free simple and intuitive sprint retrospective tool
   * [GForge](https://gforge.com)  — 用于具有自建和 SaaS 选项的复杂项目的项目管理和问题跟踪工具集.  SaaS 免费计划为前 5 名用户免费提供开源项目.
   * [gleek.io](https://www.gleek.io) — Free description-to-diagrams tool for developers. Create informal, UML class, object, or entity-relationship diagrams using your keyword.
   * [gliffy.com](https://www.gliffy.com/) <i>— Online diagrams: flowchart, UML, wireframe,... Also plugins for Jira and Confluence.</i> <b>— 在线图表：流程图、UML、线框图……还有 Jira 和 Confluence 的插件。</b> <i>5 diagrams and 2 MB free</i> <b>5 个图表和 2 MB 免费</b>
   * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - GraphQL Inspector ouputs a list of changes between two GraphQL schemas. Every change is precisely explained and marked as breaking, non-breaking or dangerous.
   * [huboard.com](https://huboard.com/) — 为您的 GitHub 问题提供即时项目管理，开源免费
   * [Hygger](https://hygger.io)  ——项目管理平台. 免费计划提供无限的用户、项目和具有 100 MB 存储空间的板.
   * [Instabug](https://instabug.com)  — 适用于移动应用的全面错误报告和应用内反馈 SDK. 免费计划最多 1 个应用程序和 1 个成员.
   * [Ilograph](https://www.ilograph.com/)  — interactive diagrams that allow users to see their infrastructure from multiple perspectives and levels of detail. Diagrams can be expressed in code. Free tier has unlimited private diagrams with up to 3 viewers.
   * [Issue Embed](https://issueembed.dev/) - A bug reporting tool for websites to go directly into your Github Issues. Free plan for personal repositories with up to 500 issues/month and 10,000 page views/month.
   * [Jira](https://www.atlassian.com/software/jira)  — 在许多企业环境中使用的高级软件开发项目管理工具. 免费计划最多 10 个用户.
   * [kanbanflow.com](https://kanbanflow.com/)  — 基于董事会的项目管理. 免费的高级版本，提供更多选项
   * [kanbantool.com](https://kanbantool.com/) — Kanban board-based project management. Free, paid plans with more options
   * [Kitemaker.co](https://kitemaker.co) - Collaborate through all phases of the product development process and keep track of work across Slack, Discord, Figma, and Github. Unlimited users, unlimited spaces. Free plan up to 250 work items.
   * [Kumu.io](https://kumu.io/)  — Relationship maps with animation, decorations, filters, clustering, spreadsheet imports and more. Free tier allows unlimited public projects. Graph size unlimited. Free private projects for students. Sandbox mode is available if you prefer to not leave your file publicly online (upload, edit, download, discard).
   * [LeanBoard](https://www.leanboard.io) — 为您的 GitHub 问题提供便签的协作白板（适用于示例映射和其他技术）
   * [Linear](https://linear.app/)  — 具有简化界面的问题跟踪器. 无限会员免费，文件上传最大 10MB，250 期（不包括存档）
   * [MeisterTask](https://www.meistertask.com/)  — 团队的在线任务管理. 最多释放 3 个项目，无限的项目成员.
   * [MeuScrum](https://www.meuscrum.com/en) - Free online scrum tool with kanban board
   * [nTask](https://www.ntaskmanager.com/) — Project management software that enables your teams tn collaborate, plan, analyze and manage everyday tasks. Basic Plan free forever with 100 MB storage, 5 users/team. Unlimited workspaces, meetings,tasks, timesheets and issue tracking.
   * [Ora](https://ora.pm/)  - 敏捷任务管理和团队协作. 最多 3 个用户免费，文件限制为 10 MB.
   * [pivotaltracker.com](https://www.pivotaltracker.com/) — 对无限的公共项目和两个私人项目免费，总共有 3 个活跃用户（读写）和无限的被动用户（只读）.
   * [plan.io](https://plan.io/)  — 使用存储库托管和更多选项进行项目管理.  2 位用户免费，10 位客户和 500MB 存储空间
   * [planitpoker.com](https://www.planitpoker.com/) — 免费在线规划扑克（估算工具）
   * [saas.zentao.pm](https://saas.zentao.pm/) - 还提供用于问题跟踪和项目管理的应用程序生命周期管理解决方案、本地和开源版本.
   * [ScrumFast](https://www.scrumfast.com) - Scrum board with a very intuitive interface, free up to 5 users.
   * [Shortcut](https://shortcut.com/)  - 项目管理平台. 最多 10 位用户永久免费.
   * [SpeedBoard](https://speedboard.app) - 敏捷和 Scrum 回顾委员会 - 免费.
   * [Shake](https://www.shakebugs.com/) - In-app bug reporting and feedback tool for mobile apps. Free plan, 10 bug reports per app/per month.
   * [Tadum](https://tadum.app) - 专为定期会议设计的会议议程和会议记录应用程序，最多 10 人的团队可免费使用
   * [taiga.io](https://taiga.io/) — 面向初创公司和敏捷开发人员的项目管理平台，开源免费
   * [Tara AI](https://tara.ai/)  — 简单的冲刺管理服务. 免费计划有无限的任务、冲刺和工作空间，没有用户限制.
   * [targetprocess.com](https://www.targetprocess.com/)  — 可视化项目管理，从看板和 Scrum 到几乎任何操作流程. 无限用户免费，最多 1,000 个数据实体 {[more details](https://www.targetprocess.com/pricing/)}
   * [taskade.com](https://www.taskade.com/) — 团队的实时协作任务列表和大纲
   * [taskulu.com](https://taskulu.com/)  — 基于角色的项目管理. 最多释放 5 个用户. 与 GitHub/Trello/Dropbox/Google Drive 集成
   * [teamwork.com](https://teamwork.com/)  — 项目管理和团队聊天.  5 个用户和 2 个项目免费. 提供高级计划.
   * [testlio.com](https://testlio.com/)  — 问题跟踪、测试管理和beta测试平台. 免费供私人使用
   * [terrastruct.com](https://terrastruct.com/)  — 专门用于软件架构的在线图表制作工具. 每个图表最多 4 层的免费层.
   * [todoist.com](https://todoist.com/) — Collaborative and individual task management. Free, Premium and Team plans are available. Discounts provided for eligible users.
   * [trello.com](https://trello.com/) — Board-based project management. Unlimited Personal Boards, 10 Team Boards.
   * [Tweek](https://tweek.so/) — 简单的每周待办事项日历和任务管理.
   * [ubertesters.com](https://ubertesters.com/) — Test platform, integration and crowdtesters, 2 projects, 5 members
   * [vabotu](https://vabotu.com/)  - 用于项目管理的协作工具. 提供免费和其他计划.  Freelance 计划适用于 10 个用户，包括消息传递、任务板、5GB 在线存储、工作区、导出数据.
   * [vivifyscrum.com](https://www.vivifyscrum.com/)  — 敏捷项目管理的免费工具.  Scrum 兼容
   * [Wikifactory](https://wikifactory.com/)  — 包含项目、VCS 和问题的产品设计服务. 免费计划提供无限的项目和合作者以及 3GB 存储空间.
   * [Yodiz](https://www.yodiz.com/) — Agile development and issue tracking. Free up to 3 users, unlimited projects.
   * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud)  — 免费托管的 YouTrack (InCloud) 用于 FOSS 项目、私人项目（3 个用户免费）. 包括时间跟踪和敏捷板
   * [zenhub.com](https://www.zenhub.com)  — GitHub 内唯一的项目管理解决方案. 公共存储库、OSS 和非营利组织免费
   * [zepel.io](https://zepel.io/)  - 项目管理工具，可让您规划功能、跨学科协作以及共同构建软件. 最多释放 5 名成员. 没有功能限制.
   * [zenkit.com](https://zenkit.com) — Project management and collaboration tool. Free for up to 5 members, 5 GB attachments.
   * [Zube](https://zube.io)  — 为 4 个项目和 4 个用户提供免费计划的项目管理.  GitHub 集成可用.
   * [Toggl](https://toggl.com/) — 提供 2 个免费的生产力工具. [Toggl Track](https://toggl.com/track/) 具有免费计划的时间管理和跟踪应用程序提供了专为自由职业者设计的无缝时间跟踪和报告. 它具有无限的跟踪记录、项目、客户、标签、报告等. 和 [Toggl Plan](https://toggl.com/plan/) for task planning that comes with a free plan for solo developers with unlimited tasks, milestones and timelines.


## Storage and Media Processing

   * [borgbase.com](https://www.borgbase.com/)  — Borg Backup 的简单安全的异地备份托管.  10 GB 可用备份空间和 2 个存储库.
   * [icedrive.net](https://www.icedrive.net/)  - 简单的云存储服务.  10 GB 免费存储空间
   * [sync.com](https://www.sync.com/) - End-to-End cloud storage service. 5 GB free storage
   * [pcloud.com](https://www.pcloud.com/)  - 云存储服务. 高达 10 GB 的免费存储空间
   * [sirv.com](https://sirv.com/) — Smart Image CDN with on-the-fly image optimization and resizing. Free tier includes 500 MB of storage and 2 GB bandwidth.
   * [image4.io](https://image4.io/) — Image upload, powerful manipulations, storage and delivery for websites and apps, with SDK's, integrations and migration tools. Free tier includes 25 credits. 1 credit is equal to 1 GB of CDN usage, 1GB of storage or 1000 image transformations.
   * [cloudimage.com](https://cloudimage.com/)  — 全面的图像优化和 CDN 服务，在全球拥有 1500 多个入网点. 多种图像缩放、压缩、水印功能. 用于响应式图像、360 度图像制作和图像编辑的开源插件. 免费的月度计划，包含 25GB 的 CDN 流量和 25GB 的缓存存储和无限转换.
   * [cloudinary.com](https://cloudinary.com/) — Image upload, powerful manipulations, storage and delivery for sites and apps, with libraries for Ruby, Python, Java, PHP, Objective-C and more. Free tier includes 25 monthly credits. 1 credit is equal to 1,000 image transformations, 1 GB of storage, or 1 GB of CDN usage.
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
   * [packagecloud.io](https://packagecloud.io/)  — YUM、APT、RubyGem 和 PyPI 的托管包存储库. 有限的免费计划，可根据要求提供开源计划
   * [piio.co](https://piio.co/) — Responsive image optimization and delivery for every website. Free plan for developers and personal websites. Includes free CDN, WebP and Lazy Loading out of the box.
   * [Pinata IPFS](https://pinata.cloud) — Pinata is the simplest way to upload and manage files on IPFS. Our friendly user interface combined with our IPFS API makes Pinata the easiest IPFS pinning service for platforms, creators, and collectors. 1 GB storage free along with access to API.
   * [placeholder.com](https://placeholder.com/) — A quick and simple image placeholder service
   * [placekitten.com](https://placekitten.com/) — A quick and simple service for getting pictures of kittens for use as placeholders
   * [plot.ly](https://plot.ly/) — Graph and share your data. Free tier includes unlimited public files and 10 private files
   * [podio.com](https://podio.com/) — You can use Podio with a team of up to five people and try out the features of the Basic Plan, except user management
   * [QuickChart](https://quickchart.io) — 生成可嵌入的图像图表、图形和二维码
   * [redbooth.com](https://redbooth.com) — P2P 文件同步，最多 2 位用户免费
   * [Skynet](https://siasky.net) — An open protocol for hosting data and web applications on the decentralized web using [Sia](https://sia.tech/) . 免费层提供高达 100GB 的存储空间.
   * [Storj](https://storj.io)  — 用于应用程序和开发人员的去中心化私有云存储. 免费计划提供 3 个项目，每个项目/月 50 GB 存储空间，每个项目/月 50 GB 带宽.
   * [tinypng.com](https://tinypng.com/) — API to compress and resize PNG and JPEG images, offers 500 compressions for free each month
   * [transloadit.com](https://transloadit.com/) — Handles file uploads and encoding of video, audio, images, documents. Free for Open source, charities, and students via the GitHub Student Developer Pack. Commercial applications get 2 GB free for test driving
   * [twicpics.com](https://www.twicpics.com) - Responsive images as a service. It provides an image CDN, a media processing API and frontend library to automate image optimization. The service is free up to 3GB trafic/month.
   * [uploadcare.com](https://uploadcare.com/hub/developers/) — Uploadcare provides media pipeline  with ultimate toolkit based on cutting-edge algorithms. All features are available for developers absolutely for free: File Uploading API and UI, Image CDN and Origin Services, Adaptive Delivery and Smart Compression. Limit free tier has 3000 uploads, 3 GB traffic and 3 GB storage.
   * [imagekit.io](https://imagekit.io)  – 具有自动优化、实时转换和存储功能的图像 CDN，您可以在几分钟内与现有设置集成. 免费计划包括每月高达 20GB 的带宽.
   * [internxt.com](https://internxt.com)  – Internxt Drive 是一种基于绝对隐私和毫不妥协的安全性的零知识文件存储服务. 注册并永久免费获得 2 GB！
   * [degoo.com](https://degoo.com/) – 基于 AI 的云存储，最多可免费使用 100 Gb、5 台设备、500 Gb 推荐奖金（365 天帐户不活动）.



## Design and UI

  * [AllTheFreeStock](https://allthefreestock.com) - a curated list of free stock images, audio and videos.
  * [Ant Design Landing Page](https://landing.ant.design/) - Ant Design Landing Page provides a template built by Ant Motion's motion components. It has a rich homepage template, downloads the template code package, and can be used quickly. You can also use the editor to quickly build your own dedicated page.
  * [Backlight](https://backlight.dev/) — Backlight 以开发人员和设计师之间的协作为核心，是一个非常完整的编码平台，团队可以在其中构建、记录、发布、扩展和维护设计系统.免费计划允许多达 3 位编辑在 1 个设计系统上工作，且查看者不受限制.
  * [BoxySVG](https://boxy-svg.com/app) — A free installable Web app for drawing SVGs and exporting in svg,png,jpeg an other formats.
  * [clevebrush.com](https://www.cleverbrush.com/) — Free Graphics Design / Photo Collage App, also they offer paid integration of it as component.
  * [cloudconvert.com](https://cloudconvert.com/)  — 将任何东西转换为任何东西.  208 种支持的格式，包括视频到 gif.
  * [CodeMyUI](https://codemyui.com) - 精选的网页设计和 UI 灵感与代码片段集合.
  * [coolors](https://coolors.co/) - Color palette generator. Free.
  * [designer.io](https://www.designer.io/)  — UI、插图等的设计工具. 有一个本机应用程序. 自由.
  * [figma.com](https://www.figma.com)  — 用于团队的在线协作设计工具； 免费层包括无限的文件和查看器，最多 2 个编辑器和 3 个项目.
  * [framer.com](https://www.framer.com/)  - Framer 帮助您为您的下一个应用程序、网站或产品迭代和动画界面创意——从强大的布局开始. 对于任何将 Framer 验证为专业原型制作工具的人：无限的查看器、最多 2 个编辑器、最多 3 个项目.
  * [Gradientos](https://www.gradientos.app) - 使选择渐变变得快速而简单.
  * [Icon Horse](https://icon.horse) – 从我们简单的 API 获取任何网站的最高分辨率图标.
  * [Icons8](https://icons8.com)  — 图标、插图、照片、音乐和设计工具. 免费计划以较低的分辨率提供有限的格式. 当您使用我们的资产时链接到 Icons8.
  * [imagebin.ca](https://imagebin.ca/) — Pastebin for images.
  * [Invision App](https://www.invisionapp.com)  - UI 设计和原型制作工具. 桌面和网络应用程序可用. 免费使用 1 个活动原型.
  * [landen.co](https://www.landen.co)  — 为您的创业公司生成、编辑和发布精美的网站和登录页面. 全部没有代码. 免费套餐允许您拥有一个完全可定制并在网络上发布的网站.
  * [lensdump.com](https://lensdump.com/) - Free cloud image hosting.
  * [Lorem Picsum](https://picsum.photos/) <i>- A Free tool, easy to use stylish placeholders.</i> <b>- 免费工具，易于使用的时尚占位符。</b> <i>Just add your desired image size (width &amp; height) after our URL, and you&#39;ll get a random image.</i><b>只需在我们的 URL 后添加您想要的图像尺寸（宽度和高度），您就会得到一张随机图像。</b>
  * [LottieFiles](https://lottiefiles.com/)  - 世界上最大的在线平台，为设计师、开发人员等提供世界上最小的动画格式. 访问适用于 Android、iOS 和 Web 的 Lottie 动画工具和插件.
  * [MagicPattern](https://www.magicpattern.design/tools) — A collection of CSS & SVG background generators & tools for gradients, patterns, and blobs.
  * [marvelapp.com](https://marvelapp.com/) — 设计、原型制作和协作，免费计划仅限于一个用户和一个项目.
  * [Mindmup.com](https://www.mindmup.com/) — Unlimited mind maps for free, and store them in the cloud. Your mind maps are available everywhere, instantly, from any device.
  * [Mockplus iDoc](https://www.mockplus.com/idoc)  - Mockplus iDoc 是一个强大的设计协作和交接工具. 免费计划包括 3 个用户和 5 个具有所有可用功能的项目.
  * [mockupmark.com](https://mockupmark.com/create/free) — 为社交媒体和电子商务创建逼真的 T 恤和服装模型，40 个免费模型.
  * [Octopus.do](https://octopus.do)  — 视觉站点地图生成器. 实时构建您的网站结构并快速共享它以与您的团队或客户协作.
  * [Pencil](https://github.com/evolus/pencil) - 使用 Electron 的开源设计工具.
  * [Penpot](https://penpot.app) - Web based, open source design and prototyping tool. Supports SVG. Completely free.
  * [pexels.com](https://www.pexels.com/) - Free stock photos for commercial use. Has free API that allows you to search photos by keywords.
  * [photopea.com](https://www.photopea.com) — A Free, Advanced online design editor with Adobe Photoshop UI supporting PSD, XCF & Sketch formats (Adobe Photoshop, Gimp and Sketch App).
  * [pixlr.com](https://pixlr.com/) — Free online browser editor on the level of commercial ones.
  * [Plasmic](https://www.plasmic.app/)  - 一个快速、易于使用、功能强大的网页设计工具和页面构建器，可集成到您的代码库中. 构建响应式页面或复杂组件； 可选用代码扩展； 并发布到生产站点和应用程序.
  * [Pravatar](https://pravatar.cc/) - 生成随机/占位符假头像，该网址可以直接在您的网络/应用程序中进行热链接.
  * [Proto.io](https://www.proto.io) - Create fully interactive UI prototypes without coding. Free tier available when free trial ends. Free tier includes: 1 user, 1 project, 5 prototypes, 100MB online storage and preview in proto.io app.
  * [resizeappicon.com](https://resizeappicon.com/) — 一个简单的服务来调整和管理您的应用程序图标.
  * [Rive](https://rive.app)  — 创建精美的动画并将其发送到任何平台. 个人永久免费. 该服务是一个编辑器，它也在其服务器上托管所有图形. 它们还为许多平台提供运行时以运行使用 Rive 制作的图形.
  * [smartmockups.com](https://smartmockups.com/) — 创建产品模型，200 个免费模型.
  * [tabler-icons.io](https://tabler-icons.io/) — Over 1500 free copy and paste SVG editable icons.
  * [UI Avatars](https://ui-avatars.com/) - Generate avatars with initials from names. Which the urls can be directly hotlinked in your web/app. Support config parameters via the url.
  * [unDraw](https://undraw.co/) - A constantly updated collection of beautiful svg images that you can use completely free and without attribution.
  * [unsplash.com](https://unsplash.com/) - Free stock photos for commercial and noncommercial purposes (do-whatever-you-want license).
  * [vectr.com](https://vectr.com/) — 用于 Web + 桌面的免费设计应用程序.
  * [walkme.com](https://www.walkme.com/) — Enterprise Class Guidance and Engagement Platform, free plan 3 walk-thrus up to 5 steps/walk.
  * [Webflow](https://webflow.com) - WYSIWYG web site builder with animations and website hosting. Free for 2 projects.
  * [Updrafts.app](https://updrafts.app)  - 所见即所得网站构建器，用于基于 tailwindcss 的设计. 免费用于非商业用途.
  * [whimsical.com](https://whimsical.com/)  - 协作流程图、线框图、便利贴和思维导图. 创建多达 4 个免费板.
  * [Zeplin](https://zeplin.io/)  — 设计师和开发者协作平台. 展示设计、资产和风格指南.  1 个项目免费.
  * [Pixelixe](https://pixelixe.com/) — Create and edit engaging and unique graphics and images online.
  * [Responsively App](https://responsively.app) - A free dev-tool for faster and precise responsive web application development.
  * [SceneLab](https://scenelab.io) - 具有不断扩大的免费设计模板集合的在线模型图形编辑器
  * [xLayers](https://xlayers.dev) - 预览 Sketch 设计文件并将其转换为 Angular、React、Vue、LitElement、Stencil、Xamarin 等（在 https://github.com/xlayers/xlayers 上免费和开源）
  * [Grapedrop](https://grapedrop.com/)  — 基于 GrapesJS 框架的响应式、强大、SEO 优化的网页构建器. 前 5 页免费，无限自定义域，所有功能和简单使用.
  * [Mastershot](https://mastershot.app) - Completely free browser-based video editor. No watermark, up to 1080p export options.
  * [Unicorn Platform](https://unicornplatform.com/) - Effortless landing page builder with hosting. 1 website for free.
  * [react-favicon.com](https://react-favicon.com/) - Generate Favicons for your web site using React and JSX using any font and icon library.


## Design Inspiration

  * [awwwards.](https://www.awwwards.com/) - [热门网站] 所有最佳设计网站的展示（由设计师投票）.
  * [Behance](https://www.behance.net/)  - [设计展示]设计师展示作品的地方. 可使用 UI/UX 项目的类别进行过滤.
  * [dribbble](https://dribbble.com/) - [设计展示] 独特的设计灵感，一般并非来自实际应用.
  * [Mobbin](https://mobbin.design/) - [移动屏幕截图] 使用我们的 50,000 多个可完全搜索的移动应用屏幕截图库节省数小时的 UI 和 UX 研究.
  * [Mobile Patterns](https://www.mobile-patterns.com/) - [手机截图] 一个设计灵感库，包含最好的 UI UX 模式（iOS 和 Android），供设计师、开发人员和产品制造商参考.
  * [Screenlane](https://screenlane.com/)  - [手机截屏] 获取灵感并紧跟最新的网络和移动应用程序 UI 设计趋势. 可按模式和应用过滤.
  * [scrnshts](https://scrnshts.club/) - [Mobile screenshots] A hand-picked collection of the finest app store design screenshots.
  * [UI Garage](https://uigarage.net/) - [移动和网络截图] 设计师、开发人员的每日 UI 灵感和模式，为您的项目寻找灵感、工具和最佳资源.


## Data Visualization on Maps

   * [IP Geolocation](https://ipgeolocation.io/) — 每月有 30K 请求提供免费的 DEVELOPER 计划.
   * [carto.com](https://carto.com/) — 根据您的数据和公共数据创建地图和地理空间 API.
   * [developers.arcgis.com](https://developers.arcgis.com) — APIs and SDKs for maps, geospatial data storage, analysis, geocoding, routing, and more across web, desktop, and mobile. 2,000,000 free basemap tiles, 20,000 non-stored geocodes, 20,000 simple routes, 5,000 drive time calculations, 5GB free tile+data storage per month.
   * [Foursquare](https://developer.foursquare.com/) - 来自 Places API 和 Pilgrim SDK 的位置发现、场地搜索和上下文感知内容.
   * [geoapify.com](https://www.geoapify.com/)  - 矢量和栅格地图切片、地理编码、地点、路线、等值线 API. 每天 3000 个免费请求.
   * [geocod.io](https://www.geocod.io/)  — 通过 API 或 CSV 上传进行地理编码. 每天 2,500 次免费查询.
   * [geocodify.com](https://geocodify.com/)  — 通过 API 或 CSV 上传进行地理编码和地理解析.  10k 免费查询/月.
   * [giscloud.com](https://www.giscloud.com/) — Visualize, analyze and share geo data online.
   * [gogeo.io](https://gogeo.io/) — Maps and geospatial services with an easy to use API and support for big data.
   * [graphhopper.com](https://www.graphhopper.com/) 为开发人员提供了一个免费包，用于路由、路线优化、距离矩阵、地理编码、地图匹配.
   * [here](https://developer.here.com/)  — 用于地图和位置感知应用的 API 和 SDK.  250k 交易/月免费.
   * [mapbox.com](https://www.mapbox.com/) — Maps, geospatial services and SDKs for displaying map data.
   * [maptiler.com](https://www.maptiler.com/cloud/)  — 用于地图可视化的矢量地图、地图服务和 SDK. 具有每周更新和四种地图样式的免费矢量瓷砖.
   * [opencagedata.com](https://opencagedata.com) — Geocoding API that aggregates OpenStreetMap and other open geo sources. 2,500 free queries/day.
   * [osmnames](https://osmnames.org/) — 地理编码，搜索结果按相关维基百科页面的受欢迎程度排名.
   * [positionstack](https://positionstack.com/)  - 全球地点和坐标的免费地理编码. 每月 25.000 个供个人使用的请求.
   * [stadiamaps.com](https://stadiamaps.com/)  — 地图图块、路线、导航和其他地理空间 API. 每天 2,500 次免费地图视图和 API 请求，用于非商业用途和测试.
   * [maps.stamen.com](http://maps.stamen.com/) - Free map tiles and tile hosting.
   * [GeocodeAPI](https://geocodeapi.io) - Geocode API: Address to Coordinate Conversion & Geoparsing based on Pelias. Batch geocoding via CSV. 350000 free requests/month.
   * [Geokeo api](https://geokeo.com)  - 具有语言校正等功能的地理编码 API. 全球覆盖. 每日 2,500 次免费查询


## Package Build System

   * [build.opensuse.org](https://build.opensuse.org/) — Package build service for multiple distros (SUSE, EL, Fedora, Debian etc).
   * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — Mock-based RPM build service for Fedora and EL.
   * [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu and Debian build service.


## IDE and Code Editing

   * [3v4l](https://3v4l.org/) - Free online PHP shell and snippet sharing site, runs your code in 300+ PHP versions
   * [Android Studio](https://d.android.com/studio)  — Android Studio 为在各种类型的 Android 设备上构建应用程序提供了最快的工具. 开源 IDE，对所有人免费，是开发 Android 应用程序的最佳选择. 适用于 Windows、Mac、Linux 甚至 ChromeOS！
   * [Apache Netbeans](https://netbeans.apache.org/) — 开发环境、工具平台和应用框架.
   * [apiary.io](https://apiary.io/) — Collaborative design API with instant API mock and generated documentation (Free for unlimited API blueprints and unlimited user with one admin account and hosted documentation).
   * [Atom](https://atom.io/) - Atom 是一个基于 Electron 的可破解文本编辑器.
   * [Binder](https://mybinder.org/) - Turn a Git repo into a collection of interactive notebooks. It is a free, public service.
   * [BlueJ](https://bluej.org)  — 专为初学者设计的免费 Java 开发环境，全球数百万人使用. 由 Oracle 和简单的 GUI 提供支持，以帮助初学者.
   * [Bootify.io](https://bootify.io/) - Spring Boot app generator with custom database and REST API.
   * [cacher.io](https://www.cacher.io) — 带有标签的代码片段管理器，支持 100 多种编程语言.
   * [Code::Blocks](https://codeblocks.org) — Free Fortran & C/C++ IDE. Open Source and runs on Windows,macOS & Linux.
   * [codiga.io](https://codiga.io/) — Coding Assistant that lets you search, define and reuse code snippets directly in your IDE. Free for individual and small organizations.
   * [codesnip.com.br](https://codesnip.com.br)  — 带有类别、搜索和标签的简单代码片段管理器. 免费且无限制.
   * [cocalc.com](https://cocalc.com/) — (formerly SageMathCloud at cloud.sagemath.com) — Collaborative calculation in the cloud. Browser access to full Ubuntu with built-in collaboration and lots of free software for mathematics, science, data science, preinstalled: Python, LaTeX, Jupyter Notebooks, SageMath, scikitlearn, etc.
   * [ide.cs50.io](https://ide.cs50.io/) - 由哈佛大学提供的由 AWS Cloud9 提供支持的免费 IDE.
   * [codepen.io](https://codepen.io/) — CodePen 是 Web 前端的游乐场.
   * [codesandbox.io](https://codesandbox.io/) — Online Playground for React, Vue, Angular, Preact and more.
   * [Components.studio](https://webcomponents.dev/) - Code components in isolation, visualize them in stories, test them and publish them on npm.
   * [Eclipse Che](https://www.eclipse.org/che/) - Web based and Kubernetes-Native IDE for Developer Teams with multi-language support. Open Source and community driven. A online instance hosted by Red Hat is available at [workspaces.openshift.com](https://workspaces.openshift.com/).
   * [fakejson.com](https://fakejson.com/) — FakeJSON helps you quickly generate fake data using its API. Make an API request describing what you want and how you want it. The API returns it all in JSON. Speed up the go to market process for ideas and fake it till you make it.
   * [gitpod.io](https://www.gitpod.io) — Instant, ready-to-code dev environments for GitHub projects. Free for open source.
   * [ide.goorm.io](https://ide.goorm.io) goormIDE is full IDE on cloud. multi-language support, linux-based container via the fully-featured web-based terminal, port forwarding, custom url, real-time collaboration and chat, share link, Git/Subversion support. There are many more features (free tier includes 1GB RAM and 10GB Storage per container, 5 Container slot).
   * [JDoodle](https://www.jdoodle.com) — 超过 60 种编程语言的在线编译器和编辑器，提供免费的 REST API 代码计划，每天最多编译 200 个积分.
   * [jetbrains.com](https://jetbrains.com/products.html) — Productivity tools, IDEs and deploy tools (aka [IntelliJ IDEA](https://www.jetbrains.com/idea/), [PyCharm](https://www.jetbrains.com/pycharm/) ， 等等）. 学生、教师、开源和用户组的免费许可证.
   * [jsbin.com](https://jsbin.com) — JS Bin 是另一个前端 Web（HTML、CSS 和 JavaScript.也支持 Markdown、Jade 和 Sass）的游乐场和代码共享站点.
   * [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle 是前端 web 的游乐场和代码共享站点，也支持协作.
   * [JSONPlaceholder](http://jsonplaceholder.typicode.com/) Some REST API endpoints that return some fake data in JSON format. The source code is also available if you would like to run the server locally.
   * [Katacoda](https://katacoda.com) — 面向软件工程师的交互式学习和培训平台，帮助开发人员学习和公司提高采用率.
   * [Lazarus](https://www.lazarus-ide.org/) — Lazarus is a Delphi compatible cross-platform IDE for Rapid Application Development.
   * [micro-jaymock](https://micro-jaymock.now.sh/) - 用于生成虚假 JSON 数据的微型 API 模拟微服务.
   * [mockable.io](https://www.mockable.io/)  — Mockable 是一个简单的可配置服务，用于模拟 RESTful API 或 SOAP Web 服务. 此在线服务允许您快速定义 REST API 或 SOAP 端点并让它们返回 JSON 或 XML 数据.
   * [mockaroo](https://mockaroo.com/)  — Mockaroo 让您可以生成 CSV、JSON、SQL 和 Excel 格式的真实测试数据. 您还可以为后端 API 创建模拟.
   * [Mocklets](https://mocklets.com) - a HTTP-based mock API simulator, which helps simulate APIs for faster parallel development and more comprehensive testing, with lifetime free tier.
   * [Paiza](https://paiza.cloud/en/)  — 在浏览器中开发 Web 应用程序，无需进行任何设置. 免费计划提供 1 台服务器，其使用寿命为 24 小时，每天运行时间为 4 小时，配备 2 个 CPU 内核、2 GB RAM 和 1 GB 存储空间.
   * [Prepros](https://prepros.io/) - Prepros can compile Sass, Less, Stylus, Pug/Jade, Haml, Slim, CoffeeScript and TypeScript out of the box, reloads your browsers and makes it really easy to develop & test your websites so you can focus on making them perfect. You can also add your own tools with just a few clicks.
   * [Replit](https://replit.com/) — 适用于各种程序语言的云编码环境.
   * [SoloLearn](https://code.sololearn.com)  — 一个非常适合运行代码片段的云编程游乐场. 支持各种编程语言. 运行代码不需要注册，但当您需要在他们的平台上保存代码时需要. 还为初学者和中级编码人员提供免费课程.
   * [stackblitz.com](https://stackblitz.com/) — Online/Cloud Code IDE to create, edit, & deploy fullstack apps. Support any popular NodeJs based frontend & backend frameworks. Shortlink to create new project: [https://node.new](https://node.new).
   * [Visual Studio Code](https://code.visualstudio.com/)  - 代码编辑器重新定义和优化，用于构建和调试现代 Web 和云应用程序. 由 Microsoft 为 Windows、macOS 和 Linux 开发.
   * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — Fully-featured IDE with thousands of extensions, cross-platform app development (Microsoft extensions available for download for iOS and Android), desktop, web and cloud development, multi-language support (C#, C++, JavaScript, Python, PHP and more).
   * [VSCodium](https://vscodium.com/) - Community-driven, without telemetry/tracking, and freely-licensed binary distribution of Microsoft’s editor VSCode
   * [wakatime.com](https://wakatime.com/) — Quantified self-metrics about your coding activity, using text editor plugins, limited plan for free.
   * [WebComponents.dev](https://webcomponents.dev/) — 浏览器内的 IDE 可独立地编写 Web 组件，提供 58 个模板，支持故事和测试.


## Analytics, Events and Statistics

   * [Statvoo Analytics](https://analytics.statvoo.com/) — 为您的所有网站提供永久免费的客户分析，每月无限次活动
   * [Avo](https://avo.app/)  — 简化的分析发布工作流程. 单一真实来源跟踪计划、类型安全分析跟踪库、应用内调试器、数据可观察性，以便在发布之前捕获所有数据问题.  2 个工作区成员和 1 小时数据可观察性回溯免费.
   * [Branch](https://branch.io) — Mobile Analytics Platform. Free Tier offers upto 10K Mobile App Users with deep-linking & other services.
   * [Clicky](https://clicky.com) — Website Analytics Platform. Free Plan for 1 website with 3000 views analytics.
   * [Databox](https://databox.com)  — 通过结合其他分析和 BI 平台获得业务洞察力和分析. 免费计划提供 3 个用户、仪表板和数据源.  11M 历史数据记录.
   * [indicative.com](https://indicative.com/) — Customer analytics platform to optimize customer engagement, increase conversion, and improve retention. Free up to 50M events/month.
   * [Panelbear.com](https://panelbear.com/) — Blazingly fast and private, free tier includes 5,000 pageviews per month for unlimited websites
   * [Hitsteps.com](https://hitsteps.com/) — 1 个网站每月 2,000 次浏览量
   * [amplitude.com](https://amplitude.com/) — 每月 100 万个事件，最多 2 个应用程序
   * [Flagsmith](https://www.molasses.app) - Release features with confidence; manage feature flags across web, mobile, and server side applications. Use our hosted API, deploy to your own private cloud, or run on-premise
   * [GoatCounter](https://www.goatcounter.com/)  — GoatCounter 是一个开源网络分析平台，可作为托管服务（非商业用途免费）或自托管应用程序提供. 它旨在提供易于使用且有意义的隐私友好型网络分析，以替代 Google Analytics 或 Matomo. 免费套餐用于非商业用途，包括无限数量的网站、6 个月的数据保留期和 10 万次/月的网页浏览量.
   * [Google Analytics](https://analytics.google.com/) — Google Analytics
   * [Expensify](https://www.expensify.com/) — Expense reporting, free personal reporting approval workflow
   * [getinsights.io](https://getinsights.io) - 以隐私为重点的无 cookie 分析，每月最多可免费处理 5k 个事件.
   * [heap.io](https://heap.io)  — 自动捕获 iOS 或 Web 应用程序中的每个用户操作. 每月最多 5,000 次访问免费
   * [Hotjar](https://hotjar.com) — Website Analytics and Reports . Free Plan allows 2000 pageviews/day. 100 snapshots/day (max capacity: 300). 3 snapshot heatmaps which can be stored for 365 days. Unlimited Team Members.
   * [Keen](https://keen.io/)  — 用于数据收集、分析和可视化的自定义分析.  50,000 个事件/月免费
   * [Yandex.Metrica](https://metrica.yandex.com/) — 无限制的免费分析
   * [Mixpanel](https://mixpanel.com/) — 100,000 月度跟踪用户、无限数据历史记录和席位、美国或欧盟数据驻留
   * [Moesif](https://www.moesif.com)  — REST 和 GraphQL 的 API 分析.  （每月最多免费调用 500,000 次 API 调用）
   * [Molasses](https://www.molasses.app)  - 强大的功能标志和 A/B 测试. 最多释放 3 个环境，每个环境有 5 个功能标志.
   * [optimizely.com](https://www.optimizely.com) — A/B Testing solution, free starter plan, 1 website, 1 iOS and 1 Android app
   * [Microsoft PowerBI](https://powerbi.com)  — Microsoft 的业务洞察与分析. 免费计划提供 100 万用户许可证的有限使用.
   * [quantcast.com](https://www.quantcast.com/products/measure-audience-insights/) — 无限制的免费分析
   * [sematext.com](https://sematext.com/cloud/) — Free for up to 50 K actions/month, 1-day data retention, unlimited dashboards, users, etc.
   * [Similar Web](https://similarweb.com) — Analytics for Web & Mobile Apps. Free Plan offers 5 results per metric, 1 month of mobile app data & 3 months of website data.
   * [StatCounter](https://statcounter.com/) — Website Viewer Analytics. Free plan for analytics of 500 most recent visitors.
   * [Tableau Developer Program](https://www.tableau.com/developer)  — 创新、创建并让 Tableau 完美地为您的组织工作. 免费的开发人员计划为 Tableau Online 提供了个人开发沙盒许可证. 该版本是最新的预发布版本，因此数据开发人员可以测试这个一流平台的每一个功能.
   * [usabilityhub.com](https://usabilityhub.com/)  — 在真人身上测试设计和模型，跟踪访客. 一位用户免费，无限制测试
   * [woopra.com](https://www.woopra.com/) — Free user analytics platform for 500K actions, 90 day data retention, 30+ one click integration.
   * [counter.dev](https://counter.dev)  — 网络分析变得简单，因此对隐私友好. 免费或通过捐赠支付您想要的东西.
   * [PostHog](https://posthog.com) - Full Product Analytics suite free for up to 1m tracked events per month


## Visitor Session Recording

   * [Visualime.com](https://www.visualime.com/) — Free and unlimited session recordings, no traffic limits
   * [Reactflow.com](https://www.reactflow.com/) — 每个站点：每天 1,000 个页面浏览量、3 个热图、3 个小部件、免费的错误跟踪
   * [LogRocket.com](https://www.logrocket.com) - 每月 1,000 次会话，保留 30 天，错误跟踪，实时模式
   * [FullStory.com](https://www.fullstory.com)  — 1,000 次会话/月，1 个月的数据保留期和 3 个用户席位. 更多信息 [here](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition).
   * [hotjar.com](https://www.hotjar.com/) — 每个站点：每天 2,000 次页面浏览量，3 个热图，存储 3 个月的数据，...
   * [inspectlet.com](https://www.inspectlet.com/) — 1 个网站每月免费 2,500 次会话
   * [livesession.io](https://livesession.io/) — 1 个网站每月免费 5,000 次会话
   * [Microsoft Clarity](https://clarity.microsoft.com/) - Session recording completely free with "no traffic limits", no project limits, and no sampling
   * [mouseflow.com](https://mouseflow.com/) — 1 个网站每月免费 500 次会话
   * [mousestats.com](https://www.mousestats.com/) — 100 sessions/month free for 1 website
   * [smartlook.com](https://www.smartlook.com/) — Web 和移动应用程序的免费包（1500 个会话/月）、3 个热图、1 个漏斗、1 个月的数据历史记录
   * [usersurge.com](https://www.usersurge.com/) — 个人每月 25 万次会话.
   * [howuku.com](https://howuku.com)  — 跟踪用户交互、参与度和事件. 每月最多 5,000 次访问免费
   * [UXtweak.com](https://www.uxtweak.com/) — Record and watch how visitors use your web site or app. Free unlimited time for small projects


## International Mobile Number Verification API and SDK

  * [Cognalys](https://cognalys.com/)  — 通过一种创新且可靠的方法验证免费增值手机号码，而不是使用 SMS 网关. 每天免费 10 次尝试和 15 次验证
  * [numverify](https://numverify.com/) — Global phone number validation and lookup JSON API. 250 API requests/month
  * [veriphone](https://veriphone.io/) — Global phone number verification in a free, fast, reliable JSON API. 1000 requests/month


## Payment and Billing Integration

  * [CurrencyFreaks](https://currencyfreaks.com/)  — 提供当前和历史货币汇率. 免费的 DEVELOPER 计划可用于每月 1000 个请求.
  * [CurrencyApi](https://currencyapi.net/) — Live Currency Rates for Physical and Crypto currencies, delivered in JSON and XML. Free tier offers 1,250 API requests/month.
  * [currencylayer](https://currencylayer.com/) — 为您的业务提供可靠的汇率和货币转换，每月免费 1,000 个 API 请求
  * [currencystack.io](https://currencystack.io/) — 154 种货币的生产就绪实时汇率.
  * [exchangerate-api.com](https://www.exchangerate-api.com)  - 一个易于使用的货币转换 JSON API. 免费套餐，没有请求限制.
  * [FraudLabsPRO](https://www.fraudlabspro.com)  — 帮助商家防止支付欺诈和退款. 免费的微型计划可用于每月 500 次查询.
  * [MailPopin](https://mailpop.in) - Get the most of your Stripe notifications with contextualized information.
  * [Nami ML](https://www.namiml.com/) - Complete platform for in-app purchases and subscriptions on iOS and Android, including no-code paywalls, CRM, and analytics.  Free for all base features to run an IAP business.
  * [RevenueCat](https://www.revenuecat.com/)  — 用于应用内购买和订阅（iOS 和 Android）的托管后端. 最多可释放 $10k/mo 的跟踪收入.
  * [vatlayer](https://vatlayer.com/) — 即时增值税号验证和欧盟增值税率 API，每月免费 100 个 API 请求
  * [Freecurrencyapi.net](https://freecurrencyapi.net/)  — 免费的货币换算和汇率数据API.  10 个请求/小时，没有 API 密钥，当您免费注册时，每月 50 000 个请求.


## Docker Related

  * [canister.io](https://canister.io/) — 为开发人员提供 20 个免费的私有仓库，为团队构建和存储 Docker 镜像提供 30 个免费的私有仓库
  * [Container Registry Service](https://container-registry.com/)  - 基于港口的集装箱管理解决方案. 免费套餐为私有存储库提供 1 GB 存储空间.
  * [Docker Hub](https://hub.docker.com) — One free private repository and unlimited public repositories to build and store Docker images
  * [Play with Docker](https://labs.play-with-docker.com/) — 一个简单、互动且有趣的 Docker 学习平台.
  * [quay.io](https://quay.io/) — Build and store container images with unlimited free public repositories
  * [TreeScale.com](https://treescale.com/)  — 使用组权限托管和管理容器镜像. 免费套餐为私有存储库提供 1 GB 存储空间.
  * [Platform9](https://platform9.com/)  - 托管 Kubernetes 平面. 免费计划提供多达 3 个集群和 20 个节点的管理功能. 注意：您必须自己提供集群基础设施.


## Vagrant Related

  * [Vagrant Cloud](https://app.vagrantup.com) - HashiCorp Vagrant Cloud. Vagrant box hosting.
  * [Vagrantbox.es](https://www.vagrantbox.es/) — An alternative public box index


## Dev Blogging Sites

  * [BearBlog](https://bearblog.dev/) - 极简主义和 Markdown 驱动的博客和网站构建器.
  * [Dev.to](https://dev.to/) - Where programmers share ideas and help each other grow.
  * [Hashnode](https://hashnode.com/) — 面向开发人员的无忧博客软件！.
  * [Medium](https://medium.com/) — 更聪明地了解对您而言重要的事情.


## Commenting Platforms
  * [Staticman](https://staticman.net/) - Staticman 是一个 Node.js 应用程序，它接收用户生成的内容并将其作为数据文件上传到 GitHub 和/或 GitLab 存储库，使用拉取请求.
  * [GraphComment](https://graphcomment.com/) - GraphComment 是一个评论平台，可帮助您从网站的受众中建立一个活跃的社区.
  * [Utterances](https://utteranc.es/) - A lightweight comments widget built on GitHub issues. Use GitHub issues for blog comments, wiki pages and more!
  * [Disqus](https://disqus.com/) - Disqus 是一个网络社区平台，被网络上成千上万的网站使用.


## Screenshot APIs

  * [24browser.com](https://www.24browser.com) – 使用强大的 API 大规模捕获渲染精美的网站屏幕截图.
  * [ApiFlash](https://apiflash.com) — A screenshot API based on Aws Lambda and Chrome. Handles full page, capture timing, viewport dimensions, ...
  * [microlink.io](https://microlink.io/)  – 它将任何网站转化为数据，例如元标记标准化、美容链接预览、抓取功能或屏幕截图即服务. 每天 250 个请求/天免费.
  * [ScreenshotAPI.net](https://screenshotapi.net/)  - 截图 API 使用一个简单的 API 调用来生成任何网站的截图. 构建以扩展并托管在 Google Cloud 上. 每月提供 100 个免费截图.
  * [screenshotlayer.com](https://screenshotlayer.com/)  — 捕获任何网站的高度可定制的快照. 每月免费 100 张快照
  * [screenshotmachine.com](https://www.screenshotmachine.com/) — Capture 100 snapshots/month, png, gif and jpg, including full-length captures, not only home page
  * [PhantomJsCloud](https://PhantomJsCloud.com)  — 浏览器自动化和页面渲染. 免费套餐每天最多提供 500 页. 自 2017 年起免费套餐.
  * [Webshrinker.com](https://webshrinker.com) <i>— Web Shrinker provides web site screenshot and domain intelligence API services.</i> <b>— Web Shrinker 提供网站截图和领域智能 API 服务。</b> <i>Free 100 requests/month.</i><b>每月免费 100 个请求。</b>


## Browser based hardware emulation written in Javascript

  * [JsLinux](https://bellard.org/jslinux) — a really fast x86 virtual machine capable of running Linux and Windows 2k.
  * [Jor1k](http://s-macke.github.io/jor1k/demos/main.html) —  a OpenRISC virtual machine capable of running Linux with network support.
  * [v86](https://copy.sh/v86) — 能够在浏览器中直接运行 Linux 和其他操作系统的 x86 虚拟机.


## Privacy Management
  * [Bearer](https://www.bearer.sh/)  - 通过审计和持续的工作流程帮助通过设计实现隐私，以便组织遵守 GDPR 和其他法规. 免费套餐仅限于较小的团队和 SaaS 版本.
  * [Osano](https://www.osano.com/)  - 同意管理和合规平台，包括从 GDPR 表示到 cookie 横幅的所有内容. 免费套餐提供基本功能.
  * [Iubenda](https://www.iubenda.com/) - Privacy and cookie policies along with consent management. Free tier offers limited privacy and cookie policy as well as cookie banners.
  * [Cookiefirst](https://cookiefirst.com/) - Cookie banners, auditing, and multi-language consent management solution. Free tier offers a one-time scan and a single banner.
  * [Ketch](https://www.ketch.com/) - Consent management and privacy framework tool. Free tier offers most features with a limited visitor count.


## Miscellaneous

  * [Smartcar API](https://smartcar.com) - An API for cars to locate, get fuel tank, battery levels, odometer, unlock/lock doors, etc.
  * [Blynk](https://blynk.io) — A SaaS with API to control, build & evaluate IoT devices. Free Developer Plan with 5 devices,Free Cloud & data storage. Mobile Apps also available.
  * [Bricks Note Calculator](https://free.getbricks.app/) - a note-taking app (PWA) with a powerful built-in multiline calculator.
  * [Carbon.now.sh](https://carbon.now.sh) - create and share code snippet in an aesthetic screenshot-like image format. Usually used to aesthetically share/show-off code snippet on Twitter or blog posts.
  * [Code Time](https://www.software.com/code-time) - an extension for time-tracking and coding metrics in VS Code, Atom, IntelliJ, Sublime Text, and more.
  * [Codepng](https://www.codepng.app) - 从您的源代码创建很棒的快照，您可以在社交媒体上分享.
  * [ConfigCat](https://configcat.com)  - 跨平台功能标志服务. 适用于所有主要语言的 SDK. 免费计划每月最多 10 个标志、2 个环境、1 个产品和 500 万个请求. 无限用户席位. 学生每月免费获得 100 个标志和 1 亿个请求.
  * [datelist.io](https://datelist.io)  - 在线预约/预约调度系统. 每月最多可免费预订 5 次，包括 1 个日历
  * [docsapp.io](https://www.docsapp.io/) — 发布文档的最简单方式，对开源免费
  * [Elementor](https://elementor.com)  — WordPress 网站建设者. 免费计划提供 40 多个基本小部件.
  * [Form2Channel](https://form2channel.com) — Place a static html form on your website and receive submissions directly to Google Sheets, Email, Slack, Telegram or Http. No coding necessary.
  * [FOSSA](https://fossa.com/) - 对第三方代码、许可证合规性和漏洞进行可扩展的端到端管理.
  * [fullcontact.com](https://www.fullcontact.com/developer/pricing/)  — 通过将社交资料添加到您的应用程序中，帮助您的用户更多地了解他们的联系人.  500 次免费 Person API 匹配/月
  * [http2.pro](https://http2.pro) — HTTP/2 协议就绪测试和客户端 HTTP/2 支持检测 API.
  * [JWT Decoder](https://jwt.ssotools.com/) — 用于解码 JWT（JSON Web 令牌）并验证其签名的在线免费工具.
  * [Base64 decoder/encoder](https://devpal.co/base64-decode/) — 用于解码和编码数据的在线免费工具.
  * [newreleases.io](https://newreleases.io/) - Receive notifications on email, Slack, Telegram, Discord and custom webhooks for new releases from GitHub, GitLab, Bitbucket, Python PyPI, Java Maven, Node.js NPM, Node.js Yarn, Ruby Gems, PHP Packagist, .NET NuGet, Rust Cargo and Docker Hub.
  * [PDFMonkey](https://www.pdfmonkey.io/) — Manage PDF templates in a dashboard, call the API with dynamic data, download your PDF. Offers 1000 free documents per month.
  * [QuickType.io](https://quicktype.io/) - Quickly auto generate models/class/type/interface and serializers from JSON, schema, and GraphQL for working with data quickly & safely in any programming language. Convert JSON into gorgeous, typesafe code in any language.
  * [ray.so](https://ray.so/) - 为您的代码片段创建漂亮的图像.
  * [readme.com](https://readme.com/) — 美丽的文档让开源变得简单，免费.
  * [redirection.io](https://redirection.io/) — SaaS tool for managing HTTP redirections for businesses, marketing and SEO.
  * [redirect.pizza](https://redirect.pizza/) - Easily manage redirects with HTTPS support. Free plan includes 10 sources and 100.000 hits per month.
  * [ReqBin](https://www.reqbin.com/)  — 在线发布 HTTP 请求. 流行的请求方法包括 GET、POST、PUT、DELETE 和 HEAD. 支持标头和令牌身份验证. 包括用于保存您的请求的基本登录系统.
  * [superfeedr.com](https://superfeedr.com/)  — 实时 PubSubHubbub 兼容的订阅源、导出、分析. 免费，定制更少
  * [SurveyMonkey.com](https://www.surveymonkey.com) — Create online surveys. Analyze the results online.  Free plan allows only 10 questions and 100 responses per survey.
  * [videoinu](https://videoinu.com) — 在线创建和编辑屏幕录像和其他视频.
  * [RandomKeygen](https://randomkeygen.com/) - A free mobile-friendly tool offers a variety of randomly generated keys and passwords you can use to secure any application, service or device.
  * [Cronhooks](https://cronhooks.io/) - Replace your cron jobs with webhooks. Invoke any webhook at a given date time or repeatedly using cron expressions. Free plan allows 1 webhook schedule.
  * [Hook Relay](https://www.hookrelay.dev/) - Add webhook support to your app without the hassles: done-for-you queueing, retries with backoff, and logging. The free plan has 100 deliveries per day, 14-day retention, and 3 hook endpoints.
  * [Format Express](https://www.format-express.dev) - Instant online formatter for JSON / XML / SQL.


## Remote Desktop Tools

  * [Getscreen.me](https://getscreen.me) — 2 台设备免费，会话数量和持续时间没有限制
  * [Apache Guacamole™](https://guacamole.apache.org/) — 开源无客户端远程桌面网关


## Other Free Resources

  * [get.localhost.direct](https://get.localhost.direct) — 更好的 *.localhost.direct 通配符公共 CA 签名 SSL 证书，用于 localhost 开发，支持子域  
  * [eu.org](https://nic.eu.org)  — 免费 eu.org 域. 请求通常在 14 天内获得批准.
  * [js.org](https://js.org) - 用于 JavaScript 社区的 GitHub Pages 的免费 js.org 子域.
  * [pp.ua](https://nic.ua/) — 免费 pp.ua 子域.
  * [Framacloud](https://degooglisons-internet.org/en/list/) — 法国非营利组织的免费/自由开源软件和 SaaS 列表 [Framasoft](https://framasoft.org/en/).
  * [getawesomeness](https://getawesomeness.herokuapp.com) — Retrieve all amazing awesomeness from GitHub... a must see
  * [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) — 面向开发人员的免费和开源软件中心.
  * [GitHub Education](https://education.github.com/pack) — Collection of free services for students. Registration required.
  * [is-a.dev](https://www.is-a.dev/) — 为开发人员提供免费的 `*.is-a.dev` 子域.
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program) — Get a free sandbox, tools, and other resources you need to build solutions for the Microsoft 365 platform. The subscription is a 90-day [Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5)  （Windows 除外）这是可更新的. 如果您积极参与开发（使用遥测数据和算法测量），它会被更新.
  * [RedHat for Developers](https://developers.redhat.com)  — 专为开发人员免费访问红帽产品，包括 RHEL、OpenShift、CodeReady 等. 仅限个人计划. 还提供免费电子书以供参考.
  * [smsreceivefree.com](https://smsreceivefree.com/) — Provides free temporary and disposable phone numbers.
  * [simplebackups.io](https://simplebackups.io/) — Backup automation service for servers and databases (MySQL, PostgreSQL, MongoDB) stored directly into cloud storage providers (AWS, DigitalOcean, Backblaze...). Provides free plan for 1 backup.
  * [SnapShooter](https://snapshooter.com/) — Backup solution for DigitalOcean, AWS, LightSail, Hetzner and Exoscale, with support for direct database, file system and application backups to s3 based storage. Provides a free plan with daily backups for one resource.
  * [thedev.id](https://thedev.id) — 为开发人员提供的免费 thedev.id 子域.
  * [Themeselection](https://themeselection.com/) — 精选高品质、现代设计、专业且易于使用的免费管理仪表板模板，
HTML Themes and UI Kits to create your applications faster!
  * [Web.Dev](https://web.dev/measure/) — 这是一个免费工具，可让您查看网站的性能并改进 SEO 以在搜索引擎中获得更高的排名列表.
  * [SmallDev.tools](https://smalldev.tools/) — A free tool for developers that allows you to Encode/Decode various formats, Minify HTML/CSS/Javascript, Beautify, Generate Fake/Testing real like dataset in JSON/CSV & multiple other formats and many more features. With a delightful interface.
