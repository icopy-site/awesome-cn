<div class="github-widget" data-repo="MartinMiles/Awesome-Sitecore"></div>
## Awesome Sitecore [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/MartinMiles/Awesome-Sitecore/master/sitecore-logo.png" align="right" width="80">](https://sitecore.com)

 &gt; GitHub 上与 Sitecore 相关的项目的精选列表. 请贡献！

 Sitecore 是一个数字平台，可帮助从一个地方管理多个网站. 它提供的营销工具可通过不同设备（CRM、跟踪、POS 等）传递有关客户的信息.  Sitecore 允许创建可通过不同渠道（桌面、移动设备、API、社交媒体等）访问的内容. 该平台设计灵活，具有众多扩展点，可以部署在本地和云端. 下面的列表对 Sitecore 开发人员可以从中受益的可扩展性和部署选项进行了分类.

欢迎贡献. 通过拉取请求添加链接或创建问题以开始讨论.


- [Helix](#helix) 
- [Maintenance](#maintenance) 
- [ORM](#orm) 
- [Security](#security) 
- [SEO](#seo) 
- [Serialization](#serialization) 
- [Sitecore Host](#sitecore-host) 
- [WebApi](#webapi) 

&gt; 请注意，**Awesome Sitecore** 列表仅对您可能受益的有用 GitHub 存储库进行分类和评论. 
>
&gt; 如果您正在寻找更全面的文章、博客文章、视频和问答列表，请参阅 [Sitecore Link](https://Sitecore.Link) 知识库.

## Analytics

- [Sitecore Goal Description](https://github.com/islaytitans/SitecoreGoalDescription) - 在体验配置文件中显示目标描述.
- [Sitecore Goal Conversion Demo](https://github.com/martinrayenglish/GoalConversions.Demo) - 演示如何获取访问者交互期间触发的目标，在会话结束后，可以将这些数据发送到外部系统，以便通过告知营销人员客户和潜在客户在其网站上执行的操作来帮助营销人员.
- [Custom Timeline Eras](https://github.com/coreyasmith/sitecore-custom-timeline-eras) - 演示如何触发结果并将自定义结果显示为 Sitecore 中体验配置文件时间轴上的时代.

## Audit and performance

- [Skillcore.Stats](https://github.com/marek-musielak/Skillcore.Stats) - 收集所有 Sitecore MVC 渲染和 API 调用的详细计时信息.
- [Sitecore.Boost](https://github.com/cardinal252/Sitecore.Boost) - 该存储库包含大量潜在补丁，可用于提高 Sitecore 平台的性能，其中大部分都在 Sitecore 的生产实例中运行.
- [Sitecore.Cleanup](https://github.com/martinrayenglish/Sitecore.Cleanup) - 该模块由 3 个代理组成，它们将监视每个事件队列、发布队列和历史记录表，以确保它们不超过设定的阈值.
- [SitecoreDXG: The Documentation Experience Generator](https://github.com/zkniebel/SitecoreDXG)  - SitecoreUML 系列的 Sitecore 模板架构可视化和文档工具. 利用与 StarUML（SitecoreUML 也基于此）相关的开源 API，SitecoreDXG 支持从任何具有 SitecoreUML 的现有 Sitecore 实例（PaaS 和非 PaaS 均受支持）生成模板数据模型架构图和 HTML 文档Sitecore 服务.
- [sitecore-assembly-lists](https://github.com/richardszalay/sitecore-assembly-lists) - Sitecore 从 8.2 Update 5 开始为 Sitecore 版本提供程序集列表信息.该项目提供了用于在安装和开发过程中验证 Sitecore 程序集列表的工具.

## Azure

- [ARM templates for Sitecore](https://github.com/Sitecore/Sitecore-Azure-Quickstart-Templates) - Sitecore 当前所有可用的 Azure 资源管理器模板.
- [Sitecore Azure Scripts](https://github.com/robhabraken/Sitecore-Azure-Scripts) - Azure 相关的 PowerShell 脚本和 ARM 模板可用作您自己的脚本和需求的模板或样板.
- [Sitecore Azure Content](https://github.com/olegburov/Sitecore-Azure-Content) - 有关如何利用 Azure 服务将 Sitecore 解决方案自动部署到 Microsoft Azure 云平台的文章.
- [Sitecore Advanced Azure Devops](https://github.com/JeffDarchuk/AdvancedSitecoreAzureDevops) - 使用灵活且通用的脚本在 azure 上扩展 Sitecore（需要连接有效的 powershell Azure 会话并可用）.
- [Language Understanding (LUIS) Samples](https://github.com/Azure-Samples/cognitive-services-language-understanding) - 语言理解智能服务 (LUIS) 示例.
- [Sitecore Media Azure Blob Storage provider](https://github.com/ivansharamok/Sitecore.Media.AzureBlobStorage) - 允许将 Sitecore 媒体库资产存储在 Azure Blob 存储帐户中.
- [CloudMediaLibrary](https://github.com/jammykam/Sitecore-CloudMediaLibrary) - 允许 Sitecore 媒体库通过云存储进行存储和服务.
- [SitecoreCognitiveServices](https://github.com/smithc/SitecoreCognitiveServices) - SDK 将 Microsoft 的认知服务集成到 Sitecore 中.
- [Sitecore Publishing Service Azure Templates](https://github.com/coreyasmith/sitecore-publishing-service-azure-templates) - Azure 资源管理器 (ARM) 模板，用于在 Sitecore Azure PaaS 环境中安装 Sitecore 发布服务.
- [Sitecore Diagnostics](https://github.com/BasLijten/SitecoreDiagnostics) - 使用 Application Insights 进行 Sitecore 诊断.
- [Application Insights Annotations](https://github.com/BasLijten/sitecore-application-insights-annotations) - 创建 App Insinghts 注释.

## Cache

- [Cache Tuner](https://github.com/KayeeNL/CacheTuner) - 该模块是 Sitecore 缓存指南中给出的规则的实现.
- [Caching Manager](https://github.com/jbluemink/SitecoreCachingManager) - 用于轻松管理 Sitecore 10 缓存的控制台.
- [Cache Processing Instance](https://github.com/ParTech/Cache-Processing-Instance) - 专用 HTML 缓存处理实例的概念验证.
- [ExperienceEditorCache](https://github.com/marek-musielak/Skillcore.ExperienceEditorCache) - 缓存模块，使使用 Sitecore 体验编辑器更加愉快.
- [ManualHtmlCacheClearer](https://github.com/TwentyGotoTen/ManualHtmlCacheClearer) - 从 Sitecore 客户端清除本地和远程实例上的特定 HTML 缓存.
- [CacheCounters](https://github.com/matthewkenny/CacheCounters) - 将 Sitecore 缓存大小信息报告到 Windows 性能计数器中.
- [Sitecore Rules-Based Output Caching](https://github.com/zkniebel/Sitecore-Advanced-Output-Caching) - 提供基于规则的 Sitecore 输出缓存差异支持，支持个性化组件和其他需要更复杂缓存差异逻辑的组件的缓存.
- [Dictionary Flush Partial Cache](https://github.com/jbluemink/DictionaryFlushPartialCache) - 在 Sitecore 词典项目发生更改时闪烁部分 Html 缓存.

## Commerce

- [Reference Storefront](https://github.com/Sitecore/Reference-Storefront) - Sitecore 参考店面.
- [Commerce Sample Plugins](https://github.com/Sitecore/SitecoreCommerce) - Sitecore 商务插件的示例代码（针对 XC 9.0.3 和 9.1）.
- [HabitatHome Commerce](https://github.com/Sitecore/Sitecore.HabitatHome.Commerce) - 遵循 Helix 架构原则，在 XP 和 XC 上使用 SXA 构建的示例.
- [sitecore-commerce-configuration](https://github.com/richardszalay/sitecore-commerce-configuration) - 用于配置和增强 Sitecore Commerce Engine 配置的工具.
- [Plumber for Sitecore Commerce](https://github.com/richardszalay/plumber-sc) - 查看 Sitecore 商务引擎配置的工具.
- [Short Confirmation Codes](https://github.com/dsolovay/ShortConfirmationCodes) - Provides six character confirmation codes (configurable), randomly generated, and tracked in the commerce database to avoid conflicts, as shorter codes are easier to communicate over support calls and for some clients may be more convenient than the 25 character confirmations that are provided out of the box.
- [Sitecore Commerce Engine Fedex plugin](https://github.com/XCentium/SC-Plugin-FedEx) - 允许用户将 Fedex 集成为运输的履行方式.
- [Sitecore Commerce Engine USPS plugin](https://github.com/XCentium/SC-Plugin-USPS) - Allows the user to integrate USPS as a Fulfillment Method for shipping.
- [Sitecore Commerce Engine UPS Address Validation plugin](https://github.com/XCentium/SC-Plugin-UPS-Address-Validation) - 允许验证送货地址或帐单地址，使产品交付成为良好的体验.

## Configuration

- [Sitecore configuration consolidator (offline ShowConfig)](https://github.com/ParTech/ScShowConfig) - 简单的控制台应用程序，可整合 Sitecore 配置（包括文件）.

## Containers

- [Windows Docker Machine](https://github.com/StefanScherer/windows-docker-machine) - Vagrant 环境创建一个“Docker Machine”，在带有 Windows 容器的 MacBook 上工作，以便您可以轻松地在 Docker Desktop Linux 容器和 Windows 容器之间切换.
- [Sitecore Containers Prerequisites](https://github.com/nickwesselman/sitecore-containers-prerequisites) - 检查计算机的 Sitecore Container 兼容性，启用 Hyper-V，下载并安装包括 Sitecore 10.1 在内的软件
- [Sitecore Docker Examples](https://github.com/Sitecore/docker-examples) - 最新版本的 Sitecore 10.* 的官方 Docker 示例映像，包括“入门”XP0 容器环境.
- [Container Deployment](https://github.com/Sitecore/container-deployment) - 提供有关如何使用各种方法部署 Sitecore 容器的示例.
- [Lighthouse Demo](https://github.com/Sitecore/Sitecore.Demo.Platform)  - 使用 SXA 10.0 的最新 XP 10.0 演示. 它只能部署在 Docker 容器内.
- [Sitecore MVP](https://github.com/Sitecore/MVP-Site) - 使用 Sitecore 10 和 SXA 在容器中构建的真实 Sitecore MVP 网站的源代码.
- [Repository of Sitecore Docker images](https://github.com/Sitecore/docker-images) - 为最新版本的 Sitecore 构建您自己的 Docker 映像.
- [Packer for Sitecore](https://github.com/asmagin/sitecore-packer) - 存储库包含本地 Sitecore 托管环境的 Packer 模板，其中包含 Windows 上的 IIS 和 SQL Server、SOLR 和 Sitecore 9.0 构建虚拟机映像以及 VirtualBox 的 Vagrant 框（由 Chef 提供）.
- [Docker SOLR with SSL](https://github.com/LaubPlusCo/docker-solr-ssl) - 一个简单的设置，使用生成的证书在运行带有 SSL 的 solr 的主机上设置 Linux 容器.
- [Sitecore Docker Tools](https://github.com/sitecore/docker-tools)  - 一组实用程序，可改善开发人员在 Docker 环境中运行 Sitecore 时的体验. 这是一个包含可在 Sitecore 容器构建期间使用的开发脚本和入口点的映像，以及一个 PowerShell 模块，其中包含在 Sitecore 容器主机上用于初始化 Sitecore Docker 环境的功能.
- [Konabos Docker Examples](https://github.com/konabos/konabos-docker-examples) - 示例撰写文件和相关配置超出了 Sitecore 官方提供的范围.
- [Container Asset Image Creator Module](https://github.com/KayeeNL/sitecore-module-docker-asset-image-creator) - 用于处理给定 Sitecore 模块自动创建 Docker 资产映像的脚本.
- [Containers & AKS](https://github.com/bplasmeijer/Sitecore-Symposium-2020-Containers-AKS) - 将 Sitecore 10 提升到 Azure AKS 的新水平.
- [PaaS to AKS](https://github.com/robhabraken/paas-to-aks)  - 用于将 Sitecore 10.0.* 部署到来自 Sitecore 的 Azure PaaS 架构的 Azure AKS 的样板项目. 其中包括用于外部数据服务的 ARM 模板（在生产中运行 Sitecore k8s 所需），以及支持 AKS 上 Sitecore 的完整基础设施即代码设置的脚本.
- [Sitecore Deployment on Kubernetes Example](https://github.com/georgechang/sitecore-k8s)  - 使用 SolrCloud 将 Sitecore 10.1 XP0 部署到 AKS 的示例. 它应该部署：1）Sitecore 10.1 XP0；  2）微软SQL Server 2019；  3）Zookeeper 3.4（3个副本）；  4）Solr 8.4（3个副本）
- [Sitecore Module Docker Asset Image Creator](https://github.com/KayeeNL/sitecore-module-docker-asset-image-creator) - 用于处理给定 Sitecore 模块自动创建 Docker 资产映像的脚本
- [Test Sitecore Packages](https://github.com/michaellwest/test-sitecore-packages)  - 提供一种快速方便地安装软件包作为 docker 映像构建的一部分或在容器启动后安装的方法. 对于需要验证构建工件在 XM 的普通实例中工作的模块开发人员或团队很有用. 支持 XM、SPE、SXA 和任何自定义模块 zip/scwdp 或通用 zip 文件.


- [Sitecore Content Hub Importer](https://github.com/vasiliyfomichev/content-hub-importer)  - Sitecore 内容中心资产导入器； 允许将图像资源从各种数据源导入 Sitecore 内容中心.
- [schguild](https://github.com/sitecoreguild/schguild) - 提供工具和示例代码来帮助您学习和使用 Sitecore Content Hub.
- [Sitecore.ContentHub.Twitter](https://github.com/josedbaez/Sitecore.ContentHub.Twitter) - Demonstrates how to tweet from Sitecore Content Hub CMP.
- [Sitecore.SharedSource.CMP.Connector.Extensions](https://github.com/josedbaez/Sitecore.SharedSource.CMP.Connector.Extensions) - 扩展了 Sitecore CMP 2.0.0 的 Sitecore Connect，以便可以使用 Sitecore DAM 2.0.0 的 Sitecore Connect™ 使用的 xml 格式同步 CMP 实体上设置的图像，因此需要此模块.
- [Starter Kit for Content Hub with Next.js and GraphQL](https://github.com/konabos/Next.js-Starter-kit-using-GraphQL-and-Sitecore-Content-Hub-Content-as-a-Service) - 内容中心无头入门套件.
- [Focal point cropping](https://github.com/robhabraken/content-hub-focal-point-cropping) - Focal point cropping for Content Hub.
- [VS Solution Example for Content Hub](https://github.com/Sitecore/ContentHub-VS-Solution-Example) - 一个 Visual Studio 解决方案示例，用于下载任何内容中心开发并以此为基础，具有智能感知、脚本同步、调试和单元测试功能.


- [Sitecore.Demo.CHONE](https://github.com/Sitecore/Sitecore.Demo.CHONE) - 由 Sitecore 演示解决方案团队构建的所有 Content Hub ONE 演示的存储库.


- [Sitecore spatial geojson polygons](https://github.com/josedbaez/sitecore-spatial-geojson-polygons)  - 实现 Linq 扩展，以便能够查询 solr 索引中拦截 GeoJson 多边形的点. 该演示提供了一个带有空间字段的模板，以及几个带有来自 openstreetmap 的多边形的示例项目，覆盖了一些城市； 控制器渲染从查询字符串中读取纬度和经度并返回找到的项目的多边形（例如大本钟的坐标返回伦敦）.
- [Sitecore Solr Schema](https://github.com/konabos/solr-sitecore-schema) - Solr 8.1.1 和 8.4.0 的 Sitecore 配置集（架构）.
- [Search Index Builder](https://github.com/jermdavis/SearchIndexBuilder) - 一种用于从 Sitecore Web 应用程序外部重建搜索索引的工具，特别适合长时间运行的构建.
- [SolrCloud Install Scripts](https://github.com/jermdavis/SolrCloud-Helpers) - PowerShell 脚本库可帮助在 Windows 上安装 SolrCloud 集群. 
- [Docker SolrCloud for Sitecore 10](https://github.com/jermdavis/Sitecore-SolrCloud-Docker)  - 创建一个可与 Docker 下的 Sitecore 10 实例一起使用的 SolrCloud 容器. 这些文件已根据 Sitecore Docker 示例存储库中的 Solr 容器文件进行了调整. 可以使用这些文件替换 Sitecore 提供的默认“solr”服务.
- [Sitecore SolrProxy](https://github.com/Antonytm/Sitecore.SolrProxy) - 如果您只能访问 Sitecore CM，则可轻松访问 Solr 管理控制台的工具.
- [Common Sitecore ContentSearch extensions](https://github.com/LaubPlusCo/LaubPlusCo.Common.ContentSearch)  - Sitecore contentSearch 的常见扩展； 下面的 PopulateSolrSchema 管道处理器可确保 Sitecore 中所有已安装的语言都添加到 solr 托管架构中. 
- [Sitecore Computed Search](https://github.com/martinrayenglish/Sitecore-Computed-Search)  - 索引搜索开发加速器，允许开发人员在索引上声明计算的搜索字段，该索引可以捕获和存储一定范围内项目的目标字段值以及基于作为其表示的一部分的特定模板的项目的字段值. 此外，可以使用搜索提升将特定权重应用于这些计算字段，以便可以在搜索结果中提升匹配搜索项的内容.
- [sitecore-azure-search-compat](https://github.com/richardszalay/sitecore-azure-search-compat) - Sitecore + Azure 搜索的兼容性补丁.

## Data

- [SitecoreDataImporter](https://github.com/markstiles/SitecoreDataImporter) - 用于将数据库数据和 Sitecore 内容导入 Sitecore.
- [SitecoreEzImporter](https://github.com/dresser/SitecoreEzImporter) - 使用 SPEAK UI 的 Sitecore CMS 数据导入工具.

## Data Exchange Framework

- [Gutters for Sitecore Data Exchange Framework](https://github.com/KayeeNL/Sitecore.DataExchange.Gutters) - DEF 的 3 个装订线集合，为树中项目的上下文项目提供快速解决方案：“ItemDisabled”、“PipelineBatch”和“PipelineStep”.
- [Data Exchange Framework Docs](https://github.com/Sitecore/Data-Exchange-Framework-Docs) - 使用 Sphinx 生成的 Sitecore 数据交换框架文档.

## Demo
- [Sitecore Habitat](https://github.com/Sitecore/Habitat)  - Habitat 是基于 Helix 架构原则构建的 Sitecore 解决方案示例. 不再更新或维护，并被 Sitecore Helix Examples 取代.
- [Sitecore Helix Examples](https://github.com/Sitecore/Helix.Examples)  - 跨各种工具和业务场景的 Sitecore Helix 实践演示； 旨在展示比现有示例更广泛的实现类型/要求.
- [Lighthouse Demo](https://github.com/Sitecore/Sitecore.Demo.Platform)  - 使用 SXA 10.0 的最新 XP 10.0 演示. 它只能部署在 Docker 容器内.
- [Sitecore.Demo.Headless](https://github.com/Sitecore/Sitecore.Demo.Headless) - Sitecore JSS PWA 演示资产和未来的“Sitecore Headless”相关演示资产.
- [Sitecore MVP](https://github.com/Sitecore/MVP-Site) - 使用 Sitecore 10 和 SXA 在容器中构建的真实 Sitecore MVP 网站的源代码.
- [Sitecore.HabitatHome.Utilities](https://github.com/Sitecore/Sitecore.HabitatHome.Utilities) - 实用程序和脚本示例的集合，可帮助安装 Sitecore Experience Platform、安装 Sitecore Experience Commerce、安装 Sitecore 模块、预热 Sitecore 实例、强化 Sitecore 实例的安全性等.
- [Sitecore.HabitatHome.Commerce](https://github.com/Sitecore/Sitecore.HabitatHome.Commerce) - 与外部贡献者和合作伙伴一起演示资产.
- [Sitecore.HabitatHome.Omni](https://github.com/Sitecore/Sitecore.HabitatHome.Omni) - 共享 Sitecore JSS PWA 演示资产和未来的“Sitecore Omni”相关演示资产.
- [Sitecore.Demo.Group](https://github.com/Sitecore/Sitecore.Demo.Group) - Habitat Group 演示站点 - 基于 Habitat 的演示的开发人员示例.
- [Sitecore User Group UK](https://github.com/steviemcg/scuguk) - 使用 Git 作为单一事实来源、使用 Netlify 进行持续部署和使用 Gatsby v2 构建的 CDN 分发的 JAMstack 架构演示.
- [Sitecore DXP Demo](https://github.com/Sitecore/Sitecore.Demo.Edge) - XM、Experience Edge、Content Hub DAM 和 CMP、Content Hub Edge、JSS、CDP、Sitecore Personalize、Next.js 和 Vercel 的演示.
- [Sitecore Developer Portal](https://github.com/Sitecore/developer-portal)  - Sitecore 开发人员门户使用 Next.js、Typescript、Tailwind CSS 构建，并托管在 Vercel 上. 它使用静态站点生成（SSG）在构建时创建所有页面. 它还利用增量静态再生 (ISR) 在页面内容发生更改时自动更新应用程序. 许多页面都是用 Markdown 编写的，并在构建时转换为 HTML. 使用的图像在 Sitecore DAM 中进行管理并发布到 CDN.
- [Play Summit](https://github.com/Sitecore/Sitecore.Demo.XmCloud.PlaySummit) - 播放 Summit 演示，其中包含 XM Cloud、Content Hub DAm、CMP、带有 Versel 托管的 Next.js 等.
- [Developer Portal](https://github.com/Sitecore/developer-portal)  - Sitecore 开发人员门户使用 Next.js、Typescript、Tailwind CSS 构建并托管在 Vercel 上，使用静态站点生成在构建时创建所有页面. 它还利用增量静态再生 (ISR) 在页面内容发生更改时自动更新应用程序. 由于大部分页面内容都是用 Markdown 编写并在构建时转换为 HTML，因此图像在 Sitecore DAM 中进行管理，并且
 发布到 CDN.

## Deployment

- [PostDeploySteps](https://github.com/jst-cyr/NonlinearPostDeploySteps)  - 与 TDS 一起使用的部署后步骤.  1) 触发部署后步骤的 TDS 示例项目；  2) 示例 Web 项目以显示部署步骤中的拉动；  3) 可以添加到解决方案中的 DeployStep 类库.
- [Sitecore Devops with AppVeyor](https://github.com/steviemcg/Sitecore.Devops.AppVeyor) - 示例解决方案展示了如何开发开源 Sitecore 模块并将其与 AppVeyor（云中托管的持续交付解决方案）连接.
- [Cake.Sitecore](https://github.com/asmagin/Cake.Sitecore) - 提供一组预构建 [CAKE build] 任务，用于简化基于 Helix 的 Sitecore 项目的 CI/CD 配置.

## Edge

- [Sitecore Demo Edge](https://github.com/Sitecore/Sitecore.Demo.Edge) - 用于内容中心和体验管理的主要 Sitecore Edge 的存储库.

## Editing

- [Sitecore Sweep](https://github.com/Kasaku/Sitecore.Sweep) - Sitecore 的一个简单可扩展模块，用于自动清理项目中的 HTML.


- [Copy Version module](https://github.com/ParTech/Copy-Version)  - 向内容编辑器添加命令，允许用户复制和粘贴项目的最新版本而不是整个项目. 安装后，可以从内容树中的上下文菜单访问“复制版本”和“粘贴版本”命令.
- [Browse Command](https://github.com/ParTech/Browse-Command)  - 添加一个命令，允许用户在新的浏览器窗口中打开 Sitecore 内容树中的项目.  Sitecore 不提供开箱即用的功能，除了具有进入预览模式效果的预览命令之外，因此给定模块将执行完全相同的操作，但不会进入预览模式.
- [Expand Descendants Command](https://github.com/ParTech/Expand-Descendants-Command#expand-descendants-command) - 该模块添加了一个命令，允许用户从 Sitecore 内容树中展开某个项目的所有后代.
- [Environment Styler for Sitecore](https://github.com/jammykam/Environment-Styler-for-Sitecore) - Sitecore 登录屏幕和标题功能区上的环境特定样式（和文本）.
- [InsertOptionsLoophole](https://github.com/TwentyGotoTen/InsertOptionsLoophole) - 防止 Sitecore 用户绕过插入选项.
- [ScopeToThis](https://github.com/ianjohngraham/Coreblimey.ScopeToThis) - 允许在 Sitecore 内容编辑器树上使用 Visual Studio 的“范围”功能.
- [DeviceEditorShortcuts](https://github.com/MartinMiles/DeviceEditorShortcuts) - 设备编辑器的工作效率得到提高，如果设置为该特定组件，则显示数据源，并通过弹出单击直接预览该数据源.
- [DmsGutters](https://github.com/markvanaalst/Sitecore.SharedSource.DmsGutters) - 内容编辑器装订线指示经过测试和个性化的项目.
- [Move Validator](https://github.com/Velir/Sitecore-MoveValidator) - 验证是否可以根据插入选项将项目移动到新位置.
- [SitecoreFieldSuite](https://github.com/Velir/SitecoreFieldSuite)  - 为 Sitecore 用户提供更加简化且信息丰富的内容创作方法. 这是通过修改 5 种字段类型、引入图像字段、启用引用项目的自动发布以及添加新功能（例如“编辑表单”、“转到项目”按钮和“字段装订线”）来实现的.
- [Sitecore Smart Commands](https://github.com/AlenPelin/Sitecore-Smart-Commands) - 一个共享源模块，其中包含内容编辑器中的智能复制、复制和克隆命令，这些命令实现了默认情况下缺少的许多想要的功能.
- [CopyPageToVersions](https://github.com/merkle-open/SitecoreCopyPageToVersions) - 内容编辑器和体验编辑器的扩展，为内容编辑器提供一个对话框，其中可以将特定版本的页面复制到可选择的语言版本列表，包括页面渲染上引用的所有数据源.
- [Sitecore-TinyMCERTE](https://github.com/EmanueleCiriachi/Sitecore-TinyMCERTE) - 一种 Sitecore 控件，使用 Tiny MCE 编辑器代替默认编辑器.

## Fields

- [Sitecore.Foundation.Fields](https://github.com/MartinMiles/Sitecore.Foundation.Fields) - 可供您的 Sitecore 解决方案使用的自定义字段集合.
- [LinkList](https://github.com/josedbaez/Monoco.CMS.FieldTypes) - Sitecore LinkList Field Type.
- [CrossDatabaseTreeListField](https://github.com/ivansharamok/CrossDatabaseTreeListField) - 扩展的树列表字段以支持跨数据库引用.
- [LimitedText Field](https://github.com/ParTech/LimitedText-Field-Controls)  - 向 Sitecore 内容编辑器添加了两种新的字段类型：单行文本限制和多行文本限制. 两者都继承了现有文本字段控件的所有功能，并添加了配置字段允许的最大值的可能性，还通知用户在编辑时剩余的字符数.
- [CustomFields](https://github.com/AlexanderDavyduk/CustomFields) - NameValueDropLists、NameValueDropListsField、NameValueDroplist、NameValueDroplistField、SortableMultilist、SortableMultilistField、TimeZonesDropList 字段的选择.
- [YouTube Video Picker Field](https://github.com/pveller/BrainJocks.YouTubeVideoField) - 适用于 Sitecore 的 YouTube 视频选择器字段的完全可行的解决方案.
- [Hide Dependent Fields Controls](https://github.com/jammykam/Hide-Dependent-Fields)  - 将新的复选框、下拉列表和下拉链接字段类型添加到 Sitecore 内容编辑器，根据所选值将隐藏后续同级字段. 所有控件均继承自其等效的 Sitecore 对应项，并添加所需的 UI 增强功能.
- [icon-selector-field](https://github.com/Wesley-Lomax/icon-selector-field) - Sitecore 的自定义图标选择器字段.
- [ImageSelector](https://github.com/markvanaalst/Sitecore.SharedSource.ImageSelector) - Sitecore 的图像选择器字段，允许基于 TreeListEx 字段选择和预览多个图像.

## Forms

- [Sitecore-Forms-Extensions](https://github.com/bartverdonck/Sitecore-Forms-Extensions) - 向表单创建器添加一些功能，例如发送邮件、时间跨度验证、订阅列表、条件、Azure Blob 存储提供程序等等.
- [WFFM Conversion Tool](https://github.com/afaniuolo/WFFM-Conversion-Tool) - 控制台应用程序，提供自动化解决方案，用于将营销人员 Web 表单 (WFFM) 项目及其数据转换并迁移到 Sitecore 表单.
- [SendMail for Experience Forms](https://github.com/KayeeNL/Sitecore.ExperienceForms.Modules.SendMail) - 为 Sitecore 9 表单带来了新的发送电子邮件操作，允许使用 MainUtil.SendMail 方法提交电子邮件，该方法将使用 SMTP 服务器以 HTML 或纯文本形式提交电子邮件.
- [Forms Cloud Upload](https://github.com/jbluemink/Sitecore-Forms-Cloud-Upload) - 使用 Azure 存储队列和 Azure 存储 Blob 存储 Sitecore 9.3+ 表单上传加密，并使用来自 Azure 密钥故障的密钥 - 一旦用户上传敏感数据，这可以方便地实现合规性.

## Frameworks

- [NitroNet for Sitecore](https://github.com/merkle-open/NitroNetSitecore) - 处理所有可能的演示场景，将车把前端集成到 Sitecore（而不是 Razor View）中，而不会造成功能损失并提高工作效率.

## JSS

- [JSS](https://github.com/Sitecore/jss) - Sitecore JavaScript 服务的官方存储库.
- [sugcon-2019-jss-examples](https://github.com/chaturangar/sugcon-2019-jss-examples) - SugCon 2019 jss 示例.
- [SitecoreQL](https://github.com/kmazzoni/SitecoreQL) - Sitecore 的 GraphQL 实现，例如，您可以查询 Sitecore 的内容搜索 API.
- [JSS React Starter Application](https://github.com/altola/sitecore-jss-react-basic) - 请遵循 https://jss.sitecore.net 上的主要 JSS 文档，获取有关 JSS 的最新文档.
- ['Hello World' Starter for Sitecore JSS Tech Preview 4](https://github.com/altola/sitecore-jss-react-starter) - 没有 GraphQL 位的 Sitecore JSS 的 hello world 启动器.
- [Extensible JSON Renderings](https://github.com/coreyasmith/jss-extensible-json-renderings) - 扩展 Sitecore JavaScript 服务中的 JSON 渲染.
- [JavaScript Services Anti-Forgery Tokens](https://github.com/coreyasmith/jss-anti-forgery-tokens)  - 示例存储库，演示如何使用开箱即用的防伪令牌验证器在 Sitecore JavaScript 服务中通过 MVC 和 Web API 控制器使用 .NET 防伪令牌. 演示 API 还在断开连接模式下进行了完全模拟，以展示此功能如何在断开连接和连接模式下工作.
- [How to GraphQL](https://github.com/kamsar/howtographql) - 一个全栈教程网站，用于了解有关 GraphQL 的所有信息.
- [JSS with Vue.js](https://github.com/KayeeNL/sitecore-jss-getting-started-vuejs) - 使用 Vue.js 框架的 JSS 起始模板.
- [Headless Examples](https://github.com/Sitecore/headless-examples) - 包含有价值示例的存储库，例如使用联合身份验证的 JSS 嵌入式应用程序和 Next.js.
- [SVG Images for JSS](https://github.com/KayeeNL/Sitecore.Extensions.JSS.SVG) - 添加了对 Sitecore JSS 中由 SVG 标签呈现的图像的支持.

## JAMstack

- [Next.js Starter kit using GraphQL and Sitecore Experience Edge for Content Hub](https://github.com/konabos/Next.js-Starter-kit-using-GraphQL-and-Sitecore-Content-Hub-Content-as-a-Service) - 这是在 React 上使用 NextJS 的 Sitecore 体验 Edge 内容即服务方法的一个很好的示例，使用最新内容中心的演示实例.
- [Uniform, JSS and Next.js starter kit](https://github.com/uniformdev/sitecore-jss-nextjs-starterkit) - Uniform、JSS 和 Next.JS 入门套件，包含内容项和所需的配置文件，非常适合启动普通项目.
- [Uniform, MVC and Next.js starter kit](https://github.com/uniformdev/sitecore-mvc-nextjs-starterkit) - Uniform、MVC 和 Next.JS 入门套件，包含内容项和所需的配置文件，非常适合启动普通项目.

## Headless

- [Sample](https://github.com/uniformdev/sitecore-jss-nextjs-starterkit) - 无头示例 TODO


## Helix

- [Sitecore Helix Documentation](https://github.com/Sitecore/Helix.Docs) - 在 Sitecore 中为 Sitecore Helix 进行开发的官方指南和推荐实践.
- [Sitecore Helix Examples](https://github.com/Sitecore/Helix.Examples)  - 跨各种工具和业务场景的 Sitecore Helix 实践演示； 旨在展示比现有示例更广泛的实现类型/要求.
- [Helixbase](https://github.com/muso31/Helixbase) - 基于 Sitecore Helix 的绿地项目解决方案.
- [Sitecore Foundation](https://github.com/Avanade/SitecoreFoundation) - Sitecore框架遵循Helix模块化架构设计原则.包括大量的功能层和基础层模块，以及项目层可重用的Common.
- [Helix example Module & Solution templates](https://github.com/LaubPlusCo/Helix-Templates) - Sitecore Helix Visual Studio 模板扩展的模板.
- [Helix frontend development example](https://github.com/LaubPlusCo/helix-frontend-example) - Sitecore Helix 解决方案的简单前端开发设置.
- [Helix Publishing Pipeline](https://github.com/richardszalay/helix-publishing-pipeline)  - 允许 Helix 解决方案作为单个单元发布，并自动包含模块内容（如视图和配置补丁）. 它还包含有关本地开发部署的优化和指导. 由于它扩展了标准的 Web 发布管道，因此它应该通过 Visual Studio 或命令行与任何支持的目标（包、文件系统、Azure、Docker）配合使用.
- [CustomLinkProvider](https://github.com/TwentyGotoTen/CustomLinkProvider) - 将自定义 Sitecore 链接提供商从非 Helix 转换为 Helix 的演示.
- [Elision](https://github.com/sitecore-elision) - 实现 Helix 原理的开源 Sitecore 加速器.
- [Helixify](https://github.com/konabos/Konabos.Helixify) - 该模块旨在为任何 Sitecore 项目添加即时 Helix 兼容性.
- [Sitecore Foundation](https://github.com/Avanade/SitecoreFoundation) - Avanade 的 Sitecore 框架遵循 Helix 模块化架构设计原则.
- [PLAY Summit Demo](https://github.com/Sitecore/Sitecore.Demo.Edge) - XM、Experience Edge、Content Hub DAM 和 CMP、Content Hub Edge、JSS、CDP、Sitecore Personalize、Next.js 和 Vercel 的演示.

## Icons

- [Extra People Icons](https://github.com/jermdavis/ExtraPeopleIcons) - 您的 Sitecore 实例的一些额外的“人物”图标.
- [sitecore-icon-build](https://github.com/richardszalay/sitecore-icon-build) - MSBuild extensions for building Sitecore icon zip archives and including them in the published website.

## Integration

- [Integration Blueprints](https://github.com/Sitecore/Integration-Blueprints) - 示例代码展示了如何将 Sitecore 产品相互集成以及与第三方系统集成.

## Item Resource Files

- [Sitecore IAR Management](https://github.com/GAAOPS/Sitecore.IAR.Management) - 用于将项目作为资源进行管理的 PowerShell 脚本.
- [Sitecore Item as Resource Explorer](https://github.com/GAAOPS/Sitecore.Protobuf.Browser) - WPF 应用程序允许您浏览 Sitecore 静态数据库文件 (.dat)

## Languages

- [Sitecore Item Translator](https://github.com/adoprog/Sitecore-Item-Translator) - 项目翻译模块与 Google 翻译无缝集成，只需单击按钮，您就可以将文本翻译成 Google 翻译支持的任何语言.
- [Sitecore Item Versioner](https://github.com/aquasonic/SitecoreItemVersioner) - 此模块将新功能区添加到内容编辑器的版本块中.使用新功能区，可以最初以所有配置的语言创建项目版本.
- [CopyPageToVersions](https://github.com/merkle-open/SitecoreCopyPageToVersions) - 内容编辑器和体验编辑器的扩展，为内容编辑器提供一个对话框，其中可以将特定版本的页面复制到可选择的语言版本列表，包括页面渲染上引用的所有数据源.

## Logging

- [SitecoreRollingLogFileAppender](https://github.com/ivansharamok/SitecoreRollingLogFileAppender) - 用于 Sitecore 的 Log4net RollingLogFileAppender 允许限制日志文件大小.
- [RabbitMQ.GEFL.Appender for Sitecore](https://github.com/asmagin/Sitecore.Logger.RabbitMQ.GelfAppender) - 为 Sitecore.Logger 实现 RabbitMQ 记录器适配器.
- [Logging To Logentries](https://github.com/jammykam/Sitecore.Logentries) - 配置您的应用程序以登录 Logentries（支持 NLog、Log4net、Serilog 等）.
- [Namics.Foundation.Logger](https://github.com/merkle-open/Namics.Foundation.Logger) - 提供一组静态方法用于具有灵活选项的日志记录

## Maintenance

- [Admin Scripts for Development and Deploying](https://github.com/jbluemink/Sitecore-Admin-Scripts-for-Development-and-Deploying) - `/admin` 文件夹的附加功能：AddAdminUser、AddEditorUser、ResetAdminPassword、FillDbWithExtranetUser、InstallUpdatePackage、InstallZipPackage、ParameterDrivenPublish 和 IsPublishTaskRunning.
- [Sitecore Instance Manager](https://github.com/Sitecore/Sitecore-Instance-Manager) - 传奇的 Sitecore 实例管理器，现在支持 9.x 版.
- [Sifon](https://github.com/MartinMiles/Sifon)  - 备份恢复工具支持 XC 和远程机器操作，具有出色的可插拔接口.  Sifon 还拥有非常强大的扩展系统，其插件涵盖了日常活动的许多方面.

## Media

- [Autocropper](https://github.com/zkniebel/Autocropper) - 根据预定义的尺寸和指定的原点自动生成图像的裁剪版本，以在响应式网站上使用.
- [Media-Framework-Brightcove-Edition](https://github.com/Sitecore/Media-Framework-Brightcove-Edition) - 用于 Sitecore 媒体框架的 Brightcove 连接器.
- [YouTube Integration module](https://github.com/ivansharamok/YouTube-Integration)  - YouTube 集成模块可能是您在网站上显示 YouTube 频道视频的一种简单方法. 在媒体库中，您有一个 YouTube 文件夹，通过输入频道名称，该频道中的所有视频现在都由一个项目表示，当您在频道上创建新视频时，它会自动更新媒体库中的频道.
- [Shrink](https://github.com/robhabraken/shrink) - 深入了解媒体库的使用情况，类似于硬盘驱动器的磁盘使用统计查看器，还显示哪些项目正在实际使用和发布，以便您可以轻松找到不必要占用数据库空间的媒体项目，并为您提供多种清理媒体库的方法！
- [Dianoga](https://github.com/kamsar/Dianoga)  - Sitecore 媒体库的自动图像优化器，完全自动地将 Sitecore 提供的图像大小减少了 8-70%. 当请求媒体图像时，Dianoga 在将图像数据放入 Sitecore 媒体缓存后立即自动对图像数据运行 mozjpeg、PNGOptimizer、SVGO 或 WebP.

## NET Core Headless

- [Netcore Auth](https://github.com/robearlam/sitecore-netcore-auth) - 一个存储库，展示如何在 .NET Core 无头 Sitecore 应用程序中启用身份验证.

## ORM

- [Glass.Mapper](https://github.com/mikeedwards83/Glass.Mapper)  - Glass.Mapper 是非常流行的 Glass.Sitecore.Mapper 项目的重新开发. 该项目旨在创建一个更强大、更灵活的解决方案，该解决方案不仅适用于许多不同的 CMS.
- [TemplateModelHelper](https://github.com/lowedown/TemplateModelHelper) - 用于处理生成的 Sitecore 模板模型（通过 Glass.Mapper 或其他框架映射）的辅助方法，其主要目标是使开发人员可以轻松地使用生成的模板模型查询 Sitecore 数据库.
- [TDS-T4-Model-Generation](https://github.com/Sitecore/TDS-T4-Model-Generation) - TDS 的 T4 模型生成.
- [Sitecore.CodeGenerator](https://github.com/ParTech/sitecore.codegenerator) - 使用 T4 模板生成 Glass Mapper 界面，无需 TDS.
- [Synthesis](https://github.com/blipson89/Synthesis)  - Sitecore 的对象映射框架，与传统的 Sitecore 开发相比，它可以在更短的时间内开发更可靠和可维护的网站. 它是一个强类型模板对象生成器，对于具有 Sitecore 或传统 .NET 背景的开发人员来说很容易理解. 它与 Sitecore MVC（通过 Synthesis.Mvc 包）巧妙地集成，作为视图渲染模型提供程序和控制器渲染的 IoC 依赖项.

## Other

- [License Expiration Module 2.0](https://github.com/KayeeNL/Sitecore.License.Expiration.Module) - 检查 Sitecore 许可证的到期日期，显示内容编辑器警告消息或/和发送电子邮件以在 Sitecore 许可证即将到期时进行通知.
- [Sitecore.SharedSource.JohnWest](https://github.com/jammykam/Sitecore.SharedSource.JohnWest) - 来自 John West 博客文章的 Sitecore 原型代码示例集合.
- [BLAZOR + SITECORE](https://github.com/GoranHalvarsson/SitecoreBlazor) - 允许您运行 Sitecore 应用程序的客户端，也遵循 HELIX 概念，即干净的方式.
- [Sitecore.SampleMvc](https://github.com/coreyasmith/Sitecore.SampleMvc) - 开箱即用的 Sitecore 示例站点代码的 MVC 版本（默认情况下，Sitecore 附带一个基于 Web 表单和 XSLT 构建的示例站点）.
- [Sitecore TokenManager](https://github.com/JeffDarchuk/SCTokenManager) - 旨在允许将任何类型的内容动态注入 RTE 字段的框架.
- [sxp-notifications](https://github.com/michaellwest/westco-sxp-notifications) - Sends browser notifications to users in Sitecore.
- [Sitecore Redis Session Provider](https://github.com/boro2g/Sitecore-Redis-Session-Provider) - Sitecore Redis 会话提供程序实现.

## Packaging

- [Package Autoloader](https://github.com/JeffDarchuk/PackageAutoloader) - 一种自动应用 Sitecore 包以在部署过程中合并某些内容的工具. 
- [Sitecore.Ship](https://github.com/kevinobee/Sitecore.Ship) - 通过 HTTP 请求安装 Sitecore 更新包的轻量级方法.
- [UpdatePackageInstaller](https://github.com/HedgehogDevelopment/UpdatePackageInstaller) - 从命令行在 Sitecore 中安装更新包.
- [Sitecore Package Deployer](https://github.com/HedgehogDevelopment/SitecorePackageDeployer) - 使用 Sitecore 作业自动从 Sitecore 服务器上的文件系统文件夹部署更新包.
- [Simplified testing of package installations](https://github.com/michaellwest/test-sitecore-packages) - 通过将包转换为 WDP 并安装来确认包安装.

## Pipelines

- [Pipeline Performance Monitor](https://github.com/ParTech/Pipeline-Performance-Monitor) - 用于测量 Sitecore 管道执行持续时间的简单解决方案.
- [Sitecore Processor Dependency Injection](https://github.com/coreyasmith/Sitecore.ProcessorDi) - 演示 Sitecore 管道处理器中的依赖项注入的简单项目.

## Publishing

- [Scheduled Publishing](https://github.com/HedgehogDevelopment/SCScheduledPublishing) - 为内容编辑者提供延迟在未来某个时间点发布项目的选项.
- [AdvancedPublishDialog](https://github.com/Sitecore/AdvancedPublishDialog) - 增强的标准发布对话框.
- [Publishing Service Azure Templates](https://github.com/coreyasmith/sitecore-publishing-service-azure-templates) - 用于在 Sitecore Azure PaaS 环境中安装 Sitecore 发布服务的 ARM 模板以及用于创建必要的 Web 部署包的脚本.
- [SIF scripts to install Publishing Service](https://github.com/KayeeNL/sitecore-sif-autoinstall-publishingservice) - Powershell 脚本均使用 Sitecore 安装框架 (SIF) 自动安装发布服务并在 ContentManagement 实例或独立实例之上自动安装发布模块. 
- [Publish Viewer](https://github.com/mikeedwards83/Glass.PublishViewer) - 允许您监控 Sitecore Publishing CM 服务器上的发布队列，查看其当前状态并在需要时取消发布作业（即排队时间、发布作业启动时间、队列中的持续时间、发布的项目数、平均发布时间）一个项目，来自发布作业的所有消息）.
- [Sitecore Power Publish](https://github.com/robhabraken/sitecore-power-publish)  - 强制发布项目的“发布”按钮，无论“发布”限制中“项目”选项卡上的“可发布”选项的状态如何.  1) 此功能不会发布您网站中未发布的链接页面，而只会发布项目字段中使用的媒体库项目和数据源等资源，因为需要这些资源才能正确显示您要发布的项目. 此方法甚至会发布当前项目使用的模板和布局（如果尚未完成）.  2) 取消发布按钮使您只需单击一下即可取消发布项目. 它将更改发布限制，因为它取消选中“项目”选项卡上的“可发布”选项，然后使用不带子项目的完整重新发布来发布该项目.  3) 发布状态按钮显示所有发布目标的发布状态. 如果发布目标是最新的，则会显示绿点. 如果该项目已发布到发布目标，但该项目随后发生了更改，则会显示一个橙色点（因此它已发布，但不是最新的）. 如果当前项目根本不存在于发布目标中，则会显示红点. 此功能使内容编辑者能够针对每个发布目标详细检查内容是否已发布.

## Rules

- [Page Rules](https://github.com/marek-musielak/Marek.Musielak.PageRules)  - 为访问者浏览的每个页面创建任何自定义 Sitecore 规则. 用户尚未阅读条款和条件页面并想查看竞赛页面？ 页面应该只能在特定日期之后访问？ 您想使用 GEO IP 数据自动更改主页的语言吗？ 您还没有为您的页面准备好翻译吗？ 有了 Sitecore 规则引擎，天空才是极限！
- [ItemNamingRules](https://github.com/seankearney/Sitecore-ItemNamingRules)  - 为规则引擎提供条件和操作以自动执行项目名称约定. 您可以使用 ItemNamingRules 项目在内容树的不同分支中应用不同的项目命名规则.
- [MenuItemRules](https://github.com/jammykam/Konabos.SharedSource.MenuItemRules) - 基于规则的上下文项菜单可见性.
- [Sitecore adaptive rules](https://github.com/boro2g/sitecore-adaptive-rules) - 添加了对 Sitecore 规则引擎自适应规则的支持：当条件和操作的属性相互依赖时，它们非常有用.
- [Organize Insert Options Rules](https://github.com/coreyasmith/OrganizeInsertOptionsRules) - uiGetMasters 管道的管道处理器，允许您在内容树中按照您喜欢的方式组织插入选项规则.
- [Conditional Placeholder Settings](https://github.com/matthewkenny/ConditionalPlaceholderSettings) - 允许 Sitecore 规则引擎支持 Sitecore 附带的现有占位符设置功能的模块.
- [Sitecore Adaptive Rules](https://github.com/adamconn/sitecore-adaptive-rules) - 添加规则引擎对自适应规则的支持（当条件和操作的属性相互依赖时，这些规则很有用）.

## Security

- [Securty Headers](https://github.com/GuitarRich/SXA.SecurityHeaders) - 展示如何在 SXA 示例上实现响应安全标头，但它们确实是 Helix 通用的.
- [SI Snitch](https://github.com/KayeeNL/SI-Snitch)  - 一种调试工具，用于在从 Sitecore Identity 转换这些声明后读取从 Sitecore Identity 传递到 Sitecore 的声明. 它有助于识别 Sitecore 正在获取的声明（以及以何种格式）并确保 Sitecore Identity 中的组转换得到正确处理.
- [MasterKey](https://github.com/islaytitans/MasterKey) - 用于解锁 Sitecore 项目的模块.
- [Security Rights Reporting](https://github.com/jbluemink/Sitecore-Security-Rights-Reporting) - 一个模块，以友好的方式显示所有用户及其所有权限的网格，并带有导出选项.
- [Sitecore Delete Access Rights](https://github.com/mikaelnet/sitecore-access-rights)  - 启用“item:removeVersion”访问权限，允许作者删除单个项目版本，而不允许作者删除整个项目. 它还允许项目的初始创建者删除他/她自己的项目，除非对该项目应用了明确的拒绝删除访问权限.
- [ASP.NET 2.0 Membership Database as Identity Server User Store](https://github.com/Sitecore/sitecore-identityserver-contrib-membership) - 根据包含现有系统用户数据的现有 ASP.NET 2.0 成员数据库验证用户登录名和密码.
- [Certz](https://github.com/michaellwest/certz) - 基于 .net 7 构建的实用程序，并编译为独立的 exe，旨在简​​化证书管理，作为 mkcert 的更好替代品.

## SEO

- [301 Redirect Module](https://github.com/thecadams/301RedirectModule) - Sitecore 301 重定向模块的改进版本.
- [SitecoreSitemapXML](https://github.com/JimmieOverby/SitecoreSitemapXML) - 生成符合 sitemaps.org 定义的架构的站点地图并将其提交给搜索引擎.
- [Sitemap Generator](https://github.com/jermdavis/SitemapGenerator) - 用于生成站点地图的 Sitecore / FakeDB / TDS / Cloud Build 项目示例.
- [Sitecore Solr](https://github.com/bigredmachine/sitecore-solr) - 有关如何扩展 Sitecore Solr 提供程序的示例代码.
- [URL Rewriter Module](https://github.com/ParTech/Url-Rewriter) - 使管理员或编辑者能够从 Sitecore 客户端管理 URL 重写规则，支持主机名、相对 URL 和绝对 URL 的重写.
- [RedirectManager](https://github.com/AlexanderDavyduk/Sitecore-RedirectManager) - Sitecore 的重定向管理器.
- [URL Rewrite](https://github.com/iamandycohen/UrlRewrite) - 重定向/重写模块的站点特定版本.

## Serialization

- [Rainbow](https://github.com/SitecoreUnicorn/Rainbow) - Sitecore 的高级序列化库，旨在完全替代 Sitecore 序列化格式和文件系统组织，并支持跨源项目比较.
- [Unicorn](https://github.com/SitecoreUnicorn/Unicorn) - Sitecore 的实用程序，通过将 Sitecore 项目的序列化副本与代码一起写入磁盘来解决在 Sitecore 实例之间移动模板、渲染和其他数据库项目的问题 - 这样，就可以得到给定代码库所需数据库项目的副本在源代码控制中伴随它.
- [Sidekick](https://github.com/JeffDarchuk/SitecoreSidekick) - 基于 AngularJS 的微服务架构操作框架.
- [Rhino](https://github.com/kamsar/Rhino) - Sitecore 的实验性序列化数据提供程序.

## Sitecore Host

- [Sitecore Host Quick Start](https://github.com/sitecoreguild/SitecoreHostQuickStart/tree/develop) - 一组基本模板，可帮助您开始构建自己的 Sitecore Host 应用程序.
- [Hostbase](https://github.com/muso31/Hostbase)  - Sitecore Host 示例解决方案，可用作 Sitecore Host 应用程序的起点. 目前作为插件在 IdentityServer Host 中运行，当独立 Sitecore Host 应用程序变得可用时将进行更新.
- [Sitecore Host Plugins](https://github.com/JuliusAngwenyi/SitecoreHostPlugins) - 用于扩展 Sitecore Identity Server 的 Sitecore 主机插件.
- [Basic Sitecore Host Application](https://github.com/georgechang/schost-basic) - 显示演示网页的基本 Sitecore Host 应用程序.

## SPE (Sitecore PowerShell Extension)

- [Sitecore PowerShell Book](https://github.com/SitecorePowerShell/Book) - Sitecore PowerShell 书籍，包含所有文档.
- [Sitecore PowerShell](https://github.com/SitecorePowerShell) - Sitecore PowerShell Initiative 官方 GitHub.
- [Sitecore.Utilities](https://github.com/alan-null/Sitecore.Utilities) - 一组用于 Sitecore PowerShell 扩展的小模块.
- [SPE Content Migrator](https://github.com/michaellwest/Spe-Content-Migrator) - 用于使用 SPE 在 Sitecore 实例之间迁移内容的脚本.

## SPEAK

- [Speak 3 starter template](https://github.com/Mitya88/SitecoreSpeak3StarterProject) - 使用 Angular CLI 版本 1.2.7 生成的 Speak 3 入门模板.
- [Sitecore Speak UI Library](https://github.com/Mitya88/SitecoreSpeakUILibrary) - Speak 3 使用 Angular CLI 版本 1.2.7 生成的组件.
- [SitecoreDataImporter](https://github.com/komainu85/SitecoreDataImporter) - SPEAK 应用程序可将 CSV / JSON / XML 导入 Sitecore 项目.

## SXA (Sitecore Experience Accelerator)

- [Sitecore Experience Accelerator index](https://github.com/alan-null/SXA.Index) - 关于SXA的整套文档.
- [SXA Styleguide](https://github.com/markvanaalst/SXA.Styleguide) - 基于 SXA 的教育网站，有助于解释内部工作原理并说明最佳实践.
- [SXA.Styleguide.Frontend](https://github.com/markvanaalst/SXA.Styleguide.Frontend)  - 存储库包含运行站点所需的所有前端代码. 它由两部分组成，SXA 主题和网站上使用的 Scriban 模板. 此存储库中使用的文件夹结构模仿 SXA Creative Exchange 输出，因此您可以找到主题和单独的抄写模板的来源.
- [SXA.Foundation.Variants](https://github.com/MartinMiles/SXA.Foundation.Variants) - 自定义 SXA 渲染变体和其他一些可能对您的解决方案有帮助的有用内容的集合.
- [SXA Reference](https://github.com/alan-null/XA.Reference) - 基于 Sitecore Experience Accelerator 构建的示例 Sitecore 项目.
- [SXA.HealthCheck](https://github.com/alan-null/SXA.HealthCheck) - 用于确定 SXA 站点健康状态的 Power Shell 脚本，由验证步骤组成，每个步骤检查 SXA 解决方案中的不同内容并提供可能的解决方案.
- [Global Field Validator](https://github.com/JeffDarchuk/SxaGlobalFieldValidator) - SXA 模块，用于在站点级别而不是模板字段级别验证字段.
- [Scriban syntax coloring and auto completion](https://github.com/AdamNaj/SitecoreScriban-vscode) - Visual Studio Code 已知对象扩展的 Scriban 语法着色和智能感知.
- [Westco SXA Extensions](https://github.com/michaellwest/westco-sxa-extensions) - Sitecore 体验加速器 (SXA) 扩展.
- [docker-sxa-node](https://github.com/michaellwest/docker-sxa-node) - 演示在安装了 Node 的 Docker 容器中使用 SXA CLI.
- [SXA Securty Headers](https://github.com/GuitarRich/SXA.SecurityHeaders) - 展示如何在 SXA 示例上实现响应安全标头，但它们确实是 Helix 通用的.
- [SXA.Platform.Assemblies](https://github.com/konabos/SXA.Platform.Assemblies) - SXA 的程序集列表回到 v1.6 和 Powershell 脚本来生成您自己的.

## Testing

- [Sitecore FakeDb](https://github.com/sshushliapin/Sitecore.FakeDb)  - Sitecore 的单元测试框架，支持在内存中创建和操作 Sitecore 内容. 它旨在最大限度地减少测试内容初始化的工作量，将重点放在最小的测试数据而不是全面的内容树表示上.
- [Minq](https://github.com/valtech/minq) - 对 Sitecore 和 Sitecore MVC 的 Mockable、LINQable 支持.

## Templates

- [Token Set](https://github.com/retohugi/SitecoreExtension-TokenSet) - 为 Sitecore 数据模板提供额外的标准值标记，包括未来日期并通过执行查询获取值.

## Tooling

- [Terminal DevEx Improvements](https://github.com/Sitecore/Windows-Terminal-DevEx-improvements) - Sitecore 品牌的 Windows Termial 和 VS Code 主题和配置文件，可解锁用于使用 XM Cloud 的有用工具，例如自动完成、命令历史列表和目录改进.

## Universal Tracker

- [UniversalTracker SDK](https://github.com/Sitecore/Sitecore.UniversalTracker.MobileSDK) - .Net 标准库，为客户端 .NET 应用程序提供交互和事件编写 API，充当连接 Universal Tracker 服务和应用程序的接口，让用户使用本机对象而不是 HTTP 请求和 JSON 响应.

## WebApi

- [Sitecore Endpoints](https://github.com/MartinMiles/Sitecore.Endpoints) - 以 Helix 功能形式实现的可供选择和使用的 Sitecore 服务客户端和 Sitecore WebApi 示例.
- [Odata.SitecoreExample](https://github.com/ianjohngraham/Odata.SitecoreExample) - Sitecore oData 存储库的示例.
- [Web API Session-Enabled Routes](https://github.com/coreyasmith/WebApiEnableSessionHandler) - Sitecore 管道处理器和 HttpRouteCollection 扩展，以在 Web API 2 中启用会话.
- [Sitecore Shared Source: Web API Client](https://github.com/thinkfreshnick/SitecoreSharedSource) - Sitecore WebAPI 客户端.
- [Sitecore Services Client Publish](https://github.com/peplau/SscPublish) - 一种 Web API 方法，用于安全触发 Sitecore 发布项目或树.

## Workflows

- [DynamicWorkflows](https://github.com/ivansharamok/DynamicWorkflows) - 基于规则引擎的工作流管理工具.

## xConnect and xDB

- [XConnectTutorial](https://github.com/jst-cyr/XConnectTutorial) - 基于 Sitecore 文档的教程存储库，根据 Martina Welander 在“入门”教程和其他优秀文档中的代码，引导用户完成与 xConnect API 的常见交互.
- [XConnectHelper](https://github.com/lowedown/xConnectHelper)  - 用于调试 xConnect 的瑞士军刀. 特点：洞察当前跟踪会话数据； 显示上次页面查看时触发的目标和事件； 验证 xConnect 设置（连接、证书、设置）的状态检查器； 设置当前会话中的标识符和基本联系人数据； 刷新当前会话以立即处理.
- [XdbTracker](https://github.com/lowedown/XdbTracker) - API 和 js 函数允许客户端触发 Sitecore 事件/目标和结果.
- [Experience Generator](https://github.com/Sitecore/xGenerator) - 为具有可配置模式的 Sitecore 网站生成“逼真”的流量.
- [xconnect-odata-proxy](https://github.com/ianjohngraham/xconnect-odata-proxy) - 一个简单的 Node.js 代理，用于访问 Sitecore 9 中的 xConnect 的 oData API.
- [xConnectDeployer](https://github.com/boro2g/xConnectDeployer) - 可用于部署 Marketing Automation Engine 的示例控制台应用程序.
- [Right To Be Forgotten](https://github.com/steviemcg/SitecoreComms.RTBF) - 用于营销自动化操作的“执行被遗忘的权利”插件.

## XM Cloud

- [Next.js Styleguide for XM Cloud](https://github.com/sitecorelabs/XmCloudNextJsJssStyleguide) - 旨在帮助开发人员快速学习和开始使用 Sitecore 容器、Sitecore Next.js SDK 和 Sitecore 内容序列化的解决方案.
- [Play Summit](https://github.com/Sitecore/Sitecore.Demo.XmCloud.PlaySummit) - 播放 Summit 演示，其中包含 XM Cloud、Content Hub DAm、CMP、带有 Versel 托管的 Next.js 等.
- [XM Cloud Starter Kit](https://github.com/sitecorelabs/xmcloud-foundation-head) - 旨在帮助开发人员快速学习和入门 XMCLoud + SXA + Next.js 的解决方案.
- [XM Cloud Introduction](https://github.com/Sitecore/XM-Cloud-Introduction) - 由 Sitecore 技术营销团队管理的一系列 XM Cloud 站点的代码库：新的 MVP 网站以及 3 个 SUGCON 活动网站.
