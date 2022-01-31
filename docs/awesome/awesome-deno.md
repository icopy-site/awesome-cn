<div class="github-widget" data-repo="denolib/awesome-deno"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Deno [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/denolib/awesome-deno/master/deno-logo.png" align="right" width="100">](https://deno.land)

Deno 是一个简单、现代且安全的 JavaScript 和 TypeScript 运行时，它使用 V8 并内置于 Rust.

This list is a collection of the best Deno modules and resources.



## Docs

### Official Docs

- [Official Site](https://deno.land)
- [Deno API Reference](https://doc.deno.land/builtin/stable)
  - [Deno Unstable API Reference](https://doc.deno.land/builtin/unstable)
- [Deno Manual](https://deno.land/manual)

### External Docs

- [V8 Docs for Deno](https://denolib.github.io/v8-docs/)
- [DenoBeginner.com](https://DenoBeginner.com) - 面向初学者的完全免费的 deno 速成课程.

### Online Playgrounds

- [deno.town](https://deno.town)
- [Deno Playground](https://deno-playground.now.sh)
  - [maman/deno-playground](https://github.com/maman/deno-playground)
- [DenoBR Playground](https://playground.denobr.com/)
- [myCompiler.io](https://www.mycompiler.io/new/deno)
- [Repl.it](https://repl.it/languages/deno)

## Modules

__NOTICE__: Deno has a few official modules that could be found at [deno_std](https://deno.land/std/).
考虑提交给 [deno.land/x](https://deno.land/x/) registry.

### Automation
- [autopilot](https://github.com/divy-work/autopilot-deno) - Autopilot - Cross-platform web automation with Deno.

### CLI utils
- [cac](https://github.com/cacjs/cac) - 用于构建命令行应用程序的简单而强大的框架.
- [charmd](https://github.com/littletof/charmd) - A simple, extendable markdown renderer for your terminal.
- [chart](https://github.com/maximousblk/chart) - Console ASCII line charts with no dependencies.
- [cli-spinner](https://github.com/ameerthehacker/cli-spinners) - 运行长任务时在终端中显示微调器.
- [cliffy](https://github.com/c4spar/deno-cliffy) - 构建交互式命令行工具的完整解决方案.
- [kia](https://github.com/HarryPeach/kia) - Simple terminal spinners for Deno 🦕
- [terminal_images](https://github.com/mjrlowe/terminal_images) - 用于在终端中显示图像的 Deno 模块和 CLI 工具.

### Database
- [deno_mysql](https://github.com/denodrivers/mysql) - MySQL 数据库驱动程序.
- [deno_mongo](https://github.com/denodrivers/deno_mongo) - MongoDB 数据库驱动程序.
- [redis](https://github.com/denodrivers/redis) - 用于 deno 的 redis 客户端的实验性实现.
- [denodb](https://github.com/eveningkid/denodb) - MySQL, SQLite, MariaDB, PostgreSQL and MongoDB ORM for Deno.
- [dndb](https://github.com/denyncrawford/dndb) - Persistent and embedable NoSQL database engine written for Deno 🦕.
- [dsddb](https://github.com/MaximilianHeidenreich/DsDDB) - A dead simple persistant key-value database utilizing the JSON format.
- [dso](https://github.com/manyuanrong/dso) - 基于 mysql 的简单 ORM 库.
- [postgres](https://github.com/denodrivers/postgres) - Driver for PostgreSQL database.
- [sql-builder](https://github.com/manyuanrong/sql-builder) - An sql query builder.
- [maxminddb](https://github.com/josh-hemphill/maxminddb-deno) - A library that enables the usage of MaxmindDB geoIP database files
- [cotton](https://github.com/rahmanfadhil/cotton) - 用于 deno 的 SQL 数据库工具包
- [yongo](https://github.com/yooneskh/yongo) - deno 中的 Mongoose api 子集（如填充）但不会完全复制 mongoose

### Editor framework

- [Denops](https://github.com/vim-denops/denops.vim) - 使用 Deno 编写 Vim/Neovim 插件的生态系统.

### Frontend development
- [postcss](https://github.com/postcss/postcss-deno) - A tool for transforming styles with JS plugins.

### Frontend framework
- [aleph.js](https://github.com/postui/aleph.js) - Deno 中的 React 框架，灵感来自 [Next.js](https://nextjs.org).

### Image
- [ImageScript](https://github.com/matmen/ImageScript) - Image processing in JavaScript, utilizing WebAssembly for performance.

### Logging
- [gardens](https://github.com/partheseas/gardens) - 适用于任何地方的 JavaScript 的有用日志记录实用程序.

### Mail
- [deno-smtp](https://github.com/manyuanrong/deno-smtp) - A smtp mail sender for deno.

### Markdown
- [marked](https://github.com/denolib/marked/) - Markdown 到 HTML 转换器.

### String utils
- [camelcase](https://github.com/denolib/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [deno_case_style](https://github.com/zekth/deno_case_style) - String validator and formater for different case style. eg: camelCase etc.
- [deno-prettystring](https://github.com/OnikurYH/deno-prettystring) - 格式化、修剪和删除字符串中字符之间的多余空格.
- [deno-slugify](https://github.com/jcardama/deno_slugify) - A string slugifier for deno.
- [normalize_diacritics](https://github.com/motss/deno_mod/tree/master/normalize_diacritics) - Remove accents/diacritics in string.

### Template engine
- [dejs](https://github.com/syumai/dejs) - 用于 deno 的 Ejs 模板引擎.
- [deno_tiny_templates](https://github.com/zekth/deno_tiny_templates) - Template renderer for deno.
- [eta](https://github.com/eta-dev/eta) - 快速、轻量级和可配置的嵌入式模板引擎.
- [handlebars](https://github.com/alosaur/handlebars) - deno 的车把模板引擎
- [mustache](https://github.com/alosaur/mustache) - deno 的 Mustache 模板引擎

### Testing
- [deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert) - A colorful assertEqual for deno.
- [deno-puppeteer](https://github.com/lucacasonato/deno-puppeteer) - A library which provides a high-level API to control Chromium or Chrome over the DevTools Protocol.
- [expect](https://github.com/allain/expect) - 编写笑话的助手，例如在 deno 中的期望测试.
- [merlin](https://github.com/crewdevio/merlin) - Testing and Benchmarking framework for deno 🧙‍♂️
- [pretty_benching](https://github.com/littletof/prettyBenching) - A small library to make your Deno benchmarking progress and results look pretty.
- [rhum](https://github.com/drashland/rhum) - A lightweight testing framework for Deno.
- [superdeno](https://github.com/asos-craigmorten/superdeno) - Super-agent driven library for testing Deno HTTP servers.
- [superoak](https://github.com/asos-craigmorten/superoak) - 通过 SuperDeno 轻松实现 Oak 的 HTTP 断言.
- [tincan](https://github.com/gcaptn/tincan) - A Jest-like testing library for Deno.
- [unexpected](https://github.com/unexpectedjs/unexpected) - Extensible BDD assertion toolkit.

### Utils
- [buckets](https://github.com/jacoborus/deno-buckets) - Bundle assets and scripts in a single executable file.
- [bytes_formater](https://github.com/manyuanrong/bytes_formater) - 格式化字节（Uint8Array、ArrayBufferView 等）输出，在调试 IO 函数时很有用.
- [coffee](https://github.com/irandeno/coffee) - Deno Configuration - a type-safe, easy to use Deno config manager.
- [computed_types](https://github.com/neuledge/computed-types) - Joi 喜欢 Typescript 和 Deno 的验证器.
- [dcc](https://github.com/BoltDoggy/deno#dcc) - Deno Cache Clean，下次运行时重新加载 deps.
- [denon](https://github.com/denosaurs/denon/blob/master/mod.ts) - A file watcher with a for-await generator.
- [deno-config](https://github.com/yooneskh/deno-config) - 通过 cli、.env 和 json 文件简化 deno 应用程序配置管理的实用程序
- [deno-context](https://github.com/code-hex/deno-context)  - 将截止日期、取消和其他请求范围的值传播到多个承诺. 这种行为就像 Go 的上下文.
- [deno_cron](https://github.com/rbrahul/deno_cron) - A cron Job scheduler that allows you to write human readable cron syntax with tons of flexibility
- [deno-deamon](https://github.com/manyuanrong/deno-deamon) - Make the Deno program run in the background.
--deno-dotenv
  - [pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv) - Dotenv handling for deno.
  - [cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv) - Loads environment variables from .env for Deno projects.
- [deno-fnparse](https://github.com/hashrock/deno-fnparse) - 一个非常简单的 JavaScript 解析器组合器.
- [deno-globrex](https://github.com/hayd/deno-globrex) - Port of globrex to deno, glob to regular expression.
- [deno_notify](https://github.com/PandawanFr/deno_notify) - Send desktop notifications on all platforms.
- [deno-opn](https://github.com/hashrock/deno-opn) - Opens stuff like websites, files, executables. Cross-platform.
- [deno-plugin-prepare](https://github.com/manyuanrong/deno-plugin-prepare) - A library for managing Deno native plugin dependencies.
- [deno_random_interval](https://github.com/zekth/deno_random_interval) - Helper to generate random interval.
- [deno_tokenizer](https://github.com/eliassjogreen/deno_tokenizer) - A simple tokenizer for deno.
- [deno-using](https://github.com/hayd/deno-using) - An python-style with statements for deno.
- [dinoenv](https://deno.land/x/dinoenv) - tiny library to manage environment variables with deno.
- [ensure](https://github.com/eankeen/ensure) - Ensure you are running a minimum version of Deno, Typescript, or V8.
- [evt](https://github.com/garronej/evt) - 键入 EventEmitter 的安全替换.
- [fastest-validator](https://github.com/icebob/fastest-validator) - Schema validator for all javascript platforms 
- [fossil](https://github.com/matteocrippa/fossil) - A value-type validation suite.
- [garn-yaml](https://github.com/jupegarnica/garn-yaml) - 读取或写入 yaml 插值环境变量.
- [garn-validator](https://github.com/jupegarnica/garn-validator) - Create validations with ease.
- [invert-kv](https://github.com/denorg/invert-kv) - 在 Deno 中反转键值对.
- [lazy](https://github.com/luvies/lazy) - A linq-like lazy-evaluation iteration module.
- [maze_generator](https://github.com/mjrlowe/maze_generator) - 用于生成、解决、分析和显示迷宫的 Javascript 模块.
- [ms](https://github.com/denolib/ms) - Easily convert various time formats to milliseconds.
- [online](https://github.com/denorg/online) - Check if you're currently online in Deno.
- [optionals](https://github.com/OliverBrotchie/optionals) - Rust-like error handling and options with exhaustive pattern matching.
- [qrcode](https://github.com/denorg/qrcode) - QR code image generator for Deno.
- [recursive-readdir](https://github.com/denorg/recursive-readdir) - Recursively read directories in Deno.
- [rubico](https://github.com/richytong/rubico)  - [a]同步函数组合； 它只是工作.
- [solc](https://github.com/deno-web3/solc) - 💎 Solidity bindings for Deno.
- [type-fest](https://github.com/denoserverless/type-fest) - A collection of essential TypeScript types (port of sindresorhus/type-fest).
- [wasm-gzip](https://github.com/manyuanrong/wasm_gzip) - Encrypt and decrypt gzip for Deno.
- [watch](https://github.com/jinjor/deno-watch) - A file watcher.
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js) - 使用 wu（O（NP））算法计算两个切片之间差异的差异库.

### Web framework
- [abc](https://github.com/zhmushan/abc) - 一个更好的 Deno 框架来创建 Web 应用程序.
- [alosaur](https://github.com/alosaur/alosaur) - Alosaur - Deno web framework with many decorators.
- [attain](https://github.com/aaronwlee/Attain)  - Deno 的中间件 Web 框架，它使用受 express 和 Oak 启发的 http 标准库. 使用适当的内存快速稳定.
- [aqua](https://github.com/l2ig/aqua) - A minimal and fast web framework for Deno.
- [deno-express](https://github.com/NMathar/deno-express) - Node Express 移植到 Deno.
- [denotrain](https://github.com/Caesar2011/denotrain) - 多合一 Web 框架，例如用于 Node.js 的 express 或 fastify，具有中间件支持.
- [dinatra](https://github.com/syumai/dinatra) - Sinatra like light weight web app framework for deno.
- [doa](https://github.com/johannlai/doa)  - Deno 的 http 服务的中间件框架. 用 ❤️ 从 Koa 移植
- [drash](https://github.com/drashland/deno-drash) - A REST microframework for Deno's HTTP server with zero dependencies.
- [dragon](https://github.com/xanny-projects/dragon) - ⚡A powerful HTTP router and URL matcher for building Deno web servers with dragon 🐲.
- [microraptor](https://github.com/matteocrippa/microraptor) - 轻量级框架，可通过验证轻松实现网络路由.
- [oak](https://github.com/oakserver/oak) - Deno 网络服务器的中间件框架.
  - [oak-http-proxy](https://github.com/asos-craigmorten/oak-http-proxy) - Proxy middleware for Deno Oak HTTP servers.
- [opine](https://github.com/asos-craigmorten/opine) - Fast, minimalist web framework ported from ExpressJS.
  - [opine-http-proxy](https://github.com/asos-craigmorten/opine-http-proxy) - Proxy middleware for Deno Opine HTTP servers.
- [pogo](https://github.com/sholladay/pogo) - Server framework for Deno.
- [servest](https://github.com/keroxp/servest) - A progressive HTTP server/router.

### WebSocket
- [deno-websocket](https://github.com/ryo-ma/deno-websocket) - 一个简单的 WebSocket 库，例如 node.js 库的 ws.
- [dropper](https://github.com/denyncrawford/dropper-deno) - 用于在 Deno 上构建实时应用的自定义基于事件的 WebSockets 框架 
- [websocket_server](https://github.com/JohanWinther/websocket_server) - A WebSocket server library.
- [wocket](https://github.com/drashland/wocket) - A WebSocket library for Deno.

### Web utils
- [compression](https://github.com/deno-libs/compression) - Deno HTTP 压缩中间件.
- [djwt](https://github.com/timonson/djwt) - 根据 JWT 和 JWS 规范在 Deno 上制作 JSON Web Tokens (JWT).
- [forwarded](https://github.com/deno-libs/forwarded) - `forwarded` 库的 Deno 端口.
- [gentleRpc](https://github.com/timonson/gentleRpc) - A JSON-RPC 2.0 TypeScript library for Deno and the browser.
- [gql](https://github.com/deno-libs/gql) - 通用 GraphQL HTTP 中间件.
- [graphql-tag](https://github.com/deno-libs/graphql-tag) - GraphQL schema AST from template literal.
- [nats](https://github.com/nats-io/nats.deno) - 一个 Deno 客户端 [NATS messaging system](https://nats.io/).
- [obsidian](https://github.com/oslabs-beta/obsidian) - A native GraphQL caching client and server module.
- [qs](https://github.com/denolib/qs) - 具有嵌套支持的查询字符串解析器.
- [router](https://github.com/zhmushan/router) - 高性能基本路由器可在任何地方工作.
- [status](https://github.com/denosaurs/status) - HTTP codes and status utility for Deno.
- [ts-prometheus](https://github.com/marcopacini/ts-prometheus) - 一个普罗米修斯客户端.
- [up](https://github.com/denorg/up) - 检查网站是否在 Deno 中启动.
- [youtube-deno](https://github.com/akshgpt7/youtube-deno) - A Deno client library for the YouTube Data API for any interaction with YouTube.

### Webview
- [webview](https://github.com/eliassjogreen/deno_webview) - Deno bindings for webview, a tiny library for creating web-based desktop GUIs.

### XML
- [deno-xml-parser](https://github.com/nekobato/deno-xml-parser) - 从 segmentio/xml-parser 移植的 Deno XML 解析器.
- [sax-ts](https://github.com/Maxim-Mazurok/sax-ts) - 移植自 SAX 样式的 XML 解析器 [sax-js](https://github.com/isaacs/sax-js).

## Registries

- [crux.land](https://crux.land/) - A free registry service meant for hosting small ( < 10kB) single deno scripts.
- [Deno PKG](https://denopkg.com/) - An easier way to use code from GitHub in your Deno project.
- [Denopkg.dev](https://denopkg.dev/) - Use any public/private repository from GitHub/GitLab in your Deno project.
- [deno.land/x/](https://deno.land/x/) - The official 3rd party module registry.
- [nest.land](https://nest.land) - 一个不可变的、由区块链驱动的 Deno 包注册表. 

## Showcases

- [AuthCompanion](https://github.com/pmprosociety/authcompanion) - A token-based user management server.
- [Deno Rest](https://github.com/vicky-gonsalves/deno_rest) - deno RESTful api 的样板。
- [Deno Seed](https://github.com/tamasszoke/deno-seed) - Complete boilerplate for development. :seedling:
- [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy) - 🏆 Add dynamically generated GitHub Trophy on your readme
- [UsingDeno](https://usingdeno.com) - 使用 Deno 的 Web 应用程序和项目的精选列表.

## Tools

- [commands](https://github.com/buttercubz/commands) - Create commands shortcuts for node js and deno
- [clone](https://github.com/ekaragodin/clone) - 方便克隆的简单实用程序.
- [decense](https://github.com/vinliao/decense) - 使用一个 `deno run` 命令生成许可证.
- [dedep](https://github.com/egoist/dedep) - 管理依赖版本.
- [denoflow](https://github.com/denoflow/denoflow) - Configuration as code, use YAML to write automated workflows that run on Deno, with any Deno modules, Typescript/Javascript codes
- [denoget](https://github.com/syumai/denoget) - Denoget 安装可执行的 Deno 脚本.
- [denoify](https://github.com/garronej/denoify) - For NPM module authors that would like to support Deno but do not want to write and maintain a port.
- [denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit) - Denoinit generates useful files for Deno project.
- [denoliver](https://github.com/joakimunge/denoliver) - 一个简单、无依赖的文件服务器，具有实时重新加载功能.
- [denomander](https://github.com/siokas/denomander) - Deno command-line interfaces inspired from commander.js.
- [denon](https://github.com/denosaurs/denon)  - 一个守护程序脚本运行程序，如 nodemon. 为 Deno 内置.
- [denopkg](https://github.com/denopkg/denopkg.com) - An easier way to use code from GitHub in your Deno project.
- [denoversion](https://github.com/lucascaro/denoversion) - Deno 的 SemVer 和 git 版本管理.
- [denox](https://github.com/BentoumiTech/denox) - 与 packages.json 脚本类似，但对于具有权限支持的 Deno.
- [deno.mk](https://github.com/MarkTiedemann/deno.mk) - Cross-platform Makefile for installing and running Deno.
- maxmcd  [deno-docker](https://github.com/maxmcd/deno-docker) 泊坞窗图像.
- hayd's [deno-docker](https://github.com/hayd/deno-docker) 几个泊坞窗图像.
- [deno-vscode](https://github.com/ameerthehacker/deno-vscode) - 使用此扩展利用 vscode 中内置的 typedef 和 intellisense.
- [dev_server](https://github.com/zhmushan/dev_server) - Let TypeScript files be used directly in the script tag.
- [dmm](https://github.com/drashland/dmm) - Lightweight Deno Module Manager
- [dpm](https://github.com/BoltDoggy/deno#dpm) - Deno Package Manager, install global command for deno. like denoget.
- dvm
  - [justjavac/dvm](https://github.com/justjavac/dvm) - Deno 版本管理器：管理多个活动的 Deno 版本.
  - [axetroy/dvm](https://github.com/axetroy/dvm) - 没有运行时依赖的 Deno 版本管理器.
  - [dvm.cmd](https://github.com/MarkTiedemann/dvm.cmd)  - 适用于 Windows 的 Deno 版本管理器. 编写为单个批处理文件.
  - [ghosind/dvm](https://github.com/ghosind/dvm) - A lightweight Deno Version Manager for Linux/MacOS.
- [elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload) - 一个用 Deno 编写的 elm live reloader.
- [kopo-cli](https://github.com/littletof/kopo-cli) - 终端中的 Deno 注册表浏览器.
- [lume](https://github.com/lumeland/lume) - 一个类似于 Jekyll 或 Eleventy 的静态站点生成器，支持多种文件格式.
- [make-deno-edition](https://github.com/bevry/make-deno-edition) - Automatically makes package.json projects (such as npm packages and node.js modules) compatible with Deno.
- [nessie](https://github.com/halvardssm/deno-nessie) - 为 PostgreSQL、MySQL 和 SQLite 创建、迁移和回滚迁移.
- [packer-provisioner-deno](https://github.com/dontlaugh/packer-provisioner-deno) - 一个 Packer 插件，可以轻松使用 Deno 脚本构建虚拟机映像.
- [pagic](https://github.com/xcatliu/pagic) - 从 Markdown 生成静态 html 页面的最简单方法，使用 Deno 构建.
- [pika Deno plugin](https://github.com/pikapkg/builders/tree/master/packages/plugin-build-deno/)
- [pre-commit-deno](https://github.com/nozaq/pre-commit-deno) - pre-commit git hooks for Deno projects.
- [starter](https://github.com/denorg/starter) - Deno module starter template with GitHub Actions CI
- [task-runner](https://github.com/jinjor/deno-task-runner) - Write tasks just like npm scripts.
- [trex](https://github.com/crewdevio/Trex) - Package management like npm for deno.
- [typescript-deno-plugin](https://github.com/justjavac/typescript-deno-plugin) - Deno 语言服务插件，在编辑器中的 TypeScript 文件中提供智能感知.
- [udd](https://github.com/hayd/deno-udd) - Update Deno dependencies: updates import statements to their latest published version.
- [velociraptor](https://github.com/umbopepato/velociraptor) - An npm-style script runner for Deno.
- [vscode-deno](https://github.com/denoland/vscode_deno) - VS Code extension that provides Deno support using the `TypeScript Deno language service plugin`.
- [Update Deno](https://github.com/marketplace/actions/update-deno) - Github Action that puts a file with the latest Deno Version in your repository.
- [denofn-selfhosted](https://github.com/denofn/denofn-selfhosted) - 使用 Deno 和 Docker 制作的自托管 Deno 功能.

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
- Deno REST API with Oak Tutorial Series [0](https://www.robinwieruch.de/deno-tutorial), [1](https://www.robinwieruch.de/deno-oak), [2](https://www.robinwieruch.de/deno-oak-rest-api)
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
- [Matías Insaurralde - Deno：V8 互操作性的实验方法 [英文字幕] - NodeConf Argentina 2019](https://www.youtube.com/watch?v=N0BRE-0n2cU)
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
