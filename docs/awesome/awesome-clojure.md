<div class="github-widget" data-repo="razum2um/awesome-clojure"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

  - [Penpot](https://penpot.app/): 设计和原型制作平台
  - [LightTable (IDE)](http://lighttable.com/)
  - [Maria.cloud (Online IDE for beginners)](https://www.maria.cloud/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [Precursor (Online prototyping tool)](https://precursorapp.com/)
  - [Puppet Server](https://github.com/puppetlabs/puppet-server)
  - [PuppetDB](https://github.com/puppetlabs/puppetdb)
  - [Metabase](https://github.com/metabase/metabase)
  - [Metabase Datomic](https://github.com/lambdaisland/metabase-datomic)
  - [CircleCI](https://circleci.com/)
  - [asciinema](https://asciinema.org/)
  - [Avi (vim rewrite)](https://github.com/maitria/avi)
  - [Liquid (Text Editor)](https://github.com/mogenslund/liquid)
  - [Clojupyter](https://github.com/clojupyter/clojupyter)
  - [meins](https://github.com/matthiasn/meins)
  - [Jepsen](https://github.com/jepsen-io/jepsen)
  - [Braid](https://github.com/braidchat/braid)：具有新颖 UI 的团队聊天应用程序，可带来更好的对话
  - [Accelerated Text](https://github.com/tokenmill/accelerated-text)：自然语言生成环境（后端：Clojure，前端：JS）
  - [Ziggurat](https://github.com/gojek/ziggurat)：为简化Kafka上的流处理而构建的框架
  - [Nightcode](https://github.com/oakes/Nightcode)：Clojure 的 IDE（已存档）
  - [Nightlight](https://github.com/oakes/Nightlight)：文本编辑器（存档）
  - [Atea](https://github.com/pkamenarsky/atea)：MacOS 的简约菜单栏时间跟踪器（旧版，需要 jvm 1.6）
  - [Logseq](https://github.com/logseq/logseq)：知识管理和协作（开放前端）
  - [jank](https://github.com/jeaye/jank)
  - [lux](https://github.com/LuxLang/lux)
  - [mal](https://github.com/kanaka/mal/tree/master/impls/clojure)
  - [scheje](https://github.com/turbopape/scheje)
  - [eden](https://github.com/benzap/eden)


## Awesome macros usage

*回答为什么 lisp 闪耀，杀手级功能在行动*

  * [core.async](https://github.com/clojure/core.async) - 将 AST 转换为 CSP 程序
  * [cloroutine](https://github.com/leonoel/cloroutine) - 暂停和继续（协程）
  * [missionary](https://github.com/leonoel/missionary) - 反应式数据流编程工具包
  * [photon](https://github.com/venantius/photon) - 实时网络，如 Meteor，但适用于 Clojure（脚本）
  * [metaclj](https://github.com/brandonbloom/metaclj) - 分阶段编译
  * [meander](https://github.com/noprompt/meander) - 使用数据结构模式匹配的透明数据转换
  * [proteus](https://github.com/ztellman/proteus) - 引入可变变量（不要使用，只需学习如何将您的思想映射到不可变的世界）
## Advanced datastructures

  * [specter](https://github.com/redplanetlabs/specter)：用于查询和转换嵌套和递归数据的优雅 API
  * [meander](https://github.com/noprompt/meander): 透明数据转换（定义为模式匹配）
  * [Persistent AVL trees](https://github.com/clojure/data.avl)：具有日志时间排名查询的持久排序映射和集合
  * [Finger Tree](https://github.com/clojure/data.finger-tree): 双列表, 计数双列表, 计数排序集
  * [Hitchhiker Tree](https://github.com/datacrypt-project/hitchhiker-tree)：创建快速、可快照、可大规模扩展的数据库
  * [Hierarchical set](https://github.com/llasram/hier-set)
  * [Ordered](https://github.com/amalloy/ordered): 有序集和映射
  * [Lazy Map](https://github.com/Malabarba/lazy-map-clojure): 仅在访问时计算其值
  * [Duratom](https://github.com/jimpil/duratom): 持久化原子
  * [Durable Queue](https://github.com/Factual/durable-queue)：队列保留在磁盘上
  * [bifurcan](https://github.com/lacuna/bifurcan): 线性映射/设置/列表（在内存中连续存储条目），; 用 java 编写，但测试套件（阅读：用法示例） [in clojure](https://github.com/lacuna/bifurcan/blob/master/test/bifurcan)
  
## Web Framework

*其实不要在这里搜索 rails/django，而是自己编写它们*
  * [Compojure](https://github.com/weavejester/compojure)
  * [Compojure-api](https://github.com/metosin/compojure-api)
  * [Luminus](http://www.luminusweb.net/)
  * [Duct](https://github.com/weavejester/duct)
  * [Pedestal](https://github.com/pedestal/pedestal)
  * [Datsys](https://github.com/metasoarous/datsys)
  * [yada](https://github.com/juxt/yada)
  * [Hoplon](http://hoplon.io/)
  * [Fulcro](https://github.com/fulcrologic/fulcro)
  * [Coast](http://coastonclojure.com/)
  * [Reitit](https://github.com/metosin/reitit)
  * [Tadam](https://www.tadam-framework.dev/)

## Dependency injection

*有状态对象的管理生命周期*

  * [Component](https://github.com/stuartsierra/component)
  * [System](https://github.com/danielsz/system)
  * [mount](https://github.com/tolitius/mount)
  * [Integrant](https://github.com/weavejester/integrant)
  * [clip](https://github.com/juxt/clip)
  * [piotr-yuxuan/closeable-map](https://github.com/piotr-yuxuan/closeable-map)

## Build Automation and Package management

*用于项目构建自动化和包/依赖项管理的库.*

  * [Leiningen](https://github.com/technomancy/leiningen)
  * [Boot](https://github.com/boot-clj/boot)
  * [clojurephant](https://github.com/clojurephant/clojurephant) （Gradle 插件）
  * [shadow-cljs](https://github.com/thheller/shadow-cljs) （Clojurescript）

## Version Control Management

*用于与 VCS 软件交互的代码实用程序*

  * [clj-jgit](https://github.com/clj-jgit/clj-jgit)

## Date and Time

*用于处理日期和时间的库.*

  * [clj-time](https://github.com/clj-time/clj-time)
  * [clojure.java-time](https://github.com/dm3/clojure.java-time) - Java 8 日期时间 API
  * [timewords](https://github.com/tokenmill/timewords)
  * [tick](https://github.com/juxt/tick): Clojure(Script) 库，旨在替代 clj-time

## GUI

  * [seesaw](https://github.com/daveray/seesaw)
  * [trikl](https://github.com/lambdaisland/trikl)
  * [fx-clj](https://github.com/aaronc/fx-clj)

## Audio

  * [Overtone](http://overtone.github.io/)
  * [Alda](https://github.com/alda-lang/alda)

## HTTP

*用于处理 HTTP 的库.*

  * [clj-http](https://github.com/dakrone/clj-http) ：Apache HttpComponents 客户端包装器
  * [http-kit](https://github.com/http-kit/http-kit) ：简单、高性能的事件驱动的 HTTP 客户端和服务器
  * [ring](https://github.com/ring-clojure/ring) : HTTP 服务器抽象
  * [kvlt](https://github.com/nervous-systems/kvlt) ：跨 JVM/节点/浏览器的 HTTP 统一异步客户端接口
  * [aleph](https://github.com/clj-commons/aleph) : 基于 Netty 的异步客户端/服务器，默认为 HTTP、TCP 和 UDP
  * [hato](https://github.com/gnarroway/hato) : Clojure 的 HTTP 客户端，包装了 JDK 11 的 HttpClient

## Database

*数据库和数据库客户端库*

  * [Datomic](http://www.datomic.com/)
  * [xtdb](https://github.com/xtdb/xtdb)：用于 SQL、Datalog 和图形查询的双时态数据库
  * [Datahike](https://github.com/replikativ/datahike)
  * [Datascript](https://github.com/tonsky/datascript)
  * [Datalevin](https://github.com/juji-io/datalevin)
  * [next.jdbc](https://github.com/seancorfield/next-jdbc)
  * [clojure.java.jdbc](https://github.com/clojure/java.jdbc)
  * [clojure.jdbc](https://github.com/funcool/clojure.jdbc)
  * [cravendb](https://github.com/robashton/cravendb)
  * [Monger](http://clojuremongodb.info/): 对于 MongoDB
  * [Monglorious](https://baumandm.github.io/monglorious/): 对于 MongoDB
  * [clj-rethinkdb](https://github.com/apa512/clj-rethinkdb): 对于 RethinkDB
  * [Revise](https://github.com/bitemyapp/revise): 对于 RethinkDB
  * [Spandex](https://github.com/mpenet/spandex): 用于弹性搜索
  * [Elastisch](http://clojureelasticsearch.info/): 用于弹性搜索
  * [neocons](http://clojureneo4j.info/): 对于 Neo4j
  * [Alia](https://github.com/mpenet/alia): 对于卡桑德拉
  * [aerospike-clj](https://github.com/AppsFlyer/aerospike-clj): 用于 Aerospike

## Connection pools

*数据库连接池*

  * [hikari-cp](https://github.com/tomekw/hikari-cp)
  * [metabase/connection-pool](https://github.com/metabase/connection-pool)

## Structural Migrations

*保持数据库和其他同步*

  * [Lobos](https://github.com/budu/lobos)
  * [Ragtime](https://github.com/weavejester/ragtime)
  * [Joplin](https://github.com/juxt/joplin)
  * [Migratus](https://github.com/yogthos/migratus)
  * [Drift](https://github.com/macourtney/drift)

## Redis

  * [carmine](https://github.com/ptaoussanis/carmine)
  * [celtuce](https://github.com/lerouxrgd/celtuce)

## JSON

  * [cheshire](https://github.com/dakrone/cheshire)
  * [jsonista](https://github.com/metosin/jsonista)

## Database Cli

## ORM and SQL generation

*用于 SQL 生成的 DSL.*
  * [Walkable](https://github.com/walkable-server/walkable)
  * [Korma](https://github.com/korma/Korma)
  * [Specql](https://github.com/tatut/specql/)
  * [stch-library/sql](https://github.com/stch-library/sql)
  * [sqlingvo](https://github.com/r0man/sqlingvo)
  * [sqlium](https://github.com/TheLadders/sqlium/)
  * [honeysql](https://github.com/jkk/honeysql)
  * [Toucan](https://github.com/metabase/toucan)

## Security

*身份验证、授权和其他安全相关的库.*

  * [Buddy](https://github.com/funcool/buddy)
  * [caesium](https://github.com/lvh/caesium) （libsodium 绑定）
  * [Friend](https://github.com/cemerick/friend)
  * [secrets.clj](https://github.com/lk-geimfari/secrets.clj)
  * [bolt](https://github.com/juxt/bolt)

## RESTful API

*用于开发 RESTful API 的库.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [Compojure-api](https://github.com/metosin/compojure-api)
  * [Friboo](https://github.com/zalando/friboo)
  * [yada](https://github.com/juxt/yada)
  * [router](https://github.com/darkleaf/router)
  * [reitit](https://github.com/metosin/reitit)

## GraphQL API

*用于开发 GraphQL API 的库.*

  * [Lacinia](https://lacinia.readthedocs.io/en/latest/)

## Emails

  * [postal](https://github.com/drewr/postal)

## HTML Manipulation

*用于处理 HTML 的库.*

  * [Enlive](https://github.com/cgrand/enlive/wiki)
  * [hiccup](https://github.com/weavejester/hiccup)
  * [clostache](https://github.com/fhd/clostache)
  * [selmer](https://github.com/yogthos/Selmer)

## Data Validation

*用于验证数据的库.*

  * [Validateur](http://clojurevalidations.info/)
  * [Prismatic's schema](https://github.com/plumatic/schema)
  * [Bouncer](https://github.com/leonardoborges/bouncer)
  * [clova](https://github.com/markwoodhall/clova)
  * [Orchestra](https://github.com/jeaye/orchestra)
  * [struct](https://github.com/funcool/struct)
  * [domaintypes](https://github.com/friemen/domaintypes)

## Type System
*Clojure 的可选类型系统*

  * [core.typed](https://github.com/clojure/core.typed)

## Pattern Matching

  * [core.match](https://github.com/clojure/core.match)
  * [defun](https://github.com/killme2008/defun)
  * [cats.match](https://github.com/zalando/cats.match)
  * [Akar](https://github.com/missingfaktor/akar)
  * [Meander](https://github.com/noprompt/meander)
  * [Verbal-Exprejon](https://github.com/WeshGuillaume/Verbal-Exprejon)

## Async processing

  * [core.async](https://github.com/clojure/core.async/)
  * [pulsar](https://github.com/puniverse/pulsar)
  * [manifold](https://github.com/ztellman/manifold)

## Monads

  * [cats](https://github.com/funcool/cats)
  * [algo.monads](https://github.com/clojure/algo.monads)
  * [Fluokitten](https://github.com/uncomplicate/fluokitten)

## WebSocket

  * [Chord](https://github.com/jarohen/chord)
  * [Sente](https://github.com/ptaoussanis/sente)
  * [aleph](https://github.com/ztellman/aleph)

## Testing

  * [Expectations](https://github.com/clojure-expectations/expectations)
  * [Midje](https://github.com/marick/Midje)
  * [test-doubles](https://github.com/GreenPowerMonitor/test-doubles) 
  * [kaocha](https://github.com/lambdaisland/kaocha)

## Webdriver automation

  * [Etaoin](https://github.com/igrishaev/etaoin)

## Code Analysis and Linter

  * [Slamhound](https://github.com/technomancy/slamhound)
  * [eastwood](https://github.com/jonase/eastwood)
  * [kibit](https://github.com/jonase/kibit)
  * [yagni](https://github.com/venantius/yagni)
  * [lein-bikeshed](https://github.com/dakrone/lein-bikeshed)
  * [spectrum](https://github.com/arohner/spectrum)
  * [cloverage](https://github.com/cloverage/cloverage)
  * [clj-kondo](https://github.com/borkdude/clj-kondo)

## Science and Data Analysis

*用于科学和统计数据的库、扩展 REPL 和其他工具
分析和可视化. *

  * [Incanter](https://github.com/incanter/incanter)
  * [Cascalog](http://cascalog.org/)
  * [Onyx](https://github.com/onyx-platform/onyx)
  * [sparklling](https://github.com/gorillalabs/sparkling)
  * [flambo](https://github.com/yieldbot/flambo)
  * [Neanderthal](https://github.com/uncomplicate/neanderthal)
  * [Streaming Histograms](https://github.com/bigmlcom/histogram)
  * [Gorilla REPL](http://gorilla-repl.org/)  
  * [Bayadera - Bayesian Data Analysis on the GPU](https://github.com/uncomplicate/bayadera)
  * [ClojureCUDA](https://github.com/uncomplicate/clojurecuda)
  * [Neanderthal - fast matrix and linear algebra](https://github.com/uncomplicate/neanderthal)
  * [ClojureCL - parallel computations with OpenCL](https://github.com/uncomplicate/clojurecl)
  * [Loom - graph library for Clojure](https://github.com/aysylu/loom)

## Machine Learning

  * [neanderthal](https://github.com/uncomplicate/neanderthal)：快速矩阵库
  * [clojurecuda](https://github.com/uncomplicate/clojurecuda)
  * [clojurecl](https://github.com/uncomplicate/clojurecl)
  * [bayadera](https://github.com/uncomplicate/bayadera): GPU 上的贝叶斯数据分析
  * [cortex](https://github.com/originrose/cortex)
  * [Flare](https://github.com/aria42/flare)
  * [MXNet - Clojure API](https://mxnet.apache.org/versions/1.7.0/api/clojure)
  * [clj-bigml](https://github.com/bigmlcom/clj-bigml)
  * [Deeplearning4j](https://github.com/deeplearning4j/deeplearning4j)
  * [Enclog](https://github.com/jimpil/enclog)
  * [lambda-ml](https://github.com/cloudkj/lambda-ml)
  * [clojure-tensorflow](https://github.com/kieranbrowne/clojure-tensorflow)
  * [dl4clj (deeplearning4j to clojure)](https://github.com/yetanalytics/dl4clj)
  * [Anglican](https://probprog.github.io/anglican/)
  * [clj-ml](https://github.com/antoniogarrote/clj-ml)
  * [Clatern](https://github.com/rinuboney/clatern)
  * [k9](https://github.com/gigasquid/k9)
  * [Statistiker](https://github.com/clojurewerkz/statistiker)
  * [Synaptic](https://github.com/japonophile/synaptic)
  * [Infer](https://github.com/aria42/infer)
  * [clj-synapses](https://github.com/mrdimosthenis/clj-synapses)
  * [scicloj.ml](https://github.com/scicloj/scicloj.ml)

## Computer Vision

  * [origami](https://github.com/hellonico/origami)：OpenCV 4 包装器
  * [clj-tesseract](https://github.com/antoniogarrote/clj-tesseract)
  * [vision](http://nakkaya.com/vision.html)

## Text Processing

  * [clojure-opennlp](https://github.com/dakrone/clojure-opennlp)
  * [postagga](https://github.com/turbopape/postagga)
  * [beagle](https://github.com/tokenmill/beagle)
  * [lmgrep](https://github.com/dainiusjocas/lucene-grep)

## Parsing

  * [Instaparse](https://github.com/Engelberg/instaparse)
  * [kern](https://github.com/blancas/kern)
  * [duckling](https://github.com/wit-ai/duckling)
  * [buran](https://github.com/alekseysotnikov/buran) - RSS/Atom 提要消费者和生产者
  
## Exceptions and Error Handling
  * [Ex](https://github.com/mpenet/ex)
  * [Perseverance](https://github.com/grammarly/perseverance)
  * [Dire](https://github.com/MichaelDrogalis/dire)

## Rule-based Programming
  * [Clara Rules](https://github.com/cerner/clara-rules)
  * [Arete](https://github.com/yipeeio/arete)

## Editor Plugins

  * [Calva (VSCode)](https://github.com/BetterThanTomorrow/calva)
  * [clojure-lsp (multiple editors)](https://github.com/clojure-lsp/clojure-lsp)
  * [CIDER (Emacs)](https://github.com/clojure-emacs/cider)
  * [smartparens (Emacs)](https://github.com/Fuco1/smartparens)
  * [rainbow-delimiters (Emacs)](https://github.com/Fanael/rainbow-delimiters)
  * [aggressive-indent (Emacs)](https://github.com/Malabarba/aggressive-indent-mode)
  * [Conjure (Neovim)](https://github.com/Olical/conjure)
  * [vim-cljfmt (Vim)](https://github.com/venantius/vim-cljfmt)
  * [vim-eastwood (Vim)](https://github.com/venantius/vim-eastwood)
  * [vim-fireplace (Vim)](https://github.com/tpope/vim-fireplace)
  * [vim-redl (Vim)](https://github.com/dgrnbrg/vim-redl)
  * [vim-leiningen (Vim)](https://github.com/tpope/vim-salve)
  * [rainbow_parentheses.vim (Vim)](https://github.com/junegunn/rainbow_parentheses.vim)
  * [vim-iced (Vim)](https://github.com/liquidz/vim-iced)
  * [Cursive (IntelliJ)](https://cursive-ide.com/)
  * [proto-repl (Atom)](https://atom.io/packages/proto-repl)
  * [Parinfer (multiple editors)](http://shaunlebron.github.io/parinfer/)
  * [Bracket Pair Colorizer (VSCode)](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
  * [clojureVSCode (VSCode)](https://github.com/avli/clojureVSCode)
  * [Notepad++](https://github.com/linpengcheng/ClojureBoxNpp): 修改了 Lisp 的配置文件

## Documentation

*用于（非 LP）代码和项目文档的实用程序和库*

 * [codox](https://github.com/weavejester/codox)

## Literate Programming

  * [marginalia](https://github.com/gdeer81/marginalia)
  * [klipse](https://github.com/viebel/klipse)

## Archives and Compression

  * [swindon (java.util.zip wrapper)](https://github.com/AeroNotix/swindon)

## Miscellaneous

 * [potemkin](https://github.com/ztellman/potemkin) - 在另一个 ns 中重新导出 vars / 像 clojure 地图一样
 * [clj-tuple](https://github.com/ztellman/clj-tuple)
 * [slingshot](https://github.com/scgilardi/slingshot)
 * [virgil](https://github.com/ztellman/virgil)
 * [javastar](https://github.com/tailrecursion/javastar)
 * [riddley](https://github.com/ztellman/riddley)
 * [kezban](https://github.com/ertugrulcetin/kezban)
 * [clj-grpc](https://github.com/otwieracz/clj-grpc)

## Debugging

  * [tools.trace](https://github.com/clojure/tools.trace)
  * [debugger](https://github.com/razum2um/clj-debugger)
  * [debug-repl](https://github.com/GeorgeJahad/debug-repl)
  * [ritz](https://github.com/pallet/ritz)
  * [redl](https://github.com/dgrnbrg/redl)
  * [limit-break](https://github.com/technomancy/limit-break)
  * [spyscope](https://github.com/dgrnbrg/spyscope)
  * [aprint](https://github.com/razum2um/aprint)
  * [packed-printer](https://github.com/cgrand/packed-printer)
  * [pretty](https://github.com/AvisoNovate/pretty)
  * [prone](https://github.com/magnars/prone)
  * [figwheel](https://github.com/bhauman/lein-figwheel)
  * [ultra](https://github.com/venantius/ultra)
  * [mate-clj](https://github.com/AppsFlyer/mate-clj)

## CI

  * [lambdacd](https://github.com/flosell/lambdacd)
  
## Project Management
  
  * [milestones](https://github.com/turbopape/milestones)

## Terminal UI

  * [clojure-lanterna](https://github.com/MultiMUD/clojure-lanterna)
  * [triki](https://github.com/lambdaisland/trikl)
  * [zaffre](https://github.com/aaron-santos/zaffre)
  * [closh](https://github.com/dundalek/closh)
  * [piotr-yuxuan/malli-cli](https://github.com/piotr-yuxuan/malli-cli)
  
## Graphviz

  * [zipper-viz](https://github.com/lambdaisland/zipper-viz)
  * [dorothy](https://github.com/daveray/dorothy)
  * [viz.cljc](https://github.com/jebberjeb/viz.cljc)
  * [fsmviz](https://github.com/jebberjeb/fsmviz)
  * [rhizome](https://github.com/ztellman/rhizome)

## Guides

  * [The Clojure Style Guide](https://github.com/bbatsov/clojure-style-guide)
  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook](https://github.com/clojure-cookbook/clojure-cookbook)
  * [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
  * [Clojure for the Brave and True](http://www.braveclojure.com/)
  * [Clojure from the ground up](https://aphyr.com/tags/Clojure-from-the-ground-up)
  * [Error message catalog](https://github.com/yogthos/clojure-error-message-catalog)
  * [Clojure by Example](https://kimh.github.io/clojure-by-example/)

## Video tutorials

### YouTube

  * [Misophistful's channel](https://www.youtube.com/user/Misophistful/videos): 理解列表理解、线程宏、生成测试、解构、core.match 等概念以及使用 Clojure 介绍 Light Table、Datomic 和游戏开发
  * [Fred Overflow's channel](https://www.youtube.com/channel/UC9m7D4XKPJqTPCLSBym3BCg/search?query=Clojure): Clojure 函数式编程和 TDD 介绍
  * [Clojure Pills screencast](https://www.youtube.com/channel/UCH0CkLvbv6yEyrUnw9qujpQ/videos): Clojure 一次一个函数的介绍
  * [Data persistance with Postgres, Clojure and JDBC](https://www.youtube.com/channel/UCrwwOZ4h2FQhAdTMfjyQfQA/playlists)
  * [Clojure Tutorials by Timothy Baldridge](https://www.youtube.com/channel/UC6yONKYeoE2P3bsahDtsimg/videos)：关于 core.async、传感器、瞬态、逻辑编程和“每日函数”系列的更多高级视频.

## Websites

  * [Clojure](http://clojure.org/)
  * [Clojure Slack](http://clojurians.net/)
  * [clojuredocs](http://clojuredocs.org)
  * [clojure-doc](http://clojure-doc.org/)
  * [The Clojure Toolbox](http://www.clojure-toolbox.com/)
  * [ZEEF/Clojure](https://clojure.zeef.com/vlad.bokov)

## Twitter

  * [oss_clj](https://twitter.com/oss_clj)

## Exercises

  * [rich4clojure](https://github.com/PEZ/rich4clojure)
  * [Clojure Koans](http://clojurekoans.com)
  * [Clojure Katas](http://clojurekatas.org)
  * [exercism.io](http://exercism.io/languages/clojure)
  * [Codewars](https://www.codewars.com/kata/search/clojure)
