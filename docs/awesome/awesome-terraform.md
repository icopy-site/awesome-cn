<div class="github-widget" data-repo="shuaibiyy/awesome-terraform"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Terraform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精选的资源清单 [HashiCorp's Terraform](https://www.terraform.io/).
[<img src="https://rawgit.com/shuaibiyy/awesome-terraform/master/terraform.svg" align="right" width="100">](https://terraform.io)
Your [contributions](https://github.com/shuaibiyy/awesome-terraform/blob/master/contributing.md) 受欢迎的！

 Terraform使您能够安全，可预测地创建，更改和改善生产基础架构.  它是一个开放源代码工具，将API编码为声明性配置文件，这些文件可以在团队成员之间共享，视为代码，进行编辑，查看和版本控制.



## Official Resources

* [Introduction to Terraform](https://www.terraform.io/intro/)
* [Terraform Documentation](https://www.terraform.io/docs/)
* [Hashicorp Terraform Blog](https://www.hashicorp.com/blog/category/terraform)
* [Terraform learn](https://learn.hashicorp.com/terraform/)
* [Terraform GitHub Actions](https://github.com/hashicorp/terraform-github-actions)

## Community

* [Terraform Google Group](https://groups.google.com/forum/#!forum/terraform-tool)
* [Terraform Gitter](https://gitter.im/hashicorp-terraform)
* [Terraform Bug Tracker](https://github.com/hashicorp/terraform/issues)
* [Terraform Community Modules](https://github.com/terraform-community-modules)
* [Terraform AWS Modules](https://github.com/terraform-aws-modules) + [meta-configurations repository](https://github.com/terraform-aws-modules/meta)
* [Terraform Module Registry](https://registry.terraform.io/)
* [Terraform PDF Doc](https://github.com/dohsimpson/terraform-doc-pdf)
* [Complete Terraform documentation as PDF files (Updated nightly)](https://github.com/antonbabenko/terraform-docs-as-pdf)
* [Terraform Best Practices](https://www.terraform-best-practices.com/) - [open-source ebook](https://github.com/antonbabenko/terraform-best-practices)
* [Terragrunt Reference Architecture](https://github.com/antonbabenko/terragrunt-reference-architecture)
* [serverless.tf - Doing serverless with Terraform](https://serverless.tf/) -serverless.tf是一个坚定的开源框架，用于使用Terraform在AWS上开发，构建，部署和保护无服务器应用程序和基础架构. [Read more](https://github.com/antonbabenko/serverless.tf).

## Books

* [Terraform: Up & Running](http://www.terraformupandrunning.com/?ref=gruntwork-blog-comprehensive-terraform)
* [The Terraform Book](https://terraformbook.com/)
* [Getting Started with Terraform, 2nd ed.](https://www.amazon.com/Getting-Started-Terraform-production-infrastructure/dp/1788623533/)
* [Infrastructure as Code](http://shop.oreilly.com/product/0636920039297.do)
* [Terraform in Action](https://www.manning.com/books/terraform-in-action)

## Tutorials and Blog Posts

### Beginner Guides
* [A Comprehensive Guide to Terraform](https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca#.w9x897ywp) -“ Terraform：启动与运行”作者的一系列博客文章，指导读者从Terraform开始到在现实世界中使用它.
* [Using Terraform for Cloud Deployments - Part 1](https://dev.to/koenighotze/using-terraform-for-cloud-deployments---part-1) -设置EC2实例.

### Writing Custom Providers

* [Creating custom terraform providers](https://medium.com/@jozmo/creating-custom-terraform-providers-341311823fa2) -创建自定义提供程序的指南.
* [Writing Custom Providers](https://www.terraform.io/docs/extend/writing-custom-providers.html) -用于创建自定义提供程序的官方文档.
* [Writing a Terraform provider](http://blog.jfabre.net/2017/01/22/writing-terraform-provider/) -创建自定义提供程序的指南.

### How-To

* [Deploying Discourse with Terraform](https://www.hashicorp.com/blog/terraform-discourse.html) -显示Terraform如何在一个命令中在DigitalOcean上创建Discourse的运行实例.
* [Easily Deploy A Seneca Microservice to ECS with Wercker and Terraform: Part I](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/), [II](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-ii/) & [III](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/) -说明如何将Terraform合并到微服务部署管道中.
* [Terraforming 1Password](https://blog.agilebits.com/2018/01/25/terraforming-1password/) -1Password如何从CloudFormation迁移到Terraform.
* [Tutorial: How to Use Terraform to Deploy OpenStack Workloads](http://www.stratoscale.com/blog/openstack/tutorial-how-to-use-terraform-to-deploy-openstack-workloads/) -说明了使用OpenStack Terraform提供程序部署Web服务器有多么容易.
* [Zero Downtime Updates with HashiCorp Terraform](https://www.hashicorp.com/blog/zero-downtime-updates-with-terraform) -确保基础架构的零停机时间.
* [Terraform for a Highly Available VPN between AWS and Azure](https://deployeveryday.com/2020/04/13/vpn-aws-azure-terraform.html) -Terraform代码在AWS和Azure之间部署高可用性VPN.

### Multi-Environment Configuration

* [Terraform Design Patterns: the Terrafile](http://bensnape.com/2016/01/14/terraform-design-patterns-the-terrafile/) -使用Terrafile在Terraform项目中管理Terraform模块及其版本.
* [Terraform, VPC, and why you want a tfstate file per env](https://charity.wtf/2016/03/30/terraform-vpc-and-why-you-want-a-tfstate-file-per-env/) -在具有多个环境的大型项目中使用Terraform的一些陷阱以及如何避免它们.
* [Using Pipelines to Manage Environments with Infrastructure as Code](https://medium.com/@kief/https-medium-com-kief-using-pipelines-to-manage-environments-with-infrastructure-as-code-b37285a1cbf5) -解释了构建管道以处理从一种环境转移到另一种环境的基础架构更改的不同方法.

### Azure

* [Learning HashiCorp Terraform](https://www.g10s.io/hashicorp-terraform/) -Azure指南.
* [New Terraform Azure Automation Resources](https://bgelens.nl/terraform-automation-resources/) -Azure自动化.
* [Terraforming Azure PaaS](https://devkimchi.com/2019/01/21/terraforming-azure-paas/) -在Azure上部署PaaS资源.

### Miscellaneous

* [Sharing data between Terraform configurations](https://jamesmckay.net/2016/09/sharing-data-between-terraform-configurations/) -说明如何使用远程状态在Terraform配置之间共享数据.
* [The Segment AWS Stack](https://segment.com/blog/the-segment-aws-stack/) -显示由Terraform支持的基础架构的幕后解决方案 [The Million Dollar Engineering Problem](https://segment.com/blog/the-million-dollar-eng-problem/) 在 [Segment](https://segment.com/).
* [Top 3 Terraform Testing Strategies for Ultra-Reliable Infrastructure-as-Code](https://www.contino.io/insights/top-3-terraform-testing-strategies-for-ultra-reliable-infrastructure-as-code)
* [Two Weeks with Terraform](https://charity.wtf/2016/02/23/two-weeks-with-terraform/) -在野外使用Terraform有一些来之不易的经验，以及一些操作上的智慧.
* [Terraform: Beyond the Basics with AWS](https://aws.amazon.com/blogs/apn/terraform-beyond-the-basics-with-aws/) -有关使用Terraform来提供示例AWS架构的演示的说明.
* [Terraform cost estimation](https://github.com/antonbabenko/terraform-cost-estimation) -基于Terraform计划（0.12+）或Terraform状态（任何版本）的匿名，安全和免费的Terraform成本估算.


## Community Modules

有关此处未列出的更多社区模块，请参见 [Terraform Module Registry](https://registry.terraform.io/).

* [rancher-terraform-digitalocean](https://github.com/lunagt/rancher-terraform-digitalocean) -Digitalocean上的Rancher服务器.
* [segmentio/stack](https://github.com/segmentio/stack) -使用AWS，Docker和ECS配置生产基础架构.
* [terraform-aws-alb](https://github.com/terraform-aws-modules/terraform-aws-alb) -在AWS上创建了应用程序负载均衡器（已验证模块）.
* [terraform-aws-atlantis](https://github.com/terraform-aws-modules/terraform-aws-atlantis) -创建用于运行的Terraform配置 [Atlantis](https://runatlantis.io)  在AWS Fargate上.  支持Github，Gitlab和BitBucket.
* [terraform-aws-autoscaling](https://github.com/terraform-aws-modules/terraform-aws-autoscaling) -创建自动伸缩组和启动配置（已验证模块）.
* [terraform-aws-ecr](https://github.com/cloudposse/terraform-aws-ecr) -在AWS ECR上管理Docker容器注册表.
* [terraform-aws-efs](https://github.com/cloudposse/terraform-aws-efs) -定义一个EFS文件系统.
* [terraform-aws-eks](https://github.com/terraform-aws-modules/terraform-aws-eks) -在AWS（非常流行的模块）上创建Elastic Kubernetes服务.
* [terraform-aws-elb](https://github.com/terraform-aws-modules/terraform-aws-elb) -在AWS（已验证模块）上创建了弹性负载均衡器.
* [terraform-aws-jenkins-ha-agents](https://github.com/neiman-marcus/terraform-aws-jenkins-ha-agents)  -具有HA（现场）代理的基于EC2的Jenkins部署.  在EFS上运行以实现不变性.  完全可自定义，具有合理的默认值.
* [terraform-aws-jenkins](https://github.com/cloudposse/terraform-aws-jenkins) -使用Jenkins构建Docker映像，将其保存到ECR存储库，然后将其部署到运行Docker堆栈的Elastic Beanstalk.
* [terraform-aws-key-pair](https://github.com/cloudposse/terraform-aws-key-pair) -自动生成SSH密钥对（公共/专用密钥）.
* [terraform-aws-modules](https://github.com/terraform-aws-modules) -社区支持的Terraform AWS模块集合（包括官方AWS模块）.
* [terraform-aws-postgresql-rds](https://github.com/azavea/terraform-aws-postgresql-rds) -在RDS上创建PostgreSQL.
* [terraform-aws-rds](https://github.com/terraform-aws-modules/terraform-aws-rds) -在AWS（已验证模块）上创建RDS资源.
* [terraform-aws-secure-baseline](https://github.com/nozaq/terraform-aws-secure-baseline) - Set up your AWS account with the secure baseline configuration based on CIS Amazon Web Services Foundations.
* [terraform-aws-security-group](https://github.com/terraform-aws-modules/terraform-aws-security-group) -在AWS（已验证模块）上创建EC2-VPC安全组.
* [terraform-aws-ssh-bastion-service](https://github.com/joshuamkite/terraform-aws-ssh-bastion-service) -Terraform计划将ssh堡垒部署为AWS上的无状态服务.
* [terraform-aws-lambda](https://github.com/terraform-aws-modules/terraform-aws-lambda) -Terraform模块，该模块构建依赖关系和程序包，并以无数组合创建AWS Lambda资源.
* [terraform-aws-vpc](https://github.com/terraform-aws-modules/terraform-aws-vpc) -在AWS（已验证且非常流行的模块）上创建VPC资源.
* [terraform-azurerm-aks](https://github.com/kjanshair/terraform-azurerm-aks) -在Azure上创建AKS资源.
* [terraform-azurerm-iis](https://github.com/ghostinthewires/terraform-azurerm-iis-install) -在Azure VM实例上安装IIS服务器.
* [terraform-azurerm-mysql](https://github.com/foreverXZC/terraform-azurerm-mysql) -在Azure上创建MySql数据库.
* [terraform-azurerm-redis](https://github.com/rahulkhengare/terraform-azurerm-redis) -在Azure上创建Redis.
* [terraform-azurerm-sqlserver](https://github.com/metadevpro/terraform-azurerm-sqlserver-seed) -在Azure上创建SQl服务器数据库.
* [terraform-digitalocean-droplet](https://registry.terraform.io/modules/terraform-digitalocean-modules/droplet/digitalocean) -用于管理DigitalOcean Droplet和相关资源的Terraform模块.
* [terraform-ecs-jenkins](https://github.com/shuaibiyy/terraform-ecs-jenkins) -使用Terraform在AWS ECS上配置Jenkins.
* [terraform-google-project-factory](https://github.com/terraform-google-modules/terraform-google-project-factory) -通过共享的VPC，IAM，API等进行有根据的Google Cloud Platform项目创建和配置.
* [terraform-linode-k8s](https://registry.terraform.io/modules/linode/k8s/linode/) -在Linode实例上安装Kubernetes.
* [terraform-static-website-s3-cloudfront](https://github.com/sjevs/terraform-static-website-s3-cloudfront) -根据变量在AWS S3和Cloudfront上创建静态网站.
* [tf_aws_availability_zones_cfn](https://github.com/terraform-community-modules/tf_aws_availability_zones_cfn) -从Cloudformation获取您的AWS区域/帐户的可用区.
* [tf_aws_bastion_s3_keys](https://github.com/terraform-community-modules/tf_aws_bastion_s3_keys) -在AWS EC2上创建堡垒主机.
* [tf_aws_coreos_ami](https://github.com/terraform-community-modules/tf_aws_coreos_ami) -使用Terraform查找CoreOS AMI的简便方法.
* [tf_aws_nat](https://github.com/terraform-community-modules/tf_aws_nat) -AWS的NAT实例.

## Private Module Registries

* [anthology](https://github.com/erikvanbrakel/anthology) -私有Terraform注册表实现，可以替代官方注册表.
* [citizen](https://github.com/outsideris/citizen) -专用Terraform模块注册表
* [terraform-simple-registry](https://github.com/apparentlymart/terraform-simple-registry) -Terraform注册协议的简单实现.

## Providers

* [terraform-provider-alicloud](https://github.com/terraform-providers/terraform-provider-alicloud) -阿里云插件.
* [terraform-provider-aws](https://github.com/terraform-providers/terraform-provider-aws) -Amazon Web Services插件.
* [terraform-provider-azurerm](https://github.com/terraform-providers/terraform-provider-azurerm) -Microsoft Azure插件.
* [terraform-provider-datadog](https://github.com/terraform-providers/terraform-provider-datadog) -Datadog插件.
* [terraform-provider-digitalocean](https://github.com/terraform-providers/terraform-provider-digitalocean) -DigitalOcean的插件.
* [terraform-provider-docker](https://github.com/terraform-providers/terraform-provider-docker) -Docker插件.
* [terraform-provider-github](https://github.com/terraform-providers/terraform-provider-github) -GitHub插件.
* [terraform-provider-gitlab](https://github.com/terraform-providers/terraform-provider-gitlab) -适用于GitLab的插件.
* [terraform-provider-google](https://github.com/terraform-providers/terraform-provider-google) -Google Cloud Platform插件.
* [terraform-provider-hcloud](https://github.com/terraform-providers/terraform-provider-hcloud) -Hetzner Cloud插件.
* [terraform-provider-healthchecksio](https://github.com/kristofferahl/terraform-provider-healthchecksio) -管理healthchecks.io资源的提供者.
* [terraform-provider-helm](https://github.com/terraform-providers/terraform-provider-helm) -头盔插件.
* [terraform-provider-ibm](https://github.com/IBM-Cloud/terraform-provider-ibm) -IBM Cloud插件
* [terraform-provider-keycloak](https://github.com/mrparkers/terraform-provider-keycloak) -提供程序来管理您的设置 [Keycloak](https://www.keycloak.org/) 身份提供商服务器.
* [terraform-provider-kubernetes](https://github.com/terraform-providers/terraform-provider-kubernetes) -Kubernetes的插件.
* [terraform-provider-linode](https://github.com/btobolaski/terraform-provider-linode) -Linode插件.
* [terraform-provider-openstack](https://github.com/terraform-providers/terraform-provider-openstack) -OpenStack插件.
* [terraform-provider-pingdom](https://github.com/russellcardullo/terraform-provider-pingdom) -管理Pingdom资源的提供者.
* [terraform-provider-secrethub](https://github.com/secrethub/terraform-provider-secrethub) -SecretHub的提供者.
* [terraform-provider-spinnaker](https://github.com/armory-io/terraform-provider-spinnaker) -管理 [Spinnaker](https://www.spinnaker.io/) Terraform的应用程序和管道.
* [terraform-provider-spotinst](https://github.com/terraform-providers/terraform-provider-spotinst) -适用于AWS，Azure，GCP的Devops自动化平台.
* [terraform-provider-stripe](https://github.com/franckverrot/terraform-provider-stripe) -Stripe的提供者.
* [terraform-provider-uptimerobot](https://github.com/louy/terraform-provider-uptimerobot) -管理uptimerobot资源的提供商.
* [terraform-provider-vaulted](https://github.com/sumup-oss/terraform-provider-vaulted) -通过Terraform加密的HashiCorp Vault机密，可以存储在SCM中，例如Git.
* [terraform-provider-vsphere](https://github.com/terraform-providers/terraform-provider-vsphere) -适用于VMware vSphere的插件.
* [terraform-provider-dominos](https://github.com/ndmckinley/terraform-provider-dominos) -Dominos Pizza的提供商.
* [terraform-provider-azuredevops](https://github.com/mikaelkrief/terraform-provider-azuredevops) -Azure DevOps（VSTS）的提供程序.
* [terraform-provider-snowfake](https://github.com/chanzuckerberg/terraform-provider-snowflake) -Snowflake数据仓库的提供者

## Testing

* [kitchen-terraform](https://github.com/newcontext-oss/kitchen-terraform) -提供了一组Test Kitchen插件，使系统可以使用Test Kitchen融合Terraform配置并通过InSpec控件验证生成的Terraform状态.
* [rspec-terraform](https://github.com/bsnape/rspec-terraform) -针对您的Terraform模块的RSpec测试.
* [terraform-compliance](https://github.com/eerkunt/terraform-compliance) -Terraform文件的BDD测试.
* [terraform_validate](https://github.com/elmundio87/terraform_validate) -协助在Terraform中实施用户定义的标准.
* [terratest](https://github.com/gruntwork-io/terratest) -Terratest是一个Go库，可以更轻松地为基础结构代码编写自动化测试.

## Tools
* [astro](https://github.com/uber/astro/) - Astro is a tool for managing multiple Terraform executions as a single command.
* [atlantis](https://github.com/runatlantis/atlantis) -通过GitHub在Terraform上进行协作的统一工作流程.
* [blast radius](https://github.com/28mm/blast-radius) -Terraform依赖图的交互式可视化.
* [fogg](https://github.com/chanzuckerberg/fogg) -消除管理Terraform资料库中的工作的工具.
* [former2](https://github.com/iann0036/former2) -从AWS账户中的现有资源生成Terraform配置.
* [geopoiesis](https://docs.geopoiesis.io/manual/) -专业的持续集成和部署工具，用于现代声明式基础架构的设置和管理.
* [iam-policy-json-to-terraform](https://github.com/flosell/iam-policy-json-to-terraform) -将JSON格式的IAM策略转换为Terraform aws_iam_policy_document的小型工具
* [k2tf](https://github.com/sl1pm4t/k2tf) -Kubernetes YAML到Terraform HCL转换器.
* [json2hcl](https://github.com/kvz/json2hcl) -将JSON转换为HCL，反之亦然.
* [modules.tf](https://modules.tf/) -基础结构作为代码生成器-通过使用 [Cloudcraft.co](https://cloudcraft.co/app) 到Terraform. [Source code](https://github.com/antonbabenko/modules.tf-lambda).
* [para](https://github.com/paraterraform/para) -缺少的第三方插件管理器和Terraform / Terragrunt的“瑞士军刀”-仅有1个工具可简化所有工作流程.
* [pre-commit-terraform](https://github.com/antonbabenko/pre-commit-terraform) -预先提交git挂钩，以处理Terraform配置（自动格式化，验证，更新文档）.
* [pretf](https://github.com/raymondbutcher/pretf)  -嵌入式Terraform包装器，可使用Python生成Terraform配置.  看到 [pretf documentation](https://pretf.readthedocs.io/en/latest/)
* [python-terrafile](https://github.com/claranet/python-terrafile) -系统地管理来自Github的外部模块，以在Terraform中使用.
* [prettyplan](https://github.com/chrislewisdev/prettyplan) -Prettyplan（[available online here](https://chrislewisdev.github.io/prettyplan/)）是一个小工具，可帮助您轻松查看大型Terraform计划.
* [ruby-terraform](https://github.com/infrablocks/ruby_terraform) -用于调用terraform命令的简单Ruby包装器.
* [scenery](https://github.com/dmlittle/scenery) -另一个Terraform计划输出修饰词.
* [scratchrelaxtv](https://github.com/YakDriver/scratchrelaxtv) -一个简单的Python工具，可帮助模块开发-从main.tf中提取变量，以生成variables.tf，并从variables.tf中创建模块使用存根.
* [tads-boilerplate](https://github.com/Thomvaill/tads-boilerplate) -Ansible和Terraform的功能+ Docker Swarm的简单性=基础架构作为Code和DevOps的最佳实践.
* [tau](https://github.com/avinor/tau) -Tau是terraform之上的瘦包装，用于管理多个部署，依赖项和秘密.
* [terraboard](https://github.com/camptocamp/terraboard) -Web仪表板以检查Terraform状态.
* [terraboot](https://github.com/MastodonC/terraboot) -DSL生成Terraform配置并运行它.
* [terrafile](https://github.com/coretech/terrafile) -系统地管理来自Github的外部模块，以在Terraform中使用（用Go编写）.
* [terrafile](https://github.com/dxw/terrafile) -系统地管理来自Github的外部模块，以在Terraform中使用（用Ruby编写）.
* [terraform-bundle](https://github.com/hashicorp/terraform/tree/master/tools/terraform-bundle)  -轻松构建包含Terraform二进制文件以及提供程序二进制文件的捆绑软件.  对于CI和空白的Terraform Enterprise非常有用.
* [terraform-docs](https://github.com/segmentio/terraform-docs) -快速实用程序，可从terraform模块生成文档.
* [terraform-landscape](https://github.com/coinbase/terraform-landscape) -改进Terraform的计划输出，使其更易于阅读和理解.
* [terraform-plan-parser](https://github.com/lifeomic/terraform-plan-parser) -命令行实用程序和JavaScript API，用于从“ terraform plan”中解析标准输出并将其转换为JSON.
* [terraform-provisioner](https://github.com/shuaibiyy/terraform-provisioner) -用于管理同一Terraform脚本的多个配置的工具.
* [terraform-rake-tasks](https://github.com/gina-alaska/terraform-rake-tasks) -用于管理Terraform计划的共享Rake任务.
* [terraform.py](https://github.com/ciscocloud/terraform.py) -Ansible动态清单脚本，用于解析Terraform状态文件.
* [terraformer](https://github.com/GoogleCloudPlatform/terraformer)  -CLI工具，用于从现有基础结构生成terraform文件.  代码基础架构.  支持的提供商很少.
* [terraforming](https://github.com/dtan4/terraforming)  -将现有的AWS资源导出为Terraform样式（tf，tfstate）.  类似于`terraformer`.
* [terragrunt](https://github.com/gruntwork-io/terragrunt) -Terragrunt是Terraform的薄包装，它提供了额外的工具来使您的Terraform配置保持干燥，与多个Terraform模块一起使用以及管理远程状态.
* [terrahelp](https://github.com/opencredo/terrahelp) -旨在提供补充功能的命令行实用程序，在使用Terraform时有时会证明是有用的.
* [terrahub](https://github.com/TerraHubCorp/terrahub)  -TerraHub是Terraform自动化和编排工具.  与企业友好的GUI无缝集成到console.terrahub.io中，以显示实时Terraform执行以及历史Terraform运行的审核和报告功能.
* [terrascan](https://github.com/cesar-rodriguez/terrascan) -收集用于Terraform模板的静态代码分析的安全性和最佳实践测试
* [Checkov](https://github.com/bridgecrewio/checkov/) -用于Terraform&gt; = 0.12的Terraform静态分析工具
* [tfenv](https://github.com/tfutils/tfenv) -受rbenv启发的Terraform版本管理器.
* [tfjson](https://github.com/palantir/tfjson) -读取Terraform计划文件并将其转储为JSON的实用程序.
* [tflint](https://github.com/wata727/tflint) -Terraform linter，用于检测“ terraform plan”无法检测到的错误
* [tfmask](https://github.com/cloudposse/tfmask) -Terraform实用程序，可屏蔽“ terraform plan”和“ terraform apply”中的选择输出
* [tfscaffold](https://github.com/tfutils/tfscaffold) -用于控制多环境多组件地形管理的AWS基础架构的框架.
* [tfschema](https://github.com/minamijoyo/tfschema) -Terraform提供程序的架构检查器.
* [tfsec](https://github.com/liamg/tfsec) -静态分析支持的安全扫描器，用于您的Terraform代码
* [tfupdate](https://github.com/minamijoyo/tfupdate) -更新Terraform配置中的版本限制.
* [tfwrapper](https://github.com/manheim/tfwrapper) -Rubygem提供耙任务，以合理地运行Hashicorp Terraform.
* [tgf](https://github.com/coveo/tgf) -Terragrunt前端，用于通过Docker执行Terragrunt / Terraform.
* [xterrafile](https://github.com/devopsmakers/xterrafile) 从模块注册表，git或本地目录中系统地管理外部模块，以在Terraform中使用（用Go编写）.
* [TerraDepot](https://github.com/derBroBro/TerraDepot)  Terraform状态存储库，基于默认的http远程后端.  允许在AWS S3上对tfstates进行集中管理.

## Libraries

* [python-hcl2](https://github.com/amplify-education/python-hcl2/) -Python中的HCL2解析器
* [pyhcl](https://github.com/virtuald/pyhcl) -Python中的HCL解析器
* [rhcl](https://github.com/winebarrel/rhcl) -纯Ruby HCL解析器

## Terraform Enterprise

* [terraform-enterprise-cli](https://github.com/skierkowski/terraform-enterprise-cli) -Terraform企业命令行界面.
* [terraform-enterprise-client](https://github.com/skierkowski/terraform-enterprise-client) -Terraform Enterprise API Ruby客户端和命令行工具.
* [terraform-enterprise-migrator](https://github.com/silinternational/terraform-enterprise-migrator) -用于将Terraform Enterprise环境从旧版迁移到Terraform Enterprise的新版本的脚本.
* [tfe-state-explorer](https://github.com/segmentio/tfe-state-explorer) -具有自动完成功能的用于探索远程terraform企业状态的简单外壳.

## Talks

* [Building Scalable, Repeatable Infrastructure in the Cloud with Terraform](https://www.youtube.com/watch?v=cG7pcksTAnY) -演示Terraform如何通过使用托管PostgreSQL在AWS中部署TeamCity来实现将基础架构作为代码的实践.
* [Creating a Google Compute Instance with Terraform](https://www.youtube.com/watch?v=fo3VX33Zx0c) -使用Terraform代码创建Google Compute实例的示例.
* [Creating a Terraform Provider for Just About Anything](https://www.hashicorp.com/resources/creating-terraform-provider-for-anything) -通过本演练了解如何为Terraform提供商做出贡献或创建自己的提供商.
* [Evolving Your Infrastructure with Terraform](https://www.youtube.com/watch?v=wgzgVm7Sqlk) -OpenCredo的CTO借助一些有趣的用例，全面了解了在现实世界中使用Terraform的情况.
* [Going Multi-Cloud with Terraform and Nomad](https://www.youtube.com/watch?v=e42A4aBZUkQ).
* [How to Build Reusable, Composable, Battle tested Terraform Modules](https://www.youtube.com/watch?v=LVgP63BkhKQ)  -Yevgeniy Brikman讨论了如何编写Terraform代码以使其可重用，可组合和可测试.  该演讲重点介绍了Terraform模块，还简要介绍了Terraform创建的要解决的问题，并简要介绍了Terraform基础知识（2017年10月约39分钟）.
* [How to Extend the Terraform Provider List](https://www.youtube.com/watch?v=2BvpqmFpchI) -在此演讲中，Paul将逐步介绍如何创建Terraform提供程序.
* [Orchestrating Containers with Terraform and Consul](https://www.infoq.com/presentations/terraform-consul) -Mitchell Hashimoto展示了如何使用Terraform来部署和扩展容器化工作负载.
* [Production ChaosMonkey with Terraform](https://www.youtube.com/watch?v=CPI6W3LK0-g) -DigitalOcean如何使用Terraform进行生产集成测试.
* [Running a Terraform Environment at Scale](https://www.youtube.com/watch?v=3JVGSq7QIS0) -使用数百个AWS帐户大规模运行Terraform.
* [Setup Continuous Integration for a Terraform module](https://www.youtube.com/watch?v=vuJ6bjYKUcA) -将CI与Kitchen-Terraform结合使用以测试，标记和发布创建Google Compute实例的Terraform模块的示例.
* [State of Terraform Providerland](https://www.youtube.com/watch?v=ar1PF5iDtbg) -Terraform提供程序如何工作以及如何编写.
* [Terraform At Scale](https://www.youtube.com/watch?v=RldRDryLiXs) -细分如何使用Terraform.
* [Terraform w/ Lee Trout](https://www.youtube.com/watch?v=p2ESyuqPw1A) -专注于开发模式以及如何有效构造Terraform代码.
* [Terraforming the Composable World](https://www.youtube.com/watch?v=cHrOXPatFeg) -将Terraform与内部裸机配置集成.
* [Test and verify a Google Compute Instance with Kitchen-Terraform](https://www.youtube.com/watch?v=kiH3-LEveek) -使用Kitchen-Terraform测试我们创建了Google Compute的Terraform代码的示例.
* [Untangling Terraform Through Refactoring](https://www.youtube.com/watch?v=OH6iDKaXpZs) -如何以最小的风险谨慎地重构Terraform代码.
* [Using Terraform for blue-green deployments on Triton](https://www.joyent.com/blog/video-blue-green-deploys-terraform) -有关在Terraform中使用蓝绿色的演示视频.
* [Webinar: Multi-Cloud, One Command with Terraform](https://www.youtube.com/watch?v=adzqsywrJKk) -使用Terraform供应混合云基础架构.

## Editor Plugins

* [Atom terraform-lookup](https://atom.io/packages/terraform-lookup)
* [Emacs terraform-mode](https://github.com/syohex/emacs-terraform-mode)
* [Intellij](https://plugins.jetbrains.com/plugin/7808-hashicorp-terraform--hcl-language-support)
* [Terraform-lsp](https://github.com/juliosueiras/terraform-lsp) （用于Terraform的语言服务器协议）
* [Vim-Terraform](https://github.com/hashivim/vim-terraform)
* [Vim-Terraform-Completion](https://github.com/juliosueiras/vim-terraform-completion)
* [VS Code](https://marketplace.visualstudio.com/items?itemName=mauve.terraform)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，Shuaib Yunus放弃了该作品的所有版权以及相关或邻近的权利.
