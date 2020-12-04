<div class="github-widget" data-repo="coq-community/awesome-coq"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Coq [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/coq-community/awesome-coq/master/coq-logo.svg?sanitize=true" align="right" width="100" title="Awesome Coq is a coq-community project">](https://github.com/coq-community/manifesto)

&gt;精选的Coq库，插件，工具和资源的精选列表.

The [Coq proof assistant](https://coq.inria.fr) 提供了一种正式的语言来编写数学定义，可执行算法和定理，并提供了一种用于半交互式开发机器检查的证明的环境.

欢迎捐款！ 阅读 [contribution guidelines](https://github.com/coq-community/awesome-coq/blob/master/CONTRIBUTING.md) 第一.



---

## Projects

### Frameworks

- [CoqEAL](https://github.com/CoqEAL/CoqEAL) -简化证明中数据表示形式更改的框架.
- [FCF](https://github.com/adampetcher/fcf) -密码学证明框架.
- [Fiat](https://github.com/mit-plv/fiat) -多数情况下自动综合按施工程序编制的程序.
- [FreeSpec](https://github.com/ANSSI-FR/FreeSpec) -用于使用效果和效果处理程序对程序进行模块化验证的框架.
- [Iris](https://iris-project.org) -高阶并发分离逻辑框架.
- [Q\*cert](https://querycert.github.io) -用于实现和验证查询编译器的平台.
- [Verdi](https://github.com/uwplse/verdi) -用于正式验证分布式系统实现的框架.
- [VST](https://vst.cs.princeton.edu) -用于以更高阶的并发强制性分隔逻辑验证Coq中的C代码的工具链，该逻辑对于CompCert编译器的Clight语言而言是正确的.

### User Interfaces

- [CoqIDE](https://coq.inria.fr/refman/practical-tools/coqide.html) -用于与Coq进行交互的独立图形工具.
- [Coqtail](https://github.com/whonore/Coqtail) -基于Vim文本编辑器的Coq界面.
- [Proof General](https://proofgeneral.github.io) -基于可扩展的，可自定义的文本编辑器Emacs的证明助手的通用界面.
- [Company-Coq](https://github.com/cpitclaudel/company-coq) -Proof General的Coq模式的IDE扩展.
- [jsCoq](https://github.com/ejgallego/jscoq) -将Coq移植到JavaScript，从而可以在浏览器中运行Coq项目.
- [Jupyter kernel for Coq](https://github.com/EugeneLoy/coq_jupyter) -对Jupyter Notebook Web环境的Coq支持.
- [VSCoq](https://github.com/coq-community/vscoq) -Visual Studio代码编辑器的扩展.

### Libraries

- [ALEA](https://github.com/coq-community/alea) -用于对随机算法进行推理的库.
- [Bignums](https://github.com/coq/bignums) -任意大数的库.
- [CoLoR](http://color.inria.fr) -有关重写理论，lambda演算和终止的库，以及有关通用数据结构的子库，扩展了Coq标准库.
- [coq-haskell](https://github.com/jwiegley/coq-haskell) -库简化了Haskell用户向Coq的过渡.
- [Coq record update](https://github.com/tchajed/coq-record-update) -提供更新Coq记录字段的通用方法的库.
- [Coq-std++](https://gitlab.mpi-sws.org/iris/stdpp) -扩展了Coq的替代标准库.
- [ExtLib](https://github.com/coq-community/coq-ext-lib) -可能在其他Coq开发中有用的理论和插件的集合.
- [FCSL-PCM](https://github.com/imdea-software/fcsl-pcm) -验证指针操作程序中使用的部分可交换monoid的形式化.
- [Flocq](http://flocq.gforge.inria.fr) -浮点计算的形式化.
- [Formalised Undecidable Problems](https://github.com/uds-psl/coq-library-undecidability) -无法确定的问题及其之间的减少的图书馆.
- [Hahn](https://github.com/vafeiadis/hahn) -用于推理列表和二进制关系的库.
- [Metalib](https://github.com/plclub/metalib) -用于使用本地无名变量绑定表示对语言元理论进行编程的库.
- [Monae](https://github.com/affeldt-aist/monae) -单子效应和方程式推理.
- [Paco](http://plv.mpi-sws.org/paco/) -用于参数化共导的库.
- [Regular Language Representations](https://github.com/coq-community/reglang) -包括正则表达式和自动机在内的各种常规语言定义之间的翻译.
- [Relation Algebra](https://github.com/damien-pous/relation-algebra) -以异构二进制关系作为模型的代数的模块化形式化.
- [Simple IO](https://github.com/Lysxia/coq-simple-io) -具有用户可定义的基本操作的输入/输出monad.
- [TLC](https://github.com/charguer/tlc) -Coq标准库的非建设性替代方案.

### Package and Build Management

- [coq_makefile](https://coq.inria.fr/refman/practical-tools/utilities.html) -与Coq一起分发并基于生成Makefile的构建工具.
- [Coq Package Index](https://coq.inria.fr/packages.html) -基于OPAM的Coq软件包集合.
- [Coq Platform](https://github.com/MSoegtropIMC/coq-platform) -精选实验性包装，以支持Coq在工业，教育和研究中的使用.
- [Coq-community Templates](https://github.com/coq-community/templates) -用于为Coq项目生成配置文件的模板.
- [Docker-Coq](https://github.com/coq-community/docker-coq) -适用于许多版本的Coq的Docker映像.
- [Docker-MathComp](https://github.com/math-comp/docker-mathcomp) -用于Coq版本和Mathematical Components库的许多组合的Docker映像.
- [Docker-Coq-action](https://github.com/marketplace/actions/docker-coq-action) -可与Docker-Coq或Docker-MathComp一起使用的GitHub容器操作.
- [Dune](https://dune.build) -Coq和OCaml（以前的jbuilder）可组合且自以为是的构建系统.
- [Nix](https://nixos.org/nix/) -Linux和其他Unix系统的软件包管理器，支持原子升级和回滚.
- [Nix Coq packages](https://nixos.org/nixos/packages.html?channel=nixpkgs-unstable&query=coqPackages) -收集Cox相关的Nix软件包.
- [OPAM](https://opam.ocaml.org) -用于OCaml的灵活且Git友好的软件包管理器，具有多种编译器支持.

### Plugins

- [AAC Tactics](https://github.com/coq-community/aac-tactics) -重写通用量化方程，某些算子的模结合和可交换性的策略.
- [Coq-Elpi](https://github.com/LPCIC/coq-elpi) -嵌入式Lambda Prolog解释器的插件.
- [CoqHammer](https://github.com/lukaszcz/coqhammer) -通用的自动推理锤工具，结合了从先前的证明中学习和将问题转换为自动证明和重建发现的证明.
- [Equations](https://github.com/mattam82/Coq-Equations) -Coq的功能定义包.
- [Gappa](https://gitlab.inria.fr/gappa/coq) -达成有关浮点算术和舍入误差的目标的策略.
- [Hierarchy Builder](https://github.com/math-comp/hierarchy-builder) -基于打包类声明Coq层次结构的命令集合.
- [Ltac2](https://coq.inria.fr/refman/proof-engine/ltac2.html) -实验型战术语言，类似于Coq的经典Ltac语言.
- [MetaCoq](https://github.com/MetaCoq/metacoq) -在Coq中将Coq正式化，并提供用于处理Coq术语和开发经过认证的插件的工具.
- [Mtac2](https://github.com/Mtac2/Mtac2) -插件添加了用于向后推理的类型化策略.
- [Paramcoq](https://github.com/coq-community/paramcoq) -生成Coq术语的参数化翻译的插件.
- [QuickChick](https://github.com/QuickChick/QuickChick) -用于基于属性的随机测试的插件.
- [SMTCoq](https://github.com/smtcoq/smtcoq) -检查来自外部SAT和SMT求解器的证据见证人的工具.
- [Unicoq](https://github.com/unicoq/unicoq) -用增强的功能替换现有的统一算法的插件.

### Tools

- [CFML](https://gitlab.inria.fr/charguer/cfml2) -在分离逻辑中证明OCaml程序属性的工具.
- [coq2html](https://github.com/xavierleroy/coq2html) -Coq的备用HTML文档生成器.
- [CoqOfOCaml](https://github.com/clarus/coq-of-ocaml) -用于从OCaml代码生成惯用Coq的工具.
- [coq-dpdgraph](https://github.com/Karmaki/coq-dpdgraph) -用于在Coq对象之间建立依赖关系图的工具.
- [coq-tools](https://github.com/JasonGross/coq-tools) -脚本，可帮助构建小型的错误重现示例，删除不需要的导入等.
- [Cosette](https://github.com/uwdb/Cosette) -用于推理SQL查询等效性的自动求解器.
- [hs-to-coq](https://github.com/plclub/hs-to-coq) -从Haskell代码转换为等效的Coq代码.
- [lngen](https://github.com/plclub/lngen) -用于生成本地无名Coq定义和证明的工具.
- [Menhir](http://gallium.inria.fr/~fpottier/menhir/) -解析器生成器，可以输出经过验证的解析器的Coq代码.
- [mCoq](https://github.com/EngineeringSoftware/mcoq) -Coq项目的变异分析工具.
- [Ott](https://github.com/ott-lang/ott) -用于编写可翻译为Coq的编程语言和演算的定义的工具.
- [Roosterize](https://github.com/EngineeringSoftware/roosterize) -在Coq项目中建议引理名称的工具.
- [SerAPI](https://github.com/ejgallego/coq-serapi) -用于在与JSON和S表达式之间进行Coq代码反序列化的库和工具.

### Type Theory and Mathematics

- [Analysis](https://github.com/math-comp/analysis) -与数学组件兼容的经典真实分析库.
- [Category Theory in Coq](https://github.com/jwiegley/category-theory) -无公理的范畴论形式化.
- [Completeness and Decidability of Modal Logic Calculi](https://github.com/coq-community/comp-dec-modal) -逻辑K，K *，CTL和PDL的健全性，完整性和可判定性.
- [CoqPrime](https://github.com/thery/coqprime) -使用Pocklington和Elliptic Curve证书来证明原始性的库.
- [CoRN](https://github.com/coq-community/corn) -建设性的实物分析和代数图书馆.
- [Coqtail Math](https://github.com/coq-community/coqtail-math) -数学结果库，范围从算术到实际和复杂分析.
- [Coquelicot](https://gitlab.inria.fr/coquelicot/coquelicot) -与标准库兼容并关注可用性的经典实物分析的形式化.
- [Finmap](https://github.com/math-comp/finmap) -扩展带有有限映射，集合和多集合的数学组件.
- [Four Color Theorem](https://github.com/math-comp/fourcolor) -四色定理的形式证明，是图论的标志性结果.
- [Gaia](https://github.com/coq-community/gaia) -实施Bourbaki的《数学元素》中的书籍，包括集合论和数论.
- [GeoCoq](https://github.com/GeoCoq/GeoCoq) -基于Tarski公理系统的几何形式化.
- [Graph Theory](https://github.com/coq-community/graph-theory) -形式化图论的结果.
- [Homotopy Type Theory](https://github.com/HoTT/HoTT) -同伦理论思想的发展.
- [Infotheo](https://github.com/affeldt-aist/infotheo) -信息论和线性纠错码的形式化.
- [Mathematical Components](http://math-comp.github.io) -数学理论的形式化，特别是小组理论.
- [Math Classes](https://github.com/coq-community/math-classes) -基于类型类的数学结构的抽象接口.
- [Odd Order Theorem](https://github.com/math-comp/odd-order) -奇数定理的形式证明，这是有限群论的标志性结果.
- [Puiseuxth](https://github.com/roglo/puiseuxth) -Puiseux定理的证明和Puiseux级数的多项式根的计算.
- [UniMath](https://github.com/UniMath/UniMath) -旨在使用单价观点形式化大量数学的图书馆.

### Verified Software

- [CompCert](http://compcert.inria.fr) -几乎所有C语言（ISO C99）的高安全性编译器，可为PowerPC，ARM，RISC-V和x86处理器生成高效的代码.
- [Fiat-Crypto](https://github.com/mit-plv/fiat-crypto) -密码原始代码生成.
- [Incremental Cycles](https://gitlab.inria.fr/agueneau/incremental-cycles) - Verified OCaml implementation of an algorithm for incremental cycle detection in graphs.
- [JSCert](https://github.com/jscert/jscert) -带有经过验证的参考解释器的ECMAScript 5（JavaScript）的Coq规范.
- [lambda-rust](https://gitlab.mpi-sws.org/iris/lambda-rust) -Rust核心语言和类型系统的正式模型，类型系统的逻辑关系以及某些Rust库的安全证明.
- [Verdi Raft](https://github.com/uwplse/verdi-raft) -Raft分布式共识协议的实现，已使用Verdi框架在Coq中进行了验证.

## Resources

### Community

- [Official Coq website](https://coq.inria.fr)
- [Official Coq manual](https://coq.inria.fr/refman/)
- [Official Coq standard library](https://coq.inria.fr/stdlib/)
- [Official Coq Discourse forum](https://coq.discourse.group)
- [Official Coq Zulip chat](https://coq.zulipchat.com)
- [Official Coq-Club mailing list](https://sympa.inria.fr/sympa/arc/coq-club)
- [Official Coq wiki](https://github.com/coq/coq/wiki)
- [Official Coq Twitter](https://twitter.com/CoqLang)
- [coq-community package maintenance project](https://github.com/coq-community/manifesto)
- [Coq subreddit](https://www.reddit.com/r/coq/)
- [Coq tag on Stack Overflow](https://stackoverflow.com/questions/tagged/coq)
- [Coq tag on Theoretical Computer Science Stack Exchange](https://cstheory.stackexchange.com/questions/tagged/coq)
- [Mathematical Components wiki](https://github.com/math-comp/math-comp/wiki)
- [Planet Coq link aggregator](https://coq.pl-a.net)

### Blogs

- [Coq Exchange: ideas and experiment reports about Coq](https://project.inria.fr/coqexchange/news/)
- [Gagallium](http://gallium.inria.fr/blog)
- [Gregory Malecha's blog](https://gmalecha.github.io)
- [Guillaume Claret's Coq blog](http://coq-blog.clarus.me)
- [Joachim Breitner's blog posts on Coq](http://www.joachim-breitner.de/blog/tag/Coq)
- [MIT PLV blog posts on Coq](https://plv.csail.mit.edu/blog/category/coq.html)
- [PLClub Blog](https://www.seas.upenn.edu/~plclub/blog/)
- [Poleiro: a Coq blog by Arthur Azevedo de Amorim](http://poleiro.info)
- [Ralf Jung's blog posts on Coq](https://www.ralfj.de/blog/categories/coq.html)
- [Thomas Letan's blog posts on Coq](https://soap.coffee/~lthms/#coq)

### Books

- [Coq'Art](https://www.labri.fr/perso/casteran/CoqArt/) -致力于Coq的第一本书.
- [Software Foundations](https://softwarefoundations.cis.upenn.edu) -基于Coq的有关逻辑，函数式编程和编程语言基础的教科书系列，旨在供初学者使用.
- [Certified Programming with Dependent Types](http://adam.chlipala.net/cpdt/) -关于使用Coq进行实践工程的教科书，讲授高级实践技巧和非常具体的证明样式.
- [Program Logics for Certified Compilers](https://www.cs.princeton.edu/~appel/papers/plcc.pdf) -本书解释了如何使用分离逻辑构造程序逻辑，并辅以Coq中的形式化模型，该模型适用于Clight编程语言和其他示例.
- [Formal Reasoning About Programs](http://adam.chlipala.net/frap/) -同时提供有关程序正确性的形式逻辑推理和为此目的使用Coq的一般介绍的书.
- [Programs and Proofs](https://ilyasergey.net/pnp/) -本书简要介绍了Coq中的交互式证明，并在实践中作了介绍，该书强调了通过SSReflect证明语言中的一小部分原语，对可判定命题进行归纳推理的计算性质.
- [Computer Arithmetic and Formal Proofs](http://iste.co.uk/book.php?id=1238) -本书介绍了如何使用Flocq库在Coq中正式指定和验证浮点算法.
- [The Mathematical Components book](https://math-comp.github.io/mcb/) -面向数学倾向用户的书籍，侧重于数学组件库和SSReflect证明语言.

### Course Material

- [Foundations of Separation Logic](https://chargueraud.org/teach/verif/) -介绍使用分离逻辑来推理Coq中的顺序命令程序.
- [Introduction to Computational Logic](https://courses.ps.uni-saarland.de/icl_20/2/Resources) -介绍基本逻辑原理，构造型理论以及用Coq证明的交互式定理.

### Tutorials and Hints

- [CodeWars' Coq kata](https://www.codewars.com/kata/search/coq) -在线验证挑战.
- [Coq'Art Exercises and Tutorials](https://github.com/coq-community/coq-art) -Coq&#39;Art书中的Coq代码和练习，包括其他教程.
- [Coq in a Hurry](http://cel.archives-ouvertes.fr/inria-00001173) -介绍如何使用Coq定义逻辑概念和功能及其原因.
- [Lemma Overloading](https://github.com/coq-community/lemma-overloading) -演示用于规范结构编程和验证的设计模式.
- [Mike Nahas's Coq Tutorial](https://mdnahas.github.io/doc/nahas_tutorial.html) -使用Coq编写形式证明的基础.
- [Tricks in Coq](https://github.com/tchajed/coq-tricks) -难以发现的提示，技巧和功能.
