<div class="github-widget" data-repo="henrikwirth/awesome-wordpress-gatsby"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">
  <br /><br />
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat.svg" /></a>
  <br /><br /><br />
  <a href="https://wordpress.org/"><img width="150" height="150" align="center" src="https://raw.githubusercontent.com/henrikwirth/awesome-wordpress-gatsby/master/media/wordpress-logo.svg?sanitize=true" alt="WordPress"></a>
      <a href="https://www.gatsbyjs.org/"><img width="150" height="150" align="center" src="https://raw.githubusercontent.com/henrikwirth/awesome-wordpress-gatsby/master/media/gatsby-logo.svg?sanitize=true" alt="Gatsby"></a>
  <br /><br />
  <p>
    <b>
      精选的有关WordPress作为无头CMS和Gatsby作为静态站点生成器（SSG）的资源列表.
    </b>
  </p>
  <br />
</div>

 **无头CMS **是仅后端的内容管理系统（CMS）.  其目的是提供内容并使其可以通过API（例如REST或GraphQL）进行访问.

 静态网站生成器（SSG）是一种框架或设置，可帮助您生成静态网站（HTML / CSS / JS）.  数据的来源可以是任何东西，从本地文件（例如文本文件或markdown）到API（例如REST，GraphQL）.

<br />

**为什么要使用盖茨比和WordPress？**

 WordPress是“世界上使用最广泛的CMS”之一，因此许多人已经知道如何使用它.  在性能是关键的环境中，基于PHP的模板的典型前端方法正变得越来越成问题.  已经存在将WordPress用作通过JavaScript进行普通API调用的无头CMS的方法，但是还存在必须向服务器发出请求并根据响应进行呈现的缺点.  这增加了加载时间.  **相反，Gatsby会在编译时预先渲染整个网站**，因此用户会在第一次请求时获得**准备充分的静态网站**，从而使其成为**最佳性能方法之一.  另一个巨大的好处是**安全性**，因为您的WordPress实例可以在任何地方，甚至在本地，也不需要向用户公开.  **因此，静态的Gatsby网站是不可入侵的.**在下面的资源中查找利弊的进一步论据.

<!-- TOC -->
<!-- /TOC -->

## Communities
如果您需要任何帮助，可以使用一些活跃的社区.

**WPGraphQL**
- [Slack Chat](https://wpgql-slack.herokuapp.com/)
- [Spectrum Chat](https://spectrum.chat/wpgraphql)
- [Twitter](https://twitter.com/wpgraphql)

**Gatsby**
- [Discord Chat](https://gatsby.dev/discord)
- [Reddit](https://www.reddit.com/r/gatsbyjs/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/gatsby)


## Articles

文章列表，通常讨论技术堆栈.

-2019.06：[JAMstack上的现代Web开发
]（https://www.netlify.com/oreilly-jamstack/）-O&#39;REILLY发布的Netlify关于JAMStack上的现代Web开发的报告.

## Plugins

使WordPress和Gatsby协同工作的有用插件列表.

### WordPress

- [WPGraphQL](https://github.com/wp-graphql/wp-graphql) - [Documentation](https://docs.wpgraphql.com/) -WPGraphQL将GraphQL的功能带到您的WordPress网站.
- [WPGraphQL for Advanced Custom Fields](https://github.com/wp-graphql/wp-graphql-acf) -将高级自定义字段公开到WPGraphQL架构.
- [WPGraphQL Polylang Extension](https://github.com/valu-digital/wp-graphql-polylang) -使用来自Polylang插件的语言数据扩展WPGraphQL模式.
- [WPGraphQL Gutenberg](https://github.com/pristas-peter/wp-graphql-gutenberg) -将Gutenberg块暴露于WPGraphQL API.
- [WPGraphQL Gutenberg ACF](https://github.com/pristas-peter/wp-graphql-gutenberg-acf) -通过GraphQL公开ACF块
- [WPGraphQL Meta Query](https://github.com/wp-graphql/wp-graphql-meta-query) -将Meta_Query支持添加到WPGraphQL插件以支持postObject查询args.
- [WPGraphQL Tax Query](https://github.com/wp-graphql/wp-graphql-tax-query) -向PostObject查询参数（WP_Query）的WPGraphQL插件添加Tax_Query支持.
- [WPGraphQL JWT Authentication](https://github.com/wp-graphql/wp-graphql-jwt-authentication) -扩展WPGraphQL插件以使用JWT（JSON Web令牌）提供身份验证.
- [WPGraphQL Lock](https://github.com/valu-digital/wp-graphql-lock) -通过实施持久的GraphQL查询，为WPGraphQL启用查询锁定.
- [QL Search](https://github.com/funkhaus/ql-search) -将SearchWP集成到WPGraphQL中的扩展.
- [WPGraphiQL](https://github.com/wp-graphql/wp-graphiql) -使用GraphiQL IDE扩展WordPress仪表板.
- [WP API Menus](https://wordpress.org/plugins/wp-api-menus/) -使用WordPress注册菜单的新路由扩展WordPress JSON REST API.
- [WP JAMstack Deployments](https://github.com/crgeary/wp-jamstack-deployments) -用于Netlify（和其他平台）上的JAMstack部署的WordPress插件.
- [Headless Mode](https://wordpress.org/plugins/headless-mode/)  -无头模式为尝试访问该网站的所有用户设置了重定向.  唯一允许访问的请求是试图访问REST API，WP GraphQL API或希望访问无头安装以编辑或创建帖子的登录用户.


**显而易见的是，上面的一些插件：**

- [Advanced Custom Fields](https://wordpress.org/plugins/advanced-custom-fields/) - [ACF PRO](https://www.advancedcustomfields.com/pro/)
- [Polylang](https://wordpress.org/plugins/polylang/)


### Gatsby

- [gatsby-source-graphql](https://www.gatsbyjs.org/packages/gatsby-source-graphql)
- [gatsby-image](https://www.gatsbyjs.org/packages/gatsby-image)
- [gatsby-source-filesystem](https://www.gatsbyjs.org/packages/gatsby-source-filesystem)
- [gatsby-source-wordpress](https://www.gatsbyjs.org/packages/gatsby-source-wordpress)

## Tutorials

 **注意：**我们区分在Gatsby中使用WordPress的两种方式.  有一个`gatsby-source-wordpress`插件，它基于WP REST API **创建了一个Gatsby-GraphQL模式，还有一个** WPGraphQL **方式，它直接从带有``的GraphQL模式中提取. gatsby-source-graphql`插件.

### Written Tutorials

**General**

- 2018.08: [Headless WordPress + Gatsby + Netlify continuous deployment](https://justinwhall.com/headless-wordpress-gatsby-netlify-continous-deployment/) -通过几个简单的步骤显示如何创建WordPress + Gatsby + Netlify设置的指南.


**WPGraphQL**
- 2019.11: [Guide to Gatsby WordPress Starter Advanced with Previews, i18n and more](https://dev.to/nevernull/overview-guide-to-gatsby-wordpress-starter-advanced-with-previews-i18n-and-more-583l) -一个教程系列，从使用WPGraphQL进行WordPress和Gatsby的基本设置开始，然后深入研究更高级的主题，例如部署，预览，i18n和页面生成器，例如使用ACF flexible cotent字段进行设置.
- 2019.08: [Live Previews with WordPress and Gatsby](https://justinwhall.com/live-previews-with-wordpress-gatsby/) -教程展示了如何使用主题的高阶组件来简化WordPress帖子和自定义帖子类型的预览.
- 2019.08: [Gatsby with WPGraphQL, ACF and Gatbsy-Image](https://dev.to/nevernull/gatsby-with-wpgraphql-acf-and-gatbsy-image-72m) -指南，显示了如何实现gatsby-image，因此可以将其用于WordPress媒体文件.


** WP REST API **
- 2019.09: [Sourcing from WordPress](https://www.gatsbyjs.org/docs/sourcing-from-wordpress/) -本指南将引导您完成将Gatsby与WordPress Rest Api结合使用的过程.
- 2019.07: [Complete guide to WordPress menu sourcing in Gatsby](https://dev.to/boussama/complete-guide-to-wordpress-menu-sourcing-in-gatsby-h76) -本指南说明了如何将WordPress菜单添加到您的Gatsby版本中.
- 2019.04: [How To Build A Blog with WordPress and Gatsby.js](https://dev.to/iam_timsmith/how-to-build-a-blog-with-wordpress-and-gatsby-js-part-1-4f9e) -教程（共3部分），教您如何使用WordPress和Gatsby构建博客.
- 2018.10: [Build a blog with React, WordPress using Gatsby](https://medium.com/@mjadav/build-a-blog-with-react-wordpress-using-gatsby-4cdfb6ce2004) -讲解如何使用Gatsby和WordPress作为数据源的10个步骤创建博客的教程.


### Video Tutorials

**WPGraphQL**
- 2019.11: [30+ Videos - Gatsby + WordPress (2019) Complete Course](https://whatjackhasmade.co.uk/gatsby-wordpress-2019/)  -该系列重点介绍如何将WordPress用作具有GraphQL模式的无头CMS.  设置了WordPress网站和主题之后，我们将转到Gatsby上，以及如何使用新模式为Gatsby网站生成内容，以编程方式生成页面，将Gutenberg块转换为React组件并着重介绍本章.盖茨比的SEO.
- 2019.07: [Gatsby + WordPress with WPGraphQL (with Jason Bahl) — Learn With Jason](https://www.youtube.com/watch?v=DH7I1xRrbxs) -在此流中，Jason Bahl讲授如何将WordPress与Advanced Custom Fields和WPGraphQL一起使用，以创建功能强大，灵活的管理仪表板，然后在Gatsby网站中查询和显示该数据.
- 2019.07: [Crash Course: Headless WordPress with WPGraphQL, ACF, and React](https://www.youtube.com/watch?v=9KGuI0UmpMw) -在此视频中，Alex Young（WPCasts）介绍了如何通过WPGraphQL和React获得简单的无头WordPress设置.
- 2019.06: [Using WordPress with WPGraphQL](https://www.youtube.com/watch?v=aqEfEuVWqws) -在此视频中，您将学习如何使用名为WPGraphQL的超赞插件和GraphQL + Advanced Custom Fields等超酷工具，将GraphQL与WordPress结合使用.
- 2019.04: [WPGraphQL for ACF](https://www.youtube.com/watch?v=rIg4MHc8elg) -Jason Bahl展示了如何将WPGraphQL用于高级自定义字段.
-2018.07：[GraphQL with WordPress and Gutenberg-Jason Bahl-2018 JavaScript for WordPress Conference
]（https://www.youtube.com/watch?v=6CuM1PY9ESQ）-在2018年WordPress的JavaScript会议的演讲中，WP GraphQL插件的开发人员Jason Bahl提供了有关如何使用GraphQL的更新示例. WordPress和古腾堡.


** WP REST API **
- 2018.03: [Gatsby.js + WordPress](https://www.youtube.com/watch?v=etii9yp1J6s) -在这个小型系列中，开发人员尝试使用Gatsby.js和WordPress创建网站.


## Starters
您可以克隆并开始构建的项目启动器列表.

- [Gatsby + WPGraphQL Blog Example](https://github.com/wp-graphql/gatsby-wpgraphql-blog-example) -演示展示如何使用WPGraphQL作为盖茨比站点的源.
- [Gatsby + Headless WordPress + Netlify Starter](https://github.com/justinwhall/gatsby-wordpress-netlify-starter) -用于持续部署到Netlify的Gatsby + WordPress入门工具.
- [Gatsby WordPress Starter Advanced](https://github.com/henrikwirth/gatsby-starter-wordpress-advanced) -先进的Gatsby + WordPress入门程序，它是根据一系列教程构建的，并与ACF灵活的内容字段一起使用以创建内容块/布局.


## Themes
与WordPress配合使用的gatsby主题列表，您可以在Gatsby设置中使用.

- [Twenty Nineteen Gatsby Theme](https://github.com/zgordon/twentynineteen-gatsby-theme) -将二十十九个WordPress主题的端口转移到盖茨比.
-[Gatsby WordPress发布者主题
](https://github.com/staticfuse/gatsby-theme-publisher) - The Gatsby Publisher Theme allows you to create a headless (or decoupled) WordPress site. This theme will display all of your pages and posts in a static front-end built on React and Gatsby.

## Contribute

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/henrikwirth/awesome-wordpress-gatsby/blob/master/contributing.md) 第一.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，Henrik Wirth放弃了所有版权和
相关或邻接权.

<!--- unicorn --->
