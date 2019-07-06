<div class="github-widget" data-repo="marcobiedermann/search-engine-optimization"></div>
## [Search Engine Optimization (SEO)](https://marcobiedermann.github.io/search-engine-optimization/)

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Join the chat at https://gitter.im/marcobiedermann/search-engine-optimization](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/marcobiedermann/search-engine-optimization)

搜索引擎优化（SEO）技巧和技巧的有用清单/集合.



## URL

-  **描述性网址：**使用描述性网页网址，该网址应反映您的目标关键字
- **[File extension](https://www.youtube.com/watch?v=dSG6C33GwsE)**：不要删除URL上的文件扩展名
- **[HTTPS](https://webmasters.googleblog.com/2014/08/https-as-ranking-signal.html)：**安全是Google的首要任务
- **[Hyphens](https://www.youtube.com/watch?v=AQcSFsQyct8)：**使用连字符分裂单词
- **[Localisation](https://support.google.com/webmasters/answer/62399)：**选择特定国家/地区的域名，以获得更好的本地搜索结果
- **[Subdomain or subfolder](https://www.youtube.com/watch?v=_MswMYk05tk)：**子域名被视为单独的域名
- **[URL builder](https://support.google.com/analytics/answer/1033867)：**使用此工具向您的网址添加自定义广告系列参数
- **[www or no-www](https://support.google.com/webmasters/answer/44231)：**提供两个域，但在Google网站站长工具中设置首选版本

## Accessibility

-  ** 403：**提供403  - 访问被拒绝页面
-  ** 404：**提供404  - 页面未找到页面
- **[Custom Search](https://developers.google.com/structured-data/slsb-overview):** with Google Sitelink search box, people can reach your content more quickly
-  **找不到文件：**避免“404 FILE_NOT_FOUND”错误
  -  **布局：**使用`divs`代替`tables`进行布局.  使用`tables`在语义上不正确.
-  **移动网站：**通过`.htaccess`将所有链接重定向到新位置
- **[Pagination](https://support.google.com/webmasters/answer/1663744)：**为链接实现`rel =“next”`和`rel =“prev”`属性
- **[Performance](https://developers.google.com/webmasters/mobile-sites/mobile-seo/common-mistakes/slow-mobile-pages)：**性能和加载时间很重要
  -  **重定向：**尽可能避免重定向.  使用301重定向而不是302
- **[RichSnippets](https://schema.org/)：**使用丰富的代码段标记您的代码，它们会显示在搜索结果页面上
-  **机器人：**阻止不应通过`robots.txt`文件索引的页面
  `<meta name="robots" content="">`
-  **验证：**写有效代码（[HTML Validator](https://validator.w3.org/) [CSS Validator](https://jigsaw.w3.org/css-validator/))
- **[WAI-Aria](https://www.w3.org/TR/wai-aria/)：**使用WAI-Aria标签来帮助机器理解您的代码

## Meta Information

- **[Description](https://www.youtube.com/watch?v=W4gr88oHb-k)：**每个页面都应该有唯一的描述（最多160个字符）
  `<meta name="description" content="">`
-  **标题：**每页应具有唯一的发言名称（60  -  100个字符）
   ` <title>网站标题</title>  `

## Keywords

-  **内容：**关键字应出现在文章长度的约3％
-  **标题：**关键字应出现在标题中
- **[Meta Tag](https://www.youtube.com/watch?v=jK7IPbnmvVU) ：**你可以省略` <meta name="keywords" content="">  `
  搜索引擎不使用此元标记
-  **研究：**流量高，竞争较少的关键词排名
-  **单身：**每个页面都应该有一个唯一的目标关键词
-  **标题：**关键字应出现在页面标题中
- **[URL](https://www.youtube.com/watch?v=rAWFv43qubI)：**关键字应出现在URL名称中


-  **内容：**内容在SEO中最重要
  -  ** Flash：**避免Flash内容和Flash页面.  他们无法通过手机访问，而且排名较低
  -  **新鲜度：**新内容很重要.  建议更新页面或定期发布
  -  **标题：**结构清晰`H1` -`H6`最大.  70个字符长
-  **长度：**文章应至少300字
-  **强：**使用`strong`标签突出显示您的目标关键字
- **[Uniqueness](https://www.youtube.com/watch?v=mQZY7EmjbMA)：**不提供重复内容，使用独特的内容类型

## Images

- **[Alt tag](https://support.google.com/webmasters/answer/114016)：**添加一个alt-tag这个图像的描述（60  -  70个字符）
-  **尺寸：**为图像添加`width =“”`和`height =“”`属性
- **[File name](https://www.youtube.com/watch?v=h2SWuUobbr0)：**使用简短的描述性名称
- **[Optimization](https://imageoptim.com/)：**通过删除一些元信息来优化图像
- **[Responsive Images](https://www.w3.org/TR/html-picture-element/)：**提供与窗口大小相对应的最优化图像
-  **大小：**保持文件大小尽可能低

## Videos

-  **控件：**添加控件以播放和控制您的视频
-  **嵌入：**允许其他人嵌入您的视频
-  **转录：**使用转录进行索引，可用性和内容
- **[Unplayable content](https://developers.google.com/webmasters/mobile-sites/mobile-seo/common-mistakes/unplayable-content) ：**避免无法播放的视频内容.  使用HTML5` <video>  `标记而不是Flash

## Links

-  **反向链接：**只有在您的网站有反向链接时才添加外部链接
-  **内部链接：**添加~3个内容链接到您的内容
- **[Languages](https://moz.com/learn/seo/hreflang-tag)：** hreflang标签告诉Google您在特定页面上使用的语言，因此搜索引擎可以将该结果提供给使用该语言搜索的用户
  `<link rel="alternate" href="example.com/fr/" hreflang="fr-fr" />`
  -  **命名：**使用描述性链接名称：“单击此处”或“阅读更多”是错误的链接文本.  更好“阅读更多关于SEO和Web可访问性”
- **[nofollow](https://support.google.com/webmasters/answer/96569)：**只为外部链接添加`rel =“nofollow”属性，以防止垃圾邮件和错误的链接
-  **标题：**将title属性添加到链接

## Mobile

- **[AppLinks](http://applinks.org/documentation/)：**链接到您的内容的应用可以使用此元数据深入链接到您的应用
- **[mobile friendly](https://googlewebmastercentral.blogspot.be/2014/11/helping-users-find-mobile-friendly-pages.html) ：**移动优化网站在搜索结果中标记.  测试 [mobile friendly site](https://www.google.com/webmasters/tools/mobile-friendly/)
- **[Smart App Banner](https://developer.apple.com/library/ios/documentation/AppleApplications/Reference/SafariWebContent/PromotingAppswithAppBanners/PromotingAppswithAppBanners.html)：** Safari具有智能应用横幅功能，可以从网站上提供在App Store上推广应用的标准化方法
- **[Tap targets](https://developers.google.com/speed/docs/insights/SizeTapTargetsAppropriately)：**可点击链接不应太小
-  **视口：**告诉浏览器如何调整页面的尺寸和缩放以适应设备
  `<meta name="viewport" content="width=device-width, initial-scale=1">`

## Sitemap

- **[HTML sitemap](https://www.youtube.com/watch?v=hi5DGOu1uA0)：** HTML站点地图允许网站访问者轻松浏览网站
- **[Image sitemap](https://support.google.com/webmasters/answer/178636)：**增加您的图像可以在图像搜索结果中找到
- **[Mobile sitemap](https://support.google.com/webmasters/answer/6082207)：**对于功能手机，您可以创建移动站点地图
- **[Video sitemap](https://support.google.com/webmasters/answer/80471)：**确保搜索引擎了解您网站上的所有视频内容
- **[XML sitemap](https://support.google.com/webmasters/answer/183668)：**帮助搜索引擎索引您的网页

## Social Media

- 作者信息
- **[Facebook](https://developers.facebook.com/docs/sharing/best-practices)：**分享网站和移动应用程序的最佳实践
- **[OpenGraph](http://ogp.me/)：** Open Graph协议使任何网页都成为社交图中的丰富对象.
- **[Social Profiles](https://developers.google.com/webmasters/structured-data/customize/social-profiles)：**将社交个人资料添加到您的Google搜索结果中
-  **社交分享：**为您的网站提供分享选项
- **[Twitter](https://dev.twitter.com/cards/getting-started)：**使用Twitter卡，您可以附加照片，视频和媒体经验给您推文

## Tools & Services

### Webmasters

- **[Bing Webmasters](http://www.bing.com/toolbox/webmaster):** allows webmasters to add their websites to the Bing index crawler.
- **[Google Search Console (GWT)](https://www.google.com/webmasters/)：**允许网站管理员检查索引状态并优化其网站的可见性
- **[Google Tag Manager](https://www.google.com/analytics/tag-manager/) ：**了解Google Analytics跟踪代码管理器以及它如何帮助简化您的生活和IT请求的需求.  只需点击几下即可启动新标签.

### Analytics

- **[Ahrefs](https://ahrefs.com/) ：**分析网站，跟踪社交媒体，建立反向链接 -  Ahrefs让你了解.  立即尝试我们的营销和SEO工具Site Explorer和Content Explorer！
- **[BuzzSumo](https://app.buzzsumo.com/research/most-shared)：**找到任何主题或域的最共享内容.
- **[Followerwonk](https://moz.com/followerwonk)：**分析，生物搜索等工具
- **[Google Analytics](https://www.google.com/analytics/)：**生成有关网站流量的详细统计信息
- **[Open Site Explorer](https://moz.com/researchtools/ose/) ：**使用Open Site Explorer识别链接构建机会.  研究反向链接，识别首页，查看社交活动以及分析锚文本.
- **[Matomo](https://matomo.org/)：**一个开放的分析平台
- **[SEMrush](https://www.semrush.com/)：** SEMrush是一个功能强大的多功能竞争情报套件，适用于在线营销，从SEO和PPC到社交媒体和视频广告研究.
- **[Seomator](https://seomator.com/)：** SEO审计工具和网站爬虫，通过如何修复提示改善SEO性能.
- **[SEOstats](https://github.com/eyecatchup/SEOstats)：** SEOstats是一个功能强大的开源PHP库，可以请求一堆SEO相关指标.
- **[SimilarWeb](https://www.similarweb.com/) ：**将网站流量与SimilarWeb.com的高级流量估算工具进行比较.  查看任何网站的流量来源并发现他们的在线营销策略.
- **[Twitter Analytics](https://analytics.twitter.com/)：**衡量并提升你对Twitter的影响力.

### Optimization

- **[PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)：** Page Speed Insights衡量移动设备和桌面设备页面的性能.
- **[Varvy Seo tool](https://varvy.com/)：**显示：域名强度，链接，图像搜索引擎优化，社交计数和提及，页面/技术搜索引擎优化，页面速度等.
- **[Webpagetest.org](https://www.webpagetest.org/) ：**网页测试为您提供整体性能瀑布以及网站的渲染时间表.  它还提供了对第一个字节的时间以及可能阻碍网页性能的关键洞察力
- **[WooRank](https://www.woorank.com/)：** WooRank将帮助您解决您网站上的问题，并找出让您领先于竞争对手的机会.

### Keywords

- **[Google Trends](https://www.google.com/trends/)：**使用Google趋势探索Google热门搜索主题.
- **[Keyword Planner](https://adwords.google.com/KeywordPlanner)：**计划您的搜索网络广告系列并了解客户的需求
- **[Keyword Tool](http://keywordtool.io/) ：**最佳免费替代谷歌关键字工具的SEO和PPC关键字研究！  在几秒钟内从Google Suggest获得750多个相关的长尾关键词！
- **[Moz Keyword Explorer](https://moz.com/explorer)：**付费关键字工具，提供精确的搜索量，关键字难度，SERP功能和有机点击率数据.

### Links

- **[OpenLinkProfiler](http://www.openlinkprofiler.org/)：**深入分析最新鲜的反向链接.
- **[Search Engine Spider Simulator](http://tools.seochat.com/tools/search-spider-simulator)：**此工具通过显示网页内容来模拟搜索引擎，完全与搜索引擎机器人在抓取页面时看到的方式相同：查看最突出或不可访问的页面元素.
- **[Screaming Frog SEO Spider Tool & Crawler Software](https://www.screamingfrog.co.uk/seo-spider/)：** Screaming Frog SEO Spider是一个小型桌面程序（PC或Mac），它从SEO角度抓取网站的链接，图像，CSS，脚本和应用程序.

### Structured Data

- **[Facebook Debugger](https://developers.facebook.com/tools/debug)：**输入您要抓取的网址，以查看该网页的标记如何显示在Facebook上
- **[Pinterest](https://developers.pinterest.com/rich_pins/validator/)：**验证您的Rich Pins并申请将它们放到Pinterest上
- **[Structured Data Testing Tool](https://developers.google.com/structured-data/testing-tool/)：**粘贴在您的丰富网页摘要或网址上进行测试
- **[Twitter card validator](https://cards-dev.twitter.com/validator)：**输入带有要验证的元标记的页面的URL

### Bookmarklets

- **[OuiSEO](https://github.com/carlsednaoui/seo-bookmarklet)：**一个开源书签，向您显示页面上的SEO和社交元数据信息.
- **[SEO Bookmarklet](https://twkm.ca/projects/seo-bookmarklet)：**一站式SEO书签快速审查现场搜索引擎优化

### Browser Extensions

- **[MozBar](https://moz.com/tools/seo-toolbar) ：**来自Moz的SEO工具栏可让您快速访问许多页面上的搜索引擎优化因素，域和页面权限以及快速nofollow切换.  立即下载免费工具栏！

### Jekyll Plugins

- **[Jekyll SEO Tag](https://github.com/jekyll/jekyll-seo-tag)：**一个Jekyll插件，用于为搜索引擎和社交网络添加元数据标签，以便更好地索引和显示您网站的内容.

### TYPO3 Extensions

- **[Basic SEO Features](https://typo3.org/extensions/repository/view/seo_basics)：**为每页标题标记添加单独的字段，在新模块中添加易于搜索引擎优化的关键字和描述以及灵活的Google Sitemap.
- **[Google sitemap](https://typo3.org/extensions/repository/view/dd_googlesitemap)：**高性能的Google站点地图实施，可避免其他类似扩展程序出现的典型错误.

### WordPress Plugins

- **[All in One SEO Pack](https://wordpress.org/plugins/all-in-one-seo-pack/) ：**下载量最多的WordPress插件（下载量近3000万）.  使用All in One SEO Pack自动优化您的搜索引擎网站
- **[Yoast SEO](https://wordpress.org/plugins/wordpress-seo/)：**改善你的WordPress SEO：写出更好的内容，并使用Yoast SEO插件有一个完全优化的WordPress网站.

## Books

- **[Search engine optimization 2016: Learn SEO with smart internet marketing strategies](https://www.amazon.com/Search-Optimization-Internet-Marketing-Strategies/dp/151534567X)：**学习搜索引擎优化策略，以SEO 2016排名在谷歌的顶部
- **[Search Engine Optimization All-in-One For Dummies](https://www.amazon.com/Search-Engine-Optimization-All-Dummies/dp/1118921755) ：** Bruce Clay是SEO社区中最受尊敬的人物之一，在所有主要会议上教授课程和研讨会.  就像“搜索引擎优化的艺术”一样，这本书实际上非常技术性，可能不是你最好的第一指南，尽管它是“傻瓜”系列的一部分.
- **[SEO 2016: Learn Search Engine Optimization](https://www.amazon.com/SEO-2016-Search-Engine-Optimization/dp/1512275069)：**当今竞争搜索环境中SEO的全面必备指南
- **[SEO Fitness Workbook](https://www.amazon.com/SEO-Fitness-Workbook-2016-Optimization/dp/1518748880)：**关于搜索引擎优化的一步一步的书，从目标开始，浏览页面搜索引擎优化，如页面标签，最后是关闭页面搜索引擎优化，如链接建设和社会提及.
- **[SEO For Dummies, 6th Edition](http://shop.oreilly.com/product/9781119129554.do)：**您完全更新的搜索引擎优化指南
- **[SEO Step-by-Step - The Complete Beginner's Guide to Getting Traffic from Google](https://www.amazon.com/SEO-Step-Step-Complete-Beginners/dp/1497415020) ：**也从关键字开始，涵盖ON PAGE和OFF PAGE SEO.  强调速度的重要性，并有一个很好的附录与SEO资源，词汇表和链接.
- **[SEO Warrior](http://shop.oreilly.com/product/9780596157081.do)：**提高Web可见性的基本技术
- **[SEO: Marketing Strategies to Dominate the First Page](https://www.amazon.com/SEO-Marketing-Strategies-analytics-optimization-ebook/dp/B01ACB7LQM)：** Google Analytics，网站站长，网站流量，Adwords，每次点击付费，网站推广和搜索引擎优化简介.
- **[The Art of SEO, 3rd Edition](http://shop.oreilly.com/product/0636920032908.do)：**掌握搜索引擎优化
- **[The Beginner's Guide to SEO](https://moz.com/beginners-guide-to-seo) ：**新来的SEO？  需要提高你的知识吗？  搜索引擎优化的初学者指南已被阅读超过300万次，并提供了获得专业质量搜索引擎优化所需的信息.
- **[The SEO Battlefield](http://shop.oreilly.com/product/0636920050964.do)：**如果您想建立一个持续的SEO计划，目标是增加流量和搜索突出，这个实用的分步指南将帮助您了解SEO方法，然后向您展示如何将这些理论付诸实践.

## Courses

- **[Analyzing Your Website to Improve SEO](https://www.lynda.com/Marketing-Small-Business-Marketing-tutorials/Analyzing-Your-Website-Improve-SEO/82409-2.html) ：**逐步完成审查网站内容和标记的过程，以提高其在搜索引擎结果中的排名.  与Lynda.com的Peter Kent合作
- **[ClickMinded](https://www.clickminded.com/)：** ClickMinded是一个SEO培训课程，面向希望尽快增加有机流量和销售额的创业公司.
- **[Ecommerce SEO 101 Video Series](https://www.shopify.com/videos/ecommerce-seo-101)：**电子商务SEO 101视频系列与海伦Overland shopify
- **[Improving SEO Using Accessibility Techniques](https://www.lynda.com/HTML-5-tutorials/Improving-SEO-Using-Accessibility-Techniques/89051-6.html) ：**通过适当的标记和Web标准合规性，使网站更易于访问和搜索引擎友好.  与Lynda.com的Morten Rand-Hendriksen合作
- **[International SEO Fundamentals](https://www.lynda.com/Analytics-tutorials/International-SEO-Fundamentals/377449-6.html) ：**通过这些SEO技巧吸引国际访问者访问您的网站.  了解如何确定目标市场并优化您网站的技术方面和内容，以适应世界各国和各种语言.  与Lynda.com的David Booth合作
- **[Learning Search Engine Optimization (SEO): A Video Introduction](https://www.video2brain.com/en/courses/learning-search-engine-optimization-seo-a-video-introduction)：**学习搜索引擎优化（SEO）：视频介绍Matt Bailey by video2brain
- **[Learning Web Analytics](https://www.video2brain.com/en/courses/learning-web-analytics)：**通过video2brain与Matt Bailey一起学习网络分析
- **[SEO for Beginners](http://seoforbeginners.com/)：**初学者搜索引擎优化：视频指南简介
- **[SEO for Ecommerce](https://www.lynda.com/Google-Analytics-tutorials/SEO-Ecommerce/386884-2.html) ：**电子商务的SEO是不同的.  获取针对优化在线商店的策略，以改善页面排名和构建流量.  与Lynda.com的Steven Harris合作
- **[SEO for Local Visibility](https://www.lynda.com/Google-Maps-tutorials/SEO-Local-Visibility/178132-2.html) ：**使用这些本地SEO策略在搜索排名中实现最大可见性.  与Lynda.com的Brad Batesole合作
- **[SEO for Web Designers](https://webdesign.tutsplus.com/courses/seo-for-web-designers)：**网站设计师的SEO与TutsPlus的Craig Campbell合作
- **[SEO Fundamentals](https://www.lynda.com/Analytics-tutorials/SEO-Fundamentals/187858-2.html)：Lynda.com与David Booth的SEO基础知识
- **[SEO Fundamentals](https://www.pluralsight.com/courses/seo-fundamentals)：Pluralsight与保罗威尔逊的SEO基础
- **[SEO Tools Fundamentals](https://www.lynda.com/Buzzstream-tutorials/SEO-Tools-Fundamentals/368917-2.html) ：**了解当今用于技术优化，内容优化，异地优化和竞争性研究的顶级SEO工具.  与Lynda.com的Brad Batesole合作
- **[SEO Training Course by Moz](https://www.udemy.com/whiteboard-seo/)：** udemy与Moz的SEO培训课程
- **[SEO: Keyword Strategy in Depth](https://www.lynda.com/Business-Online-Marketing-tutorials/SEO-Keyword-Strategy-Depth/147030-6.html) ：**了解如何研究关键字，将其应用到您的网站，以及围绕关键字制作广告系列.  通过关键字增加网站流量并更好地了解用户的意图.  与Lynda.com的Matt Bailey合作
- **[SEO: Link Building in Depth](https://www.lynda.com/Business-Online-Marketing-tutorials/SEO-Link-Building-Depth/95253-6.html) ：**调查链接的解剖，链接如何影响页面排名，以及构成出色链接的属性.  与Lynda.com的Peter Kent合作
- **[Spying with SEO Tools](https://www.lynda.com/Marketing-PPC-tutorials/Spying-SEO-Tools/371730-6.html) ：**学习如何使用SEO工具和技术在线研究竞争.  找出竞争对手正在优化的关键字，然后在搜索引擎结果页面上超越它们.  随着Anson Alexander by Lynda.com
- **[Video SEO Basics](https://www.lynda.com/Business-Web-Video-tutorials/Video-SEO-Basics/118217-6.html) ：**为搜索引擎优化您的视频并转换流量以实现您的业务目标.  与Lynda.com的Ian Lurie合作
- **[WordPress Plugins: SEO](https://www.lynda.com/WordPress-tutorials/WordPress-Plugins-SEO/140779-2.html) ：**借助两个强大的插件，通过执行搜索引擎优化或搜索引擎优化，为您的WordPress网站吸引更多访问者.  与Lynda.com的Morten Rand-Hendriksen合作

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
