<div class="github-widget" data-repo="veelenga/awesome-crystal"></div>
<p align="center"><img src="https://raw.githubusercontent.com/veelenga/awesome-crystal/master/logo/logotype_horizontal.png" alt="awesome-crystal"></p>

## Awesome Crystal
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Build Status](https://api.travis-ci.org/veelenga/awesome-crystal.svg)](https://travis-ci.org/veelenga/awesome-crystal)

 精彩的Crystal代码和资源的精选列表.  灵感来自 [awesome](https://github.com/sindresorhus/awesome) 和 [awesome-awesomeness](https://github.com/bay和in/awesome-awesomeness).
目标是使项目大多稳定并对社区有用.

Search [Crystal Shards](https://crystalshards.xyz) 或者关注公告[Crystal [ANN]]（https://crystal-ann.com）了解更多信息.

 欢迎捐款.  请快速浏览一下 [contribution guidelines](https://github.com/veelenga/awesome-crystal/blob/master/.github/CONTRIBUTING.md) 第一.


## Algorithms and Data structures
 * [aho_corasick](https://github.com/chenkovsky/aho_corasick) -  AhoCorasick算法
 * [bisect](https://github.com/spider-gazelle/bisect) - 将值插入已排序的数组中
 * [bitfields](https://github.com/elorest/bitfields)   -  BitFields的Pure Crystal实现.  处理字节的编码/解码.
 * [CrOTP](https://github.com/philnash/crotp) - 用于双因素身份验证的HOTP和TOTP实现
 * [crystal-diff](https://github.com/MakeNowJust/crystal-diff) - 晶体序列差异实现
 * [crystal-linked-list](https://github.com/abvdasker/crystal-linked-list) - 链接列表的实施
 * [crystaledge](https://github.com/unn4m3d/crystaledge) - 纯矢量数学库
 * [crystalg](https://github.com/TobiasGSmollett/crystalg) - 通用算法库
 * [crystalline](https://github.com/jtomschroeder/crystalline) - 容器和算法的集合
 * [delimiter_tree](https://github.com/drujensen/delimiter_tree) - 使用分隔符构建的树结构
 * [edits.cr](https://github.com/tcrouch/edits.cr) - 编辑距离算法的集合
 * [graphlb](https://github.com/mettuaditya/graphlb) - 图形数据结构和算法的集合
 * [hash_ring](https://github.com/TobiasGSmollett/hash_ring) - 一致哈希环的实现
 * [ksuid.cr](https://github.com/Sija/ksuid.cr) -  K-Sortable全球唯一ID
 * [markov](https://github.com/mccallofthewild/markov) - 构建马尔可夫链并运行马尔可夫过程
 * [multiset.cr](https://github.com/tcrouch/multiset.cr) - 实现多重集
 * [murmur3](https://github.com/kuende/murmur3) -  Cassandra使用的Murmur3哈希算法的实现
 * [oak](https://github.com/obsidian/oak) - 灵活的Radix Tree实现
 * [radix](https://github.com/luislavena/radix) -  Radix Tree实现
 * [ternary_search_tree](https://github.com/johnjansen/ternary_search_tree) - 三元搜索树

## Api Builders
 * [kemal-rest-api](https://github.com/blocknotes/kemal-rest-api) - 使用Kemal创建RESTful API的库

## Blockchain
 * [SushiChain](https://github.com/SushiChain/SushiChain) - 自定义区块链平台

## C bindings
 * [asound-cr](https://github.com/TamasSzekeres/asound-cr) -  ALSA / libasound的绑定
 * [cairo-cr](https://github.com/TamasSzekeres/cairo-cr) - 绑定 [Cairo](https://cairographics.org/) 图形库
 * [clang.cr](https://github.com/ysbaddaden/clang.cr) -  Libclang绑定
 * [crass](https://github.com/vonKingsley/crass) -  libsass的绑定
 * [crt.cr](https://github.com/maiha/crt.cr) -  libncursesw和crt的绑定
 * [crystal-gsl](https://github.com/ruivieira/crystal-gsl) -  GNU Scientific Library绑定
 * [curl-crystal](https://github.com/blocknotes/curl-crystal) - 绑定 [libcurl](https://curl.haxx.se/libcurl/)
 * [duktape.cr](https://github.com/jessedoyle/duktape.cr) - 绑定 [Duktape](https://github.com/svaarala/duktape) JavaScript引擎
 * [gphoto2.cr](https://github.com/Sija/gphoto2.cr) - 绑定 [libgphoto2](http://www.gphoto.org/) 图书馆
 * [icu.cr](https://github.com/olbat/icu.cr) - 绑定 [ICU](http://site.icu-project.org/) 图书馆
 * [libnotify.cr](https://github.com/splattael/libnotify.cr) -  Libnotify的绑定
 * [pcap.cr](https://github.com/maiha/pcap.cr) -  libpcap的绑定
 * [pledge.cr](https://github.com/chris-huxtable/pledge.cr) -  OpenBSD的承诺（2）的绑定
 * [posix](https://github.com/ysbaddaden/posix) -  POSIX / C绑定
 * [soundfile](https://github.com/mjago/soundfile) - 绑定 [libsndfile](http://www.mega-nerd.com/libsndfile/) 图书馆
 * [ssh2.cr](https://github.com/spider-gazelle/ssh2.cr) -  libssh2库的绑定
 * [syslog.cr](https://github.com/chris-huxtable/syslog.cr) - `syslog`的绑定
 * [termbox-crystal](https://github.com/andrewsuzuki/termbox-crystal) - 绑定和扩展库 [termbox](https://github.com/nsf/termbox) （终端UI库）
 * [x11-cr](https://github.com/TamasSzekeres/x11-cr) -  X11绑定
 * [x_do.cr](https://github.com/woodruffw/x_do.cr) -  libxdo的绑定（[`xdotool`](https://github.com/jordansissel/xdotool))

## Caching
 * [bloom_filter](https://github.com/crystal-community/bloom_filter) -  Bloom过滤器的实现
 * [bojack](https://github.com/marceloboeira/bojack) - 不可靠的内存中键值存储
 * [cache-hash](https://github.com/samueleaton/cache-hash) - 键/值存储，其中条目在指定的时间间隔后到期
 * [crystal-memcached](https://github.com/comandeo/crystal-memcached) - 实现memcached客户端
 * [Nuummite](https://github.com/CodeSteak/Nuummite) - 一个微小的持久嵌入式键值存储

## CLI Builders
 * [admiral](https://github.com/jwaldrip/admiral.cr) - 用于编写命令行界面的强大DSL
 * [cli](https://github.com/mosop/cli) - 用于构建命令行界面应用程序的库
 * [clicr](https://github.com/j8r/clicr) - 一个简单的声明性命令行界面构建器
 * [clim](https://github.com/at-grandpa/clim) - 超薄命令行界面构建器
 * [commander](https://github.com/mrrooijen/commander) - 命令行界面构建器
 * [completion](https://github.com/f/completion) - 简单的命令行完成引擎
 * [optarg](https://github.com/mosop/optarg) - 另一个用于解析命令行选项和参数的库
 * [OptionParser](https://crystal-lang.org/api/OptionParser.html) - 命令行选项处理（Crystal stdlib）

## CLI Utils
 * [cride](https://github.com/j8r/cride) - 轻量级CLI文本编辑器/ IDE
 * [progress_bar.cr](https://github.com/TPei/progress_bar.cr) - 简单且可自定义的进度条
 * [tallboy](https://github.com/epoch/tallboy) - 生成ASCII字符表，支持在多列上生成单元格
 * [terminal_table.cr](https://github.com/benoist/terminal_table.cr) - 简单的ASCII表生成器
 * [todo](https://git.sceptique.eu/Sceptique/todo) -  Todo列表在命令行中工作

## Code Analysis and Metrics
 * [ameba](https://github.com/veelenga/ameba) - 静态代码分析工具
 * [trashman](https://github.com/Groogy/trashman) -  Crystal应用程序的简单内存分析器

## Configuration
 * [cr-dotenv](https://github.com/gdotdesign/cr-dotenv) - 加载.env文件
 * [envyable](https://github.com/philnash/envyable.cr) - 一个简单的YAML到ENV配置加载器
 * [habitat](https://github.com/luckyframework/habitat) - 为类和模块键入安全配置
 * [totem](https://github.com/icyleaf/totem) - 以JSON，YAML，dotenv格式加载和解析配置

## Converters
 * [base62.cr](https://github.com/Sija/base62.cr) -  Base62编码器/解码器，非常适合缩短网址
 * [money](https://github.com/crystal-money/money) - 轻松处理货币和货币转换（几乎完整的港口） [RubyMoney](https://github.com/RubyMoney/money))
 * [moola](https://github.com/dorkrawk/moola) - 处理金钱和转换的图书馆（灵感来源于 [RubyMoney](https://github.com/RubyMoney/money))
 * [ms](https://github.com/SuperPaintman/ms) - 库可以轻松地将各种时间格式转换为毫秒和毫秒到人类可读的格式
 * [sass.cr](https://github.com/straight-shoota/sass.cr) - 将SASS / SCSS编译为CSS（[libsass](https://github.com/sass/libsass/) 捆绑）
 * [time_format.cr](https://github.com/vladfaust/time_format.cr) - 轻松转换人类可读格式的时间
 * [turkish-number](https://github.com/izniburak/turkish-number) - 将整数转换为土耳其语
 * [wkhtmltopdf-crystal](https://github.com/blocknotes/wkhtmltopdf-crystal) -  libwkhtmltox的绑定/包装（HTML到PDF /图像转换器）

## Data Formats
 * [BinData](https://github.com/spider-gazelle/bindata) - 二进制数据解析器帮助器 [ASN.1](https://en.wikipedia.org/wiki/Abstract_Syntax_Notation_One) 解析器
 * [config.cr](https://github.com/chris-huxtable/config.cr) - 易于使用的配置格式解析器
 * [crinder](https://github.com/c910335/crinder) - 基于类的json渲染器
 * [CSV](https://crystal-lang.org/api/CSV.html) - 解析和生成逗号分隔值（Crystal stdlib）
 * [front_matter.cr](https://github.com/chris-huxtable/front_matter.cr) - 将文件前端内容与其内容分开
 * [geoip2.cr](https://github.com/delef/geoip2.cr) -  GeoIP2阅读器
 * [Gzip](https://crystal-lang.org/api/Gzip.html) -  gzip格式的读者和作者（Crystal stdlib）
 * [INI](https://crystal-lang.org/api/INI.html) - 这个解析器文件（Crystal stdlib）
 * [JSON](https://crystal-lang.org/api/JSON.html) - 解析和生成JSON文档（Crystal stdlib）
 * [JSON tools](https://github.com/impatienttraveller/json-tools) -  JSON补丁和指针RFC的实现
 * [maxminddb.cr](https://github.com/delef/maxminddb.cr) -  MaxMindDB阅读器
 * [toml.cr](https://github.com/crystal-community/toml.cr) -  TOML解析器
 * [XML](https://crystal-lang.org/api/XML.html) - 解析和生成XML文档（Crystal stdlib）
 * [YAML](https://crystal-lang.org/api/YAML.html) - 解析和生成YAML文档（Crystal stdlib）
 * [Zip](https://crystal-lang.org/api/Zip.html) -  zip格式的读者和作者（Crystal stdlib）
 * [Zlib](https://crystal-lang.org/api/Zlib.html) -  zlib格式的读者和作者（Crystal stdlib）
 * [zq](https://github.com/colstrom/zq) - 命令行ZPL处理器

## Data Generators
 * [faker](https://github.com/askn/faker) - 用于生成虚假数据的库
 * [hashids.cr](https://github.com/splattael/hashids.cr) - 用于从一个或多个号码生成类似YouTube的ID的库

## Database Drivers/Clients
 * [couchdb.cr](https://github.com/TechMagister/couchdb.cr) -  CouchDB客户端
 * [crystal-db](https://github.com/crystal-lang/crystal-db) - 常见的数据库API
 * [crystal-monetdb-libmapi](https://github.com/puppetpies/crystal-monetdb-libmapi) -  MonetDB的绑定
 * [crystal-mysql](https://github.com/crystal-lang/crystal-mysql) -  Crystal的MySQL连接器
 * [crystal-pg](https://github.com/will/crystal-pg) - 一个Postgres司机
 * [crystal-redis](https://github.com/stefanwille/crystal-redis) - 功能齐全的Redis客户端
 * [crystal-rethinkdb](https://github.com/kingsleyh/crystal-rethinkdb) -  RethinkDB / RebirthDB的驱动程序
 * [crystal-sqlite3](https://github.com/crystal-lang/crystal-sqlite3) -  SQLite3绑定
 * [eventql-crystal](https://github.com/measurechina/eventql-crystal) -  EventQL驱动程序
 * [leveldb](https://github.com/crystal-community/leveldb) -  LevelDB的Crystal绑定
 * [mongo.cr](https://github.com/datanoise/mongo.cr) - Binding for MongoDB C driver
 * [rocksdb.cr](https://github.com/maiha/rocksdb.cr) -  RocksDB客户端
 * [tarantool-crystal](https://github.com/vladfaust/tarantool-crystal) -  Tarantool司机

## Database Tools
 * [micrate](https://github.com/juanedi/micrate) - 数据库迁移工具
 * [migrate](https://github.com/vladfaust/migrate.cr) - 具有事务的更简单的数据库迁移工具
 * [migro](https://github.com/aisrael/migro) - 数据库迁移工具，允许在YAML或原始SQL中指定迁移

## Development Tools
 * [guardian](https://github.com/f/guardian) -  Crystal和非Crystal库的文件更改监视器
 * [kemal-watcher](https://github.com/faustinoaq/kemal-watcher) -  Kemal插件可以观看文件并实时重新加载浏览器
 * [sentry](https://github.com/samueleaton/sentry) - 观察src文件，在文件更改时重建/重新运行应用程序
 * [sentry-run](https://github.com/faustinoaq/sentry-run) - 使用Sentry.run重新加载代码
 * [Warden](https://github.com/diggersheep/warden) - 如果文件更改成功，则监视文件，运行命令和git命令
 * [watcher](https://github.com/faustinoaq/watcher) - 使用File.stat监视文件更改

## Email
 * [carbon](https://github.com/luckyframework/carbon) - 有趣，可测试和基于适配器的电子邮件库
 * [crystal-email](https://github.com/arcage/crystal-email) - 简单的电子邮件发送库
 * [CrystalEmail](https://git.sceptique.eu/Sceptique/CrystalEmail) - 符合RFC的电子邮件验证程序
 * [devmail](https://github.com/tijn/devmail) - 具有易失性邮件存储的组合SMTP / POP3服务器
 * [sendgrid.cr](https://github.com/dlanileonardo/sendgrid.cr) - 简单的Sendgrid客户端

## Environment Management
 * [asdf-crystal](https://github.com/marciogm/asdf-crystal) -  asdf版本管理器的插件
 * [crenv](https://github.com/pine/crenv) - 水晶版经理
 * [rcm.cr](https://github.com/maiha/rcm.cr) -  Redis群集管理器

## Examples and funny stuff
 * [battlesnake_crystal](https://github.com/nbw/battlesnake_crystal) - Tron snake for [battlesnake](https://www.battlesnake.io/) 竞争
 * [blackjack-cr](https://github.com/gdonald/blackjack-cr) - 控制台二十一点
 * [breakout.cr](https://github.com/petoem/breakout.cr) - 使用crsfml编写的突破游戏
 * [chuck-norris-holy-quotes](https://github.com/codenoid/chuck-norris-holy-quotes) - 查克诺里斯的圣洁语录
 * [clamp](https://github.com/johnjansen/clamp) - 钳制任何可比较
 * [crsfml-examples](https://github.com/oprypin/crsfml-examples) - 使用CrSFML制作的简单游戏
 * [crystal-benchmarks-game](https://github.com/kostya/crystal-benchmarks-game) - 计算机语言基准游戏
 * [crystal-by-example](https://github.com/askn/crystal-by-example) - 水晶示例
 * [Crystal-Maze](https://github.com/Demonstrandum/Crystal-Maze) -  PNG迷宫的A *路径查找
 * [crystal-mysql-crud-example](https://github.com/codenoid/crystal-mysql-crud-example) -  Crystal MySQL CRUD示例
 * [crystal-patterns](https://github.com/crystal-community/crystal-patterns) -  GOF模式的例子
 * [crystalized_ruby](https://github.com/phoffer/crystalized_ruby) - 用Crystal编写的本机Ruby扩展
 * [crystalworld](https://github.com/vladfaust/crystalworld) - [realworld.io](https://realworld.io) 后端API实现
 * [exercism-crystal](https://github.com/exercism/crystal) - 运动练习
 * [jihantoro-cr-mysql](https://github.com/codenoid/jihantoro-cr-mysql) - 从头开始​​的Crystal MySQL示例应用程序
 * [jihantoro.sd](https://github.com/codenoid/jihantoro.sd) -  Serdar Dogruyol博客的Crystal＆Kemal版本
 * [kemal-chat](https://github.com/sdogruyol/kemal-chat) - 使用Kemal和WebSocket构建实时应用程序
 * [kemal-heroku-example](https://github.com/cagataycali/kemal-heroku-example) - 此存储库显示，如何在几秒钟内发布开源应用程序，这些应用程序将kemal框架作为heroku app发布
 * [kemal-mysql-blog](https://github.com/codenoid/kemal-mysql-blog) - 用Crystal，Kemal和MySQL编写的博客
 * [kemal-react-chat](https://github.com/f/kemal-react-chat) - 使用Kemal和React构建实时Web应用程序
 * [kemal-vue-chat](https://github.com/ChangJoo-Park/kemal-vue-chat) - 使用Kemal和Vue.js构建实时Web应用程序
 * [lattice-core-card-game](https://github.com/jasonl99/card_game) - 针对（基于WebSocket的）网格核心的演示Web应用程序
 * [medley](https://github.com/jwoertink/medley) - 音乐相关方法的混合
 * [os-crystal](https://github.com/lbguilherme/os-crystal) - 在Crystal中实现的x86内核
 * [realtime-todo-app](https://github.com/Angarsk8/realtime-todo-app) - 使用Kemal，Websockets，React，ES2015和PostgreSQL开发的实时Todo应用程序
 * [rocky](https://github.com/codingphasedotcom/rocky) - 反应水晶凯末尔和纱线
 * [try.cr](https://github.com/maiha/try.cr) - 尝试monad

## Feature Flipping
 * [can_use](https://github.com/rodrigopinto/can_use) - 这是一款基于yaml的水晶极简主义功能切换/标记
 * [flipper](https://github.com/metaware/flipper)   - 功能翻转/标记/卷展栏.  支持多个后端

## Framework Components
 * [cr-melon](https://github.com/gdotdesign/cr-melon) - 基于类的Http API
 * [Crystal-DI](https://github.com/funk-yourself/crystal-di) - 轻质DI容器
 * [crystal-mime](https://github.com/spalger/crystal-mime) - 水晶的Mimetypes
 * [device_detector](https://github.com/creadone/device_detector) - 用户代理字符串检测设备的分片
 * [Exception Page](https://github.com/crystal-loot/exception_page) -  Crystal Web库和框架的特殊异常页面
 * [graphql-crystal](https://github.com/ziprandom/graphql-crystal) - [Graphql](http://graphql.org) 履行
 * [kave](https://github.com/jwoertink/kave) -  Kemal API版本扩展
 * [kemal-auth-token](https://github.com/akwiatkowski/kemal-auth-token) - 使用JWT通过HTTP头令牌进行身份验证的Kemal中间件
 * [kemal-monetdb](https://github.com/puppetpies/kemal-monetdb) -  Kemal的MonetDB数据连接
 * [kemal-session](https://github.com/kemalcr/kemal-session) - 凯末尔的会话交易
 * [mime-types.cr](https://github.com/jwaldrip/mime-types.cr) -  Ruby MIME类型库的一个端口
 * [multi-auth](https://github.com/msa7/multi_auth) - 标准化的多提供商OAuth2身份验证（受omniauth启发）
 * [praetorian](https://github.com/ilanusse/praetorian) - 受Pundit启发的极简授权库
 * [request_id](https://github.com/SuperPaintman/request-id) - 用于生成/获取Crystal服务器的唯一请求ID的中间件
 * [response_time](https://github.com/SuperPaintman/response-time) -  Crystal服务器的响应时间（纯http服务器，kemal等）
 * [spec-kemal](https://github.com/kemalcr/spec-kemal) - 易于测试凯末尔

## Game Development
 * [cray](https://gitlab.com/Zatherz/cray) - 绑定 [raylib](http://www.raylib.com/)，一个易于使用的游戏开发库
 * [CrSFML](https://github.com/oprypin/crsfml) - 绑定到 [SFML](https://www.sfml-dev.org/) 多媒体/游戏库
 * [crystal-chipmunk](https://github.com/oprypin/crystal-chipmunk) - 绑定 [Chipmunk](http://chipmunk-physics.net/)，一个快速轻巧的2D游戏物理库
 * [glove](https://github.com/ddfreyne/glove) - 游戏开发库
 * [inari](https://github.com/ddfreyne/inari) - 使用Glove作为游戏引擎的游戏集合
 * [mos_game](https://github.com/bararchy/mos_game) - 迷你离线单人游戏

## GUI library
 * [hedron](https://github.com/Qwerp-Derp/hedron) - 具有标记语言功能的可扩展GUI库
 * [libui.cr](https://github.com/Fusion/libui.cr) - 绑定 [libui](https://github.com/andlabs/libui)
 * [qt5.cr](https://github.com/Papierkorb/qt5.cr) - 基于Bindgen的Crystal的Qt5绑定

## HTML Builders
 * [form_builder.cr](https://github.com/westonganger/form_builder.cr) -  Crystal的死简单HTML表单构建器，内置支持许多流行的UI库，如Bootstrap
 * [html_builder](https://github.com/crystal-lang/html_builder) - 用于创建HTML的DSL

## HTML/XML Parsing
 * [crystagiri](https://github.com/madeindjs/Crystagiri) - 像Html读者/解析器 [Nokogiri](https://github.com/sparklemotion/nokogiri) 红宝石宝石
 * [gumbo-crystal](https://github.com/blocknotes/gumbo-crystal) - 绑定 [Gumbo](https://github.com/google/gumbo-parser)，一个由Google制作的HTML5解析库
 * [hq.cr](https://github.com/maiha/hq.cr) -  crystal-xml的简单包装
 * [myhtml](https://github.com/kostya/myhtml) - 包含CSS选择器的快速HTML5分析器

## HTTP
 * [cossack](https://github.com/crystal-community/cossack) - 简单灵活的HTTP客户端
 * [crest](https://github.com/mamantoha/crest) - 简单的HTTP和REST客户端，受Ruby的RestClient gem的启发
 * [crul](https://github.com/porras/crul) - 命令行HTTP客户端
 * [cryload](https://github.com/sdogruyol/cryload) -  HTTP基准测试工具
 * [halite](https://github.com/icyleaf/halite) - 带有可链接REST API的Crystal HTTP请求，内置会话和记录器
 * [helmet](https://github.com/EvanHahn/crystal-helmet) - 设置与安全相关的HTTP标头
 * [http-multiserver.cr](https://github.com/vladfaust/http-multiserver.cr) - 通过路由安装多个服务器（也称为URL映射）
 * [http-params-serializable](https://github.com/vladfaust/http-params-serializable) -  HTTP params（de）序列化，适用于URL查询和URL编码形式
 * [http-protection](https://github.com/rogeriozambon/http-protection) - 防止典型的网络攻击
 * [http2](https://github.com/ysbaddaden/http2) -  HTTP / 2协议实现
 * [HTTP::Client](https://crystal-lang.org/api/HTTP/Client.html) -  HTTP客户端（Crystal stdlib）
 * [HTTP::Server](https://crystal-lang.org/api/HTTP/Server.html) -  HTTP服务器（Crystal stdlib）
 * [HTTP::WebSocket](https://crystal-lang.org/api/HTTP/WebSocket.html) -  HTTP WebSocket客户端（Crystal stdlib）
 * [keyer_cr](https://github.com/danielpclark/keyer_cr) - 将HTTP GET / POST参数解析添加为类似哈希的对象
 * [ngrok.cr](https://github.com/watzon/ngrok.cr) -  Ngrok包装纸
 * [params](https://github.com/vladfaust/params.cr) - 强类型HTTP params解析模块
 * [resp-crystal](https://github.com/soveran/resp-crystal) - 轻量级RESP客户端

## Image processing
 * [magickwand-crystal](https://github.com/blocknotes/magickwand-crystal) - 绑定 [MagickWand](https://www.imagemagick.org/script/magick-wand.php)，ImageMagick处理库的C接口
 * [stumpy_gif](https://github.com/stumpycr/stumpy_gif) - 写（动画）GIF图像
 * [stumpy_png](https://github.com/stumpycr/stumpy_png) - 读写PNG图像

## Implementations/Compilers
 * [charly](https://github.com/charly-lang) -  Charly编程语言
 * [cibyl](https://github.com/senselogic/CIBYL) - 轻量级花括号语言，编译为Ruby和Crystal
 * [cltk](https://github.com/ziprandom/cltk) -  Ruby Language Toolkit的水晶端口
 * [cppize](https://github.com/unn4m3d/cppize) -  Crystal-to-C ++转换器
 * [crisp](https://github.com/rhysd/Crisp) - 用Crystal实现的Lisp方言
 * [crow](https://github.com/geppetto-apps/crow) - 透明/编译Crystal到 [Flow](https://flow.org/)
 * [LinCAS-lang](https://github.com/LinCAS-lang) - 用于科学计算的编程语言
 * [mint-lang](https://github.com/mint-lang/mint) - 前端Web的一种令人耳目一新的编程语言
 * [myst-lang](https://github.com/myst-lang/) - 一种实用的动态语言，旨在尽可能轻松有效地编写和理解
 * [NuummiteOS](https://github.com/TheKernelCorp/NuummiteOS) - 用水晶作为概念证明编写的操作系统
 * [runic-lang](https://github.com/runic-lang) - 设计中的玩具语言

## Logging and monitoring
 * [crometheus](https://gitlab.com/ezrast/crometheus) - 一个 [Prometheus](https://prometheus.io/) 客户端库
 * [crystal-logreader](https://github.com/arcage/crystal-logreader) - 拖尾日志文件
 * [fluent-logger-crystal](https://github.com/TobiasGSmollett/fluent-logger-crystal) - 结构化记录器 [Fluentd](https://www.fluentd.org/)
 * [instana](https://github.com/instana/crystal-sensor) - 指标和分布式跟踪收集器 [Instana](https://www.instana.com/)
 * [katip](https://github.com/guvencenanguvenal/katip) -  JSONbase日志
 * [Logger](https://crystal-lang.org/api/Logger.html) - 日志实用程序（Crystal stdlib）
 * [statsd.cr](https://github.com/miketheman/statsd.cr) - [Statsd](https://github.com/etsy/statsd) 客户端库
 * [syslog.cr](https://github.com/comandeo/syslog.cr) -  Syslog客户端的实现

## Machine Learning
 * [ai4cr](https://github.com/drhuffman12/ai4cr) - 人工智能（基于https://github.com/SergioFierens/ai4r）
 * [crystal-fann](https://github.com/NeuraLegion/crystal-fann) -  FANN（快速人工神经网络）绑定
 * [crystal-learn](https://github.com/pbrusco/crystal-learn) - 类似Sklearn的机器学习库
 * [shainet](https://github.com/NeuraLegion/shainet) -  SHAInet（纯晶体中的神经网络）
 * [tensorflow.cr](https://github.com/fazibear/tensorflow.cr) - 绑定 [TensorFlow](https://github.com/tensorflow/tensorflow)

## Markdown/Text Processors
 * [html-pipeline](https://github.com/huacnlee/html-pipeline) -  HTML处理过滤器和实用程序
 * [markd](https://github.com/icyleaf/markd) - 另一种为速度而构建的降价解析器，符合CommonMark规范

## Misc
 * [aasm.cr](https://github.com/veelenga/aasm.cr) - 易于使用有限状态机的水晶类
 * [any_hash.cr](https://github.com/Sija/any_hash.cr) - 使用更好的JSON ::任何包含的递归哈希
 * [atomic_write.cr](https://github.com/chris-huxtable/atomic_write.cr) - 用于以原子方式编写或添加文件的库
 * [burocracia.cr](https://github.com/vnbrs/burocracia.cr) -  burocracia.cr dependecyless shard用于验证，生成和格式化巴西burocracias，如CPF，CNPJ和CEP
 * [callbacks](https://github.com/vladfaust/callbacks.cr) - 富有表现力的回调模块
 * [circuit_breaker](https://github.com/TPei/circuit_breaker) - 实现断路器模式
 * [compiled_license](https://github.com/elorest/compiled_license) - 在没有代码的情况下将二进制文件复制到系统或容器时，将许可证编译为二进制文件以便与MIT兼容
 * [crystal-binary_parser](https://github.com/DanSnow/crystal-binary_parser) - 二进制解析器
 * [crz](https://github.com/dhruvrajvanshi/crz) - 函数式编程库
 * [emoji.cr](https://github.com/veelenga/emoji.cr) - 表情符号库
 * [hoop](https://github.com/0x73/hoop) - 构建本机OSX应用程序
 * [i18n.cr](https://github.com/vladfaust/i18n.cr) - 国际化碎片
 * [immutable](https://github.com/lucaong/immutable) - 实现线程安全，持久，不可变的集合
 * [inflector.cr](https://github.com/phoffer/inflector.cr) -  Singularize，pluralize，camelize等（来自ActiveSupport的端口）
 * [lirith](https://github.com/lirith-engine/lirith) - 图形引擎
 * [m3u8](https://github.com/akiicat/m3u8) - 为HTTP Live Streaming生成并解析m3u8播放列表
 * [manual-generator](https://github.com/blocknotes/manual-generator) - 从文档站点生成PDF手册的工具
 * [message_verifier.cr](https://github.com/danielwestendorf/message_verifier.cr) - 验证并生成Rails`ActiveSupport :: MessageVerifier`签名的令牌
 * [pangu.cr](https://github.com/isaced/pangu.cr) -  Crystal中的偏执文本间距
 * [raytracer](https://github.com/l3kn/raytracer) - 带有示例的CPU Raytracer
 * [retriable.cr](https://github.com/Sija/retriable.cr) - 简单的DSL重试失败的代码块
 * [tren](https://github.com/sdogruyol/tren) - 给你的SQL一些爱
 * [ulid](https://github.com/SuperPaintman/ulid) - 通用独特的词典可排序标识符（ULID）

## Network Protocols
 * [bson.cr](https://github.com/jeromegn/bson.cr) - 原生BSON实施
 * [Crirc](https://github.com/Meoowww/Crirc) -  IRC协议实施（客户端，服务器，机器人）
 * [crystal-json-socket](https://github.com/foi/crystal-json-socket)   -  JSON套接字客户端和服务器实现.  灵感来自并兼容 [node-json-socket](https://github.com/sebastianseilund/node-json-socket/) 和 [ruby-json-socket](https://github.com/foi/ruby-json-socket)
 * [fast_irc.cr](https://github.com/RX14/fast_irc.cr) - 快速IRC解析器/生成器
 * [gopher.cr](https://github.com/anicholson/gopher.cr) -  Gopher服务器工具包
 * [jwt](https://github.com/crystal-community/jwt) -  JWT（JSON Web令牌）的实现
 * [msgpack-crystal](https://github.com/crystal-community/msgpack-crystal) -  MessagePack库
 * [OAuth](https://crystal-lang.org/api/OAuth.html) -  OAuth消费者（Crystal stdlib）
 * [OAuth2](https://crystal-lang.org/api/OAuth2.html) -  OAuth2客户端（Crystal stdlib）
 * [OpenSSL](https://crystal-lang.org/api/OpenSSL.html) - 绑定到libssl（Crystal stdlib）
 * [Socks](https://github.com/wontruefree/socks) -  SOCKS代理
 * [transfer_more](https://git.sceptique.eu/Sceptique/transfer_more) - 克隆transfer.sh以上传文件

## Networking
 * [ipaddress.cr](https://github.com/Sija/ipaddress.cr) - 用于处理IPv4和IPv6地址的库

## ORM/ODM Extensions
 * [clear](https://github.com/anykeyh/clear) -  ORM专门针对PostgreSQL，但具有高级功能
 * [granite](https://github.com/amberframework/granite) -  Postgres，Mysql，Sqlite的ORM
 * [jennifer.cr](https://github.com/imdrasil/jennifer.cr) - 使用灵活的查询可链接构建器和迁移系统实现Active Record模式
 * [ohm-crystal](https://github.com/soveran/ohm-crystal) -  Redis的Object-hash映射库
 * [onyx-sql](https://github.com/onyxframework/sql) - 与DB无关的SQL ORM，具有漂亮的DSL和类型安全的查询构建器
 * [record](https://github.com/luckyframework/record) - 键入安全查询，保存和更新
 * [redis-tsv.cr](https://github.com/maiha/redis-tsv.cr) - 以TSV格式从Redis导入和导出数据
 * [stal-crystal](https://github.com/soveran/stal-crystal) - 为Redis设置代数求解器
 * [topaz](https://github.com/topaz-crystal/topaz) - 一个简单而有用的db包装器

## Package Management
 * [CRelease](https://github.com/elorest/crelease) - 版本和git标签管理器，使分片发布变得容易
 * [shards](https://github.com/crystal-lang/shards) -  Crystal的依赖管理器

## Processes and Threads
 * [await_async](https://github.com/anykeyh/await_async) - 在Crystal Lang中添加关键词await＆async
 * [crystal-futures](https://github.com/dhruvrajvanshi/crystal-futures) - 未来类型实施
 * [neph](https://github.com/tbrand/neph) - 可以同时执行作业的现代命令行作业处理器
 * [promise](https://github.com/spider-gazelle/promise) - 使用类型推断的Promise实现

## Project Generators
 * [bindgencr](https://github.com/TechMagister/bindgencr) - 基于castxml输出的绑定生成器
 * [crystal_lib](https://github.com/crystal-lang/crystal_lib) - 本机库的自动绑定生成器
 * [fez](https://github.com/jwoertink/fez) -  Kemal应用程序生成器
 * [kgen](https://github.com/kemalyst/kemalyst-generator) - 用于控制台，init，生成（脚手架）和监视的Kemalyst命令行工具.
 * [libgen](https://github.com/olbat/libgen) - 使用JSON / YAML文件配置的自动绑定生成器
 * [wasp](https://github.com/icyleaf/wasp) - 静态站点生成器

## Queues and Messaging
 * [amqp.cr](https://github.com/datanoise/amqp.cr) - 带有RabbitMQ扩展的AMQP 0.9.1客户端
 * [dispatch](https://github.com/bmulvihill/dispatch) - 在内存中异步作业处理
 * [mosquito](https://github.com/robacarp/mosquito/) -  Redis支持定期和临时作业处理
 * [sidekiq.cr](https://github.com/mperham/sidekiq.cr) - 简单，高效的工作处理

## Routing
 * [crouter](https://github.com/jreinert/crouter) - 独立路由器
 * [orion](https://github.com/obsidian/orion) - 最小的rails-esque路由库
 * [router.cr](https://github.com/tbrand/router.cr) -  HTTP :: Server的最小但功能强大的http路由器
 * [toro](https://github.com/soveran/toro) - 面向树的路由

## Scheduling
 * [cron_scheduler](https://github.com/kostya/cron_scheduler) - 具有crontab模式的作业调度程序
 * [crystime](https://gitlab.com/crystallabs/crystime) - 高级时间，日历，日程安排和提醒库
 * [schedule.cr](https://github.com/hugoabonizio/schedule.cr) - 运行定期任务
 * [tasker](https://github.com/spider-gazelle/tasker) - 高精度调度程序，包括时区感知cron作业

## Science and Data analysis
 * [linalg](https://github.com/konovod/linalg) - 受MATLAB和SciPy.linalg启发的线性代数库
 * [predict.cr](https://github.com/RX14/predict.cr) - 使用sgp4模型的卫星预测库
 * [stats](https://git.sceptique.eu/Sceptique/stats) - 统计分布的表达实施

## Search
 * [hermes](https://github.com/imdrasil/hermes.cr) -  ElastiSearch的Data Mapper模式实现
 * [query-builder](https://github.com/izniburak/query-builder) -  Sql Query Builder库
 * [query.cr](https://github.com/waterlink/query.cr) - 查询抽象
 * [soegen](https://github.com/Ragmaanir/soegen) -  Crystal的Elasticsearch客户端类似于ruby的stretcher gem

## Serverless Computing
 * [crystal_openfaas](https://github.com/TPei/crystal_openfaas/) - 模板使水晶成为OpenFaaS中的一等公民
 * [FaaStRuby](https://faastruby.io) - 用于Ruby和Crystal的无服务器软件开发平台.
 * [gcf.cr](https://github.com/sam0x17/gcf.cr) - 在Google Cloud Functions中管理Crystal的执行

## System
 * [baked_file_system](https://github.com/schovi/baked_file_system) - 虚拟文件系统实现
 * [hardware](https://github.com/crystal-community/hardware) - 获取正在运行的操作系统及其进程的CPU，内存和网络信息
 * [rcpu](https://github.com/ddfreyne/rcpu) - 虚拟机模拟器和汇编器

## Task management
 * [cake](https://github.com/axvm/cake) - 生产就绪的Make-like实用工具
 * [sam](https://github.com/imdrasil/sam.cr) - 另一个具有命名空间和参数系统的类似Rake的任务管理器

## Template Engine
 * [crinja](https://github.com/straight-shoota/crinja) - 执行 [Jinja2 template engine](http://jinja.pocoo.org/)
 * [crustache](https://github.com/MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) 为水晶
 * [ECR (Embedded Crystal)](https://crystal-lang.org/api/ECR.html) - 编译时间模板语言，使用普通水晶表达式（Crystal stdlib）
 * [Kilt](https://github.com/jeromegn/kilt) - 模板引擎的抽象层
 * [Slang](https://github.com/jeromegn/slang) - 轻巧，简洁，模板化的语言，灵感来自Ruby的Slim
 * [teeplate](https://github.com/mosop/teeplate) - 用于呈现多个模板文件的库
 * [temel](https://github.com/f/temel) -  Crystal的可扩展HTML :: Builder替代方案，支持自定义标记定义

## Testing
 * [coverage](https://github.com/anykeyh/crystal-coverage) - 为您的水晶代码生成封面报告
 * [crotest](https://github.com/emancu/crotest) - 一个简单而简单的测试框架
 * [crystal-clear](https://github.com/Groogy/crystal-clear) - 合同库设计
 * [crytic](https://github.com/hanneskaeufler/crytic) - 变异测试框架
 * [LuckyFlow](https://github.com/luckyframework/lucky_flow) - 类似于Capybara的自动浏览器测试
 * [mass-spec](https://github.com/c910335/mass-spec) -  Web API测试库
 * [microtest](https://github.com/Ragmaanir/microtest) - 关注电源断言的小型固定测试库
 * [minitest.cr](https://github.com/ysbaddaden/minitest.cr) - 用于单元测试和断言的库
 * [mocks.cr](https://github.com/waterlink/mocks.cr) - 模拟水晶库
 * [Spec](https://crystal-lang.org/api/Spec.html) -  spec框架（Crystal stdlib）
 * [timecop.cr](https://github.com/crystal-community/timecop.cr)   - 使用`Time.now`进行模拟的库.  灵感来自于 [timecop ruby gem](https://github.com/travisjeffery/timecop)
 * [webdriver_pump](https://github.com/bwilczek/webdriver_pump)   - 页面对象库.  灵感来自Ruby [WatirPump](https://github.com/bwilczek/watir_pump)
 * [webmock.cr](https://github.com/manastech/webmock.cr) - 用于存根“HTTP :: Client”请求的库

## Third-party APIs
 * [aws-signer.cr](https://github.com/beanieboi/aws-signer.cr) - 此库使用AWS v4签署您的HTTP请求
 * [awscr-s3](https://github.com/taylorfinnell/awscr-s3) -  AWS S3界面
 * [awscr-signer](https://github.com/taylorfinnell/awscr-signer) - 签署HTTP ::请求对象并生成预先签署的帖子表格
 * [bugsnag.cr](https://github.com/gewo/bugsnag.cr) -  Bugsnag异常通知程序和sidekiq中间件
 * [crystal-darksky](https://github.com/sb89/crystal-darksky) - 包装纸 [Dark Sky](https://darksky.net) API
 * [crystal-github](https://github.com/felipeelias/crystal-github) - 包装纸 [Github](https://github.com/) API
 * [crystal-monzo](https://github.com/barisbalic/crystal-monzo) - A client for the [Monzo API](https://monzo.com/docs/)
 * [crystal-swapi](https://github.com/sb89/crystal-swapi) - 星球大战API（SWAPI）包装器
 * [crystal_slack](https://github.com/manastech/crystal_slack) - 解析Slack斜杠命令或发送传入Web挂钩的工具
 * [discordcr](https://github.com/meew0/discordcr) - 极简主义的Discord API库
 * [GDAX](https://github.com/mccallofthewild/gdax) - 请求签名的GDAX REST和WebSocket API Wrapper
 * [gitlab.cr](https://github.com/icyleaf/gitlab.cr) -  GitLab API包装器
 * [google_maps_api](https://github.com/fridgerator/google_maps_api) -  Google Maps API
 * [hncr](https://github.com/Gangwolf/hncr) - 黑客新闻API包装器
 * [mixpanel-crystal](https://github.com/petoem/mixpanel-crystal) - 用于向Mixpanel发送事件的库
 * [nexmo-crystal](https://github.com/timcraft/nexmo-crystal) - [Nexmo REST API](https://developer.nexmo.com/) 客户
 * [open_exchange_rates](https://github.com/osfx/open_exchange_rates) - 访问的图书馆 [Open Exchange Rates](https://openexchangerates.org/) API
 * [pinboard.cr](https://github.com/oz/pinboard.cr) - [Pinboard](https://pinboard.in) API
 * [raven.cr](https://github.com/sija/raven.cr) -  Raven是客户 [Sentry](https://github.com/getsentry/sentry)
 * [slack.cr](https://github.com/DougEverly/slack.cr) - 一个松弛 [Real Time Messaging API](https://api.slack.com/rtm) WebSocket客户端库
 * [telegram_bot](https://github.com/hangyas/telegram_bot) -  Telegram Bot API的包装器
 * [twitter-crystal](https://github.com/sferik/twitter-crystal) - 用于访问Twitter API的库

## Validation
 * [accord](https://github.com/neovintage/accord) -  Crystal Objects的可共享验证库
 * [CrSerializer](https://github.com/blacksmoke16/CrSerializer) - 基于可扩展注释的序列化/反序列化/验证库
 * [denetmen](https://github.com/izniburak/denetmen) - 用于修补Crystal stdlib的微检查库
 * [validations](https://github.com/vladfaust/validations.cr) - Validations mixin

## Web Frameworks
 * [amber](https://github.com/amberframework/amber) - 开源高效且具有凝聚力的Web应用程序框架
 * [kemal](https://github.com/kemalcr/kemal)   -  Lightning Fast，超级简单的Web框架.  灵感来自Sinatra
 * [lattice-core](https://github.com/jasonl99/lattice-core) - 一个WebSocket优先的面向对象框架（基于Kemal）
 * [lucky](https://github.com/luckyframework/lucky) - 尽早捕获错误，忘记大多数性能问题，花更多时间在代码上而不是调试和编写测试
 * [onyx-rest](https://github.com/onyxframework/rest) -  REST API框架，具有类型安全的参数和独立的业务和渲染层，基于 [onyx-http](https://github.com/onyxframework/http)
 * [raze](https://github.com/samueleaton/raze) - 模块化，轻型Web框架
 * [spider-gazelle](https://github.com/spider-gazelle/spider-gazelle) - 一个专注于速度和可扩展性的Rails esque Web框架

## Web Servers
 * [fast-http-server](https://github.com/sdogruyol/fast-http-server) - 超快速，零配置命令行HTTP服务器
 * [prax.cr](https://github.com/ysbaddaden/prax.cr) - 用于开发的机架代理服务器
 * [salt](https://github.com/icyleaf/salt) -  HTTP服务器的人性化界面
 * [serve](https://github.com/SuperPaintman/serve) - 命令行静态HTTP服务器

## Community
 * [Crystal weekly newsletters](http://crystalweekly.com/)
 * [Gitter](https://gitter.im/crystal-lang/crystal)
 * [Google Group](https://groups.google.com/forum/?fromgroups#!forum/crystal-lang)
 * [IRC](http://irc.lc/freenode/crystal-lang) - #crystal-lang on Freenode
 * [Metaruby](https://metaruby.com/c/crystal-forum) -  Metaruby水晶论坛
 * [Reddit](https://www.reddit.com/r/crystal_programming/)
 * [Stackoverflow](https://stackoverflow.com/tags/crystal-lang/info)

## Unofficial
 * [Russian-speaking Telegram Group](https://t.me/crystal_ru) - 欢迎，同志们！

## Resources
 * [Crystal for Rubyists](http://www.crystalforrubyists.com/) - 免费预订您的水晶之旅
 * [Crystal Mastery](https://crystalmastery.io/) - 用于学习Crystal的截屏视频
 * [crystal-lang.org](https://crystal-lang.org) - 官方语言网站
 * [devdocs.io](https://devdocs.io/crystal/) - 具有Crystal支持的API文档浏览器
 * [getgood.at](https://getgood.at/crystal/in-a-day) - 一天学习水晶
 * [Programming Crystal](https://pragprog.com/book/crystal/programming-crystal) -  PragProg书开始你的水晶之旅

## Official Documentation Translations
 * [br.crystal-lang.org](http://br.crystal-lang.org/) - 巴西人
 * [ja.crystal-lang.org](http://ja.crystal-lang.org/) - 日本人
 * [kr.crystal-lang.org](https://kr.crystal-lang.org/) - 韩国人
 * [ru.crystal-lang.org](http://ru.crystal-lang.org/) - 俄罗斯
 * [tw.crystal-lang.org](http://tw.crystal-lang.org/) - 中国传统

## Services and Apps
 * [carc.in](https://carc.in/) - 运行代码并显示结果的Web服务
 * [cry](https://github.com/elorest/cry) - 能够以类似于Ruby的pry编辑的方式执行水晶代码
 * [Crystal [ANN]]（https://crystal-ann.com） - 宣布新项目，博客文章，版本更新或任何其他Crystal工作
 * [crystalshards.herokuapp.com](https://crystalshards.herokuapp.com/), [crystalshards.xyz](http://crystalshards.xyz/) - 列出所有可用Crystal分片的Web服务
 * [Crystular](http://www.crystular.org) - 正则表达式测试仪
 * [DeBot](https://github.com/jhass/DeBot) - 用Crystal写的IRC bot
 * [Fluence](https://github.com/crystallabs/fluence) - 使用markdown和Git的WYSIWYG wiki
 * [icr](https://github.com/crystal-community/icr) -  Crystal的交互式控制台（如Ruby的IRB）
 * [Invidious](https://github.com/omarroth/invidious) -  Invidious是YouTube的另一个前端
 * [mpngin](https://github.com/thewalkingtoast/mpngin) - 具有简单统计信息的URL缩短器
 * [nes](https://github.com/romeroadrian/nes.cr) -  NES模拟器
 * [quicktype](https://quicktype.io/) - 从JSON，JSON Schema，GraphQL和TypeScript生成模型和序列化程序
 * [shards.info](http://shards.info/)   -  Web服务，列出GitHub上包含Crystal代码的所有存储库.  资料来源可用 [GitHub](https://github.com/mamantoha/shards-info)
 * [wikicr](https://git.sceptique.eu/Sceptique/wikicr) - 使用git管理修订版的Wiki

## Tools
 * [ast_helper](https://github.com/bcardiff/crystal-ast-helper) - 帮助调试解析器和格式化程序的工具
 * [crystal-base](https://github.com/ruivieira/crystal-base) - 用于Crystal开发的CentOS基础docker镜像
 * [crystal-ctags](https://github.com/SuperPaintman/crystal-ctags) - 用于水晶的Ctags发生器
 * [crystal-dash-docset](https://github.com/Sija/crystal-dash-docset) - [Dash](https://kapeli.com/dash) docset生成器
 * [helptransl8](https://github.com/papilip/helptransl8) - 文档翻译工具

## DevOps
 * [ansible-crystal](https://github.com/CorbanR/ansible-crystal) - 用于安装水晶的Ansible剧本
 * [capistrano-kemal](https://github.com/bitfex/capistrano-kemal) -  Kemal的Capistrano插件
 * [crystal-cookbook](https://github.com/vjdhama/crystal-cookbook) - 用于安装水晶的厨师食谱
 * [DPPM](https://github.com/DFabric/dppm) - 一种简单，通用的方式来安装和管理应用程序（主要是Linux）

## Editor Plugins
 *原子
   * [crystal-tools](https://atom.io/packages/crystal-tools) - 在Crystal编译器中启用内置工具
   * [language-crystal-actual](https://atom.io/packages/language-crystal-actual) -  Atom中的Crystal语言支持
 * Emacs
   * [emacs-crystal-mode](https://github.com/dotmilk/emacs-crystal-mode) - 对Emacs的Crystal语言支持
   * [play-crystal.el](https://github.com/veelenga/play-crystal.el) - [play.crystal-lang.org](https://play.crystal-lang.org/#/cr) 在Emacs中集成
 * [scry](https://github.com/crystal-lang-tools/scry) -  Crystal实现的代码分析服务器 [Language Server Protocol](https://microsoft.github.io/language-server-protocol/)
 * Spacemacs
   * [crystal-spacemacs-layer](https://github.com/juanedi/crystal-spacemacs-layer) -  Crystal的Spacemacs贡献层
 *崇高
   * [sublime-crystal](https://github.com/crystal-lang-tools/sublime-crystal) - 用于崇高文本的Crystal语法高亮显示
 * TextMate
   * [Crystal.tmbundle](https://github.com/crystal-lang-tools/Crystal.tmbundle) -  Crystal语法高亮，编译，格式化命令，片段
 *来到
   * [carcin.vim](https://github.com/MakeNowJust/carcin.vim) -  Vim插件，为carc.in提供实用功能
   * [vim-crystal](https://github.com/rhysd/vim-crystal) - 对Crystal的Vim文件类型支持
   * [vim-slang](https://github.com/elorest/vim-slang) - 对Slang Templating Engine的Vim文件类型支持
 * Visual Studio代码
   * [vscode-crystal](https://github.com/g3ortega/vscode-crystal) -  VSCode中的Crystal语言支持
   * [vscode-crystal-ide](https://github.com/crystal-lang-tools/crystal-ide) -  Crystal IDE驱动 [Language Server Protocol](https://code.visualstudio.com/blogs/2016/06/27/common-language-protocol)
   * [vscode-crystal-lang](https://github.com/crystal-lang-tools/vscode-crystal-lang) - `cr`和`ecr`文件的格式化程序，linter和语法高亮显示

## Shell plugins
 * [crun](https://github.com/Val/crun) -  Crystal Run：水晶的shebang包装
 * [crystal-zsh](https://github.com/veelenga/crystal-zsh) -  .oh-my-zsh插件
