<div class="github-widget" data-repo="CodyReichert/awesome-cl"></div>
<div align="center">
  <a href="https://awesome-cl.com" target="_blank">
    <img src="https://i.imgur.com/jLVXhpc.png">
  </a>
</div>

## Awesome Common Lisp [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Assertible status](https://assertible.com/apis/102e334d-f9a8-4565-9353-7572de775cae/status?api_token=8b55a286830323effb)](https://assertible.com/docs/guide/deployments)

一个很棒的 Common Lisp 库的精选列表.

对于很棒的*软件*，请参阅 [lisp-lang.org's success stories](http://lisp-lang.org/success/) 和 [awesome-cl-software](https://github.com/azzamsa/awesome-cl-software) 列表.

此处列出的所有库均可从 [Quicklisp][16] 获得，除非
另有说明. 标有 ⭐ 的应用非常普遍，而且
坚定地认为它们成为了社区标准. 你不会错
他们.  Quicklisp、BordeauxThreads 和
这样的. 用 a 表示的库是我们喜欢并且想要的库
promote here at the Awesome-cl list. They proved solid, they may solve
一个比社区标准更好的问题，但它们并不那么好
广泛存在，或不被认为是稳定的. 例如，我们更喜欢
Cl-Who 上方的喷丝板.

添加新内容！ 请参阅 [contributing](#contributing) 部分添加一些东西到
list.

这是在 GNU 自由文档许可证下发布的 - 其文本
在 LICENSE 文件中提供. 该存储库也镜像在
[NotABug](https://notabug.org/CodyReichert/awesome-cl) - **完全免费**（如 libre）
 Github 的替代品. 优先考虑[自由软件][13]并且
不为物质资源作恶的卖家.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->


<!-- markdown-toc end -->


Audio
=====

* [Open Music](https://github.com/openmusic-project/OM6)  - 可视化编程、计算机辅助创作环境.  [GPL3][2].
* [OM7](https://github.com/openmusic-project/om7)  - OpenMusic 可视化编程和计算机辅助作曲环境的新实现，包括图形界面、计算模式以及与外部软件库的连接方面的多项改进.  [GPL3][2].
* [Incudine](http://incudine.sourceforge.net/)  - Common Lisp 的音乐/DSP 编程环境. 对于从头开始设计软件合成器或声音插件很有用. 它也是一种作曲工具，可以在样本级别产生可控制的高质量声音，从而动态定义和重新定义数字信号处理器和音乐结构.
* [cl-collider](https://github.com/byulparan/cl-collider) - A
[SuperCollider](http://supercollider.github.io/)  CommonLisp 的客户端. 与一个 [tutorial](https://github.com/defaultxr/cl-collider-tutorial) 和 [live coding demos](https://www.youtube.com/watch?v=xzTH_ZqaFKI) . 公共区域.
* [csound](https://github.com/csound/csound)  - 声音和音乐计算系统. 包括 Common Lisp 的 CFFI 和 FFI 接口.
* [CLM](https://ccrma.stanford.edu/software/clm/)  - Common Lisp Music 是 Music V 系列中的音乐合成和信号处理包. 它提供了与 Stk、Csound、SuperCollider、PD、CMix、cmusic 和 Arctic 几乎相同的功能——一组创建和操作声音的函数，主要针对作曲家（无论如何，在 CLM 的情况下）.
  * [common-tones](https://github.com/theraphonics/common-tones)  - CLM5 与现代 Lisp 的分支（ASDF、cffi...）.  [BSD_3 条款][15].
* [cl-patterns](https://github.com/defaultxr/cl-patterns)  - 一个通过 Lisp 代码创作音乐的系统，深受 SuperCollider 模式系统的启发，旨在实现其中的大部分内容，但以更强大、更具表现力、一致、反思和 lispy 的方式. 通过 SuperCollider 进行音频输出，初步支持 Incudine，并通过 ALSA 进行 MIDI 输出.
* [cl-openal](https://github.com/zkat/cl-openal)  - OpenAL 音频库的绑定. 公共区域.
* [Common Music](https://github.com/ormf/cm) - 的存储库
Common Music 的古代版本（版本 2.12.0），大概是最后一个
在 Common Lisp 上运行的版本可以追溯到 2007 年 9 月左右，之前
Common Music 的工作转移到（基于方案的）cm3.
* [Slippery Chicken](https://github.com/mdedwards/slippery-chicken/)  - 算法作曲库，通过 Lilypond 输出 Midi、通用音乐符号、pdf 乐谱，通过 Common Lisp Music 输出声音.  [GPL3][2].
* [Common Music Notation](https://ccrma.stanford.edu/software/cmn/)  - 通用乐谱 (CMN) 提供了一组函数来分层描述乐谱. 公共区域.
* [cm-incudine](https://github.com/ormf/cm-incudine)  - 通过实时功能扩展 Common Music 2.  GPL2.
* [Mégra](https://github.com/the-drunk-coder/megra)  - 一种迷你语言，可以用变阶马尔可夫链和其他一些随机恶作剧来制作音乐.  [GPL3][2].
* [Music](https://github.com/MegaLoler/Music) - Lisp 中的音乐表达框架，重点是音乐理论（从头开始构建，与通用音乐无关）.
* [rq](https://github.com/openmusic-project/RQ) - OpenMusic 中的节奏转录库（版本 6.10 及更高版本）. [demo video](https://www.youtube.com/watch?v=XVEllB0TtVs) .  [GPL3][2].
* [scheduler](https://github.com/byulparan/scheduler)  - Common Lisp 的基于时间的音乐事件调度程序.  [Apache2.0][89].
* [mixalot](https://github.com/ahefner/mixalot)  - 松散耦合的 mp3、ogg vorbis、flac 音频库集合. 用于 [Shuffletron music player](https://github.com/ahefner/shuffletron) .  [麻省理工学院][200].
* [osc](https://github.com/zzkt/osc)  - 开放声音协议的实现.  [LGPL2.1][11].
* [Harmony](https://shirakumo.github.io/harmony)  - 实时声音处理和播放系统.  [zlib][33].


构建系统
=============

* ⭐[ASDF](https://common-lisp.net/project/asdf/)  - 另一个系统定义工具；  Common Lisp 的构建系统.  [外籍人士][14].  Quicklisp（参见 [library manager](#library-manager)）在幕后使用 ASDF.
  * [known ASDF extensions](https://common-lisp.net/project/asdf/#extensions)，例如“asdf-system-connections”，它允许您指定在加载其他两个系统时自动加载的系统，以连接它们.
* [asdf-linguist](https://github.com/eudoxia0/asdf-linguist)  - ASDF 的扩展.  [外籍人士][14].
* [asdf-viz](https://github.com/guicho271828/asdf-viz)  - 可视化 ASDF 系统的库依赖性、函数调用图和类继承的工具.  [LLGPL][8].

也可以看看：

* [modularize](https://github.com/Shinmera/modularize)  - Common Lisp 的模块化框架.  [zlib][33].
  * 提供一个通用接口来隔离主要的应用程序组件.
  * 例如，通过添加模块定义选项，您可以引入将模块在功能上捆绑在一起、相互挂钩等的机制.
  * 充当 `defpackage` 的包装器并集成到 ASDF 中.

编译器、代码生成器
==========================

APL
---

* [April](https://github.com/phantomics/april)  - APL 编程语言（其子集）编译为 Common Lisp. 用一行 APL 替换数百行数字运算代码.  [阿帕奇2][89].


C、C++
------

* [cmacro](https://github.com/eudoxia0/cmacro) - C 语言的 Lisp 宏.[MIT][200].
* [C-mera](https://github.com/kiselgra/c-mera)  - 一个源到源的编译器，利用 Lisp 的宏系统对类 C 语言进行元编程.  [GPL3][2].
* [lispc](https://github.com/eratosthenesia/lispc) - C 的强大“lispsy”宏语言.[MIT][200].
* [with-c-syntax](https://github.com/y2q-actionman/with-c-syntax)  - 一个有趣的包，它将 C 语言语法引入 Common Lisp.  （是的，我认为这个包不适用于实际编码.）WTFPL 许可证.
* [ecrepl](https://gitlab.common-lisp.net/ecl/ecrepl) - an interactive REPL for the C language. [BSD_2Clause][17].
* [Software-Evolution-Library](https://github.com/GrammaTech/sel)  - SEL 支持对软件进行编程修改和评估（使用 Clang、编译的汇编程序和链接的 ELF 二进制文件支持 C/C++）.  [GPL3][2].

Cryptography
============

* ⭐ [Ironclad](https://github.com/sharplispers/ironclad)  - Common Lisp 的加密函数库. 不被认为是安全的，但对于消息摘要功能仍然有用.  [外籍人士][14].
* [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts)  - 常见加密快捷方式的集合.  [zlib][33].
* [trivial-ssh](https://github.com/eudoxia0/trivial-ssh)  - SSH 客户端库.  [外籍人士][14].
* [cl-ssh-keys](https://github.com/dnaeon/cl-ssh-keys)  - 用于生成和解析 OpenSSH 密钥的 Common Lisp 系统.  [BSD_3 条款][15].
* [cl-bcrypt](https://github.com/dnaeon/cl-bcrypt)  - 用于解析和生成 bcrypt 密码哈希值的 Common Lisp 系统.  [BSD_3 条款][15].
  * 也可以看看 [cl-pass](https://github.com/eudoxia0/cl-pass)，使用 pbkdf2.
* [gpgme](https://www.gnupg.org/download/index.en.html#gpgme)  (GnuPG Made Easy) 是从编程语言访问 GnuPG 函数的标准库. 它提供了官方的 Common Lisp 系统.
  * [gpgme lisp sources](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpgme.git;a=tree;f=lang/cl;h=05151bdf839e513f534a1b423d59332a2e46fd5d;hb=HEAD)  （不在 Quicklisp 中）.  GPL2.
* [cl-frugal-uuid](https://github.com/ak-coram/cl-frugal-uuid/)  - 零依赖的 Common Lisp UUID 库.  [麻省理工学院][200].

Cryptocurrencies
================

* [bp](https://github.com/rodentrabies/bp)  - Common Lisp 中的比特币协议组件.  [麻省理工学院][200].
* [cl-monero-tools](https://github.com/glv2/cl-monero-tools)  - 用于使用 Monero 加密货币的 Common Lisp 工具箱.  [GPL3][2]. 不在 Quicklisp 中.
* [emotiq](https://github.com/emotiq/emotiq)  - 具有创新的自然语言智能合约方法的下一代区块链.  [麻省理工学院][200].
* [peercoin-blockchain-parser](https://github.com/glv2/peercoin-blockchain-parser)  - 解析文件中包含的区块链并将其部分数据导出到文本文件、SQL 脚本或数据库. 它还可以使用 Peercoin 守护程序的 RPC 作为数据源而不是区块链文件来创建数据库.  LGPL3. 不在 Quicklisp 中.
* [peercoin-calculator](https://github.com/glv2/peercoin-calculator)  - 该计划为您提供在 10 分钟、24 小时、31 天、90 天和 1 年内生成 POS 或 POW 区块的概率，以及可预期的奖励.  Qt 中的 GUI.  [GPL3][2]. 不在 Quicklisp 中.
* [peercoin-vote](https://github.com/glv2/peercoin-vote)  - 基于区块链数据（地址和余额）的投票系统.  [GPL3][2]. 不在 Quicklisp 中.

也可以看看 [legochain](https://github.com/defunkydrummer/legochain)，一个简单的教育区块链.

Database
========

* [cl-yesql](https://github.com/ruricolist/cl-yesql)  - SQL 语句以 SQL 语法存在于它们自己的文件中，并作为函数导入到 Lisp 中. 您不受 DSL 支持的功能的限制. 基于 Clojure 的 Yesql.  [麻省理工学院][200].

ORMs
----

* ⭐ [clsql](http://www.cliki.net/CLSQL)  - 具有 Common Lisp 接口的 SQL 数据库.  [LLGPL][8].
* [mito](https://github.com/fukamachi/mito) - Common Lisp 的 ORM，具有迁移、关系和 PostgreSQL 支持 [LLGPL][8].
  * [mitho-auth](https://github.com/fukamachi/mito-auth)，一个用于使用授权的 mixin 类
  * [mito-attachment](https://github.com/fukamachi/mito-attachment)，一个用于 RDBMS 之外的文件管理的 mixin 类.
* [cl-dbi](https://github.com/fukamachi/cl-dbi)  - Common Lisp 的独立于数据库的接口.  [LLGPL][8].
  * [dbd-oracle](https://github.com/sergadin/dbd-oracle)  - CL-DBI 的 Oracle 数据库驱动程序.  [LLGPL][8].
* [crane](https://github.com/eudoxia0/crane)  - 另一个 ORM.  [外籍人士][14].
* [datafly](https://github.com/fukamachi/datafly)  - 一个轻量级的数据库.  [3 条款 BSD][15].
* [sxql](https://github.com/fukamachi/sxql)  - 用于生成 SQL 的 DSL.  [3 条款 BSD][15].

持久对象数据库
---------------------------

* [bknr.datastore](https://github.com/hanshuebner/bknr-datastore) - RAM 中基于 CLOS 的仅 lisp 数据库，具有事务日志持久性. [Manual](https://www.common-lisp.net/project/bknr/html/documentation.html) .  [许可证][208].
  * 另请参阅此 [good introductory blog post](https://ashok-khanna.medium.com/persistent-in-memory-data-storage-in-common-lisp-b-k-n-r-37f8ae76042f)
  * 使用 bknr.datastore 的示例 Web 应用程序： [screenshotbot-oss](https://github.com/screenshotbot/screenshotbot-oss).
* [ubiquitous](https://github.com/Shinmera/ubiquitous)  - 提供易于使用的持久配置存储的库.  [zlib][33].
* [cl-prevalence](https://common-lisp.net/project/cl-prevalence/)  - 内存数据库系统. 对象普遍性的实现，其中业务对象保留在内存中，并记录事务以供系统恢复. [github fork](https://github.com/40ants/cl-prevalence) .  [LLGPL][8].
  * 也可以看看 [cl-prevalence-multimaster](https://github.com/40ants/cl-prevalence-multimaster)，同步多个 cl-prevalence 系统状态.
* [cl-naive-store](https://gitlab.com/Harag/cl-naive-store)  - Common Lisp 的一个简单的持久性内存（延迟加载）索引文档存储.  [麻省理工学院][200].
  - 看 [the introductory blog post](https://zaries.wordpress.com/2022/05/31/cl-naive-store/)
  - 我们敢添加：由作者公司（ASTN Group，参见 Awesome-lisp-companies）用于生产

也可以看看 [Clache](#caching)，可以将任何对象保存在磁盘上.


图数据库
---------------

* [cl-agraph](https://github.com/vseloved/cl-agraph)，最小客户端 [AllegroGraph](https://allegrograph.com/) .  AllegroGraph 是一种水平分布式、多模型（文档和图）、实体-事件知识图谱技术. 它是专有的，并且有一个免费版本，限制为 500 万个三元组.
* [neo4cl](https://github.com/equill/neo4cl)  - 与 Neo4J 交互的库. 将 Cypher 查询发送到 Neo4J 服务器，并将响应解码为可用于 CL 处理的内容.  [阿帕奇2][89].
  * 有可能： [cl-neo4j](https://github.com/kraison/cl-neo4j) - 精简的 neo4j RESTFUL 客户端界面.
* [vivace-graph](https://github.com/kraison/vivace-graph-v3)  - 图形数据库和 Prolog 实现. 从 CouchDB、neo4j 和 AllegroGraph 获取设计灵感. 它使用用户定义的索引和映射缩减视图实现符合 ACID 的对象图模型. 它还实现了主/从复制方案，以实现冗余和水平读取扩展. 查询图是通过许多 Lisp 方法或类似 Prolog 的查询语言来完成的.  [麻省理工学院][200].
  * "I have used Vivace Graph as an online catalog for millions of products, as the back end for a complex, adaptable VoIP-based IVR, as well as data store for several complex big data analysis systems, and finally as the engine for two recommender systems." (issue #23)
  * “为什么 vivace graph 这么快？我一直在将它与基于 SQL 的方法和 Neo4j 进行比较，vivace graph 快得多.”

并且：

* [restagraph](https://github.com/equill/restagraph)  - 使用数据库中定义的模式为 Neo4j 数据库动态生成 REST API 的应用程序.  [GPL3][2].
* [facts](https://github.com/cl-facts/facts)  - 内存图形数据库，具有事务和回滚、日志记录/重放以及从磁盘转储/加载.  BSD 样式许可证 (ISC).


Wrappers
--------

* ⭐ [postmodern](http://marijnhaverbeke.nl/postmodern/)  - 与 PostgreSQL 交互的库.  [zlib][33].
* [cl-sqlite](https://github.com/dmitryvk/cl-sqlite)  - SQLite 的绑定. 公共区域.
* [cl-memcached](https://github.com/quasi/cl-memcached)  - Memcached 对象缓存系统的快速、线程安全接口.  [外籍人士][14].
* [cl-mongo](https://github.com/fons/cl-mongo)  - MongoDB 客户端.  [外籍人士][14].
* [cl-redis](https://github.com/vseloved/cl-redis)  - Redis 客户端.  [外籍人士][14].
* [cl-disque](https://github.com/CodyReichert/cl-disque)  - 客户盘.  [BSD 3 条款][15].
* [cl-rethinkdb](https://github.com/orthecreedence/cl-rethinkdb)  - RethinkDB 客户端.  [外籍人士][14].
* [cl-mango](https://github.com/cmoore/cl-mango/)  - 极简的 CouchDB 2.x 数据库客户端.  BSD_3 条款.
  * 也可以看看 [clouchdb](https://common-lisp.net/project/clouchdb/)  - 用于与 CouchDB 交互的库.  [FreeBSD][39].
* [lmdb](https://github.com/antimer/lmdb) - 绑定到 [LMDB](http://www.lmdb.tech/doc/)，闪电内存映射数据库，具有多版本并发控制的 ACID 键值数据库.
* [cl-ndbapi](https://github.com/datagraph/cl-ndbapi) - 绑定到 C++ NDB API [RonDB](https://www.rondb.com/)，“世界上最快的键值存储”，作者： [Dydra](https://dydra.com/home) .  GPLv2.
* [cl-duckdb](https://github.com/ak-coram/cl-duckdb)  - DuckDB C API 的 Common Lisp CFFI 包装器.  [麻省理工学院][200].

迁移工具
---------------

* [cl-migratum](https://github.com/dnaeon/cl-migratum)  - 提供用于执行数据库模式迁移的设施的系统，旨在与各种数据库一起使用.  [BSD_3 条款][15].
* [postmodern-passenger-pigeon](https://github.com/fisxoj/postmodern-passenger-pigeon/)  - 后现代的迁移经理. 未指定许可证.


致第三方
----------------

* [dyna](https://github.com/Rudolph-Miller/dyna)  - AWS DynamoDB ORM.  [麻省理工学院][200].
* [cl-influxdb](https://github.com/mmaul/cl-influxdb/)  - 时间序列数据库 InfluxDB 的接口.  [麻省理工学院][200].
* [pzmq](https://github.com/orivej/pzmq)  - ZeroMQ 4.0+ Common Lisp 绑定. 无执照.

Tools
-----

* ⭐ [pgloader](https://github.com/dimitri/pgloader)  - PostgreSQL 的数据加载工具.  [PostgreSQL 许可证][205].


数据结构
===============

* [str](https://github.com/vindarel/cl-str)  - 一个现代、简单且一致的字符串操作库.  [麻省理工学院][200].
* [FSet](https://common-lisp.net/project/fset)  - 一个功能性的集合论集合数据结构库.  [LLGPL][8].
* [trivial-extensible-sequences](https://github.com/Shinmera/trivial-extensible-sequences) - 可扩展序列协议的可移植库（[SBCL documentation](http://www.sbcl.org/manual/#Extensible-Sequences) ）.  [zlib][33].
* [bst](https://github.com/glv2/bst)  - 二叉搜索树.  [GPL3][2].
* [pileup](http://nikodemus.github.io/pileup/)  - Common Lisp 的可移植、高性能和线程安全的二进制堆.  [麻省理工学院][200].
* [sycamore](https://github.com/ndantam/sycamore)  - 一个快速、纯功能的数据结构库.  [BSD_3 条款][15].
* [genhash](https://github.com/pnathan/genhash)  – 使用通用方法的 API 实现哈希表. 公共区域.
* [cl-ctrie](https://github.com/danlentz/cl-ctrie) -
无锁、并发、键/值索引，具有高效的内存映射持久性和快速瞬态存储模型.  [麻省理工学院][200].
* [cl-data-structures](https://github.com/sirherrbatka/cl-data-structures)  - 数据结构和算法的可移植集合（主要是字典和序列，带有一些统计函数）.  [BSD][15].
* [listopia](https://github.com/Dimercel/listopia)  - 受 Haskell 的 Data.List 启发的列表操作库.  [LLGPL][8].
* [hash-set](https://github.com/samebchase/hash-set/) - 在 CL 哈希表之上实现哈希集的便利库 [The Unlicense][5]
* [bit-smasher](https://github.com/thephoeron/bit-smasher)  - 用于处理位向量、位向量算术和类型转换的 Common Lisp 库.  [麻省理工学院][200].
* [cl-containers](https://common-lisp.net/project/cl-containers/) - 一个广泛的数据结构和实用程序库 - 队列、树、堆、双向链表、集合、包……[MIT][200]
* [cl-competitive](https://github.com/privet-kitty/cl-competitive)  - 用于竞争性编程的 Common Lisp 算法集合. 公共领域、CCO 或 MIT.

访问数据结构：

* [access](https://github.com/AccelerationNet/access/)  - 对最常见数据结构的一致和嵌套访问.  [BSD_3 条款][15].
* [modf](https://github.com/smithzvk/modf) - 用于函数式编程的类似 setf 的宏.

其他数据结构：

* [bitfield](https://github.com/marcoheisig/bitfield)  - 有效地将多个有限集或小整数表示为单个非负整数.  [麻省理工学院][200].


Docker 镜像
=============

* [cl-docker-images](https://common-lisp.net/project/cl-docker-images/) - Windows (amd64) 以及 Alpine 和 Debian (amd64、arm64、arm/v7) 上的 ABCL、CCL、ECL 和 SBCL 的 Docker 映像 [BSD_2Clause][17].
* [base-lisp-image](https://github.com/40ants/base-lisp-image) - 根据
  使用 SBCL 或 CCL 以及最新版本的 Common Lisp 项目的 Docker 镜像
  ASDF、Qlot 和罗斯威尔.
* [archlinux-cl](https://github.com/yitzchak/archlinux-cl)  - 带有 Common Lisp 实现的 Docker Arch Linux 镜像（7 至今）. 麻省理工学院.


外部函数接口、语言互操作
=============================================

## C ##

* ⭐ [CFFI](https://github.com/cffi/cffi)  - 可移植、易于使用的C外部函数接口.  [外籍人士][14].
  * [cffi-ops](https://github.com/bohonghuang/cffi-ops) - 帮助编写简洁的 CFFI 相关代码.
  * [cffi-objects](https://github.com/bohonghuang/cffi-object) - 能够快速、方便地与外部对象进行互操作.
*[cl-autowrap](https://github.com/rpav/cl-autowrap)  - 自动将头文件解析为 CFFI 定义.  [FreeBSD][39].
* [cl-bindgen](https://github.com/sdilts/cl-bindgen)  - 用于从 C 头文件创建 Common Lisp 语言绑定的命令行工具和库.  [麻省理工学院][200].
* [cl-gobject-introspection](https://github.com/andy128k/cl-gobject-introspection) - [Gobject Introspection](https://gi.readthedocs.io/en/latest/)  FFI. 自动绑定以调用 C 库.  [BSD][15]. 生成一个 Lisp 接口 [gir2cl](https://github.com/kat-co/gir2cl) .  [LGPL3][9].
* [cl-cxx-jit](https://github.com/Islam0mar/CL-CXX-JIT)  - Common Lisp 和 C++ 与 JIT 的互操作.  [麻省理工学院][200].

## Clojure

* [ABCLJ](https://github.com/lsevero/abclj)  - Clojure 与 Common lisp 互操作非常简单.  EPL-2.0.

开发中：

* [Cloture](https://github.com/ruricolist/cloture) - Common Lisp 中的 Clojure.

&gt; Cloture 处于非常早期（pre-alpha）阶段，但它已经进展到足以加载 clojure.test，从而允许测试套件实际上用 Clojure 编写.

另请参阅这些库：

* [cl-oju](https://github.com/eigenhombre/cl-oju/)  - 一些我在编写 Common Lisp 时错过的惯用语，主要与序列有关.  [麻省理工学院][200].
* [clj-con](https://github.com/dtenny/clj-con)  - Common Lisp 中 Clojure 风格的并发操作.  [麻省理工学院][200].
* [clj-re](https://github.com/dtenny/clj-re/) - Clojure 风格的正则表达式函数.

## Erlang ##

* [CLERIC](https://github.com/flambard/CLERIC)  - Common Lisp Erlang 接口.  Erlang 分发协议的实现，与 erl_interface 和 jinterface 相当.  [麻省理工学院][200].

## Java ##

* [cl+j](https://common-lisp.net/project/cl-plus-j/)  - 通过 CFFI 与 JVM 的基于 JNI 的接口. 在 Quicklisp 上不可用. 不能可靠地与所有实现一起工作.  [外籍人士][14].

## Objective-C ##

* [objc-lisp-bridge](https://github.com/fiddlerwoaroof/objc-lisp-bridge)  - 用于与 Objective-C 和 Cocoa 交互的便携式阅读器和桥梁.  [麻省理工学院][200].

## Python ##

* [burgled-batteries](https://github.com/pinterface/burgled-batteries)  - Python 和 Common Lisp 之间的桥梁. 目标是 Lisp 程序可以使用 Python 库. 在 Quicklisp 上不可用.  [麻省理工学院][200].
* [cl4py](https://github.com/marcoheisig/cl4py)  - 库 cl4py（发音为 clappy）允许 Python 程序调用 Common Lisp 库.  [麻省理工学院][200].
* [py4cl](https://github.com/bendudson/py4cl)  - 允许 Common Lisp 代码访问 Python 库的库. 它基本上是 cl4py 的逆过程.  [麻省理工学院][200].
* [py4cl2-cffi](https://github.com/digikar99/py4cl2-cffi) - 基于 CFFI 的 py4cl2 替代方案.
  *“如果有能力，CFFI 方法可以比 py4cl2 快 50 倍.”

也可以看看 [async-process](https://github.com/cxxxr/async-process/).

* [cl-python](https://github.com/metawilm/cl-python)  - Common Lisp 中的 Python 实现.  [LLGPL][8]，未在积极开发中.


## .Net Core

* [Bike](https://github.com/Lovesan/bike)  - 跨平台.Net Core 接口.  [麻省理工学院][200].

## Miscellaneous ##

* [Foil](http://foil.sourceforge.net/)  - 外部对象接口； 与 JVM 和 CLI 一起使用. 在 Quicklisp 上不可用.  [CPL 1.0][47].

对于 Emacs Lisp：

* [CEDAR](https://gitlab.com/sasanidas/cedar)  - 一个先进的交互式开发环境，旨在与 Emacs 兼容，并与其附带的所有功能兼容.  （开发中）
* [CLOCC's elisp.lisp](https://sourceforge.net/p/clocc/hg/ci/default/tree/src/cllib/elisp.lisp) - Common Lisp 中的 Emacs Lisp.
   * 将 Emacs Lisp 语言实现为 Common Lisp 包.  [1999]
   * 不尝试重新实现 Emacs 中提供的函数库来操作缓冲区和其他相关对象，因此它专注于“纯”Emacs Lisp 语言； 但它能够运行 Emacs 日历的非 UI 部分.  （S.莫尼尔，M.斯珀伯）


游戏开发
================

* [Trial](https://github.com/shirakumo/trial)  - Trial 是一个 OpenGL 游戏引擎，非常注重模块化. 它应该提供一个包含有用的零碎内容的大型工具包，您可以从中创建游戏.  [zlib][33].
  * 这 [Kandria](https://kandria.com/) 游戏是通过试用构建的.
* [trivial-gamekit](https://borodust.org/projects/trivial-gamekit/getting-started/)  – 使用这个小框架，您将能够制作简单的 2D 游戏：绘制基本的几何形状、图像和文本、播放声音以及聆听鼠标和键盘输入.  [麻省理工学院][200].
* [virality](https://github.com/bufferswap/ViralityEngine) - 用 Common Lisp 编写的基于组件的游戏引擎 [MIT][200].
* [Xelf](https://gitlab.com/dto/xelf/)  - 可扩展的游戏库. 在 Quicklisp 上不可用.  [GNU LGPL2.1][11].

Utilities:

* [cl-gamepad](https://shirakumo.github.io/cl-gamepad)  - 访问 Windows、Mac OS 和 Linux 上的游戏手柄和操纵杆.  [zlib][33].
* [cl-mpg123](https://shirakumo.github.io/cl-mpg123) 和 [cl-out123](https://shirakumo.github.io/cl-out123), bindings libraries for libmpg123 和 libout123 respectively, giving you fast 和 easy to use mp3 decoding 和 cross-platform audio output. [zlib][33].

Graphics
========

这些是用于处理图形的库，而不是制作 GUI（即小部件工具包），它们有自己的部分.

* ⭐ [Sketch](https://github.com/vydd/sketch)  - 用于创建电子艺术、图形等的 CL 框架.  [麻省理工学院][200].
* [common-cv](https://github.com/byulparan/common-cv)  - CommonLisp 的 OpenCV（开源计算机视觉库）绑定库. 未指定许可证.
* [cl-cairo2](https://github.com/rpav/cl-cairo2)  - 开罗绑定.  [提升1.0][54]
* [cl-gd](http://weitz.de/cl-gd/)  - 提供 GD 图形库接口的库.  [FreeBSD][39].
* [cl-horde3d](https://github.com/anwyn/cl-horde3d/)  - FFI 绑定到 Horde3D 图形库. 在 Quicklisp 上不可用.  [EPL 1.0][59]
* [cl-jpeg](https://github.com/sharplispers/cl-jpeg)  - 基线 JPEG 编码器和解码器库.  [3 条款 BSD][15].
* [cl-liballegro](https://github.com/resttime/cl-liballegro)  - Allegro 5 游戏编程库的接口和绑定.  [zlib][33].
* [cl-opengl](https://github.com/3b/cl-opengl)  - CFFI 绑定到 OpenGL、GLU 和 GLUT API.  [3 条款 BSD][15].
* [cl-sdl2](https://github.com/lispgames/cl-sdl2)  - 使用 C2FFI 绑定 SDL2.  [外籍人士][14].
* [cl-svg](https://github.com/wmannis/cl-svg)  - 用于生成 SVG 文件的基本库.  [外籍人士][14].
* [CLinch](https://github.com/BradWBeer/CLinch)  - 用于 OpenGL 的 Common Lisp 2D/3D 图形引擎.  [FreeBSD][39].
* [donuts](https://github.com/tkych/donuts)  - Common Lisp 的 Graphviz 接口.  [外籍人士][14].
* [dufy](https://github.com/privet-kitty/dufy)  - 各种颜色模型中精确的颜色操作和转换.  [麻省理工学院][200].
* [lispbuilder-sdl](https://github.com/lispbuilder/lispbuilder)  - 一组 SDL 绑定.  [外籍人士][14].
* [lisp-magick-wand](https://github.com/TBRSS/lisp-magick-wand)  - ImageMagick 绑定.  [BSD][15]. 不在 Quicklisp 中.
* [okra](https://www.common-lisp.net/project/okra/manual.html)  - CFFI 与 Ogre 的绑定. 在 Quicklisp 上不可用.  [3 条款 BSD][15].
* [opticl](https://github.com/slyrus/opticl)  - 用于表示和处理图像的库.  [BSD_2 条款][17].
* [Varjo](https://github.com/cbaggers/varjo)  - Lisp 到 GLSL 转换器.  [BSD_2 条款][17].
* [Vecto](http://www.xach.com/lisp/vecto/)  - 简单的矢量绘图库.  [FreeBSD][39].
* [zpng](http://www.xach.com/lisp/zpng/)  - 用于创建 PNG 文件的库.  [FreeBSD][39].
* [pngload-fast](https://git.mfiano.net/mfiano/pngload)  - 便携式 Common Lisp 中的 PNG（便携式网络图形）图像格式解码器，重点是速度.  [麻省理工学院][200].
* [cl-cuda](https://github.com/takagi/cl-cuda)  - 在 Common Lisp 程序中使用 NVIDIA CUDA 的库.  [LLGPL][8].


GUI
===

有关 GUI 工具包的概述和教程，请参阅 [the Cookbook/GUI](https://lispcookbook.github.io/cl-cookbook/gui.html).

* [LispWork's CAPI](http://www.lispworks.com/products/capi.html)  - 便携式 GUI 工具包，具有移动运行时. 专有，但附带免费版本.
* [Allegro's Common Graphics](https://franz.com/products/allegro-common-lisp/acl_gui_tools.lhtml) - 用于为 Windows、Mac 和 Linux 编写窗口化 GUI 的函数库. 专有且有免费版本.
  - 自 Allegro 10.1（2022 年 3 月）起，IDE 和 Common Graphics 工具包 [runs in the browser](https://franz.com/ftp/pri/acl/cgjs/doc.html).
* [Qtools](https://github.com/Shinmera/qtools/)  - 基于 CommonQt 的 Qt 工具包.  [zlib][33] 另外 [Qtools-ui](https://github.com/Shinmera/qtools-ui) （预制 UI 组件）， [videos](https://www.youtube.com/watch?v=KwASFOhYta4&index=7&list=PLkDl6Irujx9Mh3BWdBmt4JtIrwYgihTWp).
* ⭐ [CommonQt](https://github.com/commonqt/commonqt)  - 通过 QtSmoke 绑定 Qt4 的 Common Lisp.  [FreeBSD][39].
  * [CommonQt5](https://github.com/commonqt/commonqt5/) - Qt5 的绑定.
     *警告：目前很难安装. 由 SISCOG 用于生产©.
* ⭐ [ltk](http://www.peter-herth.de/ltk/)  - Tk 工具包的绑定.  [LLGPL][8] 或 [GNU LGPL2.1][11].
  * [LTk Examples](https://peterlane.netlify.app/ltk-examples/) - 为 tkdocs 教程提供 LTk 示例.
  * [LTk Plotchart](https://peterlane.netlify.app/ltk-plotchart/)  - tklib/plotchart 库的包装器，可与 LTk 一起使用. 其中包括 20 多种不同的图表类型（xy 绘图、甘特图、3d 条形图等）.
* [nodgui](https://notabug.org/cage/nodgui)  - Tk 工具包的绑定，基于 Ltk，带有语法糖和附加小部件.  [LLGPL][8].
  * 支持 [tk custom themes](https://wiki.tcl-lang.org/page/List+of+ttk+Themes)， 例如 [ttkthemes](https://ttkthemes.readthedocs.io/en/latest/themes.html) 和 [Forest-ttk-theme](https://github.com/rdbende/Forest-ttk-theme).
* [IUP](https://github.com/lispnik/iup/) - CFFI 绑定到 [IUP](https://www.tecgraf.puc-rio.br/iup/) 可移植用户界面库（ALPHA 之前）.  IUP 是跨平台的（Windows、macOS、GNU/Linux，带有新的 Android、iO、Cocoa 和 Web Assembly 驱动程序），拥有许多小部件，拥有小型 API，并且正在积极开发中.
* [cl-gtk4](https://github.com/bohonghuang/cl-gtk4)  - Common Lisp 的 GTK4/Libadwaita/WebKit 绑定.  [LGPL3][9].
* [cl-cffi-gtk](https://github.com/crategus/cl-cffi-gtk)  - GTK+3 绑定.  [GNU LGPL2.1][11].
  - 教程： [Learn Common Lisp by Example: GTK GUI with SBCL](https://dev.to/goober99/learn-common-lisp-by-example-gtk-gui-with-sbcl-5e5c)
* [cl-gtk2](https://github.com/dmitryvk/cl-gtk2)  - GTK+2 的绑定.  [LLGPL][8].
* [ceramic](https://ceramic.github.io/)  - 使用 Electron 的桌面网络应用程序.  [外籍人士][14].
  * [Electron-lisp-boilerplate](https://github.com/mikelevins/electron-lisp-boilerplate) - 用于构建具有嵌入式 Lisp 辅助进程的 Electron 应用程序的基本样板.
  * 电子应用程序骨架： [electron-sbcl-sqlite](https://github.com/mikelevins/electron-sbcl-sqlite/)
   * 注意：在 Electron 中嵌入 Lisp Web 应用程序的主要思想是将 Lisp Web 服务器作为异步进程启动，并将 Electron 窗口指向本地主机 URL. 就是这样.

但这还不是全部：

* [CocoaInterface](https://github.com/plkrueger/CocoaInterface/) -
 Clozure Common Lisp 的 Cocoa 接口. 构建 Cocoa 用户界面
Windows 动态使用 Lisp 代码并绕过典型的 Xcode
流程. 它有
[good documentation and a tutorial](https://github.com/plkrueger/CocoaInterface/blob/master/Documentation/UserInterfaceTutorial.pdf).
* [McCLIM](https://common-lisp.net/project/mcclim/)  - Common Lisp Interface Manager 版本 II 的实现.  [GNU LGPL2.1][11].
* [cl-webkit](https://github.com/joachifm/cl-webkit)  - 与 WebKitGTK+ 的绑定. 还为应用程序添加了 Web 浏览功能，充分利用 WebKit 浏览引擎的功能.  [麻省理工学院][200].
* [ftw](https://github.com/fjames86/ftw)  - Win32 GUI 库.  [麻省理工学院][200].
* [eql, eql5, eql5-android](https://gitlab.com/eql)  - 嵌入式Qt4和Qt5 Lisp，嵌入ECL，可嵌入Qt. 将 EQL5 移植到 Android 平台.  [麻省理工学院][200].
* [bodge-nuklear](https://github.com/borodust/bodge-nuklear) - 包装在 [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear) 立即模式 GUI 库.  [麻省理工学院][200].
* [vk](https://github.com/JolifantoBambla/vk)  - Vulkan API 的通用 Lisp/CFFI 绑定.  [麻省理工学院][200].

其他实用程序：

* [file-select](https://github.com/Shinmera/file-select)  - 用于调用本机系统文件对话框来选择或创建文件的库. 兹利布.

另请参阅此 [demo to use Java Swing from ABCL](https://github.com/defunkydrummer/abcl-jazz).

Mobile
------

* [LispWork's mobile runtime](http://www.lispworks.com/products/lw4mr.html)  - Android 和 iO. 所有权.
* [LQML](https://gitlab.com/eql/lqml)  - 与源自 EQL5 的 QML（Qt5 和 Qt6）的轻量级 ECL 绑定.  LGPL 和公共领域.

另请参阅下面的 MOCL，CL 作为移动设备（iOS、Android 和 OSX）的库，以及 [hello-allien](https://github.com/Gleefre/hello-alien/)，为 Android 应用程序构建的 SBCL（非常新，2023 年）.


Implementations
===============

* ⭐ [SBCL](http://www.sbcl.org/index.html)  - 钢铁银行 Common Lisp.  CMUCL 的一个分叉； 编译为高效的机器代码.  [标准符合性][13]. 公共领域，某些部分位于 [Expat][14] 和 [3-clause BSD][15] 下.
  * 也可以看看： [sbcl-librarian](https://github.com/quil-lang/sbcl-librarian)  - SBCL 的动态库交付工具. 创建可以从 C 或 Python 调用的共享库. 麻省理工学院. [Blog post](https://mstmetent.blogspot.com/2022/04/using-lisp-libraries-from-other.html). [Full example](https://github.com/quil-lang/sbcl-librarian/tree/main/example).
  * [SBCL-GOODIES](https://github.com/sionescu/sbcl-goodies) - 使用 Common Lisp 和外部库分发二进制文件：libssl、libcrypto 和 libfixposix 是静态烘焙的.[MIT][200].
* ⭐ [CCL](https://github.com/CodyReichert/awesome-cl/blob/master///ccl.clozure.com/) - Clozure Common Lisp; compiler-only implementation, generates native code.  [LLGPL][8].
* [ECL](https://common-lisp.net/project/ecl/)  - 可嵌入的 Common Lisp； 编译为 C.[GNU LGPL2.1][11].
* [ABCL](https://common-lisp.net/project/armedbear/)  - 武装熊 Common Lisp； 以 JVM 为目标，编译为字节码.  [标准一致性][4].  [GNU GPL3][2] 和 [类路径例外][3].
* [CLASP](https://github.com/drmeister/clasp)  - 一种新的 Common Lisp 实现，可与使用 LLVM 编译为本机代码的 C++ 库和程序无缝互操作. 这使得 Clasp 能够利用大量现有的库和程序，例如科学计算生态系统之外的库和程序.  [LGPL2.1][11]（及其他）.

Proprietary:

* [LispWorks](http://www.lispworks.com/) - Common Lisp 的集成跨平台开发工具.
  * 著名的功能包括：CAPI 跨平台和本机 GUI 工具包、LispWorks IDE、移动平台运行时（iO、Android）、Java 接口、用于构建更轻量级二进制文件的摇树机、用于“基于规则、面向对象、逻辑、函数和数据库编程”等等.
  * 有免费版本，有限制（堆大小限制、时间限制）.
* [Allegro CL](https://franz.com/products/allegro-common-lisp/) - 提供完整的 ANSI Common Lisp 标准和许多扩展.
  * 著名的功能包括：AllegroCache 对象持久数据库系统、KnowledgeGraph 系统、并发垃圾收集器、基于 Web 的 IDE 等等.
   * 有免费版本. 它包括 AllegroCache，但有大小限制.
* [MOCL](https://wukix.com/mocl) - CL 作为移动设备（iOS 和 Android）和 OSX 的库.

其他实现，主要用于历史目的：

* [CMUCL](https://github.com/CodyReichert/awesome-cl/blob/master///www.cons.org/cmucl/)  - 卡内基梅隆大学的实施. 公共区域.  SBCL 是 CMUCL 的一个分支.
* [GNU CLISP](http://www.clisp.org/)  - GNU 实现； 包含一个编译器和一个解释器.  [标准一致性][6].  [GNU GPL3][2]. 他们开发 [on Gitlab](https://gitlab.com/gnu-clisp/clisp).
  * 编译为字节码，其默认 REPL 比 SBCL 更用户友好（具有符号完成和 readline 集成）.
  * 然而，它的开发并不积极，它不完全符合 ANSI 标准，它的性能低于 SBCL，并且缺乏兼容性功能.
* [Corman Lisp](https://github.com/sharplispers/cormanlisp)  - 用于在 Intel 平台上运行的 Microsoft Windows 的 Common Lisp 开发环境.  [麻省理工学院][200].

您可以在此处检查实现与常见扩展的兼容性： [portability.cl](https://portability.cl).

JSON
====

* [jzon](https://github.com/Zulu-Inuoe/jzon/)  - 一个正确、安全、快速的 JSON 解析器.  [麻省理工学院][200].
  * jzon 是唯一一个 CL JSON 库，它可以正确拒绝每个官方 JSON 测试套件的所有无效输入，并接受每个该套件的所有有效输入.
  * 它不会因无效输入而崩溃（jsown），不会因大型数据集而阻塞（Jonathan）等等.
  * v1.0 于 2023 年 2 月在 Quicklisp 发行版发布.
  * “我相信 jzon 是更好的选择，并希望它一劳永逸地成为 JSON-in-CL 领域新的、真正的事实上的库.”
* [jonathan](https://github.com/Rudolph-Miller/jonathan)  - JSON 编码器和解码器.  [麻省理工学院][200].
* [cl-json](https://github.com/sharplispers/cl-json)  - 高度可定制的 JSON 编码器和解码器.  [麻省理工学院][14].
* [jsown](https://github.com/madnificent/jsown)  - JSON 格式的读取器和写入器.  [外籍人士][14].
* [shasht](https://github.com/yitzchak/shasht)  - 用于 Kzinti 的 Common Lisp JSON 读写.  [麻省理工学院][14].
   - “Shasht 是我特别喜欢的两个新库之一，并且已经在 Quicklisp 中.它速度快，正确处理 null，对 CLOS 对象、结构和哈希表进行编码.它还可以进行增量编码.” 萨布拉·克罗尔顿.

看到这个 [extensive comparison](https://sabracrolleton.github.io/json-review) JSON 库.

JSON 工具：

* [json-mop](https://github.com/gschjetne/json-mop)  - 用于桥接 CLOS 和 JSON 对象的元类.  [麻省理工学院][200].
* [cl-json-pointer](https://github.com/y2q-actionman/cl-json-pointer)  - JSON 指针实现.  [麻省理工学院][200].
* [cl-jwk](https://github.com/dnaeon/cl-jwk)  - 用于解码公共 JSON Web 密钥 (JWK) 的 Common Lisp 系统.  BSD 许可证.


YAML
====

* [cl-yacclyaml](https://github.com/mabragor/cl-yaclyaml)  - 一个纯 lisp YAML 处理器（加载器，但还不是转储器）.  [GPL3][2].
* [cl-yaml](https://github.com/eudoxia0/cl-yaml.git)  - 基于 libyaml 构建的 YAML 解析器和发射器.  [麻省理工学院][200].


语言扩展
===================

* ⭐ [alexandria](https://common-lisp.net/project/alexandria/)  - 通用实用程序库. 公共区域.
* [serapeum](https://github.com/TBRSS/serapeum/)  - 另一个通用实用程序库.  [外籍人士][14].
* [rutils](https://github.com/vseloved/rutils)  - Common Lisp 的激进而合理的语法实用程序.  [麻省理工学院][200].
* [generic-cl](https://github.com/alex-gutev/generic-cl/)  - 标准 Common Lisp 函数的通用函数接口（相等、比较、算术、对象、迭代器、序列……）.  [麻省理工学院][200]. 另请参阅更轻量级 [generic-comparability](https://github.com/pnathan/generic-comparability) .  [LLGPL][8].
* [anaphora](https://common-lisp.net/project/anaphora/)  - 照应宏的集合. 公共区域.
* ⭐ [trivia](https://github.com/guicho271828/trivia/)  - 优化的模式匹配库.  [LLGPL][8].
* [arrow-macros](https://github.com/hipeta/arrow-macros)  - 类似 Clojure 的线程宏.  [麻省理工学院][200].
* [hu.dwim.walker](https://github.com/hu-dwim/hu.dwim.walker)  - 代码解析器和解析器（又名 AST 解析器和解析器）.  [BSD][15]. 也可以看看 [this blog post](http://40ants.com/lisp-project-of-the-day/2020/04/0044-hu.dwim.walker.html).

可移植层
------------------

这里收集了大量的可移植层： [portability.cl/](https://portability.cl/) . 这里是其中的一些：

* [trivial-arguments](https://github.com/Shinmera/trivial-arguments)  - 用于检索函数参数列表的可移植库.  [zlib][33].
* [definitions](https://github.com/Shinmera/definitions)  - 通用定义内省库. 它使您能够检索与指示符（例如符号、包和名称）关联的定义或绑定.  [zlib][33].
* [dissect](https://shinmera.github.io/dissect)  - 当许多项目使用“trivial-backtrace”系统时，该系统只是为它们提供一个带有回溯的字符串，Dissect 允许您捕获、单步执行和完全检查各种 Lisp 实现上的堆栈跟踪. 对于日志记录和其他自动继续执行的情况也非常有用，但当前堆栈的信息对于存储在某处仍然有用.  [zlib][33].

更改语法
-------------------

* [cl21](https://github.com/cl21/cl21)  - 一个将 Common Lisp 推进到 21 世纪的实验项目.  [外籍人士][14].
* [clamp](https://github.com/malisper/Clamp)  - Arc 语言相对于 Common Lisp 来说简洁明了.  [艺术许可2.0][51].
  * 还 [arc-compat](https://github.com/g000001/arc-compat)  - 电弧兼容封装.  Perl 基金会的艺术许可证 2.0.
* [cl-syntax](https://github.com/m2ym/cl-syntax)  - 阅读器语法约定.  [LLGPL][8].
* [cl-2dsyntax](http://www.cliki.net/cl-2dsyntax)  - 缩进敏感的阅读器系统. 在 Quicklisp 上不可用. 公共区域.
* [cl-annot](https://github.com/m2ym/cl-annot)  - Common Lisp 的类似 Python 的注释.  [LLGPL][8].
  * [cl-annot-revisit](https://github.com/y2q-actionman/cl-annot-revisit/)  - 重新实施 cl-annot.  WTFPL.
* [cl-reader](https://github.com/digikar99/reader) - 实用程序库
旨在为 lambda、映射、访问器提供读取器宏，
哈希表和哈希集.  [麻省理工学院][200].

对于字符串：

* ⭐ [cl-interpol](https://github.com/edicl/cl-interpol/)  - 一组读取器修改以允许字符串插值.  [BSD][15].
* [mstrings](https://git.sr.ht/~shunter/mstrings)  - 一个阅读器宏，提供视觉上吸引人的多行块.  M 字符串会修剪前导空格、将行连接在一起等.[BSD_3Clause][15].
* [pythonic-string-reader](https://github.com/smithzvk/pythonic-string-reader)  - 受 Python 的三引号字符串启发的简单且不显眼的读取表修改.  [BSD_3 条款][15].
* [cl-heredoc](https://github.com/outergod/cl-heredoc) - A ["heredocs"](https://github.com/outergod/cl-heredoc) dispatcher. [GPL3][2]. Allows to write: `#>eof>Write whatever (you) "want", no matter what characters, until the magic end sequence has been reached.eof`


CLOS 扩展
---------------

* ⭐ [closer-mop](http://cliki.net/closer-mop)  - 一个兼容层，可纠正许多缺失或不正确的 MOP 功能.  [外籍人士][14].
* [defclass-std](https://github.com/EuAndreh/defclass-std)  - 用于快速编写 DEFCLASS 表单的快捷宏.  [LLGPL][8].
* [specialization-store](https://github.com/markcox80/specialization-store/)  - 基于类型的通用函数. 简化的 BSD 许可证变体.
* [filtered-functions](https://github.com/pcostanza/filtered-functions)  - 允许使用任意谓词来选择和应用方法.  [麻省理工学院][200].
* [inlined-generic-function](https://github.com/guicho271828/inlined-generic-function) -
将静态调度的速度提升至 CLOS.  [LLGPL][8].
* [static-dispatch](https://github.com/alex-gutev/static-dispatch)  - 允许静态（在编译时）而不是动态（运行时）执行标准通用函数调度. 这类似于 C++ 和 Java 等语言中所谓的“重载”.  [麻省理工学院][200].
* [dynamic-mixins](https://github.com/rpav/dynamic-mixins)  - 简单、动态的类组合.  [BSD_2 条款][17].
* [fast-generic-functions](https://github.com/marcoheisig/fast-generic-functions)  - 密封您的通用函数以进一步提高性能.  [麻省理工学院][200].
* [polymorphic functions](https://github.com/digikar99/polymorphic-functions)  - 用于分派类型而不是类的函数类型，部分支持分派可选和关键字参数类型. 仍处于实验阶段（2021 年 5 月）.  [麻省理工学院][200].
   - 多态函数根据提供给它的参数类型进行分派. 这有助于在专用数组和用户定义类型上进行分派.
  - for differences with specialization-store and fast-generic-functions, see its README.

并且：

* [slot-extra-options](https://github.com/some-mthfka/slot-extra-options)  - 允许您构建一个元类，该元类又允许您在其类中指定额外的插槽选项.  [LGPL3][9].

功能扩展
-------------------

* [cl-hooks](https://github.com/scymtym/architecture.hooks/)  - Hooks 扩展点机制（如已知的，例如来自 GNU Emacs）.  LGPL.
* [method-hooks](https://gitlab.com/Gnuxie/method-hooks)  - 当 CLOS 方法组合只允许每个方法有一个钩子时，该库允许任意数量的钩子.  Mozilla 公共许可证.
* [cl-advice](https://github.com/lisp-mirror/budden-tools/blob/213ab2b52a1b0c0b496efd30c3b5143f5c8e1ff2/cl-advice/README.md)  - SBCL、CCL、LispWorks 和 Allegro 的可移植层建议库的尝试. 不在 Quicklisp 中.
* [nhooks](https://github.com/atlas-engineer/nhooks) - 增强了钩子（扩展点）的实现，并进行了重大改进.

Iteration
---------

* ⭐ [iterate](https://common-lisp.net/project/iterate/)  - Common Lisp 的迭代构造，可扩展且 Lispier.  [麻省理工学院][200].
* [for](https://shinmera.github.io/for/)  - 简洁、口齿不清且可扩展的迭代宏. 与循环不同，它是可扩展且合理的，并且与迭代不同，它不需要代码遍历并且更容易扩展.  [zlib][33].
* [series](https://series.sourceforge.net/)  - 函数式风格，完全没有任何运行时间损失.  [麻省理工学院][200].
* [trivial-do](https://github.com/yitzchak/trivial-do/)  - Common Lisp 的附加 dolist 风格宏.  [麻省理工学院][200].
* [doplus](https://github.com/alessiostalla/doplus) – 另一个可扩展的迭代库，类似于 :for.
* [cl-transducers](https://github.com/fosskers/cl-transducers)  - 符合人体工程学、高效的数据处理.  [AGPL-3.0][51].
  *“传感器是一种符合人体工程学且极其节省内存的数据源处理方式.这里的“数据源”指的是列表或向量等简单集合，但也可能是大文件或无限数据生成器.”
  *“总的来说，这是 Transducer 模式最完整的实现.”
  * 一个“现代”API，带有`map`、`filter`、`take`、`repeat`、`cycle`、`fold`…
* [snakes](https://github.com/BnMcGn/snakes)  - Common Lisp 的 Python 风格生成器. 包括 itertools 的端口.  [阿帕奇2][89].
* [picl](https://github.com/anlsh/picl)  - Python 的 itertools 包的（几乎）完整移植，在适用的情况下完成了惰性，并且不依赖于 cl-cont.  [麻省理工学院][200].
* [gtwiwtg](https://cicadas.surf/cgit/colin/gtwiwtg.git/about/)  - 一个惰性序列库. 与“系列”类似，但不那么完整. 然而，它有一个“现代”API，其中包含“take”、“filter”、“for”、“fold”等易于使用的内容.
* [gmap](https://github.com/slburson/misc-extensions/blob/master/src/gmap.lisp)  - 一个简洁且可扩展的迭代工具，具有与 FSet 良好集成的优点（请参阅数据结构部分），因为它是由同一作者编写的. 在 Quicklisp 中作为“misc-extensions”的一部分. 公共区域.


Lambda 简写
-----------------

* [fn](https://github.com/cbaggers/fn)  - 几个 lambda 速记宏.  `(fn* (+ _ _)) --&gt; (lambda (_) (+ _ _))`. 公共区域.
* [f-underscore](https://gitlab.common-lisp.net/bpm/f-underscore)  - 一个小型的函数式编程实用程序库.  `(f_ (+ _ _)) -&gt; (lambda (_) (+ _ _))`. 公共区域.
* [cl-punch](https://github.com/windymelt/cl-punch/)  - 类似 Scala 的匿名 lambda 文字.  `(mapcar ^(* 2 _) &#39;(1 2 3 4 5))`.  [麻省理工学院][200].


另请参见 CL21 和 [Rutils](https://github.com/vseloved/rutils).


非确定性逻辑编程
------------------------------------

* [cl-prolog2](https://github.com/guicho271828/cl-prolog2)  - Common Lisp 到 ISO Prolog 实现的通用接口.  [麻省理工学院][200].
* [Screamer](https://github.com/nikodemus/screamer) - 增强通用性
  Lisp 几乎具有 Prolog 和 Prolog 的所有功能
  constraint logic programming
  语言. [Blog post](https://chriskohlhepp.wordpress.com/reasoning-systems/specification-driven-programming-in-common-lisp/)
  解决欧拉计划难题.  [麻省理工学院][200].
* [Screamer+](https://github.com/yakovzaytsev/screamer-plus) - increasing the expressiveness of SCREAMER. [MIT][200].
* [Temperance](https://github.com/sjl/temperance)  - 逻辑编程.  [麻省理工学院][200]. 注重性能，考虑一般游戏玩法.

反应式编程
--------------------

* [Cells](https://github.com/kennytilton/cells)  - 数据流编程范式的实现，CLOS 的反应式电子表格表达能力. 用于构建一个 [algebra learning system](http://tiltontec.com/) . 和 [documentation](https://github.com/stefano/cells-doc/) .  Lisp LGPL.
* [lwcells](https://github.com/kchanqvq/lwcells) - 轻质电池.
   * LWCELLS 是 Common Lisp 的数据流扩展. 它根据指定细胞关系的函数维持细胞的一致状态.  LWCELLS 的设计简单、干净、组合且灵活.

合约编程
--------------------

* [quid-pro-quo](https://github.com/sellout/quid-pro-quo) - 合同
   Eiffel 的 Design by Contract™ 风格的编程库. 公共区域.

Typing
------

* [Coalton](https://github.com/coalton-lang/coalton/)  - 一种高效、静态类型的函数式编程语言，可增强 Common Lisp 的性能.  [麻省理工学院][200].
* [trivial-types](https://github.com/m2ym/trivial-types)  - 提供缺失但重要的类型定义，例如“proper-list”、“association-list”、“property-list”和“tuple”.  [LLGPL][8].
* [defstar](https://bitbucket.org/eeeickythump/defstar/src/master/)  - 宏集合，用于轻松包含 lambda 列表中参数的类型声明.  [GNU GPL3][2]

也可以看看：

* [typo](https://github.com/marcoheisig/Typo/)  - Common Lisp 的可移植类型推理库.  [麻省理工学院][200].

定理证明者
-------------------

* [ACL2](https://www.cs.utexas.edu/users/moore/acl2/) - 一种逻辑和编程语言，您可以在其中对计算机系统进行建模，以及帮助您证明这些模型的属性的工具.
  * 自 20 世纪 90 年代起在业界使用.
  * 它支持 ANSI 标准 Common Lisp 编程语言的子集.
   * “经常使用 ACL2 的公司包括 AMD、Centaur Technology、IBM、Intel、Kestrel Institute、Motorola/Freescale、Oracle 和 Rockwell Collins.”  （[source](https://royalsocietypublishing.org/doi/10.1098/rsta.2015.0399))
  * [Proofpad](https://github.com/calebegg/proof-pad/)，ACL2 的在线 IDE.


学习和教程
=====================

## Online ##

Beginner
--------

* [Learn X in Y minutes - Where X = Common Lisp](https://learnxinyminutes.com/docs/common-lisp/) - 涵盖要点的 Common Lisp 小型教程.
* [Lisp Koans][201] - 该项目引导学习者逐步了解许多 Common Lisp 语言功能.
 * [Practical Common Lisp][206] - 很好的 Common Lisp 介绍性文本，带有实际示例. 更好地阅读 [a Firefox add-on](https://github.com/vale981/practical-cl-beautified).
* [Common LISP: A Gentle Introduction to Symbolic Computation](http://www.cs.cmu.edu/afs/cs.cmu.edu/user/dst/www/LispBook/index.html) - 很好的语言介绍.
* [Successful Lisp](http://successful-lisp.blogspot.com/) - 对于具有一定编程背景的初学者来说是一本好书.
* [Lisp Quickstart](https://cs.gmu.edu/~sean/lisp/LispTutorial.html) - 快速入门和编写 Common Lisp 代码的好教程.
* [Casting SPELs in LISP](http://www.lisperati.com/casting.html) - 边看漫画书边学习 LISP 的有趣方式.
   &gt; 感谢您支持我在 Udemy 上的工作. 另请注意，我会不时发布免费优惠券，并且 Udemy 经常提出大幅促销，但您也可以向我索取免费优惠券.

Intermediate
------------

* [The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/)
* [Lisp Tips](https://github.com/lisp-tips/lisp-tips/issues/)  - 包含有用提示和技巧的博客. 的延续 [Common Lisp tips](http://lisptips.com/).
* [Lisp project of the day](http://40ants.com/lisp-project-of-the-day/) - 展示许多 Lisp 库的博客.

Advanced
--------

 * [Let Over Lambda][156] - 一本关于高级宏观技术的书. 前六章可在​​线获取.
* [On Lisp](http://www.paulgraham.com/onlisp.html) - Paul Graham 关于 Lisp 宏（以及其他有趣的东西）的精彩书籍.
* [Programming Algorithms in Lisp](https://link.springer.com/book/10.1007/978-1-4842-6428-7) - 更新版本“[Programming Algorithms](https://leanpub.com/progalgs)”; 使用 Lisp 中的数据结构和算法编写高效程序的综合指南.

编码平台
----------------

* [Codewars](https://docs.codewars.com/languages/commonlisp/) - 一个代码培训平台，具有 Common Lisp 支持 (SBCL).

Web开发
--------

* [Lisp for the Web](https://leanpub.com/lispweb) - 这本书将引导您构建三层投票 Web 应用程序.
* [Lisp Web Tales](https://leanpub.com/lispwebtales) - 简单的教程使用 [hunchentoot](http://edicl.github.io/hunchentoot/), [cl-redis](https://github.com/vseloved/cl-redis), [restas](https://github.com/archimag/restas), [SEXML](https://github.com/madnificent/SEXML), [Postmodern](https://github.com/marijnh/Postmodern), and more.
* [Section on Web Development in The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/web.html) - 介绍性教程，涵盖 Web 服务器设置、路由、weblocks、模板、错误处理、打包、热重载、数据库连接和部署，以及当前 Lisp Web 开发生态系统中的其他主题.

Reference
---------

* 新的！ [CL CommunitySpec](https://cl-community-spec.github.io/pages/index.html) - Common Lisp ANSI 规范草案的演绎版.
   * 具有交互式搜索、语法高亮！ 并且开源.
* 新的！ [novaspec](https://novaspec.org/) - CL ANSI 草案的现代版本.
  * 不是开源的？

* [Common Lisp Quick Reference](http://clqr.boundp.org/index.html)  - ANSI CL 规范的精炼袖珍版本. 可供下载 PDF 版本.
* [CLHS](http://www.lispworks.com/documentation/lw50/CLHS/Front/index.htm)  - Common Lisp HyperSpec； 超文本形式的 ANSI CL 标准.
* [CLOS MOP specification](https://clos-mop.hexstreamsoft.com/) - 《元对象协议的艺术》第 5 章和第 6 章的现代公共领域在线版本
* [Common Lisp Standard Draft (pdf)](https://franz.com/support/documentation/cl-ansi-standard-draft-w-sidebar.pdf) - Common Lisp 规范的标准草案，格式良好，带有侧边栏的 PDF.
* [Common Lisp the Language](http://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html) - ANSI 规范之前的 Common Lisp 原始标准.
* [Minispec](https://lamberta.github.io/minispec/)  - CLHS 的更友好但不太完整的版本. 还包含一些常用 CL 库（例如 Alexandria）的文档.
* [Simplified Common Lisp reference](http://jtra.cz/stuff/lisp/sclr/index.html) - CLHS 的简化版本.
* [CDR](https://cdr.common-lisp.dev/)  - Common Lisp 文档存储库.  Common Lisp 社区感兴趣的文档存储库.  CDR 文档最重要的属性是它永远不会改变：如果您引用它，您可以确保您的引用将始终引用完全相同的文档.
  - Common Lisp 文档存储库托管于 [Zenodo](https://zenodo.org/communities/cdr/).

## Offline ##

CLHS 可通过以下方式离线使用 [archive](https://github.com/CodyReichert/awesome-cl/blob/master/ftp://ftp.lispworks.com/pub/software_tools/reference/HyperSpec-7-0.tar.gz) 正如文档所示 [Dash](https://kapeli.com/dash), [Zeal](https://zealdocs.org/) 和 [Velocity](https://velocity.silverlakesoftware.com/).

Beginner
--------

* [Land of Lisp](http://landoflisp.com/) - 有趣的、面向游戏的 Common Lisp 介绍.
* [Practical Common Lisp][206] - 很好的 Common Lisp 介绍性文本，带有实际示例.

Intermediate
------------

* [ANSI Common Lisp](http://www.paulgraham.com/acl.html)  - 全面、实用地涵盖整个语言，并附有练习. 由于[一些注意事项][20]，不建议将其作为起始文本.
* [Common Lisp Recipes](http://weitz.de/cl-recipes/)  - **Common Lisp Recipes** 是您在使用 Common Lisp 编写实际应用程序时可能遇到的问题的解决方案和答案的集合.  2015 年出版.

Advanced
--------

 * [Let Over Lambda][156] - 一本关于高级宏观技术的书. 所有八章均可在印刷版中找到.
* [Common Lisp 中的面向对象编程：CLOS 程序员指南][21] - 一本关于 CLOS 的古老但非常详尽的书.
* [人工智能编程范式：Common Lisp 案例研究][157] - 一本关于人工智能编程的书，涵盖了一些高级 Lisp.
  * 网页版： [https://norvig.github.io/paip-lisp/](https://norvig.github.io/paip-lisp/#/)

其他书籍
-----------

* [Building Problem Solvers](https://www.qrg.northwestern.edu/bps/readme.html) ([PDF](http://www.qrg.northwestern.edu/bps/BPS-Searchable.pdf)）由 Ken Forbus 和 Johan de Kleer 撰写，由麻省理工学院出版社免费提供 - 这是标准人工智能文本中的一本独特的书，结合了科学与工程、理论和工艺来描述人工智能推理系统的构建，并包括说明想法的代码.

Community
---------

* [/r/Common_Lisp](https://www.reddit.com/r/Common_Lisp/) - 关于 Common Lisp 的 Reddit 子版块
* [/r/learnlisp](https://www.reddit.com/r/learnlisp/) - 一个用于提问和获取有关 Lisp 的帮助的 Reddit 子版块
* [common-lisp.net](https://common-lisp.net)
* [lisp-lang.org](https://lisp-lang.org/)
* [Lisp Discord Server](https://discord.gg/hhk46CE)
* [#commonlisp](https://irclog.tymoon.eu/libera/%23commonlisp) 在 Libera Chat - 主要 Common Lisp IRC 频道上.
* [#lisp](https://irclog.tymoon.eu/libera/%23lisp) Libera Chat - 所有 Lisp 方言的 IRC 频道.
* #clschool on Libera Chat - IRC channel for learning Common Lisp.
* #lispcafe on Libera Chat - IRC channel for off-topic discussions.
* [Common Lisp chat](https://chat.hexstreamsoft.com/) - 具有明确定义的规则和保留策略的密钥库团队.

图书馆经理
===============

 * ⭐ [Quicklisp][16] - 包含许多库的库管理器，具有轻松的依赖关系管理.  [外籍人士][14].
  * [ql-https](https://github.com/rudolfochrist/ql-https) - 默认情况下，shell 为 cURL 并使用 HTTPS.
  * [Quicklisp bundles](https://quicklisp.org/beta/bundles.html) - 从 Quicklisp 导出并可加载的独立系统集，无需涉及 Quicklisp.
* [CLPM](https://www.clpm.dev)  - Common Lisp 的包管理器，致力于将包管理器进程本身与使用它的客户端映像完全分离.  [BSD_2 条款][17].
  * CLPM 作为预构建的二进制文件提供，默认支持 HTTPS，支持安装多个软件包版本，支持版本化系统等等.
* [Ultralisp](http://ultralisp.org/)  - 一种 Quicklisp 发行版，每 5 分钟更新一次，并且可以一键添加他的项目.  [BSD][15].
*[Roswell](https://github.com/roswell/roswell)  - Lisp 实现安装程序、脚本启动程序等.  [麻省理工学院][200].
* [Qlot](https://github.com/fukamachi/qlot)  - 项目本地库安装程序，类似于 Bundler 或 Virtualenv.  [外籍人士][14].
  * 如何 [use it from the Lisp REPL](https://github.com/svetlyak40wt/qlot-without-roswell) 没有罗斯威尔.
* [Quicksys](https://lisp.com.br/quicksys/)  - 从多个 Quicklisp 发行版安装系统.  [麻省理工学院][200].
* [Quickutil](https://github.com/stylewarning/quickutil) - A utility manager, similar to Quicklisp, but for small utilities rather than whole libraries. [3-clause BSD][15].

也可以看看：

*（新！截至 2023 年 5 月） [ocicl](https://github.com/ocicl/ocicl)  - Quicklisp 的新的实验性替代方案，基于容器世界的工具构建.  [麻省理工学院][200].

可能有帮助：

* [redist](https://github.com/shirakumo/redist) - 生成 Quicklisp 发行版的设施.
* [quick-patch](https://github.com/tdrhq/quick-patch/)  - 无需使用 git 子模块即可轻松覆盖 Quicklisp 项目.  MPL-2.0.
* [print-licenses](https://github.com/vindarel/print-licenses)  - 打印项目及其依赖项使用的许可证.  [麻省理工学院][200].
* [asdf-dependency-graph](https://github.com/digikar99/asdf-dependency-graph/) - 围绕“dot”的最小包装器，用于生成依赖关系图的图像.

### Interfaces to other package managers

* [linux-packaging](https://gitlab.com/ralt/linux-packaging)  - 使用单个 ASDF 声明为您的应用程序构建 .deb、.rpm 或 .pkg 包. 在后台使用 fpm.  [麻省理工学院][200].
* [qldeb](https://github.com/ralt/qldeb) - Quicklisp 系统到 debian 软件包，以及 [deb-packager](https://github.com/ralt/deb-packager) （只需通过定义 s-表达式来创建 debian 包）和介绍性 [blog post](http://margaine.com/2015/12/22/quicklisp-packagecloud-debian-packages.html) . 两者都是[麻省理工学院][200].
* [ql-to-deb](https://github.com/dimitri/ql-to-deb)  - 从 Quicklisp 版本更新 cl-* debian 软件包.  WTFPL.
* [dh-quicklisp-buildapp](https://github.com/ralt/dh-quicklisp-buildapp)  - debhelper 实用程序可让您几乎毫不费力地将基于 Quicklisp 的 Common Lisp 代码编译为 .deb 中的 buildapp 二进制文件.  [麻省理工学院][200].
* [cl-brewer](https://github.com/can3p/cl-brewer)  - 用于（命令行）common lisp 应用程序的自制公式生成器. 公共区域.
* [flatpack-common-lisp](https://gitlab.com/ralph-schleicher/flatpak-common-lisp) - BuildStream 项目，用于为 Common Lisp 应用程序构建基于 Flatpak 的运行时环境.
* [alien-works-delivery](https://github.com/borodust/alien-works-delivery)  - 用于将 Common Lisp 应用程序作为可执行包提供的 WIP 系统. 目前，它仅支持 Linux 的 AppImage 格式和 Windows 的 MSIX 格式，但也计划支持 Android 的 .APK 以及更高版本的 MacOSX 和 iOS 捆绑包格式.


也可以看看 [asdf-sbcl](https://github.com/smashedtoatoms/asdf-sbcl)，通用包管理器的插件.


机器学习
================

* [MGL](https://github.com/melisgl/mgl)  - 用于反向传播神经网络、玻尔兹曼机、高斯过程等的机器学习库.  [麻省理工学院][200].
  * 一些部分最初由 Ravenpack International 提供.
  * 由其使用 [author](https://github.com/melisgl) 到 [win](https://github.com/melisgl/higgsml) 希格斯玻色子机器学习挑战.
  * 更多关于作者的信息：他还获得了 Google [AI Challenge](https://en.wikipedia.org/wiki/AI_Challenge)  2010 年使用 Common Lisp，但没有使用 MGL，因为不需要机器学习.  A [related talk](https://www.youtube.com/watch?v=7sgERtZkycU) (59', 2013).
* [clml](https://github.com/mmaul/clml)  - 最初由日本公司 Mathematicl Systems Inc. 开发. 与一个 [tutorial](https://mmaul.github.io/clml.tutorials//2015/08/08/CLML-Time-Series-Part-1.html) .  [LLGPL][8].
* [antik](https://www.common-lisp.net/project/antik/)  - Common Lisp 中科学和工程计算的基础. 通用公共许可证. 还 [mgl-mat](https://github.com/melisgl/mgl-mat) 和 [LLA](https://github.com/tpapp/lla).

图片来源：borretti.me [State of CL Ecosystem 2015](http://borretti.me/article/common-lisp-sotu-2015#machine-learning).


自然语言处理
===========================

* [sparser](https://github.com/ddmcdonald/sparser)  - 英语自然语言理解系统.  [日食][209].
   *&gt; 模型驱动、基于规则的语言文本分析系统，用于大容量、高精度信息提取. 从本质上讲，Sparser 是一个自下而上、基于短语结构的图表解析器，针对语义语法和部分解析进行了优化.
* [cl-nlp](https://github.com/vseloved/cl-nlp)  - 自然语言处理工具集.  [Apache2.0][89].
* [babel2](https://github.com/lucas8/Babel2/) - 流体构造语法实现、计算框架和基于统一的语法形式[Apache2.0][89].



网络和互联网
====================

See [Cliki](http://www.cliki.net/Web) 了解更多.

HTTP 客户端
------------
* [Dexador](https://github.com/fukamachi/dexador)  - 一个 HTTP 客户端，旨在取代 Drakma.  [麻省理工学院][200].
* [Carrier](https://github.com/orthecreedence/carrier)  - 构建在 cl-async 和 fast-http 之上的轻量级异步 HTTP 客户端.  [麻省理工学院][200].
* [fast-http](https://github.com/fukamachi/fast-http)  - Common Lisp 的快速 HTTP 请求/响应解析器.  [麻省理工学院][200].
* [http2](https://github.com/zellerin/http2/)  - Common Lisp 中的 HTTP/2 实现.  [麻省理工学院][200].


HTTP 服务器
------------

* ⭐ [Hunchentoot](http://weitz.de/hunchentoot/)  - 网络服务器.  [2 条款 BSD][207]
*[Clack](https://github.com/fukamachi/clack)  - 受 Rack 和 WSGI 启发的 Web 应用程序环境.  [LLGPL][8]. 为所选的网络服务器提供统一的接口（默认为 Hunchentoot）. 随着更多 [getting started guide](https://jasom.github.io/clack-tutorial/posts/getting-started-with-clack/).
* [zaserve](https://github.com/gendl/aserve) - Franz Inc. 的 AllegroServe 便携式叉子 [LLGPL][8].
* [wookie](https://github.com/orthecreedence/wookie) - Asynchronous HTTP server. [Expat][14].
* [woo](https://github.com/fukamachi/woo)  - 基于 libev 的快速非阻塞 HTTP 服务器.  [麻省理工学院][200].
* [cl-http2-protocol](https://github.com/akamai/cl-http2-protocol)  - 草案 14 中 HTTP/2 协议的纯 Common Lisp 传输不可知实现.  [麻省理工学院][200].

### Hunchentoot plugins

* [easy-routes](https://github.com/mmontone/easy-routes)  - Hunchentoot 之上的路线处理系统. 它支持基于 HTTP 方法的调度、从 url 路径中提取参数、装饰器、从路由名称生成 url 等.[MIT][200].
* [hunchentoot-cgi](https://github.com/slyrus/hunchentoot-cgi)  - 用于从 hunchentoot Web 服务器执行 CGI 脚本的库.  [BSD][207].
* [hunchentoot-multi-acceptor](https://github.com/moderninterpreters/hunchentoot-multi-acceptor/)  - 使用单个端口在单个 hunchentoot 接受器上路由多个域（虚拟主机）.  [Apache2.0][89].
* [hunchentoot-errors](https://github.com/mmontone/hunchentoot-errors)  - 使用请求和会话信息增强了 Hunchentoot 错误页面和日志.  [麻省理工学院][200].

也可以看看：

* [cl-tbnl-gserver-tmgr](https://github.com/mdbergmann/cl-tbnl-gserver-tmgr)  - Hunchentoot 基于 Gserver 的任务管理器.  cl-gserver 是一个类似于 actor 的消息传递库（请参阅下面的“Actors 模式”）. 实验性的.

### Clack plugins

* [tiny-routes](https://github.com/jeko2000/tiny-routes)  - 一个针对 Common Lisp 的小型路由库，目标是 Clack.  [BSD_3 条款][15].
* [clack-errors](https://github.com/eudoxia0/clack-errors)  - Clack 的错误页面中间件.  [LLGPL][8].
* [clath](https://github.com/BnMcGn/clath) - 单点登录
   Clack 的中间件. 它允许使用 OAuth1.0a、OAuth2 进行基本登录
  和 OpenID. 在撰写本文时，它支持来自
  谷歌、Twitter、LinkedIn、StackExchange、Reddit 和 Github.  [Apache2.0][89].
* [clack-pretend](https://github.com/BnMcGn/clack-pretend) - 一个测试
  以及clack的调试工具.  [Apache2.0][89].
* [hermetic](https://github.com/eudoxia0/hermetic)  - 基于 Clack 的 Web 应用程序的安全性.  [外籍人士][14].
* [live-reload](https://github.com/knobo/live-reload)  - 实时重新加载原型.  [LLGPL][8].
* [clack-static-asset-middleware](https://github.com/fisxoj/clack-static-asset-middleware)  - 一个用于 clack 的缓存破坏静态资产中间件.  [麻省理工学院][200].

对于路由，我们还可以使用 Snooze（见下文）.

网络框架
--------------

* [Caveman](https://github.com/fukamachi/caveman)  - 一个强大的网络框架.  [LLGPL][8].
  示例项目： [Quickdocs](https://github.com/quickdocs)
* [ningle](https://github.com/fukamachi/ningle)  - 一个超微型网络框架.  [LLGPL][8].
  - [jingle](https://github.com/dnaeon/cl-jingle) - based on ningle, adds  bells and whistles, such as middlewares.
    - 包括 OpenAPI 和 Swagger UI 演示.
* [radiance](https://github.com/Shirakumo/radiance)  - Web 应用程序环境和框架.  [zlib][33].

以 REST 为中心的框架：

* [Snooze](https://github.com/joaotavora/snooze)  - 一个 RESTful 网络框架. 与 Web 服务器无关. 目前支持 Hunchentoot 和 Clack. 路由只是函数，HTTP 条件只是 Lisp 条件.  [LLGPL][8].
* [cl-rest-server](https://github.com/mmontone/cl-rest-server)  - 用于编写 REST Web API 的库. 具有模式验证、日志记录注释、缓存、权限或身份验证、通过 Swagger 提供的文档等功能.[MIT][200].

请参阅下面的 OpenAPI、OData 和其他库.

### Isomorphic web frameworks

* [CLOG](https://github.com/rabbibotton/clog)  - Common Lisp Omnificent GUI. 使用 Web 技术为本地或远程应用程序生成图形用户界面.  [BSD_3 条款][15].
  - CLOG 基于 GNOGA 的思想，GNOGA 是作者为 Ada 编写的框架，自 2013 年起用于商业生产代码.
* [Interactive SSR](https://github.com/interactive-ssr/client/blob/master/main.org/)  - ISSR 允许您制作交互式网页，而无需编写客户端脚本. 无需了解 Javascript 或 DOM.
  - 它与 Phoenix LiveView 或 Hotwire 没有什么不同.
* [Weblocks](https://github.com/40ants/reblocks)  - 一个基于小部件的框架，具有内置的ajax更新机制，“解决了JavaScript问题”.  [LLGPL][8].


解析html
------------
 * [Plump][71] - 一个宽松的 HTML/XML 解析器，能够容忍格式错误的标记.  [zlib][33]. 最好与 [lquery][72] 和 [clss](https://github.com/Shinmera/CLSS).

查询 HTML/DOM
-----------------
 * [lquery][72] - 类似 jQuery 的 HTML/DOM 操作库.  [zlib][33].

另请参阅下面的 XML 部分以了解 xpath 库等.


HTML 生成器和模板
-----------------------------

* [spinneret](https://github.com/ruricolist/spinneret)  - Common Lisp HTML5 生成器.  [外籍人士][14].
* ⭐ [cl-who](http://weitz.de/cl-who/)  - 久负盛名的 HTML 生成器.  [FreeBSD][39].
* ⭐ [Djula](https://github.com/mmontone/djula)  - Django 模板引擎到 Common Lisp 的端口.  [外籍人士][14].
  - [cl-djula-tailwind](https://github.com/rajasegar/cl-djula-tailwind) - 在 Djula 模板中使用 TailwindCSS 类，无需任何 JavaScript 或 Node.js 工具.
* [TEN](https://github.com/mmontone/ten)  - Djula 的完整性满足 Eco 的可用性.  [麻省理工学院][200].
* [eco](https://github.com/eudoxia0/eco)  - 快速、灵活、设计者友好的模板引擎.  [外籍人士][14].
* [cl-closure-template](https://github.com/archimag/cl-closure-template)  - Google Closure 模板的实现，其中编译模板会创建一个生成结果的函数.  [LLGPL][8].
* [flute](https://github.com/ailisp/flute)  - 一个易于组合的 HTML5 生成库，具有最简单的语法.  [麻省理工学院][200].
* [clip](https://shinmera.github.io/clip)  - HTML 模板处理器，其中模板以 HTML 编写.  [zlib][33].
* [lsx](https://github.com/fukamachi/lsx/) 和 [markup](https://github.com/moderninterpreters/markup)  - 两个类似 JSX 的模板引擎，其中 HTML 标签是 Common Lisp 代码.  `markup` 带有 Emacs 包.

URI处理
------------

* [quri](https://github.com/fukamachi/quri) - 另一个 URI 库
  通用 Lisp. 支持用户信息、IPv6主机名、编码/解码
  公用事业，... [BSD_3Clause][15].
* [cl-slug](https://github.com/EuAndreh/cl-slug)  - 一个用于制作 slugs 的小型库，主要用于 URI，以 CamelCase 进行转换，删除重音符号和标点符号，适用于英语和其他语言.  [LLGPL][8].

Javascript
----------

* ⭐ [Parenscript](https://common-lisp.net/project/parenscript/)  - 从 Common Lisp 到 Javascript 的翻译器.  [3 条款 BSD][15]. 看 [Trident-mode](https://github.com/johnmastro/trident-mode.el)，一种提供与浏览器实时交互的 Emacs 模式.[未许可][5].
  * [paren6](https://github.com/BnMcGn/paren6/) - 一组用于 Parenscript 的 ES6 宏.
* [JSCL](https://github.com/jscl-project/jscl)  - 一个 CL 到 JS 的编译器，从第一天起就被设计为自托管. 缺乏 CLOS、格式和循环.
* [CL-JavaScript](http://marijnhaverbeke.nl/cl-javascript/)  - 从 Javascript 到 Common Lisp 的翻译器. 在 Quicklisp 上不可用.  [外籍人士][14].
* [parse-js](http://marijnhaverbeke.nl/parse-js/) - 用于解析 ECMAScript 3 的包. [zlib][33].
* [Wuwei](https://github.com/mtravers/wuwei/)  - 用于构建基于 Ajax 的网页的工具包.  [麻省理工学院][200].
* [SmackJack](https://github.com/aarvid/SmackJack)  - 一个 Ajax Common Lisp 库，使用 parenscript 生成 javascript 和 hunchentoot（目前）作为 Web 服务器. 还允许服务器端 lisp 函数调用客户端 parenscript 函数.  [麻省理工学院][200].
* [remote-js](https://github.com/ceramic/remote-js)  - 将 JavaScript 从 Common Lisp 发送到浏览器.  [麻省理工学院][200].
* [sigil](https://github.com/BnMcGn/sigil)  - Javascript 命令行编译器和 REPL 的 Parenscript.  [麻省理工学院][200].

开发中：

* [Valtan](https://github.com/cxxxr/valtan) - Common Lisp 到 JavaScript 编译器.
* [JACL](https://tailrecursion.com/JACL/) - 用于 Web 浏览器平台的实验性 Lisp 系统，用于探索使用 Lisp 开发大型单页应用程序的新技术.


**React** 的实用程序：

* [cl-react](https://github.com/helmutkian/cl-react)  - 用于在 ReactJs 中构建 Web 应用程序的 Common Lisp (Parenscript) 实用程序. 麻省理工学院.
* [Panic](https://github.com/michaeljforster/panic) ，一个 React 的 Parenscript 库. 不在 Quicklisp 中.  [麻省理工学院][200]. 它是 [TodoMVC example](https://github.com/40ants/todomvc/blob/common-lisp-example/examples/common-lisp-react/src/app.lisp).
* [Parenscriptx](https://github.com/jasom/parenscriptx)  - Parenscript 宏帮助生成反应代码.  [麻省理工学院][200].
* [jscl-react](https://github.com/nilesr/jscl-react)  - 一个使用 jscl 在 common lisp 中编写 React 组件的 Web 框架. 未指定许可证.


也可以看看：

* [trident-mode](https://github.com/johnmastro/trident-mode.el)，用于实时 Parenscript 交互的 Emacs 小模式.


Deployment
----------

* [deploy](https://shinmera.github.io/deploy)  - 用于 Lisp 应用程序二进制部署的工具包，额外支持外部共享库.  [zlib][33].
* [common-lisp-heroku-example](https://github.com/fstamour/common-lisp-heroku-example) - Heroku 上使用 Docker 的 Common Lisp 服务器示例.
* [cube](https://github.com/xh4/cube)  - 根据 Swagger 规范生成的 Common LISP 的 Kubernetes 客户端库.  [麻省理工学院][200].
* [s2i-lisp](https://github.com/container-lisp/s2i-lisp)  - 基于 CentOS 或 RHEL7 的 Source-to-Image 构建器映像，用于为 OpenShift（以及 Docker）构建 Common LISP 映像. 它具有最新的 SBCL 和 Quicklisp 安装、SLIME 或 SLY 集成，并允许通过环境变量进行自定义.  [阿帕奇2][89]
* [cl-aws-runtime-test](https://github.com/y2q-actionman/cl-aws-custom-runtime-test)  - 使用 Common Lisp (SBCL) 作为 AWS lambda 上的自定义运行时的示例.  WTFPL.

也可以看看：

- [Platform.sh](https://platform.sh/blog/2019/lisp/) 有 Common Lisp 支持，所以有 [OVH](https://docs.ovh.com/ie/en/web-paas/languages-lisp/) 通过他们的 Web PaaS 合作伙伴关系.
- [Heliohost](https://www.heliohost.org/) 获取免费托管解决方案.
- [Cloud Init file for SBCL](https://gist.github.com/marcuskammer/366964f7d569317429773b82a4dafbf9) - 支持 cloudinit 格式（DigitalOcean 等）的提供商的示例 init 文件.

Monitoring
----------

* [prometheus.cl](https://github.com/deadtrickster/prometheus.cl)  - Prometheus.io 客户端. 用于 SBCL 和 Hunchentoot 指标（内存、线程、每秒请求数……）的 Grafana 仪表板.  [麻省理工学院][200].
  * [prometheus-g](https://github.com/40ants/prometheus-gc) - prometheus.cl 的扩展，收集有关垃圾收集器状态的指标.
* [cl-sentry-client](https://github.com/mmontone/cl-sentry-client)  - Common Lisp 的 Sentry 客户端，基于云的错误监控系统.  [麻省理工学院][200].
* [rollbar.lisp](https://github.com/adventuring/rollbar.lisp) - 接口 [Rollbar.com](https://rollbar.com/)，一个错误跟踪软件.


Websockets
----------

* [usocket](https://github.com/usocket/usocket)  - 可移植的 TCP 和 UDP 套接字接口.  [外籍人士][14].
* [Portal](https://github.com/charJe/portal)  - Common Lisp 的可移植 websockets，使用 usocket.  [LLGPL][8].
* [clws](https://github.com/3b/clws)  - CL 中的 websockets 服务器，基于 IOlib 和 libfixposix 构建. 未指定许可证.
* [Hunchensocket](https://github.com/joaotavora/hunchensocket)  - Common Lisp 的符合 RFC6455 的 WebSockets，作为 Hunchentoot 的扩展.  [麻省理工学院][200].
* [websocket-driver](https://github.com/fukamachi/websocket-driver) - 基于克拉克.
* [iolib](https://github.com/sionescu/iolib)  - I/O 库.  [外籍人士][14].
  *“IOlib 是一个比标准 Common Lisp 库更好、更现代的 I/O 库.它包含：套接字库、DNS 解析器、I/O 多路复用器、路径名库和文件系统实用程序.”

 *编者注：在撰写本文时，我们似乎还没有 Common Lisp 的全功能 websocket 实现. 不过，我们可以推荐 Portal，并邀请您仔细检查 Hunchensocket 和 websocket-driver 的当前问题.*


网络开发实用程序
-------------------------

### Assets management

* [Rock](https://github.com/eudoxia0/rock) - 资产管理人
  通用 Lisp. 它基本上是 Bower 和
  网络资产.  [麻省理工学院][200].

### Browser tests

* [cl-webdriver-client](https://github.com/copyleft/cl-webdriver-client/) - WebDriver 的绑定库（支持 Selenium 4.0）.

### Form handling

* [cl-forms](https://github.com/mmontone/cl-forms)  - Common lisp 的 Web 表单处理库.  [麻省理工学院][200].

### User login and password management

* [cl-authentic](https://github.com/charJe/cl-authentic)  - Common Lisp（Web）应用程序的密码管理.  [LLGPL][8].
  - 安全密码存储：无明文，通过铁定使用您选择的哈希算法，存储在 SQL 数据库中，
  - 具有一次性令牌的密码重置机制（适合邮寄给用户进行确认），
  - 可选择使用确认令牌创建用户（适合邮寄给用户），
* [mito-email-auth](https://github.com/40ants/mito-email-auth) - 通过电子邮件向网站用户发送唯一代码，帮助验证网站用户的身份.

* [cl-cas](https://github.com/fferrere/cl-cas) - 一个可以提供帮助的图书馆 [CAS authenticaton](https://apereo.github.io/cas/6.0.x/protocol/CAS-Protocol.html)  Common Lisp Web 应用程序. 不在 Quicklisp 中.
  * [cas-middleware](https://github.com/fferrere/cas-middleware) - Caveman 的 CAS 身份验证中间件.
  * [cas-demo](https://github.com/fferrere/cas-demo) - 一个演示项目.

另请参阅上面的 mito-auth 以及 Hunchentoot 和 Clack 插件.

### Web project skeletons and generators

* [cl-cookieweb](https://github.com/vindarel/cl-cookieweb)  - 用于启动 Web 项目的 Cookiecutter 模板.  [BSD_3 条款][15]. 不在 Quicklisp 中.
  * 提供一个可运行的玩具 Web 应用程序，其中包含 Hunchentoot Web 服务器、简单路线、Djula 模板、Bulma 样式、基于 SQLite、迁移、示例表定义和使用 FiveAM 的测试套件.
* [make-like](https://github.com/container-lisp/make-like)  - LIKE（Lisp In Kubernetes + Emacs）应用程序的应用程序模板构建器.  [Apache2.0][51].
  * Makefile、podman 支持、GitHub Actions、Prometheus 指标支持、TOML 风格的 config.ini、预配置健康检查的简单路由等.
* [cl-webapp-seed](https://github.com/rajasegar/cl-webapp-seed)  - 一个简单的 Web 应用程序样板. 使用 Hunchentoot、cl-who，轻松部署到 Heroku.  [麻省理工学院][200].

Others
------

* [css-lite](https://github.com/paddymul/css-lite)  - CSS 语法.  [外籍人士][14].
* [find-port](https://github.com/eudoxia0/find-port)  - 以编程方式查找开放端口.  [麻省理工学院][200].
* [Postmaster](https://github.com/eudoxia0/postmaster)  - 一个简单、易于使用的 SMTP/IMAP 库.  [外籍人士][14].
* [cl-wget](https://github.com/cl-wget/cl-wget)  - 使检索大文件或镜像整个网站变得容易.  [AGPL-3.0][51].
* [trivial-download](https://github.com/eudoxia0/trivial-download)  - 下载文件.  [麻省理工学院][200].


### Email

* [trivial-imap](https://github.com/40ants/trivial-imap)  - 尝试简化使用 IMAP 服务器的一些常见情况，例如从服务器读取电子邮件. 邮局库（Franz 的 cl-imap 的一个分支）的薄包装.  [BSD][15].
* [cl-smtp](https://gitlab.common-lisp.net/cl-smtp/cl-smtp) - CL-SMTP 是一个简单的 lisp smtp 客户端.
* [sendgrid](https://github.com/vindarel/cl-sendgrid)  - 使用 Sendgrid 的 API 发送电子邮件.  [麻省理工学院][200].
* [mailgun](https://github.com/40ants/mailgun)  - 通过 mailgun.com 发布 HTML 电子邮件的薄包装.  [无执照][5].
* [cl-ses](https://github.com/CodyReichert/cl-ses/)  - AWS SES 库.  [外籍人士][14].

### OpenAPI, OData, OpenRPC

* [openapi-generator](https://codeberg.org/kilianmh/openapi-generator)  - OpenAPI 客户端代码生成器.  [AGPL-3.0][51].
  * 在一个命令中生成 OpenAPI ASDF/Quicklisp 可加载项目，
  * 支持路径、（任意）查询、（任意）标头、（json）内容参数、
  * 将 OpenAPI 规范转换为 CLOS 对象 -&gt; 在检查器中探索 API，
  * 使用 swagger 转换器将 OpenAPI-2.0 或 YAML 文件转换为 OpenAPI-3.0 JSON（需要网络连接），
  * ETC.
* [apispec](https://github.com/cxxxr/apispec)  - 用于处理 Web API 请求和响应的 Common Lisp 库.  [BSD_3 条款][15].
  - takes an OpenAPI3 yaml specification and allows to validate and parse HTTP request headers, parameters and bodies.
* [cl-odata-client](https://github.com/copyleft/cl-odata-client) - 用于访问的 Common Lisp 客户端库 [OData services](https://www.odata.org) .  [麻省理工学院][200].
* [OpenRPC](https://github.com/40ants/openrpc)  - Common Lisp 的 OpenRPC 实现.  [BSD][15].
  - 自动生成 OpenRPC 规范
   - 按照 OpenRPC 规范自动构建 JSON-RPC 客户端. 这包括创建用于发出 RPC 请求和返回本机 CL 对象的 Common Lisp 类和方法.
  - 所有 JSON 编组都是在后台完成的.


### Static site generators

* [coleslaw](https://github.com/kingcons/coleslaw) 和它
  [coleslaw-cli](https://github.com/40ants/coleslaw-cli) - 灵活
   Lisp Blogware 类似于 Frog、Jekyll 或 Hakyll.  [BSD][15].

### Third-party APIs

* [Aws-sign4](https://github.com/rotatef/aws-sign4) - 用于 Amazon Web Services 签名版本 4 的 Common Lisp 库.[GNU GPL3][2].
* [aws-sdk-lisp](https://github.com/pokepay/aws-sdk-lisp/)  - 为每个 AWS 服务作为单独的系统提供接口.  [BSD_2 条款][17].
  * 包括数十种服务：dsn、appstream、athena、cloudfront、codedeploy、cognito-*、directconnect、dynamodb、dms、elasticache、电子邮件、事件、kinesis、机器学习、监控、s3、sms、storagegateway、工作区...
* [zs3](https://github.com/xach/zs3) - 用于使用 Amazon Simple Storage 的库
服务 (S3) 和 CloudFront 服务.  [BSD][15].
* [north](https://shinmera.github.io/north)  - South (Simple OaUTH) 库的后继者，在客户端和服务器端实现完整的 oAuth 1.0a 协议. 使用 North，您可以轻松成为 oAuth 提供者或消费者.  [zlib][33].
* [Ciao](https://github.com/kjinho/ciao)  - 易于使用的 Common Lisp OAuth 2.0 客户端库. 它是 Racket OAuth 2.0 客户端到 Common Lisp 的端口.  [LGPL3][9].
* [avatar-api](https://github.com/eudoxia0/avatar-api) - Get avatars from Google+, Gravatar and others. [Expat][14].
* [chirp](https://github.com/Shinmera/chirp)  - Twitter 客户端库.  [zlib][33].
* [tooter](https://github.com/Shinmera/tooter)  - 为 Mastodon 实现完整 v1 REST API 协议的客户端库.  [zlib][33].
* [cl-irc](https://www.common-lisp.net/project/cl-irc/)  - IRC 客户端库.  [外籍人士][14].
* [cl-mediawiki](https://github.com/AccelerationNet/cl-mediawiki)  - MediaWiki api 的包装器.  [麻省理工学院][200].
* [cl-openid](https://github.com/cl-openid/cl-openid)  - OpenID 的实现.  [LLGPL][8].
* [cl-pushover](https://github.com/TeMPOraL/cl-pushover)  - Common Lisp 与 Pushover 的绑定.  [麻省理工学院][200].
* [humbler](https://github.com/Shinmera/humbler)  - Tumblr API 接口.  [zlib][33].
* [multiposter](https://github.com/Shinmera/multiposter)  - 同时发布到多个服务.  [zlib][33].
* [stripe](https://git.mfiano.net/mfiano/stripe)  - Stripe 支付系统的客户端.  [麻省理工学院][200].
* [lisp-pay](https://github.com/K1D77A/lisp-pay)  - 各种支付处理器的包装：Paypal、Stripe、Coin payments 和 BTCPayServer.  [麻省理工学院][200].
* [lunamech-matrix-api](https://github.com/K1D77A/lunamech-matrix-api)  - 客户端 -&gt; 服务器矩阵 API 的完整包装.  [麻省理工学院][200].
* [cl-telegram-bot](https://40ants.com/cl-telegram-bot/)  - 电报机器人 API.  [麻省理工学院][200].


数值与科学
========================

* ⭐ [maxima](http://maxima.sourceforge.net/)  - 计算机代数系统.  [GNU GPL3][2].
  * [wxMaxima](https://wxmaxima-developers.github.io/wxmaxima/)：图形前端.
  * [Maxima on Android](https://play.google.com/store/apps/details?id=jp.yhonda)，用 ECL 构建.
  * [Maxima on Jupyter](https://github.com/robert-dodier/maxima-jupyter)
  * 可以通过以下方式使用 [SageMath](https://www.sagemath.org/) 和 [KDE Cantor](https://apps.kde.org/cantor/) . 当然，使用 Emacs： [maxima-mode](https://gitlab.com/sasanidas/maxima) ([screenshot](https://community.linuxmint.com/img/screenshots/maxima-emacs.png)) 和 [maxima-interface](https://github.com/jmbr/maxima-interface) to ease the interface between Maxima 和 Common Lisp.
  * 可以使用 [from a Lisp REPL](https://mahmoodsheikh36.github.io/post/20230510181916-maxima_in_lisp/).
* [numcl](https://github.com/numcl/numcl)  - Common Lisp 中的 Numpy 克隆.  [LGPL3][9].
* [GSLL](https://common-lisp.net/project/gsll/)  - Lisp 的 GNU 科学图书馆； 允许使用 Common Lisp 中的 GSL.  [GNU LGPL2.1][11].
* [Xecto](https://github.com/pkhuong/Xecto)  - 用于常规数组并行性的库.  [3 条款 BSD][15].
* [Petalisp](https://github.com/marcoheisig/Petalisp) - 尝试
  为并行计算机生成高性能代码
   JIT 编译数组定义. 它适用于更多
  比 NumPy 更基础的水平，提供更强大
  N 维数组，但只是一些用于处理的构建块
  他们.  [AGPL-3.0][agpl3].
* [cl-ana](https://github.com/ghollisjr/cl-ana)  - Common Lisp 数据分析库，强调模块化和概念清晰度. 它的目标是成为一个用于分析小型和大型数据集的通用框架，包括分级数据分析和可视化.  [GNU GPL3][2].
* [linear-programming](https://neil-lindquist.github.io/linear-programming/)  – 用于解决线性规划问题的库.  [麻省理工学院][200].
* [avm](https://github.com/takagi/avm)  - 高效且富有表现力的阵列向量数学库，具有多线程和 CUDA 支持.  [麻省理工学院][200].
* [array-operations](https://github.com/bendudson/array-operations)  - 用于操作 Common Lisp 数组并用它们执行数值计算的函数和宏的集合.  [麻省理工学院][200].
* [cl-geometry](https://github.com/Ramarren/cl-geometry/)  - Common Lisp 的二维计算几何系统.  [麻省理工学院][200].
* [Vellum](https://github.com/sirherrbatka/vellum)  - Common Lisp 的数据框架.  BSD_2 条款.
* [rtg-math](https://github.com/cbaggers/rtg-math/)  - 选择在 lisp 中制作实时图形最常用的数学例程（2、3 和 4 个分量向量、3x3 和 4x4 矩阵、四元数、球坐标和极坐标）.  BSD_2 条款.
* [origin](https://github.com/mfiano/origin)  - 原生 Lisp 图形数学库，强调性能和正确性. 包括：向量、矩阵（高达 4x4）、四元数、单/双浮点支持、破坏性/非破坏性操作、整形和交叉.  [麻省理工学院][200].

矩阵库
----------------

* [magicl](https://github.com/quil-lang/magicl)  - 基于 BLAS/LAPACK 和 Expokit 的 Common Lisp 中的矩阵代数程序，由 Rigetti Computering 开发.  [BSD_3 条款][15].
* [lisp-matrix](https://github.com/blindglobe/lisp-matrix)  - 矩阵包.  [FreeBSD][39].
* [3d-matrices](https://shinmera.github.io/3d-matrices)  - 实现常见矩阵计算的库，重点关注图形中常用的 2x2、3x3 和 4x4 矩阵. 它还提供了一些数值函数，但这些不是重点. 该库经过了深度优化，因此它不是由漂亮的代码组成的.  [zlib][33].
* [clem](https://github.com/slyrus/clem)  - 矩阵库.  [BSD_2 条款][17].

Statistics
---------

* [lisp-stat](https://github.com/lisp-stat) - an environment for statistical computing, conceptually similar to R, that is also suitable for front-line production deployments. "It grew out of a desire to have an environment for rapidly prototyping analytical and A.I. solutions, and move directly to production environments with minimal friction."
  * https://lisp-stat.dev/
  * 运送卢克·蒂尔尼 [XLisp-Stat](https://homepage.stat.uiowa.edu/~luke/xls/xlsinfo/) （R 的前身）以及较新的库.
* [common-lisp-stat](https://github.com/blindglobe/common-lisp-stat/)  - Common Lisp 统计库.  [FreeBSD][39].

Units
-----

* [physical-quantities](https://github.com/mrossini-ethz/physical-quantities)  - 一个库，提供具有可选单位和/或不确定性的数字类型，用于自动错误传播的计算. 通用公共许可证2

Utils
-----

* [cmu-infix](https://github.com/rigetti/cmu-infix)  - 用于在 Common Lisp 中编写中缀数学符号的库. 也可以看看 [polisher](https://github.com/mrcdr/polisher).


并行性和并发性
===========================

* ⭐ [BordeauxThreads](https://common-lisp.net/project/bordeaux-threads/)  - 可移植、共享状态并发.  [外籍人士][14].
* ⭐ [lparallel](https://github.com/lmj/lparallel)  - 并行编程库.  [3 条款 BSD][15].
* [lfarm](https://github.com/lmj/lfarm)  - 跨机器分配工作（在 lparallel 和 usocket 之上）.  [BSD_3条款][15]
* [calispel](https://github.com/hawkir/calispel) - [CSP](https://en.wikipedia.org/wiki/Communicating_sequential_processes) - 类似于 common lisp 的通道. 具有阻塞、可选缓冲通道和“CSP select”语句.  ISC 风格.
   - “它完整、灵活且易于使用.我会推荐 Calispel，而不是 Lparallel 和 ChanL.”  @安布雷瓦尔. [discussion](https://github.com/CodyReichert/awesome-cl/issues/290)
* [chanl](https://github.com/zkat/chanl)  - 可移植的、基于通道的并发.  [Expat][14]，部分内容位于 [3-clause BSD][15] 下.
* [cl-async](https://github.com/orthecreedence/cl-async)  - 用于通用、非阻塞编程的库.  [外籍人士][14].
* [Moira](https://github.com/TBRSS/moira)  - 监视并重新启动后台线程.  In-lisp 流程主管.  [麻省理工学院][200].
* [trivial-monitored-thread](https://gitlab.com/ediethelm/trivial-monitored-thread) -
  一个 Common Lisp 库，提供了一种生成线程的方法
  当其中任何一个坠毁并死亡时通知.  [麻省理工学院][200].
* [cl-gearman](https://github.com/taksatou/cl-gearman) - 一个图书馆 [Gearman](http://gearman.org/) 分布式作业系统.  [LLGPL][8].
* [swank-crew](https://github.com/brown/swank-crew)  - 使用 Swank Client 实现的分布式计算框架.  [BSD_3 条款][15].
* [cl-coroutine](https://github.com/takagi/cl-coroutine)  - 协程库. 它在实现中使用 CL-CONT 延续库.  [麻省理工学院][200].
* [STMX](https://github.com/cosmos72/stmx)  - Common Lisp 的高性能事务内存.  [LLGPL][8].
* [Blackbird](https://orthecreedence.github.io/blackbird/) - Common Lisp 的 Promise 实现 [MIT][200].
  * 也可以看看 [promise](https://github.com/Shinmera/promise)  - 一个基本的承诺数据结构，带有超时.  ZLIB.

也可以看看：

* [cl-etcd](https://github.com/atgreen/cl-etcd) - 将 etcd 作为异步下级进程运行.  [etcd](https://etcd.io/) 是一个强一致的分布式键值存储.  [AGPL-3.0][agpl3].

演员图案
--------------

* [Sento](https://github.com/mdbergmann/cl-gserver)  - Sento（以前称为 cl-gserver）是一个“消息传递”库/框架，其参与者类似于 Erlang 或 Akka. 它支持创建反应式工作、需要并行计算和基于事件的消息处理的系统.  [阿帕奇2][89].
* [erlangen](https://github.com/eugeneia/erlangen)  - Clozure Common Lisp 的分布式异步消息传递系统.  [GNU GPL3][2].
* [Actors](https://github.com/aarvid/Actors) LispWorks 包（[announce](https://www.reddit.com/r/Common_Lisp/comments/77vsft/david_mcclains_actors_package_for_lispworks/)）[麻省理工学院][200].
* [common-lisp-actors](https://github.com/naveensundarg/Common-Lisp-Actors)  - 一个简单易用的Actor系统.  [BSD_2 条款][17].
* [memento-mori](https://github.com/zkat/memento-mori) - 用于编写健壮的、基于参与者的系统的库. 它从 Erlang/OTP 中汲取灵感，特别是其高可用性系统的崩溃优先方法以及 Akka.  [麻省理工学院][200].

也可以看看：

* [lisp-actors](https://github.com/dbmcclain/Lisp-Actors)，“对 Common Lisp 中 Actor 模型的使用进行的持续调查，这对现实世界的应用有好处”.
  * 它是的一部分 [Emotiq blockchain](https://github.com/emotiq/emotiq/blob/dev/src/test/blockchain-test.lisp) （已终止的项目）
  * 进行远程处理，包括类似于 Bordeaux-Threads 的线程抽象层库.
   *！ 它缺乏单元测试.


事件处理
----------------

* [simple-tasks](https://github.com/Shinmera/simple-tasks)  - 一个非常简单的任务调度框架.  [zlib][33].
* [deeds](https://github.com/Shinmera/deeds)  - Deeds 是一个可扩展的事件交付系统. 它允许通过复杂的事件过滤系统将事件有效地传递到多个处理程序.  [zlib][33].
* [cl-flow](https://github.com/borodust/cl-flow/)  - 用于非阻塞并发 Common Lisp 的数据流计算树库.  [麻省理工学院][200].
* [event-glue](https://github.com/orthecreedence/event-glue)  - 简单的事件抽象. 没有依赖性. 它可以在任何需要通用事件处理系统的地方使用.  [麻省理工学院][200].


作业处理
--------------


* [SBCL's timers](http://www.sbcl.org/manual/#Timers)，系统范围的事件调度程序.
* [psychiq](https://github.com/fukamachi/psychiq)  - Common Lisp 应用程序的基于 redis 的后台作业处理. 受到 Ruby 的 Sidekiq 的启发，并与其 Web UI 兼容.  [LLGPL][8].
* [cl-cron](https://github.com/ciel-lang/cl-cron)  - 一个简单的工具，提供类似 cron 的功能.  [GPL3][2].
* [clerk](https://github.com/tsikov/clerk)  - 一个类似 cron 的调度程序，具有健全的 DSL.  [麻省理工学院][200].


Regex
=====

* ⭐ [cl-ppcre](http://weitz.de/cl-ppcre/)  - 可移植、与 Perl 兼容的正则表达式.  [FreeBSD][39].
* [one-more-re-nightmare](https://github.com/no-defun-allowed/one-more-re-nightmare)  - Common Lisp 中的快速正则表达式编译器.  [BSD_2 条款][17].

另请参见上面的 clj-re.


Scripting
=========

编写、运行脚本
------------------------

* [Roswell](https://github.com/roswell/roswell#scripting-with-roswell) -
  一个 lisp 安装程序和脚本环境（帮助程序、启动程序、
  安装程序）等等.  [麻省理工学院][200].
* [cl-all](https://github.com/shinmera/cl-all)  - 在多个实现中运行 Lisp 片段的脚本. 这使您可以快速比较实现行为和差异.  [zlib][33].
* [clawk](https://github.com/sharplispers/clawk)  - 嵌入到 Common Lisp 中的 AWK 实现，用于搜索文件中的行并对其字段执行指定的操作.  BSD 风格.
* [ScriptL](https://github.com/rpav/ScriptL)  - Shell 脚本变得像 Lisp 一样！ 或者，实时编码远程函数调用 shell. 在 REPL 中编写命令，然后立即在 shell 中运行它.  [LLGPL][8].
  * 类似并且可能更简单： [lserver](https://notabug.org/quasus/lserver/)

命令行选项解析器
----------------------------

* [Clingon](https://github.com/dnaeon/clingon) - 丰富的命令行选项解析器系统.
  * 它可能具有最丰富的功能集：子命令、bash补全的生成、支持各种选项（整数、布尔值、计数器、枚举……）、可扩展……
* [Adopt](https://github.com/sjl/adopt/)  - 一个该死的OPTion解析库.  [麻省理工学院][200].


Readline、ncurses 和其他图形助手
--------------------------------------------

* [cl-readline](https://github.com/vindarel/cl-readline) - 一套
  函数可以在输入行时对其进行编辑，以维护列表
  以前输入的命令行，调用并重新编辑它们
  执行类似 csh 的历史扩展.  Emacs 和 vi 编辑
  模式.  [GPL3][2].
* [Linedit](https://common-lisp.net/project/linedit) - Readline风格
  提供可定制行编辑的库
  特征.  [麻省理工风格][210].
* [cl-charms](https://github.com/HiTECNOLOGYs/cl-charms) - 一个
   Common Lisp 中“libcurses”的接口. 它既提供了原始的、
  通过 CFFI 到 libcurses 的低级接口，以及更高级别的接口
  口齿不清的接口.  [麻省理工学院][200].
* [replic](https://github.com/vindarel/replic/)  - 将现有代码转换为 readline 应用程序的帮助程序，重点是定义命令参数的完成. 还作为一个随时可用的可执行文件提供，它将用户的 lispy 初始化文件转换为 readline 命令.  [麻省理工学院][200].
* [cl-ansi-term](https://github.com/vindarel/cl-ansi-term) - 打印
  彩色文本、水平线、进度条、（未）排序列表
  以及符合 ANSI 标准的终端上的表格.  [GPL3][2].
* [cl-progress-bar](https://github.com/sirherrbatka/cl-progress-bar/)  - 进度条，就像 Quicklisp 中一样！  [麻省理工学院][200].

外壳、外壳接口
-------------------------

* [Lish](https://github.com/nibbula/lish)  - `lish` 有一天可能会成为一个 lisp shell.  [GPL3][2].
  * 支持路径和 Lisp 符号中可执行文件的制表符补全，允许编写和混合 shell 命令和 Lisp 代码，具有小型 REPL 和交互式调试器等等.
* [shcl](https://github.com/bradleyjensen/shcl)  - Common Lisp 中的类似 POSIX 的 shell.  [Apache2.0][89].
* [Shelly](https://github.com/fukamachi/shelly) - 执行 Common Lisp
  功能类似于shell命令，无需编写命令
  行参数解析器. 它也可以用作类似Make
  构建工具.  [FreeBSD][39].
* [unix-in-lisp](https://github.com/PuellaeMagicae/unix-in-lisp) - 将 Unix 系统挂载到 Common Lisp 映像中.
  * Unix 概念直接/浅层嵌入到 Lisp 中（Unix 命令变成 Lisp 宏，Unix 文件变成 Lisp 变量，Unix 流变成惰性 Lisp 序列，等等）.

Lisp 实用程序：

* [cmd](https://github.com/ruricolist/cmd)  - 用于运行外部程序的实用程序. 防止 shell 插值，在构建时考虑到多线程程序，支持 Windows.  [麻省理工学院][200].
  * `uiop:run-program` (synchronous) and `uiop:launch-program` (async) are shipped with ASDF and available on all modern implementations. See the [CL Cookbook: running external programs](https://lispcookbook.github.io/cl-cookbook/os.html#running-external-programs).
* [Clesh](https://github.com/Neronus/Clesh)  - 扩展 Common Lisp，以类似于 Perl 反引号的方式嵌入 shell 代码.  [FreeBSD][39].

系统管理
---------------------

* [Consfigurator](https://spwhitton.name/tech/code/consfigurator/)  - Lisp 声明式配置管理系统. 您可以使用它以 root 身份配置主机、以非特权用户身份部署服务、构建和部署容器以及生成光盘映像.  [GPL3][2].
* [cl-unix-cybernetics](https://github.com/cl-unix-cybernetics/cl-unix-cybernetics)  (以前的 Adams) - Common Lisp 中的 UNIX 系统管理. 与 Ansible、Chef 或 Puppet 没什么不同.  [国际标准委员会][22].
   - 您使用具有属性的资源来描述您的系统（主机）. 然后仅使用远程主机上的 /bin/sh 和控制主机上的 /usr/bin/ssh 来探测和同步属性.

其他脚本实用程序
-------------------------

* [WCL](https://github.com/wadehennessey/wcl) [停滞] - 允许数百个 Lisp
应用程序立即可用，同时允许
其中几个同时运行.  WCL 通过以下方式实现这一目标
提供 Common Lisp 作为可以链接的 Unix 共享库
 Lisp 和 C 代码可生成高效的应用程序. 例如，
规范“Hello World!”的 Lisp 版本的可执行文件
程序在 32 位 x86 Linux 上仅需要 20k 字节.  WCL也
支持完整的开发环境，包括动态文件
加载和调试.  GDB 的修改版本用于调试 WCL
程序，提供对混合语言调试的支持.
    - A [paper](https://dl.acm.org/doi/abs/10.1145/141478.141560)：“在 Unix 下交付高效的 Common Lisp 应用程序”.


文本编辑器资源
=====================

其中包含各种文本编辑器的插件和其他好东西.

* [Parinfer](https://shaunlebron.github.io/parinfer/)  - Parinfer 是一种编辑 Lisp 代码的方法，有助于保持缩进和括号平衡. 它很容易上手，但它提供了 Paredit 的高级功能. 它可在许多编辑器上使用（Emacs、Vim、Neovim、Atom、Sublime Text、Visual Studio Code、LightTable、CodeMirror 等）.

## Emacs ##

* ⭐ [Slime](https://github.com/slime/slime)  - Emacs 的高级 Lisp 交互模式；  Emacs 内成熟的 Common Lisp 环境. 公共区域.
* [Sly](https://github.com/joaotavora/sly) - SLY 是 SLIME 的一个分支，并包含多项改进.
* [Portacle](https://shinmera.github.io/portacle/) - 一个可移植的多平台 Common Lisp 环境：SBCL、Quicklisp、Emacs、Slime、Git.
* [cl-devel2](https://hub.docker.com/r/eshamster/cl-devel2/)  - 用于 Common Lisp 开发环境的 Docker 容器. 随 Slime 一起提供 SBCL、CCL、Roswell 和 Emacs25.
* [Emacs4CL](https://github.com/susam/emacs4cl)  - 一个小型 Emacs 初始化文件，可快速设置普通 Emacs 以进行 Common Lisp 编程. 附带初始化文件中每一行代码的逐行解释.
* [slime-star](https://github.com/mmontone/slime-star) - 预装扩展的 SLIME 配置，还有一些自定义实用程序和菜单：
  - Lisp系统浏览器
  - [SLIME doc contrib](https://github.com/mmontone/slime-doc-contribs) - 增强默认帮助缓冲区.
  - [Quicklisp systems](https://github.com/mmontone/quicklisp-systems) - 从 Emacs 搜索、浏览和加载 Quicklisp 系统.
  - [Quicksearch](https://github.com/tkych/quicksearch)
  - [Slime breakpoints](https://github.com/mmontone/slime-breakpoints)
  - [Slite](https://github.com/tdrhq/slite/) - FiveAM 的测试运行程序.
  - [Quicklisp-apropos](https://github.com/mmontone/quicklisp-apropos) - 在 Quicklisp 中跨库执行“apropos”查询（对符号名称、类、文档等进行全文搜索）.
  - [slime-critic](https://github.com/mmontone/slime-critic) - Lisp 评论家温和地批评你的代码是否存在不良模式.

## Vim & Neovim ##

* [SLIMV](https://github.com/kovisoft/slimv)  - Vim 的高级 Lisp 交互模式；  Vim 内部成熟的 Common Lisp 环境. 未指定许可证.
* [Vlime](https://github.com/vlime/vlime)  - VLIME：Vim 加上 Lisp 大多是邪恶的.  Vim（和 Neovim）的 Common Lisp 开发环境.  [麻省理工学院][200].
* [quicklisp.nvim](https://gitlab.com/HiPhish/quicklisp.nvim) - Neovim 的 Quicklisp 前端.
* [Slimv_box](https://github.com/justin2004/slimv_box) - Docker 容器中的 slimv.


## Eclipse ##

* [Dandelion](https://github.com/Ragnaroek/dandelion) - Eclipse IDE 的 Common Lisp 插件.

## Lem ##

* [Lem](https://github.com/lem-project/lem) - 一个即用型、类似 Emacs、基于 Slime 
  专为开箱即用的 Common Lisp 开发以及带有内置 LSP 客户端的其他编程语言量身定制的编辑器. 具有 ncurses、Electron 和 SDL2 接口.  [麻省理工学院][200].
  * [Lem 2.0](https://github.com/lem-project/lem/releases/tag/v2.0.0)于 2023 年 5 月发布，添加了 SDL2 前端，从而增加了鼠标支持、图形功能和 Windows 支持等新功能.
  *另见：一个 [opengl frontend](https://github.com/pupcraft/lem-opengl), [Lem in Docker](https://github.com/40ants/lem-docker), [lem-pareto](https://github.com/40ants/lem-pareto).

## Atom, Pulsar ##

* [SLIMA](https://github.com/neil-lindquist/slima) 允许您
  交互式地开发 Common Lisp 代码，将 Atom（或现在的 Pulsar）变成
   Lisp IDE 非常好，并且正在积极开发.  [麻省理工学院][200].

## Sublime Text ##

* [Sublime Text](http://www.sublimetext.com/3) （专有）有
  Common Lisp 支持及其 SublimeREPL 和
  [Slyblime](https://github.com/s-clerc/slyblime) 包. 斯莱布利姆
  是 SLY 的实现，它使用相同的后端 (SLYNK). 它
  提供高级功能，包括带有堆栈框架的调试器
  检查.

## VSCode ##

* [commonlisp-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.commonlisp-vscode)  - 支持语法突出显示、自动完成、悬停文档、转到定义、编译和加载文件、REPL 的扩展. 这是 [On GitHub](https://github.com/ailisp/commonlisp-vscode/).
* [alive](https://github.com/nobody-famous/alive)  - VSCode 的 Common Lisp 扩展. 公共区域.
  *参见食谱： [using VSCode with Alive](https://lispcookbook.github.io/cl-cookbook/vscode-alive.html)
* [strict-paredit-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.strict-paredit) - 像 Emacs 一样的结构编辑和导航.

## JetBrains

* [SLT](https://github.com/Enerccio/SLT) - Itellij/Jetbrains IDE 系列的 IDE 插件，通过 SBCL 和 Slime/Swank 实现对 Common Lisp 的支持.
   - 新的！  2023 年 1 月发布.

## Geany (experimental) ##

* [Geany-lisp](https://github.com/jasom/geany-lisp) 是一个实验性的 Lisp 模式 [Geany](https://geany.org/) 编辑.

## Notebooks ##

* [common-lisp-jupyter](https://github.com/yitzchak/common-lisp-jupyter)  - Jupyter 的 Common Lisp 内核以及用于构建 Jupyter 内核的库，基于 Robert Dodier 的 Maxima-Jupyter，而该库基于 Frederic Peschanski 的 cl-jupyter.  [麻省理工学院][200].
  * [jupyterlab-debugger-restarts](https://github.com/yitzchak/jupyterlab-debugger-restarts) - JupyterLab 调试器的重新启动功能.
  * [Cytoscape widget](https://github.com/yitzchak/cytoscape-clj) -用于 common-lisp-jupyter 的 Cytoscape.js 小部件.
  * [Kekule widget](https://github.com/yitzchak/kekule-clj) -用于 common-lisp-jupyter 的 Kekule.js 小部件.
  * [molecule viewer](https://github.com/yitzchak/jupyterlab-molviewer) - 使用 ngl 的 JupyterLab 分子查看器.
  * [ngl widget](https://github.com/yitzchak/ngl-clj) - 用于 common-lisp-jupyter 的 ngl 小部件（蛋白质查看器）.
  * [sheet widget](https://github.com/yitzchak/sheet-clj) - common-lisp-jupyter 的数据网格小部件.
* [cl-jupyter](https://github.com/fredokun/cl-jupyter) - 适用于 Jupyter 笔记本的 Common Lisp 内核 [custom licence](https://github.com/fredokun/cl-jupyter/blob/master/LICENSE).
* [Darkmatter](https://github.com/tamamu/darkmatter) - A
  笔记本式 Common Lisp 环境.  [麻省理工学院][200].

## REPLs ##

* [cl-repl](https://github.com/koji-kojiro/cl-repl)  - 类似 ipython 的 REPL. 具有完成、shell 命令、魔术命令、调试器等[MIT][200]. 和 [colorthemes](https://github.com/koji-kojiro/lem-pygments-colorthemes).
* [sbcli](https://github.com/hellerve/sbcli)  - SBCL 的读取行 REPL. 具有完成功能、快速命令、可选语法突出显示（使用 pygments），并且没有交互式调试器.  [GPL3][2].

## Online editors ##

* [Judge0 IDE](https://ide.judge0.com/?lUpj) 是一个支持 Common Lisp (SBCL) 的在线编辑器.  [麻省理工学院][200].
* [Riju](https://riju.codes/commonlisp)，一个“适合每种编程语言的快速在线游乐场”，支持 Common Lisp (SBCL).

## Apps ##

* [CodePlayground](https://codeplayground.app/) - 通过 CCL 支持 Lisp 的 iPhone 和 iPad 应用程序.

文本解析器
============

* ⭐ [esrap](https://github.com/scymtym/esrap)  - Packrat 解析器.  [外籍人士][14].
* [cl-yacc](https://github.com/jech/cl-yacc)  - LALR(1) 解析器生成器.  [麻省理工学院][200].
* [cl-shlex](https://github.com/ruricolist/cl-shlex/)  - 用于类似 shell 语法的简单词法分析器.  [麻省理工学院][200].
* [smug](https://github.com/drewc/smug)  - Common Lisp 的解析器组合器.  SMUG 可以轻松创建快速可扩展的递归下降解析器，而无需时髦的语法或难以理解的宏观学.  [麻省理工学院][200].
* [parseq](https://github.com/mrossini-ethz/parseq)  - 使用解析表达式语法解析序列（例如字符串和列表）的库. 受到 Esrap 的启发.  GPL2.
* [texp](https://github.com/eugeneia/texp/)  - 用于生成 TeX 的 DSL.  [AGPL-3.0][agpl3].

文本处理
===============

* [montezuma](https://github.com/sharplispers/montezuma/)  - Common Lisp 的全文索引和搜索.  [外籍人士][14].
* [mk-string-metrics](https://github.com/cbaggers/mk-string-metrics) -
  在 Common Lisp 中高效计算各种字符串指标
  （Damerau-Levenshtein、Hamming、Jaro、Jaro-Winkler、Levenshtein、
   ETC）.  [麻省理工学院][200].
* [wiki-lang-detect](https://github.com/vseloved/wiki-lang-detect) -
使用维基百科数据进行文本语言识别. 未指定许可证.
* [cl-phonetic](https://github.com/bgutter/cl-phonetic)  - Common Lisp 的语音模式匹配库（旨在替换 Python 的 Sylvia 库）.  [麻省理工学院][200].
* [cl-string-generator](https://github.com/pokepay/cl-string-generator)  - 从正则表达式生成字符串.  [麻省理工学院][200].
* [trivial-sanitize](https://notabug.org/cage/trivial-sanitize)  - 干净的 html 字符串：`&quot; <a>foo</a> &quot;` → `&quot;foo&quot;`.  [LLGPL][8].

也可以看看：

* [Resolve](https://github.com/GrammaTech/resolve)  - 用于基于 AST 的差异计算、显示和自动解析的软件. 您会发现 Lisp 实用程序是用 C++ 和 CL 编写的.

Tools
=====

这些应用程序或代码片段使 Common Lisp 中的开发变得更加容易，而它们本身并不是 Common Lisp 库.

* [quicksearch](https://github.com/tkych/quicksearch)  - 从 REPL 查找在线图书馆.  [外籍人士][14].
* [lake](https://github.com/takagi/lake)  - 类似 GNU make 的构建实用程序.  [麻省理工学院][200].


单元测试
============

* ⭐ [FiveAM](https://github.com/sionescu/fiveam)  - 简单的回归测试框架.  [FreeBSD][39].
  * [fiveam-matchers](https://github.com/tdrhq/fiveam-matchers/)  - Fiveam 的可扩展、可组合匹配器库.  [Apache2.0][89].
* [CLUnit2](https://notabug.org/cage/clunit2/)  - 单元测试库.  [麻省理工学院][200].
* [Parachute](https://github.com/Shinmera/parachute)  - 可扩展且交叉兼容的测试框架. 具有测试依赖性、条件、固定装置和重新启动.  [zlib][33].
* [Mockingbird](https://github.com/Chream/mockingbird) - 一个小
   Common Lisp 的存根和模拟库. 还可以检查是否
  一个存根函数被调用了多少次以及调用的次数
  论据.  [麻省理工学院][200].
* [cl-mock](https://github.com/Ferada/cl-mock)  - 另一个模拟库. 它比 Mockingbird 有更多的功能，比如模拟调用的模式匹配等.
* [Check-it](https://github.com/DalekBaldwin/check-it)  - QuickCheck 式的随机基于属性的测试.  [LLGPL][8].
* [cl-coveralls](https://github.com/fukamachi/cl-coveralls) - 一个帮手
  库将测试覆盖率发布到 Coveralls. 看 [SBCL's code coverage tool](http://www.sbcl.org/manual/index.html#sb_002dcover) .  [FreeBSD][39].

也可以看看：

* [testieren](https://cicadas.surf/cgit/colin/testiere.git/about/)  - 一个测试实用程序，其中测试包含在“defun/t”表单的顶部. 当您以交互方式重新编译函数时，它们就会运行. 具有模拟和存根支持.  [GPL3][2].

编辑器实用程序：

* [Slite](https://github.com/tdrhq/slite/)  - 用于 FiveAM 测试的基于 SLIme 的 TEst 运行程序.  [Apache2.0][89]
   - Slite 以交互方式运行您的 Common Lisp 测试（在撰写本文时仅支持 FiveAM）. 它允许您查看测试失败的摘要、跳转到测试定义、使用调试器重新运行测试，所有这些都可以在 Emacs 内部进行.

了解更多： [Sabra Crolleton's extensive test frameworks comparison](https://sabracrolleton.github.io/testing-framework).


Utilities
=========

Caching
-------

* [clache](https://github.com/html/clache)  - 通用缓存设施. 在磁盘或内存中缓存任何 Lisp 对象. 缓存可以是持久的或有过期时间.  [LLGPL][8].
* [function-cache](https://github.com/AccelerationNet/function-cache)  - Common Lisp 函数缓存/记忆库.  [BSD][15].


压缩/减压
---------------------------

* [chipz](https://github.com/froydnj/chipz)  - 一个解压库.  [3 条款 BSD][15].
* [Salza2](http://www.xach.com/lisp/salza2/)  - 用于创建压缩数据的库.  [FreeBSD][39].
* [zippy](https://github.com/Shinmera/zippy)  - 基于 3bz 的 ZIP 存档格式库.  [zlib][33].
* [archive](https://github.com/froydnj/archive)  - 用于读取和创建存档（tar、cpio）文件的库.  [BSD_3 条款][15].  “tar”程序的纯 Common Lisp 替代品.
  * 查看其最近的分叉 [cl-tar](https://common-lisp.net/project/cl-tar/) (2021). [Announce](https://www.timmons.dev/posts/new-project-cl-tar.html).


Configuration
-------------

* [py-configparser](https://common-lisp.net/project/py-configparser/)  - 读取和写入Python 的类似ConfigParser 的配置文件.  [麻省理工学院][200].
* [envy](https://github.com/fukamachi/envy)  - 配置切换器.  [FreeBSD][39].
* [chameleon](https://github.com/sheepduke/chameleon/)  - 附带配置文件支持的配置管理库.  [麻省理工学院][200].

CSV
---

* ⭐ [cl-csv](https://github.com/AccelerationNet/cl-csv)  - 用于解析 CSV 文件的库.  [3 条款 BSD][15].
* [cl-decimals](https://github.com/tlikonen/cl-decimals)  - 十进制数解析器和格式化程序. 公共区域.
* [auto-text](https://github.com/defunkydrummer/auto-text)  - 文本文件的自动（编码、行尾、列宽、csv 分隔符等）检测.  [麻省理工学院][200]. 也可以看看 [inquisitor](https://github.com/t-sin/inquisitor) 用于检测亚洲和远东语言.
* [csv-validator](https://github.com/KoenvdBerg/csv-validator)  - 使用预定义的验证来验证表格 CSV 数据，其灵感来自于其 Python 同源“远大的期望”.  [BSD_3 条款][15].


Date and time
-------------

* ⭐ [local-time](https://common-lisp.net/project/local-time/)  - 用于以半标准方式操作日期和时间信息的开发库.  [3 条款 BSD][15].
* [cl-date-time-parser](https://github.com/tkych/cl-date-time-parser)  - 自由地解析日期时间字符串. 隐藏日期-时间格式之间的差异，并能够将日期和时间作为一种日期-时间格式进行管理.  [麻省理工学院][200].
* [chronicity](https://github.com/chaitanyagupta/chronicity)  - 自然语言日期和时间解析，用于解析“3 天后”等字符串.  [BSD_3 条款][15].
* [local-time-duration](https://github.com/enaeher/local-time-duration) -
建立在本地时间之上的持续时间处理库.  [麻省理工学院][200].
  * 看这个叉子： [humanize-duration](https://github.com/40ants/humanize-duration) ，仅输出持续时间对象的重要部分. 有本地化支持.
* [iso-8601-date](https://gitlab.com/DataLinkDroid/iso-8601-date)  - Common Lisp 中的各种日期例程，基于 ISO 8601 字符串表示形式.  [LLGPL][8].
* [calendar-date](https://github.com/takagi/calendar-date)  - 公历日期库.  [麻省理工学院][200].
* [periods](https://github.com/jwiegley/periods)  - 在更高级别上操作日期/时间对象. 具有系列兼容的数据结构.  [BSD_3 条款][15].
* [stopclock](https://github.com/Gleefre/stopclock)  - 使用（停止）时钟测量时间的库. 它允许您创建时钟、暂停它、恢复它并改变它的速度.  [Apache2.0][89].

另请参阅本书 [Calendrical calculations](https://www.cambridge.org/us/academic/subjects/computer-science/computing-general-interest/calendrical-calculations-ultimate-edition-4th-edition?format=HB#resources) ，作者：Edward M. Reingold、Nachum Dershowitz，剑桥出版社. 它提供 Lisp 源代码.

数据验证
---------------

* [ratify](https://github.com/Shinmera/ratify)  - 用于批准、验证和解析输入的实用程序集合.  [zlib][33].
* [clavier](https://github.com/mmontone/clavier)  - Common Lisp 的通用验证库.  [麻省理工学院][200].
* [json-schema](https://github.com/fisxoj/json-schema) - 用于根据草案 4、6、7 和 2019-09 的模式验证数据的库 [JSON Schema](https://json-schema.org/) 标准.  [LLGPL][8].
* [sanity-clause](https://github.com/fisxoj/sanity-clause)  - Common Lisp 的数据序列化/契约库. 模式可以是属性列表或基于类，允许在“make-instance”期间检查槽的类型.  [LLGPL][8].
* [cl-semver](https://github.com/cldm/cl-semver) - 实施 [Semantic Versioning](https://semver.org) 规格.  [麻省理工学院][200]

开发者实用程序
-------------------

* [repl-utilities](https://github.com/m-n/repl-utilities) - 舒适
REPL 的常见任务（打印文档、打印外部符号、
加载包时调用挂钩，...）.  [BSD_2 条款][17].
* [flight-recorder](https://github.com/vseloved/flight-recorder) - 强大的 REPL 历史记录工具.
* [tracer](https://github.com/TeMPOraL/tracer)  - Common Lisp 的跟踪分析器，输出适合在 Chrome 的/Chromium 的跟踪查看器中显示.  [麻省理工学院][200].
* [cl-flamegraph](https://github.com/40ants/cl-flamegraph)  - SBCL 统计分析器的包装器，用于为 Common Lisp 程序生成 FlameGraph 图表.  [BSD][15].
* [cl-debug](https://github.com/LowH/cl-debug)  - 跨包调试工具. 提供一种统一的方式来启用或禁用特定于调试的代码. 可以相对于由符号或关键字表示的程序功能来启用或禁用调试代码.  ISC 许可证.
* [supertrace](https://github.com/fukamachi/supertrace)  - 用于调试/分析的高级 Common Lisp“跟踪”功能. 一次跟踪多个函数，使用 before 和 after 钩子.  [BSD_2 条款][17].
* [printv](https://github.com/danlentz/printv)  - 包含电池的跟踪和调试日志宏.  [阿帕奇2][89].
* [journal](https://github.com/melisgl/journal)  - 用于日志记录、跟踪、记录和重放测试以及持久性的库. 麻省理工学院.

并且：

* [GTFL](http://www.martin-loetzsch.de/gtfl/)  - Lisp 的图形终端，适用于想要调试或可视化自己的算法的 Lisp 程序员. 浏览器中的图形跟踪.  BSD 风格.
* [trivial-benchmark](https://github.com/Shinmera/trivial-benchmark)  - 小型基准测试库.  [zlib][33].
* [glyphs](https://github.com/ahungry/glyphs/)  - 一个用于减少 Common Lisp 某些地方的冗长性的库.  [GNU GPL3][2].
* [Lisp REPL core dumper](https://gitlab.com/ambrevar/lisp-repl-core-dumper/) -
一个可移植的包装器，可按需生成 Lisp 核心，从而快速启动 REPL.
它可以预加载提供的系统，以帮助构建专门的集合
Lisp 核心.


文档构建者
----------------------

* [Staple](https://github.com/Shinmera/staple) - a tool to generate documentation pages using an HTML template. Uses the existing README, adds docstrings, crossreferences and links to the CLHS. [zlib][33].
* [mgl-pax](https://github.com/melisgl/mgl-pax) - 探索性
编程环境和文档生成器. 一个可能
实现与文学编程类似的效果，但是
文档是从代码生成的，反之亦然. 代码是第一位的，
代码必须看起来漂亮，文档就是代码.  [麻省理工学院][200].
  - 看到这个 [40ants fork](https://github.com/40ants/doc) 用于：更轻的核心系统、JavaScript 搜索索引、多种格式输出、HTML 主题、用于更新日志的 RSS 和 Atom 提要等等.
* [Declt](https://github.com/didierverna/declt)  - Common Lisp 库的参考手册生成器. 构建可进一步处理为各种格式（例如 HTML 或 PDF）的 texinfo 文档.  BSD.
* [Codex](https://github.com/CommonDoc/codex) - 一个美丽
   Common Lisp 的文档系统.  [麻省理工学院][200].
* [QBook](https://github.com/mmontone/qbook)  - 生成 Common Lisp 源文件的 HTML（或 LaTeX）格式的代码列表.  [BSD_3 条款][15].
   - 所有以 4 `;`（“;;;;”）开头的注释都被解释为文档. 使用标题和指令增强文档.
   - QBook 充当“一个轻量级的文学编程系统，其中 Lisp 代码不是内联呈现的，而是在单独的部分中呈现，这使得文档更易于浏览.”  @mmontone
* [sphinxcontrib-cldomain](https://sphinxcontrib-cldomain.russellsim.org/) -
  扩展 Sphinx 以覆盖 Common Lisp. 构建文档
  就像 Python 项目中的 sphinx 一样简单.  [GPL3][2]
* [cl-bibtex](https://github.com/mkoeppe/cl-bibtex)  - Common Lisp 中 BibTeX 程序的兼容重新实现，带有 BST-to-CL 编译器.  [GNU LGPL2.1][11].

也可以看看：

* [docbrowser](https://github.com/lokedhs/docbrowser) - 动态生成加载系统文档的服务器.
   - 它的主页显示了 Lisp 镜像中所有已加载系统的列表. 单击一个系统，您会看到一个包含三个窗格的页面：函数、类和变量. 单击某个函数可在上下文中查看其源代码以及行号. 单击类可查看其插槽和专门功能.
* [cl-livedocs](https://github.com/mmontone/cl-livedocs) - 类似且较新，基于Webinfo，默认启用全文搜索.

包含更多文档生成器的概述博客文章：https://lisp-journey.gitlab.io/blog/overview-of-documentation-generators/

你可能还喜欢： [literate programming systems](#literate-programming).


文件和目录
---------------------

* ⭐ [uiop](https://common-lisp.net/project/asdf/uiop.html) 及其“路径名”包
  （替换 [cl-fad](http://weitz.de/cl-fad/) ）.  uiop 是 ASDF3 的一部分
  因此在许多实现中都是如此.  [麻省理工学院][200].
* [osicat](https://common-lisp.net/project/osicat/) - 类 POSIX 系统上的轻量级操作系统接口（目录迭代和删除、环境变量、文件权限等）[Expat][14].
* [pathname-utils](https://github.com/Shinmera/pathname-utils)  - 帮助进行路径名操作的实用程序集合.  [zlib][33].
  * [filesystem-utils](https://github.com/Shinmera/filesystem-utils) - 处理文件系统的常见问题，例如列出文件、探测文件类型、确定默认目录等.
  * [file-attributes](https://github.com/Shinmera/file-attributes) - 访问常见文件属性（uid、gid、权限、ctime、mtime、atime）.
* [ppath](https://github.com/fourier/ppath) - Common Lisp 
 Python os.path 模块的实现.  [BSD][15].
* [mmap](https://github.com/Shinmera/mmap)  - 便携式 mmap 文件内存映射实用程序库.  [zlib][33].
* [fof](https://gitlab.com/ambrevar/fof)  - 文件对象查找器 Common Lisp 库. 实现快速文件搜索、检查和操作.  [GPL3][2].

文件查看库：

* [file-notify](https://github.com/shinmera/file-notify)  - 用于文件更改检测的跨平台库.  [zlib][33].

Git
---

* [cl-git](https://cl-git.russellsim.org/)  - libgit2 库的 CFFI 接口.  [LGPL3][9].
* [legit](https://shinmera.github.io/legit/)  - Git 二进制文件的接口.  [zlib][33].
* [git-api](https://github.com/fourier/git-api)  - 用于访问 git 存储库的 Common Lisp 库. 它不需要安装 git 或 libgit.  [BSD][15].

i18n
----

* [cl-i18n](https://notabug.org/cage/cl-i18n)  - 国际化图书馆. 从 GNU gettext 文本或二进制文件或其本机格式加载翻译. 复数形式的本地化助手.  [LLGPL][8].
* [gettext](https://github.com/rotatef/gettext)  - gettext 运行时到 Common Lisp 的端口.  [GPL3][2].
* [translate](https://github.com/dkochmanski/translate)  - 无缝语言本地化.  LLGPL.
* [enchant](https://github.com/tlikonen/cl-enchant)  - Enchant 拼写检查库的绑定. 公共区域.
* [oxenfurt](https://github.com/Shinmera/oxenfurt)  - 牛津词典 API 的客户端库.  [zlib][33].
* [language-codes](https://shinmera.github.io/language-codes)  - ISO 语言代码数据库.  [zlib][33]
* [system-locale](https://shinmera.github.io/system-locale)  - 用于检索用户首选语言的库，以便您的应用程序可以选择合理的默认值.  [zlib][33].
* [multilang-documentation](https://shinmera.github.io/multilang-documentation)  - 允许用多种语言编写文档字符串，以实现真正的国际文档库.  [zlib][33].

Linting、代码格式化
------------------------

* [sblint](https://github.com/fukamachi/sblint) - 使用 SBCL 的 Common Lisp 源代码的 linter，适合 Reviewdog ([slides](http://www.slideshare.net/fukamachi/sblint) ）.  [BSD_2 条款][17].
* [trivial-formatter](https://github.com/hyotang666/trivial-formatter)  - Common Lisp 的代码格式化程序.  [麻省理工学院][200].

并且： [lisp-format](https://github.com/eschulte/lisp-format) 和 [cl-indentify](https://github.com/yitzchak/cl-indentify).

识字编程
--------------------

* [literate-lisp](https://github.com/jingtaozf/literate-lisp)  - 从 Emacs 的 Org 文件加载 Common Lisp 代码块.  [麻省理工学院][200].
* [erudite](https://github.com/mmontone/erudite)  - 以交互式开发为理念构建的文学编程系统.  [麻省理工学院][200].


Logging
-------

* ⭐ [log4cl](https://github.com/sharplispers/log4cl/)  - 模仿 Log4J 的日志框架.  [Apache2.0][89]. 与 Slime 的高级集成.
  * [log4cl-json](https://github.com/40ants/log4cl-json)  - JSON 附加器扩展.  [BSD][15].
* [verbose](https://shinmera.github.io/verbose)  - 快速且高度可配置的日志记录框架.  [zlib][33].
* [a-cl-logger](https://github.com/AccelerationNet/a-cl-logger)  - 日志库提供上下文敏感的日志记录，不仅仅是字符串到本地文件或输出流. 具有logstash支持、json支持、记录器层次结构、上下文敏感日志记录、打印为可检查演示文稿的对象……

致第三方：

* [cl-fluent-logger](https://github.com/fukamachi/cl-fluent-logger) - Common Lisp 结构化记录器 [Fluentd](https://www.fluentd.org/).

也可以看看： [extensive comparison of logging libraries](https://sabracrolleton.github.io/logging-comparison).

宏助手
-------------

* [easy-macros](https://github.com/tdrhq/easy-macros/)  - 编写 90% 宏的简单方法.  [Apache2.0][89].
* [trivial-with-current-source-from](https://github.com/scymtym/trivial-with-current-source-form/)  - 帮助宏编写者为宏用户产生更好的错误.  [GPL3][2].

Markdown
--------

* [3bmd](https://github.com/3b/3bmd)  - 一个 markdown -&gt; html 转换器.  [麻省理工学院][200].

PDF
---

* [cl-typesetting](https://github.com/mbattyani/cl-typesetting) 和 [cl-pdf](https://github.com/mbattyani/cl-pdf)  - 用于生成 PDF 文件的跨平台 Common Lisp 库.  [FreeBSD][39].
* [cl-pslib](https://notabug.org/cage/cl-pslib) - 一个（薄）包装纸 [pslib](http://pslib.sourceforge.net/) 用于生成 PostScript 文件的库. 还 [cl-pslib-barcode](https://notabug.org/cage/cl-pslib-barcode) .  [LLGPL][8].

Plotting
--------

* [vgplot](https://github.com/volkers/vgplot) - 一个接口
  gnuplot 绘图实用程序，旨在类似于某些
   Octave 或 Matlab 的绘图命令.  [GPL3][2].
* [eazy-gnuplot](https://github.com/guicho271828/eazy-gnuplot) - A
   lispy，无结构的 Gnuplot 库. 以其
  [cookbook](http://guicho271828.github.io/eazy-gnuplot/) .  [LLGPL][8]
* [kai](https://github.com/komi1230/kai)  - Common Lisp 的高级绘图仪库. 周围有一个包装纸 [Plotly](https://plotly.com/javascript/)  JS 库.  [麻省理工学院][200].
* [ADW-Charting](https://common-lisp.net/project/adw-charting/)  - 一个完全用 Common Lisp 编写的简单图表绘制库. 还包括 Google 图表服务的后端. 类似 BSD.
* [cl-spark](https://github.com/tkych/cl-spark)  - 控制台的迷你图字符串：`(spark &#39;(1 1 2 3 5 8))` =&gt; &quot; ▂▃▅▇&quot;.  [麻省理工学院][200].

另请参阅 IUP 和 ltk-plotchart 的图表工具（GUI 部分）.

项目骨架
-----------------

* [cl-project](https://github.com/fukamachi/cl-project)  - 一般现代项目骨架.  [LLGPL][8].
* [cl-project-with-docs](https://github.com/40ants/cl-project-with-docs)  - 使用 Sphinx 和重构文本来呈现漂亮且可读的 HTML 文档.  [BSD][15].
* [cl-cookieproject](https://github.com/vindarel/cl-cookieproject)  - 生成一个随时可用的 Common Lisp 项目. 不在 Quicklisp 中.  [BSD_3 条款][15].
  * 测试定义、从源运行的入口点、构建二进制文件、Roswell 集成……

Security
--------

* [cl-isolated](https://github.com/kanru/cl-isolated) - Common Lisp 代码评估的受限环境 [AGPL-3.0][agpl3].

XML
---

* [CXML](https://common-lisp.net/project/cxml/)  - XML 解析器和序列化器，带有一系列扩展库.  [LLGPL][8].
  - 有一个增量解析器，允许解析大文件.
  - 参见 [FXML](https://github.com/ruricolist/FXML) 分叉，具有修复和新功能. 如果您正在解析可能格式不正确或恶意的 XML，或者需要将 Klacks 与命名空间一起使用，则应该使用它.
 * [Plump][71] - 一个宽松的 XML 解析器.  [zlib][33].
* [xpath](https://github.com/sharplispers/xpath) ([homepage](https://common-lisp.net/project/plexippus-xpath/atdoc/index.html)  - XML 路径语言 (XPath) 1.0 版的实现.  [BSD_2 条款][17].
* [s-xml](http://cliki.net/S-XML)  - 一个基本的解析器.  [LLGPL][8].
* [xmls](https://github.com/rpgoldman/xmls)  - 一个小型、简单、非验证的 XML 解析器.  [3 条款 BSD][15].
* [cl-feedparser](https://github.com/TBRSS/cl-feedparser)  - Common Lisp（RSS、Atom）提要解析器.  [LLGPL][8]
* [Buildnode](https://github.com/AccelerationNet/buildnode)  - 一个通用的 lisp 库，可简化与 CXML-dom 的交互，例如构建 Excel 电子表格.  [BSD][15].


Other
-----

其中包含不属于其他类别的任何内容.

* [babel](https://github.com/cl-babel/babel)  - 字符集编码/解码库.  [外籍人士][14].
* [corona](https://github.com/eudoxia0/corona) - 从 Common Lisp 创建和管理虚拟机 http://eudoxia.me/corona [MIT][200].
* [fast-io](https://github.com/rpav/fast-io)  - 快速八位位组向量/流 I/O.  [3 条款 BSD][15].
* [named-readtables](https://github.com/melisgl/named-readtables)  - 提供一个可读的命名空间，类似于包命名空间.  [3 条款 BSD][15].
* [simple-currency](https://github.com/a0-prw/simple-currency)  - 使用欧洲央行发布的每日信息的货币换算库.  [FreeBSD][39].
* [trivial-garbage](https://github.com/trivial-garbage/trivial-garbage)  - 便携式终结器、弱哈希表和弱指针 API. 公共区域.
* [trivial-utf8](https://common-lisp.net/project/trivial-utf-8/)  - 一个用于执行基于 UTF-8 的 I/O 的小型库.  BSD.


Contributing
============
随时欢迎您的贡献！ 请提交拉取请求或创建
将新框架、库或软件添加到列表中的问题.

我们（尝试）遵守的规则如下：

- 默认情况下，将库添加到其部分的末尾.
- 绝对事实上的库，如 BordeauxThreads 或 Quicklisp，
  应用 ⭐ 表示（Unicode 代码 U+2B50）.
- 两个范围非常相似的库应该并排，或者在一个
  他们自己的部分.
- 根据您的经验和现状进行一些策划
  图书馆的文档. 我们*不*旨在列出所有现有
  CL 库（请参阅 Cliki）也不列出每个
  “流行”库（参见 Quicklisp 统计）.
- 因此，我们最喜欢的库标有 (`1F44D`
  统一码字符）. 另请参阅中的标志说明
  介绍.


[2]: http://www.gnu.org/copyleft/gpl.html
[3]: http://www.gnu.org/software/classpath/license.html
[4]: https://common-lisp.net/project/armedbear/faq.shtml#qa
[5]: http://unlicense.org/
[6]: http://www.gnu.org/software/clisp/impnotes.html
[8]: http://opensource.franz.com/preamble.html
[9]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[11]: http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html
[13]: http://www.sbcl.org/manual/index.html#ANSI-Conformance
[14]: https://directory.fsf.org/wiki/License:Expat
[15]: https://directory.fsf.org/wiki/License:BSD_3Clause
[16]: https://www.quicklisp.org/beta/
[17]: https://directory.fsf.org/wiki/License:BSD_2Clause
[20]: http://www.cs.northwestern.edu/academics/courses/325/readings/graham/graham-notes.html
[21]: http://www.goodreads.com/book/show/1175730.Object_Oriented_Programming_in_Common_LISP
[22]: https://en.wikipedia.org/wiki/ISC_license
[33]: https://directory.fsf.org/wiki/License:Zlib
[39]: https://directory.fsf.org/wiki?title=License:FreeBSD
[47]: https://directory.fsf.org/wiki/License:CPLv1.0
[51]: https://directory.fsf.org/wiki/License:ArtisticLicense2.0
[54]: https://directory.fsf.org/wiki/License:Boost1.0
[59]: https://directory.fsf.org/wiki/License:EPLv1.0
[71]: https://github.com/Shinmera/plump
[72]: https://github.com/Shinmera/lquery
[89]: https://directory.fsf.org/wiki/License:Apache2.0
[156]: http://letoverlambda.com/
[157]: http://norvig.com/paip.html
[176]: https://github.com/gwkkwg/lift/blob/master/COPYING
[188]: https://github.com/triclops200/quickapp
[200]: https://opensource.org/licenses/MIT
[201]: https://github.com/google/lisp-koans
[205]: https://www.postgresql.org/about/licence/
[206]: http://www.gigamonkeys.com/book/
[207]: https://opensource.org/licenses/bsd-license.php
[208]: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[209]: http://www.eclipse.org/legal/epl-v10.html
[210]: https://common-lisp.net/project/linedit/license.html
[agpl3]：https://directory.fsf.org/wiki/License:AGPL-3.0
