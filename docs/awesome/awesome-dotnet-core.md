<div class="github-widget" data-repo="thangchung/awesome-dotnet-core"></div>
## Awesome .NET Core [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

灵感来自 [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

 欢迎捐款！  请看看 [contribution guidelines](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md)  首页.  我们也接受专有和商业软件.

谢谢大家 [contributors](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors) ，你很棒，没有你就不可能！  目标是建立一个由知名资源组成的分类社区驱动集合.

看看我 [blog](https://medium.com/@thangchung) 或者打招呼 [Twitter](https://twitter.com/thangchung)!


  * [Code Analysis and Metrics](#code-analysis-and-metrics)  

## General

* [ASP.NET Core Documentation](https://docs.asp.net/en/latest/) - 官方ASP.NET核心文档站点.
* [.NET Core Documentation](https://docs.microsoft.com/en-us/dotnet/articles/welcome) - Home of the technical documentation for .NET Core, C#, F# and Visual Basic, including basic concepts, getting started instructions, tutorials and samples.
* [.NET Core SDK](https://www.microsoft.com/net/core) -  .NET Core SDK是由Microsoft和.NET社区维护的通用开发平台 [GitHub](https://github.com/dotnet/core).
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/master/Documentation/architecture/net-platform-standard.md) - 旧版本和新版本的.NET之间存在差异.
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - 描述.NET Standard 2.0的内容以及当前.NET Standard缺失部分的路线图.
* [Clean Code .NET/.NET Core](https://github.com/thangchung/clean-code-dotnet) - 适用于.NET / .NET Core的Clean Code概念.

## Frameworks, Libraries and Tools

### API

* [autorest](https://github.com/Azure/autorest) - Swagger (OpenAPI) Specification code generator featuring C# and Razor templates. Supports C#, Java, Node.js, TypeScript, Python and Ruby. `4.5.x or above`
* [aspnet-api-versioning](https://github.com/Microsoft/aspnet-api-versioning) - 将服务API版本添加到ASP.NET Web API，使用ASP.NET Web API的OData和ASP.NET Core的库集.
* [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) -  ASP.NET核心速率限制中间件.
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) - 使用Kestrel和Consul的API冷凝器/反向代理，包括轻量级的consul库.
* [Flurl](https://github.com/tmenier/Flurl) - 适用于.NET的Fluent URL构建器和可测试的HTTP [https://flurl.io](https://flurl.io).
* GraphQL
  * [Dapper.GraphQL](https://github.com/landmarkhw/Dapper.GraphQL) - 一个旨在将Dapper和graphql-dotnet项目集成在一起的库，其中包括易用性和性能作为主要关注点.
  * [graphql-aspnetcore](https://github.com/JuergenGutsch/graphql-aspnetcore) -  ASP.NET Core MiddleWare创建GraphQL端点.
  * [graphql-convention](https://github.com/graphql-dotnet/conventions) - 此库是顶部的补充层，允许您使用现有属性获取器和方法作为字段解析器自动将.NET类包装到GraphQL模式定义中
  * [graphiql-dotnet](https://github.com/JosephWoodward/graphiql-dotnet) - 用于ASP.NET Core的GraphiQL中间件.
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) - 基于.NET Framework的.NET [https://github.com/graphql/graphql-js](https://github.com/graphql/graphql-js).
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) -  GraphQL for .NET.
  * [graphql-dotnet-server](https://github.com/graphql-dotnet/server) -  GraphQL for .NET  - 订阅传输WebSockets.
  * [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) -  .Net Core和.NET Framework的GraphQL服务器.
  * [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL) -  FSharp实现Facebook GraphQL查询语言 [https://fsprojects.github.io/FSharp.Data.GraphQL](https://fsprojects.github.io/FSharp.Data.GraphQL).
  * [parser](https://github.com/graphql-dotnet/parser) -  .NET中GraphQL的词法分析器和解析器.
* [halcyon](https://github.com/visualeyes/halcyon) -  ASP.NET的HAL实现.
* [JSON API .NET Core](https://github.com/Research-Institute/json-api-dotnet-core) - 构建json：api兼容API的框架，目标是消除RESTful样板.
* [LightNode](https://github.com/neuecc/LightNode) - 基于OWIN构建的Micro RPC / REST Framework [http://neuecc.github.io/LightNode](http://neuecc.github.io/LightNode).
* [NetCoreStack.Proxy](https://github.com/NetCoreStack/Proxy) - 适用于.NET Standard 2.0的类型安全的分布式REST库（NetCoreStack Flying Proxy）
* [NSwag](https://github.com/RSuter/NSwag) - 用于.NET，Web API和TypeScript的Swagger / OpenAPI工具链. [http://NSwag.org](http://NSwag.org).
* [OData](https://github.com/OData/WebApi/tree/feature/netcore) - 开放数据协议（OData）支持创建基于HTTP的数据服务，这些服务允许使用统一资源标识符（URI）识别并在抽象数据模型中定义的资源，由Web客户端使用简单的HTTP消息进行发布和编辑.
* [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) - OpenAPI Generator allows generation of API client libraries (e.g. C#, TypeScript, etc), server stubs (ASP.NET Core, NancyFx, etc), documentation and configuration automatically given an OpenAPI Spec (v2, v3).
* [refit](https://github.com/paulcbetts/refit) - 适用于Xamarin和.NET的自动类型安全REST库.
* [RestClient.Net](https://github.com/MelbourneDeveloper/RestClient.Net) - Cross Platform REST Client for all C# platforms
* [RestEase](https://github.com/canton7/RestEase) - 易于使用的类型安全REST API客户端库，简单且可自定义.
* [RestLess](https://github.com/letsar/RestLess) -  .Net Standard的自动类型安全无反射REST API客户端库.
* [Restier](https://github.com/OData/RESTier) -  RESTier是一个RESTful API开发框架，用于在.NET平台上构建基于OData V4的标准RESTful服务.
* [Restsharp](https://github.com/restsharp/RestSharp) - 用于.NET的简单REST和HTTP API客户端
* [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) - 无缝地为WebApi项目添加了一个招摇.
  * [MicroElements.Swashbuckle.FluentValidation](https://github.com/micro-elements/MicroElements.Swashbuckle.FluentValidation) - 添加FluentValidation规则以招摇.
  * [Swashbuckle.AspNetCore.Filters](https://github.com/mattfrear/Swashbuckle.AspNetCore.Filters) -  Swashbuckle.AspNetCore的一堆有用的过滤器.
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core) -  ASP.NET Core的社区贡献.

### Application Frameworks
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate)   -  ASP.NET Boilerplate是一个专用于新的现代Web应用程序的通用应用程序框架.  它使用已经熟悉的工具并实现最佳实践，为您提供SOLID开发体验.
* [AsyncEx](https://github.com/StephenCleary/AsyncEx) -  async / await的帮助程序库.
* [Aeron.NET](https://github.com/AdaptiveConsulting/Aeron.NET) - 高效可靠的UDP单播，UDP多播和IPC消息传输 -  Aeron的.NET端口.
* [akka.net](https://github.com/akkadotnet/akka.net) - 用于在.NET和Mono上构建高度并发，分布式和容错的事件驱动应用程序的工具包和运行时.
* [Aggregates.NET](https://github.com/volak/Aggregates.NET) -  Aggregates.NET是一个框架，可以帮助开发人员将优秀的NServiceBus和EventStore库集成在一起.
* [ASP.NET MVC](https://github.com/aspnet/Mvc) - 模型视图控制器框架，用于构建动态网站，清晰地分离关注点，包括合并的MVC，Web API和带Razor的Web页面.
* [Butterfly Server .NET](https://github.com/firesharkstudios/butterfly-server-dotnet)   - 允许用最少的工作量构建实时Web应用程序和本机应用程序.  定义Web API和Subscription API，以自动同步所连接客户端的数据集.
* [CAP](https://github.com/dotnetcore/CAP) - 具有本地持久消息功能的EventBus，用于SOA或微服务架构中的系统集成.
* [Carter](https://github.com/CarterCommunity/Carter) -  Carter是一个允许Nancy-esque路由与ASP.Net Core一起使用的库.
* [Chromely](https://github.com/mattkol/Chromely) -  Electron.NET的轻量级替代品，用于.NET / .NET核心的电子.
* [Cinchoo ETL](https://github.com/Cinchoo/ChoETL) - 用于.NET的ETL框架（用于CSV，Flat，Xml，JSON，键值格式文件的分析器/写入器）.
* [CQRSlite](https://github.com/gautema/CQRSlite) - Lightweight framework for helping writing CQRS and Eventsourcing applications in C#.
* [dataaccess_aspnetcore](https://github.com/digipolisantwerp/dataaccess_aspnetcore) -  DataAccess Toolbox包含使用工作单元和存储库模式在ASP.NET Core和Entity Framework Core 1.0中进行数据访问的基类.
* [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore) - 基于ASP.NET Core构建高质量Web应用程序的轻量级和可扩展基础架构.
* [DotNetCorePlugins](https://github.com/natemcmaster/DotNetCorePlugins) - .NET Core library for loading assemblies as a plugin.
* [DotnetSpider](https://github.com/dotnetcore/DotnetSpider)   -  DotnetSpider，一个类似于WebMagic和Scrapy的.NET标准网络爬行库.  它是.NET的轻量级，高效且快速的高级Web爬行和抓取框架.
* [DotNetty](https://github.com/Azure/DotNetty) -  netty端口，事件驱动的异步网络应用程序框架.
* [dotvvm](https://github.com/riganti/dotvvm) - 用于Web Apps的开源MVVM框架.
* [ElectronNET](https://github.com/ElectronNET/Electron.NET) - 使用ASP.NET NET Core构建跨平台桌面应用程序.
* [EmbedIO](https://github.com/unosquare/embedio) - 用于.NET Framework和.NET Core的基于模块的小型跨平台Web服务器.
* [Ether.Network](https://github.com/Eastrall/Ether.Network) -  Ether.Network是一个开源网络库，允许开发人员通过TCP / IP协议创建简单，快速和可扩展的套接字服务器或客户端应用程序.
* [EventFlow](https://github.com/eventflow/EventFlow) -  Async /等待.NET的第一个CQRS + ES和DDD框架.
* [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - Lightweight and fast library written in C# for reading Microsoft Excel files.
* [ExtCore](https://github.com/ExtCore) - 基于ASP.NET Core 1.0创建模块化和可扩展Web应用程序的免费，开源和跨平台框​​架.
* [Finbuckle.MultiTenant](https://github.com/Finbuckle/Finbuckle.MultiTenant)   -  Finbuckle.MultiTenant是一个.NET标准库，用于为ASP.NET 2.0+设计的多租户支持.  它提供租户解析，每租户应用配置和每租户数据隔离的功能.
* [fission](https://github.com/fission/fission) -  Kubernetes的快速无服务器功能.
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp)   - 远程过程调用（RPC）为构建分布式应用程序和服务提供了有用的抽象.  此存储库中的库提供了gRPC协议的具体实现，通过HTTP / 2分层.  这些库使用支持的语言的任意组合实现客户端和服务器之间的通信.
* [Halibut](https://github.com/OctopusDeploy/Halibut) - 使用基于SSL的JSON-RPC的.NET安全通信堆栈.
* [MagicOnion](https://github.com/neuecc/MagicOnion) - 适用于.NET，.NET Core和Unity的基于gRPC的HTTP / 2 RPC流式处理框架.
* [MassTransit](https://github.com/MassTransit/MassTransit) -  .NET分布式应用程序框架. 
* [microdot](https://github.com/gigya/microdot) - 开源.NET微服务框架.
* [MoreLINQ](https://github.com/morelinq/MoreLINQ) -  LINQ to Objects的扩展.
* [Nancy](https://github.com/NancyFx/Nancy) - 用于在.NET和Mono上构建基于HTTP的服务的轻量级，低仪式框架.
* [opencvsharp](https://github.com/shimat/opencvsharp) -  OpenCV的.NET Framework包装器.
* [orleans](https://github.com/dotnet/orleans) - 框架，提供了构建分布式高规模计算应用程序的直接方法，无需学习和应用复杂的并发或其他扩展模式.
* [protoactor-dotnet](https://github.com/AsynkronIT/protoactor-dotnet) -  Golang和C的超快速分布式演员# [http://proto.actor](http://proto.actor).
* [resin](https://github.com/kreeben/resin) - 具有HTTP API和可插拔读/写管道的16位宽矢量空间搜索引擎.
* [RService.io](https://github.com/Stoom/RService.IO) -  ASP.Net Core RESTful微服务框架，专注于速度和易用性.
* [ServiceStack](https://github.com/ServiceStack/ServiceStack) - 为所有人提供周到的架构，令人难以置信的快速，令人愉快的网络服务 [https://servicestack.net](https://servicestack.net).
* [Steeltoe OSS](https://github.com/SteelToeOSS) - 用于常见微服务模式的.NET工具包.
* [Strathweb.TypedRouting.AspNetCore](https://github.com/filipw/Strathweb.TypedRouting.AspNetCore) - 在ASP.NET Core MVC项目中启用强类型路由的库.
* [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0.
* [X.PagedList](https://github.com/dncuug/X.PagedList) - 用于轻松分页ASP.NET / ASP.NET Core中任何IEnumerable / IQueryable的库.

### Application Templates
* [.NET Boxed](https://github.com/Dotnet-Boxed/Templates)   - 包含电池的项目模板，提供使您前往所需的最少代码.  包括ASP.NET Core API和GraphQL模板.
* [aspnet-core-react-template](https://github.com/bradymholt/aspnet-core-react-template) -  ASP.NET Core 2.0 / React SPA模板应用程序.
* [AspNetCoreSpa](https://github.com/asadsahi/AspNetCoreSpa) - 具有Angular CLI全功能应用程序的Asp.Net Core 2+和Angular 6 SPA.
* [ASP.NET-MVC-Template](https://github.com/NikolayIT/ASP.NET-MVC-Template) -  ASP.NET MVC 5和ASP.NET Core的即用型模板，修复了存储库，服务，模型映射以及DI和StyleCop警告.
* [AddFeatureFolders](https://github.com/OdeToCode/AddFeatureFolders) - Enable feature folders for MVC controllers and views in ASP.NET Core.
* [Angular Visual Studio Webpack Starter](https://github.com/damienbod/AngularWebpackVisualStudio)   -  Webpack，Visual Studio，ASP.NET Core和Angular的模板.  应用程序的客户端和服务器端都在一个ASP.NET Core项目中实现，这使得部署更容易.
* [DNTFrameworkCoreTemplate](https://github.com/rabbal/DNTFrameworkCoreTemplate) - 基于的Boilerplate项目模板 [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore)
* [dotnet new caju](https://github.com/ivanpaulovich/dotnet-new-caju) - dotnet new templates with awesome architecture styles! Increases productivity to design layered applications based on Hexagonal, Clean or Event Sourcing architectures styles. It supports multiple data access frameworks (MongoDB, EntityFramework, Dapper or Kafka) and it is completely testable.
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices) -  Microsoft ASP.NET核心JavaScript服务.
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core) - 用于构建现代Web应用程序的基于jQuery的HTML5小部件库. [http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui).
* [QuickApp](https://github.com/emonney/QuickApp) - 具有完整登录，用户和角色管理的ASP.NET Core / Angular4启动项目模板.
* [Serenity](https://github.com/volkanceylan/Serenity) -  Serenity是一个ASP.NET MVC / TypeScript应用程序平台，旨在通过基于服务的体系结构简化和缩短以数据为中心的业务应用程序的开发.
* [Toucan](https://github.com/mrellipse/toucan)   - 用于构建单页应用程序的Boilerplate.  服务器是围绕SOLID原则设计的多项目.Net Core解决方案.  客户端是TypeScript 2，Vuejs 2，Vuex 2.

### Authentication and Authorization
* [AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) - 面向OWIN / Katana和ASP.NET Core的OpenID Connect / OAuth2服务器框架.
* [Auth0](https://github.com/auth0/auth0.net) - 托管，企业级现代身份平台.
* [Cierge](https://github.com/PwdLess/Cierge)   -  Cierge是一个OpenID Connect服务器，用于处理用户注册，登录，配置文件，管理，社交登录等.  Cirege不使用密码，而是使用魔术链接/代码和外部登录来验证您的用户.
* [Identity](https://github.com/aspnet/Identity) -  ASP.NET Core Identity是用于构建ASP.NET Core Web应用程序的成员资格系统，包括成员资格，登录名和用户数据.
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) -  IdentityServer for ASP.NET Core 1.0和2.0
  * [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework) -  EntityFramework持久层
  * [IdentityServer4.MongoDB](https://github.com/diogodamiani/IdentityServer4.MongoDB) -  MongoDB持久层
  * [IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - 实体框架核心持久层
  * [IdentityServer4.Templates](https://github.com/IdentityServer/IdentityServer4.Templates) -  IdentityServer4的dotnet cli模板.
* [openiddict](https://github.com/openiddict/openiddict-core) - 易于使用的ASP.NET Core OpenID Connect服务器.
  * [oidc-debugger](https://github.com/nbarbettini/oidc-debugger) - OAuth 2.0 and OpenID Connect debugging tool.
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - 建立 [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) 使用Stormpath和ASP.NET Core. 
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - 建立 [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) 使用Stormpath和ASP.NET Core.（已弃用：加入OKTA后，2017年3月将更新更新） 
* [stuntman](https://github.com/ritterim/stuntman) - 利用ASP.NET标识在开发期间模拟用户的库.

### Blockchain
* [BTCPayServer](https://github.com/btcpayserver/btcpayserver) - 与Bitpay API兼容的跨平台自托管服务器.
* [Meadow](https://github.com/MeadowSuite/Meadow) - 集成的以太坊实施和工具套件，专注于Solidity测试和开发.
* [NBitcoin](https://github.com/MetacoSA/NBitcoin) - 用于.NET框架的综合比特币库.
* [NBlockchain](https://github.com/danielgerlag/NBlockchain) - 用于构建支持区块链的应用程序的.NET标准库
* [NBXplorer](https://github.com/dgarage/NBXplorer) - 比特币和Altcoin轻量级块浏览器.
* [NEO](https://github.com/neo-project/neo) - 智能经济开放网络.
* [Nethereum](https://github.com/Nethereum) - 将以太坊的爱带到.NET.
* [StratisBitcoinFullNode](https://github.com/stratisproject/StratisBitcoinFullNode) - Simple and affordable end-to-end solutions for development, testing and deployment of native C# blockchain applications on the .Net framework.
* [Trezor.Net](https://github.com/MelbourneDeveloper/Trezor.Net) - Cross platform C# library for talking to the Trezor Hardwarewallet
* [WalletWasabi](https://github.com/zkSNACKs/WalletWasabi) - 以隐私为重点，符合ZeroLink标准的比特币钱包.

### Bot
* [BotSharp](https://github.com/SciSharp/BotSharp) - The Open Source AI Chatbot Platform Builder in 100% C# Running in .NET Core with Machine Learning algorithm.
* [NadekoBot](https://github.com/Kwoth/NadekoBot) - Open source, general-purpose Discord chat bot written in C#.
* [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) - C# Telegram Bot API library.
* [Funogram](https://github.com/Dolfik1/Funogram) - F# Telegram Bot Api library.

### Build Automation
* [cake-build](https://github.com/cake-build/cake) - 跨平台构建自动化系统.
* [CatLight](https://catlight.io) - Status notifier for developers that monitors builds and tasks in the project. Built using .Net Core and Electron.
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) - Style your C# console output!
* [dotnet-docker](https://github.com/dotnet/dotnet-docker) - 用于使用.NET Core和.NET Core Tools的基本Docker镜像.
* [Dockerize.NET](https://github.com/brthor/Dockerize.NET) -  .NET Cli工具将.NET核心应用程序打包成docker镜像：&#39;dotnet dockerize&#39;
* [FlubuCore](https://github.com/flubu-core/flubu.core) - A cross platform build and deployment automation system for building projects and executing deployment scripts using C# code.
* [GitInfo](https://github.com/kzu/GitInfo) - Git and SemVer Info from MSBuild, C# and VB.
* [GitVersioning](https://github.com/AArnott/Nerdbank.GitVersioning) - 使用单个简单版本.txt文件中的版本标记程序集和NuGet包，并为非官方构建包含git commit ID.
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet) - 去.NET Core Runtime的包装器.
* [Image2Docker](https://github.com/docker/communitytools-image2docker-win) -  PowerShell模块，可将现有Windows应用程序工作负载移植到Docker.
* [LocalAppVeyor](https://github.com/joaope/LocalAppVeyor) - 在本地运行AppVeyor版本.
* [msbuild](https://github.com/Microsoft/msbuild) -  Microsoft Build Engine是用于构建应用程序的平台.
* [Nuke](https://github.com/nuke-build/nuke) - 跨平台构建自动化系统.
* [Opserver](https://github.com/opserver/Opserver) -  Stack Exchange的监控系统.
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) -  Visual Studio Team Services构建和发布代理.

### Bundling and Minification
* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) -  Visual Studio扩展，让您配置JS，CSS和HTML文件的捆绑和缩小.
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine)   -  ASP.NET MVC ViewEngine，用于在JavaScript环境中呈现标记.  适用于React和Angular服务器端呈现.
* [Smidge](https://github.com/Shazwazza/Smidge/) - 用于ASP.NET Core的轻量级运行时CSS / JavaScript文件缩小，组合，压缩和管理库.
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin)   - 包含一组标记最小化器的.NET库.  该项目的目标是通过减少HTML，XHTML和XML代码的大小来提高Web应用程序的性能.

### Caching
* [CacheManager](https://github.com/MichaCo/CacheManager) - Open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. [http://cachemanager.michaco.net](http://cachemanager.michaco.net)
* [Faster](https://github.com/Microsoft/FASTER/tree/master/cs) -  Microsoft Research的快速键值存储.
* [Foundatio](https://github.com/exceptionless/Foundatio) - 用于构建分布式应用程序的可插入基础块.
* [Microsoft Caching](https://github.com/aspnet/Caching) - 用于内存缓存和分布式缓存的库.
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) - High performance general purpose redis client for .NET languages (C# etc).

### CMS
* [Awesome-CMS-Core](https://github.com/SaiGonSoftware/Awesome-CMS-Core) - 令人敬畏的CMS Core是一个开源CMS，使用ASP.Net Core和ReactJS构建，考虑到模块分离问题，并提供最新的技术趋势，如.Net Core，React，Webpack，SASS，后台作业，消息队列.
* [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core) -  ASP.NET应用程序提供常见的博客功能.
* [Cofoundry](https://github.com/cofoundry-cms/cofoundry)   - 开源.NET Core CMS和模块化应用程序框架.  代码优先，不引人注目且可扩展.
* [CoreWiki](https://github.com/csharpfritz/CoreWiki) - 我们正在实时编码流中处理的简单ASP.NET核心wiki.
* [Miniblog](https://github.com/madskristensen/Miniblog.Core) -  ASP.NET Core博客引擎.
* [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS)   - 开源ASP.NET Core 2.0 CMS.  它目前支持MySQL并计划实现MSSQL，SQLite和PostgreSQL.  此外，它是一个模块化CMS支持主题，皮肤，自定义布局，小部件，多语言（En，BN）.
* [Piranha CMS](https://github.com/piranhacms/piranha.core) - 用于ASP.NET核心和实体框架核心的轻量级且不显眼的开源CMS.
* [Platformus](https://github.com/Platformus) - 基于ASP.NET Core 1.0和ExtCore框架的免费，开源和跨平台CMS.
* [Squidex](https://github.com/Squidex/squidex) - 无头CMS，基于MongoDB，CQRS和事件采购.
* [Swastika I/O Core CMS](https://github.com/Swastika-IO/Swastika-IO-Core)   - 开源ASP.NET Core 2.x CMS.  它目前支持MS SQL并计划在不久的将来实现MSSQL，SQLite.  它有许多开箱即用的功能，如多语言支持，主题，模板......
* [Weapsy](https://github.com/Weapsy/Weapsy)   - 基于DDD和CQRS的开源ASP.NET核心CMS.  它支持开箱即用的MSSQL，MySQL，SQLite和PostgreSQL.
* [ZKEACMS](https://github.com/SeriaWei/ZKEACMS.Core) - 视觉设计，通过拖放建立网站.

### Code Analysis and Metrics
* [awesome-static-analysis](https://github.com/mre/awesome-static-analysis) - 针对各种编程语言的静态分析工具，链接和代码质量检查器的精选列表.
*代码分析
  * [DevSkim](https://github.com/Microsoft/DevSkim) - 一组IDE插件和规则，提供安全“linting”功能.
  * [RefactoringEssentials](https://github.com/icsharpcode/RefactoringEssentials) - 重构Visual Studio的Essentials.
  * [roslyn-analyzers](https://github.com/dotnet/roslyn-analyzers) -  .NET编译器平台（“Roslyn”）分析器.
  * [StyleCopAnalyzers](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) - 使用.NET编译器平台的StyleCop规则.
*指标
  * [AppMetrics](https://github.com/alhardy/AppMetrics) -  App Metrics是一个开源和跨平台的.NET库，用于记录和报告应用程序中的指标并报告其健康状况.
  * [Audit.NET](https://github.com/thepirat000/Audit.NET) - 审核.NET对象更改的小框架.
  * [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) - 强大的.NET库，用于基准测试.
  * [coverlet](https://github.com/tonerdo/coverlet) - 用于.NET Core的跨平台代码覆盖库.
  * [Foundatio](https://github.com/exceptionless/Foundatio#metrics) - 内存，redis，StatsD和Metrics.NET实现中的通用接口.
  * [MiniCover](https://github.com/lucaslorentz/minicover) -  .NET Core的极简代码覆盖工具.
  * [NBench](https://github.com/petabridge/NBench) -  .NET应用程序的性能基准测试和测试框架.
  * [Nexogen.Libraries.Metrics](https://github.com/nexogen-international/Nexogen.Libraries.Metrics) - 用于在.NET中收集应用程序指标并将其导出到Prometheus的库.
  * [OpenCover](https://github.com/OpenCover/opencover) - 适用于.NET 2及更高版本的代码覆盖工具（仅限WINDOWS OS），支持分支和序列点的32和64个进程.
  * [prometheus-net](https://github.com/prometheus-net/prometheus-net) -  .NET客户端 [https://prometheus.io](https://prometheus.io).
  * [Prometheus.Client](https://github.com/PrometheusClientNet/Prometheus.Client) -  .NET客户端 [Prometheus](https://prometheus.io).
  	* [Prometheus.Client.MetricPusher](https://github.com/PrometheusClientNet/Prometheus.Client.MetricPusher) - 将指标推送到Prometheus.Client的PushGateaway.
  	* [Prometheus.Client.AspNetCore](https://github.com/PrometheusClientNet/Prometheus.Client.AspNetCore) -  Prometheus.Client的中间件.
  	* [Prometheus.Client.MetricServer](https://github.com/PrometheusClientNet/Prometheus.Client.MetricServer) -  Prometheus.Client的MetricServer.
  	* [Prometheus.Client.HttpRequestDurations](https://github.com/PrometheusClientNet/Prometheus.Client.HttpRequestDurations) -  Prometheus.Client的请求持续时间的度量标准记录.

### Compression
* [lz4net](https://github.com/MiloszKrajewski/lz4net) - 适用于所有.NET平台的超快速压缩算法.
* [sharpcompress](https://github.com/adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats.

### Compilers, Transpilers and Languages
* [Fable](https://github.com/fable-compiler/Fable) - F# to JavaScript Compiler.
* [fparsec](https://github.com/stephan-tolksdorf/fparsec) - A parser combinatory library for F# and C#.
* [Mond](https://github.com/Rohansi/Mond) - A dynamically typed scripting language written in C# with a REPL, debugger, and simple embedding API.
* [peachpie](https://github.com/peachpiecompiler/peachpie) -  .NET的开源PHP编译器.
* [Pidgin](https://github.com/benjamin-hodgson/Pidgin) - A lightweight, fast and flexible parsing library for C#, developed at Stack Overflow.
* [roslyn](https://github.com/dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs.
* [Sprache](https://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework.

### Cryptography
* [BCrypt.Net](https://github.com/BcryptNet/bcrypt.net) - 更新原始的bcrypt包.
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core) -  BCrypt.NET的.NET Core端口用于安全地存储密码.
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols.
* [multiformats](https://github.com/multiformats/cs-multihash) - 通用散列库，但是用于编码/解码Multihashes的库，它是一个“容器”，用于描述计算摘要的散列算法.
* [nsec](https://github.com/ektrah/nsec) -  NSec是基于libsodium的.NET Core的新加密库.

### Database
* [DBreeze](https://github.com/hhblaze/DBreeze) - C# .NET MONO NOSQL (key value store embedded) ACID multi-paradigm database management system.
* [JsonFlatFileDataStore](https://github.com/ttu/json-flatfile-datastore) - 简单的JSON平面文件数据存储，支持打字和动态数据.
* [LiteDB](https://github.com/mbdavid/LiteDB) -  .NET NoSQL文档存储在单个数据文件中 -  [http://www.litedb.org](http://www.litedb.org).
* [NoDb](https://github.com/joeaudette/NoDb) -  .NET Core / ASP.NET Core的“无数据库”文件系统存储，因为并非每个项目都需要数据库.
* [marten](https://github.com/JasperFx/marten) -  Postgresql作为.NET应用程序的文档数据库和事件存储 [http://jasperfx.github.io/marten](http://jasperfx.github.io/marten).
* [yessql](https://github.com/sebastienros/yessql) - 适用于任何RDBMS的.NET文档数据库.

### Database Drivers
* [cassandra-csharp-driver](https://github.com/datastax/csharp-driver) - DataStax C# Driver for Apache Cassandra.
* [confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet) -  Confluent的Apache Kafka .NET客户端.
* [couchbase-lite-net](https://github.com/couchbase/couchbase-lite-net) - 用于.NET的轻量级，面向文档（NoSQL），可同步的数据库引擎.
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) -  MongoDB的.NET驱动程序.
* MySQL
  * [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/8.0) -  Connector / Net是一个完全托管的MySQL ADO.NET驱动程序.
  * [MySqlConnector](https://github.com/mysql-net/MySqlConnector) - 用于.NET和.NET Core的异步MySQL连接器.
* Neo4j
  * [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) - 用于.NET的Neo4j Bolt驱动程序.
  * [Neo4jClient](https://github.com/Readify/Neo4jClient) -  Neo4j的.NET客户端绑定.
* [npgsql](https://github.com/npgsql/npgsql) - .NET data provider for PostgreSQL. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) -  Linq为.NET启用了文档数据库.
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) - C#/.NET RethinkDB driver with 100% ReQL API coverage.
* [progaudi.tarantool](https://github.com/progaudi/progaudi.tarantool) -  Tarantool NoSql数据库的.NET客户端.

### Database Tools and Utilities
* [DbUp](https://github.com/DbUp/DbUp)   -  .NET库，可帮助您将更改部署到SQL Server数据库.  它跟踪已经运行的SQL脚本，并运行使数据库保持最新所需的更改脚本.
* [fluentmigrator](https://github.com/fluentmigrator/fluentmigrator) -  .NET的迁移框架，就像Ruby on Rails迁移一样.
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData) - 具有OLAP操作和数据透视表数据模型的内存数据立方体.
* [roundhouse](https://github.com/chucknorris/roundhouse) - 使用sql文件的.NET数据库迁移实用程序和基于源代码控制的版本控制.
* [SharpRepository](https://github.com/SharpRepository/SharpRepository) - SharpRepository is a generic repository written in C# which includes support for various relational, document and object databases including Entity Framework, RavenDB, MongoDb and Db4o. SharpRepository includes Xml and InMemory repository implementations as well.
* [TrackableEntities.Core](https://github.com/TrackableEntities/TrackableEntities.Core) - 使用.NET Core跨服务边界进行更改跟踪.
* [Mongo.Migration](https://github.com/SRoddis/Mongo.Migration) -  Mongo.Migration是专为 [MongoDB C# Driver](https://github.com/thangchung/awesome-dotnet-core/blob/master/ https://github.com/mongodb/mongo-csharp-driver)  轻松，即时地迁移您的文档.  不再有架构迁移的停机时间.  只需编写小而简单的迁移. [Link](https://github.com/thangchung/awesome-dotnet-core/blob/master/ https://github.com/SRoddis/Mongo.Migration)

### Date and Time
* [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions) -  DateTimeRange，营业日和各种DateTime，DateTimeOffset，TimeSpan扩展方法.
* [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime)   - 允许您编写更清晰的DateTime表达式和操作.  部分灵感来自Ruby DateTime Extensions.
* [nodatime](https://github.com/nodatime/nodatime) - 更好的.NET日期和时间API [http://nodatime.org](http://nodatime.org).

### Distributed Computing
* [AspNetCore.Diagnostics.HealthChecks](https://github.com/xabaril/AspNetCore.Diagnostics.HealthChecks) -  ASP.NET核心诊断程序包的Enterprise HealthChecks.
  - [BeatPulse](https://github.com/Xabaril/BeatPulse) - 启用负载平衡器以监控已部署的Web应用程序的状态
* [Foundatio](https://github.com/exceptionless/Foundatio) - 用于构建分布式应用程序的可插入基础块.
* [Rafty](https://github.com/ThreeMammals/Rafty) -  RAFT在.NET Core中的共识.
* [Obvs](https://github.com/christopherread/Obvs) - 一个可观察的微服务总线.NET库，它在简单的基于Rx的接口中包装底层传输.
* [Ocelot](https://github.com/ThreeMammals/Ocelot) - 使用.NET Core创建的API网关.
* [OpenTracing](https://github.com/opentracing/opentracing-csharp) - 供应商中立的API和分布式跟踪工具.
* [Polly](https://github.com/App-vNext/Polly) -  .NET 3.5 / 4.0 / 4.5 / PCL库，允许开发人员以流畅的方式表达瞬态异常和故障处理策略，如重试，重试永久，等待和重试或断路器.

### E-Commerce and Payments
* [nopCommerce](https://github.com/nopSolutions/nopCommerce) - 免费的开源电子商务购物车（ASP.NET MVC / ASP.NET核心MVC），拥有庞大的社区和充满新功能，主题和插件的市场.
* [GrandNode](https://github.com/grandnode/grandnode) - 基于ASP.NET Core 2.1和MongoDB的多平台免费开源电子商务购物车 [nopCommerce](https://github.com/nopSolutions/nopCommerce).
* [PayPal](https://github.com/paypal/PayPal-NET-SDK) - 用于PayPal的RESTful API的.NET SDK.
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) - 基于.NET Core构建的超级简单电子商务系统.
* [Stripe](https://github.com/ServiceStack/Stripe) - 为stripe.com REST API键入.NET客户端.


### Exceptions
* [Demystifier](https://github.com/benaadams/Ben.Demystifier) - 对堆栈跟踪的高性能理解（使错误日志更高效）.
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - 无异常的.NET客户端
* [GlobalExceptionHandlerDotNet](https://github.com/JosephWoodward/GlobalExceptionHandlerDotNet) -  GlobalExceptionHandlerDotNet允许您将异常处理配置为ASP.NET Core应用程序管道的约定，而不是在每个控制器操作中显式处理它们.

### Functional Programming
* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) - Functional Extensions for C#.
* [DynamicData](https://github.com/RolandPheasant/DynamicData) - 基于Rx.NET的反应式集合.
* [echo-process](https://github.com/louthy/echo-process) - Actor library for C# with additional modules that support persistence to Redis, as well as JS integration.
* [FsCheck](https://github.com/fscheck/FsCheck) -  .NET的随机测试.
* [Giraffe](https://github.com/dustinmoris/Giraffe) - A native functional ASP.NET Core web framework for F# developers.
* [language-ext](https://github.com/louthy/language-ext) - C# functional language extensions and 'Erlang like' concurrency system.
* [LaYumba.Functional](https://github.com/la-yumba/functional-csharp-code) - Utility library for programming functionally in C#.
* [NetMQ.ReactiveExtensions](https://github.com/NetMQ/NetMQ.ReactiveExtensions)   - 使用Reactive Extensions（RX）轻松地在网络上的任何位置发送消息.  传输协议是ZeroMQ.
* [Optional](https://github.com/nlkl/Optional) - A robust option type for C#.
* [reactive-streams-dotnet](https://github.com/reactive-streams/reactive-streams-dotnet) - [Reactive Streams](http://www.reactive-streams.org/) 对于.NET.
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - 与Reactive Extensions for .NET集成的MVVM框架，可创建在任何移动或桌面平台上运行的优雅，可测试的用户界面.
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) -  [Reactive Extensions](http://reactivex.io) 对于.NET.
* [Qactive](https://github.com/RxDave/Qactive)   - 反应性可查询可观察框架.  `4.xx或以上`
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/)   - 功能反应式编程（FRP）库.  `4.xx或以上`

### Graphics
* [GLFWDotNet](https://github.com/smack0007/GLFWDotNet) -  GLFW的.NET绑定.
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) -  System.Drawing周围的流畅包装，用于处理图像文件 [http://imageprocessor.org](http://imageprocessor.org) .  `4.5.x或以上`
* [ImageSharp](https://github.com/SixLabors/ImageSharp) - Cross-platform library for processing of image files written in C#.
* [LibVLCSharp](https://github.com/videolan/libvlcsharp)：用于libvlc的.NET / Mono绑定，libvlc是为VideoLAN制作的VLC应用程序提供动力的多媒体框架.
* [Magick.NET](https://github.com/dlemstra/Magick.NET) -  ImageMagick的.NET库.
* [MagicScaler](https://github.com/saucecontrol/PhotoSauce) - MagicScaler high-performance, high-quality image processing pipeline for .NET
* [QRCoder](https://github.com/codebude/QRCoder) - A pure C# Open Source QR Code implementation.
* [SharpBgfx](https://github.com/MikePopoloski/SharpBgfx) - C# bindings for the bgfx graphics library.
* [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching) - 用于支持.NET Core的.NET应用程序的图像处理库.
* [veldrid](https://github.com/mellinoe/veldrid) - 用于.NET的低级硬件加速3D图形库.

### GUI
* [Avalonia](https://github.com/AvaloniaUI/Avalonia) - 多平台.NET UI框架（以前称为Perspex）.
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) - 基于Avalonia的文本编辑器组件分叉 [AvalonEdit](https://github.com/icsharpcode/AvalonEdit)
* [Qml.Net](https://github.com/pauldotknopf/Qml.Net) - 用于Mono / .NET / .NET Core的跨平台Qml / .NET集成.
* [WinApi](https://github.com/prasannavl/WinApi) - 一个简单，直接，超薄的CLR库，用于高性能Win32 Native Interop，具有自动化，窗口，DirectX，OpenGL和Skia助手.

### IDE
* [Mono](https://github.com/mono/monodevelop) -  MonoDevelop使开发人员能够在Linux，Windows和Mac OS X上快速编写桌面和Web应用程序.它还使开发人员可以轻松地将使用Visual Studio创建的.NET应用程序移植到Linux和Mac OS X，为所有平台维护单一代码库.
* [rider](https://www.jetbrains.com/rider/) - Cross-platform C# IDE based on the IntelliJ platform and ReSharper.
* [Omnisharp](http://www.omnisharp.net/) - 开源项目系列，每个项目都有一个目标：在您选择的编辑器中实现出色的.NET体验.
* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) - SharpDevelop is a free Integrated Development Environment (IDE) for C#, VB.NET, Boo, IronPython, IronRuby and F# projects on Microsoft's .NET platform. It is written (almost) entirely in C#, and comes with features you would expect in an IDE plus a few more.
* [Visual Studio Code](https://github.com/Microsoft/vscode)   - 新型工具，结合了代码编辑器的简单性和开发人员核心编辑 - 构建 - 调试周期所需的工具.  Code提供全面的编辑和调试支持，可扩展性模型以及与现有工具的轻量级集成.
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - 针对个人开发人员，开源项目，学术研究，教育和小型专业团队的免费编辑.

### Internationalization
* [Localization](https://github.com/aspnet/Localization) -  ASP.NET核心应用程序的本地化抽象和实现.
* [NetCoreStack.Localization](https://github.com/NetCoreStack/Localization) - 具有实体框架和内存缓存的.NET Core的数据库资源本地化
* [Westwind.Globalization](https://github.com/RickStrahl/Westwind.Globalization) -  .NET应用程序的数据库驱动资源本地化.

### IOC
* [AutoDI](https://github.com/Keboo/AutoDI) - 使用IL编织的超快编译时依赖注入.
* [Autofac](https://github.com/autofac/Autofac) - 上瘾的.NET IoC容器.
* [Castle.Windsor](https://github.com/castleproject/Windsor) Castle Windsor是适用于.NET的最佳品牌，成熟的Inversion of Control容器.
* [DryIoc](https://github.com/dadhi/DryIoc) - 快速，小巧，功能齐全的IoC Container for .NET.
* [Grace](https://github.com/ipjohnson/Grace) -  Grace是一款功能丰富的依赖注入容器，其设计考虑了易用性和性能.
* [Inyector](https://github.com/davidrevoledo/Inyector) -  AspNetCore的依赖注入自动化 
* [LightInject](https://github.com/seesharper/LightInject) - 超轻量级IoC容器 [http://www.lightinject.net](http://www.lightinject.net).
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) - 简单，灵活，快速的依赖注入库，可促进最佳实践，引导开发人员走向成功之路.
* [Stashbox](https://github.com/z4kn4fein/stashbox) - 基于.NET的解决方案的轻量级，可移植依赖注入框架.
* [StructureMap](https://github.com/structuremap/structuremap) -  .NET的依赖注入/反转控制工具.

### Logging
* [common-logging](https://github.com/net-commons/common-logging) -  .NET的可移植日志记录抽象 [http://net-commons.github.io/common-logging](http://net-commons.github.io/common-logging).
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) - 使用UDP和Redis传输的.NET Core应用程序的Logstash日志记录扩展.
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - 无异常的.NET客户端
* [Foundatio](https://github.com/exceptionless/Foundatio#logging) - 流畅的日志记录API，可用于在整个应用程序中记录消息.
* [LibLog](https://github.com/damianh/LibLog) - Single file for you to either copy/paste or install via nuget, into your library/ framework/ application to provide a logging abstraction.
* [log4net](https://github.com/apache/logging-log4net) -  log4net是Microsoft®.NET运行时的优秀Apache log4j™框架的一个端口.
* [NLog](https://github.com/NLog/NLog) - 高级.NET，Silverlight和Xamarin日志记录.
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) - 在ASP.NET Core日志记录中构建日志appender，以将所有日志发送到Application Insights.
* [serilog](https://github.com/serilog/serilog) - 具有完全结构化事件的简单.NET日志记录.
  * [serilog-aspnetcore](https://github.com/serilog/serilog-aspnetcore) - 用于ASP.NET Core 2+的Serilog集成.
  * [Serilog.Exceptions](https://github.com/RehanSaeed/Serilog.Exceptions) -  Serilog.Exceptions是一个附加组件 [Serilog](https://serilog.net/) 记录异常详细信息和Exception.ToString（）中未输出的自定义属性.
  * [Serilog.Settings.Configuration](https://github.com/serilog/serilog-settings-configuration) - 从Microsoft.Extensions.Configuration读取的Serilog配置提供程序.
* [SEQ](https://getseq.net) -  Seq通过HTTP收集数据，而您的应用程序使用适用于您平台的最佳可用结构化日志API.

### Machine Learning and Data Science
* [Accord](https://github.com/accord-net/framework) -  .NET的机器学习，计算机视觉，统计和通用科学计算.
* [ML.NET](https://github.com/dotnet/machinelearning) - 跨平台开源机器学习框架，使.NET开发人员可以访问机器学习 [http://dot.net/ml](http://dot.net/ml).
* [Spreads](https://github.com/Spreads/Spreads/) - 用于数据流实时和探索性分析的系列和面板.
* [TensorFlowSharp](https://github.com/migueldeicaza/TensorFlowSharp) - 适用于.NET语言的TensorFlow API.
* [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) - 借助量子力学的思想，从单个例子​​中生成itmap和tilemap.

### Mail
* [FluentEmail](https://github.com/lukencode/FluentEmail) -  .NET和.NET Core的一体化电子邮件发件人
* [MailBody](https://github.com/doxakis/MailBody) - 使用流畅的界面（.NET）创建交易电子邮件.
* [MailKit](https://github.com/jstedfast/MailKit) - 用于IMAP，POP3和SMTP的跨平台.NET库.
* [MailMergeLib](https://github.com/axuno/MailMergeLib) -  SMTP邮件客户端库，为文本，内联图像和附件提供舒适的邮件合并功能，以及发送邮件的良好吞吐量和容错能力.
* [MimeKit](https://github.com/jstedfast/MimeKit) - 跨平台.NET MIME创建和解析器库，支持S / MIME，PGP，DKIM，TNEF和Unix mbox spool.
* [netDumbster](https://github.com/cmendible/netDumbster)   - 用于测试的.Net假SMTP服务器.  克隆流行的Dumbster.
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [SendGrid Client](https://github.com/0xdeafcafe/sendgrid-dotnet) - C# library for the SendGrid v3 mail endpoint.
* [SmtpServer](https://github.com/cosullivan/SmtpServer) - 库创建自己的SMTP服务器.
* [StrongGrid](https://github.com/Jericho/StrongGrid)   -  SendGrid的v3 API客户端.  不仅允许您发送电子邮件，还允许您批量导入联系人，管理列表和段，为列表创建自定义字段等.还包括SendGrid Webhooks的解析器.

### Mathematics
* [UnitConversion](https://github.com/Stratajet/UnitConversion) - 用于.NET Core和.NET Framework的可扩展单元转换库.
* [AutoDiff](https://github.com/alexshtf/autodiff) - 一个库，提供快速，准确和自动的数学函数微分（计算导数/梯度）.

### Misc
* [AdvanceDLSupport](https://github.com/Firwood-Software/AdvanceDLSupport)   - 库来改进P / Invoke-ing本机代码.  与本机对象交互，就像它们是第一类对象一样.
* [AngleSharp](https://github.com/AngleSharp/AngleSharp)   - 最终尖括号解析器库.  它解析HTML5，MathML，SVG和CSS，以构建基于官方W3C规范的DOM.  可与python的beautifulsoup4相媲美.
* [AgileMapper](https://github.com/agileobjects/AgileMapper) -  AgileMapper是一个零配置，高度可配置的对象 - 对象映射器，具有可查看的执行计划.
* [AspNetCore Extension Library](https://github.com/sgjsakura/AspNetCore) -  ASP.NET核心扩展库.
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) -  .NET中基于约定的对象 - 对象映射器.
* [Bleak](https://github.com/Akaion/Bleak) -  Windows本机DLL注入库.
* [Bullseye](https://github.com/adamralph/bullseye/) - 用于描述和运行目标及其依赖项的.NET包.
* [Castle.Core](https://github.com/castleproject/Core) -  Castle Core，包括Castle DynamicProxy，Logging Services和DictionaryAdapter [http://www.castleproject.org](http://www.castleproject.org).
* [Chessie](https://github.com/fsprojects/Chessie) - 面向铁路的.NET编程 [http://fsprojects.github.io/Chessie](http://fsprojects.github.io/Chessie).
* [CliWrap](https://github.com/Tyrrrz/CliWrap) - 用于命令行界面的包装器.
* [commanddotnet](https://github.com/bilal-fazlani/commanddotnet) - 在类中为命令行应用程序接口建模.
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - The implementation of CommonMark specification in C# for converting Markdown documents to HTML.
* [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt) - 用于为.NET控制台应用程序创建表的流畅库.
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) -  Microsoft ASP.NET服务器端支持和jQuery DataTables的帮助程序.
* [DinkToPdf](https://github.com/rdvojmoc/DinkToPdf) - C# .NET Core wrapper for wkhtmltopdf library that uses Webkit engine to convert HTML pages to PDF.
* [dotnet-env](https://github.com/tonerdo/dotnet-env) - 用于从.env文件加载环境变量的.NET库.
* [DotNet.Glob](https://github.com/dazinator/DotNet.Glob)   - 用于.NET / .NETStandard应用程序的快速通配库.  优于正则表达式.
* [Dotnet outdated](https://github.com/jerriep/dotnet-outdated) - 一个.NET Core全局工具，用于在项目中显示过时的NuGet包.
* [Dotnet Script](https://github.com/filipw/dotnet-script) - Run C# scripts from the .NET CLI.
* [Dotnet Serve](https://github.com/natemcmaster/dotnet-serve) - 用于.NET Core CLI的简单命令行HTTP服务器.
* [Eighty](https://github.com/benjamin-hodgson/Eighty) - 一个简单的HTML生成库
* [Enums.NET](https://github.com/TylerBrinkley/Enums.NET) -  Enums.NET是一个高性能的类型安全的.NET枚举实用程序库
* [FastExpressionCompiler](https://github.com/dadhi/FastExpressionCompiler) - 快速ExpressionTree编译器委托.
* [FluentFTP](https://github.com/robinrodricks/FluentFTP/) -  FTP和FTPS客户端，具有广泛的FTP命令，SSL / TLS连接，散列/校验和等.
* [Fody](https://github.com/Fody/Fody) - 用于编织.net组件的可扩展工具
* [HdrHistogram.NET](https://github.com/HdrHistogram/HdrHistogram.NET) - 高动态范围（HDR）直方图.
* [httpclient-interception](https://github.com/justeat/httpclient-interception) - 用于拦截服务器端HTTP依赖关系的.NET标准库.
* [Humanizer](https://github.com/Humanizr/Humanizer) -  Humanizer满足您操作和显示字符串，枚举，日期，时间，时间跨度，数字和数量的所有.NET需求.
* [Humidifier](https://github.com/jakejscott/Humidifier) - Write and maintain AWS Cloudformation templates using C#.
* [LibSass Host](https://github.com/Taritsyn/LibSassHost) -  .NET包装器 [libSass](http://sass-lang.com/libsass) 能够支持虚拟文件系统的库.
* [markdig](https://github.com/lunet-io/markdig) - 快速，强大，兼容CommonMark，可扩展的Markdown处理器，适用于.NET.
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) - 将字符串表达式（公式，方法调用，条件）解析为LINQ表达式树，可以编译为lambda并进行求值.
* [Otp.NET](https://github.com/kspearrin/Otp.NET) - An implementation TOTP RFC 6238 and HOTP RFC 4226 in C#.
* [pose](https://github.com/tonerdo/pose) - 用委托替换任何.NET方法（包括静态和非虚拟）
* [PuppeteerSharp](https://github.com/kblok/puppeteer-sharp) -  Puppeteer Sharp是官方Node.JS Puppeteer API的.NET端口.
* [readline](https://github.com/tsolarin/readline) - Pure C# GNU-Readline like library for .NET/.NET Core.
* [Relinq](https://github.com/re-motion/Relinq) - 使用re-linq，现在比以往更容易创建功能齐全的LINQ提供程序.
* [ReverseMarkdown](https://github.com/mysticmind/reversemarkdown-net) -  Html到Markdown转换器库.
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) -  PdfReport.Core是一个代码优先的报告引擎，它建立在iTextSharp.LGPLv2.Core和EPPlus.Core库之上.
* [Scientist](https://github.com/github/Scientist.net)   - 用于仔细重构关键路径的.NET库.  它是GitHub的Ruby Scientist库的一个端口.
* [Scrutor](https://github.com/khellang/Scrutor) -  Microsoft.Extensions.DependencyInjection的程序集扫描扩展.
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) -  string.Format的可扩展替换.
*股票
  * [Trady](https://github.com/lppkarl/Trady) - 用于计算技术指标的便捷图书馆，其目标是成为一个自动交易系统，提供股票数据投放，指标计算，策略构建和自动交易.
* [System.Linq.Dynamic.Core](https://github.com/StefH/System.Linq.Dynamic.Core) -  System Linq Dynamic功能的.NET Standard（.NET Core）版本.
* [UnitsNet](https://github.com/angularsen/UnitsNet) -  Units.NET为您提供所有常用的度量单位和它们之间的转换.
*验证
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation) -  .NET的小型验证库，它使用流畅的接口和lambda表达式来构建验证规则.
  * [Guard](https://github.com/safakgur/guard) - 高性能，可扩展的参数验证库.
  * [Valit](https://github.com/valit-stack/Valit)   -  .NET Core的简单验证.  代码周围不再有if语句.  写一些漂亮而干净的流利验证器吧！
* [warden-stack](https://github.com/warden-stack)   - 针对您的应用程序，资源和基础架构的“健康检查”.  让守望者守在手表上.
* [WebEssentials.AspNetCore.ServiceWorker](https://github.com/madskristensen/WebEssentials.AspNetCore.ServiceWorker) -  ASP.NET核心渐进式Web应用程序.
* [Xabe.FFmpeg](https://github.com/tomaszzmuda/Xabe.FFmpeg) - .NET Standard wrapper for FFmpeg. It allows to process media without know how FFmpeg works, and can be used to pass customized arguments to FFmpeg from C# application.
* [YoutubeExplode](https://github.com/Tyrrrz/YoutubeExplode) - 用于提取元数据和下载Youtube视频和播放列表的终极库.

### Networking
* [CurlThin](https://github.com/stil/CurlThin) - Lightweight cURL binding library for C# with support for multiple simultaneous transfers through curl_multi interface.
* [NETStandard.HttpListener](https://github.com/StefH/NETStandard.HttpListener) - 用于.NET Core的HttpListener（NETStandard）.
* [Networker](https://github.com/MarkioE/Networker) - 一个简单易用的.NET TCP和UDP网络库，旨在实现灵活，可扩展和快速.

### Office
* [EPPlus](https://github.com/JanKallman/EPPlus) - 使用.NET创建高级Excel电子表格.
* [npoi](https://github.com/tonyqus/npoi)   - 可以读取/写入未安装Microsoft Office的Office格式的.NET库.  没有COM +，没有互操作.
* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK) -  Open XML SDK提供了使用Office Word，Excel和PowerPoint文档的工具.

### ORM
* [Chloe](https://github.com/shuxinqin/Chloe) - 用于.NET的轻量级高性能对象/关系映射（ORM）库.
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) - 熟悉以前版本EF的开发人员经验，包括LINQ，POCO和Code First支持.
  * [EFCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions) - 用于插入更新删除读取（CRUD）操作的EntityFrameworkCore批量批量扩展
  * [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus)   - 实体框架实用程序|  批量操作|  批量删除|  批量更新|  查询缓存|  查询过滤器|  查询未来|  查询包括|  审计.
  * [EntityFramework.Triggers](https://github.com/NickStrupat/EntityFramework.Triggers) - 触发EF的事件.
  * [EntityFramework.Rx](https://github.com/NickStrupat/EntityFramework.Rx) - 您的EF操作的反应性**热**观察.
  * [Npgsql.EntityFrameworkCore.PostgreSQL](https://github.com/npgsql/Npgsql.EntityFrameworkCore.PostgreSQL) -  PostgreSQL的实体框架核心提供程序.
  * [EntityFramework.PrimaryKey](https://github.com/NickStrupat/EntityFramework.PrimaryKey) - 轻松获取任何实体的主键（包括复合键）.
  * [EntityFramework.TypedOriginalValues](https://github.com/NickStrupat/EntityFramework.TypedOriginalValues) - 获取实体的原始值的代理对象（对Property（“...”）的类型访问.OriginalValue）.
  * [EntityFramework.VersionedProperties](https://github.com/NickStrupat/EntityFramework.VersionedProperties) - 自动神奇地保存指定属性更改的审计历史记录的类.
  * [LINQKit](https://github.com/scottksmith95/LINQKit) -  LINQ to SQL和Entity Framework高级用户的一组免费扩展.
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) - 构建在mysql-net / MySqlConnector之上的MySql的实体框架核心提供程序.
* [Dapper](https://github.com/StackExchange/Dapper) -  .NET的简单对象映射器.
  * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - 使用Dapper时，提供一个简单的API，可以将POCO属性流畅地映射到数据库列.
  * [Dommel](https://github.com/henkmollema/Dommel) -  Dapper的简单CRUD操作.
  * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) -  DAPper的CRUD.
* [Limebean](https://nick-lucas.github.io/LimeBean/)   -  Hybrid-ORM，设计简单易用，不完全隐藏SQL，同时拥有您对ORM所期望的所有好处.  灵感来自RedBeanPHP.
* [LINQ to DB (linq2db)](https://linq2db.github.io/) - 最快的LINQ数据库访问库，在POCO对象和数据库之间为10多个具有完全SQL支持的数据库引擎提供简单，轻量，快速且类型安全的层.
* [nhibernate-core](https://github.com/nhibernate/nhibernate-core) -  NHibernate对象关系映射器.
* [NEventStore](https://github.com/NEventStore/NEventStore)   - 使用事件源作为存储机制时，持久性库用于抽象不同的存储实现.  该库的开发特别关注DDD / CQRS应用程序.
* [NPoco](https://github.com/schotime/NPoco)   - 简单的microORM，将查询结果映射到POCO对象.  项目基于Schotime的PetaPoco分公司.
* [NReco.Data](https://github.com/nreco/data) - Lightweight provider-independent DAL for SQL commands generation, CRUD operations and simple POCO mapping.
* [PetaPoco](https://github.com/CollaboratingPlatypus/PetaPoco) - 对于你的POCO来说，这是一个很小的ORM东西.
* [querybuilder](https://github.com/sqlkata/querybuilder) - SqlKata Query Builder is a powerful Sql Query Builder written in C#.
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) - 轻便，简单，快速的基于会议的POCO ORM.
* [SqlFu](https://github.com/sapiens/SqlFu) - 快速且通用的Micro-ORM.
* [SmartSql](https://github.com/Ahoo-Wang/SmartSql) -  SmartSql = MyBatis + Cache（Memory | Redis）+ ZooKeeper + R / W Splitting + Dynamic Repository ....
* [SQLStreamStore](https://github.com/SQLStreamStore/SQLStreamStore) - 针对基于SQL的.NET实现的Stream Store库.

### Profiling
* [Glimpse](https://github.com/Glimpse/Glimpse.Prototype)   - 适用于.NET的轻量级，开源，实时诊断和洞察分析器.  `不稳定的版本`
* [MiniProfiler](https://github.com/MiniProfiler/dotnet) - 一个简单但有效的ASP.NET网站迷你分析器.

### Query Builders
* [SqlKata](https://github.com/sqlkata/querybuilder) - 优雅的Sql Query Builder，支持复杂的查询，连接，子查询，嵌套条件，供应商引擎目标等

### Queue and Messaging
* [emitter](https://emitter.io/)   - 连接所有设备的免费开源实时消息服务.  此发布 - 订阅消息传递API是为了提高速度和安全性而构建的.
* [EventStore](https://github.com/EventStore/EventStore) - 使用JavaScript中的复杂事件处理的开源，功能数据库.
* [Foundatio](https://github.com/exceptionless/Foundatio#queues) - 内存，redis和azure实现中的通用接口.
* [MediatR](https://github.com/jbogard/MediatR) -  .NET中简单，无语的中介实现.
 * [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) -  Microsoft.Extensions.DependencyInjection的MediatR扩展.
* [Mediator.Net](https://github.com/mayuanyang/Mediator.Net) -  .Net的简单中介，用于发送支持管道的命令，发布事件和请求响应.
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) -  .NET中简单的进程中介.
* [MQTTnet](https://github.com/chkr1011/MQTTnet) -  MQTTnet是一个用于基于MQTT的通信的高性能.NET库.
* [netmq](https://github.com/zeromq/netmq) - 100% native C# implementation of ZeroMQ for .NET.
* [OpenCQRS](https://github.com/OpenCQRS/OpenCQRS)   - 用于DDD，CQRS和事件源的.NET核心库，具有Azure Service Bus集成.  Command和Event存储支持的数据库提供程序包括：DocumentDB，MongoDB，SQL Server，MySQL，PostgreSQL和SQLite.
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) -  RabbitMQ .NET客户端 [https://www.rabbitmq.com](https://www.rabbitmq.com).
* [RawRabbit](https://github.com/pardahlman/RawRabbit) - 用于通过RabbitMq进行通信的现代.NET框架.
* [Rebus](https://github.com/rebus-org/Rebus) -  .NET的简单和精简服务总线实现.
* [Restbus](http://restbus.org) -  RabbitMq的消息传递库.
* [Tossit](https://github.com/turgayozgur/tossit)   - 用于分布式作业/工作逻辑的简单易用的库.  内置RabbitMQ实现处理的分布式消息.

### Reporting
* [FastReport](https://github.com/FastReports/FastReport)   -  .NET Core 2.x / .Net Framework 4.x的开源报告生成器.  FastReport可用于MVC，Web API应用程序.

### Scheduler and Job
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) - 轻量级健壮的库，用于在计划上运行任务（作业）.
* [Coravel](https://github.com/jamesmh/coravel) -  .Net Core与Laravel会面：调度，排队等
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - 具有流畅界面的自动化作业调度程序.
* [Gofer.NET](https://github.com/brthor/Gofer.NET) - Easy C# API for Distributed Background Tasks/Jobs for .NET Core. Inspired by celery for python.
* [HangfireIO](https://github.com/HangfireIO/Hangfire) - 在ASP.NET应用程序中执行即发即弃，延迟和重复任务的简便方法 [http://hangfire.io](http://hangfire.io).
* [LiquidState](https://github.com/prasannavl/LiquidState) - 用于.NET的高效异步和同步状态机.
* [NCrontab](https://github.com/atifaziz/NCrontab) - 用于.NET的Crontab.
* [quartznet](https://github.com/quartznet/quartznet/) -  Quartz Enterprise Scheduler .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net).
* [stateless](https://github.com/dotnet-state-machine/stateless) - Simple library for creating state machines in C# code.

### SDKs
* [AWS SDK](https://github.com/aws/aws-sdk-net)   -  Amazon Web Services（AWS）.NET Core SDK组件.  每个AWS服务都有自己的NuGet包.
* [azure-event-hubs-dotnet](https://github.com/azure/azure-event-hubs-dotnet) -  Azure事件中心的.NET标准客户端库.
*区块链客户
  * [Bittrex.Net](https://github.com/JKorf/Bittrex.Net) - C# .Net wrapper for the Bittrex web API including all features easily accessible and usable.
  * [Binance.Net](https://github.com/JKorf/Binance.Net) -  binance web API的.Net API包装器.
* [CakeMail.RestClient](https://github.com/Jericho/CakeMail.RestClient)   -  CakeMail API的客户端.  允许您发送交易电子邮件，批量电子邮件，管理列表和联系人等.
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) -  Consul的.NET API.
* [csharp-nats](https://github.com/nats-io/csharp-nats) - C# .NET client for the NATS messaging system.
* [DarkSkyCore](https://github.com/amweiss/dark-sky-core) - 一个.NET标准的包装器 [Dark Sky API](https://darksky.net/dev/docs).
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - .NET (C#) Client Library for Docker API.
* [google-cloud-dotnet](https://github.com/GoogleCloudPlatform/google-cloud-dotnet) - 适用于.NET的Google Cloud Client Libraries.
* [Manatee.Trello](https://github.com/gregsdennis/Manatee.Trello) - A fully object-oriented .Net wrapper for Trello's RESTful API written in C#.
* [Microphone](https://github.com/rogeralsing/Microphone) - 使用Consul或ETCD集群的Web Api或NancyFx运行自托管REST服务的轻量级框架.
* [octokit.net](https://github.com/octokit/octokit.net) - 用于.NET的GitHub API客户端库.
* [PreStorm](https://github.com/jshirota/PreStorm) -  ArcGIS Server的并行REST客户端.
* [SendGrid-csharp](https://github.com/sendgrid/sendgrid-csharp) - C# client library for using the full SendGrid API.
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) - .NET Standard compatible C# client to interface with Etsy's excellent [statsd](https://github.com/etsy/statsd) 服务器.
* [tweetinvi](https://github.com/linvi/tweetinvi) - Intuitive .NET C# library to access the Twitter REST and STREAM API.

### Security
* [aspnetcore-security-headers](https://github.com/juunas11/aspnetcore-security-headers) - 用于向ASP.NET Core应用程序添加安全标头的中间件.
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) - 清除HTML以避免XSS攻击.
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - 用于处理JOSE对象的库（JWT，JWA，JWS和相关）.
* [Jwt.Net](https://github.com/jwt-dotnet/jwt) -  Jwt.Net，一种用于.NET的JWT（JSON Web Token）实现.
* [JWT Simple Server](https://github.com/Xabaril/JWTSimpleServer) - 用于ASP.NET Core的轻量级动态jwt服务器.
* [NWebsec](https://github.com/NWebsec/NWebsec) -  ASP.NET的安全库 [http://www.nwebsec.com](http://www.nwebsec.com).
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) - 用于ASP.NET Core的reCAPTCHA 2.0.
* [roslyn-security-guard](https://github.com/dotnet-security-guard/roslyn-security-guard) -  Roslyn分析器，旨在帮助.NET应用程序进行安全审计.
* [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core) -  .NET Core中间件，用于注入Owasp推荐的HTTP标头，以提高安全性.
* [Security](https://github.com/aspnet/Security) - 用于Web应用程序安全性和授权的中间件.
* [SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders) - 小包，允许向ASP.NET Core网站添加安全标头.

### Searching
* [Algolia.Search](https://github.com/algolia/algoliasearch-client-csharp) - 官方Algolia .NET客户端的存储库.
* [AutoComplete](https://github.com/omerfarukz/autocomplete) - 持久，简单，功能强大且可移植的自动完成库.
* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net) -  NEST和Elasticsearch.NET的存储库，两个官方的弹性搜索.NET客户端.
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) -  Elasticsearch .NET API.
* [SearchExtensions](https://github.com/ninjanye/SearchExtensions) -  IQueryable接口的高级搜索功能，例如实体框架查询.
* [SimMetrics.Net](https://github.com/StefH/SimMetrics.Net) - 相似度量库，例如从编辑距离（Levenshtein，Gotoh，Jaro等）到其他指标，（例如Soundex，Chapman）
* [SolrExpress](https://github.com/solr-express/solr-express) - 用于Solr的简单轻量级查询.NET库，采用可控，可构建和快速失败的方式.

### Serialization
* [bond](https://github.com/Microsoft/bond)   - 用于处理模式化数据的跨平台框架.  它支持跨语言的序列化和强大的通用机制，可以有效地处理数据.  Bond广泛用于Microsoft的高规模服务.
* [Channels](https://github.com/davidfowl/Channels) - 基于推送的.NET Streams.
* [CsvHelper](https://github.com/JoshClose/CsvHelper) - 用于帮助读写CSV文件的库.
* [Edi.Net](https://github.com/indice-co/EDI.Net)   -  EDI串行器/解串器.  支持EDIFact，X12和TRADACOMS格式.
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer) - 用于.NET的扩展Xml Serializer.
* [Jil](https://github.com/kevin-montrose/Jil) - 基于Sigil构建的快速.NET JSON（De）串行器.
* MessagePack 
  * [msgpack-cli](https://github.com/msgpack/msgpack-cli) - 公共语言基础结构的MessagePack实现/ [msgpack.org](http://msgpack.org).
  * [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp) - Extremely Fast MessagePack Serializer for C#(.NET, .NET Core, Unity, Xamarin).
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - 适用于.NET的流行高性能JSON框架.
* [protobuf-net](https://github.com/mgravell/protobuf-net/) - 用于惯用.NET的Protocol Buffers库.
* [Schema.NET](https://github.com/RehanSaeed/Schema.NET) - Schema.org objects turned into strongly typed C# POCO classes for use in .NET. All classes can be serialized into JSON/JSON-LD and XML, typically used to represent structured data in the head section of html page.
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) -  JSON，JSV和CSV文本序列化器.
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) - 易于使用，易于扩展和高性能的库，用于使用.NET进行CSV解析.
* [Wire](https://github.com/rogeralsing/Wire) - 用于POCO对象的二进制序列化程序.
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) -  .NET
* [ZeroFormatter](https://github.com/neuecc/ZeroFormatter) - 用于.NET的快速二进制（反）序列化器.
* [Utf8Json](https://github.com/neuecc/Utf8Json) - Definitely Fastest and Zero Allocation JSON Serializer for C#(NET, .NET Core, Unity, Xamarin).
* [YAXLib](https://github.com/sinairv/YAXLib)   -  .NET Framework和.NET Core的XML序列化库.  非常灵活和强大.

### Template Engine
* [dotliquid](https://github.com/dotliquid/dotliquid) - TobiasLütke的.NET端口Liquid模板语言.
* [fluid](https://github.com/sebastienros/fluid) - 开源.NET模板引擎，尽可能接近Liquid模板语言.
* [Portable.Xaml](https://github.com/cwensley/Portable.Xaml) - 用于读/写xaml文件的可移植.NET库.
* [Razor](https://github.com/aspnet/Razor) - 用于MVC Web应用程序视图页面的CSHTML文件的解析器和代码生成器.
* [RazorLight](https://github.com/toddams/RazorLight) - 基于Microsoft针对.NET Core的Razor解析引擎的模板引擎.

### Testing
* [Bogus](https://github.com/bchavez/Bogus) - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
* [CoreBDD](https://github.com/stevenknox/CoreBDD) -  xUnit.net的BDD框架
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) -  .NET的简易模拟库.
* [FluentAssertions](https://github.com/dennisdoomen/FluentAssertions) - 一组.NET扩展方法，允许您更自然地指定TDD或BDD样式测试的预期结果.
* [GenFu](https://github.com/MisterJames/GenFu) - 可用于生成实际测试数据的库.
* [LightBDD](https://github.com/LightBDD/LightBDD) -  BDD框架允许创建易于阅读和维护的测试.
* [mockhttp](https://github.com/richardszalay/mockhttp) -  Microsoft的HttpClient库的测试层.
* [moq.netcore](https://github.com/Moq/moq4) -  .NET最受欢迎和友好的模拟框架.
* [MSpec](https://github.com/machine/machine.specifications) - 用于编写BDD样式测试的流行测试框架.
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - 流畅的测试
  ASP.NET Core MVC的框架.
* [Netling](https://github.com/hallatore/Netling) - 负载测试客户端，便于Web测试.
* [NSpec](https://github.com/nspec/NSpec) - Battle hardened testing framework for C# that's heavily inspired by Mocha and RSpec.
* [NSubstitute](https://github.com/nsubstitute/NSubstitute) -  .NET模拟框架的友好替代品.
* [nunit](https://github.com/nunit/dotnet-test-nunit) - 用于.NET Core的NUnit测试运行器.
* [shouldly](https://github.com/shouldly/shouldly) - 应该测试.NET  - 断言*应该*的方式！ [http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)   - 用于.NET的实用BDD解决方案.  它使用Gherkin规范语言并集成到Visual Studio中.
* [Storyteller](https://github.com/storyteller/Storyteller) -  .NET的可执行规范 [http://storyteller.github.io](http://storyteller.github.io).
* [Stubbery](https://markvincze.github.io/Stubbery/) - 一个用于在.NET中创建和运行Api存根的简单库.
* [Testavior](https://github.com/geeklearningio/Testavior) -  Testavior是一个轻量级的解决方案，可帮助您开发ASP.NET Core的行为测试.
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) - 最简单的BDD框架！
* [xBehave.net](https://github.com/xbehave/xbehave.net) -  xUnit.net扩展，用于使用自然语言描述您的测试. [http://xbehave.github.io](http://xbehave.github.io)
* [xUnit.net](https://github.com/xunit/xunit) - 面向.NET Framework的免费，开源，以社区为中心的单元测试工具.

### Tools
* [CommandLineUtils](https://github.com/natemcmaster/CommandLineUtils) - Command line parsing and utilities for .NET Core and .NET Framework.
* [docfx](https://github.com/dotnet/docfx) - 用于构建和发布.NET项目的API文档的工具 [http://dotnet.github.io/docfx](http://dotnet.github.io/docfx)
* [dotnetfiddle](https://dotnetfiddle.net) -  .NET沙箱，供开发人员快速尝试代码和共享代码段.
* [dotnet-tools](https://github.com/natemcmaster/dotnet-tools) -  .NET Core命令行（dotnet CLI）的工具扩展列表.
  * [LibMan CLI](https://github.com/aspnet/LibraryManager) - 用于Web应用程序的客户端内容管理器.
* [EntryPoint](https://github.com/Nick-Lucas/EntryPoint) - 用于.Net Core和.Net Framework 4.5+的可组合CLI（命令行）参数解析器.
* [Fake JSON Server](https://github.com/ttu/dotnet-fake-json-server)   - 用于原型设计或作为CRUD后端的假REST API.  无需定义类型，使用动态类型.  数据存储在单个JSON文件中.  具有身份验证，WebSocket通知，异步长时间运行操作，错误/延迟的随机生成以及实验性GraphQL支持.
* [gitignore.io](https://github.com/joeblau/gitignore.io) - 为您的项目创建有用的.gitignore文件 [https://www.gitignore.io](https://www.gitignore.io).
* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore) - 扫描上传的packages.config文件或GitHub存储库，并确定nuget包是否以.NET Standard为目标 [https://icanhasdot.net](https://icanhasdot.net).
* [json2csharp](http://json2csharp.com) - Generate C# classes from JSON.
* [letsencrypt-win-simple](https://github.com/Lone-Coder/letsencrypt-win-simple) - 适用于Windows的简单ACME客户端.
* [NJsonSchema](https://github.com/RSuter/NJsonSchema) -  NJsonSchema是一个.NET库，用于读取，生成和验证JSON Schema草案v4 +模式.
* [NuKeeper](https://github.com/NuKeeperDotNet/NuKeeper) - 自动更新.NET项目中的nuget包.
* [NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer) - 使用GUI创建，更新和部署Nuget软件包.
* [NugetVisualizer](https://github.com/sepharg/NugetVisualizer) - 为一组给定的git存储库或文件夹可视化所有nuget包及其相应的版本.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - 使用适用于GitHub的OctoLinker浏览器扩展，有效地浏览`projects.json`文件.
* [posh-dotnet](https://github.com/bergmeister/posh-dotnet) - `PowerShell`选项卡完成 [dotnet CLI](https://github.com/dotnet/cli).
* [Rin](https://github.com/mayuki/Rin)   -  ASP.NET Core的请求/响应Inspector中间件.  像Glimpse.
* [scoop](https://github.com/lukesampson/scoop) -  Windows的命令行安装程序.
* [SerilogAnalyzer](https://github.com/Suchiman/SerilogAnalyzer)   - 使用Serilog日志库对基于Roslyn的代码进行分析.  检查常见错误和使用问题.
* [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) - #ziplib is a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.
* [ShareX](https://github.com/ShareX/ShareX)   - 免费和开源程序，可让您捕获或记录屏幕的任何区域，只需按一下键即可共享.  它还允许将图像，文本或其他类型的文件上传到80多个支持的目的地，您可以从中选择. [https://getsharex.com](https://getsharex.com)
* [SharpLab](https://github.com/ashmind/SharpLab) -  .NET代码游乐场，显示代码编译的中间步骤和结果. [https://sharplab.io](https://sharplab.io)
* [sourcelink](https://github.com/dotnet/sourcelink) -  SourceLink是一种语言和源代码控制不可知系统，用于为二进制文件提供一流的源代码调试体验.
* [X.Web.Sitemap](https://github.com/dncuug/X.Web.Sitemap) - 用于.NET和.NET Core的简单站点地图生成器
* [X.Web.RSS](https://github.com/dncuug/X.Web.RSS) - 用于.NET和.NET Core的简单RSS Feed生成器
* [SmartCode](https://github.com/Ahoo-Wang/SmartCode)   -  SmartCode = IDataSource  - &gt; IBuildTask  - &gt; IOutput =&gt; Build Everything !!!  （包括[代码生成器]）

### Web Framework
* WebAssembly
  * [Blazor](https://github.com/SteveSanderson/Blazor) - 通过WebAssembly在浏览器中运行.NET的UI框架.
    * [Blazor Redux](https://github.com/torhovland/blazor-redux) - 将Redux状态存储与Blazor连接.
  * [Ooui](https://github.com/praeclarum/Ooui) - 小型跨平台UI库，可将本机UI开发的简单性带入Web.
* [ReactJS.NET](https://github.com/reactjs/React.NET) - 用于JSX编译的.NET库和React组件的服务器端呈现.
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET)   -  .NET应用程序的可预测状态容器.  灵感来自 [https://github.com/reactjs/redux](https://github.com/reactjs/redux).

### Web Socket
* [Fleck](https://github.com/statianzo/Fleck) - Fleck is a WebSocket server implementation in C#. Fleck requires no inheritance, container, or additional references.
* [SignalR Server](https://github.com/aspnet/signalr) -  Web应用程序的实时Web功能，包括服务器端推送.
* [SuperSocket](https://github.com/kerryjiang/SuperSocket) - 轻量级，跨平台和可扩展的套接字服务器应用程序框架.
* [WampSharp](https://github.com/Code-Sharp/WampSharp) - C# implementation of [The Web Application Messaging Protocol](http://wamp-proto.org/) - 提供远程过程调用和通过WebSockets发布/订阅的消息传递模式的协议.
* [websocket-manager](https://github.com/radu-matei/websocket-manager) -  ASP .NET Core的实时库.

### Windows Service
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) - 直接从.NET Core设置并运行Windows服务.
* [Topshelf](https://github.com/Topshelf/Topshelf) - 使用.NET构建Windows服务的简易服务托管框架.

### Workflow
* [CoreWF](https://github.com/dmetzgar/corewf/) -  Windows Workflow Foundation（WF）到.NET Core的端口.
* [workflow-core](https://github.com/danielgerlag/workflow-core) -  .NET Standard的轻量级工作流引擎.
* [WorkflowEngine.NET](https://github.com/optimajet/WorkflowEngine.NET) - 在应用程序中添加工作流程的组件.
* [Wexflow](https://github.com/aelassas/Wexflow) - 高性能，可扩展，模块化和跨平台的工作流引擎.

## Starter Kits
* [Arch](https://github.com/Arch) -  .NET Core库的集合，由嵌入.NET Core中所有新东西的软件架构师创建.
  * [AutoHistory](https://github.com/Arch/AutoHistory) -  Microsoft.EntityFrameworkCore的插件，支持自动记录数据更改历史记录.
* [AspNetCore-Angular2-Universal](https://github.com/MarkPieszak/aspnetcore-angular2-universal) - 跨平台 - 具有服务器端呈现的SEO，Bootstrap，i18n国际化（ngx-translate），Webpack，TypeScript，单元测试w / Karma，WebAPI REST设置，SignalR，Swagger文档等等！
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors.
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices) -  Yeoman生成器构建一个全新的ASP.NET Core单页面应用程序，在客户端上使用Angular 2 / React / React和Redux / Knockout / Aurelia.
* [ASP.Net Core Vue Starter](https://github.com/MarkPieszak/aspnetcore-Vue-starter) -  Asp.NETCore 2.0 Vue 2（ES6）SPA入门套件，包含路由，Vuex等！
* [bitwarden-core](https://github.com/bitwarden/core) - 核心基础设施后端（API，数据库等） [https://bitwarden.com](https://bitwarden.com).
* [dotNetify](https://github.com/dsuryd/dotNetify) - Simple, lightweight, yet powerful way to build real-time HTML5/C# .NET web apps.
* [generator-aspnet](https://github.com/OmniSharp/generator-aspnet) - 用于ASP.NET Core的yo生成器.
* [Nucleus](https://github.com/alirizaadiyahsi/Nucleus) -  Vue启动应用程序模板，在后端使用ASP.NET Core API分层体系结构和基于JWT的身份验证
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - 使用ASP.NET Core 1构建同构React应用程序的起点，利用现有技术.
* [saaskit](https://github.com/saaskit/saaskit) - 用于构建SaaS应用程序的开发人员工具包.

## Sample Projects
*微服务和服务网格
  * [coolstore-microservices ](https://github.com/vietnam-devs/coolstore-microservices) - 容器化的多语言服务网格应用程序（Istio），包括基于.NET Core，NodeJS和更多运行在Kubernetes上的微服务.
  * [distributed-playground](https://github.com/jvandevelde/distributed-playground) - 分布式服务游乐场，包括Vagrant，Consul，Docker和ASP.NET Core.
  * [eShopOnContainers](https://github.com/dotnet/eShopOnContainers) - 基于微服务架构和容器的参考应用.
  * [magazine-website](https://github.com/thangchung/magazine-website) - 杂志网站（使用.NET Core，ASP.NET Core，EF Core），应用DDD，CQRS，微服务，异步编程.
  * [microservices-in-dotnetcore](https://github.com/horsdal/microservices-in-dotnetcore) - 我的微服务书中的代码示例 - [https://manning.com/books/microservices-in-net-core](https://manning.com/books/microservices-in-net-core)
  * [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - 实时交易平台演示，展示在整个应用程序堆栈中应用的反应式编程原理.
*巨石
  * [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) -  West Wind Album Viewer ASP.NET 5示例.
  * [allReady](https://github.com/HTBox/allReady) - 开源解决方案的重点是提高当地社区人道主义和灾害响应组织提供的准备活动的意识，效率和影响. [http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
  * [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) -  ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger.
  * [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) - 使用ASP.NET Core实现服务发现模式的示例.
  * [AspNetAuthorizationWorkshop](https://github.com/blowdart/AspNetAuthorizationWorkshop) - 一个研讨会，用于浏览ASP.NET核心授权中的各个新部分
  * [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/) 发布了12月Connect 2016大会，这是一套针对企业用户和消费者（自行车骑手）的一套复杂的互通应用程序： [Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps), [Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices), [Websites](https://github.com/Microsoft/BikeSharing360_Websites), [Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer), [Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer), [Cognitive Services Kiosk App](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp),
 [Azure Bot App](https://github.com/Microsoft/BikeSharing360_BotApps).
  * [cloudscribe](https://github.com/cloudscribe/cloudscribe) -  ASP.NET核心多租户Web应用程序基础.
  * [CoreCodeCamp](https://github.com/shawnwildermuth/CoreCodeCamp) - 用于运行小型本地开发活动的开源网站.
  * [DotNetClub](https://github.com/scheshan/DotNetClub) - 用ASP.NET Core编写的小俱乐部.
  * [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) - 具有单片部署模型的分层应用程序架构.
  * [Entropy](https://github.com/aspnet/Entropy) - 用于新功能和想法的混乱实验游乐场 - 请在此处查看针对各个功能的小型和简单样本.
  * [EquinoxProject](https://github.com/EduardoPires/EquinoxProject) - 具有DDD，CQRS和事件源的完整ASP.NET Core 2.0应用程序.
  * [GenVue](https://github.com/herbat73/GenVue) - 一个可托管的Web应用程序，允许机密用户上传和共享基于Vue.js，Vuetifyjs和NetCore WebAPI堆栈构建的私有文件
  * [guidance-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) - 如何使用Azure Active Directory进行身份验证，在Microsoft Azure上的多租户应用程序中管理用户身份.
  * [JustA.ML](https://github.com/mustakimali/JustA.ML)   - 一个Web应用程序，允许您在使用ASP.NET Core 2.0编写的设备之间共享文件/ URL /文本.  开源，住在 [https://justa.ml](https://justa.ml)
  * [MegaMine](https://github.com/Nootus/MegaMine) - 开源挖掘解决方案，帮助矿工提取黄金，石英，花岗岩等.该解决方案使用ASP.NET Core和AngularJS以微服务方式利用多个轻量级组件构建.
  * [minicompiler](https://github.com/ealsur/minicompiler) - 缩小，捆绑和编译样本.
  * [MusicStore](https://github.com/aspnet/MusicStore) - 使用MVC和Entity Framework的示例MusicStore应用程序.
  * [myFeed](https://github.com/worldbeater/myFeed)   - 为通用Windows平台构建的ReactiveUI应用程序示例.  使用PropertyChanged.Fody，DryIoc和Reactive Extensions演示MVVM模式和依赖注入的用法.
  * [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) - 带有.NET Core Preview 2的NLayerAppV3 N层架构.
  * [NorthwindTraders](https://github.com/JasonGT/NorthwindTraders) -  Northwind Traders是使用ASP.NET Core和Entity Framework Core构建的示例应用程序.
  * [Orchard Core - Modular and Multi-tenant applications](https://github.com/OrchardCMS/OrchardCore.Samples) - 使用Orchard Core Framework创建模块化和多租户应用程序.
  * [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript) - 使用ASP.NET Core，Angular 2和TypeScript的跨平台单页应用程序 [http://wp.me/p3mRWu-11L](http://wp.me/p3mRWu-11L).
  * [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore) - 每日更新的ASP.NET核心功能和设施的微量样本.
  * [StarWars](https://github.com/JacekKosciesza/StarWars) - 使用GraphQL for .NET，ASP.NET Core，Entity Framework Core的GraphQL“星球大战”示例.
 
## Articles
* 基础知识
  * [Microsoft architectual overview of comprehensive BikeSharing360 suite of demo apps with related videos](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [Porting a .NET Framework library to .NET Core](https://www.codeproject.com/Articles/1190475/Porting-a-NET-Framework-library-to-NET-Core)
  * [The 68 things the CLR does before executing a single line of your code](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-single-line-of-your-code/)
  * .NET Core和Nodejs之间的比较 [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) 和 [here](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
  * [Understanding ASP.NET Core Initialization](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/)
  * [Why you should join .NET Core and ASP.NET Core train](https://codingblast.com/why-you-should-join-asp-net-core/)
*云开发
  * [Configuring the AWS SDK in .NET Core](https://aws.amazon.com/blogs/developer/configuring-aws-sdk-with-net-core/)
  * [Serverless Architecture using C# and AWS Amazon Gateway Api/Lambda](https://www.codeproject.com/Articles/1178781/Serverless-Architecture-using-Csharp-and-AWS-Amazo)
  * [Using C# and .NET Core in Amazon Web Services (AWS) Lambda](https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
*配置和部署
  * [.NET project structure](https://gist.github.com/davidfowl/ed7564297c61fe9ab814)
  * [Adding Travis CI builds to a .NET Core app](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)
  * [ASP.NET Core 1.0 - Configure ApplicationInsights](http://social.technet.microsoft.com/wiki/contents/articles/35918.asp-net-core-1-0-configure-applicationinsights.aspx)
  * [haproxy, nginx, Angular 2, ASP.NET Core, Redis and Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/)
  * [Project.json to MSBuild conversion guide](http://www.natemcmaster.com/blog/2017/01/19/project-json-to-csproj/)
  * [Publishing a .NET project with Appveyor and NuGet](https://few-lines-of-code.blogspot.com/2016/03/publishing-net-project-with-appveyor.html)
  * [The New Configuration Model in ASP.NET Core](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
*实体框架核心
  * [.NET Core Data Access](https://blogs.msdn.microsoft.com/dotnet/2016/11/09/net-core-data-access/)
  * [A very good example about EF Core](https://github.com/rowanmiller/Demo-EFCore)
  * [Connect to Postgres with EF Core](http://en.otomatikmuhendis.com/2017/05/05/connect-to-postgres-with-ef-core/)
*神奇
  * [Getting started with Orchard Core as a NuGet package](http://www.ideliverable.com/blog/getting-started-with-orchard-core-as-a-nuget-package)
  * [How to export HTML to PDF in ASP.NET Core](https://code.msdn.microsoft.com/How-to-export-HTML-to-PDF-c5afd0ce)
  * [Vue.js server side rendering with ASP.NET Core](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
*安全
  * [.NET Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [ASP.NET Core 2.0 Authentication and Authorization System Demystified](https://digitalmccullough.com/posts/aspnetcore-auth-system-demystified.html)
  * [A walk-through for an ASP.NET Authorization Lab](https://github.com/blowdart/AspNetAuthorizationWorkshop)
  * [Authentication in ASP.NET Core](https://stormpath.com/blog/authentication-asp-net-core)
*测试
  * [Selenium with .NET Core](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)
- [InfoQ .NET articles](https://www.infoq.com/dotnet) - 在InfoQ网站上收集最好的.NET文章

## Books
* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)
* [ASP.NET Core Application Development: Building an application in four sprints (Developer Reference)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core in Action](https://www.manning.com/books/asp-net-core-in-action)
* [ASP.NET Core 1.0 High Performance](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [Building Microservices with ASP.NET Core: Develop, Test, and Deploy Cross-Platform Services in the Cloud](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp/1491961732)
* [C# 6 and .NET Core 1.0: Modern Cross-Platform Development](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [Dependency Injection in .NET Core, 2nd edition](https://www.manning.com/books/dependency-injection-in-dot-net-second-edition)
* [Exploring .NET Core with Microservices, ASP.NET Core, and Entity Framework Core - free eBook sampler](https://www.manning.com/books/exploring-dot-net-core)
* [Microservices in .NET Core: with C#, the Nancy framework, and OWIN middleware](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [Professional C# 6 and .NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [The little ASP.NET Core](https://www.recaffeinate.co/book)

## Cheat Sheets
* [dotnet cli Cheat Sheet](http://en.otomatikmuhendis.com/2018/07/02/cheat-sheet-for-dotnet-cli/)

## Videos
* [Channel9](https://channel9.msdn.com) -  MSDN
* [Channel9](https://www.youtube.com/channel/UCsMica-v34Irf9KVTh6xx-g) -  YouTube
 * [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)

## Podcasts
* [.NET Rocks](https://www.dotnetrocks.com)
* [Merge Conflict](http://www.mergeconflict.fm/)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)

## Community
* [.NET Foundation](http://forums.dotnetfoundation.org)
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

在法律允许的范围内， [thangchung](http://weblogs.asp.net/thangchung) 已放弃对此作品的所有版权及相关或相邻权利.
