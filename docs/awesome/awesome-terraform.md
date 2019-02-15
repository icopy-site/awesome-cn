## Awesome Terraform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;策划的资源列表 [HashiCorp's Terraform](https://www.terraform.io/).
[<img src="https://rawgit.com/shuaibiyy/awesome-terraform/master/terraform.svg" align="right" width="100">](https://terraform.io)
Your [contributions](https://github.com/shuaibiyy/awesome-terraform/blob/master/contributing.md) 受欢迎的！

 Terraform使您能够安全，可预测地创建，更改和改进生产基础架构.  它是一个开源工具，可将API编码为声明性配置文件，可在团队成员之间共享，视为代码，编辑，审阅和版本化.

## Contents

* [Official Resources](#official-resources)
* [Community](#community)
* [Books](#books)
* [Tutorials and Blog Posts](#tutorials-and-blog-posts)
* [Community Modules](#community-modules)
* [Private Module Registries](#private-module-registries)
* [Providers](#providers)
* [Testing](#testing)
* [Tools](#tools)
* [Libraries](#libraries)
* [Terraform Enterprise](#terraform-enterprise)
* [Talks](#talks)
* [Editor Plugins](#editor-plugins)

## Official Resources

* [Introduction to Terraform](https://www.terraform.io/intro/)
* [Terraform Documentation](https://www.terraform.io/docs/)
* [Hashicorp Terraform Blog](https://www.hashicorp.com/blog/category/terraform)

## Community

* [Terraform Google Group](https://groups.google.com/forum/#!forum/terraform-tool)
* [Terraform Gitter](https://gitter.im/hashicorp-terraform)
* [Terraform Bug Tracker](https://github.com/hashicorp/terraform/issues)
* [Terraform Community Modules](https://github.com/terraform-community-modules)
* [Terraform Module Registry](https://registry.terraform.io/)
* [Terraform PDF Doc](https://github.com/dohsimpson/terraform-doc-pdf)

## Books

* [Terraform: Up & Running](http://www.terraformupandrunning.com/?ref=gruntwork-blog-comprehensive-terraform)
* [The Terraform Book](https://terraformbook.com/)
* [Getting Started with Terraform, 2nd ed.](https://www.amazon.com/Getting-Started-Terraform-production-infrastructure/dp/1788623533/)
* [Infrastructure as Code](http://shop.oreilly.com/product/0636920039297.do)

## Tutorials and Blog Posts

* [A Comprehensive Guide to Terraform](https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca#.w9x897ywp) - 来自“Terraform：Up＆Running”作者的系列博客文章，引导读者从Terraform开始到在现实世界中使用它.
* [Bootstrapping Docker Infrastructure With Terraform](http://vilkeliskis.com/blog/2016/02/10/bootstrapping-docker-with-terraform.html) - 使用Terraform在ECS上部署dockerized应用程序的演练.
* [Deploying Discourse with Terraform](https://www.hashicorp.com/blog/terraform-discourse.html) - 显示Terraform如何在一个命令中在DigitalOcean上创建正在运行的Discourse实例.
* [Easily Deploy A Seneca Microservice to ECS with Wercker and Terraform: Part I](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/), [II](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-ii/) & [III](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/) - 说明如何将Terraform整合到微服务部署管道中.
* [Getting Started with Kitchen-Terraform](https://newcontext-oss.github.io/kitchen-terraform/getting_started.html)
* [Sharing data between Terraform configurations](https://jamesmckay.net/2016/09/sharing-data-between-terraform-configurations/) - 说明如何使用远程状态在Terraform配置之间共享数据.
* [Terraform Design Patterns: the Terrafile](http://bensnape.com/2016/01/14/terraform-design-patterns-the-terrafile/) - 使用Terrafile在Terraform项目中管理Terraform模块及其版本
* [Terraform, VPC, and why you want a tfstate file per env](https://charity.wtf/2016/03/30/terraform-vpc-and-why-you-want-a-tfstate-file-per-env/) - 在具有多种环境的大型项目中使用Terraform的一些问题以及如何避免它们.
* [Terraform: Beyond the Basics with AWS](https://aws.amazon.com/blogs/apn/terraform-beyond-the-basics-with-aws/) - 使用Terraform提供示例AWS架构的演示说明.
* [Terraforming 1Password](https://blog.agilebits.com/2018/01/25/terraforming-1password/) -  1Password如何从CloudFormation迁移到Terraform.
* [The Segment AWS Stack](https://segment.com/blog/the-segment-aws-stack/) - 显示由Terraform提供支持的基础设施的幕后故障 [The Million Dollar Engineering Problem](https://segment.com/blog/the-million-dollar-eng-problem/) 在 [Segment](https://segment.com/).
* [Top 3 Terraform Testing Strategies for Ultra-Reliable Infrastructure-as-Code](https://www.contino.io/insights/top-3-terraform-testing-strategies-for-ultra-reliable-infrastructure-as-code)
* [Tutorial: How to Use Terraform to Deploy OpenStack Workloads](http://www.stratoscale.com/blog/openstack/tutorial-how-to-use-terraform-to-deploy-openstack-workloads/) - 说明使用OpenStack Terraform提供程序部署Web服务器是多么容易.
* [Two Weeks with Terraform](https://charity.wtf/2016/02/23/two-weeks-with-terraform/) - 在野外使用Terraform的一些来之不易的经验，以及一些操作智慧.
* [Using Pipelines to Manage Environments with Infrastructure as Code](https://medium.com/@kief/https-medium-com-kief-using-pipelines-to-manage-environments-with-infrastructure-as-code-b37285a1cbf5) - 解释构建管道的不同方法，以处理从一个环境到下一个环境的基础设施变化.
* [Using Terraform for Cloud Deployments - Part 1](https://dev.to/koenighotze/using-terraform-for-cloud-deployments---part-1) - 初学者教程，重点是使用Terraform配置EC2实例.

## Community Modules

有关此处未列出的更多社区模块，请参阅 [Terraform Module Registry](https://registry.terraform.io/).

* [rancher-terraform-digitalocean](https://github.com/lunagt/rancher-terraform-digitalocean) -  digitalocean上的Rancher服务器.
* [segmentio/stack](https://github.com/segmentio/stack) - 使用AWS，Docker和ECS配置生产基础架构.
* [terraform-aws-ecr](https://github.com/cloudposse/terraform-aws-ecr) - 在AWS ECR上管理Docker容器注册表.
* [terraform-aws-efs](https://github.com/cloudposse/terraform-aws-efs) - 定义EFS文件系统.
* [terraform-aws-jenkins](https://github.com/cloudposse/terraform-aws-jenkins) - 使用Jenkins构建Docker镜像，将其保存到ECR仓库，并将其部署到运行Docker堆栈的Elastic Beanstalk.
* [terraform-aws-key-pair](https://github.com/cloudposse/terraform-aws-key-pair) - 自动生成SSH密钥对（公钥/私钥）.
* [terraform-aws-postgresql-rds](https://github.com/azavea/terraform-aws-postgresql-rds) - Creates PostgreSQL on RDS.
* [terraform-aws-secure-baseline](https://github.com/nozaq/terraform-aws-secure-baseline) - 使用基于CIS Amazon Web Services Foundations的安全基准配置设置您的AWS账户.
* [terraform-aws-ssh-bastion-service](https://github.com/joshuamkite/terraform-aws-ssh-bastion-service) -  Terraform计划将ssh堡垒部署为AWS上的无状态服务
* [terraform-ecs-jenkins](https://github.com/shuaibiyy/terraform-ecs-jenkins) - 使用Terraform在AWS ECS上规定Jenkins.
* [terraform-google-project-factory](https://github.com/terraform-google-modules/terraform-google-project-factory) - 使用共享VPC，IAM，API等创建和配置意见的Google Cloud Platform项目.
* [terraform-static-website-s3-cloudfront](https://github.com/sjevs/terraform-static-website-s3-cloudfront) - 根据变量在AWS S3和Cloudfront上创建静态网站.
* [tf_aws_asg_elb](https://github.com/terraform-community-modules/tf_aws_asg_elb) - 创建自动扩展组和启动配置以与Elastic Load Balancer一起使用.
* [tf_aws_availability_zones_cfn](https://github.com/terraform-community-modules/tf_aws_availability_zones_cfn) - 从Cloudformation获取AWS区域/帐户的可用区域.
* [tf_aws_bastion_s3_keys](https://github.com/terraform-community-modules/tf_aws_bastion_s3_keys) - 在AWS EC2上创建堡垒主机.
* [tf_aws_coreos_ami](https://github.com/terraform-community-modules/tf_aws_coreos_ami) - 使用terraform查找CoreOS AMI的简便方法.
* [tf_aws_nat](https://github.com/terraform-community-modules/tf_aws_nat) -  AWS的NAT实例.
* [tf_aws_private_subnet_nat_gateway](https://github.com/terraform-community-modules/tf_aws_private_subnet_nat_gateway) - 在AWS中使用NAT网关创建私有子网.
* [tf_aws_rds](https://github.com/terraform-aws-modules/terraform-aws-rds) - 在AWS上创建RDS资源.
* [terraform-aws-security-group](https://github.com/terraform-aws-modules/terraform-aws-security-group) - 在AWS上创建EC2-VPC安全组.
* [tf_aws_ubuntu_ami](https://github.com/terraform-community-modules/tf_aws_ubuntu_ami) - 使用Terraform查找Ubuntu AMI的简便方法.
* [terraform-aws-vpc](https://github.com/terraform-aws-modules/terraform-aws-vpc) - 在AWS上创建VPC资源.
* [tf_aws_vpc_only](https://github.com/terraform-community-modules/tf_aws_vpc_only) - 仅在AWS中提供VPC（无子网）.

## Private Module Registries

* [anthology](https://github.com/erikvanbrakel/anthology) - 私人Terraform注册管理机构实施，作为官方注册机构的替代方案.
* [citizen](https://github.com/outsideris/citizen) - 私人Terraform模块注册表
* [terraform-simple-registry](https://github.com/apparentlymart/terraform-simple-registry) -  Terraform注册管理机构协议的简单实现.

## Providers

* [terraform-provider-hcloud](https://github.com/terraform-providers/terraform-provider-hcloud) -  Hetzner Cloud的Terraform插件
* [terraform-provider-linode](https://github.com/btobolaski/terraform-provider-linode) - 用于linode的Terraform插件
* [terraform-provider-pingdom](https://github.com/russellcardullo/terraform-provider-pingdom) -  Terraform提供商管理pingdom资源.
* [terraform-provider-uptimerobot](https://github.com/louy/terraform-provider-uptimerobot) -  Terraform提供商管理uptimerobot资源.
* [terraform-provider-healthchecksio](https://github.com/kristofferahl/terraform-provider-healthchecksio) -  Terraform提供商管理healthchecks.io资源.


## Testing

* [kitchen-terraform](https://github.com/newcontext-oss/kitchen-terraform) - 提供一组Test Kitchen插件，使系统能够使用Test Kitchen收敛Terraform配置并使用InSpec控件验证生成的Terraform状态.
* [rspec-terraform](https://github.com/bsnape/rspec-terraform) -  Terraform模块的RSpec测试
* [terraform-compliance](https://github.com/eerkunt/terraform-compliance) -  Terraform文件的BDD测试.
* [terraform_validate](https://github.com/elmundio87/terraform_validate) - 协助在Terraform中实施用户定义的标准.
* [terratest](https://github.com/gruntwork-io/terratest) -  Terratest是一个Go库，可以更轻松地为您的基础架构代码编写自动化测试

## Tools
* [astro](https://github.com/uber/astro/) -  Astro是一种用于将多个Terraform执行作为单个命令进行管理的工具.
* [atlantis](https://github.com/runatlantis/atlantis) - 通过GitHub在Terraform上进行协作的统一工作流程.
* [blast radius](https://github.com/28mm/blast-radius) -  Terraform依赖图的交互式可视化.
* [geopoiesis](https://docs.geopoiesis.io/manual/) - 用于现代声明性基础设施供应和管理的专用持续集成和部署工具.
* [python-terrafile](https://github.com/claranet/python-terrafile) - 系统地管理来自Github的外部模块以用于Terraform.
* [ruby-terraform](https://github.com/infrablocks/ruby_terraform) - 用于调用terraform命令的简单Ruby包装器.
* [terraboard](https://github.com/camptocamp/terraboard) - 用于检查Terraform国家的Web仪表板.
* [terraboot](https://github.com/MastodonC/terraboot) -  DSL生成terraform配置并运行它.
* [terrafile](https://github.com/coretech/terrafile) - 从Github系统地管理外部模块以用于Terraform（用Go编写）.
* [terrafile](https://github.com/dxw/terrafile) - 从Github系统地管理外部模块以用于Terraform（用Ruby编写）.
* [terraform-docs](https://github.com/segmentio/terraform-docs) - 用于从terraform模块生成文档的快速实用程序.
* [terraform-landscape](https://github.com/coinbase/terraform-landscape) - 改进Terraform的计划输出，使其更易于阅读和理解.
* [terraform-plan-parser](https://github.com/lifeomic/terraform-plan-parser) - 命令行实用程序和JavaScript API，用于从“terraform plan”解析stdout并将其转换为JSON.
* [terraform-provisioner](https://github.com/shuaibiyy/terraform-provisioner) - 用于管理相同Terraform脚本的多个条款的工具.
* [terraform-rake-tasks](https://github.com/gina-alaska/terraform-rake-tasks) - 用于管理terraform计划的共享Rake任务.
* [terraform.py](https://github.com/ciscocloud/terraform.py) - 用于解析Terraform状态文件的Ansible动态库存脚本.
* [terragrunt](https://github.com/gruntwork-io/terragrunt) -  Terragrunt是Terraform的薄包装器，支持锁定Terraform状态并实施最佳实践.
* [terrascan](https://github.com/cesar-rodriguez/terrascan) - 收集用于地形模板的静态代码分析的安全性和最佳实践测试
* [tfenv](https://github.com/tfutils/tfenv) - 受rbenv启发的Terraform版本管理器.
* [tfjson](https://github.com/palantir/tfjson) - 用于读入Terraform计划文件并将其转储为JSON的实用程序
* [tflint](https://github.com/wata727/tflint) - 用于检测“terraform plan”无法检测到的错误的Terraform linter
* [tfscaffold](https://github.com/tfutils/tfscaffold) - 用于控制多环境多组件terraform管理的AWS基础架构的框架
* [tfschema](https://github.com/minamijoyo/tfschema) -  Terraform提供商的架构检查员.
* [tfwrapper](https://github.com/manheim/tfwrapper) -  Rubygem提供运行Hashicorp Terraform的rake任务
* [tgf](https://github.com/coveo/tgf) - 通过Docker执行Terragrunt / Terraform的Terragrunt前端.

## Libraries

* [pyhcl](https://github.com/virtuald/pyhcl) -  Python中的HCL解析器
* [rhcl](https://github.com/winebarrel/rhcl) - 纯Ruby HCL解析器

## Terraform Enterprise

* [terraform-enterprise-cli](https://github.com/skierkowski/terraform-enterprise-cli) -  Terraform企业命令行界面
* [terraform-enterprise-client](https://github.com/skierkowski/terraform-enterprise-client) -  Terraform Enterprise API Ruby客户端和命令行工具
* [terraform-enterprise-migrator](https://github.com/silinternational/terraform-enterprise-migrator) - 用于将Terraform Enterprise环境从Legacy迁移到新版Terraform Enterprise的脚本
* [tfe-state-explorer](https://github.com/segmentio/tfe-state-explorer) - 用于探索远程terraform企业状态的简单shell，具有自动完成功能.

## Talks

* [Orchestrating Containers with Terraform and Consul](https://www.infoq.com/presentations/terraform-consul) -  Mitchell Hashimoto展示了Terraform如何用于部署和扩展容器化工作负载.
* [Building Scalable, Repeatable Infrastructure in the Cloud with Terraform](https://www.youtube.com/watch?v=cG7pcksTAnY) - 通过使用托管的PostgreSQL在AWS中部署TeamCity，演示Terraform如何实现基础架构作为代码的实践.
* [Evolving Your Infrastructure with Terraform](https://www.youtube.com/watch?v=wgzgVm7Sqlk) - 在一些有趣的用例的帮助下，OpenCredo的CTO提供了在现实世界中使用Terraform的广泛视角.
* [Going Multi-Cloud with Terraform and Nomad](https://www.youtube.com/watch?v=e42A4aBZUkQ)
* [Running a Terraform Environment at Scale](https://www.youtube.com/watch?v=3JVGSq7QIS0) - 大规模运行Terraform，拥有数百个AWS账户.
* [Terraforming the Composable World](https://www.youtube.com/watch?v=cHrOXPatFeg) - 将Terraform与内部裸机配置集成.
* [State of Terraform Providerland](https://www.youtube.com/watch?v=ar1PF5iDtbg) -  Terraform提供商如何工作以及如何编写.
* [Untangling Terraform Through Refactoring](https://www.youtube.com/watch?v=OH6iDKaXpZs) - 如何以最小的风险仔细地重构Terraform代码.
* [Terraform At Scale](https://www.youtube.com/watch?v=RldRDryLiXs) -  Segment如何使用Terraform.
* [Production ChaosMonkey with Terraform](https://www.youtube.com/watch?v=CPI6W3LK0-g) -  DigitalOcean如何使用Terraform运行生产集成测试.
* [Terraform w/ Lee Trout](https://www.youtube.com/watch?v=p2ESyuqPw1A) - 重点关注开发模式以及如何有效地构建Terraform代码.
* [Webinar: Multi-Cloud, One Command with Terraform](https://www.youtube.com/watch?v=adzqsywrJKk) - 使用Terraform配置混合云基础架构.
* [How to Build Reusable, Composable, Battle tested Terraform Modules](https://www.youtube.com/watch?v=LVgP63BkhKQ)   -  Yevgeniy Brikman谈论如何编写Terraform代码，使其可重用，可组合和可测试.  演讲重点介绍Terraform模块，同时也简要明了地解释了Terraform要解决的问题以及Terraform基础知识的简短演示（约39分钟，2017年10月）

## Editor Plugins

* [Vim-Terraform](https://github.com/hashivim/vim-terraform)
* [Vim-Terraform-Completion](https://github.com/juliosueiras/vim-terraform-completion)
* [Intellij](https://plugins.jetbrains.com/plugin/7808-hashicorp-terraform--hcl-language-support)
* [Emacs terraform-mode](https://github.com/syohex/emacs-terraform-mode)
* [VS Code](https://marketplace.visualstudio.com/items?itemName=mauve.terraform)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，Shuaib Yunus已放弃所有版权及相关或相邻的权利.
