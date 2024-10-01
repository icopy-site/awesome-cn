<div class="github-widget" data-repo="awesome-spark/awesome-spark"></div>
[<img src="https://cdn.rawgit.com/awesome-spark/awesome-spark/f78a16db/spark-logo-trademark.svg" align="right">](https://spark.apache.org/)

## Awesome Spark [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome [Apache Spark](https://spark.apache.org/) packages and resources.

_Apache Spark is an open-source cluster-computing framework. Originally developed at the [University of California](https://www.universityofcalifornia.edu/), [Berkeley's AMPLab](https://amplab.cs.berkeley.edu/), the Spark codebase was later donated to the [Apache Software Foundation](https://www.apache.org/), which has maintained it since. Spark provides an interface for programming entire clusters with implicit data parallelism and fault-tolerance_  ([Wikipedia 2017](#wikipedia-2017)).

Users of Apache Spark may choose between different the Python, R, Scala and Java programming languages to interface with the Apache Spark APIs.

## Packages

### Language Bindings


### Notebooks and IDEs
* [almond](https://almond.sh/) <img src="https://img.shields.io/github/last-commit/almond-sh/almond.svg"> - A scala kernel for [Jupyter](https://jupyter.org/).
* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/zeppelin.svg"> - Web-based notebook that enables interactive data analytics with plugable backends, integrated plotting, and extensive Spark support out-of-the-box.
* [Polynote](https://polynote.org/)  <img src="https://img.shields.io/github/last-commit/polynote/polynote.svg"> - Polynote: an IDE-inspired polyglot notebook. It supports mixing multiple languages in one notebook, and sharing data between them seamlessly. It encourages reproducible notebooks with its immutable data model. Originating from [Netflix](https://medium.com/netflix-techblog/open-sourcing-polynote-an-ide-inspired-polyglot-notebook-7f929d3f447).

### General Purpose Libraries


### SQL Data Sources

SparkSQL has [serveral built-in Data Sources](https://spark.apache.org/docs/latest/sql-data-sources-load-save-functions.html#manually-specifying-options) for files. These include `csv`, `json`, `parquet`, `orc`, and `avro`. It also supports JDBC databases as well as Apache Hive. Additional data sources can be added by including the packages listed below, or writing your own.


### Storage

* [lakeFS](https://docs.lakefs.io/integrations/spark.html) <img src="https://img.shields.io/github/last-commit/treeverse/lakefs.svg"> - Integration with the lakeFS atomic versioned storage layer.

### Bioinformatics


### GIS


### Graph Processing


### Machine Learning Extension

* [Apache SystemML](https://systemml.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/systemml.svg"> - Declarative machine learning framework on top of Spark.
* [Mahout Spark Bindings](https://mahout.apache.org/users/sparkbindings/home.html) \[status unknown\] - linear algebra DSL and optimizer with R-like syntax.
* [KeystoneML](http://keystone-ml.org/) - Type safe machine learning pipelines with RDDs.
* [MLflow](https://mlflow.org/docs/latest/python_api/mlflow.spark.html#module-mlflow.spark) <img src="https://img.shields.io/github/last-commit/mlflow/mlflow.svg"> - Machine learning orchestration platform. 

### Middleware


### Monitoring


### Utilities


### Natural Language Processing


### Streaming

* [Apache Bahir](https://bahir.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/bahir.svg"> - Collection of the streaming connectors excluded from Spark 2.0 (Akka, MQTT, Twitter. ZeroMQ).

### Interfaces

* [Apache Beam](https://beam.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/beam.svg"> - Unified data processing engine supporting both batch and streaming applications. Apache Spark is one of the supported execution environments.

### Testing


### Web Archives


### Workflow Management


## Resources

### Books

* [Learning Spark, 2nd Edition](https://www.oreilly.com/library/view/learning-spark-2nd/9781492050032/) - Introduction to Spark API with Spark 3.0 covered. Good source of knowledge about basic concepts.
* [Advanced Analytics with Spark](http://shop.oreilly.com/product/0636920035091.do) - Useful collection of Spark processing patterns. Accompanying GitHub repository: [sryza/aas](https://github.com/sryza/aas).
* [Mastering Apache Spark](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/) - Interesting compilation of notes by [Jacek Laskowski](https://github.com/jaceklaskowski). Focused on different aspects of Spark internals.

### Papers

* [Large-Scale Intelligent Microservices](https://arxiv.org/pdf/2009.08044.pdf) - Microsoft paper that presents an Apache Spark-based micro-service orchestration framework that extends database operations to include web service primitives.
* [Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://people.csail.mit.edu/matei/papers/2012/nsdi_spark.pdf) - Paper introducing a core distributed memory abstraction.
* [Structured Streaming: A Declarative API for Real-Time Applications in Apache Spark](https://cs.stanford.edu/~matei/papers/2018/sigmod_structured_streaming.pdf) - Structured Streaming is a new high-level streaming API, it is a declarative API based on automatically incrementalizing a static relational query.

### MOOCS

* [Data Science and Engineering with Apache Spark (edX XSeries)](https://www.edx.org/xseries/data-science-engineering-apache-spark) - Series of five courses ([Introduction to Apache Spark](https://www.edx.org/course/introduction-apache-spark-uc-berkeleyx-cs105x), [Distributed Machine Learning with Apache Spark](https://www.edx.org/course/distributed-machine-learning-apache-uc-berkeleyx-cs120x), [Big Data Analysis with Apache Spark](https://www.edx.org/course/big-data-analysis-apache-spark-uc-berkeleyx-cs110x), [Advanced Apache Spark for Data Science and Data Engineering](https://www.edx.org/course/advanced-apache-spark-data-science-data-uc-berkeleyx-cs115x), [Advanced Distributed Machine Learning with Apache Spark](https://www.edx.org/course/advanced-distributed-machine-learning-uc-berkeleyx-cs125x)) covering different aspects of software engineering and data science. Python oriented.
* [Big Data Analysis with Scala and Spark (Coursera)](https://www.coursera.org/learn/big-data-analysys) - Scala oriented introductory course. Part of [Functional Programming in Scala Specialization](https://www.coursera.org/specializations/scala).

### Workshops

* [AMP Camp](http://ampcamp.berkeley.edu) - Periodical training event organized by the [UC Berkeley AMPLab](https://amplab.cs.berkeley.edu/). A source of useful exercise and recorded workshops covering different tools from the [Berkeley Data Analytics Stack](https://amplab.cs.berkeley.edu/software/).

### Projects Using Spark

* [Oryx 2](https://github.com/OryxProject/oryx) - [Lambda architecture](http://lambda-architecture.net/) platform built on Apache Spark and [Apache Kafka](http://kafka.apache.org/) with specialization for real-time large scale machine learning.
* [Photon ML](https://github.com/linkedin/photon-ml) - A machine learning library supporting classical Generalized Mixed Model and Generalized Additive Mixed Effect Model.
* [PredictionIO](https://prediction.io/) - Machine Learning server for developers and data scientists to build and deploy predictive applications in a fraction of the time.
* [Crossdata](https://github.com/Stratio/Crossdata) - Data integration platform with extended DataSource API and multi-user environment.


### Docker Images

- [apache/spark](https://hub.docker.com/r/apache/spark) - Apache Spark Official Docker images.
- [jupyter/docker-stacks/pyspark-notebook](https://github.com/jupyter/docker-stacks/tree/master/pyspark-notebook) - PySpark with Jupyter Notebook and Mesos client.
- [sequenceiq/docker-spark](https://github.com/sequenceiq/docker-spark) - Yarn images from [SequenceIQ](http://www.sequenceiq.com/).
- [datamechanics/spark](https://hub.docker.com/r/datamechanics/spark) - An easy to setup Docker image for Apache Spark from [Data Mechanics](https://www.datamechanics.co/).

### Miscellaneous

- [Spark with Scala Gitter channel](https://gitter.im/spark-scala/Lobby) - "_A place to discuss and ask questions about using Scala for Spark programming_" started by [@deanwampler](https://github.com/deanwampler).
- [Apache Spark User List](http://apache-spark-user-list.1001560.n3.nabble.com/) and [Apache Spark Developers List](http://apache-spark-developers-list.1001551.n3.nabble.com/) - Mailing lists dedicated to usage questions and development topics respectively.

## References

<p id="wikipedia-2017">Wikipedia. 2017. “Apache Spark — Wikipedia, the Free Encyclopedia.” <a href="https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753" class="uri">https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753</a>.</p>

## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/publicdomain.svg"
     style="border-style: none;" alt="Public Domain Mark" />
</a>
<br />
This work (<span property="dct:title">Awesome Spark</span>, by <a href="https://github.com/awesome-spark/awesome-spark" rel="dct:creator">https://github.com/awesome-spark/awesome-spark</a>), identified by <a href="https://github.com/zero323" rel="dct:publisher"><span property="dct:title">Maciej Szymkiewicz</span></a>, is free of known copyright restrictions.
</p>

Apache Spark, Spark, Apache, and the Spark logo are <a href="https://www.apache.org/foundation/marks/">trademarks</a> of
  <a href="http://www.apache.org">The Apache Software Foundation</a>. This compilation is not endorsed by The Apache Software Foundation.

Inspired by [sindresorhus/awesome](https://github.com/sindresorhus/awesome).
