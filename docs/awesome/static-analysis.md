<div class="github-widget" data-repo="analysis-tools-dev/static-analysis"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--  DON'T EDIT THIS FILE DIRECTLY. Edit `data/tools.yml` instead.  -->

 <a href="https://analysis-tools.dev/">
   <img width="400px" alt="Analysis Tools" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/logo.png" />
 </a>

This repository lists **static analysis tools** for all programming languages, build tools, config files and more.  
官方网站， [analysis-tools.dev](https://analysis-tools.dev/) 基于此存储库，并为每个工具添加排名、用户评论和其他资源，例如视频.

![CI](https://github.com/analysis-tools-dev/static-analysis/workflows/CI/badge.svg)

## What is Static Analysis?

> Static program analysis is the analysis of computer software that is performed without actually executing programs — [Wikipedia](https://en.wikipedia.org/wiki/Static_program_analysis)

 &gt; 作为一名程序员，我这几年做的最重要的事情就是积极追求静态代码分析. 比我用它防止的数百个严重错误更有价值的是我对软件可靠性和代码质量的看法发生了变化.  — [John Carmack (Creator of Doom)](https://www.gamasutra.com/view/news/128836/InDepth_Static_Code_Analysis.php)

## Sponsors

This project would not be possible without the generous support of our sponsors.

<table>
  <tr>
    <td><a href="https://deepcode.ai"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/deepcode.png" /></a></td>
    <td><a href="https://codescene.io/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/codescene.svg" /></a></td>
    <td><a href="https://r2c.dev/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/r2c.svg" /></a></td>
    <td><a href="https://codiga.io/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/codiga.svg" /></a></td>
  </tr>
</table>

如果您也想支持这个项目，请访问我们 [Github sponsors page](https://github.com/sponsors/analysis-tools-dev).

## Meaning of Symbols:

- :copyright: stands for proprietary software. All other tools are Open Source.
- :information_source: indicates that the community does not recommend to use this tool for new projects anymore. The icon links to the discussion issue.
- :warning: 表示此工具超过 1 年未更新，或者 repo 已存档.

Pull requests are very welcome!  
Also check out the sister project, [awesome-dynamic-analysis](https://github.com/mre/awesome-dynamic-analysis).



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
    <li><a href="#vbscript">VBScript</a></li>
    <li><a href="#verilog">Verilog/SystemVerilog</a></li>
    <li><a href="#vim-script">Vim Script</a></li>
    </ul>
</details>




---

## Programming Languages

<h2 id="abap">ABAP</h2>

- [abaplint](https://abaplint.org) - Linter for ABAP, written in TypeScript.
- [abapOpenChecks](https://docs.abapopenchecks.org) - 通过新的和可自定义的检查增强 SAP 代码检查器.


<h2 id="ada">有</h2>

- [Codepeer](http://www.adacore.com/codepeer) :copyright: - Detects run-time and logic errors.
- [Polyspace for Ada](https://www.mathworks.com/products/polyspace-ada.html) :copyright: - Provide code verification that proves the absence of overflow, divide-by-zero, out-of-bounds array access, and certain other run-time errors in source code.
- [SPARK](https://www.adacore.com/about-spark) :copyright: - Ada 的静态分析和形式验证工具集.


<h2 id="asm">Assembly</h2>

- [STOKE](https://github.com/StanfordPL/stoke) :warning: - A programming-language agnostic stochastic optimizer for the x86_64 instruction set. It uses random search to explore the extremely high-dimensional space of all possible program transformations.


<h2 id="awk">awk</h2>

- [gawk --lint](https://www.gnu.org/software/gawk/manual/html_node/Options.html) - 对可疑或不可移植到其他 awk 实现的构造发出警告.


<h2 id="c">C</h2>

- [Astrée](https://www.absint.com/astree/index.htm)  :copyright: - Astrée 自动证明 C/C++ 应用程序中不存在运行时错误和无效的并发行为. 它非常适合浮点计算，非常快速且异常精确. 该分析仪还检查 MISRA/CERT/CWE/Adaptive Autosar 编码规则，并支持 ISO 26262、DO-178C A 级和其他安全标准的认证.  Jenkins 和 Eclipse 插件可用.
- [CBMC](http://www.cprover.org/cbmc) - C 程序的有界模型检查器、用户定义的断言、标准断言、几种覆盖率度量分析.
- [clang-tidy](http://clang.llvm.org/extra/clang-tidy) - clang static analyser.
- [clazy](https://github.com/KDE/clazy) - Qt-oriented static code analyzer based on the Clang framework. clazy is a compiler plugin which allows clang to understand Qt semantics. You get more than 50 Qt related compiler warnings, ranging from unneeded memory allocations to misusage of API, including fix-its for automatic refactoring.
- [CMetrics](https://github.com/MetricsGrimoire/CMetrics) - Measures size and complexity for C files.
- [CPAchecker](https://cpachecker.sosy-lab.org) - A tool for configurable software verification of C programs.  The name CPAchecker was chosen to reflect that the tool is based on the CPA concepts and is used for checking software programs.
- [cppcheck](http://cppcheck.sourceforge.net) - Static analysis of C/C++ code.
- [CppDepend](https://www.cppdepend.com) :warning: :copyright: - Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.
- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) - Automated C++ checker that follows Google's style guide.
- [cqmetrics](https://github.com/dspinellis/cqmetrics) - C 代码的质量指标.
- [CScout](https://www.spinellis.gr/cscout) :warning: - C 和 C 预处理器代码的复杂性和质量指标.
- [ESBMC](http://esbmc.org) - ESBMC is an open source, permissively licensed, context-bounded model checker based on satisfiability modulo theories for the verification of single- and multi-threaded C/C++ programs.
- [flawfinder](http://dwheeler.com/flawfinder/) - 发现可能的安全漏洞.
- [flint++](https://github.com/JossWhittle/FlintPlusPlus) - flint 的跨平台、零依赖端口，这是 Facebook 开发和使用的 C++ lint 程序.
- [Frama-C](http://frama-c.com) - 用于 C 代码的健全且可扩展的静态分析器.
- [Helix QAC](https://www.perforce.com/products/helix-qac) :copyright: - Enterprise-grade static analysis for embedded software. Supports MISRA, CERT, and AUTOSAR coding standards.
- [IKOS](https://github.com/nasa-sw-vnv/ikos) - A sound static analyzer for C/C++ code based on LLVM.
- [Joern](https://joern.io) - Open-source code analysis platform for C/C++ based on code property graphs
- [LDRA](https://ldra.com) :copyright: - A tool suite including static analysis (TBVISION) to various standards including MISRA C & C++, JSF++ AV, CWE, CERT C, CERT C++ & Custom Rules.
- [PC-lint](https://www.gimpel.com)  :copyright: - C/C++ 的静态分析. 在 Windows/Linux/MacOS 下本机运行. 分析几乎任何平台的代码，支持 C11/C18 和 C++17.
- [Phasar](https://phasar.org) - A LLVM-based static analysis framework which comes with a taint and type state analysis.
- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) :copyright: - 识别 C 和 C++ 嵌入式软件中的运行时错误、并发问题、安全漏洞和其他缺陷.
- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) :copyright: - Provide code verification that proves the absence of overflow, divide-by-zero, out-of-bounds array access, and certain other run-time errors in C and C++ source code.
- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) - Analyzes C/C++ code using LLVM at compile-time.
- [splint](http://splint.org) - Annotation-assisted static program checker.
- [SVF](http://svf-tools.github.io/SVF) - 一种静态工具，可对 C 和 C++ 程序进行可扩展且精确的过程间依赖性分析.
- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) - Vera++ 是用于验证、分析和转换 C++ 源代码的可编程工具.


<h2 id="csharp">C#</h2>

- [.NET Analyzers](https://github.com/DotNetAnalyzers) - An organization for the development of analyzers (diagnostics and code fixes) using the .NET Compiler Platform.
- [ArchUnitNET](https://github.com/TNG/ArchUnitNET) - A C# architecture test library to specify and assert architecture rules in C# for automated testing.
- [code-cracker](http://code-cracker.github.io) - An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.
- [CSharpEssentials](https://github.com/DustinCampbell/CSharpEssentials) :warning: - C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features.
- [Designite](http://www.designite-tools.com) :copyright: - Designite 支持检测各种架构、设计和实现异味，计算各种代码质量指标和趋势分析.
- [Gendarme](https://www.mono-project.com/docs/tools+libraries/tools/gendarme) - 宪兵检查包含 ECMA CIL 格式（Mono 和 .NET）代码的程序和库.
- [Infer#](https://github.com/microsoft/infersharp) - InferSharp (also referred to as Infer#) is an interprocedural and  scalable static code analyzer for C#. Via the capabilities of Facebook's Infer,  this tool detects null pointer dereferences and resource leaks.
- [NDepend](http://www.ndepend.com) :copyright: - Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.
- [Puma Scan](https://pumasecurity.io) :warning: - 当开发团队在 Visual Studio 中编写代码时，Puma Scan 为常见漏洞（XSS、SQLi、CSRF、LDAPi、加密、反序列化等）提供实时安全代码分析.
- [Roslynator](https://github.com/JosefPihrt/Roslynator) - A collection of 190+ analyzers and 190+ refactorings for C#, powered by Roslyn.
- [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) :warning: - A collection of static analyzers based on Roslyn that integrates with VS.
- [Wintellect.Analyzers](https://github.com/Wintellect/Wintellect.Analyzers) - .NET Compiler Platform ("Roslyn") diagnostic analyzers and code fixes.


<h2 id="cpp">C++</h2>

- [Astrée](https://www.absint.com/astree/index.htm)  :copyright: - Astrée 自动证明 C/C++ 应用程序中不存在运行时错误和无效的并发行为. 它非常适合浮点计算，非常快速且异常精确. 该分析仪还检查 MISRA/CERT/CWE/Adaptive Autosar 编码规则，并支持 ISO 26262、DO-178C A 级和其他安全标准的认证.  Jenkins 和 Eclipse 插件可用.
- [CBMC](http://www.cprover.org/cbmc) - C 程序的有界模型检查器、用户定义的断言、标准断言、几种覆盖率度量分析.
- [clang-tidy](http://clang.llvm.org/extra/clang-tidy) - clang static analyser.
- [clazy](https://github.com/KDE/clazy) - Qt-oriented static code analyzer based on the Clang framework. clazy is a compiler plugin which allows clang to understand Qt semantics. You get more than 50 Qt related compiler warnings, ranging from unneeded memory allocations to misusage of API, including fix-its for automatic refactoring.
- [CMetrics](https://github.com/MetricsGrimoire/CMetrics) - Measures size and complexity for C files.
- [cppcheck](http://cppcheck.sourceforge.net) - Static analysis of C/C++ code.
- [CppDepend](https://www.cppdepend.com) :warning: :copyright: - Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.
- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) - Automated C++ checker that follows Google's style guide.
- [cqmetrics](https://github.com/dspinellis/cqmetrics) - C 代码的质量指标.
- [CScout](https://www.spinellis.gr/cscout) :warning: - C 和 C 预处理器代码的复杂性和质量指标.
- [ESBMC](http://esbmc.org) - ESBMC is an open source, permissively licensed, context-bounded model checker based on satisfiability modulo theories for the verification of single- and multi-threaded C/C++ programs.
- [flawfinder](http://dwheeler.com/flawfinder/) - 发现可能的安全漏洞.
- [flint++](https://github.com/JossWhittle/FlintPlusPlus) - flint 的跨平台、零依赖端口，这是 Facebook 开发和使用的 C++ lint 程序.
- [Frama-C](http://frama-c.com) - 用于 C 代码的健全且可扩展的静态分析器.
- [Helix QAC](https://www.perforce.com/products/helix-qac) :copyright: - Enterprise-grade static analysis for embedded software. Supports MISRA, CERT, and AUTOSAR coding standards.
- [IKOS](https://github.com/nasa-sw-vnv/ikos) - A sound static analyzer for C/C++ code based on LLVM.
- [Joern](https://joern.io) - Open-source code analysis platform for C/C++ based on code property graphs
- [LDRA](https://ldra.com) :copyright: - A tool suite including static analysis (TBVISION) to various standards including MISRA C & C++, JSF++ AV, CWE, CERT C, CERT C++ & Custom Rules.
- [PC-lint](https://www.gimpel.com)  :copyright: - C/C++ 的静态分析. 在 Windows/Linux/MacOS 下本机运行. 分析几乎任何平台的代码，支持 C11/C18 和 C++17.
- [Phasar](https://phasar.org) - A LLVM-based static analysis framework which comes with a taint and type state analysis.
- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) :copyright: - 识别 C 和 C++ 嵌入式软件中的运行时错误、并发问题、安全漏洞和其他缺陷.
- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) :copyright: - Provide code verification that proves the absence of overflow, divide-by-zero, out-of-bounds array access, and certain other run-time errors in C and C++ source code.
- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) - Analyzes C/C++ code using LLVM at compile-time.
- [splint](http://splint.org) - Annotation-assisted static program checker.
- [SVF](http://svf-tools.github.io/SVF) - 一种静态工具，可对 C 和 C++ 程序进行可扩展且精确的过程间依赖性分析.
- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) - Vera++ 是用于验证、分析和转换 C++ 源代码的可编程工具.


<h2 id="clojure">Clojure</h2>

- [clj-kondo](https://github.com/borkdude/clj-kondo)  - Clojure 代码的 linter 可以激发快乐. 它会在您键入时通知您潜在的错误.


<h2 id="coffeescript">CoffeeScript</h2>

- [coffeelint](http://www.coffeelint.org) - A style checker that helps keep CoffeeScript code clean and consistent.


<h2 id="crystal">Crystal</h2>

- [ameba](https://crystal-ameba.github.io) - Crystal 的静态代码分析工具.
- [crystal](https://crystal-lang.org) - The Crystal compiler has built-in linting functionality.


<h2 id="dart">Dart</h2>

- [Dart Code Metrics](https://pub.dev/packages/dart_code_metrics) - Additional linter for Dart. Reports code metrics, checks for anti-patterns and provides additional rules for Dart analyzer.
- [effective_dart](https://pub.dev/packages/effective_dart) - 与 Effective Dart 中的指南相对应的 Linter 规则
- [lint](https://github.com/passsy/dart-lint) - An opinionated, community-driven set of lint rules for Dart and Flutter projects. Like pedantic but stricter
- [Linter for dart](https://dart-lang.github.io/linter) - 飞镖风格的短绒.


<h2 id="delphi">德尔福</h2>

- [Fix Insight](https://www.tmssoftware.com/site/fixinsight.asp)  :copyright: - 用于静态代码分析的免费 IDE 插件.  _Pro_ 版本包括用于自动化目的的命令行工具.
- [Pascal Analyzer](https://peganza.com/products_pal.html)  :copyright: - 带有大量报告的静态代码分析工具. 提供有限报告的免费 _Lite_ 版本.
- [Pascal Expert](https://peganza.com/products_pex.html)  :copyright: - 用于代码分析的 IDE 插件. 包括 Pascal Analyzer 报告功能的子集，可用于 Delphi 2007 版及更高版本.


<h2 id="dlang">Dlang</h2>

- [D-scanner](https://github.com/dlang-community/D-Scanner) - D-Scanner is a tool for analyzing D source code.


<h2 id="elixir">灵药</h2>

- [credo](https://github.com/rrrene/credo) - A static code analysis tool with a focus on code consistency and teaching.
- [dialyxir](https://github.com/jeremyjh/dialyxir) - 混合任务以简化 Elixir 项目中 Dialyzer 的使用.
- [sobelow](https://github.com/nccgroup/sobelow) - Security-focused static analysis for the Phoenix Framework.


<h2 id="elm">榆树</h2>

- [elm-analyse](https://stil4m.github.io/elm-analyse) :warning: - A tool that allows you to analyse your Elm code, identify deficiencies and apply best practices.
- [elm-review](https://package.elm-lang.org/packages/jfmengels/elm-review/latest) - 分析整个 Elm 项目，重点关注用 Elm 编写的可共享和自定义规则，这些规则增加了 Elm 编译器无法提供的保证.


<h2 id="erlang">Erlang</h2>

- [dialyzer](https://www.erlang.org/doc/man/dialyzer.html)  - DIALYZER，ERlang 程序的差异分析器.  Dialyzer 是一个静态分析工具，用于识别软件差异，例如明确的类型错误、由于编程错误而死或无法访问的代码，以及在单个 Erlang 模块或整个（一组）应用程序中的不必要测试.
Dialyzer starts its analysis from either debug-compiled BEAM bytecode  or from Erlang source code. The file and line number of a discrepancy  is reported along with an indication of what the discrepancy is about.  Dialyzer bases its analysis on the concept of success typings,  which allows for sound warnings (no false positives).
- [elvis](https://github.com/inaka/elvis) - Erlang Style Reviewer.
- [Primitive Erlang Security Tool (PEST)](https://github.com/okeuday/pest) - 对 Erlang 源代码进行基本扫描并报告任何可能导致 Erlang 源代码不安全的函数调用的工具.


<h2 id="fsharp">F#</h2>

- [FSharpLint](http://fsprojects.github.io/FSharpLint) - Lint tool for F#.


<h2 id="fortran">Fortran</h2>

- [i-Code CNES for Fortran](https://github.com/lequal/i-CodeCNES) :warning: - An open source static code analysis tool for Fortran 77, Fortran 90 and Shell.


<h2 id="go">去</h2>

- [aligncheck](https://gitlab.com/opennota/check) - 查找低效打包的结构.
- [bodyclose](https://github.com/timakin/bodyclose) - 检查 HTTP 响应正文是否已关闭.
- [deadcode](https://github.com/tsenart/deadcode) - Finds unused code.
- [dingo-hunter](https://github.com/nickng/dingo-hunter) :warning: - Static analyser for finding deadlocks in Go.
- [dogsled](https://github.com/alexkohler/dogsled) - 查找具有太多空白标识符的分配/声明.
- [dupl](https://github.com/mibk/dupl) :warning: - 报告可能重复的代码.
- [errcheck](https://github.com/kisielk/errcheck) - Check that error return values are used.
- [errwrap](https://github.com/fatih/errwrap) - Wrap and fix Go errors with the new %w verb directive.  This tool analyzes fmt.Errorf() calls and reports calls that contain a verb directive that  is different than the new %w verb directive introduced in Go v1.13.  It's also capable of rewriting calls to use the new %w wrap verb directive.
- [flen](https://github.com/lafolle/flen) - Get info on length of functions in a Go package.
- [Go Meta Linter](https://github.com/alecthomas/gometalinter)  :warning: - 同时运行 Go lint 工具并标准化它们的输出. 对新项目使用 `golangci-lint`.
- [go tool vet --shadow](https://golang.org/cmd/vet#hdr-Shadowed_variables) - Reports variables that may have been unintentionally shadowed.
- [go vet](https://golang.org/cmd/vet) - Examines Go source code and reports suspicious.
- [go-consistent](https://github.com/Quasilyte/go-consistent) :warning: - Analyzer that helps you to make your Go programs more consistent.
- [go-critic](https://github.com/go-critic/go-critic) - Go source code linter that maintains checks which are currently not implemented in other linters.
- [go/ast](https://golang.org/pkg/go/ast) - 包 ast 声明了用于表示 Go 包语法树的类型.
- [gochecknoglobals](https://github.com/leighmcculloch/gochecknoglobals) - Checks that no globals are present.
- [goconst](https://github.com/jgautheron/goconst) - 查找可以被常量替换的重复字符串.
- [gocyclo](https://github.com/fzipp/gocyclo) - 计算 Go 源代码中函数的圈复杂度.
- [gofmt -s](https://golang.org/cmd/gofmt) - Checks if the code is properly formatted and could not be further simplified.
- [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) - 检查丢失或未引用的包导入.
- [gokart](https://github.com/praetorian-inc/gokart) - Golang security analysis with a focus on minimizing false positives. It is capable of tracing the source of variables and function arguments  to determine whether input sources are safe.
- [GolangCI-Lint](https://golangci-lint.run) - Alternative to `Go Meta Linter`: GolangCI-Lint is a linters aggregator.
- [golint](https://github.com/golang/lint) - Prints out coding style mistakes in Go source code.
- [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) - 同时运行许多 linter 并将它们的输出标准化为报告.
- [goroutine-inspect](https://github.com/linuxerwang/goroutine-inspect) - An interactive tool to analyze Golang goroutine dump.
- [gosec (gas)](https://securego.io) - Inspects source code for security problems by scanning the Go AST.
- [gotype](https://pkg.go.dev/golang.org/x/tools/cmd/gotype) - 类似于 Go 编译器的语法和语义分析.
- [ineffassign](https://github.com/gordonklaus/ineffassign) - 检测 Go 代码中的无效分配.
- [interfacer](https://github.com/mvdan/interfacer) :warning: - Suggest narrower interfaces that can be used.
- [lll](https://github.com/walle/lll) :warning: - Report long lines.
- [maligned](https://github.com/mdempsky/maligned) - Detect structs that would take less memory if their fields were sorted.
- [misspell](https://github.com/client9/misspell) - 查找常见拼写错误的英语单词.
- [nakedret](https://github.com/alexkohler/nakedret) - 寻找赤裸裸的回报.
- [nargs](https://github.com/alexkohler/nargs) - 在函数声明中查找未使用的参数.
- [prealloc](https://github.com/alexkohler/prealloc) - 查找可能被预分配的切片声明.
- [Reviewdog](https://github.com/haya14busa/reviewdog) - A tool for posting review comments from any linter in any code hosting service.
- [revive](https://revive.run) - Fast, configurable, extensible, flexible, and beautiful linter for Go. Drop-in replacement of golint.
- [safesql](https://github.com/stripe/safesql) - Static analysis tool for Golang that protects against SQL injections.
- [shisho](https://docs.shisho.dev/)  - 专为开发人员和安全团队设计的轻量级静态代码分析器. 它允许您使用类似于 sed 的直观 DSL 分析和转换源代码，但用于代码.
- [staticcheck](https://staticcheck.io) - Go static analysis that specialises in finding bugs, simplifying code and improving performance.
- [structcheck](https://gitlab.com/opennota/check) - 查找未使用的结构字段.
- [structslop](https://github.com/orijtech/structslop) - Static analyzer for Go that recommends struct field rearrangements to provide for maximum space/allocation efficiency
- [test](http://golang.org/pkg/testing) - Show location of test failures from the stdlib testing module.
- [unconvert](https://github.com/mdempsky/unconvert) :warning: - Detect redundant type conversions.
- [unparam](https://github.com/mvdan/unparam) - 查找未使用的函数参数.
- [varcheck](https://gitlab.com/opennota/check) - 查找未使用的全局变量和常量.
- [wsl](https://github.com/bombsimon/wsl) - 在正确的位置强制执行空行.


<h2 id="groovy">Groovy</h2>

- [CodeNarc](https://codenarc.github.io/CodeNarc) - Groovy 源代码的静态分析工具，可以监控和执行许多编码标准和最佳实践.


<h2 id="haskell">Haskell</h2>

- [brittany](https://github.com/lspitzner/brittany) - Haskell source code formatter
- [HLint](https://github.com/ndmitchell/hlint) - HLint is a tool for suggesting possible improvements to Haskell code.
- [Stan](https://kowainik.github.io/projects/stan) - Stan 是一个命令行工具，用于分析 Haskell 项目并以有用的方式输出发现的漏洞，并为检测到的问题提供可能的解决方案.
- [Weeder](https://github.com/ocharles/weeder) - 在 Haskell 代码中检测死导出或包导入的工具.


<h2 id="haxe">斧头</h2>

- [Haxe Checkstyle](http://haxecheckstyle.github.io/docs/haxe-checkstyle/home.html) - 一种静态分析工具，可帮助开发人员编写符合编码标准的 Haxe 代码.


<h2 id="java">爪哇</h2>

- [Checker Framework](https://checkerframework.org) - Java 的可插拔类型检查.
- [checkstyle](https://checkstyle.org) - Checking Java source code for adherence to a Code Standard or set of validation rules (best practices).
- [ck](https://github.com/mauricioaniche/ck) - Calculates Chidamber and Kemerer object-oriented metrics by processing the source Java files.
- [ckjm](http://www.spinellis.gr/sw/ckjm) - 通过处理已编译 Java 文件的字节码来计算 Chidamber 和 Kemerer 面向对象的指标.
- [CogniCrypt](https://www.eclipse.org/cognicrypt) - Checks Java source and byte code for incorrect uses of cryptographic APIs.
- [DesigniteJava](http://www.designite-tools.com/designitejava) :copyright: - DesigniteJava supports detection of various architecture, design, and implementation smells along with computation of various code quality metrics.
- [Doop](https://bitbucket.org/yanniss/doop)  - Doop是Java/Android程序静态分析的声明式框架，以指针分析算法为核心.  Doop 提供了种类繁多的分析以及周围的脚手架来运行端到端分析（事实生成、处理、统计等）.
- [Error-prone](https://errorprone.info) - Catch common Java mistakes as compile-time errors.
- [fb-contrib](http://fb-contrib.sourceforge.net) - A plugin for FindBugs with additional bug detectors.
- [forbidden-apis](https://github.com/policeman-tools/forbidden-apis) - Detects and forbids invocations of specific method/class/field (like reading from a text stream without a charset). Maven/Gradle/Ant compatible.
- [google-java-format](https://github.com/google/google-java-format) - Google Style Reformat.
- [HuntBugs](https://github.com/amaembo/huntbugs) :warning: - 基于 Procyon 编译器工具的字节码静态分析器工具旨在取代 FindBugs.
- [IntelliJ IDEA](https://www.jetbrains.com/idea) :copyright: - Comes bundled with a lot of inspections for Java and Kotlin and includes tools for refactoring, formatting and more.
- [JArchitect](https://www.jarchitect.com) :copyright: - Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.
- [JBMC](https://www.cprover.org/jbmc) - Java（字节码）的有界模型检查器，验证用户定义的断言、标准断言、几个覆盖率度量分析.
- [NullAway](https://github.com/uber/NullAway) - Type-based null-pointer checker with low build-time overhead; an [Error Prone](http://errorprone.info/) plugin.
- [OWASP Dependency Check](https://owasp.org/www-project-dependency-check) - Checks dependencies for known, publicly disclosed, vulnerabilities.
- [qulice](https://www.qulice.com) - Combines a few (pre-configured) static analysis tools (checkstyle, PMD, Findbugs, ...).
- [Reshift](https://www.reshiftsecurity.com) :copyright: - A source code analysis tool for detecting and managing Java security vulnerabilities.
- [Soot](https://soot-oss.github.io/soot) - 用于分析和转换 Java 和 Android 应用程序的框架.
- [Spoon](http://spoon.gforge.inria.fr)  - Spoon 是一个元编程库，用于分析和转换 Java 源代码（包括 Java 9、10、11、12、13、14）. 它解析源文件以构建具有强大分析和转换 API 的精心设计的 AST. 可以集成在 Maven 和 Gradle 中.
- [SpotBugs](https://spotbugs.github.io) - SpotBugs is FindBugs' successor. A tool for static analysis to look for bugs in Java code.
- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  - 用于从静态代码分析中解析报告文件的 Java 库. 被一堆 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="javascript">JavaScript</h2>

- [aether](http://aetherjs.com) :warning: - Lint, analyze, normalize, transform, sandbox, run, step through, and visualize user JavaScript, in node or the browser.
- [Closure Compiler](https://developers.google.com/closure/compiler) - 一种用于提高效率、减小大小并在 JavaScript 文件中提供代码警告的编译器工具.
- [ClosureLinter](https://github.com/google/closure-linter)  :warning: - 确保您项目的所有 JavaScript 代码都遵循 Google JavaScript 样式指南中的指南. 它还可以自动修复许多常见错误.
- [complexity-report](https://github.com/escomplex/complexity-report) :warning: - Software complexity analysis for JavaScript projects.
- [DeepScan](https://deepscan.io) :copyright: - An analyzer for JavaScript which targets runtime errors and quality issues rather than coding conventions.
- [es6-plato](https://github.com/the-simian/es6-plato) - Visualize JavaScript (ES6) source complexity.
- [escomplex](https://github.com/jared-stilwell/escomplex) :warning: - JavaScript 系列抽象语法树的软件复杂性分析.
- [Esprima](https://esprima.org) - 用于多用途分析的 ECMAScript 解析基础架构.
- [flow](https://flow.org) - A static type checker for JavaScript.
- [hegel](https://hegel.js.org) - JavaScript 的静态类型检查器，偏向于类型推断和强类型系统.
- [jshint](https://jshint.com/about) [:information_source:](https://github.com/analysis-tools-dev/static-analysis/blob/master/<https://github.com/analysis-tools-dev/static-analysis/issues/223>) - Detect errors and potential problems in JavaScript code and enforce your team's coding conventions.
- [JSLint](https://github.com/douglascrockford/JSLint) [:information_source:](https://github.com/analysis-tools-dev/static-analysis/blob/master/<https://github.com/analysis-tools-dev/static-analysis/issues/223>) - JavaScript 代码质量工具.
- [JSPrime](http://dpnishant.github.io/jsprime) :warning: - Static security analysis tool.
- [NodeJSScan](https://opensecurity.in)  - 由 libsast 和 semgrep 提供支持的 Node.js 应用程序的静态安全代码扫描程序，构建在 njsscan cli 工具上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.
- [plato](https://github.com/es-analysis/plato) :warning: - Visualize JavaScript source complexity.
- [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer) - Web 组件的静态分析框架.
- [retire.js](http://retirejs.github.io/retire.js) - Scanner detecting the use of JavaScript libraries with known vulnerabilities.
- [RSLint](http://rslint.org/) - A (WIP) JavaScript linter written in Rust designed to be as fast as possible, customizable, and easy to use.
- [standard](http://standardjs.com) - 检查 Javascript 样式指南问题的 npm 模块.
- [tern](https://ternjs.net) - 一个 JavaScript 代码分析器，用于深度、交叉编辑器语言支持.
- [TypL](https://typl.dev) - With TypL, you just write completely standard JS, and the tool figures out your types via powerful inferencing.
- [xo](https://github.com/xojs/xo) - Opinionated but configurable ESLint wrapper with lots of goodies included. Enforces strict and readable code.
- [yardstick](https://github.com/calmh/yardstick) :warning: - Javascript code metrics.


<h2 id="julia">Julia</h2>

- [StaticLint](https://github.com/julia-vscode/StaticLint.jl) - Static Code Analysis for Julia


<h2 id="kotlin">Kotlin</h2>

- [detekt](https://detekt.github.io/detekt) - Kotlin 代码的静态代码分析.
- [diktat](https://analysis-dev.github.io/diktat) - Strict coding standard for Kotlin and a linter that detects and auto-fixes code smells.
- [ktlint](https://ktlint.github.io) - An anti-bikeshedding Kotlin linter with built-in formatter.


<h2 id="lua">拿</h2>

- [luacheck](https://github.com/mpeterv/luacheck) :warning: - Lua 代码的 linting 和静态分析工具。
- [lualint](https://github.com/philips/lualint) - lualint performs luac-based static analysis of global variable usage in Lua source code.
- [Luanalysis](https://plugins.jetbrains.com/plugin/14698-luanalysis) - 用于静态类型 Lua 开发的 IDE.


<h2 id="matlab">MATLAB</h2>

- [mlint](https://mathworks.com/help/matlab/ref/mlint.html) :copyright: - 检查 MATLAB 代码文件是否存在可能的问题.


<h2 id="nim">Nim</h2>

- [DrNim](https://nim-lang.org/docs/drnim.html) - DrNim 将 Nim 前端与 Z3 证明引擎相结合，以允许验证/验证用 Nim 编写的软件.
- [nimfmt](https://github.com/FedericoCeratto/nimfmt) - Nim code formatter / linter / style checker


<h2 id="ocaml">Ocaml</h2>

- [Sys](https://github.com/PLSysSec/sys)  :warning: - 用于查找（浏览器）代码中的错误的静态/符号工具. 它使用 LLVM AST 来查找诸如未初始化内存访问之类的错误.
- [VeriFast](https://github.com/verifast/verifast) - A tool for modular formal verification of correctness properties of single-threaded and multithreaded  C and Java programs annotated with preconditions and postconditions written in separation logic.  To express rich specifications, the programmer can define inductive datatypes,  primitive recursive pure functions over these datatypes, and abstract separation logic predicates.


<h2 id="php">PHP</h2>

- [churn-php](https://github.com/bmitch/churn-php) - 帮助发现重构的优秀候选者.
- [dephpend](https://github.com/mihaeu/dephpend) - 依赖分析工具.
- [deprecation-detector](https://github.com/sensiolabs-de/deprecation-detector) - 查找已弃用 (Symfony) 代码的用法.
- [deptrac](https://github.com/sensiolabs-de/deptrac) - Enforce rules for dependencies between software layers.
- [DesignPatternDetector](https://github.com/Halleck45/DesignPatternDetector) - Detection of design patterns in PHP code.
- [EasyCodingSt和ard](https://www.tomasvotruba.com/blog/2017/05/03/combine-power-of-php-code-sniffer-和-php-cs-fixer-in-3-lines) - Combine [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 和 [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).
- [Enlightn](https://www.laravel-enlightn.com/)  - 用于 Laravel 应用程序的静态和动态分析工具，它提供建议以提高 Laravel 应用程序的性能、安全性和代码可靠性. 包含 120 个自动检查.
- [exakat](https://www.exakat.io) - An automated code reviewing engine for PHP.
- [GrumPHP](https://github.com/phpro/grumphp) - 在每次提交时检查代码.
- [larastan](https://github.com/nunomaduro/larastan) - Adds static analysis to Laravel improving developer productivity and code quality. It is a wrapper around PHPStan.
- [Mondrian](http://trismegiste.github.io/Mondrian) :warning: - 一组使用图论的静态分析和重构工具.
- [Nitpick CI](https://nitpick-ci.com) :copyright: - 自动 PHP 代码审查.
- [parallel-lint](https://github.com/php-parallel-lint/PHP-Parallel-Lint) - This tool checks syntax of PHP files faster than serial check with a fancier output.
- [Parse](https://github.com/psecio/parse) - 静态安全扫描器.
- [pdepend](https://pdepend.org) - Calculates software metrics like cyclomatic complexity for PHP code.
- [phan](https://github.com/phan/phan/wiki) - 来自 etsy 的现代静态分析器.
- [PHP Architecture Tester](https://github.com/carlosas/phpat) - Easy to use architecture testing tool for PHP.
- [PHP Assumptions](https://github.com/rskuipers/php-assumptions) - Checks for weak assumptions.
- [PHP Coding Standards Fixer](https://cs.symfony.com) - 根据 PSR-1、PSR-2 和 Symfony 标准等标准修复您的代码.
- [PHP Insights](https://phpinsights.com) - Instant PHP quality checks from your console. Analysis of code quality and coding style as well as overview of code architecture and its complexity.
- [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-) - PHP 的静态代码分析器.
- [PHP Refactoring Browser](http://qafoolabs.github.io/php-refactoring-browser) - Refactoring helper.
- [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - Suggests a next version according to semantic versioning.
- [PHP-Parser](https://github.com/nikic/PHP-Parser) - 用 PHP 编写的 PHP 解析器.
- [php-speller](https://github.com/mekras/php-speller) - PHP 拼写检查库.
- [PHP-Token-Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) :warning: - 模拟 PHP 内部反射的库.
- [php7cc](https://github.com/sstalle/php7cc) :warning: - PHP 7 兼容性检查器.
- [php7mar](https://github.com/Alexia/php7mar) :warning: - 帮助开发人员将他们的代码快速移植到 PHP 7.
- [PHP_CodeSniffer](https://pear.php.net/package/PHP_CodeSniffer) - Detects violations of a defined set of coding standards.
- [phpca](https://github.com/wapmorgan/PhpCodeAnalyzer) :warning: - 查找非内置扩展的用法.
- [phpcpd](https://github.com/sebastianbergmann/phpcpd) - PHP 代码的复制/粘贴检测器.
- [phpdcd](https://github.com/sebastianbergmann/phpdcd) :warning: - Dead Code Detector (DCD) for PHP code.
- [PhpDependencyAnalysis](https://mamuz.github.io/PhpDependencyAnalysis) :warning: - 为项目构建依赖关系图.
- [PhpDeprecationDetector](https://github.com/wapmorgan/PhpDeprecationDetector)  - PHP 代码分析器可在较新的解释器版本中搜索已弃用功能的问题. 它发现已删除的对象（函数、变量、常量和 ini 指令）、不推荐使用的函数功能以及禁止使用的名称或技巧（例如，较新版本中的保留标识符）.
- [phpdoc-to-typehint](https://github.com/dunglas/phpdoc-to-typehint) :warning: - Add scalar type hints and return types to existing PHP projects using PHPDoc annotations.
- [phpDocumentor](https://www.phpdoc.org) - Analyzes PHP source code to generate documentation.
- [phploc](https://github.com/sebastianbergmann/phploc) - 用于快速测量 PHP 项目大小和分析结构的工具.
- [PHPMD](https://phpmd.org) - 查找代码中可能存在的错误.
- [PhpMetrics](http://www.phpmetrics.org) - Calculates and visualizes various code quality metrics.
- [phpmnd](https://github.com/povils/phpmnd) - 帮助检测幻数.
- [PHPQA](https://edgedesigncz.github.io/phpqa) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
- [phpqa - jakzal](https://github.com/jakzal/phpqa) - 在一个容器中提供多种 PHP 静态分析工具.
- [phpqa - jmolivas](https://github.com/jmolivas/phpqa) - PHPQA 多合一分析器 CLI 工具.
- [phpsa](https://github.com/ovr/phpsa) :warning: - PHP 的静态分析工具.
- [PHPStan](https://phpstan.org) - PHP Static Analysis Tool - discover bugs in your code without running it!
- [Progpilot](https://github.com/designsecurity/progpilot) - A static analysis tool for security purposes.
- [Psalm](https://psalm.dev) - Static analysis tool for finding type errors in PHP applications.
- [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) :warning: - 可视化指标和源代码.
- [Symfony Insight](https://insight.symfony.com/) :copyright: - Detect security risks, find bugs and provide actionable metrics for PHP projects.
- [Tuli](https://github.com/ircmaxell/Tuli) - A static analysis engine.
- [twig-lint](https://github.com/asm89/twig-lint) - twig-lint is a lint tool for your twig files.
- [WAP](https://securityonline.info/owasp-wap-web-application-protection-project) - 用于检测和纠正 PHP（4.0 或更高版本）Web 应用程序中的输入验证漏洞并通过结合静态分析和数据挖掘来预测误报的工具.


<h2 id="plsql">PL/SQL</h2>

- [ZPA](https://felipezorzo.com.br/zpa/) - Z PL/SQL Analyzer (ZPA) is an extensible code analyzer for PL/SQL and Oracle SQL. It can be integrated with SonarQube.


<h2 id="perl">Perl</h2>

- [Perl::Critic](https://metacpan.org/pod/Perl::Critic) - Critique Perl 源代码以获得最佳实践.


<h2 id="python">Python</h2>

- [bandit](https://bandit.readthedocs.io/en/latest) - A tool to find common security issues in Python code.
- [bellybutton](https://github.com/hchasestevens/bellybutton) - A linting engine supporting custom project-specific rules.
- [Black](https://black.readthedocs.io/en/stable) - 毫不妥协的 Python 代码格式化程序.
- [Bowler](https://pybowler.io/)  - 现代 Python 的安全代码重构.  Bowler 是一个重构工具，用于在语法树级别操作 Python. 它支持安全、大规模的代码修改，同时保证生成的代码可以编译和运行. 它提供了简单的命令行界面和 Python 中的流畅 API，用于在代码中生成复杂的代码修改.
- [ciocheck](https://github.com/ContinuumIO/ciocheck)  :warning: - Linter、格式化程序和测试套件助手. 作为 linter，它是 `pep8`、`pydocstyle`、`flake8` 和 `pylint` 的包装器.
- [cohesion](https://github.com/mschwager/cohesion) :warning: - 一个测量 Python 类凝聚力的工具.
- [Dlint](https://github.com/dlint-py/dlint) - 确保 Python 代码安全的工具.
- [fixit](https://pypi.org/project/fixit) - A framework for creating lint rules and corresponding auto-fixes for source code.
- [flake8](https://github.com/PyCQA/flake8) - `pyflakes`、`pycodestyle` 和 `mccabe` 的​​包装器.
- [InspectorTiger](https://github.com/thg-consulting/it)  :warning: - IT，Inspector Tiger，是一个现代的 python 代码审查工具/框架. 它带有一堆预定义的处理程序，可以警告您改进和可能的错误. 除了这些处理程序之外，您还可以编写自己的或使用社区处理程序.
- [jedi](https://jedi.readthedocs.io/en/latest) - Python 的自动完成/静态分析库.
- [linty fresh](https://github.com/lyft/linty_fresh) - Parse lint errors and report them to Github as comments on a pull request.
- [mccabe](https://pypi.org/project/mccabe) - 检查 McCabe 的复杂性.
- [multilint](https://github.com/adamchainz/multilint) :warning: - `flake8`、`isort` 和 `modernize` 的包装器.
- [mypy](http://www.mypy-lang.org) - 一个静态类型检查器，旨在结合鸭子类型和静态类型的优点，经常与 [MonkeyType](https://github.com/Instagram/MonkeyType).
- [prospector](https://github.com/PyCQA/prospector) - A wrapper around `pylint`, `pep8`, `mccabe` and others.
- [py-find-injection](https://github.com/uber/py-find-injection) :warning: - 在 Python 代码中查找 SQL 注入漏洞.
- [pyanalyze](https://pyanalyze.readthedocs.io/en/latest/)  - 一种以编程方式检测 Python 代码中常见错误的工具，例如对未定义变量的引用和类型错误. 它可以扩展以添加其他规则并执行特定于特定功能的检查.
- [PyCodeQual](https://pycodequ.al)  :copyright: - PyCodeQual 让您深入了解复杂性和错误风险. 它将自动审查添加到您的拉取请求中.
- [pycodestyle](https://pycodestyle.pycqa.org/en/latest) -（以前的 `pep8`）检查 Python 代码是否符合 PEP 8 中的一些样式约定.
- [pydocstyle](http://www.pydocstyle.org) - 检查是否符合 Python 文档字符串约定。
- [pyflakes](https://pypi.org/project/pyflakes) - Check Python source files for errors.
- [pylint](http://pylint.pycqa.org/en/latest)  - 查找编程错误，帮助执行编码标准并嗅探一些代码异味. 它还包括`pyreverse`（一个UML图生成器）和`symilar`（一个相似性检查器）.
- [pyre-check](https://pyre-check.org) - 用于大型 Python 代码库的快速、可扩展的类型检查器.
- [pyright](https://github.com/Microsoft/pyright) - Static type checker for Python, created to address gaps in existing tools like mypy.
- [pyroma](https://github.com/regebro/pyroma) - Rate how well a Python project complies with the best practices of the Python packaging ecosystem, and list issues that could be improved.
- [Pysa](https://pyre-check.org/docs/pysa-basics.html) - 基于 Facebook 的 pyre-check 的工具，用于识别通过污点分析识别的 Python 代码中的潜在安全问题.
- [PyT - Python Taint](https://github.com/python-security/pyt) :warning: - 用于检测 Python Web 应用程序中的安全漏洞的静态分析工具.
- [pytype](https://google.github.io/pytype) - A static type analyzer for Python code.
- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode) :warning: - Automated code review & repair. It helps you to keep track of issues and metrics in your software projects, and can be easily extended to support new types of analyses.
- [radon](https://radon.readthedocs.io/en/latest) - A Python tool that computes various metrics from the source code.
- [unimport](https://unimport.hakancelik.dev) - 用于查找和删除未使用的导入语句的 linter、格式化程序.
- [vulture](https://github.com/jendrikseipp/vulture) - Find unused classes, functions and variables in Python code.
- [wemake-python-styleguide](https://wemake-python-stylegui.de) - 有史以来最严格和最固执的python linter.
- [wily](https://github.com/tonybaloney/wily) - A command-line tool for archiving, exploring and graphing the complexity of Python source code.
- [xenon](https://xenon.readthedocs.io) - 使用监控代码复杂性 [`radon`](https://github.com/rubik/radon).


<h2 id="r">R</h2>

- [cyclocomp](https://github.com/MangoTheCat/cyclocomp) - 量化 R 函数/表达式的圈复杂度.
- [goodpractice](http://mangothecat.github.io/goodpractice) - Analyses the source code for R packages and provides best-practice recommendations.
- [lintr](https://github.com/jimhester/lintr) - Static Code Analysis for R.
- [styler](https://styler.r-lib.org) - R 源代码文件的格式化和 R 代码的漂亮打印.


<h2 id="ruby">Ruby</h2>

- [brakeman](https://brakemanscanner.org) - A static analysis security vulnerability scanner for Ruby on Rails applications.
- [bundler-audit](https://github.com/rubysec/bundler-audit) - Audit Gemfile.lock for gems with security vulnerabilities reported in [Ruby Advisory Database](https://github.com/rubysec/ruby-advisory-db).
- [cane](https://github.com/square/cane) :warning: - 代码质量阈值检查作为构建的一部分.
- [dawnscanner](https://github.com/thesp0nge/dawnscanner) - A static analysis security scanner for ruby written web applications. It supports Sinatra, Padrino and Ruby on Rails frameworks.
- [ERB Lint](https://github.com/Shopify/erb-lint) - 整理您的 ERB 或 HTML 文件
- [Fasterer](https://github.com/DamirSvrtan/fasterer) - Common Ruby idioms checker.
- [flay](https://ruby.sadi.st/Flay.html) - Flay analyzes code for structural similarities.
- [flog](https://ruby.sadi.st/Flog.html)  - Flog 在一个易于阅读的痛苦报告中报告最受折磨的代码. 分数越高，代码越痛苦.
- [Fukuzatsu](https://github.com/CoralineAda/fukuzatsu) - A tool for measuring code complexity in Ruby class files. Its analysis generates scores based on cyclomatic complexity algorithms with no added "opinions".
- [laser](https://github.com/michaeledgar/laser) :warning: - Static analysis and style linter for Ruby code.
- [pelusa](https://github.com/codegram/pelusa) - Static analysis Lint-type tool to improve your OO Ruby code.
- [quality](https://github.com/apiology/quality) :warning: - Runs quality checks on your code using community tools, and makes sure your numbers don't get any worse over time.
- [Querly](https://github.com/soutaro/querly) - 基于模式的 Ruby 检查工具.
- [Railroader](https://railroader.org) :warning: - An open source static analysis security vulnerability scanner for Ruby on Rails applications.
- [rails_best_practices](https://rails-bestpractices.com) - A code metric tool for Rails projects
- [reek](https://github.com/troessner/reek) - Ruby 的代码气味检测器.
- [RuboCop](https://docs.rubocop.org/rubocop) - A Ruby static code analyzer, based on the community Ruby style guide.
- [Rubrowser](https://github.com/blazeeboy/rubrowser) - Ruby 类交互式依赖图生成器.
- [ruby-lint](http://code.yorickpeterse.com/ruby-lint/latest) :warning: - Ruby 的静态代码分析.
- [rubycritic](https://github.com/whitesmith/rubycritic) - Ruby 代码质量报告员.
- [rufo](https://github.com/ruby-formatter/rufo) - An opinionated ruby formatter, intended to be used via the command line as a text-editor plugin, to autoformat files on save or on demand.
- [Saikuro](https://metricfu.github.io/Saikuro) :warning: - Ruby 圈复杂度分析器。
- [SandiMeter](https://rubygems.org/gems/sandi_meter) :warning: - 用于检查 Sandi Metz 规则的 Ruby 代码的静态分析工具.
- [Sorbet](https://sorbet.org) - 专为 Ruby 设计的快速、强大的类型检查器.
- [Standard Ruby](https://github.com/testdouble/standard) - Ruby 风格指南，带有 linter 和自动代码修复器
- [Steep](https://github.com/soutaro/steep) - Ruby 的渐进式打字.


<h2 id="rust">Rust</h2>

- [C2Rust](https://c2rust.com)  - C2Rust 帮助您将符合 C99 的代码迁移到 Rust. 翻译器（或转译器）生成不安全的 Rust 代码，这些代码与输入的 C 代码非常相似.
- [cargo udeps](https://github.com/est31/cargo-udeps) - Find unused dependencies in Cargo.toml. It either prints out a "unused crates" line listing the crates,  or it prints out a line saying that no crates were unused.
- [cargo-audit](https://rustsec.org) - Audit Cargo.lock for crates with security vulnerabilities reported to the [RustSec Advisory Database](https://github.com/RustSec/advisory-db/).
- [cargo-bloat](https://github.com/RazrFalcon/cargo-bloat)  - 找出在您的可执行文件中占用大部分空间的内容. 支持 ELF (Linux, BSD)、Mach-O (macOS) 和 PE (Windows) 二进制文件.
- [cargo-deny](https://embarkstudios.github.io/cargo-deny) - A cargo plugin for linting your dependencies. It can be used either as a command line too, a Rust crate, or a Github action for CI. It checks for valid license information, duplicate crates, security vulnerabilities, and more.
- [cargo-expand](https://github.com/dtolnay/cargo-expand) - Cargo subcommand to show result of macro expansion  and #[derive] expansion applied to the current crate.  This is a wrapper around a more verbose compiler command.
- [cargo-inspect](https://github.com/mre/cargo-inspect) - 检查没有语法糖的 Rust 代码，看看编译器在幕后做了什么.
- [cargo-spellcheck](https://github.com/drahnr/cargo-spellcheck) - 使用 hunspell (ready) 和 languagetool (preview) 检查所有文档的拼写和语法错误
- [clippy](https://rust-lang.github.io/rust-clippy) - 一个代码检查器，用于捕捉常见错误并改进您的 Rust 代码.
- [dylint](https://www.trailofbits.com/post/write-rust-lints-without-forking-clippy)  - 从动态库运行 Rust lints 的工具.  Dylint 使开发人员可以轻松维护自己的个人 lint 集合.
- [electrolysis](http://kha.github.io/electrolysis) :warning: - A tool for formally verifying Rust programs by transpiling them into definitions in the Lean theorem prover.
- [herbie](https://github.com/mcarton/rust-herbie-lint) :warning: - Adds warnings or errors to your crate when using a numerically unstable floating point expression.
- [linter-rust](https://github.com/AtomLinter/linter-rust) :warning: - 使用 rustc 和 cargo 在 Atom 中整理你的 Rust 文件.
- [MIRAI](https://github.com/facebookexperimental/MIRAI) - And abstract interpreter operating on Rust's mid-level intermediate language, and providing warnings based on taint analysis.
- [prae](https://github.com/teenjuna/prae) - Provides a convenient macro that allows you to generate type wrappers  that promise to always uphold arbitrary invariants that you specified. 
- [Prusti](https://www.pm.inf.ethz.ch/research/prusti.html)  - Rust 的静态验证器，基于 Viper 验证基础设施. 默认情况下，Prusti 通过证明诸如 unreachable!() 和 panic!() 之类的语句不可达来验证是否存在恐慌.
- [Rudra](https://github.com/sslab-gatech/Rudra) :copyright: - Rust Memory Safety & Undefined Behavior Detection. It is capable of analyzing single Rust packages as well as all the packages on crates.io.
- [Rust Language Server](https://github.com/rust-lang-nursery/rls) - 支持“goto 定义”、符号搜索、重新格式化和代码完成等功能，并启用重命名和重构.
- [rust-analyzer](https://rust-analyzer.github.io) - 支持“goto 定义”、类型推断、符号搜索、重新格式化和代码完成等功能，并启用重命名和重构.
- [rust-audit](https://github.com/Shnatsel/rust-audit) - Audit Rust binaries for known bugs or security vulnerabilities. This works by embedding data about the dependency tree (Cargo.lock) in JSON format into a dedicated linker section of the compiled executable.
- [rustfix](https://github.com/rust-lang/rustfix) - Read and apply the suggestions made by rustc (and third-party lints, like those offered by clippy).
- [rustfmt](https://github.com/rust-lang/rustfmt) - A tool for formatting Rust code according to style guidelines.
- [RustViz](https://github.com/rustviz/rustviz) - RustViz is a tool that generates visualizations  from simple Rust programs to assist users in better  understanding the Rust Lifetime and Borrowing mechanism. It generates SVG files with graphical indicators that integrate  with mdbook to render visualizations of data-flow in Rust programs.
- [warnalyzer](https://github.com/est31/warnalyzer) - 显示多箱 Rust 项目中未使用的代码


<h2 id="sql">SQL</h2>

- [dbcritic](https://github.com/channable/dbcritic) - dbcritic 发现数据库模式中的问题，例如表中缺少主键约束.
- [sqlcheck](https://github.com/jarulraj/sqlcheck) - Automatically identify anti-patterns in SQL queries.
- [SQLFluff](https://www.sqlfluff.com/) - Multiple dialect SQL linter and formatter.
- [sqlint](https://github.com/purcell/sqlint) - 简单的 SQL 短绒.
- [squawk](https://squawkhq.com) - Linter for PostgreSQL, focused on migrations. Prevents unexpected downtime caused by database migrations and encourages best practices around Postgres schemas and SQL.
- [tsqllint](https://github.com/tsqllint/tsqllint) - T-SQL-specific linter.
- [TSqlRules](https://github.com/ashleyglee/TSqlRules) :warning: - TSQL Static Code Analysis Rules for SQL Server.
- [Visual Expert](https://www.visual-expert.com) :copyright: - PowerBuilder、Oracle 和 SQL Server 的代码分析探索、分析和记录代码 


<h2 id="scala">梯子</h2>

- [linter](https://github.com/HairyFotr/linter) :warning: - Linter is a Scala static analysis compiler plugin which adds compile-time checks for various possible bugs, inefficiencies, and style problems.
- [Scalastyle](http://www.scalastyle.org) - Scalastyle examines your Scala code and indicates potential problems with it.
- [scapegoat](https://github.com/sksamuel/scapegoat) - Scala compiler plugin for static code analysis.
- [WartRemover](https://www.wartremover.org) - 一个灵活的 Scala 代码检查工具.


<h2 id="shell">壳</h2>

- [bashate](https://github.com/openstack/bashate)  - bash 程序的代码样式强制执行. 输出格式旨在遵循 pycodestyle (pep8) 默认输出格式.
- [i-Code CNES for Shell](https://github.com/lequal/i-CodeCNES) :warning: - An open source static code analysis tool for Shell and Fortran (77 and 90).
- [kmdr](https://kmdr.sh) - CLI tool for learning commands from your terminal. kmdr delivers a break down of commands with every attribute explained.
- [sh](https://pkg.go.dev/mvdan.cc/sh/v3)  - 支持 bash 的 shell 解析器、格式化程序和解释器； 包括 shfmt
- [shellcheck](https://www.shellcheck.net) - ShellCheck, a static analysis tool that gives warnings and suggestions for bash/sh shell scripts.
- [shellharden](https://github.com/anordal/shellharden) - A syntax highlighter and a tool to semi-automate the rewriting of scripts to ShellCheck conformance, mainly focused on quoting.


<h2 id="swift">迅速</h2>

- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - 用于重新格式化 Swift 代码的库和命令行格式化工具.
- [SwiftLint](https://realm.github.io/SwiftLint) - A tool to enforce Swift style and conventions.
- [Tailor](https://sleekbyte.github.io/tailor) :warning: - 用 Apple 的 Swift 编程语言编写的源代码的静态分析和 lint 工具.


<h2 id="tcl">Tcl</h2>

- [Frink](http://catless.ncl.ac.uk/Programs/Frink) - A Tcl formatting and static check program (can prettify the program, minimise, obfuscate or just sanity check it).
- [Nagelfar](https://sourceforge.net/projects/nagelfar) - Tcl 的静态语法检查器.
- [tclchecker](https://github.com/ActiveState/tdk/blob/master/docs/3.0/TDK_3.0_Checker.txt) - A static syntax analysis module (as part of [TDK](https://github.com/ActiveState/tdk)).


<h2 id="typescript">TypeScript</h2>

- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) - Linter for Angular projects
- [Codelyzer](http://codelyzer.com) - A set of tslint rules for static code analysis of Angular 2 TypeScript projects.
- [tslint-clean-code](https://www.npmjs.com/package/tslint-clean-code) - A set of TSLint rules inspired by the Clean Code handbook.
- [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib) :warning: - 一组 tslint 规则，用于对 Microsoft 维护的 TypeScript 项目进行静态代码分析.
- [TypeScript Call Graph](https://github.com/whyboris/TypeScript-Call-Graph) - CLI 从您的 TypeScript 文件生成函数和调用的交互式图表
- [TypeScript ESLint](https://github.com/typescript-eslint/typescript-eslint) - TypeScript language extension for eslint.


<h2 id="vbscript">VBScript</h2>

- [Test Design Studio](http://patterson-consulting.net/tds) :copyright: - A full IDE with static code analysis for Micro Focus Unified Functional Testing VBScript-based automated tests.


<h2 id="verilog">Verilog/SystemVerilog</h2>

- [Icarus Verilog](https://github.com/steveicarus/iverilog) - 一个 Verilog 模拟和综合工具，通过将 IEEE-1364 Verilog 编写的源代码编译成某种目标格式来运行
- [svls](https://github.com/dalance/svls) - A Language Server Protocol implementation for Verilog and SystemVerilog, including lint capabilities.
- [verible-linter-action](https://github.com/chipsalliance/verible-linter-action) - Automatic SystemVerilog linting in github actions with the help of Verible Used to lint Verilog and SystemVerilog source files and comment erroneous lines  of code in Pull Requests automatically.
- [Verilator](https://www.veripool.org/verilator)  - 将 Verilog 转换为 C++ 或 SystemC 中的周期精确行为模型的工具. 执行 lint 代码质量检查.
- [vscode-verilog-hdl-support](https://github.com/mshr-h/vscode-verilog-hdl-support) - Verilog HDL/SystemVerilog/Bluespec SystemVerilog support for VS Code. Provides syntax highlighting and Linting support from Icarus Verilog, Vivado Logical Simulation, Modelsim and Verilator


<h2 id="vim-script">Vim Script</h2>

- [vint](https://github.com/Kuniwak/vint) :warning: - 由 Python 实现的快速且高度可扩展的 Vim 脚本语言 Lint.


## Multiple languages

- [ale](https://github.com/w0rp/ale) - Asynchronous Lint Engine for Vim and NeoVim with support for many languages.
- [Android Studio](https://developer.android.com/studio) - Based on IntelliJ IDEA, and comes bundled with tools for Android including Android Lint.
- [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) :copyright: - Static analysis for C/C++/C#, PHP and Java.
- [Application Inspector](https://www.ptsecurity.com/ww-en/products/ai) :copyright: - Commercial Static Code Analysis which generates exploits to verify vulnerabilities.
- [ApplicationInspector](https://github.com/microsoft/ApplicationInspector) - 为特征检测创建超过 400 种规则模式的报告（例如，在应用程序中使用加密或版本控制）.
- [APPscreener](https://solarappscreener.com) :copyright: - Static code analysis for binary and source code - Java/Scala, PHP, Javascript, C#, PL/SQL, Python, T-SQL, C/C++, ObjectiveC/Swift, Visual Basic 6.0, Ruby, Delphi, ABAP, HTML5 and Solidity.
- [ArchUnit](https://www.archunit.org) - Unit test your Java or Kotlin architecture.
- [Atom-Beautify](https://atom.io/packages/atom-beautify) :warning: - Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom editor.
- [Axivion Bauhaus Suite](https://www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: - Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95.
- [Better Code Hub](https://bettercodehub.com) :copyright: - Better Code Hub checks your GitHub codebase against 10 engineering guidelines devised by the authority in software quality, Software Improvement Group.
- [CAST Highlight](https://www.castsoftware.com/products/highlight) :copyright: - Commercial Static Code Analysis which runs locally, but uploads the results to its cloud for presentation.
- [Checkmarx CxSAST](https://www.checkmarx.com/products/static-application-security-testing) :copyright: - 不需要预编译的商业静态代码分析.
- [ClassGraph](https://github.com/classgraph/classgraph) - A classpath and module path scanner for querying or visualizing class metadata or class relatedness.
- [Clayton](https://www.getclayton.com/)  :copyright: - Salesforce 的 AI 驱动的代码审查. 实时保护您的开发、执行最佳实践并控制您的技术债务.
- [coala](https://coala.io) - 用于创建代码分析的语言独立框架 - 支持 [over 60 languages](https://coala.io/languages) 默认情况下。
- [Cobra](http://spinroot.com/cobra) :copyright: - NASA 喷气推进实验室的结构源代码分析器.
- [Codacy](https://www.codacy.com) :copyright: - 代码分析以更快地发布更好的代码.
- [Code Intelligence](https://www.code-intelligence.com) :copyright: - 与 CI/CD 无关的 DevSecOps 平台，它结合了行业领先的 fuzzing 引擎，用于查找错误和可视化代码覆盖率
- [Codeac](https://www.codeac.io/?ref=awesome-static-analysis)  :copyright: - 自动代码审查工具与 GitHub、Bitbucket 和 GitLab 集成（甚至是自托管的）. 适用于 JavaScript、TypeScript、Python、Ruby、Go、PHP、Java、Docker 等.  （开源免费）
- [codeburner](http://groupon.github.io/codeburner) :warning: - 提供统一的界面来对发现的问题进行排序和处理.
- [codechecker](https://codechecker.readthedocs.io/en/latest) - A defect database and viewer extension for the Clang Static Analyzer with web GUI.
- [CodeFactor](https://codefactor.io) :copyright: - GitHub 或 BitBucket 上 repos 的自动代码分析.
- [CodeFlow](https://www.getcodeflow.com) :copyright: - Automated code analysis tool to deal with technical depth. Integrates with Bitbucket and Gitlab. (free for Open Source Projects)
- [CodeIt.Right](https://submain.com/products/codeit.right.aspx) :copyright: - CodeIt.Right™ 提供了一种快速、自动化的方式来确保您的源代码符合（您的）预定义的设计和样式指南以及最佳编码实践.
- [CodePatrol](https://cyber-security.claranet.fr/en/codepatrol) :copyright: - Automated SAST code reviews driven by security, supports 15+ languages and includes security training.
- [codeql](https://github.com/github/codeql) - 深度代码分析 - 支持 VSCode 插件的多种语言的语义查询和数据流.
- [Coderrect](https://coderrect.com/)  :copyright: - 用于多线程软件的高级静态分析器. 支持 OpenMP、Pthreads、std::thread 和 GPU/CUDA.
- [CodeRush](https://www.devexpress.com/products/coderush) :copyright: - 在 Visual Studio 2015 及更高版本中使用 Roslyn 引擎的代码创建、调试、导航、重构、分析和可视化工具.
- [CodeScan](https://www.codescan.io/) :copyright: - Code Quality and Security for Salesforce Developers. Made exclusively for the Salesforce platform, CodeScan’s code analysis solutions provide you with total visibility into your code health.
- [CodeScene](https://codescene.com) :copyright: - CodeScene is a quality visualization tool for software. Prioritize technical debt, detect delivery risks, and measure organizational aspects. Fully automated.
- [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) :copyright: - Advanced, whole program, deep path, static analysis of C, C++, Java and C# with easy-to-understand explanations and code and path visualization.
- [Codiga](https://www.codiga.io) :copyright: - 支持 12 种以上语言的自动代码审查和技术债务管理平台.
- [Corrode](https://github.com/jameysharp/corrode) :warning: - Semi-automatic translation from C to Rust. Could reveal bugs in the original implementation by showing Rust compiler warnings and errors. Superseded by C2Rust.
- [Coverity](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - Synopsys Coverity supports 20 languages and over 70 frameworks including Ruby on rails, Scala, PHP, Python, JavaScript, TypeScript, Java, Fortran, C, C++, C#, VB.NET.
- [cqc](https://github.com/xcatliu/cqc) :warning: - Check your code quality for js, jsx, vue, css, less, scss, sass and styl files.
- [DeepCode](https://www.deepcode.ai)  :copyright: - DeepCode 基于 AI 发现错误、安全漏洞、性能和 API 问题.  DeepCode 的分析速度使我们能够实时分析您的代码并在您点击 IDE 中的保存按钮时提供结果. 支持的语言有 Java、C/C++、JavaScript、Python 和 TypeScript. 与 GitHub、BitBucket 和 Gitlab 集成.
- [DeepSource](https://deepsource.io) :copyright: - In-depth static analysis to find issues in verticals of bug risks, security, anti-patterns, performance, documentation and style. Native integrations with GitHub, GitLab and Bitbucket. Less than 5% false positives.
- [Depends](https://github.com/multilang-depends/depends) - 分析 Java、C/C++、Ruby 的代码元素的综合依赖关系.
- [DevSkim](https://github.com/microsoft/devskim) - Regex-based static analysis tool for Visual Studio, VS Code, and Sublime Text - C/C++, C#, PHP, ASP, Python, Ruby, Java, and others.
- [Embold](https://embold.io) :copyright: - Intelligent software analytics platform that identifies design issues, code issues, duplication and metrics. Supports Java, C, C++, C#, JavaScript, TypeScript, Python, Go, Kotlin and more.
- [ESLint](https://github.com/eslint/eslint) - 一个 JS 的可扩展 linter，遵循 ECMAScript 标准.
- [Find Security Bugs](https://find-sec-bugs.github.io) - The SpotBugs plugin for security audits of Java web applications and Android applications. (Also work with Kotlin, Groovy and Scala projects)
- [Fortify](https://software.microfocus.com/en-us/products/static-code-analysis-sast/overview) :copyright: - A commercial static analysis platform that supports the scanning of C/C++, C#, VB.NET, VB6, ABAP/BSP, ActionScript, Apex, ASP.NET, Classic ASP, VB Script, Cobol, ColdFusion, HTML, Java, JS, JSP, MXML/Flex, Objective-C, PHP, PL/SQL, T-SQL, Python (2.6, 2.7), Ruby (1.9.3), Swift, Scala, VB, and XML.
- [Goodcheck](https://sider.github.io/goodcheck) - Regexp based customizable linter.
- [goone](https://github.com/masibw/goone) :warning: - 在 go 代码中查找 N+1 个查询（for 循环中的 SQL 调用）
- [graudit](http://www.justanotherhacker.com) - Grep 粗略审计——源代码审计工具.
- [HCL AppScan Source](https://www.hcltechsw.com/products/appscan) :copyright: - Commercial Static Code Analysis.
- [Hopper](https://github.com/cuplv/hopper) :warning: - A static analysis tool written in scala for languages that run on JVM.
- [Hound CI](https://houndci.com)  - 对 GitHub 拉取请求中的样式违规的评论. 支持 Coffeescript、Go、HAML、JavaScript、Ruby、SCSS 和 Swift.
- [imhotep](https://github.com/justinabrahms/imhotep) - Comment on commits coming into your repository and check for syntactic errors and general lint warnings.
- [include-gardener](https://github.com/feddischson/include_gardener) :warning: - A multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
- [Infer](https://fbinfer.com) - Java、C 和 Objective-C 的静态分析器
- [InsiderSec](https://insidersec.io) :warning: - A open source Static Application Security Testing tool (SAST) written in GoLang for Java (Maven and Android), Kotlin (Android), Swift (iOS), .NET Full Framework, C# and Javascript (Node.js).
- [Kiuwan](https://www.kiuwan.com/code-security-sast) :copyright: - Identify and remediate cyber threats in a blazingly fast, collaborative environment, with seamless integration in your SDLC. Python, C\C++, Java, C#, PHP and more.
- [Klocwork](https://www.perforce.com/products/klocwork) :copyright: - Quality and Security Static analysis for C/C++, Java and C#.
- [LGTM](https://lgtm.com/)  :copyright: - 使用对源代码的查询来查找安全漏洞、变体和关键代码质量问题. 自动 PR 代码审查； 免费用于开源. 以前的semme.
- [LGTM.com](https://lgtm.com) :copyright: - Deep code analysis for GitHub and Bitbucket to find security vulnerabilities and critical code quality issues (using Semmle QL). Automatic code review for pull requests; free for public repositories.
- [lizard](https://github.com/terryyin/lizard)  - Lizard 是一个可扩展的圈复杂度分析器，适用于包括 C/C++ 在内的许多编程语言（不需要所有头文件或 Java 导入）. 它还进行复制粘贴检测（代码克隆检测/代码重复检测）和许多其他形式的静态代码分析. 计算不带注释的代码行数、CCN（圈复杂度数）、函数的标记数、函数的参数数.
- [Mega-Linter](https://nvuillam.github.io/mega-linter/) - Mega-Linter can handle any type of project thanks to its 70+ embedded Linters,
 its advanced reporting, runnable on any CI system or locally,
 通过辅助安装和配置，能够应用格式化和修复
- [oclint](http://oclint.org) - 一种静态源代码分析工具，用于提高 C、C++ 和 Objective-C 的质量并减少缺陷.
- [ocular](https://www.shiftleft.io/ocular/)  :copyright: - 使代码审计员和安全团队能够以交互方式调查他们独特的代码库，以发现传统 SAST 无法找到的业务逻辑缺陷和技术漏洞. 这是通过使分析师能够编写自己的自定义查询来完成的. 可以找到硬编码的秘密、身份验证问题和恶意代码，如 rootkit 和后门.
- [Offensive 360](https://offensive360.com/) :copyright: - Commercial Static Code Analysis system doesn't require building the source code or pre-compilation.
- [parasoft](https://www.parasoft.com/)  :copyright: - 用于单元、API 和 Web UI 测试的自动化软件测试解决方案. 符合 MISRA、OWASP 等.
- [pfff](https://github.com/facebookarchive/pfff/wiki/Main) - Facebook 用于多种语言的代码分析、可视化或保留样式的源转换工具.
- [PMD](https://pmd.github.io) - 适用于 Java、Salesforce Apex、Javascript、PLSQL、XML、XSL 等的源代码分析器.
- [pre-commit](https://pre-commit.com) - 用于管理和维护多语言预提交挂钩的框架.
- [Prettier](https://prettier.io) - 自以为是的代码格式化程序.
- [Pronto](https://github.com/prontolabs/pronto)  - 对您的更改进行快速自动代码审查. 支持 40 多种不同语言的运行器，包括 Clang、Elixir、JavaScript、PHP、Ruby 等.
- [PT.PM](https://github.com/PositiveTechnologies/PT.PM) :warning: - An engine for searching patterns in the source code, based on Unified AST or UST. At present time C#, Java, PHP, PL/SQL, T-SQL, and JavaScript are supported. Patterns can be described within the code or using a DSL.
- [PVS-Studio](https://pvs-studio.com) :copyright: - A ([conditionally free](https://pvs-studio.com/en/order/open-source-license) for FOSS and individual developers) static analysis of C, C++, C# and Java code. For advertising purposes [you can propose a large FOSS project for analysis by PVS employees](https://github.com/viva64/pvs-studio-check-list). Supports CWE mapping, MISRA and CERT coding standards.
- [pylama](https://klen.github.io/pylama/) - Code audit tool for Python and JavaScript. Wraps pycodestyle, pydocstyle, PyFlakes, Mccabe, Pylint, and more
- [Refactoring Essentials](https://marketplace.visualstudio.com/items?itemName=SharpDevelopTeam.RefactoringEssentialsforVisualStudio) :warning: - The free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers.
- [relint](https://github.com/codingjoe/relint) - 允许您使用正则表达式 (RegEx) 编写自定义规则的静态文件 linter.
- [ReSharper](https://www.jetbrains.com/resharper) :copyright: - Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies.
- [RIPS](https://www.ripstech.com) :copyright: - 针对 PHP 脚本漏洞的静态源代码分析器.
- [Rome](https://rome.tools/) - Rome 是一个 linter、编译器、捆绑器和 [more](https://rome.tools/#development-status) for JavaScript, TypeScript, JSON, HTML, Markdown, and CSS.
- [Roslyn Analyzers](https://github.com/dotnet/roslyn-analyzers) - Roslyn-based implementation of FxCop analyzers.
- [Roslyn Security Guard](https://security-code-scan.github.io) - 专注于识别潜在漏洞的项目，例如 SQL 注入、跨站点脚本 (XSS)、CSRF、加密弱点、硬编码密码等等.
- [Scrutinizer](https://scrutinizer-ci.com) :copyright: - A proprietary code quality checker that can be integrated with GitHub.
- [Security Code Scan](https://security-code-scan.github.io) - Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc. Integrates into Visual Studio 2015 and newer. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
- [Semgrep](https://semgrep.dev)  - 一个快速、开源的静态分析工具，用于在编辑器、提交和 CI 时发现错误并执行代码标准. 它的规则看起来像你已经编写的代码； 没有抽象语法树或正则表达式摔跤. 支持 17 多种语言.
- [ShiftLeft](https://www.shiftleft.io) :copyright: - Identify vulnerabilities that are unique to your code base before they reach production. Leverages the Code Property Graph (CPG) to run its analyses concurrently in a single graph of graphs. Automatically finds business logic flaws in dev like hardcoded secrets and logic bombs
- [ShiftLeft Scan](https://slscan.io) - Scan is a free open-source DevSecOps platform for detecting security issues in source code and dependencies. It supports a broad range of languages and CI/CD pipelines.
- [shipshape](https://github.com/google/shipshape) :warning: - Static program analysis platform that allows custom analyzers to plug in through a common interface.
- [Sider](https://sider.review) :copyright: - An automated code reviewing tool. Improving developers' productivity.
- [Similarity Tester](https://dickgrune.com/Programs/similarity_tester/) - A tool that finds similarities between or within files to support you encountering DRY principle violations.
- [Snyk](https://snyk.io) :copyright: - node.js 应用程序依赖项的漏洞扫描程序（开源项目免费）.
- [SonarCloud](https://sonarcloud.io)  :copyright: - 多语言基于云的静态代码分析. 历史、趋势、安全热点、拉取请求分析等. 开源免费.
- [SonarLint for Visual Studio](https://vs.sonarlint.org) - SonarLint 是 Visual Studio 2015 和 2017 的扩展，可为开发人员提供有关注入 .NET 代码的新错误和质量问题的即时反馈.
- [SonarQube](http://www.sonarqube.org) - SonarQube is an open platform to manage code quality.
- [Sonatype](https://www.sonatype.com) :copyright: - Reports known vulnerabilities in common dependencies and recommends updated packages to minimize breaking changes
- [Soto Platform](https://www.hello2morrow.com/products/sotograph) :copyright: - Suite of static analysis tools consisting of the three components Sotoarc (Architecture Analysis), Sotograph (Quality Analysis), and Sotoreport (Quality report). Helps find differences between architecture and implementation, interface violations (e.g. external access of private parts of subsystems, detection of all classes, files, packages and subsystems which are strongly coupled by cyclical relationships and more. The Sotograph product family runs on Windows and Linux. 
- [SourceMeter](https://www.sourcemeter.com/) :copyright: - Static Code Analysis for C/C++, Java, C#, Python, and RPG III and RPG IV versions (including free-form).
- [sqlvet](https://github.com/houqp/sqlvet)  - 对 Go 代码库中的原始 SQL 查询执行静态分析，以发现潜在的运行时错误. 它检查 SQL 语法错误，识别可能导致 SQL 注入的不安全查询，确保列计数与 INSERT 语句中的值计数匹配，并验证表名和列名.
- [Super-Linter](https://github.com/github/super-linter) - 多个 linter 的组合以作为 GitHub Action 安装.
- [Synopsys](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - A commercial static analysis platform that allows for scanning of multiple languages (C/C++, Android, C#, Java, JS, PHP, Python, Node.JS, Ruby, Fortran, and Swift).
- [Teamscale](https://www.cqse.eu/en/teamscale/overview/)  :copyright: - 支持超过 25 种语言和直接 IDE 集成的静态和动态分析工具. 可根据要求免费托管开源项目. 提供免费的学术许可证.
- [todocheck](https://github.com/preslavmihaylov/todocheck) - 用于将带注释的 TODO 与您的问题跟踪器集成的 Linter
- [trivy](https://github.com/aquasecurity/trivy) - A Simple and Comprehensive Vulnerability Scanner for Containers and other Artifacts, Suitable for CI. Trivy detects vulnerabilities of OS packages (Alpine, RHEL, CentOS, etc.) and application dependencies (Bundler, Composer, npm, yarn, etc.). Checks containers and filesystems.

- [trunk](https://trunk.io)  :copyright: - 现代存储库包含许多技术，每种技术都有自己的一组 linter. 凭借 30 多个 linter 和计数，Trunk 可以非常简单地为您的所有存储库识别、安装、配置和运行正确的 linter、静态分析器和格式化程序.
- [TscanCode](https://github.com/Tencent/TscanCode) - A fast and accurate static analysis solution for C/C++, C#, Lua codes provided by Tencent. Using GPLv3 license.
- [Undebt](https://github.com/Yelp/undebt) - 独立于语言的工具，用于基于简单模式定义的大规模、自动、可编程重构.
- [Understand](https://www.scitools.com) :copyright: - 代码可视化工具，为 Ada、VHDL 等提供代码分析、标准测试、度量、图形、依赖性分析等.
- [Unibeautify](https://unibeautify.com) - Universal code beautifier with a GitHub app. Supports HTML, CSS, JavaScript, TypeScript, JSX, Vue, C++, Go, Objective-C, Java, Python, PHP, GraphQL, Markdown, and more.
- [Upsource](https://www.jetbrains.com/upsource) :copyright: - Code review tool with static code analysis and code-aware navigation for Java, PHP, JavaScript and Kotlin.
- [Veracode](http://www.veracode.com/products/static-analysis-sast/static-code-analysis)  :copyright: - 在不需要源代码的情况下查找二进制文件和字节码中的缺陷. 支持所有主要编程语言：Java、.NET、JavaScript、Swift、Objective-C、C、C++ 等.
- [Viezly](https://viezly.com) :copyright: - Code review tool with dependency diagrams. Improve your team's code reviews with better navigation and code analysis
- [WALA](https://github.com/wala/WALA) - Static analysis capabilities for Java bytecode and related languages and for JavaScript.
- [weggli](https://github.com/googleprojectzero/weggli) - A fast and robust semantic search tool for C and C++ codebases. It is designed to help security researchers identify interesting functionality in large codebases.
- [WhiteHat Application Security Platform](https://www.whitehatsec.com/platform/static-application-security-testing) :copyright: - WhiteHat Scout (for Developers) combined with WhiteHat Sentinel Source (for Operations) supporting WhiteHat Top 40 and OWASP Top 10.
- [Wotan](https://github.com/fimbullinter/wotan) - Pluggable TypeScript and JavaScript linter.
- [XCode](https://developer.apple.com/xcode) :copyright: - XCode 为 [Clang's](http://clang-analyzer.llvm.org/xcode.html) static code analyzer (C/C++, Obj-C).
- [🐊Putout](https://github.com/coderaiser/putout) - Pluggable and configurable code transformer with built-in eslint, babel plugins support for js, jsx typescript, flow, markdown, yaml and json.


## Other



<h2 id="angular">Angular</h2>

- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) - Linter for Angular projects


<h2 id="ansible">Ansible</h2>

- [kics](https://kics.io/) - Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible


<h2 id="arm">Azure 资源管理器</h2>

- [AzSK](https://azsk.azurewebsites.net/)  - 适用于 Azure (AzSK) 的安全 DevOps 工具包在基础架构即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础架构错误配置. 通过 ARM 支持 Azure.


<h2 id="binary">Binaries</h2>

- [angr](https://github.com/angr/angr) - Binary code analysis tool that also supports symbolic execution.
- [binbloom](https://github.com/quarkslab/binbloom) - Analyzes a raw binary firmware and determines features like endianness or the loading address.  The tool is compatible with all architectures.
Loading address: binbloom can parse a raw binary firmware and determine its loading address. Endianness: binbloom can use heuristics to determine the endianness of a firmware. UDS Database: binbloom can parse a raw binary firmware and check if it contains an array containing UDS command IDs.
- [BinSkim](https://github.com/Microsoft/binskim) - A binary static analysis tool that provides security and correctness results for Windows portable executables.
- [Black Duck](https://www.blackducksoftware.com) :copyright: - 分析可重用代码、必要许可证和潜在安全方面的源代码和二进制文件的工具.
- [bloaty](https://github.com/google/bloaty) - Ever wondered what's making your binary big? Bloaty McBloatface will show you a size profile of the binary so you can understand what's taking up space inside. Bloaty performs a deep analysis of the binary. Using custom ELF, DWARF, and Mach-O parsers,  Bloaty aims to accurately attribute every byte of the binary to the symbol or compileunit that produced it.  It will even disassemble the binary looking for references to anonymous data. F
- [cargo-bloat](https://github.com/RazrFalcon/cargo-bloat)  - 找出在您的可执行文件中占用大部分空间的内容. 支持 ELF (Linux, BSD)、Mach-O (macOS) 和 PE (Windows) 二进制文件.
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) - cwe_checker 在二进制可执行文件中发现易受攻击的模式.
- [Ghidra](https://ghidra-sre.org) - A software reverse engineering (SRE) suite of tools developed by NSA's Research Directorate in support of the Cybersecurity mission
- [IDA Free](https://www.hex-rays.com/products/ida/support/download_freeware) :copyright: - Binary code analysis tool.
- [Jakstab](https://github.com/jkinder/jakstab) - Jakstab 是一个基于抽象解释的集成反汇编和静态分析框架，用于设计对可执行文件的分析并恢复可靠的控制流图.
- [JEB Decompiler](https://www.pnfsoftware.com/) :copyright: - Decompile and debug binary code. Break down and analyze document files. Android Dalvik, MIPS, ARM, Intel x86, Java, WebAssembly & Ethereum Decompilers.
- [Manalyze](https://github.com/JusticeRage/Manalyze) - 静态分析器，用于检查可移植可执行文件中的恶意内容.
- [mcsema](https://github.com/lifting-bits/mcsema)  - 用于将 x86、amd64、aarch64、sparc32 和 sparc64 程序二进制文件提升到 LLVM 位码的框架. 它将可执行二进制文件从本机机器代码转换（“提升”）为 LLVM 位码，这对于执行程序分析方法非常有用.
- [Nauz File Detector](https://github.com/horsicq/Nauz-File-Detector) - Static Linker/Compiler/Tool detector for Windows, Linux and MacOS.
- [Twiggy](https://rustwasm.github.io/twiggy)  - 分析二进制文件的调用图以分析代码大小. 目标是缩小 wasm 二进制大小.
- [VMware chap](https://github.com/vmware/chap) - chap analyzes un-instrumented ELF core files for leaks, memory growth, and corruption.  It is sufficiently reliable that it can be used in automation to catch leaks before  they are committed. As an interactive tool, it helps explain memory growth,  can identify some forms of corruption, and supplements a debugger  by giving the status of various memory locations. 
- [zydis](https://zydis.re) - Fast and lightweight x86/x86-64 disassembler library


<h2 id="buildtool">构建工具</h2>

- [checkmake](https://github.com/mrtazz/checkmake) - 用于生成文件的 Linter / Analyzer.
- [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) - A verifier for FreeBSD and DragonFlyBSD port directories.


<h2 id="css">CSS/SASS/SCSS</h2>

- [CSS Stats](https://cssstats.com) - 样式表上可能有趣的统计数据.
- [CSScomb](https://github.com/csscomb/csscomb.js)  - CSS 的编码样式格式化程序. 支持自己的配置，使样式表美观一致.
- [CSSLint](http://csslint.net) - 进行基本语法检查并发现有问题的模式或效率低下的迹象.
- [GraphMyCSS.com](https://graphmycss.com) - CSS 特异性图生成器.
- [Nu Html Checker](https://validator.github.io/validator/) - 帮助您发现 HTML/CSS/SVG 中的问题
- [Parker](https://github.com/katiefenn/parker) :warning: - Stylesheet analysis tool.
- [PostCSS](https://postcss.org)  - 使用 JS 插件转换样式的工具. 这些插件可以 lint 你的 CSS，支持变量和 mixins，转换未来的 CSS 语法，内联图像等等.
- [Project Wallace CSS Analyzer](https://www.projectwallace.com) - Analytics for CSS, part of [Project Wallace](https://www.projectwallace.com).
- [sass-lint](https://github.com/sasstools/sass-lint) :warning: - A Node-only Sass linter for both sass and scss syntax.
- [scsslint](https://github.com/brigade/scss-lint) - SCSS 文件的 Linter.
- [Specificity Graph](https://jonassebastianohlsson.com/specificity-graph) - CSS 特异性图生成器.
- [Stylelint](http://stylelint.io) - Linter for SCSS/CSS files.


<h2 id="configfile">Config Files</h2>

- [dotenv-linter](https://dotenv-linter.readthedocs.io/en/latest) - Linting dotenv files like a charm.
- [dotenv-linter (Rust)](https://dotenv-linter.github.io/#/)  - 用于 .env 文件的闪电般快速的 linter. 用锈写
- [gixy](https://github.com/yandex/gixy) :warning: - A tool to analyze Nginx configuration. The main goal is to prevent misconfiguration and automate flaw detection.


<h2 id="configmanagement">配置管理</h2>

- [ansible-lint](https://docs.ansible.com/ansible-lint) - Checks playbooks for practices and behaviour that could potentially be improved.
- [AWS CloudFormation Guard](https://github.com/aws-cloudformation/cloudformation-guard) - Check local CloudFormation templates against policy-as-code rules  and generate rules from existing templates.
- [AzSK](https://azsk.azurewebsites.net/)  - 适用于 Azure (AzSK) 的安全 DevOps 工具包在基础架构即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础架构错误配置. 通过 ARM 支持 Azure.
- [cfn-lint](https://github.com/awslabs/cfn-python-lint) - AWS 实验室 CloudFormation 短绒.
- [cfn_nag](https://github.com/stelligent/cfn_nag) - A linter for AWS CloudFormation templates.
- [chart-testing](https://github.com/helm/chart-testing) - ct is the the tool for testing Helm charts.  It is meant to be used for linting and testing pull requests.  It automatically detects charts changed against the target branch.
- [checkov](https://www.checkov.io) - Terraform 文件的静态分析工具 (tf&gt;=v0.12)，防止构建时云配置错误.
- [clusterlint](https://github.com/digitalocean/clusterlint)  - Clusterlint 查询实时 Kubernetes 集群的资源，对这些资源执行常见的和特定于平台的检查，并向集群操作员提供可操作的反馈. 它是一种在外部运行的非侵入性工具.  Clusterlint 不会改变资源配置.
- [cookstyle](https://docs.chef.io/cookstyle.html) - Cookstyle 是一个基于 RuboCop Ruby linting 工具的 linting 工具，用于 Chef 食谱.
- [Datree](https://datree.io/) - 一个 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及您组织的政策来防止 Kubernetes 错误配置
- [foodcritic](http://www.foodcritic.io) - 检查 Chef 食谱中常见问题的 lint 工具.
- [kics](https://kics.io/) - Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible
- [kube-lint](https://github.com/viglesiasce/kube-lint)  - 具有可定制规则集的 Kubernetes 资源的 linter. 您定义了一个要针对您的资源验证的规则列表，kube-lint 将根据它们评估这些规则.
- [kube-linter](https://github.com/stackrox/kube-linter) - KubeLinter 是一个静态分析工具，用于检查 Kubernetes YAML 文件和 Helm 图表，以确保其中表示的应用程序符合最佳实践. 
- [kubeval](https://kubeval.instrumenta.dev) - Validates your Kubernetes configuration files and supports multiple Kubernetes versions.
- [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint) - 检查 Puppet metadata.json 文件有效性的工具.
- [Puppet Lint](https://github.com/rodjek/puppet-lint) - Check that your Puppet manifests conform to the style guide.
- [terraform-compliance](https://terraform-compliance.com) - 针对 Terraform 的轻量级、合规性和安全性 BDD 测试框架.
- [terrascan](https://github.com/cesar-rodriguez/terrascan) - 收集用于 Terraform 模板的静态代码分析的安全性和最佳实践测试.
- [tflint](https://github.com/wata727/tflint) - 用于检测“terraform plan”无法检测到的错误的 Terraform linter.
- [tfsec](https://github.com/tfsec/tfsec) - Terraform static analysis tool that prevents potential security issues by checking cloud misconfigurations at build time and directly integrates with the HCL parser for better results. Checks for violations of AWS, Azure and GCP security best practice recommendations.


<h2 id="container">容器</h2>

- [anchore](https://anchore.io)  - 发现、分析和验证容器映像. 一种分析 Docker 映像并应用用户定义的接受策略以允许自动容器映像验证和认证的服务 
- [chart-testing](https://github.com/helm/chart-testing) - ct is the the tool for testing Helm charts.  It is meant to be used for linting and testing pull requests.  It automatically detects charts changed against the target branch.
- [clair](https://github.com/coreos/clair) - Vulnerability Static Analysis for Containers.
- [clusterlint](https://github.com/digitalocean/clusterlint)  - Clusterlint 查询实时 Kubernetes 集群的资源，对这些资源执行常见的和特定于平台的检查，并向集群操作员提供可操作的反馈. 它是一种在外部运行的非侵入性工具.  Clusterlint 不会改变资源配置.
- [collector](https://github.com/banyanops/collector) :warning: - Run arbitrary scripts inside containers, and gather useful information.
- [dagda](https://github.com/eliasgranderubio/dagda) - 对 docker 镜像/容器中的已知漏洞进行静态分析.
- [Datree](https://datree.io/) - 一个 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及您组织的政策来防止 Kubernetes 错误配置
- [Docker Label Inspector](https://github.com/garethr/docker-label-inspector) :warning: - Lint 并验证 Dockerfile 标签.
- [Haskell Dockerfile Linter](https://github.com/lukasmartinelli/hadolint) - 更智能的 Dockerfile linter，可帮助您构建最佳实践 Docker 映像.
- [kics](https://kics.io/) - Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible
- [kube-lint](https://github.com/viglesiasce/kube-lint)  - 具有可定制规则集的 Kubernetes 资源的 linter. 您定义了一个要针对您的资源验证的规则列表，kube-lint 将根据它们评估这些规则.
- [kube-linter](https://github.com/stackrox/kube-linter) - KubeLinter 是一个静态分析工具，用于检查 Kubernetes YAML 文件和 Helm 图表，以确保其中表示的应用程序符合最佳实践. 
- [kube-score](https://kube-score.com) - 对您的 Kubernetes 对象定义进行静态代码分析.
- [KubeLinter](https://github.com/stackrox/kube-linter) - KubeLinter 是一个静态分析工具，用于检查 Kubernetes YAML 文件和 Helm 图表，以确保其中表示的应用程序符合最佳实践.
- [kubeval](https://kubeval.instrumenta.dev) - Validates your Kubernetes configuration files and supports multiple Kubernetes versions.
- [OpenSCAP](https://www.open-scap.org/) - Suite of automated audit tools to examine the configuration and  known vulnerabilities following the NIST-certified Security  Content Automation Protocol (SCAP).
- [Qualys Container Security](https://www.qualys.com/apps/container-security) :copyright: - Container native application protection to provide visibility and control of containerized applications.
- [sysdig](https://sysdig.com/)  :copyright: - 用于云和容器取证的安全 DevOps 平台.  Sysdig 建立在开源堆栈之上，提供 Docker 图像扫描并创建了 Falco，这是用于容器、Kubernetes 和云的运行时威胁检测的开放标准. 
- [Vuls](https://vuls.io/) - 基于 NVD、OVAL 等信息的无代理 Linux 漏洞扫描程序.它具有一些容器映像支持，尽管不是特定于容器的工具.


<h2 id="ci">Continuous Integration</h2>

- [actionlint](https://rhysd.github.io/actionlint)  - GitHub Actions 工作流文件的静态检查器. 提供在线版本.
- [AzSK](https://azsk.azurewebsites.net/)  - 适用于 Azure (AzSK) 的安全 DevOps 工具包在基础架构即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础架构错误配置. 通过 ARM 支持 Azure.
- [Code Climate](https://codeclimate.com) - The open and extensible static analysis platform, for everyone.
- [exakat](https://www.exakat.io) - An automated code reviewing engine for PHP.
- [Nitpick CI](https://nitpick-ci.com) :copyright: - 自动 PHP 代码审查.
- [PullRequest](https://www.pullrequest.com) :copyright: - Code review as a service with built-in static analysis.  Increase velocity and reduce technical debt through quality code review by expert engineers backed by best-in-class automation.
- [quality](https://github.com/apiology/quality) :warning: - Runs quality checks on your code using community tools, and makes sure your numbers don't get any worse over time.
- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode) :warning: - Automated code review & repair. It helps you to keep track of issues and metrics in your software projects, and can be easily extended to support new types of analyses.
- [Reviewdog](https://github.com/haya14busa/reviewdog) - A tool for posting review comments from any linter in any code hosting service.
- [Symfony Insight](https://insight.symfony.com/) :copyright: - Detect security risks, find bugs and provide actionable metrics for PHP projects.
- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  - 用于从静态代码分析中解析报告文件的 Java 库. 被一堆 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="deno">Deno</h2>

- [deno_lint](https://github.com/denoland/deno_lint) - Official linter for Deno.


<h2 id="embedded">Embedded</h2>

- [oelint-adv](https://github.com/priv-kweihmann/oelint-adv) - Linter for bitbake recipes used in open-embedded and YOCTO


<h2 id="erb">Embedded Ruby (a.k.a. ERB, eRuby)</h2>

- [ERB Lint](https://github.com/Shopify/erb-lint) - 整理您的 ERB 或 HTML 文件


<h2 id="gherkin">Gherkin</h2>

- [gherkin-lint](https://github.com/vsiakka/gherkin-lint) - 用 Ja​​vascript 编写的 Gherkin-Syntax 的 linter.


<h2 id="html">HTML</h2>

- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) - Linter for Angular projects
- [Bootlint](https://github.com/twbs/bootlint) - An HTML linter for Bootstrap projects.
- [ERB Lint](https://github.com/Shopify/erb-lint) - 整理您的 ERB 或 HTML 文件
- [grunt-bootlint](https://github.com/twbs/grunt-bootlint) - A Grunt wrapper for [Bootlint](https://github.com/twbs/bootlint), Bootstrap 项目的 HTML linter.
- [gulp-bootlint](https://github.com/tschortsch/gulp-bootlint) - 一个 gulp 包装器 [Bootlint](https://github.com/twbs/bootlint), Bootstrap 项目的 HTML linter.
- [HTML Inspector](https://github.com/philipwalton/html-inspector) :warning: - HTML Inspector 是一种代码质量工具，可帮助您和您的团队编写更好的标记.
- [HTML Tidy](http://www.html-tidy.org) - Corrects and cleans up HTML and XML documents by fixing markup errors and upgrading legacy code to modern standards.
- [HTML-Validate](https://html-validate.org/) - Offline HTML5 validator.
- [HTMLHint](https://htmlhint.com) - A Static Code Analysis Tool for HTML.
- [Nu Html Checker](https://validator.github.io/validator/) - 帮助您发现 HTML/CSS/SVG 中的问题
- [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer) - Web 组件的静态分析框架.


<h2 id="json">JSON</h2>

- [Spectral](https://stoplight.io/open-source/spectral) - A flexible JSON/YAML linter, without of the box support for OpenAPI v2/v3 and AsyncAPI v2.


<h2 id="kubernetes">Kubernetes</h2>

- [chart-testing](https://github.com/helm/chart-testing) - ct is the the tool for testing Helm charts.  It is meant to be used for linting and testing pull requests.  It automatically detects charts changed against the target branch.
- [clusterlint](https://github.com/digitalocean/clusterlint)  - Clusterlint 查询实时 Kubernetes 集群的资源，对这些资源执行常见的和特定于平台的检查，并向集群操作员提供可操作的反馈. 它是一种在外部运行的非侵入性工具.  Clusterlint 不会改变资源配置.
- [Datree](https://datree.io/) - 一个 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及您组织的政策来防止 Kubernetes 错误配置
- [kics](https://kics.io/) - Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible
- [kube-lint](https://github.com/viglesiasce/kube-lint)  - 具有可定制规则集的 Kubernetes 资源的 linter. 您定义了一个要针对您的资源验证的规则列表，kube-lint 将根据它们评估这些规则.
- [kube-linter](https://github.com/stackrox/kube-linter) - KubeLinter 是一个静态分析工具，用于检查 Kubernetes YAML 文件和 Helm 图表，以确保其中表示的应用程序符合最佳实践. 
- [kubeval](https://kubeval.instrumenta.dev) - Validates your Kubernetes configuration files and supports multiple Kubernetes versions.


<h2 id="latex">LaTeX</h2>

- [ChkTeX](http://www.nongnu.org/chktex) - A linter for LaTex which catches some typographic errors LaTeX oversees.
- [lacheck](https://www.ctan.org/pkg/lacheck) - A tool for finding common mistakes in LaTeX documents.
- [TeXLab](https://texlab.netlify.app) - A Language Server Protocol implementation for TeX/LaTeX, including lint capabilities.


<h2 id="laravel">拉拉维尔</h2>

- [Enlightn](https://www.laravel-enlightn.com/)  - 用于 Laravel 应用程序的静态和动态分析工具，它提供建议以提高 Laravel 应用程序的性能、安全性和代码可靠性. 包含 120 个自动检查.


<h2 id="make">Makefiles</h2>

- [checkmake](https://github.com/mrtazz/checkmake) - 用于生成文件的 Linter / Analyzer.
- [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) - A verifier for FreeBSD and DragonFlyBSD port directories.


<h2 id="markdown">降价</h2>

- [markdownlint](https://github.com/DavidAnson/markdownlint) - Node.js -based style checker and lint tool for Markdown/CommonMark files.
- [mdformat](https://mdformat.rtfd.io) - CommonMark compliant Markdown formatter
- [mdl](https://github.com/mivok/markdownlint) - 检查 Markdown 文件和标记样式问题的工具.
- [remark-lint](https://remark.js.org) - Pluggable Markdown code style linter written in JavaScript.


<h2 id="meta">Metalinter</h2>

- [ciocheck](https://github.com/ContinuumIO/ciocheck)  :warning: - Linter、格式化程序和测试套件助手. 作为 linter，它是 `pep8`、`pydocstyle`、`flake8` 和 `pylint` 的包装器.
- [flake8](https://github.com/PyCQA/flake8) - `pyflakes`、`pycodestyle` 和 `mccabe` 的​​包装器.
- [Go Meta Linter](https://github.com/alecthomas/gometalinter)  :warning: - 同时运行 Go lint 工具并标准化它们的输出. 对新项目使用 `golangci-lint`.
- [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) - 同时运行许多 linter 并将它们的输出标准化为报告.
- [multilint](https://github.com/adamchainz/multilint) :warning: - `flake8`、`isort` 和 `modernize` 的包装器.
- [prospector](https://github.com/PyCQA/prospector) - A wrapper around `pylint`, `pep8`, `mccabe` and others.


<h2 id="mobile">Mobile</h2>

- [Android Lint](http://tools.android.com/tips/lint) - 对 Android 项目运行静态分析.
- [android-lint-summary](https://passy.github.io/android-lint-summary) :warning: - Combines lint errors of multiple projects into one output, check lint results of multiple sub-projects at once.
- [FlowDroid](https://github.com/secure-software-engineering/FlowDroid) - 适用于 Android 应用程序的静态污点分析工具.
- [iblessing](https://www.kitploit.com/2020/08/iblessing-ios-security-exploiting.html)  - iblessing 是一个 iOS 安全漏洞利用工具包. 它可用于逆向工程、二进制分析和漏洞挖掘.
- [Oversecured](https://oversecured.com) :copyright: - Enterprise vulnerability scanner for Android and iOS apps. It allows app owners and developers to secure each new version of a mobile app by integrating Oversecured into the development process.
- [paprika](https://github.com/GeoffreyHecht/paprika) :warning: - 在分析的 Android 应用程序中检测一些代码异味的工具包.
- [qark](https://github.com/linkedin/qark) :warning: - Tool to look for several security related Android application vulnerabilities.
- [redex](https://fbredex.com)  - Redex 提供了一个用于读取、写入和分析 .dex 文件的框架，以及一组使用该框架改进字节码的优化通道.  Redex 优化的 APK 应该更小更快.


<h2 id="nix">Nix</h2>

- [deadnix](https://github.com/astro/deadnix) - 扫描 Nix 文件中的死代码（未使用的变量绑定）


<h2 id="nodejs">节点.js</h2>

- [lockfile-lint](https://github.com/lirantal/lockfile-lint) - 对 npm 或 yarn lockfile 进行 Lint 分析和检测安全问题
- [njsscan](https://opensecurity.in) - A static application testing (SAST) tool that can find insecure code patterns in your node.js applications using simple pattern matcher from libsast and syntax-aware semantic code pattern search tool semgrep.
- [NodeJSScan](https://opensecurity.in)  - 由 libsast 和 semgrep 提供支持的 Node.js 应用程序的静态安全代码扫描程序，构建在 njsscan cli 工具上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.
- [standard](http://standardjs.com) - 检查 Javascript 样式指南问题的 npm 模块.


<h2 id="package">Packages</h2>

- [lintian](https://lintian.debian.org) - Static analysis tool for Debian packages.
- [rpmlint](https://github.com/rpm-software-management/rpmlint) - 用于检查 rpm 包中常见错误的工具.


<h2 id="protobuf">Protocol Buffers</h2>

- [buf](https://buf.build) - Provides a CLI linter that enforces good API design choices and structure
- [protolint](https://github.com/yoheimuta/protolint) - 可插入的 linter 和 fixer 以强制执行 Protocol Buffer 样式和约定.


<h2 id="puppet">木偶</h2>

- [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint) - 检查 Puppet metadata.json 文件有效性的工具.


<h2 id="rails">导轨</h2>

- [dawnscanner](https://github.com/thesp0nge/dawnscanner) - A static analysis security scanner for ruby written web applications. It supports Sinatra, Padrino and Ruby on Rails frameworks.


<h2 id="security">安全/SAST</h2>

- [AzSK](https://azsk.azurewebsites.net/)  - 适用于 Azure (AzSK) 的安全 DevOps 工具包在基础架构即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础架构错误配置. 通过 ARM 支持 Azure.
- [brakeman](https://brakemanscanner.org) - A static analysis security vulnerability scanner for Ruby on Rails applications.
- [Datree](https://datree.io/) - 一个 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及您组织的政策来防止 Kubernetes 错误配置
- [Enlightn](https://www.laravel-enlightn.com/)  - 用于 Laravel 应用程序的静态和动态分析工具，它提供建议以提高 Laravel 应用程序的性能、安全性和代码可靠性. 包含 120 个自动检查.
- [Gitleaks](https://github.com/zricethezav/gitleaks) - A SAST tool for detecting hardcoded secrets like passwords, api keys, and tokens in git repos.
- [gokart](https://github.com/praetorian-inc/gokart) - Golang security analysis with a focus on minimizing false positives. It is capable of tracing the source of variables and function arguments  to determine whether input sources are safe.
- [iblessing](https://www.kitploit.com/2020/08/iblessing-ios-security-exploiting.html)  - iblessing 是一个 iOS 安全漏洞利用工具包. 它可用于逆向工程、二进制分析和漏洞挖掘.
- [kics](https://kics.io/) - Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible
- [lockfile-lint](https://github.com/lirantal/lockfile-lint) - 对 npm 或 yarn lockfile 进行 Lint 分析和检测安全问题
- [njsscan](https://opensecurity.in) - A static application testing (SAST) tool that can find insecure code patterns in your node.js applications using simple pattern matcher from libsast and syntax-aware semantic code pattern search tool semgrep.
- [NodeJSScan](https://opensecurity.in)  - 由 libsast 和 semgrep 提供支持的 Node.js 应用程序的静态安全代码扫描程序，构建在 njsscan cli 工具上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.
- [Oversecured](https://oversecured.com) :copyright: - Enterprise vulnerability scanner for Android and iOS apps. It allows app owners and developers to secure each new version of a mobile app by integrating Oversecured into the development process.
- [PT Application Inspector](https://www.ptsecurity.com)  :copyright: - 识别代码缺陷并检测漏洞以防止 Web 攻击. 通过展示可能的漏洞来演示远程代码执行.
- [Qualys Container Security](https://www.qualys.com/apps/container-security) :copyright: - Container native application protection to provide visibility and control of containerized applications.
- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode) :warning: - Automated code review & repair. It helps you to keep track of issues and metrics in your software projects, and can be easily extended to support new types of analyses.
- [Reshift](https://www.reshiftsecurity.com) :copyright: - A source code analysis tool for detecting and managing Java security vulnerabilities.
- [scorecard](https://github.com/ossf/scorecard) - Security Scorecards - Security health metrics for Open Source
- [SearchDiggity](https://resources.bishopfox.com/resources/tools/google-hacking-diggity/attack-tools/) :copyright: - Identifies vulnerabilities in open source code projects  hosted on Github, Google Code, MS CodePlex, SourceForge, and more.  The tool comes with over 130 default searches that identify SQL injection,  cross-site scripting (XSS), insecure remote and local file includes, hard-coded passwords, etc. 
- [Symfony Insight](https://insight.symfony.com/) :copyright: - Detect security risks, find bugs and provide actionable metrics for PHP projects.
- [tfsec](https://github.com/tfsec/tfsec) - Terraform static analysis tool that prevents potential security issues by checking cloud misconfigurations at build time and directly integrates with the HCL parser for better results. Checks for violations of AWS, Azure and GCP security best practice recommendations.
- [Tsunami Security Scanner](https://github.com/google/tsunami-security-scanner) - A general purpose network security scanner with an extensible plugin system for  detecting high severity RCE-like vulnerabilities with high confidence. Custom detectors for finding vulnerabilities (e.g. open APIs) can be added.


<h2 id="smart-contracts">智能合约</h2>

- [mythril](https://github.com/ConsenSys/mythril) - 包含电池的符号执行框架，可用于自动查找和利用智能合约中的漏洞.
- [MythX](https://mythx.io)  :copyright: - MythX 是一个易于使用的分析平台，它集成了多种分析方法，如模糊测试、符号执行和静态分析，以高精度查找漏洞. 它可以与 Remix 或 VSCode 等工具链集成，也可以从命令行调用.
- [slither](https://github.com/trailofbits/slither) - 运行一套漏洞检测器的静态分析框架，打印有关合同细节的可视信息，并提供一个 API 来轻松编写自定义分析.
- [solhint](https://protofire.github.io/solhint) - Solhint is an open source project created by https://protofire.io. Its goal is to provide a linting utility for Solidity code.
- [solium](https://ethlint.readthedocs.io/en/latest) - Solium is a linter to identify and fix style and security issues in Solidity smart contracts.


<h2 id="support">支持</h2>

- [LibVCS4j](https://github.com/uni-bremen-agst/libvcs4j) - A Java library that allows existing tools to analyse the evolution of software systems by providing a common API for different version control systems and issue trackers.
- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  - 用于从静态代码分析中解析报告文件的 Java 库. 被一堆 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="template">Template-Languages</h2>

- [ember-template-lint](https://github.com/ember-template-lint/ember-template-lint) - 用于 Ember 或 Handlebars 模板的 Linter.
- [haml-lint](https://github.com/sds/haml-lint) - Tool for writing clean and consistent HAML.
- [slim-lint](https://github.com/sds/slim-lint) - 用于分析 Slim 模板的可配置工具.
- [yamllint](https://yamllint.readthedocs.io) - 检查 YAML 文件的语法有效性、键重复和外观问题，如行长、尾随空格和缩进.


<h2 id="terraform">Terraform</h2>

- [kics](https://kics.io/) - Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible
- [shisho](https://docs.shisho.dev/)  - 专为开发人员和安全团队设计的轻量级静态代码分析器. 它允许您使用类似于 sed 的直观 DSL 分析和转换源代码，但用于代码.


<h2 id="translation">翻译</h2>

- [dennis](https://github.com/willkg/dennis) :warning: - A set of utilities for working with PO files to ease development and improve quality.


<h2 id="vue">Vue.js</h2>

- [HTML-Validate](https://html-validate.org/) - Offline HTML5 validator.
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) - Vue tooling for VS Code, powered by vls (vue language server). Vetur has support for formatting embedded HTML, CSS, SCSS, JS, TypeScript, and more. Vetur only has a "whole document formatter" and cannot format arbitrary ranges.


<h2 id="wasm">网络组装</h2>

- [Twiggy](https://rustwasm.github.io/twiggy)  - 分析二进制文件的调用图以分析代码大小. 目标是缩小 wasm 二进制大小.


<h2 id="writing">写作</h2>

- [After the Deadline](https://open.afterthedeadline.com) :warning: - 拼写、风格和语法检查器.
- [alex](https://alexjs.com) - Catch insensitive, inconsiderate writing
- [codespell](https://github.com/codespell-project/codespell) - 检查常见拼写错误的代码.
- [languagetool](https://languagetool.org)  - 超过 25 种语言的风格和语法检查器. 它发现了许多简单的拼写检查器无法检测到的错误.
- [misspell-fixer](https://github.com/vlajos/misspell-fixer) - 修复源代码中常见拼写错误和拼写错误的快速工具.
- [Misspelled Words In Context](https://jwilk.net/software/mwic) - 一个拼写检查器，可将可能的拼写错误分组并在其上下文中显示.
- [proselint](http://proselint.com) - 英语散文的短绒，重点是写作风格而不是语法.
- [vale](https://docs.errata.ai/vale/about) - A syntax-aware linter for prose built with speed and extensibility in mind.
- [write-good](https://github.com/btford/write-good) - A linter with a focus on eliminating "weasel words".


<h2 id="yaml">YAML</h2>

- [Spectral](https://stoplight.io/open-source/spectral) - A flexible JSON/YAML linter, without of the box support for OpenAPI v2/v3 and AsyncAPI v2.
- [yamllint](https://yamllint.readthedocs.io) - 检查 YAML 文件的语法有效性、键重复和外观问题，如行长、尾随空格和缩进.


<h2 id="git">git</h2>

- [commitlint](https://commitlint.js.org) - checks if your commit messages meet the conventional commit format


## More Collections

- [Clean code linters](https://github.com/collections/clean-code-linters) - A collection of linters in github collections
- [Code Quality Checker Tools For PHP Projects](https://github.com/collections/code-quality-in-php) - A collection of PHP linters in github collections
- [go-tools](https://github.com/dominikh/go-tools) - 一组用于处理 Go 代码的工具和库，包括 linter 和静态分析
- [linters](https://github.com/mcandre/linters) - An introduction to static code analysis
- [OWASP Source Code Analysis Tools](https://owasp.org/www-community/Source_Code_Analysis_Tools) - List of tools maintained by the Open Web Application Security Project
- [php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools) - 有用的 PHP 静态分析工具的审查列表
- [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) - 静态代码分析工具列表.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Matthias Endler](https://endler.dev) has waived all copyright and related or neighboring rights to this work.
用于格式化和显示该内容的底层源代码在 MIT 许可下获得许可.


标题图片 [Designed by Freepik](http://www.freepik.com).
