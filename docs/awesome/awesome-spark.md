<div class="github-widget" data-repo="awesome-spark/awesome-spark"></div>
[<img src="https://cdn.rawgit.com/awesome-spark/awesome-spark/f78a16db/spark-logo-trademark.svg" align="right">](https://spark.apache.org/)

## Awesome Spark [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精彩的精选列表 [Apache Spark](https://spark.apache.org/) 包和资源.

 _Apache Spark是一个开源的集群计算框架.  最初开发于 [University of California](https://www.universityofcalifornia.edu/), [Berkeley's AMPLab](https://amplab.cs.berkeley.edu/)，Spark代码库后来被捐赠给了 [Apache Software Foundation](https://www.apache.org/) 从那以后一直保持着它.  Spark提供了一个用于编程整个集群的接口，具有隐式数据并行性和容错性（[Wikipedia 2017](#wikipedia-2017)).

Apache Spark的用户可以选择不同的Python，R，Scala和Java编程语言来与Apache Spark API进行交互.





## Packages

### Language Bindings


### Notebooks and IDEs

* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/zeppelin.svg"> - 基于Web的笔记本电脑，支持可插拔后端的交互式数据分析，集成绘图以及开箱即用的广泛Spark支持.

### General Purpose Libraries

* [Succinct](http://succinct.cs.berkeley.edu/) <img src="https://img.shields.io/github/last-commit/amplab/succinct.svg">- 支持对压缩数据的有效查询.


### SQL Data Sources


### Bioinformatics


### GIS


### Time Series Analytics


### Graph Processing

* [SparklingGraph](http://sparkling.ml) <img src="https://img.shields.io/github/last-commit/sparkling-graph/sparkling-graph.svg"> - 库扩展GraphX功能，具有多种功能，可用于图形分析（度量，生成器，链接预测等）.

### Machine Learning Extension

* [Apache SystemML](https://systemml.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/systemml.svg"> -  Spark之上的声明式机器学习框架.
* [Mahout Spark Bindings](https://mahout.apache.org/users/sparkbindings/home.html) \ [状态未知\]  - 具有类R语法的线性代数DSL和优化器.
* [KeystoneML](http://keystone-ml.org/) - 使用RDD键入安全的机器学习管道.

### Middleware


### Utilities


### Natural Language Processing

### Streaming

* [Apache Bahir](https://bahir.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/bahir.svg"> - 从Spark 2.0（Akka，MQTT，Twitter.ZeroMQ）中排除的流连接器的集合.

### Interfaces

* [Apache Beam](https://beam.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/beam.svg">   - 统一数据处理引擎，支持批处理和流应用程序.  Apache Spark是受支持的执行环境之一.

### Testing


### Web Archives


### Workflow Management


## Resources

### Books

* [Learning Spark, Lightning-Fast Big Data Analysis](http://shop.oreilly.com/product/0636920028512.do)   - 稍微过时（Spark 1.3）Spark API的介绍.  关于基本概念的良好知识来源.
* [Advanced Analytics with Spark](http://shop.oreilly.com/product/0636920035091.do)   - 有用的Spark处理模式集合.  随附GitHub存储库： [sryza/aas](https://github.com/sryza/aas).
* [Mastering Apache Spark](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/) - 有趣的笔记汇编 [Jacek Laskowski](https://github.com/jaceklaskowski) .  专注于Spark内部的不同方面.
* [Spark Gotchas](https://github.com/awesome-spark/spark-gotchas) - 主观汇编提示，技巧和常见的编程错误.

### Papers

* [Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://people.csail.mit.edu/matei/papers/2012/nsdi_spark.pdf) - 介绍核心分布式内存抽象的论文.

### MOOCS

* [Data Science and Engineering with Apache Spark (edX XSeries)](https://www.edx.org/xseries/data-science-engineering-apache-spark) - 五门系列课程（[Introduction to Apache Spark](https://www.edx.org/course/introduction-apache-spark-uc-berkeleyx-cs105x), [Distributed Machine Learning with Apache Spark](https://www.edx.org/course/distributed-machine-learning-apache-uc-berkeleyx-cs120x), [Big Data Analysis with Apache Spark](https://www.edx.org/course/big-data-analysis-apache-spark-uc-berkeleyx-cs110x), [Advanced Apache Spark for Data Science and Data Engineering](https://www.edx.org/course/advanced-apache-spark-data-science-data-uc-berkeleyx-cs115x), [Advanced Distributed Machine Learning with Apache Spark](https://www.edx.org/course/advanced-distributed-machine-learning-uc-berkeleyx-cs125x) ）涵盖软件工程和数据科学的不同方面.  面向Python.
* [Big Data Analysis with Scala and Spark (Coursera)](https://www.coursera.org/learn/big-data-analysys)   -  Scala导向的入门课程.  部分 [Functional Programming in Scala Specialization](https://www.coursera.org/specializations/scala).

### Workshops

* [AMP Camp](http://ampcamp.berkeley.edu) - 由学校组织的定期培训活动 [UC Berkeley AMPLab](https://amplab.cs.berkeley.edu/) .  有用的练习来源和记录的研讨会，涵盖了不同的工具 [Berkeley Data Analytics Stack](https://amplab.cs.berkeley.edu/software/).

### Projects Using Spark

* [Oryx 2](https://github.com/OryxProject/oryx) - [Lambda architecture](http://lambda-architecture.net/) 基于Apache Spark和 [Apache Kafka](http://kafka.apache.org/) 专业实时大规模机器学习.
* [Photon ML](https://github.com/linkedin/photon-ml) - 支持经典广义混合模型和广义加性混合效应模型的机器学习库.
* [PredictionIO](https://prediction.io/) - 机器学习服务器，供开发人员和数据科学家在很短的时间内构建和部署预测应用程序.
* [Crossdata](https://github.com/Stratio/Crossdata) - 具有扩展DataSource API和多用户环境的数据集成平台.

### Blogs

- [Spark Technology Center](http://spark.tc/blog/)   - 与Spark生态系统相关的高度多样化职位的重要来源.  从实用建议到Spark commiter配置文件.

### Docker Images

- [jupyter/docker-stacks/pyspark-notebook](https://github.com/jupyter/docker-stacks/tree/master/pyspark-notebook) -  PySpark与Jupyter Notebook和Mesos客户端.
- [sequenceiq/docker-spark](https://github.com/sequenceiq/docker-spark) - 来自的纱线图像 [SequenceIQ](http://www.sequenceiq.com/).

### Miscellaneous

- [Spark with Scala Gitter channel](https://gitter.im/spark-scala/Lobby) - “_一个讨论并提出有关使用Scala进行Spark编程的问题的地方”，开始于 [@deanwampler](https://github.com/deanwampler).
- [Apache Spark User List](http://apache-spark-user-list.1001560.n3.nabble.com/) 和 [Apache Spark Developers List](http://apache-spark-developers-list.1001551.n3.nabble.com/) - Mailing lists dedicated to usage questions 和 development topics respectively.

## References

<p id="wikipedia-2017">  维基百科.  2017.“Apache Spark  - 维基百科，自由百科全书.” <a href="https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753" class="uri">https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753</a> . </p>

## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/publicdomain.svg"
      style =“border-style：none;”  alt =“公共域标记”/&gt;
</a>
<br />
由<a href="https://github.com/zero323" rel="dct:publisher"><span property="dct:title">Maciej Szymkiewicz</span></a>识别的这项工作（ <span property="dct:title">Awesome Spark</span> ，由<a href="https://github.com/awesome-spark/awesome-spark" rel="dct:creator">https://github.com/awesome-spark/awesome-spark提供</a> ）没有已知的版权限制.
</p>

Apache Spark，Spark，Apache和Spark徽标是其<a href="https://www.apache.org/foundation/marks/">商标</a>
   <a href="http://www.apache.org">Apache软件基金会</a> .  此编译未得到Apache Software Foundation的认可.


灵感来自 [sindresorhus/awesome](https://github.com/sindresorhus/awesome).
