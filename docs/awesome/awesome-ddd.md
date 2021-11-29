<div class="github-widget" data-repo="heynickc/awesome-ddd"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Domain-Driven Design [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 域驱动设计 (DDD)、命令查询责任分离 (CQRS)、事件溯源和事件风暴资源的精选列表.

**看看我 [blog](https://buildplease.com) and [weekly DDD newsletter](https://buildplease.com/pages/dddweekly/) 或者打个招呼 [Twitter](https://twitter.com/heynickc)!**

**[Domain-Driven Design (DDD)](https://en.m.wikipedia.org/wiki/Domain-driven_design) ** 是一种通过将实现连接到不断发展的模型来满足复杂需求的软件开发方法. 领域驱动设计的前提如下：

- 将项目的主要重点放在核心领域和领域逻辑上
- 基于领域模型的复杂设计
- 发起技术专家和领域专家之间的创造性合作，以迭代地改进解决特定领域问题的概念模型

这个词是由埃里克·埃文斯在他的同名书中创造的.

**[Command Query Responsibility Segregation (CQRS)](http://codebetter.com/gregyoung/2010/02/16/cqrs-task-based-uis-event-sourcing-agh/) ** 只是在以前只有一个对象的情况下创建了两个对象. 分离的发生基于方法是命令还是查询（Meyer 在命令和查询分离中使用的相同定义，命令是任何改变状态的方法，查询是任何返回值的方法）.

**[Event Sourcing](http://www.martinfowler.com/eaaDev/EventSourcing.html)** 事件溯源的基本思想是确保应用程序状态的每一次更改都在事件对象中捕获，并且这些事件对象本身按照它们应用的顺序存储，与应用程序状态本身具有相同的生命周期.

**[Event Storming](https://ziobrando.blogspot.com/2013/11/introducing-event-storming.html)** 是一种研讨会形式，用于快速探索复杂的业务领域.


- [Awesome Domain-Driven Design](https://github.com/heynickc/awesome-ddd/)

## Books

- [Applying Domain Driven Design with CQRS and Event Sourcing](https://buildplease.com/pages/now-what/) - 使用 EventStorming 和其他建模技术为虚构的业务领域构建基于 CQRS 和事件源的原型的演练.
- [CQRS](https://leanpub.com/cqrs)  - Mark Nijhof 的笔记，来自他从 Greg Young 那里学习 DDD 和 CQRS 的经验. 本书附带了一个广泛的示例项目.
- [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215)  - 创造术语领域驱动设计的规范书籍. 又称“蓝皮书”.
- [Domain-Driven Design Distilled](https://www.amazon.com/Domain-Driven-Design-Distilled-Vaughn-Vernon/dp/0134434420) - 阅读前非常好的入门书 [Implementing Domain-Driven Design](https://vaughnvernon.co/?page_id=168#iddd) 或者 [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215).
- [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - 用 PHP 编写的真实示例，展示了 DDD 架构风格、战术设计和限界上下文集成.
- [Domain-Driven Rails](https://blog.arkency.com/domain-driven-rails/) - 领域驱动的 Rails 描述了 11 种技术（从限界上下文到事件溯源），您可以在新旧 Rails 应用程序中单独或一起使用，以实现更好的架构.
- [Domain Modeling Made Functional](https://pragprog.com/book/swdddf/domain-modeling-made-functional) - Tackle Software Complexity with Domain-Driven Design and F#.
- [Domain Specific Languages](http://martinfowler.com/books/dsl.html) - 与 DDD 相关，描述了通用语言的重要性以及与领域专家的合作，以及许多技术细节.
- [Event Sourcing and CQRS with .NET Core and SQL Server](https://buildplease.com/products/fpc-v2/) - 在生产中使用 ASP.NET Core 和 SQL Server 将域驱动设计与事件源和 CQRS 结合使用的演练.
- [Hands-On Domain-Driven Design with .NET Core](https://www.amazon.com/Hands-Domain-Driven-Design-NET-dp-1788834097/dp/1788834097) - 通过 Alexey Zimarev 将 DDD 原则付诸实践，解决软件核心的复杂性.
- [Implementing Domain-Driven Design](https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)  - 也是一本规范的书，介绍了理解领域驱动设计的自上而下的方法. 又称“红皮书”.
- [Implementing DDD, CQRS and Event Sourcing](https://leanpub.com/implementing-ddd-cqrs-and-event-sourcing)  - 了解如何实施 DDD、CQRS 和事件溯源. 理解理论并使用 JavaScript 和 Node.js 将其付诸实践.
- [Introducing Event Storming: An act of Deliberate Collective Learning](https://leanpub.com/introducing_eventstorming) - 直接来自发明者的关于 EventStorming 的最深入的教程和解释.
- [Learning Domain-Driven Design: Aligning Software Architecture and Business Strategy](https://www.amazon.com/Learning-Domain-Driven-Design-Aligning-Architecture/dp/1098100131/) - 了解领域驱动设计的基本模式和实践，以及如何将它们应用到您的日常工作中，包括绿地和棕地项目.
- [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/) - 软件架构师对核心实践的总结，实用的应用.
- [Patterns, Principles, and Practices of Domain-Driven Design (1st Edition)](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709) - Methods for managing complex software construction following the practices, principles and patterns of Domain-Driven Design with code examples in C#.
- [Secure by Design](https://www.manning.com/books/secure-by-design?a_aid=danbjson&a_bid=0b3fac80) - 展示如何使用领域驱动设计来避免安全漏洞.
- [Specification by Example](https://www.manning.com/books/specification-by-example)  - 本书从全球领先团队的经验中提炼而成，这些经验是在短的迭代交付周期内指定、测试和交付软件的有效方法. 本书中的案例研究范围从小型网络初创公司到大型金融机构，在许多流程中工作，包括 XP、Scrum 和看板.
- [Versioning in an Event Sourced System](https://leanpub.com/esversioning)  - 您是否在版本控制事件源系统方面遇到问题？ 第一次进入一个新的事件源系统？ 本书是有关如何处理长时间版本控制的权威指南.
- [What is Domain-Driven Design?](https://learning.oreilly.com/library/view/what-is-domain-driven/9781492057802/) - 快速阅读，探索领域驱动设计的核心模式和原则，以及在棕地项目中应用 DDD 的策略.
- [Writing Great Specifications](https://www.manning.com/books/writing-great-specifications) - Writing Great Specifications is an example-rich tutorial that teaches you how to write good Gherkin specification documents that take advantage of Specification by Example's benefits.

## Free eBooks

- [The Anatomy of Domain-Driven Design - The Infographic](https://leanpub.com/theanatomyofdomain-drivendesign) - 关于领域驱动设计剖析的信息图.
- [Architecting Modern Web Applications with ASP.NET Core and Microsoft Azure](https://dotnet.microsoft.com/download/thank-you/aspnet-ebook) - 提供有关使用 DDD、ASP.NET Core 和 Azure 构建整体式 Web 应用程序的端到端指南. [eShopOnWeb sample](https://github.com/dotnet-architecture/eShopOnWeb)
- [Architecture Patterns with Python](https://www.cosmicpython.com/book/preface.html) - 一本关于管理复杂性的 Pythonic 应用程序架构模式的书.
- [CQRS Journey](https://msdn.microsoft.com/en-us/library/jj554200.aspx) - 探索 CQRS 和事件溯源.
- [Domain-Driven Design: The First 15 Years](https://dddeurope.com/15years)  - 为了庆祝周年纪念，我们邀请了软件设计界的杰出作者贡献新旧文章. 由 Martin Fowler、James Coplien、Rebecca Wirfs-Brock、Mel Conway 等人贡献.
- [DDD Reference](http://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) - DDD 模式和定义的总结.
- [Domain Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly) - 快速领域驱动设计是对 DDD 基础知识的简短、易读的总结和介绍.
- [Effective Aggregate Design](http://dddcommunity.org/library/vernon_2011/) - 在这个由三部分组成的系列中，Vaughn Vernon 探讨了一些常见的设计陷阱，讨论了各种聚合建模选择的优缺点，并提供了指导聚合建模的经验法则.
- [Getting Started with DDD when Surrounded by Legacy Systems](http://domainlanguage.com/wp-content/uploads/2016/04/GettingStartedWithDDDWhenSurroundedByLegacySystemsV1.pdf) - 描述了当您对遗留系统有很大承诺时开始使用 DDD 的三种策略.
- [Living Documentation by Design, with Domain-Driven Design](https://leanpub.com/livingdocumentation) - 了解动态文档如何在项目的各个方面为您提供帮助，从业务目标到业务领域知识、架构和设计、流程和部署，即使您讨厌编写文档.
- [.NET Microservices: Architecture for Containerized .NET Applications](https://dotnet.microsoft.com/download/thank-you/microservices-architecture-ebook) - 介绍开发基于微服务的应用程序并使用容器管理它们. [eShopOnContainers sample](https://github.com/dotnet-architecture/eShopOnContainers)
- [The Semantic JavaScript Backend for Event-Driven Development](https://docs.wolkenkit.io/1.1.0/downloads/brochure/) - 一本 68 页长的免费电子书，介绍什么是 DDD、CQRS 和事件溯源，以及它们如何相互配合.
- [DDD Magazine from Xebia #1](https://pages.xebia.com/domain-driven-design-magazine-xebia) - 这本杂志包含基于个人、业务和客户体验的富有远见和实用的见解，为您的 DDD 之旅提供支持
- [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/)  - Visual Collaboration Tools 是一本适合团队构建软件的书. 它描述了帮助我们完成日常工作的工具，并展示了来自不同从业者的现场故事.

## Training Courses

- [DDD Workshops across Europe and Online](https://training.dddeurope.com/) - 由 Eric Evans、Alberto Brandolini、Mathias Verraes、Rebecca Wirfs-Brock、Nick Tune 等举办的公开研讨会.
- [Domain Language eLearning](http://elearn.domainlanguage.com/) - 与 Eric Evans 一起使用我们的视频课程，Eric Evans 是领域驱动设计 (DDD) 原书的作者，自学技术来发展改进您的软件的实用模型——而不仅仅是您的文档.
- [Greg Young's CQRS Class](http://subscriptions.viddler.com/GregYoung/) - 这些视频包括 Greg Young 的 DDD、CQRS 和事件溯源课程的全部内容.
- [Distilling Domain-Driven Design](https://forcomprehension.com/) - Vaughn Vernon 的在线培训课程.
- [Advanced Distributed Systems Design](https://learn-particular.thinkific.com/courses/adsd-online)  - 来自 Udi Dahan 的在线培训课程. 可以找到Udi的现场训练时间表 [here](http://udidahan.com/training/).
- [Nomad PHP](https://nomadphp.com/product/introduction-event-sourcing-cqrs/) - 事件溯源和 CQRS 简介.
- [Event Sourcery](https://eventsourcery.com/) - DDD、CQRS 和事件溯源简介.
- [Mixter](https://github.com/DevLyon/mixter) - CQRS 和事件溯源 Koans.
- [Pluralsight](https://pluralsight.com)
	 - [Domain-Driven Design Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) - 通过客户交互演示和复杂的演示应用程序以及 Eric Evans 的建议，教授领域驱动设计 (DDD) 的基础知识.
	 - [Domain-Driven Design in Practice](https://www.pluralsight.com/courses/domain-driven-design-in-practice) - 在实践中应用领域驱动设计原则的描述性、深入的演练.
	 - [Modern Software Architecture: Domain Models, CQRS, and Event Sourcing](https://www.pluralsight.com/courses/modern-software-architecture-domain-models-cqrs-event-sourcing)  - 本课程涵盖有助于发现业务领域顶级架构的 DDD 分析模式. 架构师和开发人员将找到实现模式的详细信息，例如领域模型、CQRS 和事件溯源.
- [Rails + Domain Driven Design Workshop](https://blog.arkency.com/ddd-training/) - 为 Ruby/Rails 开发人员介绍 DDD、CQRS 和事件溯源的基础知识.
- [Reactive Architecture: Domain Driven Design](https://cognitiveclass.ai/courses/reactive-architecture-ddd/)  - 使用 DDD 将问题域分解为可管理的部分. 了解这些部分如何成为反应式微服务和反应式架构的基础. 免费、在线、自定进度. 完成后提供证书.
- [Reactive Architecture: CQRS and Event Sourcing](https://cognitiveclass.ai/courses/reactive-architecture-cqrs/)  - 本课程将讨论我们使用 CQRS/ES 的原因、它为我们提供的好处，以及我们使用 CQRS/ES 的成本. 我们将看到 CQRS/ES 如何影响我们应用程序的可扩展性、一致性和可用性.
- [DDD Workshop by Xebia](https://xebia.com/academy/en/search?query=Domain-driven%20design) - 从基础到专业级别的公共和内部领域驱动设计研讨会.

## Video Collections

- [DDD Europe](https://dddeurope.com/videos) - 在 DDD 欧洲提供的谈话录音.
- [SkillsCasts by SkillsMatter](https://skillsmatter.com/skillscasts) - 搜索 DDD 会返回 Greg Young、Alberto Brandolini 和 Dan North 等人的各种演讲.
- [Alberto Brandolini: Event Storming](https://www.youtube.com/watch?v=veTVAN0oEkQ&list=PLve553MhJLs4YkEnHmOjWJv0B-6WY0-JI) - 阿尔贝托·布兰多里尼 (Alberto Brandolini) 关于事件风暴的演讲的 YouTube 合集.
- [Greg Young](https://www.youtube.com/watch?v=JHGkaShoyNs&list=PL5XpN_ZVafKLePdxruDfdfi-IiZtXz-k9) - 由 Greg Young 提供的各种演讲的 YouTube 合集.
- [Explore DDD videos](https://www.youtube.com/channel/UCcpKGt6MVvz7dISXLlMGmag) - 在探索 DDD 会议上提供的谈话录音.
- [KanDDDinsky](https://www.youtube.com/channel/UCJCpnslPdb_Dl8DKokXC3HA) - 在 YouTube 上的 KanDDDinsky 演讲集.
- [Virtual Domain-driven design](https://www.youtube.com/channel/UCob_jOzzpxBp-di-x0vLlwA) - 来自 Virtual Domain 驱动设计的录制聚会会话的 YouTube 集合

## Community Resources

- [DDD/CQRS Google Group](https://groups.google.com/forum/?utm_source=digest&utm_medium=email#!forum/dddcqrs) - 一个活跃的邮件列表和一个很好的资源，可以提出问题并了解有关 DDD/CQRS 的细粒度细节.
- [Domain Driven Design Yahoo Group](https://groups.yahoo.com/neo/groups/domaindrivendesign/conversations/messages)  - 本组讨论设计软件的领域驱动风格，以及 Eric Evans 所著的《领域驱动设计：解决商业软件核心的复杂性》一书. 欢迎对本书内容提出问题和讨论，也欢迎分享应用 DDD 的经验，以及对该主题的一般讨论.
- [DDDinPHP Google Group](https://groups.google.com/forum/#!forum/dddinphp) - 在 PHP 上下文中讨论领域驱动设计、CQRS、事件溯源、模型风暴、六边形架构、分布式系统、反应式……的地方.
- [DDD in Ruby subreddit](https://www.reddit.com/r/ddd_ruby/) - 对领域驱动设计感兴趣的 Ruby 开发人员的子版块.
- [EventStormers Google+ Community](https://plus.google.com/u/0/communities/113258571348605620818) - 每个对 EventStorming 和相关主题感兴趣的人的公共讨论组.
- [DDD/CQRS/ES Slack](https://github.com/ddd-cqrs-es/slack-community)  - 对于那些想要讨论领域驱动设计、CQRS、事件溯源以及有时是随机事物的人来说，这是一个松散的团队. 主要渠道与语言和框架无关.
- [Domain StoryTelling Slack](https://domainstorytelling.slack.com)  - 关于 Domain StoryTelling 的松懈团队. 目前仅限邀请，但您可以询问 [@hofstef](https://twitter.com/hofstef) 为邀请. 主页位于 [domainstorytelling.org](http://domainstorytelling.org/).
- [Software Engineering Stack Exchange](http://softwareengineering.stackexchange.com/questions/tagged/domain-driven-design) - 标记为 * 领域驱动设计 * 的软件工程堆栈交换问题.
- [Code Review Stack Exchange](http://codereview.stackexchange.com/questions/tagged/ddd) - 代码审查堆栈交换问题标记为 *domain-driven-design*.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/domain-driven-design) - 堆栈溢出问题标记为*领域驱动设计*.
- [Advanced Topics in Event Sourcing / CQRS / DDD](https://github.com/sebastianharko/adv-es-cqrs-ddd) - 由@编译和维护的事件溯源/CQRS/DDD列表中的高级主题[sebastianharko](https://github.com/sebastianharko).
- [Quora](https://www.quora.com/topic/Domain-Driven-Design-DDD) - 问题标记为*领域驱动设计*.
- [wolkenkit Slack](http://slackin.wolkenkit.io/) - 一个关于 DDD、事件溯源、CQRS 和 wolkenkit 的 Slack 团队.
- [Awesome Event Storming](https://github.com/mariuszgil/awesome-eventstorming) - 仅关注事件风暴的精彩列表.
- [Virtual Domain-driven design community](https://virtualddd.com) - 包含小组讨论、在线协作和资源共享的在线聚会.
- [Domain-driven design heuristics](https://www.dddheuristics.com/) - 领域驱动设计启发式是一个社区驱动的站点，用于记录和讨论设计启发式.

## Blogs

- [Nick Chamberlain](https://buildplease.com) - 为 .NET 开发人员提供有用的开发和设计建议.
- [Ardalis.com](https://ardalis.com/blog)  - 史蒂夫史密斯.  Pluralsight 作者和作者 [DDD Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) 课程和微软 [eShopOnWeb sample app](https://github.com/dotnet-architecture/eShopOnWeb).
- [DDD Weekly](http://dddweekly.com) - 与 DDD/CQRS/ES 相关的每周策划链接.
- [Daniel Whittaker](http://danielwhittaker.me)  - 想了解 CQRS 和事件溯源？ 该博客包含分步文章，可为您提供一个良好的开端.
- [Cyrille Martraire](http://cyrille.martraire.com) - 沉浸在金融领域，同时仍然热爱编程，我自然是 Eric Evans 的领域驱动设计以及 TDD、BDD 和敏捷/XP 实践的忠实粉丝.
- [Jimmy Bogard](https://lostechies.com/jimmybogard/) - 我专注于 DDD、分布式系统和任何其他以首字母缩略词为中心的设计/架构/方法论.
- [CodeBetter](http://codebetter.com) - CodeBetter.Com 的存在是为了帮助在软件开发社区内培养对更好实践、卓越工具、经过验证的方法和技术的认识.
- [Greg Young](https://goodenoughsoftware.net/) - 足够好的软件定义为足够好.
- [InfoQ Blog](https://www.infoq.com/domaindrivendesign/) - InfoQ 上的领域驱动设计内容.
- [Dan North](https://dannorth.net/blog/)  - 行为驱动设计的发明者. 也有关于事件风暴的博客和讨论.
- [Mike Mogosanu](http://blog.sapiensworks.com)  - 可维护的代码是一个商业优势. 领域地图的创建者：领域建模工具 - 简单而强大的领域驱动设计.
- [Christian Posta](http://blog.christianposta.com) - Principal Middleware Architect @ Red Hat, open-source enthusiast, committer @ Apache, Cloud, Integration, Kubernetes, Docker, OpenShift, Fabric8.
- [Vladimir Khorikov](http://enterprisecraftsmanship.com)  - Pluralsight 作者. 关于软件开发原则和最佳实践的博客.
- [TechBeacon](http://techbeacon.com/) - TechBeacon 上的文章标记为*领域驱动设计*.
- [Derek Comartin](http://codeopinion.com) - 类别*领域驱动设计*下的文章.
- [Alberto Brandolini](https://ziobrando.blogspot.it)  - 事件风暴的发明者.  Alberto 断言问题无法以产生问题的相同心态来解决，他经常转换观点，假设架构师、导师、教练、经理或开发人员的观点.
- [Jérémie Chassaing](http://thinkbeforecoding.com/) - Various articles about DDD/CQRS.  Implemented Greg Young's SimpleCQRS sample in F#.
- [Vaughn Vernon](https://vaughnvernon.co) - Vaughn Vernon 了解软件开发的独特需求以及您在快节奏的行业中改进工艺时面临的挑战.
- [Vladik Khononov](http://vladikk.com/) - 各种与 DDD 相关的文章.
- [Eventsourcing Publications](https://blog.eventsourcing.com) - 实用的事件采购.
- [Jef Claes](http://www.jefclaes.be/) - 关于领域驱动设计的优秀文章和演讲.
- [Udi Dahan](http://udidahan.com/articles/) - 来自 NServiceBus 的创建者.
- [Chris Patterson](https://lostechies.com/chrispatterson/) - 来自 MassTransit 分布式应用程序框架的创建者.
- [Aaron Stannard](http://www.aaronstannard.com/) - 来自 Petabridge 的 CTO 和联合创始人，Akka.NET Actor Model 框架的开发人员.
- [Roger Johansson](https://rogeralsing.com/) - Mostly C#, DDD, and Akka.NET.
- [Konrad Garus](http://squirrel.pl/blog/)  - Java、Clojure 和 JavaScript 中的咆哮和编程. 标记在 *cqrs* 下的文章.
- [Oasis Digital](http://blog.oasisdigital.com/category/cqrs/) - Oasis Digital 的内容标记为 *cqrs*.
- [Adaptech](http://adaptechsolutions.net/blog/)  - Adaptech 解决方案博客. 我们的创始人 Adam Dymitruk 在 Greg 创造了 CQRS 一词之前，与 Greg Young 讨论了 CQRS 的优点.  Adam 和业务合作伙伴 Robert Reppel 是事件源微服务的领先实践者.
- [Lev Gorodinski](http://gorodinski.com/) - 2013 年的几篇关于 DDD 的文章，仍然具有相关性.
- [Dino Esposito](https://software2cents.wordpress.com/)  - 软件架构师、培训师、书籍作者. 作者 [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/).
- [Dan Bergh Johnsson "Dear Junior"](http://dearjunior.blogspot.se/search/label/domain%20driven%20design)  - 域驱动设计与安全性和敏捷性相结合. 写给年轻程序员的虚构信件.
- [the native web](https://www.thenativeweb.io/blog/2017-10-25-09-46-ddd-and-co-part-1-whats-wrong-with-crud/) - DDD &amp; Co. 系列
- [Arkency](https://blog.arkency.com/) - 来自 Ruby 专家的各种 DDD、CQRS、事件溯源相关文章.
- [Svaťa Šimara](http://svatasimara.cz/) - DDD 系列 - PHP 中的语言、领域、建模、基础设施、实现
- [Martin Havlišta](https://xhafan.com/blog/) - DDD, CQRS, TDD blog posts with code samples in C# .NET
- [Khalil Stemmler](https://khalilstemmler.com/articles/categories/domain-driven-design) - DDD系列介绍，谈谈如何用TypeScript实现DDD
- [Kenny Baas-Schwegler](https://baasie.com/) - DDD、BDD、社会技术、事件风暴和持续交付博客.
- [João Rosa](https://joaorosa.io)  - 关于领域驱动设计、视觉协作、领导力和组织设计的个人博客. 以及介于两者之间的其他事情. 策展人 [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/) 和主持人 [Software Crafts Podcast](https://www.softwarecraftspodcast.com/)

## Sample Projects

### GO
- [BDD in GO](https://github.com/JankariTech/bsDateServer)  - 演示使用 Cucumber + GO 进行 BDD 测试方法的示例应用程序. 可以找到博文 [here](https://dev.to/jankaritech/demonstrating-bdd-behavior-driven-development-in-go-1eci).
- [Citerus DDD Sample App GO Port](https://github.com/marcusolsson/goddd) - 这是尝试移植 [DDD Sample App](https://github.com/citerus/dddsample-core) 地道的 Go. 它可以在 dockerized 模式下运行以预览应用程序.
- [DDD by Refactoring](https://github.com/ThreeDotsLabs/wild-workouts-go-ddd-example)  - 完整的无服务器应用程序，展示如何通过 Go 项目的实际重构来应用 DDD、清洁架构和 CQRS. 可以在以下位置找到有关它的完整博客系列<https://threedots.tech/> .
- [DDD Food App](https://github.com/victorsteven/food-app-server)  - 实现 4 层（域、基础设施、应用程序和接口）并考虑两种域模式的示例 DDD 应用程序. 有一篇博客文章是为它写 [here](https://dev.to/stevensunflash/using-domain-driven-design-ddd-in-golang-3ee5).
- [DDD Sample in GO](https://github.com/takashabe/go-ddd-sample) - 只是另一个实现四层 DDD 的示例应用程序.
- [Evolutive CRUD API](https://github.com/friendsofgo/gopherapi)  - 使用 SOLID 六边形架构的完整 CRUD 的 API 实现. 有一系列为它写的博客文章在<https://blog.friendsofgo.tech/> .
- [Simple Hexagonal Architecture PoC API](https://github.com/tomiok/patients-API) - 使用六边形架构模式的患者 API 的 PoC.

### .NET (C#/F#)
- [Better code with DDD building blocks](https://github.com/asc-lab/better-code-with-ddd)  - 解决方案提出使用 DDD 战术模式来实现更好的代码可读性和表达性. 将 DDD 模式与无处不在的语言一起应用可以缩小专家所说的语言与团队和代码中使用的语言之间的差距.
- [CQRS-DDD Example](https://github.com/dcomartin/DDD-CQRS-ES-Example) - 使用 GetEventStore、CommonDomain、NServiceBus、实体框架、SQL Server、SignalR 的域驱动设计、CQRS 和事件源示例.
- [Companion Code for Microsoft .NET Architecting Applications for the Enterprise](https://github.com/mastreeno/Merp) - An event based Micro ERP.
- [ContosoUniversityCore](https://github.com/jbogard/ContosoUniversityCore) - ContosoUniversity on ASP.NET Core 和完整的 .NET Framework.
- [DDD-starter-dotnet](https://github.com/itlibrium/DDD-starter-dotnet)  - 构建 DDD 应用程序的各种方法的示例实现和比较. 可用作快速启动 DDD .net 项目的基线.
- [DDDInventoryItemFSharp](https://github.com/eulerfx/DDDInventoryItemFSharp) - An idiomatic F# implementation of Domain-Driven Design
- [DDDSkeletonNet](https://github.com/andras-nemes/DDDSkeletonNet) (C#) - a .NET skeleton project to introduce the concepts of Domain Driven Design and loosely coupled layers.
- [DotNet CQRS Intro](https://github.com/asc-lab/dotnet-cqrs-intro) - 使用事件溯源实现 CQRS 的示例 - 进化方法（无 CQRS，具有相同模型的单独模型和命令，具有单独模型的单独模型和命令，单独的存储引擎，事件溯源）.
- [EISK](https://github.com/eisk) - .NET CLI 和 VS 模板具有简单的用例，可在具有架构最佳实践（DDD、洋葱架构等）的 .net 核心之上构建可扩展的应用程序.
- [EmailMaker](https://github.com/xhafan/emailmaker) - 电子邮件营销 ASP.NET Core MVC 和 ASP.NET MVC 演示应用程序演示 [CoreDdd](https://github.com/xhafan/coreddd) 用法
- [Equinox Project](https://github.com/EduardoPires/EquinoxProject) - 完整的 ASP.NET Core 3.1 应用程序，具有 Clean Architecture、DDD、CQRS 和 Event Sourcing 概念
- [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) - 来自 Microsoft 的完整 ASP.NET Core 3.1 参考应用程序，展示了整体部署架构
- [eShopOnContainersDDD](https://github.com/volak/eShopOnContainersDDD) - eShop 全栈示例，包含目录、购物篮、结账和订单有界上下文
- [Example of Domain-Driven Design in F#](https://gist.github.com/swlaschin/2ad8627d0400b2ab70e9f3da08902c9d)  - 跳棋游戏的领域驱动设计示例. 有两个文件：带有一系列设计的临时文件和最终版本.
- [Event Sourcing .NET](https://github.com/oskardudycz/EventSourcing.NetCore)  - 有关 .NET 中的事件溯源和 CQRS 的示例和资源. 还包含一个关于如何构建自己的 Event Store 的自定进度套件
- [EventFlow.Example](https://github.com/OKTAYKIR/EventFlow.Example) - DDD、CQRS 和 Event-Sourcing 示例并包含以下技术堆栈： [EventFlow](https://github.com/eventflow/EventFlow), [EventStore](https://eventstore.com), [RabbitMQ](https://www.rabbitmq.com), [MongoDB](https://www.mongodb.com), [PostgreSQL](https://www.postgresql.org), [Docker](https://www.docker.com)
- [Fohjin](https://github.com/MarkNijhof/Fohjin) - 伴随 Mark Nijhof 的示例项目 [CQRS](https://leanpub.com/cqrs) 书.
- [FsUno](https://github.com/thinkbeforecoding/FsUno) - Event sourcing implementation sample in F#.
- [IDDD Samples in .NET](https://github.com/VaughnVernon/IDDD_Samples_NET) - These are the sample Bounded Contexts for C#.NET from the book "Implementing Domain-Driven Design" by Vaughn Vernon.
- [Microsoft Patterns and Practices: CQRS Journey Sample Code](https://github.com/mspnp/cqrs-journey) - 来自 CQRS Journey 的示例代码.
- [Modular Monolith](https://github.com/kgrzybek/modular-monolith-with-ddd) - 采用领域驱动设计方法的全模块化单体 .NET 应用程序.
- [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) (.Net Core Preview 2) - N 层架构示例项目.
- [Photostock CQRS-DDD Example](https://github.com/mr0zek/Photostock)
- [Reactive Trader Cloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Adaptive Consulting 的 Reactive Trader Cloud.
- [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) - .NET Core REST API CQRS 实现，带有原始 SQL 和 DDD，使用 Clean Architecture.
- [Scritchy](https://github.com/ToJans/Scritchy) - 没有管道的 CQRS， [video](http://www.youtube.com/watch?v=5DKTFZD3hu8).
- [Simple CQRS in F#](https://github.com/thinkbeforecoding/m-r) - Greg Young's SimpleCQRS in F#.
- [SimpleCQRS](https://github.com/gregoryyoung/m-r) - Greg Young 的“最简单的事情”CQRS 与事件采购项目.
- [TaskoMask](https://github.com/hamed-shirbandi/TaskoMask) - 基于 .NET Core 的任务管理系统，具有 DDD、CQRS 和事件溯源概念.
- [TodoMVC-DDD-CQRS-EventSourcing](https://github.com/volak/TodoMVC-DDD-CQRS-EventSourcing) - Implementation of basic Todo app via tastejs/todomvc in C#/Typescript with eventsourcing, cqrs, and domain driven design

### Haskell
- [Eventuria gsd](https://github.com/Eventuria/gsd) - Haskell todo list reactive application with DDD, CQRS and Event Sourcing, FRP.

### Idris
- [OrderTaking](http://github.com/andorp/order-taking)  - Domain Modeling Made Functional book 的依赖类型实现. 一个如何用依赖类型形式化有界上下文和工作流图的示例项目.  NodeJS 可部署演示.

### JavaScript
- [wolkenkit Sample Applications](https://docs.wolkenkit.io/latest/media/sample-applications/wolkenkit-boards/) - DDD 示例应用程序的集合，例如 TodoMVC、寻宝应用程序、协作板等.

### JVM languages
- [Akka CQRS ES Demo](https://github.com/mdonkers/akka-cqrs-es-demo) - 在 Scala-Akka 中实现 CQRS 和事件溯源模式的演示项目.
- [DDD By Examples - Library](https://github.com/ddd-by-examples/library)  - 由真实业务需求驱动的库示例项目. 在 DDD、BDD、EventStorming、示例映射、CQRS 等的帮助下实现的模块化单体.
- [DDD Leaven](https://github.com/BottegaIT/ddd-leaven-v2) - DDD-CQRS 示例 v2.0 项目，可帮助您使用 Spring、JPA 和测试开始高级域建模.
- [DDD Workshop - Project Manager](https://github.com/mkopylec/project-manager)  - “自己动手”DDD 研讨会和 DDD 应用程序示例. 基于项目管理域.
- [Event Sourcing Example](https://github.com/Pragmatists/eventsourcing-java-example) - Java 代码的事件溯源和 CQRS 实现的简化（内存中）示例（针对银行域用例建模）.
- [Event Sourcing and CQRS Examples](https://github.com/andreschaffer/event-sourcing-cqrs-examples) - 事件溯源和 CQRS 在 Java 中的实用应用，为常见的相关问题提供了很好的参考，例如事件排序和幂等性.
- [Event Sourcing and CQRS Sample](https://github.com/pilloPl/event-source-cqrs-sample) - 带有命令查询职责分离的示例事件源应用程序
- [IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) - 这些是 Vaughn Vernon 所著的“实施领域驱动设计”一书中的限界上下文示例.
- [Java CQRS Intro](https://github.com/asc-lab/java-cqrs-intro) - 使用事件溯源实现 CQRS 的示例 - 进化方法（无 CQRS，具有相同模型的单独模型和命令，具有单独模型的单独模型和命令，单独的存储引擎，事件溯源）.
- [Kotlin DDD Sample](https://github.com/fabriciorissetto/kotlin-ddd-sample) - 用 Kotlin 编写的示例 DDD/CQRS 项目.
- [EventStormingWorkshop - Designing Cloud Native Microservices On AWS](https://github.com/humank/EventStormingWorkShop/) - 通过 EventStorming 研讨会并在 Java 中实现 DDD 战术设计模式的具体示例，应用 AWS 云原生服务来构建基于业务事件的 Coffeeshop 场景.
- [DDDSample](https://github.com/citerus/dddsample-core) - 使用 Spring Boot 的示例 DDD 项目（最初托管在 http://dddsample.sourceforge.net/）
- [Eclipse CargoTracker](https://eclipse-ee4j.github.io/cargotracker/) - 该项目展示了如何使用领域驱动设计 (DDD) 等广泛采用的架构最佳实践，通过 Jakarta EE 平台开发应用程序. [The code](https://github.com/eclipse-ee4j/cargotracker/) 旨在反映开发人员在实际工作中会使用的非平凡应用程序. 它试图直接展示如何使用 Jakarta EE 有效地满足实际的企业问题，例如生产力、敏捷性、可测试性、灵活性、可维护性、可扩展性和安全性. 该项目直接基于众所周知的原创 [Java DDD sample application](https://github.com/citerus/dddsample-core) 由 DDD 先驱 Eric Evans 的 Domain Language 公司和瑞典软件咨询公司 Citerus 开发. 
- [https://github.com/felipexw/clean-arch-ddd-intro](https://github.com/felipexw/clean-arch-ddd-intro) - 使用 Micronaut 的简单 DDD + 清洁架构.

### PHP
- [DDD CQRS Todo Sample](https://github.com/ferrius/ddd-cqrs-example) - 使用 PHP 7 和 Symfony 5 构建的 DDD CQRS ADR 六边形架构实现.
- [DDD Wish List](https://github.com/franzose/symfony-ddd-wishlist) - 使用 Symfony 3 和 Vue.js 构建的 PHP 示例应用程序.
- [DDD Playground](https://github.com/jorge07/ddd-playground/) - PHP 中的示例实现.
- [Eric Evans DDD Cargo Sample](https://github.com/codeliner/php-ddd-cargo-sample) - Eric Evans DDD 书中使用的货物示例的 PHP 7 版本
- [Shop Cart in PHP](https://github.com/simara-svatopluk/cart)  - 演示购物车的简单示例项目. 领域对象，Doctrine 集成.，TDD，层，单元测试
- [Symfony 5 DDD ES CQRS backend](https://github.com/jorge07/symfony-5-es-cqrs-boilerplate) - 使用 Symfony 和 PHP 8 的 DDD、CQRS 和事件溯源应用程序.

## Libraries and Frameworks

### GO
- [Ginkgo](https://github.com/onsi/ginkgo) - Ginkgo 建立在 Go 的测试包之上，允许进行富有表现力的行为驱动开发（“BDD”）风格的测试.
- [GOBDD](https://github.com/go-bdd/gobdd) - 用于 GO 的小型 BDD 框架.
- [GoConvey](https://github.com/smartystreets/goconvey)  - 在浏览器中进行测试. 与`go test`集成. 用 Go 编写行为测试.
- [Godog](https://github.com/cucumber/godog) - godog 包是 Golang 官方的 Cucumber BDD 框架，它将规范和测试文档合二为一，使用 Gherkin 格式的场景，格式为 Given, When, Then.

### .NET
- [Aggregates.NET](https://github.com/volak/Aggregates.NET) - 通过 NServicebus 和 GetEventStore 的 .NET 事件源域驱动设计模型.
- [AggregateSource](https://github.com/yreynhout/aggregateSource) - 使用聚合进行事件采购的轻量级基础设施.
- [Akka.NET](http://getakka.net/) - Akka.NET 是一个工具包和运行时，用于在 .NET 和 Mono 上构建高度并发、分布式和容错的事件驱动应用程序.
- [ABP](https://abp.io) - ASP.NET Boilerplate 的继任者 - 基于 ASP.NET Core 的应用程序框架，用于创建 NLayered、域驱动设计的 Web 应用程序，具有以微服务为中心的模块化架构
- [ASP.NET Boilerplate](http://aspnetboilerplate.com/) - 基于 ASP.NET MVC、Web API 和 ASP.NET Core 的应用程序框架，用于创建 NLayered、域驱动设计的 Web 应用程序，实现最佳实践.
- [ByValue](https://github.com/sm-g/ByValue) - 该库有助于创建具有正确实现的相等行为的 ValueObjects（即使具有集合属性）.
- [Cedar.CommandHandling](https://github.com/damianh/Cedar.CommandHandling)  - 通过 HTTP 处理命令的中间件； 通常用于 CQRS 应用程序.
- [Cirqus](https://github.com/d60/Cirqus) - d60 事件溯源 + CQRS 框架.
- [CommandQuery](https://github.com/hlaueriksson/CommandQuery) - ASP.NET Core 的命令查询分离 ⚡AWS Lambda ⚡Azure 函数 ⚡Google Cloud Functions ASP.NET Web API 2
- [CoreDdd](https://github.com/xhafan/coreddd) - 一组有助于 DDD 和 CQRS 的开源 .NET 库，具有 NHibernate 持久性
- [CQRS on Azure](https://github.com/MerrionComputing/CQRSAzure) Windows Azure 上的 CQRS.
- [Dolittle](https://dolittle.com)  - 使用 Dolittle 构建更好的应用程序. 一个面向 DDD 的事件源微服务平台，以开发人员的生产力和简单性为中心.
- [Edument CQRS and Intentful BDD Testing Starter Kit](https://www.cqrs.nu/) - 关于如何构建 CQRS/ES 应用程序的库和教程，包括 BDD 风格的测试框架.
- [EventFlow](https://github.com/eventflow/EventFlow) - 用于 .NET http://geteventflow.net/ 的 Async/await 第一个 CQRS+ES 和 DDD 框架.
- [Core.EventStore](https://github.com/younos1986/Core.EventStore)  - 用于促进 CommandService 和 QueryService 之间通信的库. 想法是当commandService中发生任何事件时，它应该持久化在MongoDb中的QueryService中.
- [Its.Cqrs](https://github.com/jonsequitur/Its.Cqrs) - 一组用于 CQRS 和事件溯源的库，具有领域驱动设计风格.
- [Marten](https://github.com/JasperFx/marten) - Postgresql 作为 .Net 应用程序的文档数据库和事件存储.
- [MassTransit](https://github.com/MassTransit/MassTransit) - .NET 的分布式应用程序框架.
- [MediatR](https://github.com/jbogard/MediatR) - Supports request/response, commands, queries, notifications and events, synchronous and async with intelligent dispatching via C# generic variance.
- [MessageRouter](https://github.com/QuickenLoans/MessageRouter) - 在此视频中描述： [The Beating Heart of CQRS, or Actor-Based Message Routing on the CLR](https://vimeo.com/171178586) by Paulmichael Blasucci at the New York F# .NET User Group.
- [NetDevPack](https://github.com/netdevpack) - 一组智能的通用类和实现，可使用 .NET（DDD、CQRS、规范模式、MediatR、验证、通知）提高您的开发效率.
- [NEventStore](https://github.com/NEventStore/NEventStore) - 一个持久化库，用于在使用事件溯源作为存储机制时抽象不同的存储实现.
- [NServiceBus](https://github.com/Particular/NServiceBus) - .NET 的服务总线.
- [Projac](https://github.com/yreynhout/Projac) - Projac 是一组投影库，允许您编写针对各种后备存储的投影.
- [shriek-fx](https://github.com/ElderJames/shriek-fx) - 使用 .NET Core 2.0 开发的简单、优雅且有用的领域驱动设计和 CQRS 框架.
- [SqlStreamStore](https://github.com/damianh/SqlStreamStore) - .NET Stream Store 库针对基于 SQL 的实现.
- [Streamstone](https://github.com/yevhen/Streamstone) - Azure 表存储的事件存储.
- [Stringly.Typed](https://github.com/mission202/Stringly.Typed) - 更轻松地将字符串转换为 .NET 类型/从 .NET 类型转换.
- [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0.

### Databases
- [Event Store](https://geteventstore.com) - 在 JavaScript 中具有复杂事件处理功能的开源函数式数据库.
- [Eventsourcing](https://eventsourcing.com) - 业务事件捕获和查询框架.
- [Message DB](https://github.com/message-db/message-db)  - 用于 Postgres 的微服务本机事件存储和消息存储. 在 PostgreSQL 中为发布/订阅、事件溯源、消息传递和事件化微服务应用程序实现的全功能事件存储和消息存储.
- [Serialized](https://serialized.io) - 事件溯源和 CQRS 的完整平台.

### Elixir
- [Commanded](https://github.com/slashdotdash/commanded) - 用于 CQRS/ES 应用程序的命令处理中间件、用于聚合和进程管理器的纯功能数据结构、点对点消息路由以及 Elixir (Erlang VM) 中的更多内容 - 全部在 Actor 并发模型中.
- [Event Bus](https://github.com/otobus/event_bus) - 基于 ETS 的内置事件存储和事件观察器的 Elixir 可追踪、可扩展和极简事件总线实现.
- [eventstore](https://github.com/slashdotdash/eventstore) - 使用 PostgreSQL 进行持久化的 CQRS 事件存储.

### JavaScript
- [cqrs.js](http://cqrs.js.org)  - node.js 中的 CQRS 实现. 包括 [node-eventstore](https://github.com/adrai/node-eventstore), [node-cqrs-domain](https://github.com/adrai/node-cqrs-domain), [node-eventdenormalizer](https://github.com/adrai/node-cqrs-eventdenormalizer), [node-cqrs-saga](https://github.com/adrai/node-cqrs-saga).
- [Node API Boilerplate](https://github.com/talyssonoc/node-api-boilerplate) - 用于 DDD 和清洁架构应用程序的 NodeJS Web API 样板.
- [wolkenkit](https://www.wolkenkit.io/) - 适用于 JavaScript 和 Node.js 的 CQRS、DDD 和事件源框架.

### JVM
- [akka-ddd](https://github.com/pawelkaczor/akka-ddd) - 可重用工件，用于遵循基于 CQRS/DDDD 的方法在 Akka 平台之上构建应用程序.
- [Apache Isis](https://isis.apache.org/index.html) - Apache Isis 是一个用 Java 快速开发域驱动应用程序的框架.
- [Axon Framework](http://www.axonframework.org/) - axon 框架专注于让想要基于 CQRS 原则创建 Java 应用程序的开发人员更轻松.
- [DDDplus framework](https://github.com/funkygao/cp-ddd-framework) - 基于DDD的复杂业务架构的轻量级灵活开发框架.
- [JESA](https://github.com/yreynhout/JESA) - Java 的事件源聚合.
- [Lagom](https://www.lagomframework.com)  - Lagom 框架是用于 Java 虚拟机的微服务框架，具有用于 Java 和 Scala 语言的 API. 它包括一个基于事件源/CQRS 的持久性模块.
- [SeedStack's Business Framework](http://seedstack.org/docs/business/) - 一组构建块，使您能够根据领域驱动设计 (DDD) 方法对业务逻辑进行编码.
- [Spine Event Engine](https://spine.io/)  - 用于构建云应用程序的 CQRS/ES 框架. 在 Protobuf 中定义有界上下文及其命令、事件和实体状态. 后端逻辑是用 Java 编写的，位于 Proto 生成的代码之上.  Java、JS 或 Dart 中的客户端代码通过 gRPC 与后端通信.

### PHP
- [Broadway](https://github.com/broadway/broadway) - Broadway 是一个 (PHP) 项目，为创建 CQRS 和事件源应用程序提供基础设施和测试助手.
- [Ecotone](http://ecotone.tech) - 在 PHP 中启用消息驱动架构并提供构建块以遵循 DDD 和 CQRS 原则.

### Python
- [Eventsoucing in Python](https://github.com/johnbywater/eventsourcing)  - 用于事件源和 DDD 的成熟、稳定的 Python 库. 支持多种数据库、不同类型的域事件排序、应用程序级加密、快照、乐观并发控制和处理事件. 应用程序和整个应用程序系统可以独立于基础设施进行定义，并以不同的方式（单线程、多线程、时钟、步进、多进程、参与者模型）和不同的基础设施运行.
- [dry-python](https://github.com/dry-python) - 一组用于可插拔业务逻辑组件的库.

### Ruby
- [Eventide](https://eventide-project.org)  - Ruby 的事件溯源和微服务堆栈. 一组用于编写事件驱动的自治服务的库.
- [Rails Event Store](https://railseventstore.org)  - Rails Event Store (RES) 是一个用于发布、使用、存储和检索事件的库. 它是为 Rails 应用程序使用事件驱动架构的最佳伴侣.

## Podcasts and Interviews

- [Deeper into DDD on DotNetRocks with David Real](http://dotnetrocks.com/?show=1151) - 2015 年 6 月 11 日.
- [Thinking in DDD on DotNetRocks with Julie Lerman and Steve Smith](http://dotnetrocks.com/?show=1023) - 2014 年 8 月 19 日.
- [Eric Evans on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=236) - 2007 年 5 月 10 日.
- [Jimmy Nilsson on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=191) - 2006 年 8 月 29 日.
- [Being the Worst](http://www.beingtheworst.com) - 2012 年至 2016 年.
- [Software Engineering Radio Episode 225: Eric Evans on Domain-Driven Design at 10 Years](http://www.se-radio.net/2015/05/se-radio-episode-226-eric-evans-on-domain-driven-design-at-10-years/) - 2015 年 5 月 13 日.
- [Software Engineering Radio Episode 218: Udi Dahan on CQRS (Command Query Responsibility Segregation)](http://www.se-radio.net/2015/01/episode-218-udi-dahan-on-cqrs-command-query-responsibility-segregation/) - 2015 年 1 月 30 日.

## Conferences

- [Domain-Driven Design Europe](https://dddeurope.com) - 领先的 DDD 会议（在 COVID19 期间在线）
- [EventSourcing](https://dddeurope.com/2020/#eventsourcing) - CQRS/EventSourcing 社区的新活动
- [DDD Foundations](https://dddeurope.com/2020/#foundations) - 为 DDD 新人策划的会议
- [Explore DDD - USA](http://exploreddd.com/)
- [Kandddinsky - Germany](http://kandddinsky.com/)

## User Groups

- [Collective CFP](https://sessionize.com/ddd-meetups) - 一次将您的演讲提交给所有 DDD 用户组.
- [Map of user groups in Europe](https://datawrapper.dwcdn.net/9FNZI/)
- [Map of user groups in North America](https://datawrapper.dwcdn.net/nbZkd/)
- [Map of user groups in Asia](https://datawrapper.dwcdn.net/oin66/)
- [Map of user groups in Africa](https://datawrapper.dwcdn.net/yaEOa/)
- [Virtual](https://virtualddd.com/)
- [Worldwide](https://www.meetup.com/worldwide-eventstorming-meetup/) - 具体关于 EventStorming
- [Austria](https://www.meetup.com/ddd-vienna/)
- [Barcelona](https://www.meetup.com/dddbcn/)
- [Belfast](https://dddbelfast.com/)
- [Belgium](http://www.meetup.com/dddbelgium/)
- [Berlin](http://www.meetup.com/Domain-Driven-Design-Berlin/)
- [Cologne/Bonn](https://www.meetup.com/Domain-Driven-Design-Koln-Bonn/)
- [Cracow](http://www.meetup.com/ddd-krk/)
- [DDD Taiwan Community](https://www.facebook.com/groups/dddtaiwan/)
- [Denver](https://www.meetup.com/ddd-denver/)
- [Iran](https://t.me/ddd_iran/)
- [Greece](https://www.meetup.com/dddgreece/)
- [Hamburg](https://www.meetup.com/DDD-HH-Domain-driven-Design-Hamburg/)
- [London](http://www.meetup.com/dddlondon/)
- [Munich](https://www.meetup.com/Microservices-Meetup-Munich/)
- [Nederland](http://www.meetup.com/Domain-Driven-Design-Nederland/)
- [Norway](https://www.meetup.com/dddnorway/)
- [Phoenix](https://www.meetup.com/DDD-Phoenix)
- [Warsaw](https://www.meetup.com/DDD-WAW)
- [Wroclaw](http://www.meetup.com/DDD-WRO)
- [Russia](https://t.me/dddevotion)

## Tools

- [Domain Storytelling](http://www.domainstorytelling.org/)  - 一种知识处理技术，可帮助相关人员熟悉该领域并制定表达他们共同理解的模型. 可作为 [print-out template](http://www.domainstorytelling.org/images/DST_Whiteboard-Kit.pdf)，以及开源在线工具， [WPS Modeler](https://www.wps.de/modeler) ([source](https://github.com/wps/domain-story-modeler)).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Nick Chamberlain](https://buildplease.com) 已放弃本作品的所有版权和相关或邻接权.
