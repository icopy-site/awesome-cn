<div class="github-widget" data-repo="simskij/awesome-software-architecture"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">

<img src="https://raw.githubusercontent.com/simskij/awesome-software-architecture/master/./banner.png" />

## Awesome Software Architecture<br/>
  
[![awesome-badge](https://awesome.re/badge.svg)](https://awesome.re)
  
[Software architecture](https://en.wikipedia.org/wiki/Software_architecture) 旨在描述高水平 
软件的结构以及创建它们的学科. 由于这个话题相当广泛，它可能 
包含一些资源，这些资源也出现在更多的利基列表中. 

<i>
  如果您喜欢此列表，请考虑通过在 Twitter 上关注<a href="https://twitter.com/0x12b/">@0x12b</a>来表达您的支持. 
</i>
  
</div>



## Principles
- [Flexibility](https://medium.com/faun/flexibility-a-software-architecture-principle-6eafe045a1d4) - 能够适应环境和可用性要求的变化，而不包括结构性变化.

## Design Patterns
- [Ports and adapters pattern](https://jmgarridopaz.github.io/content/hexagonalarchitecture.html) - 将应用程序核心逻辑与其使用的服务分离.
- [Observer pattern](https://medium.com/datadriveninvestor/design-patterns-a-quick-guide-to-observer-pattern-d0622145d6c2) - 一对多状态变化通知.
- [Design Patterns: Elements of Reusable Object-Oriented Software, by Gamma et al](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612/) - 开始这一切的那个：orange_book:.
- [Software Design Patterns: A Guide](https://airbrake.io/blog/design-patterns/software-design-patterns-guide) - 常见软件设计模式介绍.
- [Software Design Patterns and Principes (quick overview)](https://www.youtube.com/watch?v=WV2Ed1QTst8) - 关于常见设计模式的原因以及它们的优点和缺点.
- [CQRS](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs) - 使用单独的接口将读取数据的操作与更新数据的操作分开.
- [Event Sourcing](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing) - 不是仅存储域中数据的当前状态，而是使用仅附加存储来记录对该数据采取的完整系列操作.
- [Feature Toggles](https://www.martinfowler.com/articles/feature-toggles.html) - 功能切换（通常也称为功能标志）是一种强大的技术，允许团队在不更改代码的情况下修改系统行为.
- [Behavior Driven Development (BDD) and Functional Testing](https://medium.com/javascript-scene/behavior-driven-development-bdd-and-functional-testing-62084ad7f1f2) - BDD 使用人类可读的软件用户需求描述作为软件测试的基础.
- [N-tier architecture style](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/n-tier) - 层是分离职责和管理依赖关系的一种方式.

### Scalability and Resilience
- [Circuit Breaker](https://martinfowler.com/bliki/CircuitBreaker.html) - 保护故障资源以防止级联故障.
- [Bulkhead](https://docs.microsoft.com/en-us/azure/architecture/patterns/bulkhead) - 对资源进行分区以隔离故障.
- [Leader Election](https://docs.microsoft.com/en-us/azure/architecture/patterns/leader-election) - 通过选举领导协调分布式工作负载.

## Methodology

- [No silver bullet, by Brooks](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf) - 为小幅增长的软件提供案例：orange_book:.
- [Clean Architecture, by Martin](https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164) - 构建可持续和可维护软件的关键原则和概念：orange_book:.
- [Technical Debt, by Fowler](https://martinfowler.com/bliki/TechnicalDebt.html) - 累积技术债务的成本和影响.
- [The Magic Tricks of Testing, by Metz](https://www.youtube.com/watch?v=URSWYvyc42M) - 将简约的理想作为一种实用且务实的软件测试方法.
- [TDD, Where did it all go wrong?, by Cooper](https://www.infoq.com/presentations/tdd-original/) - 关于 TDD 实践和边界的建议，以减少耦合.

## Documentation

- [arc42](https://arc42.org/) - 软件和系统架构的文档和通信模板.
- [Architectural Decision Records](https://adr.github.io/) - 以与代码相同的方式版本和文档架构决策.
- [Documenting architecture](https://dzone.com/articles/documenting-architecture-1) - 关于如何有效记录软件架构的实用技巧.


## Workshop formats

- [Event Storming](https://www.eventstorming.com/) - 探索领域驱动设计的格式.
- [MoSCoW Prioritization](https://www.knowledgehut.com/blog/agile/how-to-prioritise-requirements-with-the-moscow-technique) - 对需求进行优先排序的快速而简单的方法.
- [Story mapping](https://www.jpattonassociates.com/wp-content/uploads/2015/03/story_mapping.pdf) - 通过创建故事地图可视化您的需求.
- [Impact mapping](https://www.impactmapping.org/) - 一种用于构建产品和交付项目的战略规划技术.
- [Business Model Canvas](https://en.wikipedia.org/wiki/Business_Model_Canvas) - 商业计划变得简单和直观.
- [Business Model Generation, by Osterwalder & Pigneur](https://www.amazon.com/Business-Model-Generation-Visionaries-Challengers/dp/0470876417) - 轻松可视化您的价值主张、成本和收入流 :orange_book:.

## Modeling

- [The C4 Model](https://c4model.com/) - 使用上下文、容器、组件和代码描述软件.
- [Wikipedia: Data modeling](https://en.wikipedia.org/wiki/Data_modeling) - 很棒的简短介绍数据建模.

## Tools

- [Sparx Systems Enterprise Architect](https://sparxsystems.com/products/ea/index.html)  - 面向对象的建模套件. 仅适用于 Windows.
- [Visual Paradigm](https://www.visual-paradigm.com/)  - 类似于企业架构师. 适用于多个平台.
- [Lucidchart](https://www.lucidchart.com)  - 付费的基于云的图表编辑器. 可在所有常见平台上使用.
- [Draw.io](https://www.draw.io)  - 免费和简单的图表编辑器. 与 Visio 等类似. 可在所有常见平台上使用.
- [Structurizr](https://structurizr.com) - 基于 C4 模型的建模工具（见上文）.
- [PlantUML](http://plantuml.com/) - 与图表的降价一样，PlantUML 将类似英语的语法呈现为图表.
- [PlantUML for Atlassian](https://marketplace.atlassian.com/apps/1215115/plantuml-for-confluence-cloud?hosting=cloud&tab=overview) - Adds support for PlantUML-based diagrams in the atlassian suite.
- [Sketchboard.io](https://sketchboard.io/) - 协作画板.

## Frameworks

### Agile

- [Scrum](https://www.scrumguides.org/) - 开发和维护复杂产品的框架.
- [SAFe](https://www.scaledagileframework.com/) - 可扩展的敏捷框架.
- [Nexus](https://www.scrum.org/resources/scaling-scrum) - 根据 Scrum 的共同创建者 Ken Schwaber 的说法，可扩展的 Scrum. 
- [The death of Agile, by Allen Holub](https://www.youtube.com/watch?v=HZyRQ8Uhhmk&feature=youtu.be) - “敏捷”如何脱离敏捷的基本原则，以及我们需要做什么来解决问题.
- [Agile Architecture Pt. 1, by Allen Holub](https://www.youtube.com/watch?v=0kRCFVGpX7k) - 我们如何在敏捷世界中使用架构. 
- [Agile Architecture Pt. 2, by Allen Holub](https://www.youtube.com/watch?v=txbS0WJC1bo) - 我们如何在敏捷世界中使用架构. 
### Lean software development

- [Wikipedia: Lean Software Development](https://en.wikipedia.org/wiki/Lean_software_development) - 为软件开发领域翻译精益制造.
- [Rolling rocks downhill, by Clarke Ching](https://www.amazon.com/Rolling-Rocks-Downhill-Software-Projects/dp/1505446511) - 关于敏捷和精益软件开发的商业小说：orange_book:.
- [The Goal: A Process of Ongoing Improvement, by Goldratt](https://www.amazon.com/Goal-Process-Ongoing-Improvement/dp/0884270610)  - 关于在制造环境中不断改进的商业小说. 也很容易适应软件开发：orange_book:.
### Extreme programming

- [Extreme Programming](http://www.extremeprogramming.org/) - 最具体的流行敏捷流程，侧重于工程和开发实践.

### DevOps

- [Wikipedia: DevOps](https://en.wikipedia.org/wiki/DevOps) - 结合软件开发和运营实践，在保持高质量的同时缩短上市时间.
- [The Phoenix Project, by Gene Kim et al](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262592) - IT、Devops 并帮助您的业务获胜 :orange_book:.
- [The Unicorn Project, by Gene Kim](https://www.amazon.com/Unicorn-Project-Developers-Disruption-Thriving-ebook/dp/B07QT9QR41) - 数据时代的开发人员、数字颠覆和繁荣：orange_book:.
- [Keep CALMS and carry on](https://dwpdigital.blog.gov.uk/2019/03/25/keep-calms-and-carry-on-how-we-do-devops/) - BPDTS 如何使用 CALMS 模型作为其 DevOps 适应的参考. 
- [Chaos Engineering at Netfix](https://www.youtube.com/watch?v=6ilMZqKdMMU) - 混沌工程是软件工程中的一门新学科，可建立对大规模分布式系统行为的信心. 
- [Adidas DevOps Maturity Framework](https://github.com/adidas/adidas-devops-maturity-framework) - 基于 DevOps 的 CALMS 定义，该框架定义了一组功能和指南，当采用这些功能和指南时，可以提高团队的效率、有效性和幸福感.
## Bonus

- [How to learn software design and architecture - a roadmap](https://www.freecodecamp.org/news/software-design/) - 有助于学习深入了解软件架构的其他内容.

## Contributing

想为这份清单做出更好的贡献吗？ 耶，太棒了！ 在开始之前，请先查看我们<a href="code_of_conduct.md">的行为准则</a>和<a href="contributing.md">贡献指南</a>.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [simskij](https://github.com/simskij) 已放弃本作品的所有版权和相关或邻接权.
