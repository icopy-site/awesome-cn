<div class="github-widget" data-repo="coq-community/awesome-coq"></div>
## Awesome Coq [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/coq-community/awesome-coq/master/coq-logo.svg?sanitize=true" align="right" width="100" alt="coq-community logo" title="Awesome Coq is a coq-community project">](https://github.com/coq-community/manifesto)

&gt; 很棒的 Coq 库、插件、工具和资源的精选列表.

The [Coq proof assistant](https://coq.inria.fr) 提供了一种用于编写数学定义、可执行算法和定理的形式语言，以及用于机器检查证明的半交互式开发的环境.

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/coq-community/awesome-coq/blob/master/CONTRIBUTING.md) 第一的.



---

## Projects

### Frameworks

- [ConCert](https://github.com/AU-COBRA/ConCert) - 智能合约测试和验证框架，具有多种智能合约语言的代码提取管道.
- [CoqEAL](https://github.com/CoqEAL/CoqEAL) - 简化证明中数据表示形式变化的框架.
- [FCF](https://github.com/adampetcher/fcf) - 密码学证明框架.
- [Fiat](https://github.com/mit-plv/fiat) - 主要是构建正确程序的自动合成.
- [FreeSpec](https://github.com/lthms/FreeSpec) - 使用效果和效果处理程序模块化验证程序的框架.
- [Hoare Type Theory](https://github.com/imdea-software/htt/) - 顺序分离逻辑的浅嵌入被表述为类型理论.
- [Hybrid](https://www.site.uottawa.ca/~afelty/HybridCoq/) - 使用对象逻辑的高阶抽象语法表示进行推理的系统.
- [Iris](https://iris-project.org) - 高阶并发分离逻辑框架.
- [Q\*cert](https://github.com/querycert/qcert) - 用于实现和验证查询编译器的平台.
- [VCFloat](https://github.com/VeriNum/vcfloat) - 使用浮点计算验证 C 程序的框架.
- [Verdi](https://github.com/uwplse/verdi) - 正式验证分布式系统实现的框架.
- [VST](https://vst.cs.princeton.edu) - 用于在 Coq 内以高阶并发、命令式分离逻辑验证 C 代码的工具链，该逻辑对于 CompCert 编译器的 Clight 语言来说是合理的.

### User Interfaces

- [CoqIDE](https://coq.inria.fr/refman/practical-tools/coqide.html) - 用于与 Coq 交互的独立图形工具.
- [Coqtail](https://github.com/whonore/Coqtail) - 基于 Vim 文本编辑器的 Coq 界面.
- [Coq LSP](https://github.com/ejgallego/coq-lsp) - Visual Studio Code 和 VSCodium 编辑器的语言服务器和扩展，具有自定义文档检查引擎.
- [Proof General](https://proofgeneral.github.io) - 基于可扩展、可定制文本编辑器 Emacs 的校样助手通用界面.
- [Company-Coq](https://github.com/cpitclaudel/company-coq) - Proof General 的 Coq 模式的 IDE 扩展.
- [jsCoq](https://github.com/ejgallego/jscoq) - 将 Coq 移植到 JavaScript，从而可以在浏览器中运行 Coq 项目.
- [Jupyter kernel for Coq](https://github.com/EugeneLoy/coq_jupyter) - Coq 对 Jupyter Notebook Web 环境的支持.
- [VsCoq1](https://github.com/coq-community/vscoq/tree/vscoq1) - 使用 Coq 的旧版 XML 协议对 Visual Studio Code 和 VSCodium 编辑器进行扩展.
- [VsCoq2](https://github.com/coq-community/vscoq) - Visual Studio Code 和 VSCodium 编辑器的实验性语言服务器和扩展.

### Libraries

- [ALEA](https://github.com/coq-community/alea) - 用于推理随机算法的库.
- [Algebra Tactics](https://github.com/math-comp/algebra-tactics) - 数学部分的环场战术.
- [Bignums](https://github.com/coq/bignums) - 任意大数的库.
- [Bedrock Bit Vectors](https://github.com/mit-plv/bbv) - 用于对固定精度机器字进行推理的库.
- [CertiGraph](https://github.com/Salamari/CertiGraph) - 用于推理有向图及其在分离逻辑中的嵌入的库.
- [CoLoR](https://github.com/fblanqui/color) - 重写理论、lambda 演算和终止的库，以及扩展 Coq 标准库的通用数据结构的子库.
- [coq-haskell](https://github.com/jwiegley/coq-haskell) - 库使 Haskell 用户顺利过渡到 Coq.
- [CoqInterval](https://gitlab.inria.fr/coqinterval/interval/) - 对实数表达式进行不等式证明的策略.
- [Coq record update](https://github.com/tchajed/coq-record-update) - 提供更新 Coq 记录字段的通用方法的库.
- [Coq-std++](https://gitlab.mpi-sws.org/iris/stdpp) - Coq 的扩展替代标准库.
- [ExtLib](https://github.com/coq-community/coq-ext-lib) - 可能对其他 Coq 开发有用的理论和插件的集合.
- [FCSL-PCM](https://github.com/imdea-software/fcsl-pcm) - 用于验证指针操作程序的部分交换幺半群的形式化.
- [Flocq](https://gitlab.inria.fr/flocq/flocq) - 浮点数和计算的形式化.
- [Formalised Undecidable Problems](https://github.com/uds-psl/coq-library-undecidability) - 不可判定问题及其之间的减少的库.
- [Hahn](https://github.com/vafeiadis/hahn) - 用于推理列表和二元关系的库.
- [Interaction Trees](https://github.com/DeepSpec/InteractionTrees) - 用于表示递归和不纯程序的库.
- [LibHyps](https://github.com/Matafou/LibHyps) - Ltac 策略库用于管理和操纵证明中的假设.
- [MathComp Extra](https://github.com/thery/mathcomp-extra) - 数学组件库的额外材料，包括 AKS 素性测试和 RSA 加密和解密.
- [Mczify](https://github.com/math-comp/mczify) - 使用数学组件数字定义时，使 Micromega 算术求解器能够工作的库.
- [Metalib](https://github.com/plclub/metalib) - 使用本地无名变量绑定表示的编程语言元理论库.
- [Paco](http://plv.mpi-sws.org/paco/) - 参数化共归纳库.
- [Regular Language Representations](https://github.com/coq-community/reglang) - 正则语言不同定义之间的翻译，包括正则表达式和自动机.
- [Relation Algebra](https://github.com/damien-pous/relation-algebra) - 以异构二元关系作为模型的代数的模块化形式化.
- [Simple IO](https://github.com/Lysxia/coq-simple-io) - 具有用户可定义原语操作的输入/输出单子.
- [TLC](https://github.com/charguer/tlc) - Coq 标准库的非建设性替代方案.

### Package and Build Management

- [coq_makefile](https://coq.inria.fr/refman/practical-tools/utilities.html) - 与 Coq 一起分发并基于生成 makefile 的构建工具.
- [Coq Nix Toolbox](https://github.com/coq-community/coq-nix-toolbox) - Nix 帮助程序脚本可自动执行 Coq 的本地构建和持续集成.
- [Coq Package Index](https://coq.inria.fr/opam/www/) - 基于 opam 的 Coq 包集合.
- [Coq Platform](https://github.com/coq/platform) - 精心策划的软件包集合，以支持 Coq 在工业、教育和研究中的使用.
- [coq-community Templates](https://github.com/coq-community/templates) - 用于为 Coq 项目生成配置文件的模板.
- [Docker-Coq](https://github.com/coq-community/docker-coq) - 许多 Coq 版本的 Docker 镜像.
- [Docker-MathComp](https://github.com/math-comp/docker-mathcomp) - Coq 和数学组件库版本的多种组合的 Docker 镜像.
- [Docker-Coq GitHub Action](https://github.com/marketplace/actions/docker-coq-action) - 可与 Docker-Coq 或 Docker-MathComp 一起使用的 GitHub 容器操作.
- [Dune](https://dune.build) - OCaml 和 Coq（前 jbuilder）的可组合且固执己见的构建系统.
- [Nix](https://nixos.org/nix/) - Linux 和其他 Unix 系统的包管理器，支持原子升级和回滚.
- [Nix Coq packages](https://search.nixos.org/packages?channel=unstable&query=coqPackages) - Nix 的 Coq 相关包集合.
- [opam](https://opam.ocaml.org) - 适用于 OCaml 和 Coq 的灵活且 Git 友好的包管理器，具有多个编译器支持.

### Plugins

- [AAC Tactics](https://github.com/coq-community/aac-tactics) - 重写通用量化方程、某些算子的模结合性和交换性的策略.
- [Coq-Elpi](https://github.com/LPCIC/coq-elpi) - 基于 λProlog 的扩展框架提供广泛的 API 来实施命令和策略.
- [CoqHammer](https://github.com/lukaszcz/coqhammer) - 通用自动推理锤工具，将先前证明的学习与将问题转化为自动证明者以及重建找到的证明相结合.
- [Equations](https://github.com/mattam82/Coq-Equations) - Coq 的函数定义包.
- [Gappa](https://gitlab.inria.fr/gappa/coq) - 消除浮点运算和舍入误差目标的策略.
- [Hierarchy Builder](https://github.com/math-comp/hierarchy-builder) - 用于声明基于打包类的 Coq 层次结构的命令集合.
- [Itauto](https://gitlab.inria.fr/fbesson/itauto) - 类似 SMT 的策略，用于对函数符号、构造函数和算术进行组合命题推理.
- [Ltac2](https://coq.inria.fr/refman/proof-engine/ltac2.html) - 实验性类型策略语言，类似于 Coq 的经典 Ltac 语言.
- [MetaCoq](https://github.com/MetaCoq/metacoq) - 在 Coq 中正式化 Coq 的项目，并提供用于操作 Coq 术语和开发经过认证的插件的工具.
- [Mtac2](https://github.com/Mtac2/Mtac2) - 插件添加用于向后推理的类型策略.
- [Paramcoq](https://github.com/coq-community/paramcoq) - 用于生成 Coq 术语的参数化翻译的插件.
- [QuickChick](https://github.com/QuickChick/QuickChick) - 用于基于属性的随机测试的插件.
- [SMTCoq](https://github.com/smtcoq/smtcoq) - 检查来自外部 SAT 和 SMT 求解器的证明证据的工具.
- [Tactician](https://coq-tactician.github.io) - 交互式工具，它从所有已安装的 Coq 包中先前编写的策略脚本中学习，并建议下一个要执行的策略或尝试完全自动化证明合成.
- [Unicoq](https://github.com/unicoq/unicoq) - 用增强型算法替换现有统一算法的插件.

### Puzzles and Games

- [Coqoban](https://github.com/coq-community/coqoban) - Coq 实现了 Sokoban（日本仓库管理员游戏）.
- [Hanoi](https://github.com/thery/hanoi) - Coq 中的汉诺塔谜题，包括有关配置的概括和定理.
- [Mini-Rubik](https://github.com/thery/minirubik) - 魔方拼图 2x2x2 版本的 Coq 形式化和求解器.
- [Name the Biggest Number](https://github.com/codyroux/name-the-biggest-number) - 用于提交 Coq 中最大数字头衔的经过验证的竞争者的存储库.
- [Natural Number Game](https://github.com/uncomputable/natural-number-game) - 为精益证明者开发的自然数游戏的 Coq 版本.
- [Sudoku](https://github.com/coq-community/sudoku) - Coq 中数独数字放置难题的形式化和求解器.
- [T2048](https://github.com/thery/T2048) - 2048 滑动瓷砖游戏的 Coq 版本.

### Tools

- [Alectryon](https://github.com/cpitclaudel/alectryon) - 用于编写混合 Coq 代码和散文的技术文档的工具集合.
- [Autosubst 2](https://github.com/uds-psl/autosubst2) - 生成 Coq 代码的工具，用于处理语法中的绑定器，例如重命名和替换.
- [CFML](https://gitlab.inria.fr/charguer/cfml2) - 用于证明 OCaml 程序在分离逻辑中的属性的工具.
- [coq2html](https://github.com/xavierleroy/coq2html) - Coq 的替代 HTML 文档生成器.
- [coqdoc](https://coq.inria.fr/refman/using/tools/coqdoc.html) - 标准文档工具，可从 Coq 代码生成 LaTeX 或 HTML 文件.
- [CoqOfOCaml](https://github.com/clarus/coq-of-ocaml) - 用于从 OCaml 代码生成惯用 Coq 的工具.
- [coq-dpdgraph](https://github.com/coq-community/coq-dpdgraph) - 用于构建 Coq 对象之间的依赖关系图的工具.
- [coq-scripts](https://github.com/JasonGross/coq-scripts) - 用于处理 Coq 文件的脚本，包括将证明时间制成表格.
- [coq-tools](https://github.com/JasonGross/coq-tools) - 用于操纵 Coq 开发的脚本.
  - [`find-bug.py`](https://github.com/JasonGross/coq-tools/blob/master/find-bug.py) - 自动最小化产生错误的源文件，为 Coq 错误创建小型测试用例.
  - [`absolutize-imports.py`](https://github.com/JasonGross/coq-tools/blob/master/absolutize-imports.py) - 处理源文件以使依赖项的加载对文件名的阴影具有鲁棒性.
  - [`inline-imports.py`](https://github.com/JasonGross/coq-tools/blob/master/inline-imports.py) - 通过内联加载所有依赖项，从开发中创建独立的源文件.
  - [`minimize-requires.py`](https://github.com/JasonGross/coq-tools/blob/master/minimize-requires.py) - Removes loading of unused dependencies.
  - [`move-requires.py`](https://github.com/JasonGross/coq-tools/blob/master/move-requires.py) - 将所有依赖项加载语句移至源文件的顶部.
  - [`move-vernaculars.py`](https://github.com/JasonGross/coq-tools/blob/master/move-vernaculars.py) - 从证明脚本块中提出许多白话命令和内部引理.
  - [`proof-using-helper.py`](https://github.com/JasonGross/coq-tools/blob/master/proof-using-helper.py) - 修改源文件以包含证明注释，以实现更快的并行证明.
- [Cosette](https://github.com/uwdb/Cosette) - 用于推理 SQL 查询等价性的自动求解器.
- [hs-to-coq](https://github.com/plclub/hs-to-coq) - 从 Haskell 代码到等效 Coq 代码的转换器.
- [lngen](https://github.com/plclub/lngen) - 用于生成本地无名 Coq 定义和证明的工具.
- [Menhir](http://gallium.inria.fr/~fpottier/menhir/) - 解析器生成器，可以为经过验证的解析器输出 Coq 代码.
- [mCoq](https://github.com/EngineeringSoftware/mcoq) - Coq 项目的突变分析工具.
- [Ott](https://github.com/ott-lang/ott) - 用于编写可翻译为 Coq 的编程语言和演算定义的工具.
- [PyCoq](https://github.com/ejgallego/pycoq) - 用于从 Python 3 内部与 Coq 交互的一组绑定和库.
- [Roosterize](https://github.com/EngineeringSoftware/roosterize) - 用于在 Coq 项目中建议引理名称的工具.
- [Sail](https://github.com/rems-project/sail) - 用于指定处理器指令集架构语义并生成 Coq 定义的工具.
- [SerAPI](https://github.com/ejgallego/coq-serapi) - 用于 Coq 代码与 JSON 和 S 表达式之间的序列化（反序列化）的工具和 OCaml 库.
- [Trakt](https://github.com/ecranceMERCE/trakt) - 用于证明自动化策略的通用目标预处理工具.

### Type Theory and Mathematics

- [Analysis](https://github.com/math-comp/analysis) - 与数学组件兼容的经典实分析库.
- [Category Theory in Coq](https://github.com/jwiegley/category-theory) - 范畴论的无公理形式化.
- [Completeness and Decidability of Modal Logic Calculi](https://github.com/coq-community/comp-dec-modal) - 逻辑 K、K*、CTL 和 PDL 的健全性、完整性和可判定性.
- [CoqPrime](https://github.com/thery/coqprime) - 使用 Pocklington 和椭圆曲线证书证明素数的库.
- [CoRN](https://github.com/coq-community/corn) - 建设性实分析和代数库.
- [Coqtail Math](https://github.com/coq-community/coqtail-math) - 数学结果库，范围从算术到实际和复杂的分析.
- [Coquelicot](https://gitlab.inria.fr/coquelicot/coquelicot) - 经典实分析的形式化，与标准库兼容并注重可用性.
- [Finmap](https://github.com/math-comp/finmap) - 用有限映射、集合和多重集扩展数学组件.
- [Four Color Theorem](https://github.com/coq-community/fourcolor) - 四色定理的形式证明，这是图论的里程碑式的结果.
- [Gaia](https://github.com/coq-community/gaia) - 实施布尔巴基《数学原理》中的书籍，包括集合论和数论.
- [GeoCoq](https://github.com/GeoCoq/GeoCoq) - 基于塔斯基公理系统的几何形式化.
- [Graph Theory](https://github.com/coq-community/graph-theory) - 形式化的图论结果.
- [Homotopy Type Theory](https://github.com/HoTT/Coq-HoTT) - 同伦理论思想的发展.
- [Infotheo](https://github.com/affeldt-aist/infotheo) - 信息论和线性纠错码的形式化.
- [Mathematical Components](http://math-comp.github.io) - 数学理论的形式化，特别关注群论.
- [Math Classes](https://github.com/coq-community/math-classes) - 基于类型类的数学结构的抽象接口.
- [Monae](https://github.com/affeldt-aist/monae) - 一元效应和等式推理.
- [Odd Order Theorem](https://github.com/math-comp/odd-order) - 奇数阶定理的形式证明，这是有限群论的里程碑式的结果.
- [Puiseuxth](https://github.com/roglo/puiseuxth) - Puiseux 定理的证明和 Puiseux 级数多项式根的计算.
- [UniMath](https://github.com/UniMath/UniMath) - 旨在使用统一观点形式化大量数学的图书馆.

### Verified Software

- [CompCert](http://compcert.inria.fr) - 适用于几乎所有 C 语言 (ISO C99) 的高保证编译器，为 PowerPC、ARM、RISC-V 和 x86 处理器生成高效代码.
- [Ceramist](https://github.com/certichain/ceramist) - 验证基于散列的近似成员资格结构，例如布隆过滤器.
- [Fiat-Crypto](https://github.com/mit-plv/fiat-crypto) - 加密原始代码生成.
- [Functional Algorithms Verified in SSReflect](https://github.com/clayrat/fav-ssr) - 用于搜索、排序和其他基本问题的算法的纯功能验证实现.
- [Incremental Cycles](https://gitlab.inria.fr/agueneau/incremental-cycles) - 验证了图形中增量循环检测算法的 OCaml 实现.
- [Jasmin](https://github.com/jasmin-lang/jasmin) - 用于高保证和高速加密的形式化语言和经过验证的编译器.
- [JSCert](https://github.com/jscert/jscert) - ECMAScript 5 (JavaScript) 的 Coq 规范以及经过验证的参考解释器.
- [lambda-rust](https://gitlab.mpi-sws.org/iris/lambda-rust) - Rust 核心语言和类型系统的形式模型、类型系统的逻辑关系以及一些 Rust 库的安全证明.
- [Prosa](https://gitlab.mpi-sws.org/RT-PROOFS/rt-proofs) - 实时系统可调度性分析的定义和证明.
- [RISC-V Specification in Coq](https://github.com/mit-plv/riscv-coq) - RISC-V 处理器指令集架构和扩展的定义.
- [Tarjan and Kosaraju](https://github.com/math-comp/tarjan) - 拓扑排序和在有限图中查找强连通分量的算法的验证实现.
- [Vélus](http://velus.inria.fr) - 经过验证的类似 Lustre/Scade 数据流同步语言的编译器.
- [Verdi Raft](https://github.com/uwplse/verdi-raft) - Raft 分布式共识协议的实现，使用 Verdi 框架在 Coq 中进行验证.

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
- [Coq Zulip chat archive](https://coq.gitlab.io/zulip-archive/)
- [Coq subreddit](https://www.reddit.com/r/Coq/)
- [Coq tag on Stack Overflow](https://stackoverflow.com/questions/tagged/coq)
- [Coq tag on Theoretical Computer Science Stack Exchange](https://cstheory.stackexchange.com/questions/tagged/coq)
- [Coq tag on Proof Assistants Stack Exchange](https://proofassistants.stackexchange.com/questions/tagged/coq)
- [Coq keyword on Zenodo](https://zenodo.org/search?q=keywords%3A%22Coq%22)
- [coq-community package maintenance project](https://github.com/coq-community/manifesto)
- [Mathematical Components wiki](https://github.com/math-comp/math-comp/wiki)
- [100 famous theorems proved using Coq](https://github.com/coq-community/coq-100-theorems)
- [Planet Coq link aggregator](https://coq.pl-a.net)
- [Sherlocoq code search](https://sherlocoq.sirref.org)

### Blogs

- [Coq Exchange: ideas and experiment reports about Coq](https://project.inria.fr/coqexchange/news/)
- [Gagallium](http://gallium.inria.fr/blog)
- [Gregory Malecha's blog](https://gmalecha.github.io)
- [Guillaume Claret's Coq blog](http://coq-blog.clarus.me)
- [Joachim Breitner's blog posts on Coq](http://www.joachim-breitner.de/blog/tag/Coq)
- [Lysxia's blog](https://blog.poisson.chat)
- [MIT PLV blog posts on Coq](https://plv.csail.mit.edu/blog/category/coq.html)
- [PLClub Blog](https://www.seas.upenn.edu/~plclub/blog/)
- [Poleiro: a Coq blog by Arthur Azevedo de Amorim](http://poleiro.info)
- [Ralf Jung's blog posts on Coq](https://www.ralfj.de/blog/categories/coq.html)
- [Thomas Letan's blog posts on Coq](https://soap.coffee/~lthms/tags/coq.html)

### Books

- [Coq'Art](https://www.labri.fr/perso/casteran/CoqArt/) - 第一本专门介绍 Coq 的书.
- [Software Foundations](https://softwarefoundations.cis.upenn.edu) - 基于 Coq 的一系列关于逻辑、函数式编程和编程语言基础的教科书，旨在供初学者使用.
- [Certified Programming with Dependent Types](http://adam.chlipala.net/cpdt/) - 关于 Coq 实际工程的教科书，教授高级实用技巧和非常具体的证明风格.
- [Program Logics for Certified Compilers](https://www.cs.princeton.edu/~appel/papers/plcc.pdf) - 本书解释了如何使用分离逻辑构建程序逻辑，并附有应用于 Clight 编程语言的 Coq 形式模型和其他示例.
- [Formal Reasoning About Programs](http://adam.chlipala.net/frap/) - 本书同时提供了关于程序正确性的形式逻辑推理以及为此目的使用 Coq 的一般介绍.
- [Programs and Proofs](https://ilyasergey.net/pnp/) - 这本书对 Coq 中的交互式证明进行了简短且实用的介绍，强调通过 SSReflect 证明语言中的一小组原语对可判定命题进行归纳推理的计算性质.
- [Computer Arithmetic and Formal Proofs](http://iste.co.uk/book.php?id=1238) - 描述如何使用 Flocq 库在 Coq 中正式指定和验证浮点算法的书.
- [The Mathematical Components book](https://math-comp.github.io/mcb/) - 本书面向数学爱好者，重点关注数学组件库和 SSReflect 证明语言.
- [Modeling and Proving in Computational Type Theory](https://github.com/uds-psl/MPCTT) - 本书涵盖使用 Coq 的计算逻辑主题，包括基础知识、典型案例研究和实用编程.
- [Hydras & Co.](https://github.com/coq-community/hydra-battles) - 持续不断的关于 Kirby 和 Paris 的九头蛇之战以及 Coq 中其他有趣的形式化数学的书籍和图书馆，包括哥德尔-罗瑟第一不完备性定理的证明.

### Course Material

- [Foundations of Separation Logic](https://chargueraud.org/teach/verif/) - 介绍如何在 Coq 中使用分离逻辑来推理顺序命令式程序.
- [Floating-Point Numbers and Formal Proof](https://github.com/thery/FlocqLecture) - Flocq 库中的 Coq 实数和浮点数入门课程.
- [Introduction to the Theory of Computation](https://gitlab.com/umb-svl/turing) - 形式化以支持计算理论本科课程，包括语言和图灵机.
- [Lectures on Software Foundations](https://github.com/clarksmr/sf-lectures) - Material on the Software Foundations series of textbooks, including a series of YouTube videos.
- [MathComp School](https://github.com/gares/math-comp-school-2022) - Coq 课程和练习资源，介绍 SSReflect 证明语言和数学组件库.
- [Mechanized Semantics](https://github.com/xavierleroy/cdf-mech-sem) - 法兰西学院编程语言语义课程的 Coq 资源.
- [Proofs and Reliable Programming using Coq](https://team.inria.fr/stamp/proofs-and-reliable-programming-using-coq-2022/) - 介绍使用 Coq 开发和验证程序.

### Tutorials and Hints

- [Coq'Art Exercises and Tutorials](https://github.com/coq-community/coq-art) - Coq&#39;Art 书中的 Coq 代码和练习，包括附加教程.
- [Coq in a Hurry](http://cel.archives-ouvertes.fr/inria-00001173) - 介绍如何使用 Coq 定义逻辑概念和函数并对其进行推理.
- [Coq requirements in Common Criteria evaluations](https://www.ssi.gouv.fr/uploads/2014/11/anssi-requirements-on-the-use-of-coq-in-the-context-of-common-criteria-evaluations-v1.1-en.pdf) - 有关如何在高保证应用程序中编写可读且可审查的 Coq 代码的指南.
- [Lemma Overloading](https://github.com/coq-community/lemma-overloading) - 演示使用规范结构进行编程和证明的设计模式.
- [MathComp Tutorial Materials](https://github.com/math-comp/tutorial_material) - 数学组件教程的源代码.
- [Mike Nahas's Coq Tutorial](https://mdnahas.github.io/doc/nahas_tutorial.html) - 使用 Coq 编写形式证明的基础知识.
- [Tricks in Coq](https://github.com/tchajed/coq-tricks) - 难以发现的提示、技巧和功能.
