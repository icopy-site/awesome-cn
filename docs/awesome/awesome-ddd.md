<div class="github-widget" data-repo="heynickc/awesome-ddd"></div>
## Awesome Domain-Driven Design [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;域驱动设计（DDD），命令查询责任隔离（CQRS），事件源和事件存储资源的精选列表.

**看看我 [blog](https://buildplease.com) 和 [weekly DDD newsletter](https://buildplease.com/pages/dddweekly/) 或者打招呼 [Twitter](https://twitter.com/heynickc)!**

**[Domain-Driven Design (DDD)](https://en.m.wikipedia.org/wiki/Domain-driven_design) **是一种通过将实现连接到不断发展的模型来满足复杂需求的软件开发方法.  域驱动设计的前提如下：

- 将项目的主要重点放在核心域和域逻辑上
- 基于域模型的复杂设计
- 启动技术专家和领域专家之间的创造性协作，以迭代方式完善解决特定领域问题的概念模型

这个词是埃里克埃文斯在他的同名书中创造的.

**[Command Query Responsibility Segregation (CQRS)](http://codebetter.com/gregyoung/2010/02/16/cqrs-task-based-uis-event-sourcing-agh/) **只是创建了两个对象，而以前只有一个对象.  分离是基于方法是命令还是查询（Meyer在命令和查询分离中使用的定义相同，命令是任何改变状态的方法，查询是任何返回值的方法）.

**[Event Sourcing](http://www.martinfowler.com/eaaDev/EventSourcing.html)**事件源的基本思想是确保在事件对象中捕获应用程序状态的每个更改，并且这些事件对象本身按照它们应用的顺序存储，其生命周期与应用程序状态本身相同.

**[Event Storming](https://ziobrando.blogspot.com/2013/11/introducing-event-storming.html)**是一种快速探索复杂业务领域的研讨会格式.



## Books

- [Applying Domain Driven Design with CQRS and Event Sourcing](https://buildplease.com/pages/now-what/) - 使用EventStorming和其他建模技术为虚构的业务领域构建基于CQRS和事件采购的原型的演练.
- [CQRS](https://leanpub.com/cqrs)   -  Mark Nijhof从Greg Young学习DDD和CQRS的经验.  本书附带了一个广泛的示例项目.
- [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215)   - 创造“领域驱动设计”一词的规范书籍.  也被称为“蓝皮书”.
- [Domain-Driven Design Distilled](https://www.amazon.com/Domain-Driven-Design-Distilled-Vaughn-Vernon/dp/0134434420) - 阅读之前非常好的入门书 [Implementing Domain-Driven Design](https://vaughnvernon.co/?page_id=168#iddd) 要么 [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215).
- [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - 用PHP编写的真实示例，展示DDD架构风格，战术设计和有界上下文集成.
- [Domain-Driven Rails](https://blog.arkency.com/domain-driven-rails/) -  Domain-Driven Rails描述了11种技术（从Bounded Contexts到Event Sourcing），您可以在新旧Rails应用程序中单独使用这些技术来实现更好的架构.
- [Domain Specific Languages](http://martinfowler.com/books/dsl.html) - 与DDD切向连接，描述了泛在语言的重要性，并与领域专家合作，以及大量技术细节.
- [Event Sourcing and CQRS with .NET Core and SQL Server](https://buildplease.com/products/fpc-v2/) - 使用ASP.NET Core和SQL Server在生产中使用域驱动设计与事件源和CQRS的演练.
- [Implementing Domain-Driven Design](https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)   - 这是一本规范书籍，提供了一种自上而下的方法来理解领域驱动设计.  也被称为“红皮书”.
- [Introducing Event Storming: An act of Deliberate Collective Learning](https://leanpub.com/introducing_eventstorming) - 关于EventStorming的最深入的教程和解释，直接来自发明者.
- [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/) - 软件架构师的核心实践摘要，实用.
- [Patterns, Principles, and Practices of Domain-Driven Design (1st Edition)](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709) - Methods for managing complex software construction following the practices, principles and patterns of Domain-Driven Design with code examples in C#.
- [Secure by Design (early access)](https://www.manning.com/books/secure-by-design?a_aid=danbjson&a_bid=0b3fac80) - 演示如何使用域驱动设计来避免安全漏洞.
- [Specification by Example](https://www.manning.com/books/specification-by-example)   - 本书从全球领先团队的经验中提炼出有效的方法，可以在短暂的迭代交付周期中指定，测试和交付软件.  本书中的案例研究范围从小型网络初创公司到大型金融机构，在许多流程中工作，包括XP，Scrum和看板.
- [Versioning in an Event Sourced System](https://leanpub.com/esversioning)   - 您是否在使用事件源系统进行版本控制时遇到了麻烦？  刚刚第一次进入一个新的Event Sourced系统？  本书是如何在很长一段时间内处理版本控制的权威指南.
- [Writing Great Specifications](https://www.manning.com/books/writing-great-specifications) - 编写出色的规范是一个示例丰富的教程，它教你如何编写好的Gherkin规范文档，这些文档利用了Specification by Example的优点.

## Free eBooks

- [The Anatomy of Domain-Driven Design - The Infographic](https://leanpub.com/theanatomyofdomain-drivendesign) - 关于领域驱动设计解剖学的信息图.
- [Architecting Modern Web Applications with ASP.NET Core and Microsoft Azure](https://dotnet.microsoft.com/download/thank-you/aspnet-ebook) - 提供有关使用DDD，ASP.NET Core和Azure构建单一Web应用程序的端到端指导. [eShopOnWeb sample](https://github.com/dotnet-architecture/eShopOnWeb)
- [CQRS Journey](https://msdn.microsoft.com/en-us/library/jj554200.aspx) - 探索CQRS和事件采购.
- [DDD Reference](http://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) -  DDD模式和定义的摘要.
- [Domain Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly) - 领域驱动设计快速简化，快速阅读的DDD基础知识摘要和介绍.
- [Effective Aggregate Design](http://dddcommunity.org/library/vernon_2011/) - 在这个由三部分组成的系列中，Vaughn Vernon介绍了一些常见的设计缺陷，讨论了各种聚合建模选择的优缺点，并提供了指导聚合建模的经验法则.
- [Getting Started with DDD when Surrounded by Legacy Systems](http://domainlanguage.com/wp-content/uploads/2016/04/GettingStartedWithDDDWhenSurroundedByLegacySystemsV1.pdf) - 描述了对遗留系统做出巨大贡献时开始使用DDD的三种策略.
- [Living Documentation by Design, with Domain-Driven Design](https://leanpub.com/livingdocumentation) - 了解Living Documentation如何在项目的各个方面为您提供帮助，从业务目标到业务领域知识，架构和设计，流程和部署，即使您讨厌编写文档.
- [.NET Microservices: Architecture for Containerized .NET Applications](https://dotnet.microsoft.com/download/thank-you/microservices-architecture-ebook) - 介绍如何开发基于微服务的应用程序并使用容器管理它们. [eShopOnContainers sample](https://github.com/dotnet-architecture/eShopOnContainers)
- [The Semantic JavaScript Backend for Event-Driven Development](https://docs.wolkenkit.io/1.1.0/downloads/brochure/) -  68页长的免费电子书，关于DDD，CQRS和事件采购是什么，以及它们如何相互适应.

## Training Courses

- [Domain Language eLearning](http://elearn.domainlanguage.com/) - 使用我们与领域驱动设计（DDD）原书的作者Eric Evans的视频课程，自学技巧，不断改进软件的实用模型，而不仅仅是文档.
- [Greg Young's CQRS Class](http://subscriptions.viddler.com/GregYoung/) - 这些视频包括Greg Young的全部DDD，CQRS和Event Sourcing课程.
- [Distilling Domain-Driven Design](https://forcomprehension.com/) -  Vaughn Vernon的在线培训课程.
- [Advanced Distributed Systems Design](https://learn-particular.thinkific.com/courses/adsd-online)   -  Udi Dahan的在线培训课程.  可以找到Udi的现场训练计划 [here](http://udidahan.com/training/).
- [Nomad PHP](https://nomadphp.com/product/introduction-event-sourcing-cqrs/) - 事件采购和CQRS简介.
- [Event Sourcery](https://eventsourcery.com/) -  DDD，CQRS和事件采购简介.
- [Mixter](https://github.com/DevLyon/mixter) -  CQRS和Event Sourcing Koans.
- [Pluralsight](https://pluralsight.com)
	 - [Domain-Driven Design Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) - 通过演示客户交互和复杂的演示应用程序以及Eric Evans的建议，教授领域驱动设计（DDD）的基础知识.
	 - [Domain-Driven Design in Practice](https://www.pluralsight.com/courses/domain-driven-design-in-practice) - 在实践中应用领域驱动设计原则的描述性深入演练.
	 - [Modern Software Architecture: Domain Models, CQRS, and Event Sourcing](https://www.pluralsight.com/courses/modern-software-architecture-domain-models-cqrs-event-sourcing)   - 本课程介绍DDD分析模式，有助于发现业务领域的顶级体系结构.  架构师和开发人员将找到实施模式的详细信息，例如域模型，CQRS和事件源.
- [Rails + Domain Driven Design Workshop](https://blog.arkency.com/ddd-training/) -  DDD简介，CQRS的基础知识和Ruby / Rails开发人员的事件采购.
- [Reactive Architecture: Domain Driven Design](https://cognitiveclass.ai/courses/reactive-architecture-ddd/)   - 使用DDD将问题域分解为可管理的部分.  了解这些部件如何成为Reactive Microservices和Reactive Architecture的基础.  免费，在线，自定进度.  完成后提供证书.
- [Reactive Architecture: CQRS and Event Sourcing](https://cognitiveclass.ai/courses/reactive-architecture-cqrs/)   - 本课程将讨论我们使用CQRS / ES的原因，它为我们提供的好处，以及我们使用它的成本.  我们将了解CQRS / ES如何影响我们应用程序的可伸缩性，一致性和可用性.

## Video Collections

- [DDD Europe](https://dddeurope.com) - 记录在DDD Europe发表的谈话.
- [SkillsCasts by SkillsMatter](https://skillsmatter.com/skillscasts) - 搜索DDD返回Greg Young，Alberto Brandolini和Dan North等人的各种演讲.
- [Alberto Brandolini: Event Storming](https://www.youtube.com/watch?v=veTVAN0oEkQ&list=PLve553MhJLs4YkEnHmOjWJv0B-6WY0-JI) -  Alberto Brandolini在Event Storming上发表的YouTube演讲集.
- [Greg Young](https://www.youtube.com/watch?v=JHGkaShoyNs&list=PL5XpN_ZVafKLePdxruDfdfi-IiZtXz-k9) -  Greg Young提供的各种演讲的YouTube收藏.
- [Explore DDD videos](https://www.youtube.com/channel/UCcpKGt6MVvz7dISXLlMGmag) - 记录探索DDD会议上的讲座.
- [KanDDDinsky](https://www.youtube.com/channel/UCJCpnslPdb_Dl8DKokXC3HA) -  KanDDDinsky提供的YouTube会谈集.

## Community Resources

- [DDD/CQRS Google Group](https://groups.google.com/forum/?utm_source=digest&utm_medium=email#!forum/dddcqrs) - 活跃的邮件列表和优秀的资源，可以提出问题并了解有关DDD / CQRS的细粒度详细信息.
- [Domain Driven Design Yahoo Group](https://groups.yahoo.com/neo/groups/domaindrivendesign/conversations/messages)   - 这个小组讨论领域驱动的设计软件风格，以及Eric Evans的书，领域驱动设计：处理商业软件中心的复杂性.  这里欢迎对书籍内容的问题和讨论，以及分享应用DDD的经验，以及对该主题的讨论.
- [DDDinPHP Google Group](https://groups.google.com/forum/#!forum/dddinphp) - 在PHP环境中讨论领域驱动设计，CQRS，事件源，模型风暴，六角架构，分布式系统，反应...的地方.
- [DDD in Ruby subreddit](https://www.reddit.com/r/ddd_ruby/) - 对域驱动设计感兴趣的Ruby开发人员的subreddit.
- [EventStormers Google+ Community](https://plus.google.com/u/0/communities/113258571348605620818) - 为所有对EventStorming感兴趣的人和相关主题的公共讨论组.
- [DDD/CQRS/ES Slack](https://t.co/MRxpx0rLH2)   - 对于那些想要聊聊领域驱动设计，CQRS，事件采购以及有时随机事物的人来说，这是一个松散的团队.  主要渠道是语言和框架无关.
- [Domain StoryTelling Slack](https://domainstorytelling.slack.com)   - 一个关于Domain StoryTelling的松散团队.  它目前只是邀请，但你可以问 [@hofstef](https://twitter.com/hofstef)  的邀请.  主页在 [domainstorytelling.org](http://domainstorytelling.org/).
- [Software Engineering Stack Exchange](http://softwareengineering.stackexchange.com/questions/tagged/domain-driven-design) - 软件工程Stack Exchange问​​题标记为* domain-driven-design *.
- [Code Review Stack Exchange](http://codereview.stackexchange.com/questions/tagged/ddd) - 代码审查Stack Exchange问​​题标记为* domain-driven-design *.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/domain-driven-design) -  Stack Overflow问题标记为* domain-driven-design *.
- [Advanced Topics in Event Sourcing / CQRS / DDD](https://github.com/sebastianharko/adv-es-cqrs-ddd) - 由@编译和维护的事件采购/ CQRS / DDD列表中的高级主题[sebastianharko](https://github.com/sebastianharko).
- [Quora](https://www.quora.com/topic/Domain-Driven-Design-DDD) - 标记为* domain-driven-design *的问题.
- [wolkenkit Slack](http://slackin.wolkenkit.io/) - 关于DDD，事件采购，CQRS和wolkenkit的Slack团队.
- [Awesome Event Storming](https://github.com/mariuszgil/awesome-eventstorming) - 非常棒的列表，仅关注事件风暴.

## Blogs

- [Nick Chamberlain](https://buildplease.com) - 为.NET开发人员提供有用的开发和设计建议.
- [DDD Weekly](http://dddweekly.com) - 与DDD / CQRS / ES相关的每周策划链接.
- [Daniel Whittaker](http://danielwhittaker.me)   - 想了解CQRS和事件采购？  这个博客包含一步一步的文章，为您提供一个良好的开端.
- [Cyrille Martraire](http://cyrille.martraire.com) - 在热爱编程的同时沉浸在金融领域，我自然是Eric Evans领域驱动设计的忠实粉丝，以及TDD，BDD和敏捷/ XP实践.
- [Jimmy Bogard](https://lostechies.com/jimmybogard/) - 我专注于DDD，分布式系统和任何其他以首字母缩略词为中心的设计/架构/方法.
- [CodeBetter](http://codebetter.com) -  CodeBetter.Com的存在是为了帮助培养对软件开发社区内更好的实践，卓越的工具，成熟的方法和技术的认识.
- [Greg Young](https://goodenoughsoftware.net/) - 良好的足够软件定义足够好.
- [InfoQ Blog](https://www.infoq.com/domaindrivendesign/) -  InfoQ上的域驱动设计内容.
- [Dan North](https://dannorth.net/blog/)   - 行为驱动设计的发明者.  关于事件风暴的博客和谈话也.
- [Mike Mogosanu](http://blog.sapiensworks.com)   - 可维护的代码是业务优势.  域映射的创建者：域建模工具 - 简单而强大的域驱动设计.
- [Christian Posta](http://blog.christianposta.com) - 首席中间件架构师@ Red Hat，开源爱好者，提交者@Apache，云，集成，Kubernetes，Docker，OpenShift，Fabric8.
- [Vladimir Khorikov](http://enterprisecraftsmanship.com)   -  Pluralsight作者.  有关软件开发原则和最佳实践的博客.
- [TechBeacon](http://techbeacon.com/) - 关于TechBeacon的文章标记*域驱动设计*.
- [Derek Comartin](http://codeopinion.com) - 类别*领域驱动设计*下的文章.
- [Alberto Brandolini](https://ziobrando.blogspot.it)   - 事件风暴的发明者.  断言这些问题无法用同样的思维方式来解决，而Alberto常常会从建筑师，导师，教练，经理或开发人员的角度出发.
- [Jérémie Chassaing](http://thinkbeforecoding.com/) - Various articles about DDD/CQRS.  Implemented Greg Young's SimpleCQRS sample in F#.
- [Vaughn Vernon](https://vaughnvernon.co) -  Vaughn Vernon了解软件开发的独特需求以及您在快节奏行业中提高工艺所面临的挑战.
- [Vladik Khononov](http://vladikk.com/) - 各种与DDD相关的文章.
- [Eventsourcing Publications](https://blog.eventsourcing.com) - 实际的事件采购.
- [Jef Claes](http://www.jefclaes.be/) - 关于领域驱动设计的优秀文章和演讲.
- [Udi Dahan](http://udidahan.com/articles/) - 来自NServiceBus的创建者.
- [Chris Patterson](https://lostechies.com/chrispatterson/) - 来自MassTransit分布式应用程序框架的创建者.
- [Aaron Stannard](http://www.aaronstannard.com/) - 来自CTO和Petabridge的联合创始人，Akka.NET Actor Model框架的开发人员.
- [Roger Johansson](https://rogeralsing.com/) - Mostly C#, DDD, and Akka.NET.
- [Konrad Garus](http://squirrel.pl/blog/)   -  Java，Clojure和JavaScript中的Ranting和编程.  在* cqrs *下标记的文章.
- [Oasis Digital](http://blog.oasisdigital.com/category/cqrs/) -  Oasis Digital的内容标记为* cqrs *.
- [Adaptech](http://adaptechsolutions.net/blog/)   -  Adaptech Solutions博客.  在Greg创造这个词之前，我们的创始人Adam Dymitruk与Greg Young讨论了CQRS的优点.  Adam和业务合作伙伴Robert Reppel是事件源微服务的主要实践者之一.
- [Lev Gorodinski](http://gorodinski.com/) -  2013年有几篇关于DDD的文章仍然相关.
- [Dino Esposito](https://software2cents.wordpress.com/)   - 软件架构师，培训师，书籍作者.  作者 [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/).
- [Dan Bergh Johnsson "Dear Junior"](http://dearjunior.blogspot.se/search/label/domain%20driven%20design)   - 域驱动设计与安全性相结合，并且通常具有敏捷性.  写作虚构的信件给年轻的程序员.
- [the native web](https://www.thenativeweb.io/blog/2017-10-25-09-46-ddd-and-co-part-1-whats-wrong-with-crud/) -  DDD＆Co.系列
- [Arkency](https://blog.arkency.com/) - 来自Ruby专家的各种DDD，CQRS，事件采购相关文章.
- [Svaťa Šimara](http://svatasimara.cz/) -  DDD系列 - 语言，领域，建模，基础设施，PHP实现
- [Martin Havlišta](https://xhafan.com/blog/) - DDD, CQRS, TDD blog posts with code samples in C# .NET  

## Sample Projects

### .NET (C#/F#)
- [CQRS-DDD Example](https://github.com/dcomartin/DDD-CQRS-ES-Example) - 使用GetEventStore，CommonDomain，NServiceBus，Entity Framework，SQL Server，SignalR的域驱动设计，CQRS和事件源示例.
- [Companion Code for Microsoft .NET Architecting Applications for the Enterprise](https://github.com/mastreeno/Merp) - An event based Micro ERP. 
- [ContosoUniversityCore](https://github.com/jbogard/ContosoUniversityCore) - 具有完整.NET Framework的ASP.NET Core上的ContosoUniversity.
- [DDDInventoryItemFSharp](https://github.com/eulerfx/DDDInventoryItemFSharp) - An idiomatic F# implementation of Domain-Driven Design
- [DDDSkeletonNet](https://github.com/andras-nemes/DDDSkeletonNet) (C#) - a .NET skeleton project to introduce the concepts of Domain Driven Design and loosely coupled layers.
- [EmailMaker](https://github.com/xhafan/emailmaker) - 电子邮件营销ASP.NET Core MVC和ASP.NET MVC演示应用程序演示 [CoreDdd](https://github.com/xhafan/coreddd) 用法
- [eShopOnContainersDDD](https://github.com/volak/eShopOnContainersDDD) -  eShop fullstack示例，包含目录，购物篮，结帐和订单有限的上下文
- [Equinox Project](https://github.com/EduardoPires/EquinoxProject) - 具有DDD，CQRS和事件源的完整ASP.NET Core 2.0应用程序
- [Example of Domain-Driven Design in F#](https://gist.github.com/swlaschin/2ad8627d0400b2ab70e9f3da08902c9d)   - 用于棋子游戏的域驱动设计示例.  有两个文件：带有一系列设计的临时文件和最终版本.
- [Fohjin](https://github.com/MarkNijhof/Fohjin) -  Mark Nijhof陪同的示例项目 [CQRS](https://leanpub.com/cqrs) 书.
- [FsUno](https://github.com/thinkbeforecoding/FsUno) - Event sourcing implementation sample in F#.
- [IDDD Samples in .NET](https://github.com/VaughnVernon/IDDD_Samples_NET) - These are the sample Bounded Contexts for C#.NET from the book "Implementing Domain-Driven Design" by Vaughn Vernon.
- [Lokad IDDD Sample](https://github.com/Lokad/lokad-iddd-sample) - This is a .NET Sample Project to accompany Event Sourcing materials from the book by Vaughn Vernon: Implementing Domain-Driven Design.
- [Microsoft Patterns and Practices: CQRS Journey Sample Code](https://github.com/mspnp/cqrs-journey) -  CQRS Journey的示例代码.
- [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) （.Net Core Preview 2） - 一个N层架构示例项目.
- [Reactive Trader Cloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) -  Adaptive Consulting的Reactive Trader Cloud.
- [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) - 使用Clean Architecture的原始SQL和DDD的.NET Core REST API CQRS实现.
- [Scritchy](https://github.com/ToJans/Scritchy) - 没有管道的CQRS， [video](http://www.youtube.com/watch?v=5DKTFZD3hu8).
- [Simple CQRS in F#](https://github.com/thinkbeforecoding/m-r) - Greg Young's SimpleCQRS in F#.
- [SimpleCQRS](https://github.com/gregoryyoung/m-r) -  Greg Young的“最简单的事情”CQRS与事件采购项目.
- [TodoMVC-DDD-CQRS-EventSourcing](https://github.com/volak/TodoMVC-DDD-CQRS-EventSourcing) - Implementation of basic Todo app via tastejs/todomvc in C#/Typescript with eventsourcing, cqrs, and domain driven design

### Haskell
- [Eventuria gsd](https://github.com/Eventuria/gsd) -  Haskell todo列出了DDD，CQRS和事件采购，FRP的反应式应用程序.

### JavaScript
- [wolkenkit Sample Applications](https://docs.wolkenkit.io/latest/media/sample-applications/wolkenkit-boards/) -  DDD示例应用程序的集合，例如TodoMVC，地理缓存应用程序，协作板等.

### JVM languages
- [Akka CQRS ES Demo](https://github.com/mdonkers/akka-cqrs-es-demo) - 在Scala-Akka中实施CQRS和事件采购模式的演示项目.
- [DDD Leaven](https://github.com/BottegaIT/ddd-leaven-v2) -  DDD-CQRS示例v2.0项目，可帮助您使用Spring，JPA和测试开始高级域建模.
- [Event Sourcing Example](https://github.com/Pragmatists/eventsourcing-java-example) - A simplified (in memory) example of Event Sourcing and CQRS implementation for Java code (modeled for banking domain use cases).
- [Event Sourcing and CQRS Examples](https://github.com/andreschaffer/event-sourcing-cqrs-examples) -  Java中的事件源和CQRS的实用应用，具有对常见相关问题的良好参考，例如事件排序和幂等性.
- [Event Sourcing and CQRS Sample](https://github.com/pilloPl/event-source-cqrs-sample) - 带有Command Query Responsibility Segregation的示例事件源应用程序
- [IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) - 这些是Vaughn Vernon出版的“实现领域驱动设计”一书中的有限上下文示例.
- [Kotlin DDD Sample](https://github.com/fabriciorissetto/kotlin-ddd-sample) - 用Kotlin编写的DDD / CQRS项目示例.

### PHP
- [DDD Wish List](https://github.com/franzose/symfony-ddd-wishlist) - 使用Symfony 3和Vue.js构建的PHP示例应用程序.
- [DDD Playground](https://github.com/jorge07/ddd-playground/) -  PHP中的示例实现.
- [Shop Cart in PHP](https://github.com/simara-svatopluk/cart)   - 示例项目，演示了购物车的简单外观.  域对象，Doctrine集成.，TDD，图层，单元测试


## Libraries and Frameworks
### .NET
- [Aggregates.NET](https://github.com/volak/Aggregates.NET) - 通过NServicebus和GetEventStore的.NET事件源域驱动设计模型.
- [AggregateSource](https://github.com/yreynhout/aggregateSource) - 使用聚合进行事件处理的轻量级基础架构.
- [Akka.NET](http://getakka.net/) -  Akka.NET是一个工具包和运行时，用于在.NET和Mono上构建高度并发，分布式和容错的事件驱动应用程序.
- [ASP.NET Boilerplate](http://aspnetboilerplate.com/) -  ASP.NET MVC，Web API和基于ASP.NET Core的应用程序框架，用于创建实现最佳实践的NLayered，Domain Driven Designed Web应用程序.
- [Cedar.CommandHandling](https://github.com/damianh/Cedar.CommandHandling)   - 通过HTTP处理命令的中间件;  通常用于CQRS应用程序.
- [Cirqus](https://github.com/d60/Cirqus) -  d60事件采购+ CQRS框架.
- [CoreDdd](https://github.com/xhafan/coreddd) - 一组开源.NET库，帮助DDD和CQRS，具有NHibernate持久性
- [CQRS on Azure](https://github.com/MerrionComputing/CQRSAzure) Windows Azure上的CQRS.
- [Dolittle](https://dolittle.com)   - 使用Dolittle构建更好的应用程序.  一个面向DDD的事件源微服务平台，具有开发人员的工作效率和简单的前端和中心.
- [EventFlow](https://github.com/eventflow/EventFlow) -  Async /等待.NET的第一个CQRS + ES和DDD框架http://geteventflow.net/.
- [Its.Cqrs](https://github.com/jonsequitur/Its.Cqrs) - 用于CQRS和事件采购的一组库，具有域驱动设计风格.
- [MassTransit](https://github.com/MassTransit/MassTransit) -  .NET分布式应用程序框架.
- [MessageRouter](https://github.com/QuickenLoans/MessageRouter) - 在此视频中描述： [The Beating Heart of CQRS, or Actor-Based Message Routing on the CLR](https://vimeo.com/171178586) by Paulmichael Blasucci at the New York F# .NET User Group.
- [NEventStore](https://github.com/NEventStore/NEventStore) - 使用事件源作为存储机制时，用于抽象不同存储实现的持久性库.
- [NServiceBus](https://github.com/Particular/NServiceBus) -  .NET的服务总线.
- [Projac](https://github.com/yreynhout/Projac) -  Projac是一组投影库，允许您编写针对各种后备存储的投影.
- [shriek-fx](https://github.com/ElderJames/shriek-fx) - 使用.NET Core 2.0开发的简单，优雅且有用的域驱动设计和CQRS框架.
- [SqlStreamStore](https://github.com/damianh/SqlStreamStore) - 面向基于SQL的实现的.NET Stream Store库.
- [Streamstone](https://github.com/yevhen/Streamstone) -  Azure表存储的事件存储.
- [Stringly.Typed](https://github.com/mission202/Stringly.Typed) - 更容易将字符串转换为.NET类型/从.NET类型转换.
- [Value](https://github.com/tpierrain/Value) - Help you to easily implement Value Types in your C# projects without making errors nor polluting your domain logic with boiler-plate code.
- [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0.

### Databases 
- [Event Store](https://geteventstore.com) - 使用JavaScript中的复杂事件处理的开源，功能数据库.
- [Eventsourcing](https://eventsourcing.com) - 业务事件捕获和查询框架.

### Elixir
- [Commanded](https://github.com/slashdotdash/commanded) - 用于CQRS / ES应用程序的命令处理中间件，用于聚合和流程管理器的纯功能数据结构，点对点消息路由以及Elixir（Erlang VM）中的更多内容 - 所有在Actor并发模型中.
- [Event Bus](https://github.com/otobus/event_bus) -  Elixir的可追踪，可扩展和极简主义事件总线实施，内置事件存储和基于ETS的事件观察器.
- [eventstore](https://github.com/slashdotdash/eventstore) - 使用PostgreSQL进行持久化的CQRS事件存储.

### JavaScript
- [cqrs.js](http://cqrs.js.org)   -  node.js中的CQRS实现.  包括 [node-eventstore](https://github.com/adrai/node-eventstore), [node-cqrs-domain](https://github.com/adrai/node-cqrs-domain), [node-eventdenormalizer](https://github.com/adrai/node-cqrs-eventdenormalizer), [node-cqrs-saga](https://github.com/adrai/node-cqrs-saga).
- [Node API Boilerplate](https://github.com/talyssonoc/node-api-boilerplate) - 用于DDD和Clean Architecture应用程序的NodeJS Web API样板.
- [wolkenkit](https://www.wolkenkit.io/) - 用于JavaScript和Node.js的CQRS，DDD和事件源框架.

### JVM
- [akka-ddd](https://github.com/pawelkaczor/akka-ddd) - 在基于CQRS / DDDD的方法之后，在Akka平台上构建应用程序的可重用工件.
- [Apache Isis](https://isis.apache.org/index.html) -  Apache Isis是一个用Java快速开发域驱动应用程序的框架.
- [Axon Framework](http://www.axonframework.org/) - 轴突框架专注于为希望基于CQRS原则创建Java应用程序的开发人员提供更轻松的生活.
- [JESA](https://github.com/yreynhout/JESA) -  Java的事件源聚合.
- [Lagom](https://www.lagomframework.com)   -  Lagom Framework是Java虚拟机的微服务框架，具有Java和Scala语言的API.  它包括基于事件源/ CQRS的持久性模块.
- [SeedStack's Business Framework](http://seedstack.org/docs/business/) - 一组构建块，使您能够根据域驱动设计（DDD）方法对业务逻辑进行编码.

### PHP
- [Broadway](https://github.com/broadway/broadway) - 百老汇是一个（PHP）项目，提供用于创建CQRS和事件源应用程序的基础架构和测试助手.

### Ruby
- [Rails Event Store](https://railseventstore.org)   -  Rails Event Store（RES）是一个用于发布，使用，存储和检索事件的库.  对于使用Rails应用程序的事件驱动架构，它是您最好的伴侣.

## Podcasts and Interviews

- [Deeper into DDD on DotNetRocks with David Real](http://dotnetrocks.com/?show=1151) -  2015年6月11日.
- [Thinking in DDD on DotNetRocks with Julie Lerman and Steve Smith](http://dotnetrocks.com/?show=1023) -  2014年8月19日.
- [Eric Evans on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=236) -  2007年5月10日.
- [Jimmy Nilsson on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=191) -  2006年8月29日.
- [Being the Worst](http://www.beingtheworst.com) -  2012年至2016年.
- [Software Engineering Radio Episode 225: Eric Evans on Domain-Driven Design at 10 Years](http://www.se-radio.net/2015/05/se-radio-episode-226-eric-evans-on-domain-driven-design-at-10-years/) -  2015年5月13日.
- [Software Engineering Radio Episode 218: Udi Dahan on CQRS (Command Query Responsibility Segregation)](http://www.se-radio.net/2015/01/episode-218-udi-dahan-on-cqrs-command-query-responsibility-segregation/) -  2015年1月30日.

## Conferences

- [Domain-Driven Design Europe - Netherlands](http://www.dddeurope.com)
- [Explore DDD - USA](http://exploreddd.com/)
- [Kandddinsky - Germany](http://kandddinsky.com/)

## User Groups

- [Austria](https://www.meetup.com/ddd-vienna/)
- [Barcelona](https://www.meetup.com/dddbcn/)
- [Belfast](https://dddbelfast.com/)
- [Belgium](http://www.meetup.com/dddbelgium/)
- [Berlin](http://www.meetup.com/Domain-Driven-Design-Berlin/)
- [Cologne/Bonn](https://www.meetup.com/Domain-Driven-Design-Koln-Bonn/)
- [Cracow](http://www.meetup.com/ddd-krk/)
- [Denver](https://www.meetup.com/ddd-denver/)
- [Greece](https://www.meetup.com/dddgreece/)
- [Hamburg](https://www.meetup.com/DDD-HH-Domain-driven-Design-Hamburg/)
- [London](http://www.meetup.com/dddlondon/)
- [Munich](https://www.meetup.com/Microservices-Meetup-Munich/)
- [Nederland](http://www.meetup.com/Domain-Driven-Design-Nederland/)
- [Norway](https://www.meetup.com/dddnorway/)
- [Phoenix](https://www.meetup.com/DDD-Phoenix)
- [Warsaw](https://www.meetup.com/DDD-WAW)
- [Wroclaw](http://www.meetup.com/DDD-WRO)

## Tools

- [Domain Storytelling](http://www.domainstorytelling.org/)   - 一种知识运算技术，可帮助相关人员熟悉域并制定出表达共同理解的模型.  可用作 [print-out template](http://www.domainstorytelling.org/images/DST_Whiteboard-Kit.pdf)，以及开源在线工具， [WPS Modeler](https://www.wps.de/modeler) ([source](https://github.com/wps/domain-story-modeler)).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Nick Chamberlain](https://buildplease.com) 已放弃对此作品的所有版权及相关或相邻权利.
