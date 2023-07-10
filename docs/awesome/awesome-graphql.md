<div class="github-widget" data-repo="chentsulin/awesome-graphql"></div>
## awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 很棒的 GraphQL 列表

如果您想对此列表做出贡献（请这样做），请向我发送拉取请求.


<!-- MarkdownTOC depth=4 -->


<!-- /MarkdownTOC -->

<a name="spec" />

## Specifications

- [GraphQL](https://github.com/graphql/graphql-spec) - GraphQL 规范的工作草案.
- [GraphQL over HTTP](https://github.com/graphql/graphql-over-http) - “GraphQL over HTTP”规范的工作草案.
- [GraphQL Relay](https://relay.dev/docs/guides/graphql-server-specification/) - 符合 Relay 的 GraphQL 服务器规范.
- [OpenCRUD](https://github.com/opencrud/opencrud) - OpenCRUD 是数据库的 GraphQL CRUD API 规范.
- [Apollo Federation](https://www.apollographql.com/docs/federation/federation-spec/) - 阿波罗联盟规范
- [GraphQXL](https://gabotechs.github.io/graphqxl/) - GraphQXL 是 GraphQL 语言的扩展，具有一些附加功能，有助于创建大型且可扩展的服务器端模式.
- [GraphQL Scalars](https://www.graphql-scalars.com/) - 托管社区定义的自定义标量规范，以便与 @specifiedBy 一起使用.

<a name="foundation" />

## Foundations

- [GraphQL Foundation](https://graphql.org/foundation/) - Linux基金会下的GraphQL基金会

<a name="community" />

## Communities

- [Discord - GraphQL](https://discord.graphql.org/) - 官方 GraphQL.org 不和谐频道.
- [GraphQL Weekly](https://www.graphqlweekly.com/) - 每周简讯，重点介绍 GraphQL 社区的资源和新闻.
- [Apollo GraphQL Community](https://community.apollographql.com/) - 与其他开发人员联系并分享有关 Apollo GraphQL 平台各个部分的知识.
- [Discord - Reactiflux](http://join.reactiflux.com/) - Join `#help-graphql` on the Reactiflux Discord server.
- [Facebook](https://www.facebook.com/groups/795330550572866/) - 讨论、文章和知识共享的小组.
- [Twitter](https://twitter.com/search?q=%23GraphQL) - Use the hashtag `#graphql`.
- [StackOverflow](https://stackoverflow.com/questions/tagged/graphql)  - 问题与解答. 使用标签“graphql”.
- [GraphQL APIs](https://github.com/APIs-guru/graphql-apis) - 公共 GraphQL API 的集体列表.
- [/r/GraphQL](https://old.reddit.com/r/graphql/) - 一个包含有趣且信息丰富的 GraphQL 内容和讨论的 Reddit 子版块.
- [GraphQL Jobs](https://graphql.jobs) - 世界各地初创公司中基于 GraphQL 的职位列表.
- [Codever](https://www.codever.land/search?q=graphql)  - 开发书签. 使用标签 [graphql](https://www.codever.land/bookmarks/t/graphql).

<a name="meetup" />

## Meetups

- [Relay Meetup](https://relaymeetup.com/) - GraphQL 客户端 Relay 上的全球在线聚会.
- [Amsterdam](https://www.meetup.com/Amsterdam-GraphQL-Meetup/)
- [Bangalore](https://www.meetup.com/graphql-bangalore/)
- [Berlin](https://www.meetup.com/graphql-berlin/)
- [Buenos Aires](https://www.meetup.com/es-ES/GraphQL-BA/)
- [Copenhagen](https://www.meetup.com/Copenhagen-GraphQL-Meetup-Group/)
- [Dallas-Fort Worth](https://www.meetup.com/DFW-GraphQL-Meetup/)
- [Hamburg](https://www.meetup.com/GraphQL-Hamburg/)
- [London](https://www.meetup.com/GraphQL-London/)
- [Melbourne](https://www.meetup.com/GraphQL-Melbourne/)
- [Munich](https://www.meetup.com/GraphQL-Munich/)
- [New York City](https://www.meetup.com/GraphQL-NYC/)
- [San Francisco](https://www.meetup.com/GraphQL-SF/)
- [Seattle](https://www.meetup.com/Seattle-GraphQL/)
- [Sydney](https://www.meetup.com/GraphQL-Sydney/)
- [Tel Aviv](https://www.meetup.com/GraphQL-TLV/)
- [Wrocław](https://www.meetup.com/GraphQL-Wroclaw/)
- [Singapore](https://www.meetup.com/GraphQL-SG/)
- [Zurich](https://www.meetup.com/GraphQL-Zurich/)

<a name="impl" />

## Implementations

<a name="js" />

### JavaScript/TypeScript

- [graphql-js](https://github.com/graphql/graphql-js) - JavaScript 的 GraphQL 参考实现.
- [graphql-jit](https://github.com/zalando-incubator/graphql-jit) - 使用 JIT 编译器执行 GraphQL.

#### Clients

- [apollo-client](https://github.com/apollographql/apollo-client) - 适用于每个 UI 框架和 GraphQL 服务器的功能齐全、可用于生产的缓存 GraphQL 客户端.
- [graphql-request](https://github.com/prisma-labs/graphql-request) - 适用于 Node 和浏览器的最小 GraphQL 客户端.
- [typescript-graphql-request](https://graphql-code-generator.com/docs/plugins/typescript-graphql-request) - 使用 GraphQL Request 作为完全类型化的 SDK.
- [graphql-zeus](https://github.com/graphql-editor/graphql-zeus) - GraphQL Zeus 为“JavaScript”或“TypeScript”创建自动完成客户端库，为强类型查询提供自动完成功能.
- [graphqurl](https://github.com/hasura/graphqurl)  - 具有自动完成、订阅和 GraphiQL 功能的 GraphQL 卷曲. 也是一个极其简单的通用 JavaScript GraphQL 客户端.
- [aws-amplify](https://github.com/aws-amplify/amplify-js) - Amazon 开发的用于缓存、分析等的客户端库，其中包括一种获取 GraphQL 查询的方法.
- [gqty](https://github.com/gqty-dev/gqty) - TypeScript 的无 GraphQL 客户端

##### Frontend Framework Integrations

- [vue-apollo](https://github.com/vuejs/vue-apollo) - VueJS 的 Apollo/GraphQL 集成.
- [apollo-angular](https://github.com/kamilkisiela/apollo-angular) - 适用于 Angular 和每个 GraphQL 服务器的功能齐全、可用于生产的缓存 GraphQL 客户端.
- [svelte-apollo](https://github.com/timhall/svelte-apollo) - Apollo GraphQL 的 Svelte 集成.
- [ember-apollo-client](https://github.com/ember-graphql/ember-apollo-client) - Apollo 客户端和 GraphQL 的 ember-cli 插件.
- [apollo-elements](https://github.com/apollo-elements/apollo-elements) - 可在任何前端框架中工作的 GraphQL Web 组件.
- [sveltekit-kitql](https://github.com/jycouet/kitql) - 一组工具，可帮助您使用 SvelteKit 和 GraphQL 快速构建高效的应用程序.

###### React

- [react-apollo](https://www.apollographql.com/docs/react/) - 核心 @apollo/client 库提供与 React 的内置集成.
- [relay](https://github.com/facebook/relay) - Relay 是一个用于构建数据驱动的 React 应用程序的 JavaScript 框架.
- [urql](https://github.com/FormidableLabs/urql) - 一个简单的 React 缓存 GraphQL 客户端.
- [graphql-hooks](https://github.com/nearform/graphql-hooks) - 最小钩子优先的 GraphQL 客户端，具有缓存和服务器端渲染支持.
- [mst-gql](https://github.com/mobxjs/mst-gql) - mobx-state-tree 和 GraphQL 的绑定.
- [micro-graphql-react](https://github.com/arackaf/micro-graphql-react)  - 一个轻量级实用程序，用于将 GraphQL 添加到 React. 成分. 包括简单的缓存并使用 GET 请求，这些请求还可以通过服务工作线程进行缓存.
- [@gqty/react](https://github.com/gqty-dev/gqty) - TypeScript 的无 GraphQL 客户端

#### Servers

- [apollo-server](https://github.com/apollographql/apollo-server)  - 符合规范且可用于生产的 JavaScript GraphQL 服务器，可让您以模式优先的方式进行开发. 专为 Express、Connect、Hapi、Koa 等而构建.
- [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql) - 使用 Hapi 创建 GraphQL HTTP 服务器.
- [hapi-plugin-graphiql](https://github.com/rse/hapi-plugin-graphiql) - 用于GraphiQL集成的HAPI插件.
- [graphql-api-koa](https://github.com/jaydenseric/graphql-api-koa) - GraphQL Koa 中间件，从头开始实现 GraphQL.js 并支持原生 ESM.
- [koa-graphql](https://github.com/chentsulin/koa-graphql) - GraphQL Koa 中间件.
- [graphql-koa-scripts](https://github.com/ryanhs/graphql-koa-scripts)  - 简化了 GraphQL Koa 1 文件. 对于快速测试很有用
- [gql](https://github.com/deno-libs/gql) - 适用于 Deno 的通用 GraphQL HTTP 中间件.
- [mercurius](https://github.com/mercurius-js/mercurius) - Fastify 的 GraphQL 插件.
- [graphql-yoga](https://github.com/prisma-labs/graphql-yoga) - 功能齐全的 GraphQL Server，专注于轻松设置、性能和出色的开发人员体验.
- [graphitejs](https://github.com/graphitejs/server) - GraphQL 的 NodeJS 框架.
- [graphql-helix](https://github.com/contrawork/graphql-helix) - 高度发展的 GraphQL HTTP 服务器.

##### Databases & ORMs

- [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize) - GraphQL 的 Sequelize 助手.
- [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf) - 一些帮助围绕 BookshelfJS 模型定义 GraphQL 模式.
- [join-monster](https://github.com/acarl005/join-monster) - A GraphQL-to-SQL query execution layer for batch data fetching.

##### PubSub

- [graphql-ably-pubsub](https://www.npmjs.com/package/graphql-ably-pubsub) - GraphQL 的 Ably PubSub 实现，用于发布突变更新并通过订阅查询订阅结果.

#### Custom Scalars

- [graphql-scalars](https://github.com/Urigo/graphql-scalars) - 自定义 GraphQL 标量库，用于创建精确的类型安全 GraphQL 模式.

#### Type

- [type-graphql](https://github.com/19majkel94/type-graphql) - 使用类和装饰器，使用 TypeScript 创建 GraphQL 模式和解析器！
- [graphql-nexus](https://github.com/graphql-nexus/nexus) - 代码优先、类型安全、GraphQL 架构构建.
- [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator)：GraphQL 代码生成器，灵活支持自定义插件和模板，如 TypeScript（前端和后端）、React Hooks、解析器签名等.
- [pothos](https://github.com/hayes/pothos)  - Pothos 是一个基于插件的 Typescript GraphQL 模式构建器. 它使得在 TypeScript 中构建 graphql 模式变得简单、快速和愉快.
- [fast-graphql](https://github.com/idurar/fast-graphql) - 用于 Node.js、Next.Js 和 Graphql Apollo 服务器的结构、组合解析器和合并架构定义的 Graphql 工具

#### Miscellaneous

- [graphql-tools](https://github.com/apollographql/graphql-tools) - 用于构建和维护 GraphQL-JS 服务器的工具库.
- [graphql-tag](https://github.com/apollographql/graphql-tag) - 解析 GraphQL 查询的 JavaScript 模板文字标签.
- [graphql-compose](https://github.com/graphql-compose/graphql-compose) - 允许您通过插件从不同数据源构建灵活的 graphql 模式的工具.
- [graphql-modules](https://github.com/Urigo/graphql-modules) - 按模块或功能将 GraphQL 服务器分成更小的、可重用的部分.
- [graphql-shield](https://github.com/maticzav/graphql-shield) - 一个帮助为 graphql api 创建权限层的库.
- [graphql-shield-generator](https://github.com/omar-dulaimi/graphql-shield-generator) - 从您的 GraphQL 模式发出 GraphQL Shield.
- [graphqlgate](https://github.com/oslabs-beta/GraphQL-Gate) - 具有 Node.js 查询复杂性分析功能的 GraphQL 速率限制库
- [graphql-let](https://github.com/piglovesyou/graphql-let) - 一个 webpack 加载器，用于直接从 GraphQL 文档导入受类型保护的代码生成结果
- [graphql-config](https://github.com/kamilkisiela/graphql-config) - 所有 GraphQL 工具的一种配置（大多数工具、编辑器和 IDE 支持）.
- [graphql-cli](https://github.com/urigo/graphql-cli) - 用于常见 GraphQL 开发工作流程的命令行工具.
- [graphql-toolkit](https://github.com/ardatan/graphql-toolkit) - 一组用于更快开发 GraphQL 工具的实用程序（架构和文档加载、架构合并等）.
- [graphql-mesh](https://github.com/urigo/graphql-mesh) - 使用 GraphQL 查询语言访问不运行 GraphQL 的远程 API（以及运行 GraphQL 的远程 API）中的数据.
- [sofa](https://github.com/Urigo/sofa) - 从 GraphQL API 生成 REST API.
- [graphback](https://github.com/aerogear/graphback) - 使用数据模型将 GraphQLCRUD API 层添加到 GraphQL 服务器的框架和 CLI.
- [graphql-middleware](https://github.com/maticzav/graphql-middleware) - 在中间件函数中拆分 GraphQL 解析器.
- [graphql-relay-js](https://github.com/graphql/graphql-relay-js) - 一个帮助构建支持react-relay的graphql-js服务器的库.
- [graphql-normalizr](https://github.com/monojack/graphql-normalizr) - 标准化 GraphQL 响应以持久保存在客户端缓存/状态中.
- [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql) - 编译 GraphQL 标记模板字符串的 Babel 插件.
- [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) - 一个 ESLint 插件，用于根据架构检查 GraphQL 字符串.
- [graphql-ws](https://github.com/enisdenjo/graphql-ws) - 连贯、零依赖、惰性、简单、基于 WebSocket 协议的 GraphQL 兼容服务器和客户端.
- [graphql-live-query](https://github.com/n1ru4l/graphql-live-query) - 使用 JavaScript 进行实时 GraphQL 实时查询.
- [GraphVinci](https://github.com/Comcast/graphvinci) - GraphQL API 的交互式模式可视化工具.
- [supertest-graphql](https://github.com/alexstrat/supertest-graphql) - 延伸 [supertest](https://github.com/visionmedia/supertest) 轻松测试 GraphQL 端点
- [schemathesis](https://github.com/schemathesis/schemathesis) - 运行与 GraphQL 模式匹配的任意查询以查找服务器错误.
- [microfiber](https://github.com/anvilco/graphql-introspection-tools) - 以有用的方式查询和操作 GraphQL 内省查询结果.
- [graphql-armor](https://github.com/Escape-Technologies/graphql-armor) - 用于生产 GraphQL 端点的即时安全层.
- [GraphQL Constraint Directive](https://github.com/confuser/graphql-constraint-directive)  - 允许使用@constraint 作为指令来验证输入数据. 受到约束指令 RFC 和 OpenAPI 的启发
- [Validator.js Wrapper Directive](https://github.com/ktutnik/graphql-directive/tree/master/packages/validator) - 验证器指令的完整列表包含 Validator.js 功能

<a name="js-example" />

#### JavaScript Examples

- [React Starter Kit](https://github.com/kriasoft/react-starter-kit) - 使用 React、Relay、GraphQL 和 JAM 堆栈架构的前端入门套件.
- [SWAPI GraphQL Wrapper](https://github.com/graphql/swapi-graphql) - GraphQL 模式和服务器包装 SWAPI.
- [Relay TodoMVC](https://github.com/taion/relay-todomvc) - 使用路由中继 TodoMVC.
- [Apollo Client documentation](https://www.apollographql.com/react/) - 使用 apollo 客户端构建 GraphQL 应用程序的文档和示例.
- [Apollo Server tools documentation](https://www.apollographql.com/docs/apollo-server/) - 用于构建 GraphQL 服务器以及连接到 SQL、MongoDB 和 REST 端点的文档、教程和示例.
- [F8 App 2017](https://github.com/fbsamples/f8app) - 2016 年官方 F8 应用程序的源代码，由 React Native 和其他 Facebook 开源项目提供支持.
- [Apollo React example for Github GraphQL API](https://github.com/katopz/react-apollo-graphql-github-example) - 使用示例 Apollo React for Github GraphQL API 和 create-react-app.
- [Next.js TypeScript and GraphQL Example](https://github.com/zeit/next.js/tree/canary/examples/with-typescript-graphql) - Next.js 上运行的受类型保护的 GraphQL 示例 [graphql-codegen](https://graphql-code-generator.com/) 在引擎盖下
- [GraphQL StackBlitz Starter](https://stackblitz.com/fork/graphql) – 一个实时、可编辑的演示，大约 2 秒内即可启动并在浏览器中运行.
- [NAPERG](https://github.com/alan345/naperg)  - 全栈样板 GraphQL. 使用 React 和 Prisma + 身份验证和角色制成.
- [VulcanJS](http://vulcanjs.org) - 全栈React+GraphQL框架
- [RAN Toolkit](https://github.com/sly777/ran) - 生产就绪的工具包/样板，支持 GraphQL、SSR、热重载、CSS-in-JS、缓存等.

<a name="ts-example" />

#### TypeScript Examples

- [Node.js API Starter](https://github.com/kriasoft/nodejs-api-starter) - 基于 Yarn v2 的 monorepo 模板（代码优先 GraphQL API、PostgreSQL、PnP、零安装、无服务器）.
- [Next.js Apollo TypeScript Starter](https://github.com/borisowsky/nextjs-apollo-ts-starter) - Next.js 入门项目专注于开发人员体验.
- [GraphQL Starter](https://github.com/cerino-ligutom/GraphQL-Starter) - TypeScript + Node Express + Apollo GraphQL API 的样板.
- [Mocked Managed Federation - Apollo Server 3](https://github.com/setchy/apollo-server-3-mocked-federation) - 如何使用 Apollo Server 3.x 模拟托管联合 Supgraph 的示例
- [Mocked Managed Federation - Apollo Server 4](https://github.com/setchy/apollo-server-4-mocked-federation) - 如何使用 Apollo Server 4.x 模拟托管联合 Supgraph 的示例
- [Next.js Advanced Graphql Crud MongoDB Starter](https://github.com/idurar/starter-advanced-graphql-crud-next-js-mongodb) - 使用带有 Next.js 和 Mongodb (TypeScript) 的高级 Apollo Graphql 服务器启动通用 CRUD

<a name="rb" />

### Ruby

- [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) - Facebook GraphQL 的 Ruby 实现.
- [graphql-client](https://github.com/github/graphql-client) - 用于声明、编写和执行 GraphQL 查询的 Ruby 库.
- [graphql-batch](https://github.com/Shopify/graphql-batch) - graphql gem 的查询批处理执行器.
- [graphql-auth](https://github.com/o2web/graphql-auth) - 与设备一起使用的 JWT 身份验证包装器.
- [agoo](https://github.com/ohler55/agoo) - 实现 Facebook GraphQL 的 Ruby Web 服务器.
- [GQLi](https://github.com/contentful-labs/gqli.rb)  - GraphQL 客户端和 DSL. 允许用本机 Ruby 编写查询.

<a name="rb-example" />

#### Ruby Examples

- [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo) - 使用 graphql-ruby 公开 Rails 应用程序.
- [github-graphql-rails-example](https://github.com/github/github-graphql-rails-example) - 使用 GitHub 的 GraphQL API 的示例 Rails 应用程序.
- [relay-on-rails](https://github.com/nethsix/relay-on-rails) - 用于带有 Rails GraphQL 服务器的 Relay 应用程序的 Barebones 入门套件.
- [relay-rails-blog](https://github.com/gauravtiwari/relay-rails-blog) - graphql、继电器和标准 Rails 应用程序支持的演示博客.
- [to_eat_app](https://github.com/jcdavison/to_eat_app) - 示例 graphql/rails/relay 应用程序以及相关的 3 部分文章系列.
- [agoo-demo](https://github.com/ohler55/agoo/tree/develop/example/graphql) - 使用 Agoo 服务器演示简单的 GraphQL 应用程序.
- [rails-devise-graphql](https://github.com/zauberware/rails-devise-graphql) - 带有设计、graphql 和 JWT auth 的 Rails 6 样板.

<a name="php" />

### PHP

- [graphql-php](https://github.com/webonyx/graphql-php) - GraphQL 参考实现的 PHP 端口.
- [graphql-relay-php](https://github.com/ivome/graphql-relay-php) - GraphQL 的 webonyx/graphql-php 实现的中继助手.
- [lighthouse](https://github.com/nuwave/lighthouse) - 一个 PHP 包，允许从 Laravel 应用程序提供 GraphQL 端点.
- [graphql-laravel](https://github.com/rebing/graphql-laravel) - Facebook GraphQL 的 Laravel 包装器.
- [overblog/graphql-bundle](https://github.com/overblog/GraphQLBundle)  - 该捆绑包提供了在 Symfony 应用程序中构建完整 GraphQL 服务器的工具. 支持反应中继.
- [wp-graphql](https://github.com/wp-graphql/wp-graphql) - 适用于 WordPress 的 GraphQL API.
- [graphqlite](https://github.com/thecodingmachine/graphqlite) - 与框架无关的库，允许您通过注释 PHP 类来编写 GraphQL 服务器.
- [siler](https://github.com/leocavalcante/siler) - 普通的旧函数为具有订阅支持的 GraphQL 服务器提供声明性 API.
- [graphql-request-builder](https://github.com/dpauli/php-graphql-request-builder) - 在 GraphQL 结构中构建请求负载.
- [drupal/graphql](https://www.drupal.org/project/graphql) - 为 Drupal 8+ 制作并公开 GraphQL 架构.

<a name="php-example" />

#### PHP Examples

- [siler-graphgl](https://github.com/leocavalcante/siler/tree/main/examples/graphql) - 使用 Siler 编写的 GraphQL 服务器示例.

<a name="py" />

### Python

- [graphql-parser](https://github.com/tryolabs/graphql-parser) - Python 的 GraphQL 解析器.
- [graphql-core](https://github.com/graphql-python/graphql-core) - 基于 GraphQL.js v16.3.0 参考实现的 Python GraphQL 实现
- [graphql-relay-py](https://github.com/graphql-python/graphql-relay-py) - 一个帮助构建支持react-relay的graphql-py服务器的库.
- [graphql-parser-python](https://github.com/tallstreet/graphql-parser-python) - libgraphqlparser 的 python 包装器.
- [graphene](https://github.com/graphql-python/graphene) - 用于以 Python 的简单方式创建 GraphQL 模式/类型的包.
- [graphene-gae](https://github.com/graphql-python/graphene-gae) - 向 Google AppEngine (GAE) 添加 GraphQL 支持.
- [django-graphiql](https://github.com/GraphQL-python-archive/django-graphiql) - 将 GraphiQL 轻松集成到您的 Django 项目中.
- [flask-graphql](https://github.com/graphql-python/flask-graphql) - 向您的 Flask 应用程序添加 GraphQL 支持.
- [python-graphql-client](https://github.com/prisma/python-graphql-client) - 适用于 Python 2.7+ 的简单 GraphQL 客户端
- [python-graphjoiner](https://github.com/healx/python-graphjoiner) - 使用联接、SQL 或其他方式创建 GraphQL API.
- [graphene-django](https://github.com/graphql-python/graphene-django) - 石墨烯的 Django 集成.
- [Flask-GraphQL-Auth](https://github.com/callsign-viper/Flask-GraphQL-Auth) - Flask 的身份验证库，灵感来自 Flask-jwt-extended.
- [tartiflette](https://github.com/dailymotion/tartiflette) - GraphQL 实现，SDL First，适用于 python 3.6+ / asyncio.
- [tartiflette-aiohttp](https://github.com/dailymotion/tartiflette-aiohttp) - Tartiflette 的包装器，基于 aiohttp / 3.6+ / asyncio 通过 HTTP 公开 GraphQL API， [official tutorial available on tartiflette.io](https://tartiflette.io/docs/tutorial/getting-started).
- [Ariadne](https://github.com/mirumee/ariadne)  - 使用模式优先方法实现 GraphQL 服务器的库. 异步查询执行，包括 ASGI、WSGI 和流行的 Web 框架的电池， [fully documented](https://ariadnegraphql.org).
- [django-graphql-auth](https://github.com/PedroBern/django-graphql-auth) - 使用 GraphQL 进行 Django 注册和身份验证.
- [strawberry](https://github.com/strawberry-graphql/strawberry) - 一个新的 Python GraphQL 库.
- [turms](https://github.com/jhnnsrs/turms) - 围绕 graphql-core 和 pydantic 构建的 pythonic graphql 代码生成器
- [rath](https://github.com/jhnnsrs/rath) - 类似 apollo 的 graphql 客户端，具有异步和同步接口
- [sgqlc](https://github.com/profusion/sgqlc) - 简单的 GraphQL 客户端使得在 Python 中使用 GraphQL API 响应变得更加容易.

<a name="py-example" />

#### Python Examples

- [swapi-graphene](https://github.com/graphql-python/swapi-graphene) - A GraphQL schema and server using [Graphene](https://graphene-python.org).
- [Python Backend Tutorial](https://hasura.io/learn/graphql/backend-stack/languages/python/) - 有关创建 GraphQL 服务器的教程 [Strawberry](https://strawberry.rocks/) 和一个客户 [Qlient](https://qlient-org.github.io/python-qlient/site/).

<a name="java" />

### Java

- [graphql-java](https://github.com/graphql-java/graphql-java) - GraphQL Java 实现.
- [DGS Framework](https://github.com/Netflix/dgs-framework) - Spring Boot 的 GraphQL 服务器框架，由 Netflix 开发.
- [graphql-java-generator](https://github.com/graphql-java-generator) - A [Maven plugin](https://github.com/graphql-java-generator/graphql-maven-plugin-project) 和一个 [Gradle plugin](https://github.com/graphql-java-generator/graphql-gradle-plugin-project) 可以生成**客户端**和**服务器**（POJO 和实用程序类）. 服务器部分基于graphql-java，并隐藏其所有样板代码.
- [gaphql-java-type-generator](https://github.com/graphql-java/graphql-java-type-generator) - 自动生成与 GraphQL Java 一起使用的类型
- [schemagen-graphql](https://github.com/bpatters/schemagen-graphql)  - 模式生成和执行包，将 POJO 转换为 GraphQL Java 可查询对象集. 允许使用注释将任何服务公开为 GraphQL 服务.
- [graphql-java-annotations](https://github.com/Enigmatis/graphql-java-annotations) - 使用 GraphQL Java 为模式定义提供基于注释的语法.
- [graphql-java-tools](https://github.com/graphql-java-kickstart/graphql-java-tools) - Schema-first graphql-java convenience library that makes it easy to bring your own implementations as data resolvers. Inspired by [graphql-tools](https://github.com/apollographql/graphql-tools) 对于JS.
- [graphql-java-codegen-maven-plugin](https://github.com/kobylynskyi/graphql-java-codegen-maven-plugin)  - 用于生成 Java 类型和解析器接口的模式优先 Maven 插件. 与 graphql-java-tools 完美结合. 灵感来自 [swagger-codegen-maven-plugin](https://github.com/swagger-api/swagger-codegen/tree/master/modules/swagger-codegen-maven-plugin).
- [graphql-java-codegen-gradle-plugin](https://github.com/kobylynskyi/graphql-java-codegen-gradle-plugin)  - 用于生成 Java 类型和解析器接口的模式优先 gradle 插件. 与 graphql-java-tools 完美结合. 灵感来自 [gradle-swagger-generator-plugin](https://github.com/int128/gradle-swagger-generator-plugin).
- [graphql-java-servlet](https://github.com/graphql-java-kickstart/graphql-java-servlet) - 一个与框架无关的 java servlet，用于通过 GET、POST 和分段上传公开 graphql-java 查询端点.
- [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql)  - 全面的 GraphQL 客户端使用. 模式优先. 类型安全的 GraphQL 类型、查询和结果，没有代码生成器、没有 POJO、没有注释. 出色 [IDE support](http://manifold.systems/images/graphql.mp4) 使用 IntelliJ IDEA 和 Android Studio. 请参阅 [Java example](#example-java) 以下.
- [spring-graphql-common](https://github.com/oembedler/spring-graphql-common) - Spring 框架 GraphQL 库.
- [graphql-spring-boot](https://github.com/graphql-java-kickstart/graphql-spring-boot) - GraphQL 和 GraphiQL Spring 框架启动启动器.
- [vertx-graphql-service-discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - 异步 GraphQL 服务发现和查询微服务.
- [vertx-dataloader](https://github.com/engagingspaces/vertx-dataloader) - Facebook DataLoader 的端口，用于在集群 GraphQL 环境中进行高效、异步批处理和缓存.
- [graphql-spqr](https://github.com/leangen/GraphQL-SPQR) - 用于快速开发 GraphQL 服务的 Java 8+ API.
- [Light Java GraphQL](https://github.com/networknt/light-graphql-4j)：一个轻量级、快速的微服务框架，解决了所有横切问题并准备插入 GraphQL 模式.
- [Elide](https://elide.io)：一个 Java 库，可以将 JPA 带注释的数据模型公开为任何关系数据库上的 GraphQL 服务.
- [federation-jvm](https://github.com/apollographql/federation-jvm) - JVM 上的 Apollo Federation.
- [graphql-orchestrator-java](https://github.com/graph-quilt/graphql-orchestrator-java) GraphQL Orchestrator/网关库，支持架构缝合和 Apollo Federation 指令，将多个 GraphQL 微服务的架构组合成一个统一的架构.
- [graphql-java-extended-validation](https://github.com/graphql-java/graphql-java-extended-validation) - 为 graphql-java 提供字段和字段参数的扩展验证.
- [dgs-extended-formatters](https://github.com/setchy/dgs-extended-formatters) - 用于常见格式化用例的一组实验性 DGS 指令.

#### Custom Scalars

- [graphql-java-datetime](https://github.com/donbeave/graphql-java-datetime) - GraphQL ISO Date 是一组与 graphql-java 一起使用的符合 RFC 3339 的日期/时间标量类型.
- [graphql-java-extended-scalars](https://github.com/graphql-java/graphql-java-extended-scalars) - graphql-java 的扩展标量.

<a name="java-example" />

#### Java Examples

- [light-java-graphql examples](https://github.com/networknt/light-example-4j/tree/master/graphql) - Light Java GraphQL 示例和教程.
- [graphql-spqr-samples](https://github.com/leangen/graphql-spqr-samples) - 使用 Spring MVC 和 GraphQL-SPQR 编写的示例 GraphQL 服务器.
- [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-graphql-app) - 一个简单的应用程序，包括客户端和服务器，演示了 Manifold GraphQL 库.
- [graphql-java-kickstart_samples](https://github.com/graphql-java-kickstart/samples) - 使用 GraphQL Java Kickstart 项目的示例.
- [graphql-java-kickstart-federation-example](https://github.com/setchy/graphql-java-kickstart-federation-example) - GraphQL Java Kickstart 联合示例.
- [dgs-federation-example](https://github.com/Netflix/dgs-federation-example) - Netflix DGS 联合示例.
- [Spring Boot backend tutorial](https://hasura.io/learn/graphql/backend-stack/languages/java/) - 使用 Spring Boot 和 Netflix DGS 创建 GraphQL 服务器和客户端的教程.

<a name="kotlin" />

### Kotlin

- [graphql-kotlin](https://github.com/ExpediaGroup/graphql-kotlin) - GraphQL Kotlin 实现.
- [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql)  - 全面的 GraphQL 客户端使用. 模式优先. 类型安全的 GraphQL 类型、查询和结果，没有代码生成器、没有 POJO、没有注释. 出色 [IDE support](http://manifold.systems/images/graphql.mp4) 使用 IntelliJ IDEA 和 Android Studio. 请参阅 [Kotlin example](#example-kotlin) 以下.
- [KGraphQL](https://github.com/aPureBase/KGraphQL)：用于设置 GraphQL 服务器的纯 Kotlin 实现.
- [Kobby](https://github.com/ermadmi78/kobby) - Codegen插件 [Kotlin DSL Client](https://blog.kotlin-academy.com/how-to-generate-kotlin-dsl-client-by-graphql-schema-707fd0c55284) 通过 GraphQL 模式. 生成的 DSL 支持在 Kotlin 中执行复杂的 GraphQL 查询、突变和订阅，其语法类似于原生 GraphQL 语法.
- [Graphkt](https://github.com/cufyorg/graphkt) - 一个基于 DSL 的 kotlin graphql 服务器库，由 graphql-java 支持.

<a name="kotlin-example" />

#### Kotlin Examples

- [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-kotlin-app) - 一个简单的 GraphQL 应用程序（客户端和服务器），使用 Kotlin 演示 Manifold GraphQL 库.

<a name="c" />

### C/C++

- [libgraphqlparser](https://github.com/graphql/libgraphqlparser) - C++ 中的 GraphQL 查询解析器，具有 C 和 C++ API.
- [agoo-c](https://github.com/ohler55/agoo-c) - 用 C 编写的高性能 GraphQL 服务器. [benchmarks](https://github.com/the-benchmarker/graphql-benchmarks)
- [cppgraphqlgen](https://github.com/Microsoft/cppgraphqlgen) - C++ GraphQL 模式服务生成器.
- [CaffQL](https://github.com/caffeinetv/CaffQL) - 从 GraphQL 内省查询生成 C++ 客户端类型和请求/响应序列化.

<a name="go" />

### Go

- [graphql](https://github.com/graphql-go/graphql) - GraphQL for Go 的实现遵循 graphql-js
- [graphql-go](https://github.com/graph-gophers/graphql-go) - 注重易用性的 GraphQL 服务器.
- [gqlgen](https://github.com/99designs/gqlgen) - 生成基于 graphql 服务器库.
- [graphql-relay-go](https://github.com/graphql-go/relay) - 一个 Go/Golang 库，可帮助构建支持 React-relay 的服务器.
- [graphjin](https://github.com/dosco/graphjin) ：使用 GraphQL 在 5 分钟内构建 API. 即时 GraphQL 到 SQL 编译器.

<a name="go-example" />

#### Go Examples

- [golang-relay-starter-kit](https://github.com/sogko/golang-relay-starter-kit) - 使用 Golang GraphQL 服务器的 Relay 应用程序的准系统起点.
- [todomvc-relay-go](https://github.com/sogko/todomvc-relay-go) - React/Relay TodoMVC 应用程序的端口，由 Golang GraphQL 后端驱动.
- [go-graphql-subscription-example](https://github.com/ccamel/go-graphql-subscription-example) - 演示 GraphQL 的 GraphQL 模式和服务器 [subscriptions](https://github.com/apollographql/subscriptions-transport-ws/blob/v0.9.4/PROTOCOL.md) （通过Websocket）消费 [Apache Kafka](https://kafka.apache.org/) 消息.
- [Go Backend Tutorial](https://hasura.io/learn/graphql/backend-stack/languages/go/) - 展示如何使用代码生成来制作 Go GraphQL 服务器和客户端的教程.

<a name="scala" />

### Scala

- [sangria](https://github.com/sangria-graphql/sangria) - Scala GraphQL 服务器实现.
- [sangria-relay](https://github.com/sangria-graphql/sangria-relay) - 桑格利亚汽酒中继支持.
- [caliban](https://github.com/ghostdogpr/caliban) - Caliban 是一个纯函数库，用于在 Scala 中创建 GraphQL 后端.

<a name="scala-example" />

#### Scala Examples

- [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example) - 使用 akka-http 编写的示例 GraphQL 服务器和 [sangria](https://sangria-graphql.github.io/)
- [sangria-playground](https://github.com/sangria-graphql/sangria-playground) - 使用 Play 和 sangria 编写的 GraphQL 服务器示例.

<a name="dotnet" />

### .NET

- [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - .NET 的 GraphQL.
- [graphql-net](https://github.com/ckimes89/graphql-net) - GraphQL 到 IQueryable for .NET.
- [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) - 适用于 .Net Core 和 .NET Framework 的 GraphQL 服务器.
- [Snowflaqe](https://github.com/Zaid-Ajaj/Snowflaqe) - Type-safe GraphQL code generator for F# and [Fable](https://github.com/fable-compiler/Fable)
- [EntityGraphQL](https://github.com/EntityGraphQL/EntityGraphQL) - 在数据模型之上构建 GraphQL API 的库，具有可扩展性，可将多个数据源整合到单个 GraphQL 架构中.
- [ZeroQL](https://github.com/byme8/ZeroQL) - 类型安全的 GraphQL 客户端，具有类似 Linq 的 C 接口#

<a name="net-example" />

#### .NET Examples

- [.NET backend tutorial](https://hasura.io/learn/graphql/backend-stack/languages/dotnet/) - 使用 .NET 创建 GraphQL 服务器和客户端的教程.

<a name="elixir" />

### Elixir

- [absinthe-graphql](https://github.com/absinthe-graphql/absinthe) - 功能齐全的 Elixir GraphQL 库.
- [graphql-elixir](https://github.com/graphql-elixir/graphql)  - GraphQL Elixir.  （不再维护）
- [plug_graphql](https://github.com/graphql-elixir/plug_graphql) - GraphQL Elixir 的插件集成.
- [graphql_relay](https://github.com/graphql-elixir/graphql_relay) - GraphQL Elixir 的中继助手.
- [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - Elixir 绑定 [libgraphqlparser](https://github.com/graphql/libgraphqlparser)
- [graphql](https://github.com/asonge/graphql) - Elixir GraphQL 解析器.
- [plot](https://github.com/peburrows/plot) - Elixir 的 GraphQL 解析器和解析器.

<a name="elixir-example" />

#### Elixir Examples

- [hello_graphql_phoenix](https://github.com/graphql-elixir/hello_graphql_phoenix) - Phoenix 中安装的 GraphQL Elixir Plug 端点示例

<a name="haskell" />

### Haskell

- [graphql-haskell](https://github.com/jdnavarro/graphql-haskell) - 用于 Haskell 的 GraphQL AST 和解析器.
- [morpheus-graphql](https://github.com/morpheusgraphql/morpheus-graphql) - Haskell GraphQL Api、客户端和工具.

<a name="sql" />

### SQL

- [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL) - 用于 Postgres 的 GraphQL.
- [sql-to-graphql](https://github.com/rexxars/sql-to-graphql) - 根据您的 SQL 数据库结构生成 GraphQL API.
- [PostGraphile](https://github.com/graphile/postgraphile)  - 用于 PostgreSQL 的闪电般的 GraphQL API：高度可定制； 可通过插件扩展； 即时的.
- [Hasura](https://github.com/hasura/graphql-engine)  - Hasura 通过 PostgreSQL 提供即时实时 GraphQL API. 也适用于现有数据库.
- [subZero](https://subzero.cloud/) - 适用于您的数据库的 GraphQL 和 REST API

<a name="lua" />

### Lua

- [graphql-lua](https://github.com/bjornbytes/graphql-lua) - Lua 的 GraphQL.

<a name="elm" />

### Elm

- [elm-graphql](https://github.com/dillonkearns/elm-graphql) -Elm 的 GraphQL.

<a name="clojure" />

### Clojure

- [graphql-clj](https://github.com/tendant/graphql-clj) - 旨在提供 GraphQL 实现的 Clojure 库.
- [Lacinia](https://github.com/walmartlabs/lacinia) - 纯 Clojure 中的 GraphQL 实现.
- [graphql-query](https://github.com/district0x/graphql-query) - Clojure（脚本）GraphQL 查询生成.

<a name="clojure-example" />

#### Clojure Examples

- [Clojure Game Geek](https://github.com/walmartlabs/clojure-game-geek) - Lacinia GraphQL 框架教程的示例代码.

<a name="swift" />

### Swift

- [GraphQL](https://github.com/GraphQLSwift/GraphQL) - GraphQL 的 Swift 实现.

<a name="ocaml" />

### OCaml

- [ocaml-graphql-server](https://github.com/andreas/ocaml-graphql-server) - OCaml 中的 GraphQL 服务器.

<a name="android" />

### Android

- [apollo-android](https://github.com/apollographql/apollo-android) - 适用于 Android 的强类型缓存 GraphQL 客户端，用 Java 编写.
- [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql)  - 全面的 GraphQL 客户端使用. 模式优先. 类型安全的 GraphQL 类型、查询和结果，没有代码生成器、没有 POJO、没有注释. 出色 [IDE support](http://manifold.systems/images/graphql.mp4) 使用 IntelliJ IDEA 和 Android Studio. 请参阅 [Java example](#example-java) 以下.

<a name="android-example" />

#### Android Examples

- [apollo-frontpage-android-app](https://github.com/rnitame/apollo-frontpage-android-app) - Apollo“hello world”应用程序，适用于 Android.

<a name="ios" />

### iOS

- [apollo-ios](https://github.com/apollographql/apollo-ios) - 适用于 iOS 的强类型缓存 GraphQL 客户端，用 Swift 编写.
- [ApolloDeveloperKit](https://github.com/manicmaniac/ApolloDeveloperKit) - 适用于 [Apollo iOS] 的 Apollo 客户端开发工具桥.
- [Graphaello](https://github.com/nerdsupremacist/Graphaello) - 直接从 SwiftUI 输入 Safe GraphQL.
- [GQLite iOS SDK](https://graphqlite.com/sdk-ios) - GQLite iOS SDK 是一个可以轻松使用 GraphQL 服务器的工具包.

<a name="ios-example" />

#### iOS Examples

- [frontpage-ios-app](https://github.com/apollographql/frontpage-ios-app) - Apollo“hello world”应用程序，适用于 iOS.

<a name="clojurescript" />

### ClojureScript

- [re-graph](https://github.com/oliyh/re-graph) - ClojureScript 的 GraphQL 客户端，具有用于重新构建应用程序的绑定.
- [graphql-query](https://github.com/district0x/graphql-query) - Clojure（脚本）GraphQL 查询生成.

<a name="reasonml" />

### ReasonML

- [reason-apollo](https://github.com/apollographql/reason-apollo) - Apollo 客户端的 ReasonML 绑定.
- [ReasonQL](https://github.com/sainthkh/reasonql) - 为 ReasonML 开发人员提供类型安全且简单的 GraphQL 客户端.
- [reason-urql](https://github.com/FormidableLabs/reason-urql) - urql 客户端的 ReasonML 绑定.

<a name="dart" />

### Dart

- [graphql-flutter](https://github.com/zino-app/graphql-flutter) - Flutter 的 GraphQL 客户端.
- [Artemis](https://github.com/comigor/artemis) - 用于 Dart/Flutter 的 GraphQL 类型和查询生成器.

<a name="rust" />

### Rust

- [async-graphql](https://github.com/async-graphql/async-graphql) - 支持所有 GraphQL 规范的高性能服务器端库.
- [juniper](https://github.com/graphql-rust/juniper) - Rust 的 GraphQL 服务器库.
- [graphql-client](https://github.com/tomhoule/graphql-client) - Rust 的 GraphQL 客户端库，支持 WebAssembly (wasm).
- [graphql-parser](https://github.com/graphql-rust/graphql-parser) - 用于 Rust 的 GraphQL 查询和模式定义语言的解析器、格式化程序和 AST.

<a name="rust-example" />

#### Rust Examples

- [Warp GraphQL Juniper Demo](https://github.com/graphql-rust/juniper/tree/master/examples/warp_async)

<a name="d" />

### D (dlang)

- [graphqld](https://github.com/burner/graphqld) - D 的 GraphQL 服务器库

<a name="r" />

### R (Rstat)

- [ghql](https://github.com/ropensci/ghql) - 通用 GraphQL R 客户端.
- [graphql](https://github.com/ropensci/graphql)  - 绑定到“libgraphqlparser”C++ 库. 解析 GraphQL 语法并以 JSON 格式导出 AST.
- [gqlr](https://github.com/schloerke/gqlr) - R GraphQL 实现.

<a name="julia" />

### Julia

- [Diana.jl](https://github.com/codeneomatrix/Diana.jl) - Julia GraphQL 客户端/服务器实现.
- [GraphQLClient.jl](https://github.com/DeloitteDigitalAPAC/GraphQLClient.jl) - A Julia GraphQL client for seamless integration with a server.

<a name="crystal" />

### Crystal

- [graphql](https://github.com/graphql-crystal/graphql) - GraphQL 服务器库.
- [graphql-crystal](https://github.com/ziprandom/graphql-crystal) - 图书馆的灵感来自 [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) & [go-graphql](https://github.com/playlyfe/go-graphql) & [graphql-parser](https://github.com/graphql-dotnet/parser).
- [crystal-gql](https://github.com/itsezc/crystal-gql) - 受 Apollo 客户端启发的 GraphQL 客户端分片.
- [graphql.cr](https://github.com/garymardell/graphql.cr) - GraphQL 分片.

<a name="tools" />

## Tools

### Tools - Editors & IDEs & Explorers

- [GraphiQL](https://github.com/graphql/graphiql) - 用于探索 GraphQL 的浏览器内 IDE.
- [GraphQL Editor](https://github.com/graphql-editor/graphql-editor) - 可视化编辑器和 GraphQL IDE.
- [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager) - 将任何 GraphQL API 表示为交互式图表.
- [Altair GraphQL Client](https://github.com/altair-graphql/altair) - 适用于所有平台的漂亮且功能丰富的 GraphQL 客户端.
- [Brangr](https://github.com/networkimprov/brangr) - 适用于任何 GraphQL 服务的独特、用户友好的数据浏览器/查看器，具有有吸引力的结果布局.
- [Insomnia](https://insomnia.rest/) - 带有第一方 GraphQL 查询编辑器的全功能 API 客户端.
- [Postman](https://learning.postman.com/docs/sending-requests/supported-api-frameworks/graphql/) - 支持编辑 GraphQL 查询的 HTTP 客户端.
- [Escape GraphMan](https://github.com/Escape-Technologies/graphman) - 从 GraphQL 端点生成完整的 Postman 集合.
- [Apollo Sandbox](https://sandbox.apollo.dev/) - 导航和测试 GraphQL 端点的最快方法.
- [GraphQL Birdseye](https://github.com/Novvum/graphql-birdseye) – 将任何 GraphQL 模式视为动态交互式图表.
- [AST Explorer](https://astexplorer.net/) - 选择顶部的“GraphQL”，探索 GraphQL AST 并通过单击查询突出显示不同的部分.
- [Firecamp - GraphQL Playground](https://firecamp.io/graphql) - 最快的协作 GraphQL 游乐场.
- [CraftQL](https://github.com/yamafaktory/craftql) - 一个 CLI 工具，用于可视化 GraphQL 模式并将图形数据结构输出为 graphviz .dot 格式.
- [gqt](https://github.com/eerimoq/gqt) - 在终端中构建并执行 GraphQL 查询.
- [Graph Proxy](https://graphproxy.com/) - Graph Proxy 检测并显示所有 GraphQL 网络流量.

<a name="tool-testing" />

### Tools - Testing

- [Step CI](https://stepci.com) - 支持 GraphQL 的开源 API 测试和监控
- [graphql-to-karate](https://github.com/wbaldoumas/graphql-to-karate) - 从 GraphQL 模式生成空手道 API 测试

<a name="tool-security" />

### Tools - Security

- [GraphCrawler - The all-in-one GraphQL Security toolkit](https://github.com/gsmith257-cyber/GraphCrawler) - 用于 GraphQL 的一体化自动化渗透测试工具包，用 Python 编写
- [Escape - The GraphQL Security Scanner](https://graphql.security/)  - 对 GraphQL 端点进行一键安全扫描. 免费，无需登录.
- [Escape Graphinder - GraphQL Subdomain Enumeration](https://github.com/Escape-Technologies/graphinder) – 使用子域枚举、脚本分析和暴力破解的超快 GraphQL 端点查找器.
- [StackHawk - GraphQL Vulnerability Scanner](https://www.stackhawk.com/blog/automated-graphql-security-testing) - [StackHawk](https://www.stackhawk.com)
- [Tinfoil Security - GraphQL Security Scanner](https://www.tinfoilsecurity.com/blog/graphql-security-scanning) - [Tinfoil Security](https://www.tinfoilsecurity.com/solutions/api-scanner)
- [InQL Scanner](https://github.com/doyensec/inql) - 用于 GraphQL 安全测试的 Burp 扩展
- [GraphQL Raider](https://portswigger.net/bappstore/4841f0d78a554ca381c65b26d48207e6) [BurpSuite](https://portswigger.net/burp)
- [WAF for graphQL](https://lab.wallarm.com/api-security-solution/) - 用于 graphQL API 的 Web 应用程序防火墙
- [GraphQL Intruder](https://github.com/davinerd/gql_intruder) - 基于插件的 python 脚本来执行 GraphQL 漏洞评估.

### Tools - Browser Extensions

- [Apollo Client Developer Tools](https://github.com/apollographql/apollo-client-devtools) - Chrome 开发者控制台中 Apollo Client 的 GraphQL 调试工具
- [GraphQL Network Inspector](https://chrome.google.com/webstore/detail/graphql-network-inspector/ndlbedplllcgconngcnfmkadhokfaaln) - 一个简单干净的 chrome 开发工具扩展，用于 GraphQL 网络检查.

### Tools - Prototyping

- [GraphQL Faker](https://github.com/APIs-guru/graphql-faker)  - 使用伪造的数据模拟或扩展您的 GraphQL API. 无需编码.
- [GraphQL Designer](http://graphqldesigner.com/) - 开发人员的 Web 应用程序工具，可使用 React 快速构建 GraphQL 的全栈 CRUD 实现原型.

### Tools - Docs

- [graphdoc](https://github.com/2fd/graphdoc) - 用于记录 GraphQL 架构的静态页面生成器.
- [gqldoc](https://github.com/Code-Hex/gqldoc) - 为 GraphQL 制作 API 文档的最简单方法.
- [spectaql](https://github.com/anvilco/spectaql) - 自动生成静态 GraphQL API 文档.
- [graphql-markdown](https://graphql-markdown.github.io/) - 由 Docusaurus 提供支持的 GraphQL 的灵活文档.

### Tools - Editor Plugins

- [Apollo GraphQL VSCode Extension](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo) - 丰富的编辑器支持 GraphQL 客户端和服务器开发，与 Apollo 平台无缝集成
- [js-graphql-intellij-plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin/) - IntelliJ IDEA 和 WebStorm 的 GraphQL 语言支持，包括 JavaScript 和 TypeScript 中的 Relay.QL 标记模板.
- [vim-graphql](https://github.com/jparise/vim-graphql) - 一个 Vim 插件，提供 GraphQL 文件检测和语法突出显示.
- [Apollo Workbench](https://marketplace.visualstudio.com/items?itemName=apollographql.apollo-workbench) - 帮助您使用 Apollo Federation 开发和模拟联合模式的工具.
- [graphql-autocomplete](https://github.com/orionsoft/atom-graphql-autocomplete) - 来自 Atom 中 GraphQL 端点的自动完成和 lint.

### Tools - Miscellaneous

- [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator) - 基于模式和文档的 GraphQL 代码生成器.
- [swagger-to-graphql](https://github.com/yarax/swagger-to-graphql)  - 基于 Swagger 中描述的 REST API 的 GraphQL 类型构建器. 允许从 REST 迁移到 GraphQL 5 分钟
- [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin) - 语言服务插件完成并验证 TypeScript 模板字符串中的 GraphQL 查询.
- [apollo-tracing](https://github.com/apollographql/apollo-tracing) - GraphQL 扩展使您能够轻松获取解析器级别的性能信息作为 GraphQL 响应的一部分.
- [json-graphql-server](https://github.com/marmelab/json-graphql-server) - 基于 JSON 数据文件，在 30 秒内获得零编码的完整假 GraphQL API.
- [Prisma](https://github.com/prisma/prisma)  - 将您的数据库转变为 GraphQL API.  Prisma 可让您设计数据模型，并在几分钟内在线获得生产就绪的 GraphQL API.
- [Typetta](https://github.com/twinlogix/typetta)  - 用 TypeScript 为类型爱好者编写的 Node.js ORM.  Typetta 是 GraphQL + NodeJS + Typescript 堆栈的完美 ORM.
- [tuql](https://github.com/bradleyboy/tuql) - 从任何 sqlite 数据库自动创建 GraphQL 服务器.
- [Bit](https://github.com/teambit/bit) - 将 GraphQL API 组织为与 NPM 一起使用或从任何项目修改的组件， [example-explanation](https://hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1)).
- [openapi-to-graphql](https://github.com/ibm/openapi-to-graphql) - 采用任何 OpenAPI 规范 (OAS) 或 swagger 并创建 GraphQL 界面 - 两分钟的视频和资源 [here](https://developer.ibm.com/open/projects/openapi-to-graphql/)
- [Retool](https://retool.com/) – GraphQL API + GraphQL IDE 之上的内部工具构建器，带有模式浏览器.
- [dataloader-codegen](https://github.com/Yelp/dataloader-codegen) - 一个固执己见的 JavaScript 库，用于通过一组资源（例如 HTTP 端点）自动生成可预测的、类型安全的 DataLoader.
- [raphql-inspector](https://github.com/kamilkisiela/graphql-inspector)：验证架构、获取架构更改通知、验证操作、查找重大更改、查找相似类型、架构覆盖率.
- [amplication](https://github.com/amplication/amplication) ：Amplication 是一种开源低代码开发工具. 它使用 REST API 和 GraphQL 构建具有关系、排序、过滤、分页功能的 CRUD 数据库应用程序.
- [Blendbase](https://github.com/blendbase/blendbase) ：单个开源 GraphQL API，用于将 CRM 连接到您的 SaaS. 使用 SaaS 应用程序中的单个 API 查询来查询任何客户 CRM 系统（Salesforce、Hubspot 等）.
- [microfiber](https://github.com/anvilco/graphql-introspection-tools) - 以有用的方式查询和操作 GraphQL 内省查询结果.
- [ILLA Cloud](https://www.illacloud.com/) – 开源低代码工具构建平台提供了一种以最少配置与 GraphQL 集成的简单方法
- [DronaHQ](https://www.dronahq.com/) - 在几分钟内基于 GraphQL 数据构建内部工具、仪表板、管理面板
  <a name="databases" />

## Databases

- [Cube](https://cube.dev) - [Headless BI](https://cube.dev/blog/headless-bi) 用于使用 SQL、REST 和 [GraphQL API](https://cube.dev/docs/backend/graphql) . 连接任何数据库或数据仓库，立即获得具有亚秒级延迟的 GraphQL API.  - [Source Code](https://github.com/cube-js/cube.js)
- [Dgraph](https://dgraph.io/) - 可扩展、分布式、低延迟、高吞吐量的图形数据库，以 GraphQL 作为查询语言
- [EdgeDB](https://edgedb.com/) - 具有原生 GraphQL 支持的下一代对象关系数据库.
- [FaunaDB](https://fauna.com) - 关系型 NoSQL 数据库 [GraphQL schema import.](https://fauna.com/blog/getting-started-with-graphql-part-1-importing-and-querying-your-schema) 支持联接、索引和多区域 ACID 事务，采用无服务器按使用付费定价.
- [ArangoDB](https://arangodb.com/) - 原生多模型数据库 [GraphQL integration](https://www.arangodb.com/docs/3.4/foxx-reference-modules-graph-ql.html) 通过内置 [Foxx Microservices Framework](https://www.arangodb.com/docs/stable/foxx.html).
- [Weaviate](https://github.com/semi-technologies/weaviate) - Weaviate 是一个云原生、模块化、实时矢量搜索引擎，具有 [GraphQL interface](https://weaviate.io/developers/weaviate/api/graphql) 旨在扩展您的机器学习模型.
- [LunaSec](https://www.lunasec.io/) - 用于加密/标记敏感数据的键值数据库 [GraphQL support](https://www.lunasec.io/docs/pages/getting-started/dedicated-tokenizer/graphql/) 授权请求.  - [Source Code](https://github.com/lunasec-io/lunasec)

<a name="services" />

## Services

- [AWS AppSync](https://aws.amazon.com/appsync/) - 可扩展的托管 GraphQL 服务，具有用于构建实时和离线优先应用程序的订阅
- [FakeQL](https://fakeql.com/) - GraphQL API 模拟作为服务...因为 GraphQL API 模拟应该很容易！
- [Moesif API Analytics](https://www.moesif.com/features/graphql-analytics) - GraphQL 分析和监控服务，用于查找功能和性能问题.
- [Booster framework](https://booster.cloud/)  - 一个开源框架，让您_完全_忘记基础设施，并允许您专注于您的业务逻辑. 它会为您的模型自动生成 GraphQL API，支持突变、查询和订阅.
- [Hypi](https://hypi.io/)  - 低代码、可扩展、无服务器后端即服务. 只需几分钟即可通过 GraphQL 后端完成 GraphQL 和 REST.
- [Nhost](https://nhost.io/) - 使用 GraphQL 的开源 Firebase 替代品
- [Saleor](https://github.com/mirumee/saleor/) - GraphQL-第一个无头电子商务平台.
- [Stargate](https://stargate.io/docs/latest/quickstart/qs-graphql-cql-first.html) - 开源数据网关目前支持 Apache Cassandra® 和 DataStax Enterprise.
- [Grafbase](https://grafbase.com) - 适用于任何数据源的即时 GraphQL API.

### CDN

- [GraphCDN](https://graphcdn.io/) - 用于缓存 GraphQL API 的 GraphQL CDN.

### CMS

- [DatoCMS](https://www.datocms.com/) - 基于 CDN 的 GraphQL 无头内容管理系统.
- [Apito](https://apito.io/) - 基于云的无头 CMS，具有 CDN、Webhooks、团队协作、内容修订、云功能.
- [GraphCMS](https://graphcms.com/) - 基于 GraphQL 的无头内容管理系统.
- [Cosmic](https://www.cosmicjs.com/) - GraphQL 支持的 Headless CMS 和 API 工具包.

<a name="book" />

## Books

- [The GraphQL Guide](https://graphql.guide) 作者：约翰·雷西格和洛伦·桑兹·拉姆肖
- [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) by Bruce Williams and Ben Wilson
- [The Road to GraphQL](https://www.roadtographql.com/)
- [Learning GraphQL and Relay](https://www.packtpub.com/web-development/learning-graphql-and-relay) 通过萨梅尔·布纳
- [Practical GraphQL](https://leanpub.com/book-graphql) 丹尼尔·施密茨
- [Production Ready GraphQL](https://book.productionreadygraphql.com) 作者：马克·安德烈·吉鲁
- [Full Stack GraphQL Applications](https://www.manning.com/books/fullstack-graphql-applications) 威廉·里昂

<a name="video" />

## Videos

- [GraphQL: The Documentary](https://www.youtube.com/watch?v=783ccP__No8)
- [Zero to GraphQL in 30 Minutes](https://www.youtube.com/embed/UBGzsb2UkeY)
- [Data fetching for React applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU)
- [React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU)
- [Exploring GraphQL](https://www.youtube.com/watch?v=WQLzZf34FJ8)
- [Creating a GraphQL Server](https://www.youtube.com/watch?v=gY48GW87Feo)
- [GraphQL at The Financial Times](https://www.youtube.com/watch?v=S0s935RKKB4)
- [Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg)
- [Building and Deploying Relay with Facebook](https://www.youtube.com/watch?t=643&v=Pxdgu2XIAAg)
- [Introduction to GraphQL](https://vimeo.com/144817545)
- [Exploring GraphQL@Scale](https://www.youtube.com/watch?v=_9RgHXqH8J0)
- [What's Next for Phoenix by Chris McCord](https://www.youtube.com/watch?v=IMUpYOc9z3c&feature=youtu.be)
- [GraphQL with Nick Schrock](https://www.youtube.com/watch?v=Ed6oJXKt3-M)
- [Build a GraphQL server for Node.js using PostgreSQL/MySQL](https://www.youtube.com/watch?v=DNPVqK_woRQ)
- [GraphQL server tutorial for Node.js with SQL, MongoDB and REST](https://www.youtube.com/watch?v=PHabPhgRUuU)
- [JavaScript Air Episode 023: Transitioning from REST to GraphQL](https://www.youtube.com/watch?v=ENqDNIp1Nd8)
- [GraphQL Future at react-europe 2016](https://www.youtube.com/watch?v=ViXL0YQnioU)
- [GraphQL at Facebook at react-europe 2016](https://www.youtube.com/watch?v=etax3aEe2dA)
- [Building native mobile apps with GraphQL at react-europe 2016](https://www.youtube.com/watch?v=z5rz3saDPJ8)
- [Build a GraphQL Server](https://www.youtube.com/watch?v=PEcJxkylcRM&list=PLillGF-RfqbYZty73_PHBqKRDnv7ikh68)
- [GraphQL Tutorial](https://www.youtube.com/watch?v=Y0lDGjwRYKw&list=PL4cUxeGkcC9iK6Qhn-QLcXCXPQUov1U7f)
- [Five years of GraphQL](https://www.youtube.com/watch?v=s8meG38iZAM)
- [GraphQL is for Everyone by Moon Highway](https://moonhighway.teachable.com/p/graphql-is-for-everyone)

<a name="podcast" />

## Podcasts

- [GraphQL.FM](https://podcasts.google.com/feed/aHR0cHM6Ly9hbmNob3IuZm0vcy8zNjE5NmViMC9wb2RjYXN0L3Jzcw==) 作者：马克·安德烈·吉鲁和托尼·吉塔.

<a name="style-guide" />

## Style Guides

- [Shopify GraphQL Design Tutorial](https://github.com/Shopify/graphql-design-tutorial)  - 本教程最初由 Shopify 出于内部目的而创建. 它基于 Shopify 近 3 年创建和发展生产模式的经验教训.
- [GitLab GraphQL API Style Guide](https://docs.gitlab.com/ee/development/api_graphql_styleguide.html) - 本文档概述了 GitLab GraphQL API 的风格指南.
- [Yelp GraphQL Guidelines](https://yelp.github.io/graphql-guidelines/) - 此存储库包含标准化且最合理的 GraphQL 方法的文档和指南（在 Yelp 上）.
- [Principled GraphQL](https://principledgraphql.com/) - Apollo 的 10 条 GraphQL 原则，分为三类，格式灵感来自十二因素应用程序.

<a name="blogs" />

## Blogs

- [Official GraphQL blog](https://graphql.org/blog/)
- [Building Apollo](https://blog.apollographql.com/)
- [The Guild blog](https://medium.com/the-guild)
- [Production Ready GraphQL blog](https://productionreadygraphql.com)

<a name="security-blog" />

### Blogs - Security

- [Escape - The GraphQL Security Blog](https://blog.escape.tech) - 了解 GraphQL 安全性、性能、测试以及使用 GraphQL 生态系统的最新工具和最佳实践构建生产就绪的 API.
- [9 GraphQL Security Best Practices](https://blog.escape.tech/9-graphql-security-best-practices/)
- [Discovering GraphQL Endpoints and SQLi Vulnerabilities](https://medium.com/@localh0t/discovering-graphql-endpoints-and-sqli-vulnerabilities-5d39f26cea2e)
- [Securing GraphQL API](https://lab.wallarm.com/securing-graphql-api/)
- [Security Points to Consider Before Implementing GraphQL](https://nordicapis.com/security-points-to-consider-before-implementing-graphql/)
- [GraphQL for Pentesters](https://www.acceis.fr/graphql-for-pentesters/) - 基本概念介绍、安全注意事项和侦察、漏洞和攻击、攻击性工具.

<a name="post" />

## Posts

- [GraphQL federation example with Apollo Federation and Apollo GraphOS](https://cube.dev/blog/graphql-federation-example-with-apollo-federation-and-apollo-graphos)
- [GraphQL federation with Hasura GraphQL Engine and Cube](https://cube.dev/blog/graphql-federation-with-hasura-graphql-engine)
- [Using DataLoader to batch GraphQL requests](https://medium.com/@gajus/using-dataloader-to-batch-requests-c345f4b23433)
- [Introducing Relay and GraphQL](https://reactjs.org/blog/2015/02/20/introducing-relay-and-graphql.html)
- [GraphQL Introduction](https://reactjs.org/blog/2015/05/01/graphql-introduction.html)
- [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47)
- [Your First GraphQL Server](https://medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2)
- [GraphQL Overview - Getting Started with GraphQL and Node.js](https://blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/)
- [4 Reasons you should try out GraphQL](https://medium.freecodecamp.org/introduction-to-graphql-1d8011b80159)
- [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247)
- [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/)
- [Building a GraphQL Server with Node.js and SQL](https://www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/)
- [GraphQL at The Financial Times](https://www.slideshare.net/LondonReact/graph-ql)
- [From REST to GraphQL](https://jacobwgillespie.com/2015-10-09-from-rest-to-graphql)
- [GraphQL: A data query language](https://graphql.org/blog/graphql-a-query-language/)
- [Subscriptions in GraphQL and Relay](https://graphql.org/blog/subscriptions-in-graphql-and-relay/)
- [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6)
- [GraphQL Shorthand Notation Cheatsheet](https://wehavefaces.net/graphql-shorthand-notation-cheatsheet-17cd715861b6)
- [The GitHub GraphQL API](https://githubengineering.com/the-github-graphql-api/)
- [Github GraphQL API React Example](https://medium.com/@katopz/github-graphql-api-react-example-eace824d7b61)
- [Testing a GraphQL Server using Jest](https://medium.com/entria/testing-a-graphql-server-using-jest-4e00d0e4980e)
- [How to implement viewerCanSee in GraphQL](https://medium.com/entria/how-to-implement-viewercansee-in-graphql-78cc48de7464)
- [Preventing traversal attacks on your GraphQL API](https://blog.morethancode.dev/preventing-traversal-attacks-in-your-graphql-api/)
- [Mock your GraphQL server realistically with faker.js](https://dev.to/yvonnickfrin/mock-your-graphql-server-realistically-with-faker-js-25oo)
- [Create an infinite loading list with React and GraphQL](https://dev.to/yvonnickfrin/create-an-infinite-loading-list-with-react-and-graphql-19hh)
- [REST vs GraphQL](https://www.moesif.com/blog/technical/graphql/REST-vs-GraphQL-APIs-the-good-the-bad-the-ugly/)
- [Authentication and Authorization for GraphQL APIs](https://www.moesif.com/blog/technical/api-design/Steps-to-Building-Authentication-and-Authorization-For-GraphQL-APIs/)
- [Build a GraphQL API with Siler on top of Swoole](https://www.swoole.co.uk/article/Build-a-GraphQL-API-on-top-of-Swoole)
- [Fluent GraphQL clients: how to write queries like a boss](https://hasura.io/blog/fluent-graphql-clients-how-to-write-queries-like-a-boss/)
- [Level up your serverless game with a GraphQL data-as-a-service layer](https://hasura.io/blog/level-up-your-serverless-game-with-a-graphql-data-as-a-service-layer/)
- [A deep-dive into Relay, the friendly & opinionated GraphQL client](https://hasura.io/blog/deep-dive-into-relay-graphql-client/)
- [make your graphql api easier to adopt through components](https://hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1)
- [Undocumented: keeping parts of your GraphQL schema hidden from introspection](https://www.useanvil.com/blog/engineering/undocumented-directive/)

<a name="tutorials" />

## Tutorials

- [How to GraphQL](https://www.howtographql.com) - 全栈教程网站，包含所有主要框架和语言的跟踪，包括 React、Apollo、Relay、JavaScript、Ruby、Java、Elixir 等等.
- [Apollo Odyssey](https://odyssey.apollographql.com/) - Apollo的免费互动学习平台.
- [learning-graphql](https://github.com/mugli/learning-graphql) - 尝试学习 GraphQL.
- [GraphQL Roadmap](https://roadmap.sh/graphql/) - 学习 GraphQL 的分步指南.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Chen-Tsu Lin](https://github.com/chentsulin) 已放弃本作品的所有版权以及相关或邻接权.
