<div class="github-widget" data-repo="h4cc/awesome-elixir"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Elixir [![Build Status](https://api.travis-ci.org/h4cc/awesome-elixir.svg?branch=master)](https://travis-ci.org/h4cc/awesome-elixir) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
精选的令人惊叹的 Elixir 库、资源和闪亮事物的列表，灵感来自 [awesome-php](https://github.com/ziadoz/awesome-php).

如果您认为应该添加一个包，请在相应的问题上添加一个 :+1: (`:+1:`) 或创建一个新的.

有 [other sites with curated lists of elixir packages](#other-awesome-lists) 你可以看看.


## Actors
*用于与演员等合作的库和工具.*

* [bpe](https://github.com/spawnproc/bpe)  - Erlang 中的业务流程引擎.  ([Doc](https://bpe.n2o.dev)).
* [dflow](https://github.com/dalmatinerdb/dflow) - 流水线式流处理引擎.
* [exactor](https://github.com/sasa1977/exactor) - 帮助在 Elixir 中更轻松地实现 actor.
* [exos](https://github.com/awetzel/exos) - 一个端口包装器，它将转换和调用转发到一个链接的端口.
* [flowex](https://github.com/antonmi/flowex) - 使用 Elixir GenStage 的基于铁路流的编程.
* [mon_handler](https://github.com/tattdcodemonkey/mon_handler) - 监视给定 GenEvent 处理程序的最小 GenServer.
* [pool_ring](https://github.com/camshaft/pool_ring) - 基于哈希环创建一个池.
* [poolboy](https://github.com/devinus/poolboy) - 一个笨拙的 Erlang 工人池工厂.
* [pooler](https://github.com/seth/pooler) - OTP 进程池应用程序.
* [sbroker](https://github.com/fishcakez/sbroker) - 基于逗留时间的活动队列管理库.
* [workex](https://github.com/sasa1977/workex) - EVM 过程中的背压和流量控制.

## Algorithms and Data structures
*算法和数据结构的库和实现.*

* [array](https://github.com/takscape/elixir-array) - Erlang 数组的 Elixir 包装库.
* [aruspex](https://github.com/dkendal/aruspex) - Aruspex 是一个可配置的约束求解器，完全用 Elixir 编写.
* [bimap](https://github.com/mkaput/elixir-bimap) - Pure Elixir 实现 [bidirectional maps](https://en.wikipedia.org/wiki/Bidirectional_map) 和多图.
* [bitmap](https://github.com/hashd/bitmap-elixir) - Pure Elixir 实现 [bitmaps](https://en.wikipedia.org/wiki/Bitmap).
* [blocking_queue](https://github.com/joekain/BlockingQueue)  - BlockingQueue 是一个实现为 GenServer 的简单队列. 它在创建时有一个固定的最大长度.
* [bloomex](https://github.com/gmcabrita/bloomex) - 可扩展布隆过滤器的纯 Elixir 实现.
* [clope](https://github.com/ayrat555/clope) - Elixir 的实现 [CLOPE](http://www.inf.ufrgs.br/~alvares/CMP259DCBD/clope.pdf)：一种快速有效的交易数据聚类算法.
* [combination](https://github.com/seantanly/elixir-combination) - Elixir 库，用于从 Enumerable 集合生成组合和排列.
* [count_buffer](https://github.com/camshaft/count_buffer) - 缓冲大量计数器并定期刷新.
* [cuckoo](https://github.com/gmcabrita/cuckoo) - 一个纯粹的 Elixir 实现 [Cuckoo Filters](https://www.cs.cmu.edu/%7Edga/papers/cuckoo-conext2014.pdf).
* [cuid](https://github.com/duailibe/cuid) - 用 Elixir 编写的针对水平缩放和顺序查找性能进行了优化的抗碰撞 ID.
* [data_morph](https://hex.pm/packages/data_morph) - 从数据创建 Elixir 结构.
* [dataframe](https://github.com/JordiPolo/dataframe) - 提供类似于 Python 的 Pandas 或 R 的 data.frame() 功能的包.
* [datastructures](https://github.com/meh/elixir-datastructures) - 一组用于处理数据结构的协议、实现和包装器.
* [def_memo](https://github.com/os6sense/DefMemo) - 使用 genserver 后备存储的 elixir 记忆宏 (defmemo).
* [dlist](https://github.com/stocks29/dlist) - Elixir 中的所有实现.
* [eastar](https://github.com/herenowcoder/eastar) - 纯 Elixir 中的 A* 图形寻路.
* [ecto_materialized_path](https://github.com/asiniy/ecto_materialized_path) - ecto 模型的树结构、层次结构和祖先.
* [ecto_state_machine](https://github.com/asiniy/ecto_state_machine) - 在 Elixir 上实现并为 Ecto 采用的有限状态机模式.
* [elistrix](https://github.com/tobz/elistrix) - 一个延迟/容错库，有助于将您的应用程序与缓慢或失败服务的不确定世界隔离开来.
* [emel](https://github.com/mrdimosthenis/emel) - 一个用 elixir 编写的简单实用的机器学习库.
* [erlang-algorithms](https://github.com/aggelgian/erlang-algorithms) - 流行数据结构和算法的实现.
* [exconstructor](https://github.com/appcues/exconstructor) - 一个 Elixir 库，用于生成轻松处理外部数据的结构构造函数.
* [exfsm](https://github.com/awetzel/exfsm) - 定义静态 FSM 的简单 elixir 库.
* [exkad](https://github.com/rozap/exkad) - 一种 [kademlia](https://en.wikipedia.org/wiki/Kademlia) 在 Elixir 中实现.
* [exmatrix](https://github.com/a115/exmatrix) - ExMatrix 是一个用于处理矩阵的小型库，最初开发用于并行测试矩阵乘法.
* [exor_filter](https://github.com/mpope9/exor_filter)  - xor_filters 的 Nif.  “比布隆和布谷鸟过滤器更快、更小”.
* [ezcryptex](https://github.com/stocks29/ezcryptex) - Cryptex 顶部的薄层.
* [flow](https://github.com/dashbitco/flow) - GenStage 之上的计算并行流程.
* [fnv](https://github.com/asaaki/fnv.ex) - Fowler–Noll–Vo 哈希函数的纯 Elixir 实现.
* [fsm](https://github.com/sasa1977/fsm) - 作为功能数据结构的有限状态机.
* [fuse](https://github.com/jlouis/fuse) - 此应用程序为 Erlang 实现了所谓的断路器.
* [gen_fsm](https://github.com/pavlos/gen_fsm) - 通用有限状态机 - 围绕 OTP 的 gen_fsm 的 Elixir 包装器.
* [graphmath](https://github.com/crertel/graphmath) - 用于执行 2D 和 3D 数学的 Elixir 库.
* [hash_ring_ex](https://github.com/reset/hash-ring-ex) - Elixir 的一致哈希环实现.
* [hypex](https://github.com/whitfin/hypex) - HyperLogLog 的快速 Elixir 实现.
* [indifferent](https://github.com/vic/indifferent) - 使用自定义键转换对 Elixir 映射/列表/元组的访问无关紧要.
* [isaac](https://github.com/arianvp/elixir-isaac) - Isaac 是 ISAAC 的灵丹妙药模块：快速加密随机数生成器.
* [jumper](https://github.com/whitfin/jumper) - 在 Elixir 中跳转一致的哈希实现（没有 NIF）.
* [key2value](https://github.com/okeuday/key2value) - Erlang 2 路集关联映射.
* [lfsr](https://github.com/pma/lfsr) - 二进制伽罗瓦线性反馈移位寄存器的 Elixir 实现.
* [loom](https://github.com/asonge/loom) - 支持 δ-CRDT 的 CRDT 库.
* [luhn](https://github.com/ma2gedev/luhn_ex) - Elixir 中的 Luhn 算法.
* [lz4](https://github.com/szktty/erlang-lz4) - 用于快速数据压缩的 Erlang LZ4 绑定.
* [machinery](https://github.com/joaomdmoura/machinery) - 一般用于结构的状态机库，它开箱即用地与 Phoenix 集成.
* [mason](https://github.com/spacepilots/mason)  - 强制映射到结构中. 这很有用，例如，当您连接 REST API 并希望从响应创建结构时.
* [matrex](https://github.com/versilov/matrex) - 使用 CBLAS 的具有 C 实现的 Elixir/Erlang 的超快矩阵库.
* [merkle_tree](https://github.com/yosriady/merkle_tree) - Elixir 中的 Merkle 哈希树实现.
* [minmaxlist](https://github.com/seantanly/elixir-minmaxlist) - Elixir 库扩展了 `Enum.min_by/2`、`Enum.max_by/2` 和 `Enum.min_max_by/2` 以返回结果列表而不是一个.
* [mmath](https://github.com/dalmatinerdb/mmath) - 用于对二进制文件中的数字“数组”执行数学运算的库.
* [monad](https://github.com/rmies/monad) - Haskell 启发了 Elixir 时尚语法中的 monad.
* [monadex](https://github.com/rob-brown/MonadEx) - 使用 monad 升级您的 Elixir 管道.
* [murmur](https://github.com/gmcabrita/murmur) - 非加密哈希 Murmur3 的纯 Elixir 实现.
* [nary_tree](https://github.com/medhiwidjaja/nary_tree) - 通用 n 元树数据结构的 Elixir 实现.
* [natural_sort](https://github.com/DanCouper/natural_sort) - 字符串列表的 Elixir 自然排序实现.
* [navigation_tree](https://github.com/gutschilla/elixir-navigation-tree) - 带有帮助程序的导航树表示，可从中生成 HTML.
* [parallel_stream](https://github.com/beatrichartz/parallel_stream) - Elixir 的并行流实现.
* [paratize](https://github.com/seantanly/elixir-paratize) - Elixir 库提供了一些方便的并行处理（执行）工具，支持配置工作线程数和超时.
* [parex](https://github.com/StevenJL/parex) - Parallel Execute (Parex) 是一个 Elixir 模块，用于并行执行多个（慢）进程.
* [qex](https://github.com/princemaple/elixir-queue) - 包装 `:queue`，具有改进的 API 和 `Inspect`、`Collectable` 和 `Enumerable` 协议实现.
* [ratio](https://github.com/Qqwy/elixir-rational)  - 添加有理数并允许它们用于常见的算术运算. 还支持浮点数和有理数之间的转换.
* [red_black_tree](https://github.com/SenecaSystems/red_black_tree) - Elixir 中的红黑树实现.
* [remodel](https://github.com/stavro/remodel) - 用于转换地图结构的 Elixir 演示程序包.
* [rendezvous](https://github.com/timdeputter/Rendezvous) - 在 Elixir 中实现 Rendezvous 或最高随机权重 (HRW) 哈希算法.
* [rock](https://github.com/ayrat555/rock) - ROCK 的 Elixir 实现：分类属性的稳健聚类算法.
* [sfmt](https://github.com/jj1bdx/sfmt-erlang/) - Erlang 的面向 SIMD 的 Fast Mersenne Twister (SFMT).
* [simhash](https://github.com/UniversalAvenue/simhash-ex) - 使用 Siphash 和 N-gram 实现 Simhash.
* [sleeplocks](https://github.com/whitfin/sleeplocks) - 用于 Elixir/Erlang 的 BEAM 友好自旋锁.
* [sorted_set](https://github.com/SenecaSystems/sorted_set) - Elixir 的排序集.
* [spacesaving](https://github.com/rozap/spacesaving) - 使用“节省空间”算法的流计数不同元素估计.
* [structurez](https://github.com/hamiltop/structurez) - Elixir 中数据结构的游乐场.
* [supermemo](https://github.com/edubkendo/supermemo) - 一个 Elixir 实现 [Supermemo 2 algorithm](https://www.supermemo.com/english/ol/sm2.htm).
* [tfidf](https://github.com/OCannings/tf-idf) - 词频-逆文档频率的 Elixir 实现.
* [the_fuzz](https://github.com/smashedtoatoms/the_fuzz) - 模糊字符串匹配算法实现.
* [tinymt](https://github.com/jj1bdx/tinymt-erlang/) - 用于 Erlang 的 Tiny Mersenne Twister (TinyMT).
* [trie](https://github.com/okeuday/trie) - Erlang Trie 实现.
* [witchcraft](https://github.com/expede/witchcraft) - Elixir 的常见代数结构和函数.
* [zipper_tree](https://github.com/Dkendal/zipper_tree) - 带有用于 Elixir 的拉链的可变参数树.

## Applications
*独立应用程序.*
* [CaptainFact](https://github.com/CaptainFact/captain-fact-api)  - 一个协作的实时视频事实核查平台.  ([Docs](https://captainfact.io/)).
* [chat](https://github.com/synrc/chat) - 基于 N2O 的小型文本聊天示例.
* [Consolex](https://github.com/sivsushruth/consolex) - Consolex 是一种工具，可让您将基于 Web 的控制台附加到任何混音项目.
* [dragonfly_server](https://github.com/cloud8421/dragonfly-server) - Elixir 应用程序来提供蜻蜓图像.
* [exchat](https://github.com/tony612/exchat) - Elixir、Phoenix 和 React (redux) 的类似 Slack 的应用程序.
* [Exon](https://github.com/tchoutri/Exon)  - 在 Elixir 中开发的“混乱管理器”并提供简单的 API 来管理和记录您的东西.  ([Docs](https://hexdocs.pm/exon/readme.html)).
* [ExShop](https://github.com/authentic-pixels/ex-shop) - 使用 Phoenix 框架创建的数字商品商店和博客.
* [Hydra](https://github.com/doomspork/hydra) - 多头野兽：API 网关、请求缓存和数据转换.
* [Igthorn](https://github.com/Frathon/Igthorn) - 带有管理面板的加密货币交易平台/交易机器人.
* [majremind](https://bitbucket.org/Anwen/majremind) - 更新服务器的自我维护数据库，告诉您需要更新哪个服务器.
* [medex](https://github.com/xerions/medex) - 体检 - 申请注册健康检查回调并通过 HTTP 表示其状态.
* [medusa_server](https://github.com/IcaliaLabs/medusa_server)  - 一个用 Elixir 编写的用于堆叠图像的简单牛仔 Web 服务器.  ([Docs](https://hexdocs.pm/medusa/0.2.0/api-reference.html)).
* [Nvjorn](https://github.com/tchoutri/Nvjorn) - 使用 Poolboy 用 Elixir 编写的多协议网络服务监视器.
* [Phoenix Battleship](https://github.com/bigardone/phoenix-battleship) - 使用 Elixir、Phoenix Framework、React 和 Redux 构建的 Good Old 游戏.
* [Phoenix Toggl](https://github.com/bigardone/phoenix-toggl) - 在 Elixir、Phoenix Framework、React 和 Redux 中完成的 Toggl 致敬.
* [Phoenix Trello](https://github.com/bigardone/phoenix-trello) - 在 Elixir、Phoenix Framework、React 和 Redux 中完成的 Trello 致敬.
* [poxa](https://github.com/edgurgel/poxa) - 开放 Pusher 实现，与 Pusher 库兼容.
* [Queerlink](https://github.com/Queertoo/Queerlink) - 用 Elixir 编写的简单而高效的 URL 缩短服务.
* [RemoteRetro](https://github.com/stride-nyc/remote_retro) - 用于在以下地点进行敏捷回顾的实时应用程序 [remoteretro.org](https://remoteretro.org) 用 Elixir/Phoenix/React 编写.
* [Sprint Poker](https://github.com/elpassion/sprint-poker) - 敏捷团队的在线评估工具，使用 Elixir Lang、Phoenix Framework 和 React 编写.
* [Startup Job](https://github.com/tsurupin/job_search) - 一个伞形项目，用于搜索从 Elixir/Phoenix 和 React/Redux 编写的网站上抓取的创业工作.
* [Tai](https://github.com/fremantle-capital/tai) - 一个可组合的实时加密货币市场数据和交易执行工具包.
* [tty2048](https://github.com/lexmag/tty2048) - 用 Elixir 编写的基于终端的 2048 游戏.
* [uai_shot](https://github.com/sergioaugrod/uai_shot) - 使用 Elixir、Phoenix Framework 和 Phaser 构建的多人船舶游戏.
* [workbench](https://github.com/fremantle-industries/workbench) - 从创意到执行 - 在全球分布式集群中管理您的交易操作.

## Artificial Intelligence
*当你的代码变得比你更聪明时.*

* [Exnn](https://github.com/zampino/exnn)  - 进化神经网络框架 à la G.Sher 用 Elixir 编写.  ([Docs](http://zampino.github.io/exnn/)).
* [Neat-Ex](https://gitlab.com/onnoowl/Neat-Ex)  - NEAT 算法的 Elixir 实现.  ([Docs](https://hexdocs.pm/neat_ex/Neat.html)).
* [Runhyve](https://runhyve.app)  - Runhyve 是 FreeBSD 上 bhyve 的完整虚拟机管理器. 它是用 Elixir 编写的，并使用 Phoenix 框架.
* [simple_bayes](https://github.com/fredwu/simple_bayes) - Elixir 中的简单贝叶斯/朴素贝叶斯实现.
* [Synapses](https://mrdimosthenis.github.io/Synapses/?elixir) - 一个轻量级的神经网络库.

## Audio and Sounds
*使用声音和音调的库.*

* [erlaudio](https://github.com/asonge/erlaudio) - Erlang PortAudio bindings.
* [firmata](https://github.com/entone/firmata) - 这个包实现了 Firmata 协议.
* [synthex](https://github.com/bitgamma/synthex) - 一个信号合成库.

## Authentication
*用于实现身份验证方案的库.*

* [aeacus](https://github.com/zmoshansky/aeacus) - 一个简单的可配置身份/密码认证模块（兼容 Ecto/Phoenix）.
* [apache_passwd_md5](https://github.com/kevinmontuori/Apache.PasswdMD5) - Apache/APR 风格的密码散列.
* [aws_auth](https://github.com/bryanjos/aws_auth) - 针对 Elixir 的 AWS 签名版本 4 签名库.
* [basic_auth](https://github.com/CultivateHQ/basic_auth) - Elixir Plug 可轻松向应用程序添加 HTTP 基本身份验证.
* [coherence](https://github.com/smpallen99/coherence)  - Coherence 是一个功能齐全、可配置的 Phoenix 身份验证系统.  ([Docs](https://hexdocs.pm/coherence/Coherence.html)).
* [doorman](https://github.com/BlakeWilliams/doorman) - 使 Elixir 身份验证简单灵活的工具.
* [elixir_auth_google](https://github.com/dwyl/elixir-auth-google) - 将 Google OAuth 身份验证（“使用 Google 登录”）添加到您的 Elixir/Phoenix 应用程序的最简单方法.
* [github_oauth](https://github.com/lidashuang/github_oauth) - 一个简单的 github oauth 库.
* [goth](https://github.com/peburrows/goth) - 通过 Google Cloud API 用于服务器到服务器应用程序的 OAuth 2.0 库.
* [guardian](https://github.com/ueberauth/guardian)  - 用于 Elixir 应用程序的身份验证框架.  ([Docs](https://hexdocs.pm/guardian/Guardian.html)).
* [guardian_db](https://github.com/ueberauth/guardian_db)  - Guardian 的扩展，用于跟踪应用程序数据库中的令牌以防止播放.  ([Docs](https://hexdocs.pm/guardian_db/readme.html)).
* [guardian_redis](https://github.com/alexfilatov/guardian_redis)  - Guardian DB 的 Redis 存储库.  ([Docs](https://hexdocs.pm/guardian_redis/readme.html)).
* [htpasswd](https://github.com/kevinmontuori/Apache.htpasswd) - Elixir 中的 Apache htpasswd 文件读写器.
* [mojoauth](https://github.com/mojolingo/mojo-auth.ex) - Elixir 中的 MojoAuth 实现.
* [oauth2](https://github.com/scrogson/oauth2) - Elixir 的 OAuth 2.0 客户端库.
* [oauth2_facebook](https://github.com/chrislaskey/oauth2_facebook) - 针对 Elixir 的 Facebook OAuth2 提供程序.
* [oauth2_github](https://github.com/chrislaskey/oauth2_github) - Elixir 的 GitHub OAuth2 提供程序.
* [oauth2cli](https://github.com/mgamini/oauth2cli-elixir) - 为 Elixir 编写的简单 OAuth2 客户端.
* [oauth2ex](https://github.com/parroty/oauth2ex) - Elixir 的另一个 OAuth 2.0 客户端库.
* [oauther](https://github.com/lexmag/oauther) - Elixir 的 OAuth 1.0 实现.
* [passwordless_auth](https://github.com/madebymany/passwordless_auth) - Elixir 的简单无密码登录或 2 因素/多因素身份验证.
* [phauxth](https://github.com/riverrun/phauxth) - Phoenix 1.3 和其他基于插件的应用程序的身份验证库.
* [phoenix_client_ssl](https://github.com/jshmrtn/phoenix-client-ssl) - 用于 Phoenix 和其他基于插件的应用程序的客户端 SSL 身份验证插件.
* [phx_gen_auth](https://github.com/aaronrenner/phx_gen_auth) - Phoenix 1.5 应用程序的身份验证系统生成器.
* [pow](https://github.com/danschultzer/pow) - 强大、模块化和可扩展的用户身份验证系统（[Website](https://powauth.com) - [Doc](https://hex.pm/packages/pow)).
* [samly](https://github.com/handnot2/samly) - SAML SP SSO 变得简单（[Doc](https://hexdocs.pm/samly/readme.html)).
* [sesamex](https://github.com/khusnetdinov/sesamex) - 5 分钟内另一种简单灵活的身份验证解决方案！
* [sigaws](https://github.com/handnot2/sigaws) - AWS Signature V4 签名和验证库（[Doc](https://hexdocs.pm/sigaws/Sigaws.html)).
* [ueberauth](https://github.com/ueberauth/ueberauth) - 基于插件的 Web 应用程序的 Elixir 身份验证系统.
* [ueberauth_auth0](https://hex.pm/packages/ueberauth_auth0) - 使用 Auth0 对您的用户进行身份验证的 Ueberauth 策略.
* [ueberauth_cas](https://github.com/marceldegraaf/ueberauth_cas) - Überauth 的中央身份验证服务策略.
* [ueberauth_facebook](https://github.com/ueberauth/ueberauth_Facebook) - 针对 Überauth 的 Facebook OAuth2 策略.
* [ueberauth_foursquare](https://github.com/borodiychuk/ueberauth_foursquare) - 用于 Überauth 的 Foursquare OAuth2 策略.
* [ueberauth_github](https://github.com/ueberauth/ueberauth_github) - Überauth 的 GitHub 策略.
* [ueberauth_google](https://github.com/ueberauth/ueberauth_google) - 针对 Überauth 的 Google 策略.
* [ueberauth_identity](https://github.com/ueberauth/ueberauth_identity) - Überauth 的简单用户名/密码策略.
* [ueberauth_line](https://github.com/alexfilatov/ueberauth_line) - Überauth 的 LINE 策略.
* [ueberauth_microsoft](https://github.com/swelham/ueberauth_microsoft) - Microsoft 的 Überauth 策略.
* [ueberauth_slack](https://github.com/ueberauth/ueberauth_slack) - Überauth 的 Slack 策略.
* [ueberauth_twitter](https://github.com/ueberauth/ueberauth_twitter) - Überauth 的 Twitter 策略.
* [ueberauth_vk](https://github.com/sobolevn/ueberauth_vk) - [vk.com](https://vk.com) Strategy for Überauth.
* [ueberauth_weibo](https://github.com/he9qi/ueberauth_weibo) - [Weibo](https://weibo.com) Überauth 的 OAuth2 策略.
* [zachaeus](https://github.com/railsmechanic/zachaeus) - 基于非对称加密的易于使用的许可系统.

## Authorization
*用于实现授权处理的库.*

* [authorize](https://github.com/jfrolich/authorize) - 基于规则的授权，用于高级授权规则.
* [bodyguard](https://github.com/schrockwell/bodyguard) - 灵活的 Phoenix 应用授权库.
* [canada](https://github.com/jarednorman/canada) - 一个简单的授权库，使用声明式权限规则提供友好的界面.
* [canary](https://github.com/cpjk/canary)  - Elixir 应用程序的授权库，用于限制当前用户可以访问的资源.  ([Docs](https://hexdocs.pm/canary/api-reference.html)).
* [speakeasy](https://github.com/coryodaniel/speakeasy) - 基于中间件的 Absinthe GraphQL 身份验证和授权，由 Bodyguard 提供支持.
* [terminator](https://github.com/MilosMosovsky/terminator)  - 基于数据库的授权 (ACL)，具有用于要求所需权限的自定义 DSL 规则.  ([Docs](https://hexdocs.pm/terminator/readme.html)).

## Behaviours and Interfaces
*定义某些事物应该如何表现，例如来自 OOP-World 的接口*

* [connection](https://github.com/fishcakez/connection)  - 连接进程的连接行为. 该 API 是 GenServer API 的超集.
* [gen_state_machine](https://github.com/antipax/gen_state_machine) - gen_statem 的 Elixir 包装器.
* [stockastic](https://github.com/shanewilton/stockastic) - Stockfighter API 的简单 Elixir 包装器.

## Benchmarking
*运行代码以查看需要多长时间，哪个更快和/或是否进行了改进.*

* [benchee](https://github.com/PragTob/benchee) - Elixir 中简单且可扩展的基准测试！
* [benchfella](https://github.com/alco/benchfella) - Elixir 的基准测试工具.
* [bmark](https://github.com/joekain/bmark) - Elixir 的基准测试工具.

## Bittorrent
*分享是对 Elixir 的关怀*

* [bento](https://github.com/folz/bento) - 令人难以置信的快速、正确、纯 Elixir Bencoding 库.
* [tracker_request](https://github.com/alehander42/tracker_request) - 处理 bittorrent 跟踪器请求和响应.
* [wire](https://github.com/alehander42/wire) - 使用 Elixir 编码和解码 bittorrent 对等线协议消息.

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
* [Exscript](https://github.com/liveforeverx/exscript) - 选择脚本库.
* [mad](https://github.com/synrc/mad) - 小而快速的钢筋更换.
* [pc](https://github.com/blt/port_compiler) - 一个 rebar3 端口编译器.
* [reaxt](https://github.com/awetzel/reaxt) - 将模板反应到您的 Elixir 应用程序中以进行服务器渲染.
* [rebar3_abnfc_plugin](https://github.com/surik/rebar3_abnfc_plugin) - Rebar3 abnfc 编译器.
* [rebar3_asn1_compiler](https://github.com/pyykkis/rebar3_asn1_compiler) - 使用 Rebar3 编译 ASN.1 模块的插件.
* [rebar3_auto](https://github.com/vans163/rebar3_auto) - Rebar3 插件可在文件更改时自动编译和重新加载.
* [rebar3_diameter_compiler](https://github.com/carlosedp/rebar3_diameter_compiler) - 在 rebar3 项目中编译直径 .dia 文件.
* [rebar3_eqc](https://github.com/kellymclaughlin/rebar3-eqc-plugin) - 一个 rebar3 插件，用于启用 Erlang QuickCheck 属性的执行.
* [rebar3_exunit](https://github.com/processone/rebar3_exunit) - 一个从 rebar3 构建工具运行 Elixir ExUnit 测试的插件.
* [rebar3_idl_compiler](https://github.com/sebastiw/rebar3_idl_compiler) - 这是一个使用 Rebar3 编译 Erlang IDL 文件的插件.
* [rebar3_live](https://github.com/pvmart/rebar3_live) - Rebar3 实时插件.
* [rebar3_neotoma_plugin](https://github.com/zamotivator/rebar3_neotoma_plugin) - Rebar3 neotoma（解析器表达式语法）编译器.
* [rebar3_protobuffs](https://github.com/benoitc/rebar3_protobuffs) - 使用来自 Basho 的 protobuffs 的 rebar3 protobuffs 提供者.
* [rebar3_run](https://github.com/tsloughter/rebar3_run) - 使用一个简单的命令运行一个版本.
* [rebar3_yang_plugin](https://github.com/surik/rebar3_yang_plugin) - Rebar3 yang compiler.
* [reltool_util](https://github.com/okeuday/reltool_util) - Erlang reltool 实用程序功能应用程序.
* [relx](https://github.com/erlware/relx) - Erlang 的发布汇编程序.
* [remix](https://github.com/AgilionApps/remix) - 文件更改时自动重新编译 Mix 代码.
* [rotor](https://github.com/HashNuke/rotor) - 超简单的 Elixir 构建系统.
* [sass_elixir](https://github.com/zamith/sass_elixir) - Elixir 项目的 sass 插件.

## Caching
*用于缓存数据的库.*

* [cachex](https://github.com/whitfin/cachex) - 强大的 Elixir 缓存库，具有广泛的功能集.
* [con_cache](https://github.com/sasa1977/con_cache) - ConCache 是基于 ETS 的键/值存储.
* [elixir_locker](https://github.com/tsharju/elixir_locker) - Locker 是更衣室 Erlang 库的 Elixir 包装器，它提供了一些有用的库，应该使使用储物柜更容易一些.
* [gen_spoxy](https://github.com/SpotIM/gen_spoxy) - 缓存变得有趣.
* [jc](https://github.com/jr0senblum/jc) - 具有发布/订阅、JSON 查询和一致性支持的内存中可分发缓存.
* [locker](https://github.com/wooga/locker) - 针对短期密钥的原子分布式“检查和设置”.
* [lru_cache](https://github.com/arago/lru_cache) - 简单的 LRU 缓存，用 ets 实现.
* [memoize](https://github.com/melpon/memoize) - 可轻松缓存功能的记忆宏.
* [nebulex](https://github.com/cabol/nebulex) - 一个快速、灵活和可扩展的 Elixir 分布式和本地缓存库.
* [stash](https://github.com/whitfin/stash) - 一个简单、快速且用户友好的键/值存储.

## Chatting
*通过 IRC、Slack、HipChat 和其他使用 Elixir 的系统聊天.*

* [alice](https://github.com/alice-bot/alice) - Elixir 的 Slack 机器人框架.
* [chatty](https://github.com/alco/chatty) - 一个基本的 IRC 客户端，对编写机器人最有用.
* [cog](https://github.com/operable/cog) - Cog 是一个开放的聊天平台，可在您的聊天窗口中为您提供安全、协作的命令行.
* [ExGram](https://github.com/rockneurotiko/ex_gram)  - 用于构建 Telegram Bots 的库，您可以使用低级方法和模型或使用包含的真正自以为是的框架.  ([Docs](https://hexdocs.pm/ex_gram/readme.html)).
* [ExIrc](https://github.com/bitwalker/exirc) - 用于 Elixir 项目的 IRC 客户端适配器.
* [ExMustang](https://github.com/techgaun/ex_mustang) - A simple, clueless slackbot and collection of responders.
* [Guri](https://github.com/elvio/guri) - 使用聊天消息自动执行任务.
* [hedwig](https://github.com/hedwig-im/hedwig) - Elixir 的 XMPP 客户端/机器人框架.（[Docs](https://hexdocs.pm/hedwig/readme.html)).
* [hipchat_elixir](https://github.com/ymtszw/hipchat_elixir) - Elixir 的 HipChat 客户端库，基于 httpc.
* [kaguya](https://github.com/Luminarys/Kaguya) - 一个小巧、强大、模块化的 IRC 机器人.
* [slacker](https://github.com/koudelka/slacker) - Slack 聊天服务的机器人库.
* [yocingo](https://github.com/Yawolf/yocingo) - 创建您自己的 Telegram Bot.

## Cloud Infrastructure and Management
*适用于您自己的云服务的应用程序、工具和库.*

* [aws](https://github.com/aws-beam/aws-elixir) - 针对 Elixir 的 AWS 客户端.
* [Bonny](https://github.com/coryodaniel/bonny) - Kubernetes 运营商开发框架.
* [Cloudi](http://cloudi.org/) - CloudI 用于需要软实时事务的后端服务器处理任务.
* [discovery](https://github.com/undeadlabs/discovery) - 使用 Consul 自动发现服务的 OTP 应用程序.
* [erlcloud](https://github.com/erlcloud/erlcloud)  - Erlang 云计算库（Amazon EC2、S3、SQS、SimpleDB、Mechanical Turk、ELB）.  ([Docs](https://hexdocs.pm/erlcloud/)).
* [ex_aws](https://github.com/CargoSense/ex_aws) - AWS 客户端，支持 Dynamo、Kinesis、Lambda、SQS 和 S3.
* [ex_riak_cs](https://github.com/ayrat555/ex_riak_cs) - Ripple CS API 客户端.
* [fleet_api](https://github.com/jordan0day/fleet-api)  - Fleet (CoreOS) API 的简单包装器. 可以与 etcd 令牌或通过直接节点 URL 一起使用.
* [Gandi](https://github.com/Ahamtech/elixir-Gandi) - 用于 Leaseweb 基础设施的 Gandi 包装器.
* [IElixir](https://github.com/pprzetacznik/IElixir) - 用于 Elixir 编程语言的 Jupyter 内核.
* [k8s](https://github.com/coryodaniel/k8s) - Kubernetes Elixir 客户端，具有 CRD 支持、多集群支持、可插拔身份验证和可配置中间件.
* [Kazan](https://github.com/obmarg/kazan) - Elixir 的 Kubernetes 客户端，根据 k8s 开放 API 规范生成.
* [Kubex](https://github.com/ingerslevio/kubex) - Kubernetes 客户端和 Elixir 集成，用纯 Elixir 编写.
* [Leaseweb](https://github.com/Ahamtech/elixir-leaseweb) - 用于 Leaseweb 基础设施的 Elixir 包装器.
* [libcluster](https://github.com/bitwalker/libcluster) - Elixir 应用程序的自动集群形成/修复.（[Docs](https://hexdocs.pm/libcluster/readme.html)).
* [nodefinder](https://github.com/okeuday/nodefinder) - Erlang 中自动节点发现的策略.
* [nomad](https://github.com/sashaafm/nomad)  - 创建云便携式 Elixir 和 Phoenix 应用程序. 一次编写，到处使用！
* [sidejob](https://github.com/basho/sidejob) - Erlang 的并行工作者和容量限制库.
* [sidetask](https://github.com/PSPDFKit-labs/sidetask) - SideTask 是 Task.Supervisor 的替代品，它使用 Basho 的具有并行性和容量限制的 sidejob 库.
* [skycluster](https://github.com/Nebo15/skycluster)  - 针对 Elixir/Erlang 应用程序的自动 Erlang 集群形成、消息传递和管理. 与 Kubernetes 集成.

## Code Analysis
*用于代码库分析、解析和操作的库和工具.*

* [belvedere](https://github.com/nirvana/belvedere) - CircleCI 与 Elixir 集成的示例.
* [coverex](https://github.com/alfert/coverex) - Elixir 的覆盖率报告.
* [credo](https://github.com/rrrene/credo)  - 静态代码分析工具，专注于代码一致性和 Elixir 教学.  ([Docs](https://hexdocs.pm/credo/Credo.html)).
* [DepViz](https://depviz.jasonaxelson.com/)  - 帮助开发人员了解项目中 Elixir 重新编译的可视化工具.  ([Code](https://github.com/axelson/dep_viz/)).
* [dialyxir](https://github.com/jeremyjh/dialyxir) - 混合任务以简化 Elixir 项目中 Dialyzer 的使用.（[Docs](https://hexdocs.pm/dialyzex/Mix.Tasks.Dialyzer.html)).
* [dogma](https://github.com/lpil/dogma) - Elixir 的代码样式 linter，由羞耻提供支持.（[Docs](https://hexdocs.pm/dogma/api-reference.html)).
* [excoveralls](https://github.com/parroty/excoveralls) - 与 coveralls.io 集成的 Elixir 覆盖率报告工具.
* [exprof](https://github.com/parroty/exprof) - 一个简单的 Elixir 代码分析器，使用 eprof.

## Command Line Applications
*任何有助于构建 CLI 应用程序的东西.*

* [anubis](https://github.com/bennyhallett/anubis) - Elixir 的命令行应用程序框架.
* [ex_cli](https://github.com/tuvistavie/ex_cli) - 用于 Elixir 的用户友好 CLI 应用程序.
* [ex_prompt](https://github.com/behind-design/ex_prompt) - 帮助程序包，尽可能轻松地为您的命令行应用程序添加交互性.
* [firex](https://github.com/msoedov/firex) - Firex 是一个用于从 elixir 模块自动生成命令行界面 (CLI) 的库.
* [getopt](https://github.com/jcomellas/getopt) - Erlang 的命令行选项解析器.
* [loki](https://github.com/khusnetdinov/loki) - 用于创建交互式命令行应用程序的库.
* [optimus](https://github.com/savonarola/optimus) - 灵感来自 Elixir 的命令行选项解析器 [clap.rs](https://clap.rs/).
* [phoenix-cli](https://phoenix-cli.github.io/) - Phoenix Framework 的命令行界面，如 Rails 命令.
* [progress_bar](https://github.com/henrik/progress_bar) - 命令行进度条和微调器.
* [ratatouille](https://github.com/ndreynolds/ratatouille) - Elixir 的 TUI（终端 UI）套件.
* [scribe](https://github.com/codedge-llc/scribe)  - Elixir 结构和地图的漂亮打印表. 灵感来自 hirb.
* [table_rex](https://github.com/djm/table_rex) - 生成可配置的 ASCII 样式表以供显示.
* [tabula](https://github.com/aerosol/tabula) - ASCII 表中 Ecto 查询结果/地图的漂亮打印列表（GitHub Markdown/OrgMode）.

## Configuration
*使用配置的库和工具*

* [confex](https://github.com/Nebo15/confex) - Helper 模块提供了一种在运行时读取环境配置的好方法.
* [configparser_ex](https://github.com/easco/configparser_ex) - 一个简单的 Elixir 解析器，用于 Python 的 configparser 库处理的同类文件.
* [conform](https://github.com/bitwalker/conform) - Elixir 应用程序的轻松发布配置.
* [dotenv](https://github.com/avdi/dotenv_elixir) - dotenv 到 Elixir 的端口.
* [ex_conf](https://github.com/phoenixframework/ex_conf) - 简单的 Elixir 配置管理.
* [figaro](https://github.com/trestrantham/ex_figaro) - 简单的 Elixir 项目配置.
* [figaro_elixir](https://github.com/KamilLelonek/figaro-elixir) - Elixir 的环境变量管理器.
* [hush](https://github.com/gordalina/hush) - 在运行时读取和注入配置，并在支持多个提供程序的发布模式下读取和注入配置.
* [hush_aws_secrets_manager](https://github.com/gordalina/hush_aws_secrets_manager) - 用于静默的 AWS Secrets Manager 提供商.
* [hush_gcp_secret_manager](https://github.com/gordalina/hush_gcp_secret_manager) - 用于安静的 Google Secret Manager 提供商.
* [sweetconfig](https://github.com/d0rc/sweetconfig) - 从您的应用程序的任何位置读取 YAML 配置文件.

## Cryptography
*加密和解密数据*

* [aescmac](https://github.com/kleinernik/elixir-aes-cmac) - AES CMAC ([RFC 4493](https://tools.ietf.org/html/rfc4493)) 在长生不老药.
* [cipher](https://github.com/rubencaro/cipher) - 用于加密/解密任意二进制文件的 Elixir 加密库.
* [cloak](https://github.com/danielberkompas/cloak) - Cloak 使使用 Ecto 加密变得容易.（[Docs](https://hexdocs.pm/cloak/readme.html)).
* [comeonin](https://github.com/riverrun/comeonin) - Elixir 的密码散列（argon2、bcrypt、pbkdf2_sha512）库.（[https://hexdocs.pm/comeonin/api-reference.html](https://hexdocs.pm/comeonin/api-reference.html)).
* [crypto_rsassa_pss](https://github.com/potatosalad/erlang-crypto_rsassa_pss) - Erlang 的 RSASSA-PSS 公钥加密签名算法.
* [elixir_tea](https://github.com/keichan34/elixir_tea) - 在 Elixir 中实现 TEA.
* [ex_bcrypt](https://github.com/manelli/ex_bcrypt) - OpenBSD bcrypt 密码散列算法的 Elixir 包装器.
* [ex_crypto](https://github.com/ntrepid8/ex_crypto)  - Erlang `crypto` 和 `public_key` 模块的 Elixir 包装器. 为许多加密函数提供合理的默认值，使其更易于使用.（[Docs](https://hexdocs.pm/ex_crypto/readme.html)).
* [exgpg](https://github.com/rozap/exgpg) - 使用 Elixir 的 gpg.
* [ntru_elixir](https://github.com/alisinabh/ntru_elixir)  - libntru 的 Elixir 包装器. 后量子密码系统.
* [one_time_pass_ecto](https://github.com/riverrun/one_time_pass_ecto) - Elixir 的一次性密码库.
* [pot](https://github.com/yuce/pot) - Erlang 库，用于生成与 Google 身份验证器兼容的一次性密码.
* [rsa](https://github.com/trapped/elixir-rsa) - Elixir 的`public_key` 加密封装.
* [rsa_ex](https://github.com/anoskov/rsa-ex) - 用于处理 RSA 密钥的库.
* [siphash-elixir](https://github.com/whitfin/siphash-elixir) - Elixir implementation of the SipHash hash family.
* [tea_crypto](https://github.com/keichan34/tea_crypto_erl) - 微小的加密算法实现.

## CSV
*使用 CSV 的库和实现.*

* [cesso](https://github.com/meh/cesso) - Elixir 的 CSV 处理库.
* [csv](https://github.com/beatrichartz/csv) - Elixir 的 CSV 解码和编码.
* [csv2sql](https://github.com/Arp-G/csv2sql) - 快速且全自动的 CSV 到数据库导入器.
* [csvlixir](https://github.com/jimm/csvlixir) - Elixir 的 CSV 读/写应用程序.
* [ecsv](https://github.com/erpuno/ecsv) - 用于 Elixir 的基于 libcs​​v 的快速流解析器.
* [ex_csv](https://github.com/CargoSense/ex_csv) - 用于 Elixir 的 CSV.
* [nimble_csv](https://github.com/plataformatec/nimble_csv) - 用于 Elixir 的简单快速的 CSV 解析和转储库.

## Date and Time
*用于处理日期和时间的库.*

* [block_timer](https://github.com/adamkittelson/block_timer) - 将 :timer.apply_after 和 :timer.apply_interval 与块一起使用的宏.
* [calendar](https://github.com/lau/calendar) - 日历是 Elixir 的日期和时间库.
* [calendarific](https://github.com/Bounceapp/elixir-calendarific) - Calendarific 是假期 API Calendarific 的包装器.
* [calixir](https://github.com/rengel-de/calixir) - Calixir 是 Lisp 日历软件 calendrica-4.0 到 Elixir 的端口.
* [chronos](https://github.com/nurugger07/chronos) - Elixir 日期/时间库.
* [cocktail](https://github.com/peek-travel/cocktail) - 基于 iCalendar 事件的 Elixir 日期重复库.
* [cronex](https://github.com/jbernardo95/cronex) - 类似 Cron 的系统，您可以安装在您的监督树中.
* [crontab](https://github.com/jshmrtn/crontab) - Cron 表达式解析器、作曲家和日期候选查找器.
* [emojiclock](https://github.com/nathanhornby/emojiclock-elixir) - 一个 Elixir 模块，用于为您提供特定小时的表情符号时钟.
* [ex_ical](https://github.com/fazibear/ex_ical) - ICalendar 解析器.
* [filtrex](https://github.com/rcdilorenzo/filtrex) - 用于执行和验证来自客户端的复杂 SQL 式过滤器（例如智能过滤器）的库.
* [good_times](https://github.com/DevL/good_times) - 富有表现力且易于使用的日期时间函数.
* [jalaali](https://github.com/jalaali/elixir-jalaali) - Elixir 的 Jalaali 日历实现.
* [milliseconds](https://github.com/davebryson/elixir_milliseconds) - 在 Elixir 中使用毫秒的简单库.
* [moment](https://github.com/atabary/moment) - 在 Elixir 中解析、验证、操作和显示日期.
* [open_hours](https://github.com/hopsor/open_hours) - 使用营业时间计算时间.
* [quantum](https://github.com/quantum-elixir/quantum-core) - 用于 Elixir 应用程序的类似 Cron 的作业调度程序.
* [repeatex](https://github.com/rcdilorenzo/repeatex) - 重复日期的自然语言解析.
* [tiktak](https://github.com/ConduitMobileRND/tiktak) - 用 Elixir 编写的快速轻量级的 Web 调度程序.
* [timelier](https://github.com/ausimian/timelier) - 针对 Elixir 的 cron 式调度程序.
* [timex](https://github.com/bitwalker/timex) - 易于使用的 Elixir 日期和时间模块.
* [timex_interval](https://github.com/atabary/timex-interval) - 基于 Timex 的 Elixir 项目的日期/时间间隔库.
* [tzdata](https://github.com/lau/tzdata) - Elixir 中的时区数据库.

## Debugging
*用于调试代码和应用程​​序的库和工具.*

* [beaker](https://github.com/hahuang65/beaker) - Elixir 的统计和指标库.
* [booter](https://github.com/eraserewind/booter) - 逐步启动 Elixir 应用程序.
* [dbg](https://github.com/fishcakez/dbg) - Elixir 的分布式跟踪.
* [eflame](https://github.com/proger/eflame) - Erlang 的火焰图分析器.
* [eh](https://github.com/Frost/eh) - 从命令行查找 Elixir 文档的工具.
* [eper](https://github.com/massemanet/eper) - Erlang 性能和调试工具.
* [ether](https://github.com/maarek/ether) - Ether 提供了将 Elixir 连接到 Erlang 调试器的功能.
* [ex_debug_toolbar](https://github.com/kagux/ex_debug_toolbar) - Phoenix 项目的工具栏，用于交互式调试代码并显示有关请求的有用信息：日志、时间线、数据库查询等.
* [exrun](https://github.com/liveforeverx/exrun) - 具有速率限制和简单的基于宏的界面的 Elixir 分布式跟踪.
* [extrace](https://github.com/redink/extrace) - Recon Trace 的 Elixir 包装器.
* [git_hooks](https://github.com/qgadrian/elixir_git_hooks) - 向 Elixir 项目添加 git 钩子.
* [observer_cli](https://github.com/zhongwencool/observer_cli) - 在命令行上可视化 Elixir 和 Erlang 节点，旨在帮助开发人员调试生产系统.
* [quaff](https://github.com/qhool/quaff) - Debug 模块提供了一个简单的帮助器界面，用于在 erlang 图形调试器中运行 Elixir 代码.
* [rexbug](https://github.com/nietaki/rexbug) - `redbug` 生产友好型 Erlang 跟踪调试器的 Elixir 包装器.
* [visualixir](https://github.com/koudelka/visualixir) - 远程 BEAM 节点的过程可视化器.

## Deployment
*在其他机器上自动安装和运行你的代码.*

* [akd](https://github.com/annkissam/akd) - Capistrano 类似、可配置且易于设置 Elixir 部署自动化框架.
* [ansible-elixir-stack](https://github.com/HashNuke/ansible-elixir-stack) - 一条命令设置并部署到服务器，为 Phoenix 应用程序提供一流的支持.
* [bootleg](https://github.com/labzero/bootleg) - Elixir 的简单部署和服务器自动化.
* [bottler](https://github.com/rubencaro/bottler) - Bottler 是一组工具，旨在帮助您生成版本、将它们发送到您的服务器、在那里安装它们，并使它们在生产中上线.
* [edeliver](https://github.com/boldpoker/edeliver) - 针对 Elixir 和 Erlang 的部署.
* [elixir-on-docker](https://github.com/CrowdHailer/elixir-on-docker) - 用于开始为云环境开发集群 Elixir 应用程序的项目模板.
* [exdm](https://github.com/joeyates/exdm) - 通过混合任务部署 Elixir 应用程序.
* [exreleasy](https://github.com/miros/exreleasy) - 用于发布 Elixir 应用程序的简单且混合友好的工具.
* [gatling](https://github.com/hashrocket/gatling) - 收集混合任务以从 git 自动创建 exrm 版本并在您的服务器上启动/升级它.
* [Gigalixir](https://www.gigalixir.com)  - 为 Elixir 设计的功能齐全的 PaaS. 支持集群、热升级和远程控制台/观察器. 无需信用卡即可免费试用.
* [heroku-buildpack-elixir](https://github.com/HashNuke/heroku-buildpack-elixir) - Heroku buildpack 将 Elixir 应用程序部署到 Heroku.

## Documentation
*用于创建文档的库和工具.*

* [blue_bird](https://github.com/KittyHeaven/blue_bird)  - BlueBird 是一个用 Elixir 编程语言为 Phoenix 框架编写的库. 它允许您从控制器和自动化测试中的注释生成 API 蓝图格式的 API 文档.
* [bureaucrat](https://github.com/api-hogs/bureaucrat) - 从测试中生成 Phoenix API 文档.
* [ex_doc](https://github.com/elixir-lang/ex_doc) - ExDoc 是为您的 Elixir 项目生成文档的工具.
* [ex_doc_dash](https://github.com/JonGretar/ExDocDash) - ExDoc 的格式化程序，用于生成 Dash.app 中使用的 docset 文档.
* [hexdocset](https://github.com/yesmeck/hexdocset) - 将十六进制文档转换为 Dash.app 的文档集格式.
* [inch-ci](http://inch-ci.org/) - Ruby 和 Elixir 的文档徽章.
* [maru_swagger](https://github.com/falood/maru_swagger) - 将 swagger 兼容文档添加到您的 maru API.
* [phoenix_api_docs](https://github.com/smoku/phoenix_api_docs) - 从 Phoenix 框架中的控制器和测试生成 API 蓝图文档.
* [phoenix_swagger](https://github.com/xerions/phoenix_swagger) - 提供与 Phoenix 框架的 swagger 集成.
* [xcribe](https://github.com/brainn-co/xcribe) - 使用 Swagger (OpenAPI) 或 API Blueprint 规范从测试中生成 API 文档.

## Domain-specific language
*Specialized computer languages for a particular application domain.*

* [Absinthe Graphql](https://github.com/absinthe-graphql/absinthe) - 功能齐全的 GraphQL 库.
* [absinthe_gen](https://github.com/sashman/absinthe_gen) - Absithne 的脚手架生成器.
* [JSON-LD.ex](https://github.com/marcelotto/jsonld-ex) - 实施 [JSON-LD](http://www.w3.org/TR/json-ld/) 标准 [RDF.ex](https://github.com/marcelotto/rdf-ex).
* [RDF.ex](https://github.com/marcelotto/rdf-ex) - 实施 [RDF](https://www.w3.org/TR/rdf11-primer/) Elixir 中的数据模型.
* [SPARQL.ex](https://github.com/marcelotto/sparql-ex) - 实施 [SPARQL](http://www.w3.org/TR/sparql11-overview/) Elixir 中的标准.

## ECMAScript
*使用 JavaScript、JScript 或 ActionScript 的实现.*

* [elixirscript](https://github.com/elixirscript/elixirscript/) - 从 Elixir 到 Javascript 的转译器.
* [estree](https://github.com/bryanjos/elixir-estree) - 在 Elixir 中实现 SpiderMonkey Parser API.
* [phoenix_gon](https://github.com/khusnetdinov/phoenix_gon) - 允许您毫无问题地将 Phoenix 环境或控制器变量传递给 JavaScript.
* [phoenix_routes_js](https://github.com/khusnetdinov/phoenix_routes_js) - Phoenix 在 JavaScript 代码和浏览器控制台中路由助手.

## Email
*使用电子邮件和其他东西.*

* [bamboo](https://github.com/thoughtbot/bamboo)  - 可组合、可测试和基于适配器的电子邮件库. 对使用 Phoenix 进行渲染的开箱即用支持以及用于在开发中预览已发送电子邮件的插件.
* [burnex](https://github.com/Betree/burnex) - 燃烧器电子邮件（临时地址）检测器.
* [echo](https://github.com/zmoshansky/echo)  - 元通知系统；  Echo 检查通知偏好并发送通知.
* [ex_postmark](https://github.com/KamilLelonek/ex_postmark) - 用于在 Elixir 中发送模板电子邮件的邮戳适配器.
* [gen_smtp](https://github.com/Vagabond/gen_smtp) - 可以通过回调模块扩展的通用 Erlang SMTP 服务器和客户端.
* [gmail](https://github.com/craigp/elixir-gmail) - 一个用于 Elixir 的简单 Gmail REST API 客户端.
* [mail](https://github.com/DockYard/elixir-mail) - Elixir 中的 RFC2822 实现，专为可组合性而构建.
* [mailer](https://github.com/antp/mailer) - 一个简单的 SMTP 邮件程序.
* [mailibex](https://github.com/awetzel/mailibex) - 包含 Elixir 中电子邮件相关实现的库：dkim、spf、dmark、mimemail、smtp.
* [mailman](https://github.com/kamilc/mailman) - Mailman 提供了一种在 Elixir 应用程序中定义邮件程序的简洁方法.
* [pop3mail](https://hex.pm/packages/pop3mail) - Pop3 客户端通过命令行或 Elixir API 从收件箱下载电子邮件（包括附件）.
* [ravenx](https://github.com/acutario/ravenx) - Elixir 应用程序的通知调度库.
* [smoothie](https://github.com/jfrolich/smoothie) - 您的电子邮件模板的内联样式 Smoothie，并从 HTML 生成纯文本版本.
* [swoosh](https://github.com/swoosh/swoosh) - 使用适用于 SMTP、Sendgrid、Mandrill、Mailgun、Postmark 等的适配器，以及 Phoenix 与邮箱预览的集成，在 Elixir 中轻松撰写、发送和测试您的电子邮件（带附件！）.

## Embedded Systems
*嵌入式系统开发.*

* [nerves](http://nerves-project.org) - 在 Elixir 中编写嵌入式软件的框架.

## Encoding and Compression
*以不同格式转换数据或对其进行压缩.*

* [ex_rlp](https://github.com/exthereum/ex_rlp) - 以太坊 RLP（递归长度前缀）编码的 Elixir 实现.
* [huffman](https://github.com/SenecaSystems/huffman) - Elixir 中的霍夫曼编码和解码.

## Errors and Exception Handling
*处理错误和异常.*

* [exceptional](https://github.com/expede/exceptional) - 快乐路径编程和异常处理的助手.
* [happy](https://github.com/vic/happy) - 快乐路径编程，替代灵丹妙药`with`形式.
* [OK](https://github.com/CrowdHailer/OK) - 使用结果 monad 进行优雅的错误处理，具有简单而强大的 `with` 构造和快乐路径管道运算符.
* [sentry-elixir](https://github.com/getsentry/sentry-elixir) - 官方 Elixir 客户端 [Sentry](https://sentry.io/).

## Eventhandling
*在 Elixir 中发送/发射和接收/处理事件.*

* [cizen](https://gitlab.com/cizen/cizen) - 使用一系列传奇构建高度并发、可监控和可扩展的应用程序.
* [event_bus](https://github.com/mustafaturan/event_bus) - 带有主题过滤和内置事件存储和事件观察器的简单事件总线实现.
* [goldrush](https://github.com/DeadZen/goldrush) - Small, Fast event processing and monitoring for Erlang/OTP applications.
* [reaxive](https://github.com/alfert/reaxive) - Reaxive 是一个反应式事件处理库，灵感来自 [Elm](http://elm-lang.org) 和反应式扩展.
* [wait_for_it](https://github.com/jvoegele/wait_for_it) - 为同步并发活动提供方便且易于使用的工具.

## Examples and funny stuff
*示例代码和太有趣或好奇的东西更不用说.*

* [butler_cage](https://github.com/keathley/butler_cage) - 一个用于显示尼克凯奇愚蠢照片的巴特勒插件.
* [butler_tableflip](https://github.com/keathley/butler_tableflip) - 与管家翻转桌子.
* [changelog.com](https://github.com/thechangelog/changelog.com) - 运行使用 Phoenix 1.4 构建的 changelog.com 的 CMS.
* [coderplanets.com](https://github.com/coderplanets/coderplanets_server) - 使用 Phoenix 1.4 和 Absinthe 构建的用于 coderplanets.com 的 GraphQL api.
* [dice](https://github.com/stocks29/dice) - 在 Elixir 中掷骰子.
* [elixir_koans](https://github.com/elixirkoans/elixir-koans) - [Elixir koans](http://elixirkoans.io/) 是开始使用 elixir 编程语言的一种有趣且简单的方法.
* [ex_chain](https://github.com/eljojo/ex_chain) - 使用 Elixir 构建的生成有趣推文的简单马尔可夫链.
* [ex_iss](https://github.com/cryptobird/ex_iss) - 此包用于与 Open Notify API 接口以获取信息，例如国际空间站的当前位置、机组人员以及它何时会经过某个位置.
* [feedx](https://github.com/erneestoc/feedx)  - 向当前应用程序添加社交提要功能. 举例说明 OTP 伞形应用程序，包含 3 个应用程序. 薄凤凰控制器.
* [harakiri](https://github.com/rubencaro/harakiri) - 帮助应用程序自杀.
* [hello_phoenix](https://github.com/bigardone/phoenix-react-redux-template) - 带有 Phoenix、React 和 Redux 的 SPA 应用程序模板.
* [hexpm](https://github.com/hexpm/hexpm) - 使用 Phoenix 1.3 构建的十六进制包管理器站点的源代码.
* [kaisuu](https://github.com/SebastianSzturo/kaisuu) - 在 Twitter 上实时观看日本的汉字用法.
* [koans](https://github.com/dojo-toulouse/elixir-koans) - 通过使用 elixir-koans 来学习 Elixir.
* [lolcat](https://github.com/restartr/ex-lolcat)  - 这是busyloop/lolcat的克隆. 但它不支持动画和原版的一些功能.
* [magnetissimo](https://github.com/sergiotapia/magnetissimo) - 为所有流行的 torrent 站点编制索引并将其保存到本地数据库的 Web 应用程序.
* [oop](https://github.com/wojtekmach/oop) - 长生不老药中的 DOP！
* [phoenix-chat-example](https://github.com/dwyl/phoenix-chat-example)  - 在凤凰城为初学者构建聊天应用程序的分步示例/教程. 涵盖测试、文档和部署. 凤凰`1.5.3`.
* [phoenix-ecto-encryption-example](https://github.com/dwyl/phoenix-ecto-encryption-example) - 一个全面的示例/教程，向人们展示如何使用 Ecto 类型在 Phoenix 1.4 应用程序中透明地加密/解密数据.
* [phoenix-flux-react](https://github.com/fxg42/phoenix-flux-react) - Phoenix Channels、GenEvents、React 和 Flux 的实验.
* [phoenix-liveview-counter-tutorial](https://github.com/dwyl/phoenix-liveview-counter-tutorial) - 在 Phoenix `1.5.3` 和 LiveView `0.14.1` 中构建实时计数器的完整初学者分步教程.
* [phoenix-todo-list-tutorial](https://github.com/dwyl/phoenix-todo-list-tutorial) - 一个完整的初学者分步教程，用于在 Phoenix `1.5.3` 中从头开始构建待办事项列表.
* [portal](https://github.com/josevalim/portal) - Elixir 中分布式门户数据传输应用的射击容错门.
* [real world example app](https://github.com/gothinkster/elixir-phoenix-realworld-example-app) - Elixir / Phoenix 实现 [RealWorld.io](https://realworld.io/) 后端规格 - 中型克隆.
* [rollex](https://gitlab.com/olhado/rollex) - Elixir 库使用 Pratt Parser 算法来计算掷骰子.
* [rubix](https://github.com/YellowApple/Rubix) - 一个用于 Elixir 的非常简单（并且几乎无法运行）的 Ruby 运行程序.
* [stranger](https://github.com/cazrin/stranger) - Elixir Phoenix 应用程序可与随机选择的陌生人匿名聊天.
* [tilex](https://github.com/hashrocket/tilex) - 使用 Phoenix 1.3 构建的 Hashrocket 的 TIL 网站的源代码.
* [weather](https://github.com/tacticiankerala/elixir-weather) - 使用 Elixir 构建的命令行天气应用程序.

## Feature Flags and Toggles
*管理功能切换的库（又名功能标志）：可以在运行时通过某些界面切换的开/关值*

* [ConfigCat](https://github.com/configcat/elixir-sdk) - 用于 ConfigCat 托管功能标志服务的 Elixir SDK.
* [flippant](https://github.com/sorentwo/flippant) - Feature flipping for the Elixir world.
* [fun_with_flags](https://github.com/tompave/fun_with_flags)  - 使用 Redis 或 Ecto 实现持久性的功能切换库、用于速度的 ETS 缓存和用于分布式缓存破坏的 PubSub. 带有 Phoenix 和 Plug 的管理 Web UI.
* [molasses](https://github.com/securingsincity/molasses) - 使用 redis 或 SQL（使用 Ecto）作为支持服务的功能切换库.

## Feeds
*使用 RSS 或 ATOM 等提要的库.*

* [atomex](https://github.com/Betree/atomex) - 专注于标准合规性、安全性和可扩展性的 ATOM 提要构建器.
* [feeder](https://github.com/michaelnisi/feeder) - 解析 RSS 和 Atom 提要.
* [feeder_ex](https://github.com/manukall/feeder_ex)  - RSS 提要解析器. 馈线的简单包装.
* [feedme](https://github.com/umurgdk/elixir-feedme) - RSS/Atom 解析器建立在 erlang 的 xmerl xml 解析器上.

## Files and Directories
*用于处理文件和目录的库和实现.*

* [Belt](https://bitbucket.org/pentacent/belt/) - 支持 SFTP、S3 和文件系统存储的可扩展文件上传库.
* [cassius](https://github.com/jquadrin/cassius) - 监控 Linux 文件系统事件.
* [dir_walker](https://github.com/pragdave/dir_walker) - DirWalker 懒惰地遍历一个或多个目录树，深度优先，返回连续的文件名.
* [elixgrep](https://github.com/bbense/elixgrep) - 对文件集合进行 Hadoop 风格的 Map/Reduce 操作的框架.
* [ex_guard](https://github.com/slashmili/ex_guard) - ExGuard 是一个混合命令，用于处理文件系统修改事件.
* [ex_minimatch](https://github.com/gniquil/ex_minimatch) - 不走树的环球路径！
* [exfile](https://github.com/keichan34/exfile) - Elixir 和 Plug 中的文件上传处理、持久化和处理.
* [exfswatch](https://github.com/falood/exfswatch) - 基于 __fs__ 的文件更改观察器包装器.
* [eye_drops](https://github.com/rkotze/eye_drops) - 可配置的混合任务来观察文件变化并运行相应的命令.
* [format_parser.ex](https://github.com/ahtung/format_parser.ex) - Elixir 库，用于确定文件的类型和格式.
* [fs](https://github.com/synrc/fs) - Erlang 文件系统侦听器.
* [fwatch](https://github.com/ryo33/fwatch-ex) - 基于 __fs__ 的基于回调的文件观察器.
* [librex](https://github.com/ricn/librex) - 使用 LibreOffice 将办公文档转换为其他格式的 Elixir 库.
* [Radpath](https://github.com/lowks/Radpath) - Elixir 的路径库，受 Python 的 Enhpath 启发.
* [sentix](https://github.com/whitfin/sentix) - 基于 fswatch 的 Elixir 跨平台文件观察器.
* [sizeable](https://github.com/arvidkahl/sizeable) - 一个 Elixir 库，使文件大小易于阅读.
* [waffle](https://github.com/elixir-waffle/waffle) - 灵活的 Elixir 文件上传和附件库.
* [zarex](https://github.com/ricn/zarex) - Elixir 的文件名清理.

## Formulars
*处理网络公式和类似的东西.*

* [forms](https://github.com/spawnproc/forms) - Erlang Business Documents Generator.

## Framework Components
*来自 Web 开发框架的独立组件.*

* [absinthe_plug](https://github.com/absinthe-graphql/absinthe_plug) - 对苦艾酒的插件支持.
* [addict](https://github.com/trenpixster/addict) - Phoenix Framework 的用户身份验证.
* [airbrake_plug](https://github.com/romul/airbrake_plug) - 向 Airbrake 报告 Plug 堆栈或任何内容中的错误.
* [ashes](https://github.com/nickgartmann/ashes) - Phoenix web 框架的代码生成工具.
* [better_params](https://github.com/sheharyarn/better_params) - Elixir Plug 用于 Web 应用程序中更清晰的请求参数.
* [blaguth](https://github.com/lexmag/blaguth) - Plug 应用程序中的基本访问身份验证.
* [commanded](https://github.com/slashdotdash/commanded) - 用于命令查询职责分离 (CQRS) 应用程序的命令处理中间件.
* [cors_plug](https://github.com/mschae/cors_plug) - 一个 Elixir 插件，将 CORS 标头添加到请求并响应预检请求 (OPTIONS).
* [corsica](https://github.com/whatyouhide/corsica) - 用于处理 CORS 请求的 Elixir 库.
* [crudex](https://github.com/bitgamma/crudex) - Phoenix 和 Ecto 的 CRUD 实用程序.
* [dayron](https://github.com/inaka/Dayron) - 一个类似于 `Ecto.Repo` 的存储库，用于处理 REST API 请求而不是数据库.
* [ex_admin](https://github.com/smpallen99/ex_admin) - ExAdmin 是 Elixir 和 Phoenix Framework 的自动管理包.
* [exdjango](https://github.com/nicksanders/exdjango) - 一些用于 django 的 Elixir 库.
* [exrecaptcha](https://github.com/adanselm/exrecaptcha) - Elixir 应用程序的简单 reCaptcha 显示/验证代码.
* [filterable](https://github.com/omohokcoj/filterable) - 受 Rails has_scope 启发的 Phoenix 框架的简单查询参数过滤.
* [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - 一个 Elixir 绑定 [libgraphqlparser](https://github.com/graphql/libgraphqlparser).
* [http_router](https://github.com/sugar-framework/elixir-http-router) - 带有各种宏的 HTTP 路由器，以帮助开发您的应用程序和组织您的代码.
* [kerosene](https://github.com/elixirdrops/kerosene) - Ecto 和 Phoenix 的分页.
* [mellon](https://github.com/sajmoon/mellon) - Plug 应用程序的身份验证模块.
* [multiverse](https://github.com/Nebo15/multiverse) - 允许通过 API 请求/响应网关添加版本兼容性层的插件.
* [params](https://github.com/vic/params) - 使用 Ecto 来强制/验证参数结构，类似于 Rails 的强参数.
* [passport](https://github.com/opendrops/passport) - Passport 为 Phoenix 应用程序提供身份验证.
* [phoenix_ecto](https://github.com/phoenixframework/phoenix_ecto) - Phoenix 和 Ecto 集成.
* [phoenix_haml](https://github.com/chrismccord/phoenix_haml) - Haml 的 Phoenix 模板引擎.
* [phoenix_html](https://github.com/phoenixframework/phoenix_html) - 用于处理 HTML 字符串和模板的 Phoenix.HTML 函数.
* [phoenix_html_sanitizer](https://github.com/elixirstatus/phoenix_html_sanitizer) - Phoenix 的 HTML Sanitizer 集成.
* [phoenix_html_simplified_helpers](https://github.com/ikeikeikeike/phoenix_html_simplified_helpers) - phoenix html 的一些帮助程序（截断、time_ago_in_words、number_with_delimiter）.
* [phoenix_linguist](https://github.com/jxs/phoenix_linguist)  - 一个集成了 Phoenix 和 Linguist 的项目，提供了一个插件和视图助手. 它看起来被遗弃了：它的最后一次提交是在 2015 年，它的 CI 运行 Elixir 1.0.3.
* [phoenix_live_reload](https://github.com/phoenixframework/phoenix_live_reload) - 为 Phoenix 提供实时重新加载功能.
* [phoenix_meta_tags](https://github.com/hlongvu/phoenix_meta_tags) - 为网站生成元标记.
* [phoenix_pubsub_postgres](https://github.com/opendrops/phoenix-pubsub-postgres) - 用于 Phoenix 应用程序的 Postgresql PubSub 适配器.
* [phoenix_pubsub_rabbitmq](https://github.com/pma/phoenix_pubsub_rabbitmq) - 用于 Phoenix 的 PubSub 层的 RabbitMQ 适配器.
* [phoenix_pubsub_redis](https://github.com/phoenixframework/phoenix_pubsub_redis) - 用于 Phoenix 框架的 Redis PubSub 适配器.
* [phoenix_pubsub_vernemq](https://github.com/larshesel/phoenix_pubsub_vernemq) - 用于 Phoenix 框架的 VerneMQ MQTT pubsub 适配器.
* [phoenix_slime](https://github.com/slime-lang/phoenix_slime) - 对 Phoenix 的 Slim 模板支持.
* [phoenix_token_auth](https://github.com/manukall/phoenix_token_auth)  - Phoenix 的令牌认证解决方案. 对 API 或单页应用程序很有用.
* [phx_component_helpers](https://github.com/cblavier/phx_component_helpers) - 可扩展的 live_components，没有样板.
* [plug](https://github.com/elixir-lang/plug) - Web 应用程序之间可组合模块的规范和便利.
* [plug_accesslog](https://github.com/mneudert/plug_accesslog) - 用于写入访问日志的插件.
* [plug_and_play](https://github.com/henrik/plug_and_play) - 使用较少的样板设置 Plug 应用程序.
* [plug_auth](https://github.com/bitgamma/plug_auth) - 认证相关插件的集合.
* [plug_canonical_host](https://github.com/remiprev/plug_canonical_host) - 插入以确保所有请求都来自单个规范主机.
* [plug_checkup](https://github.com/ggpasqualino/plug_checkup) - 用于向您的应用程序添加简单的健康检查的插件.
* [plug_cloudflare](https://github.com/c-rack/plug_cloudflare) - 受 mod_cloudflare 的启发，这个 Elixir 插件将 Cloudflares CF-Connecting-IP HTTP 请求标头解析为 Plug.Conn 的 remote_ip 字段.
* [plug_forward_peer](https://github.com/awetzel/plug_forwarded_peer) - 非常简单的插件，它根据 RFC7239 读取 X-Forwarded-For 或 Forwarded 标头，并用根客户端 ip 填充 conn.remote_ip.
* [plug_fprof](https://github.com/obmarg/plug_fprof) - 向请求添加 fprof 跟踪的插件，以允许轻松分析.
* [plug_graphql](https://github.com/graphql-elixir/plug_graphql) - 凤凰插头集成为 [GraphQL Elixir](http://graphql-elixir.org/).
* [plug_heartbeat](https://github.com/whatyouhide/plug_heartbeat) - 用于响应心跳请求的插件.
* [plug_jwt](https://github.com/bryanjos/plug_jwt) - 用于 JWT 身份验证的插件.
* [plug_password](https://github.com/azranel/plug_password) - 用于添加简单的基于 cookie 的身份验证的插件.
* [plug_rails_cookie_session_store](https://github.com/cconstantin/plug_rails_cookie_session_store) - Rails 兼容插件会话存储.
* [plug_redirect_https](https://github.com/stocks29/plug_redirect_https) - 插入以将 http 请求重定向到反向代理后面的 https 请求.
* [plug_require_header](https://github.com/DevL/plug_require_header) - 要求并提取 HTTP 标头并处理丢失的标头.
* [plug_response_header](https://github.com/c-rack/plug_response_header) - 轻松操作 HTTP 响应标头.
* [plug_ribbon](https://github.com/stnly/plug_ribbon) - 在开发环境中向您的 Web 应用程序注入功能区.
* [plug_secex](https://github.com/techgaun/plug_secex) - 添加各种 HTTP 标头以使 Phoenix/Elixir 应用程序更安全的插件.
* [plug_session_memcached](https://github.com/gutschilla/plug-session-memcached) - 一个非常简单的用于 Elixir 插件的 memcached 会话存储.
* [plug_sigaws](https://github.com/handnot2/plug_sigaws) - 针对 Phoenix/Plug 路由的 AWS 签名 V4 身份验证保护（[Docs](https://hexdocs.pm/plug_sigaws/PlugSigaws.html)).
* [plug_statsd](https://github.com/jeffweiss/plug_statsd) - 用于自动向 statsd 发送计时和计数指标的插件.
* [plugs](https://github.com/sugar-framework/plugs) - Web 应用程序插件中间件的集合.
* [plugsnag](https://github.com/jarednorman/plugsnag) - 针对 Elixir 插件的 Bugsnag 通知程序.
* [raygun](https://github.com/cobenian/raygun) - 捕获错误并将它们发送给 Raygun.
* [react_phoenix](https://github.com/geolessel/react-phoenix) - 在 Phoenix 视图中渲染 React.js 组件，重点是易于安装和 Brunch 兼容性.
* [recaptcha](https://github.com/samueljseay/recaptcha) - 用于 Elixir 应用程序的简单 reCaptcha 2 库.
* [resin](https://github.com/Frost/resin) - Resin 是一个插件，它将为通过它的每个请求添加可配置的延迟，除非在生产中运行.
* [revision_plate_ex](https://github.com/KazuCocoa/revision_plate_ex) - 服务端点的插件应用程序和中间件返回应用程序的修订版.
* [rummage_ecto](https://github.com/Excipients/rummage_ecto) - 用于搜索、排序和分页 Ecto 查询的可配置框架.
* [rummage_phoenix](https://github.com/Excipients/rummage_phoenix) - 用于在 Phoenix 中搜索、排序和分页模型的支持框架，具有 HTML 支持.
* [scaffold](https://github.com/gausby/scaffold) - 基于从 Git-repo 获取的模板创建新项目的混合任务.
* [scrivener](https://github.com/drewolson/scrivener) - 对您的 Ecto 查询进行分页.
* [scrivener_headers](https://github.com/doomspork/scrivener_headers) - 使用 Scrivener 和 HTTP 标头对 API 响应进行分页的助手.
* [scrivener_html](https://github.com/mgwidmann/scrivener_html) - 为使用 Scrivener 的页面结构而构建的助手，可以轻松地为各种 CSS 框架构建 HTML 输出.
* [sentinel](https://github.com/britton-jb/sentinel) - Phoenix 扩展监护人的身份验证框架，具有路由和其他基本功能.
* [surface](https://github.com/msaraiva/surface) - Phoenix 的服务器端渲染组件库.
* [torch](https://github.com/infinitered/torch)  - Torch 是 Phoenix 应用程序的快速管理生成器. 它使用生成器而不是 DSL 来确保代码保持可维护性.
* [trailing_format_plug](https://github.com/mschae/trailing_format_plug) - 一个 Elixir 插件，用于支持使用类似 Rails 的尾随格式的旧 API.
* [turn_the_page](https://hex.pm/packages/turn_the_page) - 用于 Elixir 应用程序的快速、简单和轻量级的分页系统.
* [webassembly](https://github.com/herenowcoder/webassembly) - Elixir 的 Web DSL.
* [weebo](https://github.com/stevenschobert/weebo) - 一个用于 Elixir 的 XML-RPC 解析器/格式化器，完全支持数据类型映射.

## Frameworks
*Web 开发框架.*

* [exelli](https://github.com/pigmej/exelli) - 带有一些糖语法优点的 Elli Elixir 包装器.
* [kitto](https://github.com/kittoframework/kitto) - 交互式仪表板的框架.
* [n2o](https://github.com/synrc/n2o) - 分布式应用服务器.
* [nitro](https://github.com/synrc/nitro) - 与氮兼容的 Web 框架.
* [phoenix](https://github.com/phoenixframework/phoenix) - Elixir Web 框架针对具有实时功能的全功能、容错应用程序.
* [placid](https://github.com/slogsdon/placid) - 一个 REST 工具包，用于使用 Elixir 构建高度可扩展和容错的 HTTP API.
* [rackla](https://github.com/AntonFagerberg/rackla) - Elixir 中的 API 网关.
* [relax](https://github.com/AgilionApps/relax) - 一个简单的 Elixir 实现 [jsonapi.org](http://jsonapi.org) 服务器.
* [rest](https://github.com/synrc/rest) - 带有类型化 JSON 的微型 REST 框架.
* [RIG](https://github.com/Accenture/reactive-interaction-gateway) - 为无状态微服务创建低延迟、交互式用户体验.
* [sugar](https://github.com/sugar-framework/sugar) - Elixir 的模块化 Web 框架.
* [trot](https://github.com/hexedpackets/trot) - Elixir 网络微框架.

## Games
*游戏库和实现.*

* [Binbo](https://github.com/DOBRO/binbo) - A chess representation written in Erlang using [Bitboards](https://www.chessprogramming.org/Bitboards)，准备在游戏服务器上使用.
* [entice](https://github.com/entice/entice) - 分布式实体-组件-系统框架，提供自己的 MMORPG 服务器示例.
* [mines](https://github.com/kevlar1818/mines) - 终端中的扫雷艇克隆.
* [vim_snake](https://github.com/theanht1/vim_snake) - 经典的多人蛇游戏，带有使用 Phoenix 框架构建的 Vim 风格的按键绑定.

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [distance_api_matrix](https://github.com/C404/distance-matrix-api) - 通过谷歌距离矩阵 api 提供距离和航向计算.
* [geo](https://github.com/bryanjos/geo) - Elixir 的 GIS 功能集合.
* [geocalc](https://github.com/yltsrc/geocalc) - 计算纬度/经度点之间的距离、方位等.
* [geocoder](https://github.com/knrz/geocoder) - 具有内置缓存的简单、高效的地理编码器/反向地理编码器.
* [geohash](https://github.com/polmuz/elixir-geohash) - Geohash 编码/解码库.
* [geohash_nif](https://github.com/wstucco/geohash_nif/) - 替代作为 NIF 实现的 Geohash 编码/解码库.
* [geohax](https://github.com/evuez/geohax) - 使用邻居查找器进行 Geohash 编码和解码.
* [geoip](https://github.com/navinpeiris/geoip) - 查找给定 IP、主机名或“Plug.Conn”的地理位置.
* [geolix](https://github.com/mneudert/geolix) - MaxMind GeoIP2 数据库阅读器/解码器.
* [geonames](https://github.com/pareeohnos/geonames-elixir) - 一个围绕 GeoNames API 的简单 Elixir 包装器.
* [ip2location](https://github.com/nazipov/ip2location-elixir) - IP2Location 数据库的 Elixir 库.
* [ipgeobase](https://github.com/sergey-chechaev/elixir_ipgeobase) - 通过 IP 地址查找俄罗斯和乌克兰城市，并为其他国家/地区查找国家/地区.
* [proj](https://github.com/CandyGumdrop/proj) - 使用 OSGeo 的 PROJ.4 的 Elixir 坐标转换库.
* [segseg](https://github.com/pkinney/segseg_ex) - 段间相交分类器和计算器.
* [topo](https://github.com/pkinney/topo) - Elixir 的几何库，用于计算两个几何之间的空间关系.
* [wheretz](https://github.com/UA3MQJ/wheretz) - Elixir 版本的 Ruby gem，用于按地理坐标查找时区.

## GUI
*用于编写图形用户界面的库.*

* [scenic](https://github.com/boydm/scenic) - 便携式 2D UI 框架.

## Hardware
*硬件相关的东西，如 I/O 接口等.*

* [elixir_ale](https://github.com/fhunleth/elixir_ale) - Elixir 访问硬件 I/O 接口，例如 GPIO、I2C 和 SPI.
* [nerves](https://github.com/nerves-project/nerves) - 为 Raspberry Pi 和 BeagleBone Black 等平台构建固件的框架.

## HTML
*使用 HTML 的库和实现（对于 xml 工具，请访问 [XML](#xml) 部分）.*

* [exquery](https://github.com/rozap/exquery) - 用于解析 HTML 和查询其中元素的库.
* [floki](https://github.com/philss/floki) - 一个简单的 HTML 解析器，可以使用类似选择器的 CSS 进行搜索.
* [html_sanitize_ex](https://github.com/rrrene/html_sanitize_ex) - Elixir 的 HTML 消毒剂.
* [modest_ex](https://github.com/f34nk/modest_ex) - 使用 CSS 选择器对 html 字符串进行管道转换的库，例如 find()、prepend()、append()、replace() 等.
* [myhtmlex](https://github.com/Overbryd/myhtmlex) - lexborisov 的 myhtml 的 Elixir/Erlang 绑定.
* [readability](https://github.com/keepcosmos/readability) - 可读性用于提取和整理文章.
* [texas](https://gitlab.com/dgmcguire/texas) - Texas 是使用服务器端渲染和服务器端虚拟 DOM 差异/补丁更新客户端的强大抽象.
* [tidy_ex](https://github.com/f34nk/tidy_ex) - Elixir 绑定到 HTML 工具的老祖宗 [http://www.html-tidy.org](http://www.html-tidy.org).

## HTTP
*用于处理 HTTP 和抓取网站的库.*

* [Ace](https://github.com/CrowdHailer/Ace) - HTTP Web 服务器和客户端，支持 http1 和 http2.
* [bolt](https://github.com/SebastianSzturo/bolt) - 简单快速的 http 代理.
* [cauldron](https://github.com/meh/cauldron) - 作为库的 HTTP/SPDY 服务器.
* [Crawler](https://github.com/fredwu/crawler) - Elixir 中的高性能网络爬虫.
* [Crawly](https://github.com/oltarasenko/crawly) - Elixir 的高级网络抓取和抓取框架.
* [elli](https://github.com/knutin/elli) - Elli 是一个 Web 服务器，您可以在 Erlang 应用程序中运行以公开 HTTP API.
* [etag_plug](https://github.com/sascha-wolf/etag_plug) - 一个简单易用的浅 ETag 插头.
* [explode](https://github.com/pkinney/explode) - 一个简单的实用程序，用于在基于插件和 Phoenix 的应用程序中响应标准 HTTP/JSON 错误有效负载.
* [exvcr](https://github.com/parroty/exvcr) - Elixir 的 HTTP 请求/响应记录库，受 VCR 启发.
* [finch](https://github.com/keathley/finch) - 一个注重性能的 HTTP 客户端，建立在 Mint 和 NimblePool 之上.
* [fuzzyurl](https://github.com/gamache/fuzzyurl.ex)  - 用于解析、构造和通配符匹配 URL 的 Elixir 库. 也可用于 [Ruby](https://github.com/gamache/fuzzyurl.rb) 和 [JavaScript](https://github.com/gamache/fuzzyurl.js).
* [gun](https://github.com/ninenines/gun) - 用于 Erlang/OTP 的 HTTP/1.1、HTTP/2 和 Websocket 客户端.
* [hackney](https://github.com/benoitc/hackney) - 用 Erlang 编写的简单 HTTP 客户端.
* [http](https://github.com/slogsdon/http) - Elixir 的 HTTP 服务器.
* [http_digex](https://github.com/techgaun/http_digex) - 创建基本摘要 HTTP 身份验证标头的模块.
* [http_proxy](https://github.com/KazuCocoa/http_proxy) - 多端口 HTTP 代理.
* [httpoison](https://github.com/edgurgel/httpoison) - 另一个由 hackney 提供支持的 Elixir 的 HTTP 客户端.
* [httpotion](https://github.com/myfreeweb/httpotion) - 基于 ibrowse 的 Elixir 花式 HTTP 客户端.
* [ivar](https://github.com/swelham/ivar) - 围绕 HTTPoison 的轻量级包装器，提供了一种流畅且可组合的方式来构建 http 请求.
* [lhttpc](https://github.com/talko/lhttpc) - 在 Erlang 中实现的轻量级 HTTP/1.1 客户端.
* [mint](https://github.com/ericmj/mint) - Elixir 的功能性 HTTP 客户端，支持 HTTP/1 和 HTTP/2.
* [mnemonic_slugs](https://github.com/devshane/mnemonic_slugs) - Elixir 中令人难忘的助记符生成器.
* [mochiweb](https://github.com/mochi/mochiweb) - MochiWeb 是一个用于构建轻量级 HTTP 服务器的 Erlang 库.
* [neuron](https://github.com/uesteibar/neuron) - Elixir 的 GraphQL 客户端.
* [plug_wait1](https://github.com/wait1/plug_wait1) - 用于 wait1 协议的插头适配器.
* [raxx](https://github.com/CrowdHailer/raxx) - HTTP 网络服务器、框架和客户端的接口.
* [river](https://github.com/peburrows/river) - 轻量级和闪电般快速的 HTTP/2 客户端.
* [scrape](https://github.com/Anonyfox/elixir-scrape) - 轻松抓取任何网站、文章或 RSS/Atom Feed.
* [sparql_client](https://github.com/marcelotto/sparql_client) - 一种 [SPARQL protocol](https://www.w3.org/TR/sparql11-protocol/) Elixir 的客户.
* [spell](https://github.com/MyMedsAndMe/spell) - 拼写是 [Web Application Messaging Protocol](http://wamp-proto.org/) (WAMP) 客户端在 Elixir 中的实现.
* [tesla](https://github.com/teamon/tesla) - HTTP 客户端库，支持中间件和多个适配器.
* [Tube](https://github.com/narrowtux/Tube) - 纯 Elixir WebSocket 客户端库.
* [uri_query](https://github.com/shhavel/uri_query) - URI 编码 Elixir 中嵌套的 GET 参数和数组值.
* [uri_template](https://github.com/pezra/ex-uri-template) - 用于 Elixir 的符合 RFC6570 的 URI 模板处理器.
* [web_socket](https://github.com/slogsdon/plug-web-socket) - 探索插件应用程序的独立库，以轻松采用 WebSockets.
* [webdriver](https://github.com/stuart/elixir-webdriver)  - 这是 WebDriver 协议客户端的实现. 它目前支持 PhantomJS、FireFox、ChromeDriver 和远程 webdriver 服务器（例如 Selenium）.
* [yuri](https://github.com/kemonomachi/yuri) - 用于表示 URI 的简单结构.

## Images
*用于处理和操作图像的库.*

* [alchemic_avatar](https://github.com/zhangsoledad/alchemic_avatar) - Elixir 库，用于从字符串生成字母头像.
* [artifact](https://github.com/doomspork/artifact) - Elixir 的文件上传和即时处理.
* [bump](https://github.com/evanfarrar/ex_bump) - 纯 Elixir 中的 BMP 文件编写器.
* [chunky_svg](https://github.com/mmmries/chunky_svg) - 使用 SVG 绘制事物的库.
* [cloudex](https://github.com/smeevil/cloudex) - Cloudex 是一个 Elixir 库，可以将图像文件或 url 上传到 Cloudinary.
* [eikon](https://github.com/tchoutri/Eikon) - 一个 Elixir 库，为图像文件提供只读界面.
* [elixir_exif](https://github.com/sschneider1207/ElixirExif) - Parse exif tags and thumbnail data from jpeg files.
* [ex_image_info](https://github.com/rNoz/ex_image_info) - 一个 Elixir 库，用于解析图像（二进制文件）并获取一组图像格式的维度、检测到的 MIME 类型和整体有效性.
* [exexif](https://github.com/pragdave/exexif) - 纯 Elixir 库，用于从 jpeg 文件中提取 TIFF 和 EFIX 元数据.
* [exfavicon](https://github.com/ikeikeikeike/exfavicon) - 用于发现收藏夹图标的 Elixir 库.
* [identicon](https://github.com/rbishop/identicon) - 用于生成 5x5 标识的 Elixir 库.
* [image64](https://hex.pm/packages/image64) - 用于处理 base64 编码图像的工具.
* [imagineer](https://github.com/SenecaSystems/imagineer) - Elixir 中的图像解析.
* [imgex](https://github.com/ianwalter/imgex) - 用于在 Elixir 中生成 imgix URL 的非官方客户端库.
* [mogrify](https://github.com/route/mogrify) - ImageMagick 命令行的 Elixir 包装器.
* [png](https://github.com/yuce/png)  - 用于创建 PNG 图像的纯 Erlang 库. 它目前可以创建 8 位和 16 位 RGB、带 alpha 的 RGB、索引、灰度和带 alpha 图像的灰度.
* [thumbnex](https://github.com/talklittle/thumbnex) - 从图像和视频截图创建缩略图.

## Instrumenting / Monitoring
*用于收集和导出指标的库.*

* [appsignal-elixir](https://github.com/appsignal/appsignal-elixir/) - 从 Elixir 应用程序收集错误和性能数据并将其发送到 [AppSignal](https://appsignal.com/).
* [elixometer](https://github.com/pinterest/elixometer) - exometer 周围的轻型 Elixir 包装纸.
* [erlang-metrics](https://github.com/benoitc/erlang-metrics) - Erlang 中不同度量系统的通用接口.
* [exometer](https://github.com/Feuerlabs/exometer) - Erlang 中的基本测量对象和探针行为.
* [folsom_ddb](https://github.com/dalmatinerdb/folsom_ddb) - 用于存储 Folsom 指标的 DalmatinerDB 后端.
* [graphitex](https://github.com/msoedov/graphitex) - Elixir 的石墨/碳客户端.
* [instream](https://github.com/mneudert/instream) - Elixir 的 InfluxDB 驱动程序.
* [instrumental](https://github.com/undeadlabs/instrumental-ex) - Elixir 客户端 [Instrumental](https://instrumentalapp.com/).
* [newrelic.ex](https://github.com/romul/newrelic.ex) - 从您的 Elixir/Phoenix 应用程序收集指标并将它们发送到 [NewRelic](https://newrelic.com/).
* [prometheus](https://github.com/deadtrickster/prometheus.erl) - [Prometheus.io](https://prometheus.io) Erlang中的监控系统和时间序列数据库客户端.
* [prometheus-ecto](https://github.com/deadtrickster/prometheus-ecto) - prometheus.ex 的 Ecto 仪器.
* [prometheus-phoenix](https://github.com/deadtrickster/prometheus-phoenix) - prometheus.ex 的 Phoenix 仪器.
* [prometheus-plugs](https://github.com/deadtrickster/prometheus-plugs) - prometheus.ex 的插头仪器/出口商.
* [prometheus.ex](https://github.com/deadtrickster/prometheus.ex) - 长生不老药友好 [Prometheus.io](https://prometheus.io) 监控系统和时间序列数据库客户端.
* [prometheus_process_collector](https://github.com/deadtrickster/prometheus_process_collector) - Prometheus 收集器，可导出进程指标的当前状态，包括 CPU、内存、文件描述符使用情况和本机线程数以及进程启动和启动时间.
* [spandex](https://github.com/spandex-project/spandex) - 最初为 Datadog APM 开发的平台无关跟踪库.
* [telemetry](https://github.com/beam-telemetry/telemetry) - 用于指标和仪器的动态调度库.
* [wobserver](https://github.com/shinyscorpion/wobserver) - 基于 Web 的指标、监控和观察者.

## JSON
*使用 JSON 的库和实现.*

* [exjson](https://github.com/guedes/exjson) - Elixir 中的 JSON 解析器和生成器.
* [ja_serializer](https://github.com/AgilionApps/ja_serializer) - Elixir 中的 JSONAPI.org 序列化.
* [jason](https://github.com/michalmuskala/jason) - 纯 Elixir 中超快的 JSON 解析器和生成器.
* [jazz](https://github.com/meh/jazz) - 另一个在 Elixir 中处理 JSON 的库.
* [joken](https://github.com/bryanjos/joken) - 编码和解码 JSON 网络令牌.
* [jose](https://github.com/potatosalad/erlang-jose) - 用于 Erlang 和 Elixir 的 JSON 对象签名和加密 (JOSE).
* [json](https://github.com/cblage/elixir-json) - Elixir 的原生 JSON 库.
* [json_pointer](https://github.com/xavier/json_pointer) - RFC 6901 的实现，它定义了用于标识 JSON 文档中特定值的字符串语法.
* [json_stream_encoder](https://github.com/TreyE/json_stream_encoder) - JsonStreamEncoder 是一个流式编码器，用于将 JSON 流式传输到 Elixir 中的 IOish 事物.
* [json_web_token_ex](https://github.com/garyf/json_web_token_ex) - JSON 网络令牌 (JWT) 标准跟踪 (RFC 7519) 的 Elixir 实现.
* [jsonapi](https://github.com/jeregrine/jsonapi) - 将您的数据模型渲染成的项目 [JSONAPI Documents](http://jsonapi.org/format/).
* [jsx](https://github.com/talentdeficit/jsx) - 一个用于消费、生产和操作 json 的 Erlang 应用程序.
* [jsxn](https://github.com/talentdeficit/jsxn) - jsx 但有地图.
* [jwalk](https://github.com/jr0senblum/jwalk) - 用于处理 JSON 的 Erlang 表示的辅助模块.
* [jwtex](https://github.com/mschae/jwtex) - 用于编码和解码的库 [JWT tokens](http://jwt.io/).
* [poison](https://github.com/devinus/poison) - Poison 是 Elixir 的新 JSON 库，专注于极快的速度，同时又不牺牲简单性、完整性或正确性.
* [tiny](https://github.com/whitfin/tiny) - 用于 Elixir 的小巧、快速且完全兼容的 JSON 解析器.
* [world_json](https://github.com/camshaft/world_json_ex) - elixir/erlang 的 topojson 国家和州/省集合.

## Languages
*建立在 Elixir 之上的语言.*

* [Elchemy](https://github.com/wende/elchemy) - 允许将 Elm 编程语言代码翻译成 Elixir 的编译器.
* [lighthouse_scheme](https://github.com/jwhiteman/lighthouse-scheme) - 在 Elixir 中构建的类似 Lisp 的小型语言和交互式 REPL.
* [Monkey](https://github.com/fabrik42/writing_an_interpreter_in_elixir) - 类似 js 的 Monkey 编程语言的解释器和 REPL 的 Elixir 实现.

## Lexical analysis
*关于词法分析器、词法分析器、扫描器、分词器或编译器.*

* [abnf_parsec](https://github.com/princemaple/abnf_parsec) - ABNF 输入和解析器输出.
* [ex_abnf](https://github.com/marcelog/ex_abnf) - Elixir 中 ABNF 语法的解析器.
* [lex_luthor](https://github.com/jamesotron/lex_luthor) - LexLuthor 是 Elixir 中的一个词法分析器，它使用宏来生成可重用的词法分析器.

## Logging
*记录信息和消息.*

* [bunyan](https://github.com/bunyan-logger/bunyan) - 班扬：一个长生不老药记录员.
* [exlager](https://github.com/khia/exlager) - 长生不老药绑定股票.
* [exsentry](https://github.com/appcues/exsentry) - 登录时出错 [Sentry](https://getsentry.com/).
* [gelf_logger](https://github.com/jschniper/gelf_logger) - 将生成 Graylog 扩展日志格式 (GELF) 消息的 Logger 后端.
* [honeybadger](https://github.com/honeybadger-io/honeybadger-elixir) - 登录时出错 [Honeybadger](https://www.honeybadger.io/).
* [json_logger](https://github.com/LeeroyDing/json_logger) - JSON Logger 是一个以 JSON 格式输出长生不老药日志的记录器后端.
* [lager](https://github.com/basho/lager) - basho.com 的 Erlang/OTP 日志框架.
* [lager_logger](https://github.com/PSPDFKit-labs/lager_logger) - 一个更大的后端，将所有日志消息转发到 Elixir 的 Logger.
* [logfmt](https://github.com/jclem/logfmt-elixir) - Logfmt 是一个用于编码和解码 logfmt 风格的日志行的模块.
* [logger_logstash_backend](https://github.com/marcelog/logger_logstash_backend) - Elixir Logger 的后端，将日志发送到 Logstash UDP 输入.
* [logglix](https://github.com/pragmaticivan/logglix) - 用于将错误发布到 Loggly 的记录器后端.
* [logster](https://github.com/navinpeiris/logster) - 受 Lograge 启发，适用于 Phoenix 和 Plug 应用程序的易于解析的单行日志记录.
* [metrix](https://github.com/rwdaigle/metrix) - 将自定义应用程序指标记录到标准输出以供 Librato 和其他下游处理器使用.
* [mstore](https://github.com/dalmatinerdb/mstore) - MStore 是一个用 erlang 构建的实验性度量存储，主要功能是 open、new、get 和 put.
* [quiet_logger](https://github.com/Driftrock/quiet_logger/pull/1) - 一个简单的插件来抑制健康检查日志（例如：当使用 Kubernetes 时）.
* [rogger](https://github.com/duartejc/rogger) - Elixir logger 在 RabbitMQ 中发布日志消息.
* [rollbax](https://github.com/elixir-addicts/rollbax) - 异常跟踪和记录到 [Rollbar](https://rollbar.com/).
* [slack_logger_backend](https://github.com/craigp/slack_logger_backend) - 用于将错误发布到 Slack 的记录器后端.
* [syslog](https://github.com/Vagabond/erlang-syslog) - 用于通过 syslog(3) 与 syslog 交互的 Erlang 端口驱动程序.
* [timber](https://github.com/timberio/timber-elixir) - Structured logging platform; turns raw text logs into rich structured events.
* [youtrack_logger_backend](https://github.com/unifysell/youtrack_logger_backend) - 一个记录器后端，将消息发布到 [YouTrack](https://www.jetbrains.com/youtrack/) （JetBrains 制作的问题跟踪器）.

## Macros
 *用于更快、更轻松开发的宏. 为您的代码添加糖.*

* [anaphora](https://github.com/sviridov/anaphora-elixir)  - Anaphora 是 Elixir 的回指宏集合. 照应宏是故意从提供给宏的表单中捕获变量（通常是它）的宏.
* [apix](https://github.com/liveforeverx/apix) - 简单的约定和 DSL，用于将 elixir 函数转换为 API，以便以后文档和/或验证.
* [backports](https://github.com/leifg/backports) - 使用 Elixir 1.1 和 1.2 中的新功能.
* [crudry](https://github.com/gabrielpra1/crudry) - Crudry 是一个长生不老药库，用于 Phoenix Contexts 和 Absinthe Resolvers 的 DRYing CRUD.
* [eventsourced](https://github.com/slashdotdash/eventsourced) - 构建功能性的、基于事件的域模型.
* [expat](https://github.com/vic/expat) - 跨 Elixir 库的可重用、可组合模式.
* [guardsafe](https://github.com/DevL/guardsafe) - 宏扩展为可以在保护子句中安全使用的代码.
* [kwfuns](https://github.com/RobertDober/lab42_defkw) - 使用基于语法的关键字参数和默认值创建函数的宏.
* [lineo](https://github.com/camshaft/lineo) - 解析转换以获得准确的行号.
* [mdef](https://github.com/pragdave/mdef) - 在 Elixir 中轻松定义多个函数头.
* [named_args](https://github.com/mgwidmann/named_args) - 允许在 Elixir 中命名 arg 样式参数.
* [ok_jose](https://github.com/vic/ok_jose) - 匹配 `{:ok,_}`、`{:error,_}` 元组或自定义模式的管道 elixir 函数.
* [opus](https://github.com/zorbash/opus) - 可插拔业务逻辑组件的框架.
* [pathex](https://github.com/hissssst/pathex) - 零依赖、超快的功能镜头.
* [pattern_tap](https://github.com/mgwidmann/elixir-pattern_tap) - 用于在使用管道操作符时进入模式匹配的宏.
* [pipe_here](https://github.com/vic/pipe_here) - 轻松地将值传送到任何参数位置.
* [pipe_to](https://github.com/taiansu/pipe_to) - 增强的管道操作符，可以指定目标位置.
* [pipes](https://github.com/batate/elixir-pipes) - 使用 Elixir Pipe 操作符进行更灵活组合的宏.
* [pit](https://github.com/vic/pit) - 在管道内流动时转换值.
* [rebind](https://github.com/camshaft/rebind) - 为 Erlang 重新绑定解析转换.
* [rulex](https://github.com/awetzel/rulex) - 使用 Elixir 模式匹配的简单规则处理程序.
* [shorter_maps](https://github.com/meyercm/shorter_maps)  - 地图速记的 ~M 印记.  `~M{id name} ~&gt; %{id: id, name: name}`.
* [unsafe](https://github.com/whitfin/unsafe) - 为 Elixir 函数生成简单的不安全 (!) 绑定.

## Markdown
*使用 Markdown 等的库和工具.*

* [cmark](https://github.com/asaaki/cmark.ex) - CommonMark 的 Elixir NIF（在 C 中），一个遵循 CommonMark 规范的解析器.
* [discount](https://github.com/asaaki/discount.ex) - Elixir NIF 折扣，Markdown 解析器.
* [earmark](https://github.com/pragdave/earmark) - Elixir 的 Markdown 解析器.
* [Markdown](https://github.com/devinus/markdown) - Implemented entirely as a NIF binding to the Hoedown library.
* [Pandex](https://github.com/filterkaapi/pandex)  - Pandoc 的轻量级 Elixir 包装器. 将 Markdown、CommonMark、HTML、Latex、HTML、HTML5、opendocument、rtf、texttile、asciidoc 相互转换.

## Miscellaneous
*不属于上述类别的有用库或工具.*

* [address_us](https://github.com/smashedtoatoms/address_us) - 用于将美国地址解析为各个部分的库.
* [AlloyCI](https://github.com/AlloyCI/alloy_ci) - AlloyCI 是一个持续集成、部署和交付协调器，用 Elixir 编写，它利用 GitLab CI Runner 及其作为执行器的功能来准备和运行您的管道.
* [Apex](https://github.com/bjro/apex) - Elixir 的精美打印.
* [AtomVM](https://github.com/bettio/AtomVM) - AtomVM 允许在嵌入式设备（如 ESP32 和 STM32 微控制器）上运行 Elixir/Erlang 代码.
* [bupe](https://github.com/milmazz/bupe) - EPUB 生成器和解析器.
* [charm](https://github.com/tomgco/elixir-charm) - 使用 ANSI 终端字符书写颜色和光标位置.
* [codec-beam](https://github.com/hkgumbs/codec-beam) - 从 Haskell 生成 Erlang VM 字节码.
* [Countries](https://github.com/SebastianSzturo/countries) - 国家/地区是 ISO 3166 标准中每个国家/地区的各种有用信息的集合.
* [countriex](https://github.com/navinpeiris/countriex) - 一个纯粹的万能药国家数据提供者，包含 ISO 3166 中每个国家的各种信息.
* [dye](https://github.com/Kabie/dye) - 用于染色终端输出的库.
* [dynamic_compile](https://github.com/okeuday/dynamic_compile) - 从字符串输入编译和加载 Erlang 模块.
* [ecto_autoslug_field](https://github.com/sobolevn/ecto_autoslug_field) - 自动为您的 Ecto 模型创建 slug.
* [egaugex](https://github.com/Brightergy/egaugex) - 客户端从 egauge 设备获取和解析实时数据.
* [elixir-browser](https://github.com/tuvistavie/elixir-browser) - Elixir 的浏览器检测.
* [epub_cover_extractor](https://github.com/zelazna/epub_cover_extractor) - 从 EPUB 文件中提取封面.
* [erlang_term](https://github.com/okeuday/erlang_term) - 提供 Erlang 术语的内存大小，忽略它们的存储位置.
* [ex2ms](https://github.com/ericmj/ex2ms) - 翻译 Elixir 函数以匹配用于 `ets` 的规范.
* [ex_phone_number](https://github.com/socialpaymentsbv/ex_phone_number) - 格式化、规范化和验证电话号码.
* [ex_rated](https://github.com/grempe/ex_rated) - 简单灵活的 API 或任何东西的速率限制.
* [exfcm](https://github.com/Hajto/ExFCM) - 用于发布 Firebase 云消息的简单包装器.
* [exldap](https://github.com/jmerriweather/exldap) - 用于使用 Elixir 的 LDAP 的模块.
* [exlibris](https://github.com/pragdave/exlibris) - 随机库函数的集合.
* [expool](https://github.com/whitfin/expool) - Elixir 中用于并行任务的小型进程池库.
* [exprint](https://github.com/parroty/exprintf) - Elixir 的 printf / sprintf 库，用作 :io.format 的包装器.
* [expyplot](https://github.com/MaxStrange/expyplot) - 使用 matplotlib.pyplot 的绘图/绘图库的 Elixir 接口.
* [exquisite](https://github.com/meh/exquisite) - Elixir 的类似 LINQ 的 match_spec 生成.
* [exsync](https://github.com/falood/exsync) - 又一个 Elixir 重装器.
* [funnel](https://github.com/chatgris/funnel) - 基于 ElasticSearch 的渗透构建的流式 Elixir API.
* [gen_task](https://github.com/Nebo15/gen_task) - 通用任务行为，有助于在经典 GenStage 中封装工作错误并从中恢复.
* [gimei_ex](https://github.com/ma2gedev/gimei_ex) - 吉美图书馆的灵丹妙药端口.
* [growl](https://github.com/zachallett/growl) - 咆哮的简单包装，OSX 的通知系统.
* [hammer](https://github.com/ExHammer/hammer) - 具有可插拔存储后端的速率限制器，包括 Redis.
* [html_entities](https://github.com/martinsvalin/html_entities) - Elixir 模块，用于解码字符串中的 HTML 实体.
* [huex](https://github.com/xavier/huex) - 飞利浦 Hue 连接灯泡的 Elixir 客户端.
* [japan_municipality_key](https://github.com/hykw/japan_municipality_key) - 用于日本市政密钥转换的 Elixir 库.
* [Jisho-Elixir](https://github.com/nbw/jisho_elixir)  - Jisho.org 的 API 包装器，在线日语词典. 允许用户按单词、符号和/或标签进行搜索（请参阅文档）.
* [keys1value](https://github.com/okeuday/keys1value) - Erlang 为键列表设置关联映射.
* [licensir](https://github.com/unnawut/licensir) - 列出项目中所有已安装软件包的许可证的混合任务.
* [mixgraph](https://github.com/sivsushruth/mixgraph) - 十六进制包的交互式依赖绘图仪.
* [mixstar](https://github.com/ma2gedev/mix-star) - MixStar 已加星的 GitHub 存储库取决于您的项目.
* [netrc](https://github.com/ma2gedev/netrcex) - 读取在 Elixir 中实现的 netrc 文件.
* [notifier](https://hex.pm/packages/notifier) - 桌面通知的可插拔架构.
* [onetime](https://github.com/ryo33/onetime-elixir) - Elixir 的一次性键值存储.
* [pact](https://github.com/BlakeWilliams/pact) - Elixir 中更好的依赖注入，以实现更清晰的代码和测试.
* [phone](https://github.com/fcevado/phone) - 从电话号码中获取有用信息的解析器.
* [porcelain](https://github.com/alco/porcelain) - Porcelain 实现了一种更明智的方法来启动 Elixir 的外部操作系统进程并与之通信.
* [presentex](https://github.com/Cobenian/Presentex) - 基于 HTML/JavaScript 的演示框架的 Elixir.
* [ratekeeper](https://github.com/whitered/ratekeeper) - 速率限制器和速率限制动作调度器.
* [ratx](https://github.com/liveforeverx/ratx) - erlang 应用程序的速率限制器和过载保护.
* [reprise](https://github.com/herenowcoder/reprise) - 简化的 Elixir 模块重新加载器.
* [spawndir](https://github.com/jtmoulia/spawndir) - 从文件系统生成进程.
* [spotify_ex](https://github.com/jsncmgs1/spotify_ex) - Spotify Web API 的 Elixir 包装器.
* [std_json_io](https://github.com/hassox/std_json_io) - 通过 JSON 管理和与 IO 服务器通信的应用程序.
* [url_unroller](https://github.com/semanticart/url_unroller) - Elixir 中的简单 URL 展开器（取消缩短器）.
* [vessel](https://github.com/whitfin/vessel) - Elixir MapReduce 与 Hadoop Streaming 集成的接口.

## Native Implemented Functions
*使用 Erlang NIF 的工具和库.*

* [hsnif](https://github.com/urbanserj/hsnif) - 允许在 Haskell 中编写 Erlang NIF 库的工具.
* [nifty](https://github.com/rossjones/nifty) - 用于设置编写 NIF 时所需样板的帮助脚本.
* [Rustler](https://github.com/hansihe/Rustler)  - 在 Rust 中安全地为 Erlang 或 Elixir 编写 NIF 的库. 没有段错误.

## Natural Language Processing (NLP)
*使用人类（自然）语言的工具和库.*

* [gibran](https://github.com/abitdodgy/gibran) - Gibran 是一个 Elixir 端口 [WordsCounted](https://github.com/abitdodgy/words_counted)，一种从文本中提取有用统计信息的自然语言处理器.
* [Paasaa](https://github.com/minibikini/paasaa) - Elixir 的自然语言检测.
* [Petrovich](https://github.com/petrovich/petrovich_elixir) - Elixir 库，用于变形俄语的名字、姓氏和中间名.
* [Tongue](https://github.com/dannote/tongue) - Nakatani Shuyo 的自然语言检测器的 Elixir 端口.
* [Woolly](https://github.com/pjhampton/woolly) - Woolly 是用于 Elixir 的雄心勃勃的文本挖掘和自然语言处理 API.

## Networking
*用于使用网络相关内容的库和工具.*

* [asn](https://github.com/ephe-meral/asn) - 可用于从 IP 到 AS 再到 ASN 的映射.
* [chatter](https://github.com/dbeck/chatter_ex) - 基于 UDP 多播和 TCP 混合的安全消息广播.
* [download](https://github.com/asiniy/download) - 轻松从互联网下载文件.
* [eio](https://github.com/falood/eio) - engine.io 的 Elixir 服务器.
* [ExPcap](https://github.com/cobenian/expcap) - 用 Elixir 编写的 PCAP 解析器.
* [FlyingDdns](https://gitlab.com/timopallach/FlyingDdns) - 用 elixir 编写的 dyndns 服务器.
* [hades](https://github.com/fklement/hades) - 用 Elixir 编写的 NMAP 包装器.
* [mac](https://github.com/ephe-meral/mac) - 可用于查找以十六进制字符串给出的 MAC 的供应商（根据 IEEE）.
* [pool](https://github.com/slogsdon/pool) - Elixir 的套接字接受器池.
* [reagent](https://github.com/meh/reagent) - 试剂是 Elixir 的套接字受体池.
* [sockerl](https://github.com/Pouriya-Jahanbakhsh/sockerl) - Sockerl 是用于 TCP 协议的高级 Erlang/Elixir 套接字库，并为实现服务器、客户端和客户端连接池提供快速、有用且易于使用的 API.
* [socket](https://github.com/meh/elixir-socket) - Elixir 的套接字包装.
* [sshex](https://github.com/rubencaro/sshex) - Elixir 的简单 SSH 助手.
* [sshkit](https://github.com/bitcrowd/sshkit.ex) - 一个 Elixir 工具包，用于在一个或多个服务器上执行任务，构建在 Erlang 的 SSH 应用程序之上.
* [torex](https://github.com/alexfilatov/torex) - 简单的 Tor 连接库.
* [tunnerl](https://github.com/surik/tunnerl) - SOCKS4 和 SOCKS5 代理服务器.
* [wifi](https://github.com/gausby/wifi) - 用于在 Elixir 中使用本地 Wifi 网络的各种实用功能.
* [wpa_supplicant](https://github.com/fhunleth/wpa_supplicant.ex) - wpa_supplicant 的 Elixir 接口.

## Office
*用于处理办公套件文档的库.*

* [elixlsx](https://github.com/xou/elixlsx) - XLSX 文件编写器.
* [excellent](https://github.com/leifg/excellent) - 一个用于 Elixir 的 OpenXL (Excel 2000) 解析器.
* [xlsxir](https://github.com/kennellroxco/xlsxir)  - Xlsx 文件解析器，支持 ISO 8601 日期格式. 数据被提取到 Erlang 术语存储 (ETS) 表并通过各种函数访问.

## ORM and Datamapping
*实现对象关系映射或数据映射技术的库.*

* [amnesia](https://github.com/meh/amnesia) - Elixir 的 Mnesia 包装器.
* [arbor](https://github.com/coryodaniel/arbor) - Ecto 邻接表和树遍历.
* [arc_ecto](https://github.com/stavro/arc_ecto) - Arc.Ecto 提供了与 Arc 和 Ecto 的集成.
* [atlas](https://github.com/chrismccord/atlas) - Elixir 的对象关系映射器.
* [barrel_ex](https://github.com/jxub/barrel_ex) - [Barrel-db](https://barrel-db.org/) Elixir 中的分布式面向文档的数据库 REST 客户端.
* [Bolt.Sips](https://github.com/florinpatrascu/bolt_sips) - 使用 Bolt 协议的 Elixir Neo4j 驱动程序.
* [boltun](https://github.com/bitgamma/boltun) - 将来自 Postgres LISTEN/NOTIFY 机制的通知转换为回调执行.
* [caylir](https://github.com/mneudert/caylir) - Elixir 的 Cayley 驱动程序.
* [comeonin_ecto_password](https://github.com/vic/comeonin_ecto_password) - 使用 Comeonin 存储加密密码的 Ecto 自定义类型.
* [couchdb_connector](https://github.com/locolupo/couchdb_connector) - CouchDB 的连接器，基于 Erlang 的 JSON 文档数据库.
* [craterl](https://github.com/crate/craterl) - 用于 crate 的 Erlang 客户端.
* [database_url](https://github.com/s-m-i-t-a/database_url) - 解析数据库 URL 并返回关键字列表以与 Ecto 一起使用.
* [datomex](https://github.com/edubkendo/datomex) - Datomic REST API 的 Elixir 驱动程序.
* [ddb_client](https://github.com/dalmatinerdb/ddb_client) - DalmatinerDB 客户端.
* [defql](https://github.com/fazibear/defql) - 创建以 SQL 为主体的 Elixir 函数.
* [dexts](https://github.com/meh/dexts) - Disk Elixir Terms Storage, dest wrapper.
* [diver](https://github.com/novabyte/diver) - 使用 Jinterface 和 Asynchbase Java 客户端查询数据库的 Erlang/Elixir 的 HBase 驱动程序.
* [dproto](https://github.com/dalmatinerdb/dproto) - DalmatinerDB 的协议.
* [dqe](https://github.com/dalmatinerdb/dqe) - DalmatinerDB 查询引擎.
* [ecto](https://github.com/elixir-ecto/ecto) - 针对 Elixir 的数据库包装器和语言集成查询.
* [ecto_cassandra](https://github.com/cafebazaar/ecto-cassandra) - 用于 Ecto 的 Cassandra DB 适配器.
* [ecto_enum](https://github.com/gjaldon/ecto_enum) - Ecto 扩展以支持模型中的枚举.
* [ecto_facade](https://github.com/azranel/ecto_facade) - 允许将写入和读取分开到不同数据库的 Ecto 门面.
* [ecto_factory](https://hex.pm/packages/ecto_factory) - 根据您的 ecto 模式轻松生成结构.
* [ecto_fixtures](https://github.com/DockYard/ecto_fixtures) - 使用 Ecto 的 Elixir 应用程序的固定装置.
* [ecto_lazy_float](https://github.com/joshdholtz/ecto-lazy-float) - Ecto.LazyFloat - 接受二进制和整数的 Ecto.Float.
* [ecto_migrate](https://github.com/xerions/ecto_migrate)  - Ecto 自动迁移库. 它允许为初始和更新迁移生成和运行迁移.
* [ecto_mnesia](https://github.com/Nebo15/ecto_mnesia) - Mnesia Erlang 术语数据库的 Ecto 适配器.
* [ecto_ordered](https://github.com/zovafit/ecto-ordered) - 订购模型的 Ecto 扩展.
* [ecto_paging](https://github.com/Nebo15/ecto_paging) - Ecto 基于光标的分页.
* [ecto_psql_extras](https://github.com/pawurb/ecto_psql_extras) - Ecto PostgreSQL 数据库性能洞察.
* [ecto_rut](https://github.com/sheharyarn/ecto_rut) - 简单而强大的 Ecto 快捷方式来简化和加速开发.
* [ecto_shortcuts](https://github.com/MishaConway/ecto_shortcuts) - ecto 中常见操作的快捷方式.
* [ecto_shortuuid](https://github.com/gpedic/ecto_shortuuid) - 增加了对 Ecto 类型的支持 [ShortUUIDs](https://github.com/gpedic/ex_shortuuid).
* [ecto_validation_case](https://github.com/danielberkompas/ecto_validation_case)  - 简化您的 Ecto 模型验证测试. 受到 shoulda 匹配器的松散启发，但更简单.
* [ectophile](https://github.com/gjaldon/ectophile) - Ecto 扩展可立即支持模型中的文件上传.
* [elastic](https://github.com/radar/elastic) - 一个基于 HTTPotion 的薄板，可帮助您与 Elastic Search 对话.
* [elastix](https://github.com/werbitzky/elastix) - 一个用 Elixir 编写的简单 Elastic REST 客户端.
* [eredis](https://github.com/wooga/eredis) - Erlang Redis client.
* [erlastic_search](https://github.com/tsloughter/erlastic_search) - 用于与 Elastic Search 的休息界面进行通信的 Erlang 应用程序.
* [esqlite](https://github.com/mmzeeman/esqlite) - 用于 sqlite 的 Erlang NIF.
* [eternal](https://github.com/whitfin/eternal) - 让您的 ETS 表永远、安全、轻松地保持活力.
* [ets_map](https://github.com/antipax/ets_map) - 一个 Elixir 包，提供由 ETS 表支持的类似 Map 的接口（Map/Access/Enumerable/Collectable）.
* [eventstore](https://github.com/slashdotdash/eventstore) - 使用 Postgres 进行持久化的 CQRS EventStore，用 Elixir 编写.
* [ex_bitcask](https://github.com/JonGretar/ExBitcask) - Basho 的 Bitcask 键/值存储的 Elixir 包装器.
* [ex_sider](https://github.com/ephe-meral/ex_sider) - Redis 数据结构的 Elixir Map/List/Set 接口（使用 Redix，但这是可配置的）.
* [exleveldb](https://github.com/skovsgaard/exleveldb) - Elixir wrapper around Basho's eleveldb module for LevelDB.
* [exnumerator](https://github.com/KamilLelonek/exnumerator) - Elixir 可枚举类型定义以一种简单的方式用于任何数据库.
* [exredis](https://github.com/artemeff/exredis) - Elixir 的 Redis 客户端.
* [exseed](https://github.com/seaneshbaugh/exseed) - 一个 Elixir 库，它提供了一个简单的 DSL，用于通过 Ecto 播种数据库.
* [exsolr](https://github.com/dcarneiro/exsolr) - 用 Elixir 编写的 Solr 包装器.
* [extreme](https://github.com/exponentially/extreme) - 使用 Elixir 库 [Eventstore](https://geteventstore.com) 用于由聚合 (CQRS) 生成的事件的持久性.
* [exts](https://github.com/meh/exts) - Elixir 术语存储，ets 包装器.
* [github_ecto](https://github.com/wojtekmach/github_ecto) - GitHub API 的 Ecto 适配器.
* [gremlex](https://github.com/Revmaker/gremlex) - Apache Tinkerpop Gremlin Elixir 客户端.
* [hstore](https://github.com/senecasystems/hstore) - 对 Postgrex 的 Hstore 支持.
* [inquisitor](https://github.com/dockyard/inquisitor) - Ecto 的可组合查询构建器.
* [isn](https://github.com/Frost/isn) - postgreSQL 的 Ecto 类型是扩展.
* [kalecto](https://github.com/lau/calecto) - 在 Kalends 和 Ecto 之间粘合以保存日期、时间和日期时间.
* [kvs](https://github.com/synrc/kvs) - Erlang 抽象术语数据库.
* [level](https://github.com/gausby/level) - Elixir 的 Level 实现了各种辅助函数和数据类型，用于处理 Google 的 Level 数据存储.
* [mariaex](https://github.com/xerions/mariaex) - Elixir 的 MariaDB/MySQL 驱动程序.
* [memento](https://github.com/sheharyarn/memento) - Elixir 中的简单 Mnesia 界面.
* [moebius](https://github.com/robconery/moebius) - 针对 Elixir 和 PostgreSQL 的功能查询工具.
* [mongo](https://github.com/checkiz/elixir-mongo) - Elixir 的 MongoDB 驱动程序.
* [mongodb](https://github.com/ericmj/mongodb) - Elixir 的 MongoDB 驱动程序.
* [mongodb_driver](https://github.com/zookzook/elixir-mongodb-driver) - MongoDB 的替代驱动程序，支持最新版本的 MongoDB 和全面的功能列表.
* [mongodb_ecto](https://github.com/michalmuskala/mongodb_ecto) - 用于 Ecto 的 MongoDB 适配器.
* [mysql](https://github.com/mysql-otp/mysql-otp) - MySQL/OTP – Erlang/OTP 的 MySQL 驱动程序.
* [mysqlex](https://github.com/tjheeta/mysqlex) - 围绕 mysql-otp 库的 Ecto 兼容包装器.
* [neo4j_sips](https://github.com/florinpatrascu/neo4j_sips) - Elixir 的 Neo4j 驱动程序.
* [neo4j_sips_models](https://github.com/florinpatrascu/neo4j_sips_models) - 对 Neo4j.Sips Elixir 驱动程序的简约模型支持.
* [panoramix](https://github.com/gameanalytics/panoramix) - Elixir 的 Apache Druid 客户端.
* [paper_trail](https://github.com/izelnakri/paper_trail) - 用于跟踪和记录数据库中所有更改的 Ecto 插件.
* [pillar](https://github.com/sofakingworld/pillar) - Clickhouse 基于 HTTP 的客户端.
* [postgrex](https://github.com/elixir-ecto/postgrex) - Elixir 的 PostgreSQL 驱动程序.
* [red](https://github.com/rodrigues/red) - 以类似图形的方式在 Redis 中保持对象之间的关系.
* [rediscl](https://github.com/akdilsiz/elixir-rediscl) - 带有连接池和管道查询构建器的最小 redis 客户端.
* [redix](https://github.com/whatyouhide/redix) - 用于 Elixir 的超快、流水线、弹性 Redis 驱动程序.
* [redo](https://github.com/heroku/redo) - Heroku 的 erlang 流水线 redis 客户端.
* [rethinkdb](https://github.com/hamiltop/rethinkdb-elixir) - Rethinkdb 客户端在纯 Elixir 中使用 JSON 协议.
* [riak](https://github.com/drewkerrigan/riak-elixir-client) - 用 Elixir 编写的 Riak 客户端.
* [riak_ecto](https://github.com/pma/riak_ecto) - 用于 Ecto 的 Riak 适配器.
* [shards](https://github.com/cabol/shards) - 对 Erlang/Elixir ETS 表的透明和开箱即用的分片支持.
* [sql_dust](https://github.com/bettyblocks/sql_dust) - 使用神奇的 Elixir SQL 灰尘生成（复杂）SQL 查询.
* [sqlite_ecto](https://github.com/jazzyb/sqlite_ecto) - 用于 Ecto 的 SQLite3 适配器.
* [sqlitex](https://github.com/mmmries/sqlitex)  - 围绕 esqlite 的 Elixir 包装器. 允许访问 sqlite3 数据库.
* [ssdb_elixir](https://github.com/lidashuang/ssdb-elixir) - Elixir 的 ssdb 客户端，专注于性能.
* [tds](https://github.com/livehelpnow/tds) - 用于 Elixir 的 MSSQL/TDS 数据库驱动程序.
* [tds_ecto](https://github.com/livehelpnow/tds_ecto) - 用于 Ecto 的 MSSQL/TDS 适配器.
* [timex_ecto](https://github.com/bitwalker/timex_ecto) - 用于将 Timex DateTimes 与 Ecto 一起使用的适配器.
* [tirexs](https://github.com/Zatvobor/tirexs) - 一个 Elixir 风格的 DSL，用于构建对 Elasticsearch 引擎的基于 JSON 的请求.
* [triplex](https://github.com/ateliware/triplex) - 具有用于 Elixir 应用程序的 postgres 模式的数据库多租户！
* [triton](https://github.com/blitzstudios/triton) - 建立在 Xandra 之上的 Pure Elixir Cassandra ORM.
* [udpflux](https://github.com/timbuchwaldt/udpflux) - 一个固执的 InfluxDB UDP 客户端.
* [xandra](https://github.com/lexhide/xandra) - Cassandra 驱动程序在 Elixir 中原生构建，专注于速度、简单性和健壮性.
* [yar](https://github.com/dantswain/yar) - Elixir 的另一个 Redis 客户端.

## OTP
*用于处理 OTP 相关事物的库.*

* [core](https://github.com/fishcakez/core) - 用于选择性接收 OTP 进程的库.
* [erlexec](https://github.com/saleyn/erlexec) - 从 Erlang/OTP 执行和控制操作系统进程.
* [immortal](https://github.com/danielberkompas/immortal) - Immortal 是一小部分帮助模块，旨在使构建容错 OTP 应用程序变得更加容易.
* [libex_config](https://github.com/reset/libex-config) - 访问 OTP 应用程序配置的助手.

## Package Management
*用于包和依赖项管理的库和工具.*

* [Hex](https://hex.pm/) - Erlang 生态系统的包管理器.
* [rebar3_hex](https://github.com/hexpm/rebar3_hex) - 用于 rebar3 的 Hex.pm 插件.

## PDF
*用于处理 PDF 文件的库和软件.*

* [chromic_pdf](https://github.com/bitcrowd/chromic_pdf) - Chrome 的 DevTools API 客户端，用于生成 PDF（HTML 到 PDF）.
* [gutenex](https://github.com/SenecaSystems/gutenex) - Elixir 的原生 PDF 生成.
* [pdf2htmlex](https://github.com/ricn/pdf2htmlex) - 将 PDF 文档转换为漂亮的 HTML 文件而不会丢失文本或格式.
* [pdf_generator](https://github.com/gutschilla/elixir-pdf-generator) - 在 Elixir 项目中使用的 wkhtmltopdf 或 puppeteer（HTML 到 PDF）的简单包装器.
* [puppeteer_pdf](https://github.com/coletiv/puppeteer-pdf) - 另一个围绕 puppeteer（HTML 到 PDF）的包装器，用于 Elixir 项目.

## Protocols
*特殊协议和格式库.*

* [elixir_radius](https://github.com/bearice/elixir-radius) - Elixir 上的 RADIUS 协议.
* [ex_hl7](https://github.com/jcomellas/ex_hl7) - 健康级别 7 (HL7) 是一种旨在以电子方式建模和传输健康相关数据的协议.
* [ex_marshal](https://github.com/gaynetdinov/ex_marshal) - 在 Elixir 中实现的 Ruby Marshal 格式.
* [exprotobuf](https://github.com/bitwalker/exprotobuf) - Elixir 中的协议缓冲区，变得简单.
* [grpc-elixir](https://github.com/tony612/grpc-elixir) - gRPC 的 Elixir 实现.
* [message_pack](https://github.com/mururu/msgpack-elixir) - Elixir 的 MessagePack 实现.
* [msgpax](https://github.com/lexmag/msgpax) - Elixir 的 MessagePack（反）序列化器实现.
* [protox](https://github.com/ahamez/protox) - 协议缓冲区的 Elixir 实现.
* [riffed](https://github.com/pinterest/riffed) - 为 Apache Thrift 提供惯用的 Elixir 绑定.
* [Sippet](https://github.com/balena/elixir-sippet) - 设计用作 SIP 协议中间件的 Elixir 库.
* [SMPPEX](https://github.com/savonarola/smppex) - Elixir 中的 SMPP 3.4 协议和框架实现.

## Queue
*用于处理事件和任务队列的库.*

* [adap](https://github.com/awetzel/adap) - 创建跨信息系统的数据流，以根据 Elixir 匹配规则查询、扩充和转换数据.
* [amqp](https://github.com/pma/amqp) - 基于 Langohr 的 Erlang RabbitMQ 客户端的简单 Elixir 包装器.
* [broadway](https://github.com/dashbitco/broadway) - 使用 Elixir 进行并发和多阶段数据摄取和数据处理.
* [conduit](https://github.com/conduitframework/conduit) - 用于处理消息队列的框架，带有用于 SQS 和 AMQP 的适配器，以及用于可重用消息传递模式的插件.
* [cspex](https://github.com/costaraphael/cspex) - CSP 通道的简单、符合 OTP 的 Elixir 实现.
* [dbus](https://github.com/aforward/sadbus) - 用于在使用 Redis 解耦的微服务之间共享数据的哑消息总线.
* [ecto_job](https://github.com/mbuhot/ecto_job) - 使用 Ecto、PostgreSQL 和 GenStage 构建的事务性作业队列.
* [elixir_nsq](https://github.com/wistia/elixir_nsq) - Elixir 的 NSQ 客户端库.
* [elixir_talk](https://github.com/jsvisa/elixir_talk) - beanstalkd 的 Elixir 客户端.
* [enm](https://github.com/basho/enm) - enm 是一个 Erlang 端口驱动程序，它封装了 nanomsg C 库.
* [exdisque](https://github.com/mosic/exdisque) - Elixir 客户端 [Disque](https://github.com/antirez/disque)，一个内存中的分布式作业队列.
* [exq](https://github.com/akira/exq) - Elixir 的作业处理库 - 与 Resque/Sidekiq 兼容.
* [exrabbit](https://github.com/d0rc/exrabbit) - Elixir 的 RabbitMQ 绑定和 DSL.
* [flume](https://github.com/scripbox/flume) - 由 GenStage 和 Redis 支持的超快作业处理系统.
* [gen_rmq](https://github.com/meltwater/gen_rmq) - 旨在用于创建 RabbitMQ 消费者和发布者的一组行为.
* [heapq](https://github.com/takscape/elixir-heapq) - Elixir 中基于堆的优先级队列实现.
* [honeydew](https://github.com/koudelka/honeydew) - Honeydew 是 Elixir 的工作池库.
* [hulaaki](https://github.com/suvash/hulaaki) - 用 Elixir 编写的 MQTT 3.1.1 客户端库.
* [kaffe](https://github.com/spreedly/kaffe) - Elixir 的 Kafka 客户端库.
* [mqs](https://github.com/synrc/mqs) - RabbitMQ 客户端库、路由密钥、基于 MQ 的 RPC 和其他东西.
* [oban](https://github.com/sorentwo/oban) - 由 Elixir 和现代 PostgreSQL 提供支持的强大异步作业处理器.
* [opq](https://github.com/fredwu/opq) - 一个简单的内存队列，在 Elixir 中具有工作池和速率限制.
* [pqueue](https://github.com/okeuday/pqueue) - Erlang 优先级队列实现.
* [que](https://github.com/sheharyarn/que) - 使用 Mnesia 进行简单的后台作业处理.
* [queuex](https://github.com/falood/queuex) - 具有多个后端的优先队列.
* [RBMQ](https://github.com/Nebo15/rbmq) - 用于生成 RabbitMQ 生产者和消费者的简单 API.
* [Rihanna](https://github.com/samphilipd/rihanna) - Elixir 的高性能 postgres 支持的作业队列.
* [stream_weaver](https://hex.pm/packages/stream_weaver) - 用于处理流的库.
* [task_bunny](https://github.com/shinyscorpion/task_bunny) - 用 Elixir 编写的后台处理应用程序，并使用 RabbitMQ 作为消息传递后端.
* [toniq](https://github.com/joakimk/toniq) - 简单可靠的 Elixir 后台作业库.
* [verk](https://github.com/edgurgel/verk)  - Verk 是一个由 Redis 支持的作业处理系统. 它使用与 Sidekiq/Resque 相同的作业定义.
* [work_queue](https://github.com/pragdave/work_queue) - Elixir 中饥饿消费者模型的简单实现.


## Release Management
*用于发布管理的库和工具.*

* [changex](https://github.com/Gazler/changex) - 从 GIT 日志自动生成变更日志.
* [distillery](https://github.com/bitwalker/distillery) - Erlang VM 的发布打包功能的纯 Elixir 实现.
* [eliver](https://github.com/glasnoster/eliver) - Elixir 包的交互式语义版本控制.
* [exrm](https://github.com/bitwalker/exrm) - 自动为您的 Elixir 项目生成一个版本.
* [exrm_deb](https://github.com/johnhamelink/exrm_deb) - 轻松为您的 Elixir 版本创建 deb.
* [exrm_heroku](https://github.com/epsanchezma/exrm-heroku) - 轻松将您的 Elixir 版本发布到 Heroku.
* [exrm_rpm](https://github.com/smpallen99/exrm-rpm) - 轻松为您的 Elixir 版本创建 RPM.
* [mix_docker](https://github.com/Recruitee/mix_docker) - 将您的 Elixir 应用程序生产版本放在最小的 docker 映像中.
* [relex](https://github.com/yrashk/relex) - Erlang/Elixir Release Assembler.
* [renew](https://github.com/Nebo15/renew) - 混合任务以创建构建到 Docker 容器中的混合项目.

## REST and API
*用于开发 REST-ful API 的库和 Web 工具.*

* [accent](https://github.com/sticksnleaves/accent) - 用于处理 JSON API 密钥到不同情况的转换的插件.
* [detergent](https://github.com/devinus/detergent) - 一个乳化的 Erlang SOAP 库.
* [detergentex](https://github.com/r-icarus/detergentex) - Elixir 绑定到用于调用 WSDL/SOAP 服务的 Detergent erlang 库.
* [maru](https://github.com/falood/maru) - 用于创建类似 REST 的 API 的葡萄的 Elixir 副本.
* [mazurka](https://github.com/exstruct/mazurka) - 超媒体 API 工具包.
* [plug_rest](https://github.com/christopheradams/plug_rest) - 用于超媒体 Web 应用程序的 REST 行为和插件路由器.
* [signaturex](https://github.com/edgurgel/signaturex) - 简单的基于密钥/秘密的 API 身份验证.
* [SOAP client](https://github.com/elixir-soap/soap) - 基于 HTTPoison 的十六进制文档 SOAP 客户端.
* [urna](https://github.com/meh/urna) - Urna 是一个围绕 Cauldron 的简单 DSL，用于实现 REST 服务.
* [versionary](https://github.com/sticksnleaves/versionary) - Elixir Plug 和 Phoenix 的 API 版本控制.

## Search
*与搜索索引、搜索算法和搜索客户端相关的库.*

* [elasticsearch](https://github.com/infinitered/elasticsearch-elixir) - 一个用于 Elixir 的简单、严肃的 Elasticsearch 库.
* [elasticsearch_elixir_bulk_processor](https://github.com/sashman/elasticsearch_elixir_bulk_processor) - 一种高效灵活的插入 Elasticsearch 的方式.
* [giza_sphinxsearch](https://github.com/Tyler-pierce/giza_sphinxsearch) - 与 Manticore 兼容的 Sphinx 搜索客户端.

## Security
*有关安全性的库和工具.*

* [ca](https://github.com/synrc/ca) - 证书颁发机构.
* [clamxir](https://github.com/ramortegui/clamxir) - 灵丹妙药的 ClamAV 包装器.
* [code_signing](https://github.com/benknowles/code_signing) - 使用 Ed25519 签名对 BEAM 文件进行签名和验证.
* [Ockam](https://github.com/ockam-network/ockam) - 一套工具、编程库和基础设施，可以轻松构建与云服务和其他设备进行安全、私密和可信通信的设备. [Docs](https://www.ockam.io/learn/concepts/) .
* [pwned](https://github.com/thiamsantos/pwned) - 检查您的密码是否已被盗用.
* [safetybox](https://github.com/aforward/safetybox) - Elixir 面向​​安全的辅助函数.
* [sobelow](https://github.com/nccgroup/sobelow) - 针对 Phoenix 框架的以安全为中心的静态分析.
* [ssl_verify_fun](https://github.com/deadtrickster/ssl_verify_fun.erl) - Erlang ssl 验证函数的集合.

## SMS
*短信相关库和工具.*

* [exsms](https://hex.pm/packages/exsms) - 用于发送事务性 SMS 的 Elixir 库 - 支持 Sendinblue、mailjet、msg91 和 textlocal.

## Static Page Generation

* [blogit](https://github.com/meddle0x53/blogit) - 用于从包含降价文件的 git 存储库生成博客的 OTP 应用程序.
* [glayu](https://github.com/pablomartinezalvarez/glayu) - 用于中型站点的静态站点生成器.
* [medusa](https://github.com/Vesuvium/medusa) - 支持 Pug 的 Elixir 静态站点生成器.
* [obelisk](https://github.com/BennyHallett/obelisk) - 静态博客和网站生成器.
* [serum](https://github.com/Dalgona/Serum) - 一个用 Elixir 编写的简单静态网站生成器.

## Statistics
*围绕主题统计的图书馆.*

* [descriptive_statistics](https://github.com/pusewicz/descriptive_statistics) - Elixir 的描述性统计.
* [mtx](https://github.com/synrc/mtx) - MTX 支持前端 API，用于跟踪直方图、仪表、计数器、仪表、计时键.
* [numerix](https://github.com/safwank/Numerix) - 一系列有用的数学函数，偏向于统计学、线性代数和机器学习.
* [simple_stat_ex](https://github.com/Tyler-pierce/simplestatex) - Ecto 兼容库，用于按时间段进行简单统计.
* [statistics](https://github.com/msharp/elixir-statistics) - Elixir 的一些基本统计函数.

## Templating
*库解析和帮助模板*

* [bbmustache](https://github.com/soranoba/bbmustache) - Erlang/OTP 的基于二进制模式匹配的 Mustache 模板引擎.
* [calliope](https://github.com/nurugger07/calliope) - Elixir HAML 解析器.
* [eml](https://github.com/zambal/eml) - 用于在 Elixir 中编写和操作 (HTML) 标记的库.
* [exgen](https://github.com/rwdaigle/exgen) - A templating library for quickly generating Elixir projects.
* [expug](https://github.com/rstacruz/expug) - Elixir 的 Pug 模板.
* [mustache](https://github.com/schultyy/Mustache.ex) - Elixir 的胡子模板.
* [mustachex](https://github.com/jui/mustachex) - Elixir 的胡子 - 无逻辑模板.
* [slime](https://github.com/slime-lang/slime) - 用于渲染超薄模板的 Elixir 库.
* [taggart](https://github.com/ijcd/taggart) - HTML 作为 Elixir 中的代码.
* [templates](https://github.com/sugar-framework/templates) - 用于向 Web 应用程序添加模板的助手库.
* [temple](https://github.com/mhanberg/temple) - 针对 Elixir 和 Phoenix 的 HTML DSL.

## Testing
*用于测试代码库和生成测试数据的库.*

* [amrita](https://github.com/josephwilk/amrita) - 一个礼貌、彬彬有礼且完全正直的 Elixir 测试框架.
* [apocryphal](https://github.com/coryodaniel/apocryphal) - ExUnit 基于 Swagger 的文档驱动开发.
* [blacksmith](https://github.com/batate/blacksmith) - Elixir 的数据生成框架.
* [blitzy](https://github.com/benjamintanweihao/blitzy) - Elixir 中的简单 HTTP 负载测试器.
* [bypass](https://github.com/pspdfkit-labs/bypass) - Bypass 提供了一种使用自定义插件创建模拟 HTTP 服务器的快速方法.
* [chaperon](https://github.com/polleverywhere/chaperon) - 用 Elixir 编写的 HTTP 服务性能和负载测试框架.
* [chemistry](https://github.com/genericlady/chemistry) - Elixir 的测试框架.
* [cobertura_cover](https://github.com/PSPDFKit-labs/cobertura_cover) - 从与 Jenkins 的 Cobertura 插件兼容的 `mix test --cover` 文件中编写coverage.xml.
* [definject](https://github.com/definject/definject) - 不显眼的 Elixir 依赖注入器.
* [double](https://github.com/sonerdy/double) - 在不覆盖全局模块的情况下为测试创建存根依赖项.
* [ecto_it](https://github.com/xerions/ecto_it) - 带有默认配置的 Ecto 插件，用于使用数据库测试不同的 ecto 插件.
* [efrisby](https://github.com/FabioBatSilva/efrisby) - 用于 erlang 的 REST API 测试框架.
* [elixir-auto-test](https://github.com/joaothallis/elixir-auto-test) - 使用 inotify-tools 保存文件时运行测试.
* [espec](https://github.com/antonmi/espec) - 受 RSpec 启发的 Elixir 的 BDD 测试框架.
* [espec_phoenix](https://github.com/antonmi/espec_phoenix) - 凤凰网框架的 ESpec.
* [ex_machina](https://github.com/thoughtbot/ex_machina)  - Elixir 的灵活测试工厂. 与 Ecto 和 Ecto 协会开箱即用.
* [ex_parameterized](https://github.com/KazuCocoa/ex_parameterized) - 用于参数化测试的简单宏.
* [ex_spec](https://github.com/drewolson/ex_spec) - ExUnit 的类似 BDD 的语法.
* [ex_unit_fixtures](https://github.com/obmarg/ex_unit_fixtures) - 用于为 ExUnit 测试定义模块化依赖项的库.
* [ex_unit_notifier](https://github.com/navinpeiris/ex_unit_notifier) - ExUnit 的桌面通知.
* [excheck](https://github.com/parroty/excheck) - 基于属性的 Elixir 测试库（QuickCheck 风格）.
* [exkorpion](https://github.com/wesovilabs/exkorpion) - 针对 Elixir 开发人员的 BDD 库.
* [factory_girl_elixir](https://github.com/sinetris/factory_girl_elixir) - Ruby 的 factory_girl 在 Elixir 中的最小实现.
* [fake_server](https://github.com/bernardolins/fake_server) - FakeServer 是一个 HTTP 服务器，它模拟响应并使测试外部 API 更容易.
* [faker](https://github.com/igas/faker) - Faker 是一个纯 Elixir 库，用于生成假数据.
* [faker_elixir](https://github.com/GesJeremie/faker-elixir) - FakerElixir 是一个 Elixir 包，可以为您生成假数据.
* [fqc](https://github.com/project-fifo/fqc) - FiFo Quickcheck 助手，一组用于运行 EQC 的助手.
* [gimei](https://github.com/KazuCocoa/elixir-gimei) - Gimei 是一个纯 Elixir 库，用于生成日本假数据.
* [hound](https://github.com/HashNuke/hound) - 用于编写集成测试和浏览器自动化的 Elixir 库.
* [hypermock](https://github.com/stevegraham/hypermock) - HTTP 请求存根和期望 Elixir 库.
* [ignorant](https://github.com/campezzi/ignorant) - 部分`Map` 比较，确保字段存在同时忽略它们的值.
* [katt](https://github.com/for-GET/katt) - KATT（Klarna API 测试工具）是一个基于 HTTP 的 Erlang API 测试工具.
* [kovacs](https://github.com/antp/kovacs) - 一个简单的 ExUnit 测试运行器.
* [markdown_test](https://github.com/MainShayne233/markdown_test) - 一个让你在 Markdown 文件中测试 Elixir 代码的库.
* [meck](https://github.com/eproxus/meck) - Erlang 的模拟库.
* [mecks_unit](https://github.com/archan937/mecks_unit) - 在（异步）ExUnit 测试中使用优雅模拟模块功能的包 [meck](https://github.com/eproxus/meck).
* [mix_erlang_tasks](https://github.com/alco/mix-erlang-tasks) - 使用 Mix 的 Erlang 项目的常见任务.
* [mix_eunit](https://github.com/dantswain/mix_eunit) - 执行 eunit 测试的 Mix 任务.
* [mix_test_interactive](https://github.com/influxdata/mix_test_interactive) - 交互式测试运行器，用于带手表模式的混合测试.
* [mix_test_watch](https://github.com/lpil/mix-test.watch) - 每次保存文件时自动运行 Elixir 项目的测试.
* [mixunit](https://github.com/talentdeficit/mixunit) - 基于 Mix 的项目的 EUnit 任务.
* [mock](https://github.com/jjh42/mock) - Elixir 语言的模拟库.
* [mockery](https://github.com/appunite/mockery) - 用于异步测试的简单模拟库.
* [mockingbird](https://github.com/Driftrock/mockingbird) - 一组帮助测试涉及 http 请求的代码.
* [mox](https://github.com/dashbitco/mox) - Elixir 的模拟和显式合约.
* [pavlov](https://github.com/sproutapp/pavlov) - 用于 Elixir 项目的 BDD 框架.
* [plug_test_helpers](https://github.com/xavier/plug_test_helpers) - 一个简单的 Plugs 测试 DSL.
* [ponos](https://github.com/klarna/ponos) - Ponos 是一个 Erlang 应用程序，它公开了一个灵活的负载生成器 API.
* [power_assert](https://github.com/ma2gedev/power_assert_ex)  - Elixir 中的 Power Assert. 显示每个表达式的评估结果.
* [proper](https://github.com/manopapad/proper) - PropEr（ERlang 的基于 PROPerty 的测试工具）是一个受 QuickCheck 启发的开源基于属性的 Erlang 测试工具.
* [setup_tag](https://github.com/vic/setup_tag) - 轻松混合和匹配标记有标签的函数以设置您的测试上下文.
* [shouldi](https://github.com/batate/shouldi) - Elixir 测试库具有嵌套上下文、出色的可读性和易用性.
* [test_selector](https://github.com/DefactoSoftware/test_selector) - 一组测试助手，可确保您始终在 Phoenix 应用程序中选择正确的元素.
* [test_that_json](https://github.com/facto/test_that_json) - 用于 Elixir 测试需求的 JSON 断言和帮助程序.
* [tuco_tuco](https://github.com/stuart/tuco_tuco) - TucoTuco 通过运行 Web 浏览器并模拟用户与应用程序的交互来帮助您测试 Web 应用程序.
* [Walkman](https://github.com/derekkraan/walkman) - 受 Ruby 的 VCR 启发，将测试与现实世界隔离开来.
* [wallaby](https://github.com/keathley/wallaby) - Wallaby 通过同时模拟用户交互和管理浏览器来帮助测试您的 Web 应用程序.
* [white_bread](https://github.com/meadsteve/white-bread) - 使用小黄瓜语法在 Elixir 中基于故事的 BDD.

## Text and Numbers
*用于解析和操作文本和数字的库.*

* [abacus](https://github.com/narrowtux/abacus) - 在 Elixir 中评估数学术语.
* [base58](https://github.com/jrdnull/base58) - Elixir 的 Base58 编码/解码.
* [base58check](https://github.com/gjaldon/base58check) - 比特币的 Base58Check 编码/解码.
* [base62](https://github.com/igas/base62) - 纯 Elixir 中的 Base62 编码器/解码器.
* [bencode](https://github.com/gausby/bencode)  - Elixir 的 Bencode 编码器和解码器. 如果在输入中找到信息字典，解码器将返回信息字典的校验和值.
* [bencoder](https://github.com/alehander42/bencoder) - 在 Elixir 中编码.
* [bitcoinex](https://github.com/RiverFinancial/bitcoinex) - Elixir 中的比特币实用程序.
* [brcpfcnpj](https://github.com/williamgueiros/Brcpfcnpj) - 巴西文件的数字格式和验证 (CPF/CNPJ).
* [caustic](https://github.com/agro1986/caustic)  - 用于比特币、以太坊和其他区块链的 Elixir 加密货币库. 包括密码学、数论（素数、同余）和用于探索性数学的通用数学库.
* [ccc](https://github.com/Joe-noh/ccc) - 字符代码转换器.
* [chinese_translation](https://github.com/tyrchen/chinese_translation) - 根据维基百科数据在繁体中文和简体中文之间进行翻译，并将中文单词/字符翻译成拼音（或带或不带声调的slug）.
* [cidr](https://github.com/c-rack/cidr-elixir) - Elixir 的无类别域间路由 (CIDR).
* [cirru_parser](https://github.com/Cirru/parser.ex) - Elixir 中的 Cirru 解析器.
* [colorful](https://github.com/Joe-noh/colorful) - 用于在 CUI 上装饰字符的 Elixir 宏.
* [colors](https://github.com/lidashuang/colors) - 用 Elixir 编写的颜色工具.
* [convertat](https://github.com/whatyouhide/convertat) - 用于在任意碱基之间进行转换的 Elixir 库.
* [curtail](https://github.com/seankay/curtail) - HTML 标记安全字符串截断.
* [custom_base](https://github.com/igas/custom_base) - 允许您在 Elixir 中进行自定义基础转换.
* [decimal](https://github.com/ericmj/decimal) - Elixir 的任意精度十进制算法.
* [dicer](https://github.com/olhado/dicer) - 掷骰子表达式评估器.
* [eden](https://github.com/jfacorro/Eden) - [EDN](https://github.com/edn-format/edn) Elixir 的编码器/解码器.
* [elixilorem](https://github.com/mgamini/elixilorem) - Elixir 的 lorem ipsum 生成器.
* [elixir-range-extras](https://github.com/lnikkila/elixir-range-extras) - Elixir 范围实用程序：恒定时间随机采样和设置操作.
* [elixir_bencode](https://github.com/AntonFagerberg/elixir_bencode) - 在 Elixir 中实现的 Bencode.
* [erldn](https://github.com/marianoguerra/erldn) - [EDN](https://github.com/edn-format/edn) Erlang 平台的格式解析器.
* [event_source_encoder](https://github.com/chatgris/event_source_encoder) - 将数据编码为符合 EventSource 的数据.
* [ex_brace_expansion](https://github.com/gniquil/ex_brace_expansion) - 大括号扩展，如从 sh/bash 所知，在 Elixir 中.
* [ex_cldr](https://github.com/kipcole9/cldr) - Cldr 是 Unicode Consortium 的 Common Locale Data Repository (CLDR) 的 Elixir 库.
* [ex_rfc3966](https://github.com/marcelog/ex_rfc3966) - Elixir Tel URI 解析器与 RFC3966 兼容.
* [ex_rfc3986](https://github.com/marcelog/ex_rfc3986) - RFC3986 URI/URL 解析器.
* [ex_uc](https://github.com/carturoch/ex_uc) - Elixir 的可扩展单位转换器.
* [exmoji](https://github.com/mroth/exmoji) - 用于 Elixir/Erlang 的 Emoji 编码瑞士军刀.
* [expletive](https://github.com/xavier/expletive) - Elixir 的脏话过滤器库.
* [expr](https://github.com/Rob-bie/Expr) - An Elixir library for parsing and evaluating mathematical expressions.
* [faust](https://github.com/jquadrin/faust) - Elixir 的马尔可夫文本生成器.
* [haikunator](https://github.com/knrz/Haikunator) - 生成类似于 Heroku 的令人难忘的随机名称，以在您的应用程序或其他任何地方使用.
* [hashids](https://github.com/alco/hashids-elixir) - Hashids 允许您通过可逆映射混淆数字标识符.
* [hexate](https://github.com/rjsamson/hexate) - Elixir 中用于十六进制编码/解码的简单模块.
* [inet_cidr](https://github.com/cobenian/inet_cidr) - Elixir 的无类别域间路由 (CIDR)，与 :inet 兼容并支持 IPv4 和 IPv6.
* [inflex](https://github.com/nurugger07/inflex) - Elixir 的 Inflector 库.
* [kitsune](https://github.com/edubkendo/kitsune) - 用于转换数据表示的 Elixir 库.
* [ltsvex](https://github.com/ma2gedev/ltsvex) - Elixir 中的 LTSV 解析器实现.
* [mbcs](https://github.com/woxtu/elixir-mbcs)  - erlang-mbcs 的包装器. 该模块提供了字符编码转换的功能.
* [mimetype_parser](https://github.com/camshaft/mimetype_parser) - 解析 mimetypes.
* [minigen](https://github.com/mrdimosthenis/minigen) - Erlang 生态系统的随机数据生成器.
* [monetized](https://github.com/theocodes/monetized) - 用于处理和存储资金的轻量级解决方案.
* [money](https://github.com/liuggio/money) - 使用 Money 更安全、更轻松、更有趣，诠释了 Fowler&#39;s Money 模式.
* [mt940](https://github.com/my-flow/mt940) - 用于 Elixir 的 MT940（标准结构化 SWIFT 客户声明消息）解析器.
* [nanoid](https://github.com/railsmechanic/nanoid) - NanoID 的 Elixir 端口，一个安全且 URL 友好的唯一 ID 生成器.
* [neotomex](https://github.com/jtmoulia/neotomex) - 一种 [PEG](http://bford.info/packrat/) 使用令人愉快的 Elixir DSL 实现.
* [number](https://github.com/danielberkompas/number) - Number 是一个假名的 Elixir 库，它提供了将数字转换为各种不同格式的函数.
* [numero](https://github.com/alisinabh/numero) - 用于在 elixir 中转换非英文 utf-8 数字的微型库.
* [palette](https://github.com/lpil/palette) - 一个方便的库，用于在 Elixir 中为字符串着色.
* [pinyin](https://github.com/lidashuang/pinyin) - Elixir 的中文拼音库.
* [porterstemmer](https://github.com/frpaulas/porterstemmer) - 长生不老药中的波特声音.
* [pretty_hex](https://github.com/polsab/pretty_hex) - Elixir 中的二进制十六进制转储库.
* [quickrand](https://github.com/okeuday/quickrand) - 快速随机数生成.
* [RandomStringGenerator](https://github.com/caioceccon/random_string_generator) - 根据给定的字符串模式生成随机字符串的模块.
* [ref_inspector](https://github.com/elixytics/ref_inspector)  - Elixir 中的引用解析器库. 从 URL 获取信息.
* [remove_emoji](https://github.com/guanting112/elixir_remove_emoji)  - Elixir 中的表情符号文本消毒剂. 它可以删除任何表情符号.
* [secure_random](https://github.com/patricksrobertson/secure_random.ex) - 以我对 Ruby 的 SecureRandom 的热爱为模型的随机 base64 字符串的便利库.
* [sentient](https://github.com/dantame/sentient) - 基于 AFINN-111 词表的简单情感分析.
* [shortuuid](https://github.com/gpedic/ex_shortuuid) - 生成简洁、明确、URL 安全的 UUID.
* [simetric](https://github.com/lexmag/simetric) - Elixir 的字符串相似度指标.
* [slugger](https://github.com/h4cc/slugger) - Slugger 可以从可用于 URL 或文件名的给定字符串生成 slug.
* [smile](https://github.com/danigulyas/smile) - 用于将表情符号映射器转换为表情符号字符的小型库，例如在 Slack 消息中.
* [stemmer](https://github.com/fredwu/stemmer) - Elixir 中的英语 (Porter2) 词干实现.
* [tau](https://github.com/FranklinChen/tau) - 提供著名的数学常数，tau，τ = 6.2831....
* [tomlex](https://github.com/zamith/tomlex) - Elixir 的 TOML 解析器.
* [ua_inspector](https://github.com/elixytics/ua_inspector) - 用户代理解析器库，如`piwik/device-detector`.
* [ua_parser2](https://github.com/nazipov/ua_parser2-elixir)  - ua-parser2 到 Elixir 的端口. 用户代理解析器库.
* [unit_fun](https://github.com/meadsteve/unit_fun) - 尝试在 elixir 中为数字添加单位，以在处理数字数量时提供一些额外的类型安全性.
* [uuid](https://github.com/zyro/elixir-uuid) - Elixir 的 UUID 生成器和实用程序.
* [uuid_erl](https://github.com/okeuday/uuid) - Erlang 原生 UUID 生成.
* [veritaserum](https://github.com/uesteibar/veritaserum) - 基于 afinn-165、表情符号和一些增强功能的情绪分析.

## Third Party APIs
*用于访问第三方 API 的库.*

* [airbax](https://github.com/adjust/airbax) - 从 Elixir 到 Airbrake 的异常跟踪.
* [airbrake](https://github.com/romul/airbrake-elixir) - Airbrake 的 Elixir 通知程序.
* [airbrakex](https://github.com/fazibear/airbrakex) - 用于 Airbrake 服务的 Elixir 客户端.
* [amazon_product_advertising_client](https://github.com/zachgarwood/elixir-amazon-product-advertising-client) - Elixir 的亚马逊产品广告 API 客户端.
* [apns](https://github.com/chvanikoff/apns4ex) - 用于 elixir 的 Apple 推送通知服务客户端库.
* [asanaficator](https://github.com/trenpixster/asanaficator)  - Asana API 的简单 Elixir 包装器. 基于 Tentacat.
* [askimet_ex](https://github.com/mijailr/askimet_ex) - 用于 Askimet 反垃圾邮件服务的 Elixir 客户端.
* [assembla_api](https://github.com/Assembla/ex_assembla_api) - 为 Elixir 组装客户端 API.
* [balalaika_bear](https://github.com/ayrat555/balalaika_bear) - Elixir 的简单 VK API 客户端.
* [balanced](https://github.com/bryanjos/balanced-elixir) - Elixir 的平衡 API 客户端.
* [bandwidth](https://github.com/bandwidthcom/elixir-bandwidth) - 用于带宽应用平台的 Elixir 客户端库.
* [bing_translator](https://github.com/ikeikeikeike/bing_translator) - 一个简单的 Elixir 接口到 Bing 的翻译 API.
* [bitmex](https://github.com/nobrick/bitmex) - Elixir 的 BitMEX 客户端库.
* [bitpay](https://github.com/bitpay/elixir-client) - 用于连接到 bitpay.com 的 Elixir 核心库.
* [cashier](https://github.com/swelham/cashier) - 支付网关提供通向多个支付提供商的通用接口.
* [cleverbot](https://github.com/BlakeWilliams/Elixir-Cleverbot) - 在 Elixir 中简单实现 Cleverbot API.
* [coinbase](https://github.com/gregpardo/coinbase-elixir) - 一个非官方的 Coinbase API v1 客户端.
* [commerce_billing](https://github.com/joshnuss/commerce_billing) - Elixir 的支付处理库，支持多个网关（例如 Bogus &amp; Stripe）.
* [conekta](https://github.com/echavezNS/conekta-elixir) - Conekta API 的 Elixir 包装器.
* [correios_cep](https://github.com/prodis/correios-cep-elixir)  - 直接从 Correios 数据库中按邮政编码查找巴西地址. 没有 HTML 解析器.
* [currently](https://github.com/chatgris/currently) - 显示当前在 Trello 上分配的卡片的工具.
* [darkskyx](https://github.com/techgaun/darkskyx) - 一个用于 Elixir 的 Darksky.com（前身为forecast.io）API 客户端.
* [digitalocean](https://github.com/lukeed/elixir-digitalocean) - Digital Ocean API v2 的 Elixir 包装器.
* [digoc](https://github.com/kevinmontuori/digoc) - 数字海洋 API v2 Elixir 客户端.
* [diplomat](https://github.com/peburrows/diplomat) - 一种 [Google Cloud Datastore](https://cloud.google.com/datastore/) 客户.
* [dnsimple](https://github.com/dnsimple/dnsimple-elixir) - 用于 DNSimple API v2 的 Elixir 客户端.
* [docker](https://github.com/hexedpackets/docker-elixir) - 用于 Docker 远程 API 的 Elixir 客户端.
* [dockerex](https://github.com/hisea/dockerex) - 具有 SSL/TLS 登录/连接支持的轻量级 Docker 远程 API 客户端.
* [dogstatsd](https://github.com/adamkittelson/dogstatsd-elixir) - Elixir 客户端 [DogStatsd](https://www.datadoghq.com/).
* [dpd_client](https://github.com/knewter/dpd_client) - DPD 服务的 API 客户端.
* [dropbox](https://github.com/ammmir/elixir-dropbox) - 用于 Elixir 的 Dropbox Core API 客户端.
* [dublin_bus_api](https://github.com/carlo-colombo/dublin-bus-api) - 访问都柏林巴士服务的实时乘客信息 (RTPI).
* [edgarex](https://github.com/rozap/edgarex) - 用于从 EDGAR 获取 SEC 文件的 Elixir 接口.
* [elixir_authorizenet](https://github.com/marcelog/elixir_authorizenet) - Authorize.Net 商家 API 的非官方客户端.
* [elixir_ipfs_api](https://github.com/zabirauf/elixir-ipfs-api) - Elixir 的 IPFS（星际文件系统）API 客户端.
* [elixirfm](https://github.com/jrichocean/Elixirfm) - Elixir 的 Last.fm API 包装器.
* [elixtagram](https://github.com/zensavona/elixtagram) - Elixir 的 Instagram API 客户端.
* [ethereumex](https://github.com/exthereum/ethereumex) - 以太坊区块链的 Elixir JSON-RPC 客户端.
* [everex](https://github.com/jwarlander/everex) - 用于 Elixir 的 Evernote API 客户端.
* [everyoneapi](https://github.com/knewter/everyoneapi) -EveryoneAPI.com 的 API 客户端.
* [ex_changerate](https://github.com/81dr/ex_changerate) - Elixir 客户端 [exchangerate.host](https://exchangerate.host) 火.
* [ex_codeship](https://github.com/securingsincity/ex_codeship) - Codeship 的 API 客户端.
* [ex_statsd](https://github.com/CargoSense/ex_statsd) - Elixir 的 statsd 客户端实现.
* [ex_twilio](https://github.com/danielberkompas/ex_twilio) - Elixir 的 Twilio API 客户端.
* [ex_twiml](https://github.com/danielberkompas/ex_twiml) - 在 Elixir 中为您的 Twilio 集成生成 TwiML.
* [exdesk](https://github.com/deadkarma/exdesk) - 用于 Desk.com API 的 Elixir 库.
* [exfacebook](https://github.com/oivoodoo/exfacebook) - Facebook API，使用 Elixir 编写，使用类似 Ruby koala gem 的方法.
* [exgenius](https://github.com/jeffweiss/exgenius) -（未记录的）Rap Genius API 的 Elixir 库.
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
* [gcmex](https://github.com/dukex/gcmex) - 用于 elixir 的 Google Cloud Messaging 客户端库.
* [google-cloud](https://github.com/GoogleCloudPlatform/elixir-google-api) - 此存储库包含与 Google API 交互的所有客户端库.
* [google_sheets](https://github.com/GrandCru/GoogleSheets) - Elixir 库，用于以 CSV 格式获取和轮询 Google 电子表格数据.
* [govtrack](https://github.com/walterbm/govtrack-elixir) - 一个简单的 Elixir 包装器，用于 [govtrack.us](https://www.govtrack.us/developers) 火.
* [gringotts](https://github.com/aviabird/gringotts) - 类似于 Elixir 和 Phoenix 框架的完整支付库 [ActiveMerchant](https://github.com/activemerchant/active_merchant) 来自红宝石世界.
* [hexoku](https://github.com/JonGretar/Hexoku) - 针对 Elixir 项目的 Heroku API 客户端和 Heroku Mix 任务.
* [honeywell](https://github.com/jeffutter/honeywell-elixir) - 霍尼韦尔 Lyric、Round 和 Water Leak &amp; Freeze Detector API 的客户.
* [kane](https://github.com/peburrows/kane) - 一种 [Google Cloud Pub/Sub](https://cloud.google.com/pubsub/overview) 客户.
* [keenex](https://github.com/bryanjos/keenex) - Keen.io API 客户端.
* [link_shrinkex](https://github.com/jonahoffline/link_shrinkex) - Elixir 库，用于使用 Google 的 URL Shortener API 创建短 URL.
* [m2x](https://github.com/attm2x/m2x-elixir)  - AT&amp;T M2X 的 Elixir 客户端，这是一种基于云的完全托管时间序列数据存储服务，适用于网络连接的机器对机器 (M2M) 设备和物联网 (IoT).  ([Erlang Version](https://github.com/attm2x/m2x-erlang)).
* [mailchimp](https://github.com/duartejc/mailchimp) - MailChimp API 版本 3 的基本 Elixir 包装器.
* [mailgun](https://github.com/chrismccord/mailgun) - Elixir Mailgun 客户端.
* [mandrill](https://github.com/slogsdon/mandrill-elixir) - Elixir 的 Mandrill 包装纸.
* [marvel](https://github.com/bryanjos/marvel) - Marvel API 的 CLI 和 Elixir API 客户端.
* [mexpanel](https://github.com/blendmedia/mexpanel) - Mixpanel HTTP API 的 Elixir 客户端.
* [mixpanel](https://github.com/michihuber/mixpanel_ex) - Mixpanel HTTP API 的 Elixir 客户端.
* [mixpanel_data_client](https://github.com/jeregrine/mixpanel_data_client) - 用于与 Mixpanel 数据导出 API 交互的客户端.
* [mmExchangeRate](https://github.com/Arkar-Aung/mmExchangeRate) - 基于缅甸中央银行 Api 的简单汇率检查器和计算器.
* [nadia](https://github.com/zhyu/nadia) - 用 Elixir 编写的 Telegram Bot API Wrapper.
* [omise](https://github.com/teerawat1992/omise-elixir) - 省略 Elixir 的客户端库.
* [opbeat](https://github.com/teodor-pripoae/opbeat) - Opbeat 的 Elixir 客户端.
* [pagexduty](https://github.com/ride/pagexduty) - Elixir 的 Pagerduty 客户端.
* [parse_client](https://github.com/elixircnx/parse_elixir_client) - parse.com REST API 的 Elixir 客户端.
* [parsex](https://github.com/maarek/ParsEx) - ParsEx 是一个 Elixir HTTP 客户端，用于与 Parse.com 的 Restful API 通信.
* [particle](https://github.com/jeffutter/particle-elixir) - 粒子物联网平台 HTTP API 的 Elixir 客户端.
* [pathway](https://github.com/novabyte/pathway) - 一个 Erlang/Elixir 客户端 [Trak.io](http://trak.io/) REST API.
* [pay](https://github.com/era/pay) - 用于处理 Paypal 和其他支付解决方案的 Elixir Lib.
* [pay_pal](https://github.com/zensavona/paypal) - 用于处理 PayPal REST API 的 Elixir 库.
* [pigeon](https://github.com/codedge-llc/pigeon) - 用于发送 iOS 和 Android 推送通知的 HTTP2 兼容包装器.
* [pocketex](https://github.com/essenciary/pocketex) - Pocketex 是 Pocket read later 服务的 Elixir 客户端 [getpocket.com](https://getpocket.com/).
* [pusher](https://github.com/edgurgel/pusher) - 用于访问 Pusher REST API 的 Elixir 库.
* [qiita_ex](https://github.com/ma2gedev/qiita_ex) - Elixir 的 Qiita API v2 接口.
* [qiniu](https://github.com/tony612/qiniu) - Elixir 七牛 SDK.
* [random_user](https://github.com/katgironpe/random_user) - 一个用于 randomuser.me API 的 Elixir 客户端.
* [random_user_api](https://hex.pm/packages/random_user_api) - 另一个简单的 randomuser.me API 客户端.
* [reap](https://github.com/Raynes/reap) - Reap 是一个简单的 Elixir 库，用于使用 refheap API.
* [reddhl](https://github.com/MonkeyIsNull/reddhl) - Reddit 及其各种 subreddit 的标题和链接提取器.
* [redtube](https://github.com/kkirsche/Redtube_Elixir) - 用 Elixir 编写的 Redtube API Wrapper.
* [reporter](https://github.com/KazuCocoa/simple_app_reporter_ex)  - 记者是简单的报告应用评论库. 支持 AppStore 和 GooglePlay.
* [riemann](https://github.com/koudelka/elixir-riemann) - 一种 [Riemann](http://riemann.io/) Elixir 的客户.
* [rs_twitter](https://github.com/radzserg/rstwitter) - Elixir 的低级 Twitter 客户端.
* [semver](https://github.com/lee-dohm/semver) - 用于处理 semver.org 兼容版本字符串的实用程序.
* [sendgrid](https://github.com/alexgaribay/sendgrid_elixir) - 使用 SendGrid 发送可组合的交易电子邮件.
* [shopify](https://github.com/nsweeting/shopify) - 轻松访问 Shopify API.
* [sift_ex](https://github.com/C404/sift_ex) - Elixir 的 Siftscience API 库.
* [simplex](https://github.com/adamkittelson/simplex) - 用于与 Amazon SimpleDB API 交互的 Elixir 库.
* [slack](https://github.com/BlakeWilliams/Elixir-Slack) - Elixir 中的 Slack 实时消息客户端.
* [sparkpost](https://github.com/SparkPost/elixir-sparkpost) - 使用 SparkPost 发送电子邮件的 Elixir 库.
* [statix](https://github.com/lexmag/statix) - 在 StatsD 协议中公开应用指标.
* [stripe](https://github.com/SenecaSystems/stripe) - 包装 Stripe API 的 Elixir 库.
* [stripity_stripe](https://github.com/robconery/stripity-stripe) - 一个长生不老药库 [Stripe](https://stripe.com/).
* [tagplay](https://github.com/tagplay/elixir-tagplay) - 用于 Tagplay API 的 Elixir 客户端.
* [telegex](https://github.com/Hentioe/telegex) - Elixir 的电报机器人库.
* [telephonist](https://github.com/danielberkompas/telephonist) - 用于 Twilio 调用的 Elixir 状态机.
* [tentacat](https://github.com/edgurgel/tentacat) - GitHub API 的简单 Elixir 包装器.
* [tg_client](https://github.com/ccsteam/ex-telegram-client) - 与 Telegram-CLI 通信的 Elixir 包装器.
* [tradehub](https://github.com/anhmv/tradehub-elixir) - Tradehub 区块链的 Elixir 客户端库.
* [traitify_elixir](https://github.com/traitify/traitify_elixir) - 用于 Traitify 开发人员 API 的 Elixir 客户端库.
* [ui_faces](https://github.com/katgironpe/ui_faces) - Elixir 应用程序的 UIFaces API 客户端.
* [unsplash-elixir](https://github.com/waynehoover/unsplash-elixir) - Unsplash 的 Elixir 库.
* [vultr](https://github.com/avitex/elixir-vultr) - Vultr API 的简单包装器.
* [xe](https://github.com/paulodiniz/xe) - 货币的实时转换.
* [zanox](https://github.com/rafaelss/zanox) - Zanox API.

## Translations and Internationalizations
*提供翻译或国际化的图书馆.*

* [exkanji](https://github.com/ikeikeikeike/exkanji)  - 用于在平假名、片假名、罗马字和汉字之间进行翻译的 Elixir 库. 它使用 Mecab.
* [exromaji](https://github.com/ikeikeikeike/exromaji) - 用于在平假名、片假名和罗马字之间进行翻译的 Elixir 库.
* [getatrex](https://github.com/alexfilatov/getatrex) - 使用谷歌翻译为 Elixir/Phoenix 项目自动翻译 Gettext 语言环境的工具.
* [gettext](https://github.com/elixir-lang/gettext) - Elixir 的国际化和本地化支持.
* [linguist](https://github.com/change/linguist) - Elixir 国际化库.
* [parabaikElixirConverter](https://github.com/Arkar-Aung/ParabaikElixirConverter)  - ParabaikElixirConverter 只是 Parabaik 转换器的 Elixir 版本. 它可以从 Unicode 转换为 Zawgyi-One，也可以从 Zawgyi-One 转换为 Unicode，反之亦然.
* [trans](https://github.com/belaustegui/trans) - 一个 Elixir 库，用于利用 PostgreSQL JSONB 数据类型管理嵌入到模型中的翻译.

## Utilities
*实用程序库.*

* [ar2ecto](https://github.com/aforward/ar2ecto) - Ar2ecto 是一组混合任务，可帮助您从 ActiveRecord 迁移到 Ecto.
* [async_with](https://github.com/fertapric/async_with) - Elixir 的“with”修饰符以并行执行其所有子句.
* [crutches](https://github.com/mykewould/crutches) - Elixir 的实用程序库，旨在补充与该语言捆绑在一起的标准库.
* [deppie](https://github.com/whitfin/deppie) - Elixir 最酷的弃用记录器.
* [dot-notes](https://github.com/whitfin/dot-notes-elixir) - 地图/列表的简单点/括号符号解析/转换.
* [dress](https://github.com/veelenga/dress) - Cli 应用程序，让您的标准输出更上一层楼.
* [erlang-history](https://github.com/ferd/erlang-history) - 将 shell 历史添加到 Erlang 的 shell 的技巧.
* [erlsh](https://github.com/proger/erlsh) - 涉及与系统外壳、路径和外部程序交互的函数和端口系列.
* [erlware_commons](https://github.com/erlware/erlware_commons) - Erlang 的附加标准库.
* [ex_progress](https://github.com/acj/ex_progress) - 用于跟踪许多任务和子任务的进度的库.
* [exjprop](https://github.com/stocks29/exjprop) - Elixir 库，用于从各种来源读取 Java 属性文件.
* [fitex](https://github.com/timdeputter/FitEx) - FitEx 是一个宏模块，它为函数定义提供了一些糖.
* [global](https://github.com/mgwidmann/global) - Erlang `:global` 模块的包装器.
* [mandrake](https://github.com/mbasso/mandrake) - Mandrake 是一个函数式编程库，它为 elixir 带来了一些其他的魔法.
* [mnemonix](https://github.com/christhekeele/mnemonix) - 键/值存储的统一接口.
* [plasm](https://github.com/facto/plasm) - Plasm 是 Ecto 的可组合查询多工具，包含更高级的函数，如 .count、.random、.first、.last、.find、.inserted_before、.inserted_after 等.
* [pubsub](https://github.com/simonewebdesign/elixir_pubsub) - 发布-订阅实用程序库，它实现了发布-订阅机制以减轻业务逻辑流程上的通信负担.
* [quark](https://github.com/robot-overlord/quark) - 常见函数式编程习语的库：组合器、柯里化和部分应用.
* [retry](https://github.com/safwank/ElixirRetry) - 用于线性重试、指数退避和可组合延迟等待的简单 Elixir 宏.
* [sips_downloader](https://github.com/DavsX/SipsDownloader) - Elixir 模块，用于下载 ElixirSips 剧集和所有其他文件.
* [sitemap](https://github.com/ikeikeikeike/sitemap) - 站点地图是在 Elixir 中生成站点地图的最简单方法.
* [uef-lib](https://github.com/DOBRO/uef-lib)  - 有用的 Erlang 函数库，提供用于操作列表、二进制文件、地图、数字、日期和时间的模块. 它包含一些针对特定情况下的性能优化的函数（例如，用于文件 I/O 操作或二进制转换）.
* [vert.x](https://github.com/PharosProduction/ExVertx) - Elixir 事件总线桥接使用 TCP 套接字的 Vert.x 服务.

## Validations
*用于验证数据的库和实现.*

* [bankster](https://github.com/railsmechanic/bankster) - Elixir 的 IBAN 帐号和 BIC 验证库.
* [ex_gtin](https://github.com/kickinespresso/ex_gtin) - GS1 规范下的 GTIN 代码验证库.
* [ex_nric](https://github.com/falti/ex_nric) - 新加坡国民注册身份证号码 (NRIC) 的验证.
* [exop](https://github.com/madeinussr/exop) - 一个允许封装业务逻辑并使用预定义合同验证参数的库.
* [form](https://github.com/synrc/form) - 文档表单和验证库.
* [is](https://github.com/bydooweedoo/is) - 具有嵌套结构支持的 elixir 快速、可扩展且易于使用的数据结构验证.
* [jeaux](https://github.com/zbarnes757/jeaux) - 一个轻量级和简单的模式验证器.
* [optimal](https://github.com/albert-io/optimal) - 基于模式的关键字列表选项验证器.
* [shape](https://github.com/prio/shape) - 基于 Prismatic Sc​​heme 的 Elixir 数据验证库.
* [skooma](https://github.com/bcoop713/skooma) - 用于描述和验证数据结构的简单数据验证库.
* [uk_postcode](https://github.com/KushalP/uk_postcode) - 英国邮政编码解析和验证库.
* [vex](https://github.com/CargoSense/vex) - Elixir 的可扩展数据验证库.
* [voorhees](https://github.com/danmcclain/voorhees) - 用于验证 JSON 响应的库.

## Version Control
*使用版本控制，如 git、mercury、subversion ...*

* [gitex](https://github.com/awetzel/gitex) - Git 对象存储的 Elixir 实现，但目标是实现与其他存储和主题相同的语义.

## Video
*用于处理和操作视频和多媒体的库.*

* [ffmpex](https://github.com/talklittle/ffmpex) - FFmpeg 命令行包装器.
* [silent_video](https://github.com/talklittle/silent_video) - 将 GIF 和视频转换为静音视频，针对移动播放进行了优化.

## WebAssembly
*用于在 Elixir 中运行 WebAssembly (WASM) 或在 WebAssembly 上运行 Elixir 的库.*

* [lumen](https://github.com/lumen/lumen) - 为 WebAssembly 设计的替代 BEAM 实现.
* [wasmex](https://github.com/tessi/wasmex/) - 从 Elixir 执行 WebAssembly / WASM 二进制文件.

## XML
*使用 XML 的库和实现（对于 html 工具，请访问 [HTML](#html) 部分）.*

* [elixir-map-to-xml](https://github.com/gunnar2k/elixir-map-to-xml) - 将 Elixir 映射转换为 XML 文档.
* [elixir-xml-to-map](https://github.com/homanchou/elixir-xml-to-map) - 从 XML 字符串创建 Elixir Map 数据结构.
* [erlsom](https://github.com/willemdj/erlsom) - Erlsom 是一个 Erlang 库，用于解析（和生成）XML 文档.
* [exmerl](https://github.com/pwoolcoc/exmerl) - xmerl 的 Elixir 包装器.
* [exml](https://github.com/expelledboy/exml) - 最简单的用于 xmerl xpath 的 Elixir 包装器.
* [exoml](https://github.com/Overbryd/exoml) - 将 xml 解码/编码为树结构的模块.
* [fast_xml](https://github.com/processone/fast_xml) - 基于快速 Expat 的 Erlang XML 解析库.
* [meeseeks](https://github.com/mischov/meeseeks) - 一个使用 CSS 或 XPath 选择器从 HTML 和 XML 解析和提取数据的库.
* [quinn](https://github.com/nhu313/Quinn) - Elixir 的 XML 解析器.
* [saxy](https://github.com/qcam/saxy) - Saxy 是 Elixir 中的 XML 解析器和编码器，专注于速度和标准合规性.
* [sweet_xml](https://github.com/awetzel/sweet_xml) - 简单有效地查询 XML.
* [xml_builder](https://github.com/joshnuss/xml_builder) - 用于生成 xml 的 Elixir 库.
* [xmlrpc](https://github.com/ewildgoose/elixir-xml_rpc) - 用于为客户端和服务器编码和解码 XML-RPC 的库.

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
*精彩的书籍和电子书.*

* [Adopting Elixir](https://pragprog.com/book/tvmelixir/adopting-elixir)  - 将 Elixir 带入您的公司，使用来自创建 Elixir 并成功大规模使用它的人员的现实策略. 本书包含将应用程序从概念到生产所需的所有信息 (2017).
* [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) - 将您的 Web API 升级到 GraphQL，利用其灵活的查询来增强您的用户的能力，并利用其声明式结构来简化您的代码（2017）.
* [Elixir Cookbook](https://www.packtpub.com/application-development/elixir-cookbook) - 这本书是 Paulo A Pereira (2015) 按主题分组的一组食谱.
* [Elixir do zero à concorrência](https://www.casadocodigo.com.br/products/livro-elixir) -（葡萄牙语）这本书介绍了 Tiago Davi（2014 年）使用 Elixir 进行函数式和并发编程.
* [Elixir in Action](https://www.manning.com/books/elixir-in-action-second-edition) - Saša Jurić (2015) 对该语言的简要介绍，然后更详细地介绍了在 Elixir 中构建生产就绪系统.
* [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) - Wolfgang Loder 在函数概念的背景下介绍 Erlang 和 Elixir（2016 年）.
* [Erlang in Anger](http://www.erlang-in-anger.com/) - 这本书旨在成为 Fred Hebert（2014 年）所著的关于如何在战争时期成为 Erlang 军医的小指南.
* [Functional Web Development with Elixir, OTP, and Phoenix](https://pragprog.com/book/lhelph/functional-web-development-with-elixir-otp-and-phoenix) - 打开强大的新技术之门，让您以全新的方式思考 Web 开发（2017 年）.
* [Getting Started - Elixir](https://github.com/potatogopher/elixir-getting-started) - Elixir 入门教程 (2016) 的 PDF、MOBI 和 EPUB 文档.
* [Hands-on Elixir & OTP: Cryptocurrency trading bot](https://www.elixircryptobot.com)  - 想通过创建一个真实世界的项目来学习 Elixir 和 OTP？ 通过动手操作 *Elixir 和 OTP：加密货币交易机器人*，您将通过从事有趣的软件项目获得动手经验. 我们将通过迭代实现改进探索所有关键抽象和基本原则.  (2021).
* [Introducing Elixir ](http://shop.oreilly.com/product/0636920030584.do) - 对该语言的温和介绍，其中包含 Simon St. Laurent 和 J. David Eisenberg 的大量代码示例和练习（2013 年）.
* [Learn Functional Programming with Elixir](https://pragprog.com/book/cdc-elixir/learn-functional-programming-with-elixir)  - 不要带着势在必行的心态登上 Elixir 列车！ 要充分利用函数式语言，您需要从函数式角度进行思考 (2017).
* [Metaprogramming Elixir: Write Less Code, Get More Done (and Have Fun!)](https://pragprog.com/book/cmelixir/metaprogramming-elixir) - Chris McCord 对如何利用 Elixir 的元编程功能改进 Elixir 编码的详尽解释（2015 年）.
* [Phoenix for Rails Developers](http://www.phoenixforrailsdevelopers.com)  - 这本书展示了 Rails 开发人员如何从他们现有的知识中受益来学习 Phoenix. 作者：埃尔维奥·维科萨 (2017).
* [Phoenix in Action](https://manning.com/books/phoenix-in-action)  - 以您现有的 Web 开发技能为基础，教您 Phoenix 的独特优势以及足够的 Elixir 来完成工作. 作者：杰弗里·莱塞尔 (2017).
* [Phoenix Inside Out](https://shankardevy.com/phoenix-book/)  - 本系列的目标是让您成为一名自信的 Phoenix 开发人员. 有 3 个不同的版本可以满足进入 Phoenix 的开发人员的不同需求.
* [Programming Elixir 1.6](https://pragprog.com/titles/elixir16/) - 这本书介绍了 Dave Thomas（2014 年）使用 Elixir 进行的函数式和并发编程.
* [Programming Phoenix 1.4](https://pragprog.com/titles/phoenix14/) - Chris McCord、José Valim 和 Bruce Tate 使用 Phoenix 框架构建 Web 应用程序的权威指南（2015 年）.
* [The Beam Book](https://happi.github.io/theBeamBook/) - Erlang 运行时系统 ERTS 和虚拟机 BEAM 的描述.
* [The Little Elixir & OTP Guidebook](https://www.manning.com/books/the-little-elixir-and-otp-guidebook) - Benjamin Tan Wei Hao (2014) 通过中小型项目学习 Elixir 和 OTP 的书.
* [Études for Elixir](https://www.oreilly.com/library/view/etudes-for-elixir/9781491917640/) - J. David Eisenberg 编写的 Elixir 编程练习集（2013 年）（[Github Repo](https://github.com/oreillymedia/etudes-for-elixir)).

## Cheat Sheets
*有用的 Elixir 相关备忘单.*

* [benjamintanweihao/elixir-cheatsheets](https://github.com/benjamintanweihao/elixir-cheatsheets/) - GenServer 和 Supervisor 备忘单.

## Community
*通过聊天或邮件列表与社区取得联系.*

* [#elixir-lang](http://webchat.freenode.net/?channels=elixir-lang) - The IRC Channel #elixir-lang on Freenode.
* [Elixir Forum](https://elixirforum.com/) - 社区运行有关 Elixir 的所有内容的论坛.
* [elixir-lang-core](https://groups.google.com/d/forum/elixir-lang-core) - Elixir Core 开发的邮件列表，使用“talk”进行问题和一般性讨论.
* [elixir-lang-talk](https://groups.google.com/d/forum/elixir-lang-talk) - 用于问题和讨论的官方 Elixir 邮件列表.
* [ElixirSlack](https://elixir-slackin.herokuapp.com/) - Elixir Slack 社区.

## Editors
*可用于 Elixir/Erlang 的编辑器和 IDE*

* [Alchemist](https://github.com/tonini/alchemist.el) - Elixir 工具集成到 Emacs 中.
* [Alchemist-Server](https://github.com/tonini/alchemist-server) - 编辑器/IDE 独立后台服务器通知有关 Elixir 混合项目.
* [Alchemist.vim](https://github.com/slashmili/alchemist.vim) - Elixir 工具集成到 Vim 中.
* [Atom](https://atom.io/packages/language-elixir) - 对 Atom 的 Elixir 语言支持.
* [atom-elixir](https://github.com/msaraiva/atom-elixir) - Elixir 的 Atom 包.
* [atom-iex](https://github.com/indiejames/atom-iex) - 在 Atom 中运行 IEx 会话.
* [elixir-ls](https://github.com/JakeBecker/elixir-ls)  - 用于 Elixir 的独立于前端的 IDE“智能”服务器. 实现基于 JSON 的“语言服务器协议”标准，并通过 VS Code 的调试器协议提供调试器支持.
* [elixir-tmbundle](https://github.com/elixir-lang/elixir-tmbundle) - 用于 Elixir 的 TextMate 和 SublimeText 包.
* [elixir_generator](https://github.com/jadercorrea/elixir_generator.vim) - Vim 插件，用一个命令生成 Elixir 模块和测试文件.
* [ElixirSublime](https://github.com/vishnevskiy/ElixirSublime) - SublimeText 3 的 Elixir 插件，提供代码完成和 linting.
* [ilexir](https://github.com/dm1try/ilexir) - Neovim 中 Elixir 的类似 IDE 的东西.
* [intellij_elixir](https://github.com/KronicDeth/intellij_elixir) - 用于 JetBrains IDE 的 Elixir 插件 intellj-elixir 的 Elixir 助手.
* [Jetbrains](http://plugins.jetbrains.com/plugin/7522) - 用于 IntelliJ IDEA、RubyMine、WebStorm、PhpStorm、PyCharm、AppCode、Android Studio、0xDBE 的 Elixir.
* [Notepad++](https://github.com/Hades32/elixir-udl-npp) - 用于 Notepad++ 的 Elixir 语法突出显示.
* [Nova Elixir](https://github.com/stollcri/elixir.novaextension) - Nova 中 Elixir 文件（.ex、.exs、.eex）的语法突出显示和代码完成.
* [nvim](https://github.com/dm1try/nvim) - Neovim 主机，用于在 Elixir 中编写插件.
* [phoenix-snippets](https://github.com/phoenixframework-Brazil/phoenix-snippets) - Atom 的 Phoenix 片段.
* [vim-elixir](https://github.com/elixir-lang/vim-elixir) - Elixir 的 Vim 配置文件.
* [vim-ex_test](https://github.com/moofish32/vim-ex_test) - 基于 Thoughtbots vim-rspec 的 Vim 测试运行器.
* [vim-mix-format](https://github.com/mhinz/vim-mix-format) - Vim 和 Neovim 的异步“混合格式”.
* [vscode-elixir](https://github.com/mat-mcloughlin/vscode-elixir) - 对 Visual Studio 代码的 Elixir 支持.
* [vscode-elixir-ls](https://github.com/JakeBecker/vscode-elixir-ls) - 由 ElixirLS 提供支持的 VS Code 的 Elixir 语言支持和调试器.

## Newsletters
*有用的 Elixir 相关时事通讯.*

* [Elixir Digest](http://elixirdigest.net) - 包含有关 Elixir 和 Phoenix 的最新文章的每周时事通讯.
* [Elixir Radar](http://plataformatec.com.br/elixir-radar) - “官方” Elixir 时事通讯，由 Plataformatec 每周通过电子邮件发布.
* [ElixirWeekly](https://elixirweekly.net) - Elixir 社区通讯，涵盖您容易错过的内容，分享于 [ElixirStatus](http://elixirstatus.com) 和网络.

## Other Awesome Lists
*可以在以下位置找到其他非常棒的列表 [jnv/lists](https://github.com/jnv/lists#lists-of-lists) 或者 [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness#awesome-awesomeness).*

* [Awesome Elixir and CQRS](https://github.com/slashdotdash/awesome-elixir-cqrs) - 精选的 Elixir 和命令查询职责分离 (CQRS) 和事件溯源资源的精选列表.
* [Awesome Elixir by LibHunt](https://elixir.libhunt.com) - 精选的 Elixir 和 Erlang 包和资源的精选列表.
* [Awesome Erlang](https://github.com/drobakowski/awesome-erlang) - 精选的 Erlang 库、资源和闪亮事物的精选列表.
* [Curated Elixir Resources](https://hackr.io/tutorials/learn-elixir) - 顶级推荐的 Elixir 资源集合.
* [Erlang Bookmarks](https://github.com/0xAX/erlang-bookmarks) - Erlang 开发人员的链接集合.

## Reading
*Elixir 相关阅读材料.*

* [Discover Elixir & Phoenix](https://www.ludu.co/course/discover-elixir-phoenix/) - 同时教授 Elixir 语言和 Phoenix 框架的在线课程.
* [Elixir Cheat-Sheet](http://media.pragprog.com/titles/elixir/ElixirCheat.pdf) - 安迪·亨特和戴夫·托马斯的 Elixir 备忘单.
* [Elixir Functional Programming](https://github.com/kblake/functional-programming) - 介绍使用 Elixir 语言进行函数式编程的材料.
* [Elixir School](https://elixirschool.com/) - 有关 Elixir 编程语言的课程.
* [Elixir Tab](https://github.com/efexen/elixir-tab) - 帮助您学习 Elixir 核心库的 Chrome 扩展程序.
* [Elixir vs Ruby | How Switching To Elixir Made Our Team Better](https://foxbox.com/blog/elixir-vs-ruby/) - 详细解释何时以及为什么应该选择 Elixir 而不是 Ruby 的长篇文章.
* [The Little Schemer in Elixir](https://github.com/jwhiteman/a-little-elixir-goes-a-long-way) - Little Schemer 书中的练习和算法，移植到 Elixir.
* [xElixir](https://github.com/exercism/xelixir) - Elixir 中的锻炼练习.

## Screencasts
*很酷的视频教程.*

* [Alchemist Camp](https://alchemist.camp) - Alchemist.Camp 有许多小时的免费、基于项目的 Elixir 学习屏幕录像.
* [Confreaks (Elixir)](http://confreaks.tv/tags/40) - Elixir 相关的会议谈话.
* [Elixir for Programmers](https://codestool.coding-gnome.com/courses/elixir-for-programmers) - Functional, Parallel, Reliable (and fun!), taught by Dave Thomas.
* [Elixir Sips](http://elixirsips.com/) - 用于学习 Elixir 的小屏幕录像.
* [ElixirCasts.io](https://elixircasts.io/) - 帮助您学习 Elixir 和 Phoenix 的简单截屏视频.
* [ExCasts](https://excasts.com) - 适合所有技能水平的 Elixir 和 Phoenix 截屏视频.
* [Frathon's YouTube Channel](https://www.youtube.com/c/Frathon) - 致力于推广函数式编程的 YouTube 频道，在 Elixir 中发布“现实世界”编程视频，例如“在 Elixir 中创建加密货币交易机器人”系列.
* [LearnElixir.tv](https://www.learnelixir.tv/) - 初学者友好、深入、分步的截屏视频.
* [LearnPhoenix.tv](https://www.learnphoenix.tv/) - 了解如何使用 Phoenix 构建快速、可靠的 Web 应用程序.
* [Meet Elixir](https://www.pluralsight.com/courses/meet-elixir) - 通过 José Valim 了解 Elixir 的一些功能和概念.

## Styleguides
*用于确保编码时一致性的样式指南.*

* [christopheradams/elixir_style_guide](https://github.com/christopheradams/elixir_style_guide) - 社区驱动的 Elixir 风格指南.
* [lexmag/elixir-style-guide](https://github.com/lexmag/elixir-style-guide) - 固执的 Elixir 风格指南.
* [rrrene/elixir-style-guide](https://github.com/rrrene/elixir-style-guide) - 风格指南检查 [Credo](https://github.com/rrrene/credo).

## Websites
*有用的 Elixir 相关网站.*

* [30 Days of Elixir](https://github.com/seven1m/30-days-of-elixir) - 在 30 个练习中演练 Elixir 语言.
* [BEAM Community](http://beamcommunity.github.io/) - 从分布式系统到 Erlang VM 上的强大服务器和语言设计.
* [Benjamin Tan - Learnings & Writings](http://benjamintan.io/blog/tags/elixir/) - 一个主要由 Elixir 帖子组成的博客.
* [Elixir Career](https://elixir.career/) - Elixir 的工作委员会和 Elixir 开发人员社区.
* [Elixir China](https://github.com/jw2013/elixir-china) - 中国长生不老药网站 [elixir-cn.com](http://elixir-cn.com/).
* [Elixir Examples](http://elixir-examples.github.io/) - 小型 Elixir 编程语言示例的集合.
* [Elixir Flashcards](https://elixircards.co.uk/)  - 抽认卡是提高知识的有效方式.  Elixircards 是手工制作的、专业印刷的抽认卡，用于升级您的 Elixir.
* [Elixir Fountain](https://soundcloud.com/elixirfountain) - 每周播客，其中包含来自 Elixir 社区的新闻和采访，由 [Johnny Winn](https://twitter.com/johnny_rugger).
* [Elixir Github Repository](https://github.com/elixir-lang/elixir) - 项目存储库.
* [Elixir Github Wiki](https://github.com/elixir-lang/elixir/wiki) - 项目的维基，包含很多有用的信息.
* [Elixir Quiz](http://elixirquiz.github.io/) - 每周编程问题，帮助您学习 Elixir.
* [Elixir Recipes](http://elixir-recipes.github.io/) - Elixir 中常见问题的模式和解决方案的集合.
* [Hashrocket Today I Learned - Elixir](https://til.hashrocket.com/elixir) - 来自 Hashrocket 团队的关于 Elixir 的小帖子.
* [How I start - Elixir](http://howistart.org/posts/elixir/1) - Explanation and intro to Elixir by José Valim.
* [Learning Elixir](http://learningelixir.joekain.com/) - 关于专业软件工程师学习 Elixir 的博客.

## Contributing
请参阅 [CONTRIBUTING](https://github.com/h4cc/awesome-elixir/blob/master/.github/CONTRIBUTING.md) 详情.
