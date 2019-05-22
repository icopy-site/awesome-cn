<div class="github-widget" data-repo="ironcev/awesome-roslyn"></div>
<p align="center">
    <a href="https://github.com/dotnet/roslyn">
        <img src="https://raw.githubusercontent.com/ironcev/awesome-roslyn/master/images/awesome-roslyn-logo.png" alt="Awesome Roslyn" width="500">
    </a>
</p>

<p align="center">
    <a href="https://github.com/sindresorhus/awesome">
        <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome">
    </a>
</p>

&gt; Roslyn书籍，教程，开源项目，分析器，代码修复和重构的精选列表.

罗斯林，正式命名 [.NET Compiler Platform](https://en.wikipedia.org/wiki/.NET_Compiler_Platform), is a set of open-source compilers and code analysis APIs for C# and Visual Basic .NET languages.



## Books
很棒的书籍，为您提供Roslyn的良好开端.

- [Roslyn Succinctly](https://www.syncfusion.com/ebooks/roslyn) - *Free e-book* by Alessandro Del Sole and the perfect book to start with. Explains Roslyn APIs and afterward focuses on writing analyzers and refactorings.
- [.NET Development Using the Compiler API](https://www.apress.com/la/book/9781484221105)   - 由Jason Bock预订.  除了分析器和重构之外，它还解释了脚本API，并对Compiler API的未来进行了有趣的反思.
- [Roslyn Cookbook](https://www.packtpub.com/application-development/roslyn-cookbook) - Book by Manish Vasani, a member of the Roslyn analyzers team. After covering analyzers, refactorings, and scripting in detail, the book goes in-depth explaining how to develop new C# language features and contribute to the Roslyn source code.

## Tutorials
非常棒的在线教程，可帮助您编写第一个分析器和代码修复程序.

- [Learn Roslyn Now](https://joshvarty.com/learn-roslyn-now/)   - 探索Roslyn编译器API的系列博客文章.  它通过小型自成一体的例子介绍了罗斯林的力量.  一个完美的教程开始:-)
- [How To Write a C# Analyzer and Code Fix](https://github.com/dotnet/roslyn/wiki/How-To-Write-a-C%23-Analyzer-and-Code-Fix) - 所有Roslyn教程的母亲:-)对语法和语义分析以及语法转换进行实际的逐步介绍.
- [C# and Visual Basic - Use Roslyn to Write a Live Code Analyzer for Your API](https://msdn.microsoft.com/en-us/magazine/dn879356.aspx) - 关于编写代码分析器的旧版但仍未过时，非常详细的MSDN文章.
- [C# - Adding a Code Fix to Your Roslyn Analyzer](https://msdn.microsoft.com/en-us/magazine/dn904670.aspx)   - 上一篇MSDN文章的续集.  详细介绍了代码修复.

## Open Source Projects
在Roslyn之上构建的令人敬畏的开源项目.

- [Bridge](https://github.com/bridgedotnet/Bridge) - C# to JavaScript transpiler. Write modern mobile and web apps in C# and run them anywhere in JavaScript.
- [Code Converter](https://github.com/icsharpcode/CodeConverter/) - C# to VB.NET and VB.NET to C# transpiler.
- [CodeAnalysis.CSharp.PatternMatching](https://github.com/pvginkel/Microsoft.CodeAnalysis.CSharp.PatternMatching) - Intuitive pattern matching for Roslyn syntax trees. Simplifies C# syntax and semantic analysis.
- [CodeGeneration.Roslyn](https://github.com/AArnott/CodeGeneration.Roslyn) - 在构建期间基于Roslyn的代码生成，具有设计时支持.
- [dotnet-script](https://github.com/filipw/dotnet-script) - Runs C# scripts from the .NET CLI, defines NuGet packages inline and edit/debugs them in VS Code.
- [FlubuCore](https://github.com/flubu-core/flubu.core) - Cross platform build automation tool for building projects and executing deployment scripts using C# code.
- [MirrorSharp](https://github.com/ashmind/mirrorsharp) - Online C#, VB.NET, and F# code editor. Features code completion, method signature help, quick fixes, and diagnostics.
- [OmniSharp](http://www.omnisharp.net/)   - 在您选择的编辑器中启用跨平台.NET开发.  一系列开源项目，每个项目都有一个目标：在您选择的编辑器中实现出色的.NET体验.
- [roslyn-linq-rewrite](https://github.com/antiufo/roslyn-linq-rewrite) - Compiles C# code by first rewriting the syntax trees of LINQ expressions using plain procedural code. This increases performance by minimizes heap allocations and dynamic dispatch.
- [RoslynPad](https://roslynpad.net/) - Cross-platform C# editor. Features code completion, method signature help, quick fixes, and diagnostics.
- [RoslynQuoter](https://github.com/KirillOsenkov/RoslynQuoter) - Online tool that for a given C# program generates syntax tree API calls that construct syntax tree of that program.
- [scriptcs](http://scriptcs.net/) - Turns C# into a powerful scripting tool. Features C# REPL, installation of NuGet packages, and execution of scripts with a single line of code.
- [Scripty](https://github.com/daveaglick/Scripty) - Tool to use Roslyn-powered C# scripts for code generation. You can think of it as a scripted alternative to T4 templates.
- [Sharpen](http://sharpen.rocks) - Visual Studio extension that intelligently introduces new C# language features into your existing code base.
- [SharpLab](https://sharplab.io/) - .NET code playground. Displays intermediate steps and results of code compilation. Shows the code as compiler sees it. Allows selecting different branches and versions of Roslyn. Runs C#, VB.NET, and F# code in the browser.
- [Testura.Code](https://github.com/Testura/Testura.Code) - Wrapper around the Roslyn API used for generation, saving, and compiling C# code. Provides methods and helpers to generate classes, methods, statements, and expressions.
- [Uno SourceGenerator](https://github.com/nventive/Uno.SourceGeneration) - C# source code generator based on a project being built, using all of its syntactic and semantic model information.

## Open Source Analyzers, Code Fixes, and Refactorings
令人敬畏的开源分析器，代码修复和重构.

- [.NET Analyzers](https://github.com/DotNetAnalyzers)   -  GitHub组织开发Roslyn分析仪.  组织内的各种存储库涵盖ASP.NET Core，WPF，IDisposable，System.Reflection的使用等分析器.
- [.NET Compiler Platform ("Roslyn") Analyzers](https://github.com/dotnet/roslyn-analyzers)   -  Roslyn团队开发的诊断分析仪.  最初开发用于帮助充实静态分析API的设计和实现.  分析器涵盖代码质量，.NET Core，桌面.NET Framework，代码注释等.
- [Code Cracker](https://github.com/code-cracker/code-cracker) - Analyzer library for C# and VB.NET. Offers diagnostics in many categories like performance, coding styles, as well as some basic refactorings.
- [CSharpGuidelinesAnalyzer](https://github.com/bkoelman/CSharpGuidelinesAnalyzer) - Reports diagnostics for C# coding guidelines (https://csharpcodingguidelines.com/).
- [Refactoring Essentials for Visual Studio](https://github.com/icsharpcode/RefactoringEssentials/) - Refactorings, analyzers and code fixes for C# and VB.NET.
- [Roslyn Clr Heap Allocation Analyzer](https://github.com/Microsoft/RoslynClrHeapAllocationAnalyzer) - C# heap allocation analyzer that can detect explicit and many implicit allocations like boxing, closures, implicit delegate creations, etc.
- [Roslynator](https://github.com/JosefPihrt/Roslynator) - Collection of 190+ analyzers and 190+ refactorings for C#. Covers coding style, code readability and simplification, removing redundancies, fixing compiler errors, and many more.
- [SonarC#](https://github.com/SonarSource/sonar-csharp) - Static code analyzer for C# language used as an extension for the SonarQube platform.
- [StyleCop Analyzers for the .NET Compiler Platform](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) -  StyleCop端口规则为Roslyn.
- [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics)   - 代码质量分析器的收集.  涵盖异步方法，标记枚举，异常处理的最佳实践以及许多其他代码质量检查的用法.

## Blog Posts and Articles
精彩的博客文章和在线文章，涵盖各种主题，如性能，Roslyn内部和类似.

- [Inside the .NET Compiler Platform – Performance Considerations during Syntax Analysis (#SpeakRoslyn)](https://robinsedlaczek.com/2015/04/29/inside-the-net-compiler-platform-performance-considerations-during-syntax-analysis-speakroslyn/) - 深入了解Roslyn的性能，重点关注内存消耗.
- [Persistence, Facades and Roslyn's Red-Green Trees](https://blogs.msdn.microsoft.com/ericlippert/2012/06/08/persistence-facades-and-roslyns-red-green-trees/)   - 鼓励介绍罗斯林团队如何使用便宜的父母参考和许多其他好东西实现不可变，可重复使用的树木.  引用：“但是在Roslyn团队，我们经常做不可能的事情”:-)
- [ReSharper and Roslyn: Q&A](https://blog.jetbrains.com/dotnet/2014/04/10/resharper-and-roslyn-qa/)   - 很好的解释为什么ReSharper不会使用Roslyn.  包括关于静态代码分析和Roslyn的一些限制的良好讨论.
- [Roslyn performance (Matt Gertz)](https://blogs.msdn.microsoft.com/csharpfaq/2014/01/15/roslyn-performance-matt-gertz/) - 洞察罗斯林团队如何处理评估和实现绩效的主题.

## Talks
关于罗斯林的公开谈话.

- [The Power of Roslyn](https://www.youtube.com/watch?v=nXljhGDokqA) -  Kasey Uhlenhuth在NDC奥斯陆2018年的精彩演讲，内容涉及Roslyn必需品和用于构建代码分析器和修复的API和工具.

## Contribute

 欢迎贡献:-)目标是建立一个分类的社区驱动的令人敬畏的Roslyn资源集合.  在做出贡献之前，请务必阅读 [contribution guidelines](https://github.com/ironcev/awesome-roslyn/blob/master/contributing.md).

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，IgorRončević已放弃所有版权及相关或相邻的权利.
