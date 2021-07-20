<div class="github-widget" data-repo="iipc/awesome-web-archiving"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint ignore awesome-github-->
## Awesome Web Archiving [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

网络归档是收集万维网部分的过程，以确保将信息保存在档案中，供未来的研究人员、历史学家和公众使用. 由于 Web 的庞大规模，Web 档案管理员通常使用 Web 爬虫进行自动捕获. 不断发展的 Web 标准要求归档工具不断发展，以跟上 Web 技术的变化，以确保对归档网页进行可靠且有意义的捕获和重放.




## Training/Documentation

* 网络归档概念介绍：
  * [What is a web archive?](https://youtu.be/ubDHY-ynWi0) - 来自的视频 [the UK Web Archive YouTube Channel](https://www.youtube.com/channel/UCJukhTSw8VRj-VNTpBcqWkw)
  * [Wikipedia's List of Web Archiving Initiatives](https://en.wikipedia.org/wiki/List_of_Web_archiving_initiatives)
  * [Glossary of Archive-It and Web Archiving Terms](https://support.archive-it.org/hc/en-us/articles/208111686-Glossary-of-Archive-It-and-Web-Archiving-Terms)
  * [The Web Archiving Lifecycle Model](https://archive-it.org/blog/post/announcing-the-web-archiving-life-cycle-model/)  - Web 归档生命周期模型试图将 Web 归档的技术和程序化臂整合到一个框架中，该框架将与任何寻求从 Web 归档内容的组织相关.  Archive-It 是 Internet Archive 的网络存档服务，它基于与世界各地的记忆机构的合作开发了该模型.
  * [Training materials: module for beginners (8 sessions)](https://netpreserve.org/web-archiving/training-materials/)
* WARC 标准：
  * 这 [warc-specifications](https://iipc.github.io/warc-specifications/) 官方规范的社区 HTML 版本和新提案的中心.
  * 这 [offical ISO 28500 WARC specification homepage](http://bibnum.bnf.fr/WARC/).
* 对于使用网络档案的研究人员：
  * [GLAM Workbench: Web Archives](https://glam-workbench.github.io/web-archives/) - 也可以看看 [this related blog post on 'Asking questions with web archives'](https://netpreserveblog.wordpress.com/2020/05/28/asking-questions-with-web-archives/).
  * [Archives Unleashed Toolkit documentation](https://aut.docs.archivesunleashed.org/)

## Resources for Web Publishers

当与在 Web 上发布内容以及希望确保其网站可以存档的个人或组织合作时，这些资源会有所帮助.

* [Stanford Libraries' Archivability pages](https://library.stanford.edu/projects/web-archiving/archivability)
* 这 [Archive Ready](http://archiveready.com/) 工具，用于估计网页成功存档的可能性.


## Tools & Software

这份工具和软件列表旨在简要描述一些与 Web 归档相关的最重要和最广泛使用的工具. 有关更多详细信息，我们建议您参考（并贡献给！）来自其他组的这些优秀资源：
* [Comparison of web archiving software](https://github.com/archivers-space/research/tree/master/web_archiving)
* [Awesome Website Change Monitoring](https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring)

### Acquisition

* [22120](https://github.com/c9fe/22120)  - 一种非基于 WARC 的工具，可连接到 Chrome 浏览器并存档您浏览的所有内容，使其可用于离线重播.  *（开发中）*
* [ArchiveBox](https://github.com/pirate/ArchiveBox)  - 使用 wget、Chrome headless 和其他方法（以前称为“Bookmark Archiver”）维护来自 RSS 提要、书签和链接的附加存档的工具.  *（开发中）*
* [archivenow](https://github.com/oduwsdl/archivenow) - 一种 [Python library](http://ws-dl.blogspot.com/2017/02/2017-02-22-archive-now-archivenow.html) 将网络资源推送到按需网络档案中.  *（稳定的）*
* [ArchiveWeb.Page](https://archiveweb.page)  - 适用于 Chrome 和其他基于 Chromium 的浏览器的插件，可让您以交互方式存档网页、重放它们并将它们导出为 WARC 数据. 也可用作基于 Electron 的桌面应用程序.
* [Browsertrix Crawler](https://github.com/webrecorder/browsertrix-crawler) - 基于 Chrome 的高保真抓取系统，旨在在单个 Docker 容器中运行复杂的、可定制的基于浏览器的抓取.
* [Brozzler](https://github.com/internetarchive/brozzler)  - 一种分布式网络爬虫（爬虫），它使用真实的浏览器（Chrome 或 Chromium）来获取页面和嵌入的 url 并提取链接.  *（稳定的）*
* [Cairn](https://github.com/wabarc/cairn)  - 用于保存网页的 npm 包和 CLI 工具.  *（稳定的）*
* [Chronicler](https://github.com/CGamesPlay/chronicler)  - 具有记录和回放功能的网络浏览器.  *（开发中）*
* [Crawl](https://git.autistici.org/ale/crawl)  - 一个简单的 Golang 网络爬虫.  *（稳定的）*
* [crocoite](https://github.com/promyloph/crocoite)  - 使用无头 Google Chrome/Chromium 抓取网站并将资源、静态 DOM 快照和页面截图保存到 WARC 文件.  *（开发中）*
* [F(b)arc](https://github.com/justinlittman/fbarc) - 用于归档数据的命令行工具和 Python 库 [Facebook](https://www.facebook.com/) 使用 [Graph API](https://developers.facebook.com/docs/graph-api) .  *（稳定的）*
* [freeze-dry](https://github.com/WebMemex/freeze-dry)  - 将页面转换为静态、自包含的 HTML 文档的 JavaScript 库； 对浏览器扩展很有用.  *（开发中）*
* [grab-site](https://github.com/ArchiveTeam/grab-site)  - 档案管理员的网络爬虫：WARC 输出、所有爬虫的仪表板、动态忽略模式.  *（稳定的）*
* [Heritrix](https://github.com/internetarchive/heritrix3/wiki)  - 一个开源的、可扩展的、网络规模的、档案质量的网络爬虫.  *（稳定的）*
  * [Heritrix Walkthrough](https://github.com/web-archive-group/heritrix-walkthrough) *（开发中）*
* [html2warc](https://github.com/steffenfritz/html2warc)  - 将离线数据转换为单个 WARC 文件的简单脚本.  *（稳定的）*
* [HTTrack](http://www.httrack.com/)  - 一个开源网站复制实用程序.  *（稳定的）*
* [monolith](https://github.com/Y2Z/monolith)  - 将网页保存为单个 HTML 文件的 CLI 工具.  *（稳定的）*
* [Obelisk](https://github.com/go-shiori/obelisk)  - Go 包和 CLI 工具，用于将网页保存为单个 HTML 文件.  *（稳定的）*
* [SingleFile](https://github.com/gildas-lormeau/SingleFile)  - Firefox/Chrome 浏览器扩展和 CLI 工具，可将完整页面的忠实副本保存为单个 HTML 文件.  *（稳定的）*
* [SiteStory](http://mementoweb.github.com/SiteStory/)  - 一个交易档案，它有选择地捕获和存储在 Web 客户端（浏览器）和 Web 服务器之间发生的交易.  *（稳定的）*
* [Social Feed Manager](https://gwu-libraries.github.io/sfm-ui/)  - 使用户能够从 Twitter、Tumblr、Flickr 和新浪微博公共 API 创建社交媒体收藏的开源软件.  *（稳定的）*
* [Squidwarc](https://github.com/N0taN3rd/Squidwarc) - 一个 [open source, high-fidelity, page interacting](http://ws-dl.blogspot.com/2017/07/2017-07-24-replacing-heritrix-with.html) archival crawler that uses Chrome or Chrome Headless directly. *(In Development)*
* [StormCrawler](http://stormcrawler.net/)  - 用于在 Apache Storm 上构建低延迟、可扩展的网络爬虫的资源集合.  *（稳定的）*
* [twarc](https://github.com/docnow/twarc)  - 用于归档 Twitter JSON 数据的命令行工具和 Python 库.  *（稳定的）*
* [WAIL](https://github.com/machawk1/wail) - 在多个 Web 归档工具之上的图形用户界面 (GUI)，旨在用作任何人保存和重放网页的简便方法； [Python](https://machawk1.github.io/wail/), [Electron](https://github.com/n0tan3rd/wail) .  *（稳定的）*
* [Warcprox](https://github.com/internetarchive/warcprox)  - 编写 WARC 的 MITM HTTP/S 代理.  *（稳定的）*
* [WARCreate](http://matkelly.com/warcreate/) - 一种 [Google Chrome](https://www.google.com/intl/en/chrome/browser/) 用于将单个网页或网站存档到 WARC 文件的扩展.  *（稳定的）*
* [Warcworker](https://github.com/peterk/warcworker)  - 基于 Squidwarc 的开源、dockerized、排队、高保真 Web 归档器，具有简单的 Web GUI.  *（稳定的）*
* [Web2Warc](https://github.com/helgeho/Web2Warc)  - 易于使用且高度可定制的爬虫，使任何人都可以创建自己的小型 Web 档案 (WARC/CDX).  *（稳定的）*
* [Web Curator Tool](https://webcuratortool.org)  - 用于选择性 Web 归档的开源工作流管理.  *（稳定的）*
* [WebMemex](https://github.com/WebMemex)  - Firefox 和 Chrome 浏览器扩展，可让您存档访问的网页.  *（开发中）*
* [Webrecorder](https://webrecorder.io/)  - 为您浏览的任何网站创建高保真交互式录音.  *（稳定的）*
* [Wget](http://www.gnu.org/software/wget/) - 一个开源文件检索实用程序 [version 1.14 supports writing warcs](http://www.archiveteam.org/index.php?title=Wget_with_WARC_output) .  *（稳定的）*
* [Wget-lua](https://github.com/alard/wget-lua)  - 带有 Lua 扩展的 Wget.  *（稳定的）*
* [Wpull](https://github.com/chfoo/wpull)  - 与 Wget 兼容（或重制/克隆/替换/替代）的网络下载器和爬虫.  *（稳定的）*

### Replay

* [InterPlanetary Wayback (ipwb)](https://github.com/oduwsdl/ipwb) - 使用 Web Archive (WARC) 索引和重播 [IPFS](https://ipfs.io/).
* [OpenWayback](https://github.com/iipc/openwayback/)  - 开源项目旨在开发 Wayback Machine，这是全球网络档案馆用来在用户浏览器中播放存档网站的关键软件.  *（稳定的）*
* [PyWb](https://github.com/ikreymer/pywb)  - 网络档案重放工具的 Python（2 和 3）实现，有时也称为“Wayback Machine”.  *（稳定的）*
* [Reconstructive](https://oduwsdl.github.io/Reconstructive/) - Reconstructive 是一个 ServiceWorker 模块，用于通过将资源请求重新路由到相应的存档副本 (JavaScript) 来重建复合纪念品的客户端.
* [ReplayWeb.Page](https://replayweb.page/) - 基于浏览器的、完全客户端的本地和远程 WARC 文件重播引擎.

### Search & Discovery

* [Mink](https://github.com/machawk1/mink) - 一种 [Google Chrome](https://www.google.com/intl/en/chrome/) 用于在浏览和集成实时存档网络导航时查询 Memento 聚合器的扩展.  *（稳定的）*
* [playback](https://github.com/wabarc/playback) - 用于搜索存档网页的工具包 [Internet Archive](https://web.archive.org), [archive.today](https://archive.today), [Memento](http://timetravel.mementoweb.org) 超越.  *（开发中）*
* [SecurityTrails](https://securitytrails.com/)  - 基于 Web 的 WHOIS 和 DNS 记录存档. 免费提供 REST API. 
* [Tempas v1](http://tempas.L3S.de/v1) - 基于时间的网络档案搜索 [Delicious](https://en.wikipedia.org/wiki/Delicious_(website) ) 标签.  *（稳定的）*
* [Tempas v2](http://tempas.L3S.de/v2) - 基于从 1996 年到 2013 年从德国网络中提取的链接和锚文本的临时网络档案搜索（结果不限于德语页面，例如， [Obama@2005-2009 in Tempas](http://tempas.l3s.de/v2/query?q=obama&from=2005&to=2009) ）.  *（稳定的）*
* [webarchive-discovery](https://github.com/ukwa/webarchive-discovery)  - WARC 和 ARC 全文索引和发现工具，以及许多能够使用下面显示的索引的相关工具.  *（稳定的）*
  * [Shine](https://github.com/ukwa/shine) - 原型网络档案探索用户界面，与研究人员一起开发，作为 [Big UK Domain Data for the Arts and Humanities project](https://buddah.projects.history.ac.uk/) .  *（稳定的）*
  * [SolrWayback](https://github.com/netarchivesuite/solrwayback)  - 具有自由文本搜索和内置播放引擎的后端 Java 和前端 VUE JS 项目. 要求 Warc 文件已被 Warc-Indexer 索引.  Web 应用程序还具有广泛的数据可视化工具和数据导出工具，可用于整个 Webarchive. [SolrWayback 4 Bundle release](https://github.com/netarchivesuite/solrwayback/releases) 在易于安装的开箱即用解决方案中包含所有软件和依赖项.
  * [Warclight](https://github.com/archivesunleashed/warclight)  - 基于 Project Blacklight 的 Rails 引擎，支持发现以 WARC 和 ARC 格式保存的 Web 档案.  *（开发中）*
  * [Wasp](https://github.com/webis-de/wasp) - 一个功能齐全的个人原型 [web archive and search system](http://ceur-ws.org/Vol-2167/paper6.pdf) .  *（开发中）*
  * 构建前端的其他可能选项在`webarchive-discovery` wiki 中列出， [here](https://github.com/ukwa/webarchive-discovery/wiki/Front-ends).

### Utilities

* [ArchiveTools](https://github.com/recrm/ArchiveTools) - 用于提取 WARC 文件并与之交互的工具集合 (Python).
* [gowarcserver](https://github.com/nlnwa/gowarcserver) - [BadgerDB](https://github.com/dgraph-io/badger)基于捕获索引 (CDX) 和 WARC 记录服务器，用于索引和提供 WARC 文件 (Go).
* [har2warc](https://github.com/webrecorder/har2warc) - 转换 HTTP 档案 (HAR) -&gt; 网页档案 (WARC) 格式 (Python).
* [httpreserve.info](http://httpreserve.info/)  - 返回网页状态或将其保存到 Internet Archive 的服务. 使用 GET（Golang 包）通过浏览器或命令行通过 CURL 返回 JSON.  *（稳定的）*
* [HTTPreserve Workbench](https://github.com/httpreserve/workbench)  - 描述以简单 JSON 输出编码的网页状态的工具和 API，描述当前状态，以及 wayback.org 上最早和最新的链接. 将网页保存到 Internet Archive. 审核 URI 列表并输出包含上述数据的 CSV (Golang).  *（开发中）*
* [httrack2warc](https://github.com/nla/httrack2warc) - 将 HTTrack 档案转换为 WARC 格式 (Java).
* [MementoMap](https://github.com/oduwsdl/MementoMap)  - 总结网络档案馆藏的工具 (Python).  *（开发中）*
* [MemGator](https://github.com/oduwsdl/MemGator)  - Memento Aggregator CLI 和服务器（Golang）.  *（稳定的）*
* [node-cdxj](https://github.com/N0taN3rd/node-cdxj) - [CDXJ](https://github.com/oduwsdl/ORS/wiki/CDXJ) 文件解析器（Node.js）.  *（稳定的）*
* [OutbackCDX](https://github.com/nla/outbackcdx)  - 基于 RocksDB 的捕获索引 (CDX) 服务器，支持增量更新和压缩. 可用作 OpenWayback、PyWb 和的后端 [Heritrix](https://github.com/ukwa/ukwa-heritrix/blob/master/src/main/java/uk/bl/wap/modules/uriuniqfilters/OutbackCDXRecentlySeenUriUniqFilter.java) .  *（稳定的）*
* [py-wasapi-client](https://github.com/unt-libraries/py-wasapi-client)  - 从 WASAPI (Python) 下载爬网的命令行应用程序.  *（稳定的）*
* [tikalinkextract](https://github.com/httpreserve/tikalinkextract)  - 从可以被 Apache Tika（Golang、Apache Tika 服务器）解析的文档类型的文件夹中提取超链接作为 Web 归档的种子.  *（开发中）*
* [wasapi-downloader](https://github.com/sul-dlss/wasapi-downloader)  - 从 WASAPI 下载爬虫的 Java 命令行应用程序.  *（稳定的）*
* [WarcPartitioner](https://github.com/helgeho/WarcPartitioner)  - 按 MIME 类型和年份分区 (W)ARC 文件.  *（稳定的）*
* [webarchive-indexing](https://github.com/ikreymer/webarchive-indexing) - 对 Hadoop、EMR 或本地文件系统上的 WARC/ARC 文件进行批量索引的工具.
* [wikiteam](https://github.com/WikiTeam/wikiteam)  - 用于下载和保存维基的工具.  *（稳定的）*

### WARC I/O Libraries

* [HadoopConcatGz](https://github.com/helgeho/HadoopConcatGz)  - 用于连接 GZIP 文件（和 `*.warc.gz`）的可拆分 Hadoop InputFormat.  *（稳定的）*
* [jwarc](https://github.com/iipc/jwarc) - 使用类型安全 API (Java) 读取和写入 WARC 文件.
* [Jwat](https://sbforge.org/display/JWAT/JWAT)  - 用于读取/写入/验证 WARC/ARC/GZIP 文件 (Java) 的库和工具.  *（稳定的）*
* [node-warc](https://github.com/N0taN3rd/node-warc) - 使用任一解析 WARC 文件或创建 WARC 文件 [Electron](https://electron.atom.io/) 或者 [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface)  （节点.js）.  *（稳定的）*
* [Warcat](https://github.com/chfoo/warcat)  - 用于处理 Web ARChive (WARC) 文件 (Python) 的工具和库.  *（稳定的）*
* [warcio](https://github.com/webrecorder/warcio) - 用于快速 Web 存档 IO (Python) 的流式 WARC/ARC 库.
* [warctools](https://github.com/internetarchive/warctools) - 用于处理 ARC 和 WARC 文件的库 (Python).
* [webarchive](https://github.com/richardlehane/webarchive) - ARC 和 WARC webarchive 格式 (Golang) 的 Golang 阅读器.

### Analysis

* [ArchiveSpark](https://github.com/helgeho/ArchiveSpark)  - 用于 Web 档案的 Apache Spark 框架（不仅是），可以轻松进行数据处理、提取和派生.  *（稳定的）*
* [Archives Unleashed Notebooks](https://github.com/archivesunleashed/notebooks)  - 使用 Archives Unleashed Toolkit 处理网络档案的笔记本，以及由 Archives Unleashed Toolkit 生成的衍生工具.  *（稳定的）*
* [Archives Unleashed Toolkit](https://github.com/archivesunleashed/aut)  - Archives Unleashed Toolkit (AUT) 是一个开源平台，用于使用 Apache Spark 分析 Web 档案.  *（稳定的）*
* [Tweet Archvies Unleashed Toolkit](https://github.com/archivesunleashed/twut)  - 一个开源工具包，用于使用 Apache Spark 分析面向行的 JSON Twitter 档案.  *（开发中）*

### Quality Assurance

* [Chrome Check My Links](https://chrome.google.com/webstore/detail/check-my-links/ojkcdipcgfaekbeaelaapakgnjflfglf) - 浏览器扩展：具有更多选项的链接检查器.
* [Chrome link checker](https://chrome.google.com/webstore/detail/link-checker/aibjbgmpmnidnmagaefhmcjhadpffaoi) - 浏览器扩展：基本链接检查器.
* [Chrome link gopher](https://chrome.google.com/webstore/detail/bpjdkodgnbfalgghnbeggfbfjpcfamkf/publish-accepted?hl=en-US&gl=US) - 浏览器扩展：页面上的链接收割机.
* [Chrome Open Multiple URLs](https://chrome.google.com/webstore/detail/open-multiple-urls/oifijhaokejakekmnjmphonojcfkpbbh?hl=de) - 浏览器扩展：打开多个 URL 并从文本中提取 URL.
* [Chrome Revolver](https://chrome.google.com/webstore/detail/revolver-tabs/dlknooajieciikpedpldejhhijacnbda) - 浏览器扩展：在浏览器选项卡之间切换.
* [FlameShot](https://github.com/lupoDharkael/flameshot) - Screen capture and annotation on Ubuntu.
* [PlayOnLinux](https://www.playonlinux.com/en/) - 用于在 Ubuntu 上运行 Xenu 和 Notepad++.
* [PlayOnMac](https://www.playonmac.com/en/) - 用于在 macOS 上运行 Xenu 和 Notepad++.
* [Windows Snipping Tool](https://support.microsoft.com/en-gb/help/13776/windows-use-snipping-tool-to-capture-screenshots)  - 用于部分屏幕捕获和注释的 Windows 内置. 在 macOS 上，您可以使用 Command + Shift + 4（用于截取部分屏幕的键盘快捷键）.
* [WineBottler](http://winebottler.kronenberg.org/) - 用于在 macOS 上运行 Xenu 和 Notepad++.
* [xDoTool](https://github.com/jordansissel/xdotool) - 在 Ubuntu 上单击自动化.
* [Xenu](http://home.snafu.de/tilman/xenulink.html) - 适用于 Windows 的桌面链接检查器.

### Curation

* [Zotero Robust Links Extension](https://robustlinks.mementoweb.org/zotero/) - 一种 [Zotero](https://www.zotero.org/) 提交到 Web 档案并从中读取的扩展. 来源 [on GitHub](https://github.com/lanl/Zotero-Robust-Links-Extension) . 取代 [leonkt/zotero-memento](https://github.com/leonkt/zotero-memento).

## Community Resources

### Other Awesome Lists

* [Web Archiving Community](https://github.com/pirate/ArchiveBox/wiki/Web-Archiving-Community)
* [Awesome Memento](https://github.com/machawk1/awesome-memento)
* [The WARC Ecosystem](http://www.archiveteam.org/index.php?title=The_WARC_Ecosystem)
* [The Web Crawl section of COPTR](http://coptr.digipres.org/Category:Web_Crawl)

### Blogs and Scholarship

* [IIPC Blog](https://netpreserveblog.wordpress.com/)
* [Web Archiving Roundtable](https://webarchivingrt.wordpress.com/) - Web Archiving Roundtable 的非官方博客 [Society of American Archivists](https://www2.archivists.org/) 由 Web Archiving Roundtable 的成员维护.
* [The Web as History](http://www.ucl.ac.uk/ucl-press/browse-books/the-web-as-history) - 一本开源书籍，提供了 Web 归档研究的概念概述以及几个案例研究.
* [WS-DL Blog](https://ws-dl.blogspot.com/) - 网络科学和数字图书馆研究小组关于各种网络架构相关主题、学术工作和学术旅行报告的博客.
* [DSHR's Blog](https://blog.dshr.org/) - David Rosenthal 定期审查和总结在数字保存领域所做的工作.
* [UK Web Archive Blog](https://blogs.bl.uk/webarchive/)

### Mailing Lists

* [IIPC](http://netpreserve.org/about-us/iipc-mailing-list/)
* [OpenWayback](https://groups.google.com/g/openwayback-dev)
* [WASAPI](https://groups.google.com/g/wasapi-community)

### Slack

* [IIPC Slack](https://iipc.slack.com/) - 问 [@netpreserve](https://twitter.com/NetPreserve?s=20) 访问.
* [Archives Unleashed Slack](https://archivesunleashed.slack.com/) - [Fill out this request form](https://docs.google.com/forms/d/e/1FAIpQLScXPIH0Ssw63yWqyMkUqHVYmz2-ItBMzHiJQ-sOlJwTA8u5AQ/viewform?usp=sf_link) 用于访问使用网络档案的研究人员组.
* [Archivers Slack](https://archivers.slack.com) - [Invite yourself](https://archivers-slack.herokuapp.com/) 进行多学科努力，以归档与以下机构有关联的项目 [EDGI](https://envirodatagov.org/archiving/) 和 [Data Together](http://datatogether.org/).

### Twitter

* [@NetPreserve](https://twitter.com/NetPreserve) - 官方 IIPC 句柄.
* [@WebSciDL](https://twitter.com/WebSciDL) - ODU 网络科学和数字图书馆研究组.
* [#WebArchiving](https://twitter.com/search?q=%23webarchiving)
* [#WebArchiveWednesday](https://twitter.com/hashtag/webarchivewednesday)
