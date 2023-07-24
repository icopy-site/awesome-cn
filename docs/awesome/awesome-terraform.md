<div class="github-widget" data-repo="shuaibiyy/awesome-terraform"></div>
## Awesome Terraform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->

&gt; 精选的资源列表 [HashiCorp's Terraform](https://www.terraform.io/).
> [<img src="https://rawgit.com/shuaibiyy/awesome-terraform/master/terraform.svg" align="right" width="100">](https://terraform.io)
&gt; 你 [contributions](https://github.com/shuaibiyy/awesome-terraform/blob/master/contributing.md) 受欢迎的！

 Terraform 使您能够安全且可预测地创建、更改和改进生产基础设施. 它是一个开源工具，可将 API 编码为声明性配置文件，这些文件可以在团队成员之间共享、视为代码、进行编辑、审查和版本控制.



## Legend

- 与 _terraform &gt;= 0.12_ 不兼容：ghost：
- 被遗弃的：头骨：
- 货币化：heavy_dollar_sign：

## Official Resources

- [Hashicorp Terraform Blog](https://www.hashicorp.com/blog/products/terraform)
- [Introduction to Terraform](https://www.terraform.io/intro/)
- [Terraform Documentation](https://www.terraform.io/docs/)
- [Terraform GitHub Actions](https://github.com/hashicorp/setup-terraform)
- [Terraform learn](https://learn.hashicorp.com/terraform/)

## Community

- [weekly.tf - Terraform Weekly Newsletter](https://weekly.tf) - Terraform 世界中的各种新闻（项目、公告、讨论）.
- [Complete Terraform documentation as PDF files (Updated nightly)](https://github.com/antonbabenko/terraform-docs-as-pdf)
- [Terraform AWS Modules](https://github.com/terraform-aws-modules) + [meta-configurations repository](https://github.com/terraform-aws-modules/meta)
- [Terraform Bug Tracker](https://github.com/hashicorp/terraform/issues)
- [Terraform Community Modules](https://github.com/terraform-community-modules)
- [Terraform Twitter Community](https://twitter.com/i/communities/1501688565884928007) <!-- markdown-link-check-disable-line -->
- [Terraform Discuss](https://discuss.hashicorp.com/c/terraform-core/27)
- [Terraform Provider/Module Registry](https://registry.terraform.io/)
- [Terraform PDF Doc](https://github.com/dohsimpson/terraform-doc-pdf) ：颅骨：
- [Terragrunt Reference Architecture](https://github.com/antonbabenko/terragrunt-reference-architecture)
- 特定语言社区：
  - [Telegram (Ukrainian speak community)](https://t.me/terraform_ukraine)

## Books

- [Big Little Book On Terraform](https://www.amazon.com/Big-Little-Book-Terraform-Omos-ebook/dp/B07PWYPNX8/)
- [Bootstrapping Microservices with Docker, Kubernetes, and Terraform, Second Editon](https://www.manning.com/books/bootstrapping-microservices-with-docker-kubernetes-and-terraform-second-edition)
- [Deep-Dive Terraform on Azure](https://link.springer.com/book/10.1007/978-1-4842-7328-9)
- [Getting Started with Terraform, 2nd ed.](https://www.amazon.com/Getting-Started-Terraform-production-infrastructure/dp/1788623533/)
- [HashiCorp Infrastructure Automation Certification Guide](https://www.amazon.com/HashiCorp-Infrastructure-Automation-Certification-Guide-ebook/dp/B092KM7LXC/)
- [Infrastructure as Code](http://shop.oreilly.com/product/0636920039297.do)
- [Patterns and Practices for Infrastructure as Code: With examples in Python and Terraform](https://www.manning.com/books/patterns-and-practices-for-infrastructure-as-code)
- [Terraform Best Practices](https://www.terraform-best-practices.com/) - [open-source ebook](https://github.com/antonbabenko/terraform-best-practices)
- [Terraform Cookbook](https://www.amazon.com/Terraform-Cookbook-Efficiently-Infrastructure-platforms/dp/1800207557)
- [Terraform in Action](https://www.manning.com/books/terraform-in-action)
- [Terraform: Up & Running, 3rd ed.](https://www.terraformupandrunning.com/)
- [The Terraform Book](https://terraformbook.com/)
- [IaC starting with Terraform(Korean)](https://product.kyobobook.co.kr/detail/S000202478097)

## Tutorials and Blog Posts

### Beginner Guides

- [A Comprehensive Guide to Terraform](https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca#.w9x897ywp) - 《Terraform：启动和运行》作者的一系列博客文章，引导读者从开始使用 Terraform 到在现实世界中使用它.
- [Using Terraform for Cloud Deployments - Part 1](https://dev.to/koenighotze/using-terraform-for-cloud-deployments---part-1) - 配置 EC2 实例.
- [Hello, world: The Fargate/Terraform tutorial I wish I had](https://section411.com/2019/07/hello-world/) - 描述从头开始设置 ECS Fargate 集群的博客文章
- [Terraform Security Guide](https://sysdig.com/blog/terraform-security-best-practices/) - 描述使用 Terraform 时的安全最佳实践的博客文章

### Writing Custom Providers

- [Creating custom terraform providers](https://medium.com/@jozmo/creating-custom-terraform-providers-341311823fa2) - 创建自定义提供程序的指南.
- [Writing a Terraform provider](https://web.archive.org/web/20220516140659/http://blog.jfabre.net/2017/01/22/writing-terraform-provider/) - 创建自定义提供程序的指南.
- [Writing Custom Providers](https://www.terraform.io/docs/extend/writing-custom-providers.html) - 创建自定义提供程序的官方文档.

### How-To

- [How To Write OPA for Terraform](https://www.scalr.com/blog/opa-series-part-1-open-policy-agent-and-terraform/) - 如何使用开放策略代理来评估和执行 Terraform 计划上的策略
- [Deploying Discourse with Terraform](https://web.archive.org/web/20181001135342/http://www.hashicorp.com/blog/deploying-discourse-with-terraform) - 展示 Terraform 如何通过一个命令在 DigitalOcean 上创建 Discourse 的运行实例.
- [Deploying Django to AWS ECS with Terraform](https://testdriven.io/blog/deploying-django-to-ecs-with-terraform/) - 了解如何使用 Terraform 启动在 ECS 上运行 Django 应用程序所需的 AWS 基础设施.
- [Easily Deploy A Seneca Microservice to ECS with Wercker and Terraform: Part I](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/), [II](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-ii/) & [III](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/) - 说明如何将 Terraform 合并到微服务部署管道中.
- [Terraform for a Highly Available VPN between AWS and Azure](https://web.archive.org/web/20210616132857/https://deployeveryday.com/2020/04/13/vpn-aws-azure-terraform.html) - 用于在 AWS 和 Azure 之间部署高度可用的 VPN 的 Terraform 代码.
- [Terraforming 1Password](https://blog.agilebits.com/2018/01/25/terraforming-1password/) - 1Password 如何从 CloudFormation 迁移到 Terraform.
- [Tutorial: How to Use Terraform to Deploy OpenStack Workloads](https://web.archive.org/web/20170611135511/http://www.stratoscale.com/blog/openstack/tutorial-how-to-use-terraform-to-deploy-openstack-workloads/) - 说明使用 OpenStack Terraform 提供程序部署 Web 服务器是多么容易.
- [Zero Downtime Updates with HashiCorp Terraform](https://www.hashicorp.com/blog/zero-downtime-updates-with-terraform) - 确保基础设施零停机.
- [Google Cloud Platform for 10$ a month using terraform](https://github.com/nufailtd/terraform-budget-gcp) - Shows how to use terraform to create a secure Google Kubernetes Cluster, Google Cloud Run Services and other infrastructure elements for less than [10$](https://nufailtd.github.io/budget-gcp/) 一个月.
- [Infracost + Terraform + GitHub Actions = Automate Cloud Cost Management](https://betterprogramming.pub/infracost-terraform-github-actions-automate-cloud-cost-management-a62b329f2834?sk=495131c5831bc9276369150da5f3bc2c) - 如何在 Terraform 开发过程中使用 Infracost 作为护栏来管理云成本.

### Multi-Environment Configuration

- [Terraform Design Patterns: the Terrafile](http://bensnape.com/2016/01/14/terraform-design-patterns-the-terrafile/) - 使用 Terrafile 管理 Terraform 项目中的 Terraform 模块及其版本.
- [Terraform, VPC, and why you want a tfstate file per env](https://charity.wtf/2016/03/30/terraform-vpc-and-why-you-want-a-tfstate-file-per-env/) - 在具有多个环境的大型项目中使用 Terraform 时遇到的一些问题以及如何避免它们.
- [Using Pipelines to Manage Environments with Infrastructure as Code](https://medium.com/@kief/https-medium-com-kief-using-pipelines-to-manage-environments-with-infrastructure-as-code-b37285a1cbf5) - 解释了构建管道以处理从一种环境到另一种环境的基础设施变化的不同方法.

### Azure

- [Learning HashiCorp Terraform](https://web.archive.org/web/20201108000713/https://www.g10s.io/hashicorp-terraform/) - Azure 指南.
- [New Terraform Azure Automation Resources](https://bgelens.nl/terraform-automation-resources/) - Azure 自动化.
- [Terraforming Azure PaaS](https://devkimchi.com/2019/01/21/terraforming-azure-paas/) - 在 Azure 上部署 PaaS 资源.

### AWS

- [AWS Lambda the Terraform Way](https://github.com/nsriram/lambda-the-terraform-way)  - 除了执行函数之外，还使用 ​​Terraform 深入了解 AWS Lambda. 还包括与 S3、API Gateway、DynamoDB、Kinesis、SQS 集成的指南.
- [Managing AWS Lambda Functions with Terraform](https://spacelift.io/blog/terraform-aws-lambda) - AWS Lambda 的用途是什么以及如何使用 Terraform 管理 AWS Lambda 函数？

### Google Cloud
- [Managing infrastructure as code with Terraform, Cloud Build, and GitOps](https://cloud.google.com/architecture/managing-infrastructure-as-code) - 使用 Terraform、Cloud Build 和 GitOps 设置和管理基础设施即代码.
- [Getting started with Terraform on Google Cloud](https://cloud.google.com/community/tutorials/getting-started-on-gcp-with-terraform) - 使用 Terraform 在 Google Cloud 中创建虚拟机并启动基本的 Python Flask 服务器.
- [Managing Cloud Infrastructure with Terraform](https://www.cloudskillsboost.google/quests/44) - 使用 Terraform 部署 Kubernetes 负载均衡器服务、使用 Terraform 部署基于 HTTPS 内容的负载均衡器、使用 Terraform 进行模块化负载均衡 - 区域负载均衡器、使用 Terraform 的自定义提供商、使用 Terraform 的 Cloud SQL、使用 Terraform 在 Google Cloud 和 AWS 之间构建 VPN.
- [Hashicorp Terraform Tutorials for Google Cloud](https://learn.hashicorp.com/collections/terraform/gcp-get-started) - 开始使用 Google Cloud 上的 Terraform.

### Miscellaneous

- [Sharing data between Terraform configurations](https://jamesmckay.net/2016/09/sharing-data-between-terraform-configurations/) - 说明如何使用远程状态在 Terraform 配置之间共享数据.
- [The Segment AWS Stack](https://segment.com/blog/the-segment-aws-stack/) - 显示由 Terraform 提供支持的基础设施的幕后解决方案 [The Million Dollar Engineering Problem](https://segment.com/blog/the-million-dollar-eng-problem/) 在 [Segment](https://segment.com/).
- [Top 3 Terraform Testing Strategies for Ultra-Reliable Infrastructure-as-Code](https://www.contino.io/insights/top-3-terraform-testing-strategies-for-ultra-reliable-infrastructure-as-code)
- [Two Weeks with Terraform](https://charity.wtf/2016/02/23/two-weeks-with-terraform/) - 在野外使用 Terraform 时获得的一些来之不易的经验，以及一些操作智慧.
- [Terraform: Beyond the Basics with AWS](https://aws.amazon.com/blogs/apn/terraform-beyond-the-basics-with-aws/) - 说明使用 Terraform 来配置示例 AWS 架构的演示.
- [Terraform cost estimation](https://github.com/antonbabenko/terraform-cost-estimation) - 基于 Terraform 计划 (0.12+) 或 Terraform 状态（任何版本）的匿名、安全且免费的 Terraform 成本估算.
- [How to Debug Terraform Projects: Tutorial](https://spacelift.io/blog/terraform-debug)

## Community Modules

有关此处未列出的更多社区模块，请参阅 [Terraform Module Registry](https://registry.terraform.io/).

- [rancher-terraform-digitalocean](https://github.com/lunagt/rancher-terraform-digitalocean) - digitalocean 上的 Rancher 服务器.
- [segmentio/stack](https://github.com/segmentio/stack) - 使用 AWS、Docker 和 ECS 配置生产基础设施.
- [terraform-aws-alb](https://github.com/terraform-aws-modules/terraform-aws-alb) - 在 AWS 上创建应用程序负载均衡器（经过验证的模块）.
- [terraform-aws-appconfig](https://github.com/clowdhaus/terraform-aws-appconfig) - 在 AWS 上创建 AWS AppConfig 资源.
- [terraform-aws-atlantis](https://github.com/terraform-aws-modules/terraform-aws-atlantis) - 创建用于运行的 Terraform 配置 [Atlantis](https://runatlantis.io) 在 AWS Fargate 上. 支持 Github、Gitlab 和 BitBucket.
- [terraform-aws-autoscaling](https://github.com/terraform-aws-modules/terraform-aws-autoscaling) - 创建自动缩放组和启动配置（已验证模块）.
- [terraform-aws-customer-gateway](https://github.com/terraform-aws-modules/terraform-aws-customer-gateway) - 在 AWS 上创建客户网关.
- [terraform-aws-datadog-forwarders](https://github.com/clowdhaus/terraform-aws-datadog-forwarders) - 在 AWS 上创建资源以将日志/指标转发到 Datadog.
- [terraform-aws-dms](https://github.com/clowdhaus/terraform-aws-dms) - 在 AWS 上创建 AWS DMS（数据库迁移服务）资源.
- [terraform-aws-dynamodb-table](https://github.com/terraform-aws-modules/terraform-aws-dynamodb-table) - 在 AWS 上创建 DynamoDB 表.
- [terraform-aws-ec2-instance](https://github.com/terraform-aws-modules/terraform-aws-ec2-instance) - 在 AWS 上创建 EC2 实例.
- [terraform-aws-ecr](https://github.com/cloudposse/terraform-aws-ecr) - 管理 AWS ECR 上的 Docker 容器注册表.
- [terraform-aws-ecs](https://github.com/terraform-aws-modules/terraform-aws-ecs) - 在 AWS 上创建 AWS ECS 资源.
- [terraform-aws-efs](https://github.com/cloudposse/terraform-aws-efs) - 定义 EFS 文件系统.
- [terraform-aws-eks](https://github.com/terraform-aws-modules/terraform-aws-eks) - 在 AWS 上创建 Elastic Kubernetes 服务（非常受欢迎的模块）.
- [terraform-aws-elb](https://github.com/terraform-aws-modules/terraform-aws-elb) - 在 AWS 上创建弹性负载均衡器（经过验证的模块）.
- [terraform-aws-eventbridge](https://github.com/terraform-aws-modules/terraform-aws-eventbridge) - 在 AWS 上创建 EventBridge 资源.
- [terraform-aws-jenkins-ha-agents](https://github.com/neiman-marcus/terraform-aws-jenkins-ha-agents)  - 基于 EC2 的 Jenkins 部署，具有 HA（现货）代理. 在 EFS 上运行以实现不变性. 完全可定制，具有合理的默认值.
- [terraform-aws-jenkins](https://github.com/cloudposse/terraform-aws-jenkins) - 使用 Jenkins 构建 Docker 映像，将其保存到 ECR 存储库，并将其部署到运行 Docker 堆栈的 Elastic Beanstalk.
- [terraform-aws-key-pair](https://github.com/cloudposse/terraform-aws-key-pair) - 自动生成 SSH 密钥对（公钥/私钥）.
- [terraform-aws-lambda](https://github.com/terraform-aws-modules/terraform-aws-lambda) - Terraform 模块，它构建依赖项和包，并以无数组合创建 AWS Lambda 资源.
- [terraform-aws-lambda-auto-package](https://github.com/nozaq/terraform-aws-lambda-auto-package) - 一个 terraform 模块，用于定义 lambda 函数，自动构建和打包源文件以进行 lambda 部署.
- [terraform-aws-managed-service-prometheus](https://github.com/clowdhaus/terraform-aws-managed-service-prometheus) - 在 AWS 上创建 AWS Managed Service for Prometheus (AMP) 资源.
- [terraform-aws-modules](https://github.com/terraform-aws-modules) - 社区支持的 Terraform AWS 模块集合（包括官方 AWS 模块）.
- [terraform-aws-msk-kafka-cluster](https://github.com/clowdhaus/terraform-aws-msk-kafka-cluster) - 在 AWS 上创建 AWS MSK（Kafka 托管流）资源.
- [terraform-aws-notify-slack](https://github.com/terraform-aws-modules/terraform-aws-notify-slack) - 创建 SNS 主题和 Lambda 函数，用于向 Slack 发送通知.
- [terraform-aws-postgresql-rds](https://github.com/azavea/terraform-aws-postgresql-rds) - 在 RDS 上创建 PostgreSQL.
- [terraform-aws-rds](https://github.com/terraform-aws-modules/terraform-aws-rds) - 在 AWS 上创建 RDS 资源（已验证模块）.
- [terraform-aws-rds-aurora](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora) - 在 AWS 上创建 RDS Aurora 集群资源（已验证模块）.
- [terraform-aws-rds-proxy](https://github.com/clowdhaus/terraform-aws-rds-proxy) - 在 AWS 上创建 AWS RDS 代理资源.
- [terraform-aws-redshift](https://github.com/terraform-aws-modules/terraform-aws-redshift) - 在 AWS 上创建 Redshift 资源.
- [terraform-aws-route53](https://github.com/terraform-aws-modules/terraform-aws-route53) - 在 AWS 上创建 Route53 资源.
- [terraform-aws-secure-baseline](https://github.com/nozaq/terraform-aws-secure-baseline) - 使用基于 CIS Amazon Web Services Foundations 的安全基线配置设置您的 AWS 账户.
- [terraform-aws-security-group](https://github.com/terraform-aws-modules/terraform-aws-security-group) - 在 AWS 上创建 EC2-VPC 安全组（已验证模块）.
- [terraform-aws-ssh-bastion-service](https://github.com/joshuamkite/terraform-aws-ssh-bastion-service) - Terraform 计划将 ssh 堡垒部署为 AWS 上的无状态服务.
- [terraform-aws-s3-bucket](https://github.com/terraform-aws-modules/terraform-aws-s3-bucket) - 在 AWS 上创建 S3 存储桶资源.
- [terraform-aws-transit-gateway](https://github.com/terraform-aws-modules/terraform-aws-transit-gateway) - 在 AWS 上创建 Transit Gateway 资源.
- [terraform-aws-vpc](https://github.com/terraform-aws-modules/terraform-aws-vpc) - 在AWS上创建VPC资源（经过验证且非常流行的模块）.
- [terraform-aws-vpn-gateway](https://github.com/terraform-aws-modules/terraform-aws-vpn-gateway) - 在 AWS 上创建 VPN 网关资源.
- [terraform-azurerm-aks](https://github.com/kjanshair/terraform-azurerm-aks) - 在 Azure 上创建 AKS 资源.
- [terraform-azurerm-iis](https://github.com/ghostinthewires/terraform-azurerm-iis-install) - 在 Azure VM 实例上安装 IIS 服务器.
- [terraform-azurerm-mysql](https://github.com/foreverXZC/terraform-azurerm-mysql) - 在 Azure 上创建 MySql 数据库.
- [terraform-azurerm-redis](https://github.com/rahulkhengare/terraform-azurerm-redis) - 在 Azure 上创建 Redis.
- [terraform-azurerm-sqlserver](https://github.com/metadevpro/terraform-azurerm-sqlserver-seed) - 在 Azure 上创建 SQL Server 数据库.
- [terraform-cloudflare-maintenance](https://github.com/adinhodovic/terraform-cloudflare-maintenance) - 使用 Cloudflare Workers 创建维护页面的模块.
- [terraform-digitalocean-droplet](https://registry.terraform.io/modules/terraform-digitalocean-modules/droplet/digitalocean) - 用于管理 DigitalOcean Droplet 和相关资源的 Terraform 模块.
- [terraform-ecs-jenkins](https://github.com/shuaibiyy/terraform-ecs-jenkins) - 使用 Terraform 在 AWS ECS 上配置 Jenkins.
- [terraform-gce-atlantis](https://github.com/bschaatsbergen/terraform-gce-atlantis) - 创建用于运行的 Terraform 配置 [Atlantis](https://runatlantis.io) 在谷歌计算引擎上.
- [terraform-google-project-factory](https://github.com/terraform-google-modules/terraform-google-project-factory) - 使用共享 VPC、IAM、API 等自行创建和配置 Google Cloud Platform 项目.
- [terraform-linode-k8s](https://registry.terraform.io/modules/linode/k8s/linode/) - 在 Linode 实例上安装 Kubernetes.
- [terraform-static-website-s3-cloudfront](https://github.com/sjevs/terraform-static-website-s3-cloudfront) - 基于变量在 AWS S3 和 Cloudfront 上创建静态网站.
- [tf_aws_bastion_s3_keys](https://github.com/terraform-community-modules/tf_aws_bastion_s3_keys) - 在 AWS EC2 上创建堡垒主机.

## Private Module Registries

- [anthology](https://github.com/erikvanbrakel/anthology) - 私有 Terraform 注册表实现作为官方注册表的替代方案.
- [citizen](https://github.com/outsideris/citizen) - 私有 Terraform 模块注册表
- [tapir](https://github.com/PacoVK/tapir)  - 具有提供程序和模块支持的模块化私有 Terraform 注册表平台. 提供强大的 UI 生成安全指标、依赖关系可视化和自动生成文档.
- [terraform-simple-registry](https://github.com/apparentlymart/terraform-simple-registry) - Terraform 注册表协议的简单实现.
- [terraform-registry](https://github.com/philips-labs/terraform-registry) - 提供由 GitHub 版本支持的 terraform 提供程序注册表.
- [Terrareg](https://github.com/matthewjohn/terrareg) - 私有 Terraform 模块注册表，具有 UI 和 git 支持的索引/导入、成本估算、安全分析、资源图表、API 和单点登录

## Private Provider Registries

- [terustry](https://github.com/veepee-oss/terustry) - 开源 terraform 提供程序注册表，充当 gitlab 或 github 版本的代理.

## Providers

### Hashicorp supported providers

- [terraform-provider-aws](https://github.com/hashicorp/terraform-provider-aws) - 亚马逊网络服务提供商.
- [terraform-provider-azurerm](https://github.com/hashicorp/terraform-provider-azurerm) - Azure 提供商.
- [terraform-provider-docker](https://github.com/hashicorp/terraform-provider-docker) - Docker 的提供者.
- [terraform-provider-google](https://github.com/hashicorp/terraform-provider-google) - Google 云平台提供商.
- [terraform-provider-helm](https://github.com/hashicorp/terraform-provider-helm) - Helm 的提供者.
- [terraform-provider-kubernetes](https://github.com/hashicorp/terraform-provider-kubernetes) - Kubernetes 的提供商.
- [terraform-provider-vsphere](https://github.com/hashicorp/terraform-provider-vsphere) - VMware vSphere 提供商.

### Vendor supported providers

- [terraform-provider-alicloud](https://github.com/aliyun/terraform-provider-alicloud) - 阿里云提供商.
- [terraform-provider-artifactory](https://github.com/jfrog/terraform-provider-artifactory) - 提供者 [JFrog Artifactory](https://jfrog.com/artifactory/).
- [terraform-provider-atlas](https://github.com/ariga/terraform-provider-atlas) - 提供者 [Atlas](https://atlasgo.io/).
- [terraform-provider-azapi](https://github.com/Azure/terraform-provider-azapi) - Azure 资源管理器 Rest API 的提供者
- [terraform-provider-azuredevops](https://github.com/microsoft/terraform-provider-azuredevops) - Azure DevOps (VSTS) 提供商.
- [terraform-provider-buildkite](https://github.com/buildkite/terraform-provider-buildkite) - Buildkite 的提供商.
- [terraform-provider-checkly](https://github.com/checkly/terraform-provider-checkly) - 管理 [Checkly](https://www.checklyhq.com) API 和 E2E 监控资源.
- [terraform-provider-confluent](https://github.com/confluentinc/terraform-provider-confluent) - Confluence 的提供者.
- [terraform-provider-datadog](https://github.com/DataDog/terraform-provider-datadog) - Datadog 的提供商.
- [terraform-provider-digitalocean](https://github.com/digitalocean/terraform-provider-digitalocean) - DigitalOcean 的提供商.
- [terraform-provider-dominos](https://github.com/ndmckinley/terraform-provider-dominos) - 多米诺披萨供应商.
- [terraform-provider-env0](https://github.com/env0/terraform-provider-env0) - 提供者 [env0](https://www.env0.com/)
- [terraform-provider-github](https://github.com/integrations/terraform-provider-github) - GitHub 的提供商.
- [terraform-provider-gitlab](https://github.com/gitlabhq/terraform-provider-gitlab) - GitLab 的提供商.
- [terraform-provider-graphql](https://github.com/sullivtr/terraform-provider-graphql) - GraphQL 查询和突变的提供者.
- [terraform-provider-hcloud](https://github.com/hetznercloud/terraform-provider-hcloud) - Hetzner 云提供商.
- [terraform-provider-healthchecksio](https://github.com/kristofferahl/terraform-provider-healthchecksio) - 管理 healthchecks.io 资源的提供商.
- [terraform-provider-heroku](https://github.com/heroku/terraform-provider-heroku) - Heroku 的提供商.
- [terraform-provider-ibm](https://github.com/IBM-Cloud/terraform-provider-ibm) - IBM Cloud 提供商.
- [terraform-provider-k8s](https://github.com/banzaicloud/terraform-provider-k8s) - 简单的 Kubernetes 提供程序，适用于任何清单.
- [terraform-provider-keycloak](https://github.com/mrparkers/terraform-provider-keycloak) - 管理您的设置的提供商 [Keycloak](https://www.keycloak.org/) 身份提供者服务器.
- [terraform-provider-linode](https://github.com/btobolaski/terraform-provider-linode) - Linode 的提供商.
- [terraform-provider-openstack](https://github.com/terraform-provider-openstack/terraform-provider-openstack) - OpenStack 插件.
- [terraform-provider-panos](https://github.com/PaloAltoNetworks/terraform-provider-panos) - 提供者 [Palo Alto Networks next-generation firewalls](https://www.paloaltonetworks.com/network-security).
- [terraform-provider-pingdom](https://github.com/russellcardullo/terraform-provider-pingdom) - 管理 Pingdom 资源的提供商.
- [terraform-provider-rancher2](https://github.com/rancher/terraform-provider-rancher2) - Rancher v2 的提供者.
- [terraform-provider-scalr](https://github.com/Scalr/terraform-provider-scalr) - 提供者 [Scalr](https://scalr.com)
- [terraform-provider-secrethub](https://github.com/secrethub/terraform-provider-secrethub) - SecretHub 的提供商.
- [terraform-provider-sigsci](https://github.com/signalsciences/terraform-provider-sigsci) - 信号科学提供商.
- [terraform-provider-snowflake](https://github.com/chanzuckerberg/terraform-provider-snowflake) - Snowflake 数据仓库的提供商.
- [terraform-provider-spinnaker](https://github.com/armory-io/terraform-provider-spinnaker) - 提供者 [Spinnaker](https://www.spinnaker.io/).
- [terraform-provider-spotinst](https://github.com/spotinst/terraform-provider-spotinst) - 现货供应商.
- [terraform-provider-stripe](https://github.com/franckverrot/terraform-provider-stripe) - Stripe 的提供商.
- [terraform-provider-terracurl](https://github.com/devops-rob/terraform-provider-terracurl) - 向您的目标端点发出托管和非托管 API 调用的提供商.
- [terraform-provider-ucloud](https://github.com/ucloud/terraform-provider-ucloud) - 管理UCloud资源的提供商.
- [terraform-provider-uptimerobot](https://github.com/louy/terraform-provider-uptimerobot) - 管理 uptimerobot 资源的提供商.
- [terraform-provider-vaulted](https://github.com/sumup-oss/terraform-provider-vaulted) - 通过 Terraform 加密的 HashiCorp Vault 机密可以存储在 SCM（例如 Git）中.
- [terraform-provider-iterative](https://github.com/iterative/terraform-provider-iterative) - Terraform 插件以机器学习为理念构建.

## Testing

- [kitchen-terraform](https://github.com/newcontext-oss/kitchen-terraform) - 提供一组 Test Kitchen 插件，使系统能够使用 Test Kitchen 聚合 Terraform 配置并使用 InSpec 控件验证生成的 Terraform 状态.
- [rspec-terraform](https://github.com/bsnape/rspec-terraform) - 针对 Terraform 模块的 RSpec 测试.
- [terraform-compliance](https://github.com/terraform-compliance/cli) - Terraform 文件的 BDD 测试.
- [terraform_validate](https://github.com/elmundio87/terraform_validate) - 协助在 Terraform 中执行用户定义的标准.
- [terratest](https://github.com/gruntwork-io/terratest) - Terratest 是一个 Go 库，可以更轻松地为基础设施代码编写自动化测试.
- [clarity](https://github.com/xchapter7x/clarity) - 用于单元测试的 Terraform 声明性测试框架.

## Tools

- [AIaC](https://github.com/gofireflyio/aiac) - 人工智能基础设施即代码生成器
- [AirIAM](https://github.com/bridgecrewio/AirIAM) - AirIAM 是 AWS IAM 最小化 Terraform 执行框架权限的工具.
- [Argonaut](https://argonaut.dev/)  - 只需几分钟即可在您的云上部署应用程序和基础设施. 自动生成 Terraform 模块，通过 PR 自定义配置. 支持 Kubernetes 和 Lambda 环境上的应用程序部署.
- [astro](https://github.com/uber/astro/)  - Astro 是一个用于将多个 Terraform 执行作为单个命令进行管理的工具.  ：鬼：
- [atmos](https://github.com/cloudposse/atmos)  - 一个通用工具，可将深度合并的 YAML 转换为模块输入.  ：外星人：
- [atlantis](https://github.com/runatlantis/atlantis) - 通过 GitHub 在 Terraform 上进行协作的统一工作流程.
- [aws2tf](https://github.com/aws-samples/aws2tf) - 自动将现有 AWS 资源导入 Terraform 并输出 Terraform HCL 代码.
- [aztfexport](https://github.com/Azure/aztfexport) - 将现有 Azure 资源置于 Terraform 管理之下的工具.
- [blast radius](https://github.com/28mm/blast-radius)  - Terraform 依赖图的交互式可视化.  ：颅骨：
- [Checkov](https://github.com/bridgecrewio/checkov/) - Terraform静态分析工具，terraform&gt;=0.12
- [Coder](https://coder.com/) - Coder 通过 Terraform 在您的基础设施上配置软件开发环境.
- [driftctl](https://github.com/snyk/driftctl) - 检测、跟踪基础设施偏差并发出警报
- [flora](https://github.com/ketchoop/flora) - Terraform 版本管理器.
- [fogg](https://github.com/chanzuckerberg/fogg) - 一种消除管理 terraform 存储库繁琐工作的工具.
- [former2](https://github.com/iann0036/former2) - 从您的 AWS 账户中的现有资源生成 terraform 配置.
- [fuzzy-terraform-rm](https://github.com/paololazzari/fuzzy-terraform-rm) - 模糊查找器命令行工具，用于从地形状态中删除资源.
- [gaia](https://github.com/gaia-app/gaia) - 用于导入和运行 Terraform 模块的 Web 应用程序.
- [hcldump](https://github.com/magodo/hcldump) - 转储 HCL (v2) 抽象语法树.
- [hcledit](https://github.com/minamijoyo/hcledit) - HCL 的命令行编辑器.
- [hclgrep](https://github.com/magodo/hclgrep) - HCL(v2) 的基于语法的 grep.
- [iam-policy-json-to-terraform](https://github.com/flosell/iam-policy-json-to-terraform) - 将 JSON 格式的 IAM 策略转换为 Terraform aws_iam_policy_document 的小工具
- [k2tf](https://github.com/sl1pm4t/k2tf) - Kubernetes YAML 到 Terraform HCL 转换器.
- [KICS](https://github.com/Checkmarx/kics)  - 扫描 IaC 项目是否存在安全漏洞、合规性问题和基础设施配置错误. 目前正在处理 Terraform 项目、Kubernetes 清单、Dockerfile、AWS CloudFormation 模板和 Ansible playbook.
- [Infracost](https://github.com/infracost/infracost) - CLI 和拉取请求中 Terraform 的云成本估算.
- [inframap](https://github.com/cycloidio/inframap) - 读取您的 tfstate 或 HCL 以生成特定于每个提供商的图表，仅显示最重要/相关的资源.
- [json2hcl](https://github.com/kvz/json2hcl)  - 将 JSON 转换为 HCL，反之亦然.  ：鬼：
- [modules.tf-lambda](https://github.com/antonbabenko/modules.tf-lambda) - 基础设施作为代码生成器，来自创建的可视化图表 [Cloudcraft.co](https://cloudcraft.co/app) 到地形.
- [para](https://github.com/paraterraform/para)  - 缺少的第 3 方插件管理器和 Terraform/Terragrunt 的“瑞士军刀” - 只需 1 个工具即可促进所有工作流程.  ：颅骨：
- [pluralith](https://www.pluralith.com/)  - Terraform 状态可视化和基础设施文档的自动生成.  ：重美元符号：
- [pre-commit-terraform](https://github.com/antonbabenko/pre-commit-terraform) - 预提交 git hooks 来处理 Terraform 配置（自动格式化、验证、更新文档）.
- [pike](https://github.com/jamesWoolfenden/pike) - Pike 计算构建 Terraform 所需的权限或 IAM 策略.
- [pretf](https://github.com/raymondbutcher/pretf)  - 插入 Terraform 包装器，使用 Python 生成 Terraform 配置. 看 [pretf documentation](https://pretf.readthedocs.io/en/latest/)
- [python-terrafile](https://github.com/claranet/python-terrafile) - 系统地管理来自 Github 的外部模块以在 Terraform 中使用.
- [prettyplan](https://github.com/chrislewisdev/prettyplan) - 漂亮的计划（[available online here](https://chrislewisdev.github.io/prettyplan/) ) 是一个小工具，可帮助您轻松查看大型 Terraform 计划.  ：鬼：
- [regula](https://github.com/fugue/regula) - 在部署之前评估 Terraform 基础设施即代码是否存在潜在的 AWS、Azure 和 Google Cloud 安全配置错误和合规性违规.
- [rover](https://github.com/im2nguyen/rover) - 交互式 Terraform 状态和配置资源管理器.
- [ruby-terraform](https://github.com/infrablocks/ruby_terraform) - 用于调用 terraform 命令的简单 Ruby 包装器.
- [sato](https://github.com/JamesWoolfenden/sato) - Sato 帮助您将遗留的 Cloudformation 转换为 Terraform.
- [scenery](https://github.com/dmlittle/scenery)  - 另一个 Terraform 计划输出美化器.  ：鬼：
- [scratchrelaxtv](https://github.com/YakDriver/scratchrelaxtv) - 帮助模块开发的简单 Python 工具 - 从“main.tf”中提取变量以生成“variables.tf”并从“variables.tf”制作模块使用存根.
- [serverless.tf - Doing serverless with Terraform](https://serverless.tf/) - serverless.tf 是一个固执己见的开源框架，用于使用 Terraform 在 AWS 上开发、构建、部署和保护无服务器应用程序和基础设施. [Read more](https://github.com/antonbabenko/serverless.tf).
- [Shisho](https://github.com/flatt-security/shisho) - Terraform 的轻量级静态分析器.
- [Styra Declarative Authorization Service (DAS)](https://www.styra.com/terraform-cloud-config-management-with-styra-das-and-open-policy-agent) - 提供托管 [Open Policy Agent (OPA)](https://www.openpolicyagent.org) 应用程序和基础设施用例的平台，包括 Terraform、Terraform Cloud 和 Kubernetes. 在开发期间、CI/CD 管道中以及部署时实施策略护栏.  Styra DAS Free 提供多个系统和用户、策略影响分析、决策记录和重播以及对 Styra Terraform 策略库的访问.
- [tads-boilerplate](https://github.com/Thomvaill/tads-boilerplate) - Ansible 和 Terraform 的强大功能 + Docker Swarm 的简单性 = 基础设施即代码和 DevOps 最佳实践.
- [tau](https://github.com/avinor/tau) - Tau 是 terraform 之上的一个薄包装器，用于管理多个部署、依赖项和机密.
- [terraboard](https://github.com/camptocamp/terraboard) - 用于检查 Terraform 状态的 Web 仪表板.
- [terraboot](https://github.com/MastodonC/terraboot) - DSL 用于生成 terraform 配置并运行它.
- [terracognita](https://github.com/cycloidio/terracognita) - 从现有云提供商读取（反向 Terraform）并生成基础设施作为 Terraform 配置上的代码.
- [terracost](https://github.com/cycloidio/terracost) - CLI 中 Terraform 的云成本估算.
- [TerraDepot](https://github.com/derBroBro/TerraDepot)  Terraform 状态存储库，基于默认的 http 远程后端. 允许对 AWS S3 上的 tfstate 进行集中管理.
- [terradozer](https://github.com/jckuester/terradozer) - Terraform 无需配置文件即可销毁.
- [terrafile](https://github.com/coretech/terrafile) - 系统地管理来自 Github 的外部模块，以便在 Terraform 中使用（用 Go 编写）.
- [terrafile](https://github.com/dxw/terrafile) - 系统地管理来自 Github 的外部模块，以便在 Terraform 中使用（用 Ruby 编写）.
- [terraform-bundle](https://github.com/hashicorp/terraform/tree/master/tools/terraform-bundle)  - 轻松构建包含 Terraform 二进制文件以及提供程序二进制文件的捆绑包. 对于 CI 和气隙 Terraform Enterprise 很有用.
- [terraform-cdk](https://github.com/hashicorp/terraform-cdk) - Terraform 的 CDK（云开发工具包）允许开发人员使用熟悉的编程语言来定义云基础设施并通过 HashiCorp Terraform 进行配置.
- [terraform-iam-policy-validator](https://github.com/awslabs/terraform-iam-policy-validator) - CLI 根据 AWS IAM 最佳实践验证 Terraform 模板中的 AWS IAM 策略.
- [terraform-credentials-vault](https://github.com/oulman/terraform-credentials-vault) - Terraform“凭据帮助程序”插件，允许通过环境变量为 Terraform 原生服务（私有模块注册表、Terraform Cloud 等）提供凭据.
- [terraform-diff](https://github.com/contentful-labs/terraform-diff) - 始终知道您需要在哪里运行 Terraform 计划并申请！
- [terraform-docs](https://github.com/terraform-docs/terraform-docs) - 从 terraform 模块生成文档的快速实用程序.
- [terraform-graph-beautifier](https://github.com/pcasteran/terraform-graph-beautifier) - 命令行工具允许将 terraform graph 命令几乎不可用的输出转换为更有意义和解释性的内容.
- [terraform-landscape](https://github.com/coinbase/terraform-landscape) - *（仅 0.11 及更早版本）* 改进 Terraform 的计划输出，使其更易于阅读和理解.
- [terraform-operator](https://github.com/isaaguilar/terraform-operator.git) - 用于处理 Terraform 操作的 Kubernetes CRD.
- [terraform-plan-parser](https://github.com/lifeomic/terraform-plan-parser)  - 命令行实用程序和 JavaScript API，用于从“terraform plan”解析标准输出并将其转换为 JSON.  ：鬼：
- [terraform-provisioner](https://github.com/shuaibiyy/terraform-provisioner) - 用于管理相同 Terraform 脚本的多个规定的工具.
- [terraform-rake-tasks](https://github.com/gina-alaska/terraform-rake-tasks) - 用于管理地形计划的共享 Rake 任务.
- [terraform-repl](https://github.com/paololazzari/terraform-repl) - terraform 控制台包装器，提供更好的交互式控制台体验.
- [terraform.py](https://github.com/ciscocloud/terraform.py) - 用于解析 Terraform 状态文件的 Ansible 动态清单脚本.
- [terraformer](https://github.com/GoogleCloudPlatform/terraformer)  - 用于从现有基础设施生成 terraform 文件的 CLI 工具. 基础设施到代码. 支持许多提供商.
- [terraforming](https://github.com/dtan4/terraforming)  - 将现有 AWS 资源导出为 Terraform 样式（tf、tfstate）. 类似于“地形改造者”.
- [terraformize](https://github.com/naorlivne/terraformize) - 通过简单的 REST API 端点应用\销毁 Terraform 模块.
- [terraformsh](https://github.com/pwillis-els/terraformsh) - Bash 中的包装器，用于更轻松的 CLI UX 和 DRY 分层配置
- [Terraform-Visual](https://github.com/hieven/terraform-visual) - 一个简单但功能强大的工具来可视化 Terraform 计划.
- [terragrunt](https://github.com/gruntwork-io/terragrunt) - Terragrunt 是 Terraform 的瘦包装器，它提供了额外的工具来保持 Terraform 配置干燥、使用多个 Terraform 模块以及管理远程状态.
- [terragrunt-atlantis-config](https://github.com/transcend-io/terragrunt-atlantis-config) - 为 Terragrunt 项目生成 Atlantis 配置.
- [Terrahaxs](https://www.terrahaxs.com) - GitOps Terraform CI/CD GitHub 应用程序：heavy_dollar_sign：
- [terrahelp](https://github.com/opencredo/terrahelp) - 命令行实用程序旨在提供补充功能，这些功能有时在使用 Terraform 时很有用.
- [terrahub](https://github.com/TerraHubCorp/terrahub)  - TerraHub 是 terraform 自动化和编排工具. 无缝集成到 console.terrahub.io，这是一个企业友好型 GUI，可显示实时 terraform 执行情况，以及历史 terraform 运行的审核和报告功能.  ：重美元符号：
- [terramate](https://github.com/mineiros-io/terramate) - 用于管理多个 Terraform 堆栈的工具，支持更改检测和代码生成
- [terrascan](https://github.com/accurics/terrascan) - Terraform 模板静态代码分析的安全性和最佳实践测试集合
- [terraspace](https://terraspace.cloud) - Terraform 框架
- [terrastate](https://github.com/rohinivsenthil/terrastate) - Visual Studio Code 扩展用于监视/部署/销毁工作区中的 Terraform 资源
- [terratag](https://github.com/env0/terratag) - Terratag 是一个 CLI 工具，使 Terraform 用户能够在整个 AWS、Azure 和 GCP 资源集上自动创建和维护标签.
- [tf-init-booster](https://github.com/hayorov/terraform-init-booster) - 一个 Pre-terraform 例程，可加速大型蓝图的 terraform 模块下载.
- [tf-profile](https://github.com/datarootsio/tf-profile/)  - Terraform 运行的探查器. 生成全局统计数据、资源级统计数据或可视化.
- [tf-summarize](https://github.com/dineshba/tf-summarize) - 用于打印 terraform 计划摘要的命令行实用程序
- [tfaction](https://github.com/suzuki-shunsuke/tfaction) - 自以为是的 Terraform 工作流程的 GitHub Actions 集合
- [tfautomv](https://github.com/padok-team/tfautomv) - 自动生成 Terraform“移动”块以进行无痛重构
- [tfcmt](https://github.com/suzuki-shunsuke/tfcmt) - CLI 通知计划结果并作为 Pull Request 评论进行应用.
- [tfedit](https://github.com/minamijoyo/tfedit) - Terraform 的重构工具.
- [tfsec](https://github.com/aquasecurity/tfsec) - Terraform 静态分析工具，支持 terraform &lt;0.12 &amp; &gt;=0.12 并直接与 HCL 解析器集成以获得更好的结果.
- [tfenv](https://github.com/tfutils/tfenv) - Terraform version manager inspired by rbenv.
- [tfgpt](https://github.com/flavius-dinu/tfgpt) - 一个 CLI 工具，将 Terraform 与 OpenAI 的 GPT-3.5 Turbo 集成，为 Terraform 命令和概念提供解释.
- [tfjson](https://github.com/palantir/tfjson)  - 用于读取 Terraform 计划文件并将其转储为 JSON 的实用程序.  ：颅骨：
- [tflint](https://github.com/terraform-linters/tflint) - Terraform linter 用于检测 `terraform plan` 无法检测到的错误
- [tfmask](https://github.com/cloudposse/tfmask) - Terraform 实用程序可屏蔽“terraform plan”和“terraform apply”的选择输出
- [tfmigrate](https://github.com/minamijoyo/tfmigrate) - 用于 GitOps 的 Terraform 状态迁移工具.
- [tfmigrator](https://github.com/tfmigrator/cli) - 转到库和 CLI 来迁移 Terraform 配置和状态
- [tfproviderlint](https://github.com/bflad/tfproviderlint) - Terraform Provider Lint 工具.
- [tfrepl](https://github.com/andreineculau/tfrepl)  - Terraform REPL，为您提供完整的 shell 体验. 基于Readline. 没有依赖性. 保存配置更改. 历史.
- [tfscaffold](https://github.com/tfutils/tfscaffold) - 用于控制多环境多组件 terraform 管理的 AWS 基础设施的框架.
- [tfschema](https://github.com/minamijoyo/tfschema) - Terraform 提供商的架构检查器.
- [tftarget](https://github.com/future-architect/tftarget) - 用于交互执行 `terraform xxx -target={...}` 的 CLI 工具.
- [tftree](https://github.com/busser/tftree) - 在终端中显示 Terraform 模块调用堆栈.
- [tftui](https://github.com/idoavrah/terraform-tui) - Terraform 状态的文本用户界面.
- [tfupdate](https://github.com/minamijoyo/tfupdate) - 更新 Terraform 配置中的版本限制.
- [tfvaultenv](https://github.com/oulman/tfvaultenv) - tfvaultenv 从 HashiCorp Vault 读取机密，并使用这些机密输出各种 Terraform 提供程序的环境变量.
- [tfvar](https://github.com/shihanng/tfvar) - tfvar 扫描您的 Terraform 配置或模块，并将变量提取为您选择的格式（tfvar、环境变量等）以进行编辑.
- [tfwrapper](https://github.com/manheim/tfwrapper) - Rubygem 提供 rake 任务以正常运行 Hashicorp Terraform.
- [tgf](https://github.com/coveo/tgf) - Terragrunt 前端，用于通过 Docker 执行 Terragrunt/Terraform.
- [tpm](https://github.com/Madh93/tpm) - Terraform 提供程序的包管理器.
- [validIaC](https://github.com/gofireflyio/validiac) - ValidIaC 结合了最好的开源工具，以帮助确保 Terraform 最佳实践、卫生和安全.
- [xterrafile](https://github.com/devopsmakers/xterrafile) 从模块注册表、git 或本地目录系统地管理外部模块，以便在 Terraform（用 Go 编写）中使用.
- [yor](https://github.com/bridgecrewio/yor) - 自动标记和跟踪基础设施作为代码框架（Terraform、Cloudformation 和 Serverless）.

## Libraries

- [pyhcl](https://github.com/virtuald/pyhcl) - Python 中的 HCL 解析器
- [python-hcl2](https://github.com/amplify-education/python-hcl2/) - Python 中的 HCL2 解析器
- [rhcl](https://github.com/winebarrel/rhcl) - Pure Ruby HCL parser
- [nu_plugin_hcl](https://github.com/Yethal/nu_plugin_hcl) - HCL 解析器插件 [Nushell](https://github.com/nushell/nushell)

## Boilerplates

- [Terraform Generator](https://github.com/sudokar/generator-tf-module) - 支持测试框架（terratest 和 kitchen-terraform）的新 terraform 模块或项目的脚手架
- [Terraform GitOps Framework](https://www.kubestack.com) - 在一个免费的开源框架中为 AKS、EKS 和 GKE Kubernetes 集群构建可靠的自动化所需的一切.

## Terraform Enterprise

- [terraform-enterprise-cli](https://github.com/skierkowski/terraform-enterprise-cli) - Terraform Enterprise 命令行界面.
- [terraform-enterprise-client](https://github.com/skierkowski/terraform-enterprise-client) - Terraform Enterprise API Ruby 客户端和命令行工具.
- [terraform-enterprise-migrator](https://github.com/silinternational/terraform-enterprise-migrator) - 用于将 Terraform Enterprise 环境从旧版本迁移到新版本 Terraform Enterprise 的脚本.
- [tfe-state-explorer](https://github.com/segmentio/tfe-state-explorer)  - 用于探索远程 terraform 企业状态的简单 shell，具有自动完成功能.  ：颅骨：
- [Scalr](https://scalr.com)  - Terraform Enterprise 的替代方案，具有 OPA 集成、组织结构、自定义挂钩、与其他 DevOps 平台的本机集成以及集中报告.  ：重美元符号：
- [env0](https://env0.com) - Terraform 云/企业的替代方案，具有 OPA 集成、自定义流程和 Terragrunt 支持：heavy_dollar_sign：
- [Brainboard](https://www.brainboard.co) - 从任何云提供商开始可视化设计、部署和管理现代云基础设施 - AWS、GCP、Azure :heavy_dollar_sign:
- [OTF](https://github.com/leg100/otf) - 开放 Terraforming Framework，这是 Terraform Enterprise 的开源替代方案，具有完整的 Terraform CLI 集成.
- [Terrakube](https://docs.terrakube.io) - Terraform Enterprise 的开源替代品，具有私有注册表、远程状态、自定义流程、计划工作区和视觉状态.
- [Spacelift](https://spacelift.io/)  - Terraform 云/企业的替代方案.  Terraform 协作基础设施交付平台：heavy_dollar_sign：
- [Terrateam](https://terrateam.io)  - Terraform GitOps 具有成本估算、静态分析、访问控制、偏差检测和自定义工作流程.  ：重美元符号：
- [Digger](https://digger.dev) - Terraform Cloud 的开源替代方案 - 运行 Terraform 计划并在 CI 中应用作业.
- [cloud-concierge](https://github.com/dragondrop-cloud/cloud-concierge) - 开源，将非托管资源编码为 Terraform、检测偏差以及云成本和安全分析，以 Pull 请求形式交付.

## Videos

- [Your Weekly Dose of Terraform](https://bit.ly/terraform-youtube) - YouTube 频道，每周进行直播，内容涵盖 Terraform 新闻、评论、采访、问答、实时编码以及一些 Terraform 黑客攻击.
- [Terraform explained in 15 mins](https://www.youtube.com/watch?v=l5k1ai_GBDE) - Terraform 在 15 分钟内解释.
- [Terraform Course](https://www.youtube.com/watch?v=SLB_c_ayRMo) - 自动化您的 AWS 云基础设施.
- [How to Build Reusable, Composable, Battle tested Terraform Modules](https://www.youtube.com/watch?v=LVgP63BkhKQ)  - Yevgeniy Brikman 谈论如何编写 Terraform 代码，使其可重用、可组合和可测试. 该演示文稿重点介绍了 Terraform 模块，但还简要清晰地解释了创建 Terraform 是为了解决什么问题，以及 Terraform 基础知识的简短演示（约 39 分钟，2017 年 10 月）.
- [Building Scalable, Repeatable Infrastructure in the Cloud with Terraform](https://www.youtube.com/watch?v=cG7pcksTAnY) - 演示 Terraform 如何通过使用托管 PostgreSQL 在 AWS 中部署 TeamCity 来实现基础设施即代码实践.
- [Creating a Google Compute Instance with Terraform](https://www.youtube.com/watch?v=fo3VX33Zx0c) - 使用 Terraform 代码创建 Google 计算实例的示例.
- [Creating a Terraform Provider for Just About Anything](https://www.hashicorp.com/resources/creating-terraform-provider-for-anything) - 通过本演练了解如何为 Terraform 提供程序做出贡献或创建您自己的提供程序.
- [Evolving Your Infrastructure with Terraform](https://www.youtube.com/watch?v=wgzgVm7Sqlk) - OpenCredo 的首席技术官在一些有趣的用例的帮助下，对在现实世界中使用 Terraform 进行了广泛的研究.
- [Going Multi-Cloud with Terraform and Nomad](https://www.youtube.com/watch?v=e42A4aBZUkQ).
- [How to Extend the Terraform Provider List](https://www.youtube.com/watch?v=2BvpqmFpchI) - 在本次演讲中，Paul 将逐步介绍 terraform 提供程序的创建过程.
- [Orchestrating Containers with Terraform and Consul](https://www.infoq.com/presentations/terraform-consul) - Mitchell Hashimoto 展示了如何使用 Terraform 来部署和扩展容器化工作负载.
- [Production ChaosMonkey with Terraform](https://www.youtube.com/watch?v=CPI6W3LK0-g) - DigitalOcean 如何使用 Terraform 运行生产集成测试.
- [Running a Terraform Environment at Scale](https://www.youtube.com/watch?v=3JVGSq7QIS0) - 使用数百个 AWS 账户大规模运行 Terraform.
- [Setup Continuous Integration for a Terraform module](https://www.youtube.com/watch?v=vuJ6bjYKUcA) - 使用 CI 和 Kitchen-Terraform 来测试、标记和发布我们的 Terraform 模块的示例，该模块创建一个 Google 计算实例.
- [State of Terraform Providerland](https://www.youtube.com/watch?v=ar1PF5iDtbg) - Terraform 提供程序如何工作以及如何编写.
- [Terraform At Scale](https://www.youtube.com/watch?v=RldRDryLiXs) - Segment 如何使用 Terraform.
- [Terraform w/ Lee Trout](https://www.youtube.com/watch?v=p2ESyuqPw1A) - 重点关注开发模式以及如何有效构建 Terraform 代码.
- [Terraforming the Composable World](https://www.youtube.com/watch?v=cHrOXPatFeg) - 将 Terraform 与本地裸机配置集成.
- [Test and verify a Google Compute Instance with Kitchen-Terraform](https://www.youtube.com/watch?v=kiH3-LEveek) - 使用 Kitchen-Terraform 测试创建 Google Compute 的 Terraform 代码的示例.
- [Untangling Terraform Through Refactoring](https://www.youtube.com/watch?v=OH6iDKaXpZs) - 如何以最小的风险谨慎地重构 Terraform 代码.
- [Complete Terraform Course - From BEGINNER to PRO! (Learn Infrastructure as Code)](https://www.youtube.com/watch?v=7xngnjfIlK4) - Complete course from beginner to pro, with no cloud provider focus, with a general approach

## Editor Plugins

- [Atom terraform-lookup](https://atom.io/packages/terraform-lookup)
- [Emacs terraform-mode](https://github.com/syohex/emacs-terraform-mode)
- [Intellij](https://plugins.jetbrains.com/plugin/7808-hashicorp-terraform--hcl-language-support)
- [Terraform-ls](https://github.com/hashicorp/terraform-ls) （Terraform 语言服务器）
- [Terraform-lsp](https://github.com/juliosueiras/terraform-lsp) （Terraform 的语言服务器协议）
- [Vim-Terraform](https://github.com/hashivim/vim-terraform)
- [Vim-Terraform-Completion](https://github.com/juliosueiras/vim-terraform-completion)
- [VS Code](https://marketplace.visualstudio.com/items?itemName=mauve.terraform)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，Shuaib Yunus 放弃了本作品的所有版权以及相关或邻接权.
