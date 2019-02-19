<div class="github-widget" data-repo="ocaml-community/awesome-ocaml"></div>
令人敬畏的OCaml [![Build Status](https://travis-ci.org/ocaml-community/awesome-ocaml.svg?branch=master)](https://travis-ci.org/rizo/awesome-ocaml)
=============

<img src="https://raw.githubusercontent.com/ocaml-community/awesome-ocaml/master/colour-logo.png" width="70%" />

&gt; _ **在掌握OCaml的道路上你将需要的一切.** _

 精选OCaml工具，框架，库和文章的精选列表.  此外，还有一系列免费提供 [**books**](https://github.com/rizo/awesome-ocaml/tree/master/books), [**papers**](https://github.com/rizo/awesome-ocaml/tree/master/papers) 和 [**presentations**](https://github.com/rizo/awesome-ocaml/tree/master/presentations).

如果您正在寻找有关OCaml访问的全面的社区驱动内容 [OCamlverse](https://ocamlverse.github.io/)!

要快速了解现代OCaml开发工作流程，请咨询 [**OCaml for the impatient**](https://adambard.com/blog/getting-started-with-ocaml/) 指南.

 你最喜欢的包没有列出？  叉子和 [create a Pull Request](https://github.com/rizo/awesome-ocaml/edit/master/README.md) 添加它！



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
- [OCamlgraph](https://github.com/backtracking/ocamlgraph) -  OCaml的通用图库.
- [ods](https://github.com/owainlewis/ods) -  OCaml的大量数据结构和算法.
- [combine](https://github.com/backtracking/combine)   - 用于组合学的OCaml库 <https://www.lri.fr/~filliatr/combine/>  .
- [Decompress](https://github.com/mirage/decompress) -  Zlib的纯OCaml实现.
- [Ke](https://github.com/mirage/ke) - 在OCaml中快速实现队列（FIFO）.
- [Duff](https://github.com/mirage/duff) - 由P. MacDonald在OCaml中实施Rabin的指纹和delta压缩（与...相同） [libXdiff](http://www.xmailserver.org/xdiff-lib.html)


## Application Libraries

- [Batteries Included](https://github.com/ocaml-batteries-team/batteries-included) - 为您的OCaml项目提供社区维护的基础库.
- [Cmdliner](https://github.com/dbuenzli/cmdliner) -  OCaml的命令行接口的声明性定义.
- [Core](https://github.com/janestreet/core)   -  Jane Street Capital完整的标准库叠加层.  还提供可移植的Core子集： [Core_kernel](https://github.com/janestreet/core_kernel).
- [Base](https://github.com/janestreet/base) -  Jane Street Capital的无依赖性，快速编译，可在任何可运行OCaml代码标准库的环境中完全移植.
- [React](http://erratique.ch/software/react)   -  React是用于功能反应式编程（FRP）的OCaml模块.  它为具有时变值的程序提供支持：声明性事件和信号.
- [Minicli](https://github.com/UnixJunkie/minicli) - 用于命令行解析的极简主义库.
- [easy-format](https://github.com/mjambon/easy-format) -  OCaml的漂亮打印库.
- [ocaml-rpc](https://github.com/mirage/ocaml-rpc) - 用于处理OCaml中的RPC的轻型库.
- [ocaml-containers](https://github.com/c-cube/ocaml-containers)   - 轻量级，模块化标准库扩展，字符串库和各种库（bigarrays，unix等等）的接口.  BSD许可证.


## Benchmarking

- [core_bench](https://github.com/janestreet/core_bench) -  Jane Street的OCaml微基准测试库.
  - [Getting Started with Core_bench](https://github.com/janestreet/core_bench/wiki/Getting-Started-with-Core_bench)
- [benchmark](https://github.com/Chris00/ocaml-benchmark) - 基准测试功能，用于使用延迟或吞吐量测量功能的运行时间.


## Blogs

- [Gagallium](http://gallium.inria.fr/blog/)
- [Type OCaml – Many things about OCaml](http://typeocaml.com/)
- [OCaml Platform](https://opam.ocaml.org/blog/)
- [Drup's Thingies](https://drup.github.io/)

## Books

- [More OCaml: Algorithms, Methods, and Diversions](https://www.amazon.com/More-OCaml-Algorithms-Methods-Diversions/dp/0957671113/)   - 在更多OCaml中，John Whitington使用OCaml进行了函数式编程的蜿蜒之旅，介绍了各种语言特性并描述了一些经典算法.  本书以一个处理PDF文件生成的大型工作示例结束.  每章都有问题以及有效的答案和提示.
- [How to Think Like a (Functional) Programmer](http://www.greenteapress.com/thinkocaml/index.html)  作者：Allen Downey和Nicholas Monje  - 如何像计算机一样思考科学家是一本基于OCaml语言的入门编程教科书.  它是Allen Downey对Think Python的修改版本.  它适用于新手编程，也适合那些了解某些编程但希望学习面向函数范式编程的人，或者那些只想学习OCaml的人.
- [OCaml from the Very Beginning](http://ocaml-book.com/) 作者：J.Whitington  - 来自Very Beginning的OCaml将吸引新的程序员和有经验的程序员，他们渴望探索OCaml等功能语言.
- [Pearls of Functional Algorithm Design](https://www.amazon.co.uk/Pearls-Functional-Algorithm-Design-Richard/dp/0521513383) by Richard Bird - It summaries 30 hard algorithm problems in function programming world. Although it is for Haskell, the algorithm problems are very interesting and trying to solve them in OCaml also helps the thinking of functional programming. Partial solutions in OCaml are [here](https://github.com/MassD/pearls).
- [Real World OCaml](https://realworldocaml.org/) 由Y. Minsky，A.Madhavapeddy和J. Hickey撰写 - 为群众提供功能性编程.
- [Unix System Programming in OCaml](https://ocaml.github.io/ocamlunix/) 由X. Leroy和D.Rémy撰写 - 介绍Unix系统编程，重点介绍进程之间的通信.
- [Using, Understanding, and Unraveling OCaml](https://caml.inria.fr/pub/docs/u3-ocaml) - 本书描述了OCaml语言及其强大类型系统背后的理论基础.
- [Purely Functional Data Structures](https://www.amazon.co.uk/Purely-Functional-Structures-Chris-Okasaki/dp/0521631246/ref=sr_1_1?ie=UTF8&qid=1406279836&sr=8-1&keywords=functional+data+structures)   - 这是第一本或唯一一本关注FP世界中各种数据结构的书.  一个必读的.
- [OCaml for Scientists](http://www.ffconsultancy.com/products/ocaml_for_scientists/) -  Jon Harrop.
- [Functional Programming in OCaml: A Principled Approach](http://www.cs.cornell.edu/courses/cs3110/2018fa/textbook/) - 康奈尔大学CS 3110数据结构和功能编程教材.



## Code Analysis and Linters

- [Mascot](http://mascot.x9c.fr/) -  Mascot是OCaml来源的风格检查员
- [pfff](https://github.com/facebook/pfff) -  pfff是一组工具和API，用于执行一些静态分析，动态分析，代码可视化，代码导航或样式保留源到源转换，例如对源代码的重构.
- [Infer](https://github.com/facebook/infer) - 推断是Java，C和Objective-C的静态分析器
- [Frama-C](http://frama-c.com) -  Frama-C是C和C ++的静态分析和形式证明框架
- [flow](https://github.com/facebook/flow) -  flow是JavaScript的静态类型检查器
- [Ocamllint](https://github.com/cryptosense/ocamllint) -  Ocamllint检测OCaml代码中的常见错误
- [BetterErrors](https://github.com/npm-ml/BetterErrors) -  BetterErrors改进了OCaml编译器的错误消息（使OCaml错误再次发生.）
- [SLAyer](https://github.com/Microsoft/SLAyer) -  SLAyer是一种自动形式验证工具，它使用分离逻辑来验证C程序的内存安全性.
- [MemCAD](https://github.com/Antique-team/memcad)   -  MemCAD是一种用于形状分析的抽象解释器.  MemCAD可以验证C程序操纵复杂的数据结构.

## Program analysis
- [BAP](https://github.com/BinaryAnalysisPlatform/bap) -  BAP是一个针对二进制程序的逆向工程和程序分析平台.
- [BinCat](https://github.com/airbus-seclab/bincat) -  BinCat是一个二进制代码静态分析工具包.

## Compilers and Compiler Tools

-  **语言和编译器**：
  - [cDuce](http://www.cduce.org/) -  cDuce是一种现代的面向XML的功能语言，具有创新功能.
  - [Compcert C Compiler](http://compcert.inria.fr/) - 它是一个C编译器，支持大多数ISO C90和C99 / ANSI C功能.
  - [Eff Programming Language](http://www.eff-lang.org/) -  Eff是一种函数式语言，不仅具有异常处理程序，还具有其他计算效果（如状态或I / O）的处理程序.
  - [Hack Programming Language](https://hacklang.org/)
  - [Haxe Programming Language](https://haxe.org/)
  - [Neko Programming Language](https://nekovm.org/) - 最初编译器是用OCaml编写的.
  - [Mezzo Programming Language](https://protz.github.io/mezzo/) -  Mezzo是ML传统中的一种编程语言，它强调控制别名和访问可变内存.
  - [OCaml-Java](http://www.ocamljava.org/) -  OCaml到Java字节码编译器.
  - [Opa Programming Language](http://opalang.org/)
  - [Rhine](https://github.com/artagnon/rhine-ml) - 用OCaml编写的LLVM上的Lisp.
  - [Rust Programming Language](https://www.rust-lang.org/) - 最初在引导之前用OCaml编写.
  - [Quick C-- Target Language](http://www.cminusminus.org/) - 现在这是一个死的项目. [Github Repo](https://github.com/nrnrnr/qc--). [Alternative website](http://www.cs.tufts.edu/~nr/c--/qc--.html).
  - [tis-interpreter](https://github.com/TrustInSoft/tis-interpreter) - 用于在标准C中编写的程序中发现细微错误的解释器

  - [Reason](http://facebook.github.io/reason/) -  Facebook的OCaml友好语法和工具链.
  - [RaML](http://raml.co/index.html) - 资源感知ML（RaML）是一种自动和静态计算OCaml程序的资源使用边界的工具.

-  **解析器和Lexer生成器**：
  - [Opal](https://github.com/pyrocat101/opal) - 用于OCaml的独立monadic解析器组合器.
  - [Sedlex](https://github.com/ocaml-community/sedlex) 是一个现代的，编码不可知的（读取：支持Unicode的）词法分析器生成器（基于ppx的后继者） [ulex](http://www.cduce.org/download.html#side).)
  - [Menhir](http://gallium.inria.fr/~fpottier/menhir/) --Menhir是OCaml的LR（1）解析器生成器.
    - 见 [ocaml-parsing](https://github.com/smolkaj/ocaml-parsing) 有关使用Menhir和Sedlex生成有用解析器的更清晰示例，
    -  ......和 [Obelisk](https://github.com/Lelio-Brun/Obelisk)，一个简洁的项目，为您的语法生成可读的LaTeX，HTML或纯文本EBNF风格的文档.
  - [ocamllex/ocamlyacc](http://caml.inria.fr/pub/docs/manual-ocaml-4.01/lexyacc.html) -  OCaml的lex和yacc实现.
  - [Angstrom](https://github.com/inhabitedtype/angstrom) - 用于速度和内存效率的分析器组合器
-  **文章**：
  - [Kaleidoscope: Implementing a Language with LLVM in Objective Caml¶](http://llvm.org/docs/tutorial/OCamlLangImpl1.html)


## Concurrency

 OCaml中存在两个并发库：_Lwt_和_Async_.  它们提供了非常相似的功能，但在错误处理和内部实现细节方面做出了截然不同的决定（有关详细信息，请参阅下面的链接）. [Real World OCaml](https://realworldocaml.org/) 使用Async但是版本 [code examples translated to Lwt](https://github.com/dkim/rwo-lwt) is also available.

-  **图书馆**：
  - [Lwt](http://ocsigen.org/lwt/) -  OCaml的协作线程库.
  - [Async](http://janestreet.github.io/) - 与核心库一起使用的monadic并发库.
-  **文章**：
  - [The blog post that introduced Async](https://blog.janestreet.com/announcing-async/)
  - [A user gives up on Async](http://rgrinberg.com/posts/abandoning-async/)
  - [Cooperative Concurrency in OCaml: A Core.Std.Async Example](http://philtomson.github.io/blog/2014/07/09/core-dot-async-example/).

还有一个正在进行的实验项目，以使OCaml多处理器和多核感知 [OCaml multicore](https://github.com/ocamllabs/ocaml-multicore) 叉子.

## Databases

-  **绑定**
  - [Dbm](https://forge.ocamlcore.org/projects/camldbm/) - 绑定到NDBM / GDBM Unix“数据库”.
  - [Mongo.ml](https://massd.github.io/mongo/) -  Mongodb的OCaml驱动程序
  - [PG'OCaml](http://pgocaml.forge.ocamlcore.org/) - 纯OCaml中PostgreSQL的类型安全接口.
    - [ppx_pgsql](https://github.com/tizoc/ppx_pgsql) - 使用PG&#39;OCaml的嵌入式SQL查询的语法扩展.
  - [PostgreSQL-OCaml](https://mmottl.github.io/postgresql-ocaml/) - 通过C API（`libpq`）到PostgreSQL的接口.
  - [SQLite3](https://github.com/mmottl/sqlite3-ocaml) -  OCaml绑定到SQLite3数据库.
  - [Sqlite3EZ](https://mlin.github.io/ocaml-sqlite3EZ/) -  SQLite3的瘦包装器，具有简化的界面.
  - [ocaml-redis](https://github.com/0xffea/ocaml-redis) -  OCaml的Redis绑定.
  - [mysql](http://ygrek.org.ua/p/ocaml-mysql/) - 绑定到libmysqlclient以与MySQL数据库交互.
  - [mysql_protocol](https://github.com/slegrand45/mysql_protocol) - 使用Bitstring库实现MySQL协议.
-  **新实施**
  - [Irmin](https://github.com/mirage/irmin) - 遵循与Git相同的设计原则的分布式数据库.
  - [Obigstore](http://obigstore.forge.ocamlcore.org/) -  LevelDB上具有类似BigTable的数据模型的数据库.
  - [RunOrg](https://github.com/RunOrg/RunOrg) - 它是用OCaml编写的WIP数据库服务器.
-  **叠加**
  - [Sequoia](https://github.com/andrenth/sequoia) -  Sequoia是MySQL / MariaDB和PostgreSQL的类型安全查询构建器
  - [Macaque](https://github.com/ocsigen/macaque) - 使用PG&#39;OCaml之上的理解，Macaque是一个安全灵活的数据库查询库.
  - [ORM](https://github.com/mirage/orm) -  SQLite的ORM.
  - [Caqti](https://github.com/paurkedal/ocaml-caqti) - 对关系数据的协作线程访问
-  **文章**：
  - [Implementing the Binary Memcached Protocol with Ocaml and Bitstring](https://andreas.github.io/2014/08/22/implementing-the-binary-memcached-protocol-with-ocaml-and-bitstring/)
  - [Interfacing OCaml and PostgreSQL with Caqti](https://medium.com/@bobbypriambodo/interfacing-ocaml-and-postgresql-with-caqti-a92515bdaa11)


## Datetime

- [ISO8601](https://github.com/sagotch/ISO8601.ml)
- [calendar](http://calendar.forge.ocamlcore.org/)
- [odate](https://github.com/hhugo/odate)
- [ptime](http://erratique.ch/software/ptime)


## Developer Tools

- [Try OCaml](https://try.ocamlpro.com/) - 在Web浏览器中尝试OCaml.
- [codingground](https://www.tutorialspoint.com/compile_ocaml_online.php) - 在线编译和执行OCaml代码.
- [Jupyter](https://github.com/akabe/ocaml-jupyter) -  Jupyter笔记本的OCaml内核.
- [utop](https://github.com/ocaml-community/utop) -  OCaml的通用顶级支持，支持多行版本，历史记录，实时和上下文相关的完成，颜色等.
- [ocamlformat](https://github.com/ocaml-ppx/ocamlformat) - 用于格式化OCaml代码的命令行工具.
- [ocamlbrowser](http://caml.inria.fr/pub/docs/manual-ocaml/browser.html)   - 使用LablTk编写的源代码和编译界面浏览器.  包含在ocaml &lt;= 4.01和labltk for ocaml&gt; = 4.02的标准分布中.
- [ghim](https://github.com/samoht/ghim) - 用于管理Github问题的命令行工具.
- [OCaml Yeoman Generator](https://github.com/mabrasil/generator-ocaml) -  Yeoman发电机支架OCaml模块.

-  **外部函数接口**：
  - [ctypes](https://github.com/ocamllabs/ocaml-ctypes) - 使用纯OCaml绑定到C库的库.
  - [ocaml-main-program-in-c](https://github.com/johnwhitington/ocaml-main-program-in-c) - 用于制作混合C / Ocaml二进制文件的示例构建系统，其中主程序位于C中.
  - [Modular foreign function bindings](http://openmirage.org/blog/modular-foreign-function-bindings)
  - [Py.ml](https://github.com/thierry-martinez/pyml) - 用于Python的OCaml绑定.
-  **编辑整合**：
  - [merlin](https://github.com/ocaml/merlin) -  Vim和Emacs中Ocaml的上下文敏感完成.
  - [tuareg](https://github.com/ocaml/tuareg) -  Emacs的OCaml模式，可以在Emacs中运行顶层和调试器.
  - [merlin-eldoc](https://github.com/Khady/merlin-eldoc) -  Emacs包通过eldoc提供merlin的功能.
  - [vscode-ocaml](https://github.com/hackwaly/vscode-ocaml) - 提供OCaml语言支持的扩展 [VSCode](https://github.com/microsoft/vscode)
  - [OCaml Debugger](https://github.com/hackwaly/ocamlearlybird) - 为OCaml调试器提供的扩展 [VSCode](https://github.com/microsoft/vscode)
  - [Sublime better ocaml](https://github.com/whitequark/sublime-better-ocaml) -  Sublime Text更好的OCaml模式.
    - [Sublime text package](https://github.com/def-lkb/sublime-text-merlin)
  - [ocp-index](http://www.typerex.org/ocp-index.html)   - 轻松访问已安装的OCaml库的接口信息.  提供独立的工具，如`ocp-browser`和`ocp-grep`.
    - [ocp-browser](http://www.typerex.org/ocp-index.html#ocp-browser) - 基于小型ncurses的API和文档浏览器.
    - [ocp-index-top](https://github.com/reynir/ocp-index-top) - 使用ocp-index查找文档的Toplevel指令.
    - [Sublime text package](https://sublime.wbond.net/packages/OCaml%20Autocompletion)
  - [ocp-indent](http://www.typerex.org/ocp-indent.html) -  OCaml的缩进工具，可以从Emacs和Vim等编辑器中使用.
    - [Vim plugin](https://github.com/def-lkb/ocp-indent-vim).
-  **代码覆盖率**：
  - [Bisect](http://bisect.x9c.fr/)
  - [Bisect_ppx](https://github.com/rleonid/bisect_ppx) 上一个工具的最新分支.


## Exercises

- [99 problems](https://ocaml.org/learn/tutorials/99problems.html) .  99％的解决方案 [here](https://github.com/MassD/99).
- [Rosetta Code](http://rosettacode.org/wiki/Category:OCaml)
- [OCaml at Exercism](http://exercism.io/languages/ocaml)   - 练习是您进行有关代码的深思熟虑的对话的地方.  探索简洁，惯用的语言功能和富有表现力的可读代码. [Solutions](https://github.com/exercism/xocaml).


## Formal Software Verification

- [Coq](https://coq.inria.fr/)   -  Coq是一种正式的证明管理系统.  它提供了一种形式语言来编写数学定义，可执行算法和定理，以及用于机器检查证明的半交互式开发的环境.
- [Why3](http://why3.lri.fr/)   -  Why3是演绎程序验证的平台.  它为规范和编程提供了丰富的语言，称为WhyML，并依赖于自动和交互式的外部定理证明来排除验证条件.
- [Alt-Ergo](http://alt-ergo.lri.fr/) -  Alt-Ergo是一个开源SMT求解器，专门用于证明在程序验证环境中生成的数学公式.


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
- [camlPDF](https://github.com/johnwhitington/camlpdf) - 用于读取，编写和修改PDF文件的OCaml库.
- [slacko](https://github.com/Leonidas-from-XIV/slacko) - 在OCaml中为Slack提供了一个简洁的界面.
- [Learn X in Y minutes](https://learnxinyminutes.com/docs/ocaml/) - 其中X = OCaml.


## Graphics

-  ** 2D **
  - [archimedes](http://archimedes.forge.ocamlcore.org/) -  2D绘图库.
  - [cairo2](https://github.com/Chris00/ocaml-cairo)   - 绑定到开罗，一个2D矢量图形库.  与lablgtk完美结合.
  - [Vg](https://github.com/dbuenzli/vg) -  OCaml的声明性2D矢量图形.
-  ** 3D **
  - [glMLite](http://www.linux-nantes.org/~fmonnier/OCaml/GL/)   -  OCaml的OpenGL绑定.  提供（实验性）功能API.
  - [lablgl](https://forge.ocamlcore.org/projects/lablgl/)   - 与OpenGL的接口.  与lablgtk完美结合.
  - [tgls](http://erratique.ch/software/tgls) - 精简绑定OpenGL 3. {2,3}，4.{0,1,2,3,4}和OpenGL ES {2,3}.


## User Interface

- [lablgtk](http://lablgtk.forge.ocamlcore.org/) - 用于OCaml的GTK2绑定以及各种更高级别的设施来定义GUI.
- [lablqml](https://github.com/Kakadu/lablqml) - 用于OCaml的QML Qt5绑定.
- [labltk](https://forge.ocamlcore.org/projects/labltk/)   - 与Tcl / Tk GUI框架的接口.  在ocaml的标准分布中&lt;= 4.01.
- [TSDL](http://erratique.ch/software/tsdl) -  Tsdl是一个OCaml模块，为跨平台SDL库提供精简绑定.
- [Lambda-Term](https://github.com/ocaml-community/lambda-term)   -  Lambda-Term是一个用于操纵终端的跨平台库.  它提供了键，鼠标事件，颜色的抽象，以及一组用于编写类似curses的应用程序的小部件.
- [Notty](https://github.com/pqwy/notty) -  Notty是OCaml的声明性终端库，围绕可组合图像的概念构建.


## Language-related

- [Higher-Rank Polymorphism in OCaml](http://devmusings.legiasoft.com/blog/2008/05/23/higher-rank_polymorphism_in_ocaml)
- [mikmatch](https://github.com/mjambon/mikmatch) - 使用regexp扩展OCaml模式匹配
- [Inlined records in constructors](http://www.lexifi.com/blog/ocaml/inlined-records-constructors)
- [Algebraic Data Types](https://espertech.wordpress.com/2014/07/30/algebraic-data-types/)
- [XEN – OCaml Best Practices for Developers](http://wiki.xen.org/wiki/OCaml_Best_Practices_for_Developers)
- [OCaml Style Guide (by Jane Street)](https://opensource.janestreet.com/standards/) - 另见：[[1]]（https://www.seas.upenn.edu/~cis500/cis500-f06/resources/programming_style.html），[[2]]（http://www.cs. cornell.edu/Courses/cs312/2001sp/style.html），[[3]]（https://www.seas.upenn.edu/~cis120/current/programming_style.shtml）.
- [A safe but strange way of modifying OCaml compiler](https://bitbucket.org/camlspotter/compiler-libs-hack)
- [Fiddling with the OCaml Type System](https://technotroph.wordpress.com/2013/10/25/fiddling-with-the-ocaml-type-system/)


## Logging

- [dolog](https://github.com/UnixJunkie/dolog) - 一个愚蠢的OCaml记录器.
- [Volt](https://github.com/codinuum/volt) -  Bolt OCaml测井工具的变体.
- [Logs](http://erratique.ch/software/logs) -  Logs为OCaml提供日志记录基础结构.


## Messaging

- [ocaml-zmq](https://github.com/issuu/ocaml-zmq) - 使用Async和Lwt包装器对OCaml进行ZeroMQ绑定.
- [onanomsg](https://github.com/rgrinberg/onanomsg) - 用于OCaml的nanomsg结合.
- [Kafka](https://github.com/didier-wenzek/ocaml-kafka) -  Apache Kafka的OCaml绑定.
- [AMQP](https://github.com/andersfugmann/amqp-client) -  Async和Lwt的AMQP客户端库.
- [MPI](https://github.com/xavierleroy/ocamlmpi) - 消息传递OCaml的接口绑定.
- [MQTT](https://github.com/j0sh/ocaml-mqtt) -  MQTT pubsub协议的OCaml实现.
- [capnp-ocaml](https://github.com/capnproto/capnp-ocaml) - 用于Cap&#39;n Proto序列化框架的OCaml代码生成器插件.

## Metaprogramming

-  **文章**：
  - [A Guide to Extension Points in OCaml](http://whitequark.org/blog/2014/04/16/a-guide-to-extension-points-in-ocaml/)
  - [Extension Points, or how OCaml is becoming more like Lisp](https://blogs.janestreet.com/extension-points-or-how-ocaml-is-becoming-more-like-lisp)
  - [Syntax extensions without Camlp4: let's do it!](http://www.lexifi.com/blog/ocaml/syntax-extensions-without-camlp4-lets-do-it/)
  - [Reading Camlp4 – Ambassador to the Computers](https://ambassadortothecomputers.blogspot.com/p/reading-camlp4.html)
-  **语法扩展**：
  - [ppx_import](https://github.com/ocaml-ppx/ppx_import) -  Import是一种语法扩展，允许从其他编译的接口文件中提取类型或签名.
  - [ppx_string_interpolate](https://github.com/sheijk/ppx_string_interpolate) - 支持字符串插值的简单ppx过滤器，如foo的`[％str“值是$（foo）”]`.
  - [ppx_monad](https://github.com/rizo/ppx_monad) -  OCaml的Monad语法扩展.
  - [ppx_deriving_yojson](https://github.com/whitequark/ppx_deriving_yojson) -  OCaml的Yojson编解码器生成器.
-  **工具和语言扩展**：
  - [MetaOCaml](http://okmij.org/ftp/ML/MetaOCaml.html) - 用于多阶段编程的OCaml方言.
  - [Fan](http://zhanghongbo.me/fan/)   -  Fan是OCaml的编译时元编程系统，最初受到Camlp4的启发.  它是OCaml和Lispy Macros的组合.  它与OCaml具有相同的具体语法.
  - [camlp5](https://camlp5.github.io/) -  Camlp5是OCaml的预处理器 - 漂亮的打印机.
  - [camlp4](http://caml.inria.fr/pub/docs/manual-camlp4/manual002.html) -  Camlp4是标准OCaml发行版的一部分，与Camlp5不同.

## Metrics

- [prometheus](https://github.com/mirage/prometheus) - 用于Prometheus监控的OCaml客户端库.

## Mobile Applications

-  **文章**：
  - [OCaml on iOS 7 Released](http://psellos.com/2014/08/2014.08.ocamlxarm-402.html)
  - [OCaml + Cordova = more secured, typed and hybrid mobile applications](https://blog.danny-willems.be/en/ocaml-cordova-secured-typed-hybrid-mobile-applications/)
-  **绑定**：
  - [Cordova plugins](https://github.com/dannywillems/ocaml-cordova-plugin-list)   -  Cordova插件的绑定列表.  在OCaml中访问本机设备组件，如加速度计，SMS，地理定位等.


## Networking

-  ** HTTP工具**：
  - [ocaml-cohttp](https://github.com/mirage/ocaml-cohttp) - 使用Lwt或Async的非常轻量级的HTTP服务器.
  - [ocurl](https://github.com/ygrek/ocurl) -  OCaml绑定到libcurl.
  - [httpaf](https://github.com/inhabitedtype/httpaf) - 用OCaml编写的高性能，高效，可扩展的Web服务器.
- [ocaml-dns](https://github.com/mirage/ocaml-dns) -  DNS协议的纯OCaml实现.
- [fluent-logger](https://github.com/fluent/fluent-logger-ocaml) -  OCaml的流利记录器.
- [charrua-unix](https://github.com/haesbaert/charrua-unix) -  charrua-unix是一个基于Unix的Unix DHCP守护进程 [charrua-core](https://github.com/haesbaert/charrua-core).


## Online Courses

- [Introduction to Functional Programming in OCaml](https://www.fun-mooc.fr/courses/parisdiderot/56002S02/session02/about).
- [Cornell University – Data Structures and Functional Programming](http://www.cs.cornell.edu/Courses/cs3110/2014fa/course_info.php).
- [Princeton University - Functional programming in OCaml](http://www.cs.princeton.edu/~dpw/courses/cos326-12/).
- [University of Illinois](https://courses.engr.illinois.edu/cs421/fa2014/) - 使用OCaml教授函数式编程和编程语言设计的课程


## Package Management
-  **分发**：
  - [OPAM](http://opam.ocamlpro.com/) - 灵活的Git友好型包管理器，支持多种编译器.
  - [ocamlfind](http://projects.camlcity.org/projects/findlib.html)   - 本地OCaml库管理器.  由大多数OCaml生态系统使用.
  - [OCaml for Windows](https://fdopen.github.io/opam-repository-mingw) - 适用于Windows的opam存储库和实验版本.
  - [makorel](https://github.com/sagotch/makorel) - 轻松发布OPAM包.

-  **构建工具**：
  - [Oasis](http://oasis.forge.ocamlcore.org/)   - 在OCaml项目中集成配置，构建和安装系统的工具.  它有助于在构建系统中创建标准入口点，并允许外部工具轻松分析项目.
    - [oasis2opam](https://github.com/ocaml/oasis2opam) - 将OASIS元数据转换为OPAM包描述的工具.
  - [obuild](https://github.com/ocaml-obuild/obuild) - 用于ocaml的简单包构建系统.
  - [dune](https://github.com/ocaml/dune) -  OCaml（前jbuilder）的可组合且自以为是的构建系统
  - [jenga](https://github.com/janestreet/jenga) -  Jane Street的Monadic构建系统.
  - [ocamlbuild](http://ocaml.org/learn/tutorials/ocamlbuild/) - 构建随编译器提供的系统.
  - [ocaml-makefile](https://github.com/mmottl/ocaml-makefile) - 易于使用的Makefile适用于中小型OCaml项目.
  - [topkg](https://github.com/dbuenzli/topkg) - 使用ocamlbuild的OPAM感知包装系统.
  - [Namespaces](https://github.com/aantron/namespaces) -  ocamlbuild插件，可将目录树转换为嵌套模块.
  - [Bazel](https://github.com/jin/rules_ocaml) -  OCaml规则 [Bazel](https://bazel.build/)，谷歌的多语言和平台构建工具.


## Parallelism

（_注意：从更容易使用到更灵活的排序._）

-  **图书馆**：
  - [Parmap](http://rdicosmo.github.io/parmap/) - 提供易于使用的平行地图和折叠功能.
  - [ForkWork](https://github.com/mlin/forkwork) - 一个简单的库，用于分叉子进程在多个核上执行工作.
  - [Functory](http://functory.lri.fr/About.html) - 分布式计算库，它以无缝方式促进可并行化计算的分布式执行.
  - [Rpc.Parallel](https://github.com/janestreet/rpc_parallel) - 用于在一组计算机上生成进程并在它们之间传递类型消息的库.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html)   - 增强的系统平台库.  包含`netmulticore`库，可根据需要在机器的多个核心上计算任务.
  - [Nproc](https://github.com/MyLifeLabs/nproc) -  OCaml的进程池实现.
  - [Parany](https://github.com/UnixJunkie/parany) - 在独立项目上并行计算，即使它们数量无限.
  - [Sklml](http://sklml.inria.fr) - 用于OCaml程序的功能并行骨架编译器和编程系统.
  - [SPOC](https://github.com/mathiasbourgoin/SPOC) - 用于将密集计算卸载到并行加速器（多核CPU，GPU和与GPGPU框架兼容的其他加速器）的库和语法扩展.

-  **文章**：
  - [What is the state of OCaml's parallelization abilities?](https://stackoverflow.com/questions/6588500/what-is-the-state-of-ocamls-parallelization-abilities)


## Questions

- [OCaml polymorphism example other than template function?](https://stackoverflow.com/questions/14440531/ocaml-polymorphism-example-other-than-template-function)
- [OCaml - polymorphic print and type losing](https://stackoverflow.com/questions/7442449/ocaml-polymorphic-print-and-type-losing)


## Science and Technical Computing

- [biocaml](https://github.com/biocaml/biocaml)   -  OCaml生物信息学图书馆 <http://biocaml.org>  .
- [guizmin](https://github.com/pveber/guizmin) - 用于构建生物信息学管道的OCaml库.
- [lacaml](https://mmottl.github.io/lacaml/) - 用于BLAS / LAPACK的OCaml绑定（高性能线性代数Fortran库）.
- [obandit](http://freux.fr/oss/obandit.html) - 用于多臂匪徒的OCaml库.
- [onumerical](https://github.com/cheshire/onumerical) -  OCaml的数字库.
- [oml](https://github.com/hammerlab/oml) - 用于一般数字工作的OCaml库.
- [ocephes](https://github.com/rleonid/ocephes) - 绑定到常用的`C`特殊功能库.
- [slap](https://github.com/akabe/slap) -  OCaml中的线性代数库，基于类型的静态大小检查矩阵运算.
- [tensorflow-ocaml](https://github.com/LaurentMazare/tensorflow-ocaml) -  TensorFlow的OCaml绑定.
- [owl](https://github.com/owlbarn/owl) -  OCaml数值库：密集和稀疏矩阵，线性代数，回归，数学和统计函数.


## Regular Expressions

- [Re](https://github.com/ocaml/ocaml-re) - 带有组合器的纯OCaml正则表达式库，支持多种格式（glob，posix，str ...）
- [ocaml-pcre](https://github.com/mmottl/pcre-ocaml) - 绑定到PCRE库（perl兼容的正则表达式）
- [Humane-re](https://github.com/rgrinberg/humane-re) -  Humane-re试图为90％的正则表达式提供简单的界面.感谢ocaml-re
- [Tyre](https://github.com/Drup/tyre) - 轮胎是一组组合器，用于构建类型安全的正则表达式，允许自动提取和修改匹配的组.


## Security and Cryptography

- [ocaml-tls](https://github.com/mirleft/ocaml-tls) - 纯OCaml中的T​​LS.
- [Digestif](https://github.com/mirage/digestif) -  OCaml和C中的哈希算法（如SHA *或BLAKE2 *）.
- [cryptokit](https://github.com/xavierleroy/cryptokit) -  OCaml的Cryptokit库提供了各种加密原语，可用于在安全敏感的应用程序中实现加密协议.
- [nocrypto](https://github.com/mirleft/ocaml-nocrypto)   -  ocaml-tls项目背后的一个小型加密库.  它的构建使其易于使用，符合函数式编程原则，并且能够在基于Xen的单核中运行.

&gt;注意：`nocrypto`和`cryptokit`加密库之间的区别在以下博客文章中描述： [OCaml-TLS: building the nocrypto library core](https://mirage.io/blog/introducing-nocrypto).


## Semantic Technology

- [OCaml-RDF](https://www.good-eris.net/ocaml-rdf/) -  OCaml库来操作RDF图并执行Sparql查询.


## Serialization

- [bencode](https://github.com/rgrinberg/bencode) -  Bencode（.torrent文件格式）读/写器.
- [biniou](https://github.com/mjambon/biniou) - 可扩展的二进制数据格式，如JSON但速度更快.
- [jsonm](http://erratique.ch/software/jsonm) -  OCaml的非阻塞流式JSON编解码器.
- [xmlm](http://erratique.ch/software/xmlm) - 用于解码和编码XML数据格式的流式编解码器.
- [yojson](https://github.com/ocaml-community/yojson) - 针对JSON格式的优化解析和打印库.
- [sexplib](https://github.com/janestreet/sexplib) -  S表达式解析器和打印机


## System Programming

- [Mirage OS](https://github.com/mirage/mirage) -  Mirage是一个编程框架，用于在各种云计算和移动平台上构建安全，高性能的网络应用程序.
- [ocaml-fat](https://github.com/mirage/ocaml-fat) - 从OCaml读取和写入FAT格式文件系统.
- [ocaml-git](https://github.com/mirage/ocaml-git) - 纯OCaml低级git绑定.
- [ocaml-vchan](https://github.com/mirage/ocaml-vchan) - 纯“OCaml”实现“vchan”共享内存通信协议.

- **嵌入式系统**
  - [OMicroB](https://github.com/stevenvar/omicrob) - 设计用于在AVR（例如Arduino）微控制器上运行OCaml字节码的虚拟机.
  - [OCaPIC](http://www.algo-prog.info/ocapic/web/index.php?id=OCAPIC:OCAPIC) - 用于PIC18微控制器的OCaml虚拟机.
  - [ocaml-esp32](https://github.com/sadiqj/ocaml-esp32) -  ESP32 SoC的编译器.


## Testing

- [Alcotest](https://github.com/mirage/alcotest) - 轻量级和丰富多彩的测试框架.
- [OUnit](http://ounit.forge.ocamlcore.org/)   -  OUnit是OCaml的单元测试框架.  它允许人们轻松地为OCaml代码创建单元测试.  它基于HUnit，一个Haskell的单元测试框架.
- [QCheck](https://github.com/c-cube/qcheck) -  QCheck是一个灵感来自Haskell QuickCheck的属性测试库
- [iTeML](https://github.com/vincent-hugot/iTeML) （原名 [qtest](http://batteries.vhugot.com/qtest/)） - 支持内联编译指示生成测试.
- [Kaputt](http://kaputt.x9c.fr/) - 全面的测试框架.
- [Pa_test](https://ocaml.janestreet.com/ocaml-core/111.28.00/doc/pa_test) - 一般内联测试宏.
- [TestSimple](https://github.com/hcarty/ocaml-testsimple) - 与之兼容的轻量级单元测试框架 [Test Anything Protocol](https://testanything.org/).


## Utilities

- [ocaml-cuid](https://github.com/marcoonroad/ocaml-cuid) - 用于服务器可伸缩性和数据库性能的防冲突ID.


## Web Development

- **构架**：
  - [Opium](https://github.com/rgrinberg/opium) -  Sinatra喜欢OCaml的web工具包.
  - [Ocsigen Eliom](http://ocsigen.org/eliom/)   -  Eliom是一个功能齐全的多层框架，用于开发多平台Web和移动应用程序，作为100％OCaml分布式应用程序.  它还可以用于更传统的Web或移动应用程序：Web站点，单页面应用程序，REST API等.
  - [webmachine](https://github.com/inhabitedtype/ocaml-webmachine)   -  OCaml的REST工具包.  OCaml webmachine是cohttp之上的一个层，它实现了一个基于状态机的HTTP请求处理器.  它特别适合编写RESTful API.  顾名思义，这是webmachine项目的OCaml端口.

-  **工具**：
  - [COW](https://github.com/mirage/ocaml-cow) - 网络上的Caml（COW）是一组解析器和语法扩展，可让您直接从OCaml代码操作HTML，CSS，XML，JSON和Markdown.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html)
    有许多相关的网络图书馆 - 
    [Nethtml](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Nethtml.html)
    html解析器，
    [Netasn1](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netasn1.html)
    对于ASN.1解析，
    [Netencoding](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netencoding.html)
    for Base64，Quoted Printable，URL编码和HTML转义，
    [Netmime](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netmime.html)
    用于MIME处理等.请参阅[清单
    模块（http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/index.html）
    在Ocamlnet的手册中.
  - [tyxml](http://ocsigen.org/tyxml) - 库构建有效（根据W3C规范）Html和Svg树.
  - [js_of_ocaml](http://ocsigen.org/js_of_ocaml) – Js_of_ocaml is a compiler of OCaml bytecode to Javascript. It makes it possible to run Ocaml programs in a Web browser.
    - [commonjs_of_ocaml](https://github.com/AngryLawyer/commonjs_of_ocaml) - 从js_of_ocaml项目轻松导入和导出CommonJS模块.
  - [BuckleScript](https://github.com/bloomberg/bucklescript)   -  BuckleScript是OCaml的后端，用于生成可调试的Javascript.  它使OCaml能够以无缝方式集成Javascript平台.
  - [ocaml-uri](https://github.com/mirage/ocaml-uri) -  RFC3986 URI解析库.
  - [Goji](https://github.com/klakplok/goji) - 用于JavaScript库的OCaml绑定生成器.
  - [Syndic](https://github.com/Cumulus/Syndic) -  RSS和Atom feed解析
  - [ocaml-mustache](https://github.com/rgrinberg/ocaml-mustache) -  OCaml中的mustache.js无逻辑模板.
  - [atdjs](https://github.com/barko/atdjs) - 用于OCaml / js_of_ocaml的atd代码生成器.
  - [jingoo](https://github.com/tategakibunko/jingoo) -  OCaml模板引擎几乎与jinja2兼容.
  - [dispatch](https://github.com/inhabitedtype/ocaml-dispatch) - 客户端和服务器端应用程序的基于路径的调度.
  - [Lambda Soup](https://github.com/aantron/lambda-soup) - 使用CSS选择器进行功能性HTML抓取和操作，即Python的Beautiful Soup.
  - [Markup.ml](https://github.com/aantron/markup.ml) - 错误恢复流式HTML5和XML解析器，序列化程序.
  - [gen_js_api](https://github.com/LexiFi/gen_js_api) -  gen_js_api旨在简化Javascript库的OCaml绑定的创建.

-  **开源项目**：
  - [Cumulus](https://github.com/Cumulus/Cumulus) - 像OCaml框架Ocsigen的网站一样的黑客新闻

* * *

 _Inspired由令人敬畏的项目线.  发现 [more awesomeness](https://github.com/bayandin/awesome-awesomeness) ：闪耀：._
