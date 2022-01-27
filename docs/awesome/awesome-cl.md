<div class="github-widget" data-repo="CodyReichert/awesome-cl"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">
  <a href="https://awesome-cl.com" target="_blank">
    <img src="https://i.imgur.com/jLVXhpc.png">
  </a>
</div>

## Awesome Common Lisp [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Assertible status](https://assertible.com/apis/102e334d-f9a8-4565-9353-7572de775cae/status?api_token=8b55a286830323effb)](https://assertible.com/docs/guide/deployments)

A curated list of _awesome_ Common Lisp libraries.

For awesome *software*, see [lisp-lang.org's success stories](http://lisp-lang.org/success/) 和 [awesome-cl-software](https://github.com/azzamsa/awesome-cl-software) list.

All libraries listed here are available from [Quicklisp][16] unless
stated otherwise. The ones marked with a :star: are so widespread and
坚实，他们成为社区的标准. 你不会错
他们.  Quicklisp、BordeauxThreads 和
such. Libraries denoted with a 👍 are the ones we like and want to
promote here at the Awesome-cl list. They proved solid, they may solve
a problem better than a community standard but they aren't as
普遍，或不被认为是稳定的. 例如，我们更喜欢
Cl-Who 上的喷丝板.

添加新内容！ 见 [contributing](#contributing) 用于添加内容的部分
list.

这是根据 GNU 自由文档许可证发布的 - 它的文本
is provided in the LICENSE file. This repository is also mirrored on
[NotABug](https://notabug.org/CodyReichert/awesome-cl) - **完全免费**（如在 libre 中）
alternative to Github.  Preference is given to [free software][13] and
sellers who aren't evil for physical resources.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->


<!-- markdown-toc end -->


Audio
=====

* [Open Music](https://github.com/openmusic-project/OM6) - a visual programming, computer-aided composition environment. [GPL3][2].
* [OM7](https://github.com/openmusic-project/om7) - a new implementation of the OpenMusic visual programming and computer-aided composition environment including a number of improvements on graphical interface, computational mode, and connection to external software libraries. [GPL3][2].
* [Incudine](http://incudine.sourceforge.net/) -  Music/DSP programming environment for Common Lisp. Useful to design software synthesizers or sound plugins from scratch. It is also a compositional tool that allows to produce high quality sounds controllable at the sample level, defining and redefining the digital signal processors and the musical structures on-the-fly.
* [cl-collider](https://github.com/byulparan/cl-collider) - A
[SuperCollider](http://supercollider.github.io/) client for CommonLisp. With a [tutorial](https://github.com/defaultxr/cl-collider-tutorial) 和 [live coding demos](https://www.youtube.com/watch?v=xzTH_ZqaFKI). Public domain.
* [csound](https://github.com/csound/csound)  - 声音和音乐计算系统. 包括用于 Common Lisp 的 CFFI 和 FFI 接口.
* [CLM](https://ccrma.stanford.edu/software/clm/) - Common Lisp Music is a music synthesis and signal processing package in the Music V family. It provides much the same functionality as Stk, Csound, SuperCollider, PD, CMix, cmusic, and Arctic — a collection of functions that create and manipulate sounds, aimed primarily at composers (in CLM's case anyway).
* [cl-patterns](https://github.com/defaultxr/cl-patterns) - a system for composing music via Lisp code, heavily inspired by SuperCollider’s patterns system, with aims to implement much of it, but in a more robust, expressive, consistent, reflective, and lispy way. Audio output through SuperCollider, with preliminary support for Incudine, and MIDI through ALSA.
* [cl-openal](https://github.com/zkat/cl-openal)  - OpenAL 音频库的绑定. 公共区域.
* [Common Music](https://github.com/ormf/cm) - 存储库
ancient version of Common Music (version 2.12.0), the presumably last
在 2007-09 年左右在 Common Lisp 上运行的版本，之前
work on Common Music shifted to (scheme-based) cm3.
* [Slippery Chicken](https://github.com/mdedwards/slippery-chicken/) - Algorithmic composition library which outputs Midi, Common Music Notation, pdf-score via Lilypond and sound via Common Lisp Music. [GPL3][2].
* [Common Music Notation](https://ccrma.stanford.edu/software/cmn/)  - Common Music Notation (CMN) 提供了一组函数来分层描述乐谱. 公共区域.
* [cm-incudine](https://github.com/ormf/cm-incudine) - extends Common Music 2 with realtime capabilities. GPL2.
* [Mégra](https://github.com/the-drunk-coder/megra) - A mini-language to make music with variable-order markov chains and some other stochastic shenanigans. [GPL3][2].
* [Music](https://github.com/MegaLoler/Music) - A framework for musical expression in Lisp with a focus on music theory (built from scratch, unrelated to Common Music).
* [rq](https://github.com/openmusic-project/RQ) - 在 OpenMusic（6.10 版及更高版本）中用于节奏转录的库. [demo video](https://www.youtube.com/watch?v=XVEllB0TtVs) .  [GPL3][2].
* [scheduler](https://github.com/byulparan/scheduler)  - Common Lisp 基于时间的音乐事件调度程序.  [Apache2.0][89].
* [mixalot](https://github.com/ahefner/mixalot) - Loosely-coupled collection of audio libraries for mp3, ogg vorbis, flac. Used for the [Shuffletron music player](https://github.com/ahefner/shuffletron). [MIT][200].
* [osc](https://github.com/zzkt/osc) - an implementation of the Open Sound Protocol. [LGPL2.1][11].
* [Harmony](https://shirakumo.github.io/harmony) - A real-time sound processing and playback system. [zlib][33].


Build Systems
=============

* :star: [ASDF](https://common-lisp.net/project/asdf/)  - 另一个系统定义工具；  Common Lisp 的构建系统.  [外籍人士][14].  Quicklisp（见 [library manager](#library-manager)) uses ASDF under the hood.
  * [known ASDF extensions](https://common-lisp.net/project/asdf/#extensions), such as `asdf-system-connections`, that lets you specify systems that are automatically loaded when two other systems are loaded, to connect them.
* [asdf-linguist](https://github.com/eudoxia0/asdf-linguist)  - ASDF 的扩展.  [外籍人士][14].
* [asdf-viz](https://github.com/guicho271828/asdf-viz)  - 可视化 ASDF 系统的库依赖关系、函数调用图和类继承的工具.  [LLGPL][8].

编译器、代码生成器
==========================

APL
---

* [April](https://github.com/phantomics/april) - The APL programming language (a subset thereof) compiling to Common Lisp. Replace hundreds of lines of number-crunching code with a single line of APL. [Apache2][89].


C, C++
------

* [cmacro](https://github.com/eudoxia0/cmacro) - C. [MIT][200] 的 Lisp 宏.
* [C-mera](https://github.com/kiselgra/c-mera)  - 一个源到源编译器，它利用 Lisp 的宏系统对类 C 语言进行元编程.  [GPL3][2].
* [lispc](https://github.com/eratosthenesia/lispc) - 一种强大的 C 语言“lispsy”宏语言.[MIT][200].
* [with-c-syntax](https://github.com/y2q-actionman/with-c-syntax) - a fun package which introduces the C language syntax into Common Lisp. (Yes, this package is not for practical coding, I think.) WTFPL Licence.
* [ecrepl](https://gitlab.common-lisp.net/ecl/ecrepl) - an interactive REPL for the C language. [BSD_2Clause][17].
* [Software-Evolution-Library](https://github.com/GrammaTech/sel) - The SEL enables the programmatic modification and evaluation of software (C/C++ support using Clang, compiled assembler, and linked ELF binaries). [GPL3][2].

Crypto
======

* :star: [Ironclad](https://github.com/sharplispers/ironclad)  - Common Lisp 的加密函数库. 不被认为是安全的，但对于消息摘要功能仍然有用.  [外籍人士][14].
* [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts)  - 常用加密快捷方式的集合.  [zlib][33].
* [trivial-ssh](https://github.com/eudoxia0/trivial-ssh) - An SSH client library. [Expat][14].
* [cl-ssh-keys](https://github.com/dnaeon/cl-ssh-keys)  - 用于生成和解析 OpenSSH 密钥的 Common Lisp 系统.  [BSD_3 条款][15].
* [cl-bcrypt](https://github.com/dnaeon/cl-bcrypt) - Common Lisp system for parsing and generating bcrypt password hashes. [BSD_3Clause][15].
  * see also [cl-pass](https://github.com/eudoxia0/cl-pass), using pbkdf2.

Cryptocurrencies
================

* [cl-monero-tools](https://github.com/glv2/cl-monero-tools) -  Common Lisp toolbox to work with the Monero cryptocurrency. [GPL3][2]. Not in Quicklisp.
* [emotiq](https://github.com/emotiq/emotiq) - a next-generation blockchain with an innovative natural-language approach to smart contracts. [MIT][200].
* [peercoin-blockchain-parser](https://github.com/glv2/peercoin-blockchain-parser) - parse the blockchain contained in a file and export some of its data to a text file, a SQL script or a database. It can also create a database using the RPC of a Peercoin daemon as source of data instead of a blockchain file. LGPL3. Not in Quicklisp.
* [peercoin-calculator](https://github.com/glv2/peercoin-calculator) - This program gives you the probability of generating a POS or POW block within 10 minutes, 24 hours, 31 days, 90 days and 1 year, as well as the reward that can be expected. GUI in Qt. [GPL3][2]. Not in Quicklisp.
* [peercoin-vote](https://github.com/glv2/peercoin-vote)  - 基于区块链数据（地址和余额）的投票系统.  [GPL3][2]. 不在 Quicklisp 中.

See also [legochain](https://github.com/defunkydrummer/legochain), a simple educational blockchain.

Database
========

* [cl-yesql](https://github.com/ruricolist/cl-yesql)  - SQL 语句以 SQL 语法存在于它们自己的文件中，并作为函数导入 Lisp. 您不仅限于 DSL 支持的功能. 基于 Clojure 的 Yesql.  [麻省理工学院][200].

ORMs
----

* :star: [clsql](http://www.cliki.net/CLSQL) - An SQL database with a Common Lisp interface. [LLGPL][8].
*  [mito](https://github.com/fukamachi/mito) - An ORM for Common Lisp with migrations, relationships and PostgreSQL support [LLGPL][8]. [mitho-auth](https://github.com/fukamachi/mito-auth), a mixin class for use authorization; [mito-attachment](https://github.com/fukamachi/mito-attachment), a mixin class for file management outside of RDBMS.
* [cl-dbi](https://github.com/fukamachi/cl-dbi) - A database-independent interface for Common Lisp. [LLGPL][8].
  * [dbd-oracle](https://github.com/sergadin/dbd-oracle)  - 用于 CL-DBI 的 Oracle 数据库驱动程序.  [LLGPL][8].
* [crane](https://github.com/eudoxia0/crane)  - 另一个 ORM.  [外籍人士][14].
* [datafly](https://github.com/fukamachi/datafly)  - 一个轻量级的数据库库.  [3 条款 BSD][15].
* [sxql](https://github.com/fukamachi/sxql) - A DSL for generating SQL. [3-clause BSD][15].

Persistent object databases
---------------------------

* [bknr.datastore](https://github.com/hanshuebner/bknr-datastore) - RAM 中基于 CLOS 的仅 lisp 数据库，具有事务日志记录持久性. [Manual](https://www.common-lisp.net/project/bknr/html/documentation.html). [licence][208].
  * see also this [good introductory blog post](https://ashok-khanna.medium.com/persistent-in-memory-data-storage-in-common-lisp-b-k-n-r-37f8ae76042f)
  * an example web application using bknr.datastore: [screenshotbot-oss](https://github.com/screenshotbot/screenshotbot-oss).
* [ubiquitous](https://github.com/Shinmera/ubiquitous)  - 提供易于使用的持久配置存储的库.  [zlib][33].
* [cl-prevalence](https://common-lisp.net/project/cl-prevalence/) - in-memory database system. Implementation of Object Prevalence, in which business objects are kept live in memory and transactions are journaled for system recovery. [github fork](https://github.com/40ants/cl-prevalence) .  [LLGPL][8]. 也可以看看 [cl-prevalence-multimaster](https://github.com/40ants/cl-prevalence-multimaster), to syncronize multiple cl-prevalence systems state.

图数据库
---------------

* [cl-agraph](https://github.com/vseloved/cl-agraph), a minimal client for [AllegroGraph](https://allegrograph.com/). AllegroGraph is a horizontally distributed, multi-model (document and graph), entity-event knowledge graph technology. It is proprietary and has a free version with a limit of 5 million triples.
* [neo4cl](https://github.com/equill/neo4cl) - a library for interacting with Neo4J. Sends Cypher queries to a Neo4J server, and decodes the responses into something useful for processing in CL. [Apache2][89].
  * and maybe: [cl-neo4j](https://github.com/kraison/cl-neo4j) - a thin neo4j RESTFUL client interface.
* [vivace-graph](https://github.com/kraison/vivace-graph-v3)  - 图形数据库和 Prolog 实现. 从 CouchDB、neo4j 和 AllegroGraph 中汲取设计灵感. 它使用用户定义的索引和 map-reduce 视图实现了符合 ACID 的对象图模型. 它还实现了用于冗余和水平读取扩展的主/从复制方案. 查询图形是通过许多 Lisp 方法或通过类似 Prolog 的查询语言来完成的.  [麻省理工学院][200].
* [facts](https://github.com/cl-facts/facts) - an in-memory graph database with transactions and rollbacks, logging/replay and dumping/loading to/from disk. BSD-style license (ISC).

and also:

* [restagraph](https://github.com/equill/restagraph) - an app that dynamically generates REST APIs for a Neo4j database, using a schema defined within the database. [GPL3][2].


Wrappers
--------

* :star: [postmodern](http://marijnhaverbeke.nl/postmodern/)  - 用于与 PostgreSQL 交互的库.  [zlib][33].
* [cl-sqlite](https://github.com/dmitryvk/cl-sqlite) - Bindings for SQLite. Public domain.
* [cl-memcached](https://github.com/quasi/cl-memcached) - Fast, thread-safe interface to the Memcached object caching system. [Expat][14].
* [cl-mongo](https://github.com/fons/cl-mongo) - MongoDB client. [Expat][14].
* [cl-redis](https://github.com/vseloved/cl-redis) - Redis client. [Expat][14].
* [cl-disque](https://github.com/CodyReichert/cl-disque)  - 客户磁盘.  [BSD 3 条款][15].
* [cl-rethinkdb](https://github.com/orthecreedence/cl-rethinkdb)  - RethinkDB 客户端.  [外籍人士][14].
* [cl-mango](https://github.com/cmoore/cl-mango/) -  A minimalist CouchDB 2.x database client. BSD_3Clause. See also [clouchdb](https://common-lisp.net/project/clouchdb/) - Library for interacting with CouchDB. [FreeBSD][39].
* [lmdb](https://github.com/antimer/lmdb) - Bindings to [LMDB](http://www.lmdb.tech/doc/), the Lightning Memory-mapped Database, an ACID key-value database with MultiVersion Concurrency Control.

迁移工具
---------------

* [cl-migratum](https://github.com/dnaeon/cl-migratum)  - 一个为执行数据库模式迁移提供设施的系统，旨在与各种数据库一起使用.  [BSD_3 条款][15].
* [postmodern-passenger-pigeon](https://github.com/fisxoj/postmodern-passenger-pigeon/) - a migration manager for postmodern. No licence specified.


To third parties
----------------

* [dyna](https://github.com/Rudolph-Miller/dyna) - an AWS DynamoDB ORM. [MIT][200].
* [cl-influxdb](https://github.com/mmaul/cl-influxdb/) - an interface to the Time Series Database InfluxDB. [MIT][200].
* [pzmq](https://github.com/orivej/pzmq) -  ZeroMQ 4.0+ Common Lisp bindings. Unlicense.

Tools
-----

* [pgloader](https://github.com/dimitri/pgloader)  - 用于 PostgreSQL 的数据加载工具.  [PostgreSQL 许可证][205].


数据结构
===============

*  [str](https://github.com/vindarel/cl-str) - a modern, simple and consistent string manipulation library. [MIT][200].
*  [FSet](https://common-lisp.net/project/fset) - A functional, set-theoretic collections data structure library. [LLGPL][8].
* [trivial-extensible-sequences](https://github.com/Shinmera/trivial-extensible-sequences) - Portability library for the extensible sequences protocol ([SBCL documentation](http://www.sbcl.org/manual/#Extensible-Sequences)). [zlib][33].
* [bst](https://github.com/glv2/bst)  - 二叉搜索树.  [GPL3][2].
* [pileup](http://nikodemus.github.io/pileup/) - a portable, performant, and thread-safe binary heap for Common Lisp. [MIT][200].
* [sycamore](https://github.com/ndantam/sycamore)  - 一个快速、纯功能的数据结构库.  [BSD_3 条款][15].
* [genhash](https://github.com/pnathan/genhash)  – 使用通用方法的 API 实现哈希表. 公共区域.
* [cl-ctrie](https://github.com/danlentz/cl-ctrie) -
lock-free, concurrent, key/value index with efficient memory-mapped persistence and fast transient storage models. [MIT][200].
* [cl-data-structures](https://github.com/sirherrbatka/cl-data-structures) - a portable collection of data structures and algorithms (mainly dicts and sequences, with some statistical functions). [BSD][15].
* [listopia](https://github.com/Dimercel/listopia) - a list manipulation library inspired by Haskell's Data.List. [LLGPL][8].
* [hash-set](https://github.com/samebchase/hash-set/) - 在 CL 哈希表之上实现哈希集的便利库 [The Unlicense][5]
* [cl-containers](https://common-lisp.net/project/cl-containers/) - an extensive library of data structures and utilities - queues, trees, heaps, doubly-linked lists, sets, bags,... [MIT][200]
* [cl-competitive](https://github.com/privet-kitty/cl-competitive)  - 用于竞争性编程的通用 Lisp 算法集合. 公共领域，CCO 或 MIT.

Accessing data structures:

*  [access](https://github.com/AccelerationNet/access/) - Consistent and nested access to most common data structures. [BSD_3Clause][15].
* [modf](https://github.com/smithzvk/modf) - a setf-like macro for functional programming.

Other data structures:

* [bitfield](https://github.com/marcoheisig/bitfield) - Efficiently represent several finite sets or small integers as a single non-negative integer. [MIT][200].


Docker images
=============

* [cl-docker-images](https://common-lisp.net/project/cl-docker-images/) - Docker images for ABCL, CCL, ECL, and SBCL on Windows (amd64) and Alpine and Debian (amd64, arm64, arm/v7) [BSD_2Clause][17].
* [base-lisp-image](https://github.com/40ants/base-lisp-image) - base
  Docker image for Common Lisp projects with SBCL or CCL and the latest
  ASDF, Qlot and Roswell.


外部函数接口，语言互操作
=============================================

## C ##

* :star: [CFFI](https://github.com/cffi/cffi) - Portable, easy-to-use C foreign function interface. [Expat][14].
* [cl-autowrap](https://github.com/rpav/cl-autowrap) - Automatically parses header files into CFFI definitions. [FreeBSD][39].
* [cl-bindgen](https://github.com/sdilts/cl-bindgen)  - 用于从 C 头文件创建 Common Lisp 语言绑定的命令行工具和库.  [麻省理工学院][200].
* [cl-gobject-introspection](https://github.com/andy128k/cl-gobject-introspection) - [Gobject Introspection](https://gi.readthedocs.io/en/latest/)  FFI. 调用 C 库的自动绑定.  [BSD][15]. 生成一个lisp接口 [gir2cl](https://github.com/kat-co/gir2cl). [LGPL3][9].
* [cl-cxx-jit](https://github.com/Islam0mar/CL-CXX-JIT) -  Common Lisp and C++ interoperation with JIT. [MIT][200].

## Clojure

* [ABCLJ](https://github.com/lsevero/abclj) - dead easy  Clojure to Common lisp interop. EPL-2.0.

## Erlang ##

* [CLERIC](https://github.com/flambard/CLERIC) - a Common Lisp Erlang Interface. An implementation of the Erlang distribution protocol, comparable with erl_interface and jinterface. [MIT][200].

## Java ##

* [cl+j](https://common-lisp.net/project/cl-plus-j/)  - 通过 CFFI 到 JVM 的基于 JNI 的接口. 在 Quicklisp 上不可用. 不能可靠地与所有实现一起工作.  [外籍人士][14].

## Objective-C ##

* [objc-lisp-bridge](https://github.com/fiddlerwoaroof/objc-lisp-bridge) -  A portable reader and bridge for interacting with Objective-C and Cocoa. [MIT][200].

## Python ##

* [burgled-batteries](https://github.com/pinterface/burgled-batteries) - A bridge between Python and Common Lisp. The goal is that Lisp programs can use Python libraries. Not available on Quicklisp. [MIT][200].
* [cl4py](https://github.com/marcoheisig/cl4py) <i>- The library cl4py (pronounce as clappy) allows Python programs to call Common Lisp libraries.</i> <b>- 库 cl4py（发音为 clappy）允许 Python 程序调用 Common Lisp 库。</b> <i>[MIT][200].</i> <b>[麻省理工学院][200]。</b>
* [py4cl](https://github.com/bendudson/py4cl)  - 一个允许 Common Lisp 代码访问 Python 库的库. 它基本上是 cl4py 的逆.  [麻省理工学院][200].
* [cl-python](https://github.com/metawilm/cl-python)  - 在 Common Lisp 中实现 Python.  [LLGPL][8].

See also [async-process](https://github.com/cxxxr/async-process/).

## .Net Core

* [Bike](https://github.com/Lovesan/bike) - a cross-platform .Net Core interface. [MIT][200].

## Miscellaneous ##

* [Foil](http://foil.sourceforge.net/) - A foreign object interface; works with the JVM and CLI. Not available on Quicklisp. [CPL 1.0][47].


Game Development
================

* [Xelf](http://xelf.me/) - Extensible game library. Not available on Quicklisp. [GNU LGPL2.1][11].
* [Trial](https://github.com/shirakumo/trial)  - Trial 是一个非常注重模块化的 OpenGL 游戏引擎. 它应该提供一个包含有用的点点滴滴的大型工具包，您可以从中创建游戏.  [zlib][33].
* [cl-mpg123](https://shirakumo.github.io/cl-mpg123) 和 [cl-out123](https://shirakumo.github.io/cl-out123), bindings libraries for libmpg123 和 libout123 respectively, giving you fast 和 easy to use mp3 decoding 和 cross-platform audio output. [zlib][33].
* [trivial-gamekit](https://borodust.org/projects/trivial-gamekit/getting-started/) – with this small framework you would be able to make simple 2D games: draw basic geometric forms, images and text, play sounds and listen to mouse and keyboard input. [MIT][200].
* [cl-gamepad](https://shirakumo.github.io/cl-gamepad) - Access to gamepads and joysticks on Windows, Mac OS, and Linux. [zlib][33].
* [virality](https://github.com/bufferswap/ViralityEngine) - A component-based game engine written in Common Lisp [MIT][200].

Graphics
========

这些是用于处理图形的库，而不是制作 GUI（即小部件工具包），它们有自己的部分.

* :star: [Sketch](https://github.com/vydd/sketch) - A CL framework for the creation of electronic art, graphics, and lots more. [MIT][200].
* [common-cv](https://github.com/byulparan/common-cv) - the OpenCV (Open Source Computer Vision Library) binding library for CommonLisp. No license specified.
* [cl-cairo2](https://github.com/rpav/cl-cairo2) - Cairo bindings. [Boost 1.0][54]
* [cl-gd](http://weitz.de/cl-gd/) - A library providing an interface to the GD graphics library. [FreeBSD][39].
* [cl-horde3d](https://github.com/anwyn/cl-horde3d/) - FFI bindings to the Horde3D graphics library. Not available on Quicklisp. [EPL 1.0][59]
* [cl-jpeg](https://github.com/sharplispers/cl-jpeg) - Baseline JPEG encoder and decoder library. [3-clause BSD][15].
* [cl-liballegro](https://github.com/resttime/cl-liballegro)  - Allegro 5 游戏编程库的接口和绑定.  [zlib][33].
* [cl-opengl](https://github.com/3b/cl-opengl)  - CFFI 绑定到 OpenGL、GLU 和 GLUT API.  [3 条款 BSD][15].
* [cl-sdl2](https://github.com/lispgames/cl-sdl2) - Bindings for SDL2 using C2FFI. [Expat][14].
* [cl-svg](https://github.com/wmannis/cl-svg)  - 用于生成 SVG 文件的基本库.  [外籍人士][14].
* [CLinch](https://github.com/BradWBeer/CLinch) - Common Lisp 2D/3D graphics engine for OpenGL. [FreeBSD][39].
* [donuts](https://github.com/tkych/donuts)  - 用于 Common Lisp 的图形绘制 DSL.  [外籍人士][14].
* [dufy](https://github.com/privet-kitty/dufy) - exact color manipulation and conversion in various color models. [MIT][200].
* [lispbuilder-sdl](https://github.com/lispbuilder/lispbuilder) - A set of bindings for SDL. [Expat][14].
* [lisp-magick-wand](https://github.com/TBRSS/lisp-magick-wand) - ImageMagick bindings. [BSD][15]. Not in Quicklisp.
* [okra](https://www.common-lisp.net/project/okra/manual.html)  - CFFI 绑定到 Ogre. 在 Quicklisp 上不可用.  [3 条款 BSD][15].
* [opticl](https://github.com/slyrus/opticl)  - 一个用于表示和处理图像的库.  [BSD_2 条款][17].
* [Varjo](https://github.com/cbaggers/varjo) - Lisp to GLSL translator. [BSD_2Clause][17].
* [Vecto](http://www.xach.com/lisp/vecto/) - Simple vector drawing library. [FreeBSD][39].
* [zpng](http://www.xach.com/lisp/zpng/) - A library for creating PNG files. [FreeBSD][39].
* [pngload-fast](https://git.mfiano.net/mfiano/pngload) - A PNG (Portable Network Graphics) image format decoder in portable Common Lisp with an emphasis on speed. [MIT][200].
* [cl-cuda](https://github.com/takagi/cl-cuda) - A library to use NVIDIA CUDA in Common Lisp programs. [LLGPL][8].


GUI
===

For an overview and a tutorial on GUI toolkits, see [the Cookbook/GUI](https://lispcookbook.github.io/cl-cookbook/gui.html).

* [LispWork's CAPI](http://www.lispworks.com/products/capi.html) - A portable GUI toolkit, with mobile runtime. Proprietary, but comes with a free version.
*  [Qtools](https://github.com/Shinmera/qtools/) - A Qt toolkit, based on CommonQt. [zlib][33] Also [Qtools-ui](https://github.com/Shinmera/qtools-ui) (premade UI components), with [videos](https://www.youtube.com/watch?v=KwASFOhYta4&index=7&list=PLkDl6Irujx9Mh3BWdBmt4JtIrwYgihTWp).
* :star: [CommonQt](https://github.com/commonqt/commonqt)  - 通过 QtSmoke 为 Qt4 提供的 Common Lisp 绑定.  [自由BSD][39].
* :star: [ltk](http://www.peter-herth.de/ltk/)  - Tk 工具包的绑定.  [LLGPL][8] 或 [GNU LGPL2.1][11].
  * [LTk Examples](https://peterlane.netlify.app/ltk-examples/) - 为 tkdocs 教程提供 LTk 示例。
  * [LTk Plotchart](https://peterlane.netlify.app/ltk-plotchart/) - A wrapper around the tklib/plotchart library to work with LTk. This includes over 20 different chart types (xy-plots, gantt charts, 3d-bar charts etc...).
* [IUP](https://github.com/lispnik/iup/) - CFFI bindings to the [IUP](https://www.tecgraf.puc-rio.br/iup/) Portable User Interface library (pre-ALPHA). IUP is cross-platform (Windows, macOS, GNU/Linux, with new Android, iOs, Cocoa and Web Assembly drivers), has many widgets, has a small api and is actively developed.
* [nodgui](https://notabug.org/cage/nodgui) - Bindings for the Tk toolkit, based on Ltk, with syntax sugar and additional widgets. [LLGPL][8].
* [cl-cffi-gtk](https://github.com/Ferada/cl-cffi-gtk/)  - 绑定 GTK+3.  [GNU LGPL2.1][11].
  - a tutorial: [Learn Common Lisp by Example: GTK GUI with SBCL](https://dev.to/goober99/learn-common-lisp-by-example-gtk-gui-with-sbcl-5e5c)
* [cl-gtk2](https://github.com/dmitryvk/cl-gtk2)  - GTK+2 的绑定.  [LLGPL][8].
* [ceramic](https://ceramic.github.io/)  - 使用 Electron 的桌面网络应用程序.  [外籍人士][14].
  * [Electron-lisp-boilerplate](https://github.com/mikelevins/electron-lisp-boilerplate) - A rudimentary boilerplate for building Electron apps with embedded Lisp helper processes.
  * 电子应用程序骨架： [electron-sbcl-sqlite](https://github.com/mikelevins/electron-sbcl-sqlite/)
* [CocoaInterface](https://github.com/plkrueger/CocoaInterface/) -
Cocoa interface for Clozure Common Lisp. Build Cocoa user interface
windows dynamically using Lisp code and bypass the typical Xcode
过程. 它有
[good documentation and a tutorial](https://github.com/plkrueger/CocoaInterface/blob/master/Documentation/UserInterfaceTutorial.pdf).
* [McCLIM](https://common-lisp.net/project/mcclim/) - An implementation of the Common Lisp Interface Manager, version II. [GNU LGPL2.1][11].
* [cl-webkit](https://github.com/joachifm/cl-webkit)  - 与 WebKitGTK+ 的绑定. 还为应用程序添加 Web 浏览功能，利用 WebKit 浏览引擎的全部功能.  [麻省理工学院][200].
* [ftw](https://github.com/fjames86/ftw) - A Win32 GUI library. [MIT][200].
* [eql, eql5, eql5-android](https://gitlab.com/eql) - Embedded Qt4 and Qt5 Lisp, embedded in ECL, embeddable in Qt. Port of EQL5 to the Android platform. [MIT][200].
* [bodge-nuklear](https://github.com/borodust/bodge-nuklear) - 包装在 [Nuklear](https://github.com/vurtun/nuklear) immediate mode GUI library. [MIT][200].
* [Allegro's Common Graphics](https://franz.com/products/allegro-common-lisp/acl_gui_tools.lhtml) - 用于为 Windows、Mac 和 Linux 编写窗口化 GUI 的函数库. 所有权.

See also this [demo to use Java Swing from ABCL](https://github.com/defunkydrummer/abcl-jazz).


Implementations
===============

* :star: [SBCL](http://www.sbcl.org/index.html)  - CMUCL 的一个分支； 编译成机器码.  [符合标准][13]. 公共领域，有一些部分在 [Expat][14] 和 [3-clause BSD][15] 下.
* :star: [CCL](https://github.com/CodyReichert/awesome-cl/blob/master///ccl.clozure.com/)  - Clozure Common Lisp； 仅编译器实现，生成本机代码.  [LLGPL][8].
* [ECL](https://common-lisp.net/project/ecl/) - Embeddable Common Lisp; compiles to C. [GNU LGPL2.1][11].
* [ABCL](https://common-lisp.net/project/armedbear/)  - 武装熊 Common Lisp； 以 JVM 为目标，编译为字节码.  [标准一致性][4].  [GNU GPL3][2] 与 [类路径异常][3].
* [CMUCL](https://github.com/CodyReichert/awesome-cl/blob/master///www.cons.org/cmucl/) - An implementation from Carnegie Mellon University. Public domain.
* [GNU CLISP](http://www.clisp.org/) - A GNU implementation; contains a compiler and an interpreter. [Standard conformance][6]. [GNU GPL3][2].
* [CLASP](https://github.com/drmeister/clasp) - a new Common Lisp implementation that seamlessly interoperates with C++ libraries and programs using LLVM for compilation to native code. This allows Clasp to take advantage of a vast array of preexisting libraries and programs, such as out of the scientific computing ecosystem. [LGPL2.1][11] (and others).
* [Corman Lisp](https://github.com/sharplispers/cormanlisp) - a Common Lisp development environment for Microsoft Windows running on Intel platforms. [MIT][200].

Proprietary:

* [LispWorks](http://www.lispworks.com/) - an integrated cross-platform development tool for Common Lisp.
* [Allegro CL](https://franz.com/products/allegro-common-lisp/) - provides the full ANSI Common Lisp standard with many extensions.
* [MOCL](https://wukix.com/mocl) - CL as a library for mobile devices (iOS & Android) and OSX.

JSON
====

* [jonathan](https://github.com/Rudolph-Miller/jonathan) - A JSON encoder and decoder. [MIT][200].
* [cl-json](https://github.com/sharplispers/cl-json) - A highly customizable JSON encoder and decoder. [MIT][14].
* [jsown](https://github.com/madnificent/jsown)  - JSON 格式的读取器和写入器.  [外籍人士][14].
* [json-mop](https://github.com/gschjetne/json-mop)  - 用于桥接 CLOS 和 JSON 对象的元类.  [麻省理工学院][200].
* [cl-json-pointer](https://github.com/y2q-actionman/cl-json-pointer)  - JSON 指针实现.  [麻省理工学院][200].

See also this [extensive comparison](https://sites.google.com/site/sabraonthehill/home/json-libraries) of JSON libraries.

YAML
====

* [cl-yacclyaml](https://github.com/mabragor/cl-yaclyaml)  - 一个纯 lisp YAML 处理器（加载器，但还不是转储器）.  [GPL3][2].
* [cl-yaml](https://github.com/eudoxia0/cl-yaml.git) - a YAML parser and emitter built on top of libyaml. [MIT][200].


Language extensions
===================

* :star: [alexandria](https://common-lisp.net/project/alexandria/) - A general-purpose utility library. Public domain.
* [serapeum](https://github.com/TBRSS/serapeum/)  - 另一个通用实用程序库.  [外籍人士][14].
* [rutils](https://github.com/vseloved/rutils)  - Common Lisp 的激进但合理的语法实用程序.  [麻省理工学院][200].
* [anaphora](https://common-lisp.net/project/anaphora/)  - 照应宏的集合. 公共区域.
* :star: [trivia](https://github.com/guicho271828/trivia/)  - 优化的模式匹配库.  [LLGPL][8].
* [arrow-macros](https://github.com/hipeta/arrow-macros) - Clojure-like threading macros. [MIT][200].
* [dissect](https://shinmera.github.io/dissect)  - 当许多项目使用“trivial-backtrace”系统时，它只是给他们一个带有回溯的字符串，Dissect 允许您捕获、步进和完全检查各种 Lisp 实现的堆栈跟踪. 对于日志记录和其他自动继续执行的情况也非常有用，但是当前堆栈的信息对于存储在某处仍然有用.  [zlib][33].
* [generic-cl](https://github.com/alex-gutev/generic-cl/) - Generic function interface to standard Common Lisp functions (equality, comparison, arithmetic, objects, iterator, sequences,…). [MIT][200]. See also the more lightweight [generic-comparability](https://github.com/pnathan/generic-comparability). [LLGPL][8].
* [hu.dwim.walker](https://quickref.common-lisp.net/hu.dwim.walker.html) - a code walker and unwalker (aka AST parser and unparser). [BSD][15]. See also [this blog post](http://40ants.com/lisp-project-of-the-day/2020/04/0044-hu.dwim.walker.html).

可移植层
------------------

A large list of portability layers [is collected here](https://shinmera.github.io/portability/). Here are some of them:

* [trivial-arguments](https://github.com/Shinmera/trivial-arguments) - A portable library to retrieve the arguments list of a function. [zlib][33].
* [definitions](https://github.com/Shinmera/definitions) - a general definitions introspection library. It gives you the ability to retrieve definitions or bindings associated with designators such as symbols, packages, and names in general. [zlib][33].

更改语法
-------------------

* [cl21](https://github.com/cl21/cl21) - An experimental project to move Common Lisp into the 21st century. [Expat][14].
* [clamp](https://github.com/malisper/Clamp)  - Arc 语言对 Common Lisp 的简洁性和简洁性.  [艺术许可证 2.0][51].
* [cl-syntax](https://github.com/m2ym/cl-syntax) - Reader syntax conventions. [LLGPL][8].
* [cl-2dsyntax](http://www.cliki.net/cl-2dsyntax) - An indentation-sensitive reader system. Not available on Quicklisp. Public domain.
* [cl-annot](https://github.com/m2ym/cl-annot) - Python-like annotations for Common Lisp. [LLGPL][8].
* :star: [cl-interpol](https://github.com/edicl/cl-interpol/)  - 一组阅读器修改以允许字符串插值.  [BSD][15].
* [pythonic-string-reader](https://github.com/smithzvk/pythonic-string-reader)  - 受 Python 的三个引号字符串启发的简单且不显眼的读取表修改.  [BSD_3 条款][15].
* [cl-reader](https://github.com/digikar99/reader) - A utility library
intended at providing reader macros for lambdas, mapping, accessors,
hash-tables and hash-sets. [MIT][200].


CLOS extensions
---------------

* :star: [closer-mop](http://cliki.net/closer-mop) - A compatibility layer that rectifies many absent or incorrect MOP features. [Expat][14].
* [defclass-std](https://github.com/EuAndreh/defclass-std) - a shortcut macro to write DEFCLASS forms quickly. [LLGPL][8].
* [specialization-store](https://github.com/markcox80/specialization-store/) - generic functions based on types. Simplified BSD License variant.
* [filtered-functions](https://github.com/pcostanza/filtered-functions) - enable the use of arbitrary predicates for selecting and applying methods. [MIT][200].
* [inlined-generic-function](https://github.com/guicho271828/inlined-generic-function) -
Bringing the speed of Static Dispatch to CLOS. [LLGPL][8].
* [static-dispatch](https://github.com/alex-gutev/static-dispatch) - allows standard generic function dispatch to be performed statically (at compile time) rather than dynamically (runtime). This is similar to what is known as "overloading" in languages such as C++ and Java. [MIT][200].
* [dynamic-mixins](https://github.com/rpav/dynamic-mixins) - simple, dynamic class combination. [BSD_2Clause][17].
* [fast-generic-functions](https://github.com/marcoheisig/fast-generic-functions)  - 密封您的通用功能以进一步提高性能.  [麻省理工学院][200].
* [polymorphic functions](https://github.com/digikar99/polymorphic-functions) - A function type to dispatch on types instead of classes with partial support for dispatching on optional and keyword argument types. Still experimental (May, 2021). [MIT][200].
  - polymorphic-functions dispatch on the types of the arguments supplied to it. This helps dispatching on specialized arrays as well as user-defined types.
  - for differences with specialization-store and fast-generic-functions, see its README.

并且：

* [slot-extra-options](https://github.com/some-mthfka/slot-extra-options) - lets you build a metaclass which in turn lets you specify extra slot options in its classes. [LGPL3][9].

Function extensions
-------------------

* [cl-hooks](https://github.com/scymtym/architecture.hooks/)  - Hooks 扩展点机制（如已知的，例如，来自 GNU Emacs）.  LGPL.
* [method-hooks](https://gitlab.com/Gnuxie/method-hooks)  - 当 CLOS 方法组合每个方法只允许一个钩子时，这个库允许任意数量的钩子.  Mozilla 公共许可证.
* [cl-advice](https://github.com/lisp-mirror/budden-tools/blob/213ab2b52a1b0c0b496efd30c3b5143f5c8e1ff2/cl-advice/README.md)  - SBCL、CCL、LispWorks 和 Allegro 的可移植层建议库的尝试. 不在 Quicklisp 中.

See also hooks in Serapeum.

Iteration
---------

* :star: [iterate](https://common-lisp.net/project/iterate/) - An iteration construct for Common Lisp which is extensible and Lispier. [MIT][200].
* [for](https://shinmera.github.io/for/) - A concise, lispy and extensible iteration macro. Unlike loop it is extensible and sensible, and unlike iterate it does not require code-walking and is easier to extend. [zlib][33].
* [series](https://github.com/tokenrove/series/wiki) - Functional style without any runtime penalty at all. [MIT][200].
* [gmap](https://github.com/slburson/misc-extensions/blob/master/src/gmap.lisp) - A concise and extensible iteration facility that has the advantage of integrating well with FSet (see the Data Structures section), as it was written by the same author. In Quicklisp as part of `misc-extensions`. Public domain.
* [trivial-do](https://github.com/yitzchak/trivial-do/)  - Common Lisp 的附加 dolist 样式宏.  [麻省理工学院][200].
* [doplus](https://github.com/alessiostalla/doplus) – 另一个可扩展的迭代库，类似于 :for.
* [snakes](https://github.com/BnMcGn/snakes) - Python style generators for Common Lisp. Includes a port of itertools. [Apache2][89].
* [picl](https://github.com/anlsh/picl)  - Python 的 itertools 包的（几乎）完整端口，在适用的情况下具有惰性，并且不依赖于 cl-cont.  [麻省理工学院][200].
* [gtwiwtg](https://github.com/cbeo/gtwiwtg)  - 一个惰性序列库. 类似于“系列”，但不完整. 然而，它有一个“现代”API，其中包含易于使用的 `take`、`filter`、`for`、`fold` 等内容.


Lambda shorthands
-----------------

* [fn](https://github.com/cbaggers/fn) - a couple of lambda shorthand macros. `(fn* (+ _ _))  -->  (lambda (_) (+ _ _))`. Public domain.
* [f-underscore](https://gitlab.common-lisp.net/bpm/f-underscore) - a tiny library of functional programming utils. `(f_ (+ _ _)) -> (lambda (_) (+ _ _))`. Public domain.
* [cl-punch](https://github.com/windymelt/cl-punch/) - Scala-like anonymous lambda literals. `(mapcar ^(* 2 _) '(1 2 3 4 5))`. [MIT][200].


另见 CL21 和 [Rutils](https://github.com/vseloved/rutils).



非确定性逻辑编程
------------------------------------

* [cl-prolog2](https://github.com/guicho271828/cl-prolog2)  - 来自 Common Lisp 的 ISO Prolog 实现的通用接口.  [麻省理工学院][200].
* [Screamer](https://github.com/nikodemus/screamer) - 增加通用
  Lisp with practically all of the functionality of both Prolog and
  constraint logic programming
  languages. [Blog post](https://chriskohlhepp.wordpress.com/reasoning-systems/specification-driven-programming-in-common-lisp/)
  solving Project Euler puzzles. [MIT][200].
* [Screamer+](https://github.com/yakovzaytsev/screamer-plus) - increasing the expressiveness of SCREAMER. [MIT][200].
* [Temperance](https://github.com/sjl/temperance) - logic programming. [MIT][200]. A focus on performance, with General Game Playing in mind.

Reactive programming
--------------------

* [Cells](https://github.com/kennytilton/cells)  - 数据流编程范式的实现，CLOS 的反应式电子表格般的表现力. 用于构建一个 [algebra learning system](http://tiltontec.com/). With [documentation](https://github.com/stefano/cells-doc/). Lisp LGPL.

合约编程
--------------------

* [quid-pro-quo](https://github.com/sellout/quid-pro-quo) - a contract
   Eiffel&#39;s Design by Contract™ 风格的编程库. 公共区域.

Typing
------

*  [Coalton](https://github.com/coalton-lang/coalton/) - an efficient, statically typed functional programming language that supercharges Common Lisp. [MIT][200].
* [cl-algebraic-data-type](https://github.com/stylewarning/cl-algebraic-data-type) - A library for defining algebraic data types in a similar spirit to Haskell or ML. [3-clause BSD][15].
*  [trivial-types](https://github.com/m2ym/trivial-types) - provides missing but important type definitions such as `proper-list`, `association-list`, `property-list` and `tuple`. [LLGPL][8].
* [defstar](https://bitbucket.org/eeeickythump/defstar/src/master/)  - 一组宏，用于轻松包含 lambda 列表中参数的类型声明.  [GNU GPL3][2]


Learning and Tutorials
=====================

## Online ##

Beginner
--------

* [Learn X in Y minutes - Where X = Common Lisp](https://learnxinyminutes.com/docs/common-lisp/) - Small Common Lisp tutorial covering the essentials.
* [Lisp Koans][201] - The project guides the learner progressively through many Common Lisp language features.
* [Practical Common Lisp][206] - A good introductory text to Common Lisp, with practical examples. Better read with [a Firefox add-on](https://github.com/vale981/practical-cl-beautified).
* [Common LISP: A Gentle Introduction to Symbolic Computation](http://www.cs.cmu.edu/afs/cs.cmu.edu/user/dst/www/LispBook/index.html) - 一个很好的语言介绍.
* [Successful Lisp](http://successful-lisp.blogspot.com/) - A good book for beginners with some programming background.
* [Lisp Quickstart](https://cs.gmu.edu/~sean/lisp/LispTutorial.html) - 一个快速入门和编写 Common Lisp 的好教程.
* [Casting SPELs in LISP](http://www.lisperati.com/casting.html) - A fun way to learn LISP while reading a comic book.
  > Thanks for supporting my work on Udemy. Also note that I release free coupons from time to time, and that Udemy often proposes drastic promotions, but you can ask me a free coupon too.

Intermediate
------------

* [The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/)
* [Lisp Tips](https://github.com/lisp-tips/lisp-tips/issues/)  - 一个包含有用提示和技巧的博客. 的延续 [Common Lisp tips](http://lisptips.com/).
* [Lisp project of the day](http://40ants.com/lisp-project-of-the-day/) - A blog showcasing many Lisp libraries.

Advanced
--------

* [Let Over Lambda][156] - A book on advanced macro techniques. The first six chapters are available online.
* [On Lisp](http://www.paulgraham.com/onlisp.html) - Paul Graham's amazing book on Lisp macros (and other interesting things).
* [Programming Algorithms in Lisp](https://link.springer.com/book/10.1007/978-1-4842-6428-7) - 更新版本的“[Programming Algorithms](https://leanpub.com/progalgs)"; A comprehensive guide to writing efficient programs with data structures and algorithms in Lisp.

Web开发
--------

* [Lisp for the Web](https://leanpub.com/lispweb) - A book that walks you through building a voting web application in three tiers.
* [Lisp Web Tales](https://leanpub.com/lispwebtales) - Simple tutorials using [hunchentoot](http://edicl.github.io/hunchentoot/), [cl-redis](https://github.com/vseloved/cl-redis), [restas](https://github.com/archimag/restas), [SEXML](https://github.com/madnificent/SEXML), [Postmodern](https://github.com/marijnh/Postmodern), and more.
* [Section on Web Development in The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/web.html) - 介绍性教程，涵盖 Web 服务器设置、路由、weblocks、模板、错误处理、打包、热重载、数据库连接和部署，以及当前 lisp Web 开发生态系统中的其他主题.

Reference
---------

* [Common Lisp Quick Reference](http://clqr.boundp.org/index.html) - A distilled, pocket-size version of the ANSI CL spec. Available for download as a PDF.
* [CLHS](http://www.lispworks.com/documentation/lw50/CLHS/Front/index.htm) - The Common Lisp HyperSpec; the ANSI CL standard, in hypertext form.
* [CLOS MOP specification](https://clos-mop.hexstreamsoft.com/) - A modern public domain online version of chapters 5 and 6 of The Art of the Metaobject Protocol
* [Common Lisp Standard Draft (pdf)](https://franz.com/support/documentation/cl-ansi-standard-draft-w-sidebar.pdf) - The standard draft of the Common Lisp specifications, in a well formatted PDF with a sidebar.
* [Common Lisp the Language](http://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html) - ANSI 规范之前的 Common Lisp 的原始标准.
* [Minispec](https://lamberta.github.io/minispec/)  - 更友好但不完整的 CLHS 版本. 还包含一些常用 CL 库（例如 Alexandria）的文档.
* [Simplified Common Lisp reference](http://jtra.cz/stuff/lisp/sclr/index.html) - CLHS 的简化版本.

## Offline ##

CLHS 可通过 [archive](https://github.com/CodyReichert/awesome-cl/blob/master/ftp://ftp.lispworks.com/pub/software_tools/reference/HyperSpec-7-0.tar.gz) 和 as doc sets in [Dash](https://kapeli.com/dash), [Zeal](https://zealdocs.org/) 和 [Velocity](https://velocity.silverlakesoftware.com/).

Beginner
--------

* [Land of Lisp](http://landoflisp.com/) - A fun, game-oriented introduction to Common Lisp.
* [Practical Common Lisp][206] - A good introductory text to Common Lisp, with practical examples.

Intermediate
------------

* [ANSI Common Lisp](http://www.paulgraham.com/acl.html) - A thorough, practical covering of the entire language, with exercises. Not recommended as a starter text, due to [some caveats][20].
* [Common Lisp Recipes](http://weitz.de/cl-recipes/) - **Common Lisp Recipes** is a collection of solutions to problems and answers to questions you are likely to encounter when writing real-world applications in Common Lisp. Published in 2015.

Advanced
--------

<i>* [Let Over Lambda][156] - A book on advanced macro techniques.</i> <b>* [Let Over Lambda][156] - 一本关于高级宏技术的书。</b> <i>All eight chapters are available in the print copy.</i><b>所有八章都可以在印刷版中找到。</b>
* [Object-Oriented Programming in Common Lisp: A Programmer's Guide to CLOS][21] - An old, but very thorough book on CLOS.
* [Paradigms of Artificial Intelligence Programming: Case Studies in Common Lisp][157] - A book on programming AI that covers some advanced Lisp.

其他书籍
-----------

* [Building Problem Solvers](https://www.qrg.northwestern.edu/bps/readme.html) ([PDF](http://www.qrg.northwestern.edu/bps/BPS-Searchable.pdf)) 由 Ken Forbus 和 Johan de Kleer 撰写，由 MIT Press 免费提供——这是一本在标准人工智能文本中独一无二的书籍，它结合了科学和工程、理论和工艺来描述 AI 推理系统的构建，并包括说明这些想法的代码.

Community
---------

* [/r/Common_Lisp](https://www.reddit.com/r/Common_Lisp/) - subreddit about Common Lisp
* [/r/learnlisp](https://www.reddit.com/r/learnlisp/) - a subreddit to ask questions and get help about Lisp
* [common-lisp.net](https://common-lisp.net)
* [lisp-lang.org](https://lisp-lang.org/)
* [Lisp Discord Server](https://discord.gg/hhk46CE)
* [#commonlisp](https://irclog.tymoon.eu/libera/%23commonlisp) 在 Libera Chat - 主要的 Common Lisp IRC 频道.
* [#lisp](https://irclog.tymoon.eu/libera/%23lisp) on Libera Chat - IRC channel for all Lisp dialects.
* #clschool on Libera Chat - IRC channel for learning Common Lisp.
* #lispcafe on Libera Chat - IRC channel for off-topic discussions.
* [Common Lisp chat](https://chat.hexstreamsoft.com/) - Keybase team with well-defined rules and retention policies.

Library Manager
===============

* :star: [Quicklisp][16] - A library manager containing many libraries, with easy depencency management. [Expat][14].
* [CLPM](https://gitlab.common-lisp.net/clpm/clpm) - A package manager for Common Lisp that strives to cleanly separate the package manager process itself from the client image that uses it. [BSD_2Clause][17].
* [Ultralisp](http://ultralisp.org/) - A Quicklisp distribution which updates every 5 minutes and to which one can add his project in one click. [BSD][15].
* [Roswell](https://github.com/roswell/roswell) - a Lisp implementation installer, script launcher and more. [MIT][200].
* [Qlot](https://github.com/fukamachi/qlot) - A project-local library installer, similar to Bundler or Carton. [Expat][14].
* [Quicksys](https://lisp.com.br/quicksys/) - install systems from multiple Quicklisp distributions. [MIT][200].
* [Quickutil](https://github.com/tarballs-are-good/quickutil) - A utility manager, similar to Quicklisp, but for small utilities rather than whole libraries. [3-clause BSD][15].

might help:

* [quick-patch](https://github.com/tdrhq/quick-patch/)  - 无需使用 git 子模块即可轻松覆盖 quicklisp 项目.  MPL-2.0.
* [print-licenses](https://github.com/vindarel/print-licenses) - print licenses used by a project and its dependencies. [MIT][200].

### Interfaces to other package managers

* [linux-packaging](https://gitlab.com/ralt/linux-packaging) - build .deb, .rpm or .pkg packages for your application with a single ASDF declaration. Uses fpm under the hood. [MIT][200].
* [qldeb](https://github.com/ralt/qldeb) - Quicklisp 系统到 debian 包，以及 [deb-packager](https://github.com/ralt/deb-packager) （只需通过定义一个 s 表达式来创建一个 debian 包）和一个介绍性 [blog post](http://margaine.com/2015/12/22/quicklisp-packagecloud-debian-packages.html) . 两者都 [麻省理工学院] [200].
* [ql-to-deb](https://github.com/dimitri/ql-to-deb) -  Update cl-* debian packages from Quicklisp releases. WTFPL.
* [dh-quicklisp-buildapp](https://github.com/ralt/dh-quicklisp-buildapp) - debhelper utility to let you compile your quicklisp-based Common Lisp code into a buildapp binary in a .deb with almost no effort. [MIT][200].
* [cl-brewer](https://github.com/can3p/cl-brewer)  - 用于（命令行）通用 lisp 应用程序的自制公式生成器. 公共区域.
* [flatpack-common-lisp](https://gitlab.com/ralph-schleicher/flatpak-common-lisp) - A BuildStream project for building Flatpak based runtime environments for Common Lisp applications.


See also [asdf-sbcl](https://github.com/smashedtoatoms/asdf-sbcl), a plugin for the universal package manager.


机器学习
================

* [MGL](https://github.com/melisgl/mgl)  - 用于反向传播神经网络、玻尔兹曼机、高斯过程等的机器学习库.  [麻省理工学院][200].
  * some parts originally contributed by Ravenpack International.
  - 由其使用 [author](https://github.com/melisgl) 到 [win](https://github.com/melisgl/higgsml) the Higgs Boson Machine Learning Challenge.
* [clml](https://github.com/mmaul/clml) - originally developed by Mathematicl Systems Inc., a Japanese company. With a [tutorial](https://mmaul.github.io/clml.tutorials//2015/08/08/CLML-Time-Series-Part-1.html). [LLGPL][8].
* [antik](https://www.common-lisp.net/project/antik/)  - Common Lisp 中科学和工程计算的基础.  GPL. 还 [mgl-mat](https://github.com/melisgl/mgl-mat) 和 [LLA](https://github.com/tpapp/lla).

Credit: [borretti.me' state of CL ecosystem 2015](http://borretti.me/article/common-lisp-sotu-2015#machine-learning).


Natural Language Processing
===========================

* [cl-nlp](https://github.com/vseloved/cl-nlp) - Natural language processing toolset. [Apache2.0][89].
* [babel2](https://github.com/lucas8/Babel2/) - A Fluid Construction Grammar implementation, computational framework, and unification-based grammar formalism [Apache2.0][89].
* [sparser](https://github.com/ddmcdonald/sparser)  - 英语的自然语言理解系统.  [日食][209].



Network and Internet
====================

See [Cliki](http://www.cliki.net/Web) for more.

HTTP 客户端
------------
*  [Dexador](https://github.com/fukamachi/dexador) - An HTTP client, that aims at replacing Drakma. [MIT][200].
* [Carrier](https://github.com/orthecreedence/carrier)  - 基于 cl-async 和 fast-http 构建的轻量级异步 HTTP 客户端.  [麻省理工学院][200].
* [fast-http](https://github.com/fukamachi/fast-http) - A fast HTTP request/response parser for Common Lisp. [MIT][200].


HTTP Servers
------------
* [Clack](https://github.com/fukamachi/clack) - A web application environment inspired by Rack and WSGI. [LLGPL][8].  Provides a unified interface to a webserver of choice (default is Hunchentoot). With more [getting started guide](https://jasom.github.io/clack-tutorial/posts/getting-started-with-clack/).
* :star: [Hunchentoot](http://weitz.de/hunchentoot/)  - 网络服务器.  [2 子句 BSD][207]
* [zaserve](https://github.com/gendl/aserve) - A portable fork of AllegroServe, by Franz Inc.  [LLGPL][8].
* [wookie](https://github.com/orthecreedence/wookie) - Asynchronous HTTP server. [Expat][14].
* [woo](https://github.com/fukamachi/woo) - A fast non-blocking HTTP server on top of libev. [MIT][200].
* [cl-http2-protocol](https://github.com/akamai/cl-http2-protocol) - a pure Common Lisp transport agnostic implementation of the HTTP/2 protocol at draft-14. [MIT][200].

### Hunchentoot plugins

*  [easy-routes](https://github.com/mmontone/easy-routes)  - Hunchentoot 之上的路线处理系统. 它支持基于 HTTP 方法的调度、从 url 路径提取参数、装饰器、从路由名称生成 url 等 [MIT][200].
* [hunchentoot-cgi](https://github.com/slyrus/hunchentoot-cgi) - a library for executing CGI scripts from the hunchentoot webserver. [BSD][207].
* [hunchentoot-multi-acceptor](https://github.com/moderninterpreters/hunchentoot-multi-acceptor/) - Route multiple domains (virtual hosts) on a single hunchentoot acceptor using a single port. [Apache2.0][89].
* [hunchentoot-auth](https://github.com/slyrus/hunchentoot-auth)  - 使用密码实现用户身份验证.  [BSD][207].
* [hunchentoot-errors](https://github.com/mmontone/hunchentoot-errors)  - 使用请求和会话信息增强 Hunchentoot 错误页面和日志.  [麻省理工学院][200].

### Clack plugins

* [clack-errors](https://github.com/eudoxia0/clack-errors) - Error page middleware for Clack. [LLGPL][8].
* [clath](https://github.com/BnMcGn/clath) - 单点登录
  middleware for Clack. It allows basic login with OAuth1.0a, OAuth2
  and OpenID. At the time of writing, it supports authentication from
  Google, Twitter, LinkedIn, StackExchange, Reddit and Github. [Apache2.0][89].
* [clack-pretend](https://github.com/BnMcGn/clack-pretend) - 一个测试
  and debugging tool for clack. [Apache2.0][89].
* [hermetic](https://github.com/eudoxia0/hermetic) - Security for Clack-based web applications. [Expat][14].
* [live-reload](https://github.com/knobo/live-reload) - Live reload prototype for clack. [LLGPL][8].
* [clack-static-asset-middleware](https://github.com/fisxoj/clack-static-asset-middleware) - a cache-busting static asset middleware for the clack. [MIT][200].

网络框架
--------------

* [Caveman](https://github.com/fukamachi/caveman) - A powerful web framework. [LLGPL][8].
  示例项目： [Quickdocs](https://github.com/quickdocs)
* [hh-web](https://github.com/hargettp/hh-web) - Framework for building modern web apps. [Expat][14].
* [ningle](https://github.com/fukamachi/ningle) - A super-micro web framework. [LLGPL][8]. [ninglex](https://github.com/defunkydrummer/ninglex), an extended and noob-friendly ningle (mostly easier handling of query parameters). [MIT][200].
* [radiance](https://github.com/Shirakumo/radiance)  - 一个网络应用环境和框架.  [zlib][33].
* [Lucerne](https://github.com/eudoxia0/lucerne)  - 受 Flask 启发，基于 Clack 构建的最小 Web 框架.  [麻省理工学院][200].
* [Snooze](https://github.com/joaotavora/snooze) - A RESTful web framework. Web server agnostic. Currently has support for Hunchentoot and Clack. Routes are just functions and HTTP conditions are just Lisp conditions. [LLGPL][8].

以 REST 为中心的框架：

* [cl-rest-server](https://github.com/mmontone/cl-rest-server) - a library for writing REST web APIs. Features validation with schemas, annotations for logging, caching, permissions or authentication, documentation via Swagger, etc. [MIT][200].
* [cl-odata-client](https://github.com/copyleft/cl-odata-client) - 用于访问的 Common Lisp 客户端库 [OData services](https://www.odata.org). [MIT][200].

Authentication plugins (in addition to the Clack plugins above):

* [cl-cas](https://github.com/fferrere/cl-cas) - 帮助图书馆 [CAS authenticaton](https://apereo.github.io/cas/6.0.x/protocol/CAS-Protocol.html) to Common Lisp web applications.
* [cas-middleware](https://github.com/fferrere/cas-middleware) - CAS authenticaton middleware for Caveman.
  * [cas-demo](https://github.com/fferrere/cas-demo) - a demo project.

还有更多的项目，或多或少停产但很有趣. 查看其他资源.

同构网络框架
-------------------------

* [CLOG](https://github.com/rabbibotton/clog)  - Common Lisp Omnificent GUI. 使用 Web 技术为本地或远程应用程序生成图形用户界面.  [BSD_3 条款][15].
  - CLOG is based on the ideas of GNOGA, a framework the author wrote for Ada and used in commercial production code since 2013.
* [Interactive SSR](https://github.com/interactive-ssr/client/blob/master/main.org/) - ISSR allows you to make interactive web pages without writing client scripting. No knowledge about Javascript or DOM is necessary.
  - 它与 Phoenix LiveView 或 Hotwire 没有什么不同.
* [Weblocks](https://github.com/40ants/weblocks)  - 一个基于小部件的框架，具有“解决 JavaScript 问题”的内置 ajax 更新机制.  [LLGPL][8].


资产管理
-----------------

* [Rock](https://github.com/eudoxia0/rock) - an asset manager for
  Common Lisp. It's basically a combination of Bower and
  网络资产.  [麻省理工学院][200].


解析html
------------
* 👍 [Plump][71] - A lenient HTML/XML parser, tolerant on malformed markup. [zlib][33]. Best used with [lquery][72] and [clss](https://github.com/Shinmera/CLSS).

查询 HTML/DOM
-----------------
 * [lquery][72] - 一个类似 jQuery 的 HTML/DOM 操作库.  [zlib][33].

See also the XML section below for xpath libraries and more.


HTML generators and templates
-----------------------------
*  [spinneret](https://github.com/ruricolist/spinneret) - Common Lisp HTML5 generator. [Expat][14].
* :star: [cl-who](http://weitz.de/cl-who/) - The venerable HTML generator. [FreeBSD][39].
* :star: [Djula](https://github.com/mmontone/djula) - A port of Django's template engine to Common Lisp. [Expat][14].
* [eco](https://github.com/eudoxia0/eco)  - 快速、灵活、对设计师友好的模板引擎.  [外籍人士][14].
* [TEN](https://github.com/mmontone/ten) - the completness of Djula meets the usability of Eco. [MIT][200].
* [cl-closure-template](https://github.com/archimag/cl-closure-template) - Implementation of Google's Closure templates. [LLGPL][8].
* [flute](https://github.com/ailisp/flute)  - 一个易于组合的 HTML5 生成库，具有最简单的语法.  [麻省理工学院][200].
* [clip](https://shinmera.github.io/clip) - An HTML template processor where the templates are written in HTML. [zlib][33].
* [lsx](https://github.com/fukamachi/lsx/) 和 [markup](https://github.com/moderninterpreters/markup)  - 两个类似 JSX 的模板引擎，其中 HTML 标记是 Common Lisp 代码.  `markup` 带有一个 Emacs 包.

URI handling
------------

* [quri](https://github.com/fukamachi/quri) - Another URI library for
  常见的 Lisp. 支持用户信息、IPv6 主机名、编码/解码
  utilities,… [BSD_3Clause][15].
* [cl-slug](https://github.com/EuAndreh/cl-slug) - a small library to make slugs, mainly for URIs, transform in CamelCase, remove accentuation and punctuation, for english and beyound. [LLGPL][8].

Javascript
----------

* :star: [Parenscript](https://common-lisp.net/project/parenscript/)  - 从 Common Lisp 到 Javascript 的翻译器.  [3 条款 BSD][15]. 看 [Trident-mode](https://github.com/johnmastro/trident-mode.el)，一种 Emacs 模式，提供与浏览器的实时交互.[unlicence][5].
  * [paren6](https://github.com/BnMcGn/paren6/) - 一组用于 Parenscript 的 ES6 宏.
* [parse-js](http://marijnhaverbeke.nl/parse-js/) - A package for parsing ECMAScript 3. [zlib][33].
* [JSCL](https://github.com/jscl-project/jscl) - A CL-to-JS compiler designed to be self-hosting from day one. Lacks CLOS, format and loop.
* [CL-JavaScript](http://marijnhaverbeke.nl/cl-javascript/)  - 从 Javascript 到 Common Lisp 的翻译器. 在 Quicklisp 上不可用.  [外籍人士][14].
* [Wuwei](https://github.com/mtravers/wuwei/) - A toolkit to build Ajax-based web pages. [MIT][200].
* [SmackJack](https://github.com/aarvid/SmackJack) - An Ajax Common Lisp Library using parenscript to generate javascript and hunchentoot (for now) as the web server. Also allows a server-side lisp function to call a client-side parenscript one. [MIT][200].
* [Panic](https://github.com/michaeljforster/panic) ，一个用于 React 的 Parenscript 库. 不在 Quicklisp 中.  [麻省理工学院][200]. 它 [TodoMVC example](https://github.com/40ants/todomvc/blob/common-lisp-example/examples/common-lisp-react/src/app.lisp).
* [remote-js](https://github.com/ceramic/remote-js) - send JavaScript from Common Lisp to a browser. [MIT][200].
* [sigil](https://github.com/BnMcGn/sigil) - A Parenscript to
Javascript command line compiler and REPL. [MIT][200].

See also
[trident-mode](https://github.com/johnmastro/trident-mode.el), 一个 Emacs
minor mode for live Parenscript interaction.


Email
-----

* [trivial-imap](https://github.com/40ants/trivial-imap) - tries to make easy some common cases of working with IMAP servers, like reading emails from the server. A thin wrapper over post-office library (which is a fork of Franz's cl-imap). [BSD][15].
* [mailgun](https://github.com/40ants/mailgun)  - 通过 mailgun.com 发布 HTML 电子邮件的薄包装器.  [无牌][5].
* [mito-email-auth](https://github.com/40ants/mito-email-auth) - Helper to authenticate a website's users by sending them unique code by email.


Websockets
----------

*  [usocket](https://github.com/usocket/usocket)  - 一个可移植的 TCP 和 UDP 套接字接口.  [外籍人士][14].
* [websocket-driver](https://github.com/fukamachi/websocket-driver)  - WebSocket 服务器/客户端实现，后端不可知（Clack）.  [3 条款 BSD][15].
* [Portal](https://github.com/charJe/portal)  - 使用 usocket 的 Common Lisp 的便携式 websocket.  [LLGPL][8].

See more [on cliki](http://www.cliki.net/site/search?query=websockets).

Static site generators
----------------------

* [coleslaw](https://github.com/kingcons/coleslaw) 及其
  [coleslaw-cli](https://github.com/40ants/coleslaw-cli) - 灵活
  类似于 Frog、Jekyll 或 Hakyll 的 Lisp 博客软件.  [BSD][15].

Deployment
----------

* [heroku-buildpack-common-lisp](https://gitlab.com/duncan-bayne/heroku-buildpack-common-lisp) - A Heroku buildpack that uses Roswell to compile Common Lisp applications. LGPL3.
* [cube](https://github.com/xh4/cube) - Kubernetes client library for Common LISP generated from the Swagger specification. [MIT][200].
* [s2i-lisp](https://github.com/container-lisp/s2i-lisp) <i>- Source-to-Image builder image based on CentOS or alternatively RHEL7 for building Common LISP images for OpenShift (and also Docker).</i> <b>- 基于 CentOS 或 RHEL7 的 Source-to-Image 构建器镜像，用于为 OpenShift（以及 Docker）构建 Common LISP 镜像。</b> <i>It features an up-to-date SBCL with Quicklisp installation, SLIME or SLY integration and allows customization via environment variables.</i><b>它具有带有 Quicklisp 安装、SLIME 或 SLY 集成的最新 SBCL，并允许通过环境变量进行自定义。</b> <i>[Apache2][89]</i> <b>[阿帕奇2][89]</b>
* [deploy](https://shinmera.github.io/deploy)  - Lisp 应用程序的二进制部署工具包，额外支持外部共享库.  [zlib][33].
* [cl-aws-runtime-test](https://github.com/y2q-actionman/cl-aws-custom-runtime-test) - An example of using Common Lisp (SBCL) as a custom runtime on AWS lambda. WTFPL.

See also:

- [Heliohost](https://www.heliohost.org/) for a free hosting solution.
- [Platform.sh](https://platform.sh/blog/2019/lisp/) 有 Common Lisp 支持.

Monitoring
----------

* [prometheus.cl](https://github.com/deadtrickster/prometheus.cl) - Prometheus.io client. Grafana dashboard for SBCL and Hunchentoot metrics (memory, threads, requests per second,…). [MIT][200].
* [cl-sentry-client](https://github.com/mmontone/cl-sentry-client)  - 基于云的错误监控系统 Common Lisp 的 Sentry 客户端.  [麻省理工学院][200].
* [rollbar.lisp](https://github.com/adventuring/rollbar.lisp) - interface to [Rollbar.com](https://rollbar.com/)，一个错误跟踪软件.


Third-party APIs
----------------

* [Aws-sign4](https://github.com/rotatef/aws-sign4) - Common Lisp library for Amazon Web Services signing version 4. [GNU GPL3][2].
* [zs3](https://github.com/xach/zs3) - 一个使用亚马逊简单存储的库
Service (S3) and CloudFront service. [BSD][15].
* [cl-ses](https://github.com/CodyReichert/cl-ses/) - Library for AWS SES. [Expat][14].
* [north](https://shinmera.github.io/north)  - South (Simple OaUTH) 库的继承者，在客户端和服务器端实现完整的 oAuth 1.0a 协议. 使用 North，您可以轻松成为 oAuth 提供者或消费者.  [zlib][33].
* [avatar-api](https://github.com/eudoxia0/avatar-api) - Get avatars from Google+, Gravatar and others. [Expat][14].
* [chirp](https://github.com/Shinmera/chirp) - A Twitter client library. [zlib][33].
* [tooter](https://github.com/Shinmera/tooter)  - 为 Mastodon 实现完整的 v1 REST API 协议的客户端库.  [zlib][33].
* [cl-irc](https://www.common-lisp.net/project/cl-irc/)  - IRC 客户端库.  [外籍人士][14].
* [cl-mediawiki](https://github.com/AccelerationNet/cl-mediawiki)  - MediaWiki api 的包装器.  [麻省理工学院][200].
* [cl-openid](https://github.com/cl-openid/cl-openid) - An implementation of OpenID. [LLGPL][8].
* [cl-pushover](https://github.com/TeMPOraL/cl-pushover)  - 通用 Lisp 绑定到 Pushover.  [麻省理工学院][200].
* [humbler](https://github.com/Shinmera/humbler) - A Tumblr API interface. [zlib][33].
* [multiposter](https://github.com/Shinmera/multiposter) - post to multiple services simultaneously. [zlib][33].
* [stripe](https://git.mfiano.net/mfiano/stripe) - a client for the Stripe payment system. [MIT][200].

Web project skeletons and generators
------------------------------------

* [cl-cookieweb](https://github.com/vindarel/cl-cookieweb)  - 用于启动 Web 项目的 Cookiecutter 模板.  [BSD_3 条款][15]. 不在 Quicklisp 中.
  * 提供一个工作玩具网络应用程序，带有 Hunchentoot 网络服务器、easy-routes、Djula 模板、Bulma 样式、基于 SQLite、迁移、示例表定义和使用 FiveAM 的测试套件.
* [make-like](https://github.com/container-lisp/make-like)  - LIKE（Lisp In Kubernetes + Emacs）应用程序的应用程序模板构建器.  [Apache2.0][51].
  * Makefile, podman support, GitHub Actions, Prometheus metrics support, TOML-style config.ini, easy-route preconfigured with health-check and more.
* [cl-webapp-seed](https://github.com/rajasegar/cl-webapp-seed) - a simple web application boilerplate. Uses Hunchentoot, cl-who, deploys easily to Heroku. [MIT][200].


Others
------

*  [cl-forms](https://github.com/mmontone/cl-forms)  - Common lisp 的 Web 表单处理库.  [麻省理工学院][200].
* [maiden](https://shirakumo.github.io/maiden)  - 支持 IRC 等的机器人和聊天系统框架.  [zlib][33].
* [css-lite](https://github.com/paddymul/css-lite)  - CSS 语法.  [外籍人士][14].
* [find-port](https://github.com/eudoxia0/find-port)  - 以编程方式查找开放端口.  [麻省理工学院][200].
* [Postmaster](https://github.com/eudoxia0/postmaster) - A simple, easy-to-use SMTP/IMAP library. [Expat][14].
* [cl-webdriver-client](https://github.com/copyleft/cl-webdriver-client/) - WebDriver 的绑定库（支持 Selenium 4.0）.
* [cl-wget](https://github.com/cl-wget/cl-wget) - Makes retrieving large files or mirroring entire websites easy. [AGPL-3.0][51].
* [trivial-download](https://github.com/eudoxia0/trivial-download)  - 下载文件.  [麻省理工学院] [200].

Numerical and Scientific
========================

* [numcl](https://github.com/numcl/numcl)  - Common Lisp 中的 Numpy 克隆.  [LGPL3][9].
* [GSLL](https://common-lisp.net/project/gsll/) - GNU Scientific Library for Lisp; allows the use of the GSL from Common Lisp. [GNU LGPL2.1][11].
* [maxima](http://maxima.sourceforge.net/)  - 计算机代数系统. 在 Quicklisp 上不可用.  [GNU GPL3][2].
* [Xecto](https://github.com/pkhuong/Xecto)  - 用于常规阵列并行性的库.  [3 条款 BSD][15].
* [Petalisp](https://github.com/marcoheisig/Petalisp) - an attempt to
  generate high performance code for parallel computers by
   JIT 编译数组定义. 它适用于更多
  fundamental level than NumPy, by providing even more powerful
  N 维数组，但只是一些用于处理的构建块
  them. [AGPL-3.0][agpl3].
* [cl-ana](https://github.com/ghollisjr/cl-ana) - Common Lisp data analysis library with emphasis on modularity and conceptual clarity. It aims to be a general purpose framework for analyzing small and large scale datasets, including binned data analysis and visualization. [GNU GPL3][2].
* [linear-programming](https://neil-lindquist.github.io/linear-programming/)  – 用于解决线性规划问题的库.  [麻省理工学院][200].
* [avm](https://github.com/takagi/avm)  - 具有多线程和 CUDA 支持的高效且富有表现力的阵列矢量数学库.  [麻省理工学院][200].
* [array-operations](https://github.com/bendudson/array-operations) - a collection of functions and macros for manipulating Common Lisp arrays and performing numerical calculations with them. [MIT][200].
* [cl-geometry](https://github.com/Ramarren/cl-geometry/) - a system for two dimensional computational geometry for Common Lisp. [MIT][200].
* [Vellum](https://github.com/sirherrbatka/vellum)  - Common Lisp 的数据帧.  BSD_2 条款.
* [rtg-math](https://github.com/cbaggers/rtg-math/)  - 在 lisp 中制作实时图形最常用的数学例程选择（2、3 和 4 分量向量、3x3 和 4x4 矩阵、四元数、球坐标和极坐标）.  BSD_2 条款.
* [origin](https://github.com/mfiano/origin)  - 一个原生的 Lisp 图形数学库，强调性能和正确性. 包括：向量、矩阵（最多 4x4）、四元数、单/双浮点支持、破坏性/非破坏性操作、整形和交叉.  [麻省理工学院][200].

Matrix libraries
----------------

* [magicl](https://github.com/rigetticomputing/magicl) - Matrix Algebra proGrams In Common Lisp based on BLAS/LAPACK and Expokit, by Rigetti Computing. [BSD_3Clause][15].
* [lisp-matrix](https://github.com/blindglobe/lisp-matrix) - A matrix package. [FreeBSD][39].
* [3d-matrices](https://shinmera.github.io/3d-matrices) - A library implementing common matrix calculations, with an emphasis on 2x2,3x3, and 4x4 matrices as commonly used in graphics. It provides some numerical functions as well, but those are not the focus. The library is heavily optimised, so it is not made of pretty code. [zlib][33].
* [clem](https://github.com/slyrus/clem)  - 一个矩阵库.  [BSD_2 条款][17].

Statistics
---------

* [lisp-stat](https://github.com/lisp-stat) - an environment for statistical computing, conceptually similar to R, that is also suitable for front-line production deployments. "It grew out of a desire to have an environment for rapidly prototyping analytical and A.I. solutions, and move directly to production environments with minimal friction."
  * https://lisp-stat.dev/
  * ships Luke Tierney's [XLisp-Stat](https://homepage.stat.uiowa.edu/~luke/xls/xlsinfo/) (a predecessor of R) as well as newer libraries.
* [common-lisp-stat](https://github.com/blindglobe/common-lisp-stat/)  - 通用 Lisp 统计库.  [自由BSD][39].

Units
-----

* [physical-quantities](https://github.com/mrossini-ethz/physical-quantities) - a library that provides a numeric type with optional unit and/or uncertainty for computations with automatic error propagation. GPL2

Utils
-----

* [cmu-infix](https://github.com/rigetti/cmu-infix) - A library for writing infix mathematical notation in Common Lisp. See also [polisher](https://github.com/mrcdr/polisher).


Parallelism and Concurrency
===========================

* :star: [BordeauxThreads](https://common-lisp.net/project/bordeaux-threads/) - Portable, shared-state concurrency. [Expat][14].
* :star: [lparallel](https://github.com/lmj/lparallel) - A library for parallel programming. [3-clause BSD][15].
* [lfarm](https://github.com/lmj/lfarm) - distributing work across machines (on top of lparallel and usocket). [BSD_3Clause][15]
* [calispel](https://github.com/hawkir/calispel) - [CSP](https://en.wikipedia.org/wiki/Communicating_sequential_processes)-like channels for common lisp. With blocking, optionally buffered channels and a "CSP select" statement. ISC-style.
  <i>- &quot;It is complete, flexible and easy to use. I would recommend Calispel over Lparallel and ChanL.&quot;</i> <b>- “它完整、灵活且易于使用。我会推荐 Calispel 而不是 Lparallel 和 ChanL。”</b> <i>@Ambrevar.</i> <b>@Ambrevar。</b> [discussion](https://github.com/CodyReichert/awesome-cl/issues/290)
* [chanl](https://github.com/zkat/chanl) - Portable, channel-based concurrency. [Expat][14], with parts under [3-clause BSD][15].
* [cl-async](https://github.com/orthecreedence/cl-async)  - 用于通用、非阻塞编程的库.  [外籍人士][14].
* [Moira](https://github.com/TBRSS/moira) -  Monitor and restart background threads. In-lisp process supervisor. [MIT][200].
* [trivial-monitored-thread](https://gitlab.com/ediethelm/trivial-monitored-thread) -
  一个 Common Lisp 库，提供了一种产生线程的方法
  informed when one any of them crash and die. [MIT][200].
* [cl-gearman](https://github.com/taksatou/cl-gearman) - 一个图书馆 [Gearman](http://gearman.org/) distributed job system. [LLGPL][8].
* [swank-crew](https://github.com/brown/swank-crew) - distributed computation framework implemented using Swank Client. [BSD_3Clause][15].
* [cl-coroutine](https://github.com/takagi/cl-coroutine)  - 一个协程库. 它在其实现中使用 CL-CONT 延续库.  [麻省理工学院][200].
* [STMX](https://github.com/cosmos72/stmx) -  High performance Transactional Memory for Common Lisp. [LLGPL][8].

See also:

* [cl-etcd](https://github.com/atgreen/cl-etcd) - Run etcd as an asynchronous inferior process.  [etcd](https://etcd.io/) is a strongly consistent, distributed key-value store. [AGPL-3.0][agpl3].

演员模式
--------------

*  [cl-gserver](https://github.com/mdbergmann/cl-gserver)  - cl-gserver 是一个“消息传递”库/框架，具有类似于 Erlang 或 Akka 的演员. 它支持创建应该反应式工作的系统，需要并行计算和基于事件的消息处理.  [阿帕奇2] [89].
* [erlangen](https://github.com/eugeneia/erlangen)  - Clozure Common Lisp 的分布式异步消息传递系统.  [GNU GPL3][2].
* [Actors](https://github.com/aarvid/Actors) package for LispWorks ([announce](https://www.reddit.com/r/Common_Lisp/comments/77vsft/david_mcclains_actors_package_for_lispworks/)) [MIT][200].
* [common-lisp-actors](https://github.com/naveensundarg/Common-Lisp-Actors) - a simple and easy to use Actor system. [BSD_2Clause][17].
* [memento-mori](https://github.com/zkat/memento-mori)-  a library for writing robust, actor-based systems. It draws inspiration from Erlang/OTP, particularly its crash-first approach to high-availability systems, as well as Akka. [MIT][200].


Event processing
----------------

* [simple-tasks](https://github.com/Shinmera/simple-tasks) - A very simple task scheduling framework. [zlib][33].
* [deeds](https://github.com/Shinmera/deeds) - Deeds is an Extensible Event Delivery System. It allows for efficient event delivery to multiple handlers with a complex event filtering system. [zlib][33].
* [cl-flow](https://github.com/borodust/cl-flow/) -  Data-flowish computation tree library for non-blocking concurrent Common Lisp. [MIT][200].
* [event-glue](https://github.com/orthecreedence/event-glue)  - 简单的事件抽象. 没有依赖关系. 它可以在任何需要通用事件处理系统的地方使用.  [麻省理工学院][200].


Job processing
--------------


* [SBCL's timers](http://www.sbcl.org/manual/#Timers), system-wide event schedulers.
* [psychiq](https://github.com/fukamachi/psychiq) - redis-based background job processing for Common Lisp applications. Inspired by Ruby's Sidekiq and compatible with its web UI. [LLGPL][8].
* [cl-cron](https://github.com/ciel-lang/cl-cron) - A simple tool that provides cron like facilities. [GPL3][2].
* [clerk](https://github.com/tsikov/clerk)  - 一个类似 cron 的调度器，带有健全的 DSL.  [麻省理工学院][200].


Regex
=====

* :star: [cl-ppcre](http://weitz.de/cl-ppcre/)  - 可移植的、Perl 兼容的正则表达式.  [自由BSD][39].
* [one-more-re-nightmare](https://github.com/no-defun-allowed/one-more-re-nightmare) - a fast-ish regular expression compiler in Common Lisp. [BSD_2Clause][17].


Scripting
=========

编写、运行脚本
------------------------

*  [Roswell](https://github.com/roswell/roswell#scripting-with-roswell) -
  lisp 安装程序和脚本环境（帮助程序、启动程序、
  installer) and more. [MIT][200].
* [cl-all](https://github.com/shinmera/cl-all) - A script to run Lisp snippets in multiple implementations. This allows you to quickly compare implementation behaviour and differences. [zlib][33].
* [clawk](https://github.com/sharplispers/clawk)  - 嵌入到 Common Lisp 中的 AWK 实现，用于搜索文件中的行并对其字段执行指定的操作.  BSD 风格.
* [ScriptL](https://github.com/rpav/ScriptL) - Shell scripting made Lisp-like! Or, live-coding remote function calls for the shell. Write a command in the REPL, and run it instantly in the shell. [LLGPL][8].
  * similar and maybe simpler: [lserver](https://notabug.org/quasus/lserver/)

Command-line options parsers
----------------------------

*  [Unix-opts](https://github.com/libre-man/unix-opts) - a command line
  options parser with a concise declaration of options. [MIT][200].
* [Adopt](https://github.com/sjl/adopt/) - A Damn OPTion parsing library. [MIT][200].
* [Clingon](https://github.com/dnaeon/clingon) - 丰富的命令行选项解析器系统.
  * 较新，它可能拥有最丰富的功能集：子命令、生成 bash 补全、支持各种选项（整数、布尔值、计数器、枚举……）、可扩展……


Readline, ncurses and other graphical helpers
--------------------------------------------

* [cl-readline](https://github.com/vindarel/cl-readline) - a set of
  在输入行时编辑行的功能，以维护列表
  以前输入的命令行，以调用和重新编辑它们
  perform csh-like history expansion.  Emacs and vi editing
  模式.  [GPL3][2].
* [Linedit](https://common-lisp.net/project/linedit) - 阅读线风格
  提供可定制的行编辑的库
  特征.  [麻省理工学院风格][210].
* [cl-charms](https://github.com/HiTECNOLOGYs/cl-charms) - 一个
  interface to `libcurses` in Common Lisp. It provides both a raw,
  low-level interface to libcurses via CFFI, and a more higher-level
  lispier interface. [MIT][200].
* [replic](https://github.com/vindarel/replic/)  - 帮助将现有代码转换为 readline 应用程序，重点是定义命令参数的完成. 也作为一个准备使用的可执行文件，将用户的 lispy init 文件转换为 readline 命令.  [麻省理工学院][200].
* [cl-ansi-term](https://github.com/vindarel/cl-ansi-term) - 打印
  彩色文本、水平线、进度条、（未）有序列表
  和符合 ANSI 标准的终端上的表格.  [GPL3][2].
* [cl-progress-bar](https://github.com/sirherrbatka/cl-progress-bar/) - progress bars, just like in Quicklisp ! [MIT][200].

Shells, shells interfaces
-------------------------

* [Lish](https://github.com/nibbula/lish) - `lish` may someday be a lisp shell. [GPL3][2].
  * 支持路径和 Lisp 符号中的可执行文件的制表符补全，允许编写和混合 shell 命令和 Lisp 代码，具有微型 REPL 和交互式调试器等等.
* [shcl](https://github.com/bradleyjensen/shcl)  - Common Lisp 中类似 POSIX 的 shell.  [Apache2.0][89].
* [Shelly](https://github.com/fukamachi/shelly) - execute Common Lisp
  功能类似于 shell 命令，无需编写命令
  line arguments parser. And it also can be used as a Make-like
  构建工具.  [自由BSD][39].
* [cmd](https://github.com/ruricolist/cmd) - utility for running external programs. Protects against shell interpolation, built with multi-threaded programs in mind, Windows support. [MIT][200].
  * `uiop:run-program` (synchronous) and `uiop:launch-program` (async) are shipped with ASDF and available on all modern implementations. See the [CL Cookbook: running external programs](https://lispcookbook.github.io/cl-cookbook/os.html#running-external-programs).
* [Clesh](https://github.com/Neronus/Clesh) - extends Common Lisp to embed shell code in a manner similar to perl's backtick. [FreeBSD][39].

系统管理
---------------------

* [Consfigurator](https://spwhitton.name/tech/code/consfigurator/) - Lisp declarative configuration management system.  You can use it to configure hosts as root, deploy services as unprivileged users, build and deploy containers, and produce disc images. [GPL3][2].
* [Adams](https://github.com/cl-adams/adams) - UNIX system administration in Common Lisp. Not unlike Ansible, Chef or Puppet. [ISC][22].

其他脚本实用程序
-------------------------

* [WCL](https://github.com/wadehennessey/wcl) [陈旧] - 允许数百个 Lisp
应用程序立即可用，同时允许
<i>several of them to run concurrently.</i><b>其中几个同时运行。</b> <i>WCL accomplishes this by</i> <b>WCL 通过</b>
providing Common Lisp as a Unix shared library that can be linked with
 Lisp 和 C 代码可生成高效的应用程序. 例如，
executable for a Lisp version of the canonical `Hello World!`
program requires only 20k bytes on 32 bit x86 Linux.  WCL also
支持完整的开发环境，包括动态文件
loading and debugging.  A modified version of GDB is used to debug WCL
程序，为混合语言调试提供支持.


Text Editor Resources
=====================

This contains plugins and other goodies for various text editors.

* [Parinfer](https://shaunlebron.github.io/parinfer/) - Parinfer is a way to edit lisp code that helps to keep both the indentation and the parenthesis balanced. It is easy to start with and yet it offers advanced features à la Paredit. It is available on many editors (Emacs, Vim, Neovim, Atom, Sublime Text, Visual Studio Code, LightTable, CodeMirror,…).

## Emacs ##

* :star: [Slime](https://github.com/slime/slime) - Superior Lisp Interaction Mode for Emacs; a full-blown environment for Common Lisp inside of Emacs. Public domain.
*  [Sly](https://github.com/joaotavora/sly) - SLY 是 SLIME 的一个分支，并对其进行了多项改进.
*  [Portacle](https://shinmera.github.io/portacle/) - A portable and multiplatform Common Lisp environment: SBCL, Quicklisp, Emacs, Slime, Git.
* [cl-devel2](https://hub.docker.com/r/eshamster/cl-devel2/)  - 一个用于 Common Lisp 开发环境的 Docker 容器. 使用 Slime 运送 SBCL、CCL、Roswell 和 Emacs25.
* [Emacs4CL](https://github.com/susam/emacs4cl) - A tiny Emacs initialization file to quickly set up vanilla Emacs for Common Lisp programming. Comes with a line-by-line explanation of every line of code in the initialization file.
* [quicklisp-systems](https://github.com/mmontone/quicklisp-systems) - 从 Emacs 搜索、浏览和加载 Quicklisp 系统.
*[slime-doc-contribs](https://github.com/mmontone/slime-doc-contribs) - enhance the default help buffer.

## Vim & Neovim ##

* [SLIMV](https://github.com/kovisoft/slimv)  - Vim 的高级 Lisp 交互模式；  Vim 内部的 Common Lisp 的成熟环境. 未指定许可证.
* [Vlime](https://github.com/vlime/vlime) - VLIME: Vim plus Lisp Is Mostly Evil. A Common Lisp dev environment for Vim (and Neovim). [MIT][200].
* [quicklisp.nvim](https://gitlab.com/HiPhish/quicklisp.nvim) - A Quicklisp frontend for Neovim.
* [Slimv_box](https://github.com/justin2004/slimv_box) - slimv in a Docker container.


## Eclipse ##

* [Dandelion](https://github.com/Ragnaroek/dandelion) - a Common Lisp plugin for the Eclipse IDE.

## Lem ##

* [Lem](https://github.com/cxxxr/lem) - a ready to use, Emacs-like, Slime-based
  editor tailored for Common Lisp development. With ncurses and Electron interfaces. [MIT][200]. See also: an [opengl frontend](https://github.com/pupcraft/lem-opengl), [Lem in Docker](https://github.com/40ants/lem-docker), [lem-pareto](https://github.com/40ants/lem-pareto).

## Atom ##

* [SLIMA](https://github.com/neil-lindquist/slima) allows you to
  交互式开发 Common Lisp 代码，将 Atom 变成
  相当不错，并且积极开发的 Lisp IDE.  [麻省理工学院][200].

## Sublime Text ##

* [Sublime Text](http://www.sublimetext.com/3) (proprietary) has
  Common Lisp support with its SublimeREPL and
  [Slyblime](https://github.com/s-clerc/slyblime) packages. Slyblime
  is an implementation of SLY and it uses the same backend (SLYNK). It
  ships advanced features including a debugger with stack frame
  inspection.

## VSCode ##

* [commonlisp-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.commonlisp-vscode)  - 支持语法高亮、自动完成、悬停文档、转到定义、编译和加载文件、REPL 的扩展. 它是 [On GitHub](https://github.com/ailisp/commonlisp-vscode/).
* [alive](https://github.com/nobody-famous/alive) -  Common Lisp Extension for VSCode. Public domain.
  * see the Cookbook: [using VSCode with Alive](https://lispcookbook.github.io/cl-cookbook/vscode-alive.html)
* [strict-paredit-vscode](https://marketplace.visualstudio.com/items?itemName=ailisp.strict-paredit) - structural editing and navigation like Emacs.

## Geany (experimental) ##

* [Geany-lisp](https://github.com/jasom/geany-lisp) is an experimental lisp mode for the [Geany](https://geany.org/) editor.

## Notebooks ##

* [cl-jupyter](https://github.com/fredokun/cl-jupyter) - A Common Lisp kernel for Jupyter notebooks [custom licence](https://github.com/fredokun/cl-jupyter/blob/master/LICENSE).
* [common-lisp-jupyter](https://github.com/yitzchak/common-lisp-jupyter)  - 一个用于 Jupyter 的 Common Lisp 内核以及一个用于构建 Jupyter 内核的库，基于 Robert Dodier 的 Maxima-Jupyter，它基于 Frederic Peschanski 的 cl-jupyter.  [麻省理工学院][200].
* [Darkmatter](https://github.com/tamamu/darkmatter) - A
  笔记本式的 Common Lisp 环境.  [麻省理工学院][200].

## REPLs ##

* [cl-repl](https://github.com/koji-kojiro/cl-repl) - an ipython-like REPL. With completion, shell commands, magic commands, debugger, etc. [MIT][200]. With [colorthemes](https://github.com/koji-kojiro/lem-pygments-colorthemes).
* [sbcli](https://github.com/hellerve/sbcli) - a readline REPL for SBCL. With completion, quick commands, optional syntax highlighting (with pygments), and no interactive debugger. [GPL3][2].

## Online editors ##

* [Judge0 IDE](https://ide.judge0.com/?lUpj) is an online editor which supports Common Lisp (SBCL). [MIT][200].

## Apps ##

* [CodePlayground](https://codeplayground.app/) - 通过 CCL 支持 Lisp 的 iPhone 和 iPad 应用程序.

文本解析器
============

* :star: [esrap](https://github.com/scymtym/esrap)  - Packrat 解析器.  [外籍人士][14].
* [cl-yacc](https://github.com/jech/cl-yacc) - a LALR(1) parser generator. [MIT][200].
* [cl-shlex](https://github.com/ruricolist/cl-shlex/)  - 用于类似 shell 的语法的简单词法分析器.  [麻省理工学院][200].
* [smug](https://github.com/drewc/smug)  - Common Lisp 的解析器组合器.  SMUG 使创建快速可扩展的递归下降解析器变得简单，而没有时髦的语法或难以理解的宏观.  [麻省理工学院][200].
* [parseq](https://github.com/mrossini-ethz/parseq) - a library for parsing sequences such as strings and lists using parsing expression grammars. Inspired by Esrap. GPL2.
* [texp](https://github.com/eugeneia/texp/) - A DSL to generate TeX. [AGPL-3.0][agpl3].

文本处理
===============

* [montezuma](https://github.com/sharplispers/montezuma/) -  Full-text indexing and search for Common Lisp. [Expat][14].
* [mk-string-metrics](https://github.com/cbaggers/mk-string-metrics) -
  在 Common Lisp 中高效计算各种字符串度量
  (Damerau-Levenshtein, Hamming, Jaro, Jaro-Winkler, Levenshtein,
  etc). [MIT][200].
* [wiki-lang-detect](https://github.com/vseloved/wiki-lang-detect) -
使用维基百科数据的文本语言识别. 未指定许可证.
* [cl-phonetic](https://github.com/bgutter/cl-phonetic)  - Common Lisp 的语音模式匹配库（旨在替换 Python 的 Sylvia 库）.  [麻省理工学院][200].
* [cl-string-generator](https://github.com/pokepay/cl-string-generator)  - 从正则表达式生成字符串.  [麻省理工学院][200].

Tools
=====

These are applications or bits of code that make development in Common Lisp easier without being Common Lisp libraries themselves.

* [quicksearch](https://github.com/tkych/quicksearch) - Look up online libraries from the REPL. [Expat][14].
* [lake](https://github.com/takagi/lake) - a GNU make like build utility. [MIT][200].


Unit Testing
============

* :star: [FiveAM](https://github.com/sionescu/fiveam) - Simple regression testing framework. [FreeBSD][39].
* [CLUnit2](https://notabug.org/cage/clunit2/) - A unit testing library. [MIT][200].
* [Parachute](https://github.com/Shinmera/parachute)  - 一个可扩展和交叉兼容的测试框架. 具有测试依赖项、条件、固定装置和重新启动.  [zlib][33].
* [Mockingbird](https://github.com/Chream/mockingbird) - A small
   Common Lisp 的存根和模拟库. 也可以检查是否
  a stubbed function was called, how many times and with which
  论据.  [麻省理工学院][200].
* [cl-mock](https://github.com/Ferada/cl-mock) - Another mocking library. It has more features than Mockingbird, like pattern matching on the mocked call, etc.
* [Check-it](https://github.com/DalekBaldwin/check-it) - A QuickCheck-style randomized property-based testing. [LLGPL][8].
* [cl-coveralls](https://github.com/fukamachi/cl-coveralls) - 帮手
  库将测试覆盖率发布到工作服. 看 [SBCL's code coverage tool](http://www.sbcl.org/manual/index.html#sb_002dcover) .  [自由BSD][39].

编辑器实用程序：

* [Slite](https://github.com/tdrhq/slite/) - a SLIme-based TEst runner for FiveAM Tests. [Apache2.0][89]
  - Slite interactively runs your Common Lisp tests (at the time of writing only FiveAM is supported). It allows you to see the summary of test failures, jump to test definitions, rerun tests with the debugger, all from inside Emacs.


Utilities
=========

Caching
-------

* [clache](https://github.com/html/clache)  - 通用缓存设施.  [LLGPL][8].


Compression / decompression
---------------------------

* [chipz](https://github.com/froydnj/chipz) - A decompression library. [3-clause BSD][15].
* [Salza2](http://www.xach.com/lisp/salza2/)  - 用于创建压缩数据的库.  [自由BSD][39].
* [zippy](https://github.com/Shinmera/zippy)  - 基于 3bz 的 ZIP 存档格式库.  [zlib][33].


Configuration
-------------

*  [py-configparser](https://common-lisp.net/project/py-configparser/) - reads and writes Python's ConfigParser-like configuration files. [MIT][200].
* [envy](https://github.com/fukamachi/envy) - Configuration switcher. [FreeBSD][39].
* [chameleon](https://github.com/sheepduke/chameleon/) - a configuration management library shipped with profile support. [MIT][200].

CSV
---

* :star: [cl-csv](https://github.com/AccelerationNet/cl-csv) - A library for parsing CSV files. [3-clause BSD][15].
* [cl-decimals](https://github.com/tlikonen/cl-decimals) - Decimal number parser and formatter. Public domain.
* [auto-text](https://github.com/defunkydrummer/auto-text)  - 文本文件的自动（编码、行尾、列宽、csv 分隔符等）检测.  [麻省理工学院][200]. 也可以看看 [inquisitor](https://github.com/t-sin/inquisitor) for detection of asian and far eastern languages.


日期和时间
-------------

* :star: [local-time](https://common-lisp.net/project/local-time/)  - 用于以半标准方式处理日期和时间信息的开发库.  [3 条款 BSD][15].
* [cl-date-time-parser](https://github.com/tkych/cl-date-time-parser)  - 自由地解析日期时间字符串. 隐藏日期时间格式之间的差异，并允许将日期和时间作为一种日期时间格式进行管理.  [麻省理工学院][200].
* [chronicity](https://github.com/chaitanyagupta/chronicity) - A natural language date and time parse, to parse strings like "3 days from now". [BSD_3Clause][15].
* [local-time-duration](https://github.com/enaeher/local-time-duration) -
Duration processing library built on top of local-time. [MIT][200].
  * see this fork: [humanize-duration](https://github.com/40ants/humanize-duration) ，仅输出持续时间对象的重要部分. 具有本地化支持.
* [iso-8601-date](https://gitlab.com/DataLinkDroid/iso-8601-date)  - Common Lisp 中的其他日期例程，基于 ISO 8601 字符串表示.  [LLGPL][8].
* [calendar-date](https://github.com/takagi/calendar-date)  - 一个公历日期库.  [麻省理工学院][200].
* [periods](https://github.com/jwiegley/periods)  - 在更高级别操作日期/时间对象. 具有系列兼容的数据结构.  [BSD_3 条款][15].

See also the book [Calendrical calculations](https://www.cambridge.org/us/academic/subjects/computer-science/computing-general-interest/calendrical-calculations-ultimate-edition-4th-edition?format=HB#resources), by Edward M. Reingold, Nachum Dershowitz, Cambridge Press. It provides Lisp sources.

Data validation
---------------

* [ratify](https://github.com/Shinmera/ratify)  - 用于批准、验证和解析输入的实用程序集合.  [zlib][33].
* [clavier](https://github.com/mmontone/clavier)  - Common Lisp 的通用验证库.  [麻省理工学院][200].
* [json-schema](https://github.com/fisxoj/json-schema) - 用于根据草案 4、6、7 和 2019-09 的模式验证数据的库 [JSON Schema](https://json-schema.org/) 标准.  [LLGPL][8].
* [sanity-clause](https://github.com/fisxoj/sanity-clause)  - Common Lisp 的数据序列化/合同库. 模式可以是属性列表或基于类，允许在“make-instance”期间检查插槽的类型.  [LLGPL][8].

Developer utilities
-------------------

* [repl-utilities](https://github.com/m-n/repl-utilities) - Ease
common tasks at the REPL (print documentation, print external symbols,
call hooks when loading a package,…). [BSD_2Clause][17].
* [flight-recorder](https://github.com/vseloved/flight-recorder) - a robust REPL history facility.
* [tracer](https://github.com/TeMPOraL/tracer)  - Common Lisp 的跟踪分析器，输出适合在 Chrome/Chromium 的跟踪查看器中显示.  [麻省理工学院][200].
* [cl-flamegraph](https://github.com/40ants/cl-flamegraph) - A wrapper around SBCL's statistical profiler, to generate FlameGraph charts for Common Lisp programs. [BSD][15].
* [cl-debug](https://github.com/LowH/cl-debug)  - 一个跨包调试工具. 提供统一的方式来启用或禁用调试特定的代码. 可以相对于由符号或关键字表示的程序功能启用或禁用调试代码.  ISC 许可证.
* [supertrace](https://github.com/fukamachi/supertrace)  - 用于调试/分析的高级 Common Lisp `trace` 功能. 一次跟踪多个函数，使用 before 和 after 钩子.  [BSD_2 条款][17].
* [printv](https://github.com/danlentz/printv) -  A batteries-included tracing and debug-logging macro. [Apache2][89].
* [GTFL](http://www.martin-loetzsch.de/gtfl/) - A graphical terminal for Lisp, meant for Lisp programmers who want to debug or visualize their own algorithms. A graphical trace in the browser. BSD-style.
* [trivial-with-current-source-from](https://github.com/scymtym/trivial-with-current-source-form/) - Helps macro writers produce better errors for macro users. [GPL3][2].
* [trivial-benchmark](https://github.com/Shinmera/trivial-benchmark) - Tiny benchmarking library. [zlib][33].
* [glyphs](https://github.com/ahungry/glyphs/) - A library for cutting down the verboseness of Common Lisp in places. [GNU GPL3][2].
* [Lisp REPL core dumper](https://gitlab.com/ambrevar/lisp-repl-core-dumper/) -
A portable wrapper to generate Lisp cores on demand to start REPL blazing fast.
它可以预加载提供的系统，以帮助构建一个专门的集合
Lisp 核心.


文档构建器
----------------------

* [sphinxcontrib-cldomain](https://github.com/russell/sphinxcontrib-cldomain) -
  Extending Sphinx to cover Common Lisp. To build documentation with
  与 sphinx 一样的易用性将成为 Python 项目.  [GPL3][2]
* [Codex](https://github.com/CommonDoc/codex) - A beautiful
  documentation system for Common Lisp. [MIT][200].
* [Staple](https://github.com/Shinmera/staple)  - 使用 HTML 模板生成文档页面的工具. 使用现有的 README，将文档字符串、交叉引用和链接添加到 CLHS.  [zlib][33].
* [cl-bibtex](https://github.com/mkoeppe/cl-bibtex)  - 在 Common Lisp 中对 BibTeX 程序的兼容重新实现，带有 BST-to-CL 编译器.  [GNU LGPL2.1][11].
* [mgl-pax](https://github.com/melisgl/mgl-pax) - Exploratory
编程环境和文档生成器. 一个可能
accomplish similar effects as with Literate Programming, but
文档是从代码生成的，反之亦然. 代码是第一位的，
code must look pretty, documentation is code. [MIT][200].
  - see this [40ants fork](https://github.com/40ants/doc)
* [erudite](https://github.com/mmontone/erudite)  - 考虑到交互式开发而构建的文学编程系统.  [麻省理工学院][200].


文件和目录
---------------------

* :star: [uiop](https://common-lisp.net/project/asdf/uiop.html) 及其 `pathname` 包
  (replaces [cl-fad](http://weitz.de/cl-fad/)). uiop is part of ASDF3
  and as thus is shipped in many implementations. [MIT][200].
* [osicat](https://common-lisp.net/project/osicat/) - 类 POSIX 系统上的轻量级操作系统接口（目录迭代和删除、环境变量、文件权限等）[Expat][14].
* [pathname-utils](https://github.com/Shinmera/pathname-utils) - A collection of utilities to help with pathname operations. [zlib][33].
* [ppath](https://github.com/fourier/ppath) - 普通 Lisp 
implementation of the Python's os.path module. [BSD][15].
* [archive](https://github.com/froydnj/archive)  - 用于读取和创建归档（tar、cpio）文件的库.  [BSD_3 条款][15].  `tar` 程序的纯 Common Lisp 替代品.
  * see its recent fork [cl-tar](https://common-lisp.net/project/cl-tar/) (2021). [Announce](https://www.timmons.dev/posts/new-project-cl-tar.html).
* [mmap](https://github.com/Shinmera/mmap)  - 便携式 mmap 文件内存映射实用程序库.  [zlib][33].
* [fof](https://gitlab.com/ambrevar/fof)  - 文件对象查找器 Common Lisp 库. 启用快速文件搜索、检查和操作.  [GPL3][2].

File watching libraries:

* [cl-inotify](https://github.com/Ferada/cl-inotify) - interface to the Linux inotify API. Simplified BSD License.
* [cl-fswatch](https://github.com/muyinliu/cl-fswatch) - 的包装 YFC [fswatch](https://github.com/emcrisostomo/fswatch) ，一个跨平台的文件更改监视器.  [国际标准委员会][22].

Git
---

* [legit](https://shinmera.github.io/legit/)  - Git 二进制文件的接口.  [zlib][33].
* [git-api](https://github.com/fourier/git-api) - 通用 Lisp 库
to access git repository. It doesn't need git or libgit installed. [BSD][15].

i18n
----

* [cl-i18n](https://notabug.org/cage/cl-i18n) - an i18n library. Load translations from GNU gettext text or binary files or from its native format. Localisation helpers of plural forms. [LLGPL][8].
* [gettext](https://github.com/rotatef/gettext)  - 将 gettext 运行时移植到 Common Lisp.  [GPL3][2].
* [cl-locale](https://github.com/fukamachi/cl-locale)  - 一个简单的 i18n 库.  [LLGPL][8].
* [enchant](https://github.com/tlikonen/cl-enchant) - bindings for the Enchant spell-checker library. Public domain.
* [oxenfurt](https://github.com/Shinmera/oxenfurt) - A  client library for the Oxford dictionary API. [zlib][33].
* [language-codes](https://shinmera.github.io/language-codes) - A database library for ISO language codes. [zlib][33]
* [system-locale](https://shinmera.github.io/system-locale) - A library to retrieve the user's preferred language, so that your application may choose a sensible default. [zlib][33].
* [multilang-documentation](https://shinmera.github.io/multilang-documentation) - Allows writing docstrings in multiple languages, for truly internationally documented libraries. [zlib][33].

Linting，代码格式化
------------------------

* [sblint](https://github.com/fukamachi/sblint) - 使用 SBCL 的 Common Lisp 源代码的 linter，适用于 Reviewdog（[slides](http://www.slideshare.net/fukamachi/sblint)). [BSD_2Clause][17].
* [trivial-formatter](https://github.com/hyotang666/trivial-formatter)  - Common Lisp 的代码格式化程序.  [麻省理工学院][200].

和 also: [lisp-format](https://github.com/eschulte/lisp-format) 和 [cl-indentify](https://github.com/yitzchak/cl-indentify).


Logging
-------

* :star: [log4cl](https://github.com/sharplispers/log4cl/) - Logging framework modelled after Log4J. [Apache2.0][89]. Advanced integration with Slime.
  * [log4cl-json](https://github.com/40ants/log4cl-json) - JSON appender extension. [BSD][15].
* [verbose](https://shinmera.github.io/verbose)  - 一个快速且高度可配置的日志框架.  [zlib][33].
* [a-cl-logger](https://github.com/AccelerationNet/a-cl-logger) - Logging library providing context sensitive logging of more than just strings to more than just local files or output streams. Features logstash support, json support, logger hierarchies, context sensitive logging, objects printed as an inspectable presentation,…

给第三方：

* [cl-fluent-logger](https://github.com/fukamachi/cl-fluent-logger) - A Common Lisp structured logger for [Fluentd](https://www.fluentd.org/).

See also: [extensive comparison of logging libraries](https://sabracrolleton.github.io/logging-comparison).


Markdown
--------

* [3bmd](https://github.com/3b/3bmd) - a markdown -> html converter. [MIT][200].

PDF
---

* [cl-typesetting](https://github.com/mbattyani/cl-typesetting) 和 [cl-pdf](https://github.com/mbattyani/cl-pdf)  - 用于生成 PDF 文件的跨平台 Common Lisp 库.  [自由BSD][39].
* [cl-pslib](https://notabug.org/cage/cl-pslib) - 一个（薄）包装 [pslib](http://pslib.sourceforge.net/) library for generating PostScript files. Also [cl-pslib-barcode](https://notabug.org/cage/cl-pslib-barcode). [LLGPL][8].

Plotting
--------

* [vgplot](https://github.com/volkers/vgplot) - an interface to the
  gnuplot plotting utility with the intention to resemble some of
   octave 或 matlab 的绘图命令.  [GPL3][2].
* [eazy-gnuplot](https://github.com/guicho271828/eazy-gnuplot) - a
  lispy, structure-less Gnuplot library. With its
  [cookbook](http://guicho271828.github.io/eazy-gnuplot/) .  [LLGPL] [8]
* [kai](https://github.com/komi1230/kai)  - Common Lisp 的高级绘图仪库. 一个包装器 [Plotly](https://plotly.com/javascript/) JS library. [MIT][200].
* [ADW-Charting](https://common-lisp.net/project/adw-charting/)  - 一个完全用 Common Lisp 编写的简单图表绘制库. 还包括 Google 图表服务的后端. 类似 BSD.
* [cl-spark](https://github.com/tkych/cl-spark) - sparkline strings for the console: `(spark '(1 1 2 3 5 8))` => "▁▁▂▃▅▇". [MIT][200].

另请参阅 IUP 和 ltk-plotchart 的图表工具（GUI 部分）.

项目骨架
-----------------

* [cl-project](https://github.com/fukamachi/cl-project)  - 一般的现代项目骨架.  [LLGPL][8].
* [cl-project-with-docs](https://github.com/40ants/cl-project-with-docs)  - 使用 Sphinx 和 reStructured 文本来呈现美观且可读的 HTML 文档.  [BSD][15].
* [cl-cookieproject](https://github.com/vindarel/cl-cookieproject) -  Generate a ready-to-use Common Lisp project. Not in Quicklisp. [BSD_3Clause][15].
  * test definitions, entry point to run from sources, build a binary, Roswell integration…

Security
--------

* [cl-isolated](https://github.com/kanru/cl-isolated) - A restricted environment for Common Lisp code evaluation [AGPL-3.0][agpl3].


Other
-----

This contains anything which doesn't fit into another category.

* [babel](https://github.com/cl-babel/babel) - A charset encoding/decoding library. [Expat][14].
* [corona](https://github.com/eudoxia0/corona) -  Create and manage virtual machines from Common Lisp http://eudoxia.me/corona [MIT][200].
* [fast-io](https://github.com/rpav/fast-io) - Fast octet-vector/stream I/O. [3-clause BSD][15].
* [iolib](https://github.com/sionescu/iolib)  - I/O 库.  [外籍人士][14].
* [named-readtables](https://github.com/melisgl/named-readtables) - Provides a readtable namespace, akin to package namespaces. [3-clause BSD][15].
* [simple-currency](https://github.com/a0-prw/simple-currency) - A currency conversion library using daily information published by the ECB. [FreeBSD][39].
* [trivial-garbage](https://github.com/trivial-garbage/trivial-garbage) - A portable finalizer, weak hash-table and weak pointer API. Public domain.
* [trivial-utf8](https://common-lisp.net/project/trivial-utf-8/)  - 用于进行基于 UTF-8 的 I/O 的小型库.  BSD.


XML
===

* [CXML](https://common-lisp.net/project/cxml/)  - XML 解析器和序列化器，带有一系列扩展库.  [LLGPL][8].
  - 👍 has an incremental parser, allowing to parse big files.
* [Plump][71] - A lenient XML parser. [zlib][33].
* [xpath](https://github.com/sharplispers/xpath) ([homepage](https://common-lisp.net/project/plexippus-xpath/atdoc/index.html) - Implementation of the XML Path Language (XPath) Version 1.0. [BSD_2Clause][17].
* [s-xml](http://cliki.net/S-XML) - A basic parser. [LLGPL][8].
* [xmls](https://github.com/rpgoldman/xmls) - A small, simple, non-validating XML parser. [3-clause BSD][15].
* [cl-feedparser](https://github.com/TBRSS/cl-feedparser)  - 一个 Common Lisp (RSS, Atom) 提要解析器.  [LLGPL][8]
* [Buildnode](https://github.com/AccelerationNet/buildnode) - A common lisp library to ease interaction with CXML-dom, such as building Excel spreadsheets. [BSD][15].


Contributing
============
Your contributions are always welcome! Please submit a pull request or create
an issue to add a new framework, library or software to the list.

我们（试图）遵守的规则如下：

- by default, add a library to the end of its section.
- absolute de-facto libraries, like BordeauxThreads or Quicklisp,
  should be denoted with a :star: (`:star:` in markdown).
- two libraries very similar in scope should be side by side, or in a
  section of their own.
- 根据我们的经验和现状做一些策展
  图书馆的文档. 我们*不*旨在列出所有现有
  CL 库（参见 Cliki）也没有列出每个
  "popular" library (see Quicklisp stats).
- as such, the libraries we like best are marked with a 👍 (`1F44D`
  unicode character). See also the signs' explanation in the
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
[agpl3]: https://directory.fsf.org/wiki/License:AGPL-3.0
