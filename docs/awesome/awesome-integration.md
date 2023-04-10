<div class="github-widget" data-repo="stn1slv/awesome-integration"></div>
## Awesome Integration [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; 精选的系统集成软件、模式和资源列表.

系统集成是将不同的 IT 系统（组件）链接在一起以作为一个整体进行功能协作的过程.

  - [Data Mapping Solution](#data-mapping-solution) 
  - [iPaaS](#ipaas)  
  - [API Specification](#api-specification) 
  - [Enterprise Integration Patterns](#enterprise-integration-patterns) 

---
## Projects
### API Management
*API 管理解决方案.*
- [Akana API Management Platform](https://www.akana.com/products/api-platform)  ——加快数字化转型. 管理完整的 API 生命周期. 跨多个云部署. 并确保合规.
- [Anypoint Platform](https://www.mulesoft.com/platform/api/manager) - 将 API 管理和集成功能结合到 Mulesoft 的单一平台中.
- [Amazon API Management](https://aws.amazon.com/api-gateway/api-management/) - API 管理策略允许您以安全和可扩展的方式监控和管理 API.
- [Amplify API Management Platform](https://www.axway.com/en/products/amplify-api-management-platform) - 来自 Axway 的 API 管理开放平台.
- [Apigee](https://cloud.google.com/apigee) - 来自 Google 的 API 管理解决方案.
- [Azure API Management](https://azure.microsoft.com/en-us/services/api-management/) - 适用于所有环境的 API 的混合多云管理平台.
- [DigitMarket API Manager](https://www.torryharris.com/products/digitmarket-api-manager-for-api-management) - 一个完整的包，可帮助管理您的 API，并将它们变成推动您的业务向前发展的工具，作者：Torry Harris.
- [Gravitee.io API Management](https://www.gravitee.io/products/api-management) - 灵活、轻量级和超快的开源解决方案.
- [IBM API Connect](https://www.ibm.com/cloud/api-connect) - 一个完整、直观且可扩展的 API 平台，可让您跨云创建、公开、管理 API 并从中获利.
- [Kong Enterprise](https://konghq.com/products/kong-enterprise) - The service connectivity platform.
- [Layer7 API Management](https://www.broadcom.com/products/software/api-management) - 来自 Broadcom 的持续 API 管理.
- [Red Hat 3scale API Management](https://www.redhat.com/en/technologies/jboss-middleware/3scale) - 云原生开发变得更简单、更灵活.
- [Sensedia API Management](https://www.sensedia.com/api-management-platform) - 全生命周期API管理平台.
- [TIBCO Cloud Mashery](https://www.tibco.com/products/api-management) - 可部署在任何地方并从任何地方管理 API 的云原生 API 平台.
- [Tyk API Management](https://tyk.io/api-lifecycle-management/) - 连接、构建和控制.
- [webMethods API](https://www.softwareag.cloud/site/product/webmethods-api.html)  - 用于全生命周期 API 管理的 Software AG 产品是 webMethods API 管理. 平台（用于本地部署）和 webMethods.io API（用于云）.
- [WSO2 API Manager](https://wso2.com/api-manager/) - 完全开源的 API 管理平台.

### API Design
*API 设计、文档和生命周期自动化工具.*
- [OpenAPI Diff](https://github.com/OpenAPITools/openapi-diff) - 比较两个 OpenAPI 规范 (3.x) 并将差异呈现为 HTML 纯文本或 Markdown 文件.
- [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) - 允许在给定 OpenAPI 规范（支持 2.0 和 3.0）的情况下自动生成 API 客户端库（SDK 生成）、服务器存根、文档和配置.
- [OpenAPI Style Validator](https://github.com/OpenAPITools/openapi-style-validator) - 可自定义的样式验证器，以确保您的 OpenAPI 规范符合您组织的标准.
- [Spectral](https://github.com/stoplightio/spectral) - 开箱即用的 JSON/YAML linter，支持 OpenAPI 3.0 &amp; 2.0 和 AsyncAPI.
- [Swagger Editor](https://swagger.io/tools/swagger-editor/) - 在第一个完全专用于基于 OpenAPI 的 API 的开源编辑器上设计、描述和记录您的 API.
- [Zally](https://github.com/zalando/zally) - OpenAPI 规范的 linter.

### API Documentation
*API 门户和文档工具.*
- [APITree](https://www.apitree.com/) - 管理和共享 API 规范的中心位置.
- [DapperDox](http://dapperdox.io) - 用于 OpenAPI/Swagger 规范的开源 API 文档生成器和服务器.
- [OpenAPI Explorer](https://github.com/Rhosys/openapi-explorer) - 用于根据规范生成 UI 的 OpenAPI Web 组件.
- [RapiDoc](https://github.com/rapi-doc/RapiDoc) - 根据 OpenAPI 规范创建美观、可定制、交互式的 API 文档.
- [Redoc](https://github.com/Redocly/redoc) - 用于从 OpenAPI (fka Swagger) 定义生成文档的开源工具.
- [Slate](https://github.com/slatedocs/slate) - 漂亮的 API 静态文档.
- [SwaggerHub](https://swagger.io/tools/swaggerhub/) - 一个集成的 API 设计和文档平台，专为团队构建，以推动整个 API 开发工作流程的一致性和纪律性.
- [Swagger UI](https://github.com/swagger-api/swagger-ui) - 在直观的 UI 中可视化 OpenAPI 规范定义.


### API Gateway
*API Gateways.*
- [Apinto](https://github.com/eolinker/goku) - 基于Golang的微服务网关，支持高性能动态路由、服务编排、多租户管理、API访问控制等.
- [Ambassador Edge Stack](https://www.getambassador.io/products/edge-stack/api-gateway/) - Kubernetes 原生 API 网关.
- [Apache APISIX](https://apisix.apache.org) - 动态、实时、高性能的 API 网关.
- [Gloo Edge](https://www.solo.io/products/gloo-edge/) - 基于 Envoy 代理的 API 网关.
- [Kong API Gateway](https://github.com/Kong/kong) - 云原生、平台不可知、可扩展的 API 网关以其通过插件的高性能和可扩展性而著称.
- [KrakenD API Gateway](https://github.com/devopsfaith/krakend-ce) - 带有中间件的超高性能 API 网关.
- [Ocelot](https://github.com/ThreeMammals/Ocelot) - .NET API 网关.
- [Spring Cloud Gateway](https://spring.io/projects/spring-cloud-gateway) - API 网关建立在 Spring 生态系统之上，包括：Spring 5、Spring Boot 2 和 Project Reactor.
- [Traefik](https://github.com/traefik/traefik)  - 一个现代的开源 API 网关，旨在处理动态容器环境，例如 Kubernetes、Docker Swarm 和 Mesos. 它提供负载平衡、SSL/TLS 终止、速率限制、熔断等功能.
- [Tyk API Gateway](https://github.com/TykTechnologies/tyk) - 开源企业 API 网关，支持 REST、GraphQL、TCP 和 gRPC 协议.

### API Testing
*API 测试工具.*
- API客户端
  - [Advanced REST Client](https://github.com/advanced-rest-client/arc-electron) - 出于为开发人员社区提供他们需要的工具的热情，一个对所有人免费的开源 API 工具.
  - [curl](https://github.com/curl/curl) - 用于使用 URL 传输数据的命令行工具和库.
  - [curlie](https://curlie.io) - 一个 curl 的前端，增加了 httpie 的易用性，而不影响功能和性能.
  - [HTTPie](https://httpie.io) - 命令行 HTTP 客户端，比 curl 对开发者更友好.
  - [Insomnia](https://insomnia.rest/products/insomnia) - 跨平台 HTTP 和 GraphQL 客户端.
  - [Postman](https://www.postman.com/product/api-client/) - 用于发出 HTTP 请求、生成模拟服务器和制作 API 文档的工具.
  - [SoapUI](https://www.soapui.org/tools/soapui) - 用于 SOAP 和 REST 的开源 Web 服务测试应用程序.
- MQ客户端
  - [JMSToolBox](https://github.com/jmstoolbox/jmstoolbox) - 一个通用的 JMS 客户端，能够与最多的基于 JMS 的消息代理进行交互.
  - [kcat](https://github.com/edenhill/kcat)  - Apache Kafka 的通用非 JVM 生产者和消费者，可以将其视为 Kafka 的 netcat. 以前称为卡夫卡猫.
  - [MQTT Explorer](https://github.com/thomasnordquist/MQTT-Explorer) - 提供结构化主题概述的全方位 MQTT 客户端.
  - [Offset Explorer](https://www.kafkatool.com)  - 用于管理和使用 Apache Kafka 集群的 GUI 应用程序. 以前称为 Kafka 工具.
  - [Service Bus Explorer](https://github.com/paolosalvatori/ServiceBusExplorer) - Azure 服务总线的 GUI 应用程序，它提供高级功能，如导入/导出功能或测试主题、队列、订阅、中继服务、通知中心和事件中心的能力.
- 模拟工具
  - [Microcks](https://github.com/microcks/microcks)  - 用于 API 模拟和测试的开源 Kubernetes 本机工具. 支持 AsyncAPI、OpenAPI、Postman Collections 等.
  - [Mockable](https://www.mockable.io/) - 模拟 RESTful API 或 SOAP 网络服务的简单可配置服务.
  - [Mockoon](https://mockoon.com/) - 设计和运行模拟 REST API 的最简单快捷的方法.
  - [MockServer](https://github.com/mock-server/mockserver) - 轻松模拟您通过 HTTP 或 HTTPS 集成的任何系统.
  - [Mocky](https://designer.mocky.io/) - 免费且无限制的在线服务，允许生成自定义 HTTP 响应.
  - [Prism](https://github.com/stoplightio/prism) - 一个开源 HTTP 模拟服务器，可以模仿您的 API 的行为，就好像您已经构建了它一样.
  - [WireMock](https://github.com/tomakehurst/wiremock) - 模拟您的 API 以进行快速、稳健和全面的测试.
- 测试工具和框架
  - [Apache JMeter](https://jmeter.apache.org/) - 一个开源的基于 java 的负载测试工具.
  - [Karate](https://github.com/intuit/karate) - 将 API 测试自动化、模拟、性能测试甚至 UI 自动化组合到一个统一框架中的开源工具.
  - [Pyresttest](https://github.com/svanoort/pyresttest) - REST 测试和 API 微基准测试工具.
  - [REST Assured](https://github.com/rest-assured/rest-assured) - 用于轻松测试 REST 服务的 Java DSL.
  - [Schemathesis](https://github.com/schemathesis/schemathesis) - API 模式的基于属性的测试.

### BRE
*业务规则引擎和业务规则管理系统.*
- [Drools](https://www.drools.org) - 开源工具，具有对一致性级别 3 的决策模型和符号 (DMN) 模型的完整运行时支持，以及用于核心开发的 Eclipse IDE 插件.
- [Easy Rules](https://github.com/j-easy/easy-rules) - 一个简单的 Java 规则引擎.
- [NxBRE](https://github.com/ddossot/NxBRE/wiki) - .NET 平台的开源规则引擎.
- [OpenL Tablets](http://openl-tablets.org/) - 开源业务规则引擎（BRE、BRMS）和决策管理系统.

### BPM
*业务流程管理解决方案.*
- [Appian BPM Suite](https://appian.com/platform/complete-automation/business-process-management-bpm.html) - 平台将低代码开发与流程管理相结合
允许 IT 和公民开发人员构建以流程为中心和以案例为中心的应用程序.
- [Genpack Cora SeQuence](https://www.genpact.com/cora/sequence) - 编排更有效的流程，产生增长，提高成本效率，并推动业务敏捷性.
- [IBM Business Automation Workflow](https://www.ibm.com/products/business-automation-workflow) - 全面的业务流程管理平台.
- [Oracle BPM Suite](https://www.oracle.com/middleware/technologies/bpm.html) - 用于开发、管理和使用以业务流程为中心的业务应用程序的集成环境.
- [Pega Platform](https://www.pega.com/products/platform) - 结合了业务流程管理和机器人流程自动化 (RPA) 平台以及来自 Pegasystems 的高级劳动力分析.
- [Red Hat Process Automation Manager](https://www.redhat.com/en/technologies/jboss-middleware/process-automation-manager) - 一个应用程序开发平台，使开发人员和业务专家能够创建可自动化业务运营的云原生应用程序.
- [SAP Process Orchestration](https://www.sap.com/products/process-orchestration.html) - 业务流程管理产品和应用程序基础架构. 
- [TIBCO BPM Enterprise](https://www.tibco.com/products/business-process-management) - 具有流程自动化、流程文档、人力资本管理、流程模式和预测性运营分析功能的业务流程管理平台.

### Data Mapping Solution
*数据映射解决方案.*
- [AltasMap](https://www.atlasmap.io/) - 具有基于 Web 的交互式用户界面的数据映射解决方案，可简化 Java、XML、CSV 和 JSON 数据源之间的配置集成.
- [Altova MapForce](https://www.altova.com/mapforce) - 用于任意转换和集成的图形数据映射工具.
- [JOLT](https://github.com/bazaarvoice/jolt) - 用 Ja​​va 编写的 JSON 到 JSON 转换库，其中转换的“规范”本身就是一个 JSON 文档.
- [JSLT](https://github.com/schibsted/jslt)  - 完整的 JSON 查询和转换语言. 语言设计灵感来自 jq、XPath 和 XQuery.

### ESB
*企业服务总线解决方案.*
- [Anypoint Platform](https://www.mulesoft.com/platform/enterprise-integration) - 将 API 管理和集成功能结合到 Mulesoft 的单一平台中.
- [Apache ServiceMix](https://servicemix.apache.org/) - 一个灵活的开源集成容器，统一了 Apache ActiveMQ、Camel、CXF 和 Karaf 的特性和功能.
- [ArcESB](https://www.arcesb.com/integration/) - 跨应用程序同步数据，与合作伙伴无缝集成，或使数据可公开访问.
- [IBM App Connect](https://www.ibm.com/cloud/app-connect)  - 将应用程序连接在一起，无论它们支持何种消息格式或协议. 以前称为 IBM Integration Bus.
- [NServiceBus](https://particular.net/nservicebus) - 对开发人员最友好的 .NET 服务总线.
- [Oracle Service Bus](https://www.oracle.com/middleware/technologies/service-bus.html) - 通过连接、虚拟化和管理服务与应用程序之间的交互，将复杂而脆弱的架构转变为敏捷的集成网络.
- [Oracle SOA Suite](https://www.oracle.com/middleware/technologies/soasuite.html) - 使系统开发人员能够设置和管理服务，并将它们编排到复合应用程序和业务流程中.
- [Red Hat Fuse](https://www.redhat.com/en/technologies/jboss-middleware/fuse) - 分布式、云原生集成平台.
- [Software AG webMethods Integration Server](https://www.softwareag.com/en_corporate/platform/integration-apis/webmethods-integration.html) - 更快地整合任何东西.
- [TIBCO BusinessWorks](https://www.tibco.com/products/tibco-businessworks) - 实施混合集成的企业模式.
- [UltraESB](https://www.adroitlogic.com/products/ultraesb/) - 唯一支持零拷贝代理的 ESB，利用直接内存访问 (DMA) 和 sendfile 系统调用以及非阻塞 IO 实现极致性能.
- [WSO2 Enterprise Integrator](https://wso2.com/integration/) - 以 API 为中心、云原生和分布式集成平台.

### ETL
*ETL/ELT 和数据集成工具.*
- [Apache NiFi](https://nifi.apache.org/) - Apache NiFi 是一个集成的数据物流平台，用于在不同系统之间自动移动数据.
- [CloverETL](http://www.cloveretl.com/) - 一个数据集成软件套件，用于数据迁移和数据仓库，以及将数据输入商业智能和报告应用程序. 
- [Hevo](https://hevodata.com/) - Hevo Data 是一个全自动、无代码的数据管道平台，支持跨数据库、SaaS 应用程序、云存储、SDK 和流媒体服务的 150 多个即用型集成.
- [IBM DataStage](https://www.ibm.com/products/datastage) - 帮助企业理解、清理、转换和交付可信信息的数据集成平台.
- [Informatica PowerCenter](https://www.informatica.com/products/data-integration/powercenter.html) - 提供支持大数据和云分析的企业数据集成和管理软件.
- [Microsoft SSIS](https://docs.microsoft.com/en-us/sql/integration-services/sql-server-integration-services) - SQL Server Integration Services 是一个用于构建企业级数据集成和数据转换解决方案的平台.
- [Oracle Data Integrator](https://www.oracle.com/middleware/technologies/data-integrator.html) - 一个全面的数据集成平台，涵盖所有数据集成需求，包括批量加载、集成流程和支持 SOA 的数据服务.
- [Pentaho Data Integration](https://github.com/pentaho/pentaho-kettle) - 使用户能够使用可视化工具从任何来源摄取、混合、清理和准备各种数据，以消除编码和复杂性.
- [SAS Data Management](https://www.sas.com/en_us/software/data-management.html) - 帮助转换、集成、管理和保护数据，同时提高其整体质量和可靠性.
- [Stitch](https://www.stitchdata.com/)  - 一种简单、强大的 ETL 服务，适用于各种规模的企业，包括企业.  Stitch 在可扩展、容错的云平台上运行，集成了来自数十个不同来源的数据.
- [Talend Data Integration](https://www.talend.com/products/integrate-data/) - 将来自多个来源的数据汇集在一起​​，为您的所有业务决策提供支持.

### Integration Frameworks
*基于已知企业集成模式的集成框架.*
- [Apache Camel](https://camel.apache.org) - 通过企业集成模式将不同的传输 API 粘合在一起.
- [Ballerina](https://ballerina.io/) - 一种开源编程语言，可以更轻松地使用、组合和创建网络服务.
- [Spring Integration](https://spring.io/projects/spring-integration) - 扩展 Spring 编程模型以支持著名的企业集成模式.

### iPaaS
*集成平台即服务.*
- [Anypoint Platform](https://www.mulesoft.com/platform/saas/cloudhub-ipaas-cloud-based-integration) - 将 API 管理和集成功能结合到 Mulesoft 的单一平台中.
- [Dell Boomi AtomSphere](https://boomi.com/platform) - 通过云原生的、统一的、开放的、智能的平台连接每个人和任何事物.
- [Jitterbit Harmony](https://www.jitterbit.com/platform/ipaas) - 将数以千计的应用程序与预建模板和工作流集成在一起，以自动化您的业务流程.
- [IBM Cloud Integration](https://www.ibm.com/cloud/integration) - 人工智能驱动的集成方法.
- [Informatica Intelligent Cloud Services](https://www.informatica.com/products/cloud-integration.html) - 多种云数据管理产品，旨在提高生产力并提高速度和规模.
- [OpenText Alloy](https://businessnetwork.opentext.com/enterprise-data-management/)  - 企业数据管理，组织超越基本集成，将数据转化为洞察力和行动. 以前称为联络合金平台.
- [Oracle Integration Cloud Service](https://www.oracle.com/integration/application-integration/) - 通过与任何 SaaS 或本地应用程序的预建连接加快上线时间.
- [SnapLogic Intelligent Integration Platform](https://www.snaplogic.com/products/intelligent-integration-platform) - 连接您的应用程序和数据环境.
- [Software AG webMethods Hybrid Integration Platform](https://www.softwareag.com/en_corporate/platform/integration-apis/application-integration.html) - 一个应用集成平台，一网打尽.
- [TIBCO Cloud Integration](https://www.tibco.com/products/cloud-integration) - 使每个人都能通过 API 主导和事件驱动的集成来集成任何东西.
- [Workato](https://www.workato.com/) - 用于整个组织的集成和工作流自动化的单一平台.

### MaaS
*云消息传递即服务 (MaaS).*
- [Amazon MQ](https://aws.amazon.com/amazon-mq) - 用于 Apache ActiveMQ 和 RabbitMQ 的完全托管消息代理服务.
- [Amazon MSK](https://aws.amazon.com/msk) - 用于 Apache Kafka 的亚马逊托管流.
- [Amazon SQS](https://aws.amazon.com/sqs) - 亚马逊简单队列服务.
- [Amazon SNS](https://aws.amazon.com/sns)  - 亚马逊简单通知服务. 发布/订阅功能为分布式系统、微服务和事件驱动的无服务器应用程序之间的高吞吐量、基于推送的多对多消息传递提供主题.
- [Alibaba Cloud Message Queue for Apache Kafka](https://www.alibabacloud.com/product/kafka) - 来自阿里云的完全托管的 Apache Kafka 服务.
- [Alibaba Cloud Message Queue for RabbitMQ](https://www.alibabacloud.com/product/rabbitmq) - 一种分布式、完全托管的专业消息服务，具有高吞吐量、低延迟和高可扩展性的特点.
- [Alibaba Cloud Message Service](https://www.alibabacloud.com/product/message-service) - 分布式消息队列和通知服务，支持并发操作以促进应用程序和解耦系统之间的消息传输.
- [AlibabaMQ for Apache RocketMQ](https://www.alibabacloud.com/product/mq) - 一种分布式消息队列服务，支持微服务、分布式系统和无服务器应用程序之间基于消息的可靠异步通信.
- [Anypoint MQ](https://www.mulesoft.com/platform/anypoint-mq-message-queue) - 企业级云消息传递，与 Anypoint 平台完全集成.
- [Azure Service Bus](https://azure.microsoft.com/en-us/services/service-bus/) - 可靠的云消息传递即服务 (MaaS) 和简单的混合集成.
- [CloudAMQP](https://www.cloudamqp.com/) - RabbitMQ 即服务.
- [CloudKarafka](https://www.cloudkarafka.com/) - 在 AWS 和谷歌云上提供经济实惠、直接、完全托管的 Kafka 集群.
- [Google Cloud Pub/Sub](https://cloud.google.com/pubsub) - 事件驱动系统和流分析的消息传递和摄取.
- [Huawei Cloud Distributed Message Service](https://www.huaweicloud.com/intl/en-us/product/dms.html) - 一种完全托管的高性能消息队列服务，可在分布式应用程序之间实现可靠、灵活和异步的通信.
- [Huawei Cloud Distributed Message Service for Kafka](https://www.huaweicloud.com/intl/en-us/product/dmskafka.html) - 托管 Apache Kafka 服务.
- [IBM MQ on Cloud](https://www.ibm.com/cloud/mq) - 在企业应用程序、系统和服务之间轻松移动数据.
- [IronMQ](https://www.iron.io/mq) - 专门针对云创建的弹性消息队列.
- [Oracle Cloud Streaming](https://www.oracle.com/cloud/cloud-native/streaming/) - A real-time, serverless, Apache Kafka-compatible event streaming platform.
- [Solace PubSub+ Cloud](https://solace.com/products/platform/cloud/) - 一个完整的事件流、管理和洞察平台.
- [Yandex Message Queue](https://cloud.yandex.com/en/services/message-queue) - 与 Amazon SQS HTTP API 的兼容性.
- [Yandex Managed Service for Apache Kafka](https://cloud.yandex.com/en/services/managed-kafka) - 托管 Apache Kafka 服务.

### Managed File Transfer
*托管文件传输 (MFT) 解决方案.*
- [ArcESB Managed File Transfer](https://www.arcesb.com/mft/) - 一体式企业级 MFT.
- [Axway Managed File Transfer](https://www.axway.com/en/products/managed-file-transfer) - 使文件传输服务易于使用.
- [Cornerstone MFT](https://southrivertech.com/products/cornerstone/) - 具有高可用性和故障转移功能的企业 MFT 服务器解决方案，可消除停机时间.
- [IBM Sterling Secure File Transfer](https://www.ibm.com/products/secure-file-transfer) - 使用快速且可扩展的文件传输平台，每天移动超过 100 万个文件.
- [Oracle Managed File Transfer](https://www.oracle.com/middleware/technologies/mft/managed-file-transfer.html) - 启用安全的文件交换和管理.
- [TIBCO Managed File Transfer](https://www.tibco.com/products/tibco-managed-file-transfer) - 从一个集中管理的 MFT 平台安全地支持所有文件传输用例.

### Master Data Management
*主数据管理解决方案.*
- [IBM InfoSphere Master Data Management](https://www.ibm.com/products/ibm-infosphere-master-data-management) - Comprehensive master data management.
- [Informatica Multidomain MDM](https://www.informatica.com/products/master-data-management/multidomain-mdm.html) - 多合一的主数据管理.
- [Oracle Enterprise Data Management](https://www.oracle.com/performance-management/enterprise-data-management/) - 通过管理主数据更快、更有效地适应和响应变化.
- [SAP Master Data Governance](https://www.sap.com/products/master-data-governance.html) - 通过整合和集中管理主数据生命周期，提高整个组织的信息质量和一致性.
- [SAS MDM](https://support.sas.com/en/software/mdm-support.html) - 提供单一、准确和统一的公司数据视图，将来自各种数据源的信息集成到一个主记录中.
- [Software AG OneData for MDM](https://www.softwareag.com/resources/Master-data-management) - 在数据方面提供“单一版本的事实”，确保只有可靠、准确和经过批准的信息才能流经您的系统、流程和应用程序.
- [Teradata MDM](https://www.teradata.co.uk/Products/Applications/Master-Data-Management) - 使用一致的参考数据来建立准确的分析数据基础，从而推动显着的投资回报率.
- [TIBCO EBX](https://www.tibco.com/products/tibco-ebx-software) - 用于治理、管理和使用所有共享数据资产的单一解决方案.

### Messaging
*消息代理.*
- [Apache ActiveMQ](https://activemq.apache.org) - 实现 JMS 并将同步通信转换为异步通信的消息代理.
- [Apache Kafka](https://kafka.apache.org) - 高吞吐量分布式消息系统.
- [Apache Pulsar](https://pulsar.apache.org) - 分布式发布/子消息系统.
- [Apache RocketMQ](https://rocketmq.apache.org) - 快速、可靠且可扩展的分布式消息传递平台.
- [Apache Qpid](https://qpid.apache.org) - Apache Qpid 制作使用 AMQP 并支持多种语言和平台的消息传递工具.
- [Eclipse Mosquitto](https://mosquitto.org/) - 实现 MQTT 协议的轻量级开源消息代理.
- [IBM MQ](https://www.ibm.com/products/mq) - 企业级消息传递功能，可以巧妙、安全地在应用程序之间移动信息.
- [KubeMQ](https://kubemq.io/) - Kubernetes Message Queue Broker 企业级消息代理和消息队列，可扩展、高可用且安全.
- [NATS](https://github.com/nats-io/gnatsd) - 用于微服务、物联网和云原生系统的轻量级、高性能消息传递系统.
- [Oracle AQ](https://www.oracle.com/database/technologies/advanced-queuing.html) - Oracle Advanced Queuing (AQ) 提供跨多个行业的企业消息功能，并广泛用于数据库本身. 
- [RabbitMQ](https://www.rabbitmq.com) - 最初实现高级消息队列协议 (AMQP) 的开源消息代理.
- [Redpanda](https://github.com/vectorizedio/redpanda)  - 用于关键任务工作负载的流媒体平台.  Kafka® 兼容，无 Zookeeper®，无 JVM，无需更改代码.
- [Red Hat AMQ](https://www.redhat.com/en/technologies/jboss-middleware/amq) - 基于 Apache ActiveMQ 和 Apache Kafka 等开源社区的 Red Hat AMQ.
- [TIBCO Enterprise Message Service](https://www.tibco.com/products/tibco-enterprise-message-service) - TIBCO EMS 是基于标准的 Java™ 消息服务 (JMS) 实现，允许任何支持 JMS 的应用程序，无论是自主开发的还是第三方的，都可以快速轻松地交换消息.
- [VerneMQ](https://github.com/vernemq/vernemq) - 高性能、分布式 MQTT 消息代理.

### RPA
*机器人流程自动化 (RPA) 解决方案.*
- [Automation Anywhere](https://www.automationanywhere.com/) - 智能自动化生态系统.
- [Blue Prism](https://www.blueprism.com/products/intelligent-rpa-automation/) - 智能自动化——业务开发的无代码自动化RPA平台.
- [UiPath](https://www.uipath.com/product) - 通常由人执行的自动化重复性数字任务.
- [WorkFusion](https://www.workfusion.com/platform/) - 企业自动化平台.

### Self-Service Integration
*任何自助服务和公民集成工具.*

- [IFTTT](https://ifttt.com/) - 允许在 Web 服务之间创建条件语句链，以使 Web 为您工作并提高您的工作效率.
- [Oracle Self-Service Integration](https://docs.oracle.com/en/cloud/paas/self-service-integration-cloud/index.html) - 自动化云应用程序之间的任务.
- [Zapier](https://zapier.com/) - 自动化工具，允许您连接数百个 Web 服务并在流程之间创建自动化.

### Workflow engine
*工作流和编排引擎.*
- [Activiti](https://github.com/Activiti/Activiti) - 一个轻量级和以 java 为中心的开源 BPMN 引擎.
- [Apache Airflow](https://github.com/apache/airflow) - 一个以编程方式创作、安排和监控工作流的平台.
- [Argo Workflows](https://github.com/argoproj/argo-workflows) - 用于在 Kubernetes 上编排并行作业的开源容器原生工作流引擎.
- [Azkaban](https://github.com/azkaban/azkaban) - 分布式工作流管理器，在 LinkedIn 实现，用于解决 Hadoop 作业依赖性问题.
- [Bonita](https://github.com/bonitasoft/bonita-engine) - 带有可选开发环境、设计器、可选用户界面和管理工具的 BPMN 引擎.
- [Cadence](https://github.com/uber/cadence) - 容错状态代码平台.
- [Camunda](https://github.com/camunda/camunda-bpm-platform) - 开源工作流和决策自动化平台.
- [Conductor](https://github.com/Netflix/conductor) - Netflix Conductor 是一个在云端运行的编排引擎.
- [Elsa Core](https://github.com/elsa-workflows/elsa-core) - 支持在任何 .NET Core 应用程序中执行工作流的工作流库.
- [Flowable](https://github.com/flowable/flowable-engine) - 提供一套核心的开源业务流程引擎，紧凑高效.
- [jBPM](https://www.jbpm.org/) - 用于构建业务应用程序以帮助自动化业务流程和决策的工具包.
- [StackStorm](https://github.com/StackStorm/st2)  - 提供传感器、触发器、规则、工作流和操作的强大自动化引擎.  StackStorm 是您将应用程序“粘合”在一起的方式.

## Resources
*一些有用的规范、模式、文章和文档.*
### API Specification
- [API Blueprint](https://apiblueprint.org) - 用于设计和记录 API 的高级 API 描述语言.
- [AsyncAPI](https://www.asyncapi.com/docs/specifications/v2.0.0) - AsyncAPI 规范为事件驱动架构 (EDA) 的更大更好的工具生态系统奠定了基础.
- [GraphQL](https://github.com/graphql/graphql-spec) - 用于 API 的查询语言和用于使用现有数据完成这些查询的运行时.
- [JSON:API](https://jsonapi.org) - 用于构建 API 的规范，它提供了表示资源、关系和元数据的标准化方式.
- [OpenAPI (ex.Swagger)](https://spec.openapis.org/oas/v3.1.0) - 为 RESTful API 定义了一个标准的、与语言无关的接口，它允许人类和计算机在不访问源代码、文档或通过网络流量检查的情况下发现和理解服务的功能. 
- [RAML](https://github.com/raml-org/raml-spec/blob/master/versions/raml-10/raml-10.md/) - RESTful API 建模语言.
- [WSDL](http://www.w3.org/TR/wsdl20) - 用于基于 SOAP 的服务的基于 XML 的接口描述语言.
### Articles
- [Enterprise Integration Using REST](http://martinfowler.com/articles/enterpriseREST.html) - 讨论非公共 API 的限制和灵活性，以及​​从跨多个团队进行大规模 RESTful 集成中吸取的经验教训.
- [Richardson Maturity Model](http://martinfowler.com/articles/richardsonMaturityModel.html) - 由 Martin Fowler 解释，最初由 Leonard Richardson 提出.
### Connectors
- [JCA](https://projects.eclipse.org/projects/ee4j.jca)  - 为 Jakarta EE 应用程序组件定义标准架构以连接到企业信息系统. 以前称为 Java EE 连接器体系结构和 J2EE 连接器体系结构.
- [Kafka Connect](https://kafka.apache.org/documentation/#connect) - 一种用于在 Apache Kafka 和其他系统之间可扩展且可靠地传输数据的工具.
### Data Formats
- [Apache Avro](https://github.com/apache/avro) - 数据序列化系统.
- [BSON](https://bsonspec.org/) - 二进制 JSON 的缩写，是类 JSON 文档的二进制编码序列化.
- [CSV](https://datatracker.ietf.org/doc/html/rfc4180) - 逗号分隔值 (CSV) 文件是使用逗号分隔值的分隔文本文件.
- [JSON](https://datatracker.ietf.org/doc/html/rfc8259) - JavaScript 对象表示法 (JSON) 数据交换格式.
- [NDJSON](https://github.com/ndjson/ndjson-spec) - 在流协议中分隔 JSON 的标准.
- [Protocol Buffers](https://developers.google.com/protocol-buffers) - 一种语言中立、平台中立的可扩展机制，用于序列化结构化数据.
- [XML](https://www.w3.org/TR/2006/REC-xml11-20060816/) - 可扩展标记语言 (XML).
- [YAML](https://yaml.org/) - YAML 是适用于所有编程语言的人性化数据序列化标准.

### Enterprise Integration Patterns
*模式来自 Gregor Hohpe 和 Bobby Woolf 的一本书.*
- [Aggregator](https://www.enterpriseintegrationpatterns.com/patterns/messaging/Aggregator.html) - 我们如何组合单个但相关消息的结果，以便将它们作为一个整体进行处理？  
- [Canonical Data Model](https://www.enterpriseintegrationpatterns.com/patterns/messaging/CanonicalDataModel.html) - 在集成使用不同数据格式的应用程序时如何最大程度地减少依赖性？
- [Channel Adapter](https://www.enterpriseintegrationpatterns.com/patterns/messaging/ChannelAdapter.html) - 如何将应用程序连接到消息系统，以便它可以发送和接收消息？
- [Channel Purger](https://www.enterpriseintegrationpatterns.com/patterns/messaging/ChannelPurger.html) - 如何防止通道上的“遗留”消息干扰测试或运行系统？
- [Claim Check](https://www.enterpriseintegrationpatterns.com/patterns/messaging/StoreInLibrary.html) - 我们如何在不牺牲信息内容的情况下减少通过系统发送的消息的数据量？  
- [Command Message](https://www.enterpriseintegrationpatterns.com/patterns/messaging/CommandMessage.html) - 如何使用消息传递来调用另一个应用程序中的过程？  
- [Competing Consumers](https://www.enterpriseintegrationpatterns.com/patterns/messaging/CompetingConsumers.html) - 消息传递客户端如何同时处理多条消息？
- [Composed Message Processor](https://www.enterpriseintegrationpatterns.com/patterns/messaging/DistributionAggregate.html) - 在处理由多个元素组成的消息时，如何维护整个消息流，每个元素可能需要不同的处理？  
- [Content Enricher](https://www.enterpriseintegrationpatterns.com/patterns/messaging/DataEnricher.html) - 如果消息发起者没有可用的所有必需数据项，我们如何与另一个系统通信？  
- [Content Filter](https://www.enterpriseintegrationpatterns.com/patterns/messaging/ContentFilter.html) - 当您只对少数数据项感兴趣时，您如何简化对大消息的处理？  
- [Content-Based Router](https://www.enterpriseintegrationpatterns.com/patterns/messaging/ContentBasedRouter.html) - 我们如何处理单个逻辑功能（例如，库存检查）的实施分布在多个物理系统中的情况？  
- [Control Bus](https://www.enterpriseintegrationpatterns.com/patterns/messaging/ControlBus.html) - 我们如何有效地管理分布在多个平台和广泛地理区域的消息传递系统？  
- [Correlation Identifier](https://www.enterpriseintegrationpatterns.com/patterns/messaging/CorrelationIdentifier.html) - 收到回复的请求者如何知道这是针对哪个请求的回复？
- [Datatype Channel](https://www.enterpriseintegrationpatterns.com/patterns/messaging/DatatypeChannel.html) - 应用程序如何发送数据项以便接收方知道如何处理它？
- [Dead Letter Channel](https://www.enterpriseintegrationpatterns.com/patterns/messaging/DeadLetterChannel.html) - 消息系统将如何处理它无法传递的消息？  
- [Detour](https://www.enterpriseintegrationpatterns.com/patterns/messaging/Detour.html) - 如何通过中间步骤路由消息以执行验证、测试或调试功能？
- [Document Message](https://www.enterpriseintegrationpatterns.com/patterns/messaging/DocumentMessage.html) - 如何使用消息传递在应用程序之间传输数据？
- [Durable Subscriber](https://www.enterpriseintegrationpatterns.com/patterns/messaging/DurableSubscription.html) - 订户如何在不收听消息时避免丢失消息？
- [Dynamic Router](https://www.enterpriseintegrationpatterns.com/patterns/messaging/DynamicRouter.html) - 如何在保持其效率的同时避免路由器对所有可能目的地的依赖？
- [Envelope Wrapper](https://www.enterpriseintegrationpatterns.com/patterns/messaging/EnvelopeWrapper.html) - 现有系统如何参与对消息格式提出特定要求（例如消息头字段或加密）的消息交换？  
- [Event Message](https://www.enterpriseintegrationpatterns.com/patterns/messaging/EventMessage.html) - 如何使用消息传递将事件从一个应用程序传输到另一个应用程序？
- [Event-Driven Consumer](https://www.enterpriseintegrationpatterns.com/patterns/messaging/EventDrivenConsumer.html) - 应用程序如何在消息可用时自动使用它们？
- [Format Indicator](https://www.enterpriseintegrationpatterns.com/patterns/messaging/FormatIndicator.html) - 如何设计消息的数据格式以允许将来可能发生的变化？
- [Guaranteed Delivery](https://www.enterpriseintegrationpatterns.com/patterns/messaging/GuaranteedMessaging.html) - 即使消息传递系统出现故障，发件人如何确保消息能够送达？
- [Idempotent Receiver](https://www.enterpriseintegrationpatterns.com/patterns/messaging/IdempotentReceiver.html) - 消息接收者如何处理重复消息？
- [Invalid Message Channel](https://www.enterpriseintegrationpatterns.com/patterns/messaging/InvalidMessageChannel.html) - 消息接收者如何优雅地处理接收到的毫无意义的消息？
- [Message](https://www.enterpriseintegrationpatterns.com/patterns/messaging/Message.html) - 通过消息通道连接的两个应用程序如何交换一条信息？
- [Message Dispatcher](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageDispatcher.html) - 单个通道上的多个消费者如何协调他们的消息处理？
- [Message Expiration](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageExpiration.html) - 发件人如何指示消息何时应被视为过时且因此不应处理？
- [Message Translator](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageTranslator.html) - 使用不同数据格式的系统如何使用消息传递相互通信？  
- [Message Broker](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageBroker.html) - 如何将消息的目的地与发送者分离并保持对消息流的集中控制？
- [Message Bus](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageBus.html) - 什么是使独立的应用程序能够一起工作的体系结构，但以解耦的方式使应用程序可以轻松添加或删除而不影响其他应用程序？  
- [Message Channel](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageChannel.html) - 一个应用程序如何使用消息传递与另一个应用程序通信？
- [Message Endpoint](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageEndpoint.html) - 应用程序如何连接到消息通道以发送和接收消息？
- [Message Filter](https://www.enterpriseintegrationpatterns.com/patterns/messaging/Filter.html) - 组件如何避免接收无趣的消息？
- [Message History](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageHistory.html) - 我们如何有效地分析和调试松散耦合系统中的消息流？  
- [Message Router](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageRouter.html) - 如何解耦各个处理步骤，以便根据一组条件将消息传递到不同的过滤器？
- [Message Sequence](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageSequence.html) - 消息传递如何传输任意大量的数据？
- [Message Store](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageStore.html) - 我们如何在不影响消息系统松散耦合和瞬态特性的情况下报告消息信息？  
- [Messaging Bridge](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessagingBridge.html) - 如何连接多个消息系统，以便在一个系统上可用的消息在其他系统上也可用？
- [Messaging Gateway](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessagingGateway.html) - 如何封装从应用程序的其余部分访问消息系统？
- [Messaging Mapper](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessagingMapper.html) - 如何在域对象和消息传递基础结构之间移动数据，同时保持两者相互独立？
- [Normalizer](https://www.enterpriseintegrationpatterns.com/patterns/messaging/Normalizer.html) - 如何处理语义相同但格式不同的消息？
- [Pipes and Filters](https://www.enterpriseintegrationpatterns.com/patterns/messaging/PipesAndFilters.html) - 如何在保持独立性和灵活性的同时对消息进行复杂的处理？  
- [Point-to-Point Channel](https://www.enterpriseintegrationpatterns.com/patterns/messaging/PointToPointChannel.html) - 呼叫者如何确定只有一个接收者会收到文件或执行呼叫？
- [Polling Consumer](https://www.enterpriseintegrationpatterns.com/patterns/messaging/PollingConsumer.html) - 当应用程序就绪时，应用程序如何使用消息？  
- [Process Manager](https://www.enterpriseintegrationpatterns.com/patterns/messaging/ProcessManager.html) - 当所需步骤在设计时可能未知且可能不是连续的时，我们如何通过多个处理步骤路由消息？
- [Publish-Subscribe Channel](https://www.enterpriseintegrationpatterns.com/patterns/messaging/PublishSubscribeChannel.html) - 发送方如何向所有感兴趣的接收方广播一个事件？
- [Recipient List](https://www.enterpriseintegrationpatterns.com/patterns/messaging/RecipientList.html) - 我们如何将消息路由到动态指定的收件人列表？
- [Request-Reply](https://www.enterpriseintegrationpatterns.com/patterns/messaging/RequestReply.html) - 当应用程序发送消息时，它如何从接收者那里得到响应？
- [Resequencer](https://www.enterpriseintegrationpatterns.com/patterns/messaging/Resequencer.html) - 我们如何才能将相关但无序的消息流恢复为正确的顺序？
- [Return Address](https://www.enterpriseintegrationpatterns.com/patterns/messaging/ReturnAddress.html) - 回复者如何知道将回复发送到哪里？
- [Routing Slip](https://www.enterpriseintegrationpatterns.com/patterns/messaging/RoutingTable.html) - 当步骤顺序在设计时未知且每条消息可能不同时，我们如何通过一系列处理步骤连续路由消息？  
- [Scatter-Gather](https://www.enterpriseintegrationpatterns.com/patterns/messaging/BroadcastAggregate.html) - 当一条消息需要发送给多个收件人并且每个收件人都可以发送回复时，您如何维护整体消息流？  
- [Selective Consumer](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageSelector.html) - 消息消费者如何选择它希望接收的消息？  
- [Service Activator](https://www.enterpriseintegrationpatterns.com/patterns/messaging/MessagingAdapter.html) - 应用程序如何设计既可通过各种消息传递技术又可通过非消息传递技术调用的服务？
- [Smart Proxy](https://www.enterpriseintegrationpatterns.com/patterns/messaging/SmartProxy.html) - 您如何跟踪将回复消息发布到请求者指定的返回地址的服务上的消息？
- [Splitter](https://www.enterpriseintegrationpatterns.com/patterns/messaging/Sequencer.html) - 如果消息包含多个元素，我们如何处理消息，每个元素可能必须以不同的方式处理？  
- [Test Message](https://www.enterpriseintegrationpatterns.com/patterns/messaging/TestMessage.html) - 但是，如果组件正在积极处理消息，但由于内部故障而使传出的消息出现乱码，会发生什么情况？  
- [Transactional Client](https://www.enterpriseintegrationpatterns.com/patterns/messaging/TransactionalClient.html) - 客户端如何控制其与消息系统的交易？  
- [Wire Tap](https://www.enterpriseintegrationpatterns.com/patterns/messaging/WireTap.html) - 您如何检查在点对点通道上传输的消息？  

### Integration Styles
- [File Transfer](https://www.enterpriseintegrationpatterns.com/patterns/messaging/FileTransferIntegration.html)
- [Messaging](https://www.enterpriseintegrationpatterns.com/patterns/messaging/Messaging.html)
- [Remote Procedure Invocation](https://www.enterpriseintegrationpatterns.com/patterns/messaging/EncapsulatedSynchronousIntegration.html)
- [Shared Database](https://www.enterpriseintegrationpatterns.com/patterns/messaging/SharedDataBaseIntegration.html)

### Market Analysis
- API管理
  - [Gartner Critical Capabilities for Full Life Cycle API Management](https://www.gartner.com/doc/code/468184)
  - [Gartner Magic Quadrant for Full Life Cycle API Management](https://www.gartner.com/doc/code/464116)
  - [The Forrester Wave: API Management Solutions](https://www.forrester.com/go?objectid=RES159081)
- BPM
  - [Gartner Critical Capabilities for Intelligent Business Process Management Suites](https://www.gartner.com/doc/code/292486)
  - [Gartner Magic Quadrant for Intelligent Business Process Management Suites](https://www.gartner.com/doc/code/345694)
-ETL
  - [Gartner Critical Capabilities for Data Integration Tools](https://www.gartner.com/doc/code/464068)
  - [Gartner Magic Quadrant for Data Integration Tools](https://www.gartner.com/doc/code/450251)
- iPaaS
  - [Gartner Critical Capabilities for Enterprise Integration Platform as a Service](https://www.gartner.com/doc/code/434187)
  - [Gartner Magic Quadrant for Enterprise Integration Platform as a Service](https://www.gartner.com/doc/code/397953)
  - [The Forrester Wave: Enterprise iPaaS](https://www.forrester.com/report/the-forrester-wave-tm-enterprise-ipaas-q4-2021/RES176201)
- 机器人流程自动化
  - [Gartner Critical Capabilities for Robotic Process Automation](https://www.gartner.com/doc/code/465756)
  - [Gartner Magic Quadrant for Robotic Process Automation](https://www.gartner.com/doc/code/441474)
  - [The Forrester Wave: Robotic Process Automation](https://www.forrester.com/go?objectid=RES161538)

### Protocols
- [AMQP 0-9-1](https://www.rabbitmq.com/resources/specs/amqp0-9-1.pdf) - 高级消息队列协议 (AMQP) 版本 0-9-1.
- [AMQP 1.0](http://docs.oasis-open.org/amqp/core/v1.0/os/amqp-core-overview-v1.0-os.html) - 高级消息队列协议 (AMQP) 1.0 版.
- [CoAP](http://coap.technology/) - 受限应用协议 (CoAP) 是受限设备的专用互联网应用协议，如 RFC 7252 中所定义.
- [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) - 超文本传输​​协议 (HTTP) 是分布式协作超媒体信息系统的应用层协议.
- [JSON-RPC](https://www.jsonrpc.org/specification) - 设计简单，它是一种无状态、轻量级的远程过程调用 (RPC) 协议.
- [MQTT](https://mqtt.org/mqtt-specification/) - 消息队列遥测传输 (MQTT) 是一种轻量级的发布-订阅网络协议，可在设备之间传输消息.
- [SOAP](https://www.w3.org/TR/soap/) - 简单对象访问协议是基于 XML 的消息传递协议. 
- [STOMP](https://stomp.github.io/) - 简单（或流式）面向文本的消息传递协议.

### Standard APIs
- [JDBC](https://docs.oracle.com/javase/8/docs/technotes/guides/jdbc/) - Java 数据库连接 (JDBC) API 提供从 Java 编程语言进行的通用数据访问.
- [JMS](https://javaee.github.io/jms-spec/) - Java 消息服务 (JMS) API.
- [ODBC](https://docs.microsoft.com/en-us/sql/odbc/reference/odbc-overview) - 开放式数据库连接 (ODBC) 是一种广泛接受的用于数据库访问的应用程序编程接口 (API).
- [OData](https://www.odata.org/) - 一种开放协议，允许以简单和标准的方式创建和使用可查询和可互操作的 REST API.

### Structure and Validation
- [JSON Schema](https://json-schema.org/) - 用于验证 JSON 数据结构的强大工具.
- [Schematron](https://www.schematron.com) - 一种基于规则的验证语言，用于业务规则验证、数据报告、一般验证、质量控制、质量保证、防火墙、过滤、约束检查、命名和设计规则检查、统计一致性、数据探索、转换测试、特征提取和房屋-样式规则检查.
- [XML Schema](https://www.w3.org/TR/xmlschema11-1/) - 提供描述结构和限制 XML 文档内容的工具.

## Contributing
随时欢迎您的贡献！ 请看一下 [contribution guidelines](https://github.com/stn1slv/awesome-integration/blob/main/CONTRIBUTING.md) 第一的.
