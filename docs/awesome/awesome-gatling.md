<div class="github-widget" data-repo="aliesbelik/awesome-gatling"></div>
## Awesome Gatling [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!--lint ignore double-link-->
[<img src="https://raw.githubusercontent.com/aliesbelik/awesome-gatling/master/assets/images/gatling-logo.svg?sanitize=true" align="right" width="260" alt="Gatling">](https://gatling.io/)
<!--lint ignore double-link-->
A curated collection of resources covering all aspects of load testing using [Gatling](https://gatling.io/) and related stuff: plugins, integrations, testing techniques, DevOps practices, etc.
<!--lint ignore double-link-->
> [Gatling](https://gatling.io/) is an open-source load and performance testing framework based on Scala, Akka and Netty.



## Official Resources
<!--lint ignore double-link-->
- [Homepage](https://gatling.io/)
- [Documentation](https://docs.gatling.io/)
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

- [Distributed load testing with Gatling and Kubernetes](https://debijenkorf.tech/https-medium-com-annashepeleva-distributed-load-testing-with-gatling-and-kubernetes-93ebce26edbe)
- [Gatling – Scaling Out Your Load Tests](https://web.archive.org/web/20210625094528/http://www.nimrodstech.com/gatling-cluster-load-testing/)
- [Distributed Gatling](https://github.com/Abiy/distGatling) - Solution to run Gatling simulation tests in a distributed/cluster environment.
- [gatling-operator](https://github.com/st-tech/gatling-operator) - Automating distributed Gatling load testing using Kubernetes operator.

## Tools

### Plugins

- [gatling-sbt-plugin](https://github.com/gatling/gatling-sbt-plugin) - Gatling SBT plugin to integrate Gatling with SBT, allowing to use Gatling as a testing framework.
- [gatling-build-plugin](https://github.com/gatling/gatling-build-plugin) - An SBT plugin to share common settings across Gatling's projects' builds.
- [gatling-maven-plugin](https://github.com/gatling/gatling-maven-plugin) - Gatling Maven Extensions.
- [gatling-gradle-plugin](https://github.com/gatling/gatling-gradle-plugin) - Gatling plugin for Gradle.
- [gatling-remote-sbt](https://github.com/Pravoru/gatling-remote-sbt) - Remote execution plugin for Gatling load tests.
- [gatling-junitrunner](https://github.com/Pravoru/gatling-junitrunner) - JUnit wrapper around Gatling simulations.
- [gatling-grpc](https://github.com/phiSgr/gatling-grpc) - Gatling load test plugin for gRPC.
- [gatling-aws](https://github.com/callistaenterprise/gatling-aws) - Gatling custom protocol for AWS Lambda.
- [gatling-xmpp-protocol](https://github.com/TLmaK0/gatling-xmpp-protocol) - XMPP protocol for stress test XMPP servers with Gatling.
- [gatling-jwt](https://bitbucket.org/atlassianlabs/gatling-jwt/) - An extension to Gatling 2.0 to help make JWT-signed requests.
- [gatling-mqtt](https://github.com/mnogu/gatling-mqtt) - A Gatling plugin for stress testing MQTT.
- [gatling-kafka](https://github.com/mnogu/gatling-kafka) - A Gatling plugin for stress testing Apache Kafka protocol.
- [gatling-kafka-plugin](https://github.com/Tinkoff/gatling-kafka-plugin) - Plugin for support Kafka in Gatling.
- [gatling-amqp-plugin](https://github.com/Tinkoff/gatling-amqp-plugin) - Plugin for support performance testing with AMQP in Gatling (3.2.x).
- [gatling-jdbc-plugin](https://github.com/Tinkoff/gatling-jdbc-plugin) - Simple Gatling plugin for JDBC support.
- [gatling-picatinny](https://github.com/Tinkoff/gatling-picatinny) - Library with a bunch of useful functions that extend Gatling DSL.
- [gatling-sql](https://github.com/tmcgrath/gatling-sql) - Gatling extension for JDBC or Spark Thrift Server stress testing.
- [gatling-tcp-extensions](https://github.com/scalecube/gatling-tcp-extensions) - TCP extensions for Gatling.
- [gatling-thrift](https://github.com/3tty0n/gatling-thrift) - Gatling third party plugin for Apache Thrift.
- [gatling-bolt](https://github.com/sarmbruster/gatling-bolt) - Support Neo4j Bolt protocol for Gatling.
- [gatling-zeromq](https://github.com/softwaremill/gatling-zeromq) - A Gatling stress test plugin for ZeroMQ protocol.
- [gatling-dubbo](https://github.com/youzan/gatling-dubbo) - A Gatling plugin for running load tests on Apache Dubbo.

### Frameworks

- [Kraken](https://github.com/OctoPerf/kraken) - Load testing IDE based on Gatling by OctoPerf.
- [Karate Gatling](https://karatelabs.github.io/karate/karate-gatling/) - Re-use Karate API-tests as performance tests executed by Gatling.
- [Taurus](https://gettaurus.org/docs/Gatling/) - Gatling Executor in Taurus framework.
- [Carrier](https://getcarrier.io/) - Continuous test execution platform with ability to perform load testing using customized JMeter and Gatling containers.

### Reporting

- [gatling-report](https://github.com/nuxeo/gatling-report) - Parse Gatling simulation.log files to output CSV stats or build HTML reports with Plotly charts.
- [gatling2allure](https://github.com/biski/gatling2allure) - Convert Gatling log to Allure report.

### Sandbox

- [gatling-scaffold](https://github.com/robsonbittencourt/gatling-scaffold) - Base for load test project using Gatling, InfluxDB and Grafana.
- [perfiz](https://github.com/znsio/perfiz) - A dockerised API performance test setup based on Gatling with Grafana dashboards and Prometheus monitoring.

### Miscellaneous

- [dakiya](https://github.com/rupeshmore/dakiya) - Convert Postman collections to Gatling scripts.
- [gatling.g8](https://github.com/gatling/gatling.g8) - Giter8 template for Gatling.
- [gatling-template.g8](https://github.com/Tinkoff/gatling-template.g8) - A Giter8 template for Gatling performance test project.

## CI

- [Gatling Jenkins Plugin](https://github.com/jenkinsci/gatling-plugin) - [Jenkins plugin](https://plugins.jenkins.io/gatling/) for Gatling.
- [run-gatling](https://github.com/liatrio/run-gatling) - GitHub Action to easily integrate Gatling performance tests to GitHub workflows.

## Trainings & Courses

- [Gatling Academy](https://academy.gatling.io/)
- [Gatling Courses](https://www.udemy.com/topic/gatling/) - By Udemy.
- [Performance Test Automation 101: Gatling, Lighthouse, & Jenkins](https://www.educative.io/courses/performance-test-automation-101-gatling-lighthouse-jenkins) - By Educative.

## Videos

### Talks

- [Load Testing Done Right with Gatling](https://www.youtube.com/watch?v=VUPTaPms210) - Stéphane Landelle @ Voxxed Days Belgrade 2015.
- [Load Testing Crash Course with Gatling](https://www.youtube.com/watch?v=RiM1GsVSbzM) - Stéphane Landelle @ Devoxx Belgium 2022.
- [Load Testing Made Easy with Gatling](https://www.youtube.com/watch?v=8Eplj8BvugA) - Rafał Piotrowski @ Scala Days 2023 Madrid.

### Video Tutorials

- [Performance Testing with Gatling](https://www.youtube.com/playlist?list=PLd4gvNaNZ4T3NCWsv3zwHYlLGtr9s1-Fz) - Tutorial series by Tomi Tiihonen.
- [Gatling Tutorials for Beginners](https://www.youtube.com/playlist?list=PLw_jGKXm9lIYpTotIJ-R31pXS7qqwXstt) - Tutorial series by James Willett.

## Community

- [Gatling Community](https://community.gatling.io/)
- [`gatling` on Stack Overflow](https://stackoverflow.com/questions/tagged/gatling+or+scala-gatling+or+gatling-plugin)
- [`@GatlingTool` on Twitter](https://twitter.com/gatlingtool)

## Related

### Awesome Lists

- [Awesome Software Quality](https://github.com/ligurio/sqa-wiki) - A list of free software testing and verification resources.
- [Awesome Testing](https://github.com/TheJambo/awesome-testing) - A curated list of testing resources.
- [Awesome JMeter](https://github.com/aliesbelik/awesome-jmeter) - Open-source load testing and performance measurement tool, written in Java.
- [Awesome Tsung](https://github.com/aliesbelik/awesome-tsung) - Open-source multi-protocol distributed load testing tool, developed in Erlang.
- [Awesome k6](https://github.com/grafana/awesome-k6) - Open-source, developer-centric performance monitoring and load testing solution.
- [Awesome Locust](https://github.com/aliesbelik/awesome-locust) - Open-source scalable load testing framework written in Python.

### Other

- [How They Load Test](https://github.com/aliesbelik/how-they-load) - A curated collection of publicly available resources on how companies around the world perform load testing.
- [Load Testing Toolkit](https://github.com/aliesbelik/load-testing-toolkit) - Collection of open-source tools for debugging, benchmarking, load and stress testing your code or services.

## Contributing

Contributions are welcome!<br>
Please take a look at the [CONTRIBUTING](https://github.com/aliesbelik/awesome-gatling/blob/master/CONTRIBUTING.md) guidelines first.
