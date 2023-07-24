<div class="github-widget" data-repo="analysis-tools-dev/static-analysis"></div>
<!--  DON'T EDIT THIS FILE DIRECTLY. Edit `data/tools.yml` instead.  -->

 <a href="https://analysis-tools.dev/">
   <img alt="Analysis Tools Website" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/redesign.svg" />
 </a>

该存储库列出了所有编程语言、构建工具、配置文件等的**静态分析工具**. 重点是提高代码质量的工具，例如 linter 和格式化程序.
官方网站， [analysis-tools.dev](https://analysis-tools.dev/) 基于此存储库，并添加排名、用户评论以及每个工具的视频等其他资源.

[![Website](https://img.shields.io/badge/Website-Online-2B5BAE)](https://analysis-tools.dev)
![CI](https://github.com/analysis-tools-dev/static-analysis/workflows/CI/badge.svg)

## Sponsors

如果没有赞助商的慷慨支持，这个项目就不可能实现.

<table>
   <tr>
      <td><a href="https://deepcode.ai"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/deepcode.png" /></a></td>
      <td>
         <a href="https://www.bearer.com">
            <picture >
               <source width="200px" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/bearer-dark.svg?sanitize=true">
               <img width="200px" alt="Bearer" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/bearer-light.svg">
            </picture>
         </a>
      </td>
      <td><a href="https://codescene.io/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/codescene.svg" /></a></td>
      <td><a href="https://semgrep.dev/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/semgrep.svg" /></a></td>
      <td><a href="https://codiga.io/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/codiga.svg" /></a></td>
      <td><a href="https://offensive360.com/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/offensive360.png" /></a></td>
   </tr>
</table>

如果您也想支持这个项目，请访问我们 [Github sponsors page](https://github.com/sponsors/analysis-tools-dev).

## Meaning of Symbols:

 - ：版权：代表专有软件. 所有其他工具都是开源的.
 - :information_source: 表示社区不再建议在新项目中使用该工具. 该图标链接到讨论问题.
- :warning: 表示该工具已超过 1 年未更新，或者存储库已存档.

非常欢迎请求请求！  
另请查看姊妹项目， [awesome-dynamic-analysis](https://github.com/mre/awesome-dynamic-analysis).






<details>
 <summary>显示其他</summary>

</details>

---

## Programming Languages

<h2 id="abap">ABAP</h2>


- [abaplint](https://abaplint.org) — ABAP 的 Linter，用 TypeScript 编写.

- [abapOpenChecks](https://docs.abapopenchecks.org) — Enhances the SAP Code Inspector with new and customizable checks.


<h2 id="ada">有</h2>


- [Codepeer](https://www.adacore.com/static-analysis/codepeer) :copyright: — 检测运行时和逻辑错误.

- [Polyspace for Ada](https://www.mathworks.com/products/polyspace-ada.html) :copyright: — 提供代码验证，证明源代码中不存在溢出、被零除、数组访问越界以及某些其他运行时错误.

- [SPARK](https://www.adacore.com/about-spark) ：版权： — Ada 的静态分析和形式验证工具集.


<h2 id="asm">集会</h2>


- [STOKE](https://github.com/StanfordPL/stoke)  :warning: — 用于 x86_64 指令集的与编程语言无关的随机优化器. 它使用随机搜索来探索所有可能的程序转换的极高维空间.


<h2 id="awk">awk</h2>


- [gawk --lint](https://www.gnu.org/software/gawk/manual/html_node/Options.html) — 警告可疑或不可移植到其他 awk 实现的构造.


<h2 id="c">C</h2>


- [Astrée](https://www.absint.com/astree/index.htm)  :copyright: — Astrée 自动证明 C/C++ 应用程序中不存在运行时错误和无效的并发行为. 它非常适合浮点计算，速度非常快，而且非常精确. 该分析仪还检查 MISRA/CERT/CWE/Adaptive Autosar 编码规则，并支持 ISO 26262、DO-178C A 级和其他安全标准的资格认证.  Jenkins 和 Eclipse 插件可用.

- [CBMC](http://www.cprover.org/cbmc) — C 程序的有界模型检查器、用户定义的断言、标准断言、多种覆盖率度量分析.

- [clang-tidy](https://clang.llvm.org/extra/clang-tidy) — 基于 Clang 的 C++ linter 工具，也具有（有限）修复问题的能力.

- [clazy](https://github.com/KDE/clazy)  — 基于 Clang 框架的面向 Qt 的静态代码分析器.  clazy 是一个编译器插件，它允许 clang 理解 Qt 语义. 您会收到超过 50 个与 Qt 相关的编译器警告，范围从不需要的内存分配到 API 的误用，包括用于自动重构的修复.

- [CMetrics](https://github.com/MetricsGrimoire/CMetrics) — 测量 C 文件的大小和复杂性.

- [CPAchecker](https://cpachecker.sosy-lab.org)  — 用于 C 程序的可配置软件验证的工具. 选择 CPAchecker 这个名称是为了反映该工具基于 CPA 概念，用于检查软件程序.

- [cppcheck](https://cppcheck.sourceforge.io) — C/C++ 代码的静态分析.

- [CppDepend](https://www.cppdepend.com) :copyright: — 测量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.

- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) — 遵循 Google 风格指南的自动 C++ 检查器.

- [cqmetrics](https://github.com/dspinellis/cqmetrics) — C 代码的质量指标.

- [CScout](https://www.spinellis.gr/cscout) :警告: — C 和 C 预处理器代码的复杂性和质量指标.

- [ESBMC](http://esbmc.org) — ESBMC 是一个开源、许可许可、上下文受限的模型检查器，基于可满足性模理论，用于验证单线程和多线程 C/C++ 程序.

- [flawfinder](http://dwheeler.com/flawfinder/) — 发现可能的安全漏洞.

- [flint++](https://github.com/JossWhittle/FlintPlusPlus) — flint 的跨平台、零依赖端口，是 Facebook 开发和使用的 C++ lint 程序.

- [Frama-C](https://www.frama-c.com) — 一个健全且可扩展的 C 代码静态分析器.

- [GCC](https://gcc.gnu.org/onlinedocs/gcc/Static-Analyzer-Options.html)  — GCC 编译器从版本 10 起就具有静态分析功能.仅当 GCC 配置为启用分析器支持时，此选项才可用. 它还可以将其诊断信息输出到 SARIF 格式的 JSON 文件（从 v13 开始）.

- [Goblint](https://goblint.in.tum.de)  — 用于分析多线程 C 程序的静态分析器. 它的主要重点是检测数据竞争，但它也报告其他运行时错误，例如缓冲区溢出和空指针取消引用.

- [Helix QAC](https://www.perforce.com/products/helix-qac)  ：版权： — 嵌入式软件的企业级静态分析. 支持 MISRA、CERT 和 AUTOSAR 编码标准.

- [IKOS](https://github.com/nasa-sw-vnv/ikos) — 基于 LLVM 的 C/C++ 代码健全静态分析器.

- [Joern](https://joern.io) — 基于代码属性图的C/C++开源代码分析平台

- [KLEE](http://klee.github.io/)  — 构建在 LLVM 编译器基础架构之上的动态符号执行引擎. 它可以自动为程序生成测试用例，以便测试用例尽可能多地运行程序.

- [LDRA](https://ldra.com) ：版权： — 一个工具套件，包括符合各种标准的静态分析 (TBVISION)，包括 MISRA C &amp; C++、JSF++ AV、CWE、CERT C、CERT C++ 和自定义规则.

- [MATE](https://galoisinc.github.io/MATE/)  — 一套用于交互式程序分析的工具，重点是寻找 C 和 C++ 代码中的错误.  MATE 使用代码属性图 (CPG) 统一特定于应用程序的漏洞分析和低级漏洞分析，从而能够发现依赖于目标 C/C++ 程序的实现细节和高级语义的高度特定于应用程序的漏洞.

- [PC-lint](https://pclintplus.com/)  :copyright: — C/C++ 静态分析. 在 Windows/Linux/MacOS 下本机运行. 分析几乎任何平台的代码，支持 C11/C18 和 C++17.

- [Phasar](https://phasar.org) — 基于 LLVM 的静态分析框架，带有污点和类型状态分析.

- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) :copyright: — 识别 C 和 C++ 嵌入式软件中的运行时错误、并发问题、安全漏洞和其他缺陷.

- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) :copyright: — 提供代码验证，证明 C 和 C++ 源代码中不存在溢出、被零除、越界数组访问以及某些其他运行时错误.

- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) — 通过常规构建驱动 Clang 内置的 Clang 静态分析器的前端.

- [splint](http://splint.org) — 注释辅助静态程序检查器.

- [SVF](https://svf-tools.github.io/SVF) — 一种静态工具，可以对 C 和 C++ 程序进行可扩展且精确的过程间依赖分析.

- [TrustInSoft Analyzer](https://trust-in-soft.com)  ：版权： — 彻底检测编码错误及其相关的安全漏洞. 这包括健全的未定义行为检测（缓冲区溢出、越界数组访问、空指针取消引用、释放后使用、除以零、未初始化内存访问、有符号溢出、无效指针算术等）、数据流和控制流验证以及形式规范的完整功能验证. 支持 C 至 C18 和 C++ 至 C++20 的所有版本.  TrustInSoft Analyzer 将于 2023 年第二季度 (TCL3) 获得 ISO 26262 资格. 还捆绑了 MISRA C 检查器.

- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) — Vera++ 是一个用于验证、分析和转换 C++ 源代码的可编程工具.


<h2 id="csharp">C#</h2>


- [.NET Analyzers](https://github.com/DotNetAnalyzers) — 使用 .NET 编译器平台开发分析器（诊断和代码修复）的组织.

- [ArchUnitNET](https://github.com/TNG/ArchUnitNET) — A C# architecture test library to specify and assert architecture rules in C# for automated testing.

- [code-cracker](https://code-cracker.github.io) — An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.

- [CSharpEssentials](https://github.com/DustinCampbell/CSharpEssentials) :warning: — C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features.

- [Designite](http://www.designite-tools.com) :copyright: — Designite 支持检测各种架构、设计和实现气味，计算各种代码质量指标以及趋势分析.

- [Gendarme](https://www.mono-project.com/docs/tools+libraries/tools/gendarme) — Gendarme 检查包含 ECMA CIL 格式（Mono 和 .NET）代码的程序和库.

- [Infer#](https://github.com/microsoft/infersharp) — InferSharp (also referred to as Infer#) is an interprocedural and  scalable static code analyzer for C#. Via the capabilities of Facebook's Infer,  this tool detects null pointer dereferences and resource leaks.

- [NDepend](http://www.ndepend.com) :copyright: — 测量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.

- [Puma Scan](https://pumasecurity.io) — 当开发团队在 Visual Studio 中编写代码时，Puma Scan 为常见漏洞（XSS、SQLi、CSRF、LDAPi、加密、反序列化等）提供实时安全代码分析.

- [Roslynator](https://github.com/JosefPihrt/Roslynator) — A collection of 190+ analyzers and 190+ refactorings for C#, powered by Roslyn.

- [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) — 基于 Roslyn 并与 VS 集成的静态分析器集合.

- [Wintellect.Analyzers](https://github.com/Wintellect/Wintellect.Analyzers) — .NET 编译器平台（“Roslyn”）诊断分析器和代码修复.


<h2 id="cpp">C++</h2>


- [Astrée](https://www.absint.com/astree/index.htm)  :copyright: — Astrée 自动证明 C/C++ 应用程序中不存在运行时错误和无效的并发行为. 它非常适合浮点计算，速度非常快，而且非常精确. 该分析仪还检查 MISRA/CERT/CWE/Adaptive Autosar 编码规则，并支持 ISO 26262、DO-178C A 级和其他安全标准的资格认证.  Jenkins 和 Eclipse 插件可用.

- [CBMC](http://www.cprover.org/cbmc) — C 程序的有界模型检查器、用户定义的断言、标准断言、多种覆盖率度量分析.

- [clang-tidy](https://clang.llvm.org/extra/clang-tidy) — 基于 Clang 的 C++ linter 工具，也具有（有限）修复问题的能力.

- [clazy](https://github.com/KDE/clazy)  — 基于 Clang 框架的面向 Qt 的静态代码分析器.  clazy 是一个编译器插件，它允许 clang 理解 Qt 语义. 您会收到超过 50 个与 Qt 相关的编译器警告，范围从不需要的内存分配到 API 的误用，包括用于自动重构的修复.

- [CMetrics](https://github.com/MetricsGrimoire/CMetrics) — 测量 C 文件的大小和复杂性.

- [cppcheck](https://cppcheck.sourceforge.io) — C/C++ 代码的静态分析.

- [CppDepend](https://www.cppdepend.com) :copyright: — 测量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.

- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) — 遵循 Google 风格指南的自动 C++ 检查器.

- [cqmetrics](https://github.com/dspinellis/cqmetrics) — C 代码的质量指标.

- [CScout](https://www.spinellis.gr/cscout) :警告: — C 和 C 预处理器代码的复杂性和质量指标.

- [ESBMC](http://esbmc.org) — ESBMC 是一个开源、许可许可、上下文受限的模型检查器，基于可满足性模理论，用于验证单线程和多线程 C/C++ 程序.

- [flawfinder](http://dwheeler.com/flawfinder/) — 发现可能的安全漏洞.

- [flint++](https://github.com/JossWhittle/FlintPlusPlus) — flint 的跨平台、零依赖端口，是 Facebook 开发和使用的 C++ lint 程序.

- [Frama-C](https://www.frama-c.com) — 一个健全且可扩展的 C 代码静态分析器.

- [Helix QAC](https://www.perforce.com/products/helix-qac)  ：版权： — 嵌入式软件的企业级静态分析. 支持 MISRA、CERT 和 AUTOSAR 编码标准.

- [IKOS](https://github.com/nasa-sw-vnv/ikos) — 基于 LLVM 的 C/C++ 代码健全静态分析器.

- [Joern](https://joern.io) — 基于代码属性图的C/C++开源代码分析平台

- [KLEE](http://klee.github.io/)  — 构建在 LLVM 编译器基础架构之上的动态符号执行引擎. 它可以自动为程序生成测试用例，以便测试用例尽可能多地运行程序.

- [LDRA](https://ldra.com) ：版权： — 一个工具套件，包括符合各种标准的静态分析 (TBVISION)，包括 MISRA C &amp; C++、JSF++ AV、CWE、CERT C、CERT C++ 和自定义规则.

- [MATE](https://galoisinc.github.io/MATE/)  — 一套用于交互式程序分析的工具，重点是寻找 C 和 C++ 代码中的错误.  MATE 使用代码属性图 (CPG) 统一特定于应用程序的漏洞分析和低级漏洞分析，从而能够发现依赖于目标 C/C++ 程序的实现细节和高级语义的高度特定于应用程序的漏洞.

- [PC-lint](https://pclintplus.com/)  :copyright: — C/C++ 静态分析. 在 Windows/Linux/MacOS 下本机运行. 分析几乎任何平台的代码，支持 C11/C18 和 C++17.

- [Phasar](https://phasar.org) — 基于 LLVM 的静态分析框架，带有污点和类型状态分析.

- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) :copyright: — 识别 C 和 C++ 嵌入式软件中的运行时错误、并发问题、安全漏洞和其他缺陷.

- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) :copyright: — 提供代码验证，证明 C 和 C++ 源代码中不存在溢出、被零除、越界数组访问以及某些其他运行时错误.

- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) — 通过常规构建驱动 Clang 内置的 Clang 静态分析器的前端.

- [splint](http://splint.org) — 注释辅助静态程序检查器.

- [SVF](https://svf-tools.github.io/SVF) — 一种静态工具，可以对 C 和 C++ 程序进行可扩展且精确的过程间依赖分析.

- [TrustInSoft Analyzer](https://trust-in-soft.com)  ：版权： — 彻底检测编码错误及其相关的安全漏洞. 这包括健全的未定义行为检测（缓冲区溢出、越界数组访问、空指针取消引用、释放后使用、除以零、未初始化内存访问、有符号溢出、无效指针算术等）、数据流和控制流验证以及形式规范的完整功能验证. 支持 C 至 C18 和 C++ 至 C++20 的所有版本.  TrustInSoft Analyzer 将于 2023 年第二季度 (TCL3) 获得 ISO 26262 资格. 还捆绑了 MISRA C 检查器.

- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) — Vera++ 是一个用于验证、分析和转换 C++ 源代码的可编程工具.


<h2 id="clojure">克洛尤尔</h2>


- [clj-kondo](https://github.com/borkdude/clj-kondo)  — 激发欢乐的 Clojure 代码检查器. 它会在您打字时通知您潜在的错误.


<h2 id="coffeescript">咖啡脚本</h2>


- [coffeelint](https://coffeelint.github.io/) :warning: — 一个风格检查器，有助于保持 CoffeeScript 代码的干净和一致.


<h2 id="coldfusion">冷聚变</h2>


- [Fixinator](https://fixinator.app)  :copyright: — ColdFusion 或 CFML 代码的静态安全代码分析. 设计用于在 CI 管道内或从开发人员终端工作.


<h2 id="crystal">水晶</h2>


- [ameba](https://crystal-ameba.github.io) — Crystal 的静态代码分析工具.

- [crystal](https://crystal-lang.org) — Crystal 编译器具有内置的 linting 功能.


<h2 id="dart">镖</h2>


- [Dart Code Metrics](https://pub.dev/packages/dart_code_metrics)  — Dart 的额外 linter. 报告代码指标、检查反模式并为 Dart 分析器提供附加规则.

- [effective_dart](https://pub.dev/packages/effective_dart) :warning: — 与《Effective Dart》中的指南相对应的 Linter 规则

- [lint](https://github.com/passsy/dart-lint)  — 针对 Dart 和 Flutter 项目的一套固执己见、社区驱动的 lint 规则. 喜欢迂腐但更严格

- [Linter for dart](https://dart-lang.github.io/linter) — Dart 的样式 linter.


<h2 id="delphi">德尔福</h2>


- [Fix Insight](https://www.tmssoftware.com/site/fixinsight.asp)  :copyright: — 用于静态代码分析的免费 IDE 插件.  _Pro_ 版本包括用于自动化目的的命令行工具.

- [Pascal Analyzer](https://peganza.com/products_pal.html)  :copyright: — 具有大量报告的静态代码分析工具. 免费_Lite_版本提供有限的报告.

- [Pascal Expert](https://peganza.com/products_pex.html)  :copyright: — 用于代码分析的 IDE 插件. 包括 Pascal 分析器报告功能的子集，适用于 Delphi 2007 及更高版本.


<h2 id="dlang">当</h2>


- [D-scanner](https://github.com/dlang-community/D-Scanner) — D-Scanner是一个分析D源代码的工具.


<h2 id="elixir">灵丹妙药</h2>


- [credo](https://github.com/rrrene/credo) — 静态代码分析工具，重点关注代码一致性和教学.

- [dialyxir](https://github.com/jeremyjh/dialyxir) — 混合任务以简化 Elixir 项目中 Dialyzer 的使用.

- [sobelow](https://github.com/nccgroup/sobelow) — Phoenix 框架的以安全为中心的静态分析.


<h2 id="elm">榆树</h2>


- [elm-analyse](https://stil4m.github.io/elm-analyse) :warning: — 一个允许您分析 Elm 代码、识别缺陷并应用最佳实践的工具.

- [elm-review](https://package.elm-lang.org/packages/jfmengels/elm-review/latest) — 分析整个 Elm 项目，重点关注用 Elm 编写的可共享和自定义规则，这些规则添加了 Elm 编译器无法提供的保证.


<h2 id="erlang">埃尔兰</h2>


- [dialyzer](https://www.erlang.org/doc/man/dialyzer.html)  — DIALYZER，用于 ERlang 程序的差异分析器.  Dialyzer 是一个静态分析工具，可以识别单个 Erlang 模块或整个（组）应用程序中的软件差异，例如明确的类型错误、由于编程错误而死亡或无法访问的代码以及不必要的测试.
 Dialyzer 从调试编译的 BEAM 字节码或 Erlang 源代码开始分析. 报告差异的文件和行号以及差异的内容指示.  Dialyzer 的分析基于成功打字的概念，它允许发出声音警告（无误报）.

- [elvis](https://github.com/inaka/elvis) ——Erlang 风格评论家.

- [Primitive Erlang Security Tool (PEST)](https://github.com/okeuday/pest) — 一个对 Erlang 源代码进行基本扫描并报告任何可能导致 Erlang 源代码不安全的函数调用的工具.


<h2 id="fsharp">F#</h2>


- [FSharpLint](https://fsprojects.github.io/FSharpLint) — Lint tool for F#.


<h2 id="fortran">福特兰语言</h2>


- [fprettify](https://pypi.python.org/pypi/fprettify) — 现代 Fortran 源代码的自动格式化程序，用 Python 编写.
Fprettify 是一个在代码中提供一致的空格、缩进和分隔符对齐的工具，包括更改字母大小写和处理预处理器指令的能力，同时保留修订历史记录并测试编辑器集成.

- [i-Code CNES for Fortran](https://github.com/lequal/i-CodeCNES) — 适用于 Fortran 77、Fortran 90 和 Shell 的开源静态代码分析工具.


<h2 id="go">去</h2>


- [aligncheck](https://gitlab.com/opennota/check) — 查找低效打包的结构.

- [bodyclose](https://github.com/timakin/bodyclose) — 检查 HTTP 响应正文是否关闭.

- [deadcode](https://github.com/tsenart/deadcode) — 查找未使用的代码.

- [dingo-hunter](https://github.com/nickng/dingo-hunter) — 用于查找 Go 中死锁的静态分析器.

- [dogsled](https://github.com/alexkohler/dogsled) — 查找具有太多空白标识符的赋值/声明.

- [dupl](https://github.com/mibk/dupl) :warning: — 报告潜在的重复代码.

- [errcheck](https://github.com/kisielk/errcheck) — 检查是否使用了错误返回值.

- [errwrap](https://github.com/fatih/errwrap)  — 使用新的 %w 动词指令包装并修复 Go 错误. 该工具分析 fmt.Errorf() 调用并报告包含与 Go v1.13 中引入的新 %w 动词指令不同的动词指令的调用. 它还能够重写调用以使用新的 %w 换行动词指令.

- [flen](https://github.com/lafolle/flen) — 获取有关 Go 包中函数长度的信息.

- [Go Meta Linter](https://github.com/alecthomas/gometalinter)  :warning: — 同时运行 Go lint 工具并标准化其输出. 对新项目使用“golangci-lint”.

- [go tool vet --shadow](https://golang.org/cmd/vet#hdr-Shadowed_variables) — 报告可能被无意隐藏的变量.

- [go vet](https://golang.org/cmd/vet) — 检查 Go 源代码并报告可疑情况.

- [go-consistent](https://github.com/Quasilyte/go-consistent) — 分析器可帮助您使 Go 程序更加一致.

- [go-critic](https://github.com/go-critic/go-critic) — Go 源代码 linter，维护当前在其他 linter 中未实现的检查.

- [go/ast](https://golang.org/pkg/go/ast) —包ast声明了用于表示Go包语法树的类型.

- [gochecknoglobals](https://github.com/leighmcculloch/gochecknoglobals) — Checks that no globals are present.

- [goconst](https://github.com/jgautheron/goconst) — 查找可以用常量替换的重复字符串.

- [gocyclo](https://github.com/fzipp/gocyclo) — 计算 Go 源代码中函数的圈复杂度.

- [gofmt -s](https://golang.org/cmd/gofmt) — 检查代码格式是否正确且无法进一步简化.

- [gofumpt](https://github.com/mvdan/gofumpt)  — 强制执行比“gofmt”更严格的格式，同时向后兼容. 也就是说，“gofumpt”对“gofmt”满意的格式子集感到满意.
该工具是 Go 1.19 中 `gofmt` 的一个分支，需要 Go 1.18 或更高版本. 它可以用作格式化 Go 代码的直接替代品，并且在 gofumpt 之后运行 gofmt 应该不会产生任何变化.
 `gofumpt` 永远不会添加与 `gofmt` 格式不一致的规则. 所以我们扩展“gofmt”而不是与之竞争.

- [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) — 检查丢失或未引用的包导入.

- [gokart](https://github.com/praetorian-inc/gokart)  — Golang 安全分析，重点是最大限度地减少误报. 它能够追踪变量和函数参数的来源，以确定输入源是否安全.

- [GolangCI-Lint](https://golangci-lint.run) — `Go Meta Linter` 的替代方案：GolangCI-Lint 是一个 linters 聚合器.

- [golint](https://github.com/golang/lint) — 打印 Go 源代码中的编码风格错误.

- [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) — 同时运行许多 linter 并将其输出标准化为报告.

- [goroutine-inspect](https://github.com/linuxerwang/goroutine-inspect) — 一个用于分析 Golang goroutine dump 的交互式工具.

- [gosec (gas)](https://securego.io) — 通过扫描 Go AST 检查源代码是否存在安全问题.

- [gotype](https://pkg.go.dev/golang.org/x/tools/cmd/gotype) — 类似于Go编译器的语法和语义分析.

- [govulncheck](https://go.dev/blog/vuln)  — Govulncheck 报告影响 Go 代码的已知漏洞. 它使用源代码或二进制符号表的静态分析来将报告范围缩小到仅那些可能影响应用程序的报告.
默认情况下，govulncheck 向位于 https://vuln.go.dev 的 Go 漏洞数据库发出请求. 对漏洞数据库的请求仅包含模块路径，而不包含程序的代码或其他属性.

- [ineffassign](https://github.com/gordonklaus/ineffassign) — 检测 Go 代码中无效的赋值.

- [interfacer](https://github.com/mvdan/interfacer) :警告: — 建议可以使用的更窄的接口.

- [lll](https://github.com/walle/lll) :警告: — 报告排长队.

- [maligned](https://github.com/mdempsky/maligned) :warning: — 检测如果字段已排序则占用较少内存的结构.

- [misspell](https://github.com/client9/misspell) — 查找常见拼写错误的英语单词.

- [nakedret](https://github.com/alexkohler/nakedret) — 发现裸回报.

- [nargs](https://github.com/alexkohler/nargs) — 查找函数声明中未使用的参数.

- [prealloc](https://github.com/alexkohler/prealloc) — 查找可能被预分配的切片声明.

- [Reviewdog](https://github.com/haya14busa/reviewdog) — 用于发布来自任何代码托管服务中的任何 linter 的评论评论的工具.

- [revive](https://revive.run)  — 用于 Go 的快速、可配置、可扩展、灵活且美观的 linter.  golint 的直接替代品.

- [safesql](https://github.com/stripe/safesql) :warning: — Golang 静态分析工具，可防止 SQL 注入.

- [shisho](https://docs.shisho.dev/)  — 专为开发人员和安全团队设计的轻量级静态代码分析器. 它允许您使用类似于 sed 的直观 DSL 来分析和转换源代码，但针对的是代码.

- [staticcheck](https://staticcheck.io) — Go static analysis that specialises in finding bugs, simplifying code and improving performance.

- [structcheck](https://gitlab.com/opennota/check) — 查找未使用的结构字段.

- [structslop](https://github.com/orijtech/structslop) — Go 的静态分析器建议结构字段重新排列以提供最大的空间/分配效率

- [test](https://pkg.go.dev/testing) — 显示 stdlib 测试模块中测试失败的位置.

- [unconvert](https://github.com/mdempsky/unconvert) — 检测冗余类型转换.

- [unparam](https://github.com/mvdan/unparam) — 查找未使用的函数参数.

- [varcheck](https://gitlab.com/opennota/check) — 查找未使用的全局变量和常量.

- [wsl](https://github.com/bombsimon/wsl) — 在正确的位置强制执行空行.


<h2 id="groovy">格罗维</h2>


- [CodeNarc](https://codenarc.github.io/CodeNarc) — Groovy 源代码的静态分析工具，支持监控和执行许多编码标准和最佳实践.


<h2 id="haskell">哈斯克尔</h2>


- [brittany](https://github.com/lspitzner/brittany) — Haskell 源代码格式化程序

- [HLint](https://github.com/ndmitchell/hlint) — HLint 是一个用于建议 Haskell 代码可能改进的工具.

- [Liquid Haskell](https://ucsd-progsys.github.io/liquidhaskell-blog/) — Liquid Haskell 是 Haskell 程序的细化类型检查器.

- [Stan](https://kowainik.github.io/projects/stan) — Stan 是一个命令行工具，用于分析 Haskell 项目并以有用的方式输出发现的漏洞以及针对检测到的问题的可能解决方案.

- [Weeder](https://github.com/ocharles/weeder) — 用于检测 Haskell 代码中的无效导出或包导入的工具.


<h2 id="haxe">混合</h2>


- [Haxe Checkstyle](https://haxecheckstyle.github.io/docs/haxe-checkstyle/home.html) — 一种静态分析工具，可帮助开发人员编写符合编码标准的 Haxe 代码.


<h2 id="java">爪哇</h2>


- [Checker Framework](https://checkerframework.org) — Java 的可插入类型检查.

- [checkstyle](https://checkstyle.org) — 检查 Java 源代码是否遵守代码标准或验证规则集（最佳实践）.

- [ck](https://github.com/mauricioaniche/ck) — 通过处理源 Java 文件来计算 Chidamber 和 Kemerer 面向对象的指标.

- [ckjm](http://www.spinellis.gr/sw/ckjm) — 通过处理编译的 Java 文件的字节码来计算 Chidamber 和 Kemerer 面向对象的指标.

- [CogniCrypt](https://www.eclipse.org/cognicrypt) — 检查 Java 源代码和字节代码是否错误地使用了加密 API.

- [DesigniteJava](http://www.designite-tools.com/designitejava) :copyright: — DesigniteJava 支持检测各种架构、设计和实现气味以及计算各种代码质量指标.

- [Diffblue](https://www.diffblue.com/) ：版权： — Diffblue 是一家软件公司，为软件开发团队提供人工智能驱动的代码分析和测试解决方案.
其技术可帮助开发人员自动化测试、查找错误并减少软件开发过程中的体力劳动. 该公司的主要产品 Diffblue Cover 使用 AI 生成和运行 Java 代码的单元测试，有助于捕获错误并提高代码质量.

- [Doop](https://bitbucket.org/yanniss/doop)  — Doop 是一个用于 Java/Android 程序静态分析的声明式框架，以指针分析算法为中心.  Doop 提供了各种各样的分析以及周围的脚手架来运行端到端分析（事实生成、处理、统计等）.

- [Error-prone](https://errorprone.info) — 将常见的 Java 错误捕获为编译时错误.

- [fb-contrib](http://fb-contrib.sourceforge.net) — FindBugs 的插件，带有额外的错误检测器.

- [forbidden-apis](https://github.com/policeman-tools/forbidden-apis)  — 检测并禁止调用特定方法/类/字段（例如从没有字符集的文本流中读取）.  Maven/Gradle/Ant 兼容.

- [google-java-format](https://github.com/google/google-java-format) — 重新格式化 Java 源代码以符合 Google Java 风格

- [HuntBugs](https://github.com/amaembo/huntbugs) :警告: — 基于 Procyon 编译器工具的字节码静态分析器工具旨在取代 FindBugs.

- [IntelliJ IDEA](https://www.jetbrains.com/idea) :copyright: — 捆绑了许多针对 Java 和 Kotlin 的检查，并包含用于重构、格式化等的工具.

- [JArchitect](https://www.jarchitect.com) :copyright: — 测量、查询和可视化您的代码，避免意外问题、技术债务和复杂性.

- [JBMC](https://www.cprover.org/jbmc) — Java（字节码）的有界模型检查器，验证用户定义的断言、标准断言、多种覆盖率度量分析.

- [Mariana Trench](https://mariana-tren.ch/)  — 我们针对 Android 和 Java 应用程序的安全静态分析工具.  Mariana Trench 分析 Dalvik 字节码，旨在在大型代码库（数十百万行代码）上快速运行. 它可以在代码更改时发现漏洞，然后再将其放入存储库.

- [NullAway](https://github.com/uber/NullAway)  — 基于类型的空指针检查器，构建时间开销低； 一个 [Error Prone](http://errorprone.info/) 插入.

- [OWASP Dependency Check](https://owasp.org/www-project-dependency-check) — 检查依赖关系是否存在已知的、公开披露的漏洞.

- [qulice](https://www.qulice.com) — 结合了一些（预先配置的）静态分析工具（checkstyle、PMD、Findbugs...）.

- [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst) — 识别并优先考虑 Java 代码库中的上帝类和高度耦合类，您应该首先重构.

- [Soot](https://soot-oss.github.io/soot) — 用于分析和转换 Java 和 Android 应用程序的框架.

- [Spoon](https://spoon.gforge.inria.fr)  — Spoon 是一个元编程库，用于分析和转换 Java 源代码（包括 Java 9、10、11、12、13、14）. 它解析源文件以构建具有强大分析和转换 API 的精心设计的 AST. 可以集成到 Maven 和 Gradle 中.

- [SpotBugs](https://spotbugs.github.io)  — SpotBugs 是 FindBugs 的继任者. 一种静态分析工具，用于查找 Java 代码中的错误.

- [steady](https://eclipse.github.io/steady/) — 分析您的 Java 应用程序是否存在已知漏洞的开源依赖项，同时使用静态分析和测试来确定代码上下文和使用情况，以提高准确性.

- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  — 用于从静态代码分析中解析报告文件的 Java 库. 被大量 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="javascript">JavaScript</h2>


- [aether](http://aetherjs.com) :warning: — 在节点或浏览器中检查、分析、规范化、转换、沙箱、运行、单步执行和可视化用户 JavaScript.

- [Closure Compiler](https://developers.google.com/closure/compiler) — 一种编译器工具，可提高效率、减小大小并在 JavaScript 文件中提供代码警告.

- [ClosureLinter](https://github.com/google/closure-linter)  :warning: — 确保项目的所有 JavaScript 代码都遵循 Google JavaScript 样式指南中的准则. 它还可以自动修复许多常见错误.

- [complexity-report](https://github.com/escomplex/complexity-report) :警告: — JavaScript 项目的软件复杂性分析.

- [DeepScan](https://deepscan.io) :copyright: — JavaScript 分析器，其目标是运行时错误和质量问题，而不是编码约定.

- [es6-plato](https://github.com/the-simian/es6-plato) :warning: — 可视化 JavaScript (ES6) 源复杂性.

- [escomplex](https://github.com/jared-stilwell/escomplex) :警告: — JavaScript 系列抽象语法树的软件复杂性分析.

- [Esprima](https://esprima.org) :警告: — 用于多用途分析的 ECMAScript 解析基础设施.

- [flow](https://flow.org) — JavaScript 的静态类型检查器.

- [hegel](https://hegel.js.org) — JavaScript 的静态类型检查器，偏向于类型推断和强类型系统.

- [jshint](https://jshint.com/about) [:information_source:](https://github.com/analysis-tools-dev/static-analysis/blob/master/<https://github.com/analysis-tools-dev/static-analysis/issues/223>) — 检测 JavaScript 代码中的错误和潜在问题并强制执行团队的编码约定.

- [JSLint](https://github.com/douglascrockford/JSLint) [:information_source:](https://github.com/analysis-tools-dev/static-analysis/blob/master/<https://github.com/analysis-tools-dev/static-analysis/issues/223>) — JavaScript 代码质量工具.

- [JSPrime](https://dpnishant.github.io/jsprime) :warning: — 静态安全分析工具.

- [NodeJSScan](https://opensecurity.in)  — 用于 Node.js 应用程序的静态安全代码扫描器，由 libsast 和 semgrep 提供支持，构建于 njsscan cli 工具之上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.

- [plato](https://github.com/es-analysis/plato) :warning: — 可视化 JavaScript 源代码的复杂性.

- [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer) — Web 组件的静态分析框架.

- [Reshift](https://www.reshiftsecurity.com) :copyright: — 用于检测和管理 JavaScript 安全漏洞的源代码分析工具.

- [retire.js](https://retirejs.github.io/retire.js) — 扫描器检测具有已知漏洞的 JavaScript 库的使用情况.

- [RSLint](http://rslint.org/) :warning: — 用 Rust 编写的（WIP）JavaScript linter，旨在尽可能快、可定制且易于使用.

- [standard](http://standardjs.com) — 检查 Javascript 样式指南问题的 npm 模块.

- [tern](https://ternjs.net) — JavaScript 代码分析器，提供深入的跨编辑器语言支持.

- [TypL](https://typl.dev) :警告: — 使用 TypL，您只需编写完全标准的 JS，该工具就会通过强大的推理来找出您的类型.

- [xo](https://github.com/xojs/xo)  — 固执己见但可配置的 ESLint 包装器，其中包含许多好东西. 强制执行严格且可读的代码.

- [yardstick](https://github.com/calmh/yardstick) :warning: — Javascript 代码指标.


<h2 id="julia">朱莉娅</h2>


- [StaticLint](https://github.com/julia-vscode/StaticLint.jl) — Julia 的静态代码分析


<h2 id="kotlin">科特林</h2>


- [detekt](https://detekt.github.io/detekt) — Kotlin 代码的静态代码分析.

- [diktat](https://diktat.saveourtool.com) — Kotlin 的严格编码标准以及检测和自动修复代码异味的 linter.

- [ktfmt](https://facebook.github.io/ktfmt/) — 重新格式化 Kotlin 源代码以符合 Kotlin 代码约定的通用社区标准的程序.
 ktfmt IntelliJ 插件可从插件存储库中获取. 要安装它，请转到 IDE 的设置并选择插件类别. 单击 Marketplace 选项卡，搜索 ktfmt 插件，然后单击 Install 按钮.

- [ktlint](https://ktlint.github.io) — 带有内置格式化程序的防自行车脱落 Kotlin linter.


<h2 id="lua">二</h2>


- [luacheck](https://github.com/mpeterv/luacheck) :warning: — A tool for linting and static analysis of Lua code.

- [lualint](https://github.com/philips/lualint) — lualint 对 Lua 源代码中的全局变量使用情况进行基于 luac 的静态分析.

- [Luanalysis](https://plugins.jetbrains.com/plugin/14698-luanalysis) — 用于静态类型 Lua 开发的 IDE.


<h2 id="matlab">MATLAB</h2>


- [mlint](https://mathworks.com/help/matlab/ref/mlint.html) :copyright: — 检查 MATLAB 代码文件是否存在可能的问题.


<h2 id="nim">他</h2>


- [DrNim](https://nim-lang.org/docs/drnim.html) — DrNim 将 Nim 前端与 Z3 证明引擎相结合，以便验证/验证用 Nim 编写的软件.

- [nimfmt](https://github.com/FedericoCeratto/nimfmt) :warning: — Nim 代码格式化程序/linter/样式检查器


<h2 id="ocaml">奥卡梅尔</h2>


- [Sys](https://github.com/PLSysSec/sys)  — 用于查找（浏览器）代码中的错误的静态/符号工具. 它使用 LLVM AST 来查找诸如未初始化内存访问之类的错误.

- [VeriFast](https://github.com/verifast/verifast)  — 用于对单线程和多线程 C 和 Java 程序的正确性进行模块化形式验证的工具，用分离逻辑编写的前置条件和后置条件进行注释. 为了表达丰富的规范，程序员可以定义归纳数据类型、这些数据类型上的原始递归纯函数以及抽象分离逻辑谓词.


<h2 id="php">PHP</h2>


- [churn-php](https://github.com/bmitch/churn-php) — 帮助发现重构的良好候选者.

- [dephpend](https://github.com/mihaeu/dephpend) — 依赖性分析工具.

- [deprecation-detector](https://github.com/sensiolabs-de/deprecation-detector) — 查找已弃用的 (Symfony) 代码的用法.

- [deptrac](https://github.com/sensiolabs-de/deptrac) — 强制执行软件层之间依赖关系的规则.

- [DesignPatternDetector](https://github.com/Halleck45/DesignPatternDetector) — PHP 代码中设计模式的检测.

- [EasyCodingSt和ard](https://www.tomasvotruba.com/blog/2017/05/03/combine-power-of-php-code-sniffer-和-php-cs-fixer-in-3-lines) - 结合 [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 和 [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).

- [Enlightn](https://www.laravel-enlightn.com/)  — Laravel 应用程序的静态和动态分析工具，提供提高 Laravel 应用程序的性能、安全性和代码可靠性的建议. 包含 120 项自动检查.

- [exakat](https://www.exakat.io) — PHP 的自动代码审查引擎.

- [GrumPHP](https://github.com/phpro/grumphp) — 检查每次提交的代码.

- [larastan](https://github.com/nunomaduro/larastan)  — 向 Laravel 添加静态分析，提高开发人员的工作效率和代码质量. 它是 PHPStan 的包装器.

- [Mondrian](https://trismegiste.github.io/Mondrian) :警告: — 一组使用图论的静态分析和重构工具.

- [Nitpick CI](https://nitpick-ci.com) :copyright: — 自动 PHP 代码审查.

- [parallel-lint](https://github.com/php-parallel-lint/PHP-Parallel-Lint) — 该工具检查 PHP 文件的语法比串行检查更快，输出更精美.

- [Parse](https://github.com/psecio/parse) — 静态安全扫描器.

- [pdepend](https://pdepend.org) — 计算 PHP 代码的圈复杂度等软件指标.

- [phan](https://github.com/phan/phan/wiki) — etsy 的现代静态分析器.

- [PHP Architecture Tester](https://github.com/carlosas/phpat) — 易于使用的 PHP 架构测试工具.

- [PHP Assumptions](https://github.com/rskuipers/php-assumptions) — 检查薄弱的假设.

- [PHP Coding Standards Fixer](https://cs.symfony.com) — 根据 PSR-1、PSR-2 和 Symfony 标准等标准修复您的代码.

- [PHP Insights](https://phpinsights.com)  — 从控制台进行即时 PHP 质量检查. 分析代码质量和编码风格以及代码架构及其复杂性概述.

- [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-) — PHP 静态代码分析器.

- [PHP Refactoring Browser](https://qafoolabs.github.io/php-refactoring-browser) — 重构助手.

- [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) — 根据语义版本控制建议下一个版本.

- [PHP-Parser](https://github.com/nikic/PHP-Parser) — 用 PHP 编写的 PHP 解析器.

- [php-speller](https://github.com/mekras/php-speller) — PHP 拼写检查库.

- [PHP-Token-Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) :warning: — 模拟 PHP 内部反射的库.

- [php7cc](https://github.com/sstalle/php7cc) :警告: — PHP 7 兼容性检查器.

- [php7mar](https://github.com/Alexia/php7mar) :warning: — 帮助开发者快速将代码移植到 PHP 7.

- [PHP_CodeSniffer](https://pear.php.net/package/PHP_CodeSniffer) — 检测对一组定义的编码标准的违反.

- [phpca](https://github.com/wapmorgan/PhpCodeAnalyzer) — 查找非内置扩展的使用情况.

- [phpcpd](https://github.com/sebastianbergmann/phpcpd) — PHP 代码的复制/粘贴检测器.

- [phpdcd](https://github.com/sebastianbergmann/phpdcd) :警告: — PHP 代码的死代码检测器 (DCD).

- [PhpDependencyAnalysis](https://mamuz.github.io/PhpDependencyAnalysis) :warning: — 为项目构建依赖关系图.

- [PhpDeprecationDetector](https://github.com/wapmorgan/PhpDeprecationDetector)  — PHP 代码分析器，用于搜索较新解释器版本中已弃用功能的问题. 它查找已删除的对象（函数、变量、常量和 ini 指令）、已弃用的函数功能以及禁止名称或技巧的使用（例如，新版本中的保留标识符）.

- [phpdoc-to-typehint](https://github.com/dunglas/phpdoc-to-typehint) :warning: — 使用 PHPDoc 注释向现有 PHP 项目添加标量类型提示和返回类型.

- [phpDocumentor](https://www.phpdoc.org) — 分析 PHP 源代码以生成文档.

- [phploc](https://github.com/sebastianbergmann/phploc) — 快速测量 PHP 项目大小并分析其结构的工具.

- [PHPMD](https://phpmd.org) — 查找代码中可能存在的错误.

- [PhpMetrics](http://www.phpmetrics.org) — 计算并可视化各种代码质量指标.

- [phpmnd](https://github.com/povils/phpmnd) — 帮助检测幻数.

- [PHPQA](https://edgedesigncz.github.io/phpqa) — 用于运行 QA 工具（phploc、phpcpd、phpcs、pdepend、phpmd、phpmetrics）的工具.

- [phpqa - jakzal](https://github.com/jakzal/phpqa) — 在一个容器中提供多种 PHP 静态分析工具.

- [phpqa - jmolivas](https://github.com/jmolivas/phpqa) — PHPQA 一体化分析器 CLI 工具.

- [phpsa](https://github.com/ovr/phpsa) :warning: — PHP 静态分析工具.

- [PHPStan](https://phpstan.org) — PHP 静态分析工具 - 无需运行代码即可发现代码中的错误！

- [Progpilot](https://github.com/designsecurity/progpilot) — 用于安全目的的静态分析工具.

- [Psalm](https://psalm.dev) — 用于查找 PHP 应用程序中类型错误的静态分析工具.

- [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) :warning: — 可视化指标和源代码.

- [rector](https://getrector.org)  — 任何 PHP 5.3+ 代码的即时升级和自动重构. 它将您的代码升级为 PHP 7.4、8.0 及更高版本.  Rector 承诺较低的误报率，因为它寻找狭义定义的 AST（抽象语法树）模式. 主要用例是解决遗留代码中的技术债务并删除死代码.  Rector 为 Symfony、Doctrine、PHPUnit 等提供了一组特殊规则.

- [Reflection](https://github.com/phpDocumentor/Reflection) — 用于对 PHP 项目进行静态分析的反射库

- [Symfony Insight](https://insight.symfony.com/) :copyright: — 检测安全风险、查找错误并为 PHP 项目提供可操作的指标.

- [Tuli](https://github.com/ircmaxell/Tuli) — 静态分析引擎.

- [twig-lint](https://github.com/asm89/twig-lint) — twig-lint 是一个针对 twig 文件的 lint 工具.

- [WAP](https://securityonline.info/owasp-wap-web-application-protection-project) — 用于检测和纠正 PHP（4.0 或更高版本）Web 应用程序中的输入验证漏洞的工具，并通过结合静态分析和数据挖掘来预测误报.


<h2 id="plsql">PL/SQL</h2>


- [ZPA](https://felipezorzo.com.br/zpa/)  — Z PL/SQL 分析器 (ZPA) 是用于 PL/SQL 和 Oracle SQL 的可扩展代码分析器. 它可以与 SonarQube 集成.


<h2 id="perl">珀尔</h2>


- [Perl::Analyzer](https://technix.github.io/Perl-Analyzer/) — Perl-Analyzer is a set of programs and modules that allow users to analyze and visualize Perl  codebases by providing information about namespaces and their relations, dependencies,  inheritance, and methods implemented, inherited, and redefined in packages,  as well as calls to methods from parent packages via SUPER. 

- [Perl::Critic](https://metacpan.org/pod/Perl::Critic) — 批判 Perl 源代码以获得最佳实践.

- [perltidy](https://perltidy.sourceforge.net/) — Perltidy 是一个 Perl 脚本，它可以缩进并重新格式化 Perl 脚本以使其更易于阅读. 
可以使用命令行参数来控制格式. 默认参数设置大致遵循 Perl 样式指南中的建议. 
除了重新格式化脚本之外，Perltidy 还可以在追踪缺少或多余大括号、圆括号和方括号的错误方面提供很大帮助，因为它非常擅长定位错误.

- [zarn](https://github.com/htrgouvea/zarn) — 现代 Perl 应用程序的轻量级静态安全分析工具


<h2 id="python">Python</h2>


- [autoflake](https://github.com/PyCQA/autoflake) — Autoflake 从 Python 代码中删除未使用的导入和未使用的变量.

- [autopep8](https://pypi.org/project/autopep8/) — 一种自动格式化 Python 代码以符合 PEP 8 风格指南的工具.
它使用 pycodestyle 实用程序来确定代码的哪些部分需要格式化.

- [bandit](https://bandit.readthedocs.io/en/latest) — 查找 Python 代码中常见安全问题的工具.

- [bellybutton](https://github.com/hchasestevens/bellybutton) — 支持自定义项目特定规则的 linting 引擎.

- [Black](https://black.readthedocs.io/en/stable) — 毫不妥协的 Python 代码格式化程序.

- [Bowler](https://pybowler.io/)  — 现代 Python 的安全代码重构.  Bowler 是一个用于在语法树级别操作 Python 的重构工具. 它支持安全、大规模的代码修改，同时保证生成的代码可以编译和运行. 它提供了简单的命令行界面和流畅的Python API，用于在代码中生成复杂的代码修改.

- [ciocheck](https://github.com/ContinuumIO/ciocheck)  :warning: — Linter、格式化程序和测试套件帮助程序. 作为一个 linter，它是 `pep8`、`pydocstyle`、`flake8` 和 `pylint` 的包装器.

- [cohesion](https://github.com/mschwager/cohesion) — 用于测量 Python 类内聚力的工具.

- [deal](https://deal.readthedocs.io/)  — 通过 Python 合约进行设计. 编写无错误的代码. 通过在代码中添加一些装饰器，您可以获得免费测试、静态分析、形式验证等等.

- [Dlint](https://github.com/dlint-py/dlint) — 确保 Python 代码安全的工具.

- [Dodgy](https://github.com/landscapeio/dodgy)  — Dodgy 是一个非常基本的工具，可以针对您的代码库运行以搜索看起来“狡猾”的值. 它是一系列简单的正则表达式，旨在检测诸如意外的 SCM 差异签入、硬编码到文件中的密码或密钥等情况.

- [fixit](https://pypi.org/project/fixit) — 用于为源代码创建 lint 规则和相应自动修复的框架.

- [flake8](https://github.com/PyCQA/flake8) — `pyflakes`、`pycodestyle` 和 `mccabe` 的​​包装.

- [InspectorTiger](https://github.com/thg-consulting/it)  :警告: — IT，Inspector Tiger，是一个现代 Python 代码审查工具/框架. 它附带了一堆预定义的处理程序，可以警告您有关改进和可能的错误. 除了这些处理程序之外，您还可以编写自己的处理程序或使用社区处理程序.

- [jedi](https://jedi.readthedocs.io/en/latest) — Python 的自动完成/静态分析库.

- [linty fresh](https://github.com/lyft/linty_fresh) — 解析 lint 错误并将其作为拉取请求的评论报告给 Github.

- [mccabe](https://pypi.org/project/mccabe) — 检查 McCabe 的复杂性.

- [multilint](https://github.com/adamchainz/multilint) :warning: — `flake8`、`isort` 和 `modernize` 的包装.

- [mypy](http://www.mypy-lang.org) — 静态类型检查器，旨在结合鸭子类型和静态类型的优点，经常与 [MonkeyType](https://github.com/Instagram/MonkeyType).

- [prospector](https://github.com/PyCQA/prospector) — `pylint`、`pep8`、`mccabe` 等的包装.

- [py-find-injection](https://github.com/uber/py-find-injection) :warning: — 查找 Python 代码中的 SQL 注入漏洞.

- [pyanalyze](https://pyanalyze.readthedocs.io/en/latest/)  — 一种以编程方式检测 Python 代码中常见错误的工具，例如对未定义变量的引用和类型错误. 它可以扩展以添加额外的规则并执行特定于特定功能的检查.

- [PyCodeQual](https://pycodequ.al)  :copyright: — PyCodeQual 让您深入了解复杂性和错误风险. 它会为您的拉取请求添加自动审查.

- [pycodestyle](https://pycodestyle.pycqa.org/en/latest) —（以前称为“pep8”）根据 PEP 8 中的一些样式约定检查 Python 代码.

- [pydocstyle](http://www.pydocstyle.org) — 检查是否符合 Python 文档字符串约定.

- [pyflakes](https://pypi.org/project/pyflakes) — 检查 Python 源文件是否有错误.

- [pylint](http://pylint.pycqa.org/en/latest)  — 查找编程错误，帮助执行编码标准并嗅出一些代码异味. 它还包括“pyreverse”（UML 图生成器）和“symilar”（相似性检查器）.

- [pyre-check](https://pyre-check.org) — 适用于大型 Python 代码库的快速、可扩展的类型检查器.

- [pyright](https://github.com/Microsoft/pyright) - Python 的静态类型检查器，旨在解决 mypy 等现有工具中的缺陷.

- [pyroma](https://github.com/regebro/pyroma) — 评估 Python 项目符合 Python 打包生态系统最佳实践的情况，并列出可以改进的问题.

- [Pysa](https://pyre-check.org/docs/pysa-basics.html) — 一个基于 Facebook 的 Pyre-Check 的工具，用于识别通过污点分析识别的 Python 代码中的潜在安全问题.

- [PyT - Python Taint](https://github.com/python-security/pyt) :warning: — 用于检测 Python Web 应用程序中的安全漏洞的静态分析工具.

- [pytype](https://google.github.io/pytype) — Python 代码的静态类型分析器.

- [pyupgrade](https://pypi.org/project/pyupgrade-docs/) — 一个工具（和预提交挂钩），用于自动升级该语言新版本的语法.

- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode)  :警告: — 自动代码审查和修复. 它可以帮助您跟踪软件项目中的问题和指标，并且可以轻松扩展以支持新型分析.

- [radon](https://radon.readthedocs.io/en/latest) — 一个从源代码计算各种指标的 Python 工具.

- [refurb](https://github.com/dosisod/refurb)  — 用于翻新和现代化 Python 代码库的工具.  Refurb 很大程度上受到了 Clippy（Rust 的内置 linter）的启发.

- [ruff](https://astral.sh/ruff)  — 快速 Python linter，用 Rust 编写. 比现有的 linter 快 10-100 倍. 与Python 3.10兼容. 支持文件观察器.

- [unimport](https://unimport.hakancelik.dev) — 用于查找和删除未使用的导入语句的 linter、格式化程序.

- [vulture](https://github.com/jendrikseipp/vulture) — 查找 Python 代码中未使用的类、函数和变量.

- [wemake-python-styleguide](https://wemake-python-styleguide.rtfd.io/) — 有史以来最严格、最固执己见的 python linter.

- [wily](https://github.com/tonybaloney/wily) — 用于归档、探索和绘制 Python 源代码复杂性的命令行工具.

- [xenon](https://xenon.readthedocs.io) — 使用以下方式监控代码复杂性 [`radon`](https://github.com/rubik/radon).

- [yapf](https://github.com/google/yapf) — Google 创建的 Python 文件格式化程序
 YAPF 遵循一种独特的方法，该方法源自 Daniel Jasper 创建的“clang-format”工具. 本质上，程序将代码重新构建为遵守样式指南的最合适的格式，即使原始代码已经遵循样式指南. 这个概念类似于 Go 编程语言的“gofmt”工具，该工具旨在通过让项目的整个代码库在发生更改时都通过 YAPF 来结束有关格式的争论，从而在整个项目中保持一致的风格，并消除在每次代码审查中争论风格的需要.


<h2 id="r">右</h2>


- [cyclocomp](https://github.com/MangoTheCat/cyclocomp) — 量化 R 函数/表达式的圈复杂度.

- [goodpractice](https://mangothecat.github.io/goodpractice) — 分析 R 包的源代码并提供最佳实践建议.

- [lintr](https://github.com/jimhester/lintr) — R 的静态代码分析.

- [styler](https://styler.r-lib.org) — R 源代码文件的格式化和 R 代码的漂亮打印.


<h2 id="rego">沟</h2>


- [Regal](https://github.com/styrainc/regal)  — Regal 是策略语言 Rego 的 linter.  Regal 的目标是发现策略代码中的 bug 和错误，同时帮助人们学习语言、最佳实践和惯用结构.


<h2 id="ruby">红宝石</h2>


- [brakeman](https://brakemanscanner.org) — 用于 Ruby on Rails 应用程序的静态分析安全漏洞扫描器.

- [bundler-audit](https://github.com/rubysec/bundler-audit) — 审核 Gemfile.lock 中报告的存在安全漏洞的 gem [Ruby Advisory Database](https://github.com/rubysec/ruby-advisory-db).

- [cane](https://github.com/square/cane) :warning: — 代码质量阈值检查作为构建的一部分.

- [Churn](https://github.com/danmayer/churn)  :warning: — 为给定签入的项目提供流失文件、类和方法的项目. 随着时间的推移，该工具会累加改动的历史记录，以给出文件、类或方法在项目生命周期内更改的次数.

- [dawnscanner](https://github.com/thesp0nge/dawnscanner)  — 用于 ruby​​ 编写的 Web 应用程序的静态分析安全扫描器. 它支持 Sinatra、Padrino 和 Ruby on Rails 框架.

- [ERB Lint](https://github.com/Shopify/erb-lint) — 检查您的 ERB 或 HTML 文件

- [Fasterer](https://github.com/DamirSvrtan/fasterer) — 常见 Ruby 习语检查器.

- [flay](https://ruby.sadi.st/Flay.html) — Flay 分析代码的结构相似性.

- [flog](https://ruby.sadi.st/Flog.html)  — Flog 在一份易于阅读的痛苦报告中报告了最受折磨的代码. 分数越高，代码就越痛苦.

- [Fukuzatsu](https://github.com/CoralineAda/fukuzatsu)  — 用于测量 Ruby 类文件中代码复杂性的工具. 其分析根据圈复杂度算法生成分数，没有添加“意见”.

- [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)  — HTML 的规范化器/美化器，也理解嵌入式 Ruby. 非常适合整理 Rails 模板.

- [laser](https://github.com/michaeledgar/laser) :warning: — Ruby 代码的静态分析和样式 linter.

- [MetricFu](https://github.com/metricfu/metric_fu) :警告: — MetricFu 是一组工具，用于提供报告，显示代码的哪些部分可能需要额外的工作.

- [pelusa](https://github.com/codegram/pelusa) — 静态分析 Lint 类型的工具，用于改进您的 OO Ruby 代码.

- [quality](https://github.com/apiology/quality) — Runs quality checks on your code using community tools, and makes sure your numbers don't get any worse over time.

- [Querly](https://github.com/soutaro/querly) :warning: — Ruby 的基于模式的检查工具.

- [Railroader](https://railroader.org) :警告: — 用于 Ruby on Rails 应用程序的开源静态分析安全漏洞扫描程序.

- [rails_best_practices](https://rails-bestpractices.com) — Rails 项目的代码度量工具

- [reek](https://github.com/troessner/reek) — Ruby 代码气味检测器.

- [Roodi](https://github.com/roodi/roodi)  :警告: — Roodi 代表 Ruby 面向对象设计 Inferometer. 它会解析您的 Ruby 代码，并根据其配置的检查向您发出有关设计问题的警告.

- [RuboCop](https://docs.rubocop.org/rubocop) — Ruby 静态代码分析器，基于社区 Ruby 风格指南.

- [Rubrowser](https://github.com/blazeeboy/rubrowser) — Ruby 类交互式依赖图生成器.

- [ruby-lint](http://code.yorickpeterse.com/ruby-lint/latest) :warning: — Ruby 的静态代码分析.

- [rubycritic](https://github.com/whitesmith/rubycritic) — Ruby 代码质量报告者.

- [rufo](https://github.com/ruby-formatter/rufo) — 一个固执己见的 ruby​​ 格式化程序，旨在通过命令行作为文本编辑器插件使用，在保存或按需时自动格式化文件.

- [Saikuro](https://metricfu.github.io/Saikuro) :warning: — Ruby 圈复杂度分析器.

- [SandiMeter](https://rubygems.org/gems/sandi_meter) :warning: — 用于检查 Ruby 代码是否符合 Sandi Metz 规则的静态分析工具.

- [Sorbet](https://sorbet.org) — 专为 Ruby 设计的快速、强大的类型检查器.

- [Standard Ruby](https://github.com/testdouble/standard) — Ruby 风格指南，带有 linter 和自动代码修复程序

- [Steep](https://github.com/soutaro/steep) — Ruby 的渐进式打字.


<h2 id="rust">锈</h2>


- [C2Rust](https://c2rust.com)  — C2Rust 帮助您将符合 C99 的代码迁移到 Rust. 翻译器（或转译器）生成与输入 C 代码密切相关的不安全 Rust 代码.

- [cargo udeps](https://github.com/est31/cargo-udeps)  — 在 Cargo.toml 中查找未使用的依赖项. 它要么打印出“未使用的板条箱”行，列出板条箱，要么打印出一行，说明没有未使用的板条箱.

- [cargo-audit](https://rustsec.org) — 审核 Cargo.lock 是否存在安全漏洞，并报告给了 [RustSec Advisory Database](https://github.com/RustSec/advisory-db/).

- [cargo-bloat](https://github.com/RazrFalcon/cargo-bloat)  — 找出可执行文件中占用大部分空间的内容. 支持 ELF（Linux、BSD）、Mach-O（macOS）和 PE（Windows）二进制文件.

- [cargo-breaking](https://github.com/iomentum/cargo-breaking) ——cargo-breaking 比较两个不同分支之间的 crate 公共 API，显示更改的内容，并根据 semver 建议下一个版本.

- [cargo-call-stack](https://github.com/japaric/cargo-call-stack) — 整个程序静态堆栈分析 该工具将程序的完整调用图生成为点文件.

- [cargo-deny](https://embarkstudios.github.io/cargo-deny)  — 用于检查依赖项的货物插件. 它也可以用作命令行、Rust crate 或 CI 的 Github 操作. 它检查有效的许可证信息、重复的包、安全漏洞等等.

- [cargo-expand](https://github.com/dtolnay/cargo-expand) — Cargo subcommand to show result of macro expansion  and #[derive] expansion applied to the current crate.  This is a wrapper around a more verbose compiler command.

- [cargo-inspect](https://github.com/mre/cargo-inspect) — 在没有语法糖的情况下检查 Rust 代码，看看编译器在幕后做了什么.

- [cargo-show-asm](https://github.com/pacak/cargo-show-asm) — Cargo 子命令显示为 Rust 代码生成的程序集、LLVM-IR 和 MIR

- [cargo-spellcheck](https://github.com/drahnr/cargo-spellcheck) — 使用 hunspell（就绪）和 languagetool（预览）检查所有文档中的拼写和语法错误

- [cargo-unused-features](https://github.com/TimonPost/cargo-unused-features)  — 查找潜在未使用的启用功能标志并修剪它们. 您可以从 json 生成简单的 HTML 报告，以便更轻松地检查结果.
它删除依赖项的功能，然后编译项目以查看它是否仍然可以编译. 如果是这样，功能标志可能会被删除，但它可能是误报.

- [clippy](https://rust-lang.github.io/rust-clippy) — 代码检查器，用于捕获常见错误并改进 Rust 代码.

- [diff.rs](https://diff.rs) — Web 应用程序 (WASM) 用于呈现 Rust 板条箱版本之间的差异.

- [dylint](https://www.trailofbits.com/post/write-rust-lints-without-forking-clippy)  — 用于从动态库运行 Rust lint 的工具.  Dylint 使开发人员可以轻松维护自己的个人 lint 集合.

- [electrolysis](https://kha.github.io/electrolysis) :warning: — 一种通过将 Rust 程序转换为精益定理证明器中的定义来正式验证 Rust 程序的工具.

- [herbie](https://github.com/mcarton/rust-herbie-lint) :warning: — 在使用数值不稳定的浮点表达式时向您的 crate 添加警告或错误.

- [linter-rust](https://github.com/AtomLinter/linter-rust) :warning: — Linting your Rust-files in Atom, using rustc and cargo.

- [lockbud](https://github.com/BurtonQin/lockbud)  — 静态检测 Rust 死锁错误. 它目前检测两种常见的死锁错误：双锁和冲突顺序锁. 它将以 JSON 格式打印错误以及源代码位置和每个错误的解释.

- [MIRAI](https://github.com/facebookexperimental/MIRAI) — 抽象解释器在 Rust 的中级中间语言上运行，并提供基于污点分析的警告.

- [prae](https://github.com/teenjuna/prae) — 提供一个方便的宏，允许您生成类型包装器，承诺始终支持您指定的任意不变量. 

- [Prusti](https://www.pm.inf.ethz.ch/research/prusti.html)  — Rust 的静态验证器，基于 Viper 验证基础设施. 默认情况下，Prusti 通过证明诸如 unreachable!() 和 panic!() 之类的语句无法访问来验证是否存在恐慌.

- [Rudra](https://github.com/sslab-gatech/Rudra)  :警告: — Rust 内存安全和未定义行为检测. 它能够分析单个 Rust 包以及 crates.io 上的所有包.

- [Rust Language Server](https://github.com/rust-lang-nursery/rls) — 支持“转到定义”、符号搜索、重新格式化和代码完成等功能，并支持重命名和重构.

- [rust-analyzer](https://rust-analyzer.github.io) — 支持“转到定义”、类型推断、符号搜索、重新格式化和代码完成等功能，并支持重命名和重构.

- [rust-audit](https://github.com/Shnatsel/rust-audit)  — 审核 Rust 二进制文件是否存在已知错误或安全漏洞. 这是通过将 JSON 格式的依赖树 (Cargo.lock) 相关数据嵌入到已编译可执行文件的专用链接器部分来实现的.

- [rustfix](https://github.com/rust-lang/rustfix) :warning: — 阅读并应用 rustc 提出的建议（以及第三方 lint，如 Clippy 提供的建议）.

- [rustfmt](https://github.com/rust-lang/rustfmt) — 根据样式指南格式化 Rust 代码的工具.

- [RustViz](https://github.com/rustviz/rustviz)  — RustViz 是一个从简单的 Rust 程序生成可视化效果的工具，以帮助用户更好地理解 Rust 生命周期和借用机制. 它生成带有图形指示器的 SVG 文件，这些文件与 mdbook 集成以呈现 Rust 程序中数据流的可视化.

- [warnalyzer](https://github.com/est31/warnalyzer) — Show unused code from multi-crate Rust projects


<h2 id="sql">SQL</h2>


- [dbcritic](https://github.com/channable/dbcritic) — dbcritic 发现数据库模式中的问题，例如表中缺少主键约束.

- [holistic](https://holistic.dev/)  — 超过 1,300 条用于分析 SQL 查询的规则. 采用 SQL 架构定义和查询源代码来生成改进建议. 检测代码气味、未使用的索引、未使用的表、视图、物化视图等.

- [sleek](https://github.com/nrempel/sleek)  — Sleek 是一个用于格式化 SQL 的 CLI 工具. 它可以帮助您在 SQL 代码中保持一致的风格，从而提高可读性和生产力. 繁重的工作是由 sqlformat 包完成的.

- [sqlcheck](https://github.com/jarulraj/sqlcheck) :warning: — 自动识别 SQL 查询中的反模式.

- [SQLFluff](https://www.sqlfluff.com/) — 多种方言 SQL linter 和格式化程序.

- [sqlint](https://github.com/purcell/sqlint) — 简单的 SQL linter.

- [squawk](https://squawkhq.com)  — 用于 PostgreSQL 的 Linter，专注于迁移. 防止因数据库迁移导致的意外停机，并鼓励围绕 Postgres 架构和 SQL 的最佳实践.

- [tsqllint](https://github.com/tsqllint/tsqllint) — T-SQL 特定的 linter.

- [TSqlRules](https://github.com/ashleyglee/TSqlRules) :warning: — SQL Server 的 TSQL 静态代码分析规则.

- [Visual Expert](https://www.visual-expert.com) :copyright: — PowerBuilder、Oracle 和 SQL Server 的代码分析 探索、分析和记录代码 


<h2 id="scala">斯卡拉</h2>


- [linter](https://github.com/HairyFotr/linter) :警告: — Linter 是一个 Scala 静态分析编译器插件，它添加了针对各种可能的错误、低效率和样式问题的编译时检查.

- [Scalastyle](http://www.scalastyle.org) — Scalastyle 检查您的 Scala 代码并指出潜在的问题.

- [scapegoat](https://github.com/sksamuel/scapegoat) — 用于静态代码分析的 Scala 编译器插件.

- [WartRemover](https://www.wartremover.org) — 灵活的 Scala 代码检查工具.


<h2 id="shell">壳</h2>


- [bashate](https://github.com/openstack/bashate)  — bash 程序的代码风格强制执行. 输出格式旨在遵循 pycodestyle (pep8) 默认输出格式.

- [i-Code CNES for Shell](https://github.com/lequal/i-CodeCNES) — 用于 Shell 和 Fortran（77 和 90）的开源静态代码分析工具.

- [kmdr](https://github.com/ediardo/kmdr-cli)  — 用于从终端学习命令的 CLI 工具.  kmdr 提供了命令的详细信息，并解释了每个属性.

- [sh](https://pkg.go.dev/mvdan.cc/sh/v3)  — 支持 bash 的 shell 解析器、格式化程序和解释器； 包括转移

- [shellcheck](https://www.shellcheck.net) — ShellCheck，一个静态分析工具，可为 bash/sh shell 脚本提供警告和建议.

- [shellharden](https://github.com/anordal/shellharden) — 语法荧光笔和半自动重写脚本以符合 ShellCheck 的工具，主要侧重于引用.


<h2 id="swift">迅速</h2>


- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) — 用于重新格式化 Swift 代码的库和命令行格式化工具.

- [SwiftLint](https://realm.github.io/SwiftLint) — 强制执行 Swift 风格和约定的工具.

- [Tailor](https://sleekbyte.github.io/tailor) :warning: — 一个静态分析和 lint 工具，用于用 Apple 的 Swift 编程语言编写的源代码.


<h2 id="tcl">铊</h2>


- [Frink](http://catless.ncl.ac.uk/Programs/Frink) — Tcl 格式化和静态检查程序（可以美化程序、最小化、混淆或只是进行健全性检查）.

- [Nagelfar](https://sourceforge.net/projects/nagelfar) — Tcl 的静态语法检查器.

- [tclchecker](https://github.com/ActiveState/tdk/blob/master/docs/3.0/TDK_3.0_Checker.txt) — 静态语法分析模块（作为 [TDK](https://github.com/ActiveState/tdk)).


<h2 id="typescript">打字稿</h2>


- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) — 用于 Angular 项目的 Linter

- [Codelyzer](http://codelyzer.com) :warning: — 一组用于 Angular 2 TypeScript 项目静态代码分析的 tslint 规则.

- [stc](https://stc.dudy.dev) — 用 Rust 编写的 Speedy TypeScript 类型检查器

- [tslint](https://palantir.github.io/tslint/) :warning: — TSLint has been deprecated as of 2019. Please see [this issue](https://github.com/palantir/tslint/issues/4534) 更多细节.  `typescript-eslint` 现在是检查 TypeScript 的最佳选择.
 TSLint 是一个可扩展的静态分析工具，用于检查 TypeScript 代码的可读性、可维护性和功能错误. 它在现代编辑器和构建系统中得到广泛支持，并且可以使用您自己的 lint 规则、配置和格式化程序进行自定义.

- [tslint-clean-code](https://www.npmjs.com/package/tslint-clean-code) — 一组受《清洁代码手册》启发的 TSLint 规则.

- [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib) :warning: — 由 Microsoft 维护的一组用于 TypeScript 项目静态代码分析的 tslint 规则.

- [TypeScript Call Graph](https://github.com/whyboris/TypeScript-Call-Graph) — CLI 用于从 TypeScript 文件生成函数和调用的交互式图表

- [TypeScript ESLint](https://github.com/typescript-eslint/typescript-eslint) — eslint 的 TypeScript 语言扩展.

- [zod](https://zod.dev)  — 使用静态类型推断进行 TypeScript 优先模式验证. 目标是消除重复的类型声明. 使用 Zod，您声明一次验证器，Zod 将自动推断静态 TypeScript 类型. 将更简单的类型组合成复杂的数据结构很容易.


<h2 id="verilog">Verilog/系统Verilog</h2>


- [Icarus Verilog](https://github.com/steveicarus/iverilog) — Verilog 仿真和综合工具，通过将以 IEEE-1364 Verilog 编写的源代码编译为某种目标格式来运行

- [svls](https://github.com/dalance/svls) — Verilog 和 SystemVerilog 的语言服务器协议实现，包括 lint 功能.

- [verible-linter-action](https://github.com/chipsalliance/verible-linter-action) — 在 Verible 的帮助下在 github 操作中自动进行 SystemVerilog linting 用于对 Verilog 和 SystemVerilog 源文件进行 lint 并自动注释 Pull 请求中的错误代码行.

- [Verilator](https://www.veripool.org/verilator)  — 将 Verilog 转换为 C++ 或 SystemC 中的周期精确行为模型的工具. 执行 lint 代码质量检查.

- [vscode-verilog-hdl-support](https://github.com/mshr-h/vscode-verilog-hdl-support)  — Verilog HDL/SystemVerilog/Bluespec SystemVerilog 支持 VS Code. 提供来自 Icarus Verilog、Vivado 逻辑仿真、Modelsim 和 Verilator 的语法突出显示和 Linting 支持


<h2 id="vim-script">Vim 脚本</h2>


- [vint](https://github.com/Kuniwak/vint) — 由 Python 实现的快速且高度可扩展的 Vim 脚本语言 Lint.


## Multiple languages


- [ale](https://github.com/w0rp/ale) — 适用于 Vim 和 NeoVim 的异步 Lint 引擎，支持多种语言.

- [Android Studio](https://developer.android.com/studio) — 基于 IntelliJ IDEA，并捆绑了 Android 工具，包括 Android Lint.

- [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) :copyright: — Static analysis for C/C++/C#, PHP and Java.

- [Application Inspector](https://www.ptsecurity.com/ww-en/products/ai) ：版权： - 商业静态代码分析，可生成漏洞来验证漏洞.

- [ApplicationInspector](https://github.com/microsoft/ApplicationInspector) — 创建超过 400 种规则模式的报告以进行功能检测（例如，在应用程序中使用加密或版本控制）.

- [APPscreener](https://solarappscreener.com) :copyright: — Static code analysis for binary and source code - Java/Scala, PHP, Javascript, C#, PL/SQL, Python, T-SQL, C/C++, ObjectiveC/Swift, Visual Basic 6.0, Ruby, Delphi, ABAP, HTML5 and Solidity.

- [ArchUnit](https://www.archunit.org) — 对 Java 或 Kotlin 架构进行单元测试.

- [Atom-Beautify](https://atom.io/packages/atom-beautify) :warning: — Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom editor.

- [autocorrect](https://huacnlee.github.io/autocorrect) — 一个 linter 和格式化程序，可帮助您改进文案写作、纠正 CJK（中文、日文、韩文）之间的空格、单词和标点符号.

- [Axivion Bauhaus Suite](https://www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: — Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95.

- [Bearer](https://github.com/bearer/bearer)  — 开源静态代码分析工具，用于发现、过滤和优先处理导致敏感数据泄露（PII、PHI、PD）的安全风险和漏洞. 高度可配置且易于扩展，专为安全和工程团队而构建.

- [Better Code Hub](https://bettercodehub.com) ：版权： - Better Code Hub 根据软件质量权威 Software Improvement Group 制定的 10 条工程指南检查您的 GitHub 代码库.

- [callGraph](https://github.com/koknat/callGraph) — 静态生成调用图图像并将其显示在屏幕上.

- [CAST Highlight](https://www.castsoftware.com/products/highlight) ：版权： - 商业静态代码分析在本地运行，但将结果上传到云端进行演示.

- [Checkmarx CxSAST](https://www.checkmarx.com/products/static-application-security-testing) :copyright: — 商业静态代码分析，不需要预编译.

- [ClassGraph](https://github.com/classgraph/classgraph) — 类路径和模块路径扫描器，用于查询或可视化类元数据或类相关性.

- [Clayton](https://www.getclayton.com/)  :copyright: — Salesforce 的人工智能代码审查. 保护您的开发、实施最佳实践并实时控制您的技术债务.

- [coala](https://coala.io) :警告: — 用于创建代码分析的语言独立框架 - 支持 [over 60 languages](https://coala.io/languages) 默认情况下.

- [Cobra](https://spinroot.com/cobra) ：版权： — NASA 喷气推进实验室的结构源代码分析器.

- [Codacy](https://www.codacy.com) :copyright: — 代码分析以更快地交付更好的代码.

- [Code Intelligence](https://www.code-intelligence.com) :copyright: — 与 CI/CD 无关的 DevSecOps 平台，结合了行业领先的模糊测试引擎，用于查找错误和可视化代码覆盖率

- [Codeac](https://www.codeac.io/?ref=awesome-static-analysis)  :copyright: — 自动代码审查工具与 GitHub、Bitbucket 和 GitLab（甚至是自托管）集成. 适用于 JavaScript、TypeScript、Python、Ruby、Go、PHP、Java、Docker 等.  （开源免费）

- [codeburner](https://groupon.github.io/codeburner) — 提供统一的界面来对发现的问题进行排序和采取行动.

- [codechecker](https://codechecker.readthedocs.io/en/latest) — 带有 Web GUI 的 Clang Static Analyzer 的缺陷数据库和查看器扩展.

- [CodeFactor](https://codefactor.io) :copyright: — GitHub 或 BitBucket 上存储库的自动代码分析.

- [CodeFlow](https://www.getcodeflow.com) :copyright: — Automated code analysis tool to deal with technical depth. Integrates with Bitbucket and Gitlab. (free for Open Source Projects)

- [CodeIt.Right](https://submain.com/products/codeit.right.aspx) :copyright: — CodeIt.Right™ 提供了一种快速、自动化的方法来确保您的源代码遵循（您的）预定义的设计和风格指南以及最佳编码实践.

- [CodePatrol](https://cyber-security.claranet.fr/en/codepatrol) ：版权： — 由安全性驱动的自动 SAST 代码审查，支持 15 种以上语言并包括安全培训.

- [codeql](https://github.com/github/codeql) — 深度代码分析 - 具有 VSCode 插件支持的多种语言的语义查询和数据流.

- [CodeQue](https://codeque.co)  — 结构匹配 JavaScript 和 TypeScript 代码的生态系统. 提供了解代码结构的搜索工具. 作为 CLI 工具和 Visual Studio Code 扩展提供. 它有助于更​​快、更准确地搜索代码，使您的工作流程更加有效. 很快它将提供 ESLint 插件，让您在几分钟内创建自己的规则，以帮助确保代码库质量.

- [CodeRush](https://www.devexpress.com/products/coderush) :copyright: — 在 Visual Studio 2015 及更高版本中使用 Roslyn 引擎的代码创建、调试、导航、重构、分析和可视化工具.

- [CodeScan](https://www.codescan.io/)  :copyright: — Salesforce 开发人员的代码质量和安全性.  CodeScan 的代码分析解决方案专为 Salesforce 平台打造，可让您全面了解代码运行状况.

- [CodeScene](https://codescene.com)  ：版权： — CodeScene 是一款高质量的软件可视化工具. 确定技术债务的优先级、检测交付风险并衡量组织方面. 完全自动化.

- [CodeSee](https://www.codesee.io/)  :copyright: — CodeSee 正在映射和自动化您的应用程序的服务、目录、文件依赖项和代码更改. 它就像 Google 地图，但用于 code.t

- [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) :copyright: — Advanced, whole program, deep path, static analysis of C, C++, Java and C# with easy-to-understand explanations and code and path visualization.

- [Codiga](https://www.codiga.io) ：版权： — 支持 12 种以上语言的自动代码审查和技术债务管理平台.

- [Corrode](https://github.com/jameysharp/corrode)  :警告: — 从 C 到 Rust 的半自动翻译. 可以通过显示 Rust 编译器警告和错误来揭示原始实现中的错误. 被 C2Rust 取代.

- [Coverity](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: — Synopsys Coverity supports 20 languages and over 70 frameworks including Ruby on rails, Scala, PHP, Python, JavaScript, TypeScript, Java, Fortran, C, C++, C#, VB.NET.

- [cpp-linter-action](https://cpp-linter.github.io/cpp-linter-action/) — 用于对 C/C++ 代码进行 linting 的 Github Action，集成 clang-tidy 和 clang-format 以收集以线程注释和/或注释形式提供的反馈.

- [cqc](https://github.com/xcatliu/cqc) :warning: — 检查 js、jsx、vue、css、less、scss、sass 和 styl 文件的代码质量.

- [DeepCode](https://www.deepcode.ai) ：版权： — DeepCode 被 Snyk 收购，现更名为 Snyk Code.

- [DeepSource](https://deepsource.io)  ：版权： — 深入的静态分析，以查找错误风险、安全性、反模式、性能、文档和风格等垂直领域的问题. 与 GitHub、GitLab 和 Bitbucket 的本机集成. 误报率低于 5%.

- [Depends](https://github.com/multilang-depends/depends) — Analyses the comprehensive dependencies of code elements for Java, C/C++, Ruby.

- [DevSkim](https://github.com/microsoft/devskim) — Regex-based static analysis tool for Visual Studio, VS Code, and Sublime Text - C/C++, C#, PHP, ASP, Python, Ruby, Java, and others.

- [dotenet-format](https://github.com/dotnet/format) — A code formatter for .NET. Preferences will be read from an `.editorconfig` file, if present, otherwise a default set of preferences will be used. At this time dotnet-format is able to format C# and Visual Basic projects with a subset of supported `.editorconfig` options.

- [Embold](https://embold.io) :copyright: — Intelligent software analytics platform that identifies design issues, code issues, duplication and metrics. Supports Java, C, C++, C#, JavaScript, TypeScript, Python, Go, Kotlin and more.

- [emerge](https://github.com/glato/emerge)  — Emerge 是一个源代码和依赖关系可视化工具，可用于收集有关软件项目的源代码结构、指标、依赖关系和复杂性的见解. 扫描项目的源代码后，它会为您提供一个交互式 Web 界面，以使用图形结构探索和分析您的项目.

- [ESLint](https://github.com/eslint/eslint) — JS 的可扩展 linter，遵循 ECMAScript 标准.

- [ezno](https://kaleidawave.github.io/posts/introducing-ezno/)  — 用 Rust 编写的 JavaScript 编译器和 TypeScript 检查器，重点关注静态分析和运行时性能.  Ezno 的类型检查器是从头开始构建的. 该检查器与 TypeScript 类型注释完全兼容，并且可以在没有任何类型注释的情况下工作.

- [Find Security Bugs](https://find-sec-bugs.github.io)  — 用于 Java Web 应用程序和 Android 应用程序安全审核的 SpotBugs 插件.  （还可以使用 Kotlin、Groovy 和 Scala 项目）

- [Fortify](https://software.microfocus.com/en-us/products/static-code-analysis-sast/overview) :copyright: — A commercial static analysis platform that supports the scanning of C/C++, C#, VB.NET, VB6, ABAP/BSP, ActionScript, Apex, ASP.NET, Classic ASP, VB Script, Cobol, ColdFusion, HTML, Java, JS, JSP, MXML/Flex, Objective-C, PHP, PL/SQL, T-SQL, Python (2.6, 2.7), Ruby (1.9.3), Swift, Scala, VB, and XML.

- [Goodcheck](https://sider.github.io/goodcheck) — 基于正则表达式的可定制 linter.

- [goone](https://github.com/masibw/goone) — 在 Go 代码中查找 N+1 条查询（for 循环中的 SQL 调用）

- [graudit](http://www.justanotherhacker.com) — Grep 粗略审计 - 源代码审计工具.

- [HCL AppScan Source](https://www.hcltechsw.com/products/appscan) ：版权： - 商业静态代码分析.

- [Hopper](https://github.com/cuplv/hopper) :warning: — 用 scala 编写的静态分析工具，适用于在 JVM 上运行的语言.

- [Hound CI](https://houndci.com)  — 对 GitHub 拉取请求中风格违规的评论. 支持 Coffeescript、Go、HAML、JavaScript、Ruby、SCSS 和 Swift.

- [imhotep](https://github.com/justinabrahms/imhotep) — 对进入存储库的提交进行评论，并检查语法错误和一般 lint 警告.

- [include-gardener](https://github.com/feddischson/include_gardener) — A multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.

- [Infer](https://fbinfer.com) — Java、C 和 Objective-C 的静态分析器

- [Kiuwan](https://www.kiuwan.com/code-security-sast) :copyright: — Identify and remediate cyber threats in a blazingly fast, collaborative environment, with seamless integration in your SDLC. Python, C\C++, Java, C#, PHP and more.

- [Klocwork](https://www.perforce.com/products/klocwork) :copyright: — Quality and Security Static analysis for C/C++, Java and C#.

- [LGTM](https://lgtm.com/)  ：版权： — 使用 CodeQL 对源代码进行查询来查找安全漏洞、变体和关键代码质量问题. 自动 PR 代码审查； 免费开源. 以前是塞姆勒. 它支持 Bitbucket Cloud、GitHub.com、GitLab.com 上托管的公共 Git 存储库.

- [lizard](https://github.com/terryyin/lizard)  — Lizard 是一个可扩展的循环复杂度分析器，适用于包括 C/C++ 在内的许多编程语言（不需要所有头文件或 Java 导入）. 它还进行复制粘贴检测（代码克隆检测/代码重复检测）和许多其他形式的静态代码分析. 计算没有注释的代码行数、CCN（圈复杂度数）、函数的标记计数、函数的参数计数.

- [Mega-Linter](https://nvuillam.github.io/mega-linter/) — Mega-Linter 凭借其 70 多个嵌入式 Linters 可以处理任何类型的项目，
 其高级报告可在任何 CI 系统或本地运行，
 具有辅助安装和配置功能，能够应用格式设置和修复

- [oclint](http://oclint.org) :警告: — 一个静态源代码分析工具，用于提高 C、C++ 和 Objective-C 的质量并减少缺陷.

- [Offensive 360](https://offensive360.com/) ：版权： - 商业静态代码分析系统不需要构建源代码或预编译.

- [OpenStaticAnalyzer](https://github.com/sed-inf-u-szeged/OpenStaticAnalyzer) — OpenStaticAnalyzer是一个源代码分析工具，可以对复杂系统的源代码进行深度静态分析.

- [parasoft](https://www.parasoft.com/)  ：版权： — 用于单元、API 和 Web UI 测试的自动化软件测试解决方案. 符合 MISRA、OWASP 及其他标准.

- [pfff](https://github.com/facebookarchive/pfff/wiki/Main) — Facebook 的代码分析、可视化或多种语言的风格保留源代码转换工具.

- [PMD](https://pmd.github.io) — 适用于 Java、Salesforce Apex、Javascript、PLSQL、XML、XSL 等的源代码分析器.

- [pre-commit](https://pre-commit.com) — 用于管理和维护多语言预提交挂钩的框架.

- [Prettier](https://prettier.io) — 一个固执己见的代码格式化程序.

- [Pronto](https://github.com/prontolabs/pronto)  — 对您的更改进行快速自动代码审查. 支持 40 多个各种语言的运行程序，包括 Clang、Elixir、JavaScript、PHP、Ruby 等.

- [PT.PM](https://github.com/PositiveTechnologies/PT.PM) :warning: — An engine for searching patterns in the source code, based on Unified AST or UST. At present time C#, Java, PHP, PL/SQL, T-SQL, and JavaScript are supported. Patterns can be described within the code or using a DSL.

- [Putout](https://github.com/coderaiser/putout) — 可插入且可配置的代码转换器，内置 eslint、babel 插件，支持 js、jsx typescript、flow、markdown、yaml 和 json.

- [PVS-Studio](https://pvs-studio.com) ：版权： — A ([conditionally free](https://pvs-studio.com/en/order/open-source-license) for FOSS and individual developers) static analysis of C, C++, C# and Java code. For advertising purposes [you can propose a large FOSS project for analysis by PVS employees](https://github.com/viva64/pvs-studio-check-list) . 支持 CWE 映射、OWASP ASVS、MISRA、AUTOSAR 和 SEI CERT 编码标准.

- [pylama](https://klen.github.io/pylama/)  — 适用于 Python 和 JavaScript 的代码审核工具. 包装 pycodestyle、pydocstyle、PyFlakes、Mccabe、Pylint 等

- [Qwiet AI](https://qwiet.ai/)  ：版权： - 在代码库投入生产之前识别其特有的漏洞. 利用代码属性图 (CPG) 在单个图表中同时运行分析. 自动发现开发中的业务逻辑缺陷，例如硬编码秘密和逻辑炸弹

- [Refactoring Essentials](https://marketplace.visualstudio.com/items?itemName=SharpDevelopTeam.RefactoringEssentialsforVisualStudio) :warning: — The free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers.

- [relint](https://github.com/codingjoe/relint) — 静态文件 linter，允许您使用正则表达式 (RegEx) 编写自定义规则.

- [ReSharper](https://www.jetbrains.com/resharper) :copyright: — Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies.

- [RIPS](https://www.ripstech.com) :copyright: — 针对 PHP 脚本中的漏洞的静态源代码分析器.

- [Rome](https://rome.tools/) — Rome 是一个 linter、编译器、捆绑器，并且 [more](https://rome.tools/#development-status) 适用于 JavaScript、TypeScript、JSON、HTML、Markdown 和 CSS.

- [Rome Formatter](https://rome.tools/blog/2022/04/05/rome-formatter-release) — 用 Rust 编写的用于 JS/TS 的高性能且容错的代码格式化程序

- [Roslyn Analyzers](https://github.com/dotnet/roslyn-analyzers) — 基于 Roslyn 的 FxCop 分析器实现.

- [Roslyn Security Guard](https://security-code-scan.github.io) — 该项目专注于识别潜在漏洞，例如 SQL 注入、跨站脚本 (XSS)、CSRF、加密弱点、硬编码密码等等.

- [SafeQL](https://safeql.dev)  — 从 PostgreSQL 中的原始 SQL 查询验证并自动生成 TypeScript 类型.  SafeQL 是一个 ESLint 插件，用于以类型安全的方式编写 SQL 查询.

- [SAST Online](https://sast.online/)  ：版权： — 彻底检查 Android 源代码，以发现并解决潜在的安全问题和漏洞. 静态应用安全测试（静态代码分析）工具在线

- [Scanmycode CE (Community Edition)](http://www.scanmycode.today) — Scanmycode - 使用多种工具/扫描仪和一份报告进行代码扫描/SAST/Linting

- [Scrutinizer](https://scrutinizer-ci.com) :copyright: — 可以与 GitHub 集成的专有代码质量检查器.

- [Security Code Scan](https://security-code-scan.github.io) — Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc. Integrates into Visual Studio 2015 and newer. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.

- [Semgrep](https://semgrep.dev)  — 一种快速、开源、静态分析工具，用于在编辑器、提交和 CI 时间查找错误并执行代码标准. 它的规则看起来就像你已经编写的代码； 没有抽象语法树或正则表达式摔跤. 支持 17 种以上语言.

- [Semgrep Supply Chain](https://semgrep.dev/products/semgrep-supply-chain)  :copyright: — 快速查找并修复高优先级安全问题.  Semgrep Supply Chain 优先考虑可通过代码访问的 2% 的漏洞.

- [ShiftLeft Scan](https://github.com/ShiftLeftSecurity/sast-scan)  — Scan 是一个免费的开源 DevSecOps 平台，用于检测源代码和依赖项中的安全问题. 它支持多种语言和 CI/CD 管道.

- [shipshape](https://github.com/google/shipshape) ：警告： — 静态程序分析平台，允许自定义分析器通过通用接口插入.

- [Sigrid](https://www.softwareimprovementgroup.com/solutions/sigrid-software-assurance-platform/) ：版权： — Sigrid 通过测量系统的代码质量来帮助您改进软件，然后将结果与数千个行业系统的基准进行比较，为您提供可以改进的领域的具体建议.

- [Similarity Tester](https://dickgrune.com/Programs/similarity_tester/) — 一种工具，可以查找文件之间或文件内的相似性，为您遇到违反 DRY 原则的情况提供支持.

- [Snyk Code](https://snyk.io) :copyright: — Snyk Code finds security vulnerabilities based on AI. Its speed of analysis allow us to  analyse your code in real time and deliver results when you hit the save button in your IDE.  Supported languages are Java, JavaScript, Python, PHP, C#, Go and TypeScript. Integrations with  GitHub, BitBucket and Gitlab. It is free to try and part of the Snyk platform also covering SCA,  containers and IaC.

- [SonarCloud](https://sonarcloud.io)  :copyright: — 基于云的多语言静态代码分析. 历史、趋势、安全热点、拉取请求分析等等. 免费开源.

- [SonarLint for Visual Studio](https://vs.sonarlint.org) — SonarLint 是 Visual Studio 2015 和 2017 的扩展，它向开发人员提供有关注入 .NET 代码的新错误和质量问题的即时反馈.

- [SonarQube](http://www.sonarqube.org) — SonarQube 是一个管理代码质量的开放平台.

- [Sonatype](https://www.sonatype.com) :copyright: — 报告常见依赖项中的已知漏洞并推荐更新包以最大程度地减少重大更改

- [Soto Platform](https://www.hello2morrow.com/products/sotograph)  ：版权： — 静态分析工具套件，由三个组件 Sotoarc（架构分析）、Sotograph（质量分析）和 Sotoreport（质量报告）组成. 帮助发现架构和实现之间的差异、接口违规（例如子系统私有部分的外部访问、通过循环关系强耦合的所有类、文件、包和子系统的检测等）.Sotograph 产品系列在 Windows 和 Linux 上运行. 

- [SourceMeter](https://www.sourcemeter.com/) :copyright: — Static Code Analysis for C/C++, Java, C#, Python, and RPG III and RPG IV versions (including free-form).

- [sqlvet](https://github.com/houqp/sqlvet)  — 对 Go 代码库中的原始 SQL 查询执行静态分析，以发现潜在的运行时错误. 它检查 SQL 语法错误，识别可能导致 SQL 注入的不安全查询，确保列计数与 INSERT 语句中的值计数匹配，并验证表名称和列名称.

- [StaticReviewer](https://securityreviewer.atlassian.net/wiki/spaces/KC/pages/196633/Static+Reviewer) ：版权： — Static Reviewer 根据最相关的安全编码标准、OWASP、CWE、CVE、CVSS、MISRA、CERT 对 40 多种编程语言执行代码检查，使用 1000 多个内置安全性、死代码和最佳实践验证规则 可用软件组合分析 (SCA) 模块来查找开源和第三方库中的漏洞.

- [Super-Linter](https://github.com/github/super-linter) — 多个 linter 的组合作为 GitHub Action 安装.

- [Svace](https://www.ispras.ru/en/technologies/svace/) :copyright: — Static code analysis tool for Java,C,C++,C#,Go.

- [Synopsys](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: — A commercial static analysis platform that allows for scanning of multiple languages (C/C++, Android, C#, Java, JS, PHP, Python, Node.JS, Ruby, Fortran, and Swift).

- [Teamscale](https://www.cqse.eu/en/teamscale/overview/)  :copyright: — 支持超过 25 种语言和直接 IDE 集成的静态和动态分析工具. 可根据要求免费托管开源项目. 提供免费学术许可证.

- [TencentCodeAnalysis](https://tca.tencent.com/)  ——腾讯云代码分析（简称TCA，早期公司内部代号CodeDog）是一个综合性的代码分析和问题跟踪平台.  TCA 由三个组件组成：服务器、Web 和客户端. 它集成了多种自主开发的工具，还支持各种编程语言的代码分析工具的动态集成.

- [ThreatMapper](https://github.com/deepfence/ThreatMapper)  — 运行时容器、无服务器和主机的漏洞扫描和风险评估.  ThreatMapper 从依赖项和操作系统包生成运行时 BOM，与多个威胁源进行匹配，扫描未受保护的机密，并根据严重性和利用风险对问题进行评分.

- [todocheck](https://github.com/preslavmihaylov/todocheck) — Linter 用于将带注释的 TODO 与问题跟踪器集成

- [trivy](https://github.com/aquasecurity/trivy)  — 适用于 CI 的简单而全面的容器和其他工件漏洞扫描器.  Trivy 检测操作系统软件包（Alpine、RHEL、CentOS 等）和应用程序依赖项（Bundler、Composer、npm、yarn 等）的漏洞. 检查容器和文件系统.


- [trunk](https://trunk.io)  :copyright: — 现代存储库包含许多技术，每种技术都有自己的一组 linter. 凭借 30 多个 linter 和计数，Trunk 使识别、安装、配置和运行所有存储库的正确 linter、静态分析器和格式化程序变得非常简单.

- [TscanCode](https://github.com/Tencent/TscanCode) — A fast and accurate static analysis solution for C/C++, C#, Lua codes provided by Tencent. Using GPLv3 license.

- [Undebt](https://github.com/Yelp/undebt) — 独立于语言的工具，用于基于简单模式定义的大规模、自动、可编程重构.

- [Understand](https://www.scitools.com) :copyright: — 代码可视化工具，为 Ada、VHDL 等提供代码分析、标准测试、指标、图形、依赖性分析等.

- [Unibeautify](https://unibeautify.com)  — 带有 GitHub 应用程序的通用代码美化器. 支持 HTML、CSS、JavaScript、TypeScript、JSX、Vue、C++、Go、Objective-C、Java、Python、PHP、GraphQL、Markdown 等.

- [Upsource](https://www.jetbrains.com/upsource) :copyright: — 具有静态代码分析和代码感知导航功能的代码审查工具，适用于 Java、PHP、JavaScript 和 Kotlin.

- [Veracode](https://www.veracode.com/security/static-code-analysis)  :copyright: — 无需源代码即可查找二进制文件和字节码中的缺陷. 支持所有主要编程语言：Java、.NET、JavaScript、Swift、Objective-C、C、C++ 等.

- [WALA](https://github.com/wala/WALA) — Java 字节码和相关语言以及 JavaScript 的静态分析功能.

- [weggli](https://github.com/googleprojectzero/weggli)  — 用于 C 和 C++ 代码库的快速且强大的语义搜索工具. 它旨在帮助安全研究人员识别大型代码库中有趣的功能.

- [WhiteHat Application Security Platform](https://www.whitehatsec.com/platform/static-application-security-testing) ：版权： — WhiteHat Scout（针对开发人员）与 WhiteHat Sentinel Source（针对运营）相结合，支持 WhiteHat Top 40 和 OWASP Top 10.

- [Wotan](https://github.com/fimbullinter/wotan) :warning: — 可插入 TypeScript 和 JavaScript linter.

- [XCode](https://developer.apple.com/xcode) :copyright: — XCode 提供了一个相当不错的 UI [Clang's](https://clang-analyzer.llvm.org/xcode.html) 静态代码分析器（C/C++、Obj-C）.


## Other



<h2 id="ansible">安西布尔</h2>


- [kics](https://kics.io/)  — 查找基础设施即代码中的安全漏洞、合规性问题和基础设施错误配置. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [Steampunk Spotter](https://steampunk.si/spotter/) ：版权： — Ansible Playbook 扫描工具，可分析您的 Playbook 并提供建议.


<h2 id="archive">档案</h2>


- [alquitran](https://github.com/ferivoz/alquitran) :warning: — 检查 tar 档案并尝试发现有关 POSIX 2017 pax 规范和常见 tar 实现的可移植性问题.
该项目旨在供希望为尽可能多的系统提供可移植源代码存档的项目维护人员使用. 在发布 tar 档案之前使用 alquitran 检查它们应该有助于在问题到达分发者和用户之前发现问题.

- [packj](https://packj.dev)  — Packj（发音为 package）是一个命令行 (CLI) 工具，用于审查开源软件包是否存在“风险”属性，这些属性使它们容易受到供应链攻击. 这是我们的大型安全分析平台 Packj.dev 背后的工具，该平台不断审查软件包并提供免费报告.

- [pure](https://github.com/ronomon/pure) :warning: — Pure 是一个静态分析文件格式检查器，可检查 ZIP 文件是否存在危险的压缩比、规格偏差、恶意存档签名、不匹配的本地和中央目录标头、不明确的 UTF-8 文件名、目录和符号链接遍历、无效的 MS-DOS 日期、重叠标头、溢出、下溢、稀疏、意外缓冲区出血等.


<h2 id="arm">Azure 资源管理器</h2>


- [AzSK](https://azsk.azurewebsites.net/)  — 适用于 Azure 的安全 DevOps 套件 (AzSK) 在基础设施即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础设施错误配置. 通过 ARM 支持 Azure.


<h2 id="binary">二进制文件</h2>


- [angr](https://github.com/angr/angr) — 也支持符号执行的二进制代码分析工具.

- [binbloom](https://github.com/quarkslab/binbloom)  — 分析原始二进制固件并确定字节顺序或加载地址等功能. 该工具与所有架构兼容.
加载地址：binbloom 可以解析原始二进制固件并确定其加载地址. 字节序：binbloom 可以使用启发式方法来确定固件的字节序.  UDS 数据库：binbloom 可以解析原始二进制固件并检查它是否包含包含 UDS 命令 ID 的数组.

- [BinSkim](https://github.com/Microsoft/binskim) — 一种二进制静态分析工具，可为 Windows 可移植可执行文件提供安全性和正确性结果.

- [Black Duck](https://www.blackducksoftware.com) :copyright: — 用于分析源代码和二进制文件以获取可重用代码、必要许可证和潜在安全问题的工具.

- [bloaty](https://github.com/google/bloaty)  — 有没有想过是什么让你的二进制文件变大了？  Bloaty McBloatface 将向您显示二进制文件的大小配置文件，以便您了解内部空间的占用情况.  Bloaty 对二进制文件进行了深入分析.  Bloaty 使用自定义的 ELF、DWARF 和 Mach-O 解析器，旨在准确地将二进制文件的每个字节归因于生成它的符号或编译单元. 它甚至会反汇编二进制文件以查找对匿名数据的引用.  F

- [cargo-bloat](https://github.com/RazrFalcon/cargo-bloat)  — 找出可执行文件中占用大部分空间的内容. 支持 ELF（Linux、BSD）、Mach-O（macOS）和 PE（Windows）二进制文件.

- [cwe_checker](https://github.com/fkie-cad/cwe_checker) — cwe_checker 发现二进制可执行文件中的易受攻击的模式.

- [Ghidra](https://ghidra-sre.org) — 由 NSA 研究局开发的软件逆向工程 (SRE) 工具套件，用于支持网络安全任务

- [Hopper](https://www.hopperapp.com/)  :copyright: — macOS 和 Linux 逆向工程工具，可让您反汇编、反编译和调试应用程序.  Hopper 使用不同的表示形式显示代码，例如控制流图和过程的伪代码. 支持苹果芯片.

- [IDA Free](https://www.hex-rays.com/products/ida/support/download_freeware) :copyright: — 二进制代码分析工具.

- [Jakstab](https://github.com/jkinder/jakstab) — Jakstab 是一个基于抽象解释的集成反汇编和静态分析框架，用于设计可执行文件的分析并恢复可靠的控制流图.

- [JEB Decompiler](https://www.pnfsoftware.com/)  :copyright: — 反编译和调试二进制代码. 分解并分析文档文件.  Android Dalvik、MIPS、ARM、Intel x86、Java、WebAssembly 和以太坊反编译器.

- [ktool](https://ktool.cynder.me/en/latest/ktool.html)  — 用于 MachO+Obj-C 编辑/分析的完全跨平台工具包和库. 包括 cli 工具包、curses GUI、ObjC 标头转储等等.

- [Manalyze](https://github.com/JusticeRage/Manalyze) — 静态分析器，用于检查可移植可执行文件中是否存在恶意内容.

- [mcsema](https://github.com/lifting-bits/mcsema)  :warning: — 用于将 x86、amd64、aarch64、sparc32 和 sparc64 程序二进制文件提升为 LLVM 位码的框架. 它将可执行二进制文件从本机机器代码转换（“提升”）为 LLVM 位代码，这对于执行程序分析方法非常有用.

- [Nauz File Detector](https://github.com/horsicq/Nauz-File-Detector) — 适用于 Windows、Linux 和 MacOS 的静态链接器/编译器/工具检测器.

- [rust-audit](https://github.com/Shnatsel/rust-audit)  — 审核 Rust 二进制文件是否存在已知错误或安全漏洞. 这是通过将 JSON 格式的依赖树 (Cargo.lock) 相关数据嵌入到已编译可执行文件的专用链接器部分来实现的.

- [Twiggy](https://rustwasm.github.io/twiggy)  — 分析二进制文件的调用图以分析代码大小. 目标是缩小 wasm 二进制大小.

- [VMware chap](https://github.com/vmware/chap)  — chap 分析未检测的 ELF 核心文件是否存在泄漏、内存增长和损坏. 它足够可靠，可以用于自动化以在泄漏发生之前捕获泄漏. 作为一种交互式工具，它有助于解释内存增长，可以识别某些形式的损坏，并通过提供各种内存位置的状态来补充调试器. 

- [zydis](https://zydis.re) — 快速且轻量级的 x86/x86-64 反汇编程序库


<h2 id="buildtool">构建工具</h2>


- [checkmake](https://github.com/mrtazz/checkmake) — Makefile 的 Linter / 分析器.

- [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) — FreeBSD 和 DragonFlyBSD 端口目录的验证器.


<h2 id="css">CSS/SASS/SCSS</h2>


- [CSS Stats](https://cssstats.com) — 样式表上可能有趣的统计数据.

- [CSScomb](https://github.com/csscomb/csscomb.js)  — CSS 编码风格格式化程序. 支持自己的配置，使样式表美观一致.

- [CSSLint](http://csslint.net) — 进行基本语法检查并发现有问题的模式或效率低下的迹象.

- [GraphMyCSS.com](https://graphmycss.com) — CSS 特异性图生成器.

- [Nu Html Checker](https://validator.github.io/validator/) — 帮助您发现 HTML/CSS/SVG 中的问题

- [Parker](https://github.com/katiefenn/parker) :warning: — 样式表分析工具.

- [PostCSS](https://postcss.org)  — 一个通过 JS 插件转换样式的工具. 这些插件可以检查你的 CSS、支持变量和 mixin、转译未来的 CSS 语法、内联图像等等.

- [Project Wallace CSS Analyzer](https://www.projectwallace.com) — CSS 分析，一部分 [Project Wallace](https://www.projectwallace.com).

- [sass-lint](https://github.com/sasstools/sass-lint) :warning: — 用于 sass 和 scss 语法的仅节点 Sass linter.

- [scsslint](https://github.com/brigade/scss-lint) — SCSS 文件的 Linter.

- [Specificity Graph](https://jonassebastianohlsson.com/specificity-graph) — CSS 特异性图生成器.

- [Stylelint](http://stylelint.io) — SCSS/CSS 文件的 Linter.


<h2 id="configfile">配置文件</h2>


- [dotenv-linter](https://dotenv-linter.readthedocs.io/en/latest) ——像魅力一样对 dotenv 文件进行 Linting.

- [dotenv-linter (Rust)](https://dotenv-linter.github.io/#/)  — .env 文件的闪电般的 linter. 用铁锈写成

- [gixy](https://github.com/yandex/gixy)  — 分析 Nginx 配置的工具. 主要目标是防止错误配置并自动检测缺陷.


<h2 id="configmanagement">配置管理</h2>


- [ansible-lint](https://docs.ansible.com/ansible-lint) — 检查行动手册中是否有可能改进的做法和行为.

- [AWS CloudFormation Guard](https://github.com/aws-cloudformation/cloudformation-guard) — 根据策略即代码规则检查本地 CloudFormation 模板，并从现有模板生成规则.

- [AzSK](https://azsk.azurewebsites.net/)  — 适用于 Azure 的安全 DevOps 套件 (AzSK) 在基础设施即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础设施错误配置. 通过 ARM 支持 Azure.

- [cfn-lint](https://github.com/awslabs/cfn-python-lint) — AWS 实验室 CloudFormation linter.

- [cfn_nag](https://github.com/stelligent/cfn_nag) — AWS CloudFormation 模板的 linter.

- [checkov](https://www.checkov.io) — Terraform 文件的静态分析工具 (tf&gt;=v0.12)，防止构建时云配置错误.

- [cookstyle](https://docs.chef.io/cookstyle.html) — Cookstyle 是一款基于用于 Chef 食谱的 RuboCop Ruby linting 工具的 linting 工具.

- [foodcritic](http://www.foodcritic.io) — 一个 lint 工具，用于检查 Chef 食谱中的常见问题.

- [kics](https://kics.io/)  — 查找基础设施即代码中的安全漏洞、合规性问题和基础设施错误配置. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint) — 检查 Puppetmetadata.json 文件有效性的工具.

- [Puppet Lint](https://github.com/rodjek/puppet-lint) :warning: — 检查您的 Puppet 清单是否符合样式指南.

- [Steampunk Spotter](https://steampunk.si/spotter/) ：版权： — Ansible Playbook 扫描工具，可分析您的 Playbook 并提供建议.

- [terraform-compliance](https://terraform-compliance.com) — 针对 Terraform 的轻量级、注重合规性和安全性的 BDD 测试框架.

- [terrascan](https://github.com/cesar-rodriguez/terrascan) — Terraform 模板静态代码分析的安全性和最佳实践测试集合.

- [tflint](https://github.com/wata727/tflint) — Terraform linter，用于检测 `terraform plan` 无法检测到的错误.

- [tfsec](https://github.com/tfsec/tfsec)  — Terraform 静态分析工具，通过在构建时检查云错误配置来防止潜在的安全问题，并直接与 HCL 解析器集成以获得更好的结果. 检查是否违反 AWS、Azure 和 GCP 安全最佳实践建议.


<h2 id="container">集装箱</h2>


- [anchore](https://anchore.io)  — 发现、分析和认证容器镜像. 一项分析 Docker 映像并应用用户定义的接受策略以允许自动容器映像验证和认证的服务 

- [clair](https://github.com/coreos/clair) — 容器的漏洞静态分析.

- [collector](https://github.com/banyanops/collector) :warning: — 在容器内运行任意脚本，并收集有用的信息.

- [dagda](https://github.com/eliasgranderubio/dagda) — 对 Docker 镜像/容器中的已知漏洞进行静态分析.

- [Docker Label Inspector](https://github.com/garethr/docker-label-inspector) :warning: — Lint 并验证 Dockerfile 标签.

- [Haskell Dockerfile Linter](https://github.com/lukasmartinelli/hadolint) — 更智能的 Dockerfile linter，可帮助您构建最佳实践 Docker 镜像.

- [kics](https://kics.io/)  — 查找基础设施即代码中的安全漏洞、合规性问题和基础设施错误配置. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [krane](https://github.com/appvia/krane) — Krane 是一个简单的 Kubernetes RBAC 静态分析工具.
它识别了 K8s RBAC 设计中潜在的安全风险，并就如何缓解这些风险提出了建议.  Krane 仪表板显示当前 RBAC 安全状况，并让您浏览其定义.

- [OpenSCAP](https://www.open-scap.org/) — Suite of automated audit tools to examine the configuration and  known vulnerabilities following the NIST-certified Security  Content Automation Protocol (SCAP).

- [Qualys Container Security](https://www.qualys.com/apps/container-security) :copyright: — 容器本机应用程序保护，提供容器化应用程序的可见性和控制.

- [sysdig](https://sysdig.com/)  ：版权： — 用于云和容器取证的安全 DevOps 平台.  Sysdig 基于开源堆栈构建，提供 Docker 映像扫描并创建了 Falco，这是容器、Kubernetes 和云的运行时威胁检测的开放标准. 

- [Vuls](https://vuls.io/) — 基于 NVD、OVAL 等信息的无代理 Linux 漏洞扫描器.它具有一些容器映像支持，尽管不是特定于容器的工具.


<h2 id="ci">持续集成</h2>


- [actionlint](https://rhysd.github.io/actionlint)  — GitHub Actions 工作流程文件的静态检查器. 提供在线版本.

- [AzSK](https://azsk.azurewebsites.net/)  — 适用于 Azure 的安全 DevOps 套件 (AzSK) 在基础设施即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础设施错误配置. 通过 ARM 支持 Azure.

- [Code Climate](https://codeclimate.com) — 适合所有人的开放且可扩展的静态分析平台.

- [Codecov](https://about.codecov.io/) :copyright: — Codecov 是一家为开发人员和工程领导者提供代码覆盖率工具的公司，以帮助他们了解他们的代码覆盖率.
它们提供灵活、统一的报告、无缝的覆盖范围洞察和强大的覆盖范围控制.  Codecov 支持 20 多种语言，并且与 CI/CD 无关. 超过 29,000 个组织和 100 万开发人员使用 Codecov.  Codecov 最近加入了 Sentry.

- [Diffblue](https://www.diffblue.com/) ：版权： — Diffblue 是一家软件公司，为软件开发团队提供人工智能驱动的代码分析和测试解决方案.
其技术可帮助开发人员自动化测试、查找错误并减少软件开发过程中的体力劳动. 该公司的主要产品 Diffblue Cover 使用 AI 生成和运行 Java 代码的单元测试，有助于捕获错误并提高代码质量.

- [exakat](https://www.exakat.io) — PHP 的自动代码审查引擎.

- [Goblint](https://goblint.in.tum.de)  — 用于分析多线程 C 程序的静态分析器. 它的主要重点是检测数据竞争，但它也报告其他运行时错误，例如缓冲区溢出和空指针取消引用.

- [Nitpick CI](https://nitpick-ci.com) :copyright: — 自动 PHP 代码审查.

- [PullRequest](https://www.pullrequest.com)  ：版权： - 代码审查作为具有内置静态分析的服务. 由专家工程师在一流的自动化支持下进行质量代码审查，提高速度并减少技术债务.

- [quality](https://github.com/apiology/quality) — Runs quality checks on your code using community tools, and makes sure your numbers don't get any worse over time.

- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode)  :警告: — 自动代码审查和修复. 它可以帮助您跟踪软件项目中的问题和指标，并且可以轻松扩展以支持新型分析.

- [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst) — 识别并优先考虑 Java 代码库中的上帝类和高度耦合类，您应该首先重构.

- [Reviewdog](https://github.com/haya14busa/reviewdog) — 用于发布来自任何代码托管服务中的任何 linter 的评论评论的工具.

- [Symfony Insight](https://insight.symfony.com/) :copyright: — 检测安全风险、查找错误并为 PHP 项目提供可操作的指标.

- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  — 用于从静态代码分析中解析报告文件的 Java 库. 被大量 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="deno">不是</h2>


- [deno_lint](https://github.com/denoland/deno_lint) — Deno 的官方 linter.


<h2 id="embedded">嵌入式</h2>


- [oelint-adv](https://github.com/priv-kweihmann/oelint-adv) — 用于开放嵌入式和 YOCTO 中使用的 bitbake 配方的 Linter


<h2 id="erb">嵌入式 Ruby（又名 ERB、eRuby）</h2>


- [ERB Lint](https://github.com/Shopify/erb-lint) — 检查您的 ERB 或 HTML 文件

- [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)  — HTML 的规范化器/美化器，也理解嵌入式 Ruby. 非常适合整理 Rails 模板.


<h2 id="gherkin">小黄瓜</h2>


- [gherkin-lint](https://github.com/vsiakka/gherkin-lint) — 用 Ja​​vascript 编写的 Gherkin-Syntax 的 linter.


<h2 id="html">超文本标记语言</h2>


- [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme) — 用于 Angular 项目的 Linter

- [Bootlint](https://github.com/twbs/bootlint) :warning: — An HTML linter for Bootstrap projects.

- [ERB Lint](https://github.com/Shopify/erb-lint) — 检查您的 ERB 或 HTML 文件

- [grunt-bootlint](https://github.com/twbs/grunt-bootlint) :warning: — Grunt 包装器 [Bootlint](https://github.com/twbs/bootlint)，Bootstrap 项目的 HTML linter.

- [gulp-bootlint](https://github.com/tschortsch/gulp-bootlint) :警告: — gulp 包装器 [Bootlint](https://github.com/twbs/bootlint)，Bootstrap 项目的 HTML linter.

- [HTML Inspector](https://github.com/philipwalton/html-inspector) :警告: — HTML Inspector 是一个代码质量工具，可帮助您和您的团队编写更好的标记.

- [HTML Tidy](http://www.html-tidy.org) — 通过修复标记错误并将遗留代码升级到现代标准来纠正和清理 HTML 和 XML 文档.

- [HTML-Validate](https://html-validate.org/) — 离线 HTML5 验证器.

- [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)  — HTML 的规范化器/美化器，也理解嵌入式 Ruby. 非常适合整理 Rails 模板.

- [HTMLHint](https://htmlhint.com) — HTML 静态代码分析工具.

- [Nu Html Checker](https://validator.github.io/validator/) — 帮助您发现 HTML/CSS/SVG 中的问题

- [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer) — Web 组件的静态分析框架.


<h2 id="json">JSON</h2>


- [jsonlint](https://jsonlint.com/)  — 带有 CLI 的 JSON 解析器和验证器.  jsonlint.com 的独立版本

- [Spectral](https://stoplight.io/open-source/spectral) — 灵活的 JSON/YAML linter，对 OpenAPI v2/v3 和 AsyncAPI v2 提供开箱即用的支持.


<h2 id="kubernetes">库伯内斯</h2>


- [chart-testing](https://github.com/helm/chart-testing) — ct is the the tool for testing Helm charts.  It is meant to be used for linting and testing pull requests.  It automatically detects charts changed against the target branch.

- [clusterlint](https://github.com/digitalocean/clusterlint)  — Clusterlint 查询实时 Kubernetes 集群的资源，对这些资源执行常见的和特定于平台的检查，并向集群操作员提供可操作的反馈. 它是一种在外部运行的非侵入性工具.  Clusterlint 不会更改资源配置.

- [Datree](https://datree.io/) — CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及组织的策略来防止 Kubernetes 错误配置

- [kics](https://kics.io/)  — 查找基础设施即代码中的安全漏洞、合规性问题和基础设施错误配置. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [klint](https://github.com/uswitch/klint)  — 一种监听 Kubernetes 资源变化并针对它们运行 linting 规则的工具. 识别和调试错误的对象，并根据策略微调对象，因为两者都会随着时间的推移而变化.  Klint 帮助我们对检查进行编码，并在团队需要采取行动时主动提醒他们.

- [krane](https://github.com/appvia/krane) — Krane 是一个简单的 Kubernetes RBAC 静态分析工具.
它识别了 K8s RBAC 设计中潜在的安全风险，并就如何缓解这些风险提出了建议.  Krane 仪表板显示当前 RBAC 安全状况，并让您浏览其定义.

- [kube-hunter](https://aquasecurity.github.io/kube-hunter/) — 寻找 Kubernetes 集群中的安全漏洞.

- [kube-lint](https://github.com/viglesiasce/kube-lint)  — 具有可定制规则集的 Kubernetes 资源的 linter. 您定义一个要根据您的资源验证的规则列表，kube-lint 将根据它们评估这些规则.

- [kube-linter](https://github.com/stackrox/kube-linter) KubeLinter 是一种静态分析工具，用于检查 Kubernetes YAML 文件和 Helm 图表，以确保其中代表的应用程序遵循最佳实践.

- [kube-score](https://kube-score.com) — Kubernetes 对象定义的静态代码分析.

- [kubeconform](https://github.com/yannh/kubeconform) — 快速 Kubernetes 清单验证器，支持自定义资源.
它的灵感来自于，包含代码，并且旨在保持接近 [Kubeval](https://analysis-tools.dev/tool/kubeval)，但具有以下改进：*高性能：将通过多个例程验证和下载清单，将下载的文件缓存在内存中*可配置的远程或本地模式位置列表，启用验证 Kubernetes 自定义资源（CRD）和离线验证功能*默认情况下使用由 kubernetes-json-schema 项目维护的模式注册表的自更新分支 - 这保证了所有最新版本的 Kubernetes 的最新模式.

- [KubeLinter](https://github.com/stackrox/kube-linter) KubeLinter 是一种静态分析工具，用于检查 Kubernetes YAML 文件和 Helm 图表，以确保其中代表的应用程序遵循最佳实践.

- [kubeval](https://kubeval.instrumenta.dev) — 验证您的 Kubernetes 配置文件并支持多个 Kubernetes 版本.


<h2 id="latex">乳胶</h2>


- [ChkTeX](http://www.nongnu.org/chktex) — LaTex 的 linter，可以捕获 LaTeX 监督的一些印刷错误.

- [lacheck](https://www.ctan.org/pkg/lacheck) — 用于查找 LaTeX 文档中常见错误的工具.

- [TeXLab](https://texlab.netlify.app) — TeX/LaTeX 的语言服务器协议实现，包括 lint 功能.


<h2 id="laravel">拉维尔</h2>


- [Enlightn](https://www.laravel-enlightn.com/)  — Laravel 应用程序的静态和动态分析工具，提供提高 Laravel 应用程序的性能、安全性和代码可靠性的建议. 包含 120 项自动检查.

- [larastan](https://github.com/nunomaduro/larastan)  — 向 Laravel 添加静态分析，提高开发人员的工作效率和代码质量. 它是 PHPStan 的包装器.


<h2 id="make">生成文件</h2>


- [checkmake](https://github.com/mrtazz/checkmake) — Makefile 的 Linter / 分析器.

- [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) — FreeBSD 和 DragonFlyBSD 端口目录的验证器.


<h2 id="markdown">降价</h2>


- [markdownlint](https://github.com/DavidAnson/markdownlint) — 用于 Markdown/CommonMark 文件的基于 Node.js 的样式检查器和 lint 工具.

- [mdformat](https://mdformat.rtfd.io) — CommonMark 兼容的 Markdown 格式化程序

- [mdl](https://github.com/mivok/markdownlint) — 检查 Markdown 文件和标记样式问题的工具.

- [remark-lint](https://remark.js.org) — 用 Ja​​vaScript 编写的可插入 Markdown 代码风格 linter.


<h2 id="meta">金属熔体</h2>


- [ciocheck](https://github.com/ContinuumIO/ciocheck)  :warning: — Linter、格式化程序和测试套件帮助程序. 作为一个 linter，它是 `pep8`、`pydocstyle`、`flake8` 和 `pylint` 的包装器.

- [flake8](https://github.com/PyCQA/flake8) — `pyflakes`、`pycodestyle` 和 `mccabe` 的​​包装.

- [Go Meta Linter](https://github.com/alecthomas/gometalinter)  :warning: — 同时运行 Go lint 工具并标准化其输出. 对新项目使用“golangci-lint”.

- [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) — 同时运行许多 linter 并将其输出标准化为报告.

- [multilint](https://github.com/adamchainz/multilint) :warning: — `flake8`、`isort` 和 `modernize` 的包装.

- [prospector](https://github.com/PyCQA/prospector) — `pylint`、`pep8`、`mccabe` 等的包装.


<h2 id="mobile">移动的</h2>


- [Android Lint](http://tools.android.com/tips/lint) — 对 Android 项目运行静态分析.

- [android-lint-summary](https://passy.github.io/android-lint-summary) :warning: — 将多个项目的 lint 错误合并到一个输出中，同时检查多个子项目的 lint 结果.

- [FlowDroid](https://github.com/secure-software-engineering/FlowDroid) — Android 应用程序的静态污点分析工具.

- [iblessing](https://www.kitploit.com/2020/08/iblessing-ios-security-exploiting.html)  :警告: — iblessing 是一个 iOS 安全利用工具包. 它可用于逆向工程、二进制分析和漏洞挖掘.

- [Mariana Trench](https://mariana-tren.ch/)  — 我们针对 Android 和 Java 应用程序的安全静态分析工具.  Mariana Trench 分析 Dalvik 字节码，旨在在大型代码库（数十百万行代码）上快速运行. 它可以在代码更改时发现漏洞，然后再将其放入存储库.

- [Oversecured](https://oversecured.com)  :copyright: — 适用于 Android 和 iOS 应用程序的企业漏洞扫描器. 它允许应用程序所有者和开发人员通过将 Oversecured 集成到开发过程中来保护移动应用程序的每个新版本.

- [paprika](https://github.com/GeoffreyHecht/paprika) :warning: — 一个工具包，用于检测分析的 Android 应用程序中的一些代码气味.

- [qark](https://github.com/linkedin/qark) :warning: — 用于查找多个与安全相关的 Android 应用程序漏洞的工具.

- [redex](https://fbredex.com)  — Redex 提供了一个用于读取、写入和分析 .dex 文件的框架，以及一组使用该框架来改进字节码的优化过程. 经过 Redex 优化的 APK 应该更小、更快.


<h2 id="nix">尼克斯</h2>


- [deadnix](https://github.com/astro/deadnix) — 扫描 Nix 文件中的死代码（未使用的变量绑定）

- [statix](https://git.peppe.rs/languages/statix/about/)  — Nix 编程语言的 Lint 和建议.  “statix check”突出显示 Nix 代码中的反模式.  “statix fix”可以修复多个此类事件.


<h2 id="nodejs">Node.js</h2>


- [lockfile-lint](https://github.com/lirantal/lockfile-lint) — Lint npm 或yarn 锁定文件以分析和检测安全问题

- [njsscan](https://opensecurity.in) — 静态应用程序测试 (SAST) 工具，可以使用 libsast 中的简单模式匹配器和语法感知语义代码模式搜索工具 semgrep 来查找 Node.js 应用程序中不安全的代码模式.

- [NodeJSScan](https://opensecurity.in)  — 用于 Node.js 应用程序的静态安全代码扫描器，由 libsast 和 semgrep 提供支持，构建于 njsscan cli 工具之上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.

- [standard](http://standardjs.com) — 检查 Javascript 样式指南问题的 npm 模块.


<h2 id="package">套餐</h2>


- [lintian](https://lintian.debian.org) — Debian 软件包的静态分析工具.

- [rpmlint](https://github.com/rpm-software-management/rpmlint) — 用于检查 rpm 包中常见错误的工具.


<h2 id="protobuf">协议缓冲区</h2>


- [buf](https://buf.build) — Provides a CLI linter that enforces good API design choices and structure

- [protolint](https://github.com/yoheimuta/protolint) — 可插入的 linter 和修复程序以强制执行 Protocol Buffer 样式和约定.


<h2 id="puppet">木偶</h2>


- [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint) — 检查 Puppetmetadata.json 文件有效性的工具.


<h2 id="rails">导轨</h2>


- [dawnscanner](https://github.com/thesp0nge/dawnscanner)  — 用于 ruby​​ 编写的 Web 应用程序的静态分析安全扫描器. 它支持 Sinatra、Padrino 和 Ruby on Rails 框架.


<h2 id="security">安全/先科</h2>


- [AzSK](https://azsk.azurewebsites.net/)  — 适用于 Azure 的安全 DevOps 套件 (AzSK) 在基础设施即代码中提供安全 IntelliSense、安全验证测试 (SVT)、CICD 扫描漏洞、合规性问题和基础设施错误配置. 通过 ARM 支持 Azure.

- [brakeman](https://brakemanscanner.org) — 用于 Ruby on Rails 应用程序的静态分析安全漏洞扫描器.

- [Credential Digger](https://github.com/SAP/credential-digger) — Credential Digger 是一款 GitHub 扫描工具，可识别硬编码凭证（密码、API 密钥、密钥、令牌、个人信息等），并通过名为“Credential Digger”的机器学习模型过滤误报数据 [Password Model](https://huggingface.co/SAPOSS/password-model) . 该扫描仪能够以较低的误报率检测密码和非结构化令牌. 

- [Datree](https://datree.io/) — CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及组织的策略来防止 Kubernetes 错误配置

- [detect-secrets](https://github.com/Yelp/detect-secrets) — 一种企业友好的方式来检测和防止代码中的秘密.
它通过针对启发式制作的正则表达式语句运行定期 diff 输出来识别是否已提交任何新机密来实现此目的. 这样，它避免了挖掘所有 git 历史记录的开销，以及每次扫描整个存储库的需要.

- [Enlightn](https://www.laravel-enlightn.com/)  — Laravel 应用程序的静态和动态分析工具，提供提高 Laravel 应用程序的性能、安全性和代码可靠性的建议. 包含 120 项自动检查.

- [Gitleaks](https://github.com/zricethezav/gitleaks) — 一个 SAST 工具，用于检测 git 存储库中的硬编码秘密，例如密码、API 密钥和令牌.

- [gokart](https://github.com/praetorian-inc/gokart)  — Golang 安全分析，重点是最大限度地减少误报. 它能够追踪变量和函数参数的来源，以确定输入源是否安全.

- [iblessing](https://www.kitploit.com/2020/08/iblessing-ios-security-exploiting.html)  :警告: — iblessing 是一个 iOS 安全利用工具包. 它可用于逆向工程、二进制分析和漏洞挖掘.

- [kics](https://kics.io/)  — 查找基础设施即代码中的安全漏洞、合规性问题和基础设施错误配置. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [ktool](https://ktool.cynder.me/en/latest/ktool.html)  — 用于 MachO+Obj-C 编辑/分析的完全跨平台工具包和库. 包括 cli 工具包、curses GUI、ObjC 标头转储等等.

- [kube-hunter](https://aquasecurity.github.io/kube-hunter/) — 寻找 Kubernetes 集群中的安全漏洞.

- [lockfile-lint](https://github.com/lirantal/lockfile-lint) — Lint npm 或yarn 锁定文件以分析和检测安全问题

- [LunaSec](https://www.lunasec.io)  — 开源 AppSec 平台，下次发生 Log4Shell 或 node-ipc 等漏洞时会自动通知您. 跟踪您的依赖项并构建集中式服务.

- [njsscan](https://opensecurity.in) — 静态应用程序测试 (SAST) 工具，可以使用 libsast 中的简单模式匹配器和语法感知语义代码模式搜索工具 semgrep 来查找 Node.js 应用程序中不安全的代码模式.

- [NodeJSScan](https://opensecurity.in)  — 用于 Node.js 应用程序的静态安全代码扫描器，由 libsast 和 semgrep 提供支持，构建于 njsscan cli 工具之上. 它具有一个 UI，其中包含有关应用程序安全状态的各种仪表板.

- [Oversecured](https://oversecured.com)  :copyright: — 适用于 Android 和 iOS 应用程序的企业漏洞扫描器. 它允许应用程序所有者和开发人员通过将 Oversecured 集成到开发过程中来保护移动应用程序的每个新版本.

- [PT Application Inspector](https://www.ptsecurity.com)  :copyright: — 识别代码缺陷并检测漏洞以防止网络攻击. 通过提供可能的漏洞来演示远程代码执行.

- [Qualys Container Security](https://www.qualys.com/apps/container-security) :copyright: — 容器本机应用程序保护，提供容器化应用程序的可见性和控制.

- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode)  :警告: — 自动代码审查和修复. 它可以帮助您跟踪软件项目中的问题和指标，并且可以轻松扩展以支持新型分析.

- [Reshift](https://www.reshiftsecurity.com) :copyright: — 用于检测和管理 JavaScript 安全漏洞的源代码分析工具.

- [Rezilion](https://www.rezilion.com/) ：版权： — 发现环境中所有组件的漏洞，过滤掉 85% 不可利用的漏洞，并创建修复计划并开票以升级违反安全策略的组件和/或在 CI 中自动修补.

- [scorecard](https://github.com/ossf/scorecard) — 安全记分卡 - 开源的安全健康指标

- [SearchDiggity](https://resources.bishopfox.com/resources/tools/google-hacking-diggity/attack-tools/)  :copyright: — 识别 Github、Google Code、MS CodePlex、SourceForge 等托管的开源代码项目中的漏洞. 该工具附带 130 多个默认搜索，可识别 SQL 注入、跨站点脚本 (XSS)、不安全的远程和本地文件包含、硬编码密码等. 

- [Steampunk Spotter](https://steampunk.si/spotter/) ：版权： — Ansible Playbook 扫描工具，可分析您的 Playbook 并提供建议.

- [Symfony Insight](https://insight.symfony.com/) :copyright: — 检测安全风险、查找错误并为 PHP 项目提供可操作的指标.

- [tfsec](https://github.com/tfsec/tfsec)  — Terraform 静态分析工具，通过在构建时检查云错误配置来防止潜在的安全问题，并直接与 HCL 解析器集成以获得更好的结果. 检查是否违反 AWS、Azure 和 GCP 安全最佳实践建议.

- [trufflehog](https://trufflesecurity.com) — 到处寻找凭证
TruffleHog 是一个开源秘密扫描引擎，可以解决公司整个技术堆栈中暴露的秘密. 

- [Tsunami Security Scanner](https://github.com/google/tsunami-security-scanner)  — 具有可扩展插件系统的通用网络安全扫描器，用于高可信度地检测高严重性的类似 RCE 的漏洞. 可以添加用于查找漏洞的自定义检测器（例如开放 API）.


<h2 id="smart-contracts">智能合约</h2>


- [mythril](https://github.com/ConsenSys/mythril) — 包含电池的符号执行框架可用于自动查找和利用智能合约中的漏洞.

- [MythX](https://mythx.io)  :copyright: — MythX 是一个易于使用的分析平台，它集成了模糊测试、符号执行和静态分析等多种分析方法，可以高精度地发现漏洞. 它可以与 Remix 或 VSCode 等工具链集成，也可以从命令行调用.

- [slither](https://github.com/trailofbits/slither) — 静态分析框架，运行一套漏洞检测器，打印有关合约详细信息的可视化信息，并提供 API 来轻松编写自定义分析.

- [solhint](https://protofire.github.io/solhint)  — Solhint 是由 https://protofire.io 创建的开源项目. 它的目标是为 Solidity 代码提供一个 linting 实用程序.

- [solium](https://ethlint.readthedocs.io/en/latest) — Solium 是一个 linter，用于识别和修复 Solidity 智能合约中的样式和安全问题.


<h2 id="support">支持</h2>


- [LibVCS4j](https://github.com/uni-bremen-agst/libvcs4j) — 一个 Java 库，通过为不同版本控制系统和问题跟踪器提供通用 API，允许现有工具分析软件系统的演变.

- [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst) — 识别并优先考虑 Java 代码库中的上帝类和高度耦合类，您应该首先重构.

- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  — 用于从静态代码分析中解析报告文件的 Java 库. 被大量 Jenkins、Maven 和 Gradle 插件使用.


<h2 id="template">模板语言</h2>


- [ember-template-lint](https://github.com/ember-template-lint/ember-template-lint) — 用于 Ember 或 Handlebars 模板的 Linter.

- [haml-lint](https://github.com/sds/haml-lint) — 用于编写干净且一致的 HAML 的工具.

- [slim-lint](https://github.com/sds/slim-lint) — 用于分析 Slim 模板的可配置工具.

- [yamllint](https://yamllint.readthedocs.io) — 检查 YAML 文件的语法有效性、键重复和外观问题，例如行长度、尾随空格和缩进.


<h2 id="terraform">地形</h2>


- [kics](https://kics.io/)  — 查找基础设施即代码中的安全漏洞、合规性问题和基础设施错误配置. 支持 Terraform、Kubernetes、Docker、AWS CloudFormation 和 Ansible

- [shisho](https://docs.shisho.dev/)  — 专为开发人员和安全团队设计的轻量级静态代码分析器. 它允许您使用类似于 sed 的直观 DSL 来分析和转换源代码，但针对的是代码.


<h2 id="translation">翻译</h2>


- [dennis](https://github.com/willkg/dennis) :警告: — 一组用于处理 PO 文件的实用程序，以简化开发并提高质量.


<h2 id="vue">视图.js</h2>


- [HTML-Validate](https://html-validate.org/) — 离线 HTML5 验证器.

- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)  — 用于 VS Code 的 Vue 工具，由 vls（vue 语言服务器）提供支持.  Vetur 支持格式化嵌入式 HTML、CSS、SCSS、JS、TypeScript 等.  Vetur 只有“整个文档格式化程序”，无法格式化任意范围.


<h2 id="wasm">Webassembly</h2>


- [Twiggy](https://rustwasm.github.io/twiggy)  — 分析二进制文件的调用图以分析代码大小. 目标是缩小 wasm 二进制大小.


<h2 id="writing">写作</h2>


- [After the Deadline](https://open.afterthedeadline.com) :warning: — 拼写、风格和语法检查器.

- [alex](https://alexjs.com) — 捕捉麻木不仁、不体贴的写作

- [codespell](https://github.com/codespell-project/codespell) — 检查代码中是否存在常见拼写错误.

- [languagetool](https://languagetool.org)  — 超过 25 种语言的风格和语法检查器. 它可以发现许多简单的拼写检查器无法检测到的错误.

- [misspell-fixer](https://github.com/vlajos/misspell-fixer) — 用于修复源代码中常见拼写错误、拼写错误的快速工具.

- [Misspelled Words In Context](https://jwilk.net/software/mwic) — 拼写检查器，可对可能的拼写错误进行分组并在上下文中显示它们.

- [proselint](http://proselint.com) — 英语散文的 linter，重点关注写作风格而不是语法.

- [vale](https://docs.errata.ai/vale/about) — 用于散文的语法感知 linter，在构建时考虑了速度和可扩展性.

- [write-good](https://github.com/btford/write-good) — 专注于消除“狡猾的词语”的 linter.


<h2 id="yaml">YAML</h2>


- [Spectral](https://stoplight.io/open-source/spectral) — 灵活的 JSON/YAML linter，对 OpenAPI v2/v3 和 AsyncAPI v2 提供开箱即用的支持.

- [yamllint](https://yamllint.readthedocs.io) — 检查 YAML 文件的语法有效性、键重复和外观问题，例如行长度、尾随空格和缩进.


<h2 id="git">git</h2>


- [commitlint](https://commitlint.js.org) — 检查您的提交消息是否符合常规提交格式


## More Collections

- [Clean code linters](https://github.com/collections/clean-code-linters) — github 集合中的 linter 集合
- [Code Quality Checker Tools For PHP Projects](https://github.com/collections/code-quality-in-php) — github 集合中 PHP linter 的集合
- [go-tools](https://github.com/dominikh/go-tools) — 用于处理 Go 代码的工具和库的集合，包括 linter 和静态分析
- [linters](https://github.com/mcandre/linters) ——静态代码分析简介
- [OWASP Source Code Analysis Tools](https://owasp.org/www-community/Source_Code_Analysis_Tools) — 开放 Web 应用程序安全项目维护的工具列表
- [php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools) — 有用的 PHP 静态分析工具的回顾列表
- [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) — 静态代码分析工具列表.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Matthias Endler](https://endler.dev) 已放弃本作品的所有版权以及相关或邻接权.
用于格式化和显示该内容的底层源代码已根据 MIT 许可证获得许可.


标题图片 [Designed by Freepik](http://www.freepik.com).
