<div class="github-widget" data-repo="CodyReichert/awesome-cl"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">
  <a href="https://awesome-cl.com" target="_blank">
    <img src="https://i.imgur.com/jLVXhpc.png">
  </a>
</div>

## Awesome Common Lisp [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Assertible status](https://assertible.com/apis/102e334d-f9a8-4565-9353-7572de775cae/status?api_token=8b55a286830323effb)](https://assertible.com/docs/guide/deployments)

_awesome_ Common Lisp 库的精选列表.

对于很棒的*软件*，请参阅 [lisp-lang.org's success stories](http://lisp-lang.org/success/) 和 [awesome-cl-software](https://github.com/azzamsa/awesome-cl-software) 列表.

此处列出的所有库均可从 [Quicklisp][16] 获得，除非
另有说明. 标有 :star: 的那些是如此普遍和
他们成为社区标准的坚实基础. 你不会错
他们.  Quicklisp、BordeauxThreads 和
这样的. 用 a 表示的库是我们喜欢和想要的库
在 Awesome-cl 列表中进行推广. 他们证明是可靠的，他们可以解决
一个比社区标准更好的问题，但它们并不像
普遍存在，或不被认为是稳定的. 例如，我们更喜欢
Cl-Who 上的喷丝板.

添加新东西！ 见 [contributing](#contributing) 添加一些东西的部分
list.

这是在 GNU 自由文档许可证下发布的 - 它的文本
在 LICENSE 文件中提供. 此存储库也镜像在
[NotABug](https://notabug.org/CodyReichert/awesome-cl) - **完全免费**（如自由）
 Github 的替代品. 优先考虑[自由软件][13]和
对物质资源不作恶的卖家.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->


<!-- markdown-toc end -->


Audio
=====

* [Open Music](https://github.com/openmusic-project/OM6)  - 一个可视化编程、计算机辅助的合成环境.  [GPL3][2].
* [OM7](https://github.com/openmusic-project/om7)  - OpenMusic 可视化编程和计算机辅助合成环境的新实现，包括对图形界面、计算模式和与外部软件库的连接的许多改进.  [GPL3][2].
* [Incudine](http://incudine.sourceforge.net/)  - Common Lisp 的音乐/DSP 编程环境. 从头开始设计软件合成器或声音插件很有用. 它也是一个作曲工具，允许产生在样本级别可控的高质量声音，动态定义和重新定义数字信号处理器和音乐结构.
* [cl-collider](https://github.com/byulparan/cl-collider) - 一种
[SuperCollider](http://supercollider.github.io/)  CommonLisp 的客户端. 用一个 [tutorial](https://github.com/defaultxr/cl-collider-tutorial) 和 [live coding demos](https://www.youtube.com/watch?v=xzTH_ZqaFKI) . 公共区域.
* [csound](https://github.com/csound/csound)  - 声音和音乐计算系统. 包括用于 Common Lisp 的 CFFI 和 FFI 接口.
* [CLM](https://ccrma.stanford.edu/software/clm/)  - Common Lisp Music 是 Music V 系列中的音乐合成和信号处理包. 它提供了与 Stk、Csound、SuperCollider、PD、CMix、cmusic 和 Arctic 大致相同的功能——一组创建和操作声音的函数，主要针对作曲家（无论如何在 CLM 的情况下）.
* [cl-patterns](https://github.com/defaultxr/cl-patterns)  - 一个通过 Lisp 代码创作音乐的系统，深受 SuperCollider 模式系统的启发，旨在实现其中的大部分内容，但以更健壮、富有表现力、一致、反思和流畅的方式. 通过 SuperCollider 输出音频，初步支持 Incudine，通过 ALSA 输出 MIDI.
* [cl-openal](https://github.com/zkat/cl-openal)  - OpenAL 音频库的绑定. 公共区域.
* [Common Music](https://github.com/ormf/cm) - 存储库
古代版Common Music（2.12.0版），大概是最后一个
在 Common Lisp 上运行的版本可以追溯到 2007-09 年左右，之前
Common Music 的工作转移到（基于方案的）cm3.
* [Slippery Chicken](https://github.com/mdedwards/slippery-chicken/)  - 通过 Lilypond 输出 Midi、Common Music Notation、pdf-score 和通过 Common Lisp Music 输出声音的算法作曲库.  [GPL3][2].
* [Common Music Notation](https://ccrma.stanford.edu/software/cmn/)  - 通用乐谱 (CMN) 提供了一系列功能来分层描述乐谱. 公共区域.
* [cm-incudine](https://github.com/ormf/cm-incudine)  - 使用实时功能扩展了 Common Music 2.  GPL2.
* [Mégra](https://github.com/the-drunk-coder/megra)  - 一种使用可变阶马尔可夫链和其他一些随机诡计来制作音乐的迷你语言.  [GPL3][2].
* [Music](https://github.com/MegaLoler/Music) - Lisp 中的音乐表达框架，侧重于音乐理论（从头开始构建，与 Common Music 无关）.
* [rq](https://github.com/openmusic-project/RQ) - OpenMusic 中的节奏转录库（版本 6.10 及更高版本）. [demo video](https://www.youtube.com/watch?v=XVEllB0TtVs) .  [GPL3][2].
* [scheduler](https://github.com/byulparan/scheduler)  - Common Lisp 的基于时间的音乐事件调度器.  [Apache2.0][89].
* [mixalot](https://github.com/ahefner/mixalot) - Loosely-coupled collection of audio libraries for mp3, ogg vorbis, flac. Used for the [Shuffletron music player](https://github.com/ahefner/shuffletron).
* [osc](https://github.com/zzkt/osc)  - 开放声音协议的实现.  [LGPL2.1][11].
* [Harmony](https://shirakumo.github.io/harmony)  - 实时声音处理和播放系统.  [艺术许可 2.0][51].
* [mixalot](https://github.com/ahefner/mixalot)  - 松散耦合的音频库集合.  [麻省理工学院][200].


构建系统
=============

* ：星星： [ASDF](https://common-lisp.net/project/asdf/)  - 另一个系统定义工具；  Common Lisp 的构建系统.  [外籍人士][14].  Quicklisp（见 [library manager](#library-manager)) 在引擎盖下使用 ASDF.
  * [known ASDF extensions](https://common-lisp.net/project/asdf/#extensions)，例如`asdf-system-connections`，它允许您指定在加载其他两个系统时自动加载的系统，以连接它们.
* [asdf-linguist](https://github.com/eudoxia0/asdf-linguist)  - ASDF 的扩展.  [外籍人士][14].
* [asdf-viz](https://github.com/guicho271828/asdf-viz)  - 一种可视化 ASDF 系统库依赖关系、函数调用图和类继承的工具.  [LLGPL] [8].

编译器、代码生成器
==========================

APL
---

* [April](https://github.com/phantomics/april)  - 编译为 Common Lisp 的 APL 编程语言（其子集）. 用一行 APL 替换数百行数字运算代码.  [Apache2][89].


C、C++
------

* [cmacro](https://github.com/eudoxia0/cmacro) - C 语言的 Lisp 宏.[MIT][200].
* [C-mera](https://github.com/kiselgra/c-mera)  - 一个源到源编译器，它利用 Lisp 的宏系统进行类 C 语言的元编程.  [GPL3][2].
* [lispc](https://github.com/eratosthenesia/lispc) - 强大的 C 语言“lispsy”宏语言.[MIT][200].
* [with-c-syntax](https://github.com/y2q-actionman/with-c-syntax)  - 一个将 C 语言语法引入 Common Lisp 的有趣包.  （是的，我认为这个包不是用于实际编码的.） WTFPL 许可证.
* [ecrepl](https://gitlab.common-lisp.net/ecl/ecrepl)  - C 语言的交互式 REPL.  [BSD_2 条款][17].
* [Software-Evolution-Library](https://github.com/GrammaTech/sel)  - SEL 支持软件的程序化修改和评估（使用 Clang、编译的汇编程序和链接的 ELF 二进制文件的 C/C++ 支持）.  [GPL3][2].

Crypto
======

* ：星星： [Ironclad](https://github.com/sharplispers/ironclad)  - Common Lisp 的加密函数库. 不被认为是安全的，但对于消息摘要功能仍然有用.  [外籍人士][14].
* [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts)  - 常见加密快捷方式的集合.  [zlib] [33].
* [trivial-ssh](https://github.com/eudoxia0/trivial-ssh)  - SSH 客户端库.  [外籍人士][14].
* [cl-ssh-keys](https://github.com/dnaeon/cl-ssh-keys)  - 用于生成和解析 OpenSSH 密钥的 Common Lisp 系统.  [BSD_3 条款][15].
* [cl-bcrypt](https://github.com/dnaeon/cl-bcrypt)  - 用于解析和生成 bcrypt 密码哈希的 Common Lisp 系统.  [BSD_3 条款][15].
  * see also [cl-pass](https://github.com/eudoxia0/cl-pass)，使用 pbkdf2.

Cryptocurrencies
================

* [cl-monero-tools](https://github.com/glv2/cl-monero-tools)  - 用于 Monero 加密货币的 Common Lisp 工具箱.  [GPL3][2]. 不在 Quicklisp 中.
* [emotiq](https://github.com/emotiq/emotiq)  - 具有创新的自然语言智能合约方法的下一代区块链.  [麻省理工学院][200].
* [peercoin-blockchain-parser](https://github.com/glv2/peercoin-blockchain-parser)  - 解析包含在文件中的区块链并将其部分数据导出到文本文件、SQL 脚本或数据库. 它还可以使用 Peercoin 守护进程的 RPC 作为数据源而不是区块链文件来创建数据库.  LGPL3. 不在 Quicklisp 中.
* [peercoin-calculator](https://github.com/glv2/peercoin-calculator)  - 该程序为您提供在10分钟、24小时、31天、90天和1年内生成POS或POW区块的概率，以及可预期的奖励.  Qt 中的图形用户界面.  [GPL3][2]. 不在 Quicklisp 中.
* [peercoin-vote](https://github.com/glv2/peercoin-vote)  - 基于区块链数据（地址和余额）的投票系统.  [GPL3][2]. 不在 Quicklisp 中.

也可以看看 [legochain](https://github.com/defunkydrummer/legochain)，一个简单的教育区块链.

Database
========

* [cl-yesql](https://github.com/ruricolist/cl-yesql)  - SQL 语句存在于它们自己的文件中，采用 SQL 语法，并作为函数导入 Lisp. 您不仅限于 DSL 支持的功能. 基于Clojure的Yesql.  [麻省理工学院][200].

ORMs
----

* ：星星： [clsql](http://www.cliki.net/CLSQL)  - 一个带有 Common Lisp 接口的 SQL 数据库.  [LLGPL] [8].
*  [mito](https://github.com/fukamachi/mito) - 具有迁移、关系和 PostgreSQL 支持的 Common Lisp 的 ORM [LLGPL][8]. [mitho-auth](https://github.com/fukamachi/mito-auth)，一个用于使用授权的mixin类； [mito-attachment](https://github.com/fukamachi/mito-attachment)，用于 RDBMS 之外的文件管理的 mixin 类.
* [cl-dbi](https://github.com/fukamachi/cl-dbi)  - Common Lisp 的独立于数据库的接口.  [LLGPL] [8].
  * [dbd-oracle](https://github.com/sergadin/dbd-oracle)  - 用于 CL-DBI 的 Oracle 数据库驱动程序.  [LLGPL] [8].
* [crane](https://github.com/eudoxia0/crane)  - 另一个 ORM.  [外籍人士][14].
* [datafly](https://github.com/fukamachi/datafly)  - 一个轻量级的数据库库.  [3 条款 BSD][15].
* [sxql](https://github.com/fukamachi/sxql)  - 用于生成 SQL 的 DSL.  [3 条款 BSD][15].

持久对象数据库
---------------------------

* [bknr.datastore](https://github.com/hanshuebner/bknr-datastore) - RAM 中基于 CLOS 的仅 lisp 数据库，具有事务日志持久性. [Manual](https://www.common-lisp.net/project/bknr/html/documentation.html) .  [许可证] [208].
  *另见这个 [good introductory blog post](https://ashok-khanna.medium.com/persistent-in-memory-data-storage-in-common-lisp-b-k-n-r-37f8ae76042f)
  * 使用 bknr.datastore 的示例 Web 应用程序： [screenshotbot-oss](https://github.com/screenshotbot/screenshotbot-oss).
* [ubiquitous](https://github.com/Shinmera/ubiquitous)  - 提供易于使用的持久配置存储的库.  [zlib] [33].
* [cl-prevalence](https://common-lisp.net/project/cl-prevalence/)  - 内存数据库系统. 对象普遍性的实现，其中业务对象保持在内存中，事务被记录以进行系统恢复. [github fork](https://github.com/40ants/cl-prevalence) .  [LLGPL] [8]. 也可以看看 [cl-prevalence-multimaster](https://github.com/40ants/cl-prevalence-multimaster), 同步多个 cl-流行系统状态.

图数据库
---------------

* [cl-agraph](https://github.com/vseloved/cl-agraph), 最小客户端 [AllegroGraph](https://allegrograph.com/) .  AllegroGraph 是一种水平分布、多模型（文档和图）、实体-事件知识图谱技术. 它是专有的，有一个免费版本，限制为 500 万个三元组.
* [cl-neo4j](https://github.com/kraison/cl-neo4j) - neo4j RESTFUL 客户端界面.
* [vivace-graph](https://github.com/kraison/vivace-graph-v3)  - 图数据库和 Prolog 实现. 从 CouchDB、neo4j 和 AllegroGraph 中汲取设计灵感. 它实现了一个符合 ACID 的对象图模型，带有用户定义的索引和 map-reduce 视图. 它还实现了用于冗余和水平读取扩展的主/从复制方案. 查询图是通过许多 Lisp 方法或通过类似 Prolog 的查询语言完成的.  [麻省理工学院][200].
* [facts](https://github.com/cl-facts/facts)  - 具有事务和回滚、日志记录/重放和转储/加载到/从磁盘的内存中图形数据库.  BSD 风格的许可证 (ISC).


Wrappers
--------

* ：星星： [postmodern](http://marijnhaverbeke.nl/postmodern/)  - 用于与 PostgreSQL 交互的库.  [zlib] [33].
* [cl-sqlite](https://github.com/dmitryvk/cl-sqlite)  - SQLite 的绑定. 公共区域.
* [cl-memcached](https://github.com/quasi/cl-memcached)  - Memcached 对象缓存系统的快速、线程安全接口.  [外籍人士][14].
* [cl-mongo](https://github.com/fons/cl-mongo)  - MongoDB 客户端.  [外籍人士][14].
* [cl-redis](https://github.com/vseloved/cl-redis)  - Redis 客户端.  [外籍人士] [14].
* [cl-disque](https://github.com/CodyReichert/cl-disque)  - 客户端磁盘.  [3-BSD 条款] [15].
* [cl-rethinkdb](https://github.com/orthecreedence/cl-rethinkdb)  - RethinkDB 客户端.  [外籍人士][14].
* [cl-mango](https://github.com/cmoore/cl-mango/)  - 一个极简的 CouchDB 2.x 数据库客户端.  BSD_3 条款. 也可以看看 [clouchdb](https://common-lisp.net/project/clouchdb/)  - 用于与 CouchDB 交互的库.  [FreeBSD] [39].

迁移工具
---------------

* [cl-migratum](https://github.com/dnaeon/cl-migratum)  - 提供用于执行数据库模式迁移的设施的系统，旨在与各种数据库一起使用.  [BSD_3 条款][15].
* [postmodern-passenger-pigeon](https://github.com/fisxoj/postmodern-passenger-pigeon/)  - 后现代的移民经理. 未指定许可证.


给第三方
----------------

* [dyna](https://github.com/Rudolph-Miller/dyna)  - AWS DynamoDB ORM.  [麻省理工学院] [200].
* [cl-influxdb](https://github.com/mmaul/cl-influxdb/)  - 时间序列数据库 InfluxDB 的接口.  [麻省理工学院][200].
* [pzmq](https://github.com/orivej/pzmq)  - ZeroMQ 4.0+ 通用 Lisp 绑定. 未经许可.

Tools
-----

* [pgloader](https://github.com/dimitri/pgloader)  - PostgreSQL 的数据加载工具.  [PostgreSQL 许可证][205].


数据结构
===============

*  [str](https://github.com/vindarel/cl-str)  - 现代、简单且一致的字符串操作库.  [麻省理工学院][200].
*  [FSet](https://common-lisp.net/project/fset)  - 一个功能性的、集合论的集合数据结构库.  [LLGPL] [8].
* [trivial-extensible-sequences](https://github.com/Shinmera/trivial-extensible-sequences) - 可扩展序列协议的可移植性库（[SBCL documentation](http://www.sbcl.org/manual/#Extensible-Sequences) ）.  [zlib] [33].
* [bst](https://github.com/glv2/bst)  - 二叉搜索树.  [GPL3][2].
* [pileup](http://nikodemus.github.io/pileup/)  - 用于 Common Lisp 的可移植、高性能和线程安全的二进制堆.  [麻省理工学院][200].
* [sycamore](https://github.com/ndantam/sycamore)  - 一个快速、纯功能的数据结构库.  [BSD_3 条款][15].
* [genhash](https://github.com/pnathan/genhash)  – 使用通用方法的 API 实现哈希表. 公共区域.
* [cl-ctrie](https://github.com/danlentz/cl-ctrie) -
具有高效内存映射持久性和快速瞬态存储模型的无锁、并发、键/值索引.  [麻省理工学院][200].
* [cl-data-structures](https://github.com/sirherrbatka/cl-data-structures)  - 数据结构和算法的可移植集合（主要是字典和序列，具有一些统计功能）.  [BSD] [15].
* [listopia](https://github.com/Dimercel/listopia)  - 受 Haskell 的 Data.List 启发的列表操作库.  [LLGPL] [8].
* [hash-set](https://github.com/samebchase/hash-set/) - 在 CL 哈希表之上实现哈希集的便利库 [The Unlicense][5]
* [cl-containers](https://common-lisp.net/project/cl-containers/) - 一个广泛的数据结构和实用程序库 - 队列、树、堆、双向链表、集合、包…… [MIT][200]
* [cl-competitive](https://github.com/privet-kitty/cl-competitive)  - 用于竞争性编程的 Common Lisp 算法集合. 公共领域，CCO 或 MIT.

访问数据结构：

*  [access](https://github.com/AccelerationNet/access/)  - 对最常见数据结构的一致和嵌套访问.  [BSD_3 条款][15].
* [modf](https://github.com/smithzvk/modf) - 用于函数式编程的类似 setf 的宏.

其他数据结构：

* [bitfield](https://github.com/marcoheisig/bitfield)  - 有效地将几个有限集或小整数表示为单个非负整数.  [麻省理工学院][200].


Docker 镜像
=============

* [cl-docker-images](https://common-lisp.net/project/cl-docker-images/) - 用于 Windows (amd64) 和 Alpine 和 Debian (amd64, arm64, arm/v7) [BSD_2Clause] [17] 上的 ABCL、CCL、ECL 和 SBCL 的 Docker 映像.
* [base-lisp-image](https://github.com/40ants/base-lisp-image) - 根据
  带有 SBCL 或 CCL 和最新版本的 Common Lisp 项目的 Docker 镜像
  ASDF、Qlot 和罗斯威尔.


外部函数接口，语言互操作
=============================================

## C ##

* ：星星： [CFFI](https://github.com/cffi/cffi)  - 可移植、易于使用的 C 外来函数接口.  [外籍人士][14].
* [cl-autowrap](https://github.com/rpav/cl-autowrap)  - 自动将头文件解析为 CFFI 定义.  [FreeBSD] [39].
* [cl-bindgen](https://github.com/sdilts/cl-bindgen)  - 用于从 C 头文件创建 Common Lisp 语言绑定的命令行工具和库.  [麻省理工学院][200].
* [cl-gobject-introspection](https://github.com/andy128k/cl-gobject-introspection) - [Gobject Introspection](https://gi.readthedocs.io/en/latest/) 外国金融机构. 调用 C 库的自动绑定.  [BSD] [15]. 生成一个 lisp 接口 [gir2cl](https://github.com/kat-co/gir2cl) .  [LGPL3][9].
* [cl-cxx-jit](https://github.com/Islam0mar/CL-CXX-JIT)  - Common Lisp 和 C++ 与 JIT 的互操作.  [麻省理工学院][200].

## Clojure

* [ABCLJ](https://github.com/lsevero/abclj)  - 非常简单的 Clojure 到 Common lisp 互操作.  EPL-2.0.

## Erlang ##

* [CLERIC](https://github.com/flambard/CLERIC)  - 一个通用的 Lisp Erlang 接口.  Erlang 分发协议的一个实现，与 erl_interface 和 jinterface 相当.  [麻省理工学院][200].

## Java ##

* [cl+j](https://common-lisp.net/project/cl-plus-j/)  - 通过 CFFI 连接到 JVM 的基于 JNI 的接口. 在 Quicklisp 上不可用. 不能可靠地与所有实现一起工作.  [外籍人士][14].

## Objective-C ##

* [objc-lisp-bridge](https://github.com/fiddlerwoaroof/objc-lisp-bridge)  - 用于与 Objective-C 和 Cocoa 交互的便携式阅读器和桥梁.  [麻省理工学院][200].

## Python ##

* [burgled-batteries](https://github.com/pinterface/burgled-batteries)  - Python 和 Common Lisp 之间的桥梁. 目标是 Lisp 程序可以使用 Python 库. 在 Quicklisp 上不可用.  [麻省理工学院][200].
* [cl4py](https://github.com/marcoheisig/cl4py) - The library cl4py (pronounce as clappy) allows Python programs to call Common Lisp libraries. [MIT][200].
* [py4cl](https://github.com/bendudson/py4cl)  - 一个允许 Common Lisp 代码访问 Python 库的库. 它基本上是 cl4py 的倒数.  [麻省理工学院][200].
* [cl-python](https://github.com/metawilm/cl-python)  - 在 Common Lisp 中的 Python 实现.  [LLGPL] [8].

也可以看看 [async-process](https://github.com/cxxxr/async-process/).

## .Net Core

* [Bike](https://github.com/Lovesan/bike)  - 跨平台的 .Net Core 接口.  [麻省理工学院][200].

## Miscellaneous ##

* [Foil](http://foil.sourceforge.net/)  - 异物接口； 适用于 JVM 和 CLI. 在 Quicklisp 上不可用.  [CPL 1.0] [47].


游戏开发
================

* [Xelf](http://xelf.me/)  - 可扩展的游戏库. 在 Quicklisp 上不可用.  [GNU LGPL2.1][11].
* [Trial](https://github.com/shirakumo/trial)  - Trial 是一个 OpenGL 游戏引擎，非常注重模块化. 它应该提供一个包含有用点点滴滴的大型工具包，您可以从中创建游戏.  [zlib] [33].
* [cl-mpg123](https://shirakumo.github.io/cl-mpg123) 和 [cl-out123](https://shirakumo.github.io/cl-out123), bindings libraries for libmpg123 和 libout123 respectively, giving you fast 和 easy to use mp3 decoding 和 cross-platform audio output. [zlib][33].
* [trivial-gamekit](https://borodust.org/projects/trivial-gamekit/getting-started/)  – 使用这个小框架，您将能够制作简单的 2D 游戏：绘制基本的几何形状、图像和文本、播放声音以及聆听鼠标和键盘输入.  [麻省理工学院][200].
* [cl-gamepad](https://shirakumo.github.io/cl-gamepad)  - 在 Windows、Mac OS 和 Linux 上访问游戏手柄和操纵杆.  [zlib] [33].
* [virality](https://github.com/bufferswap/ViralityEngine) - 用 Common Lisp [MIT][200] 编写的基于组件的游戏引擎.

Graphics
========

These are libraries for working with graphics, rather than making GUIs (i.e. widget toolkits), which have their own section.

* ：星星： [Sketch](https://github.com/vydd/sketch)  - 用于创建电子艺术、图形等的 CL 框架.  [麻省理工学院][200].
* [common-cv](https://github.com/byulparan/common-cv)  - CommonLisp 的 OpenCV（开源计算机视觉库）绑定库. 未指定许可证.
* [cl-cairo2](https://github.com/rpav/cl-cairo2)  - 开罗绑定.  [提升 1.0][54]
* [cl-gd](http://weitz.de/cl-gd/)  - 为 GD 图形库提供接口的库.  [FreeBSD] [39].
* [cl-horde3d](https://github.com/anwyn/cl-horde3d/)  - FFI 绑定到 Horde3D 图形库. 在 Quicklisp 上不可用.  [英超 1.0][59]
* [cl-jpeg](https://github.com/sharplispers/cl-jpeg)  - 基线 JPEG 编码器和解码器库.  [3 条款 BSD][15].
* [cl-liballegro](https://github.com/resttime/cl-liballegro)  - Allegro 5 游戏编程库的接口和绑定.  [zlib] [33].
* [cl-opengl](https://github.com/3b/cl-opengl)  - CFFI 绑定到 OpenGL、GLU 和 GLUT API.  [3 条款 BSD][15].
* [cl-sdl2](https://github.com/lispgames/cl-sdl2)  - 使用 C2FFI 绑定 SDL2.  [外籍人士][14].
* [cl-svg](https://github.com/wmannis/cl-svg)  - 用于生成 SVG 文件的基本库.  [外籍人士][14].
* [CLinch](https://github.com/BradWBeer/CLinch)  - 用于 OpenGL 的 Common Lisp 2D/3D 图形引擎.  [FreeBSD] [39].
* [donuts](https://github.com/tkych/donuts)  - Common Lisp 的图形绘制 DSL.  [外籍人士][14].
* [dufy](https://github.com/privet-kitty/dufy)  - 各种颜色模型中的精确颜色操作和转换.  [麻省理工学院][200].
* [lispbuilder-sdl](https://github.com/lispbuilder/lispbuilder)  - SDL 的一组绑定.  [外籍人士][14].
* [lisp-magick-wand](https://github.com/TBRSS/lisp-magick-wand)  - ImageMagick 绑定.  [BSD] [15]. 不在 Quicklisp 中.
* [okra](https://www.common-lisp.net/project/okra/manual.html)  - CFFI 绑定到 Ogre. 在 Quicklisp 上不可用.  [3 条款 BSD][15].
* [opticl](https://github.com/slyrus/opticl)  - 用于表示和处理图像的库.  [BSD_2 条款][17].
* [Varjo](https://github.com/cbaggers/varjo)  - Lisp 到 GLSL 翻译器.  [BSD_2 条款][17].
* [Vecto](http://www.xach.com/lisp/vecto/)  - 简单的矢量绘图库.  [FreeBSD] [39].
* [zpng](http://www.xach.com/lisp/zpng/)  - 用于创建 PNG 文件的库.  [FreeBSD] [39].
* [pngload-fast](https://git.mfiano.net/mfiano/pngload)  - 便携式 Common Lisp 中的 PNG（便携式网络图形）图像格式解码器，强调速度.  [麻省理工学院][200].
* [cl-cuda](https://github.com/takagi/cl-cuda)  - 在 Common Lisp 程序中使用 NVIDIA CUDA 的库.  [LLGPL] [8].


GUI
===

有关 GUI 工具包的概述和教程，请参见 [the Cookbook/GUI](https://lispcookbook.github.io/cl-cookbook/gui.html).

* [LispWork's CAPI](http://www.lispworks.com/products/capi.html)  - 具有移动运行时的便携式 GUI 工具包. 专有，但带有免费版本.
*  [Qtools](https://github.com/Shinmera/qtools/)  - 基于 CommonQt 的 Qt 工具包.  [zlib][33] 还有 [Qtools-ui](https://github.com/Shinmera/qtools-ui) （预制的 UI 组件），与 [videos](https://www.youtube.com/watch?v=KwASFOhYta4&index=7&list=PLkDl6Irujx9Mh3BWdBmt4JtIrwYgihTWp).
* ：星星： [CommonQt](https://github.com/commonqt/commonqt)  - 通过 QtSmoke 对 Qt4 的 Common Lisp 绑定.  [FreeBSD] [39].
* ：星星： [ltk](http://www.peter-herth.de/ltk/)  - Tk 工具包的绑定.  [LLGPL][8] 或 [GNU LGPL2.1][11].
  * [LTk Examples](https://peterlane.netlify.app/ltk-examples/) - 为 tkdocs 教程提供 LTk 示例.
  * [LTk Plotchart](https://peterlane.netlify.app/ltk-plotchart/)  - 围绕 tklib/plotchart 库与 LTk 一起使用的包装器. 这包括 20 多种不同的图表类型（xy 图、甘特图、3d 条形图等...）.
* [IUP](https://github.com/lispnik/iup/) - YFC 绑定到 [IUP](https://www.tecgraf.puc-rio.br/iup/) 便携式用户界面库（ALPHA 之前）.  IUP 是跨平台的（Windows、macOS、GNU/Linux，带有新的 Android、iOs、Cocoa 和 Web Assembly 驱动程序），有许多小部件，有一个小的 api 并且正在积极开发.
* [nodgui](https://notabug.org/cage/nodgui)  - Tk 工具包的绑定，基于 Ltk，带有语法糖和附加小部件.  [LLGPL] [8].
* [cl-cffi-gtk](https://github.com/Ferada/cl-cffi-gtk/)  - GTK+3 绑定.  [GNU LGPL2.1][11].
* [cl-gtk2](https://github.com/dmitryvk/cl-gtk2)  - GTK+2 的绑定.  [LLGPL] [8].
* [ceramic](https://ceramic.github.io/)  - 带有 Electron 的桌面 Web 应用程序.  [外籍人士][14].
  * [Electron-lisp-boilerplate](https://github.com/mikelevins/electron-lisp-boilerplate) - 用于构建带有嵌入式 Lisp 帮助程序进程的 Electron 应用程序的基本样板.
  *电子应用程序骨架： [electron-sbcl-sqlite](https://github.com/mikelevins/electron-sbcl-sqlite/)
* [CocoaInterface](https://github.com/plkrueger/CocoaInterface/) -
 Clozure Common Lisp 的 Cocoa 接口. 构建 Cocoa 用户界面
windows 动态使用 Lisp 代码并绕过典型的 Xcode
过程. 它有
[good documentation and a tutorial](https://github.com/plkrueger/CocoaInterface/blob/master/Documentation/UserInterfaceTutorial.pdf).
* [McCLIM](https://common-lisp.net/project/mcclim/)  - Common Lisp 接口管理器的实现，版本 II.  [GNU LGPL2.1][11].
* [cl-webkit](https://github.com/joachifm/cl-webkit)  - 与 WebKitGTK+ 的绑定. 还向应用程序添加 Web 浏览功能，充分利用 WebKit 浏览引擎的强大功能.  [麻省理工学院][200].
* [ftw](https://github.com/fjames86/ftw)  - Win32 GUI 库.  [麻省理工学院][200].
* [eql, eql5, eql5-android](https://gitlab.com/eql)  - 嵌入式 Qt4 和 Qt5 Lisp，嵌入 ECL，可嵌入 Qt. 将 EQL5 移植到 Android 平台.  [麻省理工学院][200].
* [bodge-nuklear](https://github.com/borodust/bodge-nuklear) - 包装在 [Nuklear](https://github.com/vurtun/nuklear) 立即模式 GUI 库.  [麻省理工学院] [200].
* [Allegro's Common Graphics](https://franz.com/products/allegro-common-lisp/acl_gui_tools.lhtml) - 用于为 Windows、Mac 和 Linux 编写窗口化 GUI 的函数库. 所有权.

另见这个 [demo to use Java Swing from ABCL](https://github.com/defunkydrummer/abcl-jazz).


Implementations
===============

* ：星星： [SBCL](http://www.sbcl.org/index.html)  - CMUCL 的一个分支； 编译成机器码.  [符合标准][13]. 公共领域，某些部分属于 [Expat][14] 和 [3-clause BSD][15].
* ：星星： [CCL](https://github.com/CodyReichert/awesome-cl/blob/master///ccl.clozure.com/)  - Clozure Common Lisp； 仅编译器实现，生成本机代码.  [LLGPL] [8].
* [ECL](https://common-lisp.net/project/ecl/) - Embeddable Common Lisp; compiles to C. [GNU LGPL2.1][11].
* [ABCL](https://common-lisp.net/project/armedbear/)  - 武装熊Common Lisp； 以 JVM 为目标，编译为字节码.  [标准一致性][4].  [GNU GPL3][2] 带有 [类路径例外][3].
* [CMUCL](https://github.com/CodyReichert/awesome-cl/blob/master///www.cons.org/cmucl/)  - 卡内基梅隆大学的一个实现. 公共区域.
* [GNU CLISP](http://www.clisp.org/)  - GNU 实现； 包含一个编译器和一个解释器.  [标准一致性][6].  [GNU GPL3][2].
* [CLASP](https://github.com/drmeister/clasp)  - 一种新的 Common Lisp 实现，可与 C++ 库和程序无缝互操作，使用 LLVM 编译为本机代码. 这使 Clasp 能够利用大量预先存在的库和程序，例如科学计算生态系统之外的库和程序.  [LGPL2.1][11]（及其他）.
* [Corman Lisp](https://github.com/sharplispers/cormanlisp)  - 在 Intel 平台上运行的 Microsoft Windows 的 Common Lisp 开发环境.  [麻省理工学院][200].

Proprietary:

* [LispWorks](http://www.lispworks.com/) - Common Lisp 的集成跨平台开发工具.
* [Allegro CL](https://franz.com/products/allegro-common-lisp/) - 提供带有许多扩展的完整 ANSI Common Lisp 标准.
* [MOCL](https://wukix.com/mocl) - CL 作为移动设备（iOS 和 Android）和 OSX 的库.

JSON
====

* [jonathan](https://github.com/Rudolph-Miller/jonathan)  - JSON 编码器和解码器.  [麻省理工学院][200].
* [cl-json](https://github.com/sharplispers/cl-json)  - 高度可定制的 JSON 编码器和解码器.  [麻省理工学院][14].
* [jsown](https://github.com/madnificent/jsown)  - JSON 格式的读写器.  [外籍人士][14].
* [json-mop](https://github.com/gschjetne/json-mop)  - 用于桥接 CLOS 和 JSON 对象的元类.  [麻省理工学院][200].
* [cl-json-pointer](https://github.com/y2q-actionman/cl-json-pointer)  - JSON 指针实现.  [麻省理工学院][200].

另见这个 [extensive comparison](https://sites.google.com/site/sabraonthehill/home/json-libraries) JSON 库.

YAML
====

* [cl-yacclyaml](https://github.com/mabragor/cl-yaclyaml)  - 纯 lisp YAML 处理器（加载程序，但尚未转储程序）.  [GPL3][2].
* [cl-yaml](https://github.com/eudoxia0/cl-yaml.git)  - 一个建立在 libyaml 之上的 YAML 解析器和发射器.  [麻省理工学院][200].


语言扩展
===================

* ：星星： [alexandria](https://common-lisp.net/project/alexandria/)  - 一个通用的实用程序库. 公共区域.
* [serapeum](https://github.com/TBRSS/serapeum/)  - 另一个通用实用程序库.  [外籍人士][14].
* [rutils](https://github.com/vseloved/rutils)  - Common Lisp 的激进而合理的语法实用程序.  [麻省理工学院][200].
* [anaphora](https://common-lisp.net/project/anaphora/)  - 一组照应宏. 公共区域.
* ：星星： [trivia](https://github.com/guicho271828/trivia/)  - 优化模式匹配库.  [LLGPL] [8].
* [arrow-macros](https://github.com/hipeta/arrow-macros)  - 类似 Clojure 的线程宏.  [麻省理工学院][200].
* [dissect](https://shinmera.github.io/dissect)  - 当许多项目使用“trivial-backtrace”系统时，它只为它们提供一个带有回溯的字符串，Dissect 允许您捕获、步进和完全检查各种 Lisp 实现上的堆栈跟踪. 对于日志记录和其他自动继续执行的情况也非常有用，但是当前堆栈的信息存储在某处仍然很有用.  [zlib] [33].
* [generic-cl](https://github.com/alex-gutev/generic-cl/)  - 标准 Common Lisp 函数（相等、比较、算术、对象、迭代器、序列等）的通用函数接口.  [麻省理工学院][200]. 另见更轻量 [generic-comparability](https://github.com/pnathan/generic-comparability) .  [LLGPL] [8].
* [hu.dwim.walker](https://quickref.common-lisp.net/hu.dwim.walker.html)  - 代码walker 和unwalker（又名AST 解析器和解析器）.  [BSD] [15]. 也可以看看 [this blog post](http://40ants.com/lisp-project-of-the-day/2020/04/0044-hu.dwim.walker.html).

可移植层
------------------

大量可移植层 [is collected here](https://shinmera.github.io/portability/) . 这里是其中的一些：

* [trivial-arguments](https://github.com/Shinmera/trivial-arguments)  - 一个便携式库，用于检索函数的参数列表.  [zlib] [33].
* [definitions](https://github.com/Shinmera/definitions)  - 通用定义内省库. 它使您能够检索与指示符（例如符号、包和名称）相关联的定义或绑定.  [zlib] [33].

更改语法
-------------------

* [cl21](https://github.com/cl21/cl21)  - 将 Common Lisp 带入 21 世纪的实验项目.  [外籍人士][14].
* [clamp](https://github.com/malisper/Clamp)  - Arc 语言对 Common Lisp 的简洁性.  [艺术许可 2.0][51].
* [cl-syntax](https://github.com/m2ym/cl-syntax)  - 读者语法约定.  [LLGPL] [8].
* [cl-2dsyntax](http://www.cliki.net/cl-2dsyntax)  - 压痕敏感阅读器系统. 在 Quicklisp 上不可用. 公共区域.
* [cl-annot](https://github.com/m2ym/cl-annot)  - Common Lisp 的类 Python 注释.  [LLGPL] [8].
* ：星星： [cl-interpol](https://github.com/edicl/cl-interpol/)  - 一组读取器修改以允许字符串插值.  [BSD] [15].
* [pythonic-string-reader](https://github.com/smithzvk/pythonic-string-reader)  - 受 Python 的三个引号字符串启发的简单且不显眼的读取表修改.  [BSD_3 条款][15].
* [cl-reader](https://github.com/digikar99/reader) - 实用程序库
旨在为 lambda、映射、访问器提供读取器宏，
哈希表和哈希集.  [麻省理工学院][200].


CLOS 扩展
---------------

* ：星星： [closer-mop](http://cliki.net/closer-mop)  - 一个兼容层，可以纠正许多缺失或不正确的 MOP 功能.  [外籍人士][14].
* [defclass-std](https://github.com/EuAndreh/defclass-std)  - 快速编写 DEFCLASS 表单的快捷宏.  [LLGPL] [8].
* [specialization-store](https://github.com/markcox80/specialization-store/)  - 基于类型的通用函数. 简化的 BSD 许可证变体.
* [filtered-functions](https://github.com/pcostanza/filtered-functions)  - 允许使用任意谓词来选择和应用方法.  [麻省理工学院][200].
* [inlined-generic-function](https://github.com/guicho271828/inlined-generic-function) -
将静态调度的速度带入 CLOS.  [LLGPL] [8].
* [static-dispatch](https://github.com/alex-gutev/static-dispatch)  - 允许静态（在编译时）而不是动态（运行时）执行标准的通用函数调度. 这类似于 C++ 和 Java 等语言中所谓的“重载”.  [麻省理工学院][200].
* [dynamic-mixins](https://github.com/rpav/dynamic-mixins)  - 简单、动态的类组合.  [BSD_2 条款][17].
* [fast-generic-functions](https://github.com/marcoheisig/fast-generic-functions)  - 密封您的通用功能以进一步提高性能.  [麻省理工学院][200].
* [polymorphic functions](https://github.com/digikar99/polymorphic-functions)  - 在类型上调度的函数类型，而不是部分支持在可选和关键字参数类型上调度的类. 仍在试验中（2021 年 5 月）.  [麻省理工学院][200].
   - 多态函数根据提供给它的参数类型进行调度. 这有助于在专门的数组和用户定义的类型上进行调度.
  - 有关 specialization-store 和 fast-generic-functions 的差异，请参阅其自述文件.

并且：

* [slot-extra-options](https://github.com/some-mthfka/slot-extra-options)  - 允许您构建一个元类，从而让您在其类中指定额外的插槽选项.  [LGPL3][9].

功能扩展
-------------------

* [cl-hooks](https://github.com/scymtym/architecture.hooks/)  - Hooks 扩展点机制（众所周知，例如来自 GNU Emacs）.  LGPL.
* [method-hooks](https://gitlab.com/Gnuxie/method-hooks)  - 当 CLOS 方法组合每个方法只允许一个钩子时，这个库允许任意数量的钩子.  Mozilla 公共许可证.
* [cl-advice](https://github.com/lisp-mirror/budden-tools/blob/213ab2b52a1b0c0b496efd30c3b5143f5c8e1ff2/cl-advice/README.md)  - SBCL、CCL、LispWorks 和 Allegro 的可移植层建议库的尝试. 不在 Quicklisp 中.

另请参阅 Serapeum 中的钩子.

Iteration
---------

* ：星星： [iterate](https://common-lisp.net/project/iterate/)  - 可扩展和 Lispier 的 Common Lisp 迭代构造.  [麻省理工学院][200].
* [for](https://shinmera.github.io/for/)  - 一个简洁、流畅和可扩展的迭代宏. 与循环不同，它是可扩展且合理的，与迭代不同的是，它不需要代码遍历并且更容易扩展.  [zlib] [33].
* [series](https://github.com/tokenrove/series/wiki)  - 完全没有任何运行时损失的函数式风格.  [麻省理工学院][200].
* [gmap](https://github.com/slburson/misc-extensions/blob/master/src/gmap.lisp)  - 简洁且可扩展的迭代工具，具有与 FSet 很好地集成的优势（参见数据结构部分），因为它是由同一作者编写的. 在 Quicklisp 作为 `misc-extensions` 的一部分. 公共区域.
* [trivial-do](https://github.com/yitzchak/trivial-do/)  - Common Lisp 的附加 dolist 样式宏.  [麻省理工学院][200].
* [doplus](https://github.com/alessiostalla/doplus) – 另一个可扩展的迭代库，类似于 :for.
* [snakes](https://github.com/BnMcGn/snakes) - Python style generators for Common Lisp. Includes a port of itertools. [Apache2][89].
* [picl](https://github.com/anlsh/picl)  - Python 的 itertools 包的（几乎）完整端口，在适用的情况下具有惰性，并且不依赖于 cl-cont.  [麻省理工学院][200].
* [gtwiwtg](https://github.com/cbeo/gtwiwtg)  - 一个懒惰的序列库. 类似于“系列”但不完整. 然而，它有一个“现代”API，其中包含“take”、“filter”、“for”、“fold”等易于使用的内容.


Lambda 简写
-----------------

* [fn](https://github.com/cbaggers/fn)  - 几个 lambda 速记宏.  `(fn* (+ _ _)) --&gt; (lambda (_) (+ _ _))`. 公共区域.
* [f-underscore](https://gitlab.common-lisp.net/bpm/f-underscore)  - 一个小型的函数式编程工具库.  `(f_ (+ _ _)) -&gt; (lambda (_) (+ _ _))`. 公共区域.
* [cl-punch](https://github.com/windymelt/cl-punch/)  - 类似 Scala 的匿名 lambda 文字.  `(mapcar ^(* 2 _) &#39;(1 2 3 4 5))`.  [麻省理工学院][200].


另见 CL21 和 [Rutils](https://github.com/vseloved/rutils).



非确定性逻辑编程
------------------------------------

* [cl-prolog2](https://github.com/guicho271828/cl-prolog2)  - 来自 Common Lisp 的 ISO Prolog 实现的通用接口.  [麻省理工学院][200].
* [Screamer](https://github.com/nikodemus/screamer) - 增加普通
  Lisp 具有 Prolog 和
  约束逻辑编程
  语言. [Blog post](https://chriskohlhepp.wordpress.com/reasoning-systems/specification-driven-programming-in-common-lisp/)
  解决 Project Euler 难题.  [麻省理工学院][200].
* [Screamer+](https://github.com/yakovzaytsev/screamer-plus)  - 增加 SCREAMER 的表现力.  [麻省理工学院][200].
* [Temperance](https://github.com/sjl/temperance)  - 逻辑编程.  [麻省理工学院][200]. 专注于性能，并考虑到一般游戏玩法.

反应式编程
--------------------

* [Cells](https://github.com/kennytilton/cells)  - 数据流编程范式的实现，CLOS 的类似电子表格的反应式表达能力. 用于构建一个 [algebra learning system](http://tiltontec.com/) . 和 [documentation](https://github.com/stefano/cells-doc/) .  Lisp LGPL.

合约编程
--------------------

* [quid-pro-quo](https://github.com/sellout/quid-pro-quo) - 合同
   Eiffel 的 Design by Contract™ 风格的编程库. 公共区域.

Typing
------

*  [Coalton](https://github.com/coalton-lang/coalton/)  - 一种高效的、静态类型的函数式编程语言，可以增强 Common Lisp.  [麻省理工学院][200].
* [cl-algebraic-data-type](https://github.com/stylewarning/cl-algebraic-data-type)  - 一个以类似于 Haskell 或 ML 的精神定义代数数据类型的库.  [3 条款 BSD][15].
*  [trivial-types](https://github.com/m2ym/trivial-types)  - 提供缺失但重要的类型定义，例如`proper-list`、`association-list`、`property-list` 和`tuple`.  [LLGPL] [8].
* [defstar](https://bitbucket.org/eeeickythump/defstar/src/master/)  - 一组宏，用于轻松包含 lambda 列表中参数的类型声明.  [GNU GPL3][2]


学习和教程
=====================

## Online ##

Beginner
--------

* [Learn X in Y minutes - Where X = Common Lisp](https://learnxinyminutes.com/docs/common-lisp/) - 涵盖基本知识的小型 Common Lisp 教程.
* [Lisp Koans][201] - 该项目通过许多 Common Lisp 语言功能逐步引导学习者.
 * [Practical Common Lisp][206] - Common Lisp 的很好的介绍性文本，带有实际示例. 更好地阅读 [a Firefox add-on](https://github.com/vale981/practical-cl-beautified).
* [Common LISP: A Gentle Introduction to Symbolic Computation](http://www.cs.cmu.edu/afs/cs.cmu.edu/user/dst/www/LispBook/index.html) - 很好的语言介绍.
* [Successful Lisp](http://successful-lisp.blogspot.com/) - 一本适合具有一定编程背景的初学者的好书.
* [Lisp Quickstart](https://cs.gmu.edu/~sean/lisp/LispTutorial.html) - 快速入门和编写 Common Lisp 的好教程.
* [Casting SPELs in LISP](http://www.lisperati.com/casting.html) - 在阅读漫画书的同时学习 LISP 的有趣方式.

Intermediate
------------

* [The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/)
* [Lisp Tips](https://github.com/lisp-tips/lisp-tips/issues/)  - 包含有用提示和技巧的博客. 的延续 [Common Lisp tips](http://lisptips.com/).
* [Lisp project of the day](http://40ants.com/lisp-project-of-the-day/) - 展示许多 Lisp 库的博客.

Advanced
--------

 * [Let Over Lambda][156] - 一本关于高级宏技术的书. 前六章可在​​线获取.
* [On Lisp](http://www.paulgraham.com/onlisp.html) - Paul Graham 关于 Lisp 宏（和其他有趣的东西）的惊人的书.
* [Programming Algorithms in Lisp](https://link.springer.com/book/10.1007/978-1-4842-6428-7) - 更新版本的“[Programming Algorithms](https://leanpub.com/progalgs)&quot;; 在 Lisp 中编写具有数据结构和算法的高效程序的综合指南.

Web开发
--------

* [Lisp for the Web](https://leanpub.com/lispweb) - 一本指导您构建三层投票 Web 应用程序的书.
* [Lisp Web Tales](https://leanpub.com/lispwebtales) - 简单的教程使用 [hunchentoot](http://edicl.github.io/hunchentoot/), [cl-redis](https://github.com/vseloved/cl-redis), [restas](https://github.com/archimag/restas), [SEXML](https://github.com/madnificent/SEXML), [Postmodern](https://github.com/marijnh/Postmodern)， 和更多.
* [Section on Web Development in The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/web.html) - 介绍性教程，涵盖 Web 服务器设置、路由、web 块、模板、错误处理、打包、热重载、数据库连接和部署，以及当前 lisp Web 开发生态系统中的其他主题.

Reference
---------

* [Common Lisp Quick Reference](http://clqr.boundp.org/index.html)  - ANSI CL 规范的精炼袖珍版. 可作为 PDF 下载.
* [CLHS](http://www.lispworks.com/documentation/lw50/CLHS/Front/index.htm)  - Common Lisp HyperSpec；  ANSI CL 标准，超文本形式.
* [CLOS MOP specification](https://clos-mop.hexstreamsoft.com/) - 元对象协议的艺术第 5 章和第 6 章的现代公共领域在线版本
* [Common Lisp Standard Draft (pdf)](https://franz.com/support/documentation/cl-ansi-standard-draft-w-sidebar.pdf) - Common Lisp 规范的标准草案，格式良好的 PDF 和侧边栏.
* [Common Lisp the Language](http://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html) - 在 ANSI 规范之前，Common Lisp 的原始标准.
* [Minispec](https://lamberta.github.io/minispec/)  - 一个更友好但不完整的 CLHS 版本. 还包含一些常用 CL 库（例如 Alexandria）的文档.
* [Simplified Common Lisp reference](http://jtra.cz/stuff/lisp/sclr/index.html) - CLHS 的简化版.

## Offline ##

CLHS 可通过以下方式离线使用 [archive](https://github.com/CodyReichert/awesome-cl/blob/master/ftp://ftp.lispworks.com/pub/software_tools/reference/HyperSpec-7-0.tar.gz) 并且作为文档设置 [Dash](https://kapeli.com/dash), [Zeal](https://zealdocs.org/) 和 [Velocity](https://velocity.silverlakesoftware.com/).

Beginner
--------

* [Land of Lisp](http://landoflisp.com/) - 一个有趣的、面向游戏的 Common Lisp 介绍.
* [Practical Common Lisp][206] - Common Lisp 的很好的介绍性文本，带有实际示例.

Intermediate
------------

* [ANSI Common Lisp](http://www.paulgraham.com/acl.html)  - 对整个语言进行全面、实用的覆盖，并附有练习. 由于[一些警告][20]，不推荐作为入门文本.
* [Common Lisp Recipes](http://weitz.de/cl-recipes/)  - **Common Lisp Recipes** 是您在用 Common Lisp 编写实际应用程序时可能遇到的问题的解决方案和答案的集合.  2015 年出版.

Advanced
--------

 * [Let Over Lambda][156] - 一本关于高级宏技术的书. 所有八章都可以在印刷版中找到.
* [Common Lisp 中的面向对象编程：CLOS 程序员指南][21] - 一本关于 CLOS 的古老但非常全面的书.
* [人工智能编程范式：Common Lisp 中的案例研究][157] - 一本关于人工智能编程的书，涵盖了一些高级 Lisp.

其他书籍
-----------

* [Building Problem Solvers](https://www.qrg.northwestern.edu/bps/readme.html) ([PDF](http://www.qrg.northwestern.edu/bps/BPS-Searchable.pdf)) 由 Ken Forbus 和 Johan de Kleer 免费提供，由麻省理工学院出版社免费提供——这是标准人工智能文本中独一无二的书籍，结合科学与工程、理论和工艺来描述人工智能推理系统的构建，并包括说明这些想法的代码.

Community
---------

* [/r/Common_Lisp](https://www.reddit.com/r/Common_Lisp/) - 关于 Common Lisp 的 subreddit
* [/r/learnlisp](https://www.reddit.com/r/learnlisp/) - 一个用于提问和获取 Lisp 帮助的 subreddit
* [common-lisp.net](https://common-lisp.net)
* [lisp-lang.org](https://lisp-lang.org/)
* [Lisp Discord Server](https://discord.gg/hhk46CE)
* [#commonlisp](https://irclog.tymoon.eu/libera/%23commonlisp) 在 Libera Chat - 主要 Common Lisp IRC 频道.
* [#lisp](https://irclog.tymoon.eu/libera/%23lisp) on Libera Chat - 所有 Lisp 方言的 IRC 频道.
* #clschool on Libera Chat - IRC channel for learning Common Lisp.
* #lispcafe on Libera Chat - IRC channel for off-topic discussions.
* [Common Lisp chat](https://chat.hexstreamsoft.com/) - Keybase 团队具有明确定义的规则和保留策略.

图书馆经理
===============

 * :star: [Quicklisp][16] - 一个包含许多库的库管理器，具有简单的依赖管理.  [外籍人士][14].
* [CLPM](https://gitlab.common-lisp.net/clpm/clpm)  - Common Lisp 的包管理器，它努力将包管理器进程本身与使用它的客户端映像彻底分开.  [BSD_2 条款][17].
* [Ultralisp](http://ultralisp.org/)  - Quicklisp 发行版，每 5 分钟更新一次，可以一键添加项目.  [BSD] [15].
* [Roswell](https://github.com/roswell/roswell)  - Lisp 实现安装程序、脚本启动程序等.  [麻省理工学院][200].
* [Qlot](https://github.com/fukamachi/qlot)  - 项目本地库安装程序，类似于 Bundler 或 Carton.  [外籍人士][14].
* [Quicksys](https://lisp.com.br/quicksys/)  - 从多个 Quicklisp 发行版安装系统.  [麻省理工学院][200].
* [Quickutil](https://github.com/tarballs-are-good/quickutil)  - 实用程序管理器，类似于 Quicklisp，但适用于小型实用程序而不是整个库.  [3 条款 BSD][15].

可能有帮助：

* [quick-patch](https://github.com/tdrhq/quick-patch/)  - 无需使用 git 子模块即可轻松覆盖 quicklisp 项目.  MPL-2.0.
* [print-licenses](https://github.com/vindarel/print-licenses)  - 打印项目及其依赖项使用的许可证.  [麻省理工学院][200].

### Interfaces to other package managers

* [linux-packaging](https://gitlab.com/ralt/linux-packaging)  - 使用单个 ASDF 声明为您的应用程序构建 .deb、.rpm 或 .pkg 包. 在引擎盖下使用 fpm.  [麻省理工学院][200].
* [qldeb](https://github.com/ralt/qldeb) - Quicklisp 系统到 debian 软件包，以及 [deb-packager](https://github.com/ralt/deb-packager) （只需通过定义一个 s 表达式来创建一个 debian 包）和一个介绍 [blog post](http://margaine.com/2015/12/22/quicklisp-packagecloud-debian-packages.html) . 两者 [麻省理工学院] [200].
* [ql-to-deb](https://github.com/dimitri/ql-to-deb)  - 从 Quicklisp 版本更新 cl-* debian 包.  WTFPL.
* [dh-quicklisp-buildapp](https://github.com/ralt/dh-quicklisp-buildapp)  - debhelper 实用程序，可让您几乎毫不费力地将基于 quicklisp 的 Common Lisp 代码编译为 .deb 中的 buildapp 二进制文件.  [麻省理工学院][200].
* [cl-brewer](https://github.com/can3p/cl-brewer)  - 用于（命令行）常见 lisp 应用程序的自制公式生成器. 公共区域.
* [flatpack-common-lisp](https://gitlab.com/ralph-schleicher/flatpak-common-lisp) - 一个 BuildStream 项目，用于为 Common Lisp 应用程序构建基于 Flatpak 的运行时环境.


也可以看看 [asdf-sbcl](https://github.com/smashedtoatoms/asdf-sbcl)，通用包管理器的插件.


机器学习
================

* [clml](https://github.com/mmaul/clml)  - 最初由日本公司 Mathematicl Systems Inc. 开发. 用一个 [tutorial](https://mmaul.github.io/clml.tutorials//2015/08/08/CLML-Time-Series-Part-1.html) .  [LLGPL] [8].
* [mgl](https://github.com/melisgl/mgl) - 由其使用 [author](https://github.com/melisgl) 到 [win](https://github.com/melisgl/higgsml) 希格斯玻色子机器学习挑战.  [麻省理工学院][200].
* [antik](https://www.common-lisp.net/project/antik/)  - Common Lisp 中科学和工程计算的基础. 通用公共许可证. 还 [mgl-mat](https://github.com/melisgl/mgl-mat) 和 [LLA](https://github.com/tpapp/lla).

Credit: [borretti.me' state of CL ecosystem 2015](http://borretti.me/article/common-lisp-sotu-2015#machine-learning).


自然语言处理
===========================

* [cl-nlp](https://github.com/vseloved/cl-nlp)  - 自然语言处理工具集.  [Apache2.0][89].
* [babel2](https://github.com/lucas8/Babel2/) - 流体构造语法实现、计算框架和基于统一的语法形式[Apache2.0][89].
* [sparser](https://github.com/ddmcdonald/sparser)  - 英语的自然语言理解系统.  [日食][209].



网络和互联网
====================

See [Cliki](http://www.cliki.net/Web) for more.

HTTP 客户端
------------
*  [Dexador](https://github.com/fukamachi/dexador)  - 一个 HTTP 客户端，旨在取代 Drakma.  [麻省理工学院][200].
* [Carrier](https://github.com/orthecreedence/carrier)  - 构建在 cl-async 和 fast-http 之上的轻量级异步 HTTP 客户端.  [麻省理工学院][200].
* [fast-http](https://github.com/fukamachi/fast-http)  - Common Lisp 的快速 HTTP 请求/响应解析器.  [麻省理工学院][200].


HTTP 服务器
------------
* [Clack](https://github.com/fukamachi/clack)  - 受 Rack 和 WSGI 启发的 Web 应用程序环境.  [LLGPL] [8]. 为选择的网络服务器提供统一的界面（默认为 Hunchentoot）. 随着更多 [getting started guide](https://jasom.github.io/clack-tutorial/posts/getting-started-with-clack/).
* ：星星： [Hunchentoot](http://weitz.de/hunchentoot/)  - 网络服务器.  [2 条款 BSD][207]
* [zaserve](https://github.com/gendl/aserve) - 由 Franz Inc. [LLGPL][8] 提供的 AllegroServe 的便携式分叉.
* [wookie](https://github.com/orthecreedence/wookie)  - 异步 HTTP 服务器.  [外籍人士][14].
* [woo](https://github.com/fukamachi/woo)  - 基于 libev 的快速非阻塞 HTTP 服务器.  [麻省理工学院][200].
* [cl-http2-protocol](https://github.com/akamai/cl-http2-protocol)  - 草案 14 中 HTTP/2 协议的纯 Common Lisp 传输不可知实现.  [麻省理工学院][200].

### Hunchentoot plugins

*  [easy-routes](https://github.com/mmontone/easy-routes)  - 在 Hunchentoot 之上的路线处理系统. 它支持基于 HTTP 方法的调度、从 url 路径提取参数、装饰器、从路由名称生成 url 等.[MIT][200].
* [hunchentoot-cgi](https://github.com/slyrus/hunchentoot-cgi)  - 用于从 hunchentoot 网络服务器执行 CGI 脚本的库.  [BSD] [207].
* [hunchentoot-multi-acceptor](https://github.com/moderninterpreters/hunchentoot-multi-acceptor/)  - 使用单个端口在单个 hunchentoot 接受器上路由多个域（虚拟主机）.  [Apache2.0][89].
* [hunchentoot-auth](https://github.com/slyrus/hunchentoot-auth)  - 使用密码实现用户身份验证.  [BSD] [207].
* [hunchentoot-errors](https://github.com/mmontone/hunchentoot-errors)  - 使用请求和会话信息增强 Hunchentoot 错误页面和日志.  [麻省理工学院][200].

### Clack plugins

* [clack-errors](https://github.com/eudoxia0/clack-errors)  - Clack 的错误页面中间件.  [LLGPL] [8].
* [clath](https://github.com/BnMcGn/clath) - 单点登录
   Clack 的中间件. 它允许使用 OAuth1.0a、OAuth2 进行基本登录
  和 OpenID. 在撰写本文时，它支持来自
  谷歌、推特、LinkedIn、StackExchange、Reddit 和 Github.  [Apache2.0][89].
* [clack-pretend](https://github.com/BnMcGn/clack-pretend) - 测试
  和 clack 的调试工具.  [Apache2.0][89].
* [hermetic](https://github.com/eudoxia0/hermetic)  - 基于 Clack 的 Web 应用程序的安全性.  [外籍人士][14].
* [live-reload](https://github.com/knobo/live-reload)  - 实时重新加载克拉克原型.  [LLGPL] [8].
* [clack-static-asset-middleware](https://github.com/fisxoj/clack-static-asset-middleware)  - 用于时钟的缓存破坏静态资产中间件.  [麻省理工学院][200].

网络框架
--------------

* [Caveman](https://github.com/fukamachi/caveman)  - 强大的网络框架.  [LLGPL] [8].
  示例项目： [Quickdocs](https://github.com/quickdocs)
* [hh-web](https://github.com/hargettp/hh-web)  - 构建现代网络应用程序的框架.  [外籍人士][14].
* [ningle](https://github.com/fukamachi/ningle)  - 超微网络框架.  [LLGPL] [8]. [ninglex](https://github.com/defunkydrummer/ninglex) ，一个扩展的和 noob-friendly ningle（主要是更容易处理查询参数）.  [麻省理工学院][200].
* [radiance](https://github.com/Shirakumo/radiance)  - Web 应用程序环境和框架.  [艺术许可 2.0][51].
* [Lucerne](https://github.com/eudoxia0/lucerne)  - 受 Flask 启发，基于 Clack 构建的最小 Web 框架.  [麻省理工学院][200].
* [Snooze](https://github.com/joaotavora/snooze)  - 一个 RESTful 网络框架.  Web 服务器不可知. 目前支持 Hunchentoot 和 Clack. 路由只是函数，HTTP 条件只是 Lisp 条件.  [LLGPL] [8].

以 REST 为中心的框架：

* [cl-rest-server](https://github.com/mmontone/cl-rest-server)  - 用于编写 REST Web API 的库. 具有模式验证、日志注释、缓存、权限或身份验证、Swagger 文档等功能.[MIT][200].
* [cl-odata-client](https://github.com/copyleft/cl-odata-client) - 用于访问的 Common Lisp 客户端库 [OData services](https://www.odata.org) .  [麻省理工学院] [200].


有更多的项目，或多或少已停产，但很有趣. 查看其他资源.

同构网络框架
-------------------------

* [CLOG](https://github.com/rabbibotton/clog)  - Common Lisp Omnificent GUI. 使用 Web 技术为本地或远程应用程序生成图形用户界面.  [BSD_3 条款][15].
  - CLOG 基于 GNOGA 的思想，GNOGA 是作者为 Ada 编写的框架，自 2013 年起用于商业生产代码.
* [Interactive SSR](https://github.com/interactive-ssr/client/blob/master/main.org/)  - ISSR 允许您在不编写客户端脚本的情况下制作交互式网页. 不需要有关 Javascript 或 DOM 的知识.
  - 它与 Phoenix LiveView 或 Hotwire 不同.
* [Weblocks](https://github.com/40ants/weblocks)  - 基于小部件的框架，具有“解决 JavaScript 问题”的内置 ajax 更新机制.  [LLGPL] [8].


资产管理
-----------------

* [Rock](https://github.com/eudoxia0/rock) - 资产管理人
  通用 Lisp. 它基本上是 Bower 和
  网络资产.  [麻省理工学院] [200].


解析html
------------
 * [Plump][71] - 一个宽松的 HTML/XML 解析器，可以容忍格式错误的标记.  [zlib] [33]. 最好与 [lquery][72] 和 [clss](https://github.com/Shinmera/CLSS).

查询 HTML/DOM
-----------------
 * [lquery][72] - 一个类似 jQuery 的 HTML/DOM 操作库.  [艺术许可 2.0][51].

另请参阅下面的 XML 部分以了解 xpath 库等.


HTML 生成器和模板
-----------------------------
*  [spinneret](https://github.com/ruricolist/spinneret)  - Common Lisp HTML5 生成器.  [外籍人士][14].
* ：星星： [cl-who](http://weitz.de/cl-who/)  - 古老的 HTML 生成器.  [FreeBSD] [39].
* ：星星： [Djula](https://github.com/mmontone/djula)  - Django 模板引擎到 Common Lisp 的端口.  [外籍人士][14].
* [eco](https://github.com/eudoxia0/eco)  - 快速、灵活、对设计师友好的模板引擎.  [外籍人士][14].
* [TEN](https://github.com/mmontone/ten)  - Djula 的完整性满足 Eco 的可用性.  [麻省理工学院][200].
* [cl-closure-template](https://github.com/archimag/cl-closure-template)  - 实施 Google 的 Closure 模板.  [LLGPL] [8].
* [flute](https://github.com/ailisp/flute)  - 一个易于组合的 HTML5 生成库，具有最简单的语法.  [麻省理工学院][200].
* [clip](https://shinmera.github.io/clip)  - 一个 HTML 模板处理器，其中模板是用 HTML 编写的.  [zlib] [33].
* [lsx](https://github.com/fukamachi/lsx/) 和 [markup](https://github.com/moderninterpreters/markup)  - 两个类似 JSX 的模板引擎，其中 HTML 标签是 Common Lisp 代码.  `markup` 带有一个 Emacs 包.

URI 处理
------------

* [quri](https://github.com/fukamachi/quri) - 另一个 URI 库
  通用 Lisp. 支持用户信息、IPv6 主机名、编码/解码
  实用程序，... [BSD_3Clause][15].
* [cl-slug](https://github.com/EuAndreh/cl-slug)  - 一个用于制作 slug 的小型库，主要用于 URI，在 CamelCase 中进行转换，删除重音和标点符号，用于英语和超越.  [LLGPL] [8].

Javascript
----------

* ：星星： [Parenscript](https://common-lisp.net/project/parenscript/)  - 从 Common Lisp 到 Javascript 的翻译器.  [3 条款 BSD][15]. 看 [Trident-mode](https://github.com/johnmastro/trident-mode.el)，一种 Emacs 模式，提供与浏览器的实时交互.[unlicence][5].
  * [paren6](https://github.com/BnMcGn/paren6/) - 一组用于 Parenscript 的 ES6 宏.
* [parse-js](http://marijnhaverbeke.nl/parse-js/) - 用于解析 ECMAScript 3 的包.[zlib][33].
* [JSCL](https://github.com/jscl-project/jscl)  - 从一开始就设计为自托管的 CL-to-JS 编译器. 缺少 CLOS、格式和循环.
* [CL-JavaScript](http://marijnhaverbeke.nl/cl-javascript/)  - 从 Javascript 到 Common Lisp 的翻译器. 在 Quicklisp 上不可用.  [外籍人士][14].
* [Wuwei](https://github.com/mtravers/wuwei/)  - 用于构建基于 Ajax 的网页的工具包.  [麻省理工学院][200].
* [SmackJack](https://github.com/aarvid/SmackJack)  - 使用 parenscript 生成 javascript 和 hunchentoot（目前）作为 Web 服务器的 Ajax Common Lisp 库. 还允许服务器端 lisp 函数调用客户端 parenscript 一个.  [麻省理工学院][200].
* [Panic](https://github.com/michaeljforster/panic) ，一个 React 的 Parenscript 库. 不在 Quicklisp 中.  [麻省理工学院][200]. 它 [TodoMVC example](https://github.com/40ants/todomvc/blob/common-lisp-example/examples/common-lisp-react/src/app.lisp).
* [remote-js](https://github.com/ceramic/remote-js)  - 将 JavaScript 从 Common Lisp 发送到浏览器.  [麻省理工学院][200].
* [sigil](https://github.com/BnMcGn/sigil) - 家长
 Javascript 命令行编译器和 REPL.  [麻省理工学院][200].

也可以看看
[trident-mode](https://github.com/johnmastro/trident-mode.el)，一个 Emacs
实时 Parenscript 交互的次要模式.


Email
-----

* [trivial-imap](https://github.com/40ants/trivial-imap)  - 尝试简化使用 IMAP 服务器的一些常见情况，例如从服务器读取电子邮件. 邮局图书馆的薄包装（它是 Franz 的 cl-imap 的一个分支）.  [BSD] [15].
* [mailgun](https://github.com/40ants/mailgun)  - 通过 mailgun.com 发布 HTML 电子邮件的薄包装器.  [未授权][5].
* [mito-email-auth](https://github.com/40ants/mito-email-auth) - 帮助通过电子邮件向网站用户发送唯一代码来验证他们的身份.


Websockets
----------

*  [usocket](https://github.com/usocket/usocket)  - 一个可移植的 TCP 和 UDP 套接字接口.  [外籍人士][14].
* [websocket-driver](https://github.com/fukamachi/websocket-driver) - a WebSocket server/client implementation, backend agnostic (Clack). [3-clause BSD][15].
* [Portal](https://github.com/charJe/portal)  - 使用 usocket 用于 Common Lisp 的便携式 websocket.  [LLGPL] [8].

查看更多 [on cliki](http://www.cliki.net/site/search?query=websockets).

静态站点生成器
----------------------

* [coleslaw](https://github.com/kingcons/coleslaw) 和它
  [coleslaw-cli](https://github.com/40ants/coleslaw-cli) - 灵活
   Lisp 博客软件类似于 Frog、Jekyll 或 Hakyll.  [BSD] [15].

Deployment
----------

* [heroku-buildpack-common-lisp](https://gitlab.com/duncan-bayne/heroku-buildpack-common-lisp)  - 使用 Roswell 编译 Common Lisp 应用程序的 Heroku buildpack.  LGPL3.
* [cube](https://github.com/xh4/cube)  - 根据 Swagger 规范生成的 Common LISP 的 Kubernetes 客户端库.  [麻省理工学院][200].
* [s2i-lisp](https://github.com/container-lisp/s2i-lisp)  - 基于 CentOS 或 RHEL7 的源到映像构建器映像，用于为 OpenShift（以及 Docker）构建通用 LISP 映像. 它具有带有 Quicklisp 安装、SLIME 或 SLY 集成的最新 SBCL，并允许通过环境变量进行自定义.  [Apache2][89]
* [deploy](https://shinmera.github.io/deploy)  - 用于 Lisp 应用程序二进制部署的工具包，额外支持外部共享库.  [zlib] [33].
* [cl-aws-runtime-test](https://github.com/y2q-actionman/cl-aws-custom-runtime-test)  - 在 AWS lambda 上使用 Common Lisp (SBCL) 作为自定义运行时的示例.  WTFPL.

也可以看看：

- [Heliohost](https://www.heliohost.org/) 免费托管解决方案.
- [Platform.sh](https://platform.sh/blog/2019/lisp/) 有 Common Lisp 支持.

Monitoring
----------

* [prometheus.cl](https://github.com/deadtrickster/prometheus.cl) - Prometheus.io client. Grafana dashboard for SBCL and Hunchentoot metrics (memory, threads, requests per second,…). [MIT][200].
* [cl-sentry-client](https://github.com/mmontone/cl-sentry-client)  - 基于云的错误监控系统 Common Lisp 的 Sentry 客户端.  [麻省理工学院][200].
* [rollbar.lisp](https://github.com/adventuring/rollbar.lisp) - 接口 [Rollbar.com](https://rollbar.com/)，一个错误跟踪软件.


第三方 API
----------------

* [Aws-sign4](https://github.com/rotatef/aws-sign4) - Amazon Web Services 签名版本 4 的 Common Lisp 库.[GNU GPL3][2].
* [zs3](https://github.com/xach/zs3) - 用于使用 Amazon Simple Storage 的库
服务 (S3) 和 CloudFront 服务.  [BSD] [15].
* [cl-ses](https://github.com/CodyReichert/cl-ses/)  - AWS SES 库.  [外籍人士][14].
* [north](https://shinmera.github.io/north)  - South (Simple OaUTH) 库的继承者，在客户端和服务器端都实现了完整的 oAuth 1.0a 协议. 使用 North，您可以轻松成为 oAuth 提供者或消费者.  [zlib] [33].
* [avatar-api](https://github.com/eudoxia0/avatar-api)  - 从 Google+、Gravatar 和其他人获取头像.  [外籍人士][14].
* [chirp](https://github.com/Shinmera/chirp)  - Twitter 客户端库.  [zlib] [33].
* [tooter](https://github.com/Shinmera/tooter)  - 为 Mastodon 实现完整 v1 REST API 协议的客户端库.  [zlib] [33].
* [cl-irc](https://www.common-lisp.net/project/cl-irc/)  - IRC 客户端库.  [外籍人士][14].
* [cl-mediawiki](https://github.com/AccelerationNet/cl-mediawiki)  - MediaWiki api 的包装器.  [麻省理工学院][200].
* [cl-openid](https://github.com/cl-openid/cl-openid)  - OpenID 的实现.  [LLGPL] [8].
* [cl-pushover](https://github.com/TeMPOraL/cl-pushover)  - 普通 Lisp 绑定到 Pushover.  [麻省理工学院][200].
* [humbler](https://github.com/Shinmera/humbler)  - Tumblr API 接口.  [zlib] [33].
* [multiposter](https://github.com/Shinmera/multiposter)  - 同时发布到多个服务.  [zlib] [33].
* [stripe](https://git.mfiano.net/mfiano/stripe)  - Stripe 支付系统的客户端.  [麻省理工学院][200].

Web 项目骨架和生成器
------------------------------------

* [cl-cookieweb](https://github.com/vindarel/cl-cookieweb)  - 用于启动 Web 项目的 Cookiecutter 模板.  [BSD_3 条款][15]. 不在 Quicklisp 中.
  * 提供带有 Hunchentoot Web 服务器、easy-routes、Djula 模板、基于 SQLite 的 Bulma 样式、迁移、示例表定义和使用 FiveAM 的测试套件的工作玩具 Web 应用程序.
* [make-like](https://github.com/container-lisp/make-like)  - LIKE (Lisp In Kubernetes + Emacs) 应用程序的应用程序模板构建器.  [Apache2.0][51].
  * Makefile、podman 支持、GitHub Actions、Prometheus 指标支持、TOML 风格的 config.ini、预先配置了健康检查的 easy-route 等等.
* [cl-webapp-seed](https://github.com/rajasegar/cl-webapp-seed)  - 一个简单的 Web 应用程序样板. 使用 Hunchentoot，cl-who，可轻松部署到 Heroku.  [麻省理工学院][200].


Others
------

*  [cl-forms](https://github.com/mmontone/cl-forms)  - Common lisp 的 Web 表单处理库.  [麻省理工学院][200].
* [maiden](https://shirakumo.github.io/maiden)  - 支持 IRC 等的机器人和聊天系统框架.  [艺术许可 2.0][51].
* [css-lite](https://github.com/paddymul/css-lite)  - CSS 语法.  [外籍人士][14].
* [find-port](https://github.com/eudoxia0/find-port)  - 以编程方式查找开放端口.  [麻省理工学院][200].
* [Postmaster](https://github.com/eudoxia0/postmaster)  - 一个简单易用的 SMTP/IMAP 库.  [外籍人士][14].
* [cl-selenium-webdriver](https://github.com/TatriX/cl-selenium-webdriver/) - Selenium 2.0 的绑定库.
* [cl-wget](https://github.com/cl-wget/cl-wget)  - 使检索大文件或镜像整个网站变得容易.  [AGPL-3.0] [51].
* [trivial-download](https://github.com/eudoxia0/trivial-download)  - 下载文件.  [麻省理工学院] [200].

数值和科学
========================

* [numcl](https://github.com/numcl/numcl)  - Common Lisp 中的 Numpy 克隆.  [LGPL3][9].
* [GSLL](https://common-lisp.net/project/gsll/)  - Lisp 的 GNU 科学图书馆； 允许使用来自 Common Lisp 的 GSL.  [GNU LGPL2.1][11].
* [maxima](http://maxima.sourceforge.net/)  - 计算机代数系统. 在 Quicklisp 上不可用.  [GNU GPL3][2].
* [Xecto](https://github.com/pkhuong/Xecto)  - 用于常规数组并行性的库.  [3 条款 BSD][15].
* [Petalisp](https://github.com/marcoheisig/Petalisp) - 试图
  为并行计算机生成高性能代码
   JIT 编译数组定义. 它适用于更多
  比 NumPy 更基础，提供更强大
  N 维数组，但只是一些用于处理的构建块
  他们.  [AGPL-3.0][agpl3].
* [cl-ana](https://github.com/ghollisjr/cl-ana)  - Common Lisp 数据分析库，强调模块化和概念清晰度. 它旨在成为分析小型和大型数据集的通用框架，包括分箱数据分析和可视化.  [GNU GPL3][2].
* [linear-programming](https://neil-lindquist.github.io/linear-programming/)  – 用于解决线性规划问题的库.  [麻省理工学院][200].
* [avm](https://github.com/takagi/avm)  - 高效且富有表现力的数组矢量数学库，具有多线程和 CUDA 支持.  [麻省理工学院][200].
* [array-operations](https://github.com/bendudson/array-operations)  - 一组用于操作 Common Lisp 数组并使用它们执行数值计算的函数和宏.  [麻省理工学院][200].
* [cl-geometry](https://github.com/Ramarren/cl-geometry/)  - Common Lisp 的二维计算几何系统.  [麻省理工学院][200].
* [Vellum](https://github.com/sirherrbatka/vellum)  - Common Lisp 的数据帧.  BSD_2 条款.
* [rtg-math](https://github.com/cbaggers/rtg-math/)  - 选择在 lisp 中制作实时图形最常用的数学例程（2、3 和 4 分量向量、3x3 和 4x4 矩阵、四元数、球坐标和极坐标）.  BSD_2 条款.

矩阵库
----------------

* [magicl](https://github.com/rigetticomputing/magicl)  - 基于 BLAS/LAPACK 和 Expokit 的 Common Lisp 中的矩阵代数程序，由 Rigetti Computing 提供.  [BSD_3 条款][15].
* [lisp-matrix](https://github.com/blindglobe/lisp-matrix)  - 矩阵包.  [FreeBSD] [39].
* [3d-matrices](https://shinmera.github.io/3d-matrices)  - 一个实现常见矩阵计算的库，重点是图形中常用的 2x2、3x3 和 4x4 矩阵. 它也提供了一些数值函数，但这些不是重点. 该库进行了大量优化，因此它不是由漂亮的代码组成的.  [zlib] [33].
* [clem](https://github.com/slyrus/clem)  - 矩阵库.  [BSD_2 条款][17].

Statistics
---------

* [lisp-stat](https://github.com/lisp-stat)  - 用于统计计算的环境，在概念上类似于 R，也适用于前线生产部署.  “它源于对快速构建分析和人工智能解决方案原型的环境的渴望，并以最小的摩擦直接转移到生产环境.”
  * https://lisp-stat.dev/
  * 运送卢克·蒂尔尼 (Luke Tierney) [XLisp-Stat](https://homepage.stat.uiowa.edu/~luke/xls/xlsinfo/) （R 的前身）以及更新的库.
* [common-lisp-stat](https://github.com/blindglobe/common-lisp-stat/)  - Common Lisp 统计库.  [FreeBSD] [39].

Units
-----

* [physical-quantities](https://github.com/mrossini-ethz/physical-quantities)  - 一个库，为具有自动错误传播的计算提供具有可选单位和/或不确定性的数字类型.  GPL2

Utils
-----

* [cmu-infix](https://github.com/rigetti/cmu-infix)  - 在 Common Lisp 中编写中缀数学符号的库. 也可以看看 [polisher](https://github.com/mrcdr/polisher).


并行和并发
===========================

* ：星星： [BordeauxThreads](https://common-lisp.net/project/bordeaux-threads/)  - 可移植的共享状态并发.  [外籍人士][14].
* ：星星： [lparallel](https://github.com/lmj/lparallel)  - 用于并行编程的库.  [3 条款 BSD][15].
* [lfarm](https://github.com/lmj/lfarm)  - 跨机器分配工作（在 lparallel 和 usocket 之上）.  [BSD_3Clause][15]
* [calispel](https://github.com/hawkir/calispel) - [CSP](https://en.wikipedia.org/wiki/Communicating_sequential_processes) - 类似于普通 lisp 的通道. 具有阻塞、可选缓冲通道和“CSP 选择”语句.  ISC 风格.
   - “它完整、灵活且易于使用.相比 Lparallel 和 ChanL，我更推荐 Calispel.”  @安布雷瓦. [discussion](https://github.com/CodyReichert/awesome-cl/issues/290)
* [chanl](https://github.com/zkat/chanl)  - 可移植的、基于通道的并发.  [Expat][14]，部分在 [3-clause BSD][15] 下.
* [cl-async](https://github.com/orthecreedence/cl-async)  - 用于通用非阻塞编程的库.  [外籍人士][14].
* [Moira](https://github.com/TBRSS/moira)  - 监控并重启后台线程.  In-lisp 流程主管.  [麻省理工学院][200].
* [trivial-monitored-thread](https://gitlab.com/ediethelm/trivial-monitored-thread) -
  一个 Common Lisp 库，提供了一种产生线程的方式并被
  当其中任何一个崩溃和死亡时通知.  [麻省理工学院][200].
* [cl-gearman](https://github.com/taksatou/cl-gearman) - 一个图书馆 [Gearman](http://gearman.org/) 分布式作业系统.  [LLGPL] [8].
* [swank-crew](https://github.com/brown/swank-crew)  - 使用 Swank 客户端实现的分布式计算框架.  [BSD_3 条款][15].
* [cl-coroutine](https://github.com/takagi/cl-coroutine)  - 一个协程库. 它在其实现中使用了 CL-CONT 延续库.  [麻省理工学院][200].
* [STMX](https://github.com/cosmos72/stmx)  - Common Lisp 的高性能事务内存.  [LLGPL] [8].

也可以看看：

* [cl-etcd](https://github.com/atgreen/cl-etcd) - 将 etcd 作为异步次等进程运行.  [etcd](https://etcd.io/) 是一个高度一致的分布式键值存储.  [AGPL-3.0][agpl3].

演员模式
--------------

*  [cl-gserver](https://github.com/mdbergmann/cl-gserver)  - 受 Erlang 启发的 GenServer. 它旨在封装状态，但也用于执行异步操作. 还有演员. 有关状态的功能与 Clojure 的 Agent 或 cl-actors 并无不同.  [麻省理工学院][200].
* [erlangen](https://github.com/eugeneia/erlangen)  - Clozure Common Lisp 的分布式异步消息传递系统.  [GNU GPL3][2].
* [Actors](https://github.com/aarvid/Actors) LispWorks 的包（[announce](https://www.reddit.com/r/Common_Lisp/comments/77vsft/david_mcclains_actors_package_for_lispworks/)) [与] [200].
* [common-lisp-actors](https://github.com/naveensundarg/Common-Lisp-Actors)  - 一个简单易用的演员系统.  [BSD_2 条款][17].
* [memento-mori](https://github.com/zkat/memento-mori) - 一个用于编写健壮的、基于角色的系统的库. 它从 Erlang/OTP 中汲取灵感，特别是其对高可用性系统的崩溃优先方法以及 Akka.  [麻省理工学院][200].


事件处理
----------------

* [simple-tasks](https://github.com/Shinmera/simple-tasks)  - 一个非常简单的任务调度框架.  [zlib] [33].
* [deeds](https://github.com/Shinmera/deeds)  - Deeds 是一个可扩展的事件传递系统. 它允许使用复杂的事件过滤系统将事件高效地传递给多个处理程序.  [zlib] [33].
* [cl-flow](https://github.com/borodust/cl-flow/)  - 用于非阻塞并发 Common Lisp 的数据流计算树库.  [麻省理工学院][200].
* [event-glue](https://github.com/orthecreedence/event-glue)  - 简单的事件抽象. 没有依赖性. 它可以在您需要通用事件处理系统的任何地方使用.  [麻省理工学院][200].


作业处理
--------------


* [SBCL's timers](http://www.sbcl.org/manual/#Timers)，系统范围的事件调度程序.
* [psychiq](https://github.com/fukamachi/psychiq)  - 用于 Common Lisp 应用程序的基于 redis 的后台作业处理. 受 Ruby 的 Sidekiq 启发并与其 Web UI 兼容.  [LLGPL] [8].
* [cl-cron](https://github.com/ciel-lang/cl-cron)  - 一个简单的工具，提供类似 cron 的设施.  [GPL3][2].
* [clerk](https://github.com/tsikov/clerk)  - 一个类似 cron 的调度程序，具有健全的 DSL.  [麻省理工学院][200].


Regex
=====

* ：星星： [cl-ppcre](http://weitz.de/cl-ppcre/)  - 可移植的、与 Perl 兼容的正则表达式.  [FreeBSD] [39].
* [one-more-re-nightmare](https://github.com/no-defun-allowed/one-more-re-nightmare)  - Common Lisp 中的快速正则表达式编译器.  [BSD_2 条款][17].


Scripting
=========

编写、运行脚本
------------------------

*  [Roswell](https://github.com/roswell/roswell#scripting-with-roswell) -
  一个 lisp 安装程序和脚本环境（帮助程序、启动程序、
  安装程序）等.  [麻省理工学院][200].
* [cl-all](https://github.com/shinmera/cl-all)  - 在多个实现中运行 Lisp 片段的脚本. 这使您可以快速比较实现行为和差异.  [zlib] [33].
* [clawk](https://github.com/sharplispers/clawk)  - 嵌入到 Common Lisp 中的 AWK 实现，用于搜索文件中的行并对其字段执行指定的操作.  BSD 风格.
* [ScriptL](https://github.com/rpav/ScriptL)  - Shell 脚本编写类似于 Lisp！ 或者，实时编码远程函数调用 shell. 在 REPL 中编写一个命令，并立即在 shell 中运行它.  [LLGPL] [8].
  * 类似，也许更简单： [lserver](https://notabug.org/quasus/lserver/)

命令行选项解析器
----------------------------

*  [Unix-opts](https://github.com/libre-man/unix-opts) - 一个命令行
  带有简明选项声明的选项解析器.  [麻省理工学院][200].
* [Adopt](https://github.com/sjl/adopt/)  - 该死的 OPTion 解析库.  [麻省理工学院][200].
* [Clingon](https://github.com/dnaeon/clingon) - 丰富的命令行选项解析器系统.
  * 更新，它可能拥有最丰富的功能集：子命令、生成 bash 完成、支持各种选项（整数、布尔值、计数器、枚举……），可扩展……


Readline、ncurses 和其他图形助手
--------------------------------------------

* [cl-readline](https://github.com/vindarel/cl-readline) - 一套
  在输入时编辑行的功能，以维护一个列表
  以前输入的命令行，调用和重新编辑它们和
  执行类似 csh 的历史扩展.  Emacs 和 vi 编辑
  模式.  [GPL3][2].
* [Linedit](https://common-lisp.net/project/linedit) - 阅读风格
  提供可定制行编辑的库
  特征.  [MIT 风格] [210].
* [cl-charms](https://github.com/HiTECNOLOGYs/cl-charms) - 一个
   Common Lisp 中`libcurses` 的接口. 它提供了一个原始的，
  通过 CFFI 到 libcurses 的低级接口，以及更高级别的接口
   lispier 界面.  [麻省理工学院] [200].
* [replic](https://github.com/vindarel/replic/)  - 将现有代码转换为 readline 应用程序的助手，重点是定义命令参数的完成. 还提供了一个随时可用的可执行文件，它将用户的 lispy init 文件转换为 readline 命令.  [麻省理工学院][200].
* [cl-ansi-term](https://github.com/vindarel/cl-ansi-term) - 打印
  彩色文本、水平线、进度条、（无）有序列表
  和 ANSI 兼容终端上的表格.  [GPL3][2].
* [cl-progress-bar](https://github.com/sirherrbatka/cl-progress-bar/)  - 进度条，就像在 Quicklisp 中一样！  [麻省理工学院][200].

壳、壳接口
-------------------------

* [Lish](https://github.com/nibbula/lish)  - `lish` 可能有一天会成为一个 lisp shell.  [GPL3][2].
  * 支持路径和 Lisp 符号中的可执行文件的制表符补全，允许编写和混合 shell 命令和 Lisp 代码，具有小型 REPL 和交互式调试器等.
* [shcl](https://github.com/bradleyjensen/shcl)  - Common Lisp 中类似 POSIX 的 shell.  [Apache2.0][89].
* [Shelly](https://github.com/fukamachi/shelly) - 执行 Common Lisp
  功能类似于shell命令，无需编写命令
  行参数解析器. 它也可以用作Make-like
  构建工具.  [FreeBSD] [39].
* [cmd](https://github.com/ruricolist/cmd)  - 用于运行外部程序的实用程序. 防止外壳插值，考虑到多线程程序构建，Windows 支持.  [麻省理工学院][200].
   * `uiop:run-program`（同步）和 `uiop:launch-program`（异步）随 ASDF 一起提供，可用于所有现代实现. 见 [CL Cookbook: running external programs](https://lispcookbook.github.io/cl-cookbook/os.html#running-external-programs).
* [Clesh](https://github.com/Neronus/Clesh)  - 扩展 Common Lisp 以类似于 perl 的反引号的方式嵌入 shell 代码.  [FreeBSD] [39].

系统管理
---------------------

* [Consfigurator](https://spwhitton.name/tech/code/consfigurator/)  - Lisp 声明式配置管理系统. 您可以使用它以 root 用户身份配置主机、以非特权用户身份部署服务、构建和部署容器以及生成磁盘映像.  [GPL3][2].
* [Adams](https://github.com/cl-adams/adams)  - Common Lisp 中的 UNIX 系统管理. 与 Ansible、Chef 或 Puppet 不同.  [国际标准委员会][22].

其他脚本工具
-------------------------

* [WCL](https://github.com/wadehennessey/wcl) [陈旧] - 允许数百个 Lisp
应用程序立即可用，同时允许
其中几个同时运行.  WCL 通过
提供 Common Lisp 作为可以链接的 Unix 共享库
 Lisp 和 C 代码来生成高效的应用程序. 例如，
规范`Hello World!` 的 Lisp 版本的可执行文件
程序在 32 位 x86 Linux 上只需要 20k 字节.  WCL也
支持完整的开发环境，包括动态文件
加载和调试. 使用 GDB 的修改版本来调试 WCL
程序，提供对混合语言调试的支持.


文本编辑器资源
=====================

这包含各种文本编辑器的插件和其他好东西.

* [Parinfer](https://shaunlebron.github.io/parinfer/)  - Parinfer 是一种编辑 lisp 代码的方法，有助于保持缩进和括号平衡. 它很容易开始，但它提供了 Paredit 的高级功能. 它可在许多编辑器（Emacs、Vim、Neovim、Atom、Sublime Text、Visual Studio Code、LightTable、CodeMirror 等）上使用.

## Emacs ##

* ：星星： [Slime](https://github.com/slime/slime)  - Emacs 的高级 Lisp 交互模式；  Emacs 内部的 Common Lisp 的成熟环境. 公共区域.
*  [Sly](https://github.com/joaotavora/sly) - SLY 是 SLIME 的一个分支，并对其进行了多项改进.
*  [Portacle](https://shinmera.github.io/portacle/) - 一个可移植的多平台 Common Lisp 环境：SBCL、Quicklisp、Emacs、Slime、Git.
* [cl-devel2](https://hub.docker.com/r/eshamster/cl-devel2/)  - Common Lisp 开发环境的 Docker 容器. 使用 Slime 运送 SBCL、CCL、Roswell 和 Emacs25.
* [Emacs4CL](https://github.com/susam/emacs4cl)  - 一个微小的 Emacs 初始化文件，用于快速设置用于 Common Lisp 编程的 vanilla Emacs. 附带对初始化文件中每一行代码的逐行解释.
* [quicklisp-systems](https://github.com/mmontone/quicklisp-systems) - 从 Emacs 搜索、浏览和加载 Quicklisp 系统.
*[slime-doc-contribs](https://github.com/mmontone/slime-doc-contribs) - 增强默认帮助缓冲区.

## Vim & Neovim ##

* [SLIMV](https://github.com/kovisoft/slimv)  - Vim 的高级 Lisp 交互模式； 在 Vim 中为 Common Lisp 提供一个成熟的环境. 未指定许可证.
* [Vlime](https://github.com/vlime/vlime)  - VLIME：Vim 加上 Lisp 大多是邪恶的.  Vim（和 Neovim）的 Common Lisp 开发环境.  [麻省理工学院][200].
* [quicklisp.nvim](https://gitlab.com/HiPhish/quicklisp.nvim) - Neovim 的 Quicklisp 前端.
* [Slimv_box](https://github.com/justin2004/slimv_box) - Docker 容器中的 slimv.


## Eclipse ##

* [Dandelion](https://github.com/Ragnaroek/dandelion) - Eclipse IDE 的 Common Lisp 插件.

## Lem ##

* [Lem](https://github.com/cxxxr/lem) - 即用型，类似 Emacs，基于 Slime
  为 Common Lisp 开发量身定制的编辑器. 带有 ncurses 和 Electron 接口.  [麻省理工学院][200]. 另见： [opengl frontend](https://github.com/pupcraft/lem-opengl), [Lem in Docker](https://github.com/40ants/lem-docker), [lem-pareto](https://github.com/40ants/lem-pareto).

## Atom ##

* [SLIMA](https://github.com/neil-lindquist/slima) 允许你
  交互式开发 Common Lisp 代码，将 Atom 变成一个
  非常好，积极开发，Lisp IDE.  [麻省理工学院][200].

## Sublime Text ##

* [Sublime Text](http://www.sublimetext.com/3) （专有）有
  Common Lisp 支持其 SublimeREPL 和
  [Slyblime](https://github.com/s-clerc/slyblime) packages. Slyblime
  是 SLY 的一个实现，它使用相同的后端 (SLYNK). 它
  提供高级功能，包括带有堆栈帧的调试器
  检查.

## VSCode ##

* [commonlisp-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.commonlisp-vscode)  - 支持语法高亮、自动完成、悬停文档、转到定义、编译和加载文件、REPL 的扩展. 这是 [On GitHub](https://github.com/ailisp/commonlisp-vscode/).
* [alive](https://github.com/nobody-famous/alive)  - VSCode 的通用 Lisp 扩展. 公共区域.
  * 见食谱： [using VSCode with Alive](https://lispcookbook.github.io/cl-cookbook/vscode-alive.html)
* [strict-paredit-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.strict-paredit) - 结构编辑和导航，如 Emacs.

## Geany (experimental) ##

* [Geany-lisp](https://github.com/jasom/geany-lisp) 是一个实验性的 lisp 模式 [Geany](https://geany.org/) 编辑.

## Notebooks ##

* [cl-jupyter](https://github.com/fredokun/cl-jupyter) - 用于 Jupyter 笔记本的 Common Lisp 内核 [custom licence](https://github.com/fredokun/cl-jupyter/blob/master/LICENSE).
* [common-lisp-jupyter](https://github.com/yitzchak/common-lisp-jupyter)  - Jupyter 的 Common Lisp 内核以及用于构建 Jupyter 内核的库，基于 Robert Dodier 的 Maxima-Jupyter，后者基于 Frederic Peschanski 的 cl-jupyter.  [麻省理工学院][200].
* [Darkmatter](https://github.com/tamamu/darkmatter) - 一种
  笔记本式的 Common Lisp 环境.  [麻省理工学院][200].

## REPLs ##

* [cl-repl](https://github.com/koji-kojiro/cl-repl)  - 一个类似 ipython 的 REPL. 带有补全、shell 命令、魔术命令、调试器等.[MIT][200]. 和 [colorthemes](https://github.com/koji-kojiro/lem-pygments-colorthemes).
* [sbcli](https://github.com/hellerve/sbcli)  - SBCL 的 readline REPL. 具有完成、快速命令、可选的语法突出显示（使用 pygments），并且没有交互式调试器.  [GPL3][2].

## Online editors ##

* [Judge0 IDE](https://ide.judge0.com/?lUpj) 是一个支持 Common Lisp (SBCL) 的在线编辑器.  [麻省理工学院][200].

## Apps ##

* [CodePlayground](https://codeplayground.app/) - 通过 CCL 支持 Lisp 的 iPhone 和 iPad 应用程序.

文本解析器
============

* ：星星： [esrap](https://github.com/scymtym/esrap)  - Packrat 解析器.  [外籍人士][14].
* [cl-yacc](https://github.com/jech/cl-yacc)  - LALR (1) 解析器生成器.  [麻省理工学院] [200].
* [cl-shlex](https://github.com/ruricolist/cl-shlex/)  - 用于类 shell 语法的简单词法分析器.  [麻省理工学院][200].
* [smug](https://github.com/drewc/smug)  - Common Lisp 的解析器组合器.  SMUG 使创建快速可扩展递归下降解析器变得简单，而无需时髦的语法或难以理解的宏观.  [麻省理工学院][200].
* [parseq](https://github.com/mrossini-ethz/parseq)  - 使用解析表达式语法解析字符串和列表等序列的库. 灵感来自 Esrap.  GPL2.
* [texp](https://github.com/eugeneia/texp/)  - 用于生成 TeX 的 DSL.  [AGPL-3.0][agpl3].

文本处理
===============

* [montezuma](https://github.com/sharplispers/montezuma/)  - 全文索引和搜索 Common Lisp.  [外籍人士][14].
* [mk-string-metrics](https://github.com/cbaggers/mk-string-metrics) -
  在 Common Lisp 中高效计算各种字符串度量
  (Damerau-Levenshtein, Hamming, Jaro, Jaro-Winkler, Levenshtein,
  等等）.  [麻省理工学院] [200].
* [wiki-lang-detect](https://github.com/vseloved/wiki-lang-detect) -
使用维基百科数据进行文本语言识别. 未指定许可证.
* [cl-phonetic](https://github.com/bgutter/cl-phonetic)  - Common Lisp 的语音模式匹配库（旨在替换 Python 的 Sylvia 库）.  [麻省理工学院][200].
* [cl-string-generator](https://github.com/pokepay/cl-string-generator)  - 从正则表达式生成字符串.  [麻省理工学院][200].

Tools
=====

这些是使 Common Lisp 中的开发变得更容易的应用程序或代码片段，而不是 Common Lisp 库本身.

* [quicksearch](https://github.com/tkych/quicksearch)  - 从 REPL 中查找在线库.  [外籍人士][14].
* [lake](https://github.com/takagi/lake)  - 一个类似于 GNU make 的构建工具.  [麻省理工学院][200].


单元测试
============

* ：星星： [FiveAM](https://github.com/sionescu/fiveam)  - 简单的回归测试框架.  [FreeBSD] [39].
* [CLUnit2](https://notabug.org/cage/clunit2/)  - 单元测试库.  [麻省理工学院][200].
* [Parachute](https://github.com/Shinmera/parachute)  - 一个可扩展和交叉兼容的测试框架. 具有测试依赖性、条件、装置和重启.  [zlib] [33].
* [Mockingbird](https://github.com/Chream/mockingbird) - 一个小
   Common Lisp 的存根和模拟库. 也可以查
  调用了一个存根函数，调用了多少次，用哪个
  论据.  [麻省理工学院] [200].
* [cl-mock](https://github.com/Ferada/cl-mock)  - 另一个嘲讽库. 它比 Mockingbird 具有更多功能，例如模拟调用的模式匹配等.
* [Check-it](https://github.com/DalekBaldwin/check-it)  - QuickCheck 风格的随机属性测试.  [LLGPL] [8].
* [cl-coveralls](https://github.com/fukamachi/cl-coveralls) - 帮手
  库将测试覆盖率发布到 Coveralls. 看 [SBCL's code coverage tool](http://www.sbcl.org/manual/index.html#sb_002dcover) .  [FreeBSD] [39].

编辑器实用程序：

* [Slite](https://github.com/tdrhq/slite/)  - 用于 FiveAM 测试的基于 SLIme 的测试运行器.  [Apache2.0][89]
   - Slite 以交互方式运行您的 Common Lisp 测试（在撰写本文时仅支持 FiveAM）. 它允许您查看测试失败的摘要、跳转到测试定义、使用调试器重新运行测试，所有这些都来自 Emacs.


Utilities
=========

Caching
-------

* [clache](https://github.com/html/clache)  - 通用缓存设施.  [LLGPL] [8].


压缩/解压
---------------------------

* [chipz](https://github.com/froydnj/chipz)  - 一个解压库.  [3 条款 BSD][15].
* [Salza2](http://www.xach.com/lisp/salza2/)  - 用于创建压缩数据的库.  [FreeBSD] [39].
* [zippy](https://github.com/Shinmera/zippy)  - 基于 3bz 的 ZIP 存档格式库.  [zlib] [33].


Configuration
-------------

*  [py-configparser](https://common-lisp.net/project/py-configparser/)  - 读取和写入 Python 的类似 ConfigParser 的配置文件.  [麻省理工学院][200].
* [envy](https://github.com/fukamachi/envy)  - 配置切换器.  [FreeBSD] [39].
* [chameleon](https://github.com/sheepduke/chameleon/)  - 带有配置文件支持的配置管理库.  [麻省理工学院][200].

CSV
---

* ：星星： [cl-csv](https://github.com/AccelerationNet/cl-csv)  - 用于解析 CSV 文件的库.  [3 条款 BSD][15].
* [cl-decimals](https://github.com/tlikonen/cl-decimals)  - 十进制数解析器和格式化程序. 公共区域.
* [auto-text](https://github.com/defunkydrummer/auto-text)  - 文本文件的自动（编码、行尾、列宽、csv 分隔符等）检测.  [麻省理工学院][200]. 也可以看看 [inquisitor](https://github.com/t-sin/inquisitor) 用于检测亚洲和远东语言.


日期和时间
-------------

* ：星星： [local-time](https://common-lisp.net/project/local-time/)  - 以半标准方式操作日期和时间信息的开发库.  [3 条款 BSD][15].
* [cl-date-time-parser](https://github.com/tkych/cl-date-time-parser)  - 自由地解析日期时间字符串. 隐藏日期时间格式之间的差异，并可以将日期和时间作为一种日期时间格式进行管理.  [麻省理工学院][200].
* [chronicity](https://github.com/chaitanyagupta/chronicity)  - 自然语言日期和时间解析，用于解析诸如“从现在起 3 天”之类的字符串.  [BSD_3 条款][15].
* [local-time-duration](https://github.com/enaeher/local-time-duration) -
建立在本地时间之上的持续时间处理库.  [麻省理工学院][200].
  * 看到这个叉子： [humanize-duration](https://github.com/40ants/humanize-duration) ，只输出持续时间对象的重要部分. 有本地化支持.
* [iso-8601-date](https://gitlab.com/DataLinkDroid/iso-8601-date)  - Common Lisp 中的其他日期例程，基于 ISO 8601 字符串表示.  [LLGPL] [8].
* [calendar-date](https://github.com/takagi/calendar-date)  - 公历日期库.  [麻省理工学院][200].
* [periods](https://github.com/jwiegley/periods)  - 在更高级别操作日期/时间对象. 具有系列兼容的数据结构.  [BSD_3 条款][15].

又见书 [Calendrical calculations](https://www.cambridge.org/us/academic/subjects/computer-science/computing-general-interest/calendrical-calculations-ultimate-edition-4th-edition?format=HB#resources) ，Edward M. Reingold，Nachum Dershowitz，剑桥出版社. 它提供 Lisp 源代码.

数据验证
---------------

* [ratify](https://github.com/Shinmera/ratify)  - 一组用于批准、验证和解析输入的实用程序.  [zlib] [33].
* [clavier](https://github.com/mmontone/clavier)  - Common Lisp 的通用验证库.  [麻省理工学院][200].
* [json-schema](https://github.com/fisxoj/json-schema) - 用于根据草案 4、6、7 和 2019-09 的模式验证数据的库 [JSON Schema](https://json-schema.org/) 标准.  [LLGPL] [8].
* [sanity-clause](https://github.com/fisxoj/sanity-clause)  - Common Lisp 的数据序列化/合同库. 模式可以是属性列表或基于类，允许在 `make-instance` 期间检查插槽的类型.  [LLGPL] [8].

开发人员实用程序
-------------------

* [repl-utilities](https://github.com/m-n/repl-utilities) - 舒适
REPL 的常见任务（打印文档、打印外部符号、
加载包时调用钩子，...）.  [BSD_2 条款][17].
* [flight-recorder](https://github.com/vseloved/flight-recorder) - 一个强大的 REPL 历史工具.
* [tracer](https://github.com/TeMPOraL/tracer)  - Common Lisp 的跟踪分析器，输出适合在 Chrome/Chromium 的跟踪查看器中显示.  [麻省理工学院][200].
* [cl-flamegraph](https://github.com/40ants/cl-flamegraph)  - SBCL 统计分析器的包装器，用于为 Common Lisp 程序生成 FlameGraph 图表.  [BSD] [15].
* [cl-debug](https://github.com/LowH/cl-debug)  - 跨包调试工具. 提供一种统一的方式来启用或禁用特定于调试的代码. 可以相对于由符号或关键字表示的程序功能启用或禁用调试代码.  ISC 许可证.
* [supertrace](https://github.com/fukamachi/supertrace)  - 用于调试/分析的高级 Common Lisp `trace` 功能. 一次跟踪多个函数，使用前后钩子.  [BSD_2 条款][17].
* [printv](https://github.com/danlentz/printv)  - 包含电池的跟踪和调试日志宏.  [Apache2][89].
* [GTFL](http://www.martin-loetzsch.de/gtfl/)  - Lisp 的图形终端，适用于想要调试或可视化他们自己的算法的 Lisp 程序员. 浏览器中的图形跟踪.  BSD 风格.
* [trivial-with-current-source-from](https://github.com/scymtym/trivial-with-current-source-form/)  - 帮助宏编写者为宏用户产生更好的错误.  [GPL3][2].
* [trivial-benchmark](https://github.com/Shinmera/trivial-benchmark)  - 小型基准测试库.  [zlib] [33].
* [glyphs](https://github.com/ahungry/glyphs/)  - 用于在某些地方减少 Common Lisp 冗长的库.  [GNU GPL3][2].
* [Lisp REPL core dumper](https://gitlab.com/ambrevar/lisp-repl-core-dumper/) -
一个便携式包装器，可按需生成 Lisp 内核以快速启动 REPL.
它可以预加载提供的系统以帮助构建专门的集合
Lisp cores.


文档构建器
----------------------

* [sphinxcontrib-cldomain](https://github.com/russell/sphinxcontrib-cldomain) -
  扩展 Sphinx 以覆盖 Common Lisp. 构建文档
   Python 项目与 sphinx 一样容易.  [GPL3][2]
* [Codex](https://github.com/CommonDoc/codex) - 一个美丽
   Common Lisp 的文档系统.  [麻省理工学院][200].
* [Staple](https://github.com/Shinmera/staple)  - 使用 HTML 模板生成文档页面的工具. 使用现有的自述文件，添加文档字符串、交叉引用和到 CLHS 的链接.  [zlib] [33].
* [cl-bibtex](https://github.com/mkoeppe/cl-bibtex)  - 用 BST-to-CL 编译器在 Common Lisp 中兼容地重新实现 BibTeX 程序.  [GNU LGPL2.1][11].
* [mgl-pax](https://github.com/melisgl/mgl-pax) - 探索性
编程环境和文档生成器. 一个人可以
实现与文学编程类似的效果，但
文档是从代码生成的，反之亦然. 代码为先，
代码必须看起来很漂亮，文档就是代码.  [麻省理工学院][200].
  - 看到这个 [40ants fork](https://github.com/40ants/doc)
* [erudite](https://github.com/mmontone/erudite)  - 以交互式开发为基础构建的文学编程系统.  [麻省理工学院][200].


文件和目录
---------------------

* ：星星： [uiop](https://common-lisp.net/project/asdf/uiop.html) 和它的 `pathname` 包
  （代替 [cl-fad](http://weitz.de/cl-fad/) ）.  uiop 是 ASDF3 的一部分
  并且因此在许多实现中提供.  [麻省理工学院][200].
* [osicat](https://common-lisp.net/project/osicat/) - 类 POSIX 系统上的轻量级操作系统接口（目录迭代和删除、环境变量、文件权限等）[Expat][14].
* [pathname-utils](https://github.com/Shinmera/pathname-utils)  - 一组帮助进行路径名操作的实用程序.  [zlib] [33].
* [ppath](https://github.com/fourier/ppath) - Common Lisp 
 Python 的 os.path 模块的实现.  [BSD] [15].
* [archive](https://github.com/froydnj/archive)  - 用于读取和创建存档（tar、cpio）文件的库.  [BSD_3 条款][15].  `tar` 程序的纯 Common Lisp 替代品.
  * 查看它最近的分支 [cl-tar](https://common-lisp.net/project/cl-tar/) (2021). [Announce](https://www.timmons.dev/posts/new-project-cl-tar.html).
* [mmap](https://github.com/Shinmera/mmap)  - 便携式 mmap 文件内存映射实用程序库.  [zlib] [33].
* [fof](https://gitlab.com/ambrevar/fof)  - 文件对象查找器 Common Lisp 库. 启用快速文件搜索、检查和操作.  [GPL3][2].

文件监视库：

* [cl-inotify](https://github.com/Ferada/cl-inotify)  - Linux inotify API 的接口. 简化的 BSD 许可证.
* [cl-fswatch](https://github.com/muyinliu/cl-fswatch) - 包装器 YFC [fswatch](https://github.com/emcrisostomo/fswatch) ，一个跨平台的文件更改监视器.  [国际标准委员会][22].

Git
---

* [legit](https://shinmera.github.io/legit/)  - Git 二进制文件的接口.  [zlib] [33].
* [git-api](https://github.com/fourier/git-api) - Common Lisp 库
访问 git 存储库. 它不需要安装 git 或 libgit.  [BSD] [15].

i18n
----

* [cl-i18n](https://notabug.org/cage/cl-i18n)  - 一个 i18n 库. 从 GNU gettext 文本或二进制文件或其本机格式加载翻译. 复数形式的本地化助手.  [LLGPL] [8].
* [gettext](https://github.com/rotatef/gettext)  - gettext 运行时到 Common Lisp 的端口.  [GPL3][2].
* [cl-locale](https://github.com/fukamachi/cl-locale)  - 一个简单的 i18n 库.  [LLGPL] [8].
* [enchant](https://github.com/tlikonen/cl-enchant)  - 附魔拼写检查库的绑定. 公共区域.
* [oxenfurt](https://github.com/Shinmera/oxenfurt)  - 牛津词典 API 的客户端库.  [zlib] [33].
* [language-codes](https://shinmera.github.io/language-codes)  - ISO 语言代码的数据库库.  [zlib][33]
* [system-locale](https://shinmera.github.io/system-locale)  - 检索用户首选语言的库，以便您的应用程序可以选择合理的默认值.  [zlib] [33].
* [multilang-documentation](https://shinmera.github.io/multilang-documentation)  - 允许以多种语言编写文档字符串，用于真正具有国际记录的库.  [zlib] [33].

Linting、代码格式化
------------------------

* [sblint](https://github.com/fukamachi/sblint) - 使用 SBCL 的 Common Lisp 源代码的 linter，适用于 Reviewdog ([slides](http://www.slideshare.net/fukamachi/sblint) ）.  [BSD_2 条款][17].
* [trivial-formatter](https://github.com/hyotang666/trivial-formatter)  - Common Lisp 的代码格式化程序.  [麻省理工学院][200].

并且： [lisp-format](https://github.com/eschulte/lisp-format) 和 [cl-indentify](https://github.com/yitzchak/cl-indentify).


Logging
-------

* ：星星： [log4cl](https://github.com/sharplispers/log4cl/)  - 以 Log4J 为模型的日志框架.  [Apache2.0][89]. 与 Slime 的高级集成.
  * [log4cl-json](https://github.com/40ants/log4cl-json)  - JSON 附加程序扩展.  [BSD] [15].
* [verbose](https://shinmera.github.io/verbose)  - 一个快速且高度可配置的日志框架.  [zlib] [33].
* [a-cl-logger](https://github.com/AccelerationNet/a-cl-logger)  - 日志库提供上下文敏感的日志记录，不仅仅是字符串，不仅仅是本地文件或输出流. 具有 logstash 支持、json 支持、记录器层次结构、上下文相关日志记录、打印为可检查演示文稿的对象……

对第三方：

* [cl-fluent-logger](https://github.com/fukamachi/cl-fluent-logger) - 一个 Common Lisp 结构化记录器，用于 [Fluentd](https://www.fluentd.org/).

也可以看看： [extensive comparison of logging libraries](https://sabracrolleton.github.io/logging-comparison).


Markdown
--------

* [3bmd](https://github.com/3b/3bmd)  - 降价 -&gt; html 转换器.  [麻省理工学院] [200].

PDF
---

* [cl-typesetting](https://github.com/mbattyani/cl-typesetting) 和 [cl-pdf](https://github.com/mbattyani/cl-pdf)  - 用于生成 PDF 文件的跨平台 Common Lisp 库.  [FreeBSD] [39].
* [cl-pslib](https://notabug.org/cage/cl-pslib) - 周围的（薄）包装 [pslib](http://pslib.sourceforge.net/) 用于生成 PostScript 文件的库. 还 [cl-pslib-barcode](https://notabug.org/cage/cl-pslib-barcode) .  [LLGPL] [8].

Plotting
--------

* [vgplot](https://github.com/volkers/vgplot) - 一个接口
  gnuplot 绘图实用程序，旨在类似于某些
  八度或matlab的绘图命令.  [GPL3][2].
* [eazy-gnuplot](https://github.com/guicho271828/eazy-gnuplot) - 一种
   lispy，无结构的 Gnuplot 库. 与其
  [cookbook](http://guicho271828.github.io/eazy-gnuplot/) .  [LLGPL] [8]
* [kai](https://github.com/komi1230/kai)  - Common Lisp 的高级绘图仪库. 周围的包装 [Plotly](https://plotly.com/javascript/)  JS库.  [麻省理工学院][200].
* [ADW-Charting](https://common-lisp.net/project/adw-charting/)  - 一个完全用 Common Lisp 编写的简单图表绘制库. 还包括 Google 图表服务的后端. 类似BSD.
* [cl-spark](https://github.com/tkych/cl-spark)  - 控制台的迷你图字符串：`(spark &#39;(1 1 2 3 5 8))` =&gt; &quot; ▂▃▅▇&quot;.  [麻省理工学院][200].

另请参阅 IUP 和 ltk-plotchart 的图表工具（GUI 部分）.

项目骨架
-----------------

* [cl-project](https://github.com/fukamachi/cl-project)  - 一般现代项目骨架.  [LLGPL] [8].
* [cl-project-with-docs](https://github.com/40ants/cl-project-with-docs)  - 使用 Sphinx 和重构文本来呈现漂亮且可读的 HTML 文档.  [BSD] [15].
* [cl-cookieproject](https://github.com/vindarel/cl-cookieproject)  - 生成一个随时可用的 Common Lisp 项目. 不在 Quicklisp 中.  [BSD_3 条款][15].
  * 测试定义、从源代码运行的入口点、构建二进制文件、Roswell 集成……

Security
--------

* [cl-isolated](https://github.com/kanru/cl-isolated) - Common Lisp 代码评估的受限环境 [AGPL-3.0][agpl3].


Other
-----

这包含任何不属于另一个类别的内容.

* [babel](https://github.com/cl-babel/babel)  - 字符集编码/解码库.  [外籍人士][14].
* [corona](https://github.com/eudoxia0/corona) - 从 Common Lisp http://eudoxia.me/corona [MIT][200] 创建和管理虚拟机.
* [fast-io](https://github.com/rpav/fast-io)  - 快速八位字节向量/流 I/O.  [3 条款 BSD][15].
* [iolib](https://github.com/sionescu/iolib)  - I/O 库.  [外籍人士][14].
* [named-readtables](https://github.com/melisgl/named-readtables)  - 提供一个可读的命名空间，类似于包命名空间.  [3 条款 BSD][15].
* [simple-currency](https://github.com/a0-prw/simple-currency)  - 使用欧洲央行发布的每日信息的货币转换库.  [FreeBSD] [39].
* [trivial-garbage](https://github.com/trivial-garbage/trivial-garbage)  - 一个便携式终结器、弱哈希表和弱指针 API. 公共区域.
* [trivial-utf8](https://common-lisp.net/project/trivial-utf-8/)  - 一个用于执行基于 UTF-8 的 I/O 的小型库.  BSD.


XML
===

* [CXML](https://common-lisp.net/project/cxml/)  - XML 解析器和序列化器，具有一系列扩展库.  [LLGPL] [8].
  - 有一个增量解析器，允许解析大文件.
 * [Plump][71] - 一个宽松的 XML 解析器.  [艺术许可 2.0][51].
* [xpath](https://github.com/sharplispers/xpath) ([homepage](https://common-lisp.net/project/plexippus-xpath/atdoc/index.html)  - XML 路径语言 (XPath) 1.0 版的实现.  [BSD_2 条款][17].
* [s-xml](http://cliki.net/S-XML) - A basic parser. [LLGPL][8].
* [xmls](https://github.com/rpgoldman/xmls)  - 一个小的、简单的、非验证的 XML 解析器.  [3 条款 BSD][15].
* [cl-feedparser](https://github.com/TBRSS/cl-feedparser)  - Common Lisp（RSS，Atom）提要解析器.  [LLGPL][8]
* [Buildnode](https://github.com/AccelerationNet/buildnode)  - 一个通用的 lisp 库，用于简化与 CXML-dom 的交互，例如构建 Excel 电子表格.  [BSD] [15].


Contributing
============
随时欢迎您的贡献！ 请提交拉取请求或创建
将新框架、库或软件添加到列表中的问题.

我们（尝试）遵守的规则如下：

- 默认情况下，将库添加到其部分的末尾.
- 绝对事实上的库，如 BordeauxThreads 或 Quicklisp，
  应该用 :star: 表示（markdown 中的`:star:`）.
- 两个范围非常相似的库应该并排，或在一个
  属于自己的部分.
- 根据我们的经验和现状做一些策展
  图书馆的文档. 我们*不*旨在列出每个现有
  CL 库（请参阅 Cliki）也不列出每个
  “流行”库（参见 Quicklisp 统计信息）.
- 因此，我们最喜欢的库标有 (`1F44D`
   Unicode 字符）. 另请参阅说明中的标志说明
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
