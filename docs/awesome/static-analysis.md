<div class="github-widget" data-repo="analysis-tools-dev/static-analysis"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!-- 🚨🚨 DON'T EDIT THIS FILE DIRECTLY. Edit `data/tools.yml` instead. 🚨🚨 -->

 <a href="https://analysis-tools.dev/">
   <img width="400px" alt="Analysis Tools" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/logo.png" />
 </a>

该存储库列出了所有编程语言、构建工具、配置文件等的**静态分析工具**.  
官方网站， [analysis-tools.dev](https://analysis-tools.dev/) 基于此存储库，并为每个工具添加排名、用户评论和其他资源，例如视频.

![CI](https://github.com/analysis-tools-dev/static-analysis/workflows/CI/badge.svg)

## What is Static Analysis?

&gt; 静态程序分析是在没有实际执行程序的情况下执行的计算机软件分析—— [Wikipedia](https://en.wikipedia.org/wiki/Static_program_analysis)

 &gt; 作为一名程序员，我这几年做的最重要的事情就是积极追求静态代码分析. 比我用它预防的数​​百个严重错误更有价值的是我对软件可靠性和代码质量的看法发生了变化.  — [John Carmack (Creator of Doom)](https://www.gamasutra.com/view/news/128836/InDepth_Static_Code_Analysis.php)

## Sponsors

如果没有我们赞助商的慷慨支持，这个项目是不可能实现的.

<table>
  <tr>
    <td><a href="https://deepcode.ai"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/deepcode.png" /></a></td>
    <td><a href="https://codescene.io/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/codescene.svg" /></a></td>
    <td><a href="https://r2c.dev/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/r2c.svg" /></a></td>
    <td><a href="https://codiga.io/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/codiga.svg" /></a></td>
    <td><a href="https://offensive360.com/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/offensive360.png" /></a></td>
  </tr>
</table>

如果您也想支持这个项目，请访问我们 [Github sponsors page](https://github.com/sponsors/analysis-tools-dev).

## Meaning of Symbols:

 - :copyright: 代表专有软件. 所有其他工具都是开源的.
 - :information_source: 表示社区不再建议在新项目中使用此工具. 图标链接到讨论问题.
- :warning: 表示此工具超过 1 年未更新，或者 repo 已存档.

非常欢迎请求请求！  
也看看姐妹项目， [awesome-dynamic-analysis](https://github.com/mre/awesome-dynamic-analysis).



<details>
 <summary>显示语言</summary>
  <!-- Please use HTML syntax here so that it works for Github and mkdocs -->
  <ul>
    <li><a href="#abap">ABAP</a></li>
    <li><a href="#ada">Ada</a></li>
    <li><a href="#asm">Assembly</a></li>
    <li><a href="#awk">Awk</a></li>
    <li><a href="#c">C</a></li>
    <li><a href="#csharp">C#</a></li>
    <li><a href="#cpp">C++</a></li>
    <li><a href="#clojure">Clojure</a></li>
    <li><a href="#coffeescript">CoffeeScript</a></li>
    <li><a href="#crystal">Crystal</a></li>
    <li><a href="#dart">Dart</a></li>
    <li><a href="#delphi">Delphi</a></li>
    <li><a href="#dlang">Dlang</a></li>
    <li><a href="#elixir">Elixir</a></li>
    <li><a href="#elm">Elm</a></li>
    <li><a href="#erlang">Erlang</a></li>
    <li><a href="#fsharp">F#</a></li>
    <li><a href="#fortran">Fortran</a></li>
    <li><a href="#go">Go</a></li>
    <li><a href="#groovy">Groovy</a></li>
    <li><a href="#haskell">Haskell</a></li>
    <li><a href="#haxe">Haxe</a></li>
    <li><a href="#java">Java</a></li>
    <li><a href="#javascript">JavaScript</a></li>
    <li><a href="#julia">Julia</a></li>
    <li><a href="#kotlin">Kotlin</a></li>
    <li><a href="#lua">Lua</a></li>
    <li><a href="#matlab">MATLAB</a></li>
    <li><a href="#nim">Nim</a></li>
    <li><a href="#ocaml">Ocaml</a></li>
    <li><a href="#php">PHP</a></li>
    <li><a href="#plsql">PL/SQL</a></li>
    <li><a href="#perl">Perl</a></li>
    <li><a href="#python">Python</a></li>
    <li><a href="#r">R</a></li>
    <li><a href="#ruby">Ruby</a></li>
    <li><a href="#rust">Rust</a></li>
    <li><a href="#sql">SQL</a></li>
    <li><a href="#scala">Scala</a></li>
    <li><a href="#shell">Shell</a></li>
    <li><a href="#swift">Swift</a></li>
    <li><a href="#tcl">Tcl</a></li>
    <li><a href="#typescript">TypeScript</a></li>
    <li><a href="#verilog">Verilog/SystemVerilog</a></li>
    <li><a href="#vim-script">Vim Script</a></li>
    </ul>
</details>




---

## Programming Languages

<h2 id="abap">ABAP</h2>

- [abaplint](https://abaplint.org) — 用于 ABAP 的 Linter，用 TypeScript 编写.
- [abapOpenChecks](https://docs.abapopenchecks.org) — 通过新的可自定义检查增强 SAP Code Inspector.


<h2 id="ada">存在</h2>

- [Codepeer](http://www.adacore.com/codepeer) :copyright: — 检测运行时和逻辑错误.
- [Polyspace for Ada](https://www.mathworks.com/products/polyspace-ada.html) :copyright: — 提供代码验证，证明源代码中不存在溢出、被零除、越界数组访问和某些其他运行时错误.
- [SPARK](https://www.adacore.com/about-spark) :copyright: — Ada 的静态分析和形式验证工具集.


<h2 id="asm">集会</h2>

- [STOKE](https://github.com/StanfordPL/stoke)  :warning: — x86_64 指令集的编程语言不可知随机优化器. 它使用随机搜索来探索所有可能的程序转换的极高维空间.


<h2 id="awk">awk</h2>

- [gawk --lint](https://www.gnu.org/software/gawk/manual/html_node/Options.html) — 对可疑或不可移植到其他 awk 实现的构造发出警告.


<h2 id="c">C</h2>

- [Astrée](https://www.absint.com/astree/index.htm)  :copyright: — Astrée 自动证明 C/C++ 应用程序中不存在运行时错误和无效的并发行为. 它非常适合浮点计算，非常快速且异常精确. 该分析仪还检查 MISRA/CERT/CWE/Adaptive Autosar 编码规则，并支持 ISO 26262、DO-178C A 级和其他安全标准的认证.  Jenkins 和 Eclipse 插件可用.
- [CBMC](http://www.cprover.org/cbmc) — C 程序的有界模型检查器、用户定义的断言、标准断言、几个覆盖率度量分析.
- [clang-tidy](http://clang.llvm.org/extra/clang-tidy) - 铿锵静态分析.
- [clazy](https://github.com/KDE/clazy)  — 基于 Clang 框架的面向 Qt 的静态代码分析器.  clazy 是一个编译器插件，它允许 clang 理解 Qt 语义. 您会收到 50 多个与 Qt 相关的编译器警告，范围从不需要的内存分配到 API 的误用，包括用于自动重构的修复.
- [CMetrics](https://github.com/MetricsGrimoire/CMetrics) — 测量 C 文件的大小和复杂性.
- [CPAchecker](https://cpachecker.sosy-lab.org)  — 用于 C 程序的可配置软件验证的工具. 选择 CPAchecker 这个名称是为了反映该工具基于 CPA 概念并用于检查软件程序.
- [cppcheck](http://cppcheck.sourceforge.net) — C/C++ 代码的静态分析.
- [CppDepend](https://www.cppdepend.com) :warning: :copyright: — 测量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.
- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) — 遵循 Google 风格指南的自动 C++ 检查器.
- [cqmetrics](https://github.com/dspinellis/cqmetrics) — C 代码的质量指标.
- [CScout](https://www.spinellis.gr/cscout) :warning: — C 和 C 预处理器代码的复杂性和质量指标.
- [ESBMC](http://esbmc.org) — ESBMC 是基于可满足性模理论的开源、许可许可、上下文有界模型检查器，用于验证单线程和多线程 C/C++ 程序.
- [flawfinder](http://dwheeler.com/flawfinder/) — 发现可能的安全漏洞.
- [flint++](https://github.com/JossWhittle/FlintPlusPlus) — flint 的跨平台、零依赖端口，这是 Facebook 开发和使用的 C++ lint 程序.
- [Frama-C](http://frama-c.com) — 用于 C 代码的健全且可扩展的静态分析器.
- [Helix QAC](https://www.perforce.com/products/helix-qac)  :copyright: — 嵌入式软件的企业级静态分析. 支持 MISRA、CERT 和 AUTOSAR 编码标准.
- [IKOS](https://github.com/nasa-sw-vnv/ikos) — 基于 LLVM 的 C/C++ 代码的可靠静态分析器.
- [Joern](https://joern.io) — 基于代码属性图的 C/C++ 开源代码分析平台
- [LDRA](https://ldra.com) :copyright: — 一个工具套件，包括静态分析 (TBVISION) 到各种标准，包括 MISRA C 和 C++、JSF++ AV、CWE、CERT C、CERT C++ 和自定义规则.
- [PC-lint](https://www.gimpel.com)  :copyright: — C/C++ 的静态分析. 在 Windows/Linux/MacOS 下本机运行. 分析几乎任何平台的代码，支持 C11/C18 和 C++17.
- [Phasar](https://phasar.org) — 基于 LLVM 的静态分析框架，带有污点和类型状态分析.
- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) :copyright: — 识别 C 和 C++ 嵌入式软件中的运行时错误、并发问题、安全漏洞和其他缺陷.
- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) :copyright: — 提供代码验证，证明 C 和 C++ 源代码中不存在溢出、被零除、越界数组访问以及某些其他运行时错误.
- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) — 在编译时使用 LLVM 分析 C/C++ 代码.
- [splint](http://splint.org) — 注释辅助静态程序检查器.
- [SVF](http://svf-tools.github.io/SVF) — 一种静态工具，可对 C 和 C++ 程序进行可扩展且精确的过程间依赖性分析.
- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) — Vera++ 是用于验证、分析和转换 C++ 源代码的可编程工具.


<h2 id="csharp">C#</h2>

- [.NET Analyzers](https://github.com/DotNetAnalyzers) — 使用 .NET 编译器平台开发分析器（诊断和代码修复）的组织.
- [ArchUnitNET](https://github.com/TNG/ArchUnitNET) — A C# architecture test library to specify and assert architecture rules in C# for automated testing.
- [code-cracker](http://code-cracker.github.io) — An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.
- [CSharpEssentials](https://github.com/DustinCampbell/CSharpEssentials) :warning: — C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features.
- [Designite](http://www.designite-tools.com) :copyright: — Designite 支持检测各种架构、设计和实现异味，计算各种代码质量指标和趋势分析.
- [Gendarme](https://www.mono-project.com/docs/tools+libraries/tools/gendarme) — 宪兵检查包含 ECMA CIL 格式（Mono 和 .NET）代码的程序和库.
- [Infer#](https://github.com/microsoft/infersharp) — InferSharp (also referred to as Infer#) is an interprocedural and  scalable static code analyzer for C#. Via the capabilities of Facebook's Infer,  this tool detects null pointer dereferences and resource leaks.
- [NDepend](http://www.ndepend.com) :copyright: — 测量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.
- [Puma Scan](https://pumasecurity.io) — 当开发团队在 Visual Studio 中编写代码时，Puma Scan 为常见漏洞（XSS、SQLi、CSRF、LDAPi、加密、反序列化等）提供实时安全代码分析.
- [Roslynator](https://github.com/JosefPihrt/Roslynator) — A collection of 190+ analyzers and 190+ refactorings for C#, powered by Roslyn.
- [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) — 基于 Roslyn 与 VS 集成的静态分析器集合.
- [Wintellect.Analyzers](https://github.com/Wintellect/Wintellect.Analyzers) — .NET 编译器平台（“Roslyn”）诊断分析器和代码修复.


<h2 id="cpp">C++</h2>

- [Astrée](https://www.absint.com/astree/index.htm)  :copyright: — Astrée 自动证明 C/C++ 应用程序中不存在运行时错误和无效的并发行为. 它非常适合浮点计算，非常快速且异常精确. 该分析仪还检查 MISRA/CERT/CWE/Adaptive Autosar 编码规则，并支持 ISO 26262、DO-178C A 级和其他安全标准的认证.  Jenkins 和 Eclipse 插件可用.
- [CBMC](http://www.cprover.org/cbmc) — C 程序的有界模型检查器、用户定义的断言、标准断言、几个覆盖率度量分析.
- [clang-tidy](http://clang.llvm.org/extra/clang-tidy) - 铿锵静态分析.
- [clazy](https://github.com/KDE/clazy)  — 基于 Clang 框架的面向 Qt 的静态代码分析器.  clazy 是一个编译器插件，它允许 clang 理解 Qt 语义. 您会收到 50 多个与 Qt 相关的编译器警告，范围从不需要的内存分配到 API 的误用，包括用于自动重构的修复.
- [CMetrics](https://github.com/MetricsGrimoire/CMetrics) — 测量 C 文件的大小和复杂性.
- [cppcheck](http://cppcheck.sourceforge.net) — C/C++ 代码的静态分析.
- [CppDepend](https://www.cppdepend.com) :warning: :copyright: — 测量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.
- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) — 遵循 Google 风格指南的自动 C++ 检查器.
- [cqmetrics](https://github.com/dspinellis/cqmetrics) — C 代码的质量指标.
- [CScout](https://www.spinellis.gr/cscout) :warning: — C 和 C 预处理器代码的复杂性和质量指标.
- [ESBMC](http://esbmc.org) — ESBMC 是基于可满足性模理论的开源、许可许可、上下文有界模型检查器，用于验证单线程和多线程 C/C++ 程序.
- [flawfinder](http://dwheeler.com/flawfinder/) — 发现可能的安全漏洞.
- [flint++](https://github.com/JossWhittle/FlintPlusPlus) — flint 的跨平台、零依赖端口，这是 Facebook 开发和使用的 C++ lint 程序.
- [Frama-C](http://frama-c.com) — 用于 C 代码的健全且可扩展的静态分析器.
- [Helix QAC](https://www.perforce.com/products/helix-qac)  :copyright: — 嵌入式软件的企业级静态分析. 支持 MISRA、CERT 和 AUTOSAR 编码标准.
- [IKOS](https://github.com/nasa-sw-vnv/ikos) — 基于 LLVM 的 C/C++ 代码的可靠静态分析器.
- [Joern](https://joern.io) — 基于代码属性图的 C/C++ 开源代码分析平台
- [LDRA](https://ldra.com) :copyright: — 一个工具套件，包括静态分析 (TBVISION) 到各种标准，包括 MISRA C 和 C++、JSF++ AV、CWE、CERT C、CERT C++ 和自定义规则.
- [PC-lint](https://www.gimpel.com)  :copyright: — C/C++ 的静态分析. 在 Windows/Linux/MacOS 下本机运行. 分析几乎任何平台的代码，支持 C11/C18 和 C++17.
- [Phasar](https://phasar.org) — 基于 LLVM 的静态分析框架，带有污点和类型状态分析.
- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) :copyright: — 识别 C 和 C++ 嵌入式软件中的运行时错误、并发问题、安全漏洞和其他缺陷.
- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) :copyright: — 提供代码验证，证明 C 和 C++ 源代码中不存在溢出、被零除、越界数组访问以及某些其他运行时错误.
- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) — 在编译时使用 LLVM 分析 C/C++ 代码.
- [splint](http://splint.org) — 注释辅助静态程序检查器.
- [SVF](http://svf-tools.github.io/SVF) — 一种静态工具，可对 C 和 C++ 程序进行可扩展且精确的过程间依赖性分析.
- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) — Vera++ 是用于验证、分析和转换 C++ 源代码的可编程工具.


<h2 id="clojure">Clojure</h2>

- [clj-kondo](https://github.com/borkdude/clj-kondo)  — Clojure 代码的 linter 激发了快乐. 它会在您键入时通知您潜在的错误.


<h2 id="coffeescript">咖啡脚本</h2>

- [coffeelint](http://www.coffeelint.org) — 帮助保持 CoffeeScript 代码干净和一致的样式检查器.


<h2 id="crystal">水晶</h2>

- [ameba](https://crystal-ameba.github.io) — Crystal 的静态代码分析工具.
- [crystal](https://crystal-lang.org) — Crystal 编译器具有内置的 linting 功能.


<h2 id="dart">镖</h2>

- [Dart Code Metrics](https://pub.dev/packages/dart_code_metrics)  — Dart 的额外 linter. 报告代码指标，检查反模式并为 Dart 分析器提供额外的规则.
- [effective_dart](https://pub.dev/packages/effective_dart) — 与 Effective Dart 中的指南相对应的 Linter 规则
- [lint](https://github.com/passsy/dart-lint)  — 一套针对 Dart 和 Flutter 项目的自以为是的、社区驱动的 lint 规则. 像迂腐但更严格
- [Linter for dart](https://dart-lang.github.io/linter) — Dart 的样式 linter.


<h2 id="delphi">德尔福</h2>

- [Fix Insight](https://www.tmssoftware.com/site/fixinsight.asp)  :copyright: — 用于静态代码分析的免费 IDE 插件.  _Pro_ 版本包括用于自动化目的的命令行工具.
- [Pascal Analyzer](https://peganza.com/products_pal.html)  :copyright: — 带有大量报告的静态代码分析工具. 提供有限报告的免费 _Lite_ 版本.
- [Pascal Expert](https://peganza.com/products_pex.html)  :copyright: — 用于代码分析的 IDE 插件. 包括 Pascal Analyzer 报告功能的子集，可用于 Delphi 2007 版及更高版本.


<h2 id="dlang">俚语</h2>

- [D-scanner](https://github.com/dlang-community/D-Scanner) — D-Scanner 是一个分析 D 源代码的工具.


<h2 id="elixir">灵药</h2>

- [credo](https://github.com/rrrene/credo) — 专注于代码一致性和教学的静态代码分析工具.
- [dialyxir](https://github.com/jeremyjh/dialyxir) — 在 Elixir 项目中混合任务以简化 Dialyzer 的使用.
- [sobelow](https://github.com/nccgroup/sobelow) — Phoenix 框架的以安全为中心的静态分析.


<h2 id="elm">榆树</h2>

- [elm-analyse](https://stil4m.github.io/elm-analyse) :warning: — 一种允许您分析 Elm 代码、识别缺陷并应用最佳实践的工具.
- [elm-review](https://package.elm-lang.org/packages/jfmengels/elm-review/latest) — 分析整个 Elm 项目，重点关注用 Elm 编写的可共享和自定义规则，这些规则增加了 Elm 编译器无法提供的保证.


<h2 id="erlang">Erlang</h2>

- [dialyzer](https://www.erlang.org/doc/man/dialyzer.html)  — DIALYZER，ERlang 程序的差异分析器.  Dialyzer 是一个静态分析工具，用于识别软件差异，例如明确的类型错误、由于编程错误而死或无法访问的代码，以及在单个 Erlang 模块或整个（一组）应用程序中的不必要测试.
 Dialyzer 从调试编译的 BEAM 字节码或 Erlang 源代码开始分析. 报告差异的文件和行号以及差异的指示.  Dialyzer 的分析基于成功类型的概念，该概念允许声音警告（无误报）.
- [elvis](https://github.com/inaka/elvis) — Erlang Style Reviewer.
- [Primitive Erlang Security Tool (PEST)](https://github.com/okeuday/pest) — 对 Erlang 源代码进行基本扫描并报告任何可能导致 Erlang 源代码不安全的函数调用的工具.


<h2 id="fsharp">F#</h2>

- [FSharpLint](http://fsprojects.github.io/FSharpLint) — Lint tool for F#.


<h2 id="fortran">Fortran</h2>

- [i-Code CNES for Fortran](https://github.com/lequal/i-CodeCNES) :warning: — Fortran 77、Fortran 90 和 Shell 的开源静态代码分析工具.


<h2 id="go">走</h2>

- [aligncheck](https://gitlab.com/opennota/check) — 查找低效打包的结构.
- [bodyclose](https://github.com/timakin/bodyclose) — 检查 HTTP 响应正文是否已关闭.
- [deadcode](https://github.com/tsenart/deadcode) — 查找未使用的代码.
- [dingo-hunter](https://github.com/nickng/dingo-hunter) :warning: — 用于查找 Go 死锁的静态分析器.
- [dogsled](https://github.com/alexkohler/dogsled) — 查找具有太多空白标识符的分配/声明.
- [dupl](https://github.com/mibk/dupl) :warning: — 报告可能重复的代码.
- [errcheck](https://github.com/kisielk/errcheck) — 检查是否使用了错误返回值.
- [errwrap](https://github.com/fatih/errwrap)  — 使用新的 %w 动词指令包装并修复 Go 错误. 此工具分析 fmt.Errorf() 调用并报告包含与 Go v1.13 中引入的新 %w 动词指令不同的动词指令的调用. 它还能够重写调用以使用新的 %w wrap 动词指令.
- [flen](https://github.com/lafolle/flen) — 获取 Go 包中函数长度的信息.
- [Go Meta Linter](https://github.com/alecthomas/gometalinter)  :warning: — 同时运行 Go lint 工具并标准化它们的输出. 对新项目使用 `golangci-lint`.
- [go tool vet --shadow](https://golang.org/cmd/vet#hdr-Shadowed_variables) — 报告可能被无意遮蔽的变量.
- [go vet](https://golang.org/cmd/vet) — 检查 Go 源代码并报告可疑.
- [go-consistent](https://github.com/Quasilyte/go-consistent) :warning: — 帮助您使 Go 程序更加一致的分析器.
- [go-critic](https://github.com/go-critic/go-critic) — Go 源代码 linter，维护当前未在其他 linter 中实现的检查.
- [go/ast](https://golang.org/pkg/go/ast) — 包 ast 声明了用于表示 Go 包的语法树的类型.
- [gochecknoglobals](https://github.com/leighmcculloch/gochecknoglobals) — 检查是否存在全局变量.
- [goconst](https://github.com/jgautheron/goconst) — 查找可以被常量替换的重复字符串.
- [gocyclo](https://github.com/fzipp/gocyclo) — 计算 Go 源代码中函数的圈复杂度.
- [gofmt -s](https://golang.org/cmd/gofmt) — 检查代码是否格式正确且无法进一步简化.
- [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) — 检查丢失或未引用的包导入.
- [gokart](https://github.com/praetorian-inc/gokart)  — Golang 安全分析，重点是尽量减少误报. 它能够跟踪变量和函数参数的来源，以确定输入源是否安全.
- [GolangCI-Lint](https://golangci-lint.run) — `Go Meta Linter` 的替代方案：GolangCI-Lint 是一个 linter 聚合器.
- [golint](https://github.com/golang/lint) — 打印出 Go 源代码中的编码风格错误.
- [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) — 同时运行许多 linter 并将它们的输出标准化为报告.
- [goroutine-inspect](https://github.com/linuxerwang/goroutine-inspect) — 分析 Golang goroutine 转储的交互式工具.
- [gosec (gas)](https://securego.io) — 通过扫描 Go AST 检查源代码是否存在安全问题.
- [gotype](https://pkg.go.dev/golang.org/x/tools/cmd/gotype) — 类似于 Go 编译器的句法和语义分析.
- [ineffassign](https://github.com/gordonklaus/ineffassign) — 检测 Go 代码中的无效分配.
- [interfacer](https://github.com/mvdan/interfacer) :warning: — 建议可以使用的更窄的接口.
- [lll](https://github.com/walle/lll) :warning: — 报告长行.
- [maligned](https://github.com/mdempsky/maligned) — 检测如果对它们的字段进行排序将占用更少内存的结构.
- [misspell](https://github.com/client9/misspell) — 查找常见拼写错误的英语单词.
- [nakedret](https://github.com/alexkohler/nakedret) — 寻找赤裸裸的回报.
- [nargs](https://github.com/alexkohler/nargs) — 查找函数声明中未使用的参数.
- [prealloc](https://github.com/alexkohler/prealloc) — 查找可能被预分配的切片声明.
- [Reviewdog](https://github.com/haya14busa/reviewdog) — 在任何代码托管服务中发布来自任何 linter 的评论评论的工具.
- [revive](https://revive.run)  — Go 的快速、可配置、可扩展、灵活和漂亮的 linter. 直接替换 golint.
- [safesql](https://github.com/stripe/safesql) — Golang 的静态分析工具，可防止 SQL 注入.
- [shisho](https://docs.shisho.dev/)  — 专为开发人员和安全团队设计的轻量级静态代码分析器. 它允许您使用类似于 sed 的直观 DSL 分析和转换源代码，但用于代码.
- [staticcheck](https://staticcheck.io) — Go 静态分析，专门用于查找错误、简化代码和提高性能.
- [structcheck](https://gitlab.com/opennota/check) — 查找未使用的结构字段.
- [structslop](https://github.com/orijtech/structslop) — Go 的静态分析器，建议重新排列结构字段以提供最大的空间/分配效率
- [test](http://golang.org/pkg/testing) — 从 stdlib 测试模块显示测试失败的位置.
- [unconvert](https://github.com/mdempsky/unconvert) — 检测冗余类型转换.
- [unparam](https://github.com/mvdan/unparam) — 查找未使用的函数参数.
- [varcheck](https://gitlab.com/opennota/check) — 查找未使用的全局变量和常量.
- [wsl](https://github.com/bombsimon/wsl) — 在正确的位置强制使用空行.


<h2 id="groovy">时髦的</h2>

- [CodeNarc](https://codenarc.github.io/CodeNarc) — Groovy 源代码的静态分析工具，可以监控和执行许多编码标准和最佳实践.


<h2 id="haskell">哈斯克尔</h2>

- [brittany](https://github.com/lspitzner/brittany) — Haskell 源代码格式化程序
- [HLint](https://github.com/ndmitchell/hlint) — HLint 是一个建议对 Haskell 代码进行改进的工具.
- [Liquid Haskell](https://ucsd-progsys.github.io/liquidhaskell-blog/) — Liquid Haskell 是 Haskell 程序的细化类型检查器.
- [Stan](https://kowainik.github.io/projects/stan) — Stan 是一个命令行工具，用于分析 Haskell 项目并以有用的方式输出发现的漏洞，并为检测到的问题提供可能的解决方案.
- [Weeder](https://github.com/ocharles/weeder) — 在 Haskell 代码中检测死导出或包导入的工具.


<h2 id="haxe">斧头</h2>

- [Haxe Checkstyle](http://haxecheckstyle.github.io/docs/haxe-checkstyle/home.html) — 一种静态分析工具，可帮助开发人员编写符合编码标准的 Haxe 代码.


<h2 id="java">爪哇</h2>

- [Checker Framework](https://checkerframework.org) — Java 的可插入类型检查.
- [checkstyle](https://checkstyle.org) — 检查 Java 源代码是否符合代码标准或一组验证规则（最佳实践）.
- [ck](https://github.com/mauricioaniche/ck) — 通过处理源 Java 文件计算 Chidamber 和 Kemerer 面向对象的指标.
- [ckjm](http://www.spinellis.gr/sw/ckjm) — 通过处理已编译 Java 文件的字节码来计算 Chidamber 和 Kemerer 面向对象的指标.
- [CogniCrypt](https://www.eclipse.org/cognicrypt) — 检查 Java 源代码和字节码是否错误地使用了加密 API.
- [DesigniteJava](http://www.designite-tools.com/designitejava) :copyright: — DesigniteJava 支持检测各种架构、设计和实现气味以及计算各种代码质量指标.
- [Doop](https://bitbucket.org/yanniss/doop)  — Doop 是一个声明式框架，用于对 Java/Android 程序进行静态分析，以指针分析算法为中心.  Doop 提供了种类繁多的分析以及周围的脚手架来运行端到端分析（事实生成、处理、统计等）.
- [Error-prone](https://errorprone.info) — 将常见的 Java 错误捕获为编译时错误.
- [fb-contrib](http://fb-contrib.sourceforge.net) — 带有附加错误检测器的 FindBugs 插件.
- [forbidden-apis](https://github.com/policeman-tools/forbidden-apis)  — 检测并禁止对特定方法/类/字段的调用（例如从没有字符集的文本流中读取）.  Maven/Gradle/Ant 兼容.
- [google-java-format](https://github.com/google/google-java-format) — 谷歌风格重新格式化.
- [HuntBugs](https://github.com/amaembo/huntbugs) :warning: — 基于 Procyon 编译器工具的字节码静态分析器工具，旨在取代 FindBugs.
- [IntelliJ IDEA](https://www.jetbrains.com/idea) :copyright: — 捆绑了许多对 Java 和 Kotlin 的检查，并包括用于重构、格式化等的工具.
- [JArchitect](https://www.jarchitect.com) :copyright: — 测量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.
- [JBMC](https://www.cprover.org/jbmc) — Java（字节码）的有界模型检查器，验证用户定义的断言、标准断言、几个覆盖率度量分析.
- [NullAway](https://github.com/uber/NullAway)  — 基于类型的空指针检查器，构建时间开销低； 一个 [Error Prone](http://errorprone.info/) 插入.
- [OWASP Dependency Check](https://owasp.org/www-project-dependency-check) — 检查已知的、公开披露的漏洞的依赖关系.
- [qulice](https://www.qulice.com) — 结合了一些（预配置的）静态分析工具（checkstyle、PMD、Findbugs，...）.
- [Reshift](https://www.reshiftsecurity.com) :copyright: — 用于检测和管理 Java 安全漏洞的源代码分析工具.
- [Soot](https://soot-oss.github.io/soot) — 用于分析和转换 Java 和 Android 应用程序的框架.
- [Spoon](http://spoon.gforge.inria.fr)  — Spoon 是一个元编程库，用于分析和转换 Java 源代码（包括 Java 9、10、11、12、13、14）. 它解析源文件以构建具有强大分析和转换 API 的精心设计的 AST. 可以集成在 Maven 和 Gradle 中.
- [SpotBugs](https://spotbugs.github.io)  — SpotBugs 是 FindBugs 的继任者. 一种静态分析工具，用于查找 Java 代码中的错误.
- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  — 用于从静态代码分析中解析报告文件的 Java 库. 被一堆 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="javascript">JavaScript</h2>

- [aether](http://aetherjs.com) :warning: — 在节点或浏览器中，Lint、分析、规范化、转换、沙箱、运行、单步执行和可视化用户 JavaScript.
- [Closure Compiler](https://developers.google.com/closure/compiler) — 一种用于提高效率、减小大小并在 JavaScript 文件中提供代码警告的编译器工具.
- [ClosureLinter](https://github.com/google/closure-linter)  :warning: — 确保您项目的所有 JavaScript 代码都遵循 Google JavaScript 样式指南中的指南. 它还可以自动修复许多常见错误.
- [complexity-report](https://github.com/escomplex/complexity-report) :warning: — JavaScript 项目的软件复杂性分析.
- [DeepScan](https://deepscan.io) :copyright: — 针对运行时错误和质量问题而不是编码约定的 JavaScript 分析器.
- [es6-plato](https://github.com/the-simian/es6-plato) — 可视化 JavaScript (ES6) 源代码复杂性.
- [escomplex](https://github.com/jared-stilwell/escomplex) :warning: — JavaScript 系列抽象语法树的软件复杂性分析.
- [Esprima](https://esprima.org) — 用于多用途分析的 ECMAScript 解析基础架构.
- [flow](https://flow.org) — JavaScript 的静态类型检查器.
- [hegel](https://hegel.js.org) — JavaScript 的静态类型检查器，偏向于类型推断和强类型系统.
- [jshint](https://jshint.com/about) [:information_source:](https://github.com/analysis-tools-dev/static-analysis/blob/master/<https://github.com/analysis-tools-dev/static-analysis/issues/223>) — 检测 JavaScript 代码中的错误和潜在问题，并强制执行团队的编码约定.
- [JSLint](https://github.com/douglascrockford/JSLint) [:information_source:](https://github.com/analysis-tools-dev/static-analysis/blob/master/<https://github.com/analysis-tools-dev/static-analysis/issues/223>) — JavaScript 代码质量工具.
- [JSPrime](http://dpnishant.github.io/jsprime) :warning: — 静态安全分析工具.
- [NodeJSScan](https://opensecurity.in)  — 由 libsast 和 semgrep 提供支持的 Node.js 应用程序的静态安全代码扫描程序，构建在 njsscan cli 工具上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.
- [plato](https://github.com/es-analysis/plato) :warning: — 可视化 JavaScript 源代码的复杂性.
- [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer) — Web 组件的静态分析框架.
- [retire.js](http://retirejs.github.io/retire.js) — 扫描程序检测到使用具有已知漏洞的 JavaScript 库.
- [RSLint](http://rslint.org/) — 用 Rust 编写的 (WIP) JavaScript linter，旨在尽可能快、可定制且易于使用.
- [standard](http://standardjs.com) — 检查 Javascript 样式指南问题的 npm 模块.
- [tern](https://ternjs.net) — 一种 JavaScript 代码分析器，用于深度、跨编辑器语言支持.
- [TypL](https://typl.dev) — 使用 TypL，您只需编写完全标准的 JS，该工具通过强大的推理来计算您的类型.
- [xo](https://github.com/xojs/xo)  — 自以为是但可配置的 ESLint 包装器，其中包含许多好东西. 强制执行严格和可读的代码.
- [yardstick](https://github.com/calmh/yardstick) :warning: — Javascript 代码指标.


<h2 id="julia">朱莉娅</h2>

- [StaticLint](https://github.com/julia-vscode/StaticLint.jl) — Julia 的静态代码分析


<h2 id="kotlin">科特林</h2>

- [detekt](https://detekt.github.io/detekt) — Kotlin 代码的静态代码分析.
- [diktat](https://analysis-dev.github.io/diktat) — Kotlin 的严格编码标准和检测和自动修复代码异味的 linter.
- [ktlint](https://ktlint.github.io) — 带有内置格式化程序的防自行车脱落 Kotlin linter.


<h2 id="lua">拿</h2>

- [luacheck](https://github.com/mpeterv/luacheck) :warning: — Lua 代码的 linting 和静态分析工具.
- [lualint](https://github.com/philips/lualint) — lualint 对 Lua 源代码中的全局变量使用执行基于 luac 的静态分析.
- [Luanalysis](https://plugins.jetbrains.com/plugin/14698-luanalysis) :warning: — 用于静态类型 Lua 开发的 IDE.


<h2 id="matlab">MATLAB</h2>

- [mlint](https://mathworks.com/help/matlab/ref/mlint.html) :copyright: — 检查 MATLAB 代码文件是否存在可能的问题.


<h2 id="nim">Nim</h2>

- [DrNim](https://nim-lang.org/docs/drnim.html) — DrNim 将 Nim 前端与 Z3 证明引擎相结合，以允许验证/验证用 Nim 编写的软件.
- [nimfmt](https://github.com/FedericoCeratto/nimfmt) — Nim 代码格式化程序 / linter / 样式检查器


<h2 id="ocaml">奥卡姆</h2>

- [Sys](https://github.com/PLSysSec/sys)  — 用于在（浏览器）代码中查找错误的静态/符号工具. 它使用 LLVM AST 来查找诸如未初始化内存访问之类的错误.
- [VeriFast](https://github.com/verifast/verifast)  — 一种用于对单线程和多线程 C 和 Java 程序的正确性属性进行模块化形式验证的工具，这些程序用分离逻辑编写的前置条件和后置条件进行注释. 为了表达丰富的规范，程序员可以定义归纳数据类型、在这些数据类型上的原始递归纯函数以及抽象分离逻辑谓词.


<h2 id="php">PHP</h2>

- [churn-php](https://github.com/bmitch/churn-php) — 帮助发现重构的优秀候选者.
- [dephpend](https://github.com/mihaeu/dephpend) — 依赖分析工具.
- [deprecation-detector](https://github.com/sensiolabs-de/deprecation-detector) — 查找已弃用 (Symfony) 代码的用法.
- [deptrac](https://github.com/sensiolabs-de/deptrac) — 对软件层之间的依赖关系实施规则.
- [DesignPatternDetector](https://github.com/Halleck45/DesignPatternDetector) — 检测 PHP 代码中的设计模式.
- [EasyCodingSt和ard](https://www.tomasvotruba.com/blog/2017/05/03/combine-power-of-php-code-sniffer-和-php-cs-fixer-in-3-lines) - 结合 [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 和 [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).
- [Enlightn](https://www.laravel-enlightn.com/)  — Laravel 应用程序的静态和动态分析工具，它提供建议以提高 Laravel 应用程序的性能、安全性和代码可靠性. 包含 120 个自动检查.
- [exakat](https://www.exakat.io) — PHP 的自动代码审查引擎.
- [GrumPHP](https://github.com/phpro/grumphp) — 在每次提交时检查代码.
- [larastan](https://github.com/nunomaduro/larastan)  — 向 Laravel 添加静态分析，提高开发人员的工作效率和代码质量. 它是 PHPStan 的包装器.
- [Mondrian](http://trismegiste.github.io/Mondrian) :warning: — 一组使用图论的静态分析和重构工具.
- [Nitpick CI](https://nitpick-ci.com) :copyright: — 自动 PHP 代码审查.
- [parallel-lint](https://github.com/php-parallel-lint/PHP-Parallel-Lint) — 这个工具检查 PHP 文件的语法比串行检查更快，输出更漂亮.
- [Parse](https://github.com/psecio/parse) — 静态安全扫描器.
- [pdepend](https://pdepend.org) — 计算 PHP 代码的圈复杂度等软件指标.
- [phan](https://github.com/phan/phan/wiki) — 来自 etsy 的现代静态分析器.
- [PHP Architecture Tester](https://github.com/carlosas/phpat) — 易于使用的 PHP 架构测试工具.
- [PHP Assumptions](https://github.com/rskuipers/php-assumptions) — 检查弱假设.
- [PHP Coding Standards Fixer](https://cs.symfony.com) — 根据 PSR-1、PSR-2 和 Symfony 标准等标准修复您的代码.
- [PHP Insights](https://phpinsights.com)  — 从您的控制台即时检查 PHP 质量. 代码质量和编码风格分析以及代码架构及其复杂性的概述.
- [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-) — PHP 的静态代码分析器.
- [PHP Refactoring Browser](http://qafoolabs.github.io/php-refactoring-browser) — 重构助手.
- [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) — 根据语义版本建议下一个版本.
- [PHP-Parser](https://github.com/nikic/PHP-Parser) — 用 PHP 编写的 PHP 解析器.
- [php-speller](https://github.com/mekras/php-speller) — PHP 拼写检查库.
- [PHP-Token-Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) :warning: — 模拟 PHP 内部反射的库.
- [php7cc](https://github.com/sstalle/php7cc) :warning: — PHP 7 兼容性检查器.
- [php7mar](https://github.com/Alexia/php7mar) :warning: — 帮助开发人员将他们的代码快速移植到 PHP 7.
- [PHP_CodeSniffer](https://pear.php.net/package/PHP_CodeSniffer) — 检测违反一组定义的编码标准.
- [phpca](https://github.com/wapmorgan/PhpCodeAnalyzer) :warning: — 查找非内置扩展的用法.
- [phpcpd](https://github.com/sebastianbergmann/phpcpd) — PHP 代码的复制/粘贴检测器.
- [phpdcd](https://github.com/sebastianbergmann/phpdcd) :warning: — PHP 代码的死代码检测器 (DCD).
- [PhpDependencyAnalysis](https://mamuz.github.io/PhpDependencyAnalysis) :warning: — 为项目构建依赖关系图.
- [PhpDeprecationDetector](https://github.com/wapmorgan/PhpDeprecationDetector)  — PHP 代码分析器，用于在较新的解释器版本中搜索已弃用功能的问题. 它发现已删除的对象（函数、变量、常量和 ini 指令）、不推荐使用的函数功能以及禁止使用的名称或技巧（例如，较新版本中的保留标识符）.
- [phpdoc-to-typehint](https://github.com/dunglas/phpdoc-to-typehint) :warning: — 使用 PHPDoc 注释向现有 PHP 项目添加标量类型提示和返回类型.
- [phpDocumentor](https://www.phpdoc.org) — 分析 PHP 源代码以生成文档.
- [phploc](https://github.com/sebastianbergmann/phploc) — 用于快速测量 PHP 项目大小和分析结构的工具.
- [PHPMD](https://phpmd.org) — 查找代码中可能存在的错误.
- [PhpMetrics](http://www.phpmetrics.org) — 计算和可视化各种代码质量指标.
- [phpmnd](https://github.com/povils/phpmnd) — 帮助检测幻数.
- [PHPQA](https://edgedesigncz.github.io/phpqa) — 用于运行 QA 工具（phploc、phpcpd、phpcs、pdepend、phpmd、phpmetrics）的工具.
- [phpqa - jakzal](https://github.com/jakzal/phpqa) — 在一个容器中提供多种 PHP 静态分析工具.
- [phpqa - jmolivas](https://github.com/jmolivas/phpqa) — PHPQA 一体化分析器 CLI 工具.
- [phpsa](https://github.com/ovr/phpsa) :warning: — PHP 的静态分析工具.
- [PHPStan](https://phpstan.org) — PHP 静态分析工具 - 无需运行即可发现代码中的错误！
- [Progpilot](https://github.com/designsecurity/progpilot) — 出于安全目的的静态分析工具.
- [Psalm](https://psalm.dev) — 用于在 PHP 应用程序中查找类型错误的静态分析工具.
- [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) :warning: — 可视化指标和源代码.
- [Symfony Insight](https://insight.symfony.com/) :copyright: — 检测安全风险、发现错误并为 PHP 项目提供可操作的指标.
- [Tuli](https://github.com/ircmaxell/Tuli) — 静态分析引擎.
- [twig-lint](https://github.com/asm89/twig-lint) — twig-lint 是你的 twig 文件的 lint 工具.
- [WAP](https://securityonline.info/owasp-wap-web-application-protection-project) — 用于检测和纠正 PHP（4.0 或更高版本）Web 应用程序中的输入验证漏洞并通过结合静态分析和数据挖掘来预测误报的工具.


<h2 id="plsql">PL/SQL</h2>

- [ZPA](https://felipezorzo.com.br/zpa/)  — Z PL/SQL Analyzer (ZPA) 是用于 PL/SQL 和 Oracle SQL 的可扩展代码分析器. 它可以与 SonarQube 集成.


<h2 id="perl">Perl</h2>

- [Perl::Critic](https://metacpan.org/pod/Perl::Critic) — Critique Perl 源代码以获得最佳实践.


<h2 id="python">Python</h2>

- [bandit](https://bandit.readthedocs.io/en/latest) — 在 Python 代码中查找常见安全问题的工具.
- [bellybutton](https://github.com/hchasestevens/bellybutton) — 支持自定义项目特定规则的 linting 引擎.
- [Black](https://black.readthedocs.io/en/stable) — 毫不妥协的 Python 代码格式化程序.
- [Bowler](https://pybowler.io/)  — 现代 Python 的安全代码重构.  Bowler 是一个重构工具，用于在语法树级别操作 Python. 它支持安全、大规模的代码修改，同时保证生成的代码可以编译和运行. 它提供了简单的命令行界面和 Python 中的流利的 API，用于在代码中生成复杂的代码修改.
- [ciocheck](https://github.com/ContinuumIO/ciocheck)  :warning: — Linter、格式化程序和测试套件助手. 作为 linter，它是 `pep8`、`pydocstyle`、`flake8` 和 `pylint` 的包装器.
- [cohesion](https://github.com/mschwager/cohesion) :warning: — 一个测量 Python 类凝聚力的工具.
- [Dlint](https://github.com/dlint-py/dlint) — 确保 Python 代码安全的工具.
- [fixit](https://pypi.org/project/fixit) — 用于为源代码创建 lint 规则和相应的自动修复的框架.
- [flake8](https://github.com/PyCQA/flake8) — `pyflakes`、`pycodestyle` 和 `mccabe` 的​​包装器.
- [InspectorTiger](https://github.com/thg-consulting/it)  :warning: — IT，Inspector Tiger，是一个现代的 Python 代码审查工具/框架. 它带有一堆预定义的处理程序，可以警告您改进和可能的错误. 除了这些处理程序之外，您还可以编写自己的或使用社区处理程序.
- [jedi](https://jedi.readthedocs.io/en/latest) — Python 的自动完成/静态分析库.
- [linty fresh](https://github.com/lyft/linty_fresh) — 解析 lint 错误并将它们作为对拉取请求的评论报告给 Github.
- [mccabe](https://pypi.org/project/mccabe) — 检查 McCabe 复杂性.
- [multilint](https://github.com/adamchainz/multilint) :warning: — `flake8`、`isort` 和 `modernize` 的包装器.
- [mypy](http://www.mypy-lang.org) — A static type checker that aims to combine the benefits of duck typing and static typing, frequently used with [MonkeyType](https://github.com/Instagram/MonkeyType).
- [prospector](https://github.com/PyCQA/prospector) — `pylint`、`pep8`、`mccabe` 等的封装.
- [py-find-injection](https://github.com/uber/py-find-injection) :warning: — 在 Python 代码中查找 SQL 注入漏洞.
- [pyanalyze](https://pyanalyze.readthedocs.io/en/latest/)  — 一种以编程方式检测 Python 代码中常见错误的工具，例如对未定义变量的引用和类型错误. 它可以扩展以添加其他规则并执行特定于特定功能的检查.
- [PyCodeQual](https://pycodequ.al)  :copyright: — PyCodeQual 让您深入了解复杂性和错误风险. 它将自动审查添加到您的拉取请求中.
- [pycodestyle](https://pycodestyle.pycqa.org/en/latest) —（以前称为 `pep8`）根据 PEP 8 中的一些样式约定检查 Python 代码.
- [pydocstyle](http://www.pydocstyle.org) — 检查是否符合 Python 文档字符串约定.
- [pyflakes](https://pypi.org/project/pyflakes) — 检查 Python 源文件是否有错误.
- [pylint](http://pylint.pycqa.org/en/latest)  — 寻找编程错误，帮助执行编码标准并嗅探一些代码异味. 它还包括`pyreverse`（一个UML图生成器）和`symilar`（一个相似性检查器）.
- [pyre-check](https://pyre-check.org) — 用于大型 Python 代码库的快速、可扩展的类型检查器.
- [pyright](https://github.com/Microsoft/pyright) — Python 的静态类型检查器，旨在解决现有工具（如 mypy）中的空白.
- [pyroma](https://github.com/regebro/pyroma) — 评价 Python 项目在多大程度上符合 Python 打包生态系统的最佳实践，并列出可以改进的问题.
- [Pysa](https://pyre-check.org/docs/pysa-basics.html) — 基于 Facebook 的 pyre-check 的工具，用于识别 Python 代码中的潜在安全问题，并通过污点分析识别.
- [PyT - Python Taint](https://github.com/python-security/pyt) :warning: — 用于检测 Python Web 应用程序中的安全漏洞的静态分析工具.
- [pytype](https://google.github.io/pytype) — Python 代码的静态类型分析器.
- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode)  :warning: — 自动代码审查和修复. 它可以帮助您跟踪软件项目中的问题和指标，并且可以轻松扩展以支持新类型的分析.
- [radon](https://radon.readthedocs.io/en/latest) — 从源代码计算各种指标的 Python 工具.
- [unimport](https://unimport.hakancelik.dev) — linter，格式化程序，用于查找和删除未使用的导入语句.
- [vulture](https://github.com/jendrikseipp/vulture) — Find unused classes, functions and variables in Python code.
- [wemake-python-styleguide](https://wemake-python-stylegui.de) — 有史以来最严格、最自以为是的 python linter.
- [wily](https://github.com/tonybaloney/wily) — 用于归档、探索和绘制 Python 源代码复杂性的命令行工具.
- [xenon](https://xenon.readthedocs.io) — 使用监控代码复杂度 [`radon`](https://github.com/rubik/radon).


<h2 id="r">R</h2>

- [cyclocomp](https://github.com/MangoTheCat/cyclocomp) — 量化 R 函数/表达式的圈复杂度.
- [goodpractice](http://mangothecat.github.io/goodpractice) — 分析 R 包的源代码并提供最佳实践建议.
- [lintr](https://github.com/jimhester/lintr) — R 的静态代码分析.
- [styler](https://styler.r-lib.org) — R 源代码文件的格式化和 R 代码的漂亮打印.


<h2 id="ruby">红宝石</h2>

- [brakeman](https://brakemanscanner.org) — 用于 Ruby on Rails 应用程序的静态分析安全漏洞扫描程序.
- [bundler-audit](https://github.com/rubysec/bundler-audit) — 审计 Gemfile.lock 中报告的具有安全漏洞的 gem [Ruby Advisory Database](https://github.com/rubysec/ruby-advisory-db).
- [cane](https://github.com/square/cane) :warning: — 代码质量阈值检查作为构建的一部分.
- [dawnscanner](https://github.com/thesp0nge/dawnscanner)  — 用于 Ruby 编写的 Web 应用程序的静态分析安全扫描器. 它支持 Sinatra、Padrino 和 Ruby on Rails 框架.
- [ERB Lint](https://github.com/Shopify/erb-lint) — 整理您的 ERB 或 HTML 文件
- [Fasterer](https://github.com/DamirSvrtan/fasterer) — 常见的 Ruby 习语检查器.
- [flay](https://ruby.sadi.st/Flay.html) — Flay 分析代码的结构相似性.
- [flog](https://ruby.sadi.st/Flog.html)  — Flog 在一个易于阅读的痛苦报告中报告了最受折磨的代码. 分数越高，代码越痛苦.
- [Fukuzatsu](https://github.com/CoralineAda/fukuzatsu)  — 用于测量 Ruby 类文件中代码复杂性的工具. 它的分析基于圈复杂度算法生成分数，没有添加“意见”.
- [laser](https://github.com/michaeledgar/laser) :warning: — Ruby 代码的静态分析和样式 linter.
- [pelusa](https://github.com/codegram/pelusa) — 静态分析 Lint 类型的工具，用于改进您的 OO Ruby 代码.
- [quality](https://github.com/apiology/quality) :warning: — 使用社区工具对您的代码进行质量检查，并确保您的数字不会随着时间的推移而变得更糟.
- [Querly](https://github.com/soutaro/querly) — Ruby 的基于模式的检查工具.
- [Railroader](https://railroader.org) :warning: — 用于 Ruby on Rails 应用程序的开源静态分析安全漏洞扫描器.
- [rails_best_practices](https://rails-bestpractices.com) — Rails 项目的代码度量工具
- [reek](https://github.com/troessner/reek) — Ruby 的代码气味检测器.
- [RuboCop](https://docs.rubocop.org/rubocop) — 基于社区 Ruby 风格指南的 Ruby 静态代码分析器.
- [Rubrowser](https://github.com/blazeeboy/rubrowser) — Ruby 类交互式依赖图生成器.
- [ruby-lint](http://code.yorickpeterse.com/ruby-lint/latest) :warning: — Static code analysis for Ruby.
- [rubycritic](https://github.com/whitesmith/rubycritic) — Ruby 代码质量报告员.
- [rufo](https://github.com/ruby-formatter/rufo) — 自以为是的 ruby​​ 格式化程序，旨在通过命令行用作文本编辑器插件，以在保存或按需自动格式化文件.
- [Saikuro](https://metricfu.github.io/Saikuro) :warning: — Ruby 圈复杂度分析器.
- [SandiMeter](https://rubygems.org/gems/sandi_meter) :warning: — 用于检查 Ruby 代码是否符合 Sandi Metz 规则的静态分析工具.
- [Sorbet](https://sorbet.org) — 专为 Ruby 设计的快速、强大的类型检查器.
- [Standard Ruby](https://github.com/testdouble/standard) — Ruby 风格指南，带有 linter 和自动代码修复器
- [Steep](https://github.com/soutaro/steep) — Ruby 的渐进式打字.


<h2 id="rust">锈</h2>

- [C2Rust](https://c2rust.com)  — C2Rust 帮助您将符合 C99 的代码迁移到 Rust. 翻译器（或转译器）生成不安全的 Rust 代码，这些代码与输入的 C 代码非常相似.
- [cargo udeps](https://github.com/est31/cargo-udeps)  — 在 Cargo.toml 中查找未使用的依赖项. 它要么打印出一个列出箱子的“未使用的箱子”行，要么打印出一行说明没有未使用的箱子.
- [cargo-audit](https://rustsec.org) — 审核 Cargo.lock 以查找具有安全漏洞的 crate 报告给 [RustSec Advisory Database](https://github.com/RustSec/advisory-db/).
- [cargo-bloat](https://github.com/RazrFalcon/cargo-bloat)  — 找出在您的可执行文件中占用大部分空间的内容. 支持 ELF (Linux, BSD)、Mach-O (macOS) 和 PE (Windows) 二进制文件.
- [cargo-deny](https://embarkstudios.github.io/cargo-deny)  — 一个用于检查依赖项的货物插件. 它也可以用作命令行、Rust crate 或 CI 的 Github 操作. 它会检查有效的许可证信息、重复的 crate、安全漏洞等.
- [cargo-expand](https://github.com/dtolnay/cargo-expand) — Cargo subcommand to show result of macro expansion  and #[derive] expansion applied to the current crate.  This is a wrapper around a more verbose compiler command.
- [cargo-inspect](https://github.com/mre/cargo-inspect) — 检查没有语法糖的 Rust 代码，看看编译器在幕后做了什么.
- [cargo-spellcheck](https://github.com/drahnr/cargo-spellcheck) — 使用 hunspell（就绪）和语言工具（预览版）检查所有文档的拼写和语法错误
- [clippy](https://rust-lang.github.io/rust-clippy) — 用于捕捉常见错误并改进您的 Rust 代码的代码 linter.
- [dylint](https://www.trailofbits.com/post/write-rust-lints-without-forking-clippy)  — 从动态库运行 Rust lints 的工具.  Dylint 使开发人员可以轻松维护自己的个人 lint 集合.
- [electrolysis](http://kha.github.io/electrolysis) :warning: — 通过将 Rust 程序转换为精益定理证明器中的定义来正式验证 Rust 程序的工具.
- [herbie](https://github.com/mcarton/rust-herbie-lint) :warning: — 在使用数值不稳定的浮点表达式时向您的 crate 添加警告或错误.
- [linter-rust](https://github.com/AtomLinter/linter-rust) :warning: — 使用 rustc 和 cargo 在 Atom 中整理你的 Rust 文件.
- [MIRAI](https://github.com/facebookexperimental/MIRAI) — 以及在 Rust 的中级中间语言上运行的抽象解释器，并根据污点分析提供警告.
- [prae](https://github.com/teenjuna/prae) — 提供一个方便的宏，允许您生成承诺始终支持您指定的任意不变量的类型包装器. 
- [Prusti](https://www.pm.inf.ethz.ch/research/prusti.html)  — Rust 的静态验证器，基于 Viper 验证基础设施. 默认情况下，Prusti 通过证明诸如 unreachable!() 和 panic!() 之类的语句不可达来验证是否存在恐慌.
- [Rudra](https://github.com/sslab-gatech/Rudra)  — Rust 内存安全和未定义行为检测. 它能够分析单个 Rust 包以及 crates.io 上的所有包.
- [Rust Language Server](https://github.com/rust-lang-nursery/rls) — 支持“goto 定义”、符号搜索、重新格式化和代码完成等功能，并支持重命名和重构.
- [rust-analyzer](https://rust-analyzer.github.io) — 支持“goto 定义”、类型推断、符号搜索、重新格式化和代码完成等功能，并支持重命名和重构.
- [rust-audit](https://github.com/Shnatsel/rust-audit)  — 审计 Rust 二进制文件中的已知错误或安全漏洞. 这通过以 JSON 格式将有关依赖树 (Cargo.lock) 的数据嵌入到已编译可执行文件的专用链接器部分来实现.
- [rustfix](https://github.com/rust-lang/rustfix) — 阅读并应用 rustc（以及第三方 lints，如 clippy 提供的那些）提出的建议.
- [rustfmt](https://github.com/rust-lang/rustfmt) — 根据样式指南格式化 Rust 代码的工具.
- [RustViz](https://github.com/rustviz/rustviz)  — RustViz 是一个从简单的 Rust 程序生成可视化的工具，以帮助用户更好地理解 Rust 生命周期和借用机制. 它生成带有与 mdbook 集成的图形指示器的 SVG 文件，以呈现 Rust 程序中数据流的可视化.
- [warnalyzer](https://github.com/est31/warnalyzer) — 显示多箱 Rust 项目中未使用的代码


<h2 id="sql">SQL</h2>

- [dbcritic](https://github.com/channable/dbcritic) — dbcritic 发现数据库模式中的问题，例如表中缺少主键约束.
- [sqlcheck](https://github.com/jarulraj/sqlcheck) — 自动识别 SQL 查询中的反模式.
- [SQLFluff](https://www.sqlfluff.com/) — 多方言 SQL linter 和格式化程序.
- [sqlint](https://github.com/purcell/sqlint) — 简单的 SQL 短绒.
- [squawk](https://squawkhq.com)  — Linter for PostgreSQL，专注于迁移. 防止由数据库迁移导致的意外停机，并鼓励围绕 Postgres 模式和 SQL 的最佳实践.
- [tsqllint](https://github.com/tsqllint/tsqllint) — T-SQL 特定的 linter.
- [TSqlRules](https://github.com/ashleyglee/TSqlRules) :warning: — SQL Server 的 TSQL 静态代码分析规则.
- [Visual Expert](https://www.visual-expert.com) :copyright: — PowerBuilder、Oracle 和 SQL Server 的代码分析 探索、分析和记录代码 


<h2 id="scala">楼梯</h2>

- [linter](https://github.com/HairyFotr/linter) :warning: — Linter 是一个 Scala 静态分析编译器插件，它为各种可能的错误、低效率和样式问题添加了编译时检查.
- [Scalastyle](http://www.scalastyle.org) — Scalastyle 检查您的 Scala 代码并指出它的潜在问题.
- [scapegoat](https://github.com/sksamuel/scapegoat) — 用于静态代码分析的 Scala 编译器插件.
- [WartRemover](https://www.wartremover.org) — 一个灵活的 Scala 代码检查工具.


<h2 id="shell">贝壳</h2>

- [bashate](https://github.com/openstack/bashate)  — bash 程序的代码样式强制执行. 输出格式旨在遵循 pycodestyle (pep8) 默认输出格式.
- [i-Code CNES for Shell](https://github.com/lequal/i-CodeCNES) :warning: — Shell 和 Fortran（77 和 90）的开源静态代码分析工具.
- [kmdr](https://kmdr.sh)  :warning: — 用于从终端学习命令的 CLI 工具.  kmdr 提供了对每个属性进行解释的命令分解.
- [sh](https://pkg.go.dev/mvdan.cc/sh/v3)  — 支持 bash 的 shell 解析器、格式化程序和解释器； 包括 shfmt
- [shellcheck](https://www.shellcheck.net) — ShellCheck，一种静态分析工具，可为 bash/sh shell 脚本提供警告和建议.
- [shellharden](https://github.com/anordal/shellharden) — 一个语法高亮工具和一个半自动化地重写脚本以符合 ShellCheck 的工具，主要集中在引用上.


<h2 id="swift">迅速</h2>

- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) — 用于重新格式化 Swift 代码的库和命令行格式化工具.
- [SwiftLint](https://realm.github.io/SwiftLint) — 一个强制执行 Swift 风格和约定的工具.
- [Tailor](https://sleekbyte.github.io/tailor) :warning: — 一个静态分析和 lint 工具，用于用 Apple 的 Swift 编程语言编写的源代码.


<h2 id="tcl">Tcl</h2>

- [Frink](http://catless.ncl.ac.uk/Programs/Frink) — 一个 Tcl 格式化和静态检查程序（可以美化程序、最小化、混淆或只是完整性检查）.
- [Nagelfar](https://sourceforge.net/projects/nagelfar) — Tcl 的静态语法检查器.
- [tclchecker](https://github.com/ActiveState/tdk/blob/master/docs/3.0/TDK_3.0_Checker.txt) — 一个静态语法分析模块（作为 [TDK](https://github.com/ActiveState/tdk)).


<h2 id="typescript">打字稿</h2>

- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) — Angular 项目的 Linter
- [Codelyzer](http://codelyzer.com) — 一组用于 Angular 2 TypeScript 项目的静态代码分析的 tslint 规则.
- [tslint-clean-code](https://www.npmjs.com/package/tslint-clean-code) — 一组受 Clean Code 手册启发的 TSLint 规则.
- [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib) :warning: — 一组 tslint 规则，用于对 Microsoft 维护的 TypeScript 项目进行静态代码分析.
- [TypeScript Call Graph](https://github.com/whyboris/TypeScript-Call-Graph) — CLI 从您的 TypeScript 文件生成函数和调用的交互式图表
- [TypeScript ESLint](https://github.com/typescript-eslint/typescript-eslint) — eslint 的 TypeScript 语言扩展.


<h2 id="verilog">Verilog/系统Verilog</h2>

- [Icarus Verilog](https://github.com/steveicarus/iverilog) — 一种 Verilog 仿真和综合工具，通过将 IEEE-1364 Verilog 编写的源代码编译成某种目标格式来运行
- [svls](https://github.com/dalance/svls) — Verilog 和 SystemVerilog 的语言服务器协议实现，包括 lint 功能.
- [verible-linter-action](https://github.com/chipsalliance/verible-linter-action) — Automatic SystemVerilog linting in github actions with the help of Verible Used to lint Verilog and SystemVerilog source files and comment erroneous lines  of code in Pull Requests automatically.
- [Verilator](https://www.veripool.org/verilator)  — 将 Verilog 转换为 C++ 或 SystemC 中的周期精确行为模型的工具. 执行 lint 代码质量检查.
- [vscode-verilog-hdl-support](https://github.com/mshr-h/vscode-verilog-hdl-support)  — Verilog HDL/SystemVerilog/Bluespec SystemVerilog 支持 VS Code. 提供来自 Icarus Verilog、Vivado 逻辑仿真、Modelsim 和 Verilator 的语法高亮和 Linting 支持


<h2 id="vim-script">Vim 脚本</h2>

- [vint](https://github.com/Kuniwak/vint) — 由 Python 实现的快速且高度可扩展的 Vim 脚本语言 Lint.


## Multiple languages

- [ale](https://github.com/w0rp/ale) — Vim 和 NeoVim 的异步 Lint 引擎，支持多种语言.
- [Android Studio](https://developer.android.com/studio) — 基于 IntelliJ IDEA，并与包括 Android Lint 在内的 Android 工具捆绑在一起.
- [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) :copyright: — Static analysis for C/C++/C#, PHP and Java.
- [Application Inspector](https://www.ptsecurity.com/ww-en/products/ai) :copyright: — 商业静态代码分析，生成漏洞以验证漏洞.
- [ApplicationInspector](https://github.com/microsoft/ApplicationInspector) — 为特征检测创建超过 400 种规则模式的报告（例如，在应用程序中使用密码学或版本控制）.
- [APPscreener](https://solarappscreener.com) :copyright: — Static code analysis for binary and source code - Java/Scala, PHP, Javascript, C#, PL/SQL, Python, T-SQL, C/C++, ObjectiveC/Swift, Visual Basic 6.0, Ruby, Delphi, ABAP, HTML5 and Solidity.
- [ArchUnit](https://www.archunit.org) — 对您的 Java 或 Kotlin 架构进行单元测试.
- [Atom-Beautify](https://atom.io/packages/atom-beautify) :warning: — Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom editor.
- [Axivion Bauhaus Suite](https://www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: — Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95.
- [Better Code Hub](https://bettercodehub.com) :copyright: — Better Code Hub 根据软件质量权威软件改进组制定的 10 条工程指南检查您的 GitHub 代码库.
- [callGraph](https://github.com/koknat/callGraph) — 静态生成调用图图像并将其显示在屏幕上.
- [CAST Highlight](https://www.castsoftware.com/products/highlight) :copyright: — 商业静态代码分析，在本地运行，但将结果上传到其云端进行演示.
- [Checkmarx CxSAST](https://www.checkmarx.com/products/static-application-security-testing) :copyright: — 不需要预编译的商业静态代码分析.
- [ClassGraph](https://github.com/classgraph/classgraph) — 用于查询或可视化类元数据或类相关性的类路径和模块路径扫描器.
- [Clayton](https://www.getclayton.com/)  :copyright: — Salesforce 的 AI 驱动的代码审查. 实时保护您的开发、执行最佳实践并控制您的技术债务.
- [coala](https://coala.io) - 用于创建代码分析的语言独立框架 - 支持 [over 60 languages](https://coala.io/languages) 默认.
- [Cobra](https://spinroot.com/cobra) :copyright: — NASA 喷气推进实验室的结构源代码分析器.
- [Codacy](https://www.codacy.com) :copyright: — 代码分析以更快地交付更好的代码.
- [Code Intelligence](https://www.code-intelligence.com) :copyright: — 与 CI/CD 无关的 DevSecOps 平台，它结合了行业领先的 fuzzing 引擎，用于查找错误和可视化代码覆盖率
- [Codeac](https://www.codeac.io/?ref=awesome-static-analysis)  :copyright: — 自动代码审查工具与 GitHub、Bitbucket 和 GitLab 集成（甚至是自托管的）. 适用于 JavaScript、TypeScript、Python、Ruby、Go、PHP、Java、Docker 等.  （开源免费）
- [codeburner](http://groupon.github.io/codeburner) — 提供统一的界面来对发现的问题进行分类和处理.
- [codechecker](https://codechecker.readthedocs.io/en/latest) — 带有 Web GUI 的 Clang 静态分析器的缺陷数据库和查看器扩展.
- [CodeFactor](https://codefactor.io) :copyright: — GitHub 或 BitBucket 上 repos 的自动代码分析.
- [CodeFlow](https://www.getcodeflow.com)  :copyright: — 处理技术深度的自动化代码分析工具. 与 Bitbucket 和 Gitlab 集成.  （开源项目免费）
- [CodeIt.Right](https://submain.com/products/codeit.right.aspx) :copyright: — CodeIt.Right™ 提供了一种快速、自动化的方式来确保您的源代码符合（您的）预定义的设计和样式指南以及最佳编码实践.
- [CodePatrol](https://cyber-security.claranet.fr/en/codepatrol) :copyright: — 由安全驱动的自动 SAST 代码审查，支持 15 多种语言并包括安全培训.
- [codeql](https://github.com/github/codeql) — 深度代码分析 - 支持 VSCode 插件的多种语言的语义查询和数据流.
- [Coderrect](https://coderrect.com/)  :copyright: — 用于多线程软件的高级静态分析器. 支持 OpenMP、Pthreads、std::thread 和 GPU/CUDA.
- [CodeRush](https://www.devexpress.com/products/coderush) :copyright: — 在 Visual Studio 2015 及更高版本中使用 Roslyn 引擎的代码创建、调试、导航、重构、分析和可视化工具.
- [CodeScan](https://www.codescan.io/)  :copyright: — Salesforce 开发人员的代码质量和安全性.  CodeScan 的代码分析解决方案专为 Salesforce 平台设计，可让您全面了解代码运行状况.
- [CodeScene](https://codescene.com)  :copyright: — CodeScene 是软件的质量可视化工具. 优先考虑技术债务、检测交付风险并衡量组织方面. 全自动.
- [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) :copyright: — Advanced, whole program, deep path, static analysis of C, C++, Java and C# with easy-to-understand explanations and code and path visualization.
- [Codiga](https://www.codiga.io) :copyright: — 支持 12 种以上语言的自动代码审查和技术债务管理平台.
- [Corrode](https://github.com/jameysharp/corrode)  :warning: — 从 C 到 Rust 的半自动翻译. 可以通过显示 Rust 编译器警告和错误来揭示原始实现中的错误. 被 C2Rust 取代.
- [Coverity](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: — Synopsys Coverity supports 20 languages and over 70 frameworks including Ruby on rails, Scala, PHP, Python, JavaScript, TypeScript, Java, Fortran, C, C++, C#, VB.NET.
- [cqc](https://github.com/xcatliu/cqc) :warning: — 检查 js、jsx、vue、css、less、scss、sass 和 styl 文件的代码质量.
- [DeepCode](https://www.deepcode.ai)  :copyright: — DeepCode 基于 AI 发现错误、安全漏洞、性能和 API 问题.  DeepCode 的分析速度使我们能够实时分析您的代码并在您点击 IDE 中的保存按钮时提供结果. 支持的语言有 Java、C/C++、JavaScript、Python 和 TypeScript. 与 GitHub、BitBucket 和 Gitlab 集成.
- [DeepSource](https://deepsource.io)  :copyright: — 深入的静态分析，以发现错误风险、安全性、反模式、性能、文档和样式等垂直领域的问题. 与 GitHub、GitLab 和 Bitbucket 的原生集成. 低于 5% 的误报.
- [Depends](https://github.com/multilang-depends/depends) — 分析 Java、C/C++、Ruby 的代码元素的综合依赖关系.
- [DevSkim](https://github.com/microsoft/devskim) — Regex-based static analysis tool for Visual Studio, VS Code, and Sublime Text - C/C++, C#, PHP, ASP, Python, Ruby, Java, and others.
- [Embold](https://embold.io) :copyright: — Intelligent software analytics platform that identifies design issues, code issues, duplication and metrics. Supports Java, C, C++, C#, JavaScript, TypeScript, Python, Go, Kotlin and more.
- [ESLint](https://github.com/eslint/eslint) — 一个 JS 的可扩展 linter，遵循 ECMAScript 标准.
- [Find Security Bugs](https://find-sec-bugs.github.io)  — 用于对 Java Web 应用程序和 Android 应用程序进行安全审计的 SpotBugs 插件.  （也可以使用 Kotlin、Groovy 和 Scala 项目）
- [Fortify](https://software.microfocus.com/en-us/products/static-code-analysis-sast/overview) :copyright: — A commercial static analysis platform that supports the scanning of C/C++, C#, VB.NET, VB6, ABAP/BSP, ActionScript, Apex, ASP.NET, Classic ASP, VB Script, Cobol, ColdFusion, HTML, Java, JS, JSP, MXML/Flex, Objective-C, PHP, PL/SQL, T-SQL, Python (2.6, 2.7), Ruby (1.9.3), Swift, Scala, VB, and XML.
- [Goodcheck](https://sider.github.io/goodcheck) — 基于正则表达式的可定制 linter.
- [goone](https://github.com/masibw/goone) :warning: — 在 go 代码中查找 N+1 个查询（for 循环中的 SQL 调用）
- [graudit](http://www.justanotherhacker.com) — Grep 粗略审计——源代码审计工具.
- [HCL AppScan Source](https://www.hcltechsw.com/products/appscan) :copyright: — 商业静态代码分析.
- [Hopper](https://github.com/cuplv/hopper) :warning: — 一个用 scala 编写的静态分析工具，用于在 JVM 上运行的语言.
- [Hound CI](https://houndci.com)  — 对 GitHub 拉取请求中的样式违规的评论. 支持 Coffeescript、Go、HAML、JavaScript、Ruby、SCSS 和 Swift.
- [imhotep](https://github.com/justinabrahms/imhotep) — 评论进入您的存储库的提交并检查语法错误和一般 lint 警告.
- [include-gardener](https://github.com/feddischson/include_gardener) :warning: — A multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
- [Infer](https://fbinfer.com) — Java、C 和 Objective-C 的静态分析器
- [InsiderSec](https://insidersec.io) :warning: — A open source Static Application Security Testing tool (SAST) written in GoLang for Java (Maven and Android), Kotlin (Android), Swift (iOS), .NET Full Framework, C# and Javascript (Node.js).
- [Kiuwan](https://www.kiuwan.com/code-security-sast) :copyright: — Identify and remediate cyber threats in a blazingly fast, collaborative environment, with seamless integration in your SDLC. Python, C\C++, Java, C#, PHP and more.
- [Klocwork](https://www.perforce.com/products/klocwork) :copyright: — Quality and Security Static analysis for C/C++, Java and C#.
- [LGTM](https://lgtm.com/)  :copyright: — 使用对源代码的查询来查找安全漏洞、变体和关键代码质量问题. 自动 PR 代码审查； 免费用于开源. 以前的semme.
- [LGTM.com](https://lgtm.com)  :copyright: — 对 GitHub 和 Bitbucket 进行深度代码分析，以发现安全漏洞和关键代码质量问题（使用 Semmle QL）. 拉取请求的自动代码审查； 公共存储库免费.
- [lizard](https://github.com/terryyin/lizard)  — Lizard 是一种可扩展的圈复杂度分析器，适用于包括 C/C++ 在内的许多编程语言（不需要所有头文件或 Java 导入）. 它还进行复制粘贴检测（代码克隆检测/代码重复检测）和许多其他形式的静态代码分析. 计算不带注释的代码行数、CCN（圈复杂度数）、函数的标记数、函数的参数数.
- [Mega-Linter](https://nvuillam.github.io/mega-linter/) — Mega-Linter 可以处理任何类型的项目，这要归功于其 70 多个嵌入式 Linter，
 它的高级报告，可在任何 CI 系统或本地运行，
 通过辅助安装和配置，能够应用格式化和修复
- [oclint](http://oclint.org) — 一种静态源代码分析工具，用于提高 C、C++ 和 Objective-C 的质量并减少缺陷.
- [ocular](https://www.shiftleft.io/ocular/)  :copyright: — 使代码审计员和安全团队能够以交互方式调查他们独特的代码库，以发现传统 SAST 无法找到的业务逻辑缺陷和技术漏洞. 这是通过使分析师能够编写自己的自定义查询来完成的. 可以找到硬编码的秘密、身份验证问题和恶意代码，如 rootkit 和后门.
- [Offensive 360](https://offensive360.com/) :copyright: — Commercial Static Code Analysis system doesn't require building the source code or pre-compilation.
- [parasoft](https://www.parasoft.com/)  :copyright: — 用于单元、API 和 Web UI 测试的自动化软件测试解决方案. 符合 MISRA、OWASP 等.
- [pfff](https://github.com/facebookarchive/pfff/wiki/Main) — Facebook 用于多种语言的代码分析、可视化或保留样式的源转换工具.
- [PMD](https://pmd.github.io) — 适用于 Java、Salesforce Apex、Javascript、PLSQL、XML、XSL 等的源代码分析器.
- [pre-commit](https://pre-commit.com) — 用于管理和维护多语言预提交挂钩的框架.
- [Prettier](https://prettier.io) — 自以为是的代码格式化程序.
- [Pronto](https://github.com/prontolabs/pronto)  — 对您的更改进行快速自动代码审查. 支持 40 多种不同语言的运行器，包括 Clang、Elixir、JavaScript、PHP、Ruby 等.
- [PT.PM](https://github.com/PositiveTechnologies/PT.PM) :warning: — An engine for searching patterns in the source code, based on Unified AST or UST. At present time C#, Java, PHP, PL/SQL, T-SQL, and JavaScript are supported. Patterns can be described within the code or using a DSL.
- [Putout](https://github.com/coderaiser/putout) — 可插入和可配置的代码转换器，内置 eslint，babel 插件支持 js、jsx typescript、flow、markdown、yaml 和 json.
- [PVS-Studio](https://pvs-studio.com) :版权: — A ([conditionally free](https://pvs-studio.com/en/order/open-source-license) for FOSS and individual developers) static analysis of C, C++, C# and Java code. For advertising purposes [you can propose a large FOSS project for analysis by PVS employees](https://github.com/viva64/pvs-studio-check-list) . 支持 CWE 映射、MISRA 和 CERT 编码标准.
- [pylama](https://klen.github.io/pylama/)  — 适用于 Python 和 JavaScript 的代码审计工具. 包装 pycodestyle、pydocstyle、PyFlakes、Mccabe、Pylint 等
- [Refactoring Essentials](https://marketplace.visualstudio.com/items?itemName=SharpDevelopTeam.RefactoringEssentialsforVisualStudio) :warning: — The free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers.
- [relint](https://github.com/codingjoe/relint) — 一个静态文件 linter，允许您使用正则表达式 (RegEx) 编写自定义规则.
- [ReSharper](https://www.jetbrains.com/resharper) :copyright: — Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies.
- [RIPS](https://www.ripstech.com) :copyright: — PHP 脚本漏洞的静态源代码分析器.
- [Rome](https://rome.tools/) — Rome 是一个 linter、编译器、捆绑器和 [more](https://rome.tools/#development-status) 适用于 JavaScript、TypeScript、JSON、HTML、Markdown 和 CSS.
- [Roslyn Analyzers](https://github.com/dotnet/roslyn-analyzers) — 基于 Roslyn 的 FxCop 分析器实现.
- [Roslyn Security Guard](https://security-code-scan.github.io) — 专注于识别潜在漏洞的项目，例如 SQL 注入、跨站点脚本 (XSS)、CSRF、加密弱点、硬编码密码等等.
- [Scanmycode CE (Community Edition)](http://www.scanmycode.today) — Scanmycode - 使用多种工具进行代码扫描/SAST/Linting/带有一份报告的扫描仪
- [Scrutinizer](https://scrutinizer-ci.com) :copyright: — 可与 GitHub 集成的专有代码质量检查器.
- [Security Code Scan](https://security-code-scan.github.io) — Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc. Integrates into Visual Studio 2015 and newer. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
- [Semgrep](https://semgrep.dev)  — 一种快速、开源的静态分析工具，用于在编辑器、提交和 CI 时发现错误并执行代码标准. 它的规则看起来像你已经编写的代码； 没有抽象语法树或正则表达式摔跤. 支持 17 多种语言.
- [ShiftLeft](https://www.shiftleft.io)  :copyright: — 在您的代码库进入生产环境之前识别它们特有的漏洞. 利用代码属性图 (CPG) 在单个图表中同时运行其分析. 自动发现开发中的业务逻辑缺陷，例如硬编码的秘密和逻辑炸弹
- [ShiftLeft Scan](https://slscan.io)  — Scan 是一个免费的开源 DevSecOps 平台，用于检测源代码和依赖项中的安全问题. 它支持广泛的语言和 CI/CD 管道.
- [shipshape](https://github.com/google/shipshape) :warning: — 允许自定义分析器通过通用接口插入的静态程序分析平台.
- [Sider](https://sider.review)  :copyright: — 一种自动代码审查工具. 提高开发人员的生产力.
- [Similarity Tester](https://dickgrune.com/Programs/similarity_tester/) — 一种工具，用于发现文件之间或文件内的相似性，以支持您遇到 DRY 原则违规行为.
- [Snyk](https://snyk.io) :copyright: — node.js 应用程序依赖项的漏洞扫描程序（开源项目免费）.
- [SonarCloud](https://sonarcloud.io)  :copyright: — 基于云的多语言静态代码分析. 历史、趋势、安全热点、拉取请求分析等. 开源免费.
- [SonarLint for Visual Studio](https://vs.sonarlint.org) — SonarLint 是 Visual Studio 2015 和 2017 的扩展，可为开发人员提供有关注入 .NET 代码的新错误和质量问题的即时反馈.
- [SonarQube](http://www.sonarqube.org) — SonarQube 是一个管理代码质量的开放平台.
- [Sonatype](https://www.sonatype.com) :copyright: — 报告常见依赖项中的已知漏洞并推荐更新的软件包以最大程度地减少重大更改
- [Soto Platform](https://www.hello2morrow.com/products/sotograph)  :copyright: — 静态分析工具套件，由 Sotoarc（架构分析）、Sotograph（质量分析）和 Sotoreport（质量报告）三个组件组成. 帮助发现架构和实现之间的差异、接口违规（例如子系统私有部分的外部访问、检测所有类、文件、包和通过循环关系强耦合的子系统等等.Sotograph 产品系列在 Windows 和 Linux 上运行. 
- [SourceMeter](https://www.sourcemeter.com/) :copyright: — Static Code Analysis for C/C++, Java, C#, Python, and RPG III and RPG IV versions (including free-form).
- [sqlvet](https://github.com/houqp/sqlvet)  — 对 Go 代码库中的原始 SQL 查询执行静态分析，以发现潜在的运行时错误. 它检查 SQL 语法错误，识别可能导致 SQL 注入的不安全查询，确保列计数与 INSERT 语句中的值计数匹配，并验证表名和列名.
- [Super-Linter](https://github.com/github/super-linter) — 将多个 linter 组合安装为 GitHub Action.
- [Synopsys](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: — A commercial static analysis platform that allows for scanning of multiple languages (C/C++, Android, C#, Java, JS, PHP, Python, Node.JS, Ruby, Fortran, and Swift).
- [Teamscale](https://www.cqse.eu/en/teamscale/overview/)  :copyright: — 支持超过 25 种语言和直接 IDE 集成的静态和动态分析工具. 可根据要求免费托管开源项目. 提供免费的学术许可证.
- [ThreatMapper](https://github.com/deepfence/ThreatMapper)  — 运行时容器、无服务器和主机的漏洞扫描器和风险评估.  ThreatMapper 从依赖项和操作系统包生成运行时 BOM，匹配多个威胁源，扫描未受保护的机密，并根据严重性和利用风险对问题进行评分.
- [todocheck](https://github.com/preslavmihaylov/todocheck) — Linter for integrating annotated TODOs with your issue trackers
- [trivy](https://github.com/aquasecurity/trivy)  — 适用于 CI 的容器和其他工件的简单而全面的漏洞扫描程序.  Trivy 检测操作系统包（Alpine、RHEL、CentOS 等）和应用程序依赖项（Bundler、Composer、npm、yarn 等）的漏洞. 检查容器和文件系统.

- [trunk](https://trunk.io)  :copyright: — 现代存储库包含许多技术，每种技术都有自己的一组 linter. 凭借 30 多个 linter 和计数，Trunk 可以非常简单地为您的所有存储库识别、安装、配置和运行正确的 linter、静态分析器和格式化程序.
- [TscanCode](https://github.com/Tencent/TscanCode) — A fast and accurate static analysis solution for C/C++, C#, Lua codes provided by Tencent. Using GPLv3 license.
- [Undebt](https://github.com/Yelp/undebt) — 独立于语言的工具，用于基于简单模式定义的大规模、自动、可编程重构.
- [Understand](https://www.scitools.com) :copyright: — 代码可视化工具，为 Ada、VHDL 等提供代码分析、标准测试、度量、图形、依赖性分析等.
- [Unibeautify](https://unibeautify.com)  — 带有 GitHub 应用程序的通用代码美化器. 支持 HTML、CSS、JavaScript、TypeScript、JSX、Vue、C++、Go、Objective-C、Java、Python、PHP、GraphQL、Markdown 等.
- [Upsource](https://www.jetbrains.com/upsource) :copyright: — 具有静态代码分析和代码感知导航的代码审查工具，适用于 Java、PHP、JavaScript 和 Kotlin.
- [Veracode](http://www.veracode.com/products/static-analysis-sast/static-code-analysis) :copyright: — Find flaws in binaries and bytecode without requiring source. Support all major programming languages: Java, .NET, JavaScript, Swift, Objective-C, C, C++ and more.
- [Viezly](https://viezly.com)  :copyright: — 带有依赖关系图的代码审查工具. 通过更好的导航和代码分析改进团队的代码审查
- [WALA](https://github.com/wala/WALA) — Java 字节码和相关语言以及 JavaScript 的静态分析功能.
- [weggli](https://github.com/googleprojectzero/weggli)  — 用于 C 和 C++ 代码库的快速且强大的语义搜索工具. 它旨在帮助安全研究人员识别大型代码库中的有趣功能.
- [WhiteHat Application Security Platform](https://www.whitehatsec.com/platform/static-application-security-testing) :copyright: — WhiteHat Scout（针对开发人员）与 WhiteHat Sentinel Source（针对运营）相结合，支持 WhiteHat Top 40 和 OWASP Top 10.
- [Wotan](https://github.com/fimbullinter/wotan) — 可插入的 TypeScript 和 JavaScript linter.
- [XCode](https://developer.apple.com/xcode) :copyright: — XCode 为 [Clang's](http://clang-analyzer.llvm.org/xcode.html) 静态代码分析器（C/C++、Obj-C）.


## Other



<h2 id="angular">角</h2>

- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) — Angular 项目的 Linter


<h2 id="ansible">Ansible</h2>

- [kics](https://kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible


<h2 id="arm">Azure 资源管理器</h2>

- [AzSK](https://azsk.azurewebsites.net/)  — 适用于 Azure (AzSK) 的安全 DevOps 套件在基础架构即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础架构错误配置. 通过 ARM 支持 Azure.


<h2 id="binary">二进制文件</h2>

- [angr](https://github.com/angr/angr) — 也支持符号执行的二进制代码分析工具.
- [binbloom](https://github.com/quarkslab/binbloom)  — 分析原始二进制固件并确定字节序或加载地址等特性. 该工具与所有架构兼容.
加载地址：binbloom 可以解析原始二进制固件并确定其加载地址. 字节序：binbloom 可以使用启发式方法来确定固件的字节序.  UDS 数据库：binbloom 可以解析原始二进制固件并检查它是否包含包含 UDS 命令 ID 的数组.
- [BinSkim](https://github.com/Microsoft/binskim) — 一种二进制静态分析工具，可为 Windows 可移植可执行文件提供安全性和正确性结果.
- [Black Duck](https://www.blackducksoftware.com) :copyright: — 分析源代码和二进制文件以获取可重用代码、必要许可证和潜在安全方面的工具.
- [bloaty](https://github.com/google/bloaty)  — 有没有想过是什么让你的二进制文件变大了？  Bloaty McBloatface 将向您显示二进制文件的大小配置文件，以便您了解内部空间占用的情况.  Bloaty 对二进制文件进行了深入分析. 使用自定义 ELF、DWARF 和 Mach-O 解析器，Bloaty 旨在准确地将二进制文件的每个字节归因于生成它的符号或编译单元. 它甚至会反汇编二进制文件以查找对匿名数据的引用.  F
- [cargo-bloat](https://github.com/RazrFalcon/cargo-bloat)  — 找出在您的可执行文件中占用大部分空间的内容. 支持 ELF (Linux, BSD)、Mach-O (macOS) 和 PE (Windows) 二进制文件.
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) — cwe_checker 在二进制可执行文件中发现易受攻击的模式.
- [Ghidra](https://ghidra-sre.org) — 由 NSA 研究局开发的一套软件逆向工程 (SRE) 工具套件，用于支持网络安全任务
- [IDA Free](https://www.hex-rays.com/products/ida/support/download_freeware) :copyright: — 二进制代码分析工具.
- [Jakstab](https://github.com/jkinder/jakstab) — Jakstab 是一个基于抽象解释的集成反汇编和静态分析框架，用于设计对可执行文件的分析并恢复可靠的控制流图.
- [JEB Decompiler](https://www.pnfsoftware.com/)  :copyright: — 反编译和调试二进制代码. 分解和分析文档文件.  Android Dalvik、MIPS、ARM、Intel x86、Java、WebAssembly 和 Ethereum 反编译器.
- [Manalyze](https://github.com/JusticeRage/Manalyze) — 一种静态分析器，用于检查可移植可执行文件中的恶意内容.
- [mcsema](https://github.com/lifting-bits/mcsema)  — 用于将 x86、amd64、aarch64、sparc32 和 sparc64 程序二进制文件提升到 LLVM 位码的框架. 它将可执行二进制文件从本机机器代码转换（“提升”）为 LLVM 位码，这对于执行程序分析方法非常有用.
- [Nauz File Detector](https://github.com/horsicq/Nauz-File-Detector) — 适用于 Windows、Linux 和 MacOS 的静态链接器/编译器/工具检测器.
- [Twiggy](https://rustwasm.github.io/twiggy)  — 分析二进制文件的调用图以分析代码大小. 目标是缩小 wasm 二进制大小.
- [VMware chap](https://github.com/vmware/chap) — chap analyzes un-instrumented ELF core files for leaks, memory growth, and corruption.  It is sufficiently reliable that it can be used in automation to catch leaks before  they are committed. As an interactive tool, it helps explain memory growth,  can identify some forms of corruption, and supplements a debugger  by giving the status of various memory locations. 
- [zydis](https://zydis.re) — 快速、轻量级的 x86/x86-64 反汇编库


<h2 id="buildtool">构建工具</h2>

- [checkmake](https://github.com/mrtazz/checkmake) — 用于 Makefile 的 Linter / Analyzer.
- [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) — FreeBSD 和 DragonFlyBSD 端口目录的验证器.


<h2 id="css">CSS/SASS/SCSS</h2>

- [CSS Stats](https://cssstats.com) — 样式表上可能有趣的统计数据.
- [CSScomb](https://github.com/csscomb/csscomb.js)  — CSS 的编码样式格式化程序. 支持自己的配置，使样式表美观一致.
- [CSSLint](http://csslint.net) — 进行基本的语法检查并发现有问题的模式或效率低下的迹象.
- [GraphMyCSS.com](https://graphmycss.com) — CSS 特异性图生成器.
- [Nu Html Checker](https://validator.github.io/validator/) — 帮助您发现 HTML/CSS/SVG 中的问题
- [Parker](https://github.com/katiefenn/parker) :warning: — 样式表分析工具.
- [PostCSS](https://postcss.org)  — 使用 JS 插件转换样式的工具. 这些插件可以 lint 你的 CSS，支持变量和 mixins，转换未来的 CSS 语法，内联图像等等.
- [Project Wallace CSS Analyzer](https://www.projectwallace.com) — CSS 分析，其中的一部分 [Project Wallace](https://www.projectwallace.com).
- [sass-lint](https://github.com/sasstools/sass-lint) :warning: — 适用于 sass 和 scss 语法的仅限节点的 Sass linter.
- [scsslint](https://github.com/brigade/scss-lint) — SCSS 文件的 Linter.
- [Specificity Graph](https://jonassebastianohlsson.com/specificity-graph) — CSS 特异性图生成器.
- [Stylelint](http://stylelint.io) — 用于 SCSS/CSS 文件的 Linter.


<h2 id="configfile">配置文件</h2>

- [dotenv-linter](https://dotenv-linter.readthedocs.io/en/latest) — Linting dotenv 文件就像一个魅力.
- [dotenv-linter (Rust)](https://dotenv-linter.github.io/#/)  — 用于 .env 文件的闪电般快速的 linter. 用锈写
- [gixy](https://github.com/yandex/gixy)  :warning: — 分析 Nginx 配置的工具. 主要目标是防止错误配置和自动化缺陷检测.


<h2 id="configmanagement">配置管理</h2>

- [ansible-lint](https://docs.ansible.com/ansible-lint) — 检查剧本中可能改进的实践和行为.
- [AWS CloudFormation Guard](https://github.com/aws-cloudformation/cloudformation-guard) — 根据策略即代码规则检查本地 CloudFormation 模板，并从现有模板生成规则.
- [AzSK](https://azsk.azurewebsites.net/)  — 适用于 Azure (AzSK) 的安全 DevOps 套件在基础架构即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础架构错误配置. 通过 ARM 支持 Azure.
- [cfn-lint](https://github.com/awslabs/cfn-python-lint) — AWS 实验室 CloudFormation 短绒.
- [cfn_nag](https://github.com/stelligent/cfn_nag) — AWS CloudFormation 模板的 linter.
- [chart-testing](https://github.com/helm/chart-testing)  — ct 是测试 Helm 图表的工具. 它旨在用于 linting 和测试拉取请求. 它会自动检测针对目标分支更改的图表.
- [checkov](https://www.checkov.io) — Terraform 文件的静态分析工具 (tf&gt;=v0.12)，防止在构建时云配置错误.
- [clusterlint](https://github.com/digitalocean/clusterlint)  — Clusterlint 查询实时 Kubernetes 集群以获取资源，对这些资源执行通用和特定于平台的检查，并向集群操作员提供可操作的反馈. 它是一种在外部运行的非侵入性工具.  Clusterlint 不会改变资源配置.
- [cookstyle](https://docs.chef.io/cookstyle.html) — Cookstyle 是一种基于用于 Chef 食谱的 RuboCop Ruby linting 工具的 linting 工具.
- [Datree](https://datree.io/) — 一个 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及您组织的政策来防止 Kubernetes 错误配置
- [foodcritic](http://www.foodcritic.io) — 检查 Chef 食谱中常见问题的 lint 工具.
- [kics](https://kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible
- [kube-lint](https://github.com/viglesiasce/kube-lint)  — 具有可定制规则集的 Kubernetes 资源 linter. 您定义了一个要针对您的资源验证的规则列表，kube-lint 将根据它们评估这些规则.
- [kube-linter](https://github.com/stackrox/kube-linter) — KubeLinter 是一种静态分析工具，可检查 Kubernetes YAML 文件和 Helm 图表，以确保其中表示的应用程序符合最佳实践. 
- [kubeval](https://kubeval.instrumenta.dev) — 验证您的 Kubernetes 配置文件并支持多个 Kubernetes 版本.
- [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint) — 检查 Puppet metadata.json 文件有效性的工具.
- [Puppet Lint](https://github.com/rodjek/puppet-lint) — 检查您的 Puppet 清单是否符合样式指南.
- [terraform-compliance](https://terraform-compliance.com) — 针对 Terraform 的轻量级、以合规性和安全性为重点的 BDD 测试框架.
- [terrascan](https://github.com/cesar-rodriguez/terrascan) — 收集用于 Terraform 模板的静态代码分析的安全性和最佳实践测试.
- [tflint](https://github.com/wata727/tflint) — Terraform linter，用于检测“terraform plan”无法检测到的错误.
- [tfsec](https://github.com/tfsec/tfsec)  — Terraform 静态分析工具，通过在构建时检查云错误配置来防止潜在的安全问题，并直接与 HCL 解析器集成以获得更好的结果. 检查是否违反 AWS、Azure 和 GCP 安全最佳实践建议.


<h2 id="container">容器</h2>

- [anchore](https://anchore.io)  — 发现、分析和验证容器映像. 一种分析 Docker 映像并应用用户定义的接受策略以允许自动容器映像验证和认证的服务 
- [chart-testing](https://github.com/helm/chart-testing)  — ct 是测试 Helm 图表的工具. 它旨在用于 linting 和测试拉取请求. 它会自动检测针对目标分支更改的图表.
- [clair](https://github.com/coreos/clair) — 容器的漏洞静态分析.
- [clusterlint](https://github.com/digitalocean/clusterlint)  — Clusterlint 查询实时 Kubernetes 集群以获取资源，对这些资源执行通用和特定于平台的检查，并向集群操作员提供可操作的反馈. 它是一种在外部运行的非侵入性工具.  Clusterlint 不会改变资源配置.
- [collector](https://github.com/banyanops/collector) :warning: — 在容器内运行任意脚本，并收集有用信息.
- [dagda](https://github.com/eliasgranderubio/dagda) — 对 docker 镜像/容器中的已知漏洞进行静态分析.
- [Datree](https://datree.io/) — 一个 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及您组织的政策来防止 Kubernetes 错误配置
- [Docker Label Inspector](https://github.com/garethr/docker-label-inspector) :warning: — Lint 并验证 Dockerfile 标签.
- [Haskell Dockerfile Linter](https://github.com/lukasmartinelli/hadolint) — 更智能的 Dockerfile linter，可帮助您构建最佳实践 Docker 映像.
- [kics](https://kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible
- [kube-lint](https://github.com/viglesiasce/kube-lint)  — 具有可定制规则集的 Kubernetes 资源 linter. 您定义了一个要针对您的资源验证的规则列表，kube-lint 将根据它们评估这些规则.
- [kube-linter](https://github.com/stackrox/kube-linter) — KubeLinter 是一种静态分析工具，可检查 Kubernetes YAML 文件和 Helm 图表，以确保其中表示的应用程序符合最佳实践. 
- [kube-score](https://kube-score.com) — Kubernetes 对象定义的静态代码分析.
- [KubeLinter](https://github.com/stackrox/kube-linter) — KubeLinter 是一种静态分析工具，可检查 Kubernetes YAML 文件和 Helm 图表，以确保其中表示的应用程序符合最佳实践.
- [kubeval](https://kubeval.instrumenta.dev) — 验证您的 Kubernetes 配置文件并支持多个 Kubernetes 版本.
- [OpenSCAP](https://www.open-scap.org/) — 一套自动化审计工具，用于按照 NIST 认证的安全内容自动化协议 (SCAP) 检查配置和已知漏洞.
- [Qualys Container Security](https://www.qualys.com/apps/container-security) :copyright: — 容器原生应用程序保护，提供对容器化应用程序的可见性和控制.
- [sysdig](https://sysdig.com/)  :copyright: — 用于云和容器取证的安全 DevOps 平台.  Sysdig 建立在开源堆栈之上，提供 Docker 图像扫描并创建了 Falco，这是用于容器、Kubernetes 和云的运行时威胁检测的开放标准. 
- [Vuls](https://vuls.io/) — 基于 NVD、OVAL 等信息的无代理 Linux 漏洞扫描程序.它具有一些容器映像支持，尽管不是特定于容器的工具.


<h2 id="ci">持续集成</h2>

- [actionlint](https://rhysd.github.io/actionlint)  — GitHub Actions 工作流文件的静态检查器. 提供在线版本.
- [AzSK](https://azsk.azurewebsites.net/)  — 适用于 Azure (AzSK) 的安全 DevOps 套件在基础架构即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础架构错误配置. 通过 ARM 支持 Azure.
- [Code Climate](https://codeclimate.com) — 开放且可扩展的静态分析平台，适合所有人.
- [exakat](https://www.exakat.io) — PHP 的自动代码审查引擎.
- [Nitpick CI](https://nitpick-ci.com) :copyright: — 自动 PHP 代码审查.
- [PullRequest](https://www.pullrequest.com)  :copyright: — 代码审查作为具有内置静态分析的服务. 通过由一流自动化支持的专家工程师进行质量代码审查，提高速度并减少技术债务.
- [quality](https://github.com/apiology/quality) :warning: — 使用社区工具对您的代码进行质量检查，并确保您的数字不会随着时间的推移而变得更糟.
- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode)  :warning: — 自动代码审查和修复. 它可以帮助您跟踪软件项目中的问题和指标，并且可以轻松扩展以支持新类型的分析.
- [Reviewdog](https://github.com/haya14busa/reviewdog) — 在任何代码托管服务中发布来自任何 linter 的评论评论的工具.
- [Symfony Insight](https://insight.symfony.com/) :copyright: — 检测安全风险、发现错误并为 PHP 项目提供可操作的指标.
- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  — 用于从静态代码分析中解析报告文件的 Java 库. 被一堆 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="deno">德诺</h2>

- [deno_lint](https://github.com/denoland/deno_lint) — Deno 的官方 linter.


<h2 id="embedded">嵌入式</h2>

- [oelint-adv](https://github.com/priv-kweihmann/oelint-adv) — 用于开放式嵌入式和 YOCTO 的 bitbake 配方的 Linter


<h2 id="erb">嵌入式 Ruby（又名 ERB、eRuby）</h2>

- [ERB Lint](https://github.com/Shopify/erb-lint) — 整理您的 ERB 或 HTML 文件


<h2 id="gherkin">小黄瓜</h2>

- [gherkin-lint](https://github.com/vsiakka/gherkin-lint) — 用 Ja​​vascript 编写的 Gherkin-Syntax 的 linter.


<h2 id="html">HTML</h2>

- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) — Angular 项目的 Linter
- [Bootlint](https://github.com/twbs/bootlint) — An HTML linter for Bootstrap projects.
- [ERB Lint](https://github.com/Shopify/erb-lint) — 整理您的 ERB 或 HTML 文件
- [grunt-bootlint](https://github.com/twbs/grunt-bootlint) — Grunt 包装器 [Bootlint](https://github.com/twbs/bootlint), Bootstrap 项目的 HTML linter.
- [gulp-bootlint](https://github.com/tschortsch/gulp-bootlint) — 一个 gulp 包装器 [Bootlint](https://github.com/twbs/bootlint), Bootstrap 项目的 HTML linter.
- [HTML Inspector](https://github.com/philipwalton/html-inspector) :warning: — HTML Inspector 是一种代码质量工具，可帮助您和您的团队编写更好的标记.
- [HTML Tidy](http://www.html-tidy.org) — 通过修复标记错误并将遗留代码升级到现代标准来更正和清理 HTML 和 XML 文档.
- [HTML-Validate](https://html-validate.org/) — 离线 HTML5 验证器.
- [HTMLHint](https://htmlhint.com) — HTML 的静态代码分析工具.
- [Nu Html Checker](https://validator.github.io/validator/) — 帮助您发现 HTML/CSS/SVG 中的问题
- [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer) — Web 组件的静态分析框架.


<h2 id="json">JSON</h2>

- [jsonlint](https://jsonlint.com/)  — 带有 CLI 的 JSON 解析器和验证器.  jsonlint.com 的独立版本
- [Spectral](https://stoplight.io/open-source/spectral) — 一个灵活的 JSON/YAML linter，对 OpenAPI v2/v3 和 AsyncAPI v2 提供开箱即用的支持.


<h2 id="kubernetes">州长</h2>

- [chart-testing](https://github.com/helm/chart-testing)  — ct 是测试 Helm 图表的工具. 它旨在用于 linting 和测试拉取请求. 它会自动检测针对目标分支更改的图表.
- [clusterlint](https://github.com/digitalocean/clusterlint)  — Clusterlint 查询实时 Kubernetes 集群以获取资源，对这些资源执行通用和特定于平台的检查，并向集群操作员提供可操作的反馈. 它是一种在外部运行的非侵入性工具.  Clusterlint 不会改变资源配置.
- [Datree](https://datree.io/) — 一个 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及您组织的政策来防止 Kubernetes 错误配置
- [kics](https://kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible
- [kube-lint](https://github.com/viglesiasce/kube-lint)  — 具有可定制规则集的 Kubernetes 资源 linter. 您定义了一个要针对您的资源验证的规则列表，kube-lint 将根据它们评估这些规则.
- [kube-linter](https://github.com/stackrox/kube-linter) — KubeLinter 是一种静态分析工具，可检查 Kubernetes YAML 文件和 Helm 图表，以确保其中表示的应用程序符合最佳实践. 
- [kubeval](https://kubeval.instrumenta.dev) — 验证您的 Kubernetes 配置文件并支持多个 Kubernetes 版本.


<h2 id="latex">乳胶</h2>

- [ChkTeX](http://www.nongnu.org/chktex) — 用于 LaTex 的 linter，它可以捕获 LaTeX 监督的一些印刷错误.
- [lacheck](https://www.ctan.org/pkg/lacheck) — 用于查找 LaTeX 文档中常见错误的工具.
- [TeXLab](https://texlab.netlify.app) — TeX/LaTeX 的语言服务器协议实现，包括 lint 功能.


<h2 id="laravel">拉拉维尔</h2>

- [Enlightn](https://www.laravel-enlightn.com/)  — Laravel 应用程序的静态和动态分析工具，它提供建议以提高 Laravel 应用程序的性能、安全性和代码可靠性. 包含 120 个自动检查.


<h2 id="make">生成文件</h2>

- [checkmake](https://github.com/mrtazz/checkmake) — 用于 Makefile 的 Linter / Analyzer.
- [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) — FreeBSD 和 DragonFlyBSD 端口目录的验证器.


<h2 id="markdown">降价</h2>

- [markdownlint](https://github.com/DavidAnson/markdownlint) — 基于 Node.js 的样式检查器和用于 Markdown/CommonMark 文件的 lint 工具.
- [mdformat](https://mdformat.rtfd.io) — CommonMark 兼容的 Markdown 格式化程序
- [mdl](https://github.com/mivok/markdownlint) — 检查 Markdown 文件和标记样式问题的工具.
- [remark-lint](https://remark.js.org) — 用 Ja​​vaScript 编写的可插入 Markdown 代码样式 linter.


<h2 id="meta">金属间</h2>

- [ciocheck](https://github.com/ContinuumIO/ciocheck)  :warning: — Linter、格式化程序和测试套件助手. 作为 linter，它是 `pep8`、`pydocstyle`、`flake8` 和 `pylint` 的包装器.
- [flake8](https://github.com/PyCQA/flake8) — `pyflakes`、`pycodestyle` 和 `mccabe` 的​​包装器.
- [Go Meta Linter](https://github.com/alecthomas/gometalinter)  :warning: — 同时运行 Go lint 工具并标准化它们的输出. 对新项目使用 `golangci-lint`.
- [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) — 同时运行许多 linter 并将它们的输出标准化为报告.
- [multilint](https://github.com/adamchainz/multilint) :warning: — `flake8`、`isort` 和 `modernize` 的包装器.
- [prospector](https://github.com/PyCQA/prospector) — `pylint`、`pep8`、`mccabe` 等的封装.


<h2 id="mobile">移动的</h2>

- [Android Lint](http://tools.android.com/tips/lint) — 对 Android 项目运行静态分析.
- [android-lint-summary](https://passy.github.io/android-lint-summary) :warning: — 将多个项目的 lint 错误合并为一个输出，一次检查多个子项目的 lint 结果.
- [FlowDroid](https://github.com/secure-software-engineering/FlowDroid) — 用于 Android 应用程序的静态污点分析工具.
- [iblessing](https://www.kitploit.com/2020/08/iblessing-ios-security-exploiting.html)  — iblessing 是一个 iOS 安全漏洞利用工具包. 它可用于逆向工程、二进制分析和漏洞挖掘.
- [Oversecured](https://oversecured.com)  :copyright: — 适用于 Android 和 iOS 应用程序的企业漏洞扫描程序. 它允许应用程序所有者和开发人员通过将 Oversecured 集成到开发过程中来保护移动应用程序的每个新版本.
- [paprika](https://github.com/GeoffreyHecht/paprika) :warning: — 一个工具包，用于检测分析的 Android 应用程序中的一些代码异味.
- [qark](https://github.com/linkedin/qark) :warning: — 用于查找多个与安全相关的 Android 应用程序漏洞的工具.
- [redex](https://fbredex.com)  — Redex 提供了一个用于读取、写入和分析 .dex 文件的框架，以及一组使用该框架改进字节码的优化通道.  Redex 优化的 APK 应该更小更快.


<h2 id="nix">没有</h2>

- [deadnix](https://github.com/astro/deadnix) — 扫描 Nix 文件中的死代码（未使用的变量绑定）
- [statix](https://git.peppe.rs/languages/statix/about/)  — Nix 编程语言的 Lints 和建议.  “statix check”突出显示 Nix 代码中的反模式.  “statix fix”可以修复几个这样的事件.


<h2 id="nodejs">节点.js</h2>

- [lockfile-lint](https://github.com/lirantal/lockfile-lint) — Lint 一个 npm 或 yarn lockfile 来分析和检测安全问题
- [njsscan](https://opensecurity.in) — 一个静态应用程序测试 (SAST) 工具，可以使用来自 libsast 的简单模式匹配器和语法感知语义代码模式搜索工具 semgrep 在您的 node.js 应用程序中找到不安全的代码模式.
- [NodeJSScan](https://opensecurity.in)  — 由 libsast 和 semgrep 提供支持的 Node.js 应用程序的静态安全代码扫描程序，构建在 njsscan cli 工具上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.
- [standard](http://standardjs.com) — 检查 Javascript 样式指南问题的 npm 模块.


<h2 id="package">套餐</h2>

- [lintian](https://lintian.debian.org) — Debian 软件包的静态分析工具.
- [rpmlint](https://github.com/rpm-software-management/rpmlint) — 用于检查 rpm 包中常见错误的工具.


<h2 id="protobuf">协议缓冲区</h2>

- [buf](https://buf.build) — 提供 CLI linter，强制执行良好的 API 设计选择和结构
- [protolint](https://github.com/yoheimuta/protolint) — 可插入的 linter 和 fixer 以强制执行 Protocol Buffer 样式和约定.


<h2 id="puppet">木偶</h2>

- [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint) — 检查 Puppet metadata.json 文件有效性的工具.


<h2 id="rails">导轨</h2>

- [dawnscanner](https://github.com/thesp0nge/dawnscanner)  — 用于 Ruby 编写的 Web 应用程序的静态分析安全扫描器. 它支持 Sinatra、Padrino 和 Ruby on Rails 框架.


<h2 id="security">安全/SAST</h2>

- [AzSK](https://azsk.azurewebsites.net/)  — 适用于 Azure (AzSK) 的安全 DevOps 套件在基础架构即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础架构错误配置. 通过 ARM 支持 Azure.
- [brakeman](https://brakemanscanner.org) — 用于 Ruby on Rails 应用程序的静态分析安全漏洞扫描程序.
- [Datree](https://datree.io/) — 一个 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及您组织的政策来防止 Kubernetes 错误配置
- [Enlightn](https://www.laravel-enlightn.com/)  — Laravel 应用程序的静态和动态分析工具，它提供建议以提高 Laravel 应用程序的性能、安全性和代码可靠性. 包含 120 个自动检查.
- [Gitleaks](https://github.com/zricethezav/gitleaks) — 一种 SAST 工具，用于检测 git repos 中的密码、api 密钥和令牌等硬编码机密.
- [gokart](https://github.com/praetorian-inc/gokart)  — Golang 安全分析，重点是尽量减少误报. 它能够跟踪变量和函数参数的来源，以确定输入源是否安全.
- [iblessing](https://www.kitploit.com/2020/08/iblessing-ios-security-exploiting.html)  — iblessing 是一个 iOS 安全漏洞利用工具包. 它可用于逆向工程、二进制分析和漏洞挖掘.
- [kics](https://kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible
- [lockfile-lint](https://github.com/lirantal/lockfile-lint) — Lint 一个 npm 或 yarn lockfile 来分析和检测安全问题
- [njsscan](https://opensecurity.in) — 一个静态应用程序测试 (SAST) 工具，可以使用来自 libsast 的简单模式匹配器和语法感知语义代码模式搜索工具 semgrep 在您的 node.js 应用程序中找到不安全的代码模式.
- [NodeJSScan](https://opensecurity.in)  — 由 libsast 和 semgrep 提供支持的 Node.js 应用程序的静态安全代码扫描程序，构建在 njsscan cli 工具上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.
- [Oversecured](https://oversecured.com)  :copyright: — 适用于 Android 和 iOS 应用程序的企业漏洞扫描程序. 它允许应用程序所有者和开发人员通过将 Oversecured 集成到开发过程中来保护移动应用程序的每个新版本.
- [PT Application Inspector](https://www.ptsecurity.com)  :copyright: — 识别代码缺陷并检测漏洞以防止 Web 攻击. 通过展示可能的漏洞来演示远程代码执行.
- [Qualys Container Security](https://www.qualys.com/apps/container-security) :copyright: — 容器原生应用程序保护，提供对容器化应用程序的可见性和控制.
- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode)  :warning: — 自动代码审查和修复. 它可以帮助您跟踪软件项目中的问题和指标，并且可以轻松扩展以支持新类型的分析.
- [Reshift](https://www.reshiftsecurity.com) :copyright: — 用于检测和管理 Java 安全漏洞的源代码分析工具.
- [scorecard](https://github.com/ossf/scorecard) — 安全记分卡——开源的安全健康指标
- [SearchDiggity](https://resources.bishopfox.com/resources/tools/google-hacking-diggity/attack-tools/)  :copyright: — 识别托管在 Github、Google Code、MS CodePlex、SourceForge 等上的开源代码项目中的漏洞. 该工具带有超过 130 个默认搜索，可识别 SQL 注入、跨站点脚本 (XSS)、不安全的远程和本地文件包含、硬编码密码等. 
- [Symfony Insight](https://insight.symfony.com/) :copyright: — 检测安全风险、发现错误并为 PHP 项目提供可操作的指标.
- [tfsec](https://github.com/tfsec/tfsec)  — Terraform 静态分析工具，通过在构建时检查云错误配置来防止潜在的安全问题，并直接与 HCL 解析器集成以获得更好的结果. 检查是否违反 AWS、Azure 和 GCP 安全最佳实践建议.
- [Tsunami Security Scanner](https://github.com/google/tsunami-security-scanner)  — 具有可扩展插件系统的通用网络安全扫描器，用于以高可信度检测高严重性的类似 RCE 的漏洞. 可以添加用于查找漏洞的自定义检测器（例如开放 API）.


<h2 id="smart-contracts">智能合约</h2>

- [mythril](https://github.com/ConsenSys/mythril) — 包含电池的符号执行框架，可用于自动查找和利用智能合约中的漏洞.
- [MythX](https://mythx.io)  :copyright: — MythX 是一个易于使用的分析平台，它集成了多种分析方法，如模糊测试、符号执行和静态分析，以高精度查找漏洞. 它可以与 Remix 或 VSCode 等工具链集成，也可以从命令行调用.
- [slither](https://github.com/trailofbits/slither) — 运行一套漏洞检测器的静态分析框架，打印有关合同细节的可视信息，并提供一个 API 来轻松编写自定义分析.
- [solhint](https://protofire.github.io/solhint)  — Solhint 是一个由 https://protofire.io 创建的开源项目. 它的目标是为 Solidity 代码提供一个 linting 实用程序.
- [solium](https://ethlint.readthedocs.io/en/latest) — Solium 是一种用于识别和修复 Solidity 智能合约中的样式和安全问题的 linter.


<h2 id="support">支持</h2>

- [LibVCS4j](https://github.com/uni-bremen-agst/libvcs4j) — 一个 Java 库，允许现有工具通过为不同的版本控制系统和问题跟踪器提供通用 API 来分析软件系统的演变.
- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  — 用于从静态代码分析中解析报告文件的 Java 库. 被一堆 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="template">模板语言</h2>

- [ember-template-lint](https://github.com/ember-template-lint/ember-template-lint) — 用于 Ember 或 Handlebars 模板的 Linter.
- [haml-lint](https://github.com/sds/haml-lint) — 编写干净一致的 HAML 的工具.
- [slim-lint](https://github.com/sds/slim-lint) — 用于分析 Slim 模板的可配置工具.
- [yamllint](https://yamllint.readthedocs.io) — 检查 YAML 文件的语法有效性、键重复和外观问题，例如行长、尾随空格和缩进.


<h2 id="terraform">地形</h2>

- [kics](https://kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible
- [shisho](https://docs.shisho.dev/)  — 专为开发人员和安全团队设计的轻量级静态代码分析器. 它允许您使用类似于 sed 的直观 DSL 分析和转换源代码，但用于代码.


<h2 id="translation">翻译</h2>

- [dennis](https://github.com/willkg/dennis) :warning: — 一组用于处理 PO 文件以简化开发和提高质量的实用程序.


<h2 id="vue">Vue.js</h2>

- [HTML-Validate](https://html-validate.org/) — 离线 HTML5 验证器.
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)  — VS Code 的 Vue 工具，由 vls（vue 语言服务器）提供支持.  Vetur 支持格式化嵌入的 HTML、CSS、SCSS、JS、TypeScript 等.  Vetur 只有一个“整个文档格式化程序”，不能格式化任意范围.


<h2 id="wasm">网络组装</h2>

- [Twiggy](https://rustwasm.github.io/twiggy)  — 分析二进制文件的调用图以分析代码大小. 目标是缩小 wasm 二进制大小.


<h2 id="writing">写作</h2>

- [After the Deadline](https://open.afterthedeadline.com) :warning: — 拼写、风格和语法检查器.
- [alex](https://alexjs.com) — 抓住麻木不仁、轻率的写作
- [codespell](https://github.com/codespell-project/codespell) — 检查常见拼写错误的代码.
- [languagetool](https://languagetool.org)  — 25 多种语言的样式和语法检查器. 它发现了许多简单的拼写检查器无法检测到的错误.
- [misspell-fixer](https://github.com/vlajos/misspell-fixer) — 用于修复源代码中常见拼写错误和拼写错误的快速工具.
- [Misspelled Words In Context](https://jwilk.net/software/mwic) — 一种拼写检查器，可将可能的拼写错误分组并在其上下文中显示.
- [proselint](http://proselint.com) — 专注于写作风格而不是语法的英语散文短绒.
- [vale](https://docs.errata.ai/vale/about) — 考虑到速度和可扩展性的散文语法感知 linter.
- [write-good](https://github.com/btford/write-good) — 专注于消除“鼬鼠的话”的 linter.


<h2 id="yaml">YAML</h2>

- [Spectral](https://stoplight.io/open-source/spectral) — 一个灵活的 JSON/YAML linter，对 OpenAPI v2/v3 和 AsyncAPI v2 提供开箱即用的支持.
- [yamllint](https://yamllint.readthedocs.io) — 检查 YAML 文件的语法有效性、键重复和外观问题，例如行长、尾随空格和缩进.


<h2 id="git">走</h2>

- [commitlint](https://commitlint.js.org) — 检查你的提交信息是否符合传统的提交格式


## More Collections

- [Clean code linters](https://github.com/collections/clean-code-linters) — github 集合中的 linter 集合
- [Code Quality Checker Tools For PHP Projects](https://github.com/collections/code-quality-in-php) — github 集合中的 PHP linter 集合
- [go-tools](https://github.com/dominikh/go-tools) — 一组用于处理 Go 代码的工具和库，包括 linter 和静态分析
- [linters](https://github.com/mcandre/linters) — 静态代码分析简介
- [OWASP Source Code Analysis Tools](https://owasp.org/www-community/Source_Code_Analysis_Tools) — 由开放 Web 应用程序安全项目维护的工具列表
- [php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools) — 有用的 PHP 静态分析工具列表
- [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) — 静态代码分析工具列表.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Matthias Endler](https://endler.dev) 已放弃本作品的所有版权和相关或邻近权利.
用于格式化和显示该内容的底层源代码在 MIT 许可下获得许可.


标题图片 [Designed by Freepik](http://www.freepik.com).
