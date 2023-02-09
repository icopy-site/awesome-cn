<div class="github-widget" data-repo="analysis-tools-dev/static-analysis"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!-- 🚨🚨 DON'T EDIT THIS FILE DIRECTLY. Edit `data/tools.yml` instead. 🚨🚨 -->

 <a href="https://analysis-tools.dev/">
   <img width="400px" alt="Analysis Tools" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/logo.png" />
 </a>

这个存储库列出了所有编程语言、构建工具、配置文件等的**静态分析工具**. 重点是提高代码质量的工具，例如 linters 和格式化程序.
The official website, [analysis-tools.dev](https://analysis-tools.dev/) 基于此存储库，并为每个工具添加排名、用户评论和其他资源（如视频）.

[![Website](https://img.shields.io/badge/Website-Online-2B5BAE)](https://analysis-tools.dev)
![CI](https://github.com/analysis-tools-dev/static-analysis/workflows/CI/badge.svg)

## Sponsors

如果没有赞助商的慷慨支持，这个项目是不可能完成的.

<table>
  <tr>
    <td><a href="https://deepcode.ai"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/deepcode.png" /></a></td>
    <td><a href="https://codescene.io/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/codescene.svg" /></a></td>
    <td><a href="https://semgrep.dev/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/semgrep.svg" /></a></td>
    <td><a href="https://codiga.io/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/codiga.svg" /></a></td>
    <td><a href="https://offensive360.com/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/offensive360.png" /></a></td>
  </tr>
</table>

如果您也想支持这个项目，请访问我们 [Github sponsors page](https://github.com/sponsors/analysis-tools-dev).

## Meaning of Symbols:

 - :copyright: 代表专有软件. 所有其他工具都是开源的.
 - :information_source: 表示社区不建议再将此工具用于新项目. 该图标链接到讨论问题.
- :warning: 表示此工具超过 1 年未更新，或者 repo 已存档.

非常欢迎请求请求！  
还要检查姐妹项目， [awesome-dynamic-analysis](https://github.com/mre/awesome-dynamic-analysis).



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
    <li><a href="#coldfusion">ColdFusion</a></li>
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

- [abapOpenChecks](https://docs.abapopenchecks.org) — 通过新的和可定制的检查增强了 SAP 代码检查器.


<h2 id="ada">有</h2>


- [Codepeer](http://www.adacore.com/codepeer) :copyright: — 检测运行时和逻辑错误.

- [Polyspace for Ada](https://www.mathworks.com/products/polyspace-ada.html) :copyright: — 提供代码验证，证明源代码中不存在溢出、被零除、越界数组访问和某些其他运行时错误.

- [SPARK](https://www.adacore.com/about-spark) :copyright: — Ada 的静态分析和形式验证工具集.


<h2 id="asm">集会</h2>


- [STOKE](https://github.com/StanfordPL/stoke)  — 一种与编程语言无关的随机优化器，适用于 x86_64 指令集. 它使用随机搜索来探索所有可能的程序变换的极高维空间.


<h2 id="awk">awk</h2>


- [gawk --lint](https://www.gnu.org/software/gawk/manual/html_node/Options.html) — 对可疑或不可移植到其他 awk 实现的构造发出警告.


<h2 id="c">C</h2>


- [Astrée](https://www.absint.com/astree/index.htm)  :copyright: — Astrée 自动证明 C/C++ 应用程序中不存在运行时错误和无效的并发行为. 它适用于浮点计算，速度非常快，而且非常精确. 该分析器还检查 MISRA/CERT/CWE/Adaptive Autosar 编码规则，并支持 ISO 26262、DO-178C A 级和其他安全标准的资格认证.  Jenkins 和 Eclipse 插件可用.

- [CBMC](http://www.cprover.org/cbmc) — C 程序的有界模型检查器、用户定义的断言、标准断言、多个覆盖率度量分析.

- [clang-tidy](http://clang.llvm.org/extra/clang-tidy) — clang 静态分析器.

- [clazy](https://github.com/KDE/clazy)  — 基于 Clang 框架的面向 Qt 的静态代码分析器.  clazy 是一个编译器插件，它允许 clang 理解 Qt 语义. 您会收到 50 多个与 Qt 相关的编译器警告，范围从不需要的内存分配到 API 的滥用，包括用于自动重构的修复.

- [CMetrics](https://github.com/MetricsGrimoire/CMetrics) — 测量 C 文件的大小和复杂性.

- [CPAchecker](https://cpachecker.sosy-lab.org)  — 用于 C 程序的可配置软件验证的工具. 选择 CPAchecker 这个名称是为了反映该工具基于 CPA 概念并用于检查软件程序.

- [cppcheck](http://cppcheck.sourceforge.net) — C/C++ 代码的静态分析.

- [CppDepend](https://www.cppdepend.com) :warning: :copyright: — 测量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.

- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) — 遵循 Google 风格指南的自动 C++ 检查器.

- [cqmetrics](https://github.com/dspinellis/cqmetrics) — C 代码的质量指标.

- [CScout](https://www.spinellis.gr/cscout) — C 和 C 预处理器代码的复杂性和质量指标.

- [ESBMC](http://esbmc.org) — ESBMC 是一种开源、许可的、上下文有界的模型检查器，基于可满足性模理论，用于验证单线程和多线程 C/C++ 程序.

- [flawfinder](http://dwheeler.com/flawfinder/) — 发现可能的安全弱点.

- [flint++](https://github.com/JossWhittle/FlintPlusPlus) — flint 的跨平台、零依赖端口，这是 Facebook 开发和使用的 C++ lint 程序.

- [Frama-C](http://frama-c.com) — 用于 C 代码的可靠且可扩展的静态分析器.

- [GCC](https://gcc.gnu.org/onlinedocs/gcc/Static-Analyzer-Options.html)  — GCC 编译器自版本 10 起具有静态分析功能.此选项仅在 GCC 配置为启用分析器支持时可用. 它还可以将其诊断信息输出到 SARIF 格式的 JSON 文件（从 v13 开始）.

- [Goblint](https://goblint.in.tum.de)  — 用于分析多线程 C 程序的静态分析器. 它的主要重点是检测数据竞争，但它也报告其他运行时错误，例如缓冲区溢出和空指针取消引用.

- [Helix QAC](https://www.perforce.com/products/helix-qac)  :copyright: — 嵌入式软件的企业级静态分析. 支持 MISRA、CERT 和 AUTOSAR 编码标准.

- [IKOS](https://github.com/nasa-sw-vnv/ikos) — 基于 LLVM 的 C/C++ 代码的可靠静态分析器.

- [Joern](https://joern.io) — 基于代码属性图的C/C++开源代码分析平台

- [LDRA](https://ldra.com) :copyright: — 一个工具套件，包括针对各种标准的静态分析 (TBVISION)，包括 MISRA C 和 C++、JSF++ AV、CWE、CERT C、CERT C++ 和自定义规则.

- [PC-lint](https://www.gimpel.com)  :copyright: — C/C++ 的静态分析. 在 Windows/Linux/MacOS 下原生运行. 分析几乎任何平台的代码，支持 C11/C18 和 C++17.

- [Phasar](https://phasar.org) — 基于 LLVM 的静态分析框架，带有污点和类型状态分析.

- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) :copyright: — 标识 C 和 C++ 嵌入式软件中的运行时错误、并发问题、安全漏洞和其他缺陷.

- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) :copyright: — 提供代码验证，证明 C 和 C++ 源代码中不存在溢出、被零除、数组访问越界以及某些其他运行时错误.

- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) — 在编译时使用 LLVM 分析 C/C++ 代码.

- [splint](http://splint.org) — 注释辅助静态程序检查器.

- [SVF](http://svf-tools.github.io/SVF) — 一种静态工具，支持对 C 和 C++ 程序进行可扩展且精确的过程间依赖性分析.

- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) — Vera++ 是一个用于验证、分析和转换 C++ 源代码的可编程工具.


<h2 id="csharp">C#</h2>


- [.NET Analyzers](https://github.com/DotNetAnalyzers) — 使用 .NET 编译器平台开发分析器（诊断和代码修复）的组织.

- [ArchUnitNET](https://github.com/TNG/ArchUnitNET) — A C# architecture test library to specify and assert architecture rules in C# for automated testing.

- [code-cracker](http://code-cracker.github.io) — An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.

- [CSharpEssentials](https://github.com/DustinCampbell/CSharpEssentials) — C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features.

- [Designite](http://www.designite-tools.com) :copyright: — Designite 支持检测各种架构、设计和实现气味，各种代码质量指标的计算和趋势分析.

- [Gendarme](https://www.mono-project.com/docs/tools+libraries/tools/gendarme) — Gendarme 检查包含 ECMA CIL 格式（Mono 和 .NET）代码的程序和库.

- [Infer#](https://github.com/microsoft/infersharp) — InferSharp (also referred to as Infer#) is an interprocedural and  scalable static code analyzer for C#. Via the capabilities of Facebook's Infer,  this tool detects null pointer dereferences and resource leaks.

- [NDepend](http://www.ndepend.com) :copyright: — 衡量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.

- [Puma Scan](https://pumasecurity.io) — Puma Scan 为开发团队在 Visual Studio 中编写代码时的常见漏洞（XSS、SQLi、CSRF、LDPi、加密、反序列化等）提供实时安全代码分析.

- [Roslynator](https://github.com/JosefPihrt/Roslynator) — A collection of 190+ analyzers and 190+ refactorings for C#, powered by Roslyn.

- [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) — 基于与 VS 集成的 Roslyn 的静态分析器集合.

- [Wintellect.Analyzers](https://github.com/Wintellect/Wintellect.Analyzers) — .NET 编译器平台（“Roslyn”）诊断分析器和代码修复.


<h2 id="cpp">C++</h2>


- [Astrée](https://www.absint.com/astree/index.htm)  :copyright: — Astrée 自动证明 C/C++ 应用程序中不存在运行时错误和无效的并发行为. 它适用于浮点计算，速度非常快，而且非常精确. 该分析器还检查 MISRA/CERT/CWE/Adaptive Autosar 编码规则，并支持 ISO 26262、DO-178C A 级和其他安全标准的资格认证.  Jenkins 和 Eclipse 插件可用.

- [CBMC](http://www.cprover.org/cbmc) — C 程序的有界模型检查器、用户定义的断言、标准断言、多个覆盖率度量分析.

- [clang-tidy](http://clang.llvm.org/extra/clang-tidy) — clang 静态分析器.

- [clazy](https://github.com/KDE/clazy)  — 基于 Clang 框架的面向 Qt 的静态代码分析器.  clazy 是一个编译器插件，它允许 clang 理解 Qt 语义. 您会收到 50 多个与 Qt 相关的编译器警告，范围从不需要的内存分配到 API 的滥用，包括用于自动重构的修复.

- [CMetrics](https://github.com/MetricsGrimoire/CMetrics) — 测量 C 文件的大小和复杂性.

- [cppcheck](http://cppcheck.sourceforge.net) — C/C++ 代码的静态分析.

- [CppDepend](https://www.cppdepend.com) :warning: :copyright: — 测量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.

- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) — 遵循 Google 风格指南的自动 C++ 检查器.

- [cqmetrics](https://github.com/dspinellis/cqmetrics) — C 代码的质量指标.

- [CScout](https://www.spinellis.gr/cscout) — C 和 C 预处理器代码的复杂性和质量指标.

- [ESBMC](http://esbmc.org) — ESBMC 是一种开源、许可的、上下文有界的模型检查器，基于可满足性模理论，用于验证单线程和多线程 C/C++ 程序.

- [flawfinder](http://dwheeler.com/flawfinder/) — 发现可能的安全弱点.

- [flint++](https://github.com/JossWhittle/FlintPlusPlus) — flint 的跨平台、零依赖端口，这是 Facebook 开发和使用的 C++ lint 程序.

- [Frama-C](http://frama-c.com) — 用于 C 代码的可靠且可扩展的静态分析器.

- [Helix QAC](https://www.perforce.com/products/helix-qac)  :copyright: — 嵌入式软件的企业级静态分析. 支持 MISRA、CERT 和 AUTOSAR 编码标准.

- [IKOS](https://github.com/nasa-sw-vnv/ikos) — 基于 LLVM 的 C/C++ 代码的可靠静态分析器.

- [Joern](https://joern.io) — 基于代码属性图的C/C++开源代码分析平台

- [LDRA](https://ldra.com) :copyright: — 一个工具套件，包括针对各种标准的静态分析 (TBVISION)，包括 MISRA C 和 C++、JSF++ AV、CWE、CERT C、CERT C++ 和自定义规则.

- [PC-lint](https://www.gimpel.com)  :copyright: — C/C++ 的静态分析. 在 Windows/Linux/MacOS 下原生运行. 分析几乎任何平台的代码，支持 C11/C18 和 C++17.

- [Phasar](https://phasar.org) — 基于 LLVM 的静态分析框架，带有污点和类型状态分析.

- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) :copyright: — 标识 C 和 C++ 嵌入式软件中的运行时错误、并发问题、安全漏洞和其他缺陷.

- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) :copyright: — 提供代码验证，证明 C 和 C++ 源代码中不存在溢出、被零除、数组访问越界以及某些其他运行时错误.

- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) — 在编译时使用 LLVM 分析 C/C++ 代码.

- [splint](http://splint.org) — 注释辅助静态程序检查器.

- [SVF](http://svf-tools.github.io/SVF) — 一种静态工具，支持对 C 和 C++ 程序进行可扩展且精确的过程间依赖性分析.

- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) — Vera++ 是一个用于验证、分析和转换 C++ 源代码的可编程工具.


<h2 id="clojure">Clojure 语言</h2>


- [clj-kondo](https://github.com/borkdude/clj-kondo)  — 激发喜悦的 Clojure 代码 linter. 它会在您打字时通知您潜在的错误.


<h2 id="coffeescript">咖啡脚本</h2>


- [coffeelint](https://coffeelint.github.io/) — 一种有助于保持 CoffeeScript 代码整洁和一致的样式检查器.


<h2 id="coldfusion">冷聚变</h2>


- [Fixinator](https://fixinator.app)  :copyright: — ColdFusion 或 CFML 代码的静态安全代码分析. 设计用于在 CI 管道或开发人员终端中工作.


<h2 id="crystal">水晶</h2>


- [ameba](https://crystal-ameba.github.io) — Crystal 的静态代码分析工具.

- [crystal](https://crystal-lang.org) — Crystal 编译器具有内置的 linting 功能.


<h2 id="dart">镖</h2>


- [Dart Code Metrics](https://pub.dev/packages/dart_code_metrics)  — Dart 的额外 linter. 报告代码指标、检查反模式并为 Dart 分析器提供附加规则.

- [effective_dart](https://pub.dev/packages/effective_dart) — 与 Effective Dart 指南相对应的 Linter 规则

- [lint](https://github.com/passsy/dart-lint)  — 一套自以为是的、社区驱动的 lint 规则集，用于 Dart 和 Flutter 项目. 喜欢迂腐但更严格

- [Linter for dart](https://dart-lang.github.io/linter) — Dart 的样式 linter.


<h2 id="delphi">德尔福</h2>


- [Fix Insight](https://www.tmssoftware.com/site/fixinsight.asp)  :copyright: — 用于静态代码分析的免费 IDE 插件.  _Pro_ 版本包括用于自动化目的的命令行工具.

- [Pascal Analyzer](https://peganza.com/products_pal.html)  :copyright: — 具有大量报告的静态代码分析工具. 免费的 _Lite_ 版本提供有限的报告.

- [Pascal Expert](https://peganza.com/products_pex.html)  :copyright: — 用于代码分析的 IDE 插件. 包括一部分 Pascal Analyzer 报告功能，适用于 Delphi 2007 及更高版本.


<h2 id="dlang">党</h2>


- [D-scanner](https://github.com/dlang-community/D-Scanner) — D-Scanner 是分析D 源代码的工具.


<h2 id="elixir">长生不老药</h2>


- [credo](https://github.com/rrrene/credo) — 专注于代码一致性和教学的静态代码分析工具.

- [dialyxir](https://github.com/jeremyjh/dialyxir) — 混合任务以简化 Dialyzer 在 Elixir 项目中的使用.

- [sobelow](https://github.com/nccgroup/sobelow) — Phoenix Framework 的以安全为中心的静态分析.


<h2 id="elm">榆树</h2>


- [elm-analyse](https://stil4m.github.io/elm-analyse) — 一种允许您分析 Elm 代码、识别缺陷并应用最佳实践的工具.

- [elm-review](https://package.elm-lang.org/packages/jfmengels/elm-review/latest) — Analyzes whole Elm projects, with a focus on shareable and custom rules written in Elm that add guarantees the Elm compiler doesn't give you.


<h2 id="erlang">二郎</h2>


- [dialyzer](https://www.erlang.org/doc/man/dialyzer.html)  — DIALYZER，一个用于 ERlang 程序的差异分析器.  Dialyzer 是一种静态分析工具，可在单个 Erlang 模块或整个（组）应用程序中识别软件差异，例如明确的类型错误、由于编程错误而变得无效或无法访问的代码，以及不必要的测试.
 Dialyzer 从调试编译的 BEAM 字节码或 Erlang 源代码开始分析. 报告差异的文件和行号以及差异的指示.  Dialyzer 的分析基于成功打字的概念，它允许发出声音警告（无误报）.

- [elvis](https://github.com/inaka/elvis) — Erlang 风格评论家.

- [Primitive Erlang Security Tool (PEST)](https://github.com/okeuday/pest) — 对 Erlang 源代码进行基本扫描并报告任何可能导致 Erlang 源代码不安全的函数调用的工具.


<h2 id="fsharp">F#</h2>


- [FSharpLint](http://fsprojects.github.io/FSharpLint) — Lint tool for F#.


<h2 id="fortran">Fortran</h2>


- [i-Code CNES for Fortran](https://github.com/lequal/i-CodeCNES) — Fortran 77、Fortran 90 和 Shell 的开源静态代码分析工具.


<h2 id="go">去</h2>


- [aligncheck](https://gitlab.com/opennota/check) — 查找低效打包的结构.

- [bodyclose](https://github.com/timakin/bodyclose) — 检查 HTTP 响应主体是否关闭.

- [deadcode](https://github.com/tsenart/deadcode) — 查找未使用的代码.

- [dingo-hunter](https://github.com/nickng/dingo-hunter) — 用于在 Go 中查找死锁的静态分析器.

- [dogsled](https://github.com/alexkohler/dogsled) — 查找包含太多空白标识符的赋值/声明.

- [dupl](https://github.com/mibk/dupl) — 报告可能重复的代码.

- [errcheck](https://github.com/kisielk/errcheck) — 检查是否使用了错误返回值.

- [errwrap](https://github.com/fatih/errwrap)  — 使用新的 %w 动词指令包装并修复 Go 错误. 此工具分析 fmt.Errorf() 调用并报告包含与 Go v1.13 中引入的新 %w 动词指令不同的动词指令的调用. 它还能够重写调用以使用新的 %w wrap 动词指令.

- [flen](https://github.com/lafolle/flen) — 获取有关 Go 包中函数长度的信息.

- [Go Meta Linter](https://github.com/alecthomas/gometalinter)  :warning: — 同时运行 Go lint 工具并规范化它们的输出. 对新项目使用 `golangci-lint`.

- [go tool vet --shadow](https://golang.org/cmd/vet#hdr-Shadowed_variables) — 报告可能被无意遮蔽的变量.

- [go vet](https://golang.org/cmd/vet) — 检查 Go 源代码并报告可疑.

- [go-consistent](https://github.com/Quasilyte/go-consistent) — 帮助您使 Go 程序更加一致的分析器.

- [go-critic](https://github.com/go-critic/go-critic) — Go 源代码 linter，维护当前未在其他 linter 中实现的检查.

- [go/ast](https://golang.org/pkg/go/ast) — 包 ast 声明用于表示 Go 包语法树的类型.

- [gochecknoglobals](https://github.com/leighmcculloch/gochecknoglobals) — 检查是否不存在全局变量.

- [goconst](https://github.com/jgautheron/goconst) — 查找可以用常量替换的重复字符串.

- [gocyclo](https://github.com/fzipp/gocyclo) — 计算 Go 源代码中函数的圈复杂度.

- [gofmt -s](https://golang.org/cmd/gofmt) — Checks if the code is properly formatted and could not be further simplified.

- [gofumpt](https://github.com/mvdan/gofumpt)  — 执行比 `gofmt` 更严格的格式，同时向后兼容. 也就是说，`gofumpt` 对 `gofmt` 满意的格式子集感到满意.
从 Go 1.19 开始，该工具是 `gofmt` 的一个分支，需要 Go 1.18 或更高版本. 它可以用作格式化 Go 代码的直接替代品，并且在 gofumpt 之后运行 gofmt 应该不会产生任何变化.
 `gofumpt` 永远不会添加与 `gofmt` 格式不一致的规则. 所以我们扩展了 gofmt 而不是与之竞争.

- [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) — 检查丢失或未引用的包导入.

- [gokart](https://github.com/praetorian-inc/gokart)  — Golang 安全分析，重点是最大限度地减少误报. 它能够追踪变量和函数参数的来源，以确定输入源是否安全.

- [GolangCI-Lint](https://golangci-lint.run) — `Go Meta Linter` 的替代方案：GolangCI-Lint 是一个 linters 聚合器.

- [golint](https://github.com/golang/lint) — 打印出 Go 源代码中的编码风格错误.

- [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) — 同时运行许多 linters 并将它们的输出规范化为报告.

- [goroutine-inspect](https://github.com/linuxerwang/goroutine-inspect) — 分析 Golang goroutine 转储的交互式工具.

- [gosec (gas)](https://securego.io) — 通过扫描 Go AST 检查源代码是否存在安全问题.

- [gotype](https://pkg.go.dev/golang.org/x/tools/cmd/gotype) — 类似于 Go 编译器的句法和语义分析.

- [govulncheck](https://go.dev/blog/vuln)  — Govulncheck 报告影响 Go 代码的已知漏洞. 它使用源代码或二进制符号表的静态分析来缩小报告范围，仅报告可能影响应用程序的报告.
默认情况下，govulncheck 向 https://vuln.go.dev 上的 Go 漏洞数据库发出请求. 对漏洞数据库的请求仅包含模块路径，不包含代码或程序的其他属性.

- [ineffassign](https://github.com/gordonklaus/ineffassign) — Detect ineffectual assignments in Go code.

- [interfacer](https://github.com/mvdan/interfacer) :warning: — 建议可以使用的更窄的接口.

- [lll](https://github.com/walle/lll) — 报告排长队.

- [maligned](https://github.com/mdempsky/maligned) — 检测如果对字段进行排序会占用更少内存的结构.

- [misspell](https://github.com/client9/misspell) — 查找经常拼写错误的英语单词.

- [nakedret](https://github.com/alexkohler/nakedret) — 发现裸回报.

- [nargs](https://github.com/alexkohler/nargs) — 查找函数声明中未使用的参数.

- [prealloc](https://github.com/alexkohler/prealloc) — 查找可能预分配的切片声明.

- [Reviewdog](https://github.com/haya14busa/reviewdog) — 用于从任何代码托管服务中的任何 linter 发布评论的工具.

- [revive](https://revive.run)  — 用于 Go 的快速、可配置、可扩展、灵活且美观的 linter. 直接替换 golint.

- [safesql](https://github.com/stripe/safesql) — Golang 的静态分析工具，可防止 SQL 注入.

- [shisho](https://docs.shisho.dev/)  — 为开发人员和安全团队设计的轻量级静态代码分析器. 它允许您使用类似于 sed 的直观 DSL 分析和转换源代码，但用于代码.

- [staticcheck](https://staticcheck.io) — 专注于查找错误、简化代码和提高性能的静态分析.

- [structcheck](https://gitlab.com/opennota/check) — 查找未使用的结构字段.

- [structslop](https://github.com/orijtech/structslop) — Go 的静态分析器，建议结构字段重新排列以提供最大的空间/分配效率

- [test](http://golang.org/pkg/testing) — 显示 stdlib 测试模块中测试失败的位置.

- [unconvert](https://github.com/mdempsky/unconvert) — 检测冗余类型转换.

- [unparam](https://github.com/mvdan/unparam) — 查找未使用的函数参数.

- [varcheck](https://gitlab.com/opennota/check) — 查找未使用的全局变量和常量.

- [wsl](https://github.com/bombsimon/wsl) — 在正确的地方强制使用空行.


<h2 id="groovy">时髦的</h2>


- [CodeNarc](https://codenarc.github.io/CodeNarc) — Groovy 源代码的静态分析工具，支持监控和执行许多编码标准和最佳实践.


<h2 id="haskell">哈斯克尔</h2>


- [brittany](https://github.com/lspitzner/brittany) — Haskell 源代码格式化程序

- [HLint](https://github.com/ndmitchell/hlint) — HLint 是一种工具，用于建议对 Haskell 代码进行可能的改进.

- [Liquid Haskell](https://ucsd-progsys.github.io/liquidhaskell-blog/) — Liquid Haskell 是 Haskell 程序的精化类型检查器.

- [Stan](https://kowainik.github.io/projects/stan) — Stan 是一个命令行工具，用于分析 Haskell 项目并以有用的方式输出发现的漏洞以及检测到的问题的可能解决方案.

- [Weeder](https://github.com/ocharles/weeder) — 用于检测 Haskell 代码中死导出或包导入的工具.


<h2 id="haxe">混合的</h2>


- [Haxe Checkstyle](http://haxecheckstyle.github.io/docs/haxe-checkstyle/home.html) — 一种静态分析工具，可帮助开发人员编写符合编码标准的 Haxe 代码.


<h2 id="java">爪哇</h2>


- [Checker Framework](https://checkerframework.org) — Java 的可插入类型检查.

- [checkstyle](https://checkstyle.org) — Checking Java source code for adherence to a Code Standard or set of validation rules (best practices).

- [ck](https://github.com/mauricioaniche/ck) — 通过处理源 Java 文件计算 Chidamber 和 Kemerer 面向对象的指标.

- [ckjm](http://www.spinellis.gr/sw/ckjm) — 通过处理已编译 Java 文件的字节码来计算 Chidamber 和 Kemerer 面向对象的指标.

- [CogniCrypt](https://www.eclipse.org/cognicrypt) — 检查 Java 源代码和字节代码是否正确使用了加密 API.

- [DesigniteJava](http://www.designite-tools.com/designitejava) :copyright: — DesigniteJava 支持检测各种体系结构、设计和实现气味以及各种代码质量指标的计算.

- [Diffblue](https://www.diffblue.com/) :copyright: — Diffblue 是一家软件公司，为软件开发团队提供基于 AI 的代码分析和测试解决方案.
它的技术可帮助开发人员在其软件开发过程中实现自动化测试、查找错误并减少人工劳动. 该公司的主要产品 Diffblue Cover 使用 AI 为 Java 代码生成和运行单元测试，有助于发现错误并提高代码质量.

- [Doop](https://bitbucket.org/yanniss/doop)  — Doop 是一个用于 Java/Android 程序静态分析的声明式框架，以指针分析算法为中心.  Doop 提供了种类繁多的分析以及周围的脚手架来运行端到端的分析（事实生成、处理、统计等）.

- [Error-prone](https://errorprone.info) — 将常见的 Java 错误捕获为编译时错误.

- [fb-contrib](http://fb-contrib.sourceforge.net) — 带有附加错误检测器的 FindBugs 插件.

- [forbidden-apis](https://github.com/policeman-tools/forbidden-apis)  — 检测并禁止调用特定方法/类/字段（例如从没有字符集的文本流中读取）.  Maven/Gradle/Ant 兼容.

- [google-java-format](https://github.com/google/google-java-format) — 谷歌样式重新格式化.

- [HuntBugs](https://github.com/amaembo/huntbugs) :warning: — 基于 Procyon 编译器工具的字节码静态分析器工具，旨在取代 FindBugs.

- [IntelliJ IDEA](https://www.jetbrains.com/idea) :copyright: — 捆绑了大量针对 Java 和 Kotlin 的检查，包括用于重构、格式化等的工具.

- [JArchitect](https://www.jarchitect.com) :copyright: — 衡量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.

- [JBMC](https://www.cprover.org/jbmc) — Java 的有界模型检查器（字节码），验证用户定义的断言、标准断言、多个覆盖率度量分析.

- [NullAway](https://github.com/uber/NullAway)  — 具有低构建时间开销的基于类型的空指针检查器； 一个 [Error Prone](http://errorprone.info/) 插入.

- [OWASP Dependency Check](https://owasp.org/www-project-dependency-check) — 检查依赖项是否存在已知的、公开披露的漏洞.

- [qulice](https://www.qulice.com) — 结合了一些（预配置的）静态分析工具（checkstyle、PMD、Findbugs 等）.

- [Soot](https://soot-oss.github.io/soot) — 用于分析和转换 Java 和 Android 应用程序的框架.

- [Spoon](http://spoon.gforge.inria.fr)  — Spoon 是一个元编程库，用于分析和转换 Java 源代码（包括 Java 9、10、11、12、13、14）. 它解析源文件以构建具有强大分析和转换 API 的精心设计的 AST. 可以集成到 Maven 和 Gradle 中.

- [SpotBugs](https://spotbugs.github.io)  — SpotBugs 是 FindBugs 的继任者. 用于静态分析以查找 Java 代码中的错误的工具.

- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  — 用于从静态代码分析中解析报告文件的 Java 库. 由一堆 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="javascript">JavaScript</h2>


- [aether](http://aetherjs.com) — 在节点或浏览器中检查、分析、规范化、转换、沙盒、运行、逐步执行和可视化用户 JavaScript.

- [Closure Compiler](https://developers.google.com/closure/compiler) — 一种用于提高效率、减小大小并在 JavaScript 文件中提供代码警告的编译器工具.

- [ClosureLinter](https://github.com/google/closure-linter)  :warning: — 确保您项目的所有 JavaScript 代码都遵循 Google JavaScript 样式指南中的准则. 它还可以自动修复许多常见错误.

- [complexity-report](https://github.com/escomplex/complexity-report) :warning: — JavaScript 项目的软件复杂性分析.

- [DeepScan](https://deepscan.io) :copyright: — 针对运行时错误和质量问题而非编码约定的 JavaScript 分析器.

- [es6-plato](https://github.com/the-simian/es6-plato) — 可视化 JavaScript (ES6) 源代码的复杂性.

- [escomplex](https://github.com/jared-stilwell/escomplex) — JavaScript 系列抽象语法树的软件复杂性分析.

- [Esprima](https://esprima.org) — 用于多用途分析的 ECMAScript 解析基础设施.

- [flow](https://flow.org) — JavaScript 的静态类型检查器.

- [hegel](https://hegel.js.org) — JavaScript 的静态类型检查器，偏向于类型推断和强类型系统.

- [jshint](https://jshint.com/about) [:information_source:](https://github.com/analysis-tools-dev/static-analysis/blob/master/<https://github.com/analysis-tools-dev/static-analysis/issues/223>) — 检测 JavaScript 代码中的错误和潜在问题并强制执行团队的编码约定.

- [JSLint](https://github.com/douglascrockford/JSLint) [:information_source:](https://github.com/analysis-tools-dev/static-analysis/blob/master/<https://github.com/analysis-tools-dev/static-analysis/issues/223>) — JavaScript 代码质量工具.

- [JSPrime](http://dpnishant.github.io/jsprime) :warning: — 静态安全分析工具.

- [NodeJSScan](https://opensecurity.in)  — 一个用于 Node.js 应用程序的静态安全代码扫描器，由 libsast 和 semgrep 提供支持，构建在 njsscan cli 工具之上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.

- [plato](https://github.com/es-analysis/plato) :warning: — 可视化 JavaScript 源代码的复杂性.

- [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer) — Web 组件的静态分析框架.

- [Reshift](https://www.reshiftsecurity.com) :copyright: — 用于检测和管理 JavaScript 安全漏洞的源代码分析工具.

- [retire.js](http://retirejs.github.io/retire.js) — 检测使用具有已知漏洞的 JavaScript 库的扫描程序.

- [RSLint](http://rslint.org/) — 一个用 Rust 编写的 (WIP) JavaScript linter，旨在尽可能快、可定制且易于使用.

- [standard](http://standardjs.com) — 检查 Javascript Styleguide 问题的 npm 模块.

- [tern](https://ternjs.net) — 一个 JavaScript 代码分析器，用于深入的跨编辑器语言支持.

- [TypL](https://typl.dev) — 使用 TypL，您只需编写完全标准的 JS，该工具会通过强大的推理来确定您的类型.

- [xo](https://github.com/xojs/xo)  — 自以为是但可配置的 ESLint 包装器，其中包含许多好东西. 执行严格且可读的代码.

- [yardstick](https://github.com/calmh/yardstick) :warning: — Javascript 代码指标.


<h2 id="julia">茱莉亚</h2>


- [StaticLint](https://github.com/julia-vscode/StaticLint.jl) — Julia 的静态代码分析


<h2 id="kotlin">科特林</h2>


- [detekt](https://detekt.github.io/detekt) — Kotlin 代码的静态代码分析.

- [diktat](https://diktat.saveourtool.com) — 严格的 Kotlin 编码标准和检测并自动修复代码异味的 linter.

- [ktfmt](https://facebook.github.io/ktfmt/) — 重新格式化 Kotlin 源代码以符合 Kotlin 代码约定的通用社区标准的程序.
插件存储库中提供了一个 ktfmt IntelliJ 插件. 要安装它，请转到您的 IDE 设置并选择插件类别. 单击市场选项卡，搜索 ktfmt 插件，然后单击安装按钮.

- [ktlint](https://ktlint.github.io) — 一个带有内置格式化程序的反 bikeshedding Kotlin linter.


<h2 id="lua">二</h2>


- [luacheck](https://github.com/mpeterv/luacheck) — 用于 Lua 代码的 linting 和静态分析的工具.

- [lualint](https://github.com/philips/lualint) — lualint 对 Lua 源代码中的全局变量使用情况执行基于 luac 的静态分析.

- [Luanalysis](https://plugins.jetbrains.com/plugin/14698-luanalysis) — 用于静态类型 Lua 开发的 IDE.


<h2 id="matlab">软件</h2>


- [mlint](https://mathworks.com/help/matlab/ref/mlint.html) :copyright: — 检查 MATLAB 代码文件是否存在可能的问题.


<h2 id="nim">他</h2>


- [DrNim](https://nim-lang.org/docs/drnim.html) — DrNim 将 Nim 前端与 Z3 证明引擎相结合，以允许验证/验证用 Nim 编写的软件.

- [nimfmt](https://github.com/FedericoCeratto/nimfmt) — Nim 代码格式化程序/linter/样式检查器


<h2 id="ocaml">奥卡姆</h2>


- [Sys](https://github.com/PLSysSec/sys)  — 用于在（浏览器）代码中查找错误的静态/符号工具. 它使用 LLVM AST 来查找未初始化内存访问等错误.

- [VeriFast](https://github.com/verifast/verifast)  — 一种用于对单线程和多线程 C 和 Java 程序的正确性进行模块化形式验证的工具，这些程序用分离逻辑编写的前置条件和后置条件进行了注释. 为了表达丰富的规范，程序员可以定义归纳数据类型、基于这些数据类型的原始递归纯函数以及抽象分离逻辑谓词.


<h2 id="php">PHP</h2>


- [churn-php](https://github.com/bmitch/churn-php) — 帮助发现重构的良好候选者.

- [dephpend](https://github.com/mihaeu/dephpend) — 依赖分析工具.

- [deprecation-detector](https://github.com/sensiolabs-de/deprecation-detector) — 查找已弃用 (Symfony) 代码的用法.

- [deptrac](https://github.com/sensiolabs-de/deptrac) — 执行软件层之间依赖关系的规则.

- [DesignPatternDetector](https://github.com/Halleck45/DesignPatternDetector) — 检测 PHP 代码中的设计模式.

- [EasyCodingSt和ard](https://www.tomasvotruba.com/blog/2017/05/03/combine-power-of-php-code-sniffer-和-php-cs-fixer-in-3-lines) - 结合 [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 和 [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).

- [Enlightn](https://www.laravel-enlightn.com/)  — Laravel 应用程序的静态和动态分析工具，提供建议以提高 Laravel 应用程序的性能、安全性和代码可靠性. 包含 120 个自动检查.

- [exakat](https://www.exakat.io) — PHP 的自动代码审查引擎.

- [GrumPHP](https://github.com/phpro/grumphp) — 检查每次提交的代码.

- [larastan](https://github.com/nunomaduro/larastan)  — 为 Laravel 添加静态分析，提高开发人员的生产力和代码质量. 它是 PHPStan 的包装器.

- [Mondrian](http://trismegiste.github.io/Mondrian) — 一组使用图论的静态分析和重构工具.

- [Nitpick CI](https://nitpick-ci.com) :copyright: — 自动 PHP 代码审查.

- [parallel-lint](https://github.com/php-parallel-lint/PHP-Parallel-Lint) — 此工具检查 PHP 文件的语法比串行检查更快，输出更精美.

- [Parse](https://github.com/psecio/parse) — 静态安全扫描器.

- [pdepend](https://pdepend.org) — 计算软件指标，例如 PHP 代码的圈复杂度.

- [phan](https://github.com/phan/phan/wiki) — 来自 etsy 的现代静态分析器.

- [PHP Architecture Tester](https://github.com/carlosas/phpat) — 易于使用的 PHP 架构测试工具.

- [PHP Assumptions](https://github.com/rskuipers/php-assumptions) — 检查薄弱的假设.

- [PHP Coding Standards Fixer](https://cs.symfony.com) — 根据 PSR-1、PSR-2 和 Symfony 标准等标准修复您的代码.

- [PHP Insights](https://phpinsights.com)  — 从您的控制台进行即时 PHP 质量检查. 代码质量和编码风格的分析以及代码架构及其复杂性的概述.

- [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-) — PHP 的静态代码分析器.

- [PHP Refactoring Browser](http://qafoolabs.github.io/php-refactoring-browser) — 重构助手.

- [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) — 根据语义版本控制建议下一个版本.

- [PHP-Parser](https://github.com/nikic/PHP-Parser) — 用 PHP 编写的 PHP 解析器.

- [php-speller](https://github.com/mekras/php-speller) — PHP 拼写检查库.

- [PHP-Token-Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) — 模拟 PHP 内部反射的库.

- [php7cc](https://github.com/sstalle/php7cc) :warning: — PHP 7 兼容性检查器.

- [php7mar](https://github.com/Alexia/php7mar) :warning: — 协助开发人员将他们的代码快速移植到 PHP 7.

- [PHP_CodeSniffer](https://pear.php.net/package/PHP_CodeSniffer) — 检测是否违反一组已定义的编码标准.

- [phpca](https://github.com/wapmorgan/PhpCodeAnalyzer) — 查找非内置扩展的用法.

- [phpcpd](https://github.com/sebastianbergmann/phpcpd) — PHP 代码的复制/粘贴检测器.

- [phpdcd](https://github.com/sebastianbergmann/phpdcd) :warning: — PHP 代码的死代码检测器 (DCD).

- [PhpDependencyAnalysis](https://mamuz.github.io/PhpDependencyAnalysis) — 为项目构建依赖关系图.

- [PhpDeprecationDetector](https://github.com/wapmorgan/PhpDeprecationDetector)  — PHP 代码分析器，用于搜索较新解释器版本中已弃用功能的问题. 它会发现已删除的对象（函数、变量、常量和 ini 指令）、已弃用的函数功能以及禁止使用的名称或技巧（例如，新版本中的保留标识符）.

- [phpdoc-to-typehint](https://github.com/dunglas/phpdoc-to-typehint) — 使用 PHPDoc 注释向现有 PHP 项目添加标量类型提示和返回类型.

- [phpDocumentor](https://www.phpdoc.org) — 分析 PHP 源代码以生成文档.

- [phploc](https://github.com/sebastianbergmann/phploc) — 用于快速测量 PHP 项目大小和分析结构的工具.

- [PHPMD](https://phpmd.org) — 查找代码中可能存在的错误.

- [PhpMetrics](http://www.phpmetrics.org) — 计算和可视化各种代码质量指标.

- [phpmnd](https://github.com/povils/phpmnd) — 有助于检测幻数.

- [PHPQA](https://edgedesigncz.github.io/phpqa) — 用于运行 QA 工具（phploc、phpcpd、phpcs、pdepend、phpmd、phpmetrics）的工具.

- [phpqa - jakzal](https://github.com/jakzal/phpqa) — 一个容器中的许多 PHP 静态分析工具.

- [phpqa - jmolivas](https://github.com/jmolivas/phpqa) — PHPQA 多合一分析器 CLI 工具.

- [phpsa](https://github.com/ovr/phpsa) — PHP 的静态分析工具.

- [PHPStan](https://phpstan.org) — PHP 静态分析工具 - 无需运行即可发现代码中的错误！

- [Progpilot](https://github.com/designsecurity/progpilot) — 用于安全目的的静态分析工具.

- [Psalm](https://psalm.dev) — 用于查找 PHP 应用程序中的类型错误的静态分析工具.

- [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) — 可视化指标和源代码.

- [Symfony Insight](https://insight.symfony.com/) :copyright: — 检测安全风险、查找错误并为 PHP 项目提供可操作的指标.

- [Tuli](https://github.com/ircmaxell/Tuli) — 静态分析引擎.

- [twig-lint](https://github.com/asm89/twig-lint) — twig-lint 是一个用于 twig 文件的 lint 工具.

- [WAP](https://securityonline.info/owasp-wap-web-application-protection-project) — 用于检测和纠正 PHP（4.0 或更高版本）Web 应用程序中输入验证漏洞的工具，并通过结合静态分析和数据挖掘来预测误报.


<h2 id="plsql">PL/SQL</h2>


- [ZPA](https://felipezorzo.com.br/zpa/)  — Z PL/SQL Analyzer (ZPA) 是用于 PL/SQL 和 Oracle SQL 的可扩展代码分析器. 它可以与 SonarQube 集成.


<h2 id="perl">Perl</h2>


- [Perl::Analyzer](https://technix.github.io/Perl-Analyzer/) — Perl-Analyzer 是一组程序和模块，允许用户通过提供有关名称空间及其关系、依赖关系、继承和在包中实现、继承和重新定义的方法以及对方法的调用的信息来分析和可视化 Perl 代码库通过 SUPER 从父包中获取. 

- [Perl::Critic](https://metacpan.org/pod/Perl::Critic) — 批判 Perl 源代码以获得最佳实践.


<h2 id="python">Python</h2>


- [autopep8](https://pypi.org/project/autopep8/) — 自动格式化 Python 代码以符合 PEP 8 风格指南的工具.
它使用 pycodestyle 实用程序来确定代码的哪些部分需要格式化.

- [bandit](https://bandit.readthedocs.io/en/latest) — 在 Python 代码中查找常见安全问题的工具.

- [bellybutton](https://github.com/hchasestevens/bellybutton) — 支持自定义项目特定规则的 linting 引擎.

- [Black](https://black.readthedocs.io/en/stable) — 不妥协的 Python 代码格式化程序.

- [Bowler](https://pybowler.io/)  — 现代 Python 的安全代码重构.  Bowler 是一种重构工具，用于在语法树级别操作 Python. 它支持安全、大规模的代码修改，同时保证生成的代码能够编译和运行. 它在 Python 中提供了简单的命令行界面和流畅的 API，用于在代码中生成复杂的代码修改.

- [ciocheck](https://github.com/ContinuumIO/ciocheck)  — Linter、格式化程序和测试套件助手. 作为 linter，它是 `pep8`、`pydocstyle`、`flake8` 和 `pylint` 的包装器.

- [cohesion](https://github.com/mschwager/cohesion) — 一种用于测量 Python 类内聚性的工具.

- [Dlint](https://github.com/dlint-py/dlint) — 确保 Python 代码安全的工具.

- [fixit](https://pypi.org/project/fixit) — 用于创建 lint 规则和相应的源代码自动修复的框架.

- [flake8](https://github.com/PyCQA/flake8) — `pyflakes`、`pycodestyle` 和 `mccabe` 的​​包装器.

- [InspectorTiger](https://github.com/thg-consulting/it)  — IT，Inspector Tiger，是一个现代的 Python 代码审查工具/框架. 它带有一堆预定义的处理程序，可以警告您有关改进和可能的错误. 除了这些处理程序之外，您还可以编写自己的或使用社区的.

- [jedi](https://jedi.readthedocs.io/en/latest) — Python 的自动完成/静态分析库.

- [linty fresh](https://github.com/lyft/linty_fresh) — 解析 lint 错误并将它们作为拉取请求的评论报告给 Github.

- [mccabe](https://pypi.org/project/mccabe) — 检查 McCabe 复杂性.

- [multilint](https://github.com/adamchainz/multilint) — `flake8`、`isort` 和 `modernize` 的包装器.

- [mypy](http://www.mypy-lang.org) — 一种静态类型检查器，旨在结合鸭子类型和静态类型的优点，经常与 [MonkeyType](https://github.com/Instagram/MonkeyType).

- [prospector](https://github.com/PyCQA/prospector) — `pylint`、`pep8`、`mccabe` 等的包装器.

- [py-find-injection](https://github.com/uber/py-find-injection) :warning: — 查找 Python 代码中的 SQL 注入漏洞.

- [pyanalyze](https://pyanalyze.readthedocs.io/en/latest/)  — 一种以编程方式检测 Python 代码中常见错误的工具，例如对未定义变量的引用和类型错误. 它可以扩展以添加额外的规则并执行特定于特定功能的检查.

- [PyCodeQual](https://pycodequ.al)  :copyright: — PyCodeQual 让您深入了解复杂性和错误风险. 它将自动审查添加到您的拉取请求中.

- [pycodestyle](https://pycodestyle.pycqa.org/en/latest) —（以前称为 `pep8`）根据 PEP 8 中的一些样式约定检查 Python 代码.

- [pydocstyle](http://www.pydocstyle.org) — 检查是否符合 Python 文档字符串约定.

- [pyflakes](https://pypi.org/project/pyflakes) — 检查 Python 源文件是否有错误.

- [pylint](http://pylint.pycqa.org/en/latest)  — 查找编程错误，帮助执行编码标准并嗅探某些代码的味道. 它还包括“pyreverse”（一个 UML 图生成器）和“symilar”（一个相似性检查器）.

- [pyre-check](https://pyre-check.org) — 适用于大型 Python 代码库的快速、可扩展的类型检查器.

- [pyright](https://github.com/Microsoft/pyright) — Python 的静态类型检查器，旨在解决现有工具（如 mypy）中的缺陷.

- [pyroma](https://github.com/regebro/pyroma) — 评估 Python 项目与 Python 打包生态系统最佳实践的一致性，并列出可以改进的问题.

- [Pysa](https://pyre-check.org/docs/pysa-basics.html) — 基于 Facebook 的 pyre-check 的工具，用于识别通过污点分析识别的 Python 代码中的潜在安全问题.

- [PyT - Python Taint](https://github.com/python-security/pyt) :warning: — 一种静态分析工具，用于检测 Python Web 应用程序中的安全漏洞.

- [pytype](https://google.github.io/pytype) — Python 代码的静态类型分析器.

- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode)  :warning: — 自动代码审查和修复. 它可以帮助您跟踪软件项目中的问题和指标，并且可以轻松扩展以支持新型分析.

- [radon](https://radon.readthedocs.io/en/latest) — 一种从源代码计算各种指标的 Python 工具.

- [refurb](https://github.com/dosisod/refurb)  — 一种用于翻新和现代化 Python 代码库的工具.  Refurb 深受 clippy 的启发，clippy 是 Rust 的内置 linter.

- [ruff](https://github.com/charliermarsh/ruff)  — 快速 Python linter，用 Rust 编写. 比现有的 linters 快 10-100 倍. 与 Python 3.10 兼容. 支持文件观察器.

- [unimport](https://unimport.hakancelik.dev) — 用于查找和删除未使用的导入语句的 linter、格式化程序.

- [vulture](https://github.com/jendrikseipp/vulture) — 在 Python 代码中查找未使用的类、函数和变量.

- [wemake-python-styleguide](https://wemake-python-styleguide.rtfd.io/) — 有史以来最严格、最自以为是的 Python linter.

- [wily](https://github.com/tonybaloney/wily) — 用于存档、探索和绘制 Python 源代码复杂性的命令行工具.

- [xenon](https://xenon.readthedocs.io) — 使用监控代码复杂性 [`radon`](https://github.com/rubik/radon).

- [yapf](https://github.com/google/yapf) — Google 创建的 Python 文件格式化程序
YAPF follows a distinctive methodology, originating from the 'clang-format' tool created by Daniel Jasper. Essentially, the program reframes the code to the most suitable formatting that abides by the style guide, even if the original code already follows the style guide. This concept is similar to the Go programming language's 'gofmt' tool, which aims to put an end to debates about formatting by having the entire codebase of a project pass through YAPF whenever changes are made, thereby maintaining a consistent style throughout the project and eliminating the need to argue about style in every code review.


<h2 id="r">R</h2>


- [cyclocomp](https://github.com/MangoTheCat/cyclocomp) — 量化 R 函数/表达式的圈复杂度.

- [goodpractice](http://mangothecat.github.io/goodpractice) — 分析 R 包的源代码并提供最佳实践建议.

- [lintr](https://github.com/jimhester/lintr) — R 的静态代码分析.

- [styler](https://styler.r-lib.org) — R 源代码文件的格式化和 R 代码的漂亮打印.


<h2 id="ruby">红宝石</h2>


- [brakeman](https://brakemanscanner.org) — 用于 Ruby on Rails 应用程序的静态分析安全漏洞扫描器.

- [bundler-audit](https://github.com/rubysec/bundler-audit) — 审计 Gemfile.lock 中报告的具有安全漏洞的 gem [Ruby Advisory Database](https://github.com/rubysec/ruby-advisory-db).

- [cane](https://github.com/square/cane) — 代码质量阈值检查作为构建的一部分.

- [Churn](https://github.com/danmayer/churn)  — 为给定签入的项目提供流失文件、类和方法的项目. 随着时间的推移，该工具会将改动的历史记录加起来，以给出文件、类或方法在项目生命周期中发生更改的次数.

- [dawnscanner](https://github.com/thesp0nge/dawnscanner)  — 用于 ruby​​ 编写的 Web 应用程序的静态分析安全扫描器. 它支持 Sinatra、Padrino 和 Ruby on Rails 框架.

- [ERB Lint](https://github.com/Shopify/erb-lint) — 整理你的 ERB 或 HTML 文件

- [Fasterer](https://github.com/DamirSvrtan/fasterer) — 常见的 Ruby 习语检查器.

- [flay](https://ruby.sadi.st/Flay.html) — Flay 分析代码的结构相似性.

- [flog](https://ruby.sadi.st/Flog.html)  — Flog 在一份易于阅读的痛苦报告中报告了最受折磨的代码. 分数越高，代码越痛苦.

- [Fukuzatsu](https://github.com/CoralineAda/fukuzatsu)  — 一种用于测量 Ruby 类文件中代码复杂性的工具. 它的分析基于圈复杂度算法生成分数，没有添加“意见”.

- [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)  — HTML 的规范化器/美化器，也理解嵌入式 Ruby. 整理 Rails 模板的理想选择.

- [laser](https://github.com/michaeledgar/laser) :warning: — Ruby 代码的静态分析和样式 linter.

- [MetricFu](https://github.com/metricfu/metric_fu) — MetricFu 是一组工具，用于提供报告，显示您的代码的哪些部分可能需要额外工作.

- [pelusa](https://github.com/codegram/pelusa) — 用于改进 OO Ruby 代码的静态分析 Lint 类型工具.

- [quality](https://github.com/apiology/quality) — 使用社区工具对您的代码进行质量检查，并确保您的代码不会随着时间的推移而变得更糟.

- [Querly](https://github.com/soutaro/querly) — Ruby 基于模式的检查工具.

- [Railroader](https://railroader.org) — 用于 Ruby on Rails 应用程序的开源静态分析安全漏洞扫描器.

- [rails_best_practices](https://rails-bestpractices.com) — Rails 项目的代码度量工具

- [reek](https://github.com/troessner/reek) — Ruby 的代码气味检测器.

- [Roodi](https://github.com/roodi/roodi)  — Roodi 代表 Ruby Object Oriented Design Inferometer. 它会解析您的 Ruby 代码，并根据已配置的检查向您发出有关设计问题的警告.

- [RuboCop](https://docs.rubocop.org/rubocop) — 基于社区 Ruby 风格指南的 Ruby 静态代码分析器.

- [Rubrowser](https://github.com/blazeeboy/rubrowser) — Ruby 类交互式依赖图生成器.

- [ruby-lint](http://code.yorickpeterse.com/ruby-lint/latest) :warning: — Ruby 的静态代码分析.

- [rubycritic](https://github.com/whitesmith/rubycritic) — 一位 Ruby 代码质量报告者.

- [rufo](https://github.com/ruby-formatter/rufo) — 一个自以为是的 ruby​​ 格式化程序，旨在通过命令行用作文本编辑器插件，以在保存或按需时自动格式化文件.

- [Saikuro](https://metricfu.github.io/Saikuro) — Ruby 圈复杂度分析器.

- [SandiMeter](https://rubygems.org/gems/sandi_meter) :warning: — 用于检查 Sandi Metz 规则的 Ruby 代码的静态分析工具.

- [Sorbet](https://sorbet.org) — 为 Ruby 设计的快速、强大的类型检查器.

- [Standard Ruby](https://github.com/testdouble/standard) — Ruby 风格指南，带有 linter 和自动代码修复器

- [Steep](https://github.com/soutaro/steep) — Ruby 的渐进式打字.


<h2 id="rust">锈</h2>


- [C2Rust](https://c2rust.com)  — C2Rust 帮助您将符合 C99 的代码迁移到 Rust. 翻译器（或转译器）生成不安全的 Rust 代码，该代码与输入的 C 代码非常相似.

- [cargo udeps](https://github.com/est31/cargo-udeps)  — 在 Cargo.toml 中查找未使用的依赖项. 它要么打印出列出包装箱的“未使用的包装箱”行，要么打印出一行说明没有未使用的包装箱.

- [cargo-audit](https://rustsec.org) — 审计 Cargo.lock 是否有安全漏洞报告给 [RustSec Advisory Database](https://github.com/RustSec/advisory-db/).

- [cargo-bloat](https://github.com/RazrFalcon/cargo-bloat)  — 找出什么占用了可执行文件中的大部分空间. 支持 ELF（Linux、BSD）、Mach-O（macOS）和 PE（Windows）二进制文件.

- [cargo-breaking](https://github.com/iomentum/cargo-breaking) — cargo-breaking 比较两个不同分支之间 crate 的公共 API，显示更改的内容，并根据 semver 建议下一个版本.

- [cargo-deny](https://embarkstudios.github.io/cargo-deny)  — 一个 cargo 插件，用于检查您的依赖项. 它也可以用作命令行、Rust crate 或 CI 的 Github 操作. 它会检查有效的许可证信息、重复的包装箱、安全漏洞等.

- [cargo-expand](https://github.com/dtolnay/cargo-expand) — Cargo subcommand to show result of macro expansion  and #[derive] expansion applied to the current crate.  This is a wrapper around a more verbose compiler command.

- [cargo-inspect](https://github.com/mre/cargo-inspect) — 检查没有语法糖的 Rust 代码，看看编译器在幕后做了什么.

- [cargo-show-asm](https://github.com/pacak/cargo-show-asm) — cargo 子命令显示为 Rust 代码生成的程序集、LLVM-IR 和 MIR

- [cargo-spellcheck](https://github.com/drahnr/cargo-spellcheck) — 使用 hunspell (ready) 和 languagetool (preview) 检查所有文件的拼写和语法错误

- [cargo-unused-features](https://github.com/TimonPost/cargo-unused-features)  — 查找潜在未使用的已启用功能标志并修剪它们. 您可以从 json 生成简单的 HTML 报告，以便更轻松地检查结果.
它删除依赖项的功能，然后编译项目以查看它是否仍然可以编译. 如果是这样，则可能会删除功能标志，但它可能是误报.

- [clippy](https://rust-lang.github.io/rust-clippy) — 用于捕获常见错误并改进 Rust 代码的代码检查器.

- [dylint](https://www.trailofbits.com/post/write-rust-lints-without-forking-clippy)  — 从动态库运行 Rust lints 的工具.  Dylint 使开发人员可以轻松维护自己的个人 lint 集合.

- [electrolysis](http://kha.github.io/electrolysis) — 一种通过将 Rust 程序转换为精益定理证明器中的定义来正式验证 Rust 程序的工具.

- [herbie](https://github.com/mcarton/rust-herbie-lint) — 在使用数值不稳定的浮点表达式时向您的板条箱添加警告或错误.

- [linter-rust](https://github.com/AtomLinter/linter-rust) — 使用 rustc 和 cargo 在 Atom 中检查你的 Rust 文件.

- [MIRAI](https://github.com/facebookexperimental/MIRAI) — 以及在 Rust 的中级中间语言上运行的抽象解释器，并根据污点分析提供警告.

- [prae](https://github.com/teenjuna/prae) — 提供一个方便的宏，允许您生成类型包装器，承诺始终支持您指定的任意不变量. 

- [Prusti](https://www.pm.inf.ethz.ch/research/prusti.html)  — 基于 Viper 验证基础设施的 Rust 静态验证器. 默认情况下，Prusti 通过证明诸如 unreachable!() 和 panic!() 之类的语句是不可访问的来验证是否存在恐慌.

- [Rudra](https://github.com/sslab-gatech/Rudra)  — Rust 内存安全和未定义行为检测. 它能够分析单个 Rust 包以及 crates.io 上的所有包.

- [Rust Language Server](https://github.com/rust-lang-nursery/rls) — 支持“转到定义”、符号搜索、重新格式化和代码完成等功能，并支持重命名和重构.

- [rust-analyzer](https://rust-analyzer.github.io) — 支持“转到定义”、类型推断、符号搜索、重新格式化和代码完成等功能，并支持重命名和重构.

- [rust-audit](https://github.com/Shnatsel/rust-audit)  — 审计 Rust 二进制文件是否存在已知错误或安全漏洞. 这是通过将有关依赖树 (Cargo.lock) 的数据以 JSON 格式嵌入到已编译可执行文件的专用链接器部分中来实现的.

- [rustfix](https://github.com/rust-lang/rustfix) — 阅读并应用 rustc 提出的建议（以及第三方 lints，如 clippy 提供的）.

- [rustfmt](https://github.com/rust-lang/rustfmt) — 根据样式指南格式化 Rust 代码的工具.

- [RustViz](https://github.com/rustviz/rustviz)  — RustViz 是一个从简单的 Rust 程序生成可视化的工具，以帮助用户更好地理解 Rust 生命周期和借用机制. 它生成带有图形指示器的 SVG 文件，这些指示器与 mdbook 集成以呈现 Rust 程序中数据流的可视化.

- [warnalyzer](https://github.com/est31/warnalyzer) — 显示多箱 Rust 项目中未使用的代码


<h2 id="sql">数据库</h2>


- [dbcritic](https://github.com/channable/dbcritic) — dbcritic 发现数据库模式中的问题，例如表中缺少主键约束.

- [sqlcheck](https://github.com/jarulraj/sqlcheck) — 自动识别 SQL 查询中的反模式.

- [SQLFluff](https://www.sqlfluff.com/) — 多方言 SQL linter 和格式化程序.

- [sqlint](https://github.com/purcell/sqlint) — 简单的 SQL linter.

- [squawk](https://squawkhq.com)  — Linter for PostgreSQL，专注于迁移. 防止由数据库迁移引起的意外停机，并鼓励围绕 Postgres 模式和 SQL 的最佳实践.

- [tsqllint](https://github.com/tsqllint/tsqllint) — T-SQL 特定的 linter.

- [TSqlRules](https://github.com/ashleyglee/TSqlRules) — SQL Server 的 TSQL 静态代码分析规则.

- [Visual Expert](https://www.visual-expert.com) :copyright: — PowerBuilder、Oracle 和 SQL Server 的代码分析探索、分析和记录代码 


<h2 id="scala">斯卡拉</h2>


- [linter](https://github.com/HairyFotr/linter) — Linter 是一个 Scala 静态分析编译器插件，它为各种可能的错误、低效和样式问题添加了编译时检查.

- [Scalastyle](http://www.scalastyle.org) — Scalastyle 检查您的 Scala 代码并指出它的潜在问题.

- [scapegoat](https://github.com/sksamuel/scapegoat) — 用于静态代码分析的 Scala 编译器插件.

- [WartRemover](https://www.wartremover.org) — 灵活的 Scala 代码检查工具.


<h2 id="shell">壳</h2>


- [bashate](https://github.com/openstack/bashate)  — bash 程序的代码风格实施. 输出格式旨在遵循 pycodestyle (pep8) 默认输出格式.

- [i-Code CNES for Shell](https://github.com/lequal/i-CodeCNES) — 用于 Shell 和 Fortran（77 和 90）的开源静态代码分析工具.

- [kmdr](https://github.com/ediardo/kmdr-cli)  — 用于从终端学习命令的 CLI 工具.  kmdr 提供了命令分解，并解释了每个属性.

- [sh](https://pkg.go.dev/mvdan.cc/sh/v3)  — 支持 bash 的 shell 解析器、格式化器和解释器； 包括 shfmt

- [shellcheck](https://www.shellcheck.net) — ShellCheck，一种静态分析工具，可为 bash/sh shell 脚本提供警告和建议.

- [shellharden](https://github.com/anordal/shellharden) — 一个语法高亮器和一个半自动重写脚本以符合 ShellCheck 一致性的工具，主要侧重于引用.


<h2 id="swift">迅速</h2>


- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) — 用于重新格式化 Swift 代码的库和命令行格式化工具.

- [SwiftLint](https://realm.github.io/SwiftLint) — A tool to enforce Swift style and conventions.

- [Tailor](https://sleekbyte.github.io/tailor) :warning: — 以 Apple 的 Swift 编程语言编写的源代码的静态分析和 lint 工具.


<h2 id="tcl">TCL</h2>


- [Frink](http://catless.ncl.ac.uk/Programs/Frink) — 一个 Tcl 格式化和静态检查程序（可以美化程序、最小化、混淆或只是完整性检查）.

- [Nagelfar](https://sourceforge.net/projects/nagelfar) — Tcl 的静态语法检查器.

- [tclchecker](https://github.com/ActiveState/tdk/blob/master/docs/3.0/TDK_3.0_Checker.txt) — A static syntax analysis module (as part of [TDK](https://github.com/ActiveState/tdk)).


<h2 id="typescript">打字稿</h2>


- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) — Angular 项目的 Linter

- [Codelyzer](http://codelyzer.com) :warning: — 一组用于 Angular 2 TypeScript 项目静态代码分析的 tslint 规则.

- [stc](https://stc.dudy.dev) — 用 Rust 编写的快速 TypeScript 类型检查器

- [tslint](https://palantir.github.io/tslint/) :warning: — TSLint 已于 2019 年弃用.请参阅此问题了解更多详细信息：typescript-eslint 现在是检查 TypeScript 的最佳选择.
 TSLint 是一种可扩展的静态分析工具，用于检查 TypeScript 代码的可读性、可维护性和功能错误. 它在现代编辑器和构建系统中得到广泛支持，并且可以使用您自己的 lint 规则、配置和格式化程序进行自定义.

- [tslint-clean-code](https://www.npmjs.com/package/tslint-clean-code) — 一组受 Clean Code 手册启发的 TSLint 规则.

- [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib) :warning: — Microsoft 维护的一组 tslint 规则，用于对 TypeScript 项目进行静态代码分析.

- [TypeScript Call Graph](https://github.com/whyboris/TypeScript-Call-Graph) — CLI 从您的 TypeScript 文件生成函数和调用的交互式图形

- [TypeScript ESLint](https://github.com/typescript-eslint/typescript-eslint) — eslint 的 TypeScript 语言扩展.

- [zod](https://zod.dev)  — 使用静态类型推断的 TypeScript 优先模式验证. 目标是消除重复的类型声明. 使用 Zod，您只需声明一个验证器，Zod 就会自动推断出静态 TypeScript 类型. 将简单的类型组合成复杂的数据结构很容易.


<h2 id="verilog">Verilog/SystemVerilog</h2>


- [Icarus Verilog](https://github.com/steveicarus/iverilog) — 一种 Verilog 仿真和综合工具，通过将 IEEE-1364 Verilog 中编写的源代码编译成某种目标格式来运行

- [svls](https://github.com/dalance/svls) — Verilog 和 SystemVerilog 的语言服务器协议实现，包括 lint 功能.

- [verible-linter-action](https://github.com/chipsalliance/verible-linter-action) — 在 Verible 的帮助下，github 操作中的自动 SystemVerilog linting 用于自动检查 Verilog 和 SystemVerilog 源文件，并自动注释 Pull Requests 中的错误代码行.

- [Verilator](https://www.veripool.org/verilator)  — 将 Verilog 转换为 C++ 或 SystemC 中的周期精确行为模型的工具. 执行 lint 代码质量检查.

- [vscode-verilog-hdl-support](https://github.com/mshr-h/vscode-verilog-hdl-support)  — Verilog HDL/SystemVerilog/Bluespec SystemVerilog 支持 VS 代码. 提供来自 Icarus Verilog、Vivado Logical Simulation、Modelsim 和 Verilator 的语法突出显示和 Linting 支持


<h2 id="vim-script">Vim 脚本</h2>


- [vint](https://github.com/Kuniwak/vint) — 由 Python 实现的快速且高度可扩展的 Vim 脚本语言 Lint.


## Multiple languages


- [ale](https://github.com/w0rp/ale) — Vim 和 NeoVim 的异步 Lint 引擎，支持多种语言.

- [Android Studio](https://developer.android.com/studio) — 基于 IntelliJ IDEA，并捆绑了适用于 Android 的工具，包括 Android Lint.

- [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) :copyright: — Static analysis for C/C++/C#, PHP and Java.

- [Application Inspector](https://www.ptsecurity.com/ww-en/products/ai) :copyright: — 商业静态代码分析，它生成漏洞以验证漏洞.

- [ApplicationInspector](https://github.com/microsoft/ApplicationInspector) — 创建超过 400 种规则模式的报告以进行特征检测（例如，在应用程序中使用密码学或版本控制）.

- [APPscreener](https://solarappscreener.com) :copyright: — Static code analysis for binary and source code - Java/Scala, PHP, Javascript, C#, PL/SQL, Python, T-SQL, C/C++, ObjectiveC/Swift, Visual Basic 6.0, Ruby, Delphi, ABAP, HTML5 and Solidity.

- [ArchUnit](https://www.archunit.org) — 对您的 Java 或 Kotlin 架构进行单元测试.

- [Atom-Beautify](https://atom.io/packages/atom-beautify) — Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom editor.

- [autocorrect](https://huacnlee.github.io/autocorrect) — 一种 linter 和格式化程序，可帮助您改进 CJK（中文、日语、韩语）之间的文案写​​作、更正空格、单词、标点符号.

- [Axivion Bauhaus Suite](https://www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: — Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95.

- [Better Code Hub](https://bettercodehub.com) :copyright: — Better Code Hub 根据软件质量权威机构 Software Improvement Group 制定的 10 项工程指南检查您的 GitHub 代码库.

- [callGraph](https://github.com/koknat/callGraph) — 静态生成调用图图像并将其显示在屏幕上.

- [CAST Highlight](https://www.castsoftware.com/products/highlight) :copyright: — 商业静态代码分析，在本地运行，但将结果上传到其云端进行展示.

- [Checkmarx CxSAST](https://www.checkmarx.com/products/static-application-security-testing) :copyright: — 不需要预编译的商业静态代码分析.

- [ClassGraph](https://github.com/classgraph/classgraph) — 用于查询或可视化类元数据或类相关性的类路径和模块路径扫描器.

- [Clayton](https://www.getclayton.com/)  :copyright: — Salesforce 的人工智能代码审查. 保护您的开发，实施最佳实践并实时控制您的技术债务.

- [coala](https://coala.io) — 用于创建代码分析的语言独立框架 - 支持 [over 60 languages](https://coala.io/languages) 默认情况下.

- [Cobra](https://spinroot.com/cobra) :copyright: — NASA 喷气推进实验室的结构源代码分析器.

- [Codacy](https://www.codacy.com) :copyright: — 代码分析以更快地发布更好的代码.

- [Code Intelligence](https://www.code-intelligence.com) :copyright: — 与 CI/CD 无关的 DevSecOps 平台，结合了行业领先的模糊测试引擎，用于查找错误和可视化代码覆盖率

- [Codeac](https://www.codeac.io/?ref=awesome-static-analysis)  :copyright: — 自动代码审查工具集成了 GitHub、Bitbucket 和 GitLab（甚至是自托管）. 适用于 JavaScript、TypeScript、Python、Ruby、Go、PHP、Java、Docker 等.  （开源免费）

- [codeburner](http://groupon.github.io/codeburner) — 提供一个统一的界面来对它发现的问题进行分类和处理.

- [codechecker](https://codechecker.readthedocs.io/en/latest) — 带有 Web GUI 的 Clang 静态分析器的缺陷数据库和查看器扩展.

- [CodeFactor](https://codefactor.io) :copyright: — GitHub 或 BitBucket 上 repos 的自动代码分析.

- [CodeFlow](https://www.getcodeflow.com)  :copyright: — 处理技术深度的自动代码分析工具. 与 Bitbucket 和 Gitlab 集成.  （开源项目免费）

- [CodeIt.Right](https://submain.com/products/codeit.right.aspx) :copyright: — CodeIt.Right™ 提供了一种快速、自动化的方法来确保您的源代码符合（您的）预定义的设计和样式指南以及最佳编码实践.

- [CodePatrol](https://cyber-security.claranet.fr/en/codepatrol) :copyright: — 由安全驱动的自动化 SAST 代码审查，支持 15 种以上的语言并包括安全培训.

- [codeql](https://github.com/github/codeql) — 深度代码分析——支持 VSCode 插件的多种语言的语义查询和数据流.

- [CodeQue](https://codeque.co)  — 用于结构匹配 JavaScript 和 TypeScript 代码的生态系统. 提供了解代码结构的搜索工具. 作为 CLI 工具和 Visual Studio Code 扩展可用. 它有助于更​​快、更准确地搜索代码，使您的工作流程更有效. 很快它将提供 ESLint 插件来在几分钟内创建您自己的规则，以帮助确保代码库质量.

- [Coderrect](https://coderrect.com/)  :copyright: — 用于多线程软件的高级静态分析器. 支持 OpenMP、Pthreads、std::thread 和 GPU/CUDA.

- [CodeRush](https://www.devexpress.com/products/coderush) :copyright: — 在 Visual Studio 2015 及更高版本中使用 Roslyn 引擎的代码创建、调试、导航、重构、分析和可视化工具.

- [CodeScan](https://www.codescan.io/)  :copyright: — Salesforce 开发人员的代码质量和安全性.  CodeScan 的代码分析解决方案专为 Salesforce 平台打造，可让您全面了解代码的健康状况.

- [CodeScene](https://codescene.com)  :copyright: — CodeScene 是一种高质量的软件可视化工具. 确定技术债务的优先级、检测交付风险并衡量组织方面. 完全自动化.

- [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) :copyright: — Advanced, whole program, deep path, static analysis of C, C++, Java and C# with easy-to-understand explanations and code and path visualization.

- [Codiga](https://www.codiga.io) :copyright: — 支持 12 种以上语言的自动代码审查和技术债务管理平台.

- [Corrode](https://github.com/jameysharp/corrode)  :warning: — 从 C 到 Rust 的半自动翻译. 可以通过显示 Rust 编译器警告和错误来揭示原始实现中的错误. 被 C2Rust 取代.

- [Coverity](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: — Synopsys Coverity supports 20 languages and over 70 frameworks including Ruby on rails, Scala, PHP, Python, JavaScript, TypeScript, Java, Fortran, C, C++, C#, VB.NET.

- [cpp-linter-action](https://cpp-linter.github.io/cpp-linter-action/) — 用于检查 C/C++ 代码的 Github 操作，集成了 clang-tidy 和 clang-format 以收集以线程评论和/或注释的形式提供的反馈.

- [cqc](https://github.com/xcatliu/cqc) — 检查 js、jsx、vue、css、less、scss、sass 和 styl 文件的代码质量.

- [DeepCode](https://www.deepcode.ai) :copyright: — DeepCode 被 Snyk 收购，现在是 Snyk Code.

- [DeepSource](https://deepsource.io)  :copyright: — 深入的静态分析，以发现错误风险、安全性、反模式、性能、文档和风格等垂直领域的问题. 与 GitHub、GitLab 和 Bitbucket 的原生集成. 误报率低于 5%.

- [Depends](https://github.com/multilang-depends/depends) — 分析了Java、C/C++、Ruby 代码元素的综合依赖性.

- [DevSkim](https://github.com/microsoft/devskim) — Regex-based static analysis tool for Visual Studio, VS Code, and Sublime Text - C/C++, C#, PHP, ASP, Python, Ruby, Java, and others.

- [Embold](https://embold.io) :copyright: — Intelligent software analytics platform that identifies design issues, code issues, duplication and metrics. Supports Java, C, C++, C#, JavaScript, TypeScript, Python, Go, Kotlin and more.

- [emerge](https://github.com/glato/emerge)  — Emerge 是一个源代码和依赖项可视化工具，可用于收集有关软件项目的源代码结构、指标、依赖项和复杂性的见解. 扫描项目的源代码后，它会为您提供一个交互式 Web 界面，以使用图形结构探索和分析您的项目.

- [ESLint](https://github.com/eslint/eslint) — 一个可扩展的 JS linter，遵循 ECMAScript 标准.

- [Find Security Bugs](https://find-sec-bugs.github.io)  — 用于 Java Web 应用程序和 Android 应用程序安全审计的 SpotBugs 插件.  （也适用于 Kotlin、Groovy 和 Scala 项目）

- [Fortify](https://software.microfocus.com/en-us/products/static-code-analysis-sast/overview) :copyright: — A commercial static analysis platform that supports the scanning of C/C++, C#, VB.NET, VB6, ABAP/BSP, ActionScript, Apex, ASP.NET, Classic ASP, VB Script, Cobol, ColdFusion, HTML, Java, JS, JSP, MXML/Flex, Objective-C, PHP, PL/SQL, T-SQL, Python (2.6, 2.7), Ruby (1.9.3), Swift, Scala, VB, and XML.

- [Goodcheck](https://sider.github.io/goodcheck) — 基于正则表达式的可定制 linter.

- [goone](https://github.com/masibw/goone) — 在 go 代码中查找 N+1 个查询（for 循环中的 SQL 调用）

- [graudit](http://www.justanotherhacker.com) — Grep 粗略审计——源代码审计工具.

- [HCL AppScan Source](https://www.hcltechsw.com/products/appscan) :copyright: — 商业静态代码分析.

- [Hopper](https://github.com/cuplv/hopper) :warning: — 用 scala 编写的静态分析工具，适用于在 JVM 上运行的语言.

- [Hound CI](https://houndci.com)  — 对 GitHub 拉取请求中的样式违规的评论. 支持 Coffeescript、Go、HAML、JavaScript、Ruby、SCSS 和 Swift.

- [imhotep](https://github.com/justinabrahms/imhotep) — 评论进入您的存储库的提交并检查语法错误和一般 lint 警告.

- [include-gardener](https://github.com/feddischson/include_gardener) — A multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.

- [Infer](https://fbinfer.com) — Java、C 和 Objective-C 的静态分析器

- [Kiuwan](https://www.kiuwan.com/code-security-sast) :copyright: — Identify and remediate cyber threats in a blazingly fast, collaborative environment, with seamless integration in your SDLC. Python, C\C++, Java, C#, PHP and more.

- [Klocwork](https://www.perforce.com/products/klocwork) :copyright: — Quality and Security Static analysis for C/C++, Java and C#.

- [LGTM](https://lgtm.com/)  :copyright: — 使用 CodeQL 查询源代码查找安全漏洞、变体和关键代码质量问题. 自动 PR 代码审查； 免费开源. 以前塞姆勒. 它支持托管在 Bitbucket Cloud、GitHub.com、GitLab.com 上的公共 Git 存储库.

- [lizard](https://github.com/terryyin/lizard)  — Lizard 是一种可扩展的循环复杂度分析器，适用于许多编程语言，包括 C/C++（不需要所有头文件或 Java 导入）. 它还进行复制粘贴检测（代码克隆检测/代码重复检测）和许多其他形式的静态代码分析. 计算没有注释的代码行数、CCN（循环复杂度数）、函数的标记数、函数的参数数.

- [Mega-Linter](https://nvuillam.github.io/mega-linter/) — 由于其 70 多个嵌入式 Linter，Mega-Linter 可以处理任何类型的项目，
 其高级报告，可在任何 CI 系统或本地运行，
 通过辅助安装和配置，能够应用格式和修复

- [oclint](http://oclint.org) — 一种静态源代码分析工具，用于提高 C、C++ 和 Objective-C 的质量并减少缺陷.

- [ocular](https://www.shiftleft.io/ocular/)  :copyright: — 使代码审计员和安全团队能够以交互方式调查他们独特的代码库，以发现传统 SAST 无法发现的业务逻辑缺陷和技术漏洞. 这是通过使分析师能够编写他们自己的自定义查询来完成的. 可以找到硬编码的秘密、身份验证问题以及 Rootkit 和后门等恶意代码.

- [Offensive 360](https://offensive360.com/) :copyright: — 商业静态代码分析系统不需要构建源代码或预编译.

- [parasoft](https://www.parasoft.com/)  :copyright: — 用于单元、API 和 Web UI 测试的自动化软件测试解决方案. 符合 MISRA、OWASP 等标准.

- [pfff](https://github.com/facebookarchive/pfff/wiki/Main) :warning: — Facebook 用于多种语言的代码分析、可视化或保留样式的源代码转换的工具.

- [PMD](https://pmd.github.io) — Java、Salesforce Apex、Javascript、PLSQL、XML、XSL 等的源代码分析器.

- [pre-commit](https://pre-commit.com) — 用于管理和维护多语言预提交挂钩的框架.

- [Prettier](https://prettier.io) — 自以为是的代码格式化程序.

- [Pronto](https://github.com/prontolabs/pronto)  — 对您的更改进行快速自动代码审查. 支持 40 多种不同语言的运行器，包括 Clang、Elixir、JavaScript、PHP、Ruby 等.

- [PT.PM](https://github.com/PositiveTechnologies/PT.PM) :warning: — An engine for searching patterns in the source code, based on Unified AST or UST. At present time C#, Java, PHP, PL/SQL, T-SQL, and JavaScript are supported. Patterns can be described within the code or using a DSL.

- [Putout](https://github.com/coderaiser/putout) — 可插入和可配置的代码转换器，内置 eslint，支持 js、jsx typescript、flow、markdown、yaml 和 json 的 babel 插件.

- [PVS-Studio](https://pvs-studio.com) ：版权：-一个（[conditionally free](https://pvs-studio.com/en/order/open-source-license) for FOSS and individual developers) static analysis of C, C++, C# and Java code. For advertising purposes [you can propose a large FOSS project for analysis by PVS employees](https://github.com/viva64/pvs-studio-check-list) . 支持 CWE 映射、OWASP ASVS、MISRA、AUTOSAR 和 SEI CERT 编码标准.

- [pylama](https://klen.github.io/pylama/)  — Python 和 JavaScript 的代码审计工具. 包装 pycodestyle、pydocstyle、PyFlakes、Mccabe、Pylint 等

- [Refactoring Essentials](https://marketplace.visualstudio.com/items?itemName=SharpDevelopTeam.RefactoringEssentialsforVisualStudio) — The free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers.

- [relint](https://github.com/codingjoe/relint) — 一个静态文件 linter，允许您使用正则表达式 (RegEx) 编写自定义规则.

- [ReSharper](https://www.jetbrains.com/resharper) :copyright: — Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies.

- [RIPS](https://www.ripstech.com) :copyright: — PHP 脚本漏洞的静态源代码分析器.

- [Rome](https://rome.tools/) — Rome 是一个 linter、编译器、打包器和 [more](https://rome.tools/#development-status) 适用于 JavaScript、TypeScript、JSON、HTML、Markdown 和 CSS.

- [Rome Formatter](https://rome.tools/blog/2022/04/05/rome-formatter-release) — 用 Rust 编写的 JS/TS 的高性能和容错代码格式化程序

- [Roslyn Analyzers](https://github.com/dotnet/roslyn-analyzers) — FxCop 分析器的基于 Roslyn 的实现.

- [Roslyn Security Guard](https://security-code-scan.github.io) — 专注于识别潜在漏洞的项目，例如 SQL 注入、跨站点脚本 (XSS)、CSRF、密码学弱点、硬编码密码等等.

- [Scanmycode CE (Community Edition)](http://www.scanmycode.today) — Scanmycode - 代码扫描/SAST/Linting 使用许多工具/扫描器和一份报告

- [Scrutinizer](https://scrutinizer-ci.com) :copyright: — 可以与 GitHub 集成的专有代码质量检查器.

- [Security Code Scan](https://security-code-scan.github.io) — Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc. Integrates into Visual Studio 2015 and newer. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.

- [Semgrep](https://semgrep.dev)  — 一种快速、开源的静态分析工具，用于在编辑器、提交和 CI 时查找错误并强制执行代码标准. 它的规则看起来像您已经编写的代码； 没有抽象语法树或正则表达式摔跤. 支持 17 种以上的语言.

- [Semgrep Supply Chain](https://semgrep.dev/products/semgrep-supply-chain)  :copyright: — 快速查找并修复高优先级安全问题.  Semgrep Supply Chain 优先考虑可从您的代码中获取的 2% 的漏洞.

- [ShiftLeft](https://www.shiftleft.io)  :copyright: — 在您的代码库进入生产环境之前识别它们所特有的漏洞. 利用代码属性图 (CPG) 在单个图形图中同时运行其分析. 自动发现开发中的业务逻辑缺陷，如硬编码秘密和逻辑炸弹

- [ShiftLeft Scan](https://github.com/ShiftLeftSecurity/sast-scan)  — Scan 是一个免费的开源 DevSecOps 平台，用于检测源代码和依赖项中的安全问题. 它支持广泛的语言和 CI/CD 管道.

- [shipshape](https://github.com/google/shipshape) :warning: — 允许自定义分析器通过通用接口插入的静态程序分析平台.

- [Sider](https://sider.review)  :copyright: — 一种自动代码审查工具. 提高开发人员的生产力.

- [Sigrid](https://www.softwareimprovementgroup.com/solutions/sigrid-software-assurance-platform/) :copyright: — Sigrid 通过测量系统的代码质量帮助您改进软件，然后将结果与数千个行业系统的基准进行比较，为您提供可以改进的领域的具体建议.

- [Similarity Tester](https://dickgrune.com/Programs/similarity_tester/) — 一种查找文件之间或文件内部相似性的工具，以支持您遇到违反 DRY 原则的情况.

- [Snyk Code](https://snyk.io) :copyright: — Snyk Code finds security vulnerabilities based on AI. Its speed of analysis allow us to  analyse your code in real time and deliver results when you hit the save button in your IDE.  Supported languages are Java, JavaScript, Python, PHP, C#, Go and TypeScript. Integrations with  GitHub, BitBucket and Gitlab. It is free to try and part of the Snyk platform also covering SCA,  containers and IaC.

- [SonarCloud](https://sonarcloud.io)  :copyright: — 多语言基于云的静态代码分析. 历史、趋势、安全热点、拉取请求分析等. 免费开源.

- [SonarLint for Visual Studio](https://vs.sonarlint.org) — SonarLint 是 Visual Studio 2015 和 2017 的扩展，它向开发人员提供有关注入到 .NET 代码中的新错误和质量问题的即时反馈.

- [SonarQube](http://www.sonarqube.org) — SonarQube 是一个管理代码质量的开放平台.

- [Sonatype](https://www.sonatype.com) :copyright: — 报告常见依赖项中的已知漏洞并推荐更新包以尽量减少破坏性更改

- [Soto Platform](https://www.hello2morrow.com/products/sotograph)  :copyright: — 静态分析工具套件，由三个部分组成 Sotoarc（架构分析）、Sotograph（质量分析）和 Sotoreport（质量报告）. 帮助发现体系结构和实现之间的差异、接口违规（例如子系统私有部分的外部访问、检测所有类、文件、包和子系统，这些类、文件、包和子系统通过循环关系强耦合等等.Sotograph 产品系列在 Windows 和 Linux 上运行. 

- [SourceMeter](https://www.sourcemeter.com/) :copyright: — Static Code Analysis for C/C++, Java, C#, Python, and RPG III and RPG IV versions (including free-form).

- [sqlvet](https://github.com/houqp/sqlvet)  — 对 Go 代码库中的原始 SQL 查询执行静态分析，以发现潜在的运行时错误. 它检查 SQL 语法错误，识别可能导致 SQL 注入的不安全查询，确保列数与 INSERT 语句中的值数相匹配，并验证表名和列名.

- [Super-Linter](https://github.com/github/super-linter) — 组合多个 linter 以作为 GitHub 操作安装.

- [Svace](https://www.ispras.ru/en/technologies/svace/) :copyright: — Static code analysis tool for Java,C,C++,C#,Go.

- [Synopsys](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: — A commercial static analysis platform that allows for scanning of multiple languages (C/C++, Android, C#, Java, JS, PHP, Python, Node.JS, Ruby, Fortran, and Swift).

- [Teamscale](https://www.cqse.eu/en/teamscale/overview/)  :copyright: — 支持超过 25 种语言和直接 IDE 集成的静态和动态分析工具. 可根据要求免费托管开源项目. 提供免费的学术许可证.

- [TencentCodeAnalysis](https://tca.tencent.com/)  — 腾讯云代码分析（简称TCA，早期公司内部代号CodeDog）是一个综合性的代码分析和问题跟踪平台.  TCA 由三个组件组成，服务器、Web 和客户端. 集成了多项自主开发的工具，还支持动态集成各种编程语言的代码分析工具.

- [ThreatMapper](https://github.com/deepfence/ThreatMapper)  — 运行时容器、无服务器和主机的漏洞扫描程序和风险评估.  ThreatMapper 从依赖项和操作系统包生成运行时 BOM，匹配多个威胁源，扫描未受保护的秘密，并根据严重性和利用风险对问题进行评分.

- [todocheck](https://github.com/preslavmihaylov/todocheck) — 用于将带注释的 TODO 与问题跟踪器集成的 Linter

- [trivy](https://github.com/aquasecurity/trivy)  — 一个简单而全面的容器和其他工件的漏洞扫描器，适用于 CI.  Trivy 检测操作系统包（Alpine、RHEL、CentOS 等）和应用程序依赖项（Bundler、Composer、npm、yarn 等）的漏洞. 检查容器和文件系统.


- [trunk](https://trunk.io)  :copyright: — 现代存储库包含许多技术，每种技术都有自己的一套 linters.  Trunk 拥有 30 多个 linters 并且还在增加，可以非常简单地为您的所有存储库识别、安装、配置和运行正确的 linters、静态分析器和格式化程序.

- [TscanCode](https://github.com/Tencent/TscanCode) — A fast and accurate static analysis solution for C/C++, C#, Lua codes provided by Tencent. Using GPLv3 license.

- [Undebt](https://github.com/Yelp/undebt) — 独立于语言的工具，用于基于简单模式定义的大规模、自动、可编程的重构.

- [Understand](https://www.scitools.com) :copyright: — 代码可视化工具，为 Ada、VHDL 等提供代码分析、标准测试、指标、图形、依赖分析等.

- [Unibeautify](https://unibeautify.com)  — 带有 GitHub 应用程序的通用代码美化器. 支持 HTML、CSS、JavaScript、TypeScript、JSX、Vue、C++、Go、Objective-C、Java、Python、PHP、GraphQL、Markdown 等.

- [Upsource](https://www.jetbrains.com/upsource) :copyright: — 代码审查工具，具有针对 Java、PHP、JavaScript 和 Kotlin 的静态代码分析和代码感知导航.

- [Veracode](http://www.veracode.com/products/static-analysis-sast/static-code-analysis)  :copyright: — 在不需要源代码的情况下查找二进制文件和字节码中的缺陷. 支持所有主要编程语言：Java、.NET、JavaScript、Swift、Objective-C、C、C++ 等.

- [WALA](https://github.com/wala/WALA) — Java 字节码和相关语言以及 JavaScript 的静态分析功能.

- [weggli](https://github.com/googleprojectzero/weggli)  — 用于 C 和 C++ 代码库的快速且强大的语义搜索工具. 它旨在帮助安全研究人员识别大型代码库中有趣的功能.

- [WhiteHat Application Security Platform](https://www.whitehatsec.com/platform/static-application-security-testing) :copyright: — WhiteHat Scout（面向开发人员）与 WhiteHat Sentinel Source（面向运营）相结合，支持 WhiteHat Top 40 和 OWASP Top 10.

- [Wotan](https://github.com/fimbullinter/wotan) — 可插入的 TypeScript 和 JavaScript linter.

- [XCode](https://developer.apple.com/xcode) :copyright: — XCode 为 [Clang's](http://clang-analyzer.llvm.org/xcode.html) 静态代码分析器（C/C++，Obj-C）.


## Other



<h2 id="angular">有角的</h2>


- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) — Angular 项目的 Linter


<h2 id="ansible">Ansible的</h2>


- [kics](https://kics.io/)  — 在您的基础设施即代码中查找安全漏洞、合规性问题和基础设施配置错误. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible


<h2 id="archive">档案</h2>


- [alquitran](https://github.com/ferivoz/alquitran) — 检查 tar 存档并尝试发现与 POSIX 2017 pax 规范和常见 tar 实现有关的可移植性问题.
该项目旨在供希望为尽可能多的系统提供可移植源代码存档的项目维护人员使用. 在发布之前使用 alquitran 检查 tar 档案应该有助于在问题到达分销商和用户之前发现问题.

- [packj](https://packj.dev)  — Packj（发音为 package）是一个命令行 (CLI) 工具，用于审查开源软件包是否存在“风险”属性，这些属性使它们容易受到供应链攻击. 这是我们的大型安全分析平台 Packj.dev 背后的工具，它不断审查包并提供免费报告.

- [pure](https://github.com/ronomon/pure) — Pure 是一个静态分析文件格式检查器，用于检查 ZIP 文件是否存在危险的压缩比、规范偏差、恶意存档签名、不匹配的本地和中央目录标头、不明确的 UTF-8 文件名、目录和符号链接遍历、无效的 MS-DOS 日期、重叠标题，溢出，下溢，稀疏，意外缓冲区流血等.


<h2 id="arm">Azure 资源管理器</h2>


- [AzSK](https://azsk.azurewebsites.net/)  — 用于 Azure (AzSK) 的安全 DevOps 工具包提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础设施即代码中的基础设施错误配置. 通过 ARM 支持 Azure.


<h2 id="binary">二进制文件</h2>


- [angr](https://github.com/angr/angr) — 也支持符号执行的二进制代码分析工具.

- [binbloom](https://github.com/quarkslab/binbloom)  — 分析原始二进制固件并确定字节顺序或加载地址等特征. 该工具与所有架构兼容.
加载地址：binbloom 可以解析原始二进制固件并确定其加载地址. 字节顺序：binbloom 可以使用启发式方法来确定固件的字节顺序.  UDS 数据库：binbloom 可以解析原始二进制固件并检查它是否包含包含 UDS 命令 ID 的数组.

- [BinSkim](https://github.com/Microsoft/binskim) — 一种二进制静态分析工具，可为 Windows 可移植可执行文件提供安全性和正确性结果.

- [Black Duck](https://www.blackducksoftware.com) :copyright: — 用于分析源代码和二进制文件以获取可重用代码、必要许可和潜在安全方面的工具.

- [bloaty](https://github.com/google/bloaty)  — 有没有想过是什么让你的二进制文件变大了？  Bloaty McBloatface 将向您展示二进制文件的大小概况，以便您了解内部占用空间的内容.  Bloaty 对二进制文件进行深入分析.  Bloaty 使用自定义 ELF、DWARF 和 Mach-O 解析器，旨在将二进制文件的每个字节准确地归因于生成它的符号或编译单元. 它甚至会反汇编二进制文件以查找对匿名数据的引用.  F

- [cargo-bloat](https://github.com/RazrFalcon/cargo-bloat)  — 找出什么占用了可执行文件中的大部分空间. 支持 ELF（Linux、BSD）、Mach-O（macOS）和 PE（Windows）二进制文件.

- [cwe_checker](https://github.com/fkie-cad/cwe_checker) — cwe_checker 在二进制可执行文件中发现易受攻击的模式.

- [Ghidra](https://ghidra-sre.org) — 由 NSA 研究理事会开发的软件逆向工程 (SRE) 工具套件，用于支持网络安全任务

- [IDA Free](https://www.hex-rays.com/products/ida/support/download_freeware) :copyright: — 二进制代码分析工具.

- [Jakstab](https://github.com/jkinder/jakstab) — Jakstab 是一个基于抽象解释的集成反汇编和静态分析框架，用于设计可执行文件的分析和恢复可靠的控制流图.

- [JEB Decompiler](https://www.pnfsoftware.com/)  :copyright: — 反编译和调试二进制代码. 分解和分析文档文件.  Android Dalvik、MIPS、ARM、Intel x86、Java、WebAssembly 和 Ethereum 反编译器.

- [Manalyze](https://github.com/JusticeRage/Manalyze) — 静态分析器，检查可移植可执行文件中的恶意内容.

- [mcsema](https://github.com/lifting-bits/mcsema)  — 将 x86、amd64、aarch64、sparc32 和 sparc64 程序二进制文件提升为 LLVM 位码的框架. 它将可执行二进制文件从本机机器代码翻译（“提升”）为 LLVM 位代码，这对于执行程序分析方法非常有用.

- [Nauz File Detector](https://github.com/horsicq/Nauz-File-Detector) — 适用于 Windows、Linux 和 MacOS 的静态链接器/编译器/工具检测器.

- [rust-audit](https://github.com/Shnatsel/rust-audit)  — 审计 Rust 二进制文件是否存在已知错误或安全漏洞. 这是通过将有关依赖树 (Cargo.lock) 的数据以 JSON 格式嵌入到已编译可执行文件的专用链接器部分中来实现的.

- [Twiggy](https://rustwasm.github.io/twiggy)  — 分析二进制文件的调用图以分析代码大小. 目标是缩小 wasm 二进制大小.

- [VMware chap](https://github.com/vmware/chap)  — chap 分析未检测的 ELF 核心文件是否存在泄漏、内存增长和损坏. 它足够可靠，可以用于自动化以在泄漏发生之前捕获它们. 作为一种交互式工具，它有助于解释内存增长，可以识别某些形式的损坏，并通过提供各种内存位置的状态来补充调试器. 

- [zydis](https://zydis.re) — 快速轻量级的 x86/x86-64 反汇编程序库


<h2 id="buildtool">构建工具</h2>


- [checkmake](https://github.com/mrtazz/checkmake) — Makefile 的 Linter / 分析器.

- [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) — FreeBSD 和 DragonFlyBSD 端口目录的验证器.


<h2 id="css">CSS/SASS/SCSS</h2>


- [CSS Stats](https://cssstats.com) — 样式表上可能有趣的统计数据.

- [CSScomb](https://github.com/csscomb/csscomb.js)  — CSS 的编码样式格式化程序. 支持自定义配置，使样式表美观一致.

- [CSSLint](http://csslint.net) — 进行基本的语法检查并发现有问题的模式或效率低下的迹象.

- [GraphMyCSS.com](https://graphmycss.com) — CSS 特异性图生成器.

- [Nu Html Checker](https://validator.github.io/validator/) — 帮助您发现 HTML/CSS/SVG 中的问题

- [Parker](https://github.com/katiefenn/parker) — 样式表分析工具.

- [PostCSS](https://postcss.org)  — 使用 JS 插件转换样式的工具. 这些插件可以检查您的 CSS、支持变量和混合、转换未来的 CSS 语法、内联图像等等.

- [Project Wallace CSS Analyzer](https://www.projectwallace.com) — CSS 分析，部分 [Project Wallace](https://www.projectwallace.com).

- [sass-lint](https://github.com/sasstools/sass-lint) :warning: — 用于 sass 和 scss 语法的仅限节点的 Sass linter.

- [scsslint](https://github.com/brigade/scss-lint) :warning: — SCSS 文件的 Linter.

- [Specificity Graph](https://jonassebastianohlsson.com/specificity-graph) — CSS 特异性图生成器.

- [Stylelint](http://stylelint.io) — SCSS/CSS 文件的 Linter.


<h2 id="configfile">配置文件</h2>


- [dotenv-linter](https://dotenv-linter.readthedocs.io/en/latest) — 像魅力一样检查 dotenv 文件.

- [dotenv-linter (Rust)](https://dotenv-linter.github.io/#/)  — .env 文件的快如闪电的 linter. 用 Rust 编写

- [gixy](https://github.com/yandex/gixy)  — 分析 Nginx 配置的工具. 主要目标是防止错误配置和自动化缺陷检测.


<h2 id="configmanagement">配置管理</h2>


- [ansible-lint](https://docs.ansible.com/ansible-lint) — 检查剧本中是否有可能改进的做法和行为.

- [AWS CloudFormation Guard](https://github.com/aws-cloudformation/cloudformation-guard) — 根据策略即代码规则检查本地 CloudFormation 模板，并从现有模板生成规则.

- [AzSK](https://azsk.azurewebsites.net/)  — 用于 Azure (AzSK) 的安全 DevOps 工具包提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础设施即代码中的基础设施错误配置. 通过 ARM 支持 Azure.

- [cfn-lint](https://github.com/awslabs/cfn-python-lint) — AWS 实验室 CloudFormation linter.

- [cfn_nag](https://github.com/stelligent/cfn_nag) — AWS CloudFormation 模板的 linter.

- [checkov](https://www.checkov.io) — Terraform 文件的静态分析工具 (tf&gt;=v0.12)，防止在构建时出现云错误配置.

- [cookstyle](https://docs.chef.io/cookstyle.html) — Cookstyle 是一种基于 RuboCop Ruby linting 工具的 linting 工具，适用于 Chef 食谱.

- [foodcritic](http://www.foodcritic.io) — 检查 Chef 食谱中是否存在常见问题的 lint 工具.

- [kics](https://kics.io/)  — 在您的基础设施即代码中查找安全漏洞、合规性问题和基础设施配置错误. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint) — 检查 Puppet metadata.json 文件有效性的工具.

- [Puppet Lint](https://github.com/rodjek/puppet-lint) — 检查您的 Puppet 清单是否符合风格指南.

- [terraform-compliance](https://terraform-compliance.com) — 针对 Terraform 的轻量级、以合规性和安全性为重点的 BDD 测试框架.

- [terrascan](https://github.com/cesar-rodriguez/terrascan) — 为 Terraform 模板的静态代码分析收集安全和最佳实践测试.

- [tflint](https://github.com/wata727/tflint) — 用于检测“terraform plan”无法检测到的错误的 Terraform linter.

- [tfsec](https://github.com/tfsec/tfsec)  — Terraform 静态分析工具，通过在构建时检查云错误配置来防止潜在的安全问题，并直接与 HCL 解析器集成以获得更好的结果. 检查是否违反了 AWS、Azure 和 GCP 安全最佳实践建议.


<h2 id="container">集装箱</h2>


- [anchore](https://anchore.io)  — 发现、分析和验证容器镜像. 一种分析 Docker 映像并应用用户定义的接受策略以允许自动进行容器映像验证和认证的服务 

- [clair](https://github.com/coreos/clair) — 容器的漏洞静态分析.

- [collector](https://github.com/banyanops/collector) — 在容器内运行任意脚本，并收集有用的信息.

- [dagda](https://github.com/eliasgranderubio/dagda) — 对 docker 镜像/容器中的已知漏洞进行静态分析.

- [Docker Label Inspector](https://github.com/garethr/docker-label-inspector) — Lint 和验证 Dockerfile 标签.

- [Haskell Dockerfile Linter](https://github.com/lukasmartinelli/hadolint) — 更智能的 Dockerfile linter，可帮助您构建最佳实践 Docker 映像.

- [kics](https://kics.io/)  — 在您的基础设施即代码中查找安全漏洞、合规性问题和基础设施配置错误. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [OpenSCAP](https://www.open-scap.org/) — 一套自动化审计工具，用于检查遵循 NIST 认证的安全内容自动化协议 (SCAP) 的配置和已知漏洞.

- [Qualys Container Security](https://www.qualys.com/apps/container-security) :copyright: — 容器本机应用程序保护，以提供容器化应用程序的可见性和控制.

- [sysdig](https://sysdig.com/)  :copyright: — 用于云和容器取证的安全 DevOps 平台.  Sysdig 建立在开源堆栈之上，提供 Docker 图像扫描并创建了 Falco，这是容器、Kubernetes 和云的运行时威胁检测的开放标准. 

- [Vuls](https://vuls.io/) — 基于 NVD、OVAL 等信息的无代理 Linux 漏洞扫描器.它有一些容器图像支持，尽管不是容器特定的工具.


<h2 id="ci">持续集成</h2>


- [actionlint](https://rhysd.github.io/actionlint)  — GitHub Actions 工作流文件的静态检查器. 提供在线版本.

- [AzSK](https://azsk.azurewebsites.net/)  — 用于 Azure (AzSK) 的安全 DevOps 工具包提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础设施即代码中的基础设施错误配置. 通过 ARM 支持 Azure.

- [Code Climate](https://codeclimate.com) — 开放且可扩展的静态分析平台，适合所有人.

- [Codecov](https://about.codecov.io/) :copyright: — Codecov 是一家为开发人员和工程负责人提供代码覆盖率工具以了解其代码覆盖率的公司.
他们提供灵活统一的报告、无缝的覆盖洞察力和强大的覆盖控制.  Codecov 支持 20 多种语言，并且与 CI/CD 无关. 超过 29,000 个组织和 100 万开发人员使用 Codecov.  Codecov 最近加入了 Sentry.

- [Diffblue](https://www.diffblue.com/) :copyright: — Diffblue 是一家软件公司，为软件开发团队提供基于 AI 的代码分析和测试解决方案.
它的技术可帮助开发人员在其软件开发过程中实现自动化测试、查找错误并减少人工劳动. 该公司的主要产品 Diffblue Cover 使用 AI 为 Java 代码生成和运行单元测试，有助于发现错误并提高代码质量.

- [exakat](https://www.exakat.io) — PHP 的自动代码审查引擎.

- [Goblint](https://goblint.in.tum.de)  — 用于分析多线程 C 程序的静态分析器. 它的主要重点是检测数据竞争，但它也报告其他运行时错误，例如缓冲区溢出和空指针取消引用.

- [Nitpick CI](https://nitpick-ci.com) :copyright: — 自动 PHP 代码审查.

- [PullRequest](https://www.pullrequest.com)  :copyright: — 代码审查作为具有内置静态分析的服务. 通过由一流自动化支持的专家工程师进行质量代码审查，提高速度并减少技术债务.

- [quality](https://github.com/apiology/quality) — 使用社区工具对您的代码进行质量检查，并确保您的代码不会随着时间的推移而变得更糟.

- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode)  :warning: — 自动代码审查和修复. 它可以帮助您跟踪软件项目中的问题和指标，并且可以轻松扩展以支持新型分析.

- [Reviewdog](https://github.com/haya14busa/reviewdog) — 用于从任何代码托管服务中的任何 linter 发布评论的工具.

- [Symfony Insight](https://insight.symfony.com/) :copyright: — 检测安全风险、查找错误并为 PHP 项目提供可操作的指标.

- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  — 用于从静态代码分析中解析报告文件的 Java 库. 由一堆 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="deno">不是</h2>


- [deno_lint](https://github.com/denoland/deno_lint) — Deno 的官方 linter.


<h2 id="embedded">嵌入式</h2>


- [oelint-adv](https://github.com/priv-kweihmann/oelint-adv) — 开放式嵌入式和 YOCTO 中使用的 bitbake 配方的 Linter


<h2 id="erb">嵌入式 Ruby（又名 ERB、eRuby）</h2>


- [ERB Lint](https://github.com/Shopify/erb-lint) — 整理你的 ERB 或 HTML 文件

- [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)  — HTML 的规范化器/美化器，也理解嵌入式 Ruby. 整理 Rails 模板的理想选择.


<h2 id="gherkin">小黄瓜</h2>


- [gherkin-lint](https://github.com/vsiakka/gherkin-lint) — 用 Ja​​vascript 编写的 Gherkin-Syntax 的 linter.


<h2 id="html">HTML</h2>


- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) — Angular 项目的 Linter

- [Bootlint](https://github.com/twbs/bootlint) — 用于 Bootstrap 项目的 HTML linter.

- [ERB Lint](https://github.com/Shopify/erb-lint) — 整理你的 ERB 或 HTML 文件

- [grunt-bootlint](https://github.com/twbs/grunt-bootlint) — Grunt 包装器 [Bootlint](https://github.com/twbs/bootlint)，用于 Bootstrap 项目的 HTML linter.

- [gulp-bootlint](https://github.com/tschortsch/gulp-bootlint) — 一个 gulp 包装器 [Bootlint](https://github.com/twbs/bootlint)，用于 Bootstrap 项目的 HTML linter.

- [HTML Inspector](https://github.com/philipwalton/html-inspector) :warning: — HTML Inspector 是一种代码质量工具，可帮助您和您的团队编写更好的标记.

- [HTML Tidy](http://www.html-tidy.org) — 通过修复标记错误并将遗留代码升级到现代标准来更正和清理 HTML 和 XML 文档.

- [HTML-Validate](https://html-validate.org/) — 离线 HTML5 验证器.

- [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)  — HTML 的规范化器/美化器，也理解嵌入式 Ruby. 整理 Rails 模板的理想选择.

- [HTMLHint](https://htmlhint.com) — HTML 的静态代码分析工具.

- [Nu Html Checker](https://validator.github.io/validator/) — 帮助您发现 HTML/CSS/SVG 中的问题

- [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer) — Web 组件的静态分析框架.


<h2 id="json">JSON</h2>


- [jsonlint](https://jsonlint.com/)  — 带有 CLI 的 JSON 解析器和验证器. 单机版的 jsonlint.com

- [Spectral](https://stoplight.io/open-source/spectral) — 灵活的 JSON/YAML linter，开箱即用地支持 OpenAPI v2/v3 和 AsyncAPI v2.


<h2 id="kubernetes">库伯内斯</h2>


- [chart-testing](https://github.com/helm/chart-testing) — ct is the the tool for testing Helm charts.  It is meant to be used for linting and testing pull requests.  It automatically detects charts changed against the target branch.

- [clusterlint](https://github.com/digitalocean/clusterlint)  — Clusterlint 查询实时 Kubernetes 集群的资源，对这些资源执行通用和平台特定的检查，并向集群操作员提供可操作的反馈. 它是一种在外部运行的非侵入式工具.  Clusterlint 不会改变资源配置.

- [Datree](https://datree.io/) — 通过确保清单和 Helm 图表遵循最佳实践以及您组织的政策来防止 Kubernetes 错误配置的 CLI 工具

- [kics](https://kics.io/)  — 在您的基础设施即代码中查找安全漏洞、合规性问题和基础设施配置错误. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [klint](https://github.com/uswitch/klint)  — 一种侦听 Kubernetes 资源变化并针对它们运行 linting 规则的工具. 识别和调试错误的对象并根据策略调整对象，因为这两者都会随着时间的推移而变化.  Klint 帮助我们对检查进行编码，并在团队需要采取行动时主动提醒他们.

- [kube-hunter](https://aquasecurity.github.io/kube-hunter/) — 寻找 Kubernetes 集群中的安全漏洞.

- [kube-lint](https://github.com/viglesiasce/kube-lint)  — 具有可定制规则集的 Kubernetes 资源 linter. 您定义一个规则列表，您希望根据您的资源验证这些规则，kube-lint 将根据它们评估这些规则.

- [kube-linter](https://github.com/stackrox/kube-linter) — KubeLinter 是一种静态分析工具，用于检查 Kubernetes YAML 文件和 Helm 图表，以确保其中代表的应用程序符合最佳实践.

- [kube-score](https://kube-score.com) — Kubernetes 对象定义的静态代码分析.

- [kubeconform](https://github.com/yannh/kubeconform) — 一个快速的 Kubernetes 清单验证器，支持自定义资源.
它的灵感来自于，包含来自的代码，并且旨在保持接近 [Kubeval](https://analysis-tools.dev/tool/kubeval)，但具有以下改进：*高性能：将通过多个例程验证和下载清单，将下载的文件缓存在内存中*可配置的远程或本地模式位置列表，启用验证 Kubernetes 自定义资源（CRD）和离线验证功能*使用默认情况下，由 kubernetes-json-schema 项目维护的模式注册表的自我更新分支——它保证所有最新版本的 Kubernetes 的模式都是最新的.

- [KubeLinter](https://github.com/stackrox/kube-linter) — KubeLinter 是一种静态分析工具，用于检查 Kubernetes YAML 文件和 Helm 图表，以确保其中代表的应用程序符合最佳实践.

- [kubeval](https://kubeval.instrumenta.dev) — 验证您的 Kubernetes 配置文件并支持多个 Kubernetes 版本.


<h2 id="latex">乳胶</h2>


- [ChkTeX](http://www.nongnu.org/chktex) — 用于 LaTex 的 linter，它可以捕获 LaTeX 监督的一些印刷错误.

- [lacheck](https://www.ctan.org/pkg/lacheck) — 用于查找 LaTeX 文档中常见错误的工具.

- [TeXLab](https://texlab.netlify.app) — TeX/LaTeX 的语言服务器协议实现，包括 lint 功能.


<h2 id="laravel">拉维</h2>


- [Enlightn](https://www.laravel-enlightn.com/)  — Laravel 应用程序的静态和动态分析工具，提供建议以提高 Laravel 应用程序的性能、安全性和代码可靠性. 包含 120 个自动检查.


<h2 id="make">生成文件</h2>


- [checkmake](https://github.com/mrtazz/checkmake) — Makefile 的 Linter / 分析器.

- [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) — FreeBSD 和 DragonFlyBSD 端口目录的验证器.


<h2 id="markdown">降价</h2>


- [markdownlint](https://github.com/DavidAnson/markdownlint) — 用于 Markdown/CommonMark 文件的基于 Node.js 的样式检查器和 lint 工具.

- [mdformat](https://mdformat.rtfd.io) — CommonMark 兼容的 Markdown 格式化程序

- [mdl](https://github.com/mivok/markdownlint) — 检查 Markdown 文件和标记样式问题的工具.

- [remark-lint](https://remark.js.org) — 用 Ja​​vaScript 编写的可插入 Markdown 代码样式 linter.


<h2 id="meta">金属互化器</h2>


- [ciocheck](https://github.com/ContinuumIO/ciocheck)  — Linter、格式化程序和测试套件助手. 作为 linter，它是 `pep8`、`pydocstyle`、`flake8` 和 `pylint` 的包装器.

- [flake8](https://github.com/PyCQA/flake8) — `pyflakes`、`pycodestyle` 和 `mccabe` 的​​包装器.

- [Go Meta Linter](https://github.com/alecthomas/gometalinter)  :warning: — 同时运行 Go lint 工具并规范化它们的输出. 对新项目使用 `golangci-lint`.

- [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) — 同时运行许多 linters 并将它们的输出规范化为报告.

- [multilint](https://github.com/adamchainz/multilint) — `flake8`、`isort` 和 `modernize` 的包装器.

- [prospector](https://github.com/PyCQA/prospector) — `pylint`、`pep8`、`mccabe` 等的包装器.


<h2 id="mobile">移动的</h2>


- [Android Lint](http://tools.android.com/tips/lint) — 在 Android 项目上运行静态分析.

- [android-lint-summary](https://passy.github.io/android-lint-summary) — 将多个项目的 lint 错误合并为一个输出，一次检查多个子项目的 lint 结果.

- [FlowDroid](https://github.com/secure-software-engineering/FlowDroid) — 适用于 Android 应用程序的静态污点分析工具.

- [iblessing](https://www.kitploit.com/2020/08/iblessing-ios-security-exploiting.html)  — iblessing 是一个 iOS 安全漏洞利用工具包. 它可用于逆向工程、二进制分析和漏洞挖掘.

- [Oversecured](https://oversecured.com)  :copyright: — 适用于 Android 和 iOS 应用程序的企业漏洞扫描器. 它允许应用程序所有者和开发人员通过将 Oversecured 集成到开发过程中来保护移动应用程序的每个新版本.

- [paprika](https://github.com/GeoffreyHecht/paprika) — 一个工具包，用于检测已分析的 Android 应用程序中的某些代码气味.

- [qark](https://github.com/linkedin/qark) — 用于查找多个与安全相关的 Android 应用程序漏洞的工具.

- [redex](https://fbredex.com)  — Redex 提供了一个读取、写入和分析.dex 文件的框架，以及一组使用该框架改进字节码的优化通道. 经过 Redex 优化的 APK 应该更小更快.


<h2 id="nix">尼克斯</h2>


- [deadnix](https://github.com/astro/deadnix) — 扫描 Nix 文件中的死代码（未使用的变量绑定）

- [statix](https://git.peppe.rs/languages/statix/about/)  — Nix 编程语言的 Lint 和建议.  “statix check”突出了 Nix 代码中的反模式.  “statix fix”可以修复几个这样的事件.


<h2 id="nodejs">节点.js</h2>


- [lockfile-lint](https://github.com/lirantal/lockfile-lint) — Lint 一个 npm 或 yarn lockfile 来分析和检测安全问题

- [njsscan](https://opensecurity.in) — 一种静态应用程序测试 (SAST) 工具，可以使用来自 libsast 的简单模式匹配器和语法感知语义代码模式搜索工具 semgrep 在您的 node.js 应用程序中找到不安全的代码模式.

- [NodeJSScan](https://opensecurity.in)  — 一个用于 Node.js 应用程序的静态安全代码扫描器，由 libsast 和 semgrep 提供支持，构建在 njsscan cli 工具之上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.

- [standard](http://standardjs.com) — 检查 Javascript Styleguide 问题的 npm 模块.


<h2 id="package">Packages</h2>


- [lintian](https://lintian.debian.org) — Debian 软件包的静态分析工具.

- [rpmlint](https://github.com/rpm-software-management/rpmlint) — 用于检查 rpm 包中常见错误的工具.


<h2 id="protobuf">协议缓冲区</h2>


- [buf](https://buf.build) — 提供一个 CLI linter，强制执行良好的 API 设计选择和结构

- [protolint](https://github.com/yoheimuta/protolint) — 可插拔的 linter 和 fixer 来执行 Protocol Buffer 风格和约定.


<h2 id="puppet">木偶</h2>


- [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint) — 检查 Puppet metadata.json 文件有效性的工具.


<h2 id="rails">导轨</h2>


- [dawnscanner](https://github.com/thesp0nge/dawnscanner)  — 用于 ruby​​ 编写的 Web 应用程序的静态分析安全扫描器. 它支持 Sinatra、Padrino 和 Ruby on Rails 框架.


<h2 id="security">安全/先科</h2>


- [AzSK](https://azsk.azurewebsites.net/)  — 用于 Azure (AzSK) 的安全 DevOps 工具包提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础设施即代码中的基础设施错误配置. 通过 ARM 支持 Azure.

- [brakeman](https://brakemanscanner.org) — 用于 Ruby on Rails 应用程序的静态分析安全漏洞扫描器.

- [Datree](https://datree.io/) — 通过确保清单和 Helm 图表遵循最佳实践以及您组织的政策来防止 Kubernetes 错误配置的 CLI 工具

- [detect-secrets](https://github.com/Yelp/detect-secrets) — 一种检测和防止代码中的秘密的企业友好方式.
它通过针对启发式制作的正则表达式语句运行定期差异输出来确定是否已提交任何新秘密. 这样，它避免了挖掘所有 git 历史的开销，也避免了每次都扫描整个存储库的需要.

- [Enlightn](https://www.laravel-enlightn.com/)  — Laravel 应用程序的静态和动态分析工具，提供建议以提高 Laravel 应用程序的性能、安全性和代码可靠性. 包含 120 个自动检查.

- [Gitleaks](https://github.com/zricethezav/gitleaks) — 一种 SAST 工具，用于检测 git repos 中的硬编码秘密，如密码、api 密钥和令牌.

- [gokart](https://github.com/praetorian-inc/gokart)  — Golang 安全分析，重点是最大限度地减少误报. 它能够追踪变量和函数参数的来源，以确定输入源是否安全.

- [iblessing](https://www.kitploit.com/2020/08/iblessing-ios-security-exploiting.html)  — iblessing 是一个 iOS 安全漏洞利用工具包. 它可用于逆向工程、二进制分析和漏洞挖掘.

- [kics](https://kics.io/)  — 在您的基础设施即代码中查找安全漏洞、合规性问题和基础设施配置错误. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [kube-hunter](https://aquasecurity.github.io/kube-hunter/) — 寻找 Kubernetes 集群中的安全漏洞.

- [lockfile-lint](https://github.com/lirantal/lockfile-lint) — Lint 一个 npm 或 yarn lockfile 来分析和检测安全问题

- [LunaSec](https://www.lunasec.io)  — 开源 AppSec 平台，可在下次发生 Log4Shell 或 node-ipc 等漏洞时自动通知您. 跟踪您的依赖项并在集中式服务中构建.

- [njsscan](https://opensecurity.in) — 一种静态应用程序测试 (SAST) 工具，可以使用来自 libsast 的简单模式匹配器和语法感知语义代码模式搜索工具 semgrep 在您的 node.js 应用程序中找到不安全的代码模式.

- [NodeJSScan](https://opensecurity.in)  — 一个用于 Node.js 应用程序的静态安全代码扫描器，由 libsast 和 semgrep 提供支持，构建在 njsscan cli 工具之上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.

- [Oversecured](https://oversecured.com)  :copyright: — 适用于 Android 和 iOS 应用程序的企业漏洞扫描器. 它允许应用程序所有者和开发人员通过将 Oversecured 集成到开发过程中来保护移动应用程序的每个新版本.

- [PT Application Inspector](https://www.ptsecurity.com)  :copyright: — 识别代码缺陷并检测漏洞以防止网络攻击. 通过展示可能的漏洞来演示远程代码执行.

- [Qualys Container Security](https://www.qualys.com/apps/container-security) :copyright: — 容器本机应用程序保护，以提供容器化应用程序的可见性和控制.

- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode)  :warning: — 自动代码审查和修复. 它可以帮助您跟踪软件项目中的问题和指标，并且可以轻松扩展以支持新型分析.

- [Reshift](https://www.reshiftsecurity.com) :copyright: — 用于检测和管理 JavaScript 安全漏洞的源代码分析工具.

- [Rezilion](https://www.rezilion.com/) :copyright: — 发现您环境中所有组件的漏洞，过滤掉 85% 不可利用的漏洞，并创建补救计划和开票以升级违反安全策略的组件和/或在 CI 中自动打补丁.

- [scorecard](https://github.com/ossf/scorecard) — 安全记分卡——开源的安全健康指标

- [SearchDiggity](https://resources.bishopfox.com/resources/tools/google-hacking-diggity/attack-tools/)  :copyright: — 识别 Github、Google Code、MS CodePlex、SourceForge 等托管的开源代码项目中的漏洞. 该工具带有 130 多个默认搜索，可识别 SQL 注入、跨站点脚本 (XSS)、不安全的远程和本地文件包含、硬编码密码等. 

- [Symfony Insight](https://insight.symfony.com/) :copyright: — 检测安全风险、查找错误并为 PHP 项目提供可操作的指标.

- [tfsec](https://github.com/tfsec/tfsec)  — Terraform 静态分析工具，通过在构建时检查云错误配置来防止潜在的安全问题，并直接与 HCL 解析器集成以获得更好的结果. 检查是否违反了 AWS、Azure 和 GCP 安全最佳实践建议.

- [trufflehog](https://trufflesecurity.com) — 到处寻找凭据
TruffleHog 是一个开源秘密扫描引擎，可以解决公司整个技术堆栈中暴露的秘密. 

- [Tsunami Security Scanner](https://github.com/google/tsunami-security-scanner)  — 具有可扩展插件系统的通用网络安全扫描器，用于高度可靠地检测高严重性的类似 RCE 的漏洞. 可以添加用于查找漏洞（例如开放 API）的自定义检测器.


<h2 id="smart-contracts">智能合约</h2>


- [mythril](https://github.com/ConsenSys/mythril) — 一个包含电池的符号执行框架，可用于自动查找和利用智能合约中的漏洞.

- [MythX](https://mythx.io) :copyright: — MythX is an easy to use analysis platform which integrates several analysis methods like fuzzing, symbolic execution and static analysis to find vulnerabilities with high precision. It can be integrated with toolchains like Remix or VSCode or called from the command-line.

- [slither](https://github.com/trailofbits/slither) — 运行一套漏洞检测器的静态分析框架，打印关于合约细节的视觉信息，并提供一个 API 来轻松编写自定义分析.

- [solhint](https://protofire.github.io/solhint)  — Solhint 是由 https://protofire.io 创建的开源项目. 它的目标是为 Solidity 代码提供一个 linting 实用程序.

- [solium](https://ethlint.readthedocs.io/en/latest) — Solium 是一种 linter，用于识别和修复 Solidity 智能合约中的样式和安全问题.


<h2 id="support">支持</h2>


- [LibVCS4j](https://github.com/uni-bremen-agst/libvcs4j) — 一个 Java 库，通过为不同版本控制系统和问题跟踪器提供通用 API，允许现有工具分析软件系统的演变.

- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  — 用于从静态代码分析中解析报告文件的 Java 库. 由一堆 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="template">模板语言</h2>


- [ember-template-lint](https://github.com/ember-template-lint/ember-template-lint) — 用于 Ember 或 Handlebars 模板的 Linter.

- [haml-lint](https://github.com/sds/haml-lint) — 用于编写干净一致的 HAML 的工具.

- [slim-lint](https://github.com/sds/slim-lint) — 用于分析 Slim 模板的可配置工具.

- [yamllint](https://yamllint.readthedocs.io) — 检查 YAML 文件的语法有效性、键重复和外观问题，例如行长、尾随空格和缩进.


<h2 id="terraform">地貌</h2>


- [kics](https://kics.io/)  — 在您的基础设施即代码中查找安全漏洞、合规性问题和基础设施配置错误. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [shisho](https://docs.shisho.dev/)  — 为开发人员和安全团队设计的轻量级静态代码分析器. 它允许您使用类似于 sed 的直观 DSL 分析和转换源代码，但用于代码.


<h2 id="translation">翻译</h2>


- [dennis](https://github.com/willkg/dennis) — 一组用于处理 PO 文件以简化开发和提高质量的实用程序.


<h2 id="vue">查看.js</h2>


- [HTML-Validate](https://html-validate.org/) — 离线 HTML5 验证器.

- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)  — VS Code 的 Vue 工具，由 vls（vue 语言服务器）提供支持.  Vetur 支持格式化嵌入式 HTML、CSS、SCSS、JS、TypeScript 等.  Vetur 只有一个“整个文档格式化程序”，不能格式化任意范围.


<h2 id="wasm">Webassembly</h2>


- [Twiggy](https://rustwasm.github.io/twiggy)  — 分析二进制文件的调用图以分析代码大小. 目标是缩小 wasm 二进制大小.


<h2 id="writing">写作</h2>


- [After the Deadline](https://open.afterthedeadline.com) :warning: — 拼写、风格和语法检查器.

- [alex](https://alexjs.com) — Catch insensitive, inconsiderate writing

- [codespell](https://github.com/codespell-project/codespell) — 检查代码中常见的拼写错误.

- [languagetool](https://languagetool.org)  — 超过 25 种语言的风格和语法检查器. 它发现了许多简单的拼写检查器无法检测到的错误.

- [misspell-fixer](https://github.com/vlajos/misspell-fixer) — 修复源代码中常见拼写错误和拼写错误的快速工具.

- [Misspelled Words In Context](https://jwilk.net/software/mwic) — 拼写检查器，将可能的拼写错误分组并在其上下文中显示.

- [proselint](http://proselint.com) — 专注于写作风格而非语法的英语散文 linter.

- [vale](https://docs.errata.ai/vale/about) — 一种语法感知的 linter，用于散文，考虑到速度和可扩展性.

- [write-good](https://github.com/btford/write-good) — 专注于消除“黄鼠狼的话”的 linter.


<h2 id="yaml">YAML</h2>


- [Spectral](https://stoplight.io/open-source/spectral) — 灵活的 JSON/YAML linter，开箱即用地支持 OpenAPI v2/v3 和 AsyncAPI v2.

- [yamllint](https://yamllint.readthedocs.io) — 检查 YAML 文件的语法有效性、键重复和外观问题，例如行长、尾随空格和缩进.


<h2 id="git">混帐</h2>


- [commitlint](https://commitlint.js.org) — 检查你的提交信息是否符合常规的提交格式


## More Collections

- [Clean code linters](https://github.com/collections/clean-code-linters) — github collections 中的 linter 集合
- [Code Quality Checker Tools For PHP Projects](https://github.com/collections/code-quality-in-php) — github collections 中的 PHP linters 集合
- [go-tools](https://github.com/dominikh/go-tools) — 用于处理 Go 代码的工具和库的集合，包括 linters 和静态分析
- [linters](https://github.com/mcandre/linters) — 介绍静态代码分析
- [OWASP Source Code Analysis Tools](https://owasp.org/www-community/Source_Code_Analysis_Tools) — 由 Open Web Application Security Project 维护的工具列表
- [php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools) — 有用的 PHP 静态分析工具的评论列表
- [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) — 静态代码分析工具列表.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Matthias Endler](https://endler.dev) 已放弃该作品的所有版权和相关或邻接权.
用于格式化和显示该内容的底层源代码已获得 MIT 许可.


标题图片 [Designed by Freepik](http://www.freepik.com).
