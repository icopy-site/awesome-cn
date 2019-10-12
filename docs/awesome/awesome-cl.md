<div class="github-widget" data-repo="CodyReichert/awesome-cl"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">
  <a href="https://awesome-cl.com" target="_blank">
    <img src="https://i.imgur.com/jLVXhpc.png">
  </a>
</div>

## Awesome Common Lisp [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Assertible status](https://assertible.com/apis/102e334d-f9a8-4565-9353-7572de775cae/status?api_token=8b55a286830323effb)](https://assertible.com/docs/guide/deployments)

_awesome_ Common Lisp库的精选列表.

有关出色的*软件*，请参见 [lisp-lang.org's success stories](http://lisp-lang.org/success/) 和 [awesome-cl-software](https://github.com/azzamsa/awesome-cl-software) 清单.

除非[Quicklisp] [16]可以使用此处列出的所有库，除非
 另有说明.  带有：star：的标记是如此广泛且
 坚信他们成为社区标准.  你不会错
 他们.  Quicklisp，BordeauxThreads和
 这样.  标有a的库是我们喜欢并想要
 在Awesome-cl列表中进行推广.  他们证明是可靠的，他们可能会解决
比社区标准更好的问题，但他们没有
 普遍存在，或不被认为是稳定的.  例如，我们更喜欢
Cl-Who上的喷丝板.

 添加新的东西！  见 [contributing](#contributing) 部分添加到
list.

它是根据GNU Free Documentation License发布的-其文本
 在LICENSE文件中提供.  该存储库也已镜像到
[NotABug](https://notabug.org/CodyReichert/awesome-cl) -完全免费**（如随意）
 替代Github.  优先考虑[免费软件] [13]和
对物质资源并不有害的卖方.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->


<!-- markdown-toc end -->


Audio
=====

* [Open Music](https://github.com/openmusic-project/OM6)  -可视化程序，计算机辅助合成环境.  [GPL3] [2].
* [OM7](https://github.com/openmusic-project/om7)  -OpenMusic可视化编程和计算机辅助合成环境的新实现，包括图形界面，计算模式以及与外部软件库的连接方面的许多改进.  [GPL3] [2].
* [Incudine](http://incudine.sourceforge.net/)  -Common Lisp的音乐/ DSP编程环境.  从零开始设计软件合成器或声音插件很有用.  它也是一种合成工具，可以在样本级别上产生可控制的高质量声音，实时定义和重新定义数字信号处理器和音乐结构.
* [cl-collider](https://github.com/byulparan/cl-collider) - 一种
[SuperCollider](http://supercollider.github.io/)  CommonLisp的客户端.  用 [tutorial](https://github.com/defaultxr/cl-collider-tutorial) 和 [live coding demos](https://www.youtube.com/watch?v=xzTH_ZqaFKI) .  公共区域.
* [csound](https://github.com/csound/csound)  -声音和音乐计算系统.  包括用于Common Lisp的CFFI和FFI接口.
* [CLM](https://ccrma.stanford.edu/software/clm/)  -Common Lisp Music是Music V系列中的音乐合成和信号处理软件包.  它提供与Stk，Csound，SuperCollider，PD，CMix，cmusic和Arctic几乎相同的功能-一组创建和操纵声音的功能，主要针对作曲家（无论如何，对于CLM而言）.
* [cl-patterns](https://github.com/defaultxr/cl-patterns)  -一种通过Lisp代码进行音乐创作的系统，该系统受到SuperCollider的模式系统的极大启发，旨在实现其中的大部分功能，但以一种更健壮，富有表现力，一致，反射性和脆弱的方式实现.  通过SuperCollider进行音频输出，初步支持Incudine，通过ALSA进行MIDI.
* [cl-openal](https://github.com/zkat/cl-openal)  -用于OpenAL音频库的绑定.  公共区域.
* [Common Music](https://github.com/ormf/cm) -一个的存储库
古老版本的通用音乐（2.12.0版），大概是最后一个
该版本在2007-09年左右的Common Lisp上运行，之前
普通音乐的工作转移到（基于方案）cm3.
* [cm-incudine](https://github.com/ormf/cm-incudine)  -扩展具有实时功能的Common Music 2.  GPL2.
* [Mégra](https://github.com/the-drunk-coder/megra)  -用变序马尔可夫链和其他一些随机的恶作剧制作音乐的迷你语言.  [GPL3] [2].
* [Music](https://github.com/MegaLoler/Music) -Lisp中的音乐表达框架，着重于音乐理论（从零开始，与通用音乐无关）.
* [rq](https://github.com/openmusic-project/RQ) -OpenMusic（版本6.10及更高版本）中节奏转录的库. [demo video](https://www.youtube.com/watch?v=XVEllB0TtVs) .  [GPL3] [2].
* [scheduler](https://github.com/byulparan/scheduler)  -Common Lisp的基于时间的音乐事件调度程序.  [Apache2.0] [51].
* [mixalot](https://github.com/ahefner/mixalot)  -mp3，ogg vorbis和flac的音频库的松耦合集合.  用于 [Shuffletron music player](https://github.com/ahefner/shuffletron).
* [osc](https://github.com/zzkt/osc)  -开放声音协议的实现.  [LGPL2.1] [11].
* [Harmony](https://shirakumo.github.io/harmony)  -实时声音处理和播放系统.  [Artistic License 2.0] [51].


构建系统
=============

*：星级： [ASDF](https://common-lisp.net/project/asdf/)  -另一个系统定义工具；  Common Lisp的构建系统.  [Expat] [14].
* [asdf-linguist](https://github.com/eudoxia0/asdf-linguist)  -ASDF的扩展.  [Expat] [14].
* [asdf-viz](https://github.com/guicho271828/asdf-viz)  -可视化ASDF系统的库依赖性，函数的调用图和类继承的工具.  [LLGPL] [8].

编译器，代码生成器
==========================

C，C ++
------

* [cmacro](https://github.com/eudoxia0/cmacro) -C. [MIT] [200]的Lisp宏.
* [C-mera](https://github.com/kiselgra/c-mera)  -源到源的编译器，利用Lisp的宏系统对类似C的语言进行元编程.  [GPL3] [2].
* [lispc](https://github.com/eratosthenesia/lispc) -用于C. [MIT] [200]的强大的“ lispsy”宏语言.
* [ecrepl](https://gitlab.common-lisp.net/ecl/ecrepl)  -用于C语言的交互式REPL.  未指定许可证.


Crypto
======

*：星级： [Ironclad](https://github.com/sharplispers/ironclad)  -Common Lisp的加密函数库.  不被认为是安全的，但是对于消息摘要功能仍然有用.  [Expat] [14].
* [crypto-shortcuts](https://github.com/Shinmera/crypto-shortcuts)  -常见的加密快捷方式的集合.  [Artistic License 2.0] [51].
* [trivial-ssh](https://github.com/eudoxia0/trivial-ssh)  -SSH客户端库.  [Expat] [14].

Cryptocurrencies
================

* [cl-monero-tools](https://github.com/glv2/cl-monero-tools)  -Common Lisp工具箱，可与Monero加密货币一起使用.  [GPL3] [2].  不在Quicklisp中.
* [emotiq](https://github.com/emotiq/emotiq)  -下一代区块链，采用创新的自然语言方法处理智能合约.  [MIT] [200].
* [peercoin-blockchain-parser](https://github.com/glv2/peercoin-blockchain-parser)  -解析文件中包含的区块链并将其某些数据导出到文本文件，SQL脚本或数据库.  它还可以使用Peercoin守护程序的RPC作为数据源而不是区块链文件来创建数据库.  LGPL3.  不在Quicklisp中.
* [peercoin-calculator](https://github.com/glv2/peercoin-calculator) - This program gives you the probability of generating a POS or POW block within 10 minutes, 24 hours, 31 days, 90 days and 1 year, as well as the reward that can be expected. GUI in Qt. [GPL3][2]. Not in Quicklisp.
* [peercoin-vote](https://github.com/glv2/peercoin-vote)  -基于来自区块链的数据（地址和余额）的投票系统.  [GPL3] [2].  不在Quicklisp中.

Database
========

ORMs
----

*：星级： [clsql](http://www.cliki.net/CLSQL)  -具有Common Lisp接口的SQL数据库.  [LLGPL] [8].
*  [mito](https://github.com/fukamachi/mito) -带有迁移，关系和PostgreSQL支持[LLGPL] [8]的Common Lisp的ORM. [mitho-auth](https://github.com/fukamachi/mito-auth)，一个用于使用授权的mixin类； [mito-attachment](https://github.com/fukamachi/mito-attachment)，RDBMS外部用于文件管理的混合类.
* [cl-dbi](https://github.com/fukamachi/cl-dbi)  -Common Lisp的独立于数据库的接口.  [LLGPL] [8].
* [crane](https://github.com/eudoxia0/crane)  -另一个ORM.  [Expat] [14].
* [datafly](https://github.com/fukamachi/datafly)  -轻量级的数据库库.  [3子BSD] [15].
* [sxql](https://github.com/fukamachi/sxql)  -用于生成SQL的DSL.  [3子BSD] [15].

持久对象数据库
---------------------------

* [bknr.datastore](https://github.com/hanshuebner/bknr-datastore) -RAM中基于CLOS的仅Lisp数据库，具有事务日志记录持久性. [licence](http://bknr.net/html/license.html) .  （另请参见“常见的Lisp食谱”第21章）
* [ubiquitous](https://github.com/Shinmera/ubiquitous)  -提供易于使用的持久配置存储的库.  [Artistic License 2.0] [51].
* [cl-prevalence](https://common-lisp.net/project/cl-prevalence/)  -内存数据库系统.  对象流行性的实现，其中将业务对象保留在内存中，并记录交易记录以进行系统恢复. [github fork](https://github.com/40ants/cl-prevalence) .  [LLGPL] [8].

Wrappers
--------

*：星级： [postmodern](http://marijnhaverbeke.nl/postmodern/)  -与PostgreSQL交互的库.  [zlib] [33].
* [cl-sqlite](https://github.com/dmitryvk/cl-sqlite)  -SQLite的绑定.  公共区域.
* [cl-memcached](https://github.com/quasi/cl-memcached)  -与Memcached对象缓存系统的快速，线程安全的接口.  [Expat] [14].
* [cl-mongo](https://github.com/fons/cl-mongo)  -MongoDB客户端.  [Expat] [14].
* [cl-redis](https://github.com/vseloved/cl-redis)  -Redis客户端.  [外籍] [14].
* [cl-disque](https://github.com/CodyReichert/cl-disque)  -客户磁盘.  [3子BSD] [15].
* [cl-rethinkdb](https://github.com/orthecreedence/cl-rethinkdb)  -RethinkDB客户端.  [Expat] [14].
* [clouchdb](https://common-lisp.net/project/clouchdb/)  -用于与CouchDB交互的库.  [FreeBSD] [39].

给第三方
----------------

* [dyna](https://github.com/Rudolph-Miller/dyna)  -AWS DynamoDB ORM.  [MIT] [200].
* [cl-influxdb](https://github.com/mmaul/cl-influxdb/)  -时间序列数据库InfluxDB的接口.  [MIT] [200].

Tools
-----

* [pgloader](https://github.com/dimitri/pgloader) - a data loading tool for PostgreSQL. [PostgreSQL Licence][205].


Data Structures
===============

*  [FSet](http://quickdocs.org/fset/)  -功能性的，集合论的集合数据结构库.  [LLGPL] [8].
* [bst](https://github.com/glv2/bst)  -二进制搜索树.  [GPL3] [2].  不在Quicklisp中.
* [pileup](http://nikodemus.github.io/pileup/)  -Common Lisp的可移植，高性能和线程安全的二进制堆.  [MIT] [200].
* [sycamore](https://github.com/ndantam/sycamore)  -快速，纯功能的数据结构库.  [BSD_3Clause] [15].
* [genhash](https://github.com/pnathan/genhash)  –通过通用方法使用API​​实现哈希表.  公共区域.
* [cl-ctrie](https://github.com/danlentz/cl-ctrie) -
 无锁，并发，键/值索引，具有高效的内存映射持久性和快速瞬态存储模型.  [MIT] [200].
* [cl-data-structures](https://github.com/sirherrbatka/cl-data-structures)  -数据结构和算法（主要是字典和序列，具有某些统计功能）的可移植集合.  [BSD] [15].

并查看更多 [Quickdocs](http://quickdocs.org/search?q=data+structure).


外功能接口
==========================

## C ##

*：星级： [CFFI](https://github.com/cffi/cffi)  -便携式，易于使用的C外部功能界面.  [Expat] [14].
* [cl-autowrap](https://github.com/rpav/cl-autowrap)  -自动将头文件解析为CFFI定义.  [FreeBSD] [39].
* [cl-gobject-introspection](https://github.com/andy128k/cl-gobject-introspection) - [Gobject Introspection](https://gi.readthedocs.io/en/latest/)  FFI.  自动绑定以调用C库.  [BSD] [15].

## Java ##

* [cl+j](https://common-lisp.net/project/cl-plus-j/)  -通过CFFI与JVM的基于JNI的接口.  在Quicklisp上不可用.  不能可靠地与所有实现一起使用.  [Expat] [14].

## Objective-C ##

* [objc-lisp-bridge](https://github.com/fiddlerwoaroof/objc-lisp-bridge)  -与Objective-C和Cocoa交互的便携式阅读器和桥接器.  [MIT] [200].

## Python ##

* [burgled-batteries](https://github.com/pinterface/burgled-batteries)  -Python和Common Lisp之间的桥梁.  目的是Lisp程序可以使用Python库.  在Quicklisp上不可用.  未指定许可证.
* [cl4py](https://github.com/marcoheisig/cl4py)  -库cl4py（读作clappy）允许Python程序调用Common Lisp库.  [MIT] [200].
* [py4cl](https://github.com/bendudson/py4cl)  -允许Common Lisp代码访问Python库的库.  它基本上是cl4py的反函数.  [MIT] [200].
* [cl-python](https://github.com/metawilm/cl-python)  -Common Lisp中Python的实现.  [LLGPL] [8].

也可以看看 [async-process](https://github.com/cxxxr/async-process/).

## .Net Core

* [Bike](https://github.com/Lovesan/bike)  -跨平台的.Net Core接口.  [MIT] [200].

## Miscellaneous ##

* [Foil](http://foil.sourceforge.net/)  -异物接口；  与JVM和CLI一起使用.  在Quicklisp上不可用.  [CPL 1.0] [47].


游戏开发
================

* [Xelf](http://xelf.me/)  -可扩展的游戏库.  在Quicklisp上不可用.  [GNU LGPL2.1] [11].
* [Trial](https://github.com/shirakumo/trial) -试用版是OpenGL
   专注于模块化的游戏引擎.  应该是
  提供大量有用的零散工具，您可以从中
   创建一个游戏.  [Artistic License 2.0] [47].
* [cl-mpg123](https://shirakumo.github.io/cl-mpg123) 和
  [cl-out123](https://shirakumo.github.io/cl-out123)，绑定
  分别用于libmpg123和libout123的库
  易于使用的mp3解码和跨平台音频
   输出.  [Artistic License 2.0] [47].
* [trivial-gamekit](https://borodust.org/projects/trivial-gamekit/getting-started/) –通过这种小型框架，您将能够制作简单的2D游戏：绘制基本的几何形式，图像和文本，播放声音以及收听鼠标和键盘输入.
* [cl-gamepad](https://shirakumo.github.io/cl-gamepad)  -在Windows，Mac OS和Linux上访问游戏手柄和操纵杆.  [Artistic License 2.0] [51].

Graphics
========

这些是用于处理图形的库，而不是用于制作具有自己部分的GUI（即小部件工具箱）的库.

*：星级： [Sketch](https://github.com/vydd/sketch)  -用于创建电子艺术，图形等的CL框架.  [MIT] [200].
* [common-cv](https://github.com/byulparan/common-cv)  -CommonLisp的OpenCV（开源计算机视觉库）绑定库.  未指定许可证.
* [cl-cairo2](https://github.com/rpav/cl-cairo2)  -开罗装订.  [提升1.0] [54]
* [cl-gd](http://weitz.de/cl-gd/)  -提供GD图形库接口的库.  [FreeBSD] [39].
* [cl-horde3d](https://github.com/anwyn/cl-horde3d/)  -将FFI绑定到Horde3D图形库.  在Quicklisp上不可用.  [EPL 1.0] [59]
* [cl-opengl](https://github.com/3b/cl-opengl)  -CFFI绑定到OpenGL，GLU和GLUT API.  [3子BSD] [15].
* [cl-sdl2](https://github.com/lispgames/cl-sdl2)  -使用C2FFI绑定SDL2.  [Expat] [14].
* [cl-svg](https://github.com/wmannis/cl-svg)  -用于生成SVG文件的基本库.  [Expat] [14].
* [CLinch](https://github.com/BradWBeer/CLinch)  -用于OpenGL的通用Lisp 2D / 3D图形引擎.  [FreeBSD] [39].
* [donuts](https://github.com/tkych/donuts)  -绘制Common Lisp的DSL图形.  [Expat] [14].
* [dufy](https://github.com/privet-kitty/dufy)  -在各种颜色模型中进行精确的颜色处理和转换.  [MIT] [200].
* [lispbuilder-sdl](https://github.com/lispbuilder/lispbuilder)  -一组SDL绑定.  [Expat] [14].
* [lisp-magick-wand](https://github.com/TBRSS/lisp-magick-wand)  -ImageMagick绑定.  [BSD] [15].  不在Quicklisp中.
* [okra](https://www.common-lisp.net/project/okra/manual.html)  -CFFI绑定到Ogre.  在Quicklisp上不可用.  [3子BSD] [15].
* [opticl](https://github.com/slyrus/opticl)  -用于表示和处理图像的库.  [BSD_2Clause] [17].
* [Varjo](https://github.com/cbaggers/varjo)  -Lisp到GLSL转换器.  [BSD_2Clause] [17].
* [Vecto](http://www.xach.com/lisp/vecto/)  -简单的矢量绘图库.  [FreeBSD] [39].
* [zpng](http://www.xach.com/lisp/zpng/)  -用于创建PNG文件的库.  [FreeBSD] [39].


GUI
===

*  [Qtools](https://github.com/Shinmera/qtools/)  -基于CommonQt的Qt工具包.  [Artistic License 2.0] [51]另外 [Qtools-ui](https://github.com/Shinmera/qtools-ui) （预制的UI组件）， [videos](https://www.youtube.com/watch?v=KwASFOhYta4&index=7&list=PLkDl6Irujx9Mh3BWdBmt4JtIrwYgihTWp).
*：星级： [CommonQt](https://github.com/commonqt/commonqt)  -通过QtSmoke为Qt4的Common Lisp绑定.  [FreeBSD] [39].
*：星级： [ltk](http://www.peter-herth.de/ltk/)  -Tk工具包的绑定.  [LLGPL] [8]或[GNU LGPL2.1] [11].
*：星级： [IUP](https://github.com/lispnik/iup/) -YFC绑定到 [IUP](https://www.tecgraf.puc-rio.br/iup/)  便携式用户界面库（ALPHA之前的版本）.  IUP是跨平台的（Windows，macOS，GNU / Linux），具有许多小部件，具有小的api，并且正在积极开发中.
* [nodgui](https://notabug.org/cage/nodgui)  -基于Ltk的Tk工具箱的绑定，带有语法糖和其他小部件.  [LLGPL] [8].
* [cl-cffi-gtk](http://www.crategus.com/books/cl-cffi-gtk/)  -绑定GTK + 3.  [GNU LGPL2.1] [11].
* [cl-gtk2](https://github.com/dmitryvk/cl-gtk2)  -绑定GTK + 2.  [LLGPL] [8].
* [ceramic](https://ceramic.github.io/)  -带有Electron的桌面Web应用程序.  [Expat] [14].
* [CocoaInterface](https://github.com/plkrueger/CocoaInterface/) -
 Clozure Common Lisp的可可界面.  构建可可用户界面
窗口动态使用Lisp代码并绕过典型的Xcode
 流程.  它有
[good documentation and a tutorial](https://github.com/plkrueger/CocoaInterface/blob/master/Documentation/UserInterfaceTutorial.pdf).
* [McCLIM](https://common-lisp.net/project/mcclim/)  -Common Lisp Interface Manager版本II的实现.  [GNU LGPL2.1] [11].
* [cl-webkit](https://github.com/joachifm/cl-webkit)  -绑定到WebKitGTK +.  还利用WebKit浏览引擎的全部功能为应用程序添加Web浏览功能.  [MIT] [200].
* [ftw](https://github.com/fjames86/ftw)  -Win32 GUI库.  [MIT] [200].
* [cl-xul](https://github.com/mmontone/cl-xul)  -Mozilla XUL绑定.  [Expat] [14].
* [eql, eql5, eql5-android](https://gitlab.com/eql)  -嵌入在ECL中的嵌入式Qt4和Qt5 Lisp，可嵌入Qt中.  EQL5到Android平台的端口.  [MIT] [200].
* [bodge-nuklear](https://github.com/borodust/bodge-nuklear) -包装在 [Nuklear](https://github.com/vurtun/nuklear)  立即模式GUI库.  [MIT] [200].


Implementations
===============

*：星级： [SBCL](http://www.sbcl.org/index.html)  -CMUCL的叉子；  编译为机器代码.  [符合标准] [13].  公共领域，[Expat] [14]和[3-clause BSD] [15]下的某些部分.
*：星级： [CCL](https://github.com/CodyReichert/awesome-cl/blob/master///ccl.clozure.com/)  -Clozure普通Lisp；  仅限编译器的实现，生成本机代码.  [LLGPL] [8].
* [ECL](https://common-lisp.net/project/ecl/)  -可嵌入的普通Lisp；  编译为C.[GNU LGPL2.1] [11].
* [ABCL](https://common-lisp.net/project/armedbear/)  -武装熊常见口齿不清；  针对JVM，编译为字节码.  [标准符合性] [4].  [GNU GPL3] [2]和[Classpath exception] [3].
* [CMUCL](https://github.com/CodyReichert/awesome-cl/blob/master///www.cons.org/cmucl/)  -卡内基梅隆大学实施.  公共区域.
* [GNU CLISP](http://www.clisp.org/)  -GNU实现；  包含一个编译器和一个解释器.  [标准符合性] [6].  [GNU GPL3] [2].
* [CLASP](https://github.com/drmeister/clasp)  -一种新的Common Lisp实现，可使用LLVM与C ++库和程序无缝地互操作，以编译为本机代码.  这使Clasp可以利用大量预先存在的库和程序，例如科学计算生态系统之外的库和程序.  [LGPL2.1] [11]（及其他）.
* [Corman Lisp](https://github.com/sharplispers/cormanlisp)  -在Intel平台上运行的Microsoft Windows通用Lisp开发环境.  [MIT] [200].

Proprietary:

* [LispWorks](http://www.lispworks.com/) -Common Lisp的集成的跨平台开发工具.
* [Allegro CL](https://franz.com/products/allegro-common-lisp/) -提供具有许多扩展功能的完整ANSI Common Lisp标准.
* [MOCL](https://wukix.com/mocl) - CL as a library for mobile devices (iOS & Android) and OSX.

JSON
====

* [cl-json](https://github.com/hankhero/cl-json)  -JSON编码器和解码器.  [Expat] [14].
* [jsown](https://github.com/madnificent/jsown)  -JSON格式的读取器和写入器.  [Expat] [14].
* [json-mop](https://github.com/gschjetne/json-mop)  -用于桥接CLOS和JSON对象的元类.  [MIT] [200].

另请参阅 [extensive comparison](https://sites.google.com/site/sabraonthehill/home/json-libraries) JSON库.

YAML
====

* [cl-yacclyaml](https://github.com/mabragor/cl-yaclyaml)  -纯Lisp YAML处理器（加载程序，但尚未转储）.  [GPL3] [2].
* [cl-yaml](https://github.com/eudoxia0/cl-yaml.git)  -建立在libyaml之上的YAML解析器和发射器.  [MIT] [200].


语言扩展
===================

* [cl21](https://github.com/cl21/cl21)  -将Common Lisp迁移到21世纪的实验项目.  [Expat] [14].
*：星级： [alexandria](https://common-lisp.net/project/alexandria/)  -通用实用程序库.  公共区域.
* [serapeum](https://github.com/TBRSS/serapeum/)  -另一个通用实用程序库.  [Expat] [14].
* [https://github.com/CodyReichert/awesome-cl/blob/master/rutils](https://github.com/CodyReichert/awesome-cl/blob/master/rutils)  -Common Lisp的基本但合理的语法实用程序.  [MIT] [200].
* [anaphora](https://common-lisp.net/project/anaphora/)  -照应宏的集合.  公共区域.
*：星级： [optima](https://github.com/m2ym/optima)  -优化的模式匹配库.  [LLGPL] [8].
* [str](https://github.com/vindarel/cl-str)  -一个现代，简单且一致的字符串操作库.  [MIT] [200].
* [interface](https://bitbucket.org/tarballs_are_good/interface)  -协议库.  [3子BSD] [15].
* [cl-syntax](https://github.com/m2ym/cl-syntax)  -阅读器语法约定.  [LLGPL] [8].
* [cl-2dsyntax](http://www.cliki.net/cl-2dsyntax)  -压痕敏感的阅读器系统.  在Quicklisp上不可用.  公共区域.
* [cl-annot](https://github.com/m2ym/cl-annot)  -Common Lisp的类似Python的注释.  [LLGPL] [8].
*：星级： [cl-interpol](http://www.cliki.net/cl-interpol)  -一组读取器修改，以允许字符串内插.  未指定许可证.
* [arrow-macros](https://github.com/hipeta/arrow-macros)  -类Clojure的线程宏.  [MIT] [200].
* [dissect](https://shinmera.github.io/dissect) -当很多
  项目使用“简单回溯”系统
  带回溯的字符串，Dissect允许您捕获，步进和
  完全检查各种Lisp上的堆栈跟踪
   实现.  对于日志记录和其他情况也非常有用
  自动继续执行，但以下信息
  当前堆栈对于存储仍然有用
   某处.  [Artistic License 2.0] [51].
* [clamp](https://github.com/malisper/Clamp)  -Arc语言对Common Lisp的简洁明了.  [Artistic License 2.0] [51].
* [trivial-arguments](https://github.com/Shinmera/trivial-arguments) -
   可移植库，用于检索函数的参数列表.  [Artistic License 2.0] [51].
* [modf](https://github.com/smithzvk/modf) -用于函数式编程的类似setf的宏.
* [generic-cl](https://github.com/alex-gutev/generic-cl/)  -到标准Common Lisp函数的通用函数接口（相等性，比较，算术，对象，迭代器，序列等）.  [MIT] [200].  另请参阅更轻量 [generic-comparability](https://github.com/pnathan/generic-comparability) .  [LLGPL] [8].
* [pythonic-string-reader](https://github.com/smithzvk/pythonic-string-reader)  -受Python的三个引号字符串的启发，对读取表进行了简单，轻松的修改.  [BSD_3Clause] [15].
*  [access](https://github.com/AccelerationNet/access/)  -对大多数常用数据结构的一致和嵌套访问.  [BSD_3Clause] [15].
* [listopia](https://github.com/Dimercel/listopia)  -受Haskell的Data.List启发的列表处理库.  [LLGPL] [8].


CLOS扩展
---------------

*：星级： [closer-mop](http://cliki.net/closer-mop)  -兼容性层，可纠正许多缺少或不正确的MOP功能.  [Expat] [14].
* [defclass-std](https://github.com/EuAndreh/defclass-std)  -用于快速编写DEFCLASS表单的快捷方式宏.  [LLGPL] [8].
* [specialization-store](https://github.com/markcox80/specialization-store/)  -基于类型的通用功能.  简化的BSD许可变体.
* [inlined-generic-function](https://github.com/guicho271828/inlined-generic-function) -
 将静态调度的速度带到CLOS.  [LLGPL] [8].
* [static-dispatch](https://github.com/alex-gutev/static-dispatch)  -允许静态（在编译时）而不是动态（运行时）执行标准通用函数分派.  这类似于在C ++和Java等语言中所谓的“重载”.  [MIT] [200].

功能扩展
-------------------

* [cl-hooks](https://github.com/scymtym/architecture.hooks/)  -Hooks扩展点机制（例如，从GNU Emacs中已知）.  LGPL.
* [method-hooks](https://gitlab.com/Gnuxie/method-hooks)  -如果CLOS方法组合每个方法只允许一个钩子，则此库允许任意数目的钩子.  Mozilla公共许可证.
* [cl-advice](https://bitbucket.org/budden/budden-tools/src/default/cl-advice/?at=default)  -SBCL，CCL，LispWorks和Allegro的可移植层建议库.  不在Quicklisp中.

Iteration
---------

*：星级： [iterate](https://common-lisp.net/project/iterate/)  -Common Lisp的可扩展和Lispier的迭代构造.  未指定许可证.
* [for](https://shinmera.github.io/for/) -简洁，灵活，可扩展
   迭代宏.  与循环不同，它是可扩展且明智的，并且
  与迭代不同，它不需要代码遍历并且更容易实现
   延伸.  [Artistic License 2.0] [51].
* [series](https://github.com/tokenrove/series/wiki)  -功能样式，完全没有任何运行时损失.  [MIT] [200].


Lambda速记
-----------------

* [fn](https://github.com/cbaggers/fn)  -几个lambda速记宏.  `（fn *（+ _ _））-&gt;（lambda（_）（+ _ _））.  公共区域.
* [f-underscore](http://quickdocs.org/f-underscore/api)  -一个很小的函数式编程工具库.  `（f_（+ _ _））-&gt;（lambda（_）（+ _ _））.  公共区域.
* [cl-punch](https://github.com/windymelt/cl-punch/)  -类似于Scala的匿名Lambda文字.  `（mapcar ^（* 2 _）&#39;（1 2 3 4 5））`.  [MIT] [200].


另请参阅CL21和[Rutils] [rutils].



非确定性逻辑编程
------------------------------------

* [cl-prolog2](https://github.com/guicho271828/cl-prolog2)  -从Common Lisp到ISO Prolog实施的通用接口.  [MIT] [200].
* [Screamer](https://github.com/nikodemus/screamer) -增加普通
  Lisp具有Prolog和Prolog的几乎所有功能
  约束逻辑编程
  语言. [Blog post](https://chriskohlhepp.wordpress.com/reasoning-systems/specification-driven-programming-in-common-lisp/)
  solving Project Euler puzzles. [MIT][200].
* [Screamer+](https://github.com/yakovzaytsev/screamer-plus)  -提高SCREAMER的表现力.  [MIT] [200].
* [Temperance](https://sjl.bitbucket.io/temperance/)  -逻辑编程.  [MIT] [200].  注重性能，同时考虑一般游戏.

反应式编程
--------------------

* [Cells](https://github.com/kennytilton/cells)  -数据流编程范例的实现，类似于CLOS的反应式电子表格.  用于建造 [algebra learning system](http://tiltontec.com/) .  用 [documentation](https://github.com/stefano/cells-doc/) .  Lisp LGPL.

合同编制
--------------------

* [quid-pro-quo](https://github.com/sellout/quid-pro-quo) - 合同
   Eiffel的《 Design by Contract™》风格的程序库.  公共区域.

Typing
------

* [cl-algebraic-data-type](https://github.com/stylewarning/cl-algebraic-data-type)  -一个用于以与Haskell或ML类似的方式定义代数数据类型的库.  [3子BSD] [15].
*  [trivial-types](https://github.com/m2ym/trivial-types)  -提供缺少但重要的类型定义，例如“ proper-list”，“ association-list”，“ property-list”和“ tuple”.  [LLGPL] [8].


学习与辅导
=====================

## Online ##

Beginner
--------

* [Learn X in Y minutes - Where X = Common Lisp](https://learnxinyminutes.com/docs/common-lisp/) -涵盖基本内容的小型Common Lisp教程.
 * [Practical Common Lisp] [206]-Common Lisp的良好介绍性文字，并附有实际示例.  更好地阅读 [a Firefox add-on](https://github.com/vale981/practical-cl-beautified).
* [Common LISP: A Gentle Introduction to Symbolic Computation](http://www.cs.cmu.edu/afs/cs.cmu.edu/user/dst/www/LispBook/index.html) -语言的不错介绍.
* [Learn LISP: Simply Easy Learning](http://www.tutorialspoint.com/lisp/index.htm)  -一套很好的入门教程；  包括互动示例.
* [Successful Lisp](http://successful-lisp.blogspot.com/) -对于具有某些编程背景的初学者的一本好书.
* [Common Lisp Koans] [201]-该项目通过许多Common Lisp语言功能逐步指导学习者.
* [Lisp Quickstart](https://cs.gmu.edu/~sean/lisp/LispTutorial.html) -一个很好的教程，可以快速起步并编写Common Lisp代码.
* [Casting SPELs in LISP](http://www.lisperati.com/casting.html) -在阅读漫画时学习LISP的有趣方式.

Intermediate
------------

* [The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/)
* [Common Lisp tips](http://lisptips.com/) -包含有用技巧的博客.
* [CommonQt tutorial](https://cheryllium.wordpress.com/2014/02/22/commonqt-tutorial-1/) -CommonQt很好的介绍.
* [A tutorial for creating and publishing open-source Common Lisp software](https://arxiv.org/abs/1209.5626) -使用Quicklisp和其他工具在Common Lisp中创建和发布项目的便捷教程.

Advanced
--------

 * [Lake Over Lambda] [156]-有关高级宏技术的书.  前六章可在​​线获得.
* [On Lisp](http://www.paulgraham.com/onlisp.html) -Paul Graham关于Lisp宏（以及其他有趣内容）的惊人著作.

Reference
---------

* [Common Lisp Quick Reference](http://clqr.boundp.org/index.html)  -精巧的ANSI CL规格袖珍版.  可以下载为PDF.
* [CLHS](http://www.lispworks.com/documentation/lw50/CLHS/Front/index.htm)  -通用Lisp HyperSpec；  ANSI CL标准，以超文本格式.
* [CLOS MOP specification](https://clos-mop.hexstreamsoft.com/) -Metaobject Protocol的艺术第5章和第6章的现代公共领域在线版本
* [Common Lisp Standard Draft (pdf)](https://franz.com/support/documentation/cl-ansi-standard-draft-w-sidebar.pdf) -Common Lisp规范的标准草案，格式正确且带有侧边栏的PDF.
* [Common Lisp the Language](http://www.cs.cmu.edu/Groups/AI/html/cltl/cltl2.html) -ANSI规范之前的Common Lisp的原始标准.
* [Minispec](https://lamberta.github.io/minispec/)  -一个更友好但不完整的CLHS版本.  还包含一些常用CL库的文档（例如Alexandria）.
* [Simplified Common Lisp reference](http://jtra.cz/stuff/lisp/sclr/index.html) -CLHS的简化版本.
* [Quickdocs](http://quickdocs.org/) -Quicklisp提供的库的参考.

## Offline ##

Beginner
--------

* [Land of Lisp](http://landoflisp.com/) -Common Lisp的有趣游戏导向介绍.
* [Practical Common Lisp] [206]-Common Lisp的良好介绍性文字，并附有实际示例.
* [Common Lisp Koans] [201]-该项目通过许多Common Lisp语言功能逐步指导学习者.

Intermediate
------------

* [ANSI Common Lisp](http://www.paulgraham.com/acl.html)  -通过练习全面，实用地覆盖整个语言.  由于[某些警告] [20]，不建议将其作为入门文本.
* [Common Lisp Recipes](http://weitz.de/cl-recipes/)  -** Common Lisp食谱**是问题解决方案和答案的集合，当您在Common Lisp中编写实际应用程序时，可能会遇到这些问题.  2015年出版.

Advanced
--------

 * [Lake Over Lambda] [156]-有关高级宏技术的书.  所有八章均在印刷版本中提供.
* [Common Lisp中的面向对象编程：CLOS程序员指南] [21]-一本关于CLOS的古老但非常详尽的书.
* [人工智能编程范例：Common Lisp中的案例研究] [157]-有关编程AI的书，其中涵盖了一些高级Lisp.

Community
---------

* [/r/Common_Lisp](https://www.reddit.com/r/Common_Lisp/) -关于Common Lisp的subreddit
* [common-lisp.net](https://common-lisp.net)
* [lisp-lang.org](https://lisp-lang.org/)
* [Lisp Discord Server](https://discord.gg/hhk46CE)
* [#lisp](http://log.irc.tymoon.eu/freenode/lisp) 在Freenode上-Common Lisp IRC主频道.

图书馆经理
===============

 *：star：[Quicklisp] [16]-包含许多库的库管理器，具有轻松的依赖管理.  [Expat] [14].
* [Ultralisp](http://ultralisp.org/)  -Quicklisp发行版，每5分钟更新一次，一键即可将其添加到项目中.  [BSD] [15].
* [Quicksys](https://lisp.com.br/quicksys/)  -从多个Quicklisp发行版安装系统.  [MIT] [200].
* [Roswell](https://github.com/roswell/roswell)  -Lisp实施安装程序，脚本启动器等.  [MIT] [200].
* [qlot](https://github.com/fukamachi/qlot)  -项目本地库安装程序，类似于Bundler或Carton.  [Expat] [14].
* [Quickutil](https://github.com/tarballs-are-good/quickutil)  -实用程序管理器，类似于Quicklisp，但适用于小型实用程序而不是整个库.  [3子BSD] [15].
* [Qi](https://github.com/CodyReichert/qi)  -具有传统方法的包装经理.  [BSD] [15].

可能有帮助：

* [print-licenses](https://github.com/vindarel/print-licenses)  -项目及其依赖项使用的打印许可证.  [MIT] [200].

### Interfaces to other package managers

* [cl-brewer](https://github.com/can3p/cl-brewer)  -用于（命令行）常见lisp应用程序的自制程序公式生成器.  公共区域.
* [qldeb](https://github.com/ralt/qldeb) -Quicklisp系统到debian软件包，以及 [deb-packager](https://github.com/ralt/deb-packager) （只需通过定义s表达式创建一个debian软件包）和介绍 [blog post](http://margaine.com/2015/12/22/quicklisp-packagecloud-debian-packages.html) .  两者[MIT] [200].
* [ql-to-deb](https://github.com/dimitri/ql-to-deb)  -从Quicklisp版本中更新cl- * debian软件包.  WTFPL.
* [dh-quicklisp-buildapp](https://github.com/ralt/dh-quicklisp-buildapp)  -debhelper实用程序，使您几乎无需费力就可以将基于quicklisp的Common Lisp代码编译为.deb中的buildapp二进制文件.  [MIT] [200].


机器学习
================

* [clml](https://github.com/mmaul/clml)  -最初由日本公司Mathematicl Systems Inc.开发.  用 [tutorial](https://mmaul.github.io/clml.tutorials//2015/08/08/CLML-Time-Series-Part-1.html) .  [LLGPL] [8].
* [mgl](https://github.com/melisgl/mgl) -由其使用 [author](http://quotenil.com/) 至 [win](https://github.com/melisgl/higgsml)  希格斯玻色子机器学习挑战赛.  [MIT] [200].
* [antik](https://www.common-lisp.net/project/antik/)  -Common Lisp中科学和工程计算的基础.  GPL.  也 [mgl-mat](https://github.com/melisgl/mgl-mat) 和 [LLA](https://github.com/tpapp/lla).

Credit: [borretti.me' state of CL ecosystem 2015](http://borretti.me/article/common-lisp-sotu-2015#machine-learning).


自然语言处理
===========================

* [cl-nlp](https://github.com/vseloved/cl-nlp)  -自然语言处理工具集.  [Apache2.0] [89].
* [babel2](https://github.com/lucas8/Babel2/) -流体构造语法的实现，计算框架和基于统一的语法形式化[Apache2.0] [89].
* [sparser](https://github.com/ddmcdonald/sparser) -自然
 英语语言理解系统.  [Eclipse] [209].



网络与互联网
====================

See [Cliki](http://www.cliki.net/Web) 更多.

HTTP客户端
------------
*  [Dexador](https://github.com/fukamachi/dexador) -一个HTTP客户端，旨在 [replacing Drakma](http://quickdocs.org/dexador/) ，  [带] [200].
* [Carrier](https://github.com/orthecreedence/carrier)  -建立在cl-async和fast-http之上的轻量级异步HTTP客户端.  [MIT] [200].
* [fast-http](https://github.com/fukamachi/fast-http) -快速HTTP
 Common Lisp的请求/响应解析器.  [MIT] [200].


HTTP Servers
------------
* [Clack](https://github.com/fukamachi/clack)  -受Rack和WSGI启发的Web应用程序环境.  [LLGPL] [8].  提供到所选Web服务器的统一界面（默认为Hunchentoot）.  还有更多 [getting started guide](https://jasom.github.io/clack-tutorial/pages/getting-started-with-clack/).
*：星级： [Hunchentoot](http://weitz.de/hunchentoot/)  -Web服务器.  [2子BSD] [207]
* [aserve](https://github.com/franzinc/aserve)  -AllegroServe；  Web服务器.  [LLGPL] [8].
* [wookie](https://github.com/orthecreedence/wookie)  -异步HTTP服务器.  [Expat] [14].
* [woo](https://github.com/fukamachi/woo)  -在libev之上的快速无阻塞HTTP服务器.  [MIT] [200].

### Hunchentoot plugins

* [easy-routes](https://github.com/mmontone/easy-routes)  -在Hunchentoot之上的路线处理系统.  它支持基于HTTP方法的分派，从URL路径中提取参数，装饰器，从路由名称中生成URL等.[MIT] [200].

### Clack plugins

* [clack-errors](https://github.com/eudoxia0/clack-errors)  -Clack的错误页面中间件.  [LLGPL] [8].
* [clath](https://github.com/BnMcGn/clath) -单一登录
   Clack的中间件.  它允许使用OAuth1.0a，OAuth2进行基本登录
   和OpenID.  在撰写本文时，它支持来自
   Google，Twitter，LinkedIn，StackExchange，Reddit和Github.  [Apache2.0] [51].
* [clack-pretend](https://github.com/BnMcGn/clack-pretend) -测试
   和用于调试的调试工具.  [Apache2.0] [89].
* [hermetic](https://github.com/eudoxia0/hermetic)  -基于Clack的Web应用程序的安全性.  [Expat] [14].
* [live-reload](https://github.com/knobo/live-reload)  -实时重新加载原型以进行敲击.  [LLGPL] [8].
* [clack-static-asset-middleware](https://github.com/fisxoj/clack-static-asset-middleware)  -用于破解的缓存无效静态资产中间件.  [MIT] [200].

Web框架
--------------

* [Caveman](https://github.com/fukamachi/caveman)  -强大的网络框架.  [LLGPL] [8].
  示例项目： [Quickdocs](https://github.com/quickdocs)
* [hh-web](https://github.com/hargettp/hh-web)  -用于构建现代Web应用程序的框架.  [Expat] [14].
* [ningle](https://github.com/fukamachi/ningle)  -超微型网络框架.  [LLGPL] [8]. [ninglex](https://github.com/defunkydrummer/ninglex) ，这是扩展的且对新手友好的神经元（通常更易于处理查询参数）.  [MIT] [200].
* [radiance](https://github.com/Shirakumo/radiance)  -Web应用程序环境和框架.  [Artistic License 2.0] [51].
* [Lucerne](https://github.com/eudoxia0/lucerne)  -受Flask启发，基于Clack构建的最小Web框架.  [MIT] [200].
* [Snooze](https://github.com/joaotavora/snooze)  -基于Clack构建的RESTful Web框架，其中路由仅是函数，而HTTP条件仅是Lisp条件.  [LLGPL] [8].
* [cl-rest-server](https://github.com/mmontone/cl-rest-server)  -用于编写REST Web API的库.  具有模式验证，用于日志记录，缓存，权限或身份验证的注释，通过Swagger的文档等功能.[MIT] [200].
* [Weblocks](https://github.com/40ants/weblocks)  -基于窗口小部件的框架，具有内置的ajax更新机制，可“解决JavaScript问题”.  [LLGPL] [8].

 有更多的项目，或多或少地中止了但很有趣.  请参阅其他资源.


资产管理
-----------------

* [Rock](https://github.com/eudoxia0/rock) -的资产经理
   普通Lisp.  它基本上是Bower和
   Webassets.  [带] [200].


解析HTML
------------
* 👍 [Plump][71] - A lenient HTML/XML parser, tolerant on malformed markup. [Artistic License 2.0][51]. Best used with [lquery][72] and [clss](https://github.com/Shinmera/CLSS).

查询HTML / DOM
-----------------
 * [lquery] [72]-一个类似jQuery的HTML / DOM操作库.  [Artistic License 2.0] [51].

另请参阅下面的XML部分以获取xpath库和更多内容.


HTML生成器和模板
-----------------------------
*  [spinneret](https://github.com/ruricolist/spinneret)  -常见的Lisp HTML5生成器.  [Expat] [14].
* [flute](https://github.com/ailisp/flute) -一个易于组合的HTML5生成库，其中包含
   最简单的语法.  [MIT] [200].
*：星级： [cl-who](http://weitz.de/cl-who/)  -古老的HTML生成器.  [FreeBSD] [39].
*：星级： [Djula](https://github.com/mmontone/djula)  -Django模板引擎到Common Lisp的端口.  [Expat] [14].
* [cl-markup](https://github.com/arielnetworks/cl-markup)  -现代标记生成库.  [LLGPL] [8].
* [eco](https://github.com/eudoxia0/eco)  -快速，灵活，设计友好的模板引擎.  [Expat] [14].
* [cl-closure-template](https://github.com/archimag/cl-closure-template)  -实施Google的“关闭”模板.  [LLGPL] [8].
* [clip](https://shinmera.github.io/clip)  -HTML模板处理器，其中模板以HTML编写.  [Artistic License 2.0] [51].

URI动作
------------

* [quri](https://github.com/fukamachi/quri) -另一个URI库
   普通Lisp.  支持用户信息，IPv6主机名，编码/解码
  实用程序，…[BSD_3Clause] [15].
* [purl](https://github.com/eugeneia/purl)  -提供解析器并为RFC1738中指定的URL定义类型.  [GNU GPL3] [2].
* [cl-slug](https://github.com/EuAndreh/cl-slug)  -一个小型库，主要用于URI，在CamelCase中进行转换，删除重音和标点符号，用于英语和英语.  [LLGPL] [8].

Javascript
----------

*：星级： [Parenscript](https://github.com/vsedach/Parenscript)  -从Common Lisp到Javascript的翻译器.  [3子BSD] [15].  看到 [Trident-mode](https://github.com/johnmastro/trident-mode.el)，一种Emacs模式，可与浏览器进行实时交互.[unlicence] [5].
* [parse-js](http://marijnhaverbeke.nl/parse-js/) -用于解析ECMAScript 3的软件包.[zlib] [33].
* [JSCL](https://github.com/jscl-project/jscl)  -从一开始就设计为自托管的CL到JS编译器.  缺少CLOS，格式和循环.
* [CL-JavaScript](http://marijnhaverbeke.nl/cl-javascript/)  -从Javascript到Common Lisp的翻译器.  在Quicklisp上不可用.  [Expat] [14].
* [Wuwei](https://github.com/mtravers/wuwei/)  -用于构建基于Ajax的网页的工具包.  [MIT] [200].
* [SmackJack](https://github.com/aarvid/SmackJack)  -使用parenscript生成javascript和hunchentoot（目前）作为Web服务器的Ajax Common Lisp库.  还允许服务器端lisp函数调用客户端脚本.  [MIT] [200].
* [Panic](https://github.com/michaeljforster/panic) ，一个React的Parenscript库.  不在Quicklisp中.  [MIT] [200].  它 [TodoMVC example](https://github.com/40ants/todomvc/blob/common-lisp-example/examples/common-lisp-react/src/app.lisp).
* [remote-js](https://github.com/ceramic/remote-js)  -将JavaScript从Common Lisp发送到浏览器.  [MIT] [200].

也可以看看
[trident-mode](https://github.com/johnmastro/trident-mode.el)，一个Emacs
实时Parenscript互动的次要模式.


Email
-----

* [trivial-imap](https://github.com/40ants/trivial-imap)  -尝试简化一些使用IMAP服务器的常见情况，例如从服务器读取电子邮件.  邮局库的薄包装（这是Franz的cl-imap的分支）.  [BSD] [15].
* [mailgun](https://github.com/40ants/mailgun)  -薄包装，可通过mailgun.com发布HTML电子邮件.  未指定许可证.
* [mito-email-auth](https://github.com/40ants/mito-email-auth) -通过通过电子邮件向他们发送唯一代码来帮助认证网站用户的助手.


Websockets
----------

*  [usocket](https://github.com/usocket/usocket)  -便携式TCP和UDP套接字接口.  [Expat] [14].
* [websocket-driver](https://github.com/fukamachi/websocket-driver)  -WebSocket服务器/客户端实现，后端不可知（Clack）.  [3子BSD] [15].

查看更多 [on cliki](http://www.cliki.net/site/search?query=websockets).

静态网站生成器
----------------------

* [coleslaw](https://github.com/kingcons/coleslaw) 及其
  [coleslaw-cli](https://github.com/40ants/coleslaw-cli) -灵活
   Lisp Blogware与Frog，Jekyll或Hakyll类似.  [BSD] [15].

Deployment
----------

* [heroku-buildpack-common-lisp](https://gitlab.com/duncan-bayne/heroku-buildpack-common-lisp)  -使用Roswell编译Common Lisp应用程序的Heroku构建包.  LGPL3.
* [cube](https://github.com/xh4/cube)  -从Swagger规范生成的通用LISP的Kubernetes客户端库.  未指定许可证.
* [base-lisp-image](https://github.com/40ants/base-lisp-image) -基础
  带有SBCL或CCL和最新版本的Common Lisp项目的Docker映像
  ASDF，Qlot和Roswell.
* [s2i-lisp](https://github.com/container-lisp/s2i-lisp)  -基于CentOS或RHEL7的“源到映像”构建器映像，用于为OpenShift（以及Docker）构建Common LISP映像.  它具有可与Quicklisp安装，SLIME或SLY集成的最新SBCL，并允许通过环境变量进行自定义.  [AGPL] [89]
* [deploy](https://shinmera.github.io/deploy)  -用于Lisp应用程序二进制部署的工具包，并具有对外部共享库的额外支持.  [Artistic License 2.0] [51].
* [cl-aws-runtime-test](https://github.com/y2q-actionman/cl-aws-custom-runtime-test)  -使用Common Lisp（SBCL）作为AWS lambda上的自定义运行时的示例.  WTFPL.

也可以看看：

- [Heliohost](https://www.heliohost.org/) 免费的托管解决方案.
- [Platform.sh](https://platform.sh/blog/2019/lisp/) 有Common Lisp支持.

Monitoring
----------

* [prometheus.cl](https://github.com/deadtrickster/prometheus.cl)  -Prometheus.io客户端.  Grafana仪表板，用于SBCL和Hunchentoot指标（内存，线程，每秒请求数……）.  [MIT] [200].


第三方API
----------------

* [Aws-sign4](https://github.com/rotatef/aws-sign4) -用于Amazon Web Services签名版本4的通用Lisp库.[GNU GPL3] [2].
* [zs3](https://github.com/xach/zs3) -用于处理Amazon Simple Storage的库
 服务（S3）和CloudFront服务.  [BSD] [15].
* [cl-ses](https://github.com/CodyReichert/cl-ses/)  -适用于AWS SES的库.  [Expat] [14].
* [north](https://shinmera.github.io/north) -的后继者
  南（Simple OaUTH）库，实现完整的oAuth 1.0a
   客户端和服务器端的协议.  使用北，您可以轻松
   成为oAuth提供者或使用者.  [Artistic License 2.0] [51].
* [avatar-api](https://github.com/eudoxia0/avatar-api)  -从Google +，Gravatar和其他人那里获取化身.  [Expat] [14].
* [chirp](https://github.com/Shinmera/chirp)  -Twitter客户端库.  [Artistic License 2.0] [51].
* [tooter](https://github.com/Shinmera/tooter)  -为Mastodon实现完整的v1 REST API协议的客户端库.  [ArtisticLicense2.0] [51].
* [cl-irc](https://www.common-lisp.net/project/cl-irc/)  -IRC客户端库.  [Expat] [14].
* [cl-mediawiki](https://github.com/AccelerationNet/cl-mediawiki)  -MediaWiki API的包装.  [MIT] [200].
* [cl-openid](https://github.com/cl-openid/cl-openid)  -OpenID的实现.  [LLGPL] [8].
* [cl-pushover](https://github.com/TeMPOraL/cl-pushover)  -常见的Lisp绑定到Pushover.  [MIT] [200].
* [humbler](https://github.com/Shinmera/humbler)  -Tumblr API接口.  [Artistic License 2.0] [51].
*[multiposter](https://github.com/Shinmera/multiposter) -同时发布到多个服务.
* [stripe-client](https://github.com/ruricolist/cl-stripe-client)  -Stripe付款系统的客户.  [MIT] [200].

Others
------

* [maiden](https://shirakumo.github.io/maiden)  -具有IRC等功能的机器人和聊天系统框架.  [Artistic License 2.0] [51].
* [css-lite](https://github.com/paddymul/css-lite)  -CSS语法.  [Expat] [14].
* [find-port](https://github.com/eudoxia0/find-port)  -以编程方式找到开放端口.  [MIT] [200].
* [cl-forms](https://github.com/mmontone/cl-forms)  -Common Lisp的Web表单处理库.  [MIT] [200].
* [Postmaster](https://github.com/eudoxia0/postmaster) - A simple, easy-to-use SMTP/IMAP library. [Expat][14].
* [cl-selenium-webdriver](https://github.com/TatriX/cl-selenium-webdriver/) -Selenium 2.0的绑定库.

数值科学
========================

* [numcl](https://github.com/numcl/numcl)  -Common Lisp中的Numpy克隆.  [LGPL3] [9].
* [magicl](https://github.com/rigetticomputing/magicl)  -Rigetti Computing开发的基于BLAS / LAPACK和Expokit的Common Lisp中的矩阵代数程序.  [BSD_3Clause] [15].
* [cl-spark](https://github.com/tkych/cl-spark)  -为数字列表生成迷你图字符串.  [Expat] [14].
* [GSLL](https://common-lisp.net/project/gsll/)  -GNU Lisp科学图书馆；  允许使用Common Lisp提供的GSL.  [GNU LGPL2.1] [11].
* [common-lisp-stat](https://github.com/blindglobe/common-lisp-stat/)  -通用Lisp统计资料库.  [FreeBSD] [39].
* [maxima](http://maxima.sourceforge.net/)  -计算机代数系统.  在Quicklisp上不可用.  [GNU GPL3] [2].
* [lisp-matrix](https://github.com/blindglobe/lisp-matrix)  -矩阵包.  [FreeBSD] [39].
* [3-matrices](https://shinmera.github.io/3d-matrices) -实现库
  通用矩阵计算，重点是2x2、3x3和4x4
   图形中常用的矩阵.  它提供了一些数值
   功能也可以，但是这些并不是重点.  图书馆是
  大量优化，因此它不是由漂亮
   码.  [Artistic License 2.0] [51].
* [Xecto](https://github.com/pkhuong/Xecto)  -用于常规数组并行性的库.  [3子BSD] [15].
* [Petalisp](https://github.com/marcoheisig/Petalisp) -试图
  通过以下方式为并行计算机生成高性能代码
   JIT编译数组定义.  它适用于更多
  通过提供更强大的功能，比NumPy具有更高的基本水平
  N维数组，但仅用于构建的几个构建基块
   他们.  [AGPL] [89].
* [cmu-infix](https://github.com/rigetti/cmu-infix) -用于在Common Lisp中编写中缀数学符号的库.
* [cl-ana](https://github.com/ghollisjr/cl-ana)  -通用Lisp数据分析库，着重于模块化和概念清晰性.  它旨在成为分析小型和大型数据集的通用框架，包括分箱数据分析和可视化.  [GNU GPL3] [2].
* [linear-programming](https://neil-lindquist.github.io/linear-programming/)  –用于解决线性编程问题的库.  [MIT] [200].


并行与并发
===========================

*：星级： [BordeauxThreads](https://common-lisp.net/project/bordeaux-threads/)  -可移植的共享状态并发.  [Expat] [14].
*：星级： [lparallel](https://github.com/lmj/lparallel)  -用于并行编程的库.  [3子BSD] [15].
* [lfarm](https://github.com/lmj/lfarm)  -在机器之间分配工作（在并行和usocket之上）.  [BSD_3Clause] [15]
* [chanl](https://github.com/zkat/chanl)  -可移植的基于通道的并发.  [Expat] [14]，部分内容位于[3-clause BSD] [15]下.
* [cl-async](https://github.com/orthecreedence/cl-async)  -用于通用，非阻塞编程的库.  [Expat] [14].
* [erlangen](https://github.com/eugeneia/erlangen) - Distributed, asynchronous message passing system for Clozure Common Lisp. [GNU GPL3][2]. See also the [Actors](https://github.com/aarvid/Actors) LispWorks的软​​件包（[discussion](https://www.reddit.com/r/Common_Lisp/comments/77vsft/david_mcclains_actors_package_for_lispworks/)）[MIT] [200].
* [Moira](https://github.com/TBRSS/moira)  -监视并重新启动后台线程.  lisp过程主管.  未指定许可证.
* [trivial-monitored-thread](https://gitlab.com/ediethelm/trivial-monitored-thread) -
  一个通用的Lisp库，提供了一种生成线程并被
   通知他们中的任何一个崩溃和死亡.  [MIT] [200].
* [cl-gearman](https://github.com/taksatou/cl-gearman) -图书馆 [Gearman](http://gearman.org/)  分布式工作系统.  [LLGPL] [8].
* [swank-crew](https://github.com/brown/swank-crew)  -使用Swank Client实现的分布式计算框架.  [BSD_3Clause] [15].


事件处理
----------------

* [simple-tasks](https://github.com/Shinmera/simple-tasks) -非常
   简单的任务调度框架.  [Artistic License 2.0] [51].
* [deeds](https://github.com/Shinmera/deeds) -行动是可扩展
   事件传递系统.  它可以有效地将事件传递给
  具有复杂事件过滤的多个处理程序
   系统.  [Artistic License 2.0] [51].
* [cl-flow](https://github.com/borodust/cl-flow/)  -数据丰富的计算树库，用于非阻塞并发Common Lisp.  [MIT] [200].
* [event-glue](https://github.com/orthecreedence/event-glue)  -简单的事件抽象.  没有依赖关系.  它可以在需要通用事件处理系统的任何地方使用.  [MIT] [200].


作业处理
--------------

* [psychiq](https://github.com/fukamachi/psychiq)  -用于Common Lisp应用程序的基于Redis的后台作业处理.  受到Ruby的Sidekiq的启发，并与其Web UI兼容.  [LLGPL] [8].
* [clerk](https://github.com/tsikov/clerk)  -具有健全DSL的类似cron的调度程序.  [MIT] [200].

Regex
=====

*：星级： [cl-ppcre](http://weitz.de/cl-ppcre/)  -兼容Perl的可移植正则表达式.  [FreeBSD] [39].


Scripting
=========

*  [Roswell](https://github.com/roswell/roswell#scripting-with-roswell) -
  Lisp安装程序和脚本环境（帮助程序，启动器，
   安装程序）等.  [MIT] [200].
* [Shelly](https://github.com/fukamachi/shelly) -执行Common Lisp
  功能类似于shell命令，而无需编写命令
   行参数解析器.  它也可以用作Make-like
   构建工具.  [FreeBSD] [39].
* [cl-readline](https://github.com/vindarel/cl-readline) - 一套
  键入时编辑行的功能，以维护行列表
  先前输入的命令行，以对其进行重新调用和重新编辑，以及
   执行类似csh的历史记录扩展.  Emacs和vi编辑
   模式.  [GPL3] [2].
*  [Unix-opts](https://github.com/mrkkrp/unix-opts) -命令行
   选项解析器，带有简洁的选项声明.  [MIT] [200].
* [CLON](https://github.com/didierverna/clon) -命令行选项
  Nuker. [ISC](https://github.com/didierverna/clon/blob/master/LICENSE).
* [cl-ansi-term](https://github.com/vindarel/cl-ansi-term) -打印
  彩色文本，水平线，进度条，（无序）列表
   和符合ANSI的终端上的表格.  [GPL3] [2].
* [cl-charms](https://github.com/HiTECNOLOGYs/cl-charms) -一个
   到Common Lisp中的`libcurses`接口.  它提供了原始
  通过CFFI进行libcurses的低级接口，以及更高级别的接口
   Lispier界面.  [带] [200].
* [shcl](https://github.com/bradleyjensen/shcl)  -Common Lisp中类似POSIX的外壳.  [Apache2.0] [51].
* [cl-progress-bar](https://github.com/sirherrbatka/cl-progress-bar/)  -进度条，就像在Quicklisp中一样！  [MIT] [200].
* [WCL](https://github.com/wadehennessey/wcl) -允许数百Lisp
一次可实际获得应用程序，同时允许
 其中几个要同时运行.  WCL通过以下方式完成此任务
提供Common Lisp作为可以与以下链接的Unix共享库
 Lisp和C代码可产生高效的应用程序.  例如，
Lisp版本的“ Hello World！”的可执行文件！
 在32位x86 Linux上，该程序仅需要20k字节.  WCL也
支持完整的开发环境，包括动态文件
 加载和调试.  GDB的修改版用于调试WCL
程序，为混合语言调试提供支持.
* [replic](https://github.com/vindarel/replic/)  -帮助程序将现有代码转换为readline应用程序，重点放在定义命令参数的完成.  还提供了一个随时可用的可执行文件，它将用户的lispy初始化文件转换为readline命令.  [MIT] [200].
* [cl-all](https://github.com/shinmera/cl-all)  -在多个实现中运行Lisp代码段的脚本.  这使您可以快速比较实施行为和差异.  [Artistic License 2.0] [51].

文字编辑器资源
=====================

其中包含适用于各种文本编辑器的插件和其他工具.

* [Parinfer](https://shaunlebron.github.io/parinfer/)  -Parinfer是一种编辑Lisp代码的方法，有助于保持缩进和括号之间的平衡.  开始时很容易，但是它提供了Paredit的高级功能.  它在许多编辑器（Emacs，Vim，Neovim，Atom，Sublime Text，Visual Studio Code，LightTable，CodeMirror等）中都可用.

## Emacs ##

*：星级： [Slime](https://github.com/slime/slime)  -Emacs的高级Lisp交互模式；  Emacs内部Common Lisp的成熟环境.  公共区域.
*  [Sly](https://github.com/joaotavora/sly) -SLY是SLIME的分支，对其进行了多项改进.
*  [Portacle](https://shinmera.github.io/portacle/) -便携式多平台通用Lisp环境：SBCL，Quicklisp，Emacs，Slime，Git.
* [cl-devel2](https://hub.docker.com/r/eshamster/cl-devel2/)  -用于Common Lisp开发环境的Docker容器.  随SBime，CCL，Roswell和Emacs25一起运送Slime.

## Vim & Neovim ##

* [SLIMV](https://github.com/kovisoft/slimv)  -Vim的高级Lisp交互模式；  Vim内部Common Lisp的成熟环境.  未指定许可证.
* [Vlime](https://github.com/l04m33/vlime)  -VLIME：Vim加Lisp大多是邪恶的.  Vim（和Neovim）的通用Lisp开发环境.  [MIT] [200].
* [quicklisp.nvim](https://gitlab.com/HiPhish/quicklisp.nvim) -Neovim的Quicklisp前端.
* [Slimv_box](https://github.com/justin2004/slimv_box) -在Docker容器中使用slimv.


## Eclipse ##

* [Dandelion](https://github.com/Ragnaroek/dandelion) -Eclipse IDE的Common Lisp插件.

## Lem ##

* [Lem](https://github.com/cxxxr/lem) -即用型，基于Emacs的，基于Slime
   专为Common Lisp开发量身定制的编辑器.  Ncurses和电子接口.  [MIT] [200].  一个 [opengl frontend](https://github.com/pupcraft/lem-opengl).

## Atom ##

* [SLIMA](https://github.com/neil-lindquist/slima) 让你
  交互式开发Common Lisp代码，从而将Atom变成
   Lisp IDE非常好，并且积极开发.  [MIT] [200].

## Sublime Text ##

* [Sublime Text](http://www.sublimetext.com/3) 有Common Lisp支持
   及其“ SublimeREPL”软件包.  [所有权].

## VSCode ##

* [VSCode-lisp](https://marketplace.visualstudio.com/items?itemName=mattn.Lisp)  -支持Lisp语法的扩展.  它是 [on GitHub](https://github.com/mattn/vscode-lisp).

## Notebooks ##

* [cl-jupyter](https://github.com/fredokun/cl-jupyter) -适用于Jupyter笔记本的Common Lisp内核 [custom licence](https://github.com/fredokun/cl-jupyter/blob/master/LICENSE).
* [common-lisp-jupyter](https://github.com/yitzchak/common-lisp-jupyter)  -用于Jupyter的Common Lisp内核以及用于构建Jupyter内核的库，该库基于Robert Dodier的Maxima-Jupyter，该库基于Frederic Peschanski的cl-jupyter.  [MIT] [200].
* [Darkmatter](https://github.com/tamamu/darkmatter) - 一种
   笔记本样式的通用Lisp环境.  [MIT] [200].

## REPLs ##

* [cl-repl](https://github.com/koji-kojiro/cl-repl)  -类似于ipython的REPL.  完成后，将执行shell命令，魔术命令，调试器等.[MIT] [200].  用 [colorthemes](https://github.com/koji-kojiro/lem-pygments-colorthemes).

文字处理
===============

* [montezuma](https://github.com/sharplispers/montezuma/)  -全文索引并搜索Common Lisp.  [Expat] [14].
* [mk-string-metrics](https://github.com/cbaggers/mk-string-metrics) -
  在Common Lisp中高效地计算各种字符串指标
  （Damerau-Levenshtein，Hamming，Jaro，Jaro-Winkler，Levenshtein，
   等）.  [带] [200].
* [cl-yacc](https://github.com/jech/cl-yacc)  -LALR（1）解析器生成器.  [带] [200].
* [wiki-lang-detect](https://github.com/vseloved/wiki-lang-detect) -
 使用Wikipedia数据进行文字语言识别.  未指定许可证.

Tools
=====

这些是应用程序或一些代码，它们使Common Lisp的开发变得更加容易，而无需成为Common Lisp库本身.

 * [quickapp] [188]-一个用于使用SBCL和buildapp生成模板项目的项目.  还包括命令行argparser.  [3子BSD] [15].
* [quickapp-cli](https://github.com/triclops200/quickapp-cli)  -[quickapp] [188]作为命令行实用程序.  [3子BSD] [15].
* [quicksearch](https://github.com/tkych/quicksearch)  -从REPL查找在线图书馆.  [Expat] [14].
* [SWIG](http://www.swig.org/)  -一种用于从C / C ++头文件生成FFI代码的工具.  [GNU GPL3] [2].
* [cl-project](https://github.com/fukamachi/cl-project)  -一般的现代项目骨架.  [LLGPL] [8].
* [lake](https://github.com/takagi/lake)  -一个GNU make like build实用程序.  [MIT] [200].


单元测试
============

*：星级： [FiveAM](https://github.com/sionescu/fiveam)  -简单的回归测试框架.  [FreeBSD] [39].
* [CLUnit](https://github.com/tgutu/clunit)  -单元测试库.  [Expat] [14].
* [Rove](https://github.com/fukamachi/rove)  -Rove是Common Lisp应用程序的单元测试框架.  它旨在成为 [Prove](https://github.com/fukamachi/prove) .  [3子BSD] [15].
* [Parachute](https://github.com/Shinmera/parachute) -可扩展
   和交叉兼容的测试框架.  有了测试依赖性
   条件，装置和重启.  [Artistic License 2.0] [51].
* [Mockingbird](https://github.com/Chream/mockingbird) - 一个小
   Common Lisp的存根和模拟库.  也可以检查一下
  一个存根函数被调用了多少次
   参数.  [带] [200].
* [Check-it](https://github.com/DalekBaldwin/check-it)  -一种QuickCheck样式的基于属性的随机测试.  [LLGPL] [8].
* [cl-coveralls](https://github.com/fukamachi/cl-coveralls) -帮手
   库将测试覆盖范围发布到Coveralls.  看到
  [continuous-integration on lisp-lang.org](http://lisp-lang.org/learn/continuous-integration)
  和
  [SBCL's code coverage tool](http://www.sbcl.org/manual/index.html#sb_002dcover) .  [FreeBSD] [39].


Utilities
=========

Caching
-------

* [clache](https://github.com/html/clache)  -常规缓存设施.  未指定许可证.


Configuration
-------------

*  [py-configparser](https://common-lisp.net/project/py-configparser/)  -读写Python的类似ConfigParser的配置文件.  [MIT] [200].
* [envy](https://github.com/fukamachi/envy)  -配置切换器.  [FreeBSD] [39].
* [chameleon](https://github.com/sheepduke/chameleon/)  -配置文件支持附带的配置管理库.  [MIT] [200].

CSV
---

*：星级： [cl-csv](https://github.com/AccelerationNet/cl-csv)  -用于解析CSV文件的库.  [3子BSD] [15].
* [cl-decimals](https://github.com/tlikonen/cl-decimals)  -十进制数解析器和格式化程序.  公共区域.
* [auto-text](https://github.com/defunkydrummer/auto-text)  -自动检测文本文件（编码，行尾，列宽，csv定界符等）.  [MIT] [200].  也可以看看 [inquisitor](https://github.com/t-sin/inquisitor) 用于检测亚洲和远东语言.


日期和时间
-------------

* [localtime](https://common-lisp.net/project/local-time/)  -一个开发库，用于以半标准方式处理日期和时间信息.  [3子BSD] [15].
* [cl-date-time-parser](https://github.com/tkych/cl-date-time-parser)  -自由地解析日期时间字符串.  隐藏日期时间格式之间的差异，并允许将日期和时间作为一种日期时间格式进行管理.  [MIT] [200].
* [chronicity](https://github.com/chaitanyagupta/chronicity)  -自然语言的日期和时间解析，以解析“从现在开始3天”之类的字符串.  [BSD_3Clause] [15].
* [local-time-duration](https://github.com/enaeher/local-time-duration) -
 持续时间处理库建立在本地时间之上.  [MIT] [200].
* [iso-8601-date](https://gitlab.com/DataLinkDroid/iso-8601-date)  -Common Lisp中的其他日期例程，基于ISO 8601字符串表示形式.  [LLGPL] [8].

资料验证
---------------

* [ratify](https://github.com/Shinmera/ratify)  -一组用于批准，验证和解析输入的实用程序.  [Artistic License 2.0] [51].
* [clavier](https://github.com/mmontone/clavier)  -Common Lisp的通用验证库.  [MIT] [200].
* [sanity-clause](https://github.com/fisxoj/sanity-clause)  -Common Lisp的数据序列化/合同库.  模式可以是属性列表或基于类的，允许在make-instance期间检查插槽的类型.  [LLGPL] [8].

开发人员实用程序
-------------------

* [repl-utilities](https://github.com/m-n/repl-utilities) -轻松
REPL的常见任务（打印文档，打印外部符号，
 加载程序包时调用钩子，…）.  [BSD_2Clause] [17].

文档建设者
----------------------

* [sphinxcontrib-cldomain](https://github.com/russell/sphinxcontrib-cldomain) -
   扩展Sphinx以覆盖Common Lisp.  要建立文件
   与sphinx一样容易，而Python项目却是如此.  [GPL3] [2]
* [Codex](https://github.com/CommonDoc/codex) - 一个美丽
   Lisp的文档系统.  [MIT] [200].
* [Staple](https://github.com/Shinmera/staple) -生成工具
   使用HTML模板的文档页面.  使用现有
  自述文件，将文档字符串，交叉引用和链接添加到
   CLHS  [ArtisticLicense2.0] [51].
* [cl-bibtex](https://github.com/mkoeppe/cl-bibtex)  -使用BST到CL编译器的Common Lisp中的BibTeX程序的兼容重新实现.  [GNU LGPL2.1] [11].
* [mgl-pax](https://github.com/melisgl/mgl-pax) -探索性
 编程环境和文档生成器.  一个可能
达到与Literate Programming相似的效果，但是
 文档是从代码生成的，反之亦然.  代码是第一位
 代码必须看起来很漂亮，文档就是代码.  [MIT] [200].
* [erudite](https://github.com/mmontone/erudite)  -精巧的编程系统，考虑了交互式开发.  [MIT] [200].


文件和目录
---------------------

*：星级： [uiop](http://quickdocs.org/uiop/) 及其`pathname`包
  （替换 [cl-fad](http://weitz.de/cl-fad/) ）.  uiop是ASDF3的一部分
   因此，在许多实施方式中都可以使用.  [MIT] [200].
* [osicat](https://common-lisp.net/project/osicat/) -类似于POSIX的系统上的轻量级操作系统界面（目录迭代和删除，环境变量，文件权限等）[Expat] [14].
* [pathname-utils](https://github.com/Shinmera/pathname-utils) - 一种
  实用程序集合，以帮助使用路径名
   操作.  [Artistic License 2.0] [51].
* [archive](https://github.com/froydnj/archive)  -用于读取和创建存档（tar，cpio）文件的库.  [BSD_3Clause] [15].  “ tar”程序的纯Common Lisp替代品.

Git
---

* [legit](https://shinmera.github.io/legit/) -Git的接口
   二进制  [Artistic License 2.0] [51].

i18n
----

* [cl-i18n](https://notabug.org/cage/cl-i18n)  -i18n库.  从GNU gettext文本或二进制文件或其本地格式加载翻译.  复数形式的本地化帮助器.  [LLGPL] [8].
* [cl-locale](https://github.com/fukamachi/cl-locale)  -一个简单的i18n库.  [LLGPL] [8].
* [enchant](https://github.com/tlikonen/cl-enchant)  -附魔拼写检查器库的绑定.  公共区域.
* [oxenfurt](https://github.com/Shinmera/oxenfurt)  -牛津词典API的客户端库.  [ArtisticLicense2.0] [51].
* [language-codes](https://shinmera.github.io/language-codes)  -ISO语言代码的数据库库.  [艺术许可2.0] [51]
* [system-locale](https://shinmera.github.io/system-locale)  -用于检索用户首选语言的库，以便您的应用程序可以选择合理的默认值.  [Artistic License 2.0] [51].
* [multilang-documentation](https://shinmera.github.io/multilang-documentation)  -允许以多种语言编写文档字符串，用于真正具有国际记录的库.  [Artistic License 2.0] [51].

Linting
-------

* [sblint](https://github.com/fukamachi/sblint) -普通棉短绒
  使用SBCL的Lisp源代码，适用于Reviewdog（[slides](http://www.slideshare.net/fukamachi/sblint) ）.  [BSD_2Clause] [17].


Logging
-------

*：星级： [log4cl](https://github.com/sharplispers/log4cl/)  -根据Log4J建模的日志记录框架.  [Apache2.0] [89].  与Slime的高级集成.
* [verbose](https://shinmera.github.io/verbose)  -快速且高度可配置的日志记录框架.  [Artistic License 2.0] [51].
* [a-cl-logger](https://github.com/AccelerationNet/a-cl-logger)  -日志记录库提供上下文相关的日志记录，不仅记录字符串，还记录本地文件或输出流.  具有logstash支持，json支持，记录器层次结构，上下文相关的记录，以可检查的演示形式打印的对象等功能…

致第三方：

* [cl-fluent-logger](https://github.com/fukamachi/cl-fluent-logger) -通用的Lisp结构化记录器 [Fluentd](https://www.fluentd.org/).

也可以看看： [extensive comparison of logging libraries](https://sites.google.com/site/sabraonthehill/comparison-of-lisp-logging-libraries).


Markdown
--------

* [3bmd](https://github.com/3b/3bmd)  -markdown-&gt; html转换器.  [MY] [200].

PDF
---

* [cl-typesetting](https://github.com/mbattyani/cl-typesetting) 和 [cl-pdf](https://github.com/mbattyani/cl-pdf)  -用于生成PDF文件的跨平台Common Lisp库.  [FreeBSD] [39].
* [cl-pslib](http://quickdocs.org/cl-pslib/) -薄的包装纸 [pslib](http://pslib.sourceforge.net/)  库，用于生成PostScript文件.  也 [cl-pslib-barcode](http://quickdocs.org/cl-pslib-barcode/) .  [LLGPL] [8].

Plotting
--------

* [vgplot](https://github.com/volkers/vgplot) -的接口
  gnuplot绘图实用程序，旨在类似于
   八度或matlab的绘图命令.  [GPL3] [2].
* [eazy-gnuplot](https://github.com/guicho271828/eazy-gnuplot) - 一种
   lispy，无结构的Gnuplot库.  与它
  [cookbook](http://guicho271828.github.io/eazy-gnuplot/) .  [LLGPL] [8]


Other
-----

其中包含不适合其他类别的任何内容.

* [babel](https://github.com/cl-babel/babel)  -字符集编码/解码库.  [Expat] [14].
* [chipz](https://github.com/froydnj/chipz)  -减压库.  [3子BSD] [15].
* [cl-cuda](https://github.com/takagi/cl-cuda)  -在Common Lisp程序中使用NVIDIA CUDA的库.  [LLGPL] [8].
* [corona](https://github.com/eudoxia0/corona) -通过Common Lisp http://eudoxia.me/corona [MIT] [200]创建和管理虚拟机.
*：星级： [esrap](https://github.com/scymtym/esrap)  -Packrat解析器.  [Expat] [14].
* [fast-io](https://github.com/rpav/fast-io)  -快速的八位位组向量/流I / O.  [3子BSD] [15].
* [glyphs](https://github.com/ahungry/glyphs/)  -一个用于减少Common Lisp的详细信息的库.  [GNU GPL3] [2].
* [iolib](https://github.com/sionescu/iolib)  -I / O库.  [Expat] [14].
* [mixalot](https://github.com/ahefner/mixalot)  -松散耦合的音频库集合.  未指定许可证.
* [named-readtables](https://github.com/melisgl/named-readtables)  -提供类似于包名称空间的可读表名称空间.  [3子BSD] [15].
* [nEXT-Browser](http://github.com/nEXT-Browser/nEXT)  -注重生产力，可扩展/可编程的Web浏览器.  [3子BSD] [15].
* [Salza2](http://www.xach.com/lisp/salza2/)  -用于创建压缩数据的库.  [FreeBSD] [39].
* [simple-currency](https://github.com/a0-prw/simple-currency)  -使用欧洲央行发布的每日信息的货币换算库.  [FreeBSD] [39].
* [template](https://bitbucket.org/tarballs_are_good/template)  -类似于C ++的模板和函数库.  [3子BSD] [15].
* [texp](http://mr.gy/software/texp/)  -生成TeX的DSL.  未指定许可证.
* [trivial-benchmark](https://github.com/Shinmera/trivial-benchmark)  -小型基准测试库.  [Artistic License 2.0] [51].
* [trivial-garbage](https://github.com/trivial-garbage/trivial-garbage)  -便携式终结器，弱哈希表和弱指针API.  公共区域.
* [trivial-utf8](https://common-lisp.net/project/trivial-utf-8/)  -用于执行基于UTF-8的I / O的小型库.  BSD.


XML
===

* [CXML](https://common-lisp.net/project/cxml/)  -XML解析器，带有一系列扩展库.  [LLGPL] [8].
 * [Plump] [71]-一个宽松的XML解析器.  [Artistic License 2.0] [51].
* [xpath](https://github.com/sharplispers/xpath) ([homepage](https://common-lisp.net/project/plexippus-xpath/atdoc/index.html)  -XML路径语言（XPath）1.0版的实现.  [BSD_2Clause] [17].
* [s-xml](http://cliki.net/S-XML)  -基本解析器.  [LLGPL] [8].
* [xmls](http://quickdocs.org/xmls/)  -小型，简单，未经验证的XML解析器.  [3子BSD] [15].
* [cl-feedparser](https://github.com/TBRSS/cl-feedparser)  -Common Lisp（RSS，Atom）提要解析器.  [LLGPL] [8]


Contributing
============
 永远欢迎您的贡献！  请提交拉取请求或创建
向列表添加新框架，库或软件的问题.

我们（尝试）遵守的规则如下：

-默认情况下，将库添加到其部分的末尾.
-绝对事实库，例如BordeauxThreads或Quicklisp，
  应该用：star：（在markdown中用`：star：`）表示.
-范围非常相似的两个库应并排放置，或放在一个
  自己的部分.
-根据我们的经验和状态进行一些策划
   图书馆的文件.  我们*不*旨在列出所有现有
  CL库（请参阅Quickdocs或Cliki）或列出每个库
  “热门”库（请参阅Quicklisp统计信息）.
-因此，我们最喜欢的库都标有（`1F44D`
   unicode字符）.  另请参阅
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

[rutils]：https：//github.com/vseloved/rutils）
