<div class="github-widget" data-repo="erictleung/awesome-nosql-guides"></div>
## Awesome NoSQL Guides [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

 &gt;“NoSQL（最初指的是&#39;非SQL&#39;或&#39;非关系&#39;）数据库提供了一种存储和检索数据的机制，该机制是以关系数据库中使用的表格关系之外的方式建模的.”   -  [Wikipedia](https://en.wikipedia.org/wiki/NoSQL)

有关* using * NoSQL数据库的资源和链接的策划列表以及决定使用时要查找的内容.

对于实际的NoSQL数据库，你可以去 [here](https://github.com/sindresorhus/awesome#databases), [here](http://nosql-database.org), [here](https://github.com/igorbarinov/awesome-data-engineering#databases)， 要么 [here](https://github.com/kahun/awesome-sysadmin#nosql).





## Overview of NoSQL

- [Introduction To NoSQL - Martin Fowler](https://youtu.be/qI_g07C_Q5I) （54:52） - 在GOTO 2012上的演讲是对NoSQL数据库的一个很好的介绍，NoSQL数据库的类型，它们的历史，优点和缺点，以及如何以及何时使用它们.
- [NoSQL Distilled](http://martinfowler.com/books/nosql.html) - 非常可消化且经济实惠的书籍，描述了不同的NoSQL数据库，并帮助您决定使用NoSQL数据库是否适合您的项目.
- [Seven Databases in Song](https://youtu.be/jyx8iP5tfCI) （1:43） - 来自2012年的有趣歌曲大约有七个（六个是NoSQL）数据库，并且非常简洁地概述了它们各自的工作方式.
- [NoSQL Databases: a Survey and Decision Guidance](https://medium.com/baqend-blog/nosql-databases-a-survey-and-decision-guidance-ea7823a822d#.nhzop4d23) （2016） - “这个NoSQL工具箱允许我们推导出一个简单的决策树，以帮助从业者和研究人员根据中央应用程序要求过滤潜在的系统候选者.”
- [Data Management in the Cloud: Limitations and Opportunities](http://www.cs.yale.edu/homes/dna/papers/abadi-cloud-ieee09.pdf) （PDF） -  Abadi（2009）讨论了云中数据管理和数据分析的局限性和机会.
- [10 NoSQL Misconceptions](http://www.dummies.com/how-to/content/10-nosql-misconceptions.html) - 关于NoSQL数据库的一些误解，涉及的主题包括它们是什么，ACID合规性和安全性.
- [10 Reasons Developers Love NoSQL](http://www.dummies.com/programming/big-data/10-reasons-developers-love-nosql/) - 开发人员喜欢使用NoSQL数据库的十个参数列表.
- [Distribution, Data, Deployment: Software Architecture Convergence in Big Data Systems](https://resources.sei.cmu.edu/library/asset-view.cfm?assetID=90909)  （PDF） -  Gorton和Klein（2014）的论文，讨论了在分配，数据和部署方面处理大数据系统时的软件工程问题.  也可访问 [here](https://doi.org/10.1109/MS.2014.51).
- [Use cases for NoSQL](https://stackoverflow.com/questions/2875432/use-cases-for-nosql) （2017） - 讨论使用NoSQL数据库而不是传统SQL数据库的最佳用例的Stack Overflow.
- [Best Practices for NoSQL Database Design](https://softwareengineering.stackexchange.com/q/158790/) （2012） - 一对NoSQL数据库设计的答案和链接.


## Data Structures and Modeling

- [Structure Your Database](https://firebase.google.com/docs/database/android/structure-data) （上次更新时间2018） - 如果数据库使用JSON，则构建数据的最佳实践. [Here's](https://www.firebase.com/docs/web/guide/structuring-data.html) 2016年以来的本指南的旧版本.
- [NoSQL Data Modeling Techniques](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/) （2012） - 本文从数据建模的角度提供了NoSQL系统系列的简短比较，并摘要了几种常见的建模技术.
- [Data Models for MongoDB](https://docs.mongodb.com/manual/data-modeling/)   - 数据建模帮助特定于MongoDB，范围从模式验证和示例模式.  但是，概念可能会延续到其他文档NoSQL数据库.
- [Data Models Will Be Beautiful Again](https://tdwi.org/articles/2016/11/22/data-models-will-be-beautiful-again.aspx) （2016） -  Essay认为，尽管存在无模式数据库，但深思熟虑的数据库建模对于使用算法获取知识和见解非常重要.
- [Unified Data Modeling for Relational and NoSQL Databases](https://www.infoq.com/articles/unified-data-modeling-for-relational-and-nosql-databases) - 使用统一数据建模技术管理NoSQL和关系数据库的解决方案.
- [Unifying Relational, Document, Graph, and Temporal Data Models](https://fauna.com/blog/unifying-relational-document-graph-and-temporal-data-models) - 在同一数据库中查询多个范例的模式.


## Trade-Offs in CAP/Brewer's Theorem

- [Visual Guide to NoSQL Systems](http://blog.nahurst.com/visual-guide-to-nosql-systems) （2010） - 可视化显示不同NoSQL数据库中CAP定理的权衡.


## Crowd-Sourced Information

- [/r/nosql](https://www.reddit.com/r/nosql) -  NoSQL上关于NoSQL数据库的一般问题和讨论的Reddit页面.
-  Stack Overflow上的[[nosql]标签]（https://stackoverflow.com/tags/nosql/info）
- [Ask HN: Learning NoSQL, papers and books](https://news.ycombinator.com/item?id=15427932) （2017） - “在您看来，哪些论文和书籍必须真正理解NoSQL主题？”


## Graph Databases

- [Graph Databases Use Cases](https://neo4j.com/use-cases/) - 尽管面向Neo4j的文档，概念适用于所有图形数据库.
- [How the ICIJ Used Neo4j to Unravel the Panama Papers - Mar Cabra](https://youtu.be/S20XMQyvANY) （32:02） - 了解图形数据库如何成为探索与避税天堂公司相关的主要人物的关键，包括50多个国家的140位政治家.
- [Graph Databases for Beginners: The Basics of Data Modeling](https://neo4j.com/blog/data-modeling-basics/) - 讨论数据建模的基础知识以及应采取的方法.
- [Graph Data Modeling Guidelines](https://neo4j.com/developer/guide-data-modeling/) - 与Neo4j直接相关，但可能适用于任何图形数据库.
- [Graph Data Modeling Visualize Structure and Meaning](http://www.graphdatamodeling.com) - 图形数据建模简介，是对本书的介绍， ["Graph Data Modeling for NoSQL and SQL"](https://technicspub.com/graph-data-modeling/) 作者：Thomas Frisendal.


## Criticisms and Debates

- [Addressing the NoSQL Criticism](http://bradley-holt.com/2011/07/addressing-the-nosql-criticism/) （2011） - 反对对NoSQL数据库的九个批评，因为它们适用于CouchDB，但也可能适用于其他人.
- [Thank You for Your Help NoSQL, but We Got It from Here](http://blog.memsql.com/nosql/) （2018） - 鉴于扩展问题，NoSQL数据库推动了数据库的发展，但现在NewSQL已经解决了这些问题（从MemSQL的角度来看）.
- [The Five Stages of NoSQL](https://sookocheff.com/post/opinion/the-five-stages-of-nosql/) （2016） - 经历挑选和使用NoSQL数据库的阶段反映了悲伤的五个阶段.
- [The Biggest Challenges of Moving to NoSQL](https://dzone.com/articles/the-biggest-challenges-of-moving-to-nosql) （2017） - 速度和可扩展性以及开发人员的喜悦是从持续转向NoSQL的挑战中获得的收益.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Eric Leung](https://erictleung.com) 已放弃对此作品的所有版权及相关或相邻权利.
