<div class="github-widget" data-repo="drobakowski/awesome-erlang"></div>
## Awesome Erlang [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Analytics](https://ga-beacon.appspot.com/UA-82766782-1/awesome-erlang?flat&useReferer)](https://github.com/drobakowski/awesome-erlang)
一个精选的令人惊叹的 Erlang 库、资源和受启发的闪亮事物的列表 [awesome-elixir](https://github.com/h4cc/awesome-elixir).


## Package Management
*用于包和依赖管理的库和工具.*

* [hex.pm](https://hex.pm/) - Erlang 生态系统的包管理器.

## Release Management
*用于发布管理的库和工具.*

* [relx](https://github.com/erlware/relx) - Erlang 的发布汇编程序.

## Configuration Management
*与配置管理相关的库和工具.*

* [stillir](https://github.com/heroku/stillir) - 将环境变量缓存为 Erlang 应用程序变量.

## Codebase Maintenance
*用于维护干净代码库的库和工具.*

* [elvis](https://github.com/inaka/elvis) - Erlang 风格评论家.

## Web Frameworks
*网络开发框架.*

* [Axiom](https://github.com/tsujigiri/axiom) - 受 Ruby 启发的微型框架 [Sinatra](https://github.com/sinatra/sinatra).
* [ChicagoBoss](https://github.com/ChicagoBoss/ChicagoBoss) - 受 Rails 启发并用 Erlang 编写的服务器框架.
* [cowboy](https://github.com/ninenines/cowboy) - 一个简单的 HTTP 服务器.
* [Giallo](https://github.com/kivra/giallo) - 一个小巧灵活的网络框架 [Cowboy](https://github.com/ninenines/cowboy).
* [MochiWeb](https://github.com/mochi/mochiweb) - 用于构建轻量级 HTTP 服务器的 Erlang 库.
* [N2O](https://github.com/synrc/n2o) - WebSocket 应用服务器.
* [Nitrogen](https://github.com/nitrogen/nitrogen) - 在纯 Erlang 中构建 Web 应用程序（包括前端）的框架.

## Web Framework Components
*来自网络开发框架的独立组件.*

* [cb_admin](https://github.com/ChicagoBoss/cb_admin) - An admin interface for Chicago Boss.
* [cb_websocket_controller](https://github.com/dkuhlman/cb_websocket_controller) - 用于为 ChicagoBoss 实施 Websocket 控制器的模板.
* [giallo_session](https://github.com/kivra/giallo_session) - Giallo 网络框架的会话管理库.
* [simple_bridge](https://github.com/nitrogen/simple_bridge) - 为流行的 Erlang Web 服务器（Cowboy、Inets、Mochiweb、Webmachine 和 Yaws）提供统一接口的抽象层.

## HTTP
*用于处理 HTTP 和抓取网站的库.*

* [bullet](https://github.com/ninenines/bullet) - 简单、可靠、高效的 Cowboy 流媒体.
* [gun](https://github.com/ninenines/gun) - 支持 HTTP/1.1、SPDY 和 Websocket 的 Erlang HTTP 客户端.
* [hackney](https://github.com/benoitc/hackney) - Erlang 中的简单 HTTP 客户端.
* [ibrowse](https://github.com/cmullaparthi/ibrowse) - Erlang HTTP 客户端.
* [lhttpc](https://github.com/esl/lhttpc) - 在 Erlang 中实现的轻量级 HTTP/1.1 客户端.
* [shotgun](https://github.com/inaka/shotgun) - 在这个时代，您需要的不仅仅是一把枪.

## Testing
*用于测试代码库和生成测试数据的库.*

* [PropEr](https://github.com/manopapad/proper) - 受 QuickCheck 启发的基于属性的 Erlang 测试工具.
* [tracerl](https://github.com/esl/tracerl) - Erlang/OTP 的动态跟踪测试和实用程序

## Logging
*用于生成和使用日志文件的库.*

* [lager](https://github.com/basho/lager) - Erlang/OTP 的日志记录框架.
* [lager_amqp_backend](https://github.com/jbrisbin/lager_amqp_backend) - AMQP RabbitMQ Lager 后端.
* [lager_hipchat](https://github.com/synlay/lager_hipchat) - 啤酒的 HipChat 后端.
* [lager_loggly](https://github.com/kivra/lager_loggly) - 贮藏啤酒的 Loggly 后端.
* [lager_smtp](https://github.com/blinkov/lager_smtp) - 啤酒的 SMTP 后端.
* [lager_slack](https://github.com/furmanOFF/lager_slack) - 用于啤酒的简单 Slack 后端.
* [logplex](https://github.com/heroku/logplex) - Heroku 日志路由器.

## Monitoring
*用于收集指标和监控的库.*

* [entop](https://github.com/mazenharake/entop) - 一个类似top的Erlang节点监控工具.
* [eper](https://github.com/massemanet/eper) - Erlang 性能相关工具的松散集合.
* [Exometer](https://github.com/Feuerlabs/exometer) - 一个 Erlang 仪器包.
* [folsom](https://github.com/boundary/folsom) - 一个基于 Erlang 的指标系统，其灵感来自 Coda Hale  [metrics](https://github.com/codahale/metrics).
* [statsderl](https://github.com/lpgauth/statsderl) - 一个静态的 Erlang 客户端.
* [vmstats](https://github.com/ferd/vmstats) - 与 statsderl 一起工作的微型 Erlang 应用程序，以便在 Erlang VM 上为石墨日志生成信息.

## Deployment
*与部署 Erlang/OTP 应用程序相关的库和工具.*

* [docker-erlang](https://github.com/synlay/docker-erlang) - 用于 Erlang/OTP 的基本 Docker 容器镜像.

## Distributed Systems
 *跨微服务的压力/负载测试、延迟问题等工具.*

 * [Typhoon](https://github.com/fogfish/typhoon) - 用于分布式系统的压力和负载测试工具，模拟从测试集群到被测系统 (SUT) 的流量并可视化相关延迟.
## Code Analysis
*用于分析、解析和操作代码库的库和工具.*

* [Concuerror](https://github.com/parapluu/Concuerror) - Concuerror 是并发 Erlang 程序的系统测试工具.
* [eflame](https://github.com/proger/eflame) - 用于 Erlang 的火焰图分析器.
* [geas](https://github.com/crownedgrouse/geas) - Geas 是一种工具，可以检测项目的可运行官方 Erlang 发布窗口，包括其依赖项并提供许多有用的信息.

## Build Tools
*项目构建和自动化工具.*

* [rebar](https://github.com/rebar/rebar) - Erlang 构建工具，可以轻松编译和测试 Erlang 应用程序、端口驱动程序和版本.
* [rebar3](https://github.com/rebar/rebar3) - 一个 Erlang 的构建工具，可以从中管理 Erlang 包 [Hex.pm](https://hex.pm/) . 更多信息请访问 [rebar3.org](https://www.rebar3.org/)
* [sync](https://github.com/rustyio/sync) - 为 Erlang 即时重新编译.

## Geolocation
*用于地理编码地址和处理纬度和经度的库.*

* [erl-rstar](https://github.com/armon/erl-rstar) - R* 树空间数据结构的 Erlang 实现.
* [GeoCouch](https://github.com/couchbase/geocouch) - Couchbase 和 Apache CouchDB 的空间扩展.
* [Teles](https://github.com/armon/teles) - 用于处理地理数据的 Erlang 网络服务.

## Debugging
*用于调试代码和应用程​​序的库和工具.*

* [tx](https://github.com/kvakvs/tx) - 一个 HTML Erlang 术语查看器，启动自己的网络服务器并显示您从 Erlang 节点提供的任何术语.

## Actors
*用于与演员等合作的库和工具.*

* [poolboy](https://github.com/devinus/poolboy) - 一个笨拙的 Erlang 工人池工厂.

## Date and Time
*用于处理日期和时间的库.*

* [erlang_localtime](https://github.com/dmitryme/erlang_localtime) - 用于从一个本地时间转换为另一个本地时间的 Erlang 库.
* [qdate](https://github.com/choptastic/qdate) - Erlang 日期、时间和时区管理：格式化、转换和日期算术.

## ORM and Datamapping
*实现对象关系映射或数据映射技术的库.*

* [boss_db](https://github.com/ErlyORM/boss_db) - 用于 Erlang 的分片、缓存、池、事件 ORM.
* [epgsql](https://github.com/epgsql/epgsql) - Erlang 的 PostgreSQL 驱动程序.
* [mysql-otp](https://github.com/mysql-otp/mysql-otp) - MySQL/OTP – 用于 Erlang/OTP 的 MySQL 驱动程序.
* [pgsql_migration](https://github.com/artemeff/pgsql_migration) – Erlang 的 PostgreSQL 迁移.

## Queue
*用于处理事件和任务队列的库.*

* [dq](https://github.com/darach/dq) - 分布式容错队列库.
* [ebqueue](https://github.com/rgrinberg/ebqueue) - erlang 中的微型简单阻塞队列.
* [pqueue](https://github.com/okeuday/pqueue) - Erlang 优先级队列.
* [tinymq](https://github.com/ChicagoBoss/tinymq) - 用于 Erlang 的小型内存消息队列.

## Authentication
*用于实施身份验证方案的库.*

* [oauth2](https://github.com/kivra/oauth2) - Erlang Oauth2 实施.

## Text and Numbers
*用于解析和操作文本和数字的库.*

* [ejsv](https://github.com/patternmatched/ejsv) - Erlang JSON 模式验证器.
* [eql](https://github.com/artemeff/eql) - 是否使用 SQL 的 Erlang.
* [jiffy](https://github.com/davisp/jiffy) - 用于 Erlang 的 JSON NIF.
* [jsx](https://github.com/talentdeficit/jsx) - 用于消费、生成和操作 json 的 erlang 应用程序.
* [miffy](https://github.com/expelledboy/miffy) - 返回漂亮地图的 Jiffy 包装器.
* [qsp](https://github.com/artemeff/qsp) - 增强的 Erlang 查询字符串解析器.
* [rec2json](https://github.com/lordnull/rec2json) - 从记录规范生成 JSON 编码器/解码器.

## REST and API
*用于开发 REST-ful API 的库和网络工具.*

* [leptus](https://github.com/s1n4/leptus) - Leptus 是一个运行在 cowboy 之上的 Erlang REST 框架.
* [rooster](https://github.com/FelipeBB/rooster) - rooster 是一个运行在 mochiweb 之上的轻量级 REST 框架.

## Caching
*用于缓存数据的库.*

* [cache](https://github.com/fogfish/cache) - 内存分段缓存

## Third Party APIs
*用于访问第三方 API 的库.*

* [google-token-erlang](https://github.com/ruel/google-token-erlang) - 用于 Erlang 的 Google ID 令牌验证器.
* [restc](https://github.com/kivra/restclient) - 一个 Erlang REST 客户端
* [oauth2c](https://github.com/kivra/oauth2_client) - 一个 Erlang oAuth 2 客户端（使用 restc）

## Networking
*使用网络相关内容的库和工具.*

* [barrel_tcp](https://github.com/benoitc-attic/barrel_tcp) - barrel_tcp 是 Erlang 中具有低延迟的通用 TCP 接受器池.
* [gen_rpc](https://github.com/priestjim/gen_rpc) - 用于基于 Erlang-VM 的语言的可扩展 RPC 库.
* [gen_tcp_server](https://github.com/rpt/gen_tcp_server) - 一个采用 gen_server 概念并引入相同机制来操作 TCP 服务器的库.
* [gossiperl](https://github.com/gossiperl/gossiperl) - 用 Erlang 编写的与语言无关的八卦中间件和消息总线.
* [nat_upnp](https://github.com/benoitc/nat_upnp) - 使用 UNP IGD 将您的内部端口映射到外部的 Erlang 库.
* [ranch](https://github.com/ninenines/ranch) - TCP 协议的套接字接受器池.

## Internet of Things
*用于与物理世界交互的库和工具.*

* [GRiSP](https://grisp.org/) - 使用名为 RTEMS 的小型实时 unikernel 在具有许多硬件接口和低级驱动程序的物联网板上运行 Erlang VM
* [lemma_erlang](https://github.com/noam-io/lemma_erlang) - IDEO 的 Noam 物联网原型平台的引理.

## Algorithms and Datastructures
*算法和数据结构的库和实现.*

* [datum](https://github.com/fogfish/datum) - Erlang 的纯函数式和泛型编程
* [erlando](https://github.com/travelping/erlando) - 一组语法扩展，例如 Erlang 的 currying 和 monads.
* [statebox](https://github.com/mochi/statebox) - 具有合并/冲突解决功能的 Erlang 状态“monad”.
* [riak_dt](https://github.com/basho/riak_dt) - 基于状态的 CRDT 的 Erlang 库.

## Translations and Internationalizations
*提供翻译或国际化的图书馆.*

## Miscellaneous
*不属于上述类别的有用库或工具.*

* [erlang-history](https://github.com/ferd/erlang-history) - 将 shell 历史添加到 Erlang 的 shell 中.
* [erld](https://github.com/ShoreTel-Inc/erld) - erld 是一个小程序，旨在解决将 Erlang 程序作为 UNIX 守护进程运行的问题.

## Resources
用于提高您的 Erlang 开发技能和知识的各种资源，例如书籍、网站和文章.

## Websites
*有用的网络和 Erlang 相关网站和时事通讯.*

* [Erlang Bookmarks](https://github.com/0xAX/erlang-bookmarks/wiki/Erlang-bookmarks) - 关于 erlang 编程语言 [由社区提供支持].
* [Erlang Central](https://erlangcentral.org/) - 很棒的 erlang 资源集合以及用于讨论和寻求帮助的实时社区聊天.
* [Planet Erlang](http://www.planeterlang.com/) - 涵盖整个 Erlang 生态系统主题的博客文章的 Planet 站点/RSS 提要.
* [Spawned Shelter](http://spawnedshelter.com/)  - 二郎生成的庇护所. 与 Erlang 相关的最佳文章、视频和演示文稿的集合.

## Books
*很棒的书籍和电子书.*

* [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) - Wolfgang Loder 在功能概念的背景下介绍 Erlang 和 Elixir（2016）
* [Learn You Some Erlang](http://learnyousomeerlang.com/)  - 学习一些 Erlang - 非常有用！ 一个非常全面的资源，涵盖了从开始 Erlang 编程到大规模开发和部署的所有内容.
* [Stuff Goes Bad - ERLANG IN ANGER](http://www.erlang-in-anger.com/) - 这本书旨在成为一个关于如何在战争时期成为 Erlang 军医的小指南.

## Web Reading
*与网络开发相关的一般阅读材料.*

## Erlang Reading
*与Erlang相关的阅读材料.*

* [The Joy of Erlang; Or, How To Ride A Toruk](http://www.evanmiller.org/joy-of-erlang.html)  - Erlang 的乐趣； 或者，How To Ride A Toruk 对 Erlang 的快速介绍，通过一些示例项目来教授这门语言.

## Screencasts
*很酷的视频教程.*

## Contributing
请参见 [CONTRIBUTING](https://github.com/drobakowski/awesome-erlang/blob/master/CONTRIBUTING.md) 了解详情.
