<div class="github-widget" data-repo="grafana/awesome-k6"></div>
<div align="center">
  <a href="https://k6.io/">
    <img src="https://raw.githubusercontent.com/grafana/awesome-k6/master/assets/bert.png" alt="k6 mascot" width="300px">
  </a>

<!--lint disable awesome-heading-->
## Awesome k6 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!--lint enable awesome-heading-->

</div>

社区在（测试） <a href="https://k6.io/">k6</a>上收集的内容.


想帮助改进这份清单吗？ 耶，太棒了！ 不过，在开始之前，请先查看我们 [code of conduct](https://github.com/grafana/awesome-k6/blob/master/code_of_conduct.md) 和 [contribution guidelines](https://github.com/grafana/awesome-k6/blob/master/contributing.md).



## Extensions
- [GitHub Topic: xk6](https://github.com/topics/xk6) - 探索带有 xk6 标签的 k6 扩展.

## Articles

- [k6 Learn](https://github.com/grafana/k6-learn) - 解释负载测试的原理以及如何使用 k6 进行负载测试的实例.
- [Beginner's guide to load testing with k6](https://link.medium.com/npI9sjDyyjb) - 多个部分的入门指南，帮助您开始使用k6.
- [Distributed load testing with k6](https://feryn.eu/speaking/distributed-load-testing-k6-confoo23/) - Thijs Feryn 出席 2023 年蒙特利尔 ConFoo
- [Load Testing with k6](https://medium.com/@dan.ryan.emmons/qa-load-testing-with-k6-io-c11c2afced04) - 简要概述 k6 的特性和功能.
- [Integrating k6 with Apache Kafka](https://k6.io/blog/integrating-k6-with-apache-kafka) - 将输出从 k6 发送到 Apache Kafka.
- [Test and visualize with InfluxDB, Grafana and K6](https://medium.com/@naoko.reeves/load-test-with-k6-and-visualize-with-influxdb-and-grafana-c6097a6f6d0a) - 设置负载测试并使用 grafana 仪表板可视化它们.
- [Open source load testing tool review 2020](https://k6.io/blog/comparing-best-open-source-load-testing-tools) - 最流行的开源负载测试工具的详细比较.
- [Load Testing Your API with Swagger/OpenAPI and k6](https://k6.io/blog/load-testing-your-api-with-swagger-openapi-and-k6) - 根据 OpenAPI 规范生成 k6 负载测试脚本.
- [Load Testing Your API with Postman](https://k6.io/blog/load-testing-with-postman-collections/) - 如何使用 Postman 集合来加载测试您的 API.
- [Load Testing & Black Friday capacity planning](https://medium.com/back-market-engineering/how-back-market-sres-prepared-for-black-friday-5f017f343408) - Back Market 如何通过基于 k6 的负载测试为黑色星期五做准备.
- [Load Testing SQL Databases with k6](https://k6.io/blog/load-testing-sql-databases-with-k6/) - 如何使用 xk6-sql 扩展直接测试 SQL 数据库. 
- [Introducing TestRail in your K6 tests](https://dev.to/kwidera/introducing-testrail-in-you-k6-tests-eck) - 向 TestRail 报告 k6 输出. 
- [Beautiful Load Testing With K6 and Docker Compose](https://medium.com/swlh/beautiful-load-testing-with-k6-and-docker-compose-4454edb3a2e3) - 如何使用 Docker Compose、K6、InfluxDB 和 Grafana 的完美组合运行负载测试.
- [Load Testing with Azure DevOps and k6](https://medium.com/microsoftazure/load-testing-with-azure-devops-and-k6-839be039b68a) - 如何设置 Azure DevOps 以使用 k6、handleCallback 和 JUnit 执行自动负载测试.
- [K6 — Custom Slack Integration: Metrics are the Magic of Tests](https://medium.com/geekculture/k6-custom-slack-integration-metrics-are-the-magic-of-tests-527aaf613595) - 如何使用 handleSummary 回调将 k6 输出结果发送到 Slack.
- [Load testing with k6](https://levelup.gitconnected.com/load-testing-with-k6-48488c7946bb) - 使用 k6 进行负载、浸泡、压力、尖峰和烟雾测试.
- [How to write three times fewer lines of code when doing load testing](https://dev.to/tarantool/how-to-write-three-times-fewer-lines-of-code-when-doing-load-testing-9lb) - 在 Go 中构建 k6 扩展以测试 Tarantool.
- [Load Testing. k6 + TypeScript + Azure DevOps](https://alex-klaus.com/load-test-k6-typescript-azure/)
- [Performance testing with k6](https://blog.shanelee.name/2021/12/15/performance-testing-with-k6/) - 关于 API 性能测试，使用 Open API 和 TypeScript.
- [k6 introduces browser automation and Prometheus support in k6 OSS](https://grafana.com/blog/2021/11/24/k6-introduces-browser-automation-and-prometheus-support-in-k6-oss/) - 来自 Grafana 博客：ObservabilityCON 2021 的功能公告.
- [Testing shift left observability with the Grafana Stack, OpenTelemetry, and k6](https://grafana.com/blog/2021/12/06/testing-shift-left-observability-with-the-grafana-stack-opentelemetry-and-k6/) - 来自 Grafana 博客：摩根大通平台工程执行总监的总结，Vinodh Ravi 在 ObservabilityCON 2021 上的演讲. 

- [Umbraco 9 - What a Performance!](https://moriyama.co.uk/about-us/news/blog-umbraco-9-what-a-performance/) - 测试 Azure 上 Umbraco v9 与 Umbraco v8 的性能，并比较 Windows 与 Linux.
- [On maintaining a k6 codebase, Part 1](https://filfreire.com/posts/k6_tricks_ep1) - 维护具有挑战性的 k6 负载测试代码库的个人技巧.
- [Distributed Load Testing With K6](https://engineering.empathy.co/distributed-load-testing-with-k6/) - 使用 k6-operator 和 Argo 工作流设置分布式执行. 
- [Load testing with k6 and k8s](https://www.toucantoco.com/en/tech-blog/tech-blog/load-testing-with-k6-and-k8s) - Toucan DevOps 团队解释了为什么他们选择 k6 作为他们的负载测试工具，以及他们如何在 k8s 上部署它

## Videos

- [k6 YouTube Channel](https://www.youtube.com/c/k6test)
- [How to use k6 Cloud for load testing](https://www.youtube.com/watch?v=ncxCIuo5tUU&list=PLJdv3RhAQXNGkRCp7Q0k77n5jif4qjz2o) - 用于 k6 Cloud 入门的一系列快速视频.
- [Intro to load testing with k6 and Grafana (k6 data source plugin and Prometheus Remote Write)](https://www.youtube.com/watch?v=tFsIgbqXbxM)
- [From Grafana ObservabilityCON: Intro to using k6 load testing with the Grafana observability stack](https://grafana.com/go/observabilitycon/2021/k6-load-testing/)
- [From Grafana ObservabilityCON: Building performance tests into your CI pipeline with k6 and Grafana, w/ Matthew Churcher, QA Engineer at Vonage](https://grafana.com/go/observabilitycon/2021/performance-testing-vonage/)
- [EveryoneCanContribute cafe: Load Performance Testing with k6](https://youtu.be/_ty40gSaaw8)
- [Playlist - What others says about k6](https://www.youtube.com/playlist?list=PLJdv3RhAQXNExTjuYN9ukawFHB7ucuejp)
  - [What is K6 & How to get started with k6](https://www.youtube.com/watch?v=ZAq87eZ1w2U) - 使用 k6 Extensions for Observability 的教程“Is it Observable?”
  - [Website Performance + Load Testing with K6 (k6.io) in 5 MINUTES!](https://www.youtube.com/watch?v=brasMBAezJY) - k6 的介绍性概述，展示了如何根据 DevOps 指令从 HAR 文件创建测试. 
  - [Performance Testing your web app with k6](https://www.youtube.com/watch?v=Hu1K2ZGJ_K4) - Chris James 的开源负载和性能回归测试工具 k6 演练，以及如何对您的 API 和网站进行负载测试.
  - [Application Load Testing with k6](https://www.youtube.com/watch?v=iQmItkazLOk) - Daniel Knittl-Frank @TechTalk Days 2021，k6 简介. 
  - [Performance testing: from zero to hero with k6 & Azure](https://www.youtube.com/watch?v=5G6zYLX9qvM) - Jose Luis Latorre Millas 在 2021 年云峰会上.
  - [Write load tests with co-pilot](https://twitter.com/yusuftayman/status/1456972872853852165) - Yusuf 使用 GitHub co-pilot 编写 k6 测试.

## Reference Projects

- [k6-circleci-example](https://github.com/li-clutter-org/k6-circleci-example) - 作为 CircleCI 构建的一部分运行 k6 负载测试.
- [k6-jenkins-example](https://github.com/li-clutter-org/k6-jenkins-example) - 作为 Jenkins 构建的一部分运行 k6 负载测试.
- [k6-github-actions-example](https://github.com/grafana/k6-example-github-actions) - 作为 GitHub Actions 构建的一部分运行 k6 负载测试.
- [k6-azure-pipelines-example](https://github.com/grafana/k6-example-azure-pipelines) - 作为 Azure DevOps 管道的一部分运行 k6 负载测试.
- [k6-bitbucket-pipelines-example](https://github.com/poponuts/k6-boilerplate) - 作为 Bitbucket 管道构建的一部分运行 k6 负载测试.
- [k6-performance-test-websocket](https://github.com/Julianhm9612/k6-performance-test-websocket) - 使用 k6 的 websocket 性能测试示例.
- [k6-template-es6](https://github.com/grafana/k6-template-es6) - 用于将测试项目捆绑到可由 k6 运行的单个测试脚本的模板存储库.
- [k6 templates](https://github.com/tom-miseur/k6-templates/) - k6 项目的自以为是的入门模板.
- [k6-typescript-template](https://github.com/grafana/k6-template-typescript) - 将 TypeScript 与 k6 结合使用的模板.
- [example-data-generation](https://github.com/grafana/k6-example-data-generation) - 使用 faker 为 k6 生成逼真的数据.
- [bounded-disturbances](https://github.com/bjartwolf/bounded-disturbances)  - .NET 混沌工程研讨会. 使用 Simmy 和 k6.
- [continuous-k6k8s](https://github.com/lreimer/continuous-k6k8s) - 使用 cronjobs 在 Kubernetes 中持续运行 k6 测试.
- [k6-multiscenario-template](https://github.com/SwissLife-OSS/K6-MultiScenario-template) - 使用K6实现多场景模板.
- [docker-k6-grafana-influxdb](https://github.com/luketn/docker-k6-grafana-influxdb) - 演示如何使用 K6、Grafana 和 InfluxDB 的容器化实例运行负载测试.

## Tools

- [k6-to-junit](https://github.com/Mattihew/k6-to-junit) - 用于将 k6 输出转换为 JUnit XML 以便于与 CI 一起使用的工具.
- [k6-reporter](https://github.com/benc-uk/k6-reporter) - 将 k6 输出转换为 HTML 报告的工具.
- [k6-html-reporter](https://github.com/szboynono/k6-html-reporter) - 用于生成 k6 HTML 报告的工具.
- [har-to-k6](https://github.com/grafana/har-to-k6) - 将 HAR 录音转换为 k6 测试脚本的工具.
- [postman-to-k6](https://github.com/grafana/postman-to-k6) - 将 Postman 集合转换为 k6 测试脚本的工具.
- [k6 generator](https://github.com/OpenAPITools/openapi-generator) - 将 Swagger/OpenAPI 规范转换为 k6 测试脚本的工具.
- [jmeter-to-k6](https://github.com/grafana/jmeter-to-k6) - 将 JMeter 测试用例转换为 k6 测试脚本的工具.
- [jslib.k6.io](https://jslib.k6.io/) - 用于 k6 脚本的实用工具库.
- [k6 for visual studio code](https://marketplace.visualstudio.com/items?itemName=k6.k6&ssr=false#overview) - 直接从您的 IDE 运行 k6 的市场扩展.
- [k6 for IntelliJ](https://plugins.jetbrains.com/plugin/16141-k6) - 基于 IntelliJ 的插件，用于在本地或在 [k6 Cloud](https://app.k6.io/) 从您的 IntelliJ IDE.
- [k6 Testkube executor](https://kubeshop.github.io/testkube/executor-k6/)
- [k6-junit](https://github.com/simbadltd/k6-junit) - k6 JUnit 摘要导出器库.
- [k6-expect](https://github.com/simbadltd/k6-expect) - k6 库，通过为期望提供类似笑话的语法，以功能方式简化编写测试.

## CI
- [k6 for GitHub actions](https://github.com/marketplace/actions/k6-load-test) - 在 GitHub Actions 中运行 k6 的市场操作.
- [k6 for Azure DevOps Pipelines](https://marketplace.visualstudio.com/items?itemName=k6.k6-load-test) - 用于在 Azure Devops 管道中运行 k6 的市场扩展.
- [k6 CircleCI Orb](https://circleci.com/developer/orbs/orb/k6io/test)  - k6 Orb 用于在 CircleCI 中运行 k6. 支持在 CircleCI 运行器和 k6 云 SaaS 服务中运行测试.
- [k6 for Atlassian Bamboo](https://k6.io/blog/integrating-k6-with-bamboo/)
- [k6 for AWS CodeBuild](https://k6.io/blog/integrating-k6-with-aws-codebuild/)
- [k6 for Google Cloud Build](https://k6.io/blog/integrating-k6-with-google-cloud-build/)
- [k6 for Buddy CI/CD](https://k6.io/blog/integrating-k6-with-buddy-devops/)

## Stacks

- [CloudPosse's Load Testing Stack](https://github.com/cloudposse/load-testing) - 使用 k6、Grafana 和 InfluxDB 加载测试堆栈.
- [实时压力：
AnyCable、k6、WebSockets 和 Yabeda](https://evilmartians.com/chronicles/real-time-stress-anycable-k6-websockets-and-yabeda) - Evil Martians 使用 k6 和 WebSockets 添加“实时压力” .
- [Scaling Confidently with the Load and Fault Team](https://robinhood.engineering/scaling-confidently-with-the-load-and-fault-team-122978333d9) - Robinhood 对使用 k6 的 Kubernetes 系统进行负载测试.
