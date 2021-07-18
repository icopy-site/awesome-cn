<div class="github-widget" data-repo="shuaibiyy/awesome-terraform"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Terraform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 精选的资源列表 [HashiCorp's Terraform](https://www.terraform.io/).
> [<img src="https://rawgit.com/shuaibiyy/awesome-terraform/master/terraform.svg" align="right" width="100">](https://terraform.io)
&gt; 你 [contributions](https://github.com/shuaibiyy/awesome-terraform/blob/master/contributing.md) 受欢迎的！

 Terraform 使您能够安全且可预测地创建、更改和改进生产基础设施. 它是一种开源工具，可将 API 编码为声明性配置文件，可在团队成员之间共享、将其视为代码、进行编辑、审查和版本控制.

由...赞助 [Scalr - Terraform Automation & Collaboration Software](https://scalr.com/?utm_source=awesome-terraform)

<a href="https://www.scalr.com/?utm_source=awesome-terraform" target="_blank"><img src="https://bit.ly/2VPBJDv" alt="Scalr - Terraform Automation & Collaboration Software" width="175" height="40" /></a>



## Legend

- 不兼容 _terraform &gt;= 0.12_ :ghost:
- 被遗弃的：头骨：
- 货币化：heavy_dollar_sign：

## Official Resources

- [Hashicorp Terraform Blog](https://www.hashicorp.com/blog/category/terraform)
- [Introduction to Terraform](https://www.terraform.io/intro/)
- [Terraform Documentation](https://www.terraform.io/docs/)
- [Terraform GitHub Actions](https://github.com/hashicorp/setup-terraform)
- [Terraform learn](https://learn.hashicorp.com/terraform/)

## Community

- [Complete Terraform documentation as PDF files (Updated nightly)](https://github.com/antonbabenko/terraform-docs-as-pdf)
- [Terraform AWS Modules](https://github.com/terraform-aws-modules) + [meta-configurations repository](https://github.com/terraform-aws-modules/meta)
- [Terraform Bug Tracker](https://github.com/hashicorp/terraform/issues)
- [Terraform Community Modules](https://github.com/terraform-community-modules)
- [Terraform Gitter](https://gitter.im/hashicorp-terraform)
- [Terraform Google Group](https://groups.google.com/forum/#!forum/terraform-tool)
- [Terraform Module Registry](https://registry.terraform.io/)
- [Terraform PDF Doc](https://github.com/dohsimpson/terraform-doc-pdf) ：颅骨：
- [Terragrunt Reference Architecture](https://github.com/antonbabenko/terragrunt-reference-architecture)

## Books

- [Bootstrapping Microservices with Docker, Kubernetes, and Terraform](https://www.manning.com/books/bootstrapping-microservices-with-docker-kubernetes-and-terraform).
- [Getting Started with Terraform, 2nd ed.](https://www.amazon.com/Getting-Started-Terraform-production-infrastructure/dp/1788623533/)
- [Infrastructure as Code](http://shop.oreilly.com/product/0636920039297.do)
- [Terraform Best Practices](https://www.terraform-best-practices.com/) - [open-source ebook](https://github.com/antonbabenko/terraform-best-practices)
- [Terraform Cookbook](https://www.amazon.fr/Terraform-Cookbook-Efficiently-Infrastructure-platforms/dp/1800207557)
- [Terraform in Action](https://www.manning.com/books/terraform-in-action)
- [Terraform: Up & Running](http://www.terraformupandrunning.com/?ref=gruntwork-blog-comprehensive-terraform)
- [The Terraform Book](https://terraformbook.com/)

## Tutorials and Blog Posts

### Beginner Guides

- [A Comprehensive Guide to Terraform](https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca#.w9x897ywp) - 来自“Terraform: Up &amp; Running”作者的一系列博客文章，指导读者从开始使用 Terraform 到在现实世界中使用它.
- [Using Terraform for Cloud Deployments - Part 1](https://dev.to/koenighotze/using-terraform-for-cloud-deployments---part-1) - 供应 EC2 实例.
- [Hello, world: The Fargate/Terraform tutorial I wish I had](https://section411.com/2019/07/hello-world/) - 描述从头开始设置 ECS Fargate 集群的博客文章

### Writing Custom Providers

- [Creating custom terraform providers](https://medium.com/@jozmo/creating-custom-terraform-providers-341311823fa2) - 创建自定义提供程序的指南.
- [Writing a Terraform provider](http://blog.jfabre.net/2017/01/22/writing-terraform-provider/) - 创建自定义提供程序的指南.
- [Writing Custom Providers](https://www.terraform.io/docs/extend/writing-custom-providers.html) - 创建自定义提供程序的官方文档.

### How-To

- [How To Write OPA for Terraform](https://www.scalr.com/blog/opa-series-part-1-open-policy-agent-and-terraform/) - 如何使用 Open Policy Agent 来评估和执行 Terraform 计划的策略
- [Deploying Discourse with Terraform](https://www.hashicorp.com/blog/terraform-discourse.html) - 展示了 Terraform 如何通过一个命令在 DigitalOcean 上创建一个正在运行的 Discourse 实例.
- [Deploying Django to AWS ECS with Terraform](https://testdriven.io/blog/deploying-django-to-ecs-with-terraform/) - 了解如何使用 Terraform 启动在 ECS 上运行 Django 应用程序所需的 AWS 基础设施.
- [Easily Deploy A Seneca Microservice to ECS with Wercker and Terraform: Part I](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/), [II](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-ii/) & [III](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/) - 说明如何将 Terraform 合并到微服务部署管道中.
- [Terraform for a Highly Available VPN between AWS and Azure](https://deployeveryday.com/2020/04/13/vpn-aws-azure-terraform.html) - 在 AWS 和 Azure 之间部署高度可用的 VPN 的 Terraform 代码.
- [Terraforming 1Password](https://blog.agilebits.com/2018/01/25/terraforming-1password/) - 1Password 如何从 CloudFormation 迁移到 Terraform.
- [Tutorial: How to Use Terraform to Deploy OpenStack Workloads](http://www.stratoscale.com/blog/openstack/tutorial-how-to-use-terraform-to-deploy-openstack-workloads/) - 说明使用 OpenStack Terraform 提供程序部署 Web 服务器是多么容易.
- [Zero Downtime Updates with HashiCorp Terraform](https://www.hashicorp.com/blog/zero-downtime-updates-with-terraform) - 确保您的基础设施零停机时间.

### Multi-Environment Configuration

- [Terraform Design Patterns: the Terrafile](http://bensnape.com/2016/01/14/terraform-design-patterns-the-terrafile/) - 使用 Terrafile 在 Terraform 项目中管理 Terraform 模块及其版本.
- [Terraform, VPC, and why you want a tfstate file per env](https://charity.wtf/2016/03/30/terraform-vpc-and-why-you-want-a-tfstate-file-per-env/) - 在具有多个环境的大型项目中使用 Terraform 的一些问题以及如何避免它们.
- [Using Pipelines to Manage Environments with Infrastructure as Code](https://medium.com/@kief/https-medium-com-kief-using-pipelines-to-manage-environments-with-infrastructure-as-code-b37285a1cbf5) - 解释了构建管道以处理从一个环境转移到另一个环境的基础设施变化的不同方法.

### Azure

- [Learning HashiCorp Terraform](https://www.g10s.io/hashicorp-terraform/) - Azure 指南.
- [New Terraform Azure Automation Resources](https://bgelens.nl/terraform-automation-resources/) - Azure 自动化.
- [Terraforming Azure PaaS](https://devkimchi.com/2019/01/21/terraforming-azure-paas/) - 在 Azure 上部署 PaaS 资源.

### AWS

- [AWS Lambda the Terraform Way](https://github.com/nsriram/lambda-the-terraform-way)  - 深入了解 AWS Lambda，超越执行功能，使用 Terraform. 还包括与 S3、API Gateway、DynamoDB、Kinesis、SQS 集成的指南.

### Miscellaneous

- [Sharing data between Terraform configurations](https://jamesmckay.net/2016/09/sharing-data-between-terraform-configurations/) - Illustrates how to use remote state to share data between Terraform configurations.
- [The Segment AWS Stack](https://segment.com/blog/the-segment-aws-stack/) - 展示了由 Terraform 提供支持的基础设施的幕后，解决了 [The Million Dollar Engineering Problem](https://segment.com/blog/the-million-dollar-eng-problem/) 在 [Segment](https://segment.com/).
- [Top 3 Terraform Testing Strategies for Ultra-Reliable Infrastructure-as-Code](https://www.contino.io/insights/top-3-terraform-testing-strategies-for-ultra-reliable-infrastructure-as-code)
- [Two Weeks with Terraform](https://charity.wtf/2016/02/23/two-weeks-with-terraform/) - 一些在野外使用 Terraform 来之不易的经验，以及一些操作智慧.
- [Terraform: Beyond the Basics with AWS](https://aws.amazon.com/blogs/apn/terraform-beyond-the-basics-with-aws/) - 使用 Terraform 配置示例 AWS 架构的演示的说明.
- [Terraform cost estimation](https://github.com/antonbabenko/terraform-cost-estimation) - 基于 Terraform 计划（0.12+）或 Terraform 状态（任何版本）的匿名、安全和免费的 Terraform 成本估算.

## Community Modules

有关此处未列出的更多社区模块，请参阅 [Terraform Module Registry](https://registry.terraform.io/).

- [rancher-terraform-digitalocean](https://github.com/lunagt/rancher-terraform-digitalocean) - 数字海洋上的 Rancher 服务器.
- [segmentio/stack](https://github.com/segmentio/stack) - 使用 AWS、Docker 和 ECS 配置生产基础设施.
- [terraform-aws-alb](https://github.com/terraform-aws-modules/terraform-aws-alb) - 在 AWS 上创建了应用程序负载平衡器（经过验证的模块）.
- [terraform-aws-atlantis](https://github.com/terraform-aws-modules/terraform-aws-atlantis) - 创建用于运行的 Terraform 配置 [Atlantis](https://runatlantis.io) 在 AWS Fargate 上. 支持 Github、Gitlab 和 BitBucket.
- [terraform-aws-autoscaling](https://github.com/terraform-aws-modules/terraform-aws-autoscaling) - 创建自动缩放组和启动配置（验证模块）.
- [terraform-aws-ecr](https://github.com/cloudposse/terraform-aws-ecr) - 在 AWS ECR 上管理 Docker 容器注册表.
- [terraform-aws-efs](https://github.com/cloudposse/terraform-aws-efs) - 定义 EFS 文件系统.
- [terraform-aws-eks](https://github.com/terraform-aws-modules/terraform-aws-eks) - 在 AWS 上创建弹性 Kubernetes 服务（非常流行的模块）.
- [terraform-aws-elb](https://github.com/terraform-aws-modules/terraform-aws-elb) - 在 AWS 上创建了弹性负载均衡器（经过验证的模块）.
- [terraform-aws-jenkins-ha-agents](https://github.com/neiman-marcus/terraform-aws-jenkins-ha-agents)  - 基于 EC2 的 Jenkins 部署，带有 HA（现货）代理. 在 EFS 上运行以实现不变性. 完全可定制，具有合理的默认值.
- [terraform-aws-jenkins](https://github.com/cloudposse/terraform-aws-jenkins) - 使用 Jenkins 构建 Docker 映像，将其保存到 ECR 存储库，然后将其部署到运行 Docker 堆栈的 Elastic Beanstalk.
- [terraform-aws-key-pair](https://github.com/cloudposse/terraform-aws-key-pair) - 自动生成 SSH 密钥对（公钥/私钥）.
- [terraform-aws-lambda-auto-package](https://github.com/nozaq/terraform-aws-lambda-auto-package) - 一个用于定义 lambda 函数的 terraform 模块，该函数会自动构建和打包用于 lambda 部署的源文件.
- [terraform-aws-modules](https://github.com/terraform-aws-modules) - 社区支持的 Terraform AWS 模块集合（包括官方 AWS 模块）.
- [terraform-aws-postgresql-rds](https://github.com/azavea/terraform-aws-postgresql-rds) - 在 RDS 上创建 PostgreSQL.
- [terraform-aws-rds](https://github.com/terraform-aws-modules/terraform-aws-rds) - 在 AWS 上创建 RDS 资源（经过验证的模块）.
- [terraform-aws-secure-baseline](https://github.com/nozaq/terraform-aws-secure-baseline) - 使用基于 CIS Amazon Web Services Foundations 的安全基线配置设置您的 AWS 账户.
- [terraform-aws-security-group](https://github.com/terraform-aws-modules/terraform-aws-security-group) - 在 AWS 上创建 EC2-VPC 安全组（经过验证的模块）.
- [terraform-aws-ssh-bastion-service](https://github.com/joshuamkite/terraform-aws-ssh-bastion-service) - Terraform 计划在 AWS 上将 ssh 堡垒部署为无状态服务.
- [terraform-aws-lambda](https://github.com/terraform-aws-modules/terraform-aws-lambda) - Terraform 模块，它构建依赖项和包，并以无数组合创建 AWS Lambda 资源.
- [terraform-aws-vpc](https://github.com/terraform-aws-modules/terraform-aws-vpc) - 在 AWS 上创建 VPC 资源（经过验证且非常流行的模块）.
- [terraform-azurerm-aks](https://github.com/kjanshair/terraform-azurerm-aks) - 在 Azure 上创建 AKS 资源.
- [terraform-azurerm-iis](https://github.com/ghostinthewires/terraform-azurerm-iis-install) - 在 Azure VM 实例上安装 IIS 服务器.
- [terraform-azurerm-mysql](https://github.com/foreverXZC/terraform-azurerm-mysql) - 在 Azure 上创建 MySql 数据库.
- [terraform-azurerm-redis](https://github.com/rahulkhengare/terraform-azurerm-redis) - 在 Azure 上创建 Redis.
- [terraform-azurerm-sqlserver](https://github.com/metadevpro/terraform-azurerm-sqlserver-seed) - 在 Azure 上创建 SQL Server 数据库.
- [terraform-cloudflare-maintenance](https://github.com/adinhodovic/terraform-cloudflare-maintenance) - 使用 Cloudflare Workers 创建维护页面的模块.
- [terraform-digitalocean-droplet](https://registry.terraform.io/modules/terraform-digitalocean-modules/droplet/digitalocean) - 用于管理 DigitalOcean Droplets 和相关资源的 Terraform 模块.
- [terraform-ecs-jenkins](https://github.com/shuaibiyy/terraform-ecs-jenkins) - 使用 Terraform 在 AWS ECS 上配置 Jenkins.
- [terraform-google-project-factory](https://github.com/terraform-google-modules/terraform-google-project-factory) - 使用共享 VPC、IAM、API 等创建和配置 Google Cloud Platform 项目的意见.
- [terraform-linode-k8s](https://registry.terraform.io/modules/linode/k8s/linode/) - 在 Linode 实例上安装 Kubernetes.
- [terraform-static-website-s3-cloudfront](https://github.com/sjevs/terraform-static-website-s3-cloudfront) - 基于变量在 AWS S3 和 Cloudfront 上创建静态网站.
- [tf_aws_availability_zones_cfn](https://github.com/terraform-community-modules/tf_aws_availability_zones_cfn) - 从 Cloudformation 获取您的 AWS 区域/账户的可用区.
- [tf_aws_bastion_s3_keys](https://github.com/terraform-community-modules/tf_aws_bastion_s3_keys) - 在 AWS EC2 上创建堡垒主机.
- [tf_aws_coreos_ami](https://github.com/terraform-community-modules/tf_aws_coreos_ami) - 使用 terraform 查找 CoreOS AMI 的简便方法.
- [tf_aws_nat](https://github.com/terraform-community-modules/tf_aws_nat) - AWS 的 NAT 实例.

## Private Module Registries

- [anthology](https://github.com/erikvanbrakel/anthology) - 私有 Terraform 注册表实现作为官方注册表的替代方案.
- [citizen](https://github.com/outsideris/citizen) - 私有 Terraform 模块注册表
- [terraform-simple-registry](https://github.com/apparentlymart/terraform-simple-registry) - Terraform 注册表协议的简单实现.

## Providers

- [terraform-provider-alicloud](https://github.com/terraform-providers/terraform-provider-alicloud) - 阿里云插件.
- [terraform-provider-aws](https://github.com/terraform-providers/terraform-provider-aws) - 亚马逊网络服务插件.
- [terraform-provider-azurerm](https://github.com/terraform-providers/terraform-provider-azurerm) - Microsoft Azure 插件.
- [terraform-provider-azuredevops](https://github.com/mikaelkrief/terraform-provider-azuredevops) - Azure DevOps (VSTS) 提供程序.
- [terraform-provider-buildkite](https://github.com/buildkite/terraform-provider-buildkite) - Buildkite 插件.
- [terraform-provider-checkly](https://github.com/checkly/terraform-provider-checkly) - 管理 [Checkly](https://www.checklyhq.com) 用于 API 和 E2E 监控的资源.
- [terraform-provider-datadog](https://github.com/DataDog/terraform-provider-datadog) - Datadog 插件.
- [terraform-provider-digitalocean](https://github.com/terraform-providers/terraform-provider-digitalocean) - DigitalOcean 插件.
- [terraform-provider-docker](https://github.com/terraform-providers/terraform-provider-docker) - Docker 插件.
- [terraform-provider-dominos](https://github.com/ndmckinley/terraform-provider-dominos) - Provider for Dominos Pizza.
- [terraform-provider-github](https://github.com/terraform-providers/terraform-provider-github) - GitHub 插件.
- [terraform-provider-gitlab](https://github.com/terraform-providers/terraform-provider-gitlab) - GitLab 插件.
- [terraform-provider-google](https://github.com/terraform-providers/terraform-provider-google) - 谷歌云平台插件.
- [terraform-provider-graphql](https://github.com/sullivtr/terraform-provider-graphql) - GraphQL 查询和变更插件.
- [terraform-provider-hcloud](https://github.com/terraform-providers/terraform-provider-hcloud) - Hetzner Cloud 插件.
- [terraform-provider-healthchecksio](https://github.com/kristofferahl/terraform-provider-healthchecksio) - 管理 healthchecks.io 资源的提供者.
- [terraform-provider-helm](https://github.com/terraform-providers/terraform-provider-helm) - Helm 插件.
- [terraform-provider-heroku](https://github.com/heroku/terraform-provider-heroku) - Heroku 插件.
- [terraform-provider-ibm](https://github.com/IBM-Cloud/terraform-provider-ibm) - IBM Cloud 插件.
- [terraform-provider-k8s](https://github.com/banzaicloud/terraform-provider-k8s) - 简单的 Kubernetes Provider，适用于任何清单.
- [terraform-provider-keycloak](https://github.com/mrparkers/terraform-provider-keycloak) - 提供者来管理您的设置 [Keycloak](https://www.keycloak.org/) 身份提供者服务器.
- [terraform-provider-kubernetes](https://github.com/terraform-providers/terraform-provider-kubernetes) - Kubernetes 插件.
- [terraform-provider-linode](https://github.com/btobolaski/terraform-provider-linode) - Linode 插件.
- [terraform-provider-openstack](https://github.com/terraform-providers/terraform-provider-openstack) - OpenStack 插件.
- [terraform-provider-pingdom](https://github.com/russellcardullo/terraform-provider-pingdom) - 管理 Pingdom 资源的提供者.
- [terraform-provider-rancher2](https://github.com/rancher/terraform-provider-rancher2) - Rancher v2 的提供者.
- [terraform-provider-secrethub](https://github.com/secrethub/terraform-provider-secrethub) - SecretHub 的提供者.
- [terraform-provider-snowflake](https://github.com/chanzuckerberg/terraform-provider-snowflake) - 雪花数据仓库的提供者.
- [terraform-provider-spinnaker](https://github.com/armory-io/terraform-provider-spinnaker) - 管理 [Spinnaker](https://www.spinnaker.io/) 应用程序和管道与 Terraform.
- [terraform-provider-spotinst](https://github.com/terraform-providers/terraform-provider-spotinst) - 适用于 AWS、Azure、GCP 的 DevOps 自动化平台.
- [terraform-provider-stripe](https://github.com/franckverrot/terraform-provider-stripe) - Stripe 的提供者.
- [terraform-provider-uptimerobot](https://github.com/louy/terraform-provider-uptimerobot) - 管理正常运行时间机器人资源的提供商.
- [terraform-provider-vaulted](https://github.com/sumup-oss/terraform-provider-vaulted) - 通过 Terraform 加密的 HashiCorp Vault 机密，可以存储在 SCM 中，例如 Git.
- [terraform-provider-vsphere](https://github.com/terraform-providers/terraform-provider-vsphere) - 适用于 VMware vSphere 的插件.

## Testing

- [kitchen-terraform](https://github.com/newcontext-oss/kitchen-terraform) - 提供一组 Test Kitchen 插件，使系统能够使用 Test Kitchen 收敛 Terraform 配置并使用 InSpec 控件验证生成的 Terraform 状态.
- [rspec-terraform](https://github.com/bsnape/rspec-terraform) - Terraform 模块的 RSpec 测试.
- [terraform-compliance](https://github.com/eerkunt/terraform-compliance) - Terraform 文件的 BDD 测试.
- [terraform_validate](https://github.com/elmundio87/terraform_validate) - 协助在 Terraform 中执行用户定义的标准.
- [terratest](https://github.com/gruntwork-io/terratest) - Terratest 是一个 Go 库，可以更轻松地为您的基础架构代码编写自动化测试.
- [clarity](https://github.com/xchapter7x/clarity) - 用于单元测试的 Terraform 声明性测试框架.

## Tools

- [AirIAM](https://github.com/bridgecrewio/AirIAM) - AirIAM 是 AWS IAM 用于最小化 Terraform 执行框架权限的工具.
- [astro](https://github.com/uber/astro/)  - Astro 是一种将多个 Terraform 执行作为单个命令进行管理的工具.  ：鬼：
- [atlantis](https://github.com/runatlantis/atlantis) - 通过 GitHub 在 Terraform 上进行协作的统一工作流程.
- [blast radius](https://github.com/28mm/blast-radius)  - Terraform 依赖关系图的交互式可视化.  ：颅骨：
- [Checkov](https://github.com/bridgecrewio/checkov/) - Terraform 的 Terraform 静态分析工具&gt;=0.12
- [Cloudrail](https://github.com/indeni/cloudrail-demo) - Terraform 和 Live Cloud 基于上下文的分析工具，用于 terraform&gt;=0.12 :heavy_dollar_sign:
- [flora](https://github.com/ketchoop/flora) - Terraform 版本管理器.
- [fogg](https://github.com/chanzuckerberg/fogg) - 用于消除管理 terraform 存储库的辛劳的工具.
- [former2](https://github.com/iann0036/former2) - 从您的 AWS 账户中的现有资源生成 terraform 配置.
- [gaia](https://github.com/gaia-app/gaia) - 用于导入和运行 Terraform 模块的 Web 应用程序.
- [hcledit](https://github.com/minamijoyo/hcledit) - HCL 的命令行编辑器.
- [iam-policy-json-to-terraform](https://github.com/flosell/iam-policy-json-to-terraform) - 将 JSON 格式的 IAM 策略转换为 Terraform aws_iam_policy_document 的小工具
- [k2tf](https://github.com/sl1pm4t/k2tf) - Kubernetes YAML 到 Terraform HCL 转换器.
- [KICS](https://github.com/Checkmarx/kics) - Scans IaC projects for security vulnerabilities, compliance issues, and infrastructure misconfiguration. Currently working with Terraform projects, Kubernetes manifests, Dockerfiles, AWS CloudFormation Templates, and Ansible playbooks.
- [Infracost](https://github.com/infracost/infracost) - CLI 和拉取请求中 Terraform 的云成本估算.
- [json2hcl](https://github.com/kvz/json2hcl)  - 将 JSON 转换为 HCL，反之亦然.  ：鬼：
- [modules.tf](https://modules.tf/) - 基础设施作为代码生成器 - 来自使用创建的可视化图表 [Cloudcraft.co](https://cloudcraft.co/app) 到地形. [Source code](https://github.com/antonbabenko/modules.tf-lambda).
- [para](https://github.com/paraterraform/para)  - 缺少的第 3 方插件管理器和用于 Terraform/Terragrunt 的“瑞士军刀” - 仅 1 个工具可以促进所有工作流程.  ：颅骨：
- [pre-commit-terraform](https://github.com/antonbabenko/pre-commit-terraform) - 预先提交 git hooks 来处理 Terraform 配置（自动格式化、验证、更新文档）.
- [pretf](https://github.com/raymondbutcher/pretf)  - 使用 Python 生成 Terraform 配置的嵌入式 Terraform 包装器. 看 [pretf documentation](https://pretf.readthedocs.io/en/latest/)
- [python-terrafile](https://github.com/claranet/python-terrafile) - 系统地管理来自 Github 的外部模块以在 Terraform 中使用.
- [prettyplan](https://github.com/chrislewisdev/prettyplan)  - Prettyplan（[此处在线提供] (https://chrislewisdev.github.io/prettyplan/)）是一个小工具，可帮助您轻松查看大型 Terraform 计划.  ：鬼：
- [regula](https://github.com/fugue/regula) - 在部署之前针对潜在的 AWS、Azure 和 Google Cloud 安全配置错误和合规性违规评估 Terraform 基础设施即代码.
- [ruby-terraform](https://github.com/infrablocks/ruby_terraform) - 用于调用 terraform 命令的简单 Ruby 包装器.
- [scenery](https://github.com/dmlittle/scenery)  - 另一个 Terraform 计划输出美化器.  ：鬼：
- [scratchrelaxtv](https://github.com/YakDriver/scratchrelaxtv) - 帮助模块开发的简单 Python 工具 - 从 `main.tf` 中提取变量以生成 `variables.tf` 并从 `variables.tf` 制作模块使用存根.
- [serverless.tf - Doing serverless with Terraform](https://serverless.tf/) - serverless.tf 是一个自以为是的开源框架，用于使用 Terraform 在 AWS 上开发、构建、部署和保护无服务器应用程序和基础设施. [Read more](https://github.com/antonbabenko/serverless.tf).
- [tads-boilerplate](https://github.com/Thomvaill/tads-boilerplate) - Ansible 和 Terraform 的强大功能 + Docker Swarm 的简单性 = 基础设施即代码和 DevOps 最佳实践.
- [tau](https://github.com/avinor/tau) - Tau 是 terraform 之上的一个瘦包装器，用于管理多个部署、依赖项和机密.
- [terraboard](https://github.com/camptocamp/terraboard) - 用于检查 Terraform 状态的 Web 仪表板.
- [terraboot](https://github.com/MastodonC/terraboot) - 用于生成 terraform 配置并运行它的 DSL.
- [TerraDepot](https://github.com/derBroBro/TerraDepot)  Terraform 状态存储库，基于默认的 http 远程后端. 允许在 AWS S3 上集中管理 tfstates.
- [terrafile](https://github.com/coretech/terrafile) - 系统地管理来自 Github 的外部模块以用于 Terraform（用 Go 编写）.
- [terrafile](https://github.com/dxw/terrafile) - 系统地管理来自 Github 的外部模块以用于 Terraform（用 Ruby 编写）.
- [terraform-bundle](https://github.com/hashicorp/terraform/tree/master/tools/terraform-bundle)  - 轻松构建包含 Terraform 二进制文件和提供程序二进制文件的包. 对 CI 和气隙 Terraform Enterprise 很有用.
- [terraform-cdk](https://github.com/hashicorp/terraform-cdk) - 用于 Terraform 的 CDK（云开发套件）允许开发人员使用熟悉的编程语言来定义云基础架构并通过 HashiCorp Terraform 进行配置.
- [terraform-docs](https://github.com/segmentio/terraform-docs) - 从 terraform 模块生成文档的快速实用程序.
- [terraform-graph-beautifier](https://github.com/pcasteran/terraform-graph-beautifier) - 命令行工具允许将 terraform graph 命令几乎不可用的输出转换为更有意义和解释性的内容.
- [terraform-landscape](https://github.com/coinbase/terraform-landscape) - *（仅 0.11 及更早版本）* 改进 Terraform 的计划输出，使其更易于阅读和理解.
- [terraform-operator](https://github.com/isaaguilar/terraform-operator.git) - 用于处理 Terraform 操作的 Kubernetes CRD.
- [terraform-plan-parser](https://github.com/lifeomic/terraform-plan-parser)  - 命令行实用程序和 JavaScript API，用于从 `terraform plan` 解析标准输出并将其转换为 JSON.  ：鬼：
- [terraform-provisioner](https://github.com/shuaibiyy/terraform-provisioner) - 用于管理相同 Terraform 脚本的多个规定的工具.
- [terraform-rake-tasks](https://github.com/gina-alaska/terraform-rake-tasks) - 用于管理 terraform 计划的共享 Rake 任务.
- [terraform.py](https://github.com/ciscocloud/terraform.py) - 用于解析 Terraform 状态文件的 Ansible 动态清单脚本.
- [terraformer](https://github.com/GoogleCloudPlatform/terraformer)  - 用于从现有基础设施生成 terraform 文件的 CLI 工具. 基础设施到代码. 支持许多提供商.
- [terraforming](https://github.com/dtan4/terraforming)  - 将现有的 AWS 资源导出为 Terraform 样式（tf、tfstate）. 类似于`terraformer`.
- [Terraform-Visual](https://github.com/hieven/terraform-visual) 一个简单但功能强大的工具，用于可视化 Terraform 计划.
- [terragrunt](https://github.com/gruntwork-io/terragrunt) - Terragrunt 是 Terraform 的瘦包装器，它提供了额外的工具来保持您的 Terraform 配置干燥、使用多个 Terraform 模块以及管理远程状态.
- [terrahelp](https://github.com/opencredo/terrahelp) - 旨在提供补充功能的命令行实用程序，有时在使用 Terraform 时证明很有用.
- [terrahub](https://github.com/TerraHubCorp/terrahub)  - TerraHub 是 terraform 自动化和编排工具. 无缝集成到 console.terrahub.io，企业友好的 GUI 以显示实时 terraform 执行，以及历史 terraform 运行的审计和报告功能.  :heavy_dollar_sign:
- [terrascan](https://github.com/cesar-rodriguez/terrascan) - terraform 模板静态代码分析的安全性和最佳实践测试集
- [terraspace](https://terraspace.cloud) - Terraform 框架
- [terratag](https://github.com/env0/terratag) - Terratag 是一个 CLI 工具，它使 Terraform 的用户能够在他们的整个 AWS、Azure 和 GCP 资源集上自动创建和维护标签.
- [tf-init-booster](https://github.com/hayorov/terraform-init-booster) 一个 Pre-terraform 例程，可加速 terraform 模块下载庞大的蓝图.
- [tfsec](https://github.com/tfsec/tfsec) - Terraform 静态分析工具，支持 terraform &lt;0.12 &amp; &gt;=0.12 &amp; 直接与 HCL 解析器集成以获得更好的结果.
- [tfenv](https://github.com/tfutils/tfenv) - 受 rbenv 启发的 Terraform 版本管理器.
- [tfjson](https://github.com/palantir/tfjson)  - 读取 Terraform 计划文件并将其转储到 JSON 中的实用程序.  ：颅骨：
- [tflint](https://github.com/wata727/tflint) - Terraform linter 用于检测“terraform plan”无法检测到的错误
- [tfmask](https://github.com/cloudposse/tfmask) - Terraform 实用程序可以屏蔽来自“terraform plan”和“terraform apply”的选择输出
- [tfmigrate](https://github.com/minamijoyo/tfmigrate) - GitOps 的 Terraform 状态迁移工具.
- [tfscaffold](https://github.com/tfutils/tfscaffold) - 用于控制多环境多组件 terraform 管理的 AWS 基础设施的框架.
- [tfschema](https://github.com/minamijoyo/tfschema) - Terraform 提供程序的架构检查器.
- [tfupdate](https://github.com/minamijoyo/tfupdate) - 更新 Terraform 配置中的版本约束.
- [tfwrapper](https://github.com/manheim/tfwrapper) - Rubygem 为运行 Hashicorp Terraform 提供 rake 任务.
- [tgf](https://github.com/coveo/tgf) - Terragrunt 前端，用于通过 Docker 执行 Terragrunt/Terraform.
- [xterrafile](https://github.com/devopsmakers/xterrafile) 从模块注册表、git 或本地目录系统地管理外部模块以在 Terraform 中使用（用 Go 编写）.
- [yor](https://github.com/bridgecrewio/yor) - 自动将基础设施标记和跟踪为代码框架（Terraform、Cloudformation 和 Serverless）.

## Libraries

- [pyhcl](https://github.com/virtuald/pyhcl) - Python 中的 HCL 解析器
- [python-hcl2](https://github.com/amplify-education/python-hcl2/) - Python 中的 HCL2 解析器
- [rhcl](https://github.com/winebarrel/rhcl) - 纯 Ruby HCL 解析器

## Boilerplates

- [Terraform Generator](https://github.com/sudokar/generator-tf-module) - 支持测试框架（terratest 和 kitchen-terraform）的新 terraform 模块或项目的脚手架

## Terraform Enterprise

- [terraform-enterprise-cli](https://github.com/skierkowski/terraform-enterprise-cli) - Terraform 企业命令行界面.
- [terraform-enterprise-client](https://github.com/skierkowski/terraform-enterprise-client) - Terraform Enterprise API Ruby 客户端和命令行工具.
- [terraform-enterprise-migrator](https://github.com/silinternational/terraform-enterprise-migrator) - 用于将 Terraform Enterprise 环境从 Legacy 迁移到新版本 Terraform Enterprise 的脚本.
- [tfe-state-explorer](https://github.com/segmentio/tfe-state-explorer) - 用于探索远程 terraform 企业状态的简单外壳，具有自动完成功能.
- [Scalr](https://scalr.com) - 替代具有 OPA 集成的 Terraform Enterprise

## Videos

- [Terraform explained in 15 mins](https://www.youtube.com/watch?v=l5k1ai_GBDE) - Terraform 在 15 分钟内解释.
- [Terraform Course](https://www.youtube.com/watch?v=SLB_c_ayRMo) - 自动化您的 AWS 云基础设施.
- [How to Build Reusable, Composable, Battle tested Terraform Modules](https://www.youtube.com/watch?v=LVgP63BkhKQ)  - Yevgeniy Brikman 谈到如何编写 Terraform 代码，使其可重用、可组合和可测试. 该演示文稿侧重于 Terraform 模块，但也简要而清晰地解释了创建 Terraform 是为了解决什么问题以及 Terraform 基础知识的简短演示（~39 分钟，2017 年 10 月）.
- [Building Scalable, Repeatable Infrastructure in the Cloud with Terraform](https://www.youtube.com/watch?v=cG7pcksTAnY) - 演示 Terraform 如何通过使用托管的 PostgreSQL 在 AWS 中部署 TeamCity 来实现基础设施即代码的实践.
- [Creating a Google Compute Instance with Terraform](https://www.youtube.com/watch?v=fo3VX33Zx0c) - 使用 Terraform 代码创建 Google 计算实例的示例.
- [Creating a Terraform Provider for Just About Anything](https://www.hashicorp.com/resources/creating-terraform-provider-for-anything) - 从本演练中了解如何为 Terraform 提供程序做出贡献或创建自己的提供程序.
- [Evolving Your Infrastructure with Terraform](https://www.youtube.com/watch?v=wgzgVm7Sqlk) - OpenCredo 的 CTO 在一些有趣的用例的帮助下提供了在现实世界中使用 Terraform 的广泛研究.
- [Going Multi-Cloud with Terraform and Nomad](https://www.youtube.com/watch?v=e42A4aBZUkQ).
- [How to Extend the Terraform Provider List](https://www.youtube.com/watch?v=2BvpqmFpchI) - 在本次演讲中，Paul 将介绍创建 terraform 提供程序的过程.
- [Orchestrating Containers with Terraform and Consul](https://www.infoq.com/presentations/terraform-consul) - Mitchell Hashimoto 展示了如何使用 Terraform 部署和扩展容器化工作负载.
- [Production ChaosMonkey with Terraform](https://www.youtube.com/watch?v=CPI6W3LK0-g) - DigitalOcean 如何使用 Terraform 运行生产集成测试.
- [Running a Terraform Environment at Scale](https://www.youtube.com/watch?v=3JVGSq7QIS0) - 使用数百个 AWS 账户大规模运行 Terraform.
- [Setup Continuous Integration for a Terraform module](https://www.youtube.com/watch?v=vuJ6bjYKUcA) - 使用带有 Kitchen-Terraform 的 CI 来测试、标记和发布我们创建 Google 计算实例的 Terraform 模块的示例.
- [State of Terraform Providerland](https://www.youtube.com/watch?v=ar1PF5iDtbg) - Terraform 提供者如何工作以及如何编写一个.
- [Terraform At Scale](https://www.youtube.com/watch?v=RldRDryLiXs) - Segment 如何使用 Terraform.
- [Terraform w/ Lee Trout](https://www.youtube.com/watch?v=p2ESyuqPw1A) - 专注于开发模式以及如何有效构建 Terraform 代码.
- [Terraforming the Composable World](https://www.youtube.com/watch?v=cHrOXPatFeg) - 将 Terraform 与本地裸机配置集成.
- [Test and verify a Google Compute Instance with Kitchen-Terraform](https://www.youtube.com/watch?v=kiH3-LEveek) - 使用 Kitchen-Terraform 测试我们创建 Google Compute 的 Terraform 代码的示例.
- [Untangling Terraform Through Refactoring](https://www.youtube.com/watch?v=OH6iDKaXpZs) - 如何以最小的风险以谨慎的方式重构您的 Terraform 代码.

## Editor Plugins

- [Atom terraform-lookup](https://atom.io/packages/terraform-lookup)
- [Emacs terraform-mode](https://github.com/syohex/emacs-terraform-mode)
- [Intellij](https://plugins.jetbrains.com/plugin/7808-hashicorp-terraform--hcl-language-support)
- [Terraform-lsp](https://github.com/juliosueiras/terraform-lsp) （Terraform 的语言服务器协议）
- [Vim-Terraform](https://github.com/hashivim/vim-terraform)
- [Vim-Terraform-Completion](https://github.com/juliosueiras/vim-terraform-completion)
- [VS Code](https://marketplace.visualstudio.com/items?itemName=mauve.terraform)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，Shuaib Yunus 已放弃本作品的所有版权和相关或邻接权.
