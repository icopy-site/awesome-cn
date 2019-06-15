<div class="github-widget" data-repo="CodyReichert/awesome-cl"></div>
<div align="center">
  <a href="https://awesome-cl.com" target="_blank">
    <img src="https://i.imgur.com/jLVXhpc.png">
  </a>
</div>

## Awesome Common Lisp [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Assertible status](https://assertible.com/apis/102e334d-f9a8-4565-9353-7572de775cae/status?api_token=8b55a286830323effb)](https://assertible.com/docs/guide/deployments)

_awesome_ Common Lisp库的精选列表.

对于很棒的*软件*，请参阅 [lisp-lang.org's success stories](http://lisp-lang.org/success/) 和 [awesome-cl-software](https://github.com/azzamsa/awesome-cl-software) 名单.

此处列出的所有库均可从[Quicklisp] [16]获得，除非
 另有说明.  标有星号的那些：如此广泛而且
 他们成为社区标准的坚实.  你不能错
 他们.  这就是Quicklisp，BordeauxThreads和
 这样.  用a表示的库是我们喜欢和想要的库
 在Awesome-cl列表中宣传.  他们证明了他们可以解决的问题
比社区标准更好的问题，但他们不是
 广泛的，或不被认为是稳定的.  例如，我们更喜欢
Cl-Who上的喷丝头.

 添加一些新东西！  见 [contributing](#contributing) 添加内容的部分
list.

这是根据GNU自由文档许可证 - 其文本发布
 在LICENSE文件中提供.  此存储库也是镜像
[NotABug](https://notabug.org/CodyReichert/awesome-cl) -  **完全免费**（如同libre）
 Github的替代品.  优先考虑[自由软件] [13]和
对物质资源不邪恶的卖家.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-generate-toc again -->


<!-- markdown-toc end -->


Audio
=====

* [Open Music](https://github.com/openmusic-project/OM6)   - 可视化编程，计算机辅助组合环境.  [GPL3] [2].
* [OM7](https://github.com/openmusic-project/om7)   -  OpenMusic可视化编程和计算机辅助合成环境的新实现，包括对图形界面，计算模式和与外部软件库的连接的许多改进.  [GPL3] [2].
* [Incudine](http://incudine.sourceforge.net/)   -  Common Lisp的音乐/ DSP编程环境.  从头开始设计软件合成器或声音插件很有用.  它也是一种组合工具，可以在样本级别产生可控制的高质量声音，在运行中定义和重新定义数字信号处理器和音乐结构.
* [cl-collider](https://github.com/byulparan/cl-collider) - 一个
[SuperCollider](http://supercollider.github.io/)  CommonLisp的客户端.  有了 [tutorial](https://github.com/defaultxr/cl-collider-tutorial) 和 [live coding demos](https://www.youtube.com/watch?v=xzTH_ZqaFKI) .  公共区域.
* [csound](https://github.com/csound/csound)   - 声音和音乐计算系统.  包括Common Lisp的CFFI和FFI接口.
* [CLM](https://ccrma.stanford.edu/software/clm/)   -  Common Lisp Music是Music V系列中的音乐合成和信号处理软件包.  它提供了与Stk，Csound，SuperCollider，PD，CMix，cmusic和Arctic相同的功能 - 一系列创建和操作声音的功能，主要针对作曲家（无论如何都是在CLM的情况下）.
* [cl-patterns](https://github.com/defaultxr/cl-patterns)   - 一个通过Lisp代码编写音乐的系统，深受SuperCollider模式系统的启发，目的是实现其中的大部分内容，但是以更强大，更富有表现力，一致，反思和抒情的方式.  通过SuperCollider输出音频，初步支持Incudine，MIDI通过ALSA.
* [cl-openal](https://github.com/zkat/cl-openal)   -  OpenAL音频库的绑定.  公共区域.
* [Common Music](https://github.com/ormf/cm) - 一个存储库
古代版的Common Music（版本2.12.0），大概是最后一个
在2007-09之前的Common Lisp上运行的版本
共同音乐的工作转移到（基于计划）cm3.
* [cm-incudine](https://github.com/ormf/cm-incudine)   - 通过实时功能扩展Common Music 2.  GPL2.
* [Mégra](https://github.com/the-drunk-coder/megra)   - 使用可变顺序马尔可夫链和其他一些随机恶作剧制作音乐的迷你语言.  [GPL3] [2].
* [Music](https://github.com/MegaLoler/Music) -  Lisp中音乐表达的框架，侧重于音乐理论（从头开始构建，与Common Music无关）.
* [rq](https://github.com/openmusic-project/RQ) -  OpenMusic中的节奏转录库（版本6.10及更高版本）. [demo video](https://www.youtube.com/watch?v=XVEllB0TtVs) .  [GPL3] [2].
* [scheduler](https://github.com/byulparan/scheduler)   -  Common Lisp的基于时间的音乐事件调度程序.  [Apache2.0的] [51].
* [mixalot](https://github.com/ahefner/mixalot)   - 松散耦合的mp3，ogg vorbis，flac音频库集合.  用于 [Shuffletron music player](https://github.com/ahefner/shuffletron).
* [osc](https://github.com/zzkt/osc)   - 开放声音协议的实现.  [LGPL2.1] [11].
* [Harmony](https://shirakumo.github.io/harmony)   - 实时声音处理和回放系统.  [艺术许可2.0] [51].


构建系统
=============

*：明星： [ASDF](https://common-lisp.net/project/asdf/)   - 另一个系统定义设施;  Common Lisp的构建系统.  [外籍] [14].
* [asdf-linguist](https://github.com/eudoxia0/asdf-linguist)   -  ASDF的扩展.  [外籍] [14].
* [asdf-viz](https://github.com/guicho271828/asdf-viz)   - 可视化ASDF系统的库依赖关系，函数的调用图和类继承的工具.  [LLGPL] [8].

编译器，代码生成器
==========================

C，C ++
------

* [cmacro](https://github.com/eudoxia0/cmacro) -  C. [MIT] [200]的Lisp宏.
* [C-mera](https://github.com/kiselgra/c-mera)   - 源代码到源代码编译器，利用Lisp的宏系统进行类C语言的元编程.  [GPL3] [2].
* [lispc](https://github.com/eratosthenesia/lispc) -  C. [MIT] [200]的强大“lispsy”宏语言.
* [ecrepl](https://gitlab.common-lisp.net/ecl/ecrepl)   -  C语言的交互式REPL.  未指定许可证.


Crypto
======

*：明星： [Ironclad](https://github.com/sharplispers/ironclad)   -  Common Lisp的加密函数库.  不被认为是安全的，但对消息摘要功能仍然有用.  [外籍] [14].
* [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts)   - 收集常见的加密快捷方式.  [艺术许可2.0] [51].
* [trivial-ssh](https://github.com/eudoxia0/trivial-ssh)   -  SSH客户端库.  [外籍] [14].

Cryptocurrencies
================

* [cl-monero-tools](https://github.com/glv2/cl-monero-tools)   - 使用Monero加密货币的Common Lisp工具箱.  [GPL3] [2].  不在Quicklisp.
* [emotiq](https://github.com/emotiq/emotiq)   - 采用创新的自然语言方法实现智能合约的下一代区块链.  [MIT] [200].
* [peercoin-blockchain-parser](https://github.com/glv2/peercoin-blockchain-parser)   - 解析文件中包含的区块链，并将其部分数据导出到文本文件，SQL脚本或数据库.  它还可以使用Peercoin守护程序的RPC作为数据源而不是区块链文件来创建数据库.  LGPL3.  不在Quicklisp.
* [peercoin-calculator](https://github.com/glv2/peercoin-calculator)   - 该程序为您提供在10分钟，24小时，31天，90天和1年内生成POS或POW块的概率，以及可预期的奖励.  Qt中的GUI  [GPL3] [2].  不在Quicklisp.
* [peercoin-vote](https://github.com/glv2/peercoin-vote)   - 基于区块链数据（地址和余额）的投票系统.  [GPL3] [2].  不在Quicklisp.

Database
========

ORMs
----

*：明星： [clsql](http://www.cliki.net/CLSQL)   - 具有Common Lisp接口的SQL数据库.  [LLGPL] [8].
*  [mito](https://github.com/fukamachi/mito) - 具有迁移，关系和PostgreSQL支持的Common Lisp的ORM [LLGPL] [8]. [mitho-auth](https://github.com/fukamachi/mito-auth)，一个使用授权的混合类; [mito-attachment](https://github.com/fukamachi/mito-attachment)，一个用于RDBMS之外的文件管理的mixin类.
* [cl-dbi](https://github.com/fukamachi/cl-dbi)   -  Common Lisp的数据库独立接口.  [LLGPL] [8].
* [crane](https://github.com/eudoxia0/crane)   - 另一个ORM.  [外籍] [14].
* [datafly](https://github.com/fukamachi/datafly)   - 轻量级数据库库.  [3条款BSD] [15].
* [sxql](https://github.com/fukamachi/sxql)   - 用于生成SQL的DSL.  [3条款BSD] [15].

持久对象数据库
---------------------------

* [bknr.datastore](https://github.com/hanshuebner/bknr-datastore) -  RAM中具有事务日志记录持久性的基于CLOS的lisp-only数据库. [licence](http://bknr.net/html/license.html) .  （另见“Common Lisp Recipes”第21章）
* [elephant](https://common-lisp.net/project/elephant/)   -  Elephant是Common Lisp的持久对象数据库，具有完整的事务语义.  [LLGPL] [8].
* [ubiquitous](https://github.com/Shinmera/ubiquitous)   - 提供易于使用的持久配置存储的库.  [艺术许可2.0] [51].

Wrappers
--------

*：明星： [postmodern](http://marijnhaverbeke.nl/postmodern/)   - 用于与PostgreSQL交互的库.  [ZLIB] [33].
* [cl-sqlite](https://github.com/dmitryvk/cl-sqlite)   -  SQLite的绑定.  公共区域.
* [cl-memcached](https://github.com/quasi/cl-memcached)   -  Memcached对象缓存系统的快速，线程安全的接口.  [外籍] [14].
* [cl-mongo](https://github.com/fons/cl-mongo)   -  MongoDB客户端.  [外籍] [14].
* [cl-redis](https://github.com/vseloved/cl-redis)   -  Redis客户端.  [外籍] [14].
* [cl-disque](https://github.com/CodyReichert/cl-disque)   - 客户磁盘.  [3条款BSD] [15].
* [cl-rethinkdb](https://github.com/orthecreedence/cl-rethinkdb)   -  RethinkDB客户端.  [外籍] [14].
* [clouchdb](https://common-lisp.net/project/clouchdb/)   - 用于与CouchDB交互的库.  [FreeBSD的] [39].

给第三方
----------------

* [dyna](https://github.com/Rudolph-Miller/dyna)   -  AWS DynamoDB ORM.  [MIT] [200].
* [cl-influxdb](https://github.com/mmaul/cl-influxdb/)   - 时间序列数据库InfluxDB的接口.  [MIT] [200].

Tools
-----

* [pgloader](https://github.com/dimitri/pgloader)   -  PostgreSQL的数据加载工具.  [PostgreSQL许可证] [205].


数据结构
===============

*  [FSet](http://quickdocs.org/fset/)   - 功能集合理论集合数据结构库.  [LLGPL] [8].
* [bst](https://github.com/glv2/bst)   - 二叉搜索树.  [GPL3] [2].  不在Quicklisp.
* [pileup](http://nikodemus.github.io/pileup/)   -  Common Lisp的可移植，高性能和线程安全的二进制堆.  [MIT] [200].
* [sycamore](https://github.com/ndantam/sycamore)   - 一个快速，纯功能的数据结构库.  [BSD_3Clause] [15].
* [genhash](https://github.com/pnathan/genhash)   - 使用泛型方法API的哈希表实现.  公共区域.
* [cl-ctrie](https://github.com/danlentz/cl-ctrie) -
 无锁，并发，键/值索引，具有高效的内存映射持久性和快速瞬态存储模型.  [MIT] [200].
* [cl-data-structures](https://github.com/sirherrbatka/cl-data-structures)   - 可移植的数据结构和算法集合（主要是序列和序列，具有一些统计功能）.  [BSD] [15].

并了解更多 [Quickdocs](http://quickdocs.org/search?q=data+structure).


外部函数接口
==========================

## C ##

*：明星： [CFFI](https://github.com/cffi/cffi)   - 便携，易用的C外部功能接口.  [外籍] [14].
* [cl-autowrap](https://github.com/rpav/cl-autowrap)   - 自动将头文件解析为CFFI定义.  [FreeBSD的] [39].

## Java ##

* [cl+j](https://common-lisp.net/project/cl-plus-j/)   - 通过CFFI到JVM的基于JNI的接口.  在Quicklisp上不可用.  不能可靠地适用于所有实现.  [外籍] [14].

## Miscellaneous ##

* [Foil](http://foil.sourceforge.net/)   - 外来对象接口;  适用于JVM和CLI.  在Quicklisp上不可用.  [CPL 1.0] [47].

## Objective-C ##

* [objc-lisp-bridge](https://github.com/fiddlerwoaroof/objc-lisp-bridge)   - 便携式阅读器和桥接器，用于与Objective-C和Cocoa交互.  [MIT] [200].

## Python ##

* [burgled-batteries](https://github.com/pinterface/burgled-batteries)   -  Python和Common Lisp之间的桥梁.  目标是Lisp程序可以使用Python库.  在Quicklisp上不可用.  未指定许可证.
* [cl4py](https://github.com/marcoheisig/cl4py)   - 库cl4py（发音为clappy）允许Python程序调用Common Lisp库.  [MIT] [200].
* [py4cl](https://github.com/bendudson/py4cl)   - 允许Common Lisp代码访问Python库的库.  它基本上与cl4py相反.  [MIT] [200].
* [cl-python](https://github.com/metawilm/cl-python)   -  Common Lisp中的Python实现.  [LLGPL] [8].

也可以看看 [async-process](https://github.com/cxxxr/async-process/).

游戏开发
================

* [Xelf](http://xelf.me/)   - 可扩展的游戏库.  在Quicklisp上不可用.  [GNU LGPL2.1] [11].
* [Trial](https://github.com/shirakumo/trial) - 试用是一个OpenGL
   游戏引擎重点关注模块化.  它应该是
  提供一个有用的点点滴滴的大型工具包
   创造一个游戏.  [艺术许可2.0] [47].
* [cl-mpg123](https://shirakumo.github.io/cl-mpg123) 和
  [cl-out123](https://shirakumo.github.io/cl-out123)，绑定
  libmpg123和libout123的库分别为您提供快速
  并且易于使用mp3解码和跨平台音频
   输出.  [艺术许可2.0] [47].
* [trivial-gamekit](https://borodust.org/projects/trivial-gamekit/getting-started/) - 使用这个小框架，您将能够制作简单的2D游戏：绘制基本的几何形状，图像和文本，播放声音，听取鼠标和键盘输入.
* [cl-gamepad](https://shirakumo.github.io/cl-gamepad)   - 访问Windows，Mac OS和Linux上的游戏手柄和操纵杆.  [艺术许可2.0] [51].

Graphics
========

这些是用于处理图形的库，而不是制作具有各自部分的GUI（即窗口小部件工具包）.

*：明星： [Sketch](https://github.com/vydd/sketch)   - 用于创建电子艺术，图形等的CL框架.  [MIT] [200].
* [common-cv](https://github.com/byulparan/common-cv)   - 用于CommonLisp的OpenCV（开源计算机视觉库）绑定库.  未指定许可证.
* [cl-cairo2](https://github.com/rpav/cl-cairo2)   - 开罗绑定.  [Boost 1.0] [54]
* [cl-gd](http://weitz.de/cl-gd/)   - 提供GD图形库界面的库.  [FreeBSD的] [39].
* [cl-horde3d](https://github.com/anwyn/cl-horde3d/)   -  FFI绑定到Horde3D图形库.  在Quicklisp上不可用.  [EPL 1.0] [59]
* [cl-opengl](https://github.com/3b/cl-opengl)   -  CFFI绑定到OpenGL，GLU和GLUT API.  [3条款BSD] [15].
* [cl-sdl2](https://github.com/lispgames/cl-sdl2)   - 使用C2FFI绑定SDL2.  [外籍] [14].
* [cl-svg](https://github.com/wmannis/cl-svg)   - 用于生成SVG文件的基本库.  [外籍] [14].
* [CLinch](https://github.com/BradWBeer/CLinch)   - 用于OpenGL的Common Lisp 2D / 3D图形引擎.  [FreeBSD的] [39].
* [donuts](https://github.com/tkych/donuts)   - 用于Common Lisp的图形绘制DSL.  [外籍] [14].
* [dufy](https://github.com/privet-kitty/dufy)   - 在各种颜色模型中进行精确的颜色处理和转换.  [MIT] [200].
* [lispbuilder-sdl](https://github.com/lispbuilder/lispbuilder)   -  SDL的一组绑定.  [外籍] [14].
* [lisp-magick-wand](https://github.com/TBRSS/lisp-magick-wand)   -  ImageMagick绑定.  [BSD] [15].  不在Quicklisp.
* [okra](https://www.common-lisp.net/project/okra/manual.html)   -  CFFI绑定到Ogre.  在Quicklisp上不可用.  [3条款BSD] [15].
* [opticl](https://github.com/slyrus/opticl)   - 用于表示和处理图像的库.  [BSD_2Clause] [17].
* [Varjo](https://github.com/cbaggers/varjo)   -  Lisp到GLSL翻译.  [BSD_2Clause] [17].
* [Vecto](http://www.xach.com/lisp/vecto/)   - 简单的矢量绘图库.  [FreeBSD的] [39].
* [zpng](http://www.xach.com/lisp/zpng/)   - 用于创建PNG文件的库.  [FreeBSD的] [39].


GUI
===

*  [Qtools](https://github.com/Shinmera/qtools/)   - 基于CommonQt的Qt工具包.  [艺术许可2.0] [51]此外 [Qtools-ui](https://github.com/Shinmera/qtools-ui) （预制的UI组件），用 [videos](https://www.youtube.com/watch?v=KwASFOhYta4&index=7&list=PLkDl6Irujx9Mh3BWdBmt4JtIrwYgihTWp).
*：明星： [CommonQt](https://github.com/commonqt/commonqt)   - 通过QtSmoke对Qt4进行Common Lisp绑定.  [FreeBSD的] [39].
*：明星： [ltk](http://www.peter-herth.de/ltk/)   -  Tk工具包的绑定.  [LLGPL] [8]或[GNU LGPL2.1] [11].
* [nodgui](https://notabug.org/cage/nodgui)   - 基于Ltk的Tk工具包的绑定，带有语法糖和其他小部件.  [LLGPL] [8].
* [cl-cffi-gtk](http://www.crategus.com/books/cl-cffi-gtk/)   - 绑定GTK + 3.  [GNU LGPL2.1] [11].
* [cl-gtk2](https://github.com/dmitryvk/cl-gtk2)   -  GTK + 2的绑定.  [LLGPL] [8].
* [ceramic](https://ceramic.github.io/)   - 使用Electron的桌面Web应用程序.  [外籍] [14].
* [CocoaInterface](https://github.com/plkrueger/CocoaInterface/) -
 Clozure Common Lisp的Cocoa接口.  构建Cocoa用户界面
Windows动态使用Lisp代码并绕过典型的Xcode
 流程.  它有
[good documentation and a tutorial](https://github.com/plkrueger/CocoaInterface/blob/master/Documentation/UserInterfaceTutorial.pdf).
* [McCLIM](https://common-lisp.net/project/mcclim/)   -  Common Lisp Interface Manager的实现，版本II.  [GNU LGPL2.1] [11].
* [cl-webkit](https://github.com/joachifm/cl-webkit)   - 与WebKitGTK +的绑定.  还为应用程序添加了Web浏览功能，充分利用了WebKit浏览引擎的强大功能.  [MIT] [200].
* [ftw](https://github.com/fjames86/ftw)   -  Win32 GUI库.  [MIT] [200].
* [cl-xul](https://github.com/mmontone/cl-xul)   -  Mozilla XUL绑定.  [外籍] [14].
* [eql, eql5, eql5-android](https://gitlab.com/eql)   - 嵌入在ECL中的嵌入式Qt4和Qt5 Lisp嵌入在Qt中.  EQL5端口到Android平台.  [MIT] [200].
* [bodge-nuklear](https://github.com/borodust/bodge-nuklear) - 包裹在上面 [Nuklear](https://github.com/vurtun/nuklear)  即时模式GUI库.  [MIT] [200].


Implementations
===============

*：明星： [SBCL](http://www.sbcl.org/index.html)   -  CMUCL的一个分支;  编译成机器代码.  [标准合规] [13].  公共领域，[Expat] [14]和[3-clause BSD] [15]下的部分内容.
*：明星： [CCL](https://github.com/CodyReichert/awesome-cl/blob/master///ccl.clozure.com/)   -  Clozure Common Lisp;  仅编译器实现，生成本机代码.  [LLGPL] [8].
* [ECL](https://common-lisp.net/project/ecl/)   -  Embeddable Common Lisp;  编译成C. [GNU LGPL2.1] [11].
* [ABCL](https://common-lisp.net/project/armedbear/)   - 武装熊Common Lisp;  以JVM为目标，编译为字节码.  [标准一致性] [4].  [GNU GPL3] [2] [Classpath exception] [3].
* [CMUCL](https://github.com/CodyReichert/awesome-cl/blob/master///www.cons.org/cmucl/)   - 卡内基梅隆大学的实施.  公共区域.
* [GNU CLISP](http://www.clisp.org/)   -  GNU实现;  包含编译器和解释器.  [标准一致性] [6].  [GNU GPL3] [2].
* [CLASP](https://github.com/drmeister/clasp)   - 一个新的Common Lisp实现，它使用LLVM与C ++库和程序无缝互操作，以便编译为本机代码.  这使得Clasp可以利用大量先前存在的库和程序，例如科学计算生态系统.  [LGPL2.1] [11]（和其他人）.
* [Corman Lisp](https://github.com/sharplispers/cormanlisp)   - 适用于在Intel平台上运行的Microsoft Windows的Common Lisp开发环境.  [MIT] [200].

Proprietary:

* [Lispworks](http://www.lispworks.com/) -  Common Lisp的集成跨平台开发工具.
* [Allegro CL](https://franz.com/products/allegro-common-lisp/) - 提供具有许多扩展的完整ANSI Common Lisp标准.
* [MOCL](https://wukix.com/mocl) -  CL作为移动设备（iOS和Android）和OSX的库.

JSON
====

* [cl-json](https://github.com/hankhero/cl-json)   -  JSON编码器和解码器.  [外籍] [14].
* [jsown](https://github.com/madnificent/jsown)   -  JSON格式的读写器.  [外籍] [14].
* [json-mop](https://github.com/gschjetne/json-mop)   - 用于桥接CLOS和JSON对象的元类.  [MIT] [200].

另见 [extensive comparison](https://sites.google.com/site/sabraonthehill/home/json-libraries) JSON库.

YAML
====

* [cl-yacclyaml](https://github.com/mabragor/cl-yaclyaml)   - 一个纯粹的lisp YAML处理器（加载器，但还没有转储器）.  [GPL3] [2].
* [cl-yaml](https://github.com/eudoxia0/cl-yaml.git)   - 在libyaml之上构建的YAML解析器和发射器.  [MIT] [200].


语言扩展
===================

* [cl21](https://github.com/cl21/cl21)   - 将Common Lisp推向21世纪的实验项目.  [外籍] [14].
*：明星： [alexandria](https://common-lisp.net/project/alexandria/)   - 通用实用程序库.  公共区域.
* [serapeum](https://github.com/TBRSS/serapeum/)   - 另一个通用实用程序库.  [外籍] [14].
* [anaphora](https://common-lisp.net/project/anaphora/)   - 一系列照应宏.  公共区域.
* [cl-algebraic-data-type](https://github.com/tarballs-are-good/cl-algebraic-data-type)   - 用于以与Haskell或ML类似的精神定义代数数据类型的库.  [3条款BSD] [15].
*：明星： [optima](https://github.com/m2ym/optima)   - 优化的模式匹配库.  [LLGPL] [8].
* [str](https://github.com/vindarel/cl-str)   - 一个现代，简单和一致的字符串操作库.  [MIT] [200].
* [trivial-types](https://github.com/m2ym/trivial-types)   - 琐碎的类型定义.  [LLGPL] [8].
* [interface](https://bitbucket.org/tarballs_are_good/interface)   - 协议库.  [3条款BSD] [15].
* [cl-syntax](https://github.com/m2ym/cl-syntax)   -  Reader语法约定.  [LLGPL] [8].
* [cl-2dsyntax](http://www.cliki.net/cl-2dsyntax)   - 缩进敏感的阅读器系统.  在Quicklisp上不可用.  未指定许可证.
* [cl-annot](https://github.com/m2ym/cl-annot)   -  Common Lisp的类似Python的注释.  [LLGPL] [8].
*：明星： [cl-interpol](http://www.cliki.net/cl-interpol)   - 一组允许字符串插值的读者修改.  未指定许可证.
* [arrow-macros](https://github.com/hipeta/arrow-macros)   - 类似Clojure的线程宏.  [MIT] [200].
* [dissect](https://shinmera.github.io/dissect) - 很多时候
  项目使用“琐碎的回溯”系统，只给他们一个
  带有回溯的字符串，Dissect允许你捕获，步进和
  完全检查各种Lisp上的堆栈跟踪
   实现.  对于日志记录和其他情况也非常有用
  执行自动继续，但信息
  当前堆栈仍然可用于存储
  somewhere. [Artistic License 2.0][51].
* [clamp](https://github.com/malisper/Clamp)   -  Arc语言对Common Lisp的简洁和简洁.  [艺术许可2.0] [51].
* [trivial-arguments](https://github.com/Shinmera/trivial-arguments) -
   一个可移植的库，用于检索函数的参数列表.  [艺术许可2.0] [51].
* [modf](https://github.com/smithzvk/modf) - 用于函数式编程的类似setf的宏.
* [generic-cl](https://github.com/alex-gutev/generic-cl/)   - 标准Common Lisp函数的通用函数接口（相等，比较，算术，对象，迭代器，序列......）.  [MIT] [200].
* [pythonic-string-reader](https://github.com/smithzvk/pythonic-string-reader)   - 一个简单而不显眼的读表修改，灵感来自Python的三个引用字符串.  [BSD_3Clause] [15].
*  [access](https://github.com/AccelerationNet/access/)   - 对大多数常见数据结构的一致和嵌套访问.  [BSD_3Clause] [15].


CLOS扩展
---------------

*：明星： [closer-mop](http://cliki.net/closer-mop)   - 兼容层，可纠正许多缺失或不正确的MOP功能.  [外籍] [14].
* [defclass-std](https://github.com/EuAndreh/defclass-std)   - 快速编写DEFCLASS表单的快捷方式宏.  [LLGPL] [8].


Iteration
---------

*：明星： [iterate](https://common-lisp.net/project/iterate/)   -  Common Lisp的迭代构造，它是可扩展的和Lispier.  未指定许可证.
* [for](https://shinmera.github.io/for/) - 简洁，lispy和可扩展
   迭代宏.  与循环不同，它是可扩展和合理的，并且
  与迭代不同，它不需要代码行走，而且更容易
   延伸.  [艺术许可2.0] [51].
* [series](https://github.com/tokenrove/series/wiki)   - 功能风格，没有任何运行时惩罚.  [MIT] [200].


Lambda shorthands
-----------------

* [fn](https://github.com/cbaggers/fn)   - 几个lambda速记宏.  `（fn *（+ _ _）） - &gt;（lambda（_）（+ _ _））`.  公共区域.
* [f-underscore](http://quickdocs.org/f-underscore/api)   - 一个功能编程工具库.  `（f_（+ _ _）） - &gt;（lambda（_）（+ _ _））`.  公共区域.
* [cl-chump](https://github.com/windymelt/cl-punch/)   - 类似Scala的匿名lambda文字.  `（mapcar ^（* 2 _）&#39;（1 2 3 4 5））`.  [MIT] [200].


另见CL21和Rutils.



非确定性的逻辑编程
------------------------------------

* [cl-prolog2](https://github.com/guicho271828/cl-prolog2)   -  Common Lisp的ISO Prolog实现的通用接口.  [MIT] [200].
* [Screamer](https://github.com/nikodemus/screamer) - 增加共同点
  Lisp几乎具有Prolog和.的所有功能
  约束逻辑编程
  语言. [Blog post](https://chriskohlhepp.wordpress.com/reasoning-systems/specification-driven-programming-in-common-lisp/)
   解决项目欧拉难题.  [MIT] [200].
* [Screamer+](https://github.com/yakovzaytsev/screamer-plus)   - 增加SCREAMER的表现力.  [MIT] [200].
* [Temperance](https://sjl.bitbucket.io/temperance/)   - 逻辑编程.  [MIT] [200].  关注性能，以一般游戏为主题.

反应式编程
--------------------

* [Cells](https://github.com/kennytilton/cells)   - 数据流编程范例的实现，CLOS的反应式电子表格式表达.  用来建立一个 [algebra learning system](http://tiltontec.com/) .  同 [documentation](https://github.com/stefano/cells-doc/) .  Lisp LGPL.

合同编程
--------------------

* [quid-pro-quo](https://github.com/sellout/quid-pro-quo) - 合同
   符合Eiffel&#39;s Design by Contract™风格的编程库.  公共区域.


学习和教程
=====================

## Online ##

Beginner
--------

* [Learn X in Y minutes - Where X = Common Lisp](https://learnxinyminutes.com/docs/common-lisp/) - 小型Common Lisp教程，涵盖了必需品.
 * [Practical Common Lisp] [206]  -  Common Lisp的一个很好的介绍性文本，附带实例.  （更好地阅读 [a Firefox add-on](https://addons.mozilla.org/de/firefox/addon/beautify-practical-common-lisp/?src=search))
* [Common LISP: A Gentle Introduction to Symbolic Computation](http://www.cs.cmu.edu/afs/cs.cmu.edu/user/dst/www/LispBook/index.html) - 对语言的一个很好的介绍.
* [Learn LISP: Simply Easy Learning](http://www.tutorialspoint.com/lisp/index.htm)   - 一套很好的入门教程;  包括交互式示例.
* [Successful Lisp](http://successful-lisp.blogspot.com/) - 一本适合初学者的好书，有一些编程背景.
* [Common Lisp Koans] [201]  - 该项目通过许多Common Lisp语言功能逐步指导学习者.
* [Lisp Quickstart](https://cs.gmu.edu/~sean/lisp/LispTutorial.html) - 一个很好的教程，可以快速启动并编写Common Lisp.
* [Casting SPELs in LISP](http://www.lisperati.com/casting.html) - 在阅读漫画书时学习LISP的有趣方式.

Intermediate
------------

* [The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/)
* [Common Lisp tips](http://lisptips.com/) - 一个博客，提供有用的提示和技巧.
* [CommonQt tutorial](https://cheryllium.wordpress.com/2014/02/22/commonqt-tutorial-1/) - 对CommonQt的一个很好的介绍.
* [A tutorial for creating and publishing open-source Common Lisp software](https://arxiv.org/abs/1209.5626) - 使用Quicklisp和一系列其他工具在Common Lisp中创建和发布项目的简便教程.

Advanced
--------

 * [Let Over Lambda] [156]  - 一本关于高级宏观技术的书.  前六章可在​​线获取.
* [On Lisp](http://www.paulgraham.com/onlisp.html) - 保罗格雷厄姆关于Lisp宏（和其他有趣的东西）的惊人书籍.

Reference
---------

* [Common Lisp Quick Reference](http://clqr.boundp.org/index.html)   -  ANSI CL规格的蒸馏口袋版本.  可以PDF格式下载.
* [CLHS](http://www.lispworks.com/documentation/lw50/CLHS/Front/index.htm)   -  Common Lisp HyperSpec;  ANSI CL标准，以超文本形式.
* [CLOS MOP specification](https://clos-mop.hexstreamsoft.com/) - 元对象协议艺术第5章和第6章的现代公共领域在线版本
* [Common Lisp Standard Draft](http://cvberry.com/tech_writings/notes/common_lisp_standard_draft.html) -  Common Lisp规范的最终草案，格式良好的PDF.
* [Common Lisp the Language](http://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html) -  ANSI规范之前的Common Lisp的原始标准.
* [Minispec](https://lamberta.github.io/minispec/)   - 一个更友好但不太完整的CLHS版本.  还包含一些常用CL库（如Alexandria）的文档.
* [Simplified Common Lisp reference](http://jtra.cz/stuff/lisp/sclr/index.html) -  CLHS的简化版本.
* [Quickdocs](http://quickdocs.org/) -  Quicklisp提供的库的参考.

## Offline ##

Beginner
--------

* [Land of Lisp](http://landoflisp.com/) - 一个有趣的，面向游戏的Common Lisp简介.
* [Practical Common Lisp] [206]  -  Common Lisp的一个很好的介绍性文本，附带实例.
* [Common Lisp Koans] [201]  - 该项目通过许多Common Lisp语言功能逐步指导学习者.

Intermediate
------------

* [ANSI Common Lisp](http://www.paulgraham.com/acl.html)   - 通过练习全面，实用地覆盖整个语言.  由于[一些警告] [20]，不推荐作为入门文本.
* [Common Lisp Recipes](http://weitz.de/cl-recipes/)   -  ** Common Lisp Recipes **是一系列问题解决方案，也是您在Common Lisp中编写实际应用程序时可能遇到的问题的答案.  2015年出版.

Advanced
--------

 * [Let Over Lambda] [156]  - 一本关于高级宏观技术的书.  打印副本中提供了所有八个章节.
* [Common Lisp中的面向对象编程：CLOS程序员指南] [21]  - 一本关于CLOS的旧的但非常全面的书.
* [人工智能编程的范例：Common Lisp中的案例研究] [157]  - 一本关于编程AI的书，涵盖了一些高级的Lisp.

Community
---------

* [/r/Common_Lisp](https://www.reddit.com/r/Common_Lisp/) - 关于Common Lisp的subreddit
* [common-lisp.net](https://common-lisp.net)
* [lisp-lang.org](https://lisp-lang.org/)
* [Lisp Discord Server](https://discord.gg/T5D2EAJ)
* [#lisp](http://log.irc.tymoon.eu/freenode/lisp) 在Freenode上 - 主要的Common Lisp IRC频道.

图书馆经理
===============

 *：star：[Quicklisp] [16]  - 包含许多库的库管理器，具有简单的依赖性管理.  [外籍] [14].
* [Ultralisp](http://ultralisp.org/)   -  Quicklisp发行版，每5分钟更新一次，只需单击一下即可添加项目.  [BSD] [15].
* [Quicksys](https://lisp.com.br/quicksys/)   - 从多个Quicklisp发行版安装系统.  [MIT] [200].
* [Roswell](https://github.com/roswell/roswell)   -  Lisp实现安装程序，脚本启动程序等.  [MIT] [200].
* [qlot](https://github.com/fukamachi/qlot)   - 项目本地库安装程序，类似于Bundler或Carton.  [外籍] [14].
* [Quickutil](https://github.com/tarballs-are-good/quickutil)   - 一个实用程序管理器，类似于Quicklisp，但适用于小型实用程序而不是整个库.  [3条款BSD] [15].
* [Qi](https://github.com/CodyReichert/qi)   - 具有传统方法的包管理器.  [BSD] [15].

可能有帮助：

* [print-licenses](https://github.com/vindarel/print-licenses)   - 打印项目使用的许可证及其依赖项.  [MIT] [200].

### Interfaces to other package managers

* [cl-brewer](https://github.com/can3p/cl-brewer)   - 用于（命令行）常见lisp应用程序的Homebrew公式构建器.  公共区域.
* [qldeb](https://github.com/ralt/qldeb) -  Quicklisp系统到debian包，以及 [deb-packager](https://github.com/ralt/deb-packager) （只需通过定义一个s表达式创建一个debian包）和一个介绍 [blog post](http://margaine.com/2015/12/22/quicklisp-packagecloud-debian-packages.html) .  两个[麻省理工学院] [200].
* [ql-to-deb](https://github.com/dimitri/ql-to-deb)   - 从Quicklisp版本更新cl- * debian软件包.  WTFPL.

机器学习
================

* [clml](https://github.com/mmaul/clml)   - 最初由日本公司Mathematicl Systems Inc.开发.  有了 [tutorial](https://mmaul.github.io/clml.tutorials//2015/08/08/CLML-Time-Series-Part-1.html) .  [LLGPL] [8].
* [mgl](https://github.com/melisgl/mgl) - 由它使用 [author](http://quotenil.com/) 至 [win](https://github.com/melisgl/higgsml)  希格斯玻色子机器学习挑战赛.  [MIT] [200].
* [antik](https://www.common-lisp.net/project/antik/)   -  Common Lisp中科学和工程计算的基础.  GPL.  也 [mgl-mat](https://github.com/melisgl/mgl-mat) 和 [LLA](https://github.com/tpapp/lla).

Credit: [borretti.me' state of CL ecosystem 2015](http://borretti.me/article/common-lisp-sotu-2015#machine-learning).


自然语言处理
===========================

* [cl-nlp](https://github.com/vseloved/cl-nlp)   - 自然语言处理工具集.  [Apache2.0的] [89].
* [babel2](http://emergent-languages.org/Babel2/) - 流体构造语法实现，计算框架和基于统一的语法形式[Apache2.0] [89].
* [sparser](https://github.com/ddmcdonald/sparser) - 天然
 英语语言理解系统.  [Eclipse的] [209].



网络和互联网
====================

See [Cliki](http://www.cliki.net/Web) 更多.

HTTP客户端
------------
*  [Dexador](https://github.com/fukamachi/dexador) - 旨在实现的HTTP客户端 [replacing Drakma](http://quickdocs.org/dexador/) ，  [带] [200].
* [Carrier](https://github.com/orthecreedence/carrier)   - 基于cl-async和fast-http构建的轻量级异步HTTP客户端.  [MIT] [200].
* [fast-http](https://github.com/fukamachi/fast-http) - A fast HTTP
 Common Lisp的请求/响应解析器.  [MIT] [200].


HTTP服务器
------------
* [Clack](https://github.com/fukamachi/clack)   - 受Rack和WSGI启发的Web应用程序环境.  [LLGPL] [8].  为所选的Web服务器提供统一的界面（默认为Hunchentoot）.
*：明星： [Hunchentoot](http://weitz.de/hunchentoot/)   -  Web服务器.  [2条款BSD] [207]
* [aserve](https://github.com/franzinc/aserve)   -  AllegroServe;  一个Web服务器.  [LLGPL] [8].
* [wookie](https://github.com/orthecreedence/wookie)   - 异步HTTP服务器.  [外籍] [14].
* [woo](https://github.com/fukamachi/woo)   -  libev上的快速非阻塞HTTP服务器.  [MIT] [200].

### Clack plugins

* [clack-errors](https://github.com/eudoxia0/clack-errors)   -  Clack的错误页面中间件.  [LLGPL] [8].
* [clath](https://github.com/BnMcGn/clath) - 单点登录
   克拉克的中间件.  它允许使用OAuth1.0a，OAuth2进行基本登录
   和OpenID.  在撰写本文时，它支持来自的身份验证
   Google，Twitter，LinkedIn，StackExchange，Reddit和Github.  [Apache2.0的] [51].
* [clack-pretend](https://github.com/BnMcGn/clack-pretend) - a testing
   和调试工具.  [Apache2.0的] [89].
* [hermetic](https://github.com/eudoxia0/hermetic)   - 基于Clack的Web应用程序的安全性.  [外籍] [14].
* [live-reload](https://github.com/knobo/live-reload)   - 为clack重新加载原型.  [LLGPL] [8].
* [clack-static-asset-middleware](https://github.com/fisxoj/clack-static-asset-middleware)   - 一个破解缓存的静态资产中间件.  [MIT] [200].

Web框架
--------------

* [Caveman](https://github.com/fukamachi/caveman)   - 强大的Web框架.  [LLGPL] [8].
  示例项目： [Quickdocs](https://github.com/quickdocs)
* [hh-web](https://github.com/hargettp/hh-web)   - 构建现代Web应用程序的框架.  [外籍] [14].
* [ningle](https://github.com/fukamachi/ningle)   - 超级微型Web框架.  [LLGPL] [8]. [ninglex](https://github.com/defunkydrummer/ninglex) ，一个扩展的和noob友好的ningle（更容易处理查询参数）.  [MIT] [200].
* [radiance](https://github.com/Shirakumo/radiance)   -  Web应用程序环境和框架.  [艺术许可2.0] [51].
* [Lucerne](https://github.com/eudoxia0/lucerne)   - 基于Flack构建的基于Clack的最小Web框架.  [MIT] [200].
* [Snooze](https://github.com/joaotavora/snooze)   - 一个基于Clack构建的RESTful Web框架，其中路由只是函数，HTTP条件只是Lisp条件.  [LLGPL] [8].
* [cl-rest-server](https://github.com/mmontone/cl-rest-server)   - 用于编写REST Web API的库.  功能验证包括模式，日志记录，缓存，权限或身份验证注释，Swagger文档等.[MIT] [200].
* [Weblocks](https://github.com/40ants/weblocks)   - 基于窗口小部件的框架，内置ajax更新机制，“解决JavaScript问题”.  [LLGPL] [8].

 有更多项目，或多或少停产但有趣.  查看其他资源.


资产管理
-----------------

* [Rock](https://github.com/eudoxia0/rock) - 资产经理
   Common Lisp.  它基本上是Bower和Bower的组合
   Webassets.  [带] [200].


解析HTML
------------
 * [丰满] [71]  - 宽松的HTML / XML解析器，容忍格式错误的标记.  [艺术许可2.0] [51].  最适合[lquery] [72]和 [clss](https://github.com/Shinmera/CLSS).

查询HTML / DOM
-----------------
 * [lquery] [72]  - 类似jQuery的HTML / DOM操作库.  [艺术许可2.0] [51].

有关xpath库的信息，请参阅下面的XML部分.


HTML生成器和模板
-----------------------------
*  [spinneret](https://github.com/ruricolist/spinneret)   -  Common Lisp HTML5生成器.  [外籍] [14].
* [flute](https://github.com/ailisp/flute) - 一个易于组合的HTML5生成库
   最简单的语法.  [MIT] [200].
*：明星： [cl-who](http://weitz.de/cl-who/)   - 古老的HTML生成器.  [FreeBSD的] [39].
*：明星： [Djula](https://github.com/mmontone/djula)   -  Django的Common Lisp模板引擎端口.  [外籍] [14].
* [cl-markup](https://github.com/arielnetworks/cl-markup)   - 现代标记生成库.  [LLGPL] [8].
* [eco](https://github.com/eudoxia0/eco)   - 快速，灵活，设计师友好的模板引擎.  [外籍] [14].
* [cl-closure-template](https://github.com/archimag/cl-closure-template)   - 实施Google的Closure模板.  [LLGPL] [8].
* [clip](https://shinmera.github.io/clip)   -  HTML模板处理器，其中模板以HTML编写.  [艺术许可2.0] [51].

URI动作
------------

* [quri](https://github.com/fukamachi/quri) - 另一个URI库
   Common Lisp.  支持userinfo，IPv6主机名，编码/解码
  公用事业，...... [BSD_3Clause] [15].
* [purl](https://github.com/eugeneia/purl)   - 提供解析器并定义RFC1738中指定的URL类型.  [GNU GPL3] [2].
* [cl-slug](https://github.com/EuAndreh/cl-slug)   - 一个小型库，用于制作slug，主要用于URI，在CamelCase中转换，删除重音和标点符号，用于英语和beyound.  [LLGPL] [8].

Javascript
----------

*：明星： [Parenscript](https://github.com/vsedach/Parenscript)   - 从Common Lisp到Javascript的翻译.  [3条款BSD] [15].  看到 [Trident-mode](https://github.com/johnmastro/trident-mode.el)，一种Emacs模式，提供与浏览器的实时交互.[unlicence] [5].
* [parse-js](http://marijnhaverbeke.nl/parse-js/) - 用于解析ECMAScript 3的包.[zlib] [33].
* [JSCL](https://github.com/jscl-project/jscl)   - 从第一天开始设计为自托管的CL-to-JS编译器.  缺乏CLOS，格式和循环.
* [CL-JavaScript](http://marijnhaverbeke.nl/cl-javascript/)   - 从Javascript到Common Lisp的翻译.  在Quicklisp上不可用.  [外籍] [14].
* [Wuwei](https://github.com/mtravers/wuwei/)   - 用于构建基于Ajax的Web页面的工具包.  [MIT] [200].
* [SmackJack](https://github.com/aarvid/SmackJack)   - 使用parenscript生成javascript和hunchentoot（现在）作为Web服务器的Ajax Common Lisp库.  还允许服务器端lisp函数调用客户端parenscript函数.  [MIT] [200].
* [Panic](https://github.com/michaeljforster/panic) ，React的Parenscript库.  不在Quicklisp.  [MIT] [200].  它 [TodoMVC example](https://github.com/40ants/todomvc/blob/common-lisp-example/examples/common-lisp-react/src/app.lisp).

也可以看看
[trident-mode](https://github.com/johnmastro/trident-mode.el)，一个Emacs
现场Parenscript互动的次要模式.


Email
-----

* [trivial-imap](https://github.com/40ants/trivial-imap)   - 尝试简化一些使用IMAP服务器的常见情况，例如从服务器读取电子邮件.  邮局图书馆（这是Franz的cl-imap的一个分支）的薄包装.  [BSD] [15].
* [mailgun](https://github.com/40ants/mailgun)   - 通过mailgun.com发布HTML电子邮件的瘦包装器.  未指定许可证.
* [mito-email-auth](https://github.com/40ants/mito-email-auth) - 帮助者通过电子邮件向他们发送唯一代码来验证网站的用户.


Websockets
----------

*  [usocket](https://github.com/usocket/usocket)   - 便携式TCP和UDP套接字接口.  [外籍] [14].
* [websocket-driver](https://github.com/fukamachi/websocket-driver)   -  WebSocket服务器/客户端实现，后端不可知（Clack）.  [3条款BSD] [15].

看更多 [on cliki](http://www.cliki.net/site/search?query=websockets).

静态站点生成器
----------------------

* [coleslaw](https://github.com/kingcons/coleslaw) 和它
  [coleslaw-cli](https://github.com/40ants/coleslaw-cli) - 灵活
   Lisp Blogware类似于Frog，Jekyll或Hakyll.  [BSD] [15].

Deployment
----------

* [heroku-buildpack-common-lisp](https://gitlab.com/duncan-bayne/heroku-buildpack-common-lisp)   - 使用Roswell编译Common Lisp应用程序的Heroku buildpack.  LGPL3.
* [cube](https://github.com/xh4/cube)   - 从Swagger规范生成的用于Common LISP的Kubernetes客户端库.  未指定许可证.
* [base-lisp-image](https://github.com/40ants/base-lisp-image) - 基地
  使用SBCL或CCL和最新版本的Common Lisp项目的Docker镜像
  ASDF，Qlot和Roswell.
* [s2i-lisp](https://github.com/container-lisp/s2i-lisp)   - 基于CentOS或RHEL7的Source-to-Image构建器映像，用于为OpenShift（以及Docker）构建Common LISP映像.  它具有最新的SBCL和Quicklisp安装，SLIME或SLY集成，并允许通过环境变量进行自定义.  [AGPL] [89]
* [deploy](https://shinmera.github.io/deploy)   - 用于Lisp应用程序二进制部署的工具包，以及对外部共享库的额外支持.  [艺术许可2.0] [51].
* [cl-aws-runtime-test](https://github.com/y2q-actionman/cl-aws-custom-runtime-test)   - 使用Common Lisp（SBCL）作为AWS lambda上的自定义运行时的示例.  WTFPL.

也可以看看 [Heliohost](https://www.heliohost.org/) 免费托管解决方案.

Monitoring
----------

* [prometheus.cl](https://github.com/deadtrickster/prometheus.cl)   -  Prometheus.io客户端.  用于SBCL和Hunchentoot指标的Grafana仪表板（内存，线程，每秒请求数......）.  [MIT] [200].


第三方API
----------------

* [Aws-sign4](https://github.com/rotatef/aws-sign4) - 用于Amazon Web Services签名版本4的Common Lisp库.[GNU GPL3] [2].
* [zs3](https://github.com/xach/zs3) - 用于处理亚马逊简单存储的库
 服务（S3）和CloudFront服务.  [BSD] [15].
* [cl-ses](https://github.com/CodyReichert/cl-ses/)   -  AWS SES库.  [外籍] [14].
* [north](https://shinmera.github.io/north) - 继承人
  南（Simple OaUTH）库，实现完整的oAuth 1.0a
   协议，客户端和服务器端.  使用North可以轻松实现
   成为oAuth提供商或消费者.  [艺术许可2.0] [51].
* [avatar-api](https://github.com/eudoxia0/avatar-api)   - 从Google+，Gravatar和其他人那里获取头像.  [外籍] [14].
* [chirp](https://github.com/Shinmera/chirp)   - 一个Twitter客户端库.  [艺术许可2.0] [51].
* [tooter](https://github.com/Shinmera/tooter)   - 为Mastodon实现完整v1 REST API协议的客户端库.  [ArtisticLicense2.0] [51].
* [cl-irc](https://www.common-lisp.net/project/cl-irc/)   -  IRC客户端库.  [外籍] [14].
* [cl-mediawiki](https://github.com/AccelerationNet/cl-mediawiki)   -  MediaWiki api的包装器.  [MIT] [200].
* [cl-openid](https://github.com/cl-openid/cl-openid)   -  OpenID的实现.  [LLGPL] [8].
* [cl-pushover](https://github.com/TeMPOraL/cl-pushover)   - 与Pushover的Common Lisp绑定.  [MIT] [200].
* [humbler](https://github.com/Shinmera/humbler)   -  Tumblr API接口.  [艺术许可2.0] [51].
*[multiposter](https://github.com/Shinmera/multiposter) - 同时发布到多个服务.
* [stripe-client](https://github.com/ruricolist/cl-stripe-client)   -  Stripe支付系统的客户.  [MIT] [200].

Others
------

* [maiden](https://shirakumo.github.io/maiden)   - 支持IRC等的机器人和聊天系统框架.  [艺术许可2.0] [51].
* [css-lite](https://github.com/paddymul/css-lite)   -  CSS语法.  [外籍] [14].
* [find-port](https://github.com/eudoxia0/find-port)   - 以编程方式查找开放端口.  [MIT] [200].
* [cl-forms](https://github.com/mmontone/cl-forms)   - 用于Common lisp的Web表单处理库.  [MIT] [200].
* [Postmaster](https://github.com/eudoxia0/postmaster)   - 简单易用的SMTP / IMAP库.  [外籍] [14].
* [cl-selenium-webdriver](https://github.com/TatriX/cl-selenium-webdriver/) -  Selenium 2.0的绑定库.

数值和科学
========================

* [numcl](https://github.com/numcl/numcl) - Numpy clone in Common Lisp. [LGPL3][9].
* [magicl](https://github.com/rigetticomputing/magicl)   -  Matrix Algebra proGrams在Common Lisp中基于BLAS / LAPACK和Expokit，由Rigetti Computing提供.  [BSD_3Clause] [15].
* [cl-spark](https://github.com/tkych/cl-spark)   - 为数字列表生成迷你字符串.  [外籍] [14].
* [GSLL](https://common-lisp.net/project/gsll/)   - 用于Lisp的GNU科学图书馆;  允许使用Common Lisp中的GSL.  [GNU LGPL2.1] [11].
* [common-lisp-stat](https://github.com/blindglobe/common-lisp-stat/)   -  Common Lisp统计库.  [FreeBSD的] [39].
* [maxima](http://maxima.sourceforge.net/)   - 计算机代数系统.  在Quicklisp上不可用.  [GNU GPL3] [2].
* [lisp-matrix](https://github.com/blindglobe/lisp-matrix)   - 矩阵包.  [FreeBSD的] [39].
* [3-matrices](https://shinmera.github.io/3d-matrices) - 图书馆实施
  常见的矩阵计算，重点是2x2,3x3和4x4
   矩阵常用于图形中.  它提供了一些数字
   功能也是如此，但那些不是焦点.  图书馆是
  大大优化，所以它不是漂亮
   码.  [艺术许可2.0] [51].
* [Xecto](https://github.com/pkhuong/Xecto)   - 用于常规数组并行的库.  [3条款BSD] [15].
* [Petalisp](https://github.com/marcoheisig/Petalisp) - 尝试
  通过生成并行计算机的高性能代码
   JIT编译数组定义.  它的工作原理更多
  比NumPy更基本的水平，通过提供更强大的功能
  N维数组，但只是一些工作的构建块
   他们.  [AGPL] [89].
* [cmu-infix](https://github.com/rigetti/cmu-infix) - 用于在Common Lisp中编写中缀数学符号的库.
* [cl-ana](https://github.com/ghollisjr/cl-ana)   -  Common Lisp数据分析库，强调模块化和概念清晰度.  它旨在成为分析小规模和大规模数据集的通用框架，包括分档数据分析和可视化.  [GNU GPL3] [2].


并行和并发
===========================

*：明星： [BordeauxThreads](https://common-lisp.net/project/bordeaux-threads/)   - 可移植的共享状态并发.  [外籍] [14].
*：明星： [lparallel](https://github.com/lmj/lparallel) - A library for parallel programming. [3-clause BSD][15].
* [lfarm](https://github.com/lmj/lfarm)   - 跨机器分配工作（在lparallel和usocket之上）.  [BSD_3Clause] [15]
* [chanl](https://github.com/zkat/chanl)   - 便携式，基于通道的并发性.  [Expat] [14]，部分在[3条款BSD] [15]下.
* [cl-async](https://github.com/orthecreedence/cl-async)   - 用于通用非阻塞编程的库.  [外籍] [14].
* [erlangen](https://github.com/eugeneia/erlangen)   -  Clozure Common Lisp的分布式异步消息传递系统.  [GNU GPL3] [2].  另见 [Actors](https://github.com/aarvid/Actors) LispWorks包（[discussion](https://www.reddit.com/r/Common_Lisp/comments/77vsft/david_mcclains_actors_package_for_lispworks/)）[麻省理工学院] [200].
* [Moira](https://github.com/TBRSS/moira)   - 监视并重新启动后台线程.  In-lisp流程主管.  未指定许可证.
* [trivial-monitored-thread](https://gitlab.com/ediethelm/trivial-monitored-thread) -
  一个Common Lisp库提供了一种产生线程和存在的方法
   当他们中的任何一个崩溃并死亡时通知  [MIT] [200].
* [cl-gearman](https://github.com/taksatou/cl-gearman) - 一个图书馆 [Gearman](http://gearman.org/)  分布式工作系统.  [LLGPL] [8].


事件处理
----------------

* [simple-tasks](https://github.com/Shinmera/simple-tasks) - 一个非常
   简单的任务调度框架.  [艺术许可2.0] [51].
* [deeds](https://github.com/Shinmera/deeds) - 契约是可扩展
   事件传递系统.  它允许有效的事件传递到
  具有复杂事件过滤的多个处理程序
   系统.  [艺术许可2.0] [51].
* [cl-flow](https://github.com/borodust/cl-flow/)   - 用于非阻塞并发Common Lisp的数据流计算树库.  [MIT] [200].
* [event-glue](https://github.com/orthecreedence/event-glue)   - 简单的事件抽象.  没有依赖.  它可以在任何需要通用事件处理系统的地方使用.  [MIT] [200].


工作处理
--------------

* [psychiq](https://github.com/fukamachi/psychiq)   -  Common Lisp应用程序的基于redis的后台作业处理.  灵感来自Ruby的Sidekiq并与其Web UI兼容.  [LLGPL] [8].
* [clerk](https://github.com/tsikov/clerk)   - 具有理智DSL的类似cron的调度程序.  [MIT] [200].

Regex
=====

*：明星： [cl-ppcre](http://weitz.de/cl-ppcre/)   - 便携式，Perl兼容的正则表达式.  [FreeBSD的] [39].


Scripting
=========

*  [Roswell](https://github.com/roswell/roswell#scripting-with-roswell) -
  一个lisp安装程序和脚本环境（帮助程序，启动程序，
   安装程序）等等.  [MIT] [200].
* [Shelly](https://github.com/fukamachi/shelly) - 执行Common Lisp
  函数类似于shell命令，无需编写命令
   行参数解析器.  它也可以用作Make-like
   构建工具.  [FreeBSD的] [39].
* [cl-readline](https://github.com/vindarel/cl-readline) - 一套
  用于在输入行时编辑行，以维护列表
  以前输入的命令行，用于调用和重新编辑它们
   执行类似csh的历史扩展.  Emacs和vi编辑
   模式.  [GPL3] [2].
*  [Unix-opts](https://github.com/mrkkrp/unix-opts) - 命令行
   选项解析器，带有简洁的选项声明.  [MIT] [200].
* [CLON](https://github.com/didierverna/clon) - 命令行选项
  Nuker. [ISC](https://github.com/didierverna/clon/blob/master/LICENSE).
* [cl-ansi-term](https://github.com/vindarel/cl-ansi-term) - 打印
  彩色文本，水平线，进度条，（un）有序列表
   和符合ANSI标准的终端上的表格.  [GPL3] [2].
* [cl-charms](https://github.com/HiTECNOLOGYs/cl-charms) - 一个
   Common Lisp中的`libcurses`接口.  它既提供原料，
  通过CFFI向libcurses的低级接口，以及更高级别的接口
   lispier接口.  [带] [200].
* [shcl](https://github.com/bradleyjensen/shcl)   -  Common Lisp中类似POSIX的shell.  [Apache2.0的] [51].
* [cl-progress-bar](https://github.com/sirherrbatka/cl-progress-bar/)   - 进度条，就像在Quicklisp中一样！  [MIT] [200].
* [WCL](https://github.com/wadehennessey/wcl) - 允许数百个Lisp
应用程序可以立即实现，同时允许
 其中几个同时运行.  WCL完成了这个
提供Common Lisp作为可以链接的Unix共享库
 Lisp和C代码可以生成高效的应用程序.  例如，
可执行的规范“Hello World！”的Lisp版本
 程序在32位x86 Linux上只需要20k字节.  WCL也
支持完整的开发环境，包括动态文件
 加载和调试.  GDB的修改版本用于调试WCL
 程序，为混合语言调试提供支持.  同
[a paper](http://pgc.com/commonlisp/wcl-paper.html).
* [replic](https://github.com/vindarel/replic/)   - 帮助者将现有代码转换为readline应用程序，重点是定义命令参数的完成.  也是一个随时可用的可执行文件，它将用户的lispy init文件转换为readline命令.  [MIT] [200].
* [cl-all](https://github.com/shinmera/cl-all)   - 在多个实现中运行Lisp代码段的脚本.  这使您可以快速比较实现行为和差异.  [艺术许可2.0] [51].

文本编辑器资源
=====================

这包含各种文本编辑器的插件和其他好东西.

* [Parinfer](https://shaunlebron.github.io/parinfer/)   -  Parinfer是一种编辑lisp代码的方法，有助于保持缩进和括号平衡.  它很容易入手，但它提供了先进的Paredit功能.  它可以在许多编辑器上使用（Emacs，Vim，Neovim，Atom，Sublime Text，Visual Studio Code，LightTable，CodeMirror，......）.

## Emacs ##

*：明星： [Slime](https://github.com/slime/slime)   -  Emacs的高级Lisp交互模式;  Emacs内部Common Lisp的完整环境.  公共区域.
*  [Sly](https://github.com/joaotavora/sly) -  SLY是SLIME的一个分支，并包含多项改进.
*  [Portacle](https://shinmera.github.io/portacle/) - 便携式多平台Common Lisp环境：SBCL，Quicklisp，Emacs，Slime，Git.
* [cl-devel2](https://hub.docker.com/r/eshamster/cl-devel2/)   -  Common Lisp开发环境的Docker容器.  使用Slime运送SBCL，CCL，Roswell和Emacs25.

## Vim & Neovim ##

* [SLIMV](https://github.com/kovisoft/slimv)   -  Vim的高级Lisp交互模式;  Vim中Common Lisp的完整环境.  未指定许可证.
* [Vlime](https://github.com/l04m33/vlime)   -  VLIME：Vim加上Lisp是最邪恶的.  Vim（和Neovim）的Common Lisp开发环境.  [MIT] [200].
* [quicklisp.nvim](https://gitlab.com/HiPhish/quicklisp.nvim) -  Neovim的Quicklisp前端.
* [Slimv_box](https://github.com/justin2004/slimv_box) - 在Docker容器中使用slimv.


## Eclipse ##

* [Dandelion](https://github.com/Ragnaroek/dandelion) -  Eclipse IDE的Common Lisp插件.

## Lem ##

* [Lem](https://github.com/cxxxr/lem) - 即时可用，类似Emacs，基于Slime
   为Common Lisp开发量身定制的编辑器.  Ncurses和Electron接口.  [MIT] [200].  一个 [opengl frontend](https://github.com/pupcraft/lem-opengl).

## Atom ##

* [SLIMA](https://github.com/neil-lindquist/slima) allows you to
  交互式开发Common Lisp代码，将Atom变成了一个
   相当不错，积极开发Lisp IDE.  [MIT] [200].

## Sublime Text ##

* [Sublime Text](http://www.sublimetext.com/3) 有Common Lisp支持
   使用“SublimeREPL”包.  [所有权].
  
## VSCode ##

* [VSCode-lisp](https://marketplace.visualstudio.com/items?itemName=mattn.Lisp)  扩展以支持Lisp语法.  它是 [on the GitHub](https://github.com/mattn/vscode-lisp).

## Notebooks ##

* [cl-jupyter](https://github.com/fredokun/cl-jupyter) -  Jupyter笔记本的Common Lisp内核 [custom licence](https://github.com/fredokun/cl-jupyter/blob/master/LICENSE).
* [common-lisp-jupyter](https://github.com/yitzchak/common-lisp-jupyter)   -  Jupyter的Common Lisp内核以及用于构建Jupyter内核的库，基于Robert Dodier的Maxima-Jupyter，它基于Frederic Peschanski的cl-jupyter.  [MIT] [200].
* [Darkmatter](https://github.com/tamamu/darkmatter) - 一个
   笔记本式的Common Lisp环境.  [MIT] [200].

## REPLs ##

* [cl-repl](https://github.com/koji-kojiro/cl-repl)   - 类似ipython的REPL.  完成后，shell命令，魔术命令，调试器等[MIT] [200].  同 [colorthemes](https://github.com/koji-kojiro/lem-pygments-colorthemes).

文字处理
===============

* [montezuma](https://github.com/sharplispers/montezuma/)   - 全文索引和搜索Common Lisp.  [外籍] [14].
* [mk-string-metrics](https://github.com/cbaggers/mk-string-metrics) -
  在Common Lisp中有效地计算各种字符串度量
  （Damerau-Levenshtein，Hamming，Jaro，Jaro-Winkler，Levenshtein，
   等）.  [带] [200].
* [cl-yacc](https://github.com/jech/cl-yacc)   -  LALR（1）解析器生成器.  [带] [200].
* [wiki-lang-detect](https://github.com/vseloved/wiki-lang-detect) -
 使用维基百科数据识别文本语言.  未指定许可证.

Tools
=====

这些是应用程序或代码，使Common Lisp中的开发更容易，而不是Common Lisp库本身.

 * [quickapp] [188]  - 使用SBCL和buildapp生成模板项目的项目.  还包括一个命令行argparser.  [3条款BSD] [15].
* [quickapp-cli](https://github.com/triclops200/quickapp-cli)   -  [quickapp] [188]作为命令行实用程序.  [3条款BSD] [15].
* [quicksearch](https://github.com/tkych/quicksearch)   - 从REPL中查找在线库.  [外籍] [14].
* [SWIG](http://www.swig.org/)   - 用于从C / C ++头文件生成FFI代码的工具.  [GNU GPL3] [2].
* [cl-project](https://github.com/fukamachi/cl-project)   - 一般现代项目骨架.  [LLGPL] [8].
* [lake](https://github.com/takagi/lake)   - 像构建实用程序一样的GNU make.  [MIT] [200].


单元测试
============

*：明星： [FiveAM](https://github.com/sionescu/fiveam)   - 简单的回归测试框架.  [FreeBSD的] [39].
* [CLUnit](https://github.com/tgutu/clunit)   - 单元测试库.  [外籍] [14].
* [Rove](https://github.com/fukamachi/rove)   -  Rove是Common Lisp应用程序的单元测试框架.  它的目的是成为继承者 [Prove](https://github.com/fukamachi/prove) .  [3条款BSD] [15].
* [Parachute](https://github.com/Shinmera/parachute) - 可扩展
   和交叉兼容的测试框架.  有了测试依赖性，
   条件，固定装置和重启.  [艺术许可2.0] [51].
* [Mockingbird](https://github.com/Chream/mockingbird) - 一个小
   Common Lisp的存根和模拟库.  也可以检查一下
  a stubbed function was called, how many times and with which
   参数.  [带] [200].
* [Check-it](https://github.com/DalekBaldwin/check-it)   - 基于QuickCheck的随机属性测试.  [LLGPL] [8].
* [cl-coveralls](https://github.com/fukamachi/cl-coveralls) - 帮助者
   库将测试覆盖率发布到Coveralls.  看到
  [continuous-integration on lisp-lang.org](http://lisp-lang.org/learn/continuous-integration)
  和
  [SBCL's code coverage tool](http://www.sbcl.org/manual/index.html#sb_002dcover) .  [FreeBSD的] [39].


Utilities
=========

Caching
-------

* [clache](https://github.com/html/clache)   - 一般缓存设施.  未指定许可证.


Configuration
-------------

*  [py-configparser](https://common-lisp.net/project/py-configparser/)   - 读取和编写Python的类似ConfigParser的配置文件.  [MIT] [200].
* [envy](https://github.com/fukamachi/envy)   - 配置切换器.  [FreeBSD的] [39].

CSV
---

*：明星： [cl-csv](https://github.com/AccelerationNet/cl-csv)   - 用于解析CSV文件的库.  [3条款BSD] [15].
* [cl-decimals](https://github.com/tlikonen/cl-decimals)   - 十进制数解析器和格式化程序.  公共区域.
* [auto-text](https://github.com/defunkydrummer/auto-text)   - 自动（编码，行尾，列宽，csv定界符等）检测文本文件.  [MIT] [200].  也可以看看 [inquisitor](https://github.com/t-sin/inquisitor) 用于检测亚洲和远东语言.


日期和时间
-------------

* [localtime](https://common-lisp.net/project/local-time/)   - 用于以半标准方式操纵日期和时间信息的开发库.  [3条款BSD] [15].
* [cl-date-time-parser](https://github.com/tkych/cl-date-time-parser)   - 自由地解析日期时间字符串.  隐藏日期时间格式之间的差异，并允许将日期和时间作为一种日期时间格式进行管理.  [MIT] [200].
* [chronicity](https://github.com/chaitanyagupta/chronicity)   - 自然语言日期和时间解析，用于解析“从现在开始3天”等字符串.  [BSD_3Clause] [15].
* [local-time-duration](https://github.com/enaeher/local-time-duration) -
 持续时间处理库建立在本地时间之上.  [MIT] [200].
* [iso-8601-date](https://gitlab.com/DataLinkDroid/iso-8601-date)   -  Common Lisp中的其他日期例程，基于ISO 8601字符串表示.  [LLGPL] [8].

数据验证
---------------

* [ratify](https://github.com/Shinmera/ratify)   - 用于批准，验证和解析输入的实用程序集合.  [艺术许可2.0] [51].
* [clavier](https://github.com/mmontone/clavier)   -  Common Lisp的通用验证库.  [MIT] [200].

文档构建者
----------------------

* [sphinxcontrib-cldomain](https://github.com/russell/sphinxcontrib-cldomain) -
   扩展Sphinx以涵盖Common Lisp.  使用构建文档
   Python项目与sphinx一样容易.  [GPL3] [2]
* [Codex](https://github.com/CommonDoc/codex) - 一个美丽
   Common Lisp的文档系统.  [MIT] [200].
* [Staple](https://github.com/Shinmera/staple) - 生成的工具
   使用HTML模板的文档页面.  使用现有
  自述文件，添加了文档字符串，交叉引用和链接
   CLHS.  [ArtisticLicense2.0] [51].
* [cl-bibtex](https://github.com/mkoeppe/cl-bibtex)   - 使用BST-to-CL编译器在Common Lisp中兼容重新实现BibTeX程序.  [GNU LGPL2.1] [11].


文件和目录
---------------------

*：明星： [uiop](http://quickdocs.org/uiop/) 和它的`pathname`包
  （取代 [cl-fad](http://weitz.de/cl-fad/) ）.  uiop是ASDF3的一部分
   并且因此在许多实施方式中被运送.  [MIT] [200].
* [osicat](https://common-lisp.net/project/osicat/) - 类似POSIX的系统上的轻量级操作系统接口（目录迭代和删除，环境变量，文件权限等）[Expat] [14].
* [pathname-utils](https://github.com/Shinmera/pathname-utils) - 一个
  用于帮助路径名的实用程序集合
   操作.  [艺术许可2.0] [51].
* [archive](https://github.com/froydnj/archive)   - 用于读取和创建存档（tar，cpio）文件的库.  [BSD_3Clause] [15].  纯&#39;Common Lisp替代&#39;tar&#39;程序.

Git
---

* [legit](https://shinmera.github.io/legit/) -  Git的接口
   二进制文件.  [艺术许可2.0] [51].

i18n
----

* [cl-i18n](https://notabug.org/cage/cl-i18n)   - 一个i18n库.  从GNU gettext文本或二进制文件或其本机格式加载转换.  复数形式的本地化助手.  [LLGPL] [8].
* [cl-locale](https://github.com/fukamachi/cl-locale)   - 一个简单的i18n库.  [LLGPL] [8].
* [enchant](https://github.com/tlikonen/cl-enchant)   - 附魔拼写检查库的绑定.  公共区域.
* [oxenfurt](https://github.com/Shinmera/oxenfurt)   - 牛津词典API的客户端库.  [ArtisticLicense2.0] [51].
* [language-codes](https://shinmera.github.io/language-codes)   -  ISO语言代码的数据库库.  [艺术许可证2.0] [51]
* [system-locale](https://shinmera.github.io/system-locale)   - 用于检索用户首选语言的库，以便您的应用程序可以选择合理的默认值.  [艺术许可2.0] [51].
* [multilang-documentation](https://shinmera.github.io/multilang-documentation)   - 允许以多种语言编写文档字符串，用于真正的国际文档库.  [艺术许可2.0] [51].

Linting
-------

* [sblint](https://github.com/fukamachi/sblint) -  Common的一个短片
  使用SBCL的Lisp源代码，适用于Reviewdog（[slides](http://www.slideshare.net/fukamachi/sblint) ）.  [BSD_2Clause] [17].


Logging
-------

*：明星： [log4cl](https://github.com/sharplispers/log4cl/)   -  Log4J之后的Logging框架模型.  [Apache2.0的] [89].  与Slime高级集成.
* [verbose](https://shinmera.github.io/verbose)   - 快速且高度可配置的日志框架.  [艺术许可2.0] [51].

致第三方：

* [cl-fluent-logger](https://github.com/fukamachi/cl-fluent-logger) - 一个Common Lisp结构化记录器 [Fluentd](https://www.fluentd.org/).


Markdown
--------

* [3bmd](https://github.com/3b/3bmd)   - 降价 - &gt; HTML转换器.  [MY] [200].

PDF
---

* [cl-typesetting](https://github.com/mbattyani/cl-typesetting) 和 [cl-pdf](https://github.com/mbattyani/cl-pdf)   - 用于生成PDF文件的跨平台Common Lisp库.  [FreeBSD的] [39].
* [cl-pslib](http://quickdocs.org/cl-pslib/) - 围绕着一个（薄）包装纸 [pslib](http://pslib.sourceforge.net/)  用于生成PostScript文件的库.  也 [cl-pslib-barcode](http://quickdocs.org/cl-pslib-barcode/) .  [LLGPL] [8].

Plotting
--------

* [vgplot](https://github.com/volkers/vgplot) - 一个接口
  gnuplot绘图实用程序，意图类似于某些
   octave或matlab的绘图命令.  [GPL3] [2].
* [eazy-gnuplot](https://github.com/guicho271828/eazy-gnuplot) - 一个
   lispy，无结构的Gnuplot库.  随着它
  [cookbook](http://guicho271828.github.io/eazy-gnuplot/) .  [LLPPL] [8]


Other
-----

这包含任何不适合其他类别的内容.

* [babel](https://github.com/cl-babel/babel)   - 字符集编码/解码库.  [外籍] [14].
* [chipz](https://github.com/froydnj/chipz) - A decompression library. [3-clause BSD][15].
* [cl-cuda](https://github.com/takagi/cl-cuda)   - 在Common Lisp程序中使用NVIDIA CUDA的库.  [LLGPL] [8].
* [corona](https://github.com/eudoxia0/corona) - 从Common Lisp http://eudoxia.me/corona [MIT] [200]创建和管理虚拟机.
*：明星： [esrap](https://github.com/scymtym/esrap)   -  Packrat解析器.  [外籍] [14].
* [fast-io](https://github.com/rpav/fast-io)   - 快速八位字节矢量/流I / O.  [3条款BSD] [15].
* [glyphs](https://github.com/ahungry/glyphs/)   - 一个用于在某些地方减少Common Lisp冗长的库.  [GNU GPL3] [2].
* [iolib](https://github.com/sionescu/iolib)   -  I / O库.  [外籍] [14].
* [mixalot](https://github.com/ahefner/mixalot)   - 松散耦合的音频库集合.  未指定许可证.
* [named-readtables](https://github.com/melisgl/named-readtables)   - 提供可读命名空间，类似于包命名空间.  [3条款BSD] [15].
* [nEXT-Browser](http://github.com/nEXT-Browser/nEXT)   - 以生产力为重点，可扩展/可编程的Web浏览器.  [3条款BSD] [15].
* [Salza2](http://www.xach.com/lisp/salza2/)   - 用于创建压缩数据的库.  [FreeBSD的] [39].
* [simple-currency](https://github.com/a0-prw/simple-currency)   - 使用欧洲央行公布的每日信息的货币转换库.  [FreeBSD的] [39].
* [template](https://bitbucket.org/tarballs_are_good/template)   - 模板和函数库，类似于C ++.  [3条款BSD] [15].
* [texp](http://mr.gy/software/texp/)   - 用于生成TeX的DSL.  未指定许可证.
* [trivial-benchmark](https://github.com/Shinmera/trivial-benchmark)   - 微小的基准测试库.  [艺术许可2.0] [51].
* [trivial-garbage](https://github.com/trivial-garbage/trivial-garbage)   - 便携式终结器，弱哈希表和弱指针API.  公共区域.
* [trivial-utf8](https://common-lisp.net/project/trivial-utf-8/)   - 用于执行基于UTF-8的I / O的小型库.  在Quicklisp上不可用.  未指定许可证.


XML
===

* [CXML](https://common-lisp.net/project/cxml/)   -  XML解析器，具有一系列扩展库.  [LLGPL] [8].
 * [丰满] [71]  - 宽松的XML解析器.  [艺术许可2.0] [51].
* [xpath](https://github.com/sharplispers/xpath) ([homepage](https://common-lisp.net/project/plexippus-xpath/atdoc/index.html)   -  XML路径语言（XPath）版本1.0的实现.  [BSD_2Clause] [17].
* [s-xml](http://cliki.net/S-XML)   - 一个基本的解析器.  [LLGPL] [8].
* [xmls](http://quickdocs.org/xmls/)   - 一个小而简单，无需验证的XML解析器.  [3条款BSD] [15].
* [cl-feedparser](https://github.com/TBRSS/cl-feedparser)   -  Common Lisp（RSS，Atom）提要解析器.  [LLGPL] [8]


Contributing
============
 欢迎您的贡献！  请提交拉取请求或创建
向列表中添加新框架，库或软件的问题.

我们（试图）遵守的规则如下：

- 默认情况下，将库添加到其部分的末尾.
- 绝对事实上的图书馆，如BordeauxThreads或Quicklisp，
  应该用：star：（`：：star：`in markdown）表示.
- 两个范围非常相似的图书馆应该是并排的，或者是一个
  他们自己的部分.
- 根据我们的经验和状态做一些策展
   图书馆的文件.  我们*不*目标列出每个现有
  CL库（请参阅Quickdocs或Cliki），也不列出每一个
  “流行”图书馆（参见Quicklisp统计数据）.
- 因此，我们最喜欢的库标有（`1F44D`
   unicode字符）.  另见标志中的解释
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
[14]: http://directory.fsf.org/wiki/License:Expat
[15]: http://directory.fsf.org/wiki/License:BSD_3Clause
[16]: https://www.quicklisp.org/beta/
[17]: https://directory.fsf.org/wiki/License:BSD_2Clause
[20]: http://www.cs.northwestern.edu/academics/courses/325/readings/graham/graham-notes.html
[21]: http://www.goodreads.com/book/show/1175730.Object_Oriented_Programming_in_Common_LISP
[33]: http://directory.fsf.org/wiki/License:Zlib
[39]: http://directory.fsf.org/wiki?title=License:FreeBSD
[47]: http://directory.fsf.org/wiki/License:CPLv1.0
[51]: http://directory.fsf.org/wiki/License:ArtisticLicense2.0
[54]: http://directory.fsf.org/wiki/License:Boost1.0
[59]: http://directory.fsf.org/wiki/License:EPLv1.0
[71]: https://github.com/Shinmera/plump
[72]: https://github.com/Shinmera/lquery
[89]: http://directory.fsf.org/wiki/License:Apache2.0
[156]: http://letoverlambda.com/
[157]: http://norvig.com/paip.html
[176]: https://github.com/gwkkwg/lift/blob/master/COPYING
[188]: https://github.com/triclops200/quickapp
[200]: https://opensource.org/licenses/MIT
[201]: https://github.com/google/lisp-koans
[205]: https://www.postgresql.org/about/licence/
[206]: http://www.gigamonkeys.com/book/
[207]: https://opensource.org/licenses/bsd-license.php
[208]:https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[209]: http://www.eclipse.org/legal/epl-v10.html
