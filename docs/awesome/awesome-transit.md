## awesome-transit [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![RSS](https://img.shields.io/badge/Subscribe-RSS-blue.svg)](https://github.com/CUTR-at-USF/awesome-transit/commits/master.atom)

##### Community list of transit APIs, apps, datasets, research, and software :bus::star2::train::star2::steam_locomotive:

Have something to add or change? Open a [pull request](https://github.com/CUTR-at-USF/awesome-transit/pulls) or [issue](https://github.com/CUTR-at-USF/awesome-transit/issues).

------------------------------

### Table of Contents

- [Getting started](#getting-started)
- [Community](#community)
- [Data](#data)
- [Software for Creating APIs](#software-for-creating-apis)
- [Agency Tools](#agency-tools)
- [Hardware](#hardware)
- [Apps](#apps)
  - [Web Apps](#web-apps)
  - [Native Apps (open source)](#native-apps-open-source)
  - [Native Apps (closed source)](#native-apps-closed-source)
- [Visualizations](#visualizations)
- [GTFS](#gtfs)
  - [GTFS Libraries](#gtfs-libraries)
  - [GTFS Converters](#gtfs-converters)
  - [GTFS Data Collection and Maintenance Tools](#gtfs-data-collection-and-maintenance-tools)
  - [GTFS Analysis Tools](#gtfs-analysis-tools)
  - [GTFS Timetable Publishing Tools](#gtfs-timetable-publishing-tools)
  - [GTFS Validators](#gtfs-validators)
- [GTFS Realtime](#gtfs-realtime)
  - [GTFS Realtime Libraries & Demo Apps](#gtfs-realtime-libraries--demo-apps)
  - [GTFS Realtime Validators](#gtfs-realtime-validators)
  - [GTFS Realtime (and Other Real-time API) Archival Tools](#gtfs-realtime-and-other-real-time-api-archival-tools)
  - [GTFS Realtime Convertors](#gtfs-realtime-convertors)
  - [GTFS Realtime Utilities](#gtfs-realtime-utilities)
- [SIRI](#siri)
- [Other multimodal data formats](#other-multimodal-data-formats)
- [Resources](#resources)

### Getting started

如果这是您第一次处理公交数据，您可能会发现这些链接很有用：

- [GTFS](https://developers.google.com/transit/gtfs/)   -  GTFS订阅源是一组文本文件，包含不常更改的传输数据，如停靠点，路线，行程和其他计划数据.  过境代理商通常每隔几个月更新一次GTFS Feed.
- [GTFS Realtime](https://developers.google.com/transit/gtfs-realtime/)   -  GTFS Realtime由三个二进制文件组成，包含实时车辆位置，实时到达信息和服务警报.  运输代理商通常每分钟更新这些文件.
- [TransitFeeds](https://transitfeeds.com/)   - 来自世界各地的GTFS / GTFS实时数据源列表.  如果您正在尝试获取某个代理机构的实时数据，那么这是一个很好的起点.
- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) - 一个免费的，在线的，自定进度的课程，用于学习GTFS和GTFS实时.
- [Open Transit Data Toolkit](http://transitdatatoolkit.com/) - 一系列帮助人们利用公开数据的课程.


### Community

提出问题和寻找其他社区资源的地方.

- [TransitWiki](http://transitwiki.org)   - 交通规划者的社区维基.  像这个回购，但更好.
- [GTFS Slack chat](http://gtfs.herokuapp.com/)
- [Transit Developers mailing list](https://groups.google.com/forum/#!forum/transit-developers)
-  OneBusAway
  - [OneBusAway User mailing list](http://groups.google.com/group/onebusaway-users)
  - [OneBusAway Developers mailing list](http://groups.google.com/group/onebusaway-developers)
  - [OneBusAway API mailing list](http://groups.google.com/group/onebusaway-api)
  - [OneBusAway Slack chat](https://onebusaway.herokuapp.com/)
- [Transit Techies NYC](https://www.meetup.com/Transit-Techies-NYC/) - 对于那些对此回购感兴趣的人，可以参加纽约市的聚会. [Speaker list](https://github.com/tyleragreen/transit-techies-nyc) 包括这个回购的许多贡献者.

### Data

可以访问GTFS和其他运输和多式联运数据集合的地方

#### 3rd party GTFS URL directories
- [Transitland](https://transit.land/)   - 许多公交机构GTFS数据集的社区可编辑列表.  还提供了一个API来访问数据作为JSON / GeoJSON和一个试验数据的游乐场.
- [TransitFeeds](http://transitfeeds.com/) - List of GTFS 和 [GTFS-RT](http://transitfeeds.com/search?q=gtfsrt) feeds. [Archives 和 validates](http://transitfeeds.com/p/capital-metro/24) GTFS提供并允许您预览两者 [GTFS](http://transitfeeds.com/p/capital-metro/24/20151015) 和 [GTFS-RT](http://transitfeeds.com/p/capital-metro/495) 通过浏览器.
- [~~GTFS Data Exchange~~ (Deprecated)](http://www.gtfs-data-exchange.com/agencies)   - 以前是GTFS供稿网址的权威目录.  2016年停产.但可根据要求提供2008年至2016年的93 GB数据.

#### Transit agency data archives
- [CapMetrics](https://github.com/scascketta/CapMetrics)   - 奥斯汀交通局（CapMetro）的历史车辆位置.  数据收集 [capmetricsd](https://github.com/scascketta/capmetricsd)，一个Go守护进程.

#### U.S. Federal Government
- [National Transit Database](https://www.transit.dot.gov/ntd) - 由联邦运输管理局运营的关于美国运输系统的信息和统计数据.

#### Proprietary (non-standard) vendor APIs
- [Transport API](https://www.transportapi.com/)   - 针对英国的聚合传输数据的REST API.  收费的访问.
- [TransLoc OpenAPI](https://market.mashape.com/transloc/openapi-1-2) -  REST API，用于购买TransLoc AVL硬件和软件的美国60多个交通系统的实时车辆，路线，停靠和到达数据.
- [NextBus API](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) -  REST API，用于购买NextBus硬件和/或软件的代理商的实时车辆，路线，停靠和到达数据.
- [Navitia.io](http://www.navitia.io/) - 针对美国和欧盟的旅程规划，停止时间表，同步等方面的REST API. [Navitia](https://github.com/CanalTP/navitia) 是实时API背后的开源引擎.
- [CityBikes](http://api.citybik.es) - REST API for aggregated bikeshare data from around the world. Powered by [pyBikes](https://github.com/eskerda/pybikes).

### Software for Creating APIs

Software that you can set up to provide an API to transit and multimodal data.

- [OneBusAway](http://onebusaway.org/) - 使用GTFS和GTFS-Realtime的Java应用程序（以及 [other formats](https://github.com/OneBusAway/onebusaway-application-modules/wiki/Real-Time-Data-Configuration-Guide)）并将它们变成易于使用 [REST API](http://developer.onebusaway.org/modules/onebusaway-application-modules/current/api/where/index.html).
- [OpenTripPlanner](http://www.opentripplanner.org/) - 用于多模式和多机构旅程规划的开源平台，以及返回有关多模态图的信息（使用GTFS等数据源） [OpenStreetMap](http://www.openstreetmap.org/)).
- [TransitClock](http://thetransitclock.org)   -  Java应用程序，可以使用原始车辆位置并以GTFS实时等格式生成预测时间.  以前称为“过境时期”.
- [Linked Connections](http://linkedconnections.org/)   - 开源，可扩展的联运路线规划引擎，允许客户执行路线规划算法（与服务器相对）.  使用GTFS数据.
- [TransiCast](http://www.transicast.com/) - Provides public transportation data for North America in a single, integrated call and response format. The data is provided in stream-parsable XML and JSON formats.  Open-source on [Google Code](https://code.google.com/archive/p/rasa/).  Hosted version at www.transitcast.com [requires payment](http://www.transicast.com/coststructure.html).
- [gtfs-server](https://github.com/denysvitali/gtfs-server) - 一个用Rust编写的Web服务器，它使用PostGIS作为后端，通过HTTP端点提供GTFS数据
- [Navitia](https://github.com/CanalTP/navitia) 是开源背后的开源引擎 [Navitia.io](http://www.navitia.io/) 实时API.
- [pyBikes](https://github.com/eskerda/pybikes) - Software powering [CityBikes](http://api.citybik.es) 全球自行车共享系统信息

### Agency Tools

 运输代理商的工具.  也可以看看 [GTFS Tools](#gtfs-tools) 用于特定于GTFS的工具.

- [Remix](http://getremix.com/) - 一个允许公交机构轻松规划路线的网络应用程序.
- [AC Transit RestroomFinder](https://github.com/actransitorg/ACTransit.RestroomFinder) - 使用GPS和屏幕地图，为公交运营商和现场工作人员确定最近的授权洗手间.
- [AC Transit Training and Education Department (TED) application](https://github.com/actransitorg/ACTransit.Training) - 该应用程序支持学区对运输和维护员工的培训操作，主要是公交运营商和重型教练机构（学徒和旅程），尽管该系统支持新课程和学徒计划.
- [AC Transit Customer Relations application (CusRel)](https://github.com/actransitorg/ACTransit.CusRel) - 用于客户问题和反馈的公共交通票务系统：具有通知的跨部门路由，部门/人员分配，简单工作流程，票证搜索，预先报告，每日提醒等.
- [TransAM](http://camsys.software/products/transam)   - 公共交通机构的开源资产管理平台.  开源 [on Github](https://github.com/camsys/transam_core).
- [RidePilot](https://github.com/camsys/ridepilot) - 开源计算机辅助调度和调度（CASD）软件系统，以满足小规模人类服务运输机构的需求（更多信息，请参阅 [Cambridge Systematics's marketing site](http://camsys.software/products/ridepilot)).
- [TNExT](https://github.com/ODOT-PTS/TNExT) -  Transit Network Explorer Tool（TNExT）是一个基于网络的软件工具，用于俄勒冈州区域和全州交通网络的可视化，分析和报告.

### Hardware

Experimental and production transit hardware.

- [Bus Tracking GPS](https://github.com/herrdragon/busTrackingGps) - 迈阿密原型代码，用于跟踪公交车的廉价开源解决方案.

### Apps

人们在过境时使用的应用.

#### Web Apps

- [TransitScreen](http://transitscreen.com/) - 自定义实时显示所有当地交通选择
- [Instabus](http://instabus.org)   - 奥斯汀（CapMetro）公共交通的实时地图.  根本没有服务器/后端依赖，并且完全在GitHub页面上运行.
- [Maryland MTA Real-time Vehicle Tracking](http://realtimemap.mta.maryland.gov/hiwire?.a=iRealTimeDisplay)
- [OpenTripPlanner Client GWT](https://github.com/mecatran/OpenTripPlanner-client-gwt) - 适用于OpenTripPlanner的基于Google Web Toolkit的Web界面
- [OpenTripPlanner.js](https://github.com/conveyal/otp.js) - 一个基于Javascript的OpenTripPlanner客户端
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - 用于生成GTFS实时服务警报的基于Java的Web应用程序.
- [HRT BUS Web app](https://github.com/Code4HR/hrt-bus-api) -  HRT Bus API通过应用程序编程接口发布Hampton Roads Transit的实时总线数据，供开发人员使用它制作应用程序.
- [Transit-Map](https://github.com/vasile/transit-map) - 使用公共交通时间表在地图上动画车辆（标记）的Web应用程序，以沿路线（折线）插入其位置.
- [Bikeshare Map](http://bikes.oobrien.com/) - 所有全球自行车共享站的状态
- [Bongo](http://ebongo.org)   - 爱荷华市，Coralville和爱荷华大学的实时过境跟踪.  很棒，因为它将三个不同的运输系统组合到一个UI中.
- [Transitive.js](https://github.com/conveyal/transitive.js) - 使用Leaflet或D3创建可自定义的公交路线Web地图图层.
- [Brand New Subway](http://jpwright.net/subway/) - 一种交互式交通规划游戏，可让玩家改变纽约地铁系统的内容.
- [CityMapper Webapp](https://citymapper.com/nyc) - 真正优化的webapp，包括30多个城市的旅行计划和路线状态.
- [Google I/O Transport Tracker](https://github.com/googlemaps/transport-tracker) - 根据开源信息显示Google I / O大会的班车到达时间 [transport-tracker project](https://github.com/googlemaps/transport-tracker) .  注意：要自己实现，需要一个 [Google Maps APIs Premium Plan license](https://developers.google.com/maps/pricing-and-plans/).
- [YourStop](http://yourstop.info)   - 移动友好的网络应用程序，它使用GTFS提要并显示停止的实时和预定旅行.  推出MBTA，YRT / Viva和Maryland MTA.
- [1-Click](http://camsys.software/products/1-click)   - 虚拟“旅行聚合器”，汇集各种可用模式的信息：公共交通，私人，铁路，乘坐共享，拼车，志愿者，辅助客运，步行和骑自行车.  开源 [on Github](https://github.com/camsys/oneclick).
- [Bustime](https://www.bustime.ru) - 使用WebSocket更新进行公共交通实时监控.

#### Native Apps (open source)

-  OneBusAway应用程序 -  [Android](https://play.google.com/store/apps/details?id=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [Fire Phone](http://www.amazon.com/gp/mas/dl/android?p=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [iOS](https://itunes.apple.com/us/app/onebusaway/id329380089)  [*(source code)*](https://github.com/OneBusAway/onebusaway-iphone), [Windows Phone](https://www.microsoft.com/en-us/store/apps/onebusaway/9nblggh0cbd9) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows-phone), [Windows 8](https://www.microsoft.com/en-us/store/apps/onebusaway/9wzdncrdm5pc) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows8), [Google Glass GDK](https://github.com/OneBusAway/onebusaway-android/pull/219) [*(source code)*](https://github.com/OneBusAway/onebusaway-android/pull/219)
- [OpenTripPlanner Android](https://github.com/CUTR-at-USF/OpenTripPlanner-for-Android/wiki) - 适用于Android的Android应用 [OpenTripPlanner](http://www.opentripplanner.org/)
- [OpenTripPlanner iOS](https://github.com/opentripplanner/OpenTripPlanner-iOS) - 一个iOS应用程序 [OpenTripPlanner](http://www.opentripplanner.org/)
- [Transportr](https://github.com/grote/Transportr) 一款使用的Android应用 [public-transport-enabler](https://github.com/schildbach/public-transport-enabler) 为了连接到全球许多不同的传输网络.
- [Offi Directions](https://gitlab.com/oeffi/oeffi) - 一款Android应用程序，为欧洲及其他地区的运输当局提供旅行计划，时间表，实时出发时间和中断信息.

#### Native Apps (closed source)

- [ally](http://www.allyapp.com/)
- [Transit](http://transitapp.com/)
- [CityMapper](https://citymapper.com/)
- [Moovit](http://moovitapp.com/)
- [Tiramisu Transit](http://www.tiramisutransit.com/)
- [TransLoc Rider](http://translocrider.com/) - 超过100个运输系统的实时过境地图.
- [Transit Display](http://transitdisplay.com/) - 多模式和实时传输显示软件.

### Visualizations

- [Visualizing MBTA Data](http://mbtaviz.github.io/) - Interactive graphs that show how people use Boston's subway system.
- [MIT COAXS](http://mittransportanalyst.github.io/) - Co-creative Planning of Transit Corridors using Accessibility-Based Stakeholder Engagement (shows route scenarios using [OpenTripPlanner Analyst](http://www.opentripplanner.org/analyst/)).
- [TRAVIC Transit Visualization Client](http://tracker.geops.ch/)   - 可视化基于静态GTFS数据（有时是实时数据）移动的车辆.  支持260多个城市.  GeOps组织的Github帐户是 [here](https://github.com/geops).
- [Muni, this moment](http://allthebuses.com/) - 旧金山所有巴士的实时地图.
- [MTA Frequency](http://www.tyleragreen.com/maps/new_york/) - 使用建造的纽约市地铁和公共汽车的频率可视化 [Transitland](https://transit.land/).
- [Traze](https://traze.app/) 通过 [Veridict](https://www.veridict.com)   - 可视化来自世界各地的公共交通工具.  与其他用户协作即使在代理商无法获得实时更新时也能获得实时更新.  基于许多来源，包括GTFS和GTFS-RT.  （以前称为 [Livemap24](https://www.livemap24.com)). 
- [Graphs in Transit](https://gtfs-graph.herokuapp.com/) - 在纽约市，波士顿和巴黎的快速公交网络上显示的图表中心度量标准. 
- [SEPTA Rail OTP Report](https://github.com/fulldecent/septa-regionalrail-otp) - 使用GTFS的在线准时性能修复和下钻工具.
- [TransitFlow](https://github.com/transitland/transitland-processing-animation) 使用Processing和Transitland为全球的GTFS数据制作动画.
- [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz) - 使用的动画和可视化GTFS数据的Web应用程序 [gtfspy](https://github.com/CxAalto/gtfspy).
- [Mapnificent](https://www.mapnificent.net/) - Shows areas you can reach with public transport in a given time. Open-source [on GitHub](https://github.com/mapnificent/mapnificent)，住在https://www.mapnificent.net/.
- [Toronto Transit Explorer](https://github.com/sidewalklabs/totx)   - 一个Java应用程序，可以显示多伦多市的公交，自行车和步行可达性.  实时版本托管 [here](https://totx.sidewalklabs.com/) .  使用修改后的版本 [R5](https://github.com/conveyal/r5) 用于路由.
- [fastest-bus-analysis-in-the-west](https://github.com/vta/fastest-bus-analysis-in-the-west)   - 一个python Pandas脚本，结合Ridership / APC，Swiftly速度和驻留数据，公交车站库存，GTFS和地理空间形状，通过停止，路线路径，时间分组可过滤数据集进行交叉分析.  然后可视化数据集 [Tableau](https://public.tableau.com/profile/vivek7797#!/vizhome/stopsandspeedanalyses/Story1) 帮助VTA规划人员通过加速方法（如停止整合和专用车道）找到更快，更可靠的公交和铁路网络的地方.
- [TNExT](https://github.com/ODOT-PTS/TNExT) -  Transit Network Explorer Tool（TNExT）是一个基于网络的软件工具，用于俄勒冈州区域和全州交通网络的可视化，分析和报告.

### GTFS

- [GTFS Spec](https://developers.google.com/transit/gtfs/) - Specification for the General Transit Data Feed, or GTFS. Also available in [Español](https://developers.google.com/transit/gtfs/?hl=es), [Français](https://developers.google.com/transit/gtfs/?hl=fr).
- [GTFS Best Practices](http://gtfs.org/best-practices/) -  GTFS Feed生产商的最佳实践.

#### GTFS Libraries

使用各种语言轻松使用GTFS数据的软件.

- [Mapzen GTFS](https://github.com/transitland/mapzen-gtfs) -  Python GTFS库，支持读取单个GTFS表，或构建图表以表示Feed中的每个代理.
- [gtfsdb](https://github.com/OpenTransitTools/gtfsdb) - Python library for converting GTFS files into a relational database.
- [OneBusAway GTFS Modules](https://github.com/OneBusAway/onebusaway-gtfs-modules/wiki) - A Java-based library for reading, writing, and transforming public transit data in the GTFS format, including database support.
- [GTFS to SQL](https://github.com/TransitFeeds/GtfsToSql) - 将GTFS提要解析为SQL数据库（用于 [TransitFeeds.com](http://transitfeeds.com/))
- [SQL to GTFS](https://github.com/TransitFeeds/SqlToGtfs) - 将使用“GtfsToSql”生成的SQLite文件转换回压缩的GTFS文件.
- [Go GTFS Parser](https://github.com/geops/gtfsparser) -  Go的GTFS解析库
- [GTFS Feed Parser](https://github.com/OsmSharp/GTFS) -  .Net / Mono实现GTFS解析器
- [Node-GTFS](https://github.com/brendannee/node-gtfs) - 从中​​加载传输数据 [GTFS Data Exchange](http://www.gtfs-data-exchange.com/)，解压缩并将其存储到MongoDB数据库，并提供一些查询代理，路由，停止和时间的方法.
- [GTFS-viz](https://github.com/vasile/GTFS-viz) -  Ruby脚本，将一组GTFS文件转换为SQLite数据库+ GeoJSONs（需要 [Transit Map](https://github.com/vasile/transit-map) Web应用程序）
- [gtfs-sequelize](https://github.com/evansiroky/gtfs-sequelize) - Node.js library modeling the static GTFS using [sequelize.js](http://sequelizejs.com/).
- [gtfslib-python](https://github.com/afimb/gtfslib-python) -  python中的一个开源库，用于读取GTFS文件并计算有关公共传输网络的各种统计数据和指标.
- [multigtfs](https://github.com/tulsawebdevs/django-multi-gtfs) - 用于导入和导出GTFS的Django应用程序
- [GTFSTK](https://github.com/araichev/gtfstk)   - 用于分析内存中GTFS数据的Python 3工具包.  使用Pandas和Shapely来提高速度.
- [gtfs-schema](https://github.com/tyleragreen/gtfs-schema) - 用于GTFS提要的PostgreSQL架构.
- [partridge](https://github.com/remix/partridge) - 基于pandas DataFrames的快速，宽容的Python GTFS阅读器.
- [gtfspy](https://github.com/CxAalto/gtfspy)   - 使用Python3进行公共交通网络分析和旅行时计算.  兼容Postgres / PostGIS，Oracle，MySQL和SQLite.  使用者 [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz).
- [RRRR Rapid Real-time Routing](https://github.com/bliksemlabs/rrrr) -  RRRR（通常发音为R4）是RAPTOR公共交通路由算法的C语言实现.
- [R5: Rapid Realistic Routing on Real-world and Reimagined networks](https://github.com/conveyal/r5)   - 用于多模式（公交/自行车/步行/汽车）网络的基于Java的路由引擎.  它目前计划在一个时间窗口内进行多次分析以进行分析，但最终可能会支持点对点旅程规划.
- [gtfsman](https://github.com/geops/gtfsman) -  Python中的类似存储库的工具，用于管理和更新大量GTFS源.
- [go gtfsparser](https://github.com/geops/gtfsparser) - 在Go中实现的GTFS解析库.
- [Make GTFS](https://github.com/mrcagney/make_gtfs) - 一个Python库，用于根据基本路径信息生成GTFS
- [trread](https://github.com/r-gtfs/trread) -  R的传输（GTFS）文件阅读器 

#### GTFS Converters

各种静态调度格式的转换器与GTFS之间的转换器.

- [Transmodel and IFF to GTFS](https://github.com/bliksemlabs/bliksemintegration)   - 进口和同步（Transmodel）BISON Koppelvlak1，IFF（HP / EDS编写的格式，有点类似于ATCO CIF）导入铁路网络的时间表.  内部伪NETeX数据结构允许导出到GTFS，并且有概念证明可以导出到其他格式，如NETeX，GTFS和IFF.
- [Open-Transport SYNTHESE Convertors](https://github.com/Open-Transport/synthese/wiki) - 转换法语 -  Transmodel，SIRI，NETeX，HAFAS，HASTUS，VDV452等.
- [Chouette](http://www.chouette.mobi/)   - 转换法语 -  Transmodel，SIRI，NETeX.  有关详细信息，请参阅Chouette.mobi网站.
- [osm2gtfs](https://github.com/grote/osm2gtfs) - 将OpenStreetMap数据和日程安排信息转换为GTFS.
- [GTFS-OSM-Sync](https://github.com/CUTR-at-USF/gtfs-osm-sync) - 用于以GTFS格式同步数据的Java工具 [OpenStreetMap.org](http://www.openstreetmap.org/).
- [onebusaway-gtfs-to-barefoot](https://github.com/OneBusAway/onebusaway-gtfs-to-barefoot) - 用于创建的Java工具 [Barefoot](https://github.com/bmwcarit/barefoot) 来自GTFS文件的mapfile.
- [o2g](https://github.com/hiposfer/o2g) - 从OpenStreetMap中提取GTFS提要的简单工具.
- [transloc-gtfs-rectifier](https://github.com/laidig/transloc-gtfs-rectifier) - 尝试将GTFS stop_ids分配给的Python应用程序 [TransLoc](http://transloc.com/) ID使用 [TransLoc's API](https://market.mashape.com/transloc/openapi-1-2) ([TransLoc](http://transloc.com/) 不在他们的API中提供GTFS`stop_ids`.
- [Hafas2GTFS](https://github.com/geops/hafas2gtfs) - 用Python编写的Hafas2GTFS转换器，针对SBB HAFAS源进行了优化.
- [gtsf](https://github.com/r-gtfs/gtsf) -  R中的一般传输（GTFS）简单（地理）特征（sf）可用于通过GDAL从GTFS转换为Shapefile，GeoJSON和其他格式. 

#### GTFS Data Collection and Maintenance Tools

- [bus-router](https://github.com/atlregional/bus-router) - 使用路由从GTFS生成缺少shapes.txt的Python脚本 [Google Maps Directions API](https://developers.google.com/maps/documentation/directions/) or [OSRM](https://github.com/Project-OSRM/osrm-backend/wiki/Server-api).
- [GTFS Editor](https://github.com/conveyal/gtfs-editor)  一个（自托管的）基于Web的GTFS编辑框架.  （注意：这个项目已经被弃用了 [Conveyal Data Tools](https://github.com/conveyal/datatools-ui).)
- [GTFS Editor for Vagrant](https://github.com/laidig/vagrant-gtfs-editor) 使用快速设置GTFS编辑器（上图） [Vagrant](https://www.vagrantup.com/)
- [static-GTFS-manager](https://github.com/WRI-Cities/static-GTFS-manager) - 一个（自托管的）基于浏览器的用户界面，用于创建，编辑和导出静态GTFS源（请参阅 [related post](https://groups.google.com/forum/#!topic/transit-developers/GFz5rTJTB0I) ）.  现场演示 [here](https://thawing-mountain-46422.herokuapp.com/).
- [TransitWand](http://transitwand.com/)   - 用于收集运输数据的开源Web和移动应用程序.  使用它来创建GTFS源，捕获乘客计数或生成GIS数据集.
- [Conveyal Data Tools](https://github.com/conveyal/datatools-ui)   - 处理GTFS编辑，验证，质量检查和部署到OpenTripPlanner的Web应用程序.  （结合并建立在不推荐使用的功能上 [Gtfs Data Manager](https://github.com/conveyal/gtfs-data-manager) 和 [GTFS Editor](https://github.com/conveyal/gtfs-editor).)
- [GTFS.html](https://gtfs.pleasantprogrammer.com)   - 一个完全基于浏览器的工具，用于查看GTFS供稿.  用它来查看路线，站点，时刻表等.
- [pfaedle](https://github.com/ad-freiburg/pfaedle) - 使用OpenStreetMap数据为GTFS进行精确的地图匹配

#### GTFS Analysis Tools

- [Peartree](https://github.com/kuanb/peartree) - 用于将传输数据转换为有向图以进行网络分析的Python库.
- [gtfsr](https://github.com/ropensci/gtfsr) - 一个R包，用于轻松导入，验证和映射遵循通用运输Feed规范（GTFS）格式的运输数据.
- [tidytransit](https://github.com/r-transit/tidytransit) （以前 [bustt](https://github.com/r-transit/bustt) ） - 将GTFS数据读入tidyverse和简单的特征数据帧，以映射运输站和路线，计算运输频率，并验证运输饲料.  tidytransit是一个 [fork](https://en.wikipedia.org/wiki/Fork_\(software_development\)） [gtfsr](https://github.com/ropensci/gtfsr)，发表到 [CRAN](https://cran.r-project.org/)，具有频率/车头时距计算功能. 
- [transitr](https://github.com/tmelliott/transitr) - 用于实时构建和建模公交网络以获得车辆ETA的R包

#### GTFS Timetable Publishing Tools

- [GTFS to HTML](https://github.com/BlinkTagInc/gtfs-to-html) -  A直接从GTFS传输数据创建HTML格式的人类可读，用户友好的传输时间表. 
- [TimeTablePublisher (TTPUB)](https://github.com/OpenTransitTools/ttpub) -  TriMet开发的Web发布系统，允许运输代理商检查，修改原始调度数据并将其转换为易于阅读的时间表，以供客户信息之用

#### GTFS Validators

- [feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) -  Google支持基于Python的GTFS验证器.
- [gtfs-validator](https://github.com/conveyal/gtfs-validator) - 基于OneBusAway GTFS模块的GTFS验证器，以Java运行，速度快于Google提供的验证器.
- [gtfs-lib](https://github.com/conveyal/gtfs-lib/) -  Conveyal的gtfs-validator的继承者，这是一个用于加载和保存任意大小的GTFS源和磁盘备份存储的库.
- [GTFS Data Package Specification](https://github.com/Stephen-Gates/GTFS) - 一个 [Data Package specification](http://specs.frictionlessdata.io/data-packages/) 完成验证 [Good Tables](http://goodtables.okfnlabs.org/) .  包括数据包，模式，测试，并以东南昆士兰GTFS数据为例.
- [Web GTFS Meta-Validator (hosted by Omni)](http://gtfsvalidator.omnimodal.io) - 运行两者的基于Web的GTFS验证器 [feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) 和 [gtfs-validator](https://github.com/conveyal/gtfs-validator) 上传的GTFS文件.

#### GTFS Realtime

- [GTFS-realtime documentation](https://github.com/google/transit/tree/master/gtfs-realtime) .  也有 [Español](https://github.com/google/transit/tree/master/gtfs-realtime/spec/es).
- [GTFS-realtime Autodoc](https://laidig.github.io/gtfs-rt-autodoc/index.html) - 自动生成的GTFS实时文档，由官方生成 [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto) 并包括一些扩展.

#### GTFS Realtime Libraries & Demo Apps

- [gtfs-realtime-bindings](https://github.com/google/gtfs-realtime-bindings) - 官方生成的Java，.NET，Node.js，Python和Ruby的官方绑定 [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto).
- [GTFS-realtime Exporter](https://github.com/OneBusAway/onebusaway-gtfs-realtime-exporter/wiki) - 基于Java的工具，可帮助生成和共享GTFS-relatime供稿.
- [GTFS-realtime Alerts Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-alerts-producer-demo/wiki) - A Java-based demo project for producing GTFS-realtime Service Alerts.
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - 用于生成GTFS实时服务警报的基于Java的Web应用程序.
- [GTFS-realtime TripUpdates & VehiclePositions Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-trip-updates-producer-demo/wiki) - 基于Java的演示项目，用于生成GTFS实时TripUpdates（估计到达次数）和车辆位置.
- [GTFS-realtime Vehicle Positions Consumer/Visualizer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-visualizer/wiki) - 基于Java的演示项目，用于使用GTFS实时车辆位置提要并在地图上显示此信息.

#### GTFS Realtime Validators

- [gtfs-realtime-validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator)   - 南佛罗里达大学城市交通研究中心开发的GTFS实时验证工具.  还包括一个集成版本 [gtfs-validator](https://github.com/conveyal/gtfs-validator) 工具.
- [Web gtfs-realtime-validator (hosted by TransitScreen)](http://gtfsrealtimevalidator.transitscreen.com/) - 托管版本 [gtfs-realtime-validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator).

#### GTFS Realtime (and Other Real-time API) Archival Tools

- [GTFS-realtime to SQL](https://github.com/TransitFeeds/GtfsRealTimeToSql) - 将GTFS-RealTime提要解析为SQL数据库（用于 [TransitFeeds.com](http://transitfeeds.com/))
- [gtfsrdb](https://github.com/CUTR-at-USF/gtfsrdb) - 支持将GTFS实时订阅源读取和归档到数据库中的Python工具
- [retro-gtfs](https://github.com/SAUSy-Lab/retro-gtfs) - 一个Python应用程序，它从Nextbus API收集实时数据并将其归档为GTFS格式（即回顾性GTFS）.

#### GTFS Realtime Convertors

- [SIRI 到GTFS实时](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) - 一个基于Java的命令行实用程序，用于转换 [SIRI format](http://user47094.vs.easily.co.uk/siri/) 到GTFS实时
- [OrbCAD SQL Server to GTFS-realtime](https://github.com/CUTR-at-USF/HART-GTFS-realtimeGenerator/) - 基于Java的命令行实用程序，可从OrbCAD SQL Server中提取车辆位置和行程更新信息，并将其导出为GTFS实时TripUpdates和VehiclePositions格式.
- [NextBus API to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-nextbus-cli/wiki) - 一个基于Java的命令行实用程序，用于转换 [NextBus API format](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf)  到GTFS实时.  请注意，NextBus现在直接为其产品提供GTFS实时API.  看到 [Cubic site](http://nextbus.cubic.com/Products/Real-Time-Rider-Information) 和 [this FAQ](https://medium.com/omnimodal/want-more-riders-open-up-your-nextbus-api-with-gtfs-realtime-7387c80f31e1#.pkuzizhl5).
- [Syncromatics API to GTFS-realtime](https://github.com/CUTR-at-USF/bullrunner-gtfs-realtime-generator) - 一个基于Java的命令行实用程序，用于转换 [Syncromatics API](http://www.syncromatics.com/) 格式化为GTFS实时TripUpdates和VehiclePositons.
- [KV6,15,17, and ARNU to GTFS-realtime](https://github.com/bliksemlabs/bliksemintegration-realtime) - Java-based tool to process incoming KV6,15,17 and ARNU and match them to static transit data present in a RID integration database. It then proceeds to export this data as ARNU RITinfo, GTFS(realtime) and KV78turbo
- [WMATA BusPositions API to GTFS-realtime](https://github.com/kurtraschke/wmata-gtfsrealtime) - 从WMATA转换的基于Java的工具 [BusPositions API](https://developer.wmata.com/docs/services/54763629281d83086473f231/operations/5476362a281d830c946a3d68) and Alert RSS feeds from [MetroAlerts](http://www.wmata.com/rider_tools/metro_service_status/rail_bus.cfm?) 到GTFS实时TripUpdates，VehiclePositions和Alerts供稿.
- [SEPTA API 到GTFS实时](https://github.com/kurtraschke/septa-gtfsrealtime) - 基于Java的转换工具 [SEPTA's](http://www.septa.org/) [real-time bus and rail data](http://www3.septa.org/hackathon/) 到GTFS实时
- [CTA API to GTFS-realtime](https://github.com/kurtraschke/ctatt-gtfsrealtime) - 基于Java的转换工具 [CTA's](http://www.transitchicago.com/) [Train Tracker data](http://www.transitchicago.com/developers/traintracker.aspx) 到GTFS实时.
- [Detroit DOT to GTFS-realtime](https://github.com/prashtx/ddot-avl) - 从中​​提取实时信息 [DDOT's](http://www.detroitmi.gov/How-Do-I/Locate-Transportation/Bus-Schedules) TransitMaster安装（数据库）并转换为GTFS实时
- [Live Transit Event Trigger](https://github.com/ipublic/live_transit_event_trigger) - 从中​​提取数据 [Ride On's](http://www.montgomerycountymd.gov/dot-transit/) OrbCAD database and export as GTFS-realtime.
- [SoundTransit 到GTFS实时](https://github.com/bdferris/onebusaway-sound-transit-realtime) - 转换文本文件源 [Sound Transit](http://www.soundtransit.org/) 到GTFS实时
- [Civic Transit](https://github.com/jestin/CivicTransit) - 屏幕刮擦 [KCATA’s](http://www.kcata.org/) TransitMaster WebWatch安装可生成GTFS实时源.
- [GTFS-realtime VehiclePositions to GTFS-realtime TripUpdates (TransitClock)](http://thetransitclock.org)   -  Java应用程序，可以使用原始车辆位置并以GTFS实时等格式生成预测时间.  以前称为“过境时期”.

#### GTFS Realtime Utilities

- [gtfs-rt-dump](https://github.com/kurtraschke/gtfs-rt-dump) - 将协议缓冲区格式转换为纯文本，以便以纯文本方式查看GTFS实时源（用于调试目的）
- [GTFS-realtime Printer](https://github.com/laidig/gtfs-rt-printer) 基于Java的实用程序，用于从GTFS实时文件或URL中打印出信息.
- [GTFS-realtime Munin Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-munin-plugin) - 提供一个 [Munin](http://munin-monitoring.org/) 用于记录有关GTFS实时源的信息的插件.
- [GTFS-realtime Nagio Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-nagios-plugin) - 提供一个 [Nagios](https://www.nagios.org/) 用于监控GTFS实时订阅源的插件
- [GTFS-realtime-test-service](https://github.com/CUTR-at-USF/gtfs-realtime-test-service) - 用于模拟GTFS实时馈送内容的工具（例如，用于测试GTFS实时消费应用程序）

### SIRI

- [SIRI API](https://github.com/OneBusAway/onebusaway/wiki/SIRI-Resources) - 从v1.0和v1.3生成的Java类 [SIRI](http://user47094.vs.easily.co.uk/siri/) 模式.
- [SIRI 2.0 API](https://github.com/laidig/siri-20-java) - 从v2.0生成的Java类 [SIRI](http://user47094.vs.easily.co.uk/siri/) 模式.
- [SIRI to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) - 一个基于Java的命令行实用程序，用于转换 [SIRI format](http://user47094.vs.easily.co.uk/siri/) 到GTFS实时.
- [SIRI 2.0 Autodoc](https://laidig.github.io/siri-20-java/doc/) - 从（令人难以置信的）带注释的SIRI 2.0模式定义中自动生成的文档.
- [King County Metro Legacy AVL to SIRI](https://github.com/bdferris/onebusaway-king-county-metro/tree/master/onebusaway-king-county-metro-legacy-avl-to-siri) - 基于Java的转换工具 [King County Metro's](http://metro.kingcounty.gov/) 传统的AVL格式到SIRI.
- [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki) - 一个开源的Android库，用于与RESTful SIRI接口进行交互，以获取实时传输数据，例如当前正在使用的数据. [MTA Bus Time API](http://bustime.mta.info/wiki/Developers/SIRIIntro).
- [SIRI 1.3 POJOs (Android-compatible)](https://github.com/CUTR-at-USF/onebusaway-siri-api-v13-pojos/wiki)   - 与Android兼容的Plain Old Java Objects（POJOS），用于SIRI v1.3 API的数据绑定（deserliazing XML / JSON）响应.  由...使用 [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki).
- [pysiri2validator](https://github.com/laidig/pysiri2validator) - 用Python 3编写的SIRI 2.0的简单验证器.

### Other multimodal data formats

- [GTFS-flex](https://github.com/MobilityData/gtfs-flex) - 将灵活的公共交通服务建模为GTFS扩展的数据格式.
- [NeTex](http://netex-cen.eu/) - 通用XML格式，用于在由...管理的分布式系统之间交换复杂的静态传输数据 [CEN standards process](https://www.cen.eu/work/ENdev/how/Pages/default.aspx).
- [General Bikeshare Feed Specification (GBFS)](https://github.com/NABSA/gbfs) - 由成员开发的实时自行车共享信息的开放数据标准 [North American Bikeshare Association (NABSA)](http://nabsa.net/).
    - [gbfs-validator](https://github.com/PierrickP/gbfs-validator) - 验证GBFS源的第三方工具.
- [GTFS-ride](https://github.com/ODOT-PTS/GTFS-ride) - 通过俄勒冈州交通部和俄勒冈州立大学合作开发的开放式固定路线交通乘客数据标准.
- [Managed and Tolled Lanes Feed Specification (MTLFS)](https://github.com/vta/Managed-and-Tolled-Lanes-Feed-Specification) - 建议包含托管和收费车道收费规范（MTLFS）的模式，并定义由所开发的所有文件中使用的字段 [Santa Clara Valley Transportation Authority](http://www.vta.org/).
- [GTFS-plus](https://github.com/osplanning-data-standards/GTFS-PLUS) - 基于GTFS的运输网络格式*车辆和容量数据*适用于由Puget Sound地区委员会，UrbanLabs LLC，LMZ LLC和旧金山县交通管理局开发的动态运输建模.
- [Dyno-Demand](https://github.com/osplanning-data-standards/dyno-demand) - 基于GTFS的旅行需求数据格式，侧重于个人乘客*需求*，适用于旧金山县交通管理局，LMZ LLC和UrbanLabs LLC开发的动态网络建模.
- [Dyno-Path](https://github.com/osplanning-data-standards/dyno-path) - （正在开发中 - 见 [this post](https://github.com/osplanning-data-standards/GTFS-PLUS/pull/52#issuecomment-331231000)）个别乘客*轨迹的数据*.
- [GTFS-stat](https://github.com/osplanning-data-standards/GTFS-STAT) -  GTFS公交网络的扩展，其中包含由UrbanLabs LLC和旧金山县交通管理局开发的性能数据的附加文件.
- [TIDES project](https://groups.google.com/forum/#!forum/tidesproject) -  Transit ITS数据交换规范（TIDES）旨在为历史传输ITS数据（包括AVL，APC和AFC数据）创建标准数据结构，API和数据管理工具.
- [SAE Shared and Digital Mobility Committee](http://articles.sae.org/15799/) - 似乎正在制定汽车共享和运输网络公司（TNCs）/ rideshare的数据标准.
- [City of Los Angeles Mobility Data Specification (MDS)](https://github.com/CityOfLosAngeles/mobility-data-specification)   - 实现市政当局的实时数据共享，测量和监管以及作为服务提供商的移动性的格式.  它旨在确保政府有能力执行，评估和管理提供者.
- [Alliance for Parking Data Standards (APDS)](https://www.allianceforparkingdatastandards.org/) - 由...形成 [International Parking Institute (IPI)](https://www.parking.org/)， [British Parking Association (BPA)](http://www.britishparking.co.uk/)，和 [European Parking Association (EPA)](http://www.europeanparking.eu/) ，APDS是一个非营利组织，其使命是开发，推广，管理和维护统一的全球标准，使组织能够跨全球平台共享停车数据.  APDS版本1.0文档是 [here](https://www.allianceforparkingdatastandards.org/resources).
- [Mobility as a Service API](http://maas-api.org/) - 一组开放文档和测试套件，用于定义与MaaS兼容的API（例如，a [MaaS Transport Service Provider Booking API](https://github.com/maasglobal/maas-tsp-api/blob/master/specs/Booking.md)).
- [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120)   - 本研究的目的是为参与提供需求响应运输的实体制定交易数据的技术规范.  预计完成日期为2018年底.
- [NCHRP 08-119 Developing Data Standards and Guidance for Transportation Planning and Traffic Operations - Phase 1 (Anticipated)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4543) - 该研究的目的是制定运输社区在收集，管理和共享运输规划和运营的静态和实时数据时使用和采用的标准和/或指南.

### Resources

On-line courses, blog posts, and reports related to open transit data.

#### On-line courses

- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) - 一个免费的，在线的，自定进度的课程，用于学习GTFS和GTFS实时.
- [Open Transit Data Toolkit](http://transitdatatoolkit.com/) - 一系列帮助人们利用公开数据的课程.

#### Blog posts

- [When(ish) is my bus? Data and code](https://github.com/mjskay/when-ish-is-my-bus)   -  Whenish背后的数据和代码（R）是我的公共汽车？  数据包括三天的历史车辆位置和调查结果.
- ["Legacy AVL system? It's okay, join the club." by Kurt Raschke](https://kurtraschke.com/2015/01/legacy-avl-export) - Discussion of options for transforming legacy AVL system data into the GTFS-realtime format.
- ["GTFS Best Practices now available!" by Sean Barbeau](https://medium.com/@sjbarbeau/gtfs-best-practices-now-available-88ac67194233) - 讨论2017年初推出的开放数据格式（如GTFS和GTFS最佳实践）的一些挑战，以帮助解决数据质量问题.
- ["What's new in GTFS-realtime v2.0" by Sean Barbeau](https://medium.com/@sjbarbeau/whats-new-in-gtfs-realtime-v2-0-cd45e6a861e9) - 讨论GTFS-realtime v1.0的不足之处以及v2.0的改进.
- ["AVL, CAD, and Real-Time Passenger Info for Beginners" by Tony Laidig](http://transitdata.net/avl-cad-and-real-time-passenger-info-for-beginners/) - 提供用于跟踪车辆的技术的一般介绍.

#### Academic papers

- [Tang et al. - "Ridership effects of real-time bus information system: A case study in the City of Chicago"](https://www.sciencedirect.com/science/article/pii/S0968090X12000022) - 伊利诺伊州芝加哥的实验表明，当乘客通过短信或电子邮件访问实时信息时，乘客量会有适度增加.
- [Kay et al. - "When(ish) is my bus? User-centered Visualizations of Uncertainty in Everyday, Mobile Predictive Systems"](http://faculty.washington.edu/jhullman/busUncertaintyVis.pdf)   - 论文试图回答“我们如何在过境预测中传达不确定性？”的问题.  解释问题，现有解决方案和设计a [better interface for letting users know when to arrive at the bus stop](https://github.com/mjskay/when-ish-is-my-bus/blob/master/quantile-dotplots.md#quantile-dotplots).
- [Watkins et al. - "Where Is My Bus? Impact of mobile real-time information on the perceived and actual wait time of transit riders"](https://www.sciencedirect.com/science/article/pii/S0965856411001030) - 西雅图Seattl的实验表明，当乘客通过移动应用程序访问实时信息时，他们会感觉到公交车等待时间缩短.
- [Brakewood et al. - “An experiment evaluating the impacts of real-time transit information on bus riders in Tampa, Florida”](https://www.sciencedirect.com/science/article/pii/S0965856414002146)   - 位于佛罗里达州坦帕市的受控实验表明，与没有实时信息的车手相比，通过移动应用程序访问实时信息的车手感觉等待时间减少了近2分钟.  具有实时信息的车手也减少了焦虑和沮丧以及更好地接受代理.
- [Brakewood et al. - "The impact of real-time information on bus ridership in New York City"](https://www.sciencedirect.com/science/article/pii/S0968090X15000297) - 纽约市的实验表明，当车手可以获得实时信息时，长途航线的乘客量会增加.

#### Government reports
- [APTA Policy Development and Research - Public Transportation Embracing Open Data](http://www.apta.com/resources/reportsandpublications/Documents/APTA-Embracing-Open-Data.pdf) - 亚太贸易协定关于公开数据的益处和挑战的讨论（以下TCRP报告的简短摘要）.
- [TCRP Synthesis 115 - Open Data: Challenges and Opportunities for Transit Agencies](http://onlinepubs.trb.org/Onlinepubs/tcrp/tcrp_syn_115.pdf) - 全面的报告，研究公开数据的好处和挑战.
- [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120)   - 本研究的目的是为参与提供需求响应运输的实体制定交易数据的技术规范.  预计完成日期为2018年底.

#### Community-maintained lists
- [Vendors Providing GTFS Creation/Maintenance services](https://docs.google.com/spreadsheets/u/1/d/1Gc9mu4BIYC8ORpv2IbbVnT3q8VQ3xkeY7Hz068vT_GQ/pubhtml) - 添加新供应商 [here](http://goo.gl/forms/YDbPSPmufS).
- [Entities Providing Transportation Software Development Consulting Services](https://docs.google.com/spreadsheets/u/1/d/1n44CNMCK1vt1nyrsdYz-KD_hYxUMNIm6Me69M6ROBIg/pubhtml) - 添加新实体 [here](http://goo.gl/forms/cc6kcVERuP).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Luqmaan Dawoodjee](https://github.com/luqmaan) 和 [Center for Urban Transportation Research](https://www.cutr.usf.edu/) 在 [University of South Florida](http://www.usf.edu/) 已放弃对此作品的所有版权及相关或邻接权利.

## About

Originally created by [Luqmaan Dawoodjee](https://github.com/luqmaan)，现在由维护 [Center for Urban Transportation Research](https://www.cutr.usf.edu/) 在 [University of South Florida](http://www.usf.edu/).

此列表旨在作为仅供参考的社区资源 - 项目/产品列表并不意味着认可.
