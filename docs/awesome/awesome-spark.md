<div class="github-widget" data-repo="awesome-spark/awesome-spark"></div>
[<img src="https://cdn.rawgit.com/awesome-spark/awesome-spark/f78a16db/spark-logo-trademark.svg" align="right">](https://spark.apache.org/)

## Awesome Spark [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选清单 [Apache Spark](https://spark.apache.org/) 包和资源.

 _Apache Spark 是一个开源集群计算框架. 最初开发于 [University of California](https://www.universityofcalifornia.edu/), [Berkeley's AMPLab](https://amplab.cs.berkeley.edu/), Spark 代码库后来被捐赠给 [Apache Software Foundation](https://www.apache.org/) , 从那以后一直维护它.  Spark 提供了一个接口，用于对具有隐式数据并行性和容错性的整个集群进行编程_([Wikipedia 2017](#wikipedia-2017)).

Apache Spark 的用户可以选择不同的 Python、R、Scala 和 Java 编程语言来与 Apache Spark API 交互.





## Packages

### Language Bindings


### Notebooks and IDEs
* [almond](https://almond.sh/) <img src="https://img.shields.io/github/last-commit/almond-sh/almond.svg"> - 一个scala内核 [Jupyter](https://jupyter.org/).
* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/zeppelin.svg"> - 基于 Web 的笔记本，可通过可插入后端、集成绘图和开箱即用的广泛 Spark 支持实现交互式数据分析.
* [Polynote](https://polynote.org/)  <img src="https://img.shields.io/github/last-commit/polynote/polynote.svg">  - Polynote：受 IDE 启发的多语言笔记本. 它支持在一个笔记本中混合多种语言，并在它们之间无缝共享数据. 它通过不可变的数据模型鼓励可复制的笔记本. 源自 [Netflix](https://medium.com/netflix-techblog/open-sourcing-polynote-an-ide-inspired-polyglot-notebook-7f929d3f447).

### General Purpose Libraries

* [Succinct](http://succinct.cs.berkeley.edu/) <img src="https://img.shields.io/github/last-commit/amplab/succinct.svg">- 支持对压缩数据的高效查询.

### SQL Data Sources

SparkSQL 有 [serveral built-in Data Sources](https://spark.apache.org/docs/latest/sql-data-sources-load-save-functions.html#manually-specifying-options) 对于文件. 这些包括“csv”、“json”、“parquet”、“orc”和“avro”. 它还支持 JDBC 数据库以及 Apache Hive. 可以通过包含下面列出的包或编写您自己的包来添加其他数据源.


### Storage

* [lakeFS](https://docs.lakefs.io/integrations/spark.html) <img src="https://img.shields.io/github/last-commit/treeverse/lakefs.svg"> - 与 lakeFS 原子版本存储层集成.
### Bioinformatics


### GIS


### Time Series Analytics


### Graph Processing

* [SparklingGraph](http://sparkling.ml) <img src="https://img.shields.io/github/last-commit/sparkling-graph/sparkling-graph.svg"> - 扩展 GraphX 功能的库，具有多种在图形分析中有用的功能（测量、生成器、链接预测等）.

### Machine Learning Extension
* [Apache SystemML](https://systemml.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/systemml.svg"> - 基于 Spark 的声明式机器学习框架.
* [Mahout Spark Bindings](https://mahout.apache.org/users/sparkbindings/home.html) \[状态未知\] - 具有类似 R 语法的线性代数 DSL 和优化器.
* [KeystoneML](http://keystone-ml.org/) - 使用 RDD 键入安全的机器学习管道.
* [MLflow](https://mlflow.org/docs/latest/python_api/mlflow.spark.html#module-mlflow.spark) <img src="https://img.shields.io/github/last-commit/mlflow/mlflow.svg"> - 机器学习编排平台. 

### Middleware


### Monitoring


### Utilities


### Natural Language Processing

### Streaming

* [Apache Bahir](https://bahir.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/bahir.svg"> - 从 Spark 2.0（Akka、MQTT、Twitter、ZeroMQ）中排除的流式连接器的集合.

### Interfaces

* [Apache Beam](https://beam.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/beam.svg">  - 支持批处理和流处理应用程序的统一数据处理引擎.  Apache Spark 是受支持的执行环境之一.

### Testing


### Web Archives


### Workflow Management


## Resources

### Books

* [Learning Spark, 2nd Edition](https://www.oreilly.com/library/view/learning-spark-2nd/9781492050032/)  - 涵盖 Spark 3.0 的 Spark API 简介. 有关基本概念的良好知识来源.
* [Advanced Analytics with Spark](http://shop.oreilly.com/product/0636920035091.do)  - 有用的 Spark 处理模式集合. 随附的 GitHub 存储库： [sryza/aas](https://github.com/sryza/aas).
* [Mastering Apache Spark](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/) - 有趣的笔记汇编 [Jacek Laskowski](https://github.com/jaceklaskowski) . 专注于 Spark 内部结构的不同方面.
* [Spark Gotchas](https://github.com/awesome-spark/spark-gotchas) - 提示、技巧和常见编程错误的主观汇编.

### Papers

* [Large-Scale Intelligent Microservices](https://arxiv.org/pdf/2009.08044.pdf) - 微软的论文介绍了一个基于 Apache Spark 的微服务编排框架，该框架扩展了数据库操作以包括 Web 服务原语.
* [Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://people.csail.mit.edu/matei/papers/2012/nsdi_spark.pdf) - 介绍核心分布式内存抽象的论文.
* [Structured Streaming: A Declarative API for Real-Time Applications in Apache Spark](https://cs.stanford.edu/~matei/papers/2018/sigmod_structured_streaming.pdf) - Structured Streaming 是一种新的高级流式 API，它是一种基于自动增量静态关系查询的声明式 API.

### MOOCS

* [Data Science and Engineering with Apache Spark (edX XSeries)](https://www.edx.org/xseries/data-science-engineering-apache-spark) - 五门系列课程（[Introduction to Apache Spark](https://www.edx.org/course/introduction-apache-spark-uc-berkeleyx-cs105x), [Distributed Machine Learning with Apache Spark](https://www.edx.org/course/distributed-machine-learning-apache-uc-berkeleyx-cs120x), [Big Data Analysis with Apache Spark](https://www.edx.org/course/big-data-analysis-apache-spark-uc-berkeleyx-cs110x), [Advanced Apache Spark for Data Science and Data Engineering](https://www.edx.org/course/advanced-apache-spark-data-science-data-uc-berkeleyx-cs115x), [Advanced Distributed Machine Learning with Apache Spark](https://www.edx.org/course/advanced-distributed-machine-learning-uc-berkeleyx-cs125x) ) 涵盖了软件工程和数据科学的不同方面. 面向Python.
* [Big Data Analysis with Scala and Spark (Coursera)](https://www.coursera.org/learn/big-data-analysys)  - 面向 Scala 的入门课程. 部分 [Functional Programming in Scala Specialization](https://www.coursera.org/specializations/scala).

### Workshops

* [AMP Camp](http://ampcamp.berkeley.edu) - 定期举办的培训活动 [UC Berkeley AMPLab](https://amplab.cs.berkeley.edu/) . 有用的练习和记录的研讨会的来源，涵盖了来自 [Berkeley Data Analytics Stack](https://amplab.cs.berkeley.edu/software/).

### Projects Using Spark

* [Oryx 2](https://github.com/OryxProject/oryx) - [Lambda architecture](http://lambda-architecture.net/) 平台建立在 Apache Spark 和 [Apache Kafka](http://kafka.apache.org/) 专门用于实时大规模机器学习.
* [Photon ML](https://github.com/linkedin/photon-ml) - 支持经典广义混合模型和广义加性混合效应模型的机器学习库.
* [PredictionIO](https://prediction.io/) - 机器学习服务器，供开发人员和数据科学家在短时间内构建和部署预测应用程序.
* [Crossdata](https://github.com/Stratio/Crossdata) - 具有扩展数据源 API 和多用户环境的数据集成平台.


### Docker Images

- [apache/spark](https://hub.docker.com/r/apache/spark) - Apache Spark 官方 Docker 图像.
- [jupyter/docker-stacks/pyspark-notebook](https://github.com/jupyter/docker-stacks/tree/master/pyspark-notebook) - 带有 Jupyter Notebook 和 Mesos 客户端的 PySpark.
- [sequenceiq/docker-spark](https://github.com/sequenceiq/docker-spark) - 纱线图像来自 [SequenceIQ](http://www.sequenceiq.com/).
- [datamechanics/spark](https://hub.docker.com/r/datamechanics/spark) - 一个易于设置的 Apache Spark Docker 镜像，来自 [Data Mechanics](https://www.datamechanics.co/).

### Miscellaneous

- [Spark with Scala Gitter channel](https://gitter.im/spark-scala/Lobby) - “_一个讨论和询问有关使用 Scala 进行 Spark 编程的问题的地方_” 开始于 [@deanwampler](https://github.com/deanwampler).
- [Apache Spark User List](http://apache-spark-user-list.1001560.n3.nabble.com/) 和 [Apache Spark Developers List](http://apache-spark-developers-list.1001551.n3.nabble.com/) - Mailing lists dedicated to usage questions 和 development topics respectively.

## References

<p id="wikipedia-2017">维基百科，免费的百科全书.  2017. “Apache Spark — 维基百科，免费的百科全书.”  <a href="https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753" class="uri">https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;age=7</a></p>

## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/publicdomain.svg"
     样式 =“边框样式：无；”  alt=&quot;公共领域标记&quot; /&gt;
</a>
<br />
这项工作（ <span property="dct:title">Awesome Spark</span> ，作者<a href="https://github.com/awesome-spark/awesome-spark" rel="dct:creator">：https://github.com/awesome-spark/awesome-spark</a> ）由<a href="https://github.com/zero323" rel="dct:publisher"><span property="dct:title">Maciej Szymkiewicz</span></a>鉴定，没有已知的版权限制.
</p>

Apache Spark、Spark、Apache 和 Spark<a href="https://www.apache.org/foundation/marks/">徽标</a>是
  <a href="http://www.apache.org">阿帕奇软件基金会</a>. 此汇编未经 Apache 软件基金会认可.


灵感来自 [sindresorhus/awesome](https://github.com/sindresorhus/awesome).
