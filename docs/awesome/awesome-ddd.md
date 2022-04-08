<div class="github-widget" data-repo="heynickc/awesome-ddd"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Domain-Driven Design [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 领域驱动设计 (DDD)、命令查询职责分离 (CQRS)、事件溯源和事件风暴资源的精选列表.

**查看我 [blog](https://buildplease.com) 和 [weekly DDD newsletter](https://buildplease.com/pages/dddweekly/) 或者打个招呼 [Twitter](https://twitter.com/heynickc)!**

**[Domain-Driven Design (DDD)](https://en.m.wikipedia.org/wiki/Domain-driven_design) ** 是一种通过将实现连接到不断发展的模型来满足复杂需求的软件开发方法. 领域驱动设计的前提如下：

- 将项目的主要重点放在核心领域和领域逻辑上
- 基于领域模型的复杂设计
- 发起技术专家和领域专家之间的创造性合作，以迭代改进解决特定领域问题的概念模型

这个词是由埃里克埃文斯在他的同名书中创造的.

**[Command Query Responsibility Segregation (CQRS)](http://codebetter.com/gregyoung/2010/02/16/cqrs-task-based-uis-event-sourcing-agh/) ** 只是在以前只有一个的情况下创建两个对象. 分离基于方法是命令还是查询（Meyer 在命令和查询分离中使用的定义相同，命令是改变状态的任何方法，查询是返回值的任何方法）.

**[Event Sourcing](http://www.martinfowler.com/eaaDev/EventSourcing.html)** 事件溯源的基本思想是确保应用程序状态的每一次更改都被捕获到一个事件对象中，并且这些事件对象本身按照它们被应用的顺序存储，其生命周期与应用程序状态本身相同.

**[Event Storming](https://ziobrando.blogspot.com/2013/11/introducing-event-storming.html)** 是一种用于快速探索复杂业务领域的研讨会形式.


- [Awesome Domain-Driven Design](https://github.com/heynickc/awesome-ddd/)

## Books

- [Applying Domain Driven Design with CQRS and Event Sourcing](https://buildplease.com/pages/now-what/) - 使用 EventStorming 和其他建模技术为虚构的业务领域构建基于 CQRS 和事件溯源的原型的演练.
- [CQRS](https://leanpub.com/cqrs)  - Mark Nijhof 的笔记来自他从 Greg Young 那里学习 DDD 和 CQRS 的经验. 本书附带了一个广泛的示例项目.
- [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215) - The canonical book that coined the term Domain-Driven Design.  Also known as the "Blue Book."
- [Domain-Driven Design Distilled](https://www.amazon.com/Domain-Driven-Design-Distilled-Vaughn-Vernon/dp/0134434420) - 阅读前非常好的入门书 [Implementing Domain-Driven Design](https://vaughnvernon.co/?page_id=168#iddd) 或者 [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215).
- [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - 用 PHP 编写的真实示例，展示 DDD 架构风格、战术设计和限界上下文集成.
- [Domain-Driven Rails](https://blog.arkency.com/domain-driven-rails/) - Domain-Driven Rails 描述了 11 种技术（从限界上下文到事件溯源），您可以在新旧 Rails 应用程序中单独或一起使用这些技术，以实现更好的架构.
- [Domain Modeling Made Functional](https://pragprog.com/book/swdddf/domain-modeling-made-functional) - Tackle Software Complexity with Domain-Driven Design and F#.
- [Domain Specific Languages](http://martinfowler.com/books/dsl.html) - 与 DDD 切线相关，描述了通用语言的重要性，并与领域专家一起工作，以及许多技术细节.
- [Event Sourcing and CQRS with .NET Core and SQL Server](https://buildplease.com/products/fpc-v2/) - 在生产中使用 ASP.NET Core 和 SQL Server 将领域驱动设计与事件溯源和 CQRS 结合使用的演练.
- [Hands-On Domain-Driven Design with .NET Core](https://www.amazon.com/Hands-Domain-Driven-Design-NET-dp-1788834097/dp/1788834097) - Alexey Zimarev 通过将 DDD 原则付诸实践来解决软件核心的复杂性问题.
- [Implementing Domain-Driven Design](https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)  - 也是一本规范的书，介绍了一种自上而下的方法来理解领域驱动设计. 又称“红皮书”.
- [Implementing DDD, CQRS and Event Sourcing](https://leanpub.com/implementing-ddd-cqrs-and-event-sourcing)  - 了解如何实施 DDD、CQRS 和事件溯源. 理解理论并使用 JavaScript 和 Node.js 将其付诸实践.
- [Introducing Event Storming: An act of Deliberate Collective Learning](https://leanpub.com/introducing_eventstorming) - 直接来自发明者的关于 EventStorming 的最深入的教程和解释.
- [Learning Domain-Driven Design: Aligning Software Architecture and Business Strategy](https://www.amazon.com/Learning-Domain-Driven-Design-Aligning-Architecture/dp/1098100131/) - 了解领域驱动设计的基本模式和实践，以及如何将它们应用到您的日常工作中，包括新建项目和新建项目.
- [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/) - 软件架构师对核心实践的摘要，实际应用.
- [Patterns, Principles, and Practices of Domain-Driven Design (1st Edition)](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709) - Methods for managing complex software construction following the practices, principles and patterns of Domain-Driven Design with code examples in C#.
- [Secure by Design](https://www.manning.com/books/secure-by-design?a_aid=danbjson&a_bid=0b3fac80) - 展示如何使用领域驱动设计来避免安全漏洞.
- [Specification by Example](https://www.manning.com/books/specification-by-example)  - 本书从全球领先团队的经验中提炼出在短的迭代交付周期内指定、测试和交付软件的有效方法. 本书中的案例研究范围从小型网络初创公司到大型金融机构，涉及许多流程，包括 XP、Scrum 和看板.
- [Versioning in an Event Sourced System](https://leanpub.com/esversioning)  - 您在对事件源系统进行版本控制时遇到过问题吗？ 第一次进入新的事件源系统？ 这本书是关于如何长时间处理版本控制的权威指南.
- [What is Domain-Driven Design?](https://learning.oreilly.com/library/view/what-is-domain-driven/9781492057802/) - 快速阅读，探索领域驱动设计的核心模式和原则，以及在棕地项目中应用 DDD 的策略.
- [Writing Great Specifications](https://www.manning.com/books/writing-great-specifications) - 编写出色的规范是一个示例丰富的教程，它教您如何编写良好的 Gherkin 规范文档，以利用通过示例进行规范的好处.

## Free eBooks

- [The Anatomy of Domain-Driven Design - The Infographic](https://leanpub.com/theanatomyofdomain-drivendesign) - 领域驱动设计剖析的信息图.
- [Architecting Modern Web Applications with ASP.NET Core and Microsoft Azure](https://dotnet.microsoft.com/download/thank-you/aspnet-ebook) - 提供有关使用 DDD、ASP.NET Core 和 Azure 构建单体 Web 应用程序的端到端指导. [eShopOnWeb sample](https://github.com/dotnet-architecture/eShopOnWeb)
- [Architecture Patterns with Python](https://www.cosmicpython.com/book/preface.html) - 一本关于管理复杂性的 Pythonic 应用程序架构模式的书.
- [CQRS Journey](https://msdn.microsoft.com/en-us/library/jj554200.aspx) - 探索 CQRS 和事件溯源.
- [Domain-Driven Design: The First 15 Years](https://dddeurope.com/15years)  - 为庆祝周年纪念，我们已邀请软件设计界的知名作者贡献新旧论文.  Martin Fowler、James Coplien、Rebecca Wirfs-Brock、Mel Conway 等做出了贡献.
- [DDD Reference](http://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) - DDD 的模式和定义的总结.
- [Domain Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly) - Domain Driven Design Quickly 是对 DDD 基础知识的简短、易读的总结和介绍.
- [Effective Aggregate Design](http://dddcommunity.org/library/vernon_2011/) - 在这个由三部分组成的系列中，Vaughn Vernon 介绍了一些常见的设计陷阱，讨论了各种聚合建模选择的优缺点，并提供了指导聚合建模的经验法则.
- [Getting Started with DDD when Surrounded by Legacy Systems](http://domainlanguage.com/wp-content/uploads/2016/04/GettingStartedWithDDDWhenSurroundedByLegacySystemsV1.pdf) - 描述当您对遗留系统有重大承诺时开始使用 DDD 的三种策略.
- [Living Documentation by Design, with Domain-Driven Design](https://leanpub.com/livingdocumentation) - 了解活文档如何在项目的各个方面为您提供帮助，从业务目标到业务领域知识、架构和设计、流程和部署，即使您讨厌编写文档.
- [.NET Microservices: Architecture for Containerized .NET Applications](https://dotnet.microsoft.com/download/thank-you/microservices-architecture-ebook) - 介绍开发基于微服务的应用程序并使用容器管理它们. [eShopOnContainers sample](https://github.com/dotnet-architecture/eShopOnContainers)
- [The Semantic JavaScript Backend for Event-Driven Development](https://docs.wolkenkit.io/1.1.0/downloads/brochure/) - 一本 68 页长的免费电子书，介绍什么是 DDD、CQRS 和事件溯源，以及它们如何相互配合.
- [DDD Magazine from Xebia #1](https://pages.xebia.com/domain-driven-design-magazine-xebia) - 这本杂志包含基于个人、业务和客户体验的富有远见和实用的见解，为您的 DDD 之旅提供支持
- [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/)  - Visual Collaboration Tools 是一本供团队构建软件的书. 它描述了对我们日常工作有帮助的工具，并展示了来自不同从业者的现场故事.

## Training Courses

- [DDD Workshops across Europe and Online](https://training.dddeurope.com/) - Eric Evans、Alberto Brandolini、Mathias Verraes、Rebecca Wirfs-Brock、Nick Tune 等人举办的公共研讨会.
- [Domain Language eLearning](http://elearn.domainlanguage.com/) - 使用我们与域驱动设计 (DDD) 原著作者 Eric Evans 的视频课程，自学发展实用模型的技术，从而改进您的软件——而不仅仅是您的文档.
- [Greg Young's CQRS Class](http://subscriptions.viddler.com/GregYoung/) - 这些视频包括 Greg Young 的 DDD、CQRS 和事件溯源课程的全部内容.
- [Distilling Domain-Driven Design](https://forcomprehension.com/) - Vaughn Vernon 的在线培训课程.
- [Advanced Distributed Systems Design](https://learn-particular.thinkific.com/courses/adsd-online) - Online training course from Udi Dahan.  Udi's live training schedule can be found [here](http://udidahan.com/training/).
- [Nomad PHP](https://nomadphp.com/product/introduction-event-sourcing-cqrs/) - 事件溯源和 CQRS 简介.
- [Event Sourcery](https://eventsourcery.com/) - DDD、CQRS 和事件溯源简介.
- [Mixter](https://github.com/DevLyon/mixter) - CQRS 和事件溯源 Koans.
- [Pluralsight](https://pluralsight.com)
	 - [Domain-Driven Design Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) - 通过演示客户交互和复杂的演示应用程序以及 Eric Evans 的建议，教授领域驱动设计 (DDD) 的基础知识.
	 - [Domain-Driven Design in Practice](https://www.pluralsight.com/courses/domain-driven-design-in-practice) - 在实践中应用领域驱动设计原则的描述性、深入的演练.
	 - [Modern Software Architecture: Domain Models, CQRS, and Event Sourcing](https://www.pluralsight.com/courses/modern-software-architecture-domain-models-cqrs-event-sourcing)  - 本课程涵盖有助于发现业务领域顶层架构的 DDD 分析模式. 架构师和开发人员将找到实现模式的详细信息，例如领域模型、CQRS 和事件溯源.
- [Rails + Domain Driven Design Workshop](https://blog.arkency.com/ddd-training/) - 为 Ruby/Rails 开发人员介绍 DDD、CQRS 和事件溯源的基础知识.
- [Reactive Architecture: Domain Driven Design](https://cognitiveclass.ai/courses/reactive-architecture-ddd/)  - 使用 DDD 将问题域分解为可管理的部分. 了解这些部分如何成为反应式微服务和反应式架构的基础. 免费，在线，自定进度. 完成后提供证书.
- [Reactive Architecture: CQRS and Event Sourcing](https://cognitiveclass.ai/courses/reactive-architecture-cqrs/)  - 本课程将讨论我们使用 CQRS/ES 的原因，它为我们带来的好处，以及使用它的成本. 我们将看到 CQRS/ES 如何影响我们应用程序的可扩展性、一致性和可用性.
- [DDD Workshop by Xebia](https://xebia.com/academy/en/search?query=Domain-driven%20design) - 从基础到专业水平的公共和内部领域驱动设计研讨会.

## Video Collections

- [DDD Europe](https://dddeurope.com/videos) - 在 DDD Europe 上进行的会谈录音.
- [SkillsCasts by SkillsMatter](https://skillsmatter.com/skillscasts) - 搜索 DDD 会返回 Greg Young、Alberto Brandolini 和 Dan North 等人的各种演讲.
- [Alberto Brandolini: Event Storming](https://www.youtube.com/watch?v=veTVAN0oEkQ&list=PLve553MhJLs4YkEnHmOjWJv0B-6WY0-JI) - Alberto Brandolini 就事件风暴发表的 YouTube 演讲集.
- [GlobalAppTesting TechTalks](https://vimeo.com/showcase/gatengineering) - 一个专注于 DDD 和 CQRS 的 vimeo 频道.
- [Greg Young](https://www.youtube.com/watch?v=JHGkaShoyNs&list=PL5XpN_ZVafKLePdxruDfdfi-IiZtXz-k9) - Greg Young 提供的各种演讲的 YouTube 集合.
- [Explore DDD videos](https://www.youtube.com/channel/UCcpKGt6MVvz7dISXLlMGmag) - 在探索 DDD 会议上的演讲录音.
- [KanDDDinsky](https://www.youtube.com/channel/UCJCpnslPdb_Dl8DKokXC3HA) - 在 KanDDDinsky 上发表的 YouTube 演讲集.
- [Virtual Domain-driven design](https://www.youtube.com/channel/UCob_jOzzpxBp-di-x0vLlwA) - 来自虚拟领域驱动设计的 youtube 记录的聚会会话集
- [The Art of Discovering Bounded Contexts by Nick Tune](https://www.youtube.com/watch?v=ez9GWESKG4I) - 来自 2017 DevoxxUK 的关于如何定义有界上下文的会议

## Community Resources

- [DDD/CQRS Google Group](https://groups.google.com/forum/?utm_source=digest&utm_medium=email#!forum/dddcqrs) - 一个活跃的邮件列表和一个很好的资源，可以提出问题并了解有关 DDD/CQRS 的详细信息.
- [Domain Driven Design Yahoo Group](https://groups.yahoo.com/neo/groups/domaindrivendesign/conversations/messages)  - 这个小组讨论设计软件的领域驱动风格，以及 Eric Evans 的书，领域驱动设计：解决商业软件核心的复杂性. 欢迎对本书内容提出问题和讨论，也欢迎分享应用 DDD 的经验，以及对该主题的一般讨论.
- [DDDinPHP Google Group](https://groups.google.com/forum/#!forum/dddinphp) - 在 PHP 的上下文中讨论领域驱动设计、CQRS、事件溯源、模型风暴、六边形架构、分布式系统、反应式……的地方.
- [DDD in Ruby subreddit](https://www.reddit.com/r/ddd_ruby/) - 为对领域驱动设计感兴趣的 Ruby 开发人员提供的子版块.
- [EventStormers Google+ Community](https://plus.google.com/u/0/communities/113258571348605620818) - 一个公共讨论组，供所有对 EventStorming 和相关主题感兴趣的人使用.
- [DDD/CQRS/ES Slack](https://github.com/ddd-cqrs-es/slack-community)  - 为那些想聊聊领域驱动设计、CQRS、事件溯源以及有时是随机事物的人提供一个松弛的团队. 主渠道与语言和框架无关.
- [Domain StoryTelling Slack](https://domainstorytelling.slack.com)  - 一个关于域讲故事的松弛团队. 目前仅限邀请，但您可以询问 [@hofstef](https://twitter.com/hofstef) 邀请. 主页位于 [domainstorytelling.org](http://domainstorytelling.org/).
- [Software Engineering Stack Exchange](http://softwareengineering.stackexchange.com/questions/tagged/domain-driven-design) - 软件工程堆栈交换问题标记为*领域驱动设计*.
- [Code Review Stack Exchange](http://codereview.stackexchange.com/questions/tagged/ddd) - 代码审查堆栈交换问题标记为 *domain-driven-design*.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/domain-driven-design) - 标记为 *domain-driven-design* 的 Stack Overflow 问题.
- [Advanced Topics in Event Sourcing / CQRS / DDD](https://github.com/sebastianharko/adv-es-cqrs-ddd) - 由@编译和维护的事件溯源/CQRS/DDD列表中的高级主题[sebastianharko](https://github.com/sebastianharko).
- [Quora](https://www.quora.com/topic/Domain-Driven-Design-DDD) - 标记为*领域驱动设计*的问题.
- [wolkenkit Slack](http://slackin.wolkenkit.io/) - DDD、事件溯源、CQRS 和 wolkenkit 方面的 Slack 团队.
- [Awesome Event Storming](https://github.com/mariuszgil/awesome-eventstorming) - 很棒的列表，只关注事件风暴.
- [Virtual Domain-driven design community](https://virtualddd.com) - 包含小组讨论、在线协作和资源共享的在线聚会.
- [Domain-driven design heuristics](https://www.dddheuristics.com/) - 领域驱动设计启发式是一个社区驱动的网站，用于记录和讨论设计启发式.
- [Context Mapping by ddd-crew](https://github.com/ddd-crew/context-mapping) - ddd-crew 的上下文映射备忘单和入门工具包.

## Blogs

- [Nick Chamberlain](https://buildplease.com) - 为 .NET 开发人员提供有用的开发和设计建议.
- [Ardalis.com](https://ardalis.com/blog)  - 史蒂夫史密斯.  Pluralsight 作者和作者 [DDD Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) 课程和微软 [eShopOnWeb sample app](https://github.com/dotnet-architecture/eShopOnWeb).
- [DDD Weekly](http://dddweekly.com) - 与 DDD/CQRS/ES 相关的每周精选链接.
- [Daniel Whittaker](http://danielwhittaker.me)  - 想了解 CQRS 和事件溯源？ 该博客包含分步文章，可让您抢先一步.
- [Cyrille Martraire](http://cyrille.martraire.com) - 如此沉迷于金融，同时仍然热爱编程，我自然是 Eric Evans 的领域驱动设计的忠实粉丝，以及 TDD、BDD 和敏捷/XP 实践.
- [Jimmy Bogard](https://lostechies.com/jimmybogard/) - 我专注于 DDD、分布式系统和任何其他以首字母缩略词为中心的设计/架构/方法.
- [CodeBetter](http://codebetter.com) - CodeBetter.Com 的存在是为了帮助在软件开发社区内培养对更好的实践、卓越的工具、经过验证的方法和技术的认识.
- [Greg Young](https://goodenoughsoftware.net/) - 足够好软件的定义是足够好.
- [InfoQ Blog](https://www.infoq.com/domaindrivendesign/) - InfoQ 上的领域驱动设计内容.
- [Dan North](https://dannorth.net/blog/)  - 行为驱动设计的发明者. 博客和讨论事件风暴也.
- [Mike Mogosanu](http://blog.sapiensworks.com)  - 可维护的代码是一种商业优势. 领域图的创造者：领域建模工具——简单而强大的领域驱动设计.
- [Christian Posta](http://blog.christianposta.com) - 首席中间件架构师 @ Red Hat，开源爱好者，提交者 @ Apache，云，集成，Kubernetes，Docker，OpenShift，Fabric8.
- [Vladimir Khorikov](http://enterprisecraftsmanship.com)  - Pluralsight 作者. 关于软件开发原则和最佳实践的博客.
- [TechBeacon](http://techbeacon.com/) - TechBeacon 上的文章标记为*领域驱动设计*.
- [Derek Comartin](http://codeopinion.com) - *领域驱动设计*类别下的文章.
- [Alberto Brandolini](https://ziobrando.blogspot.it)  - 事件风暴的发明者.  Alberto 断言问题无法以产生问题的相同心态来解决，他经常转换观点，假设架构师、导师、教练、经理或开发人员的观点.
- [Jérémie Chassaing](http://thinkbeforecoding.com/) - Various articles about DDD/CQRS.  Implemented Greg Young's SimpleCQRS sample in F#.
- [Vaughn Vernon](https://vaughnvernon.co) - Vaughn Vernon 了解软件开发的独特需求以及您在快节奏的行业中提高手艺时所面临的挑战.
- [Vladik Khononov](http://vladikk.com/) - 各种 DDD 相关文章.
- [Eventsourcing Publications](https://blog.eventsourcing.com) - 实际事件采购.
- [Jef Claes](http://www.jefclaes.be/) - 关于领域驱动设计的优秀文章和演讲.
- [Udi Dahan](http://udidahan.com/articles/) - 来自 NServiceBus 的创建者.
- [Chris Patterson](https://lostechies.com/chrispatterson/) - 来自 MassTransit 分布式应用程序框架的创建者.
- [Aaron Stannard](http://www.aaronstannard.com/) - 来自 Petabridge 的 CTO 和联合创始人，Akka.NET Actor Model 框架的开发人员.
- [Roger Johansson](https://rogeralsing.com/) - Mostly C#, DDD, and Akka.NET.
- [Konrad Garus](http://squirrel.pl/blog/)  - Java、Clojure 和 JavaScript 中的咆哮和编程. 在 *cqrs* 下标记的文章.
- [Oasis Digital](http://blog.oasisdigital.com/category/cqrs/) - Oasis Digital 的内容标记为 *cqrs*.
- [Adaptech](http://adaptechsolutions.net/blog/)  - Adaptech 解决方案博客. 我们的创始人 Adam Dymitruk 在 Greg 创造 CQRS 这个词之前与 Greg Young 就 CQRS 的优点进行了辩论.  Adam 和业务合作伙伴 Robert Reppel 是事件源微服务的领先实践者.
- [Lev Gorodinski](http://gorodinski.com/) - 从 2013 年开始有几篇关于 DDD 的文章，它们仍然具有相关性.
- [Dino Esposito](https://software2cents.wordpress.com/)  - 软件架构师、培训师、书籍作者. 作者 [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/).
- [Dan Bergh Johnsson "Dear Junior"](http://dearjunior.blogspot.se/search/label/domain%20driven%20design)  - 领域驱动设计与安全性相结合，总体上是敏捷的. 作为写给年轻程序员的虚构信件.
- [the native web](https://www.thenativeweb.io/blog/2017-10-25-09-46-ddd-and-co-part-1-whats-wrong-with-crud/) - DDD &amp; Co. 系列
- [Arkency](https://blog.arkency.com/) - 来自 Ruby 专家的各种 DDD、CQRS、事件溯源相关文章.
- [Svaťa Šimara](http://svatasimara.cz/) - DDD 系列 - 语言、领域、建模、基础设施、PHP 实现
- [Martin Havlišta](https://xhafan.com/blog/) - DDD, CQRS, TDD blog posts with code samples in C# .NET
- [Khalil Stemmler](https://khalilstemmler.com/articles/categories/domain-driven-design) - DDD系列介绍及谈如何用TypeScript实现DDD
- [Kenny Baas-Schwegler](https://baasie.com/) - DDD、BDD、社会技术、EventStorming 和持续交付博客.
- [João Rosa](https://joaorosa.io)  - 关于领域驱动设计、视觉协作、领导力和组织设计的个人博客. 以及介于两者之间的其他事情. 策展人 [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/) 和主持人 [Software Crafts Podcast](https://www.softwarecraftspodcast.com/)
- [GlobalAppTesting engineering](https://gat.engineering) - GlobalAppTesting 的工程博客，包含有关实用 DDD 和 CQRS 的材料.

## Sample Projects

### GO
- [BDD in GO](https://github.com/JankariTech/bsDateServer)  - 演示使用 Cucumber + GO 进行 BDD 测试方法的示例应用程序. 可以找到博文 [here](https://dev.to/jankaritech/demonstrating-bdd-behavior-driven-development-in-go-1eci).
- [Citerus DDD Sample App GO Port](https://github.com/marcusolsson/goddd) - 这是一个移植的尝试 [DDD Sample App](https://github.com/citerus/dddsample-core) 到惯用的 Go. 它可以在 dockerized 模式下运行以预览应用程序.
- [DDD by Refactoring](https://github.com/ThreeDotsLabs/wild-workouts-go-ddd-example)  - 完整的无服务器应用程序，展示如何通过对 Go 项目进行实际重构来应用 DDD、Clean Architecture 和 CQRS. 有关它的完整博客系列可以在以下位置找到<https://threedots.tech/> .
- [DDD Food App](https://github.com/victorsteven/food-app-server)  - 实现 4 层（域、基础设施、应用程序和接口）并考虑两种域模式的示例 DDD 应用程序. 有一篇为它写的博客文章 [here](https://dev.to/stevensunflash/using-domain-driven-design-ddd-in-golang-3ee5).
- [DDD Sample in GO](https://github.com/takashabe/go-ddd-sample) - 只是另一个实现四层 DDD 的示例应用程序.
- [Evolutive CRUD API](https://github.com/friendsofgo/gopherapi)  - 使用 SOLID、六边形架构的完整 CRUD 的 API 实现. 有一系列为它写的博客文章在<https://blog.friendsofgo.tech/> .
- [Simple Hexagonal Architecture PoC API](https://github.com/tomiok/patients-API) - 使用六边形架构模式的患者 API 的 PoC.

### .NET (C#/F#)
- [Better code with DDD building blocks](https://github.com/asc-lab/better-code-with-ddd)  - 解决方案展示了 DDD 战术模式的使用，以实现更好的代码可读性和表现力. 将 DDD 模式与无处不在的语言一起应用，缩小了专家和团队所说的语言以及代码中使用的语言之间的差距.
- [CQRS-DDD Example](https://github.com/dcomartin/DDD-CQRS-ES-Example) - 使用 GetEventStore、CommonDomain、NServiceBus、实体框架、SQL Server、SignalR 的领域驱动设计、CQRS 和事件溯源示例.
- [Companion Code for Microsoft .NET Architecting Applications for the Enterprise](https://github.com/mastreeno/Merp) - 基于事件的微型 ERP.
- [ContosoUniversityCore](https://github.com/jbogard/ContosoUniversityCore) - 带有完整 .NET 框架的 ASP.NET Core 上的 ContosoUniversity.
- [DDD-starter-dotnet](https://github.com/itlibrium/DDD-starter-dotnet)  - 构建 DDD 应用程序的各种方法的示例实现和比较. 作为快速启动 DDD .net 项目的基准非常有用.
- [DDDInventoryItemFSharp](https://github.com/eulerfx/DDDInventoryItemFSharp) - An idiomatic F# implementation of Domain-Driven Design
- [DDDSkeletonNet](https://github.com/andras-nemes/DDDSkeletonNet) (C#) - a .NET skeleton project to introduce the concepts of Domain Driven Design and loosely coupled layers.
- [DotNet CQRS Intro](https://github.com/asc-lab/dotnet-cqrs-intro) - 使用事件溯源的 CQRS 实施示例 - 进化方法（无 CQRS、具有相同模型的单独模型和命令、具有单独模型的单独模型和命令、单独的存储引擎、事件溯源）.
- [EISK](https://github.com/eisk) - 具有简单用例的 .NET CLI 和 VS 模板，可在具有架构最佳实践（DDD、洋葱架构等）的 .net 核心之上构建可扩展的应用程序.
- [EmailMaker](https://github.com/xhafan/emailmaker) - 电子邮件营销 ASP.NET Core MVC 和 ASP.NET MVC 演示应用程序演示 [CoreDdd](https://github.com/xhafan/coreddd) 用法
- [Equinox Project](https://github.com/EduardoPires/EquinoxProject) - 具有清洁架构、DDD、CQRS 和事件溯源概念的完整 ASP.NET Core 3.1 应用程序
- [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) - 来自 Microsoft 的完整 ASP.NET Core 3.1 参考应用程序，展示了整体部署架构
- [eShopOnContainersDDD](https://github.com/volak/eShopOnContainersDDD) - 以目录、购物篮、结账和订单有界上下文为特色的 eShop 全栈示例
- [Example of Domain-Driven Design in F#](https://gist.github.com/swlaschin/2ad8627d0400b2ab70e9f3da08902c9d)  - 跳棋游戏的领域驱动设计示例. 有两个文件：一个包含一系列设计的草稿文件和一个最终版本.
- [Event Sourcing .NET](https://github.com/oskardudycz/EventSourcing.NetCore)  - .NET 中有关事件溯源和 CQRS 的示例和资源. 还包含如何建立自己的活动商店的自定进度工具包
- [EventFlow.Example](https://github.com/OKTAYKIR/EventFlow.Example) - DDD、CQRS 和 Event-Sourcing 示例，包含以下技术堆栈： [EventFlow](https://github.com/eventflow/EventFlow), [EventStore](https://eventstore.com), [RabbitMQ](https://www.rabbitmq.com), [MongoDB](https://www.mongodb.com), [PostgreSQL](https://www.postgresql.org), [Docker](https://www.docker.com)
- [Fohjin](https://github.com/MarkNijhof/Fohjin) - 伴随 Mark Nijhof 的示例项目 [CQRS](https://leanpub.com/cqrs) 书.
- [FsUno](https://github.com/thinkbeforecoding/FsUno) - Event sourcing implementation sample in F#.
- [IDDD Samples in .NET](https://github.com/VaughnVernon/IDDD_Samples_NET) - These are the sample Bounded Contexts for C#.NET from the book "Implementing Domain-Driven Design" by Vaughn Vernon.
- [Microsoft Patterns and Practices: CQRS Journey Sample Code](https://github.com/mspnp/cqrs-journey) - 来自 CQRS Journey 的示例代码.
- [Modular Monolith](https://github.com/kgrzybek/modular-monolith-with-ddd) - 具有领域驱动设计方法的完整模块化单体 .NET 应用程序.
- [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) (.Net Core Preview 2) - N 层架构示例项目.
- [Photostock CQRS-DDD Example](https://github.com/mr0zek/Photostock)
- [Reactive Trader Cloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Adaptive Consulting 的反应式交易者云.
- [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) - .NET Core REST API CQRS 实现与原始 SQL 和 DDD 使用清洁架构.
- [Scritchy](https://github.com/ToJans/Scritchy) - 没有管道的 CQRS， [video](http://www.youtube.com/watch?v=5DKTFZD3hu8).
- [Simple CQRS in F#](https://github.com/thinkbeforecoding/m-r) - Greg Young's SimpleCQRS in F#.
- [SimpleCQRS](https://github.com/gregoryyoung/m-r) - Greg Young 的“Simplest Thing”CQRS 与 Event Sourcing 项目.
- [TaskoMask](https://github.com/hamed-shirbandi/TaskoMask) - 基于 .NET Core 的任务管理系统，具有 DDD、CQRS 和事件溯源概念.
- [TodoMVC-DDD-CQRS-EventSourcing](https://github.com/volak/TodoMVC-DDD-CQRS-EventSourcing) - Implementation of basic Todo app via tastejs/todomvc in C#/Typescript with eventsourcing, cqrs, and domain driven design

### Haskell
- [Eventuria gsd](https://github.com/Eventuria/gsd) - 带有 DDD、CQRS 和事件溯源、FRP 的 Haskell 待办事项列表反应式应用程序.

### Idris
- [OrderTaking](http://github.com/andorp/order-taking)  - Domain Modeling Made Functional 一书的依赖类型实现. 一个示例项目，如何使用依赖类型来形式化有界上下文和工作流图. 一个 NodeJS 可部署的演示.

### JavaScript
- [wolkenkit Sample Applications](https://docs.wolkenkit.io/latest/media/sample-applications/wolkenkit-boards/) - DDD 示例应用程序的集合，例如 TodoMVC、地理缓存应用程序、协作板等.
- [Booster framework examples](https://github.com/boostercloud/booster/tree/master/docs/examples) 使用 Booster Framework 构建的示例应用程序.

### JVM languages
- [Akka CQRS ES Demo](https://github.com/mdonkers/akka-cqrs-es-demo) - 在 Scala-Akka 中实现 CQRS 和事件溯源模式的演示项目.
- [DDD By Examples - Library](https://github.com/ddd-by-examples/library)  - 由真实业务需求驱动的库示例项目. 在 DDD、BDD、EventStorming、示例映射、CQRS 等帮助下实现的模块化单体.
- [DDD Leaven](https://github.com/BottegaIT/ddd-leaven-v2) - DDD-CQRS 示例 v2.0 项目，可帮助您开始使用 Spring、JPA 和测试进行高级域建模.
- [DDD Workshop - Project Manager](https://github.com/mkopylec/project-manager)  - “自己动手”DDD 研讨会和示例 DDD 应用程序同时进行. 基于项目管理域.
- [Event Sourcing Example](https://github.com/Pragmatists/eventsourcing-java-example) - Java 代码的事件溯源和 CQRS 实现的简化（在内存中）示例（为银行领域用例建模）.
- [Event Sourcing and CQRS Examples](https://github.com/andreschaffer/event-sourcing-cqrs-examples) - Java 中事件溯源和 CQRS 的实用应用，对常见相关问题有很好的参考，例如事件排序和幂等性.
- [Event Sourcing and CQRS Sample](https://github.com/pilloPl/event-source-cqrs-sample) - 具有命令查询职责分离的示例事件源应用程序
- [IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) - 这些是 Vaughn Vernon 的“实施领域驱动设计”一书中的示例限界上下文.
- [Java CQRS Intro](https://github.com/asc-lab/java-cqrs-intro) - 使用事件溯源的 CQRS 实施示例 - 进化方法（无 CQRS、具有相同模型的单独模型和命令、具有单独模型的单独模型和命令、单独的存储引擎、事件溯源）.
- [Kotlin DDD Sample](https://github.com/fabriciorissetto/kotlin-ddd-sample) - 用 Kotlin 编写的示例 DDD/CQRS 项目.
- [EventStormingWorkshop - Designing Cloud Native Microservices On AWS](https://github.com/humank/EventStormingWorkShop/) - 通过 EventStorming 研讨会并在 Java 中实现 DDD 战术设计模式的具体示例，应用 AWS 云原生服务来构建基于业务 Event 的 Coffeeshop 场景.
- [DDDSample](https://github.com/citerus/dddsample-core) - 使用 Spring Boot 的示例 DDD 项目（最初托管在 http://dddsample.sourceforge.net/ 中）
- [Eclipse CargoTracker](https://eclipse-ee4j.github.io/cargotracker/) - 该项目演示了如何使用 Jakarta EE 平台使用广泛采用的架构最佳实践（如领域驱动设计 (DDD)）开发应用程序. [The code](https://github.com/eclipse-ee4j/cargotracker/) 旨在反映实际工作中的开发人员将使用的非平凡应用程序. 它试图直接展示如何使用 Jakarta EE 来有效地满足实际的企业关注点，例如生产力、敏捷性、可测试性、灵活性、可维护性、可伸缩性和安全性. 该项目直接基于众所周知的原作 [Java DDD sample application](https://github.com/citerus/dddsample-core) 由 DDD 先驱 Eric Evans 的公司 Domain Language 和瑞典软件咨询公司 Citerus 开发. 
- [https://github.com/felipexw/clean-arch-ddd-intro](https://github.com/felipexw/clean-arch-ddd-intro) - 使用 Micronaut 的简单 DDD + 清洁架构.

### PHP
- [DDD CQRS Todo Sample](https://github.com/ferrius/ddd-cqrs-example) - 使用 PHP 7 和 Symfony 5 构建的 DDD CQRS ADR 六边形架构实现.
- [DDD Wish List](https://github.com/franzose/symfony-ddd-wishlist) - 使用 Symfony 3 和 Vue.js 构建的 PHP 示例应用程序.
- [DDD Playground](https://github.com/jorge07/ddd-playground/) - PHP 中的示例实现.
- [Eric Evans DDD Cargo Sample](https://github.com/codeliner/php-ddd-cargo-sample) - Eric Evans DDD 书中使用的货物样本的 PHP 7 版本
- [Shop Cart in PHP](https://github.com/simara-svatopluk/cart) - Sample project that demonstrates how simple shop cart can look like. Domain objects,Doctrine integration.,TDD,layers,unit testing
- [Symfony 5 DDD ES CQRS backend](https://github.com/jorge07/symfony-5-es-cqrs-boilerplate) - 使用 Symfony 和 PHP 8 的 DDD、CQRS 和事件溯源应用程序.

## Libraries and Frameworks

### GO
- [Ginkgo](https://github.com/onsi/ginkgo) - Ginkgo 建立在 Go 的测试包之上，允许富有表现力的行为驱动开发（“BDD”）风格的测试.
- [GOBDD](https://github.com/go-bdd/gobdd) - GO 的小型 BDD 框架.
- [GoConvey](https://github.com/smartystreets/goconvey)  - 在浏览器中进行测试. 与`go test`集成. 用 Go 编写行为测试.
- [Godog](https://github.com/cucumber/godog) - 包 godog 是 Golang 的官方 Cucumber BDD 框架，它将规范和测试文档合并为一个有凝聚力的整体，使用 Gherkin 格式的场景，格式为 Given、When、Then.

### .NET
- [Aggregates.NET](https://github.com/volak/Aggregates.NET) - 通过 NServicebus 和 GetEventStore 的 .NET 事件源域驱动设计模型.
- [AggregateSource](https://github.com/yreynhout/aggregateSource) - 使用聚合进行事件溯源的轻量级基础设施.
- [Akka.NET](http://getakka.net/) - Akka.NET 是一个工具包和运行时，用于在 .NET 和 Mono 上构建高度并发、分布式和容错的事件驱动应用程序.
- [ABP](https://abp.io) - ASP.NET Boilerplate 的继任者 - 基于 ASP.NET Core 的应用程序框架，用于创建 NLayered、域驱动设计的 Web 应用程序，具有以微服务为中心的模块化架构
- [ASP.NET Boilerplate](http://aspnetboilerplate.com/) - 基于 ASP.NET MVC、Web API 和 ASP.NET Core 的应用程序框架，用于创建 NLayered、领域驱动设计的 Web 应用程序，实现最佳实践.
- [ByValue](https://github.com/sm-g/ByValue) - 这个库有助于创建具有正确实现相等行为的 ValueObjects（即使具有集合属性）.
- [Cedar.CommandHandling](https://github.com/damianh/Cedar.CommandHandling)  - 通过 HTTP 处理命令的中间件； 通常用于 CQRS 应用程序.
- [Cirqus](https://github.com/d60/Cirqus) - d60 事件溯源 + CQRS 框架.
- [CommandQuery](https://github.com/hlaueriksson/CommandQuery) - ASP.NET Core ⚡AWS Lambda ⚡Azure Functions ⚡Google Cloud Functions ASP.NET Web API 2 的命令查询分离
- [CoreDdd](https://github.com/xhafan/coreddd) - 一组开源 .NET 库，有助于 DDD 和 CQRS，具有 NHibernate 持久性
- [CQRS on Azure](https://github.com/MerrionComputing/CQRSAzure) Windows Azure 上的 CQRS.
- [Dolittle](https://dolittle.com)  - 使用 Dolittle 构建更好的应用程序. 一个以 DDD 为导向的事件源微服务平台，具有开发人员的生产力和简单性.
- [Edument CQRS and Intentful BDD Testing Starter Kit](https://www.cqrs.nu/) - 有关如何构建 CQRS/ES 应用程序的库和教程，包括 BDD 样式测试框架.
- [EventFlow](https://github.com/eventflow/EventFlow) - .NET http://geteventflow.net/ 的异步/等待第一个 CQRS+ES 和 DDD 框架.
- [Core.EventStore](https://github.com/younos1986/Core.EventStore)  - 促进 CommandService 和 QueryService 之间通信的库. 想法是当commandService中发生任何事件时，它应该被持久化在MongoDb中的QueryService中.
- [Its.Cqrs](https://github.com/jonsequitur/Its.Cqrs) - A set of libraries for CQRS and Event Sourcing, with a Domain-Driven Design flavor.
- [Marten](https://github.com/JasperFx/marten) - Postgresql as a Document Database and Event Store for .Net Applications.
- [MassTransit](https://github.com/MassTransit/MassTransit) - .NET 的分布式应用程序框架.
- [MediatR](https://github.com/jbogard/MediatR) - Supports request/response, commands, queries, notifications and events, synchronous and async with intelligent dispatching via C# generic variance.
- [MessageRouter](https://github.com/QuickenLoans/MessageRouter) - 在此视频中描述： [The Beating Heart of CQRS, or Actor-Based Message Routing on the CLR](https://vimeo.com/171178586) by Paulmichael Blasucci at the New York F# .NET User Group.
- [NetDevPack](https://github.com/netdevpack) - 一组智能的通用类和实现，可使用 .NET（DDD、CQRS、规范模式、MediatR、验证、通知）提高您的开发效率.
- [NEventStore](https://github.com/NEventStore/NEventStore) - 当使用事件溯源作为存储机制时，用于抽象不同存储实现的持久性库.
- [NServiceBus](https://github.com/Particular/NServiceBus) - .NET 的服务总线.
- [Projac](https://github.com/yreynhout/Projac) - Projac 是一组投影库，允许您编写针对各种后备存储的投影.
- [shriek-fx](https://github.com/ElderJames/shriek-fx) - 使用 .NET Core 2.0 开发的简单、优雅且有用的领域驱动设计和 CQRS 框架.
- [SqlStreamStore](https://github.com/damianh/SqlStreamStore) - 针对基于 SQL 的实现的 .NET 流存储库.
- [Streamstone](https://github.com/yevhen/Streamstone) - Azure 表存储的事件存储.
- [Stringly.Typed](https://github.com/mission202/Stringly.Typed) - 使字符串与 .NET 类型之间的转换更容易.
- [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0.

### Databases
- [Event Store](https://geteventstore.com) - 在 JavaScript 中具有复杂事件处理的开源功能数据库.
- [Eventsourcing](https://eventsourcing.com) - 业务事件捕获和查询框架.
- [Message DB](https://github.com/message-db/message-db)  - Postgres 的微服务原生事件存储和消息存储. 在 PostgreSQL 中为 Pub/Sub、事件溯源、消息传递和事件微服务应用程序实现的全功能事件存储和消息存储.
- [Serialized](https://serialized.io) - 事件溯源和 CQRS 的完整平台.

### Elixir
- [Commanded](https://github.com/slashdotdash/commanded) - CQRS/ES 应用程序的命令处理中间件，聚合和流程管理器的纯功能数据结构，点对点消息路由，以及 Elixir (Erlang VM) 中的更多功能 - 全部在 Actor 并发模型中.
- [Event Bus](https://github.com/otobus/event_bus) - Elixir 的可追溯、可扩展和极简的事件总线实现，具有基于 ETS 的内置事件存储和事件观察器.
- [eventstore](https://github.com/slashdotdash/eventstore) - CQRS 事件存储使用 PostgreSQL 进行持久化.

### JavaScript
- [cqrs.js](http://cqrs.js.org)  - node.js 中的 CQRS 实现. 包括 [node-eventstore](https://github.com/adrai/node-eventstore), [node-cqrs-domain](https://github.com/adrai/node-cqrs-domain), [node-eventdenormalizer](https://github.com/adrai/node-cqrs-eventdenormalizer), [node-cqrs-saga](https://github.com/adrai/node-cqrs-saga).
- [Node API Boilerplate](https://github.com/talyssonoc/node-api-boilerplate) - 适用于 DDD 和 Clean Architecture 应用程序的 NodeJS Web API 样板.
- [wolkenkit](https://www.wolkenkit.io/) - 适用于 JavaScript 和 Node.js 的 CQRS、DDD 和事件源框架.
- [Booster](https://www.booster.cloud/)  - 一个 CQRS、DDD 和事件源开源框架，它利用所有基础设施并使用高级抽象和约定. 它帮助用户构建先进的均衡驱动应用程序，让他们专注于业务逻辑.  
### JVM
- [akka-ddd](https://github.com/pawelkaczor/akka-ddd) - 遵循基于 CQRS/DDDD 的方法在 Akka 平台之上构建应用程序的可重用工件.
- [Apache Isis](https://isis.apache.org/index.html) - Apache Isis 是一个用于在 Java 中快速开发领域驱动应用程序的框架.
- [Axon Framework](http://www.axonframework.org/) - axon 框架专注于让想要基于 CQRS 原则创建 java 应用程序的开发人员的生活更轻松.
- [DDDplus framework](https://github.com/funkygao/cp-ddd-framework) - 基于DDD的复杂业务架构的轻量级灵活开发框架.
- [JESA](https://github.com/yreynhout/JESA) - Java 的事件源聚合.
- [Lagom](https://www.lagomframework.com)  - Lagom 框架是用于 Java 虚拟机的微服务框架，具有用于 Java 和 Scala 语言的 API. 它包括一个基于事件溯源/CQRS 的持久性模块.
- [SeedStack's Business Framework](http://seedstack.org/docs/business/) - 一组构建块，使您能够根据领域驱动设计 (DDD) 方法对业务逻辑进行编码.
- [Spine Event Engine](https://spine.io/)  - 用于构建云应用程序的 CQRS/ES 框架. 在 Protobuf 中定义限界上下文及其命令、事件和实体状态. 后端逻辑是用 Java 编写的，位于 Proto 生成的代码之上.  Java、JS 或 Dart 中的客户端代码通过 gRPC 与后端通信.

### PHP
- [Broadway](https://github.com/broadway/broadway) - Broadway 是一个 (PHP) 项目，为创建 CQRS 和事件源应用程序提供基础设施和测试助手.
- [Ecotone](http://ecotone.tech) - 在 PHP 中启用消息驱动架构，并提供构建块以遵循 DDD 和 CQRS 原则.

### Python
- [Eventsoucing in Python](https://github.com/johnbywater/eventsourcing)  - 用于事件溯源和 DDD 的成熟、稳定的 Python 库. 支持各种数据库、不同类型的域事件排序、应用程序级加密、快照、乐观并发控制和处理事件. 应用程序和整个应用程序系统可以独立于基础设施进行定义，并以不同的方式（单线程、多线程、时钟、步进、多进程、参与者模型）和不同的基础设施运行.
- [dry-python](https://github.com/dry-python) - 一组用于可插拔业务逻辑组件的库.

### Ruby
- [Eventide](https://eventide-project.org)  - Ruby 的事件溯源和微服务堆栈. 一组用于编写事件驱动的自治服务的库.
- [Rails Event Store](https://railseventstore.org)  - Rails Event Store (RES) 是一个用于发布、消费、存储和检索事件的库. 它是您为 Rails 应用程序使用事件驱动架构的最佳伴侣.

## Podcasts and Interviews

- [Deeper into DDD on DotNetRocks with David Real](http://dotnetrocks.com/?show=1151) - 2015 年 6 月 11 日.
- [Thinking in DDD on DotNetRocks with Julie Lerman and Steve Smith](http://dotnetrocks.com/?show=1023) - 2014 年 8 月 19 日.
- [Eric Evans on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=236) - 2007 年 5 月 10 日.
- [Jimmy Nilsson on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=191) - 2006 年 8 月 29 日.
- [Being the Worst](http://www.beingtheworst.com) - 2012 年至 2016 年.
- [Software Engineering Radio Episode 225: Eric Evans on Domain-Driven Design at 10 Years](http://www.se-radio.net/2015/05/se-radio-episode-226-eric-evans-on-domain-driven-design-at-10-years/) - 2015 年 5 月 13 日.
- [Software Engineering Radio Episode 218: Udi Dahan on CQRS (Command Query Responsibility Segregation)](http://www.se-radio.net/2015/01/episode-218-udi-dahan-on-cqrs-command-query-responsibility-segregation/) - 2015 年 1 月 30 日.

## Conferences

- [Domain-Driven Design Europe](https://dddeurope.com) - 领先的 DDD 会议（COVID19 期间在线）
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

- [Domain Storytelling](http://www.domainstorytelling.org/)  - 一种知识处理技术，可帮助相关人员熟悉该领域并制定出表达他们共同理解的模型. 可作为 [print-out template](http://www.domainstorytelling.org/images/DST_Whiteboard-Kit.pdf)，以及开源在线工具， [WPS Modeler](https://www.wps.de/modeler) ([source](https://github.com/wps/domain-story-modeler)).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Nick Chamberlain](https://buildplease.com) 已放弃本作品的所有版权和相关或邻近权利.
