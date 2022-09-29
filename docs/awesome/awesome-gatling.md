<div class="github-widget" data-repo="aliesbelik/awesome-gatling"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Gatling [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!--lint ignore double-link-->
[<img src="https://raw.githubusercontent.com/aliesbelik/awesome-gatling/master/assets/images/gatling-logo.svg?sanitize=true" align="right" width="260" alt="Gatling">](https://gatling.io/)
<!--lint ignore double-link-->
精选的资源集合，涵盖负载测试的各个方面，使用 [Gatling](https://gatling.io/) 和相关的东西：插件、集成、测试技术、DevOps 实践等.
<!--lint ignore double-link-->
> [Gatling](https://gatling.io/) 是一个基于 Scala、Akka 和 Netty 的开源负载和性能测试框架.



## Official Resources
<!--lint ignore double-link-->
- [Homepage](https://gatling.io/)
  - [Gatling](https://gatling.io/open-source/) - 开源版本.
  - [Gatling Enterprise](https://gatling.io/enterprise/) - 企业版（以前称为 Gatling FrontLine），具有高级分析和集成.
- [Documentation](https://gatling.io/docs/gatling/)
- [Source code](https://github.com/gatling/gatling)

## Getting Started

- [Load testing with Gatling.io](https://blog.pragmatists.com/load-testing-with-gatling-io-2a128fccfb3e)
- [A first look at Gatling, a DSL based load test tool](https://callistaenterprise.se/blogg/teknik/2014/04/16/a-first-look-at-gatling-a-dsl-based-load-test-tool/)
- [Gatling: Take your performance tests to the next level](https://www.thoughtworks.com/insights/blog/gatling-take-your-performance-tests-next-level)
- [Load Testing with Gatling. The Complete Guide](https://www.james-willett.com/gatling-load-testing-complete-guide/)
- [Performance testing with Gatling](https://automationrhapsody.com/performance-testing-with-gatling/)

## Tutorials

- [Load testing gRPC services with Gatling](https://medium.com/@georgeleung_7777/load-testing-grpc-services-with-gatling-990025c77055)
- [Creating a custom Gatling protocol for AWS Lambda](https://callistaenterprise.se/blogg/teknik/2016/11/26/gatling-custom-protocol/)
- [Load testing ZeroMQ with a custom DSL for Gatling](http://mintbeans.com/load-testing-zeromq-with-gatling/)

## Distributed Testing

- [Scaling out with Gatling](https://gatling.io/docs/gatling/guides/scaling_out/) - 使用来自官方 Gatling 文档的多台机器托管的多个 Gatling 实例的配方.
- [Distributed load testing with Gatling and Kubernetes](https://medium.com/de-bijenkorf-techblog/https-medium-com-annashepeleva-distributed-load-testing-with-gatling-and-kubernetes-93ebce26edbe)
- [Gatling – Scaling Out Your Load Tests](https://web.archive.org/web/20210625094528/http://www.nimrodstech.com/gatling-cluster-load-testing/)
- [Distributed Gatling](https://github.com/Abiy/distGatling) - 在分布式/集群环境中运行 Gatling 模拟测试的解决方案.
- [gatling-operator](https://github.com/st-tech/gatling-operator) - 使用 Kubernetes 算子自动化分布式 Gatling 负载测试.

## Tools

### Plugins

- [gatling-sbt-plugin](https://github.com/gatling/gatling-sbt-plugin) - Gatling SBT 插件将 Gatling 与 SBT 集成，允许使用 Gatling 作为测试框架.
- [gatling-build-plugin](https://github.com/gatling/gatling-build-plugin) - 一个 SBT 插件，用于在 Gatling 的项目构建中共享通用设置.
- [gatling-maven-plugin](https://github.com/gatling/gatling-maven-plugin) - Gatling Maven 扩展.
- [gatling-gradle-plugin](https://github.com/gatling/gatling-gradle-plugin) - Gradle 的 Gatling 插件.
- [gatling-remote-sbt](https://github.com/Pravoru/gatling-remote-sbt) - 用于 Gatling 负载测试的远程执行插件.
- [gatling-junitrunner](https://github.com/Pravoru/gatling-junitrunner) - 围绕 Gatling 模拟的 JUnit 包装器.
- [gatling-grpc](https://github.com/phiSgr/gatling-grpc) - gRPC 的 Gatling 负载测试插件.
- [gatling-aws](https://github.com/callistaenterprise/gatling-aws) - 适用于 AWS Lambda 的 Gatling 自定义协议.
- [gatling-xmpp-protocol](https://github.com/TLmaK0/gatling-xmpp-protocol) - XMPP 协议，用于使用 Gatling 对 XMPP 服务器进行压力测试.
- [gatling-jwt](https://bitbucket.org/atlassianlabs/gatling-jwt/) - 对 Gatling 2.0 的扩展，以帮助发出 JWT 签名请求.
- [gatling-mqtt](https://github.com/mnogu/gatling-mqtt) - 用于压力测试 MQTT 的 Gatling 插件.
- [gatling-kafka](https://github.com/mnogu/gatling-kafka) - 用于压力测试 Apache Kafka 协议的 Gatling 插件.
- [gatling-kafka-plugin](https://github.com/Tinkoff/gatling-kafka-plugin) - 在 Gatling 中支持 Kafka 的插件.
- [gatling-amqp-plugin](https://github.com/Tinkoff/gatling-amqp-plugin) - 在 Gatling (3.2.x) 中使用 AMQP 支持性能测试的插件.
- [gatling-jdbc-plugin](https://github.com/Tinkoff/gatling-jdbc-plugin) - 用于 JDBC 支持的简单 Gatling 插件.
- [gatling-picatinny](https://github.com/Tinkoff/gatling-picatinny) - 具有大量扩展 Gatling DSL 的有用功能的库.
- [gatling-sql](https://github.com/tmcgrath/gatling-sql) - 用于 JDBC 或 Spark Thrift Server 压力测试的 Gatling 扩展.
- [gatling-tcp-extensions](https://github.com/scalecube/gatling-tcp-extensions) - 加特林的 TCP 扩展.
- [gatling-thrift](https://github.com/3tty0n/gatling-thrift) - Apache Thrift 的 Gatling 第三方插件.
- [gatling-bolt](https://github.com/sarmbruster/gatling-bolt) - 支持用于 Gatling 的 Neo4j Bolt 协议.
- [gatling-zeromq](https://github.com/softwaremill/gatling-zeromq) - ZeroMQ 协议的 Gatling 压力测试插件.
- [gatling-dubbo](https://github.com/youzan/gatling-dubbo) - 用于在 Apache Dubbo 上运行负载测试的 Gatling 插件.
- [gatling-cql](https://github.com/gatling-cql/GatlingCql) - 加特林支持 Apache Cassandra CQL.

### Frameworks

- [Kraken](https://github.com/OctoPerf/kraken) - 基于 Gatling 的负载测试 IDE [OctoPerf](https://octoperf.com/categories/kraken/).
- [Karate Gatling](https://karatelabs.github.io/karate/karate-gatling/) - 重新使用空手道 API 测试作为 Gatling 执行的性能测试.
- [Taurus](https://gettaurus.org/docs/Gatling/) - Taurus 框架中的 Gatling Executor.
- [Carrier](https://getcarrier.io/) - 连续测试执行平台，能够使用定制的 JMeter 和 Gatling 容器执行负载测试.

### Reporting

- [gatling-report](https://github.com/nuxeo/gatling-report) - 解析 Gatling simulation.log 文件以输出 CSV 统计数据或使用 Plotly 图表构建 HTML 报告.
- [gatling2allure](https://github.com/biski/gatling2allure) - 将 Gatling 日志转换为 Allure 报告.

### Miscellaneous

- [dakiya](https://github.com/rupeshmore/dakiya) - 将 Postman 集合转换为 Gatling 脚本.
- [gatling.g8](https://github.com/gatling/gatling.g8) - 加特林的 Giter8 模板.
- [gatling-template.g8](https://github.com/Tinkoff/gatling-template.g8) - 用于 Gatling 性能测试项目的 Giter8 模板.

## CI

- [Gatling Jenkins Plugin](https://github.com/jenkinsci/gatling-plugin) - [Jenkins plugin](https://plugins.jenkins.io/gatling/) 对于加特林.
- [run-gatling](https://github.com/liatrio/run-gatling) - GitHub Action 可轻松将 Gatling 性能测试集成到 GitHub 工作流程.

## Trainings & Courses

- [Gatling Academy](https://gatling.io/academy/)
- [Gatling Courses](https://www.udemy.com/topic/gatling/) - 由 Udemy.
- [Performance Test Automation 101: Gatling, Lighthouse, & Jenkins](https://www.educative.io/courses/performance-test-automation-101-gatling-lighthouse-jenkins) - 通过教育.

## Videos

### Talks

- [Load Testing Done Right with Gatling](https://www.youtube.com/watch?v=VUPTaPms210) - Stéphane Landelle @ Voxxed Days Belgrade 2015.

### Video Tutorials

- [Performance Testing with Gatling](https://www.youtube.com/playlist?list=PLd4gvNaNZ4T3NCWsv3zwHYlLGtr9s1-Fz) - Tomi Tiihonen 的教程系列.
- [Gatling Tutorials for Beginners](https://www.youtube.com/playlist?list=PLw_jGKXm9lIYpTotIJ-R31pXS7qqwXstt) - James Willett 的教程系列.

## Community

- [Gatling Community](https://community.gatling.io/)
- [`gatling` on Stack Overflow](https://stackoverflow.com/questions/tagged/gatling+or+scala-gatling+or+gatling-plugin)
- [`@GatlingTool` on Twitter](https://twitter.com/gatlingtool)

## Related

### Awesome Lists

- [Awesome Software Quality](https://github.com/ligurio/software-quality-wiki) - 免费软件测试和验证资源列表.
- [Awesome Testing](https://github.com/TheJambo/awesome-testing) - 精选的测试资源列表.
- [Awesome JMeter](https://github.com/aliesbelik/awesome-jmeter) - 开源负载测试和性能测量工具，用 Java 编写.
- [Awesome Tsung](https://github.com/aliesbelik/awesome-tsung) - 开源多协议分布式负载测试工具，用 Erlang 开发.
- [Awesome k6](https://github.com/grafana/awesome-k6) - 开源、以开发人员为中心的性能监控和负载测试解决方案.
- [Awesome Locust](https://github.com/aliesbelik/awesome-locust) - 用 Python 编写的开源可扩展负载测试框架.

### Other

- [How They Load Test](https://github.com/aliesbelik/how-they-load) - 有关世界各地公司如何执行负载测试的公开可用资源的精选集合.
- [Load Testing Toolkit](https://github.com/aliesbelik/load-testing-toolkit) - 用于调试、基准测试、加载和压力测试您的代码或服务的开源工具集合.

## Contributing

欢迎投稿！<br>
请看一下 [CONTRIBUTING](https://github.com/aliesbelik/awesome-gatling/blob/master/CONTRIBUTING.md) 首先是指导方针.
