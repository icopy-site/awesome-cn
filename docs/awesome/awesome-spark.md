<div class="github-widget" data-repo="awesome-spark/awesome-spark"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
[<img src="https://cdn.rawgit.com/awesome-spark/awesome-spark/f78a16db/spark-logo-trademark.svg" align="right">](https://spark.apache.org/)

## Awesome Spark [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的超赞清单 [Apache Spark](https://spark.apache.org/) 包和资源.

 _Apache Spark是一个开放源代码群集计算框架. 最初开发于 [University of California](https://www.universityofcalifornia.edu/), [Berkeley's AMPLab](https://amplab.cs.berkeley.edu/)，后来将Spark代码库捐赠给了 [Apache Software Foundation](https://www.apache.org/) ，此后一直保持.  Spark提供了一个接口，用于使用隐式数据并行性和Fault-tolerance_（[Wikipedia 2017](#wikipedia-2017)).

Apache Spark的用户可以选择不同的Python，R，Scala和Java编程语言来与Apache Spark API进行接口.





## Packages

### Language Bindings


### Notebooks and IDEs
* [almond](https://almond.sh/) <img src="https://img.shields.io/github/last-commit/almond-sh/almond.svg"> -用于的scala内核 [Jupyter](https://jupyter.org/).
* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/zeppelin.svg"> -基于Web的笔记本电脑，可通过即插即用的后端，集成绘图和广泛的Spark支持进行交互式数据分析.
* [Polynote](https://polynote.org/)  <img src="https://img.shields.io/github/last-commit/polynote/polynote.svg">  -Polynote：灵感来自IDE的多国语言笔记本. 它支持在一个笔记本中混合多种语言，并在它们之间无缝共享数据. 它通过不可变的数据模型鼓励可复制的笔记本电脑. 始于 [Netflix](https://medium.com/netflix-techblog/open-sourcing-polynote-an-ide-inspired-polyglot-notebook-7f929d3f447).

### General Purpose Libraries

* [Succinct](http://succinct.cs.berkeley.edu/) <img src="https://img.shields.io/github/last-commit/amplab/succinct.svg">-支持对压缩数据进行有效查询.


### SQL Data Sources

SparkSQL有 [serveral built-in Data Sources](https://spark.apache.org/docs/latest/sql-data-sources-load-save-functions.html#manually-specifying-options) 用于文件. 这些包括`csv`，`json`，`parquet`，`orc`和`avro`. 它还支持JDBC数据库以及Apache Hive. 可以通过包括以下列出的软件包或编写自己的软件包来添加其他数据源. 


### Storage


### Bioinformatics


### GIS


### Time Series Analytics


### Graph Processing

* [SparklingGraph](http://sparkling.ml) <img src="https://img.shields.io/github/last-commit/sparkling-graph/sparkling-graph.svg"> -扩展了GraphX功能的库，具有多种功能，可用于图形分析（度量，生成器，链接预测等）.

### Machine Learning Extension
* [Apache SystemML](https://systemml.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/systemml.svg"> -在Spark之上的声明性机器学习框架.
* [Mahout Spark Bindings](https://mahout.apache.org/users/sparkbindings/home.html) \ [状态未知\]-具有类似R语法的线性代数DSL和优化器.
* [KeystoneML](http://keystone-ml.org/) -使用RDD键入安全的机器学习管道.

### Middleware


### Utilities


### Natural Language Processing

### Streaming

* [Apache Bahir](https://bahir.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/bahir.svg"> -从Spark 2.0（Akka，MQTT，Twitter.ZeroMQ）中排除的流连接器的集合.

### Interfaces

* [Apache Beam](https://beam.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/beam.svg">  -支持批处理和流应用程序的统一数据处理引擎.  Apache Spark是受支持的执行环境之一.

### Testing


### Web Archives


### Workflow Management


## Resources

### Books

* [Learning Spark, Lightning-Fast Big Data Analysis](http://shop.oreilly.com/product/0636920028512.do)  -Spark API的过时介绍（Spark 1.3）. 有关基本概念的丰富知识来源.
* [Advanced Analytics with Spark](http://shop.oreilly.com/product/0636920035091.do)  -有用的Spark处理模式集合. 随附的GitHub存储库： [sryza/aas](https://github.com/sryza/aas).
* [Mastering Apache Spark](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/) -有趣的笔记汇编 [Jacek Laskowski](https://github.com/jaceklaskowski) . 专注于Spark内部的不同方面.
* [Spark Gotchas](https://github.com/awesome-spark/spark-gotchas) -提示，技巧和常见编程错误的主观汇编.

### Papers

* [Large-Scale Intelligent Microservices](https://arxiv.org/pdf/2009.08044.pdf) -Microsoft的论文，提出了一个基于Apache Spark的微服务编排框架，该框架将数据库操作扩展到包括Web服务原语.
* [Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://people.csail.mit.edu/matei/papers/2012/nsdi_spark.pdf) -介绍核心分布式内存抽象的论文.
* [结构化流：实时的声明性API
 Apache Spark中的应用程序]（https://cs.stanford.edu/~matei/papers/2018/sigmod_structured_streaming.pdf）-结构化流是一种新的高级流API，它是基于自动递增静态变量的声明性API关系查询.

### MOOCS

* [Data Science and Engineering with Apache Spark (edX XSeries)](https://www.edx.org/xseries/data-science-engineering-apache-spark) -系列五门课程（[Introduction to Apache Spark](https://www.edx.org/course/introduction-apache-spark-uc-berkeleyx-cs105x), [Distributed Machine Learning with Apache Spark](https://www.edx.org/course/distributed-machine-learning-apache-uc-berkeleyx-cs120x), [Big Data Analysis with Apache Spark](https://www.edx.org/course/big-data-analysis-apache-spark-uc-berkeleyx-cs110x), [Advanced Apache Spark for Data Science and Data Engineering](https://www.edx.org/course/advanced-apache-spark-data-science-data-uc-berkeleyx-cs115x), [Advanced Distributed Machine Learning with Apache Spark](https://www.edx.org/course/advanced-distributed-machine-learning-uc-berkeleyx-cs125x) ），涵盖软件工程和数据科学的不同方面. 面向Python.
* [Big Data Analysis with Scala and Spark (Coursera)](https://www.coursera.org/learn/big-data-analysys)  -面向Scala的入门课程. 部分 [Functional Programming in Scala Specialization](https://www.coursera.org/specializations/scala).

### Workshops

* [AMP Camp](http://ampcamp.berkeley.edu) -定期举办的培训活动 [UC Berkeley AMPLab](https://amplab.cs.berkeley.edu/) . 有用的练习来源和录制的讲习班，涵盖了来自 [Berkeley Data Analytics Stack](https://amplab.cs.berkeley.edu/software/).

### Projects Using Spark

* [Oryx 2](https://github.com/OryxProject/oryx) - [Lambda architecture](http://lambda-architecture.net/) 基于Apache Spark和 [Apache Kafka](http://kafka.apache.org/) 专门用于实时大规模机器学习.
* [Photon ML](https://github.com/linkedin/photon-ml) -支持经典广义混合模型和广义加性混合效应模型的机器学习库.
* [PredictionIO](https://prediction.io/) -面向开发人员和数据科学家的机器学习服务器，可以在短时间内构建和部署预测性应用程序.
* [Crossdata](https://github.com/Stratio/Crossdata) -具有扩展的DataSource API和多用户环境的数据集成平台.

### Blogs

- [Spark Technology Center](http://spark.tc/blog/)  -与Spark生态系统相关的高度多样化帖子的重要来源. 从实用建议到Spark提交者个人资料.

### Docker Images

- [jupyter/docker-stacks/pyspark-notebook](https://github.com/jupyter/docker-stacks/tree/master/pyspark-notebook) -具有Jupyter Notebook和Mesos客户端的PySpark.
- [sequenceiq/docker-spark](https://github.com/sequenceiq/docker-spark) -来自的纱线图像 [SequenceIQ](http://www.sequenceiq.com/).

### Miscellaneous

- [Spark with Scala Gitter channel](https://gitter.im/spark-scala/Lobby) -“ _有关使用Scala进行Spark编程的讨论和提问场所_” [@deanwampler](https://github.com/deanwampler).
- [Apache Spark User List](http://apache-spark-user-list.1001560.n3.nabble.com/) 和 [Apache Spark Developers List](http://apache-spark-developers-list.1001551.n3.nabble.com/) - Mailing lists dedicated to usage questions 和 development topics respectively.

## References

<p id="wikipedia-2017">维基百科.  2017年.“ Apache Spark-Wikipedia，免费百科全书”.  <a href="https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753" class="uri">https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753</a> .</p>

## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/publicdomain.svg"
     style="border-style: none;" alt="Public Domain Mark" />
</a>
<br />
由<a href="https://github.com/zero323" rel="dct:publisher"><span property="dct:title">Maciej Szymkiewicz</span></a>识别的这项工作（ <span property="dct:title">Awesome Spark</span> ， <a href="https://github.com/awesome-spark/awesome-spark" rel="dct:creator">https：//github.com/awesome-spark/awesome-spark</a> ）不受已知的版权限制.
</p>

Apache Spark，Spark，Apache和Spark徽标是的<a href="https://www.apache.org/foundation/marks/">商标</a>
   <a href="http://www.apache.org">Apache软件基金会</a>. 该编译未得到Apache软件基金会的认可.


受启发 [sindresorhus/awesome](https://github.com/sindresorhus/awesome).
