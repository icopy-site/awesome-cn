<div class="github-widget" data-repo="kolomied/awesome-cdk"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>

&gt; 精选列表 [AWS Cloud Development Kit](https://github.com/awslabs/aws-cdk) (AWS CDK) 开源项目、指南、博客和其他资源.

AWS 云开发工具包 (AWS CDK) 是一个开源软件开发框架，用于在代码中定义云基础设施.



## Construct Libraries

本节包括各种编程语言的代码库，它们提供可在 CDK 应用程序中使用的构造.

### APIs

* [cdk-chalice](https://github.com/alexpulver/cdk-chalice) - AWS Chalice 的 AWS CDK 构造（AWS 的 Python 无服务器微框架）.
* [auto-cdk](https://github.com/wulfmann/auto-cdk) - 自动生成与文件系统 (beta) 的 api-gateway/lambda 集成.
* [crow-api](https://github.com/thomasstep/crow-api) - 根据您的文件结构创建带有路由的无服务器 API.

### Databases

* [aws-cdk-dynamodb-seeder](https://github.com/elegantdevelopment/aws-cdk-dynamodb-seeder) - 用于 DynamoDB 的简单 CDK 播种器.
* [cdk-tweet-sentiment](https://www.npmjs.com/package/cdk-tweet-sentiment) - 识别推文中的情绪并将其记录到 Amazon DynamoDB 表中.
* [cdk-postgresql](https://github.com/botpress/cdk-postgresql) - 适用于 PostgreSQL 的 AWS CDK 构造.
* [cdk-sqlserver-seeder](https://github.com/kolomied/cdk-sqlserver-seeder) - 针对 SQL Server 数据库执行自定义 SQL 脚本的 CDK 构造.

### Static Websites

* [cdk-static-website](https://github.com/cloudcomponents/cdk-components/blob/master/packages/cdk-static-website) - CDK 组件使用 S3 创建静态网站，配置 CloudFront (CDN) 并通过 Route53 (DNS) 映射自定义域.
* [ness](https://github.com/nessjs/ness) - CDK 支持的 CLI 工具，用于将静态站点部署到您的 AWS 账户.

### Security

* [cdk-passwordless](https://github.com/farminf/aws-cdk-passwordless) - 构造使用用户池进行无密码身份验证.
* [cdk-iam-generator](https://github.com/srihariph/cdk-iam-generator) - 构建以使用 JSON 配置生成 IAM 托管策略和 IAM 角色.
* [c3](https://github.com/SSHcom/c3) - 符合隐私和安全最佳实践.
* [cdk-iam-floyd](https://github.com/udondan/iam-floyd) - 具有流畅界面的 IAM 策略语句生成器.
* [k9-cdk](https://github.com/k9securityio/k9-cdk) - 构建以轻松生成安全的 S3 存储桶策略.
* [cdk-cloudfront-authorization](https://github.com/cloudcomponents/cdk-constructs/tree/master/packages/cdk-cloudfront-authorization) - 使用 Lambda@Edge 进行 Cognito 身份验证的 CloudFront.
* [aws-firewall-factory](https://github.com/globaldatanet/aws-firewall-factory) - 部署、更新和暂存您的 WAF，同时通过 FMS 集中管理它们.
### Ops

* [cdk-instanceStopRule](https://github.com/tecracer/cdk-constructs/tree/master/packages/cdk-instanceStopRule) - CDK 组件，它使用 CloudWatch 规则创建实例以在一天结束时停止它.
* [cdk-time-bomb](https://github.com/jmb12686/cdk-time-bomb) - CDK Construct that implodes your AWS CDK Stack after a set amount of time.

### Queue

* [cdk-tweet-queue](https://www.npmjs.com/package/cdk-tweet-queue) - 使用来自推特搜索查询的推文填充 SQS 队列.
* [cdk-ses-template-mailer](https://github.com/mkrn/cdk-ses-template-mailer) - 构建创建 AWS SES 电子邮件模板 + 微服务以使用 AWS SES 发送模板化电子邮件.
* [cdk-sqs-monitored](https://github.com/kamilbiela/cdk-sqs-monitored) - SQS 构造带有死信队列和配置的警报.

### CI/CD

* [aws-delivlib](https://github.com/awslabs/aws-delivlib) - 综合用于多语言软件交付的 CI/CD 管道（由 CDK 本身使用）.
* [cdk-blue-green-container-deployment](https://github.com/cloudcomponents/cdk-constructs/tree/master/packages/cdk-blue-green-container-deployment) - 使用 CodeDeploy 部署蓝/绿容器.

### Monitoring

* [cdk-watchful](https://github.com/eladb/cdk-watchful) - CDK 应用程序的自动仪表板和警报.
* [aws-cdk-billing-alarm](https://github.com/alvyn279/aws-cdk-billing-alarm) - 构造设置电子邮件警报以超出您的 AWS 账单金额.
* [cdk-monitoring-constructs](https://github.com/cdklabs/cdk-monitoring-constructs)  - 使用高级 API 为您的 AWS 应用程序创建监控. 自动生成仪表板.

### Workflows

* [cdk-pull-request-check](https://github.com/cloudcomponents/cdk-components/blob/master/packages/cdk-pull-request-check) - 自动检查拉取请求的 CDK 组件.
* [cdk-github-webhook](https://github.com/cloudcomponents/cdk-components/blob/master/packages/cdk-github-webhook) - 提供 GitHub webhook 的 CDK 组件.
* [cdk-codepipeline-slack](https://github.com/cloudcomponents/cdk-components/blob/master/packages/cdk-codepipeline-slack) - CDK component that provisions a #slack approval workflow.
* [cdk-codecommit-backup](https://github.com/cloudcomponents/cdk-components/tree/master/packages/cdk-codecommit-backup) - 将 CodeCommit 存储库备份到 S3.
* [Alexa Deployment Pipeline](https://github.com/taimos/cdk-constructs/tree/master/lib/alexa) - 创建一个 CodePipeline 以使用 AWS SAM 和 DeployToAlexa 操作将 Alexa Skills 部署到 Lambda 和开发人员控制台的构造.
* [cdk-developer-tools-notifications](https://github.com/cloudcomponents/cdk-constructs/tree/master/packages/cdk-developer-tools-notifications) - Slack / Microsoft Teams / 开发人员工具的电子邮件通知：CodeCommit、CodeBuild、CodeDeploy、CodePipeline.

### Multi-accounts setup
* [aws-bootstrap-kit](https://github.com/awslabs/aws-bootstrap-kit) - 使用 AWS Organization、AWS SSO、DNS 和 AWS CodePipeline 创建多账户设置.
* [cdk-organizations](https://github.com/pepperize/cdk-organizations) - 有助于预置 AWS 组织、组织单位 (OU)、账户和策略的 CDK 构造.

## High-Level Frameworks

* [punchcard](https://github.com/punchcard/punchcard) - 用于统一 CDK 的基础设施和运行时代码的 TypeScript 框架，因此您可以在一个 Node.js 应用程序的上下文中声明构造并实现运行时逻辑.
* [aws-cdk-pure](https://github.com/fogfish/aws-cdk-pure) - 使用 AWS CDK 开发纯功能和高阶云组件的工具包.
* [cdk-stepfunctions-patterns](https://github.com/kolomied/cdk-stepfunctions-patterns) - 一组 Step Functions 高级弹性模式.
* [Orkestra](https://github.com/knowsuchagency/orkestra) - 基于 AWS CDK 和 Step Functions 构建的 Airflow 的事件驱动替代方案.
* [SST](https://github.com/serverless-stack/serverless-stack)  - 用于使用 CDK 构建无服务器应用程序的开源框架. 它具有实时 Lambda 开发环境，可以在本地测试和调试 Lambda 函数，而无需重新部署它们.
* [Datajob](https://github.com/vincentclaes/datajob) - 毫不费力地在 AWS 上构建和部署无服务器数据管道或机器学习管道. 

## Scaffolding

* [ReactJS + Cognito + CDK Starter](https://github.com/vbudilov/reactjs-cognito-starter) - 带有 AWS CDK 支持的 ReactJS + Amazon Cognito + Amazon Amplify 框架的入门项目.
* [cra-template-aws-cdk](https://github.com/luisfarzati/rnbw-aws-cdk/tree/master/packages/cra-template-aws-cdk) - 使用 AWS CDK 创建 React App 模板，用于开箱即用的无服务器 React 应用程序的简单配置.
* [create-cdk-app](https://github.com/cdk-tools/create-cdk-app) - 从模板创建 CDK 应用程序.
* [awscdk-jsii-template](https://github.com/pahud/awscdk-jsii-template) - 一个 GitHub 模板存储库，用于生成准备好的环境来构建、测试和发布您 [JSII](https://github.com/kolomied/awesome-cdk/blob/master/(https://github.com/aws/jsii)) 为 AWS CDK 构建库.

## Language Support

* [AWS-CDK-Kotlin-DSL](https://github.com/justincase-jp/AWS-CDK-Kotlin-DSL) - 一个包装库 [AWS CDK Java](https://mvnrepository.com/artifact/software.amazon.awscdk) .  CI 每天自动生成代码并进行部署.
* [aws-cdk-maven-plugin](https://github.com/LinguaRobot/aws-cdk-maven-plugin) - 一个使用 Java 和 Maven 定义和部署 AWS CDK 应用程序的插件.
* [aws-lambda-nodejs-webpack](https://github.com/vvo/aws-lambda-nodejs-webpack) - 替代 Node.js lambda CDK 构造，使用 [webpack](https://webpack.js.org/).
* [aws-lambda-nodejs-esbuild](https://github.com/floydspace/aws-lambda-nodejs-esbuild) - 替代 Node.js lambda CDK 构造，使用 [esbuild](https://github.com/evanw/esbuild).

## Library Publishing

* [GitHub Action](https://github.com/marketplace/actions/aws-cdk-action) - AWS CDK 的 GitHub 操作.
* [jsii-publish](https://github.com/udondan/jsii-publish) - 一个 [Docker image](https://hub.docker.com/r/udondan/jsii-publish) 和 [GitHub action](https://github.com/marketplace/actions/jsii-publish) to build 和 publish CDK constructs created via [JSII](https://github.com/aws/jsii).

## Tools

* [CDK-Dia](https://github.com/pistazie/cdk-dia) - AWS CDK 的自动基础设施图.

## Training Materials and Sample Code

* [Official CDK Examples](https://github.com/aws-samples/aws-cdk-examples) - AWS CDK 的一组示例项目.
* [CDK Serverless Workshop](https://cdkworkshop.com/) - 指导您完成创建和部署 CDK 应用程序的过程的研讨会.
* [Build an App with AWS Cloud Development Kit course on egghead.io](https://egghead.io/courses/build-an-app-with-the-aws-cloud-development-kit?af=6p5abz)
* [Infrastructure is Code with the AWS CDK](https://youtu.be/Lh-kVC2r2AU) - 录制 re:Invent 2018 会议.
* [GitHub Changelog Crawler](https://github.com/aws-samples/aws-cdk-changelogs-demo) - 由 Nathan Peck 编写的成熟 CDK 应用程序，它使用 Fargate、API Gateway、Lambda、CloudFront、S3、ElastiCache 和 Dynamodb.
* [ECS with CI/CD](https://github.com/rix0rrr/cdk-ecs-demo) - 使用 CDK 部署 ECS 应用程序的演示.
* [Example templates for aws cdk](https://github.com/tecracer/cdk-templates) - 来自多个 AWS 项目的工作 TypeScript 片段.
* [Lambda packaging asset](https://gitlab.com/josef.stach/aws-cdk-lambda-asset) - 构建 lambda 函数并生成具有依赖关系的 ZIP 文件的 CDK 资产.
* [Open CDK Guide](https://github.com/kevinslin/open-cdk) - 关于 CDK 和最佳实践的开源指南.
* [Colorteller Example](https://github.com/denmat/colorteller-aws-cdk) - 使用 Fargate 和 Appmesh 的优秀示例项目.
* [CDK Patterns](https://github.com/cdk-patterns/serverless) - 使用 CDK 构建的无服务器架构模式的开源集合.
* [Create a CI/CD pipeline using CodePipeline and CodeBuild](https://sbstjn.com/deploy-react-cra-with-cdk-codepipeline-and-codebuild.html) - 这 [cra-pipeline](https://github.com/sbstjn/cra-pipeline) GitHub 上的项目展示了使用 AWS CodeBuild 部署静态 React 应用程序的 AWS CodePipeline.
* [React SPA with server-side rendering on AWS Lambda](https://sbstjn.com/serverless-create-react-app-server-side-rendering-ssr-lamda.html) - 这 [cra-serverless](https://github.com/sbstjn/cra-serverless) 项目是一个无服务器架构，用于向使用创建的 React 网站添加预渲染 [create-react-app](https://create-react-app.dev).
* [Mini Tutorial: Setup AWS Lambda + ACM + API Gateway with AWS Cloud Development Kit](https://github.com/shaftoe/api-gateway-lambda-cdk-example) - 部署一个功能性公共 API，接收 HTML 表单（例如 /contact_us.html）POST 请求并将其数据传递给 Pushover 通知服务.
* [Example of REST API built with CDK](https://github.com/shaftoe/api-l3x-in) - 支持 REST API 的源代码，位于 https://api.l3x.in/.
* [dilbert-feed](https://github.com/mlafeldt/dilbert-feed) - 用 Go 编写的无服务器应用程序，可让您在 RSS 提要阅读器中享受 Dilbert，而无需任何广告.
* [django-postgres-vue-gitlab-ecs](https://gitlab.com/verbose-equals-true/django-postgres-vue-gitlab-ecs) - 使用 GitLab CI 通过 CDK 部署的示例 Django + Vue.js Web 应用程序.
* [nextjs-vercel-aws-cdk-example](https://github.com/vvo/nextjs-vercel-aws-cdk-example) - PostgreSQL (RDS)、EventBridge (crons) 和 SNS（后台作业）示例以及 Next.js 应用程序.
* [Create and Publish CDK Constructs Using projen and jsii](https://github.com/seeebiii/projen-test) - 带有示例代码的分步指南，用于使用创建新的 CDK 构造 [projen](https://github.com/projen/projen) 和 `jsii` 并将其发布到 npm、Maven Central、PyPi 和 NuGet.

## Blog Posts & Talks

* [Introduction to how and why CDK](https://www.slideshare.net/ranguard/aws-cdk-introduction-191140240) - 由利奥拉普沃斯.
* [How to Build a CDK Construct Library](https://garbe.io/blog/2019/03/26/construct-your-own-cdk-construct-library/) ——菲利普·加布.
* [CDK All The Things: A Whirlwind Tour](https://kevinslin.com/aws/cdk_all_the_things/) - 凯文·S·林.
* [AWS CDK Developer Preview Announcement](https://aws.amazon.com/blogs/developer/aws-cdk-developer-preview/) - 第一个 AWS CDK 开发人员预览版于 2018 年 8 月 27 日宣布.
* [Contributing to the AWS Cloud Development Kit](https://aws.amazon.com/blogs/developer/contributing-to-the-aws-cloud-development-kit/) - 来自 Intuit 的 Mike Cowgill.
* [First look into AWS Cloud Development Kit](https://garbe.io/blog/2018/08/17/first-look-into-cdk/) ——菲利普·加布.
* [Boost your AWS Infrastructure with the CDK](https://www.slideshare.net/philippgarbe/boost-your-aws-infrastructure-with-cdk) - Philipp Garbe 的 SlideShare.
* [Getting started with AWS CDK for Amazon ECS](https://aws.amazon.com/blogs/compute/getting-started-with-the-aws-cloud-development-kit-for-amazon-ecs/) - 内森派克.
* [AWS re:Invent 2018, best of show: CDK](https://medium.com/allermedia-techblog/aws-re-invent-2018-best-of-show-cloud-development-kit-cdk-ad1755561ade) - 所有媒体技术博客.
* [AWS Cloud Development Kit introduction with Live Demos](https://youtu.be/IIiIoMGTJec) - AWS 用户组芬兰聚会 2019 年 1 月.
* [AWS CDK — a glimpse into the future](https://medium.com/nordcloud-engineering/aws-cdk-a-glimpse-into-the-future-90db660f8a89) - 通过 Nordcloud 工程.
* [AWS Infrastructure as Code with CDK](https://medium.com/avmconsulting-blog/aws-infrastructure-as-code-with-cdk-1d6fa013ce7d) ——罗斯·罗德斯.
* [Callbacks with AWS Step Functions](https://medium.com/swlh/callbacks-with-aws-step-functions-a3dde1bc7203) ——罗斯·罗德斯.
* [Using the CDK for CodePipelines Setup](https://www.stefreitag.de/wp/2019/03/07/using-aws-cdk-for-code-pipeline-setup/) - 斯蒂芬星期五.
* [Using the CDK for AWS MSK Setup](https://www.stefreitag.de/wp/2019/08/31/paths-are-made-by-walking-or-how-aws-cdk-and-msk-work-together/) - 斯蒂芬星期五.
* [Serverless Dotnet - E01: Intro to AWS CDK](https://youtu.be/c9UXHPX6-Ns) - 杰克斯科特.
* [GitHub repository](https://github.com/jakejscott/aws-cdk-phone-verify-api) - 杰克斯科特.
* [Infrastructure is Code with the AWS CDK](https://youtu.be/ZWCvNFUN-sU) - AWS 技术讲座网络研讨会.
* [tecRacer Amazon AWS Blog](https://aws-blog.de/tags/cdk.html) - Gernot Glawe 来自 aws-blog.de 的几篇博客文章.
* [Using CDK to build a UDP NLB Logging Service](https://youtu.be/dXTEVp0ATzo) - 通过 ClouderDex.
* [GitHub Repo](https://github.com/ClouderDex/CDK-UDP-NLB-Demo) - 通过 ClouderDex.
* [Purely Functional Cloud Components with AWS CDK](https://i.am.fog.fish/2019/08/23/purely-functional-cloud-with-aws-cdk.html) - 这是一条雾鱼.
* [Using the CDK to probe multiple accounts (sfn/lambda/sqs/sechub)](https://fudless.xyz/aws/seedecay/) - 博客文章来自 [fudless.xyz](https://fudless.xyz).
* [Scheduled Lambda Functions and CI/CD pipeline with AWS CDK](https://medium.com/hatchsoftware/using-the-aws-cdk-to-build-scheduled-lambda-functions-13eb1674586e) - 马腾·托伦.
* [GitHub Repo](https://github.com/HatchSoftware/automatic-aws-db-shutdown-cdk) - 马腾·托伦.
* [AWS Client VPN with mutual TLS](https://lanwen.ru/posts/aws-client-vpn/) - 基里尔梅尔库舍夫.
* [CDK Step Functions](https://dev.to/elthrasher/exploring-aws-cdk-step-functions-1d1e) - 马特摩根.
* [Loading DynamoDB with Custom Resources](https://dev.to/elthrasher/exploring-aws-cdk-loading-dynamodb-with-custom-resources-jlf) - 马特摩根.
* [Loading DynamoDB with Provider Framework](https://dev.to/elthrasher/exploring-aws-cdk-a-million-a-minute-dynamodb-and-providerframework-e92) - 马特摩根.
* [German: React SPA und server-side rendering (SSR) mit AWS Lambda und CloudFront](https://superluminar.io/2020/02/07/react-spa-und-server-side-rendering-ssr-mit-aws-lambda-cloudfront-und-dem-cdk/) - 由 superluminar GmbH 提供.
* [Introducing AWS CDK with a real life Lambda and API gateway example](https://a.l3x.in/2020/02/04/migrating-from-terraform-to-cdk.html) ——亚历山大·福廷.
* [CloudWatch Dashboards as Code (the Right Way) Using AWS CDK](https://medium.com/poka-techblog/cloudwatch-dashboards-as-code-the-right-way-using-aws-cdk-1453309c5481) ——西蒙-皮埃尔·金格拉斯着.
* [Coding the Jamstack missing parts: databases, crons & background jobs](https://dev.to/vvo/coding-the-jamstack-missing-parts-databases-crons-background-jobs-1bpj) - 文森特·沃耶.
* [AWS CDK Continuous Integration and Delivery Using Travis CI](https://medium.com/better-programming/aws-cdk-continuous-integration-and-delivery-using-travis-ci-ee5dd7549434) - 托马斯辛酸.
* [Custom Resources with AWS CDK](https://medium.com/cyberark-engineering/custom-resources-with-aws-cdk-d9a8fad6b673?source=friends_link&sk=549fcf9d998bbea304bdd8d834aca9e6) ——罗伊·本·约瑟夫着.
* [Recommended AWS CDK project structure for Python applications](https://aws.amazon.com/blogs/developer/recommended-aws-cdk-project-structure-for-python-applications/) - 亚历克斯普尔弗.

## Related Projects

* [jsii](https://github.com/awslabs/jsii) - JavaScript 互操作接口，CDK 用于创建语言绑定的技术（目前支持 .NET、Java 和 Python）.
* [cdk8s](https://github.com/awslabs/cdk8s/) - 使用面向对象编程定义 Kubernetes 原生应用程序和抽象.
* [cdktf](https://github.com/hashicorp/terraform-cdk) - 使用编程结构定义基础设施资源并使用 HashiCorp Terraform 进行配置.
* [cdktg](https://github.com/hupe1980/cdk-threagile) - 敏捷威胁建模即代码.

## Tips & Tricks

* [Reflect on the CDK Type System](https://gist.github.com/eladb/68a009cf9c953b04a637bac5c40afdbc) - 探索 CDK 的类型系统.
* [Testing Your Construct Library CodeBuild Configuration Locally](https://github.com/aws/aws-codebuild-docker-images/tree/master/local_builds) - 使用 `jsii/superchain:latest` Docker 镜像.

## Contributing

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/kolomied/awesome-cdk/blob/master/contributing.md) 第一的.
