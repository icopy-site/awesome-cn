<div class="github-widget" data-repo="CodyReichert/awesome-cl"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">
  <a href="https://awesome-cl.com" target="_blank">
    <img src="https://i.imgur.com/jLVXhpc.png">
  </a>
</div>

## Awesome Common Lisp [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Assertible status](https://assertible.com/apis/102e334d-f9a8-4565-9353-7572de775cae/status?api_token=8b55a286830323effb)](https://assertible.com/docs/guide/deployments)

一个精选的 _awesome_ Common Lisp 库列表.

对于很棒的*软件*，请参阅 [lisp-lang.org's success stories](http://lisp-lang.org/success/) 和 [awesome-cl-software](https://github.com/azzamsa/awesome-cl-software) 列表.

此处列出的所有库都可以从 [Quicklisp][16] 获得，除非
另有说明. 标有⭐的那些是如此广泛和
他们成为社区标准的坚实基础. 你不会错
他们.  Quicklisp、BordeauxThreads 和
这样的. 标有 a 的库是我们喜欢和想要的库
在 Awesome-cl 列表中进行推广. 他们被证明是可靠的，他们可以解决
一个比社区标准更好的问题，但它们并不像
广泛的，或不被认为是稳定的. 例如，我们更喜欢
Cl-Who 上的喷丝板.

添加新内容！ 见 [contributing](#contributing) 添加内容的部分
list.

这是根据 GNU 自由文档许可证发布的 - 其文本
在 LICENSE 文件中提供. 这个存储库也被镜像到
[NotABug](https://notabug.org/CodyReichert/awesome-cl) - **完全免费**（如自由）
 Github 的替代品. 优先考虑[自由软件][13]和
对实物资源无害的卖家.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->


<!-- markdown-toc end -->


Audio
=====

* [Open Music](https://github.com/openmusic-project/OM6)  - 可视化编程、计算机辅助组合环境.  [GPL3][2].
* [OM7](https://github.com/openmusic-project/om7)  - OpenMusic 可视化编程和计算机辅助作曲环境的新实现，包括对图形界面、计算模式和与外部软件库的连接的大量改进.  [GPL3][2].
* [Incudine](http://incudine.sourceforge.net/)  - Common Lisp 的音乐/DSP 编程环境. 从头开始设计软件合成器或声音插件很有用. 它也是一种作曲工具，可以产生在样本级别可控的高质量声音，定义和重新定义数字信号处理器和动态音乐结构.
* [cl-collider](https://github.com/byulparan/cl-collider) - A
[SuperCollider](http://supercollider.github.io/)  CommonLisp 的客户端. 与 [tutorial](https://github.com/defaultxr/cl-collider-tutorial) 和 [live coding demos](https://www.youtube.com/watch?v=xzTH_ZqaFKI) . 公共区域.
* [csound](https://github.com/csound/csound)  - 声音和音乐计算系统. 包括用于 Common Lisp 的 CFFI 和 FFI 接口.
* [CLM](https://ccrma.stanford.edu/software/clm/)  - Common Lisp Music 是 Music V 系列中的音乐合成和信号处理包. 它提供与 Stk、Csound、SuperCollider、PD、CMix、cmusic 和 Arctic 几乎相同的功能 — 创建和操纵声音的功能集合，主要针对作曲家（无论如何在 CLM 的情况下）.
* [cl-patterns](https://github.com/defaultxr/cl-patterns)  - 一个通过 Lisp 代码创作音乐的系统，深受 SuperCollider 模式系统的启发，旨在实现其中的大部分内容，但以更健壮、表现力、一致、反思和 lispy 的方式. 通过 SuperCollider 输出音频，初步支持 Incudine，通过 ALSA 支持 MIDI.
* [cl-openal](https://github.com/zkat/cl-openal)  - OpenAL 音频库的绑定. 公共区域.
* [Common Music](https://github.com/ormf/cm) - 的存储库
Common Music 的古代版本（版本 2.12.0），大概是最后一个
在 Common Lisp 上运行的版本可以追溯到 2007-09 年左右，之前
Common Music 的工作转移到（基于方案的）cm3.
* [Slippery Chicken](https://github.com/mdedwards/slippery-chicken/)  - 通过 Lilypond 输出 Midi、Common Music Notation、pdf 乐谱和通过 Common Lisp Music 输出声音的算法作曲库.  [GPL3][2].
* [Common Music Notation](https://ccrma.stanford.edu/software/cmn/)  - Common Music Notation (CMN) 提供了一组功能来分层描述乐谱. 公共区域.
* [cm-incudine](https://github.com/ormf/cm-incudine)  - 扩展 Common Music 2 的实时功能.  GPL2.
* [Mégra](https://github.com/the-drunk-coder/megra)  - 一种使用可变阶马尔可夫链和其他一些随机恶作剧制作音乐的迷你语言.  [GPL3][2].
* [Music](https://github.com/MegaLoler/Music) - Lisp 中的音乐表达框架，侧重于音乐理论（从头开始构建，与普通音乐无关）.
* [rq](https://github.com/openmusic-project/RQ) - OpenMusic（版本 6.10 及更高版本）中的节奏转录库. [demo video](https://www.youtube.com/watch?v=XVEllB0TtVs) .  [GPL3][2].
* [scheduler](https://github.com/byulparan/scheduler)  - Common Lisp 的基于时间的音乐事件调度程序.  [Apache2.0][89].
* [mixalot](https://github.com/ahefner/mixalot)  - 松散耦合的 mp3、ogg vorbis、flac 音频库集合. 用于 [Shuffletron music player](https://github.com/ahefner/shuffletron) .  [麻省理工][200].
* [osc](https://github.com/zzkt/osc)  - 开放声音协议的实施.  [LGPL2.1][11].
* [Harmony](https://shirakumo.github.io/harmony)  - 实时声音处理和回放系统.  [zlib][33].


构建系统
=============

* ⭐[ASDF](https://common-lisp.net/project/asdf/)  - 另一个系统定义工具；  Common Lisp 的构建系统.  [外籍人士][14].  Quicklisp（见 [library manager](#library-manager)) 在引擎盖下使用 ASDF.
  * [known ASDF extensions](https://common-lisp.net/project/asdf/#extensions)，例如 `asdf-system-connections`，它允许您指定在加载两个其他系统时自动加载的系统，以连接它们.
* [asdf-linguist](https://github.com/eudoxia0/asdf-linguist)  - ASDF 的扩展.  [外籍人士][14].
* [asdf-viz](https://github.com/guicho271828/asdf-viz)  - 一种可视化 ASDF 系统的库依赖关系、函数调用图和类继承的工具.  [LLGPL][8].

也可以看看：

* [modularize](https://github.com/Shinmera/modularize)  - Common Lisp 的模块化框架.  [zlib][33].
  * 提供一个公共接口来隔离主要的应用程序组件.
  * 例如，通过添加模块定义选项，您可以引入机制将模块在功能上联系在一起，相互挂钩等.
  * 充当 `defpackage` 的包装器并集成到 ASDF 中.

编译器、代码生成器
==========================

APL
---

* [April](https://github.com/phantomics/april)  - 编译为 Common Lisp 的 APL 编程语言（其子集）. 用一行 APL 替换数百行数字运算代码.  [Apache2][89].


C、C++
------

* [cmacro](https://github.com/eudoxia0/cmacro) - C 的 Lisp 宏.[MIT][200].
* [C-mera](https://github.com/kiselgra/c-mera)  - 源到源编译器，利用 Lisp 的宏系统对类 C 语言进行元编程.  [GPL3][2].
* [lispc](https://github.com/eratosthenesia/lispc) - 一种强大的 C 语言“lispsy”宏语言.[MIT][200].
* [with-c-syntax](https://github.com/y2q-actionman/with-c-syntax)  - 一个将 C 语言语法引入 Common Lisp 的有趣包.  （是的，我认为这个包不是用于实际编码的.）WTFPL 许可证.
* [ecrepl](https://gitlab.common-lisp.net/ecl/ecrepl)  - C 语言的交互式 REPL.  [BSD_2条款][17].
* [Software-Evolution-Library](https://github.com/GrammaTech/sel)  - SEL 支持软件的编程修改和评估（使用 Clang、编译的汇编器和链接的 ELF 二进制文件的 C/C++ 支持）.  [GPL3][2].

Cryptography
============

* ⭐ [Ironclad](https://github.com/sharplispers/ironclad)  - Common Lisp 的加密函数库. 不被认为是安全的，但对于消息摘要功能仍然有用.  [外籍人士][14].
* [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts)  - 常见加密快捷方式的集合.  [zlib][33].
* [trivial-ssh](https://github.com/eudoxia0/trivial-ssh)  - SSH 客户端库.  [外籍人士][14].
* [cl-ssh-keys](https://github.com/dnaeon/cl-ssh-keys)  - 用于生成和解析 OpenSSH 密钥的 Common Lisp 系统.  [BSD_3条款][15].
* [cl-bcrypt](https://github.com/dnaeon/cl-bcrypt)  - 用于解析和生成 bcrypt 密码哈希的 Common Lisp 系统.  [BSD_3条款][15].
  * 也可以看看 [cl-pass](https://github.com/eudoxia0/cl-pass)，使用 pbkdf2.

Cryptocurrencies
================

* [bp](https://github.com/rodentrabies/bp)  - Common Lisp 中的比特币协议组件.  [麻省理工][200].
* [cl-monero-tools](https://github.com/glv2/cl-monero-tools)  - 使用 Monero 加密货币的 Common Lisp 工具箱.  [GPL3][2]. 不在 Quicklisp 中.
* [emotiq](https://github.com/emotiq/emotiq)  - 具有创新的自然语言智能合约方法的下一代区块链.  [麻省理工][200].
* [peercoin-blockchain-parser](https://github.com/glv2/peercoin-blockchain-parser)  - 解析包含在文件中的区块链并将其部分数据导出到文本文件、SQL 脚本或数据库. 它还可以使用点点币守护进程的 RPC 作为数据源而不是区块链文件来创建数据库.  LGPL3. 不在 Quicklisp 中.
* [peercoin-calculator](https://github.com/glv2/peercoin-calculator)  - 本程序为您提供在 10 分钟、24 小时、31 天、90 天和 1 年内生成 POS 或 POW 区块的概率，以及可以预期的奖励.  Qt 中的图形用户界面.  [GPL3][2]. 不在 Quicklisp 中.
* [peercoin-vote](https://github.com/glv2/peercoin-vote)  - 基于区块链数据（地址和余额）的投票系统.  [GPL3][2]. 不在 Quicklisp 中.

也可以看看 [legochain](https://github.com/defunkydrummer/legochain)，一个简单的教育区块链.

Database
========

* [cl-yesql](https://github.com/ruricolist/cl-yesql)  - SQL 语句以 SQL 语法存在于它们自己的文件中，并作为函数导入到 Lisp 中. 您不限于 DSL 支持的功能. 基于 Clojure 的 Yesql.  [麻省理工][200].

ORMs
----

* ⭐ [clsql](http://www.cliki.net/CLSQL)  - 具有 Common Lisp 接口的 SQL 数据库.  [LLGPL][8].
* 👍 [mito](https://github.com/fukamachi/mito) - Common Lisp 的 ORM，具有迁移、关系和 PostgreSQL 支持 [LLGPL][8].
  * [mitho-auth](https://github.com/fukamachi/mito-auth), 用于使用授权的混合类
  * [mito-attachment](https://github.com/fukamachi/mito-attachment)，用于 RDBMS 之外的文件管理的混合类.
* [cl-dbi](https://github.com/fukamachi/cl-dbi)  - 一个独立于数据库的 Common Lisp 接口.  [LLGPL][8].
  * [dbd-oracle](https://github.com/sergadin/dbd-oracle)  - 用于 CL-DBI 的 Oracle 数据库驱动程序.  [LLGPL][8].
* [crane](https://github.com/eudoxia0/crane)  - 另一个 ORM.  [外籍人士][14].
* [datafly](https://github.com/fukamachi/datafly)  - 一个轻量级的数据库库.  [3 条款 BSD][15].
* [sxql](https://github.com/fukamachi/sxql)  - 用于生成 SQL 的 DSL.  [3 条款 BSD][15].

持久对象数据库
---------------------------

* [bknr.datastore](https://github.com/hanshuebner/bknr-datastore) - RAM 中基于 CLOS 的 lisp-only 数据库，具有事务日志持久性. [Manual](https://www.common-lisp.net/project/bknr/html/documentation.html) .  [执照][208].
  * 另请参阅 [good introductory blog post](https://ashok-khanna.medium.com/persistent-in-memory-data-storage-in-common-lisp-b-k-n-r-37f8ae76042f)
  * 使用 bknr.datastore 的示例 Web 应用程序： [screenshotbot-oss](https://github.com/screenshotbot/screenshotbot-oss).
* [ubiquitous](https://github.com/Shinmera/ubiquitous)  - 提供易于使用的持久配置存储的库.  [zlib][33].
* [cl-prevalence](https://common-lisp.net/project/cl-prevalence/)  - 内存数据库系统. 对象普遍性的实现，其中业务对象在内存中保持活动状态，事务被记录下来以供系统恢复. [github fork](https://github.com/40ants/cl-prevalence) .  [LLGPL][8].
  * 也可以看看 [cl-prevalence-multimaster](https://github.com/40ants/cl-prevalence-multimaster)，以同步多个 cl-prevalence 系统状态.
* [cl-naive-store](https://gitlab.com/Harag/cl-naive-store)  - 一个天真的持久化，在内存中（延迟加载），索引，Common Lisp 的文档存储.  [麻省理工][200].
  - 看 [the introductory blog post](https://zaries.wordpress.com/2022/05/31/cl-naive-store/)
  - 我们敢于添加：作者公司用于生产（ASTN 集团，参见 awesome-lisp-companies）

也可以看看 [Clache](#caching)，可以将任何对象保存在磁盘上.


图数据库
---------------

* [cl-agraph](https://github.com/vseloved/cl-agraph)，最小客户端 [AllegroGraph](https://allegrograph.com/) .  AllegroGraph 是一种水平分布的、多模型（文档和图）、实体-事件知识图谱技术. 它是专有的，有一个免费版本，限制为 500 万个三元组.
* [neo4cl](https://github.com/equill/neo4cl)  - 用于与 Neo4J 交互的库. 将 Cypher 查询发送到 Neo4J 服务器，并将响应解码为对 CL 处理有用的内容.  [Apache2][89].
  * 有可能： [cl-neo4j](https://github.com/kraison/cl-neo4j) - 一个瘦的 neo4j RESTFUL 客户端界面.
* [vivace-graph](https://github.com/kraison/vivace-graph-v3) - graph database & Prolog implementation. Takes design inspiration from CouchDB, neo4j and AllegroGraph. It implements an ACID-compliant object graph model with user-defined indexes and map-reduce views. It also implements a master / slave replication scheme for redundancy and horizontal read scaling. Querying the graph is accomplished via a number of Lisp methods or via a Prolog-like query language. [MIT][200].
  * "I have used Vivace Graph as an online catalog for millions of products, as the back end for a complex, adaptable VoIP-based IVR, as well as data store for several complex big data analysis systems, and finally as the engine for two recommender systems." (issue #23)
  * “为什么 vivace graph 这么快？我一直在将它与基于 SQL 的方法和 Neo4j 进行比较，vivace graph 快得多.”

并且：

* [restagraph](https://github.com/equill/restagraph)  - 一个使用数据库中定义的模式为 Neo4j 数据库动态生成 REST API 的应用程序.  [GPL3][2].
* [facts](https://github.com/cl-facts/facts)  - 内存图形数据库，具有事务和回滚、日志记录/重放和转储/加载到/从磁盘.  BSD 风格的许可证 (ISC).


Wrappers
--------

* ⭐ [postmodern](http://marijnhaverbeke.nl/postmodern/)  - 用于与 PostgreSQL 交互的库.  [zlib][33].
* [cl-sqlite](https://github.com/dmitryvk/cl-sqlite)  - SQLite 的绑定. 公共区域.
* [cl-memcached](https://github.com/quasi/cl-memcached)  - Memcached 对象缓存系统的快速、线程安全接口.  [外籍人士][14].
* [cl-mongo](https://github.com/fons/cl-mongo)  - MongoDB 客户端.  [外籍人士][14].
* [cl-redis](https://github.com/vseloved/cl-redis)  - Redis客户端.  [外籍人士][14].
* [cl-disque](https://github.com/CodyReichert/cl-disque)  - 客户磁盘.  [BSD 3 条款][15].
* [cl-rethinkdb](https://github.com/orthecreedence/cl-rethinkdb)  - RethinkDB 客户端.  [外籍人士][14].
* [cl-mango](https://github.com/cmoore/cl-mango/)  - 极简主义的 CouchDB 2.x 数据库客户端.  BSD_3条款.
  * 也可以看看 [clouchdb](https://common-lisp.net/project/clouchdb/)  - 用于与 CouchDB 交互的库.  [FreeBSD][39].
* [lmdb](https://github.com/antimer/lmdb) - 绑定到 [LMDB](http://www.lmdb.tech/doc/)，闪电内存映射数据库，一个具有多版本并发控制的 ACID 键值数据库.
* [cl-ndbapi](https://github.com/datagraph/cl-ndbapi) - 绑定到的 C++ NDB API [RonDB](https://www.rondb.com/), “世界上最快的键值存储”, by [Dydra](https://dydra.com/home) .  GPLv2.

迁移工具
---------------

* [cl-migratum](https://github.com/dnaeon/cl-migratum)  - 一个为执行数据库模式迁移提供便利的系统，旨在与各种数据库一起工作.  [BSD_3条款][15].
* [postmodern-passenger-pigeon](https://github.com/fisxoj/postmodern-passenger-pigeon/)  - 后现代的迁移管理器. 未指定许可证.


给第三方
----------------

* [dyna](https://github.com/Rudolph-Miller/dyna)  - AWS DynamoDB ORM.  [麻省理工][200].
* [cl-influxdb](https://github.com/mmaul/cl-influxdb/)  - 时间序列数据库 InfluxDB 的接口.  [麻省理工][200].
* [pzmq](https://github.com/orivej/pzmq)  - ZeroMQ 4.0+ Common Lisp 绑定. 未经许可.

Tools
-----

* ⭐ [pgloader](https://github.com/dimitri/pgloader)  - PostgreSQL 的数据加载工具.  [PostgreSQL 许可证][205].


数据结构
===============

* 👍 [str](https://github.com/vindarel/cl-str)  - 现代、简单且一致的字符串操作库.  [麻省理工][200].
* 👍 [FSet](https://common-lisp.net/project/fset)  - 一个功能性的集合论集合数据结构库.  [LLGPL][8].
* [trivial-extensible-sequences](https://github.com/Shinmera/trivial-extensible-sequences) - 可扩展序列协议的可移植性库（[SBCL documentation](http://www.sbcl.org/manual/#Extensible-Sequences) ).  [zlib][33].
* [bst](https://github.com/glv2/bst)  - 二叉搜索树.  [GPL3][2].
* [pileup](http://nikodemus.github.io/pileup/)  - 用于 Common Lisp 的可移植、高性能和线程安全的二进制堆.  [麻省理工][200].
* [sycamore](https://github.com/ndantam/sycamore)  - 一个快速的、纯函数式的数据结构库.  [BSD_3条款][15].
* [genhash](https://github.com/pnathan/genhash)  – 使用通用方法的 API 实现哈希表. 公共区域.
* [cl-ctrie](https://github.com/danlentz/cl-ctrie) -
无锁、并发、键/值索引，具有高效的内存映射持久性和快速瞬态存储模型.  [麻省理工][200].
* [cl-data-structures](https://github.com/sirherrbatka/cl-data-structures)  - 数据结构和算法的可移植集合（主要是字典和序列，具有一些统计功能）.  [BSD][15].
* [listopia](https://github.com/Dimercel/listopia)  - 受 Haskell 的 Data.List 启发的列表操作库.  [LLGPL][8].
* [hash-set](https://github.com/samebchase/hash-set/) - 在 CL 哈希表 [The Unlicense][5] 之上实现哈希集的便捷库
* [bit-smasher](https://github.com/thephoeron/bit-smasher)  - 用于处理位向量、位向量算术和类型转换的 Common Lisp 库.  [麻省理工][200].
* [cl-containers](https://common-lisp.net/project/cl-containers/) - 一个广泛的数据结构和实用程序库 - 队列、树、堆、双向链表、集合、包……[MIT][200]
* [cl-competitive](https://github.com/privet-kitty/cl-competitive)  - 用于竞争性编程的 Common Lisp 算法集合. 公共领域、CCO 或 MIT.

访问数据结构：

* 👍 [access](https://github.com/AccelerationNet/access/)  - 对大多数常见数据结构的一致和嵌套访问.  [BSD_3条款][15].
* [modf](https://github.com/smithzvk/modf) - 用于函数式编程的类似 setf 的宏.

其他数据结构：

* [bitfield](https://github.com/marcoheisig/bitfield)  - 有效地将几个有限集或小整数表示为单个非负整数.  [麻省理工][200].


码头工人图像
=============

* [cl-docker-images](https://common-lisp.net/project/cl-docker-images/) - 适用于 Windows (amd64) 和 Alpine 和 Debian（amd64、arm64、arm/v7）[BSD_2Clause][17] 上的 ABCL、CCL、ECL 和 SBCL 的 Docker 镜像.
* [base-lisp-image](https://github.com/40ants/base-lisp-image) - 根据
  带有 SBCL 或 CCL 和最新版本的 Common Lisp 项目的 Docker 镜像
  ASDF、Qlot 和罗斯威尔.


外部函数接口，语言互操作
=============================================

## C ##

* ⭐ [CFFI](https://github.com/cffi/cffi)  - 便携、易于使用的 C 外部函数接口.  [外籍人士][14].
* 👍[cl-autowrap](https://github.com/rpav/cl-autowrap)  - 自动将头文件解析为 CFFI 定义.  [FreeBSD][39].
* [cl-bindgen](https://github.com/sdilts/cl-bindgen)  - 用于从 C 头文件创建 Common Lisp 语言绑定的命令行工具和库.  [麻省理工][200].
* [cl-gobject-introspection](https://github.com/andy128k/cl-gobject-introspection) - [Gobject Introspection](https://gi.readthedocs.io/en/latest/) 外国金融机构. 调用 C 库的自动绑定.  [BSD][15]. 生成一个 lisp 接口 [gir2cl](https://github.com/kat-co/gir2cl) .  [LGPL3][9].
* [cl-cxx-jit](https://github.com/Islam0mar/CL-CXX-JIT)  - Common Lisp 和 C++ 与 JIT 的互操作.  [麻省理工][200].

## Clojure

* [ABCLJ](https://github.com/lsevero/abclj)  - 非常简单的 Clojure 到 Common lisp 互操作.  EPL-2.0.

开发中：

* [Cloture](https://github.com/ruricolist/cloture) - Common Lisp 中的 Clojure.

&gt; Cloture 处于非常早期（pre-alpha）阶段，但它已经取得足够的进展来加载 clojure.test，允许测试套件实际用 Clojure 编写.

另请参阅这些库：

* [cl-oju](https://github.com/eigenhombre/cl-oju/)  - 一些习语，主要与序列有关，是我在编写 Common Lisp 时想念的.  [麻省理工][200].
* [clj-con](https://github.com/dtenny/clj-con)  - Common Lisp 中的 Clojure 风格的并发操作.  [麻省理工][200].
* [clj-re](https://github.com/dtenny/clj-re/) - Clojure 风格的正则表达式函数.

## Erlang ##

* [CLERIC](https://github.com/flambard/CLERIC)  - 一个 Common Lisp Erlang 接口.  Erlang 分发协议的实现，可与 erl_interface 和 jinterface 相媲美.  [麻省理工][200].

## Java ##

* [cl+j](https://common-lisp.net/project/cl-plus-j/)  - 通过 CFFI 连接到 JVM 的基于 JNI 的接口. 在 Quicklisp 上不可用. 不能可靠地与所有实现一起工作.  [外籍人士][14].

## Objective-C ##

* [objc-lisp-bridge](https://github.com/fiddlerwoaroof/objc-lisp-bridge)  - 用于与 Objective-C 和 Cocoa 交互的便携式阅读器和桥梁.  [麻省理工][200].

## Python ##

* [burgled-batteries](https://github.com/pinterface/burgled-batteries)  - Python 和 Common Lisp 之间的桥梁. 目标是 Lisp 程序可以使用 Python 库. 在 Quicklisp 上不可用.  [麻省理工][200].
* [cl4py](https://github.com/marcoheisig/cl4py)  - 库 cl4py（发音为 clappy）允许 Python 程序调用 Common Lisp 库.  [麻省理工][200].
* [py4cl](https://github.com/bendudson/py4cl)  - 允许 Common Lisp 代码访问 Python 库的库. 它基本上是 cl4py 的逆向.  [麻省理工][200].

也可以看看 [async-process](https://github.com/cxxxr/async-process/).

* [cl-python](https://github.com/metawilm/cl-python)  - Python 在 Common Lisp 中的实现.  [LLGPL][8]，未在积极开发中.


## .Net Core

* [Bike](https://github.com/Lovesan/bike)  - 一个跨平台的 .Net Core 接口.  [麻省理工][200].

## Miscellaneous ##

* [Foil](http://foil.sourceforge.net/)  - 一个外来对象接口； 与 JVM 和 CLI 一起工作. 在 Quicklisp 上不可用.  [CPL 1.0][47].
* [CLOCC's elisp.lisp](https://sourceforge.net/p/clocc/hg/ci/default/tree/src/cllib/elisp.lisp) - Common Lisp 中的 Emacs Lisp.
   * Emacs Lisp 语言的实现作为 Common Lisp 包.  [1999]
   * 不试图重新实现 Emacs 中提供的函数库来操作缓冲区和其他相关对象，因此它专注于“纯”Emacs Lisp 语言； 但它能够运行 Emacs 日历的非 UI 部分.  (S. Monnier, M. Sperber)


游戏开发
================

* [Trial](https://github.com/shirakumo/trial)  - Trial 是一个 OpenGL 游戏引擎，非常注重模块化. 它应该提供一个大型工具包，其中包含有用的点点滴滴，您可以从中创建游戏.  [zlib][33].
  * 这 [Kandria](https://kandria.com/) 游戏是用试用版构建的.
* [trivial-gamekit](https://borodust.org/projects/trivial-gamekit/getting-started/)  – 使用这个小型框架，您将能够制作简单的 2D 游戏：绘制基本的几何形状、图像和文本、播放声音以及收听鼠标和键盘输入.  [麻省理工][200].
* [virality](https://github.com/bufferswap/ViralityEngine) - 用 Common Lisp [MIT][200] 编写的基于组件的游戏引擎.
* [Xelf](https://gitlab.com/dto/xelf/)  - 可扩展的游戏库. 在 Quicklisp 上不可用.  [GNU LGPL2.1][11].

Utilities:

* [cl-gamepad](https://shirakumo.github.io/cl-gamepad)  - 在 Windows、Mac OS 和 Linux 上访问游戏手柄和操纵杆.  [zlib][33].
* [cl-mpg123](https://shirakumo.github.io/cl-mpg123) 和 [cl-out123](https://shirakumo.github.io/cl-out123), bindings libraries for libmpg123 和 libout123 respectively, giving you fast 和 easy to use mp3 decoding 和 cross-platform audio output. [zlib][33].

Graphics
========

这些库用于处理图形，而不是制作 GUI（即小部件工具包），它们有自己的部分.

* ⭐ [Sketch](https://github.com/vydd/sketch)  - 用于创建电子艺术、图形等的 CL 框架.  [麻省理工][200].
* [common-cv](https://github.com/byulparan/common-cv)  - CommonLisp 的 OpenCV（开源计算机视觉库）绑定库. 未指定许可证.
* [cl-cairo2](https://github.com/rpav/cl-cairo2)  - 开罗绑定.  [提升 1.0][54]
* [cl-gd](http://weitz.de/cl-gd/)  - 提供 GD 图形库接口的库.  [FreeBSD][39].
* [cl-horde3d](https://github.com/anwyn/cl-horde3d/)  - FFI 绑定到 Horde3D 图形库. 在 Quicklisp 上不可用.  [EPL 1.0][59]
* [cl-jpeg](https://github.com/sharplispers/cl-jpeg)  - 基线 JPEG 编码器和解码器库.  [3 条款 BSD][15].
* [cl-liballegro](https://github.com/resttime/cl-liballegro)  - 与 Allegro 5 游戏编程库的接口和绑定.  [zlib][33].
* [cl-opengl](https://github.com/3b/cl-opengl)  - CFFI 绑定到 OpenGL、GLU 和 GLUT API.  [3 条款 BSD][15].
* [cl-sdl2](https://github.com/lispgames/cl-sdl2)  - 使用 C2FFI 绑定 SDL2.  [外籍人士][14].
* [cl-svg](https://github.com/wmannis/cl-svg)  - 用于生成 SVG 文件的基本库.  [外籍人士][14].
* [CLinch](https://github.com/BradWBeer/CLinch)  - 用于 OpenGL 的 Common Lisp 2D/3D 图形引擎.  [FreeBSD][39].
* [donuts](https://github.com/tkych/donuts)  - Common Lisp 的 Graphviz 接口.  [外籍人士][14].
* [dufy](https://github.com/privet-kitty/dufy)  - 各种颜色模型中的精确颜色操作和转换.  [麻省理工][200].
* [lispbuilder-sdl](https://github.com/lispbuilder/lispbuilder)  - 一组 SDL 绑定.  [外籍人士][14].
* [lisp-magick-wand](https://github.com/TBRSS/lisp-magick-wand)  - ImageMagick 绑定.  [BSD][15]. 不在 Quicklisp 中.
* [okra](https://www.common-lisp.net/project/okra/manual.html)  - CFFI 绑定到食人魔. 在 Quicklisp 上不可用.  [3 条款 BSD][15].
* [opticl](https://github.com/slyrus/opticl)  - 用于表示和处理图像的库.  [BSD_2条款][17].
* [Varjo](https://github.com/cbaggers/varjo)  - Lisp 到 GLSL 翻译器.  [BSD_2条款][17].
* [Vecto](http://www.xach.com/lisp/vecto/)  - 简单的矢量绘图库.  [FreeBSD][39].
* [zpng](http://www.xach.com/lisp/zpng/)  - 用于创建 PNG 文件的库.  [FreeBSD][39].
* [pngload-fast](https://git.mfiano.net/mfiano/pngload)  - 便携式 Common Lisp 中的 PNG（便携式网络图形）图像格式解码器，强调速度.  [麻省理工][200].
* [cl-cuda](https://github.com/takagi/cl-cuda)  - 在 Common Lisp 程序中使用 NVIDIA CUDA 的库.  [LLGPL][8].


GUI
===

有关 GUI 工具包的概述和教程，请参阅 [the Cookbook/GUI](https://lispcookbook.github.io/cl-cookbook/gui.html).

* [LispWork's CAPI](http://www.lispworks.com/products/capi.html)  - 一个便携式 GUI 工具包，带有移动运行时. 专有，但附带免费版本.
* [Allegro's Common Graphics](https://franz.com/products/allegro-common-lisp/acl_gui_tools.lhtml) - 用于为 Windows、Mac 和 Linux 编写窗口化 GUI 的函数库. 专有免费版本.
  - 自 Allegro 10.1（2022 年 3 月）起，IDE 和 Common Graphics 工具包 [runs in the browser](https://franz.com/ftp/pri/acl/cgjs/doc.html).
* 👍 [Qtools](https://github.com/Shinmera/qtools/)  - 基于 CommonQt 的 Qt 工具包.  [zlib][33] 还有 [Qtools-ui](https://github.com/Shinmera/qtools-ui) （预制 UI 组件），与 [videos](https://www.youtube.com/watch?v=KwASFOhYta4&index=7&list=PLkDl6Irujx9Mh3BWdBmt4JtIrwYgihTWp).
* ⭐ [CommonQt](https://github.com/commonqt/commonqt)  - 通过 QtSmoke 为 Qt4 绑定的 Common Lisp.  [FreeBSD][39].
* ⭐ [ltk](http://www.peter-herth.de/ltk/)  - Tk 工具包的绑定.  [LLGPL][8] 或 [GNU LGPL2.1][11].
  * [LTk Examples](https://peterlane.netlify.app/ltk-examples/) - 为 tkdocs 教程提供 LTk 示例.
  * [LTk Plotchart](https://peterlane.netlify.app/ltk-plotchart/)  - 一个围绕 tklib/plotchart 库的包装器，用于与 LTk 一起工作. 这包括 20 多种不同的图表类型（xy 图、甘特图、3d 条形图等）.
  * [nodgui](https://notabug.org/cage/nodgui)  - Tk 工具包的绑定，基于 Ltk，带有语法糖和其他小部件.  [LLGPL][8].
* [IUP](https://github.com/lispnik/iup/) - CFFI 绑定到 [IUP](https://www.tecgraf.puc-rio.br/iup/) Portable User Interface library (pre-ALPHA). IUP is cross-platform (Windows, macOS, GNU/Linux, with new Android, iOs, Cocoa and Web Assembly drivers), has many widgets, has a small api and is actively developed.
* [cl-gtk4](https://github.com/bohonghuang/cl-gtk4)  - 用于 Common Lisp 的 GTK4/Libadwaita/WebKit 绑定.  [LGPL3][9].
* [cl-cffi-gtk](https://github.com/crategus/cl-cffi-gtk)  - 绑定 GTK+3.  [GNU LGPL2.1][11].
  - 教程： [Learn Common Lisp by Example: GTK GUI with SBCL](https://dev.to/goober99/learn-common-lisp-by-example-gtk-gui-with-sbcl-5e5c)
* [cl-gtk2](https://github.com/dmitryvk/cl-gtk2)  - GTK+2 的绑定.  [LLGPL][8].
* [ceramic](https://ceramic.github.io/)  - 使用 Electron 的桌面网络应用程序.  [外籍人士][14].
  * [Electron-lisp-boilerplate](https://github.com/mikelevins/electron-lisp-boilerplate) - A rudimentary boilerplate for building Electron apps with embedded Lisp helper processes.
  * 电子应用骨架： [electron-sbcl-sqlite](https://github.com/mikelevins/electron-sbcl-sqlite/)
   * 注意：在 Electron 中嵌入 lisp web 应用程序的主要思想是将 lisp web 服务器作为异步进程启动，并将 Electron 窗口指向本地主机 URL. 就是这样.

但这还不是全部：

* [CocoaInterface](https://github.com/plkrueger/CocoaInterface/) -
 Clozure Common Lisp 的 Cocoa 接口. 构建 Cocoa 用户界面
windows 动态使用 Lisp 代码并绕过典型的 Xcode
过程. 它有
[good documentation and a tutorial](https://github.com/plkrueger/CocoaInterface/blob/master/Documentation/UserInterfaceTutorial.pdf).
* [McCLIM](https://common-lisp.net/project/mcclim/)  - Common Lisp 接口管理器的实现，版本 II.  [GNU LGPL2.1][11].
* [cl-webkit](https://github.com/joachifm/cl-webkit)  - 绑定到 WebKitGTK+. 还向应用程序添加 Web 浏览功能，充分利用 WebKit 浏览引擎的强大功能.  [麻省理工][200].
* [ftw](https://github.com/fjames86/ftw)  - 一个 Win32 GUI 库.  [麻省理工][200].
* [eql, eql5, eql5-android](https://gitlab.com/eql)  - 嵌入式Qt4和Qt5 Lisp，嵌入ECL，可嵌入Qt. 将 EQL5 移植到 Android 平台.  [麻省理工][200].
* [bodge-nuklear](https://github.com/borodust/bodge-nuklear) - 包装在 [Nuklear](https://github.com/vurtun/nuklear) immediate mode GUI library. [MIT][200].
* [vk](https://github.com/JolifantoBambla/vk)  - Vulkan API 的通用 Lisp/CFFI 绑定.  [麻省理工][200].

其他实用程序：

* [file-select](https://github.com/Shinmera/file-select)  - 调用本机系统文件对话框以选择或创建文件的库. 自由.

另见这个 [demo to use Java Swing from ABCL](https://github.com/defunkydrummer/abcl-jazz).

Mobile
------

* [LispWork's mobile runtime](http://www.lispworks.com/products/lw4mr.html)  - Android 和 iOS. 所有权.
* [LQML](https://gitlab.com/eql/lqml)  - 轻量级 ECL 绑定到从 EQL5 派生的 QML（Qt5 和 Qt6）.  LGPL 和公共领域.

另请参阅下面的 MOCL，CL 作为移动设备（iOS、Android 和 OSX）的库.


Implementations
===============

* ⭐ [SBCL](http://www.sbcl.org/index.html)  - 钢铁银行通用 Lisp.  CMUCL 的一个分支； 编译成机器码.  [标准合规性][13]. 公共领域，某些部分在 [Expat][14] 和 [3-clause BSD][15] 下.
  * 也可以看看： [sbcl-librarian](https://github.com/quil-lang/sbcl-librarian)  - SBCL 的动态库交付工具. 创建可从 C 或 Python 调用的共享库. 麻省理工学院. [Blog post](https://mstmetent.blogspot.com/2022/04/using-lisp-libraries-from-other.html). [Full example](https://github.com/quil-lang/sbcl-librarian/tree/main/example).
* ⭐ [CCL](https://github.com/CodyReichert/awesome-cl/blob/master///ccl.clozure.com/)  - Clozure Common Lisp； 仅编译器实现，生成本机代码.  [LLGPL][8].
* [ECL](https://common-lisp.net/project/ecl/)  - 可嵌入的 Common Lisp； 编译为 C. [GNU LGPL2.1][11].
* [ABCL](https://common-lisp.net/project/armedbear/)  - Armed Bear Common Lisp； 以 JVM 为目标，编译为字节码.  [标准一致性][4].  [GNU GPL3][2] 与 [类路径例外][3].
* [CLASP](https://github.com/drmeister/clasp)  - 一个新的 Common Lisp 实现，它使用 LLVM 与 C++ 库和程序无缝互操作以编译为本机代码. 这使得 Clasp 可以利用大量现有的库和程序，例如科学计算生态系统之外的库和程序.  [LGPL2.1][11]（及其他）.

Proprietary:

* [LispWorks](http://www.lispworks.com/) - an integrated cross-platform development tool for Common Lisp.
* [Allegro CL](https://franz.com/products/allegro-common-lisp/) - 提供带有许多扩展的完整 ANSI Common Lisp 标准.
* [MOCL](https://wukix.com/mocl) - CL 作为移动设备（iOS 和安卓）和 OSX 的库.

也可以看看：

* [CMUCL](https://github.com/CodyReichert/awesome-cl/blob/master///www.cons.org/cmucl/)  - 卡内基梅隆大学的实施. 公共区域.  SBCL 是 CMUCL 的一个分支.
* [GNU CLISP](http://www.clisp.org/)  - GNU 实现； 包含一个编译器和一个解释器.  [标准一致性][6].  [GNU GPL3][2]. 他们发展 [https://gitlab.com/gnu-clisp/clisp](https://github.com/CodyReichert/awesome-cl/blob/master/on Gitlab).
* [Corman Lisp](https://github.com/sharplispers/cormanlisp)  - 用于在 Intel 平台上运行的 Microsoft Windows 的 Common Lisp 开发环境.  [麻省理工][200].

JSON
====

* [jonathan](https://github.com/Rudolph-Miller/jonathan)  - 一个 JSON 编码器和解码器.  [麻省理工][200].
* [cl-json](https://github.com/sharplispers/cl-json)  - 高度可定制的 JSON 编码器和解码器.  [麻省理工][14].
* [jsown](https://github.com/madnificent/jsown)  - JSON 格式的读写器.  [外籍人士][14].
* [shasht](https://github.com/yitzchak/shasht)  - 用于 Kzinti 的 Common Lisp JSON 读写.  [麻省理工][14].
   - “Shasht 是我特别喜欢的两个新库之一，它已经在 quicklisp 中.它速度快，可以正确处理 null，它可以对 CLOS 对象、结构和哈希表进行编码.它还可以进行增量编码.” 萨布拉克罗尔顿.
* [json-mop](https://github.com/gschjetne/json-mop)  - 用于桥接 CLOS 和 JSON 对象的元类.  [麻省理工][200].
* [cl-json-pointer](https://github.com/y2q-actionman/cl-json-pointer)  - 一个 JSON 指针实现.  [麻省理工][200].

另见这个 [extensive comparison](https://sabracrolleton.github.io/json-review) JSON 库.

YAML
====

* [cl-yacclyaml](https://github.com/mabragor/cl-yaclyaml)  - 纯 lisp YAML 处理器（加载器，但还不是转储器）.  [GPL3][2].
* [cl-yaml](https://github.com/eudoxia0/cl-yaml.git)  - 一个建立在 libyaml 之上的 YAML 解析器和发射器.  [麻省理工][200].


语言扩展
===================

* ⭐ [alexandria](https://common-lisp.net/project/alexandria/)  - 通用实用程序库. 公共区域.
* 👍 [serapeum](https://github.com/TBRSS/serapeum/)  - 另一个通用实用程序库.  [外籍人士][14].
* [rutils](https://github.com/vseloved/rutils)  - Common Lisp 的激进但合理的句法实用程序.  [麻省理工][200].
* [generic-cl](https://github.com/alex-gutev/generic-cl/)  - 标准 Common Lisp 函数（相等、比较、算术、对象、迭代器、序列等）的通用函数接口.  [麻省理工][200]. 又见更轻量级 [generic-comparability](https://github.com/pnathan/generic-comparability) .  [LLGPL][8].
* [anaphora](https://common-lisp.net/project/anaphora/)  - 照应宏的集合. 公共区域.
* ⭐ [trivia](https://github.com/guicho271828/trivia/)  - 优化的模式匹配库.  [LLGPL][8].
* [arrow-macros](https://github.com/hipeta/arrow-macros)  - 类似 Clojure 的线程宏.  [麻省理工][200].
* [hu.dwim.walker](https://github.com/hu-dwim/hu.dwim.walker)  - 代码 walker 和 unwalker（又名 AST 解析器和反解析器）.  [BSD][15]. 也可以看看 [this blog post](http://40ants.com/lisp-project-of-the-day/2020/04/0044-hu.dwim.walker.html).

可移植层
------------------

大量可移植层 [is collected here](https://shinmera.github.io/portability/) . 这里是其中的一些：

* [trivial-arguments](https://github.com/Shinmera/trivial-arguments)  - 一个可移植的库，用于检索函数的参数列表.  [zlib][33].
* [definitions](https://github.com/Shinmera/definitions)  - 通用定义内省库. 它使您能够检索与标志符（例如符号、包和一般名称）关联的定义或绑定.  [zlib][33].
* [dissect](https://shinmera.github.io/dissect)  - 当许多项目使用“trivial-backtrace”系统时，它只是给他们一个带有回溯的字符串，Dissect 允许您捕获、步进并完全检查各种 Lisp 实现的堆栈跟踪. 对于日志记录和其他自动继续执行的情况也非常有用，但是当前堆栈的信息存储在某个地方仍然很有用.  [zlib][33].

更改语法
-------------------

* [cl21](https://github.com/cl21/cl21)  - 将 Common Lisp 带入 21 世纪的实验项目.  [外籍人士][14].
* [clamp](https://github.com/malisper/Clamp)  - Arc 语言相对于 Common Lisp 的简洁明了.  [艺术许可证 2.0][51].
  * 还 [arc-compat](https://github.com/g000001/arc-compat)  - 弧兼容包.  Perl 基金会的艺术许可证 2.0.
* [cl-syntax](https://github.com/m2ym/cl-syntax)  - 读者语法约定.  [LLGPL][8].
* [cl-2dsyntax](http://www.cliki.net/cl-2dsyntax)  - 缩进敏感的阅读器系统. 在 Quicklisp 上不可用. 公共区域.
* [cl-annot](https://github.com/m2ym/cl-annot)  - Common Lisp 的类似 Python 的注释.  [LLGPL][8].
  * [cl-annot-revisit](https://github.com/y2q-actionman/cl-annot-revisit/)  - 重新实施 cl-annot.  WTFPL.
* [cl-reader](https://github.com/digikar99/reader) - 实用程序库
旨在为 lambda、映射、访问器提供读取器宏，
哈希表和哈希集.  [麻省理工][200].

对于字符串：

* ⭐ [cl-interpol](https://github.com/edicl/cl-interpol/)  - 一组阅读器修改以允许字符串插值.  [BSD][15].
* [mstrings](https://git.sr.ht/~shunter/mstrings)  - 阅读器宏，提供视觉上吸引人的多行块.  M 字符串修剪前导空格、将行连接在一起等 [BSD_3Clause][15].
* [pythonic-string-reader](https://github.com/smithzvk/pythonic-string-reader)  - 受 Python 的三引号字符串启发的简单且不显眼的读表修改.  [BSD_3条款][15].
* [cl-heredoc](https://github.com/outergod/cl-heredoc) - A ["heredocs"](https://github.com/outergod/cl-heredoc) dispatcher. [GPL3][2]. Allows to write: `#>eof>Write whatever (you) "want", no matter what characters, until the magic end sequence has been reached.eof`


CLOS 扩展
---------------

* ⭐ [closer-mop](http://cliki.net/closer-mop)  - 纠正许多缺失或不正确的 MOP 功能的兼容层.  [外籍人士][14].
* [defclass-std](https://github.com/EuAndreh/defclass-std)  - 快速编写 DEFCLASS 表格的快捷方式宏.  [LLGPL][8].
* [specialization-store](https://github.com/markcox80/specialization-store/)  - 基于类型的通用函数. 简化的 BSD 许可证变体.
* [filtered-functions](https://github.com/pcostanza/filtered-functions)  - 允许使用任意谓词来选择和应用方法.  [麻省理工][200].
* [inlined-generic-function](https://github.com/guicho271828/inlined-generic-function) -
将静态调度的速度带到 CLOS.  [LLGPL][8].
* [static-dispatch](https://github.com/alex-gutev/static-dispatch)  - 允许静态地（在编译时）而不是动态地（运行时）执行标准通用函数分派. 这类似于 C++ 和 Java 等语言中所谓的“重载”.  [麻省理工][200].
* [dynamic-mixins](https://github.com/rpav/dynamic-mixins)  - 简单、动态的类组合.  [BSD_2条款][17].
* [fast-generic-functions](https://github.com/marcoheisig/fast-generic-functions)  - 密封您的通用函数以获得额外的性能提升.  [麻省理工][200].
* [polymorphic functions](https://github.com/digikar99/polymorphic-functions)  - 一种函数类型，用于分派类型而不是类，部分支持分派可选和关键字参数类型. 仍处于试验阶段（2021 年 5 月）.  [麻省理工][200].
   - 多态函数根据提供给它的参数类型进行分派. 这有助于调度专门的数组以及用户定义的类型.
  - 有关专业化存储和快速通用功能的差异，请参阅其自述文件.

并且：

* [slot-extra-options](https://github.com/some-mthfka/slot-extra-options)  - 允许您构建一个元类，该元类又允许您在其类中指定额外的插槽选项.  [LGPL3][9].

功能扩展
-------------------

* [cl-hooks](https://github.com/scymtym/architecture.hooks/)  - 挂钩扩展点机制（众所周知，例如，来自 GNU Emacs）.  LGPL.
* [method-hooks](https://gitlab.com/Gnuxie/method-hooks)  - 当 CLOS 方法组合只允许每个方法有一个挂钩时，该库允许任意数量的挂钩.  Mozilla 公共许可证.
* [cl-advice](https://github.com/lisp-mirror/budden-tools/blob/213ab2b52a1b0c0b496efd30c3b5143f5c8e1ff2/cl-advice/README.md)  - SBCL、CCL、LispWorks 和 Allegro 的可移植层建议库的尝试. 不在 Quicklisp 中.
* [nhooks](https://github.com/atlas-engineer/nhooks) - 具有重要改进的挂钩（扩展点）的增强实现.

Iteration
---------

* ⭐ [iterate](https://common-lisp.net/project/iterate/)  - 可扩展和 Lispier 的 Common Lisp 的迭代构造.  [麻省理工][200].
* [for](https://shinmera.github.io/for/)  - 一个简洁、轻便且可扩展的迭代宏. 与循环不同，它是可扩展和明智的，并且与迭代不同，它不需要代码遍历并且更容易扩展.  [zlib][33].
* [series](https://series.sourceforge.net/)  - 完全没有任何运行时损失的函数式风格.  [麻省理工][200].
* [gmap](https://github.com/slburson/misc-extensions/blob/master/src/gmap.lisp)  - 一个简洁且可扩展的迭代工具，具有与 FSet 良好集成的优势（请参阅数据结构部分），因为它是由同一作者编写的. 在 Quicklisp 中作为 `misc-extensions` 的一部分. 公共区域.
* [trivial-do](https://github.com/yitzchak/trivial-do/)  - Common Lisp 的附加 dolist 样式宏.  [麻省理工][200].
* [doplus](https://github.com/alessiostalla/doplus) – 另一个可扩展的迭代库，类似于 :for.
* [snakes](https://github.com/BnMcGn/snakes)  - 用于 Common Lisp 的 Python 样式生成器. 包括一个 itertools 端口.  [Apache2][89].
* [picl](https://github.com/anlsh/picl)  - Python 的 itertools 包的（几乎）完整端口，在适用的情况下具有惰性，并且不依赖于 cl-cont.  [麻省理工][200].
* [gtwiwtg](https://cicadas.surf/cgit/colin/gtwiwtg.git/about/)  - 一个懒惰的序列库. 类似于“系列”但不完整. 然而，它有一个“现代”API，其中包含“take”、“filter”、“for”、“fold”等易于使用的东西.


Lambda 简写
-----------------

* [fn](https://github.com/cbaggers/fn)  - 几个 lambda 速记宏.  `(fn* (+ _ _)) --&gt; (lambda (_) (+ _ _))`. 公共区域.
* [f-underscore](https://gitlab.common-lisp.net/bpm/f-underscore)  - 一个小型函数式编程实用程序库.  `(f_ (+ _ _)) -&gt; (lambda (_) (+ _ _))`. 公共区域.
* [cl-punch](https://github.com/windymelt/cl-punch/)  - 类似 Scala 的匿名 lambda 文字.  `(mapcar ^(* 2 _) &#39;(1 2 3 4 5))`.  [麻省理工][200].


另见 CL21 和 [Rutils](https://github.com/vseloved/rutils).


非确定性、逻辑编程
------------------------------------

* [cl-prolog2](https://github.com/guicho271828/cl-prolog2)  - 来自 Common Lisp 的 ISO Prolog 实现的通用接口.  [麻省理工][200].
* [Screamer](https://github.com/nikodemus/screamer) - 增加普通
  Lisp 几乎具有 Prolog 和
  约束逻辑规划
  语言. [Blog post](https://chriskohlhepp.wordpress.com/reasoning-systems/specification-driven-programming-in-common-lisp/)
  解决欧拉计划难题.  [麻省理工][200].
* [Screamer+](https://github.com/yakovzaytsev/screamer-plus)  - 增加 SCREAMER 的表现力.  [麻省理工][200].
* [Temperance](https://github.com/sjl/temperance)  - 逻辑编程.  [麻省理工][200]. 专注于性能，考虑到一般游戏玩法.

响应式编程
--------------------

* [Cells](https://github.com/kennytilton/cells)  - 数据流编程范式的实现，CLOS 的反应式电子表格式表现力. 用于构建一个 [algebra learning system](http://tiltontec.com/) . 和 [documentation](https://github.com/stefano/cells-doc/) .  Lisp LGPL.

合同编程
--------------------

* [quid-pro-quo](https://github.com/sellout/quid-pro-quo) - 合同
   Eiffel&#39;s Design by Contract™ 风格的编程库. 公共区域.

Typing
------

* 👍 [Coalton](https://github.com/coalton-lang/coalton/)  - 一种高效的静态类型函数式编程语言，可增强 Common Lisp.  [麻省理工][200].
* 👍 [trivial-types](https://github.com/m2ym/trivial-types)  - 提供缺失但重要的类型定义，例如 `proper-list`、`association-list`、`property-list` 和 `tuple`.  [LLGPL][8].
* [defstar](https://bitbucket.org/eeeickythump/defstar/src/master/)  - 一组宏，用于轻松包含 lambda 列表中参数的类型声明.  [GNU GPL3][2]

也可以看看：

* [typo](https://github.com/marcoheisig/Typo/)  - 用于 Common Lisp 的可移植类型推理库.  [麻省理工][200].


学习和教程
=====================

## Online ##

Beginner
--------

* [Learn X in Y minutes - Where X = Common Lisp](https://learnxinyminutes.com/docs/common-lisp/) - 涵盖要点的小型 Common Lisp 教程.
* [Lisp Koans][201] - 该项目通过许多 Common Lisp 语言功能逐步指导学习者.
 * [Practical Common Lisp][206] - 一本很好的 Common Lisp 介绍性文字，带有实际示例. 更好地阅读 [a Firefox add-on](https://github.com/vale981/practical-cl-beautified).
* [Common LISP: A Gentle Introduction to Symbolic Computation](http://www.cs.cmu.edu/afs/cs.cmu.edu/user/dst/www/LispBook/index.html) - 很好的语言介绍.
* [Successful Lisp](http://successful-lisp.blogspot.com/) - 一本适合具有一定编程背景的初学者的好书.
* [Lisp Quickstart](https://cs.gmu.edu/~sean/lisp/LispTutorial.html) - 快速入门和编写 Common Lisp 代码的好教程.
* [Casting SPELs in LISP](http://www.lisperati.com/casting.html) - 一种在阅读漫画书的同时学习 LISP 的有趣方式.
   &gt; 感谢您支持我在 Udemy 上的工作. 另请注意，我会不时发布免费优惠券，而且 Udemy 经常提出大幅促销，但您也可以向我索取免费优惠券.

Intermediate
------------

* [The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/)
* [Lisp Tips](https://github.com/lisp-tips/lisp-tips/issues/)  - 包含有用提示和技巧的博客. 的延续 [Common Lisp tips](http://lisptips.com/).
* [Lisp project of the day](http://40ants.com/lisp-project-of-the-day/) - 展示许多 Lisp 库的博客.

Advanced
--------

 * [Let Over Lambda][156] - 一本关于高级宏技术的书. 前六章可在​​线获取.
* [On Lisp](http://www.paulgraham.com/onlisp.html) - Paul Graham 关于 Lisp 宏（和其他有趣的东西）的精彩书籍.
* [Programming Algorithms in Lisp](https://link.springer.com/book/10.1007/978-1-4842-6428-7) - 更新版本“[Programming Algorithms](https://leanpub.com/progalgs)&quot;; 在 Lisp 中使用数据结构和算法编写高效程序的综合指南.

编码平台
----------------

* [Codewars](https://docs.codewars.com/languages/commonlisp/) - 代码培训平台，支持 Common Lisp (SBCL).

Web开发
--------

* [Lisp for the Web](https://leanpub.com/lispweb) - 一本引导您分三层构建投票 Web 应用程序的书.
* [Lisp Web Tales](https://leanpub.com/lispwebtales) - 使用简单教程 [hunchentoot](http://edicl.github.io/hunchentoot/), [cl-redis](https://github.com/vseloved/cl-redis), [restas](https://github.com/archimag/restas), [SEXML](https://github.com/madnificent/SEXML), [Postmodern](https://github.com/marijnh/Postmodern)， 和更多.
* [Section on Web Development in The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/web.html) - 介绍性教程，涵盖 Web 服务器设置、路由、weblocks、模板、错误处理、打包、热重载、数据库连接和部署，以及当前 lisp Web 开发生态系统中的其他主题.

Reference
---------

* [Common Lisp Quick Reference](http://clqr.boundp.org/index.html)  - ANSI CL 规范的精简袖珍版. 可作为 PDF 下载.
* [CLHS](http://www.lispworks.com/documentation/lw50/CLHS/Front/index.htm)  - Common Lisp HyperSpec；  ANSI CL 标准，以超文本形式.
* [CLOS MOP specification](https://clos-mop.hexstreamsoft.com/) - 《元对象协议的艺术》第 5 章和第 6 章的现代公共领域在线版本
* [Common Lisp Standard Draft (pdf)](https://franz.com/support/documentation/cl-ansi-standard-draft-w-sidebar.pdf) - Common Lisp 规范的标准草案，格式良好的 PDF 格式，带有侧边栏.
* [Common Lisp the Language](http://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html) - ANSI 规范之前的 Common Lisp 原始标准.
* [Minispec](https://lamberta.github.io/minispec/)  - 更友好但不太完整的 CLHS 版本. 还包含一些常用 CL 库（例如 Alexandria）的文档.
* [Simplified Common Lisp reference](http://jtra.cz/stuff/lisp/sclr/index.html) - CLHS 的简化版本.
* [CDR](https://cdr.common-lisp.dev/)  - Common Lisp 文档存储库.  Common Lisp 社区感兴趣的文档库.  CDR 文档最重要的属性是它永远不会改变：如果您引用它，您可以确定您的引用将始终引用完全相同的文档.
  - Common Lisp 文档存储库位于 [Zenodo](https://zenodo.org/communities/cdr/).

## Offline ##

CLHS 可通过以下方式离线使用 [archive](https://github.com/CodyReichert/awesome-cl/blob/master/ftp://ftp.lispworks.com/pub/software_tools/reference/HyperSpec-7-0.tar.gz) 正如医生所说 [Dash](https://kapeli.com/dash), [Zeal](https://zealdocs.org/) 和 [Velocity](https://velocity.silverlakesoftware.com/).

Beginner
--------

* [Land of Lisp](http://landoflisp.com/) - 一个有趣的、面向游戏的 Common Lisp 介绍.
* [Practical Common Lisp][206] - 一本很好的 Common Lisp 介绍性文字，带有实际示例.

Intermediate
------------

* [ANSI Common Lisp](http://www.paulgraham.com/acl.html)  - 全面、实用地涵盖整个语言，并附有练习. 由于[一些注意事项][20]，不推荐作为入门文本.
* [Common Lisp Recipes](http://weitz.de/cl-recipes/)  - **Common Lisp Recipes** 是您在使用 Common Lisp 编写实际应用程序时可能遇到的问题的解决方案和答案的集合.  2015 年出版.

Advanced
--------

 * [Let Over Lambda][156] - 一本关于高级宏技术的书. 所有八章都可以在打印副本中找到.
* [Common Lisp 中的面向对象编程：CLOS 程序员指南][21] - 一本关于 CLOS 的古老但非常透彻的书.
* [Paradigms of Artificial Intelligence Programming: Case Studies in Common Lisp][157] - 一本关于人工智能编程的书，涵盖了一些高级 Lisp.

其他书籍
-----------

* [Building Problem Solvers](https://www.qrg.northwestern.edu/bps/readme.html) ([PDF](http://www.qrg.northwestern.edu/bps/BPS-Searchable.pdf)) 由 Ken Forbus 和 Johan de Kleer 合着，由麻省理工学院出版社免费提供——这是一本在标准人工智能文本中独一无二的书，结合了科学与工程、理论与工艺来描述 AI 推理系统的构建，并包括说明这些想法的代码.

Community
---------

* [/r/Common_Lisp](https://www.reddit.com/r/Common_Lisp/) - 关于 Common Lisp 的 subreddit
* [/r/learnlisp](https://www.reddit.com/r/learnlisp/) - 用于提出问题并获得有关 Lisp 的帮助的 subreddit
* [common-lisp.net](https://common-lisp.net)
* [lisp-lang.org](https://lisp-lang.org/)
* [Lisp Discord Server](https://discord.gg/hhk46CE)
* [#commonlisp](https://irclog.tymoon.eu/libera/%23commonlisp) 在 Libera Chat - 主要的 Common Lisp IRC 频道.
* [#lisp](https://irclog.tymoon.eu/libera/%23lisp) 在 Libera Chat - 所有 Lisp 方言的 IRC 频道.
* #clschool on Libera Chat - IRC channel for learning Common Lisp.
* #lispcafe on Libera Chat - IRC channel for off-topic discussions.
* [Common Lisp chat](https://chat.hexstreamsoft.com/) - 具有明确定义的规则和保留策略的 Keybase 团队.

图书馆经理
===============

 * ⭐ [Quicklisp][16] - 包含许多库的库管理器，具有简单的依赖管理.  [外籍人士][14].
  * [Quicklisp bundles](https://quicklisp.org/beta/bundles.html) - 独立的系统集，从 Quicklisp 导出并可在不涉及 Quicklisp 的情况下加载.
  * [redist](https://github.com/shirakumo/redist) - 生产 Quicklisp 发行版的设施.
* [CLPM](https://gitlab.common-lisp.net/clpm/clpm)  - Common Lisp 的包管理器，它努力将包管理器进程本身与使用它的客户端映像完全分开.  [BSD_2条款][17].
* [Ultralisp](http://ultralisp.org/)  - 一种 Quicklisp 发行版，每 5 分钟更新一次，只需单击一下即可将其项目添加到其中.  [BSD][15].
* 👍[Roswell](https://github.com/roswell/roswell)  - Lisp 实现安装程序、脚本启动器等.  [麻省理工][200].
* [Qlot](https://github.com/fukamachi/qlot)  - 项目本地库安装程序，类似于 Bundler 或 Carton.  [外籍人士][14].
* [Quicksys](https://lisp.com.br/quicksys/)  - 从多个 Quicklisp 发行版安装系统.  [麻省理工][200].
* [Quickutil](https://github.com/tarballs-are-good/quickutil)  - 实用程序管理器，类似于 Quicklisp，但用于小型实用程序而不是整个库.  [3 条款 BSD][15].

可能有帮助：

* [quick-patch](https://github.com/tdrhq/quick-patch/)  - 无需使用 git 子模块即可轻松覆盖 quicklisp 项目.  MPL-2.0.
* [print-licenses](https://github.com/vindarel/print-licenses)  - 打印项目及其依赖项使用的许可证.  [麻省理工][200].

### Interfaces to other package managers

* [linux-packaging](https://gitlab.com/ralt/linux-packaging)  - 使用单个 ASDF 声明为您的应用程序构建 .deb、.rpm 或 .pkg 包. 在后台使用 fpm.  [麻省理工][200].
* [qldeb](https://github.com/ralt/qldeb) - Quicklisp 系统到 debian 软件包，以及 [deb-packager](https://github.com/ralt/deb-packager) （通过定义一个 s-expression 来简单地创建一个 debian 包）和一个介绍性 [blog post](http://margaine.com/2015/12/22/quicklisp-packagecloud-debian-packages.html) .  [麻省理工][200].
* [ql-to-deb](https://github.com/dimitri/ql-to-deb)  - 从 Quicklisp 版本更新 cl-* debian 软件包.  WTFPL.
* [dh-quicklisp-buildapp](https://github.com/ralt/dh-quicklisp-buildapp)  - debhelper 实用程序，让您几乎毫不费力地将基于 quicklisp 的 Common Lisp 代码编译成 .deb 中的 buildapp 二进制文件.  [麻省理工][200].
* [cl-brewer](https://github.com/can3p/cl-brewer)  - 用于（命令行）常见 lisp 应用程序的自制公式生成器. 公共区域.
* [flatpack-common-lisp](https://gitlab.com/ralph-schleicher/flatpak-common-lisp) - 一个 BuildStream 项目，用于为 Common Lisp 应用程序构建基于 Flatpak 的运行时环境.
* [alien-works-delivery](https://github.com/borodust/alien-works-delivery)  - 用于将 Common Lisp 应用程序作为可执行包交付的 WIP 系统. 目前它仅支持 Linux 的 AppImage 格式和 Windows 的 MSIX，但也计划支持 Android 的 .APK 以及更高版本的 MacOSX 和 iOS 捆绑格式.


也可以看看 [asdf-sbcl](https://github.com/smashedtoatoms/asdf-sbcl)，通用包管理器的插件.


机器学习
================

* [MGL](https://github.com/melisgl/mgl)  - 用于反向传播神经网络、玻尔兹曼机、高斯过程等的机器学习库.  [麻省理工][200].
  * 某些部分最初由 Ravenpack International 提供.
  - 被其使用 [author](https://github.com/melisgl) 到 [win](https://github.com/melisgl/higgsml) 希格斯玻色子机器学习挑战赛.
* [clml](https://github.com/mmaul/clml)  - 最初由日本公司 Mathematicl Systems Inc. 开发. 与 [tutorial](https://mmaul.github.io/clml.tutorials//2015/08/08/CLML-Time-Series-Part-1.html) .  [LLGPL][8].
* [antik](https://www.common-lisp.net/project/antik/)  - Common Lisp 科学和工程计算的基础.  GPL. 还 [mgl-mat](https://github.com/melisgl/mgl-mat) 和 [LLA](https://github.com/tpapp/lla).

图片来源：borretti.me [State of CL Ecosystem 2015](http://borretti.me/article/common-lisp-sotu-2015#machine-learning).


自然语言处理
===========================

* [cl-nlp](https://github.com/vseloved/cl-nlp)  - 自然语言处理工具集.  [Apache2.0][89].
* [babel2](https://github.com/lucas8/Babel2/) - 流体构造语法实现、计算框架和基于统一的语法形式[Apache2.0][89].
* [sparser](https://github.com/ddmcdonald/sparser)  - 英语自然语言理解系统.  [日食][209].



网络和互联网
====================

See [Cliki](http://www.cliki.net/Web) 更多.

HTTP客户端
------------
* 👍 [Dexador](https://github.com/fukamachi/dexador)  - 一个 HTTP 客户端，旨在取代 Drakma.  [麻省理工][200].
* [Carrier](https://github.com/orthecreedence/carrier)  - 构建在 cl-async 和 fast-http 之上的轻量级异步 HTTP 客户端.  [麻省理工][200].
* [fast-http](https://github.com/fukamachi/fast-http)  - Common Lisp 的快速 HTTP 请求/响应解析器.  [麻省理工][200].


HTTP 服务器
------------

* ⭐ [Hunchentoot](http://weitz.de/hunchentoot/)  - 网络服务器.  [2-子句 BSD][207]
* 👍[Clack](https://github.com/fukamachi/clack)  - 受 Rack 和 WSGI 启发的 Web 应用程序环境.  [LLGPL][8]. 为所选网络服务器提供统一接口（默认为 Hunchentoot）. 随着更多 [getting started guide](https://jasom.github.io/clack-tutorial/posts/getting-started-with-clack/).
* [zaserve](https://github.com/gendl/aserve) - Franz Inc. [LLGPL][8] 的 AllegroServe 便携式叉子.
* [wookie](https://github.com/orthecreedence/wookie) - Asynchronous HTTP server. [Expat][14].
* [woo](https://github.com/fukamachi/woo)  - 基于 libev 的快速非阻塞 HTTP 服务器.  [麻省理工][200].
* [cl-http2-protocol](https://github.com/akamai/cl-http2-protocol)  - 草案 14 中 HTTP/2 协议的纯 Common Lisp 传输不可知实现.  [麻省理工][200].

### Hunchentoot plugins

* 👍 [easy-routes](https://github.com/mmontone/easy-routes)  - Hunchentoot 之上的路线处理系统. 它支持基于 HTTP 方法的调度、从 url 路径提取参数、装饰器、从路由名称生成 url 等 [MIT][200].
* [hunchentoot-cgi](https://github.com/slyrus/hunchentoot-cgi)  - 用于从 hunchentoot 网络服务器执行 CGI 脚本的库.  [BSD][207].
* [hunchentoot-multi-acceptor](https://github.com/moderninterpreters/hunchentoot-multi-acceptor/)  - 使用单个端口在单个 hunchentoot 接受器上路由多个域（虚拟主机）.  [Apache2.0][89].
* [hunchentoot-errors](https://github.com/mmontone/hunchentoot-errors)  - 使用请求和会话信息增强 Hunchentoot 错误页面和日志.  [麻省理工][200].

也可以看看：

* [cl-tbnl-gserver-tmgr](https://github.com/mdbergmann/cl-tbnl-gserver-tmgr)  - 基于 Hunchentoot Gserver 的任务管理器.  cl-gserver 是一个类似演员的消息传递库（参见下面的“演员模式”）. 实验性的.

### Clack plugins

* [tiny-routes](https://github.com/jeko2000/tiny-routes)  - 针对 Clack 的 Common Lisp 微型路由库.  [BSD_3条款][15].
* [clack-errors](https://github.com/eudoxia0/clack-errors)  - Clack 的错误页面中间件.  [LLGPL][8].
* [clath](https://github.com/BnMcGn/clath) - 单点登录
   Clack 的中间件. 它允许使用 OAuth1.0a、OAuth2 进行基本登录
  和 OpenID. 在撰写本文时，它支持来自
  谷歌、推特、领英、StackExchange、Reddit 和 Github.  [Apache2.0][89].
* [clack-pretend](https://github.com/BnMcGn/clack-pretend) - 一个测试
  和 clack 的调试工具.  [Apache2.0][89].
* [hermetic](https://github.com/eudoxia0/hermetic)  - 基于 Clack 的 Web 应用程序的安全性.  [外籍人士][14].
* [live-reload](https://github.com/knobo/live-reload)  - 用于 clack 的实时重载原型.  [LLGPL][8].
* [clack-static-asset-middleware](https://github.com/fisxoj/clack-static-asset-middleware)  - 用于 clack 的缓存破坏静态资产中间件.  [麻省理工][200].

对于路由，我们还可以使用 Snooze（见下文）.

网络框架
--------------

* [Caveman](https://github.com/fukamachi/caveman)  - 一个强大的网络框架.  [LLGPL][8].
  示例项目： [Quickdocs](https://github.com/quickdocs)
* [ningle](https://github.com/fukamachi/ningle)  - 超微型网络框架.  [LLGPL][8].
  - [jingle](https://github.com/dnaeon/cl-jingle) - 在ningle的基础上，增加了一些花里胡哨的东西，比如中间件.
    - 包括 OpenAPI 和 Swagger UI 演示.
* [radiance](https://github.com/Shirakumo/radiance)  - Web 应用程序环境和框架.  [zlib][33].

以 REST 为中心的框架：

* 👍 [Snooze](https://github.com/joaotavora/snooze)  - 一个 RESTful 网络框架.  Web 服务器不可知. 目前支持 Hunchentoot 和 Clack. 路由只是函数，HTTP 条件只是 Lisp 条件.  [LLGPL][8].
* [cl-rest-server](https://github.com/mmontone/cl-rest-server)  - 用于编写 REST Web API 的库. 具有模式验证、日志注释、缓存、权限或身份验证、通过 Swagger 的文档等功能验证 [MIT][200].

请参阅下面的 OpenAPI、OData 和其他库.

### Isomorphic web frameworks

* [CLOG](https://github.com/rabbibotton/clog)  - Common Lisp 无所不在的 GUI. 使用网络技术为本地或远程应用程序生成图形用户界面.  [BSD_3条款][15].
  - CLOG 基于 GNOGA 的思想，GNOGA 是作者为 Ada 编写的框架，自 2013 年起用于商业生产代码.
* [Interactive SSR](https://github.com/interactive-ssr/client/blob/master/main.org/)  - ISSR 允许您在不编写客户端脚本的情况下制作交互式网页. 不需要有关 Javascript 或 DOM 的知识.
  - 它与 Phoenix LiveView 或 Hotwire 没有什么不同.
* [Weblocks](https://github.com/40ants/reblocks)  - 一个基于小部件的框架，带有内置的“解决 JavaScript 问题”的 ajax 更新机制.  [LLGPL][8].


解析 html
------------
 * [Plump][71] - 一个宽松的 HTML/XML 解析器，可以容忍格式错误的标记.  [zlib][33]. 最好与 [lquery][72] 和 [clss](https://github.com/Shinmera/CLSS).

查询 HTML/DOM
-----------------
 * [lquery][72] - 一个类似 jQuery 的 HTML/DOM 操作库.  [zlib][33].

另请参阅下面的 XML 部分以了解 xpath 库等.


HTML 生成器和模板
-----------------------------

* 👍 [spinneret](https://github.com/ruricolist/spinneret)  - Common Lisp HTML5 生成器.  [外籍人士][14].
* ⭐ [cl-who](http://weitz.de/cl-who/)  - 令人尊敬的 HTML 生成器.  [FreeBSD][39].
* ⭐ [Djula](https://github.com/mmontone/djula)  - Django 模板引擎到 Common Lisp 的端口.  [外籍人士][14].
  - [cl-djula-tailwind](https://github.com/rajasegar/cl-djula-tailwind) - 在 Djula 模板中使用 TailwindCSS 类，无需任何 JavaScript 或 Node.js 工具.
* [TEN](https://github.com/mmontone/ten)  - Djula 的完整性满足 Eco 的可用性.  [麻省理工][200].
* [eco](https://github.com/eudoxia0/eco)  - 快速、灵活、设计人员友好的模板引擎.  [外籍人士][14].
* [cl-closure-template](https://github.com/archimag/cl-closure-template)  - 谷歌闭包模板的实施，其中编译模板创建一个生成结果的函数.  [LLGPL][8].
* [flute](https://github.com/ailisp/flute)  - 一个易于组合的 HTML5 生成库，具有最简单的语法.  [麻省理工][200].
* [clip](https://shinmera.github.io/clip)  - 一个 HTML 模板处理器，其中的模板是用 HTML 编写的.  [zlib][33].
* [lsx](https://github.com/fukamachi/lsx/) 和 [markup](https://github.com/moderninterpreters/markup)  - 两个类似 JSX 的模板引擎，其中 HTML 标签是 Common Lisp 代码.  `markup` 带有一个 Emacs 包.

URI 处理
------------

* [quri](https://github.com/fukamachi/quri) - 另一个 URI 库
  常见的 Lisp. 支持用户信息、IPv6主机名、编码/解码
  实用程序，... [BSD_3Clause][15].
* [cl-slug](https://github.com/EuAndreh/cl-slug)  - 一个用于制作 slug 的小型库，主要用于 URI，在 CamelCase 中进行转换，删除重音和标点符号，适用于英语和其他语言.  [LLGPL][8].

Javascript
----------

* ⭐ [Parenscript](https://common-lisp.net/project/parenscript/)  - 从 Common Lisp 到 Javascript 的翻译器.  [3 条款 BSD][15]. 看 [Trident-mode](https://github.com/johnmastro/trident-mode.el)，一种提供与浏览器实时交互的 Emacs 模式.[未授权][5].
  * [paren6](https://github.com/BnMcGn/paren6/) - 一组用于 Parenscript 的 ES6 宏.
* [JSCL](https://github.com/jscl-project/jscl)  - 从第一天起就设计为自托管的 CL-to-JS 编译器. 缺少 CLOS、格式和循环.
* [CL-JavaScript](http://marijnhaverbeke.nl/cl-javascript/)  - 从 Javascript 到 Common Lisp 的翻译器. 在 Quicklisp 上不可用.  [外籍人士][14].
* [parse-js](http://marijnhaverbeke.nl/parse-js/) - 用于解析 ECMAScript 3 的包.[zlib][33].
* [Wuwei](https://github.com/mtravers/wuwei/)  - 用于构建基于 Ajax 的网页的工具包.  [麻省理工][200].
* [SmackJack](https://github.com/aarvid/SmackJack)  - 一个使用 parenscript 生成 javascript 和 hunchentoot（目前）作为 Web 服务器的 Ajax Common Lisp 库. 还允许服务器端 lisp 函数调用客户端 parenscript 函数.  [麻省理工][200].
* [remote-js](https://github.com/ceramic/remote-js)  - 将 JavaScript 从 Common Lisp 发送到浏览器.  [麻省理工][200].
* [sigil](https://github.com/BnMcGn/sigil)  - Javascript 命令行编译器和 REPL 的 Parenscript.  [麻省理工][200].

开发中：

* [Valtan](https://github.com/cxxxr/valtan) - Common Lisp 到 JavaScript 编译器.
* [JACL](https://tailrecursion.com/JACL/) - 用于 Web 浏览器平台的实验性 Lisp 系统，用于探索使用 Lisp 开发大型单页应用程序的新技术.


**React** 的实用程序：

* [cl-react](https://github.com/helmutkian/cl-react)  - 用于在 ReactJs 中构建 Web 应用程序的 Common Lisp (Parenscript) 实用程序. 麻省理工学院.
* [Panic](https://github.com/michaeljforster/panic) ，一个用于 React 的 Parenscript 库. 不在 Quicklisp 中.  [麻省理工][200]. 它是 [TodoMVC example](https://github.com/40ants/todomvc/blob/common-lisp-example/examples/common-lisp-react/src/app.lisp).
* [Parenscriptx](https://github.com/jasom/parenscriptx)  - 用于帮助生成反应代码的 Parenscript 宏.  [麻省理工][200].
* [jscl-react](https://github.com/nilesr/jscl-react)  - 一个使用 jscl 在普通 lisp 中编写反应组件的 Web 框架. 未指定许可证.


也可以看看：

* [trident-mode](https://github.com/johnmastro/trident-mode.el)，用于实时 Parenscript 交互的 Emacs 次要模式.


Deployment
----------

* 👍 [deploy](https://shinmera.github.io/deploy)  - 用于 Lisp 应用程序二进制部署的工具包，额外支持外部共享库.  [zlib][33].
* [heroku-buildpack-common-lisp](https://gitlab.com/duncan-bayne/heroku-buildpack-common-lisp)  - 使用 Roswell 编译 Common Lisp 应用程序的 Heroku buildpack.  LGPL3.
* [cube](https://github.com/xh4/cube)  - 用于从 Swagger 规范生成的 Common LISP 的 Kubernetes 客户端库.  [麻省理工][200].
* [s2i-lisp](https://github.com/container-lisp/s2i-lisp) - Source-to-Image builder image based on CentOS or alternatively RHEL7 for building Common LISP images for OpenShift (and also Docker). It features an up-to-date SBCL with Quicklisp installation, SLIME or SLY integration and allows customization via environment variables. [Apache2][89]
* [cl-aws-runtime-test](https://github.com/y2q-actionman/cl-aws-custom-runtime-test)  - 使用 Common Lisp (SBCL) 作为 AWS lambda 上的自定义运行时的示例.  WTFPL.

也可以看看：

- [Platform.sh](https://platform.sh/blog/2019/lisp/) 有 Common Lisp 支持，所以有 [OVH](https://docs.ovh.com/ie/en/web-paas/languages-lisp/) 通过他们的 Web PaaS 合作伙伴关系.
- [Heliohost](https://www.heliohost.org/) 免费托管解决方案.

Monitoring
----------

* [prometheus.cl](https://github.com/deadtrickster/prometheus.cl)  - Prometheus.io 客户端.  SBCL 和 Hunchentoot 指标（内存、线程、每秒请求数等）的 Grafana 仪表板.  [麻省理工][200].
  * [prometheus-g](https://github.com/40ants/prometheus-gc) - prometheus.cl 的扩展，它收集有关垃圾收集器状态的指标.
* [cl-sentry-client](https://github.com/mmontone/cl-sentry-client)  - 用于基于云的错误监控系统 Common Lisp 的哨兵客户端.  [麻省理工][200].
* [rollbar.lisp](https://github.com/adventuring/rollbar.lisp) - 接口 [Rollbar.com](https://rollbar.com/)，一个错误跟踪软件.


Websockets
----------

* 👍 [usocket](https://github.com/usocket/usocket)  - 一个可移植的 TCP 和 UDP 套接字接口.  [外籍人士][14].
* [Portal](https://github.com/charJe/portal)  - 用于 Common Lisp 的便携式 websockets，使用 usocket.  [LLGPL][8].
* [clws](https://github.com/3b/clws)  - CL 中的 websockets 服务器，基于 IOlib 和 libfixposix. 未指定许可证.
* [Hunchensocket](https://github.com/joaotavora/hunchensocket)  - 适用于 Common Lisp 的 RFC6455 兼容 WebSockets，作为 Hunchentoot 的扩展.  [麻省理工][200].
* [websocket-driver](https://github.com/fukamachi/websocket-driver) - 基于 Clack.

 *编者注：在撰写本文时，我们似乎还没有针对 Common Lisp 的全功能 websocket 实现. 但是，我们可以推荐 Portal，我们邀请您仔细检查 Hunchensocket 和 websocket-driver 的当前问题.*


网络开发实用程序
-------------------------

### Assets management

* [Rock](https://github.com/eudoxia0/rock) - 资产经理
  常见的 Lisp. 它基本上是 Bower 和
  网络资产.  [麻省理工][200].

### Browser tests

* [cl-webdriver-client](https://github.com/copyleft/cl-webdriver-client/) - WebDriver 的绑定库（支持 Selenium 4.0）.

### Form handling

* 👍 [cl-forms](https://github.com/mmontone/cl-forms)  - 用于 Common lisp 的 Web 表单处理库.  [麻省理工][200].

### User login and password management

* [cl-authentic](https://github.com/charJe/cl-authentic)  - Common Lisp（网络）应用程序的密码管理.  [LLGPL][8].
  - 安全密码存储：无明文，通过 ironclad 使用您选择的哈希算法，存储在 SQL 数据库中，
  - 使用一次性令牌的密码重置机制（适合邮寄给用户确认），
  - 可选地使用确认令牌创建用户（适用于邮寄给用户），
* [mito-email-auth](https://github.com/40ants/mito-email-auth) - 通过电子邮件向网站用户发送唯一代码，帮助他们验证网站用户的身份.

* [cl-cas](https://github.com/fferrere/cl-cas) - 一个图书馆来帮助 [CAS authenticaton](https://apereo.github.io/cas/6.0.x/protocol/CAS-Protocol.html) 到 Common Lisp Web 应用程序. 不在 Quicklisp 中.
  * [cas-middleware](https://github.com/fferrere/cas-middleware) - 穴居人的 CAS 身份验证中间件.
  * [cas-demo](https://github.com/fferrere/cas-demo) - 一个演示项目.

另请参阅上面的 mito-auth 和 Hunchentoot 和 Clack 插件.

### Web project skeletons and generators

* [cl-cookieweb](https://github.com/vindarel/cl-cookieweb)  - 用于启动 Web 项目的 Cookiecutter 模板.  [BSD_3条款][15]. 不在 Quicklisp 中.
  * 提供一个工作玩具网络应用程序，带有 Hunchentoot 网络服务器、简单路由、Djula 模板，使用 Bulma 设计样式，基于 SQLite，带有迁移、示例表定义和使用 FiveAM 的测试套件.
* [make-like](https://github.com/container-lisp/make-like)  - LIKE（Kubernetes + Emacs 中的 Lisp）应用程序的应用程序模板构建器.  [Apache2.0][51].
  * Makefile、podman 支持、GitHub Actions、Prometheus 指标支持、TOML 风格的 config.ini、预配置了健康检查的简易路由等.
* [cl-webapp-seed](https://github.com/rajasegar/cl-webapp-seed)  - 一个简单的网络应用样板. 使用 Hunchentoot、cl-who，可以轻松部署到 Heroku.  [麻省理工][200].

Others
------

* [css-lite](https://github.com/paddymul/css-lite)  - 一个 CSS 语法.  [外籍人士][14].
* [find-port](https://github.com/eudoxia0/find-port)  - 以编程方式查找开放端口.  [麻省理工][200].
* [Postmaster](https://github.com/eudoxia0/postmaster)  - 一个简单易用的 SMTP/IMAP 库.  [外籍人士][14].
* [cl-wget](https://github.com/cl-wget/cl-wget)  - 使检索大文件或镜像整个网站变得容易.  [AGPL-3.0][51].
* [trivial-download](https://github.com/eudoxia0/trivial-download)  - 下载文件.  [麻省理工][200].


### Email

* [trivial-imap](https://github.com/40ants/trivial-imap)  - 尝试简化使用 IMAP 服务器的一些常见情况，例如从服务器读取电子邮件. 邮局库（它是 Franz 的 cl-imap 的一个分支）的薄包装器.  [BSD][15].
* [cl-smtp](https://gitlab.common-lisp.net/cl-smtp/cl-smtp) - CL-SMTP 是一个简单的 lisp smtp 客户端.
* [sendgrid](https://github.com/vindarel/cl-sendgrid)  - 使用 Sendgrid 的 API 发送电子邮件.  [麻省理工][200].
* [mailgun](https://github.com/40ants/mailgun)  - 通过 mailgun.com 发布 HTML 电子邮件的薄包装器.  [无执照][5].
* [cl-ses](https://github.com/CodyReichert/cl-ses/)  - AWS SES 库.  [外籍人士][14].

### OpenAPI, OData, OpenRPC

* [apispec](https://github.com/cxxxr/apispec)  - 用于处理 Web API 请求和响应的 Common Lisp 库.  [BSD_3条款][15].
  - 采用 OpenAPI3 yaml 规范并允许验证和解析 HTTP 请求标头、参数和正文.
* [cl-odata-client](https://github.com/copyleft/cl-odata-client) - 用于访问的 Common Lisp 客户端库 [OData services](https://www.odata.org) .  [麻省理工][200].
* [OpenRPC](https://github.com/40ants/openrpc)  - Common Lisp 的 OpenRPC 实现.  [BSD][15].
  - 自动生成 OpenRPC 规范
   - 通过 OpenRPC 规范自动构建 JSON-RPC 客户端. 这包括创建 Common Lisp 类和用于发出 RPC 请求和返回本机 CL 对象的方法.
  - 所有 JSON 编组都在幕后完成.


### Static site generators

* [coleslaw](https://github.com/kingcons/coleslaw) 及其
  [coleslaw-cli](https://github.com/40ants/coleslaw-cli) - 灵活
  类似于 Frog、Jekyll 或 Hakyll 的 Lisp 博客软件.  [BSD][15].

### Third-party APIs

* [Aws-sign4](https://github.com/rotatef/aws-sign4) - 用于 Amazon Web Services 签名版本 4 的 Common Lisp 库.[GNU GPL3][2].
* [zs3](https://github.com/xach/zs3) - 用于使用亚马逊简单存储的库
服务 (S3) 和 CloudFront 服务.  [BSD][15].
* [north](https://shinmera.github.io/north)  - South (Simple OaUTH) 库的继承者，在客户端和服务器端实现了完整的 oAuth 1.0a 协议. 使用 North，您可以轻松成为 oAuth 提供者或消费者.  [zlib][33].
* [Ciao](https://github.com/kjinho/ciao)  - 一个易于使用的 Common Lisp OAuth 2.0 客户端库. 它是 Racket OAuth 2.0 客户端到 Common Lisp 的端口.  [LGPL3][9].
* [avatar-api](https://github.com/eudoxia0/avatar-api)  - 从 Google+、Gravatar 等获取头像.  [外籍人士][14].
* [chirp](https://github.com/Shinmera/chirp)  - 一个 Twitter 客户端库.  [zlib][33].
* [tooter](https://github.com/Shinmera/tooter)  - 为 Mastodon 实现完整 v1 REST API 协议的客户端库.  [zlib][33].
* [cl-irc](https://www.common-lisp.net/project/cl-irc/)  - IRC 客户端库.  [外籍人士][14].
* [cl-mediawiki](https://github.com/AccelerationNet/cl-mediawiki)  - MediaWiki api 的包装器.  [麻省理工][200].
* [cl-openid](https://github.com/cl-openid/cl-openid)  - OpenID 的实现.  [LLGPL][8].
* [cl-pushover](https://github.com/TeMPOraL/cl-pushover)  - 与 Pushover 的 Common Lisp 绑定.  [麻省理工][200].
* [humbler](https://github.com/Shinmera/humbler)  - 一个 Tumblr API 接口.  [zlib][33].
* [multiposter](https://github.com/Shinmera/multiposter)  - 同时发布到多个服务.  [zlib][33].
* [stripe](https://git.mfiano.net/mfiano/stripe)  - Stripe 支付系统的客户端.  [麻省理工][200].
* [lisp-pay](https://github.com/K1D77A/lisp-pay)  - 围绕各种支付处理器的包装器：Paypal、Stripe、Coinpayments 和 BTCPayServer.  [麻省理工][200].
* [lunamech-matrix-api](https://github.com/K1D77A/lunamech-matrix-api)  - 客户端 -&gt; 服务器矩阵 API 的完整包装器.  [麻省理工][200].


数值和科学
========================

* [maxima](http://maxima.sourceforge.net/)  - 计算机代数系统. 在 Quicklisp 上不可用.  [GNU GPL3][2].
  * [wxMaxima](https://wxmaxima-developers.github.io/wxmaxima/): 图形前端.
  * [Maxima on Android](https://play.google.com/store/apps/details?id=jp.yhonda), 使用 ECL 构建.
  * [Maxima on Jupyter](https://github.com/robert-dodier/maxima-jupyter)
  * 可以通过 [SageMath](https://www.sagemath.org/) 和 [KDE Cantor](https://apps.kde.org/cantor/) . 当然，对于 Emacs： [maxima-mode](https://gitlab.com/sasanidas/maxima) ([screenshot](https://community.linuxmint.com/img/screenshots/maxima-emacs.png)) 和 [maxima-interface](https://github.com/jmbr/maxima-interface) to ease the interface between Maxima 和 Common Lisp.
* [numcl](https://github.com/numcl/numcl)  - Common Lisp 中的 Numpy 克隆.  [LGPL3][9].
* [GSLL](https://common-lisp.net/project/gsll/)  - Lisp 的 GNU 科学图书馆； 允许使用来自 Common Lisp 的 GSL.  [GNU LGPL2.1][11].
* [Xecto](https://github.com/pkhuong/Xecto)  - 用于常规阵列并行性的库.  [3 条款 BSD][15].
* [Petalisp](https://github.com/marcoheisig/Petalisp) - 尝试
  为并行计算机生成高性能代码
   JIT 编译数组定义. 它适用于更多
  基础水平比 NumPy，通过提供更强大
  N 维数组，但只是一些用于处理的构建块
  他们.  [AGPL-3.0][agpl3].
* [cl-ana](https://github.com/ghollisjr/cl-ana)  - 强调模块化和概念清晰度的 Common Lisp 数据分析库. 它旨在成为分析小型和大型数据集的通用框架，包括分箱数据分析和可视化.  [GNU GPL3][2].
* [linear-programming](https://neil-lindquist.github.io/linear-programming/)  – 用于解决线性规划问题的库.  [麻省理工][200].
* [avm](https://github.com/takagi/avm)  - 具有多线程和 CUDA 支持的高效且富有表现力的阵列矢量数学库.  [麻省理工][200].
* [array-operations](https://github.com/bendudson/array-operations)  - 一组函数和宏，用于操作 Common Lisp 数组并使用它们执行数值计算.  [麻省理工][200].
* [cl-geometry](https://github.com/Ramarren/cl-geometry/)  - 用于 Common Lisp 的二维计算几何系统.  [麻省理工][200].
* [Vellum](https://github.com/sirherrbatka/vellum)  - Common Lisp 的数据框架.  BSD_2条款.
* [rtg-math](https://github.com/cbaggers/rtg-math/)  - 在 lisp 中制作实时图形最常用的数学例程选择（2、3 和 4 分量向量、3x3 和 4x4 矩阵、四元数、球坐标和极坐标）.  BSD_2条款.
* [origin](https://github.com/mfiano/origin)  - 一个原生的 Lisp 图形数学库，强调性能和正确性. 包括：向量、矩阵（最多 4x4）、四元数、单/双浮点数支持、破坏性/非破坏性操作、整形和交叉.  [麻省理工][200].

矩阵库
----------------

* [magicl](https://github.com/quil-lang/magicl)  - 基于 BLAS/LAPACK 和 Expokit 的 Common Lisp 中的矩阵代数程序，由 Rigetti Computing 提供.  [BSD_3条款][15].
* [lisp-matrix](https://github.com/blindglobe/lisp-matrix)  - 矩阵包.  [FreeBSD][39].
* [3d-matrices](https://shinmera.github.io/3d-matrices)  - 一个实现通用矩阵计算的库，重点是图形中常用的 2x2、3x3 和 4x4 矩阵. 它还提供了一些数值函数，但这些不是重点. 该库经过了大量优化，因此它不是由漂亮的代码组成的.  [zlib][33].
* [clem](https://github.com/slyrus/clem)  - 矩阵库.  [BSD_2条款][17].

Statistics
---------

* [lisp-stat](https://github.com/lisp-stat)  - 统计计算环境，概念上类似于 R，也适用于一线生产部署.  “它源于希望有一个环境来快速制作分析和人工智能解决方案的原型，并以最小的摩擦直接转移到生产环境.”
  * https://lisp-stat.dev/
  * 运送 Luke Tierney  [XLisp-Stat](https://homepage.stat.uiowa.edu/~luke/xls/xlsinfo/) （R 的前身）以及更新的库.
* [common-lisp-stat](https://github.com/blindglobe/common-lisp-stat/)  - Common Lisp 统计库.  [FreeBSD][39].

Units
-----

* [physical-quantities](https://github.com/mrossini-ethz/physical-quantities)  - 一个为带有自动错误传播的计算提供带有可选单位和/或不确定性的数字类型的库.  GPL2

Utils
-----

* [cmu-infix](https://github.com/rigetti/cmu-infix)  - 用于在 Common Lisp 中编写中缀数学符号的库. 也可以看看 [polisher](https://github.com/mrcdr/polisher).


并行性和并发性
===========================

* ⭐ [BordeauxThreads](https://common-lisp.net/project/bordeaux-threads/)  - 可移植的共享状态并发.  [外籍人士][14].
* ⭐ [lparallel](https://github.com/lmj/lparallel)  - 并行编程库.  [3 条款 BSD][15].
* [lfarm](https://github.com/lmj/lfarm)  - 跨机器分配工作（在 lparallel 和 usocket 之上）.  [BSD_3条款][15]
* [calispel](https://github.com/hawkir/calispel) - [CSP](https://en.wikipedia.org/wiki/Communicating_sequential_processes) - 类似普通 lisp 的频道. 具有阻塞、可选缓冲通道和“CSP select”语句.  ISC 风格.
   - “它完整、灵活且易于使用.我会推荐 Calispel 而不是 Lparallel 和 ChanL.”  @安布雷瓦. [discussion](https://github.com/CodyReichert/awesome-cl/issues/290)
* [chanl](https://github.com/zkat/chanl)  - 可移植的、基于通道的并发.  [Expat][14]，包含 [3-clause BSD][15] 下的部分.
* [cl-async](https://github.com/orthecreedence/cl-async)  - 用于通用、非阻塞编程的库.  [外籍人士][14].
* [Moira](https://github.com/TBRSS/moira)  - 监控并重启后台线程.  In-lisp 进程主管.  [麻省理工][200].
* [trivial-monitored-thread](https://gitlab.com/ediethelm/trivial-monitored-thread) -
  一个 Common Lisp 库，提供了一种产生线程和被
  当他们中的任何一个崩溃并死亡时通知.  [麻省理工][200].
* [cl-gearman](https://github.com/taksatou/cl-gearman) - 图书馆 [Gearman](http://gearman.org/) 分布式作业系统.  [LLGPL][8].
* [swank-crew](https://github.com/brown/swank-crew)  - 使用 Swank Client 实现的分布式计算框架.  [BSD_3条款][15].
* [cl-coroutine](https://github.com/takagi/cl-coroutine)  - 协程库. 它在其实现中使用 CL-CONT 延续库.  [麻省理工][200].
* [STMX](https://github.com/cosmos72/stmx) -  High performance Transactional Memory for Common Lisp. [LLGPL][8].

也可以看看：

* [cl-etcd](https://github.com/atgreen/cl-etcd) - 将 etcd 作为异步劣质进程运行.  [etcd](https://etcd.io/) 是一个高度一致的分布式键值存储.  [AGPL-3.0][agpl3].

演员模式
--------------

* 👍 [Sento](https://github.com/mdbergmann/cl-gserver)  - Sento（以前的 cl-gserver）是一个“消息传递”库/框架，其参与者类似于 Erlang 或 Akka. 它支持创建应该响应式工作的系统，需要并行计算和基于事件的消息处理.  [Apache2][89].
* [erlangen](https://github.com/eugeneia/erlangen)  - 用于 Clozure Common Lisp 的分布式异步消息传递系统.  [GNU GPL3][2].
* [Actors](https://github.com/aarvid/Actors) LispWorks 包 ([announce](https://www.reddit.com/r/Common_Lisp/comments/77vsft/david_mcclains_actors_package_for_lispworks/)) [麻省理工][200].
* [common-lisp-actors](https://github.com/naveensundarg/Common-Lisp-Actors)  - 一个简单易用的Actor系统.  [BSD_2条款][17].
* [memento-mori](https://github.com/zkat/memento-mori) - 一个用于编写健壮的、基于参与者的系统的库. 它从 Erlang/OTP 以及 Akka 中汲取灵感，尤其是其对高可用性系统的崩溃优先方法.  [麻省理工][200].

也可以看看：

* [lisp-actors](https://github.com/dbmcclain/Lisp-Actors)，“对 Common Lisp 中 Actor 模型的使用的持续调查，它已经在实际应用中受益”.
  * 这是的一部分 [Emotiq blockchain](https://github.com/emotiq/emotiq/blob/dev/src/test/blockchain-test.lisp) （一个停止的项目）
  * 做远程处理，包括一个类似于 Bordeaux-Threads 的线程抽象层库.
   *！ 它缺乏单元测试.


事件处理
----------------

* [simple-tasks](https://github.com/Shinmera/simple-tasks)  - 一个非常简单的任务调度框架.  [zlib][33].
* [deeds](https://github.com/Shinmera/deeds)  - Deeds 是一个可扩展的事件传递系统. 它允许使用复杂的事件过滤系统将事件高效地传递给多个处理程序.  [zlib][33].
* [cl-flow](https://github.com/borodust/cl-flow/)  - 用于非阻塞并发 Common Lisp 的数据流计算树库.  [麻省理工][200].
* [event-glue](https://github.com/orthecreedence/event-glue)  - 简单的事件抽象. 没有依赖性. 它可以在任何需要通用事件处理系统的地方使用.  [麻省理工][200].


作业处理
--------------


* [SBCL's timers](http://www.sbcl.org/manual/#Timers)，系统范围的事件调度程序.
* [psychiq](https://github.com/fukamachi/psychiq)  - 用于 Common Lisp 应用程序的基于 redis 的后台作业处理. 受 Ruby 的 Sidekiq 启发并与其 web UI 兼容.  [LLGPL][8].
* [cl-cron](https://github.com/ciel-lang/cl-cron)  - 一个简单的工具，提供类似 cron 的设施.  [GPL3][2].
* [clerk](https://github.com/tsikov/clerk)  - 一个具有正常 DSL 的类似 cron 的调度程序.  [麻省理工][200].


Regex
=====

* ⭐ [cl-ppcre](http://weitz.de/cl-ppcre/)  - 可移植的、与 Perl 兼容的正则表达式.  [FreeBSD][39].
* [one-more-re-nightmare](https://github.com/no-defun-allowed/one-more-re-nightmare)  - Common Lisp 中的快速正则表达式编译器.  [BSD_2条款][17].

另见上面的 clj-re.


Scripting
=========

编写、运行脚本
------------------------

* 👍 [Roswell](https://github.com/roswell/roswell#scripting-with-roswell) -
  一个 lisp 安装程序和脚本环境（帮助器、启动器、
  安装程序）等等.  [麻省理工][200].
* [cl-all](https://github.com/shinmera/cl-all)  - 在多个实现中运行 Lisp 片段的脚本. 这使您可以快速比较实现行为和差异.  [zlib][33].
* [clawk](https://github.com/sharplispers/clawk)  - 嵌入到 Common Lisp 中的 AWK 实现，用于搜索文件中的行并在其字段上执行指定的操作.  BSD风格.
* [ScriptL](https://github.com/rpav/ScriptL)  - Shell 脚本使 Lisp 变得像！ 或者，为 shell 实时编码远程函数调用. 在 REPL 中编写命令，并在 shell 中立即运行.  [LLGPL][8].
  * 相似且可能更简单： [lserver](https://notabug.org/quasus/lserver/)

命令行选项解析器
----------------------------

* 👍 [Clingon](https://github.com/dnaeon/clingon) - 丰富的命令行选项解析器系统.
  * 它可能具有最丰富的功能集：子命令、生成 bash 完成、支持各种选项（整数、布尔值、计数器、枚举……）、可扩展……
* [Adopt](https://github.com/sjl/adopt/)  - 该死的 OPTion 解析库.  [麻省理工][200].
* [Unix-opts](https://github.com/libre-man/unix-opts)  - 带有简明选项声明的命令行选项解析器.  [麻省理工][200].


Readline、ncurses 和其他图形助手
--------------------------------------------

* [cl-readline](https://github.com/vindarel/cl-readline) - 一套
  函数在输入时编辑行，维护列表
  以前输入的命令行，调用并重新编辑它们，
  执行类似 csh 的历史扩展.  Emacs 和 vi 编辑
  模式.  [GPL3][2].
* [Linedit](https://common-lisp.net/project/linedit) - 阅读风格
  提供可定制行编辑的库
  特征.  [麻省理工风格][210].
* [cl-charms](https://github.com/HiTECNOLOGYs/cl-charms) - 一个
   Common Lisp 中“libcurses”的接口. 它既提供了原始的，
  通过 CFFI 与 libcurses 的低级接口，以及更高级别的接口
  口齿不清的界面.  [麻省理工][200].
* [replic](https://github.com/vindarel/replic/)  - 帮助将现有代码转换为 readline 应用程序，重点是定义命令参数的完成. 还作为一个随时可用的可执行文件出现，它将用户的 lispy init 文件转换为 readline 命令.  [麻省理工][200].
* [cl-ansi-term](https://github.com/vindarel/cl-ansi-term) - 打印
  彩色文本、水平线、进度条、（无）有序列表
  和 ANSI 兼容终端上的表格.  [GPL3][2].
* [cl-progress-bar](https://github.com/sirherrbatka/cl-progress-bar/)  - 进度条，就像在 Quicklisp 中一样！  [麻省理工][200].

外壳、外壳接口
-------------------------

* [Lish](https://github.com/nibbula/lish)  - `lish` 可能有一天会成为 lisp shell.  [GPL3][2].
  * 支持路径和 Lisp 符号中可执行文件的制表符完成，允许编写和混合 shell 命令和 Lisp 代码，有一个微型 REPL 和一个交互式调试器，等等.
* [shcl](https://github.com/bradleyjensen/shcl)  - Common Lisp 中类似 POSIX 的 shell.  [Apache2.0][89].
* [Shelly](https://github.com/fukamachi/shelly) - 执行 Common Lisp
  功能类似于 shell 命令，无需编写命令
  行参数解析器. 它也可以用作类似 Make 
  构建工具.  [FreeBSD][39].
* [cmd](https://github.com/ruricolist/cmd)  - 用于运行外部程序的实用程序. 防止 shell 插值，构建时考虑了多线程程序，Windows 支持.  [麻省理工][200].
   * `uiop:run-program`（同步）和 `uiop:launch-program`（异步）随 ASDF 一起提供，可用于所有现代实现. 见 [CL Cookbook: running external programs](https://lispcookbook.github.io/cl-cookbook/os.html#running-external-programs).
* [Clesh](https://github.com/Neronus/Clesh)  - 扩展 Common Lisp 以类似于 perl 反引号的方式嵌入 shell 代码.  [FreeBSD][39].

系统管理
---------------------

* [Consfigurator](https://spwhitton.name/tech/code/consfigurator/)  - Lisp 声明式配置管理系统. 您可以使用它以根用户身份配置主机、以非特权用户身份部署服务、构建和部署容器以及生成光盘映像.  [GPL3][2].
* [cl-unix-cybernetics](https://github.com/cl-unix-cybernetics/cl-unix-cybernetics)  （以前是 Adams）- Common Lisp 中的 UNIX 系统管理. 与 Ansible、Chef 或 Puppet 不同.  [ISC][22].
   - 您使用具有属性的资源来描述您的系统（主机）. 然后仅使用远程主机上的 /bin/sh 和控制主机上的 /usr/bin/ssh 来探测和同步属性.

其他脚本实用程序
-------------------------

* [WCL](https://github.com/wadehennessey/wcl) [停滞] - 允许数百个 Lisp
应用程序可立即实际使用，同时允许
其中几个同时运行.  WCL 通过
提供 Common Lisp 作为 Unix 共享库，可以与
 Lisp 和 C 代码生成高效的应用程序. 例如，
Lisp 版本的规范“Hello World!”的可执行文件
程序在 32 位 x86 Linux 上只需要 20k 字节.  WCL还有
支持完整的开发环境，包括动态文件
加载和调试.  GDB 的修改版本用于调试 WCL
程序，为混合语言调试提供支持.
    - A [paper](https://dl.acm.org/doi/abs/10.1145/141478.141560)：“在 Unix 下交付高效的 Common Lisp 应用程序”.


文本编辑器资源
=====================

这包含各种文本编辑器的插件和其他好东西.

* [Parinfer](https://shaunlebron.github.io/parinfer/)  -Parinfer 是一种编辑 lisp 代码的方法，有助于保持缩进和括号的平衡. 它很容易上手，但它提供了 la Paredit 的高级功能. 它可用于许多编辑器（Emacs、Vim、Neovim、Atom、Sublime Text、Visual Studio Code、LightTable、CodeMirror 等）.

## Emacs ##

* ⭐ [Slime](https://github.com/slime/slime)  - Emacs 的高级 Lisp 交互模式；  Emacs 内部的 Common Lisp 的成熟环境. 公共区域.
* 👍 [Sly](https://github.com/joaotavora/sly) - SLY 是 SLIME 的一个分支，包含多项改进.
* 👍 [Portacle](https://shinmera.github.io/portacle/) - 可移植的多平台 Common Lisp 环境：SBCL、Quicklisp、Emacs、Slime、Git.
* [cl-devel2](https://hub.docker.com/r/eshamster/cl-devel2/)  - 用于 Common Lisp 开发环境的 Docker 容器. 附带 Slime 的 SBCL、CCL、Roswell 和 Emacs25.
* [Emacs4CL](https://github.com/susam/emacs4cl)  - 一个微小的 Emacs 初始化文件，用于快速设置普通 Emacs 以进行 Common Lisp 编程. 附带对初始化文件中每一行代码的逐行解释.
* [slime-star](https://github.com/mmontone/slime-star) - 预装扩展的 SLIME 配置，还有一些自定义实用程序和菜单：
  - Lisp系统浏览器
  - [SLIME doc contrib](https://github.com/mmontone/slime-doc-contribs) - 增强默认帮助缓冲区.
  - [Quicklisp systems](https://github.com/mmontone/quicklisp-systems) - 从 Emacs 搜索、浏览和加载 Quicklisp 系统.
  - [Quicksearch](https://github.com/tkych/quicksearch)
  - [Slime breakpoints](https://github.com/mmontone/slime-breakpoints)
  - [Slite](https://github.com/tdrhq/slite/) - FiveAM 的测试运行器.

## Vim & Neovim ##

* [SLIMV](https://github.com/kovisoft/slimv)  - Vim 的高级 Lisp 交互模式；  Vim 内部的 Common Lisp 的成熟环境. 未指定许可证.
* [Vlime](https://github.com/vlime/vlime)  - VLIME：Vim 加上 Lisp 基本上是邪恶的.  Vim（和 Neovim）的 Common Lisp 开发环境.  [麻省理工][200].
* [quicklisp.nvim](https://gitlab.com/HiPhish/quicklisp.nvim) - Neovim 的 Quicklisp 前端.
* [Slimv_box](https://github.com/justin2004/slimv_box) - Docker 容器中的 slimv.


## Eclipse ##

* [Dandelion](https://github.com/Ragnaroek/dandelion) - Eclipse IDE 的 Common Lisp 插件.

## Lem ##

* [Lem](https://github.com/cxxxr/lem) - 一个随时可用的，类似 Emacs 的，基于 Slime 
  为开箱即用的 Common Lisp 开发以及其他编程语言量身定制的编辑器. 使用 ncurses 和 Electron 接口.  [麻省理工][200]. 另见： [opengl frontend](https://github.com/pupcraft/lem-opengl), [Lem in Docker](https://github.com/40ants/lem-docker), [lem-pareto](https://github.com/40ants/lem-pareto).

## Atom ##

* [SLIMA](https://github.com/neil-lindquist/slima) 让你
  交互式开发 Common Lisp 代码，将 Atom 变成一个
  非常好，积极开发，Lisp IDE.  [麻省理工][200].

## Sublime Text ##

* [Sublime Text](http://www.sublimetext.com/3) （专有）有
  Common Lisp 支持及其 SublimeREPL 和
  [Slyblime](https://github.com/s-clerc/slyblime) 包. 狡猾的人
  是 SLY 的一个实现，它使用相同的后端 (SLYNK). 它
  附带高级功能，包括带有堆栈框架的调试器
  检查.

## VSCode ##

* [commonlisp-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.commonlisp-vscode)  - 支持语法突出显示、自动完成、悬停文档、转到定义、编译和加载文件、REPL 的扩展. 这是 [On GitHub](https://github.com/ailisp/commonlisp-vscode/).
* [alive](https://github.com/nobody-famous/alive)  - VSCode 的 Common Lisp 扩展. 公共区域.
  * 见食谱： [using VSCode with Alive](https://lispcookbook.github.io/cl-cookbook/vscode-alive.html)
* [strict-paredit-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.strict-paredit) - 像 Emacs 一样的结构编辑和导航.

## JetBrains

* [SLT](https://github.com/Enerccio/SLT) - Itellij/Jetbrains IDE 系列的 IDE 插件，通过 SBCL 和 Slime/Swank 实现对 Common Lisp 的支持.
   - 新的！  2023 年 1 月发布.

## Geany (experimental) ##

* [Geany-lisp](https://github.com/jasom/geany-lisp) 是一个实验性的 lisp 模式 [Geany](https://geany.org/) 编辑.

## Notebooks ##

* [common-lisp-jupyter](https://github.com/yitzchak/common-lisp-jupyter)  - Jupyter 的 Common Lisp 内核以及用于构建 Jupyter 内核的库，基于 Robert Dodier 的 Maxima-Jupyter，它基于 Frederic Peschanski 的 cl-jupyter.  [麻省理工][200].
  * [jupyterlab-debugger-restarts](https://github.com/yitzchak/jupyterlab-debugger-restarts) - JupyterLab 调试器的重启功能.
  * [Cytoscape widget](https://github.com/yitzchak/cytoscape-clj) - 用于 common-lisp-jupyter 的 Cytoscape.js 小部件.
  * [Kekule widget](https://github.com/yitzchak/kekule-clj) - 用于 common-lisp-jupyter 的 Kekule.js 小部件.
  * [molecule viewer](https://github.com/yitzchak/jupyterlab-molviewer) - 使用 ngl 的 JupyterLab 分子查看器.
  * [ngl widget](https://github.com/yitzchak/ngl-clj) - 用于 common-lisp-jupyter 的 ngl 小部件（蛋白质查看器）.
  * [sheet widget](https://github.com/yitzchak/sheet-clj) - 用于 common-lisp-jupyter 的数据网格小部件.
* [cl-jupyter](https://github.com/fredokun/cl-jupyter) - 用于 Jupyter 笔记本的 Common Lisp 内核 [custom licence](https://github.com/fredokun/cl-jupyter/blob/master/LICENSE).
* [Darkmatter](https://github.com/tamamu/darkmatter) - A
  笔记本式的 Common Lisp 环境.  [麻省理工][200].

## REPLs ##

* [cl-repl](https://github.com/koji-kojiro/cl-repl)  - 一个类似 ipython 的 REPL. 具有补全、shell 命令、魔术命令、调试器等 [MIT][200]. 和 [colorthemes](https://github.com/koji-kojiro/lem-pygments-colorthemes).
* [sbcli](https://github.com/hellerve/sbcli)  - SBCL 的 readline REPL. 具有补全、快速命令、可选的语法高亮显示（使用 pygments），并且没有交互式调试器.  [GPL3][2].

## Online editors ##

* [Judge0 IDE](https://ide.judge0.com/?lUpj) 是一个支持 Common Lisp (SBCL) 的在线编辑器.  [麻省理工][200].
* [Riju](https://riju.codes/commonlisp)，“每种编程语言的快速在线游乐场”，支持 Common Lisp (SBCL).

## Apps ##

* [CodePlayground](https://codeplayground.app/) - 通过 CCL 支持 Lisp 的 iPhone 和 iPad 应用程序.

文本解析器
============

* ⭐ [esrap](https://github.com/scymtym/esrap)  - Packrat 解析器.  [外籍人士][14].
* [cl-yacc](https://github.com/jech/cl-yacc)  - LALR(1) 解析器生成器.  [麻省理工][200].
* [cl-shlex](https://github.com/ruricolist/cl-shlex/)  - 用于类 shell 语法的简单词法分析器.  [麻省理工][200].
* [smug](https://github.com/drewc/smug)  - Common Lisp 的解析器组合器.  SMUG 使创建快速可扩展的递归下降解析器变得简单，而无需时髦的语法或难以理解的宏观.  [麻省理工][200].
* [parseq](https://github.com/mrossini-ethz/parseq)  - 一个使用解析表达式语法解析字符串和列表等序列的库. 灵感来自 Esrap.  GPL2.
* [texp](https://github.com/eugeneia/texp/)  - 生成 TeX 的 DSL.  [AGPL-3.0][agpl3].

文本处理
===============

* [montezuma](https://github.com/sharplispers/montezuma/)  - 全文索引和搜索 Common Lisp.  [外籍人士][14].
* [mk-string-metrics](https://github.com/cbaggers/mk-string-metrics) -
  Calculate various string metrics efficiently in Common Lisp
  (Damerau-Levenshtein, Hamming, Jaro, Jaro-Winkler, Levenshtein,
   ETC）.  [麻省理工][200].
* [wiki-lang-detect](https://github.com/vseloved/wiki-lang-detect) -
使用维基百科数据的文本语言识别. 未指定许可证.
* [cl-phonetic](https://github.com/bgutter/cl-phonetic)  - Common Lisp 的语音模式匹配库（旨在取代 Python 的 Sylvia 库）.  [麻省理工][200].
* [cl-string-generator](https://github.com/pokepay/cl-string-generator)  - 从正则表达式生成字符串.  [麻省理工][200].
* [trivial-sanitize](https://notabug.org/cage/trivial-sanitize)  - 清理 html 字符串：“ <a>foo</a> ”→“foo”.  [LLGPL][8].

也可以看看：

* [Resolve](https://github.com/GrammaTech/resolve)  - 用于基于 AST 的差异计算、显示和自动解析的软件. 用 C++ 和 CL 编写，您会发现 Lisp 实用程序.

Tools
=====

这些是使 Common Lisp 中的开发更容易的应用程序或代码位，而不是 Common Lisp 库本身.

* [quicksearch](https://github.com/tkych/quicksearch)  - 从 REPL 查找在线图书馆.  [外籍人士][14].
* [lake](https://github.com/takagi/lake)  - 类似 GNU make 的构建实用程序.  [麻省理工][200].


单元测试
============

* ⭐ [FiveAM](https://github.com/sionescu/fiveam)  - 简单的回归测试框架.  [FreeBSD][39].
  * [fiveam-matchers](https://github.com/tdrhq/fiveam-matchers/)  - 用于 fiveam 的可扩展、可组合的匹配器库.  [Apache2.0][89].
* [CLUnit2](https://notabug.org/cage/clunit2/)  - 单元测试库.  [麻省理工][200].
* [Parachute](https://github.com/Shinmera/parachute)  - 一个可扩展和交叉兼容的测试框架. 具有测试依赖性、条件、固定装置和重新启动.  [zlib][33].
* [Mockingbird](https://github.com/Chream/mockingbird) - 一个小
   Common Lisp 的存根和模拟库. 也可以查天气
  调用了存根函数，调用了多少次以及调用了哪些
  争论.  [麻省理工][200].
* [cl-mock](https://github.com/Ferada/cl-mock)  - 另一个模拟图书馆. 它比 Mockingbird 有更多的特性，比如模拟调用的模式匹配等.
* [Check-it](https://github.com/DalekBaldwin/check-it)  - QuickCheck 风格的随机化基于属性的测试.  [LLGPL][8].
* [cl-coveralls](https://github.com/fukamachi/cl-coveralls) - 帮手
  库将测试覆盖率发布到 Coveralls. 看 [SBCL's code coverage tool](http://www.sbcl.org/manual/index.html#sb_002dcover) .  [FreeBSD][39].

也可以看看：

* [testieren](https://cicadas.surf/cgit/colin/testiere.git/about/)  - 一个测试实用程序，其中测试包含在 `defun/t` 表单的顶部. 当您以交互方式重新编译您的函数时，它们会运行. 具有模拟和存根支持.  [GPL3][2].

编辑器实用程序：

* [Slite](https://github.com/tdrhq/slite/)  - 用于 FiveAM 测试的基于 SLIme 的测试运行器.  [Apache2.0][89]
   - Slite 以交互方式运行您的 Common Lisp 测试（在撰写本文时，仅支持 FiveAM）. 它允许您查看测试失败的摘要、跳转到测试定义、使用调试器重新运行测试，所有这些都来自 Emacs 内部.

更多信息： [Sabra Crolleton's extensive test frameworks comparison](https://sabracrolleton.github.io/testing-framework).


Utilities
=========

Caching
-------

* [clache](https://github.com/html/clache)  - 通用缓存设施. 在磁盘或内存中缓存任何 Lisp 对象. 缓存可以是持久的或具有过期时间.  [LLGPL][8].
* [function-cache](https://github.com/AccelerationNet/function-cache)  - 一个 Common Lisp 函数缓存/记忆库.  [BSD][15].


压缩/解压
---------------------------

* [chipz](https://github.com/froydnj/chipz)  - 一个解压库.  [3 条款 BSD][15].
* [Salza2](http://www.xach.com/lisp/salza2/)  - 用于创建压缩数据的库.  [FreeBSD][39].
* [zippy](https://github.com/Shinmera/zippy)  - 基于 3bz 的 ZIP 存档格式库.  [zlib][33].
* [archive](https://github.com/froydnj/archive)  - 用于读取和创建存档（tar、cpio）文件的库.  [BSD_3条款][15].  `tar` 程序的纯 Common Lisp 替代品.
  * 查看它最近的分支 [cl-tar](https://common-lisp.net/project/cl-tar/) (2021). [Announce](https://www.timmons.dev/posts/new-project-cl-tar.html).


Configuration
-------------

* 👍 [py-configparser](https://common-lisp.net/project/py-configparser/)  - 读写 Python 的 ConfigParser 类配置文件.  [麻省理工][200].
* [envy](https://github.com/fukamachi/envy)  - 配置切换器.  [FreeBSD][39].
* [chameleon](https://github.com/sheepduke/chameleon/)  - 附带配置文件支持的配置管理库.  [麻省理工][200].

CSV
---

* ⭐ [cl-csv](https://github.com/AccelerationNet/cl-csv)  - 用于解析 CSV 文件的库.  [3 条款 BSD][15].
* [cl-decimals](https://github.com/tlikonen/cl-decimals)  - 十进制数解析器和格式化程序. 公共区域.
* [auto-text](https://github.com/defunkydrummer/auto-text)  - 文本文件的自动（编码、行尾、列宽、csv 定界符等）检测.  [麻省理工][200]. 也可以看看 [inquisitor](https://github.com/t-sin/inquisitor) 用于检测亚洲和远东语言.


日期和时间
-------------

* ⭐ [local-time](https://common-lisp.net/project/local-time/)  - 用于以半标准方式处理日期和时间信息的开发库.  [3 条款 BSD][15].
* [cl-date-time-parser](https://github.com/tkych/cl-date-time-parser)  - 自由地解析日期时间字符串. 隐藏日期时间格式之间的差异，并允许将日期和时间作为一种日期时间格式进行管理.  [麻省理工][200].
* [chronicity](https://github.com/chaitanyagupta/chronicity)  - 一种自然语言日期和时间解析，用于解析诸如“3 days from now”之类的字符串.  [BSD_3条款][15].
* [local-time-duration](https://github.com/enaeher/local-time-duration) -
建立在本地时间之上的持续时间处理库.  [麻省理工][200].
  * 看这个叉子： [humanize-duration](https://github.com/40ants/humanize-duration), that outputs only significant parts of a duration object. Has localization suport.
* [iso-8601-date](https://gitlab.com/DataLinkDroid/iso-8601-date)  - Common Lisp 中的其他日期例程，基于 ISO 8601 字符串表示.  [LLGPL][8].
* [calendar-date](https://github.com/takagi/calendar-date)  - 公历日期库.  [麻省理工][200].
* [periods](https://github.com/jwiegley/periods)  - 在更高层次上操作日期/时间对象. 具有系列兼容的数据结构.  [BSD_3条款][15].

另见本书 [Calendrical calculations](https://www.cambridge.org/us/academic/subjects/computer-science/computing-general-interest/calendrical-calculations-ultimate-edition-4th-edition?format=HB#resources) , Edward M. Reingold, Nachum Dershowitz, Cambridge Press. 它提供 Lisp 源代码.

数据验证
---------------

* [ratify](https://github.com/Shinmera/ratify)  - 一组用于批准、验证和解析输入的实用程序.  [zlib][33].
* [clavier](https://github.com/mmontone/clavier)  - Common Lisp 的通用验证库.  [麻省理工][200].
* [json-schema](https://github.com/fisxoj/json-schema) - 用于根据 4、6、7 和 2019-09 草案的模式验证数据的库 [JSON Schema](https://json-schema.org/) 标准.  [LLGPL][8].
* [sanity-clause](https://github.com/fisxoj/sanity-clause)  - Common Lisp 的数据序列化/合同库. 模式可以是属性列表或基于类的，允许在“make-instance”期间检查插槽的类型.  [LLGPL][8].
* [cl-semver](https://github.com/cldm/cl-semver) - 实施 [Semantic Versioning](https://semver.org) 规格.  [麻省理工][200]

开发工具
-------------------

* [repl-utilities](https://github.com/m-n/repl-utilities) - 舒适
REPL 的常见任务（打印文档、打印外部符号、
加载包时调用挂钩，...）.  [BSD_2条款][17].
* [flight-recorder](https://github.com/vseloved/flight-recorder) - 强大的 REPL 历史设施.
* [tracer](https://github.com/TeMPOraL/tracer)  - Common Lisp 的跟踪分析器，输出适合在 Chrome/Chromium 的跟踪查看器中显示.  [麻省理工][200].
* [cl-flamegraph](https://github.com/40ants/cl-flamegraph)  - SBCL 统计分析器的包装器，用于为 Common Lisp 程序生成 FlameGraph 图表.  [BSD][15].
* [cl-debug](https://github.com/LowH/cl-debug)  - 跨包调试工具. 提供一种统一的方式来启用或禁用特定于调试的代码. 相对于由符号或关键字表示的程序特征，可以启用或禁用调试代码.  ISC 许可证.
* [supertrace](https://github.com/fukamachi/supertrace)  - 用于调试/分析的高级 Common Lisp `trace` 功能. 一次跟踪多个函数，使用 before 和 after 钩子.  [BSD_2条款][17].
* [printv](https://github.com/danlentz/printv)  - 包含电池的跟踪和调试记录宏.  [Apache2][89].
* [journal](https://github.com/melisgl/journal)  - 用于日志记录、跟踪、记录和重放测试和持久性的库. 麻省理工学院.

并且：

* [GTFL](http://www.martin-loetzsch.de/gtfl/)  - Lisp 的图形终端，适用于想要调试或可视化自己的算法的 Lisp 程序员. 浏览器中的图形跟踪.  BSD风格.
* [trivial-benchmark](https://github.com/Shinmera/trivial-benchmark)  - 微型基准测试库.  [zlib][33].
* [glyphs](https://github.com/ahungry/glyphs/)  - 一个用于在某些地方减少 Common Lisp 冗长的库.  [GNU GPL3][2].
* [Lisp REPL core dumper](https://gitlab.com/ambrevar/lisp-repl-core-dumper/) -
一个可移植的包装器，用于按需生成 Lisp 核心，以快速启动 REPL.
它可以预加载提供的系统以帮助构建专门的集合
Lisp 内核.


文档构建器
----------------------

* [Staple](https://github.com/Shinmera/staple)  - 使用 HTML 模板生成文档页面的工具. 使用现有的 README，添加文档字符串、交叉引用和 CLHS 链接.  [zlib][33].
* [mgl-pax](https://github.com/melisgl/mgl-pax) - 探索性
编程环境和文档生成器. 一个可能
实现与文学编程类似的效果，但是
文档是从代码生成的，反之亦然. 代码是第一位的，
代码必须看起来漂亮，文档就是代码.  [麻省理工][200].
  - 看到这个 [40ants fork](https://github.com/40ants/doc) 用于：更轻量级的核心系统、JavaScript 搜索索引、多格式输出、HTML 主题、更新日志的 RSS 和 Atom 提要等.
* [Declt](https://github.com/didierverna/declt)  - Common Lisp 库的参考手册生成器. 构建一个可以进一步处理成各种格式的 texinfo 文档，例如 HTML 或 PDF.  BSD.
* [Codex](https://github.com/CommonDoc/codex) - 一个美丽
   Common Lisp 的文档系统.  [麻省理工][200].
* [QBook](https://github.com/mmontone/qbook)  - 生成 HTML（或 LaTeX）格式的 Common Lisp 源文件代码清单.  [BSD_3条款][15].
  - all comments started with 4 `;` (";;;;") are interpreted as documentation. Enhance the documentation with headings and directives.
   - QBook 充当“一个轻量级的文学编程系统，其中 Lisp 代码不是内联呈现的，而是在单独的部分中呈现的，这使得文档更易于浏览.”  @mmontone
* [sphinxcontrib-cldomain](https://sphinxcontrib-cldomain.russellsim.org/) -
  扩展 Sphinx 以涵盖 Common Lisp. 构建文档
  就像 sphinx 对 Python 项目一样容易.  [GPL3][2]
* [cl-bibtex](https://github.com/mkoeppe/cl-bibtex)  - 使用 BST-to-CL 编译器在 Common Lisp 中兼容重新实现 BibTeX 程序.  [GNU LGPL2.1][11].

也可以看看：

* [docbrowser](https://github.com/lokedhs/docbrowser) - 为加载的系统动态生成文档的服务器.
   - 它的主页显示了您的 Lisp 映像中所有已加载系统的列表. 单击一个系统，您将获得一个包含三个窗格的页面：函数、类和变量. 单击一个函数可以在上下文中查看其源代码和行号. 单击类以查看它们的插槽和特殊功能.
* [cl-livedocs](https://github.com/mmontone/cl-livedocs) - 相似且较新，基于 Webinfo，默认启用全文搜索.

包含更多文档生成器的概述博客文章：https://lisp-journey.gitlab.io/blog/overview-of-documentation-generators/

你可能还喜欢： [literate programming systems](#literate-programming).


文件和目录
---------------------

* ⭐ [uiop](https://common-lisp.net/project/asdf/uiop.html) 及其“路径名”包
  （取代 [cl-fad](http://weitz.de/cl-fad/) ).  uiop 是 ASDF3 的一部分
  因此在许多实现中都是如此.  [麻省理工][200].
* [osicat](https://common-lisp.net/project/osicat/) - 类 POSIX 系统上的轻量级操作系统接口（目录迭代和删除、环境变量、文件权限等）[Expat][14].
* [pathname-utils](https://github.com/Shinmera/pathname-utils)  - 一组实用程序以帮助进行路径名操作.  [zlib][33].
  * [filesystem-utils](https://github.com/Shinmera/filesystem-utils) - 处理文件系统的常见问题，例如列出文件、探测文件类型、确定默认目录等.
  * [file-attributes](https://github.com/Shinmera/file-attributes) - 访问公共文件属性（uid、gid、权限、ctime、mtime、atime）.
* [ppath](https://github.com/fourier/ppath) - Common Lisp 
 Python 的 os.path 模块的实现.  [BSD][15].
* [mmap](https://github.com/Shinmera/mmap)  - 便携式 mmap 文件内存映射实用程序库.  [zlib][33].
* [fof](https://gitlab.com/ambrevar/fof)  - 文件对象查找器 Common Lisp 库. 启用快速文件搜索、检查和操作.  [GPL3][2].

文件监视库：

* [file-notify](https://github.com/shinmera/file-notify)  - 用于文件更改检测的跨平台库.  [zlib][33].

Git
---

* [cl-git](https://cl-git.russellsim.org/)  - libgit2 库的 CFFI 接口.  [LGPL3][9].
* [legit](https://shinmera.github.io/legit/)  - Git 二进制文件的接口.  [zlib][33].
* [git-api](https://github.com/fourier/git-api)  - 用于访问 git 存储库的 Common Lisp 库. 它不需要安装 git 或 libgit.  [BSD][15].

i18n
----

* [cl-i18n](https://notabug.org/cage/cl-i18n)  - 国际图书馆. 从 GNU gettext 文本或二进制文件或其本机格式加载翻译. 复数形式的本地化助手.  [LLGPL][8].
* [gettext](https://github.com/rotatef/gettext)  - gettext 运行时到 Common Lisp 的端口.  [GPL3][2].
* [translate](https://github.com/dkochmanski/translate)  - 无缝语言本地化.  LLGPL.
* [enchant](https://github.com/tlikonen/cl-enchant)  - Enchant 拼写检查程序库的绑定. 公共区域.
* [oxenfurt](https://github.com/Shinmera/oxenfurt)  - 牛津词典 API 的客户端库.  [zlib][33].
* [language-codes](https://shinmera.github.io/language-codes)  - ISO 语言代码的数据库库.  [zlib][33]
* [system-locale](https://shinmera.github.io/system-locale)  - 检索用户首选语言的库，以便您的应用程序可以选择合理的默认值.  [zlib][33].
* [multilang-documentation](https://shinmera.github.io/multilang-documentation)  - 允许用多种语言编写文档字符串，用于真正国际化的文档库.  [zlib][33].

Linting，代码格式化
------------------------

* [sblint](https://github.com/fukamachi/sblint) - 使用 SBCL 的 Common Lisp 源代码 linter，适用于 Reviewdog（[slides](http://www.slideshare.net/fukamachi/sblint) ).  [BSD_2条款][17].
* [trivial-formatter](https://github.com/hyotang666/trivial-formatter)  - Common Lisp 的代码格式化程序.  [麻省理工][200].

并且： [lisp-format](https://github.com/eschulte/lisp-format) 和 [cl-indentify](https://github.com/yitzchak/cl-indentify).

文学编程
--------------------

* [literate-lisp](https://github.com/jingtaozf/literate-lisp)  - 从 Emacs 的 Org 文件加载 Common Lisp 代码块.  [麻省理工][200].
* [erudite](https://github.com/mmontone/erudite)  - 以交互式开发为理念构建的文学编程系统.  [麻省理工][200].


Logging
-------

* ⭐ [log4cl](https://github.com/sharplispers/log4cl/)  - 以 Log4J 为蓝本的日志记录框架.  [Apache2.0][89]. 与 Slime 的高级集成.
  * [log4cl-json](https://github.com/40ants/log4cl-json)  - JSON 附加程序扩展.  [BSD][15].
* [verbose](https://shinmera.github.io/verbose)  - 一个快速且高度可配置的日志框架.  [zlib][33].
* [a-cl-logger](https://github.com/AccelerationNet/a-cl-logger)  - 日志库提供上下文相关的日志记录，不仅仅是字符串到本地文件或输出流. 具有 logstash 支持、json 支持、记录器层次结构、上下文相关的日志记录、打印为可检查演示文稿的对象……

对第三方：

* [cl-fluent-logger](https://github.com/fukamachi/cl-fluent-logger) - 一个 Common Lisp 结构化记录器，用于 [Fluentd](https://www.fluentd.org/).

也可以看看： [extensive comparison of logging libraries](https://sabracrolleton.github.io/logging-comparison).

宏助手
-------------

* [easy-macros](https://github.com/tdrhq/easy-macros/) -  an easy way to write 90% of your macros. [Apache2.0][89].
* [trivial-with-current-source-from](https://github.com/scymtym/trivial-with-current-source-form/)  - 帮助宏作者为宏用户产生更好的错误.  [GPL3][2].

Markdown
--------

* [3bmd](https://github.com/3b/3bmd)  - 降价 -&gt; html 转换器.  [麻省理工][200].

PDF
---

* [cl-typesetting](https://github.com/mbattyani/cl-typesetting) 和 [cl-pdf](https://github.com/mbattyani/cl-pdf)  - 用于生成 PDF 文件的跨平台 Common Lisp 库.  [FreeBSD][39].
* [cl-pslib](https://notabug.org/cage/cl-pslib) - 一个（薄的）包装纸 [pslib](http://pslib.sourceforge.net/) 用于生成 PostScript 文件的库. 还 [cl-pslib-barcode](https://notabug.org/cage/cl-pslib-barcode) .  [LLGPL][8].

Plotting
--------

* [vgplot](https://github.com/volkers/vgplot) - 一个接口
  gnuplot 绘图实用程序，旨在类似于某些
   octave 或 matlab 的绘图命令.  [GPL3][2].
* [eazy-gnuplot](https://github.com/guicho271828/eazy-gnuplot) - A
   lispy，无结构的 Gnuplot 库. 与其
  [cookbook](http://guicho271828.github.io/eazy-gnuplot/) .  [LLGPL][8]
* [kai](https://github.com/komi1230/kai)  - 用于 Common Lisp 的高级绘图仪库. 一个包装器 [Plotly](https://plotly.com/javascript/)  JS库.  [麻省理工][200].
* [ADW-Charting](https://common-lisp.net/project/adw-charting/)  - 一个完全用 Common Lisp 编写的简单图表绘图库. 还包括 Google 图表服务的后端. 类 BSD.
* [cl-spark](https://github.com/tkych/cl-spark)  - 控制台的迷你图字符串：`(spark &#39;(1 1 2 3 5 8))` =&gt; &quot; ▂▃▅▇&quot;.  [麻省理工][200].

另请参阅 IUP 和 ltk-plotchart（GUI 部分）的图表工具.

项目骨架
-----------------

* [cl-project](https://github.com/fukamachi/cl-project)  - 通用的现代项目框架.  [LLGPL][8].
* [cl-project-with-docs](https://github.com/40ants/cl-project-with-docs)  - 使用 Sphinx 和重组文本来呈现漂亮且可读的 HTML 文档.  [BSD][15].
* [cl-cookieproject](https://github.com/vindarel/cl-cookieproject)  - 生成一个随时可用的 Common Lisp 项目. 不在 Quicklisp 中.  [BSD_3条款][15].
  * 测试定义、从源代码运行的入口点、构建二进制文件、Roswell 集成……

Security
--------

* [cl-isolated](https://github.com/kanru/cl-isolated) - 用于 Common Lisp 代码评估的受限环境 [AGPL-3.0][agpl3].

XML
---

* [CXML](https://common-lisp.net/project/cxml/)  - XML 解析器和序列化器，带有一系列扩展库.  [LLGPL][8].
  - 有一个增量解析器，允许解析大文件.
  - 看到 [FXML](https://github.com/ruricolist/FXML)  fork，带有修复和新功能. 如果您正在解析可能格式错误或恶意的 XML，或者如果您需要将 Klacks 与命名空间一起使用，则应该使用它.
 * [Plump][71] - 一个宽松的 XML 解析器.  [zlib][33].
* [xpath](https://github.com/sharplispers/xpath) ([homepage](https://common-lisp.net/project/plexippus-xpath/atdoc/index.html)  - XML 路径语言 (XPath) 1.0 版的实施.  [BSD_2条款][17].
* [s-xml](http://cliki.net/S-XML)  - 一个基本的解析器.  [LLGPL][8].
* [xmls](https://github.com/rpgoldman/xmls)  - 一个小型、简单、非验证的 XML 解析器.  [3 条款 BSD][15].
* [cl-feedparser](https://github.com/TBRSS/cl-feedparser)  - 一个 Common Lisp（RSS、Atom）提要解析器.  [LLGPL][8]
* [Buildnode](https://github.com/AccelerationNet/buildnode)  - 一个通用的 lisp 库，用于简化与 CXML-dom 的交互，例如构建 Excel 电子表格.  [BSD][15].


Other
-----

这包含任何不属于另一个类别的内容.

* [babel](https://github.com/cl-babel/babel)  - 一个字符集编码/解码库.  [外籍人士][14].
* [corona](https://github.com/eudoxia0/corona) - 从 Common Lisp 创建和管理虚拟机 http://eudoxia.me/corona [MIT][200].
* [fast-io](https://github.com/rpav/fast-io)  - 快速八位位组向量/流 I/O.  [3 条款 BSD][15].
* [iolib](https://github.com/sionescu/iolib)  - I/O 库.  [外籍人士][14].
* [named-readtables](https://github.com/melisgl/named-readtables)  - 提供一个可读的命名空间，类似于包命名空间.  [3 条款 BSD][15].
* [simple-currency](https://github.com/a0-prw/simple-currency)  - 使用欧洲央行发布的每日信息的货币转换库.  [FreeBSD][39].
* [trivial-garbage](https://github.com/trivial-garbage/trivial-garbage)  - 便携式终结器、弱哈希表和弱指针 API. 公共区域.
* [trivial-utf8](https://common-lisp.net/project/trivial-utf-8/)  - 用于执行基于 UTF-8 的 I/O 的小型库.  BSD.


Contributing
============
随时欢迎您的贡献！ 请提交拉取请求或创建
将新框架、库或软件添加到列表中的问题.

The rules we (try to) respect are the followings:

- 默认情况下，将库添加到其部分的末尾.
- 绝对的事实库，如 BordeauxThreads 或 Quicklisp，
  应该用 ⭐（Unicode 代码 U+2B50）表示.
- 两个范围非常相似的库应该并排放置，或者在一个
  他们自己的部分.
- 根据您的经验和状态做一些策展
  库的文档. 我们*不*旨在列出所有现有
  CL 库（参见 Cliki）也没有列出每个
  “流行”库（参见 Quicklisp 统计数据）.
- 因此，我们最喜欢的库标有 (`1F44D`
   unicode字符）. 另见标志的解释
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
