<div class="github-widget" data-repo="awesome-spark/awesome-spark"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
[<img src="https://cdn.rawgit.com/awesome-spark/awesome-spark/f78a16db/spark-logo-trademark.svg" align="right">](https://spark.apache.org/)

## Awesome Spark [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

一个很棒的精选清单 [Apache Spark](https://spark.apache.org/) 包和资源.

 _Apache Spark 是一个开源集群计算框架. 最初开发于 [University of California](https://www.universityofcalifornia.edu/), [Berkeley's AMPLab](https://amplab.cs.berkeley.edu/)，Spark 代码库后来被捐赠给了 [Apache Software Foundation](https://www.apache.org/) ，此后一直保持.  Spark 提供了一个接口，用于对具有隐式数据并行性和容错性的整个集群进行编程_（[Wikipedia 2017](#wikipedia-2017)).

Apache Spark 的用户可以选择不同的 Python、R、Scala 和 Java 编程语言来与 Apache Spark API 交互.





## Packages

### Language Bindings


### Notebooks and IDEs
* [almond](https://almond.sh/) <img src="https://img.shields.io/github/last-commit/almond-sh/almond.svg"> - 一个Scala内核 [Jupyter](https://jupyter.org/).
* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/zeppelin.svg"> - 基于 Web 的笔记本，可通过可插入后端、集成绘图和开箱即用的广泛 Spark 支持实现交互式数据分析.
* [Polynote](https://polynote.org/)  <img src="https://img.shields.io/github/last-commit/polynote/polynote.svg">  - Polynote：受 IDE 启发的多语言笔记本. 它支持在一个笔记本中混合多种语言，并在它们之间无缝共享数据. 它鼓励具有不可变数据模型的可复制笔记本. 起源于 [Netflix](https://medium.com/netflix-techblog/open-sourcing-polynote-an-ide-inspired-polyglot-notebook-7f929d3f447).

### General Purpose Libraries

* [Succinct](http://succinct.cs.berkeley.edu/) <img src="https://img.shields.io/github/last-commit/amplab/succinct.svg">- 支持对压缩数据的高效查询.

### SQL Data Sources

SparkSQL 有 [serveral built-in Data Sources](https://spark.apache.org/docs/latest/sql-data-sources-load-save-functions.html#manually-specifying-options) 对于文件. 这些包括 `csv`、`json`、`parquet`、`orc` 和 `avro`. 它还支持 JDBC 数据库以及 Apache Hive. 可以通过包含下面列出的包或编写自己的包来添加其他数据源. 


### Storage


### Bioinformatics


### GIS


### Time Series Analytics


### Graph Processing

* [SparklingGraph](http://sparkling.ml) <img src="https://img.shields.io/github/last-commit/sparkling-graph/sparkling-graph.svg"> - 扩展 GraphX 特性的库，具有在图形分析中有用的多种功能（度量、生成器、链接预测等）.

### Machine Learning Extension
* [Apache SystemML](https://systemml.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/systemml.svg"> - 基于 Spark 的声明式机器学习框架.
* [Mahout Spark Bindings](https://mahout.apache.org/users/sparkbindings/home.html) \[status unknown\] - 线性代数 DSL 和具有类似 R 语法的优化器.
* [KeystoneML](http://keystone-ml.org/) - 使用 RDD 键入安全的机器学习管道.

### Middleware


### Monitoring


### Utilities


### Natural Language Processing

### Streaming

* [Apache Bahir](https://bahir.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/bahir.svg"> - 从 Spark 2.0 中排除的流连接器的集合（Akka、MQTT、Twitter.ZeroMQ）.

### Interfaces

* [Apache Beam](https://beam.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/beam.svg">  - 支持批处理和流应用程序的统一数据处理引擎.  Apache Spark 是受支持的执行环境之一.

### Testing


### Web Archives


### Workflow Management


## Resources

### Books

* [Learning Spark, 2nd Edition](https://www.oreilly.com/library/view/learning-spark-2nd/9781492050032/)  - 包含 Spark 3.0 的 Spark API 简介. 关于基本概念的良好知识来源.
* [Advanced Analytics with Spark](http://shop.oreilly.com/product/0636920035091.do)  - 有用的 Spark 处理模式集合. 附带 GitHub 存储库： [sryza/aas](https://github.com/sryza/aas).
* [Mastering Apache Spark](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/) - 有趣的笔记汇编 [Jacek Laskowski](https://github.com/jaceklaskowski) . 专注于 Spark 内部的不同方面.
* [Spark Gotchas](https://github.com/awesome-spark/spark-gotchas) - 提示、技巧和常见编程错误的主观汇编.

### Papers

* [Large-Scale Intelligent Microservices](https://arxiv.org/pdf/2009.08044.pdf) - Microsoft 论文，提出了一个基于 Apache Spark 的微服务编排框架，该框架将数据库操作扩展为包括 Web 服务原语.
* [Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://people.csail.mit.edu/matei/papers/2012/nsdi_spark.pdf) - 介绍核心分布式内存抽象的论文.
* [结构化流媒体：实时的声明式 API
 Apache Spark 中的应用](https://cs.stanford.edu/~matei/papers/2018/sigmod_structured_streaming.pdf) - Structured Streaming 是一种新的高级流 API，它是一种基于自动递增静态的声明式 API关系查询.

### MOOCS

* [Data Science and Engineering with Apache Spark (edX XSeries)](https://www.edx.org/xseries/data-science-engineering-apache-spark) - 五门课程系列（[Introduction to Apache Spark](https://www.edx.org/course/introduction-apache-spark-uc-berkeleyx-cs105x), [Distributed Machine Learning with Apache Spark](https://www.edx.org/course/distributed-machine-learning-apache-uc-berkeleyx-cs120x), [Big Data Analysis with Apache Spark](https://www.edx.org/course/big-data-analysis-apache-spark-uc-berkeleyx-cs110x), [Advanced Apache Spark for Data Science and Data Engineering](https://www.edx.org/course/advanced-apache-spark-data-science-data-uc-berkeleyx-cs115x), [Advanced Distributed Machine Learning with Apache Spark](https://www.edx.org/course/advanced-distributed-machine-learning-uc-berkeleyx-cs125x) ）涵盖软件工程和数据科学的不同方面. 面向 Python.
* [Big Data Analysis with Scala and Spark (Coursera)](https://www.coursera.org/learn/big-data-analysys)  - 面向 Scala 的入门课程. 一部分 [Functional Programming in Scala Specialization](https://www.coursera.org/specializations/scala).

### Workshops

* [AMP Camp](http://ampcamp.berkeley.edu) - 定期举办的培训活动 [UC Berkeley AMPLab](https://amplab.cs.berkeley.edu/) . 有用的练习和录制的研讨会的来源，涵盖了来自 [Berkeley Data Analytics Stack](https://amplab.cs.berkeley.edu/software/).

### Projects Using Spark

* [Oryx 2](https://github.com/OryxProject/oryx) - [Lambda architecture](http://lambda-architecture.net/) 基于 Apache Spark 构建的平台和 [Apache Kafka](http://kafka.apache.org/) 专注于实时大规模机器学习.
* [Photon ML](https://github.com/linkedin/photon-ml) - 支持经典广义混合模型和广义加性混合效应模型的机器学习库.
* [PredictionIO](https://prediction.io/) - 机器学习服务器，供开发人员和数据科学家在很短的时间内构建和部署预测应用程序.
* [Crossdata](https://github.com/Stratio/Crossdata) - 具有扩展数据源 API 和多用户环境的数据集成平台.

### Blogs

- [Spark Technology Center](http://spark.tc/blog/)  - 与 Spark 生态系统相关的高度多样化帖子的重要来源. 从实用建议到 Spark 提交者配置文件.

### Docker Images

- [jupyter/docker-stacks/pyspark-notebook](https://github.com/jupyter/docker-stacks/tree/master/pyspark-notebook) - 带有 Jupyter Notebook 和 Mesos 客户端的 PySpark.
- [sequenceiq/docker-spark](https://github.com/sequenceiq/docker-spark) - 纱线图像来自 [SequenceIQ](http://www.sequenceiq.com/).

### Miscellaneous

- [Spark with Scala Gitter channel](https://gitter.im/spark-scala/Lobby) - “_一个讨论和提问有关使用 Scala 进行 Spark 编程的地方_”开始于 [@deanwampler](https://github.com/deanwampler).
- [Apache Spark User List](http://apache-spark-user-list.1001560.n3.nabble.com/) 和 [Apache Spark Developers List](http://apache-spark-developers-list.1001551.n3.nabble.com/) - Mailing lists dedicated to usage questions 和 development topics respectively.

## References

<p id="wikipedia-2017">维基百科.  2017. “Apache Spark — 维基百科，免费的百科全书.”  <a href="https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753" class="uri">https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753</a> .</p>

## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/publicdomain.svg"
     style="border-style: none;" alt="Public Domain Mark" />
</a>
<br />
这项工作（ <span property="dct:title">Awesome Spark</span> ，来自<a href="https://github.com/awesome-spark/awesome-spark" rel="dct:creator">https://github.com/awesome-spark/awesome-spark</a> ）由<a href="https://github.com/zero323" rel="dct:publisher"><span property="dct:title">Maciej Szymkiewicz</span></a>标识，不受已知版权限制.
</p>

Apache的火花，火花，Apache和星火标识是<a href="https://www.apache.org/foundation/marks/">商标</a>
   <a href="http://www.apache.org">Apache 软件基金会</a>. 此编译未得到 Apache 软件基金会的认可.


灵感来自 [sindresorhus/awesome](https://github.com/sindresorhus/awesome).
