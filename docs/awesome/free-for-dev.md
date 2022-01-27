<div class="github-widget" data-repo="ripienaar/free-for-dev"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## free-for.dev

Developers and Open Source authors now have a massive amount of services offering free tiers, but it can be hard to find them all to make informed decisions.

This is a list of software (SaaS, PaaS, IaaS, etc.) and other offerings that have free tiers for developers.

此特定列表的范围仅限于基础设施开发人员（系统管理员、DevOps 从业者等）可能会发现有用的内容. 我们喜欢那里的所有免费服务，但最好保持主题. 有时它有点像一条灰线，所以这有点固执己见； 如果我不接受您的贡献，请不要生气.

This list is the result of Pull Requests, reviews, ideas and work done by 1000+ people. You too can help by sending [Pull Requests](https://github.com/ripienaar/free-for-dev) 添加更多服务或删除其产品已更改或已停用的服务.

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

 *注意：* 此列表仅适用于即服务产品，不适用于自托管软件. 要使一项服务符合条件，它必须提供免费套餐，而不仅仅是免费试用. 如果免费套餐有时间限制，则必须至少为一年. 我们还从安全角度考虑免费层，因此 SSO 很好，但我不会接受将 TLS 限制为仅付费层的服务.

目录
=================


## Major Cloud Providers

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 每天 28 个前端实例小时，每天 9 个后端实例小时
    * Cloud Firestore - 1GB storage, 50,000 reads, 20,000 writes, 20,000 deletes per day
    * Compute Engine - 1 non-preemptible e2-micro, 30GB HDD, 5GB snapshot storage (restricted to certain regions), 1 GB network egress from North America to all region destinations (excluding China and Australia) per month
    * 云存储 - 5GB、1GB 网络出口
    * Cloud Shell - Web-based Linux shell/basic IDE with 5GB of persistent storage. 60 hours limit per week
    * Cloud Pub/Sub - 每月 10GB 的消息
    * Cloud Functions - 每月 200 万次调用（包括后台和 HTTP 调用）
    * Cloud Run - 每月 200 万次请求、360,000 GB 秒内存、180,000 vCPU 秒计算时间、每月从北美流出的 1 GB 网络
     * Google Kubernetes Engine - 一个区域集群不收取集群管理费. 每个用户节点均按标准 Compute Engine 价格收费
    * BigQuery - 每月 1 TB 的查询，每月 10 GB 的存储空间
    * Cloud Build - 120 build-minutes per day
    * 云源存储库 - 最多 5 个用户、50 GB 存储、50 GB 出口
    * Full, detailed list - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * Amazon CloudFront - 1TB egress per month
    * Amazon DynamoDB - 25GB NoSQL 数据库
    * Amazon EC2 - 100GB aggregated egress per month
    * Amazon EC2 - t2.micro 或 t3.micro 每月 750 小时
    * Amazon EBS - 30GB per month of General Purpose (SSD) or Magnetic
    * Amazon ELB - 750 hours per month
    * Amazon Lambda - 1 million requests per month
    * Amazon SNS - 每月 100 万次发布
    * Amazon SES - 62.000 messages per month
    * Amazon Cloudwatch - 10 custom metrics and 10 alarms
    * Amazon Glacier - 10GB 长期对象存储
    * Amazon SQS - 1 million messaging queue requests
    * Amazon CodeBuild - 每月 100 分钟的构建时间
    * Amazon CodeCommit - 每月 5 个活跃用户
    * Amazon CodePipeline - 1 active pipeline per month
    * 完整、详细的列表 - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1 B1S Linux VM, 1 B1S Windows VM
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 web, mobile or API apps
    * [Functions](https://azure.microsoft.com/services/functions/) - 1 million requests per month
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - Enable fast, easy, and lean dev-test environments
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 objects
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 50,000 monthly stored users
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 active users, unlimited private Git repos
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10 个免费的并行作业，时间不受限制，适用于 Linux、macOS 和 Windows 的开源
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 8,000 messages per day
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1 个免费的公共负载平衡 IP (VIP)
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 1 million push notifications
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 每月 5GB 出口
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 5GB storage and 400 RUs of provisioned throughput
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) — Build, deploy and host static apps and serverless functions, with free SSL, Authentication/Authorization and custom domains
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS File or Blob storage
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML APIs (Computer Vision, Translator, Face detection, Bots...) with free tier including limited transactions
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - 基于人工智能的搜索和索引服务，10,000 份文档免费
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - 托管 Kubernetes 服务，免费集群管理
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 100K ops/month
    * 完整、详细的清单 - [https://azure.microsoft.com/free/](https://azure.microsoft.com/free/)

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * 计算 - 2 个基于 x64，每个具有 1 GB RAM，4 个基于 Arm 的 Ampere A1 内核和 24 GB 内存，可用作一个 VM 或最多 4 个 VM
    * Block Volume - 4 volumes, 200 GB total (used for compute)
    * Object Storage - 10 GB
    * 负载均衡器 - 1 个 10 Mbps 的实例
    * Databases - 2 DBs, 20 GB each
    * 监控 - 5 亿个摄取数据点，10 亿个检索数据点
    * 带宽 - 每月 10 TB 出口，基于 x64 的 VM 上的速度限制为 50 Mbps，500 Mbps * 基于 ARM 的 VM 上的核心数
    * Public IP - 2 IPv4 for VMs, 1 IPv4 for load balancer
    * 通知 - 每月 100 万个递送选项，每月发送 1000 封电子邮件
    * 完整、详细的列表 - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloud Functions - 每月执行 500 万次
    * Object Storage - 25GB per month
    * Cloudant database - 1 GB of data storage
    * Db2 database - 100MB of data storage
    * API Connect - 每月 50,000 次 API 调用
    * Availability Monitoring - 3 million data points per month
    * Log Analysis - 500MB of daily log
    * Full, detailed list - https://www.ibm.com/cloud/free/


## Cloud management solutions
  * [Brainboard](https://www.brainboard.co) - 从端到端可视化构建和管理云基础架构的协作解决方案.
  * [terraform.io](https://www.terraform.io/) — Terraform Cloud. Free remote state management and team collaboration for teams up to 5 users.


## Source Code Repos

  * [Bitbucket](https://bitbucket.org/) — Unlimited public and private Git repos for up to 5 users with Pipelines for CI/CD
  * [chiselapp.com](http://chiselapp.com/) — Unlimited public and private Fossil repositories
  * [codebasehq.com](https://www.codebasehq.com/) — 一个 100 MB 空间和 2 个用户的免费项目
  * [Codeberg.org](https://codeberg.org/) - Unlimited public and private Git repos for free and open-source projects. Static website hosting with [Codeberg Pages](https://codeberg.page/).
  * [Gitea.com](https://www.gitea.com/) - 无限的公共和私人 Git 存储库
  * [GitGud](https://gitgud.io) — Unlimited private and public repositories. Free forever. Powered by GitLab & Sapphire. CI/CD not provided.
  * [GitHub](https://github.com/) — Unlimited public repositories and unlimited private repositories (with unlimited collaborators). Apart from this some other free services(there are much more but we list the main ones here) provided are :
       - [CI/CD](https://github.com/features/actions)(Free for Public Repos, 2000 min/month for private repos free)
       - [Static Website Hosting](https://pages.github.com) (Free for Public Repos)
       - [Package Hosting & Container Registry](https://github.com/features/packages) (Free for public repos,500 MB storage & 1GB bandwidth outside CI/CD free for private repos)
       - Project Management & Issue Tracking.
  * [gitlab.com](https://about.gitlab.com/) — Unlimited public and private Git repos with unlimited collaborators. Also offers the following features :
       - [CI/CD](https://about.gitlab.com/product/continuous-integration) （公共回购免费，私人回购每月 400 分钟）
       - Static Sites with [GitLab Pages](https://about.gitlab.com/product/pages).
       - Container Registry with 10 GB limit per repo.
       - Project Management & Issue Tracking.
  * [heptapod.net](https://foss.heptapod.net/) — Heptapod is a friendly fork of GitLab Community Edition providing support for Mercurial
  * [ionicframework.com](https://ionicframework.com/appflow) - Repo and tools to develop applications with Ionic, also you have an ionic repo
  * [NotABug](https://notabug.org) — NotABug.org 是一个免费软件代码协作平台，用于免费许可项目，基于 Git
  * [OSDN](https://osdn.net/) - OSDN.net 是为开源软件开发人员提供的免费服务，提供 SVN/Git/Mercurial/Bazaar/CVS 存储库等。
  * [Pagure.io](https://pagure.io) — Pagure.io 是一个免费的开源软件代码协作平台，用于 FOSS 许可项目，基于 Git
  * [perforce.com](https://www.perforce.com/products/helix-teamhub) — 免费 1GB 云和 Git、Mercurial 或 SVN 存储库.
  * [pijul.com](https://pijul.com/)  - 无限免费和开源的分布式版本控制系统. 它的显着特点是建立在完善的补丁理论基础上，易于学习和使用，真正的分布式. 解决了 git/hg/svn/darcs 的很多问题.
  * [plasticscm.com](https://plasticscm.com/) — Free for individuals, OSS and nonprofit organizations
  * [projectlocker.com](https://projectlocker.com) — One free private project (Git and Subversion) with 50 MB space
  * [RocketGit](https://rocketgit.com) — Repository Hosting based on Git. Unlimited Public & Private repositories.
  * [savannah.gnu.org](https://savannah.gnu.org/) - Serves as a collaborative software development management system for free Software projects (for GNU Projects)
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - 作为自由软件项目（非 GNU 项目）的协作软件开发管理系统


## APIs, Data and ML

  * [IP.City](https://ip.city) — 每天 100 个免费 IP 地理定位请求
  * [Abstract API](https://www.abstractapi.com) — API suite for a variety of use cases including IP geolocation, gender detection or even email validation.
  * [algorithmia.com](https://algorithmia.com/) — Host algorithms for free. Includes free monthly allowance for running algorithms. Now with CLI support.
  * [Apify](https://www.apify.com/) — Web scraping and automation platform to create an API for any website and extract data. Ready-made scrapers, integrated proxies, and custom solutions. Free plan with $5 platform credits included every month.
  * [API Mocha](https://apimocha.com)  - 用于测试和原型设计的完全免费的在线 API 模拟. 每天最多发出 500 个请求，完全可定制的 API 响应，将模拟规则下载为 Postman 集合.
  * [APITemplate.io](https://apitemplate.io) - Auto-generate images and PDF documents with a simple API or automation tools like Zapier & Airtable. No CSS/HTML required. Free plan comes with 50 images/month and 3 templates.
  * [Atlas toolkit](https://atlastk.org/)  - 用于开发可立即访问的单页 Web 应用程序的轻量级库. 适用于 Java、Node.js、Perl、Python 和 Ruby.
  * [Beeceptor](https://beeceptor.com)  - 在几秒钟内模拟一个休息 API，伪造 API 响应等等. 每天免费 50 个请求，公共仪表板，开放端点（任何拥有仪表板链接的人都可以查看请求和响应）.
  * [bigml.com](https://bigml.com/) — Hosted machine learning algorithms. Unlimited free tasks for development, limit of 16 MB data/task.
  * [Bruzu](https://bruzu.com/)  — 自动化图像制作. 使用 API、集成或 nocode 表生成大量图像变体.  API 是免费的，带有水印.
  * [Calendarific](https://calendarific.com)  - 超过 200 个国家的企业级公共假期 API 服务. 免费计划包括每月 1000 次通话.
  * [Clarifai](https://www.clarifai.com) — Image API for custom face recognition and detection. Able to train AI models. Free plan has 5000 calls per month.
  * [Cloudmersive](https://cloudmersive.com/) — 实用 API 平台，可完全访问广泛的 API 库，包括文档转换、病毒扫描等，每月调用 800 次.
  * [Colaboratory](https://colab.research.google.com) — Free web-based Python notebook environment with Nvidia Tesla K80 GPU.
  * [Collect2](https://collect2.com) — Create an API endpoint to test, automate, and connect webhooks. Free plan allows for two datasets, 2000 records, 1 forwarder, and 1 alert.
  * [Conversion Tools](https://conversiontools.io/)  - 用于文档、图像、视频、音频、电子书的在线文件转换器.  REST API 可用.  Node.js、PHP、Python 的库. 支持最大 50 GB 的文件（用于付费计划）. 免费套餐受文件大小和每天转换次数的限制.
  * [CraftMyPDF](https://craftmypdf.com) - Auto-Generate PDF documents from reusable templates with a drop-and-drop editor and a simple API. Free plan comes with 100 PDFs/month and 3 templates.
  * [CurlHub](https://curlhub.io) — Proxy service for inspecting and debugging API calls. Free plan includes 10,000 requests per month.
  * [CurrencyScoop](https://currencyscoop.com) - Realtime currency data API for fintech apps. Free plan includes 5000 calls per month.
  * [Datapane](https://datapane.com) - API for building interactive reports in Python and deploying Python scripts and Jupyter Notebooks as self-service tools.
  * [DB Designer](https://www.dbdesigner.net/) — 基于云的数据库模式设计和建模工具，具有 2 个数据库模型和每个模型 10 个表的免费入门计划.
  * [DeepAR](https://developer.deepar.ai)  — 适用于任何平台的增强现实面部过滤器，只需一个 SDK. 免费计划提供多达 10 个每月活跃用户 (MAU) 并跟踪多达 4 个面孔
  * [Deepnote](https://deepnote.com) - A new kind of data science notebook. Jupyter-compatible with real-time collaboration and running in the cloud. Free tier includes unlimited personal projects, up to 750 hours of standard hardware and teams with up to 3 editors.
  * [Diggernaut](https://www.diggernaut.com/)  — 基于云的网络抓取和数据提取平台，用于将任何网站转换为数据集或像使用 API 一样使用它. 免费计划包括每月 5K 页面请求.
  * [Disease.sh](https://disease.sh/) — 一个免费的 API，为构建与 Covid-19 相关的有用应用程序提供准确的数据.
  * [dominodatalab.com](https://www.dominodatalab.com) — Data science with support for Python, R, Spark, Hadoop, MATLAB and others.
  * [dreamfactory.com](https://dreamfactory.com/)  — 用于移动、Web 和 IoT 应用程序的开源 REST API 后端. 连接任何 SQL/NoSQL 数据库、文件存储系统或外部服务，它会立即创建一个具有实时文档、用户管理、...
  * [DynaPictures](https://dynapictures.com)  - 设计自动化工具，可让您通过 REST API 动态生成图像. 即时更改颜色、文本、徽标和图像. 免费计划包括每月 30 个生成的图像和 3 个图像模板.
  * [Efemarai](https://efemarai.com) - Testing and debugging platform for ML models and data. Visualize any computational graph. Free 30 debugging sessions per month for developers.
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) - Free web-based HTTP client to send HTTP requests.
  * [Export SDK](https://exportsdk.com)  - 带有拖放模板编辑器的 PDF 生成器 API，还提供 SDK 和无代码集成. 免费计划每月提供 250 页、无限用户和三个模板.
  * [FraudLabs Pro](https://www.fraudlabspro.com) — Screen an order transaction for credit card payment fraud. This REST API will detect all possible fraud traits based on the input parameters of an order. Free Micro plan has 500 transactions per month.
  * [FreeGeoIP.app](https://freegeoip.app/)  - 完全免费的地理 IP 信息（JSON、CSV、XML）. 无需注册，每小时 15000 次查询的速率限制.
  * [GeoDataSource](https://www.geodatasource.com) — Location search service lookup for city name by using latitude and longitude coordinate. Free API queries up to 500 times per month.
  * [Glitterly](https://glitterly.app/)  - 以编程方式从基本模板生成动态图像.  Restful API 和 nocode 集成. 免费套餐每月提供 50 张图片和 5 个模板.
  * [GoodData](https://www.gooddata.com/)  - 数据即服务 - 创建交互式且富有洞察力的仪表板. 免费层包含 5 个工作区和 100 MB/工作区.
  * [Hookbin](https://hookbin.com/)  - 创建唯一（公共或私有）端点来收集、解析和检查 HTTP 请求. 检查标头、正文、查询字符串、cookie、上传的文件等.对于测试/检查 webhook 很有用. 类似于 RequestBin 和 Webhook.site.
  * [Hoppscotch](https://hoppscotch.io) - 免费、快速、美观的 API 请求生成器.
  * [Hybiscus](https://hybiscus.dev/)  - 使用简单的声明式 API 构建 pdf 报告. 免费套餐包括每月最多 100 个单页报告，能够自定义颜色托盘和字体.
  * [Invantive Cloud](https://cloud.invantive.com/) — Access over 70 (cloud)platforms such as Exact Online, Twinfield, ActiveCampaign or Visma using Invantive SQL or OData4 (typically Power BI or Power Query). Includes data replication and exchange. Free plan for developers and implementation consultants. Free for specific platforms with limitations in data volumes.
  * [ipaddress.sh](https://ipaddress.sh) — Simple service to get public IP address in different [formats](https://about.ipaddress.sh/).
  * [Iploka](https://iploka.com/) — IP to Geolocation API - Forever free plan for developers with 10k requests per month limit.
  * [IP Geolocation](https://ipgeolocation.io/) — IP Geolocation API - 为每月 30k 请求（1k/天）限制的开发人员提供永久免费计划.
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) — IP Geolocation API from Abstract - Extensive free plan allowing 200,000 requests per month.
  * [IP2Location](https://www.ip2location.com) — Freemium IP geolocation service. LITE database is available for free download. Import the database in server and perform local query to determine city, coordinates and ISP information.
  * [ipapi](https://ipapi.co/)  - Kloudend, Inc 的 IP 地址位置 API - 一个可靠的地理定位 API，建立在 AWS 上，受到财富 500 强的信任.免费套餐每月提供 30k 次查找（1k/天），无需注册. 联系我们获取更高限额的试用计划.
  * [IPinfo](https://ipinfo.io/) — Fast, accurate, and free (up to 50k/month) IP address data API. Offers APIs with details on geolocation, companies, carriers, IP ranges, domains, abuse contacts, and more. All paid APIs can be trialed for free.
  * [IPFast](https://ip-fast.com/) — Find out your IP Address and related detailed information using the free, fastest and simple lookup tool.
  * [IPList](https://www.iplist.cc)  — 查找有关任何 IP 地址的详细信息，例如 Geo IP 信息、Tor 地址、主机名和 ASN 详细信息. 个人和企业用户免费.
  * [BigDataCloud](https://www.bigdatacloud.com/) - 为现代网络提供快速、准确和免费（无限或高达 10K-50K/月）的 API，如 IP 地理定位、反向地理编码、网络洞察、电子邮件和电话验证、客户信息等.
  * [IPTrace](https://iptrace.io) — An embarrassingly simple API that provides reliable and useful IP geolocation data for your business.
  * [JSON IP](https://getjsonip.com)  — 返回请求它的客户端的公共 IP 地址. 免费层无需注册. 可以使用客户端 JS 直接从浏览器请求使用 CORS 数据. 对于监控客户端和服务器 IP 变化的服务很有用. 无限请求.
  * [konghq.com/](https://konghq.com/)  — API 市场和强大的私有和公共 API 工具. 在免费层中，某些功能会受到限制，例如监控、警报和支持.
  * [Kreya](https://kreya.app)  — 用于调用和测试 gRPC API 的免费 gRPC GUI 客户端. 可以通过服务器反射导入 gRPC API.
  * [KSoft.Si](https://api.ksoft.si/) — Free lyrics api chiefly aimed for discord bots.Also provides an extensive library of images and user data
  * [Lightly](https://www.lightly.ai/)  — 使用正确的数据改进您的机器学习模型. 免费使用多达 1&#39;000 个样本的数据集.
  * [MailboxValidator](https://www.mailboxvalidator.com) — Email verification service using real mail server connection to confirm valid email. Free API plan has 300 verifications per month.
  * [microlink.io](https://microlink.io/) – It turns any website into data such as metatags normalization, beauty link previews, scraping capabilities or screenshots as a service. 100 reqs/day every day free.
  * [monkeylearn.com](https://monkeylearn.com/) — 使用机器学习进行文本分析，每月免费 300 次查询.
  * [MockAPI](https://www.mockapi.io/) — MockAPI is a simple tool that lets you easily mock up APIs, generate custom data, and preform operations on it using RESTful interface. MockAPI is meant to be used as a prototyping/testing/learning tool. 1 project/50 resources per project for free.
  * [Mocki](https://mocki.io)  - 一种工具，可让您创建同步到 GitHub 存储库的模拟 GraphQL 和 REST API. 无需注册即可免费创建和使用简单的 REST API.
  * [Mocko.dev](https://mocko.dev/) — Proxy your API, choose which endpoints to mock in the cloud and inspect traffic, for free. Speed up your development and integrations tests.
  * [Mocky](https://designer.mocky.io/)  - 一个简单的 Web 应用程序，用于生成自定义 HTTP 响应以模拟 HTTP 请求. 也可作为 [open source](https://github.com/julien-lafont/Mocky).
  * [reqres.in](https://reqres.in) - A Free hosted REST-API ready to respond to your AJAX requests.
  * [microenv.com](https://microenv.com) — 为开发人员创建假的 REST API，并有可能在 docker 容器中生成代码和应用程​​序.
  * [neptune.ai](https://neptune.ai/)  - 记录、存储、显示、组织、比较和查询所有 MLOps 元数据. 个人免费：1 名成员、100 GB 元数据存储、200 小时监控/月
  * [News API](https://newsapi.org)  — 使用代码在网络上搜索新闻，获取 JSON 结果. 开发人员每月免费获得 3,000 个查询.
  * [OCR.Space](https://ocr.space/)  — 一个 OCR API，它解析图像和 pdf 文件，以 JSON 格式返回文本结果. 每月免费 25,000 个请求.
  * [Duply.co](https://duply.co) — Create dynamic images from API & URL, design template once and reuse it. Free tier offers 70 images/month creation from API & URL and Up to 100 through Form.
  * [OpenAPI3 Designer](https://openapidesigner.com/) — 免费直观地创建 Open API 3 定义.
  * [parsehub.com](https://parsehub.com/) — Extract data from dynamic sites, turn dynamic websites into APIs, 5 projects free.
  * [Pixela](https://pixe.la/) - Free daystream database service. All operations are performed by API. Visualization with heat maps and line graphs is also possible.
  * [Postbacks](https://postbacks.io/)  - 稍后请求 HTTP 回调. 注册时有 8,000 个免费请求.
  * [Postman](https://postman.com) — Simplify workflows and create better APIs – faster – with Postman, a collaboration platform for API development. Use the Postman App for free forever. Postman cloud features are also free forever with certain limits.
  * [PrefectCloud](https://www.prefect.io/cloud/)  — 一个完整的数据流自动化平台. 所有计划都包括每月 20,000 次免费运行. 这足以支持大多数小型企业的 ETL.
  * [ProxyCrawl](https://proxycrawl.com/) — Crawl and scrape websites without the need of proxies, infrastructure or browsers. We solve captchas for you and prevent you being blocked. The first 1000 calls are free of charge.
  * [Public-Apis Github Repo](https://github.com/public-apis/public-apis) — 免费的公共 API 列表.
  * [Supportivekoala](http://supportivekoala.com/) <i>— Allows you to autogenerate images by your input via templates.</i> <b>— 允许您通过模板输入自动生成图像。</b> <i>Free plan allows you to create up to 100 images per week.</i><b>免费计划允许您每周创建多达 100 张图像。</b>
  * [QuickMocker](https://quickmocker.com/) <i>— Manage online fake API endpoints under your own subdomain, forward requests to localhost URL for webhooks development and testing, use RegExp and multiple HTTP methods for URL path, prioritize endpoints, more than 100 shortcodes (dynamic or fake response values) for response templating, import from OpenAPI (Swagger) Specifications in JSON format, proxy requests, restrict endpoint by IP address and authorization header.</i> <b>— 在您自己的子域下管理在线虚假 API 端点，将请求转发到 localhost URL 以进行 webhook 开发和测试，使用 RegExp 和多种 HTTP 方法作为 URL 路径，优先考虑端点，100 多个短代码（动态或虚假响应值）用于响应模板，从 JSON 格式的 OpenAPI (Swagger) 规范导入，代理请求，通过 IP 地址和授权标头限制端点。</b> <i>Free account provides 1 random subdomain, 10 endpoints, 5 RegExp URL paths, 50 shortcodes per endpoint, 100 requests per day, 50 history records in requests log.</i><b>免费帐户提供 1 个随机子域、10 个端点、5 个 RegExp URL 路径、每个端点 50 个短代码、每天 100 个请求、请求日志中的 50 个历史记录。</b>
  * [RequestBin.com](https://requestbin.com)  — 创建一个可以向其发送 HTTP 请求的免费端点. 发送到该端点的任何 HTTP 请求都将与相关的有效负载和标头一起记录，以便您可以观察来自 webhook 和其他服务的请求.
  * [restlet.com](https://restlet.com/products/apispark/) — APISpark 使任何 API、应用程序或数据所有者能够通过直观的浏览器界面在几分钟内成为 API 提供者.
  * [Roboflow](https://roboflow.com) - create and deploy a custom computer vision model with no prior machine learning experience required. Free tier includes up to 1,000 free source images.
  * [ROBOHASH](https://robohash.org/) - Web service to generate unique (cool :) images from any text.
  * [Scraper.AI](https://scraper.ai)  - SaaS 可将任何网站转变为可消耗的 API，供您构建. 每月免费 50 次提取和 10000 次 API 调用.
  * [Scraper's Proxy](https://scrapersproxy.com) — Simple HTTP proxy API made for scraping. Scrape anonymously without having to worry about restrictions, blocks or captchas. First 100 successfully scrape's per month free including javascript rendering (more available if you contact support).
  * [ScrapingAnt](https://scrapingant.com/) — Headless Chrome scraping API and free checked proxies service. Javascript rendering, premium rotating proxies, CAPTCHAs avoiding. Free plans available.
  * [ScraperBox](https://scraperbox.com/)  — 使用真正的 Chrome 浏览器和代理轮换无法检测到 Web 抓取 API. 使用简单的 API 调用来抓取任何网页. 免费计划每月有 1000 个请求.
  * [ScrapingDog](https://scrapingdog.com/) — Scrapingdog handles millions of proxies, browsers and CAPTCHAs to provide you with HTML of any web page in a single API call. It also provides Web Scraper for Chrome & Firefox and a software for instant scraping demand. Free plans available.
  * [scrapinghub.com](https://scrapinghub.com) — Data scraping with visual interface and plugins. Free plan includes unlimited scraping on a shared server.
  * [ScrapingNinja](https://www.scrapingninja.co/) — Handle JS rendering, Chrome Headless, Proxy rotation and CAPTCHAs solving all in one place. The first 1000 are free of charge, no credit card required.
  * [Sheetson](https://sheetson.com) <i>- Instantly turn any Google Sheets into RESTful API.</i> <b>- 立即将任何 Google 表格转换为 RESTful API。</b> <i>Free plan available.</i><b>提供免费计划。</b>
  * [shrtcode API](https://shrtco.de/docs) - 未经授权且无请求限制的免费 URL Shortening API.
  * [SerpApi](https://serpapi.com/) - Real-time search engine scraping API. Returns structured JSON results for Google, Youtube, Bing, Baidu, Walmart and many other engines. Free plan includes 100 successful API calls per month.
  * [Similar Words API](https://word-simi.herokuapp.com/) — An API to find similar words, has vocabulary of about 4Million words.
  * [Sofodata](https://www.sofodata.com/) - Create secure RESTful APIs from CSV files. Upload a CSV file and instantly access the data via its API allowing faster application development. Free plan includes 2 APIs and 2,500 API calls per month. No credit card required.
  * [tamber](https://tamber.com) — Put deep-learning powered recommendations in your app. Free 5k monthly active users.
  * [Time Door](https://timedoor.io) - 时间序列分析 API.
  * [TinyMCE](https://www.tiny.cloud)  - 富文本编辑 API. 核心功能免费无限使用.
  * [Unixtime](https://unixtime.co.za) - 将 Unixtime 转换为 DateTime 的免费 API，反之亦然.
  * [Webhook.site](https://webhook.site) - 使用即时显示请求的便捷工具轻松测试 HTTP webhook.
  * [wit.ai](https://wit.ai/) — NLP for developers.
  * [wolfram.com](http://wolfram.com/language/) — 在云端内置基于知识的算法.
  * [wrapapi.com](https://wrapapi.com/)  — 将任何网站变成参数化 API. 每月 30k API 调用.
  * [ZenRows](https://www.zenrows.com/)  — Web Scraping API 和代理服务器，可绕过任何反机器人解决方案，同时提供 javascript 渲染、旋转代理和地理定位.  1000 个 API 调用的免费层级.
  * [Zenscrape](https://zenscrape.com/web-scraping-api) — Web scraping API with headless browsers, residentials IPs and simple pricing. 1000 free API calls/month, extra free credits for students and non-profits.
  * [ip-api](https://ip-api.com) — IP Geolocation API，免费用于非商业用途，无需 API 密钥，免费计划的同一 IP 地址限制为 45 次/分钟.
  * [WebScraping.AI](https://webscraping.ai) - Simple Web Scraping API with built-in parsing, Chrome rendering and proxies. 2000 free API calls per month.
  * [Zipcodebase](https://zipcodebase.com)  - 免费邮政编码 API，访问全球邮政编码数据.  10000 个免费请求/月.
  * [EVA](http://eva.pingutil.com/) - 免费的电子邮件验证器 API，有助于识别电子邮件是否是一次性的以及是否具有有效的 MX 记录.
  * [happi.dev](https://happi.dev) - Freemium api services collection (Music, Exchange Rate, Key value store, Language Detection, Password Generator, QRCode Generator, Lyrics). 8000 free API calls per month.
  * [huggingface.co](https://huggingface.co) - Build, train and deploy NLP models for Pytorch, TensorFlow, and JAX. Free up to 30k input characters/mo.
  * [vatcheckapi.com](https://vatcheckapi.com)  - 简单且免费的增值税号码验证 API. 每月 500 个免费请求.
  * [numlookupapi.com](https://numlookupapi.com) - 免费电话号码验证 API - 每月 10 万次免费请求.
  * [geojs.io](https://www.geojs.io/) - 高度可用的 REST/JSON/JSONP IP 地理位置查找 API.


## Artifact Repos

 * [Artifactory](https://jfrog.com/start-free/) - An artifact repository that supports numerous package formats like Maven, Docker, Cargo, Helm, PyPI, CocoaPods, and GitLFS. Incudes package scanning tool XRay and CI/CD tool Pipelines (formerly Shippable) with a free tier of 2,000 CI/CD minutes per month.
 * [central.sonatype.org](https://central.sonatype.org) — The default artifact repository for Apache Maven, SBT and other build systems.
 * [cloudrepo.io](https://cloudrepo.io)  - 基于云的私有和公共、Maven 和 PyPi 存储库. 对开源项目免费.
 * [cloudsmith.io](https://cloudsmith.io)  — 适用于 Java/Maven、RedHat、Debian、Python、Ruby、Vagrant 等的简单、安全和集中的存储库服务. 免费层 + 免费用于开源.
 * [jitpack.io](https://jitpack.io/) — Maven repository for JVM and Android projects on GitHub, free for public projects.
 * [packagecloud.io](https://packagecloud.io/users/new?plan=free_usage_plan) — Easy to use repository hosting for: Maven, RPM, DEB, PyPi, NPM, and RubyGem packages (has free tier).
 * [repsy.io](https://repsy.io) — 1 GB 免费的私有/公共 Maven 存储库.


## Tools for Teams and Collaboration

  * [3Cols](https://3cols.com/) - 一个免费的基于云的代码片段管理器，用于个人和协作代码.
  * [Bitwarden](https://bitwarden.com) — 个人、团队和企业组织存储、共享和同步敏感数据的最简单、最安全的方式.
  * [Braid](https://www.braidchat.com/)  — 专为团队设计的聊天应用程序. 对公共访问组、无限用户、历史记录和集成免费. 它还提供自托管的开源版本.
  * [cally.com](https://cally.com/) — Find the perfect time and date for a meeting. Simple to use, works great for small and large groups.
  * [Calendly](https://calendly.com) — Calendly is the tool for connecting and scheduling meetings. Free plan provides 1 Calendar connection per user and Unlimited meetings. Desktop and Mobile apps also provided.
  * [Discord](https://discord.com/) — Chat with public/private rooms. Markdown text, voice, video, and screen sharing capabilities. Free for unlimited users.
  * [Telegram](https://telegram.org/) — Telegram is for everyone who wants fast and reliable messaging and calls. Business users and small teams may like the large groups, usernames, desktop apps and powerful file sharing options.
  * [Duckly](https://duckly.com/)  — 与您的团队实时交谈和协作. 与任何 IDE 配对编程、终端共享、语音、视频和屏幕共享. 小团队免费.
  * [evernote.com](https://evernote.com/) — Tool for organizing information. Share your notes and work together with others
  * [Fibery](https://fibery.io/) — Connected workspace platform. Free for single user, up to 2 GB disk space.
  * [Filestash](https://www.filestash.app) — 类似于 Dropbox 的文件管理器，可连接到一系列协议和平台：S3、FTP、SFTP、Minio、Git、WebDAV、Backblaze、LDAP 等.
  * [flock.com](https://flock.com) — A faster way for your team to communicate. Free Unlimited Messages, Channels, Users, Apps & Integrations
  * [Flowdash](https://flowdash.com/) — Automate business workflows. Free tier for up to 3 users, 1000 tasks, and 3 workflows.
  * [flowdock.com](https://www.flowdock.com/) — 聊天和收件箱，最多 5 人的团队免费
  * [GitDailies](https://gitdailies.com)  - 您团队在 GitHub 上的提交和拉取请求活动的每日报告. 包括推送可视化工具、对等识别系统、自定义警报生成器. 免费层有无限用户、3 个存储库、3 个警报配置.
  * [gitter.im](https://gitter.im/) — Chat, for GitHub. Unlimited public and private rooms, free for teams up to 25
  * [hangouts.google.com](https://hangouts.google.com/) — One place for all your conversations, for free, need a Google account
  * [HeySpace](https://hey.space)  - 带有聊天、日历、时间线和视频通话的任务管理工具. 最多 5 位用户免费.
  * [helplightning.com](https://www.helplightning.com/)  — 通过增强现实帮助视频. 免费，无需分析、加密、支持
  * [ideascale.com](https://ideascale.com/) — 允许客户提交想法和投票，1 个社区的 25 名成员免费
  * [Igloo](https://www.igloosoftware.com/) — 用于共享文档、博客和日历等的内部门户.最多可供 10 位用户免费使用.
  * [Keybase](https://keybase.io/) — Keybase is a cool FOSS alternative to Slack, it keeps everyone's chats and files safe, from families to communities to companies.
  * [Google Meet](https://meet.google.com/) — Use Google Meet for your business's online video meeting needs. Meet provides secure, easy-to-join online meetings.
  * [/meet for Slack](https://meetslack.com)  - 在任何频道、组或 DM 中使用 /meet 直接从 Slack 启动 Google 会议. 免费，没有任何限制.
  * [MarkUp](https://www.markup.io/) — MarkUp 让您可以直接在您的网站、PDF 和图像上收集反馈.
  * [meet.jit.si](https://meet.jit.si/) — 一键视频对话，屏幕共享，免费
  * [Microsoft Teams](https://products.office.com/microsoft-teams/free) — Microsoft Teams is a chat-based digital hub that brings conversations, content, and apps together in one place all from a single experience. Free for up to 500k users.
  * [Miro](https://miro.com/)  - 适用于分布式团队的可扩展、安全、跨设备和企业就绪的团队协作白板. 有免费增值计划.
  * [nootiz](https://www.nootiz.com/) - 在任何网站上收集和管理视觉反馈的首选工具
  * [Notion](https://www.notion.so/) - Notion is a note-taking and collaboration application with markdown support that also integrates tasks, wikis, and databases. The company describes the app as an all-in-one workspace for note-taking, project management and task management. In addition to cross-platform apps, it can be accessed via most web browsers.
  * [Nuclino](https://www.nuclino.com) - A lightweight and collaborative wiki for all your team's knowledge, docs, and notes. Free plan with all essential features, up to 50 items, 5GB total storage.
  * [PageShare.dev](https://www.pageshare.dev)  - 将视觉评论功能添加到 GitHub 拉取请求中，无需部署网站. 每个月最多免费提供 10 页，总共 100MB 的存储空间.
  * [Pendulums](https://pendulums.io/) - Pendulums is a free time tracking tool which helps you to manage your time in a better manner with an easy to use interface and useful statistics.
  * [Raindrop.io](https://raindrop.io)  - 适用于 macOS、Windows、Android、iOS 和 Web 的私密且安全的书签应用程序. 免费无限书签和协作.
  * [element.io](https://element.io/)  — 一个基于 Matrix 的去中心化开源通信工具. 群聊、直接消息、加密文件传输、语音和视频聊天以及与其他服务的轻松集成.
  * [Rocket.Chat](https://rocket.chat/) - 团队共享收件箱，安全、无限制和开源.
  * [seafile.com](https://www.seafile.com/) — Private or cloud storage, file sharing, sync, discussions. Private version is full. Cloud version has just 1 GB
  * [Slab](https://slab.com/) <i>— A modern knowledge management service for teams.</i> <b>— 面向团队的现代知识管理服务。</b> <i>Free for up to 10 users.</i><b>最多 10 个用户免费。</b>
  * [slack.com](https://slack.com/) — Free for unlimited users with some feature limitations
  * [Spectrum](https://spectrum.chat/) - Create public or private communities for free.
  * [StatusPile](https://www.statuspile.com/)  - 状态页面的状态页面. 跟踪上游提供商的状态页面.
  * [talky.io](https://talky.io/) — Free group video chat. Anonymous. Peer‑to‑peer. No plugins, signup, or payment required
  * [Tefter](https://tefter.io) - Bookmarking app with a powerful Slack integration. Free for open-source teams.
  * [TeleType](https://teletype.oorja.io/)  — 共享终端、语音、代码、白板等. 无需登录，面向开发人员的端到端加密协作.
  * [TimeCamp](https://www.timecamp.com/)  - 无限用户的免费时间跟踪软件. 与 Jira、Trello、Asana 等 PM 工具轻松集成.
  * [Tree Schema](https://treeschema.com/) — Data catalog and metadata management with APIs to manage data lineage as code. Free for teams of up to 5 users.
  * [twist.com](https://twist.com) — An asynchronous-friendly team communication app where conversations stay organized and on-topic. Free and Unlimited plans available. Discounts provided for eligible teams.
  * [BookmarkOS.com](https://bookmarkos.com) - Free all-on-one bookmark manager, tab manager, and task manager in a customizable online desktop with folder collaboration.
  * [typetalk.com](https://www.typetalk.com/) — 通过网络或手机上的即时消息与您的团队分享和讨论想法
  * [Tugboat](https://tugboat.qa) - Preview every pull request, automated and on-demand. Free for all, complimentary Nano tier for non-profits.
  * [whereby.com](https://whereby.com/) — 一键视频对话，免费（以前称为appear.in）
  * [vadoo.tv](https://vadoo.tv/) — Video hosting and marketing made simple. Upload videos with a single click. Record, manage, share & more. Free tier provides upto 10 videos, 1 GB storage, 10 GB bandwidth/month
  * [vspace](https://vvv.space/) — Free links manager with private/public spaces, includes slack and google docs integration and chrome plugin.
  * [userforge.com](https://userforge.com/)  - 相互关联的在线角色、用户故事和上下文映射. 帮助保持设计和开发同步，最多可免费供 3 个角色和 2 个协作者使用.
  * [wistia.com](https://wistia.com/) — 带有观众分析、高清视频交付和营销工具的视频托管，以帮助了解您的访问者、25 个视频和 Wistia 品牌播放器
  * [wormhol.org](https://www.wormhol.org/) — Straightforward file sharing service. Share unlimited files up to 5GB to as many peers as you want.
  * [zoom.us](https://zoom.us/) — Secure Video and Web conferencing, add-ons available. Free limited to 40 minutes
  * [shtab.app](https://shtab.app/) - 项目管理服务，通过基于 AI 的跟踪器使办公室协作和远程透明化.
  * [zdoo.co](https://www.zdoo.co) — With CRM, OA, and Project management suites, zdoo is so powerful for team collaboration. Free cloud version with limited users and space offered, one-month free trial for premium versions.
  * [Zulip](https://zulip.com/)  — 具有独特的类似电子邮件的线程模型的实时聊天. 免费计划包括 10,000 条搜索历史消息和高达 5 GB 的文件存储空间. 它还提供自托管的开源版本.
  * [Automate.io](https://automate.io) - Simple and complex automation workflow tool with over 200+ app integrations. 300 monthly actions and 5 bots are free
  * [robocorp.com](https://robocorp.com)  - 用于支持自动化操作的开源堆栈. 免费试用云功能并实施简单的自动化. 机器人工作 240 分钟/月，10 次助手运行，100 MB 存储空间.
  * [Fleep.io](https://fleep.io/) — Fleep an alternative to Slack. It has a free plan for small teams with full message history, unlimited 1:1 conversations, 1 group conversation and 1 GB file storage.
  * [Chanty.com](https://chanty.com/) — Chanty is another alternative to Slack. It has a free forever plan for small teams (up to 10) with unlimited public and private conversations, searchable history, unlimited 1:1 audio calls, unlimited voice messages, 10 integrations and 20 GB storage per team.


## CMS

  * [acquia.com](https://www.acquia.com/) — Hosting for Drupal sites. Free tier for developers. Free development tools (such as Acquia Dev Desktop) also available
  * [Contentful](https://www.contentful.com/) — Headless CMS. Content management and delivery APIs in the cloud. Comes with one free Community space that includes 5 users, 25K records, 48 Content Types, 2 locales.
  * [Cosmic](https://www.cosmicjs.com/)  — 无头 CMS 和 API 工具包. 开发人员的免费个人计划.
  * [Crystallize](https://crystallize.com)  — 具有电子商务支持的无头 PIM. 内置 GraphQL API. 免费版包括无限用户、1000 个目录项、5 GB/月带宽和 25k/月 API 调用.
  * [DatoCMS](https://www.datocms.com/)  - 为小型项目提供免费套餐.  DatoCMS 是一个基于 GraphQL 的 CMS. 在较低层，您每月有 10 万次通话.
  * [Directus](https://directus.io) — Headless CMS. A completely free and open-source platform for managing assets and database content on-prem or in the Cloud. No limitations or paywalls.
  * [Forestry.io/](https://forestry.io/)  — 无头 CMS. 为您的编辑提供 Git 的强大功能. 轻松创建和编辑基于 Markdown 的内容. 附带三个免费网站，其中包括 3 个编辑器、即时预览. 与托管在 Netlify/GitHubpages/ 其他地方的博客集成
  * [FrontAid](https://frontaid.io/) — Headless CMS that stores JSON content directly in your own Git repository. No restrictions.
  * [kontent.ai](https://www.kontent.ai)  - 一个内容即服务平台，可为您提供所有无头 CMS 优势，同时为营销人员提供支持. 开发人员计划为 2 个用户提供无限项目，每个用户有 2 个环境、500 个内容项、2 种语言以及交付和管理 API，以及自定义元素支持. 更大的计划可满足您的需求.
  * [Prismic](https://www.prismic.io/)  — 无头 CMS. 具有完全托管和可扩展 API 的内容管理界面. 社区计划为 1 位用户提供无限的 API 调用、文档、自定义类型、资产和语言环境. 您下一个项目所需的一切. 更大的免费计划可用于开放内容/开源项目.
  * [Sanity.io](https://www.sanity.io/)  - 带有开源编辑环境和实时托管数据存储的结构化内容平台. 无限的项目. 无限的管理员用户、3 个非管理员用户、2 个数据集、500K API CDN 请求、10GB 带宽、每个项目免费包含 5GB 资产.
  * [sensenet](https://sensenet.com)  - API 优先的无头 CMS，为各种规模的企业提供企业级解决方案. 开发人员计划提供 3 个用户、500 个内容项、3 个内置角色、25+5 种内容类型、完全可访问的 REST API、文档预览生成和 Office Online 编辑.
  * [GraphCMS](https://graphcms.com/)  - 为小型项目提供免费套餐.  GraphQL 第一个 API. 从遗留解决方案转移到 GraphQL 原生 Headless CMS - 并首先提供全渠道内容 API.
  * [Squidex](https://squidex.io/) - Offers free tier for small projects. API / GraphQL first. Open source, and based on event sourcing (versing every changes automatically).


## Code Quality

  * [SoftaCheck](https://www.softacheck.com/) — An online tool that performs static analysis for C/C++ code using open source tools such as cppcheck and clang-tidy and automatically generates code documentation for users using doxygen. This tool is free for use.
  * [beanstalkapp.com](https://beanstalkapp.com/) — 编写、审查和部署代码的完整工作流程）、1 个用户的免费帐户和 1 个具有 100 MB 存储空间的存储库
  * [browserling.com](https://www.browserling.com/) — Live interactive cross-browser testing, free only 3 minutes sessions with MS IE 9 under Vista at 1024 x 768 resolution
  * [codacy.com](https://www.codacy.com/) — PHP、Python、Ruby、Java、JavaScript、Scala、CSS 和 CoffeeScript 的自动代码审查，对无限的公共和私有存储库免费
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev) - Automated Infrastructure as Code review tool for DevOps integrates with GitHub, Bitbucket and GitLab (even self-hosted). In addition to standard languages, it analyzes also Ansible, Terraform, CloudFormation, Kubernetes, and more. (open-source free)
  * [CodeBeat](https://codebeat.co)  — 可用于多种语言的自动代码审查平台. 与 Slack 和电子邮件集成的公共存储库永远免费.
  * [codeclimate.com](https://codeclimate.com/) — Automated code review, free for Open Source and unlimited organisation-owned private repos (up to 4 collaborators). Also free for students and institutions.
  * [codecov.io](https://codecov.io/) — 代码覆盖工具 (SaaS)，对开源免费和 1 个免费私人仓库
  * [CodeFactor](https://www.codefactor.io) — Automated Code Review for Git. Free version includes unlimited users, unlimited public repositories and 1 private repo.
  * [codescene.io](https://codescene.io/)  - CodeScene 根据开发人员使用代码的方式确定技术债务的优先级，并可视化团队耦合和系统掌握等组织因素. 开源免费.
  * [coveralls.io](https://coveralls.io/) — Display test coverage reports, free for Open Source
  * [dareboost](https://dareboost.com) - 5 free analysis report for web performance, accessibility, security each month
  * [deepcode.ai](https://www.deepcode.ai) <i>— DeepCode finds bugs, security vulnerabilities, performance and API issues based on AI.</i> <b>— DeepCode 基于 AI 发现错误、安全漏洞、性能和 API 问题。</b> <i>DeepCode&#39;s speed of analysis allow us to analyse your code in real time and deliver results when you hit the save button in your IDE.</i> <b>DeepCode 的分析速度使我们能够实时分析您的代码并在您点击 IDE 中的保存按钮时提供结果。</b> <i>Supported languages are Java, C/C++, JavaScript, Python, and TypeScript.</i><b>支持的语言有 Java、C/C++、JavaScript、Python 和 TypeScript。</b> <i>Integrations with GitHub, BitBucket and GitLab.</i><b>与 GitHub、BitBucket 和 GitLab 集成。</b> <i>Free for open source and private repos, free up to 30 developers.</i><b>对开源和私人存储库免费，最多可释放 30 名开发人员。</b>
  * [deepscan.io](https://deepscan.io) — Advanced static analysis for automatically finding runtime errors in JavaScript code, free for Open Source
  * [DeepSource](https://deepsource.io/)  - DeepSource 持续分析源代码更改，发现并修复按安全、性能、反模式、错误风险、文档和样式分类的问题. 与 GitHub、GitLab 和 Bitbucket 的原生集成.
  * [eversql.com](https://www.eversql.com/) — EverSQL - The #1 platform for database optimization. Gain critical insights into your database and SQL queries, auto-magically.
  * [gerrithub.io](https://review.gerrithub.io/) — 免费对 GitHub 存储库进行 Gerrit 代码审查
  * [gocover.io](https://gocover.io/) — Code coverage for any [Go](https://golang.org/) 包裹
  * [goreportcard.com](https://goreportcard.com/) — Code Quality for Go projects, free for Open Source
  * [gtmetrix.com](https://gtmetrix.com/) — Reports and thorough recommendations to optimize websites
  * [holistic.dev](https://holistic.dev/) - The #1 static code analyzer for Postgresql optimization. Performance, security, and architect database issues automatic detection service
  * [houndci.com](https://houndci.com/) — 对 GitHub 提交关于代码质量的评论，对开源免费
  * [Imgbot](https://github.com/marketplace/imgbot) — Imgbot is a friendly robot that optimizes your images and saves you time. Optimized images mean smaller file sizes without sacrificing quality. It's free for open source.
  * [Kritika](https://kritika.io/)  — Perl 的静态代码分析与 GitHub 的集成. 免费用于无限的公共存储库.
  * [resmush.it](https://resmush.it) — reSmush.it is a FREE API that provides image optimization. reSmush.it has been implemented on the most common CMS such as Wordpress, Drupal or Magento. reSmush.it is the most used image optimization API with more than 7 billions images already treated, and is still Free of charge.
  * [insight.sensiolabs.com](https://insight.sensiolabs.com/) — Code Quality for PHP/Symfony projects, free for Open Source
  * [lgtm.com](https://lgtm.com) — Continuous security analysis for Java, Python, JavaScript, TypeScript, C#, C and C++, free for Open Source
  * [Moderne.io](https://app.moderne.io)  — 自动源代码重构.  Moderne 提供框架迁移、带有补救措施的代码分析以及无与伦比的大规模代码转换，因此开发人员可以将时间花在构建新事物上，而不是维护旧事物. 开源免费.
  * [reviewable.io](https://reviewable.io/) — GitHub 存储库的代码审查，公共或个人存储库免费
  * [parsers.dev](https://parsers.dev/) - 抽象语法树解析器和中间表示编译器即服务
  * [scan.coverity.com](https://scan.coverity.com/) — Static code analysis for Java, C/C++, C# and JavaScript, free for Open Source
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 持续检测平台，开源免费
  * [shields.io](https://shields.io) — Quality metadata badges for open source projects
  * [Sider](https://sider.review)  — 多种语言的代码审查平台. 支持与 GitHub 集成. 对拥有无限用户的公共存储库免费.
  * [sonarcloud.io](https://sonarcloud.io) — Automated source code analysis for Java, JavaScript, C/C++, C#, VB.NET, PHP, Objective-C, Swift, Python, Groovy and even more languages, free for Open Source
  * [SourceLevel](https://sourcelevel.io/) — Automated Code Review and Team Analytics. Free for Open Source and organizations up to 5 collaborators.
  * [Typo CI](https://github.com/marketplace/typo-ci) — Typo CI 审查您的 Pull Requests 和提交的拼写错误，对开源免费.
  * [Viezly](https://viezly.com/) - Enhanced code review tool for easier code reading and navigation. Free for Open Source and free for personal usage.
  * [webceo.com](https://www.webceo.com/) — SEO tools but with also code verifications and different type of advices
  * [zoompf.com](https://zoompf.com/) — 修复您网站的性能，详细分析


## Code Search and Browsing

  * [codota.com](https://www.codota.com/)  — Codota 通过提供从世界上所有代码中学到的见解，帮助开发人员更快地创建更好的软件. 插件可用.
  * [libraries.io](https://libraries.io/) — Search and dependency update notifications for 32 different package managers, free for open source
  * [Namae](https://namae.dev/) - 搜索各种网站，如 github、gitlab、heroku、netlify 等，以获取项目名称的可用性.
  * [searchcode.com](https://searchcode.com/) — Comprehensive text-based code search, free for Open Source
  * [sourcegraph.com](https://about.sourcegraph.com/) — Java、Go、Python、Node.js 等，代码搜索/交叉引用，开源免费
  * [tickgit.com](https://www.tickgit.com/) — Surfaces `TODO` comments (and other markers) to identify areas of code worth returning to for improvement.
  * [CodeKeep](https://codekeep.io) - Google Keep for Code Snippets. Organize,Discover and share code snippets, featuring a powerful code screenshot tool with preset templates and linking feature.


## CI and CD

  * [AccessLint](https://github.com/marketplace/accesslint)  — AccessLint 将自动化的 Web 可访问性测试引入您的开发工作流程. 它对于开源和教育目的是免费的.
  * [appcircle.io](https://appcircle.io)  — 适用于 iOS 和 Android 的自动化移动 CI/CD/CT，带有在线设备模拟器.  20 分钟构建超时（开源为 60 分钟），单并发免费.
  * [appveyor.com](https://www.appveyor.com/) — CD service for Windows, free for Open Source
  * [bitrise.io](https://www.bitrise.io/)  — 适用于原生或混合移动应用程序的 CI/CD. 每月 200 次免费构建 10 分钟构建时间和两名团队成员.  OSS 项目获得 45 分钟的构建时间、+1 并发和无限的团队规模.
  * [buddy.works](https://buddy.works/) — A CI/CD with 5 free projects and 1 concurrent runs (120 executions/month)
  * [buddybuild.com](https://www.buddybuild.com/) — 在一个无缝的迭代系统中为您的 iOS 和 Android 应用程序构建、部署和收集反馈
  * [circleci.com](https://circleci.com/) — Free for one concurrent build
  * [cirrus-ci.org](https://cirrus-ci.org) - Free for public GitHub repositories
  * [codefresh.io](https://codefresh.io) — 终身免费计划：1 个构建、1 个环境、共享服务器、无限制的公共存储库
  * [codemagic.io](https://codemagic.io/) - Free 500 build minutes/month
  * [codeship.com](https://codeship.com/) — 100 private builds/month, 5 private projects, unlimited for Open Source
  * [Continuous PHP](https://continuousphp.com/) — continuousphp is the first and only PHP-centric Platform to build, package, test and deploy applications in the same workflow. Free for Community Projects i.e. OSS/Public/Educational projects.
  * [deployhq.com](https://www.deployhq.com/) — 1 project with 10 daily deployments (30 build minutes/month)
  * [drone](https://cloud.drone.io/) - Drone Cloud enables developers to run Continuous Delivery pipelines across multiple architectures - including x86 and Arm (both 32 bit and 64 bit) - all in one place
  * [LayerCI](https://layerci.com)  — 全栈项目的 CI.  1 个具有 5GB 内存和 3 个 CPU 的完整堆栈预览环境.
  * [ligurio/awesome-ci](https://github.com/ligurio/awesome-ci) — 持续集成服务的比较
  * [Octopus Deploy](https://octopus.com)  - 自动化部署和发布管理.  &lt;= 10 个部署目标免费.
  * [scalr.com](https://scalr.com/) - Remote state & operations backend for Terraform with full CLI support, integration with OPA and a hierarchical configuration model. Free up to 5 users.
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
  * [checklyhq.com](https://checklyhq.com) - Checkly is the API & E2E monitoring platform for the modern stack: programmable, flexible and loving JavaScript. Generous free tier for devs.
  * [crossbrowsertesting.com](https://crossbrowsertesting.com) - 云中的手动、可视化和 Selenium 浏览器测试 - [free for Open Source](https://crossbrowsertesting.com/open-source)
  * [cypress.io](https://www.cypress.io/)  - 对在浏览器中运行的任何东西进行快速、简单和可靠的测试.  Cypress Test Runner 始终是免费和开源的，没有任何限制和限制.  Cypress Dashboard 对最多 5 个用户的开源项目是免费的.
  * [everystep-automation.com](https://www.everystep-automation.com/) — 记录和回放在 Web 浏览器中进行的所有步骤并创建脚本，......免费，选项更少
  * [Gremlin](https://www.gremlin.com/gremlin-free-software) — Gremlin's Chaos Engineering tools allow you to safely, securely, and simply inject failure into your systems to find weaknesses before they cause customer-facing issues. Gremlin Free provides access to Shutdown and CPU attacks on up to 5 hosts or containers.
  * [gridlastic.com](https://www.gridlastic.com/) — Selenium Grid 测试，免费计划多达 4 个同时的 selenium 节点/10 个网格启动/4,000 分钟测试/月
  * [loadmill.com](https://www.loadmill.com/)  - 通过分析网络流量自动创建 API 和负载测试. 每月免费模拟多达 50 个并发用户长达 60 分钟.
  * [percy.io](https://percy.io) - Add visual testing to any web app, static site, style guide, or component library.  Unlimited team members, Demo app and unlimited projects, 5,000 snapshots / month.
  * [reflect.run](https://reflect.run) - Codeless automated tests for web apps. Tests can be scheduled in-app or executed from a CI/CD tool. Each test run includes a full video recording along with console and network logs. The free tier includes an unlimited number of saved tests, with 25 test runs per month and up to 3 users.
  * [saucelabs.com](https://saucelabs.com/) — 跨浏览器测试、Selenium 测试和移动测试， [free for Open Source](https://saucelabs.com/open-source)
  * [snippets.uilicious.com](https://snippets.uilicious.com)  - 类似于 CodePen，但用于跨浏览器测试.  UI-licious 允许编写用户故事之类的测试，并提供免费平台 - UI-licious Snippets - 允许您在 Chrome 上免费运行无限数量的测试，无需注册，每次测试运行最多 3 分钟. 发现错误？ 您可以简单地将唯一的 url 复制到您的测试中，以准确地向您的开发人员展示如何重现错误.
  * [testingbot.com](https://testingbot.com/) — Selenium 浏览器和设备测试， [free for Open Source](https://testingbot.com/open-source)
  * [Testspace.com](https://testspace.com/) - A Dashboard for publishing automated test results and a Framework for implementing manual tests as code using GitHub. The service is [free for Open Source](https://github.com/marketplace/testspace-com) accounts for 450 results per month.
  * [tesults.com](https://www.tesults.com)  — 测试结果报告和测试用例管理. 与流行的测试框架集成. 开源软件开发人员、个人、教育工作者和小团队入门可以请求基本免费项目之外的折扣和免费产品.
  * [websitepulse.com](https://www.websitepulse.com/tools/) — Various free network and server tools.
  * [qase.io](https://qase.io)  - 开发和质量保证团队的测试管理系统. 管理测试用例、编写测试运行、执行测试运行、跟踪缺陷和衡量影响. 免费层包括所有核心功能，500Mb 可用于附件和最多 3 个用户.
  * [knapsackpro.com](https://knapsackpro.com)  - 在任何 CI 提供商上使用最佳测试套件并行化加速您的测试. 在并行 CI 节点上拆分 Ruby、JavaScript 测试以节省时间. 长达 10 分钟测试文件的免费计划和开源项目的免费无限计划.
  * [webhook.site](https://webhook.site)  - 使用自定义 URL 验证 webhook、出站 HTTP 请求或电子邮件. 临时 URL 和电子邮件地址始终免费.
  * [Vaadin](https://vaadin.com)  — 使用 Java 或 TypeScript 构建可扩展的 UI，并使用集成的工具、组件和设计系统来更快地迭代、更好地设计并简化开发过程. 无限项目，5 年免费维护.
  * [Foresight](https://thundra.io/foresight) — Thundra Foresight 是一种工具，用于立即调试和排除测试故障，并优化 CI 管道中的构建持续时间和性能.


## Security and PKI

  * [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — Uncovers compromised systems in your network
  * [atomist.com](https://atomist.com/) — A quicker and more convenient way to automate a variety of development tasks. Now in beta.
  * [auth0.com](https://auth0.com/) — Hosted free for development SSO. Up to 2 social identity providers for closed-source projects.
  * [Authgear](https://www.authgear.com)  - 在几分钟内为您的应用程序带来无密码、OTP、2FA、SSO. 包括所有前端. 释放多达 5000 个 MAU.
  * [Authress](https://authress.io/)  — 身份验证登录和访问控制，任何项目的无限身份提供者. 脸书、谷歌、推特等. 前 1000 个 API 调用是免费的.
  * [Authy](https://authy.com)  - 多台设备上的双因素身份验证 (2FA)，带有备份.  Google Authenticator 的直接替代品. 免费进行多达 100 次成功的身份验证.
  * [Bridgecrew](https://bridgecrew.io/) — 由开源工具提供支持的基础设施即代码 (IaC) 安全性 — [Checkov](https://github.com/bridgecrewio/checkov). The core Bridgecrew platform is free for up to 50 IaC resources.
  * [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services (AWS) 安全性和合规性审计和监控
  * [Cmd](https://cmd.com/) — 安全平台在您的云或数据中心中的每个 Linux 实例上提供实时访问控制和动态策略实施
  * [CodeNotary.io](https://www.codenotary.io/) — Open Source platform with indelible proof to notarize code, files, directories or container
  * [crypteron.com](https://www.crypteron.com/) — 云优先、对开发人员友好的安全平台可防止 .NET 和 Java 应用程序中的数据泄露
  * [Datree](https://www.datree.io/) — Open Source CLI tool to prevent Kubernetes misconfigurations by ensuring that manifests and Helm charts follow best practices as well as your organization’s policies
  * [Dependabot](https://dependabot.com/) Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven 和 Gradle）、.NET、Go、Elm、Docker、Terraform、Git 子模块和 GitHub Actions 的自动依赖项更新.
  * [DJ Checkup](https://djcheckup.com) — Scan your Django site for security flaws with this free, automated, checkup tool. Forked from the Pony Checkup site.
  * [Doppler](https://doppler.com/) — Universal Secrets Manager for application secrets and config, with support for syncing to various cloud providers. Free for unlimited users with basic access controls.
  * [duo.com](https://duo.com/)  — 网站或应用程序的双因素身份验证 (2FA).  10 个用户免费，所有身份验证方法，无限制，集成，硬件令牌.
  * [GitGuardian](https://www.gitguardian.com) — Keep secrets out of your source code with automated secrets detection and remediation. Scan your git repos for 350+ types of secrets and sensitive files – Free for individuals and teams of 25 developers or less.
  * [globalsign.com](https://www.globalsign.com/en/ssl/ssl-open-source/) — Free SSL certificates for Open Source
  * [Have I been pwned?](https://haveibeenpwned.com) — REST API for fetching the information on the breaches.
  * [hostedscan.com](https://hostedscan.com)  — 针对 Web 应用程序、服务器和网络的在线漏洞扫描程序. 每月 10 次免费扫描.
  * [Internet.nl](https://internet.nl) — 测试现代互联网标准，如 IPv6、DNSSEC、HTTPS、DMARC、STARTTLS 和 DANE
  * [Jumpcloud](https://jumpcloud.com/)  — 提供类似于 Azure AD 的目录即服务、用户管理、单点登录和 RADIUS 身份验证. 最多 10 个用户免费.
  * [keychest.net](https://keychest.net) - SSL 到期管理和证书购买与集成 CT 数据库
  * [letsencrypt.org](https://letsencrypt.org/) — Free SSL Certificate Authority with certs trusted by all major browsers
  * [LoginRadius](https://www.loginradius.com/)  — 免费的托管用户身份验证服务. 电子邮件注册和 3 个社交服务提供商.
  * [logintc.com](https://www.logintc.com/) — Two-factor authentication (2FA) by push notifications, free for 10 users, VPN, Websites and SSH
  * [meterian.io](https://www.meterian.io/)  - 监控 Java、Javascript、.NET、Scala、Ruby 和 NodeJS 项目的依赖项中的安全漏洞. 一个私人项目免费，开源项目无限.
  * [MojoAuth](https://mojoauth.com/) - MojoAuth 可以在几分钟内轻松地在您的 Web、移动设备或任何应用程序上实施无密码身份验证.
  * [Mozilla Observatory](https://observatory.mozilla.org/) — 查找并修复您网站中的安全漏洞.
  * [Okta](https://developer.okta.com/)  — 用户管理、认证和授权. 每月最多 1000 名活跃用户免费.
  * [onelogin.com](https://www.onelogin.com/) — 身份即服务 (IDaaS)、单点登录身份提供商、云 SSO IdP、3 个公司应用程序和 5 个个人应用程序、无限用户
  * [Operous](https://operous.dev/) — Cloud instance testing tool with a comprehensive and automated set of test-suites of best practices, performance, and security. Free tier offers 100 testing minutes, 10 Test Suites, and up to 5 instances to 1 user.
  * [opswat.com](https://www.opswat.com/) — 计算机、设备、应用程序、配置等的安全监控... 免费 25 位用户和 30 天历史用户.
  * [pyup.io](https://pyup.io)  — 监控 Python 依赖项是否存在安全漏洞并自动更新它们. 一个私人项目免费，开源项目无限.
  * [qualys.com](https://www.qualys.com/community-edition) — Find web app vulnerabilities, audit for OWASP Risks
  * [reCAPTCHAMe](https://recaptchame.com/)  — 免费的 reCAPTCHA 和 hCAPTCHA 后端服务. 无需服务器端编码. 适用于静态网站.
  * [report-uri.io](https://report-uri.io/) — CSP and HPKP violation reporting
  * [ringcaptcha.com](https://ringcaptcha.com/) — 使用电话号码作为 id 的工具，免费提供
  * [sawolabs.com](https://sawolabs.com/) - Simplify login and improve user experience by integrating passwordless authentication in your app. 5000 free authentications per month.
  * [snyk.io](https://snyk.io) — Can find and fix known security vulnerabilities in your open source dependencies. Unlimited tests and remediation for open source projects. Limited to 200 tests/month for your private projects.
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) — Very deep analysis of the configuration of any SSL web server
  * [StackHawk](https://www.stackhawk.com/) Automate application scanning throughout your pipeline to find and fix security bugs before they hit production. Unlimited scans and environments for a single app.
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) - 免费的网站安全检查和恶意软件扫描程序
  * [Protectumus](https://protectumus.com) - Free website security check, site antivirus and server firewall (WAF) for PHP. Email notifications for registered users in free tier.
  * [TestTLS.com](https://testtls.com) - 为安全的服务器配置、证书、链等测试 SSL/TLS 服务.不限于 HTTPS.
  * [threatconnect.com](https://threatconnect.com) — Threat intelligence: It is designed for individual researchers, analysts and organizations who are starting to learn about cyber threat intelligence. Free up to 3 Users
  * [tinfoilsecurity.com](https://www.tinfoilsecurity.com/) — Automated vulnerability scanning. Free plan allows weekly XSS scans
  * [Ubiq Security](https://ubiqsecurity.com/) — Encrypt and decrypt data with 3 lines of code and automatic key management. Free for 1 application and up to 1,000,000 encryptions per month.
  * [Virgil Security](https://virgilsecurity.com/) — Tools and services for implementing end-to-end encryption, database protection, IoT security and more in your digital solution. Free for applications with up to 250 users.
  * [Virushee](https://virushee.com/)  — 由混合启发式和人工智能辅助引擎提供支持的面向隐私的文件/数据扫描. 可以使用内部动态沙盒分析. 每个文件上传限制为 50MB
  * [Warrant](https://warrant.dev/) — Hosted enterprise-grade authorization and access control service for your apps. Free tier includes 5,000 API requests per month.
  * [Escape GraphQL Quickscan](https://escape.tech/quickscan)  - 一键安全扫描您的 GraphQL 端点. 免费，无需登录.


## Management System

  * [bitnami.com](https://bitnami.com/)  — 在 IaaS 上部署准备好的应用程序. 免费管理 1 个 AWS 微实例
  * [Esper](https://esper.io)  — 适用于具有 DevOps 的 Android 设备的 MDM 和 MAM.  100 台设备免费，1 个用户许可证和 25 MB 应用程序存储.
  * [jamf.com](https://www.jamf.com/) —  Device management for iPads, iPhones and Macs, 3 devices free
  * [Miradore](https://miradore.com) — Device Management service. Stay up-to-date with your device fleet and secure an unlimited number of devices for free. Free plan offers basic features.
  * [moss.sh](https://moss.sh) - Help developers deploy and manage their web apps and servers. Free up to 25 git deployments per month
  * [runcloud.io](https://runcloud.io/) - Server management focusing mainly on PHP projects. Free for up to 1 server.
  * [ploi.io](https://ploi.io/)  - 服务器管理工​​具，可轻松管理和部署您的服务器和站点.  1台服务器免费.


## Messaging and Streaming

  * [Ably](https://www.ably.com/)  - 具有存在、持久性和保证交付的实时消息传递服务. 免费计划包括每月 300 万条消息、100 个高峰连接和 100 个高峰频道.
  * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ as a Service. Little Lemur plan: max 1 million messages/month, max 20 concurrent connections, max 100 queues, max 10,000 queued messages, multiple nodes in different AZ's
  * [connectycube.com](https://connectycube.com) - Unlimited chat messages, p2p voice & video calls, files attachments and push notifications. Free for apps up to 20K MAU.
  * [courier.com](https://www.courier.com/) — Single API for push, in-app, email, chat, SMS, and other messaging channels with template management and other features. Free plan includes 10,000 messages/mo.
  * [pusher.com](https://pusher.com/) — Realtime messaging service. Free for up to 100 simultaneous connections and 200,000 messages/day
  * [scaledrone.com](https://www.scaledrone.com/) — Realtime messaging service. Free for up to 20 simultaneous connections and 100,000 events/day
  * [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io) 作为一项服务. 全球、AWS、GCP 和 Azure. 每月 4k 消息大小、50 个活动连接和 5GB 数据，永久免费.
  * [cloudkarafka.com](https://www.cloudkarafka.com/) - Free Shared Kafka cluster, up to 5 topics, 10MB data per topic and 28 days of data retention.
  * [pubnub.com](https://www.pubnub.com/)  - 每月 100 万笔交易的 Swift、Kotlin 和 React 消息传递. 事务可能包含多条消息.
  * [eyeson API](https://developers.eyeson.team/)  - 基于WebRTC（SFU，MCU）构建视频平台的视频通信API服务. 允许实时数据注入、视频布局、录制、功能齐全的托管 Web UI（快速入门）或自定义 UI 包. 有一个 [free tier for developers](https://apiservice.eyeson.com/api-pricing) with 1000 meeting minutes a month.


## Log Management

  * [bugfender.com](https://bugfender.com/) — Free up to 100k log lines/day with 24 hours retention
  * [humio.com](https://www.humio.com/) — Free up to 2 GB/day with 7 days retention
  * [logdna.com](https://logdna.com) - Free for a single user, no retention, unlimited hosts and sources
  * [logentries.com](https://logentries.com/) — Free up to 5 GB/month with 7 days retention
  * [loggly.com](https://www.loggly.com/) — Free for a single user, see the lite option
  * [logz.io](https://logz.io/) — Free up to 3 GB/day, 3 days retention
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-log-management)  — 由 Manage Engine 提供支持的日志管理服务. 免费计划提供 50 GB 存储空间和 1 个月的保留期.
  * [papertrailapp.com](https://papertrailapp.com/) — 48 小时搜索，7 天存档，100 MB/月
  * [sematext.com](https://sematext.com/logsene) — 每天最多释放 500 MB，保留 7 天
  * [sumologic.com](https://www.sumologic.com/) — 每天最多释放 500 MB，保留 7 天
  * [logflare.app](https://logflare.app/) — Free for upto 12,960,000 enteries per app per month, 3 days retention
  * [logtail.com](https://logtail.com/) — ClickHouse-based SQL-compatible log management. Free up to 1 GB per month, 3 days retention.


## Translation Management

  * [crowdin.com](https://crowdin.com/) — 无限的项目、无限的字符串和开源合作者
  * [gitlocalize.com](https://gitlocalize.com) - 私人和公共存储库免费且无限制
  * [lingohub.com](https://lingohub.com/) — 最多释放 3 个用户，对开源始终免费
  * [localazy.com](https://localazy.com) - Free for 1000 source language strings, unlimited languages, unlimited contributors, startup and open source deals
  * [Localeum](https://localeum.com) - Free up to 1000 strings, 1 user, unlimited languages, unlimited projects
  * [localizely.com](https://localizely.com/) — 开源免费
  * [Loco](https://localise.biz/) — Free up to 2000 translations, Unlimited translators, 10 languages/project, 1000 translatable assets/project
  * [oneskyapp.com](https://www.oneskyapp.com/) — 最多 5 位用户的有限免费版，开源免费
  * [POEditor](https://poeditor.com/) — Free up to 1000 strings
  * [SimpleLocalize](https://simplelocalize.io/) - 最多免费 100 个翻译键、无限字符串、无限语言、启动交易
  * [Texterify](https://texterify.com/) - 单个用户免费
  * [transifex.com](https://www.transifex.com/) — 开源免费
  * [Translation.io](https://translation.io) - 开源免费
  * [webtranslateit.com](https://webtranslateit.com/) — 最多释放 500 个字符串
  * [weblate.org](https://weblate.org/) — It's free for libre projects up to 10,000 string source for the free tier, and Unlimited Self-hosted on-premises.
  * [Free PO editor](https://pofile.net/free-po-editor) — Free for everybody


## Monitoring

  * [Pingmeter.com](https://pingmeter.com/) - 5 uptime monitors with 10 minutes interval. monitor SSH, HTTP, HTTPS, and any custom TCP ports.
  * [amixr.io](https://amixr.io/)  - 通过出色的 Slack 集成、API 和 Terraform 对开发人员友好的警报和待命管理. 免费电话、短信、电报、Slack 和电子邮件套餐.
  * [appdynamics.com](https://www.appdynamics.com/) — 24 小时免费指标，应用程序性能管理代理仅限于一种 Java、一种 .NET、一种 PHP 和一种 Node.js
  * [appneta.com](https://www.appneta.com/) — Free with 1-hour data retention
  * [assertible.com](https://assertible.com) — Automated API testing and monitoring. Free plans for teams and individuals.
  * [blackfire.io](https://blackfire.io/) — Blackfire is the SaaS-delivered Application Performance Solution. Free Hacker plan (PHP only)
  * [checklyhq.com](https://checklyhq.com) - Open source E2E / Synthetic monitoring and deep API monitoring for developers. Free plan with 5 users and 50k+ check runs.
  * [circonus.com](https://www.circonus.com/) — 20 个指标免费
  * [cloudsploit.com](https://cloudsploit.com)  — AWS 安全和配置监控. 免费：无限制的按需扫描、无限制的用户、无限制的存储帐户. 订阅：自动扫描、API访问等.
  * [datadoghq.com](https://www.datadoghq.com/) — Free for up to 5 nodes
  * [deadmanssnitch.com](https://deadmanssnitch.com/) — Monitoring for cron jobs. 1 free snitch (monitor), more if you refer others to sign up
  * [economize.cloud](https://economize.cloud)  — Economize 通过组织、优化和报告云资源，帮助揭开云基础设施成本的神秘面纱. 每月在 Google Cloud Platform 上花费高达 5000 美元即可免费使用.
  * [elastic.co](https://www.elastic.co/solutions/apm)  — 为 JS 开发人员提供即时性能洞察. 免费提供 24 小时数据保留
  * [freeboard.io](https://freeboard.io/)  — 公共项目免费. 物联网 (IoT) 项目的仪表板
  * [freshworks.com](https://www.freshworks.com/website-monitoring/) — 以 1 分钟的间隔监控 50 个 URL，包含 10 个全球位置和 5 个免费的公共状态页面
  * [gitential.com](https://gitential.com)  — 软件开发分析平台. 免费：无限的公共存储库，无限的用户，私人存储库的免费试用. 可用于企业的本地版本.
  * [Grafana Cloud](https://grafana.com/products/cloud/)  - Grafana Cloud 是一个可组合的可观察性平台，将指标和日志与 Grafana 集成. 免费：3 个用户，10 个仪表板，100 个警报，Prometheus 和 Graphite 中的指标存储（10,000 系列，14 天保留），Loki 中的日志存储（50 GB 日志，14 天保留）
  * [healthchecks.io](https://healthchecks.io) — Monitor your cron jobs and background tasks. Free for up to 20 checks.
  * [inspector.dev](https://www.inspector.dev) - A complete Real-Time monitoring dashboard in less than one minute with free forever tier.
  * [instrumentalapp.com](https://instrumentalapp.com) - 美观且易于使用的应用程序和服务器监控，多达 500 个指标和 3 小时的免费数据可见性
  * [keychest.net/speedtest](https://keychest.net/speedtest) - 针对 Digital Ocean 的独立速度测试和 TLS 握手延迟测试
  * [letsmonitor.org](https://letsmonitor.org) - SSL 监控，最多可免费使用 5 台显示器
  * [loader.io](https://loader.io/) — 有限制的免费负载测试工具
  * [meercode.io](https://meercode.io/)  — Meercode 是您的 CI/CD 构建的终极监控仪表板. 免费提供开源和 1 个私有存储库.
  * [netdata.cloud](https://www.netdata.cloud/) — Netdata is an open source tool designed to collect real-time metrics.Great fast growing product. It can also be found in github!
  * [newrelic.com](https://www.newrelic.com) — New Relic observability platform built to help engineers create more perfect software. From monoliths to serverless, you can instrument everything, then analyze, troubleshoot, and optimize your entire software stack. Free tier offers 100GB/month of free data ingest, 1 free full access user, and unlimited free basic users.
  * [nixstats.com](https://nixstats.com)  - 一台服务器免费. 电子邮件通知、公共状态页面、60 秒间隔等.
  * [OnlineOrNot.com](https://onlineornot.com/) - OnlineOrNot is a reliable uptime monitor for both JS-based web apps and websites. 10 uptime checks (for static websites and APIs) with a 5 minute interval, 1 browser check with a 15 minute interval. Free for up to 3 users, alerts via Slack, Discord, and Email.
  * [opsgenie.com](https://www.opsgenie.com/)  — 强大的警报和待命管理，用于运行始终在线的服务. 最多释放 5 个用户.
  * [paessler.com](https://www.paessler.com/) — Powerful infrastructure and network monitoring solution including alerting, strong visualization capabilities and basic reporting. Free up to 100 sensors.
  * [syagent.com](https://syagent.com/) — Non commercial free server monitoring service, alerts and metrics.
  * [pagertree.com](https://pagertree.com/) - Simple interface for alerting and on-call management. Free up to 5 users.
  * [pingbreak.com](https://pingbreak.com/)  — 现代正常运行时间监控服务. 检查无限 URL 并通过 Discord、Slack 或电子邮件获取停机通知.
  * [pingpong.one](https://pingpong.one/) — Advanced status page platform with monitoring. Free tier includes one public customizable status page with SSL subdomain. Pro plan is offered to open-source projects and non-profits free of charge.
  * [sematext.com](https://sematext.com/) — 免费提供 24 小时指标、无限数量的服务器、10 个自定义指标、500,000 个自定义指标数据点、无限的仪表板、用户等.
  * [sitemonki.com](https://sitemonki.com/) — 网站、域名、Cron 和 SSL 监控，每个类别免费 5 个监控器
  * [skylight.io](https://www.skylight.io/) — Free for first 100,000 requests (Rails only)
  * [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — 性能监控 API，检查 Ping、DNS 等.
  * [stathat.com](https://www.stathat.com/) — Get started with 10 stats for free, no expiration
  * [statuscake.com](https://www.statuscake.com/) — 网站监控，无限制的免费测试
  * [statusgator.com](https://statusgator.com/) — 状态页面监控，3台免费监控
  * [thousandeyes.com](https://www.thousandeyes.com/)  — 网络和用户体验监控. 免费提供主要网络服务的 3 个位置和 20 个数据源
  * [thundra.io/apm](https://www.thundra.io/apm) — Application monitoring and debugging. Has a free tier up to 250k monthly invocations.
  * [uptimerobot.com](https://uptimerobot.com/) — 网站监控，免费 50 台显示器
  * [uptimetoolbox.com](https://uptimetoolbox.com/) — 免费监控 5 个网站，60 秒间隔，公开状态页.
  * [zenduty.com](https://www.zenduty.com/)  — 用于网络运营、站点可靠性工程和 DevOps 团队的端到端事件管理、警报、待命管理和响应编排平台. 最多 5 位用户免费.
  * [asayer.io](https://asayer.io/pricing.html)  — openreplay 的托管版本，一种开源会话重播（FullStory 和 LogRocket 的替代品）. 每月免费 1k 次会话，保留 14 天
  * [lean20.com](https://lean20.com/product/status/)  - 事件报告的公共状态页面.  100% 免费.
  * [instatus.com](https://instatus.com)  - 在 10 秒内获得漂亮的状态页面. 无限订阅和无限团队永远免费.
  * [Squadcast.com](https://squadcast.com)  - Squadcast 是一款端到端的事件管理软件，旨在帮助您推广 SRE 最佳实践. 永久免费计划可供多达 10 位用户使用.


## Crash and Exception Handling

  * [CatchJS.com](https://catchjs.com/) - JavaScript error tracking with screenshots and click trails. Free for open source projects.
  * [bugsnag.com](https://www.bugsnag.com/) — Free for up to 2,000 errors/month after the initial trial
  * [exceptionless](https://exceptionless.com) — Real-time error, feature, log reporting and more. Free for 3k events per month/1 user. Open source and easy to self-host for unlimited use.
  * [GlitchTip](https://glitchtip.com/) — Simple, open source error tracking. Compatible with open-source Sentry SDKs. 1000 events per month for free, or can self-host with no limits
  * [honeybadger.io](https://www.honeybadger.io) - Exception, uptime, and cron monitoring. Free for small teams and open-source projects (12,000 errors/month).
  * [rollbar.com](https://rollbar.com/) — 异常和错误监控、每月 5,000 个错误的免费计划、无限用户、30 天保留
  * [sentry.io](https://sentry.io/) — Sentry tracks app exceptions in real-time, has a small free plan. Free for 5k errors per month/ 1 user, unrestricted use if self-hosted


## Search

  * [algolia.com](https://www.algolia.com/) — Hosted search-as-you-type (instant). Free hacker plan up to 10,000 documents and 100,000 operations. Bigger free plans available for community/Open Source projects
  * [bonsai.io](https://bonsai.io/) — 免费 1 GB 内存和 1 GB 存储空间
  * [searchly.com](http://www.searchly.com/) — 免费 2 个索引和 20 MB 存储空间
  * [pagedart.com](https://pagedart.com/)  - AI 搜索即服务，免费套餐包括 1000 个文档、50000 次搜索. 对于有价值的项目，更大的免费层是可能的.


## Email

  * [10minutemail](https://10minutemail.com) - 用于测试的免费临时电子邮件.
  * [AnonAddy](https://anonaddy.com) - 开源匿名邮件转发，免费创建无限邮件别名
  * [Antideo](https://www.antideo.com)  — 每小时 10 个 API 请求，用于免费套餐中的电子邮件验证、IP 和电话号码验证. 无需信用卡.
  * [biz.mail.ru](https://biz.mail.ru/) — 5,000 个邮箱，每个邮箱 25 GB，每个自定义域使用 DNS 托管
  * [Bump](https://bump.email/) - 免费 10 个 Bump 电子邮件地址，1 个自定义域
  * [Burnermail](https://burnermail.io/) – Free 5 Burner Email Addresses, 1 Mailbox, 7 day Mailbox History
  * [Buttondown](https://buttondown.email/) — Newsletter service. Up to 1,000 subscribers free
  * [CloudMailin](https://www.cloudmailin.com/) - 通过 HTTP POST 和事务出站接收电子邮件 - 每月 10,000 封免费电子邮件
  * [cloudmersive.com](https://www.cloudmersive.com/email-verification-api) — 面向开发人员的电子邮件验证和验证 API，每月 2,000 个免费 API 请求
  * [Contact.do](https://contact.do/) — Contact form in a link (bitly for contact forms) - totally free!
  * [debugmail.io](https://debugmail.io/) — 易于开发人员使用的测试邮件服务器
  * [Email Temporanee](https://emailtemporanee.com/) - Easy to use free Unlimited disposable temporary email addresses (temp email). Autoexpires even you can set it day.
  * [elasticemail.com](https://elasticemail.com)  — 每天 100 封免费电子邮件. 通过 API 以 0.09 美元的价格发送 1,000 封电子邮件（即用即付）.
  * [EmailOctopus](https://emailoctopus.com) - Up to 2,500 subscribers and 10,000 emails per month free
  * [Eva](https://eva.pingutil.com) — Verify 5 million emails per day for free using REST API. No sign-ups required.
  * [fakermail.com](https://fakermail.com/) — Free, temporary email for testing with last 100 email accounts stored.
  * [forwardemail.net](https://forwardemail.net)  — 自定义域的免费电子邮件转发. 使用您的域名创建和转发无限数量的电子邮件地址（**注意**：如果您使用 .casa、.cf、.click、.email、.fit、.ga、.gdn、.gq、 .loan、.london、.men、.ml、.pl、.rest、.ru、.tk、.top、.work 顶级域名（由于垃圾邮件）
  * [ImprovMX](https://improvmx.com) – Free email forwarding
  * [inboxkitten.com](https://inboxkitten.com/)  - 免费的临时/一次性电子邮件收件箱，最多可自动删除 3 天的电子邮件. 开源，可以自托管.
  * [inumbo.com](http://inumbo.com/) — SMTP based spam filter, free for 10 users
  * [kickbox.io](https://kickbox.io/) — Verify 100 emails free, real-time API available
  * [mail.gw](https://mail.gw)  — 10 分钟邮件. 免费匿名临时电子邮件，没有义务.
  * [mail.tm](https://mail.tm) — Disposable e-mail with user friendly interface. No registration needed.
  * [mailazy.com](https://mailazy.com/)  — Mailazy 是您唯一需要的简单交易电子邮件服务.  15,000 封电子邮件/月永久免费（500 封电子邮件/天发送限制）.
  * [mail-tester.com](https://www.mail-tester.com) — 测试电子邮件的 dns/spf/dkim/dmarc 设置是否正确，每月免费 20
  * [dkimvalidator.com](https://dkimvalidator.com/) - 测试电子邮件的 dns/spf/dkim/dmarc 设置是否正确，roundsphere.com 提供免费服务
  * [mailboxlayer.com](https://mailboxlayer.com/)  — 面向开发人员的电子邮件验证和验证 JSON API.  1,000 个免费 API 请求/月
  * [mailcatcher.me](https://mailcatcher.me/) — 捕获邮件并通过 Web 界面发送邮件
  * [mailchimp.com](https://mailchimp.com/) — 2,000 名订阅者和 12,000 封电子邮件/月免费
  * [MailerLite.com](https://www.mailerlite.com) — 1,000 名订阅者/月，12,000 封电子邮件/月免费
  * [mailinator.com](https://www.mailinator.com/) — Free, public, email system where you can use any inbox you want
  * [mailjet.com](https://www.mailjet.com/) — 6,000 封电子邮件/月免费（每日发送限制 200 封电子邮件）
  * [mailkitchen](https://www.mailkitchen.com/) — 终身免费，无需承诺，每月 10,000 封电子邮件，每天 1,000 封电子邮件
  * [mailmenot.io](http://mailmenot.io) — Free disposable temporary email service with ability to add multiple email addresses
  * [Mailnesia](https://mailnesia.com) - Free temporary/disposable email, which auto visit registration link.
  * [mailsac.com](https://mailsac.com) - Free API for temporary email testing, free public email hosting, outbound capture, email-to-slack/websocket/webhook (1,500 monthly API limit)
  * [Mailtie.com](https://mailtie.com/) - Free Email Forwarding for Your Domain. No registration required. Free Forever.
  * [mailtrap.io](https://mailtrap.io/) — 用于开发的假 SMTP 服务器，带有 1 个收件箱的免费计划，50 条消息，没有团队成员，2 封电子邮件/秒，没有转发规则
  * [mailvalidator.io](https://mailvalidator.io/) - 每月免费验证 300 封电子邮件，提供批量处理的实时 API
  * [mail7.io](https://www.mail7.io/)  — QA 开发人员的免费临时电子邮件地址. 使用 Web 界面或 API 立即创建电子邮件地址
  * [mohmal.com](https://www.mohmal.com/en) — Disposable temporary email
  * [moosend.com](https://moosend.com/)  — 邮件列表管理服务. 为初创公司提供 6 个月的免费帐户
  * [Outlook.com](https://outlook.live.com/owa/) - Free personal email and calendar
  * [Parsio.io](https://parsio.io) - 免费电子邮件解析器（转发电子邮件，提取数据，将其发送到您的服务器）
  * [pepipost.com](https://pepipost.com) — 第一个月免费发送 30k 封电子邮件，然后每天免费发送前 100 封电子邮件
  * [phplist.com](https://phplist.com/) — Hosted version allow 300 emails/month free
  * [postmarkapp.com](https://postmarkapp.com/) - 100 emails/month free, unlimited DMARC weekly digests
  * [QuickEmailVerification](https://quickemailverification.com) — 在免费套餐中每天免费验证 100 封电子邮件以及 DEA 检测器、DNS 查找、SPF 检测器等其他免费 API.
  * [Sender](https://www.sender.net) 每月最多 15 000 封电子邮件 - 最多 2 500 名订阅者
  * [sendgrid.com](https://sendgrid.com/) — 100 emails/day and 2,000 contacts free
  * [sendinblue.com](https://www.sendinblue.com/) — 9,000 封电子邮件/月免费
  * [sendpulse.com](https://sendpulse.com) — 50 emails free/hour, first 12,000 emails/month free
  * [socketlabs.com](https://www.socketlabs.com) - 第一个月免费发送 40k 封电子邮件，然后每月免费发送前 2000 封电子邮件
  * [sparkpost.com](https://www.sparkpost.com/) — 前 500 封电子邮件/月免费
  * [Substack](https://substack.com)  — 无限制的免费通讯服务. 收费时开始付款.
  * [Tempmailo](https://tempmailo.com/) - Unlimited free temp email addresses. Autoexpire in two days.
  * [HotTempMail](https://hottempmail.com/)  - 无限制的免费临时电子邮件或一次性临时电子邮件地址. 一天后自动过期.
  * [temp-mail.io](https://temp-mail.io) — 免费一次性临时电子邮件服务，一次发送多封电子邮件并转发
  * [temp-mail.org](https://temp-mail.org) — Temporary, secure, anonymous, free, disposable email address with REST API for fetching 100 emails from its disposable mailbox per day for free.
  * [testmail.app](https://testmail.app/) - Automate end-to-end email tests with unlimited mailboxes and a GraphQL API. 100 emails/month free forever, unlimited free for open source.
  * [tinyletter.com](https://tinyletter.com/) — 5,000 名订阅者/月免费
  * [trashmail.com](https://www.trashmail.com) - 具有转发和自动地址到期功能的免费一次性电子邮件地址
  * [Validator.Pizza](https://www.validator.pizza/) — Free API to detect disposable emails
  * [Verifalia](https://verifalia.com/email-verification-api) — Real-time email verification API with mailbox confirmation and disposable email address detector; 25 free email verifications/day.
  * [verimail.io](https://verimail.io/) — Bulk and API email verification service. 100 free verifications/month
  * [Yandex.Connect](https://connect.yandex.com/pdd/) — Free email and DNS hosting for up to 1,000 users
  * [yopmail.fr](http://www.yopmail.fr/en/) — 一次性电子邮件地址
  * [Zoho](https://www.zoho.com)  — 最初是一家电子邮件提供商，但现在提供一套服务，其中一些服务提供免费计划. 具有免费计划的服务列表：
     - [Email](https://zoho.com/mail)  5个用户免费.  5GB/用户和 25MB 附件限制，1 个域.
     - [Sprints](https://zoho.com/sprints) Free for 5 users,5 Projects & 500MB storage.
     - [Docs](https://zoho.com/docs) — Free for 5 users with 1 GB upload limit & 5GB storage. Zoho Office Suite (Writer,Sheets & Show) comes bundled with it.
     - [Projects](https://zoho.com/projects)  — 3 个用户、2 个项目和 10 MB 附件限制免费. 同样的计划适用于 [Bugtracker](https://zoho.com/bugtracker).
     - [Connect](https://zoho.com/connect) — 25 位用户的团队协作免费，包含 3 个组、3 个自定义应用程序、3 个板、3 个手册、10 个集成以及渠道、活动和论坛.
     - [Meeting](https://zoho.com/meeting) — 最多 3 位会议参与者和 10 位网络研讨会参与者的会议.
     - [Vault](https://zoho.com/vault) — Password Management free for Individuals.
     - [Showtime](https://zoho.com/showtime) — 另一个会议软件，用于培训最多 5 名与会者的远程会议.
     - [Notebook](https://zoho.com/notebook) — A free alternative to Evernote.
     - [Wiki](https://zoho.com/wiki) — 3 位用户免费提供 50 MB 存储空间、无限页面、zip 备份、RSS 和 Atom 提要、访问控制和可自定义的 CSS.
     - [Subscriptions](https://zoho.com/subscriptions)  — 为 20 位客户/订阅和 1 位用户免费提供定期计费管理，所有付款托管均由 Zoho 自己完成. 存储最后 40 个订阅指标
     - [Checkout](https://zoho.com/checkout) — 3 页和最多 50 次付款的产品计费管理.
     - [Desk](https://zoho.com/desk)  — 具有 3 个代理和私人知识库、电子邮件票证的客户支持管理. 与集成 [Assist](https://zoho.com/assist) 适用于 1 名远程技术人员和 5 台无人值守的计算机.
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
  * [Everything Fonts](https://everythingfonts.com/)  - 提供多种工具；  @font-face，单位转换器，字体提示和字体提交者.
  * [Font Squirrel](https://www.fontsquirrel.com/)  - 获得商业作品许可的免费字体. 手工选择这些字体并以易于使用的格式呈现.
  * [Google Fonts](https://fonts.google.com/) - Lots of free fonts that are easy and quick to install in a website via a download or a link to Google's CDN.
  * [FontGet](https://www.fontget.com/) - Has a variety of fonts available to download and sorted neatly with tags.
  * [Fontshare](https://www.fontshare.com/)  - 是一项免费的字体服务. 这是一个不断增长的专业级字体集合，100% 免费供个人和商业使用.


## Forms

  * [99inbound.com](https://www.99inbound.com/)  - 建立表格并在线分享. 为每次提交获取电子邮件或 Slack 消息. 免费计划有 2 种表格，每月 100 个条目，基本电子邮件和 Slack.
  * [Form.taxi](https://form.taxi/) — Endpoint for HTML forms submissions. With notifications, spam blocker and GDPR-compliant data processing. Free plan for basic usage.
  * [Formcake.com](https://formcake.com)  - 开发人员的表单后端，免费计划允许无限的表单，100 个提交，Zapier 集成. 不需要库或依赖项.
  * [Formcarry.com](https://formcarry.com) - HTTP POST Form endpoint, Free plan allows 100 submissions per month.
  * [formingo.co](https://www.formingo.co/) - 用于静态网站的简单 HTML 表单，无需注册帐户即可免费使用. 免费计划允许每月 500 次提交，可自定义回复电子邮件地址.
  * [formlets.com](https://formlets.com/) — Online forms, unlimited single page forms/month, 100 submissions/month, email notifications.
  * [formrocket.me](https://www.formrocket.me)  - HTML 表单变得简单，无限制的表单和响应. 附带 Discord 通知等.
  * [formspark.io](https://formspark.io/) - 表格到电子邮件服务，免费计划允许无限的表格，每月 250 份提交，客户支持团队的支持.
  * [Formspree.io](https://formspree.io/) — Send email using an HTTP POST request. Free tier limits to 50 submissions per form per month.
  * [Formsubmit.co](https://formsubmit.co/)  — HTML 表单的简单表单端点. 永远免费. 无需注册.
  * [getform.io](https://getform.io/) - Form backend platform for designers and developers, 1 form, 50 submissions, Single file upload, 100MB file storage.
  * [HeroTofu.com](https://herotofu.com/) - Forms backend with bot detection and encrypted archive. Forward submissions via UI to email, Slack, or Zapier. Use your own frontend, no server code required. Free plan gives unlimited forms and 100 submissions per month.
  * [HeyForm.net](https://heyform.net/) - Drag and drop online form builder. Free tier lets you create unlimited forms and collect unlimited submissions. Comes with pre-built templates, anti-spam, and 100MB file storage.
  * [Hyperforms.app](https://hyperforms.app/)  — 在几秒钟内创建表单以发送电子邮件等，无需后端代码. 个人帐户每月最多可免费为您提供 50 份表单提交.
  * [Kwes.io](https://kwes.io/)  - 功能丰富的形式端点. 适用于静态网站. 免费计划包括最多 1 个网站，每月最多 50 个提交.
  * [Pageclip](https://pageclip.co/) - Free plan allows one site, one form, 1,000 submissions per month.
  * [Qualtrics Survey](https://qualtrics.com/free-account) — Create professional forms & survey using this first class tool. 50+ expert-designed survey templates. Free Account has limit of 1 active survey, 100 responses/survey & 8 response types.
  * [smartforms.dev](https://smartforms.dev/) - Powerful and easy form backend for your website, forever free plan allows 50 submissions per month, 250MB file storage, Zapier integration, CSV/JSON export, custom redirect, custom response page, Telegram & Slack bot, single email notifications.
  * [staticforms.xyz](https://www.staticforms.xyz/)  - 免费集成 HTML 表单，无需任何服务器端代码. 用户提交表单后，将向您的注册地址发送一封包含表单内容的电子邮件.
  * [stepFORM.io](https://stepform.io) - Quiz and Form Builder. Free plan has 5 forms, up to 3 steps per form, 50 responses per month.
  * [Typeform.com](https://www.typeform.com/) — Include beautifully designed forms on websites.  Free plan allows only 10 fields per form and 100 responses per month.
  * [WaiverStevie.com](https://waiverstevie.com) - Electronic Signature platform with a REST API. Receive notifications with webhooks. Free plan watermarks signed documents, but allows unlimited envelopes + signatures.
  * [Web3Forms](https://web3forms.com) - Contact forms for Static & JAMStack Websites without writing backend code. Free plan allows Unlimited Forms, Unlimited Domains & 250 Submissions per month.
  * [WebAsk](https://webask.io)  - 调查和表格生成器. 免费计划每个帐户有 3 个调查，每月 100 个回复，每个调查 10 个元素.
  * [Wufoo](https://www.wufoo.com/)  - 在网站上使用的快速表格. 免费计划每月有 100 次提交的限制.
  * [formpost.app](https://formpost.app) - Free, unlimited Form to Email service. Setup custom redirect, auto response, webhooks etc for free.


## CDN and Protection

  * [Arvan Cloud](https://arvancloud.com/)  — 提供云相关服务（CDN、Cloud DNS、PaaS、安全等）. 免费计划提供：
     - 带有免费 SSL 的 CDN.  50 GB 流量 + 100 万个 HTTP(S) 请求.
    - 无限域的免费云 DNS.
    - Free Cloud Security with Basic DDoS Protection + 5 Firewall Rules.
    - Free VoD (Video On Demand) Platform with 10 GB Storage + 50 GB Traffic.
  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) — bootstrap、bootswatch 和 fontawesome.io 的 CDN
  * [cdnjs.com](https://cdnjs.com/)  - 简单的. 快速地. 可靠的. 最好的内容交付.  cdnjs 是一项免费的开源 CDN 服务，受到超过 11% 的网站的信任，由 Cloudflare 提供支持.
  * [Cloudflare](https://www.cloudflare.com/)
    * CDN 以及免费 SSL
    * 无限数量域的免费 DNS
    * 防火墙规则和页面规则
    * 分析
    * [Cloudflare Pages](https://pages.cloudflare.com/)  — 免费网络托管（JAMstack 平台），供前端开发人员协作和部署网站. 一次构建 1 个，每月 500 个构建，无限站点，无限请求，无限带宽.
    * [Cloudflare Workers](https://workers.cloudflare.com/)  — 在 Cloudflare 的全球网络上免费部署无服务器代码. 每天有 100,000 个使用 workers.dev 子域的免费请求.
    * [Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/run-tunnel/trycloudflare)  — 创建从您的服务器到可公开访问、随机生成的 trycloudflare.com 域的隧道. 无需帐户.
  * [Combinatronics](https://combinatronics.com/)  - 将您的 Github 托管资产（图像、CSS、JS 等）转换为 CDN 资产. 甚至可以渲染 HTML 文件，例如 [example from this repo](https://combinatronics.com/ripienaar/free-for-dev/master/index.html) . 类似于 rawgit.com 和 raw.githack.com.
  * [ddos-guard.net](https://ddos-guard.net/store/web) — 免费 CDN、DDoS 保护和 SSL 证书
  * [developers.google.com](https://developers.google.com/speed/libraries/) — The Google Hosted Libraries is a content distribution network for the most popular, Open Source JavaScript libraries
  * [GraphCDN](https://graphcdn.io/)  - 扩展、检查和保护您的 GraphQL API. 每月 500 万次免费请求.
  * [jare.io](http://www.jare.io) — CDN for images. Uses AWS CloudFront
  * [jsdelivr.com](https://www.jsdelivr.com/)  — 一个免费、快速、可靠的开源 CDN. 支持 npm、GitHub、WordPress、Deno 等.
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — The Microsoft Ajax CDN hosts popular third-party JavaScript libraries such as jQuery and enables you to easily add them to your Web application
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) — 免费 DDoS 保护和 SSL 证书
  * [PageCDN.com](https://pagecdn.com/) - Offers free Public CDN for everyone, and free Private CDN for opensource / nonprofits.
  * [Skypack](https://www.skypack.dev/)  — 100% 原生 ES 模块 JavaScript CDN. 每个域每月 100 万次请求免费.
  * [raw.githack.com](https://raw.githack.com/) — **rawgit.com** 的现代替代品，它仅使用 Cloudflare 托管文件
  * [section.io](https://www.section.io/) <i>— A simple way to spin up and manage a complete Varnish Cache solution.</i> <b>— 一种启动和管理完整 Varnish Cache 解决方案的简单方法。</b> <i>Supposedly free forever for one site</i><b>据说一个网站永久免费</b>
  * [speeder.io](https://speeder.io/) — Uses KeyCDN. Automatic image optimization and free CDN boost. Free and does not require any server changes
  * [statically.io](https://statically.io/) — Git repos（GitHub、GitLab、Bitbucket）、WordPress 相关资产和图像的 CDN
  * [toranproxy.com](https://toranproxy.com/)  — Packagist 和 GitHub 的代理. 永远不会失败的CD. 免费供个人使用，1个开发者，不支持
  * [UNPKG](https://unpkg.com/) — CDN for everything on npm
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — 免费 DDoS 保护


## PaaS

  * [anvil.works](https://anvil.works)  - 仅使用 Python 进行 Web 应用程序开发. 无限应用的免费套餐.
  * [appharbor.com](https://appharbor.com/) — A .Net PaaS that provides 1 free worker
  * [configure.it](https://www.configure.it/) — 移动应用开发平台，2个项目免费，功能有限但无资源限制
  * [codenameone.com](https://www.codenameone.com/)  — 面向 Java/Kotlin 开发人员的开源、跨平台、移动应用程序开发工具链. 免费用于商业用途，项目数量不限
  * [Deta](https://www.deta.sh)  – 免费部署无限数量的 Node.js 和 Python 应用程序. 包括免费的数据库、身份验证和电子邮件.
  * [encore.dev](https://encore.dev/) — Backend framework using static analysis to provide automatic infrastructure, boilerplate free code, and more. Includes free cloud hosting for hobby projects.
  * [gigalixir.com](https://gigalixir.com/) - Gigalixir 为 Elixir/Phoenix 应用程序提供 1 个永不休眠的免费实例，以及限制为 2 个连接、10、000 行且无备份的免费层级 PostgreSQL 数据库。
  * [Glitch](https://glitch.com/)  — 具有代码共享和实时协作等功能的免费公共托管. 免费计划有 1000 小时/月的限制.
  * [Heroku](https://www.heroku.com/) — Host your apps in the cloud, free for single process apps
  * [Krucible](https://usekrucible.com) — Krucible is a platform for creating Kubernetes clusters for testing and development. Free tier accounts come with 25 cluster-hours per month.
  * [Mendix](https://www.mendix.com/) — Rapid Application Development for Enterprises, unlimited number of free sandbox environments supporting unlimited users, 0.5 GB storage and 1 GB RAM per app. Also Studio and Studio Pro IDEs are allowed in free tier.
  * [m3o.com](https://m3o.com)  - API 服务开发的云平台.  M3O 是一个完全托管的微即服务产品，专注于云中的 Go 微服务开发. 免费套餐足以运行 5 项服务并与他人协作.
  * [Okteto Cloud](https://okteto.com) - Managed Kubernetes service designed for remote development. Free developer accounts come with 5 Kubernetes namespaces, 3Gi/pod with a maximum of 8Gi/namespace, 1CPU/pod with a maximum of 4CPUs/namespace and 5GB Disk space. The apps sleep after 24 hours of inactivity.
  * [opeNode](https://openode.io)  — 用于开源项目的免费 Node.js 托管.  100 GB 带宽/月，100 MB 内存和 1000 MB 存储空间. 使用 CLI 或现有 Git 存储库进行部署.
  * [outsystems.com](https://www.outsystems.com/) — Enterprise web development PaaS for on-premise or cloud, free "personal environment" offering allows for unlimited code and up to 1 GB database
  * [pipedream.com](https://pipedream.com)  - 为开发人员构建的集成平台. 基于任何触发器开发任何工作流. 工作流是可以运行的代码 [for free](https://docs.pipedream.com/pricing/) . 无需管理服务器或云资源.
  * [pythonanywhere.com](https://www.pythonanywhere.com/)  — 云 Python 应用程序托管. 初学者帐户是免费的，在 your-username.pythonanywhere.com 域中有 1 个 Python Web 应用程序，512 MB 私人文件存储，一个 MySQL 数据库
  * [scn.sap.com](https://scn.sap.com/docs/DOC-56411)  — SAP 的内存平台即服务产品. 免费的开发者帐户附带 1 GB 结构化、1 GB 非结构化、1 GB Git 数据，并允许您运行 HTML5、Java 和 HANA XS 应用程序
  * [Serverless Cloud](https://www.serverless.com/cloud) - Serverless Cloud lets you build Serverless APIs, DBs and Storage by using infrastrucure _from_ code approach(no yaml, no infrastructure configuration). The product is provided by Serverless Inc. and currently under public preview. 
  * [fly.io](https://fly.io/)  - Fly 是一个面向需要在全球范围内运行的应用程序的平台. 它在靠近用户的地方运行您的代码，并在您的应用程序最繁忙的城市扩展计算. 编写您的代码，将其打包成 Docker 映像，将其部署到 Fly 的平台，并让其完成所有工作以保持您的应用程序快速运行. 辅助项目免费，每月 10 美元的服务信用额度自动适用于任何付费服务. 而且，如果您运行非常小的虚拟机，那么积分将大有帮助.
  * [Divio](https://www.divio.com/) - A platform to manage cloud application deploying only using Docker. Available free subscription for development projects, Requires card and no custom domain support.  
  * [Koyeb](https://www.koyeb.com)  - Koyeb 是一个开发人员友好的无服务器平台，用于在全球部署应用程序. 通过基于 git 的部署、本机自动缩放、全球边缘网络以及内置的服务网格和发现，无缝运行 Docker 容器、Web 应用程序和 API.  Koyeb 提供了两种纳米服务来运行您的应用程序及其永久免费层，并且还赞助具有免费资源的开源项目.
  * [Railway](https://railway.app)  - 铁路是一个基础架构平台，您可以在其中配置基础架构，在本地使用该基础架构进行开发，然后部署到云端.  1GB 磁盘，512 MB RAM，每月限用 5 美元免费提供.
  * [Napkin](https://www.napkin.io/) - FaaS with 1Gb of memory, a default timeout of 15 seconds and 1,000,000 free API calls/month.
  * [Meteor Cloud](https://www.meteor.com/cloud)  — 银河托管.  Meteor 自己的 Meteor 应用程序平台即服务，其中包括免费的 MongoDB 共享主机和自动 SSL.
  * [Northflank](https://northflank.com) — Build and deploy microservices, jobs and managed databases with a powerful UI, API & CLI. Seamlessly scale containers from version control and external Docker registries. Free tier includes 2 services, 2 cron jobs and 1 database.


## BaaS

  * [ably.com](https://www.ably.com)  - 用于实时消息传递、推送通知和事件驱动 API 创建的 API. 免费计划有 300 万条消息/月，100 个并发连接，100 个并发通道.
  * [back4app.com](https://www.back4app.com) - Back4App 是一个易于使用、灵活且可扩展的基于 Parse 平台的后端.
  * [backendless.com](https://backendless.com/) — 移动和 Web Baas，提供 1 GB 的免费文件存储空间，每月推送通知 50000 个，表中包含 1000 个数据对象.
  * [BMC Developer Program](https://developers.bmc.com/site/global/bmc_helix_platform/program/overview/index.gsp) — The BMC Developer Program provides documentation and resources to build and deploy digital innovations for your enterprise. Access to a comprehensive, personal sandbox which includes the platform, SDK, and a library of components that can be used to build and tailor apps.
  * [darklang.com](https://darklang.com/) - Hosted language combined with editor and infrastructure. Free during the beta, generous free tier planned after beta.
  * [Firebase](https://firebase.com)  — Firebase 可帮助您构建和运行成功的应用程序. 免费 Spark 计划提供身份验证、托管、Firebase ML、实时数据库、云存储、测试实验室.  A/B 测试、分析、应用分发、应用索引、云消息传递 (FCM)、Crashlytics、动态链接、应用内消息传递、性能监控、预测和远程配置始终免费.
  * [Flutter Flow](https://flutterflow.io)  — 无需编写任何代码即可构建您的 Flutter App UI. 还具有 Firebase 集成. 免费计划包括对 UI Builder 和免费模板的完全访问权限.
  * [getstream.io](https://getstream.io/) — 在几小时而不是几周内构建可扩展的新闻源、活动流、聊天和消息传递
  * [hasura.io](https://hasura.io/) — Hasura extends your existing databases wherever it is hosted and provides an instant GraphQL API that can be securely accessed for web, mobile, and data integration workloads. Free for 1GB/month of data pass-through.
  * [iron.io](https://www.iron.io/) — Async task processing (like AWS Lambda) with free tier and 1-month free trial
  * [netlicensing.io](https://netlicensing.io)  - 一种经济高效的集成许可即服务 (LaaS) 解决方案，适用于从桌面到物联网和 SaaS 的任何平台上的软件. 学生期间*免费*的基本计划.
  * [nhost.io](https://nhost.io)  - 用于 Web 和移动应用程序的无服务器后端. 免费计划包括：PostgreSQL、GraphQL (Hasura)、身份验证、存储和无服务器函数.
  * [onesignal.com](https://onesignal.com/) — Unlimited free push notifications
  * [paraio.com](https://paraio.com) — Backend service API with flexible authentication, full-text search and caching. Free for 1 app, 1GB app data.
  * [posthook.io](https://posthook.io/)  — 作业调度服务. 允许您安排特定时间的请求.  500 个预定请求/月免费.
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
  * [simperium.com](https://simperium.com/) — Move data everywhere instantly and automatically, multi-platform, unlimited sending and storage of structured data, max. 2,500 users/month
  * [stackstorm.com](https://stackstorm.com/) — 应用程序、服务和工作流的事件驱动自动化，免费无流，访问控制，LDAP，...
  * [streamdata.io](https://streamdata.io/) — Turns any REST API into an event-driven streaming API. Free plan up to 1 million messages and 10 concurrent connections.
  * [Supabase](https://supabase.io)  — 构建后端的开源 Firebase 替代方案. 免费计划提供身份验证、实时数据库和对象存储.
  * [tyk.io](https://tyk.io/)  — 具有身份验证、配额、监控和分析的 API 管理. 免费云产品
  * [zapier.com](https://zapier.com/)  — 连接您使用的应用程序，以自动执行任务.  5 zaps，每 15 分钟和 100 个任务/月
  * [LeanCloud](https://leancloud.app/)  — 移动后端.  1GB 数据存储、256MB 实例、3K API 请求/天、10K 推送/天免费.  （API 与 Parse Platform 非常相似）
  * [Liteflow](https://liteflow.com/) - Low-code development toolkit built to help you focus on your app’s real value.
  * [BudiBase](https://budibase.com/) - Budibase is an open-source low-code platform for creating internal apps in minutes. Supports PostgreSQL, MySQL, MSSQL, MongoDB, Rest API, Docker, K8s 


## Web Hosting

  * [Alwaysdata](https://www.alwaysdata.com/)  — 100 MB 免费网络托管，支持 MySQL、PostgreSQL、CouchDB、MongoDB、PHP、Python、Ruby、Node.js、Elixir、Java、Deno、自定义网络服务器，可通过 FTP、WebDAV 和 SSH 访问； 包括邮箱、邮件列表和应用程序安装程序.
  * [Awardspace.com](https://www.awardspace.com) — 免费虚拟主机 + 免费短域名、PHP、MySQL、应用安装程序、电子邮件发送和无广告.
  * [Bubble](https://bubble.io/) — 无需代码即可构建 Web 和移动应用程序的可视化编程，免费使用 Bubble 品牌.
  * [cloudno.de](https://cloudno.de/) — Node.js 应用程序的免费云托管.
  * [Deploy Now](https://deploynow.space) — Deploy smarter. Deploy faster. Deploy Now. - Deploy up to 3 web projects from your GitHub repository for free.
  * [Drive To Web](https://drv.tw) — Host directly to the web from Google Drive & OneDrive. Static sites only. Free forever. One site per Google/Microsoft account.
  * [Fenix Web Server](https://preview.fenixwebserver.com) - A developer desktop app for hosting sites locally and sharing them publically (in realtime). Work however you like, using its beautiful user interface, API, and/or CLI.
  * [Free Hosting](http://freehostingnoads.net/) — Free Hosting With PHP 5, Perl, CGI, MySQL, FTP, File Manager, POP E-Mail, free sub-domains, free domain hosting, DNS Zone Editor, Web Site Statistics, FREE Online Support and many more features not offered by other free hosts.
  * [Freehostia](https://www.freehostia.com) — FreeHostia offers free hosting services incl. an industry-best Control Panel & a 1-click installation of 50+ free apps. Instant setup. No forced ads.
  * [hostman.com](https://hostman.com) — 从您的 GitHub 存储库免费部署多达 3 个静态站点.
  * [Neocities](https://neocities.org) — 静态、1 GB 免费存储和 200 GB 带宽.
  * [Netlify](https://www.netlify.com/) — 免费构建、部署和托管静态站点/应用程序，提供 100 GB 数据和 100 GB/月带宽.
  * [Layer0](https://layer0.co/) Deploy fast dynamic Jamstack websites on a global CDN powered by [Limelight](https://www.limelight.com/) 免费提供 100GB/月带宽和 3 个环境.
  * [pantheon.io](https://pantheon.io/)  — Drupal 和 WordPress 托管、自动化 DevOps 和可扩展的基础架构. 开发商和代理商免费
  * [readthedocs.org](https://readthedocs.org/) — 带有版本控制、PDF 生成等功能的免费文档托管
  * [render.com](https://render.com) — 统一云，使用免费 SSL、全球 CDN、专用网络、从 Git 自动部署以及完全免费的 Web 服务、数据库和静态网页计划来构建和运行应用程序和站点.
  * [SourceForge](https://sourceforge.net/) — 免费查找、创建和发布开源软件
  * [Stormkit](https://stormkit.io/)  — 将构建、部署和托管与 JAMStack 或 Node.JS 应用程序的 git 流无缝集成. 每月免费 50 GB 带宽和 1000 万个请求，包括免费 SSL.
  * [surge.sh](https://surge.sh/) — Static web publishing for Front-End developers. Unlimited sites with custom domain support
  * [tilda.cc](https://tilda.cc/) — 一个站点，50 个页面，50 MB 存储空间，只有 170 多个可用的主要预定义块，没有字体，没有 favicon 和自定义域
  * [txti.es](https://txti.es/) — 使用 Markdown 快速创建网页.
  * [Vercel](https://vercel.com/) — Build, deploy, and host web apps with free SSL, global CDN, and unique Preview URLs each time you `git push`. Perfect for Next.js and other Static Site Generators.
  * [Versoly](https://versoly.com/) — SaaS focussed website builder - unlimited websites, 70+ blocks, 5 templates, custom CSS, favicon, SEO and forms. No custom domain.
  * [Qovery](https://www.qovery.com)  — Qovery 是在 AWS、GCP 和 Azure 上部署全栈应用程序的最简单方法. 它是面向具有数据库、SSL、全球 CDN 和 Git 自动部署的开发人员的免费 Web 托管.
  * [Qoddi](https://qoddi.com) - PaaS service similar to Heroku with a developer-centric approach and all inclusive features. Free tier for static assets, staging and developer apps.
  * [FreeFlarum](https://freeflarum.com/) - Community powered free Flarum hosting for up to 250 users (donate to remove watermark from footer).


## DNS
  * [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) - Free public DNS Resolver which is fast and secure (encrypt your DNS query), provided by CloudFlare. Useful to bypass your internet provider's DNS blocking, prevent DNS query spying, and [to block adult & malware content](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families) . 也可以使用 [via API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests) . 注意：只是一个 DNS 解析器，而不是一个 DNS 主机.
  * [1984.is](https://www.1984.is/product/freedns/) — Free DNS service with API, and lots of other free DNS features included.
  * [biz.mail.ru](https://biz.mail.ru) — Free email and DNS hosting for up to 5,000 users
  * [cloudns.net](https://www.cloudns.net/) — Free DNS hosting up to 1 domain with 50 records
  * [dns.he.net](https://dns.he.net/) — Free DNS hosting service with Dynamic DNS Support
  * [dnspod.com](https://www.dnspod.com/) — 免费 DNS 托管.
  * [duckdns.org](https://www.duckdns.org/) — Free DDNS with up to 5 domains on the free tier. With configuration guides for various setups.
  * [dynu.com](https://www.dynu.com/) — 免费动态 DNS 服务
  * [fosshost.org](https://fosshost.org/) - 免费开源托管 VPS、网络、存储和镜像托管
  * [freedns.afraid.org](https://freedns.afraid.org/) — Free DNS hosting. Also provide free subdomain based on numerous public user [contributed domains](https://freedns.afraid.org/domain/registry/). Get free subdomains from "Subdomains" menu after signing up.
  * [luadns.com](https://www.luadns.com/) — Free DNS hosting, 3 domains, all features with reasonable limits
  * [namecheap.com](https://www.namecheap.com/domains/freedns/)  — 免费 DNS. 域名数量没有限制
  * [nextdns.io](https://nextdns.io) - 基于 DNS 的防火墙，每月 30 万次免费查询
  * [noip](https://www.noip.com/) — 动态 dns 服务，最多允许 3 个免费主机名，每 30 天确认一次
  * [ns1.com](https://ns1.com/) — Data Driven DNS, automatic traffic management, 500k free queries
  * [nsupdate.info](https://www.nsupdate.info/) — 免费和开源的动态 DNS 服务
  * [pointhq.com](https://pointhq.com/developer) — Free DNS hosting on Heroku.
  * [selectel.com](https://selectel.com/services/dns/) — 无限记录的免费 DNS 托管，任播
  * [web.gratisdns.dk](https://web.gratisdns.dk/domaener/dns/) — 免费 DNS 托管.
  * [Yandex.Connect](https://connect.yandex.com/pdd/) — Free email and DNS hosting for up to 1,000 users
  * [zilore.com](https://zilore.com/en/dns) — 免费 DNS 托管.
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) — Free DNS hosting with Dynamic DNS Support.
  * [zonewatcher.com](https://zonewatcher.com) — Automatic backups and DNS change monitoring. 1 domain free
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – 华为提供的免费 DNS 托管
  * [Hetzner](https://www.hetzner.com/dns-console) – Hetzner 提供的免费 DNS 托管，支持 API
  * [Glauca](https://docs.glauca.digital/hexdns/) – Free DNS hosting for up to 3 domains and DNSSEC support


## IaaS

  * [filebase.com](https://filebase.com/)  - 由区块链支持的 S3 兼容对象存储.  5 GB 免费存储无限期.
  * [backblaze.com](https://www.backblaze.com/b2/) — Backblaze B2 cloud storage. Free 10 GB (Amazon S3-like) object storage for unlimited time
  * [scaleway.com](https://www.scaleway.com/en/object-storage/)  — S3 兼容的对象存储. 免费 75 GB 存储空间和外部传出流量
  * [terraform.io](https://www.terraform.io/) — Terraform Cloud. Free remote state management and team collaboration for teams up to 5 users.


## DBaaS

   * [airtable.com](https://airtable.com/) — Looks like a spreadsheet, but it's a relational database, unlimited bases, 1,200 rows/base and 1,000 API requests/month
   * [Astra](https://www.datastax.com/products/datastax-astra/) — Cloud Native Cassandra as a Service with [80GB free tier](https://www.datastax.com/products/datastax-astra/pricing)
   * [bit.io](https://bit.io)  — PostgreSQL 托管数据库服务. 无限回购，10GB 存储，10M 查询行/月.
   * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ as a Service, up to 1M messages/month and 20 connections free
   * [elephantsql.com](https://www.elephantsql.com/) — PostgreSQL as a service, 20 MB free
   * [FaunaDB](https://fauna.com/) — 无服务器云数据库，具有原生 GraphQL、多模型访问和高达 100 MB 的每日免费层
   * [HarperDb](https://harperdb.io/) — 无服务器云数据库，具有基于 JSON 的动态模式，3000 IOPS 和 1GB 存储
   * [heroku.com](https://www.heroku.com/) — PostgreSQL as a service, up to 10,000 rows and 20 connections free (provided as an "addon," but can be attached to an otherwise empty app and accessed externally)
   * [Upstash](https://upstash.com/) — Serverless Redis with free tier up to 10,000 requests per day, 256MB max database size, and 20 concurrent connections
   * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — free tier gives 512 MB
   * [redsmin.com](https://www.redsmin.com/) — Redis在线实时监控和管理服务，免费监控1个Redis实例
   * [redislabs](https://redislabs.com/try-free/) - 免费 30Mb redis 实例
   * [MemCachier](https://www.memcachier.com/) — Managed Memcache service. Free for up to 25MB, 1 Proxy Server and basic analytics
   * [scalingo.com](https://scalingo.com/) — 主要是 PaaS，但提供 128MB 到 192MB 的 MySQL、PostgreSQL 或 MongoDB 免费层
   * [SeaTable](https://seatable.io/)  — Seafile 团队构建的灵活、类似电子表格的数据库. 无限表、2,000 行、1 个月版本控制、最多 25 名团队成员.
   * [skyvia.com](https://skyvia.com/) — 云数据平台，提供免费套餐，所有计划在测试阶段完全免费
   * [StackBy](https://stackby.com/)  — 一款将电子表格的灵活性、数据库的强大功能以及与您最喜欢的业务应用程序的内置集成相结合的工具. 免费计划包括无限用户、10 个堆栈、每个堆栈 2GB 附件.
   * [InfluxDB](https://www.influxdata.com/) — Timeseries 数据库，最多可释放 3MB/5 分钟写入、30MB/5 分钟读取和 10,000 个基数系列
   * [Quickmetrics](https://www.quickmetrics.io/) — Timeseries database with dashboard included, free up to 10,000 events/day and total of 5 metrics.
   * [restdb.io](https://restdb.io/)  - 快速简单的 NoSQL 云数据库服务. 使用 restdb.io，您可以获得模式、关系、自动 REST API（带有类似 MongoDB 的查询）和用于处理数据的高效多用户管理 UI. 免费计划每秒允许 3 个用户、2500 条记录和 1 个 API 请求.
   * [cockroachlabs.com](https://www.cockroachlabs.com/free-tier/) — 免费 CockroachDB 高达 5GB 和 1vCPU（有限 [request units](https://www.cockroachlabs.com/docs/cockroachcloud/serverless-faqs.html#what-are-the-usage-limits-of-cockroachdb-serverless-beta))
   * [Neo4j Aura](https://neo4j.com/cloud/aura/) — Managed native Graph DBMS / analytics platform with a Cypher query language and a REST API. Limits on graph size (50k nodes, 175k relationships).
   * [Dgraph Cloud](https://cloud.dgraph.io/pricing?type=free)  — 使用 GraphQL API 托管本机 Graph DBMS. 每天限制为 1 MB 数据传输.
   * [TigerGraph Cloud](https://www.tigergraph.com/cloud/) — Managed native Graph DBMS / analytics platform with a SQL-like graph query language and a REST API. 1 TG.Free instance on AWS (4 vCPU, 7.5 GB memory, 50 GB disk) or on GCP(2 vCPU, 8 GB memory, 128 GB disk). Free instance sleeps after 1 hour of inactivity.
   * [Macrometa](https://www.macrometa.com/) - a noSQL database, Pub/Sub, event processing, and serverless edge computing platform for building geo-distributed and real-time applications. Free dev account gives access to 10,000 Operations/Day & 200MB Storage.
   * [Planetscale](https://planetscale.com/) - PlanetScale 是由 Vitess 提供支持的 MySQL 兼容、无服务器数据库平台，3 个免费数据库，10GB 存储，每个数据库每月读取 1 亿行，每个数据库每月写入 1000 万行.
   * [YugabyteDB](http://cloud.yugabyte.com) - YugabyteDB is a distributed SQL database compatible with PostgresSQL. The cloud free tier is a 2 vCPU, 4GB RAM, 10GB Disk.


## Tunneling, WebRTC, Web Socket Servers and Other Routers

   * [conveyor.cloud](https://conveyor.cloud/) — Visual Studio extension to expose IIS Express to the local network or over a tunnel to a public URL.
   * [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi is a hosted VPN service that lets you securely extend LAN-like networks to distributed teams with free plan allows unlimited networks with up to 5 peoples
   * [localhost.run](https://localhost.run/) — Expose locally running servers over a tunnel to a public URL.
   * [localtunnel](https://theboroer.github.io/localtunnel-www/)  — 通过隧道向公共 URL 公开本地运行的服务器. 免费托管版本，以及 [open source](https://github.com/localtunnel/localtunnel).
   * [ngrok.com](https://ngrok.com/) — Expose locally running servers over a tunnel to a public URL.
   * [Radmin VPN](https://www.radmin-vpn.com/) — Connect multiple computers together via a VPN enabling LAN-like networks. Unlimited peers. (Hamachi alternative)
   * [segment.com](https://segment.com/)  — 将事件翻译和路由到其他第三方服务的集线器.  100,000 个事件/月免费
   * [STUN](https://en.wikipedia.org/wiki/STUN) — Session Traversal of User Datagram Protocol [UDP] Through Network Address Translators [NATs])
     * 谷歌眩晕—— [https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302](https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302)
     * Twilio STUN — [https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp](https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp)
   * [Tailscale](https://tailscale.com/)  — 零配置 VPN，使用开源 WireGuard 协议. 安装在 MacOS、iOS、Windows、Linux 和 Android 设备上.  20 台设备供个人使用的免费计划.
   * [webhookrelay.com](https://webhookrelay.com)  — 管理、调试、扇出和代理所有 webhook 到公共或内部（即：localhost）目的地. 此外，通过获取公共 HTTP 端点（`https://yoursubdomain.webrelay.io &lt;----&gt; http://localhost:8080`），通过隧道公开在专用网络中运行的服务器.
   * [Xirsys](https://www.xirsys.com) — STUN / TURN 服务器的全球网络，提供大量免费套餐.
   * [ZeroTier](https://www.zerotier.com)  — FOSS 管理的虚拟以太网即服务. 免费计划的 100 个客户端的无限端到端加密网络. 桌面/移动/NA客户端； 用于配置自定义路由规则和批准专用网络上的新客户端节点的 Web 界面.


## Issue Tracking and Project Management

   * [acunote.com](https://www.acunote.com/) — 最多 5 名团队成员的免费项目管理和 SCRUM 软件
   * [asana.com](https://asana.com/) — 与合作者的私人项目免费
   * [Backlog](https://backlog.com) — Everything your team needs to release great projects in one platform. Free plan offers 1 Project with 10 users & 100MB storage.
   * [Basecamp](https://basecamp.com/personal)  - 待办事项列表、里程碑管理、类似论坛的消息传递、文件共享和时间跟踪. 最多 3 个项目、20 个用户和 1GB 的存储空间.
   * [bitrix24.com](https://www.bitrix24.com/) — 免费的内网和项目管理工具
   * [cacoo.com](https://cacoo.com/)  — 实时在线图表：流程图、UML、网络. 免费最大.  15 个用户/图表，25 张
   * [Chpokify](https://chpokify.com/) — Teams based Planning Poker that saves time of sprint estimation. Free up to 5 users, free Jira integrations, unlimited video calls, unlimited teams, unlimited sessions.
   * [clickup.com](https://clickup.com/)  - 项目管理. 带有云存储的免费高级版本. 提供移动应用程序和 Git 集成
   * [Cloudcraft](https://cloudcraft.co/) — Design a professional architecture diagram in minutes with the Cloudcraft visual designer, optimized for AWS with smart components that show live data too.
   * [Codegiant](https://codegiant.io) — Project Management with Repository hosting & CI/CD. Free Plan Offers Unlimited Repositories,Projects & Documents with 5 Team Members. 500 CI/CD minutes per month. 30000 Serverless Code Run minutes per month.1GB repository storage.
   * [Confluence](https://www.atlassian.com/software/confluence)  - Atlassian 的内容协作工具，用于帮助团队高效协作和共享知识. 免费计划最多 10 个用户.
   * [contriber.com](https://www.contriber.com/) — Customizable project management platform, free starter plan, 5 workspaces
   * [draw.io](https://www.draw.io/)  — 存储在本地、Google Drive、OneDrive 或 Dropbox 中的在线图表. 免费提供所有功能和存储级别
   * [freedcamp.com](https://freedcamp.com/)  - 任务、讨论、里程碑、时间跟踪、日历、文件和密码管理器. 免费计划，无限项目、用户和文件存储.
   * [easyretro.io](https://www.easyretro.io/) — Free simple and intuitive sprint retrospective tool
   * [GForge](https://gforge.com) — Project Management & Issue Tracking toolset for complex projects with self-premises and SaaS options. SaaS free plan offers first 5 users free & free for Open Source Projects.
   * [gleek.io](https://www.gleek.io)  — 面向开发人员的免费描述到图表工具. 使用关键字创建非正式的 UML 类、对象或实体关系图.
   * [gliffy.com](https://www.gliffy.com/)  — 在线图表：流程图、UML、线框图……还有 Jira 和 Confluence 的插件.  5 个图表和 2 MB 免费
   * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - GraphQL Inspector ouputs a list of changes between two GraphQL schemas. Every change is precisely explained and marked as breaking, non-breaking or dangerous.
   * [huboard.com](https://huboard.com/) — Instant project management for your GitHub issues, free for Open Source
   * [Hygger](https://hygger.io) — Project management platform. Free plan offers unlimited users,projects & boards with 100 MB Storage.
   * [Instabug](https://instabug.com) —  A comprehensive bug reporting and in-app feedback SDK for mobile apps. Free plan up to 1 app and 1 member.
   * [Ilograph](https://www.ilograph.com/)   — 交互式图表，允许用户从多个角度和详细程度查看其基础架构. 图表可以用代码表示. 免费层有无限的私人图表，最多有 3 个查看者.
   * [Issue Embed](https://issueembed.dev/)  - 用于网站直接进入您的 Github 问题的错误报告工具. 个人存储库的免费计划，每月最多 500 个问题和 10,000 个页面浏览量/月.
   * [Jira](https://www.atlassian.com/software/jira)  — 在许多企业环境中使用的高级软件开发项目管理工具. 免费计划最多 10 个用户.
   * [kanbanflow.com](https://kanbanflow.com/) — Board-based project management. Free, premium version with more options
   * [kanbantool.com](https://kanbantool.com/)  — 基于看板的项目管理. 免费的付费计划，有更多选择
   * [Kitemaker.co](https://kitemaker.co)  - 在产品开发过程的所有阶段进行协作，并跟踪跨 Slack、Discord、Figma 和 Github 的工作. 无限用户，无限空间. 免费计划多达 250 个工作项目.
   * [Kumu.io](https://kumu.io/)  — Relationship maps with animation, decorations, filters, clustering, spreadsheet imports and more. Free tier allows unlimited public projects. Graph size unlimited. Free private projects for students. Sandbox mode is available if you prefer to not leave your file publicly online (upload, edit, download, discard).
   * [LeanBoard](https://www.leanboard.io) — Collaborative whiteboard with sticky notes for your GitHub issues (Useful for Example Mapping and other techniques)
   * [Linear](https://linear.app/)  — 具有简化界面的问题跟踪器. 无限会员免费，文件上传最大 10MB，250 期（不包括存档）
   * [MeisterTask](https://www.meistertask.com/)  — 团队的在线任务管理. 最多释放 3 个项目，无限的项目成员.
   * [MeuScrum](https://www.meuscrum.com/en) - 带有看板的免费在线 Scrum 工具
   * [nTask](https://www.ntaskmanager.com/) — Project management software that enables your teams tn collaborate, plan, analyze and manage everyday tasks. Basic Plan free forever with 100 MB storage, 5 users/team. Unlimited workspaces, meetings,tasks, timesheets and issue tracking.
   * [Ora](https://ora.pm/) - Agile task management & team collaboration. Free for up to 3 users and files are limited to 10 MB.
   * [pivotaltracker.com](https://www.pivotaltracker.com/) — 对无限的公共项目和两个私人项目免费，总共有 3 个活跃用户（读写）和无限的被动用户（只读）.
   * [plan.io](https://plan.io/) — Project Management with Repository Hosting and more options. Free for 2 users with 10 customers and 500MB Storage
   * [planitpoker.com](https://www.planitpoker.com/) — 免费在线规划扑克（估算工具）
   * [saas.zentao.pm](https://saas.zentao.pm/) - An Application Lifecycle Management solution for Issue Tracking and Project Management, on-premise and open source version are available as well.
   * [ScrumFast](https://www.scrumfast.com) - Scrum 板具有非常直观的界面，最多可释放 5 个用户.
   * [Shortcut](https://shortcut.com/)  - 项目管理平台. 最多 10 位用户永久免费.
   * [SpeedBoard](https://speedboard.app) - 敏捷和 Scrum 回顾委员会 - 免费.
   * [Shake](https://www.shakebugs.com/)  - 适用于移动应用的应用内错误报告和反馈工具. 免费计划，每个应用程序/每月 10 个错误报告.
   * [Tadum](https://tadum.app) - Meeting agenda and minutes app designed for recurring meetings, free for teams up to 10
   * [taiga.io](https://taiga.io/) — Project management platform for startups and agile developers, free for Open Source
   * [Tara AI](https://tara.ai/)  — 简单的冲刺管理服务. 免费计划有无限的任务、冲刺和工作空间，没有用户限制.
   * [targetprocess.com](https://www.targetprocess.com/) — Visual project management, from Kanban and Scrum to almost any operational process. Free for unlimited users, up to 1,000 data entities {[more details](https://www.targetprocess.com/pricing/)}
   * [taskade.com](https://www.taskade.com/) — Real-time collaborative task lists and outlines for teams
   * [taskulu.com](https://taskulu.com/)  — 基于角色的项目管理. 最多释放 5 个用户. 与 GitHub/Trello/Dropbox/Google Drive 集成
   * [teamwork.com](https://teamwork.com/) — Project management & Team Chat. Free for 5 users and 2 projects. Premium plans available.
   * [testlio.com](https://testlio.com/)  — 问题跟踪、测试管理和beta测试平台. 免费供私人使用
   * [terrastruct.com](https://terrastruct.com/) — Online diagram maker specifically for software architecture. Free tier up to 4 layers per diagram.
   * [todoist.com](https://todoist.com/)  — 协作和个人任务管理. 提供免费、高级和团队计划. 为符合条件的用户提供折扣.
   * [trello.com](https://trello.com/)  — 基于董事会的项目管理. 无限的个人板，10 个团队板.
   * [Tweek](https://tweek.so/) — Simple Weekly To-Do Calendar & Task Management.
   * [ubertesters.com](https://ubertesters.com/) — 测试平台、集成和众测者，2 个项目，5 名成员
   * [vabotu](https://vabotu.com/) - A collaborative tool for project management. Free and other plans are available. The Freelance plan is for 10 users, include messaging, task-boards, 5GB online storage, workspaces, export data.
   * [vivifyscrum.com](https://www.vivifyscrum.com/) — Free tool for Agile project management. Scrum Compatible
   * [Wikifactory](https://wikifactory.com/)  — 包含项目、VCS 和问题的产品设计服务. 免费计划提供无限的项目和合作者以及 3GB 存储空间.
   * [Yodiz](https://www.yodiz.com/)  — 敏捷开发和问题跟踪. 最多释放 3 个用户，无限项目.
   * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) — Free hosted YouTrack (InCloud) for FOSS projects, private projects (free for 3 users). Includes time tracking and agile boards
   * [zenhub.com](https://www.zenhub.com) — The only project management solution inside GitHub. Free for public repos, OSS and nonprofit organizations
   * [zepel.io](https://zepel.io/) - The project management tool that lets you plan features, collaborate across disciplines, and build software together. Free up to 5 members. No feature restrictions.
   * [zenkit.com](https://zenkit.com)  — 项目管理和协作工具. 最多 5 名成员免费，5 GB 附件.
   * [Zube](https://zube.io)  — 为 4 个项目和 4 个用户提供免费计划的项目管理.  GitHub 集成可用.
   * [Toggl](https://toggl.com/) — 提供 2 个免费的生产力工具. [Toggl Track](https://toggl.com/track/) for time management and tracking app with a free plan provides seamless time tracking and reporting designed for freelancers in mind. It has unlimited tracking records, projects, clients, tags, reporting and more. And [Toggl Plan](https://toggl.com/plan/) 为独立开发者提供免费计划的任务计划，具有无限的任务、里程碑和时间表.


## Storage and Media Processing

   * [borgbase.com](https://www.borgbase.com/) — Simple and secure offsite backup hosting for Borg Backup. 10 GB free backup space and 2 repositories.
   * [icedrive.net](https://www.icedrive.net/) - Simple cloud storage service. 10 GB free storage
   * [sync.com](https://www.sync.com/)  - 端到端的云存储服务.  5 GB 免费存储空间
   * [pcloud.com](https://www.pcloud.com/) <i>- Cloud storage service.</i> <b>- 云存储服务。</b> <i>Up to 10 GB free storage</i><b>高达 10 GB 的免费存储空间</b>
   * [sirv.com](https://sirv.com/)  — 具有动态图像优化和调整大小的智能图像 CDN. 免费套餐包括 500 MB 的存储空间和 2 GB 的带宽.
   * [image4.io](https://image4.io/)  — 带有 SDK、集成和迁移工具的网站和应用程序的图像上传、强大的操作、存储和交付. 免费套餐包括 25 个积分.  1 个积分等于 1 GB 的 CDN 使用量、1 GB 的存储空间或 1000 个图像转换.
   * [cloudimage.com](https://cloudimage.com/)  — 全面的图像优化和 CDN 服务，在全球拥有 1500 多个入网点. 多种图像缩放、压缩、水印功能. 用于响应式图像、360 度图像制作和图像编辑的开源插件. 免费的月度计划，包含 25GB 的 CDN 流量和 25GB 的缓存存储和无限转换.
   * [cloudinary.com](https://cloudinary.com/)  — 用于网站和应用程序的图像上传、强大的操作、存储和交付，以及用于 Ruby、Python、Java、PHP、Objective-C 等的库. 免费套餐包括 25 个每月积分.  1 个积分等于 1,000 个图像转换、1 GB 的存储空间或 1 GB 的 CDN 使用量.
   * [easyDB.io](https://easydb.io/) — one-click, hosted database provider. They provide a database for the programming language of your choice for development purposes. The DB is ephemeral and will be deleted after 24 or 72 hours on the free tier.
   * [embed.ly](https://embed.ly/) — Provides APIs for embedding media in a webpage, responsive image scaling, extracting elements from a webpage. Free for up to 5,000 URLs/month at 15 requests/second
   * [filestack.com](https://www.filestack.com/) — File picker, transform and deliver, free for 250 files, 500 transformations and 3 GB bandwidth
   * [gumlet.com](https://www.gumlet.com/)  — 图像调整大小即服务. 它还优化图像并通过 CDN 执行交付. 免费套餐包括 1 GB 带宽和 1 年内每月不限次数的图像处理.
   * [image-charts.com](https://www.image-charts.com/) — Unlimited image chart generation with a watermark
   * [imgen](https://www.jitbit.com/imgen/) - Free unlimited social cover image generation API, no watermark
   * [jsonbin.io](https://jsonbin.io/) — 免费的 JSON 数据存储服务，非常适合小型 Web 应用程序、网站、移动应用程序.
   * [kraken.io](https://kraken.io/) — Image optimization for website performance as a service, free plan up to 1 MB file size
   * [npoint.io](https://www.npoint.io/) — 具有协作模式编辑的 JSON 存储
   * [otixo.com](https://www.otixo.com/)  — 从一处加密、共享、复制和移动您的所有云存储文件. 基本计划提供最大 250 MB 的无限文件传输. 文件大小并允许 5 个加密文件
   * [packagecloud.io](https://packagecloud.io/) — Hosted Package Repositories for YUM, APT, RubyGem and PyPI.  Limited free plans, open source plans available via request
   * [piio.co](https://piio.co/)  — 每个网站的响应式图像优化和交付. 开发人员和个人网站的免费计划. 包括开箱即用的免费 CDN、WebP 和延迟加载.
   * [Pinata IPFS](https://pinata.cloud)  — Pinata 是在 IPFS 上上传和管理文件的最简单方法. 我们友好的用户界面与我们的 IPFS API 相结合，使 Pinata 成为平台、创建者和收集者最简单的 IPFS 固定服务.  1 GB 免费存储以及对 API 的访问.
   * [placeholder.com](https://placeholder.com/) — 快速简单的图像占位符服务
   * [placekitten.com](https://placekitten.com/) — 一种快速简单的服务，用于获取小猫的照片以用作占位符
   * [plot.ly](https://plot.ly/) — Graph and share your data. Free tier includes unlimited public files and 10 private files
   * [podio.com](https://podio.com/) — 您可以与最多五人的团队一起使用 Podio，并试用基本计划的功能，但用户管理除外
   * [QuickChart](https://quickchart.io) — 生成可嵌入的图像图表、图形和二维码
   * [redbooth.com](https://redbooth.com) — P2P 文件同步，最多 2 位用户免费
   * [Skynet](https://siasky.net) — 一种开放协议，用于在去中心化网络上托管数据和网络应用程序，使用 [Sia](https://sia.tech/). Free tier provides storage upto 100GB.
   * [Storj](https://storj.io) — Decentralised Private Cloud Storage for Apps and Developers. Free plan provides 3 Projects, 50 GB storage per project/month , 50 GB bandwidth per project/month.
   * [tinypng.com](https://tinypng.com/) — 用于压缩和调整 PNG 和 JPEG 图像大小的 API，每月免费提供 500 次压缩
   * [transloadit.com](https://transloadit.com/)  — 处理文件上传和视频、音频、图像、文档的编码. 通过 GitHub 学生开发包免费为开源、慈善机构和学生提供. 商业应用程序可免费获得 2 GB 用于试驾
   * [twicpics.com](https://www.twicpics.com)  - 响应式图像即服务. 它提供图像 CDN、媒体处理 API 和前端库来自动优化图像. 该服务每月最多免费提供 3GB 流量.
   * [uploadcare.com](https://uploadcare.com/hub/developers/) — Uploadcare provides media pipeline  with ultimate toolkit based on cutting-edge algorithms. All features are available for developers absolutely for free: File Uploading API and UI, Image CDN and Origin Services, Adaptive Delivery and Smart Compression. Limit free tier has 3000 uploads, 3 GB traffic and 3 GB storage.
   * [imagekit.io](https://imagekit.io) – Image CDN with automatic optimization, real-time transformation, and storage that you can integrate with existing setup in minutes. Free plan includes up to 20GB bandwidth per month.
   * [internxt.com](https://internxt.com)  – Internxt Drive 是一种基于绝对隐私和毫不妥协的安全性的零知识文件存储服务. 注册并永久免费获得 2 GB！
   * [degoo.com](https://degoo.com/) – AI based cloud storage with free up to 100 Gb, 5 devices, 500 Gb referral bonus (365 days account inactivity).



## Design and UI

  * [AllTheFreeStock](https://allthefreestock.com) - a curated list of free stock images, audio and videos.
  * [Ant Design Landing Page](https://landing.ant.design/) - Ant Design Landing Page provides a template built by Ant Motion's motion components. It has a rich homepage template, downloads the template code package, and can be used quickly. You can also use the editor to quickly build your own dedicated page.
  * [Backlight](https://backlight.dev/) — Backlight 以开发人员和设计师之间的协作为核心，是一个非常完整的编码平台，团队可以在其中构建、记录、发布、扩展和维护设计系统.免费计划允许多达 3 位编辑在一个设计系统上工作，且查看者不受限制.
  * [BoxySVG](https://boxy-svg.com/app) — 一个可免费安装的 Web 应用程序，用于绘制 SVG 并以 svg、png、jpeg 和其他格式导出.
  * [clevebrush.com](https://www.cleverbrush.com/) — 免费的图形设计/照片拼贴应用程序，他们还提供将其作为组件的付费集成.
  * [cloudconvert.com](https://cloudconvert.com/) — Convert anything to anything. 208 supported formats including videos to gif.
  * [CodeMyUI](https://codemyui.com) - Handpicked collection of Web Design & UI Inspiration with Code Snippets.
  * [coolors](https://coolors.co/)  - 调色板生成器. 自由.
  * [designer.io](https://www.designer.io/) — Design tool for UI, illustrations and more. Has a native app. Free.
  * [figma.com](https://www.figma.com) — Online, collaborative design tool for teams; free tier includes unlimited files and viewers with a max of 2 editors and 3 projects.
  * [framer.com](https://www.framer.com/) - Framer helps you iterate and animate interface ideas for your next app, website, or product—starting with powerful layouts. For anyone validating Framer as a professional prototyping tool: unlimited viewers, up to 2 editors, up to 3 projects.
  * [Gradientos](https://www.gradientos.app) - 使选择渐变变得快速而简单.
  * [Icon Horse](https://icon.horse) – Get the highest resolution favicon for any website from our simple API.
  * [Icons8](https://icons8.com) — Icons, illustrations, photos, music, and design tools. Free Plan offers Limited formats in lower resolution. Link to Icons8 when you use our assets.
  * [imagebin.ca](https://imagebin.ca/) — 用于图像的 Pastebin.
  * [Invision App](https://www.invisionapp.com)  - UI 设计和原型制作工具. 桌面和网络应用程序可用. 免费使用 1 个活动原型.
  * [landen.co](https://www.landen.co) — Generate, edit and publish beautiful websites and landing pages for your startup. All without code. Free tier allows you to have one website, fully customizable and published on the web.
  * [lensdump.com](https://lensdump.com/) - 免费云图像托管.
  * [Lorem Picsum](https://picsum.photos/)  - 免费工具，易于使用的时尚占位符. 只需在我们的 URL 后添加您想要的图像尺寸（宽度和高度），您就会得到一张随机图像.
  * [LottieFiles](https://lottiefiles.com/) - The world’s largest online platform for the world’s smallest animation format for designers, developers, and more. Access Lottie animation tools and plugins for Android, iOS, and Web.
  * [MagicPattern](https://www.magicpattern.design/tools) — 用于渐变、图案和 blob 的 CSS 和 SVG 背景生成器和工具的集合.
  * [marvelapp.com](https://marvelapp.com/) — Design, prototyping and collaboration, free plan limited to one user and one project.
  * [Mindmup.com](https://www.mindmup.com/) — Unlimited mind maps for free, and store them in the cloud. Your mind maps are available everywhere, instantly, from any device.
  * [Mockplus iDoc](https://www.mockplus.com/idoc) - Mockplus iDoc is a powerful design collaboration & handoff tool. Free Plan includes 3 users and 5 projects with all features available.
  * [mockupmark.com](https://mockupmark.com/create/free) — Create realistic t-shirt and clothing mockups for social media and E-commerce, 40 free mockups.
  * [Octopus.do](https://octopus.do) — Visual sitemap builder. Build your website structure in real-time and rapidly share it to collaborate with your team or clients.
  * [Pencil](https://github.com/evolus/pencil) - Open source design tool using Electron.
  * [Penpot](https://penpot.app)  - 基于 Web 的开源设计和原型制作工具. 支持 SVG. 完全免费.
  * [pexels.com](https://www.pexels.com/)  - 用于商业用途的免费库存照片. 具有免费的 API，可让您按关键字搜索照片.
  * [photopea.com](https://www.photopea.com) — A Free, Advanced online design editor with Adobe Photoshop UI supporting PSD, XCF & Sketch formats (Adobe Photoshop, Gimp and Sketch App).
  * [pixlr.com](https://pixlr.com/) — 商业级别的免费在线浏览器编辑器.
  * [Plasmic](https://www.plasmic.app/)  - 一个快速、易于使用、功能强大的网页设计工具和页面构建器，可集成到您的代码库中. 构建响应式页面或复杂组件； 可选用代码扩展； 并发布到生产站点和应用程序.
  * [Pravatar](https://pravatar.cc/) - Generate random/placeholder fake avatar, which url can be directly hotlinked in your web/app.
  * [Proto.io](https://www.proto.io) - Create fully interactive UI prototypes without coding. Free tier available when free trial ends. Free tier includes: 1 user, 1 project, 5 prototypes, 100MB online storage and preview in proto.io app.
  * [resizeappicon.com](https://resizeappicon.com/) — A simple service to resize and manage your app icons.
  * [Rive](https://rive.app)  — 创建精美的动画并将其发送到任何平台. 个人永久免费. 该服务是一个编辑器，它也在其服务器上托管所有图形. 它们还为许多平台提供运行时以运行使用 Rive 制作的图形.
  * [smartmockups.com](https://smartmockups.com/) — Create product mockups, 200 free mockups.
  * [tabler-icons.io](https://tabler-icons.io/) — Over 1500 free copy and paste SVG editable icons.
  * [UI Avatars](https://ui-avatars.com/)  - 生成带有姓名首字母的头像. 哪些网址可以直接在您的网络/应用程序中进行热链接. 支持通过 url 配置参数.
  * [unDraw](https://undraw.co/) - 不断更新的精美 svg 图像集合，您可以完全免费使用，无需署名.
  * [unsplash.com](https://unsplash.com/) - 用于商业和非商业目的的免费库存照片（随心所欲地做许可证）.
  * [vectr.com](https://vectr.com/) — 适用于 Web + 桌面的免费设计应用程序.
  * [walkme.com](https://www.walkme.com/) — 企业级指导和参与平台，免费计划 3 步走，最多 5 步/步.
  * [Webflow](https://webflow.com)  - 具有动画和网站托管的所见即所得网站构建器.  2个项目免费.
  * [Updrafts.app](https://updrafts.app)  - 所见即所得网站构建器，用于基于 tailwindcss 的设计. 免费用于非商业用途.
  * [whimsical.com](https://whimsical.com/) - Collaborative flowcharts, wireframes, sticky notes and mind maps. Create up to 4 free boards.
  * [Zeplin](https://zeplin.io/) — Designer and developer collaboration platform. Show designs, assets and styleguides. Free for 1 project.
  * [Pixelixe](https://pixelixe.com/) — 在线创建和编辑引人入胜且独特的图形和图像.
  * [Responsively App](https://responsively.app) - 一个免费的开发工具，用于更快、更精确的响应式 Web 应用程序开发.
  * [SceneLab](https://scenelab.io) - Online mockup graphics editor with an ever-expanding collection of free design templates
  * [xLayers](https://xlayers.dev) - Preview and convert Sketch design files into Angular, React, Vue, LitElement, Stencil, Xamarin and more (free and open source at https://github.com/xlayers/xlayers)
  * [Grapedrop](https://grapedrop.com/)  — 基于 GrapesJS 框架的响应式、强大、SEO 优化的网页构建器. 前 5 页免费，无限自定义域，所有功能和简单使用.
  * [Mastershot](https://mastershot.app)  - 完全免费的基于浏览器的视频编辑器. 无水印，高达 1080p 的导出选项.
  * [Unicorn Platform](https://unicornplatform.com/) - Effortless landing page builder with hosting. 1 website for free.
  * [react-favicon.com](https://react-favicon.com/) - 使用 React 和 JSX 使用任何字体和图标库为您的网站生成 Favicon.


## Design Inspiration

  * [awwwards.](https://www.awwwards.com/) - [Top websites] A showcases of all the best designed websites (voted on by designers).
  * [Behance](https://www.behance.net/) - [Desing showcase] A place where designers showcase their work. Filterable with categories for UI/UX projects.
  * [dribbble](https://dribbble.com/) - [Design showcase] Unique design inspiration, generally not from real applications.
  * [Mobbin](https://mobbin.design/) - [Mobile screenshots] Save hours of UI & UX research with our library of 50,000+ fully searchable mobile app screenshots.
  * [Mobile Patterns](https://www.mobile-patterns.com/) - [Mobile screenshots] A design inspirational library featuring finest UI UX Patterns (iOS and Android) for designers, developers, and product makers to reference.
  * [Screenlane](https://screenlane.com/) - [Mobile screenshots] Get inspired and keep up with the latest web & mobile app UI design trends. Filterable by pattern and app.
  * [scrnshts](https://scrnshts.club/) - [手机截图] 精选的最好的应用商店设计截图集合.
  * [UI Garage](https://uigarage.net/) - [Mobile and web screenshots] Daily UI inspiration & patterns for designers, developers to find inspiration, tools and the best resources for your project.


## Data Visualization on Maps

   * [IP Geolocation](https://ipgeolocation.io/) — Free DEVELOPER plan available with 30K requests/month.
   * [carto.com](https://carto.com/) — Create maps and geospatial APIs from your data and public data.
   * [developers.arcgis.com](https://developers.arcgis.com)  — 用于跨网络、桌面和移动设备的地图、地理空间数据存储、分析、地理编码、路由等的 API 和 SDK.  2,000,000 个免费底图切片、20,000 个非存储地理编码、20,000 条简单路线、5,000 次行驶时间计算、每月 5GB 免费切片+数据存储.
   * [Foursquare](https://developer.foursquare.com/) - Location discovery, venue search, and context-aware content from Places API and Pilgrim SDK.
   * [geoapify.com](https://www.geoapify.com/) - Vector and raster map tiles, geocoding, places, routing, isolines APIs. 3000 free requests / day.
   * [geocod.io](https://www.geocod.io/) — Geocoding via API or CSV Upload. 2,500 free queries/day.
   * [geocodify.com](https://geocodify.com/) — Geocoding and Geoparsing via API or CSV Upload. 10k free queries/month.
   * [giscloud.com](https://www.giscloud.com/) — 在线可视化、分析和共享地理数据.
   * [gogeo.io](https://gogeo.io/) — 具有易于使用的 API 和对大数据的支持的地图和地理空间服务.
   * [graphhopper.com](https://www.graphhopper.com/) A free package for developers is offered for Routing, Route Optimization, Distance Matrix, Geocoding, Map Matching.
   * [here](https://developer.here.com/) — APIs and SDKs for maps and location-aware apps. 250k transactions/month for free.
   * [mapbox.com](https://www.mapbox.com/) — Maps, geospatial services and SDKs for displaying map data.
   * [maptiler.com](https://www.maptiler.com/cloud/) — Vector maps, map services and SDKs for map visualisation. Free vector tiles with weekly update and four map styles.
   * [opencagedata.com](https://opencagedata.com) — Geocoding API that aggregates OpenStreetMap and other open geo sources. 2,500 free queries/day.
   * [osmnames](https://osmnames.org/) — 地理编码，搜索结果按相关维基百科页面的受欢迎程度排名.
   * [positionstack](https://positionstack.com/) - Free geocoding for global places and coordinates. 25.000 Requests per month for personal use.
   * [stadiamaps.com](https://stadiamaps.com/) — Map tiles, routing, navigation, and other geospatial APIs. 2,500 free map views and API requests / day for non-commercial usage and testing.
   * [maps.stamen.com](http://maps.stamen.com/) - 免费地图瓷砖和瓷砖托管.
   * [GeocodeAPI](https://geocodeapi.io)  - 地理编码 API：基于 Pelias 的地址到坐标转换和地理解析. 通过 CSV 进行批量地理编码.  350000 个免费请求/月.
   * [Geokeo api](https://geokeo.com) - Geocoding api with language correction and more. Worldwide coverage. 2,500 free daily queries


## Package Build System

   * [build.opensuse.org](https://build.opensuse.org/) — 用于多个发行版（SUSE、EL、Fedora、Debian 等）的软件包构建服务.
   * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — Fedora 和 EL 的基于 Mock 的 RPM 构建服务.
   * [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu 和 Debian 构建服务.


## IDE and Code Editing

   * [3v4l](https://3v4l.org/) - 免费在线 PHP shell 和代码段共享站点，以 300 多个 PHP 版本运行您的代码
   * [Android Studio](https://d.android.com/studio) — Android Studio provides the fastest tools for building apps on every type of Android device. Open Source IDE, free for everyone and the best to develop Android apps. Available for Windows,Mac,Linux and even ChromeOS!
   * [Apache Netbeans](https://netbeans.apache.org/) — Development Environment, Tooling Platform and Application Framework.
   * [apiary.io](https://apiary.io/) — 具有即时 API 模拟和生成文档的协作设计 API（无限的 API 蓝图和无限的用户免费提供一个管理员帐户和托管文档）.
   * [Atom](https://atom.io/) - Atom is a hackable text editor built on Electron.
   * [Binder](https://mybinder.org/)  - 将 Git 存储库变成交互式笔记本的集合. 这是一项免费的公共服务.
   * [BlueJ](https://bluej.org) — A free Java Development Environment designed for beginners, used by millions worldwide. Powered by Oracle & simple GUI to help beginners.
   * [Bootify.io](https://bootify.io/) - Spring Boot app generator with custom database and REST API.
   * [cacher.io](https://www.cacher.io) — Code snippet organizer with labels and support for 100+ programming languages.
   * [Code::Blocks](https://codeblocks.org)  — 免费的 Fortran 和 C/C++ IDE. 开源并在 Windows、macOS 和 Linux 上运行.
   * [codiga.io](https://codiga.io/)  — 编码助手，可让您直接在 IDE 中搜索、定义和重用代码片段. 个人和小型组织免费.
   * [codesnip.com.br](https://codesnip.com.br) — Simple code snippets manager with categories, search and tags. free and unlimited.
   * [cocalc.com](https://cocalc.com/)  —（以前位于 cloud.sagemath.com 的 SageMathCloud）— 云中的协作计算. 浏览器访问具有内置协作功能的完整 Ubuntu，以及许多用于数学、科学、数据科学的免费软件，预装：Python、LaTeX、Jupyter Notebooks、SageMath、scikitlearn 等.
   * [ide.cs50.io](https://ide.cs50.io/) - A free IDE powered by AWS Cloud9 by Harvard University.
   * [codepen.io](https://codepen.io/) — CodePen is a playground for the front end side of the web.
   * [codesandbox.io](https://codesandbox.io/) — React、Vue、Angular、Preact 等的在线游乐场.
   * [Components.studio](https://webcomponents.dev/) - 单独编写组件，在故事中可视化它们，测试它们并在 npm 上发布它们.
   * [Eclipse Che](https://www.eclipse.org/che/) - Web based and Kubernetes-Native IDE for Developer Teams with multi-language support. Open Source and community driven. A online instance hosted by Red Hat is available at [workspaces.openshift.com](https://workspaces.openshift.com/).
   * [fakejson.com](https://fakejson.com/) — FakeJSON helps you quickly generate fake data using its API. Make an API request describing what you want and how you want it. The API returns it all in JSON. Speed up the go to market process for ideas and fake it till you make it.
   * [gitpod.io](https://www.gitpod.io)  — 用于 GitHub 项目的即时、可编写代码的开发环境. 开源免费.
   * [ide.goorm.io](https://ide.goorm.io)  goormIDE 是完整的云端 IDE. 多语言支持、基于 linux 的容器（通过功能齐全的基于 Web 的终端）、端口转发、自定义 url、实时协作和聊天、共享链接、Git/Subversion 支持. 还有更多功能（免费层包括每个容器 1GB RAM 和 10GB 存储，5 个容器插槽）.
   * [JDoodle](https://www.jdoodle.com) — Online compiler and editor for more than 60 programming languages with a free plan for REST API code compiling up to 200 credits per day.
   * [jetbrains.com](https://jetbrains.com/products.html) — 生产力工具、IDE 和部署工具（又名 [IntelliJ IDEA](https://www.jetbrains.com/idea/), [PyCharm](https://www.jetbrains.com/pycharm/), etc). Free license for students, teachers, Open Source and user groups.
   * [jsbin.com](https://jsbin.com) — JS Bin 是另一个前端 Web（HTML、CSS 和 JavaScript.也支持 Markdown、Jade 和 Sass）的游乐场和代码共享站点.
   * [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle is a playground and code sharing site of front end web, support collaboration as well.
   * [JSONPlaceholder](http://jsonplaceholder.typicode.com/) Some REST API endpoints that return some fake data in JSON format. The source code is also available if you would like to run the server locally.
   * [Katacoda](https://katacoda.com) — Interactive learning and training platform for software engineers helping developers learn and companies increase adoption.
   * [Lazarus](https://www.lazarus-ide.org/) — Lazarus 是一个兼容 Delphi 的跨平台 IDE，用于快速应用程序开发.
   * [micro-jaymock](https://micro-jaymock.now.sh/) - 用于生成虚假 JSON 数据的微型 API 模拟微服务.
   * [mockable.io](https://www.mockable.io/) — Mockable is a simple configurable service to mock out RESTful API or SOAP web-services. This online service allows you to quickly define REST API or SOAP endpoints and have them return JSON or XML data.
   * [mockaroo](https://mockaroo.com/)  — Mockaroo 让您可以生成 CSV、JSON、SQL 和 Excel 格式的真实测试数据. 您还可以为后端 API 创建模拟.
   * [Mocklets](https://mocklets.com) - 基于 HTTP 的模拟 API 模拟器，有助于模拟 API 以实现更快的并行开发和更全面的测试，并提供终身免费层.
   * [Paiza](https://paiza.cloud/en/) — Develop Web apps in Browser without having the need to setup anything. Free Plan offers 1 server with 24 hours lifetime and 4 hours running time per day with 2 CPU cores, 2 GB RAM and 1 GB storage.
   * [Prepros](https://prepros.io/) - Prepros can compile Sass, Less, Stylus, Pug/Jade, Haml, Slim, CoffeeScript and TypeScript out of the box, reloads your browsers and makes it really easy to develop & test your websites so you can focus on making them perfect. You can also add your own tools with just a few clicks.
   * [Replit](https://replit.com/) — A cloud coding environment for various program languages.
   * [SoloLearn](https://code.sololearn.com) — A cloud programming playground well-suited for running code snippets. Supports various programming languages. No registration required for running code but required when you need to save code on their platform. Also offers free courses for begginers and intermediate level coders.
   * [stackblitz.com](https://stackblitz.com/)  — 用于创建、编辑和部署全栈应用程序的在线/云代码 IDE. 支持任何流行的基于 NodeJs 的前端和后端框架. 创建新项目的短链接： [https://node.new](https://node.new).
   * [Visual Studio Code](https://code.visualstudio.com/) - Code editor redefined and optimized for building and debugging modern web and cloud applications. Developed by Microsoft for Windows, macOS and Linux.
   * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — Fully-featured IDE with thousands of extensions, cross-platform app development (Microsoft extensions available for download for iOS and Android), desktop, web and cloud development, multi-language support (C#, C++, JavaScript, Python, PHP and more).
   * [VSCodium](https://vscodium.com/) - 社区驱动，无遥测/跟踪，微软编辑器 VSCode 的免费许可二进制分发
   * [wakatime.com](https://wakatime.com/) — Quantified self-metrics about your coding activity, using text editor plugins, limited plan for free.
   * [WebComponents.dev](https://webcomponents.dev/) — In-browser IDE to code web components in isolation with 58 templates available, supporting stories and tests.


## Analytics, Events and Statistics

   * [Statvoo Analytics](https://analytics.statvoo.com/) — Forever FREE Customer Analytics for ALL your websites, with Unlimited Events per month
   * [Avo](https://avo.app/) — Simplified analytics release workflow. Single-source-of-truth tracking plan, type safe analytics tracking library, in-app debuggers, data observability to catch all data issues before you release. Free for 2 workspace members and 1 hour data observability lookback.
   * [Branch](https://branch.io)  — 移动分析平台. 免费套餐为多达 10K 移动应用用户提供深度链接和其他服务.
   * [Clicky](https://clicky.com)  — 网站分析平台.  1 个网站的免费计划，包含 3000 次浏览分析.
   * [Databox](https://databox.com)  — 通过结合其他分析和 BI 平台获得业务洞察力和分析. 免费计划提供 3 个用户、仪表板和数据源.  11M 历史数据记录.
   * [indicative.com](https://indicative.com/)  — 客户分析平台，可优化客户参与度、提高转化率并提高保留率. 每月最多释放 5000 万个事件.
   * [Panelbear.com](https://panelbear.com/) — 极快且私密的免费套餐，包括每月 5,000 次网页浏览量，可用于无限网站
   * [Hitsteps.com](https://hitsteps.com/) — 2,000 pageviews per month for 1 website
   * [amplitude.com](https://amplitude.com/) — 1 million monthly events, up to 2 apps
   * [Flagsmith](https://www.molasses.app)  - 自信地发布功能； 跨 Web、移动和服务器端应用程序管理功能标志. 使用我们的托管 API，部署到您自己的私有云，或在本地运行
   * [GoatCounter](https://www.goatcounter.com/)  — GoatCounter 是一个开源网络分析平台，可作为托管服务（非商业用途免费）或自托管应用程序提供. 它旨在提供易于使用且有意义的隐私友好型网络分析，以替代 Google Analytics 或 Matomo. 免费套餐用于非商业用途，包括无限数量的网站、6 个月的数据保留期和 10 万次/月的网页浏览量.
   * [Google Analytics](https://analytics.google.com/) — Google Analytics
   * [Expensify](https://www.expensify.com/) — Expense reporting, free personal reporting approval workflow
   * [getinsights.io](https://getinsights.io) - 以隐私为重点的无 cookie 分析，每月最多可免费处理 5k 个事件.
   * [heap.io](https://heap.io) — Automatically captures every user action in iOS or web apps. Free for up to 5,000 visits/month
   * [Hotjar](https://hotjar.com)  — 网站分析和报告. 免费计划允许每天 2000 次浏览量. 每天 100 个快照（最大容量：300）.  3 个快照热图，可存储 365 天. 无限的团队成员.
   * [Keen](https://keen.io/) — Custom Analytics for data collection, analysis and visualization. 50,000 events/month free
   * [Yandex.Metrica](https://metrica.yandex.com/) — 无限制的免费分析
   * [Mixpanel](https://mixpanel.com/) — 100,000 monthly tracked users, unlimited data history and seats, US or EU data residency
   * [Moesif](https://www.moesif.com)  — REST 和 GraphQL 的 API 分析.  （每月最多免费调用 500,000 次 API 调用）
   * [Molasses](https://www.molasses.app)  - 强大的功能标志和 A/B 测试. 最多释放 3 个环境，每个环境有 5 个功能标志.
   * [optimizely.com](https://www.optimizely.com) — A/B 测试解决方案、免费入门计划、1 个网站、1 个 iOS 和 1 个 Android 应用
   * [Microsoft PowerBI](https://powerbi.com) — Business Insights & Analytics by Microsoft. Free Plan offers limited use with 1 Million User licenses.
   * [quantcast.com](https://www.quantcast.com/products/measure-audience-insights/) — 无限制的免费分析
   * [sematext.com](https://sematext.com/cloud/) — 每月最多 50,000 次免费操作、1 天数据保留、无限制的仪表板、用户等.
   * [Similar Web](https://similarweb.com)  — 网络和移动应用分析. 免费计划提供每个指标 5 个结果、1 个月的移动应用数据和 3 个月的网站数据.
   * [StatCounter](https://statcounter.com/)  — 网站查看者分析. 用于分析 500 位最近访问者的免费计划.
   * [Tableau Developer Program](https://www.tableau.com/developer) — Innovate, create, and make Tableau work perfectly for your organization. Free developer program gives a personal development sandbox license for Tableau Online. The version is the latest pre-release version so Data Devs can test each & every feature of this superb platform.
   * [usabilityhub.com](https://usabilityhub.com/)  — 在真人身上测试设计和模型，跟踪访客. 一位用户免费，无限制测试
   * [woopra.com](https://www.woopra.com/) — Free user analytics platform for 500K actions, 90 day data retention, 30+ one click integration.
   * [counter.dev](https://counter.dev)  — 网络分析变得简单，因此对隐私友好. 免费或通过捐赠支付您想要的东西.
   * [PostHog](https://posthog.com) - 完整的产品分析套件，每月最多可跟踪 100 万个事件


## Visitor Session Recording

   * [Visualime.com](https://www.visualime.com/) — 免费且无限制的会话录音，无流量限制
   * [Reactflow.com](https://www.reactflow.com/) — Per site: 1,000 pages views/day, 3 heatmaps, 3 widgets, free bug tracking
   * [LogRocket.com](https://www.logrocket.com) - 每月 1,000 次会话，保留 30 天，错误跟踪，实时模式
   * [FullStory.com](https://www.fullstory.com) — 1,000 sessions/month with 1 month data retention and 3 user seats. More information [here](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition).
   * [hotjar.com](https://www.hotjar.com/) — 每个站点：每天 2,000 次页面浏览量，3 个热图，存储 3 个月的数据，...
   * [inspectlet.com](https://www.inspectlet.com/) — 1 个网站每月免费 2,500 次会话
   * [livesession.io](https://livesession.io/) — 5,000 sessions/month free for 1 website
   * [Microsoft Clarity](https://clarity.microsoft.com/) - Session recording completely free with "no traffic limits", no project limits, and no sampling
   * [mouseflow.com](https://mouseflow.com/) — 500 sessions/month free for 1 website
   * [mousestats.com](https://www.mousestats.com/) — 1 个网站每月免费 100 次会话
   * [smartlook.com](https://www.smartlook.com/) — Web 和移动应用程序的免费包（1500 个会话/月）、3 个热图、1 个漏斗、1 个月的数据历史记录
   * [usersurge.com](https://www.usersurge.com/) — 个人每月 25 万次会话.
   * [howuku.com](https://howuku.com) — Track user interaction, engagement, and event. Free for up to 5,000 visits/month
   * [UXtweak.com](https://www.uxtweak.com/) — Record and watch how visitors use your web site or app. Free unlimited time for small projects


## International Mobile Number Verification API and SDK

  * [Cognalys](https://cognalys.com/) — Freemium mobile number verification through an innovative and reliable method than using SMS gateway. Free 10 tries and 15 verifications/day
  * [numverify](https://numverify.com/)  — 全球电话号码验证和查询 JSON API.  250 个 API 请求/月
  * [veriphone](https://veriphone.io/)  — 免费、快速、可靠的 JSON API 中的全球电话号码验证.  1000 个请求/月


## Payment and Billing Integration

  * [CurrencyFreaks](https://currencyfreaks.com/) — Provides current and historical currency exchange rates. Free DEVELOPER plan available with 1000 requests/month.
  * [CurrencyApi](https://currencyapi.net/)  — 实物和加密货币的实时汇率，以 JSON 和 XML 格式提供. 免费套餐每月提供 1,250 个 API 请求.
  * [currencylayer](https://currencylayer.com/) — Reliable Exchange Rates and Currency Conversion for your Business, 1,000 API requests/month free
  * [currencystack.io](https://currencystack.io/) — Production-ready real-time exchange rates for 154 currencies.
  * [exchangerate-api.com](https://www.exchangerate-api.com)  - 一个易于使用的货币转换 JSON API. 免费套餐，没有请求限制.
  * [FraudLabsPRO](https://www.fraudlabspro.com)  — 帮助商家防止支付欺诈和退款. 免费的微型计划可用于每月 500 次查询.
  * [MailPopin](https://mailpop.in) - Get the most of your Stripe notifications with contextualized information.
  * [Nami ML](https://www.namiml.com/)  - 适用于 iOS 和 Android 上的应用内购买和订阅的完整平台，包括无代码付费墙、CRM 和分析. 免费提供所有基本功能以运行 IAP 业务.
  * [RevenueCat](https://www.revenuecat.com/) — Hosted backend for in-app purchases and subscriptions (iOS and Android). Free up to $10k/mo in tracked revenue.
  * [vatlayer](https://vatlayer.com/) — 即时增值税号验证和欧盟增值税率 API，每月免费 100 个 API 请求
  * [Freecurrencyapi.net](https://freecurrencyapi.net/)  — 免费的货币换算和汇率数据API.  10 个请求/小时，没有 API 密钥，当您免费注册时，每月 50 000 个请求.


## Docker Related

  * [canister.io](https://canister.io/) — 20 free private repositories for developers, 30 free private repositories for teams to build and store Docker images
  * [Container Registry Service](https://container-registry.com/) - Harbor based Container Management Solution. Free tier offers 1 GB storage for private repositories.
  * [Docker Hub](https://hub.docker.com) — One free private repository and unlimited public repositories to build and store Docker images
  * [Play with Docker](https://labs.play-with-docker.com/) — A simple, interactive and fun playground to learn Docker.
  * [quay.io](https://quay.io/) — 使用无限的免费公共存储库构建和存储容器镜像
  * [TreeScale.com](https://treescale.com/)  — 使用组权限托管和管理容器镜像. 免费套餐为私有存储库提供 1 GB 存储空间.
  * [Platform9](https://platform9.com/) - Managed Kubernetes plane. Free plan offers management capabilities up to 3 clusters & 20 nodes. Note: you must provide cluster infrastructure by yourself.


## Vagrant Related

  * [Vagrant Cloud](https://app.vagrantup.com)  - HashiCorp 流浪云. 流浪盒托管.
  * [Vagrantbox.es](https://www.vagrantbox.es/) — 另一种公共盒子索引


## Dev Blogging Sites

  * [BearBlog](https://bearblog.dev/) - Minimalist, and Markdown powered blog and website builder.
  * [Dev.to](https://dev.to/) - Where programmers share ideas and help each other grow.
  * [Hashnode](https://hashnode.com/) — Hassle-free Blogging Software for Developers!.
  * [Medium](https://medium.com/) — 更聪明地了解对您而言重要的事情.


## Commenting Platforms
  * [Staticman](https://staticman.net/) - Staticman 是一个 Node.js 应用程序，它接收用户生成的内容并将其作为数据文件上传到 GitHub 和/或 GitLab 存储库，使用拉取请求.
  * [GraphComment](https://graphcomment.com/) - GraphComment is a comments platform that helps you build an active community from website’s audience.
  * [Utterances](https://utteranc.es/)  - 基于 GitHub 问题构建的轻量级评论小部件. 将 GitHub 问题用于博客评论、wiki 页面等！
  * [Disqus](https://disqus.com/) - Disqus 是一个网络社区平台，被网络上成千上万的网站使用.


## Screenshot APIs

  * [24browser.com](https://www.24browser.com) – 使用强大的 API 大规模捕获渲染精美的网站屏幕截图.
  * [ApiFlash](https://apiflash.com)  — 基于 Aws Lambda 和 Chrome 的屏幕截图 API. 处理整页，捕捉时间，视口尺寸，......
  * [microlink.io](https://microlink.io/) – It turns any website into data such as metatags normalization, beauty link previews, scraping capabilities or screenshots as a service. 250 reqs/day every day free.
  * [ScreenshotAPI.net](https://screenshotapi.net/) - Screenshot API use one simple API call to generate screenshots of any website. Build to scale and hosted on Google Cloud. Offers 100 free screenshots per month.
  * [screenshotlayer.com](https://screenshotlayer.com/) — Capture highly customizable snapshots of any website. Free 100 snapshots/month
  * [screenshotmachine.com](https://www.screenshotmachine.com/) — 每月捕获 100 个快照，png、gif 和 jpg，包括全长捕获，不仅是主页
  * [PhantomJsCloud](https://PhantomJsCloud.com) — Browser automation and page rendering.  Free Tier offers up to 500 pages/day.  Free Tier since 2017.
  * [Webshrinker.com](https://webshrinker.com)  — Web Shrinker 提供网站截图和领域智能 API 服务. 每月免费 100 个请求.


## Browser based hardware emulation written in Javascript

  * [JsLinux](https://bellard.org/jslinux) — 一个真正快速的 x86 虚拟机，能够运行 Linux 和 Windows 2k.
  * [Jor1k](http://s-macke.github.io/jor1k/demos/main.html) — 一个能够在网络支持下运行 Linux 的 OpenRISC 虚拟机.
  * [v86](https://copy.sh/v86) — a x86 virtual machine capable of running Linux and other OS directly into the browser.


## Privacy Management
  * [Bearer](https://www.bearer.sh/) - Helps implement privacy by design via audits and continuous workflows so that organizations comply with GDPR and other regulations. Free tier is limited to smaller teams and SaaS version only.
  * [Osano](https://www.osano.com/) - Consent management and compliance platform with everything from GDPR representation to cookie banners. Free tier offers basic features.
  * [Iubenda](https://www.iubenda.com/)  - 隐私和 cookie 政策以及同意管理. 免费套餐提供有限的隐私和 cookie 政策以及 cookie 横幅.
  * [Cookiefirst](https://cookiefirst.com/)  - Cookie 横幅、审核和多语言同意管理解决方案. 免费套餐提供一次性扫描和单个横幅.
  * [Ketch](https://www.ketch.com/)  - 同意管理和隐私框架工具. 免费套餐提供大多数功能，但访客人数有限.


## Miscellaneous

  * [Smartcar API](https://smartcar.com) - 用于汽车定位、获取油箱、电池电量、里程表、解锁/锁门等的 API.
  * [Blynk](https://blynk.io)  — 具有 API 的 SaaS，用于控制、构建和评估物联网设备. 包含 5 台设备、免费云和数据存储的免费开发者计划. 移动应用程序也可用.
  * [Bricks Note Calculator](https://free.getbricks.app/) - 带有强大的内置多行计算器的笔记应用程序 (PWA).
  * [Carbon.now.sh](https://carbon.now.sh) - create and share code snippet in an aesthetic screenshot-like image format. Usually used to aesthetically share/show-off code snippet on Twitter or blog posts.
  * [Code Time](https://www.software.com/code-time) - VS Code、Atom、IntelliJ、Sublime Text 等中时间跟踪和编码指标的扩展.
  * [Codepng](https://www.codepng.app) - Create awesome snapshots from your source code that you can share on social media.
  * [ConfigCat](https://configcat.com)  - 跨平台功能标志服务. 适用于所有主要语言的 SDK. 免费计划每月最多 10 个标志、2 个环境、1 个产品和 500 万个请求. 无限用户席位. 学生每月免费获得 100 个标志和 1 亿个请求.
  * [datelist.io](https://datelist.io) - Online booking / appointment scheduling system. Free up to 5 bookings per month, includes 1 calendar
  * [docsapp.io](https://www.docsapp.io/) — Easiest way to publish documentation, free for Open Source
  * [Elementor](https://elementor.com) — WordPress website builder. Free plan available with 40+ Basic Widgets.
  * [Form2Channel](https://form2channel.com)  — 在您的网站上放置一个静态 html 表单，并直接接收提交到 Google 表格、电子邮件、Slack、Telegram 或 Http 的内容. 无需编码.
  * [FOSSA](https://fossa.com/) - Scalable, end-to-end management for third-party code, license compliance and vulnerabilities.
  * [fullcontact.com](https://www.fullcontact.com/developer/pricing/)  — 通过将社交资料添加到您的应用程序中，帮助您的用户更多地了解他们的联系人.  500 次免费 Person API 匹配/月
  * [http2.pro](https://http2.pro) — HTTP/2 protocol readiness test and client HTTP/2 support detection API.
  * [JWT Decoder](https://jwt.ssotools.com/) — Online free tool for decoding JWT(JSON web token) and verifying it's signature.
  * [Base64 decoder/encoder](https://devpal.co/base64-decode/) — Online free tool for decoding & encoding data.
  * [newreleases.io](https://newreleases.io/) - 通过电子邮件、Slack、Telegram、Discord 和自定义 webhook 接收来自 GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM、Node.js Yarn、Ruby Gems、PHP Packagist、.NET NuGet 的新版本通知， Rust Cargo 和 Docker Hub.
  * [PDFMonkey](https://www.pdfmonkey.io/) — Manage PDF templates in a dashboard, call the API with dynamic data, download your PDF. Offers 1000 free documents per month.
  * [QuickType.io](https://quicktype.io/)  - 从 JSON、模式和 GraphQL 快速自动生成模型/类/类型/接口和序列化程序，以便以任何编程语言快速安全地处理数据. 将 JSON 转换为任何语言的华丽、类型安全的代码.
  * [ray.so](https://ray.so/) - 为您的代码片段创建漂亮的图像.
  * [readme.com](https://readme.com/) — Beautiful documentation made easy, free for Open Source.
  * [redirection.io](https://redirection.io/) — 用于管理企业、营销和 SEO 的 HTTP 重定向的 SaaS 工具.
  * [redirect.pizza](https://redirect.pizza/)  - 使用 HTTPS 支持轻松管理重定向. 免费计划包括每月 10 个来源和 100.000 次点击.
  * [ReqBin](https://www.reqbin.com/)  — 在线发布 HTTP 请求. 流行的请求方法包括 GET、POST、PUT、DELETE 和 HEAD. 支持标头和令牌身份验证. 包括用于保存您的请求的基本登录系统.
  * [superfeedr.com](https://superfeedr.com/) — Real-time PubSubHubbub compliant feeds, export, analytics. Free with less customization
  * [SurveyMonkey.com](https://www.surveymonkey.com)  — 创建在线调查. 在线分析结果. 免费计划每次调查仅允许 10 个问题和 100 个回复.
  * [videoinu](https://videoinu.com) — Create and edit screen recordings and other videos online.
  * [RandomKeygen](https://randomkeygen.com/) - A free mobile-friendly tool offers a variety of randomly generated keys and passwords you can use to secure any application, service or device.
  * [Cronhooks](https://cronhooks.io/)  - 用 webhook 替换您的 cron 作业. 在给定的日期时间或重复使用 cron 表达式调用任何 webhook. 免费计划允许 1 个 webhook 计划.
  * [Hook Relay](https://www.hookrelay.dev/)  - 轻松为您的应用添加 webhook 支持：为您完成排队、使用退避重试和日志记录. 免费计划每天有 100 次交付、14 天保留期和 3 个挂钩端点.
  * [Format Express](https://www.format-express.dev) - JSON / XML / SQL 的即时在线格式化程序.


## Remote Desktop Tools

  * [Getscreen.me](https://getscreen.me) —  Free for 2 devices, no limits on the number and duration of sessions
  * [Apache Guacamole™](https://guacamole.apache.org/) — Open source clientless remote desktop gateway


## Other Free Resources

  * [get.localhost.direct](https://get.localhost.direct) — A better *.localhost.direct Wildcard public CA signed SSL cert for localhost development with sub-domain support  
  * [eu.org](https://nic.eu.org) — Free eu.org domain. Request is usually approved in 14 days.
  * [js.org](https://js.org) - Free js.org subdomains for GitHub Pages for the JavaScript community.
  * [pp.ua](https://nic.ua/) — Free pp.ua subdomains.
  * [Framacloud](https://degooglisons-internet.org/en/list/) — A list of Free/Libre Open Source Software and SaaS by the French non-profit [Framasoft](https://framasoft.org/en/).
  * [getawesomeness](https://getawesomeness.herokuapp.com) — 从 GitHub 检索所有令人惊叹的精彩……必看
  * [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) — 面向开发人员的免费和开源软件中心.
  * [GitHub Education](https://education.github.com/pack)  — 为学生收集免费服务. 需要注册.
  * [is-a.dev](https://www.is-a.dev/) — Free `*.is-a.dev` subdomain for developers.
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program)  — 获取构建 Microsoft 365 平台解决方案所需的免费沙盒、工具和其他资源. 订阅期为 90 天 [Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5)  （Windows 除外）这是可更新的. 如果您积极参与开发（使用遥测数据和算法测量），它会被更新.
  * [RedHat for Developers](https://developers.redhat.com) — Free access to Red Hat products including RHEL,OpenShift,CodeReady etc exclusively for developers. Individual plan only. Free e-Books also offered for reference.
  * [smsreceivefree.com](https://smsreceivefree.com/) — 提供免费的临时和一次性电话号码.
  * [simplebackups.io](https://simplebackups.io/) — Backup automation service for servers and databases (MySQL, PostgreSQL, MongoDB) stored directly into cloud storage providers (AWS, DigitalOcean, Backblaze...). Provides free plan for 1 backup.
  * [SnapShooter](https://snapshooter.com/)  — DigitalOcean、AWS、LightSail、Hetzner 和 Exoscale 的备份解决方案，支持将数据库、文件系统和应用程序直接备份到基于 s3 的存储. 为一项资源提供每日备份的免费计划.
  * [thedev.id](https://thedev.id) — A free thedev.id subdomain for developers.
  * [Themeselection](https://themeselection.com/) — Selected high quality, modern design, professional and easy-to-use Free Admin Dashboard Template,
HTML 主题和 UI 工具包可以更快地创建您的应用程序！
  * [Web.Dev](https://web.dev/measure/) — This is a free tool that allows you to see the performance of your website and improve the SEO to get higher rank list in search engines.
  * [SmallDev.tools](https://smalldev.tools/)  — 开发人员的免费工具，允许您编码/解码各种格式、缩小 HTML/CSS/Javascript、美化、生成假/测试真实的 JSON/CSV 和多种其他格式的数据集以及更多功能. 具有令人愉快的界面.
