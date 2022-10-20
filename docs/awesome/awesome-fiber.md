<div class="github-widget" data-repo="gofiber/awesome-fiber"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Fiber [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://gofiber.io">
  <img src="https://raw.githubusercontent.com/gofiber/docs/master/static/fiber_v2_logo.svg" alt="Fiber Logo" align="right" style="margin-right: 25px" height=75>
</a>

> **Fiber** is an [Express](https://github.com/expressjs/express) 受启发的 **web 框架** 建立在 [Fasthttp](https://github.com/valyala/fasthttp)，**最快的** HTTP 引擎 [Go](https://golang.org/doc/) . 旨在为**快速**开发**缓解**事情，同时考虑**零内存分配**和**性能**.

精选的 Fiber 中间件、样板、食谱、文章和工具的精选列表.
<br>

<!--lint disable awesome-toc-->
<!--lint disable awesome-git-repo-age-->

## ⚙️ Middlewares
在哪里可以找到 Fiber 中间件.

### 🧬 Core
Fiber 框架中包含的中间件列表.
- [BasicAuth](https://github.com/gofiber/fiber/tree/master/middleware/basicauth)  - 基本身份验证中间件提供 HTTP 基本身份验证. 它为有效凭据调用下一个处理程序，并为丢失或无效凭据调用 401 Unauthorized.
- [Cache](https://github.com/gofiber/fiber/tree/master/middleware/cache) - 拦截和缓存响应.
- [Compress](https://github.com/gofiber/fiber/tree/master/middleware/compress) - Fiber 的压缩中间件，默认支持 `deflate`、`gzip` 和 `brotli`.
- [CORS](https://github.com/gofiber/fiber/tree/master/middleware/cors) - 使用各种选项启用跨域资源共享 (CORS).
- [CSRF](https://github.com/gofiber/fiber/tree/master/middleware/csrf) - 防止 CSRF 漏洞利用.
- [Encrypt Cookie](https://github.com/gofiber/fiber/tree/master/middleware/encryptcookie) - 加密中间件，加密 cookie 值.
- [EnvVar](https://github.com/gofiber/fiber/tree/master/middleware/envvar) - 通过提供可选配置来公开环境变量.
- [ETag](https://github.com/gofiber/fiber/tree/master/middleware/etag) - ETag 中间件让缓存更高效并节省带宽，因为如果内容没有更改，Web 服务器不需要重新发送完整响应.
- [Expvar](https://github.com/gofiber/fiber/tree/master/middleware/expvar) - 通过其 HTTP 服务器运行时提供服务的 Expvar 中间件以 JSON 格式公开变体.
- [Favicon](https://github.com/gofiber/fiber/tree/master/middleware/favicon) - 如果提供了文件路径，则忽略日志中的网站图标或从内存中提供服务.
- [FileSystem](https://github.com/gofiber/fiber/tree/master/middleware/filesystem) - 用于 Fiber 的 FileSystem 中间件，特别感谢 Alireza Salary.
- [Limiter](https://github.com/gofiber/fiber/tree/master/middleware/limiter)  - 限速中间件. 用于限制对公共 API 和/或端点的重复请求，例如密码重置.
- [Logger](https://github.com/gofiber/fiber/tree/master/middleware/logger) - HTTP 请求/响应记录器.
- [Monitor](https://github.com/gofiber/fiber/tree/master/middleware/monitor) - 监控报告服务器指标的中间件，受 express-status-monitor 启发.
- [Pprof](https://github.com/gofiber/fiber/tree/master/middleware/pprof) - Pprof 中间件通过其 HTTP 服务器运行时分析数据以 pprof 可视化工具预期的格式提供服务.
- [Proxy](https://github.com/gofiber/fiber/tree/master/middleware/proxy) - 允许您将请求代理到多个服务器.
- [Recover](https://github.com/gofiber/fiber/tree/master/middleware/recover) - 恢复中间件从堆栈链中任何地方的恐慌中恢复，并将控制权交给集中式 ErrorHandler.
- [RequestID](https://github.com/gofiber/fiber/tree/master/middleware/requestid) - 为每个请求添加一个 requestid.
- [Session](https://github.com/gofiber/fiber/tree/master/middleware/session)  - 会话中间件. 注意：这个中间件使用我们的存储包.
- [Skip](https://github.com/gofiber/fiber/tree/master/middleware/skip) - 跳过包装处理程序的跳过中间件是谓词为真.
- [Timeout](https://github.com/gofiber/fiber/tree/master/middleware/timeout) - 为请求添加最大时间，如果超过则转发给 ErrorHandler.

### 🔗 External
外部托管的中间件模块列表并由 [Fiber team](https://github.com/orgs/gofiber/people).
- [adaptor](https://github.com/gofiber/adaptor) - net/http 处理程序与 Fiber 请求处理程序之间的转换器.
- [helmet](https://github.com/gofiber/helmet) - 通过设置各种 HTTP 标头来帮助保护您的应用程序.
- [jwt](https://github.com/gofiber/jwt) - JWT 返回一个 JSON Web Token (JWT) 身份验证中间件.
- [keyauth](https://github.com/gofiber/keyauth) - Key auth 中间件提供基于密钥的身份验证.
- [redirect](https://github.com/gofiber/redirect) - 为 Fiber 重定向中间件.
- [rewrite](https://github.com/gofiber/rewrite)  - 重写中间件根据提供的规则重写 URL 路径. 它有助于向后兼容或只是创建更清晰和更具描述性的链接.
- [storage](https://github.com/gofiber/storage) - 实现 Storage 接口的预制存储驱动程序，旨在与各种 Fiber 中间件一起使用.
- [template](https://github.com/gofiber/template) - 此软件包包含 8 个模板引擎，可用于 Fiber v1.10.x Go 版本 1.13 或更高版本.
- [websocket](https://github.com/gofiber/websocket) - 基于Fasthttp WebSocket for Fiber，支持Locals！

### ‍💻 Contrib
由 Fiber 团队和社区维护的第三方中间件列表.
- [casbin](https://github.com/gofiber/contrib/tree/main/casbin) - 用于 Fiber 的 Casbin 中间件.
- [fibernewrelic](https://github.com/gofiber/contrib/tree/main/fibernewrelic)  - 用于 Fiber 的 NewRelic 中间件. 中间件处理 NewRelic 仪器.
- [fibersentry](https://github.com/gofiber/contrib/tree/main/fibersentry) - 对光纤的哨兵支持.
- [fiberzap](https://github.com/gofiber/contrib/tree/main/fiberzap) - 对 Fiber 的 Zap 日志记录支持.
- [opafiber](https://github.com/gofiber/contrib/tree/main/opafiber)  - 为 Fiber 开放策略代理中间件. 中间件处理正在运行的 Rego 策略.
- [otelfiber](https://github.com/gofiber/contrib/tree/main/otelfiber) - 对光纤的 OpenTelemetry 支持.
- [paseto](https://github.com/gofiber/contrib/tree/main/paseto) - PASETO 返回一个 Web Token (PASETO) 身份验证中间件.
- [swagger](https://github.com/gofiber/contrib/tree/main/swagger)  - 用于 Fiber 的 Swagger 中间件. 中间件处理 Swagger UI.

### 🌱 Third Party
Fiber 社区创建的中间件列表.
- [arsmn/fiber-swagger](https://github.com/arsmn/fiber-swagger) - 使用 Swagger 2.0 自动生成 RESTful API 文档的 Fiber 中间件.
- [arsmn/fiber-casbin](https://github.com/arsmn/fiber-casbin) - 用于 Fiber 的 Casbin 中间件.
- [shareed2k/fiber_tracing](https://github.com/shareed2k/fiber_tracing) - 带有 OpenTracing API 的 Fiber 框架上的中间件跟踪请求.
- [shareed2k/fiber_limiter](https://github.com/shareed2k/fiber_limiter) - 限制器使用 redis 作为速率限制的存储，具有两种选择滑动窗口的算法，gcra 漏桶.
- [arsmn/fastgql](https://github.com/arsmn/fastgql) - 用于构建 GraphQL 服务器的 Go 库，无需大惊小怪，但支持 fasthttp.
- [kiyonlin/fiber_limiter](https://github.com/kiyonlin/fiber_limiter) - 限制器基于 golang.org/x/time/rate 的分叉速率.
- [juandiii/go-jwk-security](https://github.com/juandiii/go-jwk-security) - 用于光纤的 JWT 中间件. 
- [ansrivas/fiberprometheus](https://github.com/ansrivas/fiberprometheus) - 用于 gofiber 的 Prometheus 中间件.
- [LdDl/fiber-long-poll](https://github.com/LdDl/fiber-long-poll) - Golang 长轮询库，用于名为 Fiber 的基于 fasthttp 的 web 框架.
- [K0enM/fiber_vhost](https://github.com/K0enM/fiber_vhost) - 用于 Fiber 的 Vhost（虚拟主机）中间件，允许使用基于主机标头的虚拟主机.
- [sacsand/gofiber-firebaseauth](https://github.com/sacsand/gofiber-firebaseauth) - 光纤 Firebase 身份验证中间件.
- [theArtechnology/fiber-inertia](https://github.com/theArtechnology/fiber-inertia) - 这是一个基于惯性 laravel 的 Inertia.js 服务器端适配器，但适用于 Fiber 框架.
- [aschenmaker/fiber-health-check](https://github.com/aschenmaker/fiber-health-check) - 健康检查中间件支持 Fiber️ 框架的健康检查.
- [elastic/apmfiber](https://github.com/elastic/apm-agent-go/tree/master/module/apmfiber) - Go Fiber 的 APM 代理.
- [eozer/fiber_ldapauth](https://github.com/eozer/fiber_ldapauth) - 用于光纤的 LDAP 身份验证中间件.
- [darkweak/souin](https://github.com/darkweak/souin) - HTTP 缓存，符合 RFC，可作为中间件替代 Varnish.
- [witer33/fiberpow](https://github.com/witer33/fiberpow) - 具有可定制工作证明挑战的反 DDoS/Bot 中间件.
- [joffref/opa-middleware](https://github.com/Joffref/opa-middleware) - 为光纤提供 OPA 中间件集成.


## 🚧 Boilerplates
Fiber 的预制样板.
- [gofiber/boilerplate](https://github.com/gofiber/boilerplate) - 官方纤维样板.
- [fiber-boilerplate](https://github.com/thomasvvugt/fiber-boilerplate) - Fiber web 框架的样板.
- [sujit-baniya/fiber-boilerplate](https://github.com/sujit-baniya/fiber-boilerplate) - 带有许多中间件和功能的光纤网络框架顶部的样板.
- [sujit-baniya/goravel](https://github.com/sujit-baniya/goravel) - Laravel 类似的样板 go Go，支持 Gofiber 或 Gin.
- [create-go-app/fiber-go-template](https://github.com/create-go-app/fiber-go-template) - Create Go App CLI 的光纤后端模板.
- [efectn/fiber-boilerplate](https://github.com/efectn/fiber-boilerplate) - 简单且可扩展的样板，用于使用 Fiber 构建强大且有组织的 REST 项目. 
- [embedmode/fiberseed](https://github.com/embedmode/fiberseed) - 带有许多中间件的光纤样板 API.


## 📁 Recipes
纤维食谱.
- [gofiber/recipes](https://github.com/gofiber/recipes) - 官方纤维食谱.
- [kiyonlin/fiblar-demo](https://github.com/kiyonlin/fiblar-demo) - Fiber v1 + 角度演示.
- [koddr/tutorial-go-fiber-rest-api](https://github.com/koddr/tutorial-go-fiber-rest-api) - 使用 Fiber 构建 restful api 的教程.
- [firebase007/go-rest-api-with-fiber](https://github.com/firebase007/go-rest-api-with-fiber) - 包含光纤、日志记录、basicAuth 和 postgresql 的演示项目.
- [chawk/go_fiber_quickstart](https://github.com/chawk/go_fiber_quickstart) - 光纤快速启动示例项目.
- [EricLau1/go-fiber-auth-api](https://github.com/EricLau1/go-fiber-auth-api) - 带有 Fiber MongoDB 和 JWT 的 Golang 身份验证 API.

## 🛠️ Tools
几个使 Fiber 使用更容易的工具.
- [gofiber/cli](https://github.com/gofiber/cli) - 光纤命令行界面.
- [go-dawn/dawn](https://github.com/go-dawn/dawn) - Dawn 是一个固执己见的 Web 框架，它提供了基于 Fiber 的快速开发能力.
- [tompston/gomakeme](https://github.com/tompston/gomakeme) - 为 Fiber 或 Gin REST API 生成样板文件 + 端点.

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


## 📺 Videos
社区创建的有关 Fiber 的视频教程.

- [Is Fiber the best Go web framework? Better than Gin?](https://youtu.be/10miByMOGfY)


## 🤖 Benchmarks
将 Fiber 与其他框架进行比较的几个基准.
- [TechEmpower](https://www.techempower.com/benchmarks/#section=data-r20&hw=ph&test=json) - 项目提供跨广泛的 Web 应用程序框架领域的性能度量.
- [web-frameworks-benchmark](https://web-frameworks-benchmark.netlify.app/result) - 项目旨在衡量各种编程语言框架之间的差异.
- [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - 该基准套件旨在比较 Go Web 框架的性能.


### 👍 Contributing

贡献指南可以在 [CONTRIBUTING.md](https://github.com/gofiber/awesome-fiber/blob/master/CONTRIBUTING.md)
