<div class="github-widget" data-repo="kolomied/awesome-cdk"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>

&gt;精选列表很棒 [AWS Cloud Development Kit](https://github.com/awslabs/aws-cdk) （AWS CDK）开源项目，指南，博客和其他资源.

AWS Cloud Development Kit（AWS CDK）是一个开源软件开发框架，用于在代码中定义云基础架构.



## Construct Libraries

本节包含各种编程语言的代码库，这些代码库提供可在CDK应用程序中使用的构造.

### APIs

* [cdk-chalice](https://github.com/alexpulver/cdk-chalice) -适用于AWS Chalice（适用于AWS的Python无服务器微框架）的AWS CDK构造.
* [auto-cdk](https://github.com/wulfmann/auto-cdk) -自动生成与文件系统（beta）的api-gateway / lambda集成.

### Databases

* [aws-cdk-dynamodb-seeder](https://github.com/elegantdevelopment/aws-cdk-dynamodb-seeder) -用于DynamoDB的简单CDK播种器.
* [cdk-tweet-sentiment](https://www.npmjs.com/package/cdk-tweet-sentiment) -识别推文中的情感，并将其记录到Amazon DynamoDB表中.
* [cdk-postgresql](https://github.com/botpress/cdk-postgresql) -适用于PostgreSQL的AWS CDK构造.
* [cdk-sqlserver-seeder](https://github.com/kolomied/cdk-sqlserver-seeder) -对SQL Server数据库执行自定义SQL脚本的CDK构造.

### Static Websites

* [cdk-static-website](https://github.com/cloudcomponents/cdk-components/blob/master/packages/cdk-static-website) -CDK组件，可使用S3创建静态网站，配置CloudFront（CDN）并通过Route53（DNS）映射自定义域.
* [ness](https://github.com/nessjs/ness) -CDK驱动的CLI工具，用于将静态站点部署到您的AWS账户.

### Security

* [cdk-passwordless](https://github.com/farminf/aws-cdk-passwordless) -使用userpool进行无密码身份验证的构造.
* [cdk-iam-generator](https://github.com/srihariph/cdk-iam-generator) -使用JSON配置生成IAM托管策略和IAM角色.
* [c3](https://github.com/SSHcom/c3) -符合隐私和安全最佳做法.
* [cdk-iam-floyd](https://github.com/udondan/iam-floyd) -具有流畅接口的IAM策略声明生成器.
* [k9-cdk](https://github.com/k9securityio/k9-cdk) -轻松生成安全的S3存储桶策略.

### Ops

* [cdk-instanceStopRule](https://github.com/tecracer/cdk-constructs/tree/master/packages/cdk-instanceStopRule) -CDK组件，该组件使用CloudWatch规则创建实例以在一天结束时将其停止.
* [cdk-time-bomb](https://github.com/jmb12686/cdk-time-bomb) -CDK构造，在一定时间后会爆破您的AWS CDK堆栈.

### Queue

* [cdk-tweet-queue](https://www.npmjs.com/package/cdk-tweet-queue) -用高音扬声器搜索查询的高音填充SQS队列.
* [cdk-ses-template-mailer](https://github.com/mkrn/cdk-ses-template-mailer) -用于创建AWS SES电子邮件模板+微服务的构造，以使用AWS SES发送模板化电子邮件.
* [cdk-sqs-monitored](https://github.com/kamilbiela/cdk-sqs-monitored) -具有死信队列和已配置警报的SQS构造.

### CI/CD

* [aws-delivlib](https://github.com/awslabs/aws-delivlib) -合成CI / CD管道以交付多语言软件（由CDK本身使用）.
* [cdk-blue-green-container-deployment](https://github.com/cloudcomponents/cdk-constructs/tree/master/packages/cdk-blue-green-container-deployment) -使用CodeDeploy进行蓝色/绿色容器部署.

### Monitoring

* [cdk-watchful](https://github.com/eladb/cdk-watchful) -CDK应用程序的自动仪表板和警报.
* [aws-cdk-billing-alarm](https://github.com/alvyn279/aws-cdk-billing-alarm) -构造用于设置电子邮件警报的金额超过您的AWS账单上的金额.

### Workflows

* [cdk-pull-request-check](https://github.com/cloudcomponents/cdk-components/blob/master/packages/cdk-pull-request-check) -CDK组件，可自动检查拉取请求.
* [cdk-github-webhook](https://github.com/cloudcomponents/cdk-components/blob/master/packages/cdk-github-webhook) -提供GitHub webhooks的CDK组件.
* [cdk-codepipeline-slack](https://github.com/cloudcomponents/cdk-components/blob/master/packages/cdk-codepipeline-slack) - CDK component that provisions a #slack approval workflow.
* [cdk-codecommit-backup](https://github.com/cloudcomponents/cdk-components/tree/master/packages/cdk-codecommit-backup) -将CodeCommit存储库备份到S3.
* [Alexa Deployment Pipeline](https://github.com/taimos/cdk-constructs/tree/master/lib/alexa) -使用AWS SAM和DeployToAlexa操作创建一个CodePipeline来将Alexa Skills部署到Lambda和开发人员控制台的构造.
* [cdk-developer-tools-notifications](https://github.com/cloudcomponents/cdk-constructs/tree/master/packages/cdk-developer-tools-notifications) -开发人员工具的Slack / Microsoft团队/电子邮件通知：CodeCommit，CodeBuild，CodeDeploy，CodePipeline.

### Multi-accounts setup
* [aws-bootstrap-kit](https://github.com/awslabs/aws-bootstrap-kit) -使用AWS Organization，AWS SSO，DNS和AWS CodePipeline创建多账户设置.

## High-Level Frameworks

* [punchcard](https://github.com/punchcard/punchcard) -TypeScript框架，用于统一CDK的基础结构和运行时代码，因此您可以在一个Node.js应用程序的上下文中声明构造并实现运行时逻辑.
* [aws-cdk-pure](https://github.com/fogfish/aws-cdk-pure) -使用AWS CDK开发纯功能和高级云组件的工具包.
* [cdk-stepfunctions-patterns](https://github.com/kolomied/cdk-stepfunctions-patterns) -一组“阶梯功能”高级弹性模式.

## Scaffolding

* [ReactJS + Cognito + CDK Starter](https://github.com/vbudilov/reactjs-cognito-starter) -具有AWS CDK支持的ReactJS + Amazon Cognito + Amazon Amplify Framework的入门项目.
* [cra-template-aws-cdk](https://github.com/luisfarzati/rnbw-aws-cdk/tree/master/packages/cra-template-aws-cdk) -使用AWS CDK开箱即用，简单地配置无服务器React应用程序即可创建React App模板.
* [create-cdk-app](https://github.com/cdk-tools/create-cdk-app) -从模板创建CDK应用程序.
* [awscdk-jsii-template](https://github.com/pahud/awscdk-jsii-template) -GitHub模板存储库，可生成一个就绪的环境来构建，测试和发布您 [JSII](https://github.com/kolomied/awesome-cdk/blob/master/(https://github.com/aws/jsii)）为AWS CDK构建lib.

## Language Support

* [AWS-CDK-Kotlin-DSL](https://github.com/justincase-jp/AWS-CDK-Kotlin-DSL) - A Wrapper library of [AWS CDK Java](https://mvnrepository.com/artifact/software.amazon.awscdk) .  CI自动生成代码，并每天进行部署.
* [aws-cdk-maven-plugin](https://github.com/LinguaRobot/aws-cdk-maven-plugin) -使用Java和Maven定义和部署AWS CDK应用程序的插件.
* [aws-lambda-nodejs-webpack](https://github.com/vvo/aws-lambda-nodejs-webpack) -使用以下替代Node.js lambda CDK构造 [webpack](https://webpack.js.org/).
* [aws-lambda-nodejs-esbuild](https://github.com/floydspace/aws-lambda-nodejs-esbuild) -使用以下替代Node.js lambda CDK构造 [esbuild](https://github.com/evanw/esbuild).

## Library Publishing

* [GitHub Action](https://github.com/marketplace/actions/aws-cdk-action) -适用于AWS CDK的GitHub Action.
* [jsii-publish](https://github.com/udondan/jsii-publish) - 一个 [Docker image](https://hub.docker.com/r/udondan/jsii-publish) 和 [GitHub action](https://github.com/marketplace/actions/jsii-publish) to build 和 publish CDK constructs created via [JSII](https://github.com/aws/jsii).

## Training Materials and Sample Code

* [Official CDK Examples](https://github.com/aws-samples/aws-cdk-examples) -AWS CDK的一组示例项目.
* [CDK Serverless Workshop](https://cdkworkshop.com/) -一个研讨会，指导您完成创建和部署CDK应用程序的过程.
* [Build an App with AWS Cloud Development Kit course on egghead.io](https://egghead.io/courses/build-an-app-with-the-aws-cloud-development-kit?af=6p5abz)
* [Infrastructure is Code with the AWS CDK](https://youtu.be/Lh-kVC2r2AU) -录制re：Invent 2018会议.
* [GitHub Changelog Crawler](https://github.com/aws-samples/aws-cdk-changelogs-demo) -由Nathan Peck编写的功能完善的CDK应用程序，它使用Fargate，API Gateway，Lambda，CloudFront，S3，ElastiCache和Dynamodb.
* [ECS with CI/CD](https://github.com/rix0rrr/cdk-ecs-demo) -使用CDK部署ECS应用程序的演示.
* [Example templates for aws cdk](https://github.com/tecracer/cdk-templates) -来自多个AWS项目的有效TypeScript代码片段.
* [Lambda packaging asset](https://gitlab.com/josef.stach/aws-cdk-lambda-asset) -CDK资产，可构建lambda函数并生成具有相关性的ZIP文件.
* [Open CDK Guide](https://github.com/kevinslin/open-cdk) -关于CDK和最佳做法的开源指南.
* [Colorteller Example](https://github.com/denmat/colorteller-aws-cdk) -使用Fargate和Appmesh的出色示例项目.
* [CDK Patterns](https://github.com/cdk-patterns/serverless) -使用CDK构建的无服务器架构模式的开源集合.
* [Create a CI/CD pipeline using CodePipeline and CodeBuild](https://sbstjn.com/deploy-react-cra-with-cdk-codepipeline-and-codebuild.html) - [cra-pipeline](https://github.com/sbstjn/cra-pipeline) GitHub上的项目显示了带有AWS CodeBuild的AWS CodePipeline，用于部署静态React应用程序.
* [React SPA with server-side rendering on AWS Lambda](https://sbstjn.com/serverless-create-react-app-server-side-rendering-ssr-lamda.html) - [cra-serverless](https://github.com/sbstjn/cra-serverless) 项目是一种无服务器架构，可向使用以下命令创建的React网站添加预渲染 [create-react-app](https://create-react-app.dev).
* [Mini Tutorial: Setup AWS Lambda + ACM + API Gateway with AWS Cloud Development Kit](https://github.com/shaftoe/api-gateway-lambda-cdk-example) -部署接收HTML表单（例如/contact_us.html）POST请求的功能性公共API，并将其数据传递给Pushover通知服务.
* [Example of REST API built with CDK](https://github.com/shaftoe/api-l3x-in) -通过https://api.l3x.in/提供支持REST API的源代码.
* [dilbert-feed](https://github.com/mlafeldt/dilbert-feed) -用Go语言编写的无服务器应用程序，使您无需任何广告即可在RSS feed阅读器中欣赏Dilbert.
* [django-postgres-vue-gitlab-ecs](https://gitlab.com/verbose-equals-true/django-postgres-vue-gitlab-ecs) -使用GitLab CI与CDK一起部署的示例Django + Vue.js Web应用程序.
* [nextjs-vercel-aws-cdk-example](https://github.com/vvo/nextjs-vercel-aws-cdk-example) -一个PostgreSQL（RDS），EventBridge（crons）和SNS（后台作业）示例以及Next.js应用程序.

## Blog Posts & Talks

* [Introduction to how and why CDK](https://www.slideshare.net/ranguard/aws-cdk-introduction-191140240) -Leo Lapworth.
* [How to Build a CDK Construct Library](https://garbe.io/blog/2019/03/26/construct-your-own-cdk-construct-library/) -菲利普·加伯（Philipp Garbe）.
* [CDK All The Things: A Whirlwind Tour](https://kevinslin.com/aws/cdk_all_the_things/) -凯文·林（Kevin S Lin）.
* [AWS CDK Developer Preview Announcement](https://aws.amazon.com/blogs/developer/aws-cdk-developer-preview/) -首个AWS CDK开发人员预览版于2018年8月27日发布.
* [Contributing to the AWS Cloud Development Kit](https://aws.amazon.com/blogs/developer/contributing-to-the-aws-cloud-development-kit/) -来自Intuit的Mike Cowgill.
* [First look into AWS Cloud Development Kit](https://garbe.io/blog/2018/08/17/first-look-into-cdk/) -菲利普·加伯（Philipp Garbe）.
* [Boost your AWS Infrastructure with the CDK](https://www.slideshare.net/philippgarbe/boost-your-aws-infrastructure-with-cdk) -Philipp Garbe的SlideShare.
* [Getting started with AWS CDK for Amazon ECS](https://aws.amazon.com/blogs/compute/getting-started-with-the-aws-cloud-development-kit-for-amazon-ecs/) -内森·派克（Nathan Peck）.
* [AWS re:Invent 2018, best of show: CDK](https://medium.com/allermedia-techblog/aws-re-invent-2018-best-of-show-cloud-development-kit-cdk-ad1755561ade) -所有媒体技术博客.
* [AWS Cloud Development Kit introduction with Live Demos](https://youtu.be/IIiIoMGTJec) -AWS用户组芬兰聚会2019年1月.
* [AWS CDK — a glimpse into the future](https://medium.com/nordcloud-engineering/aws-cdk-a-glimpse-into-the-future-90db660f8a89) -由Nordcloud Engineering提供.
* [AWS Infrastructure as Code with CDK](https://medium.com/avmconsulting-blog/aws-infrastructure-as-code-with-cdk-1d6fa013ce7d) -罗斯·罗兹（Ross Rhodes）.
* [Callbacks with AWS Step Functions](https://medium.com/swlh/callbacks-with-aws-step-functions-a3dde1bc7203) -罗斯·罗兹（Ross Rhodes）.
* [Using the CDK for CodePipelines Setup](https://www.stefreitag.de/wp/2019/03/07/using-aws-cdk-for-code-pipeline-setup/) -斯蒂芬·星期五.
* [Using the CDK for AWS MSK Setup](https://www.stefreitag.de/wp/2019/08/31/paths-are-made-by-walking-or-how-aws-cdk-and-msk-work-together/) -斯蒂芬·星期五.
* [Serverless Dotnet - E01: Intro to AWS CDK](https://youtu.be/c9UXHPX6-Ns) -杰克·斯科特（Jake Scott）.
* [GitHub repository](https://github.com/jakejscott/aws-cdk-phone-verify-api) -杰克·斯科特（Jake Scott）.
* [Infrastructure is Code with the AWS CDK](https://youtu.be/ZWCvNFUN-sU) -AWS Tech Talk网络研讨会.
* [tecRacer Amazon AWS Blog](https://aws-blog.de/tags/cdk.html) -Gernot Glawe的aws-blog.de上的几篇博客文章.
* [Using CDK to build a UDP NLB Logging Service](https://youtu.be/dXTEVp0ATzo) -由ClouderDex提供.
* [GitHub Repo](https://github.com/ClouderDex/CDK-UDP-NLB-Demo) -由ClouderDex提供.
* [Purely Functional Cloud Components with AWS CDK](https://i.am.fog.fish/2019/08/23/purely-functional-cloud-with-aws-cdk.html) -这是雾鱼.
* [Using the CDK to probe multiple accounts (sfn/lambda/sqs/sechub)](https://fudless.xyz/aws/seedecay/) -来自的博客文章 [fudless.xyz](https://fudless.xyz).
* [Scheduled Lambda Functions and CI/CD pipeline with AWS CDK](https://medium.com/hatchsoftware/using-the-aws-cdk-to-build-scheduled-lambda-functions-13eb1674586e) -马丁·特伦（Maarten Thoelen）.
* [GitHub Repo](https://github.com/HatchSoftware/automatic-aws-db-shutdown-cdk) -马丁·特伦（Maarten Thoelen）.
* [AWS Client VPN with mutual TLS](https://lanwen.ru/posts/aws-client-vpn/) -Kirill Merkushev.
* [CDK Step Functions](https://dev.to/elthrasher/exploring-aws-cdk-step-functions-1d1e) -马特·摩根（Matt Morgan）.
* [Loading DynamoDB with Custom Resources](https://dev.to/elthrasher/exploring-aws-cdk-loading-dynamodb-with-custom-resources-jlf) -马特·摩根（Matt Morgan）.
* [Loading DynamoDB with Provider Framework](https://dev.to/elthrasher/exploring-aws-cdk-a-million-a-minute-dynamodb-and-providerframework-e92) -马特·摩根（Matt Morgan）.
* [German: React SPA und server-side rendering (SSR) mit AWS Lambda und CloudFront](https://superluminar.io/2020/02/07/react-spa-und-server-side-rendering-ssr-mit-aws-lambda-cloudfront-und-dem-cdk/) -由superluminar GmbH生产.
* [Introducing AWS CDK with a real life Lambda and API gateway example](https://a.l3x.in/2020/02/04/migrating-from-terraform-to-cdk.html) -亚历山大·福汀（Alexander Fortin）.
* [CloudWatch Dashboards as Code (the Right Way) Using AWS CDK](https://medium.com/poka-techblog/cloudwatch-dashboards-as-code-the-right-way-using-aws-cdk-1453309c5481) -西蒙·皮埃尔·金格拉斯（Simon-Pierre Gingras）.
* [Coding the Jamstack missing parts: databases, crons & background jobs](https://dev.to/vvo/coding-the-jamstack-missing-parts-databases-crons-background-jobs-1bpj) -文森特·沃耶（Vincent Voyer）.
* [AWS CDK Continuous Integration and Delivery Using Travis CI](https://medium.com/better-programming/aws-cdk-continuous-integration-and-delivery-using-travis-ci-ee5dd7549434) -Thomas Poignant.
* [Custom Resources with AWS CDK](https://medium.com/cyberark-engineering/custom-resources-with-aws-cdk-d9a8fad6b673?source=friends_link&sk=549fcf9d998bbea304bdd8d834aca9e6) -罗伊·本·约瑟夫（Roy Ben-Yosef）.

## Related Projects

* [jsii](https://github.com/awslabs/jsii) -JavaScript互操作界面，CDK用于创建语言绑定的技术（当前支持.NET，Java和Python）.
* [cdk8s](https://github.com/awslabs/cdk8s/) -使用面向对象的编程定义Kubernetes本地应用程序和抽象.
* [cdktf](https://github.com/hashicorp/terraform-cdk) -使用编程结构定义基础结构资源，并使用HashiCorp Terraform进行配置.

## Tips & Tricks

* [Reflect on the CDK Type System](https://gist.github.com/eladb/68a009cf9c953b04a637bac5c40afdbc) -探索CDK的类型系统.
* [Testing Your Construct Library CodeBuild Configuration Locally](https://github.com/aws/aws-codebuild-docker-images/tree/master/local_builds) -使用jsii / superchain：latest Docker镜像.

## Contributing

欢迎捐款！ 阅读 [contribution guidelines](https://github.com/kolomied/awesome-cdk/blob/master/contributing.md) 第一.
