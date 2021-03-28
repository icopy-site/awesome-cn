<div class="github-widget" data-repo="awesome-selfhosted/awesome-selfhosted"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome-Selfhosted

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![](https://img.shields.io/travis/awesome-selfhosted/awesome-selfhosted/master?label=link%20checks)](https://github.com/awesome-selfhosted/awesome-selfhosted/issues/2266)

自我托管是在本地托管和管理应用程序的一种做法，而不是从 [SaaSS](https://www.gnu.org/philosophy/who-does-that-server-really-serve.html) 提供者.

这是一个清单 [Free](https://en.wikipedia.org/wiki/Free_software) 软件 [network services](https://en.wikipedia.org/wiki/Network_service) 和 [web applications](https://en.wikipedia.org/wiki/Web_application) 可以在本地托管. 非免费软件列在 [Non-Free](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/non-free.md) 页.

See [Contributing](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/.github/CONTRIBUTING.md).

--------------------

-软件清单

--------------------

<!-- BEGIN SOFTWARE LIST -->

## Analytics

**[`^        back to top        ^`](#)**

_有关个人分析/仪表板，请参阅 [Personal Dashboards](#personal-dashboards)_

_有关其他所有内容，请参见 [awesome-analytics](https://github.com/onurakpolat/awesome-analytics)_


## Archiving and Digital Preservation (DP)

**[`^        back to top        ^`](#)**

_Some [Content Management System](#content-management-systems-cms) 解决方案还具有存档和数字保存功能.

- [Access to Memory (AtoM)](https://www.accesstomemory.org/)  -基于Web的开源应用程序，用于在多语言，多存储库环境中进行基于标准的存档描述和访问.  （[Demo](https://demo.accesstomemory.org/), [Source Code](https://github.com/artefactual/atom)）`AGPL-3.0-only``PHP`
- [Archivematica](https://www.archivematica.org/)  -成熟的数字保存系统，旨在维护基于标准的对数字对象集合的长期访问.  （[Demo](http://sandbox.archivematica.org/administration/accounts/login/), [Source Code](https://github.com/artefactual/archivematica)）`AGPL-3.0-only``Python`
- [ArchiveBox](https://archivebox.io/)  -自托管的“回溯机器”，可根据您的书签，浏览历史记录，RSS提要或其他来源创建网站的HTML和屏幕快照存档.  （[Source Code](https://github.com/pirate/bookmark-archiver)）和Python
- [ArchivesSpace](https://archivesspace.org/)  -档案信息管理应用程序，用于管理和提供对档案，手稿和数字对象的Web访问.  （[Demo](https://archivesspace.org/application/demo/), [Source Code](https://github.com/archivesspace/archivesspace)）`ECL-2.0``Ruby`
- [Collective Access: Providence](http://collectiveaccess.org/)  -高度可配置的基于Web的框架，用于管理，描述和发现数字和物理集合，支持各种元数据标准，数据类型和媒体格式.  （[Source Code](https://github.com/collectiveaccess/providence)）`仅GPL-3.0``PHP`
- [CKAN](https://ckan.org)  -CKAN是用于制作开放数据网站的工具.  （[Source Code](https://github.com/ckan/ckan)）`AGPL-3.0``Python`

## Automation

**[`^        back to top        ^`](#)**

_也可以看看 [Internet of Things (IoT)](#internet-of-things-iot)_

- [Accelerated Text](https://github.com/tokenmill/accelerated-text)  -自动生成措辞和结构各异的数据的多种自然语言描述.  Apache-2.0 Java
- [Actionsflow](https://github.com/actionsflow/actionsflow)  `⚠`-开发人员的免费Zapier / IFTTT替代方案，可基于Github动作使您的工作流程自动化. 麻省理工学院Docker / Nodejs
- [ActiveWorkflow](https://github.com/automaticmode/active_workflow)  -基于软件代理的智能流程和工作流自动化平台. 麻省理工学院Ruby
- [Alltube](http://www.alltubedownload.net) -Web界面 [youtube-dl](https://github.com/rg3/youtube-dl)，用于从中下载视频和音频的程序 [more than 100 websites](https://rg3.github.io/youtube-dl/supportedsites.html). ([Source Code](https://github.com/Rudloff/alltube)）`GPL-3.0``PHP`
- [AmIUnique](https://amiunique.org/)  -了解您在互联网上的身份（浏览器指纹识别工具）.  （[Source Code](https://github.com/DIVERSIFY-project/amiunique)）MIT Java
- [Beehive](https://github.com/muesli/beehive)  -灵活的事件和代理系统，使您可以创建自己的代理，以执行由事件和过滤器触发的自动化任务.  AGPL-3.0`Go
- [betanin](https://github.com/sentriz/betanin/)  -您的洪流客户端和音乐播放器的中间音乐人. 基于beets.io，类似于Sonarr和Radarr.  GPL-3.0 Python
- [CouchPotato](https://couchpota.to/)  -CouchPotato是用于电影的自动视频库管理器. 您可以根据自己的需求自动搜索，下载和处理torrent / nzb.  （[Source Code](https://github.com/CouchPotato/CouchPotatoServer)）`GPL-3.0`` Python`
- [Episodes](https://github.com/guptachetan1997/Episodes)  `⚠`-使用django，bootstrap4构建的自托管电视节目剧集跟踪器和推荐器. 麻省理工学院Python
- [feed2toot](https://feed2toot.readthedocs.io/)  -Feed2toot解析RSS提要，提取最后一个条目并将其发送给Mastodon.  （[Source Code](https://gitlab.com/chaica/feed2toot)）`GPL-3.0`` Python`
- [feedmixer](https://github.com/cristoper/feedmixer)  -FeedMixer是WSGI（Python3）微型Web服务，它接收供稿URL列表并返回一个新的供稿，该供稿由每个给定供稿（返回Atom，RSS或JSON）中的最新n个条目组成.  （[Demo](https://mretc.net/feedmixer/json?f=http://hnrss.org/newest&f=http://americancynic.net/atom.xml&n=1)）`WTFPL``Python`
- [Gekko](https://gekko.wizb.it/)  -Gekko是比特币TA交易和回测机器人，支持多种交易所和加密货币.  （[Source Code](https://github.com/askmike/gekko)）`与`Node.js`
- [Headphones](https://github.com/rembo10/headphones)  -NZB和Torrent的自动音乐下载器，使用Python编写. 它支持SABnzbd，NZBget，Transmission，µTorrent，Deluge和Blackhole.  GPL-3.0 Python
- [Healthchecks](https://healthchecks.io/)  -侦听ping并在ping迟到时发送警报的Django应用.  （[Source Code](https://github.com/healthchecks/healthchecks)）`BSD-3-Clause`` Python`
- [homebank-converter](https://github.com/Binnette/homebank-converter)  -将出口银行文件转换为兼容的Homebank CSV的Web应用程序.  （[Demo](http://binnette.github.io/homebank-converter/)）AGPL-3.0 HTML5
- [HRConvert2](https://github.com/zelon88/HRConvert2)  -具有基于会话的身份验证，自动临时文件维护和日志记录功能的拖放式文件转换服务器.  `GPL-3.0``PHP`
- [Huginn](https://github.com/huginn/huginn)  -允许您建立代理进行监视并代表您采取行动. 麻省理工学院Ruby
- [Kibitzr](https://kibitzr.github.io)  -具有强大集成功能的轻量级个人Web助手.  （[Source Code](https://github.com/kibitzr/kibitzr)）和Python
- [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian)  `⚠`-LazyLibrarian是一个程序，可以跟踪作者并获取满足您所有数字阅读需求的元数据. 它结合使用了Goodreads Librarything和可选的GoogleBooks作为作者信息和书籍信息的来源.  GPL-3.0 Python
- [Leon](https://getleon.ai)  -可以驻留在您的服务器上的开源个人助理.  （[Demo](https://www.youtube.com/watch?v=p7GRGiicO1c), [Source Code](https://github.com/leon-ai/leon)）`MIT`` Node.js`
- [Lidarr](https://lidarr.audio/)  -Lidarr是Usenet和BitTorrent用户的音乐收藏经理.  （[Source Code](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#`
- [Medusa](https://github.com/pymedusa/SickRage)  -用于电视节目的自动视频库管理器. 它会监视您喜欢的节目的新剧集，并在它们发布后发挥其神奇作用.  GPL-3.0 Python
- [MeTube](https://github.com/alexta69/metube)  -youtube-dl的Web GUI，具有播放列表支持. 允许从数十个网站下载视频.  `AGPL-3.0``Python / Nodejs / Docker`
- [n8n](https://n8n.io/)  -免费的基于节点的工作流自动化工具. 轻松自动化跨不同服务的任务.  （[Source Code](https://github.com/n8n-io/n8n)）`Apache-2.0`` Nodejs`
- [nefarious](https://github.com/lardbit/nefarious)  -自动下载电影和电视节目的Web应用程序.  GPL-3.0 Python
- [Patrowl](https://github.com/Patrowl/PatrowlManager)  -开源，智能和可扩展的安全操作流程平台.  AGPL-3.0 Python
- [Podgrab](https://github.com/akhilrex/podgrab)  -轻量级播客管理器和自动播客情节下载器. 它将监视您的播客，并在新节目上线时自动下载.  GPL-3.0`Docker / Go`
- [pyLoad](https://pyload.net/)  -轻量级，可自定义且可远程管理的下载器，用于一键式托管网站（如Rapidshare.com或upload.to）.  （[Source Code](https://github.com/pyload/pyload)）`GPL-3.0`` Python`
- [Radarr](https://radarr.video/)  -Radarr是Sonarr的独立分支，经过重新设计，可以通过Usenet和Couchpotato的BitTorrent自动下载电影.  （[Source Code](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#`
- [StackStorm](https://stackstorm.com)  -StackStorm（又称“ IFTTT for Ops”）是事件驱动的自动化，可进行自动修复，安全响应，故障排除，部署等. 包括规则引擎，工作流，具有6000多个动作的160个集成包和ChatOps.  （[Source Code](https://github.com/StackStorm/st2)）`Apache-2.0`` Python`
- [SickRage](http://sickrage.github.io/)  -SickRage是用于电视节目的自动视频库管理器. 您可以根据自己的需求自动搜索，下载和处理torrent / nzb.  （[Source Code](https://github.com/SickRage/SickRage)）`GPL-3.0`` Python`
- [SiteInspector](https://www.getsiteinspector.com/)  -基于Web的工具，用于在网站上捕获拼写错误，语法错误，链接断开和其他错误.  （[Demo](https://demo.getsiteinspector.com/reports), [Source Code](https://github.com/siteinspector/siteinspector)）`AGPL-3.0``Ruby`
- [Sonarr](https://sonarr.tv/)  -Usenet和BitTorrent的自动电视节目下载和管理器. 它可以抓取，排序和重命名新的情节，并在质量更好的格式可用时自动升级已下载文件的质量.  （[Source Code](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#`
- [µTask](https://github.com/ovh/utask)  -µTask是一个自动化引擎，用于建模和执行yaml中声明的业务流程.  BSD-3-Clause`Go
- [WebUI-aria2](https://github.com/ziahamza/webui-aria2)  -与aria2下载器进行交互的界面. 使用非常简单，只需在任何Web浏览器中下载并打开index.html.  （[Demo](http://ziahamza.github.io/webui-aria2/)）`MIT`` HTML5`
- [YoutubeDL-Material](https://github.com/Tzahi12345/YoutubeDL-Material)  -Material Design启发了基于youtube-dl的YouTube下载器. 支持播放列表，质量选择，搜索，暗模式等等，所有这些都具有简洁现代的设计.  MIT`Nodejs`
- [Zenbot 3](https://github.com/carlos8f/zenbot)  -Zenbot是一款轻量级，可扩展的人工智能交易机器人，适用于比特币，以太坊，Litecoin等.  MIT`Node.js`
- [ZeroQueue](https://github.com/thezeroqueue/zeroqueue)  -低代码队列管理系统，可让您运行任何作业的计划作业.  GPL-3.0 Node.js

## Blogging Platforms

**[`^        back to top        ^`](#)**

_也可以看看 [Static Site Generators](#static-site-generators), [Content Management Systems](#content-management-systems-cms) 和 [WeblogMatrix](http://www.weblogmatrix.org/)_

- [Antville](https://antville.org)  -免费的开源项目，旨在开发高性能，功能丰富的Weblog托管软件.  （[Source Code](https://github.com/antville/antville)）Apache-2.0 Javascript
- [Blog](https://github.com/m1k1o/blog)  -Facebook风格的博客. 免费，轻巧，单用户且易于安装.  （[Demo](https://blog.m1k1o.net/)）`GPL-3.0``PHP`
 -Blogotext-用PHP编写并使用SQLite的免费博客引擎. 这为您提供了安装过程中无与伦比的简便性和出色的性能.  （[Source Code](https://github.com/timovn/blogotext)）和PHP`
- [Bludit](https://www.bludit.com/)  `⚠`-简单的应用程序，可在几秒钟内构建站点或博客.  Bludit使用平面文件（JSON格式的文本文件）存储帖子和页面.  （[Demo](https://demo.bludit.com/), [Source Code](https://github.com/dignajar/bludit)）和PHP`
- [Cadmus](https://github.com/liamdemafelix/cadmus)  -Cadmus是Markdown支持的极其轻量级的平面文件博客平台. 麻省理工学院PHP
- [Canvas](https://trycanvas.app/)  -Laravel发布平台.  （[Source Code](https://github.com/cnvs/canvas)）和PHP`
- [Chyrp Lite](http://chyrplite.net)  -超赞，超轻量级的博客引擎.  （[Source Code](https://github.com/xenocrat/chyrp-lite)）`BSD-3-Clause``PHP`
- [Dante Stories](https://dante-stories.herokuapp.com/)  -使用Ruby on Rails构建的自托管中型平台.  （[Source Code](https://github.com/michelson/dante-stories)）`MIT`` Ruby`
- [Dotclear](http://dotclear.org/)  -控制您的博客.  （[Source Code](https://hg.dotclear.org/dotclear)）`GPL-2.0``PHP`
- [Formtools](https://formtools.org/)  -强大，灵活，免费和开放源代码的PHP / MySQL脚本，用于管理您的表单和数据.  （[Source Code](https://github.com/formtools)）`GPL-2.0``PHP`
- [Ghost](https://ghost.org/)  -只是一个博客平台.  （[Source Code](https://github.com/TryGhost/Ghost)）`与`Node.js`
- [Hexo](https://hexo.io/)  -由Node.js提供支持的快速，简单且功能强大的博客框架.  （[Source Code](https://github.com/hexojs/hexo)）`与`Node.js`
- [Hotglue](https://hotglue.me/)  -手绘CMS，可直接在网络浏览器中构建网站. 它使用平面文件进行存储，并提供直观的GUI.  （[Demo](https://hotglue.me/demo/), [Source Code](https://github.com/k0a1a/hotglue2)）`GPL-3.0``PHP`
- [htmly](https://www.htmly.com/)  -无数据库博客平台（平面文件博客）.  （[Demo](https://www.htmly.com/demo/), [Source Code](https://github.com/danpros/htmly)）`GPL-2.0``PHP`
- [Known](https://withknown.com/)  -您所有内容的单一网站.  （[Source Code](https://github.com/idno/idno)）`Apache-2.0``PHP`
- [Plume](https://joinplu.me/)  -基于ActivityPub的联合博客引擎.  （[Source Code](https://github.com/Plume-org/Plume)）`AGPL-3.0``Rust`
- [PluXml](http://www.pluxml.org/)  -基于XML的Blog / CMS平台.  （[Source Code](https://github.com/pluxml/PluXml)）`GPL-1.0``PHP`


## Bookmarks and Link Sharing

**[`^        back to top        ^`](#)**

- [dyu/bookmarks](https://github.com/dyu/bookmarks)  -由leveldb和uWebSockets提供支持的单线程/进程书签应用程序. 支持从Delicious和Chrome导入.  （[Demo](https://dyuproject.com/bookmarks/)）Apache-2.0`` Java`
- [Espial](https://github.com/jonschoning/espial)  -一个基于Web的开源书签服务器.  `AGPL-3.0``Haskell`
- [Firefox Account Server](https://mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html)  -这使您可以托管自己的Firefox帐户服务器.  （[Source Code](https://github.com/mozilla/fxa)）`MPL-2.0`` Nodejs，Java`
  - [Firefox Sync Server](https://github.com/mozilla-services/syncserver)  -同步Firefox书签，密码，历史记录，标签，首选项.  MPL-2.0 Python
- [Geekmarks](https://geekmarks.dmitryfrank.com/)  -个人书签服务侧重于使用分层标签的速度和组织.  （[Source Code](https://github.com/dimonomid/geekmarks)）`BSD-2-Clause``Go`
- [golinks](https://github.com/prologic/golinks)  -Web应用程序，通过将Web浏览器的默认搜索引擎指向正在运行的实例，您可以创建智能书签，命令和别名. 类似于bunny1或yubnub.  （[Demo](https://search.mills.io)）`MIT`` Go`
- [Hackershare](https://github.com/hackershare/hackershare)  -黑客社交书签网站.  （[Demo](https://hackershare.dev)）`MIT`` Ruby`
- [linkding](https://github.com/sissbruecker/linkding)  -通过快速干净的UI最小化书签管理. 通过Docker进行简单安装，可以在您的Raspberry Pi上运行.  （[Demo](https://demo.linkding.link/)) `MIT` `Docker/Python/Nodejs`
- [LinkAce](https://www.linkace.org/)  -具有自动备份到Internet存档，链接监视和完整REST API的书签存档. 安装是通过Docker或简单的PHP应用程序完成的.  （[Demo](https://demo.linkace.org/), [Source Code](https://github.com/Kovah/LinkAce/)）`GPL-3.0``PHP`
- [Lobsters](https://lobste.rs)  -运行您自己的链接聚合站点.  （[Source Code](https://github.com/jcs/lobsters)）`BSD-3-Clause``Ruby`
- [No Fuss Bookmarks](http://nofussbm.herokuapp.com/signup.html)  -非常简单的软件和服务，用于存储专门为黑客设计的书签（不需要精美的界面，但需要漂亮的API）.  （[Source Code](https://github.com/mapio/nofussbm)）`GPL-3.0`` Python`
- [Pinry](http://getpinry.com/)  -适用于想要保存，标记和共享图像，视频和网页的人员的平铺图像板系统.  （[Source Code](https://github.com/pinry/pinry)）`BSD-2-Clause`` Python`
- [Reminiscence](https://github.com/kanishka-linux/reminiscence)  -自托管的书签和存档管理器.  AGPL-3.0 Python
- [Shaarli](https://github.com/shaarli/Shaarli)  -个人，极简，超快速，无数据库书签和链接共享平台.  （[Demo](https://demo.shaarli.org)）`Zlib``PHP`
- [Shiori](https://github.com/RadhiFadlillah/shiori)  -使用Go构建的简单书签管理器. 麻省理工学院
- [unmark](https://github.com/plainmade/unmark)  -开源做链接的应用程序. 麻省理工学院PHP
- [ubookmark](https://ungleich.ch/u/projects/ubookmark/)  -启用LDAP的书签服务.  （[Demo](https://ipv6.blog), [Source Code](https://code.ungleich.ch/ungleich-public/ubookmark/)）`GPL-2.0`` Python`
- [xBrowserSync](https://www.xbrowsersync.org)  -开源工具，用于在浏览器和设备之间同步浏览器数据.  （[Source Code](https://github.com/xBrowserSync)）`与`Node.js`

## Calendaring and Contacts Management

**[`^        back to top        ^`](#)**

_Some [Groupware](#groupware) 解决方案还具有日历/通讯录的编辑和同步功能.

_请参阅https://en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations_

### CalDAV or CardDAV servers

- [Baïkal](http://sabre.io/baikal/)  -基于sabre / dav的轻量级CalDAV和CardDAV服务器.  （[Source Code](https://github.com/sabre-io/Baikal)）`GPL-3.0``PHP`
- [CalendarServer](https://www.calendarserver.org/)  -Apple，Inc.的标准服务器，实现了macOS Server随附的CalDAV和CardDAV协议.  （[Source Code](https://github.com/apple/ccs-calendarserver)）`Apache-2.0`` Python`
- [calypso](https://keithp.com/calypso/)  -从Radicale派生的基于Python的CalDAV和CardDAV服务器.  （[Source Code](https://keithp.com/git/calypso.git)）`GPL-3.0`` Python`
- [DAViCal](https://www.davical.org/)  -使用PostgreSQL数据库作为数据存储的日历共享服务器（CalDAV）.  （[Source Code](https://gitlab.com/davical-project/davical)）`GPL-2.0``PHP`
- [Davis](https://github.com/tchapi/davis/)  -基于Symfony 5和Bootstrap 4的sabre / dav的简单，可泊坞窗化且可完全翻译的管理界面，灵感主要来自Baïkal. 麻省理工学院PHP
- [DecSync CC](https://f-droid.org/packages/org.decsync.cc/) -无服务器联系人，使用您自己的文件同步方法（即Syncthing，Nextcloud等）进行日历同步（[Source Code](https://github.com/39aldo39/DecSyncCC)）`GPL-3.0``Kotlin`
- [Etebase (EteSync)](https://www.etebase.com/) - End-to-end encrypted and journaled personal information server supporting calendar and contact data, offering its own clients. ([Source Code](https://github.com/etesync/server)）`AGPL-3.0``Python / Django`
- [Radicale](http://radicale.org/)  -简单的日历和联系服务器，管理费用极低.  （[Source Code](https://github.com/Kozea/Radicale)）`GPL-3.0`` Python`
- [SabreDAV](http://sabre.io/)  -开源CardDAV，CalDAV和WebDAV框架和服务器.  （[Source Code](https://github.com/sabre-io/dav)）和PHP`
- [Xandikos](https://www.xandikos.org/)  -由Git储存库支持的开源CardDAV和CalDAV服务器，具有最小的管理开销.  （[Source Code](https://github.com/jelmer/xandikos)）`GPL-3.0`` Python`

### CalDAV or CardDAV web-based clients

- [AgenDAV](http://agendav.org/)  -具有丰富的AJAX界面和共享日历支持的多语言CalDAV Web客户端.  （[Source Code](https://github.com/agendav/agendav)）`GPL-3.0``PHP`
- [InfCloud](https://www.inf-it.com/open-source/clients/infcloud/)  -开源CalDAV / CardDAV Web客户端实现.  （[Demo](https://www.inf-it.com/infcloud/), [Source Code](https://www.inf-it.com/InfCloud_0.13.1.zip)）`AGPL-3.0``Javascript`
- [EteSync Web](https://www.etesync.com/faq/#web-client)  -EteSync的官方基于Web的客户端（即，其Web应用程序）.  （[Demo](https://client.etesync.com/), [Source Code](https://github.com/etesync/etesync-web)）`AGPL-3.0``Javascript`

## Communication systems

**[`^        back to top        ^`](#)**

### Custom communication systems

- [BluetoothCommunicatorExample](https://github.com/niedev/BluetoothCommunicatorExample)  -蓝牙LE聊天应用程序，可在具有P2P架构的android设备之间进行通信.  （[Clients](https://github.com/niedev/RTranslator)）Apache-2.0`` Java`
- [Centrifugo](https://github.com/centrifugal/centrifugo)  -与语言无关的实时消息传递（Websocket或SockJS）服务器.  （[Demo](https://github.com/centrifugal/centrifugo#demo)）`MIT`` Go`
- [Chatwoot](https://www.chatwoot.com)  -自托管的客户交流平台，是Intercom和Zendesk的替代产品.  （[Source Code](https://github.com/chatwoot/chatwoot)）`MIT`` Ruby`
- [Cherry](https://github.com/rafael-santiago/cherry)  -小型网聊服务器.  GPL-2.0`Go`
- [Conduit](https://conduit.rs/)  -由Matrix提供支持的简单，快速且可靠的聊天服务器.  （[Source Code](https://gitlab.com/famedly/conduit)）`Apache-2.0`Rust`
- [Darkwire.io](https://darkwire.io/)  -端到端加密即时网络聊天.  （[Source Code](https://github.com/darkwire/darkwire.io)）`与`Node.js`
- [Freenet](https://freenetproject.org/index.html)  -匿名共享文件，浏览和发布“免费站点”（只能通过Freenet访问的网站）以及在论坛上聊天.  （[Source Code](https://github.com/freenet/fred)）`GPL-2.0`` Java`
- [Friends](http://moose-team.github.io/friends/)  -由网络提供动力的P2P聊天.  （[Source Code](https://github.com/moose-team/friends)）`与`Node.js`
- [GNUnet](https://gnunet.org/)  -用于分散式对等网络的免费软件框架.  （[Source Code](https://gnunet.org/git/)）`GPL-3.0`` C`
- [Gotify](https://gotify.net/)  -具有Android和CLI客户端的自托管通知服务器，类似于PushBullet.  （[Source Code](https://github.com/gotify/server), [Clients](https://github.com/gotify/android)）`MIT`` Go`
- [Hawkpost](https://hawkpost.co)  -HawkPost是一个网络应用程序，可让您创建唯一的链接，您可以与希望向您发送重要信息但不知道如何加密的人共享该链接. 邮件在他们的浏览器中被加密并发送到您的电子邮件地址.  （[Source Code](https://github.com/whitesmith/hawkpost)）和Python
- [Jami](https://jami.net/)  -自由和通用的通信平台，可保护用户的隐私和自由（以前称为GNU Ring）.  （[Source Code](https://git.ring.cx/savoirfairelinux/ring-project)）`GPL-3.0`` C ++`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet)  -Jitsi Meet是一个开源（MIT）WebRTC Javascript应用程序，它使用Jitsi Videobridge提供高质量，可扩展的视频会议.  （[Source Code](https://github.com/jitsi/jitsi-meet)）和Javascript
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge)  -兼容WebRTC的选择性转发单元（SFU），允许进行多用户视频通信.  （[Source Code](https://github.com/jitsi/jitsi-videobridge)）Apache-2.0`` Java`
- [KChat](https://github.com/php-kchat/kchat)  -基于PHP的实时聊天应用程序.  `Apache-2.0``PHP`
- [LeapChat](https://github.com/cryptag/leapchat)  -临时的，加密的浏览器内聊天室.  AGPL-3.0 JavaScript
- [Lets-Chat](http://sdelements.github.io/lets-chat/)  -用Node编写的自托管聊天套件.  （[Source Code](https://github.com/sdelements/lets-chat)）`与`Node.js`
- [LibreNews](https://librenews.io/)  -分散和安全的突发新闻通知系统.  （[Source Code](https://github.com/milesmcc/LibreNews-Server/)）`GPL-3.0`` Python`
- [Live Helper Chat](http://livehelperchat.com/)  -您的网站的实时支持聊天.  （[Source Code](https://github.com/LiveHelperChat/livehelperchat)）`Apache-2.0``PHP`
- [Mattermost](http://www.mattermost.org/)  -开源，本地Slack替代. 它可以与Gitlab集成.  （[Source Code](https://github.com/mattermost/mattermost-server)）`AGPL-3.0 / Apache-2.0``Go`
- [MiAOU](https://miaou.dystroy.org/login)  -多房间持久聊天服务器.  （[Source Code](https://github.com/Canop/miaou)）`与`Node.js`
- [Mibew](https://mibew.org)  -Mibew Messenger是一个用PHP和MySQL编写的开源实时支持应用程序. 它可以直接从您的网站实时进行一对一聊天帮助.  （[Demo](https://mibew.org/demo2), [Source Code](https://github.com/Mibew/mibew)）`Apache-2.0``PHP`
- [Mumble](https://wiki.mumble.info/wiki/Main_Page)  -低延迟，高质量的语音/文本聊天软件.  （[Source Code](https://github.com/mumble-voip/mumble), [Clients](https://wiki.mumble.info/wiki/3rd_Party_Applications)）`BSD-3-Clause``C ++`
- [Node-Chat](https://github.com/IgorAntun/node-chat)  -具有管理员功能的不太基本的开源聊天.  MIT`Nodejs`
- [OTS](https://ots.fyi/)  -一次性保密共享平台，在浏览器中采用对称的256位AES加密.  （[Source Code](https://github.com/Luzifer/ots)）`Apache-2.0``Go`
- [Papercups](https://papercups.io/)  -用Elixir编写的开源实时客户聊天Web应用程序.  （[Demo](https://app.papercups.io/demo), [Source Code](https://github.com/papercups-io/papercups)）`万用药
- [PushBits](https://github.com/eikendev/pushbits)  -自托管通知服务器，用于通过Matrix中继推送通知，类似于PushBullet和Gotify.  `ISC``Go`
- [Rallly](http://rallly.co)  -Rallly是免费的协作计划服务.  （[Source Code](https://github.com/lukevella/Rallly)）`CC-BY-SA-4.0`` Nodejs`
- [RetroShare](http://retroshare.org)  -安全和分散的通信系统. 提供分散的聊天，论坛，消息传递，文件传输.  （[Source Code](https://github.com/RetroShare/RetroShare)）`GPL-2.0`` C ++`
- [Rocket.Chat](https://rocket.chat/)  -与Gitter.im或Slack类似的Teamchat解决方案.  （[Source Code](https://github.com/RocketChat/Rocket.Chat)）`与`Node.js`
- [Shhh](https://github.com/smallwat3r/shhh)  -将机密信息保存在电子邮件或聊天记录中，并使用带有密码短语和有效期的安全链接进行共享. 麻省理工学院Python
- [Spectrum 2](http://spectrum.im/)  -Spectrum 2是开源的即时消息传递. 它使用户即使使用不同的IM网络也可以一起聊天.  （[Source Code](https://github.com/hanzz/spectrum2)）`GPL-3.0`` C ++`
- [Spreed](https://www.spreed.me/)  -WebRTC音频/视频通话，会议服务器和Web客户端.  （[Source Code](https://github.com/strukturag/spreed-webrtc)）`AGPL-3.0``Go`
- [Synapse](http://matrix.org/docs/projects/server/synapse.html) -服务器 [Matrix](https://matrix.org/) ，是分散式持续通讯的开放标准.  （[Source Code](https://github.com/matrix-org/synapse)）`Apache-2.0`` Python`
  - [Matrix Console Web](https://matrix.org/docs/projects/client/matrix-console-web)  -Web客户端意在展示Matrix功能，以及Matrix标准的参考实现.  （[Source Code](https://github.com/matrix-org/matrix-angular-sdk)）Apache-2.0 Javascript
  - [Element](https://element.io)  -适用于Web，iOS和Android的功能齐全的Matrix客户端.  （[Source Code](https://github.com/vector-im/element-web)）Apache-2.0 Javascript
- [Syndie](https://syndie.de)  -Syndie是用于运行分布式论坛的自由系统.  `CC0-1.0``Java`
- [TextBelt](https://github.com/typpo/textbelt)  `⚠`-传出SMS API，它使用运营商特定的网关免费发送您的短信，并且没有广告.  MIT Java语言
- [Tinode](https://github.com/tinode)  -即时通讯平台.  Go中的后端. 客户端：Swift iOS，Java Android，JS webapp，可编写脚本的命令行； 聊天机器人.  （[Demo](https://sandbox.tinode.co/), [Source Code](https://github.com/tinode/chat), [Clients](https://github.com/tinode/webapp)）`GPL-3.0``Go`
- [Tox](https://tox.chat/)  -具有音频和视频聊天功能的分布式安全Messenger.  （[Source Code](https://github.com/irungentoo/toxcore)）`GPL-3.0`` C`
- [Tuber](https://blog.trailofbits.com/2015/12/15/self-hosted-video-chat-with-tuber/)  -有效的点对点视频聊天.  （[Source Code](https://github.com/trailofbits/tubertc)）和Javascript
- [WBO](https://github.com/lovasoa/whitebophir#wbo)  -Web白板，可在模式，图形和注释上进行实时协作.  （[Demo](https://wbo.ophir.dev/)）`AGPL-3.0``Nodejs / Docker`
- [ZeroNet](https://zeronet.io/)  `⚠`-使用比特币加密技术和BitTorrent网络的开放，免费和不可审查的网站.  （[Source Code](https://github.com/HelloZeroNet/ZeroNet)）`GPL-2.0`` Python`
- [Zulip](https://zulip.org)  -Zulip是功能强大的开源群聊应用程序.  （[Source Code](https://github.com/zulip/zulip)）`Apache-2.0 / Other``Python`

### Email

**[`^        back to top        ^`](#)**

#### Complete solutions

_邮件服务器的简单部署，例如，对于没有经验或不耐烦的管理员.

- [AnonAddy](https://anonaddy.com)  -用于创建别名的开源电子邮件转发服务.  （[Source Code](https://github.com/anonaddy/anonaddy)）和PHP`
- [DebOps](https://debops.org/) - Your Debian-based data center in a box. A set of general-purpose Ansible roles that can be used to manage Debian or Ubuntu hosts. ([Source Code](https://github.com/debops/debops)）`仅GPL-3.0``YAML / Ansible / Python`
- [docker-mailserver](https://github.com/tomav/docker-mailserver)  -全栈但简单的邮件服务器（smtp，imap，反垃圾邮件，防病毒等）. 仅配置文件，无SQL数据库. 保持简单和版本化. 易于部署和升级.  MIT码头工人
- [emailwiz](https://github.com/LukeSmithxyz/emailwiz)  -Luke Smith的bash脚本可完全自动在debian上安装Postfix / Dovecot / SpamAssassin / OpenDKIM服务器.  GPL-3.0`重击
- [Excision Mail](https://github.com/Excision-Mail/Excision-Mail)  -基于ansible的基于OpenSMTPD for OpenBSD的全栈，注重安全性的邮件服务器.  `ISC``Shell / Ansible`
- [Inboxen](https://inboxen.org)  -收件箱是一项可为您提供无限数量的唯一收件箱的服务.  （[Source Code](https://github.com/Inboxen/Inboxen)）`GPL-3.0`` Python`
- [homebox](https://github.com/progmaticltd/homebox)  -Ansible脚本套件，用于在Debian上部署功能齐全的邮件服务器. 尽可能不干扰和自动执行，着眼于稳定性和安全性.  `GPL-3.0``Shell`
- [iRedMail](http://www.iredmail.org/)  -基于Postfix和Dovecot的全功能邮件服务器解决方案.  （[Source Code](https://github.com/iredmail/iRedMail)）`GPL-3.0``Shell`
- [Mailcow](https://mailcow.email/)  -基于Dovecot，Postfix和其他开源软件的邮件服务器套件，提供了用于管理的现代Web UI.  （[Source Code](https://github.com/mailcow/mailcow-dockerized)）`GPL-2.0``Docker / PHP`
- [Mailu](https://mailu.io/)  -Mailu是一个简单而功能齐全的邮件服务器，它是一组Docker映像.  （[Demo](https://github.com/Mailu/Mailu/wiki/Demo-server), [Source Code](https://github.com/Mailu/Mailu)）`MIT`` Docker / Python`
- [Mail-in-a-Box](https://mailinabox.email/)  -使用一个命令即可将任何Ubuntu服务器转变为功能齐全的邮件服务器.  （[Source Code](https://github.com/mail-in-a-box/mailinabox)）`CC0-1.0``Shell`
- [Modoboa](http://modoboa.org/en/)  -Modoboa是一个邮件托管和管理平台，包括现代且经过简化的Web用户界面.  （[Source Code](https://github.com/tonioo/modoboa)）和Python
- [Ptorx](https://ptorx.com/)  -电子邮件隐私. 通过别名转发匿名发送和接收.  （[Source Code](https://github.com/xyfir/ptorx)）GPL-3.0`Node.js`
- [Qmailtoaster](http://www.qmailtoaster.com/)  -基于qmail的稳定，功能齐全，易于安装的邮件服务器.  （[Source Code](https://github.com/QMailToaster/)）`Multiple``Linux`
- [SimpleLogin](https://simplelogin.io)  -开源电子邮件别名解决方案，以保护您的电子邮件地址. 随附浏览器扩展程序和移动应用程序.  （[Source Code](https://github.com/simple-login/app)）`MIT`` Docker / Python`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver)  -利用Nix生态系统的完整邮件服务器解决方案.  GPL-3.0`Nix`
- [wildduck](https://wildduck.email/)  -可扩展的无SPOF IMAP / POP3邮件服务器.  （[Source Code](https://github.com/nodemailer/wildduck)）`EUPL-1.2`Node.js`

#### Mail Transfer Agents

_MTA / SMTP服务器_

- [chasquid](https://blitiri.com.ar/p/chasquid/)  -专注于简单性，安全性和易操作性的SMTP（电子邮件）服务器.  （[Source Code](https://blitiri.com.ar/git/r/chasquid/)）`Apache-2.0``Go`
- [Courier MTA](http://www.courier-mta.org/)  -快速，可扩展的企业邮件/组件服务器，提供ESMTP，IMAP，POP3，Web邮件，邮件列表，基于Web的基本日历和计划服务.  （[Source Code](http://www.courier-mta.org/repo.html)）`GPL-3.0`` C`
- [Exim](https://www.exim.org/)  -剑桥大学开发的邮件传输代理（MTA）.  （[Source Code](http://git.exim.org/exim.git)）`GPL-3.0`` C`
- [Haraka](http://haraka.github.io/)  -用Javascript编写的高性能，可插入SMTP服务器.  （[Source Code](https://github.com/haraka/Haraka)）和Javascript
- [MailCatcher](http://mailcatcher.me/)  -Ruby gem，它部署了一个简单的SMTP MTA网关，该网关接受所有邮件并在Web界面中显示. 对于调试或开发很有用.  （[Source Code](https://github.com/sj26/mailcatcher)）`MIT`` Ruby`
- [Maildrop](https://gitlab.com/markbeeson/maildrop)  -一次性电子邮件SMTP服务器，对开发也很有用.  MIT斯卡拉
- [MailHog](https://github.com/mailhog/MailHog)  -小型Golang可执行文件，可运行SMTP MTA网关，该网关接受所有邮件并在Web界面中显示. 对于调试或开发很有用. 麻省理工学院
- [OpenSMTPD](https://opensmtpd.org/)  -从OpenBSD项目中保护SMTP服务器的实现.  （[Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)）`ISC``C`
- [Postfix](http://www.postfix.org/)  -快速，易于管理并确保替换Sendmail.  IPL-1.0 C
- [Qmail](https://cr.yp.to/qmail.html)  -安全的Sendmail替换.  （[Source Code](https://sources.debian.net/src/netqmail/1.06-5/)）`CC0-1.0`` C`
- [Sendmail](http://www.sendmail.com/sm/open_source/)  -邮件传输代理（MTA）.  `Sendmail``C`
- [Slimta](http://slimta.org)  -基于Python构建的邮件传输库.  （[Source Code](https://github.com/slimta/python-slimta)）和Python

#### Mail Delivery Agents

_MDA-IMAP / POP3软件_

- [Cyrus IMAP/POP3](https://www.cyrusimap.org/) -旨在在密封的服务器上运行，不允许普通用户登录.[Source Code](https://github.com/cyrusimap/cyrus-imapd )）`BSD-3-Clause-Attribution``C`
- [Dovecot](http://www.dovecot.org/)  -在编写IMAP和POP3服务器时，首先要牢记安全性.  （[Source Code](https://github.com/dovecot/core)）MIT / LGPL-2.1`` C`
- [Piler](http://www.mailpiler.org/wiki/start)  -功能丰富的开源电子邮件归档解决方案.  （[Source Code](https://bitbucket.org/jsuto/piler)）`GPL-3.0`` C`

#### Mailing lists and Newsletters

_邮寄列出服务器和群发邮件软件-一封邮件给许多收件人.

- [Dada Mail](http://dadamailproject.com/)  -基于Web的列表管理系统，可用于公告列表和/或讨论列表.  （[Source Code](https://github.com/justingit/dada-mail)）`GPL-2.0`` Perl`
- [Listmonk](https://listmonk.app/)  -具有现代化仪表板的高性能，自托管新闻通讯和邮件列表管理器.  （[Source Code](https://github.com/knadh/listmonk)）`AGPL-3.0``Go`
- [Mail For Good](https://github.com/freeCodeCamp/mail-for-good)  ⚠-面向非营利组织的开源电子邮件广告系列管理工具.  BSD-3-Clause Javascript
- [Mailman](https://www.gnu.org/software/mailman/)  -Gnu邮件列表服务器.  GPL-3.0 Python
- [Mailtrain](https://mailtrain.org/)  -基于Node.js（v5 +）和MySQL（v5.5 +或MariaDB）构建的自托管新闻通讯应用程序.  （[Source Code](https://github.com/andris9/mailtrain)）`GPL-3.0`` Nodejs`
- [MailyHerald](http://mailyherald.org/)  -自托管的Mailchimp替代方案，您可以轻松地与您的站点集成. 帮助您发送和管理应用程序邮件. 它支持电子邮件营销并处理您发送给用户的每日通知流.  （[Source Code](https://github.com/Sology/maily_herald)）`LGPL-3.0``Ruby`
- [Mautic](https://www.mautic.org/)  -Mautic是市场营销自动化软件（电子邮件，社交和更多）.  （[Source Code](https://github.com/mautic/mautic)）`GPL-3.0``PHP`
- [HyperKitty](https://wiki.list.org/HyperKitty)  -开源Django应用程序，以提供Web界面来访问GNU Mailman v3档案.  （[Demo](https://lists.mailman3.org/), [Source Code](https://gitlab.com/mailman/hyperkitty)）`GPL-3.0`` Python`
- [phpList](https://phplist.org)  -具有订户，退回和插件的高级管理功能的时事通讯和电子邮件营销.  （[Source Code](https://github.com/phpList/)）`AGPL-3.0``PHP`
- [Postal](https://github.com/atech/postal)  -用于接收和发送电子邮件的功能齐全的开源邮件传递平台. 麻省理工学院Ruby
- [Postorius](https://docs.mailman3.org/projects/postorius/en/latest/)  -访问GNU Mailman的Web用户界面.  （[Source Code](https://gitlab.com/mailman/postorius/)）`GPL-3.0`` Python`
- [Schleuder](https://schleuder.nadir.org/)  -具有重发功能的启用GPG的邮件列表管理器.  （[Source Code](https://0xacab.org/schleuder/schleuder/tree/master)）`GPL-3.0`` Ruby`
- [Sympa](https://www.sympa.org/)  -邮件列表管理器.  GPL-2.0 Perl

#### Webmail clients

- [Afterlogic WebMail Lite](http://www.afterlogic.org/webmail-lite)  -用于现有IMAP邮件服务器，Plesk或cPanel的快速，易于使用的Webmail前端.  （[Demo](https://lite.afterlogic.com/), [Source Code](https://github.com/afterlogic/webmail-lite)）`AGPL-3.0``PHP`
- [Cypht](http://cypht.org/index.html)  -Feed阅读器提供您的电子邮件帐户.  （[Source Code](https://github.com/jasonmunro/hm3)）`GPL-2.0``PHP`
- [IMP](https://www.horde.org/apps/imp/)  -HORDE应用程序，可通过Webmail访问IMAP和POP3帐户.  （[Demo](http://demo.horde.org/), [Source Code](https://www.horde.org/download/imp)）`GPL-2.0``PHP`
- [Isotope Mail](https://blog.marcnuri.com/isotope-mail-client-introduction/)  -使用ReactJS和Spring构建的基于微服务的Webmail客户端.  （[Source Code](https://github.com/manusa/isotope-mail)）`Apache-2.0``Docker / Java`
- [MailCare](https://mailcare.io)  -开源一次性电子邮件地址服务.  （[Source Code](https://github.com/mailcare/mailcare)）和PHP`
- [Mailpile](https://www.mailpile.is/)  -具有搜索，过滤，加密功能等的Webmail客户端.  （[Source Code](https://github.com/mailpile/Mailpile)）`AGPL-3.0``Python`
- [RainLoop](http://www.rainloop.net/)  -具有IMAP / SMTP支持和多种计费功能的简单，现代和快速的Webmail.  （[Demo](http://demo.rainloop.net/), [Source Code](https://github.com/RainLoop/rainloop-webmail) ）.  `AGPL-3.0``PHP`
- [Roundcube](https://roundcube.net)  -具有类似应用程序的用户界面的基于浏览器的IMAP客户端.  （[Source Code](https://github.com/roundcube/roundcubemail)）`GPL-3.0``PHP`
- [SquirrelMail](http://squirrelmail.org)  -另一个基于浏览器的IMAP客户端.  （[Source Code](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)）`GPL-2.0``PHP`

### IRC

**[`^        back to top        ^`](#)**

_[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) communication software_

- [Convos](https://convos.chat/)  -始终在线的Web IRC客户端.  （[Demo](https://convos.chat/#instant-demo), [Source Code](http://github.com/nordaaker/convos)）`Artistic-2.0`` Perl`
- [InspIRCd](https://www.inspircd.org/)  -用C ++编写的适用于Linux，BSD，Windows和macOS的模块化IRC服务器.  （[Source Code](https://github.com/inspircd/inspircd)）`仅GFDL-1.2``C ++`
- [Dispatch](https://github.com/khlieng/dispatch)  -用Go编写的自托管Web IRC客户端.  （[Demo](https://dispatch.khlieng.com/connect)）`MIT`` Go`
- [Kiwi IRC](https://kiwiirc.com/)  -具有主题支持功能的响应式Web IRC客户端.  （[Demo](https://kiwiirc.com/nextclient/), [Source Code](https://github.com/kiwiirc/kiwiirc)）`Apache-2.0`` Nodejs`
- [ngircd](https://ngircd.barton.de/)  -适用于小型或专用网络的免费，便携式，轻便的Internet中继聊天服务器.  （[Source Code](https://github.com/ngircd/ngircd)）`GPL-2.0``C`
- [Oragono](https://oragono.io)  -用Go语言编写的现代IRCv3服务器，结合了ircd，服务框架和弹跳器的功能.  （[Source Code](https://github.com/oragono/oragono/)）`MIT`` Go`
- [The Lounge](https://thelounge.github.io/)  -自托管的Web IRC客户端.  （[Demo](https://demo.thelounge.chat/), [Source Code](https://github.com/thelounge/lounge)）`与`Node.js`
- [Quassel IRC](http://quassel-irc.org/)  -分布式IRC客户端，这意味着一个（或多个）客户端可以连接到中央核心或从中央核心分离.  （[Source Code](https://github.com/quassel/quassel)）`GPL-2.0`` C ++`
- [Robust IRC](https://robustirc.net/)  -RobustIRC是没有网裂的IRC. 基于RobustSession协议的分布式IRC服务器.  （[Source Code](https://github.com/robustirc/robustirc)）`BSD-3-Clause``Go`
- [Tiny Tiny IRC](https://tt-rss.org/tt-irc/) -由AJAX支持的开源聊天平台，支持IRC（[Source Code](https://git.tt-rss.org/fox/tt-irc) ）.  `GPL-3.0`` PHP / Java`
- [Weechat](https://weechat.org/)  -快速，轻便和可扩展的聊天客户端.  GPL-3.0`C
  - [Glowing Bear](https://github.com/glowing-bear/glowing-bear/)  -WeeChat的Web前端.  （[Demo](https://www.glowing-bear.org)）`GPL-3.0``JavaScript`
- [ZNC](http://wiki.znc.in/ZNC)  -先进的IRC保镖.  （[Source Code](https://github.com/znc/znc)）Apache-2.0`C ++

### SIP

**[`^        back to top        ^`](#)**

_[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol)/[IPBX](https://en.wikipedia.org/wiki/IP_PBX) 电话软件_

- [Asterisk](http://www.asterisk.org/) - Easy to use but advanced IP PBX system, VoIP gateway and conference server. `GPL-2.0` `C`
- [ASTPP](https://www.astppbilling.org/)  -是Freeswitch的开源VoIP计费解决方案. 它支持带有通话评级和信用控制的预付费和后付费账单. 它还提供了许多其他功能.  （[Source Code](https://github.com/iNextrix/ASTPP)）`AGPL-3.0``PHP`
- [Freepbx](http://www.freepbx.org)  -控制和管理星号的基于Web的开源GUI.  （[Source Code](http://git.freepbx.org/projects/FREEPBX)）`GPL-2.0``PHP`
- [FreeSWITCH](https://freeswitch.org/)  -可扩展的开源跨平台电话平台.  （[Source Code](https://freeswitch.org/stash/projects/FS/repos/freeswitch/browse)）`MPL-2.0``C`
- [FusionPBX](https://www.fusionpbx.com/)  -开源项目，为称为FreeSWITCH的功能非常强大且高度可扩展的多平台语音交换机提供了可自定义的灵活Web界面.  （[Source Code](https://github.com/fusionpbx/fusionpbx)）`MPL-1.1``PHP`
- [Homer](https://www.sipcapture.org/) - Troubleshooting and monitoring VoIP calls. ([Source Code](https://github.com/sipcapture/homer)）`AGPL-3.0``Angular / C`
- [Kamailio](http://www.kamailio.org/w/)  -模块化SIP服务器（注册商/代理/路由器/等）.  （[Source Code](https://github.com/kamailio/kamailio)）`GPL-2.0``C`
- [Kazoo](http://2600hz.org/)  -KAZOO是一个开源，高度可扩展的软件平台，旨在提供电信级VoIP交换机功能和特性.  （[Source Code](https://github.com/2600hz/KAZOO)) `MPL-1.1` `Erlang`
- [Ostel](https://dev.guardianproject.info/projects/ostel/wiki/Server_Documentation)  -采用ZRTP加密的安全SIP电话设置.  GPL-3.0`Ruby`
- [Routr](https://routr.io)  -轻巧的SIP代理，位置服务器和注册器，可提供可靠且可扩展的SIP基础架构.  （[Demo](https://demo.routr.io/login), [Source Code](https://github.com/fonoster/routr)）`与JavaScript`
- [SipXcom](http://sipxcom.org/)  -开源统一通信系统.  （[Source Code](https://github.com/sipXcom/sipxecs)）`AGPL-3.0``Java`
- [SIP3](https://sip3.io/)  -VoIP故障排除和监视平台.  （[Demo](https://demo.sip3.io), [Source Code](https://github.com/sip3io/)）`Apache-2.0``Kotlin`
- [Wazo](http://wazo-platform.org/)  -在Asterisk上构建的功能齐全的IPBX解决方案，具有集成的Web管理界面和REST-ful API.  （[Source Code](https://github.com/wazo-platform)）`GPL-3.0`` Python`

### Social Networks and Forums

**[`^        back to top        ^`](#)**

- [Abilian SBE](https://github.com/abilian/abilian-sbe)  -开源协作和社交网络框架和平台.  LGPL-2.1 Python
- [Anahita](https://www.getanahita.com/)  -开源社交网络框架和平台.  （[Source Code](https://github.com/anahitasocial)）`GPL-3.0``PHP`
- [AsmBB](https://board.asm32.info)  -使用ASM编写的，由SQLite驱动的快速论坛引擎.  （[Source Code](https://asm32.info/fossil/asmbb/index)）`EUPL-1.1`装配体
- [bbPress](https://bbpress.org/)  -bbPress是论坛软件，与WordPress的创建者有所不同. 在WordPress.org支持的网站内轻松设置讨论论坛.  （[Source Code](https://bbpress.trac.wordpress.org/browser/trunk)）`GPL-2.0``PHP`
- [Bootcamp](http://trybootcamp.vitorfs.com)  -企业社交网络.  （[Source Code](https://github.com/vitorfs/bootcamp)）和Python
- [Buddycloud](http://buddycloud.com/)  -工具，库，服务和社区，可将用户对用户，组和社交消息传递构建到您的应用中. 节省时间. 扩大规模. 支持您.  （[Source Code](https://github.com/buddycloud)）Apache-2.0`` Java`
- [BuddyPress](https://buddypress.org/about/)  -强大的插件，可通过社交网络功能（如用户个人资料，活动流，用户组等）将WordPress.org站点带到博客之外.  （[Source Code](https://github.com/buddypress/BuddyPress)）`GPL-2.0``PHP`
- [Cactus Comments](https://cactus.chat/)  -仙人掌评论是针对基于Matrix的开放网络的联合评论系统.  （[Demo](https://cactus.chat/demo/), [Source Code](https://gitlab.com/cactus-comments/)）`GPL-3.0`` Python`
- [cartulary](https://github.com/daveajones/cartulary)  -RSS阅读器，可读性工具，文章存档器，微博者，社交图管理器和阅读列表管理器.  `CDDL-1.0``PHP`
- [Commento](https://gitlab.com/commento/commento)  -Commento是一个讨论平台，您可以将其嵌入博客，新闻文章以及希望读者添加评论的任何地方. 麻省理工学院
- [Coral](https://coralproject.net/)  -Vox Media提供了更好的评论体验.  （[Source Code](https://github.com/coralproject/talk)）`Apache-2.0`` Nodejs`
- [diaspora*](https://diasporafoundation.org/)  -分布式社交网络服务器.  （[Demo](https://podupti.me/go.php), [Source Code](https://github.com/diaspora/diaspora)）`AGPL-3.0``Ruby`
- [Discourse](http://www.discourse.org/)  -基于Ruby和JS的高级论坛/社区解决方案.  （[Demo](https://try.discourse.org/), [Source Code](https://github.com/discourse/discourse)）`GPL-2.0`` Ruby`
- [dyu/comments](https://github.com/dyu/comments)  -由leveldb提供支持的实时，支持markdown的注释引擎.  （[Demo](https://dyu.github.io/comments/real-time/)）Apache-2.0`` Java`
- [EpochTalk](https://github.com/epochtalk/epochtalk)  -下一代论坛软件.  MIT`Nodejs`
- [Elgg](https://elgg.org/)  -强大的开源社交网络引擎.  （[Source Code](https://github.com/Elgg/Elgg)）`GPL-2.0``PHP`
- [Flarum](http://flarum.org)  -非常简单的论坛.  Flarum是使在线讨论再次变得有趣的下一代论坛软件.  （[Source Code](https://github.com/flarum/flarum)）和PHP`
- [flaskbb](https://flaskbb.org/)  -FlaskBB是使用Microframework Flask用Python编写的论坛软件. 您可以轻松创建新主题，发布帖子并向其他用户发送私人消息. 它还包括基本的管理和审核工具.  （[Source Code](https://github.com/sh4nks/flaskbb)）`BSD-3-Clause`` Python`
- [FluxBB](http://fluxbb.org/)  -为您的网站提供快速，轻便，用户友好的论坛软件.  （[Source Code](https://github.com/fluxbb/fluxbb)）`GPL-2.0``PHP`
- [Friendica](https://friendi.ca/)  -社交通讯服务器.  （[Source Code](https://github.com/friendica/friendica)）`AGPL-3.0``PHP`
- [Glosa](https://github.com/glosa/glosa-server)  -易于与静态页面集成的开源评论系统. 您可以从Disqus导入.  GPL-3.0 Java
- [GNU social](https://gnu.io/social/)  -用于公共和私人通信的社交通信软件.  （[Source Code](https://notabug.org/diogo/gnu-social)）`AGPL-3.0``PHP`
- [Gosora](https://gosora-project.com/)  -Gosora是一种用Go语言编写的超快速，安全的论坛软件，它在可用性和功能之间取得了平衡.  （[Source Code](https://github.com/Azareal/Gosora)）`GPL-3.0``Go`
- [Hubzilla](https://hubzilla.org)  -分散的身份，隐私，发布，共享，云存储和通信/社交平台.  （[Source Code](https://framagit.org/hubzilla/core)）和PHP`
- [HumHub](https://www.humhub.org/)  -专用社交网络的灵活工具包.  （[Source Code](https://github.com/humhub/humhub)）`AGPL-3.0``PHP`
- [Isso](http://posativ.org/isso/)  -用Python和Javascript编写的轻量级注释服务器. 它旨在成为Disqus的替代产品.  （[Source Code](https://github.com/posativ/isso)）和Python
- [Lemmy](https://join.lemmy.ml/#/)  -链接的链接聚合器/ reddit克隆.  Rust内置的Reddit替代方案.  （[Source Code](https://github.com/dessalines/lemmy)）`AGPL-3.0``Rust`
- [Loomio](https://www.loomio.org/)  -Loomio是协作式决策工具，任何人都可以轻松参与影响他们的决策.  （[Source Code](https://github.com/loomio/loomio)）`AGPL-3.0``Ruby`
- [Mastodon](https://joinmastodon.org/)  -联合微博服务器，是GNU social的替代产品.  （[Source Code](https://github.com/tootsuite/mastodon)）`AGPL-3.0``Ruby`
- [Misago](https://misago-project.org/)  -Misago是功能齐全的现代论坛应用程序，具有快速，可扩展和响应迅速的特点.  （[Source Code](https://github.com/rafalp/Misago)）`GPL-2.0`` Python`
- [Misskey](https://misskey.io/)  -使用ActivityPub协议（例如GNU social和Mastodon）为Fediverse进行分散式应用程序式微博客服务器/ SNS.  （[Source Code](https://github.com/syuilo/misskey)）`AGPL-3.0`` Nodejs`
- [Movim](https://movim.eu/)  -基于XMPP的现代联合社交网络，具有功能齐全的群组聊天，订阅和微博.  （[Source Code](https://github.com/movim/movim)）`AGPL-3.0``PHP`
- [MyBB](http://www.mybb.com/)  -免费的，可扩展的论坛软件包.  （[Source Code](https://github.com/mybb/mybb)）`LGPL-3.0``PHP`
- [NodeBB](https://nodebb.org/)  -为现代Web构建的基于Node.js的论坛软件.  （[Source Code](https://github.com/NodeBB/NodeBB)）`GPL-3.0`` Nodejs`
- [Orange Forum](http://www.goodoldweb.com/)  -Orange Forum是易于部署的论坛，具有最小的依赖关系，并且只使用很少的javascript.  （[Source Code](https://github.com/s-gv/orangeforum)）`BSD-3-Clause``Go`
- [OSSN](https://www.opensource-socialnetwork.org/)  -开源社交网络（OSSN）是用PHP编写的社交网络软件. 它使您可以创建一个社交网站，并帮助您的成员与具有相似专业或个人兴趣的人建立社交关系.  （[Source Code](https://github.com/opensource-socialnetwork/opensource-socialnetwork)）`GPL-2.0``PHP`
- [Patchwork](https://github.com/ssbc/patchwork)  -建立在Secure Scuttlebutt（SSB）之上的分散式消息传递和共享应用程序. 仅适用于AGPL-3.0的NodeJS
- [phpBB](https://www.phpbb.com/)  -平板论坛公告板软件解决方案，可用于与一群人保持联系或为整个网站提供动力.  （[Source Code](https://github.com/phpbb/phpbb)）`GPL-2.0``PHP`
- [PixelFed](https://pixelfed.social)  -Pixelfed是Instagram的开源，联合平台.  （[Source Code](http://github.com/pixelfed/pixelfed)）`AGPL-3.0`` PHP \ HTML \ Vue`
- [Pleroma](https://pleroma.social)  -联合微博服务器，Mastodon，GNU social和ActivityPub兼容.  （[Source Code](https://git.pleroma.social/pleroma/pleroma)）`AGPL-3.0``长生不老药
- [Pump.io](http://pump.io/)  -流服务器可以满足人们从社交网络真正想要的大部分需求.  （[Source Code](https://github.com/e14n/pump.io)）`Apache-2.0`` Nodejs`
- [remark42](https://remark42.com/)  -轻巧简单的注释引擎，不会对用户构成监视. 可以将其嵌入博客，文章或读者在其中添加评论的任何其他地方.  （[Demo](https://remark42.com/demo/), [Source Code](https://github.com/umputun/remark)）`MIT`` Go`
- [Satellity](https://satellity.org/)  -另一个使用Golang，React和PostgreSQL编写的开源论坛.  （[Source Code](https://github.com/satellity/satellity)）`MIT`` Go`
- [Scoold](https://scoold.com)  -JAR中的堆栈溢出. 具有全文搜索，SAML，LDAP集成和社交登录支持的企业级问答平台.  （[Demo](https://live.scoold.com), [Source Code](https://github.com/Erudika/scoold)）Apache-2.0`` Java`
- [Simple Machines Forum](https://www.simplemachines.org/)  -免费的专业级软件包，可让您在几分钟内建立自己的在线社区.  （[Source Code](https://github.com/SimpleMachines/SMF2.1)）`BSD-3-Clause``PHP`
- [Socialhome](https://socialhome.network)  -联合和分散的配置文件生成器和社交网络引擎.  （[Demo](https://socialhome.network/), [Source Code](https://github.com/jaywink/socialhome)）`AGPL-3.0``Python`
- [Talkyard](https://www.talkyard.io/)  -创建一个社区，您的用户可以在其中提出想法并回答问题. 并进行友好的开放式讨论和聊天（Slack / StackOverflow / Discourse / Reddit / Disqus混合）.  （[Demo](https://www.talkyard.io/forum/latest), [Source Code](https://github.com/debiki/talkyard)）`AGPL-3.0`` Scala`
- [Tokumei](https://tokumei.co/)  -匿名微博平台.  （[Source Code](https://gitlab.com/tokumei/tokumei)）`ISC``rc`
- [Thredded](https://github.com/thredded/thredded)  -论坛，功能丰富且简单. 麻省理工学院Ruby
- [twister](http://twister.net.co/)  -利用比特币和BitTorrent协议的免费软件实现的完全去中心化的P2P微博平台.  （[Source Code](https://github.com/miguelfreitas/twister-core)）`MIT`` C ++`
- [twtxt.net](https://twtxt.net)  -一种类似Twitter™的自托管式分散式微日志平台. 没有广告，没有跟踪，您的内容，您的数据.  （[Source Code](https://github.com/prologic/twtxt)）`MIT`` Go`
  - [rss2twtxt](https://github.com/prologic/rss2twtxt)  -RSS / Atom提要聚合器命令行工具和Web服务，它使用RSS / Atom并生成twtxt.net提要供twtxt客户端使用.  （[Demo](https://feeds.twtxt.net)）`MIT`` Go`
- [Vanilla Forums](https://vanillaforums.org/)  -简单灵活的论坛软件.  （[Source Code](https://github.com/vanilla/vanilla)）`GPL-2.0``PHP`
- [Zusam](https://zusam.org)  -免费开放源代码方式，可以为朋友或家人组举办私人论坛.  （[Demo](https://demo.zusam.org), [Source Code](https://github.com/zusam/zusam)）`AGPL-3.0``PHP`

### XMPP

**[`^        back to top        ^`](#)**

_[Extensible Messaging and Presence Protocol](https://en.wikipedia.org/wiki/XMPP) software_

#### XMPP Servers

- [ejabberd](https://www.ejabberd.im/)  -XMPP即时消息服务器.  （[Source Code](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang`
- [Kontalk](http://kontalk.org/)  -Kontalk是一个开源Messenger，类似于WhatsApp（目前仅适用于android的应用），包括端到端加密，服务器基于Tigase XMPP服务器.  （[Source Code](https://github.com/kontalk)）`GPL-3.0`` Java`
- [Metronome IM](https://metronome.im/)  -Prosody IM的前叉.  （[Source Code](https://github.com/maranda/metronome)) `MIT` `Lua`
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html)  -专注于性能和可扩展性的移动消息平台.  （[Source Code](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang`
- [Openfire](http://www.igniterealtime.org/projects/openfire/)  -实时协作（RTC）服务器.  （[Source Code](https://github.com/igniterealtime/Openfire)）Apache-2.0`` Java`
- [Prosody IM](http://prosody.im/)  -功能丰富且易于配置的XMPP服务器.  （[Source Code](http://hg.prosody.im/)) `MIT` `Lua`
- [Tigase](http://www.tigase.net/content/tigase-xmpp-server)  -Java中的XMPP服务器实现.  GPL-3.0 Java

#### XMPP Web Clients

- [Candy](http://candy-chat.github.io/candy/)  -用Java编写的多用户XMPP客户端.  （[Source Code](https://github.com/candy-chat/candy)）和Javascript
- [Converse.js](https://conversejs.org/)  -您浏览器中的免费开源XMPP聊天客户端.  （[Source Code](https://github.com/jcbrand/converse.js)）`MPL-2.0``Javascript`
- [JSXC](https://jsxc.org)  -具有视频通话，文件传输和加密通信的实时XMPP Web聊天应用程序. 也有适用于Nextcloud / Owncloud和SOGo的版本.  （[Source Code](https://github.com/jsxc/jsxc)）和Javascript
- [Salut à Toi](http://www.salut-a-toi.org/)  -多用途，多前端，自由和分散式通信工具.  （[Source Code](http://repos.goffi.org/sat)）`AGPL-3.0``Python`
  - [Libervia](http://wiki.goffi.org/wiki/Libervia/en)  -SalutàToi的Web前端.  （[Source Code](http://repos.goffi.org/libervia)）`AGPL-3.0``Python`

## Conference Management

**[`^        back to top        ^`](#)**

- [BigBlueButton](https://bigbluebutton.org/)  -支持音频，视频，幻灯片（带有白板控件），聊天和屏幕的实时共享. 教师可以使偏远地区的学生参与投票，表情符号和分组讨论室.  （[Demo](https://demo.bigbluebutton.org/gl), [Source Code](https://github.com/bigbluebutton/bigbluebutton)）`LGPL-3.0``Java`
- [Conference Organizing Distribution (COD)](http://usecod.com/)  -创建在Drupal之上构建的会议和活动网站.  （[Source Code](http://cgit.drupalcode.org/cod)）`GPL-1.0``PHP`
- [frab](https://frab.github.io/frab/)  -基于网络的会议计划和管理系统. 它有助于收集意见，管理演讲和演讲者并制定时间表.  （[Source Code](https://github.com/frab/frab)）`MIT`` Ruby`
- [indico](https://getindico.io/)  -一个功能丰富的事件管理系统，由@ CERN制作，这是Web诞生的地方.  （[Demo](https://sandbox.getindico.io/), [Source Code](https://github.com/indico/indico)）和Python
- [Open Conference Systems (OCS)](https://pkp.sfu.ca/ocs/)  -是一个免费的Web发布工具，可以为您的学术会议创建完整的Web展示.  （[Demo](https://pkp.sfu.ca/ocs/ocs_demo/), [Source Code](https://github.com/pkp/ocs)）`GPL-1.0``PHP`
- [OpenCFP](https://github.com/opencfp/opencfp)  -OpenCFP是基于PHP的会议演讲提交系统. 麻省理工学院PHP
- [OpenConferenceWare](http://openconferenceware.org/)  -用于支持类似会议的事件的开源Web应用程序. 这个可定制的通用平台提供提案，会话，日程表，曲目，用户个人资料.  （[Source Code](https://github.com/osbridge/openconferenceware)）`MIT`` Ruby`
- [osem](http://osem.io/)  -专为免费软件会议量身定制的活动管理.  （[Demo](http://demo.osem.io/), [Source Code](https://github.com/openSUSE/osem)）`MIT`` Ruby`
- [pretalx](https://pretalx.org)  -基于Web的事件管理，包括运行论文征集，审阅提交的内容和安排讲座. 各种相关工具的进出口.  （[Source Code](https://github.com/pretalx/pretalx)）`Apache-2.0`` Python`


**[`^        back to top        ^`](#)**

 _CMS是设置具有许多功能的网站的实用方法.  CMS通常带有第三方插件，主题和功能，可以轻松添加和自定义您的需求. 也可以看看 [Blogging Platforms](#blogging-platforms) 和 [Static Site Generators](#static-site-generators)_

- [Alfresco Community Edition](https://www.alfresco.com/products/community/download)  -处理任何类型内容的开源企业内容管理软件，使用户可以轻松地在内容上共享和协作.  （[Source Code](https://hub.alfresco.com/t5/alfresco-content-services-hub/project-overview-repository/ba-p/290502)）`LGPL-3.0``Java`
- [Apostrophe](http://apostrophecms.org/)  -专注于可扩展的上下文内编辑工具的Node.js CMS.  （[Demo](http://demo.apostrophecms.org/), [Source Code](https://github.com/punkave/apostrophe)）`与`Node.js`
- [b2evolution CMS](https://b2evolution.net/)  -有史以来集成度最高的CMS：b2evolution包括构建网站以发布，共享和与社区互动所需的一切.  （[Demo](https://demo.b2evolution.net), [Source Code](https://github.com/b2evolution/b2evolution)）`GPL-2.0``PHP`
- [Backdrop CMS](https://backdropcms.org/)  -适用于中小型企业和非营利组织的全面CMS.  （[Source Code](https://github.com/backdrop/backdrop)）`GPL-2.0``PHP`
- [BigTree CMS](https://www.bigtreecms.org/)  -简单明了，文档齐全，并能用PHP和MySQL编写.  （[Source Code](https://github.com/bigtreecms/BigTree-CMS)）`LGPL-2.1``PHP`
- [Bolt CMS](https://bolt.cm/)  -开源内容管理工具，力求尽可能简单明了.  （[Demo](https://try.bolt.cm/), [Source Code](https://github.com/bolt/bolt)）和PHP`
- [CMS Made Simple](http://www.cmsmadesimple.org/)  -开源内容管理系统，可更快，更轻松地管理网站内容，可从小型企业扩展到大型公司.  （[Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)）`GPL-1.0``PHP`
- [Cockpit](http://getcockpit.com)  -用于管理任何结构化内容的简单内容平台.  （[Source Code](https://github.com/agentejo/cockpit)）和PHP`
- [Concrete 5 CMS](http://www.concrete5.org/)  -开源内容管理系统.  （[Source Code](https://github.com/concrete5/concrete5)）和PHP`
- [Contao](https://contao.org/)  -Contao是功能强大的开源CMS，可让您创建专业的网站和可扩展的Web应用程序.  （[Source Code](https://github.com/contao/contao/)）`LGPL-3.0``PHP`
- [CouchCMS](http://www.couchcms.com/)  -适用于设计人员的简单开源CMS.  （[Source Code](https://github.com/CouchCMS/CouchCMS)）`CPAL-1.0``PHP`
- [Directus](http://getdirectus.com/)  -Directus是功能强大且直观的无头CMS，用于管理具有自定义体系结构的SQL数据库. 这种分离的内容管理框架基于强大且可扩展的API构建，非常适合网站，应用程序或多客户端项目.  （[Source Code](https://github.com/directus/directus)）`GPL-3.0``PHP`
- [Drupal](https://www.drupal.org/)  -先进的开源内容管理平台.  （[Source Code](http://cgit.drupalcode.org/drupal)）`GPL-2.0``PHP`
- [eLabFTW](http://www.elabftw.net)  -用于研究实验室的在线实验室笔记本. 存储实验，使用数据库查找试剂或方案，使用可信赖的时间戳合法地为实验加上时间戳，导出为pdf或zip存档，与合作者共享….  （[Demo](https://demo.elabftw.net), [Source Code](https://github.com/elabftw/elabftw)）`AGPL-3.0``PHP`
- [Expressa](https://github.com/thomas4019/expressa)  -内容管理系统，用于使用JSON模式为数据库驱动的网站提供动力. 提供权限管理和自动REST API.  MIT`Nodejs`
- [GetSimple CMS](http://get-simple.info/)  -最简单的内容管理系统. 曾经.  （[Source Code](https://github.com/GetSimpleCMS/GetSimpleCMS)）`GPL-3.0``PHP`
- [Joomla!](https://www.joomla.org/)  -先进的内容管理系统（CMS）.  （[Source Code](https://github.com/joomla/joomla-cms)）`GPL-2.0``PHP`
- [KeystoneJS](http://keystonejs.com/)  -CMS和Web应用程序平台.  （[Demo](http://demo.keystonejs.com/), [Source Code](https://github.com/keystonejs/keystone)）`与`Node.js`
- [MODX](http://modx.com/)  -MODX是先进的内容管理和发布平台. 当前版本称为“革命”.  （[Source Code](https://github.com/modxcms/revolution)）`GPL-2.0``PHP`
- [Neos](https://www.neos.io)  -Neos或TYPO3 Neos（对于版本1）是现代的开源CMS.  （[Source Code](https://git.typo3.org/Packages/TYPO3.Neos.git)）`GPL-3.0``PHP`
- [Noosfero](https://gitlab.com/noosfero/noosfero) - Noosfero is a web platform for social and solidarity economy networks with blog, e-Portfolios, CMS, RSS, thematic discussion, events agenda and collective intelligence for solidarity economy in the same system. `AGPL-3.0` `Ruby`
- [october](http://octobercms.com/)  -免费，开源，自托管的CMS平台.  （[Source Code](https://github.com/octobercms/october)）和PHP`
- [Omeka](http://omeka.org)  -创建复杂的叙述并共享丰富的馆藏，并遵循Omeka在服务器上的都柏林核心标准，专为学者，博物馆，图书馆，档案馆和发烧友而设计.  （[Demo](http://omeka.org/showcase/), [Source Code](https://github.com/omeka/Omeka)）`GPL-3.0``PHP`
- [Pagekit](https://pagekit.com/)  -创建和共享新的现代CMS.  （[Source Code](https://github.com/pagekit/pagekit)）和PHP`
- [Pico](http://picocms.org/)  -非常简单，快速的平面文件CMS.  （[Source Code](https://github.com/picocms/Pico)）和PHP`
- [Pimcore](https://www.pimcore.org/)  -多渠道体验和参与管理平台.  （[Source Code](https://github.com/pimcore/pimcore)）`GPL-3.0或更高版本``PHP`
- [Plone](https://plone.org/)  -强大的开源CMS系统.  （[Source Code](https://github.com/plone)）ZPL-2.0`` Python`
- [ProcessWire](https://processwire.com/)  -ProcessWire是一个开放源代码内容管理系统（CMS）和Web应用程序框架，旨在满足设计人员，开发人员及其客户的需求.  （[Source Code](https://github.com/ryancramerdesign/ProcessWire)）`MPL-2.0``PHP`
- [PropertyWebBuilder](http://propertywebbuilder.com)  -用于创建房地产网站的终极Ruby on Rails引擎.  （[Demo](https://propertywebbuilder.herokuapp.com), [Source Code](https://github.com/etewiah/property_web_builder)）`MIT`` Ruby`
- [Publify](https://publify.github.io/)  -简单但功能齐全的Web发布软件.  （[Source Code](https://github.com/publify/publify)）`MIT`` Ruby`
- [REDAXO](https://www.redaxo.org)  -简单，灵活和有用的内容管理系统（仅提供德语文档）.  （[Source Code](https://github.com/redaxo/redaxo)）和PHP`
- [Redaxscript](https://redaxscript.com)  -适用于MySQL，SQLite和PostgreSQL的超轻量级CMS.  （[Demo](https://demo.redaxscript.com/login), [Source Code](https://github.com/redaxmedia/redaxscript)）`GPL-3.0``PHP`
- [Roadiz](https://www.roadiz.io/)  -基于节点系统的现代CMS，可以处理多种类型的服务.  （[Source Code](https://github.com/roadiz/roadiz)）和PHP`
- [SilverStripe](https://www.silverstripe.org)  -易于使用的CMS具有强大的MVC框架底层.  （[Demo](http://demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)）`BSD-3-Clause``PHP`
- [SPIP](http://www.spip.net/fr)  -面向协作工作，多语言环境和网络作者使用简便的Internet发布系统.  （[Source Code](https://core.spip.net/projects/spip/repository)）`GPL-2.0``PHP`
- [Squidex](http://squidex.io)  -无头CMS，基于MongoDB，CQRS和事件源.  （[Demo](http://cloud.squidex.io), [Source Code](https://github.com/Squidex/squidex)）.NET
- [Strapi](https://strapi.io/)  -最先进的开源内容管理框架（headless-CMS），可轻松构建强大的API.  （[Source Code](https://github.com/strapi/strapi)）`与`Node.js`
- [Subrion](http://www.subrion.org) - Subrion is a free open source content management system that allows you to build websites for any purpose. Yes, from blog to corporate mega portal. ([Demo](http://demos.subrion.com), [Source Code](https://github.com/intelliants/subrion)）`GPL-3.0``PHP`
- [Textpattern](http://textpattern.com/)  -灵活，优雅且易于使用的CMS.  （[Demo](http://textpattern.co/demo), [Source Code](https://github.com/textpattern/textpattern)）`GPL-2.0``PHP`
- [Typemill](https://typemill.net/)  -具有基于vue.js的可视Markdown编辑器的友好作者的flat-file-cms.  （[Source Code](https://github.com/typemill/typemill)）和PHP`
- [TYPO3](https://typo3.org/)  -具有大型社区的强大而先进的CMS.  （[Source Code](https://github.com/TYPO3/TYPO3.CMS)）`GPL-2.0``PHP`
- [Umbraco](https://umbraco.com/)  -友好的CMS. 具有令人惊叹的社区的免费和开放源代码.  （[Source Code](https://github.com/umbraco/Umbraco-CMS)）.NET
- [Wagtail](https://wagtail.io/)  -专注于灵活性和用户体验的Django内容管理系统.  （[Source Code](https://github.com/wagtail/wagtail)）`BSD-3-Clause`` Python`
- [WonderCMS](http://www.wondercms.com) -WonderCMS是自2008年以来最小的平面文件CMS.（[Demo](https://www.wondercms.com/demo), [Source Code](https://github.com/robiso/wondercms)）和PHP`
- [WordPress](https://wordpress.org/)  -世界上最常用的博客和CMS引擎.  （[Source Code](https://github.com/WordPress/WordPress)）`GPL-2.0``PHP`
- [WriteFreely](https://writefreely.org)  -编写用于启动极简联盟博客或整个社区的软件.  （[Source Code](https://github.com/writeas/writefreely)）`AGPL-3.0``Go`

### Recipe management

- [Mealie](https://hay-kot.github.io/mealie/)  -材料设计启发了食谱管理者，提供类别和标签管理，购物清单，用餐计划和网站自定义.  Mealie专注于简单的用户交互，以保持整个家庭使用该应用程序.  （[Source Code](https://github.com/hay-kot/mealie)）和Python
- [OpenEats](https://github.com/open-eats/OpenEats)  -食谱管理站点，允许用户创建，存储，共享和评分食谱，创建食品杂货清单等.  （[Demo](https://open-eats.github.io/)）和Python
- [RecipeSage](https://github.com/julianpoy/recipesage)  -食谱管理员，膳食计划组织者和购物清单管理员，可以直接从任何URL导入食谱.  （[Demo](https://recipesage.com)）`AGPL-3.0`Node.JS`
- [Tandoor Recipes](https://docs.tandoor.dev/)  -Django应用程序，用于使用内置模型或托管PDF，图像或其他文件的外部存储提供程序来管理，标记和搜索配方.  （[Demo](https://app.tandoor.dev/), [Source Code](https://github.com/vabene1111/recipes/)）和Python

### E-commerce

- [Attendize](https://www.attendize.com/)  -门票销售和活动管理平台.  （[Source Code](https://github.com/attendize/attendize)）`AAL`` PHP`
- [Bagisto](https://bagisto.com/en/)  -领先的Laravel开源电子商务框架，具有多库存来源，税收，本地化，直接发货和更多激动人心的功能.  （[Demo](https://demo.bagisto.com/), [Source Code](https://github.com/bagisto/bagisto)）和PHP`
- [CoreShop](https://www.coreshop.org)  -CoreShop是Pimcore的电子商务插件.  （[Source Code](https://github.com/coreshop/CoreShop)）`GPL-3.0``PHP`
- [Drupal Commerce](https://drupalcommerce.org)  -Drupal Commerce是Drupal CMS受欢迎的电子商务模块，支持数十种与付款，运输和购物相关的模块.  （[Source Code](https://github.com/drupalcommerce/commerce)）`GPL-2.0``PHP`
- [Magento](https://magento.com/)  -开放式全渠道创新的领先提供商.  （[Demo](https://magento.com/schedule-a-demo), [Source Code](https://github.com/magento/magento2)）OSL-3.0`PHP
- [Microweber](https://microweber.com/)  -拖放CMS和在线商店.  （[Demo](http://demo.microweber.org/), [Source Code](https://github.com/microweber/microweber)）`Apache-2.0``PHP`
- [OpenBazaar](https://www.openbazaar.org)  -使用加密货币的去中心化市场.  （[Source Code](https://github.com/openbazaar/openbazaar-go)）`MIT`` Go`
- [OpenCart](https://www.opencart.com)  -免费的开源购物车解决方案.  （[Source Code](https://github.com/opencart/opencart)）`GPL-3.0``PHP`
- [Open Classifieds](http://open-classifieds.com/)  -用于分类网站的免费开源，自托管CMS.  （[Source Code](https://github.com/open-classifieds/openclassifieds2)）`GPL-3.0``PHP`
- [Open Source POS](https://www.opensourcepos.org/)  -开源销售点是基于Web的销售点系统.  （[Demo](https://demo.opensourcepos.org/), [Source Code](https://github.com/opensourcepos/opensourcepos)）和PHP`
- [OXID eShop](http://oxidforge.org)  -OXID eShop是一款灵活的开源电子商务软件，具有多种功能.  （[Demo](http://demoshop.oxid-esales.com/community-edition/), [Source Code](https://github.com/OXID-eSales/oxideshop_ce)）`GPL-3.0``PHP`
- [Open Food Network](https://openfoodnetwork.org/)  -本地食品在线市场. 它启用了一个独立的在线食品商店网络，该网络将农民和食品中心与个人和本地企业联系起来.  （[Source Code](https://github.com/openfoodfoundation/openfoodnetwork)）`AGPL-3.0``Ruby`
- [PrestaShop](https://www.prestashop.com/)  -PrestaShop提供了一个免费的，开源的，完全可扩展的电子商务解决方案.  （[Demo](http://demo.prestashop.com/), [Source Code](https://github.com/PrestaShop/PrestaShop)）OSL-3.0`PHP
- [Pretix](https://pretix.eu/)  -基于Django的活动门票销售平台.  （[Source Code](https://github.com/pretix)）`Apache-2.0`` Python`
- [Reaction Commerce](https://reactioncommerce.com/)  -可定制的实时响应式JavaScript商业平台.  （[Source Code](https://github.com/reactioncommerce/reaction)）`GPL-3.0`` Nodejs`
- [Saleor](http://getsaleor.com/)  -基于Django的开源电子商务店面.  （[Demo](https://demo.getsaleor.com/), [Source Code](https://github.com/mirumee/saleor)）`BSD-3-Clause`` Python`
- [Shuup](https://www.shuup.com/)  -Django支持的针对小型和大型站点的完全可自定义的开源电子商务框架.  （[Source Code](https://github.com/shuup/shuup)）`AGPL-3.0``Python`
- [Shopware Community Edition](https://shopware.com/community/)  -德国制造的基于PHP的开源电子商务软件.  （[Demo](https://www.shopware.com/en/test-demo/), [Source Code](https://github.com/shopware/platform)）和PHP`
- [Solidus](https://solidus.io/)  -一个免费的开源电子商务平台，可让您完全控制商店.  （[Demo](http://demo.solidus.io/), [Source Code](https://github.com/solidusio/solidus)）`BSD-3-Clause``Ruby`
- [Spree Commerce](https://spreecommerce.org)  -Spree是针对Ruby on Rails的完整，模块化和API驱动的开源电子商务解决方案.  （[Demo](http://new-ux.spreecommerce.org/), [Source Code](https://github.com/spree/spree)）`BSD-3-Clause``Ruby`
- [Sylius](http://sylius.org/)  -Symfony2支持的开放源代码全栈电子商务平台.  （[Demo](http://sylius.org/demo), [Source Code](https://github.com/Sylius/Sylius)）和PHP`
- [Thelia](http://thelia.net/)  -Thelia是一个开源且灵活的电子商务解决方案.  （[Demo](http://demo.thelia.net/), [Source Code](https://github.com/thelia/thelia)）`LGPL-3.0``PHP`
- [WooCommerce](https://www.woothemes.com/woocommerce/)  -基于WordPress的电子商务解决方案.  （[Source Code](https://github.com/woothemes/woocommerce)）`GPL-3.0``PHP`

## DNS

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#dns_

- [blocky](https://github.com/0xERR0R/blocky) - Fast and lightweight DNS proxy (like Pi-hole) as ad-blocker for local network with many features. `Apache-2.0` `Go`
- [CoreDNS](https://coredns.io/)  -插件驱动的DNS服务器，支持代理到Google的HTTP-over-HTTPS.  （[Source Code](https://github.com/coredns/coredns)）`Apache-2.0``Go`
- [Maza ad blocking](https://maza-ad-blocking.andros.dev/)  -本地广告拦截器. 像Pi-hole一样，但在本地使用操作系统.  （[Source Code](https://github.com/tanrax/maza-ad-blocking)）`Apache-2.0`` Bash`
- [nsupdate.info](https://www.nsupdate.info/)  -nsupdate.info是动态DNS服务.  （[Demo](https://www.nsupdate.info/account/register/), [Source Code](https://github.com/nsupdate-info/nsupdate.info)）`BSD-3-Clause`` Python`
- [SPF Toolbox](http://spftoolbox.com)  -用于查找DNS记录（例如SPF，MX，Whois等）的应用程序.  （[Source Code](https://github.com/charlesabarnes/SPFtoolbox)）和PHP`

## Document Management

**[`^        back to top        ^`](#)**

- [DOCAT](https://github.com/randombenj/docat)  -托管您的文档. 简单的. 版本化. 想要.  MIT python /泊坞窗
- [Docspell](https://docspell.org)  -自动标记文档组织者和存档.  （[Source Code](https://github.com/eikek/docspell)）`GPL-3.0`` Scala / Java`
- [EdPaper](https://github.com/Edraens/EdPaper)  -具有用户管理功能的PDF组织者. 麻省理工学院PHP
- [EveryDocs](https://github.com/jonashellmann/everydocs-core/)  -一个供个人使用的简单文档管理系统，具有基本功能以数字方式组织您的文档.  GPL-3.0`Ruby`
- [Mayan EDMS](http://www.mayan-edms.com)  -免费的开源电子文档管理系统. 电子文件库，具有预览生成，OCR和自动分类等功能.  （[Source Code](https://gitlab.com/mayan-edms/mayan-edms)）`Apache-2.0`` Python`
- [Papermerge](https://www.papermerge.com)  -专注于扫描文档（电子档案）的开源文档管理系统. 具有与保管箱/ Google驱动器类似的文件浏览功能.  OCR，全文搜索，文本覆盖/选择.  （[Source Code](https://github.com/ciur/papermerge)）`Apache-2.0`` Python`
- [Paperless](https://github.com/the-paperless-project/paperless)  -扫描，索引和存档所有纸质文档.  GPL-3.0 Python
- [Paperless-ng](https://github.com/jonaswinkler/paperless-ng)  -无纸化的叉子，增加了新的界面，并在引擎盖下进行了许多其他更改. 扫描，索引和存档所有纸质文档.  GPL-3.0 Python
- [paper{s}pace](https://dedicatedcode.com/projects/)  -一个小型Web应用程序，用于管理您的所有脱机文档. 提供可搜索的文档存储空间，并提醒您即将执行的任务.  （[Source Code](https://gitlab.com/dedicatedcode/paperspace)）MIT Java
- [Teedy](https://teedy.io/)  -（Ex SismicsDocs）轻量级文档管理系统，包含大型昂贵解决方案所具有的所有功能.  （[Source Code](https://github.com/sismics/docs)）`GPL-2.0`` Java`

## E-books and Integrated Library Systems (ILS)

**[`^        back to top        ^`](#)**

_Some [Content Management System](#content-management-systems-cms) 和 [Archiving 和 Digital Preservation](#archiving-和-digital-preservation-dp) solutions also overlap with library 和 institutional repository software._

### Personal e-book management software.

- [Calibre](https://calibre-ebook.com/)  -电子书库管理器，可以查看，转换和分类大多数主要电子书格式的电子书，并为远程客户端提供内置的Web服务器.  （[Demo](https://calibre-ebook.com/demo), [Source Code](https://launchpad.net/calibre)）`GPL-3.0`` Python`
  - [BicBucStriim](http://projekte.textmulch.de/bicbucstriim/)  -提供基于Web的对Calibre Library的电子书收藏的访问.  （[Source Code](https://github.com/rvolz/BicBucStriim)）和PHP`
  - [Calibre Web](https://github.com/janeczku/calibre-web)  -Web应用程序提供了一个干净的界面，以使用现有的Calibre数据库浏览，阅读和下载电子书.  GPL-3.0 Python
  - [COPS](https://blog.slucas.fr/en/oss/calibre-opds-php-server)  -轻巧的电子书服务器，可替代Caliber内容服务器或Calibre2OPDS.  （[Demo](http://cops-demo.slucas.fr/index.php), [Source Code](https://github.com/seblucas/cops)）`GPL-2.0``PHP`
  - [The Epube](https://tt-rss.org/the-epube)  -使用EPUB.js，Bootstrap和Calibre的自托管Web EPUB阅读器.  （[Source Code](https://git.tt-rss.org/fox/the-epube)）`GPL-3.0``PHP`
- [Komga](https://komga.org)  -具有API和OPDS支持的漫画/漫画/ BD的媒体服务器，用于浏览您的图书馆的现代Web界面以及Web阅读器.  （[Source Code](https://github.com/gotson/komga)）`MIT`` Java / Docker`
- [Mango](https://github.com/hkalexling/Mango)  -带有内置MangaDex下载器的Manga服务器和Web阅读器.  MIT水晶
- [pyShelf](https://pyshelf.com)  -轻量级电子书服务器.  （[Source Code](https://github.com/th3r00t/pyShelf)）`GPL-3.0`` Python`

### Enterprise-class library management software.

- [Evergreen](https://evergreen-ils.org)  -高度可扩展的图书馆软件，可帮助图书馆顾客查找图书馆资料，并帮助图书馆管理，编目和分发这些资料.  （[Source Code](https://github.com/evergreen-library-system/Evergreen)）`GPL-2.0``PL / pgSQL`
- [Koha](https://koha-community.org/)  -企业级ILS，具有用于获取，流通，编目，标签打印，无法访问Internet的离线流通等模块，以及更多其他功能.  （[Demo](https://koha-community.org/demo/), [Source Code](https://github.com/Koha-Community/Koha)）`GPL-3.0`` Perl`
- [RERO ILS](https://rero21.ch/)  -可以作为具有联盟功能的服务运行的大规模ILS，主要用于图书馆网络. 包括大多数标准模块（发行，获取，分类等）以及基于Web的公共和专业界面.  （[Demo](https://ils.test.rero.ch/), [Source Code](https://github.com/rero/rero-ils)）`AGPL-3.0``Python / Other`

### Institutional repository and digital library software.

- [DSpace](http://dspace.org/)  -交钥匙存储库应用程序，提供对数字资源的持久访问.  （[Source Code](https://github.com/DSpace/DSpace)）`BSD-3-Clause`` Java`
- [EPrints](https://www.eprints.org/)  -具有主要针对学术机构的灵活的元数据和工作流模型的数字文档管理系统.  （[Demo](http://demoprints.eprints.org/), [Source Code](https://github.com/eprints/eprints)）`GPL-3.0`` Perl`
- [Fedora Commons Repository](https://fedorarepository.org/)  -用于管理和传播数字内容的健壮和模块化的存储系统，特别适合于数字图书馆和档案馆（用于访问和保存）.  （[Source Code](https://github.com/fcrepo4/fcrepo4)）Apache-2.0`` Java`
- [Islandora](https://islandora.ca/)  -Drupal模块，用于浏览和管理基于Fedora的数字存储库.  （[Source Code](https://github.com/Islandora/islandora)）`GPL-3.0``PHP`
- [Samvera Hyrax](https://samvera.org/)  -Samvera框架的前端，该框架本身是Ruby on Rails应用程序，用于浏览和管理基于Fedora的数字存储库.  （[Source Code](https://github.com/samvera/hyrax)）`Apache-2.0`Ruby`

## Federated Identity/Authentication

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#identity-management_

## Feed Readers

**[`^        back to top        ^`](#)**

- [CommaFeed](https://www.commafeed.com/)  -Google阅读器启发了自托管的RSS阅读器.  （[Source Code](https://github.com/Athou/commafeed)）Apache-2.0`` Java`
- [Feedbin](https://feedbin.com/)  -简单，快速且美观的RSS阅读器.  （[Source Code](https://github.com/feedbin/feedbin)）`MIT`` Ruby`
- [FeedHQ](https://feedhq.org/)  -FeedHQ是基于Web的供稿阅读器.  （[Source Code](https://github.com/feedhq/feedhq)）`BSD-3-Clause`` Python`
- [FreshRSS](http://freshrss.org/)  -可自行托管的RSS Feed聚合器.  （[Demo](http://demo.freshrss.org/i/), [Source Code](https://github.com/FreshRSS/FreshRSS), [Clients](https://github.com/Alkarex/EasyRSS)）`AGPL-3.0``PHP`
- [JARR](http://1pxsolidblack.pl/jarr-en.html)  -JARR（另一个RSS阅读器）是基于Web的新闻聚合器和阅读器（Newspipe的分支）.  （[Demo](https://jarr.info/login?next=%2F), [Source Code](https://github.com/jaesivsm/JARR)）`AGPL-3.0``Python`
- [Kriss Feed](http://tontof.net/kriss/feed/)  -简单智能（或愚蠢的）提要阅读器.  （[Demo](http://tontof.net/feed/), [Source Code](https://github.com/tontof/kriss_feed)）`CC0-1.0``PHP`
- [Leed](https://github.com/LeedRSS/Leed)  -Leed（用于Light Feed）是一个免费且简约的RSS聚合器.  （[Source Code](https://github.com/ldleman/Leed)）`AGPL-3.0``PHP`
- [Leselys](https://github.com/socketubs/leselys)  -非常优雅的RSS阅读器.  AGPL-3.0 Python
- [Lite-Reader](https://github.com/cubny/lite-reader)  -使用简单精简的应用程序在自己的计算机上阅读供稿.  （[Demo](http://cubny.com/lite-reader/)）`BSD-3-Clause``PHP`
- [Moonmoon](http://moonmoon.org/)  -简单的提要聚合器（像行星一样）：它仅汇总提要并将其吐出到单个页面中.  （[Source Code](https://github.com/mauricesvay/moonmoon)）`BSD-3-Clause``PHP`
- [Miniflux](https://miniflux.net/)  -Miniflux 2是使用Go和PostgreSQL编写的极简主义和开源新闻阅读器.  （[Source Code](https://github.com/miniflux/miniflux)）`Apache-2.0``Go`
- [NewsBlur](http://www.newsblur.com/)  -NewsBlur是一个个人新闻阅读器，它使人们聚在一起谈论世界. 旧乐器的新声音.  （[Source Code](https://github.com/samuelclay/NewsBlur)）和Python
- [newsdash](https://github.com/buzz/newsdash)  -受iGoogle和Netvibes启发的新闻仪表板.  AGPL-3.0 NodeJS
- [Newspipe](https://git.sr.ht/~cedric/newspipe)  -Newspipe是网络新闻阅读器.  （[Demo](https://www.newspipe.org/signup)）`AGPL-3.0``Python`
- [reader](https://github.com/lemon24/reader)  -Python feed阅读器Web应用程序和库（因此您可以使用它来构建自己的库），仅具有标准库和纯Python依赖项.  BSD-3-Clause Python
- [Reader-Self](http://readerself.com/)  -自托管的RSS阅读器（php / mysql或sqlite）-Google阅读器替代.  （[Source Code](https://github.com/readerself/readerself)）`GPL-3.0``PHP`
- [RSS Monster](https://github.com/pietheinstrengholt/rssmonster)  -RSS Monster是一种易于使用的基于Web的RSS聚合器，并且与Fever API兼容，与Google Fever API兼容. 麻省理工学院PHP
- [Selfoss](http://selfoss.aditu.de/)  -新的多功能rss阅读器，实时流，混搭，聚合Web应用程序.  （[Source Code](https://github.com/SSilence/selfoss)）`AGPL-3.0``PHP`
- [Sismics Reader](http://sismics.com/reader/)  -免费和开源的供稿阅读器，包括所有主要的Google Reader功能.  （[Demo](https://www.sismics.com/reader/#!/demo), [Source Code](https://github.com/sismics/reader)）`GPL-2.0`` Java`
- [Stringer](https://github.com/swanson/stringer)  -进行中的自托管反社会RSS阅读器. 麻省理工学院Ruby
- [Temboz](https://github.com/fazalmajid/temboz)  -两栏式提要阅读器，强调过滤功能以管理信息超载. 麻省理工学院Python
- [Tiny Tiny RSS](https://tt-rss.org)  -开源的基于Web的新闻源（RSS / Atom）阅读器和聚合器.  （[Demo](http://framanews.org/), [Source Code](https://git.tt-rss.org/fox/tt-rss)）`GPL-3.0``PHP`
  - [gritttt-rss](http://gritttt-rss.nicolashoening.de/)  -Tiny Tiny RSS的更多功能.  （[Source Code](https://github.com/nhoening/gritttt-rss)）`BSD-2-Clause`` Python`
  - [ttrss-mobile](https://github.com/mboinet/ttrss-mobile)  -适用于Tiny Tiny RSS的移动网络应用程序.  AGPL-3.0 Javascript
  - [ttrss-reader](https://github.com/kucrut/ttrss-reader)  -TTRSS的轻量级响应式客户端.  GPL-2.0 Javascript
- [Winds](https://getstream.io/winds/)  ⚠-使用React / Redux / Sails / Node和Stream构建的开源和漂亮的RSS阅读器. 它展示了由Stream API驱动的个性化提要.  （[Demo](https://winds.getstream.io/), [Source Code](https://github.com/GetStream/Winds)）`BSD-3-Clause``Nodejs`

_RSS / Atom自动化_

- [Feedpushr](https://github.com/ncarlier/feedpushr)  -强大的RSS聚合器，能够转换文章并将其发送到许多输出. 单个二进制文件，可通过插件扩展.  GPL-3.0`Go`
- [Full-Text RSS](https://fivefilters.org/content-only)  -从新闻站点和博客中提取文章内容，并将仅包含故事摘要的RSS feed转换为全文feed. 由FiveFilters.org开发.  （[Source Code](https://bitbucket.org/fivefilters/full-text-rss)）`GPL-3.0``PHP`
- [Goeland](https://github.com/slurdge/goeland) - Reads RSS/Atom feeds and filter/digest them to create beautiful emails. `MIT` `Go`
- [PolitePol](https://github.com/taroved/pol)  -用于为任何网页创建RSS提要的在线工具.  （[Demo](http://politepol.com)）和Python
- [RSS Fulltext Proxy](https://github.com/Kombustor/rss-fulltext-proxy)  -镜像RSS feed，以返回从网站提取的项目的全部内容.  `MIT``NodeJS`
- [RSS Merger](https://github.com/taophp/rss-merger)  -PHP脚本，它将多个RSS / Atom提要作为输入并将它们合并为一个RSS提要.  `GPL-2.0``PHP`
- [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge)  -rss-bridge是一个PHP项目，能够为没有网站的网站生成ATOM供稿.  `Unlicense``PHP`
- [RSS2EMail](https://github.com/rss2email/rss2email)  -提取RSS / Atom提要并将新的内容推送到任何电子邮件接收者，支持OPML.  GPL-2.0 Python
- [Screaming Liquid Tiger](https://github.com/herrbischoff/screaming-liquid-tiger)  -简单的脚本，可从同一文件夹中的媒体文件列表自动生成有效的RSS和Atom提要. 麻省理工学院PHP


## File Sharing and Synchronization

**[`^        back to top        ^`](#)**

_Some [Groupware](#groupware) 解决方案还具有文件共享和同步功能.

#### Distributed filesystems

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#distributed-filesystems_

#### File transfer/synchronization

- [Git Annex](https://git-annex.branchable.com/)  -计算机，服务器，外部驱动器之间的文件同步.  （[Source Code](https://git.joeyh.name/index.cgi/git-annex.git/)）`GPL-3.0``Haskell`
- [Kinto](https://kinto.readthedocs.org)  -Kinto是具有同步和共享功能的极简JSON存储服务.  （[Source Code](https://github.com/Kinto)）`Apache-2.0`` Python`
- [myDrive](https://github.com/subnub/myDrive)  -全功能的在线存储解决方案，上传/下载文件，照片/视频查看器等，所有这些都通过Web客户端完成.  （[Demo](https://mydrive-demo.herokuapp.com/)）GPL-3.0`Node.js`
- [Nextcloud](https://nextcloud.com/) -访问并共享您的文件，日历，联系人，邮件和 [more](https://apps.nextcloud.com/) 从任何设备，根据您的条件.  （[Demo](https://demo.nextcloud.com/), [Source Code](https://github.com/nextcloud/server)）`AGPL-3.0``PHP`
- [OpenSSH/SFTP](http://www.openssh.com/)  -安全文件传输程序.  （[Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh)）`BSD-2-Clause``C`
- [ownCloud](https://owncloud.org/) - All-in-one solution for saving, synchronizing, viewing, editing and sharing files, calendars, address books and more. ([Source Code](https://github.com/owncloud/core), [Clients](https://github.com/owncloud/core/wiki/Apps)）`AGPL-3.0``PHP`
- [Pydio](https://pydio.com/)  -将任何Web服务器变成功能强大的文件管理系统，以及主流云存储提供商的替代方案.  （[Source Code](https://github.com/pydio/pydio-core)）`AGPL-3.0``PHP`
- [Samba](https://www.samba.org/)  -Samba是用于Linux和Unix的标准Windows互操作性程序套件. 它使用SMB / CIFS协议为所有客户端提供安全，稳定和快速的文件和打印服务.  （[Source Code](https://git.samba.org/samba.git/)）`GPL-3.0`` C`
- [Seafile](https://www.seafile.com/en/home/)  -团队和组织主要的文件托管和共享解决方案.  （[Source Code](https://github.com/haiwen/seafile)）`GPL-2.0 / GPL-3.0 / AGPL-3.0 / Apache-2.0`` C`
- [SparkleShare](http://sparkleshare.org/)  -自托管，即时，安全的文件同步.  （[Source Code](https://github.com/hbons/SparkleShare)) `GPL-3.0` `C#`
- [Syncany](https://www.syncany.org/)  -用于任意存储后端的安全文件同步软件，一个开源云存储和文件共享应用程序. 安全地将文件同步到任何类型的存储.  GPL-3.0 Java
- [Syncthing](https://syncthing.net/)  -同步是一种开源的对等文件同步工具.  （[Source Code](https://github.com/syncthing/syncthing)）`MPL-2.0``Go`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/)  -Unison是OSX，Unix和Windows的文件同步工具.  `GPL-3.0``OCaml`
- [Z-Push](http://z-push.org/) -微软的实施 [ActiveSync](https://en.wikipedia.org/wiki/ActiveSync) 协议.  （[Source Code](https://stash.z-hub.io/projects/ZP/repos/z-push)）`AGPL-3.0``PHP`

#### Peer-to-peer filesharing

- [bittorrent-tracker](https://webtorrent.io/)  -简单，健壮的BitTorrent跟踪器（客户端和服务器）实施.  （[Source Code](https://github.com/feross/bittorrent-tracker)）`与`Node.js`
- [cloud-torrent](https://github.com/jpillora/cloud-torrent)  -带有HTTP可检索或可流式下载文件的Torrent Web客户端.  AGPL-3.0`Go
- [Dat Project](https://datproject.org)  -由大型模块生态系统构建的强大的分散式文件共享应用程序.  （[Source Code](https://github.com/datproject)）`与`Node.js`
- [FilePizza](http://file.pizza/)  -浏览器中的点对点文件传输.  （[Source Code](https://github.com/kern/filepizza)）`BSD-3-Clause``Nodejs`
- [instant.io](https://github.com/feross/instant.io)  -通过WebTorrent进行流文件传输.  （[Demo](https://instant.io)）`与`Node.js`
- [Magnetico](https://github.com/boramalper/magnetico)  -Magnetico是第一个为最终用户设计的自主（自托管）BitTorrent DHT搜索引擎套件.  AGPL-3.0 Python
- [Magnetissimo](https://github.com/sergiotapia/magnetissimo)  -搜索引擎为所有流行的洪流站点编制索引. 麻省理工学院的长生不老药
- [Opentracker](http://erdgeist.org/arts/software/opentracker/)  -打开和免费的bittorrent跟踪器. 它旨在最小化资源使用，旨在在您的wlan路由器上运行.  （[Source Code](http://erdgeist.org/gitweb/opentracker/)）`啤酒``C`
- [peerflix-server](https://github.com/asapach/peerflix-server)  -下载种子文件，并提供直接链接下载或直接链接流.  MIT`Nodejs`
- [qBittorrent](https://www.qbittorrent.org/)  -具有功能丰富的Web UI的远程访问的免费跨平台bittorrent客户端.  （[Source Code](https://github.com/qbittorrent/qBittorrent)）`GPL-2.0`` C ++`
- [rartracker](https://github.com/swetorrentking/rartracker)  -完整的私人bittorrent跟踪器.  `WTFPL``PHP`
- [Send](https://github.com/timvisee/send)  -简单，私有，端到端的加密临时文件共享，最初由Mozilla构建.  （[Clients](https://github.com/timvisee/send#clients)）`MPL-2.0`Nodejs`
- [Torrents.csv](https://gitlab.com/dessalines/torrents.csv)  -可自行托管的洪流搜索引擎.  GPL-3.0`Rust
- [Transmission](https://transmissionbt.com/)  -快速，轻松，免费的Bittorrent客户端.  （[Source Code](https://github.com/transmission/transmission)）`GPL-3.0`` C`

#### Object storage/file servers

- [Minio](https://minio.io/)  -Minio是与Amazon S3 API兼容的开源对象存储服务器.  （[Source Code](https://github.com/minio/minio)）`Apache-2.0``Go`
- [SeaweedFS](https://github.com/chrislusf/seaweedfs)  -SeaweedFS是一个开源分布式文件系统，支持WebDAV，S3 API，FUSE挂载，HDFS等，针对大量小文件进行了优化，并且易于添加容量.  `Apache-2.0``Go`
- [Zenko CloudServer](https://www.zenko.io/cloudserver)  -Zenko CloudServer，这是处理Amazon S3协议的服务器的开源Node.js实现.  （[Source Code](https://github.com/scality/S3)）`Apache-2.0`` Nodejs`

#### Single-click/drag-n-drop upload

- [BoZoN](https://github.com/broncowdd/BoZoN)  -极简主义拖放文件共享应用程序.  `AGPL-3.0``PHP`
- [Chibisafe](https://lolisafe.moe/)  -在节点中编写了快速的文件上传器和令人敬畏的地堡.  （[Source Code](https://github.com/weebdev/chibisafe)）`与`Node.js`
- [Coquelicot](https://coquelicot.potager.org/)  -Coquelicot是一个“一键式”文件共享Web应用程序，其重点是保护用户的隐私.  （[Source Code](https://coquelicot.potager.org/gitweb/?p=coquelicot.git)）`AGPL-3.0``Ruby`
- [elixire](https://elixi.re)  -简单但高级的屏幕截图上传和链接缩短服务.  （[Source Code](https://gitlab.com/elixire/elixire), [Clients](https://gitlab.com/elixire/elixiremanager)）`AGPL-3.0``Python`
- [fibridge](https://github.com/anderspitman/fibridge-proxy-rs)  -无需上传即可从浏览器中流式传输大文件. 麻省理工学院
- [FireShare](https://github.com/rockmanvnx6/FireShare)  -全栈，发布订阅，实时安全文件共享系统.  （[Demo](https://auspham.dev/FireShare)）`与`Node.js`
- [FileShelter](https://github.com/epoupon/fileshelter)  -FileShelter是一种自托管软件，可让您轻松地通过Internet共享文件.  （[Demo](http://fileshelter.demo.poupon.io/)）`GPL-3.0`` C ++`
- [Files Sharing](https://github.com/axeloz/filesharing)  -基于唯一和临时链接的开源和自托管文件共享应用程序.  `GPL-3.0``PHP`
- [Gokapi](https://github.com/Forceu/gokapi)  -轻量级服务器，用于共享文件，该文件将在一定数量的下载或几天后过期. 与停产的Firefox Send类似，不同之处在于只允许管理员上传文件.  GPL-3.0`Go`
- [goploader](https://gpldr.in/)  -易于与服务器端加密共享文件，符合curl / httpie / wget.  （[Source Code](https://github.com/Depado/goploader)）`MIT`` Go`
- [imgpush](https://github.com/hauxir/imgpush)  -imgpush是一种自托管文件上传服务，可以轻松集成到其他Web应用程序中. 麻省理工学院Python
- [ipfs.pics](https://github.com/ipfspics/server)  -ipfs.pics是一个分布式图像托管网站.  `AGPL-3.0``PHP`
- [Jirafeau](https://gitlab.com/mojo42/Jirafeau)  -Jirafeau是允许以简单方式上传文件并提供唯一链接的网站.  （[Demo](http://jirafeau.net/)）`AGPL-3.0``PHP`
- [Kleeja](https://kleeja.net/) -文件上传/共享应用程序，自2007年以来已被成千上万的网站管理员使用.[Source Code](https://github.com/kleeja-official/kleeja)）`GPL-2.0``PHP`
- [linx-server](https://github.com/andreimarcu/linx-server)  -具有API，自动到期，删除密钥和Web种子支持的简单文件共享和pastebin.  （[Demo](https://demo.linx-server.net/)）`GPL-3.0``Go`
- [lufi](https://framagit.org/fiat-tux/hat-softwares/lufi)  -让我们上传客户端加密的文件.  （[Demo](https://demo.lufi.io), [Source Code](https://framagit.org/fiat-tux/hat-softwares/lufi/tree/master)）`AGPL-3.0``Perl`
- [lutim](https://github.com/ldidry/lutim)  -让我们上传该图像.  `AGPL-3.0``Perl`
- [OnionShare](https://github.com/micahflee/onionshare)  -安全匿名共享任何大小的文件.  GPL-2.0 Python
- [PictShare](https://www.pictshare.net/)  -PictShare是一种多语言，开放源代码的图像托管服务，具有简单的调整大小和上载API.  （[Source Code](https://github.com/chrisiaut/pictshare)）`Apache-2.0``PHP`
- [Plik](https://github.com/root-gg/plik)  -Plik是可扩展且友好的临时文件上传系统.  （[Demo](https://plik.root.gg/)）`MIT`` Go`
- [Pomf](https://github.com/Pomf/Pomf)  -简单的文件上传和共享，这是现已关闭的网站Pomf.se的来源. 麻省理工学院PHP
- [ProjectSend](http://www.projectsend.org/)  -上传文件并将其分配给您创建的特定客户端. 将对这些文件的访问权授予客户.  （[Source Code](https://github.com/ignacionelson/ProjectSend)）`GPL-2.0``PHP`
- [PsiTransfer](https://github.com/psi-4ward/psitransfer)  -简单的开源自托管文件共享解决方案，具有强大的上传/下载恢复和密码保护功能.  BSD-2-Clause NodeJS
- [Pste](https://dev.pste.pw/)  -只是一个受pomf.se和teknik.io等公司启发的简单文件托管应用程序.  （[Source Code](https://github.com/FoxDev/pste)）`GPL-3.0`` Python`
- [Share](https://github.com/MrDemonWolf/share)  -简单但高级的上载器-使用管理员的调节工具上载文件，图像和文本. 可用于朋友和家人，也可仅用于您. 与ShareX等集成.  MIT`Nodejs`
- [Sharry](https://github.com/eikek/sharry)  -通过可恢复的上载和下载，在经过身份验证的用户和匿名用户之间（两种方式）轻松地通过Internet共享文件.  `GPL-3.0``Scala / Java`
- [Uguu](https://uguu.se/)  -存储文件并在X时间后删除.  （[Source Code](https://github.com/nokonoko/uguu)）和PHP`
- [Up1](https://github.com/Upload/Up1)  -客户端加密映像主机.  MIT`Nodejs`
- [Web-File-Uploader](https://v2.femto.pw/)  -让人们上传和共享图像和文件的简单工具.  （[Source Code](https://github.com/femto-apps/web-file-uploader)）`与`Node.js`
- [XBackBone](https://github.com/SergiX44/XBackBone)  -集成了即时共享工具的简单，快速，轻巧的文件管理器，例如ShareX（适用于Windows的免费开放源屏幕截图实用程序）.  `AGPL-3.0``PHP`
- [YouTransfer](http://www.youtransfer.io)  -YouTransfer是一个简单但优雅的自托管文件传输和共享解决方案.  （[Demo](http://demo.youtransfer.io/), [Source Code](https://github.com/remie/YouTransfer)）`Apache-2.0`` Nodejs`
- [Zipline](https://zipline.diced.wtf/)  -轻巧，快速且可靠的文件共享服务器，通常与ShareX一起使用，提供基于反应的Web UI和快速API.  （[Source Code](https://github.com/diced/zipline)）`与`Node.js`

#### Command-line file upload

- [Beauties](https://github.com/dsx/beauties)  -用Go编写的极简文件共享，主要用于Unix shell（例如，curl）. 可以作为Debian软件包构建，以便于安装. 麻省理工学院
- [transfer.sh](https://transfer.sh)  -从命令行轻松共享文件.  （[Source Code](https://github.com/dutchcoders/transfer.sh)）`MIT`` Go`

#### Web based file managers

- [Apaxy](https://oupala.github.io/apaxy/)  -使用mod_autoindex Apache模块和一些CSS来覆盖目录列表的默认样式，以增强浏览网页目录的体验.  （[Source Code](https://github.com/AdamWhitcroft/Apaxy)）`Unlicense``HTML`
- [DirectoryLister](http://www.directorylister.com/)  -基于PHP的简单目录列表器，列出了目录及其所有子目录，并允许您在其中进行导航.  （[Source Code](https://github.com/DirectoryLister/DirectoryLister)）和PHP`
- [Encode Explorer](http://encode-explorer.siineiolekala.net/)  -Encode Explorer是一个单页文件浏览器，它既简单又功能强大.  （[Demo](http://encode-explorer.siineiolekala.net/explorer/index.php), [Source Code](https://github.com/marekrei/encode-explorer)）和PHP`
- [explorer](https://soyuka.github.io/explorer/)  -使用nodejs创建的高度可配置的目录列表.  （[Source Code](https://github.com/soyuka/explorer)）`与`Node.js`
- [filebrowser](https://filebrowser.org/)  -具有Material Design Web界面的Web文件浏览器.  （[Source Code](https://github.com/filebrowser/filebrowser)）`Apache-2.0``Go`
- [FileGator](https://filegator.io/)  -FileGator是功能强大的多用户文件管理器，具有单页前端.  （[Demo](https://demo.filegator.io), [Source Code](https://github.com/filegator/filegator)）和PHP`
- [Filestash](https://www.filestash.app/)  -一个网络文件管理器，可让您在任何位置管理数据：FTP，SFTP，WebDAV，Git，S3，Minio，Dropbox或Google云端硬盘.  （[Demo](https://demo.filestash.app/), [Source Code](https://github.com/mickael-kerjean/filestash)）`AGPL-3.0``Go`
- [goBrowser](https://github.com/xataz/gobrowser)  -简单的http文件浏览器.  GPL-3.0`Go`
- [Gossa](https://github.com/pldubouilh/gossa)  -Gossa是您文件的轻便简单的Web服务器. 麻省理工学院
- [h5ai](https://larsjung.de/h5ai/)  -适用于HTTP Web服务器的现代文件索引器，重点放在您的文件上. 目录以吸引人的方式显示，并且通过不同的视图，面包屑和树概述增强了浏览目录的能力.  （[Demo](https://larsjung.de/h5ai/demo/), [Source Code](https://github.com/lrsjng/h5ai)）和PHP`
- [IFM](https://github.com/misterunknown/ifm)  -单个脚本文件管理器. 麻省理工学院PHP
- [ResourceSpace](https://www.resourcespace.com)  -ResourceSpace开源数字资产管理软件是组织数字资产的简单，快速和免费的方式.  （[Demo](https://www.resourcespace.com/trial), [Source Code](https://www.resourcespace.com/svn)）`其他``PHP`
- [s3server](https://github.com/jessfraz/s3server)  -简单的HTTP界面，用于索引和浏览公共S3或Google Cloud Storage存储桶中的文件. 麻省理工学院
- [Surfer](https://github.com/nebulade/surfer)  -带有webui的简单静态文件服务器，用于管理文件.  MIT`Nodejs`
- [TagSpaces](https://www.tagspaces.org/)  -TagSpaces是一个脱机的跨平台文件管理器和组织器，还可以用作笔记应用程序. 该应用程序的WebDAV版本可以安装在诸如Nextcloud或ownCloud之类的WebDAV服务器之上.  （[Demo](http://demo.tagspaces.org), [Source Code](https://github.com/tagspaces/tagspaces)）`AGPL-3.0``Javascript`

## Games

**[`^        back to top        ^`](#)**

_游戏，游戏服务器和控制面板.

- [A Dark Room](https://github.com/doublespeakgames/adarkroom)  -极简主义的文字冒险游戏，适合您的浏览器.  （[Demo](http://adarkroom.doublespeakgames.com/)）`MPL-2.0``HTML5`
- [Agar.IO Clone](https://github.com/huytd/agar.io-clone)  -用Socket.IO和HTML5画布编写的Agar.io克隆.  MIT`Nodejs`
- [battlecraft](https://github.com/jbreindel/battlecraft)  -完全分布式的多人浏览器游戏.  `Apache-2.0``Erlang`
- [elevatorsaga](http://play.elevatorsaga.com/)  -电梯编程游戏.  （[Source Code](https://github.com/magwo/elevatorsaga)）和Javascript
- [Hextris](https://github.com/Hextris/hextris)  -受俄罗斯方块启发的快节奏HTML5益智游戏.  （[Demo](https://hextris.github.io/hextris)）`GPL-3.0`` HTML5`
- [Legend of the Green Dragon](https://github.com/lotgd/core)  -《绿龙传奇》是一款基于文本的RPG，最初由Eric Stevens和JT Traub开发，是对Seth Able Robinson的经典BBS Door游戏《红龙传奇》的翻版和致敬.  （[Demo](http://lotgd.net/)）`AGPL-3.0``PHP`
- [Lila](https://lichess.org/)  -永久免费，无广告和开源国际象棋服务器，为lichess.org提供支持，并带有官方的iOS和Android客户端应用程序.  （[Source Code](https://github.com/ornicar/lila)）`AGPL-3.0`` Scala`
- [Mindustry](https://mindustrygame.github.io/)  -类似于Factorio的塔防游戏. 建立生产链以收集更多资源，并建立复杂的设施.  （[Source Code](https://github.com/Anuken/Mindustry)）`GPL-3.0`` Java`
- [Minetest](https://www.minetest.net/)  -开源体素游戏引擎. 玩我们的许多游戏之一，根据自己的喜好修改游戏，制作自己的游戏，或在多人服务器上玩.  （[Source Code](https://github.com/minetest/minetest)）`LGPL-2.1 / CC-BY-SA-3.0 / Other``C ++`
- [Net64+](https://net64-mod.github.io)  ⚠-Net64（又名SM64O）允许在在线多人游戏模式下玩Super Mario 64.  Net64 +是该程序的正式延续，并具有集成的服务器列表.  （[Source Code](https://github.com/Tarnadas/net64plus-server/), [Clients](https://github.com/Tarnadas/net64plus/)）`与`Node.js`
- [node-virtual-gamepads](https://github.com/jehervy/node-virtual-gamepads)  -将您的智能手机变成远程Linux OS计算机的游戏控制器，键盘或触摸板.  MIT节点Nodejs / CoffeScript
- [Posio](https://github.com/abrenaut/posio)  -地理多人游戏. 麻省理工学院Python
- [piqueserver](https://github.com/piqueserver/piqueserver)  -openpades服务器，可破坏体素世界中的第一人称射击游戏.  （[Clients](https://github.com/yvt/openspades)）`GPL-3.0`` Python / C ++`
- [QuakeJS](https://github.com/begleysm/quakejs)  -QuakeJS是ioquake3到JavaScript的移植，可以在浏览器中播放.  MIT`Nodejs`
- [Quizmaster](https://github.com/nymanjens/quizmaster)  -进行测验的网络应用程序，包括供玩家输入答案的页面.  `Apache-2.0``Scala`
- [RconCli](https://github.com/gorcon/rcon-cli)  -CLI，用于使用RCON协议在远程Valve Source专用服务器上执行查询. 麻省理工学院
- [SourceBans++](https://sbpp.github.io)  -用于在Source引擎上运行的游戏的管理，禁令和通讯管理系统.  （[Source Code](https://github.com/sbpp/sourcebans-pp)）`CC-BY-SA-4.0``PHP`
- [Teeworlds](https://www.teeworlds.com)  -开源2D复古多人射击游戏.  （[Source Code](https://github.com/teeworlds/teeworlds)）`BSD-3-Clause / Other``C ++`
- [TournamentMango](https://github.com/seiyria/tournamentmango)  -TournamentMango是一个开放源代码的比赛框架和用户管理系统. 您可以建立玩家档案，并跟踪他们随时间推移的所有得分以及他们的常规角色，游戏和别名.  MIT Java语言
- [The Battle for Wesnoth](https://github.com/wesnoth/wesnoth) -韦诺之战是一款开放式的回合制战术策略游戏，具有很高的幻想主题，具有单人游戏和在线/多座位多人在线战斗的功能.

## Gateways and terminal sharing

**[`^        back to top        ^`](#)**

- [asciinema](https://github.com/asciinema/asciinema-server)  -用于托管助手的Web应用程序.  （[Demo](https://asciinema.org/)）`Apache-2.0``Elixir / Docker`
- [GateOne](http://liftoffsoftware.com/Products/GateOne)  -Gate One是一个基于HTML5的基于Web的终端仿真器和SSH客户端.  （[Source Code](https://github.com/liftoff/GateOne)）`AGPL-3.0``Python`
- [Guacamole](http://guac-dev.org/)  -鳄梨调味酱是无客户端远程桌面网关. 它支持标准协议，例如VNC和RDP.  （[Source Code](https://github.com/glyptodon/)）Apache-2.0`` Java / C`
- [Neko](https://github.com/nurdism/neko)  -在Docker中运行的自托管虚拟浏览器（rabb.it克隆）.  `Apache-2.0``Docker / Go`
- [oneye](https://oneye-project.org/)  -云软件可使用任何浏览器从任何地方访问您的数据.  （[Demo](https://wiki.oneye-project.org/0.9:demo), [Source Code](https://github.com/oneye/oneye)）`AGPL-3.0``PHP`
- [OS.js](https://www.os-js.org/)  -具有完善的窗口管理器，应用程序API，GUI工具包和文件系统抽象的浏览器桌面实现.  （[Demo](https://demo.os-js.org/), [Source Code](https://github.com/os-js/OS.js)）`BSD-2-Clause``Nodejs`
- [Sshwifty](https://github.com/nirui/sshwifty)  -Sshwifty是专为Web设计的SSH和Telnet连接器.  `AGPL-3.0``Go / Docker`
- [tmate](https://tmate.io/)  -即时终端共享.  （[Source Code](https://github.com/tmate-io/tmate)）`ISC``C`

## Groupware

**[`^        back to top        ^`](#)**

- [BlueMind](https://www.bluemind.net/en/)  -具有电子邮件，日历，地址簿的组件，交换活动同步，交换“ mapi”协议支持.  （[Source Code](https://forge.bluemind.net/stash/projects/BM/repos/bluemind-public/browse)）`AGPL-3.0``Java`
- [Citadel](http://www.citadel.org/doku.php)  -组件软件，包括电子邮件，日历/计划，通讯录，论坛，邮件列表，IM，Wiki和博客引擎，RSS聚合等.  （[Source Code](http://www.citadel.org/doku.php/installation:source)）`GPL-3.0`` C`
- [Corteza](https://cortezaproject.org)  -CRM，包括统一的工作区，企业消息传递和低代码环境，用于快速安全地交付基于记录的管理解决方案.  （[Demo](https://latest.cortezaproject.org), [Source Code](https://github.com/cortezaproject/corteza-server)）`Apache-2.0``Go`
- [Cozy Cloud](https://cozy.io)  -个人云，您可以在其中管理和同步联系人，文件和日历，并通过充满社区贡献的应用商店来管理预算.  （[Source Code](https://github.com/cozy)）`GPL-3.0`` Nodejs`
- [egroupware](http://www.egroupware.org/)  -软件套件，包括日历，通讯录，记事本，项目管理工具，客户关系管理工具（CRM），知识管理工具，Wiki和CMS.  （[Source Code](https://github.com/EGroupware/egroupware)）`GPL-2.0``PHP`
- [EspoCRM](https://www.espocrm.com/)  -具有设计为单页应用程序的前端和REST API的CRM.  （[Demo](http://demo.espocrm.de/basic/), [Source Code](https://github.com/espocrm/espocrm)）`GPL-3.0``PHP`
- [Horde](http://www.horde.org/)  -Horde Project旨在基于PHP和Horde Framework创建高质量的开源应用程序和库.  （[Demo](http://demo.horde.org/login.php), [Source Code](https://github.com/horde/horde)）`GPL-2.0``PHP`
- [HRCloud2](https://github.com/zelon88/HRCloud2)  -功能齐全的家用托管云驱动器，个人助手，应用启动器，文件转换器，流媒体，共享工具等.  `GPL-3.0``PHP`
- [Kolab](https://kolab.org/)  -Kolab社区是一个统一的沟通和协作系统.  （[Source Code](https://git.kolab.org/)）`GPL-2.0 / LGPL-2.1 / GPL-3.0`` C ++ / Python / PHP`
- [Kopano](https://kopano.com/)  -组件套件，包括电子邮件，日历，任务，待办事项和便笺. 具有现代的WebApp，DeskApp和通过Z-Push / ActiveSync进行的移动访问.  （[Demo](http://demo.kopano.com), [Source Code](https://stash.kopano.io)）`AGPL-3.0``C / Python / PHP`
- [Openmeetings](https://openmeetings.apache.org/index.html)  -Openmeetings使用Red5 Streaming Server的API功能提供视频会议，即时消息传递，白板，协作文档编辑和其他组件工具，以进行远程处理和流传输.  （[Source Code](https://openmeetings.apache.org/scm.html)）Apache-2.0`` Java`
- [SOGo](https://sogo.nu/)  -SOGo提供了多种访问日历和消息传递数据的方式.  CalDAV，CardDAV，GroupDAV以及ActiveSync，包括本机Outlook兼容性和Web界面.  （[Demo](http://demo.sogo.nu/SOGo/), [Source Code](https://github.com/inverse-inc/sogo)）`LGPL-2.1``Objective-C`
- [SuiteCRM](http://www.suitecrm.com/)  -屡获殊荣的企业级开源CRM.  （[Source Code](https://github.com/salesagility/SuiteCRM)）`AGPL-3.0``PHP`
- [Tine 2.0](https://www.tine20.org)  -联系人，日历，任务，WebDAV，ActiveSync，VOIP，邮件客户端，CRM，销售，项目，Timetracker.  （[Demo](https://demo.tine20.net), [Source Code](https://packages.tine20.com/maintenance/source/)）`AGPL-3.0 / Other`PHP`
- [Zimbra Collaboration](https://www.zimbra.com/)  -电子邮件，日历，具有Web界面和大量集成功能的协作服务器.  （[Source Code](https://github.com/zimbra)）GPL-2.0 / CPAL-1.0` Java

## Human Resources Management (HRM)

**[`^        back to top        ^`](#)**

- [admidio](https://www.admidio.org/)  -Admidio是针对组织和团体网站的免费开源用户管理系统. 该系统具有灵活的角色模型，因此可以反映您组织的结构和权限.  （[Demo](https://www.admidio.org/demo/), [Source Code](https://github.com/Admidio/admidio)）`GPL-2.0``PHP`
- [IceHrm](https://icehrm.com/) - IceHrm employee management system allows companies to centralize confidential employee information. ([Demo](https://icehrm.com/demo.php), [Source Code](https://github.com/gamonoid/icehrm)）`Apache-2.0``PHP`
- [OrangeHRM](https://www.orangehrm.com/)  -OrangeHRM是一个全面的HRM系统，可捕获任何企业所需的所有基本功能.  （[Source Code](https://sourceforge.net/projects/orangehrm/)）`GPL-2.0``PHP`
- [Sentrifugo](http://www.sentrifugo.com/)  -Sentrifugo是一种HRM系统，可以轻松配置以满足您的组织需求.  （[Source Code](https://github.com/sapplica/sentrifugo)）`GPL-3.0``PHP`
- [TimeOff.Management](https://timeoff.management) - Simple yet powerful absence management software for small and medium size business. ([Demo](https://app.timeoff.management), [Source Code](https://github.com/timeoff-management/application)）`与`Node.js`

## Internet Of Things (IoT)

**[`^        back to top        ^`](#)**

- [DeviceHive](https://www.devicehive.com/)  -具有广泛集成选项的开源物联网平台.  （[Demo](https://playground.devicehive.com/), [Source Code](https://github.com/devicehive/devicehive-java-server)）Apache-2.0`` Java`
- [Domoticz](https://www.domoticz.com/)  -家庭自动化系统，可让您监视和配置各种设备，例如：灯，开关，各种传感器/仪表，例如温度，雨水，风，紫外线，伊莱克特拉，煤气，水等.  （[Source Code](https://github.com/domoticz/domoticz), [Clients](https://github.com/domoticz/domoticz-android)）`GPL-3.0`C / C ++`
- [FHEM](https://fhem.de/fhem.html)  -FHEM用于自动化家庭中的常见任务，例如开关灯和暖气. 它也可以用于记录温度或功耗等事件. 您可以通过Web或智能手机前端，telnet或TCP / IP直接对其进行控制.  （[Source Code](https://svn.fhem.de/trac)）`GPL-3.0`` Perl`
- [Gladys](https://gladysproject.com)  -Gladys是可在您的Raspberry Pi上运行的开源家庭助理.  （[Source Code](https://github.com/GladysProject/Gladys)）`与`Node.js`
- [Home Assistant](https://home-assistant.io/)  -开源家庭自动化平台.  （[Demo](https://home-assistant.io/demo/), [Source Code](https://github.com/home-assistant/home-assistant)）和Python
- [Node RED](http://nodered.org/)  -基于浏览器的流程编辑器，可帮助您连接硬件设备，API和在线服务以创建IoT解决方案.  （[Source Code](https://github.com/node-red/node-red)）`Apache-2.0`` Nodejs`
- [openHAB](http://www.openhab.org)  -面向家庭自动化的供应商和技术不可知的开源软件.  （[Demo](http://demo.openhab.org:8080/), [Source Code](https://github.com/openhab/openhab)）`EPL-2.0`` Java`
- [OpenRemote](https://openremote.io)  -100％开源IoT平台-IoT资产管理，流规则和时限规则，数据可视化，边缘网关.  （[Demo](https://demo.openremote.io/), [Source Code](https://github.com/openremote/openremote)）`AGPL-3.0``Java`
- [Thingsboard](https://thingsboard.io/)  -开源物联网平台-设备管理，数据收集，处理和可视化.  （[Demo](https://demo.thingsboard.io/signup), [Source Code](https://github.com/thingsboard/thingsboard)）Apache-2.0`` Java`
- [Thingspeak](https://thingspeak.com/)  -开源的“物联网”应用程序和API，可使用HTTP存储和检索来自物联网的数据.  （[Demo](https://thingspeak.com/channels/public), [Source Code](https://github.com/iobridge/thingspeak)）`GPL-3.0`` Ruby`
- [WebThings Gateway](https://webthings.io/gateway/)  -WebThings是物联网的开源实现，包括WebThings网关和WebThings框架.  （[Source Code](https://github.com/WebThingsIO/gateway)）`MPL-2.0``NodeJS`

## Knowledge Management Tools

**[`^        back to top        ^`](#)**

- [Mindmaps](https://github.com/drichard/mindmaps)  -开源，具有离线功能的思维导图应用程序.  （[Demo](http://drichard.org/mindmaps/)）AGPL-3.0 HTML5
- [My Mind](https://github.com/ondras/my-mind)  -用于创建和管理思维导图的Web应用程序.  （[Demo](https://my-mind.github.io/?url=examples%2Ffeatures.mymind)）和Javascript
- [Weaviate](https://github.com/semi-technologies/weaviate)  -原生云实时矢量搜索引擎，集成了可扩展的机器学习模型（GraphQL和RESTful API）.  （[Demo](https://www.semi.technology/documentation/weaviate/current/)）`BSD-3-Clause``Go`

## Learning and Courses

**[`^        back to top        ^`](#)**

- [Canvas LMS](https://www.canvaslms.com/)  -Canvas是值得信赖的开源学习管理系统（LMS），它正在彻底改变我们的教学方式.  （[Demo](https://canvas.instructure.com/register), [Source Code](https://github.com/instructure/canvas-lms)）`AGPL-3.0``Ruby`
- [Chamilo LMS](https://chamilo.org/)  -Chamilo LMS允许您创建虚拟校园，以提供在线或半在线培训.  （[Source Code](https://github.com/chamilo/chamilo-lms)）`GPL-3.0``PHP`
- [edX](https://www.edx.org/)  -Open edX平台是支持edX.org的开源代码.  （[Source Code](https://github.com/edx/)）`AGPL-3.0``Python`
- [ILIAS](http://www.ilias.de)  -ILIAS是学习管理系统，可以应付您遇到的任何问题.  （[Demo](http://demo.ilias.de), [Source Code](https://github.com/ILIAS-eLearning/ILIAS)）`GPL-3.0``PHP`
- [Mahara](https://mahara.org/)  -开源功能全面的Web应用程序，用于建立学生的电子档案袋.  （[Source Code](https://github.com/MaharaProject/mahara)）`GPL-3.0``PHP`
- [Moodle](https://moodle.org/)  -Moodle是一个学习和课程平台，拥有全球最大的开源社区之一.  （[Demo](https://moodle.org/demo/), [Source Code](https://git.moodle.org/gw)）`GPL-3.0``PHP`
- [Open eClass](http://www.openeclass.org/)  -Open eClass是一种高级的电子学习解决方案，可以增强教学过程.  （[Demo](http://demo.openeclass.org/), [Source Code](https://github.com/gunet/openeclass)）`GPL-2.0``PHP`
- [OpenOLAT](https://www.openolat.com/?lang=en)  -OpenOLAT是基于网络的学习管理系统，用于教学，教育，评估和交流.  （[Demo](https://learn.olat.com), [Source Code](https://github.com/OpenOLAT/OpenOLAT)）Apache-2.0`` Java`
- [RELATE](https://documen.tician.de/relate/)  -RELATE是一个基于Web的课件，包括以下功能：灵活的规则，统计信息，多课程支持，课程日历.  （[Source Code](https://github.com/inducer/relate)）和Python
- [RosarioSIS](https://www.rosariosis.org/)  -RosarioSIS，用于学校管理的免费学生信息系统.  （[Demo](https://www.rosariosis.org/demo/), [Source Code](https://gitlab.com/francoisjacquet/rosariosis/)）`GPL-2.0``PHP`
- [Sakai](https://www.sakaiproject.org/)  -酒井项目为教学，学习，研究和其他协作提供了灵活且功能丰富的环境.  （[Demo](https://www.sakaiproject.org/try-sakai), [Source Code](https://github.com/sakaiproject/sakai)）`ECL-2.0`` Java`

## Maps and Global Positioning System (GPS)

**[`^        back to top        ^`](#)**

_也可以看看 [awesome-gis](https://github.com/sshuair/awesome-gis)._

- [Geo2tz](https://github.com/noandrea/geo2tz)  -从地理坐标中获取时区（纬度，经度）. 麻省理工学院Go / Docker
- [GraphHopper](https://graphhopper.com/)  -使用OpenStreetMap的快速路由库和服务器.  （[Source Code](https://github.com/graphhopper/graphhopper)）Apache-2.0`` Java`
- [Hauk](https://github.com/bilde2910/Hauk)  -易于设置的位置共享平台，可让您与任何人实时临时共享位置.  （[Demo](https://github.com/bilde2910/Hauk#demo-server)）`Apache-2.0``PHP`
- [MapBBCodeShare](https://github.com/MapBBCode/share.mapbbcode.org)  -共享自定义OSM映射的工具. 支持带注释的标记，多边形，线，多种格式的导入/导出，多层，短链接.  （[Demo](http://share.mapbbcode.org/)）`WTFPL / Other``PHP`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/)  -高性能路由引擎，旨在在OpenStreetMap数据上运行，并提供HTTP API，C ++库接口和NodeJS包装器.  （[Demo](https://map.project-osrm.org/), [Source Code](https://github.com/Project-OSRM/osrm-backend)）`BSD-2-Clause``C ++`
- [Nominatim](https://nominatim.org/)  -用于对OpenStreetMap数据进行反向地址编码（地址-&gt;坐标）的服务器应用程序.  （[Source Code](https://github.com/openstreetmap/Nominatim)）`GPL-2.0``C`
- [OpenGTS](http://www.opengts.org/)  -入门级车队跟踪系统. 支持各种跟踪设备和协议. 带有丰富的Web界面和报告功能.  （[Demo](http://track.opengts.org/track/Track), [Source Code](https://sourceforge.net/projects/opengts/files/server-base/)）Apache-2.0`` Java`
- [OpenStreetMap](https://www.openstreetmap.org/)  -创建免费的可编辑世界地图的协作项目.  （[Source Code](https://github.com/openstreetmap/openstreetmap-website), [Clients](https://wiki.openstreetmap.org/wiki/Software)）`GPL-2.0`` Ruby`
- [OpenTripPlanner](https://www.opentripplanner.org/)  -基于OpenStreetMap数据并使用已发布的GTFS格式数据的多模式旅行计划软件，可使用本地公共交通系统建议路线.  （[Source Code](https://github.com/opentripplanner/OpenTripPlanner)）`LGPL-3.0``Java / JavaScript`
- [Orion](https://github.com/LINKIWI/orion-web)  -强大的OwnTracks API兼容网络位置数据可视化前端.  （[Demo](https://linkiwi.github.io/orion-web/)）`MIT`` Python / Nodejs`
- [OwnTracks Recorder](https://github.com/owntracks/recorder) ⚠-存储和访问发布者的数据 [OwnTracks](http://owntracks.org/) 位置跟踪应用.  `GPL-2.0`C` /`Lua`
- [TileServer GL](http://tileserver.readthedocs.io/)  -具有GL样式的矢量和栅格地图.  Mapbox GL Native提供的服务器端渲染. 适用于Mapbox GL JS，Android，iOS，Leaflet，OpenLayers，通过WMTS的GIS等的地图图块服务器（[Source Code](https://github.com/klokantech/tileserver-gl)）`BSD-2-Clause``Nodejs`
- [TileServer PHP](https://github.com/klokantech/tileserver-php)  -提供来自任何PHP托管的地图图块.  `BSD-2-Clause``PHP`
- [Traccar](https://www.traccar.org/)  -跟踪GPS位置的Java应用程序. 支持跟踪设备和协议的负载，并具有Android和iOS应用程序. 具有网络界面，可查看您的行程.  （[Demo](http://demo.traccar.org/), [Source Code](https://github.com/traccar)）Apache-2.0`` Java`
- [μlogger](https://github.com/bfabiszewski/ulogger-server)  -实时收集用户的地理位置，并在网站上显示其GPS轨迹.  （[Demo](http://ulogger.fabiszewski.net/)）`GPL-3.0``PHP`
- [uMap](https://umap.openstreetmap.fr/en/)  -一分钟内创建带有OpenStreetMap图层的地图，并将其嵌入到您的网站中.  （[Source Code](https://github.com/umap-project/umap)）`WTFPL``Python`

## Media Streaming

**[`^        back to top        ^`](#)**

 _也可以看看<https://en.wikipedia.org/wiki/List_of_streaming_media_systems> ，<https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems>  _

### Multimedia Streaming

- [Gerbera](https://gerbera.io/)  -非洲菊是UPnP媒体服务器. 它使您可以在整个家庭网络中流式传输数字媒体，并在各种UPnP兼容设备上收听/观看.  （[Source Code](https://github.com/gerbera/gerbera)）`GPL-2.0`` C ++`
- [homehost](https://github.com/ridhwaans/homehost)  ⚠-自托管的React + Redux应用程序，可流式传输您的媒体收藏（音乐，电影，书籍，播客，漫画等）.  MIT`Nodejs`
- [Icecast 2](http://www.icecast.org/)  -流音频/视频服务器，可用于创建Internet广播电台或私人运行的自动点唱机，介于两者之间.  （[Source Code](https://gitlab.xiph.org/xiph/icecast-server), [Clients](http://www.icecast.org/apps/)）`GPL-2.0``C`
- [Jellyfin](https://jellyfin.org)  -音频，视频，书籍，漫画和照片的媒体服务器，具有时尚的界面和强大的转码功能. 几乎所有现代平台都有客户，包括Roku，Android TV，iOS和Kodi.  （[Demo](https://demo.jellyfin.org/stable), [Source Code](https://github.com/jellyfin/jellyfin)) `GPL-2.0` `C#`
- [Karaoke Forever](https://www.karaoke-forever.com)  -举办很棒的卡拉OK派对，每个人都可以从手机的网络浏览器轻松找到歌曲并将其排队. 该播放器也是基于浏览器的，支持MP3 + G，MP4和WebGL可视化.  （[Source Code](https://www.karaoke-forever.com/repo)）ISC Nodejs
- [LBRY](https://lbry.com/)  -是一个安全，开放且由社区运营的数字市场，旨在取代Youtube和Amazon.  （[Demo](https://lbry.tv/), [Source Code](https://github.com/lbryio/lbry.com), [Clients](https://github.com/lbryio/lbry-desktop)）和PHP`
- [MistServer](http://mistserver.org/)  -在任何流环境中都能正常运行的流媒体服务器.  （[Source Code](https://github.com/DDVTECH/mistserver)）`AGPL-3.0``C ++`
- [NymphCast](http://nyanko.ws/nymphcast.php)  -NymphCast是Chromecast的替代产品，可将您选择的支持Linux的硬件转换为电视或有源扬声器的音频和视频源.  （[Source Code](https://github.com/MayaPosch/NymphCast)）`BSD-3-Clause``C ++`
- [Podify](https://www.podify.org/)  -允许您从youtube-dl支持的任何来源下载视频和音频，并使用自己喜欢的播客应用订阅和观看这些下载.  （[Source Code](https://github.com/podify-org/podify/)）`GPL-3.0`` Ruby`
- [ReadyMedia](http://sourceforge.net/projects/minidlna/)  -简单的媒体服务器软件，旨在完全兼容DLNA / UPnP-AV客户端. 前身为MiniDLNA.  （[Source Code](https://sourceforge.net/p/minidlna/git/ci/master/tree/)）`GPL-2.0``C`
- [Rygel](https://wiki.gnome.org/action/show/Projects/Rygel)  -Rygel是UPnP AV MediaServer，可让您轻松共享音频，视频和图片. 媒体播放器软件可以使用Rygel成为可由UPnP或DLNA控制器远程控制的MediaRenderer.  （[Source Code](https://gitlab.gnome.org/GNOME/rygel/)）`GPL-3.0`` C`
- [üWave](http://u-wave.net/)  `⚠`-üWave是一个自托管的协作收听平台. 用户轮流播放YouTube和SoundCloud等各种媒体来源的媒体（歌曲，演讲，游戏视频或其他内容）.  （[Demo](https://wlk.yt/), [Source Code](https://github.com/u-wave)）`与`Node.js`


### Audio Streaming

- [Ampache](http://ampache.org/)  -基于Web的音频/视频流应用程序.  （[Demo](http://play.dogmazic.net/), [Source Code](https://github.com/ampache/ampache)）`AGPL-3.0``PHP`
- [Airsonic](https://airsonic.github.io/)  -开源的基于Web的媒体流媒体和点唱机.  Subsonic上一个开源版本的一个分支，在它切换了许可证之前.  （[Source Code](https://github.com/airsonic/airsonic), [Clients](https://airsonic.github.io/docs/apps/)）`GPL-3.0`` Java`
- [AzuraCast](https://www.azuracast.com/)  -现代化且可访问的自托管网络广播管理套件.  （[Source Code](https://github.com/AzuraCast/AzuraCast)）`Apache-2.0``PHP`
- [Audioserve](https://github.com/izderadicka/audioserve)  -简单的个人服务器，可提供目录（有声读物，音乐，播客等）中的音频文件. 专注于简单性，并支持客户端之间的播放位置同步. 麻省理工学院
- [Beets](http://beets.io/)  -音乐库管理器和MusicBrainz标记器（命令行和Web界面）.  （[Source Code](https://github.com/beetbox/beets)）和Python
- [Black Candy](https://github.com/aidewoode/black_candy)  -使用Rails和Stimulus构建的音乐流服务器. 麻省理工学院Ruby
- [Compactd](https://github.com/compactd/compactd)  -支持添加内容的远程音乐播放器.  MIT`Nodejs`
- [FriendsRadio](https://github.com/xouabita/friends-radio)  `⚠`-与Youtube和Soundcloud的朋友分享音乐.  （[Demo](https://friends-radio.herokuapp.com/)）`与`Node.js`
- [Funkwhale](https://funkwhale.audio/)  -现代化的，基于Web的，欢乐的，多用户的和免费的音乐服务器.  （[Demo](https://demo.funkwhale.audio/), [Source Code](https://code.eliotberriot.com/funkwhale/funkwhale)）`BSD-3-Clause`` Python / Django`
- [GNU FM](https://gnu.io/fm/)  -运行音乐社区网站，替代last.fm.  （[Source Code](http://git.savannah.gnu.org/cgit/librefm.git/)）`AGPL-3.0``PHP`
- [gonic](https://github.com/sentriz/gonic)  -轻量级音乐流服务器. 亚音速兼容.  GPL-3.0`Go`
- [Groove Basin](https://github.com/andrewrk/groovebasin)  -音乐播放器服务器具有受Amarok 1.4启发的基于Web的用户界面.  MIT`Nodejs`
- [koel](http://koel.phanan.net/)  -有效的个人音乐流媒体服务器.  （[Source Code](https://github.com/phanan/koel)）和PHP`
- [KooZic](https://koozic.net/)  -具有强大的播放列表功能和Subsonic兼容性的音乐服务器.  （[Demo](https://demo.koozic.net/public), [Source Code](https://github.com/DocMarty84/koozic)）`LGPL-3.0 / MIT`` Python`
- [LibreTime](http://libretime.org) -简单，开放源代码的平台，可让您在网络上广播流媒体广播（ [Airtime](https://github.com/sourcefabric/Airtime)). ([Source Code](https://github.com/LibreTime/libretime)）`AGPL-3.0``PHP`
- [LMS](https://github.com/epoupon/lms)  -使用网络界面访问您的自托管音乐.  （[Demo](http://lms.demo.poupon.io/)）`GPL-3.0`` C ++`
- [moOde Audio](https://moodeaudio.org/)  -出色的Raspberry Pi单板计算机系列的发烧级质量音乐播放.  （[Source Code](https://github.com/moode-player/moode)）`GPL-3.0``PHP`
- [Mopidy](http://mopidy.readthedocs.org/)  -可扩展的音乐服务器. 提供mpd API的超集，并与Spotify，SoundCloud等第三方服务集成（[Source Code](https://github.com/mopidy/mopidy)）`Apache-2.0`` Python`
  - [Moped](https://github.com/martijnboland/moped)  -Mopidy音乐服务器的响应HTML5 + Javascript客户端.  MIT HTML5
  - [Mopidy MusicBox](https://github.com/pimusicbox/mopidy-musicbox-webclient)  -Mopidy音乐服务器的Web客户端.  `Apache-2.0``HTML5`
  - [Mopidy-Party](https://github.com/Lesterpig/mopidy-party)  -Mopidy Web扩展程序，专为聚会设计！ 让您的客人管理声音.  Apache-2.0 Python
- [mpd](http://www.musicpd.org/)  -守护程序，用于远程播放音乐，流音乐，处理和组织播放列表. 有许多可用的客户.  （[Source Code](https://github.com/MusicPlayerDaemon/MPD), [Clients](https://www.musicpd.org/clients/)）`GPL-2.0`` C ++`
  - [ympd](http://www.ympd.org/)  -利用Websockets和Bootstrap / JS用C编写的独立MPD Web GUI.  （[Source Code](https://github.com/notandy/ympd)）`GPL-2.0``C`
- [mStream](http://mstream.io/)  -具有GUI管理工具的音乐流服务器. 在Mac，Windows和Linux上运行.  （[Source Code](https://github.com/IrosTheBeggar/mStream)）`GPL-2.0`` Nodejs`
- [musikcube](https://musikcube.com/)  -具有Linux / macOS / Windows / Android客户端的流音频服务器.  （[Source Code](https://github.com/clangen/musikcube)）`BSD-3-Clause``C ++`
- [Navidrome Music Streamer](https://www.navidrome.org)  -现代音乐服务器和流媒体，与Subsonic / Airsonic兼容.  （[Demo](https://www.navidrome.org/demo), [Source Code](https://github.com/deluan/navidrome), [Clients](https://www.navidrome.org/docs/overview/#apps)）`GPL-3.0``Go / JavaScript`
- [Polaris](https://github.com/agersant/polaris)  -音乐浏览和流媒体应用程序已针对大型音乐收藏，易用性和高性能进行了优化. 麻省理工学院
- [Snapcast](https://github.com/badaix/snapcast)  -同步多房间音频服务器.  GPL-3.0 C ++
- [Sonerezh](https://www.sonerezh.bzh/)  -基于Web的自托管应用程序，可随时随地播放音乐.  （[Demo](https://www.sonerezh.bzh/demo/), [Source Code](https://github.com/sonerezh/sonerezh)）`GPL-3.0``PHP`
- [Stretto](https://github.com/benkaiser/stretto)  -具有Youtube / Soundcloud导入和iTunes / Spotify发现功能的音乐播放器.  （[Demo](https://next.kaiserapps.com), [Clients](https://github.com/benkaiser/stretto-mobile-next)）`与`Node.js`
- [Volumio](https://volumio.org/)  -一个免费的开源linux发行版，专门设计和微调以用于音乐播放.  （[Source Code](https://github.com/volumio/Volumio2)）`GPL-3.0`` NodeJS`

### Video Streaming

- [Bluecherry](https://www.bluecherrydvr.com/)  -支持IP和模拟摄像机的闭路电视（CCTV）软件应用程序.  （[Source Code](https://github.com/bluecherrydvr/bluecherry-apps)）`GPL-2.0``PHP`
- [crtmpserver](https://packages.debian.org/stable/crtmpserver)  -高性能RTMP / RTSP流服务器.  GPL-3.0 C ++
- [CyTube](https://github.com/calzoneman/sync)  -CyTube是一个Web应用程序，可为任意数量的频道提供媒体同步，聊天等功能.  （[Demo](http://cytu.be)）`与`Node.js`
- [Hellowlol HTPC Manager fork](https://github.com/Hellowlol/HTPC-Manager)  -全面响应的界面，可管理HTPC上所有您喜欢的媒体. 麻省理工学院Python
- [Invidious](https://github.com/omarroth/invidious/)  -`Invidious是YouTube的替代前端.  （[Demo](https://invidio.us/)）`AGPL-3.0``Crystal`
- [Kerberos.io](https://kerberos.io)  -Kerberos.io是一种视频监视解决方案，可与任何摄像机以及每台基于Linux的机器（Raspberry Pi，Docker，Kubernetes群集）一起使用.  （[Demo](https://demo.kerberos.io/), [Source Code](https://github.com/kerberos-io/kerberos-docker)）`MIT`` C ++`
- [Myflix](https://github.com/pastapojken/Myflix)  -自托管的超轻量级Netflix替代产品.  MIT贝壳
- [Oblecto](https://github.com/robinp7720/Oblecto)  `⚠`-具有响应性Vue.js前端的电影和电视节目的媒体服务器. 它具有强大的转码支持以及联合功能，可以与朋友共享您的库.  AGPL-3.0 NodeJS
- [Oddworks](https://gitlab.com/oddnetworks/oddworks/core)  -Oddworks是一个开放源代码视频分发平台，旨在通过Roku，Apple iOS / tvOS，Google Android和Amazon FireTV的SDK来消除流媒体电视的障碍.  MIT`Nodejs`
- [Open Streaming Platform](https://openstreamingplatform.com)  -Twitch和Youtube Live的自托管替代方案，用于实时和点播视频流.  （[Source Code](https://gitlab.com/Deamos/flask-nginx-rtmp-manager)）和Python
- [Olaris](https://gitlab.com/olaris/olaris-server)  -Olaris是开源，社区驱动的媒体管理器和转码服务器.  GPL-3.0`Go`
- [PeerTube](https://joinpeertube.org/en/)  -直接在网络浏览器中使用P2P（BitTorrent）的分散式视频流平台.  （[Source Code](https://github.com/Chocobozzz/PeerTube)）`AGPL-3.0`` Nodejs`
- [Rapidbay](https://github.com/hauxir/rapidbay/)  -自托管的洪流视频流服务/洪流客户端，允许从浏览器中的洪流或Chromecast / AppleTV / Smart TV中搜索和播放洪流视频. 麻省理工学院Python / Docker
- [Restreamer](https://datarhei.github.io/restreamer/)  -Restreamer允许您在没有流媒体提供商的情况下在网站上进行h.264实时视频流.  （[Source Code](https://github.com/datarhei/restreamer)）`Apache-2.0``Nodejs / Docker`
- [Radium](https://github.com/Zibbp/Radium)  -使用HLS的具有VOD功能的流和视频同步播放. 专为电影之夜而开发，但有许多用例.  （[Demo](https://radium-demo.herokuapp.com)）`MIT`` Nodejs / Docker`
- [ShinobiCE](https://gitlab.com/Shinobi-Systems/ShinobiCE)  -用Node编写的开源CCTV软件，同时支持IP和本地摄像机.  AGPL-3.0 / GPL-3.0 Node.js
- [Streama](https://github.com/streamaserver/streama)  -自托管的流媒体服务器.  MIT Java
- [SyncTube](https://github.com/RblSb/SyncTube)  -轻巧且易于设置的CyTube替代品，可以与朋友一起观看视频并进行聊天.  （[Demo](http://synctube-example.herokuapp.com/)）`与`Nodejs / Haxe`
- [Tube](https://prologic.github.io/tube)  -用Go语言编写的类似Youtube的视频（无需审查，无需任何功能！_），它还支持自动转码为MP4 H.265 AAC，多个集合和RSS feed.  （[Demo](https://tube.mills.io), [Source Code](https://github.com/prologic/tube)）`MIT`` Go`
- [VideoLAN Client (VLC)](https://www.videolan.org/)  -跨平台的多媒体播放器客户端和服务器，支持大多数多媒体文件以及DVD，音频CD，VCD和各种流协议.  （[Source Code](https://github.com/videolan/vlc)）`Multiple``C`
- [Zoneminder](https://www.zoneminder.com/)  -支持IP，USB和模拟摄像机的闭路电视（CCTV）软件应用程序.  （[Source Code](https://github.com/ZoneMinder/ZoneMinder)）`GPL-2.0``PHP`

## Misc/Other

**[`^        back to top        ^`](#)**

- [2FAuth](https://github.com/Bubka/2FAuth)  -一个Web应用程序，用于管理您的双重身份验证（2FA）帐户并生成其安全代码.  （[Demo](https://demo.2fauth.app/)）`AGPL-3.0``PHP`
- [411](https://github.com/etsy/411)  -警报管理Web应用程序. 麻省理工学院PHP
- [AlertHub](https://github.com/Ardakilic/alerthub)  `⚠`-AlertHub是一个简单的工具，可以从GitHub版本中获得警报.  MIT`Nodejs`
- [Anchr](https://anchr.io)  -Anchr是一个工具箱，用于处理Internet上的微小任务，包括书签集合，URL缩短和（加密的）图像上传.  （[Source Code](https://github.com/n1try/anchr)）`GPL-3.0`` Nodejs`
- [Anuko](https://www.anuko.com/time_tracker/index.htm)  -Anuko在自托管的基础上提供了简单的时间和项目跟踪.  （[Demo](https://timetracker.anuko.com/), [Source Code](https://github.com/anuko/timetracker)）`其他``PHP`
- [asciiflow](http://asciiflow.com/)  -流程图绘制工具.  （[Source Code](https://github.com/lewish/asciiflow2)）`GPL-3.0``Java / JavaScript`
- [blynk](https://blynk.io/)  -具有iOS和Android应用程序的平台，可通过Internet控制Arduino，ESP8266，Raspberry Pi和类似的微控制器板.  （[Source Code](https://github.com/blynkkk/blynk-server)）`AGPL-3.0``Java`
- [Cachet](https://cachethq.io/)  -面向所有人的开源状态页面系统.  （[Demo](https://demo.cachethq.io/), [Source Code](https://github.com/CachetHQ/Cachet)）`BSD-3-Clause``PHP`
- [CapRover](https://caprover.com/)  -在几分钟内构建自己的PaaS.  （[Demo](https://captain.server.demo.caprover.com/#/login), [Source Code](https://github.com/caprover/caprover)）`Apache-2.0``Docker / Nodejs`
- [changedetection.io](https://github.com/dgtlmoon/changedetection.io)  -自托管工具，可随时了解网站内容的变化.  Apache-2.0 Python / Docker
- [cState](https://github.com/cstate/cstate/)  -超快速雨果的静态状态页面. 简洁的设计，最少的JS，超轻便的HTML / CSS，高度自定义，可选的管理面板，只读API，IE8 +. 最好与Netlify，Docker一起使用.  （[Demo](https://cstate.mnts.lt/)）`MIT`` Go`
- [CUPS](https://www.cups.org/)  -通用Unix打印系统使用Internet打印协议（IPP）来支持到本地和网络打印机的打印.  （[Source Code](https://github.com/apple/cups)）`GPL-2.0``C`
- [CyberChef](https://github.com/gchq/CyberChef)  -在网络浏览器中执行各种方式的“网络”操作，例如AES，DES和Blowfish加密和解密，创建十六进制转储，计算哈希等等.  （[Demo](https://gchq.github.io/CyberChef)）`Apache-2.0``JavaScript`
- [DailyTxT](https://github.com/PhiTux/DailyTxT) - Encrypted Diary Web-App to save your personal memories of each day. Includes a search-function and encrypted file-upload. `MIT` `Python`
- [Digital-Currency](https://github.com/Icesofty/Digital-Currency)  -创建自己的自托管数字货币.  （[Demo](https://tonken.glitch.me/)）`GPL-3.0`` Nodejs`
- [DomainMOD](https://domainmod.org)  -在中央位置管理您的域和其他Internet资产的应用程序.  DomainMOD包含一个数据仓库框架，该框架允许您导入WHM / cPanel Web服务器数据，以便您可以查看，导出和报告数据.  （[Demo](https://demo.domainmod.org), [Source Code](https://github.com/domainmod/domainmod)）`GPL-3.0``PHP`
- [Flox](https://github.com/devfake/flox)  `⚠`-具有三分评级系统的自托管电影，电视连续剧和动漫观看列表. 使用电影数据库后端获取信息.  （[Demo](https://flox-demo.pyxl.dev/)）和PHP`
- [formspree](https://formspree.io/)  `⚠`-只需将您的表格发送到我们的URL，我们会将其转发到您的电子邮件中. 无需PHP，Javascript或注册.  （[Demo](http://test.formspree.io/), [Source Code](https://github.com/formspree/formspree)）`AGPL-3.0``Python`
- [GeneWeb](https://geneweb.tuxfamily.org/wiki/GeneWeb)  -GeneWeb是用OCaml编写的开源家谱软件. 它带有Web界面，可以脱机使用或用作Web服务.  （[Demo](https://demo.geneweb.tuxfamily.org/gw7/), [Source Code](https://github.com/geneweb/geneweb)）`GPL-2.0``OCAML`
- [graph-vl](https://github.com/verifid/graph-vl)  -使用机器学习和GraphQL进行身份证明文件验证. 麻省理工学院Python
- [How Secure Is My Password](https://github.com/howsecureismypassword/hsimp)  -我的密码有多安全，而不仅仅是说密码是“弱”或“强”？ 让您的用户知道某人需要多长时间才能破解他们的密码.  （[Demo](https://howsecureismypassword.net/)）和Javascript
- [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper)  `⚠`-轻松自托管Google字体的方法. 获取eot，ttf，svg，woff和woff2文件以及CSS代码段.  （[Demo](https://google-webfonts-helper.herokuapp.com/)）`与`Node.js`
- [ytdl-webserver](https://github.com/Algram/ytdl-webserver)  -支持Docker的网络服务器，用于下载youtube视频.  MIT`Nodejs`
- [Journal](https://github.com/inoda/journal)  -具有加密条目和共享功能的简单日记. 麻省理工学院Ruby
- [Kimai](https://www.kimai.org/)  -Kimai是免费的开源时间跟踪器. 它跟踪工作时间并按需打印出您的活动摘要.  （[Demo](https://www.kimai.org/demo/), [Source Code](https://github.com/kevinpapst/kimai2/)）和PHP`
- [King Phisher](https://github.com/securestate/king-phisher)  -Phisher国王是通过模拟真实的网络钓鱼攻击来测试和增强用户意识的工具.  BSD-3-Clause Python
- [MailyGo](https://codeberg.org/jlelse/MailyGo)  -MailyGo是一个用Go语言编写的小型工具，它可以通过电子邮件发送HTML表单，例如从没有动态后端的静态网站发送HTML表单. 麻省理工学院
- [MalwareMultiScan](https://github.com/mindcollapse/MalwareMultiScan)  -自托管VirusTotal，用于扫描在Docker中运行的具有多种防病毒功能的文件.  （[Demo](http://199.247.24.56:8888/)) `MIT` `C#`
- [MindsDB](https://github.com/mindsdb/mindsdb)  -MindsDB是现有数据库的开源自托管AI层，使您可以使用标准查询轻松地开发，训练和部署最新的机器学习模型.  GPL-3.0 Python
- [MissionKontrol](https://www.missionkontrol.io)  -可配置的管理面板，允许非技术用户访问MySQL / PostGRES数据库上的CRUD数据.  （[Source Code](https://github.com/Mission-Kontrol/MissionKontrol-rails)）`AGPL-3.0``Ruby`
- [Monica](https://monicahq.com/)  -个人关系经理和一种新型的CRM，用于组织与您的朋友和家人的互动.  （[Source Code](https://github.com/monicahq/monica)）`AGPL-3.0``PHP`
- [Musical Artifacts](https://musical-artifacts.com/)  -帮助分类，保存和释放制作音乐所需的文物.  （[Source Code](https://github.com/lfzawacki/musical-artifacts)）`MIT`` Ruby`
- [nnmm](https://github.com/Mechazawa/nnmm)  -超级微型pastebin / url缩小程序“微服务”.  `Beerware``PHP`
- [Notica](https://notica.us)  -可让您将浏览器通知从终端发送到台式机或手机. 无需安装或注册.  （[Source Code](https://github.com/tannercollin/Notica)）`与`Node.js`
- [Ombi](https://ombi.io/)  -用于Plex / Emby的内容请求系统，通过不断增长的功能集连接到SickRage，CouchPotato，Sonarr.  （[Demo](https://app.ombi.io/), [Source Code](https://github.com/tidusjar/Ombi)) `GPL-2.0` `C#`
- [oTranscribe](https://github.com/oTranscribe/oTranscribe)  -免费的网络应用程序，可消除抄录采访记录的痛苦.  （[Demo](https://otranscribe.com/)）`与JavaScript`
- [PassCheck](https://apacketofsweets.github.io/PassCheck/)  -具有某些方便的密码工具的Web应用程序，其中包括密码生成器，强度检查器和HaveIBeenPwned违规检查器.  （[Source Code](https://github.com/apacketofsweets/PassCheck)）`与JavaScript`
- [Reactive Resume](http://rxresu.me/)  -独一无二的简历构建器，牢记您的隐私. 完全安全，可定制，可移植，开源且永久免费.  （[Demo](https://rxresu.me/app/dashboard/), [Source Code](https://github.com/AmruthPillai/Reactive-Resume)）`MIT`` Docker / Nodejs`
- [ReleaseBell](https://releasebell.com/)  -发送已加星标的Github仓库的发布通知.  （[Source Code](https://git.cloudron.io/cloudron/releasebell)）`与`Node.js`
- [revealjs](https://revealjs.com)  -使用HTML轻松创建漂亮的演示文稿的框架.  （[Demo](https://revealjs.com/), [Source Code](https://github.com/hakimel/reveal.js)）`与JavaScript`
- [Revive Adserver](https://www.revive-adserver.com/)  -世界上最受欢迎的免费开源广告投放系统. 前身为OpenX Adserver和phpAdsNew.  （[Source Code](https://github.com/revive-adserver/revive-adserver)）`GPL-2.0或更高版本``PHP`
- [SANE Network Scanning](http://sane-project.org/)  -允许远程客户端访问本地主机上可用的图像采集设备（扫描仪）.  （[Source Code](http://www.sane-project.org/cvs.html)）`GPL-2.0``C`
- [TeslaMate](https://github.com/adriankumpf/teslamate)  -特斯拉汽车的功能强大的数据记录器. 麻省理工学院的长生不老药
- [Trello Burndown](https://github.com/swordbeta/trello-burndown)  ⚠-Trello板易于使用的SCRUM燃尽图. 麻省理工学院Go / Docker
- [ViMbAdmin](http://www.vimbadmin.net/)  -提供基于Web的虚拟邮箱管理系统，使邮件管理员可以轻松管理域，邮箱和别名.  （[Demo](http://www.vimbadmin.net/demo/auth/login), [Source Code](https://github.com/opensolutions/ViMbAdmin)）`GPL-3.0``PHP`
- [Web fonts repository](https://github.com/Finesse/web-fonts-repository)  -简单的webfont托管.  Google字体替代您自己的字体. 麻省理工学院PHP
- [webtrees](https://www.webtrees.net)  -Webtrees是Web上领先的在线协作家谱应用程序.  （[Demo](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [Source Code](https://github.com/fisharebest/webtrees)）`GPL-3.0``PHP`

## Money, Budgeting and Management

**[`^        back to top        ^`](#)**

_See also https://github.com/n1trux/awesome-sysadmin#it-asset-management_

- [Akaunting](https://akaunting.com/)  -Akaunting是专为小型企业和自由职业者设计的免费，在线和开源会计软件.  （[Source Code](https://github.com/akaunting/akaunting)）`GPL-3.0``PHP`
- [BTCPay Server](https://btcpayserver.org/)  -自托管的比特币和其他加密货币支付处理器.  （[Demo](https://mainnet.demo.btcpayserver.org/), [Source Code](https://github.com/btcpayserver/)) `MIT` `C#`
- [Boodle](https://github.com/manuel-uberti/boodle)  -Clojure和ClojureScript中的简单会计单页应用程序.  `EPL-1.0``Java`
- [Budget App](https://github.com/paukiatwee/budgetapp)  -Budget App是一个开源的个人预算应用程序.  Apache-2.0 Java
- [Dot Ledger](https://www.dotledger.com/)  -基于Web的个人理财管理工具.  （[Demo](https://demo.dotledger.com/), [Source Code](https://github.com/dotledger/dotledger)）`Apache-2.0`Ruby`
- [Economizzer](http://www.economizzer.org/)  -一个简单安全的系统，可让您管理您的个人资金并实现目标，并且可以通过计算机，平板电脑或智能手机进行访问.  （[Demo](https://github.com/gugoan/economizzer#live-demo), [Source Code](https://github.com/gugoan/economizzer)）和PHP`
- [ExMoney](https://github.com/gaynetdinov/ex_money)  -自托管的个人理财应用程序.  `ISC``长生不老药`
- [Firefly III](https://firefly-iii.org/)  -Firefly III是一位现代财务经理. 它可以帮助您跟踪资金状况并进行预算预测. 它支持信用卡，具有高级规则引擎，并且可以从许多银行导入数据.  （[Demo](https://demo.firefly-iii.org/), [Source Code](https://github.com/firefly-iii/firefly-iii)）`AGPL-3.0``PHP`
- [Family Accounting Tool](https://github.com/nymanjens/facto)  -基于Web的财务管理工具，用于合作伙伴承担部分费用.  `Apache-2.0``Scala`
- [Fava](https://beancount.github.io/fava/)  -Fava是Beancount的Web前端，Beancount是基于文本的重复输入记帐系统.  （[Demo](https://fava.pythonanywhere.com/example-with-budgets/income_statement/), [Source Code](https://github.com/beancount/fava)）和Python
- [Galette](http://galette.eu/dc/)  -Galette是面向非营利组织的会员管理Web应用程序.  （[Source Code](http://git.tuxfamily.org/galette/galette.git/)）`GPL-3.0``PHP`
- [GRR](http://grr.devome.com/?lang=en)  -中小型公司的资产管理和预订.  （[Source Code](https://github.com/JeromeDevome/GRR)）`GPL-2.0``PHP`
- [Hospital Run](http://hospitalrun.io/)  -Hospital Run是脱机启用的医院管理软件.  （[Demo](http://hospitalrun.io/demo/), [Source Code](https://github.com/HospitalRun/hospitalrun-server)）`GPL-3.0`` Nodejs`
- [Inventaire](https://inventaire.io/welcome)  -协作资源映射器项目，而仅专注于探索使用Wikidata和ISBN进行图书映射.  （[Source Code](https://github.com/inventaire/inventaire)）`AGPL-3.0`` Nodejs`
- [Inventree](https://inventree.readthedocs.io/en/latest/)  -InvenTree是一个开放源代码的库存管理系统，可提供直观的零件管理和库存控制.  （[Source Code](https://github.com/inventree/InvenTree)）和Python
- [Invoice Ninja](https://www.invoiceninja.org/)  -强大的工具，可在线为客户开具发票.  （[Demo](https://app.invoiceninja.com/invoices/create), [Source Code](https://github.com/invoiceninja/invoiceninja)）`AAL`` PHP`
- [InvoicePlane](https://github.com/InvoicePlane/InvoicePlane)  -管理小型企业的报价，发票，付款和客户. 麻省理工学院PHP
- [IHateMoney](http://ihatemoney.org/)  -轻松管理您的共享费用.  （[Demo](https://ihatemoney.org/demo/), [Source Code](https://github.com/spiral-project/ihatemoney)）`BSD-3-Clause`` Python`
- [IHateToBudget](https://github.com/bminusl/ihatetobudget)  -一个简单的Web应用程序，用于了解和控制您的费用.  `GPL-3.0``Docker / Python`
- [Kresus](https://kresus.org/)  -开源个人理财经理.  （[Demo](https://kresus.org/en/demo.html), [Source Code](https://github.com/kresusapp/kresus)）`与`Node.js`
- [OnTrack](https://github.com/inoda/ontrack)  -一个简单的应用程序，用于跟踪支出和设定目标.  MIT Ruby /反应
- [PartKeepr](https://www.partkeepr.org)  -PartKeepr是电子零件库存管理软件. 它可以帮助您跟踪可用零件并协助您重新订购零件.  （[Demo](https://demo.partkeepr.org/), [Source Code](https://github.com/partkeepr/PartKeepr)）`GPL-3.0``PHP`
- [SilverStrike](https://silverstrike.org/)  -个人理财管理变得容易.  （[Demo](https://demo.silverstrike.org/), [Source Code](https://github.com/agstrike/silverstrike)）`MIT`` Python / Django`
- [StockazNG](https://dev.sigpipe.me/dashie/StockazNG)  -资产管理系统. 有Python
- [Tabby](https://github.com/bertvandepoel/tabby)  -一种管理朋友之间共同费用的工具，例如餐厅费用或外卖食品，而无需每个人都创建一个帐户. 包括电子邮件提醒和跟踪谁（重新）偿还了什么. 仅适用于AGPL-3.0的PHP

## Monitoring

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#monitoring and https://github.com/n1trux/awesome-sysadmin#metric--metric-collection_

## Note-taking and Editors

**[`^        back to top        ^`](#)**

_也可以看看 [Wikis](#wikis)_

- [BulletNotes](https://bulletnotes.io/)  -具有看板（Trello）和日历功能的Workflowy / Dynalist克隆. 整理一切.  （[Source Code](https://gitlab.com/NickBusey/BulletNotes)）`与`Node.js`
- [Boostnote](https://boostnote.io/)  -面向记笔记的应用程序，专注于降价，摘要和可定制性.  （[Source Code](https://github.com/BoostIO/Boostnote)）`GPL-3.0``JavaScript`
- [DailyNotes](https://github.com/m0ngr31/DailyNotes/)  -该应用程序每天在Markdown中记录笔记和跟踪任务. 麻省理工学院Python
- [dillinger](http://dillinger.io/)  -最后的Markdown编辑器.  （[Source Code](https://github.com/joemccann/dillinger)）`与`Node.js`
- [Dnote](https://www.getdnote.com)  -具有多设备同步和Web界面的简单命令行笔记本.  （[Source Code](https://github.com/dnote/dnote)）`AGPL-3.0``Go`
- [DocPHT](https://docpht.org/)  -使用DocPHT，您可以做笔记并快速记录所有内容，而无需使用任何数据库.  （[Demo](https://demo.docpht.org/), [Source Code](https://github.com/kenlog/docpht)）和PHP`
- [draw.io](https://draw.io)  -用于制作流程图，流程图，组织图，UML，ER和网络图的图表软件.  （[Source Code](https://github.com/jgraph/drawio)）`Apache-2.0``JavaScript`
- [HedgeDoc](https://demo.hedgedoc.org/)  -在所有平台上的实时协作降价注释，以前称为CodiMD和HackMD CE.  （[Source Code](https://github.com/hedgedoc/hedgedoc)）`AGPL-3.0``TypeScript`
- [Joplin](https://joplinapp.org/)  -Joplin是一个记笔记应用程序，具有Markdown编辑器以及对移动和桌面平台的加密支持. 运行客户端并通过自托管的Nextcloud或类似服务器进行同步. 将其视为Evernote的开源替代方案.  （[Source Code](https://github.com/laurent22/joplin)）`与`Node.js`
- [Leanote](http://leanote.org/)  -Leanote，而不仅仅是记事本！ 开源云记事本.  （[Demo](https://leanote.com/note), [Source Code](https://github.com/leanote/leanote)）`GPL-2.0``Go`
- [Markdown Edit](http://georgeosddev.github.com/markdown-edit/)  -在线降价编辑器/查看器.  （[Source Code](https://github.com/georgeOsdDev/markdown-edit)）`MIT`` HTML5`
- [Meemo](https://meemo.minimal-space.de/)  -带有Markdown支持的个人笔记流.  （[Source Code](https://github.com/nebulade/meemo)）`与`Node.js`
- [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - Minimalist notepad.cc clone. ([Demo](https://notes.orga.cat/)）`Apache-2.0``PHP`
- [MiniNote](https://github.com/n1try/mininote)  -具有持久性的简单Markdown笔记应用程序.  MIT`Nodejs`
- [Oddmuse](https://oddmuse.org/)  -用Perl编写的简单Wiki引擎. 无需数据库.  （[Source Code](https://github.com/kensanata/oddmuse)）`GPL-3.0`` Perl`
- [OpenNote](https://github.com/FoxUSA/OpenNote)  -OpenNote构建为Microsoft OneNote（T）和EverNote的基于Web的开放式替代方案.  （[Demo](https://foxusa.github.io/OpenNote/OpenNote/#/folder)）`MIT`` HTML5`
- [Overleaf](https://www.overleaf.com/)  -基于Web的协作LaTeX编辑器.  （[Source Code](https://github.com/overleaf/overleaf)）`AGPL-3.0``Ruby`
- [Paperwork](https://paperwork.cloud)  -Evernote，Microsoft OneNote和Google Keep的OpenSource笔记和存档替代品.  （[Source Code](https://github.com/paperwork/paperwork)）和PHP`
- [Plainpad](https://alextselegidis.com/get/plainpad/)  -利用渐进式Web应用程序技术的最佳功能，针对云计算的现代笔记应用程序.  （[Demo](https://alextselegidis.com/try/plainpad/), [Source Code](https://github.com/alextselegidis/plainpad)）`GPL-3.0``PHP`
- [savepad](https://github.com/shelltr/textpad)  -基于notepad.cc的简约记事本. 麻省理工学院PHP
- [Standard Notes](https://standardnotes.org)  -简单和私人笔记应用程序. 在完成更多工作的同时保护您的隐私. 这是标准注释.  （[Demo](https://app.standardnotes.org/), [Source Code](https://github.com/standardnotes)）`GPL-3.0`` Ruby`
- [turndown](https://domchristie.github.io/turndown/)  -用JavaScript编写的HTML至Markdown转换器.  （[Source Code](https://github.com/domchristie/turndown)）和Javascript
- [Trilium Notes](https://github.com/zadam/trilium)  -Trilium Notes是一种分层注释应用程序，专注于建立大型个人知识库.  AGPL-3.0 NodeJS
- [Turtl](https://turtl.it/)  -完全私人的个人数据库和笔记应用程序.  （[Source Code](https://github.com/turtl)）``3.0` GPL CommonLisp`
- [Wreeto](https://wreeto.com)  -Wreeto是建立在Ruby on Rails框架之上的开源笔记，知识管理和Wiki系统.  （[Source Code](https://github.com/chrisvel/wreeto_official)）`AGPL-3.0``Ruby`
- [Writing](https://josephernest.github.io/writing/)  -浏览器中的轻量级无干扰文本编辑器（支持Markdown和LaTeX）. 写作时没有滞后.  （[Source Code](https://github.com/josephernest/writing)）和Javascript

## Office Suites

**[`^        back to top        ^`](#)**

- [ Collabora Online Development Edition](https://www.collaboraoffice.com/code)  -Collabora在线开发版（CODE）是基于LibreOffice的强大在线办公室，支持所有主要文档，电子表格和演示文稿文件格式，您可以将其集成到自己的基础架构中.  （[Source Code](https://cgit.freedesktop.org/libreoffice/online/)）`MPL-2.0``C ++`
- [CryptPad](https://cryptpad.fr/)  -CryptPad是零知识实时协作编辑器（RTF，文本，文件，源代码等）.  （[Source Code](https://github.com/xwiki-labs/cryptpad)）`AGPL-3.0`` Nodejs`
- [EtherCalc](https://ethercalc.net/)  -网络电子表格.  （[Source Code](https://github.com/audreyt/ethercalc)）CPAL-1.0 / Other` Nodejs
- [Etherpad](http://etherpad.org/)  -Etherpad是高度可定制的开源在线编辑器，可提供实时的协作编辑.  （[Demo](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [Source Code](https://github.com/ether/etherpad-lite)）`Apache-2.0`` Nodejs`
- [Infinoted](https://github.com/gobby/gobby/wiki/Dedicated%20Server) -服务器 [Gobby](https://github.com/gobby/gobby/wiki) ，一个多平台的协作文本编辑器.  （[Source Code](https://github.com/gobby/gobby)）`MIT`` C ++`
- [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx)  -Office套件，使您可以在一处管理文档，项目，团队和客户关系.  （[Source Code](https://github.com/ONLYOFFICE/DocumentServer)）`AGPL-3.0`` Nodejs`
- [PHPOffice](https://github.com/PHPOffice)  -PHPOffice包含允许从大多数办公套件中写入和读取文件的库.  `LGPL-3.0``PHP`
- [WebODF](http://webodf.org/)  -用于查看和编辑打开文档格式（ODF）文件的工具和库.  （[Source Code](https://github.com/kogmbh/WebODF)）AGPL-3.0 HTML5

## Password Managers

**[`^        back to top        ^`](#)**

- [Bitwarden](https://bitwarden.com/)  `⚠`-带有Web应用程序，浏览器扩展程序和移动应用程序的密码管理器.  （[Source Code](https://github.com/bitwarden/core)) `AGPL-3.0` `C#`
- [bitwarden_rs](https://github.com/dani-garcia/bitwarden_rs)  -用Rust编写的轻量级Bitwarden服务器API实现.  GPL-3.0`Rust
- [keeweb](https://keeweb.info/)  -该Web应用程序是与KeePass数据库兼容的浏览器和桌面密码管理器.  （[Source Code](https://github.com/keeweb/keeweb)）`MIT`` HTML5`
- [Padloc](https://padloc.app/)  -适用于个人和团队的现代，开源密码管理器.  （[Source Code](https://github.com/padloc/padloc)）`GPL-3.0`` Nodejs`
- [Passbolt](https://www.passbolt.com/)  -密码管理器，专用于使用MySQL数据库后端在任何Web服务器上以协作方式管理密码.  （[Source Code](https://github.com/passbolt/passbolt_api)）`AGPL-3.0``PHP`
- [PassIt](https://passit.io/)  -简单的密码管理，具有按组和用户共享的功能，但没有管理界面.  （[Demo](https://app.passit.io/), [Source Code](https://gitlab.com/passit)）`AGPL-3.0``Python`
- [PassWall](https://github.com/passwall/passwall-server)  -开源密码管理器.  AGPL-3.0`Go
- [Psono](https://psono.com/)  -一个有前途的密码管理器，完全适用于团队.  （[Demo](https://www.psono.pw), [Source Code](https://gitlab.com/psono)）`Apache-2.0`` Python`
- [Shaark](https://github.com/MarceauKa/shaark)  -用于链接，故事，密码和相册的多平台平台. 使用Laravel和Vue.js构建. 麻省理工学院PHP
- [sysPass](http://www.syspass.org/)  -多用户密码管理系统.  （[Demo](http://demo.syspass.org/), [Source Code](https://github.com/nuxsmin/sysPass)）`GPL-3.0``PHP`
- [Teampass](http://teampass.net/)  -专用于以协作方式管理密码的密码管理器. 一个对称密钥用于加密所有共享/组密码以及存储在文件和数据库中的服务器端. 可在任何服务器Apache，MySQL和PHP上使用.  （[Source Code](https://github.com/nilsteampassnet/TeamPass)）`GPL-3.0``PHP`

## Pastebins

**[`^        back to top        ^`](#)**

- [0bin](https://github.com/sametmax/0bin)  -客户端加密的pastebin.  WTFPL Python
- [bepasty](https://bepasty-server.readthedocs.io/en/latest/)  -用于各种文件的pastebin.  （[Source Code](https://github.com/bepasty/bepasty-server)）`BSD-2-Clause`` Python`
- [bin](https://github.com/w4/bin)  -一个粘贴容器.  `WTFPL / 0BSD``Rust`
- [cryptonote](https://cryptonote.me/)  -简单的开源Web应用程序，允许用户加密和共享只能读取一次的消息.  （[Source Code](https://github.com/alainmeier/cryptonote)）`MIT`` Ruby`
- [EdPaste](https://github.com/Edraens/EdPaste)  -用Laravel（PHP Framework）编写的自托管pastebin. 麻省理工学院PHP
- [fiche](https://github.com/solusipse/fiche)  -命令行pastebin，您只需要netcat.  （[Demo](http://termbin.com/)）MIT C
- [filite](https://github.com/raftario/filite)  -简单，轻巧和独立的粘贴框，URL缩短器和文件共享服务.  （[Demo](https://filite.raphaeltheriault.com)）``麻省理工学院休息&#39;&#39;
- [FlashPaper](https://github.com/AndrewPaglusch/FlashPaper)  -一次性加密的零知识密码/秘密共享应用程序，专注于简单性和安全性. 无需数据库或复杂的设置.  （[Demo](https://flashpaper.io)）和PHP`
- [Fugacious](https://fugacio.us)  -开源短期安全消息传递（OSSSM）.  （[Source Code](https://github.com/fugacious/fugacious)）`CC0-1.0``Ruby`
- [Hastebin](https://haste.zneix.eu/about.md)  -用Node.js编写的开源pastebin（这是具有扩展维护功能的分支）.  （[Demo](https://haste.zneix.eu), [Source Code](https://github.com/zneix/haste-server)）`MIT`` Node.js`
- [mojopaste](http://search.cpan.org/dist/App-mojopaste/)  -基于Perl的pastebin.  （[Demo](http://p.thorsen.pm/), [Source Code](https://github.com/jhthorsen/app-mojopaste)）`Artistic-2.0`` Perl`
- [MokinToken](https://mokintoken.ramsay.xyz)  -使用tweetnacl进行客户端加密的pastebin.  （[Source Code](https://github.com/nexus-uw/mokintoken)）`Unlicense``PHP`
- [NoteHub](https://github.com/chmllr/NoteHub)  -用于Markdown页面的免费且无忧的Pastebin. 简单，干净，提供密码，生成短链接.  MIT`Nodejs`
- [Paste](https://phpaste.sourceforge.io/)  -粘贴是从购买前使用的原始来源pastebin.com派生的.  （[Source Code](https://github.com/jordansamuel/PASTE)）`GPL-3.0``PHP`
- [pastebin](https://github.com/prologic/pastebin)  -便捷的api和CLI提供简单的pastebin服务.  （[Demo](https://paste.mills.io)）`MIT`` Go`
- [pastebin](https://github.com/mkaczanowski/pastebin)  -简单，快速，功能丰富的独立粘贴框服务. 麻省理工学院
- [pb](https://github.com/ptpb/pb)  -使用长颈瓶打造的轻便的pastebin（和url缩短器）.  GPL-3.0 Python
- [PrivateBin](https://privatebin.info/)  -PrivateBin是一个极简的，开源的在线粘贴/讨论板，其中服务器对托管数据了解为零.  （[Demo](https://privatebin.net/), [Source Code](https://github.com/PrivateBin/PrivateBin)）`Zlib``PHP`
- [PurritoBin](https://github.com/PurritoBin/PurritoBin)  -超快速，简约，加密的命令行粘贴框，其中服务器不了解粘贴数据.  ISC C ++
- [SharpPaste](https://github.com/phonicmouse/SharpPaste) - Cross-platform C# pastebin with client-side AES-256 encryption that just works. `MIT` `C#/NancyFX`
- [Snibox](https://snibox.github.io/)  -代码片段管理器，具有吸引人的面向标签的界面.  （[Demo](https://snibox-demo.herokuapp.com/), [Source Code](https://github.com/snibox/snibox)）`MIT`` Ruby`
- [snipt](https://github.com/nicksergeant/snipt)  -编码员的长期记忆. 共享和存储代码段. 麻省理工学院Python
- [SocksBin](https://github.com/magnumdingusedu/socksbin)  -简单快速的基于终端的pastebin，带有可选的代码突出显示. 不需要特定的客户端，您只需要netcat. [Demo](https://socksbin.magnum.wtf) .  `GPL-3.0`` Python`
- [Stikked](https://github.com/claudehohl/Stikked)  -先进而美丽的Pastbin.  （[Demo](https://paste.scratchbook.ch/)）`GPL-3.0``PHP`
- [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age)  -使用Hashicorp Vault作为秘密存储非常简单（部署和使用）秘密消息服务. 麻省理工学院
- [Pasty](https://github.com/Lukaesebrot/pasty)  -Pasty是一种快速，轻量级的代码粘贴服务器.  （[Demo](https://p.kse.li)）`MIT`` Go`

## Personal Dashboards

**[`^        back to top        ^`](#)**

_也可以看看 [Monitoring](#monitoring)_

- [Baby Buddy](https://github.com/cdubz/babybuddy)  -帮助护理人员跟踪婴儿的睡眠，喂养，尿布更换和肚子时间.  （[Demo](https://babybuddy.herokuapp.com/)）`BSD-2-Clause`` Python`
- [Dashboard](https://github.com/phntxx/dashboard)  -极简主义的主页，用于使用JSON文件来组织Web应用程序和书签.  MIT节点Nodejs / Docker
- [DashMachine](https://github.com/rmountjoy92/DashMachine)  -另一个具有有趣功能的Web应用程序书签仪表板.  GPL-3.0 Python
- [Habitica](https://habitica.com/)  -习惯追踪器应用程序，将您的目标像角色扮演游戏一样对待. 以前称为HabitRPG.  （[Source Code](https://github.com/HabitRPG/habitrpg)）`GPL-3.0 / CC-BY-NC-SA-3.0 / CC-BY-SA-3.0``Nodejs`
- [Heimdall](https://heimdall.site/)  -Heimdall是用于组织所有Web应用程序的优雅解决方案.  （[Source Code](https://github.com/linuxserver/Heimdall)）和PHP`
- [Hiccup](https://designedbyashw.in/test/hiccup/)  -一个漂亮的静态首页，可快速访问您的链接和服务. 它具有内置的搜索，编辑，PWA支持和本地存储缓存，可轻松组织您的起始页.  （[Source Code](https://github.com/ashwin-pc/hiccup)）`MIT`` HTML5`
- [Homepage](https://github.com/tomershvueli/homepage)  -简单，独立，自托管的PHP页面，它是您访问服务器和Web的窗口. 麻省理工学院PHP
- [Homer](https://github.com/bastienwirtz/homer)  -一个简单的静态静态主页，通过简单的Yaml配置和连接检查来公开您的服务器服务.  `Apache-2.0``HTML5`
- [Organizr](https://github.com/causefx/Organizr)  -Organizr的目标是成为服务器前端的一站式服务.  `GPL-3.0``PHP`
- [Personal management system](https://github.com/Volmarg/personal-management-system)  -管理个人数据（账单，付款，工作假期，便笺等）的中心点.  （[Demo](http://personal-management-system.pl/)）和PHP`
- [simple-dash](https://github.com/kutyla-philipp/simple-dash)  -一个简单，响应迅速的仪表板，可转发到您选择的服务.  （[Demo](https://kutyla-philipp.github.io/simple-dash/)）和Javascript
- [Tipboard](http://allegro.tech/tipboard/)  -内部，美味的本地仪表板系统.  （[Source Code](https://github.com/allegro/tipboard)）`Apache-2.0`` Python`
- [wger](http://wger.de/)  -基于网络的个人锻炼，健身和体重记录器/追踪器. 它也可以用作简单的健身房管理实用程序，并提供完整的REST API.  （[Demo](http://wger.de), [Source Code](https://github.com/rolandgeider/wger)）`AGPL-3.0``Python`
- [Your Spotify](https://github.com/Yooooomi/your_spotify)  ⚠-允许您记录您的Spotify监听活动，并通过Web应用程序提供有关它们的统计信息.  MIT节点Nodejs / Docker

## Photo and Video Galleries

**[`^        back to top        ^`](#)**

- [Chevereto Free](https://chevereto.com/free)  -强大而快速的图像托管脚本，可让您在短短几分钟内创建自己的全功能图像托管网站.  （[Source Code](https://github.com/Chevereto/Chevereto-Free)）`AGPL-3.0``PHP`
- [Coppermine](http://coppermine-gallery.net/)  -与各种公告板集成的多语言照相馆. 包括上传批准和受密码保护的相册.  （[Demo](http://coppermine-gallery.net/demo/cpg15x/), [Source Code](https://github.com/coppermine-gallery/cpg1.6.x)）`GPL-3.0``PHP`
- [CumulusClips](http://cumulusclips.org/)  -您自己的具有CumulusClips视频共享脚本的视频共享网站. 您可以建立YouTube克隆，用户可以在其中上传视频，对视频进行评分，对视频进行评论等.  （[Demo](http://demo.cumulusclips.org/)）`GPL-2.0``PHP`
- [Damselfly](https://damselfly.info) - Server-based Digital Asset Management with workflow similar to Picasa. `GPL-3.0` `C#/.Net`
- [Fussel](https://github.com/cbenning/fussel)  -Fussel是静态照片库生成器. 轻松生成反应式画廊，并托管资产的优化静态文件夹. 麻省理工学院Python
- [Gallery CSS](https://benschwarz.github.io/gallery-css/)  -Gallery.css都是CSS. 认为：简单，可维护和可理解的画廊，而无需使用Javascript.  （[Source Code](https://github.com/benschwarz/gallery-css)）MIT CSS
- [ImageStore](https://github.com/gregordr/ImageStore)  -具有非常相似的用户界面的自托管Google相册替代品.  （[Demo](https://gregordr.github.io/ImageStore/)）`Apache-2.0``Nodejs / Docker`
- [LibrePhotos](https://github.com/LibrePhotos/librephotos)  -自行托管的Google Photos克隆软件，略微关注酷图. 麻省理工学院Python
- [Lychee](https://lycheeorg.github.io/)  -开源网格和基于相册的照片管理系统.  （[Source Code](https://github.com/LycheeOrg/Lychee)）和PHP`
- [Mediagoblin](http://mediagoblin.org)  -任何人都可以运行的免费软件媒体发布平台. 您可以将其视为Flickr，YouTube，SoundCloud等的去中心化替代品.[Source Code](https://savannah.gnu.org/projects/mediagoblin)）`AGPL-3.0``Python`
- [Photato](https://github.com/trebonius0/Photato)  -自托管的照片库，可通过响应式WebUI访问. 直接使用文件系统中的特定文件夹并为其建立索引.  AGPL-3.0 Java
- [Photofloat](http://blog.zx2c4.com/567)  -通过静态JSON和动态Javascript完成的Web 2.0照片库.  （[Demo](http://photos.jasondonenfeld.com/)）`GPL-2.0`` Python`
- [PhotoLight](https://github.com/thibaud-rohmer/PhotoLight)  -最简单的照相馆.  `GPL-3.0``PHP`
- [Photonix](https://photonix.org/)  -一种新的基于Web的照片管理应用程序，具有对象识别，位置识别，颜色分析和其他ML算法.  （[Demo](https://demo.photonix.org/), [Source Code](https://github.com/damianmoore/photonix)）`AGPL-3.0``Python`
- [PhotoPrism](https://photoprism.org)  -由Go和Google TensorFlow支持的个人照片管理. 使用最新技术自动标记和查找图片，浏览，整理和共享您的个人照片集.  （[Source Code](https://github.com/photoprism/photoprism)）`MIT`` Go`
- [Photo Stream](https://github.com/maxvoltar/photo-stream)  -极简主义的自托管照片流.  （[Demo](https://maxvoltar.photo/)）`MIT`` Ruby`
- [Photoview](https://github.com/viktorstrate/photoview)  -用于个人服务器的简单易用的图片库. 它是专为摄影师设计的，旨在提供一种方便快捷的导航目录的方法，其中包含数千张高分辨率照片.  （[Demo](https://photos.qpqp.dk/)）`GPL-3.0``Go`
- [PiGallery 2](https://bpatrik.github.io/pigallery2/)  -目录优先的照相馆网站，具有丰富的UI，已针对在低资源服务器上运行进行了优化.  （[Demo](https://pigallery2.herokuapp.com/), [Source Code](https://github.com/bpatrik/pigallery2)）`MIT`` Docker / Nodejs`
- [Piwigo](http://piwigo.org/) - Photo gallery software for the web, built by an active community of users and developers. ([Demo](http://piwigo.org/demo/), [Source Code](https://github.com/Piwigo/Piwigo)）`GPL-2.0``PHP`
- [Plumi](http://plumi.org/)  -创建自己的复杂视频共享网站.  （[Source Code](https://github.com/plumi/plumi.app)）`GPL-2.0`` Python`
- [Quru Image Server](https://quruimageserver.com/)  -高性能，动态调整大小的图像服务器，提供基于目录的访问控制裁剪，旋转，颜色管理和其他工具.  （[Demo](https://quruimageserver.com), [Source Code](https://github.com/quru/qis)）`AGPL-3.0``Python`
- [sigal](https://github.com/saimn/sigal)  -另一个简单的静态图库生成器. 麻省理工学院Python
- [UberGallery](http://www.ubergallery.net)  -UberGallery是易于使用，易于管理的网络照相馆.  UberGallery不需要数据库，并且支持JPEG，GIF和PNG文件类型. 只需上传您的图像，UberGallery就会自动生成缩略图并输出HTML.  （[Source Code](https://github.com/UberGallery/UberGallery)）和PHP`
- [Zenphoto](http://www.zenphoto.org/)  -开源图库和CMS项目.  （[Source Code](https://github.com/zenphoto/zenphoto)）`GPL-2.0``PHP`

## Polls and Events

**[`^        back to top        ^`](#)**

- [Calagator](http://calagator.org/)  -事件汇总器.  （[Source Code](https://github.com/calagator/calagator)）`MIT`` Ruby`
- [Clerk](https://github.com/chr15m/Clerk)  -简单的事件记录器，可跟踪发生的定期事件，习惯等.  `GPL-3.0``PHP`
- [Croodle](https://github.com/jelhan/croodle)  -Croodle是一个端到端的加密Web应用程序，用于安排日期或就任何主题进行民意测验.  MIT JavaScript
- [dudle](http://primelife.ercim.eu/results/opensource/63-dudle)  -在线计划应用程序.  （[Demo](https://dudle.inf.tu-dresden.de/), [Source Code](https://github.com/kellerben/dudle)）`AGPL-3.0``Ruby`
- [Feedka](https://github.com/drabkirn/feedka)  ⚠-开源Web应用程序，可以用作从您的朋友，家人和同事那里获得真实，友善和建设性反馈的平台.  （[Demo](https://feedka.herokuapp.com)）`AGPL-3.0``Ruby`
- [Fider](http://getfider.com)  -UserVoice的开源替代品，以获取客户反馈.  （[Demo](https://demo.fider.io), [Source Code](https://github.com/getfider/fider)）`MIT`` Go`
- [Framadate](https://framadate.org/)  -用于计划约会或快速轻松地做出决定的在线服务：进行民意调查，定义要选择的日期或主题，将民意调查链接发送给您的朋友或同事，讨论并做出决定.  （[Demo](https://framadate.org/aqg259dth55iuhwm), [Source Code](https://git.framasoft.org/framasoft/framadate)）`CECILL-B``PHP`
- [Gancio](https://gancio.org/)  -当地社区的共同议程.  （[Demo](https://demo.gancio.org/), [Source Code](https://framagit.org/les/gancio)）`AGPL-3.0`` Nodejs`
- [hitobito](https://hitobito.com/en)  -一个Web应用程序，用于管理具有成员，事件等更多内容的复杂组层次结构.  （[Demo](https://demo.hitobito.com/en/users/sign_in), [Source Code](https://github.com/hitobito/hitobito)）`AGPL-3.0``Ruby`
- [JD Esurvey](https://www.jdsoft.com/jd-esurvey.html)  -开源企业调查Web应用程序.  （[Source Code](https://github.com/JD-Software/JDeSurvey)）`AGPL-3.0``Java`
- [Kyélà](http://kyela.net/) - Participation polls for group events. ([Demo](https://kyela.net/concert/), [Source Code](https://github.com/abienvenu/Kyela)）`AGPL-3.0``PHP`
- [LimeSurvey](https://www.limesurvey.org)  -功能丰富的基于开源Web的轮询软件. 支持广泛的调查逻辑.  （[Demo](https://demo.limesurvey.org), [Source Code](https://github.com/LimeSurvey/LimeSurvey)）`GPL-2.0``PHP`
- [Meetable](https://meetable.org)  -事件汇总器.  （[Demo](https://events.indieweb.org), [Source Code](https://github.com/aaronpk/Meetable)）和PHP`
- [Mobilizon](https://mobilizon.org)  -联合工具，可帮助您查找，创建和组织事件和组.  （[Demo](https://demo.mobilizon.org/), [Source Code](https://framagit.org/framasoft/mobilizon/)）`GPL-3.0``Elixir`
- [Open Event Server](https://github.com/fossasia/open-event-server)  -使组织者能够管理从音乐会到会议和聚会的活动.  GPL-3.0 Python
- [PHPBack](http://www.phpback.org)  -开源反馈系统.  （[Demo](http://www.phpback.org/demo/), [Source Code](https://github.com/ivandiazwm/phpback)）`GPL-3.0``PHP`

### Booking and Scheduling

- [Alf.io](https://alf.io/)  -开源票务预订系统.  （[Demo](https://demo.alf.io/authentication), [Source Code](https://github.com/alfio-event/alf.io)）`GPL-3.0`` Java`
- [Easy!Appointments](http://easyappointments.org/)  -高度可定制的Web应用程序，使您的客户可以通过Web与您预订约会.  （[Demo](http://easyappointments.org/demo/), [Source Code](https://github.com/alextselegidis/easyappointments)）`GPL-3.0``PHP`

## Proxy

**[`^        back to top        ^`](#)**

- [http2-serverpush-proxy](https://github.com/n1try/http2-serverpush-proxy)  -反向代理，可帮助自动将HTTP / 2.0的服务器推送机制用于静态网站. 可作为中间件和独立应用程序使用.  MIT`Nodejs`
- [imgproxy](https://github.com/DarthSim/imgproxy)  -快速安全的独立服务器，用于调整和转换远程映像的大小. 当您需要即时调整多个图像的大小而无需准备大量缓存的调整大小的图像或每次设计更改时都重新做它时，它非常有用. 麻省理工学院Go / Docker
- [inlets](https://inlets.dev/)  -通过Kubernetes集成，可用的Docker映像和CLI将本地端点公开到Internet. 麻省理工学院Go / Docker
- [iodine](http://code.kryo.se/iodine/)  -IPv4 over DNS隧道解决方案，使您能够启动socks5代理侦听器.  （[Source Code](https://github.com/yarrick/iodine)）`ISC``C`
- [microproxy](https://github.com/thekvs/microproxy)  -轻量级非缓存HTTP / HTTPS代理服务器. 麻省理工学院
- [Nginx Proxy Manager](https://nginxproxymanager.com/)  -Nginx代理管理器是通过SSL终止完成反向代理主机的简便方法.  （[Source Code](https://github.com/jc21/nginx-proxy-manager)）`MIT`` Nodejs / Docker`
- [PHP-Proxy](https://www.php-proxy.com/)  -专门构建的Web代理脚本，可快速，轻松地修改并支持YouTube等视频网站.  （[Demo](https://unblockvideos.com/), [Source Code](https://github.com/Athlon1600/php-proxy-app)）和PHP`
- [Pomerium](https://pomerium.io)  -身份识别的反向代理，是现在已经过时的oauth_proxy的后继代理. 它在将您的请求代理到后端之前插入一个OAuth步骤，以便您可以安全地将自托管网站公开到公共Internet.  （[Source Code](https://github.com/pomerium/pomerium)）`Apache-2.0``Go`
- [Pound](http://www.apsis.ch/pound/)  -轻量级的反向代理和HTTP / HTTPS负载平衡器.  GPL-2.0 C
- [Privoxy](http://www.privoxy.org)  -具有高级过滤功能的非缓存Web代理，可增强隐私，修改网页数据和HTTP标头，控制访问以及删除广告和其他令人讨厌的Internet垃圾.  GPL-2.0 C
- [Redbird](https://github.com/OptimalBits/redbird)  -节点的现代反向代理，包括群集，HTTP2，LetsEncrypt和Docker支持.  BSD-2-Clause Javascript
- [sish](https://github.com/antoniomika/sish)  -开源Servo / Ngrok替代方案，仅使用SSH提供到本地主机的HTTP（S）/ WS（S）/ TCP隧道. 麻省理工学院
- [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server)  -带有内置身份验证和Telegram-bot的SOCKS5代理服务器，用于用户管理和用户统计使用的数据（按GB数据付费时非常方便）. 它被docker化并且易于安装.  Apache-2.0 NodeJS
- [SOCKS5Engine](https://github.com/VeeSecurity/SOCKS5Engine)  -轻巧且资源高效的SOCKS5代理服务器，针对高负载进行了优化.  AGPL-3.0`Go
- [Squid](http://www.squid-cache.org/)  -支持HTTP，HTTPS，FTP等的Web缓存代理. 通过缓存和重用经常请求的网页，它减少了带宽并缩短了响应时间.  （[Source Code](https://code.launchpad.net/squid)）`GPL-2.0``C`
- [Swiperproxy](https://swiperproxy.github.io/)  -快如闪电的开源Web代理，您可以轻松运行和自定义.  （[Source Code](https://github.com/swiperproxy/swiperproxy)）和Python
- [Tinyproxy](https://tinyproxy.github.io/)  -轻量级的HTTP / HTTPS代理守护程序.  （[Source Code](https://github.com/tinyproxy/tinyproxy)）`GPL-2.0``C`
- [Traefik](https://traefik.io/)  -Træfɪk是一种现代的HTTP反向代理和负载平衡器，用于轻松部署微服务. 它支持多个后端（Docker，Swarm，Mesos / Marathon等），以自动，动态地管理其配置.  （[Source Code](https://github.com/containous/traefik)）`MIT`` Go`

## Read it Later Lists

**[`^        back to top        ^`](#)**

- [Nunux Keeper](http://keeper.nunux.org/)  -您的个人内容策划服务.  （[Source Code](https://github.com/ncarlier/nunux-keeper)）`GPL-3.0`` Nodejs`
- [Readflow](https://readflow.app) -具有现代界面和功能的轻型新闻阅读器：全文搜索，自动分类，归档，离线支持，通知...（[Source Code](https://github.com/ncarlier/readflow)）`MIT`` Go`
- [Wallabag](https://www.wallabag.org)  -Wallabag（以前是Poche）是一个网络应用程序，可让您保存文章以供日后阅读，并提高了可读性.  （[Demo](https://app.wallabag.it/register/), [Source Code](https://github.com/wallabag/wallabag)）和PHP`

## Resource Planning

**[`^        back to top        ^`](#)**

- [farmOS](http://farmos.org/)  -基于Web的农场记录保存应用程序.  （[Source Code](https://github.com/farmOS/farmOS)）`GPL-2.0``PHP`
- [grocy](https://grocy.info/)  -冰箱外的ERP-grocy是针对您的家庭的基于Web的自托管杂货和家庭管理解决方案.  （[Demo](https://en.demo.grocy.info/), [Source Code](https://github.com/grocy/grocy)）和PHP`
- [Tania](https://github.com/Tanibox/tania-core)  -Tania是面向所有人的免费开源农业管理系统. 您可以管理您的区域，水库，农场任务，库存和作物生长进度.  `Apache-2.0``Go`

### Enterprise Resource Planning

- [Dolibarr](https://www.dolibarr.org/)  -Dolibarr ERP CRM是一个现代软件包，用于管理公司或基金会的活动（联系人，供应商，发票，订单，库存，议程，会计等）.  （[Demo](https://www.dolibarr.org/onlinedemo.php), [Source Code](https://github.com/Dolibarr/dolibarr)）`GPL-3.0或更高版本``PHP`
- [ERPNext](https://erpnext.com)  -免费的开源ERP系统.  （[Demo](https://demo.erpnext.com), [Source Code](https://github.com/frappe/erpnext)）`GPL-3.0`` Python`
- [LedgerSMB](https://ledgersmb.org/)  -适用于中小型企业的集成会计和ERP系统，具有双重记帐，预算，发票，报价，项目，订单和库存管理，运输等.  （[Demo](https://demo.cloud.efficito.com/erp/1.5/login.pl), [Source Code](https://github.com/ledgersmb/LedgerSMB)）`GPL-2.0`` Perl`
- [Odoo](http://odoo.com)  -免费的开源ERP系统.  （[Demo](https://demo.odoo.com/), [Source Code](https://github.com/odoo/odoo)）`LGPL-3.0``Python`
- [OFBiz](https://ofbiz.apache.org/)  -FOSS企业资源计划系统，具有一套足够灵活的业务应用程序套件，可以在任何行业中使用.  （[Source Code](https://svn.apache.org/viewvc/ofbiz/)）Apache-2.0`` Java`
- [Tryton](http://www.tryton.org/)  -免费的开源业务解决方案.  （[Demo](http://www.tryton.org/download.html), [Source Code](https://hg.tryton.org/)）`GPL-3.0`` Python`

## Search Engines

**[`^        back to top        ^`](#)**

- [Ambar](https://ambar.cloud)  -文档搜索引擎（OCR，存储和搜索）.  （[Demo](https://app.ambar.cloud/), [Source Code](https://github.com/RD17/ambar)）`MIT`` Nodejs / Python`
- [Gigablast](http://www.gigablast.com/)  -开源搜索引擎.  （[Source Code](https://github.com/gigablast/open-source-search-engine)）Apache-2.0`C ++
- [MeiliSearch](https://meilisearch.com)  -超相关，即时且可输入错误的全文本搜索API.  （[Source Code](https://github.com/meilisearch/MeiliSearch)）``麻省理工学院休息&#39;&#39;
- [Searx](https://asciimoo.github.io/searx/)  -尊重隐私，可入侵的元搜索引擎.  （[Demo](https://searx.me/), [Source Code](https://github.com/asciimoo/searx)）`AGPL-3.0``Python`
- [sist2](https://github.com/simon987/sist2)  -快速的文件系统索引器和搜索工具.  （[Demo](https://sist2.simon987.net/)）`GPL-3.0`` C`
- [Typesense](https://typesense.org)  -快速，耐错字的开源搜索引擎，针对开发人员的幸福感和易用性进行了优化.  （[Source Code](https://github.com/typesense/typesense)）`GPL-3.0`` C ++`
- [Yacy](http://yacy.net/en/index.html)  -基于对等的，分散的搜索引擎服务器.  （[Demo](http://search.yacy.net/), [Source Code](https://github.com/yacy/yacy_search_server)）`GPL-2.0`` Java`

## Software Development

**[`^        back to top        ^`](#)**

### Project Management

_也可以看看 [Ticketing](#ticketing), [Task management/To-do lists](#task-managementto-do-lists), [awesome-sysadmin/Code Review](https://github.com/n1trux/awesome-sysadmin#code-review)_

- [Bonobo Git Server](https://bonobogitserver.com/)  -在Windows的IIS上设置您自己的自托管git服务器. 通过一个友好的用户友好图形界面管理用户并完全控制您的存储库.  （[Source Code](https://github.com/jakubgarfield/Bonobo-Git-Server)) `MIT` `C#`
- [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki)  -具有Wiki和错误跟踪器的分布式版本控制系统.  BSD-2-Clause-FreeBSD`C
- [Goodwork](https://usegood.work/)  -由Laravel和VueJS提供支持的自托管项目管理和协作工具.  （[Demo](https://github.com/iluminar/goodwork#demo), [Source Code](https://github.com/iluminar/goodwork)）和PHP`
- [Gitblit](http://gitblit.com/)  -用于管理，查看和提供Git存储库的纯Java堆栈.  （[Source Code](https://github.com/gitblit/gitblit)）Apache-2.0`` Java`
- [gitbucket](https://gitbucket.github.io/gitbucket-news/)  -由Scala支持的易于安装的GitHub克隆.  （[Source Code](https://github.com/gitbucket/gitbucket)）`Apache-2.0`` Scala / Java`
- [Gitea](https://gitea.io)  -社区管理的Gogs分支，轻量级代码托管解决方案.  （[Demo](https://try.gitea.io), [Source Code](https://github.com/go-gitea/gitea)）`MIT`` Go`
- [GitLab](http://gitlab.org/)  -自托管Git存储库管理，代码审查，问题跟踪，活动供稿和Wiki.  （[Demo](https://gitlab.com/), [Source Code](https://gitlab.com/gitlab-org/gitlab-foss)）`MIT`` Ruby`
- [Gitlist](http://gitlist.org/)  -基于Web的git存储库浏览器-GitList允许您使用自己喜欢的浏览器浏览存储库，查看不同修订版下的文件，提交历史记录和差异.  （[Source Code](https://github.com/klaussilveira/gitlist)）`BSD-3-Clause``PHP`
- [Gitolite](http://gitolite.com/gitolite/index.html)  -Gitolite允许您在中央服务器上设置git托管，具有细粒度的访问控制和许多更强大的功能.  （[Source Code](https://github.com/sitaramc/gitolite)）`GPL-2.0`` Perl`
- [GitPrep](http://gitprep.yukikimoto.com/)  -便携式Github克隆.  （[Demo](http://perlcodesample.sakura.ne.jp/gitprep/gitprep.cgi), [Source Code](https://github.com/yuki-kimoto/gitprep)）`Artistic-2.0`` Perl`
- [Git WebUI](https://github.com/alberthier/git-webui)  -git存储库的基于Web的独立用户界面.  Apache-2.0 Python
- [Gogs](https://gogs.io/)  -用Go编写的无痛自托管Git服务.  （[Demo](https://try.gogs.io/), [Source Code](https://github.com/gogits/gogs)）`MIT`` Go`
- [Kallithea](https://kallithea-scm.org/)  -源代码管理系统，通过Web界面支持两个领先的版本控制系统Mercurial和Git.  （[Source Code](https://kallithea-scm.org/repos/kallithea)）`GPL-3.0`` Python`
- [Klaus](https://github.com/jonashaag/klaus)  -易于使用的简单易设置的Git Web查看器.  ISC Python
- [Lavagna](http://lavagna.io)  -Lavagna是专为小型团队设计的开源问题/项目管理工具. 轻巧，纯Java，易于安装，易于使用.  （[Source Code](https://github.com/digitalfondue/lavagna)）`GPL-3.0`` Java`
- [Lazylead](https://lazylead.org)  `⚠`-消除票务系统（Jira，GitHub，Trello）中令人讨厌的工作. 允许自动执行日常操作，例如票证字段验证，JQL / GQL的电子邮件通知，对您（或队友）日历的会议请求.  （[Source Code](https://github.com/dgroup/lazylead)）`MIT`` Ruby`
- [Leantime](https://leantime.io)  -Leantime是一个面向小型团队和初创公司的精益项目管理系统，有助于管理从构思到交付的项目.  （[Source Code](https://github.com/leantime/leantime)）`GPL-2.0``PHP`
- [Microgit](https://github.com/microgit-com/microgit)  -由Crystal和Lucky提供的Git托管服务.  MIT水晶
- [Octobox](https://octobox.io/)  `⚠`-收回对GitHub通知的控制权.  （[Source Code](https://github.com/octobox/octobox)）`AGPL-3.0``Ruby`
- [OpenProject](https://www.openproject.org)  -OpenProject是一个基于Web的项目管理系统.  （[Source Code](https://github.com/opf/openproject)）`GPL-3.0`` Ruby`
- [Pagure](https://pagure.io/pagure)  -轻巧，强大且灵活的以git为中心的伪造，其功能为联合和分散式开发奠定了基础.  （[Demo](https://pagure.io/)）`GPL-2.0`` Python`
- [Phabricator](http://phabricator.org/)  -收集有助于构建更好软件的Web应用程序.  （[Demo](https://secure.phabricator.com/), [Source Code](https://github.com/phacility/phabricator)）`Apache-2.0``PHP`
- [Phproject](http://www.phproject.org/)  -高性能的功能齐全的项目管理系统.  （[Demo](http://demo.phproject.org/), [Source Code](https://github.com/Alanaktion/phproject)）`GPL-3.0``PHP`
- [ProjeQtOr](https://www.projeqtor.org/)  -完整，成熟的多用户项目管理系统，在项目的所有阶段均具有广泛的功能.  （[Demo](https://demo.projeqtor.org/), [Source Code](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)）`AGPL-3.0``PHP`
- [Re:Backlogs](https://github.com/kaishuu0123/rebacklogs)  -由Ruby on Rails和VueJS支持的项目管理和协作工具.  （[Demo](https://rebacklogs.saino.me/users/sign_up)）`MIT`` Ruby`
- [Redmine](http://www.redmine.org/)  -Redmine是一个灵活的项目管理Web应用程序.  （[Demo](http://demo.redmine.org/), [Source Code](https://svn.redmine.org/redmine/)）`GPL-2.0`` Ruby`
- [RhodeCode](https://rhodecode.com/) - RhodeCode is an open source platform for software development teams. It unifies and simplifies repository management for Git, Subversion, and Mercurial. ([Demo](https://try.rhodecode.com/), [Source Code](https://code.rhodecode.com/)）`AGPL-3.0``Python`
- [SCM Manager](https://www.scm-manager.org/)  -通过http共享和管理Git，Mercurial和Subversion存储库的最简单方法.  （[Source Code](https://github.com/scm-manager/scm-manager)）`BSD-3-Clause`` Java`
- [Taiga](https://taiga.io/)  -基于看板和Scrum方法的敏捷项目管理工具.  （[Source Code](https://github.com/taigaio)）`AGPL-3.0``Python`
- [Titra](https://titra.io/en/free-time-tracking-online/)  -自由职业者和小型团队的时间跟踪解决方案.  （[Demo](https://app.titra.io/try), [Source Code](https://github.com/kromitgmbh/titra)）`GPL-3.0``JavaScript`
- [Trac](http://trac.edgewall.org/)  -Trac是用于软件开发项目的增强的Wiki和问题跟踪系统.  BSD-3-Clause Python
- [Tuleap](https://www.tuleap.org/)  -Tuleap是一个自由套件，用于计划，跟踪，编码和在软件项目上进行协作.  （[Source Code](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)）`GPL-2.0``PHP`
- [UVDesk](https://www.uvdesk.com/)  -UVDesk社区是一个面向服务，事件驱动的可扩展开源帮助台系统，您的组织可以使用该平台以您想像的任何方式毫不费力地为您的客户提供有效的支持.  （[Demo](https://demo.uvdesk.com/), [Source Code](https://github.com/uvdesk/community-skeleton)）和PHP`
- [ZenTao](http://www.zentao.pm/)  -敏捷（scrum）项目管理系统/工具.  （[Demo](http://demo.zentao.pm/user-login.html), [Source Code](https://github.com/easysoft/zentaopms)）`ZPL-1.2``PHP`

### Bug Trackers

_See [Ticketing](#ticketing)_

### IDE/Tools

- [Atheos](https://www.atheos.io)  -Codiad继续提供基于Web的IDE框架，该框架占地面积小且要求最低.  （[Source Code](https://github.com/Atheos/Atheos)）和PHP`
- [Babelfish](https://github.com/bblfsh/bblfshd)  -用于源代码解析的自托管服务器. 它可以以任何受支持的语言解析任何文件，从文件中提取一个抽象语法树，然后将其转换为通用抽象语法树，从而可以进行进一步的分析和转换.  GPL-3.0`Go`
- [Code-Server](https://coder.com/)  -浏览器中的Visual Studio代码，位于远程服务器上.  （[Source Code](https://github.com/cdr/code-server)）`MIT`` Nodejs / Docker`
- [Eclipse Che](http://www.eclipse.org/che/)  -开源工作区服务器和云IDE.  （[Source Code](https://github.com/eclipse/che)）`EPL-1.0``Docker / Java`
- [Gitpod](https://gitpod.io/)  -适用于GitHub和GitLab的在线IDE.  （[Demo](https://gitpod.io/#https://github.com/awesome-selfhosted/awesome-selfhosted), [Source Code](https://github.com/gitpod-io/self-hosted)）`EPL-2.0``Go / Docker`
- [Hakatime](https://github.com/mujx/hakatime)  -具有分析仪表板的WakaTime服务器实施.  `无证``Haskell`
- [HttPlaceholder](https://github.com/dukeofharen/httplaceholder) - Quickly mock away any webservice using HttPlaceholder. HttPlaceholder lets you specify what the request should look like and what response needs to be returned. `MIT` `C#`
- [ICEcoder](https://icecoder.net/)  -ICEcoder是基于Web IDE /浏览器的代码编辑器，可让您直接在Web浏览器中开发网站.  （[Demo](http://demo.icecoder.net/ICEcoder/), [Source Code](https://github.com/icecoder/ICEcoder)）和PHP`
- [JS Bin](http://jsbin.com/)  -开源协作式Web开发调试工具.  （[Source Code](https://github.com/jsbin/jsbin)）`与`Node.js`
- [Judge0 API](https://api.judge0.com)  -开源API，用于编译和运行源代码.  （[Source Code](https://github.com/judge0/api)）`GPL-3.0`` Ruby`
- [JupyterLab](http://jupyterlab.github.io/jupyterlab/)  -用于交互式和可复制计算的基于Web的环境.  （[Demo](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), [Source Code](https://github.com/jupyterlab/jupyterlab/)）`BSD-3-Clause``Python / Docker`
- [Koding](http://www.koding.com/)  -管理整个开发基础架构的最简单方法.  （[Source Code](https://github.com/koding/koding)）`Apache-2.0`` Nodejs`
- [ML Workspace](https://github.com/ml-tooling/ml-workspace)  -用于机器学习和数据科学的基于Web的多合一IDE.  `Apache-2.0``Docker`
- [Regexr](http://regexr.com/)  -RegExr是基于HTML / JS的工具，用于创建，测试和学习正则表达式.  （[Source Code](https://github.com/gskinner/regexr)）`与`Node.js`
- [RequestBin](https://github.com/Runscope/requestbin)  -检查HTTP请求. 调试webhook. 麻省理工学院python
- [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) -用于R的基于Web浏览器的IDE.[Source Code](https://github.com/rstudio/rstudio)）`AGPL-3.0``Java / C ++`
- [Slingcode](https://slingcode.net/)  -单个静态HTML文件中的Web应用程序IDE和计算平台.  （[Demo](https://slingcode.net/slingcode.html), [Source Code](https://github.com/chr15m/slingcode/)）MIT HTML
- [sourcegraph](https://sourcegraph.com)  -Sourcegraph是使用Go编写的快速，开源，功能齐全的代码搜索和导航引擎.  （[Source Code](https://github.com/sourcegraph/sourcegraph)）`Apache-2.0``Go`
- [Wakapi](https://github.com/n1try/wakapi)  -用于编码统计信息的跟踪工具，与WakaTime兼容.  GPL-3.0`Go`

### Continuous Integration

_See [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/n1trux/awesome-sysadmin#continuous-integration--continuous-deployment)_

### UX testing

- [Uier](https://github.com/sjoerdvanderhoorn/Uier)  -使用Selenium执行测试或UI自动化的无代码或低代码用户体验测试编辑和管理.  Uier往往是Applitools，Endtest，Ghost Inspector，Usetrace，Screenster和许多其他工具的免费自托管替代产品.  Apache-2.0 NodeJS
- [Selenoid](http://aerokube.com/selenoid/latest/)  -轻量级的Selenium集线器实施，可在Docker容器中启动浏览器.  （[Source Code](https://github.com/aerokube/selenoid)）`Apache-2.0``Go`

### FaaS/Serverless

_[Serverless computing on Wikipedia](https://en.wikipedia.org/wiki/Serverless_computing)_

- [Appwrite](https://appwrite.io)  -适用于Web，本地和移动开发人员的端到端后端服务器.  （[Source Code](https://github.com/appwrite/appwrite)）`BSD-3-Clause``PHP`
- [fx](https://github.com/metrue/fx)  -fx是一种工具，可帮助您轻松地在自己的服务器上执行“功能即服务”. 麻省理工学院
- [IronFunctions](https://github.com/iron-io/functions) -无服务器微服务平台 [iron.io](https://www.iron.io/) .  `Apache-2.0``Go`
- [LocalStack](https://localstack.cloud/)  -LocalStack是功能齐全的本地AWS云堆栈. 这包括用于无服务器计算的Lambda.  （[Source Code](https://github.com/localstack/localstack)）`Apache-2.0``Python / Other`
- [OpenFaaS](https://www.openfaas.com/)  -无服务器功能使Docker和Kubernetes变得简单.  （[Source Code](https://github.com/openfaas/faas)）`MIT`` Go`
- [Trusted-CGI](https://github.com/reddec/trusted-cgi)  -轻型自托管的lambda / applications / cgi / serverless-functions平台. 麻省理工学院

### API Management

- [DreamFactory](https://www.dreamfactory.com/)  -将任何SQL / NoSQL /结构化数据转换为Restful API.  （[Source Code](https://github.com/dreamfactorysoftware/dreamfactory)）`Apache-2.0``PHP`
- [Fusio](http://www.fusio-project.org/)  -开源API管理平台，可帮助构建和管理REST API.  （[Demo](http://fusio-project.org/demo), [Source Code](https://github.com/apioo/fusio)）`AGPL-3.0``PHP`
- [Hapttic](https://github.com/jsoendermann/hapttic)  -简单的HTTP服务器，它将所有请求转发到Shell脚本以处理您收到的Webhook.  `Apache-2.0``Go`
- [Hasura](https://hasura.io)  -Postgres上具有细粒度访问控制的快速，即时实时GraphQL API，也可以触发数据库事件的webhooks.  （[Source Code](https://github.com/hasura/graphql-engine)）`Apache-2.0``Haskell`
- [Hoppscotch](https://hoppscotch.io)  -一个免费，快速，美观的API请求构建器.  （[Source Code](https://github.com/hoppscotch/hoppscotch)）`MIT`` Nodejs / Vue / Nuxt`
- [Kong](https://konghq.com/kong/)  -世界上最受欢迎的开源微服务API网关和平台.  （[Source Code](https://github.com/Kong/kong)）`Apache-2.0`` Lua`
- [KrakenD](https://www.krakend.io/)  -开源高性能API网关.  （[Source Code](https://github.com/devopsfaith/krakend)）`Apache-2.0``Go`
- [Para](http://www.paraio.org)  -灵活的模块化后端框架/服务器，用于对象持久性，API开发和身份验证.  （[Source Code](https://github.com/erudika/para)）Apache-2.0`` Java`
- [Pizzly](https://github.com/bearer/pizzly)  -开源API集成管理器，提供开发人员与基于OAuth的API进行交互所需的一切.  MIT`Nodejs`
- [Tyk](https://tyk.io)  -快速且可扩展的开源API网关.  Tyk开箱即用，提供了一个带有API网关，API Analytics，开发人员门户和API管理仪表板的API管理平台.  （[Source Code](https://github.com/TykTechnologies/tyk)）`MPL-2.0``Go`

### Documentation Generators

_也可以看看 [Static site generators](#static-site-generators)_

- [Docstore](http://haldean.org/)  -静态文档托管无需任何服务器端处理，不需要您每次更改文章时都重新编译. 克隆存储库，然后在text /目录中添加文章以开始使用.  （[Source Code](https://github.com/haldean/docstore)）`BSD-3-Clause``Javascript`
- [Flatdoc](http://ricostacruz.com/flatdoc/)  -小型Javascript文件，可提取Markdown文件并将其呈现为整页.  MIT Java语言
- [markdown-tree](https://github.com/mil/markdown-tree)  -提供markdown文件的层次结构/树目录. 适用于内置Markdown的小型网站. 麻省理工学院Ruby
- [Read the Docs](https://docs.readthedocs.org/en/latest/install.html)  -主机文档，使其完全可搜索且易于查找； 使用任何主要的版本控制系统（包括Mercurial，Git，Subversion和Bazaar）导入文档.  （[Demo](https://readthedocs.org/projects/), [Source Code](https://github.com/rtfd/readthedocs.org)）和Python

### Localization

- [Accent](https://www.accent.reviews/)  -开源，自托管，面向开发人员的翻译工具.  （[Source Code](https://github.com/mirego/accent)）`BSD-3-Clause``Elixir`
- [Pootle](http://pootle.translatehouse.org)  -在线翻译和本地化工具.  （[Source Code](https://github.com/translate/pootle)）`GPL-3.0`` Python`
- [Traduora](https://traduora.com)  -团队翻译管理平台.  （[Source Code](https://github.com/traduora/traduora)）`AGPL-3.0``Docker / Nodejs`
- [Weblate](https://weblate.org)  -基于Web的翻译工具，具有紧密的版本控制集成.  （[Demo](https://demo.weblate.org), [Source Code](https://github.com/WeblateOrg/weblate)）`GPL-3.0`` Python`
- [Zanata](http://zanata.org)  -基于Web的翻译平台，供翻译人员，内容创建者和开发人员管理本地化项目.  （[Source Code](https://github.com/zanata/zanata-platform)）`GPL-2.0`` Java`

## Static site generators

**[`^        back to top        ^`](#)**

_请参阅https://staticsitegenerators.net和https：//www.staticgen.com_

## Task management/To-do lists

**[`^        back to top        ^`](#)**

_也可以看看 [Project Management](#project-management) 和 [Ticketing](#ticketing)._

- [Kanbana](https://github.com/SrGMC/kanbana)  -创建公告板以跟踪纯平价降价文件中的用户和项目. 从Crepido分叉.  MIT`Nodejs`
- [Kanboard](http://kanboard.net/)  -简单和开放源代码的可视任务板.  （[Source Code](https://github.com/kanboard/kanboard)）和PHP`
- [myTinyTodo](http://www.mytinytodo.net/)  -以AJAX样式管理待办事项列表的简单方法. 使用PHP，jQuery，SQLite / MySQL. 符合GTD.  （[Demo](http://www.mytinytodo.net/demo/), [Source Code](https://github.com/maxpozdeev/mytinytodo/)）`GPL-2.0``PHP`
- [Nullboard](https://github.com/apankrat/nullboard)  -单页极简版看板； 紧凑，易读且使用迅速.  （[Demo](https://nullboard.io/preview)）`BSD-2-Clause``Javascript`
- [PHP Task/Todo list](https://github.com/lgg/tasks.php)  -使用JSON文本文件执行任务的简单任务/待办事项列表. 麻省理工学院PHP
- [Planka](https://planka.app/)  -开源Trello替代方案.  （[Demo](https://plankanban.github.io/planka/#/), [Source Code](https://github.com/plankanban/planka)）`与`Node.js`
- [Restyaboard](http://restya.com/board/)  -开源的Trello式看板.  （[Demo](http://restya.com/board/demo.html), [Source Code](https://github.com/RestyaPlatform/board)）OSL-3.0`PHP
- [Task Keeper](https://github.com/nymanjens/piga)  -由自托管服务器支持的高级用户列表编辑器.  `Apache-2.0``Scala`
- [TaskBoard](http://taskboard.matthewross.me/)  -看板风格的应用程序，用于跟踪需要完成的事情.  （[Demo](https://taskboard.matthewross.me/demo.html), [Source Code](https://github.com/kiswa/TaskBoard)）和PHP`
- [Taskfreak](http://www.taskfreak.com/original)  -用PHP编写的简单但有效的基于Web的任务管理器.  `GPL-3.0``PHP`
- [Tasks](https://github.com/m1guelpf/tasks)  -使用自定义平面文件数据库以PHP，jQuery和Bootstrap编写的简单任务和注释管理器.  MPL-2.0 PHP
- [Tasks](https://github.com/thewhitetulip/Tasks)  -用Go语言编写的基于看板的待办事项列表管理器. 麻省理工学院
- [Taskord](https://taskord.com)  -与制造者社区进行社交活动.  （[Source Code](https://gitlab.com/yo/taskord)）和PHP`
- [Taskwarrior](https://taskwarrior.org/)  -Taskwarrior是免费的开源软件，可从命令行管理TODO列表. 它灵活，快速，高效且不引人注目. 它会尽力而为，然后让您摆脱困境.  （[Source Code](https://taskwarrior.org/download/#git)）`MIT`` C ++`
- [Tinyissue](https://github.com/satrun77/tinyissue)  -团队的简单问题跟踪. 麻省理工学院PHP
- [todo](https://github.com/prologic/todo)  -简单的待办事项列表管理器.  （[Demo](https://todo.mills.io)）`MIT`` Go`
- [todoMini](https://www.todomini.app/)  -移动友好的零功能TODO列表网络应用.  Unix哲学.  （[Demo](https://appmini.github.io/todoMini/?demo), [Source Code](https://github.com/appMini/todoMini)）`GPL-3.0`` PHP / Java`
- [Tracks](http://www.getontracks.org/) -基于网络的应用程序，可帮助您实现David Allen [Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done) 方法.  （[Source Code](https://github.com/TracksApp/tracks)）`GPL-2.0`` Ruby`
- [Vikunja](https://vikunja.io/)  -待办事项应用程序可以组织您的生活.  （[Demo](https://try.vikunja.io/login), [Source Code](https://kolaente.dev/vikunja/)）`GPL-3.0``Go`
- [Wekan](https://wekan.github.io/)  -像Trello一样的开源看板.  （[Source Code](https://github.com/wekan/wekan)）`与`Node.js`

## Ticketing

**[`^        back to top        ^`](#)**

_也可以看看 [Task management/To-do lists](#task-managementto-do-lists) 和 [Project Management](#project-management)_

- [Bugzilla](https://www.bugzilla.org/)  -最初由Mozilla项目开发和使用的通用Bugtracker和测试工具.  MPL-2.0 Perl
- [Bumpy Booby](http://bumpy-booby.derivoile.fr/)  -简单，响应迅速且高度可定制的PHP错误跟踪系统.  （[Source Code](https://github.com/piero-la-lune/Bumpy-Booby)）和PHP`
- [DiamanteDesk](http://diamantedesk.com/)  -DiamanteDesk是免费的开源易于使用的帮助台解决方案.  （[Demo](http://diamantedesk.com/demo/), [Source Code](https://github.com/eltrino/diamantedesk-application)）OSL-3.0`PHP
- [django-todo](http://django-todo.org/)  -django-todo是一个可插入的，多用户，多组，多列表的待办事项和票务系统-一种可重用的应用程序，旨在放入任何现有的Django项目中.  （[Source Code](https://github.com/shacker/django-todo)）`BSD-3-Clause`` Python / Django`
- [Erxes](https://erxes.io/install/)  -营销，销售和客户服务平台，旨在帮助企业吸引更多敬业的客户.  （[Demo](https://demo.erxes.io/), [Source Code](https://github.com/erxes/erxes)）`GPL-3.0``Javascript`
- [Flyspray](http://www.flyspray.org/)  -简单，基于Web的错误跟踪系统.  （[Source Code](https://github.com/Flyspray/flyspray)）`GPL-2.0``PHP`
- [FreeScout](https://github.com/freescout-helpdesk/freescout)  -Help Scout的开源克隆：基于电子邮件的客户支持应用程序，帮助台和共享邮箱.  `AGPL-3.0``PHP`
- [Helpy](https://helpy.io)  -Helpy是一个现代的开源帮助台客户支持应用程序. 功能包括知识库，社区讨论以及与电子邮件集成的支持票证.  （[Demo](https://demo.helpy.io), [Source Code](https://github.com/helpyio/helpy)）`MIT`` Ruby`
- [HuBoard](https://github.com/huboard/huboard)  `⚠`-您的GitHub问题的即时项目管理（直接连接GitHub API）. 麻省理工学院Ruby
- [MantisBT](https://www.mantisbt.org/)  -自托管的错误跟踪器，最适合软件开发.  （[Demo](https://www.mantisbt.org/bugs/my_view_page.php), [Source Code](https://github.com/mantisbt/mantisbt)）`GPL-2.0``PHP`
- [OpenSupports](https://www.opensupports.com/)  -具有常见问题，角色管理，指标和罐头响应功能的多语言票证系统.  （[Demo](https://www.opensupports.com/demo/), [Source Code](https://github.com/opensupports/opensupports)）`GPL-3.0``PHP`
- [osTicket](http://osticket.com/)  -在一个地方管理，组织和存档所有支持请求和响应.  （[Source Code](https://github.com/osTicket/osTicket)）`GPL-2.0``PHP`
- [OTRS](http://www.otrs.com/)  -故障票证系统，用于将票证分配给传入的查询并跟踪进一步的通信.  （[Source Code](https://github.com/OTRS/otrs)）`AGPL-3.0``Perl`
- [Request Tracker](https://www.bestpractical.com/rt/)  -企业级问题跟踪系统.  （[Source Code](https://github.com/bestpractical/rt)）`GPL-2.0`` Perl`
- [Sentry On-Premise](https://github.com/getsentry/onpremise)  -强大的错误跟踪平台，具有广泛的语言支持和强大的API.  （[Source Code](https://github.com/getsentry/sentry)）`BSD-3-Clause`` Python / Django`
- [SIT](https://sit.fyi/)  -与SCM无关，基于文件，脱机优先，不可变的问题跟踪器.  （[Source Code](https://github.com/sit-fyi/sit)）和Apache-2.0` Rust
- [TheBugGenie](http://www.thebuggenie.org)  -友好的项目管理和问题跟踪工具，具有广泛的用户权限系统.  （[Source Code](https://github.com/thebuggenie/thebuggenie)）`MPL-2.0``PHP`
- [Zammad](https://zammad.org/)  -易于使用，但功能强大的开源支持和票务系统.  （[Source Code](https://github.com/zammad/zammad)）`AGPL-3.0``Ruby`

## URL Shorteners

_在托管一个之前，请参阅 [shortcomings](https://en.wikipedia.org/wiki/URL_shortening#Shortcomings) URL缩短器._

**[`^        back to top        ^`](#)**

- [gShort](https://github.com/someone-stole-my-name/gShort)  -隐私友好的自托管网址缩短器.  （[Demo](http://gshort.christiansegundo.com/)）`GPL-3.0``Go`
- [Kutt](https://kutt.it)  -一种现代的URL缩短器，支持自定义域.  （[Source Code](https://github.com/thedevs-network/kutt)）`与`Node.js`
- [Link-shortener-bot](https://github.com/tommyku/link-shortener-front-end)  `⚠`-使用Telegram Bot的URL缩短器.  （[Demo](http://t.me/GiveMeShortLinkBot)）`MIT`` Ruby`
- [liteshort](https://git.ikl.sh/132ikl/liteshort)  -用户友好，轻巧且可配置的URL缩短器.  （[Demo](https://ls.ikl.sh)）和Python
- [Lstu](https://github.com/ldidry/lstu)  -_让我们减少网址_-轻巧的URL缩短器.  `WTFPL``Perl`
- [Polr](https://project.polr.me/)  -现代，简约，模块化和轻量级的URL缩短器.  （[Source Code](https://github.com/Cydrobolt/polr)）`GPL-2.0``PHP`
- [reduc.io](https://github.com/ziyasal/reducio)  -使用Akka-Http和Redis用Scala编写的URL缩短服务.  MIT斯卡拉
- [ReducePy](https://github.com/abdullahselek/ReducePy)  -使用Tornado和Redis的URL缩短服务在Docker和Kubernetes上运行. 麻省理工学院Python
- [schort](https://github.com/sqozz/schort)  -没有登录，没有JavaScript，只有短链接.  （[Demo](https://s.wx0.de)）`CC0-1.0``Python`
- [Shlink](https://shlink.io)  -带有REST API和命令行界面的URL缩短器. 包括官方的渐进式Web应用程序和Docker映像.  （[Source Code](https://github.com/shlinkio/shlink), [Clients](https://shlink.io/apps)）和PHP`
- [shorturl](https://github.com/prologic/shorturl)  -简单的URL缩短器，具有非常小的URL.  （[Demo](https://url.mills.io)）`MIT`` Go`
- [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener)  -公共或私人（带帐户）的KISS URL缩短器. 极简和轻巧. 没有依赖关系.  （[Demo](https://u.azlux.fr)）和PHP`
- [Simply Shorten](https://github.com/draganczukp/simply-shorten)  -一个简单的URL缩短器，可以缩短链接.  MIT Java
- [url-shortener](https://github.com/cagataycali/url-shortener)  `⚠`-Shitty网址缩短器，表情符号和AI支持.  MIT`Nodejs`
- [URL-Shortener](https://github.com/sapioit/URL-shortener)  -使长链接短，并且仅使用小写字母，因此您可以更快地编写和拼写它们.  （[Demo](http://scurtez.cf)）`GPL-3.0``PHP`
- [YOURLS](http://yourls.org/)  -YOURLS是一组PHP脚本，可让您运行自己的URL缩短器. 功能包括密码保护，URL自定义，书签，统计信息，API，插件，jsonp.  （[Source Code](https://github.com/YOURLS/YOURLS)）和PHP`

## VPN

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#vpn_

## Web servers

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#web_

## Wikis

**[`^        back to top        ^`](#)**

_也可以看看 [Documentation Generators](#documentation-generators), [Wikimatrix](http://www.wikimatrix.org/), [Wiki Engines on WikiIndex](http://wikiindex.org/Category:Wiki_Engine), [List of wiki software on wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [Comparison of wiki software on wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)._

- [BookStack](https://www.bookstackapp.com/)  -BookStack是一个简单的，自托管的，易于使用的平台，用于组织和存储信息. 它允许将文档存储在类似时尚的书中.  （[Demo](https://www.bookstackapp.com/#demo), [Source Code](https://github.com/ssddanbrown/BookStack)）和PHP`
- [Cowyo](https://github.com/schollz/cowyo)  -Cowyo是功能强大的极简主义者Wiki.  （[Demo](https://cowyo.com)）`MIT`` Go`
- [django-wiki](https://github.com/django-wiki/django-wiki)  -具有复杂功能的Wiki系统，用于简单的集成和精湛的界面. 用样式存储您的知识：使用Django模型.  （[Demo](https://demo.django-wiki.org/)）`GPL-3.0`` Python`
- [Documize](https://documize.com)  -具有内置工作流程，单个二进制可执行文件的现代Docs + Wiki软件，只需带上MySQL / Percona.  （[Source Code](https://github.com/documize/community)）`AGPL-3.0``Go`
- [Dokuwiki](https://www.dokuwiki.org/DokuWiki)  -易于使用，轻巧且符合标准的Wiki引擎，其语法简单，可读取Wiki外部的数据. 所有数据都存储在纯文件中，因此不需要数据库.  （[Source Code](https://github.com/splitbrain/dokuwiki)）`GPL-2.0``PHP`
- [Gitit](https://github.com/jgm/gitit)  -将页面和上载的文件存储在git存储库中的Wiki程序，然后可以使用VCS命令行工具或Wiki的Web界面对其进行修改.  GPL-2.0哈斯克尔
- [Gollum](https://github.com/gollum/gollum)  -由Git驱动的简单Wiki，具有出色的API和本地前端. 麻省理工学院Ruby
- [jingo](https://github.com/claudioc/jingo)  -为node.js编写的基于Git的Wiki引擎，具有不错的设计，搜索能力和良好的排版.  MIT`Nodejs`
- [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki)  -MediaWiki是使用PHP编写的免费开源Wiki软件包. 它是Wikipedia和其他Wikimedia项目的平台，每月有成千上万人使用.  （[Demo](https://en.wikipedia.org/wiki/Main_Page), [Source Code](https://phabricator.wikimedia.org/diffusion/MW/)）`GPL-2.0``PHP`
- [MoinMoin](https://moinmo.in/)  -具有大量用户的先进，易用且可扩展的WikiEngine.  （[Source Code](https://github.com/moinwiki/moin-1.9)）`GPL-2.0`` Python`
- [Outline](https://www.getoutline.com/)  `⚠`-使用React和Node.js为您的团队提供的开放，可扩展的Wiki.  （[Source Code](https://github.com/outline/outline)）`BSD-3-Clause``Nodejs`
- [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki)  -完整的由markdown支持的Wiki，包含在单个PHP文件中.  （[Demo](https://starbeamrainbowlabs.com/labs/peppermint/build/)）`MPL-2.0``PHP`
- [PineDocs](https://github.com/xy2z/PineDocs)  -简单，快速，可自定义且轻量级的网站，用于浏览文件.  `GPL-3.0``PHP`
- [PmWiki](http://www.pmwiki.org)  -基于Wiki的系统，用于协作创建和维护网站.  `GPL-3.0``PHP`
- [Raneto](http://raneto.com/)  -Raneto是一个开源知识库平台，该平台使用静态Markdown文件为您的知识库提供支持.  MIT`Nodejs`
- [TiddlyWiki](http://tiddlywiki.com/)  -可重复使用的非线性个人网络笔记本.  （[Source Code](https://github.com/Jermolene/TiddlyWiki5)）`BSD-3-Clause``Nodejs`
- [Tiki](https://tiki.org)  -具有最多内置功能的Wiki CMS组件.  （[Demo](https://tiki.org/Demo), [Source Code](https://sourceforge.net/p/tikiwiki/code/HEAD/tree/)）`LGPL-2.1``PHP`
- [TWiki](http://twiki.org/)  -TWiki是基于Perl的结构化Wiki应用程序，通常用于运行协作平台，知识或文档管理系统，知识库或团队门户.  （[Demo](http://twiki.org/cgi-bin/view/Sandbox/WebHome), [Source Code](http://svn.twiki.org/svn/twiki/)）`GPL-1.0`` Perl`
- [wiki](https://github.com/prologic/wiki)  -基于简单Markdown的Wiki引擎.  （[Demo](https://wiki.mills.io)）`MIT`` Go`
- [Wiki.js](https://wiki.js.org/)  -建立在NodeJS，Git和Markdown之上的现代，轻巧且功能强大的Wiki应用程序.  （[Demo](https://docs.requarks.io)）`AGPL-3.0`` Nodejs`
- [WiKiss](http://wikiss.tuxfamily.org/)  -Wiki，易于使用和安装.  （[Source Code](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)）`GPL-2.0``PHP`
- [XWiki](http://www.xwiki.org)  -第二代Wiki，允许用户使用功能强大的基于扩展的体系结构扩展其功能.  （[Demo](http://playground.xwiki.org), [Source Code](https://github.com/xwiki/xwiki-platform)）LGPL-2.1 Java
- [Zim](https://zim-wiki.org/) - Graphical text editor used to maintain a collection of wiki pages. Each page can contain links to other pages, simple formatting and images. ([Source Code](https://github.com/zim-desktop-wiki/zim-desktop-wiki)）`GPL-2.0`` Python`

## Self-hosting Solutions

**[`^        back to top        ^`](#)**

- [1Backend](https://github.com/1backend/1backend)  -服务器上的自托管Web应用程序，微服务和Lambda. 高级功能可实现服务重用和组合.  AGPL-3.0`Go
- [Ansible-NAS](https://github.com/DaveStephens/ansible-nas)  -使用此剧本和Ubuntu盒构建功能齐全的家庭服务器. 麻省理工学院YAML / Docker
- [Bitsii Bridge](https://gitlab.com/bitsii/Bitsii/-/wikis/home)  ⚠-易于安装的Windows，MacOS和Linux自托管平台. 取决于动态DNS提供商和“让我们加密”.  （[Source Code](https://gitlab.com/edgii/BBridge)）`MPL-2.0``Java / Other`
- [CharjaBox](https://github.com/CherryKitten/CharjaBox)  -使用Docker的高度可配置的基于Ansible的Homeserver设置.  `GPL-3.0``YAML / Ansible / Docker`
- [DietPi](http://dietpi.com/)  -针对单板计算机进行了优化的最小Debian OS，使您可以轻松地安装和管理在家自托管的多种服务.  （[Source Code](https://github.com/Fourdee/DietPi)）`GPL-2.0``Shell`
- [DockSTARTer](https://dockstarter.com/)  -DockSTARTer可帮助您开始在Docker中运行的家庭服务器应用程序.  （[Source Code](https://github.com/GhostWriters/DockSTARTer)）`带壳`
- [DPlatform](https://dfabric.github.io/DPlatform-Shell/)  -轻松部署自托管应用程序：简单，轻松，独立的安装.  （[Source Code](https://github.com/j8r/DPlatform)）`带壳`
- [FLAP](https://www.flap.cloud)  -低维护框架，可管理自托管服务.  （[Source Code](https://gitlab.com/flap-box/flap)）`AGPL-3.0``Docker / Shell`
- [FreedomBone](https://freedombone.net/)  -基于Debian的家庭服务器配置.  （[Source Code](https://code.freedombone.net/bashrc/freedombone)）`AGPL-3.0``Shell`
- [FreedomBox](https://freedomboxfoundation.org/)  -社区项目，用于开发，设计和推广运行用于私人，个人，通信的免费软件的个人服务器.  （[Source Code](https://salsa.debian.org/freedombox-team/freedombox)）`AGPL-3.0``Python / Other`
- [FreeNAS](https://www.freenas.org/)  -基于FreeBSD和OpenZFS文件系统的网络附加存储（NAS）软件. 支持SMB，AFP，NFS，iSCSI，SSH，rsync和FTP / TFTP协议. 高级功能包括全盘加密和插件.  （[Source Code](https://github.com/freenas/freenas)）`BSD-3-Clause``Python / Other`
- [HomelabOS](https://homelabos.com)  -您自己的离线优先，以隐私为中心的开源数据中心. 使用一些命令部署100多种服务.  （[Source Code](https://gitlab.com/NickBusey/HomelabOS)）`与`Docker`
- [NextCloudPi](https://nextcloudpi.com/)  -预安装和预配置了Nextcloud，具有文本和Web管理界面以及自托管私有数据所需的所有工具. 带有用于Raspberry Pi，Odroid，Rock64，Docker的安装映像，以及用于Armbian / Debian的curl安装程序.  （[Source Code](https://github.com/nextcloud/nextcloudpi)）`GPL-2.0或更高版本``Bash / PHP`
- [OpenMediaVault](http://www.openmediavault.org/)  -OpenMediaVault是基于Debian Linux的下一代网络附加存储（NAS）解决方案. 它包含SSH，（S）FTP，SMB / CIFS，DAAP媒体服务器，RSync，BitTorrent客户端等服务.  （[Source Code](https://github.com/openmediavault/openmediavault)）`GPL-3.0``PHP`
- [Sandstorm](https://sandstorm.io/)  -用于轻松，安全地运行自托管应用程序的个人服务器.  （[Demo](https://demo.sandstorm.io/), [Source Code](https://github.com/sandstorm-io/sandstorm)）`Apache-2.0``C ++ / Other`
- [sovereign](https://github.com/sovereign/sovereign)  -用于构建和维护自己的私有云的Ansible剧本集：电子邮件，日历，联系人，文件同步，IRC保镖，VPN等.  `GPL-3.0``YAML /其他`
- [Syncloud](https://syncloud.org/)  -您自己的在线文件存储，社交网络或电子邮件服务器.  （[Source Code](https://github.com/syncloud/platform)）`GPL-3.0``Python / Other`
- [UBOS](http://ubos.net/)  -在独立盒（个人服务器和IoT设备）上运行的Linux发行版. 应用程序的单命令安装和管理-Jenkins，Mediawiki，Owncloud，WordPress等，以及其他功能.  `GPL-3.0``Perl / Other`
- [WikiSuite](https://wikisuite.org)  -最全面，集成度最高的免费/自由/开源企业软件套件.  （[Source Code](https://wikisuite.org/Source-Code)）`多个`ClearOS`
- [xsrv](https://xsrv.readthedocs.io/)  -在您自己的服务器上安装和管理自托管的服务/应用程序.  （[Source Code](https://github.com/nodiscc/xsrv)）`GPL-3.0``Shell / Ansible`
- [YunoHost](https://yunohost.org/)  -服务器操作系统，旨在使每个人都可以访问自我托管.  （[Demo](https://yunohost.org/#/try), [Source Code](https://github.com/YunoHost)）`AGPL-3.0``Python / Other`

<!-- END SOFTWARE LIST -->

--------------------

## List of Licenses

**[`^        back to top        ^`](#)**

-`⚠`-取决于用户无法控制的专有服务
-`0BSD`- [BSD Zero-Clause Licence](https://opensource.org/licenses/0BSD)
-`AAL`- [Attribution Assurance License](https://opensource.org/licenses/AAL)
-`AGPL-3.0`- [GNU Affero General Public License 3.0](https://www.gnu.org/licenses/agpl-3.0)
-`仅限AGPL-3.0`- [GNU Affero General Public License 3.0 only](https://spdx.org/licenses/AGPL-3.0-only.html)
-`Apache-2.0`- [Apache, Version 2.0](http://www.apache.org/licenses/)
-`APSL-2.0`- [Apple Public Source License, Version 2.0](https://opensource.org/licenses/APSL-2.0)
-`Artistic-2.0`- [Artistic License Version 2.0](http://opensource.org/licenses/Artistic-2.0)
-`Beerware`-- [Beerware License](https://spdx.org/licenses/Beerware.html)
-`BSD-2-Clause`- [BSD 2-clause "Simplified"](https://opensource.org/licenses/BSD-2-Clause)
-`BSD-2-Clause-FreeBSD`- [BSD 2-Clause FreeBSD License](https://www.freebsd.org/copyright/freebsd-license.html)
-`BSD-3-Clause`- [BSD 3-Clause "New" or "Revised"](https://opensource.org/licenses/BSD-3-Clause)
-`BSD-3-Clause-Attribution`- [BSD with attribution](https://fedoraproject.org/wiki/Licensing/BSD_with_Attribution)
-`CC-BY-NC-SA-3.0`- [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 International License](https://creativecommons.org/licenses/by-nc-sa/3.0/)
-`CC-BY-SA-3.0`- [Creative Commons Attribution-ShareAlike 3.0 International License](https://creativecommons.org/licenses/by-sa/3.0/)
-`CC-BY-SA-4.0`- [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)
- `CC0-1.0` - [Public Domain](https://creativecommons.org/about/cc0/)
-`CDDL-1.0`- [Common Development and Distribution License](https://opensource.org/licenses/CDDL-1.0)
-`CECILL-B`- [CEA CNRS INRIA Logiciel Libre](https://spdx.org/licenses/CECILL-B.html)
-`CPAL-1.0`- [Common Public Attribution License Version 1.0](http://opensource.org/licenses/CPAL-1.0)
-`DPL`- [Devblocks Public License 1.0](https://cerb.ai/license/)
-`ECL-2.0`- [Educational Community License, Version 2.0 ](http://opensource.org/licenses/ECL-2.0)
-`EPL-1.0`- [Eclipse Public License, Version 1.0](https://www.eclipse.org/legal/epl-v10.html)
-`EPL-2.0`- [Eclipse Public License, Version 2.0](https://www.eclipse.org/legal/epl-v20.html)
-`EUPL-1.2`- [European Union Public License 1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-11-12)
-`仅限GFDL-1.1`- [GNU Free Documentation License v1.1](https://spdx.org/licenses/GFDL-1.1-only.html)
-`GFDL-1.1或更高版本- [GNU Free Documentation License v1.1](https://spdx.org/licenses/GFDL-1.1-or-later.html)
-`仅限GFDL-1.2`- [GNU Free Documentation License v1.2](https://spdx.org/licenses/GFDL-1.2-only.html)
- `GFDL-1.2-or-later` - [GNU Free Documentation License v1.2](https://spdx.org/licenses/GFDL-1.2-or-later.html)
- `GFDL-1.3-only` - [GNU Free Documentation License v1.3](https://spdx.org/licenses/GFDL-1.3-only.html)
-`GFDL-1.3或更高版本- [GNU Free Documentation License v1.3](https://spdx.org/licenses/GFDL-1.3-or-later.html)
-`GPL-1.0`- [GNU General Public License](https://www.gnu.org/licenses/gpl-1.0)
-`GPL-2.0`- [GNU General Public License 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
-`GPL-2.0或更高版本- [GNU General Public License v2.0 or later](https://spdx.org/licenses/GPL-2.0-or-later.html)
-`仅限GPL-3.0`- [GNU General Public License v3.0 only](https://spdx.org/licenses/GPL-3.0-only.html)
-`GPL-3.0或更高版本- [GNU General Public License v3.0 or later](https://spdx.org/licenses/GPL-3.0-or-later.html)
-`GPL-3.0`- [GNU General Public License 3.0](http://www.gnu.org/licenses/gpl-3.0.en.html)
-`IPL-1.0`- [IBM Public License](https://opensource.org/licenses/IPL-1.0)
-`ISC`- [Internet Systems Consortium License](https://www.isc.org/downloads/software-support-policy/isc-license/)
- `LGPL-2.1` - [Lesser General Public License 2.1](http://opensource.org/licenses/LGPL-2.1)
-LGPL-3.0`- [Lesser General Public License 3.0](http://opensource.org/licenses/LGPL-3.0)
-`WITH`- [MIT License](http://opensource.org/licenses/MIT)
-``MPL-1.1&#39;&#39;- [Mozilla Public License Version 1.1](https://www.mozilla.org/media/MPL/1.1/index.txt)
-``MPL-2.0&#39;&#39;- [Mozilla Public License](https://www.mozilla.org/MPL/2.0/index.txt)
-`Multiple`-各种不同的许可证，用于项目软件的不同组件.
-`OSL-3.0`- [Open Software License 3.0](https://opensource.org/licenses/osl-3.0.php)
-`Other`-非标准许可证，通常是项目本身独有的.
-`Sendmail`-- [Sendmail License](https://www.sendmail.com/pdfs/open_source/sendmail_license.pdf)
-`SSPL-1.0`- [Server Side Public License](https://spdx.org/licenses/SSPL-1.0.html)
-`无证`- [The Unlicense](http://unlicense.org/)
-`WTFPL`- [Do What the Fuck You Want to Public License](http://www.wtfpl.net/about/)
-`Zlib`- [Zlib/libpng License](https://opensource.org/licenses/Zlib)
-`ZPL-1.2`- [Zope Public License 1.2](http://zpl.pub/page/zplv12)
-`ZPL-2.0`- [Zope Public License 2.0](http://opensource.org/licenses/ZPL-2.0)

--------------------

## External links

**[`^        back to top        ^`](#)**

- [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata) -精选的很棒的大数据框架，资源和其他很棒的清单.
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) -高质量，以主题为中心的公共数据源列表.
- [Awesome Sysadmin](https://github.com/n1trux/awesome-sysadmin) -精选的令人赞叹的开源sysadmin资源列表.
-以某种形式针对隐私和权力下放的软件列表： [PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](http://libreprojects.net/)
-动态域名服务： [Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
-社区/论坛： [/r/selfhosted](https://www.reddit.com/r/selfhosted), [IndieWeb](https://indieweb.org/)
镜子 [GitHub.com](https://github.com/awesome-selfhosted/awesome-selfhosted), [Gitlab.com](https://gitlab.com/awesome-selfhosted/awesome-selfhosted)

--------------------

## Contributing

可以在以下位置找到贡献准则 [https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/.github/CONTRIBUTING.md](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/.github/CONTRIBUTING.md).

## Authors

可以在以下位置找到作者列表 [https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/AUTHORS.md](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/AUTHORS.md).

## License

此列表位于 [Creative Commons Attribution-ShareAlike 3.0 Unported](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/LICENSE) 执照.
