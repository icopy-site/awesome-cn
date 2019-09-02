<div class="github-widget" data-repo="drobakowski/awesome-erlang"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Erlang [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Analytics](https://ga-beacon.appspot.com/UA-82766782-1/awesome-erlang?flat&useReferer)](https://github.com/drobakowski/awesome-erlang)
精选的令人敬畏的Erlang图书馆列表，资源和闪亮的东西 [awesome-elixir](https://github.com/h4cc/awesome-elixir).


## Package Management
*用于包和依赖管理的库和工具.*

* [hex.pm](https://hex.pm/) -  Erlang生态系统的包管理器.

## Release Management
*用于发布管理的库和工具.*

* [relx](https://github.com/erlware/relx) -  Erlang的发布汇编程序.

## Configuration Management
*与配置管理相关的库和工具.*

* [stillir](https://github.com/heroku/stillir) - 将环境变量缓存为Erlang应用程序变量.

## Codebase Maintenance
*用于维护干净代码库的库和工具.*

* [elvis](https://github.com/inaka/elvis) -  Erlang Style Reviewer.

## Web Frameworks
* Web开发框架.*

* [Axiom](https://github.com/tsujigiri/axiom) - 一个受Ruby&#39;s启发的微框架 [Sinatra](https://github.com/sinatra/sinatra).
* [ChicagoBoss](https://github.com/ChicagoBoss/ChicagoBoss) - 受Rails启发并用Erlang编写的服务器框架.
* [cowboy](https://github.com/ninenines/cowboy) - 一个简单的HTTP服务器.
* [Giallo](https://github.com/kivra/giallo) - 一个小而灵活的Web框架 [Cowboy](https://github.com/ninenines/cowboy).
* [MochiWeb](https://github.com/mochi/mochiweb) - 用于构建轻量级HTTP服务器的Erlang库.
* [N2O](https://github.com/synrc/n2o) -  WebSocket应用服务器.
* [Nitrogen](https://github.com/nitrogen/nitrogen) - 在纯Erlang中构建Web应用程序（包括前端）的框架.

## Web Framework Components
*来自Web开发框架的独立组件.*

* [cb_admin](https://github.com/ChicagoBoss/cb_admin) - 芝加哥老板的管理界面.
* [cb_websocket_controller](https://github.com/dkuhlman/cb_websocket_controller) - 用于为ChicagoBoss实现Websocket控制器的模板.
* [giallo_session](https://github.com/kivra/giallo_session) -  Giallo Web框架的会话管理库.
* [simple_bridge](https://github.com/nitrogen/simple_bridge) - 一个抽象层，为流行的Erlang Web服务器（Cowboy，Inets，Mochiweb，Webmachine和Yaws）提供统一的界面.

## HTTP
*用于处理HTTP和抓取网站的库.*

* [bullet](https://github.com/ninenines/bullet) - 牛仔简单，可靠，高效的流媒体.
* [gun](https://github.com/ninenines/gun) - 支持HTTP / 1.1，SPDY和Websocket的Erlang HTTP客户端.
* [hackney](https://github.com/benoitc/hackney) -  Erlang中的简单HTTP客户端.
* [ibrowse](https://github.com/cmullaparthi/ibrowse) -  Erlang HTTP客户端.
* [lhttpc](https://github.com/esl/lhttpc) - 在Erlang中实现的轻量级HTTP / 1.1客户端.
* [shotgun](https://github.com/inaka/shotgun) - 有时候你需要的不仅仅是一把枪.

## Testing
*用于测试代码库和生成测试数据的库.*

* [PropEr](https://github.com/manopapad/proper) - 针对Erlang的基于QuickCheck的基于属性的测试工具.
* [tracerl](https://github.com/esl/tracerl) -  Erlang / OTP的动态跟踪测试和实用程序

## Logging
*用于生成和处理日志文件的库.*

* [lager](https://github.com/basho/lager) -  Erlang / OTP的日志框架.
* [lager_amqp_backend](https://github.com/jbrisbin/lager_amqp_backend) -  AMQP RabbitMQ Lager后端.
* [lager_hipchat](https://github.com/synlay/lager_hipchat) -  HipChat后端库存.
* [lager_loggly](https://github.com/kivra/lager_loggly) -  Loggly后端库存.
* [lager_smtp](https://github.com/blinkov/lager_smtp) - 用于贮藏的SMTP后端.
* [lager_slack](https://github.com/furmanOFF/lager_slack) - 简单的Slack后端用于贮藏啤酒.
* [logplex](https://github.com/heroku/logplex) -  Heroku日志路由器.

## Monitoring
*用于收集指标和监控的图书馆.*

* [entop](https://github.com/mazenharake/entop) - 类似顶级的Erlang节点监控工具.
* [eper](https://github.com/massemanet/eper) -  Erlang Performance相关工具的松散集合.
* [Exometer](https://github.com/Feuerlabs/exometer) - 一个Erlang检测包.
* [folsom](https://github.com/boundary/folsom) - 基于Erlang的度量系统，受Coda Hale的启发 [metrics](https://github.com/codahale/metrics).
* [statsderl](https://github.com/lpgauth/statsderl) - 一个statsd Erlang客户端.
* [vmstats](https://github.com/ferd/vmstats) - 与statsderl配合使用的Tiny Erlang应用程序，用于生成有关石墨日志的Erlang VM的信息.

## Deployment
*与部署Erlang / OTP应用程序相关的库和工具.*

* [docker-erlang](https://github.com/synlay/docker-erlang) -  Erlang / OTP的基本Docker容器映像.

## Distributed Systems
 *跨微服务的压力/负载测试工具，延迟问题等.*

 * [Typhoon](https://github.com/fogfish/typhoon) - 用于分布式系统的压力和负载测试工具，用于模拟从测试集群到被测系统（SUT）的流量，并可视化相关的延迟.
## Code Analysis
*用于分析，解析和操作代码库的库和工具.*

* [Concuerror](https://github.com/parapluu/Concuerror) -  Concuerror是并发Erlang程序的系统测试工具.
* [eflame](https://github.com/proger/eflame) -  Erlang的Flame Graph分析器.
* [geas](https://github.com/crownedgrouse/geas) -  Geas是一个工具，可以检测项目的可运行官方Erlang发布窗口，包括其依赖项，并提供许多有用的信息.

## Build Tools
*项目构建和自动化工具.*

* [rebar](https://github.com/rebar/rebar) -  Erlang构建工具，可以轻松编译和测试Erlang应用程序，端口驱动程序和版本.
* [rebar3](https://github.com/rebar/rebar3) -  Erlang的构建工具，可以管理Erlang包 [Hex.pm](https://hex.pm/) .  更多信息请访问 [rebar3.org](https://www.rebar3.org/)
* [sync](https://github.com/rustyio/sync) - 为Erlang进行动态重新编译.

## Geolocation
*地理编码地址和处理纬度和经度的图书馆.*

* [erl-rstar](https://github.com/armon/erl-rstar) -  R * -tree空间数据结构的Erlang实现.
* [GeoCouch](https://github.com/couchbase/geocouch) -  Couchbase和Apache CouchDB的空间扩展.
* [Teles](https://github.com/armon/teles) - An Erlang network service for manipulating geographic data.

## Debugging
*用于调试代码和应用程​​序的库和工具.*

* [tx](https://github.com/kvakvs/tx) -  HTML Erlang术语查看器，启动自己的Web服务器并显示您从Erlang节点提供的任何术语.

## Actors
*与演员等合作的图书馆和工具.*

* [poolboy](https://github.com/devinus/poolboy) - 一个hunky Erlang工人池工厂.

## Date and Time
*处理日期和时间的图书馆.*

* [erlang_localtime](https://github.com/dmitryme/erlang_localtime) - 用于从一个本地时间转换到另一个本地时间的Erlang库.
* [qdate](https://github.com/choptastic/qdate) -  Erlang日期，时间和时区管理：格式化，转换和日期算术.

## ORM and Datamapping
*实现对象关系映射或数据映射技术的库.*

* [boss_db](https://github.com/ErlyORM/boss_db) -  Erlang的分片，缓存，池化，事件ORM.
* [epgsql](https://github.com/epgsql/epgsql) - 用于Erlang的PostgreSQL驱动程序.
* [mysql-otp](https://github.com/mysql-otp/mysql-otp) -  MySQL / OTP  -  Erlang / OTP的MySQL驱动程序.
* [pgsql_migration](https://github.com/artemeff/pgsql_migration) -  Erlang的PostgreSQL迁移.

## Queue
*用于处理事件和任务队列的库.*

* [dq](https://github.com/darach/dq) - 分布式容错队列库.
* [ebqueue](https://github.com/rgrinberg/ebqueue) -  erlang中的小型简单阻塞队列.
* [pqueue](https://github.com/okeuday/pqueue) -  Erlang优先级队列.
* [tinymq](https://github.com/ChicagoBoss/tinymq) -  Erlang的小型内存消息队列.

## Authentication
*用于实施认证计划的图书馆.*

* [oauth2](https://github.com/kivra/oauth2) -  Erlang Oauth2的实现.

## Text and Numbers
*用于解析和操作文本和数字的库.*

* [ejsv](https://github.com/patternmatched/ejsv) -  Erlang JSON模式验证器.
* [eql](https://github.com/artemeff/eql) - 带有SQL的Erlang.
* [jiffy](https://github.com/davisp/jiffy) -  Erlang的JSON NIF.
* [jsx](https://github.com/talentdeficit/jsx) - 用于消费，生成和操纵json的erlang应用程序.
* [miffy](https://github.com/expelledboy/miffy) -  Jiffy包装器返回漂亮的地图.
* [qsp](https://github.com/artemeff/qsp) -  Erlang的增强查询字符串解析器.
* [rec2json](https://github.com/lordnull/rec2json) - 根据记录规范生成JSON编码器/解码器.

## REST and API
*用于开发REST-ful API的库和Web工具.*

* [leptus](https://github.com/s1n4/leptus) -  Leptus是一个运行在牛仔之上的Erlang REST框架.
* [rooster](https://github.com/FelipeBB/rooster) -  rooster是一个轻量级的REST框架，运行在mochiweb之上.

## Caching
*用于缓存数据的库.*

* [cache](https://github.com/fogfish/cache) - 内存中的分段缓存

## Third Party APIs
*用于访问第三方API的库.*

* [google-token-erlang](https://github.com/ruel/google-token-erlang) -  Erlang的Google ID令牌验证程序.
* [restc](https://github.com/kivra/restclient) - 一个Erlang REST客户端
* [oauth2c](https://github.com/kivra/oauth2_client) -  Erlang oAuth 2客户端（使用restc）

## Networking
*使用网络相关内容的库和工具.*

* [barrel_tcp](https://github.com/benoitc-attic/barrel_tcp) -  barrel_tcp是一个通用的TCP接受器池，在Erlang中具有低延迟.
* [gen_rpc](https://github.com/priestjim/gen_rpc) - 基于Erlang-VM的语言的可扩展RPC库.
* [gen_tcp_server](https://github.com/rpt/gen_tcp_server) - 采用gen_server概念的库，并介绍了操作TCP服务器的相同机制.
* [gossiperl](https://github.com/gossiperl/gossiperl) - 用Erlang编写的语言无关的八卦中间件和消息总线.
* [nat_upnp](https://github.com/benoitc/nat_upnp) - 使用UNP IGD将内部端口映射到外部的Erlang库.
* [ranch](https://github.com/ninenines/ranch) - 用于TCP协议的套接字接受器池.

## Internet of Things
*与物理世界互动的图书馆和工具.*

* [GRiSP](https://grisp.org/) - 使用名为RTEMS的小型实时内核，在具有许多硬件接口和低级驱动程序的IoT板上运行Erlang VM
* [lemma_erlang](https://github.com/noam-io/lemma_erlang) -  IDEO的Noam物联网原型平台的引理.

## Algorithms and Datastructures
*算法和数据结构的库和实现.*

* [datum](https://github.com/fogfish/datum) -  Erlang的纯函数和泛型编程
* [erlando](https://github.com/travelping/erlando) - 一组语法扩展，如Erlang的currying和monads.
* [statebox](https://github.com/mochi/statebox) -  Erlang状态“monad”具有合并/冲突解决功能.
* [riak_dt](https://github.com/basho/riak_dt) - 基于状态的CRDT的Erlang库.

## Translations and Internationalizations
*提供翻译或国际化的图书馆.*

## Miscellaneous
*有用的库或工具不适合上述类别.*

* [erlang-history](https://github.com/ferd/erlang-history) -  Hacks将shell历史记录添加到Erlang的shell中.
* [erld](https://github.com/ShoreTel-Inc/erld) -  erld是一个小程序，旨在解决将Erlang程序作为UNIX守护程序运行的问题.

## Resources
各种资源，如书籍，网站和文章，用于提高您的Erlang开发技能和知识.

## Websites
*有用的网站和与Erlang相关的网站和新闻简报.*

* [Erlang Bookmarks](https://github.com/0xAX/erlang-bookmarks/wiki/Erlang-bookmarks) - 所有关于erlang编程语言[由社区提供支持].
* [Erlang Central](https://erlangcentral.org/) - 一个令人敬畏的erlang资源集合以及实时社区聊天，用于讨论和寻求帮助.
* [Planet Erlang](http://www.planeterlang.com/) - 包含Erlang生态系统主题的博客文章的Planet site / RSS feed.
* [Spawned Shelter](http://spawnedshelter.com/)   -  Erlang Spawned Shelter.  与Erlang相关的最佳文章，视频和演示文稿的集合.

## Books
*精彩的书籍和电子书.*

* [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) -  Wolfgang Loder（2016）在功能概念背景下介绍Erlang和Elixir
* [Learn You Some Erlang](http://learnyousomeerlang.com/)   - 了解一些Erlang  - 非常好！  一个非常全面的资源，涵盖从开始Erlang编程到大规模开发和部署的所有内容.
* [Stuff Goes Bad - ERLANG IN ANGER](http://www.erlang-in-anger.com/) - 这本书打算成为一个关于如何成为战争时期的二郎医生的小指南.

## Web Reading
*与网络开发相关的一般阅读材料.*

## Erlang Reading
*与二郎相关的阅读材料.*

* [The Joy of Erlang; Or, How To Ride A Toruk](http://www.evanmiller.org/joy-of-erlang.html)   - 二郎的喜悦;  或者，如何乘坐Toruk快速通道介绍Erlang，通过一些示例项目来教授语言.

## Screencasts
*酷视频教程.*

## Contributing
请参阅 [CONTRIBUTING](https://github.com/drobakowski/awesome-erlang/blob/master/CONTRIBUTING.md) 详情.
