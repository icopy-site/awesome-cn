<div class="github-widget" data-repo="erictleung/awesome-nosql-guides"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome NoSQL Guides [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

 &gt;“ NoSQL（最初指的是&#39;非SQL&#39;或&#39;非关系&#39;）数据库提供了一种存储和检索数据的机制，该机制以与关系数据库中使用的表格关系不同的方式建模.”  - [Wikipedia](https://en.wikipedia.org/wiki/NoSQL)

精选的资源和链接列表，涉及“使用” NoSQL数据库以及在决定使用数据库时要查找的内容.

对于实际的NoSQL数据库，您可以 [here](https://github.com/sindresorhus/awesome#databases), [here](http://nosql-database.org), [here](https://github.com/igorbarinov/awesome-data-engineering#databases)， 要么 [here](https://github.com/kahun/awesome-sysadmin#nosql).





## Overview of NoSQL

- [Introduction To NoSQL - Martin Fowler (54:52)](https://youtu.be/qI_g07C_Q5I) -在GOTO 2012上的演讲很好地介绍了NoSQL数据库，NoSQL数据库的类型，它们的历史，优缺点以及如何以及何时使用它们.
- [NoSQL Distilled](http://martinfowler.com/books/nosql.html) -易于消化且价格适中的书，描述了不同的NoSQL数据库，并帮助您决定是否使用NoSQL数据库适合您的项目.
- [Seven Databases in Song (1:43)](https://youtu.be/jyx8iP5tfCI) -2012年的一首有趣的歌曲，讲述了七个（六个是NoSQL）数据库，并简要概述了每个数据库的工作方式.
- [NoSQL Databases: a Survey and Decision Guidance (2016)](https://medium.com/baqend-blog/nosql-databases-a-survey-and-decision-guidance-ea7823a822d#.nhzop4d23) -“此NoSQL工具箱使我们能够推导简单的决策树，以帮助从业人员和研究人员根据中央应用程序的要求筛选潜在的系统候选对象.”
- [Data Management in the Cloud: Limitations and Opportunities (PDF)](http://www.cs.yale.edu/homes/dna/papers/abadi-cloud-ieee09.pdf) -Abadi（2009）讨论了云中数据管理和数据分析的局限性和机遇.
- [10 NoSQL Misconceptions](http://www.dummies.com/how-to/content/10-nosql-misconceptions.html) -关于NoSQL数据库的一些误解，涉及诸如主题，符合ACID和安全性等主题.
- [10 Reasons Developers Love NoSQL](http://www.dummies.com/programming/big-data/10-reasons-developers-love-nosql/) -有关为什么开发人员喜欢使用NoSQL数据库的十个参数的列表.
- [Distribution, Data, Deployment: Software Architecture Convergence in Big Data Systems (PDF)](https://resources.sei.cmu.edu/library/asset-view.cfm?assetID=90909)  -Gorton和Klein（2014）的论文，讨论了在大数据系统的分发，数据和部署方面对软件工程的关注.  也可访问 [here](https://doi.org/10.1109/MS.2014.51).
- [Use cases for NoSQL (2017)](https://stackoverflow.com/questions/2875432/use-cases-for-nosql) -有关在传统SQL数据库上使用NoSQL数据库的最佳用例的堆栈溢出的讨论.
- [Best Practices for NoSQL Database Design (2012)](https://softwareengineering.stackexchange.com/q/158790/) -有关NoSQL数据库设计的几个答案和链接.
- [Five Common Data Stores and When to Use Them (2019)](https://engineering.shopify.com/blogs/engineering/five-common-data-stores-usage) - Article describes five common data stores (relational database, non-relational (“NoSQL”) database, key-value store, full-text search engine, message queue) and their attributes.
- [NoSQL Databases (PDF)](https://web.archive.org/web/20190927222738/https://www.christof-strauch.de/nosqldbs.pdf)  -长达149页的文档，概述了NoSQL数据库的动机和基本原理，以及这些数据库之间的通用概念，技术和模式；  最后更新时间约为2011年.
- [NoSQL Data Architecture & Data Governance: Everything You Need to Know (2018)](https://www.dataversity.net/nosql-data-architecture-data-governance-everything-need-know/) -带有图表的不同NoSQL数据库体系结构概述.


## Data Structures and Modeling

- [Structure Your Database](https://firebase.google.com/docs/database/android/structure-data) -如果您的数据库使用JSON，则最好的做法是（截至2018年）结构化数据.
- [NoSQL Data Modeling Techniques (2012)](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/) -本文从数据建模的角度简短地比较了NoSQL系统系列，并总结了几种常见的建模技术.
- [Data Models for MongoDB](https://docs.mongodb.com/manual/data-modeling/)  -特定于MongoDB的数据建模帮助，包括模式验证和示例模式.  但是，概念可能会延续到其他文档NoSQL数据库.
- [Data Models Will Be Beautiful Again (2016)](https://tdwi.org/articles/2016/11/22/data-models-will-be-beautiful-again.aspx) -Essay认为，尽管现有无模式数据库，但是周到的数据库建模对于使用算法获取知识和见解至关重要.
- [Unified Data Modeling for Relational and NoSQL Databases](https://www.infoq.com/articles/unified-data-modeling-for-relational-and-nosql-databases) -使用统一数据建模技术管理NoSQL和关系数据库的解决方案.
- [Unifying Relational, Document, Graph, and Temporal Data Models](https://fauna.com/blog/unifying-relational-document-graph-and-temporal-data-models) -用于查询同一数据库中多个范例的模式.
- [How to Design Schema for Your NoSQL Database?](https://www.dataversity.net/how-to-design-schema-for-your-nosql-database/#) -尽管人们普遍认为NoSQL不需要架构，但本文概述了NoSQL数据库如何遵循“查询驱动的设计”以及架构中这种灵活性的注意事项.


## Trade-Offs in CAP/Brewer's Theorem

- [Visual Guide to NoSQL Systems (2010)](http://blog.nahurst.com/visual-guide-to-nosql-systems) -在不同NoSQL数据库之间的CAP定理中权衡取舍的可视化显示.
- [How to Choose the Right NoSQL Database for Your Application? (2018)](https://www.dataversity.net/choose-right-nosql-database-application/) -审查CAP定理，并将常见的NoSQL数据库映射到CAP类别以帮助选择一种.


## Crowd-Sourced Information

- [/r/nosql](https://www.reddit.com/r/nosql) -有关NoSQL数据库的一般问题和讨论，有关NoSQL的Reddit页面.
-[[Stack Overflow]上的[[nosql]标记]（https://stackoverflow.com/tags/nosql/info）
- [Ask HN: Learning NoSQL, papers and books (2017)](https://news.ycombinator.com/item?id=15427932) -“您认为，哪些纸和书是真正理解NoSQL主题所必需的？”.


## Graph Databases

- [Graph Databases Use Cases](https://neo4j.com/use-cases/) -尽管文档针对Neo4j，但概念适用于所有图形数据库.
- [How the ICIJ Used Neo4j to Unravel the Panama Papers - Mar Cabra (32:02)](https://youtu.be/S20XMQyvANY) -了解图形数据库如何成为关键人物，以探索谁是避税天堂中与公司相关的主要人物，其中包括50多个国家/地区的140名政客.
- [Graph Databases for Beginners: The Basics of Data Modeling](https://neo4j.com/blog/data-modeling-basics/) -讨论数据建模的基础知识以及应采取的方法.
- [Graph Data Modeling Guidelines](https://neo4j.com/developer/guide-data-modeling/) -与Neo4j直接相关，但可能适用于任何图形数据库.
- [Graph Data Modeling Visualize Structure and Meaning](http://www.graphdatamodeling.com) -图形数据建模简介，是本书的简介， ["Graph Data Modeling for NoSQL and SQL"](https://technicspub.com/graph-data-modeling/) 托马斯·弗里森达尔（Thomas Frisendal）.


## Criticisms and Debates

- [Addressing the NoSQL Criticism (2011)](http://bradley-holt.com/2011/07/addressing-the-nosql-criticism/) -反对对NoSQL数据库的九种批评，因为它们适用于CouchDB，但也可能适用于其他批评.
- [Thank You for Your Help NoSQL, but We Got It from Here (2018)](http://blog.memsql.com/nosql/) -争论到NoSQL数据库在扩展问题上推动了数据库的发展，但是现在NewSQL解决了这些问题（从MemSQL的角度来看）.
- [The Five Stages of NoSQL (2016)](https://sookocheff.com/post/opinion/the-five-stages-of-nosql/) -选择和使用NoSQL数据库的阶段反映了悲伤的五个阶段.
- [The Biggest Challenges of Moving to NoSQL (2017)](https://dzone.com/articles/the-biggest-challenges-of-moving-to-nosql) －通过迁移到NoSQL所面临的挑战，经久不衰的发展带来了速度，可伸缩性和开发人员的喜悦.


## Miscellaneous

- [What is a NoSQL Database? Learn By Writing One In Python](https://jeffknupp.com/blog/2014/09/01/what-is-a-nosql-database-learn-by-writing-one-in-python/) -通过使用Python构建玩具数据库来学习NoSQL和RDBMS的优秀教程.
- [Dynamo vs Cassandra : Systems Design of NoSQL Databases](https://sujithjay.com/data-systems/dynamo-cassandra/) -博客文章比较和构造了两个著名的NoSQL数据库的系统设计.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Eric Leung](https://erictleung.com) 放弃了此作品的所有版权以及相关或邻近的权利.
