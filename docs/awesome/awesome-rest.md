<div class="github-widget" data-repo="marmelab/awesome-rest"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome REST [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

关于RESTful API架构，开发，测试和性能的重要资源的协作列表. 随时为这个持续不断的清单做出贡献.




## Design

* [建筑风格和
基于网络的软件体系结构的设计]（https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm）-Roy Fielding的论文定义了REST
* [HTTP API design guide extracted from work on the Heroku Platform API](https://github.com/interagent/http-api-design)
* [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* [How to design a REST API?](http://blog.octo.com/en/design-a-rest-api/) -解决安全性，分页，过滤，版本控制，部分答案，CORS等的完整指南.
* [Richardson Maturity Model](http://martinfowler.com/articles/richardsonMaturityModel.html) -由Martin Fowler解释，最初由Leonard Richardson在 [QCon 2008](https://www.crummy.com/writing/speaking/2008-QCon/act3.html).
* [Enterprise Integration Using REST](http://martinfowler.com/articles/enterpriseREST.html) -讨论非公开API所具有的约束和灵活性，以及​​在多个团队之间进行大规模RESTful集成所获得的经验教训.
* [HATEOAS](http://timelessrepo.com/haters-gonna-hateoas) -明确说明HATEOAS是什么，以及为什么要使用它.
* [How to GET a cup of coffee](http://www.infoq.com/articles/webber-rest-workflow/)
* [REST API Tutorial](http://www.restapitutorial.com/) -RestApiTutorial.com致力于跟踪REST API最佳实践，并提供资源来为开发人员提供快速参考和自我教育.
* [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md#readme) -Microsoft REST API指南作为一种设计原则，鼓励应用程序开发人员通过RESTful HTTP接口访问资源.
* [API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist) -有关REST API安全性的最佳做法

## Standards

* [JSON API](http://jsonapi.org/) -在JSON中构建API的标准.
* [RAML](http://raml.org/) -描述RESTful API的简单方法.
* [JSend](http://labs.omniti.com/labs/jsend) -简单的规范，它规定了应如何格式化来自Web服务器的JSON响应的一些规则.
* [OData](http://www.odata.org/)  -开放协议，允许创建和使用可查询和可互操作的RESTful API. 非常复杂.
* [HAL](https://tools.ietf.org/html/draft-kelly-json-hal-06) -简单的格式，提供了一种一致且简便的方法来在API中的资源之间建立超链接（请参阅： [HATEOAS](#hateoas)).
* [JSON-LD](http://json-ld.org/) -描述JSON（W3C）中的链接数据和超媒体关系的标准.
* [Hydra](http://www.hydra-cg.com/) -超媒体驱动的Web API（W3C）的词汇表.
* [Schema.org](http://schema.org) -描述通用数据模型的模式集合.
* [OpenAPI](https://openapis.org/) -OpenAPI规范（以前称为Swagger规范）是世界上最受欢迎的用于定义Restful API的描述格式.

## Clients

### PHP Clients

* [Guzzle](http://guzzle.readthedocs.org/en/latest/) -使用RESTful Web服务的HTTP客户端和框架.
* [Buzz](https://github.com/kriswallsmith/buzz) -另一个轻量级的HTTP客户端.
* [unirest for PHP](https://github.com/Mashape/unirest-php) -简化的轻量级HTTP客户端库.

### JavaScript Clients

* [restangular](https://github.com/mgonto/restangular) -AngularJS服务，可正确轻松地处理REST API.
* [restful.js](https://github.com/marmelab/restful.js) -JS客户端，用于与服务器端RESTful资源进行交互.
* [traverson](https://github.com/basti1302/traverson) -用于Node.js和浏览器的Hypermedia API / HATEOAS客户端
* [raml-client-generator](https://github.com/mulesoft/raml-client-generator) -为js生成静态客户端库.

### Node.js Clients

 * [restler](https://github.com/danwrong/restler) -用于node.js的REST客户端库.
 * [unirest for Node.js](https://github.com/Mashape/unirest-nodejs) -简化的轻量级HTTP客户端库.

### Ruby Clients

* [RESTClient](https://github.com/rest-client/rest-client) -Ruby的简单HTTP和REST客户端，受用于指定操作的微框架语法的启发.
* [Spyke](https://github.com/balvig/spyke) -以类似ActiveRecord的方式与REST服务进行交互.
* [excon](https://github.com/excon/excon)  -可用，快速，简单的Ruby HTTP 1.1. 它可以作为一般的HTTP客户端使用，特别适合在API客户端中使用.
* [httparty](https://github.com/jnunemaker/httparty) -使HTTP再次有趣！
* [Net::HTTP](http://ruby-doc.org/stdlib/libdoc/net/http/rdoc/Net/HTTP.html) -Net :: HTTP提供了一个丰富的库，可用于构建HTTP用户代理.
* [raml-ruby-client-generator](https://github.com/zlx/raml-ruby-client-generator) -从RAML文件自动生成API客户端.

### Go Clients

* [gopencils](https://github.com/bndr/gopencils) -小而简单的程序包，可以轻松使用REST API.
* [resty](https://github.com/go-resty/resty) -受Ruby rest-client启发的Go的简单HTTP和REST客户端.

## Servers

### Directly On Top Of A RMDB

* [postgrest](https://github.com/begriffs/postgrest) -直接从现有PostgreSQL数据库提供完全RESTful API.
* [MySQL HTTP plugin](http://blog.ulf-wendel.de/2014/mysql-5-7-http-plugin-mysql/) - Simple REST-like / CRUD server for any MySQL database.
* [pREST](https://github.com/prest/prest) -使用Go编写的任何现有PostgreSQL数据库中的完全RESTful API.

### Node.js

* [node-restify](https://github.com/restify/node-restify) -专门用于REST API的框架.
* [Sails.js](http://sailsjs.org/) -嵌入命令以自动生成REST API的Node.js Web框架.
* [mers](https://github.com/jspears/mers) -将Mongoose查找器公开为RESTful API的快速服务.
* [Baucis](https://github.com/wprl/baucis) -根据您的Mongoose实体构建可扩展的REST API.
* [flatiron/resourceful](https://github.com/flatiron/resourceful) -JavaScript的同构资源引擎.
* [loopback](http://loopback.io/) -强大的Node.js框架，用于创建API并轻松连接到后端数据源.
* [Feathers](http://feathersjs.com/) -是一个实时的微服务Web框架，可让您通过RESTful资源，套接字和灵活的插件来控制数据.
* [Expressa](https://github.com/thomas4019/expressa) -Express中间件，可使用简单的管理员编辑器和权限模型从JSON模式创建API.
* [rest-hapi](https://github.com/JKHeadley/rest-hapi) -基于支持关系数据的猫鼬模型生成RESTful API.
* [Nestjsx/crud](https://github.com/nestjsx/crud) -使用NestJS和TypeORM为RESTful API生成CRUD控制器和服务.

### PHP

* [Microrest](https://github.com/marmelab/microrest.php) -在任何关系数据库之上提供REST API的微型Web应用程序.
* [Drest](https://github.com/leedavis81/drest) -用于将Doctrine实体公开为REST资源端点的库.
* [Restler](https://github.com/Luracast/Restler) -轻量级框架，将PHP方法公开为RESTful Web API.
* [HAL](https://github.com/blongden/hal) -超文本应用程序语言（HAL）构建器库.
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) -使用Zend Framework 2构建的API构建器.
* [phprest](https://github.com/phprest/phprest) -适用于PHP的专用REST微框架.
* [Hateoas](https://github.com/willdurand/Hateoas) -PHP库，用于支持实现HATEOAS REST Web服务的表示形式.
* [Fusio](https://github.com/apioo/fusio) -开源API管理平台.

#### Symfony2

* [REST APIs with Symfony2: the Right Way](http://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/) -使用Symfony2框架构建最新REST API的完整指南.
* [FOSRestBundle](https://github.com/FriendsOfSymfony/FOSRestBundle) -REST API的捆绑包处理视图，路由，错误处理等.
* [stanlemon/rest-bundle](https://github.com/stanlemon/rest-bundle) -使用约定优于配置，基于Doctrine实体构建REST API.
* [lakion/Lionframe](http://lakion.com/lionframe) -在多个社区库之间建立Glu，以简化API开发.
* [BazingaHateoasBundle](https://github.com/willdurand/BazingaHateoasBundle) -整合 [Hateoas](https://github.com/willdurand/Hateoas) 库导入Symfony2应用程序.
* [Symfony REST Edition](https://github.com/gimler/symfony-rest-edition) -从Symfony2应用程序开始，该应用程序已预先配置了所有REST友好的捆绑软件.
* [NgAdminGeneratorBundle](https://github.com/marmelab/NgAdminGeneratorBundle) -基于`stanlemon / rest-bundle`的Boostrap ng-admin配置.
* [DunglasApiBundle](https://github.com/dunglas/DunglasApiBundle) -建立遵循Hydra / JSON-LD规范的REST API.
* [API Platform](https://github.com/api-platform/api-platform) -专用于创建超媒体REST API的Symfony版本.
* [NelmioApiDocBundle](https://github.com/nelmio/NelmioApiDocBundle) -通过注释为REST API生成文档.

### Python

* [Django REST framework](http://www.django-rest-framework.org/) -功能强大且灵活的工具包，可轻松构建Web API.
* [django-tastypie](http://tastypieapi.org/) -为Django应用创建美味的API.
* [flask-restful](http://flask-restful.readthedocs.org/) -Flask扩展，增加了对快速构建REST API的支持.
* [flask-restless](https://flask-restless.readthedocs.org/en/latest/) -Flask扩展，用于为使用SQLAlchemy（或Flask-SQLAlchemy）定义的数据库模型生成ReSTful API.
* [hug](http://www.hug.rest/) -轻巧快速的API框架.
* [sandman](https://github.com/jeffknupp/sandman) -用于现有数据库驱动系统的自动化REST API.
* [restless](http://restless.readthedocs.org/en/latest/) -与框架无关的REST框架，基于从DeliciousPie汲取的经验教训.
* [savory-pie](https://github.com/RueLaLa/savory-pie/) -REST API构建库（Django等）.
* [Python Eve](http://python-eve.org/)  -Eve是一个为人类设计的开源Python REST API框架. 它允许轻松构建和部署高度可定制的，功能齐全的RESTful Web服务.
* [Ramses](https://ramses.readthedocs.org/en/stable/) -通过在运行时从它们生成可用于生产的API，使RAML文件可执行.
* [Flask-Potion](https://github.com/biosustain/potion)  -Flask-Potion是功能强大的Flask扩展，用于构建RESTful JSON API. 它还提供了多个客户端，可以更轻松地访问API.
* [apistar](https://github.com/encode/apistar) -为Python 3设计的智能Web API框架. 
* [Falcon](https://github.com/falconry/falcon) -Falcon是一个裸机Python Web API框架，用于构建高性能微服务，应用程序后端和更高级别的框架.
* [FastAPI](https://github.com/tiangolo/fastapi)  -FastAPI是一种现代，快速（高性能）的Web框架，用于基于标准Python类型提示使用Python 3.6+构建API. 使用基于OpenAPI和JSON Schema的Swagger UI和ReDoc的自动API文档.

### Ruby

* [Grape](http://www.ruby-grape.org) -在Ruby中创建类似REST的API的自觉的微框架.
* [Rails](http://guides.rubyonrails.org/api_app.html) -RailsGuides：将Rails用于仅API的应用程序.

### Go

* [gocrud](https://github.com/manishrjain/gocrud)：转到库以简化创建，更新和删除任意深度结构化数据的过程—使构建REST服务变得快速，容易.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) -位于“ net / http”之上的薄层，可帮助轻松构建RESTful API.
* [sleepy](https://github.com/dougblack/sleepy) -用Go编写的RESTful微框架.
* [restit](https://github.com/yookoala/restit) -使用微型框架来帮助编写RESTful API集成测试.
* [go-relax](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's.
* [go-rest](https://github.com/ungerik/go-rest) -Go的小巧的REST框架.
* [go-restful](https://github.com/emicklei/go-restful) -用于构建静态API的声明性高度可读的框架.
* [Goat](https://github.com/bahlo/goat) -Go中的简约REST API服务器.
* [Resoursea](https://github.com/resoursea/api) -用于快速编写基于资源的服务的REST框架.
* [Zerver](https://github.com/cosiner/zerver) -Zerver是一个表达力强，模块化，功能完善的RESTful框架.

### Java

* [RestExpress](https://github.com/RestExpress/RestExpress) -基于Netty的高性能，轻量级，无容器，可扩展插件的框架，非常适合微服务架构.
* [Vertx-Web](https://github.com/vert-x3/vertx-web) -Vert.x-Web是使用Vert.x（用于在JVM上构建响应式应用程序的工具包）构建Web应用程序的一组构建块.
* [Dropwizard](https://github.com/dropwizard/dropwizard) -用于开发对ops友好的高性能RESTful Web服务的框架.

### Scala

* [Chaos](https://github.com/mesosphere/chaos) -用于在Scala中编写REST服务的轻量级框架.


### Haskell
* [Rest for Haskell](https://github.com/silkapp/rest)  -该软件包允许您在Haskell中创建REST API. 这些API可以在不同的Web框架中运行. 它们还可以用于自动生成文档以及客户端库.

## Testing

### Querying

* [httpie](https://github.com/jkbrzt/httpie) -命令行HTTP客户端，远比`curl`开发友好.
* [Postman REST Client](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm) -Chrome扩展对于手动测试REST API是必不可少的.
* [resty](https://github.com/micha/resty) -可以在管道（bash或zsh）中使用的小命令行REST客户端.
* [jq](https://github.com/stedolan/jq) -命令行JSON处理器，与cURL等命令行HTTP客户端结合使用.
* [HttpMaster](http://www.httpmaster.net)  -用于测试REST API和服务的GUI工具. 仅Windows操作系统.
* [Http-console](https://github.com/cloudhead/http-console) -HTTP的命令行界面，可让您*像本地人一样讲HTTP *
* [HTTP Prompt](https://github.com/eliangcs/http-prompt) -HTTP提示是一个交互式命令行HTTP客户端，具有自动完成功能和语法突出显示功能，基于HTTPie和hint_toolkit构建.
* [rest-assured](https://github.com/rest-assured/rest-assured) -Java DSL，可轻松测试REST服务.
* [Insomnia](https://github.com/getinsomnia/insomnia) -跨平台HTTP和GraphQL客户端
* [ExtendsClass](https://extendsclass.com/rest-client-online.html) -使用基于Web的简单HTTP客户端发出HTTP请求.
* [TestMace](https://testmace.com) -用于API自动化测试的跨平台简单但功能强大的IDE.

### Mocking

* [RequestBin](https://requestbin.com/) -检查和调试您的客户端或第三方API发送的Webhook请求.
* [httpbin](http://httpbin.org) -HTTP请求和响应服务-用于HTTP的a / k / a瑞士军刀.
* [FakeRest](https://github.com/marmelab/FakeRest) -修补XMLHttpRequest以伪造REST API客户端.
* [json-server](https://github.com/typicode/json-server) -使用快速原型设计从夹具文件提供REST API.
* [Mocky.io](http://www.mocky.io/) -免费的在线服务，以创建伪造的HTTP响应.
* [Swagger API Mock](https://github.com/bulkismaslom/swagger-api-mock) -基于swagger模式的RESTful API模拟
* [Request Baskets](https://github.com/darklynx/request-baskets) -收集HTTP请求并通过RESTful API或Web UI检查它们的服务.
* [DuckRails](https://github.com/iridakos/duckrails) -快速，动态地模拟API端点.
* [Mockoon](https://mockoon.com)  -在本地轻松创建模拟API. 无需远程部署，无需帐户，即可开源.

### Public REST APIs To Use In Tests
* [Deck of Cards API](http://deckofcardsapi.com) -用于模拟一副纸牌的开放API.
* [ProgrammableWeb](http://www.programmableweb.com/apis/directory) -世界上最大的API存储库.
* [Public APIS](https://www.publicapis.com/) -探索Galaxy中最大的API目录.
* [Marvel Comics API](http://developer.marvel.com/) -查询有关Marvel超级英雄的角色，故事，事件.
* [JSON Placeholder](http://jsonplaceholder.typicode.com/) -免费的在线REST服务，可在需要一些虚假数据时使用.
* [APIs.guru](http://APIs.guru) -Wikipedia for Web API，每个API都有OpenAPI / Swagger描述.

## Documentation

* [Swagger](http://swagger.io/) -REST API的文档/查询Web界面.
* [API doc](http://apidocjs.com/) -RESTful Web API的内联文档.
* [raml2html](https://github.com/raml2html/raml2html) -从RAML文件生成HTML文档.
* [ReDoc](https://github.com/Rebilly/ReDoc/) -由OpenAPI / Swagger支持的三面板文档.
* [Slate](https://github.com/lord/slate) -使用Middleman的精美且响应迅速的三面板API文档.

## API Gateway

* [Kong](https://github.com/Kong/kong) -由Nginx支持的可扩展，分布式和面向插件的API网关.
* [Tyk API Gateway](https://github.com/TykTechnologies/tyk) -使用Go编写的具有分析日志记录的轻量级API网关.
* [API Umbrella](https://github.com/NREL/api-umbrella) -用Lua编写的API管理平台，用于通过Web界面和分析公开Web服务.
* [WSO2 API Management](https://github.com/wso2/product-apim) -具有Java编写的轻量级网关和API生命周期管理的API管理工具.
* [Express Gateway](https://github.com/ExpressGateway/express-gateway) -建立在ExpressJS（Node.js）之上的微服务API网关.
* [KrakenD](https://github.com/devopsfaith/krakend) 具有中间件的超高性能API网关. 用Go编写.

## SaaS Tools

* [Runscope](https://www.runscope.com/) -自动化的API监控和测试.
* [Ping-API](https://ping-api.com/) -自动化的API监控和测试.
* [import.io Magic](https://magic.import.io/) -一键式从任何网站创建REST API.
* [Apiary](https://apiary.io/) -协同设计，即时API模拟，生成的文档，集成的代码示例，调试和自动测试.
* [Amazon API Gateway](https://aws.amazon.com/api-gateway/) -Amazon API Gateway是一项完全托管的服务，使开发人员可以轻松地创建，发布，维护，监控和保护各种规模的API.
* [Apigee](https://apigee.com) -Apigee是为企业和开发人员提供API技术和服务的领先提供商.
* [3scale](https://www.3scale.net/) -基于Nginx的API网关，可将内部和外部API服务与3scale的API管理平台集成在一起.
* [Assertible](https://assertible.com) -部署后和跨环境连续测试和监视您的API.
* [Moesif](https://www.moesif.com) -用于RESTful和GraphQL的调试，监视和使用情况跟踪的API分析.
* [Beeceptor](https://beeceptor.com/)  -HTTP检查，模拟和代理服务. 提供命名端点，用于创建模拟API端点和模拟响应.

## Miscellaneous

* [react-admin](https://github.com/marmelab/react-admin) -将ReactJS管理GUI添加到任何RESTful API.
* [ng-admin](https://github.com/marmelab/ng-admin) -将AngularJS管理GUI添加到任何RESTful API.
* [swagger-codegen](https://github.com/swagger-api/swagger-codegen) -根据OpenAPI规范（以前称为Swagger规范）自动生成客户端库或服务器存根.
* [Lumber](https://github.com/ForestAdmin/lumber) -生成应用程序的管理界面.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

这项工作是根据 [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
