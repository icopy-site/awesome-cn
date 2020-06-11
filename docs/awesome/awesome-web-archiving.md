<div class="github-widget" data-repo="iipc/awesome-web-archiving"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Web Archiving [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

 Web归档是收集万维网部分的过程，以确保将信息保存在存档中，以供将来的研究人员，历史学家和公众使用.  由于Web规模庞大，Web档案管理员通常会使用Web搜寻器进行自动捕获.  不断发展的Web标准要求归档工具不断发展，以跟上Web技术的变化，以确保可靠，有意义地捕获和重放已存档的Web页面.




## Training/Documentation

* Web归档概念简介：
  * [What is a web archive?](https://youtu.be/ubDHY-ynWi0) -来自的视频 [the UK Web Archive YouTube Channel](https://www.youtube.com/channel/UCJukhTSw8VRj-VNTpBcqWkw)
  * [Wikipedia's List of Web Archiving Initiatives](https://en.wikipedia.org/wiki/List_of_Web_archiving_initiatives)
  * [Glossary of Archive-It and Web Archiving Terms](https://support.archive-it.org/hc/en-us/articles/208111686-Glossary-of-Archive-It-and-Web-Archiving-Terms)
  * [The Web Archiving Lifecycle Model](https://archive-it.org/blog/post/announcing-the-web-archiving-life-cycle-model/)  -Web归档生命周期模型是一种尝试，它将Web归档的技术和程序臂纳入了一个框架，该框架与任何寻求从Web归档内容的组织都有关.  来自Internet Archive的Web归档服务Archive-It根据其与世界各地存储机构的合作开发了该模型.
* WARC标准：
  * [warc-specifications](https://iipc.github.io/warc-specifications/) 官方规范的社区HTML版本和新提案的中心.
  * [offical ISO 28500 WARC specification homepage](http://bibnum.bnf.fr/WARC/).
*对于使用网络档案的研究人员：
  * [GLAM Workbench: Web Archives](https://glam-workbench.github.io/web-archives/) - 也可以看看 [this related blog post on 'Asking questions with web archives'](https://netpreserveblog.wordpress.com/2020/05/28/asking-questions-with-web-archives/).
  * [Archives Unleashed Toolkit documentation](https://aut.docs.archivesunleashed.org/)

## Resources for Web Publishers

当与在网络上发布并且希望确保其站点可以被存档的个人或组织合作时，这些资源可以提供帮助.

* [Stanford Libraries' Archivability pages](https://library.stanford.edu/projects/web-archiving/archivability)
* [Archive Ready](http://archiveready.com/) 工具，用于估计成功归档网页的可能性.


## Tools & Software

 该工具和软件列表旨在简要描述与Web归档相关的一些最重要且使用最广泛的工具.  有关更多详细信息，我们建议您参考（并做出贡献！）其他组的这些优秀资源：
* [Comparison of web archiving software](https://github.com/archivers-space/research/tree/master/web_archiving)
* [Awesome Website Change Monitoring](https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring)
* [Web Crawl @ COPTR](http://coptr.digipres.org/Category:Web_Crawl)

### Acquisition

* [ArchiveBox](https://github.com/pirate/ArchiveBox)  -使用wget，chrome无头浏览器和其他方法（以前称为“书签存档器”）从RSS feed，书签和链接维护附加存档的工具.  *（开发中）*
* [archivenow](https://github.com/oduwsdl/archivenow) - 一个 [Python library](http://ws-dl.blogspot.com/2017/02/2017-02-22-archive-now-archivenow.html)  将网络资源推送到按需网络存档中.  *（稳定）*
* [Brozzler](https://github.com/internetarchive/brozzler)  -使用实际浏览器（Chrome或Chrome）的分布式Web爬虫（爬虫），以获取页面和嵌入的URL并提取链接.  *（稳定）*
* [Chronicler](https://github.com/CGamesPlay/chronicler)  -具有记录和重放功能的Web浏览器.  *（开发中）*
* [Crawl](https://git.autistici.org/ale/crawl)  -Golang中的简单网络爬虫.  *（稳定）*
* [crocoite](https://github.com/promyloph/crocoite)  -使用无头的Google Chrome / Chromium抓取网站，并将资源，静态DOM快照和页面屏幕截图保存到WARC文件.  *（开发中）*
* [F(b)arc](https://github.com/justinlittman/fbarc) -命令行工具和Python库，用于从中存档数据 [Facebook](https://www.facebook.com/) 使用 [Graph API](https://developers.facebook.com/docs/graph-api) .  *（稳定）*
* [freeze-dry](https://github.com/WebMemex/freeze-dry)  -JavaScript库，可将页面转换为静态的独立HTML文档；  对于浏览器扩展很有用.  *（开发中）*
* [grab-site](https://github.com/ArchiveTeam/grab-site)  -档案管理员的网络搜寻器：WARC输出，所有搜寻的仪表板，动态忽略模式.  *（稳定）*
* [Heritrix](https://github.com/internetarchive/heritrix3/wiki)  -一个开源的，可扩展的，网络规模的，档案质量的网络爬虫.  *（稳定）*
  * [Heritrix Walkthrough](https://github.com/web-archive-group/heritrix-walkthrough) *（开发中）*
* [html2warc](https://github.com/steffenfritz/html2warc)  -将脱机数据转换为单个WARC文件的简单脚本.  *（稳定）*
* [HTTrack](http://www.httrack.com/)  -开源网站复制实用程序.  *（稳定）*
* [Lentil](https://github.com/NCSU-Libraries/lentil)  -Ruby on Rails Engine，支持从Instagram收集图像并提供几种浏览视图，共享机制，用户选择自己喜欢的图像的工具，用于审核图像的管理界面以及用于收集图像和提交供体协议的系统准备摄取到外部存储库中.  *（稳定）*
* [monolith](https://github.com/Y2Z/monolith)  -CLI工具，用于将网页另存为单个HTML文件.  *（稳定）*
* [SingleFile](https://github.com/gildas-lormeau/SingleFile) - Browser extension for Firefox/Chrome and CLI tool to save a faithful copy of a complete page as a single HTML file. *(Stable)*
* [SiteStory](http://mementoweb.github.com/SiteStory/)  -事务性归档文件，有选择地捕获和存储在Web客户端（浏览器）和Web服务器之间发生的事务.  *（稳定）*
* [Social Feed Manager](https://gwu-libraries.github.io/sfm-ui/)  -开源软件，使用户能够从Twitter，Tumblr，Flickr和Sina Weibo公共API创建社交媒体集合.  *（稳定）*
* [Squidwarc](https://github.com/N0taN3rd/Squidwarc) -一个 [open source, high-fidelity, page interacting](http://ws-dl.blogspot.com/2017/07/2017-07-24-replacing-heritrix-with.html)  直接使用Chrome或Chrome无头的档案搜寻器.  *（开发中）*
* [StormCrawler](http://stormcrawler.net/)  -用于在Apache Storm上构建低延迟，可伸缩的Web搜寻器的资源集合.  *（稳定）*
* [twarc](https://github.com/docnow/twarc)  -用于归档Twitter JSON数据的命令行工具和Python库.  *（稳定）*
* [WARCreate](http://matkelly.com/warcreate/) - 一个 [Google Chrome](https://www.google.com/intl/en/chrome/browser/)  用于将单个网页或网站存档到WARC文件的扩展名.  *（稳定）*
* [Warcworker](https://github.com/peterk/warcworker)  -基于Squidwarc的开源，泊坞窗式，排队式，高保真度的Web存档器，具有简单的Web GUI.  *（稳定）*
* [WAIL](https://machawk1.github.io/wail/) -在多个Web归档工具之上的图形用户界面（GUI），旨在用作任何人保存和重放Web页面的简便方法； [Python](https://machawk1.github.io/wail/), [Electron](https://github.com/n0tan3rd/wail) .  *（稳定）*
* [Web2Warc](https://github.com/helgeho/Web2Warc)  -易于使用且高度可定制的搜寻器，任何人都可以创建自己的小型Web存档（WARC / CDX）.  *（稳定）*
* [WebMemex](https://github.com/WebMemex)  -Firefox和Chrome浏览器扩展程序，可用于存档您访问的网页.  *（开发中）*
* [Webrecorder](https://webrecorder.io/)  -创建您浏览的任何网站的高保真交互式记录.  *（稳定）*
* [Wget](http://www.gnu.org/software/wget/) -的开源文件检索工具 [version 1.14 supports writing warcs](http://www.archiveteam.org/index.php?title=Wget_with_WARC_output) .  *（稳定）*
* [Wget-lua](https://github.com/alard/wget-lua)  -具有Lua扩展名的Wget.  *（稳定）*
* [Wpull](https://github.com/chfoo/wpull)  -与Wget兼容（或翻版/克隆/替换/替代）的Web下载器和搜寻器.  *（稳定）*

### Replay

* [PyWb](https://github.com/ikreymer/pywb)  -Web存档重播工具的Python（2和3）实现，有时也称为“ Wayback Machine”.  *（稳定）*
* [OpenWayback](https://github.com/iipc/openwayback/)  -这个开源项目旨在开发Wayback Machine，Wayback Machine是全球网络档案馆在用户浏览器中回放存档网站所使用的关键软件.  *（稳定）*
* [Webrecorder Player](https://github.com/webrecorder/webrecorderplayer-electron) -适用于台式机macOS / Windows / Linux的Web记录器播放器（内置Electron + Web记录器）.
* [InterPlanetary Wayback (ipwb)](https://github.com/oduwsdl/ipwb) -Web存档（WARC）索引并使用 [IPFS](https://ipfs.io/).
* [Reconstructive](https://oduwsdl.github.io/Reconstructive/) -Reconstructive是ServiceWorker模块，用于通过将资源请求重新路由到相应的存档副本（JavaScript）来在客户端重建复合纪念品.

### Search & Discovery

* [Mink](https://github.com/machawk1/mink) - 一个 [Google Chrome](https://www.google.com/intl/en/chrome/browser/)  扩展，用于在浏览和集成实时存档的Web导航时查询Memento聚合器.  *（稳定）*
* [SecurityTrails](https://securitytrails.com/)  -用于WHOIS和DNS记录的基于Web的存档.  REST API是免费提供的. 
* [Tempas v1](http://tempas.L3S.de/v1) -基于以下内容的时间Web存档搜索 [Delicious](https://en.wikipedia.org/wiki/Delicious_(website) ）标签.  *（稳定）*
* [Tempas v2](http://tempas.L3S.de/v2) -基于1996年至2013年从德国网络中提取的链接和锚文本对时间网络档案进行搜索（结果不限于德语页面，例如， [Obama@2005-2009 in Tempas](http://tempas.l3s.de/v2/query?q=obama&from=2005&to=2009) ）.  *（稳定）*
* [webarchive-discovery](https://github.com/ukwa/webarchive-discovery)  -WARC和ARC全文索引和发现工具，以及许多能够使用下面显示的索引的关联工具.  *（稳定）*
  * [Shine](https://github.com/ukwa/shine) -与研究人员一起开发的原型网络档案探索用户界面， [Big UK Domain Data for the Arts and Humanities project](https://buddah.projects.history.ac.uk/) .  *（稳定）*
  * [SolrWayback](https://github.com/netarchivesuite/solrwayback)  -具有WARC集成播放功能的原型Web档案浏览UI.  *（开发中）*
  * [Warclight](https://github.com/archivesunleashed/warclight)  -基于Project Blacklight的Rails引擎，支持发现WARC和ARC格式的Web存档.  *（开发中）*
  * [Wasp](https://github.com/webis-de/wasp) -个人完整功能的原型 [web archive and search system](http://ceur-ws.org/Vol-2167/paper6.pdf) .  *（开发中）*
  *在“ webarchive-discovery” Wiki中列出了用于构建前端的其他可能选项， [here](https://github.com/ukwa/webarchive-discovery/wiki/Front-ends).

### Utilities

* [ArchiveTools](https://github.com/recrm/ArchiveTools) -收集用于提取WARC文件并与之交互的工具（Python）.
* [har2warc](https://github.com/webrecorder/har2warc) -转换HTTP存档（HAR）-&gt; Web存档（WARC）格式（Python）.
* [httpreserve.info](http://httpreserve.info/)  -用于返回网页状态或将其保存到Internet存档的服务.  使用GET（Golang包）通过浏览器或CURL返回JSON.  *（稳定）*
* [HTTPreserve Workbench](https://github.com/httpreserve/workbench)  -用于描述以简单JSON输出编码的网页状态的工具和API，该JSON输出描述了当前状态以及wayback.org上的最早和最新链接.  将网页保存到Internet存档.  审核URI列表，并输出包含上述数据的CSV（Golang）.  *（开发中）*
* [MementoMap](https://github.com/oduwsdl/MementoMap)  -概述Web Archive Holdings（Python）的工具.  *（开发中）*
* [MemGator](https://github.com/oduwsdl/MemGator)  -Memento聚合器CLI和服务器（Golang）.  *（稳定）*
* [node-cdxj](https://github.com/N0taN3rd/node-cdxj) - [CDXJ](https://github.com/oduwsdl/ORS/wiki/CDXJ)  文件解析器（Node.js）.  *（稳定）*
* [OutbackCDX](https://github.com/nla/outbackcdx)  -基于RocksDB的捕获索引（CDX）服务器，支持增量更新和压缩.  可用作OpenWayback，PyWb和 [Heritrix](https://github.com/ukwa/ukwa-heritrix/blob/master/src/main/java/uk/bl/wap/modules/uriuniqfilters/OutbackCDXRecentlySeenUriUniqFilter.java) .  *（稳定）*
* [py-wasapi-client](https://github.com/unt-libraries/py-wasapi-client)  -命令行应用程序，用于从WASAPI（Python）下载爬网.  *（稳定）*
* [tikalinkextract](https://github.com/httpreserve/tikalinkextract)  -从Apache Tika（Golang，Apache Tika Server）可以解析的文档类型的文件夹中提取超链接作为用于网络归档的种子.  *（开发中）*
* [wasapi-downloader](https://github.com/sul-dlss/wasapi-downloader)  -用于从WASAPI下载爬网的Java命令行应用程序.  *（稳定）*
* [WarcPartitioner](https://github.com/helgeho/WarcPartitioner)  -按MIME类型和年份对（W）ARC文件进行分区.  *（稳定）*
* [webarchive-indexing](https://github.com/ikreymer/webarchive-indexing) -用于在Hadoop，EMR或本地文件系统上对WARC / ARC文件进行批量索引的工具.
* [wikiteam](https://github.com/WikiTeam/wikiteam)  -下载和保存Wiki的工具.  *（稳定）*

### WARC I/O Libraries

* [HadoopConcatGz](https://github.com/helgeho/HadoopConcatGz)  -用于级联GZIP文件（和`* .warc.gz`）的可拆分Hadoop InputFormat.  *（稳定）*
* [jwarc](https://github.com/iipc/jwarc) -使用类型安全API（Java）读写WARC文件.
* [Jwat](https://sbforge.org/display/JWAT/JWAT)  -用于读取/写入/验证WARC / ARC / GZIP文件（Java）的库和工具.  *（稳定）*
* [node-warc](https://github.com/N0taN3rd/node-warc) -解析WARC文件或使用以下任一文件创建WARC文件 [Electron](https://electron.atom.io/) 要么 [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface)  （Node.js）.  *（稳定）*
* [Warcat](https://github.com/chfoo/warcat)  -用于处理Web ArChive（WARC）文件（Python）的工具和库.  *（稳定）*
* [warcio](https://github.com/webrecorder/warcio) -流式WARC / ARC库，用于快速Web归档IO（Python）.
* [warctools](https://github.com/internetarchive/warctools) -用于ARC和WARC文件的库（Python）.
* [webarchive](https://github.com/richardlehane/webarchive) -用于ARC和WARC Web存档格式（Golang）的Golang阅读器.

### Analysis

* [ArchiveSpark](https://github.com/helgeho/ArchiveSpark)  -用于Web存档的Apache Spark框架（不仅如此），可轻松进行数据处理，提取和派生.  *（稳定）*
* [Archives Unleashed Cloud](https://cloud.archivesunleashed.org)  -Archives Unleashed Cloud（AUK）是用于分析Web存档的Web界面.  当前，它可以与Archive-It集合同步，并从您的集合中提取超链接网络，全文和其他信息.  *（稳定）*
* [Archives Unleashed Notebooks](https://github.com/archivesunleashed/notebooks)  -用于使用Archives Unleashed Toolkit和由Archives Unleashed Toolkit生成的派生工具处理Web存档的笔记本.  *（稳定）*
* [Archives Unleashed Toolkit](https://github.com/archivesunleashed/aut)  -Archives Unleashed Toolkit（AUT）是一个开源平台，用于使用Apache Spark分析Web存档.  *（稳定）*
* [Tweet Archvies Unleashed Toolkit](https://github.com/archivesunleashed/twut)  -一个开源工具包，用于使用Apache Spark分析面向行的JSON Twitter存档.  *（开发中）*

### Quality Assurance

* [Chrome Check My Links](https://chrome.google.com/webstore/detail/check-my-links/ojkcdipcgfaekbeaelaapakgnjflfglf) -浏览器扩展：具有更多选项的链接检查器.
* [Chrome link checker](https://chrome.google.com/webstore/detail/link-checker/aibjbgmpmnidnmagaefhmcjhadpffaoi) -浏览器扩展：基本链接检查器.
* [Chrome link gopher](https://chrome.google.com/webstore/detail/bpjdkodgnbfalgghnbeggfbfjpcfamkf/publish-accepted?hl=en-US&gl=US) -浏览器扩展：页面上的链接收割机.
* [Chrome Open Multiple URLs](https://chrome.google.com/webstore/detail/open-multiple-urls/oifijhaokejakekmnjmphonojcfkpbbh?hl=de) -浏览器扩展：打开多个URL，还从文本中提取URL.
* [Chrome Revolver](https://chrome.google.com/webstore/detail/revolver-tabs/dlknooajieciikpedpldejhhijacnbda) -浏览器扩展：在浏览器标签之间切换.
* [FlameShot](https://github.com/lupoDharkael/flameshot) -在Ubuntu上的屏幕截图和注释.
* [PlayOnLinux](https://www.playonlinux.com/en/) -用于在Ubuntu上运行Xenu和Notepad ++.
* [PlayOnMac](https://www.playonmac.com/en/) -用于在macOS上运行Xenu和Notepad ++.
* [Windows Snipping Tool](https://support.microsoft.com/en-gb/help/13776/windows-use-snipping-tool-to-capture-screenshots)  -内置Windows，用于部分屏幕捕获和注释.  在macOS上，您可以使用Command + Shift + 4（用于进行部分屏幕捕获的键盘快捷键）.
* [WineBottler](http://winebottler.kronenberg.org/) -用于在macOS上运行Xenu和Notepad ++.
* [xDoTool](https://github.com/jordansissel/xdotool) - Click automation on Ubuntu.
* [Xenu](http://home.snafu.de/tilman/xenulink.html) -Windows的桌面链接检查器.


## Community Resources

### Other Awesome Lists

* [Web Archiving Community](https://github.com/pirate/ArchiveBox/wiki/Web-Archiving-Community)
* [Awesome Memento](https://github.com/machawk1/awesome-memento)
* [The WARC Ecosystem](http://www.archiveteam.org/index.php?title=The_WARC_Ecosystem)
* [The Web Crawl section of COPTR](http://coptr.digipres.org/Category:Web_Crawl)

### Blogs and Scholarship

* [IIPC Blog](https://netpreserveblog.wordpress.com/)
* [Web Archiving Roundtable](https://webarchivingrt.wordpress.com/) -的Web归档圆桌会议的非正式博客 [Society of American Archivists](https://www2.archivists.org/) 由Web归档圆桌会议的成员维护.
* [The Web as History](http://www.ucl.ac.uk/ucl-press/browse-books/the-web-as-history) -一本开放源代码的书，提供了有关Web归档研究以及一些案例研究的概念性概述.
* [WS-DL Blog](https://ws-dl.blogspot.com/) -Web科学和数字图书馆研究小组的博客，介绍了各种与Web归档相关的主题，学术工作和学术旅行报告.
* [DSHR's Blog](https://blog.dshr.org/) -大卫·罗森塔尔（David Rosenthal）定期审查并总结在“数字保存”领域所做的工作.

### Mailing Lists

* [IIPC](http://netpreserve.org/about-us/iipc-mailing-list/)
* [OpenWayback](https://groups.google.com/forum/#!forum/openwayback-dev)
* [WASAPI](https://groups.google.com/forum/#!forum/wasapi-community)

### Slack

* [IIPC Slack](https://iipc.slack.com/) -问 [@netpreserve](https://twitter.com/NetPreserve) 访问.
* [Archives Unleashed Slack](https://archivesunleashed.slack.com/) - [Fill out this request form](https://docs.google.com/forms/d/e/1FAIpQLScXPIH0Ssw63yWqyMkUqHVYmz2-ItBMzHiJQ-sOlJwTA8u5AQ/viewform?usp=sf_link) 允许访问一组研究人员使用Web存档.
* [Archivers Slack](https://archivers.slack.com) - [Invite yourself](https://archivers-slack.herokuapp.com/) 跨学科的归档项目 [EDGI](https://envirodatagov.org/archiving/) 和 [Data Together](http://datatogether.org/).

### Twitter

* [@NetPreserve](https://twitter.com/NetPreserve) -IIPC官方手柄.
* [#WebArchiving](https://twitter.com/search?q=%23webarchiving)
