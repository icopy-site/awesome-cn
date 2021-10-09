<div class="github-widget" data-repo="thangchung/awesome-dotnet-core"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome .NET Core [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

灵感来自 [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

总是欢迎贡献！ 请看一下 [contribution guidelines](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md) 页面第一. 我们也接受专有和商业软件.

谢谢大家 [contributors](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors) ，你太棒了，没有你就不可能！ 目标是建立一个由社区驱动的非常知名资源的分类集合.

看看我 [blog](https://medium.com/@thangchung) 或者打个招呼 [Twitter](https://twitter.com/thangchung)!


  * [Code Analysis and Metrics](#code-analysis-and-metrics)  

## General

* [ASP.NET Core Documentation](https://docs.asp.net/en/latest/) - 官方 ASP.NET Core 文档站点.
* [.NET Core Documentation](https://docs.microsoft.com/en-us/dotnet/articles/welcome) - Home of the technical documentation for .NET Core, C#, F# and Visual Basic, including basic concepts, getting started instructions, tutorials and samples.
* [.NET Core SDK](https://www.microsoft.com/net/core) - .NET Core SDK 是由 Microsoft 和 .NET 社区维护的通用开发平台 [GitHub](https://github.com/dotnet/core).
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/1719a3fe2a5c81b67a4909787da4a02fb0d0d419/Documentation/architecture/net-platform-standard.md) - .NET 旧版本和新版本的区别.
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - 对 .NET Standard 2.0 将要发生的事情的描述以及当前 .NET Standard 某些缺失部分的路线图.
* [Clean Code .NET/.NET Core](https://github.com/thangchung/clean-code-dotnet) - 适用于 .NET / .NET Core 的清洁代码概念.

## Frameworks, Libraries and Tools

### API

* [autorest](https://github.com/Azure/autorest) - Swagger (OpenAPI) Specification code generator featuring C# and Razor templates. Supports C#, Java, Node.js, TypeScript, Python and Ruby. `4.5.x or above`
* [aspnet-api-versioning](https://github.com/Microsoft/aspnet-api-versioning) - 一组将服务 API 版本控制添加到 ASP.NET Web API、带有 ASP.NET Web API 的 OData 和 ASP.NET Core 的库.
* [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) - ASP.NET Core 速率限制中间件.
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) - 使用 Kestrel 和 Consul 的 API 冷凝器/反向代理，包括轻量级的 consul 库.
* [Flurl](https://github.com/tmenier/Flurl) - 用于 .NET 的流畅 URL 构建器和可测试的 HTTP [https://flurl.dev](https://flurl.dev).
* GraphQL
  * [Dapper.GraphQL](https://github.com/landmarkhw/Dapper.GraphQL) - 一个旨在集成 Dapper 和 graphql-dotnet 项目的库，将易用性和性能作为主要关注点.
  * [graphql-aspnetcore](https://github.com/JuergenGutsch/graphql-aspnetcore) - 用于创建 GraphQL 端点的 ASP.NET Core MiddleWare.
  * [graphql-convention](https://github.com/graphql-dotnet/conventions) - 该库是顶部的一个补充层，允许您使用现有的属性 getter 和方法作为字段解析器自动将 .NET 类包装到 GraphQL 模式定义中
  * [graphiql-dotnet](https://github.com/JosephWoodward/graphiql-dotnet) - 用于 ASP.NET Core 的 GraphiQL 中间件.
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) - 基于 .NET Core 的 GraphQL [https://github.com/graphql/graphql-js](https://github.com/graphql/graphql-js).
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - 用于 .NET 的 GraphQL.
  * [graphql-dotnet-server](https://github.com/graphql-dotnet/server) - 用于 .NET 的 GraphQL - 订阅传输 WebSockets.
  * [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) - 用于 .Net Core 和 .NET Framework 的 GraphQL 服务器.
  * [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL) - Facebook GraphQL 查询语言的 FSharp 实现 [https://fsprojects.github.io/FSharp.Data.GraphQL](https://fsprojects.github.io/FSharp.Data.GraphQL).
  * [parser](https://github.com/graphql-dotnet/parser) - .NET 中 GraphQL 的词法分析器和解析器.
  * [tanka-graphql](https://github.com/pekkah/tanka-graphql) - GraphQL 执行和服务器库，支持 SignalR、Apollo、模式操作以及 Apollo 和 graphql-js 中熟悉的其他功能
* [halcyon](https://github.com/visualeyes/halcyon) - ASP.NET 的 HAL 实现.
* [JSON API .NET Core](https://github.com/Research-Institute/json-api-dotnet-core) - 构建 json:api 兼容 API 的框架，目标是消除 RESTful 样板.
* [LightNode](https://github.com/neuecc/LightNode) - 基于 OWIN 构建的微型 RPC/REST 框架 [http://neuecc.github.io/LightNode](http://neuecc.github.io/LightNode).
* [NetCoreStack.Proxy](https://github.com/NetCoreStack/Proxy) - .NET Standard 2.0 的类型安全分布式 REST 库（NetCoreStack Flying Proxy）
* [NSwag](https://github.com/RSuter/NSwag) - 用于 .NET、Web API 和 TypeScript 的 Swagger/OpenAPI 工具链. [http://NSwag.org](http://NSwag.org).
* [OData](https://github.com/OData/WebApi/tree/feature/netcore) - 开放数据协议 (OData) 支持创建基于 HTTP 的数据服务，允许使用统一资源标识符 (URI) 标识并在抽象数据模型中定义的资源由 Web 客户端使用简单的 HTTP 消息发布和编辑.
* [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) - OpenAPI Generator allows generation of API client libraries (e.g. C#, TypeScript, etc), server stubs (ASP.NET Core, NancyFx, etc), documentation and configuration automatically given an OpenAPI Spec (v2, v3).
* [refit](https://github.com/paulcbetts/refit) - Xamarin 和 .NET 的自动类型安全 REST 库.
* [RestClient.Net](https://github.com/MelbourneDeveloper/RestClient.Net) - Cross Platform REST Client for all C# platforms
* [RestEase](https://github.com/canton7/RestEase) - 易于使用的类型安全 REST API 客户端库，简单且可定制.
* [RestLess](https://github.com/letsar/RestLess) - .Net Standard 的自动类型安全无反射 REST API 客户端库.
* [Restier](https://github.com/OData/RESTier) - RESTier 是一个 RESTful API 开发框架，用于在 .NET 平台上构建标准化的、基于 OData V4 的 RESTful 服务.
* [Restsharp](https://github.com/restsharp/RestSharp) - 用于 .NET 的简单 REST 和 HTTP API 客户端
* [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) - 无缝地为 WebApi 项目添加了招摇.
  * [MicroElements.Swashbuckle.FluentValidation](https://github.com/micro-elements/MicroElements.Swashbuckle.FluentValidation) - 将 FluentValidation 规则添加到 swagger.
  * [Swashbuckle.AspNetCore.Filters](https://github.com/mattfrear/Swashbuckle.AspNetCore.Filters) - 一堆有用的 Swashbuckle.AspNetCore 过滤器.
* [WebAnchor](https://github.com/mattiasnordqvist/Web-Anchor) - Web Anchor 提供对 Web 资源的类型安全、可测试和灵活的、运行时生成的访问.
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core) - ASP.NET Core 的社区贡献.

### Application Frameworks
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate)  - ASP.NET Boilerplate 是一个通用应用程序框架，专为新的现代 Web 应用程序设计. 它使用熟悉的工具并围绕它们实施最佳实践，为您提供可靠的开发体验.
* [Abp vNext](https://github.com/abpframework/abp) - Abp vNext 是下一代的开源 [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) 框架. 它是创建现代 Web 应用程序的完整架构和强大的基础设施！
遵循最佳实践和约定，为您提供可靠的开发体验.
* [AsyncEx](https://github.com/StephenCleary/AsyncEx) - async/await 的辅助库.
* [Aeron.NET](https://github.com/AdaptiveConsulting/Aeron.NET) - 高效可靠的 UDP 单播、UDP 多播和 IPC 消息传输 - Aeron 的 .NET 端口.
* [akka.net](https://github.com/akkadotnet/akka.net) - 用于在 .NET 和 Mono 上构建高并发、分布式和容错事件驱动应用程序的工具包和运行时.
* [Aggregates.NET](https://github.com/volak/Aggregates.NET) - Aggregates.NET 是一个框架，可以帮助开发人员将优秀的 NServiceBus 和 EventStore 库集成在一起.
* [ASP.NET MVC](https://github.com/dotnet/aspnetcore/tree/master/src/Mvc) - 模型视图控制器框架，用于构建具有明确关注点分离的动态网站，包括合并的 MVC、Web API 和带有 Razor 的网页.
* [Butterfly Server .NET](https://github.com/firesharkstudios/butterfly-server-dotnet)  - 允许以最少的努力构建实时 Web 应用程序和本机应用程序. 定义一个 Web API 和订阅 API，用于在连接的客户端之间自动同步数据集.
* [CAP](https://github.com/dotnetcore/CAP) - 具有本地持久消息功能的 EventBus，用于 SOA 或微服务架构中的系统集成.
* [Carter](https://github.com/CarterCommunity/Carter) - Carter 是一个允许 Nancy-esque 路由与 ASP.Net Core 一起使用的库.
* [Chromely](https://github.com/mattkol/Chromely) - Electron.NET 的轻量级替代品，Electron for .NET/.NET Core.
* [Cinchoo ETL](https://github.com/Cinchoo/ChoETL) - .NET 的 ETL 框架（CSV、Flat、Xml、JSON、Key-Value 格式文件的解析器/编写器）.
* [CQRSlite](https://github.com/gautema/CQRSlite) - Lightweight framework for helping writing CQRS and Eventsourcing applications in C#.
* [dataaccess_aspnetcore](https://github.com/digipolisantwerp/dataaccess_aspnetcore) - DataAccess Toolbox 包含使用工作单元和存储库模式使用 Entity Framework Core 1.0 在 ASP.NET Core 中进行数据访问的基类.
* [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore) - 用于构建基于 ASP.NET Core 的高质量 Web 应用程序的轻量级和可扩展基础设施.
* [DotNetCorePlugins](https://github.com/natemcmaster/DotNetCorePlugins) - .NET Core 库，用于将程序集作为插件加载.
* [DotnetSpider](https://github.com/dotnetcore/DotnetSpider)  - DotnetSpider，一个类似于 WebMagic 和 Scrapy 的 .NET 标准网络爬虫库. 它是一个轻量级、高效、快速的 .NET 高级网络爬取和抓取框架.
* [DotNetty](https://github.com/Azure/DotNetty) - netty 端口，事件驱动的异步网络应用框架.
* [dotvvm](https://github.com/riganti/dotvvm) - 用于 Web 应用程序的开源 MVVM 框架.
* [ElectronNET](https://github.com/ElectronNET/Electron.NET) - 使用 ASP.NET NET Core 构建跨平台桌面应用程序.
* [EmbedIO](https://github.com/unosquare/embedio) - 适用于 .NET Framework 和 .NET Core 的小型、跨平台、基于模块的 Web 服务器.
* [Ether.Network](https://github.com/aloisdg/Ether.Network) - Ether.Network 是一个开源网络库，允许开发人员通过 TCP/IP 协议创建简单、快速和可扩展的套接字服务器或客户端应用程序.
* [EventFlow](https://github.com/eventflow/EventFlow) - .NET 的 Async/await 第一个 CQRS+ES 和 DDD 框架.
* [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - Lightweight and fast library written in C# for reading Microsoft Excel files.
* [ExtCore](https://github.com/ExtCore) - 免费、开源和跨平台的框架，用于创建基于 ASP.NET Core 1.0 的模块化和可扩展的 Web 应用程序.
* [Finbuckle.MultiTenant](https://github.com/Finbuckle/Finbuckle.MultiTenant)  - Finbuckle.MultiTenant 是一个 .NET Standard 库，用于支持 ASP.NET 2.0+ 的多租户支持. 它提供租户解析、按租户应用配置和按租户数据隔离的功能.
* [fission](https://github.com/fission/fission) - Kubernetes 的快速无服务器功能.
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp)  - 远程过程调用 (RPC) 为构建分布式应用程序和服务提供了有用的抽象. 此存储库中的库提供了基于 HTTP/2 的 gRPC 协议的具体实现. 这些库支持使用受支持语言的任意组合在客户端和服务器之间进行通信.
* [Halibut](https://github.com/OctopusDeploy/Halibut) - 使用 JSON-RPC over SSL 的 .NET 安全通信堆栈.
* [MagicOnion](https://github.com/neuecc/MagicOnion) - 基于 gRPC 的 HTTP/2 RPC 流框架，适用于 .NET、.NET Core 和 Unity.
* [MassTransit](https://github.com/MassTransit/MassTransit) - .NET 的分布式应用程序框架. 
* [microdot](https://github.com/gigya/microdot) - 一个开源的 .NET 微服务框架.
* [MoreLINQ](https://github.com/morelinq/MoreLINQ) - LINQ to Objects 的扩展.
* [Nancy](https://github.com/NancyFx/Nancy) - 用于在 .NET 和 Mono 上构建基于 HTTP 的服务的轻量级、低仪式性的框架.
* [opencvsharp](https://github.com/shimat/opencvsharp) - OpenCV 的 .NET Framework 包装器.
* [orleans](https://github.com/dotnet/orleans) - 提供构建分布式大规模计算应用程序的直接方法的框架，无需学习和应用复杂的并发或其他扩展模式.
* [Prism](https://github.com/PrismLibrary/Prism) - Prism 是一个框架，用于在 WPF、Windows 10 UWP 和 Xamarin Forms 中构建松散耦合、可维护和可测试的 XAML 应用程序.
* [protoactor-dotnet](https://github.com/AsynkronIT/protoactor-dotnet) - 用于 Golang 和 C 的超快速分布式 actor# [http://proto.actor](http://proto.actor).
* [resin](https://github.com/kreeben/resin) - 具有 HTTP API 和可插拔读/写管道的 16 位宽向量空间搜索引擎.
* [RService.io](https://github.com/Stoom/RService.IO) - 专注于速度和易用性的 ASP.Net Core RESTful 微服务框架.
* [ServiceStack](https://github.com/ServiceStack/ServiceStack) - 为所有人精心设计、速度极快、令人愉悦的网络服务 [https://servicestack.net](https://servicestack.net).
* [Steeltoe OSS](https://github.com/SteelToeOSS) - 用于常见微服务模式的 .NET 工具包.
* [Strathweb.TypedRouting.AspNetCore](https://github.com/filipw/Strathweb.TypedRouting.AspNetCore) - 在 ASP.NET Core MVC 项目中启用强类型路由的库.
* [surging](https://github.com/dotnetcore/surging)  - Surging 是一个微服务引擎，提供轻量级、高性能、模块化的 RPC 请求管道. 服务引擎支持 http、TCP、WS、Mqtt、UDP 和 DNS 协议. 它使用ZooKeeper和Consul作为注册中心，Hash算法，随机，轮询，压力最小优先级作为负载均衡算法，内置服务治理，保证RPC通信可靠.
* [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0.
* [X.PagedList](https://github.com/dncuug/X.PagedList) - 用于在 ASP.NET/ASP.NET Core 中轻松分页任何 IEnumerable/IQueryable 的库.

### Application Templates
* [.NET Boxed](https://github.com/Dotnet-Boxed/Templates)  - 包含电池的项目模板，提供让您前进所需的最少代码. 包括 ASP.NET Core API 和 GraphQL 模板.
* [aspnet-core-react-template](https://github.com/bradymholt/aspnet-core-react-template) - ASP.NET Core 2.0 / React SPA 模板应用程序.
* [AspNetCoreSpa](https://github.com/asadsahi/AspNetCoreSpa) - 带有 Angular CLI 全功能应用程序的 Asp.Net Core 2+ 和 Angular 6 SPA.
* [ASP.NET-MVC-Template](https://github.com/NikolayIT/ASP.NET-MVC-Template) - 用于 ASP.NET MVC 5 和 ASP.NET Core 的现成模板，其中包含存储库、服务、模型映射以及 DI 和 StyleCop 警告.
* [AddFeatureFolders](https://github.com/OdeToCode/AddFeatureFolders) - 在 ASP.NET Core 中为 MVC 控制器和视图启用功能文件夹.
* [Angular Visual Studio Webpack Starter](https://github.com/damienbod/AngularWebpackVisualStudio)  - 用于 Webpack、Visual Studio、ASP.NET Core 和 Angular 的模板. 应用程序的客户端和服务器端都在一个 ASP.NET Core 项目中实现，这使得部署更加容易.
* [CleanArchitecture](https://github.com/ardalis/CleanArchitecture)  - 使用 ASP.NET Core 清洁架构的起点.  Clean Architecture 只是松散耦合、依赖倒置架构的一系列名称中的最新一个. 您还会发现它命名为六边形、端口和适配器或洋葱式架构.
* [CleanArchitecture (SPA)](https://github.com/JasonGT/CleanArchitecture) - 遵循清洁架构原则，使用 Angular 8 和 ASP.NET Core 3 创建单页应用程序 (SPA) 的解决方案模板
* [DNTFrameworkCoreTemplate](https://github.com/rabbal/DNTFrameworkCoreTemplate) - 基于的样板项目模板 [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore)
* [dotnet new caju](https://github.com/ivanpaulovich/dotnet-new-caju)  - 具有出色架构风格的 dotnet 新模板！ 提高设计基于 Hexagonal、Clean 或 Event Sourcing 架构风格的分层应用程序的生产力. 它支持多种数据访问框架（MongoDB、EntityFramework、Dapper 或 Kafka），并且完全可测试.
* [EISK](https://github.com/EISK/eisk.webapi) - 为开发人员资源提供简单的用例，以在 .NET Core 之上构建可扩展的应用程序 [architectural best practices](https://docs.microsoft.com/en-us/dotnet/standard/modern-web-apps-azure-architecture/common-web-application-architectures) （DDD，洋葱架构等）
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices) - Microsoft ASP.NET Core JavaScript 服务.
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core) - 用于构建现代 Web 应用程序的 HTML5、基于 jQuery 的小部件库. [http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui).
* [QuickApp](https://github.com/emonney/QuickApp) - 具有完整登录、用户和角色管理的 ASP.NET Core / Angular4 启动项目模板.
* [Serenity](https://github.com/volkanceylan/Serenity) - Serenity 是一个 ASP.NET MVC / TypeScript 应用程序平台，旨在通过基于服务的架构来简化和缩短以数据为中心的业务应用程序的开发.
* [Toucan](https://github.com/mrellipse/toucan)  - 用于构建单页应用程序的样板. 服务器是围绕 SOLID 原则设计的多项目 .Net Core 解决方案. 客户端是 TypeScript 2、Vuejs 2、Vuex 2.

### Authentication and Authorization
* [AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) - 用于 OWIN/Katana 和 ASP.NET Core 的 OpenID Connect/OAuth2 服务器框架.
* [Auth0](https://github.com/auth0/auth0.net) - 用于现代身份的托管企业级平台.
* [Casbin.NET](https://github.com/casbin-net/Casbin.NET) - 支持访问控制模型的授权库，如 C 中的 ACL、RBAC、ABAC#
* [Identity](https://github.com/aspnet/Identity) - ASP.NET Core Identity 是用于构建 ASP.NET Core Web 应用程序的会员系统，包括会员、登录和用户数据.
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) - 用于 ASP.NET Core 1.0 和 2.0 的 IdentityServer
  * [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework) - EntityFramework 持久层
  * [IdentityServer4.MongoDB](https://github.com/diogodamiani/IdentityServer4.MongoDB) - MongoDB 持久层
  * [IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - 实体框架核心持久层
  * [IdentityServer4.Templates](https://github.com/IdentityServer/IdentityServer4.Templates) - dotnet cli templates for IdentityServer4.
* [Okta](https://github.com/okta/okta-aspnet) - 用于现代身份的托管企业级平台.
* [openiddict](https://github.com/openiddict/openiddict-core) - 用于 ASP.NET Core 的易于使用的 OpenID Connect 服务器.
  * [oidc-debugger](https://github.com/nbarbettini/oidc-debugger) - OAuth 2.0 和 OpenID Connect 调试工具.
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - 建造 [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) 使用 Stormpath 和 ASP.NET Core. 
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - 建造 [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) 使用 Stormpath 和 ASP.NET Core.（已弃用：在加入 OKTA 后，它将在 2017 年 3 月更新） 
* [stuntman](https://github.com/ritterim/stuntman) - 在开发过程中利用 ASP.NET Identity 模拟用户的库.

### Blockchain
* [BTCPayServer](https://github.com/btcpayserver/btcpayserver) - 与 Bitpay API 兼容的跨平台、自托管服务器.
* [Meadow](https://github.com/MeadowSuite/Meadow) - 一个集成的以太坊实施和工具套件，专注于 Solidity 测试和开发.
* [NBitcoin](https://github.com/MetacoSA/NBitcoin) - .NET 框架的综合比特币库.
* [NBlockchain](https://github.com/danielgerlag/NBlockchain) - 用于构建支持区块链的应用程序的 .NET 标准库
* [NBXplorer](https://github.com/dgarage/NBXplorer) - 比特币和山寨币轻量级区块浏览器.
* [NEO](https://github.com/neo-project/neo) - 智能经济的开放网络.
* [Nethereum](https://github.com/Nethereum) - 将以太坊的爱带到 .NET.
* [Nethermind](https://github.com/NethermindEth/nethermind) - .NET Core 以太坊客户端
* [StratisBitcoinFullNode](https://github.com/stratisproject/StratisBitcoinFullNode) - Simple and affordable end-to-end solutions for development, testing and deployment of native C# blockchain applications on the .Net framework.
* [Trezor.Net](https://github.com/MelbourneDeveloper/Trezor.Net) - Cross platform C# library for talking to the Trezor Hardwarewallet
* [WalletWasabi](https://github.com/zkSNACKs/WalletWasabi) - 注重隐私，符合 ZeroLink 标准的比特币钱包.

### Bot
* [BotSharp](https://github.com/SciSharp/BotSharp) - The Open Source AI Chatbot Platform Builder in 100% C# Running in .NET Core with Machine Learning algorithm.
* [NadekoBot](https://github.com/Kwoth/NadekoBot) - Open source, general-purpose Discord chat bot written in C#.
* [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) - C# Telegram Bot API library.
* [Funogram](https://github.com/Dolfik1/Funogram) - F# Telegram Bot Api library.

### Build Automation
* [cake-build](https://github.com/cake-build/cake) - 跨平台构建自动化系统.
* [CatLight](https://catlight.io)  - 用于监视项目中的构建和任务的开发人员的状态通知程序. 使用 .Net Core 和 Electron 构建.
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) - Style your C# console output!
* [dotnet-docker](https://github.com/dotnet/dotnet-docker) - 用于 .NET Core 和 .NET Core 工具的基础 Docker 映像.
* [Dockerize.NET](https://github.com/brthor/Dockerize.NET) - .NET Cli 工具将您的 .NET Core 应用程序打包到 docker 映像中：“dotnet dockerize”
* [FlubuCore](https://github.com/dotnetcore/FlubuCore) - A cross platform build and deployment automation system for building projects and executing deployment scripts using C# code.
* [GitInfo](https://github.com/kzu/GitInfo) - Git and SemVer Info from MSBuild, C# and VB.
* [GitVersioning](https://github.com/AArnott/Nerdbank.GitVersioning) - 使用来自单个简单 version.txt 文件的版本标记您的程序集和 NuGet 包，并包含用于非官方构建的 git commit ID.
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet) - .NET Core 运行时的包装器.
* [Image2Docker](https://github.com/docker/communitytools-image2docker-win) - PowerShell 模块，可将现有的 Windows 应用程序工作负载移植到 Docker.
* [LocalAppVeyor](https://github.com/joaope/LocalAppVeyor) - 在本地运行您的 AppVeyor 构建.
* [msbuild](https://github.com/Microsoft/msbuild) - Microsoft Build Engine 是一个用于构建应用程序的平台.
* [Nuke](https://github.com/nuke-build/nuke) - 跨平台构建自动化系统.
* [Opserver](https://github.com/opserver/Opserver) - Stack Exchange 的监控系统.
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) - Visual Studio Team Services 构建和发布代理.

### Bundling and Minification
* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) - Visual Studio 扩展，可让您配置 JS、CSS 和 HTML 文件的捆绑和缩小.
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine) - ASP.NET MVC ViewEngine for rendering markup in a JavaScript environment. Ideal for React and Angular server-side rendering.
* [Smidge](https://github.com/Shazwazza/Smidge/) - 用于 ASP.NET Core 的轻量级运行时 CSS/JavaScript 文件缩小、组合、压缩和管理库.
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin)  - 包含一组标记缩小器的 .NET 库. 该项目的目标是通过减少 HTML、XHTML 和 XML 代码的大小来提高 Web 应用程序的性能.

### Caching
* [CacheManager](https://github.com/MichaCo/CacheManager) - Open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. [http://cachemanager.michaco.net](http://cachemanager.michaco.net)
* [EasyCaching](https://github.com/dotnetcore/EasyCaching) - 开源缓存库，包含缓存的基本用法和一些高级用法，可以帮助我们更轻松地处理缓存.
* [Faster](https://github.com/Microsoft/FASTER/tree/master/cs) - 来自 Microsoft Research 的快速键值存储.
* [Foundatio](https://github.com/exceptionless/Foundatio) - 用于构建分布式应用程序的可插拔基础块.
* [Microsoft Caching](https://github.com/aspnet/Caching) - 用于内存缓存和分布式缓存的库.
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) - High performance general purpose redis client for .NET languages (C# etc).

### CMS
* [Awesome-CMS-Core](https://github.com/SaiGonSoftware/Awesome-CMS-Core) - Awesome CMS Core 是一个使用 ASP.Net Core 和 ReactJS 构建的开源 CMS，考虑到模块分离问题，并提供了最新的技术趋势，如 .Net Core、React、Webpack、SASS、后台作业、消息队列.
* [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core) - ASP.NET 应用程序提供常见的博客功能.
* [Cofoundry](https://github.com/cofoundry-cms/cofoundry)  - 开源 .NET Core CMS 和模块化应用程序框架. 代码优先，不显眼且可扩展.
* [CoreWiki](https://github.com/csharpfritz/CoreWiki) - 我们在实时编码流期间正在处理的简单 ASP.NET Core wiki.
* [dasblog-core](https://github.com/poppastring/dasblog-core) - 使用 ASP.NET Core 重新构想的原始 DasBlog
* [Miniblog](https://github.com/madskristensen/Miniblog.Core) - 一个 ASP.NET Core 博客引擎.
* [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS)  - 一个开源的 ASP.NET Core 2.0 CMS. 目前支持 MySQL 并计划实现 MSSQL、SQLite 和 PostgreSQL. 它也是一个模块化的 CMS，支持主题、皮肤、自定义布局、小部件、多语言（En、BN）.
* [Piranha CMS](https://github.com/piranhacms/piranha.core) - 用于 ASP.NET Core 和 Entity Framework Core 的轻量级和不显眼的开源 CMS.
* [Platformus](https://github.com/Platformus) - 基于 ASP.NET Core 1.0 和 ExtCore 框架的免费、开源和跨平台 CMS.
* [Squidex](https://github.com/Squidex/squidex) - 基于 MongoDB、CQRS 和事件溯源的无头 CMS.
* [Swastika I/O Core CMS](https://github.com/Swastika-IO/Swastika-IO-Core)  - 开源 ASP.NET Core 2.x CMS. 目前支持MS SQL，并计划在不久的将来实现MSSQL、SQLite. 它具有许多开箱即用的内置功能，例如多语言支持、主题、模板...
* [Umbraco](https://github.com/umbraco/umbraco-cms) - 一个可扩展且友好的开源 ASP.NET Core CMS
* [Weapsy](https://github.com/Weapsy/Weapsy)  - 基于 DDD 和 CQRS 的开源 ASP.NET Core CMS. 它开箱即用地支持 MSSQL、MySQL、SQLite 和 PostgreSQL.
* [ZKEACMS](https://github.com/SeriaWei/ZKEACMS.Core) - Visual design, build site onlie by drag and drop.

### Code Analysis and Metrics
* [awesome-static-analysis](https://github.com/mre/awesome-static-analysis) - 各种编程语言的静态分析工具、linter 和代码质量检查器的精选列表.
* 代码分析
  * [CodeFormatter](https://github.com/dotnet/codeformatter) - 使用 Roslyn 自动重写源代码以遵循 netfx 编码样式的工具. [Nuget Package](https://www.nuget.org/packages/Dotnet.CodeFormatter.BuildTask.Fork) 
  * [DevSkim](https://github.com/Microsoft/DevSkim) - 一组提供安全“linting”功能的 IDE 插件和规则.
  * [RefactoringEssentials](https://github.com/icsharpcode/RefactoringEssentials) - 重构 Visual Studio 的要点.
  * [roslyn-analyzers](https://github.com/dotnet/roslyn-analyzers) - .NET 编译器平台（“Roslyn”）分析器.
  * [StyleCopAnalyzers](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) - 使用 .NET 编译器平台的 StyleCop 规则.
* 指标
  * [AppMetrics](https://github.com/alhardy/AppMetrics) - App Metrics 是一个开源的跨平台 .NET 库，用于记录和报告应用程序中的指标并报告其运行状况.
  * [Audit.NET](https://github.com/thepirat000/Audit.NET) - 用于审核 .NET 对象更改的小型框架.
  * [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) - 用于基准测试的强大 .NET 库.
  * [coverlet](https://github.com/tonerdo/coverlet) - .NET Core 的跨平台代码覆盖库.
  * [Foundatio](https://github.com/exceptionless/Foundatio#metrics) - 具有内存、redis、StatsD 和 Metrics.NET 实现的通用接口.
  * [MiniCover](https://github.com/lucaslorentz/minicover) - .NET Core 的极简代码覆盖工具.
  * [NBench](https://github.com/petabridge/NBench) - .NET 应用程序的性能基准测试和测试框架.
  * [Nexogen.Libraries.Metrics](https://github.com/nexogen-international/Nexogen.Libraries.Metrics) - 用于在 .NET 中收集应用程序指标并将其导出到 Prometheus 的库.
  * [OpenCover](https://github.com/OpenCover/opencover) - .NET 2 及更高版本的代码覆盖工具（仅限 WINDOWS 操作系统），支持 32 和 64 进程，同时具有分支和序列点.
  * [PerformanceMonitor](https://github.com/dotnet-architecture/PerformanceMonitor) - .NET Core 应用程序性能监视器.
  * [prometheus-net](https://github.com/prometheus-net/prometheus-net) - .NET 客户端 [https://prometheus.io](https://prometheus.io).
  * [Prometheus.Client](https://github.com/PrometheusClientNet/Prometheus.Client) - .NET 客户端 [Prometheus](https://prometheus.io).
  	* [Prometheus.Client.MetricPusher](https://github.com/PrometheusClientNet/Prometheus.Client.MetricPusher) - 将指标推送到 Prometheus.Client 的 PushGateaway.
  	* [Prometheus.Client.AspNetCore](https://github.com/PrometheusClientNet/Prometheus.Client.AspNetCore) - Prometheus.Client 的中间件.
  	* [Prometheus.Client.MetricServer](https://github.com/PrometheusClientNet/Prometheus.Client.MetricServer) - Prometheus.Client 的 MetricServer.
  	* [Prometheus.Client.HttpRequestDurations](https://github.com/PrometheusClientNet/Prometheus.Client.HttpRequestDurations) - Prometheus.Client 请求持续时间的指标记录.

### Compression
* [lz4net](https://github.com/MiloszKrajewski/K4os.Compression.LZ4) - 适用于所有 .NET 平台的超快速压缩算法.
* [sharpcompress](https://github.com/adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats.

### Compilers, Transpilers and Languages
* [Fable](https://github.com/fable-compiler/Fable) - F# to JavaScript Compiler.
* [fparsec](https://github.com/stephan-tolksdorf/fparsec) - A parser combinatory library for F# and C#.
* [IL2C](https://github.com/kekyo/IL2C) - A translator for ECMA-335 CIL/MSIL to C language.
* [Mond](https://github.com/Rohansi/Mond) - A dynamically typed scripting language written in C# with a REPL, debugger, and simple embedding API.
* [peachpie](https://github.com/peachpiecompiler/peachpie) - .NET 的开源 PHP 编译器.
* [Pidgin](https://github.com/benjamin-hodgson/Pidgin) - A lightweight, fast and flexible parsing library for C#, developed at Stack Overflow.
* [roslyn](https://github.com/dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs.
* [Sprache](https://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework.

### Cryptography
* [BCrypt.Net](https://github.com/BcryptNet/bcrypt.net) - 对原始 bcrypt 包进行更新.
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core) - 用于安全存储密码的 BCrypt.NET 的 .NET Core 端口.
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols.
* [multiformats](https://github.com/multiformats/cs-multihash) - 一个通用哈希库，但一个用于编码/解码 Multihashes 的库，它是一个“容器”，描述了计算摘要的哈希算法.
* [nsec](https://github.com/ektrah/nsec) - NSec 是一个新的基于 libsodium 的 .NET Core 加密库.
* [SecurityDriven.Inferno](https://github.com/thangchung/awesome-dotnet-core/blob/master/github.com/sdrapkin/SecurityDriven.Inferno) - 使用 .Net 原语的高级加密库，已经过专业审计.

### Database
* [DBreeze](https://github.com/hhblaze/DBreeze) - C# .NET MONO NOSQL (key value store embedded) ACID multi-paradigm database management system.
* [JsonFlatFileDataStore](https://github.com/ttu/json-flatfile-datastore) - 简单的 JSON 平面文件数据存储，支持类型化和动态数据.
* [LiteDB](https://github.com/mbdavid/LiteDB) - .NET NoSQL 文档存储在单个数据文件中 - [http://www.litedb.org](http://www.litedb.org).
* [NoDb](https://github.com/joeaudette/NoDb) - "no database" file system storage for .NET Core/ASP.NET Core because not every project needs a database.
* [marten](https://github.com/JasperFx/marten) - Postgresql 作为 .NET 应用程序的文档数据库和事件存储 [http://jasperfx.github.io/marten](http://jasperfx.github.io/marten).
* [StringDB](https://github.com/SirJosh3917/StringDB) - StringDB 是一个模块化的、键/值对档案数据库，旨在消耗*微小*数量的内存并生成*微小*数据库.
* [yessql](https://github.com/sebastienros/yessql) - 在任何 RDBMS 上工作的 .NET 文档数据库.

### Database Drivers
* [cassandra-csharp-driver](https://github.com/datastax/csharp-driver) - DataStax C# Driver for Apache Cassandra.
* [confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet) - Confluent 的 Apache Kafka .NET 客户端.
* [couchbase-lite-net](https://github.com/couchbase/couchbase-lite-net) - 用于 .NET 的轻量级、面向文档 (NoSQL)、可同步的数据库引擎.
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) - 用于 MongoDB 的 .NET 驱动程序.
* [MongoDB.Entities](https://github.com/dj-nitehawk/MongoDB.Entities) - MongoDB 的数据访问库，具有优雅的 api、LINQ 支持和内置实体关系管理
* MySQL
  * [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/8.0) - Connector/Net 是用于 MySQL 的完全托管的 ADO.NET 驱动程序.
  * [MySqlConnector](https://github.com/mysql-net/MySqlConnector) - 用于 .NET 和 .NET Core 的异步 MySQL 连接器.
* Neo4j
  * [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) - 用于 .NET 的 Neo4j Bolt 驱动程序.
  * [Neo4jClient](https://github.com/Readify/Neo4jClient) - Neo4j 的 .NET 客户端绑定.
* [npgsql](https://github.com/npgsql/npgsql) - .NET data provider for PostgreSQL. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) - 为 .NET 启用 Linq 的文档数据库.
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) - C#/.NET RethinkDB driver with 100% ReQL API coverage.
* [progaudi.tarantool](https://github.com/progaudi/progaudi.tarantool) - Tarantool NoSql 数据库的.NET 客户端.

### Database Tools and Utilities
* [DbUp](https://github.com/DbUp/DbUp)  - .NET 库，可帮助您将更改部署到 SQL Server 数据库. 它跟踪已经运行了哪些 SQL 脚本，并运行更新数据库所需的更改脚本.
* [Evolve](https://github.com/lecaillon/Evolve)  - 使用普通 SQL 脚本的简单数据库迁移工具. 灵感来自飞路.
* [EFCorePowerTools](https://github.com/ErikEJ/EFCorePowerTools) - Entity Framework Core Power Tools - EF Core 的逆向工程、迁移和模型可视化.
* [fluentmigrator](https://github.com/fluentmigrator/fluentmigrator) - .NET 的迁移框架很像 Ruby on Rails 迁移.
* [monitor-table-change-with-sqltabledependency](https://github.com/christiandelbianco/monitor-table-change-with-sqltabledependency) - 获取有关记录表更改的 SQL Server 通知.
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData) - 具有 OLAP 操作和数据透视表数据模型的内存中数据立方体.
* [roundhouse](https://github.com/chucknorris/roundhouse) - Database Migration Utility for .NET using sql files and versioning based on source control.
* [SapphireDb](https://github.com/SapphireDb/SapphireDb)  - SapphireDb 的服务器实现，这是一个用于轻松开发具有实时数据同步的应用程序的框架，并且是用于 asp.net 核心和 ef 核心的 firebase 实时数据库/firestore 的自托管替代方案. 查看文档以获取更多详细信息： [Documentation](https://sapphire-db.com)
* [SharpRepository](https://github.com/SharpRepository/SharpRepository) - SharpRepository is a generic repository written in C# which includes support for various relational, document and object databases including Entity Framework, RavenDB, MongoDb and Db4o. SharpRepository includes Xml and InMemory repository implementations as well.
* [TrackableEntities.Core](https://github.com/TrackableEntities/TrackableEntities.Core) - 使用 .NET Core 跨服务边界进行更改跟踪.
* [Mongo.Migration](https://github.com/SRoddis/Mongo.Migration) - Mongo.Migration 专为 [MongoDB C# Driver](https://github.com/thangchung/awesome-dotnet-core/blob/master/ https://github.com/mongodb/mongo-csharp-driver) 轻松、即时地迁移您的文档. 架构迁移不再有停机时间. 只需编写小而简单的迁移. [Link](https://github.com/thangchung/awesome-dotnet-core/blob/master/ https://github.com/SRoddis/Mongo.Migration)
* [EntityFrameworkCore.DataEncryption](https://github.com/Eastrall/EntityFrameworkCore.DataEncryption) - Microsoft.EntityFrameworkCore 插件，用于使用内置或自定义加密提供程序添加对加密字段的支持.

### Date and Time
* [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions) - DateTimeRange、工作日和各种 DateTime、DateTimeOffset、TimeSpan 扩展方法.
* [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime)  - 允许您编写更清晰的 DateTime 表达式和操作. 部分灵感来自 Ruby DateTime Extensions.
* [nodatime](https://github.com/nodatime/nodatime) - 更好的 .NET 日期和时间 API [http://nodatime.org](http://nodatime.org).

### Distributed Computing
* [AspNetCore.Diagnostics.HealthChecks](https://github.com/xabaril/AspNetCore.Diagnostics.HealthChecks) - ASP.NET Core 诊断包的企业健康检查
  - [BeatPulse](https://github.com/Xabaril/BeatPulse) - 启用负载平衡器以监控已部署的 Web 应用程序的状态
* [Foundatio](https://github.com/exceptionless/Foundatio) - 用于构建分布式应用程序的可插拔基础块
* [jasper](https://github.com/JasperFx/jasper) - .NET 的下一代应用程序开发框架
* [Rafty](https://github.com/ThreeMammals/Rafty) - .NET Core 中的 RAFT 共识
* [Obvs](https://github.com/christopherread/Obvs) - 一个可观察的微服务总线 .NET 库，它将底层传输封装在基于 Rx 的简单接口中
* [Ocelot](https://github.com/ThreeMammals/Ocelot) - 使用 .NET Core 创建的 API 网关
* [OpenTracing](https://github.com/opentracing/opentracing-csharp) - 供应商中立的 API 和用于分布式跟踪的工具
* [Polly](https://github.com/App-vNext/Polly) - .NET 3.5 / 4.0 / 4.5 / PCL 库，允许开发人员以流畅的方式表达瞬时异常和故障处理策略，例如重试、永远重试、等待和重试或断路器
* [ProxyKit](https://github.com/damianh/ProxyKit) - 在 ASP.NET Core 上创建代码优先的 HTTP 反向代理的工具包

### E-Commerce and Payments
* [nopCommerce](https://github.com/nopSolutions/nopCommerce) - 免费的开源电子商务购物车（ASP.NET MVC / ASP.NET Core MVC），拥有庞大的社区和充满新功能、主题和插件的市场.
* [GrandNode](https://github.com/grandnode/grandnode) - 基于 ASP.NET Core 2.1 和衍生自 MongoDB 的多平台、免费、开源电子商务购物车 [nopCommerce](https://github.com/nopSolutions/nopCommerce).
* [PayPal](https://github.com/paypal/PayPal-NET-SDK) - 用于 PayPal RESTful API 的 .NET SDK.
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) - 建立在 .NET Core 上的超级简单的电子商务系统.
* [Stripe](https://github.com/ServiceStack/Stripe) - 用于 stripe.com REST API 的类型化 .NET 客户端.


### Exceptions
* [Demystifier](https://github.com/benaadams/Ben.Demystifier) - 对堆栈跟踪的高性能理解（使错误日志更高效）.
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - 无异常的 .NET 客户端
* [GlobalExceptionHandlerDotNet](https://github.com/JosephWoodward/GlobalExceptionHandlerDotNet) - GlobalExceptionHandlerDotNet 允许您将异常处理配置为 ASP.NET Core 应用程序管道的约定，而不是在每个控制器操作中显式处理它们.
* [Sentry](https://github.com/getsentry/sentry-dotnet) - Sentry 的 .NET SDK，这是一种开源错误跟踪，可帮助开发人员实时监控和修复崩溃.

### Functional Programming
* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) - Functional Extensions for C#.
* [DynamicData](https://github.com/RolandPheasant/DynamicData) - 基于 Rx.NET 的反应式集合.
* [echo-process](https://github.com/louthy/echo-process) - Actor library for C# with additional modules that support persistence to Redis, as well as JS integration.
* [FsCheck](https://github.com/fscheck/FsCheck) - .NET 的随机测试.
* [Giraffe](https://github.com/dustinmoris/Giraffe) - A native functional ASP.NET Core web framework for F# developers.
* [language-ext](https://github.com/louthy/language-ext) - C# functional language extensions and 'Erlang like' concurrency system.
* [LaYumba.Functional](https://github.com/la-yumba/functional-csharp-code) - Utility library for programming functionally in C#.
* [NetMQ.ReactiveExtensions](https://github.com/NetMQ/NetMQ.ReactiveExtensions)  - 使用 Reactive Extensions (RX) 在网络上的任何地方轻松发送消息. 传输协议是 ZeroMQ.
* [Optional](https://github.com/nlkl/Optional) - A robust option type for C#.
* [reactive-streams-dotnet](https://github.com/reactive-streams/reactive-streams-dotnet) - [Reactive Streams](http://www.reactive-streams.org/) 对于.NET.
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - 与 Reactive Extensions for .NET 集成的 MVVM 框架，以创建可在任何移动或桌面平台上运行的优雅、可测试的用户界面.
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) - 这 [Reactive Extensions](http://reactivex.io) 对于.NET.
* [Qactive](https://github.com/RxDave/Qactive)  - 反应式可查询可观察框架.  `4.xx 或以上`
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/)  - 函数式反应式编程 (FRP) 库.  `4.xx 或以上`

### Graphics
* [GLFWDotNet](https://github.com/smack0007/GLFWDotNet) - GLFW 的 .NET 绑定.
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) - 围绕 System.Drawing 的流畅包装器，用于处理图像文件 [http://imageprocessor.org](http://imageprocessor.org) .  `4.5.x 或更高版本`
* [ImageSharp](https://github.com/SixLabors/ImageSharp) - Cross-platform library for processing of image files written in C#.
* [LibVLCSharp](https://github.com/videolan/libvlcsharp)：libvlc 的 .NET/Mono 绑定，支持 VideoLAN 制作的 VLC 应用程序的多媒体框架.
* [Magick.NET](https://github.com/dlemstra/Magick.NET) - ImageMagick 的 .NET 库.
* [MagicScaler](https://github.com/saucecontrol/PhotoSauce) - 用于 .NET 的 MagicScaler 高性能、高质量图像处理管道
* [QRCoder](https://github.com/codebude/QRCoder) - A pure C# Open Source QR Code implementation.
* [SharpBgfx](https://github.com/MikePopoloski/SharpBgfx) - C# bindings for the bgfx graphics library.
* [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching) - 用于支持 .NET Core 的 .NET 应用程序的图像处理库.
* [veldrid](https://github.com/mellinoe/veldrid) - 用于 .NET 的低级硬件加速 3D 图形库.
* [ZXing.Net](https://github.com/micjahn/ZXing.Net/) - 原始基于java的条码阅读器和生成器库zxing的.Net端口.

### GUI
* [AdonisUI](https://github.com/benruehl/adonis-ui) - 用于 WPF 应用程序的轻量级 UI 工具包，提供经典但增强的 Windows 视觉效果.
* [Avalonia](https://github.com/AvaloniaUI/Avalonia) - 多平台 .NET UI 框架（以前称为 Perspex）.
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) - 基于 Avalonia 的文本编辑器组件从 [AvalonEdit](https://github.com/icsharpcode/AvalonEdit)
 [HandyControls](https://github.com/ghost1372/HandyControls) - 包含一些简单且常用的 WPF 控件.
* [Lara](https://github.com/integrativesoft/lara) - Lara Web Engine 是一个用 C 语言开发 Web 用户界面的库#
* [ShellProgressBar](https://github.com/Mpdreamz/shellprogressbar) - 在控制台程序中创建进度条的库
* [Qml.Net](https://github.com/pauldotknopf/Qml.Net) - Mono/.NET/.NET Core 的跨平台 Qml/.NET 集成.
* [WinApi](https://github.com/prasannavl/WinApi) - 一个简单、直接、超薄的 CLR 库，用于具有自动化、窗口、DirectX、OpenGL 和 Skia 助手的高性能 Win32 Native Interop.

### IDE
* [Mono](https://github.com/mono/monodevelop) - MonoDevelop 使开发人员能够在 Linux、Windows 和 Mac OS X 上快速编写桌面和 Web 应用程序.它还使开发人员能够轻松地将使用 Visual Studio 创建的 .NET 应用程序移植到 Linux 和 Mac OS X，维护所有平台的单一代码库.
* [rider](https://www.jetbrains.com/rider/) - Cross-platform C# IDE based on the IntelliJ platform and ReSharper.
* [Omnisharp](http://www.omnisharp.net/) - 一系列开源项目，每个项目都有一个目标：在您选择的编辑器中实现出色的 .NET 体验.
* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) - SharpDevelop is a free Integrated Development Environment (IDE) for C#, VB.NET, Boo, IronPython, IronRuby and F# projects on Microsoft's .NET platform. It is written (almost) entirely in C#, and comes with features you would expect in an IDE plus a few more.
* [Visual Studio Code](https://github.com/Microsoft/vscode)  - 一种新型工具，将代码编辑器的简单性与开发人员的核心编辑-构建-调试周期所需的内容相结合. 代码提供全面的编辑和调试支持、可扩展性模型以及与现有工具的轻量级集成.
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - 为个人开发者、开源项目、学术研究、教育和小型专业团队提供免费编辑器.

### Internationalization
* [Localization](https://github.com/aspnet/Localization) - ASP.NET Core 应用程序的本地化抽象和实现.
* [NetCoreStack.Localization](https://github.com/NetCoreStack/Localization) - 带有实体框架和内存缓存的 .NET Core 数据库资源本地化
* [Westwind.Globalization](https://github.com/RickStrahl/Westwind.Globalization) - Database driven resource localization for .NET applications.

### IOC
* [AutoDI](https://github.com/Keboo/AutoDI) - 使用 IL 编织的超快速编译时依赖注入.
* [Autofac](https://github.com/autofac/Autofac) - 令人上瘾的 .NET IoC 容器.
* [Castle.Windsor](https://github.com/castleproject/Windsor) Castle Windsor 是可用于 .NET 的同类最佳、成熟的控制反转容器.
* [DryIoc](https://github.com/dadhi/DryIoc) - 用于 .NET 的快速、小巧、功能齐全的 IoC 容器.
* [Grace](https://github.com/ipjohnson/Grace) - Grace 是一个功能丰富的依赖注入容器，其设计考虑了易用性和性能.
* [Inyector](https://github.com/davidrevoledo/Inyector) - AspNetCore 的依赖注入自动化
* [Lamar](https://github.com/JasperFx/lamar) - Roslyn Chicanery 的控制工具和杂项的快速反转.
* [LightInject](https://github.com/seesharper/LightInject) - 超轻量级 IoC 容器.
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) - 简单、灵活、快速的依赖注入库，促进最佳实践，引导开发人员走向成功的坑.
* [Stashbox](https://github.com/z4kn4fein/stashbox) - 基于 .NET 的解决方案的轻量级、可移植依赖注入框架.
* [Unity](https://github.com/unitycontainer/unity) - 轻量级、可扩展的依赖注入容器.

### Logging
* [common-logging](https://github.com/net-commons/common-logging) - .NET 的便携式日志抽象.
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) - 具有 UDP 和 Redis 传输的 .NET Core 应用程序的 Logstash 日志记录扩展.
* [ElmahCore](https://github.com/ElmahCore/ElmahCore) - 错误日志库，包括错误过滤和从网页查看错误日志等功能.
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - 无异常的 .NET 客户端
* [Foundatio](https://github.com/exceptionless/Foundatio#logging) - 一个流畅的日志 API，可用于在整个应用程序中记录消息.
* [Karambolo.Extensions.Logging.File](https://github.com/adams85/filelogger) - 为内置 .NET Core 日志框架 (Microsoft.Extensions.Logging) 实现文件日志记录的轻量级库.
* [LibLog](https://github.com/damianh/LibLog) - 单个文件供您复制/粘贴或通过 nuget 安装到您的库/框架/应用程序中，以提供日志抽象.
* [log4net](https://github.com/apache/logging-log4net) - log4net 是优秀的 Apache log4j™ 框架到 Microsoft® .NE​​T 运行时的端口.
* [NLog](https://github.com/NLog/NLog) - 高级 .NET、Silverlight 和 Xamarin 日志记录，支持结构化和非结构化日志记录.
  * [NLog for ASP.NET and ASP.NET Core](https://github.com/NLog/NLog.Web) - ASP.NET 和 ASP.NET Core 1-3 的 NLog 集成
  * [NLog.Extensions.Logging](https://github.com/NLog/NLog.Extensions.Logging) - 用于 Microsoft.Extensions.Logging 的 NLog 提供程序，用于 .NET Standard 库和 .NET Core 应用程序
  * [NLog.Windows.Forms](https://github.com/NLog/NLog.Windows.Forms) - 特定于 Windows.Forms 的 NLog 目标
  * [NLog.MailKit](https://github.com/NLog/NLog.MailKit) - 使用使用 MailKit 库的替代邮件目标
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) - 用于构建 ASP.NET Core 日志记录的日志附加程序，以将所有日志发送到 Application Insights.
* [serilog](https://github.com/serilog/serilog) - 具有完全结构化事件的简单 .NET 日志记录.
  * [serilog-aspnetcore](https://github.com/serilog/serilog-aspnetcore) - ASP.NET Core 2+ 的 Serilog 集成.
  * [Serilog.Exceptions](https://github.com/RehanSaeed/Serilog.Exceptions) - Serilog.Exceptions 是一个附加组件 [Serilog](https://serilog.net/) 记录未在 Exception.ToString() 中输出的异常详细信息和自定义属性.
  * [Serilog.Settings.Configuration](https://github.com/serilog/serilog-settings-configuration) - 从 Microsoft.Extensions.Configuration 读取的 Serilog 配置提供程序.
* [SEQ](https://getseq.net) - Seq 通过 HTTP 收集数据，而您的应用程序使用适用于您平台的最佳可用结构化日志 API.

### Machine Learning and Data Science
* [Accord](https://github.com/accord-net/framework) - .NET 的机器学习、计算机视觉、统计和通用科学计算.
* [Catalyst](https://github.com/curiosity-ai/catalyst) 受 spaCy 启发的跨平台自然语言处理 (NLP) 库，具有预训练模型、对训练词和文档嵌入的开箱即用支持以及灵活的实体识别模型. 的一部分 [SciSharp Stack](https://scisharp.github.io/SciSharp/)
* [ML.NET](https://github.com/dotnet/machinelearning) - 跨平台开源机器学习框架，使 .NET 开发人员可以使用机器学习 [http://dot.net/ml](http://dot.net/ml).
* [Spreads](https://github.com/Spreads/Spreads/) - 用于数据流实时和探索性分析的系列和面板.
* [TensorFlowSharp](https://github.com/migueldeicaza/TensorFlowSharp) - 用于 .NET 语言的 TensorFlow API.
* [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) - 在量子力学思想的帮助下，从单个示例生成 itmap 和 tilemap.
* [SiaNet](https://github.com/SciSharp/SiaNet) - A C# deep learning library, human friendly, CUDA/OpenCL supported, well structured, easy to extend 

### Mail
* [FluentEmail](https://github.com/lukencode/FluentEmail) - 适用于 .NET 和 .NET Core 的多合一电子邮件发件人
* [MailBody](https://github.com/doxakis/MailBody) - 使用流畅的界面 (.NET) 创建交易电子邮件.
* [MailKit](https://github.com/jstedfast/MailKit) - 用于 IMAP、POP3 和 SMTP 的跨平台 .NET 库.
* [MailMergeLib](https://github.com/axuno/MailMergeLib) - SMTP 邮件客户端库，为文本、内嵌图像和附件提供舒适的邮件合并功能，以及良好的吞吐量和发送邮件消息的容错能力.
* [MimeKit](https://github.com/jstedfast/MimeKit) - 跨平台的 .NET MIME 创建和解析器库，支持 S/MIME、PGP、DKIM、TNEF 和 Unix mbox 线轴.
* [netDumbster](https://github.com/cmendible/netDumbster)  - 用于测试的 .Net Fake SMTP 服务器. 流行的 Dumbster 的克隆.
* [Papercut](https://github.com/ChangemakerStudios/Papercut) - 简单的桌面 SMTP 服务器
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [SendGrid Client](https://github.com/0xdeafcafe/sendgrid-dotnet) - C# library for the SendGrid v3 mail endpoint.
* [SmtpServer](https://github.com/cosullivan/SmtpServer) - 用于创建您自己的 SMTP 服务器的库.
* [StrongGrid](https://github.com/Jericho/StrongGrid)  - SendGrid v3 API 的客户端. 不仅允许您发送电子邮件，还允许您批量导入联系人、管理列表和细分、为您的列表创建自定义字段等.还包括一个 SendGrid Webhooks 解析器.

### Mathematics
* [UnitConversion](https://github.com/Stratajet/UnitConversion) - .NET Core 和 .NET Framework 的可扩展单位转换库.
* [AutoDiff](https://github.com/alexshtf/autodiff) - 一个提供数学函数快速、准确和自动微分（计算导数/梯度）的库.

### Media
* [MetadataExtractor](https://github.com/drewnoakes/metadata-extractor-dotnet) - 使用简单易用的 API 从媒体（图像、视频、音频）中提取元数据.

### Misc
* [AdvanceDLSupport](https://github.com/Firwood-Software/AdvanceDLSupport)  - 用于改进 P/Invoke-ing 本机代码的库. 与本机对象交互，就好像它们是一流的对象一样.
* [AngleSharp](https://github.com/AngleSharp/AngleSharp)  - 终极尖括号解析器库. 它解析 HTML5、MathML、SVG 和 CSS 以构建基于 W3C 官方规范的 DOM. 可与python的beautifulsoup4相媲美.
* [AgileMapper](https://github.com/agileobjects/AgileMapper) - AgileMapper 是一个零配置、高度可配置的对象-对象映射器，具有可查看的执行计划.
* [AspNetCore Extension Library](https://github.com/sgjsakura/AspNetCore) - ASP.NET 核心扩展库.
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) - .NET 中基于约定的对象-对象映射器.
* [Baget](https://github.com/loic-sharma/BaGet) - 轻量级 NuGet 服务器.
* [Bleak](https://github.com/Akaion/Bleak) - Windows 本机 DLL 注入库.
* [Bullseye](https://github.com/adamralph/bullseye/) - 用于描述和运行目标及其依赖项的 .NET 包.
* [Castle.Core](https://github.com/castleproject/Core) - Castle Core，包括 Castle DynamicProxy、日志服务和 DictionaryAdapter [http://www.castleproject.org](http://www.castleproject.org).
* [Chessie](https://github.com/fsprojects/Chessie) - 面向铁路的 .NET 编程 [http://fsprojects.github.io/Chessie](http://fsprojects.github.io/Chessie).
* [CliWrap](https://github.com/Tyrrrz/CliWrap) - 命令行界面的包装器.
* [commanddotnet](https://github.com/bilal-fazlani/commanddotnet) - 在类中建模您的命令行应用程序界面.
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - The implementation of CommonMark specification in C# for converting Markdown documents to HTML.
* [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt) - 为 .NET 控制台应用程序创建表的流畅库.
* [CoordinateSharp](https://github.com/Tronald/CoordinateSharp) - 一个可以快速格式化和转换地理坐标以及提供基于位置的日月信息（日落、日出、月亮光照等）的库. 
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) - Microsoft ASP.NET 服务器端支持和 jQuery DataTables 助手.
* [DinkToPdf](https://github.com/rdvojmoc/DinkToPdf) - C# .NET Core wrapper for wkhtmltopdf library that uses Webkit engine to convert HTML pages to PDF.
* [dotnet-env](https://github.com/tonerdo/dotnet-env) - 从 .env 文件加载环境变量的 .NET 库.
* [DotNet.Glob](https://github.com/dazinator/DotNet.Glob)  - 用于 .NET / .NETStandard 应用程序的快速通配库. 优于正则表达式.
* [Dotnet outdated](https://github.com/dotnet-outdated/dotnet-outdated) - 用于显示和更新项目中过时的 NuGet 包的 .NET Core 全局工具
* [Dotnet Script](https://github.com/filipw/dotnet-script) - Run C# scripts from the .NET CLI.
* [Dotnet Serve](https://github.com/natemcmaster/dotnet-serve) - 用于 .NET Core CLI 的简单命令行 HTTP 服务器.
* [Downloader](https://github.com/bezzad/Downloader)  - Downloader 是一个现代、流畅、异步、可测试和可移植的 .NET 库. 这是一个具有异步进度事件的多部分下载器.
* [Eighty](https://github.com/benjamin-hodgson/Eighty) - 一个简单的 HTML 生成库
* [Enums.NET](https://github.com/TylerBrinkley/Enums.NET) - Enums.NET 是一个高性能类型安全的 .NET 枚举实用程序库
* [FastExpressionCompiler](https://github.com/dadhi/FastExpressionCompiler) - 用于委托的快速 ExpressionTree 编译器.
* [FluentDocker](https://github.com/mariotoffia/FluentDocker) - 用于 docker、docker-compose 和 docker-machine、win/mac/linux 和本机 docker 的命令、服务和 Fluent API.
* [FluentFTP](https://github.com/robinrodricks/FluentFTP/) - FTP 和 FTPS 客户端，具有广泛的 FTP 命令、SSL/TLS 连接、散列/校验和等.
* [Fody](https://github.com/Fody/Fody) - 用于编织 .net 程序集的可扩展工具
* [HdrHistogram.NET](https://github.com/HdrHistogram/HdrHistogram.NET) - 高动态范围 (HDR) 直方图.
* [httpclient-interception](https://github.com/justeat/httpclient-interception) - 用于拦截服务器端 HTTP 依赖项的 .NET Standard 库.
* [Humanizer](https://github.com/Humanizr/Humanizer) - Humanizer 满足您在 .NET 中操作和显示字符串、枚举、日期、时间、时间跨度、数字和数量的所有需求.
* [Humidifier](https://github.com/jakejscott/Humidifier) - Write and maintain AWS Cloudformation templates using C#.
* [impromptu-interface](https://github.com/ekonbenefits/impromptu-interface)  - 动态实现的静态接口（鸭子铸造）. 将 DLR 与 Reflect.Emit 结合使用.
* [JqueryDataTablesServerSide](https://github.com/fingers10/JqueryDataTablesServerSide) - 用于 Jquery 数据表的 ASP.NET Core 服务器端处理库，具有数据库级别的多列过滤、排序和分页，支持 Excel 导出和 TagHelper.
* [LibSass Host](https://github.com/Taritsyn/LibSassHost) - .NET 包装器 [libSass](http://sass-lang.com/libsass) 能够支持虚拟文件系统的库.
* [markdig](https://github.com/lunet-io/markdig) - 用于 .NET 的快速、强大、符合 CommonMark、可扩展的 Markdown 处理器.
* [NetCoreBeauty](https://github.com/nulastudio/NetCoreBeauty) - 将 .NET Core 应用程序运行时组件和依赖项移动到子目录并使其美观的简单库.
* [NFlags](https://github.com/bartoszgolek/NFlags)  - 简单的库，使解析 CLI 参数变得容易. 图书馆还允许“开箱即用”打印使用帮助.
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) - 将字符串表达式（公式、方法调用、条件）解析为可编译为 lambda 并进行评估的 LINQ 表达式树.
* [NuGet Trends](https://github.com/NuGetTrends/nuget-trends) - 包含 NuGet 包下载计数统计信息的网站.
* [NYoutubeDL](https://gitlab.com/BrianAllred/NYoutubeDL) - A simple youtube-dl library for C#/.NET.
* [Otp.NET](https://github.com/kspearrin/Otp.NET) - An implementation TOTP RFC 6238 and HOTP RFC 4226 in C#.
* [pose](https://github.com/tonerdo/pose) - 用委托替换任何 .NET 方法（包括静态和非虚拟）
* [PuppeteerSharp](https://github.com/kblok/puppeteer-sharp) - Puppeteer Sharp 是官方 Node.JS Puppeteer API 的 .NET 端口.
* [readline](https://github.com/tsolarin/readline) - Pure C# GNU-Readline like library for .NET/.NET Core.
* [ReflectionMagic](https://github.com/ReflectionMagic/ReflectionMagic) - Framework to drastically simplify your private reflection code using C# dynamic
* [Relinq](https://github.com/re-motion/Relinq) - 使用 re-linq，现在可以比以往更轻松地创建功能齐全的 LINQ 提供程序.
* [Remote.Linq](https://github.com/6bee/Remote.Linq) - 远程 Linq 是一个小而易于使用 - 但非常强大 - 库，用于将 LINQ 表达式树转换为强类型、可序列化的表达式树，反之亦然.
* [ReverseMarkdown](https://github.com/mysticmind/reversemarkdown-net) - Html 到 Markdown 转换器库.
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) - PdfReport.Core 是代码优先报告引擎，它构建在 iTextSharp.LGPLv2.Core 和 EPPlus.Core 库之上.
* [Scientist](https://github.com/github/Scientist.net)  - 用于仔细重构关键路径的 .NET 库. 它是 GitHub 的 Ruby Scientist 库的一个端口.
* [Scrutor](https://github.com/khellang/Scrutor) - Microsoft.Extensions.DependencyInjection 的程序集扫描扩展.
* [Sheller](https://github.com/twitchax/Sheller) - 一个 .NET 库，可以让命令变得非常简单流畅.
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) - string.Format 的可扩展替代品.
* 股票
  * [Trady](https://github.com/lppkarl/Trady) - 用于计算技术指标的便捷库，其目标是成为一个自动交易系统，提供股票数据馈送、指标计算、策略构建和自动交易.
* [System.Linq.Dynamic.Core](https://github.com/StefH/System.Linq.Dynamic.Core) - 来自 System Linq 动态功能的 .NET Standard (.NET Core) 版本.
* [UnitsNet](https://github.com/angularsen/UnitsNet) - Units.NET 为您提供所有常用的测量单位以及它们之间的转换.
* 验证
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation) - .NET 的小型验证库，它使用流畅的接口和 lambda 表达式来构建验证规则.
  * [FormHelper](https://github.com/SinanBozkus/FormHelper)  - ASP.NET Core 的表单和验证助手. 表单助手可帮助您创建 ajax 表单和验证，而无需编写任何 javascript 代码.  （与 Fluent 验证兼容）.
  * [Guard](https://github.com/safakgur/guard) - 高性能、可扩展的参数验证库.
  * [Valit](https://github.com/valit-stack/Valit)  - .NET Core 的简单验证. 代码周围不再有 if 语句. 而是编写漂亮干净的流畅验证器！
* [Vanara](https://github.com/dahall/Vanara) - 一组用于 Windows 的 .NET 库，通过支持包装器实现对许多本机 Windows API 的 PInvoke 调用.
* [warden-stack](https://github.com/warden-stack)  - 对您的应用程序、资源和基础设施进行“健康检查”. 保持你的守望者值班.
* [WebEssentials.AspNetCore.ServiceWorker](https://github.com/madskristensen/WebEssentials.AspNetCore.ServiceWorker) - ASP.NET Core 渐进式 Web 应用程序.
* [Xabe.FFmpeg](https://github.com/tomaszzmuda/Xabe.FFmpeg) - .NET Standard wrapper for FFmpeg. It allows to process media without know how FFmpeg works, and can be used to pass customized arguments to FFmpeg from C# application.
* [YoutubeExplode](https://github.com/Tyrrrz/YoutubeExplode) - 用于提取元数据和下载 Youtube 视频和播放列表的终极库.

### Networking
* [AspNetCore.Proxy](https://github.com/twitchax/AspNetCore.Proxy) - ASP.NET Core 代理变得简单.
* [CurlThin](https://github.com/stil/CurlThin) - Lightweight cURL binding library for C# with support for multiple simultaneous transfers through curl_multi interface.
* [NETStandard.HttpListener](https://github.com/StefH/NETStandard.HttpListener) - 用于 .NET Core (NETStandard) 的 HttpListener.
* [Networker](https://github.com/MarkioE/Networker) - 用于 .NET 的简单易用的 TCP 和 UDP 网络库，旨在灵活、可扩展和快速.
* [SharpPcap](https://github.com/chmorgan/sharppcap) - 完全托管的跨平台（Windows、Mac、Linux）.NET 库，用于从实时和基于文件的设备捕获数据包.

### Office
* [EPPlus](https://github.com/EPPlusSoftware/EPPlus) - 使用 .NET 创建高级 Excel 电子表格.
* [npoi](https://github.com/tonyqus/npoi)  - .NET 库，无需安装 Microsoft Office 即可读取/写入 Office 格式. 没有 COM+，没有互操作.
* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK) - Open XML SDK 提供用于处理 Office Word、Excel 和 PowerPoint 文档的工具.

### Operating System
* [CosmosOS](https://github.com/CosmosOS/Cosmos) - Cosmos is an operating system "construction kit". Build your own OS using managed languages such as C#, VB.NET, and more!

### ORM
* [Chloe](https://github.com/shuxinqin/Chloe) - 用于 .NET 的轻量级和高性能对象/关系映射 (ORM) 库.
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) - 熟悉 EF 以前版本的开发人员经验，包括 LINQ、POCO 和 Code First 支持.
  * [EFCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions) - 用于插入更新删除读取 (CRUD) 操作的 EntityFrameworkCore 批量扩展
  * [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus)  - 实体框架实用程序 | 批量操作 | 批量删除 | 批量更新 | 查询缓存 | 查询过滤器 | 查询未来 | 查询包括 | 审计.
  * [EntityFramework.Exceptions](https://github.com/Giorgi/EntityFramework.Exceptions) - 当您的 SQL 查询违反 SqlServer、MySql 或 PostgreSQL 中的数据库约束时，对 EntityFrameworkCore 使用类型化异常.
  * [EntityFramework.Triggers](https://github.com/NickStrupat/EntityFramework.Triggers) - EF 的触发事件.
  * [EntityFramework.Rx](https://github.com/NickStrupat/EntityFramework.Rx) - EF 操作的反应性**热** observables.
  * [Npgsql.EntityFrameworkCore.PostgreSQL](https://github.com/npgsql/Npgsql.EntityFrameworkCore.PostgreSQL) - PostgreSQL 的实体框架核心提供程序.
  * [EntityFramework.PrimaryKey](https://github.com/NickStrupat/EntityFramework.PrimaryKey) - 轻松获取任何实体的主键（包括复合键）.
  * [EntityFramework.TypedOriginalValues](https://github.com/NickStrupat/EntityFramework.TypedOriginalValues) - 获取实体原始值的代理对象（对 Property(&quot;...&quot;).OriginalValue 的类型化访问）.
  * [EntityFramework.VersionedProperties](https://github.com/NickStrupat/EntityFramework.VersionedProperties) - 自动神奇地保留对指定属性更改的审核历史记录的类.
  * [LINQKit](https://github.com/scottksmith95/LINQKit) - LINQ to SQL 和实体框架高级用户的一组免费扩展.
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) - 基于 mysql-net/MySqlConnector 构建的 MySql 实体框架核心提供程序.
  * [spectre.query](https://github.com/spectresystems/spectre.query) - Entity Framework Core 的简单查询语言.
* [Dapper](https://github.com/StackExchange/Dapper) - .NET 的简单对象映射器.
  * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - 提供了一个简单的 API，可以在使用 Dapper 时流畅地将 POCO 属性映射到数据库列.
  * [Dommel](https://github.com/henkmollema/Dommel) - Dapper 的简单 CRUD 操作.
  * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) - CRUD for Dapper.
* [FreeSql](https://github.com/2881099/FreeSql) - dotnet 中方便的 ORM，支持 Mysql、Postgresql、SqlServer、Oracle 和 Sqlite.
* [Limebean](https://nick-lucas.github.io/LimeBean/)  - 混合 ORM，旨在易于使用且不会完全隐藏 SQL，同时具有您期望从 ORM 中获得的所有优点. 受 RedBeanPHP 的启发.
* [LINQ to DB (linq2db)](https://linq2db.github.io/) - 最快的 LINQ 数据库访问库，在 POCO 对象和数据库之间提供了一个简单、轻量级、快速且类型安全的层，适用于 10 多个具有完整 SQL 支持的数据库引擎.
* [nhibernate-core](https://github.com/nhibernate/nhibernate-core) - NHibernate 对象关系映射器.
* [NEventStore](https://github.com/NEventStore/NEventStore)  - 使用事件溯源作为存储机制时，用于抽象不同存储实现的持久性库. 该库是专门针对 DDD/CQRS 应用程序开发的.
* [NPoco](https://github.com/schotime/NPoco)  - 将查询结果映射到 POCO 对象的简单 microORM. 基于 Schotime 的 PetaPoco 分支的项目.
* [NReco.Data](https://github.com/nreco/data) - 用于 SQL 命令生成、CRUD 操作和简单 POCO 映射的轻量级独立于提供者的 DAL.
* [PetaPoco](https://github.com/CollaboratingPlatypus/PetaPoco) - 一个适合你的 POCO 的小 ORM 风格的东西.
* [querybuilder](https://github.com/sqlkata/querybuilder) - SqlKata Query Builder is a powerful Sql Query Builder written in C#.
* [RepoDb](https://github.com/mikependon/RepoDb) - .NET 的混合 ORM 库.
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) - 轻量、简单、快速的基于约定的 POCO ORM.
* [SqlFu](https://github.com/sapiens/SqlFu) - 快速且多功能的 Micro-ORM.
* [SmartSql](https://github.com/Ahoo-Wang/SmartSql) - SmartSql = MyBatis + Cache(Memory | Redis) + ZooKeeper + R/W Splitting +Dynamic Repository ....
* [SQLStreamStore](https://github.com/SQLStreamStore/SQLStreamStore) - Stream Store library targeting SQL based implementations for .NET.

### Profiling
* [Glimpse](https://github.com/Glimpse/Glimpse.Prototype)  - 用于 .NET 的轻量级、开源、实时诊断和洞察分析器.  `不稳定版本`
* [MiniProfiler](https://github.com/MiniProfiler/dotnet) - 用于 ASP.NET 网站的简单但有效的小型分析器.

### Query Builders
* [SqlKata](https://github.com/sqlkata/querybuilder) - 优雅的 Sql 查询生成器，支持复杂查询、连接、子查询、嵌套 where 条件、供应商引擎目标等

### Queue and Messaging
* [emitter](https://emitter.io/)  - 连接所有设备的免费开源实时消息服务. 此发布-订阅消息传递 API 旨在提高速度和安全性.
* [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ) - 用于 RabbitMQ 的易于使用的 .NET API.
* [EventStore](https://github.com/EventStore/EventStore) - 在 JavaScript 中具有复杂事件处理功能的开源函数式数据库.
* [Foundatio](https://github.com/exceptionless/Foundatio#queues) - 具有内存、redis 和 azure 实现的通用接口.
* [MediatR](https://github.com/jbogard/MediatR) - Simple, unambitious mediator implementation in .NET.
 * [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) - Microsoft.Extensions.DependencyInjection 的 MediatR 扩展.
* [Mediator.Net](https://github.com/mayuanyang/Mediator.Net) - 一个简单的 .Net 中介器，用于发送命令、发布事件和请求响应并支持管道.
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) - 用于 .NET 的简单进程内调解器.
* [MQTTnet](https://github.com/chkr1011/MQTTnet) - MQTTnet 是一个高性能的 .NET 库，用于基于 MQTT 的通信.
* [netmq](https://github.com/zeromq/netmq) - 100% native C# implementation of ZeroMQ for .NET.
* [OpenCQRS](https://github.com/OpenCQRS/OpenCQRS)  - 用于 DDD、CQRS 和事件溯源的 .NET Core 库与 Azure 服务总线集成. 命令和事件存储支持的数据库提供程序包括：DocumentDB、MongoDB、SQL Server、MySQL、PostgreSQL 和 SQLite.
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) - RabbitMQ .NET 客户端 [https://www.rabbitmq.com](https://www.rabbitmq.com).
* [RawRabbit](https://github.com/pardahlman/RawRabbit) - 用于通过 RabbitMq 进行通信的现代 .NET 框架.
* [Rebus](https://github.com/rebus-org/Rebus) - .NET 的简单精益服务总线实现.
* [Restbus](http://restbus.org) - RabbitMq 的消息库.
* [Silverback](https://github.com/BEagle1984/silverback) - 构建事件驱动应用程序的框架（支持 Kafka、RabbitMQ、MQTT）.
* [Tossit](https://github.com/turgayozgur/tossit)  - 用于分布式作业/工作器逻辑的简单易用的库. 由内置 RabbitMQ 实现处理的分布式消息.

### Reporting
* [FastReport](https://github.com/FastReports/FastReport)  - .NET Core 2.x/.Net Framework 4.x 的开源报告生成器.  FastReport 可用于 MVC、Web API 应用程序.

### Scheduler and Job
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) - 用于按计划运行任务（作业）的轻量级健壮库.
* [Coravel](https://github.com/jamesmh/coravel) - .Net Core 遇到 Laravel：调度、排队等.
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - 具有流畅界面的自动化作业调度程序.
* [Gofer.NET](https://github.com/brthor/Gofer.NET) - Easy C# API for Distributed Background Tasks/Jobs for .NET Core. Inspired by celery for python.
* [HangfireIO](https://github.com/HangfireIO/Hangfire) - 在 ASP.NET 应用程序中执行即发即忘、延迟和重复性任务的简单方法 [http://hangfire.io](http://hangfire.io).
* [LiquidState](https://github.com/prasannavl/LiquidState) - 用于 .NET 的高效异步和同步状态机.
* [NCrontab](https://github.com/atifaziz/NCrontab) - .NET 的 Crontab.
* [quartznet](https://github.com/quartznet/quartznet/) - Quartz 企业调度程序 .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net).
* [stateless](https://github.com/dotnet-state-machine/stateless) - Simple library for creating state machines in C# code.

### SDKs
* [AWS SDK](https://github.com/aws/aws-sdk-net)  - Amazon Web Services (AWS) .NET Core SDK 组件. 每个 AWS 服务都有自己的 NuGet 包.
* [azure-event-hubs-dotnet](https://github.com/azure/azure-event-hubs-dotnet) - 用于 Azure 事件中心的 .NET Standard 客户端库.
* 区块链客户
  * [Bittrex.Net](https://github.com/JKorf/Bittrex.Net) - C# .Net wrapper for the Bittrex web API including all features easily accessible and usable.
  * [Binance.Net](https://github.com/JKorf/Binance.Net) - 币安 Web API 的 .Net API 包装器.
* [CakeMail.RestClient](https://github.com/Jericho/CakeMail.RestClient)  - CakeMail API 的客户端. 允许您发送交易电子邮件、批量电子邮件、管理列表和联系人等.
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) - 用于领事的 .NET API.
* [csharp-nats](https://github.com/nats-io/csharp-nats) - C# .NET client for the NATS messaging system.
* [DarkSkyCore](https://github.com/amweiss/dark-sky-core) - .NET Standard 包装器 [Dark Sky API](https://darksky.net/dev/docs).
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - .NET (C#) Client Library for Docker API.
* [firebase-admin-dotnet](https://github.com/firebase/firebase-admin-dotnet) - Firebase 管理员 .NET SDK
* [google-cloud-dotnet](https://github.com/GoogleCloudPlatform/google-cloud-dotnet) - 用于 .NET 的 Google Cloud 客户端库.
* [Manatee.Trello](https://github.com/gregsdennis/Manatee.Trello) - A fully object-oriented .Net wrapper for Trello's RESTful API written in C#.
* [Microphone](https://github.com/rogeralsing/Microphone) - 使用 Web Api 或 NancyFx 在 Consul 或 ETCD 集群上运行自托管 REST 服务的轻量级框架.
* [octokit.net](https://github.com/octokit/octokit.net) - 用于 .NET 的 GitHub API 客户端库.
* [PreStorm](https://github.com/jshirota/PreStorm) - ArcGIS Server 的并行 REST 客户端.
* [SendGrid-csharp](https://github.com/sendgrid/sendgrid-csharp) - C# client library for using the full SendGrid API.
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) - .NET Standard compatible C# client to interface with Etsy's excellent [statsd](https://github.com/etsy/statsd) 服务器.
* [tweetinvi](https://github.com/linvi/tweetinvi) - Intuitive .NET C# library to access the Twitter REST and STREAM API.

### Security
* [aspnetcore-security-headers](https://github.com/juunas11/aspnetcore-security-headers) - 用于向 ASP.NET Core 应用程序添加安全标头的中间件.
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) - 清理 HTML 以避免 XSS 攻击.
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - 用于处理 JOSE 对象（JWT、JWA、JWS 和相关）的库.
* [Jwt.Net](https://github.com/jwt-dotnet/jwt) - Jwt.Net，.NET 的 JWT（JSON Web 令牌）实现.
* [JWT Simple Server](https://github.com/Xabaril/JWTSimpleServer) - 用于 ASP.NET Core 的轻量级动态 jwt 服务器.
* [NWebsec](https://github.com/NWebsec/NWebsec) - ASP.NET 的安全库 [http://www.nwebsec.com](http://www.nwebsec.com).
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) - 用于 ASP.NET Core 的 reCAPTCHA 2.0.
* [roslyn-security-guard](https://github.com/dotnet-security-guard/roslyn-security-guard) - Roslyn 分析器，旨在帮助对 .NET 应用程序进行安全审计.
* [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core) - .NET Core 中间件，用于注入 Owasp 推荐的 HTTP 标头以提高安全性.
* [Security](https://github.com/aspnet/Security) - 用于网络应用程序安全和授权的中间件.
* [SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders) - 允许向 ASP.NET Core 网站添加安全标头的小包.

### Searching
* [Algolia.Search](https://github.com/algolia/algoliasearch-client-csharp) - 官方 Algolia .NET 客户端的存储库.
* [AutoComplete](https://github.com/omerfarukz/autocomplete) - 持久、简单、强大且可移植的自动完成库.
* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net) - NEST 和 Elasticsearch.NET 这两个官方 elasticsearch .NET 客户端的存储库.
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) - Elasticsearch .NET API.
* [SearchExtensions](https://github.com/ninjanye/SearchExtensions) - IQueryable 接口的高级搜索功能，例如实体框架查询.
* [SimMetrics.Net](https://github.com/StefH/SimMetrics.Net) - 相似性度量库，例如从编辑距离（Levenshtein、Gotoh、Jaro 等）到其他度量（例如 Soundex、Chapman）
* [SolrExpress](https://github.com/solr-express/solr-express) - 用于 Solr 的简单轻量级查询 .NET 库，以可控、可构建和快速失败的方式.

### Serialization
* [BinarySerializer](https://github.com/jefffhaynes/BinarySerializer) - 自定义数据包和协议格式的序列化，支持位处理.
* [bond](https://github.com/Microsoft/bond)  - 用于处理模式化数据的跨平台框架. 它支持跨语言反序列化和强大的通用机制，用于有效地操作数据.  Bond 在 Microsoft 中广泛用于大规模服务.
* [Channels](https://github.com/davidfowl/Channels) - 基于推送的 .NET 流.
* [CsvHelper](https://github.com/JoshClose/CsvHelper) - 帮助读取和写入 CSV 文件的库.
* [Edi.Net](https://github.com/indice-co/EDI.Net)  - EDI 串行器/解串器. 支持 EDIFact、X12 和 TRADACOMS 格式.
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer) - .NET 的扩展 Xml 序列化程序.
* [Jil](https://github.com/kevin-montrose/Jil) - 建立在 Sigil 上的快速 .NET JSON (De)Serializer.
* 消息包 
  * [msgpack-cli](https://github.com/msgpack/msgpack-cli) - 公共语言基础设施的 MessagePack 实现 / [msgpack.org](http://msgpack.org).
  * [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp) - Extremely Fast MessagePack Serializer for C#(.NET, .NET Core, Unity, Xamarin).
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - 流行的 .NET 高性能 JSON 框架.
* [protobuf-net](https://github.com/mgravell/protobuf-net/) - 用于惯用 .NET 的协议缓冲区库.
* [Schema.NET](https://github.com/RehanSaeed/Schema.NET) - Schema.org objects turned into strongly typed C# POCO classes for use in .NET. All classes can be serialized into JSON/JSON-LD and XML, typically used to represent structured data in the head section of html page.
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) - JSON、JSV 和 CSV 文本序列化程序.
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) - 易于使用、易于扩展和高性能的库，用于使用 .NET 进行 CSV 解析.
* [Wire](https://github.com/rogeralsing/Wire) - POCO 对象的二进制序列化程序.
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) - .网
* [ZeroFormatter](https://github.com/neuecc/ZeroFormatter) - 用于 .NET 的快速二进制（反）序列化器.
* [Utf8Json](https://github.com/neuecc/Utf8Json) - Definitely Fastest and Zero Allocation JSON Serializer for C#(NET, .NET Core, Unity, Xamarin).
* [YAXLib](https://github.com/sinairv/YAXLib)  - 用于 .NET Framework 和 .NET Core 的 XML 序列化库. 非常灵活和强大.

### Template Engine
* [dotliquid](https://github.com/dotliquid/dotliquid) - Tobias Lütke 的 Liquid 模板语言的 .NET 端口.
* [fluid](https://github.com/sebastienros/fluid) - 尽可能接近 Liquid 模板语言的开源 .NET 模板引擎.
* [Portable.Xaml](https://github.com/cwensley/Portable.Xaml) - 用于读取/写入 xaml 文件的便携式 .NET 库.
* [Razor](https://github.com/aspnet/Razor) - 用于 MVC Web 应用程序的视图页面中使用的 CSHTML 文件的解析器和代码生成器.
* [RazorLight](https://github.com/toddams/RazorLight) - 基于 Microsoft 的 Razor 解析引擎的模板引擎，用于 .NET Core.
* [Scriban](https://github.com/lunet-io/scriban) - 一种用于 .NET 的快速、强大、安全和轻量级的文本模板语言和引擎.

### Testing
* [Atata](https://github.com/atata-framework/atata) - 基于 Selenium WebDriver 的 Web UI 测试自动化全功能框架. [https://atata.io](https://atata.io)
* [Bogus](https://github.com/bchavez/Bogus) - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
* [CoreBDD](https://github.com/stevenknox/CoreBDD) - xUnit.net 的 BDD 框架
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) - .NET 的简单模拟库.
* [FluentAssertions](https://github.com/fluentassertions/fluentassertions) - 一组 .NET 扩展方法，允许您更自然地指定 TDD 或 BDD 样式测试的预期结果.
* [GenFu](https://github.com/MisterJames/GenFu) - 可用于生成真实测试数据的库.
* [LightBDD](https://github.com/LightBDD/LightBDD) - BDD 框架允许创建易于阅读和维护的测试.
* [mockhttp](https://github.com/richardszalay/mockhttp) - Microsoft 的 HttpClient 库的测试层.
* [moq.netcore](https://github.com/Moq/moq4) - .NET 最流行和最友好的模拟框架.
* [MSpec](https://github.com/machine/machine.specifications) - 用于编写 BDD 风格测试的流行测试框架.
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - 流畅的测试
  ASP.NET Core MVC 框架.
* [Netling](https://github.com/hallatore/Netling) - 负载测试客户端，方便网络测试.
* [NSpec](https://github.com/nspec/NSpec) - Battle hardened testing framework for C# that's heavily inspired by Mocha and RSpec.
* [NSubstitute](https://github.com/nsubstitute/NSubstitute) - .NET 模拟框架的友好替代品.
* [nunit](https://github.com/nunit/dotnet-test-nunit) - .NET Core 的 NUnit 测试运行器.
* [shouldly](https://github.com/shouldly/shouldly) - 应该测试 .NET - 断言 * 应该 * 的方式！ [http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow)  - 适用于 .NET 的实用 BDD 解决方案. 它使用 Gherkin 规范语言并集成到 Visual Studio.
* [Storyteller](https://github.com/storyteller/Storyteller) - .NET 的可执行规范 [http://storyteller.github.io](http://storyteller.github.io).
* [Stubbery](https://markvincze.github.io/Stubbery/) - A simple library for creating and running Api stubs in .NET.
* [Testavior](https://github.com/geeklearningio/Testavior) - Testavior 是一个轻量级的解决方案，可帮助您为 ASP.NET Core 开发行为测试.
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) - 有史以来最简单的 BDD 框架！
* [xBehave.net](https://github.com/xbehave/xbehave.net) - 一个 xUnit.net 扩展，用于使用自然语言描述您的测试. [http://xbehave.github.io](http://xbehave.github.io)
* [xUnit.net](https://github.com/xunit/xunit) - 用于 .NET Framework 的免费、开源、以社区为中心的单元测试工具.

### Tools
* [CliFx](https://github.com/Tyrrrz/CliFx) - 用于构建命令行界面的声明性框架.
* [CommandLineUtils](https://github.com/natemcmaster/CommandLineUtils) - .NET Core 和 .NET Framework 的命令行解析和实用程序.
* [docfx](https://github.com/dotnet/docfx) - 用于为 .NET 项目构建和发布 API 文档的工具 [http://dotnet.github.io/docfx](http://dotnet.github.io/docfx)
* [dotnetfiddle](https://dotnetfiddle.net) - .NET 沙箱，供开发人员快速试用代码和共享代码片段.
* [dotnet-tools](https://github.com/natemcmaster/dotnet-tools) - .NET Core 命令行 (dotnet CLI) 的工具扩展列表.
  * [LibMan CLI](https://github.com/aspnet/LibraryManager) - Web 应用程序的客户端内容管理器.
* [EntryPoint](https://github.com/Nick-Lucas/EntryPoint) - 适用于 .Net Core 和 .Net Framework 4.5+ 的可组合 CLI（命令行）参数解析器.
* [Fake JSON Server](https://github.com/ttu/dotnet-fake-json-server)  - 用于原型设计或作为 CRUD 后端的假 REST API. 无需定义类型，使用动态类型. 数据存储在单个 JSON 文件中. 具有身份验证、WebSocket 通知、异步长时间运行的操作、错误/延迟的随机生成和实验性 GraphQL 支持.
* [gitignore.io](https://github.com/joeblau/gitignore.io) - 为您的项目创建有用的 .gitignore 文件 [https://www.gitignore.io](https://www.gitignore.io).
* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore) - 扫描上传的 packages.config 文件或 GitHub 存储库，并确定 nuget 包是否面向 .NET Standard.
* [json2csharp](http://json2csharp.com) - Generate C# classes from JSON.
* [letsencrypt-win-simple](https://github.com/Lone-Coder/letsencrypt-win-simple) - 适用于 Windows 的简单 ACME 客户端.
* [Linq_Faster](https://github.com/jackmott/LinqFaster)  - 类似 Linq 的数组、跨度扩展函数<T> , 和列表<T>更快，分配更少.
 
* [mRemoteNG](https://github.com/mRemoteNG/mRemoteNG) - 下一代 mRemote、开源、标签式、多协议、远程连接管理器
* [NJsonSchema](https://github.com/RSuter/NJsonSchema) - NJsonSchema 是一个 .NET 库，用于读取、生成和验证 JSON Schema 草案 v4+ 模式.
* [NuKeeper](https://github.com/NuKeeperDotNet/NuKeeper) - 自动更新 .NET 项目中的 nuget 包.
* [NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer) - 使用 GUI 创建、更新和部署 Nuget 包.
* [NugetVisualizer](https://github.com/sepharg/NugetVisualizer) - 可视化一组给定的 git 存储库或文件夹的所有 nuget 包及其相应版本.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - 使用 GitHub 的 OctoLinker 浏览器扩展有效地浏览 `projects.json` 文件.
* [posh-dotnet](https://github.com/bergmeister/posh-dotnet) -`PowerShell` 选项卡完成 [dotnet CLI](https://github.com/dotnet/cli).
* [Rin](https://github.com/mayuki/Rin)  - ASP.NET Core 的请求/响应检查器中间件. 像一瞥.
* [scoop](https://github.com/lukesampson/scoop) - 适用于 Windows 的命令行安装程序.
* [SerilogAnalyzer](https://github.com/Suchiman/SerilogAnalyzer)  - 使用 Serilog 日志库对代码进行基于 Roslyn 的分析. 检查常见错误和使用问题.
* [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) - #ziplib is a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.
* [ShareX](https://github.com/ShareX/ShareX)  - 免费和开源程序，可让您捕获或记录屏幕的任何区域，只需按一下键即可共享. 它还允许将图像、文本或其他类型的文件上传到 80 多个您可以选择的受支持目的地. [https://getsharex.com](https://getsharex.com)
* [SharpLab](https://github.com/ashmind/SharpLab) - .NET 代码游乐场，显示代码编译的中间步骤和结果. [https://sharplab.io](https://sharplab.io)
* [SmartCode](https://github.com/Ahoo-Wang/SmartCode)  – SmartCode= IDataSource -&gt; IBuildTask -&gt; IOutput =&gt; Build Everything！！！  （包括【代码生成器】）
* [sourcelink](https://github.com/dotnet/sourcelink) - SourceLink 是一个与语言和源代码控制无关的系统，用于为二进制文件提供一流的源代码调试体验.
* [System.CommandLine](https://github.com/dotnet/command-line-api) - System.CommandLine，一组用于命令行解析、调用和呈现终端输出的库.
* [Typin](https://github.com/adambajguz/Typin) - 简单易用的声明式框架，用于交互式 CLI 应用程序和命令行工具（直接模式），其根源在于 CliFx.
* [X.Web.Sitemap](https://github.com/dncuug/X.Web.Sitemap) – 用于 .NET 和 .NET Core 的简单站点地图生成器
* [X.Web.RSS](https://github.com/dncuug/X.Web.RSS) – 用于 .NET 和 .NET Core 的简单 RSS Feed 生成器

### Web Framework
* WebAssembly
  * [Blazor](https://github.com/SteveSanderson/Blazor) - 通过 WebAssembly 在浏览器中运行 .NET 的 UI 框架.
    * [Awesome Blazor](https://github.com/AdrienTorris/awesome-blazor) - 收集有关 Blazor 的精彩资源（示例、组件、文章、视频等）.
    * [Blazor Redux](https://github.com/torhovland/blazor-redux) - 使用 Blazor 连接 Redux 状态存储.
  * [Ooui](https://github.com/praeclarum/Ooui) - 小型跨平台 UI 库，可将原生 UI 开发的简单性引入 Web.
* [ReactJS.NET](https://github.com/reactjs/React.NET) - .NET 库，用于 React 组件的 JSX 编译和服务器端渲染.
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET)  - .NET 应用程序的可预测状态容器. 灵感来自 [https://github.com/reactjs/redux](https://github.com/reactjs/redux).

### Web Socket
* [Fleck](https://github.com/statianzo/Fleck) - Fleck is a WebSocket server implementation in C#. Fleck requires no inheritance, container, or additional references.
* [SignalR Server](https://github.com/aspnet/signalr) - 网络应用程序的实时网络功能，包括服务器端推送.
* [SuperSocket](https://github.com/kerryjiang/SuperSocket) - 轻量级、跨平台和可扩展的套接字服务器应用程序框架.
* [WampSharp](https://github.com/Code-Sharp/WampSharp) - C# implementation of [The Web Application Messaging Protocol](http://wamp-proto.org/) - 通过 WebSockets 提供远程过程调用和发布/订阅的消息传递模式的协议.
* [websocket-manager](https://github.com/radu-matei/websocket-manager) - ASP .NET Core 的实时库.

### Windows Service
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) - 直接从 .NET Core 设置并作为 Windows 服务运行.
* [Topshelf](https://github.com/Topshelf/Topshelf) - 使用 .NET 构建 Windows 服务的简单服务托管框架.

### Workflow
* [CoreWF](https://github.com/dmetzgar/corewf/) - Windows Workflow Foundation (WF) 到 .NET Core 的端口.
* [workflow-core](https://github.com/danielgerlag/workflow-core) - .NET Standard 的轻量级工作流引擎.
* [WorkflowEngine.NET](https://github.com/optimajet/WorkflowEngine.NET) - 在您的应用程序中添加工作流的组件.
* [Wexflow](https://github.com/aelassas/Wexflow) - 高性能、可扩展、模块化和跨平台的工作流引擎.

## Roadmaps
* [ASP.NET Core Developer Roadmap](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap) - 2019 年成为 ASP.NET Core 开发人员的路线图.

## Starter Kits
* [Arch](https://github.com/Arch) - 由软件架构师创建的 .NET Core 库集合，他们采用了 .NET Core 中的所有新内容.
  * [AutoHistory](https://github.com/Arch/AutoHistory) - Microsoft.EntityFrameworkCore 的插件，支持自动记录数据更改历史记录.
* [AspNetCore-Angular2-Universal](https://github.com/MarkPieszak/aspnetcore-angular2-universal) - 跨平台 - 为 SEO、Bootstrap、i18n 国际化 (ngx-translate)、Webpack、TypeScript、带 Karma 的单元测试、WebAPI REST 设置、SignalR、Swagger 文档等提供服务器端渲染！
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors.
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices) - Yeoman 生成器，用于构建全新的 ASP.NET Core 单页应用程序，该应用程序在客户端使用 Angular 2 / React / React With Redux / Knockout / Aurelia.
* [ASP.Net Core Vue Starter](https://github.com/MarkPieszak/aspnetcore-Vue-starter) - Asp.NETCore 2.0 Vue 2 (ES6) SPA Starter kit，包含路由、Vuex 等！
* [bitwarden-core](https://github.com/bitwarden/core) - 核心基础设施后端（API、数据库等） [https://bitwarden.com](https://bitwarden.com).
* [dotNetify](https://github.com/dsuryd/dotNetify) - Simple, lightweight, yet powerful way to build real-time HTML5/C# .NET web apps.
* [generator-aspnet](https://github.com/OmniSharp/generator-aspnet) - 用于 ASP.NET Core 的生成器.
* [Nucleus](https://github.com/alirizaadiyahsi/Nucleus) - Vue 启动应用程序模板，在后端使用 ASP.NET Core API 分层架构和基于 JWT 的身份验证
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - 利用现有技术使用 ASP.NET Core 1 构建同构 React 应用程序的起点.
* [saaskit](https://github.com/saaskit/saaskit) - 用于构建 SaaS 应用程序的开发人员工具包.
* [serverlessDotNetStarter](https://github.com/pharindoko/serverlessDotNetStarter) 用于在基于无服务器框架的 AWS 云中开发和部署 lambda 函数的入门套件.

## Sample Projects
* 微服务和服务网格
  * [clean-architecture-dotnet](https://github.com/thangchung/clean-architecture-dotnet) - 在电子商务示例业务领域应用带有 DDD-lite、CQRS-lite 和刚好足够的云原生模式的最小清洁架构
  * [coolstore-microservices ](https://github.com/vietnam-devs/coolstore-microservices) - 基于 Kubernetes 的多语言微服务应用程序，带有 Istio 服务网格
  * [distributed-playground](https://github.com/jvandevelde/distributed-playground) - 带有 Vagrant、Consul、Docker 和 ASP.NET Core 的分布式服务游乐场.
  * [DNC-DShop](https://github.com/devmentors)  - 分布式 .NET Core 项目和免费课程.  （DDD、CQRS、RabbitMQ、MongoDB、Redis、监控、日志、CI、CD）
  * [dotnetcore-microservices-poc](https://github.com/asc-lab/dotnetcore-microservices-poc) - 使用 .NET Core（EF Core、MediatR、Marten、Eureka、Ocelot、RabbitMQ、Polly、ElasticSearch、Dapper）和博客文章系列在微服务架构中简化的保险销售系统.
  * [eShopOnContainers](https://github.com/dotnet/eShopOnContainers) - 基于微服务架构和容器的参考应用程序.
  * [InMemoryCQRSReplication](https://github.com/Aaronontheweb/InMemoryCQRSReplication) - Akka.NET 参考架构 - CQRS + 分片 + 内存复制
  * [magazine-website](https://github.com/thangchung/magazine-website) - 杂志网站（使用 .NET Core、ASP.NET Core、EF Core），应用了 DDD、CQRS、微服务、异步编程.
  * [microservices-in-dotnetcore](https://github.com/horsdal/microservices-in-dotnet-book-second-edition) - 来自第二版的代码示例 [Microservices in .NET Core](https://www.manning.com/books/microservices-in-net-core-second-edition).
  * [practical-dapr](https://github.com/thangchung/practical-dapr) - 基于 Dapr 和 Tye 构建的全栈 .NET 微服务.
  * [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - 实时交易平台演示展示了应用于整个应用程序堆栈的反应式编程原则.   
* 单体
  * [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) - 西风专辑查看器 ASP.NET 5 示例.
  * [allReady](https://github.com/HTBox/allReady) - 开源解决方案侧重于提高备灾活动的意识、效率和影响，因为它们由当地社区的人道主义和灾害响应组织提供. [http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
  * [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) - ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger.
  * [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) - 使用 ASP.NET Core 实现服务发现模式的示例.
  * [AspNetAuthorizationWorkshop](https://github.com/blowdart/AspNetAuthorizationWorkshop) - 介绍 ASP.NET Core 授权中的各种新部分的研讨会
  * [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/) 在 2016 年 12 月 Connect 大会上展示了一套综合的面向企业用户和消费者（自行车骑手）的互通应用程序： [Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps), [Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices), [Websites](https://github.com/Microsoft/BikeSharing360_Websites), [Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer), [Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer), [Cognitive Services Kiosk App](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp),
 [Azure Bot App](https://github.com/Microsoft/BikeSharing360_BotApps).
  * [Clean Architecture Manga](https://github.com/ivanpaulovich/clean-architecture-manga) - Clean Architecture sample with .NET Core 3.0 and C# 8. Use cases as central organising structure, completely testable, decoupled from frameworks.
  * [cloudscribe](https://github.com/cloudscribe/cloudscribe) - ASP.NET Core 多租户 Web 应用程序基础.
  * [CoreCodeCamp](https://github.com/shawnwildermuth/CoreCodeCamp) - 一个用于运行小型本地开发活动的开源网站.
  * [DotNetClub](https://github.com/scheshan/DotNetClub) - 用 ASP.NET Core 编写的小俱乐部.
  * [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) - 具有整体部署模型的分层应用程序架构.
  * [Entropy](https://github.com/aspnet/Entropy) - 新功能和想法的混乱实验场 - 在此处查看单个功能的小而简单的样本.
  * [EquinoxProject](https://github.com/EduardoPires/EquinoxProject) - 带有 DDD、CQRS 和事件源的完整 ASP.NET Core 2.0 应用程序.
  * [GenVue](https://github.com/herbat73/GenVue) - 一个可托管的 Web 应用程序，允许机密用户上传和共享基于 Vue.js、Vuetifyjs 和 NetCore WebAPI 堆栈构建的私有文件
  * [guidance-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) - 如何在 Microsoft Azure 上的多租户应用程序中管理用户身份，使用 Azure Active Directory 进行身份验证.
  * [JustA.ML](https://github.com/mustakimali/JustA.ML)  - 一个 Web 应用程序，可让您在使用 ASP.NET Core 2.0 编写的设备之间共享文件/URL/文本. 开源，活在 [https://justa.ml](https://justa.ml)
  * [MegaMine](https://github.com/Nootus/MegaMine) - 开源挖矿解决方案，帮助矿工提取黄金、石英、花岗岩等.该解决方案是使用 ASP.NET Core 和 AngularJS 构建的，以微服务的方式利用多个轻量级组件.
  * [MusicStore](https://github.com/dotnet/aspnetcore/tree/master/src/MusicStore) - 使用 MVC 和实体框架的示例 MusicStore 应用程序.
  * [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) - NLayerAppV3 N-Layered Architecture with .NET Core Preview 2.
  * [NorthwindTraders](https://github.com/JasonGT/NorthwindTraders) - Northwind Traders 是一个使用 ASP.NET Core 和 Entity Framework Core 构建的示例应用程序.
  * [Orchard Core - Modular and Multi-tenant applications](https://github.com/OrchardCMS/OrchardCore.Samples) - 使用 Orchard Core Framework 创建模块化和多租户应用程序.
  * [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript) - 使用 ASP.NET Core、Angular 2 和 TypeScript 的跨平台单页应用程序 [http://wp.me/p3mRWu-11L](http://wp.me/p3mRWu-11L).
  * [PokeR](https://github.com/halomademeapc/pokeR)  - 在 ASP.NET Core 的 SPA 托管中使用 SignalR 和 Angular 进行实时 Scrum 扑克. 包括 Docker 支持. [Demo](https://planning.halomademeapc.com)
  * [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore) - ASP.NET Core 功能和设施的每日更新微示例.
  * [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) - .NET Core REST API CQRS 实现与原始 SQL 和 DDD 使用 Clean Architecture.
  * [StarWars](https://github.com/JacekKosciesza/StarWars) - GraphQL“星球大战”示例，将 GraphQL 用于 .NET、ASP.NET Core、Entity Framework Core.
 
## Articles
* 基础知识
  * [Microsoft architectural overview of comprehensive BikeSharing360 suite of demo apps with related videos](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [Porting a .NET Framework library to .NET Core](https://www.codeproject.com/Articles/1190475/Porting-a-NET-Framework-library-to-NET-Core)
  * [The 68 things the CLR does before executing a single line of your code](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-single-line-of-your-code/)
  * .NET Core 和 Nodejs 的比较在 [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) 和 [here](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
  * [Understanding ASP.NET Core Initialization](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/)
  * [Why you should join .NET Core and ASP.NET Core train](https://codingblast.com/why-you-should-join-asp-net-core/)
* 云开发
  * [Configuring the AWS SDK in .NET Core](https://aws.amazon.com/blogs/developer/configuring-aws-sdk-with-net-core/)
  * [Serverless Architecture using C# and AWS Amazon Gateway Api/Lambda](https://www.codeproject.com/Articles/1178781/Serverless-Architecture-using-Csharp-and-AWS-Amazo)
  * [Using C# and .NET Core in Amazon Web Services (AWS) Lambda](https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
* 配置和部署
  * [.NET project structure](https://gist.github.com/davidfowl/ed7564297c61fe9ab814)
  * [Adding Travis CI builds to a .NET Core app](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)
  * [ASP.NET Core 1.0 - Configure ApplicationInsights](http://social.technet.microsoft.com/wiki/contents/articles/35918.asp-net-core-1-0-configure-applicationinsights.aspx)
  * [haproxy, nginx, Angular 2, ASP.NET Core, Redis and Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/)
  * [Project.json to MSBuild conversion guide](http://www.natemcmaster.com/blog/2017/01/19/project-json-to-csproj/)
  * [Publishing a .NET project with Appveyor and NuGet](https://few-lines-of-code.blogspot.com/2016/03/publishing-net-project-with-appveyor.html)
  * [The New Configuration Model in ASP.NET Core](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
* 实体框架核心
  * [.NET Core Data Access](https://blogs.msdn.microsoft.com/dotnet/2016/11/09/net-core-data-access/)
  * [A very good example about EF Core](https://github.com/rowanmiller/Demo-EFCore)
  * [Connect to Postgres with EF Core](http://en.otomatikmuhendis.com/2017/05/05/connect-to-postgres-with-ef-core/)
* 神奇
  * [Getting started with Orchard Core as a NuGet package](http://www.ideliverable.com/blog/getting-started-with-orchard-core-as-a-nuget-package)
  * [How to export HTML to PDF in ASP.NET Core](https://code.msdn.microsoft.com/How-to-export-HTML-to-PDF-c5afd0ce)
  * [Vue.js server side rendering with ASP.NET Core](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
* 安全
  * [.NET Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [ASP.NET Core 2.0 Authentication and Authorization System Demystified](https://digitalmccullough.com/posts/aspnetcore-auth-system-demystified.html)
  * [A walk-through for an ASP.NET Authorization Lab](https://github.com/blowdart/AspNetAuthorizationWorkshop)
  * [Authentication in ASP.NET Core](https://stormpath.com/blog/authentication-asp-net-core)
* 测试
  * [Selenium with .NET Core](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)
- [InfoQ .NET articles](https://www.infoq.com/dotnet) - InfoQ 网站上最好的 .NET 文章集

## Books
* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)
* [ASP.NET Core Application Development: Building an application in four sprints (Developer Reference)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core in Action](https://www.manning.com/books/asp-net-core-in-action)
* [ASP.NET Core 1.0 High Performance](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [Building Microservices with ASP.NET Core: Develop, Test, and Deploy Cross-Platform Services in the Cloud](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp/1491961732)
* [C# 6 and .NET Core 1.0: Modern Cross-Platform Development](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [C# in Depth 4](https://www.amazon.com/C-Depth-Jon-Skeet/dp/1617294535)
* [Dependency Injection in .NET Core, 2nd edition](https://www.manning.com/books/dependency-injection-in-dot-net-second-edition)
* [Essencial C# 7.0](https://www.amazon.com/Essential-7-0-Addison-Wesley-Microsoft-Technology/dp/1509303588)
* [Exploring .NET Core with Microservices, ASP.NET Core, and Entity Framework Core - free eBook sampler](https://www.manning.com/books/exploring-dot-net-core)
* [Microservices in .NET Core: with C#, the Nancy framework, and OWIN middleware](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [Professional C# 6 and .NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [The little ASP.NET Core](https://www.recaffeinate.co/book)


## Videos
* [Channel9](https://channel9.msdn.com) - MSDN
* [Channel9](https://www.youtube.com/channel/UCsMica-v34Irf9KVTh6xx-g) - YouTube
* [Microsoft Learning Center](https://dotnet.microsoft.com/learn/aspnet)
 * [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)

## Podcasts
* [.NET Rocks](https://www.dotnetrocks.com)
* [Merge Conflict](http://www.mergeconflict.fm/)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)

## Community
* [.NET Foundation](http://forums.dotnetfoundation.org)
* [.NET Blog](https://devblogs.microsoft.com/dotnet/)
* [/r/CoolGithubProjects](https://www.reddit.com/r/coolgithubprojects)
* [ASP.NET](https://forums.asp.net)
* [Channel9](https://channel9.msdn.com)
* [Awesome .NET open source & community resources](https://discoverdot.net)
* [Slack](http://tattoocoder.com/aspnet-slack-sign-up)
* [BuiltWithDot.Net](https://builtwithdot.net)
* 堆栈溢出
  *  [.NET Core](https://stackoverflow.com/questions/tagged/.net-core)
  *  [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
  *  [ASP.NET Core](https://stackoverflow.com/questions/tagged/asp.net-core)
  *  [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
  *  [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
  *  [Entity Framework Core](https://stackoverflow.com/questions/tagged/entity-framework-core)
* [Trending .NET repositories on GitHub today](https://github.com/trending?l=csharp)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [thangchung](http://weblogs.asp.net/thangchung) 已放弃本作品的所有版权和相关或邻接权.
