<div class="github-widget" data-repo="mre/awesome-static-analysis"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
 ![Logo](https://raw.githubusercontent.com/mre/awesome-static-analysis/master/awesome.png)

&gt;静态程序分析是对未实际执行程序的情况下执行的计算机软件的分析， [Wikipedia](https://en.wikipedia.org/wiki/Static_program_analysis)

 这是静态分析工具和代码质量检查器的集合.  拉请求非常欢迎！

 *：版权：代表专有软件.  所有其他工具都是开源的.
*：警告：表示社区不建议将此工具用于
  已经过时或不再维护的新项目.

还要检查姐妹项目， [awesome-dynamic-analysis](https://github.com/mre/awesome-dynamic-analysis).



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
    <li><a href="#delphi">Delphi</a></li>
    <li><a href="#dlang">Dlang</a></li>
    <li><a href="#elixir">Elixir</a></li>
    <li><a href="#elm">Elm</a></li>
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

* [abaplint](https://github.com/larshp/abaplint) -用TypeScript编写的ABAP的Linter.
* [abapOpenChecks](https://github.com/larshp/abapOpenChecks) -通过新的和可自定义的检查功能增强了SAP Code Inspector.

## Ada

* [Codepeer](http://www.adacore.com/codepeer) -检测运行时和逻辑错误
* [Polyspace for Ada](https://www.mathworks.com/products/polyspace-ada.html) ：copyright：-提供代码验证，以证明源代码中不存在溢出，零除，越界数组访问以及某些其他运行时错误.
* [SPARK](http://www.spark-2014.org/about) ：copyright：-Ada的静态分析和形式验证工具集
* [Understand](https://scitools.com/ada-programming-essential/) ：copyright：-IDE为Ada和VHDL提供代码分析，标准测试，指标，图形，依赖性分析等.

## Awk

* [gawk --lint](https://www.gnu.org/software/gawk/manual/html_node/Options.html) -警告关于可疑或不可移植到其他awk实现的构造.

## C/C++

* [Astrée](https://www.absint.com/astree/index.htm) ：copyright：-基于C / C ++抽象解释的声音静态分析器，可检测内存，类型和并发缺陷以及MISRA违规.
* [CBMC](http://www.cprover.org/cbmc/) -用于C程序，用户定义的断言，标准断言，若干覆盖率度量分析的有界模型检查器
* [clang-tidy](http://clang.llvm.org/extra/clang-tidy/) -lang静态分析
* [CMetrics](https://github.com/MetricsGrimoire/CMetrics) -测量C文件的大小和复杂性
* [Codecheker](https://github.com/Ericsson/codechecker) -使用Web GUI对C / C ++代码进行静态分析
* [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) ：copyright：-高级，整个程序，深层路径，对C和C ++的静态分析以及易于理解的说明以及代码和路径可视化.
* [Corrode](https://github.com/jameysharp/corrode)  -从C到Rust的半自动翻译.  通过显示Rust编译器警告和错误，可以揭示原始实现中的错误.
* [cppcheck](https://github.com/danmar/cppcheck) -C / C ++代码的静态分析
* [CppDepend](https://www.cppdepend.com) ：warning：：copyright：-测量，查询和可视化您的代码，避免意外的问题，技术负担和复杂性.
* [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) -遵循Google风格指南的自动C ++检查器
* [cqmetrics](https://github.com/dspinellis/cqmetrics) -C代码的质量指标
* [CScout](https://www.spinellis.gr/cscout/) -C和C预处理程序代码的复杂度和质量指标
* [flawfinder](http://www.dwheeler.com/flawfinder/) -发现可能的安全漏洞
* [flint++](https://github.com/JossWhittle/FlintPlusPlus) -flint的跨平台，零依赖端口，这是Facebook开发和使用的用于C ++的lint程序.
* [Frama-C](http://frama-c.com/) -完善的C代码静态分析器
* [Helix QAC](https://www.perforce.com/products/helix-qac)  ：copyright：-嵌入式软件的企业级静态分析.  支持MISRA，CERT和AUTOSAR编码标准.
* [IKOS](https://github.com/nasa-sw-vnv/ikos) -基于LLVM的C / C ++代码的声音静态分析器
* [include-gardener](https://github.com/feddischson/include_gardener) - a multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
* [LDRA](https://ldra.com/) ：copyright：-一个工具套件，包括对各种标准的静态分析（TBVISION），包括MISRA C＆C ++，JSF ++ AV，CWE，CERT C，CERT C ++和自定义规则.
* [oclint](http://oclint.org/) -C / C ++代码的静态分析
* [Phasar](https://github.com/secure-software-engineering/phasar) -基于LLVM的静态分析框架，带有污点和类型状态分析.
* [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) ：copyright：-识别C和C ++嵌入式软件中的运行时错误，并发问题，安全漏洞和其他缺陷.
* [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) ：copyright：-提供代码验证，以证明C和C ++源代码中不存在溢出，零除，越界数组访问以及某些其他运行时错误.
* [scan-build](https://clang-analyzer.llvm.org/scan-build.html) -在编译时使用LLVM分析C / C ++代码
* [splint](https://github.com/ravenexp/splint) -注释辅助的静态程序检查器
* [SVF](https://github.com/SVF-tools/SVF) -静态工具，可对C和C ++程序进行可伸缩且精确的过程间相关性分析.
* [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) -Vera ++是用于验证，分析和转换C ++源代码的可编程工具.

## C# #

* [.NET Analyzers](https://github.com/DotNetAnalyzers) -使用.NET编译器平台开发分析器（诊断和代码修复）的组织.
* [Code Analysis Rule Collection](https://carc.codeplex.com/) -包含在Microsoft .NET编译器平台“ Roslyn”上构建的一组诊断程序，代码修复程序和重构程序.
* [code-cracker](https://github.com/code-cracker/code-cracker) - An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.
* [CodeRush](https://www.devexpress.com/products/coderush/) ：copyright：-使用Visual Studio 2015及更高版本中的Roslyn引擎的代码创建，调试，导航，重构，分析和可视化工具.
* [CSharpEssentials](https://github.com/DustinCampbell/CSharpEssentials) - C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features.
* [Designite](http://www.designite-tools.com) ：copyright：-Designite支持各种体系结构，设计和实现气味的检测，各种代码质量指标的计算以及趋势分析.
* [Gendarme](http://www.mono-project.com/docs/tools+libraries/tools/gendarme/) -Gendarme检查包含ECMA CIL格式（Mono和.NET）代码的程序和库.
* [NDepend](http://www.ndepend.com/) ：copyright：-测量，查询和可视化您的代码，避免意外问题，技术负担和复杂性.
* [Puma Scan](https://github.com/pumasecurity/puma-scan) -开发团队在Visual Studio中编写代码时，Puma Scan提供了针对常见漏洞（XSS，SQLi，CSRF，LDAPi，加密，反序列化等）的实时安全代码分析.
* [Refactoring Essentials](http://vsrefactoringessentials.com/) - The free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers.
* [ReSharper](https://www.jetbrains.com/resharper/) :copyright: - Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies.
* [Roslyn Analyzers](https://github.com/dotnet/roslyn-analyzers) -基于Roslyn的FxCop分析仪实施.
* [Roslyn Security Guard](https://dotnet-security-guard.github.io/) -该项目侧重于识别潜在漏洞，例如SQL注入，跨站点脚本（XSS），CSRF，加密漏洞，硬编码密码等.
* [Roslynator](https://github.com/JosefPihrt/Roslynator/) - A collection of 190+ analyzers and 190+ refactorings for C#, powered by Roslyn.
* [Security Code Scan](https://security-code-scan.github.io/) - Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
* [SonarLint for Visual Studio](https://vs.sonarlint.org/) -SonarLint是Visual Studio 2015和2017的扩展，可为开发人员提供即时反馈，以反馈有关.NET代码中注入的新错误和质量问题.
* [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) -基于Roslyn并与VS集成的静态分析器集合.
* [Wintellect.Analyzers](https://github.com/Wintellect/Wintellect.Analyzers) -.NET编译器平台（“ Roslyn”）诊断分析器和代码修复.

## Crystal

* [ameba](https://github.com/veelenga/ameba) -用于Crystal的静态代码分析工具
* [crystal](https://crystal-lang.org/) -Crystal编译器具有内置的棉绒功能.

## Delphi

* [Fix Insight](https://www.tmssoftware.com/site/fixinsight.asp)  ：copyright：-一个免费的IDE插件，用于静态代码分析.  * Pro *版本包含用于自动化目的的命令行工具.
* [Pascal Analyzer](https://peganza.com/products_pal.html)  ：copyright：-具有大量报告的静态代码分析工具.  提供免费的* Lite *版本，报告数量有限.
* [Pascal Expert](https://peganza.com/products_pex.html)  ：copyright：-用于代码分析的IDE插件.  包括Pascal Analyzer报告功能的一部分，并且可用于Delphi 2007及更高版本.

## Dlang

* [D-scanner](https://github.com/dlang-community/D-Scanner) -D-Scanner是用于分析D源代码的工具

## Elixir

* [credo](https://github.com/rrrene/credo) -静态代码分析工具，专注于代码一致性和教学.
* [sobelow](https://github.com/nccgroup/sobelow) -Phoenix框架的安全性静态分析

## Elm

* [elm-analyse](https://stil4m.github.io/elm-analyse/) -一种工具，可让您分析Elm代码，识别缺陷并应用最佳实践.

## Erlang

* [elvis](https://github.com/inaka/elvis) -Erlang Style Reviewer
* [Primitive Erlang Security Tool (PEST)](https://github.com/okeuday/pest) -一种对Erlang源代码进行基本扫描并报告可能导致Erlang源代码不安全的函数调用的工具.

## F# #

* [FSharpLint](https://github.com/fsprojects/FSharpLint) -F的皮棉工具#

## Fortran

* [i-Code CNES for Fortran](https://github.com/lequal/i-CodeCNES) -用于Fortran 77，Fortran 90和Shell的开源静态代码分析工具.

## Go

* [aligncheck](https://gitlab.com/opennota/check) -查找效率低下的打包结构.
* [bodyclose](https://github.com/timakin/bodyclose) -检查HTTP响应主体是否关闭.
* [deadcode](https://github.com/tsenart/deadcode) -查找未使用的代码.
* [dingo-hunter](https://github.com/nickng/dingo-hunter) -用于在Go中查找死锁的静态分析器.
* [dogsled](https://github.com/alexkohler/dogsled) -查找带有太多空白标识符的分配/声明.
* [dupl](https://github.com/mibk/dupl) -报告可能重复的代码.
* [errcheck](https://github.com/kisielk/errcheck) -检查是否使用错误返回值.
* [flen](https://github.com/lafolle/flen) -在Go软件包中获取有关函数长度的信息.
* [gas](https://github.com/GoASTScanner/gas) -通过扫描Go AST检查源代码是否存在安全问题.
* [Go Meta Linter](https://github.com/alecthomas/gometalinter)  ：warning：-同时运行Go lint工具并标准化其输出.  将`golangci-lint`用于新项目.
* [go tool vet --shadow](https://golang.org/cmd/vet/#hdr-Shadowed_variables) -报告可能被意外遮盖的变量.
* [go vet](https://golang.org/cmd/vet/) -检查Go源代码并报告可疑.
* [go-consistent](https://github.com/Quasilyte/go-consistent) -分析器，可帮助您使Go程序更加一致.
* [go-critic](https://github.com/go-critic/go-critic) -保留检查当前未在其他linter中实现的检查的源代码linter.
* [go/ast](https://golang.org/pkg/go/ast/) -包ast声明用于表示Go包的语法树的类型.
* [gochecknoglobals](https://github.com/leighmcculloch/gochecknoglobals) -检查是否没有全局变量.
* [goconst](https://github.com/jgautheron/goconst) -查找可以被常量替换的重复字符串.
* [gocyclo](https://github.com/fzipp/gocyclo) -计算Go源代码中函数的圈复杂度.
* [gofmt -s](https://golang.org/cmd/gofmt/) -检查代码格式是否正确，是否无法进一步简化.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) -检查丢失或未引用的程序包导入.
* [GolangCI-Lint](https://github.com/golangci/golangci-lint) -替代“ Go Meta Linter”：GolangCI-Lint是一个Linters聚合器.
* [golint](https://github.com/golang/lint) - Prints out coding style mistakes in Go source code.
* [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) -同时运行许多linter，并将其输出标准化为报告.
* [goroutine-inspect](https://github.com/linuxerwang/goroutine-inspect) -分析Golang goroutine转储的交互式工具.
* [gosec (gas)](https://github.com/GoASTScanner/gas) -通过扫描Go AST检查源代码是否存在安全问题.
* [gosimple](https://godoc.org/github.com/surullabs/lint/gosimple) -简化代码.
* [gotype](https://golang.org/x/tools/cmd/gotype) -类似于Go编译器的语法和语义分析.
* [ineffassign](https://github.com/gordonklaus/ineffassign) -在Go代码中检测无效的分配
* [interfacer](https://github.com/mvdan/interfacer) -建议使用较窄的接口.
* [lll](https://github.com/walle/lll) -报告长行.
* [maligned](https://github.com/mdempsky/maligned) -检测对字段进行排序会占用较少内存的结构.
* [misspell](https://github.com/client9/misspell) -查找通常拼写错误的英语单词.
* [nakedret](https://github.com/alexkohler/nakedret) -寻找赤裸裸的回报.
* [nargs](https://github.com/alexkohler/nargs) -在函数声明中查找未使用的参数.
* [prealloc](https://github.com/alexkohler/prealloc) -查找可能预先分配的切片声明.
* [revive](https://github.com/mgechev/revive) - Fast, configurable, extensible, flexible, and beautiful linter for Go. Drop-in replacement of golint.
* [safesql](https://github.com/stripe/safesql) -用于Golang的静态分析工具，可防止SQL注入.
* [staticcheck](https://staticcheck.io/) - A suite of static analysis tools for Go, similar to ReSharper for C#. It specialises on bug finding, code simplicity, performance and editor integration.
* [structcheck](https://gitlab.com/opennota/check) -查找未使用的结构字段.
* [test](http://golang.org/pkg/testing/) -从stdlib测试模块显示测试失败的位置.
* [unconvert](https://github.com/mdempsky/unconvert) -检测冗余类型转换.
* [unimport](https://github.com/alexkohler/unimport) -查找不必要的导入别名
* [unparam](https://github.com/mvdan/unparam) -查找未使用的功能参数.
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) -查找未使用的变量.
* [varcheck](https://gitlab.com/opennota/check) -查找未使用的全局变量和常量.
* [wsl](https://github.com/bombsimon/wsl) -在正确的地方插入空行.

## Groovy

* [CodeNarc](https://github.com/CodeNarc/CodeNarc) -用于Groovy源代码的静态分析工具，可以监视和执行许多编码标准和最佳实践

## Haskell

* [HLint](https://github.com/ndmitchell/hlint) -HLint是用于建议对Haskell代码进行可能的改进的工具.
* [Weeder](https://github.com/ndmitchell/weeder) -使用Haskell代码检测无效出口或包裹进口的工具.

## Haxe

* [Haxe Checkstyle](https://github.com/HaxeCheckstyle/haxe-checkstyle) -静态分析工具，可帮助开发人员编写符合编码标准的Haxe代码.

## Java
* [Checker Framework](https://github.com/typetools/checker-framework/) -Java的可插拔类型检查http://checkerframework.org/
* [checkstyle](https://github.com/checkstyle/checkstyle) -检查Java源代码是否符合代码标准或一组验证规则（最佳做法）
* [ck](https://github.com/mauricioaniche/ck) -通过处理源Java文件来计算Chidamber和Kemerer面向对象的指标
* [ckjm](http://www.spinellis.gr/sw/ckjm/) -通过处理已编译的Java文件的字节码来计算Chidamber和Kemerer的面向对象的指标
* [CogniCrypt](https://www.eclipse.org/cognicrypt/) -检查Java源代码和字节码是否正确使用了加密API
* [DesigniteJava](http://www.designite-tools.com/designitejava) ：copyright：-DesigniteJava支持各种体系结构，设计和实现气味的检测以及各种代码质量指标的计算.
* [Error-prone](https://github.com/google/error-prone) -捕获常见的Java错误作为编译时错误
* [fb-contrib](https://github.com/mebigfatguy/fb-contrib) -具有附加错误检测器的FindBugs插件
* [Find Security Bugs](https://find-sec-bugs.github.io/) -IDE / SonarQube插件，用于Java Web应用程序的安全审核.
* [forbidden-apis](https://github.com/policeman-tools/forbidden-apis)  -检测并禁止调用特定的方法/类/字段（例如从没有字符集的文本流中读取）.  Maven / Gradle / Ant兼容.
* [google-java-format](https://github.com/google/google-java-format) -Google样式重新格式化
* [Hopper](https://github.com/cuplv/hopper) -用scala编写的针对JVM上运行的语言的静态分析工具
* [HuntBugs](https://github.com/amaembo/huntbugs) -基于Procyon编译器工具的字节码静态分析器工具，旨在取代FindBugs.
* [JArchitect](https://www.jarchitect.com) ：copyright：-测量，查询和可视化您的代码，避免意外问题，技术负担和复杂性.
* [JBMC](http://www.cprover.org/jbmc/) -Java的有限模型检查器（字节码），验证用户定义的断言，标准断言，若干覆盖率度量分析
* [NullAway](https://github.com/uber/NullAway)  -基于类型的空指针检查器，具有较低的构建时间开销；  一个 [Error Prone](http://errorprone.info/) 插入
* [OWASP Dependency Check](https://www.owasp.org/index.php/OWASP_Dependency_Check) -检查依赖项是否存在已知的，公开披露的漏洞.
* [qulice](https://www.qulice.com/) -结合了一些（预配置）静态分析工具（checkstyle，PMD，Findbugs等）.
* [Soot](https://sable.github.io/soot/) -用于分析和转换Java和Android应用程序的框架.
* [Spoon](https://github.com/INRIA/spoon)  -为Java编写自己的静态分析和体系结构规则检查器的库.  可以集成在Maven和Gradle中.
* [SpotBugs](https://spotbugs.github.io/)  -SpotBugs是FindBugs的继任者.  静态分析工具，用于查找Java代码中的错误.
* [Xanitizer](https://xanitizer.com/) -Xanitizer在Java / Scala Web应用程序中发现安全漏洞.

## JavaScript

* [aether](https://github.com/codecombat/aether) -在节点或浏览器中衬入，分析，规范化，转换，沙盒，运行，逐步浏览和可视化用户JavaScript.
* [Closure Compiler](https://github.com/google/closure-compiler) -一种编译器工具，可提高效率，减小大小并在JavaScript文件中提供代码警告.
* [ClosureLinter](https://github.com/google/closure-linter)  ：warning：-确保您所有项目的JavaScript代码均遵循Google JavaScript样式指南中的指南.  它还可以自动修复许多常见错误
* [coffeelint](https://github.com/clutchski/coffeelint) -样式检查器，可帮助确保CoffeeScript代码保持干净和一致.
* [complexity-report](https://github.com/jared-stilwell/complexity-report) ：警告：-JavaScript项目的软件复杂性分析
* [DeepScan](https://deepscan.io) ：copyright：-一个JavaScript分析器，它针对运行时错误和质量问题，而不是编码约定.
* [escomplex](https://github.com/jared-stilwell/escomplex) -JavaScript系列抽象语法树的软件复杂性分析.
* [eslint](https://github.com/eslint/eslint) -完全可插拔的工具，用于识别和报告JavaScript模式
* [Esprima](https://github.com/jquery/esprima) -用于多用途分析的ECMAScript解析基础结构
* [flow](https://flow.org/) -JavaScript的静态类型检查器.
* [jshint](https://github.com/jshint/jshint) ：warning：-检测JavaScript代码中的错误和潜在问题，并执行团队的编码约定
* [JSLint](https://github.com/douglascrockford/JSLint) ：警告：-JavaScript代码质量工具
* [JSPrime](https://github.com/dpnishant/jsprime) -静态安全分析工具
* [NodeJSScan](https://github.com/ajinabraham/NodeJsScan) -NodeJsScan是用于Node.js应用程序的静态安全代码扫描程序.
* [plato](https://github.com/es-analysis/plato) -可视化JavaScript源复杂度
* [Prettier](https://github.com/prettier/prettier) -固执己见的代码格式化程序.
* [quality](https://github.com/jden/quality) -零配置代码和模块棉绒
* [retire.js](https://github.com/RetireJS/retire.js) -扫描程序检测已知漏洞的JavaScript库的使用
* [standard](http://standardjs.com/) -一个npm模块，用于检查Javascript Styleguide问题
* [tern](https://github.com/ternjs/tern) -JavaScript代码分析器，可提供深入的跨编辑器语言支持
* [xo](https://github.com/xojs/xo)  -固执己见，但可配置的ESLint包装器，其中包含许多好东西.  强制执行严格且易读的代码.
* [yardstick](https://github.com/calmh/yardstick) ：警告：-Javascript代码指标

## Kotlin

* [detekt](https://github.com/arturbosch/detekt) -Kotlin代码的静态代码分析.
* [ktlint](https://github.com/shyiko/ktlint) -带有内置格式化程序的防骑自行车科特林短绒

## Lua

* [luacheck](https://github.com/mpeterv/luacheck) - A tool for linting and static analysis of Lua code.

## MATLAB

* [mlint](https://de.mathworks.com/help/matlab/ref/mlint.html) ：copyright：-检查MATLAB代码文件是否存在问题.

## Perl

* [Perl::Critic](https://metacpan.org/pod/Perl::Critic) -Critique Perl最佳实践的源代码.

## PHP

* [dephpend](https://github.com/mihaeu/dephpend) -依赖性分析工具
* [deprecation-detector](https://github.com/sensiolabs-de/deprecation-detector) -查找不推荐使用的（Symfony）代码的用法
* [deptrac](https://github.com/sensiolabs-de/deptrac) -实施有关软件层之间依赖性的规则.
* [DesignPatternDetector](https://github.com/Halleck45/DesignPatternDetector) -检测PHP代码中的设计模式
* [EasyCodingSt和ard](https://github.com/Symplify/EasyCodingSt和ard) -结合 [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 和 [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
* [exakat](https://github.com/exakat/exakat) -用于PHP的自动代码审查引擎
* [GrumPHP](https://github.com/phpro/grumphp) -每次提交时检查代码
* [Mondrian](https://github.com/Trismegiste/Mondrian) -使用图论的一组静态分析和重构工具
* [parallel-lint](https://github.com/JakubOnderka/PHP-Parallel-Lint) -该工具检查PHP文件的语法的速度比带有高级输出的串行检查速度快.
* [Parse](https://github.com/psecio/parse) -静态安全扫描仪
* [pdepend](https://pdepend.org/) -计算软件度量，例如PHP代码的圈复杂度.
* [phan](https://github.com/etsy/phan) -etsy的现代静电分析仪
* [PHP Architecture Tester](https://github.com/carlosas/phpat) -易于使用的PHP体系结构测试工具.
* [PHP Assumptions](https://github.com/rskuipers/php-assumptions) -检查弱假设
* [PHP Coding Standards Fixer](http://cs.sensiolabs.org/) -根据PSR-1，PSR-2和Symfony标准等标准修复代码.
* [Php Inspections (EA Extended)](https://github.com/kalessil/phpinspectionsea) -用于PHP的静态代码分析器.
* [PHP Refactoring Browser](https://github.com/QafooLabs/php-refactoring-browser) -重构助手
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) -根据语义版本建议下一个版本
* [PHP-Parser](https://github.com/nikic/PHP-Parser) -用PHP编写的PHP解析器
* [PHP-Token-Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) -库模拟PHP内部反射
* [php7cc](https://github.com/sstalle/php7cc) -PHP 7兼容性检查器
* [php7mar](https://github.com/Alexia/php7mar) -协助开发人员将其代码快速移植到PHP 7
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) -检测违反已定义的一组编码标准
* [phpca](https://github.com/wapmorgan/PhpCodeAnalyzer) -查找非内置扩展名的用法
* [phpcf](http://wapmorgan.github.io/PhpCodeFixer/) -查找不推荐使用的PHP功能的用法
* [phpcpd](https://github.com/sebastianbergmann/phpcpd) -用于PHP代码的复制/粘贴检测器.
* [phpdcd](https://github.com/sebastianbergmann/phpdcd) -PHP代码的死代码检测器（DCD）.
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) -为项目建立依赖图
* [phpdoc-to-typehint](https://github.com/dunglas/phpdoc-to-typehint) -使用PHPDoc批注添加标量类型提示并向现有的PHP项目返回类型
* [phpDocumentor](https://www.phpdoc.org/) -分析PHP源代码以生成文档
* [PHPMD](https://phpmd.org/) -在代码中找到可能的错误
* [PhpMetrics](http://www.phpmetrics.org/) -计算和可视化各种代码质量指标
* [phpmnd](https://github.com/povils/phpmnd) -有助于检测魔术数字
* [PHPQA](https://github.com/EdgedesignCZ/phpqa) -用于运行质量检查工具的工具（phploc，phpcpd，phpcs，pdepend，phpmd，phpmetrics）
* [phpqa - jakzal](https://github.com/jakzal/phpqa) -在一个容器中有许多用于PHP静态分析的工具
* [phpqa - jmolivas](https://github.com/jmolivas/phpqa) -PHPQA多合一分析器CLI工具
* [phpsa](https://github.com/ovr/phpsa) -用于PHP的静态分析工具.
* [PHPStan](https://github.com/phpstan/phpstan) -PHP静态分析工具-无需运行即可发现代码中的错误！
* [Progpilot](https://github.com/designsecurity/progpilot) -出于安全目的的静态分析工具
* [Psalm](https://getpsalm.org/) -用于在PHP应用程序中查找类型错误的静态分析工具
* [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) -可视化指标和源代码
* [RIPS](https://www.ripstech.com/) ：copyright：-静态源代码分析器，用于PHP脚本中的漏洞
* [Tuli](https://github.com/ircmaxell/Tuli) -静态分析引擎
* [twig-lint](https://github.com/asm89/twig-lint) -twig-lint是用于您的twig文件的皮棉工具.
* [WAP](https://www.owasp.org/index.php/OWASP_WAP-Web_Application_Protection) -用于检测和纠正PHP（4.0或更高版本）Web应用程序中的输入验证漏洞的工具，并通过结合静态分析和数据挖掘来预测误报.

## Python

* [bandit](https://github.com/PyCQA/bandit) -在Python代码中查找常见安全问题的工具
* [bellybutton](https://github.com/hchasestevens/bellybutton) -支持自定义项目特定规则的整理引擎
* [Black](https://github.com/ambv/black) -毫不妥协的Python代码格式化程序
* [cohesion](https://github.com/mschwager/cohesion) -用于测量Python类内聚力的工具
* [Dlint](https://github.com/dlint-py/dlint) -确保Python代码安全的工具
* [include-gardener](https://github.com/feddischson/include_gardener) - a multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
* [jedi](https://github.com/davidhalter/jedi) -适用于Python的自动完成/静态分析库
* [linty fresh](https://github.com/lyft/linty_fresh) -解析皮棉错误并将其作为请求请求的注释报告给Github
* [mccabe](https://github.com/PyCQA/mccabe) -检查McCabe的复杂性
* [mypy](https://github.com/python/mypy) -静态类型检查器，旨在结合经常使用的鸭子类型和静态类型的优点 [MonkeyType](https://github.com/Instagram/MonkeyType)
* [py-find-injection](https://github.com/uber/py-find-injection) -在Python代码中查找SQL注入漏洞
* [pycodestyle](https://github.com/PyCQA/pycodestyle) -（以前是`pep8`）根据PEP 8中的某些样式约定检查Python代码
* [pydocstyle](https://github.com/PyCQA/pydocstyle) -检查是否符合Python文档字符串约定
* [pyflakes](https://github.com/pyflakes/pyflakes/) -检查Python源文件是否有错误
* [pylint](https://github.com/PyCQA/pylint)  -查找编程错误，帮助实施编码标准并嗅探某些代码气味.  它还包括“ pyreverse”（UML图生成器）和“ symilar”（相似性检查器）.
* [pyre-check](https://github.com/facebook/pyre-check) -适用于大型Python代码库的快速，可扩展的类型检查器
* [pyright](https://github.com/Microsoft/pyright) -用于Python的静态类型检查器，用于解决mypy等现有工具中的空白.
* [pyroma](https://github.com/regebro/pyroma) - rate how well a Python project complies with the best practices of the Python packaging ecosystem, and list issues that could be improved
* [PyT - Python Taint](https://github.com/python-security/pyt) -用于检测Python Web应用程序中的安全漏洞的静态分析工具.
* [pytype](https://github.com/google/pytype) -用于Python代码的静态类型分析器.
* [radon](https://github.com/rubik/radon) -一个Python工具，可从源代码计算各种指标
* [vulture](https://github.com/jendrikseipp/vulture) -在Python代码中找到未使用的类，函数和变量
* [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) -有史以来最严格，最有主见的python linter
* [wily](https://github.com/tonybaloney/wily) -用于归档，探索和绘制Python源代码复杂性的命令行工具
* [xenon](https://github.com/rubik/xenon) -使用以下命令监视代码复杂性 [`radon`](https://github.com/rubik/radon)

## Python wrappers

* [ciocheck](https://github.com/ContinuumIO/ciocheck)  -lint，格式化程序和测试套件帮助器.  作为短绒棉，它是包裹在“ pep8”，“ pydocstyle”，“ flake8”和“ pylint”周围的包装纸.
* [flake8](https://github.com/PyCQA/flake8) -围绕pyflakes，pycodestyle和mccabe的包装器
* [multilint](https://github.com/adamchainz/multilint) -围绕“ flake8”，“ isort”和“ modernize”的包装器
* [prospector](https://github.com/PyCQA/prospector) -在`pylint`，`pep8`，`mccabe`等周围包装

## R

* [cyclocomp](https://github.com/MangoTheCat/cyclocomp) -量化R函数/表达式的圈复杂度.
* [goodpractice](http://mangothecat.github.io/goodpractice/) -分析R软件包的源代码并提供最佳实践建议.
* [lintr](https://github.com/jimhester/lintr) -R的静态代码分析.
* [styler](https://styler.r-lib.org/) -R源代码文件的格式和R代码的漂亮打印.

## RPG

* [SourceMeter](https://www.sourcemeter.com/resources/rpg/) ：copyright：-RPG III和RPG IV版本的静态代码分析（包括自由格式）

## Ruby

* [brakeman](https://github.com/presidentbeef/brakeman) -用于Ruby on Rails应用程序的静态分析安全漏洞扫描程序
* [cane](https://github.com/square/cane) -代码质量阈值检查作为构建的一部分
* [dawnscanner](https://github.com/thesp0nge/dawnscanner)  -用于ruby编写的Web应用程序的静态分析安全扫描程序.  它支持Sinatra，Padrino和Ruby on Rails框架.
* [flay](https://github.com/seattlerb/flay) -Flay分析代码的结构相似性.
* [flog](https://github.com/seattlerb/flog)  -Flog在易于阅读的疼痛报告中报告了遭受最多折磨的代码.  分数越高，代码所处的痛苦就越大.
* [include-gardener](https://github.com/feddischson/include_gardener) - a multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
* [laser](https://github.com/michaeledgar/laser) -Ruby代码的静态分析和样式查询.
* [pelusa](https://github.com/codegram/pelusa) -静态分析Lint型工具，可改善您的OO Ruby代码
* [quality](https://github.com/apiology/quality) -使用社区工具对代码进行质量检查，并确保您的代码不会随着时间的推移而恶化.
* [Querly](https://github.com/soutaro/querly) -基于模式的Ruby检查工具
* [Railroader](https://railroader.org/) -针对Ruby on Rails应用程序的开源静态分析安全漏洞扫描程序.
* [reek](https://github.com/troessner/reek) -Ruby代码气味检测器
* [RuboCop](https://github.com/rubocop-hq/rubocop) -基于社区Ruby样式指南的Ruby静态代码分析器.
* [Rubrowser](https://github.com/blazeeboy/rubrowser) -Ruby类交互式依赖图生成器.
* [ruby-lint](https://github.com/YorickPeterse/ruby-lint) -Ruby的静态代码分析
* [rubycritic](https://github.com/whitesmith/rubycritic) -Ruby代码质量报告程序
* [SandiMeter](https://github.com/makaroni4/sandi_meter) -用于检查Ruby代码中Sandi Metz规则的静态分析工具.
* [Sorbet](https://github.com/sorbet/sorbet) -专为Ruby设计的快速，强大的类型检查器

## Rust

* [cargo-audit](https://github.com/RustSec/cargo-audit) -审核Cargo.lock，以将带有安全漏洞的板条箱报告给 [RustSec Advisory Database](https://github.com/RustSec/advisory-db/).
* [cargo-inspect](https://github.com/mre/cargo-inspect) -在没有语法糖的情况下检查Rust代码，以了解编译器的幕后工作.
* [clippy](https://github.com/Manishearth/rust-clippy) -防止常见错误并改进Rust代码的代码仓库
* [electrolysis](https://github.com/Kha/electrolysis) -通过在精益定理证明者中将其转换为定义来正式验证Rust程序的工具.
* [herbie](https://github.com/mcarton/rust-herbie-lint) -在使用数值不稳定的浮点表达式时，在包装箱中添加警告或错误.
* [linter-rust](https://github.com/AtomLinter/linter-rust) -使用Rustc和货物在Atom中整理您的Rust文件
* [MIRAI](https://github.com/facebookexperimental/MIRAI) -使用Rust的中级中间语言操作的抽象解释器，并基于污点分析提供警告.
* [Rust Language Server](https://github.com/rust-lang-nursery/rls) -支持诸如“转到定义”，符号搜索，重新格式化和代码完成之类的功能，并支持重命名和重构.
* [rustfix](https://github.com/killercup/rustfix) -阅读并应用rustc（和第三方皮棉，如clippy所提供的皮棉）提出的建议.

## Scala

* [linter](https://github.com/HairyFotr/linter) -Linter是一个Scala静态分析编译器插件，它为各种可能的bug，效率低下和样式问题添加了编译时检查.
* [Scalastyle](http://www.scalastyle.org) -Scalastyle检查您的Scala代码并指出其潜在问题.
* [scapegoat](https://github.com/sksamuel/scapegoat) -用于静态代码分析的Scala编译器插件
* [WartRemover](https://github.com/puffnfresh/wartremover) -灵活的Scala代码整理工具.
* [Xanitizer](https://xanitizer.com/) -Xanitizer在Java / Scala Web应用程序中发现安全漏洞.

## Shell

* [i-Code CNES for Shell](https://github.com/lequal/i-CodeCNES) -用于Shell和Fortran（77和90）的开源静态代码分析工具.
* [shellcheck](https://github.com/koalaman/shellcheck) -ShellCheck，一种静态分析工具，可为bash / sh shell脚本提供警告和建议

## Solidity

* [slither](https://github.com/trailofbits/slither) -静态分析框架，该框架运行一套漏洞检测器，打印有关合同明细的可视信息，并提供可轻松编写自定义分析的API
* [solium](https://github.com/duaraghav8/Solium) -Solium是一台可以识别和修复Solidity智能合约中的样式和安全问题的工具

## SQL

* [sqlcheck](https://github.com/jarulraj/sqlcheck-old) -自动识别SQL查询中的反模式
* [sqlint](https://github.com/purcell/sqlint) -简单的SQL linter
* [tsqllint](https://github.com/tsqllint/tsqllint) -T-SQL专用的linter
* [TSqlRules](https://github.com/ashleyglee/TSqlRules) -SQL Server的TSQL静态代码分析规则

## Swift

* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) -用于重新格式化Swift代码的库和命令行格式化工具
* [SwiftLint](https://github.com/realm/SwiftLint) -实施Swift样式和约定的工具
* [Tailor](https://github.com/sleekbyte/tailor) ：warning：-用于以Apple的Swift编程语言编写的源代码的静态分析和棉绒工具.

## Tcl

* [Frink](https://catless.ncl.ac.uk/Programs/Frink/) -Tcl格式化和静态检查程序（可以美化该程序，将其最小化，混淆或仅对其进行完整性检查）.
* [Nagelfar](https://sourceforge.net/projects/nagelfar/) -Tcl的静态语法检查器
* [tclchecker](https://github.com/ActiveState/tdk/blob/master/docs/3.0/TDK_3.0_Checker.txt) -静态语法分析模块（作为 [TDK](https://github.com/ActiveState/tdk)).

## TypeScript

* [Codelyzer](https://github.com/mgechev/codelyzer) -一组tslint规则，用于Angular 2 TypeScript项目的静态代码分析.
* [ESLint](https://github.com/typescript-eslint/typescript-eslint) -TypeScript语言的可扩展linter.
* [tslint-clean-code](https://github.com/Glavin001/tslint-clean-code) -受《清洁法规》手册启发的一组TSLint规则.
* [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib) -一组由Microsoft维护的Typelin项目的静态代码分析的tslint规则.

## VBScript

* [Test Design Studio](http://patterson-consulting.net/tds) ：copyright：-具有静态代码分析功能的完整IDE，用于Micro Focus统一功能测试基于VBScript的自动化测试.

## Multiple languages

* [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) :copyright: - Static analysis for C/C++/C#, PHP and Java
* [ApplicationInspector](https://github.com/microsoft/ApplicationInspector) - creates reports of over 400 rule patterns for feature detection (e.g. the use of cryptography or version control in apps). Supports C/C++, C#, Java, JavaScript, HTML, Python, Objective-C, Go, Ruby, Powershell
* [Application Inspector](https://www.ptsecurity.com/ww-en/products/ai/) :copyright: - Commercial Static Code Analysis which generates exploits to verify vulnerabilities. Supports: Java (including JSP and JSF), C#, VB.Net, ASP.NET, Php, JavaScript, Objective-C, Swift, C\C++, SQL (PL/SQL. T-SQL. MySQL), HTML5
* [AppScan Source](https://www.hcltechsw.com/wps/portal/products/appscan/home) :copyright: - Commercial Static Code Analysis. Supports: Microsoft .NET Framework (C#, ASP.NET, VB.NET), ASP (JavaScript/VBScript), C/C++, COBOL, ColdFusion, JavaScript, JavaServer Pages (JSP), Java™ (including support for Android APIs), Perl, PHP, PL/SQL, T-SQL, Visual Basic 6
* [APPscreener](https://appscreener.us) :copyright: - Static code analysis for binary and source code - Java/Scala, PHP, Javascript, C#, PL/SQL, Python, T-SQL, C/C++, ObjectiveC/Swift, Visual Basic 6.0, Ruby, Delphi, ABAP, HTML5 and Solidity
* [ArchUnit](https://www.archunit.org/) -对Java或Kotlin架构进行单元测试
* [Axivion Bauhaus Suite](https://www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: - Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95
* [CAST Highlight](https://www.castsoftware.com/products/highlight) :copyright: - Commercial Static Code Analysis which runs locally, but uploads the results to its cloud for presentation. Supports: Java, JavaScript, Python, JSP, COBOL, SAP/Abap, C/C++, C#, PHP, Visual Basic, T-SQL, PL/SQL.
* [Checkmarx CxSAST](https://www.checkmarx.com/products/static-application-security-testing/) :copyright: - Commercial Static Code Analysis which doesn't require pre-compilation. Supports: Android (Java), Apex and VisualForce, ASP, C#, C/C++, Go, Groovy, HTML5, Java, JavaScript, Node.js, Objective C, Perl, PhoneGap, PHP, Python, Ruby, Scala, Swift, VB.NET, VB6, VBScript
* [ClassGraph](https://github.com/classgraph/classgraph)  -用于查询或可视化类元数据或类相关性的类路径和模块路径扫描器.  支持JVM语言.
* [coala](https://coala.io/) -用于创建代码分析的语言独立框架-支持 [over 60 languages](https://coala.io/languages) 默认情况下
* [Cobra](http://spinroot.com/cobra/)  ：copyright：-NASA喷气推进实验室的结构源代码分析器.  支持C，C ++，Ada和Python.
* [codeburner](https://github.com/groupon/codeburner) -提供统一的界面来对发现的问题进行排序并采取行动
* [CodeFactor](https://codefactor.io) :copyright: - Static Code Analysis for C#, C, C++, CoffeeScript, CSS, Groovy, GO, JAVA, JavaScript, Less, Python, Ruby, Scala, SCSS, TypeScript.
* [CodeIt.Right](https://submain.com/products/codeit.right.aspx) :copyright: - CodeIt.Right&trade; provides a fast, automated way to ensure that your source code adheres to (your) predefined design and style guidelines as well as best coding practices. Supported languages: C#, VB.NET.
* [CodeScene](https://empear.com/) ：copyright：-CodeScene优先考虑技术债务，查找社会模式并识别代码中的隐患.
* [cqc](https://github.com/xcatliu/cqc) -检查js，jsx，vue，css，less，scss，sass和styl文件的代码质量.
* [Coverity](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - Synopsys Coverity supports 20 languages and over 70 frameworks including Ruby on rails, Scala, PHP, Python, JavaScript, TypeScript, Java, Fortran, C, C++, C#, VB.NET.
* [DeepSource](https://deepsource.io/)  ：copyright：-深入的静态分析以监视源代码的质量和安全性.  支持Python和Go，并且可以在错误风险，安全性，反模式，性能，文档和样式等垂直方面检测600多种类型的问题.  与GitHub的本机集成.
* [Depends](https://github.com/multilang-depends/depends) -分析Java，C / C ++，Ruby的代码元素的全面依赖关系.
* [DevSkim](https://github.com/microsoft/devskim) - Regex-based static analysis tool for Visual Studio, VS Code, and Sublime Text - C/C++, C#, PHP, ASP, Python, Ruby, Java, and others.
* [Fortify](https://software.microfocus.com/en-us/products/static-code-analysis-sast/overview) :copyright: A commercial static analysis platform that supports the scanning of C/C++, C#, VB.NET, VB6, ABAP/BSP, ActionScript, Apex, ASP.NET, Classic ASP, VB Script, Cobol, ColdFusion, HTML, Java, JS, JSP, MXML/Flex, Objective-C, PHP, PL/SQL, T-SQL, Python (2.6, 2.7), Ruby (1.9.3), Swift, Scala, VB, and XML.
* [Goodcheck](https://github.com/sideci/goodcheck) -基于正则表达式的可定制棉短绒
* [graudit](https://github.com/wireghoul/graudit) - Grep rough audit - source code auditing tool - C/C++, PHP, ASP, C#, Java, Perl, Python, Ruby
* [Hound CI](https://houndci.com/)  -在GitHub拉取请求中评论样式违规.  支持Coffeescript，Go，HAML，JavaScript，Ruby，SCSS和Swift.
* [imhotep](https://github.com/justinabrahms/imhotep) - Comment on commits coming into your repository and check for syntactic errors and general lint warnings.
* [Infer](https://github.com/facebook/infer) -用于Java，C和Objective-C的静态分析器
* [Klocwork](http://www.klocwork.com/products-services/klocwork) ：copyright：-针对C / C ++，Java和C的质量和安全性静态分析#
* [Kiuwan](https://www.kiuwan.com/code-security-sast/) :copyright: - Identify and remediate cyber threats in a blazingly fast, collaborative environment, with seamless integration in your SDLC. Python, C\C++, Java, C#, PHP and more
* [oclint](https://github.com/oclint/oclint) -静态源代码分析工具，可提高C，C ++和Objective-C的质量并减少缺陷
* [pfff](https://github.com/facebook/pfff) -Facebook用于多种语言的代码分析，可视化或保留样式源转换的工具
* [PMD](https://pmd.github.io/) -Java，Javascript，PLSQL，XML，XSL等的源代码分析器
* [Pronto](https://github.com/prontolabs/pronto)  -快速自动代码审查您的更改.  支持40多种语言的跑步者，包括Clang，Elixir，JavaSCript，PHP，Ruby等
* [pre-commit](https://github.com/pre-commit/pre-commit) -用于管理和维护多语言预提交挂钩的框架.
* [PT.PM](https://github.com/PositiveTechnologies/PT.PM) - An engine for searching patterns in the source code, based on Unified AST or UST. At present time C#, Java, PHP, PL/SQL, T-SQL, and JavaScript are supported. Patterns can be described within the code or using a DSL.
* [PVS-Studio](https://www.viva64.com/en/pvs-studio/) ：版权：-a（[conditionally free](https://www.viva64.com/en/b/0614/) for FOSS and individual developers) static analysis of C, C++, C# and Java code. For advertising purposes [you can propose a large FOSS project for analysis by PVS employees](https://github.com/viva64/pvs-studio-check-list) .  支持CWE映射，MISRA和CERT编码标准.
* [Reviewdog](https://github.com/haya14busa/reviewdog) -一种在任何代码托管服务中发布来自任何linter的评论评论的工具.
* [Security Code Scan](https://security-code-scan.github.io/) - Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
* [Semmle QL and LGTM](https://semmle.com/)  ：copyright：-使用对源代码的查询来查找安全漏洞，变体和关键代码质量问题.  自动检查PR代码；  对于公共GitHub / Bitbucket回购免费： [LGTM.com](https://LGTM.com).
* [shipshape](https://github.com/google/shipshape) -静态程序分析平台，允许自定义分析仪通过通用接口插入
* [SonarQube](http://www.sonarqube.org/) -SonarQube是管理代码质量的开放平台.
* [STOKE](https://github.com/StanfordPL/stoke)  -用于x86_64指令集的编程语言不可知随机优化器.  它使用随机搜索来探索所有可能的程序转换的极高维空间
* [SmartDec Scanner](https://smartdecscanner.com/) :copyright: - SAST tool which is capable of identifying vulnerabilities and undocumented features. The analyzer scans the source code and executables without debug info (i.e. binaries). Supports: Java/Scala/Kotlin, PHP, C#, JavaScript, TypeScript, VBScript, HTML5, Python, Perl, C/C++, Objective-C/Swift, PL/SQL, T-SQL, ABAP, 1C, Apex, Go, Ruby, Groovy, Delphi, VBA, Visual Basic 6, Solidity, Vyper, COBOL.
* [Synopsys](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - A commercial static analysis platform that allows for scanning of multiple languages (C/C++, Android, C#, Java, JS, PHP, Python, Node.JS, Ruby, Fortran, and Swift)
* [TscanCode](https://github.com/Tencent/TscanCode) - A fast and accurate static analysis solution for C/C++, C#, Lua codes provided by Tencent. Using GPLv3 license.
* [Undebt](https://github.com/Yelp/undebt) -基于语言的工具，可基于简单的模式定义进行大规模，自动，可编程的重构
* [Veracode](http://www.veracode.com/products/static-analysis-sast/static-code-analysis)  ：copyright：-在不需要源代码的情况下查找二进制文件和字节码中的缺陷.  支持所有主要的编程语言：Java，.NET，JavaScript，Swift，Objective-C，C，C ++等.
* [WALA](http://wala.sourceforge.net/wiki/index.php/Main_Page) -Java字节码和相关语言以及JavaScript的静态分析功能
* [WhiteHat Application Security Platform](https://www.whitehatsec.com/products/static-application-security-testing/) :copyright: - WhiteHat Scout (for Developers) combined with WhiteHat Sentinel Source (for Operations) supporting WhiteHat Top 40 and OWASP Top 10. Language support for: Java, C#(.NET), ASP.NET, PHP, JavaScript, Node.js, Objective-C, Android, HTML5, TypeScript.
* [Wotan](https://github.com/fimbullinter/wotan) -可插拔的TypeScript和JavaScript linter
* [XCode](https://developer.apple.com/xcode/) ：copyright：-XCode为 [Clang's](http://clang-analyzer.llvm.org/xcode.html) 静态代码分析器（C / C ++，Obj-C）

## Other

## Build tools

* [checkmake](https://github.com/mrtazz/checkmake) -用于文件的分析器/分析器
* [codechecker](https://github.com/Ericsson/codechecker) -Clang静态分析器的缺陷数据库和查看器扩展

## Binaries

* [BinSkim](https://github.com/Microsoft/binskim) -二进制静态分析工具，可为Windows可移植可执行文件提供安全性和正确性结果.
* [cwe_checker](https://github.com/fkie-cad/cwe_checker) -cwe_checker在二进制可执行文件中找到易受攻击的模式.
* [Jakstab](https://github.com/jkinder/jakstab) -Jakstab是基于抽象解释的集成反汇编和静态分析框架，用于设计可执行文件的分析并恢复可靠的控制流程图.
* [Twiggy](https://github.com/rustwasm/twiggy)  -分析二进制文件的调用图以分析代码大小.  目标是减少二进制文件.


## Containers

* [anchore](https://anchore.io/) -发现，分析和验证容器映像
* [clair](https://github.com/coreos/clair) -容器的漏洞静态分析
* [collector](https://github.com/banyanops/collector) -在容器内运行任意脚本，并收集有用的信息
* [dagda](https://github.com/eliasgranderubio/dagda) -对Docker映像/容器中的已知漏洞执行静态分析.
* [Docker Label Inspector](https://github.com/garethr/docker-label-inspector) -整理和验证Dockerfile标签
* [Haskell Dockerfile Linter](https://github.com/lukasmartinelli/hadolint) -更智能的Dockerfile Linter，可帮助您构建最佳实践Docker映像
* [kube-score](https://github.com/zegl/kube-score) -Kubernetes对象定义的静态代码分析.


## Config Files

* [dotenv-linter](https://github.com/wemake-services/dotenv-linter) -像魅力一样整理dotenv文件.
* [gixy](https://github.com/yandex/gixy)  -分析Nginx配置的工具.  主要目标是防止配置错误并自动进行缺陷检测.

## Configuration Management

* [ansible-lint](https://github.com/willthames/ansible-lint) -检查剧本中可能会改善的做法和行为
* [cfn-lint](https://github.com/awslabs/cfn-python-lint) -AWS Labs CloudFormation linter.
* [cfn_nag](https://github.com/stelligent/cfn_nag) -适用于AWS CloudFormation模板的模板.
* [checkov](https://github.com/bridgecrewio/checkov/) -用于Terraform文件的静态分析工具（tf&gt; = v0.12），可防止在构建时云配置错误.
* [cookstyle](https://docs.chef.io/cookstyle.html) -Cookstyle是基于RuboCop Ruby linting工具的厨师工具整理工具
* [foodcritic](http://www.foodcritic.io/) -检查主厨食谱中常见问题的皮棉工具.
* [Puppet Lint](https://github.com/rodjek/puppet-lint) -检查您的人偶清单是否符合样式指南.
* [terraform-compliance](https://terraform-compliance.com) -针对Terraform的轻量级，专注于合规性和安全性的BDD测试框架.
* [terrascan](https://github.com/cesar-rodriguez/terrascan) -收集用于Terraform模板的静态代码分析的安全性和最佳实践测试.
* [tflint](https://github.com/wata727/tflint) -一种Terraform linter，用于检测“ terraform plan”无法检测到的错误.


## CSS

* [CSS Stats](https://github.com/cssstats/cssstats) -样式表上可能有趣的统计信息
* [CSScomb](https://github.com/csscomb/csscomb.js)  -CSS的编码样式格式化程序.  支持自己的配置，使样式表美观且一致
* [CSSLint](https://github.com/CSSLint/csslint) -是否进行基本语法检查并发现有问题的模式或效率低下的迹象
* [GraphMyCSS.com](https://graphmycss.com) -CSS特异性图生成器
* [Parker](https://github.com/katiefenn/parker) -样式表分析工具
* [Project Wallace CSS Analyzer](https://github.com/projectwallace/css-analyzer) -CSS的分析工具，属于 [Project Wallace](https://www.projectwallace.com)
* [sass-lint](https://github.com/sasstools/sass-lint) -适用于sass和scss语法的仅节点Sass linter.
* [scsslint](https://github.com/brigade/scss-lint) -Sinter文件的Linter
* [Specificity Graph](https://github.com/pocketjoso/specificity-graph) -CSS特异性图生成器
* [Stylelint](http://stylelint.io/) -用于SCSS / CSS文件的Linter

## Gherkin

* [gherkin-lint](https://github.com/vsiakka/gherkin-lint) -用Java语言编写的小黄瓜语法的短毛猫.

## HTML

* [HTML Inspector](https://github.com/philipwalton/html-inspector) -HTML Inspector是一种代码质量工具，可帮助您和您的团队编写更好的标记.
* [HTML Tidy](http://www.html-tidy.org/) - Corrects and cleans up HTML and XML documents by fixing markup errors and upgrading legacy code to modern standards.
* [HTMLHint](https://github.com/yaniswang/HTMLHint) -用于HTML的静态代码分析工具
* [Polymer-analyzer](https://github.com/Polymer/polymer-analyzer) -Web组件的静态分析框架.

## IDE

* [Android Studio](https://developer.android.com/studio) -基于IntelliJ IDEA，并捆绑了适用于Android的工具，包括Android Lint.
* [IntelliJ IDEA](https://www.jetbrains.com/idea/) -捆绑了许多针对Java和Kotlin的检查，并包括用于重构，格式化等的工具.

## IDE Plugins

* [ale](https://github.com/w0rp/ale) -Vim和NeoVim的异步Lint引擎，支持多种语言
* [Attackflow Extension](https://www.attackflow.com/Extension) ：copyright：-用于Visual Studio的Attackflow插件，它使开发人员无需任何先验知识就可以在源代码中实时发现关键的安全错误.
* [DevSkim](https://github.com/Microsoft/DevSkim)  -在线实时安全分析.  与多种编程语言和IDE（VS，VS Code，Sublime Text等）配合使用.
* [Puma Scan](https://github.com/pumasecurity/puma-scan) -开发团队在Visual Studio中编写代码时，Puma Scan提供了针对常见漏洞（XSS，SQLi，CSRF，LDAPi，加密，反序列化等）的实时安全代码分析.
* [Security Code Scan](https://security-code-scan.github.io/) - Security code analyzer for C# and VB.NET that integrates into Visual Studio 2015 and newer. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
* [vint](https://github.com/Kuniwak/vint) -由Python实现的快速且高度可扩展的Vim脚本语言Lint.

## LaTeX

* [ChkTeX](http://www.nongnu.org/chktex/) -用于LaTex的短毛绒，它捕获LaTeX监督的一些印刷错误.
* [lacheck](https://www.ctan.org/pkg/lacheck) -查找LaTeX文档中常见错误的工具.

## Makefiles

* [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) -FreeBSD和DragonFlyBSD端口目录的验证程序.

## Markdown

* [markdownlint](https://github.com/DavidAnson/markdownlint) -用于Markdown / CommonMark文件的基于Node.js的样式检查器和lint工具.
* [mdl](https://github.com/mivok/markdownlint) -检查Markdown文件和标志样式问题的工具.
* [remark-lint](https://github.com/remarkjs/remark-lint) -用JavaScript编写的可插入Markdown代码样式的linter.

## Mobile

* [Android Lint](http://tools.android.com/tips/lint) -在Android项目上运行静态分析.
* [android-lint-summary](https://github.com/passy/android-lint-summary) -将多个项目的棉绒错误合并为一个输出，立即检查多个子项目的棉绒结果.
* [FlowDroid](https://github.com/secure-software-engineering/soot-infoflow-android) -适用于Android应用程序的静态污点分析工具
* [paprika](https://github.com/GeoffreyHecht/paprika) -一个工具包，用于检测已分析的Android应用程序中的某些代码气味.
* [qark](https://github.com/linkedin/qark) -查找多个与安全性相关的Android应用程序漏洞的工具

## Packages

* [lintian](https://github.com/Debian/lintian) -Debian软件包的静态分析工具
* [rpmlint](https://github.com/rpm-software-management/rpmlint) -用于检查rpm包中常见错误的工具

## Protocol-Buffer

* [protolint](https://github.com/yoheimuta/protolint) -可插入的linter和fixer，用于实施协议缓冲区样式和约定.

## Supporting Tools

* [LibVCS4j](https://github.com/uni-bremen-agst/libvcs4j) -一个Java库，通过为不同的版本控制系统和问题跟踪器提供通用API，允许现有工具分析软件系统的演变.
* [Violations Lib](https://github.com/tomasbjerre/violations-lib)  -用于从静态代码分析中解析报告文件的Java库.  由许多Jenkins，Maven和Gradle插件使用.

## Template-Languages

* [ember-template-lint](https://github.com/rwjblue/ember-template-lint) -灰烬的Ember或Handlebars模板.
* [haml-lint](https://github.com/brigade/haml-lint) -用于编写干净且一致的HAML的工具
* [slim-lint](https://github.com/sds/slim-lint) -用于分析Slim模板的可配置工具
* [yamllint](https://github.com/adrienverge/yamllint) -检查YAML文件的语法有效性，键重复和外观问题，例如行长，尾随空格和缩进.

## Translation

* [dennis](https://github.com/willkg/dennis/) -一组用于处理PO文件的实用程序，以简化开发并提高质量.

## Writing

* [After the Deadline](https://afterthedeadline.com/) ：警告：-拼写，样式和语法检查器
* [codespell](https://github.com/codespell-project/codespell) -检查常见拼写错误的代码
* [languagetool](https://github.com/languagetool-org/languagetool)  -超过25种语言的样式和语法检查器.  它会发现许多简单的拼写检查器无法检测到的错误.
* [misspell-fixer](https://github.com/vlajos/misspell-fixer) -在源代码中修复常见拼写错误，错别字的快速工具
* [Misspelled Words In Context](https://github.com/jwilk/mwic) -拼写检查器，对可能的拼写错误进行分组并在上下文中显示它们
* [proselint](https://github.com/amperser/proselint/) -专为英语散文而设的短篇小说，重点是写作风格而不是语法.
* [vale](https://github.com/ValeLint/vale) -用于散文的可自定义，语法感知的linter.
* [write-good](https://github.com/btford/write-good) -重点消除“狡猾的单词”的短毛猫.

## Web services
* [Codacy](https://www.codacy.com/) ：copyright：-代码分析可以更快地发布更好的代码.
* [Code Climate](https://codeclimate.com/) ：copyright：-面向所有人的开放和可扩展的静态分析平台.
* [Code Inspector](https://www.code-inspector.com) ：copyright：-支持10多种语言的代码质量和技术债务管理平台.
* [Codeac](https://www.codeac.io?ref=awesome-static-analysis)  ：copyright：-自动代码审查工具与GitHub，Bitbucket和GitLab（甚至是自托管）集成.  适用于JavaScript，TypeScript，Python，Ruby，Go，PHP，Java，Docker等.  （免费开源）
* [CodeFactor](https://codefactor.io) ：copyright：-在GitHub或BitBucket上针对仓库的自动代码分析.
* [CodeFlow](https://www.getcodeflow.com)  ：copyright：-自动化的代码分析工具来处理技术深度.  与Bitbucket和Gitlab集成.  （对于开源项目免费）
* [CodePatrol](https://cyber-security.claranet.fr/en/codepatrol) ：copyright：-由安全性驱动的自动SAST代码审查，支持15种以上的语言，并包括安全培训.
* [Embold](https://embold.io) :copyright: - Intelligent software analytics platform that identifies design issues, code issues, duplication and metrics. Supports Java, C, C++, C#, JavaScript, TypeScript, Python, Go, Kotlin and more.
* [kiuwan](https://www.kiuwan.com/) ：copyright：-云中的软件分析支持超过22种编程语言.
* [Landscape](https://landscape.io/) ：copyright：-Python的静态代码分析
* [Layered Insight](https://layeredinsight.com/) ：copyright：-容器本机应用程序保护，以提供对容器化应用程序的可见性和控制.
* [LGTM.com](https://lgtm.com/)  ：copyright：-针对GitHub和Bitbucket的深入代码分析，以发现安全漏洞和关键代码质量问题（使用Semmle QL）.  自动查看拉取请求的代码；  免费用于公共存储库.
* [Nitpick CI](https://nitpick-ci.com) ：copyright：-自动化PHP代码审查
* [PullRequest](https://www.pullrequest.com) ：copyright：-具有内置静态分析功能的代码审查服务
* [QuantifiedCode](https://www.quantifiedcode.com/) -自动代码审查和修复
* [Reshift](https://softwaresecured.com/reshift/) ：copyright：-用于检测和管理Java安全漏洞的源代码分析工具.
* [Scrutinizer](https://scrutinizer-ci.com/) ：copyright：-可与GitHub集成的专有代码质量检查器
* [SensioLabs Insight](https://insight.sensiolabs.com/) ：copyright：-检测安全风险，查找错误并为PHP项目提供可行的指标
* [Sider](https://sider.review)  ：copyright：-一个自动的代码检查工具.  提高开发人员的生产力.
* [Snyk](https://snyk.io/) ：copyright：-漏洞扫描程序，用于依赖node.js应用程序（开放源代码项目免费）
* [SonarCloud](https://sonarcloud.io)  ：copyright：-基于多语言云的静态代码分析.  历史，趋势，安全热点，请求请求分析等.  免费提供开源.
* [Teamscale](http://www.teamscale.com/)  ：copyright：-支持超过25种语言并直接集成IDE的静态和动态分析工具.  可应要求免费托管开源项目.  提供免费的学术许可证.
* [Upsource](https://www.jetbrains.com/upsource/) ：copyright：-具有Java，PHP，JavaScript和Kotlin的静态代码分析和代码感知导航的代码审查工具.

## More collections

* [go-tools](https://github.com/dominikh/go-tools) -使用Go代码的工具和库的集合，包括短绒和静态分析
* [linters](https://github.com/mcandre/linters) -静态代码分析简介
* [php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools) -有用的PHP静态分析工具的完整列表
* [Tools for Tcl](https://wiki.tcl-lang.org/page/Static+syntax+analysis#95329c336da897c3dea8ab434ca30575f4529bf6f514c1519881bd126e1d1423) - A wiki-page with several Tcl checker and static syntax analysis tools.
* [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) -用于静态代码分析的工具列表.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Matthias Endler](https://endler.dev) 已放弃此作品的所有版权以及相关或邻近的权利.
标题图片 [Designed by Freepik](http://www.freepik.com).
