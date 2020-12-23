<div class="github-widget" data-repo="analysis-tools-dev/static-analysis"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--  DON'T EDIT THIS FILE DIRECTLY. Edit `data/tools.yml` instead.  -->

 <a href="http://analysis-tools.dev/">
   <img width="400px" alt="Analysis Tools" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/logo.png" />
 </a>

该存储库列出了适用于所有编程语言的“静态分析工具” **，构建工具，配置文件等.  
官方网站， [analysis-tools.dev](https://analysis-tools.dev/) 基于该存储库，并为每个工具添加了排名，用户评论和其他资源（例如视频）.

![CI](https://github.com/analysis-tools-dev/static-analysis/workflows/CI/badge.svg)

## What is Static Analysis?

&gt;静态程序分析是对没有实际执行程序的情况下执行的计算机软件的分析， [Wikipedia](https://en.wikipedia.org/wiki/Static_program_analysis)

 &gt;近年来，作为一名程序员，我要做的最重要的事情是积极地进行静态代码分析. 与我所预防的数百个严重错误相比，更有价值的是关于我查看软件可靠性和代码质量的方式的观念转变.  — [John Carmack (Creator of Doom)](https://www.gamasutra.com/view/news/128836/InDepth_Static_Code_Analysis.php)

## Sponsors

没有我们的赞助商的大力支持，这个项目将是不可能的.

<table>
  <tr>
    <td><a href="https://deepcode.ai"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/deepcode.svg" /></a></td>
    <td><a href="https://deepsource.io/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/deepsource.png" /></a></td>
    <td><a href="https://www.viva64.com/free-license"><img height="100px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/pvs-studio.svg" /></a></td>
    <td><a href="https://codescene.io/"><img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/website/master/static/sponsors/codescene.png" /></a></td>
  </tr>
</table>

如果您还想支持该项目，请前往我们 [Github sponsors page](https://github.com/sponsors/analysis-tools-dev).

## Meaning of Symbols:

- :copyright: stands for proprietary software. All other tools are Open Source.
 -：information_source：指示社区不再建议将该工具用于新项目. 该图标链接到讨论问题.
-：警告：表示该工具的更新时间未超过1年，或者存储库已存档.

拉请求非常欢迎！  
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
    <li><a href="#vim-script">Vim Script</a></li>
    </ul>
</details>




---

## Programming Languages

<h2 id="abap">阿巴普</h2>

- [abaplint](https://abaplint.org) -用TypeScript编写的ABAP的Linter.
- [abapOpenChecks](https://docs.abapopenchecks.org) - Enhances the SAP Code Inspector with new and customizable checks.
- [dialyxir](https://github.com/jeremyjh/dialyxir) -混合任务以简化Elixir项目中Dialyzer的使用.


<h2 id="ada">有</h2>

- [Codepeer](http://www.adacore.com/codepeer) ：copyright：-检测运行时和逻辑错误.
- [Polyspace for Ada](https://www.mathworks.com/products/polyspace-ada.html) ：copyright：-提供代码验证，以证明源代码中不存在溢出，除零，越界数组访问以及某些其他运行时错误.
- [SPARK](https://www.adacore.com/about-spark) ：copyright：-Ada的静态分析和形式验证工具集.


<h2 id="asm">部件</h2>

- [STOKE](http://stoke.stanford.edu)  -针对x86_64指令集的编程语言不可知随机优化器. 它使用随机搜索来探索所有可能的程序转换的极高维空间.


<h2 id="awk">Awk</h2>

- [gawk --lint](https://www.gnu.org/software/gawk/manual/html_node/Options.html) -警告有关可疑或不可移植到其他awk实现的构造.


<h2 id="c">C</h2>

- [Astrée](https://www.absint.com/astree/index.htm) ：copyright：-基于C / C ++抽象解释的声音静态分析器，可检测内存，类型和并发缺陷以及MISRA违规.
- [CBMC](http://www.cprover.org/cbmc) -用于C程序，用户定义的断言，标准断言，多个coverage度量分析的有界模型检查器.
- [clang-tidy](http://clang.llvm.org/extra/clang-tidy) -lang静态分析.
- [clazy](https://github.com/KDE/clazy)  -基于Clang框架的面向Qt的静态代码分析器.  clazy是一个编译器插件，允许clang理解Qt语义. 您会收到50多个与Qt相关的编译器警告，范围从不必要的内存分配到API的滥用，包括用于自动重构的修复程序.
- [CMetrics](https://github.com/MetricsGrimoire/CMetrics) -测量C文件的大小和复杂性.
- [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) ：copyright：-高级，整个程序，深层路径，对C和C ++的静态分析以及易于理解的说明以及代码和路径可视化.
- [cppcheck](http://cppcheck.sourceforge.net) -C / C ++代码的静态分析.
- [CppDepend](https://www.cppdepend.com) ：warning：：copyright：-测量，查询和可视化您的代码，避免意外的问题，技术负担和复杂性.
- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) -遵循Google样式指南的自动C ++检查器.
- [cqmetrics](https://github.com/dspinellis/cqmetrics) -C代码的质量指标.
- [CScout](https://www.spinellis.gr/cscout) -C和C预处理程序代码的复杂性和质量指标.
- [ESBMC](http://esbmc.org) -ESBMC是基于可满足性模理论的开放源代码，未经许可的，有上下文约束的模型检查器，用于验证单线程和多线程C / C ++程序.
- [flawfinder](https://www.dwheeler.com/flawfinder) -查找可能的安全漏洞.
- [flint++](https://github.com/JossWhittle/FlintPlusPlus) -flint的跨平台，零依赖端口，这是Facebook开发和使用的C ++ lint程序.
- [Frama-C](http://frama-c.com) -完善的C代码静态分析器.
- [Helix QAC](https://www.perforce.com/products/helix-qac)  ：copyright：-嵌入式软件的企业级静态分析. 支持MISRA，CERT和AUTOSAR编码标准.
- [IKOS](https://github.com/nasa-sw-vnv/ikos) -基于LLVM的C / C ++代码的声音静态分析器.
- [Joern](https://joern.io) -基于代码属性图的C / C ++开源代码分析平台
- [LDRA](https://ldra.com) ：copyright：-一个工具套件，包括对各种标准的静态分析（TBVISION），包括MISRA C＆C ++，JSF ++ AV，CWE，CERT C，CERT C ++和自定义规则.
- [PC-lint](https://www.gimpel.com)  ：copyright：-C / C ++的静态分析. 在Windows / Linux / MacOS下本机运行. 支持C11 / C18和C ++ 17的几乎任何平台的代码分析.
- [Phasar](https://phasar.org) -基于LLVM的静态分析框架，带有污点和类型状态分析.
- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) ：copyright：-标识C和C ++嵌入式软件中的运行时错误，并发问题，安全漏洞和其他缺陷.
- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) ：copyright：-提供代码验证，以证明C和C ++源代码中没有溢出，被零除，越界数组访问以及某些其他运行时错误.
- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) -在编译时使用LLVM分析C / C ++代码.
- [splint](http://splint.org) -注释辅助的静态程序检查器.
- [SVF](http://svf-tools.github.io/SVF) -静态工具，可对C和C ++程序进行可伸缩且精确的过程间依存关系分析.
- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) -Vera ++是用于验证，分析和转换C ++源代码的可编程工具.


<h2 id="csharp">C#</h2>

- [.NET Analyzers](https://github.com/DotNetAnalyzers) -使用.NET编译器平台开发分析器（诊断和代码修复）的组织.
- [ArchUnitNET](https://github.com/TNG/ArchUnitNET) - A C# architecture test library to specify and assert architecture rules in C# for automated testing.
- [Code Analysis Rule Collection](https://carc.codeplex.com) ：warning：-包含一组基于Microsoft .NET编译器平台“ Roslyn”构建的诊断，代码修复和重构.
- [code-cracker](http://code-cracker.github.io) - An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.
- [CSharpEssentials](https://github.com/DustinCampbell/CSharpEssentials) - C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features.
- [Designite](http://www.designite-tools.com) ：copyright：-Designite支持检测各种体系结构，设计和实现的气味，计算各种代码质量指标以及趋势分析.
- [Gendarme](https://www.mono-project.com/docs/tools+libraries/tools/gendarme) -Gendarme检查包含ECMA CIL格式（Mono和.NET）代码的程序和库.
- [NDepend](http://www.ndepend.com) ：copyright：-测量，查询和可视化您的代码，避免意外的问题，技术负担和复杂性.
- [Puma Scan](https://pumasecurity.io) -开发团队在Visual Studio中编写代码时，Puma Scan提供了针对常见漏洞（XSS，SQLi，CSRF，LDAPi，加密，反序列化等）的实时安全代码分析.
- [Roslynator](https://github.com/JosefPihrt/Roslynator) - A collection of 190+ analyzers and 190+ refactorings for C#, powered by Roslyn.
- [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) -与VS集成的基于Roslyn的静态分析器集合.
- [Wintellect.Analyzers](https://github.com/Wintellect/Wintellect.Analyzers) -.NET编译器平台（“ Roslyn”）诊断分析器和代码修复.


<h2 id="cpp">C ++</h2>

- [Astrée](https://www.absint.com/astree/index.htm) ：copyright：-基于C / C ++抽象解释的声音静态分析器，可检测内存，类型和并发缺陷以及MISRA违规.
- [CBMC](http://www.cprover.org/cbmc) -用于C程序，用户定义的断言，标准断言，多个coverage度量分析的有界模型检查器.
- [clang-tidy](http://clang.llvm.org/extra/clang-tidy) -lang静态分析.
- [clazy](https://github.com/KDE/clazy)  -基于Clang框架的面向Qt的静态代码分析器.  clazy是一个编译器插件，允许clang理解Qt语义. 您会收到50多个与Qt相关的编译器警告，范围从不必要的内存分配到API的滥用，包括用于自动重构的修复程序.
- [CMetrics](https://github.com/MetricsGrimoire/CMetrics) -测量C文件的大小和复杂性.
- [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) ：copyright：-高级，整个程序，深层路径，对C和C ++的静态分析以及易于理解的说明以及代码和路径可视化.
- [cppcheck](http://cppcheck.sourceforge.net) -C / C ++代码的静态分析.
- [CppDepend](https://www.cppdepend.com) ：warning：：copyright：-测量，查询和可视化您的代码，避免意外的问题，技术负担和复杂性.
- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) -遵循Google样式指南的自动C ++检查器.
- [cqmetrics](https://github.com/dspinellis/cqmetrics) -C代码的质量指标.
- [CScout](https://www.spinellis.gr/cscout) -C和C预处理程序代码的复杂性和质量指标.
- [ESBMC](http://esbmc.org) -ESBMC是基于可满足性模理论的开放源代码，未经许可的，有上下文约束的模型检查器，用于验证单线程和多线程C / C ++程序.
- [flawfinder](https://www.dwheeler.com/flawfinder) -查找可能的安全漏洞.
- [flint++](https://github.com/JossWhittle/FlintPlusPlus) -flint的跨平台，零依赖端口，这是Facebook开发和使用的C ++ lint程序.
- [Frama-C](http://frama-c.com) -完善的C代码静态分析器.
- [Helix QAC](https://www.perforce.com/products/helix-qac)  ：copyright：-嵌入式软件的企业级静态分析. 支持MISRA，CERT和AUTOSAR编码标准.
- [IKOS](https://github.com/nasa-sw-vnv/ikos) -基于LLVM的C / C ++代码的声音静态分析器.
- [Joern](https://joern.io) -基于代码属性图的C / C ++开源代码分析平台
- [LDRA](https://ldra.com) ：copyright：-一个工具套件，包括对各种标准的静态分析（TBVISION），包括MISRA C＆C ++，JSF ++ AV，CWE，CERT C，CERT C ++和自定义规则.
- [PC-lint](https://www.gimpel.com)  ：copyright：-C / C ++的静态分析. 在Windows / Linux / MacOS下本机运行. 支持C11 / C18和C ++ 17的几乎任何平台的代码分析.
- [Phasar](https://phasar.org) -基于LLVM的静态分析框架，带有污点和类型状态分析.
- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) ：copyright：-标识C和C ++嵌入式软件中的运行时错误，并发问题，安全漏洞和其他缺陷.
- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) ：copyright：-提供代码验证，以证明C和C ++源代码中没有溢出，被零除，越界数组访问以及某些其他运行时错误.
- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) -在编译时使用LLVM分析C / C ++代码.
- [splint](http://splint.org) -注释辅助的静态程序检查器.
- [SVF](http://svf-tools.github.io/SVF) -静态工具，可对C和C ++程序进行可伸缩且精确的过程间依存关系分析.
- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) -Vera ++是用于验证，分析和转换C ++源代码的可编程工具.


<h2 id="clojure">Clojure</h2>

- [clj-kondo](https://github.com/borkdude/clj-kondo)  -用于Clojure代码的短毛绒，可带来欢乐. 它会在您键入时通知您有关潜在的错误.


<h2 id="coffeescript">CoffeeScript</h2>

- [coffeelint](http://www.coffeelint.org) -样式检查器，有助于使CoffeeScript代码保持干净和一致.


<h2 id="crystal">水晶</h2>

- [ameba](https://crystal-ameba.github.io) -用于Crystal的静态代码分析工具.
- [crystal](https://crystal-lang.org) -Crystal编译器具有内置的棉绒功能.


<h2 id="dart">镖</h2>

- [effective_dart](https://pub.dev/packages/effective_dart) -与有效飞镖指南相对应的短绒规则
- [lint](https://github.com/passsy/dart-lint)  -针对Dart和Flutter项目的一套由社区驱动的，有条理的皮棉规则. 像书呆子，但更严格
- [Linter for dart](https://dart-lang.github.io/linter) -Dart风格的短绒.


<h2 id="delphi">德尔菲</h2>

- [Fix Insight](https://www.tmssoftware.com/site/fixinsight.asp)  ：copyright：-一个免费的IDE插件，用于静态代码分析.  _Pro_版本包含用于自动化目的的命令行工具.
- [Pascal Analyzer](https://peganza.com/products_pal.html)  ：copyright：-具有大量报告的静态代码分析工具. 提供免费的_Lite_版本，报告数量有限.
- [Pascal Expert](https://peganza.com/products_pex.html)  ：copyright：-用于代码分析的IDE插件. 包括Pascal Analyzer报告功能的一部分，并且可用于Delphi 2007及更高版本.


<h2 id="dlang">德朗</h2>

- [D-scanner](https://github.com/dlang-community/D-Scanner) -D-Scanner是用于分析D源代码的工具.


<h2 id="elixir">长生不老药</h2>

- [credo](https://github.com/rrrene/credo) -静态代码分析工具，专注于代码一致性和教学.
- [sobelow](https://github.com/nccgroup/sobelow) -Phoenix框架的安全性静态分析.


<h2 id="elm">榆树</h2>

- [elm-analyse](https://stil4m.github.io/elm-analyse) -一种工具，可让您分析Elm代码，识别缺陷并应用最佳实践.
- [elm-review](https://package.elm-lang.org/packages/jfmengels/elm-review/latest) -分析整个Elm项目，重点放在用Elm编写的可共享和自定义规则上，这些规则可以确保Elm编译器不会提供给您.


<h2 id="erlang">Erlang</h2>

- [dialyzer](https://erlang.org/doc/man/dialyzer.html)  -DIALYZER，一个用于ERlang程序的差异分析仪.  Dialyzer是一种静态分析工具，可在单个Erlang模块或整个（组）应用程序中识别软件差异，例如确定的类型错误，由于编程错误而变得无效或无法访问的代码以及不必要的测试.
 Dialyzer从调试编译的BEAM字节码或Erlang源代码开始分析. 报告差异的文件和行号以及有关差异的指示.  Dialyzer的分析基于成功类型的概念，该概念允许发出声音警告（无误报）.
- [elvis](https://github.com/inaka/elvis) -Erlang样式审阅者.
- [Primitive Erlang Security Tool (PEST)](https://github.com/okeuday/pest) -一种对Erlang源代码进行基本扫描并报告可能导致Erlang源代码不安全的函数调用的工具.


<h2 id="fsharp">F#</h2>

- [FSharpLint](http://fsprojects.github.io/FSharpLint) - Lint tool for F#.


<h2 id="fortran">Fortran</h2>

- [i-Code CNES for Fortran](https://github.com/lequal/i-CodeCNES) -用于Fortran 77，Fortran 90和Shell的开源静态代码分析工具.


<h2 id="go">走</h2>

- [aligncheck](https://gitlab.com/opennota/check) -查找效率低下的打包结构.
- [bodyclose](https://github.com/timakin/bodyclose) -检查HTTP响应主体是否关闭.
- [deadcode](https://github.com/tsenart/deadcode) -查找未使用的代码.
- [dingo-hunter](https://github.com/nickng/dingo-hunter) -用于在Go中查找死锁的静态分析器.
- [dogsled](https://github.com/alexkohler/dogsled) -查找带有太多空白标识符的分配/声明.
- [dupl](https://github.com/mibk/dupl) -报告可能重复的代码.
- [errcheck](https://github.com/kisielk/errcheck) -检查是否使用了错误返回值.
- [errwrap](https://github.com/fatih/errwrap)  -使用新的％w动词指令包装和修复Go错误. 此工具分析fmt.Errorf（）调用并报告包含与Go v1.13中引入的新％w verb指令不同的verb指令的调用. 它也能够重写调用以使用新的％w wrap verb指令.
- [flen](https://github.com/lafolle/flen) -在Go软件包中获取有关函数长度的信息.
- [go tool vet --shadow](https://golang.org/cmd/vet#hdr-Shadowed_variables) -报告可能被意外遮盖的变量.
- [go vet](https://golang.org/cmd/vet) -检查Go源代码并报告可疑.
- [go-consistent](https://github.com/Quasilyte/go-consistent) -分析器，可帮助您使Go程序更加一致.
- [go-critic](https://github.com/go-critic/go-critic) -保留检查当前未在其他linter中实现的检查的源代码linter.
- [go/ast](https://golang.org/pkg/go/ast) -包ast声明用于表示Go包的语法树的类型.
- [gochecknoglobals](https://github.com/leighmcculloch/gochecknoglobals) -检查是否没有全局变量.
- [goconst](https://github.com/jgautheron/goconst) -查找可以被常量替换的重复字符串.
- [gocyclo](https://github.com/fzipp/gocyclo) -计算Go源代码中函数的圈复杂度.
- [gofmt -s](https://golang.org/cmd/gofmt) -检查代码的格式是否正确，是否无法进一步简化.
- [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) -检查丢失或未引用的程序包导入.
- [GolangCI-Lint](https://golangci-lint.run) -替代“ Go Meta Linter”：GolangCI-Lint是一个Linters聚合器.
- [golint](https://github.com/golang/lint) -在Go源代码中打印出编码样式错误.
- [goroutine-inspect](https://github.com/linuxerwang/goroutine-inspect) -分析Golang goroutine转储的交互式工具.
- [gosec (gas)](https://securego.io) -通过扫描Go AST检查源代码是否存在安全问题.
- [gotype](https://pkg.go.dev/golang.org/x/tools/cmd/gotype) -类似于Go编译器的语法和语义分析.
- [ineffassign](https://github.com/gordonklaus/ineffassign) -在Go代码中检测无效的分配.
- [interfacer](https://github.com/mvdan/interfacer) ：警告：-建议使用较窄的接口.
- [lll](https://github.com/walle/lll) -报告长行.
- [maligned](https://github.com/mdempsky/maligned) -检测对字段进行排序后会占用较少内存的结构.
- [misspell](https://github.com/client9/misspell) -查找通常拼写错误的英语单词.
- [nakedret](https://github.com/alexkohler/nakedret) -寻找赤裸裸的回报.
- [nargs](https://github.com/alexkohler/nargs) -在函数声明中查找未使用的参数.
- [prealloc](https://github.com/alexkohler/prealloc) -查找可能预先分配的切片声明.
- [revive](https://revive.run)  -Go的快速，可配置，可扩展，灵活和美观的Linter. 即插即用更换小垫布.
- [safesql](https://github.com/stripe/safesql) -用于Golang的静态分析工具，可防止SQL注入.
- [staticcheck](https://staticcheck.io) -进行静态分析，专门用于发现错误，简化代码并提高性能.
- [structcheck](https://gitlab.com/opennota/check) -查找未使用的结构字段.
- [test](http://golang.org/pkg/testing) -从stdlib测试模块显示测试失败的位置.
- [unconvert](https://github.com/mdempsky/unconvert) -检测冗余类型转换.
- [unparam](https://github.com/mvdan/unparam) -查找未使用的功能参数.
- [varcheck](https://gitlab.com/opennota/check) -查找未使用的全局变量和常量.
- [wsl](https://github.com/bombsimon/wsl) -在正确的地方插入空行.


<h2 id="groovy">Groovy</h2>

- [CodeNarc](https://codenarc.github.io/CodeNarc) -用于Groovy源代码的静态分析工具，可以监视和执行许多编码标准和最佳实践.


<h2 id="haskell">哈斯克尔</h2>

- [brittany](https://github.com/lspitzner/brittany) -Haskell源代码格式化程序
- [HLint](https://github.com/ndmitchell/hlint) -HLint是用于建议对Haskell代码进行可能的改进的工具.
- [Stan](https://kowainik.github.io/projects/stan) -Stan是一种命令行工具，用于分析Haskell项目并以有用的方式输出发现的漏洞，并提供可能的解决方案来解决已发现的问题.
- [Weeder](https://github.com/ocharles/weeder) - A tool for detecting dead exports or package imports in Haskell code.


<h2 id="haxe">哈克斯</h2>

- [Haxe Checkstyle](http://haxecheckstyle.github.io/docs/haxe-checkstyle/home.html) -静态分析工具，可帮助开发人员编写符合编码标准的Haxe代码.


<h2 id="java">爪哇</h2>

- [Checker Framework](https://checkerframework.org) -Java的可插入类型检查.
- [checkstyle](https://checkstyle.org) -检查Java源代码是否符合代码标准或一组验证规则（最佳做法）.
- [ck](https://github.com/mauricioaniche/ck) -通过处理源Java文件来计算Chidamber和Kemerer的面向对象的指标.
- [ckjm](http://www.spinellis.gr/sw/ckjm) -通过处理已编译的Java文件的字节码来计算Chidamber和Kemerer的面向对象的度量.
- [CogniCrypt](https://www.eclipse.org/cognicrypt) -检查Java源代码和字节码是否使用了错误的加密API.
- [DesigniteJava](http://www.designite-tools.com/designitejava) ：copyright：-DesigniteJava支持各种体系结构，设计和实现气味的检测以及各种代码质量指标的计算.
- [Error-prone](https://errorprone.info) -捕获常见的Java错误作为编译时错误.
- [fb-contrib](http://fb-contrib.sourceforge.net) -FindBugs的插件，带有其他错误检测器.
- [forbidden-apis](https://github.com/policeman-tools/forbidden-apis)  -检测并禁止调用特定的方法/类/字段（例如从没有字符集的文本流中读取）.  Maven / Gradle / Ant兼容.
- [google-java-format](https://github.com/google/google-java-format) -Google样式重新格式化.
- [HuntBugs](https://github.com/amaembo/huntbugs) ：warning：-基于Procyon编译器工具的字节码静态分析器工具，旨在取代FindBugs.
- [IntelliJ IDEA](https://www.jetbrains.com/idea) ：copyright：-捆绑了许多针对Java和Kotlin的检查，其中包括用于重构，格式化等的工具.
- [JArchitect](https://www.jarchitect.com) ：copyright：-测量，查询和可视化您的代码，避免意外的问题，技术负担和复杂性.
- [JBMC](https://www.cprover.org/jbmc) -Java的有界模型检查器（字节码），验证用户定义的断言，标准断言和若干覆盖率度量分析.
- [NullAway](https://github.com/uber/NullAway)  -基于类型的空指针检查器，具有较低的构建时间开销； 一个 [Error Prone](http://errorprone.info/) 插入.
- [OWASP Dependency Check](https://owasp.org/www-project-dependency-check) -检查依赖项是否存在已知的，公开披露的漏洞.
- [qulice](https://www.qulice.com) -结合了一些（预先配置的）静态分析工具（checkstyle，PMD，Findbugs等）.
- [Soot](https://soot-oss.github.io/soot) -用于分析和转换Java和Android应用程序的框架.
- [Spoon](http://spoon.gforge.inria.fr)  -Spoon是一个元编程库，用于分析和转换Java源代码（包括Java 9、10、11、12、13、14）. 它解析源文件以构建具有强大分析和转换API的精心设计的AST. 可以集成在Maven和Gradle中.
- [SpotBugs](https://spotbugs.github.io)  -SpotBugs是FindBugs的继任者. 静态分析工具，用于查找Java代码中的错误.


<h2 id="javascript">的JavaScript</h2>

- [aether](http://aetherjs.com) -在节点或浏览器中对用户JavaScript进行Lint，分析，规范化，转换，沙盒运行，逐步浏览和可视化.
- [Closure Compiler](https://developers.google.com/closure/compiler) -一种编译器工具，可提高效率，减小大小并在JavaScript文件中提供代码警告.
- [ClosureLinter](https://github.com/google/closure-linter)  ：warning：-确保您所有项目的JavaScript代码均遵循Google JavaScript样式指南中的指南. 它还可以自动修复许多常见错误.
- [complexity-report](https://github.com/escomplex/complexity-report) ：warning：-JavaScript项目的软件复杂性分析.
- [DeepScan](https://deepscan.io) ：copyright：-一个JavaScript分析器，它针对运行时错误和质量问题，而不是编码约定.
- [es6-plato](https://github.com/the-simian/es6-plato) -可视化JavaScript（ES6）源复杂性.
- [escomplex](https://github.com/jared-stilwell/escomplex) -JavaScript系列抽象语法树的软件复杂性分析.
- [Esprima](https://esprima.org) -ECMAScript解析基础结构，用于多用途分析.
- [flow](https://flow.org) -JavaScript的静态类型检查器.
- [hegel](https://hegel.js.org) -JavaScript的静态类型检查器，带有类型推断偏向和强类型系统.
- [jshint](https://jshint.com/about) [:information_source:](https://github.com/analysis-tools-dev/static-analysis/blob/master/<https://github.com/analysis-tools-dev/static-analysis/issues/223>) -检测JavaScript代码中的错误和潜在问题，并执行团队的编码约定.
- [JSLint](https://github.com/douglascrockford/JSLint) [:information_source:](https://github.com/analysis-tools-dev/static-analysis/blob/master/<https://github.com/analysis-tools-dev/static-analysis/issues/223>) -JavaScript代码质量工具.
- [JSPrime](http://dpnishant.github.io/jsprime) ：警告：-静态安全分析工具.
- [plato](https://github.com/es-analysis/plato) ：warning：-可视化JavaScript源复杂性.
- [retire.js](http://retirejs.github.io/retire.js) -扫描程序检测已知漏洞的JavaScript库的使用.
- [RSLint](http://rslint.org/) -用Rust编写的（WIP）JavaScript linter，旨在尽可能快，可自定义且易于使用.
- [tern](https://ternjs.net) -JavaScript代码分析器，可提供深入的跨编辑器语言支持.
- [TypL](https://typl.dev) -使用TypL，您只需编写完全标准的JS，然后该工具即可通过强大的推断功能来确定您的类型.
- [xo](https://github.com/xojs/xo)  -固执己见，但可配置的ESLint包装器，其中包含很多东西. 强制执行严格且易读的代码.
- [yardstick](https://github.com/calmh/yardstick) ：warning：-Javascript代码指标.


<h2 id="julia">朱莉亚</h2>

- [StaticLint](https://github.com/julia-vscode/StaticLint.jl) -朱莉娅的静态代码分析


<h2 id="kotlin">科特林</h2>

- [detekt](https://detekt.github.io/detekt) -Kotlin代码的静态代码分析.
- [diktat](https://www.cqfn.org/diKTat) -严格的Kotlin编码标准和可检测并自动修复编码异味的棉绒.
- [ktlint](https://ktlint.github.io) -带有内置格式化程序的防骑自行车科特林短绒.


<h2 id="lua">采取</h2>

- [luacheck](https://github.com/mpeterv/luacheck) -用于Lua代码的整理和静态分析的工具.
- [lualint](https://github.com/philips/lualint) -lualint对Lua源代码中的全局变量使用情况进行基于luac的静态分析.


<h2 id="matlab">的MATLAB</h2>

- [mlint](https://mathworks.com/help/matlab/ref/mlint.html) ：copyright：-检查MATLAB代码文件是否存在问题.


<h2 id="nim">他</h2>

- [DrNim](https://nim-lang.org/docs/drnim.html) -DrNim结合了Nim前端和Z3证明引擎，以允许验证/验证用Nim编写的软件.
- [nimfmt](https://github.com/FedericoCeratto/nimfmt) -Nim代码格式化程序/ linter /样式检查器


<h2 id="ocaml">迷彩</h2>

- [Sys](https://github.com/PLSysSec/sys) -静态分析工具支持LLVM.
- [VeriFast](https://github.com/verifast/verifast) -用于C和Java的源代码验证工具.


<h2 id="php">的PHP</h2>

- [churn-php](https://github.com/bmitch/churn-php) -帮助发现良好的重构候选人.
- [dephpend](https://github.com/mihaeu/dephpend) -依赖性分析工具.
- [deprecation-detector](https://github.com/sensiolabs-de/deprecation-detector) -查找不推荐使用的（Symfony）代码的用法.
- [deptrac](https://github.com/sensiolabs-de/deptrac) -强制执行有关软件层之间依赖性的规则.
- [DesignPatternDetector](https://github.com/Halleck45/DesignPatternDetector) -检测PHP代码中的设计模式.
- [EasyCodingSt和ard](https://www.tomasvotruba.com/blog/2017/05/03/combine-power-of-php-code-sniffer-和-php-cs-fixer-in-3-lines) -结合 [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 和 [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).
- [GrumPHP](https://github.com/phpro/grumphp) -检查每次提交的代码.
- [Mondrian](http://trismegiste.github.io/Mondrian) - A set of static analysis and refactoring tools which use graph theory.
- [parallel-lint](https://github.com/php-parallel-lint/PHP-Parallel-Lint) -该工具检查PHP文件的语法的速度比串行检查的速度更快，输出结果也更出色.
- [Parse](https://github.com/psecio/parse) -静态安全扫描程序.
- [pdepend](https://pdepend.org) -计算软件度量，例如PHP代码的圈复杂度.
- [phan](https://github.com/phan/phan/wiki) -etsy的现代静电分析仪.
- [PHP Architecture Tester](https://github.com/carlosas/phpat) -易于使用的PHP体系结构测试工具.
- [PHP Assumptions](https://github.com/rskuipers/php-assumptions) -检查弱假设.
- [PHP Coding Standards Fixer](https://cs.symfony.com) -根据PSR-1，PSR-2和Symfony标准等标准修复代码.
- [PHP Insights](https://phpinsights.com)  -通过控制台即时进行PHP质量检查. 分析代码质量和编码样式，并对代码体系结构及其复杂性进行概述.
- [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-) -用于PHP的静态代码分析器.
- [PHP Refactoring Browser](http://qafoolabs.github.io/php-refactoring-browser) -重构助手.
- [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) -根据语义版本建议下一个版本.
- [PHP-Parser](https://github.com/nikic/PHP-Parser) -用PHP编写的PHP解析器.
- [php-speller](https://github.com/mekras/php-speller) -PHP拼写检查库.
- [PHP-Token-Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) -模拟PHP内部反射的库.
- [php7cc](https://github.com/sstalle/php7cc) ：警告：-PHP 7兼容性检查器.
- [php7mar](https://github.com/Alexia/php7mar) ：warning：-协助开发人员将其代码快速移植到PHP 7.
- [PHP_CodeSniffer](https://pear.php.net/package/PHP_CodeSniffer) -检测违反定义的一组编码标准的行为.
- [phpca](https://github.com/wapmorgan/PhpCodeAnalyzer) -查找非内置扩展名的用法.
- [phpcpd](https://github.com/sebastianbergmann/phpcpd) -用于PHP代码的复制/粘贴检测器.
- [phpdcd](https://github.com/sebastianbergmann/phpdcd) ：warning：-死代码检测器（DCD）用于PHP代码.
- [PhpDependencyAnalysis](https://mamuz.github.io/PhpDependencyAnalysis) -为项目建立依赖图.
- [PhpDeprecationDetector](https://github.com/wapmorgan/PhpDeprecationDetector)  -PHP代码分析器，用于在较新的解释器版本中搜索过时功能的问题. 它查找已删除的对象（函数，变量，常量和ini指令），不赞成使用的函数功能以及禁止使用的名称或技巧（例如，较新版本中的保留标识符）.
- [phpdoc-to-typehint](https://github.com/dunglas/phpdoc-to-typehint) -添加标量类型提示，并使用PHPDoc注释将类型返回给现有的PHP项目.
- [phpDocumentor](https://www.phpdoc.org) -分析PHP源代码以生成文档.
- [phploc](https://github.com/sebastianbergmann/phploc) -快速测量尺寸并分析PHP项目结构的工具.
- [PHPMD](https://phpmd.org) -在代码中查找可能的错误.
- [PhpMetrics](http://www.phpmetrics.org) -计算和可视化各种代码质量指标.
- [phpmnd](https://github.com/povils/phpmnd) -帮助检测魔术数字.
- [PHPQA](https://edgedesigncz.github.io/phpqa) -用于运行质量检查工具（phploc，phpcpd，phpcs，pdepend，phpmd，phpmetrics）的工具.
- [phpqa - jakzal](https://github.com/jakzal/phpqa) -在一个容器中有许多用于PHP静态分析的工具.
- [phpqa - jmolivas](https://github.com/jmolivas/phpqa) -PHPQA多合一分析器CLI工具.
- [phpsa](https://github.com/ovr/phpsa) -用于PHP的静态分析工具.
- [PHPStan](https://phpstan.org) -PHP静态分析工具-无需运行即可发现代码中的错误！
- [Progpilot](https://github.com/designsecurity/progpilot) -出于安全目的的静态分析工具.
- [Psalm](https://psalm.dev) -用于在PHP应用程序中查找类型错误的静态分析工具.
- [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) -可视化指标和源代码.
- [Tuli](https://github.com/ircmaxell/Tuli) -静态分析引擎.
- [twig-lint](https://github.com/asm89/twig-lint) -twig-lint是用于您的twig文件的皮棉工具.
- [WAP](https://securityonline.info/owasp-wap-web-application-protection-project) -用于检测和纠正PHP（4.0或更高版本）Web应用程序中的输入验证漏洞的工具，并通过结合静态分析和数据挖掘来预测误报.


<h2 id="perl">佩尔</h2>

- [Perl::Critic](https://metacpan.org/pod/Perl::Critic) -Critique Perl最佳实践的源代码.


<h2 id="python">蟒蛇</h2>

- [bandit](https://bandit.readthedocs.io/en/latest) -查找Python代码中常见安全问题的工具.
- [bellybutton](https://github.com/hchasestevens/bellybutton) -支持自定义项目特定规则的整理引擎.
- [Black](https://black.readthedocs.io/en/stable) -毫不妥协的Python代码格式化程序.
- [cohesion](https://github.com/mschwager/cohesion) -用于测量Python类内聚力的工具.
- [Dlint](https://github.com/dlint-py/dlint) -确保Python代码安全的工具.
- [fixit](https://pypi.org/project/fixit) -用于创建棉绒规则和源代码的相应自动修复的框架.
- [InspectorTiger](https://github.com/thg-consulting/it)  -IT，Inspector Tiger，是一个现代的python代码审查工具/框架. 它带有许多预定义的处理程序，可以警告您有关改进和可能的错误的信息. 除了这些处理程序之外，您还可以编写自己的处理程序或使用社区处理程序.
- [jedi](https://jedi.readthedocs.io/en/latest) -适用于Python的自动完成/静态分析库.
- [linty fresh](https://github.com/lyft/linty_fresh) -解析皮棉错误，并将其作为请求请求的注释报告给Github.
- [mccabe](https://pypi.org/project/mccabe) -检查McCabe的复杂性.
- [mypy](http://www.mypy-lang.org) -静态类型检查器，旨在结合经常使用的鸭子类型和静态类型的优点 [MonkeyType](https://github.com/Instagram/MonkeyType).
- [py-find-injection](https://github.com/uber/py-find-injection) ：warning：-查找Python代码中的SQL注入漏洞.
- [PyCodeQual](https://pycodequ.al)  ：copyright：-PyCodeQual为您提供有关复杂性和错误风险的见解. 它将自动评论添加到您的请求中.
- [pycodestyle](https://pycodestyle.pycqa.org/en/latest) -（以前是Pep8`）根据PEP 8中的某些样式约定检查Python代码.
- [pydocstyle](http://www.pydocstyle.org) -检查是否符合Python文档字符串约定.
- [pyflakes](https://pypi.org/project/pyflakes) -检查Python源文件是否有错误.
- [pylint](http://pylint.pycqa.org/en/latest)  -查找编程错误，帮助实施编码标准并嗅探某些代码气味. 它还包括“ pyreverse”（UML图生成器）和“ symilar”（相似性检查器）.
- [pyre-check](https://pyre-check.org) -用于大型Python代码库的快速，可扩展的类型检查器.
- [pyright](https://github.com/Microsoft/pyright) -用于Python的静态类型检查器，用于解决现有工具（如mypy）中的空白.
- [pyroma](https://github.com/regebro/pyroma) -评估Python项目与Python打包生态系统的最佳实践的符合程度，并列出可以改进的问题.
- [Pysa](https://pyre-check.org/docs/pysa-basics.html) -一种基于Facebook的堆垛检查的工具，用于通过污点分析识别出Python代码中的潜在安全问题.
- [PyT - Python Taint](https://github.com/python-security/pyt) ：warning：-静态分析工具，用于检测Python Web应用程序中的安全漏洞.
- [pytype](https://google.github.io/pytype) -用于Python代码的静态类型分析器.
- [radon](https://radon.readthedocs.io/en/latest) -一个Python工具，可从源代码计算各种指标.
- [unimport](https://unimport.hakancelik.dev) -一个lint格式化程序，用于查找和删除未使用的导入语句.
- [vulture](https://github.com/jendrikseipp/vulture) -在Python代码中找到未使用的类，函数和变量.
- [wemake-python-styleguide](https://wemake-python-stylegui.de) -有史以来最严格，最自以为是的python linter.
- [wily](https://github.com/tonybaloney/wily) -用于归档，浏览和绘制Python源代码复杂性的命令行工具.
- [xenon](https://xenon.readthedocs.io) -使用监视代码的复杂性 [`radon`](https://github.com/rubik/radon).


<h2 id="r">[R</h2>

- [cyclocomp](https://github.com/MangoTheCat/cyclocomp) -量化R函数/表达式的圈复杂度.
- [goodpractice](http://mangothecat.github.io/goodpractice) -分析R软件包的源代码并提供最佳实践建议.
- [lintr](https://github.com/jimhester/lintr) -R的静态代码分析.
- [styler](https://styler.r-lib.org) -R源代码文件的格式和R代码的漂亮打印.


<h2 id="ruby">红宝石</h2>

- [cane](https://github.com/square/cane) -代码质量阈值检查作为构建的一部分.
- [Fasterer](https://github.com/DamirSvrtan/fasterer) -常见的Ruby习语检查器.
- [flay](https://ruby.sadi.st/Flay.html) -Flay分析代码的结构相似性.
- [flog](https://ruby.sadi.st/Flog.html)  -Flog在易于阅读的疼痛报告中报告了遭受最多折磨的代码. 分数越高，代码所处的痛苦就越大.
- [laser](https://github.com/michaeledgar/laser) ：warning：-Ruby代码的静态分析和样式分析.
- [pelusa](https://github.com/codegram/pelusa) -静态分析Lint型工具，可改善您的OO Ruby代码.
- [Querly](https://github.com/soutaro/querly) -基于模式的Ruby检查工具.
- [Railroader](https://railroader.org) -针对Ruby on Rails应用程序的开源静态分析安全漏洞扫描程序.
- [rails_best_practices](https://rails-bestpractices.com) -Rails项目的代码度量工具
- [reek](https://github.com/troessner/reek) -用于Ruby的代码气味检测器.
- [RuboCop](https://docs.rubocop.org/rubocop) -基于社区Ruby样式指南的Ruby静态代码分析器.
- [Rubrowser](https://github.com/blazeeboy/rubrowser) -Ruby类交互式依赖图生成器.
- [ruby-lint](http://code.yorickpeterse.com/ruby-lint/latest) ：warning：-Ruby的静态代码分析.
- [rubycritic](https://github.com/whitesmith/rubycritic) -Ruby代码质量报告程序.
- [rufo](https://github.com/ruby-formatter/rufo) -一种自以为是的ruby格式化程序，旨在通过命令行作为文本编辑器插件使用，以便在保存或按需自动格式化文件时使用.
- [Saikuro](https://metricfu.github.io/Saikuro) -Ruby循环复杂度分析器.
- [SandiMeter](https://rubygems.org/gems/sandi_meter) ：warning：-静态分析工具，用于检查Ruby代码中的Sandi Metz规则.
- [Sorbet](https://sorbet.org) -专为Ruby设计的快速，强大的类型检查器.
- [Standard Ruby](https://github.com/testdouble/standard) -Ruby样式指南，带有linter和自动代码修复程序
- [Steep](https://github.com/soutaro/steep) -逐步输入Ruby.


<h2 id="rust">锈</h2>

- [C2Rust](https://c2rust.com)  -C2Rust可帮助您将符合C99的代码迁移到Rust. 转换器（或编译器）生成不安全的Rust代码，该代码紧密地镜像了输入的C代码.
- [cargo udeps](https://github.com/est31/cargo-udeps)  -在Cargo.toml中找到未使用的依赖项. 它要么打印出列出未使用的板条箱的“未使用的板条箱”行，要么打印出一条未使用板条箱的行.
- [cargo-audit](https://rustsec.org) -审核Cargo.lock，以将带有安全漏洞的板条箱报告给 [RustSec Advisory Database](https://github.com/RustSec/advisory-db/).
- [cargo-expand](https://github.com/dtolnay/cargo-expand) - Cargo subcommand to show result of macro expansion  and #[derive] expansion applied to the current crate.  This is a wrapper around a more verbose compiler command.
- [cargo-inspect](https://github.com/mre/cargo-inspect) -在没有语法糖的情况下检查Rust代码，以了解编译器的幕后工作.
- [cargo-spellcheck](https://github.com/drahnr/cargo-spellcheck) -使用hunspell（就绪）和languagetool（预览）检查所有文档中的拼写和语法错误
- [clippy](https://rust-lang.github.io/rust-clippy) -防止常见错误并改进Rust代码的代码查询器.
- [electrolysis](http://kha.github.io/electrolysis) -通过在精益定理证明者中将其转换为定义来正式验证Rust程序的工具.
- [herbie](https://github.com/mcarton/rust-herbie-lint) -在使用数值不稳定的浮点表达式时，在包装箱中添加警告或错误.
- [linter-rust](https://github.com/AtomLinter/linter-rust) -使用Rustc和货物在Atom中整理Rust文件.
- [MIRAI](https://github.com/facebookexperimental/MIRAI) -使用Rust的中级中间语言的抽象解释器，并基于异味分析提供警告.
- [Prusti](https://www.pm.inf.ethz.ch/research/prusti.html)  -基于Viper验证基础结构的Rust静态验证程序. 默认情况下，Prusti通过证明unreachable！（）和panic！（）之类的语句不可访问来验证是否存在恐慌.
- [Rust Language Server](https://github.com/rust-lang-nursery/rls) -支持“转到定义”，符号搜索，重新格式化和代码完成等功能，并支持重命名和重构.
- [rust-analyzer](https://rust-analyzer.github.io) -支持诸如“转到定义”，类型推断，符号搜索，重新格式化和代码完成之类的功能，并支持重命名和重构.
- [rust-audit](https://github.com/Shnatsel/rust-audit)  -审核Rust二进制文件中的已知错误或安全漏洞. 这是通过将有关依赖关系树（Cargo.lock）的数据以JSON格式嵌入到已编译的可执行文件的专用链接器部分中而起作用的.
- [rustfix](https://github.com/rust-lang/rustfix) -阅读并应用rustc（和第三方皮棉，如clippy提供的建议）提出的建议.
- [rustfmt](https://github.com/rust-lang/rustfmt) -根据样式准则格式化Rust代码的工具.


<h2 id="sql">的SQL</h2>

- [sqlcheck](https://github.com/jarulraj/sqlcheck) -自动识别SQL查询中的反模式.
- [sqlint](https://github.com/purcell/sqlint) -简单的SQL linter.
- [tsqllint](https://github.com/tsqllint/tsqllint) -特定于T-SQL的linter.
- [TSqlRules](https://github.com/ashleyglee/TSqlRules) -SQL Server的TSQL静态代码分析规则.


<h2 id="scala">阶梯</h2>

- [linter](https://github.com/HairyFotr/linter) -Linter是一个Scala静态分析编译器插件，它为各种可能的错误，效率低下和样式问题添加了编译时检查.
- [Scalastyle](http://www.scalastyle.org) -Scalastyle检查您的Scala代码并指出其潜在问题.
- [scapegoat](https://github.com/sksamuel/scapegoat) -用于静态代码分析的Scala编译器插件.
- [WartRemover](https://www.wartremover.org) -灵活的Scala代码整理工具.


<h2 id="shell">贝壳</h2>

- [i-Code CNES for Shell](https://github.com/lequal/i-CodeCNES) -用于Shell和Fortran（77和90）的开源静态代码分析工具.
- [kmdr](https://kmdr.sh)  -CLI工具，用于从终端学习命令.  kmdr提供了分解的命令，并解释了每个属性.
- [shellcheck](https://www.shellcheck.net) -ShellCheck，一种静态分析工具，可为bash / sh shell脚本提供警告和建议.


<h2 id="swift">迅速</h2>

- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) -用于重新格式化Swift代码的库和命令行格式化工具.
- [SwiftLint](https://realm.github.io/SwiftLint) -实施Swift样式和约定的工具.
- [Tailor](https://github.com/sleekbyte/tailor) ：warning：-用于以Apple的Swift编程语言编写的源代码的静态分析和棉绒工具.


<h2 id="tcl">Tcl</h2>

- [Frink](https://catless.ncl.ac.uk/Programs/Frink) -Tcl格式化和静态检查程序（可以美化该程序，将其最小化，混淆或仅对其进行完整性检查）.
- [Nagelfar](https://sourceforge.net/projects/nagelfar) -Tcl的静态语法检查器.
- [tclchecker](https://github.com/ActiveState/tdk/blob/master/docs/3.0/TDK_3.0_Checker.txt) -静态语法分析模块（作为 [TDK](https://github.com/ActiveState/tdk)).


<h2 id="typescript">打字稿</h2>

- [Codelyzer](http://codelyzer.com) -一组tslint规则，用于Angular 2 TypeScript项目的静态代码分析.
- [tslint-clean-code](https://www.npmjs.com/package/tslint-clean-code) -受《清洁规范》手册启发的一组TSLint规则.
- [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib) -一组由Microsoft维护的Typelin项目的静态代码分析的tslint规则.
- [TypeScript Call Graph](https://github.com/whyboris/TypeScript-Call-Graph) -CLI生成来自TypeScript文件的函数和调用的交互式图形
- [TypeScript ESLint](https://github.com/typescript-eslint/typescript-eslint) -eslint的TypeScript语言扩展.


<h2 id="vbscript">VB脚本</h2>

- [Test Design Studio](http://patterson-consulting.net/tds) ：copyright：-具有静态代码分析功能的完整IDE，用于Micro Focus统一功能测试，基于VBScript的自动化测试.


<h2 id="vim-script">Vim脚本</h2>

- [vint](https://github.com/Kuniwak/vint) -由Python实现的快速且高度可扩展的Vim脚本语言Lint.


## Multiple languages

- [ale](https://github.com/w0rp/ale) -Vim和NeoVim的异步Lint引擎，支持多种语言.
- [Android Studio](https://developer.android.com/studio) -基于IntelliJ IDEA，并捆绑了适用于Android的工具，包括Android Lint.
- [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) :copyright: - Static analysis for C/C++/C#, PHP and Java.
- [Application Inspector](https://www.ptsecurity.com/ww-en/products/ai) ：copyright：-商业静态代码分析，该代码生成用于验证漏洞的漏洞.
- [ApplicationInspector](https://github.com/microsoft/ApplicationInspector) -创建用于功能检测的400多种规则模式的报告（例如，在应用程序中使用加密或版本控制）.
- [AppScan Source](https://www.hcltechsw.com/wps/portal/products/appscan/home) ：copyright：-商业静态代码分析.
- [APPscreener](https://solarappscreener.com) :copyright: - Static code analysis for binary and source code - Java/Scala, PHP, Javascript, C#, PL/SQL, Python, T-SQL, C/C++, ObjectiveC/Swift, Visual Basic 6.0, Ruby, Delphi, ABAP, HTML5 and Solidity.
- [ArchUnit](https://www.archunit.org) -对Java或Kotlin架构进行单元测试.
- [Atom-Beautify](https://atom.io/packages/atom-beautify) - Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom editor.
- [Axivion Bauhaus Suite](https://www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: - Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95.
- [Better Code Hub](https://bettercodehub.com) ：copyright：-Better Code Hub会根据软件质量部门Software Improvement Group制定的10条工程指南来检查GitHub代码库.
- [brakeman](https://brakemanscanner.org) -用于Ruby on Rails应用程序的静态分析安全漏洞扫描程序.
- [cargo-bloat](https://github.com/RazrFalcon/cargo-bloat)  -找出占用可执行文件大部分空间的内容. 支持ELF（Linux，BSD），Mach-O（macOS）和PE（Windows）二进制文件.
- [CAST Highlight](https://www.castsoftware.com/products/highlight) :copyright: - Commercial Static Code Analysis which runs locally, but uploads the results to its cloud for presentation.
- [checkmake](https://github.com/mrtazz/checkmake) -Makefile的Linter / Analyzer.
- [Checkmarx CxSAST](https://www.checkmarx.com/products/static-application-security-testing) ：copyright：-不需要预先编译的商业静态代码分析.
- [ciocheck](https://github.com/ContinuumIO/ciocheck)  -Linter，格式化程序和测试套件帮助器. 作为短绒棉，它是包裹在“ pep8”，“ pydocstyle”，“ flake8”和“ pylint”周围的包装纸.
- [ClassGraph](https://github.com/classgraph/classgraph) -用于查询或可视化类元数据或类相关性的类路径和模块路径扫描器.
- [Clayton](https://www.getclayton.com/)  ：版权所有：-基于AI的Salesforce代码审查. 确保您的开发，执行最佳实践并实时控制您的技术债务.
- [coala](https://coala.io) -用于创建代码分析的语言独立框架-支持 [over 60 languages](https://coala.io/languages) 默认.
- [Cobra](http://spinroot.com/cobra) ：版权所有：-NASA喷气推进实验室的结构源代码分析器.
- [Codacy](https://www.codacy.com) ：copyright：-代码分析可以更快地发布更好的代码.
- [Code Inspector](https://www.code-inspector.com) ：copyright：-支持10多种语言的代码质量和技术债务管理平台.
- [Code Intelligence](https://www.code-intelligence.com) ：copyright：-与CI / CD无关的DevSecOps平台，结合了行业领先的模糊引擎以查找错误并可视化代码覆盖率
- [Codeac](https://www.codeac.io/?ref=awesome-static-analysis)  ：copyright：-自动代码审查工具与GitHub，Bitbucket和GitLab（甚至是自托管）集成. 适用于JavaScript，TypeScript，Python，Ruby，Go，PHP，Java，Docker等.  （免费开源）
- [codeburner](http://groupon.github.io/codeburner) -提供统一的界面来对发现的问题进行排序并采取行动.
- [codechecker](https://codechecker.readthedocs.io/en/latest) -具有Web GUI的Clang静态分析器的缺陷数据库和查看器扩展.
- [CodeFactor](https://codefactor.io) ：copyright：-在GitHub或BitBucket上针对仓库的自动代码分析.
- [CodeFlow](https://www.getcodeflow.com)  ：copyright：-自动化的代码分析工具来处理技术深度. 与Bitbucket和Gitlab集成.  （对于开源项目免费）
- [CodeIt.Right](https://submain.com/products/codeit.right.aspx) ：版权所有：-CodeIt.Right™提供了一种快速，自动化的方法，以确保您的源代码符合（您）预定义的设计和样式指南以及最佳编码实践.
- [CodePatrol](https://cyber-security.claranet.fr/en/codepatrol) ：copyright：-由安全性驱动的自动SAST代码检查，支持15种以上的语言，并包括安全性培训.
- [codeql](https://github.com/github/codeql) -深入的代码分析-带有VSCode插件支持的几种语言的语义查询和数据流.
- [CodeRush](https://www.devexpress.com/products/coderush) ：copyright：-使用Visual Studio 2015及更高版本中的Roslyn引擎的代码创建，调试，导航，重构，分析和可视化工具.
- [CodeScan](https://www.codescan.io/)  ：copyright：-适用于Salesforce开发人员的代码质量和安全性.  CodeScan的代码分析解决方案专为Salesforce平台而设计，可让您全面了解代码的运行状况.
- [CodeScene](https://codescene.com)  ：copyright：-CodeScene是用于软件的高质量可视化工具. 优先考虑技术债务，检测交付风险并衡量组织方面. 完全自动化.
- [Corrode](https://github.com/jameysharp/corrode)  ：warning：-从C到Rust的半自动翻译. 通过显示Rust编译器警告和错误，可以揭示原始实现中的错误. 被C2Rust取代.
- [Coverity](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - Synopsys Coverity supports 20 languages and over 70 frameworks including Ruby on rails, Scala, PHP, Python, JavaScript, TypeScript, Java, Fortran, C, C++, C#, VB.NET.
- [cqc](https://github.com/xcatliu/cqc) -检查js，jsx，vue，css，less，scss，sass和styl文件的代码质量.
- [dawnscanner](https://github.com/thesp0nge/dawnscanner)  -用于ruby编写的Web应用程序的静态分析安全扫描程序. 它支持Sinatra，Padrino和Ruby on Rails框架.
- [DeepCode](https://www.deepcode.ai)  ：copyright：-DeepCode基于AI查找错误，安全漏洞，性能和API问题.  DeepCode的分析速度使我们可以实时分析您的代码，并在您单击IDE中的“保存”按钮时提供结果. 支持的语言是Java，C / C ++，JavaScript，Python和TypeScript. 与GitHub，BitBucket和Gitlab的集成.
- [DeepSource](https://deepsource.io)  ：copyright：-深入的静态分析，以发现错误风险，安全性，反模式，性能，文档和样式等垂直方面的问题. 与GitHub，GitLab和Bitbucket的本地集成. 假阳性率低于5％.
- [Depends](https://github.com/multilang-depends/depends) -分析Java，C / C ++，Ruby的代码元素的全面依赖关系.
- [DevSkim](https://github.com/microsoft/devskim) - Regex-based static analysis tool for Visual Studio, VS Code, and Sublime Text - C/C++, C#, PHP, ASP, Python, Ruby, Java, and others.
- [Embold](https://embold.io) :copyright: - Intelligent software analytics platform that identifies design issues, code issues, duplication and metrics. Supports Java, C, C++, C#, JavaScript, TypeScript, Python, Go, Kotlin and more.
- [ESLint](https://github.com/eslint/eslint) -遵循ECMAScript标准的JS可扩展短绒.
- [exakat](https://www.exakat.io) -用于PHP的自动代码审查引擎.
- [Find Security Bugs](https://find-sec-bugs.github.io)  -SpotBugs插件，用于Java Web应用程序和Android应用程序的安全审核.  （还与Kotlin，Groovy和Scala项目一起工作）
- [flake8](https://github.com/PyCQA/flake8) -围绕pyflakes，pycodestyle和mccabe的包装器.
- [Fortify](https://software.microfocus.com/en-us/products/static-code-analysis-sast/overview) :copyright: - A commercial static analysis platform that supports the scanning of C/C++, C#, VB.NET, VB6, ABAP/BSP, ActionScript, Apex, ASP.NET, Classic ASP, VB Script, Cobol, ColdFusion, HTML, Java, JS, JSP, MXML/Flex, Objective-C, PHP, PL/SQL, T-SQL, Python (2.6, 2.7), Ruby (1.9.3), Swift, Scala, VB, and XML.
- [Go Meta Linter](https://github.com/alecthomas/gometalinter)  ：warning：-同时运行Go lint工具并标准化其输出. 将`golangci-lint`用于新项目.
- [Goodcheck](https://sider.github.io/goodcheck) -基于Regexp的可定制短绒.
- [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) -同时运行许多linter，并将其输出标准化为报告.
- [graudit](http://www.justanotherhacker.com) -Grep粗略审核-源代码审核工具.
- [Hopper](https://github.com/cuplv/hopper) ：warning：-用scala编写的针对JVM上运行的语言的静态分析工具.
- [Hound CI](https://houndci.com)  -在GitHub拉取请求中评论样式违规. 支持Coffeescript，Go，HAML，JavaScript，Ruby，SCSS和Swift.
- [iblessing](https://www.kitploit.com/2020/08/iblessing-ios-security-exploiting.html)  -iblessing是iOS安全利用工具包. 它可以用于逆向工程，二进制分析和漏洞挖掘.
- [imhotep](https://github.com/justinabrahms/imhotep) -评论进入您的存储库的提交，并检查语法错误和常规的掉毛警告.
- [include-gardener](https://github.com/feddischson/include_gardener) - A multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
- [Infer](https://fbinfer.com) -用于Java，C和Objective-C的静态分析器
- [InsiderSec](https://insidersec.io) - A open source Static Application Security Testing tool (SAST) written in GoLang for Java (Maven and Android), Kotlin (Android), Swift (iOS), .NET Full Framework, C# and Javascript (Node.js).
- [Kiuwan](https://www.kiuwan.com/code-security-sast) :copyright: - Identify and remediate cyber threats in a blazingly fast, collaborative environment, with seamless integration in your SDLC. Python, C\C++, Java, C#, PHP and more.
- [Klocwork](https://www.perforce.com/products/klocwork) :copyright: - Quality and Security Static analysis for C/C++, Java and C#.
- [LGTM.com](https://lgtm.com)  ：copyright：-针对GitHub和Bitbucket的深入代码分析，以发现安全漏洞和关键代码质量问题（使用Semmle QL）. 自动查看拉取请求的代码； 免费用于公共存储库.
- [Lumnify](https://lumnify.com) ：copyright：-针对数千个项目进行基准测试，并分析结构质量代码，重点放在可维护性上.
- [multilint](https://github.com/adamchainz/multilint) -在“ flake8”，“ isort”和“ modernize”周围的包装器.
- [Nitpick CI](https://nitpick-ci.com) ：copyright：-自动化PHP代码审查.
- [njsscan](https://opensecurity.in) -静态应用程序测试（SAST）工具，可以使用来自libsast的简单模式匹配器和可识别语法的语义代码模式搜索工具semgrep在node.js应用程序中找到不安全的代码模式.
- [NodeJSScan](https://opensecurity.in) -NodeJsScan是用于Node.js应用程序的静态安全代码扫描程序.
- [Nu Html Checker](https://validator.github.io/validator/) -帮助您在HTML / CSS / SVG中发现问题
- [oclint](http://oclint.org) -静态源代码分析工具，可提高C，C ++和Objective-C的质量并减少缺陷.
- [ocular](https://www.shiftleft.io/ocular/)  ：copyright：-使代码审核员和安全团队可以交互地调查其独特的代码库，以发现传统SAST无法解决的业务逻辑缺陷和技术漏洞. 这是通过使分析师能够编写自己的自定义查询来完成的. 可以找到硬编码的机密，身份验证问题以及恶意代码，例如rootkit和后门程序.
- [Oversecured](https://oversecured.com)  ：copyright：-一个移动应用程序漏洞扫描程序，专为安全研究人员和漏洞赏金黑客使用. 它还允许将集成到企业的DevOps流程中.
- [pfff](https://github.com/facebookarchive/pfff/wiki/Main) ：warning：-Facebook用于多种语言的代码分析，可视化或保留样式源转换的工具.
- [PMD](https://pmd.github.io) -Java，Salesforce Apex，Javascript，PLSQL，XML，XSL等的源代码分析器.
- [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer) -Web组件的静态分析框架.
- [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) -FreeBSD和DragonFlyBSD端口目录的验证程序.
- [pre-commit](https://pre-commit.com) -用于管理和维护多语言预提交挂钩的框架.
- [Prettier](https://prettier.io) -固执己见的代码格式化程序.
- [Pronto](https://github.com/prontolabs/pronto)  -快速自动代码审查您的更改. 支持40多种语言的跑步者，包括Clang，Elixir，JavaScript，PHP，Ruby等.
- [prospector](https://github.com/PyCQA/prospector) -在`pylint`，`pep8`，`mccabe`等周围包装.
- [PT.PM](https://github.com/PositiveTechnologies/PT.PM) :warning: - An engine for searching patterns in the source code, based on Unified AST or UST. At present time C#, Java, PHP, PL/SQL, T-SQL, and JavaScript are supported. Patterns can be described within the code or using a DSL.
- [PVS-Studio](https://www.viva64.com/en/pvs-studio) ：版权：-A（[conditionally free](https://www.viva64.com/en/b/0614/) for FOSS and individual developers) static analysis of C, C++, C# and Java code. For advertising purposes [you can propose a large FOSS project for analysis by PVS employees](https://github.com/viva64/pvs-studio-check-list) . 支持CWE映射，MISRA和CERT编码标准.
- [pylama](https://pylama.readthedocs.io/en/latest/)  -适用于Python和JavaScript的代码审核工具. 包装pycodestyle，pydocstyle，PyFlakes，Mccabe，Pylint等
- [quality](https://github.com/apiology/quality) -使用社区工具对代码进行质量检查，并确保您的代码不会随着时间的推移而恶化.
- [Qualys Container Security](https://www.qualys.com/apps/container-security) ：copyright：-容器本机应用程序保护，以提供对容器化应用程序的可见性和控制.
- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode)  ：警告：-自动代码审查和修复. 它可以帮助您跟踪软件项目中的问题和指标，并且可以轻松扩展以支持新型分析.
- [Refactoring Essentials](https://marketplace.visualstudio.com/items?itemName=SharpDevelopTeam.RefactoringEssentialsforVisualStudio) - The free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers.
- [relint](https://github.com/codingjoe/relint) -静态文件linter，允许您使用正则表达式（RegEx）编写自定义规则.
- [ReSharper](https://www.jetbrains.com/resharper) :copyright: - Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies.
- [Reshift](https://www.reshiftsecurity.com) ：copyright：-用于检测和管理Java安全漏洞的源代码分析工具.
- [Reviewdog](https://github.com/haya14busa/reviewdog) -一种在任何代码托管服务中发布来自任何linter的评论注释的工具.
- [RIPS](https://www.ripstech.com) ：copyright：-用于PHP脚本中漏洞的静态源代码分析器.
- [Rome](https://rome.tools/) -罗马是一个linter，编译器，捆绑器和 [more](https://rome.tools/#development-status) 适用于JavaScript，TypeScript，JSON，HTML，Markdown和CSS.
- [Roslyn Analyzers](https://github.com/dotnet/roslyn-analyzers) -基于Roslyn的FxCop分析仪实施.
- [Roslyn Security Guard](https://security-code-scan.github.io) -该项目侧重于识别潜在漏洞，例如SQL注入，跨站点脚本（XSS），CSRF，加密漏洞，硬编码密码等.
- [Scrutinizer](https://scrutinizer-ci.com) ：copyright：-可以与GitHub集成的专有代码质量检查器.
- [Security Code Scan](https://security-code-scan.github.io) - Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc. Integrates into Visual Studio 2015 and newer. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
- [Semgrep](https://semgrep.live)  -针对多种语言的免费开放源代码轻量级静态分析. 使用看起来像源代码的模式查找和阻止错误变体.
- [Semmle QL and LGTM](https://semmle.com)  ：copyright：-使用对源代码的查询来查找安全漏洞，变体和关键代码质量问题. 自动检查PR代码； 对于公共GitHub / Bitbucket回购免费： [LGTM.com](https://LGTM.com).
- [SensioLabs Insight](https://insight.sensiolabs.com) ：copyright：-检测安全风险，查找错误并为PHP项目提供可操作的指标.
- [ShiftLeft](https://www.shiftleft.io)  ：copyright：-在生产之前确定代码库特有的漏洞. 利用代码属性图（CPG）在单个图图中同时运行其分析. 自动发现开发人员中的业务逻辑缺陷，例如硬编码的机密和逻辑炸弹
- [ShiftLeft Scan](https://slscan.io)  -Scan是一个免费的开源DevSecOps平台，用于检测源代码和依赖项中的安全性问题. 它支持多种语言和CI / CD管道.
- [shipshape](https://github.com/google/shipshape) ：warning：-静态程序分析平台，允许自定义分析器通过通用接口插入.
- [Sider](https://sider.review) :copyright: - An automated code reviewing tool. Improving developers' productivity.
- [SmartDec Scanner](https://smartdecscanner.com) :copyright: - SAST tool which is capable of identifying vulnerabilities and undocumented features. The analyzer scans the source code and executables without debug info (i.e. binaries). Supports: Java/Scala/Kotlin, PHP, C#, JavaScript, TypeScript, VBScript, HTML5, Python, Perl, C/C++, Objective-C/Swift, PL/SQL, T-SQL, ABAP, 1C, Apex, Go, Ruby, Groovy, Delphi, VBA, Visual Basic 6, Solidity, Vyper, COBOL.
- [Snyk](https://snyk.io) ：copyright：-漏洞扫描程序，用于node.js应用程序的依赖项（对于开源项目免费）.
- [SonarCloud](https://sonarcloud.io)  ：copyright：-基于多语言云的静态代码分析. 历史，趋势，安全热点，请求请求分析等. 免费开源.
- [SonarLint for Visual Studio](https://vs.sonarlint.org) -SonarLint是Visual Studio 2015和2017的扩展，可为开发人员提供实时反馈，以反馈有关.NET代码中注入的新错误和质量问题.
- [SonarQube](http://www.sonarqube.org) -SonarQube是管理代码质量的开放平台.
- [Sonatype](https://www.sonatype.com) ：copyright：-报告常见依赖项中的已知漏洞，并建议更新软件包以最大程度地减少重大更改
- [SourceMeter](https://www.sourcemeter.com/) :copyright: - Static Code Analysis for C/C++, Java, C#, Python, and RPG III and RPG IV versions (including free-form).
- [Spectral](https://stoplight.io/open-source/spectral) -灵活的JSON / YAML linter，不支持OpenAPI v2 / v3和AsyncAPI v2.
- [standard](http://standardjs.com) -一个npm模块，用于检查Javascript Styleguide问题.
- [Super-Linter](https://github.com/github/super-linter) -结合了多个linter，以作为GitHub Action安装.
- [Synopsys](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - A commercial static analysis platform that allows for scanning of multiple languages (C/C++, Android, C#, Java, JS, PHP, Python, Node.JS, Ruby, Fortran, and Swift).
- [Teamscale](http://www.teamscale.com)  ：copyright：-支持超过25种语言并直接集成IDE的静态和动态分析工具. 可应要求免费托管开源项目. 提供免费的学术许可证.
- [tfsec](https://github.com/tfsec/tfsec)  -Terraform静态分析工具，可通过在构建时检查云配置错误来防止潜在的安全问题，并直接与HCL解析器集成以获得更好的结果. 检查是否违反了AWS，Azure和GCP安全最佳实践建议.
- [todocheck](https://github.com/preslavmihaylov/todocheck) -Linter用于将带注释的TODO与您的问题跟踪器集成
- [TscanCode](https://github.com/Tencent/TscanCode) - A fast and accurate static analysis solution for C/C++, C#, Lua codes provided by Tencent. Using GPLv3 license.
- [Twiggy](https://rustwasm.github.io/twiggy)  -分析二进制文件的调用图以分析代码大小. 目标是缩小wasm二进制文件大小.
- [Undebt](https://github.com/Yelp/undebt) -基于语言的工具，可基于简单的模式定义进行大规模，自动，可编程的重构.
- [Understand](https://www.scitools.com) ：copyright：-代码可视化工具，可为Ada，VHDL等提供代码分析，标准测试，指标，图形，依赖性分析等功能.
- [Unibeautify](https://unibeautify.com)  -带有GitHub应用程序的通用代码美化器. 支持HTML，CSS，JavaScript，TypeScript，JSX，Vue，C ++，Go，Objective-C，Java，Python，PHP，GraphQL，Markdown等.
- [Upsource](https://www.jetbrains.com/upsource) ：copyright：-具有Java，PHP，JavaScript和Kotlin的静态代码分析和代码感知导航的代码审查工具.
- [Veracode](http://www.veracode.com/products/static-analysis-sast/static-code-analysis)  ：copyright：-在不需要源代码的情况下查找二进制文件和字节码中的缺陷. 支持所有主要的编程语言：Java，.NET，JavaScript，Swift，Objective-C，C，C ++等.
- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  -用于从静态代码分析中解析报告文件的Java库. 由许多Jenkins，Maven和Gradle插件使用.
- [WALA](https://github.com/wala/WALA) -Java字节码和相关语言以及JavaScript的静态分析功能.
- [WhiteHat Application Security Platform](https://www.whitehatsec.com/platform/static-application-security-testing) ：copyright：-WhiteHat Scout（针对开发人员）与WhiteHat Sentinel Source（针对运营）相结合，支持WhiteHat Top 40和OWASP Top 10.
- [Wotan](https://github.com/fimbullinter/wotan) -可插拔的TypeScript和JavaScript linter.
- [Xanitizer](https://xanitizer.com)  ：copyright：-Xanitizer发现Web应用程序中的安全漏洞. 它支持Java，Scala，JavaScript和TypeScript.
- [XCode](https://developer.apple.com/xcode) ：copyright：-XCode为 [Clang's](http://clang-analyzer.llvm.org/xcode.html) 静态代码分析器（C / C ++，Obj-C）.
- [yamllint](https://yamllint.readthedocs.io) -检查YAML文件的语法有效性，键重复和外观问题，例如行长，尾随空格和缩进.


## Other



<h2 id="binary">二进制文件</h2>

- [binbloom](https://github.com/quarkslab/binbloom)  -该项目的目的是分析原始二进制固件并自动确定其某些功能. 该工具基本上与所有体系结构兼容，只是对其进行简单的统计.
加载地址：binbloom可以解析原始二进制固件并确定其加载地址. 字节序：binbloom可以使用启发式方法来确定固件的字节序.  UDS数据库：binbloom可以解析原始二进制固件，并检查其是否包含包含UDS命令ID的数组.
- [BinSkim](https://github.com/Microsoft/binskim) -二进制静态分析工具，可为Windows可移植可执行文件提供安全性和正确性结果.
- [Black Duck](https://www.blackducksoftware.com) ：copyright：-分析源代码和二进制文件以获取可重用代码，必要许可证和潜在安全方面的工具.
- [bloaty](https://github.com/google/bloaty)  -想知道是什么使您的二进制文件变大了吗？  Bloaty McBloatface将为您显示二进制文件的大小配置文件，以便您了解内部文件占用了什么空间.  Bloaty对二进制文件进行了深入分析. 通过使用自定义的ELF，DWARF和Mach-O解析器，Bloaty旨在将二进制文件的每个字节准确地归因于产生它的符号或编译单元. 它甚至会反汇编二进制文件以查找对匿名数据的引用.  F
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) -cwe_checker在二进制可执行文件中找到易受攻击的模式.
- [Ghidra](https://ghidra-sre.org) -国家安全局研究局开发的软件逆向工程（SRE）工具套件，用于支持网络安全使命
- [IDA Free](https://www.hex-rays.com/products/ida/support/download_freeware) ：copyright：-二进制代码分析工具.
- [Jakstab](https://github.com/jkinder/jakstab) -Jakstab是基于抽象解释的集成反汇编和静态分析框架，用于设计可执行文件的分析并恢复可靠的控制流程图.
- [JEB Decompiler](https://www.pnfsoftware.com/)  ：copyright：-反编译和调试二进制代码. 分解并分析文档文件.  Android Dalvik，MIPS，ARM，Intel x86，Java，WebAssembly和以太坊反编译器.
- [Manalyze](https://github.com/JusticeRage/Manalyze) -静态分析器，用于检查可移植可执行文件中是否包含恶意内容.
- [Nauz File Detector](https://github.com/horsicq/Nauz-File-Detector) -Windows，Linux和MacOS的静态链接器/编译器/工具检测器.
- [zydis](https://zydis.re) -快速，轻量的x86 / x86-64反汇编程序库


<h2 id="css">CSS / SASS / SCSS</h2>

- [CSS Stats](https://cssstats.com) -样式表上可能有趣的统计信息.
- [CSScomb](https://github.com/csscomb/csscomb.js)  -CSS的编码样式格式化程序. 支持自己的配置，使样式表美观且一致.
- [CSSLint](http://csslint.net) -进行基本语法检查并找到有问题的模式或效率低下的迹象.
- [GraphMyCSS.com](https://graphmycss.com) -CSS特异性图生成器.
- [Parker](https://github.com/katiefenn/parker) -样式表分析工具.
- [PostCSS](https://postcss.org)  -使用JS插件转换样式的工具. 这些插件可以使您的CSS更加整洁，支持变量和混合，可以转换将来的CSS语法，内联图像等等.
- [Project Wallace CSS Analyzer](https://www.projectwallace.com) -CSS的分析，属于 [Project Wallace](https://www.projectwallace.com).
- [sass-lint](https://github.com/sasstools/sass-lint) ：warning：-用于sass和scss语法的仅节点Sass linter.
- [scsslint](https://github.com/brigade/scss-lint) ：warning：-Linter用于SCSS文件.
- [Specificity Graph](https://jonassebastianohlsson.com/specificity-graph) -CSS特异性图生成器.
- [Stylelint](http://stylelint.io) -用于SCSS / CSS文件的Linter.


<h2 id="configfile">配置文件</h2>

- [dotenv-linter](https://dotenv-linter.readthedocs.io/en/latest) -像魅力一样整理dotenv文件.
- [gixy](https://github.com/yandex/gixy)  -分析Nginx配置的工具. 主要目标是防止配置错误并自动进行缺陷检测.


<h2 id="configmanagement">配置管理</h2>

- [ansible-lint](https://docs.ansible.com/ansible-lint) -检查剧本中可能会改进的做法和行为.
- [AWS CloudFormation Guard](https://github.com/aws-cloudformation/cloudformation-guard) -对照代码策略规则检查本地CloudFormation模板，并根据现有模板生成规则.
- [cfn-lint](https://github.com/awslabs/cfn-python-lint) -AWS Labs CloudFormation linter.
- [cfn_nag](https://github.com/stelligent/cfn_nag) -适用于AWS CloudFormation模板的模板.
- [checkov](https://www.checkov.io) -用于Terraform文件的静态分析工具（tf&gt; = v0.12），可防止在构建时云配置错误.
- [cookstyle](https://docs.chef.io/cookstyle.html) -Cookstyle是基于RuboCop Ruby linting工具用于厨师食谱的整理工具.
- [foodcritic](http://www.foodcritic.io) -用于检查厨师食谱中常见问题的皮棉工具.
- [Puppet Lint](https://github.com/rodjek/puppet-lint) -检查您的人偶清单是否符合样式指南.
- [terraform-compliance](https://terraform-compliance.com) -针对Terraform的轻量级，遵循合规性和安全性的BDD测试框架.
- [terrascan](https://github.com/cesar-rodriguez/terrascan) -收集用于Terraform模板的静态代码分析的安全性和最佳实践测试.
- [tflint](https://github.com/wata727/tflint) -Terraform linter，用于检测“ terraform plan”无法检测到的错误.


<h2 id="container">货柜</h2>

- [anchore](https://anchore.io) -发现，分析和验证容器映像.
- [clair](https://github.com/coreos/clair) -容器的漏洞静态分析.
- [collector](https://github.com/banyanops/collector) -在容器内运行任意脚本，并收集有用的信息.
- [dagda](https://github.com/eliasgranderubio/dagda) -对Docker映像/容器中的已知漏洞执行静态分析.
- [Docker Label Inspector](https://github.com/garethr/docker-label-inspector) -整理和验证Dockerfile标签.
- [Haskell Dockerfile Linter](https://github.com/lukasmartinelli/hadolint) -更加智能的Dockerfile文件管理器，可帮助您构建最佳实践的Docker映像.
- [kube-score](https://kube-score.com) -Kubernetes对象定义的静态代码分析.
- [KubeLinter](https://github.com/stackrox/kube-linter) - KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts to ensure the applications represented in them adhere to best practices.
- [kubeval](https://kubeval.instrumenta.dev) -验证您的Kubernetes配置文件并支持多个Kubernetes版本.


<h2 id="ci">持续集成</h2>

- [Code Climate](https://codeclimate.com) -面向所有人的开放和可扩展的静态分析平台.
- [PullRequest](https://www.pullrequest.com)  ：copyright：-代码审查作为具有内置静态分析的服务. 通过一流的自动化技术支持的专家工程师的质量代码审查，提高速度并减少技术债务.


<h2 id="deno">天野</h2>

- [deno_lint](https://github.com/denoland/deno_lint) -Deno的官方短毛猫.


<h2 id="gherkin">小黄瓜</h2>

- [gherkin-lint](https://github.com/vsiakka/gherkin-lint) -用Java语言编写的小黄瓜语法的短毛猫.


<h2 id="html">的HTML</h2>

- [Bootlint](https://github.com/twbs/bootlint) -用于Bootstrap项目的HTML linter.
- [grunt-bootlint](https://github.com/twbs/grunt-bootlint) -用于的Grunt包装器 [Bootlint](https://github.com/twbs/bootlint)，用于Bootstrap项目的HTML linter.
- [gulp-bootlint](https://github.com/tschortsch/gulp-bootlint) -用于的大包装 [Bootlint](https://github.com/twbs/bootlint)，用于Bootstrap项目的HTML linter.
- [HTML Inspector](https://github.com/philipwalton/html-inspector) ：警告：-HTML Inspector是一种代码质量工具，可帮助您和您的团队编写更好的标记.
- [HTML Tidy](http://www.html-tidy.org) -通过修复标记错误并将旧代码升级为现代标准来纠正和清除HTML和XML文档.
- [HTMLHint](https://htmlhint.com) -用于HTML的静态代码分析工具.


<h2 id="latex">胶乳</h2>

- [ChkTeX](http://www.nongnu.org/chktex) -适用于LaTex的短绒棉布，可捕获LaTeX监督的某些印刷错误.
- [lacheck](https://www.ctan.org/pkg/lacheck) -查找LaTeX文档中常见错误的工具.
- [TeXLab](https://texlab.netlify.app) -TeX / LaTeX的语言服务器协议实现，包括棉绒功能.


<h2 id="markdown">降价促销</h2>

- [markdownlint](https://github.com/DavidAnson/markdownlint) -用于Markdown / CommonMark文件的基于Node.js的样式检查器和lint工具.
- [mdl](https://github.com/mivok/markdownlint) -检查Markdown文件和标志样式问题的工具.
- [remark-lint](https://remark.js.org) -用JavaScript编写的可插入Markdown代码样式的linter.


<h2 id="mobile">移动</h2>

- [Android Lint](http://tools.android.com/tips/lint) -在Android项目上运行静态分析.
- [android-lint-summary](https://passy.github.io/android-lint-summary) -将多个项目的棉绒错误合并为一个输出，立即检查多个子项目的棉绒结果.
- [FlowDroid](https://github.com/secure-software-engineering/FlowDroid) -适用于Android应用程序的静态污点分析工具.
- [paprika](https://github.com/GeoffreyHecht/paprika) -一个工具包，用于检测已分析的Android应用程序中的某些代码异味.
- [qark](https://github.com/linkedin/qark) -查找多个与安全相关的Android应用程序漏洞的工具.
- [redex](https://fbredex.com)  -Redex提供了一个用于读取，写入和分析.dex文件的框架，以及使用该框架来改进字节码的一组优化过程. 由Redex优化的APK应该更小，更快.


<h2 id="package">配套</h2>

- [lintian](https://lintian.debian.org) -用于Debian软件包的静态分析工具.
- [rpmlint](https://github.com/rpm-software-management/rpmlint) -用于检查rpm包中常见错误的工具.


<h2 id="protobuf">协议缓冲区</h2>

- [protolint](https://github.com/yoheimuta/protolint) -可插入的linter和fixer，用于实施协议缓冲区样式和约定.


<h2 id="security">安全/ SAST</h2>

- [Attackflow Extension](https://www.attackflow.com/Extension) ：copyright：-用于Visual Studio的Attackflow插件，它使开发人员无需任何先验知识就可以在源代码中实时发现关键的安全错误.
- [Gitleaks](https://github.com/zricethezav/gitleaks) -一种SAST工具，用于检测git repos中的硬编码机密，例如密码，api密钥和令牌.


<h2 id="smart-contracts">智能合约</h2>

- [mythril](https://github.com/ConsenSys/mythril) -包含电池的符号执行框架可用于自动查找和利用智能合约中的漏洞.
- [MythX](https://mythx.io)  ：copyright：-MythX是一个易于使用的分析平台，它集成了模糊分析，符号执行和静态分析等多种分析方法，可以高精度地查找漏洞. 它可以与Remix或VSCode之类的工具链集成，也可以从命令行调用.
- [slither](https://github.com/trailofbits/slither) -静态分析框架，运行一套漏洞检测器，打印有关合同详细信息的可视信息，并提供一个API，可轻松编写自定义分析.
- [solhint](https://protofire.github.io/solhint)  -Solhint是由https://protofire.io创建的开源项目. 其目标是为Solidity代码提供一个整理工具.
- [solium](https://ethlint.readthedocs.io/en/latest) -Solium是可用于识别和修复Solidity智能合约中的样式和安全问题的工具.


<h2 id="support">支持</h2>

- [LibVCS4j](https://github.com/uni-bremen-agst/libvcs4j) -一个Java库，通过为不同的版本控制系统和问题跟踪器提供通用的API，允许现有工具分析软件系统的演变.


<h2 id="template">范本语言</h2>

- [ember-template-lint](https://github.com/ember-template-lint/ember-template-lint) -灰烬的Ember或Handlebars模板.
- [haml-lint](https://github.com/sds/haml-lint) -用于编写干净且一致的HAML的工具.
- [slim-lint](https://github.com/sds/slim-lint) -用于分析Slim模板的可配置工具.


<h2 id="translation">翻译</h2>

- [dennis](https://github.com/willkg/dennis) -一组用于处理PO文件的实用程序，以简化开发并提高质量.


<h2 id="vue">Vue.js</h2>

- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)  -由vls（vue语言服务器）支持的VS Code的Vue工具.  Vetur支持格式化嵌入式HTML，CSS，SCSS，JS，TypeScript等.  Vetur仅具有“整个文档格式化程序”，不能格式化任意范围.


<h2 id="writing">写作</h2>

- [After the Deadline](https://afterthedeadline.com) ：warning：-拼写，样式和语法检查器.
- [alex](https://alexjs.com) -捕捉不敏感，不体贴的文字
- [codespell](https://github.com/codespell-project/codespell) -检查代码中常见的拼写错误.
- [languagetool](https://languagetool.org)  -25种以上语言的样式和语法检查器. 它会发现许多简单的拼写检查器无法检测到的错误.
- [misspell-fixer](https://github.com/vlajos/misspell-fixer) -用于修复源代码中常见拼写错误，错别字的快速工具.
- [Misspelled Words In Context](http://jwilk.net/software/mwic) -拼写检查器，对可能的拼写错误进行分组并在上下文中显示它们.
- [proselint](http://proselint.com) -英文散文短篇小说，着重于写作风格而不是语法.
- [vale](https://errata-ai.gitbook.io/vale) -用于散文的可自定义的，具有语法意识的linter.
- [write-good](https://github.com/btford/write-good) -重点消除“狡猾的单词”的短毛猫.


## More Collections

- [go-tools](https://github.com/dominikh/go-tools) -使用Go代码的工具和库的集合，包括短绒和静态分析
- [Clean code linters](https://github.com/collections/clean-code-linters) -github集合中的linters集合
- [Code Quality Checker Tools For PHP Projects](https://github.com/collections/code-quality-in-php) -github集合中的PHP linters集合
- [linters](https://github.com/mcandre/linters) -静态代码分析简介
- [php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools) -有用的PHP静态分析工具的完整列表
- [Tools for C/C++](https://www.peerlyst.com/posts/a-list-of-static-analysis-tools-for-c-c-peerlyst?utm_source=twitter&utm_medium=social&utm_content=peerlyst_post&utm_campaign=peerlyst_resources) -用于C / C ++的静态分析工具列表
- [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) -用于静态代码分析的工具列表.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Matthias Endler](https://endler.dev) has waived all copyright and related or neighboring rights to this work.
标题图片 [Designed by Freepik](http://www.freepik.com).
