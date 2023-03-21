<div class="github-widget" data-repo="henrikwirth/awesome-wordpress-gatsby"></div>
<div align="center">
  <br /><br />
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat.svg" /></a>
  <br /><br /><br />
  <a href="https://wordpress.org/"><img width="150" height="150" align="center" src="https://raw.githubusercontent.com/henrikwirth/awesome-wordpress-gatsby/master/media/wordpress-logo.svg?sanitize=true" alt="WordPress"></a>
      <a href="https://www.gatsbyjs.org/"><img width="150" height="150" align="center" src="https://raw.githubusercontent.com/henrikwirth/awesome-wordpress-gatsby/master/media/gatsby-logo.svg?sanitize=true" alt="Gatsby"></a>
  <br /><br />
  <p>
    <b>
      关于 WordPress 作为无头 CMS 和 Gatsby 作为静态站点生成器 (SSG) 的精选资源列表.
    </b>
  </p>
  <br />
</div>

 **无头 CMS** 是仅后端内容管理系统 (CMS). 它的目的是提供内容并使其可通过 API（例如 REST 或 GraphQL）访问.

 **静态站点生成器 (SSG)** 是一个框架或设置，可帮助您生成静态网站 (HTML/CSS/JS). 您的数据源可以是本地文件（例如文本文件或降价文件）到 API（例如 REST、GraphQL）的任何内容.

<br />

**为什么选择 Gatsby 和 WordPress？**

 WordPress 是**世界上使用最广泛的 CMS 之一**，因此许多人已经知道如何使用它. 使用基于 PHP 的模板的典型前端方法在性能至关重要的环境中变得越来越有问题. 将 WordPress 用作通过 JavaScript 进行普通 API 调用的无头 CMS 的方法已经存在，但也有必须向服务器发出请求并根据响应进行呈现的缺点. 这会增加加载时间.  **Gatsby 相反，在编译时预呈现整个站点**，因此用户在他们的第一个请求中得到一个**完全准备好的静态站点**，使其成为**最佳性能方法之一**. 另一个巨大的好处是**安全**，因为您的 WordPress 实例可以在任何地方，甚至在本地，您不需要向用户公开任何实例.  **因此，静态 Gatsby 站点是不可破解的.**在下面的资源中找到更多关于优缺点的论据.

<!-- TOC -->
<!-- /TOC -->

## Communities
如果您需要任何帮助，可以使用一些非常活跃的社区.

**WPGraphQL**
- [Slack Chat](https://wpgql-slack.herokuapp.com/)
- [Spectrum Chat](https://spectrum.chat/wpgraphql)
- [Twitter](https://twitter.com/wpgraphql)

**Gatsby**
- [Discord Chat](https://gatsby.dev/discord)
- [Reddit](https://www.reddit.com/r/gatsbyjs/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/gatsby)


## Articles and Talks

详细阐述技术堆栈的文章和演讲列表.

- 2021.02: [Announcing Gatsby’s New WordPress Integration](https://www.gatsbyjs.com/blog/wordpress-integration)
- 2021.02: [Jason Bahl of WPGraphQL's role in the operating system for the web](https://www.youtube.com/watch?v=Me_A0HBYXx8)
- 2021.02: [Torque News Drop: Jason Bahl and WPGraphQL](https://www.youtube.com/watch?v=8SAdtU8HAwM)
- 2021.02: [Gatsby Launches New WordPress Integration, Expanding Support for Headless Architecture](https://wptavern.com/gatsby-launches-new-wordpress-integration-expanding-support-for-headless-architecture)
- 2020.11: [Announcing WPGraphQL v1.0](https://www.wpgraphql.com/2020/11/16/announcing-wpgraphql-v1/)
- 2020.07: [My Long Journey to a Decoupled WordPress Gatsby Site](https://css-tricks.com/my-long-journey-to-a-decoupled-wordpress-gatsby-site/)
- 2019.06：[JAMstack 上的现代 Web 开发
  ](https://www.netlify.com/oreilly-jamstack/) - 来自 Netlify 的关于 JAMStack 现代 Web 开发的报告，由 O&#39;REILLY 发布.


## Plugins

使 WordPress 和 Gatsby 协同工作的有用插件列表. 按字母顺序排列.

### WordPress

#### Essential Plugins

- [WPGraphQL](https://github.com/wp-graphql/wp-graphql) - [Documentation](https://docs.wpgraphql.com/) - WPGraphQL 将 GraphQL 的强大功能带入您的 WordPress 网站.
- [WPGatsby](https://wordpress.org/plugins/wp-gatsby/) - 此插件将您的 WordPress 站点配置为 Gatsby 的优化源.

#### WPGraphQL Extensions

- [WPGraphQL Cors](https://github.com/funkhaus/wp-graphql-cors) - 这个来自@kidunot89 和@byfunkhaus 的免费插件声称允许您设置 GraphQL 将接受的 CORS 标头，从而使 WPGraphQL 的身份验证“正常工作”，这意味着可以接受 WordPress 默认身份验证 cookie.
- [Total Counts for WPGraphQL](https://github.com/builtbycactus/total-counts-for-wp-graphql) - 这个来自@builtbycactus 的免费插件公开了 WPGraphQL 架构中的连接总数.
- [WPGraphQL Gutenberg](https://github.com/pristas-peter/wp-graphql-gutenberg) - 将 Gutenberg 块暴露给 WPGraphQL API.
- [WPGraphQL JWT Authentication](https://github.com/wp-graphql/wp-graphql-jwt-authentication) - 扩展 WPGraphQL 插件以使用 JWT（JSON Web 令牌）提供身份验证.
- [WPGraphQL Lock](https://github.com/valu-digital/wp-graphql-lock) - 通过实施持久的 GraphQL 查询为 WPGraphQL 启用查询锁定.
- [WPGraphQL Meta](https://github.com/roborourke/wp-graphql-meta) - 这个来自@robertorourke 的免费插件将通过 WordPress register_meta API 注册的元数据暴露给 WPGraphQL.
- [WPGraphQL Meta Query](https://github.com/wp-graphql/wp-graphql-meta-query) - 为 postObject 查询参数的 WPGraphQL 插件添加 Meta_Query 支持.
- [WPGraphQL Persisted Queries](https://github.com/Quartz/wp-graphql-persisted-queries) - 这个来自@qz 的免费插件增加了使用 WPGraphQL 的持久查询的能力.
- [WPGraphQL Offset Pagination](https://github.com/darylldoyle/wp-graphql-offset-pagination) - 这个来自@enshrined 的免费插件添加了基本的偏移分页，而不是 WPGraphQL 附带的基于标准游标的分页.
- [WPGraphQL Send Email](https://github.com/ashhitch/wp-graphql-send-mail)  - 来自@Ash_Hitchcock 的这个免费插件允许您通过简单的修改发送电子邮件. 包括限制发送到可信来源的能力.

---
**使用 WPGraphQL 的其他插件的扩展**

- [QL Search](https://github.com/funkhaus/ql-search) - 将 SearchWP 集成到 WPGraphQL 中的扩展.
- [WPGraphQL Content Blocks](https://github.com/Quartz/wp-graphql-content-blocks) - 这个来自 QZ.com 的免费插件公开了一种从 WordPress 帖子和页面查询 HTML 内容作为“块”（与古腾堡无关）的方法，从而为您查询的内容带来更多结构.
- [WPGraphQL Enable All Post Types (DalkMania)](https://github.com/DalkMania/wp-graphql-cpt) - 来自@DalkMania 的这个免费插件会自动将所有已注册的帖子类型添加到 WPGraphQL 模式.
- [WPGraphQL Enable All Post Types (TylerBarnes)](https://github.com/TylerBarnes/wp-graphql-enable-all-post-types) - 这个来自 @tylbar 的免费插件会自动将所有注册的帖子类型添加到 WPGraphQL 模式.
- [WPGraphQL Google Schema](https://github.com/izzygld/wp-graphql-google-schema) - 来自@izzygld261 的这个免费插件将 Google Schema 支持添加到 WPGraphQL.
- [WPGraphQL Gutenberg ACF](https://github.com/pristas-peter/wp-graphql-gutenberg-acf) - 通过 GraphQL 公开 ACF 块
- [WPGraphQL MB (MetaBox)](https://github.com/DalkMania/wp-graphql-mb) - 这个来自@DalkMania 的免费插件使用 [metabox.io](https://metabox.io/) 到 WPGraphQL 模式.
- [WPGraphQL MetaBox Relationships](https://github.com/hsimah-services/wp-graphql-mb-relationships) - 这个来自@hsimah 的免费插件增加了对 [metabox.io](https://metabox.io/) WPGraphQL 的关系字段（当还使用他的 wp-graphql-metabox 插件时）.
- [WPGraphQL Polls](https://github.com/andrenoberto/wp-graphql-polls) - 这个来自@andrenosouza 的免费插件允许您通过 GraphQL 查询和突变与来自 WP-Polls 插件的数据进行交互.
- [WPGraphQL Polylang Extension](https://github.com/valu-digital/wp-graphql-polylang) - 使用来自 Polylang 插件的语言数据扩展 WPGraphQL 模式.
- [WPGraphQL Tax Query](https://github.com/wp-graphql/wp-graphql-tax-query) - 为 postObject 查询参数 (WP_Query) 添加 Tax_Query 支持到 WPGraphQL 插件.
- [WPGraphQL WPML](https://github.com/rburgst/wp-graphql-wpml)  - 来自@rburgst 的这个免费插件使用来自 WPML 插件的语言数据扩展了 WPGraphQL 模式. 此外，它会关闭 WPML 默认过滤器，以便能够遍历所有帖子，而不管语言如何.
- [WPGraphQL for Advanced Custom Fields](https://github.com/wp-graphql/wp-graphql-acf) - 向 WPGraphQL 架构公开高级自定义字段.
- [WPGraphQL for BuddyPress](https://github.com/wp-graphql/wp-graphql-buddypress) - 来自@RenatoNascAlves 的这个免费插件将 BuddyPress 数据公开给 WPGraphQL.
- [WPGraphQL for Carbon Fields](https://github.com/matepaiva/wp-graphql-crb) - 来自@matepaiva 的这个免费插件将使用 Carbon Fields 注册的字段公开给 WPGraphQL Schema.
- [WPGraphQL for Custom Post Type UI](https://github.com/wp-graphql/wp-graphql-custom-post-type-ui) - 这个免费插件将设置添加到自定义帖子类型 UI，允许您设置 CPTUI 注册的帖子类型和分类法应显示在 WPGraphQL 架构中.
- [WPGraphQL for FacetWP](https://github.com/hsimah-services/wp-graphql-facetwp) - 这个来自@hsimah 的免费插件在 WPGraphQL 查询上公开过滤器，以允许使用 FacetWP 进行分面搜索.
- [WPGraphQL for Gravity Forms](https://github.com/harness-software/wp-graphql-gravity-forms) - 这个来自@harness_up 的@KellenMace 的免费插件将@gravityforms 数据公开给 WPGraphQL，允许您查询表单、字段、条目等.
- [WPGraphQL for Metabox](https://github.com/hsimah-services/wp-graphql-metabox) - 来自@hsimah 的这个免费插件将使用流行的 http://MetaBox.io 注册的字段公开到 WPGraphQL 模式.
- [WPGraphQL for Ninja Forms](https://github.com/toriphes/wp-graphql-ninja-forms) - 这个免费插件将 Ninja Forms 插件创建的表单暴露给 WPGraphQL Schema，并允许通过 GraphQL Mutations 提交表单.
- [WPGraphQL for Posts 2 Posts](https://github.com/harness-software/wp-graphql-posts-to-posts) - 来自@harness_up 的@KellenMace 的这个免费插件会自动为您所有的 Posts 2 Posts 连接创建 GraphQL 连接.
- [WPGraphQL for SEOPress](https://github.com/ashhitch/wp-graphql-yoast-seo) - 来自@moon_meister 的这个免费插件将 SEOPress 管理的数据暴露给 WPGraphQL 架构，允许在您的无头应用程序中使用 SEO 数据.
- [WPGraphQL for WooCommerce](https://github.com/wp-graphql/wp-graphql-woocommerce) - 这个免费插件将 WooCommerce 数据公开给 WPGraphQL，允许您通过 GraphQL 查询和突变与您商店的数据进行交互.
- [WPGraphQl Yoast SEO Plugin](https://github.com/ashhitch/wp-graphql-yoast-seo) - 将 Yoast SEO 数据公开给 WPGraphQL 插件.


#### Other helpful Plugins

- [Advanced Custom Fields](https://wordpress.org/plugins/advanced-custom-fields/) - [ACF PRO](https://www.advancedcustomfields.com/pro/)
- [Headless Mode](https://wordpress.org/plugins/headless-mode/)  - 无头模式为所有试图访问该站点的用户设置重定向. 唯一被授予许可的请求是那些试图访问 REST API、WP GraphQL API 或任何希望访问无头安装以编辑或创建帖子的登录用户.
- [Polylang](https://wordpress.org/plugins/polylang/)
- [WP JAMstack Deployments](https://github.com/crgeary/wp-jamstack-deployments) - 用于在 Netlify（和其他平台）上部署 JAMstack 的 WordPress 插件.


### Gatsby Plugins

- [gatsby-image](https://www.gatsbyjs.org/packages/gatsby-image)
- [gatsby-source-filesystem](https://www.gatsbyjs.org/packages/gatsby-source-filesystem)
- [gatsby-source-wordpress](https://www.gatsbyjs.org/packages/gatsby-source-wordpress)


## Free Tutorials / Courses

**注意：** 自从 gatsby-source-wordpress V4 发布以来，它比 gatsby-source-graphql 更受欢迎，因此我只会列出与该方法相关的教程.


### Written Tutorials

- 2019.11: [Guide to Gatsby WordPress Starter Advanced with Previews, i18n and more](https://dev.to/nevernull/overview-guide-to-gatsby-wordpress-starter-advanced-with-previews-i18n-and-more-583l) - 一个教程系列，从使用 WPGraphQL 的 WordPress 和 Gatsby 的基本设置开始，然后深入到更高级的主题，如部署、预览、i18n 和页面构建器，如使用 ACF 灵活的有效字段设置.
- 2019.08: [Live Previews with WordPress and Gatsby](https://justinwhall.com/live-previews-with-wordpress-gatsby/) - 教程展示了如何使用主题的高阶组件来促进 WordPress 帖子和自定义帖子类型的预览.
- 2019.08: [Gatsby with WPGraphQL, ACF and Gatbsy-Image](https://dev.to/nevernull/gatsby-with-wpgraphql-acf-and-gatbsy-image-72m) - 一个指南，展示了如何实现 gatsby-image，因此它可以用于 WordPress 媒体文件.
- 2018.08: [Headless WordPress + Gatsby + Netlify continuous deployment](https://justinwhall.com/headless-wordpress-gatsby-netlify-continous-deployment/) - 指南展示了如何通过几个简单的步骤创建 WordPress + Gatsby + Netlify 设置.


### Video Tutorials

- 2019.11: [25+ Videos - Gatsby + WordPress (2019) Complete Course](https://whatjackhasmade.co.uk/series/gatsby-wordpress-2019/)  - 该系列的重点是我们如何将 WordPress 用作具有 GraphQL 模式的无头 CMS 进行交互. 在设置好我们的 WordPress 网站和主题之后，我们将转向 Gatsby 以及我们如何使用我们的新模式为我们的 Gatsby 网站生成内容，以编程方式生成页面，将 Gutenberg 块转换为 React 组件并结束本章，重点是盖茨比中的搜索引擎优化.
- 2019.07: [Gatsby + WordPress with WPGraphQL (with Jason Bahl) — Learn With Jason](https://www.youtube.com/watch?v=DH7I1xRrbxs) - 在此流中，Jason Bahl 教授如何将 WordPress 与高级自定义字段和 WPGraphQL 结合使用来创建强大、灵活的管理仪表板，然后在 Gatsby 站点中查询和显示该数据.
- 2019.07: [Crash Course: Headless WordPress with WPGraphQL, ACF, and React](https://www.youtube.com/watch?v=9KGuI0UmpMw) - 在此视频中，Alex Young (WPCasts) 介绍了如何使用 WPGraphQL 和 React 获得简单的无头 WordPress 设置.
- 2019.06: [Using WordPress with WPGraphQL](https://www.youtube.com/watch?v=aqEfEuVWqws) - 在本视频中，您将学习如何使用名为 WPGraphQL 的超棒插件和一些额外的酷东西（如 GraphQL + 高级自定义字段）将 GraphQL 与 WordPress 结合使用.
- 2019.04: [WPGraphQL for ACF](https://www.youtube.com/watch?v=rIg4MHc8elg) - Jason Bahl 展示了如何将 WPGraphQL 用于高级自定义字段.
- 2018.07：[GraphQL with WordPress and Gutenberg - Jason Bahl - 2018 JavaScript for WordPress Conference
](https://www.youtube.com/watch?v=6CuM1PY9ESQ) - 在 2018 年 JavaScript for WordPress 大会的演讲中，WP GraphQL 插件的开发人员 Jason Bahl 提供了有关如何使用 GraphQL 的更新示例使用 WordPress 和古腾堡.


## Paid Tutorials / Courses
付费课程列表.

- 2021.01: [Building a Headless WordPress Site with Gatsby](https://www.linkedin.com/learning/building-a-headless-wordpress-site-with-gatsby) - 本课程逐步介绍如何使用 gatsby-source-wordpress 插件创建一个功能齐全的无头 Gatsby WordPress 网站，其中包含帖子、页面、类别、标签、帖子导航和其他功能.


## Starters
项目启动器列表，您可以克隆并开始构建.

- [Gatsby Starter - WordPress Twenty Twenty](https://github.com/henrikwirth/gatsby-starter-wordpress-twenty-twenty) - 使用新的 gatsby-source-wordpress@v4 将 WordPress Twenty Twenty 主题移植到 Gatsby.
- [Gatsby + WPGraphQL Blog Example](https://github.com/wp-graphql/gatsby-wpgraphql-blog-example) - 演示如何使用 WPGraphQL 作为 Gatsby 站点的源代码.
- [Gatsby + Headless WordPress + Netlify Starter](https://github.com/justinwhall/gatsby-wordpress-netlify-starter) - 用于持续部署到 Netlify 的 Gatsby + WordPress 启动器.
- [Gatsby WordPress Starter Advanced](https://github.com/henrikwirth/gatsby-starter-wordpress-advanced) - 一个高级的 Gatsby + WordPress 启动器，它是沿着教程系列构建的，并与 ACF 灵活的内容字段一起使用来创建内容块/布局.
- [Gatsby Starter Blog](https://github.com/zeevo/gatsby-starter-wordpress-blog) - 具有足够功能的博客启动器可以开箱即用.

## Themes
以 WordPress 为源的 gatsby 主题列表，您可以在 Gatsby 设置中使用它们.

- [Twenty Nineteen Gatsby Theme](https://github.com/zgordon/twentynineteen-gatsby-theme) - 一个 29 WordPress 主题的移植到 Gatsby.
- [Gatsby WordPress 出版商主题
 ](https://github.com/staticfuse/gatsby-theme-publisher) - Gatsby Publisher 主题允许您创建一个无头（或解耦）的 WordPress 站点. 该主题将在基于 React 和 Gatsby 构建的静态前端中显示您的所有页面和帖子.


## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/henrikwirth/awesome-wordpress-gatsby/blob/master/contributing.md) 第一的.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，Henrik Wirth 已放弃所有版权和
本作品的相关或邻接权利.

<!--- unicorn --->
