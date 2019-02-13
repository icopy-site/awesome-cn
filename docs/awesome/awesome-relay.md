## Awesome Relay [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
令人敬畏的资源 [Relay](https://github.com/facebook/relay)，基于 [Awesome](https://github.com/sindresorhus/awesome/) 项目

## Table of Contents
- [Learning Resources](#learning-resources)
  - [Documentation](#documentation)
  - [FAQs](#faqs)
  - [Tutorials](#tutorials)
  - [Overviews](#overviews)
  - [Example Implementations](#example-implementations)
  - [Lists of Lists](#lists-of-lists)
- [Ecosystem](#ecosystem)
  - [Libraries & Packages](#libraries--packages)
  - [Tooling](#tooling)
  - [Starter Kits](#starter-kits)
- [Relay-Specific Server Support](#relay-specific-server-support)
  - [Go](#go)
  - [JavaScript](#javascript)
  - [Python](#python)
  - [Ruby](#ruby)
    - [Rails](#rails)
  - [Scala](#scala)
- [Testing](#testing)

## Learning Resources
## Documentation
- [Official Docs](https://facebook.github.io/relay/docs/getting-started.html#content) - 官方接力文件.

## FAQs
- [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47)   - 回答常见问题！  目前中继资源很少，所以如果你遇到困难，这将非常有用.

## Tutorials
- [Getting Started with Relay](https://auth0.com/blog/2015/10/06/getting-started-with-relay/) - 手动继电器的少数详细步骤之一.
- [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6#.1i64q1pf9) - 一个完整可行的例子.
  - [Relay 102: Mutations](https://medium.com/@clayallsopp/relay-102-mutations-d8b471a4730e#.i9vuv3vxl) - 关注突变的“接力101”的后续行动.
- [Facebook Relay talk - Lunch and Learn session](https://www.youtube.com/watch?v=sP3n-nht0Xo) - 构建一个简单的应用程序和演示的演练 [GraphiQL](https://github.com/graphql/graphiql).
- [A Beginner's Guide to Relay Mutations](http://blog.pathgather.com/blog/a-beginners-guide-to-relay-mutations) - 深度突变.
- [Learn Relay](https://learnrelay.org/) - 向您展示如何制作以Pokemon为主题的CRUD应用程序，提供基于云的个人GraphQL后端，以便您可以专注于客户端代码. 

## Overviews
- [React Data Fetching with Relay](http://www.sitepoint.com/react-data-fetching-with-relay/) - 清晰概述Relay移动部件和魔法.
- [Joseph Savona - Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg) - 来自Facebook团队的Relay概念概述.
- [F8 2015 - React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU) - 接力概述，一些关于哲学的概述.
- [Relay - Daniel Dembach - Hamburg React.js Meetup](https://www.youtube.com/watch?v=dvWTxy1eY6s)   - 对继电器的一般概述，对替代方案的一些讨论.  最后的问答在常见问题中有所涉及.
- [Facebook Relay talk - Lunch and Learn session](https://www.youtube.com/watch?v=sP3n-nht0Xo) - 构建一个简单的应用程序和演示的演练 [GraphiQL](https://github.com/graphql/graphiql).
- [React with Relay and GraphQL with Andrew Smith](https://www.youtube.com/watch?v=Cfna8gwt9h8)   -  Relay和GraphQL的高级概述，以及来自观众的一些有用的讨论.  还讨论了其他前端框架.
- [Relay for Visual Learners](http://sgwilym.github.io/relay-visual-learners/) - 非常清晰的图表，阐述了中继的不同部分如何相互关联.
- [Relay: Seamless Syncing For React](http://www.slideshare.net/BrooklynZelenka/relay-seamless-syncing-for-react-vanjs) - 概述Relay是什么，以及对在生产中使用它的经验的一些讨论.
-  Facebook继电器卡通简介 -  Relay工作原理概述，完整插图.
  - [Part 1: Saying what data you need with GraphQL](https://code-cartoons.com/a-cartoon-intro-to-facebook-s-relay-part-1-3ec1a127bca5)
  - [Part 2: Fetching data from the server](https://code-cartoons.com/a-cartoon-intro-to-facebook-s-relay-part-2-d4a2435aee59)
  - [Part 3: Syncing changes back up to the server](https://code-cartoons.com/a-cartoon-intro-to-facebook-s-relay-part-3-9d8fcf8db670)
  - [Part 4: How it all fits together](https://code-cartoons.com/a-cartoon-intro-to-facebook-s-relay-part-4-aef7d819a8ed)
 
## Example Implementations
- [Relay TODO MVC](https://github.com/taion/relay-todomvc) - 使用Relay编写的经典TODO示例应用程序.
- [`relay-chat`](https://github.com/transedward/relay-chat) - 具有路由和分页的中继.
- [`koa-graphql-relay-example`](https://github.com/chentsulin/koa-graphql-relay-example) - “TODO”应用程序 [`koa-graphql`](https://github.com/chentsulin/koa-graphql) 和“接力”.
- [`todomvc-relay-go`](https://github.com/sogko/todomvc-relay-go) - 继电器TodoMVC应用程序，由Golang GraphQL后端驱动.

## Lists of Lists
- [Relay and GraphQL Introduction Materials](https://quip.com/oLxzA1gTsJsE)

## Ecosystem
## Libraries & Packages
- [`graphql-relay-js`](https://github.com/graphql/graphql-relay-js) - 简化为`react-relay`创建JS GraphQL服务器.
- [Babel Relay Plugin](https://www.npmjs.com/package/babel-relay-plugin) - 使用Relay最新的ES6 +语法.
- [`react-router-relay`](https://github.com/relay-tools/react-router-relay)   - 对于Relay，`react-router`绑定.  大大简化了许多本地状态UI用例.
  - [Relay and Routing](https://medium.com/@cpojer/relay-and-routing-36b5439bad9#.h91614i65) - 详细阐述了`react-router-relay`及其解决的问题.
  - [`relay-nested-routes`](https://www.npmjs.com/package/relay-nested-routes)   - 生成反映嵌套数据的嵌套路由.  有助于管理深层数据.
  - [`isomorphic-relay-router`](https://github.com/denvned/isomorphic-relay-router) - 服务器端渲染支持`react-router-relay`.
- [`relay-decorator`](https://github.com/4Catalyzer/relay-decorators) - 简单的带有ES7装饰器的中继容器的语法（`@`syntax）
- [`recompose-relay`](https://www.npmjs.com/package/recompose-relay) - 通过卷曲和在容器后提供组件来缓和继电器容器的组成.
- [`relay-local-schema`](https://github.com/relay-tools/relay-local-schema)   - 使用本地架构;  不需要远程GraphQL服务器.
- [`react-native-relay`](https://github.com/lenaten/react-native-relay) - 将Relay与React Native一起使用.
  - 可能会受到支持 [out of the box](https://github.com/facebook/relay/issues/26) 在将来.
- [`relay-sink`](https://github.com/acdlite/relay-sink) - 使用Relay在React组件之外获取和存储数据.
- [`babel-plugin-flow-relay-query`](https://github.com/guymers/babel-plugin-flow-relay-query) - 兑换 [Flow](http://flowtype.org) 类型为中继片段.
- [`sequelize-relay`](https://github.com/MattMcFarland/sequelize-relay) - 使继电器兼容 [`sequelize`](https://github.com/sequelize/sequelize).
- [`relay-mongodb-connection`](https://github.com/mikberg/relay-mongodb-connection) - 从MongoDB游标创建中继连接.
- [`relay-composite-network-layer`](https://github.com/eyston/relay-composite-network-layer) - 编写许多不同网络层的中继网络层，每个网络层都有自己的架构.
- [`react-relay-network-layer`](https://github.com/nodkz/react-relay-network-layer)   - 网络层，增加了对查询批处理和中间件的支持.  它还提供了一些有用的中间件，例如auth，用于日志记录等.

## Tooling
- [GraphiQL](https://github.com/graphql/graphiql) - 一个内省GraphQL，测试查询和突变的库.
  - [GraphiQL App](https://github.com/skevy/graphiql-app)   - 用于查看GraphQL，内省文档和测试查询/突变的独立应用程序.  非常适合调试您的中继应用程序.
- [`relay-local-schema`](https://github.com/relay-tools/relay-local-schema)   - 使用本地架构;  不需要远程GraphQL服务器.
- [Babel Relay Plugin](https://www.npmjs.com/package/babel-relay-plugin) - 使用Relay最新的ES6 +语法.

## Starter Kits
- [Relay Skeleton](https://github.com/fortruce/relay-skeleton) - 中继项目骨架.
- [Relay Starter Kit](https://github.com/relayjs/relay-starter-kit)   - 已使用基本设置设置的应用程序.  只需克隆和调整以满足您的需求！
- [Node.js API Starter Kit](https://github.com/kriasoft/nodejs-api-starter) - 使用Node.js，GraphQL和Relay构建数据API的Boilerplate和工具
- [Simple Relay Starter](https://github.com/mhart/simple-relay-starter) -  Browserify的版本 [Relay Starter Kit](https://github.com/relayjs/relay-starter-kit).
- [UniversalRelayBoilerplate](https://github.com/codefoundries/UniversalRelayBoilerplate)
Boactplate + React Native（iOS，Android），React（isomorphic，Material-UI），Relay，GraphQL，JWT，Node.js，Apache Cassandra的示例.
- [Relay on Rails Starter Kit](https://github.com/nethsix/relay-on-rails)   - 用于Rails服务器上的中继应用程序的准系统入门套件.  只需克隆和调整！
- [Relay Fullstack](https://github.com/lvarayut/relay-fullstack) - 与Relay，Express，Webpack，Babel，Material Design Lite和PostCSS集成的继电器入门套件.

## Relay-Specific Server Support
## Go
- [Go Relay](https://github.com/graphql-go/relay) -  Go / Golang库，帮助构建支持react-relay的graphql-go服务器.
- [`todomvc-relay-go`](https://github.com/sogko/todomvc-relay-go) - 反应，和/继电器TodoMVC应用程序，由Golang GraphQL后端驱动.

## JavaScript
- [`graphql-relay-js`](https://github.com/graphql/graphql-relay-js) - 简化为`react-relay`创建JS GraphQL服务器.

## Python
- [`graphql-relay-py`](https://github.com/graphql-python/graphql-relay-py) - 一个帮助构建支持`react-relay`的`graphql-py`服务器的库.
 
## Ruby
- [`graphql-relay-ruby`](https://github.com/rmosolgo/graphql-relay-ruby) -  GraphQL和Ruby的中继助手.

### Rails
- [GraphQL and Relay on Rails — First relay powered react component](https://medium.com/@gauravtiwari/graphql-and-relay-on-rails-first-relay-powered-react-component-cb3f9ee95eca#.c88zcoftn) - 完整的简单中继设置，包括可克隆的代码.
- [Relay/GraphQL On Rails](https://medium.com/@khor/relay-facebook-on-rails-8b4af2057152#.5hjih9wms) -  Relay with Rails的简短示例，附有几个图表以帮助理解.
- [Relay on Rails Starter Kit](https://github.com/nethsix/relay-on-rails)   - 用于Rails服务器上的中继应用程序的准系统入门套件.  只需克隆和调整！

## Scala
- [`sangria-relay`](https://github.com/sangria-graphql/sangria-relay) - 继电器支持 [Sangria](http://sangria-graphql.org).

## Testing
- [Writing Simple Unit Tests with Relay](https://medium.com/@mikaelberg/writing-simple-unit-tests-with-relay-707f19e90129) - 初步了解测试继电器. 
