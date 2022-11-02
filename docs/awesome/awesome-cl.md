<div class="github-widget" data-repo="CodyReichert/awesome-cl"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">
  <a href="https://awesome-cl.com" target="_blank">
    <img src="https://i.imgur.com/jLVXhpc.png">
  </a>
</div>

## Awesome Common Lisp [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Assertible status](https://assertible.com/apis/102e334d-f9a8-4565-9353-7572de775cae/status?api_token=8b55a286830323effb)](https://assertible.com/docs/guide/deployments)

_awesome_ Common Lisp 库的精选列表.

对于真棒*软件*，请参阅 [lisp-lang.org's success stories](http://lisp-lang.org/success/) 和 [awesome-cl-software](https://github.com/azzamsa/awesome-cl-software) 列表.

此处列出的所有库都可以从 [Quicklisp][16] 获得，除非
另有说明. 标有⭐的那些非常普遍，而且
坚实，他们成为社区的标准. 你不会错
他们.  Quicklisp、BordeauxThreads 和
这样的. 用 a 表示的库是我们喜欢和想要的库
在 Awesome-cl 列表中推广. 他们被证明是可靠的，他们可以解决
一个比社区标准更好的问题，但它们不是
普遍，或不被认为是稳定的. 例如，我们更喜欢
Cl-Who 上的喷丝板.

添加新内容！ 见 [contributing](#contributing) 用于添加内容的部分
list.

这是根据 GNU 自由文档许可证发布的 - 它的文本
is provided in the LICENSE file. This repository is also mirrored on
[NotABug](https://notabug.org/CodyReichert/awesome-cl) - **完全免费**（如在 libre 中）
alternative to Github.  Preference is given to [free software][13] and
不为物质资源作恶的卖家.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->


<!-- markdown-toc end -->


Audio
=====

* [Open Music](https://github.com/openmusic-project/OM6)  - 可视化编程、计算机辅助作文环境.  [GPL3][2].
* [OM7](https://github.com/openmusic-project/om7)  - OpenMusic 可视化编程和计算机辅助作曲环境的新实现，包括对图形界面、计算模式和与外部软件库的连接的许多改进.  [GPL3][2].
* [Incudine](http://incudine.sourceforge.net/)  - Common Lisp 的音乐/DSP 编程环境. 从头开始设计软件合成器或声音插件很有用. 它也是一种作曲工具，可以在样本级别产生可控制的高质量声音，即时定义和重新定义数字信号处理器和音乐结构.
* [cl-collider](https://github.com/byulparan/cl-collider) - 一个
[SuperCollider](http://supercollider.github.io/)  CommonLisp 的客户端. 带一个 [tutorial](https://github.com/defaultxr/cl-collider-tutorial) 和 [live coding demos](https://www.youtube.com/watch?v=xzTH_ZqaFKI) . 公共区域.
* [csound](https://github.com/csound/csound)  - 声音和音乐计算系统. 包括用于 Common Lisp 的 CFFI 和 FFI 接口.
* [CLM](https://ccrma.stanford.edu/software/clm/)  - Common Lisp Music 是 Music V 系列中的一个音乐合成和信号处理包. 它提供了与 Stk、Csound、SuperCollider、PD、CMix、cmusic 和 Arctic 大致相同的功能——创建和操纵声音的功能集合，主要针对作曲家（无论如何是 CLM 的情况）.
* [cl-patterns](https://github.com/defaultxr/cl-patterns)  - 一个通过 Lisp 代码创作音乐的系统，深受 SuperCollider 模式系统的启发，旨在实现其中的大部分内容，但以更健壮、富有表现力、一致、反思和 lispy 的方式实现. 通过 SuperCollider 的音频输出，初步支持 Incudine，以及通过 ALSA 的 MIDI.
* [cl-openal](https://github.com/zkat/cl-openal)  - OpenAL 音频库的绑定. 公共区域.
* [Common Music](https://github.com/ormf/cm) - 存储库
Common Music 的古代版本（2.12.0 版），大概是最后一个
在 2007-09 年左右在 Common Lisp 上运行的版本，之前
Common Music 的工作转移到（基于方案的）cm3.
* [Slippery Chicken](https://github.com/mdedwards/slippery-chicken/)  - 通过 Lilypond 输出 Midi、Common Music Notation、pdf 分数和通过 Common Lisp Music 输出声音的算法作曲库.  [GPL3][2].
* [Common Music Notation](https://ccrma.stanford.edu/software/cmn/)  - Common Music Notation (CMN) 提供了一组函数来分层描述乐谱. 公共区域.
* [cm-incudine](https://github.com/ormf/cm-incudine)  - 使用实时功能扩展 Common Music 2.  GPL2.
* [Mégra](https://github.com/the-drunk-coder/megra)  - 一种用可变顺序马尔可夫链和其他一些随机恶作剧制作音乐的迷你语言.  [GPL3][2].
* [Music](https://github.com/MegaLoler/Music) - Lisp 中的音乐表达框架，专注于音乐理论（从头开始构建，与 Common Music 无关）.
* [rq](https://github.com/openmusic-project/RQ) - 在 OpenMusic（6.10 版及更高版本）中用于节奏转录的库. [demo video](https://www.youtube.com/watch?v=XVEllB0TtVs) .  [GPL3][2].
* [scheduler](https://github.com/byulparan/scheduler)  - Common Lisp 基于时间的音乐事件调度程序.  [Apache2.0][89].
* [mixalot](https://github.com/ahefner/mixalot)  - 用于 mp3、ogg vorbis、flac 的松耦合音频库集合. 用于 [Shuffletron music player](https://github.com/ahefner/shuffletron) .  [麻省理工学院][200].
* [osc](https://github.com/zzkt/osc)  - 开放声音协议的实现.  [LGPL2.1][11].
* [Harmony](https://shirakumo.github.io/harmony)  - 实时声音处理和播放系统.  [zlib][33].


构建系统
=============

* ⭐[ASDF](https://common-lisp.net/project/asdf/)  - 另一个系统定义工具；  Common Lisp 的构建系统.  [外籍人士][14].  Quicklisp（见 [library manager](#library-manager)) 在引擎盖下使用 ASDF.
  * [known ASDF extensions](https://common-lisp.net/project/asdf/#extensions)，例如`asdf-system-connections`，它允许您指定在加载其他两个系统时自动加载的系统，以连接它们.
* [asdf-linguist](https://github.com/eudoxia0/asdf-linguist)  - ASDF 的扩展.  [外籍人士][14].
* [asdf-viz](https://github.com/guicho271828/asdf-viz)  - 可视化 ASDF 系统的库依赖关系、函数调用图和类继承的工具.  [LLGPL][8].

编译器、代码生成器
==========================

APL
---

* [April](https://github.com/phantomics/april)  - 编译为 Common Lisp 的 APL 编程语言（其子集）. 用一行 APL 替换数百行数字运算代码.  [阿帕奇2] [89].


C、C++
------

* [cmacro](https://github.com/eudoxia0/cmacro) - C. [MIT][200] 的 Lisp 宏.
* [C-mera](https://github.com/kiselgra/c-mera)  - 一个源到源编译器，它利用 Lisp 的宏系统对类 C 语言进行元编程.  [GPL3][2].
* [lispc](https://github.com/eratosthenesia/lispc) - 一种强大的 C 语言“lispsy”宏语言.[MIT][200].
* [with-c-syntax](https://github.com/y2q-actionman/with-c-syntax)  - 一个有趣的包，它将 C 语言语法引入 Common Lisp.  （是的，我认为这个包不是用于实际编码的.） WTFPL 许可证.
* [ecrepl](https://gitlab.common-lisp.net/ecl/ecrepl)  - C 语言的交互式 REPL.  [BSD_2 条款][17].
* [Software-Evolution-Library](https://github.com/GrammaTech/sel)  - SEL 支持软件的编程修改和评估（使用 Clang、编译的汇编器和链接的 ELF 二进制文件的 C/C++ 支持）.  [GPL3][2].

Cryptography
============

* ⭐ [Ironclad](https://github.com/sharplispers/ironclad)  - Common Lisp 的加密函数库. 不被认为是安全的，但对于消息摘要功能仍然有用.  [外籍人士][14].
* [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts)  - 常用加密快捷方式的集合.  [zlib][33].
* [trivial-ssh](https://github.com/eudoxia0/trivial-ssh)  - 一个 SSH 客户端库.  [外籍人士][14].
* [cl-ssh-keys](https://github.com/dnaeon/cl-ssh-keys)  - 用于生成和解析 OpenSSH 密钥的 Common Lisp 系统.  [BSD_3 条款][15].
* [cl-bcrypt](https://github.com/dnaeon/cl-bcrypt)  - 用于解析和生成 bcrypt 密码哈希的 Common Lisp 系统.  [BSD_3 条款][15].
  * 也可以看看 [cl-pass](https://github.com/eudoxia0/cl-pass)，使用 pbkdf2.

Cryptocurrencies
================

* [bp](https://github.com/rodentrabies/bp)  - Common Lisp 中的比特币协议组件.  [麻省理工学院][200].
* [cl-monero-tools](https://github.com/glv2/cl-monero-tools)  - 使用 Monero 加密货币的 Common Lisp 工具箱.  [GPL3][2]. 不在 Quicklisp 中.
* [emotiq](https://github.com/emotiq/emotiq)  - 具有创新的自然语言智能合约方法的下一代区块链.  [麻省理工学院][200].
* [peercoin-blockchain-parser](https://github.com/glv2/peercoin-blockchain-parser)  - 解析文件中包含的区块链并将其部分数据导出到文本文件、SQL 脚本或数据库. 它还可以使用 Peercoin 守护程序的 RPC 作为数据源而不是区块链文件来创建数据库.  LGPL3. 不在 Quicklisp 中.
* [peercoin-calculator](https://github.com/glv2/peercoin-calculator)  - 该程序为您提供在 10 分钟、24 小时、31 天、90 天和 1 年内生成 POS 或 POW 块的概率，以及可预期的奖励.  Qt 中的图形用户界面.  [GPL3][2]. 不在 Quicklisp 中.
* [peercoin-vote](https://github.com/glv2/peercoin-vote)  - 基于区块链数据（地址和余额）的投票系统.  [GPL3][2]. 不在 Quicklisp 中.

也可以看看 [legochain](https://github.com/defunkydrummer/legochain)，一个简单的教育区块链.

Database
========

* [cl-yesql](https://github.com/ruricolist/cl-yesql)  - SQL 语句以 SQL 语法存在于它们自己的文件中，并作为函数导入 Lisp. 您不仅限于 DSL 支持的功能. 基于 Clojure 的 Yesql.  [麻省理工学院][200].

ORMs
----

* ⭐ [clsql](http://www.cliki.net/CLSQL)  - 具有 Common Lisp 界面的 SQL 数据库.  [LLGPL][8].
* [mito](https://github.com/fukamachi/mito) - 用于 Common Lisp 的 ORM，具有迁移、关系和 PostgreSQL 支持 [LLGPL][8].
  * [mitho-auth](https://github.com/fukamachi/mito-auth), 一个使用授权的mixin类
  * [mito-attachment](https://github.com/fukamachi/mito-attachment)，用于 RDBMS 之外的文件管理的 mixin 类.
* [cl-dbi](https://github.com/fukamachi/cl-dbi)  - Common Lisp 的独立于数据库的接口.  [LLGPL][8].
  * [dbd-oracle](https://github.com/sergadin/dbd-oracle)  - 用于 CL-DBI 的 Oracle 数据库驱动程序.  [LLGPL][8].
* [crane](https://github.com/eudoxia0/crane)  - 另一个 ORM.  [外籍人士][14].
* [datafly](https://github.com/fukamachi/datafly)  - 一个轻量级的数据库库.  [3 条款 BSD][15].
* [sxql](https://github.com/fukamachi/sxql)  - 用于生成 SQL 的 DSL.  [3 条款 BSD][15].

Persistent object databases
---------------------------

* [bknr.datastore](https://github.com/hanshuebner/bknr-datastore) - RAM 中基于 CLOS 的仅 lisp 数据库，具有事务日志记录持久性. [Manual](https://www.common-lisp.net/project/bknr/html/documentation.html) .  [许可证][208].
  * 也见这个 [good introductory blog post](https://ashok-khanna.medium.com/persistent-in-memory-data-storage-in-common-lisp-b-k-n-r-37f8ae76042f)
  * 使用 bknr.datastore 的示例 Web 应用程序： [screenshotbot-oss](https://github.com/screenshotbot/screenshotbot-oss).
* [ubiquitous](https://github.com/Shinmera/ubiquitous)  - 提供易于使用的持久配置存储的库.  [zlib][33].
* [cl-prevalence](https://common-lisp.net/project/cl-prevalence/)  - 内存数据库系统. 对象流行的实现，其中业务对象保持在内存中，事务被记录以进行系统恢复. [github fork](https://github.com/40ants/cl-prevalence) .  [LLGPL][8].
  * 也可以看看 [cl-prevalence-multimaster](https://github.com/40ants/cl-prevalence-multimaster), 同步多个 cl-prevalence 系统状态.
* [cl-naive-store](https://gitlab.com/Harag/cl-naive-store)  - 用于 Common Lisp 的天真持久、内存（延迟加载）、索引、文档存储.  [麻省理工学院][200].
  - 看 [the introductory blog post](https://zaries.wordpress.com/2022/05/31/cl-naive-store/)
  - 我们敢于添加：由作者公司用于生产（ASTN 集团，请参阅 awesome-lisp-companies）

也可以看看 [Clache](#caching)，可以将任何对象保存在磁盘上.


图数据库
---------------

* [cl-agraph](https://github.com/vseloved/cl-agraph), 一个最小的客户端 [AllegroGraph](https://allegrograph.com/) .  AllegroGraph 是一种水平分布、多模型（文档和图）、实体-事件知识图谱技术. 它是专有的，有一个免费版本，限制为 500 万个三元组.
* [neo4cl](https://github.com/equill/neo4cl)  - 一个与 Neo4J 交互的库. 将 Cypher 查询发送到 Neo4J 服务器，并将响应解码为对 CL 处理有用的内容.  [阿帕奇2] [89].
  * and maybe: [cl-neo4j](https://github.com/kraison/cl-neo4j) - 一个瘦neo4j RESTFUL 客户端界面.
* [vivace-graph](https://github.com/kraison/vivace-graph-v3)  - 图形数据库和 Prolog 实现. 从 CouchDB、neo4j 和 AllegroGraph 中汲取设计灵感. 它使用用户定义的索引和 map-reduce 视图实现了符合 ACID 的对象图模型. 它还实现了用于冗余和水平读取扩展的主/从复制方案. 查询图形是通过许多 Lisp 方法或通过类似 Prolog 的查询语言来完成的.  [麻省理工学院][200].

并且：

* [restagraph](https://github.com/equill/restagraph)  - 使用数据库中定义的模式为 Neo4j 数据库动态生成 REST API 的应用程序.  [GPL3][2].
* [facts](https://github.com/cl-facts/facts)  - 具有事务和回滚、日志记录/重播和转储/从磁盘加载/从磁盘加载的内存图形数据库.  BSD 风格的许可证 (ISC).


Wrappers
--------

* ⭐ [postmodern](http://marijnhaverbeke.nl/postmodern/)  - 用于与 PostgreSQL 交互的库.  [zlib][33].
* [cl-sqlite](https://github.com/dmitryvk/cl-sqlite)  - SQLite 的绑定. 公共区域.
* [cl-memcached](https://github.com/quasi/cl-memcached)  - Memcached 对象缓存系统的快速、线程安全接口.  [外籍人士][14].
* [cl-mongo](https://github.com/fons/cl-mongo)  - MongoDB 客户端.  [外籍人士][14].
* [cl-redis](https://github.com/vseloved/cl-redis)  - Redis 客户端.  [外籍人士][14].
* [cl-disque](https://github.com/CodyReichert/cl-disque)  - 客户磁盘.  [BSD 3 条款][15].
* [cl-rethinkdb](https://github.com/orthecreedence/cl-rethinkdb)  - RethinkDB 客户端.  [外籍人士][14].
* [cl-mango](https://github.com/cmoore/cl-mango/)  - 一个极简的 CouchDB 2.x 数据库客户端.  BSD_3 条款.
  * 也可以看看 [clouchdb](https://common-lisp.net/project/clouchdb/)  - 用于与 CouchDB 交互的库.  [自由BSD][39].
* [lmdb](https://github.com/antimer/lmdb) - 绑定到 [LMDB](http://www.lmdb.tech/doc/)，闪电内存映射数据库，具有多版本并发控制的 ACID 键值数据库.
* [cl-ndbapi](https://github.com/datagraph/cl-ndbapi) - 绑定到 C++ NDB API [RonDB](https://www.rondb.com/), “世界上最快的键值存储”, by [Dydra](https://dydra.com/home) .  GPLv2.

迁移工具
---------------

* [cl-migratum](https://github.com/dnaeon/cl-migratum)  - 一个为执行数据库模式迁移提供设施的系统，旨在与各种数据库一起使用.  [BSD_3 条款][15].
* [postmodern-passenger-pigeon](https://github.com/fisxoj/postmodern-passenger-pigeon/)  - 后现代的移民经理. 未指定许可证.


给第三方
----------------

* [dyna](https://github.com/Rudolph-Miller/dyna)  - AWS DynamoDB ORM.  [麻省理工学院][200].
* [cl-influxdb](https://github.com/mmaul/cl-influxdb/)  - 时间序列数据库 InfluxDB 的接口.  [麻省理工学院][200].
* [pzmq](https://github.com/orivej/pzmq)  - ZeroMQ 4.0+ Common Lisp 绑定. 无牌.

Tools
-----

* [pgloader](https://github.com/dimitri/pgloader)  - 用于 PostgreSQL 的数据加载工具.  [PostgreSQL 许可证][205].


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
具有高效内存映射持久性和快速瞬态存储模型的无锁、并发、键/值索引.  [麻省理工学院][200].
* [cl-data-structures](https://github.com/sirherrbatka/cl-data-structures)  - 数据结构和算法的可移植集合（主要是字典和序列，具有一些统计功能）.  [BSD][15].
* [listopia](https://github.com/Dimercel/listopia)  - 受 Haskell 的 Data.List 启发的列表操作库.  [LLGPL][8].
* [hash-set](https://github.com/samebchase/hash-set/) - 在 CL 哈希表之上实现哈希集的便利库 [The Unlicense][5]
* [cl-containers](https://common-lisp.net/project/cl-containers/) - 一个广泛的数据结构和实用程序库 - 队列、树、堆、双向链表、集合、包...... [麻省理工学院][200]
* [cl-competitive](https://github.com/privet-kitty/cl-competitive)  - 用于竞争性编程的通用 Lisp 算法集合. 公共领域，CCO 或 MIT.

访问数据结构：

* [access](https://github.com/AccelerationNet/access/)  - 对最常见数据结构的一致和嵌套访问.  [BSD_3 条款][15].
* [modf](https://github.com/smithzvk/modf) - 用于函数式编程的类似 setf 的宏.

其他数据结构：

* [bitfield](https://github.com/marcoheisig/bitfield)  - 有效地将几个有限集或小整数表示为单个非负整数.  [麻省理工学院][200].


Docker 镜像
=============

* [cl-docker-images](https://common-lisp.net/project/cl-docker-images/) - Windows (amd64) 和 Alpine 和 Debian (amd64, arm64, arm/v7) [BSD_2Clause][17] 上的 ABCL、CCL、ECL 和 SBCL 的 Docker 映像.
* [base-lisp-image](https://github.com/40ants/base-lisp-image) - 根据
  用于带有 SBCL 或 CCL 和最新版本的 Common Lisp 项目的 Docker 映像
  ASDF、Qlot 和罗斯威尔.


外部函数接口，语言互操作
=============================================

## C ##

* ⭐ [CFFI](https://github.com/cffi/cffi)  - 便携、易用的C外函数接口.  [外籍人士][14].
*[cl-autowrap](https://github.com/rpav/cl-autowrap)  - 自动将头文件解析为 CFFI 定义.  [自由BSD][39].
* [cl-bindgen](https://github.com/sdilts/cl-bindgen)  - 用于从 C 头文件创建 Common Lisp 语言绑定的命令行工具和库.  [麻省理工学院][200].
* [cl-gobject-introspection](https://github.com/andy128k/cl-gobject-introspection) - [Gobject Introspection](https://gi.readthedocs.io/en/latest/)  FFI. 调用 C 库的自动绑定.  [BSD][15]. 生成一个lisp接口 [gir2cl](https://github.com/kat-co/gir2cl) .  [LGPL3][9].
* [cl-cxx-jit](https://github.com/Islam0mar/CL-CXX-JIT)  - Common Lisp 和 C++ 与 JIT 的互操作.  [麻省理工学院][200].

## Clojure

* [ABCLJ](https://github.com/lsevero/abclj)  - 很容易 Clojure 到 Common lisp 互操作.  EPL-2.0.

## Erlang ##

* [CLERIC](https://github.com/flambard/CLERIC)  - 一个通用的 Lisp Erlang 接口.  Erlang 分发协议的实现，可与 erl_interface 和 jinterface 相媲美.  [麻省理工学院][200].

## Java ##

* [cl+j](https://common-lisp.net/project/cl-plus-j/)  - 通过 CFFI 到 JVM 的基于 JNI 的接口. 在 Quicklisp 上不可用. 不能可靠地与所有实现一起工作.  [外籍人士][14].

## Objective-C ##

* [objc-lisp-bridge](https://github.com/fiddlerwoaroof/objc-lisp-bridge)  - 用于与 Objective-C 和 Cocoa 交互的便携式阅读器和桥梁.  [麻省理工学院][200].

## Python ##

* [burgled-batteries](https://github.com/pinterface/burgled-batteries)  - Python 和 Common Lisp 之间的桥梁. 目标是 Lisp 程序可以使用 Python 库. 在 Quicklisp 上不可用.  [麻省理工学院][200].
* [cl4py](https://github.com/marcoheisig/cl4py)  - 库 cl4py（发音为 clappy）允许 Python 程序调用 Common Lisp 库.  [麻省理工学院][200].
* [py4cl](https://github.com/bendudson/py4cl)  - 一个允许 Common Lisp 代码访问 Python 库的库. 它基本上是 cl4py 的逆.  [麻省理工学院][200].
* [cl-python](https://github.com/metawilm/cl-python)  - 在 Common Lisp 中实现 Python.  [LLGPL][8].

也可以看看 [async-process](https://github.com/cxxxr/async-process/).

## .Net Core

* [Bike](https://github.com/Lovesan/bike)  - 一个跨平台的 .Net Core 接口.  [麻省理工学院][200].

## Miscellaneous ##

* [Foil](http://foil.sourceforge.net/)  - 异物接口； 与 JVM 和 CLI 一起工作. 在 Quicklisp 上不可用.  [CPL 1.0][47].


游戏开发
================

* [Xelf](http://xelf.me/)  - 可扩展的游戏库. 在 Quicklisp 上不可用.  [GNU LGPL2.1][11].
* [Trial](https://github.com/shirakumo/trial)  - Trial 是一个非常注重模块化的 OpenGL 游戏引擎. 它应该提供一个包含有用的点点滴滴的大型工具包，您可以从中创建游戏.  [zlib][33].
* [cl-mpg123](https://shirakumo.github.io/cl-mpg123) 和 [cl-out123](https://shirakumo.github.io/cl-out123), bindings libraries for libmpg123 和 libout123 respectively, giving you fast 和 easy to use mp3 decoding 和 cross-platform audio output. [zlib][33].
* [trivial-gamekit](https://borodust.org/projects/trivial-gamekit/getting-started/)  – 使用这个小框架，您将能够制作简单的 2D 游戏：绘制基本的几何形状、图像和文本、播放声音以及聆听鼠标和键盘输入.  [麻省理工学院][200].
* [cl-gamepad](https://shirakumo.github.io/cl-gamepad)  - 访问 Windows、Mac OS 和 Linux 上的游戏手柄和操纵杆.  [zlib][33].
* [virality](https://github.com/bufferswap/ViralityEngine) - 用 Common Lisp [MIT][200] 编写的基于组件的游戏引擎.

Graphics
========

这些是用于处理图形的库，而不是制作 GUI（即小部件工具包），它们有自己的部分.

* ⭐ [Sketch](https://github.com/vydd/sketch)  - 用于创建电子艺术、图形等的 CL 框架.  [麻省理工学院][200].
* [common-cv](https://github.com/byulparan/common-cv)  - CommonLisp 的 OpenCV（开源计算机视觉库）绑定库. 未指定许可证.
* [cl-cairo2](https://github.com/rpav/cl-cairo2)  - 开罗绑定.  [提升 1.0][54]
* [cl-gd](http://weitz.de/cl-gd/)  - 为 GD 图形库提供接口的库.  [自由BSD][39].
* [cl-horde3d](https://github.com/anwyn/cl-horde3d/)  - FFI 绑定到 Horde3D 图形库. 在 Quicklisp 上不可用.  [EPL 1.0][59]
* [cl-jpeg](https://github.com/sharplispers/cl-jpeg)  - 基线 JPEG 编码器和解码器库.  [3 条款 BSD][15].
* [cl-liballegro](https://github.com/resttime/cl-liballegro)  - Allegro 5 游戏编程库的接口和绑定.  [zlib][33].
* [cl-opengl](https://github.com/3b/cl-opengl)  - CFFI 绑定到 OpenGL、GLU 和 GLUT API.  [3 条款 BSD][15].
* [cl-sdl2](https://github.com/lispgames/cl-sdl2)  - 使用 C2FFI 的 SDL2 绑定.  [外籍人士][14].
* [cl-svg](https://github.com/wmannis/cl-svg)  - 用于生成 SVG 文件的基本库.  [外籍人士][14].
* [CLinch](https://github.com/BradWBeer/CLinch)  - 用于 OpenGL 的 Common Lisp 2D/3D 图形引擎.  [自由BSD][39].
* [donuts](https://github.com/tkych/donuts)  - 用于 Common Lisp 的图形绘制 DSL.  [外籍人士][14].
* [dufy](https://github.com/privet-kitty/dufy)  - 各种颜色模型中的精确颜色处理和转换.  [麻省理工学院][200].
* [lispbuilder-sdl](https://github.com/lispbuilder/lispbuilder)  - SDL 的一组绑定.  [外籍人士][14].
* [lisp-magick-wand](https://github.com/TBRSS/lisp-magick-wand)  - ImageMagick 绑定.  [BSD][15]. 不在 Quicklisp 中.
* [okra](https://www.common-lisp.net/project/okra/manual.html)  - CFFI 绑定到 Ogre. 在 Quicklisp 上不可用.  [3 条款 BSD][15].
* [opticl](https://github.com/slyrus/opticl)  - 一个用于表示和处理图像的库.  [BSD_2 条款][17].
* [Varjo](https://github.com/cbaggers/varjo)  - Lisp 到 GLSL 的翻译器.  [BSD_2 条款][17].
* [Vecto](http://www.xach.com/lisp/vecto/)  - 简单的矢量绘图库.  [自由BSD][39].
* [zpng](http://www.xach.com/lisp/zpng/)  - 用于创建 PNG 文件的库.  [自由BSD][39].
* [pngload-fast](https://git.mfiano.net/mfiano/pngload)  - 便携式 Common Lisp 中的 PNG（便携式网络图形）图像格式解码器，强调速度.  [麻省理工学院][200].
* [cl-cuda](https://github.com/takagi/cl-cuda)  - 在 Common Lisp 程序中使用 NVIDIA CUDA 的库.  [LLGPL][8].


GUI
===

有关 GUI 工具包的概述和教程，请参阅 [the Cookbook/GUI](https://lispcookbook.github.io/cl-cookbook/gui.html).

* [LispWork's CAPI](http://www.lispworks.com/products/capi.html)  - 具有移动运行时的便携式 GUI 工具包. 专有，但附带免费版本.
* [Allegro's Common Graphics](https://franz.com/products/allegro-common-lisp/acl_gui_tools.lhtml) - 用于为 Windows、Mac 和 Linux 编写窗口化 GUI 的函数库. 专有的免费版本.
  - 自 Allegro 10.1（2022 年 3 月）以来，IDE 和 Common Graphics 工具包 [runs in the browser](https://franz.com/ftp/pri/acl/cgjs/doc.html).
* [Qtools](https://github.com/Shinmera/qtools/)  - 基于 CommonQt 的 Qt 工具包.  [zlib][33] 也 [Qtools-ui](https://github.com/Shinmera/qtools-ui) （预制的 UI 组件），带有 [videos](https://www.youtube.com/watch?v=KwASFOhYta4&index=7&list=PLkDl6Irujx9Mh3BWdBmt4JtIrwYgihTWp).
* ⭐ [CommonQt](https://github.com/commonqt/commonqt)  - 通过 QtSmoke 为 Qt4 提供的 Common Lisp 绑定.  [自由BSD][39].
* ⭐ [ltk](http://www.peter-herth.de/ltk/)  - Tk 工具包的绑定.  [LLGPL][8] 或 [GNU LGPL2.1][11].
  * [LTk Examples](https://peterlane.netlify.app/ltk-examples/) - 为 tkdocs 教程提供 LTk 示例.
  * [LTk Plotchart](https://peterlane.netlify.app/ltk-plotchart/)  - 围绕 tklib/plotchart 库的包装器，可与 LTk 一起使用. 这包括 20 多种不同的图表类型（xy 图、甘特图、3d 条形图等）.
  * [nodgui](https://notabug.org/cage/nodgui)  - Tk 工具包的绑定，基于 Ltk，带有语法糖和其他小部件.  [LLGPL][8].
* [IUP](https://github.com/lispnik/iup/) - CFFI 绑定到 [IUP](https://www.tecgraf.puc-rio.br/iup/) 便携式用户界面库（ALPHA 之前）.  IUP 是跨平台的（Windows、macOS、GNU/Linux，带有新的 Android、iOs、Cocoa 和 Web Assembly 驱动程序），有许多小部件，有一个小的 api，并且正在积极开发.
* [cl-gtk4](https://github.com/bohonghuang/cl-gtk4)  - 通用 Lisp 的 GTK4/Libadwaita/WebKit 绑定.  [LGPL3][9].
* [cl-cffi-gtk](https://github.com/crategus/cl-cffi-gtk)  - 绑定 GTK+3.  [GNU LGPL2.1][11].
  - 一个教程： [Learn Common Lisp by Example: GTK GUI with SBCL](https://dev.to/goober99/learn-common-lisp-by-example-gtk-gui-with-sbcl-5e5c)
* [cl-gtk2](https://github.com/dmitryvk/cl-gtk2)  - GTK+2 的绑定.  [LLGPL][8].
* [ceramic](https://ceramic.github.io/)  - 使用 Electron 的桌面网络应用程序.  [外籍人士][14].
  * [Electron-lisp-boilerplate](https://github.com/mikelevins/electron-lisp-boilerplate) - 一个基本的样板，用于使用嵌入式 Lisp 帮助程序构建 Electron 应用程序.
  * 电子应用程序骨架： [electron-sbcl-sqlite](https://github.com/mikelevins/electron-sbcl-sqlite/)
   * 注意：在 Electron 中嵌入 lisp web 应用程序的主要思想是将 lisp webserver 作为异步进程启动，并将 Electron 窗口指向 localhost URL. 而已.

但这还不是全部：

* [CocoaInterface](https://github.com/plkrueger/CocoaInterface/) -
 Clozure Common Lisp 的 Cocoa 接口. 构建 Cocoa 用户界面
windows 动态使用 Lisp 代码并绕过典型的 Xcode
过程. 它有
[good documentation and a tutorial](https://github.com/plkrueger/CocoaInterface/blob/master/Documentation/UserInterfaceTutorial.pdf).
* [McCLIM](https://common-lisp.net/project/mcclim/)  - Common Lisp 接口管理器，版本 II 的实现.  [GNU LGPL2.1][11].
* [cl-webkit](https://github.com/joachifm/cl-webkit)  - 与 WebKitGTK+ 的绑定. 还为应用程序添加 Web 浏览功能，利用 WebKit 浏览引擎的全部功能.  [麻省理工学院][200].
* [ftw](https://github.com/fjames86/ftw)  - Win32 GUI 库.  [麻省理工学院][200].
* [eql, eql5, eql5-android](https://gitlab.com/eql)  - 嵌入式 Qt4 和 Qt5 Lisp，嵌入 ECL，可嵌入 Qt. 将 EQL5 移植到 Android 平台.  [麻省理工学院][200].
* [bodge-nuklear](https://github.com/borodust/bodge-nuklear) - 包装在 [Nuklear](https://github.com/vurtun/nuklear) 即时模式 GUI 库.  [麻省理工学院][200].
* [vk](https://github.com/JolifantoBambla/vk)  - Vulkan API 的通用 Lisp/CFFI 绑定.  [麻省理工学院][200].

其他实用程序：

* [file-select](https://github.com/Shinmera/file-select)  - 调用本机系统文件对话框以选择或创建文件的库. 兹利卜.

另请参阅 [demo to use Java Swing from ABCL](https://github.com/defunkydrummer/abcl-jazz).

Mobile
------

* [LispWork's mobile runtime](http://www.lispworks.com/products/lw4mr.html)  - Android 和 iOS. 所有权.
* [LQML](https://gitlab.com/eql/lqml)  - 从 EQL5 派生的与 QML（Qt5 和 Qt6）的轻量级 ECL 绑定.  LGPL 和公共领域.

另请参阅下面的 MOCL，CL 作为移动设备（iOS、Android 和 OSX）的库.


Implementations
===============

* ⭐ [SBCL](http://www.sbcl.org/index.html)  - 钢铁银行 Common Lisp.  CMUCL的一个分支； 编译成机器码.  [符合标准][13]. 公共领域，有一些部分在 [Expat][14] 和 [3-clause BSD][15] 下.
  * 也可以看看： [sbcl-librarian](https://github.com/quil-lang/sbcl-librarian)  - SBCL 的动态库交付工具. 创建可以从 C 或 Python 调用的共享库. 麻省理工学院. [Blog post](https://mstmetent.blogspot.com/2022/04/using-lisp-libraries-from-other.html). [Full example](https://github.com/quil-lang/sbcl-librarian/tree/main/example).
* ⭐ [CCL](https://github.com/CodyReichert/awesome-cl/blob/master///ccl.clozure.com/)  - Clozure Common Lisp； 仅编译器实现，生成本机代码.  [LLGPL][8].
* [ECL](https://common-lisp.net/project/ecl/)  - 可嵌入的 Common Lisp； 编译为 C. [GNU LGPL2.1][11].
* [ABCL](https://common-lisp.net/project/armedbear/)  - 武装熊 Common Lisp； 以 JVM 为目标，编译为字节码.  [标准一致性][4].  [GNU GPL3][2] 与 [类路径异常][3].
* [CLASP](https://github.com/drmeister/clasp)  - 一个新的 Common Lisp 实现，它与 C++ 库和程序无缝互操作，使用 LLVM 编译为本机代码. 这使得 Clasp 可以利用大量预先存在的库和程序，例如在科学计算生态系统之外.  [LGPL2.1][11]（和其他）.

Proprietary:

* [LispWorks](http://www.lispworks.com/) - Common Lisp 的集成跨平台开发工具.
* [Allegro CL](https://franz.com/products/allegro-common-lisp/) - 提供带有许多扩展的完整 ANSI Common Lisp 标准.
* [MOCL](https://wukix.com/mocl) - CL 作为移动设备（iOS 和 Android）和 OSX 的库.

也可以看看：

* [CMUCL](https://github.com/CodyReichert/awesome-cl/blob/master///www.cons.org/cmucl/)  - 来自卡内基梅隆大学的实现. 公共区域.  SBCL 是 CMUCL 的一个分支.
* [GNU CLISP](http://www.clisp.org/) - A GNU implementation; contains a compiler and an interpreter. [Standard conformance][6]. [GNU GPL3][2]. They develop [https://gitlab.com/gnu-clisp/clisp](https://github.com/CodyReichert/awesome-cl/blob/master/on Gitlab).
* [Corman Lisp](https://github.com/sharplispers/cormanlisp)  - 在 Intel 平台上运行的 Microsoft Windows 的 Common Lisp 开发环境.  [麻省理工学院][200].

JSON
====

* [jonathan](https://github.com/Rudolph-Miller/jonathan)  - JSON 编码器和解码器.  [麻省理工学院][200].
* [cl-json](https://github.com/sharplispers/cl-json)  - 高度可定制的 JSON 编码器和解码器.  [麻省理工学院][14].
* [jsown](https://github.com/madnificent/jsown)  - JSON 格式的读取器和写入器.  [外籍人士][14].
* [json-mop](https://github.com/gschjetne/json-mop)  - 用于桥接 CLOS 和 JSON 对象的元类.  [麻省理工学院][200].
* [cl-json-pointer](https://github.com/y2q-actionman/cl-json-pointer)  - JSON 指针实现.  [麻省理工学院][200].

另请参阅 [extensive comparison](https://sabracrolleton.github.io/json-review) JSON 库.

YAML
====

* [cl-yacclyaml](https://github.com/mabragor/cl-yaclyaml)  - 一个纯 lisp YAML 处理器（加载器，但还不是转储器）.  [GPL3][2].
* [cl-yaml](https://github.com/eudoxia0/cl-yaml.git)  - 建立在 libyaml 之上的 YAML 解析器和发射器.  [麻省理工学院][200].


语言扩展
===================

* ⭐ [alexandria](https://common-lisp.net/project/alexandria/)  - 通用实用程序库. 公共区域.
* [serapeum](https://github.com/TBRSS/serapeum/)  - 另一个通用实用程序库.  [外籍人士][14].
* [rutils](https://github.com/vseloved/rutils)  - Common Lisp 的激进但合理的语法实用程序.  [麻省理工学院][200].
* [anaphora](https://common-lisp.net/project/anaphora/)  - 照应宏的集合. 公共区域.
* ⭐ [trivia](https://github.com/guicho271828/trivia/)  - 优化的模式匹配库.  [LLGPL][8].
* [arrow-macros](https://github.com/hipeta/arrow-macros)  - 类似 Clojure 的线程宏.  [麻省理工学院][200].
* [dissect](https://shinmera.github.io/dissect) - when a lot of projects use the “trivial-backtrace” system that just gives them a string with a backtrace, Dissect allows you to capture, step, and completely inspect the stack trace on a variety of Lisp implementations. Also very useful for logging and other situations where execution is automatically continued, but the information of the current stack is still useful to store somewhere. [zlib][33].
* [generic-cl](https://github.com/alex-gutev/generic-cl/)  - 标准 Common Lisp 函数的通用函数接口（相等、比较、算术、对象、迭代器、序列……）.  [麻省理工学院][200]. 另见更轻量级 [generic-comparability](https://github.com/pnathan/generic-comparability) .  [LLGPL][8].
* [hu.dwim.walker](https://quickref.common-lisp.net/hu.dwim.walker.html)  - 代码 walker 和 unwalker（又名 AST 解析器和 unparser）.  [BSD][15]. 也可以看看 [this blog post](http://40ants.com/lisp-project-of-the-day/2020/04/0044-hu.dwim.walker.html).

可移植层
------------------

大量可移植层 [is collected here](https://shinmera.github.io/portability/) . 这里是其中的一些：

* [trivial-arguments](https://github.com/Shinmera/trivial-arguments)  - 一个可移植的库，用于检索函数的参数列表.  [zlib][33].
* [definitions](https://github.com/Shinmera/definitions)  - 一个通用定义内省库. 它使您能够检索与指示符相关的定义或绑定，例如符号、包和一般名称.  [zlib][33].

更改语法
-------------------

* [cl21](https://github.com/cl21/cl21)  - 将 Common Lisp 带入 21 世纪的实验项目.  [外籍人士][14].
* [clamp](https://github.com/malisper/Clamp)  - Arc 语言对 Common Lisp 的简洁性和简洁性.  [艺术许可证 2.0][51].
  * 还 [arc-compat](https://github.com/g000001/arc-compat)  - 弧兼容包.  Perl Foundation 的艺术许可 2.0.
* [cl-syntax](https://github.com/m2ym/cl-syntax)  - 阅读器语法约定.  [LLGPL][8].
* [cl-2dsyntax](http://www.cliki.net/cl-2dsyntax)  - 压痕敏感阅读器系统. 在 Quicklisp 上不可用. 公共区域.
* [cl-annot](https://github.com/m2ym/cl-annot)  - 用于 Common Lisp 的类似 Python 的注释.  [LLGPL][8].
* [cl-reader](https://github.com/digikar99/reader) - 实用程序库
旨在为 lambdas、映射、访问器提供阅读器宏，
哈希表和哈希集.  [麻省理工学院][200].

对于字符串：

* ⭐ [cl-interpol](https://github.com/edicl/cl-interpol/)  - 一组阅读器修改以允许字符串插值.  [BSD][15].
* [mstrings](https://git.sr.ht/~shunter/mstrings)  - 一个阅读器宏，提供视觉上吸引人的多行块.  M-string 修剪前导空格，将行连接在一起，等等.[BSD_3Clause][15].
* [pythonic-string-reader](https://github.com/smithzvk/pythonic-string-reader)  - 受 Python 的三个引号字符串启发的简单且不显眼的读取表修改.  [BSD_3 条款][15].
* [cl-heredoc](https://github.com/outergod/cl-heredoc) - 一个 ["heredocs"](https://github.com/outergod/cl-heredoc) dispatcher. [GPL3][2]. Allows to write: `#>eof>Write whatever (you) "want", no matter what characters, until the magic end sequence has been reached.eof`


CLOS 扩展
---------------

* ⭐ [closer-mop](http://cliki.net/closer-mop)  - 一个兼容层，可纠正许多缺失或不正确的 MOP 功能.  [外籍人士][14].
* [defclass-std](https://github.com/EuAndreh/defclass-std)  - 快速编写 DEFCLASS 表单的快捷宏.  [LLGPL][8].
* [specialization-store](https://github.com/markcox80/specialization-store/)  - 基于类型的通用函数. 简化的 BSD 许可证变体.
* [filtered-functions](https://github.com/pcostanza/filtered-functions)  - 允许使用任意谓词来选择和应用方法.  [麻省理工学院][200].
* [inlined-generic-function](https://github.com/guicho271828/inlined-generic-function) -
将静态调度的速度带入 CLOS.  [LLGPL][8].
* [static-dispatch](https://github.com/alex-gutev/static-dispatch)  - 允许静态（在编译时）而不是动态（运行时）执行标准通用函数调度. 这类似于 C++ 和 Java 等语言中所谓的“重载”.  [麻省理工学院][200].
* [dynamic-mixins](https://github.com/rpav/dynamic-mixins)  - 简单、动态的类组合.  [BSD_2 条款][17].
* [fast-generic-functions](https://github.com/marcoheisig/fast-generic-functions)  - 密封您的通用功能以进一步提高性能.  [麻省理工学院][200].
* [polymorphic functions](https://github.com/digikar99/polymorphic-functions)  - 一种在类型而不是类上分派的函数类型，部分支持在可选和关键字参数类型上分派. 仍处于试验阶段（2021 年 5 月）.  [麻省理工学院][200].
   - 多态函数对提供给它的参数类型进行调度. 这有助于分派专门的数组以及用户定义的类型.
  - 有关专业化存储和快速通用功能的差异，请参阅其自述文件.

并且：

* [slot-extra-options](https://github.com/some-mthfka/slot-extra-options)  - 让您构建一个元类，进而让您在其类中指定额外的插槽选项.  [LGPL3][9].

功能扩展
-------------------

* [cl-hooks](https://github.com/scymtym/architecture.hooks/)  - Hooks 扩展点机制（如已知的，例如，来自 GNU Emacs）.  LGPL.
* [method-hooks](https://gitlab.com/Gnuxie/method-hooks)  - 当 CLOS 方法组合每个方法只允许一个钩子时，这个库允许任意数量的钩子.  Mozilla 公共许可证.
* [cl-advice](https://github.com/lisp-mirror/budden-tools/blob/213ab2b52a1b0c0b496efd30c3b5143f5c8e1ff2/cl-advice/README.md)  - SBCL、CCL、LispWorks 和 Allegro 的可移植层建议库的尝试. 不在 Quicklisp 中.
* [nhooks](https://github.com/atlas-engineer/nhooks) - 具有关键改进的钩子（扩展点）的增强实施.

Iteration
---------

* ⭐ [iterate](https://common-lisp.net/project/iterate/)  - 可扩展和 Lispier 的 Common Lisp 的迭代构造.  [麻省理工学院][200].
* [for](https://shinmera.github.io/for/)  - 一个简洁、简洁和可扩展的迭代宏. 与循环不同，它是可扩展且合理的，与迭代不同，它不需要代码遍历并且更容易扩展.  [zlib][33].
* [series](https://github.com/tokenrove/series/wiki)  - 完全没有任何运行时损失的功能风格.  [麻省理工学院][200].
* [gmap](https://github.com/slburson/misc-extensions/blob/master/src/gmap.lisp)  - 一个简洁且可扩展的迭代工具，具有与 FSet 良好集成的优点（参见数据结构部分），因为它是由同一作者编写的. 在 Quicklisp 作为 `misc-extensions` 的一部分. 公共区域.
* [trivial-do](https://github.com/yitzchak/trivial-do/)  - Common Lisp 的附加 dolist 样式宏.  [麻省理工学院][200].
* [doplus](https://github.com/alessiostalla/doplus) – 另一个可扩展的迭代库，类似于 :for.
* [snakes](https://github.com/BnMcGn/snakes)  - 用于 Common Lisp 的 Python 样式生成器. 包括一个 itertools 的端口.  [阿帕奇2] [89].
* [picl](https://github.com/anlsh/picl)  - Python 的 itertools 包的（几乎）完整端口，在适用的情况下具有惰性，并且不依赖于 cl-cont.  [麻省理工学院][200].
* [gtwiwtg](https://github.com/lisp-mirror/gtwiwtg)  - 一个惰性序列库. 类似于“系列”，但不完整. 然而，它有一个“现代”API，其中包含易于使用的 `take`、`filter`、`for`、`fold` 等内容.


Lambda 速记
-----------------

* [fn](https://github.com/cbaggers/fn)  - 几个 lambda 速记宏.  `(fn* (+ _ _)) --&gt; (lambda (_) (+ _ _))`. 公共区域.
* [f-underscore](https://gitlab.common-lisp.net/bpm/f-underscore)  - 一个小型函数式编程工具库.  `(f_ (+ _ _)) -&gt; (lambda (_) (+ _ _))`. 公共区域.
* [cl-punch](https://github.com/windymelt/cl-punch/)  - 类似 Scala 的匿名 lambda 文字.  `(mapcar ^(* 2 _) &#39;(1 2 3 4 5))`.  [麻省理工学院][200].


See also CL21 and [Rutils](https://github.com/vseloved/rutils).



非确定性逻辑编程
------------------------------------

* [cl-prolog2](https://github.com/guicho271828/cl-prolog2)  - 来自 Common Lisp 的 ISO Prolog 实现的通用接口.  [麻省理工学院][200].
* [Screamer](https://github.com/nikodemus/screamer) - 增加通用
  Lisp 几乎具有 Prolog 和
  约束逻辑编程
  语言. [Blog post](https://chriskohlhepp.wordpress.com/reasoning-systems/specification-driven-programming-in-common-lisp/)
  解决 Project Euler 难题.  [麻省理工学院][200].
* [Screamer+](https://github.com/yakovzaytsev/screamer-plus)  - 增加 SCREAMER 的表现力.  [麻省理工学院][200].
* [Temperance](https://github.com/sjl/temperance)  - 逻辑编程.  [麻省理工学院][200]. 专注于性能，同时考虑到一般游戏玩法.

反应式编程
--------------------

* [Cells](https://github.com/kennytilton/cells)  - 数据流编程范式的实现，CLOS 的反应式电子表格般的表现力. 用于构建一个 [algebra learning system](http://tiltontec.com/) . 和 [documentation](https://github.com/stefano/cells-doc/) .  Lisp LGPL.

合约编程
--------------------

* [quid-pro-quo](https://github.com/sellout/quid-pro-quo) - 合同
   Eiffel&#39;s Design by Contract™ 风格的编程库. 公共区域.

Typing
------

* [Coalton](https://github.com/coalton-lang/coalton/)  - 一种高效、静态类型的函数式编程语言，可增强 Common Lisp.  [麻省理工学院][200].
* [cl-algebraic-data-type](https://github.com/stylewarning/cl-algebraic-data-type)  - 一个以与 Haskell 或 ML 类似的精神定义代数数据类型的库.  [3 条款 BSD][15].
* [trivial-types](https://github.com/m2ym/trivial-types)  - 提供缺失但重要的类型定义，例如“proper-list”、“association-list”、“property-list”和“tuple”.  [LLGPL][8].
* [defstar](https://bitbucket.org/eeeickythump/defstar/src/master/)  - 一组宏，用于轻松包含 lambda 列表中参数的类型声明.  [GNU GPL3][2]


学习和教程
=====================

## Online ##

Beginner
--------

* [Learn X in Y minutes - Where X = Common Lisp](https://learnxinyminutes.com/docs/common-lisp/) - 涵盖基本知识的 Small Common Lisp 教程.
* [Lisp Koans][201] - 该项目通过许多 Common Lisp 语言功能逐步引导学习者.
 * [Practical Common Lisp][206] - Common Lisp 的一个很好的介绍性文本，带有实际示例. 更好地阅读 [a Firefox add-on](https://github.com/vale981/practical-cl-beautified).
* [Common LISP: A Gentle Introduction to Symbolic Computation](http://www.cs.cmu.edu/afs/cs.cmu.edu/user/dst/www/LispBook/index.html) - 一个很好的语言介绍.
* [Successful Lisp](http://successful-lisp.blogspot.com/) - 一本适合有一定编程背景的初学者的好书.
* [Lisp Quickstart](https://cs.gmu.edu/~sean/lisp/LispTutorial.html) - 一个快速入门和编写 Common Lisp 的好教程.
* [Casting SPELs in LISP](http://www.lisperati.com/casting.html) - 一种在阅读漫画书时学习 LISP 的有趣方式.
   &gt; 感谢您支持我在 Udemy 上的工作. 另请注意，我不时发布免费优惠券，并且 Udemy 经常提出激烈的促销活动，但您也可以向我索要免费优惠券.

Intermediate
------------

* [The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/)
* [Lisp Tips](https://github.com/lisp-tips/lisp-tips/issues/)  - 一个包含有用提示和技巧的博客. 的延续 [Common Lisp tips](http://lisptips.com/).
* [Lisp project of the day](http://40ants.com/lisp-project-of-the-day/) - 一个展示许多 Lisp 库的博客.

Advanced
--------

 * [Let Over Lambda][156] - 一本关于高级宏技术的书. 前六章可在​​线获取.
* [On Lisp](http://www.paulgraham.com/onlisp.html) - Paul Graham 关于 Lisp 宏（和其他有趣的东西）的惊人书籍.
* [Programming Algorithms in Lisp](https://link.springer.com/book/10.1007/978-1-4842-6428-7) - 更新版本的“[Programming Algorithms](https://leanpub.com/progalgs)&quot;; 在 Lisp 中使用数据结构和算法编写高效程序的综合指南.

编码平台
----------------

* [Codewars](https://docs.codewars.com/languages/commonlisp/) - 一个代码训练平台，支持 Common Lisp (SBCL).

Web开发
--------

* [Lisp for the Web](https://leanpub.com/lispweb) - 一本指导您构建三层投票 Web 应用程序的书.
* [Lisp Web Tales](https://leanpub.com/lispwebtales) - 使用简单的教程 [hunchentoot](http://edicl.github.io/hunchentoot/), [cl-redis](https://github.com/vseloved/cl-redis), [restas](https://github.com/archimag/restas), [SEXML](https://github.com/madnificent/SEXML), [Postmodern](https://github.com/marijnh/Postmodern)， 和更多.
* [Section on Web Development in The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/web.html) - 介绍性教程，涵盖 Web 服务器设置、路由、weblocks、模板、错误处理、打包、热重载、数据库连接和部署，以及当前 lisp Web 开发生态系统中的其他主题.

Reference
---------

* [Common Lisp Quick Reference](http://clqr.boundp.org/index.html)  - ANSI CL 规范的精炼袖珍版. 可作为 PDF 下载.
* [CLHS](http://www.lispworks.com/documentation/lw50/CLHS/Front/index.htm)  - Common Lisp HyperSpec；  ANSI CL 标准，以超文本形式.
* [CLOS MOP specification](https://clos-mop.hexstreamsoft.com/) - 元对象协议的艺术第 5 章和第 6 章的现代公共领域在线版本
* [Common Lisp Standard Draft (pdf)](https://franz.com/support/documentation/cl-ansi-standard-draft-w-sidebar.pdf) - Common Lisp 规范的标准草案，带有侧边栏的格式良好的 PDF.
* [Common Lisp the Language](http://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html) - The original standard for Common Lisp before the ANSI spec.
* [Minispec](https://lamberta.github.io/minispec/)  - 更友好但不完整的 CLHS 版本. 还包含一些常用 CL 库（例如 Alexandria）的文档.
* [Simplified Common Lisp reference](http://jtra.cz/stuff/lisp/sclr/index.html) - CLHS 的简化版本.
* [CDR](https://cdr.common-lisp.dev/)  - 通用 Lisp 文档存储库.  Common Lisp 社区感兴趣的文档存储库.  CDR 文档最重要的属性是它永远不会改变：如果您引用它，您可以确定您的引用将始终引用完全相同的文档.
  - Common Lisp 文档存储库托管在 [Zenodo](https://zenodo.org/communities/cdr/).

## Offline ##

CLHS 可通过 [archive](https://github.com/CodyReichert/awesome-cl/blob/master/ftp://ftp.lispworks.com/pub/software_tools/reference/HyperSpec-7-0.tar.gz) 并且作为文档设置 [Dash](https://kapeli.com/dash), [Zeal](https://zealdocs.org/) 和 [Velocity](https://velocity.silverlakesoftware.com/).

Beginner
--------

* [Land of Lisp](http://landoflisp.com/) - 一个有趣的、面向游戏的 Common Lisp 介绍.
* [Practical Common Lisp][206] - Common Lisp 的一个很好的介绍性文本，带有实际示例.

Intermediate
------------

* [ANSI Common Lisp](http://www.paulgraham.com/acl.html)  - 全面、实用地涵盖整个语言，并附有练习. 由于[一些警告][20]，不推荐作为入门文本.
* [Common Lisp Recipes](http://weitz.de/cl-recipes/)  - **Common Lisp Recipes** 是一系列问题的解决方案以及您在使用 Common Lisp 编写实际应用程序时可能遇到的问题的答案. 发表于 2015 年.

Advanced
--------

 * [Let Over Lambda][156] - 一本关于高级宏技术的书. 所有八章都可以在印刷版中找到.
* [Common Lisp 中的面向对象编程：CLOS 程序员指南][21] - 一本古老但非常全面的 CLOS 书籍.
* [人工智能编程范式：Common Lisp 案例研究][157] - 一本涵盖一些高级 Lisp 的 AI 编程书籍.

其他书籍
-----------

* [Building Problem Solvers](https://www.qrg.northwestern.edu/bps/readme.html) ([PDF](http://www.qrg.northwestern.edu/bps/BPS-Searchable.pdf)) 由 Ken Forbus 和 Johan de Kleer 撰写，由 MIT Press 免费提供——这是一本在标准人工智能文本中独一无二的书籍，它结合了科学与工程、理论和工艺来描述 AI 推理系统的构建，并包含说明这些想法的代码.

Community
---------

* [/r/Common_Lisp](https://www.reddit.com/r/Common_Lisp/) - 关于 Common Lisp 的 subreddit
* [/r/learnlisp](https://www.reddit.com/r/learnlisp/) - 一个 subreddit，用于提问和获取有关 Lisp 的帮助
* [common-lisp.net](https://common-lisp.net)
* [lisp-lang.org](https://lisp-lang.org/)
* [Lisp Discord Server](https://discord.gg/hhk46CE)
* [#commonlisp](https://irclog.tymoon.eu/libera/%23commonlisp) 在 Libera Chat - 主要的 Common Lisp IRC 频道.
* [#lisp](https://irclog.tymoon.eu/libera/%23lisp) 在 Libera Chat - 所有 Lisp 方言的 IRC 频道.
* #clschool on Libera Chat - IRC channel for learning Common Lisp.
* #lispcafe on Libera Chat - IRC channel for off-topic discussions.
* [Common Lisp chat](https://chat.hexstreamsoft.com/) - Keybase 团队具有明确定义的规则和保留策略.

图书馆经理
===============

 * ⭐ [Quicklisp][16] - 包含许多库的库管理器，具有简单的依赖管理.  [外籍人士][14].
* [CLPM](https://gitlab.common-lisp.net/clpm/clpm)  - Common Lisp 的包管理器，致力于将包管理器进程本身与使用它的客户端映像完全分离.  [BSD_2 条款][17].
* [Ultralisp](http://ultralisp.org/)  - 一个 Quicklisp 发行版，每 5 分钟更新一次，并且可以一键添加他的项目.  [BSD][15].
*[Roswell](https://github.com/roswell/roswell)  - Lisp 实现安装程序、脚本启动器等.  [麻省理工学院][200].
* [Qlot](https://github.com/fukamachi/qlot)  - 项目本地库安装程序，类似于 Bundler 或 Carton.  [外籍人士][14].
* [Quicksys](https://lisp.com.br/quicksys/)  - 从多个 Quicklisp 发行版安装系统.  [麻省理工学院][200].
* [Quickutil](https://github.com/tarballs-are-good/quickutil)  - 实用程序管理器，类似于 Quicklisp，但用于小型实用程序而不是整个库.  [3 条款 BSD][15].

可能有帮助：

* [quick-patch](https://github.com/tdrhq/quick-patch/)  - 无需使用 git 子模块即可轻松覆盖 quicklisp 项目.  MPL-2.0.
* [print-licenses](https://github.com/vindarel/print-licenses)  - 打印项目及其依赖项使用的许可证.  [麻省理工学院][200].

### Interfaces to other package managers

* [linux-packaging](https://gitlab.com/ralt/linux-packaging)  - 使用单个 ASDF 声明为您的应用程序构建 .deb、.rpm 或 .pkg 包. 在引擎盖下使用 fpm.  [麻省理工学院][200].
* [qldeb](https://github.com/ralt/qldeb) - Quicklisp 系统到 debian 包，以及 [deb-packager](https://github.com/ralt/deb-packager) （只需通过定义一个 s 表达式来创建一个 debian 包）和一个介绍性 [blog post](http://margaine.com/2015/12/22/quicklisp-packagecloud-debian-packages.html) . 两者[麻省理工学院][200].
* [ql-to-deb](https://github.com/dimitri/ql-to-deb)  - 从 Quicklisp 版本更新 cl-* debian 软件包.  WTFPL.
* [dh-quicklisp-buildapp](https://github.com/ralt/dh-quicklisp-buildapp)  - debhelper 实用程序，让您几乎毫不费力地将基于 quicklisp 的 Common Lisp 代码编译为 .deb 中的 buildapp 二进制文件.  [麻省理工学院][200].
* [cl-brewer](https://github.com/can3p/cl-brewer)  - 用于（命令行）通用 lisp 应用程序的自制公式生成器. 公共区域.
* [flatpack-common-lisp](https://gitlab.com/ralph-schleicher/flatpak-common-lisp) - 一个 BuildStream 项目，用于为 Common Lisp 应用程序构建基于 Flatpak 的运行时环境.


也可以看看 [asdf-sbcl](https://github.com/smashedtoatoms/asdf-sbcl)，通用包管理器的插件.


机器学习
================

* [MGL](https://github.com/melisgl/mgl)  - 用于反向传播神经网络、玻尔兹曼机、高斯过程等的机器学习库.  [麻省理工学院][200].
  * 某些部分最初由 Ravenpack International 提供.
  - 由其使用 [author](https://github.com/melisgl) 至 [win](https://github.com/melisgl/higgsml) 希格斯玻色子机器学习挑战赛.
* [clml](https://github.com/mmaul/clml)  - 最初由日本公司 Mathematicl Systems Inc. 开发. 带一个 [tutorial](https://mmaul.github.io/clml.tutorials//2015/08/08/CLML-Time-Series-Part-1.html) .  [LLGPL][8].
* [antik](https://www.common-lisp.net/project/antik/)  - Common Lisp 中科学和工程计算的基础.  GPL. 还 [mgl-mat](https://github.com/melisgl/mgl-mat) 和 [LLA](https://github.com/tpapp/lla).

学分：borretti.me [State of CL Ecosystem 2015](http://borretti.me/article/common-lisp-sotu-2015#machine-learning).


自然语言处理
===========================

* [cl-nlp](https://github.com/vseloved/cl-nlp)  - 自然语言处理工具集.  [Apache2.0][89].
* [babel2](https://github.com/lucas8/Babel2/) - 流体构造语法实现、计算框架和基于统一的语法形式 [Apache2.0][89].
* [sparser](https://github.com/ddmcdonald/sparser)  - 英语的自然语言理解系统.  [日食][209].



网络和互联网
====================

See [Cliki](http://www.cliki.net/Web) 更多.

HTTP 客户端
------------
* [Dexador](https://github.com/fukamachi/dexador)  - 一个 HTTP 客户端，旨在取代 Drakma.  [麻省理工学院][200].
* [Carrier](https://github.com/orthecreedence/carrier)  - 基于 cl-async 和 fast-http 构建的轻量级异步 HTTP 客户端.  [麻省理工学院][200].
* [fast-http](https://github.com/fukamachi/fast-http)  - Common Lisp 的快速 HTTP 请求/响应解析器.  [麻省理工学院][200].


HTTP 服务器
------------
*[Clack](https://github.com/fukamachi/clack)  - 受 Rack 和 WSGI 启发的 Web 应用程序环境.  [LLGPL][8]. 为选择的网络服务器提供统一的接口（默认为 Hunchentoot）. 随着更多 [getting started guide](https://jasom.github.io/clack-tutorial/posts/getting-started-with-clack/).
* ⭐ [Hunchentoot](http://weitz.de/hunchentoot/)  - 网络服务器.  [2 子句 BSD][207]
* [zaserve](https://github.com/gendl/aserve) - 由 Franz Inc. [LLGPL][8] 开发的 AllegroServe 的便携式分叉.
* [wookie](https://github.com/orthecreedence/wookie)  - 异步 HTTP 服务器.  [外籍人士][14].
* [woo](https://github.com/fukamachi/woo)  - 基于 libev 的快速非阻塞 HTTP 服务器.  [麻省理工学院][200].
* [cl-http2-protocol](https://github.com/akamai/cl-http2-protocol)  - Draft-14 的 HTTP/2 协议的纯 Common Lisp 传输不可知实现.  [麻省理工学院][200].

### Hunchentoot plugins

* [easy-routes](https://github.com/mmontone/easy-routes)  - Hunchentoot 之上的路线处理系统. 它支持基于 HTTP 方法的调度、从 url 路径提取参数、装饰器、从路由名称生成 url 等 [MIT][200].
* [hunchentoot-cgi](https://github.com/slyrus/hunchentoot-cgi)  - 用于从 hunchentoot 网络服务器执行 CGI 脚本的库.  [BSD][207].
* [hunchentoot-multi-acceptor](https://github.com/moderninterpreters/hunchentoot-multi-acceptor/)  - 使用单个端口在单个 hunchentoot 接受器上路由多个域（虚拟主机）.  [Apache2.0][89].
* [hunchentoot-auth](https://github.com/slyrus/hunchentoot-auth)  - 使用密码实现用户身份验证.  [BSD][207].
* [hunchentoot-errors](https://github.com/mmontone/hunchentoot-errors)  - 使用请求和会话信息增强 Hunchentoot 错误页面和日志.  [麻省理工学院][200].

也可以看看：

* [cl-tbnl-gserver-tmgr](https://github.com/mdbergmann/cl-tbnl-gserver-tmgr)  - 基于 Hunchentoot Gserver 的任务管理器.  cl-gserver 是一个类似于 actor 的消息传递库（请参阅下面的“Actor 模式”）. 实验性的.

### Clack plugins

* [tiny-routes](https://github.com/jeko2000/tiny-routes)  - 针对 Clack 的 Common Lisp 的小型路由库.  [BSD_3 条款][15].
* [clack-errors](https://github.com/eudoxia0/clack-errors)  - Clack 的错误页面中间件.  [LLGPL][8].
* [clath](https://github.com/BnMcGn/clath) - 单点登录
   Clack 的中间件. 它允许使用 OAuth1.0a、OAuth2 进行基本登录
  和 OpenID. 在撰写本文时，它支持来自
  谷歌、Twitter、LinkedIn、StackExchange、Reddit 和 Github.  [Apache2.0][89].
* [clack-pretend](https://github.com/BnMcGn/clack-pretend) - 一个测试
  和clack的调试工具.  [Apache2.0][89].
* [hermetic](https://github.com/eudoxia0/hermetic)  - 基于 Clack 的 Web 应用程序的安全性.  [外籍人士][14].
* [live-reload](https://github.com/knobo/live-reload)  - 实时重新加载原型为 clack.  [LLGPL][8].
* [clack-static-asset-middleware](https://github.com/fisxoj/clack-static-asset-middleware)  - 用于 clack 的缓存清除静态资产中间件.  [麻省理工学院][200].

对于路由，我们也可以使用贪睡（见下文）.

网络框架
--------------

* [Caveman](https://github.com/fukamachi/caveman)  - 一个强大的网络框架.  [LLGPL][8].
  示例项目： [Quickdocs](https://github.com/quickdocs)
* [ningle](https://github.com/fukamachi/ningle)  - 一个超微型网络框架.  [LLGPL][8]. [ninglex](https://github.com/defunkydrummer/ninglex) ，一个扩展且对新手友好的 ningle（主要是更容易处理查询参数）.  [麻省理工学院][200].
* [radiance](https://github.com/Shirakumo/radiance)  - 一个网络应用环境和框架.  [zlib][33].

以 REST 为中心的框架：

* [Snooze](https://github.com/joaotavora/snooze)  - 一个 RESTful Web 框架.  Web 服务器不可知. 目前支持 Hunchentoot 和 Clack. 路由只是函数，HTTP 条件只是 Lisp 条件.  [LLGPL][8].
* [cl-rest-server](https://github.com/mmontone/cl-rest-server)  - 用于编写 REST Web API 的库. 使用模式进行验证，用于日志记录、缓存、权限或身份验证的注释，通过 Swagger 的文档等 [MIT][200].
* [apispec](https://github.com/cxxxr/apispec)  - 用于处理 Web API 请求和响应的 Common Lisp 库.  [BSD_3 条款][15].
  - 采用 OpenAPI3 yaml 规范并允许验证和解析 HTTP 请求标头、参数和正文.
* [cl-odata-client](https://github.com/copyleft/cl-odata-client) - 用于访问的 Common Lisp 客户端库 [OData services](https://www.odata.org) .  [麻省理工学院][200].

身份验证插件（除了上面的 Clack 插件）：

* [cl-cas](https://github.com/fferrere/cl-cas) - 帮助图书馆 [CAS authenticaton](https://apereo.github.io/cas/6.0.x/protocol/CAS-Protocol.html) 到 Common Lisp Web 应用程序. 不在 Quicklisp 中.
  * [cas-middleware](https://github.com/fferrere/cas-middleware) - Caveman 的 CAS 身份验证中间件.
  * [cas-demo](https://github.com/fferrere/cas-demo) - 一个演示项目.

还有更多的项目，或多或少停产但很有趣. 查看其他资源.

### Isomorphic web frameworks

* [CLOG](https://github.com/rabbibotton/clog)  - Common Lisp Omnificent GUI. 使用 Web 技术为本地或远程应用程序生成图形用户界面.  [BSD_3 条款][15].
  - CLOG 基于 GNOGA 的思想，这是作者为 Ada 编写的框架，自 2013 年起用于商业生产代码.
* [Interactive SSR](https://github.com/interactive-ssr/client/blob/master/main.org/)  - ISSR 允许您在不编写客户端脚本的情况下制作交互式网页. 不需要有关 Javascript 或 DOM 的知识.
  - 它与 Phoenix LiveView 或 Hotwire 没有什么不同.
* [Weblocks](https://github.com/40ants/reblocks)  - 一个基于小部件的框架，具有“解决 JavaScript 问题”的内置 ajax 更新机制.  [LLGPL][8].


解析html
------------
 * [Plump][71] - 一个宽松的 HTML/XML 解析器，可以容忍格式错误的标记.  [zlib][33]. 最好与 [lquery][72] 和 [clss](https://github.com/Shinmera/CLSS).

查询 HTML/DOM
-----------------
 * [lquery][72] - 一个类似 jQuery 的 HTML/DOM 操作库.  [zlib][33].

另请参阅下面的 XML 部分以了解 xpath 库等.


HTML 生成器和模板
-----------------------------

* [spinneret](https://github.com/ruricolist/spinneret)  - 通用 Lisp HTML5 生成器.  [外籍人士][14].
* ⭐ [cl-who](http://weitz.de/cl-who/)  - 古老的 HTML 生成器.  [自由BSD][39].
* ⭐ [Djula](https://github.com/mmontone/djula)  - 将 Django 模板引擎移植到 Common Lisp.  [外籍人士][14].
  - [cl-djula-tailwind](https://github.com/rajasegar/cl-djula-tailwind) - 在您的 Djula 模板中使用 TailwindCSS 类，无需任何 JavaScript 或 Node.js 工具.
* [eco](https://github.com/eudoxia0/eco)  - 快速、灵活、对设计师友好的模板引擎.  [外籍人士][14].
* [TEN](https://github.com/mmontone/ten)  - Djula 的完整性符合 Eco 的可用性.  [麻省理工学院][200].
* [cl-closure-template](https://github.com/archimag/cl-closure-template)  - Google 的 Closure 模板的实现.  [LLGPL][8].
* [flute](https://github.com/ailisp/flute)  - 一个易于组合的 HTML5 生成库，具有最简单的语法.  [麻省理工学院][200].
* [clip](https://shinmera.github.io/clip)  - 一个 HTML 模板处理器，其中的模板是用 HTML 编写的.  [zlib][33].
* [lsx](https://github.com/fukamachi/lsx/) 和 [markup](https://github.com/moderninterpreters/markup)  - 两个类似 JSX 的模板引擎，其中 HTML 标记是 Common Lisp 代码.  `markup` 带有一个 Emacs 包.

URI 处理
------------

* [quri](https://github.com/fukamachi/quri) - 另一个 URI 库
  常见的 Lisp. 支持用户信息、IPv6 主机名、编码/解码
  实用程序，… [BSD_3Clause][15].
* [cl-slug](https://github.com/EuAndreh/cl-slug)  - 一个用于制作 slug 的小型库，主要用于 URI，在 CamelCase 中转换，删除重音和标点符号，适用于英语及其他语言.  [LLGPL][8].

Javascript
----------

* ⭐ [Parenscript](https://common-lisp.net/project/parenscript/)  - 从 Common Lisp 到 Javascript 的翻译器.  [3 条款 BSD][15]. 看 [Trident-mode](https://github.com/johnmastro/trident-mode.el)，一种 Emacs 模式，提供与浏览器的实时交互.[unlicence][5].
  * [paren6](https://github.com/BnMcGn/paren6/) - 一组用于 Parenscript 的 ES6 宏.
* [parse-js](http://marijnhaverbeke.nl/parse-js/) - 用于解析 ECMAScript 3 的包.[zlib][33].
* [JSCL](https://github.com/jscl-project/jscl)  - 从一开始就设计为自托管的 CL 到 JS 编译器. 缺少 CLOS、格式和循环.
* [CL-JavaScript](http://marijnhaverbeke.nl/cl-javascript/)  - 从 Javascript 到 Common Lisp 的翻译器. 在 Quicklisp 上不可用.  [外籍人士][14].
* [Wuwei](https://github.com/mtravers/wuwei/)  - 用于构建基于 Ajax 的网页的工具包.  [麻省理工学院][200].
* [SmackJack](https://github.com/aarvid/SmackJack)  - 使用 parenscript 生成 javascript 和 hunchentoot（目前）作为 Web 服务器的 Ajax Common Lisp 库. 还允许服务器端 lisp 函数调用客户端 parenscript 之一.  [麻省理工学院][200].
* [remote-js](https://github.com/ceramic/remote-js)  - 将 JavaScript 从 Common Lisp 发送到浏览器.  [麻省理工学院][200].
* [sigil](https://github.com/BnMcGn/sigil)  - Javascript 命令行编译器和 REPL 的 Parenscript.  [麻省理工学院][200].


**React** 的实用程序：

* [cl-react](https://github.com/helmutkian/cl-react)  - 用于在 ReactJs 中构建 Web 应用程序的 Common Lisp (Parenscript) 实用程序. 麻省理工学院.
* [Panic](https://github.com/michaeljforster/panic) ，一个用于 React 的 Parenscript 库. 不在 Quicklisp 中.  [麻省理工学院][200]. 它 [TodoMVC example](https://github.com/40ants/todomvc/blob/common-lisp-example/examples/common-lisp-react/src/app.lisp).
* [Parenscriptx](https://github.com/jasom/parenscriptx)  - Parenscript 宏来帮助生成反应代码.  [麻省理工学院][200].
* [jscl-react](https://github.com/nilesr/jscl-react)  - 使用 jscl 在 common lisp 中编写反应组件的 Web 框架. 未指定许可证.


也可以看看：

* [trident-mode](https://github.com/johnmastro/trident-mode.el), 一个 Emacs
用于实时 Parenscript 交互的次要模式.



Deployment
----------

* [heroku-buildpack-common-lisp](https://gitlab.com/duncan-bayne/heroku-buildpack-common-lisp)  - 一个使用 Roswell 编译 Common Lisp 应用程序的 Heroku buildpack.  LGPL3.
* [cube](https://github.com/xh4/cube)  - 根据 Swagger 规范生成的 Common LISP 的 Kubernetes 客户端库.  [麻省理工学院][200].
* [s2i-lisp](https://github.com/container-lisp/s2i-lisp)  - 基于 CentOS 或 RHEL7 的 Source-to-Image 构建器镜像，用于为 OpenShift（以及 Docker）构建 Common LISP 镜像. 它具有带有 Quicklisp 安装、SLIME 或 SLY 集成的最新 SBCL，并允许通过环境变量进行自定义.  [阿帕奇2][89]
* [deploy](https://shinmera.github.io/deploy)  - Lisp 应用程序的二进制部署工具包，额外支持外部共享库.  [zlib][33].
* [cl-aws-runtime-test](https://github.com/y2q-actionman/cl-aws-custom-runtime-test)  - 在 AWS lambda 上使用 Common Lisp (SBCL) 作为自定义运行时的示例.  WTFPL.

也可以看看：

- [Platform.sh](https://platform.sh/blog/2019/lisp/) 有 Common Lisp 支持，所以也有 [OVH](https://docs.ovh.com/ie/en/web-paas/languages-lisp/) 通过他们的 Web PaaS 合作伙伴关系.
- [Heliohost](https://www.heliohost.org/) 免费托管解决方案.

Monitoring
----------

* [prometheus.cl](https://github.com/deadtrickster/prometheus.cl)  - Prometheus.io 客户端. 用于 SBCL 和 Hunchentoot 指标（内存、线程、每秒请求数……）的 Grafana 仪表板.  [麻省理工学院][200].
* [cl-sentry-client](https://github.com/mmontone/cl-sentry-client)  - 基于云的错误监控系统 Common Lisp 的 Sentry 客户端.  [麻省理工学院][200].
* [rollbar.lisp](https://github.com/adventuring/rollbar.lisp) - 接口 [Rollbar.com](https://rollbar.com/)，一个错误跟踪软件.


Websockets
----------

* [usocket](https://github.com/usocket/usocket)  - 一个可移植的 TCP 和 UDP 套接字接口.  [外籍人士][14].
* [Portal](https://github.com/charJe/portal)  - 用于 Common Lisp 的便携式 websocket，使用 usocket.  [LLGPL][8].
* [clws](https://github.com/3b/clws)  - CL 中的 websockets 服务器，建立在 IOlib 和 libfixposix 之上. 未指定许可证.
* [Hunchensocket](https://github.com/joaotavora/hunchensocket)  - 用于 Common Lisp 的符合 RFC6455 的 WebSocket，作为 Hunchentoot 的扩展.  [麻省理工学院][200].
* [websocket-driver](https://github.com/fukamachi/websocket-driver) - 基于克拉克.

 *编者注：在撰写本文时，我们似乎没有针对 Common Lisp 的全功能 websocket 实现. 但是，我们可以推荐 Portal，我们邀请您仔细检查 Hunchensocket 和 websocket-driver 的当前问题.*


Web 开发实用程序
-------------------------

### Assets management

* [Rock](https://github.com/eudoxia0/rock) - 资产经理
  常见的 Lisp. 它基本上是 Bower 和
  网络资产.  [麻省理工学院][200].

### Browser tests

* [cl-webdriver-client](https://github.com/copyleft/cl-webdriver-client/) - WebDriver 的绑定库（支持 Selenium 4.0）.

### Form handling

* [cl-forms](https://github.com/mmontone/cl-forms)  - Common lisp 的 Web 表单处理库.  [麻省理工学院][200].

### User login and password management

* [cl-authentic](https://github.com/charJe/cl-authentic)  - Common Lisp (web) 应用程序的密码管理.  [LLGPL][8].
  - 安全密码存储：无明文，通过 Ironclad 使用您选择的哈希算法，存储在 SQL 数据库中，
  - 一次性令牌的密码重置机制（适合邮寄给用户确认），
  - 可选择使用确认令牌创建用户（适合邮寄给用户），
* [mito-email-auth](https://github.com/40ants/mito-email-auth) - 帮助通过电子邮件向他们发送唯一代码来验证网站用户的身份.

另请参见上面的 mito-auth.

### Web project skeletons and generators

* [cl-cookieweb](https://github.com/vindarel/cl-cookieweb)  - 用于启动 Web 项目的 Cookiecutter 模板.  [BSD_3 条款][15]. 不在 Quicklisp 中.
  * 提供一个工作玩具网络应用程序，带有 Hunchentoot 网络服务器、easy-routes、Djula 模板、Bulma 样式、基于 SQLite、迁移、示例表定义和使用 FiveAM 的测试套件.
* [make-like](https://github.com/container-lisp/make-like)  - LIKE（Lisp In Kubernetes + Emacs）应用程序的应用程序模板构建器.  [Apache2.0][51].
  * Makefile、podman 支持、GitHub Actions、Prometheus 指标支持、TOML 风格的 config.ini、预配置了健康检查的 easy-route 等.
* [cl-webapp-seed](https://github.com/rajasegar/cl-webapp-seed)  - 一个简单的 Web 应用程序样板. 使用 Hunchentoot，cl-who，轻松部署到 Heroku.  [麻省理工学院][200].

Others
------

* [maiden](https://shirakumo.github.io/maiden)  - 支持 IRC 等的机器人和聊天系统框架.  [zlib][33].
* [css-lite](https://github.com/paddymul/css-lite)  - CSS 语法.  [外籍人士][14].
* [find-port](https://github.com/eudoxia0/find-port)  - 以编程方式查找开放端口.  [麻省理工学院][200].
* [Postmaster](https://github.com/eudoxia0/postmaster)  - 一个简单易用的 SMTP/IMAP 库.  [外籍人士][14].
* [cl-wget](https://github.com/cl-wget/cl-wget)  - 使检索大文件或镜像整个网站变得容易.  [AGPL-3.0][51].
* [trivial-download](https://github.com/eudoxia0/trivial-download)  - 下载文件.  [麻省理工学院][200].

### Email

* [trivial-imap](https://github.com/40ants/trivial-imap)  - 尝试简化使用 IMAP 服务器的一些常见情况，例如从服务器读取电子邮件. 邮局图书馆的薄包装（这是弗朗茨的 cl-imap 的一个分支）.  [BSD][15].
* [mailgun](https://github.com/40ants/mailgun)  - 通过 mailgun.com 发布 HTML 电子邮件的薄包装器.  [无牌][5].
* [cl-smtp](https://gitlab.common-lisp.net/cl-smtp/cl-smtp) - CL-SMTP 是一个简单的 lisp smtp 客户端.

### Static site generators

* [coleslaw](https://github.com/kingcons/coleslaw) 及其
  [coleslaw-cli](https://github.com/40ants/coleslaw-cli) - 灵活
  类似于 Frog、Jekyll 或 Hakyll 的 Lisp 博客软件.  [BSD][15].

### Third-party APIs

* [Aws-sign4](https://github.com/rotatef/aws-sign4) - 用于 Amazon Web Services 签名版本 4 的 Common Lisp 库.[GNU GPL3][2].
* [zs3](https://github.com/xach/zs3) - 一个使用亚马逊简单存储的库
服务 (S3) 和 CloudFront 服务.  [BSD][15].
* [cl-ses](https://github.com/CodyReichert/cl-ses/)  - AWS SES 库.  [外籍人士][14].
* [north](https://shinmera.github.io/north)  - South (Simple OaUTH) 库的继承者，在客户端和服务器端实现完整的 oAuth 1.0a 协议. 使用 North，您可以轻松成为 oAuth 提供者或消费者.  [zlib][33].
* [avatar-api](https://github.com/eudoxia0/avatar-api)  - 从 Google+、Gravatar 等获取头像.  [外籍人士][14].
* [chirp](https://github.com/Shinmera/chirp)  - Twitter 客户端库.  [zlib][33].
* [tooter](https://github.com/Shinmera/tooter)  - 为 Mastodon 实现完整的 v1 REST API 协议的客户端库.  [zlib][33].
* [cl-irc](https://www.common-lisp.net/project/cl-irc/)  - IRC 客户端库.  [外籍人士][14].
* [cl-mediawiki](https://github.com/AccelerationNet/cl-mediawiki)  - MediaWiki api 的包装器.  [麻省理工学院][200].
* [cl-openid](https://github.com/cl-openid/cl-openid)  - OpenID 的实现.  [LLGPL][8].
* [cl-pushover](https://github.com/TeMPOraL/cl-pushover)  - 通用 Lisp 绑定到 Pushover.  [麻省理工学院][200].
* [humbler](https://github.com/Shinmera/humbler)  - 一个 Tumblr API 接口.  [zlib][33].
* [multiposter](https://github.com/Shinmera/multiposter)  - 同时发布到多个服务.  [zlib][33].
* [stripe](https://git.mfiano.net/mfiano/stripe)  - Stripe 支付系统的客户.  [麻省理工学院][200].
* [lisp-pay](https://github.com/K1D77A/lisp-pay)  - 各种支付处理器的包装：Paypal、Stripe、Coinpayments 和 BTCPayServer.  [麻省理工学院][200].
* [lunamech-matrix-api](https://github.com/K1D77A/lunamech-matrix-api)  - 对客户端 -&gt; 服务器矩阵 API 的完整包装.  [麻省理工学院][200].


数值和科学
========================

* [numcl](https://github.com/numcl/numcl)  - Common Lisp 中的 Numpy 克隆.  [LGPL3][9].
* [GSLL](https://common-lisp.net/project/gsll/)  - 用于 Lisp 的 GNU 科学图书馆； 允许使用来自 Common Lisp 的 GSL.  [GNU LGPL2.1][11].
* [maxima](http://maxima.sourceforge.net/)  - 计算机代数系统. 在 Quicklisp 上不可用.  [GNU GPL3][2].
  * 还 [Maxima on Android](https://play.google.com/store/apps/details?id=jp.yhonda), 用 ECL 构建.
* [Xecto](https://github.com/pkhuong/Xecto)  - 用于常规阵列并行性的库.  [3 条款 BSD][15].
* [Petalisp](https://github.com/marcoheisig/Petalisp) - 尝试
  通过以下方式为并行计算机生成高性能代码
   JIT 编译数组定义. 它适用于更多
  比 NumPy 更基础的水平，通过提供更强大
  N 维数组，但只是一些用于处理的构建块
  他们.  [AGPL-3.0][agpl3].
* [cl-ana](https://github.com/ghollisjr/cl-ana)  - Common Lisp 数据分析库，强调模块化和概念清晰性. 它旨在成为分析小型和大型数据集的通用框架，包括分箱数据分析和可视化.  [GNU GPL3][2].
* [linear-programming](https://neil-lindquist.github.io/linear-programming/)  – 用于解决线性规划问题的库.  [麻省理工学院][200].
* [avm](https://github.com/takagi/avm)  - 具有多线程和 CUDA 支持的高效且富有表现力的阵列矢量数学库.  [麻省理工学院][200].
* [array-operations](https://github.com/bendudson/array-operations)  - 用于操作 Common Lisp 数组并使用它们执行数值计算的函数和宏的集合.  [麻省理工学院][200].
* [cl-geometry](https://github.com/Ramarren/cl-geometry/)  - Common Lisp 的二维计算几何系统.  [麻省理工学院][200].
* [Vellum](https://github.com/sirherrbatka/vellum)  - Common Lisp 的数据帧.  BSD_2 条款.
* [rtg-math](https://github.com/cbaggers/rtg-math/)  - 在 lisp 中制作实时图形最常用的数学例程选择（2、3 和 4 分量向量、3x3 和 4x4 矩阵、四元数、球坐标和极坐标）.  BSD_2 条款.
* [origin](https://github.com/mfiano/origin)  - 一个原生的 Lisp 图形数学库，强调性能和正确性. 包括：向量、矩阵（最多 4x4）、四元数、单/双浮点支持、破坏性/非破坏性操作、整形和交叉.  [麻省理工学院][200].

矩阵库
----------------

* [magicl](https://github.com/quil-lang/magicl)  - 基于 BLAS/LAPACK 和 Expokit 的 Common Lisp 中的矩阵代数程序，由 Rigetti Computing 提供.  [BSD_3 条款][15].
* [lisp-matrix](https://github.com/blindglobe/lisp-matrix)  - 矩阵包.  [自由BSD][39].
* [3d-matrices](https://shinmera.github.io/3d-matrices)  - 实现通用矩阵计算的库，重点是图形中常用的 2x2、3x3 和 4x4 矩阵. 它也提供了一些数值函数，但这些不是重点. 该库经过大量优化，因此它不是由漂亮的代码组成的.  [zlib][33].
* [clem](https://github.com/slyrus/clem)  - 一个矩阵库.  [BSD_2 条款][17].

Statistics
---------

* [lisp-stat](https://github.com/lisp-stat)  - 统计计算环境，概念上类似于 R，也适用于一线生产部署.  “它源于希望拥有一个快速原型分析和人工智能解决方案的环境，并以最小的摩擦直接转移到生产环境.”
  * https://lisp-stat.dev/
  * 运送卢克·蒂尔尼 [XLisp-Stat](https://homepage.stat.uiowa.edu/~luke/xls/xlsinfo/) （R 的前身）以及较新的库.
* [common-lisp-stat](https://github.com/blindglobe/common-lisp-stat/)  - 通用 Lisp 统计库.  [自由BSD][39].

Units
-----

* [physical-quantities](https://github.com/mrossini-ethz/physical-quantities)  - 为具有自动错误传播的计算提供具有可选单位和/或不确定性的数字类型的库.  GPL2

Utils
-----

* [cmu-infix](https://github.com/rigetti/cmu-infix)  - 在 Common Lisp 中编写中缀数学符号的库. 也可以看看 [polisher](https://github.com/mrcdr/polisher).


并行性和并发性
===========================

* ⭐ [BordeauxThreads](https://common-lisp.net/project/bordeaux-threads/)  - 可移植的共享状态并发.  [外籍人士][14].
* ⭐ [lparallel](https://github.com/lmj/lparallel)  - 用于并行编程的库.  [3 条款 BSD][15].
* [lfarm](https://github.com/lmj/lfarm)  - 跨机器分配工作（在 lparallel 和 usocket 之上）.  [BSD_3 条款][15]
* [calispel](https://github.com/hawkir/calispel) - [CSP](https://en.wikipedia.org/wiki/Communicating_sequential_processes) - 类似普通 lisp 的频道. 具有阻塞、可选缓冲通道和“CSP 选择”语句.  ISC 风格.
   - “它完整、灵活且易于使用.我会推荐 Calispel 而不是 Lparallel 和 ChanL.”  @Ambrevar. [discussion](https://github.com/CodyReichert/awesome-cl/issues/290)
* [chanl](https://github.com/zkat/chanl)  - 可移植的、基于通道的并发.  [Expat][14]，部分在 [3-clause BSD][15] 下.
* [cl-async](https://github.com/orthecreedence/cl-async)  - 用于通用、非阻塞编程的库.  [外籍人士][14].
* [Moira](https://github.com/TBRSS/moira)  - 监控和重启后台线程.  In-lisp 进程主管.  [麻省理工学院][200].
* [trivial-monitored-thread](https://gitlab.com/ediethelm/trivial-monitored-thread) -
  一个 Common Lisp 库，提供了一种产生线程的方法
  当他们中的任何一个坠毁并死亡时得到通知.  [麻省理工学院][200].
* [cl-gearman](https://github.com/taksatou/cl-gearman) - 一个图书馆 [Gearman](http://gearman.org/) 分布式工作系统.  [LLGPL][8].
* [swank-crew](https://github.com/brown/swank-crew)  - 使用 Swank Client 实现的分布式计算框架.  [BSD_3 条款][15].
* [cl-coroutine](https://github.com/takagi/cl-coroutine)  - 一个协程库. 它在其实现中使用 CL-CONT 延续库.  [麻省理工学院][200].
* [STMX](https://github.com/cosmos72/stmx)  - Common Lisp 的高性能事务内存.  [LLGPL][8].

也可以看看：

* [cl-etcd](https://github.com/atgreen/cl-etcd) - 将 etcd 作为异步劣等进程运行.  [etcd](https://etcd.io/) 是一个强一致的分布式键值存储.  [AGPL-3.0][agpl3].

演员模式
--------------

* [cl-gserver](https://github.com/mdbergmann/cl-gserver)  - cl-gserver 是一个“消息传递”库/框架，具有类似于 Erlang 或 Akka 的演员. 它支持创建应该反应式工作的系统，需要并行计算和基于事件的消息处理.  [阿帕奇2] [89].
* [erlangen](https://github.com/eugeneia/erlangen)  - Clozure Common Lisp 的分布式异步消息传递系统.  [GNU GPL3][2].
* [Actors](https://github.com/aarvid/Actors) LispWorks 软件包（[announce](https://www.reddit.com/r/Common_Lisp/comments/77vsft/david_mcclains_actors_package_for_lispworks/)) [麻省理工学院][200].
* [common-lisp-actors](https://github.com/naveensundarg/Common-Lisp-Actors)  - 一个简单易用的演员系统.  [BSD_2 条款][17].
* [memento-mori](https://github.com/zkat/memento-mori) - 一个用于编写健壮的、基于参与者的系统的库. 它从 Erlang/OTP 中汲取灵感，尤其是它对高可用性系统的崩溃优先方法以及 Akka.  [麻省理工学院][200].


事件处理
----------------

* [simple-tasks](https://github.com/Shinmera/simple-tasks)  - 一个非常简单的任务调度框架.  [zlib][33].
* [deeds](https://github.com/Shinmera/deeds)  - Deeds 是一个可扩展的事件传递系统. 它允许使用复杂的事件过滤系统将事件有效地传递给多个处理程序.  [zlib][33].
* [cl-flow](https://github.com/borodust/cl-flow/)  - 用于非阻塞并发 Common Lisp 的数据流计算树库.  [麻省理工学院][200].
* [event-glue](https://github.com/orthecreedence/event-glue)  - 简单的事件抽象. 没有依赖关系. 它可以在任何需要通用事件处理系统的地方使用.  [麻省理工学院][200].


作业处理
--------------


* [SBCL's timers](http://www.sbcl.org/manual/#Timers), system-wide event schedulers.
* [psychiq](https://github.com/fukamachi/psychiq)  - Common Lisp 应用程序的基于 redis 的后台作业处理. 受 Ruby 的 Sidekiq 启发并兼容其 Web UI.  [LLGPL][8].
* [cl-cron](https://github.com/ciel-lang/cl-cron)  - 一个提供类似 cron 的工具的简单工具.  [GPL3][2].
* [clerk](https://github.com/tsikov/clerk)  - 一个类似 cron 的调度器，带有健全的 DSL.  [麻省理工学院][200].


Regex
=====

* ⭐ [cl-ppcre](http://weitz.de/cl-ppcre/)  - 可移植的、Perl 兼容的正则表达式.  [自由BSD][39].
* [one-more-re-nightmare](https://github.com/no-defun-allowed/one-more-re-nightmare) - a fast-ish regular expression compiler in Common Lisp. [BSD_2Clause][17].


Scripting
=========

编写、运行脚本
------------------------

* [Roswell](https://github.com/roswell/roswell#scripting-with-roswell) -
  lisp 安装程序和脚本环境（帮助程序、启动程序、
  安装程序）等等.  [麻省理工学院][200].
* [cl-all](https://github.com/shinmera/cl-all)  - 在多个实现中运行 Lisp 片段的脚本. 这使您可以快速比较实现行为和差异.  [zlib][33].
* [clawk](https://github.com/sharplispers/clawk)  - 嵌入到 Common Lisp 中的 AWK 实现，用于搜索文件中的行并对其字段执行指定的操作.  BSD 风格.
* [ScriptL](https://github.com/rpav/ScriptL)  - Shell 脚本使 Lisp 类似！ 或者，对 shell 进行实时编码远程函数调用. 在 REPL 中编写一个命令，然后在 shell 中立即运行它.  [LLGPL][8].
  * 类似并且可能更简单： [lserver](https://notabug.org/quasus/lserver/)

命令行选项解析器
----------------------------

* [Clingon](https://github.com/dnaeon/clingon) - 丰富的命令行选项解析器系统.
  * 它可能拥有最丰富的功能集：子命令、生成 bash 补全、支持各种选项（整数、布尔值、计数器、枚举……）、可扩展……
* [Adopt](https://github.com/sjl/adopt/)  - 一个该死的 OPTion 解析库.  [麻省理工学院][200].
* [Unix-opts](https://github.com/libre-man/unix-opts)  - 带有简洁的选项声明的命令行选项解析器.  [麻省理工学院][200].


Readline、ncurses 和其他图形助手
--------------------------------------------

* [cl-readline](https://github.com/vindarel/cl-readline) - 一套
  在输入行时编辑行的功能，以维护列表
  以前输入的命令行，以调用和重新编辑它们
  执行类似 csh 的历史扩展.  Emacs 和 vi 编辑
  模式.  [GPL3][2].
* [Linedit](https://common-lisp.net/project/linedit) - 阅读线风格
  提供可定制的行编辑的库
  特征.  [麻省理工学院风格][210].
* [cl-charms](https://github.com/HiTECNOLOGYs/cl-charms) - 一个
   Common Lisp 中 `libcurses` 的接口. 它提供了一个原始的，
  通过 CFFI 与 libcurses 的低级接口，以及更高级别的接口
  口齿不清的界面.  [麻省理工学院][200].
* [replic](https://github.com/vindarel/replic/)  - 帮助将现有代码转换为 readline 应用程序，重点是定义命令参数的完成. 也作为一个准备使用的可执行文件，将用户的 lispy init 文件转换为 readline 命令.  [麻省理工学院][200].
* [cl-ansi-term](https://github.com/vindarel/cl-ansi-term) - 打印
  彩色文本、水平线、进度条、（未）有序列表
  和符合 ANSI 标准的终端上的表格.  [GPL3][2].
* [cl-progress-bar](https://github.com/sirherrbatka/cl-progress-bar/)  - 进度条，就像在 Quicklisp 中一样！  [麻省理工学院][200].

贝壳、贝壳接口
-------------------------

* [Lish](https://github.com/nibbula/lish)  - `lish` 可能有一天会成为一个 lisp shell.  [GPL3][2].
  * 支持路径和 Lisp 符号中的可执行文件的制表符补全，允许编写和混合 shell 命令和 Lisp 代码，具有微型 REPL 和交互式调试器等等.
* [shcl](https://github.com/bradleyjensen/shcl)  - Common Lisp 中类似 POSIX 的 shell.  [Apache2.0][89].
* [Shelly](https://github.com/fukamachi/shelly) - 执行 Common Lisp
  功能类似于 shell 命令，无需编写命令
  行参数解析器. 它也可以用作Make-like
  构建工具.  [自由BSD][39].
* [cmd](https://github.com/ruricolist/cmd)  - 用于运行外部程序的实用程序. 防止 shell 插值，在构建时考虑了多线程程序，Windows 支持.  [麻省理工学院][200].
   * `uiop:run-program`（同步）和 `uiop:launch-program`（异步）随 ASDF 一起提供，可用于所有现代实现. 见 [CL Cookbook: running external programs](https://lispcookbook.github.io/cl-cookbook/os.html#running-external-programs).
* [Clesh](https://github.com/Neronus/Clesh)  - 以类似于 perl 的反引号的方式扩展 Common Lisp 以嵌入 shell 代码.  [自由BSD][39].

系统管理
---------------------

* [Consfigurator](https://spwhitton.name/tech/code/consfigurator/)  - Lisp 声明式配置管理系统. 您可以使用它来将主机配置为 root、以非特权用户身份部署服务、构建和部署容器以及生成磁盘映像.  [GPL3][2].
* [Adams](https://github.com/cl-adams/adams)  - Common Lisp 中的 UNIX 系统管理. 与 Ansible、Chef 或 Puppet 不同.  [国际标准委员会][22].

其他脚本实用程序
-------------------------

* [WCL](https://github.com/wadehennessey/wcl) [停滞] - 允许数百个 Lisp
应用程序立即可用，同时允许
其中几个同时运行.  WCL 通过
提供 Common Lisp 作为 Unix 共享库，可以链接
 Lisp 和 C 代码可生成高效的应用程序. 例如，
可执行的 Lisp 版本的规范 `Hello World!`
程序在 32 位 x86 Linux 上只需要 20k 字节.  WCL 也
支持完整的开发环境，包括动态文件
加载和调试. 一个修改版的 GDB 用于调试 WCL
程序，为混合语言调试提供支持.


文本编辑器资源
=====================

这包含各种文本编辑器的插件和其他好东西.

* [Parinfer](https://shaunlebron.github.io/parinfer/)  - Parinfer 是一种编辑 lisp 代码的方法，有助于保持缩进和括号平衡. 它很容易上手，但它提供了高级功能 à la Paredit. 它可用于许多编辑器（Emacs、Vim、Neovim、Atom、Sublime Text、Visual Studio Code、LightTable、CodeMirror 等）.

## Emacs ##

* ⭐ [Slime](https://github.com/slime/slime)  - Emacs 的高级 Lisp 交互模式；  Emacs 内部的 Common Lisp 的成熟环境. 公共区域.
* [Sly](https://github.com/joaotavora/sly) - SLY 是 SLIME 的一个分支，并对其进行了多项改进.
* [Portacle](https://shinmera.github.io/portacle/) - 可移植的多平台 Common Lisp 环境：SBCL、Quicklisp、Emacs、Slime、Git.
* [cl-devel2](https://hub.docker.com/r/eshamster/cl-devel2/)  - 一个用于 Common Lisp 开发环境的 Docker 容器. 使用 Slime 运送 SBCL、CCL、Roswell 和 Emacs25.
* [Emacs4CL](https://github.com/susam/emacs4cl)  - 一个很小的 ​​Emacs 初始化文件，用于快速设置 vanilla Emacs 以进行 Common Lisp 编程. 附带对初始化文件中每一行代码的逐行解释.
* [slime-star](https://github.com/mmontone/slime-star) - 预先安装了扩展的 SLIME 配置，还有一些自定义实用程序和菜单：
  - Lisp 系统浏览器
  - [SLIME doc contrib](https://github.com/mmontone/slime-doc-contribs) - 增强默认帮助缓冲区.
  - [Quicklisp systems](https://github.com/mmontone/quicklisp-systems) - 从 Emacs 搜索、浏览和加载 Quicklisp 系统.
  - [Quicksearch](https://github.com/tkych/quicksearch)
  - [Slime breakpoints](https://github.com/mmontone/slime-breakpoints)
  - [Slite](https://github.com/tdrhq/slite/) - FiveAM 的测试运行器.

## Vim & Neovim ##

* [SLIMV](https://github.com/kovisoft/slimv)  - Vim 的高级 Lisp 交互模式；  Vim 内部的 Common Lisp 的成熟环境. 未指定许可证.
* [Vlime](https://github.com/vlime/vlime)  - VLIME：Vim 加 Lisp 大多是邪恶的.  Vim（和 Neovim）的 Common Lisp 开发环境.  [麻省理工学院][200].
* [quicklisp.nvim](https://gitlab.com/HiPhish/quicklisp.nvim) - Neovim 的 Quicklisp 前端.
* [Slimv_box](https://github.com/justin2004/slimv_box) - Docker 容器中的 slimv.


## Eclipse ##

* [Dandelion](https://github.com/Ragnaroek/dandelion) - Eclipse IDE 的 Common Lisp 插件.

## Lem ##

* [Lem](https://github.com/cxxxr/lem) - 一个即用型、类似 Emacs、基于 Slime 
  为开箱即用的 Common Lisp 开发以及其他编程语言量身定制的编辑器. 带有 ncurses 和 Electron 接口.  [麻省理工学院][200]. 另见： [opengl frontend](https://github.com/pupcraft/lem-opengl), [Lem in Docker](https://github.com/40ants/lem-docker), [lem-pareto](https://github.com/40ants/lem-pareto).

## Atom ##

* [SLIMA](https://github.com/neil-lindquist/slima) 允许您
  交互式开发 Common Lisp 代码，将 Atom 变成
  相当不错，并且积极开发的 Lisp IDE.  [麻省理工学院][200].

## Sublime Text ##

* [Sublime Text](http://www.sublimetext.com/3) （专有）有
  Common Lisp 支持其 SublimeREPL 和
  [Slyblime](https://github.com/s-clerc/slyblime) 包. 水灵灵
  是 SLY 的一个实现，它使用相同的后端 (SLYNK). 它
  提供高级功能，包括带有堆栈框架的调试器
  检查.

## VSCode ##

* [commonlisp-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.commonlisp-vscode)  - 支持语法高亮、自动完成、悬停文档、转到定义、编译和加载文件、REPL 的扩展. 这是 [On GitHub](https://github.com/ailisp/commonlisp-vscode/).
* [alive](https://github.com/nobody-famous/alive)  - VSCode 的通用 Lisp 扩展. 公共区域.
  * 见食谱： [using VSCode with Alive](https://lispcookbook.github.io/cl-cookbook/vscode-alive.html)
* [strict-paredit-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.strict-paredit) - 像 Emacs 一样的结构编辑和导航.

## Geany (experimental) ##

* [Geany-lisp](https://github.com/jasom/geany-lisp) 是一种实验性的 lisp 模式 [Geany](https://geany.org/) 编辑.

## Notebooks ##

* [common-lisp-jupyter](https://github.com/yitzchak/common-lisp-jupyter)  - 一个用于 Jupyter 的 Common Lisp 内核以及一个用于构建 Jupyter 内核的库，基于 Robert Dodier 的 Maxima-Jupyter，它基于 Frederic Peschanski 的 cl-jupyter.  [麻省理工学院][200].
  * [jupyterlab-debugger-restarts](https://github.com/yitzchak/jupyterlab-debugger-restarts) - JupyterLab 调试器的重启功能.
  * [Cytoscape widget](https://github.com/yitzchak/cytoscape-clj) - 用于 common-lisp-jupyter 的 Cytoscape.js 小部件.
  * [Kekule widget](https://github.com/yitzchak/kekule-clj) - 用于 common-lisp-jupyter 的 Kekule.js 小部件.
  * [molecule viewer](https://github.com/yitzchak/jupyterlab-molviewer) - 使用 ngl 的 JupyterLab 分子查看器.
  * [ngl widget](https://github.com/yitzchak/ngl-clj) - common-lisp-jupyter 的 ngl 小部件（蛋白质查看器）.
  * [sheet widget](https://github.com/yitzchak/sheet-clj) - common-lisp-jupyter 的数据网格小部件.
* [cl-jupyter](https://github.com/fredokun/cl-jupyter) - 用于 Jupyter 笔记本的 Common Lisp 内核 [custom licence](https://github.com/fredokun/cl-jupyter/blob/master/LICENSE).
* [Darkmatter](https://github.com/tamamu/darkmatter) - 一个
  笔记本式的 Common Lisp 环境.  [麻省理工学院][200].

## REPLs ##

* [cl-repl](https://github.com/koji-kojiro/cl-repl)  - 一个类似 ipython 的 REPL. 带有补全、shell 命令、魔术命令、调试器等 [MIT][200]. 和 [colorthemes](https://github.com/koji-kojiro/lem-pygments-colorthemes).
* [sbcli](https://github.com/hellerve/sbcli)  - 用于 SBCL 的 readline REPL. 具有补全、快速命令、可选的语法高亮（使用 pygments），并且没有交互式调试器.  [GPL3][2].

## Online editors ##

* [Judge0 IDE](https://ide.judge0.com/?lUpj) 是一个支持 Common Lisp (SBCL) 的在线编辑器.  [麻省理工学院][200].

## Apps ##

* [CodePlayground](https://codeplayground.app/) - 通过 CCL 支持 Lisp 的 iPhone 和 iPad 应用程序.

文本解析器
============

* ⭐ [esrap](https://github.com/scymtym/esrap)  - Packrat 解析器.  [外籍人士][14].
* [cl-yacc](https://github.com/jech/cl-yacc)  - LALR(1) 解析器生成器.  [麻省理工学院][200].
* [cl-shlex](https://github.com/ruricolist/cl-shlex/)  - 用于类似 shell 的语法的简单词法分析器.  [麻省理工学院][200].
* [smug](https://github.com/drewc/smug)  - Common Lisp 的解析器组合器.  SMUG 使创建快速可扩展的递归下降解析器变得简单，而没有时髦的语法或难以理解的宏观.  [麻省理工学院][200].
* [parseq](https://github.com/mrossini-ethz/parseq)  - 用于使用解析表达式语法解析字符串和列表等序列的库. 受到Esrap的启发.  GPL2.
* [texp](https://github.com/eugeneia/texp/)  - 用于生成 TeX 的 DSL.  [AGPL-3.0][agpl3].

文本处理
===============

* [montezuma](https://github.com/sharplispers/montezuma/)  - 全文索引和搜索 Common Lisp.  [外籍人士][14].
* [mk-string-metrics](https://github.com/cbaggers/mk-string-metrics) -
  在 Common Lisp 中高效计算各种字符串度量
  （达默劳-列文施泰因、汉明、雅罗、雅罗-温克勒、列文施泰因、
   ETC）.  [麻省理工学院][200].
* [wiki-lang-detect](https://github.com/vseloved/wiki-lang-detect) -
使用维基百科数据的文本语言识别. 未指定许可证.
* [cl-phonetic](https://github.com/bgutter/cl-phonetic)  - Common Lisp 的语音模式匹配库（旨在替换 Python 的 Sylvia 库）.  [麻省理工学院][200].
* [cl-string-generator](https://github.com/pokepay/cl-string-generator)  - 从正则表达式生成字符串.  [麻省理工学院][200].

也可以看看：

* [Resolve](https://github.com/GrammaTech/resolve)  - 用于基于 AST 的差异计算、显示和自动解析的软件. 用 C++ 和 CL 编写，你会发现 Lisp 实用程序.

Tools
=====

这些是使 Common Lisp 中的开发更容易的应用程序或代码片段，而不是 Common Lisp 库本身.

* [quicksearch](https://github.com/tkych/quicksearch)  - 从 REPL 中查找在线图书馆.  [外籍人士][14].
* [lake](https://github.com/takagi/lake)  - 一个类似 GNU make 的构建实用程序.  [麻省理工学院][200].


单元测试
============

* ⭐ [FiveAM](https://github.com/sionescu/fiveam)  - 简单的回归测试框架.  [自由BSD][39].
* [CLUnit2](https://notabug.org/cage/clunit2/)  - 一个单元测试库.  [麻省理工学院][200].
* [Parachute](https://github.com/Shinmera/parachute)  - 一个可扩展和交叉兼容的测试框架. 具有测试依赖项、条件、固定装置和重新启动.  [zlib][33].
* [Mockingbird](https://github.com/Chream/mockingbird) - 一个小
   Common Lisp 的存根和模拟库. 也可以检查是否
  一个存根函数被调用了多少次以及调用了多少次
  论据.  [麻省理工学院][200].
* [cl-mock](https://github.com/Ferada/cl-mock)  - 另一个模拟库. 它比 Mockingbird 有更多的功能，比如模拟调用上的模式匹配等.
* [Check-it](https://github.com/DalekBaldwin/check-it)  - QuickCheck 风格的基于随机属性的测试.  [LLGPL][8].
* [cl-coveralls](https://github.com/fukamachi/cl-coveralls) - 帮手
  库将测试覆盖率发布到工作服. 看 [SBCL's code coverage tool](http://www.sbcl.org/manual/index.html#sb_002dcover) .  [自由BSD][39].

编辑器实用程序：

* [Slite](https://github.com/tdrhq/slite/)  - FiveAM 测试的基于 SLIme 的测试运行器.  [Apache2.0][89]
   - Slite 以交互方式运行您的 Common Lisp 测试（在撰写本文时仅支持 FiveAM）. 它允许您查看测试失败的摘要、跳转到测试定义、使用调试器重新运行测试，所有这些都来自 Emacs.


Utilities
=========

Caching
-------

* [clache](https://github.com/html/clache)  - 通用缓存设施. 在磁盘或内存中缓存任何 Lisp 对象. 缓存可以是持久的或具有过期时间.  [LLGPL][8].


压缩/解压
---------------------------

* [chipz](https://github.com/froydnj/chipz)  - 一个解压库.  [3 条款 BSD][15].
* [Salza2](http://www.xach.com/lisp/salza2/)  - 用于创建压缩数据的库.  [自由BSD][39].
* [zippy](https://github.com/Shinmera/zippy)  - 基于 3bz 的 ZIP 存档格式库.  [zlib][33].


Configuration
-------------

* [py-configparser](https://common-lisp.net/project/py-configparser/)  - 读取和写入 Python 的类似 ConfigParser 的配置文件.  [麻省理工学院][200].
* [envy](https://github.com/fukamachi/envy)  - 配置切换器.  [自由BSD][39].
* [chameleon](https://github.com/sheepduke/chameleon/)  - 附带配置文件支持的配置管理库.  [麻省理工学院][200].

CSV
---

* ⭐ [cl-csv](https://github.com/AccelerationNet/cl-csv)  - 用于解析 CSV 文件的库.  [3 条款 BSD][15].
* [cl-decimals](https://github.com/tlikonen/cl-decimals)  - 十进制数解析器和格式化程序. 公共区域.
* [auto-text](https://github.com/defunkydrummer/auto-text)  - 文本文件的自动（编码、行尾、列宽、csv 分隔符等）检测.  [麻省理工学院][200]. 也可以看看 [inquisitor](https://github.com/t-sin/inquisitor) 用于检测亚洲和远东语言.


日期和时间
-------------

* ⭐ [local-time](https://common-lisp.net/project/local-time/)  - 用于以半标准方式处理日期和时间信息的开发库.  [3 条款 BSD][15].
* [cl-date-time-parser](https://github.com/tkych/cl-date-time-parser) - Parse date-time-string, liberally. Hides the difference between date-time formats, and enables to manage date and time as the one date-time format. [MIT][200].
* [chronicity](https://github.com/chaitanyagupta/chronicity)  - 自然语言日期和时间解析，解析字符串，如“从现在起 3 天”.  [BSD_3 条款][15].
* [local-time-duration](https://github.com/enaeher/local-time-duration) -
建立在本地时间之上的持续时间处理库.  [麻省理工学院][200].
  * 见这个分叉： [humanize-duration](https://github.com/40ants/humanize-duration) ，仅输出持续时间对象的重要部分. 具有本地化支持.
* [iso-8601-date](https://gitlab.com/DataLinkDroid/iso-8601-date)  - Common Lisp 中的其他日期例程，基于 ISO 8601 字符串表示.  [LLGPL][8].
* [calendar-date](https://github.com/takagi/calendar-date)  - 一个公历日期库.  [麻省理工学院][200].
* [periods](https://github.com/jwiegley/periods)  - 在更高级别操作日期/时间对象. 具有系列兼容的数据结构.  [BSD_3 条款][15].

另见本书 [Calendrical calculations](https://www.cambridge.org/us/academic/subjects/computer-science/computing-general-interest/calendrical-calculations-ultimate-edition-4th-edition?format=HB#resources) , 爱德华 M. Reingold，Nachum Dershowitz，剑桥出版社. 它提供 Lisp 源代码.

数据验证
---------------

* [ratify](https://github.com/Shinmera/ratify)  - 用于批准、验证和解析输入的实用程序集合.  [zlib][33].
* [clavier](https://github.com/mmontone/clavier)  - Common Lisp 的通用验证库.  [麻省理工学院][200].
* [json-schema](https://github.com/fisxoj/json-schema) - 用于根据草案 4、6、7 和 2019-09 的模式验证数据的库 [JSON Schema](https://json-schema.org/) 标准.  [LLGPL][8].
* [sanity-clause](https://github.com/fisxoj/sanity-clause)  - Common Lisp 的数据序列化/合同库. 模式可以是属性列表或基于类，允许在“make-instance”期间检查插槽的类型.  [LLGPL][8].

开发人员实用程序
-------------------

* [repl-utilities](https://github.com/m-n/repl-utilities) - 舒适
REPL 的常见任务（打印文档、打印外部符号、
加载包时调用钩子，...）.  [BSD_2 条款][17].
* [flight-recorder](https://github.com/vseloved/flight-recorder) - 强大的 REPL 历史工具.
* [tracer](https://github.com/TeMPOraL/tracer)  - Common Lisp 的跟踪分析器，输出适合在 Chrome/Chromium 的跟踪查看器中显示.  [麻省理工学院][200].
* [cl-flamegraph](https://github.com/40ants/cl-flamegraph)  - SBCL 统计分析器的包装器，用于为 Common Lisp 程序生成 FlameGraph 图表.  [BSD][15].
* [cl-debug](https://github.com/LowH/cl-debug)  - 一个跨包调试工具. 提供统一的方式来启用或禁用调试特定的代码. 可以相对于由符号或关键字表示的程序功能启用或禁用调试代码.  ISC 许可证.
* [supertrace](https://github.com/fukamachi/supertrace)  - 用于调试/分析的高级 Common Lisp `trace` 功能. 一次跟踪多个函数，使用 before 和 after 钩子.  [BSD_2 条款][17].
* [printv](https://github.com/danlentz/printv)  - 包含电池的跟踪和调试记录宏.  [阿帕奇2] [89].
* [journal](https://github.com/melisgl/journal)  - 用于记录、跟踪、记录和重放测试和持久性的库. 麻省理工学院.

并且：

* [GTFL](http://www.martin-loetzsch.de/gtfl/)  - Lisp 的图形终端，适用于想要调试或可视化自己的算法的 Lisp 程序员. 浏览器中的图形跟踪.  BSD 风格.
* [trivial-with-current-source-from](https://github.com/scymtym/trivial-with-current-source-form/)  - 帮助宏编写者为宏用户产生更好的错误.  [GPL3][2].
* [trivial-benchmark](https://github.com/Shinmera/trivial-benchmark)  - 小型基准测试库.  [zlib][33].
* [glyphs](https://github.com/ahungry/glyphs/)  - 一个用于减少 Common Lisp 在某些地方的冗长性的库.  [GNU GPL3][2].
* [Lisp REPL core dumper](https://gitlab.com/ambrevar/lisp-repl-core-dumper/) -
一个便携式包装器，可按需生成 Lisp 核心，以快速启动 REPL.
它可以预加载提供的系统，以帮助构建一个专门的集合
Lisp 核心.


文档构建器
----------------------

* [Staple](https://github.com/Shinmera/staple)  - 使用 HTML 模板生成文档页面的工具. 使用现有的 README，将文档字符串、交叉引用和链接添加到 CLHS.  [zlib][33].
* [mgl-pax](https://github.com/melisgl/mgl-pax) - 探索性
编程环境和文档生成器. 一个可能
完成与文学编程类似的效果，但
文档是从代码生成的，反之亦然. 代码是第一位的，
代码必须看起来很漂亮，文档就是代码.  [麻省理工学院][200].
  - 看到这个 [40ants fork](https://github.com/40ants/doc) 用于：更轻的核心系统、JavaScript 搜索索引、多种格式输出、HTML 主题、用于 Changelog 的 RSS 和 Atom 提要等.
* [Declt](https://github.com/didierverna/declt)  - Common Lisp 库的参考手册生成器. 构建可以进一步处理成各种格式的 texinfo 文档，例如 HTML 或 PDF.  BSD.
* [Codex](https://github.com/CommonDoc/codex) - 一个美丽
   Common Lisp 的文档系统.  [麻省理工学院][200].
* [QBook](https://github.com/mmontone/qbook)  - 生成 Common Lisp 源文件的 HTML（或 LaTeX）格式的代码列表.  [BSD_3 条款][15].
   - 所有以 4 `;` (&quot;;;;;&quot;) 开头的注释都被解释为文档. 使用标题和指令增强文档.
   - QBook 充当“一个轻量级的文学编程系统，其中 Lisp 代码不是内联呈现，而是在单独的部分中呈现，这使得文档更易于浏览.”  @mmontone
* [sphinxcontrib-cldomain](https://github.com/russell/sphinxcontrib-cldomain) -
  扩展 Sphinx 以覆盖 Common Lisp. 构建文档
  与 sphinx 一样的易用性将成为 Python 项目.  [GPL3][2]
* [cl-bibtex](https://github.com/mkoeppe/cl-bibtex)  - 在 Common Lisp 中对 BibTeX 程序的兼容重新实现，带有 BST-to-CL 编译器.  [GNU LGPL2.1][11].

也可以看看：

* [docbrowser](https://github.com/lokedhs/docbrowser) - 为加载的系统动态生成文档的服务器.
   - 它的主页显示了 Lisp 映像中所有已加载系统的列表. 单击一个系统，您将获得一个包含三个窗格的页面：函数、类和变量. 单击一个函数以在上下文中查看其源代码以及行号. 单击类以查看它们的插槽和专业化功能.
* [cl-livedocs](https://github.com/mmontone/cl-livedocs) - 类似和更新，基于 Webinfo，默认启用全文搜索.

包含更多文档生成器的概述博客文章：https://lisp-journey.gitlab.io/blog/overview-of-documentation-generators/

你可能还喜欢： [literate programming systems](#literate-programming).


文件和目录
---------------------

* ⭐ [uiop](https://common-lisp.net/project/asdf/uiop.html) 及其 `pathname` 包
  （替换 [cl-fad](http://weitz.de/cl-fad/) ）.  uiop 是 ASDF3 的一部分
  并因此在许多实现中提供.  [麻省理工学院][200].
* [osicat](https://common-lisp.net/project/osicat/) - 类 POSIX 系统上的轻量级操作系统接口（目录迭代和删除、环境变量、文件权限等）[Expat][14].
* [pathname-utils](https://github.com/Shinmera/pathname-utils)  - 帮助进行路径名操作的实用程序集合.  [zlib][33].
* [ppath](https://github.com/fourier/ppath) - 普通 Lisp 
 Python 的 os.path 模块的实现.  [BSD][15].
* [archive](https://github.com/froydnj/archive)  - 用于读取和创建归档（tar、cpio）文件的库.  [BSD_3 条款][15].  `tar` 程序的纯 Common Lisp 替代品.
  * see its recent fork [cl-tar](https://common-lisp.net/project/cl-tar/) (2021). [Announce](https://www.timmons.dev/posts/new-project-cl-tar.html).
* [mmap](https://github.com/Shinmera/mmap)  - 便携式 mmap 文件内存映射实用程序库.  [zlib][33].
* [fof](https://gitlab.com/ambrevar/fof)  - 文件对象查找器 Common Lisp 库. 启用快速文件搜索、检查和操作.  [GPL3][2].

文件监视库：

* [file-notify](https://github.com/shinmera/file-notify)  - 用于文件更改检测的跨平台库.  [zlib][33].

Git
---

* [cl-git](https://github.com/russell/cl-git)  - libgit2 库的 CFFI 接口.  [LGPL3][9].
* [legit](https://shinmera.github.io/legit/)  - Git 二进制文件的接口.  [zlib][33].
* [git-api](https://github.com/fourier/git-api)  - 用于访问 git 存储库的 Common Lisp 库. 它不需要安装 git 或 libgit.  [BSD][15].

i18n
----

* [cl-i18n](https://notabug.org/cage/cl-i18n)  - i18n 库. 从 GNU gettext 文本或二进制文件或其本机格式加载翻译. 复数形式的本地化助手.  [LLGPL][8].
* [gettext](https://github.com/rotatef/gettext)  - 将 gettext 运行时移植到 Common Lisp.  [GPL3][2].
* [translate](https://github.com/dkochmanski/translate)  - 无缝的语言本地化.  LLGPL.
* [enchant](https://github.com/tlikonen/cl-enchant)  - Enchant 拼写检查库的绑定. 公共区域.
* [oxenfurt](https://github.com/Shinmera/oxenfurt)  - 牛津词典 API 的客户端库.  [zlib][33].
* [language-codes](https://shinmera.github.io/language-codes)  - ISO 语言代码的数据库库.  [zlib][33]
* [system-locale](https://shinmera.github.io/system-locale)  - 检索用户首选语言的库，以便您的应用程序可以选择合理的默认值.  [zlib][33].
* [multilang-documentation](https://shinmera.github.io/multilang-documentation)  - 允许为真正的国际文档库编写多种语言的文档字符串.  [zlib][33].

Linting，代码格式化
------------------------

* [sblint](https://github.com/fukamachi/sblint) - 使用 SBCL 的 Common Lisp 源代码的 linter，适用于 Reviewdog ([slides](http://www.slideshare.net/fukamachi/sblint) ）.  [BSD_2 条款][17].
* [trivial-formatter](https://github.com/hyotang666/trivial-formatter)  - Common Lisp 的代码格式化程序.  [麻省理工学院][200].

并且： [lisp-format](https://github.com/eschulte/lisp-format) 和 [cl-indentify](https://github.com/yitzchak/cl-indentify).

文学编程
--------------------

* [literate-lisp](https://github.com/jingtaozf/literate-lisp)  - 从 Emacs 的 Org 文件加载 Common Lisp 代码块.  [麻省理工学院][200].
* [erudite](https://github.com/mmontone/erudite)  - 考虑到交互式开发而构建的文学编程系统.  [麻省理工学院][200].


Logging
-------

* ⭐ [log4cl](https://github.com/sharplispers/log4cl/)  - 以 Log4J 为模型的日志记录框架.  [Apache2.0][89]. 与 Slime 的高级集成.
  * [log4cl-json](https://github.com/40ants/log4cl-json)  - JSON appender 扩展.  [BSD][15].
* [verbose](https://shinmera.github.io/verbose)  - 一个快速且高度可配置的日志框架.  [zlib][33].
* [a-cl-logger](https://github.com/AccelerationNet/a-cl-logger)  - 日志库提供上下文敏感的日志，不仅仅是字符串到本地文件或输出流. 具有 logstash 支持、json 支持、记录器层次结构、上下文相关日志记录、打印为可检查演示文稿的对象，...

给第三方：

* [cl-fluent-logger](https://github.com/fukamachi/cl-fluent-logger) - 一个 Common Lisp 结构化记录器，用于 [Fluentd](https://www.fluentd.org/).

也可以看看： [extensive comparison of logging libraries](https://sabracrolleton.github.io/logging-comparison).


Markdown
--------

* [3bmd](https://github.com/3b/3bmd)  - 降价 -&gt; html 转换器.  [麻省理工学院][200].

PDF
---

* [cl-typesetting](https://github.com/mbattyani/cl-typesetting) 和 [cl-pdf](https://github.com/mbattyani/cl-pdf)  - 用于生成 PDF 文件的跨平台 Common Lisp 库.  [自由BSD][39].
* [cl-pslib](https://notabug.org/cage/cl-pslib) - 一个（薄）包装 [pslib](http://pslib.sourceforge.net/) 用于生成 PostScript 文件的库. 还 [cl-pslib-barcode](https://notabug.org/cage/cl-pslib-barcode) .  [LLGPL][8].

Plotting
--------

* [vgplot](https://github.com/volkers/vgplot) - 一个接口
  gnuplot 绘图实用程序，旨在类似于一些
   octave 或 matlab 的绘图命令.  [GPL3][2].
* [eazy-gnuplot](https://github.com/guicho271828/eazy-gnuplot) - 一个
   lispy，无结构的 Gnuplot 库. 以其
  [cookbook](http://guicho271828.github.io/eazy-gnuplot/) .  [LLGPL][8]
* [kai](https://github.com/komi1230/kai)  - Common Lisp 的高级绘图仪库. 一个包装器 [Plotly](https://plotly.com/javascript/)  JS 库.  [麻省理工学院][200].
* [ADW-Charting](https://common-lisp.net/project/adw-charting/)  - 一个完全用 Common Lisp 编写的简单图表绘制库. 还包括 Google 图表服务的后端. 类似 BSD.
* [cl-spark](https://github.com/tkych/cl-spark)  - 控制台迷你图字符串：`(spark &#39;(1 1 2 3 5 8))` =&gt; &quot; ▂▃▅▇&quot;.  [麻省理工学院][200].

另请参阅 IUP 和 ltk-plotchart 的图表工具（GUI 部分）.

项目骨架
-----------------

* [cl-project](https://github.com/fukamachi/cl-project)  - 一般的现代项目骨架.  [LLGPL][8].
* [cl-project-with-docs](https://github.com/40ants/cl-project-with-docs)  - 使用 Sphinx 和 reStructured 文本来呈现美观且可读的 HTML 文档.  [BSD][15].
* [cl-cookieproject](https://github.com/vindarel/cl-cookieproject)  - 生成一个现成的 Common Lisp 项目. 不在 Quicklisp 中.  [BSD_3 条款][15].
  * 测试定义、从源代码运行的入口点、构建二进制文件、Roswell 集成……

Security
--------

* [cl-isolated](https://github.com/kanru/cl-isolated) - Common Lisp 代码评估 [AGPL-3.0][agpl3] 的受限环境.

XML
---

* [CXML](https://common-lisp.net/project/cxml/)  - XML 解析器和序列化器，带有一系列扩展库.  [LLGPL][8].
  - 有一个增量解析器，允许解析大文件.
  - 见 [FXML](https://github.com/ruricolist/FXML)  fork，带有修复和新功能. 如果您正在解析可能格式错误或恶意的 XML，或者如果您需要将 Klacks 与命名空间一起使用，则应该使用它.
 * [Plump][71] - 一个宽松的 XML 解析器.  [zlib][33].
* [xpath](https://github.com/sharplispers/xpath) ([homepage](https://common-lisp.net/project/plexippus-xpath/atdoc/index.html)  - XML 路径语言 (XPath) 1.0 版的实现.  [BSD_2 条款][17].
* [s-xml](http://cliki.net/S-XML)  - 一个基本的解析器.  [LLGPL][8].
* [xmls](https://github.com/rpgoldman/xmls)  - 一个小型、简单、非验证的 XML 解析器.  [3 条款 BSD][15].
* [cl-feedparser](https://github.com/TBRSS/cl-feedparser)  - 一个 Common Lisp (RSS, Atom) 提要解析器.  [LLGPL][8]
* [Buildnode](https://github.com/AccelerationNet/buildnode)  - 一个通用的 lisp 库，用于简化与 CXML-dom 的交互，例如构建 Excel 电子表格.  [BSD][15].


Other
-----

这包含不属于另一个类别的任何内容.

* [babel](https://github.com/cl-babel/babel)  - 一个字符集编码/解码库.  [外籍人士][14].
* [corona](https://github.com/eudoxia0/corona) - 从 Common Lisp http://eudoxia.me/corona [MIT][200] 创建和管理虚拟机.
* [fast-io](https://github.com/rpav/fast-io)  - 快速八位字节向量/流 I/O.  [3 条款 BSD][15].
* [iolib](https://github.com/sionescu/iolib)  - I/O 库.  [外籍人士][14].
* [named-readtables](https://github.com/melisgl/named-readtables)  - 提供一个可读的命名空间，类似于包命名空间.  [3 条款 BSD][15].
* [simple-currency](https://github.com/a0-prw/simple-currency)  - 使用欧洲央行发布的每日信息的货币兑换库.  [自由BSD][39].
* [trivial-garbage](https://github.com/trivial-garbage/trivial-garbage)  - 可移植的终结器、弱哈希表和弱指针 API. 公共区域.
* [trivial-utf8](https://common-lisp.net/project/trivial-utf-8/)  - 用于进行基于 UTF-8 的 I/O 的小型库.  BSD.


Contributing
============
随时欢迎您的贡献！ 请提交拉取请求或创建
将新框架、库或软件添加到列表中的问题.

我们（试图）遵守的规则如下：

- 默认情况下，将库添加到其部分的末尾.
- 绝对的事实库，如 BordeauxThreads 或 Quicklisp，
  应该用⭐表示（Unicode代码U+2B50）.
- 两个范围非常相似的库应该并排，或者在一个
  属于自己的部分.
- 根据您的经验和状态进行一些策展
  图书馆的文档. 我们*不*旨在列出所有现有
  CL 库（参见 Cliki）也没有列出每个
  “流行”库（参见 Quicklisp 统计信息）.
- 因此，我们最喜欢的库标有 (`1F44D`
   Unicode 字符）. 另见标志的解释
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
