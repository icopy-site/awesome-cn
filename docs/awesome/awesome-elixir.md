<div class="github-widget" data-repo="h4cc/awesome-elixir"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Elixir [![Build Status](https://api.travis-ci.org/h4cc/awesome-elixir.svg?branch=master)](https://travis-ci.org/h4cc/awesome-elixir) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
令人惊叹的 Elixir 库、资源和闪亮事物的精选列表，灵感来自 [awesome-php](https://github.com/ziadoz/awesome-php).

如果您认为应该添加一个包，请在相应的问题上添加一个:+1: (`:+1:`) 或创建一个新的.

有 [other sites with curated lists of elixir packages](#other-awesome-lists) 你可以看看.


## Actors
*与演员等合作的图书馆和工具.*
* [alf](https://github.com/antonmi/ALF) - 基于流的应用层框架.
* [bpe](https://github.com/spawnproc/bpe)  - Erlang 中的业务流程引擎.  ([Doc](https://bpe.n2o.dev)).
* [dflow](https://github.com/dalmatinerdb/dflow) - 流水线流处理引擎.
* [ex_lttb](https://github.com/ispirata/ex_lttb) - Elixir 下采样库，保留数据的视觉特征.
* [exactor](https://github.com/sasa1977/exactor) - 帮助在 Elixir 中更轻松地实施演员.
* [exos](https://github.com/awetzel/exos) - 一个端口包装器，它将演员和呼叫转发到一个链接的端口.
* [mon_handler](https://github.com/tattdcodemonkey/mon_handler) - 监控给定 GenEvent 处理程序的最小 GenServer.
* [pool_ring](https://github.com/camshaft/pool_ring) - 基于哈希环创建池.
* [poolboy](https://github.com/devinus/poolboy) - 一个笨拙的 Erlang 工人池工厂.
* [pooler](https://github.com/seth/pooler) - OTP 进程池应用程序.
* [sbroker](https://github.com/fishcakez/sbroker) - 基于逗留时间的活动队列管理库.
* [workex](https://github.com/sasa1977/workex) - EVM 流程中的背压和流量控制.

## Algorithms and Data structures
*算法和数据结构的库和实现.*

* [aja](https://github.com/sabiwara/aja) - 高性能持久向量和有序映射.
* [array](https://github.com/takscape/elixir-array) - Erlang 数组的 Elixir 包装库.
* [aruspex](https://github.com/dkendal/aruspex) - Aruspex 是一个可配置的约束求解器，纯粹用 Elixir 编写.
* [bimap](https://github.com/mkaput/elixir-bimap) - Pure Elixir 的实现 [bidirectional maps](https://en.wikipedia.org/wiki/Bidirectional_map) 和多图.
* [bitmap](https://github.com/hashd/bitmap-elixir) - Pure Elixir 的实现 [bitmaps](https://en.wikipedia.org/wiki/Bitmap).
* [blocking_queue](https://github.com/joekain/BlockingQueue)  - BlockingQueue 是一个实现为 GenServer 的简单队列. 它具有在创建时确定的固定最大长度.
* [bloomex](https://github.com/gmcabrita/bloomex) - Scalable Bloom Filters 的纯 Elixir 实现.
* [clope](https://github.com/ayrat555/clope) - CLOPE 的 Elixir 实现：一种快速有效的事务数据聚类算法.
* [Closure Table](https://github.com/florinpatrascu/closure_table)  - Elixir 的封闭表 - 用于存储和操作复杂层次结构的简单解决方案. 它提供内存和 Ecto 适配器.
* [combination](https://github.com/seantanly/elixir-combination) - Elixir 库，用于从 Enumerable 集合中生成组合和排列.
* [conrex](https://github.com/NAISorg/conrex) - 用于地形或等时图的 CONREC 算法的 Elixir 实现.
* [count_buffer](https://github.com/camshaft/count_buffer) - 缓冲大量计数器并定期刷新.
* [cuckoo](https://github.com/gmcabrita/cuckoo) - 一个纯粹的 Elixir 实现 [Cuckoo Filters](https://www.cs.cmu.edu/%7Edga/papers/cuckoo-conext2014.pdf).
* [cuid](https://github.com/duailibe/cuid) - 用 Elixir 编写的针对水平缩放和顺序查找性能优化的防碰撞 id.
* [data_morph](https://hex.pm/packages/data_morph) - 从数据创建 Elixir 结构.
* [dataframe](https://github.com/JordiPolo/dataframe) - 提供类似于 Python 的 Pandas 或 R 的 data.frame() 功能的包.
* [datastructures](https://github.com/meh/elixir-datastructures) - 用于处理数据结构的协议、实现和包装器的集合.
* [def_memo](https://github.com/os6sense/DefMemo) - 使用 genserver 后备存储的 elixir 的记忆宏 (defmemo).
* [dlist](https://github.com/stocks29/dlist) - Elixir 中的双端队列实现.
* [eastar](https://github.com/herenowcoder/eastar) - 纯 Elixir 中的 A* 图寻路.
* [ecto_materialized_path](https://github.com/asiniy/ecto_materialized_path) - ecto 模型的树结构、层次结构和祖先.
* [ecto_state_machine](https://github.com/asiniy/ecto_state_machine) - 在 Elixir 上实现并为 Ecto 采用的有限状态机模式.
* [elistrix](https://github.com/tobz/elistrix) - 延迟/容错库，可帮助您将应用程序与缓慢或失败服务的不确定世界隔离开来.
* [emel](https://github.com/mrdimosthenis/emel) - 一个用 elixir 编写的简单而实用的机器学习库.
* [erlang-algorithms](https://github.com/aggelgian/erlang-algorithms) - 流行数据结构和算法的实现.
* [exconstructor](https://github.com/appcues/exconstructor) - 一个 Elixir 库，用于生成轻松处理外部数据的结构构造函数.
* [exfsm](https://github.com/awetzel/exfsm) - 用于定义静态 FSM 的简单 elixir 库.
* [exkad](https://github.com/rozap/exkad) - 一个 [kademlia](https://en.wikipedia.org/wiki/Kademlia) Elixir 中的实现.
* [exmatrix](https://github.com/a115/exmatrix) - ExMatrix 是一个用于处理矩阵的小型库，最初是为并行测试矩阵乘法而开发的.
* [exor_filter](https://github.com/mpope9/exor_filter)  - 用于 xor_filters 的 Nif.  “比 Bloom 和 Cuckoo 过滤器更快、更小”.
* [ezcryptex](https://github.com/stocks29/ezcryptex) - Cryptex 顶部的薄层.
* [flow](https://github.com/dashbitco/flow) - GenStage 之上的计算并行流.
* [fnv](https://github.com/asaaki/fnv.ex) - Fowler–Noll–Vo 哈希函数的纯 Elixir 实现.
* [fsm](https://github.com/sasa1977/fsm) - 有限状态机作为功能数据结构.
* [fuse](https://github.com/jlouis/fuse) - 这个应用程序为 Erlang 实现了一个所谓的断路器.
* [gen_fsm](https://github.com/pavlos/gen_fsm) - 通用有限状态机 - 围绕 OTP 的 gen_fsm 的 Elixir 包装器.
* [graphex](https://github.com/stocks29/graphex) - 在 Elixir 中编写和执行任务图的库. [Docs](https://hexdocs.pm/graphex)
* [graphmath](https://github.com/crertel/graphmath) - 用于执行 2D 和 3D 数学的 Elixir 库.
* [hash_ring_ex](https://github.com/reset/hash-ring-ex) - Elixir 的一致哈希环实现.
* [hypex](https://github.com/whitfin/hypex) - HyperLogLog 的快速 Elixir 实现.
* [indifferent](https://github.com/vic/indifferent) - 具有自定义键转换的 Elixir 地图/列表/元组的无差别访问.
* [isaac](https://github.com/arianvp/elixir-isaac) - Isaac 是 ISAAC 的长生不老药模块：一个快速的密码随机数生成器.
* [jumper](https://github.com/whitfin/jumper) - 在 Elixir 中跳转一致的哈希实现（没有 NIF）.
* [key2value](https://github.com/okeuday/key2value) - Erlang 2-way Set Associative Map.
* [lfsr](https://github.com/pma/lfsr) - 二进制伽罗瓦线性反馈移位寄存器的 Elixir 实现.
* [loom](https://github.com/asonge/loom) - 支持 δ-CRDT 的 CRDT 库.
* [luhn](https://github.com/ma2gedev/luhn_ex) - Elixir 中的 Luhn 算法.
* [lz4](https://github.com/szktty/erlang-lz4) - Erlang 的 LZ4 绑定用于快速数据压缩.
* [machinery](https://github.com/joaomdmoura/machinery) - 一般结构的状态机库，它与 Phoenix 开箱即用地集成.
* [mason](https://github.com/spacepilots/mason)  - 强制映射到结构中. 这很有帮助，例如，当您连接 REST API 并希望从响应中创建结构时.
* [matrex](https://github.com/versilov/matrex) - 用于 Elixir/Erlang 的超快矩阵库，使用 CBLAS 实现 C.
* [merkle_tree](https://github.com/yosriady/merkle_tree) - Elixir 中的 Merkle 哈希树实现.
* [minmaxlist](https://github.com/seantanly/elixir-minmaxlist) - Elixir 库扩展了 `Enum.min_by/2`、`Enum.max_by/2` 和 `Enum.min_max_by/2` 以返回结果列表，而不仅仅是一个.
* [mmath](https://github.com/dalmatinerdb/mmath) - 用于对二进制中的数字“数组”执行数学运算的库.
* [monad](https://github.com/rmies/monad) - Haskell 启发了 Elixir 时尚语法中的 monad.
* [monadex](https://github.com/rob-brown/MonadEx) - 使用 monad 升级您的 Elixir 管道.
* [murmur](https://github.com/gmcabrita/murmur) - 非加密哈希 Murmur3 的纯 Elixir 实现.
* [nary_tree](https://github.com/medhiwidjaja/nary_tree) - 通用 n 元树数据结构的 Elixir 实现.
* [natural_sort](https://github.com/DanCouper/natural_sort) - 字符串列表的 Elixir 自然排序实现.
* [navigation_tree](https://github.com/gutschilla/elixir-navigation-tree) - 带有帮助器的导航树表示，可从中生成 HTML.
* [parallel_stream](https://github.com/beatrichartz/parallel_stream) - Elixir 的并行流实现.
* [paratize](https://github.com/seantanly/elixir-paratize) - Elixir 库提供了一些方便的并行处理（执行）设施，支持配置工人数量和超时.
* [parex](https://github.com/StevenJL/parex) - Parallel Execute (Parex) 是一个 Elixir 模块，用于并行执行多个（慢速）进程.
* [qex](https://github.com/princemaple/elixir-queue) - 包装 `:queue`，改进 API 和 `Inspect`、`Collectable` 和 `Enumerable` 协议实现.
* [ratio](https://github.com/Qqwy/elixir-rational)  - 添加有理数并允许它们用于常见的算术运算. 还支持浮点数和有理数之间的转换.
* [red_black_tree](https://github.com/SenecaSystems/red_black_tree) - Elixir 中的红黑树实现.
* [remodel](https://github.com/stavro/remodel) - 一个用于转换地图结构的 Elixir 演示器包.
* [rendezvous](https://github.com/timdeputter/Rendezvous) - 在 Elixir 中实现 Rendezvous 或最高随机权重 (HRW) 哈希算法.
* [rock](https://github.com/ayrat555/rock) - ROCK 的 Elixir 实现：分类属性的稳健聚类算法.
* [sfmt](https://github.com/jj1bdx/sfmt-erlang/) - 用于 Erlang 的面向 SIMD 的快速 Mersenne Twister (SFMT).
* [simhash](https://github.com/UniversalAvenue/simhash-ex) - 使用 Siphash 和 N-gram 实现 Simhash.
* [sleeplocks](https://github.com/whitfin/sleeplocks) - 适用于 Elixir/Erlang 的 BEAM 友好自旋锁.
* [sorted_set](https://github.com/SenecaSystems/sorted_set) - 长生不老药的分类套装.
* [spacesaving](https://github.com/rozap/spacesaving) - 使用“节省空间”算法的流计数不同元素估计.
* [structurez](https://github.com/hamiltop/structurez) - Elixir 中数据结构的游乐场.
* [supermemo](https://github.com/edubkendo/supermemo) - Elixir 的实现 [Supermemo 2 algorithm](https://www.supermemo.com/english/ol/sm2.htm).
* [tfidf](https://github.com/OCannings/tf-idf) - 词频-逆文档频率的 Elixir 实现.
* [the_fuzz](https://github.com/smashedtoatoms/the_fuzz) - 模糊字符串匹配算法实现.
* [tinymt](https://github.com/jj1bdx/tinymt-erlang/) - 用于 Erlang 的 Tiny Mersenne Twister (TinyMT).
* [trie](https://github.com/okeuday/trie) - Erlang Trie 实现.
* [witchcraft](https://github.com/expede/witchcraft) - Elixir 的常见代数结构和函数.
* [zipper_tree](https://github.com/Dkendal/zipper_tree) - 带有 Elixir 拉链的可变参数树.

## Applications
*独立应用程序.*
* [Caddishouse](https://github.com/caddishouse/reader) - 基于 Web 的文档阅读器，可使用 Phoenix/LiveView 连接到您的云存储帐户.
* [CaptainFact](https://github.com/CaptainFact/captain-fact-api)  - 一个协作的实时视频事实核查平台.  ([Docs](https://captainfact.io/)).
* [chat](https://github.com/synrc/chat) - 基于 N2O 的小型文本聊天示例.
* [Consolex](https://github.com/sivsushruth/consolex) - Consolex 是一个工具，可让您将基于 Web 的控制台附加到任何混音项目.
* [dragonfly_server](https://github.com/cloud8421/dragonfly-server) - 提供蜻蜓图像的 Elixir 应用程序.
* [exchat](https://github.com/tony612/exchat) - 由 Elixir、Phoenix 和 React (redux) 开发的类似 Slack 的应用程序.
* [Exon](https://github.com/tchoutri/Exon)  - 在 Elixir 中开发的“混乱管理器”，并提供一个简单的 API 来管理和记录你的东西.  ([Docs](https://hexdocs.pm/exon/readme.html)).
* [ExShop](https://github.com/authentic-pixels/ex-shop) - 使用 Phoenix 框架创建的数字商品商店和博客.
* [Hydra](https://github.com/doomspork/hydra) - 多头野兽：API 网关、请求缓存和数据转换.
* [Igthorn](https://github.com/cinderella-man/igthorn) - 带有管理面板的加密货币交易平台/交易机器人.
* [majremind](https://bitbucket.org/Anwen/majremind) - 更新服务器的自我维护数据库，告诉您需要更新哪一个.
* [medex](https://github.com/xerions/medex) - 体检 - 申请注册健康检查回调并通过 HTTP 表示其状态.
* [medusa_server](https://github.com/IcaliaLabs/medusa_server)  - 一个用 Elixir 编写的简单牛仔 Web 服务器，用于堆叠图像.  ([Docs](https://hexdocs.pm/medusa/0.2.0/api-reference.html)).
* [Nvjorn](https://github.com/tchoutri/Nvjorn) - A multi-protocol network services monitor written in Elixir using Poolboy.
* [Phoenix Battleship](https://github.com/bigardone/phoenix-battleship) - 使用 Elixir、Phoenix 框架、React 和 Redux 构建的 Good Old 游戏.
* [Phoenix Toggl](https://github.com/bigardone/phoenix-toggl) - 在 Elixir、Phoenix Framework、React 和 Redux 中完成的 Toggl 致敬.
* [Phoenix Trello](https://github.com/bigardone/phoenix-trello) - 在 Elixir、Phoenix Framework、React 和 Redux 中完成的 Trello 致敬.
* [poxa](https://github.com/edgurgel/poxa) - 开放的 Pusher 实现，与 Pusher 库兼容.
* [Queerlink](https://github.com/Queertoo/Queerlink) - 用 Elixir 编写的简单而高效的 URL 缩短服务.
* [RemoteRetro](https://github.com/stride-nyc/remote_retro) - 用于进行敏捷回顾的实时应用程序 [remoteretro.org](https://remoteretro.org) 用 Elixir/Phoenix/React 编写.
* [Sprint Poker](https://github.com/elpassion/sprint-poker) - 敏捷团队的在线评估工具，使用 Elixir Lang、Phoenix 框架和 React 编写.
* [Startup Job](https://github.com/tsurupin/job_search) - 一个搜索从 Elixir/Phoenix 和 React/Redux 编写的网站上抓取的创业工作的伞式项目.
* [Tai](https://github.com/fremantle-capital/tai) - 可组合的实时加密货币市场数据和交易执行工具包.
* [tty2048](https://github.com/lexmag/tty2048) - 使用 Elixir 编写的基于终端的 2048 游戏.
* [uai_shot](https://github.com/sergioaugrod/uai_shot) - 使用 Elixir、Phoenix Framework 和 Phaser 构建的多人船舶游戏.
* [workbench](https://github.com/fremantle-industries/workbench) - 从构思到执行 - 跨全球分布式集群管理您的交易操作.

## Artificial Intelligence
*当你的代码变得比你聪明时.*

* [Exnn](https://github.com/zampino/exnn)  - Evolutive Neural Networks framework à la G.Sher 用 Elixir 编写.  ([Docs](http://zampino.github.io/exnn/)).
* [m2cgen](https://github.com/BayesWitnesses/m2cgen) - 一个 CLI 工具，用于将经过训练的经典 ML 模型转换为具有零依赖性的原生 Elixir 代码.
* [Neat-Ex](https://gitlab.com/onnoowl/Neat-Ex)  - NEAT 算法的 Elixir 实现.  ([Docs](https://hexdocs.pm/neat_ex/Neat.html)).
* [Runhyve](https://runhyve.app)  - Runhyve 是 FreeBSD 上 bhyve 的完整虚拟机管理器. 它是用 Elixir 编写的，使用 Phoenix 框架.
* [simple_bayes](https://github.com/fredwu/simple_bayes) - A Simple Bayes / Naive Bayes implementation in Elixir.
* [Synapses](https://mrdimosthenis.github.io/Synapses/?elixir) - 用于神经网络的轻量级库.

## Audio and Sounds
*使用声音和音调的库.*

* [erlaudio](https://github.com/asonge/erlaudio) - Erlang PortAudio 绑定.
* [ex_alsa](https://github.com/dulltools/ex_alsa) - Elixir ALSA 绑定
* [ex_jack](https://github.com/dulltools/ex_jack) - Elixir JACK 绑定
* [firmata](https://github.com/entone/firmata) - 这个包实现了 Firmata 协议.
* [synthex](https://github.com/bitgamma/synthex) - 一个信号合成库.

## Authentication
*用于实现身份验证方案的库.*

* [aeacus](https://github.com/zmoshansky/aeacus) - 一个简单的可配置身份/密码认证模块（兼容 Ecto/Phoenix）.
* [apache_passwd_md5](https://github.com/kevinmontuori/Apache.PasswdMD5) - Apache/APR 风格的密码散列.
* [aws_auth](https://github.com/bryanjos/aws_auth) - 适用于 Elixir 的 AWS 签名版本 4 签名库.
* [basic_auth](https://github.com/CultivateHQ/basic_auth) - Elixir 插件可轻松将 HTTP 基本身份验证添加到应用程序.
* [coherence](https://github.com/smpallen99/coherence)  - Coherence 是 Phoenix 的功能齐全、可配置的身份验证系统.  ([Docs](https://hexdocs.pm/coherence/Coherence.html)).
* [doorman](https://github.com/BlakeWilliams/doorman) - 使 Elixir 身份验证简单灵活的工具.
* [elixir_auth_google](https://github.com/dwyl/elixir-auth-google) - 将 Google OAuth 身份验证（“使用 Google 登录”）添加到您的 Elixir/Phoenix 应用程序的最简单方法.
* [github_oauth](https://github.com/lidashuang/github_oauth) - 一个简单的 github oauth 库.
* [goth](https://github.com/peburrows/goth) - 通过 Google Cloud API 用于服务器到服务器应用程序的 OAuth 2.0 库.
* [guardian](https://github.com/ueberauth/guardian)  - 与 Elixir 应用程序一起使用的身份验证框架.  ([Docs](https://hexdocs.pm/guardian/Guardian.html)).
* [guardian_db](https://github.com/ueberauth/guardian_db)  - Guardian 的扩展，可跟踪应用程序数据库中的令牌以防止播放.  ([Docs](https://hexdocs.pm/guardian_db/readme.html)).
* [guardian_redis](https://github.com/alexfilatov/guardian_redis)  - Guardian DB 的 Redis 存储库.  ([Docs](https://hexdocs.pm/guardian_redis/readme.html)).
* [htpasswd](https://github.com/kevinmontuori/Apache.htpasswd) - Elixir 中的 Apache htpasswd 文件读取器/写入器.
* [mojoauth](https://github.com/mojolingo/mojo-auth.ex) - Elixir 中的 MojoAuth 实现.
* [oauth2](https://github.com/scrogson/oauth2) - Elixir 的 OAuth 2.0 客户端库.
* [oauth2_facebook](https://github.com/chrislaskey/oauth2_facebook) - Elixir 的 Facebook OAuth2 提供程序.
* [oauth2_github](https://github.com/chrislaskey/oauth2_github) - Elixir 的 GitHub OAuth2 提供程序.
* [oauth2cli](https://github.com/mgamini/oauth2cli-elixir) - 为 Elixir 编写的简单 OAuth2 客户端.
* [oauth2ex](https://github.com/parroty/oauth2ex) - Elixir 的另一个 OAuth 2.0 客户端库.
* [oauther](https://github.com/lexmag/oauther) - Elixir 的 OAuth 1.0 实现.
* [passwordless_auth](https://github.com/madebymany/passwordless_auth) - Elixir 的简单无密码登录或 2 因素/多因素身份验证.
* [phauxth](https://github.com/riverrun/phauxth) - Phoenix 1.3 和其他基于插件的应用程序的身份验证库.
* [phoenix_client_ssl](https://github.com/jshmrtn/phoenix-client-ssl) - Phoenix 和其他基于插件的应用程序的客户端 SSL 身份验证插件.
* [phx_gen_auth](https://github.com/aaronrenner/phx_gen_auth) - Phoenix 1.5 应用程序的身份验证系统生成器.
* [pow](https://github.com/danschultzer/pow) - 强大、模块化和可扩展的用户认证系统（[Website](https://powauth.com) - [Doc](https://hex.pm/packages/pow)).
* [samly](https://github.com/handnot2/samly) - SAML SP SSO 变得简单（[Doc](https://hexdocs.pm/samly/readme.html)).
* [sesamex](https://github.com/khusnetdinov/sesamex) - 5 分钟内又一个简单灵活的身份验证解决方案！
* [sigaws](https://github.com/handnot2/sigaws) - AWS Signature V4 签名和验证库（[Doc](https://hexdocs.pm/sigaws/Sigaws.html)).
* [ueberauth](https://github.com/ueberauth/ueberauth) - 基于插件的 Web 应用程序的 Elixir 身份验证系统.
* [ueberauth_auth0](https://hex.pm/packages/ueberauth_auth0) - 使用 Auth0 对用户进行身份验证的 Ueberauth 策略.
* [ueberauth_cas](https://github.com/marceldegraaf/ueberauth_cas) - Überauth 的中央身份验证服务策略.
* [ueberauth_facebook](https://github.com/ueberauth/ueberauth_Facebook) - Überauth 的 Facebook OAuth2 策略.
* [ueberauth_foursquare](https://github.com/borodiychuk/ueberauth_foursquare) - 用于 Überauth 的 Foursquare OAuth2 策略.
* [ueberauth_github](https://github.com/ueberauth/ueberauth_github) - Überauth 的 GitHub 策略.
* [ueberauth_google](https://github.com/ueberauth/ueberauth_google) - Überauth 的 Google 策略.
* [ueberauth_identity](https://github.com/ueberauth/ueberauth_identity) - Überauth 的简单用户名/密码策略.
* [ueberauth_line](https://github.com/alexfilatov/ueberauth_line) - Überauth 的 LINE 策略.
* [ueberauth_microsoft](https://github.com/swelham/ueberauth_microsoft) - Microsoft 为 Überauth 制定的策略.
* [ueberauth_slack](https://github.com/ueberauth/ueberauth_slack) - Überauth 的 Slack 策略.
* [ueberauth_twitter](https://github.com/ueberauth/ueberauth_twitter) - Überauth 的 Twitter 策略.
* [ueberauth_vk](https://github.com/sobolevn/ueberauth_vk) - [vk.com](https://vk.com) Überauth 的策略.
* [ueberauth_weibo](https://github.com/he9qi/ueberauth_weibo) - [Weibo](https://weibo.com) Überauth 的 OAuth2 策略.
* [zachaeus](https://github.com/railsmechanic/zachaeus) - 基于非对称加密的易于使用的许可系统.

## Authorization
*用于实现授权处理的库.*

* [authorize](https://github.com/jfrolich/authorize) - 基于规则的授权，用于高级授权规则.
* [bodyguard](https://github.com/schrockwell/bodyguard) - Phoenix 应用程序的灵活授权库.
* [canada](https://github.com/jarednorman/canada) - 一个简单的授权库，使用声明性权限规则提供友好的界面.
* [canary](https://github.com/cpjk/canary)  - Elixir 应用程序的授权库，用于限制允许当前用户访问的资源.  ([Docs](https://hexdocs.pm/canary/api-reference.html)).
* [speakeasy](https://github.com/coryodaniel/speakeasy) - 基于中间件的 Absinthe GraphQL 身份验证和授权，由 Bodyguard 提供支持.
* [terminator](https://github.com/MilosMosovsky/terminator)  - 基于数据库的授权 (ACL)，具有用于需要所需权限的自定义 DSL 规则.  ([Docs](https://hexdocs.pm/terminator/readme.html)).

## Behaviours and Interfaces
*定义事物的行为方式，例如来自 OOP-World 的接口*

* [connection](https://github.com/fishcakez/connection)  - 连接过程的连接行为.  API 是 GenServer API 的超集.
* [gen_state_machine](https://github.com/antipax/gen_state_machine) - gen_state 的 Elixir 包装器.
* [stockastic](https://github.com/shanewilton/stockastic) - Stockfighter API 的简单 Elixir 包装器.

## Benchmarking
*运行代码以查看需要多长时间，哪个更快和/或是否进行了改进.*

* [beamchmark](https://github.com/membraneframework/beamchmark) - 用于测量 EVM 性能的工具.
* [benchee](https://github.com/PragTob/benchee) - Elixir 中简单且可扩展的基准测试！
* [benchfella](https://github.com/alco/benchfella) - Elixir 的基准测试工具.
* [bmark](https://github.com/joekain/bmark) - A benchmarking tool for Elixir.

## Bittorrent
*Sharing is caring with Elixir*

* [bento](https://github.com/folz/bento) - 一个令人难以置信的快速、正确、纯 Elixir Bencoding 库.
* [tracker_request](https://github.com/alehander42/tracker_request) - 处理 bittorrent 跟踪器请求和响应.
* [wire](https://github.com/alehander42/wire) - 使用 Elixir 对 bittorrent 对等线协议消息进行编码和解码.

## BSON
*使用 BSON 的库和实现.*

* [BSONMap](https://github.com/Nebo15/bsoneach) - Elixir 包，将函数应用于 BSON 文件中的每个文档，并且内存消耗低.
* [cyanide](https://github.com/ispirata/cyanide) - Elixir BSON 编码/解码库.

## Build Tools
*项目构建和自动化工具.*

* [active](https://github.com/synrc/active) - 重新编译和重新加载文件系统更改.
* [coffee_rotor](https://github.com/HashNuke/coffee_rotor) - 用于编译 CoffeeScript 文件的转子插件.
* [dismake](https://github.com/jarednorman/dismake) - 混合编译器运行 make.
* [etude](https://github.com/exstruct/etude) - Erlang/Elixir 的并行计算协调编译器.
* [ExMake](https://github.com/lycus/exmake) - 一个现代的、可编写脚本的、基于依赖的构建工具，松散地基于 Make 原则.
* [Exscript](https://github.com/liveforeverx/exscript) - Elixir 脚本库.
* [mad](https://github.com/synrc/mad) - 小而快的钢筋更换.
* [pc](https://github.com/blt/port_compiler) - rebar3 端口编译器.
* [reaxt](https://github.com/awetzel/reaxt) - 将模板反应到您的 Elixir 应用程序中以进行服务器渲染.
* [rebar3_abnfc_plugin](https://github.com/surik/rebar3_abnfc_plugin) - Rebar3 abnfc 编译器.
* [rebar3_asn1_compiler](https://github.com/pyykkis/rebar3_asn1_compiler) - 使用 Rebar3 编译 ASN.1 模块的插件.
* [rebar3_auto](https://github.com/vans163/rebar3_auto) - Rebar3 插件可在文件更改时自动编译和重新加载.
* [rebar3_diameter_compiler](https://github.com/carlosedp/rebar3_diameter_compiler) - 在 rebar3 项目中编译直径 .dia 文件.
* [rebar3_eqc](https://github.com/kellymclaughlin/rebar3-eqc-plugin) - 一个 rebar3 插件，用于启用 Erlang QuickCheck 属性的执行.
* [rebar3_exunit](https://github.com/processone/rebar3_exunit) - 从 rebar3 构建工具运行 Elixir ExUnit 测试的插件.
* [rebar3_idl_compiler](https://github.com/sebastiw/rebar3_idl_compiler) - 这是一个使用 Rebar3 编译 Erlang IDL 文件的插件.
* [rebar3_live](https://github.com/pvmart/rebar3_live) - Rebar3 实时插件.
* [rebar3_neotoma_plugin](https://github.com/zamotivator/rebar3_neotoma_plugin) - Rebar3 neotoma（解析器表达式语法）编译器.
* [rebar3_protobuffs](https://github.com/benoitc/rebar3_protobuffs) - rebar3 protobuffs 提供者使用来自 Basho 的 protobuffs.
* [rebar3_run](https://github.com/tsloughter/rebar3_run) - 使用一个简单的命令运行发布.
* [rebar3_yang_plugin](https://github.com/surik/rebar3_yang_plugin) - Rebar3 编译器.
* [reltool_util](https://github.com/okeuday/reltool_util) - Erlang reltool 实用程序功能应用程序.
* [relx](https://github.com/erlware/relx) - Erlang 的发布汇编器.
* [remix](https://github.com/AgilionApps/remix) - 文件更改时自动重新编译混合代码.
* [rotor](https://github.com/HashNuke/rotor) - Elixir 的超级简单构建系统.
* [sass_elixir](https://github.com/zamith/sass_elixir) - Elixir 项目的 sass 插件.

## Caching
*用于缓存数据的库.*

* [cachex](https://github.com/whitfin/cachex) - 一个强大的 Elixir 缓存库，具有广泛的功能集.
* [con_cache](https://github.com/sasa1977/con_cache) - ConCache 是一个基于 ETS 的键/值存储.
* [elixir_locker](https://github.com/tsharju/elixir_locker) - Locker 是 locker Erlang 库的 Elixir 包装器，它提供了一些有用的库，应该使 locker 的使用更容易一些.
* [gen_spoxy](https://github.com/SpotIM/gen_spoxy) - 缓存变得有趣.
* [jc](https://github.com/jr0senblum/jc) - 内存中的分布式缓存，具有发布/订阅、JSON 查询和一致性支持.
* [locker](https://github.com/wooga/locker) - 短期密钥的原子分布式“检查和设置”.
* [lru_cache](https://github.com/arago/lru_cache) - 简单的 LRU 缓存，用 ets 实现.
* [memoize](https://github.com/melpon/memoize) - 一个易于缓存功能的记忆宏.
* [nebulex](https://github.com/cabol/nebulex) - Elixir 的快速、灵活和可扩展的分布式和本地缓存库.
* [stash](https://github.com/whitfin/stash) - 一个简单、快速和用户友好的键/值存储.

## Chatting
*通过 IRC、Slack、HipChat 和其他使用 Elixir 的系统聊天.*

* [alice](https://github.com/alice-bot/alice) - Elixir 的 Slack 机器人框架.
* [chatty](https://github.com/alco/chatty) - 一个对编写机器人最有用的基本 IRC 客户端.
* [cog](https://github.com/operable/cog) - Cog is an open chatops platform that gives you a secure, collaborative command line right in your chat window.
* [ExGram](https://github.com/rockneurotiko/ex_gram)  - 构建 Telegram Bots 的库，您可以使用低级方法和模型或使用包含的真正自以为是的框架.  ([Docs](https://hexdocs.pm/ex_gram/readme.html)).
* [ExIrc](https://github.com/bitwalker/exirc) - Elixir 项目的 IRC 客户端适配器.
* [ExMustang](https://github.com/techgaun/ex_mustang) - 一个简单的、毫无头绪的 slackbot 和响应者集合.
* [Guri](https://github.com/elvio/guri) - Automate tasks using chat messages.
* [hedwig](https://github.com/hedwig-im/hedwig) - Elixir 的 XMPP 客户端/机器人框架.([Docs](https://hexdocs.pm/hedwig/readme.html)).
* [hipchat_elixir](https://github.com/ymtszw/hipchat_elixir) - 基于 httpc 的 Elixir 的 HipChat 客户端库.
* [kaguya](https://github.com/Luminarys/Kaguya) - 一个小巧、强大、模块化的 IRC 机器人.
* [slacker](https://github.com/koudelka/slacker) - 用于 Slack 聊天服务的机器人库.
* [yocingo](https://github.com/Yawolf/yocingo) - 创建您自己的电报机器人.

## Cloud Infrastructure and Management
*适用于您自己的云服务的应用程序、工具和库.*

* [aws](https://github.com/aws-beam/aws-elixir) - Elixir 的 AWS 客户端.
* [Bonny](https://github.com/coryodaniel/bonny) - Kubernetes 运营商开发框架.
* [Cloudi](http://cloudi.org/) - CloudI 用于需要软实时事务的后端服务器处理任务.
* [discovery](https://github.com/undeadlabs/discovery) - 使用 Consul 自动发现服务的 OTP 应用程序.
* [erlcloud](https://github.com/erlcloud/erlcloud)  - Erlang 的云计算库（Amazon EC2、S3、SQS、SimpleDB、Mechanical Turk、ELB）.  ([Docs](https://hexdocs.pm/erlcloud/)).
* [ex_aws](https://github.com/CargoSense/ex_aws) - AWS 客户端，支持 Dynamo、Kinesis、Lambda、SQS 和 S3.
* [ex_riak_cs](https://github.com/ayrat555/ex_riak_cs) - Riak CS API 客户端.
* [fleet_api](https://github.com/jordan0day/fleet-api)  - Fleet (CoreOS) API 的简单包装器. 可以与 etcd 令牌或通过直接节点 URL 一起使用.
* [Gandi](https://github.com/Ahamtech/elixir-Gandi) - 用于 Leaseweb 基础设施的 Gandi Wrapper.
* [IElixir](https://github.com/pprzetacznik/IElixir) - 用于 Elixir 编程语言的 Jupyter 内核.
* [k8s](https://github.com/coryodaniel/k8s) - 具有 CRD 支持、多集群支持、可插入身份验证和可配置中间件的 Kubernetes Elixir 客户端.
* [Kazan](https://github.com/obmarg/kazan) - Elixir 的 Kubernetes 客户端，根据 k8s 开放 API 规范生成.
* [Kubex](https://github.com/ingerslevio/kubex) - Kubernetes 客户端和 Elixir 集成，用纯 Elixir 编写.
* [Leaseweb](https://github.com/Ahamtech/elixir-leaseweb) - 用于 Leaseweb 基础设施的 Elixir Wrapper.
* [libcluster](https://github.com/bitwalker/libcluster) - Elixir 应用程序的自动集群形成/修复.（[Docs](https://hexdocs.pm/libcluster/readme.html)).
* [nodefinder](https://github.com/okeuday/nodefinder) - Erlang 中自动节点发现的策略.
* [nomad](https://github.com/sashaafm/nomad)  - 创建云便携 Elixir 和 Phoenix 应用程序. 一次编写，到处使用！
* [sidejob](https://github.com/basho/sidejob) - Erlang 的并行工作者和容量限制库.
* [sidetask](https://github.com/PSPDFKit-labs/sidetask) - SideTask 是 Task.Supervisor 的替代品，它使用 Basho 的具有并行性和容量限制的 sidejob 库.
* [skycluster](https://github.com/Nebo15/skycluster)  - Elixir/Erlang 应用程序的自动 Erlang 集群形成、消息传递和管理. 与 Kubernetes 集成.

## Code Analysis
*用于代码库分析、解析和操作的库和工具.*

* [belvedere](https://github.com/nirvana/belvedere) - CircleCI 与 Elixir 集成的示例.
* [coverex](https://github.com/alfert/coverex) - Elixir 的覆盖率报告.
* [credo](https://github.com/rrrene/credo)  - 一个静态代码分析工具，专注于代码一致性和 Elixir 教学.  ([Docs](https://hexdocs.pm/credo/Credo.html)).
* [DepViz](https://depviz.jasonaxelson.com/)  - 帮助开发人员了解项目中 Elixir 重新编译的可视化工具.  ([Code](https://github.com/axelson/dep_viz/)).
* [dialyxir](https://github.com/jeremyjh/dialyxir) - 混合任务以简化 Elixir 项目中 Dialyzer 的使用.（[Docs](https://hexdocs.pm/dialyzex/Mix.Tasks.Dialyzer.html)).
* [dogma](https://github.com/lpil/dogma) - Elixir 的代码风格 linter，由羞耻感驱动.（[Docs](https://hexdocs.pm/dogma/api-reference.html)).
* [excellent_migrations](https://github.com/Artur-Sulej/excellent_migrations) - 检测数据库迁移中的潜在危险操作.
* [excoveralls](https://github.com/parroty/excoveralls) - 具有 Coveralls.io 集成的 Elixir 覆盖率报告工具.
* [exprof](https://github.com/parroty/exprof) - 一个简单的 Elixir 代码分析器，使用 eprof.
* [int_set](https://github.com/Cantido/int_set) - 用于正整​​数的时间和内存高效的无序数据结构.

## Command Line Applications
*任何有助于构建 CLI 应用程序的东西.*

* [anubis](https://github.com/bennyhallett/anubis) - Elixir 的命令行应用程序框架.
* [ex_cli](https://github.com/tuvistavie/ex_cli) - Elixir 的用户友好 CLI 应用程序.
* [ex_prompt](https://github.com/behind-design/ex_prompt) - 帮助程序包尽可能简单地为您的命令行应用程序添加交互性.
* [firex](https://github.com/msoedov/firex) - Firex 是一个用于从 elixir 模块自动生成命令行界面 (CLI) 的库.
* [getopt](https://github.com/jcomellas/getopt) - Erlang 的命令行选项解析器.
* [loki](https://github.com/khusnetdinov/loki) - 用于创建交互式命令行应用程序的库.
* [optimus](https://github.com/savonarola/optimus) - 受启发的 Elixir 命令行选项解析器 [clap.rs](https://clap.rs/).
* [owl](https://github.com/fuelen/owl) - Owl 是一个用于在 Elixir 中编写命令行用户界面的工具包.
* [phoenix-cli](https://phoenix-cli.github.io/) - Phoenix 框架的命令行界面，如 Rails 命令.
* [progress_bar](https://github.com/henrik/progress_bar) - 命令行进度条和微调器.
* [ratatouille](https://github.com/ndreynolds/ratatouille) - Elixir 的 TUI（终端 UI）套件.
* [scribe](https://github.com/codedge-llc/scribe)  - Elixir 结构和映射的漂亮打印表. 灵感来自hirb.
* [table_rex](https://github.com/djm/table_rex) - 生成可配置的 ASCII 样式表以供显示.
* [tabula](https://github.com/aerosol/tabula) - 在 ascii 表 (GitHub Markdown/OrgMode) 中漂亮的 Ecto 查询结果/地图打印列表.

## Configuration
*使用配置的库和工具*

* [confex](https://github.com/Nebo15/confex) - 帮助模块，它提供了一种在运行时读取环境配置的好方法.
* [configparser_ex](https://github.com/easco/configparser_ex) - 一个简单的 Elixir 解析器，用于 Python 的 configparser 库处理的相同类型的文件.
* [conform](https://github.com/bitwalker/conform) - Elixir 应用程序的简单发布配置.
* [dotenv](https://github.com/avdi/dotenv_elixir) - dotenv 到 Elixir 的端口.
* [enux](https://github.com/massivefermion/enux) - 实用程序包，用于在运行时从 env、json 和 jsonc 文件加载、验证和记录应用程序的配置变量，并将它们注入到您的环境中.
* [ex_conf](https://github.com/phoenixframework/ex_conf) - 简单的 Elixir 配置管理.
* [figaro](https://github.com/trestrantham/ex_figaro) - 简单的 Elixir 项目配置.
* [figaro_elixir](https://github.com/KamilLelonek/figaro-elixir) - Elixir 的环境变量管理器.
* [hush](https://github.com/gordalina/hush) - 在运行时读取和注入配置，并在支持多个提供程序的发布模式下.
* [hush_aws_secrets_manager](https://github.com/gordalina/hush_aws_secrets_manager) - 用于安静的 AWS Secrets Manager 提供商.
* [hush_gcp_secret_manager](https://github.com/gordalina/hush_gcp_secret_manager) - Google Secret Manager 提供者用于安静.
* [skogsra](https://github.com/gmtprime/skogsra) - 轻松管理操作系统环境变量和应用程序配置选项的库
* [sweetconfig](https://github.com/d0rc/sweetconfig) - 从您的应用程序的任何位置读取 YAML 配置文件.
* [weave](https://gitlab.com/gt8/open-source/elixir/weave) - 适用于 Kubernetes 和 Docker Swarm 的 JIT 配置加载器.

## Cryptography
*加密和解密数据*

* [aescmac](https://github.com/kleinernik/elixir-aes-cmac) - AES CMAC（[RFC 4493](https://tools.ietf.org/html/rfc4493)) 在长生不老药中.
* [cipher](https://github.com/rubencaro/cipher) - Elixir 加密库，用于加密/解密任意二进制文件.
* [cloak](https://github.com/danielberkompas/cloak) - Cloak 使使用 Ecto 加密变得容易.（[Docs](https://hexdocs.pm/cloak/readme.html)).
* [comeonin](https://github.com/riverrun/comeonin) - Elixir 的密码散列（argon2、bcrypt、pbkdf2_sha512）库.（[https://hexdocs.pm/comeonin/api-reference.html](https://hexdocs.pm/comeonin/api-reference.html)).
* [crypto_rsassa_pss](https://github.com/potatosalad/erlang-crypto_rsassa_pss) - Erlang 的 RSASSA-PSS 公钥加密签名算法.
* [elixir_tea](https://github.com/keichan34/elixir_tea) - Elixir 中的 TEA 实施.
* [ex_bcrypt](https://github.com/manelli/ex_bcrypt) - OpenBSD bcrypt 密码散列算法的 Elixir 包装器.
* [ex_crypto](https://github.com/ntrepid8/ex_crypto)  - Erlang `crypto` 和 `public_key` 模块的 Elixir 包装器. 为许多加密函数提供合理的默认值，使其更易于使用.（[Docs](https://hexdocs.pm/ex_crypto/readme.html)).
* [exgpg](https://github.com/rozap/exgpg) - 使用 Elixir 的 gpg.
* [nimble_totp](https://github.com/dashbitco/nimble_totp) - 允许为 2FA 实施基于时间的一次性密码 (TOTP).
* [ntru_elixir](https://github.com/alisinabh/ntru_elixir)  - libntru 的 Elixir 包装器. 后量子密码系统.
* [pot](https://github.com/yuce/pot) - Erlang 库，用于生成与 Google Authenticator 兼容的一次性密码.
* [rsa](https://github.com/trapped/elixir-rsa) - Elixir 的“public_key”加密封装.
* [rsa_ex](https://github.com/anoskov/rsa-ex) - 使用 RSA 密钥的库.
* [siphash-elixir](https://github.com/whitfin/siphash-elixir) - SipHash 哈希系列的 Elixir 实现.
* [tea_crypto](https://github.com/keichan34/tea_crypto_erl) - 微型加密算法实现.

## CSV
*使用 CSV 的库和实现.*

* [cesso](https://github.com/meh/cesso) - Elixir 的 CSV 处理库.
* [csv](https://github.com/beatrichartz/csv) - Elixir 的 CSV 解码和编码.
* [csv2sql](https://github.com/Arp-G/csv2sql) - 一个快速且全自动的 CSV 到数据库导入器.
* [csvlixir](https://github.com/jimm/csvlixir) - Elixir 的 CSV 读/写应用程序.
* [ecsv](https://github.com/erpuno/ecsv) - Elixir 的基于 libcs​​v 的快速流解析器.
* [ex_csv](https://github.com/CargoSense/ex_csv) - Elixir 的 CSV.
* [nimble_csv](https://github.com/plataformatec/nimble_csv) - Elixir 的简单快速的 CSV 解析和转储库.

## Date and Time
*用于处理日期和时间的库.*

* [block_timer](https://github.com/adamkittelson/block_timer) - 使用 :timer.apply_after 和 :timer.apply_interval 的宏和一个块.
* [calendar](https://github.com/lau/calendar) - Calendar 是 Elixir 的日期和时间库.
* [calendarific](https://github.com/Bounceapp/elixir-calendarific) - Calendarific 是假日 API Calendarific 的包装器.
* [calixir](https://github.com/rengel-de/calixir) - Calixir 是 Lisp 日历软件 calendrica-4.0 到 Elixir 的一个端口.
* [chronos](https://github.com/nurugger07/chronos) - Elixir 日期/时间库.
* [cocktail](https://github.com/peek-travel/cocktail) - 基于 iCalendar 事件的 Elixir 日期重复库.
* [cronex](https://github.com/jbernardo95/cronex) - 类似 Cron 的系统，您可以安装在您的监督树中.
* [crontab](https://github.com/jshmrtn/crontab) - Cron 表达式解析器、作曲家和日期候选查找器.
* [emojiclock](https://github.com/nathanhornby/emojiclock-elixir) - 一个 Elixir 模块，为您提供给定小时的表情符号时钟.
* [ex_ical](https://github.com/fazibear/ex_ical) - ICalendar 解析器.
* [filtrex](https://github.com/rcdilorenzo/filtrex) - 用于从客户端执行和验证复杂的类似 SQL 的过滤器（例如智能过滤器）的库.
* [good_times](https://github.com/DevL/good_times) - 富有表现力且易于使用的日期时间功能.
* [jalaali](https://github.com/jalaali/elixir-jalaali) - 改进了 Elixir 的日历实现.
* [milliseconds](https://github.com/davebryson/elixir_milliseconds) - 在 Elixir 中处理毫秒的简单库.
* [moment](https://github.com/atabary/moment) - 在 Elixir 中解析、验证、操作和显示日期.
* [open_hours](https://github.com/hopsor/open_hours) - 使用营业时间计算时间.
* [quantum](https://github.com/quantum-elixir/quantum-core) - Elixir 应用程序的类似 Cron 的作业调度程序.
* [repeatex](https://github.com/rcdilorenzo/repeatex) - 重复日期的自然语言解析.
* [tiktak](https://github.com/ConduitMobileRND/tiktak) - 用 Elixir 编写的快速、轻量级的 Web 调度程序.
* [timelier](https://github.com/ausimian/timelier) - Elixir 的 cron 样式调度程序.
* [timex](https://github.com/bitwalker/timex) - 易于使用的 Elixir 日期和时间模块.
* [timex_interval](https://github.com/atabary/timex-interval) - 基于 Timex 的 Elixir 项目的日期/时间间隔库.
* [tzdata](https://github.com/lau/tzdata) - Elixir 中的时区数据库.

## Debugging
*用于调试代码和应用程​​序的库和工具.*

* [beaker](https://github.com/hahuang65/beaker) - Elixir 的统计和度量库.
* [booter](https://github.com/eraserewind/booter) - 逐步启动 Elixir 应用程序.
* [dbg](https://github.com/fishcakez/dbg) - Elixir 的分布式跟踪.
* [eflame](https://github.com/proger/eflame) - Erlang 的火焰图分析器.
* [eper](https://github.com/massemanet/eper) - Erlang 性能和调试工具.
* [ether](https://github.com/maarek/ether) - Ether 提供了将 Elixir 挂钩到 Erlang 调试器的功能.
* [ex_debug_toolbar](https://github.com/kagux/ex_debug_toolbar) - Phoenix 项目的工具栏，用于交互式调试代码并显示有关请求的有用信息：日志、时间线、数据库查询等.
* [exrun](https://github.com/liveforeverx/exrun) - 具有速率限制和简单的基于宏的接口的 Elixir 分布式跟踪.
* [extrace](https://github.com/redink/extrace) - Recon Trace 的 Elixir 包装器.
* [git_hooks](https://github.com/qgadrian/elixir_git_hooks) - 为 Elixir 项目添加 git 钩子.
* [inspector](https://github.com/marciol/inspector) - 一个简单的单行模块，允许更友好的调试体验. 
* [observer_cli](https://github.com/zhongwencool/observer_cli) - 在命令行中可视化 Elixir &amp; Erlang 节点，旨在帮助开发人员调试生产系统.
* [quaff](https://github.com/qhool/quaff) - Debug 模块提供了一个简单的帮助界面，用于在 erlang 图形调试器中运行 Elixir 代码.
* [rexbug](https://github.com/nietaki/rexbug) - 用于“redbug”生产友好型 Erlang 跟踪调试器的 Elixir 包装器.
* [visualixir](https://github.com/koudelka/visualixir) - 远程 BEAM 节点的过程可视化器.

## Deployment
*在其他机器上自动安装和运行您的代码.*

* [akd](https://github.com/annkissam/akd) - Capistrano 类似、可配置且易于设置 Elixir 部署自动化框架.
* [ansible-elixir-stack](https://github.com/HashNuke/ansible-elixir-stack) - 单命令设置和部署到服务器，对 Phoenix 应用程序提供一流的支持.
* [bootleg](https://github.com/labzero/bootleg) - Elixir 的简单部署和服务器自动化.
* [bottler](https://github.com/rubencaro/bottler) - Bottler 是一组工具，旨在帮助您生成版本、将它们发送到您的服务器、将它们安装在那里，并让它们在生产中上线.
* [edeliver](https://github.com/boldpoker/edeliver) - Elixir 和 Erlang 的部署.
* [elixir-on-docker](https://github.com/CrowdHailer/elixir-on-docker) - 开始为云环境开发集群 Elixir 应用程序的项目模板.
* [exdm](https://github.com/joeyates/exdm) - 通过混合任务部署 Elixir 应用程序.
* [exreleasy](https://github.com/miros/exreleasy) - 用于发布 Elixir 应用程序的简单且对 Mix 友好的工具.
* [gatling](https://github.com/hashrocket/gatling) - 混合任务的集合以自动从 git 创建一个 exrm 版本并在您的服务器上启动/升级它.
* [Gigalixir](https://www.gigalixir.com)  - 为 Elixir 设计的全功能 PaaS. 支持集群、热升级和远程控制台/观察器. 无需信用卡即可免费试用.
* [heroku-buildpack-elixir](https://github.com/HashNuke/heroku-buildpack-elixir) - Heroku buildpack 将 Elixir 应用程序部署到 Heroku.

## Documentation
*用于创建文档的库和工具.*

* [blue_bird](https://github.com/KittyHeaven/blue_bird)  - BlueBird 是一个用 Elixir 编程语言为 Phoenix 框架编写的库. 它允许您从控制器和自动化测试中的注释生成 API 蓝图格式的 API 文档.
* [bureaucrat](https://github.com/api-hogs/bureaucrat) - 从测试中生成 Phoenix API 文档.
* [ex_doc](https://github.com/elixir-lang/ex_doc) - ExDoc 是为您的 Elixir 项目生成文档的工具.
* [ex_doc_dash](https://github.com/JonGretar/ExDocDash) - ExDoc 的格式化程序，用于生成用于 Dash.app 的 docset 文档.
* [hexdocset](https://github.com/yesmeck/hexdocset) - 将十六进制文档转换为 Dash.app 的文档集格式.
* [inch-ci](http://inch-ci.org/) - Ruby 和 Elixir 的文档徽章.
* [maru_swagger](https://github.com/falood/maru_swagger) - 将符合 swagger 的文档添加到您的 maru API.
* [phoenix_api_docs](https://github.com/smoku/phoenix_api_docs) - 从 Phoenix 框架中的控制器和测试生成 API 蓝图文档.
* [phoenix_swagger](https://github.com/xerions/phoenix_swagger) - 提供与 Phoenix 框架的 swagger 集成.
* [xcribe](https://github.com/brainn-co/xcribe) - 使用 Swagger (OpenAPI) 或 API 蓝图规范从测试中生成 API 文档.

## Domain-specific language
*针对特定应用领域的专业计算机语言.*

* [Absinthe Graphql](https://github.com/absinthe-graphql/absinthe) - 功能齐全的 GraphQL 库.
* [absinthe_gen](https://github.com/sashman/absinthe_gen) - Absithne 的脚手架生成器.
* [JSON-LD.ex](https://github.com/marcelotto/jsonld-ex) - 的实施 [JSON-LD](http://www.w3.org/TR/json-ld/) 标准为 [RDF.ex](https://github.com/marcelotto/rdf-ex).
* [RDF.ex](https://github.com/marcelotto/rdf-ex) - 的实施 [RDF](https://www.w3.org/TR/rdf11-primer/) Elixir 中的数据模型.
* [SPARQL.ex](https://github.com/marcelotto/sparql-ex) - 的实施 [SPARQL](http://www.w3.org/TR/sparql11-overview/) Elixir 中的标准.

## ECMAScript
*使用 JavaScript、JScript 或 ActionScript 的实现.*

* [elixirscript](https://github.com/elixirscript/elixirscript/) - 从 Elixir 到 Javascript 的转编译器.
* [estree](https://github.com/bryanjos/elixir-estree) - Elixir 中 SpiderMonkey Parser API 的实现.
* [phoenix_gon](https://github.com/khusnetdinov/phoenix_gon) - 允许您毫无问题地将 Phoenix 环境或控制器变量传递给 JavaScript.
* [phoenix_routes_js](https://github.com/khusnetdinov/phoenix_routes_js) - Phoenix 在 JavaScript 代码和浏览器控制台中路由助手.

## Email
*使用电子邮件和其他东西.*

* [bamboo](https://github.com/thoughtbot/bamboo)  - 可组合、可测试和基于适配器的电子邮件库. 开箱即用支持使用 Phoenix 进行渲染，以及用于在 dev 中预览已发送电子邮件的插件.
* [burnex](https://github.com/Betree/burnex) - 刻录机电子邮件（临时地址）检测器.
* [echo](https://github.com/zmoshansky/echo)  - 元通知系统；  Echo 检查通知首选项并发送通知.
* [ex_postmark](https://github.com/KamilLelonek/ex_postmark) - 用于在 Elixir 中发送模板电子邮件的邮戳适配器.
* [gen_smtp](https://github.com/Vagabond/gen_smtp) - 可以通过回调模块扩展的通用 Erlang SMTP 服务器和客户端.
* [gmail](https://github.com/craigp/elixir-gmail) - Elixir 的简单 Gmail REST API 客户端.
* [mail](https://github.com/DockYard/elixir-mail) - Elixir 中的 RFC2822 实现，为可组合性而构建.
* [mailer](https://github.com/antp/mailer) - 一个简单的 SMTP 邮件程序.
* [mailibex](https://github.com/awetzel/mailibex) - 包含 Elixir 中与电子邮件相关的实现的库：dkim、spf、dmark、mimemail、smtp.
* [mailman](https://github.com/kamilc/mailman) - Mailman 提供了一种在 Elixir 应用程序中定义邮件程序的简洁方式.
* [pop3mail](https://hex.pm/packages/pop3mail) - Pop3 客户端通过命令行或 Elixir API 从收件箱下载电子邮件（包括附件）.
* [ravenx](https://github.com/acutario/ravenx) - Elixir 应用程序的通知调度库.
* [smoothie](https://github.com/jfrolich/smoothie) - 电子邮件模板的 Smoothie 内联样式，并从 HTML 生成纯文本版本.
* [swoosh](https://github.com/swoosh/swoosh) - Compose, deliver and test your Emails (with attachments!) easily in Elixir with adapters for SMTP, Sendgrid, Mandrill, Mailgun, Postmark and lots others, plus Phoenix integration with mailbox preview.

## Embedded Systems
*嵌入式系统开发.*

* [nerves](http://nerves-project.org) - 在 Elixir 中编写嵌入式软件的框架.

## Encoding and Compression
*以不同格式转换数据或对其进行压缩.*

* [ex_rlp](https://github.com/exthereum/ex_rlp) - 以太坊 RLP（递归长度前缀）编码的 Elixir 实现.
* [huffman](https://github.com/SenecaSystems/huffman) - Elixir 中的 Huffman 编码和解码.

## Errors and Exception Handling
*处理错误和异常.*

* [exceptional](https://github.com/expede/exceptional) - 快乐路径编程和异常处理的助手.
* [happy](https://github.com/vic/happy) - 快乐路径编程，替代长生不老药 `with` 形式.
* [OK](https://github.com/CrowdHailer/OK) - 带有结果单子的优雅错误处理，具有简单而强大的 `with` 构造和快乐的路径管道运算符.
* [sentry-elixir](https://github.com/getsentry/sentry-elixir) - 官方 Elixir 客户端 [Sentry](https://sentry.io/).
* [AppSignal Elixir](https://github.com/appsignal/appsignal-elixir) - 官方 [AppSignal](https://appsignal.com/) 长生不老药包.

## Eventhandling
*在 Elixir 中发送/发射和接收/处理事件.*

* [cizen](https://gitlab.com/cizen/cizen) - 使用 sagas 集合构建高度并发、可监控和可扩展的应用程序.
* [event_bus](https://github.com/mustafaturan/event_bus) - 带有主题过滤和内置事件存储和事件观察器的简单事件总线实现.
* [goldrush](https://github.com/DeadZen/goldrush) - Erlang/OTP 应用程序的小型、快速事件处理和监控.
* [reaxive](https://github.com/alfert/reaxive) - Reaxive 是一个反应式事件处理库，灵感来自 [Elm](http://elm-lang.org) 和反应式扩展.
* [wait_for_it](https://github.com/jvoegele/wait_for_it) - 为同步并发活动提供方便且易于使用的设施.

## Examples and funny stuff
*示例代码和太有趣或好奇的东西更不用提了.*

* [butler_cage](https://github.com/keathley/butler_cage) - 一个管家插件，用于显示尼克凯奇的愚蠢照片.
* [butler_tableflip](https://github.com/keathley/butler_tableflip) - 与管家翻桌.
* [changelog.com](https://github.com/thechangelog/changelog.com) - 运行用 Phoenix 1.4 构建的 changelog.com 的 CMS.
* [coderplanets.com](https://github.com/coderplanets/coderplanets_server) - 使用 Phoenix 1.4 和 Absinthe 构建的 coderplanets.com 的 GraphQL api.
* [dice](https://github.com/stocks29/dice) - 在 Elixir 中掷骰子.
* [elixir_koans](https://github.com/elixirkoans/elixir-koans) - [Elixir koans](http://elixirkoans.io/) 是开始使用 elixir 编程语言的一种有趣、简单的方法.
* [ex_chain](https://github.com/eljojo/ex_chain) - 使用 Elixir 构建的生成有趣推文的简单马尔可夫链.
* [ex_iss](https://github.com/cryptobird/ex_iss) - 此软件包用于与 Open Notify API 连接，以获取诸如 ISS 当前位置、机组人员以及何时经过某个位置等信息.
* [feedx](https://github.com/erneestoc/feedx)  - 将社交订阅功能添加到当前应用程序. 以 OTP 伞式应用为例，有 3 个应用. 薄凤凰控制器.
* [harakiri](https://github.com/rubencaro/harakiri) - 帮助应用程序自杀.
* [hello_phoenix](https://github.com/bigardone/phoenix-react-redux-template) - 带有 Phoenix、React 和 Redux 的 SPA 应用程序模板.
* [hexpm](https://github.com/hexpm/hexpm) - 使用 Phoenix 1.3 构建的十六进制包管理器站点的源代码.
* [kaisuu](https://github.com/SebastianSzturo/kaisuu) - 在 Twitter 上实时观看日本的汉字使用情况.
* [koans](https://github.com/dojo-toulouse/elixir-koans) - 使用 elixir-koans 学习 Elixir.
* [lolcat](https://github.com/restartr/ex-lolcat)  - 这是busyloop/lolcat的克隆. 但它不支持动画和原版的一些功能.
* [magnetissimo](https://github.com/sergiotapia/magnetissimo) - Web 应用程序，索引所有流行的 torrent 站点，并将其保存到本地数据库.
* [oop](https://github.com/wojtekmach/oop) - Elixir 中的 OOP！
* [phoenix-chat-example](https://github.com/dwyl/phoenix-chat-example)  - 在 Phoenix 中为完整的初学者构建聊天应用程序的分步示例/教程. 涵盖测试、文档和部署. 凤凰`1.5.3`.
* [phoenix-ecto-encryption-example](https://github.com/dwyl/phoenix-ecto-encryption-example) - 一个全面的示例/教程，向人们展示如何使用 Ecto Types 在 Phoenix 1.4 应用程序中透明地加密/解密数据.
* [phoenix-flux-react](https://github.com/fxg42/phoenix-flux-react) - Phoenix Channels、GenEvents、React 和 Flux 的实验.
* [phoenix-liveview-counter-tutorial](https://github.com/dwyl/phoenix-liveview-counter-tutorial) - 完整的初学者分步教程在 Phoenix `1.5.3` 和 LiveView `0.14.1` 中构建实时计数器.
* [phoenix-todo-list-tutorial](https://github.com/dwyl/phoenix-todo-list-tutorial) - 完整的初学者分步教程，用于在 Phoenix `1.5.3` 中从头开始构建待办事项列表.
* [portal](https://github.com/josevalim/portal) - Elixir 中分布式门户数据传输应用程序的射击容错门.
* [real world example app](https://github.com/gothinkster/elixir-phoenix-realworld-example-app) - Elixir / Phoenix 实施 [RealWorld.io](https://realworld.io/) 后端规格 - 中型克隆.
* [rollex](https://gitlab.com/olhado/rollex) - Elixir 库使用 Pratt Parser 算法来计算掷骰子.
* [rubix](https://github.com/YellowApple/Rubix) - Elixir 的一个非常简单（且几乎无法运行）的 Ruby 运行程序.
* [stranger](https://github.com/cazrin/stranger) - Elixir Phoenix 应用程序与随机选择的陌生人匿名聊天.
* [tilex](https://github.com/hashrocket/tilex) - Hashrocket 使用 Phoenix 1.3 构建的 TIL 网站的源代码.
* [weather](https://github.com/tacticiankerala/elixir-weather) - 使用 Elixir 构建的命令行天气应用程序.

## Feature Flags and Toggles
*管理功能切换的库（AKA 功能标志）：可以在运行时通过某些界面切换的 ON/OFF 值*

* [ConfigCat](https://github.com/configcat/elixir-sdk) - 用于 ConfigCat 托管功能标志服务的 Elixir SDK.
* [flippant](https://github.com/sorentwo/flippant) - Elixir 世界的功能翻转.
* [fun_with_flags](https://github.com/tompave/fun_with_flags)  - 使用 Redis 或 Ecto 实现持久性的功能切换库、用于速度的 ETS 缓存和用于分布式缓存破坏的 PubSub. 带有 Phoenix 和 Plug 的管理 Web UI.
* [molasses](https://github.com/securingsincity/molasses) - 使用 redis 或 SQL（使用 Ecto）作为支持服务的功能切换库.

## Feeds
*使用 RSS 或 ATOM 等提要的库.*

* [atomex](https://github.com/Betree/atomex) - ATOM 提要构建器，专注于标准合规性、安全性和可扩展性.
* [feeder](https://github.com/michaelnisi/feeder) - 解析 RSS 和 Atom 提要.
* [feeder_ex](https://github.com/manukall/feeder_ex)  - RSS 提要解析器. 喂食器的简单包装.
* [feedme](https://github.com/umurgdk/elixir-feedme) - 基于 erlang 的 xmerl xml 解析器构建的 RSS/Atom 解析器.

## Files and Directories
*用于处理文件和目录的库和实现.*

* [Belt](https://bitbucket.org/pentacent/belt/) - 可扩展的文件上传库，支持 SFTP、S3 和文件系统存储.
* [cassius](https://github.com/jquadrin/cassius) - 监控 Linux 文件系统事件.
* [dir_walker](https://github.com/pragdave/dir_walker) - DirWalker 懒惰地遍历一个或多个目录树，深度优先，返回连续的文件名.
* [elixgrep](https://github.com/bbense/elixgrep) - 用于对文件集合执行 Hadoop 风格的 Map/Reduce 操作的框架.
* [ex_guard](https://github.com/slashmili/ex_guard) - ExGuard 是一个混合命令，用于处理文件系统修改事件.
* [ex_minimatch](https://github.com/gniquil/ex_minimatch) - 不走树就走遍路径！
* [exfile](https://github.com/keichan34/exfile) - Elixir 和 Plug 中的文件上传处理、持久性和处理.
* [exfswatch](https://github.com/falood/exfswatch) - 基于 __fs__ 的文件更改观察程序包装器.
* [eye_drops](https://github.com/rkotze/eye_drops) - 可配置的混合任务来观察文件变化并运行相应的命令.
* [format_parser.ex](https://github.com/ahtung/format_parser.ex) - Elixir 库，用于确定文件的类型和格式.
* [fs](https://github.com/synrc/fs) - Erlang 文件系统监听器.
* [fwatch](https://github.com/ryo33/fwatch-ex) - 基于 __fs__ 的基于回调的文件观察器.
* [ivcu](https://github.com/elixir-ivcu/ivcu) - 文件验证器、转换器和上传器.
* [librex](https://github.com/ricn/librex) - 使用 LibreOffice 将办公文档转换为其他格式的 Elixir 库.
* [Radpath](https://github.com/lowks/Radpath) - Elixir 的路径库，灵感来自 Python 的 Enhpath.
* [sentix](https://github.com/whitfin/sentix) - 基于 fswatch 的 Elixir 跨平台文件观察器.
* [sizeable](https://github.com/arvidkahl/sizeable) - 一个使文件大小易于阅读的 Elixir 库.
* [waffle](https://github.com/elixir-waffle/waffle) - Elixir 灵活的文件上传和附件库.
* [zarex](https://github.com/ricn/zarex) - Elixir 的文件名清理.

## Formulars
*处理网络公式和类似的东西.*

* [forms](https://github.com/spawnproc/forms) - Erlang 商业文件生成器.

## Framework Components
*来自 Web 开发框架的独立组件.*

* [absinthe_plug](https://github.com/absinthe-graphql/absinthe_plug) - 对苦艾酒的插件支持.
* [addict](https://github.com/trenpixster/addict) - Phoenix 框架的用户身份验证.
* [airbrake_plug](https://github.com/romul/airbrake_plug) - 向 Airbrake 报告插头堆栈或其他任何错误.
* [better_params](https://github.com/sheharyarn/better_params) - Elixir Plug 用于 Web 应用程序中更清晰的请求参数.
* [blaguth](https://github.com/lexmag/blaguth) - Plug 应用程序中的基本访问身份验证.
* [commanded](https://github.com/slashdotdash/commanded) - 命令查询职责分离 (CQRS) 应用程序的命令处理中间件.
* [cors_plug](https://github.com/mschae/cors_plug) - 一个 Elixir 插件，可将 CORS 标头添加到请求并响应预检请求 (OPTIONS).
* [corsica](https://github.com/whatyouhide/corsica) - 用于处理 CORS 请求的 Elixir 库.
* [crudex](https://github.com/bitgamma/crudex) - Phoenix 和 Ecto 的 CRUD 实用程序.
* [dayron](https://github.com/inaka/Dayron) - 与 `Ecto.Repo` 类似的存储库，可处理 REST API 请求而不是数据库.
* [ex_admin](https://github.com/smpallen99/ex_admin) - ExAdmin 是 Elixir 和 Phoenix 框架的自动管理包.
* [exdjango](https://github.com/nicksanders/exdjango) - 一些与 django 一起工作的 elixir 库.
* [exrecaptcha](https://github.com/adanselm/exrecaptcha) - Elixir 应用程序的简单 reCaptcha 显示/验证代码.
* [filterable](https://github.com/omohokcoj/filterable) - 受 Rails has_scope 启发的 Phoenix 框架的简单查询参数过滤.
* [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - 一个长生不老药绑定 [libgraphqlparser](https://github.com/graphql/libgraphqlparser).
* [http_router](https://github.com/sugar-framework/elixir-http-router) - 带有各种宏的 HTTP 路由器，以帮助开发您的应用程序和组织您的代码.
* [kerosene](https://github.com/elixirdrops/kerosene) - Ecto 和 Phoenix 的分页.
* [mellon](https://github.com/sajmoon/mellon) - Plug 应用程序的身份验证模块.
* [multiverse](https://github.com/Nebo15/multiverse) - 允许通过 API 请求/响应网关添加版本兼容层的插件.
* [params](https://github.com/vic/params) - 使用 Ecto 强制/验证参数结构，类似于 Rails 的强参数.
* [passport](https://github.com/opendrops/passport) - Passport 为 Phoenix 应用程序提供身份验证.
* [phoenix_ecto](https://github.com/phoenixframework/phoenix_ecto) - Phoenix 和 Ecto 集成.
* [phoenix_haml](https://github.com/chrismccord/phoenix_haml) - 用于 Haml 的 Phoenix 模板引擎.
* [phoenix_html](https://github.com/phoenixframework/phoenix_html) - Phoenix.HTML 函数用于处理 HTML 字符串和模板.
* [phoenix_html_sanitizer](https://github.com/elixirstatus/phoenix_html_sanitizer) - Phoenix 的 HTML Sanitizer 集成.
* [phoenix_html_simplified_helpers](https://github.com/ikeikeikeike/phoenix_html_simplified_helpers) - phoenix html 的一些助手（截断、time_ago_in_words、number_with_delimiter）.
* [phoenix_linguist](https://github.com/jxs/phoenix_linguist)  - 将 Phoenix 与 Linguist 集成的项目，提供插件和查看助手. 它看起来被遗弃了：它的最后一次提交是在 2015 年，它的 CI 运行 Elixir 1.0.3.
* [phoenix_live_reload](https://github.com/phoenixframework/phoenix_live_reload) - 为 Phoenix 提供实时重新加载功能.
* [phoenix_meta_tags](https://github.com/hlongvu/phoenix_meta_tags) - 为网站生成元标记.
* [phoenix_pubsub_postgres](https://github.com/opendrops/phoenix-pubsub-postgres) - 用于 Phoenix 应用程序的 Postgresql PubSub 适配器.
* [phoenix_pubsub_rabbitmq](https://github.com/pma/phoenix_pubsub_rabbitmq) - 用于 Phoenix 的 PubSub 层的 RabbitMQ 适配器.
* [phoenix_pubsub_redis](https://github.com/phoenixframework/phoenix_pubsub_redis) - Phoenix 框架的 Redis PubSub 适配器.
* [phoenix_pubsub_vernemq](https://github.com/larshesel/phoenix_pubsub_vernemq) - Phoenix 框架的 VerneMQ MQTT pubsub 适配器.
* [phoenix_slime](https://github.com/slime-lang/phoenix_slime) - 对 Phoenix 的 Slim 模板支持.
* [phoenix_token_auth](https://github.com/manukall/phoenix_token_auth)  - Phoenix 的令牌认证解决方案. 对于 API 或单页应用程序很有用.
* [phx_component_helpers](https://github.com/cblavier/phx_component_helpers) - 可扩展的 live_components，没有样板.
* [plug](https://github.com/elixir-lang/plug) - Web 应用程序之间的可组合模块的规范和便利.
* [plug_accesslog](https://github.com/mneudert/plug_accesslog) - 用于写入访问日志的插件.
* [plug_and_play](https://github.com/henrik/plug_and_play) - 使用更少的样板设置插件应用程序.
* [plug_auth](https://github.com/bitgamma/plug_auth) - 收集与身份验证相关的插件.
* [plug_canonical_host](https://github.com/remiprev/plug_canonical_host) - 插入以确保所有请求都来自单个规范主机.
* [plug_checkup](https://github.com/ggpasqualino/plug_checkup) - 为您的应用添加简单的健康检查插件.
* [plug_cloudflare](https://github.com/c-rack/plug_cloudflare) - 受 mod_cloudflare 启发，此 Elixir 插件将 Cloudflares CF-Connecting-IP HTTP 请求标头解析为 Plug.Conn 的 remote_ip 字段.
* [plug_forward_peer](https://github.com/awetzel/plug_forwarded_peer) - 非常简单的插件，根据 RFC7239 读取 X-Forwarded-For 或 Forwarded 标头，并使用根客户端 ip 填充 conn.remote_ip.
* [plug_fprof](https://github.com/obmarg/plug_fprof) - 将 fprof 跟踪添加到请求的插件，以便于进行分析.
* [plug_graphql](https://github.com/graphql-elixir/plug_graphql) - 凤凰插头集成 [GraphQL Elixir](http://graphql-elixir.org/).
* [plug_heartbeat](https://github.com/whatyouhide/plug_heartbeat) - 用于响应心跳请求的插件.
* [plug_jwt](https://github.com/bryanjos/plug_jwt) - 用于 JWT 身份验证的插件.
* [plug_password](https://github.com/azranel/plug_password) - 添加简单的基于 cookie 的身份验证的插件.
* [plug_rails_cookie_session_store](https://github.com/cconstantin/plug_rails_cookie_session_store) - Rails 兼容插件会话存储.
* [plug_redirect_https](https://github.com/stocks29/plug_redirect_https) - 插入以将 http 请求重定向到反向代理后面的 https 请求.
* [plug_require_header](https://github.com/DevL/plug_require_header) - 要求并提取 HTTP 标头并处理丢失的标头.
* [plug_response_header](https://github.com/c-rack/plug_response_header) - 轻松操作 HTTP 响应标头.
* [plug_ribbon](https://github.com/stnly/plug_ribbon) - 在开发环境中向您的 Web 应用程序注入功能区.
* [plug_secex](https://github.com/techgaun/plug_secex) - 添加各种 HTTP 标头以使 Phoenix/Elixir 应用程序更安全的插件.
* [plug_session_memcached](https://github.com/gutschilla/plug-session-memcached) - 一个非常简单的用于 Elixir 插件的 memcached 会话存储.
* [plug_sigaws](https://github.com/handnot2/plug_sigaws) - Phoenix/Plug Routes 的 AWS Signature V4 身份验证保护（[Docs](https://hexdocs.pm/plug_sigaws/PlugSigaws.html)).
* [plug_statsd](https://github.com/jeffweiss/plug_statsd) - 用于自动将计时和计数指标发送到 statsd 的插件.
* [plugs](https://github.com/sugar-framework/plugs) - 用于 Web 应用程序的 Plug 中间件的集合.
* [plugsnag](https://github.com/jarednorman/plugsnag) - Elixir 插件的错误通知器.
* [raygun](https://github.com/cobenian/raygun) - 捕获错误并将它们发送给 Raygun.
* [react_phoenix](https://github.com/geolessel/react-phoenix) - 在 Phoenix 视图中呈现 React.js 组件，重点是易于安装和早午餐兼容性.
* [recaptcha](https://github.com/samueljseay/recaptcha) - 用于 Elixir 应用程序的简单 reCaptcha 2 库.
* [resin](https://github.com/Frost/resin) - Resin 是一个插件，它将为通过它的每个请求添加可配置的延迟，除非在生产中运行.
* [revision_plate_ex](https://github.com/KazuCocoa/revision_plate_ex) - 为端点提供服务的插件应用程序和中间件返回应用程序的 REVISION.
* [rummage_ecto](https://github.com/Excipients/rummage_ecto) - 用于搜索、排序和分页 Ecto 查询的可配置框架.
* [rummage_phoenix](https://github.com/Excipients/rummage_phoenix) - Phoenix 中用于搜索、排序和分页模型的支持框架，支持 HTML.
* [scaffold](https://github.com/gausby/scaffold) - 基于从 Git-repo 获取的模板创建新项目的混合任务.
* [scrivener](https://github.com/drewolson/scrivener) - 对您的 Ecto 查询进行分页.
* [scrivener_headers](https://github.com/doomspork/scrivener_headers) - 使用 Scrivener 和 HTTP 标头对 API 响应进行分页的助手.
* [scrivener_html](https://github.com/mgwidmann/scrivener_html) - 为与 Scrivener 的页面结构一起使用而构建的助手，可以轻松地为各种 CSS 框架构建 HTML 输出.
* [sentinel](https://github.com/britton-jb/sentinel) - Phoenix 扩展监护人的身份验证框架，具有路由和其他基本功能.
* [surface](https://github.com/msaraiva/surface) - Phoenix 的服务器端渲染组件库.
* [torch](https://github.com/infinitered/torch)  - Torch 是 Phoenix 应用程序的快速管理生成器. 它使用生成器而不是 DSL 来确保代码保持可维护性.
* [trailing_format_plug](https://github.com/mschae/trailing_format_plug) - 一个 Elixir 插件，用于支持使用类似 rails 的尾随格式的遗留 API.
* [turn_the_page](https://hex.pm/packages/turn_the_page) - 为您的 Elixir 应用程序提供快速、简单和轻量级的分页系统.
* [webassembly](https://github.com/herenowcoder/webassembly) - Elixir 的 Web DSL.
* [weebo](https://github.com/stevenschobert/weebo) - Elixir 的 XML-RPC 解析器/格式化程序，完全支持数据类型映射.

## Frameworks
*Web 开发框架.*

* [exelli](https://github.com/pigmej/exelli) - 带有一些糖语法好东西的 Elli Elixir 包装器.
* [kitto](https://github.com/kittoframework/kitto) - 交互式仪表板的框架.
* [n2o](https://github.com/synrc/n2o) - 分布式应用服务器.
* [nitro](https://github.com/synrc/nitro) - 与氮兼容的 Web 框架.
* [phoenix](https://github.com/phoenixframework/phoenix) - Elixir Web 框架针对具有实时功能的全功能、容错应用程序.
* [placid](https://github.com/slogsdon/placid) - 一个 REST 工具包，用于使用 Elixir 构建高度可扩展和容错的 HTTP API.
* [rackla](https://github.com/AntonFagerberg/rackla) - Elixir 中的 API 网关.
* [relax](https://github.com/AgilionApps/relax) - 一个简单的 Elixir 实现 [jsonapi.org](http://jsonapi.org) 服务器.
* [rest](https://github.com/synrc/rest) - 具有类型化 JSON 的 Micro-REST 框架.
* [RIG](https://github.com/Accenture/reactive-interaction-gateway) - 为无状态微服务创建低延迟、交互式用户体验.
* [sugar](https://github.com/sugar-framework/sugar) - Elixir 的模块化 Web 框架.
* [trot](https://github.com/hexedpackets/trot) - Elixir 网络微框架.

## Games
*游戏的库和实现.*

* [Binbo](https://github.com/DOBRO/binbo) - 使用 Erlang 编写的国际象棋表示 [Bitboards](https://www.chessprogramming.org/Bitboards)，准备在游戏服务器上使用.
* [entice](https://github.com/entice/entice) - 分布式实体-组件-系统框架，提供自己的示例 MMORPG 服务器.
* [mines](https://github.com/kevlar1818/mines) - 终端中的扫雷克隆.
* [pictionary](https://github.com/Arp-G/pictionary) - 多人猜谜和绘画游戏（[skribbl.io](https://skribbl.io/) 克隆）.
* [rayex](https://github.com/shiryel/rayex) - Raylib 绑定​​到 Elixir 用于游戏编程.
* [Rovex](https://github.com/emadb/rovex) - 在 Elixir 中实现的火星漫游者 kata 已转变为基本的多人游戏.
* [vim_snake](https://github.com/theanht1/vim_snake) - 经典的多人蛇游戏，采用 Phoenix 框架构建的 Vim 风格的键绑定.

## Geolocation
*用于地理编码地址和处理纬度和经度的库.*

* [distance_api_matrix](https://github.com/C404/distance-matrix-api) - 通过谷歌距离矩阵 api 提供距离和航向计算.
* [geo](https://github.com/bryanjos/geo) - Elixir 的 GIS 功能集合.
* [geocalc](https://github.com/yltsrc/geocalc) - 计算纬度/经度点之间的距离、方位等.
* [geocoder](https://github.com/knrz/geocoder) - 一个简单、高效的地理编码器/反向地理编码器，带有内置缓存.
* [geohash](https://github.com/polmuz/elixir-geohash) - Geohash 编码/解码库.
* [geohash_nif](https://github.com/wstucco/geohash_nif/) - 替换作为 NIF 实现的 Geohash 编码/解码库.
* [geohax](https://github.com/evuez/geohax) - 使用邻居查找器进行 Geohash 编码和解码.
* [geoip](https://github.com/navinpeiris/geoip) - 查找给定 IP、主机名或“Plug.Conn”的地理位置.
* [geolix](https://github.com/mneudert/geolix) - MaxMind GeoIP2 数据库阅读器/解码器.
* [geonames](https://github.com/pareeohnos/geonames-elixir) - 围绕 GeoNames API 的简单 Elixir 包装器.
* [ip2location](https://github.com/nazipov/ip2location-elixir) - IP2Location 数据库的 Elixir 库.
* [ipgeobase](https://github.com/sergey-chechaev/elixir_ipgeobase) - 通过 IP 地址查找俄罗斯和乌克兰城市并查找其他国家/地区的国家/地区.
* [proj](https://github.com/CandyGumdrop/proj) - 使用 OSGeo 的 PROJ.4 的 Elixir 坐标转换库.
* [segseg](https://github.com/pkinney/segseg_ex) - 段段交叉分类器和计算器.
* [srtm](https://github.com/adriankumpf/srtm) - 查询来自 NASA 航天飞机雷达地形任务的高程数据位置.
* [topo](https://github.com/pkinney/topo) - Elixir 的几何库，用于计算两个几何之间的空间关系.
* [wheretz](https://github.com/UA3MQJ/wheretz) - Ruby gem 的 Elixir 版本，用于按地理坐标查找时区.

## GUI
*用于编写图形用户界面的库.*

* [scenic](https://github.com/boydm/scenic) - 便携式 2D UI 框架.

## Hardware
*硬件相关的东西，如 I/O 接口等.*

* [elixir_ale](https://github.com/fhunleth/elixir_ale) - Elixir 访问硬件 I/O 接口，例如 GPIO、I2C 和 SPI.
* [nerves](https://github.com/nerves-project/nerves) - 为 Raspberry Pi 和 BeagleBone Black 等平台构建固件的框架.

## HTML
*使用 HTML 的库和实现（对于 xml 工具，请访问 [XML](#xml) 部分）.*

* [floki](https://github.com/philss/floki) - 一个简单的 HTML 解析器，可以使用类似选择器的 CSS 进行搜索.
* [html_sanitize_ex](https://github.com/rrrene/html_sanitize_ex) - Elixir 的 HTML 消毒剂.
* [meseeks](https://github.com/mischov/meeseeks) - 使用 CSS 或 XPath 选择器从 HTML 和 XML 中解析和提取数据的库.
* [modest_ex](https://github.com/f34nk/modest_ex) - 使用 CSS 选择器对 html 字符串进行可管道转换的库，例如 find()、prepend()、append()、replace() 等.
* [myhtmlex](https://github.com/Overbryd/myhtmlex) - lexborisov 的 myhtml 的 Elixir/Erlang 绑定.
* [readability](https://github.com/keepcosmos/readability) - 可读性用于提取和整理文章.
* [texas](https://gitlab.com/dgmcguire/texas) - Texas is a powerful abstraction over updating your clients using server-side rendering and server-side Virtual DOM diff/patching.
* [tidy_ex](https://github.com/f34nk/tidy_ex) - Elixir 绑定到 HTML 工具的祖父 [http://www.html-tidy.org](http://www.html-tidy.org).

## HTTP
*用于处理 HTTP 和抓取网站的库.*

* [Ace](https://github.com/CrowdHailer/Ace) - HTTP Web 服务器和客户端，支持 http1 和 http2.
* [bolt](https://github.com/SebastianSzturo/bolt) - 简单快速的 http 代理.
* [cauldron](https://github.com/meh/cauldron) - 作为库的 HTTP/SPDY 服务器.
* [Crawler](https://github.com/fredwu/crawler) - Elixir 中的高性能网络爬虫.
* [Crawly](https://github.com/oltarasenko/crawly) - Elixir 的高级网络抓取和抓取框架.
* [SpiderMan](https://github.com/feng19/spider_man) - 基于 Broadway 的 Elixir 快速高级网络爬取和抓取框架.
* [elli](https://github.com/knutin/elli) - Elli 是一个网络服务器，您可以在 Erlang 应用程序中运行以公开 HTTP API.
* [etag_plug](https://github.com/sascha-wolf/etag_plug) - 一个简单易用的浅 ETag 插头.
* [explode](https://github.com/pkinney/explode) - 一个简单的实用程序，用于在基于 Plug- 和 Phoenix 的应用程序中使用标准 HTTP/JSON 错误有效负载进行响应.
* [exvcr](https://github.com/parroty/exvcr) - 受 VCR 启发的 Elixir 的 HTTP 请求/响应记录库.
* [finch](https://github.com/keathley/finch) - 基于 Mint 和 NimblePool 构建的专注于性能的 HTTP 客户端.
* [fuzzyurl](https://github.com/gamache/fuzzyurl.ex)  - 用于解析、构造和通配符匹配 URL 的 Elixir 库. 也可用于 [Ruby](https://github.com/gamache/fuzzyurl.rb) 和 [JavaScript](https://github.com/gamache/fuzzyurl.js).
* [gun](https://github.com/ninenines/gun) - 用于 Erlang/OTP 的 HTTP/1.1、HTTP/2 和 Websocket 客户端.
* [hackney](https://github.com/benoitc/hackney) - 用 Erlang 编写的简单 HTTP 客户端.
* [http](https://github.com/slogsdon/http) - Elixir 的 HTTP 服务器.
* [http_digex](https://github.com/techgaun/http_digex) - 创建基本摘要 HTTP 身份验证标头的模块.
* [http_proxy](https://github.com/KazuCocoa/http_proxy) - 多端口 HTTP 代理.
* [httpoison](https://github.com/edgurgel/httpoison) - 另一个由 hackney 提供支持的 Elixir HTTP 客户端.
* [httpotion](https://github.com/myfreeweb/httpotion) - Elixir 的精美 HTTP 客户端，基于 ibrowse.
* [ivar](https://github.com/swelham/ivar) - 一个围绕 HTTPoison 的轻量级包装器，它提供了一种流畅且可组合的方式来构建 http 请求.
* [lhttpc](https://github.com/talko/lhttpc) - 用 Erlang 实现的轻量级 HTTP/1.1 客户端.
* [mint](https://github.com/ericmj/mint) - Elixir 的功能性 HTTP 客户端，支持 HTTP/1 和 HTTP/2.
* [Mechanize](https://github.com/gushonorato/mechanize) - 在 Elixir 中轻松构建网络爬虫并自动与网站交互！
* [mnemonic_slugs](https://github.com/devshane/mnemonic_slugs) - Elixir 中令人难忘的助记符生成器.
* [mochiweb](https://github.com/mochi/mochiweb) - MochiWeb 是一个 Erlang 库，用于构建轻量级 HTTP 服务器.
* [neuron](https://github.com/uesteibar/neuron) - Elixir 的 GraphQL 客户端.
* [plug_wait1](https://github.com/wait1/plug_wait1) - 为 wait1 协议插入适配器.
* [raxx](https://github.com/CrowdHailer/raxx) - HTTP 网络服务器、框架和客户端的接口.
* [river](https://github.com/peburrows/river) - 一个轻量级和闪电般快速的 HTTP/2 客户端.
* [scrape](https://github.com/Anonyfox/elixir-scrape) - 轻松抓取任何网站、文章或 RSS/Atom Feed.
* [sparql_client](https://github.com/marcelotto/sparql_client) - 一个 [SPARQL protocol](https://www.w3.org/TR/sparql11-protocol/) Elixir 的客户.
* [spell](https://github.com/MyMedsAndMe/spell) - 法术是一个 [Web Application Messaging Protocol](http://wamp-proto.org/) Elixir 中的 (WAMP) 客户端实现.
* [tesla](https://github.com/teamon/tesla) - HTTP 客户端库，支持中间件和多个适配器.
* [Tube](https://github.com/narrowtux/Tube) - 纯 Elixir WebSocket 客户端库.
* [uri_query](https://github.com/shhavel/uri_query) - URI 编码 Elixir 中嵌套的 GET 参数和数组值.
* [uri_template](https://github.com/pezra/ex-uri-template) - Elixir 的 RFC6570 兼容 URI 模板处理器.
* [web_socket](https://github.com/slogsdon/plug-web-socket) - 探索插件应用程序的独立库以轻松采用 WebSocket.
* [webdriver](https://github.com/stuart/elixir-webdriver)  - 这是 WebDriver 协议客户端的实现. 它目前支持 PhantomJS、FireFox、ChromeDriver 和远程 webdriver 服务器（例如 Selenium）.
* [yuri](https://github.com/kemonomachi/yuri) - 用于表示 URI 的简单结构.

## Images
*用于处理和操作图像的库.*

* [alchemic_avatar](https://github.com/zhangsoledad/alchemic_avatar) - 用于从字符串生成字母头像的 Elixir 库.
* [artifact](https://github.com/doomspork/artifact) - Elixir 的文件上传和即时处理.
* [bump](https://github.com/evanfarrar/ex_bump) - 纯 Elixir 中的 BMP 文件编写器.
* [chunky_svg](https://github.com/mmmries/chunky_svg) - 使用 SVG 绘制事物的库.
* [cloudex](https://github.com/smeevil/cloudex) - Cloudex 是一个 Elixir 库，可以将图像文件或 url 上传到 Cloudinary.
* [eikon](https://github.com/tchoutri/Eikon) - 一个 Elixir 库，为图像文件提供只读接口.
* [elixir_exif](https://github.com/sschneider1207/ElixirExif) - 从 jpeg 文件中解析 exif 标签和缩略图数据.
* [ex_image_info](https://github.com/rNoz/ex_image_info) - 一个 Elixir 库，用于解析图像（二进制文件）并获取一组图像格式的尺寸、检测到的 mime 类型和整体有效性.
* [exexif](https://github.com/pragdave/exexif) - 纯 Elixir 库，用于从 jpeg 文件中提取 TIFF 和 EFIX 元数据.
* [exfavicon](https://github.com/ikeikeikeike/exfavicon) - 一个用于发现 favicon 的 Elixir 库.
* [gi](https://github.com/LangPham/gi) - GraphicsMagick 命令行的 Elixir 包装器.
* [identicon](https://github.com/rbishop/identicon) - 用于生成 5x5 标识符的 Elixir 库.
* [image64](https://hex.pm/packages/image64) - 用于处理 base64 编码图像的工具.
* [imagineer](https://github.com/SenecaSystems/imagineer) - Elixir 中的图像解析.
* [imgex](https://github.com/ianwalter/imgex) - 用于在 Elixir 中生成 imgix URL 的非官方客户端库.
* [mogrify](https://github.com/route/mogrify) - ImageMagick 命令行的 Elixir 包装器.
* [png](https://github.com/yuce/png)  - 用于创建 PNG 图像的纯 Erlang 库. 它目前可以创建 8 位和 16 位 RGB、带 alpha 的 RGB、索引、灰度和带 alpha 的灰度图像.
* [thumbnex](https://github.com/talklittle/thumbnex) - 从图像和视频截图创建缩略图.
* [thumbor_client](https://github.com/globocom/thumbor-client-ex) - Thumbor 客户端.

## Instrumenting / Monitoring
*用于收集和导出指标的库.*

* [app_optex](https://github.com/sashman/app_optex)  - AppOptics API 客户端. 将指标和标签发送到 AppOptics 时间序列服务.
* [appsignal-elixir](https://github.com/appsignal/appsignal-elixir/) - 从您的 Elixir 应用程序收集错误和性能数据并将其发送到 [AppSignal](https://appsignal.com/).
* [elixometer](https://github.com/pinterest/elixometer) - exometer 周围有一个轻的 Elixir 包装.
* [erlang-metrics](https://github.com/benoitc/erlang-metrics) - Erlang 中不同度量系统的通用接口.
* [exometer](https://github.com/Feuerlabs/exometer) - Erlang 中的基本测量对象和探针行为.
* [folsom_ddb](https://github.com/dalmatinerdb/folsom_ddb) - 用于存储 folsom 指标的 DalmatinerDB 后端.
* [graphitex](https://github.com/msoedov/graphitex) - Elixir 的石墨/碳客户端.
* [instream](https://github.com/mneudert/instream) - Elixir 的 InfluxDB 驱动程序.
* [instrumental](https://github.com/undeadlabs/instrumental-ex) - Elixir 客户端 [Instrumental](https://instrumentalapp.com/).
* [newrelic.ex](https://github.com/romul/newrelic.ex) - 从您的 Elixir/Phoenix 应用程序收集指标并将它们发送到 [NewRelic](https://newrelic.com/).
* [prometheus](https://github.com/deadtrickster/prometheus.erl) - [Prometheus.io](https://prometheus.io) Erlang中的监控系统和时间序列数据库客户端.
* [prometheus-ecto](https://github.com/deadtrickster/prometheus-ecto) - 这是 prometheus.ex 的工具.
* [prometheus-phoenix](https://github.com/deadtrickster/prometheus-phoenix) - prometheus.ex 的 Phoenix 仪器.
* [prometheus-plugs](https://github.com/deadtrickster/prometheus-plugs) - 为 prometheus.ex 插入仪器/导出器.
* [prometheus.ex](https://github.com/deadtrickster/prometheus.ex) - 对长生不老药友好 [Prometheus.io](https://prometheus.io) 监控系统和时间序列数据库客户端.
* [prometheus_process_collector](https://github.com/deadtrickster/prometheus_process_collector) - Prometheus 收集器，它导出进程指标的当前状态，包括 cpu、内存、文件描述符使用和本机线程数以及进程启动和运行时间.
* [prom_ex](https://github.com/akoutmos/prom_ex) - 适用于所有您喜爱的 Elixir 库的 Prometheus 指标和 Grafana 仪表板.
* [spandex](https://github.com/spandex-project/spandex) - 最初为 Datadog APM 开发的平台无关跟踪库.
* [telemetry](https://github.com/beam-telemetry/telemetry) - 指标和仪表的动态调度库.
* [wobserver](https://github.com/shinyscorpion/wobserver) - 基于 Web 的指标、监控和观察者.

## JSON
*使用 JSON 的库和实现.*

* [exjson](https://github.com/guedes/exjson) - Elixir 中的 JSON 解析器和生成器.
* [ja_serializer](https://github.com/AgilionApps/ja_serializer) - JSONAPI.org Elixir 中的序列化.
* [jason](https://github.com/michalmuskala/jason) - 纯 Elixir 中超快的 JSON 解析器和生成器.
* [jazz](https://github.com/meh/jazz) - 在 Elixir 中处理 JSON 的另一个库.
* [joken](https://github.com/bryanjos/joken) - 编码和解码 JSON Web 令牌.
* [jose](https://github.com/potatosalad/erlang-jose) - Erlang 和 Elixir 的 JSON 对象签名和加密 (JOSE).
* [json](https://github.com/cblage/elixir-json) - Elixir 的原生 JSON 库.
* [json_pointer](https://github.com/xavier/json_pointer) - RFC 6901 的实现，它定义了用于识别 JSON 文档中特定值的字符串语法.
* [json_stream_encoder](https://github.com/TreyE/json_stream_encoder) - JsonStreamEncoder 是一个流式编码器，用于将 JSON 流式传输到 Elixir 中的 IOish 事物.
* [json_web_token_ex](https://github.com/garyf/json_web_token_ex) - JSON Web Token (JWT) Standards Track (RFC 7519) 的 Elixir 实现.
* [jsonapi](https://github.com/jeregrine/jsonapi) - 将您的数据模型呈现为的项目 [JSONAPI Documents](http://jsonapi.org/format/).
* [jsonc](https://github.com/massivefermion/jsonc) - 使用的实用程序 [jsonc](https://komkom.github.io/jsonc-playground), json 的超集.
* [jsx](https://github.com/talentdeficit/jsx) - 用于消费、生产和操作 json 的 Erlang 应用程序.
* [jsxn](https://github.com/talentdeficit/jsxn) - jsx 但带有地图.
* [jwalk](https://github.com/jr0senblum/jwalk) - 用于处理 JSON 的 Erlang 表示的辅助模块.
* [jwtex](https://github.com/mschae/jwtex) - 一个编码和解码的库 [JWT tokens](http://jwt.io/).
* [poison](https://github.com/devinus/poison) - Poison 是 Elixir 的新 JSON 库，专注于极快的速度，而不牺牲简单性、完整性或正确性.
* [tiny](https://github.com/whitfin/tiny) - 用于 Elixir 的小巧、快速且完全兼容的 JSON 解析器.
* [world_json](https://github.com/camshaft/world_json_ex) - 用于 elixir/erlang 的 topojson 国家和州/省集合.

## Languages
*建立在 Elixir 之上的语言.*

* [Elchemy](https://github.com/wende/elchemy) - 允许将 Elm 编程语言代码翻译成 Elixir 的编译器.
* [lighthouse_scheme](https://github.com/jwhiteman/lighthouse-scheme) - 一种类似 Lisp 的小型语言和交互式 REPL，内置于 Elixir.
* [Monkey](https://github.com/fabrik42/writing_an_interpreter_in_elixir) - 类似 js 的 Monkey 编程语言的解释器和 REPL 的 Elixir 实现.

## Lexical analysis
*关于词法分析器、词法分析器、扫描器、标记器或编译器.*

* [abnf_parsec](https://github.com/princemaple/abnf_parsec) - ABNF 输入和解析器输出.
* [ex_abnf](https://github.com/marcelog/ex_abnf) - Elixir 中 ABNF 语法的解析器.
* [lex_luthor](https://github.com/jamesotron/lex_luthor) - LexLuthor is a Lexer in Elixir which uses macros to generate a reusable lexers.

## Logging
*记录信息和消息.*

* [bunyan](https://github.com/bunyan-logger/bunyan) - 班扬：长生不老药记录器.
* [exlager](https://github.com/khia/exlager) - 长生不老药绑定啤酒.
* [exsentry](https://github.com/appcues/exsentry) - 错误记录到 [Sentry](https://getsentry.com/).
* [gelf_logger](https://github.com/jschniper/gelf_logger) - 将生成 Graylog 扩展日志格式 (GELF) 消息的 Logger 后端.
* [honeybadger](https://github.com/honeybadger-io/honeybadger-elixir) - 错误记录到 [Honeybadger](https://www.honeybadger.io/).
* [json_logger](https://github.com/LeeroyDing/json_logger) - JSON Logger 是一个记录器后端，它以 JSON 格式输出 elixir 日志.
* [lager](https://github.com/basho/lager) - basho.com 的 Erlang/OTP 日志框架.
* [lager_logger](https://github.com/PSPDFKit-labs/lager_logger) - 一个更大的后端，将所有日志消息转发到 Elixir 的 Logger.
* [logfmt](https://github.com/jclem/logfmt-elixir) - Logfmt 是一个用于对 logfmt 风格的日志行进行编码和解码的模块.
* [logger_logstash_backend](https://github.com/marcelog/logger_logstash_backend) - Elixir Logger 的后端，它将向 Logstash UDP 输入发送日志.
* [logglix](https://github.com/pragmaticivan/logglix) - 用于将错误发布到 Loggly 的记录器后端.
* [logster](https://github.com/navinpeiris/logster) - 受 Lograge 启发，用于 Phoenix 和 Plug 应用程序的易于解析的单行日志记录.
* [metrix](https://github.com/rwdaigle/metrix) - 将自定义应用程序指标记录到标准输出，供 Librato 和其他下游处理器使用.
* [mstore](https://github.com/dalmatinerdb/mstore) - MStore 是一个在 erlang 中构建的实验性度量存储，主要功能是 open、new、get 和 put.
* [quiet_logger](https://github.com/Driftrock/quiet_logger/pull/1) - 一个抑制健康检查日志的简单插件（例如：使用 Kubernetes 时）.
* [rogger](https://github.com/duartejc/rogger) - Elixir 记录器在 RabbitMQ 中发布日志消息.
* [rollbax](https://github.com/elixir-addicts/rollbax) - 异常跟踪和记录到 [Rollbar](https://rollbar.com/).
* [slack_logger_backend](https://github.com/craigp/slack_logger_backend) - 用于将错误发布到 Slack 的记录器后端.
* [syslog](https://github.com/Vagabond/erlang-syslog) - Erlang 端口驱动程序，用于通过 syslog(3) 与 syslog 交互.
* [timber](https://github.com/timberio/timber-elixir)  - 结构化日志平台； 将原始文本日志转换为丰富的结构化事件.
* [youtrack_logger_backend](https://github.com/unifysell/youtrack_logger_backend) - 将消息发布到的记录器后端 [YouTrack](https://www.jetbrains.com/youtrack/) （由 JetBrains 制作的问题跟踪器）.

## Macros
 *用于更快和更轻松开发的宏. 为您的代码加糖.*

* [anaphora](https://github.com/sviridov/anaphora-elixir)  - 照应是 Elixir 的照应宏集合. 照应宏是一种故意从提供给宏的表单中捕获变量（通常是它）的宏.
* [apix](https://github.com/liveforeverx/apix) - 简单的约定和 DSL，用于将 elixir 函数转换为 API 以供以后的文档和/或验证.
* [backports](https://github.com/leifg/backports) - 使用 Elixir 1.1 和 1.2 中的新功能.
* [crudry](https://github.com/gabrielpra1/crudry) - Crudry 是用于干燥 Phoenix Contexts 和 Absinthe Resolvers 的 CRUD 的长生不老药库.
* [eventsourced](https://github.com/slashdotdash/eventsourced) - 构建功能性、事件来源的领域模型.
* [expat](https://github.com/vic/expat) - 跨 Elixir 库的可重用、可组合模式.
* [guardsafe](https://github.com/DevL/guardsafe) - 宏扩展为可以在保护子句中安全使用的代码.
* [kwfuns](https://github.com/RobertDober/lab42_defkw) - 使用基于语法的关键字参数和默认值创建函数的宏.
* [lineo](https://github.com/camshaft/lineo) - 解析转换以获得准确的行号.
* [mdef](https://github.com/pragdave/mdef) - 在 Elixir 中轻松定义多个函数头.
* [named_args](https://github.com/mgwidmann/named_args) - 允许在 Elixir 中命名 arg 样式参数.
* [ok_jose](https://github.com/vic/ok_jose) - 匹配 `{:ok,_}`、`{:error,_}` 元组或自定义模式的管道 elixir 函数.
* [opus](https://github.com/zorbash/opus) - 可插拔业务逻辑组件的框架.
* [pathex](https://github.com/hissssst/pathex) - 零依赖，超快的功能镜头.
* [pattern_tap](https://github.com/mgwidmann/elixir-pattern_tap) - 使用管道运算符时使用模式匹配的宏.
* [pipe_here](https://github.com/vic/pipe_here) - 轻松地将值通过管道传递到任何参数位置.
* [pipe_to](https://github.com/taiansu/pipe_to) - 增强的管道操作符，可以指定目标位置.
* [pipes](https://github.com/batate/elixir-pipes) - 使用 Elixir Pipe 操作符进行更灵活组合的宏.
* [pit](https://github.com/vic/pit) - 在管道内流动时转换值.
* [rebind](https://github.com/camshaft/rebind) - 重新绑定 Erlang 的解析转换.
* [rulex](https://github.com/awetzel/rulex) - 使用 Elixir 模式匹配的简单规则处理程序.
* [shorter_maps](https://github.com/meyercm/shorter_maps)  - ~M 印记为地图速记.  `~M{id name} ~&gt; %{id: id, name: name}`.
* [typed_struct](https://github.com/ejpcmac/typed_struct) - 一个 Elixir 库，用于在不编写样板代码的情况下定义具有类型的结构.
* [unsafe](https://github.com/whitfin/unsafe) - 为 Elixir 函数生成简单的不安全 (!) 绑定.

## Markdown
*使用 Markdown 等的库和工具.*

* [cmark](https://github.com/asaaki/cmark.ex) - CommonMark 的 Elixir NIF（C 语言），一个遵循 CommonMark 规范的解析器.
* [discount](https://github.com/asaaki/discount.ex) - Elixir NIF 折扣，一个 Markdown 解析器.
* [earmark](https://github.com/pragdave/earmark) - Elixir 的 Markdown 解析器.
* [Markdown](https://github.com/devinus/markdown) - 完全实现为与 Hoedown 库的 NIF 绑定.
* [Pandex](https://github.com/filterkaapi/pandex)  - Pandoc 的轻量级 Elixir 包装器. 将 Markdown、CommonMark、HTML、Latex、HTML、HTML5、opendocument、rtf、texttile、asciidoc 相互转换.

## Miscellaneous
*不属于上述类别的有用库或工具.*

* [address_us](https://github.com/smashedtoatoms/address_us) - 用于将美国地址解析为各个部分的库.
* [AlloyCI](https://github.com/AlloyCI/alloy_ci) - AlloyCI 是用 Elixir 编写的持续集成、部署和交付协调器，它利用 GitLab CI Runner 及其作为执行器的能力来准备和运行您的管道.
* [Apex](https://github.com/bjro/apex) - Elixir 的精美印刷品.
* [AtomVM](https://github.com/bettio/AtomVM) - AtomVM 允许在嵌入式设备上运行 Elixir/Erlang 代码，例如 ESP32 和 STM32 微控制器.
* [bupe](https://github.com/milmazz/bupe) - EPUB 生成器和解析器.
* [charm](https://github.com/tomgco/elixir-charm) - 使用 ANSI 终端字符来书写颜色和光标位置.
* [codec-beam](https://github.com/hkgumbs/codec-beam) - 从 Haskell 生成 Erlang VM 字节码.
* [Countries](https://github.com/SebastianSzturo/countries) - 国家/地区是 ISO 3166 标准中每个国家/地区的各种有用信息的集合.
* [countriex](https://github.com/navinpeiris/countriex) - 一个纯粹的 Elixir 国家数据提供者，包含 ISO 3166 中每个国家的各种信息.
* [cubdb](https://github.com/lucaong/cubdb)  - CubDB 是一个嵌入式键值数据库，用 Elixir 语言编写. 它在本地运行，它是无模式的，并且由单个文件支持.
* [dye](https://github.com/Kabie/dye) - 为终端输出染色的库.
* [dynamic_compile](https://github.com/okeuday/dynamic_compile) - 从字符串输入编译和加载 Erlang 模块.
* [ecto_autoslug_field](https://github.com/sobolevn/ecto_autoslug_field) - 自动为您的 Ecto 模型创建 slug.
* [egaugex](https://github.com/Brightergy/egaugex) - 客户端从 egauge 设备获取和解析实时数据.
* [elixir-browser](https://github.com/tuvistavie/elixir-browser) - Elixir 的浏览器检测.
* [epub_cover_extractor](https://github.com/zelazna/epub_cover_extractor) - 从 EPUB 文件中提取封面.
* [erlang_term](https://github.com/okeuday/erlang_term) - 提供 Erlang 术语的内存大小，忽略它们的存储位置.
* [ex2ms](https://github.com/ericmj/ex2ms) - 翻译 Elixir 函数以匹配与 `ets` 一起使用的规范.
* [ex_phone_number](https://github.com/socialpaymentsbv/ex_phone_number) - 格式化、规范化和验证电话号码.
* [ex_rated](https://github.com/grempe/ex_rated) - API 或任何东西的简单灵活的速率限制.
* [exfcm](https://github.com/Hajto/ExFCM) - 用于发布 Firebase 云消息的简单包装器.
* [exldap](https://github.com/jmerriweather/exldap) - Elixir 中用于处理 LDAP 的模块.
* [exlibris](https://github.com/pragdave/exlibris) - 随机库函数的集合.
* [expool](https://github.com/whitfin/expool) - Elixir 中用于并行任务的小型进程池库.
* [exprint](https://github.com/parroty/exprintf) - Elixir 的 printf / sprintf 库，用作 :io.format 的包装器.
* [expyplot](https://github.com/MaxStrange/expyplot) - 使用 matplotlib.pyplot 的绘图/图形库的 Elixir 接口.
* [exquisite](https://github.com/meh/exquisite) - Elixir 的类似 LINQ 的 match_spec 生成.
* [exsync](https://github.com/falood/exsync) - 又一个 Elixir 重装机.
* [funnel](https://github.com/chatgris/funnel) - 基于 ElasticSearch 的渗透构建的流式 Elixir API.
* [gen_task](https://github.com/Nebo15/gen_task) - 通用任务行为，有助于封装工作人员错误并在经典 GenStage 中从中恢复.
* [gimei_ex](https://github.com/ma2gedev/gimei_ex) - 吉美图书馆长生不老药港.
* [growl](https://github.com/zachallett/growl) - 用于咆哮的简单包装器，OSX 的通知系统.
* [hammer](https://github.com/ExHammer/hammer) - 具有可插拔存储后端的限速器，包括 Redis.
* [html_entities](https://github.com/martinsvalin/html_entities) - Elixir 模块，用于解码字符串中的 HTML 实体.
* [huex](https://github.com/xavier/huex) - 飞利浦 Hue 连接灯泡的 Elixir 客户端.
* [indicado](https://github.com/thisiscetin/indicado) - Elixir 的技术指标库，没有依赖项.
* [japan_municipality_key](https://github.com/hykw/japan_municipality_key) - 日本市政当局密钥转换的 Elixir 图书馆.
* [Jisho-Elixir](https://github.com/nbw/jisho_elixir)  - 在线日语词典 Jisho.org 的 API 包装器. 允许用户按单词、符号和或标签进行搜索（请参阅文档）.
* [keys1value](https://github.com/okeuday/keys1value) - Erlang 为键列表设置关联映射.
* [licensir](https://github.com/unnawut/licensir) - 一个混合任务，列出项目中所有已安装包的许可证.
* [mixgraph](https://github.com/sivsushruth/mixgraph) - 用于 Hex 包的交互式依赖绘图仪.
* [mixstar](https://github.com/ma2gedev/mix-star) - MixStar 加星标的 GitHub 存储库，取决于您的项目.
* [netrc](https://github.com/ma2gedev/netrcex) - 读取在 Elixir 中实现的 netrc 文件.
* [notifier](https://hex.pm/packages/notifier) - 用于桌面通知的可插拔架构.
* [onetime](https://github.com/ryo33/onetime-elixir) - Elixir 的一次性键值存储.
* [pact](https://github.com/BlakeWilliams/pact) - Elixir 中更好的依赖注入，用于更简洁的代码和测试.
* [phone](https://github.com/fcevado/phone) - 从电话号码中获取有用信息的解析器.
* [porcelain](https://github.com/alco/porcelain) - Porcelain 实现了一种更明智的方法来启动 Elixir 的外部操作系统进程并与之通信.
* [presentex](https://github.com/Cobenian/Presentex) - Elixir 到基于 HTML/JavaScript 的演示框架.
* [quarantine](https://github.com/leorog/quarantine) - Quarantine 是一个用于功能切换的小型 OTP 应用程序.
* [ratekeeper](https://github.com/whitered/ratekeeper) - 速率限制器和速率限制动作调度器.
* [ratx](https://github.com/liveforeverx/ratx) - erlang 应用的速率限制器和过载保护.
* [reprise](https://github.com/herenowcoder/reprise) - Elixir 的简化模块重新加载器.
* [spawndir](https://github.com/jtmoulia/spawndir) - 从文件系统生成进程.
* [spotify_ex](https://github.com/jsncmgs1/spotify_ex) - Spotify Web API 的 Elixir 包装器.
* [std_json_io](https://github.com/hassox/std_json_io) - 通过 JSON 管理和与 IO 服务器通信的应用程序.
* [url_unroller](https://github.com/semanticart/url_unroller) - Elixir 中的简单 URL 展开器（取消缩短器）.
* [vessel](https://github.com/whitfin/vessel) - Elixir MapReduce 接口与 Hadoop 流集成.

## Native Implemented Functions
*使用 Erlang NIF 的工具和库.*

* [hsnif](https://github.com/urbanserj/hsnif) - 允许在 Haskell 中编写 Erlang NIF 库的工具.
* [nifty](https://github.com/rossjones/nifty) - 用于设置编写 NIF 时所需的样板的帮助脚本.
* [Rustler](https://github.com/hansihe/Rustler)  - 用于在 Rust 中安全地为 Erlang 或 Elixir 编写 NIF 的库. 没有段错误.

## Natural Language Processing (NLP)
*Tools and libraries that work with human (natural) languages.*

* [gibran](https://github.com/abitdodgy/gibran) - Gibran 是 Elixir 的港口 [WordsCounted](https://github.com/abitdodgy/words_counted)，一种从文本中提取有用统计信息的自然语言处理器.
* [Paasaa](https://github.com/minibikini/paasaa) - Elixir 的自然语言检测.
* [Petrovich](https://github.com/petrovich/petrovich_elixir) - 长生不老药库，用于改变俄语的名字、姓氏和中间名.
* [Tongue](https://github.com/dannote/tongue) - Nakatani Shuyo 的自然语言检测器的 Elixir 端口.
* [Woolly](https://github.com/pjhampton/woolly) - Woolly 是一个雄心勃勃的 Elixir 文本挖掘和自然语言处理 API.

## Networking
*用于使用网络相关内容的库和工具.*

* [asn](https://github.com/ephe-meral/asn) - 可用于从 IP 映射到 AS 到 ASN.
* [chatter](https://github.com/dbeck/chatter_ex) - 基于 UDP 多播和 TCP 混合的安全消息广播.
* [download](https://github.com/asiniy/download) - 轻松从互联网下载文件.
* [eio](https://github.com/falood/eio) - engine.io 的 Elixir 服务器.
* [ExPcap](https://github.com/cobenian/expcap) - 用 Elixir 编写的 PCAP 解析器.
* [Firezone](https://github.com/firezone/firezone)  - 基于 WireGuard 的 Linux 开源 VPN 服务器和出口防火墙.  Firezone 易于设置（所有依赖项都通过 Chef Omnibus 捆绑）、安全、高性能和自托管.
* [FlyingDdns](https://gitlab.com/timopallach/FlyingDdns) - 用 elixir 编写的 dyndns 服务器.
* [hades](https://github.com/fklement/hades) - 用 Elixir 编写的 NMAP 包装器.
* [mac](https://github.com/ephe-meral/mac) - 可用于查找以十六进制字符串（根据 IEEE）给出的 MAC 的供应商.
* [pool](https://github.com/slogsdon/pool) - Elixir 的套接字接受器池.
* [reagent](https://github.com/meh/reagent) - 试剂是 Elixir 的套接字接受池.
* [sise](https://github.com/aytchell/sise) - 一个简单易用的 SSDP 客户端.
* [sockerl](https://github.com/Pouriya-Jahanbakhsh/sockerl) - Sockerl 是用于 TCP 协议的高级 Erlang/Elixir 套接字库，并为实现服务器、客户端和客户端连接池提供快速、有用且易于使用的 API.
* [socket](https://github.com/meh/elixir-socket) - Elixir 的套接字包装.
* [sshex](https://github.com/rubencaro/sshex) - Elixir 的简单 SSH 助手.
* [sshkit](https://github.com/bitcrowd/sshkit.ex) - 一个 Elixir 工具包，用于在一个或多个服务器上执行任务，构建在 Erlang 的 SSH 应用程序之上.
* [torex](https://github.com/alexfilatov/torex) - 简单的 Tor 连接库.
* [tunnerl](https://github.com/surik/tunnerl) - SOCKS4 和 SOCKS5 代理服务器.
* [wifi](https://github.com/gausby/wifi) - 在 Elixir 中使用本地 Wifi 网络的各种实用程序功能.
* [wpa_supplicant](https://github.com/fhunleth/wpa_supplicant.ex) - wpa_supplicant 的 Elixir 接口.

## Office
*用于处理办公套件文档的库.*

* [elixlsx](https://github.com/xou/elixlsx) - XLSX 文件的编写器.
* [excellent](https://github.com/leifg/excellent) - Elixir 的 OpenXL (Excel 2000) 解析器.
* [xlsxir](https://github.com/kennellroxco/xlsxir)  - Xlsx 文件解析器，支持 ISO 8601 日期格式. 数据被提取到 Erlang Term Storage (ETS) 表中，并通过各种功能进行访问.

## ORM and Datamapping
*实现对象关系映射或数据映射技术的库.*

* [amnesia](https://github.com/meh/amnesia) - Elixir 的 Mnesia 包装器.
* [arbor](https://github.com/coryodaniel/arbor) - Ecto 邻接表和树遍历.
* [arc_ecto](https://github.com/stavro/arc_ecto) - Arc.Ecto 提供与 Arc 和 Ecto 的集成.
* [atlas](https://github.com/chrismccord/atlas) - Elixir 的对象关系映射器.
* [barrel_ex](https://github.com/jxub/barrel_ex) - [Barrel-db](https://barrel-db.org/) Elixir 中的分布式面向文档的数据库 REST 客户端.
* [Bolt.Sips](https://github.com/florinpatrascu/bolt_sips) - 使用 Bolt 协议的 Elixir 的 Neo4j 驱动程序.
* [boltun](https://github.com/bitgamma/boltun) - 将来自 Postgres LISTEN/NOTIFY 机制的通知转换为回调执行.
* [caylir](https://github.com/mneudert/caylir) - Elixir 的 Cayley 驱动程序.
* [comeonin_ecto_password](https://github.com/vic/comeonin_ecto_password) - 使用 Comeonin 存储加密密码的 Ecto 自定义类型.
* [couchdb_connector](https://github.com/locolupo/couchdb_connector) - CouchDB 的连接器，基于 Erlang 的 JSON 文档数据库.
* [craterl](https://github.com/crate/craterl) - 用于板条箱的 Erlang 客户端.
* [database_url](https://github.com/s-m-i-t-a/database_url) - 解析数据库 URL 并返回关键字列表以用于 Ecto.
* [datomex](https://github.com/edubkendo/datomex) - 用于 Datomic REST API 的 Elixir 驱动程序.
* [ddb_client](https://github.com/dalmatinerdb/ddb_client) - DalmatinerDB 客户端.
* [defql](https://github.com/fazibear/defql) - 创建以 SQL 为主体的长生不老药函数.
* [dexts](https://github.com/meh/dexts) - Disk Elixir 术语存储，dest 包装器.
* [diver](https://github.com/novabyte/diver) - 用于 Erlang/Elixir 的 HBase 驱动程序，使用 Jinterface 和 Asynchbase Java 客户端来查询数据库.
* [dproto](https://github.com/dalmatinerdb/dproto) - 用于 DalmatinerDB 的协议.
* [dqe](https://github.com/dalmatinerdb/dqe) - DalmatinerDB 查询引擎.
* [ecto](https://github.com/elixir-ecto/ecto) - Elixir 的数据库包装器和语言集成查询.
* [ecto_cassandra](https://github.com/cafebazaar/ecto-cassandra) - 用于 Ecto 的 Cassandra DB 适配器.
* [ecto_enum](https://github.com/gjaldon/ecto_enum) - Ecto 扩展以支持模型中的枚举.
* [ecto_facade](https://github.com/azranel/ecto_facade) - Ecto 外观，允许分离对不同数据库的写入和读取.
* [ecto_factory](https://hex.pm/packages/ecto_factory) - 根据您的 ecto 模式轻松生成结构.
* [ecto_fixtures](https://github.com/DockYard/ecto_fixtures) - 使用 Ecto 的 Elixir 应用程序的固定装置.
* [ecto_lazy_float](https://github.com/joshdholtz/ecto-lazy-float) - Ecto.LazyFloat - 一个接受二进制和整数的 Ecto.Float.
* [ecto_list](https://github.com/popo63301/ecto_list) - 使用 Ecto 进行简单的有序模型管理.
* [ecto_migrate](https://github.com/xerions/ecto_migrate)  - Ecto 自动迁移库. 它允许为初始和更新迁移生成和运行迁移.
* [ecto_mnesia](https://github.com/Nebo15/ecto_mnesia) - Mnesia Erlang 术语数据库的 Ecto 适配器.
* [ecto_ordered](https://github.com/zovafit/ecto-ordered) - 订购模型的 Ecto 扩展.
* [ecto_paging](https://github.com/Nebo15/ecto_paging) - Ecto 的基于光标的分页.
* [ecto_psql_extras](https://github.com/pawurb/ecto_psql_extras) - Ecto PostgreSQL 数据库性能洞察.
* [ecto_rut](https://github.com/sheharyarn/ecto_rut) - 简单而强大的 Ecto 快捷方式，可简化和加速开发.
* [ecto_shortcuts](https://github.com/MishaConway/ecto_shortcuts) - ecto 中常用操作的快捷方式.
* [ecto_shortuuid](https://github.com/gpedic/ecto_shortuuid) - 增加了对 Ecto 类型的支持 [ShortUUIDs](https://github.com/gpedic/ex_shortuuid).
* [ecto_validation_case](https://github.com/danielberkompas/ecto_validation_case)  - 简化您的 Ecto 模型验证测试. 松散地受到应该匹配器的启发，但更简单.
* [ectophile](https://github.com/gjaldon/ectophile) - Ecto 扩展可立即支持模型中的文件上传.
* [elastic](https://github.com/radar/elastic) - HTTPotion 上的薄单板，可帮助您与 Elastic Search 对话.
* [elastix](https://github.com/werbitzky/elastix) - 一个用 Elixir 编写的简单 Elastic REST 客户端.
* [eredis](https://github.com/wooga/eredis) - Erlang Redis 客户端.
* [erlastic_search](https://github.com/tsloughter/erlastic_search) - An Erlang app for communicating with Elastic Search's rest interface.
* [esqlite](https://github.com/mmzeeman/esqlite) - 用于 sqlite 的 Erlang NIF.
* [eternal](https://github.com/whitfin/eternal) - 让您的 ETS 表永远保持活力、安全和轻松.
* [ets_map](https://github.com/antipax/ets_map) - 一个 Elixir 包，提供由 ETS 表支持的类似地图的界面（地图/访问/枚举/可收集）.
* [eventstore](https://github.com/slashdotdash/eventstore) - 一个使用 Postgres 进行持久性的 CQRS EventStore，用 Elixir 编写.
* [ex_bitcask](https://github.com/JonGretar/ExBitcask) - Basho 的 Bitcask 键/值存储的 Elixir 包装器.
* [ex_sider](https://github.com/ephe-meral/ex_sider) - Redis 数据结构的 Elixir Map/List/Set 接口（使用 Redix，但这是可配置的）.
* [exleveldb](https://github.com/skovsgaard/exleveldb) - 用于 LevelDB 的 Basho 的 eleveldb 模块的 Elixir 包装器.
* [exnumerator](https://github.com/KamilLelonek/exnumerator) - Elixir 可枚举类型定义以简单的方式与任何数据库一起使用.
* [exredis](https://github.com/artemeff/exredis) - Elixir 的 Redis 客户端.
* [exseed](https://github.com/seaneshbaugh/exseed) - 一个 Elixir 库，为通过 Ecto 播种数据库提供简单的 DSL.
* [exsolr](https://github.com/dcarneiro/exsolr) - 用 Elixir 编写的 Solr 包装器.
* [extreme](https://github.com/exponentially/extreme) - 使用 Elixir 库 [Eventstore](https://geteventstore.com) 用于聚合生成的事件 (CQRS) 的持久性.
* [exts](https://github.com/meh/exts) - Elixir 术语存储，ets 包装器.
* [github_ecto](https://github.com/wojtekmach/github_ecto) - GitHub API 的 Ecto 适配器.
* [gremlex](https://github.com/Revmaker/gremlex) - Apache Tinkerpop Gremlin Elixir 客户端.
* [hstore](https://github.com/senecasystems/hstore) - Hstore 支持 Postgrex.
* [inquisitor](https://github.com/dockyard/inquisitor) - Ecto 的可组合查询构建器.
* [isn](https://github.com/Frost/isn) - postgreSQL 的 Ecto 类型是扩展.
* [kalecto](https://github.com/lau/calecto) - Kalends 和 Ecto 之间的胶水用于保存日期、时间和日期时间.
* [kvs](https://github.com/synrc/kvs) - Erlang 抽象术语数据库.
* [level](https://github.com/gausby/level) - Elixir 的关卡实现了各种帮助函数和数据类型，用于与谷歌关卡数据存储一起工作.
* [mariaex](https://github.com/xerions/mariaex) - 用于 Elixir 的 MariaDB/MySQL 驱动程序.
* [memento](https://github.com/sheharyarn/memento) - Elixir 中的简单 Mnesia 界面.
* [moebius](https://github.com/robconery/moebius) - Elixir 和 PostgreSQL 的功能查询工具.
* [mongo](https://github.com/checkiz/elixir-mongo) - Elixir 的 MongoDB 驱动程序.
* [mongodb](https://github.com/ericmj/mongodb) - Elixir 的 MongoDB 驱动程序.
* [mongodb_driver](https://github.com/zookzook/elixir-mongodb-driver) - MongoDB 的替代驱动程序，支持最新版本的 MongoDB 和全面的功能列表.
* [mongodb_ecto](https://github.com/michalmuskala/mongodb_ecto) - Ecto 的 MongoDB 适配器.
* [mysql](https://github.com/mysql-otp/mysql-otp) - MySQL/OTP – Erlang/OTP 的 MySQL 驱动程序.
* [mysqlex](https://github.com/tjheeta/mysqlex) - 围绕 mysql-otp 库的 Ecto 兼容包装器.
* [neo4j_sips](https://github.com/florinpatrascu/neo4j_sips) - Elixir 的 Neo4j 驱动程序.
* [neo4j_sips_models](https://github.com/florinpatrascu/neo4j_sips_models) - Neo4j.Sips Elixir 驱动程序的简约模型支持.
* [panoramix](https://github.com/gameanalytics/panoramix) - Elixir 的 Apache Druid 客户端.
* [paper_trail](https://github.com/izelnakri/paper_trail) - Ecto plugin for tracking and recording all the changes in your database.
* [pillar](https://github.com/sofakingworld/pillar) - 基于 Clickhouse HTTP 的客户端.
* [postgrex](https://github.com/elixir-ecto/postgrex) - Elixir 的 PostgreSQL 驱动程序.
* [ravix](https://github.com/YgorCastor/ravix) - 用于 Elixir 的 RavenDB 驱动程序.
* [ravix-ecto](https://github.com/YgorCastor/ravix-ecto) - 用于 Ecto 的 RavenDB Ravix 驱动程序适配器.
* [red](https://github.com/rodrigues/red) - 以类似图形的方式在 Redis 中保持对象之间的关系.
* [rediscl](https://github.com/akdilsiz/elixir-rediscl) - 带有连接池和管道查询构建器的最小 redis 客户端.
* [redix](https://github.com/whatyouhide/redix) - 用于 Elixir 的超快、流水线、弹性 Redis 驱动程序.
* [redo](https://github.com/heroku/redo) - Heroku 的 erlang 流水线 redis 客户端.
* [rethinkdb](https://github.com/hamiltop/rethinkdb-elixir) - 使用 JSON 协议的纯 Elixir 中的 Rethinkdb 客户端.
* [riak](https://github.com/drewkerrigan/riak-elixir-client) - 一个用 Elixir 编写的 Riak 客户端.
* [riak_ecto](https://github.com/pma/riak_ecto) - Ecto 的反应适配器.
* [shards](https://github.com/cabol/shards) - 对 Erlang/Elixir ETS 表的透明和开箱即用的分片支持.
* [sql_dust](https://github.com/bettyblocks/sql_dust) - 使用神奇的 Elixir SQL 粉尘生成（复杂的）SQL 查询.
* [sqlite_ecto](https://github.com/jazzyb/sqlite_ecto) - Ecto 的 SQLite3 适配器.
* [sqlitex](https://github.com/mmmries/sqlitex)  - esqlite 周围的 Elixir 包装器. 允许访问 sqlite3 数据库.
* [ssdb_elixir](https://github.com/lidashuang/ssdb-elixir) - ssdb client for Elixir, with focus on performance.
* [tds](https://github.com/livehelpnow/tds) - 用于 Elixir 的 MSSQL / TDS 数据库驱动程序.
* [tds_ecto](https://github.com/livehelpnow/tds_ecto) - Ecto 的 MSSQL / TDS 适配器.
* [timex_ecto](https://github.com/bitwalker/timex_ecto) - 将 Timex DateTimes 与 Ecto 一起使用的适配器.
* [tirexs](https://github.com/Zatvobor/tirexs) - 一种 Elixir 风格的 DSL，用于构建对 Elasticsearch 引擎的基于 JSON 的请求.
* [triplex](https://github.com/ateliware/triplex) - 用于 Elixir 应用程序的带有 postgres 模式的数据库多租户！
* [triton](https://github.com/blitzstudios/triton) - Pure Elixir Cassandra ORM 建立在 Xandra 之上.
* [udpflux](https://github.com/timbuchwaldt/udpflux) - 一个固执己见的 InfluxDB UDP 客户端.
* [xandra](https://github.com/lexhide/xandra) - Cassandra 驱动程序在 Elixir 中原生构建，专注于速度、简单性和稳健性.
* [yar](https://github.com/dantswain/yar) - Elixir 的另一个 Redis 客户端.

## OTP
*用于处理 OTP 相关事物的库.*

* [core](https://github.com/fishcakez/core) - 用于选择性接收 OTP 进程的库.
* [erlexec](https://github.com/saleyn/erlexec) - 从 Erlang/OTP 执行和控制操作系统进程.
* [immortal](https://github.com/danielberkompas/immortal) - Immortal 是一个帮助模块的小集合，旨在使构建容错的 OTP 应用程序变得更容易.
* [libex_config](https://github.com/reset/libex-config) - 访问 OTP 应用程序配置的助手.
* [matcha](https://github.com/christhekeele/matcha) - Elixir 的一流匹配规格.

## Package Management
*用于包和依赖管理的库和工具.*

* [Hex](https://hex.pm/) - Erlang 生态系统的包管理器.
* [rebar3_hex](https://github.com/hexpm/rebar3_hex) - rebar3 的 Hex.pm 插件.

## PDF
*用于处理 PDF 文件的库和软件.*

* [chromic_pdf](https://github.com/bitcrowd/chromic_pdf) - Chrome 的 DevTools API 生成 PDF（HTML 到 PDF）的客户端.
* [gutenex](https://github.com/SenecaSystems/gutenex) - Elixir 的原生 PDF 生成.
* [pdf2htmlex](https://github.com/ricn/pdf2htmlex) - 将 PDF 文档转换为精美的 HTML 文件，而不会丢失文本或格式.
* [pdf_generator](https://github.com/gutschilla/elixir-pdf-generator) - wkhtmltopdf 或 puppeteer（HTML 到 PDF）的简单包装器，用于 Elixir 项目.
* [puppeteer_pdf](https://github.com/coletiv/puppeteer-pdf) - 在 Elixir 项目中使用的 puppeteer（HTML 到 PDF）的另一个包装器.

## Protocols
*特殊协议和格式库.*

* [borsh](https://github.com/alexfilatov/borsh) - Elixir 的实现 [BORSH](https://borsh.io) 二进制序列化器.
* [elixir_radius](https://github.com/bearice/elixir-radius) - Elixir 上的 RADIUS 协议.
* [ex_hl7](https://github.com/jcomellas/ex_hl7) - Health Level 7 (HL7) 是一种协议，旨在以电子方式对健康相关数据进行建模和传输.
* [ex_marshal](https://github.com/gaynetdinov/ex_marshal) - 在 Elixir 中实现的 Ruby Marshal 格式.
* [exprotobuf](https://github.com/bitwalker/exprotobuf) - Elixir 中的协议缓冲区，变得简单.
* [grpc-elixir](https://github.com/tony612/grpc-elixir) - gRPC 的 Elixir 实现.
* [message_pack](https://github.com/mururu/msgpack-elixir) - Elixir 的 MessagePack 实现.
* [msgpax](https://github.com/lexmag/msgpax) - Elixir 的 MessagePack (de)serializer 实现.
* [protox](https://github.com/ahamez/protox) - 协议缓冲区的 Elixir 实现.
* [riffed](https://github.com/pinterest/riffed) - 为 Apache Thrift 提供惯用的 Elixir 绑定.
* [Sippet](https://github.com/balena/elixir-sippet) - 一个 Elixir 库，旨在用作 SIP 协议中间件.
* [SMPPEX](https://github.com/savonarola/smppex) - Elixir 中的 SMPP 3.4 协议和框架实现.

## Queue
*用于处理事件和任务队列的库.*

* [adap](https://github.com/awetzel/adap) - 在您的信息系统中创建数据流，以根据 Elixir 匹配规则查询、扩充和转换数据.
* [amqp](https://github.com/pma/amqp) - 基于 Langohr 的 Erlang RabbitMQ 客户端的简单 Elixir 包装器.
* [broadway](https://github.com/dashbitco/broadway) - 使用 Elixir 进行并发和多阶段数据摄取和数据处理.
* [conduit](https://github.com/conduitframework/conduit) - 用于处理消息队列的框架，带有 SQS 和 AMQP 适配器，以及可重用消息模式的插件.
* [cspex](https://github.com/costaraphael/cspex) - CSP 通道的简单、符合 OTP 的 Elixir 实施.
* [dbus](https://github.com/aforward/sadbus) - 用于在使用 Redis 解耦的微服务之间共享数据的哑消息总线.
* [ecto_job](https://github.com/mbuhot/ecto_job) - 使用 Ecto、PostgreSQL 和 GenStage 构建的事务性作业队列.
* [elixir_nsq](https://github.com/wistia/elixir_nsq) - Elixir 的 NSQ 客户端库.
* [elixir_talk](https://github.com/jsvisa/elixir_talk) - beanstalkd 的 Elixir 客户端.
* [enm](https://github.com/basho/enm) - enm 是包装 nanomsg C 库的 Erlang 端口驱动程序.
* [exdisque](https://github.com/mosic/exdisque) - Elixir 客户端 [Disque](https://github.com/antirez/disque)，一个内存中的分布式作业队列.
* [exq](https://github.com/akira/exq) - Elixir 的作业处理库 - 与 Resque/Sidekiq 兼容.
* [exrabbit](https://github.com/d0rc/exrabbit) - 用于 Elixir 的 RabbitMQ 绑定和 DSL.
* [flume](https://github.com/scripbox/flume) - 由 GenStage 和 Redis 支持的超快作业处理系统.
* [gen_rmq](https://github.com/meltwater/gen_rmq) - 一组用于创建 RabbitMQ 消费者和发布者的行为.
* [heapq](https://github.com/takscape/elixir-heapq) - Elixir 中基于堆的优先级队列实现.
* [honeydew](https://github.com/koudelka/honeydew) - Honeydew 是 Elixir 的工人池库.
* [hulaaki](https://github.com/suvash/hulaaki) - 一个用 Elixir 编写的 MQTT 3.1.1 客户端库.
* [kaffe](https://github.com/spreedly/kaffe) - Elixir 的 Kafka 客户端库.
* [mqs](https://github.com/synrc/mqs) - RabbitMQ 客户端库、路由键、RPC over MQ 和其他东西.
* [oban](https://github.com/sorentwo/oban) - 强大的异步作业处理器，由 Elixir 和现代 PostgreSQL 提供支持.
* [faktory_worker](https://github.com/opt-elixir/faktory_worker) - 一个可以使用的 Elixir 库 [Faktory](https://contribsys.com/faktory/)，由 Sidekiq 的作者制作的多语言作业处理系统.
* [opq](https://github.com/fredwu/opq) - Elixir 中具有工作池和速率限制的简单内存队列.
* [pqueue](https://github.com/okeuday/pqueue) - Erlang 优先队列实现.
* [que](https://github.com/sheharyarn/que) - 使用 Mnesia 进行简单的后台作业处理.
* [queuex](https://github.com/falood/queuex) - 具有多个后端的优先队列.
* [RBMQ](https://github.com/Nebo15/rbmq) - 用于生成 RabbitMQ 生产者和消费者的简单 API.
* [Rihanna](https://github.com/samphilipd/rihanna) - Elixir 的高性能 postgres 支持的作业队列.
* [stream_weaver](https://hex.pm/packages/stream_weaver) - 用于处理流的库.
* [task_bunny](https://github.com/shinyscorpion/task_bunny) - 用 Elixir 编写的后台处理应用程序，并使用 RabbitMQ 作为消息传递后端.
* [toniq](https://github.com/joakimk/toniq) - Elixir 简单可靠的后台作业库.
* [verk](https://github.com/edgurgel/verk)  - Verk 是一个由 Redis 支持的作业处理系统. 它使用与 Sidekiq/Resque 相同的作业定义.
* [work_queue](https://github.com/pragdave/work_queue) - Elixir 中饥饿消费者模型的简单实现.

## QUIC
*QUIC传输层网络协议的库和工具

* [quicer](https://github.com/emqx/quic) - QUIC 协议 erlang 库.

## Release Management
*用于发布管理的库和工具.*

* [changex](https://github.com/Gazler/changex) - 从 GIT 日志自动生成变更日志.
* [distillery](https://github.com/bitwalker/distillery) - Erlang VM 的发布打包功能的纯 Elixir 实现.
* [eliver](https://github.com/glasnoster/eliver) - Elixir 包的交互式语义版本控制.
* [exrm](https://github.com/bitwalker/exrm) - 自动为您的 Elixir 项目生成一个版本.
* [exrm_deb](https://github.com/johnhamelink/exrm_deb) - 轻松为您的 Elixir 版本创建一个 deb.
* [exrm_heroku](https://github.com/epsanchezma/exrm-heroku) - 轻松地将您的 Elixir 版本发布到 Heroku.
* [exrm_rpm](https://github.com/smpallen99/exrm-rpm) - 轻松为您的 Elixir 版本创建 RPM.
* [mix_docker](https://github.com/Recruitee/mix_docker) - 将您的 Elixir 应用程序生产版本放入最小的 docker 映像中.
* [relex](https://github.com/yrashk/relex) - Erlang/Elixir 发布汇编器.
* [renew](https://github.com/Nebo15/renew) - 混合任务以创建构建到 Docker 容器中的混合项目.
* [versioce](https://github.com/mpanarin/versioce) - 为您的混合项目生成可扩展的版本碰撞和变更日志

## REST and API
*用于开发 REST-ful API 的库和 Web 工具.*

* [accent](https://github.com/sticksnleaves/accent) - 用于处理将 JSON API 密钥转换为不同情况的插件.
* [detergent](https://github.com/devinus/detergent) - 一个乳化 Erlang SOAP 库.
* [detergentex](https://github.com/r-icarus/detergentex) - Elixir 绑定到用于调用 WSDL/SOAP 服务的 Detergent erlang 库.
* [maru](https://github.com/falood/maru) - 葡萄的 Elixir 副本，用于创建类似 REST 的 API.
* [mazurka](https://github.com/exstruct/mazurka) - 超媒体 API 工具包.
* [plug_rest](https://github.com/christopheradams/plug_rest) - 用于超媒体 Web 应用程序的 REST 行为和插件路由器.
* [signaturex](https://github.com/edgurgel/signaturex) - 简单的基于密钥/秘密的 API 身份验证.
* [SOAP client](https://github.com/elixir-soap/soap) - 基于 HTTPoison 的十六进制 SOAP 客户端.
* [urna](https://github.com/meh/urna) - Urna 是一个围绕 cauldron 的简单 DSL，用于实现 REST 服务.
* [versionary](https://github.com/sticksnleaves/versionary) - Elixir Plug 和 Phoenix 的 API 版本控制.

## Search
*与搜索索引、搜索算法和搜索客户端相关的库.*

* [elasticsearch](https://github.com/infinitered/elasticsearch-elixir) - Elixir 的简单、严肃的 Elasticsearch 库.
* [elasticsearch_elixir_bulk_processor](https://github.com/sashman/elasticsearch_elixir_bulk_processor) - 一种高效灵活的方式插入 Elasticsearch.
* [giza_sphinxsearch](https://github.com/Tyler-pierce/giza_sphinxsearch) - 狮身人面像搜索客户端与 Manticore 兼容.
* [elasticlunr](https://github.com/heywhy/ex_elasticlunr) - 在 Elixir 环境中使用的小型全文搜索库.

## Security
*有关安全性的库和工具.*

* [ca](https://github.com/synrc/ca) - 证书颁发机构.
* [clamxir](https://github.com/ramortegui/clamxir) - 长生不老药的 ClamAV 包装器.
* [code_signing](https://github.com/benknowles/code_signing) - 使用 Ed25519 签名对 BEAM 文件进行签名和验证.
* [Ockam](https://github.com/ockam-network/ockam) - 一套工具、编程库和基础设施，可以轻松构建与云服务和其他设备进行安全、私密和可信通信的设备. [Docs](https://www.ockam.io/learn/concepts/) .
* [pwned](https://github.com/thiamsantos/pwned) - 检查您的密码是否已被盗用.
* [safetybox](https://github.com/aforward/safetybox) - Elixir 的面向安全的辅助函数.
* [sobelow](https://github.com/nccgroup/sobelow) - Phoenix 框架的以安全为中心的静态分析.
* [ssl_verify_fun](https://github.com/deadtrickster/ssl_verify_fun.erl) - Erlang 的 ssl 验证功能集合.

## SMS
*SMS 相关的库和工具.*

* [exsms](https://hex.pm/packages/exsms) - 用于发送交易 SMS 的 Elixir 库 - 支持 Sendinblue、mailjet、msg91 和 textlocal.

## Static Page Generation

* [blogit](https://github.com/meddle0x53/blogit) - 用于从包含降价文件的 git 存储库生成博客的 OTP 应用程序.
* [glayu](https://github.com/pablomartinezalvarez/glayu) - 用于中型站点的静态站点生成器.
* [medusa](https://github.com/Vesuvium/medusa) - 支持 Pug 的 Elixir 静态站点生成器.
* [obelisk](https://github.com/BennyHallett/obelisk) - 静态博客和网站生成器.
* [serum](https://github.com/Dalgona/Serum) - 一个用 Elixir 编写的简单静态网站生成器.

## Statistics
*围绕主题统计的图书馆.*

* [descriptive_statistics](https://github.com/pusewicz/descriptive_statistics) - Elixir 的描述性统计数据.
* [mtx](https://github.com/synrc/mtx) - MTX 支持前端 API 用于跟踪 Histogram、Meter、Counter、Gauge、Timing 键.
* [numerix](https://github.com/safwank/Numerix) - 一组有用的数学函数，倾向于统计、线性代数和机器学习.
* [simple_stat_ex](https://github.com/Tyler-pierce/simplestatex) - Ecto 兼容库，用于按时间段进行简单的统计保存.
* [statistics](https://github.com/msharp/elixir-statistics) - Elixir 的一些基本统计功能.

## Templating
*库解析和模板帮助*

* [bbmustache](https://github.com/soranoba/bbmustache) - Erlang/OTP 的基于二进制模式匹配的 Mustache 模板引擎.
* [calliope](https://github.com/nurugger07/calliope) - Elixir HAML 解析器.
* [eml](https://github.com/zambal/eml) - 在 Elixir 中编写和操作 (HTML) 标记的库.
* [exgen](https://github.com/rwdaigle/exgen) - 用于快速生成 Elixir 项目的模板库.
* [expug](https://github.com/rstacruz/expug) - Elixir 的哈巴狗模板.
* [mustache](https://github.com/schultyy/Mustache.ex) - Elixir 的胡子模板.
* [mustachex](https://github.com/jui/mustachex) - Elixir 的 Mustache - 无逻辑模板.
* [slime](https://github.com/slime-lang/slime) - 一个 Elixir 库，用于渲染类似苗条的模板.
* [taggart](https://github.com/ijcd/taggart) - HTML 作为 Elixir 中的代码.
* [templates](https://github.com/sugar-framework/templates) - 用于将模板添加到 Web 应用程序的帮助库.
* [temple](https://github.com/mhanberg/temple) - Elixir 和 Phoenix 的 HTML DSL.

## Testing
*用于测试代码库和生成测试数据的库.*

* [amrita](https://github.com/josephwilk/amrita) - Elixir 的礼貌、彬彬有礼和彻底正直的测试框架.
* [apocryphal](https://github.com/coryodaniel/apocryphal) - ExUnit 基于 Swagger 的文档驱动开发.
* [blacksmith](https://github.com/batate/blacksmith) - Elixir 的数据生成框架.
* [blitzy](https://github.com/benjamintanweihao/blitzy) - Elixir 中的一个简单的 HTTP 负载测试器.
* [bypass](https://github.com/pspdfkit-labs/bypass) - Bypass 提供了一种使用自定义插件创建模拟 HTTP 服务器的快速方法.
* [chaperon](https://github.com/polleverywhere/chaperon) - 用 Elixir 编写的 HTTP 服务性能和负载测试框架.
* [chemistry](https://github.com/genericlady/chemistry) - Elixir 的测试框架.
* [cobertura_cover](https://github.com/PSPDFKit-labs/cobertura_cover) - 从与 Jenkins 的 Cobertura 插件兼容的 `mix test --cover` 文件中写入 coverage.xml.
* [definject](https://github.com/definject/definject) - Unobtrusive dependency injector for Elixir.
* [double](https://github.com/sonerdy/double) - 在不覆盖全局模块的情况下创建用于测试的存根依赖项.
* [dummy](https://github.com/Vesuvium/dummy) - 一个 Elixir 模拟库，通过以正确的方式暴露 meck 是有意义 
* [ecto_it](https://github.com/xerions/ecto_it) - 具有默认配置的 Ecto 插件，用于使用数据库测试不同的 ecto 插件.
* [efrisby](https://github.com/FabioBatSilva/efrisby) - Erlang 的 REST API 测试框架.
* [elixir-auto-test](https://github.com/joaothallis/elixir-auto-test) - Run test when file is saved using inotify-tools.
* [espec](https://github.com/antonmi/espec) - 受 RSpec 启发的 Elixir 的 BDD 测试框架.
* [espec_phoenix](https://github.com/antonmi/espec_phoenix) - Phoenix Web 框架的 ESpec.
* [ex_machina](https://github.com/thoughtbot/ex_machina)  - Elixir 的灵活测试工厂. 与 Ecto 和 Ecto 关联开箱即用.
* [ex_parameterized](https://github.com/KazuCocoa/ex_parameterized) - 用于参数化测试的简单宏.
* [ex_spec](https://github.com/drewolson/ex_spec) - ExUnit 的类似 BDD 的语法.
* [ex_unit_fixtures](https://github.com/obmarg/ex_unit_fixtures) - 用于定义 ExUnit 测试的模块化依赖项的库.
* [ex_unit_notifier](https://github.com/navinpeiris/ex_unit_notifier) - ExUnit 的桌面通知.
* [excheck](https://github.com/parroty/excheck) - Elixir 的基于属性的测试库（QuickCheck 风格）.
* [exkorpion](https://github.com/wesovilabs/exkorpion) - Elixir 开发人员的 BDD 库.
* [factory_girl_elixir](https://github.com/sinetris/factory_girl_elixir) - Elixir 中 Ruby 的 factory_girl 的最小实现.
* [fake_server](https://github.com/bernardolins/fake_server) - FakeServer 是一个 HTTP 服务器，可以模拟响应并使测试外部 API 变得更容易.
* [faker](https://github.com/igas/faker) - Faker 是一个纯 Elixir 库，用于生成假数据.
* [faker_elixir](https://github.com/GesJeremie/faker-elixir) - FakerElixir 是一个为你生成假数据的 Elixir 软件包.
* [fqc](https://github.com/project-fifo/fqc) - FiFo Quickcheck helper，一组运行EQC的助手.
* [gimei](https://github.com/KazuCocoa/elixir-gimei) - Gimei 是一个纯 Elixir 库，用于生成日本假数据.
* [hound](https://github.com/HashNuke/hound) - Elixir 库，用于编写集成测试和浏览器自动化.
* [hypermock](https://github.com/stevegraham/hypermock) - HTTP 请求存根和期望 Elixir 库.
* [ignorant](https://github.com/campezzi/ignorant) - 部分“地图”比较，确保字段存在，同时忽略它们的值.
* [katt](https://github.com/for-GET/katt) - KATT（Klarna API 测试工具）是一个基于 HTTP 的 Erlang API 测试工具.
* [kovacs](https://github.com/antp/kovacs) - 一个简单的 ExUnit 测试运行器.
* [markdown_test](https://github.com/MainShayne233/markdown_test) - 一个库，可让您在 Markdown 文件中测试 Elixir 代码.
* [meck](https://github.com/eproxus/meck) - Erlang 的模拟库.
* [mecks_unit](https://github.com/archan937/mecks_unit) - 在（异步）ExUnit 测试中优雅地模拟模块功能的包，使用 [meck](https://github.com/eproxus/meck).
* [mix_erlang_tasks](https://github.com/alco/mix-erlang-tasks) - 使用 Mix 的 Erlang 项目的常见任务.
* [mix_eunit](https://github.com/dantswain/mix_eunit) - 执行 eunit 测试的 Mix 任务.
* [mix_test_interactive](https://github.com/influxdata/mix_test_interactive) - 交互式测试运行器，用于与手表模式混合测试.
* [mix_test_watch](https://github.com/lpil/mix-test.watch) - 每次保存文件时自动运行 Elixir 项目的测试.
* [mixunit](https://github.com/talentdeficit/mixunit) - 基于混合项目的 EUnit 任务.
* [mock](https://github.com/jjh42/mock) - Elixir 语言的模拟库.
* [mockery](https://github.com/appunite/mockery) - 用于异步测试的简单模拟库.
* [mockingbird](https://github.com/Driftrock/mockingbird) - 一组帮助程序来测试涉及 http 请求的代码.
* [mox](https://github.com/dashbitco/mox) - Elixir 的模拟和明确的合同.
* [patch](https://github.com/ihumanable/patch) - Elixir 的人体工程学模拟.
* [pavlov](https://github.com/sproutapp/pavlov) - 您的 Elixir 项目的 BDD 框架.
* [plug_test_helpers](https://github.com/xavier/plug_test_helpers) - 一个简单的插头测试 DSL.
* [ponos](https://github.com/klarna/ponos) - Ponos 是一个 Erlang 应用程序，它公开了一个灵活的负载生成器 API.
* [power_assert](https://github.com/ma2gedev/power_assert_ex)  - Elixir 中的 Power Assert. 显示每个表达式的评估结果.
* [propcheck](https://github.com/alfert/propcheck) - Elixir 的基于属性的测试.
* [proper](https://github.com/manopapad/proper) - PropEr（ERlang 基于 PROPerty 的测试工具）是一个受 QuickCheck 启发的开源基于属性的 Erlang 测试工具.
* [setup_tag](https://github.com/vic/setup_tag) - 轻松混合和匹配标有标签的功能以设置您的测试上下文.
* [shouldi](https://github.com/batate/shouldi) - 具有嵌套上下文、卓越的可读性和易用性的 Elixir 测试库.
* [test_selector](https://github.com/DefactoSoftware/test_selector) - 一组测试助手，确保您始终在 Phoenix 应用程序中选择正确的元素.
* [test_that_json](https://github.com/facto/test_that_json) - 满足您 Elixir 测试需求的 JSON 断言和助手.
* [toxiproxy_ex](https://github.com/Jcambass/toxiproxy_ex) - 弹性测试工具 Toxiproxy 的 API 客户端.
* [tuco_tuco](https://github.com/stuart/tuco_tuco) - TucoTuco 通过运行 Web 浏览器并模拟用户与您的应用程序的交互来帮助您测试您的 Web 应用程序.
* [Walkman](https://github.com/derekkraan/walkman) - 受 Ruby 的 VCR 启发，将测试与现实世界隔离开来.
* [wallaby](https://github.com/keathley/wallaby) - Wallaby 通过同时模拟用户交互和管理浏览器来帮助测试您的 Web 应用程序.
* [white_bread](https://github.com/meadsteve/white-bread) - 在 Elixir 中使用 gherkin 语法的基于故事的 BDD.

## Text and Numbers
*用于解析和操作文本和数字的库.*

* [abacus](https://github.com/narrowtux/abacus) - 评估 Elixir 中的数学术语.
* [base58](https://github.com/jrdnull/base58) - Elixir 的 Base58 编码/解码.
* [base58check](https://github.com/gjaldon/base58check) - 比特币的 Base58Check 编码/解码.
* [base62](https://github.com/igas/base62) - 纯 Elixir 中的 Base62 编码器/解码器.
* [bencode](https://github.com/gausby/bencode)  - Elixir 的 Bencode 编码器和解码器. 如果在输入中找到信息字典，解码器将返回信息字典的校验和值.
* [bencoder](https://github.com/alehander42/bencoder) - 长生不老药中的 bencode.
* [bitcoinex](https://github.com/RiverFinancial/bitcoinex) - Elixir 中的比特币实用程序.
* [brcpfcnpj](https://github.com/williamgueiros/Brcpfcnpj) - 巴西文件的数字格式和验证 (CPF/CNPJ).
* [caustic](https://github.com/agro1986/caustic)  - 用于比特币、以太坊和其他区块链的 Elixir 加密货币库. 包括密码学、数论（素数、同余）和用于探索性数学的通用数学库.
* [ccc](https://github.com/Joe-noh/ccc) - 字符代码转换器.
* [chinese_translation](https://github.com/tyrchen/chinese_translation) - Translate between traditional chinese and simplified chinese based on wikipedia data, and translate chinese words/characters to pinyin (or slug with or without tone).
* [cidr](https://github.com/c-rack/cidr-elixir) - Elixir 的无类域间路由 (CIDR).
* [cirru_parser](https://github.com/Cirru/parser.ex) -Elixir 中的 Cirru Parser.
* [colorful](https://github.com/Joe-noh/colorful) - Elixir 宏来装饰 CUI 上的字符.
* [colors](https://github.com/lidashuang/colors) - 用 Elixir 编写的颜色工具.
* [convertat](https://github.com/whatyouhide/convertat) - 一个 Elixir 库，用于从任意碱基转换到任意碱基.
* [curtail](https://github.com/seankay/curtail) - HTML 标记安全的字符串截断.
* [custom_base](https://github.com/igas/custom_base) - 允许您在 Elixir 中进行自定义基础转换.
* [decimal](https://github.com/ericmj/decimal) - Elixir 的任意精度十进制算法.
* [dicer](https://github.com/olhado/dicer) - 一个掷骰子表情评估器.
* [eden](https://github.com/jfacorro/Eden) - [EDN](https://github.com/edn-format/edn) Elixir 的编码器/解码器.
* [elixilorem](https://github.com/mgamini/elixilorem) - 用于 Elixir 的 Lorem Ipsum 生成器.
* [elixir-range-extras](https://github.com/lnikkila/elixir-range-extras) - Elixir 范围实用程序：恒定时间随机采样和集合操作.
* [elixir_bencode](https://github.com/AntonFagerberg/elixir_bencode) - 在 Elixir 中实现的 Bencode.
* [erldn](https://github.com/marianoguerra/erldn) - [EDN](https://github.com/edn-format/edn) Erlang 平台的格式解析器.
* [event_source_encoder](https://github.com/chatgris/event_source_encoder) - 将数据编码为符合 EventSource 的数据.
* [ex_brace_expansion](https://github.com/gniquil/ex_brace_expansion) - 大括号扩展，如从 sh/bash 中所知，在 Elixir 中.
* [ex_cldr](https://github.com/kipcole9/cldr) - Cldr is an Elixir library for the Unicode Consortium's Common Locale Data Repository (CLDR).
* [ex_rfc3966](https://github.com/marcelog/ex_rfc3966) - Elixir Tel URI 解析器与 RFC3966 兼容.
* [ex_rfc3986](https://github.com/marcelog/ex_rfc3986) - RFC3986 URI/URL 解析器.
* [ex_uc](https://github.com/carturoch/ex_uc) - Elixir 的可扩展单位转换器.
* [exmoji](https://github.com/mroth/exmoji) - 为 Elixir/Erlang 编码瑞士军刀的表情符号.
* [expletive](https://github.com/xavier/expletive) - Elixir 的脏话过滤器库.
* [expr](https://github.com/Rob-bie/Expr) - 用于解析和评估数学表达式的 Elixir 库.
* [faust](https://github.com/jquadrin/faust) - Elixir 的马尔可夫文本生成器.
* [haikunator](https://github.com/knrz/Haikunator) - 生成类似 Heroku 的令人难忘的随机名称，以便在您的应用程序或其他任何地方使用.
* [hashids](https://github.com/alco/hashids-elixir) - Hashids 允许您通过可逆映射混淆数字标识符.
* [hexate](https://github.com/rjsamson/hexate) - Elixir 中用于十六进制编码/解码的简单模块.
* [inet_cidr](https://github.com/cobenian/inet_cidr) - Elixir 的无类域间路由 (CIDR)，与 :inet 兼容并支持 IPv4 和 IPv6.
* [inflex](https://github.com/nurugger07/inflex) - Elixir 的 Inflector 库.
* [kitsune](https://github.com/edubkendo/kitsune) - 用于转换数据表示的 Elixir 库.
* [ltsvex](https://github.com/ma2gedev/ltsvex) - Elixir 中的 LTSV 解析器实现.
* [mbcs](https://github.com/woxtu/elixir-mbcs)  - erlang-mbcs 的包装器. 该模块提供字符编码转换的功能.
* [mimetype_parser](https://github.com/camshaft/mimetype_parser) - 解析 mimetypes.
* [minigen](https://github.com/mrdimosthenis/minigen) - Erlang 生态系统的随机数据生成器.
* [monetized](https://github.com/theocodes/monetized) - 用于处理和存储资金的轻量级解决方案.
* [money](https://github.com/liuggio/money) - 使用 Money 更安全、更轻松、更有趣，解释了 Fowler 的金钱模式.
* [mt940](https://github.com/my-flow/mt940) - Elixir 的 MT940（标准结构化 SWIFT 客户声明消息）解析器.
* [nanoid](https://github.com/railsmechanic/nanoid) - NanoID 的 Elixir 端口，一个安全且对 URL 友好的唯一 ID 生成器.
* [near_api](https://github.com/alexfilatov/near_api) - 一个 [NEAR](https://near.org) Elixir 中的 API - NEAR 区块链平台上用于 ​​DApps 开发的库.
* [neotomex](https://github.com/jtmoulia/neotomex) - 一个 [PEG](http://bford.info/packrat/) 使用愉快的 Elixir DSL 实现.
* [number](https://github.com/danielberkompas/number) - Number 是一个自命不凡的 Elixir 库，它提供了将数字转换为各种不同格式的功能.
* [numero](https://github.com/alisinabh/numero) - 一个用于在 elixir 中转换非英语 utf-8 数字的微型库.
* [palette](https://github.com/lpil/palette) - 一个方便的库，用于在 Elixir 中为字符串着色.
* [pinyin](https://github.com/lidashuang/pinyin) - Chinese Pinyin lib for Elixir.
* [porterstemmer](https://github.com/frpaulas/porterstemmer) - Elixir 中的搬运工声音.
* [pretty_hex](https://github.com/polsab/pretty_hex) - Elixir 中的二进制十六进制转储库.
* [quickrand](https://github.com/okeuday/quickrand) - 快速随机数生成.
* [RandomStringGenerator](https://github.com/caioceccon/random_string_generator) - 基于给定字符串模式生成随机字符串的模块.
* [ref_inspector](https://github.com/elixytics/ref_inspector)  - Elixir 中的引用解析器库. 从 URL 获取信息.
* [remove_emoji](https://github.com/guanting112/elixir_remove_emoji)  - Elixir 中的表情符号文本消毒器. 它可以删除任何表情符号.
* [secure_random](https://github.com/patricksrobertson/secure_random.ex) - 以我对 Ruby 的 SecureRandom 的热爱为模型的随机 base64 字符串的便利库.
* [sentient](https://github.com/dantame/sentient) - 基于 AFINN-111 词表的简单情绪分析.
* [shortuuid](https://github.com/gpedic/ex_shortuuid) - 生成简洁、明确、URL 安全的 UUID.
* [simetric](https://github.com/lexmag/simetric) - Elixir 的字符串相似度指标.
* [slugger](https://github.com/h4cc/slugger) - Slugger 可以从给定的字符串生成 slug，这些字符串可用于 URL 或文件名.
* [smile](https://github.com/danigulyas/smile) - 用于将表情符号映射器转换为表情符号字符的小库，例如在 Slack 消息中.
* [stemmer](https://github.com/fredwu/stemmer) - Elixir 中的英语 (Porter2) 词干实现.
* [tau](https://github.com/FranklinChen/tau) - 提供著名的数学常数 tau, τ = 6.2831....
* [transformer](https://github.com/ByeongUkChoi/transformer) - 灵活的类型转换轻量级库.
* [tomlex](https://github.com/zamith/tomlex) - Elixir 的 TOML 解析器.
* [ua_inspector](https://github.com/elixytics/ua_inspector) - 用户代理解析器库，如 `piwik/device-detector`.
* [ua_parser2](https://github.com/nazipov/ua_parser2-elixir)  - ua-parser2 到 Elixir 的端口. 用户代理解析器库.
* [unit_fun](https://github.com/meadsteve/unit_fun) - 尝试在 elixir 中为数字添加单位，以在处理数字数量时提供一些额外的类型安全性.
* [uuid](https://github.com/zyro/elixir-uuid) - Elixir 的 UUID 生成器和实用程序.
* [uuid_erl](https://github.com/okeuday/uuid) - Erlang Native UUID 生成.
* [veritaserum](https://github.com/uesteibar/veritaserum) - 基于 afinn-165、表情符号和一些增强功能的情绪分析.

## Third Party APIs
*用于访问第三方 API 的库.*

* [airbax](https://github.com/adjust/airbax) - 从 Elixir 到 Airbrake 的异常跟踪.
* [airbrake](https://github.com/romul/airbrake-elixir) - Airbrake 的 Elixir 通知器.
* [airbrakex](https://github.com/fazibear/airbrakex) - Airbrake 服务的 Elixir 客户端.
* [amazon_product_advertising_client](https://github.com/zachgarwood/elixir-amazon-product-advertising-client) - Elixir 的亚马逊产品广告 API 客户端.
* [apns](https://github.com/chvanikoff/apns4ex) - 用于 elixir 的 Apple 推送通知服务客户端库.
* [asanaficator](https://github.com/trenpixster/asanaficator)  - Asana API 的简单 Elixir 包装器. 基于Tentacat.
* [askimet_ex](https://github.com/mijailr/askimet_ex) - 用于 Askimet 反垃圾邮件服务的 Elixir 客户端.
* [assembla_api](https://github.com/Assembla/ex_assembla_api) - 为 Elixir 组装 API 客户端.
* [balalaika_bear](https://github.com/ayrat555/balalaika_bear) - Elixir 的简单 VK API 客户端.
* [balanced](https://github.com/bryanjos/balanced-elixir) - Elixir 的平衡 API 客户端.
* [bandwidth](https://github.com/bandwidthcom/elixir-bandwidth) - 带宽应用平台的 Elixir 客户端库.
* [bing_translator](https://github.com/ikeikeikeike/bing_translator) - Bing 翻译 API 的简单 Elixir 接口.
* [bitmex](https://github.com/nobrick/bitmex) - Elixir 的 BitMEX 客户端库.
* [bitpay](https://github.com/bitpay/elixir-client) - Elixir 核心库，用于连接 bitpay.com.
* [cashier](https://github.com/swelham/cashier) - 支付网关为多个支付提供商提供通用接口.
* [cleverbot](https://github.com/BlakeWilliams/Elixir-Cleverbot) - Elixir 中 Cleverbot API 的简单实现.
* [coinbase](https://github.com/gregpardo/coinbase-elixir) - 一个非官方的 Coinbase API v1 客户端.
* [commerce_billing](https://github.com/joshnuss/commerce_billing) - Elixir 的支付处理库，支持多个网关（例如 Bogus &amp; Stripe）.
* [conekta](https://github.com/echavezNS/conekta-elixir) - Conekta API 的 Elixir 包装器.
* [correios_cep](https://github.com/prodis/correios-cep-elixir)  - 直接从 Correios 数据库按邮政编码查找巴西地址. 没有 HTML 解析器.
* [currently](https://github.com/chatgris/currently) - 显示当前在 Trello 上分配的卡片的工具.
* [darkskyx](https://github.com/techgaun/darkskyx) - 用于 Elixir 的 Darksky.com（以前的 forecast.io）API 客户端.
* [digitalocean](https://github.com/lukeed/elixir-digitalocean) - Digital Ocean API v2 的 Elixir 包装器.
* [digoc](https://github.com/kevinmontuori/digoc) - 数字海洋 API v2 Elixir 客户端.
* [diplomat](https://github.com/peburrows/diplomat) - 一个 [Google Cloud Datastore](https://cloud.google.com/datastore/) 客户.
* [dnsimple](https://github.com/dnsimple/dnsimple-elixir) - DNSimple API v2 的 Elixir 客户端.
* [docker](https://github.com/hexedpackets/docker-elixir) - 用于 Docker 远程 API 的 Elixir 客户端.
* [dockerex](https://github.com/hisea/dockerex) - 支持 SSL/TLS 登录/连接的轻量级 Docker 远程 API 客户端.
* [dogstatsd](https://github.com/adamkittelson/dogstatsd-elixir) - Elixir 客户端 [DogStatsd](https://www.datadoghq.com/).
* [dpd_client](https://github.com/knewter/dpd_client) - DPD 服务的 API 客户端.
* [dropbox](https://github.com/ammmir/elixir-dropbox) - Elixir 的 Dropbox Core API 客户端.
* [dublin_bus_api](https://github.com/carlo-colombo/dublin-bus-api) - 访问都柏林巴士服务的实时乘客信息 (RTPI).
* [edgarex](https://github.com/rozap/edgarex) - Elixir 接口，用于从 EDGAR 获取 SEC 文件.
* [elixir_authorizenet](https://github.com/marcelog/elixir_authorizenet) - Authorize.Net 商家 API 的非官方客户端.
* [elixir_ipfs_api](https://github.com/zabirauf/elixir-ipfs-api) - Elixir 的 IPFS（星际文件系统）API 客户端.
* [elixirfm](https://github.com/jrichocean/Elixirfm) - 用于 Elixir 的 Last.fm API 包装器.
* [elixtagram](https://github.com/zensavona/elixtagram) - Elixir 的 Instagram API 客户端.
* [ethereumex](https://github.com/exthereum/ethereumex) - 以太坊区块链的 Elixir JSON-RPC 客户端.
* [everex](https://github.com/jwarlander/everex) - 用于 Elixir 的 Evernote API 客户端.
* [everyoneapi](https://github.com/knewter/everyoneapi) -EveryoneAPI.com 的 API 客户端.
* [ex_changerate](https://github.com/81dr/ex_changerate) - Elixir 客户端 [exchangerate.host](https://exchangerate.host) API.
* [ex_codeship](https://github.com/securingsincity/ex_codeship) - 用于 Codeship 的 API 客户端.
* [ex_statsd](https://github.com/CargoSense/ex_statsd) - Elixir 的 statsd 客户端实现.
* [ex_twilio](https://github.com/danielberkompas/ex_twilio) - Elixir 的 Twilio API 客户端.
* [ex_twiml](https://github.com/danielberkompas/ex_twiml) - 在 Elixir 中为您的 Twilio 集成生成 TwiML.
* [exdesk](https://github.com/deadkarma/exdesk) - Desk.com API 的 Elixir 库.
* [exfacebook](https://github.com/oivoodoo/exfacebook) - Facebook API，用 Elixir 编写，使用类似 Ruby koala gem 的方法.
* [exgenius](https://github.com/jeffweiss/exgenius) - 用于（未记录的）Rap Genius API 的 Elixir 库.
* [exgravatar](https://github.com/scrogson/exgravatar) - 用于生成 Gravatar URL 的 Elixir 模块.
* [exgrid](https://github.com/bradleyd/exgrid) - 与 Sendgrid 的 API 交互.
* [exjira](https://github.com/mattweldon/exjira) - Elixir 的 JIRA 客户端库.
* [exlingr](https://github.com/mtwtkman/exlingr) - Lingr 客户端模块.
* [explay](https://github.com/sheharyarn/explay) - Elixir 中的非官方 Google Play API.
* [exstagram](https://github.com/arthurcolle/exstagram) - Instagram v1 API 的 Elixir 库.
* [extwitter](https://github.com/parroty/extwitter) - Elixir 的 Twitter 客户端库.
* [exurban](https://github.com/oscar-lopez/exurban) - UrbanAirship API 的 Elixir 包装器.
* [facebook](https://github.com/mweibel/facebook.ex) - 用 Elixir 编写的 Facebook Graph API Wrapper.
* [feedlex](https://github.com/essenciary/feedlex) - Elixir 的 Feedly RSS 阅读器客户端.
* [fluent_client](https://github.com/trustatom-oss/elixir-fluent-client) - 简约流畅的客户端.
* [forcex](https://github.com/jeffweiss/forcex) - Force.com REST API 的 Elixir 库.
* [forecast_io](https://github.com/r-icarus/forecast_io) - Forecast.IO API 的简单包装器.
* [gcmex](https://github.com/dukex/gcmex) - 用于长生不老药的谷歌云消息客户端库.
* [google-cloud](https://github.com/GoogleCloudPlatform/elixir-google-api) - 此存储库包含与 Google API 交互的所有客户端库.
* [google_sheets](https://github.com/GrandCru/GoogleSheets) - Elixir 库，用于以 CSV 格式获取和轮询 Google 电子表格数据.
* [govtrack](https://github.com/walterbm/govtrack-elixir) - 一个简单的 Elixir 包装器 [govtrack.us](https://www.govtrack.us/developers) API.
* [gringotts](https://github.com/aviabird/gringotts) - Elixir 和 Phoenix 框架的完整支付库，类似于 [ActiveMerchant](https://github.com/activemerchant/active_merchant) 来自红宝石世界.
* [hexoku](https://github.com/JonGretar/Hexoku) - 用于 Elixir 项目的 Heroku API 客户端和 Heroku Mix 任务.
* [honeywell](https://github.com/jeffutter/honeywell-elixir) - Honeywell Lyric、Round 和 Water Leak &amp; Freeze Detector API 的客户端.
* [kane](https://github.com/peburrows/kane) - 一个 [Google Cloud Pub/Sub](https://cloud.google.com/pubsub/overview) 客户.
* [keenex](https://github.com/bryanjos/keenex) - Keen.io API 客户端.
* [link_shrinkex](https://github.com/jonahoffline/link_shrinkex) - Elixir 库，用于使用 Google 的 URL Shortener API 创建短 URL.
* [m2x](https://github.com/attm2x/m2x-elixir)  - AT&amp;T M2X 的 Elixir 客户端，这是一种基于云的完全托管的时间序列数据存储服务，用于网络连接的机器对机器 (M2M) 设备和物联网 (IoT).  ([Erlang Version](https://github.com/attm2x/m2x-erlang)).
* [mailchimp](https://github.com/duartejc/mailchimp) - MailChimp API 版本 3 的基本 Elixir 包装器.
* [mailgun](https://github.com/chrismccord/mailgun) - Elixir Mailgun 客户端.
* [mandrill](https://github.com/slogsdon/mandrill-elixir) - Elixir 的 Mandrill 包装纸.
* [marvel](https://github.com/bryanjos/marvel) - Marvel API 的 CLI 和 Elixir API 客户端.
* [mexpanel](https://github.com/blendmedia/mexpanel) - Mixpanel HTTP API 的 Elixir 客户端.
* [mixpanel](https://github.com/michihuber/mixpanel_ex) - Mixpanel HTTP API 的 Elixir 客户端.
* [mixpanel_data_client](https://github.com/jeregrine/mixpanel_data_client) - 用于与 Mixpanel 数据导出 API 交互的客户端.
* [mmExchangeRate](https://github.com/Arkar-Aung/mmExchangeRate) - 基于缅甸中央银行 Api 的简单汇率检查器和计算器.
* [nacha](https://github.com/RiverFinancial/nacha) - Elixir 库，用于为美国 ACH 转账生成和解析 NACHA 文件.
* [nadia](https://github.com/zhyu/nadia) - 用 Elixir 编写的 Telegram Bot API 包装器.
* [omise](https://github.com/teerawat1992/omise-elixir) - Elixir 的 Omise 客户端库.
* [opbeat](https://github.com/teodor-pripoae/opbeat) - Opbeat 的 Elixir 客户端.
* [pagexduty](https://github.com/ride/pagexduty) - Elixir 的 Pagerduty 客户端.
* [parse_client](https://github.com/elixircnx/parse_elixir_client) - 用于 parse.com REST API 的 Elixir 客户端.
* [parsex](https://github.com/maarek/ParsEx) - ParsEx 是一个 Elixir HTTP 客户端，用于与 Parse.com 的 Restful API 进行通信.
* [particle](https://github.com/jeffutter/particle-elixir) - 粒子物联网平台 HTTP API 的 Elixir 客户端.
* [pathway](https://github.com/novabyte/pathway) - Erlang/Elixir 客户端 [Trak.io](http://trak.io/) REST API.
* [pay](https://github.com/era/pay) - 一个 Elixir Lib 来处理 Paypal 和其他支付解决方案.
* [pay_pal](https://github.com/zensavona/paypal) - 使用 PayPal REST API 的 Elixir 库.
* [pigeon](https://github.com/codedge-llc/pigeon) - 用于发送 iOS 和 Android 推送通知的符合 HTTP2 的包装器.
* [pocketex](https://github.com/essenciary/pocketex) - Pocketex 是 Pocket 稍后阅读服务的 Elixir 客户端 [getpocket.com](https://getpocket.com/).
* [pusher](https://github.com/edgurgel/pusher) - Elixir 库，用于访问 Pusher REST API.
* [qiita_ex](https://github.com/ma2gedev/qiita_ex) - Elixir 的 Qiita API v2 接口.
* [qiniu](https://github.com/tony612/qiniu) - Elixir 的七牛 SDK.
* [random_user](https://github.com/katgironpe/random_user) - 用于 randomuser.me API 的 Elixir 客户端.
* [random_user_api](https://hex.pm/packages/random_user_api) - Another simple randomuser.me API client.
* [reap](https://github.com/Raynes/reap) - Reap 是一个简单的 Elixir 库，用于使用 refheap API.
* [reddhl](https://github.com/MonkeyIsNull/reddhl) - Reddit 及其各种 subreddit 的标题和链接提取器.
* [redtube](https://github.com/kkirsche/Redtube_Elixir) - 用 Elixir 编写的 Redtube API 包装器.
* [reporter](https://github.com/KazuCocoa/simple_app_reporter_ex)  - 记者是简单的报告应用评论库. 支持 AppStore 和 GooglePlay.
* [riemann](https://github.com/koudelka/elixir-riemann) - 一个 [Riemann](http://riemann.io/) Elixir 的客户.
* [rs_twitter](https://github.com/radzserg/rstwitter) - Elixir 的低级 Twitter 客户端.
* [semver](https://github.com/lee-dohm/semver) - 使用符合 semver.org 的版本字符串的实用程序.
* [sendgrid](https://github.com/alexgaribay/sendgrid_elixir) - 使用 SendGrid 发送可组合的事务性电子邮件.
* [shopify](https://github.com/nsweeting/shopify) - 轻松访问 Shopify API.
* [sift_ex](https://github.com/C404/sift_ex) - Elixir 的 Siftscience API 库.
* [simplex](https://github.com/adamkittelson/simplex) - 用于与 Amazon SimpleDB API 交互的 Elixir 库.
* [slack](https://github.com/BlakeWilliams/Elixir-Slack) - Elixir 中的 Slack 实时消息传递客户端.
* [sparkpost](https://github.com/SparkPost/elixir-sparkpost) - 使用 SparkPost 发送电子邮件的 Elixir 库.
* [statix](https://github.com/lexmag/statix) - 在 StatsD 协议中公开应用程序指标.
* [stripe](https://github.com/SenecaSystems/stripe) - 包装 Stripe API 的 Elixir 库.
* [stripity_stripe](https://github.com/robconery/stripity-stripe) - 一个长生不老药图书馆 [Stripe](https://stripe.com/).
* [tagplay](https://github.com/tagplay/elixir-tagplay) - Tagplay API 的 Elixir 客户端.
* [telegex](https://github.com/Hentioe/telegex) - Elixir 的 Telegram 机器人库.
* [telephonist](https://github.com/danielberkompas/telephonist) - 用于 Twilio 调用的 Elixir 状态机.
* [tentacat](https://github.com/edgurgel/tentacat) - GitHub API 的简单 Elixir 包装器.
* [tg_client](https://github.com/ccsteam/ex-telegram-client) - 与 Telegram-CLI 通信的 Elixir 包装器.
* [tradehub](https://github.com/anhmv/tradehub-elixir) - Tradehub 区块链的 Elixir 客户端库.
* [traitify_elixir](https://github.com/traitify/traitify_elixir) - 用于 Traitify 开发人员 API 的 Elixir 客户端库.
* [ui_faces](https://github.com/katgironpe/ui_faces) - 用于 Elixir 应用程序的 UIFaces API 客户端.
* [unsplash-elixir](https://github.com/waynehoover/unsplash-elixir) - Unsplash 的 Elixir 库.
* [vultr](https://github.com/avitex/elixir-vultr) - Vultr API 的简单包装器.
* [xe](https://github.com/paulodiniz/xe) - 货币的实时转换.
* [zanox](https://github.com/rafaelss/zanox) - Zanox API.

## Translations and Internationalizations
*提供翻译或国际化的库和工具.*

* [exkanji](https://github.com/ikeikeikeike/exkanji)  - 用于在平假名、片假名、罗马字和汉字之间进行翻译的 Elixir 库. 它使用 Mecab.
* [exromaji](https://github.com/ikeikeikeike/exromaji) - 用于在平假名、片假名和罗马字之间进行翻译的 Elixir 库.
* [free PO editor](https://pofile.net/free-po-editor) - 翻译 PO 文件的工具.
* [getatrex](https://github.com/alexfilatov/getatrex) - 用于 Elixir/Phoenix 项目的带有 Google 翻译的 Gettext 语言环境自动翻译工具.
* [gettext](https://github.com/elixir-lang/gettext) - Elixir 的国际化和本地化支持.
* [linguist](https://github.com/change/linguist) - Elixir 国际化库.
* [parabaikElixirConverter](https://github.com/Arkar-Aung/ParabaikElixirConverter)  - ParabaikElixirConverter 只是 Parabaik 转换器的 Elixir 版本. 它可以从 Unicode 转换为 Zawgyi-One 和 Zawgyi-One 到 Unicode，反之亦然.
* [trans](https://github.com/belaustegui/trans) - 一个 Elixir 库，用于管理嵌入到利用 PostgreSQL JSONB 数据类型的模型的翻译.

## Utilities
*实用程序库.*

* [ar2ecto](https://github.com/aforward/ar2ecto) - Ar2ecto 是一组混合任务，可帮助您从 ActiveRecord 迁移到 Ecto.
* [async_with](https://github.com/fertapric/async_with) - Elixir 的“with”修饰符以并行执行其所有子句.
* [crutches](https://github.com/mykewould/crutches) - Elixir 的实用程序库，旨在补充与语言捆绑的标准库.
* [deppie](https://github.com/whitfin/deppie) - Elixir 最酷的弃用记录器.
* [dot-notes](https://github.com/whitfin/dot-notes-elixir) - 地图/列表的简单点/括号符号解析/转换.
* [dress](https://github.com/veelenga/dress) - 让您的标准输出变得花哨的 Cli 应用程序.
* [erlang-history](https://github.com/ferd/erlang-history) - 将 shell 历史添加到 Erlang 的 shell 的黑客.
* [erlsh](https://github.com/proger/erlsh) - 涉及与系统外壳、路径和外部程序交互的功能和端口系列.
* [erlware_commons](https://github.com/erlware/erlware_commons) - Erlang 的附加标准库.
* [ex_progress](https://github.com/acj/ex_progress) - 用于跟踪许多任务和子任务的进度的库.
* [exjprop](https://github.com/stocks29/exjprop) - Elixir 库，用于从各种来源读取 Java 属性文件.
* [fitex](https://github.com/timdeputter/FitEx) - FitEx 是一个宏模块，它为函数定义提供了一点糖.
* [global](https://github.com/mgwidmann/global) - Erlang `:global` 模块的包装器.
* [mandrake](https://github.com/mbasso/mandrake) - Mandrake 是一个函数式编程库，它为长生不老药带来了其他魔力.
* [mnemonix](https://github.com/christhekeele/mnemonix) - 键/值存储的统一接口.
* [plasm](https://github.com/facto/plasm) - Plasm 是 Ecto 的可组合查询多功能工具，包含更高级别的函数，例如 .count、.random、.first、.last、.find、.inserted_before、.inserted_after 等.
* [plugmap](https://github.com/nerdslabs/plugmap) - Plugmap 是 Plug/Phoenix 框架的站点地图生成库. [Doc](https://hexdocs.pm/plugmap/readme.html)
* [pubsub](https://github.com/simonewebdesign/elixir_pubsub) - 一个发布-订阅实用程序库，它实现了发布-订阅机制，以减轻业务逻辑流程的通信负担.
* [quark](https://github.com/robot-overlord/quark) - 用于常见函数式编程习惯用法的库：组合子、柯里化和部分应用程序.
* [retry](https://github.com/safwank/ElixirRetry) - 用于线性重试、指数退避和可组合延迟等待的简单 Elixir 宏.
* [sips_downloader](https://github.com/DavsX/SipsDownloader) - Elixir 模块，用于下载 ElixirSips 剧集和所有其他文件.
* [sitemap](https://github.com/ikeikeikeike/sitemap) - 站点地图是在 Elixir 中生成站点地图的最简单方法.
* [sitemapper](https://github.com/tomtaylor/sitemapper) - 一个快速的、基于流的 XML 站点地图生成器.
* [uef-lib](https://github.com/DOBRO/uef-lib)  - 有用的 Erlang 函数库，提供用于操作列表、二进制文件、地图、数字、日期和时间的模块. 它包含一些针对特定情况下的性能优化的函数（例如，用于文件 I/O 操作或二进制转换）.
* [vert.x](https://github.com/PharosProduction/ExVertx) - 使用 TCP 套接字连接到 Vert.x 服务的 Elixir 事件总线桥.

## Validations
*用于验证数据的库和实现.*

* [bankster](https://github.com/railsmechanic/bankster) - Elixir 的 IBAN 帐号和 BIC 验证库.
* [ex_gtin](https://github.com/kickinespresso/ex_gtin) - GS1 规范下的 GTIN 代码验证库.
* [ex_nric](https://github.com/falti/ex_nric) - 验证新加坡国民登记身份证号码 (NRIC).
* [exop](https://github.com/madeinussr/exop) - 一个允许封装业务逻辑并使用预定义合约验证参数的库.
* [form](https://github.com/synrc/form) - 文档表格和验证库.
* [is](https://github.com/bydooweedoo/is) - 快速、可扩展且易于使用的 elixir 数据结构验证，支持嵌套结构.
* [jeaux](https://github.com/zbarnes757/jeaux) - 一个轻量级的模式验证器.
* [optimal](https://github.com/albert-io/optimal) - 基于模式的关键字列表选项验证器.
* [shape](https://github.com/prio/shape) - 基于 Prismatic Sc​​heme 的 Elixir 数据验证库.
* [skooma](https://github.com/bcoop713/skooma) - 用于描述和验证数据结构的简单数据验证库.
* [uk_postcode](https://github.com/KushalP/uk_postcode) - 英国邮政编码解析和验证库.
* [vex](https://github.com/CargoSense/vex) - Elixir 的可扩展数据验证库.
* [voorhees](https://github.com/danmcclain/voorhees) - 用于验证 JSON 响应的库.

## Version Control
*使用 git、mercury、subversion 等版本控制 ...*

* [gitex](https://github.com/awetzel/gitex) - Git 对象存储的 Elixir 实现，但目标是实现与其他存储和主题相同的语义.

## Video
*用于处理和操作视频和多媒体的库.*

* [ffmpex](https://github.com/talklittle/ffmpex) - FFmpeg 命令行包装器.
* [silent_video](https://github.com/talklittle/silent_video) - 将 GIF 和视频转换为无声视频，针对移动播放进行了优化.

## WebAssembly
*用于在 Elixir 中运行 WebAssembly (WASM) 或在 WebAssembly 上运行 Elixir 的库.*

* [lumen](https://github.com/lumen/lumen) - 为 WebAssembly 设计的另一种 BEAM 实现.
* [wasmex](https://github.com/tessi/wasmex/) - 从 Elixir 执行 WebAssembly / WASM 二进制文件.

## XML
*使用 XML 的库和实现（对于 html 工具，请访问 [HTML](#html) 部分）.*

* [elixir-map-to-xml](https://github.com/gunnar2k/elixir-map-to-xml) - 将 Elixir 映射转换为 XML 文档.
* [elixir-xml-to-map](https://github.com/homanchou/elixir-xml-to-map) - 从 XML 字符串创建 Elixir Map 数据结构.
* [erlsom](https://github.com/willemdj/erlsom) - Erlsom 是一个用于解析（和生成）XML 文档的 Erlang 库.
* [exmerl](https://github.com/pwoolcoc/exmerl) - xmerl 的 Elixir 包装器.
* [exml](https://github.com/expelledboy/exml) - xmerl xpath 的最简单的 Elixir 包装器.
* [exoml](https://github.com/Overbryd/exoml) - 将 xml 解码/编码为树结构的模块.
* [fast_xml](https://github.com/processone/fast_xml) - 基于快速 Expat 的 Erlang XML 解析库.
* [meeseeks](https://github.com/mischov/meeseeks) - 使用 CSS 或 XPath 选择器从 HTML 和 XML 中解析和提取数据的库.
* [quinn](https://github.com/nhu313/Quinn) - Elixir 的 XML 解析器.
* [saxy](https://github.com/qcam/saxy) - Saxy 是 Elixir 中的 XML 解析器和编码器，专注于速度和标准合规性.
* [sweet_xml](https://github.com/awetzel/sweet_xml) - 简单有效地查询 XML.
* [xml_builder](https://github.com/joshnuss/xml_builder) - 用于生成 xml 的 Elixir 库.
* [xmlrpc](https://github.com/ewildgoose/elixir-xml_rpc) - 为客户端和服务器编码和解码 XML-RPC 的库.

## YAML
*使用 YAML 的库和实现.*

* [fast_yaml](https://github.com/processone/fast_yaml) - Fast YAML 是 libyaml &quot;C&quot; 库的 Erlang 包装器.
* [yamerl](https://github.com/yakaz/yamerl) - Erlang 中的 YAML 1.2 解析器.
* [yaml_elixir](https://github.com/KamilLelonek/yaml-elixir) - 基于原生 Erlang 实现的 Elixir 的 Yaml 解析器.
* [ymlr](https://github.com/ufirstgroup/ymlr) - Elixir 的 YAML 编码器.
* [yomel](https://github.com/Joe-noh/yomel) - Elixir 的 libyaml 接口.

## Resources
各种资源，例如书籍、网站和文章，用于提高您的 Elixir 开发技能和知识.

## Books
*很棒的书和电子书.*

* [Adopting Elixir](https://pragprog.com/book/tvmelixir/adopting-elixir)  - 将 Elixir 带入您的公司，并结合创建 Elixir 并成功大规模使用它的人们的真实策略. 这本书包含了将应用程序从概念转变为生产所需的所有信息（2017 年）.
* [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) - 将您的 Web API 升级到 GraphQL，利用其灵活的查询为您的用户提供支持，并利用其声明性结构来简化您的代码（2017 年）.
* [Elixir Cookbook](https://www.packtpub.com/application-development/elixir-cookbook) - 这本书是由 Paulo A Pereira（2015 年）按主题分组的一组食谱.
* [Elixir do zero à concorrência](https://www.casadocodigo.com.br/products/livro-elixir) - （葡萄牙语）这本书介绍了 Tiago Davi（2014 年）使用 Elixir 进行的函数式和并发编程.
* [Elixir in Action](https://www.manning.com/books/elixir-in-action-second-edition) - Saša Jurić (2015) 对语言进行了简要介绍，然后更详细地介绍了如何在 Elixir 中构建生产就绪系统.
* [Elixir Succinctly](https://www.syncfusion.com/ebooks/elixir-succinctly) - 一本了解 Elixir 及其生态系统基础知识的短书.
* [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) - Wolfgang Loder (2016) 在功能概念的背景下介绍 Erlang 和 Elixir.
* [Erlang in Anger](http://www.erlang-in-anger.com/) - 这本书旨在成为 Fred Hebert（2014 年）在战争时期如何成为 Erlang 军医的小指南.
* [Études for Elixir](https://www.oreilly.com/library/view/etudes-for-elixir/9781491917640/) - J. David Eisenberg (2013) 在 Elixir 中编写的一系列练习（[Github Repo](https://github.com/oreillymedia/etudes-for-elixir)).
* [Functional Web Development with Elixir, OTP, and Phoenix](https://pragprog.com/book/lhelph/functional-web-development-with-elixir-otp-and-phoenix) - 向强大的新技术敞开大门，让您以全新的方式思考 Web 开发（2017 年）.
* [Getting Started - Elixir](https://github.com/potatogopher/elixir-getting-started) - Elixir 入门教程 (2016) 的 PDF、MOBI 和 EPUB 文档.
* [Hands-on Elixir & OTP: Cryptocurrency trading bot](https://www.elixircryptobot.com)  - 想通过创建一个真实世界的项目来学习 Elixir 和 OTP？ 通过动手*Elixir &amp; OTP：加密货币交易机器人*，您将通过从事有趣的软件项目获得动手经验. 我们将通过迭代的实现改进来探索所有关键的抽象和基本原则.  （2021 年）.
* [Introducing Elixir ](http://shop.oreilly.com/product/0636920030584.do) - 对语言的温和介绍，包含 Simon St. Laurent 和 J. David Eisenberg 的大量代码示例和练习（2013 年）.
* [Learn Functional Programming with Elixir](https://pragprog.com/book/cdc-elixir/learn-functional-programming-with-elixir)  - 不要带着命令的心态登上 Elixir 火车！ 要充分利用函数式语言，您需要从函数式角度进行思考（2017 年）.
* [Metaprogramming Elixir: Write Less Code, Get More Done (and Have Fun!)](https://pragprog.com/book/cmelixir/metaprogramming-elixir) - Chris McCord (2015) 详细解释了如何利用 Elixir 的元编程功能来改进您的 Elixir 编码.
* [Phoenix for Rails Developers](http://www.phoenixforrailsdevelopers.com)  - 这本书展示了 Rails 开发人员如何从他们现有的知识中受益来学习 Phoenix. 埃尔维奥·维科萨 (2017).
* [Phoenix in Action](https://manning.com/books/phoenix-in-action)  - 以您现有的 Web 开发技能为基础，教您 Phoenix 的独特优势以及足够的 Elixir 来完成工作. 杰弗里·莱塞尔 (2017).
* [Phoenix Inside Out](https://shankardevy.com/phoenix-book/)  - 本系列的目标是让您成为一名自信的 Phoenix 开发人员. 有 3 个不同的版本可以满足进入 Phoenix 的开发人员的不同需求.
* [Programming Elixir 1.6](https://pragprog.com/titles/elixir16/) - 这本书介绍了 Dave Thomas (2014) 的 Elixir 函数式和并发编程.
* [Programming Phoenix 1.4](https://pragprog.com/titles/phoenix14/) - Chris McCord、José Valim 和 Bruce Tate 撰写的使用 Phoenix 框架构建 Web 应用程序的权威指南（2015 年）.
* [The Beam Book](https://happi.github.io/theBeamBook/) - Erlang 运行时系统 ERTS 和虚拟机 BEAM 的描述.
* [The Little Elixir & OTP Guidebook](https://www.manning.com/books/the-little-elixir-and-otp-guidebook) - Benjamin Tan Wei Hao 通过中小型项目学习 Elixir 和 OTP 的书（2014 年）.

## Cheat Sheets
*有用的 Elixir 相关备忘单.*

* [benjamintanweihao/elixir-cheatsheets](https://github.com/benjamintanweihao/elixir-cheatsheets/) - GenServer 和 Supervisor 备忘单.

## Community
*通过聊天或邮件列表与社区联系.*

* [#elixir-lang](http://webchat.freenode.net/?channels=elixir-lang) - The IRC Channel #elixir-lang on Freenode.
* [Elixir Forum](https://elixirforum.com/) - 社区运行所有 Elixir 的讨论论坛.
* [elixir-lang-core](https://groups.google.com/d/forum/elixir-lang-core) - Elixir Core 开发的邮件列表，使用“talk”进行问题和一般性讨论.
* [elixir-lang-talk](https://groups.google.com/d/forum/elixir-lang-talk) - 用于问题和讨论的官方 Elixir 邮件列表.
* [ElixirSlack](https://elixir-slackin.herokuapp.com/) - Elixir Slack 社区.

## Editors
*可用于 Elixir/Erlang 的编辑器和 IDE*

* [Alchemist](https://github.com/tonini/alchemist.el) - Elixir 工具集成到 Emacs.
* [Alchemist-Server](https://github.com/tonini/alchemist-server) - 编辑器/IDE 独立后台服务器，用于通知 Elixir 混合项目.
* [Alchemist.vim](https://github.com/slashmili/alchemist.vim) - 将 Elixir 工具集成到 Vim 中.
* [Atom](https://atom.io/packages/language-elixir) - 对 Atom 的 Elixir 语言支持.
* [atom-elixir](https://github.com/msaraiva/atom-elixir) - Elixir 的 Atom 包.
* [atom-iex](https://github.com/indiejames/atom-iex) - 在 Atom 中运行 IEx 会话.
* [elixir-ls](https://github.com/JakeBecker/elixir-ls)  - Elixir 的独立于前端的 IDE “智能”服务器. 实现基于 JSON 的“语言服务器协议”标准，并通过 VS Code 的调试器协议提供调试器支持.
* [elixir-tmbundle](https://github.com/elixir-lang/elixir-tmbundle) - 用于 Elixir 的 TextMate 和 SublimeText 包.
* [elixir_generator](https://github.com/jadercorrea/elixir_generator.vim) - Vim 插件，用一个命令生成 Elixir 模块和测试文件.
* [ElixirSublime](https://github.com/vishnevskiy/ElixirSublime) - SublimeText 3 的 Elixir 插件，提供代码完成和 linting.
* [ilexir](https://github.com/dm1try/ilexir) - Neovim 中 Elixir 的类似 IDE 的东西.
* [intellij_elixir](https://github.com/KronicDeth/intellij_elixir) - intellj-elixir 的 Elixir 助手，JetBrains IDE 的 Elixir 插件.
* [Jetbrains](http://plugins.jetbrains.com/plugin/7522) - 适用于 IntelliJ IDEA、RubyMine、WebStorm、PhpStorm、PyCharm、AppCode、Android Studio、0xDBE 的 Elixir.
* [mix.nvim](https://github.com/brendalf/mix.nvim) - Neovim 的混合包装插件.
* [Notepad++](https://github.com/Hades32/elixir-udl-npp) - Notepad++ 的 Elixir 语法高亮显示.
* [Nova Elixir](https://github.com/stollcri/elixir.novaextension) - Nova 中 Elixir 文件（.ex、.exs、.eex）的语法突出显示和代码完成.
* [nvim](https://github.com/dm1try/nvim) - Neovim 主机，用于在 Elixir 中编写插件.
* [phoenix-snippets](https://github.com/phoenixframework-Brazil/phoenix-snippets) - Atom 的凤凰片段.
* [vim-elixir](https://github.com/elixir-lang/vim-elixir) - Elixir 的 Vim 配置文件.
* [vim-ex_test](https://github.com/moofish32/vim-ex_test) - 基于 Thoughtbots vim-rspec 的 Vim 测试运行器.
* [vim-mix-format](https://github.com/mhinz/vim-mix-format) - Vim 和 Neovim 的异步“混合格式”.
* [vscode-elixir](https://github.com/mat-mcloughlin/vscode-elixir) - 对 Visual Studio 代码的 Elixir 支持.
* [vscode-elixir-ls](https://github.com/JakeBecker/vscode-elixir-ls) - 由 ElixirLS 提供支持的 VS Code 的 Elixir 语言支持和调试器.

## Newsletters
*有用的 Elixir 相关新闻通讯.*

* [Elixir Digest](http://elixirdigest.net) - 每周通讯，包含有关 Elixir 和 Phoenix 的最新文章.
* [Elixir Radar](http://plataformatec.com.br/elixir-radar) - Plataformatec 每周通过电子邮件发布的“官方”Elixir 通讯.
* [ElixirWeekly](https://elixirweekly.net) - Elixir 社区通讯，涵盖您容易错过的内容，分享于 [ElixirStatus](http://elixirstatus.com) 和网络.

## Other Awesome Lists
*其他令人惊叹的列表可以在以下位置找到 [jnv/lists](https://github.com/jnv/lists#lists-of-lists) 或者 [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness#awesome-awesomeness).*

* [Awesome Elixir and CQRS](https://github.com/slashdotdash/awesome-elixir-cqrs) - 很棒的 Elixir 和命令查询职责分离 (CQRS) 和事件采购资源的精选列表.
* [Awesome Elixir by LibHunt](https://elixir.libhunt.com) - 很棒的 Elixir 和 Erlang 包和资源的精选列表.
* [Awesome Erlang](https://github.com/drobakowski/awesome-erlang) - 很棒的 Erlang 库、资源和闪亮的东西的精选列表.
* [Curated Elixir Resources](https://hackr.io/tutorials/learn-elixir) - 一系列顶级推荐的 Elixir 资源.
* [Erlang Bookmarks](https://github.com/0xAX/erlang-bookmarks) - Erlang 开发人员的链接集合.

## Podcasts
*讨论 Elixir 语言和社区的播客.*

* [Elixir Fountain](https://soundcloud.com/elixirfountain)
* [Elixir Mix](https://devchat.tv/elixir-mix/)
* [Elixir Outlaws](https://elixiroutlaws.com)
* [Elixir Talk](https://soundcloud.com/elixirtalk)

## Reading
*Elixir 相关阅读材料.*

* [Discover Elixir & Phoenix](https://www.ludu.co/course/discover-elixir-phoenix/) - 一个同时教授 Elixir 语言和 Phoenix 框架的在线课程.
* [Elixir Cheat-Sheet](http://media.pragprog.com/titles/elixir/ElixirCheat.pdf) - 安迪·亨特 (Andy Hunt) 和戴夫·托马斯 (Dave Thomas) 的 Elixir 备忘单.
* [Elixir Functional Programming](https://github.com/kblake/functional-programming) - 介绍使用 Elixir 语言进行函数式编程的材料.
* [Elixir School](https://elixirschool.com/) - 关于 Elixir 编程语言的课程.
* [Elixir Tab](https://github.com/efexen/elixir-tab) - 帮助您学习 Elixir 核心库的 Chrome 扩展程序.
* [Elixir vs Ruby | How Switching To Elixir Made Our Team Better](https://foxbox.com/blog/elixir-vs-ruby/) - 长篇文章，详细解释了何时以及为什么应该选择 Elixir 而不是 Ruby.
* [The Little Schemer in Elixir](https://github.com/jwhiteman/a-little-elixir-goes-a-long-way) - Little Schemer 书中的练习和算法，移植到 Elixir.
* [xElixir](https://github.com/exercism/xelixir) - Elixir 中的锻炼练习.

## Screencasts
*酷视频教程.*

* [Alchemist Camp](https://alchemist.camp) - Alchemist.Camp 有许多小时免费的、基于项目的 Elixir 学习截屏视频.
* [Confreaks (Elixir)](http://confreaks.tv/tags/40) - Elixir 相关的会议演讲.
* [Curso de Elixir de 0 a 100](https://www.youtube.com/watch?v=-K74G9nlzSY&list=PLMLox3fRb_I4_4-DnU3yS_EglDAuVpeEg) - 免费完成长生不老药课程（西班牙语）.
* [Elixir for Programmers](https://codestool.coding-gnome.com/courses/elixir-for-programmers) - Dave Thomas 教授的实用、并行、可靠（而且有趣！）.
* [Elixir Sips](http://elixirsips.com/) - 用于学习 Elixir 的小屏幕录像.
* [ElixirCasts.io](https://elixircasts.io/) - 帮助您学习 Elixir 和 Phoenix 的简单截屏视频.
* [ExCasts](https://excasts.com) - 适用于所有技能水平的 Elixir 和 Phoenix 截屏视频.
* [Kamil Skowron](https://www.youtube.com/c/kamilskowron) - 致力于推广函数式编程的 YouTube 频道，在 Elixir 中发布“真实世界”编程视频，例如“Hands-on Elixir &amp; OTP: Cryptocurrency trading bot”系列.
* [LearnElixir.tv](https://www.learnelixir.tv/) - 对初学者友好、深入、逐步的截屏视频.
* [LearnPhoenix.tv](https://www.learnphoenix.tv/) - 了解如何使用 Phoenix 构建快速、可靠的 Web 应用程序.
* [Meet Elixir](https://www.pluralsight.com/courses/meet-elixir) - 浏览 José Valim 的 Elixir 的一些特性和概念.
* [Elixir Foundation](https://www.youtube.com/playlist?list=PLjQo0sojbbxXc4aWg5i2umjv7U8YDoHQT)  - 通过构建一个实际示例来学习 Elixir. 了解 GenServer、Agents 和许多其他 elixir 原语是如何工作的.

## Styleguides
*在编码时确保一致性的样式指南.*

* [christopheradams/elixir_style_guide](https://github.com/christopheradams/elixir_style_guide) - 社区驱动的 Elixir 风格指南.
* [lexmag/elixir-style-guide](https://github.com/lexmag/elixir-style-guide) - 自以为是的 Elixir 风格指南.
* [rrrene/elixir-style-guide](https://github.com/rrrene/elixir-style-guide) - Style guide checked by [Credo](https://github.com/rrrene/credo).

## Websites
*有用的 Elixir 相关网站.*

* [30 Days of Elixir](https://github.com/seven1m/30-days-of-elixir) - 通过 30 个练习了解 Elixir 语言.
* [BEAM Community](http://beamcommunity.github.io/) - 从分布式系统到强大的服务器和 Erlang VM 上的语言设计.
* [Benjamin Tan - Learnings & Writings](http://benjamintan.io/blog/tags/elixir/) - 一个主要由 Elixir 帖子组成的博客.
* [Elixir Career](https://elixir.career/) - Elixir 的工作委员会和 Elixir 开发人员社区.
* [Elixir Examples](http://elixir-examples.github.io/) - 小型 Elixir 编程语言示例的集合.
* [Elixir Flashcards](https://elixircards.co.uk/)  - 抽认卡是提高知识的有效方式.  Elixircards 是手工制作、专业印刷的抽认卡，用于升级您的 Elixir.
* [Elixir Fountain](https://soundcloud.com/elixirfountain) - 每周播客，包含来自 Elixir 社区的新闻和采访，由 [Johnny Winn](https://twitter.com/johnny_rugger).
* [Elixir Github Repository](https://github.com/elixir-lang/elixir) - 项目存储库.
* [Elixir Github Wiki](https://github.com/elixir-lang/elixir/wiki) - 项目的 wiki，包含很多有用的信息.
* [ElixirLibs](https://elixirlibs.com) - Elixir 库的精选列表
* [Elixir Quiz](http://elixirquiz.github.io/) - 每周编程问题，帮助您学习 Elixir.
* [Elixir Recipes](http://elixir-recipes.github.io/) - Elixir 中常见问题的模式和解决方案的集合.
* [Hashrocket Today I Learned - Elixir](https://til.hashrocket.com/elixir) - 来自 Hashrocket 团队的关于 Elixir 的小帖子.
* [How I start - Elixir](http://howistart.org/posts/elixir/1) - Jose Valim 对 Elixir 的解释和介绍.
* [Learning Elixir](http://learningelixir.joekain.com/) - 关于专业软件工程师学习 Elixir 的博客.
* [Elixir Online Courses list - Classpert](https://classpert.com/elixir-programming) - 来自 Classpert 在线课程搜索的 Elixir 在线课程列表（有些是免费的）

## Contributing
请参见 [CONTRIBUTING](https://github.com/h4cc/awesome-elixir/blob/master/.github/CONTRIBUTING.md) 详情.
