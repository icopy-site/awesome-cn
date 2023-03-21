<div class="github-widget" data-repo="ianstormtaylor/awesome-heroku"></div>

![](https://raw.githubusercontent.com/ianstormtaylor/awesome-heroku/master/images/banner.png)

<p align="center">
  <a href="https://github.com/sindresorhus/awesome">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" />
  </a>
</p>

有用的 Heroku 资源的精选列表.




Heroku 分析...

-`工具` [Metabase](http://www.metabase.com/docs/v0.13.3/operations-guide/running-metabase-on-heroku.html) — 元数据的测试版作为可以直接部署到 Heroku 的应用程序.



如何构建您的 Heroku 项目...

-`文章` [Exploring Microservices Architecure on Heroku](http://blog.codeship.com/exploring-microservices-architecture-on-heroku/) — 探索为什么 Heroku 消除了您在使用微服务时需要担心的许多工具.
-`文章` [Heroku and SOA](https://www.rdegges.com/2014/heroku-and-soa/) — 讨论了为什么 Heroku 非常适合为您的项目构建面向服务的架构.
-`文章` [Split Frontend from Backend on Heroku with npm and NodeJS](https://medium.com/@spygi/scalable-cost-effective-web-architectures-for-heroku-eb8f1f55a4b6) - 使用 npm 和 NodeJS 在 Heroku 中部署微服务 Web 应用程序的实践指南.



互联网上经常（或专门）写关于 Heroku 的博客......

-`博客` [Heroku Blog](https://blog.heroku.com) — 官方 Heroku 博客.



有助于在 Heroku 上部署的资源...

-`官方` [Preboot](https://devcenter.heroku.com/articles/preboot) — 解释了如何使用“Preboot”功能来实现零停机部署，这可能很难做到正确.
-`文章` [Automating our Heroku deployments from Jenkins](https://www.paulfurley.com/automating-heroku-deployments-from-jenkins/) — 解释您将如何自动化部署的某些部分，例如启用维护模式、将数据库从生产复制到暂存、针对暂存运行迁移等.
-`问题` [How do you ignore files when deploying to Heroku?](http://stackoverflow.com/questions/12523435/how-do-i-ignore-folders-and-files-when-pushing-to-heroku-with-a-rails-app) — 关于 .gitignore 之类功能的常见问题的答案.
-`文章` [Six Tips for Mastering your Procfile](https://medium.com/@adam_41691/six-tips-for-mastering-your-procfile-64ea1207b779) — 改进您运行 Heroku 进程的方式.
-`文章` [Deploying Django to Heroku With Docker](https://testdriven.io/blog/deploying-django-to-heroku-with-docker/) — 查看如何通过 Heroku 容器运行时使用 Docker 将 Django 应用程序部署到 Heroku



-`官方` [Managing Multiple Environments for an App](https://devcenter.heroku.com/articles/multiple-environments) — 关于如何考虑管理每个环境的不同部分的良好入门.



在 Heroku 上使用自定义域名的提示...

-`文章` [Configuring CloudFlare DNS for a Heroku app](http://www.higherorderheroku.com/articles/cloudflare-dns-heroku/) — 演练如何使用 CloudFlare 作为您的 DNS 提供商.
-`文章` [Hosting multiple Heroku apps on a single domain](https://pilot.co/blog/hosting-multiple-heroku-apps-on-a-single-domain/) — 一篇关于如何在多个 Heroku 应用程序之间共享同一个域的文章.
-`问题` [How do you host multiple Heroku apps on a single domain?](http://stackoverflow.com/questions/19119164/multiple-heroku-apps-on-a-single-domain) — 一个 StackOverflow 问题，其中包含对如何从不同路径而不是子域提供多个 Heroku 应用程序的常见问题的一些回答.



涵盖 Heroku 很多不同方面的一般资源......

-`书` [The Heroku Hacker's Guide](http://www.theherokuhackersguide.com/) — 一本电子书，涵盖了在 Heroku 上维护和扩展项目的许多基础知识.
-`书` [Heroku Cookbook](http://www.amazon.com/Heroku-Cookbook-Mike-Coutermarsh/dp/1782177949) — 分步解决在 Heroku 上管理和扩展真实世界生产 Web 应用程序的挑战.



关于公司本身的信息...

-`官方` [The big kickoff](https://blog.heroku.com/archives/2007/10/30/the_big_kickoff) — 有史以来第一篇 Heroku 博客文章.
-`文章` [Heroku isn't for idiots](https://www.rdegges.com/2012/heroku-isnt-for-idiots/) — 解释了 Heroku 的优势以及为什么它不仅仅适用于副项目.
-`文章` [My Heroku values](https://brandur.org/heroku-values) - 来自的一系列精彩内容 [Brandur Leach](https://twitter.com/brandur) 当他离开 Heroku 时.
- `谈话` [Buildpack Adventure](http://buildpack-adventure.herokuapp.com/) — 关于 Heroku 的 buildpack 的精彩幻灯片，以及开源社区正在与他们一起破解的内容.



任何处理 [Heroku Postgres](https://www.heroku.com/postgres)...

-`官方` [Heroku Postgres](https://www.heroku.com/postgres) - 用它解释的着陆页是.
-`插件` [heroku-buildpack-pgbouncer](https://github.com/heroku/heroku-buildpack-pgbouncer) — 一个允许使用事务池的 buildpack [`stunnel`](https://www.stunnel.org/index.html) 和 [`pgbouncer`](https://wiki.postgresql.org/wiki/PgBouncer) 以避免达到连接限制.



任何处理 [Heroku Redis](https://elements.heroku.com/addons/heroku-redis)...



帮助您扩展 Heroku 项目的资源...

-`工具` [HireFire](https://www.hirefire.io/) — 一种 SaaS 工具，可根据负载需要自动扩展和缩减 Heroku dynos.



如何保护您的 Heroku 应用程序...

-`文章` [Set up CloudFlare's free SSL on Heroku](https://robots.thoughtbot.com/set-up-cloudflare-free-ssl-on-heroku) — 引导您完成通过 Cloudflare 设置免费 SSL 的具体步骤.



有用的资源 [Heroku Toolbelt](https://toolbelt.heroku.com/)...

-`官方` [Toolbelt Download](https://toolbelt.heroku.com/) — 在哪里下载 Heroku 工具带.
-`插件` [heroku-accounts](https://github.com/ddollar/heroku-accounts) — 可以轻松地从命令行同时处理多个帐户.
-`插件` [heroku-pg-extras](https://github.com/heroku/heroku-pg-extras)  — 一个工具带插件，它添加了额外的有用插件来使用 Postgres. 分析缓存命中率、离群查询、未使用的索引、表大小等.



如果您出于某种原因决定从 Heroku 迁移，需要检查的事项...

-`工具` [dokku](http://dokku.viewdocs.io/dokku/) — 一个自托管的、基于 docker 的、兼容 Heroku 的平台.



[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Ian Storm Taylor](http://ianstormtaylor.com) 已放弃该作品的所有版权和相关或邻接权.
