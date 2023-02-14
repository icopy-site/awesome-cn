<div class="github-widget" data-repo="marmelab/awesome-rest"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome REST [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

关于 RESTful API 架构、开发、测试和性能的重要资源的协作列表. 随时为这个正在进行的列表做出贡献.




## Design

* [建筑风格和
基于网络的软件架构的设计](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm) - Roy Fielding 定义 REST 的论文
* [HTTP API design guide extracted from work on the Heroku Platform API](https://github.com/interagent/http-api-design)
* [Best Practices for Designing a Pragmatic RESTful API](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* [How to design a REST API?](https://blog.octo.com/en/design-a-rest-api/) - 解决安全性、分页、过滤、版本控制、部分答案、CORS 等问题的完整指南.
* [Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html) - 由 Martin Fowler 解释，最初由 Leonard Richardson 在 [QCon 2008](https://www.crummy.com/writing/speaking/2008-QCon/act3.html).
* [Enterprise Integration Using REST](https://martinfowler.com/articles/enterpriseREST.html) - 讨论非公共 API 的限制和灵活性，以及​​从跨多个团队进行大规模 RESTful 集成中吸取的经验教训.
* [HATEOAS](https://web.archive.org/web/20201111235328/timelessrepo.com/haters-gonna-hateoas) - 关于什么是 HATEOAS 以及为什么要使用它的清晰解释.
* [How to GET a cup of coffee](https://www.infoq.com/articles/webber-rest-workflow/)
* [REST API Tutorial](https://www.restapitutorial.com/) - RestApiTutorial.com 致力于跟踪 REST API 最佳实践并提供可用资源，以便为开发人员提供快速参考和自我教育.
* [API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist) - 有关 REST API 安全性的最佳实践

### Guidelines

* [Adidas REST API Guidelines](https://github.com/adidas/api-guidelines/blob/master/rest-api-guidelines/rest.md) - 阿迪达斯 REST API 指南定义了在阿迪达斯构建 REST API 的标准和指南.
* [Atlassian REST API design guidelines version 1](https://developer.atlassian.com/server/framework/atlassian-sdk/atlassian-rest-api-design-guidelines-version-1/) - 本文档为正在为 Atlassian 应用程序设计 REST API 的 Atlassian 开发人员提供指南.
* [Cisco REST API Guide](https://github.com/CiscoDevNet/api-design-guide) - 思科 REST API 设计指南.
* [Google Cloud API design guide](https://cloud.google.com/apis/design/) - Google 在设计 Cloud API 和其他 Google API（REST API 和 gRPC API）时遵循的准则.
* [Haufe API Style Guide](https://github.com/Haufe-Lexware/api-style-guide) - 由 Haufe-Lexware CTO 团队创建的指南.
* [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md#readme) - 作为设计原则，Microsoft REST API 指南鼓励应用程序开发人员通过 RESTful HTTP 接口访问资源.
* [Restful API Guidelines by Zalando](https://github.com/zalando/restful-api-guidelines) - 开发 Restful API：一套综合指南.

## Standards

* [JSON API](https://jsonapi.org/) - 在 JSON 中构建 API 的标准.
* [RAML](https://raml.org/) - 描述 RESTful API 的简单方式.
* [JSend](https://labs.omniti.com/labs/jsend) - 为 Web 服务器的 JSON 响应的格式制定一些规则的简单规范.
* [OData](https://www.odata.org/)  - 允许创建和使用可查询和可互操作的 RESTful API 的开放协议. 相当复杂.
* [HAL](https://tools.ietf.org/html/draft-kelly-json-hal-06) - 简单的格式，为 API 中的资源之间的超链接提供了一种一致且简单的方法.
* [JSON-LD](https://json-ld.org/) - 在 JSON (W3C) 中描述关联数据和超媒体关系的标准.
* [Hydra](https://www.hydra-cg.com/) - 超媒体驱动的 Web API (W3C) 的词汇表.
* [Schema.org](https://schema.org) - 描述通用数据模型的模式集合.
* [OpenAPI](https://openapis.org/) - 以前称为 Swagger 规范，OpenAPI 规范是世界上最流行的用于定义 Restful API 的描述格式.

## Clients

### PHP Clients

* [Guzzle](https://guzzle.readthedocs.org/en/latest/) - 用于使用 RESTful Web 服务的 HTTP 客户端和框架.
* [Buzz](https://github.com/kriswallsmith/buzz) - 另一个轻量级 HTTP 客户端.
* [unirest for PHP](https://github.com/Mashape/unirest-php) - 简化的轻量级 HTTP 客户端库.

### JavaScript Clients

* [restangular](https://github.com/mgonto/restangular) - AngularJS 服务可以正确、轻松地处理 REST API.
* [restful.js](https://github.com/marmelab/restful.js) - 用于与服务器端 RESTful 资源交互的 JS 客户端.
* [traverson](https://github.com/basti1302/traverson) - 用于 Node.js 和浏览器的超媒体 API/HATEOAS 客户端
* [raml-client-generator](https://github.com/mulesoft/raml-client-generator) - 为 js 生成静态客户端库.

### Node.js Clients

 * [restler](https://github.com/danwrong/restler) - 用于 node.js 的 REST 客户端库.
 * [unirest for Node.js](https://github.com/Mashape/unirest-nodejs) - 简化的轻量级 HTTP 客户端库.

### Ruby Clients

* [RESTClient](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
* [Spyke](https://github.com/balvig/spyke) - 以类似 ActiveRecord 的方式与 REST 服务交互.
* [excon](https://github.com/excon/excon)  - 可用、快速、简单的 Ruby HTTP 1.1. 它作为通用的 HTTP(s) 客户端工作得很好，特别适合在 API 客户端中使用.
* [httparty](https://github.com/jnunemaker/httparty) - 让 HTTP 再次变得有趣！
* [Net::HTTP](https://ruby-doc.org/3.2.0/stdlibs/net/Net/HTTP.html) - Net::HTTP 提供了丰富的库，可用于构建 HTTP 用户代理.
* [raml-ruby-client-generator](https://github.com/zlx/raml-ruby-client-generator) - 从 RAML 文件自动生成 API 客户端.

### Go Clients

* [gopencils](https://github.com/bndr/gopencils) - 小而简单的包，可以轻松使用 REST API.
* [resty](https://github.com/go-resty/resty) - 受 Ruby rest-client 启发的 Go 的简单 HTTP 和 REST 客户端.

### .NET Clients

* [RestSharp](https://github.com/restsharp/RestSharp) - .NET 的简单 REST 和 HTTP API 客户端
* [Refit](https://github.com/reactiveui/refit) - The automatic type-safe REST library for Xamarin and .NET
* [Flurl](https://flurl.dev) - 流畅、可移植、可测试的 REST/HTTP 客户端库
* [RestEase](https://github.com/canton7/RestEase)  - 易于使用的类型安全 REST API 客户端库，简单且可自定义. 深受 Refit 启发
* [Tiny.RestClient](https://github.com/jgiacomini/Tiny.RestClient) - 适用于 .NET 的最简单的 Fluent REST 客户端.
* [RestLess](https://github.com/letsar/RestLess) - .Net Standard 的自动类型安全无反射 REST API 客户端库.
* [Apizr](https://github.com/Respawnsive/Apizr) - 基于 Refit 的 web api 客户端，但具有弹性（重试、连接、缓存、身份验证、日志、优先级等）.

### Generators

* [openapi-generator](https://github.com/OpenAPITools/openapi-generator) - OpenAPI 生成器允许在给定 OpenAPI 规范（v2、v3）的情况下自动生成 API 客户端库（SDK 生成）、服务器存根、文档和配置.

## Servers

### Directly On Top Of A RMDB

* [postgrest](https://github.com/begriffs/postgrest) - 直接从现有的 PostgreSQL 数据库提供完全 RESTful API.
* [MySQL HTTP plugin](http://blog.ulf-wendel.de/2014/mysql-5-7-http-plugin-mysql/) - 适用于任何 MySQL 数据库的简单类 REST / CRUD 服务器.
* [pREST](https://github.com/prest/prest) - 来自用 Go 编写的任何现有 PostgreSQL 数据库的完全 RESTful API.

### Node.js

* [node-restify](https://github.com/restify/node-restify) - 专门用于 REST API 的框架.
* [Sails.js](https://sailsjs.org/) - 嵌入命令以自动生成 REST API 的 Node.js Web 框架.
* [mers](https://github.com/jspears/mers) - 将 Mongoose 查找器公开为 RESTful API 的快速服务.
* [Baucis](https://github.com/wprl/baucis) - 基于您的 Mongoose 实体构建可扩展的 REST API.
* [flatiron/resourceful](https://github.com/flatiron/resourceful) - JavaScript 的同构资源引擎.
* [loopback](https://loopback.io/) - 强大的 Node.js 框架，用于创建 API 并轻松连接到后端数据源.
* [Feathers](https://feathersjs.com/) - 是一个实时的微服务 Web 框架，可让您通过 RESTful 资源、套接字和灵活的插件来控制您的数据.
* [Expressa](https://github.com/thomas4019/expressa) - Express 中间件，用于使用简单的管理编辑器和权限模型从 JSON 模式创建 API.
* [rest-hapi](https://github.com/JKHeadley/rest-hapi) - 基于支持关系数据的猫鼬模型生成 RESTful API.
* [Nestjsx/crud](https://github.com/nestjsx/crud) - 使用 NestJS 和 TypeORM 为 RESTful API 生成 CRUD 控制器和服务.

### PHP

* [Microrest](https://github.com/marmelab/microrest.php) - 在任何关系数据库之上提供 REST API 的微型 Web 应用程序.
* [Drest](https://github.com/leedavis81/drest) - 用于将 Doctrine 实体公开为 REST 资源端点的库.
* [Restler](https://github.com/Luracast/Restler) - 将 PHP 方法公开为 RESTful Web API 的轻量级框架.
* [HAL](https://github.com/blongden/hal) - 超文本应用程序语言 (HAL) 构建器库.
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - 使用 Zend Framework 2 构建的 API 构建器.
* [phprest](https://github.com/phprest/phprest) - 专门用于 PHP 的 REST 微框架.
* [Hateoas](https://github.com/willdurand/Hateoas) - 支持 HATEOAS REST Web 服务实现表示的 PHP 库.
* [Fusio](https://github.com/apioo/fusio) - 开源API管理平台.

#### Symfony2

* [REST APIs with Symfony2: the Right Way](https://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/) - 使用 Symfony2 框架构建最先进的 REST API 的完整指南.
* [FOSRestBundle](https://github.com/FriendsOfSymfony/FOSRestBundle) - 为您的 REST API 捆绑处理视图、路由、错误处理等.
* [stanlemon/rest-bundle](https://github.com/stanlemon/rest-bundle) - 使用约定优于配置构建基于 Doctrine 实体的 REST API.
* [lakion/Lionframe](http://lakion.com/lionframe) - 多个社区库之间的 Glu 以简化 API 开发.
* [BazingaHateoasBundle](https://github.com/willdurand/BazingaHateoasBundle) - 整合 [Hateoas](https://github.com/willdurand/Hateoas) 库到 Symfony2 应用程序中.
* [Symfony REST Edition](https://github.com/gimler/symfony-rest-edition) - 从一个 Symfony2 应用程序开始，所有 REST 友好的包都预先配置好了.
* [NgAdminGeneratorBundle](https://github.com/marmelab/NgAdminGeneratorBundle) - 基于 stanlemon/rest-bundle 的 Boostrap ng-admin 配置.
* [DunglasApiBundle](https://github.com/dunglas/DunglasApiBundle) - 构建遵循 Hydra/JSON-LD 规范的 REST API.
* [API Platform](https://github.com/api-platform/api-platform) - 专门用于创建超媒体 REST API 的 Symfony 版本.
* [NelmioApiDocBundle](https://github.com/nelmio/NelmioApiDocBundle) - 从注释中为您的 REST API 生成文档.

### PowerShell

* [Pode](https://github.com/Badgerati/Pode) - Pode 是面向 PowerShell 开发人员的跨平台、开源、社区支持的 Web 服务器和 REST API 框架

### Python

* [Django REST framework](https://www.django-rest-framework.org/) - 强大而灵活的工具包，可以轻松构建 Web API.
* [django-tastypie](http://tastypieapi.org/) - 为 Django 应用程序创建美味的 API.
* [flask-restful](https://flask-restful.readthedocs.org/) - Flask 的扩展，增加了对快速构建 REST API 的支持.
* [flask-restless](https://flask-restless.readthedocs.org/en/latest/) - Flask 扩展，用于为使用 SQLAlchemy（或 Flask-SQLAlchemy）定义的数据库模型生成 ReSTful API.
* [hug](https://www.hug.rest/) - 轻量级和快速的 API 框架.
* [sandman](https://github.com/jeffknupp/sandman) - 用于现有数据库驱动系统的自动化 REST API.
* [restless](https://restless.readthedocs.org/en/latest/) - 基于从 TastyPie 中吸取的经验教训的框架不可知的 REST 框架.
* [Python Eve](https://python-eve.org/)  - Eve 是一个为人类设计的开源 Python REST API 框架. 它允许毫不费力地构建和部署高度可定制、功能齐全的 RESTful Web 服务.
* [Ramses](https://ramses.readthedocs.org/en/stable/) - 通过在运行时从中生成生产就绪的 API，使 RAML 文件可执行.
* [Flask-Potion](https://github.com/biosustain/potion)  - Flask-Potion 是一个强大的 Flask 扩展，用于构建 RESTful JSON API. 它还提供了多个客户端，以便更轻松地访问 API.
* [apistar](https://github.com/encode/apistar) - 专为 Python 3 设计的智能 Web API 框架. 
* [Falcon](https://github.com/falconry/falcon) - Falcon 是一个裸机 Python Web API 框架，用于构建高性能微服务、应用程序后端和更高级别的框架.
* [FastAPI](https://github.com/tiangolo/fastapi)  - FastAPI 是一种现代、快速（高性能）的 Web 框架，用于基于标准 Python 类型提示使用 Python 3.6+ 构建 API. 使用基于 OpenAPI 和 JSON 架构的 Swagger UI 和 ReDoc 的自动 API 文档.

### Ruby

* [Grape](https://www.ruby-grape.org) - 用于在 Ruby 中创建类 REST API 的自以为是的微框架.
* [Rails](https://guides.rubyonrails.org/api_app.html) - RailsGuides：将 Rails 用于仅 API 应用程序.

### Go

* [gocrud](https://github.com/manishrjain/gocrud): Go 库来简化创建、更新和删除任意深度结构化数据——使构建 REST 服务变得快速和容易.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - `net/http` 之上的薄层有助于轻松构建 RESTful API.
* [sleepy](https://github.com/dougblack/sleepy) - 用 Go 编写的 RESTful 微框架.
* [restit](https://github.com/yookoala/restit) - 帮助编写 RESTful API 集成测试的 Go 微框架.
* [go-relax](https://github.com/codehack/go-relax) - 用于构建 RESTful API 的可插入组件框架.
* [go-rest](https://github.com/ungerik/go-rest) - 用于 Go 的小而邪恶的 REST 框架.
* [go-restful](https://github.com/emicklei/go-restful) - 用于构建 restful API 的声明性高度可读框架.
* [Goat](https://github.com/bahlo/goat) - Go 中的简约 REST API 服务器.
* [Resoursea](https://github.com/resoursea/api) - 用于快速编写基于资源的服务的 REST 框架.

### Java

* [RestExpress](https://github.com/RestExpress/RestExpress) - 基于 Netty 的高性能、轻量级、无容器、可插件扩展的框架，非常适合微服务架构.
* [Vertx-Web](https://github.com/vert-x3/vertx-web) - Vert.x-Web 是一组用于使用 Vert.x 构建 Web 应用程序的构建块，Vert.x 是一个用于在 JVM 上构建反应式应用程序的工具包.
* [Dropwizard](https://github.com/dropwizard/dropwizard) - 用于开发操作友好、高性能、RESTful Web 服务的框架.

### Scala

* [Chaos](https://github.com/mesosphere/chaos) - 用于在 Scala 中编写 REST 服务的轻量级框架.


### Haskell
* [Rest for Haskell](https://github.com/silkapp/rest)  - 这个包允许你在 Haskell 中创建 REST API. 这些 API 可以在不同的 Web 框架中运行. 它们还可用于自动生成文档和客户端库.

## Testing

### Querying

* [httpie](https://github.com/jkbrzt/httpie) - 命令行 HTTP 客户端，比 `curl` 对开发者更友好.
* [resty](https://github.com/micha/resty) - 可以在管道（bash 或 zsh）中使用的小型命令行 REST 客户端.
* [jq](https://github.com/stedolan/jq) - 命令行 JSON 处理器，与 cURL 等命令行 HTTP 客户端结合使用.
* [HttpMaster](https://www.httpmaster.net)  - 用于测试 REST API 和服务的 GUI 工具. 仅限 Windows 操作系统.
* [Http-console](https://github.com/cloudhead/http-console) - HTTP 的命令行界面，让您*像本地人一样说 HTTP*
* [HTTP Prompt](https://github.com/eliangcs/http-prompt) - HTTP Prompt 是一个交互式命令行 HTTP 客户端，具有自动完成和语法突出显示功能，基于 HTTPie 和 prompt_toolkit 构建.
* [rest-assured](https://github.com/rest-assured/rest-assured) - 用于轻松测试 REST 服务的 Java DSL.
* [Insomnia](https://github.com/getinsomnia/insomnia) - 跨平台 HTTP 和 GraphQL 客户端
* [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 使用简单的基于 Web 的 HTTP 客户端发出 HTTP 请求.
* [TestMace](https://testmace.com) - 用于 API 自动化测试的跨平台简单但功能强大的 IDE.
* [Milkman](https://github.com/warmuuh/milkman) - 可扩展的跨平台请求/响应工作台，不仅适用于 http 调用.
* [Schemathesis](https://github.com/schemathesis/schemathesis) - 基于属性的测试工具，适用于使用 Open API 和 GraphQL 规范构建的 Web 应用程序.
* [Step CI](https://github.com/stepci/stepci) - 用于 API 质量保证的开源框架，它根据开放 API 规范自动测试 REST、GraphQL 和 gRPC.
* [RestQA](https://github.com/restqa/restqa) - 基于 BDD / Gherkin 的 REST API 测试框架，用于管理微服务本地测试.

### Mocking

* [RequestBin](https://requestbin.com/) - 检查和调试由您的客户端或第三方 API 发送的 webhook 请求.
* [httpbin](https://httpbin.org) - HTTP 请求和响应服务 - a/k/a Swiss Army Knife for HTTP.
* [FakeRest](https://github.com/marmelab/FakeRest) - 修补 XMLHttpRequest 以伪造 REST API 客户端.
* [json-server](https://github.com/typicode/json-server) - 使用快速原型设计从夹具文件提供 REST API.
* [Mocky.io](https://www.mocky.io/) - 创建假 HTTP 响应的免费在线服务.
* [MockServer](https://www.mock-server.com/) - 轻松模拟您通过 HTTP 或 HTTPS 集成的任何系统.
* [Request Baskets](https://github.com/darklynx/request-baskets) - 收集 HTTP 请求并通过 RESTful API 或 Web UI 检查它们的服务.
* [DuckRails](https://github.com/iridakos/duckrails) - 快速和动态地模拟 API 端点.
* [Mockoon](https://mockoon.com)  - 在本地轻松创建模拟 API. 无需远程部署，无需帐户，开源.
* [Mockintosh](https://mockintosh.io/) - 能够生成 RESTful API 并与消息队列通信以模拟异步任务的模拟服务器生成器.

### Validating

* [JSON Schema](http://json-schema.org/) - 允许您注释和验证 JSON 文档的声明性语言

### Public REST APIs To Use In Tests

* [Deck of Cards API](https://deckofcardsapi.com) - 用于模拟一副纸牌的开放 API.
* [ProgrammableWeb](https://www.programmableweb.com/apis/directory) - 世界上最大的 API 存储库.
* [Public APIS](https://github.com/public-apis/public-apis) - 探索银河系中最大的 API 目录.
* [Marvel Comics API](https://developer.marvel.com/) - 查询关于漫威超级英雄的人物、故事、事件.
* [JSON Placeholder](https://jsonplaceholder.typicode.com/) - 免费的在线 REST 服务，您可以在需要一些虚假数据时使用.
* [APIs.guru](https://APIs.guru) - Web API 的维基百科，每个 API 都有 OpenAPI/Swagger 描述.
* [The Cat API](https://theCatAPI.com) - 猫图片、事实和笑话的公共 API.

## Documentation

* [Swagger](https://swagger.io/) - REST API 的文档/查询 Web 界面.
* [API doc](https://apidocjs.com/) - RESTful Web API 的内联文档.
* [raml2html](https://github.com/raml2html/raml2html) - 从 RAML 文件生成 HTML 文档.
* [ReDoc](https://github.com/Rebilly/ReDoc/) - OpenAPI/Swagger 驱动的三面板文档.
* [Slate](https://github.com/lord/slate) - 使用 Middleman 的漂亮且响应迅速的三面板 API 文档.
* [Optic](https://github.com/opticdev/optic)  - 无需编写 OpenAPI/Swagger 即可维护准确的 API 规范. 适用于任何堆栈

## API Gateway

* [Kong](https://github.com/Kong/kong) - 由 Nginx 支持的可扩展、分布式和面向插件的 API 网关.
* [Tyk API Gateway](https://github.com/TykTechnologies/tyk) - 具有分析日志记录的轻量级 API 网关，用 Go 编写.
* [API Umbrella](https://github.com/NREL/api-umbrella) - 用于公开 Web 服务的 API 管理平台，带有 Web 界面和分析，用 Lua 编写.
* [WSO2 API Management](https://github.com/wso2/product-apim) - 具有轻量级网关和 API 生命周期管理的 API 管理工具，用 Java 编写.
* [Express Gateway](https://github.com/ExpressGateway/express-gateway) - 建立在 ExpressJS (Node.js) 之上的微服务 API 网关.
* [KrakenD](https://github.com/devopsfaith/krakend)  - 带有中间件的超高性能 API 网关. 用围棋写的.
* [AWS API Gateway](https://aws.amazon.com/api-gateway/) - 完全托管的服务，可帮助开发人员创建、发布、维护、监控和保护任何规模的 API.

## SaaS Tools

* [Nango](https://github.com/NangoHQ/nango) - 使用 REST API 的本机集成框架（开源）.
* [Runscope](https://www.runscope.com/) - 自动化 API 监控和测试.
* [Ping-API](https://ping-api.com/) - 自动化 API 监控和测试.
* [Apiary](https://apiary.io/) - 协作设计、即时 API 模拟、生成文档、集成代码示例、调试和自动化测试.
* [Amazon API Gateway](https://aws.amazon.com/api-gateway/) - Amazon API Gateway 是一项完全托管的服务，可让开发人员轻松创建、发布、维护、监控和保护任何规模的 API.
* [Apigee](https://apigee.com) - Apigee 是为企业和开发者提供 API 技术和服务的领先供应商.
* [3scale](https://www.3scale.net/) - 基于 Nginx 的 API 网关，用于将内部和外部 API 服务与 3scale 的 API 管理平台集成.
* [Assertible](https://assertible.com) - 在部署后和跨环境持续测试和监控您的 API.
* [Moesif](https://www.moesif.com) - 用于 RESTful 和 GraphQL 的调试、监控和使用跟踪的 API 分析.
* [Beeceptor](https://beeceptor.com/)  - HTTP 检查、模拟和代理服务. 提供用于创建模拟 API 端点和模拟响应的命名端点.

## Miscellaneous

* [react-admin](https://github.com/marmelab/react-admin) - 将 ReactJS 管理 GUI 添加到任何 RESTful API.
* [ng-admin](https://github.com/marmelab/ng-admin) - 将 AngularJS 管理 GUI 添加到任何 RESTful API.
* [swagger-codegen](https://github.com/swagger-api/swagger-codegen) - 根据 OpenAPI 规范（以前称为 Swagger 规范）自动生成客户端库或服务器存根.
* [Lumber](https://github.com/ForestAdmin/lumber) - 生成应用程序的管理界面.
* [Linx](https://linx.software)  - 低代码 API 平台. 构建、调试和托管 REST API 


## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](httsp://creativecommons.org/licenses/by/4.0/)

这项工作已获得许可 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
