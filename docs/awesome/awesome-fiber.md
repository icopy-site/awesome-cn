<div class="github-widget" data-repo="gofiber/awesome-fiber"></div>
## Awesome Fiber [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://gofiber.io">
  <picture alt="Fiber Logo" align="right" style="margin-right: 25px">
    <source height="75" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gofiber/docs/master/static/img/logo-dark.svg?sanitize=true">
    <img height="75" alt="Fiber Logo" align="right" style="margin-right: 25px" src="https://raw.githubusercontent.com/gofiber/docs/master/static/img/logo.svg">
  </picture>
</a>

&gt; **纤维**是一种 [Express](https://github.com/expressjs/express) 受启发的 **web 框架** 建立在 [Fasthttp](https://github.com/valyala/fasthttp), **最快** HTTP 引擎 [Go](https://golang.org/doc/) . 旨在**简化**事情以实现**快速**开发，同时考虑**零内存分配**和**性能**.

一个很棒的 Fiber 中间件、样板、食谱、文章和工具的精选列表.
<br>

<!--lint disable awesome-toc-->
<!--lint disable awesome-git-repo-age-->

## ⚙️ Middlewares
在哪里可以找到 Fiber 中间件.

### 🧬 Core
Fiber 框架中包含的中间件列表.
- [Adaptor](https://github.com/gofiber/fiber/tree/master/middleware/adaptor) - net/http 处理程序与 Fiber 请求处理程序之间的转换器.
- [BasicAuth](https://github.com/gofiber/fiber/tree/master/middleware/basicauth)  - 基本身份验证中间件提供 HTTP 基本身份验证. 它调用下一个处理程序来获取有效凭证，并调用 401 Unauthorized 来获取丢失或无效的凭证.
- [Cache](https://github.com/gofiber/fiber/tree/master/middleware/cache) - 拦截和缓存响应.
- [Compress](https://github.com/gofiber/fiber/tree/master/middleware/compress) - Fiber压缩中间件，默认支持`deflate`、`gzip`和`brotli`.
- [CORS](https://github.com/gofiber/fiber/tree/master/middleware/cors) - 使用各种选项启用跨域资源共享 (CORS).
- [CSRF](https://github.com/gofiber/fiber/tree/master/middleware/csrf) - 防止 CSRF 攻击.
- [Earlydata](https://github.com/gofiber/fiber/tree/master/middleware/earlydata) - 光纤的早期数据支持.
- [Encrypt Cookie](https://github.com/gofiber/fiber/tree/master/middleware/encryptcookie) - 加密 cookie 值的加密中间件.
- [EnvVar](https://github.com/gofiber/fiber/tree/master/middleware/envvar) - 通过提供可选配置公开环境变量.
- [ETag](https://github.com/gofiber/fiber/tree/master/middleware/etag) - ETag 中间件让缓存更高效并节省带宽，因为如果内容没有更改，Web 服务器不需要重新发送完整的响应.
- [Expvar](https://github.com/gofiber/fiber/tree/master/middleware/expvar) - 通过其 HTTP 服务器运行时服务的 Expvar 中间件以 JSON 格式暴露变体.
- [Favicon](https://github.com/gofiber/fiber/tree/master/middleware/favicon) - 如果提供了文件路径，则忽略日志中的图标或从内存中提供服务.
- [FileSystem](https://github.com/gofiber/fiber/tree/master/middleware/filesystem) - 用于 Fiber 的文件系统中间件，特别感谢 Alireza Salary.
- [Helmet](https://github.com/gofiber/fiber/tree/master/middleware/helmet) - 通过设置各种 HTTP 标头帮助保护您的应用程序.
- [Idempotency](https://github.com/gofiber/fiber/tree/master/middleware/idempotency) - Fiber 的幂等性中间件允许在重复请求的情况下使用容错 API.
- [Keyauth](https://github.com/gofiber/fiber/tree/master/middleware/keyauth) - 密钥授权中间件提供基于密钥的身份验证.
- [Limiter](https://github.com/gofiber/fiber/tree/master/middleware/limiter)  - 限速中间件. 用于限制对公共 API 和/或端点的重复请求，例如密码重置.
- [Logger](https://github.com/gofiber/fiber/tree/master/middleware/logger) - HTTP 请求/响应记录器.
- [Monitor](https://github.com/gofiber/fiber/tree/master/middleware/monitor) - 受 express-status-monitor 启发，监控报告服务器指标的中间件.
- [Pprof](https://github.com/gofiber/fiber/tree/master/middleware/pprof) - Pprof 中间件，通过其 HTTP 服务器运行时分析数据以 pprof 可视化工具预期的格式提供服务.
- [Proxy](https://github.com/gofiber/fiber/tree/master/middleware/proxy) - 允许您将请求代理到多个服务器.
- [Recover](https://github.com/gofiber/fiber/tree/master/middleware/recover) - 恢复中间件从堆栈链中任何地方的恐慌中恢复，并将控制权交给集中式 ErrorHandler.
- [Redirect](https://github.com/gofiber/fiber/tree/master/middleware/redirect) - 为 Fiber 重定向中间件.
- [RequestID](https://github.com/gofiber/fiber/tree/master/middleware/requestid) - 为每个请求添加一个 requestid.
- [Rewrite](https://github.com/gofiber/fiber/tree/master/middleware/rewrite)  - 重写中间件根据提供的规则重写 URL 路径. 它有助于向后兼容或只是创建更清晰和更具描述性的链接.
- [Session](https://github.com/gofiber/fiber/tree/master/middleware/session)  - 会话中间件. 注意：此中间件使用我们的存储包.
- [Skip](https://github.com/gofiber/fiber/tree/master/middleware/skip) - 跳过包装处理程序的跳过中间件谓词为真.
- [Timeout](https://github.com/gofiber/fiber/tree/master/middleware/timeout) - 为请求添加最大时间，如果超过则转发给 ErrorHandler.

### 🔗 External
外部托管的中间件模块列表，由 [Fiber team](https://github.com/orgs/gofiber/people).
- [storage](https://github.com/gofiber/storage) - 实现存储接口的预制存储驱动程序，旨在与各种光纤中间件一起使用.
- [template](https://github.com/gofiber/template) - 此软件包包含 8 个模板引擎，可用于 Fiber v1.10.x Go 版本 1.13 或更高版本是必需的.


### ‍💻 Contrib
由 Fiber 团队和社区维护的第三方中间件列表.
- [casbin](https://github.com/gofiber/contrib/tree/main/casbin) - Fiber 的 Casbin 中间件.
- [fiberi18n](https://github.com/gofiber/contrib/tree/main/fiberi18n) - go-i18n 支持光纤.
- [fibernewrelic](https://github.com/gofiber/contrib/tree/main/fibernewrelic)  - 用于 Fiber 的 NewRelic 中间件. 中间件处理 NewRelic 工具化.
- [fibersentry](https://github.com/gofiber/contrib/tree/main/fibersentry) - 对光纤的哨兵支持.
- [fiberzap](https://github.com/gofiber/contrib/tree/main/fiberzap) - 对 Fiber 的 Zap 日志记录支持.
- [jwt](https://github.com/gofiber/jwt) - JWT 返回一个 JSON Web 令牌 (JWT) 身份验证中间件.
- [opafiber](https://github.com/gofiber/contrib/tree/main/opafiber)  - 用于光纤的开放策略代理中间件. 中间件处理运行的 Rego 策略.
- [otelfiber](https://github.com/gofiber/contrib/tree/main/otelfiber) - 光纤的 OpenTelemetry 支持.
- [paseto](https://github.com/gofiber/contrib/tree/main/paseto) - PASETO 返回一个 Web 令牌 (PASETO) 身份验证中间件.
- [swagger](https://github.com/gofiber/contrib/tree/main/swagger)  - 用于 Fiber 的 Swagger 中间件. 中间件处理 Swagger UI.
- [websocket](https://github.com/gofiber/websocket) - 基于具有本地支持的 Fasthttp WebSocket for Fiber！

### 🌱 Third Party
Fiber 社区创建的中间件列表.
- [arsmn/fiber-swagger](https://github.com/arsmn/fiber-swagger) - 使用 Swagger 2.0 自动生成 RESTful API 文档的 Fiber 中间件.
- [arsmn/fiber-casbin](https://github.com/arsmn/fiber-casbin) - Fiber 的 Casbin 中间件.
- [shareed2k/fiber_tracing](https://github.com/shareed2k/fiber_tracing) - 使用 OpenTracing API 对 Fiber 框架的中间件跟踪请求.
- [shareed2k/fiber_limiter](https://github.com/shareed2k/fiber_limiter) - 限制器使用 redis 作为速率限制的存储，有两种选择滑动窗口的算法，gcra 漏桶.
- [arsmn/fastgql](https://github.com/arsmn/fastgql) - 用于构建 GraphQL 服务器的 Go 库，无需大惊小怪，但具有 fasthttp 支持.
- [kiyonlin/fiber_limiter](https://github.com/kiyonlin/fiber_limiter) - 限制器基于 golang.org/x/time/rate 的分叉率.
- [juandiii/go-jwk-security](https://github.com/juandiii/go-jwk-security) - 用于光纤的 JWT 中间件. 
- [ansrivas/fiberprometheus](https://github.com/ansrivas/fiberprometheus) - 用于 gofiber 的普罗米修斯中间件.
- [LdDl/fiber-long-poll](https://github.com/LdDl/fiber-long-poll) - Golang 长轮询库，用于名为 Fiber 的基于 fasthttp 的 Web 框架.
- [K0enM/fiber_vhost](https://github.com/K0enM/fiber_vhost) - 用于 Fiber 的 Vhost（虚拟主机）中间件，它允许使用基于主机头的虚拟主机.
- [sacsand/gofiber-firebaseauth](https://github.com/sacsand/gofiber-firebaseauth) - Fiber Firebase Auth 中间件.
- [theArtechnology/fiber-inertia](https://github.com/theArtechnology/fiber-inertia) - 这是一个基于 inertia-laravel 的 Inertia.js 服务器端适配器，但适用于 Fiber Framework.
- [aschenmaker/fiber-health-check](https://github.com/aschenmaker/fiber-health-check) - 健康检查中间件支持Fiber️框架的健康检查.
- [elastic/apmfiber](https://github.com/elastic/apm-agent-go/tree/master/module/apmfiber) - 用于 Go Fiber 的 APM 代理.
- [eozer/fiber_ldapauth](https://github.com/eozer/fiber_ldapauth) - 用于光纤的 LDAP 身份验证中间件.
- [darkweak/souin](https://github.com/darkweak/souin) - HTTP 缓存，符合 RFC，可作为中间件替代 Varnish.
- [witer33/fiberpow](https://github.com/witer33/fiberpow) - 具有可定制的工作证明挑战的反 DDoS/机器人中间件.
- [joffref/opa-middleware](https://github.com/Joffref/opa-middleware) - 为光纤提供 OPA 中间件集成.
- [vladfr/fiber-servertiming](https://github.com/vladfr/fiber-servertiming) - 基于 W3C 服务器计时规范添加服务器计时标头的中间件.
- [airbrake/gobrake](https://github.com/airbrake/gobrake/tree/master/examples/fiber) - 报告性能数据（路由统计）的 Airbrake 中间件.
- [samber/slog-fiber](https://github.com/samber/slog-fiber) - 使用 Go slog 库的记录器中间件.
- [mikhail-bigun/fiberlogrus](https://github.com/mikhail-bigun/fiberlogrus) - 使用 logrus 及其结构化日志记录功能的记录器中间件.
- [Idan-Fishman/validation](https://github.com/Idan-Fishman/validation) - 验证请求正文、查询字符串参数和路由参数等来源的数据验证中间件.

## 🚧 Boilerplates
Fiber 的预制样板.
- [gofiber/boilerplate](https://github.com/gofiber/boilerplate) - 官方纤维样板.
- [fiber-boilerplate](https://github.com/thomasvvugt/fiber-boilerplate) - Fiber web 框架的样板.
- [sujit-baniya/fiber-boilerplate](https://github.com/sujit-baniya/fiber-boilerplate) - 具有许多中间件和功能的光纤网络框架顶部的样板.
- [sujit-baniya/goravel](https://github.com/sujit-baniya/goravel) - Laravel 类似样板 go Go，支持 Gofiber 或 Gin.
- [create-go-app/fiber-go-template](https://github.com/create-go-app/fiber-go-template) - 用于 Create Go App CLI 的光纤后端模板.
- [efectn/fiber-boilerplate](https://github.com/efectn/fiber-boilerplate) - 简单且可扩展的样板，用于使用 Fiber 构建功能强大且有组织的 REST 项目. 
- [embedmode/fiberseed](https://github.com/embedmode/fiberseed) - 带有许多中间件的 Fiber 样板 API.
- [GalvinGao/gofiber-template](https://github.com/GalvinGao/gofiber-template)  - 一个生产就绪的、容器优先的固执己见的 gofiber 项目模板. 通过 envvars 配置，通过 go.uber.org/fx 进行 DI，通过 uptrace/bun 进行数据库，具有开箱即用的 MVC 文件夹结构和 CI/CD 支持.
- [mikhail-bigun/go-app-template](https://github.com/mikhail-bigun/go-app-template) - 具有丰富 Fiber 实现的干净架构 Go 应用程序样板.


## 📁 Recipes
纤维食谱.
- [gofiber/recipes](https://github.com/gofiber/recipes) - 官方纤维食谱.
- [kiyonlin/fiblar-demo](https://github.com/kiyonlin/fiblar-demo) - Fiber v1 + 角度演示.
- [koddr/tutorial-go-fiber-rest-api](https://github.com/koddr/tutorial-go-fiber-rest-api) - 使用 fiber 构建 restful api 的教程.
- [firebase007/go-rest-api-with-fiber](https://github.com/firebase007/go-rest-api-with-fiber) - 带有光纤、日志记录、basicAuth 和 postgresql 的演示项目.
- [chawk/go_fiber_quickstart](https://github.com/chawk/go_fiber_quickstart) - 光纤快速启动示例项目.
- [EricLau1/go-fiber-auth-api](https://github.com/EricLau1/go-fiber-auth-api) - 使用 Fiber MongoDB 和 JWT 的 Golang 身份验证 API.

## 🛠️ Tools
几个使 Fiber 使用更容易的工具.
- [go-dawn/dawn](https://github.com/go-dawn/dawn) - Dawn is an opinionated web framework that provides rapid development capabilities which on top of Fiber.
- [tompston/gomakeme](https://github.com/tompston/gomakeme) - 为 Fiber 或 Gin REST API 生成样板 + 端点.
- [ryanbekhen/feserve](https://github.com/ryanbekhen/feserve) - Feserve 是一个轻量级应用程序或 docker 镜像，用于为前端和负载均衡器应用程序提供服务.

## 📖 Articles
社区撰写的有关 Fiber 的文章.

- [Working with middlewares and boilerplates](https://dev.to/koddr/go-fiber-by-examples-working-with-middlewares-and-boilerplates-3p0m)
- [Testing the application](https://dev.to/koddr/go-fiber-by-examples-testing-the-application-1ldf)
- [Delving into built-in functions](https://dev.to/koddr/go-fiber-by-examples-delving-into-built-in-functions-1p3k)
- [Go Fiber by Examples: How can the Fiber Web Framework be useful?](https://dev.to/koddr/go-fiber-by-examples-how-can-the-fiber-web-framework-be-useful-487a)
- [Build a RESTful API on Go: Fiber, PostgreSQL, JWT and Swagger docs in isolated Docker containers](https://dev.to/koddr/build-a-restful-api-on-go-fiber-postgresql-jwt-and-swagger-docs-in-isolated-docker-containers-475j)
- [Getting started with Fiber](https://dev.to/fenny/getting-started-with-fiber-36b6)
- [Building an Express-style API in Go with Fiber](https://blog.logrocket.com/express-style-api-go-fiber/)
- [Fiber v1.9.6 How to improve performance by 817% and stay fast, flexible and friendly?](https://dev.to/koddr/fiber-v1-9-5-how-to-improve-performance-by-817-and-stay-fast-flexible-and-friendly-2dp6)
- [Create a travel list app with Go, Fiber, Angular, MongoDB and Google Cloud Secret Manager](https://blog.yongweilun.me/create-a-travel-list-app-with-go-fiber-angular-mongodb-and-google-cloud-secret-manager-ck9fgxy0p061pcss1xt1ubu8t)
- [Building a Basic REST API in Go using Fiber](https://tutorialedge.net/golang/basic-rest-api-go-fiber/)
- [Creating Fast APIs In Go Using Fiber](https://dev.to/jozsefsallai/creating-fast-apis-in-go-using-fiber-59m9)
- [Is switching from Express to Fiber worth it?](https://dev.to/koddr/are-sure-what-your-lovely-web-framework-running-so-fast-2jl1)
- [Fiber v1.8. What's new, updated and re-thinked?](https://dev.to/koddr/fiber-v1-8-what-s-new-updated-and-re-thinked-339h)
- [Fiber released v1.7! What\'s new and is it still fast, flexible and friendly?](https://dev.to/koddr/fiber-v2-is-out-now-what-s-new-and-is-he-still-fast-flexible-and-friendly-3ipf)
- [Welcome to Fiber — an Express.js styled web framework written in Go with ❤️](https://dev.to/koddr/welcome-to-fiber-an-express-js-styled-fastest-web-framework-written-with-on-golang-497)
- [Blazing Fast Unit Tests - Fiber/fasthttp/http Internals](https://medium.com/trendyol-tech/golang-blazing-fast-unit-tests-fiber-fasthttp-http-internals-and-optimizing-http-server-tests-bbd1fe7b944b)
- [Building Microservices in Go : Part 1 - Project Setup, Dockerization](https://saadfarhan124.medium.com/building-microservices-in-go-part-1-e7e58893bc5e)
- [Building Microservices in Go : Part 2 - Live Reload](https://saadfarhan124.medium.com/building-microservices-in-go-part-2-f9c6c535805c)
- [Building Microservices in Go : Part 3 - Database, Models, Migrations](https://saadfarhan124.medium.com/building-microservices-in-go-part-3-database-models-migrations-a4455121bb11)
- [Build a REST API from scratch with Go, Docker & Postgres](https://dev.to/divrhino/build-a-rest-api-from-scratch-with-go-and-docker-3o54)
- [Build a fullstack app with Go Fiber, Docker, and Postgres](https://dev.to/divrhino/build-a-fullstack-app-with-go-fiber-docker-and-postgres-1jg6)
- [Create a CRUD app with Go Fiber, docker, and Postgres](https://dev.to/divrhino/create-a-crud-app-with-go-fiber-docker-and-postgres-47e3)


## 📺 Videos
社区创建的有关 Fiber 的视频教程.

- [Is Fiber the best Go web framework? Better than Gin?](https://youtu.be/10miByMOGfY)


## 🤖 Benchmarks
将 Fiber 与其他框架进行比较的几个基准.
- [TechEmpower](https://www.techempower.com/benchmarks/#section=data-r20&hw=ph&test=json) - Project 提供广泛的 Web 应用程序框架领域的性能测量.
- [web-frameworks-benchmark](https://web-frameworks-benchmark.netlify.app/result) - 项目旨在衡量各种编程语言框架之间的差异.
- [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - 这个基准套件旨在比较 Go 网络框架的性能.


### 👍 Contributing

贡献指南可以在 [CONTRIBUTING.md](https://github.com/gofiber/awesome-fiber/blob/master/CONTRIBUTING.md)
