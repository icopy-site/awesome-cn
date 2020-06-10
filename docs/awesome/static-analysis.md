<div class="github-widget" data-repo="analysis-tools-dev/static-analysis"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--  DON'T EDIT THIS FILE DIRECTLY. Edit `data/tools.yml` instead.  -->

![Logo](https://raw.githubusercontent.com/analysis-tools-dev/static-analysis/master/awesome.png)

&gt;静态程序分析是对没有实际执行程序的情况下执行的计算机软件的分析， [Wikipedia](https://en.wikipedia.org/wiki/Static_program_analysis)

 &gt;近年来，作为一名程序员，我要做的最重要的事情是积极地进行静态代码分析.  与我所防止的数百个严重错误相比，更有价值的是关于我查看软件可靠性和代码质量的方式的观念转变.  - [John Carmack (Creator of Doom)](https://www.gamasutra.com/view/news/128836/InDepth_Static_Code_Analysis.php) 

![CI](https://github.com/analysis-tools-dev/static-analysis/workflows/CI/badge.svg)

 这是静态分析工具和代码质量检查器的集合.  拉请求非常欢迎！

 -：版权：代表专有软件.  所有其他工具都是开源的.
-：警告：表示社区不建议将此工具用于
  已经过时或不再维护的新项目.

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
    <li><a href="#coffeescript">CoffeeScript</a></li>
    <li><a href="#crystal">Crystal</a></li>
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
    <li><a href="#kotlin">Kotlin</a></li>
    <li><a href="#lua">Lua</a></li>
    <li><a href="#matlab">MATLAB</a></li>
    <li><a href="#php">PHP</a></li>
    <li><a href="#perl">Perl</a></li>
    <li><a href="#python">Python</a></li>
    <li><a href="#r">R</a></li>
    <li><a href="#rpg">RPG</a></li>
    <li><a href="#ruby">Ruby</a></li>
    <li><a href="#rust">Rust</a></li>
    <li><a href="#sql">SQL</a></li>
    <li><a href="#scala">Scala</a></li>
    <li><a href="#shell">Shell</a></li>
    <li><a href="#solidity">Solidity</a></li>
    <li><a href="#swift">Swift</a></li>
    <li><a href="#tcl">Tcl</a></li>
    <li><a href="#typescript">TypeScript</a></li>
    <li><a href="#vbscript">VBScript</a></li>
    </ul>
</details>





---

## Programming Languages

<h2 id="abap">阿巴普</h2>

- ![stars](https://img.shields.io/github/stars/larshp/abaplint?style=flat-square&color=ccc) [abaplint](https://abaplint.org/) -用TypeScript编写的ABAP的Linter.
- ![stars](https://img.shields.io/github/stars/larshp/abapOpenChecks?style=flat-square&color=ccc) [abapOpenChecks](https://docs.abapopenchecks.org/) -通过新的和可自定义的检查功能增强了SAP Code Inspector.


<h2 id="ada">有</h2>

- [Codepeer](http://www.adacore.com/codepeer) ：copyright：-检测运行时和逻辑错误
- [Polyspace for Ada](https://www.mathworks.com/products/polyspace-ada.html) ：copyright：-提供代码验证，以证明源代码中不存在溢出，零除，越界数组访问以及某些其他运行时错误.
- [SPARK](https://www.adacore.com/about-spark) ：copyright：-Ada的静态分析和形式验证工具集
- [Understand](https://scitools.com/ada-programming-essential/) ：copyright：-IDE为Ada和VHDL提供代码分析，标准测试，指标，图形，依赖性分析等.


<h2 id="asm">部件</h2>

- ![stars](https://img.shields.io/github/stars/StanfordPL/stoke?style=flat-square&color=ccc) [STOKE](http://stoke.stanford.edu/)  -用于x86_64指令集的编程语言不可知随机优化器.  它使用随机搜索来探索所有可能的程序转换的极高维空间


<h2 id="awk"> Awk </h2>

- [gawk --lint](https://www.gnu.org/software/gawk/manual/html_node/Options.html) -警告关于可疑或不可移植到其他awk实现的构造.


<h2 id="c"> C </h2>

- [Astrée](https://www.absint.com/astree/index.htm) ：copyright：-基于C / C ++抽象解释的声音静态分析器，可检测内存，类型和并发缺陷以及MISRA违规.
- [CBMC](http://www.cprover.org/cbmc/) -用于C程序，用户定义的断言，标准断言，若干覆盖率度量分析的有界模型检查器
- [clang-tidy](http://clang.llvm.org/extra/clang-tidy/) -lang静态分析
- ![stars](https://img.shields.io/github/stars/MetricsGrimoire/CMetrics?style=flat-square&color=ccc) [CMetrics](https://github.com/MetricsGrimoire/CMetrics) -测量C文件的大小和复杂性
- [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) ：copyright：-高级，整个程序，深层路径，对C和C ++的静态分析以及易于理解的说明以及代码和路径可视化.
- ![stars](https://img.shields.io/github/stars/danmar/cppcheck?style=flat-square&color=ccc) [cppcheck](http://cppcheck.sourceforge.net/) -C / C ++代码的静态分析
- [CppDepend](https://www.cppdepend.com) ：warning：：copyright：-测量，查询和可视化您的代码，避免意外的问题，技术负担和复杂性.
- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) -遵循Google风格指南的自动C ++检查器
- ![stars](https://img.shields.io/github/stars/dspinellis/cqmetrics?style=flat-square&color=ccc) [cqmetrics](https://github.com/dspinellis/cqmetrics) -C代码的质量指标
- ![stars](https://img.shields.io/github/stars/dspinellis/cscout?style=flat-square&color=ccc) [CScout](https://www.spinellis.gr/cscout/) -C和C预处理程序代码的复杂度和质量指标
- ![stars](https://img.shields.io/github/stars/david-a-wheeler/flawfinder?style=flat-square&color=ccc) [flawfinder](https://www.dwheeler.com/flawfinder/) -发现可能的安全漏洞
- ![stars](https://img.shields.io/github/stars/JossWhittle/FlintPlusPlus?style=flat-square&color=ccc) [flint++](https://github.com/JossWhittle/FlintPlusPlus) -flint的跨平台，零依赖端口，这是Facebook开发和使用的C ++ lint程序.
- [Frama-C](http://frama-c.com/) -完善的C代码静态分析器
- [Helix QAC](https://www.perforce.com/products/helix-qac)  ：copyright：-嵌入式软件的企业级静态分析.  支持MISRA，CERT和AUTOSAR编码标准.
- ![stars](https://img.shields.io/github/stars/nasa-sw-vnv/ikos?style=flat-square&color=ccc) [IKOS](https://github.com/nasa-sw-vnv/ikos) -基于LLVM的C / C ++代码的声音静态分析器
- ![stars](https://img.shields.io/github/stars/feddischson/include_gardener?style=flat-square&color=ccc) [include-gardener](https://github.com/feddischson/include_gardener) - a multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
- [LDRA](https://ldra.com) ：copyright：-一个工具套件，包括对各种标准的静态分析（TBVISION），包括MISRA C＆C ++，JSF ++ AV，CWE，CERT C，CERT C ++和自定义规则.
- ![stars](https://img.shields.io/github/stars/secure-software-engineering/phasar?style=flat-square&color=ccc) [Phasar](https://phasar.org/) -基于LLVM的静态分析框架，带有污点和类型状态分析.
- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) ：copyright：-标识C和C ++嵌入式软件中的运行时错误，并发问题，安全漏洞和其他缺陷.
- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) ：copyright：-提供代码验证，以证明C和C ++源代码中不存在溢出，零除，越界数组访问以及某些其他运行时错误.
- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) -在编译时使用LLVM分析C / C ++代码
- ![stars](https://img.shields.io/github/stars/ravenexp/splint?style=flat-square&color=ccc) [splint](http://splint.org/) - Annotation-assisted static program checker
- ![stars](https://img.shields.io/github/stars/SVF-tools/SVF?style=flat-square&color=ccc) [SVF](http://svf-tools.github.io/SVF/) -静态工具，可对C和C ++程序进行可伸缩且精确的过程间相关性分析.
- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) -Vera ++是用于验证，分析和转换C ++源代码的可编程工具.


<h2 id="csharp">C#</h2>

- [.NET Analyzers](https://github.com/DotNetAnalyzers) -使用.NET编译器平台开发分析器（诊断和代码修复）的组织.
- [Code Analysis Rule Collection](https://carc.codeplex.com/) ：warning：-包含一组基于Microsoft .NET编译器平台“ Roslyn”构建的诊断，代码修复和重构.
- ![stars](https://img.shields.io/github/stars/code-cracker/code-cracker?style=flat-square&color=ccc) [code-cracker](http://code-cracker.github.io/) - An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.
- ![stars](https://img.shields.io/github/stars/DustinCampbell/CSharpEssentials?style=flat-square&color=ccc) [CSharpEssentials](https://github.com/DustinCampbell/CSharpEssentials) - C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features.
- [Designite](http://www.designite-tools.com) ：copyright：-Designite支持检测各种体系结构，设计和实现的气味，计算各种代码质量指标以及趋势分析.
- [Gendarme](https://www.mono-project.com/docs/tools+libraries/tools/gendarme/) -Gendarme检查包含ECMA CIL格式（Mono和.NET）代码的程序和库.
- [NDepend](http://www.ndepend.com/) ：copyright：-测量，查询和可视化您的代码，避免意外的问题，技术负担和复杂性.
- [Roslynator](https://github.com/JosefPihrt/Roslynator/) - A collection of 190+ analyzers and 190+ refactorings for C#, powered by Roslyn.
- ![stars](https://img.shields.io/github/stars/Vannevelj/VSDiagnostics?style=flat-square&color=ccc) [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) -与VS集成的基于Roslyn的静态分析器集合.
- ![stars](https://img.shields.io/github/stars/Wintellect/Wintellect.Analyzers?style=flat-square&color=ccc) [Wintellect.Analyzers](https://github.com/Wintellect/Wintellect.Analyzers) -.NET编译器平台（“ Roslyn”）诊断分析器和代码修复.


<h2 id="cpp"> C ++ </h2>

- [Astrée](https://www.absint.com/astree/index.htm) ：copyright：-基于C / C ++抽象解释的声音静态分析器，可检测内存，类型和并发缺陷以及MISRA违规.
- [CBMC](http://www.cprover.org/cbmc/) -用于C程序，用户定义的断言，标准断言，若干覆盖率度量分析的有界模型检查器
- [clang-tidy](http://clang.llvm.org/extra/clang-tidy/) -lang静态分析
- ![stars](https://img.shields.io/github/stars/MetricsGrimoire/CMetrics?style=flat-square&color=ccc) [CMetrics](https://github.com/MetricsGrimoire/CMetrics) -测量C文件的大小和复杂性
- [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) ：copyright：-高级，整个程序，深层路径，对C和C ++的静态分析以及易于理解的说明以及代码和路径可视化.
- ![stars](https://img.shields.io/github/stars/danmar/cppcheck?style=flat-square&color=ccc) [cppcheck](http://cppcheck.sourceforge.net/) -C / C ++代码的静态分析
- [CppDepend](https://www.cppdepend.com) ：warning：：copyright：-测量，查询和可视化您的代码，避免意外的问题，技术负担和复杂性.
- [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) -遵循Google风格指南的自动C ++检查器
- ![stars](https://img.shields.io/github/stars/dspinellis/cqmetrics?style=flat-square&color=ccc) [cqmetrics](https://github.com/dspinellis/cqmetrics) -C代码的质量指标
- ![stars](https://img.shields.io/github/stars/dspinellis/cscout?style=flat-square&color=ccc) [CScout](https://www.spinellis.gr/cscout/) -C和C预处理程序代码的复杂度和质量指标
- ![stars](https://img.shields.io/github/stars/david-a-wheeler/flawfinder?style=flat-square&color=ccc) [flawfinder](https://www.dwheeler.com/flawfinder/) -发现可能的安全漏洞
- ![stars](https://img.shields.io/github/stars/JossWhittle/FlintPlusPlus?style=flat-square&color=ccc) [flint++](https://github.com/JossWhittle/FlintPlusPlus) -flint的跨平台，零依赖端口，这是Facebook开发和使用的C ++ lint程序.
- [Frama-C](http://frama-c.com/) -完善的C代码静态分析器
- [Helix QAC](https://www.perforce.com/products/helix-qac)  ：copyright：-嵌入式软件的企业级静态分析.  支持MISRA，CERT和AUTOSAR编码标准.
- ![stars](https://img.shields.io/github/stars/nasa-sw-vnv/ikos?style=flat-square&color=ccc) [IKOS](https://github.com/nasa-sw-vnv/ikos) -基于LLVM的C / C ++代码的声音静态分析器
- ![stars](https://img.shields.io/github/stars/feddischson/include_gardener?style=flat-square&color=ccc) [include-gardener](https://github.com/feddischson/include_gardener) - a multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
- [LDRA](https://ldra.com) ：copyright：-一个工具套件，包括对各种标准的静态分析（TBVISION），包括MISRA C＆C ++，JSF ++ AV，CWE，CERT C，CERT C ++和自定义规则.
- ![stars](https://img.shields.io/github/stars/secure-software-engineering/phasar?style=flat-square&color=ccc) [Phasar](https://phasar.org/) -基于LLVM的静态分析框架，带有污点和类型状态分析.
- [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) ：copyright：-标识C和C ++嵌入式软件中的运行时错误，并发问题，安全漏洞和其他缺陷.
- [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) ：copyright：-提供代码验证，以证明C和C ++源代码中不存在溢出，零除，越界数组访问以及某些其他运行时错误.
- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) -在编译时使用LLVM分析C / C ++代码
- ![stars](https://img.shields.io/github/stars/ravenexp/splint?style=flat-square&color=ccc) [splint](http://splint.org/) - Annotation-assisted static program checker
- ![stars](https://img.shields.io/github/stars/SVF-tools/SVF?style=flat-square&color=ccc) [SVF](http://svf-tools.github.io/SVF/) -静态工具，可对C和C ++程序进行可伸缩且精确的过程间相关性分析.
- [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) -Vera ++是用于验证，分析和转换C ++源代码的可编程工具.


<h2 id="coffeescript"> CoffeeScript </h2>

- ![stars](https://img.shields.io/github/stars/clutchski/coffeelint?style=flat-square&color=ccc) [coffeelint](http://www.coffeelint.org/) -样式检查器，有助于使CoffeeScript代码保持干净和一致.


<h2 id="crystal">水晶</h2>

- ![stars](https://img.shields.io/github/stars/veelenga/ameba?style=flat-square&color=ccc) [ameba](https://crystal-ameba.github.io/) -用于Crystal的静态代码分析工具
- ![stars](https://img.shields.io/github/stars/crystal-lang/crystal?style=flat-square&color=ccc) [crystal](https://crystal-lang.org/) -Crystal编译器具有内置的棉绒功能.


<h2 id="delphi">德尔菲</h2>

- [Fix Insight](https://www.tmssoftware.com/site/fixinsight.asp)  ：copyright：-一个免费的IDE插件，用于静态代码分析.  _Pro_版本包含用于自动化目的的命令行工具.
- [Pascal Analyzer](https://peganza.com/products_pal.html)  ：copyright：-具有大量报告的静态代码分析工具.  提供免费的_Lite_版本，报告数量有限.
- [Pascal Expert](https://peganza.com/products_pex.html)  ：copyright：-用于代码分析的IDE插件.  包括Pascal Analyzer报告功能的一部分，并且可用于Delphi 2007及更高版本.


<h2 id="dlang">德朗</h2>

- ![stars](https://img.shields.io/github/stars/dlang-community/D-Scanner?style=flat-square&color=ccc) [D-scanner](https://github.com/dlang-community/D-Scanner) -D-Scanner是用于分析D源代码的工具


<h2 id="elixir">长生不老药</h2>

- ![stars](https://img.shields.io/github/stars/rrrene/credo?style=flat-square&color=ccc) [credo](http://credo-ci.org/) -静态代码分析工具，专注于代码一致性和教学.
- ![stars](https://img.shields.io/github/stars/nccgroup/sobelow?style=flat-square&color=ccc) [sobelow](https://github.com/nccgroup/sobelow) -Phoenix框架的安全性静态分析


<h2 id="elm">榆树</h2>

- ![stars](https://img.shields.io/github/stars/stil4m/elm-analyse?style=flat-square&color=ccc) [elm-analyse](https://stil4m.github.io/elm-analyse/) -一种工具，可让您分析Elm代码，识别缺陷并应用最佳实践.


<h2 id="erlang">Erlang</h2>

- ![stars](https://img.shields.io/github/stars/inaka/elvis?style=flat-square&color=ccc) [elvis](https://github.com/inaka/elvis) -Erlang风格审稿人
- ![stars](https://img.shields.io/github/stars/okeuday/pest?style=flat-square&color=ccc) [Primitive Erlang Security Tool (PEST)](https://github.com/okeuday/pest) -一种对Erlang源代码进行基本扫描并报告可能导致Erlang源代码不安全的函数调用的工具.


<h2 id="fsharp">F#</h2>

- ![stars](https://img.shields.io/github/stars/fsprojects/FSharpLint?style=flat-square&color=ccc) [FSharpLint](http://fsprojects.github.io/FSharpLint/) -棉绒工具#


<h2 id="fortran"> Fortran </h2>

- ![stars](https://img.shields.io/github/stars/lequal/i-CodeCNES?style=flat-square&color=ccc) [i-Code CNES for Fortran](https://github.com/lequal/i-CodeCNES) -用于Fortran 77，Fortran 90和Shell的开源静态代码分析工具.


<h2 id="go">走</h2>

- [aligncheck](https://gitlab.com/opennota/check) -查找效率低下的打包结构.
- ![stars](https://img.shields.io/github/stars/timakin/bodyclose?style=flat-square&color=ccc) [bodyclose](https://github.com/timakin/bodyclose) -检查HTTP响应主体是否关闭.
- ![stars](https://img.shields.io/github/stars/tsenart/deadcode?style=flat-square&color=ccc) [deadcode](https://github.com/tsenart/deadcode) -查找未使用的代码.
- ![stars](https://img.shields.io/github/stars/nickng/dingo-hunter?style=flat-square&color=ccc) [dingo-hunter](https://github.com/nickng/dingo-hunter) -用于在Go中查找死锁的静态分析器.
- ![stars](https://img.shields.io/github/stars/alexkohler/dogsled?style=flat-square&color=ccc) [dogsled](https://github.com/alexkohler/dogsled) -查找带有太多空白标识符的分配/声明.
- ![stars](https://img.shields.io/github/stars/mibk/dupl?style=flat-square&color=ccc) [dupl](https://github.com/mibk/dupl) -报告可能重复的代码.
- ![stars](https://img.shields.io/github/stars/kisielk/errcheck?style=flat-square&color=ccc) [errcheck](https://github.com/kisielk/errcheck) -检查是否使用了错误返回值.
- ![stars](https://img.shields.io/github/stars/lafolle/flen?style=flat-square&color=ccc) [flen](https://github.com/lafolle/flen) -在Go软件包中获取有关函数长度的信息.
- ![stars](https://img.shields.io/github/stars/securego/gosec?style=flat-square&color=ccc) [gas](https://securego.io/) -通过扫描Go AST检查源代码是否存在安全问题.
- [go tool vet --shadow](https://golang.org/cmd/vet/#hdr-Shadowed_variables) -报告可能被意外遮盖的变量.
- [go vet](https://golang.org/cmd/vet/) -检查Go源代码并报告可疑.
- ![stars](https://img.shields.io/github/stars/Quasilyte/go-consistent?style=flat-square&color=ccc) [go-consistent](https://github.com/Quasilyte/go-consistent) -分析器，可帮助您使Go程序更加一致.
- ![stars](https://img.shields.io/github/stars/go-critic/go-critic?style=flat-square&color=ccc) [go-critic](https://github.com/go-critic/go-critic) -保留检查当前未在其他linter中实现的检查的源代码linter.
- [go/ast](https://golang.org/pkg/go/ast/) -包ast声明用于表示Go包的语法树的类型.
- ![stars](https://img.shields.io/github/stars/leighmcculloch/gochecknoglobals?style=flat-square&color=ccc) [gochecknoglobals](https://github.com/leighmcculloch/gochecknoglobals) -检查是否没有全局变量.
- ![stars](https://img.shields.io/github/stars/jgautheron/goconst?style=flat-square&color=ccc) [goconst](https://github.com/jgautheron/goconst) -查找可以被常量替换的重复字符串.
- ![stars](https://img.shields.io/github/stars/fzipp/gocyclo?style=flat-square&color=ccc) [gocyclo](https://github.com/fzipp/gocyclo) -计算Go源代码中函数的圈复杂度.
- [gofmt -s](https://golang.org/cmd/gofmt/) -检查代码格式是否正确，是否无法进一步简化.
- [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) -检查丢失或未引用的程序包导入.
- ![stars](https://img.shields.io/github/stars/golangci/golangci-lint?style=flat-square&color=ccc) [GolangCI-Lint](https://golangci-lint.run/) -替代“ Go Meta Linter”：GolangCI-Lint是一个Linters聚合器.
- ![stars](https://img.shields.io/github/stars/golang/lint?style=flat-square&color=ccc) [golint](https://github.com/golang/lint) -在Go源代码中打印出编码样式错误.
- ![stars](https://img.shields.io/github/stars/linuxerwang/goroutine-inspect?style=flat-square&color=ccc) [goroutine-inspect](https://github.com/linuxerwang/goroutine-inspect) -分析Golang goroutine转储的交互式工具.
- ![stars](https://img.shields.io/github/stars/securego/gosec?style=flat-square&color=ccc) [gosec (gas)](https://securego.io/) -通过扫描Go AST检查源代码是否存在安全问题.
- [gotype](https://pkg.go.dev/golang.org/x/tools/cmd/gotype) -类似于Go编译器的语法和语义分析.
- ![stars](https://img.shields.io/github/stars/gordonklaus/ineffassign?style=flat-square&color=ccc) [ineffassign](https://github.com/gordonklaus/ineffassign) -在Go代码中检测无效分配
- ![stars](https://img.shields.io/github/stars/mvdan/interfacer?style=flat-square&color=ccc) [interfacer](https://github.com/mvdan/interfacer) ：警告：-建议使用较窄的接口.
- ![stars](https://img.shields.io/github/stars/walle/lll?style=flat-square&color=ccc) [lll](https://github.com/walle/lll) -报告长行.
- ![stars](https://img.shields.io/github/stars/mdempsky/maligned?style=flat-square&color=ccc) [maligned](https://github.com/mdempsky/maligned) -检测对字段进行排序后会占用较少内存的结构.
- ![stars](https://img.shields.io/github/stars/client9/misspell?style=flat-square&color=ccc) [misspell](https://github.com/client9/misspell) -查找通常拼写错误的英语单词.
- ![stars](https://img.shields.io/github/stars/alexkohler/nakedret?style=flat-square&color=ccc) [nakedret](https://github.com/alexkohler/nakedret) -寻找赤裸裸的回报.
- ![stars](https://img.shields.io/github/stars/alexkohler/nargs?style=flat-square&color=ccc) [nargs](https://github.com/alexkohler/nargs) -在函数声明中查找未使用的参数.
- ![stars](https://img.shields.io/github/stars/alexkohler/prealloc?style=flat-square&color=ccc) [prealloc](https://github.com/alexkohler/prealloc) -查找可能预先分配的切片声明.
- ![stars](https://img.shields.io/github/stars/mgechev/revive?style=flat-square&color=ccc) [revive](https://revive.run/)  -Go的快速，可配置，可扩展，灵活和美观的Liner.  即插即用更换细丝.
- ![stars](https://img.shields.io/github/stars/stripe/safesql?style=flat-square&color=ccc) [safesql](https://github.com/stripe/safesql) -用于Golang的静态分析工具，可防止SQL注入.
- ![stars](https://img.shields.io/github/stars/dominikh/go-tools?style=flat-square&color=ccc) [staticcheck](https://staticcheck.io/) -进行静态分析，专门用于发现错误，简化代码并提高性能.
- [structcheck](https://gitlab.com/opennota/check) -查找未使用的结构字段.
- [test](http://golang.org/pkg/testing/) -从stdlib测试模块显示测试失败的位置.
- ![stars](https://img.shields.io/github/stars/mdempsky/unconvert?style=flat-square&color=ccc) [unconvert](https://github.com/mdempsky/unconvert) -检测冗余类型转换.
- ![stars](https://img.shields.io/github/stars/alexkohler/unimport?style=flat-square&color=ccc) [unimport](https://github.com/alexkohler/unimport) -查找不必要的导入别名
- ![stars](https://img.shields.io/github/stars/mvdan/unparam?style=flat-square&color=ccc) [unparam](https://github.com/mvdan/unparam) -查找未使用的功能参数.
- [varcheck](https://gitlab.com/opennota/check) -查找未使用的全局变量和常量.
- ![stars](https://img.shields.io/github/stars/bombsimon/wsl?style=flat-square&color=ccc) [wsl](https://github.com/bombsimon/wsl) -在正确的位置插入空行.


<h2 id="groovy"> Groovy </h2>

- ![stars](https://img.shields.io/github/stars/CodeNarc/CodeNarc?style=flat-square&color=ccc) [CodeNarc](https://codenarc.github.io/CodeNarc/) -用于Groovy源代码的静态分析工具，可以监视和执行许多编码标准和最佳实践


<h2 id="haskell">哈斯克尔</h2>

- ![stars](https://img.shields.io/github/stars/ndmitchell/hlint?style=flat-square&color=ccc) [HLint](https://github.com/ndmitchell/hlint) -HLint是用于建议对Haskell代码进行可能的改进的工具.
- ![stars](https://img.shields.io/github/stars/ocharles/weeder?style=flat-square&color=ccc) [Weeder](https://github.com/ocharles/weeder) -使用Haskell代码检测无效出口或包裹进口的工具.


<h2 id="haxe">哈克斯</h2>

- ![stars](https://img.shields.io/github/stars/HaxeCheckstyle/haxe-checkstyle?style=flat-square&color=ccc) [Haxe Checkstyle](http://haxecheckstyle.github.io/docs/haxe-checkstyle/home.html) -静态分析工具，可帮助开发人员编写符合编码标准的Haxe代码.


<h2 id="java">爪哇</h2>

- [Checker Framework](https://checkerframework.org/) -Java的可插拔类型检查http://checkerframework.org/
- ![stars](https://img.shields.io/github/stars/checkstyle/checkstyle?style=flat-square&color=ccc) [checkstyle](https://checkstyle.org/) -检查Java源代码是否符合代码标准或一组验证规则（最佳做法）
- ![stars](https://img.shields.io/github/stars/mauricioaniche/ck?style=flat-square&color=ccc) [ck](https://github.com/mauricioaniche/ck) -通过处理源Java文件来计算Chidamber和Kemerer面向对象的指标
- ![stars](https://img.shields.io/github/stars/dspinellis/ckjm?style=flat-square&color=ccc) [ckjm](http://www.spinellis.gr/sw/ckjm/) -通过处理已编译的Java文件的字节码来计算Chidamber和Kemerer面向对象的指标
- ![stars](https://img.shields.io/github/stars/eclipse-cognicrypt/CogniCrypt?style=flat-square&color=ccc) [CogniCrypt](https://www.eclipse.org/cognicrypt/) -检查Java源代码和字节码是否正确使用了加密API
- [DesigniteJava](http://www.designite-tools.com/designitejava) ：copyright：-DesigniteJava支持各种架构，设计和实现气味的检测以及各种代码质量指标的计算.
- ![stars](https://img.shields.io/github/stars/google/error-prone?style=flat-square&color=ccc) [Error-prone](https://errorprone.info/) -捕获常见的Java错误作为编译时错误
- ![stars](https://img.shields.io/github/stars/mebigfatguy/fb-contrib?style=flat-square&color=ccc) [fb-contrib](http://fb-contrib.sourceforge.net/) -用于FindBugs的插件，带有其他错误检测器
- ![stars](https://img.shields.io/github/stars/policeman-tools/forbidden-apis?style=flat-square&color=ccc) [forbidden-apis](https://github.com/policeman-tools/forbidden-apis)  -检测并禁止调用特定的方法/类/字段（例如从没有字符集的文本流中读取）.  Maven / Gradle / Ant兼容.
- ![stars](https://img.shields.io/github/stars/google/google-java-format?style=flat-square&color=ccc) [google-java-format](https://github.com/google/google-java-format) -Google样式重新格式化
- ![stars](https://img.shields.io/github/stars/amaembo/huntbugs?style=flat-square&color=ccc) [HuntBugs](https://github.com/amaembo/huntbugs) ：warning：-基于Procyon编译器工具的字节码静态分析器工具，旨在取代FindBugs.
- [JArchitect](https://www.jarchitect.com) ：copyright：-测量，查询和可视化您的代码，避免意外的问题，技术负担和复杂性.
- [JBMC](https://www.cprover.org/jbmc/) -Java的有限模型检查器（字节码），验证用户定义的断言，标准断言，几种覆盖率度量分析
- ![stars](https://img.shields.io/github/stars/uber/NullAway?style=flat-square&color=ccc) [NullAway](https://github.com/uber/NullAway)  -基于类型的空指针检查器，具有较低的构建时间开销；  一个 [Error Prone](http://errorprone.info/) 插入
- ![stars](https://img.shields.io/github/stars/jeremylong/DependencyCheck?style=flat-square&color=ccc) [OWASP Dependency Check](https://owasp.org/www-project-dependency-check/) -检查依赖项是否存在已知的，公开披露的漏洞.
- ![stars](https://img.shields.io/github/stars/teamed/qulice?style=flat-square&color=ccc) [qulice](https://www.qulice.com/) -结合了一些（预先配置的）静态分析工具（checkstyle，PMD，Findbugs等）.
- ![stars](https://img.shields.io/github/stars/Sable/soot?style=flat-square&color=ccc) [Soot](https://sable.github.io/soot/) -用于分析和转换Java和Android应用程序的框架.
- ![stars](https://img.shields.io/github/stars/INRIA/spoon?style=flat-square&color=ccc) [Spoon](http://spoon.gforge.inria.fr/)  -Spoon是一个元编程库，用于分析和转换Java源代码（包括Java 9、10、11、12、13、14）.  它解析源文件以构建具有强大分析和转换API的精心设计的AST.  可以集成在Maven和Gradle中.
- ![stars](https://img.shields.io/github/stars/spotbugs/spotbugs?style=flat-square&color=ccc) [SpotBugs](https://spotbugs.github.io/)  -SpotBugs是FindBugs的继任者.  静态分析工具，用于查找Java代码中的错误.


<h2 id="javascript">的JavaScript </h2>

- ![stars](https://img.shields.io/github/stars/codecombat/aether?style=flat-square&color=ccc) [aether](http://aetherjs.com/) -在节点或浏览器中对用户JavaScript进行Lint，分析，规范化，转换，沙箱运行，逐步浏览和可视化.
- ![stars](https://img.shields.io/github/stars/google/closure-compiler?style=flat-square&color=ccc) [Closure Compiler](https://developers.google.com/closure/compiler/) -一种编译器工具，可提高效率，减小大小并在JavaScript文件中提供代码警告.
- ![stars](https://img.shields.io/github/stars/google/closure-linter?style=flat-square&color=ccc) [ClosureLinter](https://github.com/google/closure-linter)  ：warning：-确保您所有项目的JavaScript代码均遵循Google JavaScript样式指南中的指南.  它还可以自动修复许多常见错误
- ![stars](https://img.shields.io/github/stars/jared-stilwell/complexity-report?style=flat-square&color=ccc) [complexity-report](https://github.com/jared-stilwell/complexity-report) ：警告：-JavaScript项目的软件复杂性分析
- [DeepScan](https://deepscan.io) ：copyright：-一个JavaScript分析器，它针对运行时错误和质量问题，而不是编码约定.
- ![stars](https://img.shields.io/github/stars/jared-stilwell/escomplex?style=flat-square&color=ccc) [escomplex](https://github.com/jared-stilwell/escomplex) -JavaScript系列抽象语法树的软件复杂性分析.
- ![stars](https://img.shields.io/github/stars/eslint/eslint?style=flat-square&color=ccc) [eslint](https://eslint.org/) -完全可插拔的工具，用于识别和报告JavaScript模式
- ![stars](https://img.shields.io/github/stars/jquery/esprima?style=flat-square&color=ccc) [Esprima](https://esprima.org/) -ECMAScript解析基础架构，可进行多用途分析
- ![stars](https://img.shields.io/github/stars/facebook/flow?style=flat-square&color=ccc) [flow](https://flow.org/) -JavaScript的静态类型检查器.
- ![stars](https://img.shields.io/github/stars/JSMonk/hegel?style=flat-square&color=ccc) [hegel](https://hegel.js.org/) -JavaScript的静态类型检查器，带有类型推断偏向和强类型系统.
- ![stars](https://img.shields.io/github/stars/jshint/jshint?style=flat-square&color=ccc) [jshint](https://jedi.readthedocs.io/en/latest/) ：警告：-检测JavaScript代码中的错误和潜在问题，并执行团队的编码约定
- ![stars](https://img.shields.io/github/stars/douglascrockford/JSLint?style=flat-square&color=ccc) [JSLint](https://github.com/douglascrockford/JSLint) ：警告：-JavaScript代码质量工具
- ![stars](https://img.shields.io/github/stars/dpnishant/jsprime?style=flat-square&color=ccc) [JSPrime](http://dpnishant.github.io/jsprime/) -静态安全分析工具
- ![stars](https://img.shields.io/github/stars/es-analysis/plato?style=flat-square&color=ccc) [plato](https://github.com/es-analysis/plato) -可视化JavaScript源复杂度
- ![stars](https://img.shields.io/github/stars/jden/quality?style=flat-square&color=ccc) [quality](https://github.com/jden/quality) -零配置代码和模块棉绒
- ![stars](https://img.shields.io/github/stars/RetireJS/retire.js?style=flat-square&color=ccc) [retire.js](http://retirejs.github.io/retire.js/) -扫描程序检测已知漏洞的JavaScript库的使用
- ![stars](https://img.shields.io/github/stars/ternjs/tern?style=flat-square&color=ccc) [tern](https://ternjs.net/) -JavaScript代码分析器，可提供深入的跨编辑器语言支持
- ![stars](https://img.shields.io/github/stars/xojs/xo?style=flat-square&color=ccc) [xo](https://github.com/xojs/xo) - Opinionated but configurable ESLint wrapper with lots of goodies included. Enforces strict and readable code.
- ![stars](https://img.shields.io/github/stars/calmh/yardstick?style=flat-square&color=ccc) [yardstick](https://github.com/calmh/yardstick) ：警告：-Javascript代码指标


<h2 id="kotlin">科特林</h2>

- ![stars](https://img.shields.io/github/stars/arturbosch/detekt?style=flat-square&color=ccc) [detekt](https://detekt.github.io/detekt/) -Kotlin代码的静态代码分析.


<h2 id="lua">采取</h2>

- ![stars](https://img.shields.io/github/stars/mpeterv/luacheck?style=flat-square&color=ccc) [luacheck](https://github.com/mpeterv/luacheck) -用于Lua代码的整理和静态分析的工具.


<h2 id="matlab">的MATLAB </h2>

- [mlint](https://mathworks.com/help/matlab/ref/mlint.html) ：copyright：-检查MATLAB代码文件是否存在问题.


<h2 id="php">的PHP </h2>

- ![stars](https://img.shields.io/github/stars/mihaeu/dephpend?style=flat-square&color=ccc) [dephpend](https://dephpend.com/) -依赖性分析工具
- ![stars](https://img.shields.io/github/stars/sensiolabs-de/deprecation-detector?style=flat-square&color=ccc) [deprecation-detector](https://github.com/sensiolabs-de/deprecation-detector) -查找不推荐使用的（Symfony）代码的用法
- ![stars](https://img.shields.io/github/stars/sensiolabs-de/deptrac?style=flat-square&color=ccc) [deptrac](https://github.com/sensiolabs-de/deptrac) -强制执行有关软件层之间依赖性的规则.
- ![stars](https://img.shields.io/github/stars/Halleck45/DesignPatternDetector?style=flat-square&color=ccc) [DesignPatternDetector](https://github.com/Halleck45/DesignPatternDetector) -检测PHP代码中的设计模式
- ![stars](https://img.shields.io/github/stars/Symplify/EasyCodingSt和ard?style=flat-square&color=ccc) [EasyCodingSt和ard](https://www.tomasvotruba.com/blog/2017/05/03/combine-power-of-php-code-sniffer-和-php-cs-fixer-in-3-lines/) -结合 [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 和 [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
- ![stars](https://img.shields.io/github/stars/phpro/grumphp?style=flat-square&color=ccc) [GrumPHP](https://github.com/phpro/grumphp) -每次提交时检查代码
- ![stars](https://img.shields.io/github/stars/Trismegiste/Mondrian?style=flat-square&color=ccc) [Mondrian](http://trismegiste.github.io/Mondrian/) -使用图论的一组静态分析和重构工具
- ![stars](https://img.shields.io/github/stars/php-parallel-lint/PHP-Parallel-Lint?style=flat-square&color=ccc) [parallel-lint](https://github.com/php-parallel-lint/PHP-Parallel-Lint) -该工具检查PHP文件的语法的速度比串行检查的速度更快，输出结果也更出色.
- ![stars](https://img.shields.io/github/stars/psecio/parse?style=flat-square&color=ccc) [Parse](https://github.com/psecio/parse) -静态安全扫描仪
- ![stars](https://img.shields.io/github/stars/pdepend/pdepend?style=flat-square&color=ccc) [pdepend](https://pdepend.org/) -计算软件度量，例如PHP代码的圈复杂度.
- ![stars](https://img.shields.io/github/stars/etsy/phan?style=flat-square&color=ccc) [phan](https://github.com/phan/phan/wiki) -etsy的现代静电分析仪
- ![stars](https://img.shields.io/github/stars/carlosas/phpat?style=flat-square&color=ccc) [PHP Architecture Tester](https://github.com/carlosas/phpat) -易于使用的PHP体系结构测试工具.
- ![stars](https://img.shields.io/github/stars/rskuipers/php-assumptions?style=flat-square&color=ccc) [PHP Assumptions](https://github.com/rskuipers/php-assumptions) - Checks for weak assumptions
- ![stars](https://img.shields.io/github/stars/FriendsOfPHP/PHP-CS-Fixer?style=flat-square&color=ccc) [PHP Coding Standards Fixer](https://cs.symfony.com/) -根据PSR-1，PSR-2和Symfony标准等标准修复代码.
- ![stars](https://img.shields.io/github/stars/kalessil/phpinspectionsea?style=flat-square&color=ccc) [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-) -用于PHP的静态代码分析器.
- ![stars](https://img.shields.io/github/stars/QafooLabs/php-refactoring-browser?style=flat-square&color=ccc) [PHP Refactoring Browser](http://qafoolabs.github.io/php-refactoring-browser/) -重构助手
- ![stars](https://img.shields.io/github/stars/tomzx/php-semver-checker?style=flat-square&color=ccc) [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) -根据语义版本建议下一个版本
- ![stars](https://img.shields.io/github/stars/nikic/PHP-Parser?style=flat-square&color=ccc) [PHP-Parser](https://github.com/nikic/PHP-Parser) -用PHP编写的PHP解析器
- ![stars](https://img.shields.io/github/stars/Andrewsville/PHP-Token-Reflection?style=flat-square&color=ccc) [PHP-Token-Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) -库模拟PHP内部反射
- ![stars](https://img.shields.io/github/stars/sstalle/php7cc?style=flat-square&color=ccc) [php7cc](https://github.com/sstalle/php7cc) ：警告：-PHP 7兼容性检查器
- ![stars](https://img.shields.io/github/stars/Alexia/php7mar?style=flat-square&color=ccc) [php7mar](https://github.com/Alexia/php7mar) ：warning：-协助开发人员将其代码快速移植到PHP 7
- ![stars](https://img.shields.io/github/stars/squizlabs/PHP_CodeSniffer?style=flat-square&color=ccc) [PHP_CodeSniffer](https://pear.php.net/package/PHP_CodeSniffer) -检测违反已定义的一组编码标准
- ![stars](https://img.shields.io/github/stars/wapmorgan/PhpCodeAnalyzer?style=flat-square&color=ccc) [phpca](https://github.com/wapmorgan/PhpCodeAnalyzer) -查找非内置扩展名的用法
- [phpcf](http://wapmorgan.github.io/PhpCodeFixer/) -查找不推荐使用的PHP功能的用法
- ![stars](https://img.shields.io/github/stars/sebastianbergmann/phpcpd?style=flat-square&color=ccc) [phpcpd](https://github.com/sebastianbergmann/phpcpd) -用于PHP代码的复制/粘贴检测器.
- ![stars](https://img.shields.io/github/stars/sebastianbergmann/phpdcd?style=flat-square&color=ccc) [phpdcd](https://github.com/sebastianbergmann/phpdcd) ：warning：-死代码检测器（DCD）用于PHP代码.
- ![stars](https://img.shields.io/github/stars/mamuz/PhpDependencyAnalysis?style=flat-square&color=ccc) [PhpDependencyAnalysis](https://mamuz.github.io/PhpDependencyAnalysis/) -为项目建立依赖图
- ![stars](https://img.shields.io/github/stars/dunglas/phpdoc-to-typehint?style=flat-square&color=ccc) [phpdoc-to-typehint](https://github.com/dunglas/phpdoc-to-typehint) -使用PHPDoc批注添加标量类型提示并向现有的PHP项目返回类型
- ![stars](https://img.shields.io/github/stars/phpDocumentor/phpDocumentor?style=flat-square&color=ccc) [phpDocumentor](https://www.phpdoc.org/) -分析PHP源代码以生成文档
- ![stars](https://img.shields.io/github/stars/phpmd/phpmd?style=flat-square&color=ccc) [PHPMD](https://phpmd.org/) -在代码中发现可能的错误
- ![stars](https://img.shields.io/github/stars/phpmetrics/PhpMetrics?style=flat-square&color=ccc) [PhpMetrics](http://www.phpmetrics.org/) -计算和可视化各种代码质量指标
- ![stars](https://img.shields.io/github/stars/povils/phpmnd?style=flat-square&color=ccc) [phpmnd](https://github.com/povils/phpmnd) -有助于检测魔术数字
- ![stars](https://img.shields.io/github/stars/EdgedesignCZ/phpqa?style=flat-square&color=ccc) [PHPQA](https://edgedesigncz.github.io/phpqa/) -用于运行质量检查工具的工具（phploc，phpcpd，phpcs，pdepend，phpmd，phpmetrics）
- ![stars](https://img.shields.io/github/stars/jakzal/phpqa?style=flat-square&color=ccc) [phpqa - jakzal](https://github.com/jakzal/phpqa) -在一个容器中有许多用于PHP静态分析的工具
- ![stars](https://img.shields.io/github/stars/jmolivas/phpqa?style=flat-square&color=ccc) [phpqa - jmolivas](https://github.com/jmolivas/phpqa) -PHPQA多合一分析器CLI工具
- ![stars](https://img.shields.io/github/stars/ovr/phpsa?style=flat-square&color=ccc) [phpsa](https://github.com/ovr/phpsa) -用于PHP的静态分析工具.
- ![stars](https://img.shields.io/github/stars/phpstan/phpstan?style=flat-square&color=ccc) [PHPStan](https://phpstan.org/) -PHP静态分析工具-无需运行即可发现代码中的错误！
- ![stars](https://img.shields.io/github/stars/designsecurity/progpilot?style=flat-square&color=ccc) [Progpilot](https://github.com/designsecurity/progpilot) -出于安全目的的静态分析工具
- ![stars](https://img.shields.io/github/stars/vimeo/psalm?style=flat-square&color=ccc) [Psalm](https://psalm.dev/) -用于在PHP应用程序中查找类型错误的静态分析工具
- ![stars](https://img.shields.io/github/stars/Qafoo/QualityAnalyzer?style=flat-square&color=ccc) [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) -可视化指标和源代码
- ![stars](https://img.shields.io/github/stars/ircmaxell/Tuli?style=flat-square&color=ccc) [Tuli](https://github.com/ircmaxell/Tuli) -静态分析引擎
- ![stars](https://img.shields.io/github/stars/asm89/twig-lint?style=flat-square&color=ccc) [twig-lint](https://github.com/asm89/twig-lint) -twig-lint是用于您的twig文件的皮棉工具.
- [WAP](https://securityonline.info/owasp-wap-web-application-protection-project/) -用于检测和纠正PHP（4.0或更高版本）Web应用程序中的输入验证漏洞的工具，并通过结合静态分析和数据挖掘来预测误报.


<h2 id="perl">佩尔</h2>

- [Perl::Critic](https://metacpan.org/pod/Perl::Critic) -Critique Perl最佳实践的源代码.


<h2 id="python">蟒蛇</h2>

- ![stars](https://img.shields.io/github/stars/PyCQA/bandit?style=flat-square&color=ccc) [bandit](https://bandit.readthedocs.io/en/latest/) -在Python代码中查找常见安全问题的工具
- ![stars](https://img.shields.io/github/stars/hchasestevens/bellybutton?style=flat-square&color=ccc) [bellybutton](https://github.com/hchasestevens/bellybutton) -支持自定义项目特定规则的整理引擎
- ![stars](https://img.shields.io/github/stars/mschwager/cohesion?style=flat-square&color=ccc) [cohesion](https://github.com/mschwager/cohesion) -用于测量Python类内聚力的工具
- ![stars](https://img.shields.io/github/stars/dlint-py/dlint?style=flat-square&color=ccc) [Dlint](https://github.com/dlint-py/dlint) -确保Python代码安全的工具
- ![stars](https://img.shields.io/github/stars/feddischson/include_gardener?style=flat-square&color=ccc) [include-gardener](https://github.com/feddischson/include_gardener) - a multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
- ![stars](https://img.shields.io/github/stars/davidhalter/jedi?style=flat-square&color=ccc) [jedi](https://jedi.readthedocs.io/en/latest/) -适用于Python的自动完成/静态分析库
- ![stars](https://img.shields.io/github/stars/lyft/linty_fresh?style=flat-square&color=ccc) [linty fresh](https://github.com/lyft/linty_fresh) -解析皮棉错误并将其作为请求请求的注释报告给Github
- ![stars](https://img.shields.io/github/stars/PyCQA/mccabe?style=flat-square&color=ccc) [mccabe](https://pypi.org/project/mccabe/) -检查McCabe的复杂性
- ![stars](https://img.shields.io/github/stars/python/mypy?style=flat-square&color=ccc) [mypy](http://www.mypy-lang.org/) -静态类型检查器，旨在结合经常使用的鸭子类型和静态类型的优点 [MonkeyType](https://github.com/Instagram/MonkeyType)
- ![stars](https://img.shields.io/github/stars/uber/py-find-injection?style=flat-square&color=ccc) [py-find-injection](https://github.com/uber/py-find-injection) ：警告：-在Python代码中查找SQL注入漏洞
- ![stars](https://img.shields.io/github/stars/PyCQA/pycodestyle?style=flat-square&color=ccc) [pycodestyle](https://pycodestyle.pycqa.org/en/latest/) -（以前是`pep8`）根据PEP 8中的某些样式约定检查Python代码
- ![stars](https://img.shields.io/github/stars/PyCQA/pydocstyle?style=flat-square&color=ccc) [pydocstyle](http://www.pydocstyle.org) -检查是否符合Python文档字符串约定
- [pyflakes](https://pypi.org/project/pyflakes/) -检查Python源文件是否有错误
- ![stars](https://img.shields.io/github/stars/PyCQA/pylint?style=flat-square&color=ccc) [pylint](http://pylint.pycqa.org/en/latest/)  -查找编程错误，帮助实施编码标准并嗅探某些代码气味.  它还包括“ pyreverse”（UML图生成器）和“ symilar”（相似性检查器）.
- ![stars](https://img.shields.io/github/stars/facebook/pyre-check?style=flat-square&color=ccc) [pyre-check](https://pyre-check.org/) -用于大型Python代码库的快速，可扩展的类型检查器
- ![stars](https://img.shields.io/github/stars/Microsoft/pyright?style=flat-square&color=ccc) [pyright](https://github.com/Microsoft/pyright) -用于Python的静态类型检查器，用于解决现有工具（如mypy）中的空白.
- ![stars](https://img.shields.io/github/stars/regebro/pyroma?style=flat-square&color=ccc) [pyroma](https://github.com/regebro/pyroma) -评估Python项目与Python打包生态系统的最佳实践的符合程度，并列出可以改进的问题
- ![stars](https://img.shields.io/github/stars/python-security/pyt?style=flat-square&color=ccc) [PyT - Python Taint](https://github.com/python-security/pyt) ：warning：-静态分析工具，用于检测Python Web应用程序中的安全漏洞.
- ![stars](https://img.shields.io/github/stars/google/pytype?style=flat-square&color=ccc) [pytype](https://google.github.io/pytype/) -用于Python代码的静态类型分析器.
- ![stars](https://img.shields.io/github/stars/rubik/radon?style=flat-square&color=ccc) [radon](https://radon.readthedocs.io/en/latest/) -一个Python工具，可从源代码计算各种指标
- ![stars](https://img.shields.io/github/stars/jendrikseipp/vulture?style=flat-square&color=ccc) [vulture](https://github.com/jendrikseipp/vulture) -在Python代码中查找未使用的类，函数和变量
- ![stars](https://img.shields.io/github/stars/wemake-services/wemake-python-styleguide?style=flat-square&color=ccc) [wemake-python-styleguide](https://wemake-python-stylegui.de) -有史以来最严格，最自以为是的python linter
- ![stars](https://img.shields.io/github/stars/tonybaloney/wily?style=flat-square&color=ccc) [wily](https://github.com/tonybaloney/wily) -用于归档，探索和绘制Python源代码复杂性的命令行工具
- ![stars](https://img.shields.io/github/stars/rubik/xenon?style=flat-square&color=ccc) [xenon](https://xenon.readthedocs.io/) -使用监视代码的复杂性 [`radon`](https://github.com/rubik/radon)


<h2 id="r"> [R </h2>

- ![stars](https://img.shields.io/github/stars/MangoTheCat/cyclocomp?style=flat-square&color=ccc) [cyclocomp](https://github.com/MangoTheCat/cyclocomp) -量化R函数/表达式的圈复杂度.
- ![stars](https://img.shields.io/github/stars/mangothecat/goodpractice?style=flat-square&color=ccc) [goodpractice](http://mangothecat.github.io/goodpractice/) -分析R软件包的源代码并提供最佳实践建议.
- ![stars](https://img.shields.io/github/stars/jimhester/lintr?style=flat-square&color=ccc) [lintr](https://github.com/jimhester/lintr) -R的静态代码分析.


<h2 id="rpg">角色扮演游戏</h2>

- [SourceMeter](https://www.sourcemeter.com/resources/rpg/) ：copyright：-RPG III和RPG IV版本的静态代码分析（包括自由格式）


<h2 id="ruby">红宝石</h2>

- ![stars](https://img.shields.io/github/stars/presidentbeef/brakeman?style=flat-square&color=ccc) [brakeman](https://brakemanscanner.org/) -用于Ruby on Rails应用程序的静态分析安全漏洞扫描程序
- ![stars](https://img.shields.io/github/stars/square/cane?style=flat-square&color=ccc) [cane](https://github.com/square/cane) -代码质量阈值检查作为构建的一部分
- ![stars](https://img.shields.io/github/stars/seattlerb/flay?style=flat-square&color=ccc) [flay](https://ruby.sadi.st/Flay.html) -Flay分析代码的结构相似性.
- ![stars](https://img.shields.io/github/stars/seattlerb/flog?style=flat-square&color=ccc) [flog](https://ruby.sadi.st/Flog.html)  -Flog在易于阅读的疼痛报告中报告了遭受最多折磨的代码.  分数越高，代码所处的痛苦就越大.
- ![stars](https://img.shields.io/github/stars/feddischson/include_gardener?style=flat-square&color=ccc) [include-gardener](https://github.com/feddischson/include_gardener) - a multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.
- ![stars](https://img.shields.io/github/stars/michaeledgar/laser?style=flat-square&color=ccc) [laser](https://github.com/michaeledgar/laser) ：warning：-Ruby代码的静态分析和样式分析.
- ![stars](https://img.shields.io/github/stars/codegram/pelusa?style=flat-square&color=ccc) [pelusa](https://github.com/codegram/pelusa) -静态分析Lint型工具，可改善您的OO Ruby代码
- ![stars](https://img.shields.io/github/stars/soutaro/querly?style=flat-square&color=ccc) [Querly](https://github.com/soutaro/querly) -基于模式的Ruby检查工具
- ![stars](https://img.shields.io/github/stars/david-a-wheeler/railroader?style=flat-square&color=ccc) [Railroader](https://railroader.org/) -针对Ruby on Rails应用程序的开源静态分析安全漏洞扫描程序.
- ![stars](https://img.shields.io/github/stars/troessner/reek?style=flat-square&color=ccc) [reek](https://github.com/troessner/reek) -Ruby代码气味检测器
- ![stars](https://img.shields.io/github/stars/rubocop-hq/rubocop?style=flat-square&color=ccc) [RuboCop](https://docs.rubocop.org/rubocop/) -基于社区Ruby样式指南的Ruby静态代码分析器.
- ![stars](https://img.shields.io/github/stars/blazeeboy/rubrowser?style=flat-square&color=ccc) [Rubrowser](http://www.emadelsaid.com/rubrowser/) -Ruby类交互式依赖图生成器.
- [ruby-lint](http://code.yorickpeterse.com/ruby-lint/latest/) ：warning：-Ruby的静态代码分析
- ![stars](https://img.shields.io/github/stars/whitesmith/rubycritic?style=flat-square&color=ccc) [rubycritic](https://github.com/whitesmith/rubycritic) -Ruby代码质量报告程序
- ![stars](https://img.shields.io/github/stars/makaroni4/sandi_meter?style=flat-square&color=ccc) [SandiMeter](https://rubygems.org/gems/sandi_meter) ：warning：-用于检查Ruby代码中Sandi Metz规则的静态分析工具.
- ![stars](https://img.shields.io/github/stars/sorbet/sorbet?style=flat-square&color=ccc) [Sorbet](https://sorbet.org/) -专为Ruby设计的快速，强大的类型检查器


<h2 id="rust">锈</h2>

- ![stars](https://img.shields.io/github/stars/RustSec/cargo-audit?style=flat-square&color=ccc) [cargo-audit](https://rustsec.org/) -审核Cargo.lock，以将带有安全漏洞的板条箱报告给 [RustSec Advisory Database](https://github.com/RustSec/advisory-db/).
- ![stars](https://img.shields.io/github/stars/mre/cargo-inspect?style=flat-square&color=ccc) [cargo-inspect](https://github.com/mre/cargo-inspect) - Inspect Rust code without syntactic sugar to see what the compiler does behind the curtains.
- ![stars](https://img.shields.io/github/stars/Manishearth/rust-clippy?style=flat-square&color=ccc) [clippy](https://rust-lang.github.io/rust-clippy/) -防止常见错误并改进Rust代码的代码仓库
- ![stars](https://img.shields.io/github/stars/Kha/electrolysis?style=flat-square&color=ccc) [electrolysis](http://kha.github.io/electrolysis/) -通过在精益定理证明者中将其转换为定义来正式验证Rust程序的工具.
- [herbie](https://github.com/mcarton/rust-herbie-lint) -在使用数值不稳定的浮点表达式时，在包装箱中添加警告或错误.
- ![stars](https://img.shields.io/github/stars/AtomLinter/linter-rust?style=flat-square&color=ccc) [linter-rust](https://github.com/AtomLinter/linter-rust) -使用Rustc和货物在Atom中整理您的Rust文件
- ![stars](https://img.shields.io/github/stars/facebookexperimental/MIRAI?style=flat-square&color=ccc) [MIRAI](https://github.com/facebookexperimental/MIRAI) -使用Rust的中级中间语言的抽象解释器，并基于异味分析提供警告.
- ![stars](https://img.shields.io/github/stars/rust-lang-nursery/rls?style=flat-square&color=ccc) [Rust Language Server](https://github.com/rust-lang-nursery/rls) -支持诸如“转到定义”，符号搜索，重新格式化和代码完成之类的功能，并支持重命名和重构.
- ![stars](https://img.shields.io/github/stars/rust-lang/rustfix?style=flat-square&color=ccc) [rustfix](https://github.com/rust-lang/rustfix) -阅读并应用rustc（和第三方皮棉，如clippy提供的建议）提出的建议.


<h2 id="sql">的SQL </h2>

- ![stars](https://img.shields.io/github/stars/jarulraj/sqlcheck?style=flat-square&color=ccc) [sqlcheck](https://github.com/jarulraj/sqlcheck) -自动识别SQL查询中的反模式
- ![stars](https://img.shields.io/github/stars/purcell/sqlint?style=flat-square&color=ccc) [sqlint](https://github.com/purcell/sqlint) -简单的SQL linter
- ![stars](https://img.shields.io/github/stars/tsqllint/tsqllint?style=flat-square&color=ccc) [tsqllint](https://github.com/tsqllint/tsqllint) -T-SQL专用的linter
- ![stars](https://img.shields.io/github/stars/ashleyglee/TSqlRules?style=flat-square&color=ccc) [TSqlRules](https://github.com/ashleyglee/TSqlRules) -SQL Server的TSQL静态代码分析规则


<h2 id="scala">阶梯</h2>

- ![stars](https://img.shields.io/github/stars/HairyFotr/linter?style=flat-square&color=ccc) [linter](https://github.com/HairyFotr/linter) -Linter是一个Scala静态分析编译器插件，它为各种可能的bug，效率低下和样式问题添加了编译时检查.
- ![stars](https://img.shields.io/github/stars/scalastyle/scalastyle?style=flat-square&color=ccc) [Scalastyle](http://www.scalastyle.org) -Scalastyle检查您的Scala代码并指出其潜在问题.
- ![stars](https://img.shields.io/github/stars/sksamuel/scapegoat?style=flat-square&color=ccc) [scapegoat](https://github.com/sksamuel/scapegoat) -用于静态代码分析的Scala编译器插件
- ![stars](https://img.shields.io/github/stars/puffnfresh/wartremover?style=flat-square&color=ccc) [WartRemover](https://www.wartremover.org/) -灵活的Scala代码整理工具.


<h2 id="shell">贝壳</h2>

- ![stars](https://img.shields.io/github/stars/lequal/i-CodeCNES?style=flat-square&color=ccc) [i-Code CNES for Shell](https://github.com/lequal/i-CodeCNES) -用于Shell和Fortran（77和90）的开源静态代码分析工具.
- ![stars](https://img.shields.io/github/stars/koalaman/shellcheck?style=flat-square&color=ccc) [shellcheck](https://www.shellcheck.net/) -ShellCheck，一种静态分析工具，可为bash / sh shell脚本提供警告和建议


<h2 id="solidity">坚固性</h2>

- ![stars](https://img.shields.io/github/stars/trailofbits/slither?style=flat-square&color=ccc) [slither](https://github.com/trailofbits/slither) -静态分析框架，该框架运行一套漏洞检测器，可打印有关合同详细信息的可视信息，并提供可轻松编写自定义分析的API
- ![stars](https://img.shields.io/github/stars/duaraghav8/Solium?style=flat-square&color=ccc) [solium](https://ethlint.readthedocs.io/en/latest/) -Solium是一台可以识别和修复Solidity智能合约中的样式和安全问题的工具


<h2 id="swift">迅速</h2>

- ![stars](https://img.shields.io/github/stars/realm/SwiftLint?style=flat-square&color=ccc) [SwiftLint](https://realm.github.io/SwiftLint/) -实施Swift样式和约定的工具
- ![stars](https://img.shields.io/github/stars/sleekbyte/tailor?style=flat-square&color=ccc) [Tailor](https://tailor.sh/) ：warning：-用于使用Apple的Swift编程语言编写的源代码的静态分析和皮棉工具.


<h2 id="tcl"> Tcl </h2>

- [Frink](https://catless.ncl.ac.uk/Programs/Frink/) -Tcl格式化和静态检查程序（可以美化该程序，将其最小化，混淆或仅对其进行完整性检查）.
- [Nagelfar](https://sourceforge.net/projects/nagelfar/) -Tcl的静态语法检查器
- [tclchecker](https://github.com/ActiveState/tdk/blob/master/docs/3.0/TDK_3.0_Checker.txt) -静态语法分析模块（作为 [TDK](https://github.com/ActiveState/tdk)).


<h2 id="typescript">打字稿</h2>

- ![stars](https://img.shields.io/github/stars/mgechev/codelyzer?style=flat-square&color=ccc) [Codelyzer](http://codelyzer.com/) -一组tslint规则，用于Angular 2 TypeScript项目的静态代码分析.
- ![stars](https://img.shields.io/github/stars/typescript-eslint/typescript-eslint?style=flat-square&color=ccc) [ESLint](https://github.com/typescript-eslint/typescript-eslint) -TypeScript语言的可扩展linter.
- ![stars](https://img.shields.io/github/stars/Glavin001/tslint-clean-code?style=flat-square&color=ccc) [tslint-clean-code](https://www.npmjs.com/package/tslint-clean-code) -受《清洁规范》手册启发的一组TSLint规则.
- ![stars](https://img.shields.io/github/stars/Microsoft/tslint-microsoft-contrib?style=flat-square&color=ccc) [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib) -一组由Microsoft维护的Typelin项目的静态代码分析的tslint规则.


<h2 id="vbscript"> VB脚本</h2>

- [Test Design Studio](http://patterson-consulting.net/tds) ：copyright：-具有静态代码分析功能的完整IDE，用于Micro Focus统一功能测试，基于VBScript的自动化测试.


## Multiple languages

- [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) :copyright: - Static analysis for C/C++/C#, PHP and Java 
- [Application Inspector](https://www.ptsecurity.com/ww-en/products/ai/) ：copyright：-商业静态代码分析，生成用于验证漏洞的漏洞. 
- [ApplicationInspector](https://github.com/microsoft/ApplicationInspector) -创建用于功能检测的400多种规则模式的报告（例如，在应用程序中使用加密或版本控制）. 
- [AppScan Source](https://www.hcltechsw.com/wps/portal/products/appscan/home) ：copyright：-商业静态代码分析. 
- [APPscreener](https://solarappscreener.com/) :copyright: - Static code analysis for binary and source code - Java/Scala, PHP, Javascript, C#, PL/SQL, Python, T-SQL, C/C++, ObjectiveC/Swift, Visual Basic 6.0, Ruby, Delphi, ABAP, HTML5 and Solidity 
- [ArchUnit](https://www.archunit.org/) -对Java或Kotlin架构进行单元测试 
- [Atom-Beautify](https://atom.io/packages/atom-beautify) - Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom editor 
- [Axivion Bauhaus Suite](https://www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: - Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95 
- [Black](https://black.readthedocs.io/en/stable/) -毫不妥协的Python代码格式化程序 
- [CAST Highlight](https://www.castsoftware.com/products/highlight) ：copyright：-商业静态代码分析，该分析在本地运行，但是将结果上传到其云中进行演示. 
- [Checkmarx CxSAST](https://www.checkmarx.com/products/static-application-security-testing/) ：copyright：-不需要预编译的商业静态代码分析. 
- [ciocheck](https://github.com/ContinuumIO/ciocheck)  -linter，格式化程序和测试套件帮助器.  作为短绒棉，它是包裹在“ pep8”，“ pydocstyle”，“ flake8”和“ pylint”周围的包装纸. 
- [ClassGraph](https://github.com/classgraph/classgraph) -用于查询或可视化类元数据或类相关性的类路径和模块路径扫描程序. 
- [coala](https://coala.io/) -用于创建代码分析的语言独立框架-支持 [over 60 languages](https://coala.io/languages) 默认 
- [Cobra](http://spinroot.com/cobra/) ：copyright：-NASA喷气推进实验室的结构源代码分析器. 
- [Codeac](https://www.codeac.io?ref=awesome-static-analysis)  ：copyright：-自动代码审查工具与GitHub，Bitbucket和GitLab（甚至是自托管）集成.  适用于JavaScript，TypeScript，Python，Ruby，Go，PHP，Java，Docker等.  （免费开源） 
- [codeburner](http://groupon.github.io/codeburner/) -提供统一的界面来对发现的问题进行排序并采取行动 
- [codechecker](https://codechecker.readthedocs.io/en/latest/) -具有Web GUI的Clang静态分析器的缺陷数据库和查看器扩展 
- [CodeFactor](https://codefactor.io) :copyright: - Static Code Analysis for C#, C, C++, CoffeeScript, CSS, Groovy, GO, JAVA, JavaScript, Less, Python, Ruby, Scala, SCSS, TypeScript. 
- [CodeIt.Right](https://submain.com/products/codeit.right.aspx) ：copyright：-CodeIt.Right™提供了一种快速，自动化的方法，以确保您的源代码遵循（您的）预定义的设计和样式指南以及最佳编码实践 
- [CodePatrol](https://cyber-security.claranet.fr/en/codepatrol) ：copyright：-由安全性驱动的自动SAST代码审查，支持15种以上的语言，并包括安全性培训. 
- [CodeRush](https://www.devexpress.com/products/coderush/) ：copyright：-使用Visual Studio 2015及更高版本中的Roslyn引擎的代码创建，调试，导航，重构，分析和可视化工具. 
- [CodeScene](https://empear.com/) ：copyright：-CodeScene优先考虑技术债务，查找社会模式并识别代码中的隐患. 
- [Corrode](https://github.com/jameysharp/corrode)  -从C到Rust的半自动翻译.  通过显示Rust编译器警告和错误，可以揭示原始实现中的错误. 
- [Coverity](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - Synopsys Coverity supports 20 languages and over 70 frameworks including Ruby on rails, Scala, PHP, Python, JavaScript, TypeScript, Java, Fortran, C, C++, C#, VB.NET. 
- [cqc](https://github.com/xcatliu/cqc) -检查js，jsx，vue，css，less，scss，sass和styl文件的代码质量. 
- [CSScomb](https://github.com/csscomb/csscomb.js)  -CSS的编码样式格式化程序.  支持自己的配置，使样式表美观且一致 
- [dawnscanner](https://github.com/thesp0nge/dawnscanner)  -用于ruby编写的Web应用程序的静态分析安全扫描程序.  它支持Sinatra，Padrino和Ruby on Rails框架. 
- [DeepCode](https://www.deepcode.ai/)  ：copyright：-DeepCode根据AI查找错误，安全漏洞，性能和API问题.  DeepCode的分析速度使我们可以实时分析您的代码，并在您单击IDE中的“保存”按钮时提供结果.  支持的语言是Java，C / C ++，JavaScript，Python和TypeScript.  与GitHub，BitBucket和Gitlab的集成. 
- [DeepSource](https://deepsource.io/)  ：copyright：-深入的静态分析以监视源代码的质量和安全性.  支持Python和Go，并且可以在错误风险，安全性，反模式，性能，文档和样式等垂直方面检测600多种类型的问题.  与GitHub的本机集成. 
- [Depends](https://github.com/multilang-depends/depends) -分析Java，C / C ++，Ruby的代码元素的全面依赖关系. 
- [DevSkim](https://github.com/microsoft/devskim) - Regex-based static analysis tool for Visual Studio, VS Code, and Sublime Text - C/C++, C#, PHP, ASP, Python, Ruby, Java, and others. 
- [Embold](https://embold.io) :copyright: - Intelligent software analytics platform that identifies design issues, code issues, duplication and metrics. Supports Java, C, C++, C#, JavaScript, TypeScript, Python, Go, Kotlin and more. 
- [exakat](https://www.exakat.io/) -用于PHP的自动代码审查引擎 
- [Find Security Bugs](https://find-sec-bugs.github.io/)  -SpotBugs插件，用于Java Web应用程序和Android应用程序的安全审核.  （还与Kotlin，Groovy和Scala项目一起工作） 
- [flake8](https://github.com/PyCQA/flake8) -围绕pyflakes，pycodestyle和mccabe的包装器 
- [Fortify](https://software.microfocus.com/en-us/products/static-code-analysis-sast/overview) :copyright: - A commercial static analysis platform that supports the scanning of C/C++, C#, VB.NET, VB6, ABAP/BSP, ActionScript, Apex, ASP.NET, Classic ASP, VB Script, Cobol, ColdFusion, HTML, Java, JS, JSP, MXML/Flex, Objective-C, PHP, PL/SQL, T-SQL, Python (2.6, 2.7), Ruby (1.9.3), Swift, Scala, VB, and XML. 
- [Go Meta Linter](https://github.com/alecthomas/gometalinter)  ：warning：-同时运行Go lint工具并标准化其输出.  将`golangci-lint`用于新项目. 
- [Goodcheck](https://sider.github.io/goodcheck/) -基于正则表达式的可定制棉短绒 
- [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) -同时运行许多linter，并将其输出标准化为报告. 
- [graudit](http://www.justanotherhacker.com/) -Grep粗略审核-源代码审核工具 
- [Hopper](https://github.com/cuplv/hopper) -用scala编写的针对JVM上运行的语言的静态分析工具 
- [Hound CI](https://houndci.com/)  -在GitHub拉取请求中评论样式违规.  支持Coffeescript，Go，HAML，JavaScript，Ruby，SCSS和Swift. 
- [imhotep](https://github.com/justinabrahms/imhotep) -注释进入存储库的提交，并检查语法错误和常规的掉毛警告. 
- [Infer](https://fbinfer.com/) -用于Java，C和Objective-C的静态分析器 
- [InsiderSec](https://insidersec.io/) - A open source Static Application Security Testing tool (SAST) written in GoLang for Java (Maven and Android), Kotlin (Android), Swift (iOS), .NET Full Framework, C# and Javascript (Node.js). 
- [Kiuwan](https://www.kiuwan.com/code-security-sast/) :copyright: - Identify and remediate cyber threats in a blazingly fast, collaborative environment, with seamless integration in your SDLC. Python, C\C++, Java, C#, PHP and more 
- [Klocwork](https://www.perforce.com/products/klocwork) ：copyright：-针对C / C ++，Java和C的质量和安全性静态分析# 
- [ktlint](https://ktlint.github.io/) -带有内置格式化程序的防骑自行车科特林短绒 
- [LGTM.com](https://lgtm.com/)  ：copyright：-针对GitHub和Bitbucket的深入代码分析，以发现安全漏洞和关键代码质量问题（使用Semmle QL）.  自动查看拉取请求的代码；  免费用于公共存储库. 
- [multilint](https://github.com/adamchainz/multilint) -围绕“ flake8”，“ isort”和“ modernize”的包装 
- [Nitpick CI](https://nitpick-ci.com) ：copyright：-自动化PHP代码审查 
- [NodeJSScan](https://opensecurity.in/) -NodeJsScan是用于Node.js应用程序的静态安全代码扫描程序. 
- [oclint](http://oclint.org/) -静态源代码分析工具，可提高C，C ++和Objective-C的质量并减少缺陷 
- [pfff](https://github.com/facebookarchive/pfff/wiki/Main) ：warning：-Facebook用于多种语言的代码分析，可视化或保留样式源转换的工具 
- [PMD](https://pmd.github.io/) - A source code analyzer for Java, Javascript, PLSQL, XML, XSL and others 
- [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer) -Web组件的静态分析框架. 
- [pre-commit](https://pre-commit.com/) - A framework for managing and maintaining multi-language pre-commit hooks. 
- [Prettier](https://prettier.io/) -固执己见的代码格式化程序. 
- [Pronto](https://github.com/prontolabs/pronto)  -快速自动代码审查您的更改.  支持40多种语言的跑步者，包括Clang，Elixir，JavaScript，PHP，Ruby等 
- [prospector](https://github.com/PyCQA/prospector) -在`pylint`，`pep8`，`mccabe`等周围包装 
- [PT.PM](https://github.com/PositiveTechnologies/PT.PM) :warning: - An engine for searching patterns in the source code, based on Unified AST or UST. At present time C#, Java, PHP, PL/SQL, T-SQL, and JavaScript are supported. Patterns can be described within the code or using a DSL. 
- [PullRequest](https://www.pullrequest.com) ：copyright：-将代码审查作为具有内置静态分析的服务 
- [Puma Scan](https://pumasecurity.io/) -开发团队在Visual Studio中编写代码时，Puma Scan为常见漏洞（XSS，SQLi，CSRF，LDAPi，加密，反序列化等）提供了实时安全的代码分析. 
- [PVS-Studio](https://www.viva64.com/en/pvs-studio/) ：版权：-a（[conditionally free](https://www.viva64.com/en/b/0614/) for FOSS and individual developers) static analysis of C, C++, C# and Java code. For advertising purposes [you can propose a large FOSS project for analysis by PVS employees](https://github.com/viva64/pvs-studio-check-list) .  支持CWE映射，MISRA和CERT编码标准. 
- [quality](https://github.com/apiology/quality) -使用社区工具对代码进行质量检查，并确保您的代码不会随着时间的推移而恶化. 
- [Qualys Container Security](https://www.qualys.com/apps/container-security/) ：copyright：-容器本机应用程序保护，以提供对容器化应用程序的可见性和控制. 
- [QuantifiedCode](https://github.com/quantifiedcode/quantifiedcode) ：警告：-自动代码审查和修复 
- [Refactoring Essentials](https://marketplace.visualstudio.com/items?itemName=SharpDevelopTeam.RefactoringEssentialsforVisualStudio) - The free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers. 
- [ReSharper](https://www.jetbrains.com/resharper/) :copyright: - Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies. 
- [Reviewdog](https://github.com/haya14busa/reviewdog) -一种在任何代码托管服务中发布来自任何linter的评论评论的工具. 
- [RIPS](https://www.ripstech.com/) ：copyright：-用于PHP脚本中漏洞的静态源代码分析器 
- [Roslyn Analyzers](https://github.com/dotnet/roslyn-analyzers) -基于Roslyn的FxCop分析仪实施. 
- [Roslyn Security Guard](https://security-code-scan.github.io/) -该项目侧重于识别潜在漏洞，例如SQL注入，跨站点脚本（XSS），CSRF，加密漏洞，硬编码密码等. 
- [Security Code Scan](https://security-code-scan.github.io/) - Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc. Integrates into Visual Studio 2015 and newer. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc. 
- [Semmle QL and LGTM](https://semmle.com/)  ：copyright：-使用对源代码的查询来查找安全漏洞，变体和关键代码质量问题.  自动审查PR代码；  对于公共GitHub / Bitbucket回购免费： [LGTM.com](https://LGTM.com). 
- [SensioLabs Insight](https://insight.sensiolabs.com/) ：copyright：-检测安全风险，查找错误并为PHP项目提供可操作的指标 
- [shipshape](https://github.com/google/shipshape) ：警告：-静态程序分析平台，允许自定义分析器通过通用接口插入 
- [Sider](https://sider.review)  ：copyright：-一个自动的代码检查工具.  提高开发人员的生产力. 
- [SmartDec Scanner](https://smartdecscanner.com/) :copyright: - SAST tool which is capable of identifying vulnerabilities and undocumented features. The analyzer scans the source code and executables without debug info (i.e. binaries). Supports: Java/Scala/Kotlin, PHP, C#, JavaScript, TypeScript, VBScript, HTML5, Python, Perl, C/C++, Objective-C/Swift, PL/SQL, T-SQL, ABAP, 1C, Apex, Go, Ruby, Groovy, Delphi, VBA, Visual Basic 6, Solidity, Vyper, COBOL. 
- [Snyk](https://snyk.io/) ：copyright：-漏洞扫描程序，用于依赖node.js应用程序（开放源代码项目免费） 
- [SonarCloud](https://sonarcloud.io)  ：copyright：-基于多语言云的静态代码分析.  历史，趋势，安全热点，请求请求分析等.  免费开源. 
- [SonarLint for Visual Studio](https://vs.sonarlint.org/) -SonarLint是Visual Studio 2015和2017的扩展，可为开发人员提供实时反馈，以反馈有关.NET代码中注入的新错误和质量问题. 
- [SonarQube](http://www.sonarqube.org/) -SonarQube是管理代码质量的开放平台. 
- [standard](http://standardjs.com/) -一个npm模块，用于检查Javascript Styleguide问题 
- [styler](https://styler.r-lib.org/) -R源代码文件的格式和R代码的漂亮打印. 
- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) -用于重新格式化Swift代码的库和命令行格式化工具 
- [Synopsys](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - A commercial static analysis platform that allows for scanning of multiple languages (C/C++, Android, C#, Java, JS, PHP, Python, Node.JS, Ruby, Fortran, and Swift) 
- [Teamscale](http://www.teamscale.com/)  ：copyright：-支持超过25种语言并直接集成IDE的静态和动态分析工具.  可根据要求免费托管开源项目.  提供免费的学术许可证. 
- [TscanCode](https://github.com/Tencent/TscanCode) - A fast and accurate static analysis solution for C/C++, C#, Lua codes provided by Tencent. Using GPLv3 license. 
- [Undebt](https://github.com/Yelp/undebt) -基于语言的工具，可基于简单的模式定义进行大规模，自动，可编程的重构 
- [Unibeautify](https://unibeautify.com/)  -带有GitHub应用的通用代码美化器.  支持HTML，CSS，JavaScript，TypeScript，JSX，Vue，C ++，Go，Objective-C，Java，Python，PHP，GraphQL，Markdown等. 
- [Upsource](https://www.jetbrains.com/upsource/) ：copyright：-具有Java，PHP，JavaScript和Kotlin的静态代码分析和代码感知导航的代码审查工具. 
- [Veracode](http://www.veracode.com/products/static-analysis-sast/static-code-analysis)  ：copyright：-在不需要源代码的情况下查找二进制文件和字节码中的缺陷.  支持所有主要的编程语言：Java，.NET，JavaScript，Swift，Objective-C，C，C ++等. 
- [Violations Lib](https://github.com/tomasbjerre/violations-lib)  -用于从静态代码分析中解析报告文件的Java库.  由许多Jenkins，Maven和Gradle插件使用. 
- [WALA](http://wala.sourceforge.net) -Java字节码和相关语言以及JavaScript的静态分析功能 
- [WhiteHat Application Security Platform](https://www.whitehatsec.com/platform/static-application-security-testing/) ：copyright：-WhiteHat Scout（针对开发人员）与WhiteHat Sentinel Source（针对运营）相结合，支持WhiteHat Top 40和OWASP Top 10. 
- [Wotan](https://github.com/fimbullinter/wotan) -可插拔的TypeScript和JavaScript linter 
- [Xanitizer](https://xanitizer.com/) -Xanitizer在Java / Scala Web应用程序中发现安全漏洞. 
- [Xanitizer](https://xanitizer.com/) ：copyright：-Xanitizer在Java / Scala Web应用程序中发现安全漏洞. 
- [XCode](https://developer.apple.com/xcode/) ：copyright：-XCode为 [Clang's](http://clang-analyzer.llvm.org/xcode.html) 静态代码分析器（C / C ++，Obj-C） 


## Other



<h2 id="binary">二进制文件</h2>

- [BinSkim](https://github.com/Microsoft/binskim) -二进制静态分析工具，可为Windows可移植可执行文件提供安全性和正确性结果.
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) -cwe_checker在二进制可执行文件中找到易受攻击的模式.
- [Jakstab](https://github.com/jkinder/jakstab) -Jakstab是一个基于抽象解释的集成反汇编和静态分析框架，用于设计可执行文件的分析并恢复可靠的控制流程图.
- [Manalyze](https://github.com/JusticeRage/Manalyze) -静态分析器，用于检查可移植可执行文件中是否包含恶意内容.
- [Twiggy](https://rustwasm.github.io/twiggy/)  -分析二进制文件的调用图以分析代码大小.  目标是减少二进制文件.


<h2 id="buildtool">构建工具</h2>

- [checkmake](https://github.com/mrtazz/checkmake) -生成文件的Linter / Analyzer


<h2 id="css"> CSS / SASS / SCSS </h2>

- [CSS Stats](https://cssstats.com/) -样式表上可能有趣的统计信息
- [CSSLint](http://csslint.net/) -是否进行基本语法检查并发现有问题的模式或效率低下的迹象
- [GraphMyCSS.com](https://graphmycss.com) -CSS特异性图生成器
- [Parker](https://github.com/katiefenn/parker) -样式表分析工具
- [Project Wallace CSS Analyzer](https://www.projectwallace.com/) -CSS的分析，属于 [Project Wallace](https://www.projectwallace.com)
- [sass-lint](https://github.com/sasstools/sass-lint) ：warning：-适用于sass和scss语法的仅节点Sass linter.
- [scsslint](https://github.com/brigade/scss-lint) ：警告：-Linter用于SCSS文件
- [Specificity Graph](https://jonassebastianohlsson.com/specificity-graph/) -CSS特异性图生成器
- [Stylelint](http://stylelint.io/) -用于SCSS / CSS文件的Linter


<h2 id="configfile">配置文件</h2>

- [dotenv-linter](https://dotenv-linter.readthedocs.io/en/latest/) -像魅力一样整理dotenv文件.
- [gixy](https://github.com/yandex/gixy)  -分析Nginx配置的工具.  主要目标是防止配置错误并自动进行缺陷检测.


<h2 id="configmanagement">配置管理</h2>

- [ansible-lint](https://docs.ansible.com/ansible-lint/) -检查剧本中可能会改善的做法和行为
- [cfn-lint](https://github.com/awslabs/cfn-python-lint) -AWS Labs CloudFormation linter.
- [cfn_nag](https://github.com/stelligent/cfn_nag) -适用于AWS CloudFormation模板的模板.
- [checkov](https://www.checkov.io/) -用于Terraform文件的静态分析工具（tf&gt; = v0.12），可防止在构建时云配置错误.
- [cookstyle](https://github.com/chef/cookstyle) -Cookstyle是基于RuboCop Ruby linting工具用于厨师食谱的整理工具
- [foodcritic](http://www.foodcritic.io/) -检查主厨食谱中常见问题的皮棉工具.
- [Puppet Lint](https://github.com/rodjek/puppet-lint) -检查您的人偶清单是否符合样式指南.
- [terraform-compliance](https://terraform-compliance.com) -针对Terraform的轻量级，遵循合规性和安全性的BDD测试框架.
- [terrascan](https://github.com/cesar-rodriguez/terrascan) -收集用于Terraform模板的静态代码分析的安全性和最佳实践测试.
- [tflint](https://github.com/wata727/tflint) -Terraform linter，用于检测“ terraform plan”无法检测到的错误.


<h2 id="container">货柜</h2>

- [anchore](https://anchore.io/) -发现，分析和验证容器映像
- [clair](https://github.com/coreos/clair) -容器的漏洞静态分析
- [collector](https://github.com/banyanops/collector) -在容器内运行任意脚本，并收集有用的信息
- [dagda](https://github.com/eliasgranderubio/dagda) -对Docker映像/容器中的已知漏洞执行静态分析.
- [Docker Label Inspector](https://github.com/garethr/docker-label-inspector) -整理和验证Dockerfile标签
- [Haskell Dockerfile Linter](https://github.com/lukasmartinelli/hadolint) -更智能的Dockerfile Linter，可帮助您构建最佳实践Docker映像
- [kube-score](https://kube-score.com/) -Kubernetes对象定义的静态代码分析.


<h2 id="deno">天野</h2>

- [deno_lint](https://github.com/denoland/deno_lint) -迪诺的官方短绒


<h2 id="gherkin">小黄瓜</h2>

- [gherkin-lint](https://github.com/vsiakka/gherkin-lint) -用Java语言编写的小黄瓜语法的短毛猫.


<h2 id="html">的HTML </h2>

- [HTML Inspector](https://github.com/philipwalton/html-inspector) ：警告：-HTML Inspector是一种代码质量工具，可帮助您和您的团队编写更好的标记.
- [HTML Tidy](http://www.html-tidy.org/) -通过修复标记错误并将旧代码升级为现代标准来纠正和清理HTML和XML文档.
- [HTMLHint](https://htmlhint.com/) -用于HTML的静态代码分析工具


<h2 id="ide"> IDE插件</h2>

- [ale](https://github.com/w0rp/ale) -Vim和NeoVim的异步Lint引擎，支持多种语言
- [Android Studio](https://developer.android.com/studio) -基于IntelliJ IDEA，并捆绑了适用于Android的工具，包括Android Lint.
- [Attackflow Extension](https://www.attackflow.com/Extension) ：copyright：-用于Visual Studio的Attackflow插件，它使开发人员无需任何先验知识就可以在源代码中实时发现关键的安全错误.
- [DevSkim](https://github.com/Microsoft/DevSkim)  -在线实时安全分析.  与多种编程语言和IDE（VS，VS Code，Sublime Text等）配合使用.
- [IntelliJ IDEA](https://www.jetbrains.com/idea/) ：copyright：-与Java和Kotlin的大量检查捆绑在一起，包括重构，格式化等工具.
- [vint](https://github.com/Kuniwak/vint) -由Python实现的快速且高度可扩展的Vim脚本语言Lint.


<h2 id="latex">胶乳</h2>

- [ChkTeX](http://www.nongnu.org/chktex/) -用于LaTex的短绒棉布，可捕获LaTeX监督的某些印刷错误.
- [lacheck](https://www.ctan.org/pkg/lacheck) -查找LaTeX文档中常见错误的工具.


<h2 id="make">制作文件</h2>

- [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) -FreeBSD和DragonFlyBSD端口目录的验证程序.


<h2 id="markdown">降价促销</h2>

- [markdownlint](https://github.com/DavidAnson/markdownlint) - Node.js -based style checker and lint tool for Markdown/CommonMark files.
- [mdl](https://github.com/mivok/markdownlint) -检查Markdown文件和标志样式问题的工具.
- [remark-lint](https://remark.js.org/) -用JavaScript编写的可插入Markdown代码样式的linter.


<h2 id="mobile">移动</h2>

- [Android Lint](http://tools.android.com/tips/lint) -在Android项目上运行静态分析.
- [android-lint-summary](https://passy.github.io/android-lint-summary/) -将多个项目的棉绒错误合并为一个输出，立即检查多个子项目的棉绒结果.
- [FlowDroid](https://github.com/secure-software-engineering/FlowDroid) -适用于Android应用程序的静态污点分析工具
- [paprika](https://github.com/GeoffreyHecht/paprika) -一个工具包，用于检测已分析的Android应用程序中的某些代码异味.
- [qark](https://github.com/linkedin/qark) -查找多个与安全相关的Android应用程序漏洞的工具


<h2 id="package">配套</h2>

- [lintian](https://lintian.debian.org/) -Debian软件包的静态分析工具
- [rpmlint](https://github.com/rpm-software-management/rpmlint) -用于检查rpm包中常见错误的工具


<h2 id="protobuf">协议缓冲区</h2>

- [protolint](https://github.com/yoheimuta/protolint) -可插入的linter和fixer，用于实施协议缓冲区样式和约定.


<h2 id="support">配套工具</h2>

- [LibVCS4j](https://github.com/uni-bremen-agst/libvcs4j) -一个Java库，通过为不同的版本控制系统和问题跟踪器提供通用的API，允许现有工具分析软件系统的演变.


<h2 id="template">范本语言</h2>

- [ember-template-lint](https://github.com/rwjblue/ember-template-lint) -灰烬的Ember或Handlebars模板.
- [haml-lint](https://github.com/sds/haml-lint) -用于编写干净且一致的HAML的工具
- [slim-lint](https://github.com/sds/slim-lint) -用于分析Slim模板的可配置工具
- [yamllint](https://yamllint.readthedocs.io/) -检查YAML文件的语法有效性，键重复和外观问题，例如行长，尾随空格和缩进.


<h2 id="translation">Translation</h2>

- [dennis](https://github.com/willkg/dennis/) -一组用于处理PO文件的实用程序，以简化开发并提高质量.


<h2 id="service">网页服务</h2>

- [Codacy](https://www.codacy.com/) ：copyright：-代码分析可以更快地发布更好的代码.
- [Code Climate](https://codeclimate.com/) ：copyright：-开放和可扩展的静态分析平台，适合所有人.
- [Code Inspector](https://www.code-inspector.com) ：copyright：-支持10多种语言的代码质量和技术债务管理平台.
- [CodeFactor](https://codefactor.io) ：copyright：-在GitHub或BitBucket上针对仓库的自动代码分析.
- [CodeFlow](https://www.getcodeflow.com)  ：copyright：-自动代码分析工具来处理技术深度.  与Bitbucket和Gitlab集成.  （对于开源项目免费）
- [kiuwan](https://www.kiuwan.com/) ：copyright：-云中的软件分析支持超过22种编程语言.
- [Landscape](https://landscape.io/) ：warning：：copyright：-Python的静态代码分析
- [Reshift](https://www.reshiftsecurity.com/) ：copyright：-用于检测和管理Java安全漏洞的源代码分析工具.
- [Scrutinizer](https://scrutinizer-ci.com/) ：copyright：-可与GitHub集成的专有代码质量检查器


<h2 id="writing">写作</h2>

- [After the Deadline](https://afterthedeadline.com/) ：警告：-拼写，样式和语法检查器
- [codespell](https://github.com/codespell-project/codespell) -检查常见拼写错误的代码
- [languagetool](https://languagetool.org/)  -25种以上语言的样式和语法检查器.  它会发现许多简单的拼写检查器无法检测到的错误.
- [misspell-fixer](https://github.com/vlajos/misspell-fixer) -在源代码中修复常见拼写错误，错别字的快速工具
- [Misspelled Words In Context](http://jwilk.net/software/mwic) -拼写检查器，对可能的拼写错误进行分组并在上下文中显示它们
- [proselint](http://proselint.com/) -英文散文短篇小说，着重于写作风格而不是语法.
- [vale](https://github.com/ValeLint/vale) -用于散文的可自定义的，具有语法意识的linter.
- [write-good](https://github.com/btford/write-good) -重点消除“狡猾的单词”的短毛猫.


## More collections

- [go-tools](https://github.com/dominikh/go-tools) -使用Go代码的工具和库的集合，包括短绒和静态分析
- [linters](https://github.com/mcandre/linters) -静态代码分析简介
- [php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools) -有用的PHP静态分析工具的完整列表
- [Tools for C/C++](https://www.peerlyst.com/posts/a-list-of-static-analysis-tools-for-c-c-peerlyst?utm_source=twitter&utm_medium=social&utm_content=peerlyst_post&utm_campaign=peerlyst_resources) -用于C / C ++的静态分析工具列表
- [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) -用于静态代码分析的工具列表.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Matthias Endler](https://endler.dev) 放弃了此作品的所有版权以及相关或邻近的权利.
标题图片 [Designed by Freepik](http://www.freepik.com).
