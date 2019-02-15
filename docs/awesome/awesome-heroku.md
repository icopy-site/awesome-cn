<div class="github-widget" data-repo="ianstormtaylor/awesome-heroku"></div>

![](https://raw.githubusercontent.com/ianstormtaylor/awesome-heroku/master/images/banner.png)

<p align="center">
  <a href="https://github.com/sindresorhus/awesome">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" />
  </a>
</p>

有用的Heroku资源的精选列表.




Heroku的分析......

- `工具` [Metabase](http://www.metabase.com/docs/v0.13.3/operations-guide/running-metabase-on-heroku.html) - 作为可以直接部署到Heroku的应用程序的元数据测试版.



如何构建您的Heroku项目......

- “文章” [Exploring Microservices Architecure on Heroku](http://blog.codeship.com/exploring-microservices-architecture-on-heroku/) - 探讨为什么Heroku消除了在使用微服务时需要担心的大量工具.
- “文章” [Heroku and SOA](https://www.rdegges.com/2014/heroku-and-soa/) - 讨论为什么Heroku非常适合为您的项目构建面向服务的体系结构.



互联网上经常（或专门）写关于Heroku的博客......

- `博客` [Heroku Blog](https://blog.heroku.com) - 官方Heroku博客.



有助于在Heroku上部署的资源......

- “官方” [Preboot](https://devcenter.heroku.com/articles/preboot) - 解释了如何使用“预引导”功能来启用零停机部署，这可能很难实现.
- “文章” [Automating our Heroku deployments from Jenkins](https://www.paulfurley.com/automating-heroku-deployments-from-jenkins/) - 解释如何自动执行部署的某些部分，例如启用维护模式，将数据库从生产复制到暂存，运行迁移以进行分段等.
- “问题” [How do you ignore files when deploying to Heroku?](http://stackoverflow.com/questions/12523435/how-do-i-ignore-folders-and-files-when-pushing-to-heroku-with-a-rails-app) - 关于`.gitignore`这个功能的常见问题的答案.
- “文章” [Six Tips for Mastering your Procfile](https://medium.com/@adam_41691/six-tips-for-mastering-your-procfile-64ea1207b779) - 改进运行Heroku流程的方法.



- “官方” [Managing Multiple Environments for an App](https://devcenter.heroku.com/articles/multiple-environments) - 关于如何考虑管理每个环境的不同部分的良好入门读物.



在Heroku上使用自定义域名的提示...

- “文章” [Configuring CloudFlare DNS for a Heroku app](http://www.higherorderheroku.com/articles/cloudflare-dns-heroku/) - 演示如何使用CloudFlare作为DNS提供商.
- “文章” [Hosting multiple Heroku apps on a single domain](https://pilot.co/blog/hosting-multiple-heroku-apps-on-a-single-domain/) - 有关如何在多个Heroku应用程序之间共享同一域的文章.
- “问题” [How do you host multiple Heroku apps on a single domain?](http://stackoverflow.com/questions/19119164/multiple-heroku-apps-on-a-single-domain) -  StackOverflow问题，对如何从不同路径而不是子域提供多个Heroku应用程序的常见问题做出一些回应.



关于Heroku的许多不同内容的一般资源......

- `书` [The Heroku Hacker's Guide](http://www.theherokuhackersguide.com/) - 一本电子书，涵盖了在Heroku上维护和扩展项目的许多基础知识.
- `书` [Heroku Cookbook](http://www.amazon.com/Heroku-Cookbook-Mike-Coutermarsh/dp/1782177949) - 逐步配方，以解决在Heroku上管理和扩展实际生产Web应用程序的挑战.



有关公司本身的信息......

- “官方” [The big kickoff](https://blog.heroku.com/archives/2007/10/30/the_big_kickoff) - 有史以来第一篇Heroku博客文章.
- “文章” [Heroku isn't for idiots](https://www.rdegges.com/2012/heroku-isnt-for-idiots/) - 解释Heroku的优势以及为什么它不仅仅用于辅助项目.
- “文章” [My Heroku values](https://brandur.org/heroku-values) - 来自的一系列外卖 [Brandur Leach](https://twitter.com/brandur) 当他离开Heroku时.
- “说话” [Buildpack Adventure](http://buildpack-adventure.herokuapp.com/) - 关于Heroku的buildpacks的酷炫幻灯片，以及开源社区与他们一起攻击的内容.



处理的任何事情 [Heroku Postgres](https://www.heroku.com/postgres)...

- “官方” [Heroku Postgres](https://www.heroku.com/postgres) - 用它解释的登陆页面是.
- `插件&#39; [heroku-buildpack-pgbouncer](https://github.com/heroku/heroku-buildpack-pgbouncer) - 允许使用事务池的buildpack [`stunnel`](https://www.stunnel.org/index.html) 和 [`pgbouncer`](https://wiki.postgresql.org/wiki/PgBouncer) 避免达到连接限制.



处理的任何事情 [Heroku Redis](https://elements.heroku.com/addons/heroku-redis)...



帮助您扩展Heroku项目的资源......

- `工具` [HireFire](https://www.hirefire.io/) -  SaaS工具，可根据负载需求自动调整Heroku dynos.



如何保护您的Heroku应用程序......

- “文章” [Set up CloudFlare's free SSL on Heroku](https://robots.thoughtbot.com/set-up-cloudflare-free-ssl-on-heroku) - 引导您完成通过Cloudflare设置免费SSL的确切步骤.



有用的资源 [Heroku Toolbelt](https://toolbelt.heroku.com/)...

- “官方” [Toolbelt Download](https://toolbelt.heroku.com/) - 在哪里下载Heroku工具带.
- `插件&#39; [heroku-accounts](https://github.com/ddollar/heroku-accounts) - 通过命令行可以轻松地同时使用多个帐户.
- `插件&#39; [heroku-pg-extras](https://github.com/heroku/heroku-pg-extras)   - 一个工具带插件，为Postgres添加额外有用的插件.  分析缓存命中率，异常值查询，未使用的索引，表大小等等.



如果您出于某种原因决定迁移Heroku，请检查一下......

- `工具` [dokku](http://dokku.viewdocs.io/dokku/) - 基于Docker的自托管，Heroku兼容平台.



[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Ian Storm Taylor](http://ianstormtaylor.com) 已放弃对此作品的所有版权及相关或相邻权利.
