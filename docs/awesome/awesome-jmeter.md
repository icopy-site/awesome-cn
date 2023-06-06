<div class="github-widget" data-repo="aliesbelik/awesome-jmeter"></div>
## Awesome JMeter [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!--lint ignore double-link-->
精选的资源集合，涵盖 [Apache JMeter](https://jmeter.apache.org/) 以及相关的东西和闪亮的东西：插件、集成、测试技术、DevOps 实践等.

<!--lint ignore double-link-->
[<img src="https://raw.githubusercontent.com/aliesbelik/awesome-jmeter/master/assets/images/jmeter-logo.svg?sanitize=true" align="right" width="260" alt="Apache JMeter">](https://jmeter.apache.org/)

<!--lint ignore double-link-->
> [Apache JMeter](https://jmeter.apache.org/) 是开源的纯 Java 应用程序，旨在加载测试功能行为和测量性能.

<!--lint ignore double-link-->
这个列表来自 [an occasional answer](https://sqa.stackexchange.com/a/2552/1842) 在 Stack Exchange 和个人 JMeter 相关链接集合上，从中获得了进一步的灵感 [awesome](https://github.com/sindresorhus/awesome) 项目并通过这些改进 [amazing contributors](https://github.com/aliesbelik/awesome-jmeter/blob/master/CONTRIBUTORS.md).


<!--lint ignore double-link-->

## Official Resources

<!--lint ignore double-link-->
- [Apache JMeter Project](https://jmeter.apache.org/) - Apache JMeter 官方网站.
- [GitHub Repository](https://github.com/apache/jmeter) - Apache JMeter 源代码存储库.
- [JMeter Wiki](https://cwiki.apache.org/confluence/display/jmeter) - Apache JMeter 官方文档.
- [Issue Tracking](https://jmeter.apache.org/issues.html) - Apache JMeter 问题跟踪系统.
- [Mailing Lists](https://jmeter.apache.org//mail2.html) - Apache JMeter 邮件列表.

## Distributions

- [Download Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi) - Apache JMeter：官方下载.
- [JMeter for Windows](https://sourceforge.net/projects/jmeterforwindows/) - 带插件的 JMeter 安装包.
- [JMeter Bootstrap](https://github.com/cfpb/jmeter-bootstrap) - 设置 JMeter 和 JMeter 插件的解决方案，适合用作子模块.

## Getting Started

- [Getting Started with Apache JMeter](https://dzone.com/refcardz/getting-started-with-apache-jmeter)
- [The Beginner's Guide to Performance Testing with Apache JMeter](https://betterprogramming.pub/the-beginners-guide-to-performance-testing-with-apache-jmeter-5cc52c327ff6)
- JMeter — 性能和负载测试：初学者指南： [part 1](https://ekremkurt1907.medium.com/jmeter-performance-and-load-testing-beginners-guide-part-i-5121604bf97a), [part 2](https://ekremkurt1907.medium.com/jmeter-performance-and-load-testing-beginners-guide-part-ii-7edb98b0d2c3)

## Tutorials

- [JMeter Tutorial](https://artoftesting.com/jmeter-tutorial) - 通过 ArtOfTesting.
- 使用 JMeter 进行负载测试： [part 1](https://lincolnloop.com/insights/2011/sep/21/load-testing-jmeter-part-1-getting-started/), [part 2](https://lincolnloop.com/insights/2011/oct/12/load-testing-jmeter-part-2-headless-testing-and-je/), [part 3](https://lincolnloop.com/insights/2012/sep/19/load-testing-jmeter-part-3-replaying-apache-logs/) - 布兰登·康克尔 (Brandon Konkle).
- [JMeter Resources](https://resources.infosecinstitute.com/?s=jmeter) - 德扬·卢坎 (Dejan Lukan).
- [JMeter Tutorial](https://www.tutorialspoint.com/jmeter/) - By Tutorials Point.
- [JMeter Tutorial for Load Testing: The Ultimate Guide](https://www.javacodegeeks.com/2014/11/jmeter-tutorial-load-testing.html) - 丹尼尔·古铁雷斯·迪兹 (Daniel Gutierrez Diez).
- [JMeter: Load Development Lifecycle](https://datacadamia.com/jmeter/lifecycle) - 通过 DataCadamia.
- [Load Testing with Apache JMeter](https://www.digitalocean.com/community/tutorial_series/load-testing-with-apache-jmeter) - 作者：Mitchell Anicas @ DigitalOcean.
- [JMeter Tutorial for Beginners](https://www.guru99.com/jmeter-tutorials.html) - Guru99.

## Best Practices

- [JMeter Official Best Practices](https://jmeter.apache.org/usermanual/best-practices.html)
- [Optimize JMeter for Large Scale Tests](https://octoperf.com/blog/2017/10/12/optimize-jmeter-for-large-scale-tests/)
- [Concurrent, High Throughput Performance Testing with JMeter](https://howtojboss.wordpress.com/2012/07/31/concurrent-high-throughput-performance-testing-with-jmeter/)

## Scripting

- [Beanshell vs JSR223 vs Java JMeter Scripting](https://www.blazemeter.com/blog/beanshell-vs-jsr223-vs-jmeter) - 最流行的脚本机制性能比较.
- [Testing with Groovy](https://static.packt-cdn.com/downloads/Testingwithgroovy.pdf) - 使用 JMeter 和 Groovy 进行负载测试.

## Automation

### DSL

- [Ruby-JMeter](https://github.com/flood-io/ruby-jmeter) - 用于构建 JMeter 测试计划的基于 Ruby 的 DSL.
- [jmeter-java-dsl](https://abstracta.github.io/jmeter-java-dsl/) - 以 VCS 和程序员友好的方式运行 JMeter 性能测试的简单 API.
- [jmeter-groovy-dsl](https://github.com/smicyk/groovy-jmeter) - Groovy-JMeter 项目是用于编写 JMeter 测试计划的简单 DSL.
- [jmeter-as-code](https://github.com/anasoid/jmeter-as-code) - JMeter 的简单包装器，用于使用 Java 编写和执行 JMeter 测试.
- [pymeter](https://github.com/eldaduzman/pymeter) - 用于 Python 的简单 JMeter 性能测试 API.

### Packages

- [loadtest](https://github.com/tmobile/loadtest) - 使用 JMeter 进行负载测试的 R 包.

### Frameworks

- [Taurus](https://gettaurus.org/) - 用于连续测试的自动化友好框架.
- [Performance testing framework](https://github.com/serputko/performance-testing-framework) - 使用 Apache JMeter 进行后端负载测试和使用 sitespeed.io + webpagetest 私有实例进行前端负载测试的框架.
- [JMeter Load Testing Center](https://github.com/innogames/ltc) - 使用 JMeter 运行、监控和分析负载测试结果的在线网络应用程序/仪表板.
- [MeterSphere](https://github.com/metersphere/metersphere/blob/main/README-EN.md) - 一站式开源企业级持续测试平台，兼容JMeter:cn:等开源标准.
- [Carrier](https://getcarrier.io/) - 连续测试执行平台，能够使用定制的 JMeter 和 Gatling 容器执行负载测试.

### Conversion

- [swaggerjmx](https://github.com/Pactortester/swaggerjmx) - 将 Swagger UI 规范转换为 JMeter 测试计划的工具.
- [postman2jmx](https://github.com/Loadium/postman2jmx) - Postman 集合到 JMeter jmx 文件转换器.
- [convert-postman-jmeter](https://github.com/sercheo87/convert-postman-jmeter) - 将 Postman 项目转换为 JMeter.

## CI

### Tools & Plugins

- [JMeter Ant Task](https://github.com/jfifield/ant-jmeter) - 自动运行 JMeter 测试计划的 Ant 任务.
- [JMeter Maven Plugin](https://github.com/jmeter-maven-plugin/jmeter-maven-plugin) - Maven 插件，提供在构建过程中运行 JMeter 测试的能力.
- [JMeter Gradle Plugin](https://github.com/jmeter-gradle-plugin/jmeter-gradle-plugin) - 用于执行 JMeter 测试的 Gradle 插件.
- [Jenkins Performance Plugin](https://plugins.jenkins.io/performance/) - Jenkins 插件，用于从 JMeter 捕获报告并生成具有性能和稳健性趋势报告的图表.
- [TeamCity Performance Tests Analysis Plugin](https://github.com/jtorgan/jmeter_plugin) - 在 CI 中组织最简单的性能测试的 TeamCity 插件.
- [Bamboo JMeter Aggregator Plugin](https://marketplace.atlassian.com/apps/5902/jmeter-aggregator-for-bamboo) - 用于收集、断言和绘制 JMeter 测试结果的 Bamboo 插件.
- [Sonar JMeter Plugin](https://github.com/SonarQubeCommunity/sonar-jmeter) - 用于收集 JMeter 性能测试结果并显示在 Sonar 仪表板中的插件.
- [Lightning](https://automatictester.github.io/lightning/) - 将 JMeter 非功能测试与 CI/CD 服务器集成的框架.
- [Taurus JMeter Executor](https://gettaurus.org/docs/JMeter/) - Taurus 自动化框架中的 JMeter 执行器.
- [PerfAction for JMeter](https://github.com/marketplace/actions/perfaction-for-jmeter) - GitHub Action 使用 Apache JMeter 及其插件运行性能测试.
- [Apache JMeter GitHub Action](https://github.com/marketplace/actions/apache-jmeter) - 用于执行 Apache JMeter 性能测试的 GitHub Action.

### Tutorials & Demo

- 詹金斯
  - [Performance Tests with JMeter, Maven and Hudson](https://blog.theserverlabs.com/performance-tests-with-jmeter-maven-and-hudson-d1cbdb3ffad8)
  - [CI with Jenkins, Git, Maven, Grunt, and JMeter](https://github.com/dzuluagaapigee/apigee-ci-jenkins-git-maven-jmeter)
  - [Continuous automated web tests using Jenkins and JMeter](https://www.linkedin.com/pulse/continuous-automated-web-tests-using-jenkins-jmeter-mahanta)
  - [Automating JMeter tests with Maven and Jenkins](https://www.codecentric.de/wissens-hub/blog/automating-jmeter-tests-maven-jenkins)
  - 如何使用 Maven 和 Jenkins 自动化 JMeter 测试： [part 1](https://ribblescode.wordpress.com/2012/04/16/how-to-run-jmeter-tests-with-maven/), [part 2](https://ribblescode.wordpress.com/2012/04/16/how-to-automate-jmeter-tests-with-maven-and-jenkins-hudson-8/)
  - JMeter 连续性能测试（JMeter + Ant + Jenkins）： [part 1](https://www.testautomationguru.com/jmeter-continuous-performance-testing-part1/), [part 2](https://www.testautomationguru.com/jmeter-continuous-performance-testing-part2/)
  - [Continuous Integration 101: How to Run JMeter with Jenkins](https://dzone.com/articles/continuous-integration-101-how-to-run-jmeter-with)
- 竹子
  - [How to Run JMeter in a Continuous Integration Environment with Bamboo](https://dzone.com/articles/how-to-run-jmeter-in-a-continuous-integration-envi)
- 团队城市
  - [How to Run JMeter Tests with TeamCity for Continuous Integration](https://web.archive.org/web/20211204112944/https://www.blazemeter.com/blog/how-run-jmeter-tests-teamcity-continuous-integration/)
-CircleCI
  - [How to integrate JMeter into CircleCI](https://www.blazemeter.com/blog/circleci-jmeter)
- 声纳管
  - [JMeter with Sonar](https://testersinaction.blogspot.com/2013/05/v-behaviorurldefaultvmlo_24.html)

## Distributed Testing

- [JMeter Distributed Testing Step-by-step](https://jmeter.apache.org/usermanual/jmeter_distributed_testing_step_by_step.pdf)
- [JMeter Remote Testing](https://jmeter.apache.org/usermanual/remote-test.html)
- [Setting up a JMeter Cluster for web server load testing](https://www.howtoforge.com/setting-up-jmeter-cluster-for-load-testing/)
- 码头化
  - [Dockerized JMeter](https://gist.github.com/hhcordero/abd1dcaf6654cfe51d0b) - 使用 Docker 和 JMeter 的分布式负载测试工作流程.
  - [JMeter Docker Images](https://hub.docker.com/search/?isAutomated=0&isOfficial=0&page=1&pullCount=0&q=jmeter&starCount=0)
  - [Distributed JMeter testing using Docker](https://srivaths.blogspot.com/2014/08/distrubuted-jmeter-testing-using-docker.html)
  - [A Docker solution to JMeter + InfluxDB + Grafana performance testing](https://medium.com/@ellenhuang523/a-docker-solution-to-jmeter-influxdb-grafana-performance-testing-568848de7a0f)
  - [AutoMeter](https://github.com/intuit/autometer) - 基于 JMeter 主从架构的使用分布式从站扩展负载测试的自动化工具.
- 云端测试
  - 库伯内斯
    - [jmeter-kubernetes](https://github.com/kubernauts/jmeter-kubernetes) - JMeter 集群支持 Kubernetes 和 OpenShift.
    - [jmeter-k8s-starterkit](https://github.com/Rbillon59/jmeter-k8s-starterkit) - JMeter k8s 入门套件，具有实时测试报告、JMeter 监控、k8s 监控和模拟服务.
    - [kangal](https://github.com/hellofresh/kangal) - Kubernetes 和 Go Automatic Loader 解决方案，使用多个负载生成器在 Kubernetes 集群中运行性能测试.
    - [aks_testing_fwk](https://github.com/petegrimsdale/aks_testing_fwk) - 基于 AKS 的可扩展 JMeter 测试框架，带有 Grafana 报告.
  - 亚马逊网络服务
    - [jmeter-ec2](https://github.com/oliverlloyd/jmeter-ec2/) - 在 Amazon EC2 上自动运行 Apache JMeter.
    - [gee](https://github.com/kowalcj0/gee) - JMeter-EC2 项目的修改版本.
    - [os-jmeter-aws](https://github.com/Aptimyze/os-jmeter-aws) - 在多个 Amazon EC2 实例上运行 JMeter，在 ELK 中查看结果.
    - [Load Testing with JMeter and Amazon EC2](https://medium.com/@alttaf/load-testing-with-jmeter-and-amazon-ec2-e143a7350596)
    - [Performance Testing in the Cloud with JMeter & AWS](http://web.archive.org/web/20190526033436/http://www.artofsoftwaredevelopment.com/performance/performance-testing-in-the-cloud-with-jmeter-aws)
    - [JMeter distributed testing with Amazon EC2](https://vedovini.net/2009/08/17/jmeter-distributed-testing-with-amazon-ec2/)
    - [jmeter-ecs](https://github.com/smithmicro/jmeter-ecs) - 用于在 EC2 容器服务 (ECS) 上进行分布式测试的 JMeter docker 镜像.
  - 数字海洋
    - [Lightweight JMeter Cloud](https://docs.google.com/presentation/d/1Yi5C27C3Q0AnT-uw9SRnMeEqXSKLQ8h9O9Jqo1gQiyI/) - 使用 DigitalOcean、JMeter 和 Docker 构建您自己的 JMeter Cloud.
  - 微软Azure
    - [Load Testing Pipeline with JMeter, ACI and Terraform](https://github.com/Azure-Samples/jmeter-aci-terraform) - 可扩展的云负载/压力测试管道解决方案，使用 Apache JMeter 和 Terraform 来动态配置和销毁 Azure 上所需的基础设施.

## Cloud Services / SaaS

*支持 JMeter 测试计划执行的基于云的负载测试服务列表.*

- [Perforce BlazeMeter](https://www.blazemeter.com/) - 支持 JMeter 和 Selenium 的性能工程平台.
- [OctoPerf](https://octoperf.com/) - 支持 JMeter 和 Selenium 的 SaaS 和本地负载测试工具.
- [Tricentis Flood](https://www.flood.io/) - 支持 JMeter、Gatling 和 Selenium 场景的负载测试服务.
- [RedLine13](https://redline13.com/) - 基于 AWS 的负载测试服务，支持 JMeter、Gatling 和 Selenium 场景.
- [LoadRunner Cloud](https://www.microfocus.com/en-us/products/loadrunner-cloud/overview) - Micro Focus 基于云的解决方案，用于 Web 和移动性能测试，支持 JMeter 和 Gatling（以前称为 HP StormRunner Load）.
- [Loadium](https://loadium.com/) - 基于 AWS 的负载测试服务，支持 JMeter 和 Selenium.
- [Azure Microsoft](https://azure.microsoft.com/en-us/products/load-testing/) - Azure 负载测试服务使用 Apache JMeter.

## Results Processing

- [JMeter Report Dashboard](https://jmeter.apache.org/usermanual/generating-dashboard.html) - JMeter 支持仪表板报告生成以从测试计划中获取图表和统计数据.
- [Latency Lingo](https://latencylingo.com) - 发布测试结果以生成包含见解的托管交互式仪表板.

### Results Analysis

<!--lint ignore double-link-->
- [JMeter Log Analysis](https://cwiki.apache.org/confluence/display/jmeter/LogAnalysis) - JMeter 日志分析的建议和方法.
- [Analyzing JMeter Results](https://www.datazoo.de/articles/158/performance-testing-analyzing-jmeter-results)
- [JMeter Result Analysis: The Ultimate Guide](https://octoperf.com/blog/2017/10/19/how-to-analyze-jmeter-results/)
- [JtlReporter](https://github.com/ludeknovy/jtl-reporter) - 在线报告应用程序通过上传 JTL 文件生成报告.
- [JMeter Result Analysis Plugin](https://github.com/afranken/jmeter-analysis-maven-plugin) - 解析 JMeter 测试结果并生成带有图表的详细报告的 Maven 插件.
- [JMeter Results Analyser](https://sourceforge.net/projects/jmstats/) - 基于 Web 的应用程序，用于整理、分析和报告 JMeter 测试结果.
- [JMeter Graph Tool Maven Plugin](https://github.com/vdaburon/jmeter-graph-tool-maven-plugin) - 使用 CMDRunner 和 Filter Results Tools 创建图表和过滤结果的 Maven 插件 [JMeter Plugins](#plugins) ; 通常与 [JMeter Maven Plugin](#tools--plugins) 和一套 ["companion" plugins](https://github.com/vdaburon/jmeter-graph-tool-maven-plugin#compagnion-tools).
- 数据库结果收集器
  - [JMeter DBCollector Plugin](https://sourceforge.net/projects/jmeterdbcollect/) - 启用将结果记录到数据库中以进行更有效报告的插件.
  - [JMeter MySQLCollector Plugin](https://cwiki.apache.org/confluence/display/jmeter/MysqlCollectorPlugin) - Patch to configure listener to log into MySQL database.
- SLA 和 KPI
  - [JMeter SLA Report](https://github.com/sgoeschl/jmeter-sla-report) - 基于 JAMon 的 JMeter HTML 报告生成器.
  - [JMeter JUnit Reporter](https://github.com/tilln/jmeter-junit-reporter) - Apache JMeter 插件，用于根据自定义 KPI（关键绩效指标）生成 XML 格式的 JUnit 报告.

### Reporting & Visualization

<!--lint ignore double-link-->
- 流入数据库和格拉法纳
  - [Using JMeter with InfluxDB & Grafana](https://www.vinsguru.com/category/influxdb/) - 使用 InfluxDB 和 Grafana 收集和可视化实时测试结果和服务器监控统计信息的指南集.
  - [How to Use Grafana to Monitor JMeter Non-GUI Results](https://dzone.com/articles/how-to-use-grafana-to-monitor-jmeter-non-gui-resul)
  - [jmeterReports](https://github.com/kirillyu/jmeterReports) - 自动生成的 JMeter 测试运行结果报告到 Confluence，使用 Grafana 自定义仪表板 :ru:.
  - [InfluxDB Community Template for JMeter](https://github.com/influxdata/community-templates/tree/master/apache_jmeter) - 预打包的 InfluxDB 配置，包含从仪表板和 Telegraf 配置到单个清单文件中的通知和警报的所有内容.
  - Grafana 仪表板
    - [JMeter Load Test Dashboard](https://grafana.com/grafana/dashboards/1152-jmeter-load-test/) - Grafana 仪表板显示 JMeter（由 NovaTec-APM）提供的实时负载测试指标.
    - [JMeter Dashboard using Core InfluxdbBackendListenerClient](https://grafana.com/grafana/dashboards/5496-apache-jmeter-dashboard-by-ubikloadpack/) - 使用 InfluxDB 和 Grafana（Philippe M）实时监控您的 Apache JMeter 负载测试.
    - [JMeter Dashboard (3.2 and up)](https://grafana.com/grafana/dashboards/3351-jmeter-3-3/) - 使用 InfluxDB 和 Grafana（由 adrianbanu）实时监控 JMeter 负载测试.
    - [JMeter (via prometheus exporter)](https://grafana.com/grafana/dashboards/2492-jmeter/) - Grafana 仪表板，用于通过 Prometheus 导出器（由 chiabre）检查 JMeter 指标.
  - [JMeter-InfluxBD-Writer Plugin](https://github.com/NovatecConsulting/JMeter-InfluxDB-Writer) - JMeter 插件，用于将负载测试数据即时写入 InfluxDB.
  - [JMeter Results to InfluxDB](https://github.com/soprasteria/jmeter2influxdb) - 从 csv 文件读取 JMeter 结果并放入 InfluxDB 数据库.
- 麋鹿堆栈
  - [Using ELK](https://ecmarchitect.com/archives/2014/09/09/3932) - 使用 Elasticsearch、Logstash 和 Kibana 可视化 JMeter 测试结果.
  - [JMeter + ElasticSearch Live Monitoring](https://medium.com/@anthony.gauthier325/jmeter-elasticsearch-live-monitoring-c895c843c51e) - 使用 ElasticSearch 后端监听器和 Grafana/Kibana 实时监控结果.
  - [jmeter-logstash](https://github.com/anasoid/jmeter-logstash) - 实时或在测试结束后使用 Docker 和 Logstash 解析 JTL 结果，并将数据发送到 Elasticsearch 或 InfluxDb，以获得漂亮的仪表板并比较不同的测试.
- 普罗米修斯
  - [jmeter-prometheus-plugin](https://github.com/johrstrom/jmeter-prometheus-plugin) - Apache JMeter 的 Prometheus Listener，在 HTTP API 中公开结果.
  - [jmeter-prometheus-listener](https://github.com/kolesnikovm/jmeter-prometheus-listener) - 用于 Prometheus 指标导出的 Apache JMeter 后端监听器实现.
  - [ulp-observability-plugin](https://github.com/ubikingenierie/ulp-observability-plugin) - 允许您从您最喜欢的浏览器监控您的 JMeter CLI 性能测试，而无需在 GUI 模式下启动 JMeter.
- ClickHouse
  - [JMeter Results from ClickHouse](https://grafana.com/grafana/dashboards/9561-jmeter-results-from-clickhouse-eng/) - 使用 [JMeter Listener pack](https://gitlab.com/testload/jmeter-listener/-/wikis/3.3-ClickHouse-usage)、ClickHouse 和 Grafana 来收集和监控测试结果.
  - [jmeter-clickhouse-listener](https://gitlab.com/testload-group/jmeter-clickhouse-listener) - JMeter 插件允许将负载测试数据即时写入 ClickHouse.
- 后端监听器实现
  - [jmeter-elasticsearch-backend-listener](https://github.com/anthonygauthier/jmeter-elasticsearch-backend-listener) - JMeter 插件，用于将测试结果发送到 ElasticSearch 引擎.
  - [jmeter-backend-azure](https://github.com/adrianmo/jmeter-backend-azure) - JMeter 插件，用于将测试结果发送到 Azure Application Insights.
  - [jmeter-backend-listener-kafka](https://github.com/rahulsinghai/jmeter-backend-listener-kafka) - JMeter 插件，用于将测试结果发送到 Kafka 服务器.
  - [jmeter-listener](https://gitlab.com/testload/jmeter-listener) - JMeter 插件，用于将负载测试数据即时写入 ClickHouse、InfluxDB、ElasticSearch.
  - [jmeter-influxdb2-listener-plugin](https://github.com/mderevyankoaqa/jmeter-influxdb2-listener-plugin) - 用于 Apache JMeter 的 InfluxDB v2.0 侦听器插件.
  - [jmeter-datadog-backend-listener](https://github.com/DataDog/jmeter-datadog-backend-listener) - 将 JMeter 测试结果发送给 Datadog.
  - [jmeter-dynatrace-plugin](https://github.com/dynatrace-oss/jmeter-dynatrace-plugin) - JMeter 后端侦听器实现，用于通过 Dynatrace MINT 指标摄取将记录的负载测试指标发送到配置的 Dynatrace 监控环境.
  - [jmeter-backend-newrelic](https://github.com/darrensmithwtc/jmeter-backend-newrelic) - 一个 JMeter 插件，用于将测试结果发送到 New Relic Metrics API.
- AWS 云观察
  - [jmeter-cw-logs](https://github.com/concurrencylabs/jmeter-cw-logs) - 用于将 JMeter 测试结果发布到 AWS CloudWatch Logs 的 CloudFormation 模板.
- 自定义和弃用
  - [Using Matplotlib & Python](https://www.metaltoad.com/blog/plotting-your-load-test-jmeter) - 使用 Matplotlib 绘图工具和 Python 绘制 JMeter 负载测试结果.
  - [Statistical Aggregate Report](https://rubenlaguna.com/post/2007-01-02-better-jmeter-graphs/) - 用于增强结果可视化的自定义统计聚合报告侦听器.
  - [JChav](https://github.com/d6y/jchav) - JMeter 图表历史和可视化库.
  - JMeter 仪表板： [howto](https://seangkuan.blogspot.com/2015/06/jmeter-dashboard-realtime-monitoring-of.html), [sources](https://github.com/vincentskooi/JMeterDashboard) - JMeter负载测试实时监控.
  - [Using CMDRunner & Powershell](https://performancewebautoamtionother.blogspot.com/2015/12/jmeter-create-graphs-with-cmdrunner.html) - 使用 CMDRunner 和 powershell 并行执行创建 JMeter 图表.

## Performance Testing

### Streaming Protocols

- [Easy and realistic Load Testing of HTTP Live Streaming (HLS) with Apache JMeter](https://www.ubik-ingenierie.com/blog/easy-and-realistic-load-testing-of-http-live-streaming-hls-with-apache-jmeter/)
- [Using JMeter to Load Test Live HLS Concurrency of Wowza Streaming Engine](https://web.archive.org/web/20210918113142/https://www.realeyes.com/blog/wowza-streaming/)
- [Load testing HLS with Ruby JMeter](https://www.flood.io/blog/load-testing-hls-with-ruby-jmeter)
- [How to Test Video Streaming with JMeter](https://www.blazemeter.com/blog/video-streaming-testing)
- [HLS JMeter Plugin](https://github.com/Blazemeter/HLSPlugin)

### Mobile Apps

- [Record iOS application HTTP requests](https://www.testautomationguru.com/jmeter-record-ios-application-http-requests/)
- [Load Testing Mobile Apps Made Easy](https://www.blazemeter.com/blog/mobile-app-load-testing)

### Mainframe Environments

- [JMeter RTE Plugin](https://github.com/Blazemeter/RTEPlugin) - 用于测试大型机应用程序的 JMeter RTE（远程终端仿真器协议）插件.

### RPC Frameworks

- [JMeter gRPC Plugin](https://github.com/zalopay-oss/jmeter-grpc-plugin) - JMeter 插件支持负载测试 gRPC.
- [JMeter gRPC Request](https://github.com/zalopay-oss/jmeter-grpc-request) - JMeter gRPC 请求负载测试插件.
- [JMeter Dubbo Plugin](https://github.com/thubbo/jmeter-plugins-for-apache-dubbo) - Apache Dubbo 的 JMeter 插件.

### RESTful API

- [REST API Testing with JMeter. Step by Step Guide](https://octoperf.com/blog/2018/04/23/jmeter-rest-api-testing/)

## Tools

### Plugins

- [JMeter Plugins](https://jmeter-plugins.org/) - 独立的 Apache JMeter 插件集，插件管理器引用了许多插件并简化了安装.
- [Ubik Load Pack](https://ubikloadpack.com/) - Apache JMeter 的生产力扩展.
- GitHub 主题： [jmeter-plugin](https://github.com/topics/jmeter-plugin), [jmeter-plugins](https://github.com/topics/jmeter-plugins) - 探索带有 `jmeter-plugin` 或 `jmeter-plugins` 标签的 JMeter 插件.

### Correlation

<!--lint ignore double-link-->
- [Correlation Recorder Plugin](https://github.com/Blazemeter/CorrelationRecorder) - JMeter 插件，通过在记录时提供变量的自动关联，简化了动态变量应用程序的记录过程.
- [Siebel CRM Plugin](https://github.com/Blazemeter/SiebelPlugin) - JMeter 插件通过在记录时提供变量的自动关联来简化 Siebel CRM 应用程序的脚本 ❄️.
- [ULP Auto-correlator Plugin](https://www.ubik-ingenierie.com/blog/ubikloadpack-autocorrelator-plugin-help/) - 用于 Oracle 和基于 Vaadin 的应用程序的商业插件 [Ubik Load Pack](#plugins).

### Extending JMeter

- [JMeter Developer Manual](https://cwiki.apache.org/confluence/display/jmeter/DeveloperManual)
- [How to write a plugin for JMeter](https://jmeter.apache.org/usermanual/jmeter_tutorial.html)
- [How to build a JMeter plugin utilizing Groovy](https://web.archive.org/web/20180225144718/http://artur.ejsmont.org/blog/content/how-to-build-a-jmeter-plugin-utilising-groovy)
- [How to create a plugin in JMeter](https://stackoverflow.com/questions/20422640/how-to-create-a-plugin-in-jmeter)
- [Custom JMeter Samplers and Config Elements](http://codyaray.com/2014/07/custom-jmeter-samplers-and-config-elements)
- [Implement Custom JMeter Samplers](https://dzone.com/articles/implement-custom-jmeter-samplers)
- [Hello JMeter plugin](https://github.com/Bugazelle/hello-jmeter-plugin) - 创建您的第一个 JMeter 插件的简短、清晰和快速的指南.

### IDE Integration

- [Intellij IDEA IDE Plugin](https://plugins.jetbrains.com/plugin/7013-jmeter-plugin) - 从 Intellij IDEA 创建运行配置并运行 JMeter 测试.
- [JMeter + Eclipse HOWTO](https://cwiki.apache.org/confluence/display/jmeter/JMeterAndEclipseHowTo) - 使用 Eclipse IDE 开发 JMeter 项目.
- [Using a Load Generator in NetBeans IDE](https://netbeans.apache.org//kb/docs/java/profile-loadgenerator.html)

### Editors

*除了标准的 JMeter GUI 和 XML 编辑器之外，还有 JMX 文件的替代编辑器.*

<!--lint ignore double-link-->
- [BlocklyJMX Editor](https://jmeter-plugins.org/editor/) - JMeter 测试计划文件的基于 Web 的查看器和编辑器（部分 [JMeter Plugins](#plugins) 项目）.
- [JEval](https://github.com/QAInsights/JEval) - 基于 Python 的实用程序，可评估 JMeter 测试计划并通过分析每个元素提供建议和最佳实践.
- [JMX Enhancer](https://www.jmxenhancer.com/) - 加快 JMeter 测试计划准备的解决方案.
- [jmx.js](https://www.vinodkd.org/jmx.js/) - 用于 JMeter JMX 文件的基于 Web 的编辑器.

## APM Integration

*与应用程序性能监控 (APM) 工具集成以分析应用程序服务器、数据库服务器和 Web 服务的性能.*

<!--lint ignore double-link-->
- [Servers Performance Monitoring Plugin](https://jmeter-plugins.org/wiki/PerfMon/) - 服务器监控插件来自 [JMeter Plugins](#plugins) 项目.
- [CA App Synthetic Monitor](https://asm.saas.broadcom.com/en/feature/transaction-monitoring-web-application-testing.html) - 具有 JMeter 支持的事务监控和测试解决方案.
- [Dynatrace and JMeter integration](https://www.dynatrace.com/support/help/platform-modules/cloud-automation/test-automation/dynatrace-and-jmeter-integration)
- [JMeter integration with AppDynamics](https://docplayer.net/62851982-Jmeter-integration-with-appdynamics.html) - 具有 JMeter 集成的 APM 和 EUM 解决方案.
- 使用 New Relic 和 JMeter 进行性能修复： [part 1](https://moduscreate.com/blog/performance-remediation-using-new-relic-jmeter-part-1-3/), [part 2](https://moduscreate.com/blog/performance-remediation-using-new-relic-jmeter-part-2-3/)

## JMeter Performance

- [JMeter Performance](https://cwiki.apache.org/confluence/display/jmeter/JMeterPerformance) - 跨版本的 JMeter 性能演变.
- [JMeter Performance and Tuning Tips](https://www.ubik-ingenierie.com/blog/jmeter_performance_tuning_tips/) - 由 Ubik Ingenierie 提供.
- 如何加速 JMeter： [part 1](https://pflb.us/blog/how-to-speed-up-jmeter-part-1/), [part 2](https://pflb.us/blog/how-to-speed-up-jmeter-part-2/)

## Tips & Tricks

- [JMeter tips](https://web.archive.org/web/20221126233834/https://www.webwob.com/html/jmeter_tips.html) - JMeter 提示和技巧暂存器.

## Books

<!--lint ignore double-link-->
- [Apache JMeter: A Practical Beginner's Guide to Automated Testing and Performance Measurement for Your Websites](https://books.google.com/books?id=nX8oKIEvUcYC) - Emily H. Halili（Packt Publishing）着.
- [Performance Testing with JMeter 2.9](https://books.google.com/books?id=fpWmv3wPT64C) - Bayo Erinle ([Packt Publishing](https://www.packtpub.com/product/performance-testing-with-jmeter-29/9781782165842) ); 使用 Apache JMeter 测试 Web 应用程序的指南，其中包含实际操作示例.
- [Performance Testing with JMeter, 2nd Edition](https://books.google.com/books?id=6ditCAAAQBAJ) - Bayo Erinle ([Packt Publishing](https://www.packtpub.com/product/performance-testing-with-jmeter/9781784394813)).
- [Performance Testing with JMeter 3, 3rd Edition](https://books.google.com/books?id=BedDDwAAQBAJ) - Bayo Erinle ([Packt Publishing](https://www.packtpub.com/product/performance-testing-with-jmeter-3-third-edition/9781787285774)).
- [JMeter Cookbook](https://books.google.com/books?id=gJUeBQAAQBAJ) - Bayo Erinle ([Packt Publishing](https://www.packtpub.com/product/jmeter-cookbook/9781783988280) ); 帮助成功使用 Apache JMeter 的 70 个有见地且实用的秘诀.
- [JMeter by Example](https://books.google.com/books?id=iWeJDAEACAAJ) - Sai Matam 和 Jagdeep Jain ([Leanpub](https://leanpub.com/jmeterbyexample) ); 一个简单、实用、循序渐进的教程，用于衡量网站的性能.
- [Pro Apache JMeter: Web Application Performance Testing](https://books.google.com/books?id=YJ4xDwAAQBAJ) - Sai Matam 和 Jagdeep Jain ([Apress](https://link.springer.com/book/10.1007/978-1-4842-2961-3)).
- [Master Apache JMeter: From load testing to DevOps](https://books.google.com/books?id=D_amDwAAQBAJ) - Antonio Gomes Rodrigues、Bruno Demion (Milamber) 和 Philippe Mouawad ([Leanpub](https://leanpub.com/master-jmeter-from-load-test-to-devops), [Packt Publishing](https://www.packtpub.com/product/master-apache-jmeter-from-load-testing-to-devops/9781839217647)).
- [Advanced JMeter Testing](https://leanpub.com/advanced_jmeter_testing) - 彭妮·库里奇 ([Leanpub](https://leanpub.com/advanced_jmeter_testing)), 为 Apache JMeter 5.0 编写自定义组件的指南.

## Trainings & Courses

- [JMeter: Performance and Load Testing (Feb 2019)](https://www.linkedin.com/learning/jmeter-performance-and-load-testing) - 通过 LinkedIn 学习.
- [Advanced JMeter (Jul 2020)](https://www.linkedin.com/learning/advanced-jmeter) - 通过 LinkedIn 学习.
- [JMeter Training Courses](https://www.nobleprog.co.uk/jmeter-training) - 由 NobleProg 提供.
- [BlazeMeter University](https://www.blazemeter.com/university) - 通过 BlazeMeter.
- [JMeter Courses collection](https://www.udemy.com/topic/jmeter/) - 由乌迪米.
- [Web Applications (and Mobile Apps) Performance Testing with JMeter](http://pragmatictestlabs.com/web-applications-mobile-apps-performance-testing-jmeter/) - 由 Pragmatic Test Labs 提供.
- [Training courses on Load Testing with Apache JMeter](https://www.ubik-ingenierie.com/blog/jmeter-trainings-by-contributors-and-committers/) - 由 Ubik Ingenierie 提供.
- [Apache JMeter Training](https://qainsights.com/apache-jmeter-training/) - 通过 QAInsights.
- [JMeter Getting Started Course (Apr 2019)](https://www.pluralsight.com/courses/jmeter-getting-started) - 通过 Pluralsight.

## Videos

- [JMeter Tutorials](https://www.youtube.com/c/AutomationStepByStep/search?query=jmeter) - 通过自动化一步一步.
- [Learn Apache JMeter Series](https://www.youtube.com/playlist?list=PLJ9A48W0kpRIjLkZ32Do9yDZXnnm7_uj_) - 通过 QAInsights.
- [JMeter / Devops/ CI-CD / Cloud](https://www.youtube.com/c/xavki-linux/search?query=jmeter) - 作者 xavki :fr:.

## Community

### Blogs

- [BlazeMeter Blog](https://www.blazemeter.com/blog) - 关于 JMeter 和性能测试的 BlazeMeter 博客.
- [Ubik Load Pack Blog](https://www.ubik-ingenierie.com/blog/category/jmeter/) - Ubik 工程博客.
- [TestAutomationGuru Blog](https://www.testautomationguru.com/category/jmeter/) - 关于测试自动化的技术博客.
- [RedLine13 Blog](https://www.redline13.com/blog/tag/jmeter/) - RedLine13 博客中的 JMeter 文章.
- [Flood.io Blog](https://www.flood.io/blog) - 从 Flood IO 加载测试思想、故事和创意.
- [JMeter Blog](https://shantonusarker.blogspot.com/p/jmeter.html) - 另一个使用 JMeter 进行性能和自动化测试的博客.
- [OctoPerf Blog](https://octoperf.com/categories/jmeter/) - 关于 JMeter 和负载测试的 OctoPerf 博客.
- [Abstracta JMeter Archives](https://abstracta.us/blog/tag/jmeter/) - 关于 JMeter 的抽象博客.
- [JMeter Tips](https://jmeter-tips.blogspot.com/) - 关于 Apache JMeter 和 Web 应用程序性能测试的博客.
- [JMeter Expert Blog](https://jmeter-expert.blogspot.com/) - JMeterExpert 博客.
- [JMeter Series](http://blog.sourcepole.com/2011/01/04/jmeter-series/) - Sourcepole 博客.
- [JMeter Basics](https://thatsabug.com/tags/#jmeter-series) - 若昂·法里亚斯 (João Farias).
- [Azure Load Testing Blog](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/bg-p/AppsonAzureBlog/label-name/Azure%20Load%20Testing) - 由微软技术社区提供.

### Forums

<!--lint ignore double-link-->
- [JMeter Google Group](https://groups.google.com/forum/#!forum/ptgram24)
- [JMeterPlugins Google Group](https://groups.google.com/forum/#!forum/jmeter-plugins)

### Twitter

<!--lint ignore double-link-->
- [@ApacheJMeter](https://twitter.com/apachejmeter) - Apache JMeter 负载测试工具的官方 Twitter 帐户.
- [@jmeter_plugins](https://twitter.com/jmeter_plugins) - JMeter 负载测试工具的自定义插件项目的 Twitter 帐户.
- [@BlazeMeter](https://twitter.com/BlazeMeter) - 基于 JMeter 的 DevOps 性能工程平台 Blazemeter 的官方 Twitter 帐户.
- [@masterjmeter](https://twitter.com/masterjmeter) - 公众号 [Master Apache JMeter from Load Testing to DevOps](#books) 书.
- [@ubikloadpack](https://twitter.com/ubikloadpack) - 推特账号 [Ubik Load Pack](#plugins)，用于视频流和复杂协议负载测试的自定义 JMeter 插件.

### Q&A

- [`jmeter` on Stack Overflow](https://stackoverflow.com/questions/tagged/jmeter)
- [`jmeter` on Gitter](https://app.gitter.im/#/room/#aliesbelik_jmeter-chat:gitter.im)
- [`#jmeter` on Slack](https://jmeterusers.slack.com/)
- [`r/jmeter` on Reddit](https://www.reddit.com/r/jmeter/)

## Related

### Awesome Lists

- [Awesome Software Quality](https://github.com/ligurio/sqa-wiki) - 免费软件测试和验证资源列表.
- [Awesome Testing](https://github.com/TheJambo/awesome-testing) - 精选的测试资源列表.
- [Awesome Tsung](https://github.com/aliesbelik/awesome-tsung) - 开源多协议分布式负载测试工具，使用 Erlang 开发.
- [Awesome Gatling](https://github.com/aliesbelik/awesome-gatling) - 基于 Scala、Akka 和 Netty 的开源负载和性能测试框架.
- [Awesome k6](https://github.com/grafana/awesome-k6) - 开源、以开发人员为中心的性能监控和负载测试解决方案.
- [Awesome Locust](https://github.com/aliesbelik/awesome-locust) - 用 Python 编写的开源可扩展负载测试框架.

### Other

- [How They Load Test](https://github.com/aliesbelik/how-they-load) - 关于世界各地的公司如何执行负载测试的公开可用资源的精选集合.
- [Load Testing Toolkit](https://github.com/aliesbelik/load-testing-toolkit) - 用于调试、基准测试、负载和压力测试您的代码或服务的开源工具集合.

## Contributing

欢迎投稿！<br>
请看一下 [CONTRIBUTING](https://github.com/aliesbelik/awesome-jmeter/blob/master/CONTRIBUTING.md) 准则第一.
