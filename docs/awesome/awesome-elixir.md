## Awesome Elixir [![Build Status](https://api.travis-ci.org/h4cc/awesome-elixir.svg?branch=master)](https://travis-ci.org/h4cc/awesome-elixir) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
精选的Elixir图书馆，资源和闪亮的东西，精选的精选列表 [awesome-php](https://github.com/ziadoz/awesome-php).

如果您认为应该添加一个包，请在相应的问题上添加：+1 :(`：+1：`）或创建一个新包.

有 [other sites with curated lists of elixir packages](#other-awesome-lists) 你可以看看.

- [Awesome Elixir](#awesome-elixir)
    - [Actors](#actors)
    - [Algorithms and Data structures](#algorithms-and-data-structures)
    - [Applications](#applications)
    - [Artificial Intelligence](#artificial-intelligence)
    - [Audio and Sounds](#audio-and-sounds)
    - [Authentication](#authentication)
    - [Authorization](#authorization)
    - [Behaviours and Interfaces](#behaviours-and-interfaces)
    - [Benchmarking](#benchmarking)
    - [Bittorrent](#bittorrent)
    - [BSON](#bson)
    - [Build Tools](#build-tools)
    - [Caching](#caching)
    - [Chatting](#chatting)
    - [Cloud Infrastructure and Management](#cloud-infrastructure-and-management)
    - [Code Analysis](#code-analysis)
    - [Command Line Applications](#command-line-applications)
    - [Configuration](#configuration)
    - [Cryptography](#cryptography)
    - [CSV](#csv)
    - [Date and Time](#date-and-time)
    - [Debugging](#debugging)
    - [Deployment](#deployment)
    - [Documentation](#documentation)
    - [Domain-specific language](#domain-specific-language)
    - [ECMAScript](#ecmascript)
    - [Email](#email)
    - [Embedded Systems](#embedded-systems)
    - [Encoding and Compression](#encoding-and-compression)
    - [Errors and Exception Handling](#errors-and-exception-handling)
    - [Eventhandling](#eventhandling)
    - [Examples and funny stuff](#examples-and-funny-stuff)
    - [Feature Flags and Toggles](#feature-flags-and-toggles)
    - [Feeds](#feeds)
    - [Files and Directories](#files-and-directories)
    - [Formulars](#formulars)
    - [Framework Components](#framework-components)
    - [Frameworks](#frameworks)
    - [Games](#games)
    - [Geolocation](#geolocation)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [HTML](#html)
    - [HTTP](#http)
    - [Images](#images)
    - [Instrumenting / Monitoring](#instrumenting--monitoring)
    - [JSON](#json)
    - [Languages](#languages)
    - [Lexical analysis](#lexical-analysis)
    - [Logging](#logging)
    - [Macros](#macros)
    - [Markdown](#markdown)
    - [Miscellaneous](#miscellaneous)
    - [Native Implemented Functions](#native-implemented-functions)
    - [Natural Language Processing (NLP)](#natural-language-processing-nlp)
    - [Networking](#networking)
    - [Office](#office)
    - [ORM and Datamapping](#orm-and-datamapping)
    - [OTP](#otp)
    - [Package Management](#package-management)
    - [PDF](#pdf)
    - [Protocols](#protocols)
    - [Queue](#queue)
    - [Release Management](#release-management)
    - [REST and API](#rest-and-api)
    - [Search](#search)
    - [Security](#security)
    - [SMS](#sms)
    - [Static Page Generation](#static-page-generation)
    - [Statistics](#statistics)
    - [Templating](#templating)
    - [Testing](#testing)
    - [Text and Numbers](#text-and-numbers)
    - [Third Party APIs](#third-party-apis)
    - [Translations and Internationalizations](#translations-and-internationalizations)
    - [Utilities](#utilities)
    - [Validations](#validations)
    - [Version Control](#version-control)
    - [Video](#video)
    - [XML](#xml)
    - [YAML](#yaml)
- [Resources](#resources)
    - [Books](#books)
    - [Cheat Sheets](#cheat-sheets)
    - [Community](#community)
    - [Editors](#editors)
    - [Newsletters](#newsletters)
    - [Other Awesome Lists](#other-awesome-lists)
    - [Reading](#reading)
    - [Screencasts](#screencasts)
    - [Styleguides](#styleguides)
    - [Websites](#websites)
- [Contributing](#contributing)

## Actors
*与演员等合作的图书馆和工具.*

* [dflow](https://github.com/dalmatinerdb/dflow) - 流水线流程处理引擎.
* [exactor](https://github.com/sasa1977/exactor) - 帮助更容易实现Elixir中的演员.
* [exos](https://github.com/awetzel/exos) - 端口包装器，用于转发演员和呼叫链接端口.
* [flowex](https://github.com/antonmi/flowex) - 使用Elixir GenStage进行基于铁路流量的编程.
* [mon_handler](https://github.com/tattdcodemonkey/mon_handler) - 监视给定GenEvent处理程序的最小GenServer.
* [pool_ring](https://github.com/camshaft/pool_ring) - 根据哈希环创建池.
* [poolboy](https://github.com/devinus/poolboy) - 一个hunky Erlang工人池工厂.
* [pooler](https://github.com/seth/pooler) -  OTP流程池应用程序.
* [sbroker](https://github.com/fishcakez/sbroker) - 基于逗留时间的主动队列管理库.
* [workex](https://github.com/sasa1977/workex) -  EVM过程中的背压和流量控制.

## Algorithms and Data structures
*算法和数据结构的库和实现.*

* [array](https://github.com/takscape/elixir-array) -  Erlang数组的Elixir包装器库.
* [aruspex](https://github.com/dkendal/aruspex) -  Aruspex是一个可配置的约束求解器，纯粹用Elixir编写.
* [bimap](https://github.com/mkaput/elixir-bimap) - 纯Elixir实施 [bidirectional maps](https://en.wikipedia.org/wiki/Bidirectional_map) 和多图.
* [bitmap](https://github.com/hashd/bitmap-elixir) - 纯Elixir实施 [bitmaps](https://en.wikipedia.org/wiki/Bitmap).
* [blocking_queue](https://github.com/joekain/BlockingQueue)   -  BlockingQueue是一个作为GenServer实现的简单队列.  它具有固定的最大长度，在创建时建立.
* [bloomex](https://github.com/gmcabrita/bloomex) - 可扩展布隆过滤器的纯Elixir实现.
* [clope](https://github.com/ayrat555/clope) -  Elixir的实施 [CLOPE](http://www.inf.ufrgs.br/~alvares/CMP259DCBD/clope.pdf)：一种快速有效的事务数据聚类算法.
* [combination](https://github.com/seantanly/elixir-combination) -  Elixir库，用于从Enumerable集合生成组合和排列.
* [count_buffer](https://github.com/camshaft/count_buffer) - 缓冲大量计数器并定期冲洗.
* [cuckoo](https://github.com/gmcabrita/cuckoo) - 纯粹的Elixir实现 [Cuckoo Filters](https://www.cs.cmu.edu/%7Edga/papers/cuckoo-conext2014.pdf).
* [cuid](https://github.com/duailibe/cuid) - 用Elixir编写的针对水平缩放和顺序查找性能优化的抗冲突ids.
* [data_morph](https://hex.pm/packages/data_morph) - 从数据创建Elixir结构.
* [dataframe](https://github.com/JordiPolo/dataframe) - 包提供类似于Python的Pandas或R的data.frame（）的功能.
* [datastructures](https://github.com/meh/elixir-datastructures) - 用于处理数据结构的协议，实现和包装器的集合.
* [def_memo](https://github.com/os6sense/DefMemo) - 使用genserver后备存储的elixir的memoization宏（defmemo）.
* [dlist](https://github.com/stocks29/dlist) - 在所有药剂执行.
* [eastar](https://github.com/herenowcoder/eastar) - 纯Elixir中的A *图形寻路.
* [ecto_materialized_path](https://github.com/asiniy/ecto_materialized_path) -  ecto模型的树结构，层次结构和祖先.
* [ecto_state_machine](https://github.com/asiniy/ecto_state_machine) - 在Elixir上实现的有限状态机模式，用于Ecto.
* [elistrix](https://github.com/tobz/elistrix) - 延迟/容错库，帮助您将应用程序与缓慢或失败的服务的不确定世界隔离开来.
* [emel](https://github.com/mrdimosthenis/emel) - 用elixir编写的简单实用的机器学习库.
* [erlang-algorithms](https://github.com/aggelgian/erlang-algorithms) - 流行数据结构和算法的实现.
* [exconstructor](https://github.com/appcues/exconstructor) - 用于生成结构构造函数的Elixir库，可轻松处理外部数据.
* [exfsm](https://github.com/awetzel/exfsm) - 简单的elixir库来定义静态FSM.
* [exkad](https://github.com/rozap/exkad) - 一个 [kademlia](https://en.wikipedia.org/wiki/Kademlia) 在Elixir中实施.
* [exmatrix](https://github.com/a115/exmatrix) -  ExMatrix是一个用于处理矩阵的小型库，最初是为并行测试矩阵乘法而开发的.
* [ezcryptex](https://github.com/stocks29/ezcryptex) -  Cryptex顶部的薄层.
* [fnv](https://github.com/asaaki/fnv.ex) - 纯Elixir实现Fowler-Noll-Vo散列函数.
* [fsm](https://github.com/sasa1977/fsm) - 有限状态机作为功能数据结构.
* [fuse](https://github.com/jlouis/fuse) - 该应用程序为Erlang实现了所谓的断路器.
* [gen_fsm](https://github.com/pavlos/gen_fsm) - 一个通用的有限状态机 - 围绕OTP的gen_fsm的Elixir包装器.
* [graphmath](https://github.com/crertel/graphmath) - 用于执行2D和3D数学的Elixir库.
* [hash_ring_ex](https://github.com/reset/hash-ring-ex) -  Elixir的一致哈希环实现.
* [hypex](https://github.com/whitfin/hypex) -  HyperLogLog的Fast Elixir实现.
* [indifferent](https://github.com/vic/indifferent) - 使用自定义密钥转换对Elixir地图/列表/元组进行无差别访问.
* [isaac](https://github.com/arianvp/elixir-isaac) -  Isaac是ISAAC的elixir模块：快速加密随机数生成器.
* [jumper](https://github.com/whitfin/jumper) - 在Elixir中跳转一致的哈希实现（没有NIF）.
* [key2value](https://github.com/okeuday/key2value) -  Erlang双向设置关联映射.
* [lfsr](https://github.com/pma/lfsr) -  Elixir实现二进制Galois线性反馈移位寄存器.
* [loom](https://github.com/asonge/loom) - 支持δ-CRDT的CRDT库.
* [luhn](https://github.com/ma2gedev/luhn_ex) -  Elixir中的Luhn算法.
* [lz4](https://github.com/szktty/erlang-lz4) - 用于Erlang的LZ4绑定，用于快速数据压缩.
* [machinery](https://github.com/joaomdmoura/machinery) - 一般的结构状态机库，它与Phoenix开箱即用.
* [mason](https://github.com/spacepilots/mason)   -  Coerce映射到结构.  这很有用，例如，当您连接REST API并希望从响应中创建结构时.
* [matrex](https://github.com/versilov/matrex) - 使用CBLAS进行C实现的Elixir / Erlang超快速矩阵库.
* [merkle_tree](https://github.com/yosriady/merkle_tree) -  Elixir中的Merkle哈希树实现.
* [minmaxlist](https://github.com/seantanly/elixir-minmaxlist) -  Elixir库扩展`Enum.min_by / 2`，`Enum.max_by / 2`和`Enum.min_max_by / 2`以返回结果列表而不是一个.
* [mmath](https://github.com/dalmatinerdb/mmath) - 用于对二进制文件中的数字“数组”执行数学运算的库.
* [monad](https://github.com/rmies/monad) -  Haskell激发了Elixir时尚语法中的monad.
* [monadex](https://github.com/rob-brown/MonadEx) - 使用monad升级Elixir管道.
* [murmur](https://github.com/gmcabrita/murmur) - 非加密哈希Murmur3的纯Elixir实现.
* [natural_sort](https://github.com/DanCouper/natural_sort) - 字符串列表的Elixir自然排序实现.
* [navigation_tree](https://github.com/gutschilla/elixir-navigation-tree) - 带有助手的导航树表示，用于生成HTML.
* [parallel_stream](https://github.com/beatrichartz/parallel_stream) -  Elixir的并行流实现.
* [paratize](https://github.com/seantanly/elixir-paratize) -  Elixir库提供一些方便的并行处理（执行）工具，支持配置工作人员数量和超时.
* [parex](https://github.com/StevenJL/parex) - Parallel Execute (Parex) is an Elixir module for executing multiple (slow) processes in parallel.
* [qex](https://github.com/princemaple/elixir-queue) - 包装`：queue`，改进的API和`Inspect`，`Collectable`和`Enumerable`协议实现.
* [ratio](https://github.com/Qqwy/elixir-rational)   - 添加Rational Numbers并允许它们用于常见的算术运算.  还支持Floats和Rational Numbers之间的转换.
* [red_black_tree](https://github.com/SenecaSystems/red_black_tree) -  Elixir中的红黑树实现.
* [remodel](https://github.com/stavro/remodel) - 用于转换地图结构的Elixir presenter包.
* [rendezvous](https://github.com/timdeputter/Rendezvous) - 在Elixir中实现Rendezvous或Highest Random Weight（HRW）哈希算法.
* [rock](https://github.com/ayrat555/rock) -  ROCK的Elixir实现：分类属性的鲁棒聚类算法.
* [sfmt](https://github.com/jj1bdx/sfmt-erlang/) - 针对Erlang的面向SIMD的Fast Mersenne Twister（SFMT）.
* [simhash](https://github.com/UniversalAvenue/simhash-ex) - 使用Siphash和N-gram实现Simhash.
* [sleeplocks](https://github.com/whitfin/sleeplocks) - 适用于Elixir / Erlang的BEAM友好型自旋锁.
* [sorted_set](https://github.com/SenecaSystems/sorted_set) -  Elixir的分类集.
* [spacesaving](https://github.com/rozap/spacesaving) - 使用“节省空间”算法对不同元素估计进行流计数.
* [structurez](https://github.com/hamiltop/structurez) -  Elixir数据结构的游乐场.
* [supermemo](https://github.com/edubkendo/supermemo) -  Elixir的实施 [Supermemo 2 algorithm](https://www.supermemo.com/english/ol/sm2.htm).
* [tfidf](https://github.com/OCannings/tf-idf) - 术语频率 - 逆文档频率的Elixir实现.
* [the_fuzz](https://github.com/smashedtoatoms/the_fuzz) - 模糊字符串匹配算法实现.
* [tinymt](https://github.com/jj1bdx/tinymt-erlang/) -  Erlang的Tiny Mersenne Twister（TinyMT）.
* [trie](https://github.com/okeuday/trie) -  Erlang Trie实施.
* [witchcraft](https://github.com/expede/witchcraft) -  Elixir的常见代数结构和函数.
* [zipper_tree](https://github.com/Dkendal/zipper_tree) -  Variadic arity树，带有Elixir拉链.

## Applications
*独立应用程序.*
* [bpe](https://github.com/spawnproc/bpe) -  Erlang中的业务流程引擎.
* [CaptainFact](https://github.com/CaptainFact/captain-fact-api) - 一个协作的实时视频事实检查平台.
* [Consolex](https://github.com/sivsushruth/consolex) -  Consolex是一个工具，允许您将基于Web的控制台附加到任何混合项目.
* [dragonfly_server](https://github.com/cloud8421/dragonfly-server) - 用于服务Dragonfly图像的Elixir应用程序.
* [ExChat](https://github.com/tony612/exchat) -  Elixir，Phoenix和React（redux）的类似Slack的应用程序.
* [Exon](https://github.com/tchoutri/Exon) -  Elixir开发的“混乱管理器”，提供简单的API来管理和记录您的资料.
* [ExShop](https://github.com/authentic-pixels/ex-shop) - 使用Phoenix框架创建的数字商品商店和博客.
* [Hydra](https://github.com/doomspork/hydra) - 多头野兽：API网关，请求缓存和数据转换.
* [majremind](https://bitbucket.org/Anwen/majremind) - 更新服务器的自我维护数据库，告知您需要更新哪个服务器.
* [medex](https://github.com/xerions/medex) - 体检 - 申请注册健康检查回调并通过HTTP表示其状态.
* [medusa_server](https://github.com/IcaliaLabs/medusa_server) - 用Elixir编写的简单牛仔Web服务器，用于堆叠图像.
* [n2o](https://github.com/synrc/n2o) -  WebSocket应用服务器.
* [Nvjorn](https://github.com/tchoutri/Nvjorn) - A multi-protocol network services monitor written in Elixir using Poolboy.
* [Phoenix Battleship](https://github.com/bigardone/phoenix-battleship) - 使用Elixir，Phoenix Framework，React和Redux构建的Good Old游戏.
* [Phoenix Toggl](https://github.com/bigardone/phoenix-toggl) - 在Elixir，Phoenix Framework，React和Redux中完成Toggl致敬.
* [Phoenix Trello](https://github.com/bigardone/phoenix-trello) -  Trello在Elixir，Phoenix Framework，React和Redux中的表现.
* [poxa](https://github.com/edgurgel/poxa) -  Open Pusher实现，与Pusher库兼容.
* [Queerlink](https://github.com/Queertoo/Queerlink) - 用Elixir编写的简单而有效的URL缩短服务.
* [RemoteRetro](https://github.com/stride-nyc/remote_retro) - 用于进行敏捷回顾的实时应用程序 [remoteretro.org](https://remoteretro.org) 用Elixir / Phoenix / React写的.
* [Sprint Poker](https://github.com/elpassion/sprint-poker) - 使用Elixir Lang，Phoenix Framework和React编写的敏捷团队在线评估工具.
* [Stabby Flies](https://meaty-spiffy-hermitcrab.gigalixirapp.com) - 使用Elixir，Phoenix和Pixi构建的多人格斗游戏.
* [Startup Job](https://github.com/tsurupin/job_search) - 一个搜索从Elixir / Phoenix和React / Redux编写的网站上抓取的创业工作的总体项目.
* [tty2048](https://github.com/lexmag/tty2048) - 基于终端的2048游戏用Elixir编写.
* [uai_shot](https://github.com/sergioaugrod/uai_shot) - 使用Elixir，Phoenix Framework和Phaser构建的多人游戏.

## Artificial Intelligence
*当你的代码变得比你聪明时.*

* [Exnn](https://github.com/zampino/exnn) - 用Elixir编写的G.Sher的演化神经网络框架.
* [Neat-Ex](https://gitlab.com/onnoowl/Neat-Ex) -  NEAT算法的Elixir实现.
* [simple_bayes](https://github.com/fredwu/simple_bayes) -  Elixir中的简单贝叶斯/朴素贝叶斯实现.

## Audio and Sounds
*使用声音和音调的图书馆.*

* [erlaudio](https://github.com/asonge/erlaudio) -  Erlang PortAudio绑定.
* [firmata](https://github.com/entone/firmata) - 该软件包实现了Firmata协议.
* [synthex](https://github.com/bitgamma/synthex) - 信号合成库.

## Authentication
*Libraries for implementing authentication schemes.*

* [aeacus](https://github.com/zmoshansky/aeacus) - 简单的可配置身份/密码验证模块（与Ecto / Phoenix兼容）.
* [apache_passwd_md5](https://github.com/kevinmontuori/Apache.PasswdMD5) -  Apache / APR样式密码哈希.
* [aws_auth](https://github.com/bryanjos/aws_auth) - 针对Elixir的AWS签名版本4签名库.
* [basic_auth](https://github.com/CultivateHQ/basic_auth) -  Elixir Plug可轻松将HTTP基本身份验证添加到应用程序.
* [coherence](https://github.com/smpallen99/coherence) -  Coherence是Phoenix的全功能，可配置的身份验证系统.
* [doorman](https://github.com/BlakeWilliams/doorman) - 使Elixir身份验证简单灵活的工具.
* [github_oauth](https://github.com/lidashuang/github_oauth) - 一个简单的github oauth库.
* [goth](https://github.com/peburrows/goth) - 通过Google Cloud API为服务器到服务器应用程序提供的OAuth 2.0库.
* [guardian](https://github.com/ueberauth/guardian) - 用于Elixir应用程序的身份验证框架.
* [htpasswd](https://github.com/kevinmontuori/Apache.htpasswd) -  Elixir中的Apache htpasswd文件读取器/写入器.
* [mojoauth](https://github.com/mojolingo/mojo-auth.ex) -  Elixir中的MojoAuth实现.
* [oauth2](https://github.com/scrogson/oauth2) -  Elixir的OAuth 2.0客户端库.
* [oauth2_facebook](https://github.com/chrislaskey/oauth2_facebook) -  Elixir的Facebook OAuth2提供商.
* [oauth2_github](https://github.com/chrislaskey/oauth2_github) -  Elixir的GitHub OAuth2提供程序.
* [oauth2cli](https://github.com/mgamini/oauth2cli-elixir) - 为Elixir编写的简单OAuth2客户端.
* [oauth2ex](https://github.com/parroty/oauth2ex) -  Elixir的另一个OAuth 2.0客户端库.
* [oauther](https://github.com/lexmag/oauther) -  Elixir的OAuth 1.0实现.
* [passwordless_auth](https://github.com/madebymany/passwordless_auth) -  Elixir的简单无密码登录或双因素/多因素身份验证.
* [phauxth](https://github.com/riverrun/phauxth) -  Phoenix 1.3和其他基于插件的应用程序的身份验证库.
* [phoenix_client_ssl](https://github.com/jshmrtn/phoenix-client-ssl) -  Phoenix和其他基于插件的应用程序的客户端SSL身份验证插件.
* [samly](https://github.com/handnot2/samly) -  SAML SP SSO变得简单（[Doc](https://hexdocs.pm/samly/readme.html)).
* [sesamex](https://github.com/khusnetdinov/sesamex) -  5分钟内另一种简单灵活的身份验证解决方案！
* [shield](https://github.com/mustafaturan/shield) -  Phoenix Framework的OAuth 2.0提供程序库和实现.
* [sigaws](https://github.com/handnot2/sigaws) -  AWS Signature V4签名和验证库（[Doc](https://hexdocs.pm/sigaws/Sigaws.html)).
* [ueberauth](https://github.com/ueberauth/ueberauth) - 基于插件的Web应用程序的Elixir身份验证系统.
* [ueberauth_auth0](https://hex.pm/packages/ueberauth_auth0) - 使用Auth0验证用户身份的Ueberauth策略.
* [ueberauth_cas](https://github.com/marceldegraaf/ueberauth_cas) - Überauth的中央认证服务战略.
* [ueberauth_facebook](https://github.com/ueberauth/ueberauth_Facebook) - Überauth的Facebook OAuth2战略.
* [ueberauth_foursquare](https://github.com/borodiychuk/ueberauth_foursquare) - Überauth的Foursquare OAuth2策略.
* [ueberauth_github](https://github.com/ueberauth/ueberauth_github) - Überauth的GitHub策略.
* [ueberauth_google](https://github.com/ueberauth/ueberauth_google) - Überauth的Google策略.
* [ueberauth_identity](https://github.com/ueberauth/ueberauth_identity) - Überauth的简单用户名/密码策略.
* [ueberauth_line](https://github.com/alexfilatov/ueberauth_line) - Überauth的LINE战略.
* [ueberauth_microsoft](https://github.com/swelham/ueberauth_microsoft) - Überauth的Microsoft战略.
* [ueberauth_slack](https://github.com/ueberauth/ueberauth_slack) - Überauth的Slack战略.
* [ueberauth_twitter](https://github.com/ueberauth/ueberauth_twitter) - Überauth的推特策略.
* [ueberauth_vk](https://github.com/sobolevn/ueberauth_vk) - [vk.com](https://vk.com) Überauth战略.
* [ueberauth_weibo](https://github.com/he9qi/ueberauth_weibo) - [Weibo](https://weibo.com) Überauth的OAuth2战略.

## Authorization
*用于实施授权处理的库.*

* [authorize](https://github.com/jfrolich/authorize) - 基于规则的授权，用于高级授权规则.
* [bodyguard](https://github.com/schrockwell/bodyguard) -  Phoenix应用程序的灵活授权库.
* [canada](https://github.com/jarednorman/canada) - 一个简单的授权库，使用声明性权限规则提供友好的接口.
* [canary](https://github.com/cpjk/canary) -  Elixir应用程序的授权库，用于限制当前用户可以访问的资源.
* [speakeasy](https://github.com/coryodaniel/speakeasy) - 由Bodyguard提供的Absinthe GraphQL的基于中间件的身份验证和授权.
* [terminator](https://github.com/MilosMosovsky/terminator) - 基于数据库的授权（ACL），具有用于要求所需权限的自定义DSL规则.

## Behaviours and Interfaces
*定义某些事物应该如何表现，例如来自OOP-World的界面*

* [connection](https://github.com/fishcakez/connection)   - 连接过程的连接行为.  API是GenServer API的超集.
* [gen_state_machine](https://github.com/antipax/gen_state_machine) -  gen_statem的Elixir包装器.
* [stockastic](https://github.com/shanewilton/stockastic) -  Stockfighter API的简单Elixir包装.

## Benchmarking
*运行代码以查看需要多长时间，哪些更快和/或是否已经进行了改进.*

* [benchee](https://github.com/PragTob/benchee) -  Elixir中简单易用的基准测试！
* [benchfella](https://github.com/alco/benchfella) -  Elixir的基准测试工具.
* [bmark](https://github.com/joekain/bmark) -  Elixir的基准测试工具.

## Bittorrent
*分享照顾Elixir *

* [bento](https://github.com/folz/bento) - 一个非常快速，正确，纯粹的Elixir Bencoding库.
* [tracker_request](https://github.com/alehander42/tracker_request) - 处理bittorrent跟踪器请求和响应.
* [wire](https://github.com/alehander42/wire) - 使用Elixir对bittorrent对等线协议消息进行编码和解码.

## BSON
*与BSON合作的图书馆和实施.*

* [BSONMap](https://github.com/Nebo15/bsoneach) -  Elixir软件包，它将函数应用于BSON文件中的每个文档，并且内存消耗较低.
* [cyanide](https://github.com/ispirata/cyanide) -  Elixir BSON编码/解码库.

## Build Tools
*项目构建和自动化工具.*

* [active](https://github.com/synrc/active) - 重新编译和重新加载FileSystem更改.
* [coffee_rotor](https://github.com/HashNuke/coffee_rotor) - 用于编译CoffeeScript文件的Rotor插件.
* [dismake](https://github.com/jarednorman/dismake) - 混合编译器运行make.
* [etude](https://github.com/exstruct/etude) -  Erlang / Elixir的并行计算协调编译器.
* [ExMake](https://github.com/lycus/exmake) - 一个基于Make原则的现代，可编写脚本，基于依赖性的构建工具.
* [Exscript](https://github.com/liveforeverx/exscript) -  Elixir escript库.
* [mad](https://github.com/synrc/mad) - 小而快速的钢筋更换.
* [pc](https://github.com/blt/port_compiler) - 一个rebar3端口编译器.
* [reaxt](https://github.com/awetzel/reaxt) - 将模板反射到Elixir应用程序中以进行服务器渲染.
* [rebar3_abnfc_plugin](https://github.com/surik/rebar3_abnfc_plugin) -  Rebar3 abnfc编译器.
* [rebar3_asn1_compiler](https://github.com/pyykkis/rebar3_asn1_compiler) - 使用Rebar3编译ASN.1模块的插件.
* [rebar3_auto](https://github.com/vans163/rebar3_auto) -  Rebar3插件自动编译和重新加载文件更改.
* [rebar3_diameter_compiler](https://github.com/carlosedp/rebar3_diameter_compiler) - 在rebar3项目中编译直径.dia文件.
* [rebar3_eqc](https://github.com/kellymclaughlin/rebar3-eqc-plugin) - 一个rebar3插件，用于执行Erlang QuickCheck属性.
* [rebar3_exunit](https://github.com/processone/rebar3_exunit) - 一个从rebar3构建工具运行Elixir ExUnit测试的插件.
* [rebar3_idl_compiler](https://github.com/sebastiw/rebar3_idl_compiler) - 这是一个使用Rebar3编译Erlang IDL文件的插件.
* [rebar3_live](https://github.com/pvmart/rebar3_live) -  Rebar3 live插件.
* [rebar3_neotoma_plugin](https://github.com/zamotivator/rebar3_neotoma_plugin) -  Rebar3 neotoma（Parser Expression Grammar）编译器.
* [rebar3_protobuffs](https://github.com/benoitc/rebar3_protobuffs) - 使用Basho的protobuffs提供的rebar3 protobuffs提供程序.
* [rebar3_run](https://github.com/tsloughter/rebar3_run) - 使用一个简单的命令运行发布.
* [rebar3_yang_plugin](https://github.com/surik/rebar3_yang_plugin) -  Rebar3编译器.
* [reltool_util](https://github.com/okeuday/reltool_util) -  Erlang reltool实用程序功能应用程序.
* [relx](https://github.com/erlware/relx) -  Erlang的发布汇编程序.
* [remix](https://github.com/AgilionApps/remix) - 在文件更改时自动重新编译Mix代码.
* [rotor](https://github.com/HashNuke/rotor) -  Elixir的超简单构建系统.
* [sass_elixir](https://github.com/zamith/sass_elixir) -  Elixir项目的sass插件.

## Caching
*用于缓存数据的库.*

* [cachex](https://github.com/whitfin/cachex) -  Elixir强大的缓存库，具有广泛的功能集.
* [con_cache](https://github.com/sasa1977/con_cache) -  ConCache是​​基于ETS的键/值存储.
* [elixir_locker](https://github.com/tsharju/elixir_locker) -  Locker是一个Elixir包装器，用于存放Erlang库，它提供了一些有用的库，可以更容易地使用locker.
* [gen_spoxy](https://github.com/SpotIM/gen_spoxy) - 缓存很有趣.
* [jc](https://github.com/jr0senblum/jc) - 具有pub / sub，JSON查询和一致性支持的内存中可分发缓存.
* [locker](https://github.com/wooga/locker) -  Atomic为短期密钥分发“检查和设置”.
* [lru_cache](https://github.com/arago/lru_cache) - 使用ets实现的简单LRU缓存.
* [memoize](https://github.com/melpon/memoize) - 一个容易缓存功能的memoization宏.
* [nebulex](https://github.com/cabol/nebulex) -  Elixir的快速，灵活和可扩展的分布式和本地缓存库.
* [stash](https://github.com/whitfin/stash) - 简单，快速，用户友好的键/值存储.

## Chatting
*使用Elixir通过IRC，Slack，HipChat和其他系统聊天.*

* [alice](https://github.com/alice-bot/alice) -  Elixir的Slack bot框架.
* [chatty](https://github.com/alco/chatty) - 对编写机器人最有用的基本IRC客户端.
* [cog](https://github.com/operable/cog) -  Cog是一个开放的chatops平台，可以在聊天窗口中为您提供安全，协作的命令行.
* [ExIrc](https://github.com/bitwalker/exirc) - 用于Elixir项目的IRC客户端适配器.
* [ExMustang](https://github.com/techgaun/ex_mustang) - 一个简单，无能的slackbot和响应者的集合.
* [Guri](https://github.com/elvio/guri) - 使用聊天消息自动执行任务.
* [hedwig](https://github.com/hedwig-im/hedwig) -  Elixir的XMPP客户端/ Bot框架.
* [hipchat_elixir](https://github.com/ymtszw/hipchat_elixir) - 基于httpc的Elixir的HipChat客户端库.
* [kaguya](https://github.com/Luminarys/Kaguya) - 小型，功能强大且模块化的IRC机器人.
* [slacker](https://github.com/koudelka/slacker) -  Slack聊天服务的bot库.
* [yocingo](https://github.com/Yawolf/yocingo) - 创建自己的Telegram Bot.

## Cloud Infrastructure and Management
*适用于您自己的云服务的应用程序，工具和库.*

* [aws](https://github.com/jkakar/aws-elixir) - AWS clients for Elixir.
* [Bonny](https://github.com/coryodaniel/bonny) -  Kubernetes运营商发展框架.
* [Cloudi](http://cloudi.org/) -  CloudI用于需要软实时事务的后端服务器处理任务.
* [discovery](https://github.com/undeadlabs/discovery) - 使用Consul自动发现服务的OTP应用程序.
* [erlcloud](https://github.com/erlcloud/erlcloud) - 针对Erlang的云计算库（Amazon EC2，S3，SQS，SimpleDB，Mechanical Turk，ELB）.
* [ex_aws](https://github.com/CargoSense/ex_aws) -  AWS客户端，支持Dynamo，Kinesis，Lambda，SQS和S3.
* [ex_riak_cs](https://github.com/ayrat555/ex_riak_cs) -  Riak CS API客户端.
* [fleet_api](https://github.com/jordan0day/fleet-api) - A simple wrapper for the Fleet (CoreOS) API. Can be used with etcd tokens or via direct node URLs.
* [Gandi](https://github.com/Ahamtech/elixir-Gandi) -  Gandi Wrapper for Leaseweb基础设施.
* [IElixir](https://github.com/pprzetacznik/IElixir) -  Jupyter的Elixir编程语言内核.
* [Kazan](https://github.com/obmarg/kazan) - 用于Elixir的Kubernetes客户端，由k8s开放API规范生成.
* [Kubex](https://github.com/ingerslevio/kubex) - 用纯粹的Elixir编写的Kubernetes客户端和Elixir的集成.
* [Leaseweb](https://github.com/Ahamtech/elixir-leaseweb) - 用于Leaseweb基础设施的Elixir Wrapper.
* [libcluster](https://github.com/bitwalker/libcluster) -  Elixir应用程序的自动簇形成/修复.
* [nodefinder](https://github.com/okeuday/nodefinder) -  Erlang中自动节点发现的策略.
* [nomad](https://github.com/sashaafm/nomad)   - 创建云便携式Elixir和Phoenix应用程序.  写一次，到处使用！
* [sidejob](https://github.com/basho/sidejob) -  Erlang的并行工作器和容量限制库.
* [sidetask](https://github.com/PSPDFKit-labs/sidetask) -  SideTask是使用Basho的sidejob库并具有并行性和容量限制的Task.Supervisor的替代方案.
* [skycluster](https://github.com/Nebo15/skycluster)   -  Elixir / Erlang应用程序的自动Erlang集群形成，消息传递和管理.  与Kubernetes集成.

## Code Analysis
*用于代码库分析，解析和操作的库和工具.*

* [belvedere](https://github.com/nirvana/belvedere) -  CircleCI与Elixir集成的一个例子.
* [coverex](https://github.com/alfert/coverex) -  Elixir的覆盖率报告.
* [credo](https://github.com/rrrene/credo) - 静态代码分析工具，重点关注代码一致性和教授Elixir.
* [dialyxir](https://github.com/jeremyjh/dialyxir) - 混合任务以简化Elixir项目中Dialyzer的使用.
* [dogma](https://github.com/lpil/dogma) -  Elixir的代码风格的linter，由羞耻驱动.
* [excoveralls](https://github.com/parroty/excoveralls) -  Elixir的Coverage报告工具与coveralls.io集成.
* [exprof](https://github.com/parroty/exprof) - 使用eprof的Elixir简单代码分析器.

## Command Line Applications
*任何有助于构建CLI应用程序的东西.*

* [anubis](https://github.com/bennyhallett/anubis) -  Elixir的命令行应用程序框架.
* [ex_cli](https://github.com/tuvistavie/ex_cli) -  Elixir的用户友好CLI应用程序.
* [ex_prompt](https://github.com/behind-design/ex_prompt) - 帮助程序包，以尽可能简单地为命令行应用程序添加交互性.
* [firex](https://github.com/msoedov/firex) -  Firex是一个用于从elixir模块自动生成命令行界面（CLI）的库.
* [getopt](https://github.com/jcomellas/getopt) -  Erlang的命令行选项解析器.
* [loki](https://github.com/khusnetdinov/loki) - 用于创建交互式命令行应用程序的库.
* [meld](https://github.com/Lac/meld) - 从混合任务创建全局二进制文件.
* [optimus](https://github.com/savonarola/optimus) - 灵感来自Elixir的命令行选项解析器 [clap.rs](https://clap.rs/).
* [phoenix-cli](https://phoenix-cli.github.io/) -  Phoenix Framework的命令行界面，如Rails命令.
* [progress_bar](https://github.com/henrik/progress_bar) - 命令行进度条和微调器.
* [ratatouille](https://github.com/ndreynolds/ratatouille) -  Elixir的TUI（终端UI）工具包.
* [scribe](https://github.com/codedge-llc/scribe)   -  Elixir结构和地图的漂亮印刷表.  受到hirb的启发.
* [table_rex](https://github.com/djm/table_rex) - 生成可配置的ASCII样式表以供显示.
* [tabula](https://github.com/aerosol/tabula) - 在ascii表中的Ecto查询结果/映射的漂亮打印列表（GitHub Markdown / OrgMode）.

## Configuration
*使用配置的库和工具*

* [confex](https://github.com/Nebo15/confex) -  Helper模块，提供了一种在运行时读取环境配置的好方法.
* [configparser_ex](https://github.com/easco/configparser_ex) - 一个简单的Elixir解析器，用于Python的configparser库处理的相同类型的文件.
* [conform](https://github.com/bitwalker/conform) -  Elixir应用程序的轻松发布配置.
* [dotenv](https://github.com/avdi/dotenv_elixir) -  Dotenv到Elixir的一个港口.
* [ex_conf](https://github.com/phoenixframework/ex_conf) - 简单的Elixir配置管理.
* [figaro](https://github.com/trestrantham/ex_figaro) - 简单的Elixir项目配置.
* [figaro_elixir](https://github.com/KamilLelonek/figaro-elixir) -  Elixir的环境变量经理.
* [sweetconfig](https://github.com/d0rc/sweetconfig) - 从您应用的任何位置读取YAML配置文件.
* [weave](https://github.com/GT8Online/weave) - 与Kubernetes和Docker Swarm一起使用的JIT配置加载程序.

## Cryptography
*加密和解密数据*

* [aescmac](https://github.com/kleinernik/elixir-aes-cmac) -  AES CMAC（[RFC 4493](https://tools.ietf.org/html/rfc4493)）在药剂.
* [cipher](https://github.com/rubencaro/cipher) -  Elixir加密库，用于加密/解密任意二进制文件.
* [cloak](https://github.com/danielberkompas/cloak) -  Cloak使用Ecto轻松加密.
* [comeonin](https://github.com/riverrun/comeonin) -  Elixir的密码哈希（argon2，bcrypt，pbkdf2_sha512）库.
* [crypto_rsassa_pss](https://github.com/potatosalad/erlang-crypto_rsassa_pss) - 用于Erlang的RSASSA-PSS公钥密码签名算法.
* [elixir_tea](https://github.com/keichan34/elixir_tea) - 在Elixir中实施TEA.
* [ex_bcrypt](https://github.com/manelli/ex_bcrypt) - 用于OpenBSD bcrypt密码散列算法的Elixir包装器.
* [ex_crypto](https://github.com/ntrepid8/ex_crypto)   -  Erlang`crypto`和`public_key`模块的Elixir包装器.  为许多加密函数提供合理的默认值，使其更易于使用.
* [exgpg](https://github.com/rozap/exgpg) - 使用Elixir的gpg.
* [ntru_elixir](https://github.com/alisinabh/ntru_elixir)   - 针对libntru的Elixir包装器.  后量子密码系统.
* [one_time_pass_ecto](https://github.com/riverrun/one_time_pass_ecto) -  Elixir的一次性密码库.
* [pot](https://github.com/yuce/pot) - 用于生成与Google身份验证器兼容的一次性密码的Erlang库.
* [rsa](https://github.com/trapped/elixir-rsa) -  Elixir的`public_key`加密包装器.
* [rsa_ex](https://github.com/anoskov/rsa-ex) - 用于处理RSA密钥的库.
* [siphash-elixir](https://github.com/whitfin/siphash-elixir) -  Elixir实现SipHash哈希族.
* [tea_crypto](https://github.com/keichan34/tea_crypto_erl) - 微小的加密算法实现.

## CSV
*使用CSV的库和实现.*

* [cesso](https://github.com/meh/cesso) -  Elixir的CSV处理库.
* [csv](https://github.com/beatrichartz/csv) -  Elixir的CSV解码和编码.
* [csvlixir](https://github.com/jimm/csvlixir) -  Elixir的CSV读/写应用程序.
* [ex_csv](https://github.com/CargoSense/ex_csv) -  Elixir的CSV.
* [nimble_csv](https://github.com/plataformatec/nimble_csv) -  Elixir的简单快速的CSV解析和转储库.

## Date and Time
*处理日期和时间的图书馆.*

* [block_timer](https://github.com/adamkittelson/block_timer) - 要使用的宏：timer.apply_after和：带有块的timer.apply_interval.
* [calendar](https://github.com/lau/calendar) - 日历是Elixir的日期和时间库.
* [chronos](https://github.com/nurugger07/chronos) -  Elixir日期/时间库.
* [cocktail](https://github.com/peek-travel/cocktail) - 基于iCalendar事件的Elixir日期重复库.
* [cronex](https://github.com/jbernardo95/cronex) - 您可以在监督树中安装的Cron系统.
* [crontab](https://github.com/jshmrtn/crontab) -  Cron Expressions Parser，Composer和Date Candidate Finder.
* [ex_ical](https://github.com/fazibear/ex_ical) -  ICalendar解析器.
* [filtrex](https://github.com/rcdilorenzo/filtrex) - 用于从客户端执行和验证复杂的类似SQL的过滤器的库（例如智能过滤器）.
* [good_times](https://github.com/DevL/good_times) - 具有表现力和易于使用的日期时间功能.
* [jalaali](https://github.com/jalaali/elixir-jalaali) -  Elixir的Jalaali日历实施.
* [milliseconds](https://github.com/davebryson/elixir_milliseconds) - 简单的库在Elixir中使用毫秒.
* [moment](https://github.com/atabary/moment) - 在Elixir中解析，验证，操纵和显示日期.
* [quantum](https://github.com/c-rack/quantum-elixir) - Cron-like job scheduler for Elixir applications.
* [repeatex](https://github.com/rcdilorenzo/repeatex) - 重复日期的自然语言解析.
* [tiktak](https://github.com/ConduitMobileRND/tiktak) - 用Elixir编写的快速轻量级Web调度程序.
* [timelier](https://github.com/ausimian/timelier) -  Elixir的cron风格调度程序.
* [timex](https://github.com/bitwalker/timex) -  Elixir易于使用的日期和时间模块.
* [timex_interval](https://github.com/atabary/timex-interval) - 基于Timex的Elixir项目的日期/时间间隔库.
* [tzdata](https://github.com/lau/tzdata) -  Elixir中的时区数据库.

## Debugging
*用于调试代码和应用程​​序的库和工具.*

* [beaker](https://github.com/hahuang65/beaker) -  Elixir的统计和度量库.
* [booter](https://github.com/eraserewind/booter) - 一步一步地启动Elixir应用程序.
* [dbg](https://github.com/fishcakez/dbg) -  Elixir的分布式跟踪.
* [eflame](https://github.com/proger/eflame) -  Erlang的Flame Graph分析器.
* [eh](https://github.com/Frost/eh) - 从命令行查找Elixir文档的工具.
* [eper](https://github.com/massemanet/eper) -  Erlang性能和调试工具.
* [ether](https://github.com/maarek/ether) -  Ether提供将Elixir挂钩到Erlang调试器的功能.
* [ex_debug_toolbar](https://github.com/kagux/ex_debug_toolbar) -  Phoenix项目的工具栏，以交互方式调试代码并显示有关请求的有用信息：日志，时间轴，数据库查询等.
* [exrun](https://github.com/liveforeverx/exrun) -  Elixir的分布式跟踪，具有速率限制和简单的基于宏的界面.
* [git_hooks](https://github.com/qgadrian/elixir_git_hooks) - 添加git钩子到Elixir项目.
* [observer_cli](https://github.com/zhongwencool/observer_cli) - 在命令行上可视化Elixir和Erlang节点，它旨在帮助开发人员调试生产系统.
* [quaff](https://github.com/qhool/quaff) -  Debug模块提供了一个简单的辅助接口，用于在erlang图形化调试器中运行Elixir代码.
* [rexbug](https://github.com/nietaki/rexbug) - 用于`redbug`生产友好的Erlang跟踪调试器的Elixir包装器.
* [visualixir](https://github.com/koudelka/visualixir) - 远程BEAM节点的进程可视化工具.

## Deployment
*在其他机器上自动安装和运行代码.*

* [akd](https://github.com/annkissam/akd) -  Capistrano like，Configurable，易于设置Elixir Deployment Automation Framework.
* [ansible-elixir-stack](https://github.com/HashNuke/ansible-elixir-stack) -  1命令设置和部署到服务器，为Phoenix应用程序提供一流支持.
* [bootleg](https://github.com/labzero/bootleg) -  Elixir的简单部署和服务器自动化.
* [bottler](https://github.com/rubencaro/bottler) -  Bottler是一系列工具，旨在帮助您生成版本，将它们发送到您的服务器，在那里安装，并让它们在生产中生效.
* [edeliver](https://github.com/boldpoker/edeliver) - 部署Elixir和Erlang.
* [elixir-on-docker](https://github.com/CrowdHailer/elixir-on-docker) - 开始为云环境开发集群Elixir应用程序的项目模板.
* [exdm](https://github.com/joeyates/exdm) - 通过混合任务部署Elixir应用程序.
* [exreleasy](https://github.com/miros/exreleasy) -  Dead简单和混合友好工具，用于释放Elixir应用程序.
* [gatling](https://github.com/hashrocket/gatling) - 收集混合任务以自动从git创建exrm版本并在服务器上启动/升级它.
* [Gigalixir](https://www.gigalixir.com)   - 为Elixir设计的功能齐全的PaaS.  支持群集，热升级和远程控制台/观察器.  免费试用没有信用卡.
* [heroku-buildpack-elixir](https://github.com/HashNuke/heroku-buildpack-elixir) -  Heroku buildpack将Elixir应用程序部署到Heroku.
* [Nanobox](https://github.com/nanobox-io/nanobox) - 用于创建可在任何地方部署的一致，隔离的开发环境的微型PaaS（μPaaS）https://nanobox.io.

## Documentation
*用于创建文档的库和工具.*

* [blue_bird](https://github.com/KittyHeaven/blue_bird)   -  BlueBird是一个用Phoenix框架的Elixir编程语言编写的库.  它允许您从控制器和自动化测试中的注释生成API蓝图格式的API文档.
* [bureaucrat](https://github.com/api-hogs/bureaucrat) - 从测试中生成Phoenix API文档.
* [ex_doc](https://github.com/elixir-lang/ex_doc) -  ExDoc是一个为Elixir项目生成文档的工具.
* [ex_doc_dash](https://github.com/JonGretar/ExDocDash) -  ExDoc的Formatter，用于生成在Dash.app中使用的docset文档.
* [hexdocset](https://github.com/yesmeck/hexdocset) - 将hex doc转换为Dash.app的docset格式.
* [inch-ci](http://inch-ci.org/) -  Ruby＆Elixir的文档徽章.
* [maru_swagger](https://github.com/falood/maru_swagger) - 在您的maru API中添加符合Swagger标准的文档.
* [phoenix_api_docs](https://github.com/smoku/phoenix_api_docs) - 从Phoenix框架中的控制器和测试生成API Blueprint文档.
* [phoenix_swagger](https://github.com/xerions/phoenix_swagger) - 提供与Phoenix框架的swagger集成.

## Domain-specific language
*特定应用领域的专用计算机语言.*

* [Absinthe Graphql](https://github.com/absinthe-graphql/absinthe) - 功能齐全的GraphQL库.
* [JSON-LD.ex](https://github.com/marcelotto/jsonld-ex) - 执行 [JSON-LD](http://www.w3.org/TR/json-ld/) 标准 [RDF.ex](https://github.com/marcelotto/rdf-ex).
* [RDF.ex](https://github.com/marcelotto/rdf-ex) - 执行 [RDF](https://www.w3.org/TR/rdf11-primer/) Elixir中的数据模型.
* [SPARQL.ex](https://github.com/marcelotto/sparql-ex) - 执行 [SPARQL](http://www.w3.org/TR/sparql11-overview/) Elixir的标准.

## ECMAScript
*使用JavaScript，JScript或ActionScript实现.*

* [elixirscript](https://github.com/elixirscript/elixirscript/) - 从Elixir到Javascript的转换器.
* [estree](https://github.com/bryanjos/elixir-estree) -  Elixir中SpiderMonkey Parser API的实现.
* [phoenix_gon](https://github.com/khusnetdinov/phoenix_gon) - 允许您将Phoenix环境或控制器变量传递给JavaScript而不会出现问题.
* [phoenix_routes_js](https://github.com/khusnetdinov/phoenix_routes_js) -  Phoenix在JavaScript代码和浏览器控制台中路由助手.

## Email
*使用电子邮件和东西.*

* [bamboo](https://github.com/thoughtbot/bamboo)   - 可组合，可测试和基于适配器的电子邮件库.  开箱即用支持使用Phoenix进行渲染，并使用插件预览开发中的已发送电子邮件.
* [burnex](https://github.com/Betree/burnex) -  Burner电子邮件（临时地址）检测器.
* [echo](https://github.com/zmoshansky/echo)   - 元通知系统;  Echo检查通知首选项和发送通知.
* [ex_postmark](https://github.com/KamilLelonek/ex_postmark) - 用于在Elixir中发送模板电子邮件的邮戳适配器.
* [gen_smtp](https://github.com/Vagabond/gen_smtp) - 可以通过回调模块扩展的通用Erlang SMTP服务器和客户端.
* [gmail](https://github.com/craigp/elixir-gmail) -  Elixir的简单Gmail REST API客户端.
* [mail](https://github.com/DockYard/elixir-mail) -  Elixir中的RFC2822实现，专为可组合性而构建.
* [mailer](https://github.com/antp/mailer) - 一个简单的SMTP邮件程序.
* [mailibex](https://github.com/awetzel/mailibex) - 包含Elixir中与电子邮件相关的实现的库：dkim，spf，dmark，mimemail，smtp.
* [mailman](https://github.com/kamilc/mailman) -  Mailman提供了一种在Elixir应用程序中定义邮件程序的简洁方法.
* [pop3mail](https://hex.pm/packages/pop3mail) -  Pop3客户端通过命令行或Elixir API从收件箱下载电子邮件（包括附件）.
* [ravenx](https://github.com/acutario/ravenx) -  Elixir应用程序的通知调度库.
* [smoothie](https://github.com/jfrolich/smoothie) - 电子邮件模板的Smoothie内联样式，并从HTML生成纯文本版本.
* [swoosh](https://github.com/swoosh/swoosh) - 使用SMTP，Sendgrid，Mandrill，Mailgun，Postmark和Phoenix与邮箱预览集成的适配器，轻松地在Elixir中编写，交付和测试您的电子邮件.

## Embedded Systems
*嵌入式系统开发.*

* [nerves](http://nerves-project.org) - 在Elixir中编写嵌入式软件的框架.

## Encoding and Compression
*以不同格式转换数据或压缩数据.*

* [ex_rlp](https://github.com/exthereum/ex_rlp) -  Elixir实现的以太坊的RLP（递归长度前缀）编码.
* [huffman](https://github.com/SenecaSystems/huffman) -  Elixir中的霍夫曼编码和解码.

## Errors and Exception Handling
*处理错误和例外.*

* [exceptional](https://github.com/expede/exceptional) - 快乐路径编程和异常处理的助手.
* [happy](https://github.com/vic/happy) - 快乐路径编程，替代elixir`with`形式.
* [OK](https://github.com/CrowdHailer/OK) - 使用结果monad进行优雅的错误处理，具有简单而强大的`with`结构和快乐的路径管道操作符.
* [sentry-elixir](https://github.com/getsentry/sentry-elixir) -  Elixir官方客户 [Sentry](https://sentry.io/).

## Eventhandling
*在Elixir中发送/发送和接收/处理事件.*

* [cizen](https://gitlab.com/cizen/cizen) - 使用一系列传奇来构建高度并发，可监控和可扩展的应用程序.
* [event_bus](https://github.com/mustafaturan/event_bus) - 使用主题过滤和内置事件存储和事件监视器的简单事件总线实现.
* [goldrush](https://github.com/DeadZen/goldrush) - 针对Erlang / OTP应用程序的小型，快速事件处理和监视.
* [reaxive](https://github.com/alfert/reaxive) -  Reaxive是一个反应式事件处理库，受到启发 [Elm](http://elm-lang.org) 和反应性扩展.
* [wait_for_it](https://github.com/jvoegele/wait_for_it) - 提供方便易用的同步活动同步设施.

## Examples and funny stuff
*示例代码和太有趣或好奇的东西，更不用说了.*

* [butler_cage](https://github.com/keathley/butler_cage) - 一个Butler插件，用于显示Nick Cage的愚蠢照片.
* [butler_tableflip](https://github.com/keathley/butler_tableflip) - 用管家翻转桌子.
* [changelog.com](https://github.com/thechangelog/changelog.com) - 运行使用Phoenix 1.4构建的changelog.com的CMS.
* [dice](https://github.com/stocks29/dice) - 在Elixir掷骰子.
* [elixir_koans](https://github.com/elixirkoans/elixir-koans) - [Elixir koans](http://elixirkoans.io/) 是一种有趣，简单的方法来开始使用elixir编程语言.
* [ex_chain](https://github.com/eljojo/ex_chain) - 简单的马尔可夫链，使用Elixir生成有趣的推文.
* [ex_iss](https://github.com/cryptobird/ex_iss) - 此软件包用于与Open Notify API连接，以获取ISS当前位置，工作人员以及何时通过某个位置等信息.
* [feedx](https://github.com/erneestoc/feedx)   - 为当前应用程序添加社交订阅源功能.  使用3个应用程序举例说明OTP伞形应用程序.  薄凤凰控制器.
* [harakiri](https://github.com/rubencaro/harakiri) - 帮助应用程序自杀.
* [hello_phoenix](https://github.com/bigardone/phoenix-react-redux-template) - 使用Phoenix，React和Redux的SPA的应用程序模板.
* [hexpm](https://github.com/hexpm/hexpm) - 使用Phoenix 1.3构建的十六进制包管理器站点的源代码.
* [kaisuu](https://github.com/SebastianSzturo/kaisuu) - 在Twitter上实时观看日本的汉字用法.
* [koans](https://github.com/dojo-toulouse/elixir-koans) - 使用elixir-koans学习Elixir.
* [lolcat](https://github.com/restartr/ex-lolcat)   - 这是busyloop / lolcat的克隆.  但它不支持动画和原始的一些功能.
* [magnetissimo](https://github.com/sergiotapia/magnetissimo) -  Web应用程序，索引所有流行的torrent网站，并将其保存到本地数据库.
* [oop](https://github.com/wojtekmach/oop) - 在Elixir中开放！
* [phoenix-flux-react](https://github.com/fxg42/phoenix-flux-react) -  Phoenix Channels，GenEvents，React和Flux的实验.
* [portal](https://github.com/josevalim/portal) -  Elixir中用于分布式门户数据传输应用的射击容错门.
* [real world example app](https://github.com/gothinkster/elixir-phoenix-realworld-example-app) -  Elixir / Phoenix实施 [RealWorld.io](https://realworld.io/) 后端规格 - 中等克隆.
* [rollex](https://gitlab.com/olhado/rollex) -  Elixir库使用Pratt Parser算法计算骰子卷.
* [rubix](https://github.com/YellowApple/Rubix) -  Elixir的一个非常简单（并且几乎没有功能）的Ruby跑步者.
* [stranger](https://github.com/cazrin/stranger) -  Elixir Phoenix应用程序匿名与随机选择的陌生人聊天.
* [tilex](https://github.com/hashrocket/tilex) - 使用Phoenix 1.3构建的Hashrocket的TIL网站的源代码.
* [weather](https://github.com/tacticiankerala/elixir-weather) - 使用Elixir构建的命令行天气应用程序.

## Feature Flags and Toggles
*用于管理功能切换的库（AKA功能标志）：可通过某些接口在运行时切换的ON / OFF值*

* [flippant](https://github.com/sorentwo/flippant) - 为Elixir世界翻转特征.
* [fun_with_flags](https://github.com/tompave/fun_with_flags)   - 使用Redis或Ecto进行持久化的功能切换库，用于速度的ETS缓存和用于分布式缓存清除的PubSub.  附带Phoenix和Plug的管理Web UI.
* [molasses](https://github.com/securingsincity/molasses) - 使用redis或SQL（使用Ecto）作为支持服务的功能切换库.

## Feeds
*使用RSS或ATOM等提要的图书馆.*

* [atomex](https://github.com/Betree/atomex) -  ATOM feed构建器，重点关注标准合规性，安全性和可扩展性.
* [feeder](https://github.com/michaelnisi/feeder) - 解析RSS和Atom提要.
* [feeder_ex](https://github.com/manukall/feeder_ex)   -  RSS提要解析器.  进料器的简单包装.
* [feedme](https://github.com/umurgdk/elixir-feedme) - 基于erlang的xmerl xml解析器构建的RSS / Atom解析器.

## Files and Directories
*用于处理文件和目录的库和实现.*

* [arc](https://github.com/stavro/arc) -  Elixir灵活的文件上传和附件库.
* [Belt](https://bitbucket.org/pentacent/belt/) - 可扩展文件上载库，支持SFTP，S3和文件系统存储.
* [cassius](https://github.com/jquadrin/cassius) - 监控Linux文件系统事件.
* [dir_walker](https://github.com/pragdave/dir_walker) -  DirWalker懒洋洋地遍历一个或多个目录树，深度优先，返回连续的文件名.
* [elixgrep](https://github.com/bbense/elixgrep) - 用于对文件集合执行Hadoop样式Map / Reduce操作的框架.
* [ex_guard](https://github.com/slashmili/ex_guard) -  ExGuard是一个混合命令，用于处理文件系统修改事件.
* [ex_minimatch](https://github.com/gniquil/ex_minimatch) - 没有走树的全球路径！
* [exfile](https://github.com/keichan34/exfile) -  Elixir和Plug中的文件上载处理，持久性和处理.
* [exfswatch](https://github.com/falood/exfswatch) - 基于__fs__的文件更改观察程序包装器.
* [eye_drops](https://github.com/rkotze/eye_drops) - 可配置的混合任务，用于监视文件更改并运行相应的命令.
* [format_parser.ex](https://github.com/ahtung/format_parser.ex) -  Elixir库，用于确定文件的类型和格式.
* [fs](https://github.com/synrc/fs) -  Erlang FileSystem Listener.
* [fwatch](https://github.com/ryo33/fwatch-ex) - 基于__fs__的基于回调的文件监视器.
* [librex](https://github.com/ricn/librex) - 使用LibreOffice将办公文档转换为其他格式的Elixir库.
* [Radpath](https://github.com/lowks/Radpath) -  Elixir的路径库，灵感来自Python的Enhpath.
* [sentix](https://github.com/whitfin/sentix) - 基于fswatch的Elixir跨平台文件监视器.
* [sizeable](https://github.com/arvidkahl/sizeable) -  Elixir库，使文件大小易于阅读.
* [zarex](https://github.com/ricn/zarex) -  Elixir的文件名清理.

## Formulars
*处理网络配方和类似的东西.*

* [forms](https://github.com/spawnproc/forms) -  Erlang商业文档生成器.

## Framework Components
*来自Web开发框架的独立组件.*

* [absinthe_plug](https://github.com/absinthe-graphql/absinthe_plug) -  Absinthe的插头支持.
* [addict](https://github.com/trenpixster/addict) -  Phoenix Framework的用户身份验证.
* [airbrake_plug](https://github.com/romul/airbrake_plug) - 报告插头堆栈中的错误或Airbrake的错误.
* [ashes](https://github.com/nickgartmann/ashes) -  Phoenix Web框架的代码生成工具.
* [better_params](https://github.com/sheharyarn/better_params) -  Elixir Plug用于网络应用程序中更清洁的请求参数.
* [blaguth](https://github.com/lexmag/blaguth) - 插件应用程序中的基本访问认证.
* [commanded](https://github.com/slashdotdash/commanded) - 命令处理Command Query Responsibility Segregation（CQRS）应用程序的中间件.
* [cors_plug](https://github.com/mschae/cors_plug) -  Elixir插件，可将CORS标头添加到请求并响应预检请求（OPTIONS）.
* [corsica](https://github.com/whatyouhide/corsica) - 用于处理CORS请求的Elixir库.
* [crudex](https://github.com/bitgamma/crudex) -  Phoenix和Ecto的CRUD实用程序.
* [dayron](https://github.com/inaka/Dayron) - 存储库_similar_到`Ecto.Repo`，它与REST API请求而不是数据库一起使用.
* [ex_admin](https://github.com/smpallen99/ex_admin) -  ExAdmin是Elixir和Phoenix Framework的自动管理包.
* [exdjango](https://github.com/nicksanders/exdjango) - 使用django的几个灵丹妙药库.
* [exrecaptcha](https://github.com/adanselm/exrecaptcha) -  Elixir应用程序的简单reCaptcha显示/验证代码.
* [filterable](https://github.com/omohokcoj/filterable) - 受Rails has_scope启发的Phoenix框架的简单查询参数过滤.
* [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - 一个Elixir绑定 [libgraphqlparser](https://github.com/graphql/libgraphqlparser).
* [http_router](https://github.com/sugar-framework/elixir-http-router) - 具有各种宏的HTTP路由器，可帮助开发应用程序和组织代码.
* [kerosene](https://github.com/elixirdrops/kerosene) -  Ecto和Phoenix的分页.
* [mellon](https://github.com/sajmoon/mellon) - 用于插件应用程序的验证模块.
* [multiverse](https://github.com/Nebo15/multiverse) - 允许通过API请求/响应网关添加版本兼容性层的插件.
* [params](https://github.com/vic/params) - 使用Ecto强制/验证参数结构，类似于Rails的强参数.
* [passport](https://github.com/opendrops/passport) -  Passport为Phoenix应用程序提供身份验证.
* [phoenix_ecto](https://github.com/phoenixframework/phoenix_ecto) -  Phoenix和Ecto集成.
* [phoenix_haml](https://github.com/chrismccord/phoenix_haml) -  Haml的Phoenix模板引擎.
* [phoenix_html](https://github.com/phoenixframework/phoenix_html) -  Phoenix.HTML函数用于处理HTML字符串和模板.
* [phoenix_html_sanitizer](https://github.com/elixirstatus/phoenix_html_sanitizer) -  Phoenix的HTML Sanitizer集成.
* [phoenix_html_simplified_helpers](https://github.com/ikeikeikeike/phoenix_html_simplified_helpers) - 凤凰html的一些助手（truncate，time_ago_in_words，number_with_delimiter）.
* [phoenix_linguist](https://github.com/jxs/phoenix_linguist) - 将Phoenix与Linguist集成在一起的项目，提供插件和视图助手.
* [phoenix_live_reload](https://github.com/phoenixframework/phoenix_live_reload) - 为Phoenix提供实时重载功能.
* [phoenix_pubsub_postgres](https://github.com/opendrops/phoenix-pubsub-postgres) - 用于Phoenix应用程序的Postgresql PubSub适配器.
* [phoenix_pubsub_rabbitmq](https://github.com/pma/phoenix_pubsub_rabbitmq) -  Phoenix的PubSub层的RabbitMQ适配器.
* [phoenix_pubsub_redis](https://github.com/phoenixframework/phoenix_pubsub_redis) -  Phoenix框架的Redis PubSub适配器.
* [phoenix_pubsub_vernemq](https://github.com/larshesel/phoenix_pubsub_vernemq) -  Phoenix框架的VerneMQ MQTT pubsub适配器.
* [phoenix_slime](https://github.com/slime-lang/phoenix_slime) - 凤凰城的超薄模板支持.
* [phoenix_token_auth](https://github.com/manukall/phoenix_token_auth)   -  Phoenix的令牌认证解决方案.  适用于API或单页应用程序.
* [plug](https://github.com/elixir-lang/plug) -  Web应用程序之间可组合模块的规范和便利.
* [plug_accesslog](https://github.com/mneudert/plug_accesslog) - 用于写入访问日志的插件.
* [plug_and_play](https://github.com/henrik/plug_and_play) - 设置具有较少样板的插头应用程序.
* [plug_auth](https://github.com/bitgamma/plug_auth) - 与认证相关的插头的集合.
* [plug_canonical_host](https://github.com/remiprev/plug_canonical_host) - 插件以确保从单个规范主机提供所有请求.
* [plug_checkup](https://github.com/ggpasqualino/plug_checkup) - 用于向您的应用添加简单运行状况检查的插件.
* [plug_cloudflare](https://github.com/c-rack/plug_cloudflare) - 受mod_cloudflare的启发，这个Elixir插件将Cloudflares CF-Connecting-IP HTTP请求头解析到Plug.Conn的remote_ip字段中.
* [plug_forward_peer](https://github.com/awetzel/plug_forwarded_peer) - 非常简单的插件，根据RFC7239读取X-Forwarded-For或Forwarded报头，并使用root客户端ip填写conn.remote_ip.
* [plug_fprof](https://github.com/obmarg/plug_fprof) - 一个插件，可以为请求添加fprof跟踪，以便于分析.
* [plug_graphql](https://github.com/graphql-elixir/plug_graphql) -  Phoenix Plug集成 [GraphQL Elixir](http://graphql-elixir.org/).
* [plug_heartbeat](https://github.com/whatyouhide/plug_heartbeat) - 用于响应心跳请求的插件.
* [plug_jwt](https://github.com/bryanjos/plug_jwt) - 用于JWT身份验证的插件.
* [plug_password](https://github.com/azranel/plug_password) - 用于添加简单的基于cookie的身份验证的插件.
* [plug_rails_cookie_session_store](https://github.com/cconstantin/plug_rails_cookie_session_store) - 兼容Rails的插件会话存储.
* [plug_redirect_https](https://github.com/stocks29/plug_redirect_https) - 插件将http请求重定向到反向代理后面的https请求.
* [plug_require_header](https://github.com/DevL/plug_require_header) - 需要并提取HTTP标头并处理丢失的标头.
* [plug_response_header](https://github.com/c-rack/plug_response_header) - 轻松操纵HTTP响应头.
* [plug_ribbon](https://github.com/stnly/plug_ribbon) - 在开发环境中向Web应用程序注入功能区.
* [plug_secex](https://github.com/techgaun/plug_secex) - 插件添加各种HTTP标头，使Phoenix / Elixir应用程序更安全.
* [plug_session_memcached](https://github.com/gutschilla/plug-session-memcached) -  Elixir插件的一个非常简单的memcached会话存储.
* [plug_sigaws](https://github.com/handnot2/plug_sigaws) -  Phoenix / Plug Routes的AWS Signature V4身份验证保护（[Docs](https://hexdocs.pm/plug_sigaws/PlugSigaws.html)).
* [plug_statsd](https://github.com/jeffweiss/plug_statsd) - 用于自动向statsd发送计时和计数指标的插件.
* [plugs](https://github.com/sugar-framework/plugs) - 用于Web应用程序的Plug中间件的集合.
* [plugsnag](https://github.com/jarednorman/plugsnag) -  Elixir插头的Bugsnag通知器.
* [raygun](https://github.com/cobenian/raygun) - 捕获错误并将它们发送给Raygun.
* [react_phoenix](https://github.com/geolessel/react-phoenix) - 在Phoenix视图中渲染React.js组件，重点关注简易安装和Brunch兼容性.
* [resin](https://github.com/Frost/resin) -  Resin是一个插件，它将为每个通过它的请求添加可配置的延迟，除非在生产中运行.
* [revision_plate_ex](https://github.com/KazuCocoa/revision_plate_ex) - 为端点提供服务的插件应用程序和中间件返回应用程序的REVISION.
* [rummage_ecto](https://github.com/Excipients/rummage_ecto) - 一个可配置的框架，用于搜索，排序和分页Ecto查询.
* [rummage_phoenix](https://github.com/Excipients/rummage_phoenix) - 支持HTML，支持在Phoenix中搜索，排序和分页模型的支持框架.
* [scaffold](https://github.com/gausby/scaffold) - 基于从Git-repo获取的模板创建新项目的混合任务.
* [scrivener](https://github.com/drewolson/scrivener) - 分配您的Ecto查询.
* [scrivener_headers](https://github.com/doomspork/scrivener_headers) - 使用Scrivener和HTTP标头对API响应进行分页的助手.
* [scrivener_html](https://github.com/mgwidmann/scrivener_html) - 为使用Scrivener的页面结构而构建的助手，可以轻松地为各种CSS框架构建HTML输出.
* [sentinel](https://github.com/britton-jb/sentinel) -  Phoenix扩展监护人的认证框架，具有路由和其他基本功能.
* [torch](https://github.com/infinitered/torch)   -  Torch是Phoenix应用程序的快速管理生成器.  它使用生成器而不是DSL来确保代码保持可维护性.
* [trailing_format_plug](https://github.com/mschae/trailing_format_plug) -  Elixir插件，支持使用类似轨道的尾随格式的旧API.
* [turn_the_page](https://hex.pm/packages/turn_the_page) - 适用于Elixir应用程序的快速，简单和轻量级分页系统.
* [webassembly](https://github.com/herenowcoder/webassembly) -  Elixir的Web DSL.
* [weebo](https://github.com/stevenschobert/weebo) -  Elixir的XML-RPC解析器/格式化程序，完全支持数据类型映射.

## Frameworks
* Web开发框架.*

* [exelli](https://github.com/pigmej/exelli) - 一个Elli Elixir包装器，带有一些糖语法好东西.
* [kitto](https://github.com/kittoframework/kitto) - 交互式仪表板的框架.
* [phoenix](https://github.com/phoenixframework/phoenix) -  Elixir Web Framework针对具有实时功能的全功能，容错应用程序.
* [placid](https://github.com/slogsdon/placid) - 一个REST工具包，用于使用Elixir构建高度可伸缩和容错的HTTP API.
* [rackla](https://github.com/AntonFagerberg/rackla) -  Elixir的API网关.
* [relax](https://github.com/AgilionApps/relax) - 简单的Elixir实现 [jsonapi.org](http://jsonapi.org) 服务器.
* [rest](https://github.com/synrc/rest) - 带有类型JSON的Micro-REST框架.
* [sugar](https://github.com/sugar-framework/sugar) -  Elixir的模块化Web框架.
* [trot](https://github.com/hexedpackets/trot) -  Elixir网络微框架.

## Games
*游戏的图书馆和实施.*

* [entice](https://github.com/entice/entice) - 分布式实体 - 组件 - 系统框架，提供其自己的示例MMORPG服务器.
* [mines](https://github.com/kevlar1818/mines) - 终端中的扫雷克隆.

## Geolocation
*地理编码地址和处理纬度和经度的图书馆.*

* [distance_api_matrix](https://github.com/C404/distance-matrix-api) - 通过Google距离矩阵api提供距离和航向计算.
* [geo](https://github.com/bryanjos/geo) -  Elixir的GIS功能集合.
* [geocalc](https://github.com/yltsrc/geocalc) - 计算纬度/经度点之间的距离，方位和更多.
* [geocoder](https://github.com/knrz/geocoder) - 一个简单，高效的地理编码器/反向地理编码器，内置缓存.
* [geohash](https://github.com/polmuz/elixir-geohash) -  Geohash编码/解码库.
* [geohax](https://github.com/evuez/geohax) - 使用邻居查找器进行Geohash编码和解码.
* [geoip](https://github.com/navinpeiris/geoip) - 查找给定IP，主机名或“Plug.Conn”的地理定位.
* [geolix](https://github.com/mneudert/geolix) -  MaxMind GeoIP2数据库读取器/解码器.
* [geonames](https://github.com/pareeohnos/geonames-elixir) - 围绕GeoNames API的简单Elixir包装器.
* [ip2location](https://github.com/nazipov/ip2location-elixir) - 用于IP2Location数据库的Elixir库.
* [ipgeobase](https://github.com/sergey-chechaev/elixir_ipgeobase) - 按地址查找俄罗斯和乌克兰城市，查找其他国家/地区的国家/地区.
* [proj](https://github.com/CandyGumdrop/proj) - 使用OSGeo PROJ.4的Elixir坐标转换库.
* [segseg](https://github.com/pkinney/segseg_ex) - 段 - 段交叉分类器和计算器.
* [topo](https://github.com/pkinney/topo) -  Elixir的几何库，用于计算两个几何之间的空间关系.

## GUI
*用于编写图形用户界面的库.*

* [scenic](https://github.com/boydm/scenic) - 便携式2D UI框架.

## Hardware
*硬件相关的东西，如I / O接口等.*

* [elixir_ale](https://github.com/fhunleth/elixir_ale) -  Elixir访问硬件I / O接口，如GPIO，I2C和SPI.
* [nerves](https://github.com/nerves-project/nerves) - 为Raspberry Pi和BeagleBone Black等平台构建固件的框架.

## HTML
*使用HTML的库和实现（对于xml工具，请转到 [XML](#xml) 部分）.*

* [exquery](https://github.com/rozap/exquery) - 用于解析HTML和查询其中元素的库.
* [floki](https://github.com/philss/floki) - 一个简单的HTML解析器，支持使用CSS作为选择器进行搜索.
* [html_sanitize_ex](https://github.com/rrrene/html_sanitize_ex) -  Elixir的HTML清洁剂.
* [modest_ex](https://github.com/f34nk/modest_ex) - 使用CSS选择器对html字符串进行可管道转换的库，例如find（），prepend（），append（），replace（）等.
* [myhtmlex](https://github.com/Overbryd/myhtmlex) -  lexborisov的myhtml的Elixir / Erlang绑定.
* [readability](https://github.com/keepcosmos/readability) - 可读性用于提取和策划文章.
* [texas](https://gitlab.com/dgmcguire/texas) - 使用服务器端呈现和服务器端Virtual DOM差异/修补来更新客户端时，Texas是一个强大的抽象概念.
* [tidy_ex](https://github.com/f34nk/tidy_ex) -  Elixir绑定到HTML工具的祖父 [http://www.html-tidy.org](http://www.html-tidy.org).

## HTTP
*用于处理HTTP和抓取网站的库.*

* [Ace](https://github.com/CrowdHailer/Ace) -  HTTP Web服务器和客户端，支持http1和http2.
* [bolt](https://github.com/SebastianSzturo/bolt) - 简单快速的http代理.
* [cauldron](https://github.com/meh/cauldron) - 作为库的HTTP / SPDY服务器.
* [Crawler](https://github.com/fredwu/crawler) -  Elixir中的高性能网络爬虫.
* [elli](https://github.com/knutin/elli) - Elli is a webserver you can run inside your Erlang application to expose an HTTP API.
* [etag_plug](https://github.com/Zeeker/etag_plug) - 简单易用的浅ETag插头.
* [explode](https://github.com/pkinney/explode) - 一个简单的实用程序，用于响应基于插件和Phoenix的应用程序中的标准HTTP / JSON错误有效负载.
* [exvcr](https://github.com/parroty/exvcr) - 受VCR启发的Elixir HTTP请求/响应记录库.
* [fuzzyurl](https://github.com/gamache/fuzzyurl.ex)   - 用于解析，构造和通配符匹配URL的Elixir库.  也适用于 [Ruby](https://github.com/gamache/fuzzyurl.rb) 和 [JavaScript](https://github.com/gamache/fuzzyurl.js).
* [gun](https://github.com/ninenines/gun) - 用于Erlang / OTP的HTTP / 1.1，HTTP / 2和Websocket客户端.
* [hackney](https://github.com/benoitc/hackney) - 用Erlang编写的简单HTTP客户端.
* [http](https://github.com/slogsdon/http) -  Elixir的HTTP服务器.
* [http_digex](https://github.com/techgaun/http_digex) - 用于创建基本摘要HTTP身份验证标头的模块.
* [http_proxy](https://github.com/KazuCocoa/http_proxy) - 多端口HTTP代理.
* [httpoison](https://github.com/edgurgel/httpoison) - 然而另一个Elixir的HTTP客户端由hackney提供支持.
* [httpotion](https://github.com/myfreeweb/httpotion) - 基于ibrowse的Elixir的花式HTTP客户端.
* [ivar](https://github.com/swelham/ivar) - 围绕HTTPoison的轻量级包装器，提供了一种流畅且可组合的方式来构建http请求.
* [lhttpc](https://github.com/talko/lhttpc) - 在Erlang中实现的轻量级HTTP / 1.1客户端.
* [mnemonic_slugs](https://github.com/devshane/mnemonic_slugs) -  Elixir中一个令人难忘的记忆棒生成器.
* [mochiweb](https://github.com/mochi/mochiweb) -  MochiWeb是一个用于构建轻量级HTTP服务器的Erlang库.
* [neuron](https://github.com/uesteibar/neuron) -  Elixir的GraphQL客户端.
* [plug_wait1](https://github.com/wait1/plug_wait1) - 用于wait1协议的插头适配器.
* [raxx](https://github.com/CrowdHailer/raxx) -  HTTP Web服务器，框架和客户端的接口.
* [river](https://github.com/peburrows/river) - 轻量级且闪电般快速的HTTP / 2客户端.
* [scrape](https://github.com/Anonyfox/elixir-scrape) - 轻松刮取任何网站，文章或RSS / Atom Feed.
* [sparql_client](https://github.com/marcelotto/sparql_client) - 一个 [SPARQL protocol](https://www.w3.org/TR/sparql11-protocol/) Elixir的客户.
* [spell](https://github.com/MyMedsAndMe/spell) - 法术是一个 [Web Application Messaging Protocol](http://wamp-proto.org/) （WAMP）Elixir中的客户端实现.
* [tesla](https://github.com/teamon/tesla) -  HTTP客户端库，支持中间件和多个适配器.
* [Tube](https://github.com/narrowtux/Tube) - 纯Elixir WebSocket客户端库.
* [uri_query](https://github.com/shhavel/uri_query) -  URI编码Elixir中的嵌套GET参数和数组值.
* [uri_template](https://github.com/pezra/ex-uri-template) -  Elixir的RFC6570兼容URI模板处理器.
* [web_socket](https://github.com/slogsdon/plug-web-socket) - 探索插件应用程序的独立库，以便轻松采用WebSockets.
* [webdriver](https://github.com/stuart/elixir-webdriver)   - 这是WebDriver协议客户端的实现.  它目前支持PhantomJS，FireFox，ChromeDriver和远程webdriver服务器（例如Selenium）.
* [yuri](https://github.com/kemonomachi/yuri) - 用于表示URI的简单结构.

## Images
*用于处理和操作图像的库.*
* [alchemic_avatar](https://github.com/zhangsoledad/alchemic_avatar) - 用于从字符串生成字母头像的Elixir库.
* [artifact](https://github.com/doomspork/artifact) -  Elixir的文件上传和动态处理.
* [bump](https://github.com/evanfarrar/ex_bump) - 纯Elixir中的BMP文件编写器.
* [chunky_svg](https://github.com/mmmries/chunky_svg) - 使用SVG绘制内容的库.
* [cloudex](https://github.com/smeevil/cloudex) -  Cloudex是一个Elixir库，可以将图像文件或URL上传到Cloudinary.
* [eikon](https://github.com/tchoutri/Eikon) -  Elixir库，为图像文件提供只读接口.
* [elixir_exif](https://github.com/sschneider1207/ElixirExif) - 从jpeg文件中解析exif标签和缩略图数据.
* [ex_image_info](https://github.com/rNoz/ex_image_info) -  Elixir库，用于解析图像（二进制文件）并获取一组图像格式的维度，检测到的mime类型和整体有效性.
* [exexif](https://github.com/pragdave/exexif) - 纯Elixir库从jpeg文件中提取TIFF和EFIX元数据.
* [exfavicon](https://github.com/ikeikeikeike/exfavicon) - 用于发现favicons的Elixir库.
* [identicon](https://github.com/rbishop/identicon) - 用于生成5x5识别符的Elixir库.
* [image64](https://hex.pm/packages/image64) - 用于处理base64编码图像的工具.
* [imagineer](https://github.com/SenecaSystems/imagineer) -  Elixir中的图像解析.
* [imgex](https://github.com/ianwalter/imgex) - 用于在Elixir中生成imgix URL的非官方客户端库.
* [mogrify](https://github.com/route/mogrify) -  ImageMagick命令行的Elixir包装器.
* [png](https://github.com/yuce/png)   - 用于创建PNG图像的纯Erlang库.  它目前可以创建8位和16位RGB，RGB，带alpha，索引，灰度和带alpha图像的灰度.
* [thumbnex](https://github.com/talklittle/thumbnex) - 从图像和视频屏幕截图中创建缩略图.

## Instrumenting / Monitoring
*用于收集和导出指标的库.*

* [appsignal-elixir](https://github.com/appsignal/appsignal-elixir/) - 从Elixir应用程序收集错误和性能数据并将其发送到 [AppSignal](https://appsignal.com/).
* [elixometer](https://github.com/pinterest/elixometer) - 外部仪表周围的轻型Elixir包装纸.
* [erlang-metrics](https://github.com/benoitc/erlang-metrics) -  Erlang中不同指标系统的通用接口.
* [exometer](https://github.com/Feuerlabs/exometer) -  Erlang中的基本测量对象和探测行为.
* [folsom_ddb](https://github.com/dalmatinerdb/folsom_ddb) -  DalmatinerDB后端存储folsom指标.
* [graphitex](https://github.com/msoedov/graphitex) -  Elixir的Graphite / Carbon客户端.
* [instream](https://github.com/mneudert/instream) -  Elixir的InfluxDB驱动程序.
* [instrumental](https://github.com/undeadlabs/instrumental-ex) -  Elixir客户 [Instrumental](https://instrumentalapp.com/).
* [newrelic.ex](https://github.com/romul/newrelic.ex) - 从Elixir / Phoenix应用程序收集指标并将其发送给 [NewRelic](https://newrelic.com/).
* [prometheus](https://github.com/deadtrickster/prometheus.erl) - [Prometheus.io](https://prometheus.io) Erlang中的监控系统和时间序列数据库客户端.
* [prometheus-ecto](https://github.com/deadtrickster/prometheus-ecto) - 外生仪器prometheus.ex.
* [prometheus-phoenix](https://github.com/deadtrickster/prometheus-phoenix) - Phoenix instrumenter for prometheus.ex.
* [prometheus-plugs](https://github.com/deadtrickster/prometheus-plugs) - 为prometheus.ex插入仪器/出口.
* [prometheus.ex](https://github.com/deadtrickster/prometheus.ex) -  Elixir友好 [Prometheus.io](https://prometheus.io) 监控系统和时间序列数据库客户端.
* [prometheus_process_collector](https://github.com/deadtrickster/prometheus_process_collector) -  Prometheus收集器，它导出当前状态的进程指标，包括cpu，内存，文件描述符用法和本机线程数以及进程启动和运行时间.
* [spandex](https://github.com/spandex-project/spandex) - 最初为Datadog APM开发的平台无关追踪库.
* [telemetry](https://github.com/beam-telemetry/telemetry) - 用于指标和工具的动态调度库.

## JSON
*使用JSON的库和实现.*

* [exjson](https://github.com/guedes/exjson) -  Elixir中的JSON解析器和生成器.
* [ja_serializer](https://github.com/AgilionApps/ja_serializer) -  Elixir中的JSONAPI.org序列化.
* [jason](https://github.com/michalmuskala/jason) - 纯Elixir中的超快速JSON解析器和生成器.
* [jazz](https://github.com/meh/jazz) - 另一个在Elixir中处理JSON的库.
* [joken](https://github.com/bryanjos/joken) - 对JSON Web令牌进行编码和解码.
* [jose](https://github.com/potatosalad/erlang-jose) -  Erlang和Elixir的JSON对象签名和加密（JOSE）.
* [json](https://github.com/cblage/elixir-json) -  Elixir的原生JSON库.
* [json_pointer](https://github.com/xavier/json_pointer) -  RFC 6901的实现，它定义了用于标识JSON文档中特定值的字符串语法.
* [json_stream_encoder](https://github.com/TreyE/json_stream_encoder) -  JsonStreamEncoder是一个流编码器，用于将JSON流式传输到Elixir中的IOish.
* [json_web_token_ex](https://github.com/garyf/json_web_token_ex) -  JSON Web令牌（JWT）标准跟踪（RFC 7519）的Elixir实现.
* [jsonapi](https://github.com/jeregrine/jsonapi) - 将数据模型呈现为的项目 [JSONAPI Documents](http://jsonapi.org/format/).
* [jsx](https://github.com/talentdeficit/jsx) - 用于消费，生成和操纵json的Erlang应用程序.
* [jsxn](https://github.com/talentdeficit/jsxn) -  jsx但有地图.
* [jwalk](https://github.com/jr0senblum/jwalk) - 用于处理JSON的Erlang表示的Helper模块.
* [jwtex](https://github.com/mschae/jwtex) - 用于编码和解码的库 [JWT tokens](http://jwt.io/).
* [poison](https://github.com/devinus/poison) -  Poison是Elixir的一个新的JSON库，专注于邪恶的速度，而不会牺牲简单性，完整性或正确性.
* [tiny](https://github.com/whitfin/tiny) -  Elixir的小巧，快速且完全兼容的JSON解析器.
* [world_json](https://github.com/camshaft/world_json_ex) -  elixir / erlang的topojson国家和州/省收藏.

## Languages
*建立在Elixir之上的语言.*

* [Elchemy](https://github.com/wende/elchemy) - 编译器允许将Elm编程语言代码转换为Elixir.
* [lighthouse_scheme](https://github.com/jwhiteman/lighthouse-scheme) - 一种类似Lisp的小语言和交互式REPL，内置于Elixir.
* [Monkey](https://github.com/fabrik42/writing_an_interpreter_in_elixir) -  Elixir为类似js的Monkey编程语言实现解释器和REPL.

## Lexical analysis
*所有关于词法分析器，词法分析器，扫描仪，标记器或编译器.*

* [ex_abnf](https://github.com/marcelog/ex_abnf) -  Elixir中ABNF文法的解析器.
* [lex_luthor](https://github.com/jamesotron/lex_luthor) -  LexLuthor是Elixir中的Lexer，它使用宏来生成可重复使用的词法分析器.

## Logging
*记录信息和消息.*

* [bunyan](https://github.com/bunyan-logger/bunyan) -  Bunyan：Elixir Logger.
* [exlager](https://github.com/khia/exlager) -  Elixir绑定库存.
* [exsentry](https://github.com/appcues/exsentry) - 记录错误 [Sentry](https://getsentry.com/).
* [gelf_logger](https://github.com/jschniper/gelf_logger) - 将生成Graylog扩展日志格式（GELF）消息的Logger后端.
* [honeybadger](https://github.com/honeybadger-io/honeybadger-elixir) - 记录错误 [Honeybadger](https://www.honeybadger.io/).
* [json_logger](https://github.com/LeeroyDing/json_logger) -  JSON Logger是一个记录器后端，以JSON格式输出elixir日志.
* [lager](https://github.com/basho/lager) -  basho.com的Erlang / OTP日志框架.
* [lager_logger](https://github.com/PSPDFKit-labs/lager_logger) - 一个较大的后端，将所有日志消息转发给Elixir的Logger.
* [logfmt](https://github.com/jclem/logfmt-elixir) -  Logfmt是用于编码和解码logfmt样式日志行的模块.
* [logger_logstash_backend](https://github.com/marcelog/logger_logstash_backend) -  Elixir Logger的后端，它将日志发送到Logstash UDP输入.
* [logglix](https://github.com/pragmaticivan/logglix) - 用于向Loggly发布错误的记录器后端.
* [logster](https://github.com/navinpeiris/logster) - 受Lograge启发，可轻松解析Phoenix和Plug应用程序的单行日志记录.
* [metrix](https://github.com/rwdaigle/metrix) - 将自定义应用程序指标记录到stdout以供Librato和其他下游处理器使用.
* [mstore](https://github.com/dalmatinerdb/mstore) -  MStore是一个在erlang中构建的实验性度量商店，主要功能是open，new，get和put.
* [quiet_logger](https://github.com/Driftrock/quiet_logger/pull/1) - 一个简单的插件来抑制健康检查记录（例如：使用Kubernetes时）.
* [rogger](https://github.com/duartejc/rogger) -  Elixir logger在RabbitMQ中发布日志消息.
* [rollbax](https://github.com/elixir-addicts/rollbax) - 异常跟踪和记录到 [Rollbar](https://rollbar.com/).
* [slack_logger_backend](https://github.com/craigp/slack_logger_backend) - 用于向Slack发布错误的记录器后端.
* [syslog](https://github.com/Vagabond/erlang-syslog) -  Erlang端口驱动程序，用于通过syslog（3）与syslog交互.
* [timber](https://github.com/timberio/timber-elixir)   - 结构化测井平台;  将原始文本日志转换为丰富的结构化事件
* [youtrack_logger_backend](https://github.com/unifysell/youtrack_logger_backend) - 将消息发布到的记录器后端 [YouTrack](https://www.jetbrains.com/youtrack/) （由JetBrains制作的问题跟踪器）.

## Macros
 *宏用于更快，更容易的开发.  为你的代码加糖.*

* [anaphora](https://github.com/sviridov/anaphora-elixir)   -  Anaphora是Elixir的照应宏观收藏品.  回指宏是故意从提供给宏的表单中捕获变量（通常是它）的宏.
* [apix](https://github.com/liveforeverx/apix) - 简单的约定和DSL，用于将elixir函数转换为API，以便以后进行文档和/或验证.
* [backports](https://github.com/leifg/backports) - 使用Elixir 1.1和1.2中的新功能.
* [eventsourced](https://github.com/slashdotdash/eventsourced) - 构建功能性的事件源域模型.
* [expat](https://github.com/vic/expat) -  Elixir库中可重用，可组合的模式.
* [guardsafe](https://github.com/DevL/guardsafe) - 宏扩展为可以安全地用于保护条款的代码.
* [kwfuns](https://github.com/RobertDober/lab42_defkw) - 使用默认值创建具有基于语法的关键字参数的函数的宏.
* [lineo](https://github.com/camshaft/lineo) - 解析变换以获得准确的行号.
* [mdef](https://github.com/pragdave/mdef) - 在Elixir中轻松定义多个功能头.
* [named_args](https://github.com/mgwidmann/named_args) - 允许Elixir中的命名arg样式参数.
* [ok_jose](https://github.com/vic/ok_jose) - 管道elixir函数匹配`{：ok，_}`，`{：error，_}`元组或自定义模式.
* [opus](https://github.com/zorbash/opus) - 可插入业务逻辑组件的框架.
* [pattern_tap](https://github.com/mgwidmann/elixir-pattern_tap) - 用于在使用管道操作符时进行模式匹配的宏.
* [pipe_here](https://github.com/vic/pipe_here) - 轻松将值传递到任何参数位置.
* [pipe_to](https://github.com/taiansu/pipe_to) - 增强型管道操作员，可指定目标位置.
* [pipes](https://github.com/batate/elixir-pipes) - 使用Elixir Pipe操作员实现更灵活组合的宏.
* [pit](https://github.com/vic/pit) - 在管道内流动时转换值.
* [rebind](https://github.com/camshaft/rebind) - 重新绑定Erlang的解析变换.
* [rulex](https://github.com/awetzel/rulex) - 使用Elixir模式匹配的简单规则处理程序.
* [shorter_maps](https://github.com/meyercm/shorter_maps)   -  ~M sigil用于地图速记.  `~M {id name}〜&gt;％{id：id，name：name}`.
* [unsafe](https://github.com/whitfin/unsafe) - 为Elixir函数生成简单的不安全（！）绑定.

## Markdown
*使用Markdown等的图书馆和工具.*

* [cmark](https://github.com/asaaki/cmark.ex) - 用于CommonMark的Elixir NIF（在C中），遵循CommonMark规范的解析器.
* [discount](https://github.com/asaaki/discount.ex) -  Elixir NIF折扣，Markdown解析器.
* [earmark](https://github.com/pragdave/earmark) -  Elixir的Markdown解析器.
* [Markdown](https://github.com/devinus/markdown) - 完全实现为与Hoedown库绑定的NIF.
* [Pandex](https://github.com/filterkaapi/pandex)   - 用于Pandoc的轻质Elixir包装纸.  将Markdown，CommonMark，HTML，Latex，HTML，HTML5，opendocument，rtf，texttile，asciidoc互相转换.

## Miscellaneous
*有用的库或工具不适合上述类别.*

* [address_us](https://github.com/smashedtoatoms/address_us) - 用于将美国地址解析为各个部分的库.
* [Apex](https://github.com/bjro/apex) -  Elixir的精彩打印.
* [AtomVM](https://github.com/bettio/AtomVM) -  AtomVM允许在嵌入式设备（如ESP32和STM32微控制器）上运行Elixir / Erlang代码.
* [bupe](https://github.com/milmazz/bupe) -  EPUB发电机和分析仪.
* [charm](https://github.com/tomgco/elixir-charm) - 使用ANSI终端字符写入颜色和光标位置.
* [codec-beam](https://github.com/hkgumbs/codec-beam) - 从Haskell生成Erlang VM字节代码.
* [Countries](https://github.com/SebastianSzturo/countries) - 各国是ISO 3166标准中每个国家的各种有用信息的集合.
* [countriex](https://github.com/navinpeiris/countriex) - 纯粹的万能药国家数据提供者，包含ISO 3166中每个国家的各种信息.
* [dye](https://github.com/Kabie/dye) - 用于染色终端输出的库.
* [dynamic_compile](https://github.com/okeuday/dynamic_compile) - 从字符串输入编译和加载Erlang模块.
* [ecto_autoslug_field](https://github.com/sobolevn/ecto_autoslug_field) - 自动为您的Ecto模型创建slu ..
* [egaugex](https://github.com/Brightergy/egaugex) - 客户端从egauge设备获取和解析实时数据.
* [elixir-browser](https://github.com/tuvistavie/elixir-browser) -  Elixir的浏览器检测.
* [erlang_term](https://github.com/okeuday/erlang_term) - 提供Erlang术语的内存大小，忽略这些术语的存储位置.
* [ex2ms](https://github.com/ericmj/ex2ms) - 翻译Elixir函数以匹配与`ets`一起使用的规范.
* [ex_phone_number](https://github.com/socialpaymentsbv/ex_phone_number) - 格式化，规范化和验证电话号码.
* [ex_rated](https://github.com/grempe/ex_rated) -  API或任何内容的简单灵活的速率限制.
* [exfcm](https://github.com/Hajto/ExFCM) - 用于发布Firebase云消息的简单包装器.
* [exldap](https://github.com/jmerriweather/exldap) - 用于使用Elixir的LDAP的模块.
* [exlibris](https://github.com/pragdave/exlibris) - 随机库函数的集合.
* [expool](https://github.com/whitfin/expool) -  Elixir中用于并行任务的小型流程池库.
* [exprint](https://github.com/parroty/exprintf) -  Elixir的printf / sprintf库，作为io.format的包装器.
* [exquisite](https://github.com/meh/exquisite) -  Elixir的类似LINQ的match_spec生成.
* [exsync](https://github.com/falood/exsync) - 又一个Elixir重新加载器.
* [funnel](https://github.com/chatgris/funnel) - 基于ElasticSearch的渗透构建的Streix Elixir API.
* [gen_task](https://github.com/Nebo15/gen_task) - 通用任务行为，有助于封装工作程序错误并从经典GenStage中恢复它们.
* [gimei_ex](https://github.com/ma2gedev/gimei_ex) -  gixi图书馆的Elixir港口.
* [growl](https://github.com/zachallett/growl) - 用于增强的简单包装器，OSX的通知系统.
* [hammer](https://github.com/ExHammer/hammer) - 具有可插拔存储后端的速率限制器，包括Redis.
* [html_entities](https://github.com/martinsvalin/html_entities) -  Elixir模块，用于解码字符串中的HTML实体.
* [huex](https://github.com/xavier/huex) - 飞利浦Hue连接灯泡的Elixir客户端.
* [japan_municipality_key](https://github.com/hykw/japan_municipality_key) - 日本市政府密钥转换的Elixir图书馆.
* [keys1value](https://github.com/okeuday/keys1value) -  Erlang为关键列表设置关联映射.
* [licensir](https://github.com/unnawut/licensir) - 混合任务，列出项目中所有已安装软件包的许可证.
* [mixgraph](https://github.com/sivsushruth/mixgraph) -  Hex包的交互式依赖绘图仪.
* [mixstar](https://github.com/ma2gedev/mix-star) -  MixStar主演的GitHub存储库取决于您的项目.
* [netrc](https://github.com/ma2gedev/netrcex) - 读取Elixir中实现的netrc文件.
* [notifier](https://hex.pm/packages/notifier) - 用于桌面通知的可插拔架构.
* [onetime](https://github.com/ryo33/onetime-elixir) -  Elixir的一次性键值存储.
* [pact](https://github.com/BlakeWilliams/pact) - 更好的依赖注入Elixir，以实现更清晰的代码和测试.
* [phone](https://github.com/fcevado/phone) - 从电话号码获取有用信息的解析器.
* [porcelain](https://github.com/alco/porcelain) - 瓷器实现了一种更精确的方法来启动和与Elixir的外部操作系统进程通信.
* [presentex](https://github.com/Cobenian/Presentex) -  Elixir到基于HTML / JavaScript的演示框架.
* [ratekeeper](https://github.com/whitered/ratekeeper) - 速率限制器和速率限制动作调度程序.
* [ratx](https://github.com/liveforeverx/ratx) -  erlang应用的速率限制器和过载保护.
* [reprise](https://github.com/herenowcoder/reprise) -  Elixir的简化模块重新加载器.
* [spawndir](https://github.com/jtmoulia/spawndir) - 从文件系统生成进程.
* [spotify_ex](https://github.com/jsncmgs1/spotify_ex) -  Spotify Web API的Elixir包装器.
* [std_json_io](https://github.com/hassox/std_json_io) - 通过JSON管理和与IO服务器通信的应用程序.
* [url_unroller](https://github.com/semanticart/url_unroller) -  Elixir中的简单URL展开器（非缩短器）.
* [vessel](https://github.com/whitfin/vessel) -  Elixir MapReduce与Hadoop Streaming集成的接口.

## Native Implemented Functions
*使用Erlang NIF的工具和库.*

* [hsnif](https://github.com/urbanserj/hsnif) - 允许在Haskell中编写Erlang NIF库的工具.
* [nifty](https://github.com/rossjones/nifty) - 帮助脚本，用于设置编写NIF时所需的样板文件.
* [Rustler](https://github.com/hansihe/Rustler)   - 用于在Rust中安全地为Erlang或Elixir编写NIF的库.  没有段错误.

## Natural Language Processing (NLP)
*使用人类（自然）语言的工具和库.*

* [gibran](https://github.com/abitdodgy/gibran) -  Gibran是Elixir的港口 [WordsCounted](https://github.com/abitdodgy/words_counted)，一种从文本中提取有用统计数据的自然语言处理器.
* [Paasaa](https://github.com/minibikini/paasaa) -  Elixir的自然语言检测.
* [Petrovich](https://github.com/petrovich/petrovich_elixir) -  Elixir图书馆，以反映俄罗斯的第一，最后和中间名称.
* [Woolly](https://github.com/pjhampton/woolly) -  Woolly是Elixir雄心勃勃的文本挖掘和自然语言处理API.

## Networking
*使用网络相关内容的库和工具.*

* [asn](https://github.com/ephe-meral/asn) - 可用于从IP映射到AS到ASN.
* [chatter](https://github.com/dbeck/chatter_ex) - 基于UDP多播和TCP混合的安全消息广播.
* [download](https://github.com/asiniy/download) - 轻松从互联网上下载文件.
* [eio](https://github.com/falood/eio) -  engine.io的Elixir服务器.
* [ExPcap](https://github.com/cobenian/expcap) - 用Elixir编写的PCAP解析器.
* [FlyingDdns](https://gitlab.com/timopallach/FlyingDdns) - 用elixir编写的dyndns服务器.
* [mac](https://github.com/ephe-meral/mac) - 可用于查找以十六进制字符串（根据IEEE）给出的MAC供应商.
* [pool](https://github.com/slogsdon/pool) -  Elixir的插座接收器池.
* [reagent](https://github.com/meh/reagent) - reagent is a socket acceptor pool for Elixir.
* [sockerl](https://github.com/Pouriya-Jahanbakhsh/sockerl) -  Sockerl是一个用于TCP协议的高级Erlang / Elixir套接字库，它提供了快速，实用且易于使用的API，用于实现服务器，客户端和客户端连接池.
* [socket](https://github.com/meh/elixir-socket) -  Elixir的插座包装.
* [sshex](https://github.com/rubencaro/sshex) -  Elixir的简单SSH助手.
* [sshkit](https://github.com/bitcrowd/sshkit.ex) - 用于在一个或多个服务器上执行任务的Elixir工具包，构建在Erlang的SSH应用程序之上.
* [torex](https://github.com/alexfilatov/torex) - 简单的Tor连接库.
* [tunnerl](https://github.com/surik/tunnerl) -  SOCKS4和SOCKS5代理服务器.
* [wifi](https://github.com/gausby/wifi) - 用于在Elixir中使用本地Wifi网络的各种实用功能.
* [wpa_supplicant](https://github.com/fhunleth/wpa_supplicant.ex) - 与wpa_supplicant的Elixir接口.

## Office
*用于处理办公室文件的图书馆.*

* [excellent](https://github.com/leifg/excellent) -  Elixir的OpenXL（Excel 2000）解析器.
* [xlsxir](https://github.com/kennellroxco/xlsxir)   - 支持ISO 8601日期格式的Xlsx文件解析器.  数据被提取到Erlang术语存储（ETS）表，并通过各种功能进行访问.

## ORM and Datamapping
*实现对象关系映射或数据映射技术的库.*

* [amnesia](https://github.com/meh/amnesia) -  Elixir的Mnesia包装纸.
* [arbor](https://github.com/coryodaniel/arbor) -  Ecto邻接列表和树遍历.
* [arc_ecto](https://github.com/stavro/arc_ecto) -  Arc.Ecto提供与Arc和Ecto的集成.
* [atlas](https://github.com/chrismccord/atlas) -  Elixir的对象关系映射器.
* [barrel_ex](https://github.com/jxub/barrel_ex.git) - [Barrel-db](https://barrel-db.org/) Elixir中分布式面向文档的数据库REST客户端.
* [Bolt.Sips](https://github.com/florinpatrascu/bolt_sips) - 使用Bolt协议的Elixir的Neo4j驱动程序.
* [boltun](https://github.com/bitgamma/boltun) - 将来自Postgres LISTEN / NOTIFY机制的通知转换为回调执行.
* [caylir](https://github.com/mneudert/caylir) -  Elixir的Cayley司机.
* [comeonin_ecto_password](https://github.com/vic/comeonin_ecto_password) - 使用Comeonin存储加密密码的Ecto自定义类型.
* [couchdb_connector](https://github.com/locolupo/couchdb_connector) -  CouchDB的连接器，基于Erlang的JSON文档数据库.
* [craterl](https://github.com/crate/craterl) - 用于箱子的Erlang客户端.
* [database_url](https://github.com/s-m-i-t-a/database_url) - 解析数据库URL并返回关键字列表以与Ecto一起使用.
* [datomex](https://github.com/edubkendo/datomex) -  Datomic REST API的Elixir驱动程序.
* [ddb_client](https://github.com/dalmatinerdb/ddb_client) -  DalmatinerDB客户端.
* [defql](https://github.com/fazibear/defql) - 使用SQL作为正文创建elixir函数.
* [dexts](https://github.com/meh/dexts) -  Disk Elixir Terms Storage，dest wrapper.
* [diver](https://github.com/novabyte/diver) - 使用Jinterface和Asynchbase Java客户端查询数据库的Erlang / Elixir的HBase驱动程序.
* [dproto](https://github.com/dalmatinerdb/dproto) -  DalmatinerDB的协议.
* [dqe](https://github.com/dalmatinerdb/dqe) -  DalmatinerDB查询引擎.
* [ecto](https://github.com/elixir-ecto/ecto) -  Elixir的数据库包装器和语言集成查询.
* [ecto_cassandra](https://github.com/cafebazaar/ecto-cassandra) - 用于Ecto的Cassandra数据库适配器.
* [ecto_enum](https://github.com/gjaldon/ecto_enum) -  Ecto扩展，支持模型中的枚举.
* [ecto_facade](https://github.com/azranel/ecto_facade) -  Ecto外观，允许将写入和读取分离到不同的数据库.
* [ecto_factory](https://hex.pm/packages/ecto_factory) - 根据您的ecto模式轻松生成结构.
* [ecto_fixtures](https://github.com/DockYard/ecto_fixtures) - 使用Ecto的Elixir应用程序的固定装置.
* [ecto_lazy_float](https://github.com/joshdholtz/ecto-lazy-float) -  Ecto.LazyFloat  - 一个接受二进制和整数的Ecto.Float.
* [ecto_migrate](https://github.com/xerions/ecto_migrate)   -  Ecto自动迁移库.  它允许生成和运行迁移以进行初始迁移和更新迁移.
* [ecto_mnesia](https://github.com/Nebo15/ecto_mnesia) - 用于Mnesia Erlang术语数据库的Ecto适配器.
* [ecto_ordered](https://github.com/zovafit/ecto-ordered) - 订购型号的Ecto扩展.
* [ecto_paging](https://github.com/Nebo15/ecto_paging) -  Ecto的基于光标的分页.
* [ecto_rut](https://github.com/sheharyarn/ecto_rut) - 简单而强大的Ecto快捷方式，可简化和加速开发.
* [ecto_shortcuts](https://github.com/MishaConway/ecto_shortcuts) -  ecto中常见操作的快捷方式.
* [ecto_shortuuid](https://github.com/gpedic/ecto_shortuuid) - 增加支持的Ecto类型 [ShortUUIDs](https://github.com/gpedic/ex_shortuuid).
* [ecto_validation_case](https://github.com/danielberkompas/ecto_validation_case)   - 简化您的Ecto模型验证测试.  由shoulda匹配器灵感启发，但更简单.
* [ectophile](https://github.com/gjaldon/ectophile) -  Ecto扩展，可立即支持模型中的文件上传.
* [elastic](https://github.com/radar/elastic) - 一个超薄的单板，可以帮助您与Elastic Search交谈.
* [elastix](https://github.com/werbitzky/elastix) - 用Elixir编写的简单Elastic REST客户端.
* [eredis](https://github.com/wooga/eredis) -  Erlang Redis客户端.
* [erlastic_search](https://github.com/tsloughter/erlastic_search) - 用于与Elastic Search的休息界面通信的Erlang应用程序.
* [esqlite](https://github.com/mmzeeman/esqlite) - 用于sqlite的Erlang NIF.
* [eternal](https://github.com/whitfin/eternal) - 让您的ETS桌子永远，安全，轻松地保持活力.
* [ets_map](https://github.com/antipax/ets_map) -  Elixir包，提供由ETS表支持的类似Map的界面（Map / Access / Enumerable / Collectable）.
* [eventstore](https://github.com/slashdotdash/eventstore) - 使用Postgres进行持久化的CQRS EventStore，用Elixir编写.
* [ex_bitcask](https://github.com/JonGretar/ExBitcask) -  Basho的Bitcask Key / Value商店的Elixir包装.
* [ex_sider](https://github.com/ephe-meral/ex_sider) -  Redis数据结构的Elixir Map / List / Set接口（使用Redix，但可以配置）.
* [exleveldb](https://github.com/skovsgaard/exleveldb) - 针对LevelDB的Basho eleveldb模块的Elixir包装器.
* [exnumerator](https://github.com/KamilLelonek/exnumerator) -  Elixir可枚举类型定义，以简单的方式与任何数据库一起使用.
* [exredis](https://github.com/artemeff/exredis) - 对药剂REDI客户端.
* [exseed](https://github.com/seaneshbaugh/exseed) -  Elixir库，提供简单的DSL，用于通过Ecto播种数据库.
* [exsolr](https://github.com/dcarneiro/exsolr) - 用Elixir编写的Solr包装器.
* [extreme](https://github.com/exponentially/extreme) - 使用Elixir库 [Eventstore](https://geteventstore.com) 对于聚合（CQRS）生成的事件的持久性.
* [exts](https://github.com/meh/exts) -  Elixir条款存储，ets包装.
* [github_ecto](https://github.com/wojtekmach/github_ecto) -  GitHub API的Ecto适配器.
* [gremlex](https://github.com/Revmaker/gremlex) -  Apache Tinkerpop Gremlin Elixir客户端.
* [hstore](https://github.com/senecasystems/hstore) -  Hstore对Postgrex的支持.
* [inquisitor](https://github.com/dockyard/inquisitor) -  Ecto的可组合查询构建器.
* [isn](https://github.com/Frost/isn) -  postgreSQL isn扩展的Ecto类型.
* [kalecto](https://github.com/lau/calecto) -  Kalends和Ecto之间的胶水，用于保存日期，时间和日期时间.
* [kst](https://github.com/synrc/kvs) -  Erlang抽象术语数据库.
* [level](https://github.com/gausby/level) -  Elixir的Level实现了各种帮助函数和数据类型，以便与Googles Level数据存储一起使用.
* [mariaex](https://github.com/xerions/mariaex) -  Elixir的MariaDB / MySQL驱动程序.
* [memento](https://github.com/sheharyarn/memento) -  Elixir中的简单Mnesia界面.
* [moebius](https://github.com/robconery/moebius) -  Elixir和PostgreSQL的功能查询工具.
* [mongo](https://github.com/checkiz/elixir-mongo) -  Elixir的MongoDB驱动程序.
* [mongodb](https://github.com/ericmj/mongodb) -  Elixir的MongoDB驱动程序.
* [mongodb_ecto](https://github.com/michalmuskala/mongodb_ecto) - 用于Ecto的MongoDB适配器.
* [mysql](https://github.com/mysql-otp/mysql-otp) -  MySQL / OTP  -  Erlang / OTP的MySQL驱动程序.
* [mysqlex](https://github.com/tjheeta/mysqlex) - 围绕mysql-otp库的Ecto兼容包装器.
* [neo4j_sips](https://github.com/florinpatrascu/neo4j_sips) -  Elixir的Neo4j驱动程序.
* [neo4j_sips_models](https://github.com/florinpatrascu/neo4j_sips_models) -  Neo4j.Sips Elixir驱动程序的简约模型支持.
* [paper_trail](https://github.com/izelnakri/paper_trail) - 用于跟踪和记录数据库中所有更改的Ecto插件.
* [postgrex](https://github.com/elixir-ecto/postgrex) -  Elixir的PostgreSQL驱动程序.
* [red](https://github.com/rodrigues/red) - 以类似图形的方式在Redis中保持对象之间的关系.
* [rediscl](https://github.com/akdilsiz/elixir-rediscl) - 具有连接池和管道查询构建器的最小redis客户端.
* [redix](https://github.com/whatyouhide/redix) -  Elixir的超快，流水线，弹性Redis驱动程序.
* [redo](https://github.com/heroku/redo) -  Heroku用于erlang的流水线redis客户端.
* [rethinkdb](https://github.com/hamiltop/rethinkdb-elixir) - 使用JSON协议的纯Elixir中的Rethinkdb客户端.
* [riak](https://github.com/drewkerrigan/riak-elixir-client) - 用Elixir编写的Riak客户端.
* [riak_ecto](https://github.com/pma/riak_ecto) - 用于Ecto的Riak适配器.
* [shards](https://github.com/cabol/shards) - 对Erlang / Elixir ETS表的透明和开箱即用的Sharding支持.
* [sql_dust](https://github.com/bettyblocks/sql_dust) - 使用神奇的Elixir SQL尘埃生成（复杂）SQL查询.
* [sqlite_ecto](https://github.com/jazzyb/sqlite_ecto) - 用于Ecto的SQLite3适配器.
* [sqlitex](https://github.com/mmmries/sqlitex)   - 围绕esqlite的Elixir包装器.  允许访问sqlite3数据库.
* [ssdb_elixir](https://github.com/lidashuang/ssdb-elixir) -  Elixir的ssdb客户端，专注于性能.
* [tds](https://github.com/livehelpnow/tds) -  Elixir的MSSQL / TDS数据库驱动程序.
* [tds_ecto](https://github.com/livehelpnow/tds_ecto) - 用于Ecto的MSSQL / TDS适配器.
* [timex_ecto](https://github.com/bitwalker/timex_ecto) - 使用Exo的Timex DateTimes的适配器.
* [tirexs](https://github.com/Zatvobor/tirexs) -  Elixir风格的DSL，用于构建基于JSON的Elasticsearch引擎请求.
* [triplex](https://github.com/ateliware/triplex) - 针对Elixir应用程序的postgres架构的数据库多租户！
* [triton](https://github.com/blitzstudios/triton) - 纯粹的Elixir Cassandra ORM建立在Xandra之上.
* [udpflux](https://github.com/timbuchwaldt/udpflux) - 一个自以为是的InfluxDB UDP唯一客户端.
* [xandra](https://github.com/lexhide/xandra) -  Cassandra驱动程序本身在Elixir中构建，专注于速度，简单性和稳健性.
* [yar](https://github.com/dantswain/yar) -  Elix的另一个Redis客户.

## OTP
*与OTP相关的工作的图书馆.*

* [core](https://github.com/fishcakez/core) - 用于选择性接收OTP进程的库.
* [erlexec](https://github.com/saleyn/erlexec) - 从Erlang / OTP执行和控制OS进程.
* [immortal](https://github.com/danielberkompas/immortal) -  Immortal是一小组辅助模块，旨在使构建容错OTP应用程序变得更加容易.
* [libex_config](https://github.com/reset/libex-config) - 用于访问OTP应用程序配置的助手.

## Package Management
*用于包和依赖管理的库和工具.*

* [Hex](https://hex.pm/) -  Erlang生态系统的包管理器.
* [rebar3_hex](https://github.com/hexpm/rebar3_hex) -  rebar3的Hex.pm插件.

## PDF
*用于处理PDF文件的库和软件.*

* [gutenex](https://github.com/SenecaSystems/gutenex) -  Elixir的原生PDF生成.
* [pdf2htmlex](https://github.com/ricn/pdf2htmlex) - 将PDF文档转换为漂亮的HTML文件，而不会丢失文本或格式.
* [pdf_generator](https://github.com/gutschilla/elixir-pdf-generator) - 用于Elixir项目的wkhtmltopdf（HTML到PDF）的简单包装器.

## Protocols
*特殊协议和格式库.*

* [elixir_radius](https://github.com/bearice/elixir-radius) -  Elixir上的RADIUS协议.
* [ex_hl7](https://github.com/jcomellas/ex_hl7) - 健康等级7（HL7）是一种用于以电子方式建模和传输健康相关数据的协议.
* [ex_marshal](https://github.com/gaynetdinov/ex_marshal) - 在Elixir中实现的Ruby Marshal格式.
* [exprotobuf](https://github.com/bitwalker/exprotobuf) -  Elixir中的协议缓冲区变得简单.
* [grpc-elixir](https://github.com/tony612/grpc-elixir) -  Elixir实施gRPC.
* [message_pack](https://github.com/mururu/msgpack-elixir) -  Elixir的MessagePack实现.
* [msgpax](https://github.com/lexmag/msgpax) -  Elixir的MessagePack（de）序列化器实现.
* [protox](https://github.com/ahamez/protox) - 协议缓冲区的Elixir实现.
* [riffed](https://github.com/pinterest/riffed) - 为Apache Thrift提供惯用的Elixir绑定.
* [Sippet](https://github.com/balena/elixir-sippet) - 设计用作SIP协议中间件的Elixir库.
* [SMPPEX](https://github.com/savonarola/smppex) -  Elixir中的SMPP 3.4协议和框架实现.

## Queue
*用于处理事件和任务队列的库.*

* [adap](https://github.com/awetzel/adap) - 在您的信息系统中创建数据流，以根据Elixir匹配规则查询，扩充和转换数据.
* [amqp](https://github.com/pma/amqp) - 基于Langohr的Erlang RabbitMQ客户端的简单Elixir包装器.
* [conduit](https://github.com/conduitframework/conduit) - 用于处理消息队列的框架，具有用于SQS和AMQP的适配器，以及用于可重用消息传递模式的插件.
* [cspex](https://github.com/costaraphael/cspex) - 简单，符合OTP标准，Elixir实现CSP通道.
* [dbus](https://github.com/aforward/sadbus) - 使用Redis解耦的微服务之间共享数据的哑巴消息总线.
* [ecto_job](https://github.com/mbuhot/ecto_job) - 使用Ecto，PostgreSQL和GenStage构建的事务作业队列.
* [elixir_nsq](https://github.com/wistia/elixir_nsq) -  Elix的NSQ客户库.
* [elixir_talk](https://github.com/jsvisa/elixir_talk) -  Beanstalkd的Elixir客户端.
* [enm](https://github.com/basho/enm) -  enm是一个包装nanomsg C库的Erlang端口驱动程序.
* [exdisque](https://github.com/mosic/exdisque) -  Elixir客户端 [Disque](https://github.com/antirez/disque)，内存中的分布式作业队列.
* [exq](https://github.com/akira/exq) -  Elixir的工作处理库 - 与Resque / Sidekiq兼容.
* [exrabbit](https://github.com/d0rc/exrabbit) -  RabbitMQ绑定和Elixir的DSL.
* [gen_rmq](https://github.com/meltwater/gen_rmq) - 用于创建RabbitMQ消费者和发布者的一系列行为.
* [heapq](https://github.com/takscape/elixir-heapq) -  Elixir中基于堆的优先级队列实现.
* [honeydew](https://github.com/koudelka/honeydew) -  Honeydew是Elixir的工作池库.
* [hulaaki](https://github.com/suvash/hulaaki) - 用Elixir编写的MQTT 3.1.1客户端库.
* [kafka_consumer](https://github.com/anoskov/kafka-consumer) - 使用kafka_ex的Kafka消费者.
* [kafka_ex](https://github.com/kafkaex/kafka_ex) -  Elixir的Kafka客户端库.
* [mqs](https://github.com/synrc/mqs) -  RabbitMQ客户端库，路由密钥，RPC over MQ和其他东西.
* [opq](https://github.com/fredwu/opq) - 一个简单的内存中队列，在Elixir中具有工作池和速率限制.
* [pqueue](https://github.com/okeuday/pqueue) -  Erlang优先级队列实现.
* [que](https://github.com/sheharyarn/que) - 使用Mnesia进行简单的后台作业处理.
* [queuex](https://github.com/falood/queuex) - 具有多个后端的优先级队列.
* [RBMQ](https://github.com/Nebo15/rbmq) - 用于生成RabbitMQ生产者和消费者的简单API.
* [Rihanna](https://github.com/samphilipd/rihanna) -  Elixir的高性能postgres支持的工作队列.
* [stream_weaver](https://hex.pm/packages/stream_weaver) - 用于处理流的库.
* [task_bunny](https://github.com/shinyscorpion/task_bunny) - 用Elixir编写的后台处理应用程序，并使用RabbitMQ作为消息传递后端.
* [toniq](https://github.com/joakimk/toniq) -  Elixir简单可靠的后台作业库.
* [verk](https://github.com/edgurgel/verk)   -  Verk是一个由Redis支持的工作处理系统.  它使用Sidekiq / Resque的相同作业定义.
* [work_queue](https://github.com/pragdave/work_queue) - 简单实施Elixir中的饥饿消费者模型.


## Release Management
*用于发布管理的库和工具.*

* [changex](https://github.com/Gazler/changex) - 从GIT日志生成自动更改日志.
* [distillery](https://github.com/bitwalker/distillery) - 针对Erlang VM的纯Elixir实现的发布打包功能.
* [eliver](https://github.com/glasnoster/eliver) -  Elixir软件包的交互式语义版本控制.
* [exrm](https://github.com/bitwalker/exrm) - 自动为您的Elixir项目生成一个版本.
* [exrm_deb](https://github.com/johnhamelink/exrm_deb) - 轻松为您的Elixir版本创建一个deb.
* [exrm_heroku](https://github.com/epsanchezma/exrm-heroku) - 轻松将您的Elixir版本发布到Heroku.
* [exrm_rpm](https://github.com/smpallen99/exrm-rpm) - 轻松为您的Elixir版本创建RPM.
* [mix_docker](https://github.com/Recruitee/mix_docker) - 将您的Elixir应用程序生产版本放入最小的docker镜像中.
* [relex](https://github.com/yrashk/relex) -  Erlang / Elixir Release Assembler.
* [renew](https://github.com/Nebo15/renew) - 混合任务以创建构建到Docker容器中的混合项目.

## REST and API
*用于开发REST-ful API的库和Web工具.*

* [accent](https://github.com/sticksnleaves/accent) - 用于处理JSON API密钥到不同情况的转换的插件.
* [detergent](https://github.com/devinus/detergent) - 乳化Erlang SOAP库.
* [detergentex](https://github.com/r-icarus/detergentex) -  Elixir绑定到用于调用WSDL / SOAP服务的Detergent erlang库.
* [maru](https://github.com/falood/maru) - 用于创建类似REST的API的Elixir葡萄副本.
* [mazurka](https://github.com/exstruct/mazurka) -  hypermedia api工具包.
* [plug_rest](https://github.com/christopheradams/plug_rest) - 用于超媒体Web应用程序的REST行为和插件路由器.
* [signaturex](https://github.com/edgurgel/signaturex) -  API的简单密钥/秘密身份验证.
* [urna](https://github.com/meh/urna) -  Urna是一个简单的DSL围绕大锅来实现REST服务.
* [versionary](https://github.com/sticksnleaves/versionary) -  Elixir Plug和Phoenix的API版本控制.

## Search
*与搜索索引，搜索算法和搜索客户端相关的库.*

* [elasticsearch](https://github.com/infinitered/elasticsearch-elixir) -  Elixir的一个简单，严谨的Elasticsearch库.
* [giza_sphinxsearch](https://github.com/Tyler-pierce/giza_sphinxsearch) - 与Manticore兼容的Sphinx Search客户端.

## Security
*有关安全的图书馆和工具.*

* [pwned](https://github.com/thiamsantos/pwned) - 检查您的密码是否已被确认.
* [safetybox](https://github.com/aforward/safetybox) -  Elixir的面向安全的辅助函数.
* [sobelow](https://github.com/nccgroup/sobelow) -  Phoenix Framework的以安全为中心的静态分析.
* [ssl_verify_fun](https://github.com/deadtrickster/ssl_verify_fun.erl) - 收集Erlang的ssl验证函数.

## SMS
* SMS相关的库和工具.*

* [exsms](https://hex.pm/packages/exsms) - 用于发送交易短信的Elixir库 -  supoprts Sendinblue，mailjet，msg91和textlocal.

## Static Page Generation
*用于生成静态网站和内容的工具和库.*

* [blogit](https://github.com/meddle0x53/blogit) - 用于从包含markdown文件的git存储库生成博客的OTP应用程序.
* [coil](https://github.com/badosu/coil) - Minimalistic static content engine.
* [glayu](https://github.com/pablomartinezalvarez/glayu) - 适用于中型站点的静态站点生成器.
* [obelisk](https://github.com/BennyHallett/obelisk) - 静态博客和网站生成器.
* [serum](https://github.com/Dalgona/Serum) - 一个用Elixir编写的简单静态网站生成器.

## Statistics
*围绕主题统计的图书馆.*

* [descriptive_statistics](https://github.com/pusewicz/descriptive_statistics) -  Elixir的描述性统计.
* [mtx](https://github.com/synrc/mtx) -  MTX支持前端API，用于跟踪直方图，仪表，计数器，仪表，计时键.
* [numerix](https://github.com/safwank/Numerix) - 一系列有用的数学函数，倾向于统计，线性代数和机器学习.
* [simple_stat_ex](https://github.com/Tyler-pierce/simplestatex) -  Ecto兼容库，可按时间段进行简单的统计.
* [statistics](https://github.com/msharp/elixir-statistics) -  Elixir的一些基本统计功能.

## Templating
*库解析和帮助模板*

* [bbmustache](https://github.com/soranoba/bbmustache) - 二进制模式匹配基于Erlang / OTP的Mustache模板引擎.
* [calliope](https://github.com/nurugger07/calliope) -  Elixir HAML解析器.
* [eml](https://github.com/zambal/eml) - 用于在Elixir中编写和操作（HTML）标记的库.
* [exgen](https://github.com/rwdaigle/exgen) - 用于快速生成Elixir项目的模板库.
* [expug](https://github.com/rstacruz/expug) -  Elixir的哈巴狗模板.
* [mustache](https://github.com/schultyy/Mustache.ex) -  Elixir的胡须模板.
* [mustachex](https://github.com/jui/mustachex) -  Elixir的Mustache  - 无逻辑模板.
* [slime](https://github.com/slime-lang/slime) - 用于渲染类似于模板的模板的Elixir库.
* [taggart](https://github.com/ijcd/taggart) - 作为Elixir中的代码的HTML.
* [templates](https://github.com/sugar-framework/templates) - 用于向Web应用程序添加模板的帮助程序库.

## Testing
*用于测试代码库和生成测试数据的库.*

* [amrita](https://github.com/josephwilk/amrita) -  Elixir的礼貌，有礼貌，完全正直的测试框架.
* [apocryphal](https://github.com/coryodaniel/apocryphal) - 针对ExUnit的基于Swagger的文档驱动开发.
* [blacksmith](https://github.com/batate/blacksmith) -  Elixir的数据生成框架.
* [blitzy](https://github.com/benjamintanweihao/blitzy) -  Elixir中的一个简单的HTTP负载测试器.
* [bypass](https://github.com/pspdfkit-labs/bypass) -  Bypass提供了一种使用自定义插件创建模拟HTTP服务器的快速方法.
* [chaperon](https://github.com/polleverywhere/chaperon) - 用Elixir编写的HTTP服务性能和负载测试框架.
* [chemistry](https://github.com/genericlady/chemistry) -  Elixir的测试框架.
* [cobertura_cover](https://github.com/PSPDFKit-labs/cobertura_cover) - 从与Jenkins的Cobertura插件兼容的`mix test --cover`文件中写入一个coverage.xml.
* [double](https://github.com/sonerdy/double) - 创建存根依赖关系以进行测试，而不覆盖全局模块.
* [ecto_it](https://github.com/xerions/ecto_it) - 带有默认配置的Ecto插件，用于测试不同的ecto插件和数据库.
* [efrisby](https://github.com/FabioBatSilva/efrisby) - 针对erlang的REST API测试框架.
* [elixir-auto-test](https://github.com/joaothallis/elixir-auto-test) - 使用inotify-tools保存文件时运行测试.
* [espec](https://github.com/antonmi/espec) - 受RSpec启发的Elixir BDD测试框架.
* [espec_phoenix](https://github.com/antonmi/espec_phoenix) - 针对Phoenix Web框架的ESpec.
* [ex_machina](https://github.com/thoughtbot/ex_machina)   -  Elixir灵活的测试工厂.  使用Ecto和Ecto协会开箱即用.
* [ex_parameterized](https://github.com/KazuCocoa/ex_parameterized) - 用于参数化测试的简单宏.
* [ex_spec](https://github.com/drewolson/ex_spec) -  ExUnit的类似BDD的语法.
* [ex_unit_fixtures](https://github.com/obmarg/ex_unit_fixtures) - 用于定义ExUnit测试的模块化依赖关系的库.
* [ex_unit_notifier](https://github.com/navinpeiris/ex_unit_notifier) -  ExUnit的桌面通知.
* [excheck](https://github.com/parroty/excheck) -  Elixir的基于属性的测试库（QuickCheck样式）.
* [exkorpion](https://github.com/wesovilabs/exkorpion) -  Elixir开发人员的BDD库.
* [factory_girl_elixir](https://github.com/sinetris/factory_girl_elixir) - 在Elixir中最小化Ruby的factory_girl的实现.
* [faker](https://github.com/igas/faker) -  Faker是一个纯粹的Elixir库，用于生成虚假数据.
* [faker_elixir](https://github.com/GesJeremie/faker-elixir) -  FakerElixir是一个Elixir软件包，可以为您生成虚假数据.
* [fqc](https://github.com/project-fifo/fqc) -  FiFo Quickcheck帮助程序，一组用于运行EQC的帮助程序.
* [gimei](https://github.com/KazuCocoa/elixir-gimei) -  Gimei是一个纯粹的Elixir库，用于生成日本假数据.
* [hound](https://github.com/HashNuke/hound) - 用于编写集成测试和浏览器自动化的Elixir库.
* [hypermock](https://github.com/stevegraham/hypermock) -  HTTP请求存根和期望Elixir库.
* [ignorant](https://github.com/campezzi/ignorant) - 部分“地图”比较，确保字段存在而忽略其值.
* [katt](https://github.com/for-GET/katt) -  KATT（Klarna API Testing Tool）是一个基于HTTP的Erlang API测试工具.
* [kovacs](https://github.com/antp/kovacs) - 一个简单的ExUnit测试运行器.
* [meck](https://github.com/eproxus/meck) -  Erlang的模拟库.
* [mecks_unit](https://github.com/archan937/mecks_unit) - 一个优雅地模拟（异步）ExUnit测试中的模块函数的包 [meck](https://github.com/eproxus/meck).
* [mix_erlang_tasks](https://github.com/alco/mix-erlang-tasks) - 使用Mix的Erlang项目的常见任务.
* [mix_eunit](https://github.com/dantswain/mix_eunit) - 执行eunit测试的Mix任务.
* [mix_test_watch](https://github.com/lpil/mix-test.watch) - 每次保存文件时自动运行Elixir项目的测试.
* [mixunit](https://github.com/talentdeficit/mixunit) - 基于混合项目的EUnit任务.
* [mock](https://github.com/jjh42/mock) - 模拟Elixir语言的库.
* [mockery](https://github.com/appunite/mockery) - 用于异步测试的简单模拟库.
* [mockingbird](https://github.com/Driftrock/mockingbird) - 一组帮助程序，用于测试涉及http请求的代码.
* [pavlov](https://github.com/sproutapp/pavlov) - 您的Elixir项目的BDD框架.
* [plug_test_helpers](https://github.com/xavier/plug_test_helpers) - 一个简单的插头测试DSL.
* [ponos](https://github.com/klarna/ponos) --Ponos是一个Erlang应用程序，它公开了一个灵活的负载生成器API.
* [power_assert](https://github.com/ma2gedev/power_assert_ex)   -  Elixir中的Power Assert.  显示每个表达式的评估结果
* [proper](https://github.com/manopapad/proper) -  PropEr（基于PROPerty的ERlang测试工具）是一个基于QuickCheck的开源基于属性的Erlang测试工具.
* [setup_tag](https://github.com/vic/setup_tag) - 轻松混合和匹配标记有标签的功能，以设置您的测试环境.
* [shouldi](https://github.com/batate/shouldi) -  Elixir使用嵌套上下文测试库，具有出色的可读性和易用性.
* [test_selector](https://github.com/DefactoSoftware/test_selector) - 一组测试助手，确保您始终在Phoenix应用程序中选择正确的元素.
* [test_that_json](https://github.com/facto/test_that_json) - 针对Elixir测试需求的JSON断言和帮助.
* [tuco_tuco](https://github.com/stuart/tuco_tuco) -  TucoTuco通过运行Web浏览器并模拟用户与应用程序的交互来帮助您测试Web应用程序.
* [wallaby](https://github.com/keathley/wallaby) -  Wallaby通过同时模拟用户交互和管理浏览器来帮助测试您的Web应用程序.
* [white_bread](https://github.com/meadsteve/white-bread) - 使用小黄瓜语法在Elixir中基于故事的BDD.

## Text and Numbers
*用于解析和操作文本和数字的库.*

* [abacus](https://github.com/narrowtux/abacus) - 评估Elixir中的数学术语.
* [base58](https://github.com/jrdnull/base58) -  Elixir的Base58编码/解码.
* [base58check](https://github.com/gjaldon/base58check) - 用于比特币的Base58Check编码/解码.
* [base62](https://github.com/igas/base62) - 纯Elixir中的Base62编码器/解码器.
* [bencode](https://github.com/gausby/bencode)   -  Elixir的Bencode编码器和解码器.  如果在输入中找到信息字典，解码器将返回信息字典的校验和值.
* [bencoder](https://github.com/alehander42/bencoder) -  Elixir中的bencode.
* [brcpfcnpj](https://github.com/williamgueiros/Brcpfcnpj) - 巴西文件的数字格式和验证（CPF / CNPJ）.
* [ccc](https://github.com/Joe-noh/ccc) - 字符代码转换器.
* [chinese_translation](https://github.com/tyrchen/chinese_translation) - 根据维基百科数据翻译繁体中文和简体中文，并将中文单词/字符翻译为拼音（或带或不带音调的slug）.
* [cidr](https://github.com/c-rack/cidr-elixir) -  Elixir的无类别域间路由（CIDR）.
* [cirru_parser](https://github.com/Cirru/parser.ex) -  Elixir的Cirru Parser.
* [colorful](https://github.com/Joe-noh/colorful) - 用于在CUI上装饰字符的Elixir宏.
* [colors](https://github.com/lidashuang/colors) - 用Elixir编写的Colors util.
* [convertat](https://github.com/whatyouhide/convertat) - 用于从任意碱基转换的Elixir库.
* [curtail](https://github.com/seankay/curtail) -  HTML标签安全字符串截断.
* [custom_base](https://github.com/igas/custom_base) - 允许您在Elixir中进行自定义基本转换.
* [decimal](https://github.com/ericmj/decimal) -  Elixir的任意精度十进制算术.
* [dicer](https://github.com/olhado/dicer) - 骰子滚动表达评估器.
* [eden](https://github.com/jfacorro/Eden) - [EDN](https://github.com/edn-format/edn) Elixir的编码器/解码器.
* [elixilorem](https://github.com/mgamini/elixilorem) - 对药剂Lorem存有发生器.
* [elixir-range-extras](https://github.com/lnikkila/elixir-range-extras) -  Elixir范围实用程序：恒定时间随机采样和设置操作.
* [elixir_bencode](https://github.com/AntonFagerberg/elixir_bencode) - 在Elixir中实施的Bencode.
* [erldn](https://github.com/marianoguerra/erldn) - [EDN](https://github.com/edn-format/edn) Erlang平台的格式解析器.
* [event_source_encoder](https://github.com/chatgris/event_source_encoder) - 将数据编码为符合EventSource的数据.
* [ex_brace_expansion](https://github.com/gniquil/ex_brace_expansion) - 来自于sh / bash，在Elixir中的支撑扩张.
* [ex_cldr](https://github.com/kipcole9/cldr) -  Cldr是Unicode Consortium的公共区域设置数据存储库（CLDR）的Elixir库.
* [ex_rfc3966](https://github.com/marcelog/ex_rfc3966) - 与RFC3966兼容的Elixir Tel URI解析器.
* [ex_rfc3986](https://github.com/marcelog/ex_rfc3986) -  RFC3986 URI / URL解析器.
* [ex_uc](https://github.com/carturoch/ex_uc) -  Elixir的可扩展单元转换器.
* [exmoji](https://github.com/mroth/exmoji) - 为Elixir / Erlang编码瑞士军刀的表情符号.
* [expletive](https://github.com/xavier/expletive) -  Elixir的亵渎过滤库.
* [expr](https://github.com/Rob-bie/Expr) - 用于解析和评估数学表达式的Elixir库.
* [faust](https://github.com/jquadrin/faust) -  Elixir的Markov文本生成器.
* [haikunator](https://github.com/knrz/Haikunator) - 生成类似Heroku的难忘随机名称，以便在您的应用或其他任何地方使用.
* [hashids](https://github.com/alco/hashids-elixir) -  Hashids允许您通过可逆映射来模糊数字标识符.
* [hexate](https://github.com/rjsamson/hexate) -  Elixir中用于十六进制编码/解码的简单模块.
* [inet_cidr](https://github.com/cobenian/inet_cidr) -  Elixir的无类别域间路由（CIDR），兼容：inet，支持IPv4和IPv6.
* [inflex](https://github.com/nurugger07/inflex) -  Elixir的Inflector库.
* [kitsune](https://github.com/edubkendo/kitsune) - 用于转换数据表示的Elixir库.
* [ltsvex](https://github.com/ma2gedev/ltsvex) -  Elixir中的LTSV解析器实现.
* [mbcs](https://github.com/woxtu/elixir-mbcs)   -  erlang-mbcs的包装.  该模块提供字符编码转换功能.
* [mimetype_parser](https://github.com/camshaft/mimetype_parser) - 解析mimetypes.
* [monetized](https://github.com/theocodes/monetized) - A lightweight solution for handling and storing money.
* [money](https://github.com/liuggio/money) - 使用Money更安全，更轻松，更有趣，解读福勒的金钱模式.
* [mt940](https://github.com/my-flow/mt940) -  Elixir的MT940（标准结构化SWIFT客户声明消息）解析器.
* [nanoid](https://github.com/railsmechanic/nanoid) -  NanoID的Elixir端口，一个安全且URL友好的唯一ID生成器.
* [neotomex](https://github.com/jtmoulia/neotomex) - 一个 [PEG](http://bford.info/packrat/) 使用令人愉快的Elixir DSL实现.
* [number](https://github.com/danielberkompas/number) -  Number是一个自命不凡的Elixir库，它提供了将数字转换为各种不同格式的功能.
* [numero](https://github.com/alisinabh/numero) - 用于转换灵丹妙药中非英语utf-8数字的微型库.
* [palette](https://github.com/lpil/palette) - 一个方便的库，用于在Elixir中着色字符串.
* [pinyin](https://github.com/lidashuang/pinyin) -  Elixir的中文拼音库.
* [porterstemmer](https://github.com/frpaulas/porterstemmer) -  Elixir的Porter调谐器.
* [pretty_hex](https://github.com/polsab/pretty_hex) -  Elixir中的二进制十六进制转储库.
* [quickrand](https://github.com/okeuday/quickrand) - 快速随机数生成.
* [RandomStringGenerator](https://github.com/caioceccon/random_string_generator) - 基于给定字符串模式生成随机字符串的模块.
* [ref_inspector](https://github.com/elixytics/ref_inspector)   -  Elixir中的Referer解析器库.  从URL获取信息.
* [remove_emoji](https://github.com/guanting112/elixir_remove_emoji)   -  Elixir中的表情符号文本消毒剂.  它可以删除任何表情符号.
* [secure_random](https://github.com/patricksrobertson/secure_random.ex) - 用于随机base64字符串的便捷库，模仿我对Ruby的SecureRandom的喜爱.
* [sentient](https://github.com/dantame/sentient) - 基于AFINN-111词表的简单情绪分析.
* [shortuuid](https://github.com/gpedic/ex_shortuuid) - 生成简洁，明确，URL安全的UUID.
* [simetric](https://github.com/lexmag/simetric) -  Elixir的字符串相似性度量.
* [slugger](https://github.com/h4cc/slugger) -  Slugger可以从给定字符串生成slug，可以在URL或文件名中使用.
* [stemmer](https://github.com/fredwu/stemmer) - 在Elixir中实施的英语（Porter2）.
* [tau](https://github.com/FranklinChen/tau) - 提供着名的数学常数tau，τ= 6.2831 ....
* [tomlex](https://github.com/zamith/tomlex) -  Elixir的TOML解析器.
* [ua_inspector](https://github.com/elixytics/ua_inspector) - 用户代理解析器库，如`piwik / device-detector`.
* [ua_parser2](https://github.com/nazipov/ua_parser2-elixir)   - 一个ua-parser2到Elixir的端口.  用户代理解析器库.
* [unit_fun](https://github.com/meadsteve/unit_fun) - 在处理数字量时，尝试将单位添加到elixir中的数字以提供一些额外的类型安全性.
* [uuid](https://github.com/zyro/elixir-uuid) -  Elixir的UUID生成器和实用程序.
* [uuid_erl](https://github.com/okeuday/uuid) -  Erlang Native UUID生成.
* [veritaserum](https://github.com/uesteibar/veritaserum) - 基于afinn-165，表情符号和一些增强功能的情感分析.

## Third Party APIs
*用于访问第三方API的库.*

* [airbax](https://github.com/adjust/airbax) - 从Elixir到Airbrake的异常跟踪.
* [airbrake](https://github.com/romul/airbrake-elixir) - An Elixir notifier for the Airbrake.
* [airbrakex](https://github.com/fazibear/airbrakex) - 用于Airbrake服务的Elixir客户.
* [amazon_product_advertising_client](https://github.com/zachgarwood/elixir-amazon-product-advertising-client) -  Elixir的Amazon Product Advertising API客户端.
* [apns](https://github.com/chvanikoff/apns4ex) - Apple Push Notifications Service client library for elixir.
* [asanaficator](https://github.com/trenpixster/asanaficator)   - 用于Asana API的简单Elixir包装器.  基于Tentacat.
* [assembla_api](https://github.com/Assembla/ex_assembla_api) - 为Elixir组装API客户端.
* [balalaika_bear](https://github.com/ayrat555/balalaika_bear) -  Elixir的简单VK API客户端.
* [balanced](https://github.com/bryanjos/balanced-elixir) -  Elixir的平衡API客户端.
* [bandwidth](https://github.com/bandwidthcom/elixir-bandwidth) - 带宽应用平台的Elixir客户端库.
* [bing_translator](https://github.com/ikeikeikeike/bing_translator) -  Bing翻译API的简单Elixir接口.
* [bitmex](https://github.com/nobrick/bitmex) -  Elixir的BitMEX客户端库.
* [bitpay](https://github.com/bitpay/elixir-client) - 用于连接到bitpay.com的Elixir核心库.
* [cashier](https://github.com/swelham/cashier) - 支付网关为多个支付提供商提供通用接口.
* [cleverbot](https://github.com/BlakeWilliams/Elixir-Cleverbot) - 在Elixir中简单实现Cleverbot API.
* [coinbase](https://github.com/gregpardo/coinbase-elixir) - 非官方的Coinbase API v1客户端.
* [commerce_billing](https://github.com/joshnuss/commerce_billing) -  Elixir的支付处理库，支持多个网关（例如Bogus＆Stripe）.
* [correios_cep](https://github.com/prodis/correios-cep-elixir)   - 通过邮政编码直接从Correios数据库查找巴西地址.  没有HTML解析器.
* [currently](https://github.com/chatgris/currently) - 显示目前在Trello上分配卡的工具.
* [darkskyx](https://github.com/techgaun/darkskyx) -  Elixir的Darksky.com（以前的forecast.io）API客户端.
* [digitalocean](https://github.com/lukeed/elixir-digitalocean) -  Digital Ocean API v2的Elixir包装器.
* [digoc](https://github.com/kevinmontuori/digoc) -  Digital Ocean API v2 Elixir客户端.
* [diplomat](https://github.com/peburrows/diplomat) - 一个 [Google Cloud Datastore](https://cloud.google.com/datastore/) 客户.
* [dnsimple](https://github.com/dnsimple/dnsimple-elixir) -  DNSimple API v2的Elixir客户端.
* [docker](https://github.com/hexedpackets/docker-elixir) -  Docker Remote API的Elixir客户端.
* [dockerex](https://github.com/hisea/dockerex) - 具有SSL / TLS登录/连接支持的轻量级Docker远程API客户端.
* [dogstatsd](https://github.com/adamkittelson/dogstatsd-elixir) -  Elixir客户 [DogStatsd](https://www.datadoghq.com/).
* [dpd_client](https://github.com/knewter/dpd_client) -  DPD服务的API客户端.
* [dropbox](https://github.com/ammmir/elixir-dropbox) -  Elixir的Dropbox Core API客户端.
* [dublin_bus_api](https://github.com/carlo-colombo/dublin-bus-api) - 访问都柏林巴士服务的实时乘客信息（RTPI）.
* [edgarex](https://github.com/rozap/edgarex) -  Elixir接口，用于从EDGAR获取SEC文件.
* [elixir_authorizenet](https://github.com/marcelog/elixir_authorizenet) -  Authorize.Net商家API的非官方客户.
* [elixir_ipfs_api](https://github.com/zabirauf/elixir-ipfs-api) -  Elixir的IPFS（InterPlanetary File System）API客户端.
* [elixirfm](https://github.com/jrichocean/Elixirfm) -  Elixir的Last.fm API包装器.
* [elixtagram](https://github.com/zensavona/elixtagram) -  Elixir的Instagram API客户端.
* [ethereumex](https://github.com/exthereum/ethereumex) - 以太坊区块链的Elixir JSON-RPC客户端.
* [everex](https://github.com/jwarlander/everex) -  Elixir的Evernote API客户端.
* [everyoneapi](https://github.com/knewter/everyoneapi) -  EveryoneAPI.com的API客户端.
* [ex_codeship](https://github.com/securingsincity/ex_codeship) -  Codeship的API客户端.
* [ex_gecko](https://github.com/Brightergy/ex_gecko) -  Elixir SDK与Geckoboard的API通信.
* [ex_statsd](https://github.com/CargoSense/ex_statsd) -  Elixir的statsd客户端实现.
* [ex_twilio](https://github.com/danielberkompas/ex_twilio) -  Elixir的Twilio API客户端.
* [ex_twiml](https://github.com/danielberkompas/ex_twiml) - 为Elilir内部的Twilio集成生成TwiML.
* [exdesk](https://github.com/deadkarma/exdesk) -  Desk.com API的Elixir库.
* [exfacebook](https://github.com/oivoodoo/exfacebook) - 使用Ruby koala gem等类似方法在Elixir中编写的Facebook API.
* [exgenius](https://github.com/jeffweiss/exgenius) - （未记录的）Rap Genius API的Elixir库.
* [exgravatar](https://github.com/scrogson/exgravatar) - 用于生成Gravatar URL的Elixir模块.
* [exgrid](https://github.com/bradleyd/exgrid) - 与Sendgrid的API交互.
* [exjira](https://github.com/mattweldon/exjira) -  Elixir的JIRA客户端库.
* [exlingr](https://github.com/mtwtkman/exlingr) -  Lingr客户端模块.
* [explay](https://github.com/sheharyarn/explay) -  Elixir中的非官方Google Play API.
* [exstagram](https://github.com/arthurcolle/exstagram) - 适用于Instagram v1 API的Elixir库.
* [extripe](https://github.com/princemaple/extripe) - 功能完整的Stripe API包装器.
* [extwitter](https://github.com/parroty/extwitter) -  Elixir的Twitter客户端库.
* [exurban](https://github.com/oscar-lopez/exurban) -  UrbanAirship API的Elixir包装.
* [facebook](https://github.com/mweibel/facebook.ex) - 用Elixir编写的Facebook Graph API Wrapper.
* [feedlex](https://github.com/essenciary/feedlex) -  Elixir的Feedly RSS阅读器客户端.
* [fluent_client](https://github.com/trustatom-oss/elixir-fluent-client) - 简约流利的客户.
* [forcex](https://github.com/jeffweiss/forcex) -  Force.com REST API的Elixir库.
* [forecast_io](https://github.com/r-icarus/forecast_io) -  Forecast.IO API的简单包装器.
* [gcmex](https://github.com/dukex/gcmex) - 适用于elixir的Google Cloud Messaging客户端库.
* [google-cloud](https://github.com/GoogleCloudPlatform/elixir-google-api) - 此存储库包含与Google API交互的所有客户端库.
* [google_sheets](https://github.com/GrandCru/GoogleSheets) -  Elixir库，用于以CSV格式获取和轮询Google电子表格数据.
* [govtrack](https://github.com/walterbm/govtrack-elixir) - 简单的Elixir包装纸 [govtrack.us](https://www.govtrack.us/developers) API.
* [gringotts](https://github.com/aviabird/gringotts) -  Elixir和Phoenix Framework的完整支付库类似于 [ActiveMerchant](https://github.com/activemerchant/active_merchant) 来自Ruby世界.
* [hexoku](https://github.com/JonGretar/Hexoku) - 针对Elixir项目的Heroku API客户端和Heroku Mix任务.
* [honeywell](https://github.com/jeffutter/honeywell-elixir) -  Honeywell Lyric，Round和Water Leak＆Freeze Detector API的客户.
* [kane](https://github.com/peburrows/kane) - 一个 [Google Cloud Pub/Sub](https://cloud.google.com/pubsub/overview) 客户.
* [keenex](https://github.com/bryanjos/keenex) -  Keen.io API客户端.
* [link_shrinkex](https://github.com/jonahoffline/link_shrinkex) - 使用Google的URL Shortener API创建短URL的Elixir库.
* [m2x](https://github.com/attm2x/m2x-elixir)   - 用于AT＆T M2X的Elixir客户端，这是一种基于云的完全管理的时间序列数据存储服务，用于网络连接的机器对机器（M2M）设备和物联网（IoT）.  （[Erlang Version](https://github.com/attm2x/m2x-erlang)).
* [mailchimp](https://github.com/duartejc/mailchimp) -  MailChimp API第3版的基本Elixir包装器.
* [mailgun](https://github.com/chrismccord/mailgun) -  Elixir Mailgun客户端.
* [mandrill](https://github.com/slogsdon/mandrill-elixir) -  Elixir的Mandrill包装.
* [marvel](https://github.com/bryanjos/marvel) -  Marvel API的CLI和Elixir API客户端.
* [mexpanel](https://github.com/blendmedia/mexpanel) -  Mixpanel HTTP API的Elixir客户端.
* [mixpanel](https://github.com/michihuber/mixpanel_ex) -  Mixpanel HTTP API的Elixir客户端.
* [mixpanel_data_client](https://github.com/jeregrine/mixpanel_data_client) - 与Mixpanel Data Export API交互的客户端.
* [mmExchangeRate](https://github.com/Arkar-Aung/mmExchangeRate) - 基于缅甸中央银行Api的简单汇率检查和计算器.
* [nadia](https://github.com/zhyu/nadia) - 用Elixir编写的Telegram Bot API Wrapper.
* [omise](https://github.com/teerawat1992/omise-elixir) -  Elix的Omise客户端库.
* [opbeat](https://github.com/teodor-pripoae/opbeat) -  Opbeat的Elixir客户端.
* [pagexduty](https://github.com/ride/pagexduty) -  Elixir的Pagerduty客户.
* [parse_client](https://github.com/elixircnx/parse_elixir_client) - 用于parse.com REST API的Elixir客户端.
* [parsex](https://github.com/maarek/ParsEx) -  ParsEx是一个Elixir HTTP客户端，用于与Parse.com的Restful API进行通信.
* [particle](https://github.com/jeffutter/particle-elixir) - 粒子物联网平台的HTTP API的Elixir客户端.
* [pathway](https://github.com/novabyte/pathway) - 一个Erlang / Elixir客户端 [Trak.io](http://trak.io/) REST API.
* [pay](https://github.com/era/pay) -  Elixir Lib处理Paypal和其他支付解决方案.
* [pay_pal](https://github.com/zensavona/paypal) - 用于使用PayPal REST API的Elixir库.
* [peatio_client](https://github.com/peatio/peatio-client-elixir) -  Elixir的Peatio交换项目兼容API.
* [pigeon](https://github.com/codedge-llc/pigeon) - HTTP2-compliant wrapper for sending iOS and Android push notifications.
* [pocketex](https://github.com/essenciary/pocketex) -  Pocketex是Pocket Read稍后服务的Elixir客户端 [getpocket.com](https://getpocket.com/).
* [pusher](https://github.com/edgurgel/pusher) -  Elixir库，用于访问Pusher REST API.
* [qiita_ex](https://github.com/ma2gedev/qiita_ex) - 针对Elixir的Qiita API v2接口.
* [qiniu](https://github.com/tony612/qiniu) - 针对Elixir的Qiniu SDK.
* [random_user](https://github.com/katgironpe/random_user) -  randomuser.me API的Elixir客户端.
* [random_user_api](https://hex.pm/packages/random_user_api) - 另一个简单的randomuser.me API客户端.
* [reap](https://github.com/Raynes/reap) -  Reap是一个简单的Elixir库，用于处理refheap API.
* [reddhl](https://github.com/MonkeyIsNull/reddhl) -  Reddit及其各种subreddits的标题和链接拉取器.
* [redtube](https://github.com/kkirsche/Redtube_Elixir) - 用Elixir编写的Redtube API Wrapper.
* [reporter](https://github.com/KazuCocoa/simple_app_reporter_ex)   -  Reporter是简单的报告App评论库.  支持AppStore和GooglePlay.
* [riemann](https://github.com/koudelka/elixir-riemann) - 一个 [Riemann](http://riemann.io/) Elixir的客户.
* [rs_twitter](https://github.com/radzserg/rstwitter) -  Elixir的低级Twitter客户端.
* [semver](https://github.com/lee-dohm/semver) - 用于处理符合semver.org标准的版本字符串的实用程序.
* [sendgrid](https://github.com/alexgaribay/sendgrid_elixir) - 使用SendGrid发送可组合的交易电子邮件.
* [shopify](https://github.com/nsweeting/shopify) - 轻松访问Shopify API.
* [sift_ex](https://github.com/C404/sift_ex) -  Elixir的Siftscience API库.
* [simplex](https://github.com/adamkittelson/simplex) - 用于与Amazon SimpleDB API交互的Elixir库.
* [slack](https://github.com/BlakeWilliams/Elixir-Slack) -  Elixir中的Slack实时消息客户端.
* [sparkpost](https://github.com/SparkPost/elixir-sparkpost) - 使用SparkPost发送电子邮件的Elixir库.
* [statix](https://github.com/lexmag/statix) - 在StatsD协议中公开应用指标.
* [stripe](https://github.com/SenecaSystems/stripe) - 包含Stripe API的Elixir库.
* [stripity_stripe](https://github.com/robconery/stripity-stripe) -  Elixir图书馆 [Stripe](https://stripe.com/).
* [tagplay](https://github.com/tagplay/elixir-tagplay) - 用于Tagplay API的Elixir客户端.
* [telephonist](https://github.com/danielberkompas/telephonist) - 用于Twilio呼叫的Elixir状态机.
* [tentacat](https://github.com/edgurgel/tentacat) -  GitHub API的简单Elixir包装器.
* [tg_client](https://github.com/ccsteam/ex-telegram-client) - 与Telegram-CLI通信的Elixir包装器.
* [traitify_elixir](https://github.com/traitify/traitify_elixir) -  Traitify Developer API的Elixir客户端库.
* [ui_faces](https://github.com/katgironpe/ui_faces) - 用于Elixir应用程序的UIFaces API客户端.
* [unsplash-elixir](https://github.com/waynehoover/unsplash-elixir) - 用于Unsplash的Elixir库.
* [vultr](https://github.com/avitex/elixir-vultr) -  Vultr API的简单包装器.
* [xe](https://github.com/paulodiniz/xe) - 货币的实时转换.
* [xend](https://github.com/saulecabrera/xend) -  Facebook的Send API的简单Elixir包装器.
* [zanox](https://github.com/rafaelss/zanox) -  Zanox API.

## Translations and Internationalizations
*提供翻译或国际化的图书馆.*

* [ecto_gettext](https://github.com/exbugs-elixir/ecto_gettext) - 用于本地化的库使用Gettext进行Ecto验证错误.
* [exkanji](https://github.com/ikeikeikeike/exkanji)   - 一个Elixir图书馆，用于翻译平假名，片假名，罗马字和汉字.  它使用Mecab.
* [exromaji](https://github.com/ikeikeikeike/exromaji) - 用于平假名，片假名和罗马字之间翻译的Elixir库.
* [getatrex](https://github.com/alexfilatov/getatrex) - 使用Google Translate for Elixir / Phoenix项目的Gettext语言环境的自动翻译工具.
* [gettext](https://github.com/elixir-lang/gettext) -  Elixir的国际化和本地化支持.
* [linguist](https://github.com/chrismccord/linguist) -  Elixir国际化图书馆.
* [parabaikElixirConverter](https://github.com/Arkar-Aung/ParabaikElixirConverter)   -  ParabaikElixirConverter只是Parabaik转换器的Elixir版本.  它可以从Unicode转换为Zawgyi-One和Zawgyi-One转换为Unicode，反之亦然.
* [trans](https://github.com/belaustegui/trans) -  Elixir库，用于管理嵌入式转换为利用PostgreSQL JSONB数据类型的模型.

## Utilities
*公用事业图书馆.*

* [ar2ecto](https://github.com/aforward/ar2ecto) -  Ar2ecto是一组混合任务，可帮助您从ActiveRecord迁移到Ecto.
* [async_with](https://github.com/fertapric/async_with) -  Elixir的“with”修饰符，用于并行执行所有子句.
* [crutches](https://github.com/mykewould/crutches) -  Elixir的实用程序库，旨在补充与该语言捆绑在一起的标准库.
* [deppie](https://github.com/whitfin/deppie) -  Elixir最酷的弃用记录器.
* [dot-notes](https://github.com/whitfin/dot-notes-elixir) - 地图/列表的简单点/括号表示法解析/转换.
* [dress](https://github.com/veelenga/dress) -  Cli应用程序，让你的stdout花哨.
* [erlang-history](https://github.com/ferd/erlang-history) -  Hacks将shell历史记录添加到Erlang的shell中.
* [erlsh](https://github.com/proger/erlsh) - 涉及与系统shell，路径和外部程序交互的一系列功能和端口.
* [erlware_commons](https://github.com/erlware/erlware_commons) -  Erlang的附加标准库.
* [exjprop](https://github.com/stocks29/exjprop) -  Elixir库，用于从各种来源读取Java属性文件.
* [fitex](https://github.com/timdeputter/FitEx) -  FitEx是一个宏模块，它为函数定义提供了一些糖.
* [global](https://github.com/mgwidmann/global) -  Erlang`：global`模块的包装器.
* [mandrake](https://github.com/mbasso/mandrake) -  Mandrake是一个功能性编程库，可以在灵丹妙药中带来其他魔力.
* [mnemonix](https://github.com/christhekeele/mnemonix) - 键/值存储的统一接口.
* [plasm](https://github.com/facto/plasm) -  Plasm是Ecto的可组合查询多工具，包含更高级别的函数，如.count，.random，.first，.last，.find，.inserted_before，.inserted_after等.
* [pubsub](https://github.com/simonewebdesign/elixir_pubsub) -  Publish-Subscribe实用程序库，它实现了pub-sub机制，以减轻业务逻辑进程的通信负担.
* [quark](https://github.com/robot-overlord/quark) - 用于常见函数式编程习惯用语的库：组合器，currying和部分应用程序.
* [retry](https://github.com/safwank/ElixirRetry) - 简单的Elixir宏，用于线性重试，指数退避和等待可组合延迟.
* [sips_downloader](https://github.com/DavsX/SipsDownloader) - 用于下载ElixirSips剧集和所有其他文件的Elixir模块.
* [sitemap](https://github.com/ikeikeikeike/sitemap) -  Sitemap是在Elixir中生成Sitemap的最简单方法.

## Validations
*用于验证数据的库和实现.*

* [bankster](https://github.com/railsmechanic/bankster) -  Elixir的IBAN帐号和BIC验证库.
* [ex_gtin](https://github.com/kickinespresso/ex_gtin) -  GS1规范下GTIN代码的验证库.
* [exop](https://github.com/madeinussr/exop) - 允许封装业务逻辑并使用预定义合同验证params的库.
* [is](https://github.com/bydooweedoo/is) - 具有嵌套结构支持的elixir的快速，可扩展且易于使用的数据结构验证.
* [jeaux](https://github.com/zbarnes757/jeaux) - 轻松简便的模式验证器.
* [optimal](https://github.com/albert-io/optimal) - 基于模式的关键字列表选项验证器.
* [shape](https://github.com/prio/shape) - 基于Prismatic Sc​​heme的Elixir数据验证库.
* [skooma](https://github.com/bcoop713/skooma) - 用于描述和验证数据结构的简单数据验证库.
* [uk_postcode](https://github.com/KushalP/uk_postcode) - 英国邮政编码解析和验证库.
* [vex](https://github.com/CargoSense/vex) -  Elixir的可扩展数据验证库.
* [voorhees](https://github.com/danmcclain/voorhees) - 用于验证JSON响应的库.

## Version Control
*使用版本控制，如git，mercury，subversion ...... *

* [gitex](https://github.com/awetzel/gitex) -  Elixir实现Git对象存储，但目标是与其他存储和主题实现相同的语义.

## Video
*用于处理和操纵视频和多媒体的图书馆.*

* [ffmpex](https://github.com/talklittle/ffmpex) -  FFmpeg命令行包装器.
* [silent_video](https://github.com/talklittle/silent_video) - 将GIF和视频转换为静音视频，针对移动播放进行了优化.

## XML
*使用XML的库和实现（对于html工具，请转到 [HTML](#html) 部分）.*

* [erlsom](https://github.com/willemdj/erlsom) -  Erlsom是一个用于解析（和生成）XML文档的Erlang库.
* [exmerl](https://github.com/pwoolcoc/exmerl) -  xmerl的Elixir包装纸.
* [exml](https://github.com/expelledboy/exml) -  xmerl xpath最简单的Elixir包装器.
* [exoml](https://github.com/Overbryd/exoml) - 将xml解码/编码为树结构的模块.
* [fast_xml](https://github.com/processone/fast_xml) - 基于Fast Expat的Erlang XML解析库.
* [meeseeks](https://github.com/mischov/meeseeks) - 使用CSS或XPath选择器从HTML和XML解析和提取数据的库.
* [quinn](https://github.com/nhu313/Quinn) -  Elixir的XML解析器.
* [saxy](https://github.com/qcam/saxy) -  Saxy是Elixir中的XML解析器和编码器，专注于速度和标准合规性.
* [sweet_xml](https://github.com/awetzel/sweet_xml) - 简单有效地查询XML.
* [xml_builder](https://github.com/joshnuss/xml_builder) - 用于生成xml的Elixir库.
* [xmlrpc](https://github.com/ewildgoose/elixir-xml_rpc) - 用于为客户端和服务器编码和解码XML-RPC的库.

## YAML
*Libraries and implementations working with YAML.*

* [fast_yaml](https://github.com/processone/fast_yaml) -  Fast YAML是libyaml“C”库的Erlang包装器.
* [yamerl](https://github.com/yakaz/yamerl) -  Erlang中的YAML 1.2解析器.
* [yaml_elixir](https://github.com/KamilLelonek/yaml-elixir) - 基于本机Erlang实现的Elixir的Yaml解析器.
* [yomel](https://github.com/Joe-noh/yomel) -  libyaml接口药剂.

## Resources
各种资源，如书籍，网站和文章，用于提高您的Elixir开发技能和知识.

## Books
*精彩的书籍和电子书.*

* [Adopting Elixir](https://pragprog.com/book/tvmelixir/adopting-elixir)   - 将Elixir带入您的公司，采用来自建立Elixir并成功大规模使用Elixir的人的现实战略.  本书提供了从概念到生产（2017）所需的所有信息.
* [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) - 将您的Web API升级到GraphQL，利用其灵活的查询来授权您的用户，并使用其声明性结构来简化您的代码（2017）.
* [Elixir Cookbook](https://www.packtpub.com/application-development/elixir-cookbook) - 本书是由Paulo A Pereira（2015）按主题分组的一套食谱.
* [Elixir do zero à concorrência](https://www.casadocodigo.com.br/products/livro-elixir) - （葡萄牙语）该书介绍了Tiago Davi（2014）对Elixir的功能和并发编程.
* [Elixir in Action](https://www.manning.com/books/elixir-in-action-second-edition) - 简要介绍该语言，然后更详细地介绍SašaJurić（2015年）在Elixir建立生产就绪系统.
* [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) -  Wolfgang Loder（2016）在功能概念背景下介绍Erlang和Elixir.
* [Erlang in Anger](http://www.erlang-in-anger.com/) - 这本书打算成为Fred Hebert（2014）在战争时期如何成为Erlang军医的小指南.
* [Functional Web Development with Elixir, OTP, and Phoenix](https://pragprog.com/book/lhelph/functional-web-development-with-elixir-otp-and-phoenix) - 打开强大的新技术之门，让您从根本上以全新的方式思考Web开发（2017）.
* [Getting Started - Elixir](https://github.com/potatogopher/elixir-getting-started) -  Elixir入门教程（2016）的PDF，MOBI和EPUB文档.
* [Introducing Elixir ](http://shop.oreilly.com/product/0636920030584.do) - 语言的温和介绍，以及Simon St. Laurent和J. David Eisenberg（2013）的大量代码示例和练习.
* [Learn Functional Programming with Elixir](https://pragprog.com/book/cdc-elixir/learn-functional-programming-with-elixir)   - 不要以强制性思维方式登上Elixir火车！  要充分利用函数式语言，您需要在功能上思考（2017）.
* [Metaprogramming Elixir: Write Less Code, Get More Done (and Have Fun!)](https://pragprog.com/book/cmelixir/metaprogramming-elixir) - 彻底解释如何利用Elixir的元编程功能来改进你的Elixir编码，Chris McCord（2015）.
* [Phoenix for Rails Developers](http://www.phoenixforrailsdevelopers.com) - This book shows how Rails developers can benefit from their existing knowledge to learn Phoenix. By Elvio Vicosa (2017).
* [Phoenix in Action](https://manning.com/books/phoenix-in-action)   - 以您现有的网络开发技能为基础，向您传授凤凰城的独特优势以及足够的Elixir来完成工作.  作者：Geoffrey Lessel（2017）.
* [Phoenix Inside Out](https://shankardevy.com/phoenix-book/)   - 本系列的目标是让您成为一名自信的凤凰开发者.  有3种不同的版本可以满足开发者涌入凤凰城的各种需求.
* [Programming Elixir](https://pragprog.com/book/elixir/programming-elixir) - 本书介绍了Dave Thomas（2014）对Elixir的功能和并发编程.
* [Programming Phoenix](https://pragprog.com/book/phoenix/programming-phoenix) -  Chris McCord，JoséValim和Bruce Tate（2015）使用Phoenix框架构建Web应用程序的权威指南.
* [The Beam Book](https://happi.github.io/theBeamBook/) -  Erlang运行时系统ERTS和虚拟机BEAM的描述.
* [The Little Elixir & OTP Guidebook](https://www.manning.com/books/the-little-elixir-and-otp-guidebook) -  Benjamin Tan Wei Hao（2014）通过中小型项目学习Elixir和OTP的书.
* [Études for Elixir](http://chimera.labs.oreilly.com/books/1234000001642) -  J. David Eisenberg撰写的Elixir项目练习集（2013）（[Github Repo](https://github.com/oreillymedia/etudes-for-elixir)).

## Cheat Sheets
*有用的与Elixir相关的备忘单.*

* [benjamintanweihao/elixir-cheatsheets](https://github.com/benjamintanweihao/elixir-cheatsheets/) -  GenServer和主管的秘籍表.

## Community
*通过聊天或邮件列表与社区联系.*

* [#elixir-lang](http://webchat.freenode.net/?channels=elixir-lang) - The IRC Channel #elixir-lang on Freenode.
* [Elixir Forum](https://elixirforum.com/) -  Elixir所有事物的社区运行讨论论坛.
* [elixir-lang-core](https://groups.google.com/d/forum/elixir-lang-core) -  Elixir Core开发的邮件列表，使用“talk”进行问题和一般性讨论.
* [elixir-lang-talk](https://groups.google.com/d/forum/elixir-lang-talk) - 问题和讨论的官方Elixir邮件列表.
* [ElixirSlack](https://elixir-slackin.herokuapp.com/) -  Elixir Slack社区.

## Editors
*编辑器和IDE可用于Elixir / Erlang *

* [Alchemist](https://github.com/tonini/alchemist.el) -  Elixir工具集成到Emacs中.
* [Alchemist-Server](https://github.com/tonini/alchemist-server) - 编辑器/ IDE独立后台服务器，以通知Elixir混合项目.
* [Alchemist.vim](https://github.com/slashmili/alchemist.vim) -  Elixir工具集成到Vim.
* [Atom](https://atom.io/packages/language-elixir) -  Atix的Elixir语言支持.
* [atom-elixir](https://github.com/msaraiva/atom-elixir) -  Elixir的Atom包.
* [atom-iex](https://github.com/indiejames/atom-iex) - 在Atom中运行IEx会话.
* [elixir-ls](https://github.com/JakeBecker/elixir-ls)   -  Elixir的前端独立IDE“智能”服务器.  实现基于JSON的“语言服务器协议”标准，并通过VS Code的调试器协议提供调试器支持.
* [elixir-tmbundle](https://github.com/elixir-lang/elixir-tmbundle) -  Elixir的TextMate和SublimeText包.
* [elixir_generator](https://github.com/jadercorrea/elixir_generator.vim) - 使用一个命令生成Elixir模块和测试文件的Vim插件.
* [ElixirSublime](https://github.com/vishnevskiy/ElixirSublime) -  SublimeText 3的Elixir插件，提供代码完成和linting.
* [ilexir](https://github.com/dm1try/ilexir) -  Neovim中Elixir的类似IDE的东西.
* [intellij_elixir](https://github.com/KronicDeth/intellij_elixir) - 用于intellj-elixir的Elixir助手，JetBrains IDE的Elixir插件.
* [Jetbrains](http://plugins.jetbrains.com/plugin/7522) -  Elixir for IntelliJ IDEA，RubyMine，WebStorm，PhpStorm，PyCharm，AppCode，Android Studio，0xDBE.
* [Notepad++](https://github.com/Hades32/elixir-udl-npp) -  Notepad ++的Elixir语法高亮显示.
* [nvim](https://github.com/dm1try/nvim) -  Neovim主持人在Elixir中编写插件.
* [phoenix-snippets](https://github.com/phoenixframework-Brazil/phoenix-snippets) - 用于Atom的Phoenix Snippets.
* [vim-elixir](https://github.com/elixir-lang/vim-elixir) - Vim configuration files for Elixir.
* [vim-ex_test](https://github.com/moofish32/vim-ex_test) - 基于Thoughtbots vim-rspec的Vim测试运行器.
* [vim-mix-format](https://github.com/mhinz/vim-mix-format) -  Vim和Neovim的异步`混合格式`.
* [vscode-elixir](https://github.com/mat-mcloughlin/vscode-elixir) -  Elixir支持Visual Studio代码.
* [vscode-elixir-ls](https://github.com/JakeBecker/vscode-elixir-ls) - 由ElixirLS提供支持的VS Code的Elixir语言支持和调试器.

## Newsletters
*有用的与Elixir相关的新闻稿.*

* [Elixir Digest](http://elixirdigest.net) - 每周通讯，内容包括Elixir和Phoenix的最新文章.
* [Elixir Radar](http://plataformatec.com.br/elixir-radar) - 由Plataformatec通过电子邮件每周发布的“官方”Elixir新闻通讯.
* [ElixirWeekly](https://elixirweekly.net) -  Elixir社区通讯，涵盖您很容易错过的内容，分享 [ElixirStatus](http://elixirstatus.com) 和网络.

## Other Awesome Lists
*其他惊人的精彩列表可以在 [jnv/lists](https://github.com/jnv/lists#lists-of-lists) 要么 [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness#awesome-awesomeness).*

* [Awesome Elixir and CQRS](https://github.com/slashdotdash/awesome-elixir-cqrs) - 精选的Elixir和Command Query Responsibility Segregation（CQRS）以及事件采购资源的精选列表.
* [Awesome Elixir by LibHunt](https://elixir.libhunt.com) - 精选的Elixir和Erlang包和资源的精选列表.
* [Awesome Erlang](https://github.com/drobakowski/awesome-erlang) - 精选的Erlang库，资源和闪亮的东西的精选列表.
* [Curated Elixir Resources](https://hackr.io/tutorials/learn-elixir) - 一系列推荐的Elixir资源.
* [Erlang Bookmarks](https://github.com/0xAX/erlang-bookmarks) -  Erlang开发人员的链接集合.

## Reading
* Elixir相关的阅读材料.*

* [Discover Elixir & Phoenix](https://www.ludu.co/course/discover-elixir-phoenix/) - 在线课程，教授Elixir语言和Phoenix框架.
* [Elixir Cheat-Sheet](http://media.pragprog.com/titles/elixir/ElixirCheat.pdf) - 安迪·亨特和戴夫·托马斯的Elixir作弊表.
* [Elixir Functional Programming](https://github.com/kblake/functional-programming) - 使用Elixir语言介绍函数式编程的材料.
* [Elixir School](https://elixirschool.com/) - 关于Elixir编程语言的课程.
* [Elixir Tab](https://github.com/efexen/elixir-tab) -  Chrome扩展程序，可帮助您学习Elixir核心库.
* [The Little Schemer in Elixir](https://github.com/jwhiteman/a-little-elixir-goes-a-long-way) -  Little Schemer一书中的练习和算法，移植到Elixir.
* [xElixir](https://github.com/exercism/xelixir) -  Elixir的运动练习.

## Screencasts
*酷视频教程.*

* [Confreaks (Elixir)](http://confreaks.tv/tags/40) -  Elixir相关会议讲座.
* [Elixir for Programmers](https://codestool.coding-gnome.com/courses/elixir-for-programmers) - 功能，平行，可靠（和有趣！），由戴夫托马斯教授.
* [Elixir Sips](http://elixirsips.com/) - 用于学习Elixir的微小屏幕录像.
* [ElixirCasts.io](https://elixircasts.io/) - 简单的截屏视频，帮助您学习Elixir和Phoenix.
* [ExCasts](https://excasts.com) - 适用于所有技能水平的Elixir和Phoenix截屏视频.
* [LearnElixir.tv](https://www.learnelixir.tv/) - 初学者友好，深入，一步一步的截屏视频.
* [LearnPhoenix.tv](https://www.learnphoenix.tv/) - 了解如何使用Phoenix构建快速，可靠的Web应用程序.
* [Meet Elixir](https://www.pluralsight.com/courses/meet-elixir) - 介绍JoséValim的Elixir的一些特征和概念.

## Styleguides
*用于确保编码时一致性的样式.*

* [christopheradams/elixir_style_guide](https://github.com/christopheradams/elixir_style_guide) -  Elixir的社区驱动风格指南.
* [lexmag/elixir-style-guide](https://github.com/lexmag/elixir-style-guide) - 一份自以为是的Elixir风格指南.
* [rrrene/elixir-style-guide](https://github.com/rrrene/elixir-style-guide) - 样式指南检查 [Credo](https://github.com/rrrene/credo).

## Websites
*有用的Elixir相关网站.*

* [30 Days of Elixir](https://github.com/seven1m/30-days-of-elixir) - 在30个练习中漫步Elixir语言.
* [BEAM Community](http://beamcommunity.github.io/) - 从分布式系统，到Erlang VM上的强大服务器和语言设计.
* [Benjamin Tan - Learnings & Writings](http://benjamintan.io/blog/tags/elixir/) - 一个主要由Elixir帖子组成的博客.
* [Elixir Career](https://elixir.career/) -  Elixir的工作委员会和Elixir开发人员社区.
* [Elixir China](https://github.com/jw2013/elixir-china) - 中国药剂网站 [elixir-cn.com](http://elixir-cn.com/).
* [Elixir Examples](http://elixir-examples.github.io/) - 一系列小型Elixir编程语言示例.
* [Elixir Flashcards](https://elixircards.co.uk/)   - 抽认卡是提高知识水平的有效方式.  Elixircards是手工制作的专业印刷卡片，用于升级Elixir.
* [Elixir Fountain](https://soundcloud.com/elixirfountain) - 每周播客，播放由Elixir社区周围的新闻和采访 [Johnny Winn](https://twitter.com/johnny_rugger).
* [Elixir Github Repository](https://github.com/elixir-lang/elixir) - 项目存储库.
* [Elixir Github Wiki](https://github.com/elixir-lang/elixir/wiki) - 项目的维基，包含许多有用的信息.
* [Elixir Quiz](http://elixirquiz.github.io/) - 每周编程问题，以帮助您学习Elixir.
* [Elixir Recipes](http://elixir-recipes.github.io/) - 收集Elixir常见问题的模式和解决方案.
* [Hashrocket Today I Learned - Elixir](https://til.hashrocket.com/elixir) - 关于来自Hashrocket团队的Elixir的小帖子.
* [How I start - Elixir](http://howistart.org/posts/elixir/1) - JoséValim对Elixir的解释和介绍.
* [Learning Elixir](http://learningelixir.joekain.com/) - 关于专业软件工程师学习Elixir的博客.

## Contributing
请参阅 [CONTRIBUTING](https://github.com/h4cc/awesome-elixir/blob/master/.github/CONTRIBUTING.md) 详情.
