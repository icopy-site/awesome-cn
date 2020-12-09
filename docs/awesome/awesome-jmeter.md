<div class="github-widget" data-repo="aliesbelik/awesome-jmeter"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome JMeter [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

精选的资源涵盖 [Apache JMeter](https://jmeter.apache.org/) 以及相关的东西和闪亮的东西：插件，集成，测试技术，devops实践等.

[<img src="https://raw.githubusercontent.com/aliesbelik/awesome-jmeter/master/assets/images/jmeter-logo.svg?sanitize=true" align="right" width="260" alt="Apache JMeter">](https://jmeter.apache.org/)

&gt; [Apache JMeter](https://jmeter.apache.org/) 是开源的纯Java应用程序，旨在加载测试功能行为并衡量性能.

这个名单是从 [an occasional answer](https://sqa.stackexchange.com/a/2552/1842) 从Stack Exchange和与JMeter相关的个人链接收集中获得了进一步的启发 [awesome](https://awesome.re) 项目并通过这些改进 [amazing contributors](https://github.com/aliesbelik/awesome-jmeter/blob/master/CONTRIBUTORS.md).



## Official Resources

- [Apache JMeter Project](https://jmeter.apache.org/) -Apache JMeter官方网站.
- [GitHub Repository](https://github.com/apache/jmeter) -Apache JMeter源代码存储库.
- [JMeter Wiki](https://cwiki.apache.org/confluence/display/jmeter) -Apache JMeter官方文档.
- [Issue Tracking](https://jmeter.apache.org/issues.html) -Apache JMeter问题跟踪系统.
- [Mailing Lists](https://jmeter.apache.org//mail2.html) -Apache JMeter邮件列表.

## Distributions

- [Download Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi) -Apache JMeter：官方下载.
- [JMeter for Windows](https://sourceforge.net/projects/jmeterforwindows/) -带有插件的安装JMeter的软件包.
- [JMeter Bootstrap](https://github.com/cfpb/jmeter-bootstrap) -设置JMeter和JMeter插件的解决方案，适合用作子模块.

## Getting Started

- [Getting Started with Apache JMeter](https://dzone.com/refcardz/getting-started-with-apache-jmeter)
- [A Simple Load Test with JMeter](https://www.urbaninsight.com/article/simple-load-test-with-jmeter)
- [The Beginner's Guide to Performance Testing with Apache JMeter](https://medium.com/better-programming/the-beginners-guide-to-performance-testing-with-apache-jmeter-5cc52c327ff6)

## Tutorials

- [JMeter Tutorials](https://artoftesting.com/jmeter-tutorial)
- [Load Testing your Applications with Apache JMeter](http://www.jguru.com/article/server-side/load-testing-with-apache-jmeter.html) -Keld H. Hansen.
-使用JMeter进行负载测试：
  - [part 1](https://lincolnloop.com/blog/2011/sep/21/load-testing-jmeter-part-1-getting-started/) - 入门.
  - [part 2](https://lincolnloop.com/blog/2011/oct/12/load-testing-jmeter-part-2-headless-testing-and-je/) -无头测试和Jenkins集成.
  - [part 3](https://lincolnloop.com/blog/2012/sep/19/load-testing-jmeter-part-3-replaying-apache-logs/) -重播Apache日志.
- [JMeter Resources](https://resources.infosecinstitute.com/topic/apache-jmeter-part-1/)
- [Functional Testing with JMeter](https://hub.packtpub.com/functional-testing-jmeter/)
- [JMeter Tutorial](https://www.tutorialspoint.com/jmeter/)
- [JMeter Tutorial for Load Testing: The Ultimate Guide](https://www.javacodegeeks.com/2014/11/jmeter-tutorial-load-testing.html)
- [RESTful API testing with JMeter](https://www.ibm.com/developerworks/cloud/library/cl-jmeter-restful/)
- [How to Hit Your RESTful Web Service Using JMeter](https://crunchify.com/how-to-hit-your-restful-web-service-using-jmeter-perform-a-simple-load-test/)
- [JMeter: Load Development LifeCycle](https://datacadamia.com/jmeter/lifecycle)
- [Load Testing with Apache JMeter](https://www.digitalocean.com/community/tutorial_series/load-testing-with-apache-jmeter)
- [JMeter Tutorial](https://www.guru99.com/jmeter-tutorials.html) -作者：Guru99.
- [JMeter Series](http://blog.sourcepole.com/2011/01/04/jmeter-series/)

## Best Practices

- [JMeter Official Best Practices](https://jmeter.apache.org/usermanual/best-practices.html)
- [JMeter Best Practices](https://guide.blazemeter.com/hc/en-us/articles/207421405-JMeter-Best-Practices)
- [Optimize JMeter for Large Scale Tests](https://octoperf.com/blog/2017/10/12/optimize-jmeter-for-large-scale-tests/)
- [Concurrent, High Throughput Performance Testing with JMeter](https://planet.jboss.org/post/concurrent_high_throughput_performance_testing_with_jmeter)

## Scripting

- [Beanshell vs JSR223 vs Java JMeter Scripting](https://www.blazemeter.com/blog/beanshell-vs-jsr223-vs-java-jmeter-scripting-its-performance/) -最流行的脚本机制性能比较.
- [Testing with Groovy](https://static.packt-cdn.com/downloads/Testingwithgroovy.pdf) -使用JMeter和Groovy进行负载测试.
- [JMeter: забудьте про BeanShell Sampler](https://habr.com/ru/post/250731/) -JMeter：忘记BeanShell Sampler *（俄语）*.

## Automation

### DSL

- [Ruby-JMeter](https://github.com/flood-io/ruby-jmeter) -用于构建JMeter测试计划的基于Ruby的DSL.
- [jmeter-java-dsl](https://github.com/abstracta/jmeter-java-dsl) -简单的API，以VCS和程序员友好的方式运行JMeter性能测试.
- [jmeter-groovy-dsl](https://github.com/smicyk/groovy-jmeter) -Groovy-JMeter项目是用于编写JMeter测试计划的简单DSL.

### Packages

- [loadtest](https://github.com/tmobile/loadtest) -用于使用JMeter进行负载测试的R软件包.

### Frameworks

- [Taurus](https://gettaurus.org/) -自动化友好的连续测试框架.
- [Performance testing framework](https://github.com/serputko/performance-testing-framework) -使用Apache JMeter进行后端负载测试和使用sitespeed.io + webpagetest私有实例进行前端负载测试的框架.
- [JMeter Load Testing Center](https://github.com/innogames/JMeter-Control-Center) -在线Web应用程序/仪表板，用于使用JMeter运行，监视和分析负载测试的结果.

### Conversion

- [swaggerjmx](https://github.com/Pactortester/swaggerjmx) -将Swagger UI规范转换为JMeter测试计划的工具.

## CI

### Tools & Plugins

- [JMeter Ant Task](https://github.com/jfifield/ant-jmeter) -Ant任务可自动运行JMeter测试计划.
- [JMeter Maven Plugin](https://github.com/jmeter-maven-plugin/jmeter-maven-plugin) -Maven插件，可以在构建过程中运行JMeter测试.
- [Jenkins Performance Plugin](https://plugins.jenkins.io/performance/) -Jenkins插件可捕获JMeter的报告并生成具有性能和鲁棒性趋势报告的图形图表.
- [TeamCity Performance Tests Analysis Plugin](https://github.com/jtorgan/jmeter_plugin) -TeamCity插件可以在CI中组织最简单的性能测试*（没有更多更新）*.
- [Bamboo JMeter Aggregator Plugin](https://marketplace.atlassian.com/apps/5902/jmeter-aggregator-for-bamboo) -Bamboo插件，用于收集，声明和绘制JMeter测试结果.
- [Sonar JMeter Plugin](https://github.com/SonarQubeCommunity/sonar-jmeter) -收集JMeter性能测试结果并显示在Sonar仪表板中的插件*（已弃用）*.
- [Lightning](https://automatictester.github.io/lightning/) -将JMeter非功能测试与CI / CD服务器集成的框架.
- [Taurus JMeter Executor](https://gettaurus.org/docs/JMeter/) -Taurus自动化框架中的JMeter执行器.
- [PerfAction for JMeter](https://github.com/marketplace/actions/perfaction-for-jmeter) -GitHub Action，使用Apache JMeter及其插件运行性能测试.

### Tutorials & Demo

-詹金斯
  - [Automated performance testing using JMeter and Maven](https://www.atlassian.com/blog/archives/automated_performance_testing_using_jmeter_and_maven)
  - [Performance Tests with JMeter, Maven and Hudson](https://medium.com/the-server-labs/performance-tests-with-jmeter-maven-and-hudson-d1cbdb3ffad8)
  - [CI with Jenkins, Git, Maven, Grunt, and JMeter](https://github.com/dzuluagaapigee/apigee-ci-jenkins-git-maven-jmeter)
  - [Continuous automated web tests using Jenkins and JMeter](https://www.linkedin.com/pulse/continuous-automated-web-tests-using-jenkins-jmeter-mahanta)
  - [Automating JMeter tests with Maven and Jenkins](https://blog.codecentric.de/en/2014/01/automating-jmeter-tests-maven-jenkins/)
  -如何使用Maven和Jenkins自动执行JMeter测试：
    - [part 1](https://ribblescode.wordpress.com/2012/04/16/how-to-run-jmeter-tests-with-maven/)
    - [part 2](https://ribblescode.wordpress.com/2012/04/16/how-to-automate-jmeter-tests-with-maven-and-jenkins-hudson-8/)
  -JMeter持续性能测试（JMeter + Ant + Jenkins）：
    - [part 1](http://www.testautomationguru.com/jmeter-continuous-performance-testing-part1/)
    - [part 2](http://www.testautomationguru.com/jmeter-continuous-performance-testing-part2/)
  - [Continuous Integration 101: How to Run JMeter with Jenkins](https://www.blazemeter.com/blog/continuous-integration-101-how-run-jmeter-jenkins/)
-竹
  - [How to Run JMeter in a Continuous Integration Environment with Bamboo](https://www.blazemeter.com/blog/how-run-jmeter-continuous-integration-environment-bamboo/)
-TeamCity
  - [How to Run JMeter Tests with TeamCity for Continuous Integration](https://www.blazemeter.com/blog/how-run-jmeter-tests-teamcity-continuous-integration/)
-CircleCI
  - [How to integrate JMeter into CircleCI](https://www.blazemeter.com/blog/how-to-integrate-jmeter-into-circleci/)
- SonarQube
  - [JMeter with Sonar](http://testersinaction.blogspot.com/2013/05/v-behaviorurldefaultvmlo_24.html)

## Distributed Testing

- [JMeter Distributed Testing Step-by-step](https://jmeter.apache.org/usermanual/jmeter_distributed_testing_step_by_step.pdf)
- [JMeter Remote Testing](https://jmeter.apache.org/usermanual/remote-test.html)
- [Setting up a JMeter Cluster for web server load testing](https://www.howtoforge.com/setting-up-jmeter-cluster-for-load-testing/)
-Dockerized
  - [Dockerized JMeter](https://gist.github.com/hhcordero/abd1dcaf6654cfe51d0b) -使用Docker和JMeter进行分布式负载测试工作流.
  - [JMeter Docker Images](https://hub.docker.com/search/?isAutomated=0&isOfficial=0&page=1&pullCount=0&q=jmeter&starCount=0)
  - [Distributed JMeter testing using Docker](http://srivaths.blogspot.com/2014/08/distrubuted-jmeter-testing-using-docker.html)
  - [A Docker solution to JMeter + InfluxDB + Grafana performance testing](https://medium.com/@ellenhuang523/a-docker-solution-to-jmeter-influxdb-grafana-performance-testing-568848de7a0f)
  - [AutoMeter](https://github.com/intuit/autometer) -基于JMeter主从架构，用于使用分布式从属扩展负载测试的自动化工具.
-在云中测试
  -亚马逊网络服务
    - [jmeter-ec2](https://github.com/oliverlloyd/jmeter-ec2/) -在Amazon EC2上自动运行Apache JMeter.
    - [gee](https://github.com/kowalcj0/gee) -JMeter-EC2项目的修改版本.
    - [os-jmeter-aws](https://github.com/OrdnanceSurvey/os-jmeter-aws) -在多个AWS实例上运行JMeter，在ELK中查看结果.
    - [Load Testing with JMeter and Amazon EC2](https://medium.com/@alttaf/load-testing-with-jmeter-and-amazon-ec2-e143a7350596)
    - [Performance Testing in the Cloud with JMeter & AWS](http://web.archive.org/web/20190526033436/http://www.artofsoftwaredevelopment.com/performance/performance-testing-in-the-cloud-with-jmeter-aws)
    - [JMeter distributed testing with Amazon EC2](https://vedovini.net/2009/08/17/jmeter-distributed-testing-with-amazon-ec2/)
  -DigitalOcean
    - [Lightweight JMeter Cloud](https://docs.google.com/presentation/d/1Yi5C27C3Q0AnT-uw9SRnMeEqXSKLQ8h9O9Jqo1gQiyI/) -使用DigitalOcean，JMeter和Docker构建自己的JMeter Cloud.
  -Microsoft Azure
    - [Load Testing Pipeline with JMeter, ACI and Terraform](https://github.com/Azure-Samples/jmeter-aci-terraform) -可扩展的云负载/压力测试管道解决方案，使用Apache JMeter和Terraform在Azure上动态配置和销毁所需的基础架构.

## Cloud Services / SaaS

*支持JMeter测试计划执行的基于云的负载测试服务列表.*

- [CA BlazeMeter](https://www.blazemeter.com/) -具有JMeter和Selenium支持的性能工程平台.
- [OctoPerf](https://octoperf.com/) -具有JMeter和Selenium支持的Saas和本地负载测试工具.
- [Tricentis Flood](https://www.flood.io/) -带有JMeter，Gatling和Selenium方案支持的负载测试服务.
- [RedLine13](https://redline13.com/) -基于AWS的负载测试服务，支持JMeter，Gatling和Selenium方案.
- [LoadRunner Cloud](https://www.microfocus.com/en-us/products/loadrunner-cloud/overview) -基于Micro Focus的基于云的解决方案，用于Web和移动性能测试，具有JMeter和Gatling支持（以前称为HP StormRunner Load）.
- [Loadster](https://loadster.app/) -用于分发Web应用程序和服务的负载测试的解决方案.
- [Loadium](https://loadium.com/) -具有JMeter和Selenium支持的基于AWS的负载测试服务.

## Results Processing

- [JMeter Report Dashboard](https://jmeter.apache.org/usermanual/generating-dashboard.html) -JMeter支持仪表板报告生成，以从测试计划中获取图形和统计信息.

### Results Analysis

- [JMeter Log Analysis](https://cwiki.apache.org/confluence/display/jmeter/LogAnalysis) -有关JMeter日志分析的建议和方法.
- [Analyzing JMeter Results](http://www.datazoo.de/articles/158/performance-testing-analyzing-jmeter-results)
- [JMeter Result Analysis: The Ultimate Guide](https://octoperf.com/blog/2017/10/19/how-to-analyze-jmeter-results/)
- [BlazeMeter Sense](https://sense.blazemeter.com/) -用于存储和分析性能测试结果的服务.
- [JtlReporter](https://github.com/ludeknovy/jtl-reporter) -在线报告应用程序，通过上传JTL文件来生成报告.
- [JAnalyser](http://janalyser.com/) -基于浏览器的结果分析工具.
- [JMeter Result Analysis Plugin](https://github.com/afranken/jmeter-analysis-maven-plugin) -解析JMeter测试结果并生成带有图表的详细报告的Maven插件.
- [JMeter Results Analyser](https://sourceforge.net/projects/jmstats/) -基于Web的应用程序，用于整理，分析和报告JMeter测试结果.
-数据库结果收集器
  - [JMeter DBCollector Plugin](https://sourceforge.net/projects/jmeterdbcollect/) -插件可将结果记录到数据库中，以实现更有效的报告.
  - [JMeter MySQLCollector Plugin](https://cwiki.apache.org/confluence/display/jmeter/MysqlCollectorPlugin) -修补程序，以配置侦听器以登录到MySQL数据库.
- [JMeter SLA Report](https://github.com/sgoeschl/jmeter-sla-report) -基于JAMon的JMeter HTML报告生成器.

### Results Visualisation

-石墨-* TBD *.
-InfluxDB和Grafana
  - [Using JMeter with InfluxDB & Grafana](https://www.vinsguru.com/category/influxdb/) -收集使用InfluxDB和Grafana收集和可视化实时测试结果和服务器监视统计信息的指南.
  - [How to Use Grafana to Monitor JMeter Non-GUI Results](https://dzone.com/articles/how-to-use-grafana-to-monitor-jmeter-non-gui-resul)
  -Grafana仪表板
    - [JMeter Load Test Dashboard](https://grafana.com/grafana/dashboards/1152) -Grafana仪表板显示JMeter（由NovaTec-APM提供）提供的实时负载测试指标.
    - [JMeter Dashboard using Core InfluxdbBackendListenerClient](https://grafana.com/grafana/dashboards/5496) -使用InfluxDB和Grafana（由Philippe M）实时监视Apache JMeter负载测试.
    - [JMeter Dashboard (3.2 and up)](https://grafana.com/grafana/dashboards/3351) -使用InfluxDB和Grafana实时监视JMeter负载测试（作者adrianbanu）.
    - [JMeter (via prometheus exporter)](https://grafana.com/grafana/dashboards/2492) -Grafana仪表板，可通过Prometheus导出器（按Chiabre）检查JMeter指标.
  - [JMeter-InfluxBD-Writer Plugin](https://github.com/NovatecConsulting/JMeter-InfluxDB-Writer) -JMeter插件可将负载测试数据即时写入InfluxDB.
  - [JMeter Results to InfluxDB](https://github.com/soprasteria/jmeter2influxdb) -从csv文件读取JMeter结果，并将其放入InfluxDB数据库.
-任何堆栈
  - [Using ELK](http://ecmarchitect.com/archives/2014/09/09/3932) -使用Elasticsearch，Logstash和Kibana可视化JMeter测试结果.
  - [JMeter + ElasticSearch Live Monitoring](https://medium.com/@anthony.gauthier325/jmeter-elasticsearch-live-monitoring-c895c843c51e) -使用ElasticSearch后端侦听器和Grafana / Kibana实时监视结果.
-普罗米修斯
  - [jmeter-prometheus-plugin](https://github.com/johrstrom/jmeter-prometheus-plugin) -Apache JMeter的Prometheus侦听器，可在HTTP API中公开结果.
-ClickHouse
  - [JMeter Results from ClickHouse](https://grafana.com/grafana/dashboards/9561) - 使用 [JMeter Listener pack](https://gitlab.com/testload/jmeter-listener/-/wikis/3.3-ClickHouse-usage)，ClickHouse和Grafana来收集和监视测试结果.
-后端监听器实现
  - [jmeter-elasticsearch-backend-listener](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) -JMeter插件，用于将测试结果发送到ElasticSearch引擎.
  - [jmeter-backend-azure](https://github.com/adrianmo/jmeter-backend-azure) -JMeter插件可将测试结果发送到Azure Application Insights.
  - [jmeter-backend-listener-kafka](https://github.com/rahulsinghai/jmeter-backend-listener-kafka) -JMeter插件，用于将测试结果发送到Kafka服务器.
  - [jmeter-listener](https://gitlab.com/testload/jmeter-listener) -JMeter插件可将负载测试数据即时写入ClickHouse，InfluxDB，ElasticSearch.
-自定义和不推荐使用
  - [Using Matplotlib & Python](https://www.metaltoad.com/blog/plotting-your-load-test-jmeter) -使用Matplotlib绘图工具和Python绘制JMeter负载测试结果.
  - [Statistical Aggregate Report](http://rubenlaguna.com/wp/better-jmeter-graphs/) -自定义统计汇总报告侦听器，可增强结果的可视化效果.
  - [JChav](https://github.com/d6y/jchav) -JMeter图表历史和可视化库.
  -JMeter资讯主页： [howto](http://seangkuan.blogspot.com/2015/06/jmeter-dashboard-realtime-monitoring-of.html), [sources](https://github.com/vincentskooi/JMeterDashboard) -实时监控JMeter负载测试.
  - [Using CMDRunner & Powershell](http://performancewebautoamtionother.blogspot.com/2015/12/jmeter-create-graphs-with-cmdrunner.html) -使用具有Powershell并行执行功能的CMDRunner创建JMeter图.

## Performance Testing

### Streaming Protocols

- [Easy and realistic Load Testing of HTTP Live Streaming (HLS) with Apache JMeter](https://www.ubik-ingenierie.com/blog/easy-and-realistic-load-testing-of-http-live-streaming-hls-with-apache-jmeter/)
- [Using JMeter to Load Test Live HLS Concurrency of Wowza Streaming Engine](https://www.realeyes.com/blog/wowza-streaming/)
- [Load testing HLS with Ruby JMeter](https://www.flood.io/blog/load-testing-hls-with-ruby-jmeter)
- [Media Live Streaming Load Testing with JMeter](https://www.blazemeter.com/live-streaming/) -BlazeMeter的文章集（[HLS](https://www.blazemeter.com/hls/), [RTMP](https://www.blazemeter.com/rtmp/)，WS，播客等）.
- [HLS JMeter Plugin](https://github.com/Blazemeter/HLSPlugin)

### Mobile Apps

- [Record iOS application HTTP requests](http://www.testautomationguru.com/jmeter-record-ios-application-http-requests/)
- [Load Testing Mobile Apps Made Easy](https://www.blazemeter.com/blog/load-testing-mobile-apps-made-easy/)
- [Performance Testing for Native Mobile Apps](https://www.blazemeter.com/blog/view-webcast-performance-testing-native-mobile-apps/)

### Mainframe Environments

- [JMeter RTE Plugin](https://github.com/Blazemeter/RTEPlugin) -JMeter RTE（远程终端仿真器协议）插件，用于测试大型机应用程序.

### Correlation

- [Correlation Recorder Plugin](https://github.com/Blazemeter/CorrelationRecorder) -JMeter插件，可通过在记录时提供变量的自动关联来简化具有动态变量的应用程序的记录过程.
- [Siebel CRM Plugin](https://github.com/Blazemeter/SiebelPlugin) -JMeter插件通过在记录时*（不推荐使用）*提供变量的自动关联来简化Siebel CRM应用程序的脚本.
- [ULP Auto-correlator Plugin](https://www.ubik-ingenierie.com/blog/ubikloadpack-autocorrelator-plugin-help/) -适用于Oracle和基于Vaadin的应用程序的商业插件 [Ubik Load Pack](#plugins).

## APM Integration

与应用程序性能监视（APM）工具集成，以分析应用程序服务器，数据库服务器和Web服务的性能.

- [Servers Performance Monitoring Plugin](https://jmeter-plugins.org/wiki/PerfMon/) -来自的服务器监控插件 [JMeter Plugins](#plugins) 项目.
- [CA App Synthetic Monitor](https://asm.ca.com/en/feature/transaction-monitoring-web-application-testing.html) -带有JMeter支持的事务监视和测试解决方案.
-动态痕迹
  - [Dynatrace and JMeter integration](https://www.dynatrace.com/support/help/setup-and-configuration/integrations/third-party-integrations/test-automation-frameworks/dynatrace-and-jmeter-integration/)
  - [Integrate web API performance monitoring in JMeter](https://www.dynatrace.com/support/doc/appmon/continuous-delivery-test-automation/test-automation-tutorials/integrate-web-api-performance-monitoring-in-jmeter/)
- [JMeter integration with AppDynamics](https://docplayer.net/62851982-Jmeter-integration-with-appdynamics.html) -与JMeter集成的APM和EUM解决方案.
-使用New Relic和JMeter进行性能修复： [part 1](https://moduscreate.com/blog/performance-remediation-using-new-relic-jmeter-part-1-3/), [part 2](https://moduscreate.com/blog/performance-remediation-using-new-relic-jmeter-part-2-3/)

## Plugins

- [JMeter Plugins list](https://docs.google.com/spreadsheets/d/1FYMw3zCMr2Y37QCG_vOyC3HyrLxxi7x5I3khWLj3isU/) -可用插件和扩展列表.
- [JMeter Plugins](https://jmeter-plugins.org/) -Apache JMeter的独立插件集，其中插件管理器引用了许多插件并简化了安装.
- [Ubik Load Pack](https://ubikloadpack.com/) -Apache JMeter的生产力扩展.

## Extending JMeter

- [JMeter Developer Manual](https://cwiki.apache.org/confluence/display/jmeter/DeveloperManual)
- [How to write a plugin for JMeter](https://jmeter.apache.org/usermanual/jmeter_tutorial.html)
- [How to build a JMeter plugin utilising groovy](https://web.archive.org/web/20180225144718/http://artur.ejsmont.org/blog/content/how-to-build-a-jmeter-plugin-utilising-groovy)
- [How to create a plugin in JMeter](https://stackoverflow.com/questions/20422640/how-to-create-a-plugin-in-jmeter)
- [Custom JMeter Samplers and Config Elements](http://codyaray.com/2014/07/custom-jmeter-samplers-and-config-elements)
- [Implement Custom JMeter Samplers](https://dzone.com/articles/implement-custom-jmeter-samplers)

## IDE Integration

- [Intellij IDEA IDE Plugin](https://plugins.jetbrains.com/plugin/7013-jmeter-plugin) -从Intellij IDEA创建运行配置并运行JMeter测试.
- [JMeter + Eclipse HOWTO](https://cwiki.apache.org/confluence/display/jmeter/JMeterAndEclipseHowTo) -使用Eclipse IDE开发JMeter项目.
- [NetBeans JMeter Kit](http://plugins.netbeans.org/plugin/49923/jmeter) -用于NetBeans IDE的JMeter集成模块.
- [Using a Load Generator in NetBeans IDE](https://netbeans.org/kb/docs/java/profile-loadgenerator.html)

## Editors

*除标准JMeter GUI和XML编辑器外，还提供JMX文件的替代编辑器.

- [BlocklyJMX Editor](https://jmeter-plugins.org/editor/) -基于Web的JMeter测试计划文件查看器和编辑器（ [JMeter Plugins](#plugins) 项目）.
- [JMX Enhancer](https://www.jmxenhancer.com/) -加快JMeter测试计划准备的解决方案.
- [jmx.js](http://www.vinodkd.org/jmx.js/) -JMeter JMX文件的基于Web的编辑器*（没有更多更新）*.

## JMeter Performance

- [JMeter Performance](https://cwiki.apache.org/confluence/display/jmeter/JMeterPerformance) -JMeter跨版本的性能演变.
- [JMeter Performance and Tuning Tips](https://www.ubik-ingenierie.com/blog/jmeter_performance_tuning_tips/) -由Ubik Ingenierie提供.
- [JMeter Performance and Tuning Tips](https://www.blazemeter.com/blog/jmeter-performance-and-tuning-tips) -BlazeMeter.

## Tips & Tricks

- [JMeter tips](http://www.webwob.com/html/jmeter_tips.html) -JMeter便笺簿技巧.

## Books
<!--lint ignore double-link-->
- [Apache JMeter: A Practical Beginner's Guide to Automated Testing and Performance Measurement for Your Websites](https://books.google.com/books?id=nX8oKIEvUcYC) -艾米丽·H·哈利利（[Packt Publishing](https://www.packtpub.com/product/apache-jmeter/9781847192950)).
- [Performance Testing with JMeter 2.9](https://books.google.com/books?id=fpWmv3wPT64C) -巴约·艾琳（[Packt Publishing](https://www.packtpub.com/product/performance-testing-with-jmeter-2-9/9781782165842) ）; 如何使用Apache JMeter测试Web应用程序的指南，以及一些实际的示例.
- [Performance Testing with JMeter, 2nd Edition](https://books.google.com/books?id=6ditCAAAQBAJ) -巴约·艾琳（[Packt Publishing](https://www.packtpub.com/product/performance-testing-with-jmeter-second-edition/9781784394813)).
- [Performance Testing with JMeter 3, 3rd Edition](https://books.google.com/books?id=BedDDwAAQBAJ) -巴约·艾琳（[Packt Publishing](https://www.packtpub.com/product/performance-testing-with-jmeter-3-third-edition/9781787285774)).
- [JMeter Cookbook](https://books.google.com/books?id=gJUeBQAAQBAJ) -巴约·艾琳（[Packt Publishing](https://www.packtpub.com/product/jmeter-cookbook/9781783988280) ）;  70个有见地和实用的食谱，可帮助成功使用Apache JMeter.
- [JMeter by Example](https://books.google.com/books?id=iWeJDAEACAAJ) -赛马塔姆（Sai Matam）和贾格迪普（Jagdeep Jain）（[Leanpub](https://leanpub.com/jmeterbyexample) ）; 一个简单，实用的分步教程来衡量网站的性能.
- [Pro Apache JMeter: Web Application Performance Testing](https://books.google.com/books?id=YJ4xDwAAQBAJ) -赛马塔姆（Sai Matam）和贾格迪普（Jagdeep Jain）（[Apress](https://www.apress.com/gp/book/9781484229606)).
- [Master Apache JMeter: From load testing to DevOps](https://books.google.com/books?id=D_amDwAAQBAJ) -作者：安东尼奥·戈麦斯·罗德里格斯，布鲁诺·德米翁（Milamber）和菲利普·莫瓦（Philippe Mouawad）（[Leanpub](https://leanpub.com/master-jmeter-from-load-test-to-devops), [Packt Publishing](https://www.packtpub.com/product/master-apache-jmeter-from-load-testing-to-devops/9781839217647)).
- [Maîtriser JMeter: Du Test de charge à Devops](http://samples.leanpub.com/maitriser-jmeter-du-test-de-charge-a-devops-sample.pdf) -作者：安东尼奥·戈麦斯·罗德里格斯，布鲁诺·德米翁（Milamber）和菲利普·莫瓦（Philippe Mouawad）（[Leanpub](https://leanpub.com/maitriser-jmeter-du-test-de-charge-a-devops)）*（法语）*.
- [Advanced JMeter Testing](https://leanpub.com/advanced_jmeter_testing) -由Penny Curich（[Leanpub](https://leanpub.com/advanced_jmeter_testing)），指导编写针对Apache JMeter 5.0的自定义组件.

## Trainings & Courses

- [JMeter: Performance and Load Testing](https://www.linkedin.com/learning/jmeter-performance-and-load-testing) -通过领英学习.
- [JMeter Training Courses](https://www.nobleprog.co.uk/jmeter-training) -通过NobleProg.
- [BlazeMeter University](https://www.blazemeter.com/university/) -BlazeMeter.
- [JMeter Courses collection](https://www.udemy.com/topic/jmeter/) -Udemy.
- [JMeter Training Course](http://www.absofttrainings.com/jmeter-training-course-and-tutorials/) -由ABSoft培训.
- [Web Applications (and Mobile Apps) Performance Testing with JMeter](http://pragmatictestlabs.com/web-applications-mobile-apps-performance-testing-jmeter/) -由实用测试实验室提供.
- [Training courses on Load Testing with Apache JMeter](https://www.ubik-ingenierie.com/blog/jmeter-trainings-by-contributors-and-committers/) -由Ubik Ingenierie提供.
- [Apache JMeter Testing Courses](https://qainsights.com/services/) -通过QAInsights.
- [JMeter Getting Started Course](https://www.pluralsight.com/courses/jmeter-getting-started) -通过Pluralsight.

## Community

### Blogs

- [BlazeMeter Blog](https://www.blazemeter.com/jmeter/) -有关JMeter和性能测试的BlazeMeter博客.
- [Ubik Load Pack Blog](https://www.ubik-ingenierie.com/blog/category/jmeter/) -Ubik Ingenierie博客.
- [TestAutomationGuru Blog](http://www.testautomationguru.com/category/jmeter/) -有关测试自动化的技术博客.
- [RedLine13 Blog](https://www.redline13.com/blog/tag/jmeter/) -RedLine13博客中的JMeter文章.
- [Flood.io Blog](https://www.flood.io/blog) -从Flood IO加载测试思想，故事和想法.
- [JMeter Blog](https://shantonusarker.blogspot.com/p/jmeter.html) -另一个使用JMeter进行性能和自动化测试的博客.
- [OctoPerf Blog](https://octoperf.com/categories/jmeter/) -关于JMeter和负载测试的OctoPerf博客.
- [Abstracta JMeter Archives](https://abstracta.us/blog/tag/jmeter/) -关于JMeter的Abstracta博客.
- [JMeter Tips](http://jmeter-tips.blogspot.com/) -关于Apache JMeter和Web应用程序性能测试的博客*（没有更多更新）*.
- [JMeter Expert Blog](http://jmeter-expert.blogspot.com/) -JMeterExpert博客*（没有更多更新）*.

### Forums
<!--lint ignore double-link-->
- [JMeter Google Group](https://groups.google.com/forum/#!forum/ptgram24)
- [JMeterPlugins Google Group](https://groups.google.com/forum/#!forum/jmeter-plugins)
- [JMeter Nabble Forum](http://www.jmeter-archive.org/)
- [JMeter SQAforums](http://www.sqaforums.com/postlist.php?Cat=0&Board=UBB54)
- [JMeter - Тестирование производительности](https://software-testing.ru/forum/index.php?/forum/206-jmeter-testirovanie-proizvoditelnosti/) -Software-Testing.ru *（俄语）*的讨论板.

### Newsletters

- [JMeter Community](https://www.reddit.com/r/jmeter/) -Reddit.

### Twitter

- [@ApacheJMeter](https://twitter.com/apachejmeter) -Apache JMeter负载测试工具的官方Twitter帐户.
- [@jmeter_plugins](https://twitter.com/jmeter_plugins) -JMeter负载测试工具的自定义插件项目的Twitter帐户.
- [@BlazeMeter](https://twitter.com/BlazeMeter) -基于JMeter的DevOps性能工程平台Blazemeter的官方Twitter帐户.
- [@masterjmeter](https://twitter.com/masterjmeter) -的官方帐户 [Master Apache JMeter from Load Testing to DevOps](#books) 书.
- [@ubikloadpack](https://twitter.com/ubikloadpack) -的Twitter帐户 [Ubik Load Pack](#plugins)，用于视频流和复杂协议负载测试的自定义JMeter插件.

### Q&A

- [JMeter @ Stack Overflow](https://stackoverflow.com/questions/tagged/jmeter)
- [JMeter Slack workspace](https://jmeterusers.slack.com/)
- [JMeter @ gitter](https://gitter.im/aliesbelik/jmeter-chat)

## Related

### Awesome Lists

- [Awesome](https://github.com/sindresorhus/awesome) -原始列表的原始列表.
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness) -惊人的超赞的精选清单.
- [Awesome Software Quality](https://github.com/ligurio/awesome-software-quality) -免费软件测试和验证资源列表.
- [Awesome Testing](https://github.com/TheJambo/awesome-testing) -精选的测试资源列表.
- [Awesome Page Speed Metrics](https://github.com/csabapalfi/awesome-pagespeed-metrics) -有助于了解页面速度和用户体验的指标.
- [Awesome Web Performance Optimization](https://github.com/davidsonfellipe/awesome-wpo) -Web性能优化的精选列表.
- [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability) -可扩展，可靠和高性能的大型系统的模式.
- [Awesome Site Reliability Engineering](https://github.com/dastergon/awesome-sre) -网站可靠性和生产工程资源的精选列表.
- [Awesome inspectIT](https://github.com/inspectit-labs/awesome-inspectit) -开源Java应用性能管理工具.
- [Awesome Tsung](https://github.com/aliesbelik/awesome-tsung) -用Erlang开发的开源多协议分布式负载测试工具.
- [Awesome Gatling](https://github.com/aliesbelik/awesome-gatling) -基于Scala，Akka和Netty的开源负载和性能测试框架.
- [Awesome k6](https://github.com/k6io/awesome-k6) -开源，以开发人员为中心的性能监控和负载测试解决方案.

## Contributing

欢迎捐款！<br>
请看看 [contribution guidelines](https://github.com/aliesbelik/awesome-jmeter/blob/master/CONTRIBUTING.md) 第一.

<a rel="license" href="https://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by/4.0/88x31.png" /></a>
