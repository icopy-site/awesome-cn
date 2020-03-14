<div class="github-widget" data-repo="ironcev/awesome-roslyn"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
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
很棒的书，让您从Roslyn有了一个良好的开端.

- [Roslyn Succinctly](https://www.syncfusion.com/ebooks/roslyn)  -*亚历山德罗·德尔·索尔（Alessandro Del Sole）提供的免费电子书，也是一本完美的书.  解释Roslyn API，然后重点研究编写分析器和重构.
- [.NET Development Using the Compiler API](https://www.apress.com/la/book/9781484221105)  -Jason Bock所著.  除了分析器和重构之外，它还解释了脚本API，并提供了有关Compiler API未来的有趣观点.
- [Roslyn Cookbook](https://www.packtpub.com/application-development/roslyn-cookbook) - Book by Manish Vasani, a member of the Roslyn analyzers team. After covering analyzers, refactorings, and scripting in detail, the book goes in-depth explaining how to develop new C# language features and contribute to the Roslyn source code.

## Tutorials
很棒的在线教程可以帮助您编写第一个分析器和代码修复.

- [Learn Roslyn Now](https://joshvarty.com/learn-roslyn-now/)  -探索Roslyn编译器API的一系列博客文章.  它通过一些独立的示例介绍了罗斯林的力量.  完美的教程以:-)开始
- [How To Write a C# Analyzer and Code Fix](https://github.com/dotnet/roslyn/wiki/How-To-Write-a-C%23-Analyzer-and-Code-Fix) -所有Roslyn教程的母亲:-)语法，语义分析以及语法转换的逐步介绍.
- [C# and Visual Basic - Use Roslyn to Write a Live Code Analyzer for Your API](https://msdn.microsoft.com/en-us/magazine/dn879356.aspx) -关于编写代码分析器的MSDN文章较旧，但仍未过时.
- [C# - Adding a Code Fix to Your Roslyn Analyzer](https://msdn.microsoft.com/en-us/magazine/dn904670.aspx)  -上一篇MSDN文章的续集.  代码修复的详细介绍.

## Open Source Projects
在Roslyn之上构建的很棒的开源项目.

- [Bridge](https://github.com/bridgedotnet/Bridge) - C# to JavaScript transpiler. Write modern mobile and web apps in C# and run them anywhere in JavaScript.
- [Code Converter](https://github.com/icsharpcode/CodeConverter/) - C# to VB.NET and VB.NET to C# transpiler.
- [CodeAnalysis.CSharp.PatternMatching](https://github.com/pvginkel/Microsoft.CodeAnalysis.CSharp.PatternMatching) - Intuitive pattern matching for Roslyn syntax trees. Simplifies C# syntax and semantic analysis.
- [CodeGeneration.Roslyn](https://github.com/AArnott/CodeGeneration.Roslyn) -在具有设计时支持的构建过程中基于Roslyn的代码生成.
- [dotnet-script](https://github.com/filipw/dotnet-script) - Runs C# scripts from the .NET CLI, defines NuGet packages inline and edit/debugs them in VS Code.
- [FlubuCore](https://github.com/dotnetcore/FlubuCore) - Cross platform build automation tool for building projects and executing deployment scripts using C# code.
- [MirrorSharp](https://github.com/ashmind/mirrorsharp) - Online C#, VB.NET, and F# code editor. Features code completion, method signature help, quick fixes, and diagnostics.
- [OmniSharp](http://www.omnisharp.net/)  -在您选择的编辑器中启用跨平台.NET开发.  一个开源项目系列，每个都有一个目标：在您选择的编辑器中提供出色的.NET体验.
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
很棒的开源分析器，代码修复和重构.

- [.NET Analyzers](https://github.com/DotNetAnalyzers)  -GitHub组织，用于开发Roslyn分析仪.  组织内的各种存储库涵盖了ASP.NET Core，WPF，IDisposable，System.Reflection的用法等分析器.
- [.NET Compiler Platform ("Roslyn") Analyzers](https://github.com/dotnet/roslyn-analyzers)  -由罗斯林团队开发的诊断分析仪.  最初是为了帮助充实静态分析API的设计和实现而开发的.  分析器涵盖了代码质量，.NET Core，桌面.NET Framework，代码注释等.
- [Code Cracker](https://github.com/code-cracker/code-cracker) - Analyzer library for C# and VB.NET. Offers diagnostics in many categories like performance, coding styles, as well as some basic refactorings.
- [CSharpGuidelinesAnalyzer](https://github.com/bkoelman/CSharpGuidelinesAnalyzer) - Reports diagnostics for C# coding guidelines (https://csharpcodingguidelines.com/).
- [ErrorProne.NET](https://github.com/SergeyTeplyakov/ErrorProne.NET) - Set of analyzers and code fixes focusing on the correctness and performance of C# programs. Inspired with Google's [Error Prone](https://github.com/google/error-prone).
- [Refactoring Essentials for Visual Studio](https://github.com/icsharpcode/RefactoringEssentials/) - Refactorings, analyzers and code fixes for C# and VB.NET.
- [Roslyn Clr Heap Allocation Analyzer](https://github.com/Microsoft/RoslynClrHeapAllocationAnalyzer) - C# heap allocation analyzer that can detect explicit and many implicit allocations like boxing, closures, implicit delegate creations, etc.
- [Roslynator](https://github.com/JosefPihrt/Roslynator) - Collection of 190+ analyzers and 190+ refactorings for C#. Covers coding style, code readability and simplification, removing redundancies, fixing compiler errors, and many more.
- [SonarC#](https://github.com/SonarSource/sonar-csharp) - Static code analyzer for C# language used as an extension for the SonarQube platform.
- [StyleCop Analyzers for the .NET Compiler Platform](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) -将StyleCop规则移植到罗斯林.
- [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics)  -收集代码质量分析器.  涵盖异步方法的使用，标志枚举，异常处理中的最佳实践以及许多其他代码质量检查.

## Libraries and Frameworks for Testing Analyzers, Code Fixes, and Refactorings
很棒的库和框架，用于测试分析器，代码修复和重构.

- [Microsoft.CodeAnalysis.Testing](https://github.com/dotnet/roslyn-sdk/tree/master/src/Microsoft.CodeAnalysis.Testing)  -用于使用NUnit，xUnit和MSTest框架测试分析器和代码修复的库.  一部分 [Roslyn SDK](https://github.com/dotnet/roslyn-sdk).
- [RoslynTestKit](https://github.com/cezarypiatek/RoslynTestKit)  -轻量级框架，用于为分析器，代码修复，重构和完成提供程序编写单元测试.  它是不可知的单元测试框架.

## Blog Posts and Articles
很棒的博客文章和在线文章，涵盖了各种主题，例如性能，Roslyn内部知识等.

- [Inside the .NET Compiler Platform – Performance Considerations during Syntax Analysis (#SpeakRoslyn)](https://robinsedlaczek.com/2015/04/29/inside-the-net-compiler-platform-performance-considerations-during-syntax-analysis-speakroslyn/) -深入研究Roslyn的性能，重点是内存消耗.
- [Persistence, Facades and Roslyn's Red-Green Trees](https://blogs.msdn.microsoft.com/ericlippert/2012/06/08/persistence-facades-and-roslyns-red-green-trees/)  -启发性的介绍，介绍了罗斯林团队如何通过廉价的父级引用和许多其他优点实现不可变，可重用的树.  Quote：“但是在罗斯林团队中，我们通常会做不可能的事情” :-)
- [ReSharper and Roslyn: Q&A](https://blog.jetbrains.com/dotnet/2014/04/10/resharper-and-roslyn-qa/)  -很好的解释了为什么ReSharper不会使用Roslyn.  包括有关静态代码分析的良好讨论以及Roslyn的一些限制.
- [Roslyn performance (Matt Gertz)](https://blogs.msdn.microsoft.com/csharpfaq/2014/01/15/roslyn-performance-matt-gertz/) -了解罗斯林团队如何处理评估和实现绩效的话题.

## Talks
关于罗斯林的精彩演讲.

- [The Power of Roslyn](https://www.youtube.com/watch?v=nXljhGDokqA) -Kasey Uhlenhuth在NDC Oslo 2018上的精彩演讲，涵盖了Roslyn的要点和API以及用于构建代码分析器和修复程序的工具.

## Contribute

 欢迎做出贡献：-)目标是建立由社区驱动的，精选的罗斯林资源的分类收藏.  投稿前，请务必阅读 [contribution guidelines](https://github.com/ironcev/awesome-roslyn/blob/master/contributing.md).

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，IgorRončević放弃了该作品的所有版权以及相关或邻近的权利.
