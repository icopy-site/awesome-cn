<div class="github-widget" data-repo="denolib/awesome-deno"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Deno [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/denolib/awesome-deno/master/deno-logo.png" align="right" width="100">](https://deno.land)

Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

这个列表是最好的 Deno 模块和资源的集合.



## Docs

### Official Docs

- [Official Site](https://deno.land)
- [Deno API Reference](https://doc.deno.land/builtin/stable)
  - [Deno Unstable API Reference](https://doc.deno.land/builtin/unstable)
- [Deno Manual](https://deno.land/manual)

### External Docs

- [V8 Docs for Deno](https://denolib.github.io/v8-docs/)
- [DenoBeginner.com](https://DenoBeginner.com) - A completely free crash course on deno for beginners.

### Online Playgrounds

- [deno.town](https://deno.town)
- [Deno Playground](https://deno-playground.now.sh)
  - [maman/deno-playground](https://github.com/maman/deno-playground)
- [DenoBR Playground](https://playground.denobr.com/)
- [myCompiler.io](https://www.mycompiler.io/new/deno)
- [Repl.it](https://repl.it/languages/deno)

## Modules

__NOTICE__：Deno 有一些官方模块，可以在 [deno_std](https://deno.land/std/).
考虑提交给 [deno.land/x](https://deno.land/x/) 注册表.

### Automation
- [autopilot](https://github.com/divy-work/autopilot-deno) - Autopilot - Cross-platform web automation with Deno.

### CLI utils
- [cac](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps.
- [charmd](https://github.com/littletof/charmd) - A simple, extendable markdown renderer for your terminal.
- [chart](https://github.com/maximousblk/chart) - 没有依赖关系的控制台 ASCII 折线图.
- [cli-spinner](https://github.com/ameerthehacker/cli-spinners) - Show spinners in the terminal while running long tasks.
- [cliffy](https://github.com/c4spar/deno-cliffy) - The complete solution for building interactive command-line tools.
- [kia](https://github.com/HarryPeach/kia) - Deno 的简单终端微调器 
- [terminal_images](https://github.com/mjrlowe/terminal_images) -  A Deno module and CLI tool for displaying images in the terminal.

### Database
- [deno_mysql](https://github.com/denodrivers/mysql) - MySQL database driver.
- [deno_mongo](https://github.com/denodrivers/deno_mongo) - MongoDB 数据库驱动程序。
- [redis](https://github.com/denodrivers/redis) - An experimental implementation of redis client for deno.
- [denodb](https://github.com/eveningkid/denodb) - 适用于 Deno 的 MySQL、SQLite、MariaDB、PostgreSQL 和 MongoDB ORM.
- [dndb](https://github.com/denyncrawford/dndb) - 为 Deno 编写的持久且可嵌入的 NoSQL 数据库引擎.
- [dsddb](https://github.com/MaximilianHeidenreich/DsDDB) - 一个使用 JSON 格式的简单的持久键值数据库.
- [dso](https://github.com/manyuanrong/dso) - A simple ORM library based on mysql.
- [postgres](https://github.com/denodrivers/postgres) - PostgreSQL 数据库驱动程序.
- [sql-builder](https://github.com/manyuanrong/sql-builder) - 一个 sql 查询生成器.
- [maxminddb](https://github.com/josh-hemphill/maxminddb-deno) - 允许使用 MaxmindDB geoIP 数据库文件的库
- [cotton](https://github.com/rahmanfadhil/cotton) - SQL Database Toolkit for deno
- [yongo](https://github.com/yooneskh/yongo) - Subset of Mongoose api in deno (like populate) but will not fully copy mongoose

### Editor framework

- [Denops](https://github.com/vim-denops/denops.vim) - 🐜 An ecosystem to write Vim/Neovim plugins with Deno.

### Frontend development
- [postcss](https://github.com/postcss/postcss-deno) - 使用 JS 插件转换样式的工具.

### Frontend framework
- [aleph.js](https://github.com/postui/aleph.js) - A React framework in Deno, inspired by [Next.js](https://nextjs.org).

### Image
- [ImageScript](https://github.com/matmen/ImageScript) - JavaScript 中的图像处理，利用 WebAssembly 来提高性能.

### Logging
- [gardens](https://github.com/partheseas/gardens) - A useful logging utility for JavaScript everywhere.

### Mail
- [deno-smtp](https://github.com/manyuanrong/deno-smtp) - deno 的 smtp 邮件发件人.

### Markdown
- [marked](https://github.com/denolib/marked/) - Markdown-to-HTML converter.

### String utils
- [camelcase](https://github.com/denolib/camelcase) - 将破折号/点/下划线/空格分隔的字符串转换为驼峰式：foo-bar → fooBar.
- [deno_case_style](https://github.com/zekth/deno_case_style)  - 不同案例风格的字符串验证器和格式化程序. 例如：camelCase 等.
- [deno-prettystring](https://github.com/OnikurYH/deno-prettystring) - Format, trim and remove extra white spaces between characters from string.
- [deno-slugify](https://github.com/jcardama/deno_slugify) - A string slugifier for deno.
- [normalize_diacritics](https://github.com/motss/deno_mod/tree/master/normalize_diacritics) - Remove accents/diacritics in string.

### Template engine
- [dejs](https://github.com/syumai/dejs) - Ejs template engine for deno.
- [deno_tiny_templates](https://github.com/zekth/deno_tiny_templates) - Template renderer for deno.
- [eta](https://github.com/eta-dev/eta) - Fast, lightweight, and configurable embedded template engine.
- [handlebars](https://github.com/alosaur/handlebars) - Handlebars template engine for deno
- [mustache](https://github.com/alosaur/mustache) - Mustache template engine for deno

### Testing
- [deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert) - deno 的多彩 assertEqual.
- [deno-puppeteer](https://github.com/lucacasonato/deno-puppeteer) - 提供高级 API 以通过 DevTools 协议控制 Chromium 或 Chrome 的库.
- [expect](https://github.com/allain/expect) - Helpers for writing jest like expect tests in deno.
- [merlin](https://github.com/crewdevio/merlin) - deno 的测试和基准测试框架‍♂️
- [pretty_benching](https://github.com/littletof/prettyBenching) - 一个小型库，可让您的 Deno 基准测试进度和结果看起来很漂亮.
- [rhum](https://github.com/drashland/rhum) - Deno 的轻量级测试框架.
- [superdeno](https://github.com/asos-craigmorten/superdeno) - 用于测试 Deno HTTP 服务器的超级代理驱动库.
- [superoak](https://github.com/asos-craigmorten/superoak) - HTTP assertions for Oak made easy via SuperDeno.
- [tincan](https://github.com/gcaptn/tincan) - Deno 的类似 Jest 的测试库.
- [unexpected](https://github.com/unexpectedjs/unexpected) - 可扩展的 BDD 断言工具包.

### Utils
- [buckets](https://github.com/jacoborus/deno-buckets) - Bundle assets and scripts in a single executable file.
- [bytes_formater](https://github.com/manyuanrong/bytes_formater) - Format bytes (Uint8Array, ArrayBufferView, etc) output, useful when debugging IO functions.
- [coffee](https://github.com/irandeno/coffee) - Deno Configuration - a type-safe, easy to use Deno config manager.
- [computed_types](https://github.com/neuledge/computed-types) - Joi like validators for Typescript and Deno.
- [dcc](https://github.com/BoltDoggy/deno#dcc) - Deno Cache Clean, reloading deps when next running.
- [denon](https://github.com/denosaurs/denon/blob/master/mod.ts) - 带有等待生成器的文件观察器.
- [deno-config](https://github.com/yooneskh/deno-config) - Utility to streamline deno app configuration management through cli, .env and json files
- [deno-context](https://github.com/code-hex/deno-context) - Propagate deadlines, a cancellation and other request-scoped values to multiple promise. The behaviour is like Go's context.
- [deno_cron](https://github.com/rbrahul/deno_cron) - 一个 cron 作业调度程序，允许您以极大的灵活性编写人类可读的 cron 语法
- [deno-deamon](https://github.com/manyuanrong/deno-deamon) - 让 Deno 程序在后台运行.
- deno-dotenv
  - [pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv) deno 的 Dotenv 动作.
  - [cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv) - 从 .env 为 Deno 项目加载环境变量.
- [deno-fnparse](https://github.com/hashrock/deno-fnparse) - An extremely simple parser combinator for JavaScript.
- [deno-globrex](https://github.com/hayd/deno-globrex) - globrex 到 deno 的端口，glob 到正则表达式.
- [deno_notify](https://github.com/PandawanFr/deno_notify) - 在所有平台上发送桌面通知.
- [deno-opn](https://github.com/hashrock/deno-opn)  - 打开网站、文件、可执行文件等内容. 跨平台.
- [deno-plugin-prepare](https://github.com/manyuanrong/deno-plugin-prepare) - 用于管理 Deno 原生插件依赖项的库.
- [deno_random_interval](https://github.com/zekth/deno_random_interval) - 帮助生成随机间隔.
- [deno_tokenizer](https://github.com/eliassjogreen/deno_tokenizer) - deno 的简单标记器.
- [deno-using](https://github.com/hayd/deno-using) - 带有 deno 语句的 python 样式.
- [dinoenv](https://deno.land/x/dinoenv) - 使用 deno 管理环境变量的微型库.
- [ensure](https://github.com/eankeen/ensure) - 确保您运行的是 Deno、Typescript 或 V8 的最低版本.
- [evt](https://github.com/garronej/evt) - Type safe replacement for EventEmitter.
- [fastest-validator](https://github.com/icebob/fastest-validator) - 所有 javascript 平台的模式验证器 
- [fossil](https://github.com/matteocrippa/fossil) - 值类型验证套件.
- [garn-yaml](https://github.com/jupegarnica/garn-yaml) - Read or write yaml interpolating env variables.
- [garn-validator](https://github.com/jupegarnica/garn-validator) - 轻松创建验证.
- [invert-kv](https://github.com/denorg/invert-kv) - Invert key-value pairs in Deno.
- [lazy](https://github.com/luvies/lazy) - 类似 linq 的惰性求值迭代模块.
- [maze_generator](https://github.com/mjrlowe/maze_generator) - Javascript module for generating, solving, analyzing and displaying mazes.
- [ms](https://github.com/denolib/ms) - 轻松将各种时间格式转换为毫秒.
- [online](https://github.com/denorg/online) - 检查您当前是否在 Deno 在线.
- [optionals](https://github.com/OliverBrotchie/optionals) - 类似 Rust 的错误处理和具有详尽模式匹配的选项.
- [qrcode](https://github.com/denorg/qrcode) - Deno 的 QR 码图像生成器.
- [recursive-readdir](https://github.com/denorg/recursive-readdir) - 在 Deno 中递归读取目录.
- [rubico](https://github.com/richytong/rubico) - 🏞 [a]synchronous function composition; it just works.
- [solc](https://github.com/deno-web3/solc) - Deno 的 Solidity 绑定.
- [type-fest](https://github.com/denoserverless/type-fest) - 基本 TypeScript 类型的集合（sindresorhus/type-fest 的端口）.
- [wasm-gzip](https://github.com/manyuanrong/wasm_gzip) - 为 Deno 加密和解密 gzip.
- [watch](https://github.com/jinjor/deno-watch) - 文件观察者.
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js) - A diff library to compute differences between two slices using wu(the O(NP)) algorithm.

### Web framework
- [abc](https://github.com/zhmushan/abc) - A better Deno framework to create web application.
- [alosaur](https://github.com/alosaur/alosaur) - Alosaur - 具有许多装饰器的 Deno Web 框架.
- [attain](https://github.com/aaronwlee/Attain) - A middleware web framework for Deno which is using http standard library inspired by express and Oak. Fast and stable with proper memory usage.
- [aqua](https://github.com/l2ig/aqua) - Deno 的最小且快速的 Web 框架.
- [deno-express](https://github.com/NMathar/deno-express) - Node Express ported to Deno.
- [denotrain](https://github.com/Caesar2011/denotrain) - All-in-One web framework like express or fastify for Node.js with middleware support.
- [dinatra](https://github.com/syumai/dinatra) - Sinatra 喜欢用于 deno 的轻量级 Web 应用程序框架.
- [doa](https://github.com/johannlai/doa) - A middleware framework for Deno's http serve🦕. Transplanted from Koa with ❤️
- [drash](https://github.com/drashland/deno-drash) - Deno 的 HTTP 服务器的 REST 微框架，具有零依赖性.
- [dragon](https://github.com/xanny-projects/dragon) - ⚡一个强大的 HTTP 路由器和 URL 匹配器，用于使用 Dragon 构建 Deno Web 服务器.
- [microraptor](https://github.com/matteocrippa/microraptor) - Lightweight framework for easy network routing with validation.
- [oak](https://github.com/oakserver/oak) - A middleware framework for Deno's net server.
  - [oak-http-proxy](https://github.com/asos-craigmorten/oak-http-proxy) - Deno Oak HTTP 服务器的代理中间件.
- [opine](https://github.com/asos-craigmorten/opine) - 从 ExpressJS 移植的快速、简约的 Web 框架.
  - [opine-http-proxy](https://github.com/asos-craigmorten/opine-http-proxy) - Proxy middleware for Deno Opine HTTP servers.
- [pogo](https://github.com/sholladay/pogo) - Deno 的服务器框架.
- [servest](https://github.com/keroxp/servest) - 渐进式 HTTP 服务器/路由器.

### WebSocket
- [deno-websocket](https://github.com/ryo-ma/deno-websocket) - 🦕A simple WebSocket library like ws of node.js library.
- [dropper](https://github.com/denyncrawford/dropper-deno) - Custom event-based WebSockets framework for building real-time apps on Deno 🦕
- [websocket_server](https://github.com/JohanWinther/websocket_server) - WebSocket 服务器库.
- [sockets](https://github.com/drashland/sockets) - Deno 的 WebSocket 库.

### Web utils
- [compression](https://github.com/deno-libs/compression) - Deno HTTP compression middleware.
- [djwt](https://github.com/timonson/djwt) - Make JSON Web Tokens (JWT) on Deno based on JWT and JWS specifications.
- [forwarded](https://github.com/deno-libs/forwarded) - Deno port of `forwarded` library.
- [gentleRpc](https://github.com/timonson/gentleRpc) - 适用于 Deno 和浏览器的 JSON-RPC 2.0 TypeScript 库.
- [gql](https://github.com/deno-libs/gql) - Universal GraphQL HTTP middleware.
- [graphql-tag](https://github.com/deno-libs/graphql-tag) - 来自模板文字的 GraphQL 模式 AST.
- [nats](https://github.com/nats-io/nats.deno) - A Deno client for the [NATS messaging system](https://nats.io/).
- [obsidian](https://github.com/oslabs-beta/obsidian) - 原生 GraphQL 缓存客户端和服务器模块.
- [qs](https://github.com/denolib/qs) - A query string parser with nesting support.
- [router](https://github.com/zhmushan/router) - A high-performance basic router works anywhere.
- [status](https://github.com/denosaurs/status) - Deno 的 HTTP 代码和状态实用程序.
- [ts-prometheus](https://github.com/marcopacini/ts-prometheus) - A prometheus client.
- [up](https://github.com/denorg/up) - Check if a website is up in Deno.
- [youtube-deno](https://github.com/akshgpt7/youtube-deno) - 用于与 YouTube 进行任何交互的 YouTube 数据 API 的 Deno 客户端库.

### Webview
- [webview](https://github.com/eliassjogreen/deno_webview) - 用于 webview 的 Deno 绑定，这是一个用于创建基于 Web 的桌面 GUI 的小型库.

### XML
- [deno-xml-parser](https://github.com/nekobato/deno-xml-parser) - Deno XML parser ported from segmentio/xml-parser.
- [sax-ts](https://github.com/Maxim-Mazurok/sax-ts) - SAX-style XML parser ported from [sax-js](https://github.com/isaacs/sax-js).

## Registries

- [crux.land](https://crux.land/) - 用于托管小型（&lt; 10kB）单个 deno 脚本的免费注册服务.
- [Deno PKG](https://denopkg.com/) - 在你的 Deno 项目中使用来自 GitHub 的代码的更简单方法.
- [deno.land/x/](https://deno.land/x/) - 官方的第 3 方模块注册表.
- [nest.land](https://nest.land) - An immutable, blockchain powered Deno package registry. 🥚

## Showcases

- [AuthCompanion](https://github.com/pmprosociety/authcompanion) - 基于令牌的用户管理服务器.
- [Deno Rest](https://github.com/vicky-gonsalves/deno_rest) - deno RESTful api 的样板。
- [Deno Seed](https://github.com/tamasszoke/deno-seed) - Complete boilerplate for development. :seedling:
- [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy) - 🏆 Add dynamically generated GitHub Trophy on your readme
- [UsingDeno](https://usingdeno.com) - Curated list of Web Applications & Projects using Deno 🦕.

## Tools

- [commands](https://github.com/buttercubz/commands) - 为 node js 和 deno 创建命令快捷方式
- [clone](https://github.com/ekaragodin/clone) - A simple utility for the convenient clone.
- [decense](https://github.com/vinliao/decense) - Generate a license with one `deno run` command.
- [dedep](https://github.com/egoist/dedep) - Manage dependency versions.
- [denoflow](https://github.com/denoflow/denoflow) - 配置为代码，使用 YAML 编写在 Deno 上运行的自动化工作流，使用任何 Deno 模块、Typescript/Javascript 代码
- [denoget](https://github.com/syumai/denoget) - Denoget installs executable Deno script.
- [denoify](https://github.com/garronej/denoify) - 对于希望支持 Deno 但不想编写和维护端口的 NPM 模块作者.
- [denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit) - Denoinit 为 Deno 项目生成有用的文件.
- [denoliver](https://github.com/joakimunge/denoliver) - A simple, dependency free file server with live reload.
- [denomander](https://github.com/siokas/denomander) - 受commander.js 启发的Deno 命令行界面.
- [denon](https://github.com/denosaurs/denon) - A daemon script runner, like nodemon. Built in and for Deno.
- [denopkg](https://github.com/denopkg/denopkg.com) - 在你的 Deno 项目中使用来自 GitHub 的代码的更简单方法.
- [denoversion](https://github.com/lucascaro/denoversion) - SemVer and git version management for Deno.
- [denox](https://github.com/BentoumiTech/denox) - Like packages.json scripts, but for Deno with permissions support.
- [deno.mk](https://github.com/MarkTiedemann/deno.mk) - Cross-platform Makefile for installing and running Deno.
- maxmcd's [deno-docker](https://github.com/maxmcd/deno-docker) A docker image.
- 海德 [deno-docker](https://github.com/hayd/deno-docker) Several docker images.
- [deno-vscode](https://github.com/ameerthehacker/deno-vscode) - Leverage the typedef and intellisense built into vscode using this extension.
- [dev_server](https://github.com/zhmushan/dev_server) - 让 TypeScript 文件直接在 script 标签中使用.
- [dmm](https://github.com/drashland/dmm) - Lightweight Deno Module Manager
- [dpm](https://github.com/BoltDoggy/deno#dpm)  - Deno 包管理器，为 deno 安装全局命令. 像 denoget.
- dvm
  - [justjavac/dvm](https://github.com/justjavac/dvm) - Deno Version Manager: manage multiple active Deno versions.
  - [axetroy/dvm](https://github.com/axetroy/dvm) - Version manger for Deno without runtime dependencies.
  - [dvm.cmd](https://github.com/MarkTiedemann/dvm.cmd) - Deno Version Manager for Windows. Written as a single batch file.
  - [ghosind/dvm](https://github.com/ghosind/dvm) - A lightweight Deno Version Manager for Linux/MacOS.
- [elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload) - An elm live reloader written in Deno.
- [kopo-cli](https://github.com/littletof/kopo-cli) - A Deno registry browser in the terminal.
- [lume](https://github.com/lumeland/lume) - A static site generator similar to Jekyll or Eleventy with support for multiple file formats.
- [make-deno-edition](https://github.com/bevry/make-deno-edition) - 自动使 package.json 项目（例如 npm 包和 node.js 模块）与 Deno 兼容.
- [nessie](https://github.com/halvardssm/deno-nessie) - Create, migrate and rollback migrations for PostgreSQL, MySQL and SQLite.
- [packer-provisioner-deno](https://github.com/dontlaugh/packer-provisioner-deno) - A Packer plugin that makes it easy to build virtual machine images with Deno scripts.
- [pagic](https://github.com/xcatliu/pagic) - The easiest way to generate static html page from markdown, built with Deno.
- [pika Deno plugin](https://github.com/pikapkg/builders/tree/master/packages/plugin-build-deno/)
- [pre-commit-deno](https://github.com/nozaq/pre-commit-deno) - pre-commit git hooks for Deno projects.
- [starter](https://github.com/denorg/starter) - 带有 GitHub Actions CI 的 Deno 模块入门模板
- [task-runner](https://github.com/jinjor/deno-task-runner) - 像 npm 脚本一样编写任务.
- [trex](https://github.com/crewdevio/Trex) - 包管理，如用于 deno 的 npm.
- [typescript-deno-plugin](https://github.com/justjavac/typescript-deno-plugin) - Deno language service plugin, providing intellisense in TypeScript files within editors.
- [udd](https://github.com/hayd/deno-udd) - 更新 Deno 依赖项：将导入语句更新为其最新发布的版本.
- [velociraptor](https://github.com/umbopepato/velociraptor) - Deno 的 npm 风格的脚本运行器.
- [vscode-deno](https://github.com/denoland/vscode_deno) - 使用“TypeScript Deno 语言服务插件”提供 Deno 支持的 VS Code 扩展.
- [Update Deno](https://github.com/marketplace/actions/update-deno) - 将具有最新 Deno 版本的文件放入存储库的 Github 操作.
- [denofn-selfhosted](https://github.com/denofn/denofn-selfhosted) - Self-hosted Deno functions, made with Deno and Docker.

## Articles

- [Develop with Deno and Visual Studio Code](https://medium.com/@kitsonk/develop-with-deno-and-visual-studio-code-225ce7c5b1ba)
- [First thoughts on Deno, the JavaScript/TypeScript run-time](https://43081j.com/2019/01/first-look-at-deno)
- [Getting started with Deno](https://dev.to/wuz/getting-started-with-deno-e1m)
- [What's Deno, and how is it different from Node.js?](https://dev.to/bnevilleoneill/what-s-deno-and-how-is-it-different-from-node-js-366g)
- [Write a small API using Deno](https://dev.to/kryz/write-a-small-api-using-deno-1cl0)
- [Deno on Cloud Run](https://medium.com/google-cloud/deno-on-cloud-run-89ae64d1664d)
- [Learn Deno: Chat app](https://aralroca.com/blog/learn-deno-chat-app)
- [From Node to Deno](https://dev.to/aralroca/from-node-to-deno-5gpn)
- [Create a simple Note-taking app with Deno](https://dev.to/jeferson_sb/create-a-simple-note-taking-app-with-deno-3k7g)
- [Develop and Dockerize a Blogging API With Deno, Oak, and MySQL](https://dev.to/fhsinchy/develop-and-dockerize-a-blogging-api-with-deno-oak-and-mysql-170e)
- [Building API's using Deno, Oak and MYSQL](https://codeforgeek.com/building-api-server-using-deno-and-mysql/)
- [Create interactive mail utility CLI Tool using Deno
](https://www.soubai.me/posts/create-interactive-mail-utility-cli-with-deno)
- [Create your first News CLI app using Deno](https://medium.com/javascript-in-plain-english/creating-your-first-news-cli-app-using-deno-e1470398c627)
- [Continuous Integration with Deno](https://semaphoreci.com/blog/continuous-integration-with-deno)
- [How to create and validate JSON Web Tokens in Deno](https://www.loginradius.com/engineering/blog/jwt-authentication-with-deno/)
- [Build A Simple Covid19 CLI Tool using Deno](https://www.loginradius.com/engineering/blog/build-a-cli-tool-using-deno/)
- [Creating a Web Application using Deno](https://www.loginradius.com/engineering/blog/a-webapp-in-deno/)
- [Read and Write in a local file with Deno](https://www.loginradius.com/engineering/blog/read-and-write-in-a-local-file-with-deno/)
- [The Hidden Superpower of Deno: xeval](https://stefanbuck.com/blog/hidden-superpower-deno-xeval)
- [Test coverage in Deno with Codecov and GitHub Actions](https://v1rtl.site/blog/coverage-in-deno)
- 使用 Oak 教程系列的 Deno REST API [0](https://www.robinwieruch.de/deno-tutorial), [1](https://www.robinwieruch.de/deno-oak), [2](https://www.robinwieruch.de/deno-oak-rest-api)
- [Dissecting Deno](https://fettblog.eu/dissecting-deno/)
- [Getting Started with Deno](https://sabe.io/tutorials/getting-started-with-deno)
- [How to deploy a Deno app using Docker](https://sabe.io/tutorials/how-to-deploy-deno-app-docker)

## Presentations

- [10 Things I Regret About Node.js - Ryan Dahl - JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
  - [Slides](https://tinyclouds.org/jsconf2018.pdf)
- [JSDC 2018#A01 - Deno, A New Server-Side Runtime By Ryan Dahl](https://www.youtube.com/watch?v=FlTG0UXRAkE)
  - [Slides](https://tinyclouds.org/deno_jsdc.pptx)
- [Ryan Dahl. Deno, a new way to JavaScript. JS Fest 2019 Spring](https://www.youtube.com/watch?v=z6JRlx5NC9E)
  - [Slides](https://www.slideshare.net/JSFestUA/js-fest-2019-ryan-dahl-deno-a-new-way-to-javascript)
- [Rafał Pocztarski — From Node.js to Deno - JavaScript/TypeScript runtime built with V8 and Rust [EN]](https://www.youtube.com/watch?v=Aib1OZLy0_c)
- [Ryan Dahl: A secure runtime for JavaScript and TypeScript | js.la April 2019](https://www.youtube.com/watch?v=RAmqgbv247s)
  - [Slides](https://docs.google.com/presentation/d/1CSQVTeH5tFzE4AZVXIpx9Xwew5YS-gxJZ03eRFtNeIc/edit)
- [Ryan Dahl: Deno, a new way to JavaScript - HolyJS 2019 Piter](https://www.youtube.com/watch?v=HjdJzNoT_qg)
  - [Slides](https://docs.google.com/presentation/d/1BjvZx5S8noVfFINptH4jfKfqh9jB9nXlFC0I3oIDtg4/edit)
- [Rafał Pocztarski - What is Deno? A new runtime for modern JavaScript and TypeScript backends for 2020s - Deno Warsaw](https://www.youtube.com/watch?v=aI5A9zvYSjk)
- [Michał Sabiniarz - How to contribute to Deno? - Deno Warsaw](https://www.youtube.com/watch?v=LAtjnKLbPpw)
  - [Slides](https://docs.google.com/presentation/d/1rETgslJS1ks4EihzLpUI3sS_zI46YxAOuQ5B1Z_k1mY/edit?usp=sharing)
- [Bartek Iwańczuk - Deno internals, how modern runtime is built - Deno Warsaw](https://www.youtube.com/watch?v=qt7fbmypAFk)
  - [Slides](https://docs.google.com/presentation/d/1LYNGpyjx9PemL-P__7hVC8mSqkX-jL8VQLMhCRehy00/edit?usp=sharing)
- [Ryan Dahl & Kitson Kelly: Deno is a New Way to JavaScript - TSConf 2019](https://www.youtube.com/watch?v=1gIiZfSbEAE)
- [Bert Belder - Deno - dotJS 2019](https://www.youtube.com/watch?v=puXyo1jGQys)
- [Kitson P. Kelly - Deno, and The Future of JavaScript Runtimes - CityJS Conf 2020](https://www.youtube.com/watch?v=2eRyZpX4qvI)
- [Matías Insaurralde - Deno: an experimental approach on V8 interoperability [EN subtitles] - NodeConf Argentina 2019](https://www.youtube.com/watch?v=N0BRE-0n2cU)
  - [Slides](https://speakerdeck.com/matiasinsaurralde/deno-an-experimental-approach-on-v8-interoperability)
## Resources in Other Languages

### Chinese

- [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)
- [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)
- [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)
- [Design Mistakes in Node zh-CN](https://zhuanlan.zhihu.com/p/37637923)
- [Node之父ry：Node中的设计错误](https://mp.weixin.qq.com/s/7XAiYw18c8YZc-fXk0-wrw)
- [《Deno进阶开发笔记》](https://github.com/chenshenhai/deno_note/)
- [Deno 手册](https://github.com/Nugine/deno-manual-cn/)
- [Deno 中文开发者社区](https://deno.js.cn)

### Hebrew

- [Deno intro in Hebrew (slides in English)](https://www.youtube.com/watch?v=9tJ_LkI6_qw)

### Indonesian

- [Berkenalan dengan Deno](https://medium.com/@redhajuanda/berkenalan-dengan-dengan-deno-c48cdf3aa31e)
- [Perkenalan Deno dan Instalasi](https://youtu.be/V_kpUTJSd9c)
- [Deno Land Indonesia website](https://denoland.id/)
- [Deno Land Indonesia Telegram group](https://t.me/deno_id)

### Italian

- [Deno - L'anagramma di Node](https://www.slideshare.net/FrancescoSciuti/deno-lanagramma-di-node)

### Japanese

- [Node.js における設計ミス By Ryan Dahl](https://yosuke-furukawa.hatenablog.com/entry/2018/06/07/080335)
- [mizchi/deno_code_reading.md](https://gist.github.com/mizchi/31e5628751330b624a0e8ada9e739b1e)
- [Design Mistakes in Node & Deno #kng5 / deno](https://speakerdeck.com/masashi/deno)
- [Dive into Deno：プロセス起動からTypeScriptが実行されるまで](https://blog.leko.jp/post/code-reading-of-deno-boot-process/)

### Korean

- [denoland.kr/](https://denoland.kr/)

### Russian

- [Telegram channel](https://t.me/denoland_ru)
- [Telegram chat](https://t.me/denoland)

### Spanish

- [Hola Deno! . 🦕](https://medium.com/javascript-espa%C3%B1ol/hola-deno-f31f9f6f2c84)
- [Así puedes crear tu primera API REST con Deno](https://medium.com/@mpampols/as%C3%AD-puedes-crear-tu-primera-api-rest-con-deno-a9094ee5c0b2)
- [Primeros pasos con Deno 🦕 El sucesor de NodeJS desarrollado con Rust y TypeScript](https://medium.com/@manurua/primeros-pasos-con-deno-el-nuevo-nodejs-desarrollado-con-rust-y-typescript-b9ac14f7d0c7)
- [Primer vistazo con deno](https://dev.to/buttercubz/first-look-with-deno-spanish-30dh)

### Darija

- [A first look at Deno | BlaBlaConf 2021 🇲🇦](https://www.youtube.com/watch?v=Y_etUvzAa4s) 
