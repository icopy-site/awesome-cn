<div class="github-widget" data-repo="heynickc/awesome-ddd"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Domain-Driven Design [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精选的领域驱动设计（DDD），命令查询责任隔离（CQRS），事件源和事件风暴资源列表.

**检查我 [blog](https://buildplease.com) 和 [weekly DDD newsletter](https://buildplease.com/pages/dddweekly/) 或打个招呼 [Twitter](https://twitter.com/heynickc)!**

**[Domain-Driven Design (DDD)](https://en.m.wikipedia.org/wiki/Domain-driven_design) **是通过将实现与不断发展的模型联系起来的，用于满足复杂需求的软件开发的方法. 域驱动设计的前提如下：

-将项目的主要重点放在核心领域和领域逻辑上
-根据领域模型建立复杂的设计
-在技术专家和领域专家之间发起创新合作，以迭代方式完善解决特定领域问题的概念模型

这个词是埃里克·埃文斯（Eric Evans）在同名书中创造的.

**[Command Query Responsibility Segregation (CQRS)](http://codebetter.com/gregyoung/2010/02/16/cqrs-task-based-uis-event-sourcing-agh/) **只是在以前只有一个的两个对象的创建. 根据方法是命令还是查询来进行分隔（Meyer在“命令和查询分隔”中使用的定义相同，命令是使状态发生变化的任何方法，而查询是返回值的任何方法）.

**[Event Sourcing](http://www.martinfowler.com/eaaDev/EventSourcing.html)**事件源的基本思想是确保在事件对象中捕获对应用程序状态的每次更改，并且这些事件对象本身按照与应用程序状态本身相同的生命周期应用的顺序存储.

**[Event Storming](https://ziobrando.blogspot.com/2013/11/introducing-event-storming.html)**是一种研讨会形式，用于快速探索复杂的业务领域.


- [Awesome Domain-Driven Design](https://github.com/heynickc/awesome-ddd/)

## Books

- [Applying Domain Driven Design with CQRS and Event Sourcing](https://buildplease.com/pages/now-what/) -使用EventStorming和其他建模技术为虚构的业务领域构建基于CQRS和基于事件源的原型的演练.
- [CQRS](https://leanpub.com/cqrs)  -Mark Nijhof从Greg Young学习DDD和CQRS的经验中获得的笔记. 本书附带了一个广泛的示例项目.
- [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215)  -创造了领域驱动设计一词的经典书籍. 也称为“蓝皮书”.
- [Domain-Driven Design Distilled](https://www.amazon.com/Domain-Driven-Design-Distilled-Vaughn-Vernon/dp/0134434420) -阅读前非常好的入门书 [Implementing Domain-Driven Design](https://vaughnvernon.co/?page_id=168#iddd) 要么 [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215).
- [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) -用PHP编写的真实示例展示了DDD建筑风格，战术设计和有限的上下文集成.
- [Domain-Driven Rails](https://blog.arkency.com/domain-driven-rails/) -域驱动的Rails描述了11种技术（从绑定上下文到事件源），您可以在新的和旧的Rails应用程序中单独使用这些技术，或者将它们一起使用，以实现更好的体系结构.
- [Domain Modeling Made Functional](https://pragprog.com/book/swdddf/domain-modeling-made-functional) - Tackle Software Complexity with Domain-Driven Design and F#.
- [Domain Specific Languages](http://martinfowler.com/books/dsl.html) -与DDD切线连接，描述了无处不在的语言的重要性，并与领域专家一起工作，以及许多技术细节.
- [Event Sourcing and CQRS with .NET Core and SQL Server](https://buildplease.com/products/fpc-v2/) -在生产环境中使用ASP.NET Core和SQL Server将域驱动设计与事件源和CQRS结合使用的演练.
- [Hands-On Domain-Driven Design with .NET Core](https://www.amazon.com/Hands-Domain-Driven-Design-NET-dp-1788834097/dp/1788834097) -通过将DDD原理付诸实践，Alexey Zimarev解决了软件核心的复杂性.
- [Implementing Domain-Driven Design](https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)  -也是一本规范书籍，介绍了自上而下的理解域驱动设计的方法. 也称为“红皮书”.
- [Implementing DDD, CQRS and Event Sourcing](https://leanpub.com/implementing-ddd-cqrs-and-event-sourcing)  -了解如何实施DDD，CQRS和事件源. 理解该理论并将其与JavaScript和Node.js一起付诸实践.
- [Introducing Event Storming: An act of Deliberate Collective Learning](https://leanpub.com/introducing_eventstorming) -直接来自发明家的有关EventStorming的最深入的教程和说明.
- [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/) -务实地应用软件架构师的核心实践摘要.
- [Patterns, Principles, and Practices of Domain-Driven Design (1st Edition)](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709) - Methods for managing complex software construction following the practices, principles and patterns of Domain-Driven Design with code examples in C#.
- [Secure by Design](https://www.manning.com/books/secure-by-design?a_aid=danbjson&a_bid=0b3fac80) -显示如何使用域驱动设计来避免安全漏洞.
- [Specification by Example](https://www.manning.com/books/specification-by-example)  -本书摘录了世界各地领先团队的经验，以有效的方式指定，测试和交付了简短，迭代的交付周期的软件. 本书中的案例研究范围从小型Web初创公司到大型金融机构，涉及XP，Scrum和看板等许多流程.
- [Versioning in an Event Sourced System](https://leanpub.com/esversioning)  -在对事件源系统进行版本控制时遇到麻烦吗？ 只是第一次进入新的事件源系统？ 这本书是有关如何长时间处理版本控制的权威指南.
- [What is Domain-Driven Design?](https://learning.oreilly.com/library/view/what-is-domain-driven/9781492057802/) -快速阅读，了解领域驱动设计的核心模式和原理，以及在棕地项目中应用DDD的策略.
- [Writing Great Specifications](https://www.manning.com/books/writing-great-specifications) -编写出色的规范是一个示例丰富的教程，该教程教您如何编写编写良好的Gherkin规范文档，以利用“规范得益于示例”的优势.

## Free eBooks

- [The Anatomy of Domain-Driven Design - The Infographic](https://leanpub.com/theanatomyofdomain-drivendesign) -有关域驱动设计的解剖图.
- [Architecting Modern Web Applications with ASP.NET Core and Microsoft Azure](https://dotnet.microsoft.com/download/thank-you/aspnet-ebook) -提供有关使用DDD，ASP.NET Core和Azure构建整体Web应用程序的端到端指南. [eShopOnWeb sample](https://github.com/dotnet-architecture/eShopOnWeb)
- [Architecture Patterns with Python](https://www.cosmicpython.com/book/preface.html) -有关用于管理复杂性的Pythonic应用程序体系结构模式的书.
- [CQRS Journey](https://msdn.microsoft.com/en-us/library/jj554200.aspx) -探索CQRS和事件来源.
- [Domain-Driven Design: The First 15 Years](https://dddeurope.com/15years)  -为了庆祝这一周年，我们邀请了软件设计界的杰出作者来撰写新旧论文. 在Martin Fowler，James Coplien，Rebecca Wirfs-Brock，Mel Conway等人的贡献下.
- [DDD Reference](http://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) -DDD的模式和定义的摘要.
- [Domain Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly) -“快速域驱动设计”是一个简短，易读的摘要，并介绍了DDD的基础知识.
- [Effective Aggregate Design](http://dddcommunity.org/library/vernon_2011/) -在这个由三部分组成的系列文章中，Vaughn Vernon讲述了一些常见的设计陷阱，讨论了各种聚合建模选择的优缺点，并提供了经验法则来指导聚合建模.
- [Getting Started with DDD when Surrounded by Legacy Systems](http://domainlanguage.com/wp-content/uploads/2016/04/GettingStartedWithDDDWhenSurroundedByLegacySystemsV1.pdf) -描述了在对遗留系统有重大承诺时开始使用DDD的三种策略.
- [Living Documentation by Design, with Domain-Driven Design](https://leanpub.com/livingdocumentation) -了解生活文档如何在项目的各个方面提供帮助，从业务目标到业务领域的知识，体系结构和设计，流程和部署，即使您讨厌编写文档.
- [.NET Microservices: Architecture for Containerized .NET Applications](https://dotnet.microsoft.com/download/thank-you/microservices-architecture-ebook) -介绍如何开发基于微服务的应用程序并使用容器对其进行管理. [eShopOnContainers sample](https://github.com/dotnet-architecture/eShopOnContainers)
- [The Semantic JavaScript Backend for Event-Driven Development](https://docs.wolkenkit.io/1.1.0/downloads/brochure/) -一本长达68页的免费电子书，内容涉及DDD，CQRS和事件源以及它们如何相互配合.
- [DDD Magazine from Xebia #1](https://pages.xebia.com/domain-driven-design-magazine-xebia) -该杂志根据个人，业务和客户的经验提供了富有远见和实用的见解，可为您的DDD之旅提供支持
- [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/)  -视觉协作工具是一本针对团队构建软件的书. 它描述了有助于我们日常工作的工具，还介绍了不同从业人员的实地故事.

## Training Courses

- [DDD Workshops across Europe and Online](https://training.dddeurope.com/) -Eric Evans，Alberto Brandolini，Mathias Verraes，Rebecca Wirfs-Brock，Nick Tune等举办的公共研讨会.
- [Domain Language eLearning](http://elearn.domainlanguage.com/) -通过与Eric Evans一起使用我们的视频课程，Eric Evans是有关域驱动设计（DDD）的原著的作者，向您介绍了不断发展的实用模型的技术，这些模型可以改善您的软件-而不仅仅是文档.
- [Greg Young's CQRS Class](http://subscriptions.viddler.com/GregYoung/) -这些视频包括Greg Young的DDD，CQRS和Event Sourcing类的全部内容.
- [Distilling Domain-Driven Design](https://forcomprehension.com/) -Vaughn Vernon的在线培训课程.
- [Advanced Distributed Systems Design](https://learn-particular.thinkific.com/courses/adsd-online)  -来自Udi Dahan的在线培训课程. 可以找到乌迪的现场训练时间表 [here](http://udidahan.com/training/).
- [Nomad PHP](https://nomadphp.com/product/introduction-event-sourcing-cqrs/) -事件源和CQRS简介.
- [Event Sourcery](https://eventsourcery.com/) -DDD，CQRS和事件源简介.
- [Mixter](https://github.com/DevLyon/mixter) -CQRS和事件源Koans.
- [Pluralsight](https://pluralsight.com)
	 - [Domain-Driven Design Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) -通过演示客户交互和复杂的演示应用程序以及Eric Evans的建议，来学习域驱动设计（DDD）的基础知识.
	 - [Domain-Driven Design in Practice](https://www.pluralsight.com/courses/domain-driven-design-in-practice) -在实践中应用域驱动设计原则的描述性深入演练.
	 - [Modern Software Architecture: Domain Models, CQRS, and Event Sourcing](https://www.pluralsight.com/courses/modern-software-architecture-domain-models-cqrs-event-sourcing)  -本课程涵盖DDD分析模式，有助于发现业务领域的顶级体系结构. 架构师和开发人员将找到实现模式的详细信息，例如域模型，CQRS和事件源.
- [Rails + Domain Driven Design Workshop](https://blog.arkency.com/ddd-training/) -DDD简介，Ruby / Rails开发人员的CQRS和事件源基础.
- [Reactive Architecture: Domain Driven Design](https://cognitiveclass.ai/courses/reactive-architecture-ddd/)  -使用DDD将问题域分解为可管理的部分. 了解这些部分如何成为反应式微服务和反应式架构的基础. 免费，在线，自定进度. 完成后提供证书.
- [Reactive Architecture: CQRS and Event Sourcing](https://cognitiveclass.ai/courses/reactive-architecture-cqrs/)  -本课程将讨论我们使用CQRS / ES的原因，它为我们提供的好处以及使用的成本. 我们将看到CQRS / ES如何影响应用程序的可伸缩性，一致性和可用性.
- [DDD Workshop by Xebia](https://xebia.com/academy/en/search?query=Domain-driven%20design) -从基础到专业级别的公共和内部域驱动设计研讨会.

## Video Collections

- [DDD Europe](https://dddeurope.com/videos) -在DDD Europe进行的演讲记录.
- [SkillsCasts by SkillsMatter](https://skillsmatter.com/skillscasts) -搜索DDD会返回Greg Young，Alberto Brandolini和Dan North等进行的各种演讲.
- [Alberto Brandolini: Event Storming](https://www.youtube.com/watch?v=veTVAN0oEkQ&list=PLve553MhJLs4YkEnHmOjWJv0B-6WY0-JI) -Alberto Brandolini在YouTube上发表的有关事件风暴的演讲集.
- [Greg Young](https://www.youtube.com/watch?v=JHGkaShoyNs&list=PL5XpN_ZVafKLePdxruDfdfi-IiZtXz-k9) -格雷格·杨（Greg Young）的YouTube演讲集锦.
- [Explore DDD videos](https://www.youtube.com/channel/UCcpKGt6MVvz7dISXLlMGmag) -探索DDD会议上的演讲记录.
- [KanDDDinsky](https://www.youtube.com/channel/UCJCpnslPdb_Dl8DKokXC3HA) -在KanDDDinsky上发表的YouTube演讲集.
- [Virtual Domain-driven design](https://www.youtube.com/channel/UCob_jOzzpxBp-di-x0vLlwA) -从虚拟域驱动的设计中录制的metups会话的youtube集合

## Community Resources

- [DDD/CQRS Google Group](https://groups.google.com/forum/?utm_source=digest&utm_medium=email#!forum/dddcqrs) -活跃的邮件列表和出色的资源，可以提出问题并了解有关DDD / CQRS的详细信息.
- [Domain Driven Design Yahoo Group](https://groups.yahoo.com/neo/groups/domaindrivendesign/conversations/messages)  -该小组讨论的是领域驱动的设计软件风格，以及Eric Evans的著作《领域驱动的设计：商业软件核心中的复杂性》. 在这里欢迎对本书内容进行问题和讨论，也可以分享使用DDD的经验以及有关该主题的一般讨论.
- [DDDinPHP Google Group](https://groups.google.com/forum/#!forum/dddinphp) -在PHP的背景下讨论域驱动设计，CQRS，事件源，模型风暴，六角体系结构，分布式系统，反应式的地方.
- [DDD in Ruby subreddit](https://www.reddit.com/r/ddd_ruby/) -对于对域驱动设计感兴趣的Ruby开发人员的子目录.
- [EventStormers Google+ Community](https://plus.google.com/u/0/communities/113258571348605620818) -一个对EventStorming和相关主题感兴趣的所有人的公开讨论组.
- [DDD/CQRS/ES Slack](https://github.com/ddd-cqrs-es/slack-community)  -闲聊的团队，适合那些想要谈论域驱动设计，CQRS，事件源以及有时是随机事物的人. 主要渠道是与语言和框架无关的.
- [Domain StoryTelling Slack](https://domainstorytelling.slack.com)  -有关Domain StoryTelling的小组. 目前仅受邀，但您可以询问 [@hofstef](https://twitter.com/hofstef) 邀请. 主页位于 [domainstorytelling.org](http://domainstorytelling.org/).
- [Software Engineering Stack Exchange](http://softwareengineering.stackexchange.com/questions/tagged/domain-driven-design) -标记为“域驱动设计”的软件工程堆栈交换问题.
- [Code Review Stack Exchange](http://codereview.stackexchange.com/questions/tagged/ddd) -代码复习堆栈交换标记为“域驱动设计”的问题.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/domain-driven-design) -标记为“域驱动设计”的堆栈溢出问题.
- [Advanced Topics in Event Sourcing / CQRS / DDD](https://github.com/sebastianharko/adv-es-cqrs-ddd) -由@编译和维护的事件来源/ CQRS / DDD列表中的高级主题[sebastianharko](https://github.com/sebastianharko).
- [Quora](https://www.quora.com/topic/Domain-Driven-Design-DDD) -标有“域驱动设计”的问题.
- [wolkenkit Slack](http://slackin.wolkenkit.io/) -一个在DDD，事件源，CQRS和wolkenkit上的Slack团队.
- [Awesome Event Storming](https://github.com/mariuszgil/awesome-eventstorming) - awesome list that focuses only on Event Storming.
- [Virtual Domain-driven design community](https://virtualddd.com) -小组讨论，在线协作和资源共享的在线聚会.
- [Domain-driven design heuristics](https://www.dddheuristics.com/) -域驱动的设计启发式网站是一个社区驱动的站点，用于记录和讨论有关设计启发式内容.

## Blogs

- [Nick Chamberlain](https://buildplease.com) -为.NET开发人员提供有用的开发和设计建议.
- [Ardalis.com](https://ardalis.com/blog)  -史蒂夫·史密斯.  Pluralsight作者和作者 [DDD Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) 当然和微软 [eShopOnWeb sample app](https://github.com/dotnet-architecture/eShopOnWeb).
- [DDD Weekly](http://dddweekly.com) -与DDD / CQRS / ES相关的每周精选链接.
- [Daniel Whittaker](http://danielwhittaker.me)  -想了解CQRS和事件来源吗？ 该博客中包含分步指南，可帮助您起步.
- [Cyrille Martraire](http://cyrille.martraire.com) -在沉迷于金融的同时仍然热衷于编程，我自然是Eric Evans的领域驱动设计以及TDD，BDD和敏捷/ XP实践的忠实拥护者.
- [Jimmy Bogard](https://lostechies.com/jimmybogard/) -我专注于DDD，分布式系统以及其他以缩写词为中心的设计/体系结构/方法论.
- [CodeBetter](http://codebetter.com) -CodeBetter.Com的存在是为了帮助在软件开发社区中培养对更好的实践，高级工具，行之有效的方法和技术的认识.
- [Greg Young](https://goodenoughsoftware.net/) -足够好的软件从定义上讲是足够的.
- [InfoQ Blog](https://www.infoq.com/domaindrivendesign/) -InfoQ上的域驱动设计内容.
- [Dan North](https://dannorth.net/blog/)  -行为驱动设计的发明者. 有关事件风暴的博客和讨论.
- [Mike Mogosanu](http://blog.sapiensworks.com)  -可维护的代码是业务优势. 域地图的创建者：域建模工具-简单而强大的域驱动设计.
- [Christian Posta](http://blog.christianposta.com) -Red Hat的首席中间件架构师，开源爱好者，Apache，云，集成，Kubernetes，Docker，OpenShift，Fabric8的提交者.
- [Vladimir Khorikov](http://enterprisecraftsmanship.com)  -Pluralsight作者. 有关软件开发原理和最佳实践的博客.
- [TechBeacon](http://techbeacon.com/) -TechBeacon上的文章标记了“域驱动设计”.
- [Derek Comartin](http://codeopinion.com) -“域驱动设计”类别下的文章.
- [Alberto Brandolini](https://ziobrando.blogspot.it)  -事件风暴的发明者. 断言问题无法用产生问题的相同思路来解决，Alberto经常以建筑师，导师，教练，经理或开发人员的观点来交换观点.
- [Jérémie Chassaing](http://thinkbeforecoding.com/) - Various articles about DDD/CQRS.  Implemented Greg Young's SimpleCQRS sample in F#.
- [Vaughn Vernon](https://vaughnvernon.co) -沃恩·弗农（Vaughn Vernon）了解软件开发的独特需求以及在快速发展的行业中提高自己的技能时所面临的挑战.
- [Vladik Khononov](http://vladikk.com/) -各种与DDD相关的文章.
- [Eventsourcing Publications](https://blog.eventsourcing.com) -实用的事件源.
- [Jef Claes](http://www.jefclaes.be/) -关于域驱动设计的优秀文章和讲座.
- [Udi Dahan](http://udidahan.com/articles/) -来自NServiceBus的创建者.
- [Chris Patterson](https://lostechies.com/chrispatterson/) -来自MassTransit分布式应用程序框架的创建者.
- [Aaron Stannard](http://www.aaronstannard.com/) -来自Petabridge的CTO和联合创始人，Akka.NET Actor Model框架的开发人员.
- [Roger Johansson](https://rogeralsing.com/) - Mostly C#, DDD, and Akka.NET.
- [Konrad Garus](http://squirrel.pl/blog/)  -Java，Clojure和JavaScript中的编程和编程. 在* cqrs *下标记的文章.
- [Oasis Digital](http://blog.oasisdigital.com/category/cqrs/) -由Oasis Digital在* cqrs *下标记的内容.
- [Adaptech](http://adaptechsolutions.net/blog/)  -Adaptech Solutions博客. 我们的创始人Adam Dymitruk在Greg创造这个词之前就与Greg Young辩论了CQRS的优点.  Adam和业务合作伙伴Robert Reppel都是事件源微服务的领先实践者.
- [Lev Gorodinski](http://gorodinski.com/) -2013年以来有关DDD的几篇文章仍然相关.
- [Dino Esposito](https://software2cents.wordpress.com/)  -软件架构师，培训师，书籍作者. 的作者 [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/).
- [Dan Bergh Johnsson "Dear Junior"](http://dearjunior.blogspot.se/search/label/domain%20driven%20design)  -域驱动设计结合了安全性和敏捷性. 写给年轻程序员的虚构信.
- [the native web](https://www.thenativeweb.io/blog/2017-10-25-09-46-ddd-and-co-part-1-whats-wrong-with-crud/) -DDD＆Co.系列
- [Arkency](https://blog.arkency.com/) -来自Ruby专家的各种DDD，CQRS，事件源相关文章.
- [Svaťa Šimara](http://svatasimara.cz/) -DDD系列-语言，领域，建模，基础结构，PHP实现
- [Martin Havlišta](https://xhafan.com/blog/) - DDD, CQRS, TDD blog posts with code samples in C# .NET
- [Khalil Stemmler](https://khalilstemmler.com/articles/categories/domain-driven-design) -DDD系列简介，并讨论如何使用TypeScript实现DDD
- [Kenny Baas-Schwegler](https://baasie.com/) -DDD，BDD，社交技术，EventStorming和连续交付博客.
- [João Rosa](https://joaorosa.io)  -有关域驱动设计，视觉协作，领导力和组织设计的个人博客. 介于两者之间. 策展人 [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/) 和主持人 [Software Crafts Podcast](https://www.softwarecraftspodcast.com/)

## Sample Projects

### .NET (C#/F#)
- [Better code with DDD building blocks](https://github.com/asc-lab/better-code-with-ddd)  -解决方案展示了DDD战术模式的使用，以实现更好的代码可读性和表达性. 将DDD模式与无处不在的语言一起使用可以缩小专家和团队使用的语言以及代码中使用的语言之间的差距.
- [CQRS-DDD Example](https://github.com/dcomartin/DDD-CQRS-ES-Example) -使用GetEventStore，CommonDomain，NServiceBus，实体框架，SQL Server，SignalR的域驱动设计，CQRS和事件源示例.
- [Companion Code for Microsoft .NET Architecting Applications for the Enterprise](https://github.com/mastreeno/Merp) -基于事件的Micro ERP.
- [ContosoUniversityCore](https://github.com/jbogard/ContosoUniversityCore) -带有完整.NET Framework的ASP.NET Core上的ContosoUniversity.
- [DDD-starter-dotnet](https://github.com/itlibrium/DDD-starter-dotnet)  -示例实施和各种构建DDD应用程序的方法的比较. 用作快速启动DDD .net项目的基准.
- [DDDInventoryItemFSharp](https://github.com/eulerfx/DDDInventoryItemFSharp) - An idiomatic F# implementation of Domain-Driven Design
- [DDDSkeletonNet](https://github.com/andras-nemes/DDDSkeletonNet) (C#) - a .NET skeleton project to introduce the concepts of Domain Driven Design and loosely coupled layers.
- [DotNet CQRS Intro](https://github.com/asc-lab/dotnet-cqrs-intro) -具有事件来源的实现CQRS的示例-演化方法（无CQRS，具有相同模型的单独模型和命令，具有单独模型的单独模型和命令，单独的存储引擎，事件源）.
- [EISK](https://github.com/eisk) -具有简单用例的.NET CLI和VS模板，可在具有架构最佳实践（DDD，洋葱架构等）的.net核心之上构建可扩展的应用程序.
- [EmailMaker](https://github.com/xhafan/emailmaker) -电子邮件营销ASP.NET Core MVC和ASP.NET MVC演示应用程序演示 [CoreDdd](https://github.com/xhafan/coreddd) 用法
- [Equinox Project](https://github.com/EduardoPires/EquinoxProject) -具有干净架构，DDD，CQRS和事件源概念的完整ASP.NET Core 3.1应用程序
- [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) -Microsoft的完整ASP.NET Core 3.1参考应用程序，显示了整体部署架构
- [eShopOnContainersDDD](https://github.com/volak/eShopOnContainersDDD) -具有目录，购物篮，结帐和订单有界上下文的eShop全栈示例
- [Example of Domain-Driven Design in F#](https://gist.github.com/swlaschin/2ad8627d0400b2ab70e9f3da08902c9d)  -跳棋游戏的域驱动设计示例. 有两个文件：具有一系列设计的暂存文件和最终版本.
- [Event Sourcing .NET](https://github.com/oskardudycz/EventSourcing.NetCore)  -有关.NET中事件源和CQRS的示例和资源. 还包含有关如何构建自己的事件存储的自定进度工具包
- [EventFlow.Example](https://github.com/OKTAYKIR/EventFlow.Example) -DDD，CQRS和事件来源示例，其中包含以下技术堆栈： [EventFlow](https://github.com/eventflow/EventFlow), [EventStore](https://eventstore.com), [RabbitMQ](https://www.rabbitmq.com), [MongoDB](https://www.mongodb.com), [PostgreSQL](https://www.postgresql.org), [Docker](https://www.docker.com)
- [Fohjin](https://github.com/MarkNijhof/Fohjin) -马克·尼霍夫（Mark Nijhof）随附的示例项目 [CQRS](https://leanpub.com/cqrs) 书.
- [FsUno](https://github.com/thinkbeforecoding/FsUno) - Event sourcing implementation sample in F#.
- [IDDD Samples in .NET](https://github.com/VaughnVernon/IDDD_Samples_NET) - These are the sample Bounded Contexts for C#.NET from the book "Implementing Domain-Driven Design" by Vaughn Vernon.
- [Microsoft Patterns and Practices: CQRS Journey Sample Code](https://github.com/mspnp/cqrs-journey) -CQRS Journey的示例代码.
- [Modular Monolith](https://github.com/kgrzybek/modular-monolith-with-ddd) -具有域驱动设计方法的完整模块化Monolith .NET应用程序.
- [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) （.Net Core Preview 2）-N层体系结构示例项目.
- [Photostock CQRS-DDD Example](https://github.com/mr0zek/Photostock)
- [Reactive Trader Cloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) -自适应咨询公司的反应性交易者云.
- [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) -使用原始架构的.NET Core REST API CQRS实现，带有原始SQL和DDD.
- [Scritchy](https://github.com/ToJans/Scritchy) -没有水暖的CQRS， [video](http://www.youtube.com/watch?v=5DKTFZD3hu8).
- [Simple CQRS in F#](https://github.com/thinkbeforecoding/m-r) - Greg Young's SimpleCQRS in F#.
- [SimpleCQRS](https://github.com/gregoryyoung/m-r) -格雷格·扬（Greg Young）的“最简单的事物” CQRS，带有事件来源项目.
- [TodoMVC-DDD-CQRS-EventSourcing](https://github.com/volak/TodoMVC-DDD-CQRS-EventSourcing) - Implementation of basic Todo app via tastejs/todomvc in C#/Typescript with eventsourcing, cqrs, and domain driven design

### Haskell
- [Eventuria gsd](https://github.com/Eventuria/gsd) -Haskell待办事项列出了具有DDD，CQRS和事件源，FRP的响应式应用程序.

### JavaScript
- [wolkenkit Sample Applications](https://docs.wolkenkit.io/latest/media/sample-applications/wolkenkit-boards/) -DDD示例应用程序的集合，例如TodoMVC，地理缓存应用程序，协作板等.

### JVM languages
- [Akka CQRS ES Demo](https://github.com/mdonkers/akka-cqrs-es-demo) -演示项目，用于在Scala-Akka中实现CQRS和事件源模式.
- [DDD By Examples - Library](https://github.com/ddd-by-examples/library)  -由实际业务需求驱动的图书馆样本项目. 借助DDD，BDD，EventStorming，示例映射，CQRS等实现的模块化整体.
- [DDD Leaven](https://github.com/BottegaIT/ddd-leaven-v2) -DDD-CQRS示例v2.0项目，可帮助您使用Spring，JPA和测试开始高级域建模.
- [DDD Workshop - Project Manager](https://github.com/mkopylec/project-manager)  -“自己动手” DDD研讨会和一个示例DDD应用程序同时进行. 基于项目管理域.
- [Event Sourcing Example](https://github.com/Pragmatists/eventsourcing-java-example) -Java代码的事件源和CQRS实现的简化（内存中）示例（针对银行领域用例建模）.
- [Event Sourcing and CQRS Examples](https://github.com/andreschaffer/event-sourcing-cqrs-examples) -Java中的事件源和CQRS的实用应用程序，并为常见的相关问题（例如事件排序和幂等）提供了很好的参考.
- [Event Sourcing and CQRS Sample](https://github.com/pilloPl/event-source-cqrs-sample) - Sample event sourced application with Command Query Responsibility Segregation
- [IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) -这些是沃恩·弗农（Vaughn Vernon）的“实施域驱动的设计”一书中的示例绑定上下文.
- [Java CQRS Intro](https://github.com/asc-lab/java-cqrs-intro) -具有事件来源的实现CQRS的示例-演化方法（无CQRS，具有相同模型的单独模型和命令，具有单独模型的单独模型和命令，单独的存储引擎，事件源）.
- [Kotlin DDD Sample](https://github.com/fabriciorissetto/kotlin-ddd-sample) -用Kotlin编写的DDD / CQRS示例项目.
- [EventStormingWorkshop - Designing Cloud Native Microservices On AWS](https://github.com/humank/EventStormingWorkShop/) -通过EventStorming研讨会并在Java中实现DDD战术设计模式的具体示例，应用AWS云本地服务来构建基于业务事件的Coffeeshop场景.
- [DDDSample](https://github.com/citerus/dddsample-core) -使用Spring Boot的示例DDD项目（最初托管在http://dddsample.sourceforge.net/中）

### PHP
- [DDD CQRS Todo Sample](https://github.com/ferrius/ddd-cqrs-example) -使用PHP 7和Symfony 5构建的DDD CQRS ADR六角形体系结构实现.
- [DDD Wish List](https://github.com/franzose/symfony-ddd-wishlist) -使用Symfony 3和Vue.js构建的PHP示例应用程序.
- [DDD Playground](https://github.com/jorge07/ddd-playground/) -PHP中的示例实现.
- [Eric Evans DDD Cargo Sample](https://github.com/codeliner/php-ddd-cargo-sample) -Eric Evans DDD书中使用的货物样本的PHP 7版本
- [Shop Cart in PHP](https://github.com/simara-svatopluk/cart)  -示例项目，演示简单的购物车外观. 领域对象，文档集成，TDD，层，单元测试


## Libraries and Frameworks
### .NET
- [Aggregates.NET](https://github.com/volak/Aggregates.NET) -通过NServicebus和GetEventStore的.NET事件源域驱动的设计模型.
- [AggregateSource](https://github.com/yreynhout/aggregateSource) -轻量级基础架构，用于使用聚合进行事件外包.
- [Akka.NET](http://getakka.net/) -Akka.NET是一个工具包和运行时，用于在.NET＆Mono上构建高度并发，分布式和容错的事件驱动应用程序.
- [ABP](https://abp.io) -ASP.NET Boilerplate的继任者-基于ASP.NET Core的应用程序框架，用于创建NLayered，域驱动设计的Web应用程序，具有以微服务为中心的模块化体系结构
- [ASP.NET Boilerplate](http://aspnetboilerplate.com/) - ASP.NET MVC, Web API and ASP.NET Core based application framework to create NLayered, Domain Driven Designed web Applications implementing best practices.
- [ByValue](https://github.com/sm-g/ByValue) -该库有助于创建具有正确实现的相等行为的ValueObjects（即使具有集合属性）.
- [Cedar.CommandHandling](https://github.com/damianh/Cedar.CommandHandling)  -通过HTTP处理命令的中间件； 通常在CQRS应用程序中使用.
- [Cirqus](https://github.com/d60/Cirqus) -d60事件源+ CQRS框架.
- [CoreDdd](https://github.com/xhafan/coreddd) -一组有助于DDD和CQRS，具有NHibernate持久性的开源.NET库
- [CQRS on Azure](https://github.com/MerrionComputing/CQRSAzure) Windows Azure上的CQRS.
- [Dolittle](https://dolittle.com)  -使用Dolittle构建更好的应用程序. 一个基于事件的，基于DDD的微服务平台，具有开发人员的生产力以及简洁的前端和中心.
- [Edument CQRS and Intentful BDD Testing Starter Kit](https://www.cqrs.nu/) -有关如何构建CQRS / ES应用程序的库和教程，包括BDD样式测试框架.
- [EventFlow](https://github.com/eventflow/EventFlow) -异步/等待用于.NET http://geteventflow.net/的第一个CQRS + ES和DDD框架.
- [Core.EventStore](https://github.com/younos1986/Core.EventStore)  -促进CommandService和QueryService之间的通信的库. 这个想法是，当commandService中发生任何事件时，都应将其保留在MongoDb中的QueryService中.
- [Its.Cqrs](https://github.com/jonsequitur/Its.Cqrs) -一组具有域驱动设计风格的CQRS和事件源库.
- [Marten](https://github.com/JasperFx/marten) -Postgresql作为.Net应用程序的文档数据库和事件存储.
- [MassTransit](https://github.com/MassTransit/MassTransit) -.NET的分布式应用程序框架.
- [MediatR](https://github.com/jbogard/MediatR) - Supports request/response, commands, queries, notifications and events, synchronous and async with intelligent dispatching via C# generic variance.
- [MessageRouter](https://github.com/QuickenLoans/MessageRouter) -在此视频中进行了介绍： [The Beating Heart of CQRS, or Actor-Based Message Routing on the CLR](https://vimeo.com/171178586) by Paulmichael Blasucci at the New York F# .NET User Group.
- [NetDevPack](https://github.com/netdevpack) -使用.NET（DDD，CQRS，规范模式，MediatR，验证，通知）提高一组开发人员的开发效率的通用类和实现.
- [NEventStore](https://github.com/NEventStore/NEventStore) -使用事件源作为存储机制时，用于抽象化不同存储实现的持久性库.
- [NServiceBus](https://github.com/Particular/NServiceBus) -.NET的服务总线.
- [Projac](https://github.com/yreynhout/Projac) -Projac是一组投影库，允许您编写针对各种后备店的投影.
- [shriek-fx](https://github.com/ElderJames/shriek-fx) -使用.NET Core 2.0开发的简单，优雅且有用的域驱动设计和CQRS框架.
- [SqlStreamStore](https://github.com/damianh/SqlStreamStore) -面向基于SQL的实现的.NET流存储库.
- [Streamstone](https://github.com/yevhen/Streamstone) -Azure表存储的事件存储.
- [Stringly.Typed](https://github.com/mission202/Stringly.Typed) -使字符串与.NET类型之间的转换更加容易.
- [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0.

### Databases
- [Event Store](https://geteventstore.com) -具有JavaScript中复杂事件处理功能的开源功能数据库.
- [Eventsourcing](https://eventsourcing.com) -业务事件捕获和查询框架.
- [Serialized](https://serialized.io) -事件搜索和CQRS的完整平台.

### Elixir
- [Commanded](https://github.com/slashdotdash/commanded) -适用于CQRS / ES应用程序的命令处理中间件，用于集合和流程管理器的纯功能数据结构，点对点消息路由以及Elixir（Erlang VM）中的更多功能-Actor并发模型中的所有功能.
- [Event Bus](https://github.com/otobus/event_bus) -具有内置事件存储和基于ETS的事件观察器的Elixir可追溯，可扩展且极简的事件总线实现.
- [eventstore](https://github.com/slashdotdash/eventstore) -使用PostgreSQL进行持久化的CQRS事件存储.

### JavaScript
- [cqrs.js](http://cqrs.js.org)  -node.js中的CQRS实现. 包括 [node-eventstore](https://github.com/adrai/node-eventstore), [node-cqrs-domain](https://github.com/adrai/node-cqrs-domain), [node-eventdenormalizer](https://github.com/adrai/node-cqrs-eventdenormalizer), [node-cqrs-saga](https://github.com/adrai/node-cqrs-saga).
- [Node API Boilerplate](https://github.com/talyssonoc/node-api-boilerplate) -用于DDD和Clean Architecture应用程序的NodeJS Web API样板.
- [wolkenkit](https://www.wolkenkit.io/) -用于JavaScript和Node.js的CQRS，DDD和事件源框架.

### JVM
- [akka-ddd](https://github.com/pawelkaczor/akka-ddd) -可重用的构件，用于基于CQRS / DDDD的方法在Akka平台上构建应用程序.
- [Apache Isis](https://isis.apache.org/index.html) -Apache Isis是一个框架，用于以Java快速开发域驱动的应用程序.
- [Axon Framework](http://www.axonframework.org/) -轴突框架致力于使希望基于CQRS原理创建Java应用程序的开发人员的工作更加轻松.
- [DDDplus framework](https://github.com/funkygao/cp-ddd-framework) -用于基于DDD的复杂业务体系结构的轻量级灵活开发框架.
- [JESA](https://github.com/yreynhout/JESA) -Java的事件源聚合.
- [Lagom](https://www.lagomframework.com)  -Lagom框架是用于Java虚拟机的微服务框架，具有用于Java和Scala语言的API. 它包括一个基于事件源/ CQRS的持久性模块.
- [SeedStack's Business Framework](http://seedstack.org/docs/business/) -一组构建块，使您能够根据域驱动设计（DDD）方法对业务逻辑进行编码.
- [Spine Event Engine](https://spine.io/)  -用于构建云应用程序的CQRS / ES框架. 在Protobuf中使用其命令，事件和实体状态定义有界上下文. 在Proto生成的代码之上，后端逻辑是用Java编写的.  Java，JS或Dart中的客户端代码通过gRPC与后端进行通信.

### PHP
- [Broadway](https://github.com/broadway/broadway) -Broadway是一个（PHP）项目，为创建CQRS和事件源应用程序提供基础结构和测试帮助程序.
- [Ecotone](http://ecotone.tech) -在PHP中启用消息驱动的体系结构，并提供遵循DDD和CQRS原理的构建块.

### Python
- [Eventsoucing in Python](https://github.com/johnbywater/eventsourcing)  -成熟，稳定的Python库，用于事件源和DDD. 支持各种数据库，域事件的不同排序，应用程序级别加密，快照，乐观并发控制和流程事件. 可以独立于基础架构定义应用程序以及整个应用程序系统，并以不同的方式（单线程，多线程，计时，步进，多进程，参与者模型）和不同的基础架构运行.
- [dry-python](https://github.com/dry-python) -一组用于可插入业务逻辑组件的库.

### Ruby
- [Rails Event Store](https://railseventstore.org)  -Rails Event Store（RES）是一个用于发布，使用，存储和检索事件的库. 它是为Rails应用程序使用事件驱动的体系结构的最佳伴侣.

## Podcasts and Interviews

- [Deeper into DDD on DotNetRocks with David Real](http://dotnetrocks.com/?show=1151) -2015年6月11日.
- [Thinking in DDD on DotNetRocks with Julie Lerman and Steve Smith](http://dotnetrocks.com/?show=1023) -2014年8月19日.
- [Eric Evans on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=236) -2007年5月10日.
- [Jimmy Nilsson on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=191) -2006年8月29日.
- [Being the Worst](http://www.beingtheworst.com) -2012年至2016年.
- [Software Engineering Radio Episode 225: Eric Evans on Domain-Driven Design at 10 Years](http://www.se-radio.net/2015/05/se-radio-episode-226-eric-evans-on-domain-driven-design-at-10-years/) -2015年5月13日.
- [Software Engineering Radio Episode 218: Udi Dahan on CQRS (Command Query Responsibility Segregation)](http://www.se-radio.net/2015/01/episode-218-udi-dahan-on-cqrs-command-query-responsibility-segregation/) -2015年1月30日.

## Conferences

- [Domain-Driven Design Europe](https://dddeurope.com) -领先的DDD会议（COVID19期间在线）
- [EventSourcing](https://dddeurope.com/2020/#eventsourcing) -CQRS / EventSourcing社区的新活动
- [DDD Foundations](https://dddeurope.com/2020/#foundations) -为DDD新人策划的会议
- [Explore DDD - USA](http://exploreddd.com/)
- [Kandddinsky - Germany](http://kandddinsky.com/)

## User Groups

- [Collective CFP](https://sessionize.com/ddd-meetups) -立即将演讲提交给所有DDD用户组.
- [Map of user groups in Europe](https://datawrapper.dwcdn.net/9FNZI/)
- [Map of user groups in North America](https://datawrapper.dwcdn.net/nbZkd/)
- [Map of user groups in Asia](https://datawrapper.dwcdn.net/oin66/)
- [Map of user groups in Africa](https://datawrapper.dwcdn.net/yaEOa/)
- [Virtual](https://virtualddd.com/)
- [Worldwide](https://www.meetup.com/worldwide-eventstorming-meetup/) -特定于EventStorming
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

- [Domain Storytelling](http://www.domainstorytelling.org/)  -一种知识压缩技术，可帮助相关人员熟悉领域并制定出表示他们共同理解的模型. 可作为 [print-out template](http://www.domainstorytelling.org/images/DST_Whiteboard-Kit.pdf)以及开源在线工具， [WPS Modeler](https://www.wps.de/modeler) ([source](https://github.com/wps/domain-story-modeler)).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Nick Chamberlain](https://buildplease.com) 放弃了此作品的所有版权以及相关或邻近的权利.
