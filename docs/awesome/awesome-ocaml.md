<div class="github-widget" data-repo="ocaml-community/awesome-ocaml"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
很棒的OCaml [![Build Status](https://travis-ci.org/ocaml-community/awesome-ocaml.svg?branch=master)](https://travis-ci.org/ocaml-community/awesome-ocaml)
=============

<img src="https://raw.githubusercontent.com/ocaml-community/awesome-ocaml/master/colour-logo.png" width="70%" />

&gt; _ **在掌握OCaml的过程中，您将需要的一切.** _

 精选的精选OCaml工具，框架，库和文章的参考清单.  此外，还有一些免费提供的收藏 [**books**](https://github.com/rizo/awesome-ocaml/tree/master/books), [**papers**](https://github.com/rizo/awesome-ocaml/tree/master/papers) 和 [**presentations**](https://github.com/rizo/awesome-ocaml/tree/master/presentations).

如果您正在寻找有关OCaml的全面的社区驱动内容，请访问 [OCamlverse](https://ocamlverse.github.io/)!

有关现代OCaml开发工作流程的快速介绍，请参阅 [**OCaml for the impatient**](https://adambard.com/blog/getting-started-with-ocaml/) 指南.

 您最喜欢的包装没有列出？  叉和 [create a Pull Request](https://github.com/rizo/awesome-ocaml/edit/master/README.md) 添加它！



* * *


## Community

- [Official OCaml Website](https://ocaml.org/)
- [OCaml Discourse Web Forum](https://discuss.ocaml.org/)
- [OCaml Discord Chat](https://discord.gg/ZBgYuvR)
- [Official OCaml Mailing List](http://caml.inria.fr/resources/forums.en.html)
- [OCaml Planet](https://ocaml.org/community/planet/)
- [OCaml SubReddit](https://www.reddit.com/r/ocaml/)


## Algorithms and Data Structures

- [Comparing a Machine Learning Algorithm Implemented in F# and OCaml](https://philtomson.github.io/blog/2014-05-29-comparing-a-machine-learning-algorithm-implemented-in-f-sharp-and-ocaml/)
- [OCamlgraph](https://github.com/backtracking/ocamlgraph) – OCaml的通用图形库.
- [ods](https://github.com/owainlewis/ods) – OCaml的大量数据结构和算法.
- [combine](https://github.com/backtracking/combine)  –用于组合的OCaml库 <https://www.lri.fr/~filliatr/combine/>  .
- [Decompress](https://github.com/mirage/decompress) -Zlib的纯OCaml实现.
- [Ke](https://github.com/mirage/ke) -在OCaml中快速实现队列（FIFO）.
- [Duff](https://github.com/mirage/duff) -P. MacDonald在OCaml中实现Rabin指纹和delta压缩（与 [libXdiff](http://www.xmailserver.org/xdiff-lib.html)
- [ORaft](https://github.com/komamitsu/oraft) -的图书馆 [Raft consensus algorithm](https://raft.github.io/raft.pdf) 在OCaml中实现


## Application Libraries

- [Batteries Included](https://github.com/ocaml-batteries-team/batteries-included) –用于OCaml项目的社区维护的基础库.
- [Cmdliner](https://github.com/dbuenzli/cmdliner) – OCaml的命令行界面的声明性定义.
- [Core](https://github.com/janestreet/core)  – Jane Street Capital的完整标准库覆盖图.  还提供了可移植的Core子集： [Core_kernel](https://github.com/janestreet/core_kernel).
- [Base](https://github.com/janestreet/base) -简街资本（Jane Street Capital）无依赖，快速编译，可在可运行OCaml代码标准库的任何环境中完全移植.
- [React](http://erratique.ch/software/react)  – React是用于功能反应式编程（FRP）的OCaml模块.  它为时变值的编程提供支持：声明性事件和信号.
- [Minicli](https://github.com/UnixJunkie/minicli) –用于命令行解析的极简库.
- [easy-format](https://github.com/mjambon/easy-format) – OCaml的漂亮打印库.
- [ocaml-rpc](https://github.com/mirage/ocaml-rpc) –轻型库，用于处理OCaml中的RPC.
- [ocaml-containers](https://github.com/c-cube/ocaml-containers)  –轻量级的模块化标准库扩展，字符串库和各种库（bigarray，unix等的接口）.  BSD许可证.


## Benchmarking

- [core_bench](https://github.com/janestreet/core_bench) – Jane Street提供的OCaml微基准测试库.
  - [Getting Started with Core_bench](https://github.com/janestreet/core_bench/wiki/Getting-Started-with-Core_bench)
- [benchmark](https://github.com/Chris00/ocaml-benchmark) –基准测试功能，用于使用延迟或吞吐量来测量功能的运行时间.


## Blogs

- [Gagallium](http://gallium.inria.fr/blog/)
- [Type OCaml – Many things about OCaml](http://typeocaml.com/)
- [OCaml Platform](https://opam.ocaml.org/blog/)
- [Drup's Thingies](https://drup.github.io/)

## Books

- [More OCaml: Algorithms, Methods, and Diversions](https://www.amazon.com/More-OCaml-Algorithms-Methods-Diversions/dp/0957671113/)  –在More OCaml中，约翰·惠灵顿（John Whitington）曲折地浏览了OCaml的函数式编程，介绍了各种语言功能并描述了一些经典算法.  本书最后有一个处理PDF文件生成的大型示例.  每章都有问题，以及有效的答案和提示.
- [How to Think Like a (Functional) Programmer](http://www.greenteapress.com/thinkocaml/index.html)  艾伦·唐尼（Allen Downey）和尼古拉斯·蒙耶（Nicholas Monje）撰写的-《如何像计算机科学家一样思考》是一本基于OCaml语言的入门编程教科书.  它是Allen Downey编写的Think Python的修改版本.  它适用于编程的新手，以及那些了解一些编程但想在面向功能的范式中学习编程的人，或者只是想学习OCaml的人.
- [OCaml from the Very Beginning](http://ocaml-book.com/) 由J. Whitington撰写-OCaml从一开始就将吸引新的程序员，以及经验丰富的渴望探索功能语言（例如OCaml）的程序员.
- [Pearls of Functional Algorithm Design](https://www.amazon.co.uk/Pearls-Functional-Algorithm-Design-Richard/dp/0521513383)  由理查德·伯德（Richard Bird）撰写-总结了函数编程世界中的30个难题.  尽管是针对Haskell的，但算法问题却非常有趣，尝试在OCaml中解决它们也有助于功能编程的思考.  OCaml中的部分解决方案是 [here](https://github.com/MassD/pearls).
- [Real World OCaml](https://realworldocaml.org/) 由Y. Minsky，A.Madhavapeddy和J. Hickey编写-面向大众的函数式编程.
- [Unix System Programming in OCaml](https://ocaml.github.io/ocamlunix/) 由X. Leroy和D.Rémy撰写– Unix系统编程简介，重点是进程之间的通信.
- [Using, Understanding, and Unraveling OCaml](https://caml.inria.fr/pub/docs/u3-ocaml) –本书描述了OCaml语言及其强大的类型系统背后的理论基础.
- [Purely Functional Data Structures](https://www.amazon.co.uk/Purely-Functional-Structures-Chris-Okasaki/dp/0521631246/ref=sr_1_1?ie=UTF8&qid=1406279836&sr=8-1&keywords=functional+data+structures)  -这是针对FP世界中各种数据结构的第一本或唯一一本书籍.  必读的.
- [OCaml for Scientists](http://www.ffconsultancy.com/products/ocaml_for_scientists/) -乔恩·哈罗普（Jon Harrop）.
- [Functional Programming in OCaml: A Principled Approach](http://www.cs.cornell.edu/courses/cs3110/2018fa/textbook/) -康奈尔大学CS 3110数据结构和功能编程教科书.



## Code Analysis and Linters

- [Mascot](http://mascot.x9c.fr/) -Mascot是OCaml来源的样式检查器
- [pfff](https://github.com/aryx/pfff) – pfff是一组工具和API，用于执行一些静态分析，动态分析，代码可视化，代码导航或保留样式的源到源转换，例如对源代码进行重构.
- [Infer](https://github.com/facebook/infer) -Infer是用于Java，C和Objective-C的静态分析器
- [Frama-C](http://frama-c.com) -Frama-C是针对C和C ++的静态分析和形式证明框架
- [flow](https://github.com/facebook/flow) -flow是JavaScript的静态类型检查器
- [SLAyer](https://github.com/Microsoft/SLAyer) -SLAyer是一种自动形式验证工具，该工具使用分隔逻辑来验证C程序的内存安全性.
- [MemCAD](https://github.com/Antique-team/memcad)  -MemCAD是用于形状分析的抽象解释器.  MemCAD可以验证处理复杂数据结构的C程序.

## Program analysis
- [BAP](https://github.com/BinaryAnalysisPlatform/bap) -BAP是针对二进制程序的反向工程和程序分析平台.
- [BinCat](https://github.com/airbus-seclab/bincat) -BinCat是一个二进制代码静态分析工具包.
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) -cwe_checker在二进制可执行文件中找到易受攻击的模式.

## Compilers and Compiler Tools

-**语言和编译器**：
  - [cDuce](http://www.cduce.org/) -cDuce是一种具有创新功能的现代XML面向功能语言.
  - [Compcert C Compiler](http://compcert.inria.fr/) -它是C编译器，支持大多数ISO C90和C99 / ANSI C功能.
  - [Eff Programming Language](http://www.eff-lang.org/) -Eff是一种功能语言，不仅具有异常处理程序，而且还具有其他计算效果（例如状态或I / O）的处理程序.
  - [Hack Programming Language](https://hacklang.org/)
  - [Haxe Programming Language](https://haxe.org/)
  - [Neko Programming Language](https://nekovm.org/) -最初，编译器是用OCaml编写的.
  - [Mezzo Programming Language](https://protz.github.io/mezzo/) -Mezzo是ML传统中的一种编程语言，它特别强调对别名的控制和对可变内存的访问.
  - [OCaml-Java](http://www.ocamljava.org/) -OCaml到Java字节码编译器.
  - [Opa Programming Language](http://opalang.org/)
  - [Rhine](https://github.com/artagnon/rhine-ml) –用OCaml编写的有关LLVM的Lisp.
  - [Rust Programming Language](https://www.rust-lang.org/) -最初在引导前用OCaml编写.
  - [Quick C-- Target Language](http://www.cminusminus.org/) -现在这是一个失败的项目. [Github Repo](https://github.com/nrnrnr/qc--). [Alternative website](http://www.cs.tufts.edu/~nr/c--/qc--.html).
  - [tis-interpreter](https://github.com/TrustInSoft/tis-interpreter) -在标准C语言编写的程序中发现细微错误的解释器

  - [Reason](http://facebook.github.io/reason/) -Facebook OCaml的友好语法和工具链.
  - [RaML](http://raml.co/index.html) -资源感知ML（RaML）是一种工具，可以自动和静态地计算OCaml程序的资源使用范围.

-**解析器和词法生成器**：
  - [Opal](https://github.com/pyrocat101/opal) –用于OCaml的独立式Monadic解析器组合器.
  - [Sedlex](https://github.com/ocaml-community/sedlex) 是现代的，与编码无关的（阅读：支持Unicode的）词法分析器生成器（基于ppx的后继生成器） [ulex](http://www.cduce.org/download.html#side).)
  - [Menhir](http://gallium.inria.fr/~fpottier/menhir/) – Menhir是OCaml的LR（1）解析器生成器.
    -看 [ocaml-parsing](https://github.com/smolkaj/ocaml-parsing) 有关使用Menhir和Sedlex生成有用的解析器的更清晰示例，
    -...和 [Obelisk](https://github.com/Lelio-Brun/Obelisk)，一个精巧的项目，可为您的语法生成可读的LaTeX，HTML或纯文本EBNF样式的文档.
  - [ocamllex/ocamlyacc](http://caml.inria.fr/pub/docs/manual-ocaml-4.01/lexyacc.html) – OCaml的lex和yacc实现.
  - [Angstrom](https://github.com/inhabitedtype/angstrom) -解析器组合器，旨在提高速度和内存效率
-**文章**：
  - [Kaleidoscope: Implementing a Language with LLVM in Objective Caml¶](http://llvm.org/docs/tutorial/OCamlLangImpl1.html)


## Concurrency

 OCaml中存在两个并发库：_Lwt_和_Async_.  它们提供了非常相似的功能，但是在错误处理和内部实现细节方面做出了截然不同的决定（更多信息请参见下面的链接）. [Real World OCaml](https://realworldocaml.org/) 使用异步，但使用 [code examples translated to Lwt](https://github.com/dkim/rwo-lwt) 也可以.

-**图书馆**：
  - [Lwt](http://ocsigen.org/lwt/) — OCaml的合作线程库.
  - [Async](https://opensource.janestreet.com/async/) —与Core库一起使用的monadic并发库.
-**文章**：
  - [The blog post that introduced Async](https://blog.janestreet.com/announcing-async/)
  - [A user gives up on Async](http://rgrinberg.com/posts/abandoning-async/)
  - [Cooperative Concurrency in OCaml: A Core.Std.Async Example](http://philtomson.github.io/blog/2014/07/09/core-dot-async-example/).

还有一个正在进行的实验项目可以使OCaml多处理器和多核在 [OCaml multicore](https://github.com/ocamllabs/ocaml-multicore) 叉子.

## Databases

-**绑定**
  - [Dbm](https://forge.ocamlcore.org/projects/camldbm/) —绑定到NDBM / GDBM Unix“数据库”.
  - [Mongo.ml](https://massd.github.io/mongo/) – Mongodb的OCaml驱动程序
  - [PG'OCaml](http://pgocaml.forge.ocamlcore.org/) —纯OCaml中到PostgreSQL的类型安全接口.
    - [ppx_pgsql](https://github.com/tizoc/ppx_pgsql) –使用PG&#39;OCaml的嵌入式SQL查询的语法扩展.
  - [PostgreSQL-OCaml](https://mmottl.github.io/postgresql-ocaml/) —通过C API（`libpq`）到PostgreSQL的接口.
  - [SQLite3](https://github.com/mmottl/sqlite3-ocaml) — OCaml绑定到SQLite3数据库.
  - [Sqlite3EZ](https://mlin.github.io/ocaml-sqlite3EZ/) —用于SQLite3的精简包装，具有简化的界面.
  - [ocaml-redis](https://github.com/0xffea/ocaml-redis) – OCaml的Redis绑定.
  - [mysql](http://ygrek.org.ua/p/ocaml-mysql/) –绑定到libmysqlclient以与MySQL数据库交互.
  - [mysql_protocol](https://github.com/slegrand45/mysql_protocol) –使用Bitstring库实现MySQL协议.
-**新实现**
  - [Irmin](https://github.com/mirage/irmin) —遵循与Git相同的设计原则的分布式数据库.
  - [Obigstore](http://obigstore.forge.ocamlcore.org/) —在LevelDB上具有类似BigTable数据模型的数据库.
  - [RunOrg](https://github.com/RunOrg/RunOrg) -这是用OCaml编写的WIP数据库服务器.
-**叠加**
  - [Sequoia](https://github.com/andrenth/sequoia) -Sequoia是MySQL / MariaDB和PostgreSQL的类型安全查询构建器
  - [Macaque](https://github.com/ocsigen/macaque) —猕猴是使用PG&#39;OCaml之上的理解功能进行安全灵活的数据库查询的库.
  - [ORM](https://github.com/mirage/orm) — ORM for SQLite.
  - [Caqti](https://github.com/paurkedal/ocaml-caqti) -合作关系数据访问
-**文章**：
  - [Implementing the Binary Memcached Protocol with Ocaml and Bitstring](https://andreas.github.io/2014/08/22/implementing-the-binary-memcached-protocol-with-ocaml-and-bitstring/)
  - [Interfacing OCaml and PostgreSQL with Caqti](https://medium.com/@bobbypriambodo/interfacing-ocaml-and-postgresql-with-caqti-a92515bdaa11)


## Datetime

- [ISO8601](https://github.com/sagotch/ISO8601.ml)
- [calendar](http://calendar.forge.ocamlcore.org/)
- [odate](https://github.com/hhugo/odate)
- [ptime](http://erratique.ch/software/ptime)


## Developer Tools

- [Try OCaml](https://try.ocamlpro.com/) –在您的Web浏览器中尝试OCaml.
- [codingground](https://www.tutorialspoint.com/compile_ocaml_online.php) –在线编译并执行OCaml代码.
- [Jupyter](https://github.com/akabe/ocaml-jupyter) – Jupyter笔记本电脑的OCaml内核.
- [utop](https://github.com/ocaml-community/utop) – OCaml的通用顶层，支持多行版本，历史记录，实时和上下文相关的补全，颜色等.
- [ocamlformat](https://github.com/ocaml-ppx/ocamlformat) -格式化OCaml代码的命令行工具.
- [ocamlbrowser](http://caml.inria.fr/pub/docs/manual-ocaml/browser.html)  –使用LablTk编写的源代码和编译接口浏览器.  包含在ocaml &lt;= 4.01的标准发行版中，以及包含在labml&gt; = 4.02的labltk中.
- [ghim](https://github.com/samoht/ghim) –用于管理Github问题的命令行工具.
- [OCaml Yeoman Generator](https://github.com/mabrasil/generator-ocaml) –支架式OCaml模块的Yeoman发电机.

-**外部功能接口**：
  - [ctypes](https://github.com/ocamllabs/ocaml-ctypes) –用于使用纯OCaml绑定到C库的库.
  - [ocaml-main-program-in-c](https://github.com/johnwhitington/ocaml-main-program-in-c) –用于制作混合C / Ocaml二进制文件的示例构建系统，其中主程序位于C中.
  - [Modular foreign function bindings](http://openmirage.org/blog/modular-foreign-function-bindings)
  - [Py.ml](https://github.com/thierry-martinez/pyml) -适用于Python的OCaml绑定.
-**编辑器集成**：
  - [merlin](https://github.com/ocaml/merlin) – Vim和Emacs中Ocaml的上下文相关完成.
  - [tuareg](https://github.com/ocaml/tuareg) -用于Emacs的OCaml模式，可以在Emacs中运行顶层和调试器.
  - [merlin-eldoc](https://github.com/Khady/merlin-eldoc) – Emacs软件包，可通过eldoc提供merlin的功能.
  - [vscode-ocaml](https://github.com/hackwaly/vscode-ocaml) –为OCaml语言提供支持的扩展 [VSCode](https://github.com/microsoft/vscode)
  - [OCaml Debugger](https://github.com/hackwaly/ocamlearlybird) –为OCaml调试器提供扩展 [VSCode](https://github.com/microsoft/vscode)
  - [Sublime better ocaml](https://github.com/whitequark/sublime-better-ocaml) –更好的OCaml模式用于Sublime Text.
    - [Sublime text package](https://github.com/def-lkb/sublime-text-merlin)
  - [ocp-index](http://www.typerex.org/ocp-index.html)  –轻松访问已安装的OCaml库的接口信息.  提供独立工具，例如ocp-browser和ocp-grep.
    - [ocp-browser](http://www.typerex.org/ocp-index.html#ocp-browser) –小型的基于ncurses的API和文档浏览器.
    - [ocp-index-top](https://github.com/reynir/ocp-index-top) –用于使用ocp-index查找文档的顶级指令.
    - [Sublime text package](https://sublime.wbond.net/packages/OCaml%20Autocompletion)
  - [ocp-indent](http://www.typerex.org/ocp-indent.html) –用于OCaml的缩进工具，可在Emacs和Vim等编辑器中使用.
    - [Vim plugin](https://github.com/def-lkb/ocp-indent-vim).
-**代码覆盖率**：
  - [Bisect_ppx](https://github.com/aantron/bisect_ppx)


## Exercises

- [99 problems](https://ocaml.org/learn/tutorials/99problems.html) .  99％的解决方案是 [here](https://github.com/MassD/99).
- [Rosetta Code](http://rosettacode.org/wiki/Category:OCaml)
- [OCaml at Exercism](http://exercism.io/languages/ocaml)  –锻炼是您进行有关代码的深思熟虑的场所.  探索简单性，惯用语言功能和表达力强的可读代码. [Solutions](https://github.com/exercism/xocaml).


## Formal Software Verification

- [Coq](https://coq.inria.fr/)  – Coq是一个正式的证明管理系统.  它提供了一种正式的语言来编写数学定义，可执行算法和定理，以及用于半交互式开发机器检查的证明的环境.
- [Why3](http://why3.lri.fr/)  – Why3是演绎程序验证的平台.  它为规范和编程提供了一种丰富的语言，称为WhyML，并依靠自动和交互的外部定理证明者来满足验证条件.
- [Alt-Ergo](http://alt-ergo.lri.fr/) – Alt-Ergo是一个开源SMT求解器，致力于证明在程序验证的情况下生成的数学公式.


## General

- [Functional Programming with OCaml](https://haifengl.wordpress.com/2014/06/17/ocaml-introduction/)
- [Python to OCaml: retrospective](http://roscidus.com/blog/blog/2014/06/06/python-to-ocaml-retrospective/)
- [OCaml for the Masses](http://queue.acm.org/detail.cfm?id=2038036)
- [Why We Use OCaml](https://espertech.wordpress.com/2014/07/15/why-we-use-ocaml)
- [Xen – OCaml Coding Considerations](http://wiki.xen.org/wiki/OCaml_Coding_Considerations)
- [Monads are a class of hard drugs](http://lambda-diode.com/programming/monads-are-a-class-of-hard-drugs)
- [Beginner's guide to OCaml](http://blog.nullspace.io/beginners-guide-to-ocaml-beginners-guides.html)
- [Why OCaml, why now?](http://spyder.wordpress.com/2014/03/16/why-ocaml-why-now/)
- [A blog about game development in OCaml](http://cranialburnout.blogspot.ca/)
- [(Functional) Alternatives to inheritance](http://ocamltutorials.blogspot.se/2013/06/alternatives-to-subtyping.html)
- [camlPDF](https://github.com/johnwhitington/camlpdf) –用于读取，写入和修改PDF文件的OCaml库.
- [slacko](https://github.com/Leonidas-from-XIV/slacko) – OCaml中Slack的简洁界面.
- [Learn X in Y minutes](https://learnxinyminutes.com/docs/ocaml/) -其中X = OCaml.


## Graphics

-** 2D **
  - [archimedes](http://archimedes.forge.ocamlcore.org/) — 2D绘图库.
  - [cairo2](https://github.com/Chris00/ocaml-cairo)  —绑定到2D矢量图形库Cairo.  与lablgtk很好地集成.
  - [Vg](https://github.com/dbuenzli/vg) – OCaml的声明性2D矢量图形.
-** 3D **
  - [glMLite](http://www.linux-nantes.org/~fmonnier/OCaml/GL/)  — OCaml的OpenGL绑定.  提供（实验）功能性API.
  - [lablgl](https://forge.ocamlcore.org/projects/lablgl/)  — OpenGL的接口.  与lablgtk很好地集成.
  - [tgls](http://erratique.ch/software/tgls) —薄绑定OpenGL 3. {2,3}，4.{0,1,2,3,4}和OpenGL ES {2,3}.


## Internationalization

- [Camomile](https://github.com/yoriyuki/Camomile/) — OCaml的Unicode库.
- [ocaml-m17n](https://github.com/whitequark/ocaml-m17n)  — OCaml源代码的多语言化.  允许在OCaml源代码中使用Unicode标识符.
- [Uucd](https://github.com/dbuenzli/uucd) — OCaml的Unicode字符数据库解码器.
- [Uucp](https://github.com/dbuenzli/uucp) — OCaml的Unicode字符属性.
- [Uunf](https://github.com/dbuenzli/uunf) — OCaml的Unicode文本规范化.
- [Uuseg](https://github.com/dbuenzli/uuseg) — OCaml的Unicode文本分段.
- [Uutf](https://github.com/dbuenzli/uutf) —用于OCaml的非阻塞流式Unicode编解码器.


## User Interface

- [lablgtk](http://lablgtk.forge.ocamlcore.org/) — OCaml的GTK2绑定，具有各种高级功能来定义GUI.
- [lablqml](https://github.com/Kakadu/lablqml) – OCaml的QML Qt5绑定.
- [labltk](https://forge.ocamlcore.org/projects/labltk/)  — Tcl / Tk GUI框架的接口.  在ocaml &lt;= 4.01的标准发行版中.
- [TSDL](http://erratique.ch/software/tsdl) – Tsdl是OCaml模块，提供对跨平台SDL库的精简绑定.
- [Lambda-Term](https://github.com/ocaml-community/lambda-term)  – Lambda-Term是用于操作终端的跨平台库.  它提供了按键，鼠标事件，颜色以及一组用于编写类似curses的应用程序的小部件的抽象.
- [Notty](https://github.com/pqwy/notty) -Notty是OCaml的声明性终端库，围绕可组合图像的概念构建.
- [ocaml-linenoise](https://github.com/ocaml-community/ocaml-linenoise) -独立的OCaml绑定到Linenoise，OCaml中的简单高级读取行功能.


## Language-related

- [Higher-Rank Polymorphism in OCaml](http://devmusings.legiasoft.com/blog/2008/05/23/higher-rank_polymorphism_in_ocaml)
- [mikmatch](https://github.com/mjambon/mikmatch) – OCaml模式匹配使用正则表达式扩展
- [Inlined records in constructors](https://www.lexifi.com/ocaml/inlined-records-constructors/)
- [Algebraic Data Types](https://espertech.wordpress.com/2014/07/30/algebraic-data-types/)
- [XEN – OCaml Best Practices for Developers](http://wiki.xen.org/wiki/OCaml_Best_Practices_for_Developers)
- [OCaml Style Guide (by Jane Street)](https://opensource.janestreet.com/standards/) -另请参见：[[1]]（https://www.seas.upenn.edu/~cis500/cis500-f06/resources/programming_style.html），[[2]]（http：//www.cs. cornell.edu/Courses/cs312/2001sp/style.html)，[[3]](https://www.seas.upenn.edu/~cis120/current/programming_style.shtml）.
- [A safe but strange way of modifying OCaml compiler](https://bitbucket.org/camlspotter/compiler-libs-hack)
- [Fiddling with the OCaml Type System](https://technotroph.wordpress.com/2013/10/25/fiddling-with-the-ocaml-type-system/)


## Logging

- [dolog](https://github.com/UnixJunkie/dolog) –愚蠢的OCaml记录器.
- [Volt](https://github.com/codinuum/volt) – Bolt OCaml日志记录工具的变体.
- [Logs](http://erratique.ch/software/logs) -日志为OCaml提供了日志记录基础结构.

## Machine Learning

-**图书馆**
	- [Owl](https://ocaml.xyz/) -具有神经网络，算法差异化和ONNX支持的科学图书馆.
	- [Object detection convolutional neural network with OCaml (based on Owl)](https://github.com/owlbarn/owl_mask_rcnn).
	- [PyTorch bindings](https://github.com/LaurentMazare/ocaml-torch) -PyTorch的OCaml绑定.
-**文章**
	- [Deep Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/deep-learning-experiments-in-ocaml/).
	- [Transfer Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/of-pythons-and-camels/).
	- [Reinforcement Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/playing-atari-games-with-ocaml-and-deep-rl/).

## Messaging

- [ocaml-zmq](https://github.com/issuu/ocaml-zmq) –具有异步和Lwt包装器的OCaml的ZeroMQ绑定.
- [onanomsg](https://github.com/rgrinberg/onanomsg) – OCaml的nanomsg绑定.
- [Kafka](https://github.com/didier-wenzek/ocaml-kafka) – Apache Kafka的OCaml绑定.
- [AMQP](https://github.com/andersfugmann/amqp-client) –用于异步和Lwt的AMQP客户端库.
- [MPI](https://github.com/xavierleroy/ocamlmpi) – OCaml的消息传递接口绑定.
- [MQTT](https://github.com/j0sh/ocaml-mqtt) – MQTT pubsub协议的OCaml实现.
- [capnp-ocaml](https://github.com/capnproto/capnp-ocaml) – Cap&#39;n Proto序列化框架的OCaml代码生成器插件.

## Metaprogramming

-**文章**：
  - [A Guide to Extension Points in OCaml](http://whitequark.org/blog/2014/04/16/a-guide-to-extension-points-in-ocaml/)
  - [Extension Points, or how OCaml is becoming more like Lisp](https://blogs.janestreet.com/extension-points-or-how-ocaml-is-becoming-more-like-lisp)
  - [Syntax extensions without Camlp4: let's do it!](https://www.lexifi.com/ocaml/syntax-extensions-without-camlp4-lets-do-it/)
  - [Reading Camlp4 – Ambassador to the Computers](https://ambassadortothecomputers.blogspot.com/p/reading-camlp4.html)
-**语法扩展**：
  - [ppx_import](https://github.com/ocaml-ppx/ppx_import) –导入是一种语法扩展，它允许从其他已编译的接口文件中提取类型或签名.
  - [ppx_string_interpolate](https://github.com/sheijk/ppx_string_interpolate) –一个简单的ppx过滤器，用于支持字符串插值，例如`[％str“ foo的值为$（foo）”]`.
  - [ppx_monad](https://github.com/rizo/ppx_monad) – OCaml的Monad语法扩展.
  - [ppx_deriving_yojson](https://github.com/whitequark/ppx_deriving_yojson) –用于OCaml的Yojson编解码器生成器.
-**工具和语言扩展**：
  - [MetaOCaml](http://okmij.org/ftp/ML/MetaOCaml.html) –用于多阶段编程的OCaml方言.
  - [Fan](http://zhanghongbo.me/fan/)  – Fan是OCaml的编译时元编程系统，其最初灵感来自Camlp4.  它是OCaml和Lispy宏的组合.  它与OCaml共享相同的具体语法.
  - [camlp5](https://camlp5.github.io/) -Camlp5是OCaml的预处理器漂亮打印机.
  - [camlp4](http://caml.inria.fr/pub/docs/manual-camlp4/manual002.html) -Camlp4是标准OCaml发行版的一部分，与Camlp5不同.

## Metrics

- [prometheus](https://github.com/mirage/prometheus) –用于Prometheus监控的OCaml客户端库.

## Mobile Applications

-**文章**：
  - [OCaml on iOS 7 Released](http://psellos.com/2014/08/2014.08.ocamlxarm-402.html)
  - [OCaml + Cordova = more secured, typed and hybrid mobile applications](https://blog.danny-willems.be/en/ocaml-cordova-secured-typed-hybrid-mobile-applications/)
-**绑定**：
  - [Cordova plugins](https://github.com/dannywillems/ocaml-cordova-plugin-list)  – Cordova插件的绑定列表.  可以访问OCaml中的本机设备组件，如加速度计，SMS，地理位置等.


## Networking

-** HTTP工具**：
  - [ocaml-cohttp](https://github.com/mirage/ocaml-cohttp) –使用Lwt或Async的非常轻量级的HTTP服务器.
  - [ocurl](https://github.com/ygrek/ocurl) – OCaml绑定到libcurl.
  - [httpaf](https://github.com/inhabitedtype/httpaf) –用OCaml编写的高性能，内存高效且可扩展的Web服务器.
- [ocaml-dns](https://github.com/mirage/ocaml-dns) – DNS协议的纯OCaml实现.
- [fluent-logger](https://github.com/fluent/fluent-logger-ocaml) – OCaml的流畅记录器.
- [charrua-unix](https://github.com/haesbaert/charrua-unix) -charrua-unix是基于以下内容的Unix DHCP守护程序 [charrua-core](https://github.com/haesbaert/charrua-core).


## Online Courses

- [Introduction to Functional Programming in OCaml](https://www.fun-mooc.fr/courses/parisdiderot/56002S02/session02/about).
- [Cornell University – Data Structures and Functional Programming](http://www.cs.cornell.edu/Courses/cs3110/2014fa/course_info.php).
- [Princeton University - Functional programming in OCaml](http://www.cs.princeton.edu/~dpw/courses/cos326-12/).
- [University of Illinois](https://courses.engr.illinois.edu/cs421/fa2014/) -使用OCaml教授功能编程和编程语言设计的课程


## Package Management
-**分布**：
  - [OPAM](http://opam.ocamlpro.com/) –具有多种编译器支持的灵活的Git友好软件包管理器.
  - [ocamlfind](http://projects.camlcity.org/projects/findlib.html)  —本地OCaml库管理器.  被大多数OCaml生态系统使用.
  - [OCaml for Windows](https://fdopen.github.io/opam-repository-mingw) -适用于Windows的opam存储库和实验版本.
  - [makorel](https://github.com/sagotch/makorel) –轻松发布OPAM软件包.
  - [esy](https://github.com/esy/esy) -用于使用Reason / OCaml进行本机开发的package.json工作流程.

-**构建工具**：
  - [Oasis](http://oasis.forge.ocamlcore.org/)  -在OCaml项目中集成配置，构建和安装系统的工具.  它有助于在构建系统中创建标准入口点，并允许外部工具轻松分析项目.
    - [oasis2opam](https://github.com/ocaml/oasis2opam) —用于将OASIS元数据转换为OPAM软件包描述的工具.
  - [obuild](https://github.com/ocaml-obuild/obuild) –简单的ocaml软件包构建系统.
  - [dune](https://github.com/ocaml/dune) –用于OCaml的可组合且自以为是的构建系统（以前的jbuilder）
  - [jenga](https://github.com/janestreet/jenga) – Jane Street的Monadic构建系统.
  - [ocamlbuild](http://ocaml.org/learn/tutorials/ocamlbuild/) —编译器随附的构建系统.
  - [ocaml-makefile](https://github.com/mmottl/ocaml-makefile) —适用于中小型OCaml项目的易于使用的Makefile.
  - [topkg](https://github.com/dbuenzli/topkg) —使用ocamlbuild的可识别OPAM的包装系统.
  - [Namespaces](https://github.com/aantron/namespaces) -ocamlbuild插件，可将您的目录树转换为嵌套模块.
  - [Bazel](https://github.com/jin/rules_ocaml) - OCaml rules for [Bazel](https://bazel.build/)，这是Google的多语言和平台构建工具.

## Parallelism

（_注意：从易于使用到更灵活地排序._）

-**图书馆**：
  - [Parmap](http://rdicosmo.github.io/parmap/) —提供易于使用的并行地图和折叠功能.
  - [ForkWork](https://github.com/mlin/forkwork) —一个简单的库，用于派生子进程以在多个内核上执行工作.
  - [Functory](http://functory.lri.fr/About.html) —分布式计算库，以无缝方式促进可并行计算的分布式执行.
  - [Rpc.Parallel](https://github.com/janestreet/rpc_parallel) —一个库，用于在机器集群上生成进程，并在它们之间传递键入的消息.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html)  —增强的系统平台库.  包含“ netmulticore”库，可根据需要在计算机的多个内核上计算任务.
  - [Nproc](https://github.com/MyLifeLabs/nproc) – OCaml的过程池实现.
  - [Parany](https://github.com/UnixJunkie/parany) –对独立项目进行并行计算，即使它们数量不限也是如此.
  - [Sklml](http://sklml.inria.fr) –用于OCaml程序的功能性并行骨架编译器和编程系统.
  - [SPOC](https://github.com/mathiasbourgoin/SPOC) -库和语法扩展，可将大量计算任务卸载到并行加速器（多核CPU，GPU和与GPGPU框架兼容的其他加速器）中.

-**文章**：
  - [What is the state of OCaml's parallelization abilities?](https://stackoverflow.com/questions/6588500/what-is-the-state-of-ocamls-parallelization-abilities)


## Questions

- [OCaml polymorphism example other than template function?](https://stackoverflow.com/questions/14440531/ocaml-polymorphism-example-other-than-template-function)
- [OCaml - polymorphic print and type losing](https://stackoverflow.com/questions/7442449/ocaml-polymorphic-print-and-type-losing)


## Science and Technical Computing

- [biocaml](https://github.com/biocaml/biocaml)  – OCaml生物信息学图书馆 <http://biocaml.org>  .
- [guizmin](https://github.com/pveber/guizmin) –用于建立生物信息学管道的OCaml库.
- [lacaml](https://mmottl.github.io/lacaml/) -用于BLAS / LAPACK的OCaml绑定（高性能线性代数Fortran库）.
- [obandit](http://freux.fr/oss/obandit.html) - OCaml library for multi-armed bandits.
- [onumerical](https://github.com/cheshire/onumerical) – OCaml的数字库.
- [oml](https://github.com/hammerlab/oml) -用于一般数值工作的OCaml库.
- [ocephes](https://github.com/rleonid/ocephes) -绑定到常用的`C`特殊函数库.
- [slap](https://github.com/akabe/slap) -OCaml中的线性代数库，具有用于矩阵运算的基于类型的静态大小检查.
- [tensorflow-ocaml](https://github.com/LaurentMazare/tensorflow-ocaml) – TensorFlow的OCaml绑定.
- [owl](https://github.com/owlbarn/owl) -OCaml数值库：密集和稀疏矩阵，线性代数，回归，数学和统计函数.


## Regular Expressions

- [Re](https://github.com/ocaml/ocaml-re) –具有合并器的纯OCaml正则表达式库，支持多种格式（glob，posix，str ...）
- [ocaml-pcre](https://github.com/mmottl/pcre-ocaml) –绑定到PCRE库（与perl兼容的正则表达式）
- [Humane-re](https://github.com/rgrinberg/humane-re) –人性化的尝试为90％的正则表达式提供简单的界面感谢ocaml-re
- [Tyre](https://github.com/Drup/tyre) -Tire是一组组合器，用于构建类型安全的正则表达式，从而允许自动提取和修改匹配的组.


## Security and Cryptography

- [ocaml-tls](https://github.com/mirleft/ocaml-tls) –纯OCaml中的T​​LS.
- [Digestif](https://github.com/mirage/digestif) -OCaml和C中的哈希算法（例如SHA *或BLAKE2 *）.
- [cryptokit](https://github.com/xavierleroy/cryptokit) –用于OCaml的Cryptokit库提供了多种加密原语，可用于在对安全敏感的应用程序中实现加密协议.
- [nocoiner](https://github.com/marcoonroad/nocoiner) -用于多方计算（例如在线拍卖和赌博）的承诺计划库.
- [nocrypto](https://github.com/mirleft/ocaml-nocrypto)  – ocaml-tls项目背后的小型加密库.  它被构建为易于使用，遵循功能性编程原则并且能够在基于Xen的unikernel中运行.

&gt;注意：以下博客文章中描述了nocrypto库和cryptookit加密库之间的区别： [OCaml-TLS: building the nocrypto library core](https://mirage.io/blog/introducing-nocrypto).


## Semantic Technology

- [OCaml-RDF](https://framagit.org/zoggy/ocaml-rdf) – OCaml库，用于处理RDF图和执行Sparql查询.


## Serialization

- [bencode](https://github.com/rgrinberg/bencode) — Bencode（.torrent文件格式）读取器/写入器.
- [biniou](https://github.com/mjambon/biniou) –可扩展的二进制数据格式，例如JSON，但速度更快.
- [jsonm](http://erratique.ch/software/jsonm) —用于OCaml的非阻塞流JSON编解码器.
- [xmlm](http://erratique.ch/software/xmlm) —用于解码和编码XML数据格式的流编解码器.
- [yojson](https://github.com/ocaml-community/yojson) —针对JSON格式的优化的分析和打印库.
- [sexplib](https://github.com/janestreet/sexplib) – S表达式解析器和打印机


## System Programming

- [Mirage OS](https://github.com/mirage/mirage) – Mirage是一个编程框架，用于跨各种云计算和移动平台构建安全的高性能网络应用程序.
- [ocaml-fat](https://github.com/mirage/ocaml-fat) –从OCaml读写FAT格式的文件系统.
- [ocaml-git](https://github.com/mirage/ocaml-git) –纯OCaml低级git绑定.
- [ocaml-vchan](https://github.com/mirage/ocaml-vchan) –“ vchan”共享内存通信协议的纯OCaml实现.

- **嵌入式系统**
  - [OMicroB](https://github.com/stevenvar/omicrob) -设计用于在AVR（例如Arduino）微控制器上运行OCaml字节码的虚拟机.
  - [OCaPIC](http://www.algo-prog.info/ocapic/web/index.php?id=OCAPIC:OCAPIC) -用于PIC18单片机的OCaml虚拟机.
  - [ocaml-esp32](https://github.com/sadiqj/ocaml-esp32) -用于ESP32 SoC的编译器.


## Testing

- [Alcotest](https://github.com/mirage/alcotest) –轻巧而丰富多彩的测试框架.
- [OUnit](http://ounit.forge.ocamlcore.org/)  – OUnit是OCaml的单元测试框架.  它使人们可以轻松地为OCaml代码创建单元测试.  它基于HUnit，这是Haskell的单元测试框架.
- [QCheck](https://github.com/c-cube/qcheck) — QCheck是一个受Haskell QuickCheck启发的属性测试库
- [iTeML](https://github.com/vincent-hugot/iTeML) （原名 [qtest](http://batteries.vhugot.com/qtest/)）-支持内联编译指示生成测试.
- [Kaputt](http://kaputt.x9c.fr/) —全面的测试框架.
- [Pa_test](https://ocaml.janestreet.com/ocaml-core/111.28.00/doc/pa_test) —常规的在线测试宏.
- [TestSimple](https://github.com/hcarty/ocaml-testsimple) -与 [Test Anything Protocol](https://testanything.org/).


## Utilities

- [ocaml-cuid](https://github.com/marcoonroad/ocaml-cuid) -用于服务器可伸缩性和数据库性能的防冲突ID.


## Web Development

- **构架**：
  - [Opium](https://github.com/rgrinberg/opium) – Sinatra像OCaml的网络工具包.
  - [Ocsigen Eliom](http://ocsigen.org/eliom/)  – Eliom是功能全面的多层框架，用于将多平台Web和移动应用程序开发为100％OCaml分布式应用程序.  它也可以用于更传统的Web或移动应用程序：网站，单页应用程序，REST API等.
  - [webmachine](https://github.com/inhabitedtype/ocaml-webmachine)  –用于OCaml的REST工具包.  OCaml Web机是cohttp之上的一层，它实现了基于状态机的HTTP请求处理器.  它特别适合编写RESTful API.  顾名思义，这是Webmachine项目的OCaml端口.
  - [incr_dom](https://github.com/janestreet/incr_dom) -使用Js_of_ocaml构建动态Web应用程序的库
  - [ocaml-vdom](https://github.com/LexiFi/ocaml-vdom) -Elm架构和OCaml的（V）DOM

-**工具**：
  - [COW](https://github.com/mirage/ocaml-cow) – Web上的Caml（COW）是一组解析器和语法扩展，可让您直接从OCaml代码中操作HTML，CSS，XML，JSON和Markdown.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html)
    有许多相关的网络库-
    [Nethtml](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Nethtml.html)
    html解析器
    [Netasn1](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netasn1.html)
    对于ASN.1解析，
    [Netencoding](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netencoding.html)
    对于Base64，带引号的可打印内容，URL编码和HTML转义，
    [Netmime](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netmime.html)
    用于MIME处理等.请参见[
    modules](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/index.html)
    在Ocamlnet的手册中.
  - [tyxml](http://ocsigen.org/tyxml) —用于构建有效的（根据W3C规范）Html和Svg树的库.
  - [js_of_ocaml](http://ocsigen.org/js_of_ocaml)  – Js_of_ocaml是OCaml字节码到Javascript的编译器.  这样就可以在Web浏览器中运行Ocaml程序.
    - [commonjs_of_ocaml](https://github.com/AngryLawyer/commonjs_of_ocaml) -从js_of_ocaml项目轻松导入和导出CommonJS模块.
  - [BuckleScript](https://github.com/bloomberg/bucklescript)  -BuckleScript是OCaml的后端，可生成可调试的Javascript.  它使OCaml能够无缝集成Java平台.
  - [ocaml-uri](https://github.com/mirage/ocaml-uri) – RFC3986 URI解析库.
  - [Goji](https://github.com/klakplok/goji) –用于JavaScript库的OCaml绑定生成器.
  - [Syndic](https://github.com/Cumulus/Syndic) – RSS和Atom提要解析
  - [ocaml-mustache](https://github.com/rgrinberg/ocaml-mustache) – OCaml中的mustache.js无逻辑模板.
  - [atdjs](https://github.com/barko/atdjs) –用于OCaml / js_of_ocaml的atd代码生成器.
  - [jingoo](https://github.com/tategakibunko/jingoo) – OCaml模板引擎几乎与jinja2兼容.
  - [dispatch](https://github.com/inhabitedtype/ocaml-dispatch) – Path-based dispatching for client- and server-side applications.
  - [Lambda Soup](https://github.com/aantron/lambda-soup) -使用CSS选择器进行功能性HTML抓取和操作，如Python的Beautiful Soup.
  - [Markup.ml](https://github.com/aantron/markup.ml) -错误恢复流HTML5和XML解析器，序列化器.
  - [gen_js_api](https://github.com/LexiFi/gen_js_api) -gen_js_api旨在简化Java库的OCaml绑定的创建.
  - [routes](https://github.com/anuragsoni/routes) -OCaml / ReasonML Web应用程序的类型化路由.

-**开源项目**：
  - [Cumulus](https://github.com/Cumulus/Cumulus) –带有OCaml框架Ocsigen的黑客新闻（如网站）

* * *

 _受到很棒的项目线的启发.  发现 [more awesomeness](https://github.com/bayandin/awesome-awesomeness) ：sparkles：._
