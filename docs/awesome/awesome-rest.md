## Awesome REST [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 关于RESTful API架构，开发，测试和性能的重要资源的协作列表.  随意为这个正在进行的列表做出贡献.

* [Design](#design)
* [Standards](#standards)
* [Clients](#clients)
  * [PHP](#php-clients)
  * [Client-side JavaScript](#javascript-clients)
  * [Node.js](#nodejs-clients)
  * [Ruby](#ruby-clients)
  * [Go](#go-clients)
* [Servers](#servers)
  * [Directly On Top Of A RMDB](#directly-on-top-of-a-rmdb)
  * [Node.js](#nodejs)
  * [PHP](#php)
  * [Symfony2](#symfony2)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Go](#go)
  * [Java](#java)
  * [Haskell](#haskell)
* [Testing](#testing)
  * [Querying](#querying)
  * [Mocking](#mocking)
  * [Public REST APIs To Use In Tests](#public-rest-apis-to-use-in-tests)
* [Documentation](#documentation)
* [API Gateway](#api-gateway)
* [SaaS Tools](#saas-tools)
* [Miscellaneous](#miscellaneous)



## Design

* [建筑风格和
基于网络的软件体系结构设计]（https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm） -  Roy Fielding的论文定义REST
* [HTTP API design guide extracted from work on the Heroku Platform API](https://github.com/interagent/http-api-design)
* [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* [How to design a REST API?](http://blog.octo.com/en/design-a-rest-api/) - 完整指南，处理安全性，分页，过滤，版本控制，部分答案，CORS等.
* [Richardson Maturity Model](http://martinfowler.com/articles/richardsonMaturityModel.html) - 由Martin Fowler解释，最初由Leonard Richardson出演 [QCon 2008](https://www.crummy.com/writing/speaking/2008-QCon/act3.html).
* [Enterprise Integration Using REST](http://martinfowler.com/articles/enterpriseREST.html) - 讨论非公共API的约束和灵活性，以及​​跨多个团队进行大规模RESTful集成的经验教训.
* [HATEOAS](http://timelessrepo.com/haters-gonna-hateoas) - 清楚解释HATEOAS是什么，以及为什么要使用它.
* [How to GET a cup of coffee](http://www.infoq.com/articles/webber-rest-workflow/)
* [REST API Tutorial](http://www.restapitutorial.com/) -  RestApiTutorial.com致力于跟踪REST API最佳实践并提供资源，以便为开发工艺人员提供快速参考和自我教育.
* [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md#readme) -  Microsoft REST API指南作为一种设计原则，鼓励应用程序开发人员通过RESTful HTTP接口为他们提供可访问的资源.
* [API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist) - 有关REST API安全性的最佳实践

## Standards

* [JSON API](http://jsonapi.org/) - 用于在JSON中构建API的标准.
* [RAML](http://raml.org/) - Simple and succinct way to describe RESTful API.
* [JSend](http://labs.omniti.com/labs/jsend) - 简单的规范，规定了如何格式化来自Web服务器的JSON响应的一些规则.
* [OData](http://www.odata.org/)   - 开放协议，允许创建和使用可查询和可互操作的RESTful API.  相当复杂.
* [HAL](http://stateless.co/hal_specification.html) - 简单的格式，为您的API中的资源之间的超链接提供一致且简单的方法（请参阅： [HATEOAS](#hateoas)).
* [JSON-LD](http://json-ld.org/) - 用于描述JSON（W3C）中的关联数据和超媒体关系的标准.
* [Hydra](http://www.hydra-cg.com/) - 超媒体驱动的Web API（W3C）词汇表.
* [Schema.org](http://schema.org) - 描述常见数据模型的模式集合.
* [OpenAPI](https://openapis.org/) - 以前称为Swagger规范，OpenAPI规范是世界上最流行的用于定义Restful API的描述格式.

## Clients

### PHP Clients

* [Guzzle](http://guzzle.readthedocs.org/en/latest/) - 用于使用RESTful Web服务的HTTP客户端和框架.
* [Buzz](https://github.com/kriswallsmith/buzz) - 另一个轻量级HTTP客户端.
* [unirest for PHP](https://github.com/Mashape/unirest-php) - 简化的轻量级HTTP客户端库.

### JavaScript Clients

* [restangular](https://github.com/mgonto/restangular) -  AngularJS服务，可以正确，轻松地处理REST API.
* [restful.js](https://github.com/marmelab/restful.js) - 用于与服务器端RESTful资源交互的JS客户端.
* [traverson](https://github.com/basti1302/traverson) -  Node.js和浏览器的超媒体API / HATEOAS客户端
* [raml-client-generator](https://github.com/mulesoft/raml-client-generator) - 为js生成静态客户端库.

### Node.js Clients

 * [restler](https://github.com/danwrong/restler) -  node.js的REST客户端库.
 * [unirest for Node.js](https://github.com/Mashape/unirest-nodejs) - 简化的轻量级HTTP客户端库.

### Ruby Clients

* [RESTClient](https://github.com/rest-client/rest-client) -  Ruby的简单HTTP和REST客户端，受微框架语法的启发，用于指定操作.
* [Spyke](https://github.com/balvig/spyke) - 以类似ActiveRecord的方式与REST服务交互.
* [excon](https://github.com/excon/excon)   - 可用，快速，简单的Ruby HTTP 1.1.  它作为一般的HTTP客户端非常有用，特别适合在API客户端中使用.
* [httparty](https://github.com/jnunemaker/httparty) - 再次让HTTP变得有趣！
* [Net::HTTP](http://ruby-doc.org/stdlib/libdoc/net/http/rdoc/Net/HTTP.html) -  Net :: HTTP提供了一个丰富的库，可用于构建HTTP用户代理.
* [raml-ruby-client-generator](https://github.com/zlx/raml-ruby-client-generator) - 从RAML文件自动生成API客户端.

### Go Clients

* [gopencils](https://github.com/bndr/gopencils) - 小而简单的包，可轻松使用REST API.
* [resty](https://github.com/go-resty/resty) - 受Ruby rest-client启发的Go的简单HTTP和REST客户端.

## Servers

### Directly On Top Of A RMDB

* [postgrest](https://github.com/begriffs/postgrest) - 直接从现有的PostgreSQL数据库提供完全RESTful API.
* [MySQL HTTP plugin](http://blog.ulf-wendel.de/2014/mysql-5-7-http-plugin-mysql/) - 适用于任何MySQL数据库的简单类REST / CRUD服务器.
* [pREST](https://github.com/prest/prest) - 使用Go编写的任何现有PostgreSQL数据库中的完全RESTful API.

### Node.js

* [node-restify](https://github.com/restify/node-restify) - 框架专门用于REST API.
* [Sails.js](http://sailsjs.org/) -  Node.js Web框架嵌入命令以自动生成REST API.
* [mers](https://github.com/jspears/mers) - 快速服务将Mongoose finders暴露为RESTful API.
* [Baucis](https://github.com/wprl/baucis) - 基于Mongoose实体构建可扩展的REST API.
* [flatiron/resourceful](https://github.com/flatiron/resourceful) -  JavaScript的同构资源引擎.
* [loopback](http://loopback.io/) - 强大的Node.js框架，用于创建API并轻松连接到后端数据源.
* [Feathers](http://feathersjs.com/) - 是一个实时的微服务Web框架，可让您通过RESTful资源，套接字和灵活的插件控制您的数据.
* [Expressa](https://github.com/thomas4019/expressa) - 使用简单的管理编辑器和权限模型，通过JSON模式创建API的Express中间件.
* [rest-hapi](https://github.com/JKHeadley/rest-hapi) - 基于支持关系数据的mongoose模型生成RESTful API.

### PHP

* [Microrest](https://github.com/marmelab/microrest.php) - 在任何关系数据库之上提供REST API的Micro-web应用程序.
* [Negotiation](https://github.com/willdurand/Negotiation) - 内容协商库.
* [Drest](https://github.com/leedavis81/drest) - 用于将Doctrine实体公开为REST资源端点的库.
* [Restler](https://github.com/Luracast/Restler) - 轻量级框架，将PHP方法公开为RESTful Web API.
* [HAL](https://github.com/blongden/hal) - 超文本应用程序语言（HAL）构建器库.
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - 使用Zend Framework 2构建的API构建器.
* [phprest](https://github.com/phprest/phprest) -  PHP专用REST微框架.
* [Hateoas](https://github.com/willdurand/Hateoas) - 支持为HATEOAS REST Web服务实现表示的PHP库.
* [Fusio](https://github.com/apioo/fusio) - 开源API管理平台.

#### Symfony2

* [REST APIs with Symfony2: the Right Way](http://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/) - 使用Symfony2框架构建最先进的REST API的完整指南.
* [FOSRestBundle](https://github.com/FriendsOfSymfony/FOSRestBundle) -  REST API的捆绑处理视图，路由，错误处理等.
* [stanlemon/rest-bundle](https://github.com/stanlemon/rest-bundle) - 使用约定优于配置，基于Doctrine实体构建REST API.
* [lakion/Lionframe](http://lakion.com/lionframe) - 在几个社区库之间进行混合以简化API开发.
* [BazingaHateoasBundle](https://github.com/willdurand/BazingaHateoasBundle) - 整合 [Hateoas](https://github.com/willdurand/Hateoas) 库成为Symfony2应用程序.
* [Symfony REST Edition](https://github.com/gimler/symfony-rest-edition) - Start with a Symfony2 application with all REST-friendly bundles pre-configured.
* [NgAdminGeneratorBundle](https://github.com/marmelab/NgAdminGeneratorBundle) - 基于`stanlemon / rest-bundle`的Boostrap ng-admin配置.
* [DunglasApiBundle](https://github.com/dunglas/DunglasApiBundle) - 构建遵循Hydra / JSON-LD规范的REST API.
* [API Platform](https://github.com/api-platform/api-platform) - 专门用于创建超媒体REST API的Symfony版本.
* [NelmioApiDocBundle](https://github.com/nelmio/NelmioApiDocBundle) - 从注释生成REST API的文档.

### Python

* [Django REST framework](http://www.django-rest-framework.org/) - 功能强大且灵活的工具包，可轻松构建Web API.
* [django-tastypie](http://tastypieapi.org/) - 为Django应用程序创建美味的API.
* [flask-restful](http://flask-restful.readthedocs.org/) -  Flask扩展，增加了对快速构建REST API的支持.
* [flask-restless](https://flask-restless.readthedocs.org/en/latest/) -  Flask扩展，用于为使用SQLAlchemy（或Flask-SQLAlchemy）定义的数据库模型生成ReSTful API.
* [hug](http://www.hug.rest/) - 轻量且快速的API框架.
* [sandman](https://github.com/jeffknupp/sandman) - 用于现有数据库驱动系统的自动REST API.
* [restless](http://restless.readthedocs.org/en/latest/) - 基于从TastyPie学到的经验教训的框架无关REST框架.
* [savory-pie](https://github.com/RueLaLa/savory-pie/) -  REST API构建库（django等）.
* [Python Eve](http://python-eve.org/)   -  Eve是一个专为人类设计的开源Python REST API框架.  它允许毫不费力地构建和部署高度可定制的，功能齐全的RESTful Web服务.
* [Ramses](https://ramses.readthedocs.org/en/stable/) - 通过在运行时从它们生成生产就绪API，使RAML文件可执行.
* [Flask-Potion](https://github.com/biosustain/potion)   -  Flask-Potion是一个功能强大的Flask扩展，用于构建RESTful JSON API.  它还提供了几个客户端，以便更轻松地访问API.
* [apistar](https://github.com/encode/apistar) - 专为Python 3设计的智能Web API框架. 
* [Falcon](https://github.com/falconry/falcon) -  Falcon是一个裸机Python Web API框架，用于构建高性能微服务，应用程序后端和更高级别的框架.

### Ruby

* [Grape](http://www.ruby-grape.org) - 用于在Ruby中创建类似REST的API的意见微框架.
* [Rails](http://guides.rubyonrails.org/api_app.html) -  RailsGuides：将Rails用于仅限API的应用程序.

### Go

* [gocrud](https://github.com/manishrjain/gocrud)：使用库来简化创建，更新和删除任意深度结构化数据 - 使构建REST服务变得快速而简单.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - “net / http”顶部的薄层，有助于轻松构建RESTful API.
* [sleepy](https://github.com/dougblack/sleepy) - 用Go编写的RESTful微框架.
* [restit](https://github.com/yookoala/restit) -  Go micro framework帮助编写RESTful API集成测试.
* [go-relax](https://github.com/codehack/go-relax) - 用于构建RESTful API的可插入组件的框架.
* [go-rest](https://github.com/ungerik/go-rest) -  Go的小而邪恶的REST框架.
* [go-restful](https://github.com/emicklei/go-restful) - 用于构建restful API的声明性高度可读框架.
* [Goat](https://github.com/bahlo/goat) -  Go中的简约REST API服务器.
* [Resoursea](https://github.com/resoursea/api) - 用于快速编写基于资源的服务的REST框架.
* [Zerver](https://github.com/cosiner/zerver) -  Zerver是一个富有表现力，模块化，功能完善的RESTful框架.

### Java

* [RestExpress](https://github.com/RestExpress/RestExpress) - 基于Netty，高性能，轻量级，无容器，可插件扩展的框架，是微服务架构的理想选择.
* [Vertx-Web](https://github.com/vert-x3/vertx-web) -  Vert.x-Web是一组用于使用Vert.x构建Web应用程序的构建块，Vert.x是一个用于在JVM上构建响应式应用程序的工具包.
* [Dropwizard](https://github.com/dropwizard/dropwizard) - 用于开发操作友好，高性能，RESTful Web服务的框架.

### Haskell
* [Rest for Haskell](https://github.com/silkapp/rest)   - 此包允许您在Haskell中创建REST API.  这些API可以在不同的Web框架中运行.  它们还可用于自动生成文档以及客户端库.

## Testing

### Querying

* [Hurl.it](https://www.hurl.it/) - 使用简单的基于Web的HTTP客户端发出HTTP请求 - 比如云中的“curl”.
* [httpie](https://github.com/jkbrzt/httpie) - 命令行HTTP客户端，比`curl`更加开发友好.
* [Postman REST Client](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm) -  Chrome扩展程序对于手动测试REST API至关重要.
* [resty](https://github.com/micha/resty) - 可以在管道中使用的小命令行REST客户端（bash或zsh）.
* [jq](https://github.com/stedolan/jq) - 命令行JSON处理器，与cURL等命令行HTTP客户端结合使用.
* [HttpMaster](http://www.httpmaster.net)   - 用于测试REST API和服务的GUI工具.  仅限Windows操作系统.
* [Http-console](https://github.com/cloudhead/http-console) -  HTTP的命令行界面，让您*像本地*一样说HTTP
* [HTTP Prompt](https://github.com/eliangcs/http-prompt) -  HTTP Prompt是一个交互式命令行HTTP客户端，具有基于HTTPie和prompt_toolkit的自动完成和语法突出显示功能.
* [rest-assured](https://github.com/rest-assured/rest-assured) - 用于轻松测试REST服务的Java DSL.
* [Insomnia](https://github.com/getinsomnia/insomnia) - 跨平台HTTP和GraphQL客户端

### Mocking

* [RequestBin](http://requestb.in/) - 检查和调试客户端或第三方API发送的webhook请求.
* [httpbin](http://httpbin.org) -  HTTP请求和响应服务 - 用于HTTP的a / k / Swiss Army Knife.
* [FakeRest](https://github.com/marmelab/FakeRest) - 修补XMLHttpRequest伪造REST API客户端.
* [json-server](https://github.com/typicode/json-server) - 使用快速原型设计从夹具文件提供REST API.
* [Mocky.io](http://www.mocky.io/) - 免费在线服务，以创建虚假的HTTP响应.
* [Swagger API Mock](https://github.com/bulkismaslom/swagger-api-mock) - 基于swagger架构模拟RESTful API
* [Request Baskets](https://github.com/darklynx/request-baskets) - 服务以收集HTTP请求并通过RESTful API或Web UI检查它们.
* [DuckRails](https://github.com/iridakos/duckrails) - 快速动态模拟API端点.

### Public REST APIs To Use In Tests
* [Deck of Cards API](http://deckofcardsapi.com) - 用于模拟一副牌的开放式API.
* [ProgrammableWeb](http://www.programmableweb.com/apis/directory) - 世界上最大的API存储库.
* [Public APIS](https://www.publicapis.com/) - 探索Galaxy中最大的API目录.
* [Marvel Comics API](http://developer.marvel.com/) - 查询关于漫威超级英雄的人物，故事和事件.
* [JSON Placeholder](http://jsonplaceholder.typicode.com/) - 免费在线REST服务，您可以在需要一些虚假数据时使用.
* [APIs.guru](http://APIs.guru) -  Wikipedia for Web API，每个API都有OpenAPI / Swagger描述.

## Documentation

* [Swagger](http://swagger.io/) -  REST API的文档/查询Web界面.
* [API doc](http://apidocjs.com/) -  RESTful Web API的内联文档.
* [raml2html](https://github.com/raml2html/raml2html) - 从RAML文件生成HTML文档.
* [ReDoc](https://github.com/Rebilly/ReDoc/) -  OpenAPI / Swagger驱动的三面板文档.
* [Slate](https://github.com/lord/slate) - 使用Middleman的美观且响应迅速的三面板API文档.

## API Gateway

* [Kong](https://github.com/Kong/kong) - 由Nginx支持的可扩展，分布式和面向插件的API网关.
* [Tyk API Gateway](https://github.com/TykTechnologies/tyk) - 带有分析日志记录的轻量级API网关，用Go编写.
* [API Umbrella](https://github.com/NREL/api-umbrella) - 使用Lua编写的用于公开Web服务的API管理平台，具有Web界面和分析功能.
* [WSO2 API Management](https://github.com/wso2/product-apim) - 具有轻量级网关和API生命周期管理的API管理工具，用Java编写.

## SaaS Tools

* [Runscope](https://www.runscope.com/) - 自动API监控和测试.
* [Ping-API](https://ping-api.com/) - 自动API监控和测试.
* [import.io Magic](https://magic.import.io/) - 只需单击一下，即可从任何网站创建REST API.
* [Apiary](https://apiary.io/) - 协作设计，即时API模拟，生成的文档，集成的代码示例，调试和自动化测试.
* [Amazon API Gateway](https://aws.amazon.com/api-gateway/) -  Amazon API Gateway是一种完全托管的服务，使开发人员可以轻松地以任何规模创建，发布，维护，监控和保护API.
* [Apigee](https://apigee.com) -  Apigee是面向企业和开发人员的API技术和服务的领先提供商.
* [3scale](https://www.3scale.net/) - 基于Nginx的API网关，可将内部和外部API服务与3scale的API管理平台集成.
* [Assertible](https://assertible.com) - 在部署和跨环境后连续测试和监控API.
* [Moesif](https://www.moesif.com) - 用于RESTful和GraphQL的调试，监控和使用情况跟踪的API分析.


## Miscellaneous

* [ng-admin](https://github.com/marmelab/ng-admin) - 为任何RESTful API添加AngularJS管理GUI.
* [admin-on-rest](https://github.com/marmelab/admin-on-rest) - 为任何RESTful API添加ReactJS管理GUI.
* [swagger-codegen](https://github.com/swagger-api/swagger-codegen) - 给定OpenAPI规范（以前称为Swagger规范）自动生成客户端库或服务器存根.
* [Lumber](https://github.com/ForestAdmin/lumber) - 生成应用程序的管理界面.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

这项工作是根据a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
