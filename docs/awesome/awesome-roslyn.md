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

&gt; Roslyn 书籍、教程、开源项目、分析器、代码修复、重构和源代码生成器的精选列表.

罗斯林，正式命名 [.NET Compiler Platform](https://en.wikipedia.org/wiki/.NET_Compiler_Platform), is a set of open-source compilers and code analysis APIs for C# and Visual Basic .NET languages.



## Books
很棒的书籍，让您在 Roslyn 上有个良好的开端.

- [Roslyn Succinctly](https://www.syncfusion.com/ebooks/roslyn)  - *Alessandro Del Sole 的*免费电子书*，是一本完美的入门书. 解释 Roslyn API，然后专注于编写分析器和重构.
- [.NET Development Using the Compiler API](https://www.apress.com/la/book/9781484221105)  - Jason Bock 的书. 除了分析器和重构之外，它还解释了脚本 API，并对 Compiler API 的未来进行了有趣的思考.
- [Roslyn Cookbook](https://www.packtpub.com/application-development/roslyn-cookbook) - Book by Manish Vasani, a member of the Roslyn analyzers team. After covering analyzers, refactorings, and scripting in detail, the book goes in-depth explaining how to develop new C# language features and contribute to the Roslyn source code.

## Tutorials
很棒的在线教程，可帮助您编写第一个分析器、代码修复程序和源代码生成器.

- [Learn Roslyn Now](https://joshvarty.com/learn-roslyn-now/)  - 探索 Roslyn 编译器 API 的系列博文. 它通过独立的小示例介绍了 Roslyn 的强大功能. 一个完美的教程开始:-)
- [How To Write a C# Analyzer and Code Fix](https://github.com/dotnet/roslyn/blob/master/docs/wiki/How-To-Write-a-C%23-Analyzer-and-Code-Fix.md) - 所有 Roslyn 教程之母 :-) 对语法和语义分析以及语法转换的逼真逐步介绍.
- [C# and Visual Basic - Use Roslyn to Write a Live Code Analyzer for Your API](https://msdn.microsoft.com/en-us/magazine/dn879356.aspx) - 较旧但仍未过时、非常详细的关于编写代码分析器的 MSDN 文章.
- [C# - Adding a Code Fix to Your Roslyn Analyzer](https://msdn.microsoft.com/en-us/magazine/dn904670.aspx)  - 上一篇 MSDN 文章的续集. 代码修复的详细介绍.
- [Introducing C# Source Generators](https://devblogs.microsoft.com/dotnet/introducing-c-source-generators/) - Original announcement of the C# 9.0 Source Generators feature. Explains what source generators are, in which scenarios they are useful, and shows how to write a simple source generator.
- [New C# Source Generator Samples](https://devblogs.microsoft.com/dotnet/new-c-source-generator-samples/) - 关于如何编写由额外的非代码文件（如 CSV 文件或 [Mustache](https://mustache.github.io/) 模板.
- [C# Source Generators](https://github.com/amis92/csharp-source-generators)  - 其他学习资源、示例以及实验和生产源生成器的综合列表. 一旦你掌握了基础知识，这是一个完美的参考.

## Open Source Projects
建立在 Roslyn 之上的很棒的开源项目.

- [Bridge](https://github.com/bridgedotnet/Bridge) - C# to JavaScript transpiler. Write modern mobile and web apps in C# and run them anywhere in JavaScript.
- [Code Converter](https://github.com/icsharpcode/CodeConverter/) - C# to VB.NET and VB.NET to C# transpiler.
- [CodeAnalysis.CSharp.PatternMatching](https://github.com/pvginkel/Microsoft.CodeAnalysis.CSharp.PatternMatching) - Intuitive pattern matching for Roslyn syntax trees. Simplifies C# syntax and semantic analysis.
- [CodeGeneration.Roslyn](https://github.com/AArnott/CodeGeneration.Roslyn) - 在具有设计时支持的构建期间基于 Roslyn 的代码生成.
- [dotnet-script](https://github.com/filipw/dotnet-script) - Runs C# scripts from the .NET CLI, defines NuGet packages inline and edit/debugs them in VS Code.
- [FlubuCore](https://github.com/dotnetcore/FlubuCore) - Cross platform build automation tool for building projects and executing deployment scripts using C# code.
- [MirrorSharp](https://github.com/ashmind/mirrorsharp) - Online C#, VB.NET, and F# code editor. Features code completion, method signature help, quick fixes, and diagnostics.
- [OmniSharp](http://www.omnisharp.net/)  - 在您选择的编辑器中启用跨平台 .NET 开发. 一系列开源项目，每个项目都有一个目标：在您选择的编辑器中实现出色的 .NET 体验.
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
很棒的开源分析器、代码修复和重构.

- [.NET Analyzers](https://github.com/DotNetAnalyzers)  - 用于开发 Roslyn 分析器的 GitHub 组织. 组织内的各种存储库涵盖 ASP.NET Core、WPF、IDisposable 的分析器、System.Reflection 的用法等.
- [.NET Compiler Platform ("Roslyn") Analyzers](https://github.com/dotnet/roslyn-analyzers)  - Roslyn 团队开发的诊断分析仪. 最初开发是为了帮助充实静态分析 API 的设计和实现. 分析器涵盖代码质量、.NET Core、桌面 .NET Framework、代码注释等.
- [Code Cracker](https://github.com/code-cracker/code-cracker) - Analyzer library for C# and VB.NET. Offers diagnostics in many categories like performance, coding styles, as well as some basic refactorings.
- [CSharpGuidelinesAnalyzer](https://github.com/bkoelman/CSharpGuidelinesAnalyzer) - Reports diagnostics for C# coding guidelines (https://csharpcodingguidelines.com/).
- [ErrorProne.NET](https://github.com/SergeyTeplyakov/ErrorProne.NET) - Set of analyzers and code fixes focusing on the correctness and performance of C# programs. Inspired with Google's [Error Prone](https://github.com/google/error-prone).
- [Mapping Generator](https://github.com/cezarypiatek/MappingGenerator)  - 生成任意复杂对象-对象映射的代码修复. 它开箱即用地识别大量使用映射的场景. 设计时替代方案 [AutoMapper](https://automapper.org/).
- [Nullable.Extended](https://github.com/tom-englert/Nullable.Extended) - Roslyn 工具和分析器可改善使用可空引用类型进行编码时的体验.
- [Refactoring Essentials for Visual Studio](https://github.com/icsharpcode/RefactoringEssentials/) - Refactorings, analyzers and code fixes for C# and VB.NET.
- [Roslyn Clr Heap Allocation Analyzer](https://github.com/Microsoft/RoslynClrHeapAllocationAnalyzer) - C# heap allocation analyzer that can detect explicit and many implicit allocations like boxing, closures, implicit delegate creations, etc.
- [Roslynator](https://github.com/JosefPihrt/Roslynator) - Collection of 190+ analyzers and 190+ refactorings for C#. Covers coding style, code readability and simplification, removing redundancies, fixing compiler errors, and many more.
- [SonarC#](https://github.com/SonarSource/sonar-csharp) - Static code analyzer for C# language used as an extension for the SonarQube platform.
- [StyleCop Analyzers for the .NET Compiler Platform](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) - 将 StyleCop 规则移植到 Roslyn.
- [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics)  - 代码质量分析器的集合. 涵盖异步方法的用法、标志枚举、异常处理的最佳实践以及许多其他代码质量检查.

## Libraries and Frameworks for Testing Analyzers, Code Fixes, and Refactorings
用于测试分析器、代码修复和重构的很棒的库和框架.

- [Microsoft.CodeAnalysis.Testing](https://github.com/dotnet/roslyn-sdk/tree/master/src/Microsoft.CodeAnalysis.Testing)  - 用于使用 NUnit、xUnit 和 MSTest 框架测试分析器和代码修复的库. 一部分 [Roslyn SDK](https://github.com/dotnet/roslyn-sdk).
- [RoslynTestKit](https://github.com/cezarypiatek/RoslynTestKit)  - 用于为分析器、代码修复、重构和完成提供程序编写单元测试的轻量级框架. 它与单元测试框架无关.

## Source Generators
Awesome (but mostly experimental at the moment, because .NET 5.0 and C# 9.0 are still in preview) source generators and open source projects that internally use source generators.

- [DpDtInject](https://github.com/lsoft/DpdtInject)  - 将大量解析逻辑转移到编译阶段的依赖注入容器的概念验证. 提供额外的编译时安全性和快速的运行时解析.
- [Generator.Equals](https://github.com/diegofrata/Generator.Equals)  - 自动为类和记录实现相等性和散列. 支持不同的比较策略. 提供类似于基于 IL 编织的功能 [Equals.Fody](https://github.com/Fody/Equals).
- [JsonSrcGen](https://github.com/trampster/JsonSrcGen)  - 无反射 JSON 序列化器. 通过在编译时生成无反射序列化程序，允许极快的 JSON 处理.
- [Source Generator Playground](https://sourcegen.dev/)  - 可让您试验源代码生成器的在线应用程序. 非常适合学习和测试您的想法. 编写您自己的源代码生成器或从内置示例中学习并查看生成的输出.  
- [StrongInject](https://github.com/YairHalberstadt/stronginject)  - 编译时依赖注入容器. 编译时检查、无反射和无运行时代码生成，因此快速且 [app-trimming](https://devblogs.microsoft.com/dotnet/app-trimming-in-net-5/)-friendly. 
- [StructPacker](https://github.com/RudolfKurka/StructPacker) - Low-level, lightweight and performance-focused serializer for C# struct types. Auto-generates C# serialization code to achieve peak runtime performance and efficiency.
- [Svg to C# Source Generators](https://github.com/wieslawsoltes/SourceGenerators) - SVG to C# compiler. Compiles SVG drawing markup to C# using [SkiaSharp](https://github.com/mono/SkiaSharp) 作为渲染引擎.
- [WrapperValueObject](https://github.com/martinothamar/WrapperValueObject)  - 围绕类型创建样板免费包装器. 对创作特别有用 [strongly typed wrappers around primitive types](https://andrewlock.net/series/using-strongly-typed-entity-ids-to-avoid-primitive-obsession/).

## Blog Posts and Articles
很棒的博客文章和在线文章涵盖了各种主题，例如性能、Roslyn 历史、内部结构等.

- [How Microsoft rewrote its C# compiler in C# and made it open source](https://medium.com/microsoft-open-source-stories/how-microsoft-rewrote-its-c-compiler-in-c-and-made-it-open-source-4ebed5646f98) - Roslyn's journey, presented by Mads Torgersen, the lead designer of C#. Inspiring story on how Roslyn project started and why, and what it took to make it open source.
- [Inside the .NET Compiler Platform – Performance Considerations during Syntax Analysis (#SpeakRoslyn)](https://robinsedlaczek.com/2015/04/29/inside-the-net-compiler-platform-performance-considerations-during-syntax-analysis-speakroslyn/) - 深入了解 Roslyn 的性能，重点关注内存消耗.
- [Persistence, Facades and Roslyn's Red-Green Trees](https://blogs.msdn.microsoft.com/ericlippert/2012/06/08/persistence-facades-and-roslyns-red-green-trees/)  - 关于 Roslyn 团队如何使用廉价的父引用和许多其他好东西实现不可变、可重用的树的鼓舞人心的介绍. 引用：“但是在 Roslyn 团队中，我们经常做不可能的事情”:-)
- [ReSharper and Roslyn: Q&A](https://blog.jetbrains.com/dotnet/2014/04/10/resharper-and-roslyn-qa/)  - 很好地解释了为什么 ReSharper 不使用 Roslyn. 包括关于静态代码分析和 Roslyn 的一些限制的良好讨论.
- [Roslyn performance (Matt Gertz)](https://blogs.msdn.microsoft.com/csharpfaq/2014/01/15/roslyn-performance-matt-gertz/) - 深入了解 Roslyn 团队如何处理评估和实现绩效的主题.

## Talks
关于罗斯林的精彩公开演讲.

- [The Power of Roslyn](https://www.youtube.com/watch?v=nXljhGDokqA) - Kasey Uhlenhuth 在 NDC Oslo 2018 上的精彩演讲，涵盖了用于构建代码分析器和修复程序的 Roslyn 要素和 API 以及工具.

## Contribute

欢迎贡献 :-) 目标是建立一个由社区驱动的分类的很棒的 Roslyn 资源集合. 在贡献之前，请务必阅读 [contribution guidelines](https://github.com/ironcev/awesome-roslyn/blob/master/contributing.md).

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，Igor Rončević 已放弃对本作品的所有版权和相关或邻接权.
