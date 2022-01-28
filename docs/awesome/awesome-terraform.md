<div class="github-widget" data-repo="shuaibiyy/awesome-terraform"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Terraform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->

> A curated list of resources on [HashiCorp's Terraform](https://www.terraform.io/).
> [<img src="https://rawgit.com/shuaibiyy/awesome-terraform/master/terraform.svg" align="right" width="100">](https://terraform.io)
> Your [contributions](https://github.com/shuaibiyy/awesome-terraform/blob/master/contributing.md) are welcome!

Terraform enables you to safely and predictably create, change, and improve production infrastructure. It is an open source tool that codifies APIs into declarative configuration files that can be shared amongst team members, treated as code, edited, reviewed, and versioned.

Sponsored by [Scalr - Terraform Automation & Collaboration Software](https://scalr.com/?utm_source=awesome-terraform)

<a href="https://www.scalr.com/?utm_source=awesome-terraform" target="_blank"><img src="https://bit.ly/2VPBJDv" alt="Scalr - Terraform Automation & Collaboration Software" width="175" height="40" /></a>



## Legend

- Not compatible with _terraform >= 0.12_ :ghost:
- Abandoned :skull:
- 货币化：heavy_dollar_sign：

## Official Resources

- [Hashicorp Terraform Blog](https://www.hashicorp.com/blog/category/terraform)
- [Introduction to Terraform](https://www.terraform.io/intro/)
- [Terraform Documentation](https://www.terraform.io/docs/)
- [Terraform GitHub Actions](https://github.com/hashicorp/setup-terraform)
- [Terraform learn](https://learn.hashicorp.com/terraform/)

## Community

- [weekly.tf - Terraform Weekly Newsletter](https://weekly.tf) - Various news in the Terraform world (projects, announcements, discussions).
- [Complete Terraform documentation as PDF files (Updated nightly)](https://github.com/antonbabenko/terraform-docs-as-pdf)
- [Terraform AWS Modules](https://github.com/terraform-aws-modules) + [meta-configurations repository](https://github.com/terraform-aws-modules/meta)
- [Terraform Bug Tracker](https://github.com/hashicorp/terraform/issues)
- [Terraform Community Modules](https://github.com/terraform-community-modules)
- [Terraform Gitter](https://gitter.im/hashicorp-terraform)
- [Terraform Discuss](https://discuss.hashicorp.com/c/terraform-core/27)
- [Terraform Provider/Module Registry](https://registry.terraform.io/)
- [Terraform PDF Doc](https://github.com/dohsimpson/terraform-doc-pdf) :skull:
- [Terragrunt Reference Architecture](https://github.com/antonbabenko/terragrunt-reference-architecture)

## Books

- [Big Little Book On Terraform](https://www.amazon.com/Big-Little-Book-Terraform-Omos-ebook/dp/B07PWYPNX8/)
- [Bootstrapping Microservices with Docker, Kubernetes, and Terraform](https://www.manning.com/books/bootstrapping-microservices-with-docker-kubernetes-and-terraform).
- [Deep-Dive Terraform on Azure](https://link.springer.com/book/10.1007/978-1-4842-7328-9)
- [Getting Started with Terraform, 2nd ed.](https://www.amazon.com/Getting-Started-Terraform-production-infrastructure/dp/1788623533/)
- [HashiCorp Infrastructure Automation Certification Guide](https://www.amazon.com/HashiCorp-Infrastructure-Automation-Certification-Guide-ebook/dp/B092KM7LXC/)
- [Infrastructure as Code](http://shop.oreilly.com/product/0636920039297.do)
- [Patterns and Practices for Infrastructure as Code: With examples in Python and Terraform](https://www.manning.com/books/patterns-and-practices-for-infrastructure-as-code)
- [Terraform Best Practices](https://www.terraform-best-practices.com/) - [open-source ebook](https://github.com/antonbabenko/terraform-best-practices)
- [Terraform Cookbook](https://www.amazon.fr/Terraform-Cookbook-Efficiently-Infrastructure-platforms/dp/1800207557)
- [Terraform in Action](https://www.manning.com/books/terraform-in-action)
- [Terraform: Up & Running, 2nd ed.](http://www.terraformupandrunning.com/?ref=gruntwork-blog-comprehensive-terraform)
- [The Terraform Book](https://terraformbook.com/)

## Tutorials and Blog Posts

### Beginner Guides

- [A Comprehensive Guide to Terraform](https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca#.w9x897ywp) - Series of blog posts from the author of "Terraform: Up & Running" that guide the reader from beginning with Terraform to using it in the real world.
- [Using Terraform for Cloud Deployments - Part 1](https://dev.to/koenighotze/using-terraform-for-cloud-deployments---part-1) - Provisioning an EC2 instance.
- [Hello, world: The Fargate/Terraform tutorial I wish I had](https://section411.com/2019/07/hello-world/) - Blog post describing setting up an ECS Fargate cluster from scratch

### Writing Custom Providers

- [Creating custom terraform providers](https://medium.com/@jozmo/creating-custom-terraform-providers-341311823fa2) - Guide for creating custom providers.
- [Writing a Terraform provider](http://blog.jfabre.net/2017/01/22/writing-terraform-provider/) - Guide for creating custom providers.
- [Writing Custom Providers](https://www.terraform.io/docs/extend/writing-custom-providers.html) - 用于创建自定义提供程序的官方文档.

### How-To

- [How To Write OPA for Terraform](https://www.scalr.com/blog/opa-series-part-1-open-policy-agent-and-terraform/) - 如何使用 Open Policy Agent 来评估和执行 Terraform 计划的策略
- [Deploying Discourse with Terraform](https://www.hashicorp.com/blog/terraform-discourse.html) - 展示 Terraform 如何通过一个命令在 DigitalOcean 上创建一个正在运行的 Discourse 实例.
- [Deploying Django to AWS ECS with Terraform](https://testdriven.io/blog/deploying-django-to-ecs-with-terraform/) - 了解如何使用 Terraform 启动所需的 AWS 基础设施，以便在 ECS 上运行 Django 应用程序.
- [Easily Deploy A Seneca Microservice to ECS with Wercker and Terraform: Part I](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/), [II](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-ii/) & [III](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/) - Illustrates how Terraform can be incorporated into a microservice deployment pipeline.
- [Terraform for a Highly Available VPN between AWS and Azure](https://deployeveryday.com/2020/04/13/vpn-aws-azure-terraform.html) - Terraform code to deploy a highly available VPN between AWS and Azure.
- [Terraforming 1Password](https://blog.agilebits.com/2018/01/25/terraforming-1password/) - How 1Password migrated from CloudFormation to Terraform.
- [Tutorial: How to Use Terraform to Deploy OpenStack Workloads](http://www.stratoscale.com/blog/openstack/tutorial-how-to-use-terraform-to-deploy-openstack-workloads/) - 说明使用 OpenStack Terraform 提供程序部署 Web 服务器是多么容易.
- [Zero Downtime Updates with HashiCorp Terraform](https://www.hashicorp.com/blog/zero-downtime-updates-with-terraform) - Ensuring zero downtime of your infrastructure.

### Multi-Environment Configuration

- [Terraform Design Patterns: the Terrafile](http://bensnape.com/2016/01/14/terraform-design-patterns-the-terrafile/) - 使用 Terrafile 在 Terraform 项目中管理 Terraform 模块及其版本.
- [Terraform, VPC, and why you want a tfstate file per env](https://charity.wtf/2016/03/30/terraform-vpc-and-why-you-want-a-tfstate-file-per-env/) - Some gotchas surrounding using Terraform in large projects with multiple environments and how to avoid them.
- [Using Pipelines to Manage Environments with Infrastructure as Code](https://medium.com/@kief/https-medium-com-kief-using-pipelines-to-manage-environments-with-infrastructure-as-code-b37285a1cbf5) - Explains different approaches for building a pipeline to handle infrastructure changes moving from one environment to the next.

### Azure

- [Learning HashiCorp Terraform](https://www.g10s.io/hashicorp-terraform/) - Azure 指南.
- [New Terraform Azure Automation Resources](https://bgelens.nl/terraform-automation-resources/) - Azure Automation.
- [Terraforming Azure PaaS](https://devkimchi.com/2019/01/21/terraforming-azure-paas/) - Deploy PaaS Resources on Azure.

### AWS

- [AWS Lambda the Terraform Way](https://github.com/nsriram/lambda-the-terraform-way)  - 使用 Terraform 深入了解 AWS Lambda，而不是执行函数. 还包括与 S3、API Gateway、DynamoDB、Kinesis、SQS 集成的指南.
- [Managing AWS Lambda Functions with Terraform](https://spacelift.io/blog/terraform-aws-lambda) - What is AWS Lambda used for and how to use Terraform to manage AWS Lambda functions?

### Miscellaneous

- [Sharing data between Terraform configurations](https://jamesmckay.net/2016/09/sharing-data-between-terraform-configurations/) - Illustrates how to use remote state to share data between Terraform configurations.
- [The Segment AWS Stack](https://segment.com/blog/the-segment-aws-stack/) - Shows the behind the scenes of the infrastructure powered by Terraform th在 solved [The Million Dollar Engineering Problem](https://segment.com/blog/the-million-dollar-eng-problem/) 在 [Segment](https://segment.com/).
- [Top 3 Terraform Testing Strategies for Ultra-Reliable Infrastructure-as-Code](https://www.contino.io/insights/top-3-terraform-testing-strategies-for-ultra-reliable-infrastructure-as-code)
- [Two Weeks with Terraform](https://charity.wtf/2016/02/23/two-weeks-with-terraform/) - Some hard-earned experience from using Terraform in the wild, and some operational wisdom.
- [Terraform: Beyond the Basics with AWS](https://aws.amazon.com/blogs/apn/terraform-beyond-the-basics-with-aws/) - Explanation of a demo using Terraform to provision a sample AWS architecture.
- [Terraform cost estimation](https://github.com/antonbabenko/terraform-cost-estimation) - Anonymized, secure, and free Terraform cost estimation based on Terraform plan (0.12+) or Terraform state (any version).
- [How to Debug Terraform Projects: Tutorial](https://spacelift.io/blog/terraform-debug)

## Community Modules

有关此处未列出的更多社区模块，请参阅 [Terraform Module Registry](https://registry.terraform.io/).

- [rancher-terraform-digitalocean](https://github.com/lunagt/rancher-terraform-digitalocean) - Rancher server on digitalocean.
- [segmentio/stack](https://github.com/segmentio/stack) - Configures production infrastructure with AWS, Docker, and ECS.
- [terraform-aws-alb](https://github.com/terraform-aws-modules/terraform-aws-alb) - 在 AWS（已验证模块）上创建应用程序负载均衡器.
- [terraform-aws-appconfig](https://github.com/clowdhaus/terraform-aws-appconfig) - Creates AWS AppConfig resources on AWS.
- [terraform-aws-atlantis](https://github.com/terraform-aws-modules/terraform-aws-atlantis) - Creates Terraform configurations for running [Atlantis](https://runatlantis.io) 在 AWS Fargate 上. 支持 Github、Gitlab 和 BitBucket.
- [terraform-aws-autoscaling](https://github.com/terraform-aws-modules/terraform-aws-autoscaling) - Creates Auto-Scaling Groups and Launch Configurations (verified module).
- [terraform-aws-customer-gateway](https://github.com/terraform-aws-modules/terraform-aws-customer-gateway) - Creates Customer Gateway on AWS.
- [terraform-aws-datadog-forwarders](https://github.com/clowdhaus/terraform-aws-datadog-forwarders) - 在 AWS 上创建资源以将日志/指标转发到 Datadog。
- [terraform-aws-dms](https://github.com/clowdhaus/terraform-aws-dms) - Creates AWS DMS (Database Migration Service) resources on AWS.
- [terraform-aws-dynamodb-table](https://github.com/terraform-aws-modules/terraform-aws-dynamodb-table) - Creates DynamoDB table on AWS.
- [terraform-aws-ec2-instance](https://github.com/terraform-aws-modules/terraform-aws-ec2-instance) - 在 AWS 上创建 EC2 实例.
- [terraform-aws-ecr](https://github.com/cloudposse/terraform-aws-ecr) - 管理 AWS ECR 上的 Docker 容器注册表.
- [terraform-aws-ecs](https://github.com/terraform-aws-modules/terraform-aws-ecs) - Creates AWS ECS resources on AWS.
- [terraform-aws-efs](https://github.com/cloudposse/terraform-aws-efs) - Defines an EFS Filesystem.
- [terraform-aws-eks](https://github.com/terraform-aws-modules/terraform-aws-eks) - Creates Elastic Kubernetes Service on AWS (very popular module).
- [terraform-aws-elb](https://github.com/terraform-aws-modules/terraform-aws-elb) - 在 AWS（已验证模块）上创建弹性负载均衡器.
- [terraform-aws-eventbridge](https://github.com/terraform-aws-modules/terraform-aws-eventbridge) - 在 AWS 上创建 EventBridge 资源.
- [terraform-aws-jenkins-ha-agents](https://github.com/neiman-marcus/terraform-aws-jenkins-ha-agents)  - 基于 EC2 的 Jenkins 部署与 HA（现场）代理. 在 EFS 上运行以实现不变性. 完全可定制，具有合理的默认值.
- [terraform-aws-jenkins](https://github.com/cloudposse/terraform-aws-jenkins) - Build a Docker image with Jenkins, saves it to an ECR repo, and deploys it to Elastic Beanstalk running a Docker stack.
- [terraform-aws-key-pair](https://github.com/cloudposse/terraform-aws-key-pair) - Automatically Generate SSH Key Pairs (Public/Private Keys).
- [terraform-aws-lambda](https://github.com/terraform-aws-modules/terraform-aws-lambda) - Terraform 模块，它构建依赖项和包，并以无数种组合创建 AWS Lambda 资源.
- [terraform-aws-lambda-auto-package](https://github.com/nozaq/terraform-aws-lambda-auto-package) - A terraform module to define a lambda function which source files are automatically built and packaged for lambda deployment.
- [terraform-aws-managed-service-prometheus](https://github.com/clowdhaus/terraform-aws-managed-service-prometheus) - Creates AWS Managed Service for Prometheus (AMP) resources on AWS.
- [terraform-aws-modules](https://github.com/terraform-aws-modules) - Collection of Terraform AWS modules supported by the community (includes official AWS modules).
- [terraform-aws-msk-kafka-cluster](https://github.com/clowdhaus/terraform-aws-msk-kafka-cluster) - 在 AWS 上创建 AWS MSK（Kafka 托管流）资源.
- [terraform-aws-notify-slack](https://github.com/terraform-aws-modules/terraform-aws-notify-slack) - Creates SNS topic and Lambda function which sends notifications to Slack.
- [terraform-aws-postgresql-rds](https://github.com/azavea/terraform-aws-postgresql-rds) - Creates PostgreSQL on RDS.
- [terraform-aws-rds](https://github.com/terraform-aws-modules/terraform-aws-rds) - 在 AWS（已验证模块）上创建 RDS 资源.
- [terraform-aws-rds-aurora](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora) - Creates RDS Aurora cluster resources on AWS (verified module).
- [terraform-aws-rds-proxy](https://github.com/clowdhaus/terraform-aws-rds-proxy) - Creates AWS RDS Proxy resources on AWS.
- [terraform-aws-redshift](https://github.com/terraform-aws-modules/terraform-aws-redshift) - 在 AWS 上创建 Redshift 资源.
- [terraform-aws-route53](https://github.com/terraform-aws-modules/terraform-aws-route53) - Creates Route53 resources on AWS.
- [terraform-aws-secure-baseline](https://github.com/nozaq/terraform-aws-secure-baseline) - 使用基于 CIS Amazon Web Services Foundations 的安全基线配置设置您的 AWS 账户.
- [terraform-aws-security-group](https://github.com/terraform-aws-modules/terraform-aws-security-group) - 在 AWS（已验证模块）上创建 EC2-VPC 安全组.
- [terraform-aws-ssh-bastion-service](https://github.com/joshuamkite/terraform-aws-ssh-bastion-service) - Terraform 计划将 ssh 堡垒部署为 AWS 上的无状态服务.
- [terraform-aws-s3-bucket](https://github.com/terraform-aws-modules/terraform-aws-s3-bucket) - 在 AWS 上创建 S3 存储桶资源.
- [terraform-aws-transit-gateway](https://github.com/terraform-aws-modules/terraform-aws-transit-gateway) - Creates Transit Gateway resources on AWS.
- [terraform-aws-vpc](https://github.com/terraform-aws-modules/terraform-aws-vpc) - 在 AWS 上创建 VPC 资源（经过验证且非常受欢迎的模块）.
- [terraform-aws-vpn-gateway](https://github.com/terraform-aws-modules/terraform-aws-vpn-gateway) - Creates VPN gateway resources on AWS.
- [terraform-azurerm-aks](https://github.com/kjanshair/terraform-azurerm-aks) - 在 Azure 上创建 AKS 资源.
- [terraform-azurerm-iis](https://github.com/ghostinthewires/terraform-azurerm-iis-install) - Install IIS Server on Azure VM instance.
- [terraform-azurerm-mysql](https://github.com/foreverXZC/terraform-azurerm-mysql) - 在 Azure 上创建 MySql 数据库.
- [terraform-azurerm-redis](https://github.com/rahulkhengare/terraform-azurerm-redis) - Create Redis on Azure.
- [terraform-azurerm-sqlserver](https://github.com/metadevpro/terraform-azurerm-sqlserver-seed) - Create SQl Server Database on Azure.
- [terraform-cloudflare-maintenance](https://github.com/adinhodovic/terraform-cloudflare-maintenance) - Module to create a Maintenance Page using Cloudflare Workers.
- [terraform-digitalocean-droplet](https://registry.terraform.io/modules/terraform-digitalocean-modules/droplet/digitalocean) - Terraform module for managing DigitalOcean Droplets and related resources.
- [terraform-ecs-jenkins](https://github.com/shuaibiyy/terraform-ecs-jenkins) - Provisions Jenkins on AWS ECS using Terraform.
- [terraform-google-project-factory](https://github.com/terraform-google-modules/terraform-google-project-factory) - Opinionated Google Cloud Platform project creation and configuration with Shared VPC, IAM, APIs, etc.
- [terraform-linode-k8s](https://registry.terraform.io/modules/linode/k8s/linode/) - Installs Kubernetes on Linode Instances.
- [terraform-static-website-s3-cloudfront](https://github.com/sjevs/terraform-static-website-s3-cloudfront) - Creates static websites on AWS S3 & Cloudfront based on variables.
- [tf_aws_bastion_s3_keys](https://github.com/terraform-community-modules/tf_aws_bastion_s3_keys) - Creates bastion hosts on AWS EC2.

## Private Module Registries

- [anthology](https://github.com/erikvanbrakel/anthology) - Private Terraform registry implementation as an alternative to the official registry.
- [citizen](https://github.com/outsideris/citizen) - Private Terraform Module Registry
- [modulehub](https://www.modulehub.io) - 私有 Terraform 模块注册表和状态后端.
- [terraform-simple-registry](https://github.com/apparentlymart/terraform-simple-registry) - Terraform 注册协议的简单实现。
- [terraform-registry](https://github.com/philips-labs/terraform-registry) - 提供由 GitHub 版本支持的 terraform 提供程序注册表。

## Providers

- [terraform-provider-alicloud](https://github.com/terraform-providers/terraform-provider-alicloud) - Plugin for Alibaba Cloud.
- [terraform-provider-aws](https://github.com/terraform-providers/terraform-provider-aws) - Plugin for Amazon Web Services.
- [terraform-provider-azurerm](https://github.com/terraform-providers/terraform-provider-azurerm) - Microsoft Azure 插件.
- [terraform-provider-azuredevops](https://github.com/mikaelkrief/terraform-provider-azuredevops) - Provider for Azure DevOps (VSTS).
- [terraform-provider-buildkite](https://github.com/buildkite/terraform-provider-buildkite) - Plugin for Buildkite.
- [terraform-provider-checkly](https://github.com/checkly/terraform-provider-checkly) - Manage [Checkly](https://www.checklyhq.com) API &amp; E2E 监控资源.
- [terraform-provider-datadog](https://github.com/DataDog/terraform-provider-datadog) - Datadog 插件.
- [terraform-provider-digitalocean](https://github.com/terraform-providers/terraform-provider-digitalocean) - Plugin for DigitalOcean.
- [terraform-provider-docker](https://github.com/terraform-providers/terraform-provider-docker) - Docker 插件.
- [terraform-provider-dominos](https://github.com/ndmckinley/terraform-provider-dominos) - Provider for Dominos Pizza.
- [terraform-provider-github](https://github.com/terraform-providers/terraform-provider-github) - Plugin for GitHub.
- [terraform-provider-gitlab](https://github.com/terraform-providers/terraform-provider-gitlab) - Plugin for GitLab.
- [terraform-provider-google](https://github.com/terraform-providers/terraform-provider-google) - Plugin for Google Cloud Platform.
- [terraform-provider-graphql](https://github.com/sullivtr/terraform-provider-graphql) - Plugin for GraphQL queries and mutations.
- [terraform-provider-hcloud](https://github.com/terraform-providers/terraform-provider-hcloud) - Plugin for Hetzner Cloud.
- [terraform-provider-healthchecksio](https://github.com/kristofferahl/terraform-provider-healthchecksio) - Provider to manage healthchecks.io resources.
- [terraform-provider-helm](https://github.com/terraform-providers/terraform-provider-helm) - Plugin for Helm.
- [terraform-provider-heroku](https://github.com/heroku/terraform-provider-heroku) - Heroku 插件.
- [terraform-provider-ibm](https://github.com/IBM-Cloud/terraform-provider-ibm) - IBM Cloud 插件.
- [terraform-provider-k8s](https://github.com/banzaicloud/terraform-provider-k8s) - Simple Kubernetes Provider, works with any manifest.
- [terraform-provider-keycloak](https://github.com/mrparkers/terraform-provider-keycloak) - Provider to manage the settings of your [Keycloak](https://www.keycloak.org/) identity provider server.
- [terraform-provider-kubernetes](https://github.com/terraform-providers/terraform-provider-kubernetes) - Plugin for Kubernetes.
- [terraform-provider-linode](https://github.com/btobolaski/terraform-provider-linode) - Plugin for Linode.
- [terraform-provider-openstack](https://github.com/terraform-providers/terraform-provider-openstack) - Plugin for OpenStack.
- [terraform-provider-pingdom](https://github.com/russellcardullo/terraform-provider-pingdom) - Provider to manage Pingdom resources.
- [terraform-provider-rancher2](https://github.com/rancher/terraform-provider-rancher2) - Provider for Rancher v2.
- [terraform-provider-secrethub](https://github.com/secrethub/terraform-provider-secrethub) - SecretHub 的提供者.
- [terraform-provider-snowflake](https://github.com/chanzuckerberg/terraform-provider-snowflake) - Provider for Snowflake data warehouse.
- [terraform-provider-spinnaker](https://github.com/armory-io/terraform-provider-spinnaker) - Manage [Spinnaker](https://www.spinnaker.io/) applications and pipelines with Terraform.
- [terraform-provider-spotinst](https://github.com/terraform-providers/terraform-provider-spotinst) - 适用于 AWS、Azure、GCP 的 Devops 自动化平台.
- [terraform-provider-stripe](https://github.com/franckverrot/terraform-provider-stripe) - Provider for Stripe.
- [terraform-provider-ucloud](https://github.com/ucloud/terraform-provider-ucloud) - Provider to manage UCloud resources.
- [terraform-provider-uptimerobot](https://github.com/louy/terraform-provider-uptimerobot) - Provider to manage uptimerobot resources.
- [terraform-provider-vaulted](https://github.com/sumup-oss/terraform-provider-vaulted) - Encrypted HashiCorp Vault secrets via Terraform that can be stored in SCM such as Git.
- [terraform-provider-vsphere](https://github.com/terraform-providers/terraform-provider-vsphere) - Plugin for VMware vSphere.

## Testing

- [kitchen-terraform](https://github.com/newcontext-oss/kitchen-terraform) - Provides a set of Test Kitchen plugins which enable a system to use Test Kitchen to converge a Terraform configuration and verify the resulting Terraform state with InSpec controls.
- [rspec-terraform](https://github.com/bsnape/rspec-terraform) - RSpec tests for your Terraform modules.
- [terraform-compliance](https://github.com/eerkunt/terraform-compliance) - BDD Testing for Terraform Files.
- [terraform_validate](https://github.com/elmundio87/terraform_validate) - 协助在 Terraform 中执行用户定义的标准.
- [terratest](https://github.com/gruntwork-io/terratest) - Terratest is a Go library that makes it easier to write automated tests for your infrastructure code.
- [clarity](https://github.com/xchapter7x/clarity) - A declarative test framework for Terraform for unit testing.

## Tools

- [AirIAM](https://github.com/bridgecrewio/AirIAM) - AirIAM 是 AWS IAM 为 Terraform 执行框架提供最低权限的工具.
- [astro](https://github.com/uber/astro/)  - Astro 是一种将多个 Terraform 执行作为单个命令进行管理的工具.  ：鬼：
- [atlantis](https://github.com/runatlantis/atlantis) - 通过 GitHub 在 Terraform 上进行协作的统一工作流程.
- [aztfy](https://github.com/Azure/aztfy) - A tool to bring existing Azure resources under Terraform's management.
- [blast radius](https://github.com/28mm/blast-radius) - Interactive visualizations of Terraform dependency graphs. :skull:
- [Checkov](https://github.com/bridgecrewio/checkov/) - Terraform static analysis tool for terraform>=0.12
- [Cloudrail](https://github.com/indeni/cloudrail-demo) - Terraform and Live Cloud context-based analysis tool for terraform>=0.12 :heavy_dollar_sign:
- [driftctl](https://github.com/snyk/driftctl) - Detect, track and alert on infrastructure drift
- [flora](https://github.com/ketchoop/flora) - Terraform version manager.
- [fogg](https://github.com/chanzuckerberg/fogg) - A tool for eliminating toil in managing terraform repositories.
- [former2](https://github.com/iann0036/former2) - 从您的 AWS 账户中的现有资源生成 terraform 配置.
- [gaia](https://github.com/gaia-app/gaia) - 用于导入和运行 Terraform 模块的 Web 应用程序.
- [hcldump](https://github.com/magodo/hcldump) - Dump the HCL (v2) abstract syntax tree.
- [hcledit](https://github.com/minamijoyo/hcledit) - A command line editor for HCL.
- [hclgrep](https://github.com/magodo/hclgrep) - Syntax based grep for HCL(v2).
- [iam-policy-json-to-terraform](https://github.com/flosell/iam-policy-json-to-terraform) - Small tool to convert an IAM Policy in JSON format into a Terraform aws_iam_policy_document
- [k2tf](https://github.com/sl1pm4t/k2tf) - Kubernetes YAML to Terraform HCL converter.
- [KICS](https://github.com/Checkmarx/kics) - Scans IaC projects for security vulnerabilities, compliance issues, and infrastructure misconfiguration. Currently working with Terraform projects, Kubernetes manifests, Dockerfiles, AWS CloudFormation Templates, and Ansible playbooks.
- [Infracost](https://github.com/infracost/infracost) - Cloud cost estimates for Terraform in your CLI and pull requests.
- [inframap](https://github.com/cycloidio/inframap) - 阅读您的 tfstate 或 HCL 以生成特定于每个提供商的图表，仅显示最重要/相关的资源.
- [json2hcl](https://github.com/kvz/json2hcl) - Convert JSON to HCL and vice versa. :ghost:
- [modules.tf-lambda](https://github.com/antonbabenko/modules.tf-lambda) - Infrastructure as code generator from visual diagrams created with [Cloudcraft.co](https://cloudcraft.co/app) to Terraform.
- [para](https://github.com/paraterraform/para) - The missing 3rd-party plugin manager and a "swiss army knife" for Terraform/Terragrunt - just 1 tool to facilitate all workflows. :skull:
- [pre-commit-terraform](https://github.com/antonbabenko/pre-commit-terraform) - pre-commit git hooks to take care of Terraform configurations (auto-format, validate, update docs).
- [pretf](https://github.com/raymondbutcher/pretf) - drop-in Terraform wrapper that generates Terraform configuration with Python. See [pretf documentation](https://pretf.readthedocs.io/en/latest/)
- [python-terrafile](https://github.com/claranet/python-terrafile) - Systematically manage external modules from Github for use in Terraform.
- [prettyplan](https://github.com/chrislewisdev/prettyplan) - Prettyplan ([available online here](https://chrislewisdev.github.io/prettyplan/) ) 是一个小工具，可帮助您轻松查看大型 Terraform 计划.  ：鬼：
- [regula](https://github.com/fugue/regula) - Evaluates Terraform infrastructure-as-code for potential AWS, Azure, and Google Cloud security misconfigurations and compliance violations prior to deployment.
- [rover](https://github.com/im2nguyen/rover) - Interactive Terraform state and configuration explorer.
- [ruby-terraform](https://github.com/infrablocks/ruby_terraform) - Simple Ruby wrapper for invoking terraform commands.
- [scenery](https://github.com/dmlittle/scenery)  - 另一个 Terraform 计划输出美化器.  ：鬼：
- [scratchrelaxtv](https://github.com/YakDriver/scratchrelaxtv) - Simple Python tool to help with module development - extract vars from `main.tf` to generate `variables.tf` and make module usage stub from `variables.tf`.
- [serverless.tf - Doing serverless with Terraform](https://serverless.tf/) - serverless.tf is an opinionated open-source framework for developing, building, deploying, and securing serverless applications and infrastructures on AWS using Terraform. [Read more](https://github.com/antonbabenko/serverless.tf).
- [Shisho](https://github.com/flatt-security/shisho) - Lightweight static analyzer for Terraform.
- [tads-boilerplate](https://github.com/Thomvaill/tads-boilerplate) - The power of Ansible and Terraform + the simplicity of Docker Swarm = Infrastructure as Code and DevOps best practices.
- [tau](https://github.com/avinor/tau) - Tau is a thin wrapper on top of terraform to manage multiple deployments, dependencies and secrets.
- [terraboard](https://github.com/camptocamp/terraboard) - Web dashboard to inspect Terraform States.
- [terraboot](https://github.com/MastodonC/terraboot) - DSL to generate a terraform configuration and run it.
- [terracognita](https://github.com/cycloidio/terracognita) - Reads from existing Cloud Providers (reverse Terraform) and generates your infrastructure as code on Terraform configuration.
- [terracost](https://github.com/cycloidio/terracost) - Cloud cost estimation for Terraform in your CLI.
- [TerraDepot](https://github.com/derBroBro/TerraDepot) Terraform state repository, based on the default http remote backend. Allows the central administration of tfstates on AWS S3.
- [terradozer](https://github.com/jckuester/terradozer) - Terraform destroy without configuration files.
- [terrafile](https://github.com/coretech/terrafile) - Systematically manage external modules from Github for use in Terraform (written in Go).
- [terrafile](https://github.com/dxw/terrafile) - Systematically manage external modules from Github for use in Terraform (written in Ruby).
- [terraform-bundle](https://github.com/hashicorp/terraform/tree/master/tools/terraform-bundle) - Easily builds bundles containing a Terraform binary as well as provider binaries. Useful for CI and air-gapped Terraform Enterprise.
- [terraform-cdk](https://github.com/hashicorp/terraform-cdk) - CDK (Cloud Development Kit) for Terraform allows developers to use familiar programming languages to define cloud infrastructure and provision it through HashiCorp Terraform.
- [terraform-credentials-vault](https://github.com/oulman/terraform-credentials-vault) - A Terraform "credentials helper" plugin that allows providing credentials for Terraform-native services (private module registries, Terraform Cloud, etc) via environment variables.
- [terraform-docs](https://github.com/segmentio/terraform-docs) - 从 terraform 模块生成文档的快速实用程序.
- [terraform-graph-beautifier](https://github.com/pcasteran/terraform-graph-beautifier) - Command line tool allowing to convert the barely usable output of the terraform graph command to something more meaningful and explanatory.
- [terraform-landscape](https://github.com/coinbase/terraform-landscape) - *(only 0.11 and earlier)* Improve Terraform's plan output to be easier to read and understand.
- [terraform-operator](https://github.com/isaaguilar/terraform-operator.git) - A Kubernetes CRD to handle Terraform operations.
- [terraform-plan-parser](https://github.com/lifeomic/terraform-plan-parser)  - 命令行实用程序和 JavaScript API，用于从 `terraform plan` 解析标准输出并将其转换为 JSON.  ：鬼：
- [terraform-provisioner](https://github.com/shuaibiyy/terraform-provisioner) - 用于管理相同 Terraform 脚本的多个规定的工具.
- [terraform-rake-tasks](https://github.com/gina-alaska/terraform-rake-tasks) - Shared Rake tasks for managing terraform plans.

- [terraform.py](https://github.com/ciscocloud/terraform.py) - Ansible dynamic inventory script for parsing Terraform state files.
- [terraformer](https://github.com/GoogleCloudPlatform/terraformer) - CLI tool to generate terraform files from existing infrastructure. Infrastructure to Code. Supported many providers.
- [terraforming](https://github.com/dtan4/terraforming)  - 将现有 AWS 资源导出为 Terraform 样式（tf、tfstate）. 类似于 `terraformer`.
- [terraformize](https://github.com/naorlivne/terraformize) - 通过简单的 REST API 端点应用\销毁 Terraform 模块.
- [Terraform-Visual](https://github.com/hieven/terraform-visual) A simple but powerful tool to visualize Terraform plan.
- [terragrunt](https://github.com/gruntwork-io/terragrunt) - Terragrunt 是 Terraform 的一个瘦包装器，它提供了额外的工具来保持你的 Terraform 配置干燥，使用多个 Terraform 模块，以及管理远程状态.
- [terrahelp](https://github.com/opencredo/terrahelp) - Command line utility aimed at providing supplementary functionality which can sometimes prove useful when working with Terraform.
- [terrahub](https://github.com/TerraHubCorp/terrahub) - TerraHub is terraform automation and orchestration tool. Seamlessly integrated into console.terrahub.io, enterprise friendly GUI to show realtime terraform executions, as well as auditing and reporting capabilities for historical terraform runs. :heavy_dollar_sign:
- [terrascan](https://github.com/cesar-rodriguez/terrascan) - Collection of security and best practice test for static code analysis of terraform templates
- [terraspace](https://terraspace.cloud) - The Terraform Framework
- [terrastate](https://github.com/rohinivsenthil/terrastate) - Visual Studio Code extension to monitor/deploy/destroy Terraform resources in your workspace
- [terratag](https://github.com/env0/terratag) - Terratag is a CLI tool that enables users of Terraform to automatically create and maintain tags across their entire set of AWS, Azure, and GCP resources.
- [tf-init-booster](https://github.com/hayorov/terraform-init-booster) 一个 Pre-terraform 例程，可加速 terraform 模块下载庞大的蓝图.
- [tfcmt](https://github.com/suzuki-shunsuke/tfcmt) - CLI to notify the result of plan and apply as Pull Request comment.
- [tfsec](https://github.com/tfsec/tfsec) - Terraform static analysis tool that supports terraform <0.12 & >=0.12 & directly integrates with HCL parser for better results.
- [tfenv](https://github.com/tfutils/tfenv) - Terraform version manager inspired by rbenv.
- [tfjson](https://github.com/palantir/tfjson) - Utility to read in a Terraform plan file and dump it out in JSON. :skull:
- [tflint](https://github.com/wata727/tflint) - Terraform linter for detecting errors that can not be detected by `terraform plan`
- [tfmask](https://github.com/cloudposse/tfmask) - Terraform 实用程序，用于屏蔽来自“terraform plan”和“terraform apply”的选择输出
- [tfmigrate](https://github.com/minamijoyo/tfmigrate) - 适用于 GitOps 的 Terraform 状态迁移工具.
- [tfmigrator](https://github.com/tfmigrator/cli) - Go 库和 CLI 迁移 Terraform 配置和状态
- [tfscaffold](https://github.com/tfutils/tfscaffold) - 用于控制多环境多组件 terraform 托管 AWS 基础设施的框架.
- [tfschema](https://github.com/minamijoyo/tfschema) - Schema inspector for Terraform providers.
- [tfupdate](https://github.com/minamijoyo/tfupdate) - Update version constraints in your Terraform configurations.
- [tfvaultenv](https://github.com/oulman/tfvaultenv) - tfvaultenv 从 HashiCorp Vault 读取机密，并为具有这些机密的各种 Terraform 提供者输出环境变量.
- [tfwrapper](https://github.com/manheim/tfwrapper) - Rubygem providing rake tasks for running Hashicorp Terraform sanely.
- [tgf](https://github.com/coveo/tgf) - Terragrunt frontend for executing Terragrunt/Terraform through Docker.
- [xterrafile](https://github.com/devopsmakers/xterrafile) Systematically manage external modules from the module registry, git or local directories for use in Terraform (written in Go).
- [yor](https://github.com/bridgecrewio/yor) - Automatically tag and trace infrastructure as code frameworks (Terraform, Cloudformation and Serverless) .

## Libraries

- [pyhcl](https://github.com/virtuald/pyhcl) - HCL parser in Python
- [python-hcl2](https://github.com/amplify-education/python-hcl2/) - Python 中的 HCL2 解析器
- [rhcl](https://github.com/winebarrel/rhcl) - Pure Ruby HCL parser

## Boilerplates

- [Terraform Generator](https://github.com/sudokar/generator-tf-module) - Scaffolding for a new terraform module or project with support of test frameworks (terratest and kitchen-terraform)

## Terraform Enterprise

- [terraform-enterprise-cli](https://github.com/skierkowski/terraform-enterprise-cli) - Terraform 企业命令行界面.
- [terraform-enterprise-client](https://github.com/skierkowski/terraform-enterprise-client) - Terraform Enterprise API Ruby 客户端和命令行工具.
- [terraform-enterprise-migrator](https://github.com/silinternational/terraform-enterprise-migrator) - Script for migrating Terraform Enterprise environments from Legacy to new version of Terraform Enterprise.
- [tfe-state-explorer](https://github.com/segmentio/tfe-state-explorer)  - 用于探索远程 terraform 企业状态的简单外壳，具有自动完成功能.  ：颅骨：
- [Scalr](https://scalr.com) - Alternative to Terraform Enterprise with OPA integration :heavy_dollar_sign:
- [env0](https://env0.com) - Alternative to Terraform Cloud/Enterprise with OPA integration, custom flows and Terragrunt support :heavy_dollar_sign:

## Videos

- [Your Weekly Dose of Terraform](https://bit.ly/terraform-youtube) - YouTube channel with weekly live streams covering Terraform news, reviews, interviews, Q&A, live coding, and some hacking with Terraform.
- [Terraform explained in 15 mins](https://www.youtube.com/watch?v=l5k1ai_GBDE) - Terraform explained in 15 mins.
- [Terraform Course](https://www.youtube.com/watch?v=SLB_c_ayRMo) - Automate your AWS cloud infrastructure.
- [How to Build Reusable, Composable, Battle tested Terraform Modules](https://www.youtube.com/watch?v=LVgP63BkhKQ) - Yevgeniy Brikman talks about how to write Terraform code so that it is reusable, composable and testable. The presentation focuses on Terraform modules, but also provides a brief and clear explanation of what problem Terraform was created to solve and a short demo of Terraform basics (~39 min, October 2017).
- [Building Scalable, Repeatable Infrastructure in the Cloud with Terraform](https://www.youtube.com/watch?v=cG7pcksTAnY) - Demonstrates how Terraform enables the practice of Infrastructure as Code by deploying TeamCity in AWS using a hosted PostgreSQL.
- [Creating a Google Compute Instance with Terraform](https://www.youtube.com/watch?v=fo3VX33Zx0c) - Example of creating a Google Compute Instance with Terraform code.
- [Creating a Terraform Provider for Just About Anything](https://www.hashicorp.com/resources/creating-terraform-provider-for-anything) - Learn how to contribute to a Terraform provider or create your own from this walkthrough.
- [Evolving Your Infrastructure with Terraform](https://www.youtube.com/watch?v=wgzgVm7Sqlk) - CTO of OpenCredo provides an extensive look at using Terraform in the real-world with the help of some interesting use-cases.
- [Going Multi-Cloud with Terraform and Nomad](https://www.youtube.com/watch?v=e42A4aBZUkQ).
- [How to Extend the Terraform Provider List](https://www.youtube.com/watch?v=2BvpqmFpchI) - In this talk, Paul will walk through the creation of a terraform provider.
- [Orchestrating Containers with Terraform and Consul](https://www.infoq.com/presentations/terraform-consul) - Mitchell Hashimoto shows how Terraform can be used to deploy and scale containerized workloads.
- [Production ChaosMonkey with Terraform](https://www.youtube.com/watch?v=CPI6W3LK0-g) - How DigitalOcean uses Terraform to run production integration tests.
- [Running a Terraform Environment at Scale](https://www.youtube.com/watch?v=3JVGSq7QIS0) - 使用数百个 AWS 账户大规模运行 Terraform.
- [Setup Continuous Integration for a Terraform module](https://www.youtube.com/watch?v=vuJ6bjYKUcA) - 使用 CI 和 Kitchen-Terraform 来测试、标记和发布我们的 Terraform 模块的示例，该模块创建了一个谷歌计算实例.
- [State of Terraform Providerland](https://www.youtube.com/watch?v=ar1PF5iDtbg) - How Terraform providers work and how to write one.
- [Terraform At Scale](https://www.youtube.com/watch?v=RldRDryLiXs) - Segment 如何使用 Terraform.
- [Terraform w/ Lee Trout](https://www.youtube.com/watch?v=p2ESyuqPw1A) - Focuses on development patterns and how to effectively structure Terraform code.
- [Terraforming the Composable World](https://www.youtube.com/watch?v=cHrOXPatFeg) - Integrating Terraform with an on-premise bare metal provisioning.
- [Test and verify a Google Compute Instance with Kitchen-Terraform](https://www.youtube.com/watch?v=kiH3-LEveek) - Example of using Kitchen-Terraform to test our Terraform code that creates a Google Compute.
- [Untangling Terraform Through Refactoring](https://www.youtube.com/watch?v=OH6iDKaXpZs) - 如何以最小的风险谨慎地重构您的 Terraform 代码.

## Editor Plugins

- [Atom terraform-lookup](https://atom.io/packages/terraform-lookup)
- [Emacs terraform-mode](https://github.com/syohex/emacs-terraform-mode)
- [Intellij](https://plugins.jetbrains.com/plugin/7808-hashicorp-terraform--hcl-language-support)
- [Terraform-lsp](https://github.com/juliosueiras/terraform-lsp) （Terraform 语言服务器协议）
- [Vim-Terraform](https://github.com/hashivim/vim-terraform)
- [Vim-Terraform-Completion](https://github.com/juliosueiras/vim-terraform-completion)
- [VS Code](https://marketplace.visualstudio.com/items?itemName=mauve.terraform)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Shuaib Yunus has waived all copyright and related or neighboring rights to this work.
