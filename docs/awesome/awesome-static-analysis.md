<div class="github-widget" data-repo="mre/awesome-static-analysis"></div>
 ![Logo](https://raw.githubusercontent.com/mre/awesome-static-analysis/master/awesome.png)

> Static program analysis is the analysis of computer software that is performed without actually executing programs — [Wikipedia](https://en.wikipedia.org/wiki/Static_program_analysis)

 这是静态分析工具和代码质量检查器的集合.  非常欢迎拉动请求！

 *：copyright：代表专有软件.  所有其他工具都是开源的.
*：警告：表示社区不建议使用此工具
  新项目已经过时或不再维护.

还看看姐妹项目， [awesome-dynamic-analysis](https://github.com/mre/awesome-dynamic-analysis).



<details>
 <summary>显示语言</summary>
  <!-- Please use HTML syntax here so that it works for Github and mkdocs -->
  <ul>
    <li><a href="#abap">ABAP</a></li>
    <li><a href="#ada">Ada</a></li>
    <li><a href="#awk">Awk</a></li>
    <li><a href="#cc">C/C++</a></li>
    <li><a href="#c">C#</a></li>
    <li><a href="#crystal">Crystal</a></li>
    <li><a href="#dlang">Dlang</a></li>
    <li><a href="#elixir">Elixir</a></li>
    <li><a href="#erlang">Erlang</a></li>
    <li><a href="#f">F#</a></li>
    <li><a href="#fortran">Fortran</a></li>
    <li><a href="#go">Go</a></li>
    <li><a href="#groovy">Groovy</a></li>
    <li><a href="#haskell">Haskell</a></li>
    <li><a href="#haxe">Haxe</a></li>
    <li><a href="#java">Java</a></li>
    <li><a href="#javascript">JavaScript</a></li>
    <li><a href="#kotlin">Kotlin</a></li>
    <li><a href="#lua">Lua</a></li>
    <li><a href="#matlab">Matlab</a></li>
    <li><a href="#perl">Perl</a></li>
    <li><a href="#php">PHP</a></li>
    <li><a href="#python">Python</a></li>
    <li><a href="#r">R</a></li>
    <li><a href="#rpg">RPG</a></li>
    <li><a href="#ruby">Ruby</a></li>
    <li><a href="#rust">Rust</a></li>
    <li><a href="#scala">Scala</a></li>
    <li><a href="#shell">Shell</a></li>
    <li><a href="#solidity">Solidity</a></li>
    <li><a href="#sql">SQL</a></li>
    <li><a href="#swift">Swift</a></li>
    <li><a href="#tcl">Tcl</a></li>
    <li><a href="#typescript">TypeScript</a></li>
    <li><a href="#vbscript">VBScript</a></li>
  </ul>
</details>





---

## Programming Languages

## ABAP

* [abaplint](https://github.com/larshp/abaplint) - 用TypeScript编写的ABAP用于ABAP.
* [abapOpenChecks](https://github.com/larshp/abapOpenChecks) - 使用新的和可自定义的检查增强SAP Code Inspector.

## Ada

* [Codepeer](http://www.adacore.com/codepeer) - 检测运行时和逻辑错误
* [Polyspace for Ada](https://www.mathworks.com/products/polyspace-ada.html) ：copyright： - 提供代码验证，证明没有溢出，被零除，越界数组访问以及源代码中的某些其他运行时错误.
* [SPARK](http://www.spark-2014.org/about) ：copyright： -  Ada的静态分析和形式验证工具集
* [Understand](https://scitools.com/ada-programming-essential/) ：copyright： - 为Ada和VHDL提供代码分析，标准测试，度量，图形，依赖性分析等的IDE.

## Awk

* [gawk --lint](https://www.gnu.org/software/gawk/manual/html_node/Options.html) - 警告其他awk实现可疑或不可移植的构造.

## C/C++

* [CBMC](http://www.cprover.org/cbmc/) - 用于C程序的有界模型检查器，用户定义的断言，标准断言，若干覆盖度量分析
* [clang-tidy](http://clang.llvm.org/extra/clang-tidy/) - 铿锵静态分析
* [CMetrics](https://github.com/MetricsGrimoire/CMetrics) - 测量C文件的大小和复杂性
* [Codecheker](https://github.com/Ericsson/codechecker) - 使用Web GUI对C / C ++代码进行静态分析
* [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) ：copyright： - 高级，完整的程序，深入的​​路径，C和C ++的静态分析，具有易于理解的解释和代码以及路径可视化.
* [Corrode](https://github.com/jameysharp/corrode)   - 从C到Rust的半自动翻译.  可以通过显示Rust编译器警告和错误来揭示原始实现中的错误.
* [cppcheck](https://github.com/danmar/cppcheck) -  C / C ++代码的静态分析
* [CppDepend](https://www.cppdepend.com) ：copyright： - 测量，查询和可视化您的代码，避免意外问题，技术债务和复杂性.
* [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) - 遵循Google风格指南的自动C ++检查程序
* [cqmetrics](https://github.com/dspinellis/cqmetrics) -  C代码的质量指标
* [CScout](https://www.spinellis.gr/cscout/) -  C和C预处理器代码的复杂性和质量指标
* [flawfinder](http://www.dwheeler.com/flawfinder/) - 发现可能存在的安全漏洞
* [flint++](http://l2program.co.uk/category/flint) -  flint的跨平台，零依赖端口，在Facebook开发和使用的C ++的lint程序.
* [Frama-C](http://frama-c.com/) - 用于C代码的声音和可扩展静态分析器
* [Helix QAC](https://www.perforce.com/products/helix-qac)  ：copyright： - 嵌入式软件的企业级静态分析.  支持MISRA，CERT和AUTOSAR编码标准.
* [IKOS](https://github.com/nasa-sw-vnv/ikos) - 基于LLVM的C / C ++代码的声音静态分析器
* [include-gardener](https://github.com/feddischson/include_gardener) - a static analyzer for C/C++/Obj-C to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
* [LDRA](https://ldra.com/) ：copyright： - 包括静态分析（TBVISION）到各种标准的工具套件，包括MISRA C＆C ++，JSF ++ AV，CWE，CERT C，CERT C ++和自定义规则.
* [oclint](http://oclint.org/) -  C / C ++代码的静态分析
* [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) ：copyright： - 识别C和C ++嵌入式软件中的运行时错误，并发问题，安全漏洞和其他缺陷.
* [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) ：copyright： - 提供代码验证，证明在C和C ++源代码中没有溢出，被零除，越界数组访问以及某些其他运行时错误.
* [scan-build](https://clang-analyzer.llvm.org/scan-build.html) - 在编译时使用LLVM分析C / C ++代码
* [splint](https://github.com/ravenexp/splint) - 注释辅助静态程序检查器
* [SVF](https://github.com/SVF-tools/SVF) - 一个静态工具，可以为C和C ++程序提供可扩展和精确的过程间依赖性分析.
* [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) -  Vera ++是一个用于验证，分析和转换C ++源代码的可编程工具.

## C# #

* [.NET Analyzers](https://github.com/DotNetAnalyzers) - 使用.NET编译器平台开发分析器（诊断和代码修复）的组织.
* [Code Analysis Rule Collection](https://carc.codeplex.com/) - 包含一组基于Microsoft .NET编译器平台“Roslyn”构建的诊断，代码修复和重构.
* [code-cracker](https://github.com/code-cracker/code-cracker) - An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.
* [CodeRush](https://www.devexpress.com/products/coderush/) ：copyright： - 在Visual Studio 2015及更高版本中使用Roslyn引擎的代码创建，调试，导航，重构，分析和可视化工具.
* [CSharpEssentials](https://github.com/DustinCampbell/CSharpEssentials) - C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features.
* [Designite](http://www.designite-tools.com)  ：copyright： -  Designite是一种软件设计质量评估工具.  它支持检测实现和设计气味，计算各种代码质量指标和趋势分析.
* [Gendarme](http://www.mono-project.com/docs/tools+libraries/tools/gendarme/) -  Gendarme检查包含ECMA CIL格式（Mono和.NET）代码的程序和库.
* [NDepend](http://www.ndepend.com/) ：copyright： - 测量，查询和可视化您的代码，避免意外问题，技术债务和复杂性.
* [Puma Scan](https://github.com/pumasecurity/puma-scan) - 随着开发团队在Visual Studio中编写代码，Puma Scan为常见漏洞（XSS，SQLi，CSRF，LDAPi，加密，反序列化等）提供实时安全代码分析.
* [Refactoring Essentials](http://vsrefactoringessentials.com/) - The free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers.
* [ReSharper](https://www.jetbrains.com/resharper/) :copyright: - Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies.
* [Roslyn Security Guard](https://dotnet-security-guard.github.io/) - 专注于识别潜在漏洞的项目，例如SQL注入，跨站点脚本（XSS），CSRF，加密弱点，硬编码密码等等.
* [Roslynator](https://github.com/JosefPihrt/Roslynator/) - A collection of 190+ analyzers and 190+ refactorings for C#, powered by Roslyn.
* [Security Code Scan](https://security-code-scan.github.io/) - Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
* [SonarLint for Visual Studio](https://vs.sonarlint.org/) -  SonarLint是Visual Studio 2015和2017的扩展，它为开发人员提供了有关注入.NET代码的新错误和质量问题的即时反馈.
* [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) - 基于Roslyn的静态分析器集合，与VS集成.
* [Wintellect.Analyzers](https://github.com/Wintellect/Wintellect.Analyzers) -  .NET编译器平台（“Roslyn”）诊断分析器和代码修复程序.

## Crystal

* [ameba](https://github.com/veelenga/ameba) -  Crystal的静态代码分析工具
* [crystal](https://crystal-lang.org/) -  Crystal编译器具有内置的linting功能.

## Dlang

* [D-scanner](https://github.com/dlang-community/D-Scanner) -  D-Scanner是一种分析D源代码的工具

## Elixir

* [credo](https://github.com/rrrene/credo) - 静态代码分析工具，侧重于代码一致性和教学.
* [sobelow](https://github.com/nccgroup/sobelow) -  Phoenix Framework的以安全为中心的静态分析

## Erlang

* [elvis](https://github.com/inaka/elvis) -  Erlang Style Reviewer

## F# #

* [FSharpLint](https://github.com/fsprojects/FSharpLint) -  F的棉绒工具#

## Fortran

* [i-Code CNES for Fortran](https://github.com/lequal/i-CodeCNES) -  Fortran 77，Fortran 90和Shell的开源静态代码分析工具.

## Go

* [deadcode](https://github.com/tsenart/deadcode) - 查找未使用的代码.
* [dingo-hunter](https://github.com/nickng/dingo-hunter) - 用于在Go中查找死锁的静态分析器.
* [dupl](https://github.com/mibk/dupl) - 报告可能重复的代码.
* [errcheck](https://github.com/kisielk/errcheck) - 检查是否使用了错误返回值.
* [flen](https://github.com/lafolle/flen) - 获取Go包中函数长度的信息.
* [gas](https://github.com/GoASTScanner/gas) - 通过扫描Go AST检查安全问题的源代码.
* [Go Meta Linter](https://github.com/alecthomas/gometalinter) - 同时运行Go lint工具并规范化输出.
* [go tool vet --shadow](https://golang.org/cmd/vet/#hdr-Shadowed_variables) - 报告可能无意中被遮蔽的变量.
* [go vet](https://golang.org/cmd/vet/) - 检查Go源代码并报告可疑.
* [go-consistent](https://github.com/Quasilyte/go-consistent) - 分析器，可帮助您使Go程序更加一致.
* [go-critic](https://github.com/go-critic/go-critic) - 转到源代码linter，维护当前未在其他链接中实现的检查.
* [go-staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - go vet on steroids, similar to ReSharper for C#.
* [go/ast](https://golang.org/pkg/go/ast/) - 包ast声明用于表示Go包的语法树的类型.
* [goconst](https://github.com/jgautheron/goconst) - 查找可以用常量替换的重复字符串.
* [gocyclo](https://github.com/fzipp/gocyclo) - 计算Go源代码中函数的圈复杂度.
* [gofmt -s](https://golang.org/cmd/gofmt/) - 检查代码是否格式正确，无法进一步简化.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - 检查丢失或未引用的包导入.
* [GolangCI-Lint](https://github.com/golangci/golangci-lint) - “Go Meta Linter”的替代方案：GolangCI-Lint是一个直接聚合器.
* [golint](https://github.com/golang/lint) - 在Go源代码中打印出编码风格错误.
* [goreporter](https://github.com/wgliang/goreporter) - 同时运行许多短路并将其输出规范化为报告.
* [goroutine-inspect](https://github.com/linuxerwang/goroutine-inspect) - 分析Golang goroutine转储的交互式工具.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - 报告代码简化.
* [gotype](https://golang.org/x/tools/cmd/gotype) - 类似于Go编译器的语法和语义分析.
* [ineffassign](https://github.com/gordonklaus/ineffassign) - 检测Go代码中的无效分配
* [interfacer](https://github.com/mvdan/interfacer) - 建议可以使用的更窄的接口.
* [lll](https://github.com/walle/lll) - 报告长线.
* [maligned](https://github.com/mdempsky/maligned) - 检测在字段排序时占用较少内存的结构.
* [megacheck](https://github.com/dominikh/go-tools/tree/master/cmd/megacheck) - 运行staticcheck，gosimple和unused，共享工作.
* [misspell](https://github.com/client9/misspell) - 查找通常拼写错误的英语单词.
* [nakedret](https://github.com/alexkohler/nakedret) - 找到裸体回报.
* [nargs](https://github.com/alexkohler/nargs) - 在函数声明中查找未使用的参数.
* [prealloc](https://github.com/alexkohler/prealloc) - 查找可能预先分配的切片声明.
* [revive](https://github.com/mgechev/revive)   -  Go的快速，可配置，可扩展，灵活和美观的linter.  直接替换golint.
* [safesql](https://github.com/stripe/safesql) -  Golang的静态分析工具，可防止SQL注入.
* [structcheck](https://github.com/opennota/check) - 查找未使用的结构字段.
* [test](http://golang.org/pkg/testing/) - 从stdlib测试模块显示测试失败的位置.
* [testify](https://github.com/stretchr/testify) - 显示失败的证词断言的位置.
* [unconvert](https://github.com/mdempsky/unconvert) - 检测冗余类型转换.
* [unimport](https://github.com/alexkohler/unimport) - 查找不必要的导入别名
* [unparam](https://github.com/mvdan/unparam) - 查找未使用的功能参数.
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - 查找未使用的变量.
* [varcheck](https://github.com/opennota/check) - 查找未使用的全局变量和常量.

## Groovy

* [CodeNarc](https://github.com/CodeNarc/CodeNarc) -  Groovy源代码的静态分析工具，支持监控和实施许多编码标准和最佳实践

## Haskell

* [HLint](https://github.com/ndmitchell/hlint) -  HLint是一个用于建议对Haskell代码进行可能改进的工具.
* [Weeder](https://github.com/ndmitchell/weeder) - 用于在Haskell代码中检测死导出或包导入的工具.

## Haxe

* [Haxe Checkstyle](https://github.com/HaxeCheckstyle/haxe-checkstyle) - 一个静态分析工具，可帮助开发人员编写符合编码标准的Haxe代码.

## Java
* [ArchUnit](https://www.archunit.org/) - 对Java体系结构进行单元测试
* [Checker Framework](https://github.com/typetools/checker-framework/) -  Java的可插入类型检查http://checkerframework.org/
* [checkstyle](https://github.com/checkstyle/checkstyle) - 检查Java源代码是否符合代码标准或一组验证规则（最佳实践）
* [ck](https://github.com/mauricioaniche/ck) - 通过处理源Java文件来计算Chidamber和Kemerer面向对象的度量
* [ckjm](http://www.spinellis.gr/sw/ckjm/) - 通过处理已编译Java文件的字节码来计算Chidamber和Kemerer面向对象的度量
* [ClassGraph](https://github.com/classgraph/classgraph) - 用于查询或可视化类元数据或类相关性的类路径和模块路径扫描程序
* [CogniCrypt](https://www.eclipse.org/cognicrypt/) - 检查Java源代码和字节代码是否存在加密API的错误使用
* [Error-prone](https://github.com/google/error-prone) - 将常见的Java错误作为编译时错误捕获
* [fb-contrib](https://github.com/mebigfatguy/fb-contrib) -  FindBugs的插件，带有额外的bug探测器
* [Find Security Bugs](https://find-sec-bugs.github.io/) - 用于Java Web应用程序安全审核的IDE / SonarQube插件.
* [google-java-format](https://github.com/google/google-java-format) -  Google Style Reformat
* [Hopper](https://github.com/cuplv/hopper) - 用scala编写的静态分析工具，用于在JVM上运行的语言
* [HuntBugs](https://github.com/amaembo/huntbugs) - 基于Procyon Compiler Tools的字节码静态分析器工具旨在取代FindBugs.
* [JArchitect](https://www.jarchitect.com) ：copyright： - 测量，查询和可视化您的代码，避免意外问题，技术债务和复杂性.
* [JBMC](http://www.cprover.org/jbmc/) -  Java（字节码）的有界模型检查器，验证用户定义的断言，标准断言，几个覆盖度量分析
* [NullAway](https://github.com/uber/NullAway)   - 具有低构建时开销的基于类型的空指针检查器;  一个 [Error Prone](http://errorprone.info/) 插入
* [OWASP Dependency Check](https://www.owasp.org/index.php/OWASP_Dependency_Check) - 检查已知的，公开披露的漏洞的依赖关系.
* [qulice](https://www.qulice.com/) - 结合了一些（预先配置的）静态分析工具（checkstyle，PMD，Findbugs，......）.
* [Soot](https://sable.github.io/soot/) - 用于分析和转换Java和Android应用程序的框架.
* [Spoon](https://github.com/INRIA/spoon)   - 库为Java编写自己的静态分析和架构规则检查器.  可以集成在Maven和Gradle中.
* [SpotBugs](https://spotbugs.github.io/)   -  SpotBugs是FindBugs的继任者.  用于静态分析的工具，用于查找Java代码中的错误.

## JavaScript

* [aether](https://github.com/codecombat/aether) - 在节点或浏览器中进行Lint，分析，规范化，转换，沙箱，运行，单步执行和可视化用户JavaScript.
* [ClosureLinter](https://github.com/google/closure-linter)   - 确保您项目的所有JavaScript代码都遵循Google JavaScript样式指南中的指南.  它还可以自动修复许多常见错误
* [coffeelint](https://github.com/clutchski/coffeelint) - 样式检查器，有助于保持CoffeeScript代码的清洁和一致性.
* [complexity-report](https://github.com/jared-stilwell/complexity-report) -  JavaScript项目的软件复杂性分析
* [DeepScan](https://deepscan.io) ：copyright： - 用于JavaScript的分析器，它针对运行时错误和质量问题，而不是编码约定.
* [escomplex](https://github.com/jared-stilwell/escomplex) -  JavaScript系列抽象语法树的软件复杂性分析.
* [eslint](https://github.com/eslint/eslint) - 一个完全可插入的工具，用于识别和报告JavaScript中的模式
* [Esprima](https://github.com/jquery/esprima) - 用于多功能分析的ECMAScript解析基础设施
* [flow](https://flow.org/) -  JavaScript的静态类型检查器.
* [jshint](https://github.com/jshint/jshint) ：警告： - 检测JavaScript代码中的错误和潜在问题，并执行您团队的编码约定
* [JSLint](https://github.com/douglascrockford/JSLint) ：警告： -  JavaScript代码质量工具
* [JSPrime](https://github.com/dpnishant/jsprime) - 静态安全分析工具
* [NodeJSScan](https://github.com/ajinabraham/NodeJsScan) -  NodeJsScan是Node.js应用程序的静态安全代码扫描程序.
* [plato](https://github.com/es-analysis/plato) - 可视化JavaScript源复杂性
* [Prettier](https://github.com/prettier/prettier) - 固定代码格式化程序.
* [quality](https://github.com/jden/quality) - 零配置代码和模块linting
* [retire.js](https://github.com/RetireJS/retire.js) - 扫描程序检测使用已知漏洞的JavaScript库
* [standard](http://standardjs.com/) - 用于检查Javascript Styleguide问题的npm模块
* [tern](https://github.com/ternjs/tern) - 用于深度跨编辑语言支持的JavaScript代码分析器
* [xo](https://github.com/xojs/xo)   - 包含许多好东西的Opinionated但可配置的ESLint包装器.  强制执行严格且可读的代码.
* [yardstick](https://github.com/calmh/yardstick) -  Javascript代码指标

## Kotlin

* [detekt](https://github.com/arturbosch/detekt) -  Kotlin代码的静态代码分析.
* [ktlint](https://github.com/shyiko/ktlint) - 带有内置格式器的反自行车Kotlin短绒

## Lua

* [luacheck](https://github.com/mpeterv/luacheck) -  Lua代码的linting和静态分析工具.

## MATLAB

* [mlint](https://de.mathworks.com/help/matlab/ref/mlint.html) ：copyright： - 检查MATLAB代码文件是否存在可能的问题.

## Perl

* [Perl::Critic](http://search.cpan.org/~thaljef/Perl-Critic-1.126/lib/Perl/Critic.pm) -  Critique Perl最佳实践的源代码.

## PHP

* [dephpend](https://github.com/mihaeu/dephpend) - 依赖性分析工具
* [deprecation-detector](https://github.com/sensiolabs-de/deprecation-detector) - 查找已弃用（Symfony）代码的用法
* [deptrac](https://github.com/sensiolabs-de/deptrac) - 实施软件层之间依赖关系的规则.
* [DesignPatternDetector](https://github.com/Halleck45/DesignPatternDetector) - 检测PHP代码中的设计模式
* [EasyCodingSt和ard](https://github.com/Symplify/EasyCodingSt和ard) - 结合 [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 和 [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
* [exakat](https://github.com/exakat/exakat) -  PHP的自动代码审查引擎
* [GrumPHP](https://github.com/phpro/grumphp) - 检查每次提交的代码
* [Mondrian](https://github.com/Trismegiste/Mondrian) - 一组使用图论的静态分析和重构工具
* [parallel-lint](https://github.com/JakubOnderka/PHP-Parallel-Lint) - 此工具检查PHP文件的语法比使用更高级别的输出进行串行检查更快.
* [Parse](https://github.com/psecio/parse) - 静态安全扫描程序
* [pdepend](https://pdepend.org/) - Calculates software metrics like cyclomatic complexity for PHP code.
* [phan](https://github.com/etsy/phan) - 来自etsy的现代静态分析仪
* [PHP Assumptions](https://github.com/rskuipers/php-assumptions) - 检查弱假设
* [PHP Coding Standards Fixer](http://cs.sensiolabs.org/) - 根据PSR-1，PSR-2和Symfony标准等标准修复代码.
* [Php Inspections (EA Extended)](https://github.com/kalessil/phpinspectionsea) - 用于PHP的静态代码分析器.
* [PHP Refactoring Browser](https://github.com/QafooLabs/php-refactoring-browser) - 重构帮助者
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - 根据语义版本控制建议下一个版本
* [PHP-Parser](https://github.com/nikic/PHP-Parser) - 用PHP编写的PHP解析器
* [PHP-Token-Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) - 模拟PHP内部反射的库
* [php7cc](https://github.com/sstalle/php7cc) -  PHP 7兼容性检查器
* [php7mar](https://github.com/Alexia/php7mar) - 帮助开发人员快速将代码移植到PHP 7
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - 检测违反一组定义的编码标准
* [phpca](https://github.com/wapmorgan/PhpCodeAnalyzer) - 查找非内置扩展的使用情况
* [phpcf](http://wapmorgan.github.io/PhpCodeFixer/) - 查找已弃用的PHP功能的使用
* [phpcpd](https://github.com/sebastianbergmann/phpcpd) -  PHP代码的复制/粘贴检测器.
* [phpdcd](https://github.com/sebastianbergmann/phpdcd) - 用于PHP代码的死代码检测器（DCD）.
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - 为项目构建依赖图
* [phpdoc-to-typehint](https://github.com/dunglas/phpdoc-to-typehint) - 使用PHPDoc注释向现有PHP项目添加标量类型提示和返回类型
* [phpDocumentor](https://www.phpdoc.org/) - 分析PHP源代码以生成文档
* [PHPMD](https://phpmd.org/) - 在您的代码中发现可能的错误
* [PhpMetrics](http://www.phpmetrics.org/) - 计算和可视化各种代码质量指标
* [phpmnd](https://github.com/povils/phpmnd) - 帮助检测幻数
* [PHPQA](https://github.com/EdgedesignCZ/phpqa) - 运行QA工具的工具（phploc，phpcpd，phpcs，pdepend，phpmd，phpmetrics）
* [phpqa - jakzal](https://github.com/jakzal/phpqa) - 在一个容器中用于PHP静态分析的许多工具
* [phpqa - jmolivas](https://github.com/jmolivas/phpqa) -  PHPQA all-in-one Analyzer CLI工具
* [phpsa](https://github.com/ovr/phpsa) -  PHP的静态分析工具.
* [PHPStan](https://github.com/phpstan/phpstan) -  PHP静态分析工具 - 发现代码中的错误而不运行它！
* [Progpilot](https://github.com/designsecurity/progpilot) - 用于安全目的的静态分析工具
* [Psalm](https://getpsalm.org/) - 用于在PHP应用程序中查找类型错误的静态分析工具
* [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) - 可视化指标和源代码
* [RIPS](https://www.ripstech.com/) ：copyright： - 用于PHP脚本漏洞的静态源代码分析器
* [Tuli](https://github.com/ircmaxell/Tuli) - 静态分析引擎
* [twig-lint](https://github.com/asm89/twig-lint) -  twig-lint是你的twig文件的lint工具.
* [WAP](https://www.owasp.org/index.php/OWASP_WAP-Web_Application_Protection) - 用于检测和纠正PHP（4.0或更高版本）Web应用程序中的输入验证漏洞的工具，并通过组合静态分析和数据挖掘来预测误报.

## Python

* [bandit](https://github.com/PyCQA/bandit) - 一种在Python代码中查找常见安全问题的工具
* [bellybutton](https://github.com/hchasestevens/bellybutton) - 支持自定义项目特定规则的linting引擎
* [Black](https://github.com/ambv/black) - 毫不妥协的Python代码格式化程序
* [cohesion](https://github.com/mschwager/cohesion) - 用于测量Python类内聚力的工具
* [jedi](https://github.com/davidhalter/jedi) - 用于Python的自动完成/静态分析库
* [linty fresh](https://github.com/lyft/linty_fresh) - 解析lint错误并将其作为拉取请求的注释报告给Github
* [mccabe](https://github.com/PyCQA/mccabe) - 检查McCabe的复杂性
* [mypy](https://github.com/python/mypy) - 一种静态类型检查器，旨在结合鸭子类型和静态类型的好处，经常使用 [MonkeyType](https://github.com/Instagram/MonkeyType)
* [py-find-injection](https://github.com/uber/py-find-injection) - 在Python代码中查找SQL注入漏洞
* [pycodestyle](https://github.com/PyCQA/pycodestyle) - （以前称为“pep8”）根据PEP 8中的一些样式约定检查Python代码
* [pydocstyle](https://github.com/PyCQA/pydocstyle) - 检查是否符合Python文档字符串约定
* [pyflakes](https://github.com/pyflakes/pyflakes/) - 检查Python源文件是否有错误
* [pylint](https://github.com/PyCQA/pylint)   - 查找编程错误，帮助强制执行编码标准并嗅探某些代码异味.  它还包括`pyreverse`（一个UML图生成器）和`symilar`（一个相似性检查器）.
* [pyre-check](https://github.com/facebook/pyre-check) - 适用于大型Python代码库的快速，可扩展的类型检查器
* [pyright](https://github.com/Microsoft/pyright) - 用于Python的静态类型检查器，用于解决现有工具（如mypy）中的空白.
* [pyroma](https://github.com/regebro/pyroma) - 评估Python项目符合Python打包生态系统最佳实践的程度，并列出可以改进的问题
* [PyT - Python Taint](https://github.com/python-security/pyt) - 用于检测Python Web应用程序中的安全漏洞的静态分析工具.
* [pytype](https://github.com/google/pytype) -  Python代码的静态类型分析器.
* [radon](https://github.com/rubik/radon) - 一个Python工具，用于计算源代码中的各种指标
* [vulture](https://github.com/jendrikseipp/vulture) - 在Python代码中查找未使用的类，函数和变量
* [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - 有史以来最严格，最自以为是的蟒蛇皮
* [wily](https://github.com/tonybaloney/wily) - 用于归档，探索和绘制Python源代码复杂性的命令行工具
* [xenon](https://github.com/rubik/xenon) - 使用监控代码复杂性 [`radon`](https://github.com/rubik/radon)

## Python wrappers

* [ciocheck](https://github.com/ContinuumIO/ciocheck)   -  linter，formatter和test suite helper.  作为一个linter，它是`pep8`，`pydocstyle`，`flake8`和`pylint`的包装器.
* [flake8](https://github.com/PyCQA/flake8) - 围绕`pyflakes`，`pycodestyle`和`mccabe`的包装
* [multilint](https://github.com/adamchainz/multilint) - 围绕`flake8`，`isort`和`modernize`的包装
* [prospector](https://github.com/PyCQA/prospector) - 围绕`pylint`，`pep8`，`mccabe`等的包装

## R

* [cyclocomp](https://github.com/MangoTheCat/cyclocomp) - 量化R函数/表达式的圈复杂度.
* [goodpractice](http://mangothecat.github.io/goodpractice/) - 分析R包的源代码并提供最佳实践建议.
* [lintr](https://github.com/jimhester/lintr) -  R的静态代码分析
* [styler](https://styler.r-lib.org/) -  R源代码文件的格式化和R代码的漂亮打印.

## RPG

* [SourceMeter](https://www.sourcemeter.com/resources/rpg/) ：copyright： -  RPG III和RPG IV版本的静态代码分析（包括自由格式）

## Ruby

* [brakeman](https://github.com/presidentbeef/brakeman) - 用于Ruby on Rails应用程序的静态分析安全漏洞扫描程序
* [cane](https://github.com/square/cane) - 代码质量阈值检查作为构建的一部分
* [dawnscanner](https://github.com/thesp0nge/dawnscanner)   - 用于ruby编写的Web应用程序的静态分析安全扫描程序.  它支持Sinatra，Padrino和Ruby on Rails框架.
* [flay](https://github.com/seattlerb/flay) -  Flay分析代码的结构相似性.
* [flog](https://github.com/seattlerb/flog)   -  Flog在易于阅读的痛苦报告中报告最受折磨的代码.  分数越高，代码就越痛苦.
* [laser](https://github.com/michaeledgar/laser) -  Ruby代码的静态分析和样式linter.
* [pelusa](https://github.com/codegram/pelusa) - 静态分析Lint类型工具，以改善您的OO Ruby代码
* [quality](https://github.com/apiology/quality) - 使用社区工具对您的代码进行质量检查，并确保您的数字不会随着时间的推移而变得更糟.
* [Querly](https://github.com/soutaro/querly) - 基于模式的Ruby检查工具
* [Railroader](https://railroader.org/) - 用于Ruby on Rails应用程序的开源静态分析安全漏洞扫描程序.
* [reek](https://github.com/troessner/reek) -  Ruby的代码气味检测器
* [RuboCop](https://github.com/rubocop-hq/rubocop) -  Ruby静态代码分析器，基于社区Ruby样式指南.
* [Rubrowser](https://github.com/blazeeboy/rubrowser) -  Ruby类交互式依赖图生成器.
* [ruby-lint](https://github.com/YorickPeterse/ruby-lint) -  Ruby的静态代码分析
* [rubycritic](https://github.com/whitesmith/rubycritic) -  Ruby代码质量记者
* [SandiMeter](https://github.com/makaroni4/sandi_meter) - 用于检查Sandi Metz规则的Ruby代码的静态分析工具.
* [Sorbet](https://github.com/sorbet/sorbet) - 为Ruby设计的快速，强大的类型检查器

## Rust

* [cargo-audit](https://github.com/RustSec/cargo-audit) - 审核Cargo.lock用于报告有安全漏洞的板条箱 [RustSec Advisory Database](https://github.com/RustSec/advisory-db/).
* [cargo-inspect](https://github.com/mre/cargo-inspect) - 检查没有语法糖的Rust代码，看看编辑器在窗帘后面做了什么.
* [clippy](https://github.com/Manishearth/rust-clippy) - 用于捕获常见错误并改进Rust代码的代码linter
* [electrolysis](https://github.com/Kha/electrolysis) - 通过将Rust程序转换为精益定理证明器中的定义来正式验证Rust程序的工具.
* [herbie](https://github.com/mcarton/rust-herbie-lint) - 使用数值不稳定的浮点表达式时，向包中添加警告或错误.
* [linter-rust](https://github.com/AtomLinter/linter-rust) - 使用rustc和货物将你的Rust文件存放在Atom中
* [Rust Language Server](https://github.com/rust-lang-nursery/rls) - 支持“goto definition”，符号搜索，重新格式化和代码完成等功能，并支持重命名和重构.
* [rustfix](https://github.com/killercup/rustfix) - 阅读并应用rustc（和第三方lints，如clippy提供的那些）提出的建议.

## Scala

* [linter](https://github.com/HairyFotr/linter) --Linter是一个Scala静态分析编译器插件，它为各种可能的错误，低效率和样式问题添加了编译时检查.
* [Scalastyle](http://www.scalastyle.org) -  Scalastyle检查您的Scala代码并指出它的潜在问题.
* [scapegoat](https://github.com/sksamuel/scapegoat) - 用于静态代码分析的Scala编译器插件
* [WartRemover](https://github.com/puffnfresh/wartremover) - 灵活的Scala代码linting工具.

## Shell

* [i-Code CNES for Shell](https://github.com/lequal/i-CodeCNES) -  Shell和Fortran（77和90）的开源静态代码分析工具.
* [shellcheck](https://github.com/koalaman/shellcheck) -  ShellCheck，一个静态分析工具，为bash / sh shell脚本提供警告和建议

## Solidity

* [slither](https://github.com/trailofbits/slither) - 静态分析框架，运行一套漏洞检测器，打印有关合同细节的可视信息，并提供API以轻松编写自定义分析
* [solium](https://github.com/duaraghav8/Solium) -  Solium是识别和修复Solidity智能合约中的样式和安全问题的短信

## SQL

* [sqlcheck](https://github.com/jarulraj/sqlcheck) - 自动识别SQL查询中的反模式
* [sqlint](https://github.com/purcell/sqlint) - 简单的SQL linter
* [tsqllint](https://github.com/tsqllint/tsqllint) - 特定于T-SQL的linter
* [TSqlRules](https://github.com/ashleyglee/TSqlRules) -  SQL Server的TSQL静态代码分析规则

## Swift

* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - 用于重新格式化Swift代码的库和命令行格式化工具
* [SwiftLint](https://github.com/realm/SwiftLint) - 一种强制执行Swift风格和约定的工具
* [Tailor](https://github.com/sleekbyte/tailor) - 用于使用Apple的Swift编程语言编写的源代码的静态分析和lint工具.

## Tcl

* [Frink](https://catless.ncl.ac.uk/Programs/Frink/) - 一个Tcl格式和静态检查程序（可以美化程序，最小化，混淆或只是完整性检查它）.
* [Nagelfar](https://sourceforge.net/projects/nagelfar/) -  Tcl的静态语法检查器
* [tclchecker](https://github.com/ActiveState/tdk/blob/master/docs/3.0/TDK_3.0_Checker.txt) - 静态语法分析模块（作为 [TDK](https://github.com/ActiveState/tdk)).

## TypeScript

* [Codelyzer](https://github.com/mgechev/codelyzer) - 一组用于Angular 2 TypeScript项目的静态代码分析的tslint规则.
* [TSLint](https://github.com/palantir/tslint) -  TypeScript语言的可扩展linter.
* [tslint-clean-code](https://github.com/Glavin001/tslint-clean-code) - 一套受Clean Code手册启发的TSLint规则.
* [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib) - 一组用于Microsoft维护的TypeScript项目的静态代码分析的tslint规则.

## VBScript

* [Test Design Studio](http://patterson-consulting.net/tds) ：copyright： - 一个完整的IDE，带有静态代码分析，用于Micro Focus Unified Functional Testing基于VBScript的自动化测试.

## Multiple languages

* [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) :copyright: - Static analysis for C/C++/C#, PHP and Java
* [Application Inspector](https://www.ptsecurity.com/ww-en/products/ai/) :copyright: - Commercial Static Code Analysis which generates exploits to verify vulnerabilities. Supports: Java (including JSP and JSF), C#, VB.Net, ASP.NET, Php, JavaScript, Objective-C, Swift, C\C++, SQL (PL/SQL. T-SQL. MySQL), HTML5
* [AppScan](https://www.ibm.com/support/knowledgecenter/en/SSS9LM_9.0.3/com.ibm.rational.appscansrc.install.doc/topics/system_requirements_language_support.html) :copyright: - Commercial Static Code Analysis. Supports: Microsoft .NET Framework (C#, ASP.NET, VB.NET), ASP (JavaScript/VBScript), C/C++, COBOL, ColdFusion, JavaScript, JavaServer Pages (JSP), Java™ (including support for Android APIs), Perl, PHP, PL/SQL, T-SQL, Visual Basic 6
* [APPscreener](https://appscreener.us) :copyright: - Static code analysis for binary and source code - Java/Scala, PHP, Javascript, C#, PL/SQL, Python, T-SQL, C/C++, ObjectiveC/Swift, Visual Basic 6.0, Ruby, Delphi, ABAP, HTML5 and Solidity
* [Axivion Bauhaus Suite](https://www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: - Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95
* [Checkmarx](https://www.checkmarx.com/technology/supported-coding-languages/) :copyright: - Commercial Static Code Analysis which doesn't require pre-compilation. Supports: Android (Java), Apex and VisualForce, ASP, C#, C/C++, Go, Groovy, HTML5, Java, JavaScript, Node.js, Objective C, Perl, PhoneGap, PHP, Python, Ruby, Scala, Swift, VB.NET, VB6, VBScript
* [coala](https://coala.io/) - 用于创建代码分析的语言无关框架 - 支持 [over 60 languages](https://coala.io/languages) 默认情况下
* [Cobra](http://spinroot.com/cobra/)  ：copyright： - 美国宇航局喷气推进实验室的结构源代码分析仪.  支持C，C ++，Ada和Python.
* [codeburner](https://github.com/groupon/codeburner) - 提供统一的界面，对发现的问题进行排序和处理
* [CodeFactor](https://codefactor.io) :copyright: - Static Code Analysis for C#, C, C++, CoffeeScript, CSS, Groovy, GO, JAVA, JavaScript, Less, Python, Ruby, Scala, SCSS, TypeScript.
* [CodeIt.Right](https://submain.com/products/codeit.right.aspx) :copyright: - CodeIt.Right&trade; provides a fast, automated way to ensure that your source code adheres to (your) predefined design and style guidelines as well as best coding practices. Supported languages: C#, VB.NET.
* [CodeScene](https://empear.com/) ：copyright： -  CodeScene优先考虑技术债务，发现社交模式并识别代码中隐藏的风险.
* [cqc](https://github.com/xcatliu/cqc) - 检查js，jsx，vue，css，less，scss，sass和styl文件的代码质量.
* [Depends](https://github.com/multilang-depends/depends) - 分析Java，C / C ++，Ruby的代码元素的综合依赖性.
* [DevSkim](https://github.com/microsoft/devskim) - Regex-based static analysis tool for Visual Studio, VS Code, and Sublime Text - C/C++, C#, PHP, ASP, Python, Ruby, Java, and others.
* [Fortify](https://software.microfocus.com/en-us/products/static-code-analysis-sast/overview) :copyright: A commercial static analysis platform that supports the scanning of C/C++, C#, VB.NET, VB6, ABAP/BSP, ActionScript, Apex, ASP.NET, Classic ASP, VB Script, Cobol, ColdFusion, HTML, Java, JS, JSP, MXML/Flex, Objective-C, PHP, PL/SQL, T-SQL, Python (2.6, 2.7), Ruby (1.9.3), Swift, Scala, VB, and XML.
* [Goodcheck](https://github.com/sideci/goodcheck) - 基于Regexp的可定制linter
* [graudit](https://github.com/wireghoul/graudit) - Grep rough audit - source code auditing tool - C/C++, PHP, ASP, C#, Java, Perl, Python, Ruby
* [Hound CI](https://houndci.com/)   - 关于GitHub拉取请求中的样式违规的评论.  支持Coffeescript，Go，HAML，JavaScript，Ruby，SCSS和Swift.
* [imhotep](https://github.com/justinabrahms/imhotep) - 评论进入您的存储库的提交并检查语法错误和一般lint警告.
* [Infer](https://github.com/facebook/infer) - 用于Java，C和Objective-C的静态分析器
* [Klocwork](http://www.klocwork.com/products-services/klocwork) ：copyright： - 质量和安全性C / C ++，Java和C的静态分析#
* [Kiuwan](https://www.kiuwan.com/code-security-sast/) :copyright: - Identify and remediate cyber threats in a blazingly fast, collaborative environment, with seamless integration in your SDLC. Python, C\C++, Java, C#, PHP and more
* [oclint](https://github.com/oclint/oclint) - 静态源代码分析工具，用于提高质量并减少C，C ++和Objective-C的缺陷
* [pfff](https://github.com/facebook/pfff) -  Facebook的工具，用于代码分析，可视化或保留多种语言的源代码转换
* [PMD](https://pmd.github.io/) - 用于Java，Javascript，PLSQL，XML，XSL等的源代码分析器
* [Pronto](https://github.com/prontolabs/pronto)   - 对您的更改进行快速自动代码审查.  支持40多种不同语言的跑步者，包括Clang，Elixir，JavaSCript，PHP，Ruby等
* [pre-commit](https://github.com/pre-commit/pre-commit) - 用于管理和维护多语言预提交挂钩的框架.
* [PT.PM](https://github.com/PositiveTechnologies/PT.PM) - An engine for searching patterns in the source code, based on Unified AST or UST. At present time C#, Java, PHP, PL/SQL, T-SQL, and JavaScript are supported. Patterns can be described within the code or using a DSL.
* [PVS-Studio](https://www.viva64.com/en/pvs-studio/) ：copyright： -  a（[conditionally free](https://www.viva64.com/en/b/0457/) for FOSS) static analysis of C/C++ and C# code. For advertising purposes [you can propose a large FOSS project for analysis by PVS employees](https://github.com/viva64/pvs-studio-check-list).
* [Reviewdog](https://github.com/haya14busa/reviewdog) - 用于在任何代码托管服务中发布任何linter的评论评论的工具.
* [Security Code Scan](https://security-code-scan.github.io/) - Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
* [Semmle QL and LGTM](https://semmle.com/)  ：copyright： - 使用源代码查询查找安全漏洞，变体和关键代码质量问题.  自动PR代码审查;  免费为公众GitHub / Bitbucket回购： [LGTM.com](https://LGTM.com).
* [shipshape](https://github.com/google/shipshape) - 静态程序分析平台，允许自定义分析仪通过通用接口插入
* [SonarQube](http://www.sonarqube.org/) -  SonarQube是一个管理代码质量的开放平台.
* [STOKE](https://github.com/StanfordPL/stoke)   - 用于x86_64指令集的编程语言无关的随机优化器.  它使用随机搜索来探索所有可能的程序转换的极高维度空间
* [Synopsys](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - A commercial static analysis platform that allows for scanning of multiple languages (C/C++, Android, C#, Java, JS, PHP, Python, Node.JS, Ruby, Fortran, and Swift)
* [TscanCode](https://github.com/Tencent/TscanCode) - A fast and accurate static analysis solution for C/C++, C#, Lua codes provided by Tencent. Using GPLv3 license.
* [Undebt](https://github.com/Yelp/undebt) - 基于简单模式定义的大规模自动可编程重构的独立于语言的工具
* [Veracode](http://www.veracode.com/products/static-analysis-sast/static-code-analysis)  ：copyright： - 在不需要源代码的情况下查找二进制文件和字节码中的缺陷.  支持所有主要的编程语言：Java，.NET，JavaScript，Swift，Objective-C，C，C ++等.
* [WALA](http://wala.sourceforge.net/wiki/index.php/Main_Page) -  Java字节码和相关语言以及JavaScript的静态分析功能
* [Wotan](https://github.com/fimbullinter/wotan) - 可插入的TypeScript和JavaScript linter
* [XCode](https://developer.apple.com/xcode/) ：copyright： -  XCode提供了相当不错的用户界面 [Clang's](http://clang-analyzer.llvm.org/xcode.html) 静态代码分析器（C / C ++，Obj-C）

## Other

## Build tools

* [checkmake](https://github.com/mrtazz/checkmake) -  Makefile的Linter / Analyzer
* [codechecker](https://github.com/Ericsson/codechecker) -  Clang Static Analyzer的缺陷数据库和查看器扩展

## Binaries

* [BinSkim](https://github.com/Microsoft/binskim) - 二进制静态分析工具，为Windows便携式可执行文件提供安全性和正确性结果.
* [cwe_checker](https://github.com/fkie-cad/cwe_checker) -  cwe_checker在二进制可执行文件中查找易受攻击的模式.
* [Jakstab](https://github.com/jkinder/jakstab) -  Jakstab是一个基于抽象解释的集成反汇编和静态分析框架，用于设计可执行文件分析和恢复可靠的控制流图.
* [Twiggy](https://github.com/rustwasm/twiggy)   - 分析二进制的调用图以分析代码大小.  目标是减少二进制文件.


## Containers

* [anchore](https://anchore.io/) - 发现，分析和认证容器图像
* [clair](https://github.com/coreos/clair) - 容器的漏洞静态分析
* [collector](https://github.com/banyanops/collector) - 在容器内运行任意脚本，并收集有用的信息
* [dagda](https://github.com/eliasgranderubio/dagda) - Perform static analysis of known vulnerabilities in docker images/containers.
* [Docker Label Inspector](https://github.com/garethr/docker-label-inspector) -  Lint并验证Dockerfile标签
* [Haskell Dockerfile Linter](https://github.com/lukasmartinelli/hadolint) - 更智能的Dockerfile linter，帮助您构建最佳实践Docker镜像
* [kube-score](https://github.com/zegl/kube-score) -  Kubernetes对象定义的静态代码分析.


## Config Files

* [dotenv-linter](https://github.com/wemake-services/dotenv-linter) -  Linting dotenv文件就像一个魅力.
* [gixy](https://github.com/yandex/gixy)   - 分析Nginx配置的工具.  主要目标是防止错误配置并自动进行缺陷检测.

## Configuration Management

* [ansible-lint](https://github.com/willthames/ansible-lint) - 检查剧本中可能会改进的做法和行为
* [cfn-lint](https://github.com/awslabs/cfn-python-lint) -  AWS Labs CloudFormation linter.
* [cfn_nag](https://github.com/stelligent/cfn_nag) -  AWS CloudFormation模板的linter.
* [cookstyle](https://docs.chef.io/cookstyle.html) -  Cookstyle是一款基于RuboCop Ruby linting工具的linting工具，适用于Chef cookbook
* [foodcritic](http://www.foodcritic.io/) - 一个lint工具，可检查Chef cookbook中的常见问题.
* [Puppet Lint](https://github.com/rodjek/puppet-lint) - 检查您的Puppet清单是否符合样式指南.
* [terrascan](https://github.com/cesar-rodriguez/terrascan) - 收集Terraform模板静态代码分析的安全性和最佳实践测试.
* [tflint](https://github.com/wata727/tflint) - 用于检测“terraform plan”无法检测到的错误的Terraform linter.


## CSS

* [CSS Stats](https://github.com/cssstats/cssstats) - 样式表上可能有趣的统计数据
* [CSScomb](https://github.com/csscomb/csscomb.js)   -  CSS的编码风格格式化程序.  支持自己的配置，使样式表美观且一致
* [CSSLint](https://github.com/CSSLint/csslint) - 进行基本语法检查并发现有问题的模式或效率低下的迹象
* [GraphMyCSS.com](https://graphmycss.com) -  CSS特异性图生成器
* [Parker](https://github.com/katiefenn/parker) - 样式表分析工具
* [Project Wallace CSS Analyzer](https://github.com/projectwallace/css-analyzer) -  CSS的分析，部分 [Project Wallace](https://www.projectwallace.com)
* [sass-lint](https://github.com/sasstools/sass-lint) - 用于sass和scss语法的仅限节点的Sass linter.
* [scsslint](https://github.com/brigade/scss-lint) -  SCSS文件的Linter
* [Specificity Graph](https://github.com/pocketjoso/specificity-graph) -  CSS特异性图生成器
* [Stylelint](http://stylelint.io/) -  SCSS / CSS文件的Linter

## Gherkin

* [gherkin-lint](https://github.com/vsiakka/gherkin-lint) - 用Javascript编写的Gherkin-Syntax的linter.

## HTML

* [HTML Inspector](https://github.com/philipwalton/html-inspector) -  HTML Inspector是一种代码质量工具，可帮助您和您的团队编写更好的标记.
* [HTML Tidy](http://www.html-tidy.org/) - 通过修复标记错误并将遗留代码升级到现代标准来更正和清理HTML和XML文档.
* [HTMLHint](https://github.com/yaniswang/HTMLHint) -  HTML的静态代码分析工具
* [Polymer-analyzer](https://github.com/Polymer/polymer-analyzer) - A static analysis framework for Web Components.


## IDE Plugins

* [ale](https://github.com/w0rp/ale) -  Vim和NeoVim的异步Lint引擎，支持多种语言
* [Attackflow Extension](https://www.attackflow.com/Extension) ：copyright： -  Visual Studio的Attackflow插件，使开发人员能够在没有任何先验知识的情况下在源代码中实时发现关键的安全漏洞.
* [DevSkim](https://github.com/Microsoft/DevSkim)   - 内联，实时安全分析.  适用于多种编程语言和IDE（VS，VS代码，Sublime Text，...）.
* [Puma Scan](https://github.com/pumasecurity/puma-scan) - 随着开发团队在Visual Studio中编写代码，Puma Scan为常见漏洞（XSS，SQLi，CSRF，LDAPi，加密，反序列化等）提供实时安全代码分析.
* [Security Code Scan](https://security-code-scan.github.io/) - Security code analyzer for C# and VB.NET that integrates into Visual Studio 2015 and newer. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
* [vint](https://github.com/Kuniwak/vint) - 由Python实现的快速且高度可扩展的Vim脚本语言Lint.

## LaTeX

* [ChkTeX](http://www.nongnu.org/chktex/) -  LaTex的一个linter，它可以解决LaTeX监管的一些印刷错误.
* [lacheck](https://www.ctan.org/pkg/lacheck) - 用于查找LaTeX文档中常见错误的工具.

## Makefiles

* [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) -  FreeBSD和DragonFlyBSD端口目录的验证程序.

## Markdown

* [markdownlint](https://github.com/DavidAnson/markdownlint) - 用于Markdown / CommonMark文件的基于Node.js的样式检查器和lint工具.
* [mdl](https://github.com/mivok/markdownlint) - A tool to check Markdown files and flag style issues.

## Mobile

* [android-lint-summary](https://github.com/passy/android-lint-summary) - 将多个项目的lint错误合并到一个输出中，一次检查多个子项目的lint结果.
* [FlowDroid](https://github.com/secure-software-engineering/soot-infoflow-android) - 适用于Android应用程序的静态污点分析工具
* [paprika](https://github.com/GeoffreyHecht/paprika) - 用于检测分析的Android应用程序中的某些代码气味的工具包.
* [qark](https://github.com/linkedin/qark) - 查找多个与安全相关的Android应用程序漏洞的工具

## Packages

* [lintian](https://github.com/Debian/lintian) -  Debian软件包的静态分析工具
* [rpmlint](https://github.com/rpm-software-management/rpmlint) - 用于检查rpm包中常见错误的工具

## Supporting Tools

* [LibVCS4j](https://github.com/uni-bremen-agst/libvcs4j) - 一个Java库，允许现有工具通过为不同版本控制系统和问题跟踪器提供通用API来分析软件系统的演变.
* [Violations Lib](https://github.com/tomasbjerre/violations-lib)   - 用于从静态代码分析中解析报告文件的Java库.  由一堆Jenkins，Maven和Gradle插件使用.

## Template-Languages

* [ember-template-lint](https://github.com/rwjblue/ember-template-lint) - 用于Ember或Handlebars模板的Linter.
* [haml-lint](https://github.com/brigade/haml-lint) - 用于编写干净且一致的HAML的工具
* [slim-lint](https://github.com/sds/slim-lint) - 用于分析Slim模板的可配置工具
* [yamllint](https://github.com/adrienverge/yamllint) - 检查YAML文件的语法有效性，密钥重复和整容问题，如行长度，尾随空格和缩进.

## Translation

* [dennis](https://github.com/willkg/dennis/) - 一组用于处理PO文件的实用程序，以简化开发并提高质量.

## Writing

* [After the Deadline](https://afterthedeadline.com/) ：警告： - 拼写，风格和语法检查
* [codespell](https://github.com/codespell-project/codespell) - 检查常见拼写错误的代码
* [languagetool](https://github.com/languagetool-org/languagetool)   -  25种语言的风格和语法检查.  它发现了一个简单的拼写检查程序无法检测到的许多错误.
* [misspell-fixer](https://github.com/vlajos/misspell-fixer) - 用于修复常见拼写错误的快速工具，源代码中的拼写错误
* [Misspelled Words In Context](https://github.com/jwilk/mwic) - 一种拼写检查器，可以对可能的拼写错误进行分组并在其上下文中显示它们
* [proselint](https://github.com/amperser/proselint/) - 英语散文的点缀，专注于写作风格而不是语法.
* [vale](https://github.com/ValeLint/vale) - 一个可定制的，语法感知的散文linter.
* [write-good](https://github.com/btford/write-good) - 一个专注于消除“狡猾的话”的短信.

## Web services
* [Codacy](https://www.codacy.com/) ：copyright： - 代码分析，以更快的速度发布更好的代码.
* [Code Climate](https://codeclimate.com/) ：copyright： - 开放和可扩展的静态分析平台，适合所有人.
* [Code Inspector](https://www.code-inspector.com) ：copyright： - 支持10种以上语言的代码质量和技术债务管理平台.
* [CodeFactor](https://codefactor.io) ：copyright： - 在GitHub或BitBucket上重新发布的自动代码分析.
* [CodeFlow](https://www.getcodeflow.com)  ：copyright： - 自动代码分析工具，以处理技术深度.  与Bitbucket和Gitlab集成.  （免费开源项目）
* [Gamma](https://mygamma.io) :copyright: - An intelligent software analytics platform that identifies issues from multiple lenses: Design issues, code issues, duplication and metrics. Available for Java, C, C++ and C#.
* [kiuwan](https://www.kiuwan.com/) ：copyright： - 云中的软件分析支持超过22种编程语言.
* [Landscape](https://landscape.io/) ：copyright： -  Python的静态代码分析
* [Layered Insight](https://layeredinsight.com/) ：copyright： - 容器本机应用程序保护，以提供容器化应用程序的可见性和控制.
* [LGTM.com](https://lgtm.com/)  ：copyright： - 对GitHub和Bitbucket进行深度代码分析，以发现安全漏洞和关键代码质量问题（使用Semmle QL）.  拉取请求的自动代码审查;  公共存储库免费.
* [Nitpick CI](https://nitpick-ci.com) ：copyright： - 自动PHP代码审查
* [PullRequest](https://www.pullrequest.com) ：copyright： - 代码审查作为具有内置静态分析的服务
* [QuantifiedCode](https://www.quantifiedcode.com/) - 自动代码审查和修复
* [Reshift](https://softwaresecured.com/reshift/) ：copyright： - 用于检测和管理Java安全漏洞的源代码分析工具.
* [Scrutinizer](https://scrutinizer-ci.com/) ：copyright： - 可与GitHub集成的专有代码质量检查程序
* [SensioLabs Insight](https://insight.sensiolabs.com/) ：copyright： - 检测安全风险，发现错误并为PHP项目提供可操作的指标
* [Sider](https://sider.review)  ：copyright： - 自动代码审查工具.  提高开发人员的生产力
* [Snyk](https://snyk.io/) ：copyright： - 针对node.js应用程序依赖项的漏洞扫描程序（开源项目免费）
* [SonarCloud](https://sonarcloud.io)  ：copyright： - 基于云的多语言静态代码分析.  历史，趋势，安全热点，拉动请求分析等.  免费开源.
* [Teamscale](http://www.teamscale.com/)  ：copyright： - 支持超过25种语言和直接IDE集成的静态和动态分析工具.  可根据要求免费托管开源项目.  免费学术许可证.
* [Upsource](https://www.jetbrains.com/upsource/) ：copyright： - 具有静态代码分析和代码感知导航的代码审查工具，适用于Java，PHP，JavaScript和Kotlin.

## More collections

* [go-tools](https://github.com/dominikh/go-tools) - 用于处理Go代码的工具和库的集合，包括链接和静态分析
* [linters](https://github.com/mcandre/linters) - 静态代码分析简介
* [php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools) - 经过审核的有用PHP静态分析工具列表
* [Tools for Tcl](https://wiki.tcl-lang.org/page/Static+syntax+analysis#95329c336da897c3dea8ab434ca30575f4529bf6f514c1519881bd126e1d1423) - 一个包含多个Tcl检查器和静态语法分析工具的wiki页面.
* [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) - 静态代码分析工具列表.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Matthias Endler](http://matthias-endler.de) 已放弃对此作品的所有版权及相关或相邻权利.
标题图片 [Designed by Freepik](http://www.freepik.com).
