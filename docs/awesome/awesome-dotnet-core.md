<div class="github-widget" data-repo="thangchung/awesome-dotnet-core"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome .NET Core [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

受启发 [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

 永远欢迎捐款！  请看看 [contribution guidelines](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md) pages first. We accept proprietary and commercial software too.

谢谢大家 [contributors](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors) ，您真棒，没有您就不可能！  目标是建立一个由社区驱动的非常知名的资源分类集合.

看看我 [blog](https://medium.com/@thangchung) 或打个招呼 [Twitter](https://twitter.com/thangchung)!


  * [Code Analysis and Metrics](#code-analysis-and-metrics)  

## General

* [ASP.NET Core Documentation](https://docs.asp.net/en/latest/) -官方的ASP.NET Core文档站点.
* [.NET Core Documentation](https://docs.microsoft.com/en-us/dotnet/articles/welcome) - Home of the technical documentation for .NET Core, C#, F# and Visual Basic, including basic concepts, getting started instructions, tutorials and samples.
* [.NET Core SDK](https://www.microsoft.com/net/core) -.NET Core SDK是由Microsoft和.NET社区在以下位置维护的通用开发平台： [GitHub](https://github.com/dotnet/core).
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/1719a3fe2a5c81b67a4909787da4a02fb0d0d419/Documentation/architecture/net-platform-standard.md) -NET的旧版本与新版本之间的差异.
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) -有关.NET Standard 2.0将会发生什么的说明以及当前.NET Standard某些缺少部分的路线图.
* [Clean Code .NET/.NET Core](https://github.com/thangchung/clean-code-dotnet) -适用于.NET / .NET Core的简洁代码概念.

## Frameworks, Libraries and Tools

### API

* [autorest](https://github.com/Azure/autorest) - Swagger (OpenAPI) Specification code generator featuring C# and Razor templates. Supports C#, Java, Node.js, TypeScript, Python and Ruby. `4.5.x or above`
* [aspnet-api-versioning](https://github.com/Microsoft/aspnet-api-versioning) -将服务API版本添加到ASP.NET Web API，具有ASP.NET Web API的OData和ASP.NET Core的库集.
* [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) -ASP.NET Core速率限制中间件.
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) -使用Kestrel和Consul的API冷凝器/反向代理，包括轻量的Consul库.
* [Flurl](https://github.com/tmenier/Flurl) -流利的URL构建器和可测试的.NET HTTP [https://flurl.dev](https://flurl.dev).
* GraphQL
  * [Dapper.GraphQL](https://github.com/landmarkhw/Dapper.GraphQL) -一个旨在将Dapper和graphql-dotnet项目集成在一起的库，主要考虑的是易用性和性能.
  * [graphql-aspnetcore](https://github.com/JuergenGutsch/graphql-aspnetcore) -ASP.NET Core MiddleWare创建GraphQL端点.
  * [graphql-convention](https://github.com/graphql-dotnet/conventions) -此库是顶部的补充层，允许您使用现有的属性获取器和方法作为字段解析器，将.NET类自动包装到GraphQL模式定义中
  * [graphiql-dotnet](https://github.com/JosephWoodward/graphiql-dotnet) -用于ASP.NET Core的GraphiQL中间件.
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) -基于.NET Core的GraphQL [https://github.com/graphql/graphql-js](https://github.com/graphql/graphql-js).
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) -用于.NET的GraphQL.
  * [graphql-dotnet-server](https://github.com/graphql-dotnet/server) -用于.NET的GraphQL-订阅传输WebSocket.
  * [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) -用于.Net Core和.NET Framework的GraphQL服务器.
  * [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL) -Facebook GraphQL查询语言的FSharp实现 [https://fsprojects.github.io/FSharp.Data.GraphQL](https://fsprojects.github.io/FSharp.Data.GraphQL).
  * [parser](https://github.com/graphql-dotnet/parser) -.NET中GraphQL的词法分析器和解析器.
  * [tanka-graphql](https://github.com/pekkah/tanka-graphql) -GraphQL执行和服务器库支持SignalR，Apollo，模式操纵以及Apollo和graphql-js熟悉的其他功能
* [halcyon](https://github.com/visualeyes/halcyon) -ASP.NET的HAL实现.
* [JSON API .NET Core](https://github.com/Research-Institute/json-api-dotnet-core) -构建json：api兼容API的框架，旨在消除RESTful样板.
* [LightNode](https://github.com/neuecc/LightNode) -基于OWIN的Micro RPC / REST框架 [http://neuecc.github.io/LightNode](http://neuecc.github.io/LightNode).
* [NetCoreStack.Proxy](https://github.com/NetCoreStack/Proxy) -用于.NET Standard 2.0的类型安全的分布式REST库（NetCoreStack Flying Proxy）
* [NSwag](https://github.com/RSuter/NSwag) -用于.NET，Web API和TypeScript的Swagger / OpenAPI工具链. [http://NSwag.org](http://NSwag.org).
* [OData](https://github.com/OData/WebApi/tree/feature/netcore) -开放数据协议（OData）支持创建基于HTTP的数据服务，该服务允许Web客户端使用简单的HTTP消息发布和编辑基于HTTP的数据服务，这些资源使用统一资源标识符（URI）标识并在抽象数据模型中定义.
* [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) - OpenAPI Generator allows generation of API client libraries (e.g. C#, TypeScript, etc), server stubs (ASP.NET Core, NancyFx, etc), documentation and configuration automatically given an OpenAPI Spec (v2, v3).
* [refit](https://github.com/paulcbetts/refit) -Xamarin和.NET的自动类型安全REST库.
* [RestClient.Net](https://github.com/MelbourneDeveloper/RestClient.Net) - Cross Platform REST Client for all C# platforms
* [RestEase](https://github.com/canton7/RestEase) -易于使用的类型安全REST API客户端库，这是简单且可自定义的.
* [RestLess](https://github.com/letsar/RestLess) -用于.Net Standard的自动类型安全无反射REST API客户端库.
* [Restier](https://github.com/OData/RESTier) -RESTier是一个RESTful API开发框架，用于在.NET平台上构建基于OData V4的标准化RESTful服务.
* [Restsharp](https://github.com/restsharp/RestSharp) -适用于.NET的简单REST和HTTP API客户端
* [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) -无缝地向WebApi项目添加了招摇.
  * [MicroElements.Swashbuckle.FluentValidation](https://github.com/micro-elements/MicroElements.Swashbuckle.FluentValidation) -添加FluentValidation规则来招摇.
  * [Swashbuckle.AspNetCore.Filters](https://github.com/mattfrear/Swashbuckle.AspNetCore.Filters) -一堆用于Swashbuckle.AspNetCore的有用过滤器.
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core) -ASP.NET Core的社区贡献.

### Application Frameworks
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate)  -ASP.NET Boilerplate是一个通用应用程序框架，专门为新的现代Web应用程序设计.  它使用已经熟悉的工具并实施围绕它们的最佳实践，以为您提供SOLID开发经验.
* [Abp vNext](https://github.com/abpframework/abp) -Abp vNext是下一代开源 [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate)  框架.  它是创建现代Web应用程序的完整体系结构和强大的基础架构！
遵循最佳实践和约定，为您提供SOLID开发经验.
* [AsyncEx](https://github.com/StephenCleary/AsyncEx) -异步/等待的帮助程序库.
* [Aeron.NET](https://github.com/AdaptiveConsulting/Aeron.NET) -高效可靠的UDP单播，UDP组播和IPC消息传输-Aeron的.NET端口.
* [akka.net](https://github.com/akkadotnet/akka.net) -用于在.NET和Mono上构建高度并发，分布式和容错事件驱动的应用程序的工具包和运行时.
* [Aggregates.NET](https://github.com/volak/Aggregates.NET) -Aggregates.NET是一个框架，可帮助开发人员将出色的NServiceBus和EventStore库集成在一起.
* [ASP.NET MVC](https://github.com/aspnet/Mvc) -模型视图控制器框架，用于构建具有清晰关注点的动态网站，包括合并的MVC，Web API和带有Razor的Web页面.
* [Butterfly Server .NET](https://github.com/firesharkstudios/butterfly-server-dotnet)  -允许轻松地构建实时Web应用程序和本机应用程序.  定义一个Web API和Subscription API，它们可以自动在连接的客户端之间同步数据集.
* [CAP](https://github.com/dotnetcore/CAP) -具有本地持久消息功能的EventBus，用于SOA或微服务体系结构中的系统集成.
* [Carter](https://github.com/CarterCommunity/Carter) - Carter is a library that allows Nancy-esque routing for use with ASP.Net Core.
* [Chromely](https://github.com/mattkol/Chromely) -轻巧的替代Electron.NET，Electron for .NET / .NET Core
* [Cinchoo ETL](https://github.com/Cinchoo/ChoETL) -用于.NET的ETL框架（用于CSV，Flat，Xml，JSON，键值格式的文件的解析器/编写器）.
* [CQRSlite](https://github.com/gautema/CQRSlite) - Lightweight framework for helping writing CQRS and Eventsourcing applications in C#.
* [dataaccess_aspnetcore](https://github.com/digipolisantwerp/dataaccess_aspnetcore) -DataAccess Toolbox包含使用工作单元和存储库模式在带有Entity Framework Core 1.0的ASP.NET Core中进行数据访问的基类.
* [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore) -用于基于ASP.NET Core构建高质量Web应用程序的轻量级和可扩展基础结构.
* [DotNetCorePlugins](https://github.com/natemcmaster/DotNetCorePlugins) -.NET Core库，用于将程序集作为插件加载.
* [DotnetSpider](https://github.com/dotnetcore/DotnetSpider)  -DotnetSpider，一个类似于WebMagic和Scrapy的.NET Standard Web爬网库.  它是.NET的轻量级，高效且快速的高级Web爬网和抓取框架.
* [DotNetty](https://github.com/Azure/DotNetty) -Netty端口，事件驱动的异步网络应用程序框架.
* [dotvvm](https://github.com/riganti/dotvvm) -用于Web应用程序的开源MVVM框架.
* [ElectronNET](https://github.com/ElectronNET/Electron.NET) -使用ASP.NET NET Core构建跨平台的桌面应用程序.
* [EmbedIO](https://github.com/unosquare/embedio) -用于.NET Framework和.NET Core的微型，跨平台，基于模块的Web服务器.
* [Ether.Network](https://github.com/aloisdg/Ether.Network) -Ether.Network是一个开放源代码网络库，允许开发人员通过TCP / IP协议创建简单，快速和可扩展的套接字服务器或客户端应用程序.
* [EventFlow](https://github.com/eventflow/EventFlow) -异步/等待用于.NET的第一个CQRS + ES和DDD框架.
* [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - Lightweight and fast library written in C# for reading Microsoft Excel files.
* [ExtCore](https://github.com/ExtCore) -免费，开源和跨平台框​​架，用于基于ASP.NET Core 1.0创建模块化和可扩展的Web应用程序.
* [Finbuckle.MultiTenant](https://github.com/Finbuckle/Finbuckle.MultiTenant)  -Finbuckle.MultiTenant是一个.NET标准库，用于为ASP.NET 2.0+设计的多租户支持.  它提供用于租户解析，每个租户应用程序配置和每个租户数据隔离的功能.
* [fission](https://github.com/fission/fission) -Kubernetes的快速无服务器功能.
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp)  -远程过程调用（RPC）为构建分布式应用程序和服务提供了有用的抽象.  该存储库中的库提供了gRPC协议的具体实现，该协议位于HTTP / 2上.  这些库允许使用支持的语言的任意组合在客户端和服务器之间进行通信.
* [Halibut](https://github.com/OctopusDeploy/Halibut) -使用SSL上的JSON-RPC的.NET安全通信堆栈.
* [MagicOnion](https://github.com/neuecc/MagicOnion) -用于.NET，.NET Core和Unity的基于gRPC的HTTP / 2 RPC流框架.
* [MassTransit](https://github.com/MassTransit/MassTransit) -.NET的分布式应用程序框架. 
* [microdot](https://github.com/gigya/microdot) -开源.NET微服务框架.
* [MoreLINQ](https://github.com/morelinq/MoreLINQ) -LINQ对象扩展.
* [Nancy](https://github.com/NancyFx/Nancy) -轻量级，低礼仪的框架，用于在.NET和Mono上构建基于HTTP的服务.
* [opencvsharp](https://github.com/shimat/opencvsharp) -用于OpenCV的.NET Framework包装器.
* [orleans](https://github.com/dotnet/orleans) -框架，提供了一种直接的方法来构建分布式大规模计算应用程序，而无需学习和应用复杂的并发或其他扩展模式.
* [protoactor-dotnet](https://github.com/AsynkronIT/protoactor-dotnet) -适用于Golang和C的超快速分布式演员# [http://proto.actor](http://proto.actor).
* [resin](https://github.com/kreeben/resin) -具有HTTP API和可插拔读/写管道的16位宽矢量空间搜索引擎.
* [RService.io](https://github.com/Stoom/RService.IO) -专注于速度和易用性的ASP.Net Core RESTful微服务框架.
* [ServiceStack](https://github.com/ServiceStack/ServiceStack) - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all [https://servicestack.net](https://servicestack.net).
* [Steeltoe OSS](https://github.com/SteelToeOSS) -用于常见微服务模式的.NET工具包.
* [Strathweb.TypedRouting.AspNetCore](https://github.com/filipw/Strathweb.TypedRouting.AspNetCore) -在ASP.NET Core MVC项目中启用强类型路由的库.
* [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0.
* [X.PagedList](https://github.com/dncuug/X.PagedList) -用于在ASP.NET/ASP.NET Core中轻松浏览任何IEnumerable / IQueryable的库.

### Application Templates
* [.NET Boxed](https://github.com/Dotnet-Boxed/Templates)  -包含电池的项目模板，为您提供所需的最少代码量.  包括ASP.NET Core API和GraphQL模板.
* [aspnet-core-react-template](https://github.com/bradymholt/aspnet-core-react-template) -ASP.NET Core 2.0 / React SPA模板应用程序.
* [AspNetCoreSpa](https://github.com/asadsahi/AspNetCoreSpa) -具有Angular CLI功能齐全的应用程序的Asp.Net Core 2+和Angular 6 SPA.
* [ASP.NET-MVC-Template](https://github.com/NikolayIT/ASP.NET-MVC-Template) -ASP.NET MVC 5和ASP.NET Core的现成模板，其中已修复存储库，服务，模型映射以及DI和StyleCop警告.
* [AddFeatureFolders](https://github.com/OdeToCode/AddFeatureFolders) -在ASP.NET Core中为MVC控制器和视图启用功能文件夹.
* [Angular Visual Studio Webpack Starter](https://github.com/damienbod/AngularWebpackVisualStudio)  -Webpack，Visual Studio，ASP.NET Core和Angular的模板.  应用程序的客户端和服务器端都在一个ASP.NET Core项目中实现，这使部署变得更加容易.
* [DNTFrameworkCoreTemplate](https://github.com/rabbal/DNTFrameworkCoreTemplate) -基于的样板项目模板 [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore)
* [dotnet new caju](https://github.com/ivanpaulovich/dotnet-new-caju)  -具有出色架构风格的dotnet新模板！  提高生产力，以基于六边形，干净或事件来源的体系结构样式设计分层的应用程序.  它支持多种数据访问框架（MongoDB，EntityFramework，Dapper或Kafka），并且是完全可测试的.
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices) -Microsoft ASP.NET Core JavaScript服务.
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core) -基于HTML5，基于jQuery的小部件库，用于构建现代Web应用程序. [http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui).
* [QuickApp](https://github.com/emonney/QuickApp) -具有完整的登录，用户和角色管理的ASP.NET Core / Angular4启动项目模板.
* [Serenity](https://github.com/volkanceylan/Serenity) -Serenity是一个ASP.NET MVC / TypeScript应用程序平台，旨在通过基于服务的体系结构简化和缩短以数据为中心的业务应用程序的开发.
* [Toucan](https://github.com/mrellipse/toucan)  -用于构建单页应用程序的样板.  服务器是围绕SOLID原则设计的多项目.Net Core解决方案.  客户端是TypeScript 2，Vuejs 2，Vuex 2.

### Authentication and Authorization
* [AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) -用于OWIN / Katana和ASP.NET Core的OpenID Connect / OAuth2服务器框架.
* [Auth0](https://github.com/auth0/auth0.net) -托管的企业级平台，用于提供现代身份.
* [Casbin.NET](https://github.com/casbin-net/Casbin.NET) -授权库，支持C中的访问控制模型，如ACL，RBAC，ABAC#
* [Cierge](https://github.com/PwdLess/Cierge)  -Cierge是OpenID Connect服务器，用于处理用户注册，登录，配置文件，管理，社交登录等.  Cirege不用存储密码，而是使用魔术链接/代码和外部登录来验证您的用户.
* [Identity](https://github.com/aspnet/Identity) -ASP.NET Core身份是用于构建ASP.NET Core Web应用程序的成员资格系统，包括成员资格，登录名和用户数据.
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) -用于ASP.NET Core 1.0和2.0的IdentityServer
  * [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework) -EntityFramework持久层
  * [IdentityServer4.MongoDB](https://github.com/diogodamiani/IdentityServer4.MongoDB) -MongoDB持久层
  * [IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) -实体框架核心持久层
  * [IdentityServer4.Templates](https://github.com/IdentityServer/IdentityServer4.Templates) -IdentityServer4的dotnet cli模板.
* [openiddict](https://github.com/openiddict/openiddict-core) -用于ASP.NET Core的易于使用的OpenID Connect服务器.
  * [oidc-debugger](https://github.com/nbarbettini/oidc-debugger) -OAuth 2.0和OpenID Connect调试工具.
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) -建立 [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) 使用Stormpath和ASP.NET Core. 
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) -建立 [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) 使用Stormpath和ASP.NET Core.（不建议使用：自加入OKTA之后，它将在2017年3月之前得到更新） 
* [stuntman](https://github.com/ritterim/stuntman) -用于在开发过程中利用ASP.NET Identity模仿用户的库.

### Blockchain
* [BTCPayServer](https://github.com/btcpayserver/btcpayserver) -与Bitpay API兼容的跨平台，自托管服务器.
* [Meadow](https://github.com/MeadowSuite/Meadow) -集成的以太坊实施和工具套件，专注于Solidity测试和开发.
* [NBitcoin](https://github.com/MetacoSA/NBitcoin) -用于.NET框架的综合比特币库.
* [NBlockchain](https://github.com/danielgerlag/NBlockchain) -.NET标准库，用于构建启用了区块链的应用程序
* [NBXplorer](https://github.com/dgarage/NBXplorer) -比特币和Altcoin轻量级区块浏览器.
* [NEO](https://github.com/neo-project/neo) -智慧经济的开放网络.
* [Nethereum](https://github.com/Nethereum) -将以太坊的热爱带到.NET.
* [Nethermind](https://github.com/NethermindEth/nethermind) -.NET Core以太坊客户端
* [StratisBitcoinFullNode](https://github.com/stratisproject/StratisBitcoinFullNode) - Simple and affordable end-to-end solutions for development, testing and deployment of native C# blockchain applications on the .Net framework.
* [Trezor.Net](https://github.com/MelbourneDeveloper/Trezor.Net) - Cross platform C# library for talking to the Trezor Hardwarewallet
* [WalletWasabi](https://github.com/zkSNACKs/WalletWasabi) -注重隐私，符合ZeroLink的比特币钱包.

### Bot
* [BotSharp](https://github.com/SciSharp/BotSharp) - The Open Source AI Chatbot Platform Builder in 100% C# Running in .NET Core with Machine Learning algorithm.
* [NadekoBot](https://github.com/Kwoth/NadekoBot) - Open source, general-purpose Discord chat bot written in C#.
* [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) - C# Telegram Bot API library.
* [Funogram](https://github.com/Dolfik1/Funogram) - F# Telegram Bot Api library.

### Build Automation
* [cake-build](https://github.com/cake-build/cake) -跨平台构建自动化系统.
* [CatLight](https://catlight.io)  -用于监视项目中的构建和任务的开发人员的状态通知程序.  使用.Net Core和Electron构建.
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) - Style your C# console output!
* [dotnet-docker](https://github.com/dotnet/dotnet-docker) -用于.NET Core和.NET Core工具的基本Docker映像.
* [Dockerize.NET](https://github.com/brthor/Dockerize.NET) -将您的.NET Core应用程序打包到Docker映像中的.NET Cli工具：“ dotnet dockerize”
* [FlubuCore](https://github.com/flubu-core/flubu.core) - A cross platform build and deployment automation system for building projects and executing deployment scripts using C# code.
* [GitInfo](https://github.com/kzu/GitInfo) - Git and SemVer Info from MSBuild, C# and VB.
* [GitVersioning](https://github.com/AArnott/Nerdbank.GitVersioning) -使用单个简单version.txt文件中的版本标记您的程序集和NuGet程序包，并包括用于非官方构建的git commit ID.
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet) -.NET Core Runtime的包装器.
* [Image2Docker](https://github.com/docker/communitytools-image2docker-win) -将现有Windows应用程序工作负载移植到Docker的PowerShell模块.
* [LocalAppVeyor](https://github.com/joaope/LocalAppVeyor) -在本地运行AppVeyor构建.
* [msbuild](https://github.com/Microsoft/msbuild) -Microsoft Build Engine是用于构建应用程序的平台.
* [Nuke](https://github.com/nuke-build/nuke) -跨平台的构建自动化系统.
* [Opserver](https://github.com/opserver/Opserver) -Stack Exchange的监控系统.
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) -Visual Studio Team Services构建和发布代理.

### Bundling and Minification
* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) -Visual Studio扩展，可让您配置JS，CSS和HTML文件的捆绑和最小化.
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine)  -ASP.NET MVC ViewEngine，用于在JavaScript环境中呈现标记.  是React和Angular服务器端渲染的理想选择.
* [Smidge](https://github.com/Shazwazza/Smidge/) -用于ASP.NET Core的轻量级运行时CSS / JavaScript文件压缩，组合，压缩和管理库.
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin)  -包含一组标记缩小符的.NET库.  该项目的目的是通过减少HTML，XHTML和XML代码的大小来提高Web应用程序的性能.

### Caching
* [CacheManager](https://github.com/MichaCo/CacheManager) - Open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. [http://cachemanager.michaco.net](http://cachemanager.michaco.net)
* [EasyCaching](https://github.com/dotnetcore/EasyCaching) -开源缓存库，其中包含缓存的基本用法和一些高级用法，它们可以帮助我们更轻松地处理缓存.
* [Faster](https://github.com/Microsoft/FASTER/tree/master/cs) -来自Microsoft Research的快速键值存储.
* [Foundatio](https://github.com/exceptionless/Foundatio) -用于构建分布式应用程序的可插拔基础块.
* [Microsoft Caching](https://github.com/aspnet/Caching) -用于内存中缓存和分布式缓存的库.
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) - High performance general purpose redis client for .NET languages (C# etc).

### CMS
* [Awesome-CMS-Core](https://github.com/SaiGonSoftware/Awesome-CMS-Core) -Awesome CMS Core是使用ASP.Net Core和ReactJS构建的开源CMS，考虑了模块分离的问题，并提供了最新的技术趋势，例如.Net Core，React，Webpack，SASS，后台作业，消息队列.
* [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core) -ASP.NET应用程序提供常见的博客功能.
* [Cofoundry](https://github.com/cofoundry-cms/cofoundry)  -开源.NET Core CMS和模块化应用程序框架.  代码优先，不显眼且可扩展.
* [CoreWiki](https://github.com/csharpfritz/CoreWiki) -在实时编码流中我们正在研究的简单ASP.NET Core Wiki.
* [dasblog-core](https://github.com/poppastring/dasblog-core) -使用ASP.NET Core重新构想的原始DasBlog
* [Miniblog](https://github.com/madskristensen/Miniblog.Core) -一个ASP.NET Core博客引擎.
* [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS)  -一个开放源代码的ASP.NET Core 2.0 CMS.  它目前支持MySQL，并计划实现MSSQL，SQLite和PostgreSQL.  它还是一个模块化的CMS，支持主题，外观，自定义布局，小部件，多种语言（英语，英语）.
* [Piranha CMS](https://github.com/piranhacms/piranha.core) -用于ASP.NET Core和Entity Framework Core的轻量级且不干扰用户的开源CMS.
* [Platformus](https://github.com/Platformus) -基于ASP.NET Core 1.0和ExtCore框架的免费，开源和跨平台CMS.
* [Squidex](https://github.com/Squidex/squidex) -无头CMS，基于MongoDB，CQRS和事件源.
* [Swastika I/O Core CMS](https://github.com/Swastika-IO/Swastika-IO-Core)  -开源ASP.NET Core 2.x CMS.  它目前支持MS SQL，并计划在不久的将来实现MSSQL，SQLite.  它具有许多内置功能，例如多语言支持，主题，模板...
* [Weapsy](https://github.com/Weapsy/Weapsy)  -基于DDD和CQRS的开源ASP.NET Core CMS.  它开箱即用地支持MSSQL，MySQL，SQLite和PostgreSQL.
* [ZKEACMS](https://github.com/SeriaWei/ZKEACMS.Core) -视觉设计，通过拖放构建站点.

### Code Analysis and Metrics
* [awesome-static-analysis](https://github.com/mre/awesome-static-analysis) -各种编程语言的静态分析工具，lint和代码质量检查器的精选列表.
*代码分析
  * [CodeFormatter](https://github.com/dotnet/codeformatter) - Tool that uses Roslyn to automatically rewrite the source to follow netfx coding styles. [Nuget Package](https://www.nuget.org/packages/Dotnet.CodeFormatter.BuildTask.Fork) 
  * [DevSkim](https://github.com/Microsoft/DevSkim) -一组提供安全“整理”功能的IDE插件和规则.
  * [RefactoringEssentials](https://github.com/icsharpcode/RefactoringEssentials) -重构Visual Studio的基础.
  * [roslyn-analyzers](https://github.com/dotnet/roslyn-analyzers) -.NET编译器平台（“ Roslyn”）分析器.
  * [StyleCopAnalyzers](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) -使用.NET编译器平台的StyleCop规则.
*指标
  * [AppMetrics](https://github.com/alhardy/AppMetrics) -App Metrics是一个开放源代码和跨平台的.NET库，用于记录和报告应用程序中的指标并报告其运行状况.
  * [Audit.NET](https://github.com/thepirat000/Audit.NET) -审核.NET对象更改的小型框架.
  * [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) -强大的.NET库用于基准测试.
  * [coverlet](https://github.com/tonerdo/coverlet) -.NET Core的跨平台代码覆盖库.
  * [Foundatio](https://github.com/exceptionless/Foundatio#metrics) -具有内存，redis，StatsD和Metrics.NET实现的通用接口.
  * [MiniCover](https://github.com/lucaslorentz/minicover) -.NET Core的极简代码覆盖率工具.
  * [NBench](https://github.com/petabridge/NBench) -.NET应用程序的性能基准测试框架.
  * [Nexogen.Libraries.Metrics](https://github.com/nexogen-international/Nexogen.Libraries.Metrics) -用于在.NET中收集应用程序指标并将其导出到Prometheus的库.
  * [OpenCover](https://github.com/OpenCover/opencover) -适用于.NET 2及更高版本（仅限WINDOWS OS）的代码覆盖工具，支持带有分支点和序列点的32和64个进程.
  * [PerformanceMonitor](https://github.com/dotnet-architecture/PerformanceMonitor) -.NET核心应用程序性能监视器.
  * [prometheus-net](https://github.com/prometheus-net/prometheus-net) -.NET客户端 [https://prometheus.io](https://prometheus.io).
  * [Prometheus.Client](https://github.com/PrometheusClientNet/Prometheus.Client) -.NET客户端 [Prometheus](https://prometheus.io).
  	* [Prometheus.Client.MetricPusher](https://github.com/PrometheusClientNet/Prometheus.Client.MetricPusher) -将指标推送到Prometheus.Client的PushGateaway.
  	* [Prometheus.Client.AspNetCore](https://github.com/PrometheusClientNet/Prometheus.Client.AspNetCore) -Prometheus.Client的中间件.
  	* [Prometheus.Client.MetricServer](https://github.com/PrometheusClientNet/Prometheus.Client.MetricServer) -Prometheus.Client的MetricServer.
  	* [Prometheus.Client.HttpRequestDurations](https://github.com/PrometheusClientNet/Prometheus.Client.HttpRequestDurations) -Prometheus.Client的请求持续时间的度量记录.

### Compression
* [lz4net](https://github.com/MiloszKrajewski/K4os.Compression.LZ4) -适用于所有.NET平台的超快速压缩算法.
* [sharpcompress](https://github.com/adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats.

### Compilers, Transpilers and Languages
* [Fable](https://github.com/fable-compiler/Fable) - F# to JavaScript Compiler.
* [fparsec](https://github.com/stephan-tolksdorf/fparsec) - A parser combinatory library for F# and C#.
* [IL2C](https://github.com/kekyo/IL2C) -ECMA-335 CIL / MSIL到C语言的翻译器.
* [Mond](https://github.com/Rohansi/Mond) - A dynamically typed scripting language written in C# with a REPL, debugger, and simple embedding API.
* [peachpie](https://github.com/peachpiecompiler/peachpie) -开源PHP编译器到.NET.
* [Pidgin](https://github.com/benjamin-hodgson/Pidgin) - A lightweight, fast and flexible parsing library for C#, developed at Stack Overflow.
* [roslyn](https://github.com/dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs.
* [Sprache](https://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework.

### Cryptography
* [BCrypt.Net](https://github.com/BcryptNet/bcrypt.net) -将更新带到原始bcrypt软件包.
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core) -BCrypt.NET的.NET Core端口用于安全存储密码.
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols.
* [multiformats](https://github.com/multiformats/cs-multihash) -通用哈希库，但是用于编码/解码多哈希的库，它是“容器”，用于描述使用摘要计算的哈希算法.
* [nsec](https://github.com/ektrah/nsec) -NSec是基于libsodium的.NET Core的新密码库.
* [SecurityDriven.Inferno](https://github.com/thangchung/awesome-dotnet-core/blob/master/github.com/sdrapkin/SecurityDriven.Inferno) -使用.Net原语的Hig级加密库已经过专业审核.

### Database
* [DBreeze](https://github.com/hhblaze/DBreeze) - C# .NET MONO NOSQL (key value store embedded) ACID multi-paradigm database management system.
* [JsonFlatFileDataStore](https://github.com/ttu/json-flatfile-datastore) -简单的JSON平面文件数据存储，支持类型化和动态数据.
* [LiteDB](https://github.com/mbdavid/LiteDB) -.NET NoSQL文档存储在单个数据文件中- [http://www.litedb.org](http://www.litedb.org).
* [NoDb](https://github.com/joeaudette/NoDb) -.NET Core / ASP.NET Core的“无数据库”文件系统存储，因为并非每个项目都需要一个数据库.
* [marten](https://github.com/JasperFx/marten) -Postgresql作为.NET应用程序的文档数据库和事件存储 [http://jasperfx.github.io/marten](http://jasperfx.github.io/marten).
* [StringDB](https://github.com/SirJosh3917/StringDB) -StringDB是一个模块化的键/值对档案数据库，旨在消耗少量的ram并产生小型的数据库.
* [yessql](https://github.com/sebastienros/yessql) -适用于任何RDBMS的.NET文档数据库.

### Database Drivers
* [cassandra-csharp-driver](https://github.com/datastax/csharp-driver) - DataStax C# Driver for Apache Cassandra.
* [confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet) -Confluent的Apache Kafka .NET客户端.
* [couchbase-lite-net](https://github.com/couchbase/couchbase-lite-net) -用于.NET的轻量级，面向文档（NoSQL），可同步的数据库引擎.
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) -适用于MongoDB的.NET驱动程序.
* MySQL
  * [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/8.0) -Connector / Net是MySQL的完全托管的ADO.NET驱动程序.
  * [MySqlConnector](https://github.com/mysql-net/MySqlConnector) -用于.NET和.NET Core的异步MySQL连接器.
* Neo4j
  * [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) -.NET的Neo4j Bolt驱动程序.
  * [Neo4jClient](https://github.com/Readify/Neo4jClient) -Neo4j的.NET客户端绑定.
* [npgsql](https://github.com/npgsql/npgsql) - .NET data provider for PostgreSQL. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) -为.NET启用Linq的文档数据库.
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) - C#/.NET RethinkDB driver with 100% ReQL API coverage.
* [progaudi.tarantool](https://github.com/progaudi/progaudi.tarantool) -Tarantool NoSql数据库的.NET客户端.

### Database Tools and Utilities
* [DbUp](https://github.com/DbUp/DbUp)  -.NET库，可帮助您将更改部署到SQL Server数据库.  它跟踪哪些SQL脚本已经运行，并运行使数据库更新所需的更改脚本.
* [Evolve](https://github.com/lecaillon/Evolve)  -使用普通SQL脚本的简单数据库迁移工具.  受Flyway启发.
* [EFCorePowerTools](https://github.com/ErikEJ/EFCorePowerTools) -实体框架核心动力工具-EF Core的逆向工程，迁移和模型可视化.
* [fluentmigrator](https://github.com/fluentmigrator/fluentmigrator) -.NET的迁移框架非常类似于Ruby on Rails迁移.
* [monitor-table-change-with-sqltabledependency](https://github.com/christiandelbianco/monitor-table-change-with-sqltabledependency) -获取有关记录表更改的SQL Server通知.
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData) -具有OLAP操作和数据透视表数据模型的内存中数据多维数据集.
* [roundhouse](https://github.com/chucknorris/roundhouse) -使用SQL文件和基于源代码控制的版本控制的.NET数据库迁移实用程序.
* [SharpRepository](https://github.com/SharpRepository/SharpRepository) - SharpRepository is a generic repository written in C# which includes support for various relational, document and object databases including Entity Framework, RavenDB, MongoDb and Db4o. SharpRepository includes Xml and InMemory repository implementations as well.
* [TrackableEntities.Core](https://github.com/TrackableEntities/TrackableEntities.Core) -使用.NET Core跨服务边界进行更改跟踪.
* [Mongo.Migration](https://github.com/SRoddis/Mongo.Migration) -Mongo.Migration专为 [MongoDB C# Driver](https://github.com/thangchung/awesome-dotnet-core/blob/master/ https://github.com/mongodb/mongo-csharp-driver) to migrate your documents easily and on-the-fly. No more downtime for schema-migrations. Just write small and simple migrations. [Link](https://github.com/thangchung/awesome-dotnet-core/blob/master/ https://github.com/SRoddis/Mongo.Migration)

### Date and Time
* [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions) -DateTimeRange，营业日以及各种DateTime，DateTimeOffset，TimeSpan扩展方法.
* [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime)  -允许您编写更整洁的DateTime表达式和操作.  部分受到Ruby DateTime扩展的启发.
* [nodatime](https://github.com/nodatime/nodatime) -更好的.NET日期和时间API [http://nodatime.org](http://nodatime.org).

### Distributed Computing
* [AspNetCore.Diagnostics.HealthChecks](https://github.com/xabaril/AspNetCore.Diagnostics.HealthChecks) -ASP.NET Core诊断包的企业运行状况检查
  - [BeatPulse](https://github.com/Xabaril/BeatPulse) -使负载平衡器可以监控已部署的Web应用程序的状态
* [Foundatio](https://github.com/exceptionless/Foundatio) - Pluggable foundation blocks for building distributed apps
* [Rafty](https://github.com/ThreeMammals/Rafty) -.NET Core中的RAFT共识
* [Obvs](https://github.com/christopherread/Obvs) -可观察的微服务总线.NET库，将基础传输包装在基于Rx的简单接口中
* [Ocelot](https://github.com/ThreeMammals/Ocelot) -使用.NET Core创建的API网关
* [OpenTracing](https://github.com/opentracing/opentracing-csharp) -供应商中立的API和用于分布式跟踪的工具
* [Polly](https://github.com/App-vNext/Polly) -.NET 3.5 / 4.0 / 4.5 / PCL库，允许开发人员以流畅的方式表达瞬时异常和故障处理策略，例如重试，永远重试，等待和重试或断路器
* [ProxyKit](https://github.com/damianh/ProxyKit) -在ASP.NET Core上创建代码优先的HTTP反向代理的工具包

### E-Commerce and Payments
* [nopCommerce](https://github.com/nopSolutions/nopCommerce) -具有广泛的社区和充满新功能，主题和插件的市场的免费开源电子商务购物车（ASP.NET MVC / ASP.NET Core MVC）.
* [GrandNode](https://github.com/grandnode/grandnode) -基于ASP.NET Core 2.1和MongoDB的多平台，免费，开源电子商务购物车 [nopCommerce](https://github.com/nopSolutions/nopCommerce).
* [PayPal](https://github.com/paypal/PayPal-NET-SDK) -用于PayPal RESTful API的.NET SDK.
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) -建立在.NET Core上的超级简单的电子商务系统.
* [Stripe](https://github.com/ServiceStack/Stripe) -用于stripe.com REST API的.NET客户端.


### Exceptions
* [Demystifier](https://github.com/benaadams/Ben.Demystifier) -对堆栈跟踪有很高的了解（使错误日志更高效）.
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) -出色的.NET客户端
* [GlobalExceptionHandlerDotNet](https://github.com/JosephWoodward/GlobalExceptionHandlerDotNet) -GlobalExceptionHandlerDotNet允许您将ASP.NET Core应用程序管道中的异常处理配置为约定，而不是在每个控制器操作中显式处理它们.

### Functional Programming
* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) - Functional Extensions for C#.
* [DynamicData](https://github.com/RolandPheasant/DynamicData) -基于Rx.NET的反应式集合.
* [echo-process](https://github.com/louthy/echo-process) - Actor library for C# with additional modules that support persistence to Redis, as well as JS integration.
* [FsCheck](https://github.com/fscheck/FsCheck) -.NET的随机测试.
* [Giraffe](https://github.com/dustinmoris/Giraffe) - A native functional ASP.NET Core web framework for F# developers.
* [language-ext](https://github.com/louthy/language-ext) - C# functional language extensions and 'Erlang like' concurrency system.
* [LaYumba.Functional](https://github.com/la-yumba/functional-csharp-code) - Utility library for programming functionally in C#.
* [NetMQ.ReactiveExtensions](https://github.com/NetMQ/NetMQ.ReactiveExtensions)  -使用响应式扩展（RX）轻松地在网络上的任何地方发送消息.  传输协议为ZeroMQ.
* [Optional](https://github.com/nlkl/Optional) - A robust option type for C#.
* [reactive-streams-dotnet](https://github.com/reactive-streams/reactive-streams-dotnet) - [Reactive Streams](http://www.reactive-streams.org/) 用于.NET.
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) -MVVM框架与.NET的Reactive Extensions集成在一起，以创建可在任何移动或桌面平台上运行的优雅，可测试的用户界面.
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) - [Reactive Extensions](http://reactivex.io) 用于.NET.
* [Qactive](https://github.com/RxDave/Qactive)  -反应性可查询的可观察框架.  `4.xx或以上`
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/)  -功能反应式编程（FRP）库.  `4.xx或以上`

### Graphics
* [GLFWDotNet](https://github.com/smack0007/GLFWDotNet) -GLFW的.NET绑定.
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) -围绕System.Drawing的流畅包装器，用于处理图像文件 [http://imageprocessor.org](http://imageprocessor.org) .  4.5.x或以上
* [ImageSharp](https://github.com/SixLabors/ImageSharp) - Cross-platform library for processing of image files written in C#.
* [LibVLCSharp](https://github.com/videolan/libvlcsharp)：.libvlc的.NET / Mono绑定，它是由VideoLAN制作的VLC应用程序的多媒体框架.
* [Magick.NET](https://github.com/dlemstra/Magick.NET) - The .NET library for ImageMagick.
* [MagicScaler](https://github.com/saucecontrol/PhotoSauce) -适用于.NET的MagicScaler高性能，高质量图像处理管道
* [QRCoder](https://github.com/codebude/QRCoder) - A pure C# Open Source QR Code implementation.
* [SharpBgfx](https://github.com/MikePopoloski/SharpBgfx) - C# bindings for the bgfx graphics library.
* [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching) -在支持.NET Core的.NET应用程序中使用的图像处理库.
* [veldrid](https://github.com/mellinoe/veldrid) -用于.NET的底层，硬件加速的3D图形库.

### GUI
* [Avalonia](https://github.com/AvaloniaUI/Avalonia) -多平台.NET UI框架（以前称为Perspex）.
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) -基于Avalonia的文本编辑器组件，由 [AvalonEdit](https://github.com/icsharpcode/AvalonEdit)
* [ShellProgressBar](https://github.com/Mpdreamz/shellprogressbar) -在控制台程序中创建进度栏的库
* [Qml.Net](https://github.com/pauldotknopf/Qml.Net) - A cross-platform Qml/.NET integration for Mono/.NET/.NET Core.
* [WinApi](https://github.com/prasannavl/WinApi) -简单，直接，超薄的CLR库，用于具有自动化，窗口，DirectX，OpenGL和Skia帮助器的高性能Win32 Native Interop.

### IDE
* [Mono](https://github.com/mono/monodevelop) -MonoDevelop使开发人员能够在Linux，Windows和Mac OS X上快速编写桌面和Web应用程序.这也使开发人员可以轻松地将使用Visual Studio创建的.NET应用程序移植到Linux和Mac OS X，并为所有平台维护一个代码库.
* [rider](https://www.jetbrains.com/rider/) - Cross-platform C# IDE based on the IntelliJ platform and ReSharper.
* [Omnisharp](http://www.omnisharp.net/) -一系列开源项目，每个都有一个目标：在您选择的编辑器中提供出色的.NET体验.
* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) - SharpDevelop is a free Integrated Development Environment (IDE) for C#, VB.NET, Boo, IronPython, IronRuby and F# projects on Microsoft's .NET platform. It is written (almost) entirely in C#, and comes with features you would expect in an IDE plus a few more.
* [Visual Studio Code](https://github.com/Microsoft/vscode)  -新型工具，结合了代码编辑器的简单性和开发人员对其核心edit-build-debug周期的需求.  代码提供全面的编辑和调试支持，可扩展性模型以及与现有工具的轻量级集成.
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) -为个人开发人员，开源项目，学术研究，教育和小型专业团队提供的免费编辑器.

### Internationalization
* [Localization](https://github.com/aspnet/Localization) -ASP.NET Core应用程序的本地化抽象和实现.
* [NetCoreStack.Localization](https://github.com/NetCoreStack/Localization) -具有实体框架和内存缓存的.NET Core的数据库资源本地化
* [Westwind.Globalization](https://github.com/RickStrahl/Westwind.Globalization) -数据库驱动的.NET应用程序资源本地化.

### IOC
* [AutoDI](https://github.com/Keboo/AutoDI) -使用IL编织的超快速编译时依赖项注入.
* [Autofac](https://github.com/autofac/Autofac) -上瘾的.NET IoC容器.
* [Castle.Windsor](https://github.com/castleproject/Windsor) 温莎城堡是可用于.NET的同类最佳，成熟的Inversion of Control容器.
* [DryIoc](https://github.com/dadhi/DryIoc) -用于.NET的快速，小型，功能齐全的IoC容器.
* [Grace](https://github.com/ipjohnson/Grace) -Grace是一个功能丰富的依赖注入容器，在设计时考虑了易用性和性能.
* [Inyector](https://github.com/davidrevoledo/Inyector) -AspNetCore的依赖注入自动化 
* [Lamar](https://github.com/jasperfx/lamar)  -.NET的依赖注入/控制反转工具.  （以前是StructureMap）
* [LightInject](https://github.com/seesharper/LightInject) -超轻量IoC容器 [http://www.lightinject.net](http://www.lightinject.net).
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) -简单，灵活和快速的依赖注入库，可促进最佳实践，以引导开发人员迈向成功之路.
* [Stashbox](https://github.com/z4kn4fein/stashbox) -用于基于.NET的解决方案的轻巧，可移植的依赖项注入框架.

### Logging
* [common-logging](https://github.com/net-commons/common-logging) -.NET的便携式日志记录抽象 [http://net-commons.github.io/common-logging](http://net-commons.github.io/common-logging).
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) -使用UDP和Redis传输的.NET Core应用程序的Logstash日志记录扩展.
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) -出色的.NET客户端
* [Foundatio](https://github.com/exceptionless/Foundatio#logging) -流畅的日志记录api，可用于记录整个应用程序中的消息.
* [LibLog](https://github.com/damianh/LibLog) -您可以将单个文件复制/粘贴或通过nuget安装到库/框架/应用程序中，以提供日志记录抽象.
* [log4net](https://github.com/apache/logging-log4net) -log4net是优秀的Apache log4j™框架到Microsoft®.NET运行时的移植.
* [NLog](https://github.com/NLog/NLog) -高级.NET，Silverlight和Xamarin日志记录.
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) -ASP.NET Core日志中用于生成的日志附加程序，用于将所有日志发送到Application Insights.
* [serilog](https://github.com/serilog/serilog) -具有完全结构化事件的简单.NET日志记录.
  * [serilog-aspnetcore](https://github.com/serilog/serilog-aspnetcore) -ASP.NET Core 2+的Serilog集成.
  * [Serilog.Exceptions](https://github.com/RehanSaeed/Serilog.Exceptions) -Serilog.Exceptions是一个附加组件 [Serilog](https://serilog.net/) 记录在Exception.ToString（）中未输出的异常详细信息和自定义属性.
  * [Serilog.Settings.Configuration](https://github.com/serilog/serilog-settings-configuration) -从Microsoft.Extensions.Configuration中读取的Serilog配置提供程序.
* [SEQ](https://getseq.net) -Seq通过HTTP收集数据，而您的应用程序使用适用于您平台的最佳结构化日志记录API.

### Machine Learning and Data Science
* [Accord](https://github.com/accord-net/framework) -.NET的机器学习，计算机视觉，统计和一般科学计算.
* [ML.NET](https://github.com/dotnet/machinelearning) -跨平台的开源机器学习框架，使.NET开发人员可以访问机器学习 [http://dot.net/ml](http://dot.net/ml).
* [Spreads](https://github.com/Spreads/Spreads/) -用于数据流实时和探索性分析的系列和面板.
* [TensorFlowSharp](https://github.com/migueldeicaza/TensorFlowSharp) -用于.NET语言的TensorFlow API.
* [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) -在量子力学思想的帮助下，从单个示例生成itmap和tilemap.
* [SiaNet](https://github.com/SciSharp/SiaNet) - A C# deep learning library, human friendly, CUDA/OpenCL supported, well structured, easy to extend 

### Mail
* [FluentEmail](https://github.com/lukencode/FluentEmail) -适用于.NET和.NET Core的多合一电子邮件发件人
* [MailBody](https://github.com/doxakis/MailBody) -使用流畅的界面（.NET）创建交易电子邮件.
* [MailKit](https://github.com/jstedfast/MailKit) -用于IMAP，POP3和SMTP的跨平台.NET库.
* [MailMergeLib](https://github.com/axuno/MailMergeLib) -SMTP邮件客户端库，为文本，嵌入式图像和附件提供舒适的邮件合并功能，以及良好的吞吐量和发送邮件的容错能力.
* [MimeKit](https://github.com/jstedfast/MimeKit) -跨平台的.NET MIME创建和解析器库，支持S / MIME，PGP，DKIM，TNEF和Unix mbox线轴.
* [netDumbster](https://github.com/cmendible/netDumbster)  -用于测试的.Net Fake SMTP服务器.  受欢迎的Dumbster的克隆.
* [Papercut](https://github.com/ChangemakerStudios/Papercut) -简单的桌面SMTP服务器
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [SendGrid Client](https://github.com/0xdeafcafe/sendgrid-dotnet) - C# library for the SendGrid v3 mail endpoint.
* [SmtpServer](https://github.com/cosullivan/SmtpServer) -创建自己的SMTP服务器的库.
* [StrongGrid](https://github.com/Jericho/StrongGrid)  -SendGrid v3 API的客户端.  不仅允许您发送电子邮件，还允许您批量导入联系人，管理列表和细分，为列表创建自定义字段等.还包括一个用于SendGrid Webhooks的解析器.

### Mathematics
* [UnitConversion](https://github.com/Stratajet/UnitConversion) -.NET Core和.NET Framework的可扩展单元转换库.
* [AutoDiff](https://github.com/alexshtf/autodiff) -提供快速，准确和自动的数学函数微分（计算导数/梯度）的库.

### Misc
* [AdvanceDLSupport](https://github.com/Firwood-Software/AdvanceDLSupport)  -库，用于即兴P /调用本机代码.  与本机对象进行交互，就好像它们是一流的对象一样.
* [AngleSharp](https://github.com/AngleSharp/AngleSharp)  -最终尖括号解析器库.  它解析HTML5，MathML，SVG和CSS，以根据官方W3C规范构造DOM.  相当于python的beautifulsoup4.
* [AgileMapper](https://github.com/agileobjects/AgileMapper) -AgileMapper是一个零配置，高度可配置的对象-对象映射器，具有可见的执行计划.
* [AspNetCore Extension Library](https://github.com/sgjsakura/AspNetCore) -ASP.NET Core扩展库.
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) -.NET中基于约定的对象-对象映射器.
* [Baget](https://github.com/loic-sharma/BaGet) - A lightweight NuGet server.
* [Bleak](https://github.com/Akaion/Bleak) -Windows本机DLL注入库.
* [Bullseye](https://github.com/adamralph/bullseye/) -用于描述和运行目标及其依赖关系的.NET程序包.
* [Castle.Core](https://github.com/castleproject/Core) -Castle Core，包括Castle DynamicProxy，日志记录服务和DictionaryAdapter [http://www.castleproject.org](http://www.castleproject.org).
* [Chessie](https://github.com/fsprojects/Chessie) -面向铁路的.NET编程 [http://fsprojects.github.io/Chessie](http://fsprojects.github.io/Chessie).
* [CliWrap](https://github.com/Tyrrrz/CliWrap) -命令行界面包装器.
* [commanddotnet](https://github.com/bilal-fazlani/commanddotnet) -在类中为命令行应用程序界面建模.
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - The implementation of CommonMark specification in C# for converting Markdown documents to HTML.
* [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt) -Fluent库，用于为.NET控制台应用程序创建表.
* [CoordinateSharp](https://github.com/Tronald/CoordinateSharp) -一个可以快速格式化和转换地理坐标以及提供基于位置的日月信息（日落，日出，月球照明等）的库. 
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) -Microsoft ASP.NET服务器端对jQuery DataTables的支持和帮助.
* [DinkToPdf](https://github.com/rdvojmoc/DinkToPdf) - C# .NET Core wrapper for wkhtmltopdf library that uses Webkit engine to convert HTML pages to PDF.
* [dotnet-env](https://github.com/tonerdo/dotnet-env) -一个.NET库，用于从.env文件加载环境变量.
* [DotNet.Glob](https://github.com/dazinator/DotNet.Glob)  -用于.NET / .NETStandard应用程序的快速glob库.  优于正则表达式.
* [Dotnet outdated](https://github.com/jerriep/dotnet-outdated) -.NET Core全局工具，用于在项目中显示过时的NuGet包.
* [Dotnet Script](https://github.com/filipw/dotnet-script) - Run C# scripts from the .NET CLI.
* [Dotnet Serve](https://github.com/natemcmaster/dotnet-serve) -用于.NET Core CLI的简单命令行HTTP服务器.
* [Eighty](https://github.com/benjamin-hodgson/Eighty) -一个简单的HTML生成库
* [Enums.NET](https://github.com/TylerBrinkley/Enums.NET) -Enums.NET是高性能的类型安全的.NET枚举实用程序库
* [FastExpressionCompiler](https://github.com/dadhi/FastExpressionCompiler) -快速ExpressionTree编译器进行委派.
* [FluentDocker](https://github.com/mariotoffia/FluentDocker) -适用于docker，docker-compose和docker-machine的命令，服务和Fluent API，适用于win / mac / linux和本机docker.
* [FluentFTP](https://github.com/robinrodricks/FluentFTP/) -FTP和FTPS客户端，具有大量的FTP命令，SSL / TLS连接，哈希/校验和等等.
* [Fody](https://github.com/Fody/Fody) -编织.net程序集的可扩展工具
* [HdrHistogram.NET](https://github.com/HdrHistogram/HdrHistogram.NET) -高动态范围（HDR）直方图.
* [httpclient-interception](https://github.com/justeat/httpclient-interception) -.NET标准库，用于拦截服务器端HTTP依赖关系.
* [Humanizer](https://github.com/Humanizr/Humanizer) -Humanizer满足您.NET对操纵和显示字符串，枚举，日期，时间，时间跨度，数字和数量的所有需求.
* [Humidifier](https://github.com/jakejscott/Humidifier) - Write and maintain AWS Cloudformation templates using C#.
* [JqueryDataTablesServerSide](https://github.com/fingers10/JqueryDataTablesServerSide) -ASP.NET Core服务器端处理库，用于在数据库级别具有Excel导出和TagHelper支持的多列过滤，排序和分页的Jquery数据表.
* [LibSass Host](https://github.com/Taritsyn/LibSassHost) -.NET包装 [libSass](http://sass-lang.com/libsass) 支持虚拟文件系统的库.
* [markdig](https://github.com/lunet-io/markdig) -用于.NET的快速，强大，兼容CommonMark的可扩展Markdown处理器.
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) -将字符串表达式（公式，方法调用，条件）解析为LINQ表达式树，可以将其编译为lambda并求值.
* [NuGet Trends](https://github.com/NuGetTrends/nuget-trends) -具有NuGet软件包下载计数统计信息的网站.
* [Otp.NET](https://github.com/kspearrin/Otp.NET) - An implementation TOTP RFC 6238 and HOTP RFC 4226 in C#.
* [pose](https://github.com/tonerdo/pose) -用委托替换任何.NET方法（包括静态和非虚拟）
* [PuppeteerSharp](https://github.com/kblok/puppeteer-sharp) -Puppeteer Sharp是官方Node.JS Puppeteer API的.NET端口.
* [readline](https://github.com/tsolarin/readline) - Pure C# GNU-Readline like library for .NET/.NET Core.
* [ReflectionMagic](https://github.com/ReflectionMagic/ReflectionMagic) - Framework to drastically simplify your private reflection code using C# dynamic
* [Relinq](https://github.com/re-motion/Relinq) -使用re-linq，现在比以往任何时候都更容易创建功能齐全的LINQ提供程序.
* [ReverseMarkdown](https://github.com/mysticmind/reversemarkdown-net) -HTML至Markdown转换器库.
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) -PdfReport.Core是代码优先报告引擎，它建立在iTextSharp.LGPLv2.Core和EPPlus.Core库的顶部.
* [Scientist](https://github.com/github/Scientist.net)  -.NET库，用于仔细重构关键路径.  它是GitHub的Ruby Scientist库的端口.
* [Scrutor](https://github.com/khellang/Scrutor) -Microsoft.Extensions.DependencyInjection的程序集扫描扩展.
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) -string.Format的可扩展替代.
*股票
  * [Trady](https://github.com/lppkarl/Trady) -方便的库，用于计算技术指标，它的目标是成为一个自动交易系统，提供股票数据输入，指标计算，战略制定和自动交易.
* [System.Linq.Dynamic.Core](https://github.com/StefH/System.Linq.Dynamic.Core) -System Linq Dynamic功能的.NET Standard（.NET Core）版本.
* [UnitsNet](https://github.com/angularsen/UnitsNet) -Units.NET为您提供所有常用的度量单位以及它们之间的转换.
*验证
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation) -适用于.NET的小型验证库，该库使用流利的接口和lambda表达式构建验证规则.
  * [Guard](https://github.com/safakgur/guard) -高性能，可扩展的参数验证库.
  * [Valit](https://github.com/valit-stack/Valit)  -对.NET Core的简单验证.  您的代码周围不再有if语句.  改写漂亮干净的流利的验证器！
* [warden-stack](https://github.com/warden-stack)  -针对您的应用程序，资源和基础架构的“运行状况检查”.  保持您的守望者在手表上.
* [WebEssentials.AspNetCore.ServiceWorker](https://github.com/madskristensen/WebEssentials.AspNetCore.ServiceWorker) -ASP.NET Core渐进式Web应用程序.
* [Xabe.FFmpeg](https://github.com/tomaszzmuda/Xabe.FFmpeg) - .NET Standard wrapper for FFmpeg. It allows to process media without know how FFmpeg works, and can be used to pass customized arguments to FFmpeg from C# application.
* [YoutubeExplode](https://github.com/Tyrrrz/YoutubeExplode) -终极库，用于提取元数据并下载Youtube视频和播放列表.

### Networking
* [AspNetCore.Proxy](https://github.com/twitchax/AspNetCore.Proxy) -ASP.NET Core代理变得简单.
* [CurlThin](https://github.com/stil/CurlThin) - Lightweight cURL binding library for C# with support for multiple simultaneous transfers through curl_multi interface.
* [NETStandard.HttpListener](https://github.com/StefH/NETStandard.HttpListener) -用于.NET Core（NETStandard）的HttpListener.
* [Networker](https://github.com/MarkioE/Networker) -用于.NET的易于使用的TCP和UDP网络库，旨在灵活，可扩展和快速.

### Office
* [EPPlus](https://github.com/JanKallman/EPPlus) -使用.NET创建高级Excel电子表格.
* [npoi](https://github.com/tonyqus/npoi)  -.NET库，无需安装Microsoft Office即可读取/写入Office格式.  没有COM +，没有互操作.
* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK) -Open XML SDK提供了用于处理Office Word，Excel和PowerPoint文档的工具.

### Operating System
* [CosmosOS](https://github.com/CosmosOS/Cosmos) - Cosmos is an operating system "construction kit". Build your own OS using managed languages such as C#, VB.NET, and more!

### ORM
* [Chloe](https://github.com/shuxinqin/Chloe) -用于.NET的轻量级高性能对象/关系映射（ORM）库.
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) -熟悉EF以前版本的开发人员经验，包括LINQ，POCO和Code First支持.
  * [EFCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions) -用于插入更新删除读取（CRUD）操作的EntityFrameworkCore批量批处理扩展
  * [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus)  -实体框架实用程序|  批量运营|  批量删除  批量更新|  查询缓存|  查询过滤器|  查询未来|  查询包含|  审计.
  * [EntityFramework.Triggers](https://github.com/NickStrupat/EntityFramework.Triggers) -触发EF事件.
  * [EntityFramework.Rx](https://github.com/NickStrupat/EntityFramework.Rx) -EF操作的反应性“热”可观察物.
  * [Npgsql.EntityFrameworkCore.PostgreSQL](https://github.com/npgsql/Npgsql.EntityFrameworkCore.PostgreSQL) -PostgreSQL的实体框架核心提供程序.
  * [EntityFramework.PrimaryKey](https://github.com/NickStrupat/EntityFramework.PrimaryKey) -轻松获取任何实体的主键（包括组合键）.
  * [EntityFramework.TypedOriginalValues](https://github.com/NickStrupat/EntityFramework.TypedOriginalValues) -获取实体原始值的代理对象（对Property（“ ...”）.OriginalValue进行类型化访问）.
  * [EntityFramework.VersionedProperties](https://github.com/NickStrupat/EntityFramework.VersionedProperties) -自动保留对指定属性所做更改的审核历史记录的类.
  * [LINQKit](https://github.com/scottksmith95/LINQKit) -LINQ对SQL和Entity Framework高级用户的一组免费扩展.
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) -在mysql-net / MySqlConnector之上构建的MySql实体框架核心提供程序.
  * [spectre.query](https://github.com/spectresystems/spectre.query) -用于Entity Framework Core的简单查询语言.
* [Dapper](https://github.com/StackExchange/Dapper) -用于.NET的简单对象映射器.
  * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) -提供一个简单的API，以便在使用Dapper时将POCO属性流畅地映射到数据库列.
  * [Dommel](https://github.com/henkmollema/Dommel) -Dapper的简单CRUD操作.
  * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) -Dapper的CRUD.
* [FreeSql](https://github.com/2881099/FreeSql) -在dotnet中方便的ORM，支持Mysql，Postgresql，SqlServer，Oracle和Sqlite.
* [Limebean](https://nick-lucas.github.io/LimeBean/)  -Hybrid-ORM，设计简单易用，不会完全隐藏SQL，同时具有您期望从ORM获得的所有好处.  受RedBeanPHP启发.
* [LINQ to DB (linq2db)](https://linq2db.github.io/) -最快的LINQ数据库访问库，在POCO对象和数据库之间提供了一个简单，轻巧，快速且类型安全的层，可支持10多个具有完整SQL支持的数据库引擎.
* [nhibernate-core](https://github.com/nhibernate/nhibernate-core) -NHibernate对象关系映射器.
* [NEventStore](https://github.com/NEventStore/NEventStore)  -使用事件源作为存储机制时，用于抽象化不同存储实现的持久性库.  该库的开发重点是DDD / CQRS应用程序.
* [NPoco](https://github.com/schotime/NPoco)  -将查询结果映射到POCO对象上的简单microORM.  基于PetaPoco的Schotime分支的项目.
* [NReco.Data](https://github.com/nreco/data) -用于SQL命令生成，CRUD操作和简单POCO映射的轻量级独立于提供程序的DAL.
* [PetaPoco](https://github.com/CollaboratingPlatypus/PetaPoco) -对于您的POCO来说，这是ORM的小事.
* [querybuilder](https://github.com/sqlkata/querybuilder) - SqlKata Query Builder is a powerful Sql Query Builder written in C#.
* [RepoDb](https://github.com/mikependon/RepoDb) -用于.NET的动态，轻量级，高效且非常快速的混合ORM库.
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) -轻便，简单和快速的基于约定的POCO ORM.
* [SqlFu](https://github.com/sapiens/SqlFu) -快速，通用的Micro-ORM.
* [SmartSql](https://github.com/Ahoo-Wang/SmartSql) -SmartSql = MyBatis +缓存（内存| Redis）+ ZooKeeper +读/写拆分+动态存储库....
* [SQLStreamStore](https://github.com/SQLStreamStore/SQLStreamStore) -针对.NET的基于SQL的实现的流存储库.

### Profiling
* [Glimpse](https://github.com/Glimpse/Glimpse.Prototype)  -用于.NET的轻量级，开源，实时诊断和洞察探查器.  `不稳定版本`
* [MiniProfiler](https://github.com/MiniProfiler/dotnet) -用于ASP.NET网站的简单但有效的微型分析器.

### Query Builders
* [SqlKata](https://github.com/sqlkata/querybuilder) -优雅的Sql Query Builder，支持复杂查询，联接，子查询，嵌套条件，供应商引擎目标等

### Queue and Messaging
* [emitter](https://emitter.io/)  -连接所有设备的免费开源实时消息服务.  此发布-订阅消息传递API是为提高速度和安全性而构建的.
* [EventStore](https://github.com/EventStore/EventStore) -具有JavaScript中复杂事件处理功能的开源功能数据库.
* [Foundatio](https://github.com/exceptionless/Foundatio#queues) -具有内存，redis和azure实现的通用接口.
* [MediatR](https://github.com/jbogard/MediatR) -.NET中简单，明确的中介程序实现.
 * [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) -Microsoft.Extensions.DependencyInjection的MediatR扩展.
* [Mediator.Net](https://github.com/mayuanyang/Mediator.Net) -.Net的简单中介程序，用于通过支持的管道发送命令，发布事件和请求响应.
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) -用于.NET的简单过程介体.
* [MQTTnet](https://github.com/chkr1011/MQTTnet) -MQTTnet是用于基于MQTT的通信的高性能.NET库.
* [netmq](https://github.com/zeromq/netmq) - 100% native C# implementation of ZeroMQ for .NET.
* [OpenCQRS](https://github.com/OpenCQRS/OpenCQRS)  -用于DDD，CQRS和具有Azure Service Bus集成的事件源的.NET Core库.  Command和Event存储支持的数据库提供程序包括：DocumentDB，MongoDB，SQL Server，MySQL，PostgreSQL和SQLite.
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) -RabbitMQ .NET客户端 [https://www.rabbitmq.com](https://www.rabbitmq.com).
* [RawRabbit](https://github.com/pardahlman/RawRabbit) -用于通过RabbitMq进行通信的现代.NET框架.
* [Rebus](https://github.com/rebus-org/Rebus) -.NET的简单精益服务总线实现.
* [Restbus](http://restbus.org) -RabbitMq的消息传递库.
* [Tossit](https://github.com/turgayozgur/tossit)  -简单，易于使用的库，用于分布式作业/工人逻辑.  由内置RabbitMQ实现处理的分布式消息.

### Reporting
* [FastReport](https://github.com/FastReports/FastReport)  -.NET Core 2.x / .Net Framework 4.x的开源报告生成器.  FastReport可以在MVC，Web API应用程序中使用.

### Scheduler and Job
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) -轻巧耐用的库，可按计划运行任务（作业）.
* [Coravel](https://github.com/jamesmh/coravel) -.Net Core与Laravel会面：调度，排队等.
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface.
* [Gofer.NET](https://github.com/brthor/Gofer.NET) - Easy C# API for Distributed Background Tasks/Jobs for .NET Core. Inspired by celery for python.
* [HangfireIO](https://github.com/HangfireIO/Hangfire) -在ASP.NET应用程序内执行即发即忘，延迟和重复任务的简便方法 [http://hangfire.io](http://hangfire.io).
* [LiquidState](https://github.com/prasannavl/LiquidState) -用于.NET的高效异步和同步状态机.
* [NCrontab](https://github.com/atifaziz/NCrontab) -适用于.NET的Crontab.
* [quartznet](https://github.com/quartznet/quartznet/) -Quartz Enterprise Scheduler .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net).
* [stateless](https://github.com/dotnet-state-machine/stateless) - Simple library for creating state machines in C# code.

### SDKs
* [AWS SDK](https://github.com/aws/aws-sdk-net)  -Amazon Web Services（AWS）.NET Core SDK组件.  每个AWS服务都有其自己的NuGet包.
* [azure-event-hubs-dotnet](https://github.com/azure/azure-event-hubs-dotnet) -用于Azure事件中心的.NET标准客户端库.
*区块链客户
  * [Bittrex.Net](https://github.com/JKorf/Bittrex.Net) - C# .Net wrapper for the Bittrex web API including all features easily accessible and usable.
  * [Binance.Net](https://github.com/JKorf/Binance.Net) -用于Binance Web API的.Net API包装器.
* [CakeMail.RestClient](https://github.com/Jericho/CakeMail.RestClient)  -CakeMail API的客户端.  允许您发送交易电子邮件，批量电子邮件，管理列表和联系人等.
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) -领事的.NET API.
* [csharp-nats](https://github.com/nats-io/csharp-nats) - C# .NET client for the NATS messaging system.
* [DarkSkyCore](https://github.com/amweiss/dark-sky-core) -.NET的标准包装 [Dark Sky API](https://darksky.net/dev/docs).
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - .NET (C#) Client Library for Docker API.
* [firebase-admin-dotnet](https://github.com/firebase/firebase-admin-dotnet) -Firebase Admin .NET SDK
* [google-cloud-dotnet](https://github.com/GoogleCloudPlatform/google-cloud-dotnet) -适用于.NET的Google Cloud Client库.
* [Manatee.Trello](https://github.com/gregsdennis/Manatee.Trello) - A fully object-oriented .Net wrapper for Trello's RESTful API written in C#.
* [Microphone](https://github.com/rogeralsing/Microphone) -轻巧的框架，可在Consul或ETCD集群的顶部使用Web Api或NancyFx运行自托管REST服务.
* [octokit.net](https://github.com/octokit/octokit.net) -用于.NET的GitHub API客户端库.
* [PreStorm](https://github.com/jshirota/PreStorm) -ArcGIS Server的并行REST客户端.
* [SendGrid-csharp](https://github.com/sendgrid/sendgrid-csharp) - C# client library for using the full SendGrid API.
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) - .NET Standard compatible C# client to interface with Etsy's excellent [statsd](https://github.com/etsy/statsd) 服务器.
* [tweetinvi](https://github.com/linvi/tweetinvi) - Intuitive .NET C# library to access the Twitter REST and STREAM API.

### Security
* [aspnetcore-security-headers](https://github.com/juunas11/aspnetcore-security-headers) -用于将安全标头添加到ASP.NET Core应用程序的中间件.
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) -清除HTML以避免XSS攻击.
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) -用于处理JOSE对象（JWT，JWA，JWS和相关对象）的库.
* [Jwt.Net](https://github.com/jwt-dotnet/jwt) -Jwt.Net，.NET的JWT（JSON Web令牌）实现.
* [JWT Simple Server](https://github.com/Xabaril/JWTSimpleServer) -用于ASP.NET Core的轻量级动态jwt服务器.
* [NWebsec](https://github.com/NWebsec/NWebsec) -ASP.NET的安全性库 [http://www.nwebsec.com](http://www.nwebsec.com).
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) -用于ASP.NET Core的reCAPTCHA 2.0.
* [roslyn-security-guard](https://github.com/dotnet-security-guard/roslyn-security-guard) -Roslyn分析仪，旨在帮助对.NET应用程序进行安全审核.
* [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core) -用于注入Owasp的.NET Core中间件建议使用HTTP标头，以提高安全性.
* [Security](https://github.com/aspnet/Security) -用于Web应用程序的安全性和授权的中间件.
* [SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders) -小型包装，允许向ASP.NET Core网站添加安全标头.

### Searching
* [Algolia.Search](https://github.com/algolia/algoliasearch-client-csharp) -官方Algolia .NET客户端的存储库.
* [AutoComplete](https://github.com/omerfarukz/autocomplete) -持久，简单，强大和可移植的自动完成库.
* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net) -两个正式的Elasticsearch .NET客户端NEST和Elasticsearch.NET的存储库.
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) -Elasticsearch .NET API.
* [SearchExtensions](https://github.com/ninjanye/SearchExtensions) -IQueryable接口的高级搜索功能，例如实体框架查询.
* [SimMetrics.Net](https://github.com/StefH/SimMetrics.Net) -相似度指标库，例如，从编辑距离（Levenshtein，Gotoh，Jaro等）到其他指标（例如Soundex，Chapman）
* [SolrExpress](https://github.com/solr-express/solr-express) -用于Solr的简单轻量级查询.NET库，采用可控，可构建且快速失败的方式.

### Serialization
* [BinarySerializer](https://github.com/jefffhaynes/BinarySerializer) -自定义数据包和协议格式的序列化，支持位旋转.
* [bond](https://github.com/Microsoft/bond)  -用于处理模式化数据的跨平台框架.  它支持跨语言反序列化和强大的通用机制，可有效地处理数据.  Bond在Microsoft广泛用于大规模服务中.
* [Channels](https://github.com/davidfowl/Channels) -基于推送的.NET流.
* [CsvHelper](https://github.com/JoshClose/CsvHelper) -帮助读取和写入CSV文件的库.
* [Edi.Net](https://github.com/indice-co/EDI.Net)  -EDI序列化器/反序列化器.  支持EDIFact，X12和TRADACOMS格式.
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer) -用于.NET的扩展Xml序列化器.
* [Jil](https://github.com/kevin-montrose/Jil) -建立在Sigil上的快速.NET JSON（De）Serializer.
* MessagePack 
  * [msgpack-cli](https://github.com/msgpack/msgpack-cli) -公共语言基础结构的MessagePack实现/ [msgpack.org](http://msgpack.org).
  * [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp) - Extremely Fast MessagePack Serializer for C#(.NET, .NET Core, Unity, Xamarin).
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) -面向.NET的流行的高性能JSON框架.
* [protobuf-net](https://github.com/mgravell/protobuf-net/) -惯用.NET的协议缓冲区库.
* [Schema.NET](https://github.com/RehanSaeed/Schema.NET) - Schema.org objects turned into strongly typed C# POCO classes for use in .NET. All classes can be serialized into JSON/JSON-LD and XML, typically used to represent structured data in the head section of html page.
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) -JSON，JSV和CSV文本序列化器.
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) -易于使用，易于扩展的高性能库，用于通过.NET进行CSV解析.
* [Wire](https://github.com/rogeralsing/Wire) -POCO对象的二进制序列化器.
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) -.NET
* [ZeroFormatter](https://github.com/neuecc/ZeroFormatter) -.NET的快速二进制（反）序列化器.
* [Utf8Json](https://github.com/neuecc/Utf8Json) - Definitely Fastest and Zero Allocation JSON Serializer for C#(NET, .NET Core, Unity, Xamarin).
* [YAXLib](https://github.com/sinairv/YAXLib)  -用于.NET Framework和.NET Core的XML序列化库.  极其灵活和强大.

### Template Engine
* [dotliquid](https://github.com/dotliquid/dotliquid) -TobiasLütke的Liquid模板语言的.NET端口.
* [fluid](https://github.com/sebastienros/fluid) -尽可能接近Liquid模板语言的开源.NET模板引擎.
* [Portable.Xaml](https://github.com/cwensley/Portable.Xaml) -用于读取/写入xaml文件的可移植.NET库.
* [Razor](https://github.com/aspnet/Razor) -用于MVC Web应用程序的查看页面中的CSHTML文件的解析器和代码生成器.
* [RazorLight](https://github.com/toddams/RazorLight) -基于Microsoft .NET Core Razor解析引擎的模板引擎.
* [Scriban](https://github.com/lunet-io/scriban) -用于.NET的快速，强大，安全和轻量级的文本模板语言和引擎.

### Testing
* [Bogus](https://github.com/bchavez/Bogus) - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
* [CoreBDD](https://github.com/stevenknox/CoreBDD) -xUnit.net的BDD框架
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) -用于.NET的简单模拟库.
* [FluentAssertions](https://github.com/dennisdoomen/FluentAssertions) -.NET扩展方法集，使您可以更自然地指定TDD或BDD样式测试的预期结果.
* [GenFu](https://github.com/MisterJames/GenFu) -可用于生成实际测试数据的库.
* [LightBDD](https://github.com/LightBDD/LightBDD) -BDD框架允许创建易于阅读和维护的测试.
* [mockhttp](https://github.com/richardszalay/mockhttp) -Microsoft的HttpClient库的测试层.
* [moq.netcore](https://github.com/Moq/moq4) -最受欢迎和最友好的.NET模拟框架.
* [MSpec](https://github.com/machine/machine.specifications) -用于编写BDD样式测试的流行测试框架.
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) -流利的测试
  ASP.NET Core MVC的框架.
* [Netling](https://github.com/hallatore/Netling) -加载测试仪客户端，轻松进行Web测试.
* [NSpec](https://github.com/nspec/NSpec) - Battle hardened testing framework for C# that's heavily inspired by Mocha and RSpec.
* [NSubstitute](https://github.com/nsubstitute/NSubstitute) -.NET模拟框架的友好替代品.
* [nunit](https://github.com/nunit/dotnet-test-nunit) -用于.NET Core的NUnit测试运行程序.
* [shouldly](https://github.com/shouldly/shouldly) -应该测试.NET-声明*应该*的方式！ [http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow)  -.NET的实用BDD解决方案.  它使用Gherkin规范语言并集成到Visual Studio.
* [Storyteller](https://github.com/storyteller/Storyteller) -.NET的可执行规范 [http://storyteller.github.io](http://storyteller.github.io).
* [Stubbery](https://markvincze.github.io/Stubbery/) -一个简单的库，用于在.NET中创建和运行Api存根.
* [Testavior](https://github.com/geeklearningio/Testavior) -Testavior是一种轻量级的解决方案，可帮助您开发ASP.NET Core行为测试.
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) -有史以来最简单的BDD框架！
* [xBehave.net](https://github.com/xbehave/xbehave.net) -xUnit.net扩展，用于使用自然语言描述您的测试. [http://xbehave.github.io](http://xbehave.github.io)
* [xUnit.net](https://github.com/xunit/xunit) -用于.NET Framework的免费，开源，以社区为中心的单元测试工具.

### Tools
* [CommandLineUtils](https://github.com/natemcmaster/CommandLineUtils) -.NET Core和.NET Framework的命令行解析和实用程序.
* [docfx](https://github.com/dotnet/docfx) -用于构建和发布.NET项目的API文档的工具 [http://dotnet.github.io/docfx](http://dotnet.github.io/docfx)
* [dotnetfiddle](https://dotnetfiddle.net) -.NET沙箱，供开发人员快速试用代码并共享代码段.
* [dotnet-tools](https://github.com/natemcmaster/dotnet-tools) -.NET Core命令行（dotnet CLI）的工具扩展的列表.
  * [LibMan CLI](https://github.com/aspnet/LibraryManager) -Web应用程序的客户端内容管理器.
* [EntryPoint](https://github.com/Nick-Lucas/EntryPoint) -适用于.Net Core和.Net Framework 4.5+的可组合CLI（命令行）参数解析器.
* [Fake JSON Server](https://github.com/ttu/dotnet-fake-json-server)  -用于原型或作为CRUD后端的虚假REST API.  无需定义类型，使用动态类型.  数据存储到单个JSON文件中.  具有身份验证，WebSocket通知，异步长时间运行的操作，针对错误/延迟的随机生成以及实验性GraphQL支持.
* [gitignore.io](https://github.com/joeblau/gitignore.io) -为您的项目创建有用的.gitignore文件 [https://www.gitignore.io](https://www.gitignore.io).
* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore) -扫描上传的package.config文件或GitHub存储库，并确定nuget软件包是否以.NET Standard为目标 [https://icanhasdot.net](https://icanhasdot.net).
* [json2csharp](http://json2csharp.com) - Generate C# classes from JSON.
* [letsencrypt-win-simple](https://github.com/Lone-Coder/letsencrypt-win-simple) -适用于Windows的简单ACME客户端.
* [Linq_Faster](https://github.com/jackmott/LinqFaster)  -类似于Linq的数组扩展功能，跨度 <T>  和列表 <T>  更快，分配更少.
 
* [mRemoteNG](https://github.com/mRemoteNG/mRemoteNG) -下一代mRemote，开源，选项卡式，多协议，远程连接管理器
* [NJsonSchema](https://github.com/RSuter/NJsonSchema) -NJsonSchema是一个.NET库，用于读取，生成和验证JSON Schema草稿v4 +架构.
* [NuKeeper](https://github.com/NuKeeperDotNet/NuKeeper) -自动更新.NET项目中的nuget软件包.
* [NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer) -使用GUI创建，更新和部署Nuget软件包.
* [NugetVisualizer](https://github.com/sepharg/NugetVisualizer) -为一组给定的git仓库或文件夹可视化所有nuget软件包及其相应版本.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) -使用GitHub的OctoLinker浏览器扩展有效地浏览`projects.json`文件.
* [posh-dotnet](https://github.com/bergmeister/posh-dotnet) -的“ PowerShell”标签完成 [dotnet CLI](https://github.com/dotnet/cli).
* [Rin](https://github.com/mayuki/Rin)  -用于ASP.NET Core的请求/响应检查器中间件.  就像瞥见一样.
* [scoop](https://github.com/lukesampson/scoop) -Windows的命令行安装程序.
* [SerilogAnalyzer](https://github.com/Suchiman/SerilogAnalyzer)  -使用Serilog日志库对基于Roslyn的代码进行分析.  检查常见错误和使用问题.
* [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) - #ziplib is a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.
* [ShareX](https://github.com/ShareX/ShareX)  -免费和开放源代码程序，可让您捕获或记录屏幕的任何区域，并只需按一下键即可共享.  它还允许将图像，文本或其他类型的文件上传到您可以选择的80多个受支持的目的地. [https://getsharex.com](https://getsharex.com)
* [SharpLab](https://github.com/ashmind/SharpLab) -.NET代码游乐场，显示中间步骤和代码编译结果. [https://sharplab.io](https://sharplab.io)
* [sourcelink](https://github.com/dotnet/sourcelink) -SourceLink是一种语言和源代码控制不可知系统，可为二进制文件提供一流的源代码调试体验.
* [X.Web.Sitemap](https://github.com/dncuug/X.Web.Sitemap) –适用于.NET和.NET Core的简单站点地图生成器
* [X.Web.RSS](https://github.com/dncuug/X.Web.RSS) –用于.NET和.NET Core的简单RSS Feed生成器
* [SmartCode](https://github.com/Ahoo-Wang/SmartCode)  – SmartCode = IDataSource-&gt; IBuildTask-&gt; IOutput =&gt;构建所有内容！！！  （包括[代码生成器]）

### Web Framework
* WebAssembly
  * [Blazor](https://github.com/SteveSanderson/Blazor) -通过WebAssembly在浏览器中运行.NET的UI框架.
    * [Awesome Blazor](https://github.com/AdrienTorris/awesome-blazor) -收集有关Blazor的真棒资源（样本，组件，文章，视频等）.
    * [Blazor Redux](https://github.com/torhovland/blazor-redux) -将Redux状态存储与Blazor连接.
  * [Ooui](https://github.com/praeclarum/Ooui) -小型跨平台UI库，将本机UI开发的简便性带到了网络中.
* [ReactJS.NET](https://github.com/reactjs/React.NET) -.NET库，用于JSX编译和React组件的服务器端渲染.
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET)  -.NET应用程序的可预测状态容器.  受启发 [https://github.com/reactjs/redux](https://github.com/reactjs/redux).

### Web Socket
* [Fleck](https://github.com/statianzo/Fleck) - Fleck is a WebSocket server implementation in C#. Fleck requires no inheritance, container, or additional references.
* [SignalR Server](https://github.com/aspnet/signalr) -用于Web应用程序的实时Web功能，包括服务器端推送.
* [SuperSocket](https://github.com/kerryjiang/SuperSocket) -重量轻，跨平台和可扩展的套接字服务器应用程序框架.
* [WampSharp](https://github.com/Code-Sharp/WampSharp) - C# implementation of [The Web Application Messaging Protocol](http://wamp-proto.org/) -协议，提供通过WebSocket进行远程过程调用和发布/订阅的消息传递模式.
* [websocket-manager](https://github.com/radu-matei/websocket-manager) -ASP .NET Core的实时库.

### Windows Service
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) -直接从.NET Core设置并作为Windows服务运行.
* [Topshelf](https://github.com/Topshelf/Topshelf) -用于使用.NET构建Windows服务的简易服务托管框架.

### Workflow
* [CoreWF](https://github.com/dmetzgar/corewf/) -Windows Workflow Foundation（WF）到.NET Core的端口.
* [workflow-core](https://github.com/danielgerlag/workflow-core) -用于.NET Standard的轻量级工作流引擎.
* [WorkflowEngine.NET](https://github.com/optimajet/WorkflowEngine.NET) -在您的应用程序中添加工作流程的组件.
* [Wexflow](https://github.com/aelassas/Wexflow) -高性能，可扩展，模块化和跨平台的工作流引擎.

## Roadmaps
* [ASP.NET Core Developer Roadmap](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap) -在2019年成为ASP.NET Core开发人员的路线图.

## Starter Kits
* [Arch](https://github.com/Arch) -由.NET Core中包含所有新内容的软件架构师创建的.NET Core库的集合.
  * [AutoHistory](https://github.com/Arch/AutoHistory) -Microsoft.EntityFrameworkCore的插件，支持自动记录数据更改历史记录.
* [AspNetCore-Angular2-Universal](https://github.com/MarkPieszak/aspnetcore-angular2-universal) -跨平台-带有SEO，Bootstrap，i18n国际化（ngx-translate），Webpack，TypeScript，带有Karma的单元测试，WebAPI REST设置，SignalR，Swagger文档等服务器端渲染！
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors.
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices) -Yeoman生成器生成一个全新的ASP.NET Core单页应用程序，该应用程序在客户端上使用Angular 2 / React / React with Redux / Knockout / Aurelia.
* [ASP.Net Core Vue Starter](https://github.com/MarkPieszak/aspnetcore-Vue-starter) -Asp.NETCore 2.0 Vue 2（ES6）SPA入门套件，包含路由，Vuex等！
* [bitwarden-core](https://github.com/bitwarden/core) -核心基础架构后端（API，数据库等） [https://bitwarden.com](https://bitwarden.com).
* [dotNetify](https://github.com/dsuryd/dotNetify) - Simple, lightweight, yet powerful way to build real-time HTML5/C# .NET web apps.
* [generator-aspnet](https://github.com/OmniSharp/generator-aspnet) -适用于ASP.NET Core的生成器.
* [Nucleus](https://github.com/alirizaadiyahsi/Nucleus) -Vue启动应用程序模板，该模板在后端使用ASP.NET Core API分层体系结构并基于JWT进行身份验证
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) -利用现有技术，用ASP.NET Core 1构建同构React应用程序的起点.
* [saaskit](https://github.com/saaskit/saaskit) -用于构建SaaS应用程序的开发人员工具包.
* [serverlessDotNetStarter](https://github.com/pharindoko/serverlessDotNetStarter) 基于无服务器框架在AWS云中开发和部署lambda函数的入门套件.

## Sample Projects
*微服务和服务网格
  * [coolstore-microservices ](https://github.com/vietnam-devs/coolstore-microservices) -具有Istio服务网格的基于Kubernetes的多语言微服务应用程序
  * [distributed-playground](https://github.com/jvandevelde/distributed-playground) -具有Vagrant，Consul，Docker和ASP.NET Core的分布式服务平台.
  * [DNC-DShop](https://github.com/devmentors)  -分布式.NET Core项目和免费课程.  （DDD，CQRS，RabbitMQ，MongoDB，Redis，监控，日志记录，CI，CD）
  * [dotnetcore-microservices-poc](https://github.com/asc-lab/dotnetcore-microservices-poc) -使用.NET Core（EF Core，MediatR，Marten，Eureka，Ocelot，RabbitMQ，Polly，ElasticSearch，Dapper）和博客文章系列在微服务架构中构建的简化保险销售系统.
  * [eShopOnContainers](https://github.com/dotnet/eShopOnContainers) -基于微服务架构和容器的参考应用程序.
  * [InMemoryCQRSReplication](https://github.com/Aaronontheweb/InMemoryCQRSReplication) -Akka.NET参考架构-CQRS +分片+内存中复制
  * [magazine-website](https://github.com/thangchung/magazine-website) -杂志网站（使用.NET Core，ASP.NET Core，EF Core），DDD，CQRS，微服务，异步编程.
  * [microservices-in-dotnetcore](https://github.com/horsdal/microservices-in-dotnetcore) -我的微服务书中的代码示例-[https://manning.com/books/microservices-in-net-core](https://manning.com/books/microservices-in-net-core)
  * [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) -实时交易平台演示，展示了在整个应用程序堆栈中应用的反应式编程原理.
*巨石
  * [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) -西风专辑查看器ASP.NET 5示例.
  * [allReady](https://github.com/HTBox/allReady) -开源解决方案着重于提高备灾运动的认识，效率和影响，因为这些运动是由当地社区的人道主义和救灾组织提供的. [http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
  * [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) -ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger.
  * [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) -使用ASP.NET Core实现服务发现模式的示例.
  * [AspNetAuthorizationWorkshop](https://github.com/blowdart/AspNetAuthorizationWorkshop) -讨论ASP.NET Core授权中各种新内容的研讨会
  * [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/) 在2016年12月的Connect大会上发表了一系列面向企业用户和消费者（骑车者）的交互应用程序： [Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps), [Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices), [Websites](https://github.com/Microsoft/BikeSharing360_Websites), [Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer), [Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer), [Cognitive Services Kiosk App](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp),
 [Azure Bot App](https://github.com/Microsoft/BikeSharing360_BotApps).
  * [cloudscribe](https://github.com/cloudscribe/cloudscribe) -ASP.NET Core多租户Web应用程序基础.
  * [CoreCodeCamp](https://github.com/shawnwildermuth/CoreCodeCamp) -一个开放源代码网站，用于运行小型本地开发活动.
  * [DotNetClub](https://github.com/scheshan/DotNetClub) -用ASP.NET Core编写的微型俱乐部.
  * [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) -具有整体部署模型的分层应用程序体系结构.
  * [Entropy](https://github.com/aspnet/Entropy) -混沌实验场，提供新功能和新想法-在此处查看单个功能的简单样本.
  * [EquinoxProject](https://github.com/EduardoPires/EquinoxProject) -具有DDD，CQRS和事件源的完整ASP.NET Core 2.0应用程序.
  * [GenVue](https://github.com/herbat73/GenVue) -一个可托管的Web应用程序，可让机密用户上传和共享基于Vue.js，Vuetifyjs和NetCore WebAPI堆栈的私有文件
  * [guidance-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) -如何使用Azure Active Directory进行身份验证在Microsoft Azure上的多租户应用程序中管理用户身份.
  * [JustA.ML](https://github.com/mustakimali/JustA.ML)  -一个Web应用程序，可让您在用ASP.NET Core 2.0编写的设备之间共享文件/ URL /文本.  开源，生活在 [https://justa.ml](https://justa.ml)
  * [MegaMine](https://github.com/Nootus/MegaMine) -开源采矿解决方案，可帮助矿工提取金，石英，花岗岩等.此解决方案使用ASP.NET Core和AngularJS构建，并以微服务的方式利用多个轻量级组件.
  * [minicompiler](https://github.com/ealsur/minicompiler) -缩小，捆绑和编译样本.
  * [MusicStore](https://github.com/aspnet/MusicStore) -使用MVC和实体框架的示例MusicStore应用程序.
  * [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) -具有.NET Core Preview 2的NLayerAppV3 N层体系结构.
  * [NorthwindTraders](https://github.com/JasonGT/NorthwindTraders) -Northwind Traders是使用ASP.NET Core和Entity Framework Core构建的示例应用程序.
  * [Orchard Core - Modular and Multi-tenant applications](https://github.com/OrchardCMS/OrchardCore.Samples) -使用Orchard Core Framework创建模块化和多租户应用程序.
  * [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript) -具有ASP.NET Core，Angular 2和TypeScript的跨平台单页应用程序 [http://wp.me/p3mRWu-11L](http://wp.me/p3mRWu-11L).
  * [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore) -每日更新的ASP.NET Core功能和设施的微型示例.
  * [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) -使用原始架构的.NET Core REST API CQRS实现，带有原始SQL和DDD.
  * [StarWars](https://github.com/JacekKosciesza/StarWars) -使用GraphQL for .NET，ASP.NET Core，实体框架Core的GraphQL&#39;Star Wars&#39;示例.
 
## Articles
* 基础知识
  * [Microsoft architectual overview of comprehensive BikeSharing360 suite of demo apps with related videos](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [Porting a .NET Framework library to .NET Core](https://www.codeproject.com/Articles/1190475/Porting-a-NET-Framework-library-to-NET-Core)
  * [The 68 things the CLR does before executing a single line of your code](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-single-line-of-your-code/)
  * .NET Core和Node.js之间的比较 [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) 和 [here](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
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
- [InfoQ .NET articles](https://www.infoq.com/dotnet) -InfoQ网站上的最佳.NET最佳文章集

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

## Cheat Sheets
* [dotnet cli Cheat Sheet](http://en.otomatikmuhendis.com/2018/07/02/cheat-sheet-for-dotnet-cli/)

## Videos
* [Channel9](https://channel9.msdn.com) -MSDN
* [Channel9](https://www.youtube.com/channel/UCsMica-v34Irf9KVTh6xx-g) -YouTube
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

在法律允许的范围内， [thangchung](http://weblogs.asp.net/thangchung) 放弃了此作品的所有版权以及相关或邻近的权利.
