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

 **无头CMS **是仅后端的内容管理系统（CMS）. 其目的是提供内容并使其可以通过API（例如REST或GraphQL）进行访问.

静态网站生成器（SSG）是一种框架或设置，可帮助您生成静态网站（HTML / CSS / JS）. 数据的来源可以是任何内容，从本地文件（例如文本文件或markdown）到API（例如REST，GraphQL）.

<br />

**为什么要使用盖茨比和WordPress？**

 WordPress是**世界上使用最广泛的CMS之一，因此许多人已经知道如何使用它. 在性能是关键的环境中，基于PHP的模板的典型前端方法正变得越来越成问题. 已经存在将WordPress用作通过JavaScript进行普通API调用的无头CMS的方法，但是还存在缺点，必须向服务器发出请求并根据响应进行呈现. 这增加了加载时间.  **相反，Gatsby会在编译时预先渲染整个网站**，因此用户会在他们的第一个请求上获得**准备充分的静态网站**，从而使其成为**最佳性能**之一. 另一个巨大的好处是**安全性**，因为您的WordPress实例可以在任何地方，甚至可以在本地，而且您不需要将其公开给用户.  **因此，静态的Gatsby网站是不可入侵的.**在下面的资源中查找利弊的进一步论据.

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


## Articles and Talks

总体上详细介绍技术堆栈的文章和演讲列表.

- 2021.02: [Announcing Gatsby’s New WordPress Integration](https://www.gatsbyjs.com/blog/wordpress-integration)
- 2021.02: [Jason Bahl of WPGraphQL's role in the operating system for the web](https://www.youtube.com/watch?v=Me_A0HBYXx8)
- 2021.02: [Torque News Drop: Jason Bahl and WPGraphQL](https://www.youtube.com/watch?v=8SAdtU8HAwM)
- 2021.02: [Gatsby Launches New WordPress Integration, Expanding Support for Headless Architecture](https://wptavern.com/gatsby-launches-new-wordpress-integration-expanding-support-for-headless-architecture)
- 2020.11: [Announcing WPGraphQL v1.0](https://www.wpgraphql.com/2020/11/16/announcing-wpgraphql-v1/)
- 2020.07: [My Long Journey to a Decoupled WordPress Gatsby Site](https://css-tricks.com/my-long-journey-to-a-decoupled-wordpress-gatsby-site/)
-2019.06：[JAMstack上的现代Web开发
  ]（https://www.netlify.com/oreilly-jamstack/）-由O&#39;REILLY发布的Netlify关于JAMStack上的现代Web开发的报告.


## Plugins

使WordPress和Gatsby协同工作的有用插件列表. 按字母顺序排列.

### WordPress

#### Essential Plugins

- [WPGraphQL](https://github.com/wp-graphql/wp-graphql) - [Documentation](https://docs.wpgraphql.com/) -WPGraphQL将GraphQL的功能带到您的WordPress网站.
- [WPGatsby](https://wordpress.org/plugins/wp-gatsby/) -此插件将您的WordPress网站配置为Gatsby的优化来源.

#### WPGraphQL Extensions

- [WPGraphQL Cors](https://github.com/funkhaus/wp-graphql-cors) -这个来自@ kidunot89和@byfunkhaus的免费插件声称允许通过设置GraphQL将接受的CORS标头来使WPGraphQL的身份验证“正常工作”，这意味着可以接受WordPress默认身份验证cookie.
- [Total Counts for WPGraphQL](https://github.com/builtbycactus/total-counts-for-wp-graphql) -这个来自@builtbycactus的免费插件将WPGraphQL Schema中的连接总数公开.
- [WPGraphQL Gutenberg](https://github.com/pristas-peter/wp-graphql-gutenberg) -将Gutenberg块暴露于WPGraphQL API.
- [WPGraphQL JWT Authentication](https://github.com/wp-graphql/wp-graphql-jwt-authentication) -扩展WPGraphQL插件以使用JWT（JSON Web令牌）提供身份验证.
- [WPGraphQL Lock](https://github.com/valu-digital/wp-graphql-lock) -通过实现持久的GraphQL查询，为WPGraphQL启用查询锁定.
- [WPGraphQL Meta](https://github.com/roborourke/wp-graphql-meta) -这个来自@robertorourke的免费插件将通过WordPress register_meta API注册的meta暴露给WPGraphQL.
- [WPGraphQL Meta Query](https://github.com/wp-graphql/wp-graphql-meta-query) -将Meta_Query支持添加到WPGraphQL插件中，以支持postObject查询args.
- [WPGraphQL Persisted Queries](https://github.com/Quartz/wp-graphql-persisted-queries) -这个来自@qz的免费插件增加了将持久查询与WPGraphQL一起使用的能力.
- [WPGraphQL Offset Pagination](https://github.com/darylldoyle/wp-graphql-offset-pagination) -来自@enshrined的这个免费插件添加了基本的偏移分页，而不是WPGraphQL附带的基于标准Cursor的分页.
- [WPGraphQL Send Email](https://github.com/ashhitch/wp-graphql-send-mail)  -这个来自@Ash_Hitchcock的免费插件可让您通过简单的变体发送电子邮件. 包括将发送限制为可信来源的能力.

---
**与WPGraphQL一起使用其他插件的扩展**

- [QL Search](https://github.com/funkhaus/ql-search) -将SearchWP集成到WPGraphQL中的扩展.
- [WPGraphQL Content Blocks](https://github.com/Quartz/wp-graphql-content-blocks) -这个免费的插件来自QZ.com的人们，提供了一种从WordPress帖子和页面中以“块”（与Gutenberg不相关）查询HTML内容的方法，以使您查询的内容更具结构性.
- [WPGraphQL Enable All Post Types (DalkMania)](https://github.com/DalkMania/wp-graphql-cpt) -这个来自@DalkMania的免费插件会自动将所有已注册的帖子类型添加到WPGraphQL架构中.
- [WPGraphQL Enable All Post Types (TylerBarnes)](https://github.com/TylerBarnes/wp-graphql-enable-all-post-types) -这个来自@tylbar的免费插件会自动将所有注册的帖子类型添加到WPGraphQL架构中.
- [WPGraphQL Google Schema](https://github.com/izzygld/wp-graphql-google-schema) -这个来自@ izzygld261的免费插件将Google Schema支持添加到WPGraphQL.
- [WPGraphQL Gutenberg ACF](https://github.com/pristas-peter/wp-graphql-gutenberg-acf) -通过GraphQL公开ACF块
- [WPGraphQL MB (MetaBox)](https://github.com/DalkMania/wp-graphql-mb) -来自@DalkMania的免费插件可使用以下方式添加所有已注册的metabox [metabox.io](https://metabox.io/) WPGraphQL模式.
- [WPGraphQL MetaBox Relationships](https://github.com/hsimah-services/wp-graphql-mb-relationships) -来自@hsimah的免费插件增加了对 [metabox.io](https://metabox.io/) 到WPGraphQL的“关系”字段（当还使用他的wp-graphql-metabox插件时）.
- [WPGraphQL Polls](https://github.com/andrenoberto/wp-graphql-polls) -这个来自@andrenosouza的免费插件，使您可以通过GraphQL查询和变异与WP-Polls插件中的数据进行交互.
- [WPGraphQL Polylang Extension](https://github.com/valu-digital/wp-graphql-polylang) -使用来自Polylang插件的语言数据扩展WPGraphQL模式.
- [WPGraphQL Tax Query](https://github.com/wp-graphql/wp-graphql-tax-query) -为PostObject查询参数（WP_Query）的WPGraphQL插件增加了Tax_Query支持.
- [WPGraphQL WPML](https://github.com/rburgst/wp-graphql-wpml)  -这个来自@rburgst的免费插件使用来自WPML插件的语言数据扩展了WPGraphQL模式. 另外，它关闭WPML默认过滤器，以便能够遍历所有帖子，无论使用哪种语言.
- [WPGraphQL for Advanced Custom Fields](https://github.com/wp-graphql/wp-graphql-acf) -将高级自定义字段公开到WPGraphQL架构.
- [WPGraphQL for BuddyPress](https://github.com/wp-graphql/wp-graphql-buddypress) -这个来自@RenatoNascAlves的免费插件将BuddyPress数据公开到WPGraphQL.
- [WPGraphQL for Carbon Fields](https://github.com/matepaiva/wp-graphql-crb) -这个来自@matepaiva的免费插件将使用Carbon Fields注册的字段暴露给WPGraphQL Schema.
- [WPGraphQL for Custom Post Type UI](https://github.com/wp-graphql/wp-graphql-custom-post-type-ui) -这个免费的插件将设置添加到“自定义帖子类型” UI中，使您可以设置CPTUI注册的哪些帖子类型和分类法应显示在WPGraphQL架构中.
- [WPGraphQL for FacetWP](https://github.com/hsimah-services/wp-graphql-facetwp) -这个来自@hsimah的免费插件公开了WPGraphQL查询的过滤器，以允许使用FacetWP进行多面搜索.
- [WPGraphQL for Gravity Forms](https://github.com/harness-software/wp-graphql-gravity-forms) -这个来自@harness_up的@KellenMace的免费插件将@gravityforms数据公开给WPGraphQL，使您可以查询表单，字段，条目等.
- [WPGraphQL for Metabox](https://github.com/hsimah-services/wp-graphql-metabox) - This FREE plugin from @hsimah exposes fields registered using the popular http://MetaBox.io to the WPGraphQL Schema.
- [WPGraphQL for Ninja Forms](https://github.com/toriphes/wp-graphql-ninja-forms) -这个免费的插件将Ninja Forms插件创建的表单暴露给WPGraphQL Schema，并允许通过GraphQL Mutations提交表单.
- [WPGraphQL for Posts 2 Posts](https://github.com/harness-software/wp-graphql-posts-to-posts) -这个来自@harness_up的@KellenMace的免费插件会自动为您的所有Posts 2 Posts连接创建GraphQL连接.
- [WPGraphQL for SEOPress](https://github.com/ashhitch/wp-graphql-yoast-seo) -这个来自@moon_meister的免费插件将SEOPress管理的数据公开到WPGraphQL架构，从而允许SEO数据用于无头的应用程序.
- [WPGraphQL for WooCommerce](https://github.com/wp-graphql/wp-graphql-woocommerce) -这个免费的插件将WooCommerce数据公开给WPGraphQL，使您可以通过GraphQL查询和变异与商店的数据进行交互.
- [WPGraphQl Yoast SEO Plugin](https://github.com/ashhitch/wp-graphql-yoast-seo) -将Yoast SEO数据公开到WPGraphQL插件.


#### Other helpful Plugins

- [Advanced Custom Fields](https://wordpress.org/plugins/advanced-custom-fields/) - [ACF PRO](https://www.advancedcustomfields.com/pro/)
- [Headless Mode](https://wordpress.org/plugins/headless-mode/)  -无头模式为尝试访问该网站的所有用户设置了重定向. 唯一允许访问的请求是尝试访问REST API，WP GraphQL API或希望访问无头安装以编辑或创建帖子的登录用户.
- [Polylang](https://wordpress.org/plugins/polylang/)
- [WP JAMstack Deployments](https://github.com/crgeary/wp-jamstack-deployments) -用于Netlify（和其他平台）上的JAMstack部署的WordPress插件.


### Gatsby Plugins

- [gatsby-image](https://www.gatsbyjs.org/packages/gatsby-image)
- [gatsby-source-filesystem](https://www.gatsbyjs.org/packages/gatsby-source-filesystem)
- [gatsby-source-wordpress](https://www.gatsbyjs.org/packages/gatsby-source-wordpress)


## Free Tutorials / Courses

**注意：**自从gatsby-source-wordpress V4发行以来，它比gatsby-source-graphql更受青睐，因此，我将只列出与该方法有关的教程.


### Written Tutorials

- 2019.11: [Guide to Gatsby WordPress Starter Advanced with Previews, i18n and more](https://dev.to/nevernull/overview-guide-to-gatsby-wordpress-starter-advanced-with-previews-i18n-and-more-583l) -一个教程系列，从使用WPGraphQL进行WordPress和Gatsby的基本设置开始，然后深入研究更高级的主题，例如部署，预览，i18n和页面生成器，例如使用ACF flexible cotent字段进行设置.
- 2019.08: [Live Previews with WordPress and Gatsby](https://justinwhall.com/live-previews-with-wordpress-gatsby/) -教程展示了如何使用主题的高阶组件来简化WordPress帖子和自定义帖子类型的预览.
- 2019.08: [Gatsby with WPGraphQL, ACF and Gatbsy-Image](https://dev.to/nevernull/gatsby-with-wpgraphql-acf-and-gatbsy-image-72m) -指南，显示了如何实现gatsby-image，因此可以将其用于WordPress媒体文件.
- 2018.08: [Headless WordPress + Gatsby + Netlify continuous deployment](https://justinwhall.com/headless-wordpress-gatsby-netlify-continous-deployment/) -通过几个简单的步骤显示如何创建WordPress + Gatsby + Netlify设置的指南.


### Video Tutorials

- 2019.11: [25+ Videos - Gatsby + WordPress (2019) Complete Course](https://whatjackhasmade.co.uk/series/gatsby-wordpress-2019/)  -该系列重点介绍如何将WordPress用作具有GraphQL模式的无头CMS. 在设置了WordPress网站和主题之后，我们将转到Gatsby上，以及如何使用新模式为Gatsby网站生成内容，以编程方式生成页面，将Gutenberg块转换为React组件并以本章为重点结束本章.盖茨比的SEO.
- 2019.07: [Gatsby + WordPress with WPGraphQL (with Jason Bahl) — Learn With Jason](https://www.youtube.com/watch?v=DH7I1xRrbxs) -在此流中，Jason Bahl教授如何将WordPress与Advanced Custom Fields和WPGraphQL一起使用，以创建功能强大，灵活的管理仪表板，然后在Gatsby站点中查询和显示该数据.
- 2019.07: [Crash Course: Headless WordPress with WPGraphQL, ACF, and React](https://www.youtube.com/watch?v=9KGuI0UmpMw) -在此视频中，Alex Young（WPCasts）介绍了如何使用WPGraphQL和React获得简单的无头WordPress设置.
- 2019.06: [Using WordPress with WPGraphQL](https://www.youtube.com/watch?v=aqEfEuVWqws) -在本视频中，您将学习如何使用名为WPGraphQL的超赞插件以及诸如GraphQL + Advanced Custom Fields之类的一些超酷功能，将GraphQL与WordPress结合使用.
- 2019.04: [WPGraphQL for ACF](https://www.youtube.com/watch?v=rIg4MHc8elg) -Jason Bahl展示了如何将WPGraphQL用于高级自定义字段.
-2018.07：[GraphQL with WordPress and Gutenberg-Jason Bahl-2018 JavaScript for WordPress Conference
]（https://www.youtube.com/watch?v=6CuM1PY9ESQ）-在2018年WordPress JavaScript大会上的演讲中，WP GraphQL插件的开发人员Jason Bahl提供了有关如何使用GraphQL的更新示例. WordPress和古腾堡.


## Paid Tutorials / Courses
付费课程列表.

- 2021.01: [Building a Headless WordPress Site with Gatsby](https://www.linkedin.com/learning/building-a-headless-wordpress-site-with-gatsby) -本课程是逐步使用gatsby-source-wordpress插件来创建具有帖子，页面，类别，标签，帖子导航和其他功能的功能全面的无头WordPress盖茨比WordPress网站的分步指南.


## Starters
您可以克隆并开始构建的项目启动器列表.

- [Gatsby Starter - WordPress Twenty Twenty](https://github.com/henrikwirth/gatsby-starter-wordpress-twenty-twenty) -使用新的gatsby-source-wordpress @ v4将WordPress二十二十主题移植到盖茨比.
- [Gatsby + WPGraphQL Blog Example](https://github.com/wp-graphql/gatsby-wpgraphql-blog-example) -演示显示如何使用WPGraphQL作为盖茨比站点的源.
- [Gatsby + Headless WordPress + Netlify Starter](https://github.com/justinwhall/gatsby-wordpress-netlify-starter) -用于持续部署到Netlify的Gatsby + WordPress入门工具.
- [Gatsby WordPress Starter Advanced](https://github.com/henrikwirth/gatsby-starter-wordpress-advanced) -先进的Gatsby + WordPress入门程序，它是根据一系列教程构建的，并与ACF灵活的内容字段一起使用以创建内容块/布局.
- [Gatsby Starter Blog](https://github.com/zeevo/gatsby-starter-wordpress-blog) -具有足够功能的博客启动器，可以立即投入生产.

## Themes
与WordPress配合使用的gatsby主题列表，您可以在Gatsby设置中使用.

- [Twenty Nineteen Gatsby Theme](https://github.com/zgordon/twentynineteen-gatsby-theme) -将二十十九个WordPress主题的端口转移到盖茨比.
-[Gatsby WordPress发布者主题
 ]（https://github.com/staticfuse/gatsby-theme-publisher）-Gatsby Publisher主题允许您创建无头（或解耦）的WordPress网站. 这个主题将在基于React和Gatsby的静态前端中显示您的所有页面和帖子.


## Contribute

欢迎捐款！ 阅读 [contribution guidelines](https://github.com/henrikwirth/awesome-wordpress-gatsby/blob/master/contributing.md) 第一的.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，Henrik Wirth放弃了所有版权和
相关或邻接权.

<!--- unicorn --->
