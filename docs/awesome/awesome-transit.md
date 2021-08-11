<div class="github-widget" data-repo="CUTR-at-USF/awesome-transit"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-transit [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![RSS](https://img.shields.io/badge/Subscribe-RSS-blue.svg)](https://github.com/CUTR-at-USF/awesome-transit/commits/master.atom)

##### Community list of transit APIs, apps, datasets, research, and software :bus::star2::train::star2::steam_locomotive:

有什么要添加或更改的吗？ 打开一个 [pull request](https://github.com/CUTR-at-USF/awesome-transit/pulls) 要么 [issue](https://github.com/CUTR-at-USF/awesome-transit/issues).

------------------------------



### Getting started

如果这是您第一次处理公交数据，您可能会发现这些链接很有用：

- [GTFS](https://developers.google.com/transit/gtfs/)  - GTFS 提要是一组文本文件，其中包含不经常更改的交通数据，例如停靠点、路线、行程和其他时间表数据. 运输机构通常每隔几个月更新一次他们的 GTFS 提要.
- [GTFS Realtime](https://developers.google.com/transit/gtfs-realtime/)  - GTFS Realtime 由三​​个二进制文件组成，其中包含实时车辆位置、实时到达信息和服务警报. 运输机构通常每分钟更新一次这些文件.
- [OpenMobilityData](https://openmobilitydata.org/)  （前 TransitFeeds） - 来自世界各地的 GTFS/GTFS 实时数据馈送列表. 如果您想获取某个机构的实时数据，这是一个不错的起点.
- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) - 一个免费的、在线的、自定进度的课程，用于学习 GTFS 和 GTFS-realtime.
- [Open Transit Data Toolkit](http://transitdatatoolkit.com/) - 一系列帮助人们利用开放交通数据的课程.
- [MBTA GTFS Onboarding](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb)  - MBTA 为 GTFS 静态创建的交互式教程. 一种 [stand-alone Docker image](https://github.com/mbta/gtfs_onboarding) 可在 GitHub 上以及 [hosted/no-install version](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb) 的 Jupyter 笔记本.


### Community

提问和查找其他社区资源的地方.

- [TransitWiki](http://transitwiki.org)  - 公共交通规划者的社区维基. 喜欢这个回购，但更好.
- [MobilityData Slack chat](https://mobilitydata-io.herokuapp.com/)
- [Transit Developers mailing list](https://groups.google.com/forum/#!forum/transit-developers)
- OneBusAway
  - [OneBusAway User mailing list](http://groups.google.com/group/onebusaway-users)
  - [OneBusAway Developers mailing list](http://groups.google.com/group/onebusaway-developers)
  - [OneBusAway API mailing list](http://groups.google.com/group/onebusaway-api)
  - [OneBusAway Slack chat](https://onebusaway.herokuapp.com/)
- [Transit Techies NYC](https://transittechies.nyc/) - 为对这个 repo 感兴趣的人举办的基于纽约的聚会. [Speaker list](https://transittechies.nyc/past) 包括此 repo 的许多贡献者.

### Data

访问 GTFS 和其他运输和多模式数据集合的地方

#### 3rd party GTFS URL directories
- [Transitland](https://transit.land/)  - 许多公交机构 GTFS 数据集的社区可编辑列表. 还提供了一个 API 来访问数据作为 JSON/GeoJSON 和一个操场来尝试数据.
- [OpenMobilityData](https://openmobilitydata.org/) - GTFS 和列表 [GTFS-RT](https://openmobilitydata.org/search?q=gtfsrt) 饲料. [Archives 和 validates](https://openmobilitydata.org/p/capital-metro/24) GTFS 提要并允许您预览两者 [GTFS](https://openmobilitydata.org/p/capital-metro/24/latest) 和 [GTFS-RT](https://openmobilitydata.org/p/capital-metro/495) 通过浏览器.
- [~~GTFS Data Exchange~~ (Deprecated)](http://www.gtfs-data-exchange.com/agencies)  - 以前是 GTFS 提要 URL 的最终目录.  2016 年关闭.但可应要求提供 2008 年至 2016 年的 93 GB 数据.

#### Transit agency data archives
- [CapMetrics](https://github.com/scascketta/CapMetrics)  - 奥斯汀交通局 (CapMetro) 的历史车辆位置. 数据由 [capmetricsd](https://github.com/scascketta/capmetricsd)，一个 Go 守护进程.

#### National government datasets
- [National Transit Database (USA)](https://www.transit.dot.gov/ntd) - 美国交通系统的信息和统计数据，由联邦交通管理局管理.
- [Transport (France)](https://transport.data.gouv.fr/) - 法国交通系统的 GTFS 数据集.
- [European long-distance transport operators (EU) *(Unofficial)*](https://github.com/public-transport/european-transport-operators) - 可用 API 端点、GTFS 提要和客户端库的非官方列表

#### Proprietary (non-standard) vendor APIs
- [Transport API](https://www.transportapi.com/)  - 用于英国聚合交通数据的 REST API. 基于费用的访问.
- [TransLoc OpenAPI](https://market.mashape.com/transloc/openapi-1-2) - REST API 用于美国 60 多个已购买 TransLoc 的 AVL 硬件和软件的交通系统的实时车辆、路线、停靠点和到达数据.
- [NextBus API](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) - 用于购买 NextBus 硬件和/或软件的机构的实时车辆、路线、停靠点和到达数据的 REST API.
- [Navitia.io](http://www.navitia.io/) - REST API 用于美国和欧盟的行程规划、停止时间表、等时线等. [Navitia](https://github.com/CanalTP/navitia) 是实时 API 背后的开源引擎.
- [CityBikes](http://api.citybik.es)  - 用于汇总来自世界各地的共享单车数据的 REST API. 供电 [pyBikes](https://github.com/eskerda/pybikes).
- [HAFAS](https://de.wikipedia.org/wiki/HAFAS) – 专有的公共交通管理软件由 [HaCon](https://www.hacon.de) ([list of endpoints](https://gist.github.com/derhuerst/2b7ed83bfa5f115125a5))

#### Crowdsourced transit data
- [Citylines.co](https://www.citylines.co)  - 一个用于绘制交通系统地图的协作平台，重点是它们的历史演变. 数据可以从 GeoJSON 或 CSV 下载 [citylines.co/data](https://www.citylines.co/data).
- [OpenStreetMap (OSM)](https://www.openstreetmap.org) - 用于绘制世界地图的协作平台，包括运输、过境和路线数据.
- [GTFS-Hub](https://github.com/mfdz/gtfs-hub)  - 社区测试，可能质量/内容增强，部分合并或过滤（目前是德国）运输机构的 GTFS 提要. 维护者 [MITFAHR|DE|ZENTRALE](https://github.com/mfdz).

### Software for Creating APIs

您可以设置为提供 API 以传输和多模式数据的软件.

- [OneBusAway](http://onebusaway.org/) - 使用 GTFS 和 GTFS-Realtime 的 Java 应用程序（以及 [other formats](https://github.com/OneBusAway/onebusaway-application-modules/wiki/Real-Time-Data-Configuration-Guide)) 并将它们变成易于使用 [REST API](http://developer.onebusaway.org/modules/onebusaway-application-modules/current/api/where/index.html).
- [OpenTripPlanner](http://www.opentripplanner.org/) - 用于多模式和多机构旅程规划的开源平台，以及返回有关多模式图的信息（使用数据源，如 GTFS 和 [OpenStreetMap](http://www.openstreetmap.org/)).
- [TransitClock](http://thetransitclock.org)  - 可以使用原始车辆位置并以 GTFS-realtime 等格式生成预测时间的 Java 应用程序. 旧称“过境”.
- [Linked Connections](http://linkedconnections.org/)  - 一个开源的、可扩展的多式联运路线规划引擎，它允许客户端执行路线规划算法（而不是服务器）. 使用 GTFS 数据.
- [TransiCast](http://www.transicast.com/)  - 以单一、集成的呼叫和响应格式提供北美的公共交通数据. 数据以流解析 XML 和 JSON 格式提供. 开源于 [Google Code](https://code.google.com/archive/p/rasa/) . 在 www.transitcast.com 上托管版本 [requires payment](http://www.transicast.com/coststructure.html).
- [gtfs-server](https://github.com/denysvitali/gtfs-server) - 一个用 Rust 编写的 Web 服务器，它使用 PostGIS 作为后端通过 HTTP 端点提供 GTFS 数据
- [Navitia](https://github.com/CanalTP/navitia) 是背后的开源引擎 [Navitia.io](http://www.navitia.io/) 实时 API.
- [pyBikes](https://github.com/eskerda/pybikes) - 软件供电 [CityBikes](http://api.citybik.es) 全球共享单车系统信息
- [hafas-rest-api](https://github.com/public-transport/hafas-rest-api) – 暴露一个 [HAFAS](https://de.wikipedia.org/wiki/HAFAS) 端点作为 REST API.
- [GraphHopper Routing Engine](https://github.com/graphhopper/graphhopper/#public-transit)  OpenStreetMap 的开源路由引擎. 将其用作 Java 库或服务器.

### Agency Tools

运输机构的工具. 也可以看看 [GTFS Data Collection and Maintenance Tools](#gtfs-data-collection-and-maintenance-tools) 对于特定于 GTFS 的工具.

- [Remix](http://getremix.com/) - A webapp that lets transit agencies easily plan routes.
- [AC Transit RestroomFinder](https://github.com/actransitorg/ACTransit.RestroomFinder) - 使用 GPS 和屏幕地图为巴士运营商和现场工作人员确定最近的授权洗手间.
- [AC Transit Training and Education Department (TED) application](https://github.com/actransitorg/ACTransit.Training) - 尽管该系统支持新课程和学徒计划，但该应用程序支持学区对运输和维护员工的培训操作，主要是公交车操作员和重型教练机技工（学徒和旅程）的职位.
- [AC Transit Customer Relations application (CusRel)](https://github.com/actransitorg/ACTransit.CusRel) - 用于客户问题和反馈的公共交通票务系统：带通知的跨部门路由、部门/人员分配、简单的工作流程、票务搜索、预制报告、每日提醒等.
- [TransAM](http://camsys.software/products/transam)  - 面向公共交通机构的开源资产管理平台. 开源 [on Github](https://github.com/camsys/transam_core).
- [RidePilot](https://github.com/camsys/ridepilot) - 一个开源的计算机辅助调度和调度 (CASD) 软件系统，可满足小规模人力服务运输机构的需求（有关更多信息，请参阅 [Cambridge Systematics's marketing site](http://camsys.software/products/ridepilot)).
- [TNExT](https://github.com/ODOT-PTS/TNExT) - Transit Network Explorer Tool (TNExT) 是一种基于 Web 的软件工具，用于对俄勒冈州的区域和全州交通网络进行可视化、分析和报告.
- 路线趋势（[webapp](https://metrotransitmn.shinyapps.io/route-trends/), [GitHub](https://github.com/metrotransit/route-trends)) - 一个 R Shiny 应用程序，用于摄取乘客时间序列，并根据以下情况返回季节性、趋势和残差分量 [STL methodology](https://otexts.com/fpp2/stl.html) 和预测，包括基于这些组件的不确定性. 由...赞助 [Metro Transit](https://www.metrotransit.org/) （明尼阿波利斯-圣保罗）.
- [TBEST](https://tbest.org/)  - TBEST（Transit Boardings Estimation and Simulation Tool）致力于开发一个多方面的基于 GIS 的建模、规划和分析工具，该工具将社会经济、土地利用和公交网络数据整合到一个基于场景的公交乘客量平台中估计和分析. 由佛罗里达州交通部资助. 免费使用但不开源.

### Hardware

实验和生产运输硬件.

- [Bus Tracking GPS](https://github.com/herrdragon/busTrackingGps) - 用于跟踪公交巴士的廉价开源解决方案的迈阿密原型代码.

### Apps

人们在乘坐交通工具时使用的应用程序.

#### Web Apps (open source)
- [Instabus](http://instabus.org)  - 奥斯汀（CapMetro）公共交通的实时地图. 完全没有服务器/后端依赖，完全在 GitHub 页面上运行.
- [OpenTripPlanner Client GWT](https://github.com/mecatran/OpenTripPlanner-client-gwt) - 用于 OpenTripPlanner 的基于 Google Web Toolkit 的 Web 界面
- [OpenTripPlanner.js](https://github.com/conveyal/otp.js) - 基于 Javascript 的 OpenTripPlanner 客户端（不再开发）
- [OTP-UI React Component Library](https://github.com/opentripplanner/otp-ui)  - React Javascript 组件库，可用于构建旅行计划 Web 应用程序. 见 [Storybook](http://www.opentripplanner.org/otp-ui) 用于演示.
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - 基于 Java 的 Web 应用程序，用于生成 GTFS 实时服务警报.
- [HRT BUS Web app](https://github.com/Code4HR/hrt-bus-api) - HRT Bus API 通过应用程序编程接口从 Hampton Roads Transit 发布实时总线数据，供开发人员使用它来制作应用程序.
- [Transit-Map](https://github.com/vasile/transit-map) - 使用公共交通时间表对地图上的车辆（标记）进行动画处理的 Web 应用程序，以沿路线（折线）插入它们的位置.
- [Transitive.js](https://github.com/conveyal/transitive.js) - 使用 Leaflet 或 D3 创建一个可定制的过境路线网络地图层.
- [Google I/O Transport Tracker](https://github.com/googlemaps/transport-tracker) - 显示谷歌 I/O 大会的班车到达时间，基于开源 [transport-tracker project](https://github.com/googlemaps/transport-tracker) . 注意：要自己实现，您需要一个 [Google Maps APIs Premium Plan license](https://developers.google.com/maps/pricing-and-plans/).
- [1-Click](http://camsys.software/products/1-click)  - 一个虚拟的“旅行聚合器”，可以收集各种可用模式的信息：公共交通、私人、铁路、拼车、拼车、志愿者、辅助公交以及步行和骑自行车. 开源 [on GitHub](https://github.com/camsys/oneclick).
- [Bustime](https://www.bustime.ru)  - 使用 WebSocket 更新进行公共交通实时监控. 开源 [on GitHub](https://github.com/norn/bustime).
- [Transit Tracker](https://transittracker.ca/#/) - 加拿大大蒙特利尔和多伦多的实时车辆位置
- [GTFS Builder](http://nationalrtap.org/Web-Apps/GTFS-Builder)  - 一个免费的基于 Web 的应用程序，可帮助您创建 GTFS 文件. 由国家农村交通援助计划 (RTAP) 维护.
- [Dede](https://dedriver.org)  - 一个独立和通用的乘客信息系统 (PIS) 映射实时移动. 带有 GTFS-Realtime 格式的 Vehicle Position 实体的消息馈送或 [Dede app](https://github.com/dancesWithCycles/dede-android) 可以作为数据源.
- [MBTA tile-server](https://github.com/mbta/tile-server) - 用于创建 Docker 容器的脚本，该容器封装了开发用于 MBTA.com 的地图图块所需的所有元素

#### Web Apps (closed source)
- [TransitScreen](http://transitscreen.com/) - 所有当地交通选择的自定义实时显示
- [Citylines.co](https://www.citylines.co) - 一个用于绘制交通系统地图的协作平台，重点是它们的历史演变.
- [Bikeshare Map](http://bikes.oobrien.com/) - 全球所有共享单车站点的状态
- [Bongo](http://ebongo.org)  - 爱荷华市、科拉尔维尔和爱荷华大学的实时交通跟踪. 将三个不同的交通系统合并到一个 UI 中.
- [Brand New Subway](http://jpwright.net/subway/) - 一种交互式交通规划游戏，让玩家可以根据自己的喜好改变纽约市地铁系统.
- [CityMapper Webapp](https://citymapper.com/nyc) - 真正完善的 web 应用程序，包含 30 多个城市的旅行计划和路线状态.
- [YourStop](http://yourstop.info)  - 移动友好的网络应用程序，它使用 GTFS 提要并显示站点的实时和预定行程. 与 MBTA、YRT/Viva 和马里兰州 MTA 一起推出.
- [DC MetroHero](https://dcmetrohero.com)  - 华盛顿特区地区的 WMATA Metrorail 和 Metrobus 系统的实时车辆位置和到达和离开信息.  WebApp、Android 和 iOS 应用程序可用.

#### Native Apps (open source)

- OneBusAway 应用程序 - [Android](https://play.google.com/store/apps/details?id=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [Fire Phone](http://www.amazon.com/gp/mas/dl/android?p=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [iOS](https://itunes.apple.com/us/app/onebusaway/id329380089)  [*(source code)*](https://github.com/OneBusAway/onebusaway-iphone), [Windows Phone](https://www.microsoft.com/en-us/store/apps/onebusaway/9nblggh0cbd9) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows-phone), [Windows 8](https://www.microsoft.com/en-us/store/apps/onebusaway/9wzdncrdm5pc) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows8), [Google Glass GDK](https://github.com/OneBusAway/onebusaway-android/pull/219) [*(source code)*](https://github.com/OneBusAway/onebusaway-android/pull/219), [Alexa skill](https://www.amazon.com/OneBusAway/dp/B01ELVUYCW/) [*(source code)*](https://github.com/OneBusAway/onebusaway-alexa)
- [OpenTripPlanner Android](https://github.com/CUTR-at-USF/OpenTripPlanner-for-Android/wiki) - 一个 Android 应用程序 [OpenTripPlanner](http://www.opentripplanner.org/)
- [OpenTripPlanner iOS](https://github.com/opentripplanner/OpenTripPlanner-iOS) - 一个 iOS 应用程序 [OpenTripPlanner](http://www.opentripplanner.org/)
- [opentripplanner-client-library](https://github.com/CUTR-at-USF/opentripplanner-client-library) - 一个 Kotlin 多平台库，用于从 OpenTripPlanner v2 服务器发出 API 请求和解析响应，用于 Android、iOS 和 Web 的旅行计划、自行车租赁信息和服务器元数据.
- [Transportr](https://github.com/grote/Transportr) 一个 Android 应用程序，使用 [public-transport-enabler](https://github.com/schildbach/public-transport-enabler) 为了连接到世界各地的许多不同的运输网络.
- [Offi Directions](https://gitlab.com/oeffi/oeffi) - 一个 Android 应用程序，可为欧洲及其他地区的交通当局提供旅行计划、时间表、实时出发时间和中断信息.
- [Trufi App](https://github.com/trufi-association/trufi-app) 一个跨平台的 Flutter 应用程序，使用 [OpenTripPlanner](http://www.opentripplanner.org/)
- [Dede App](https://github.com/dancesWithCycles/dede-android) - 一款让任何 Android 手机成为自动车辆定位 (AVL) 设备的应用程序 [Dede](https://dedriver.org) 乘客信息系统 (PIS).

#### Native Apps (closed source)

- [ally](http://www.allyapp.com/)
- [Transit](http://transitapp.com/)
- [CityMapper](https://citymapper.com/)
- [Moovit](http://moovitapp.com/)
- [Tiramisu Transit](http://www.tiramisutransit.com/)
- [TransLoc Rider](http://translocrider.com/) - 100 多个交通系统的实时交通地图.
- [Transit Display](http://transitdisplay.com/) - 多模式和实时运输显示软件.
- [Ualabee](https://ualabee.com/company/) - 社区驱动的行程规划器，专注于用户交互，用户可以报告异常、上传图片、编辑交通数据以及与其他乘客聊天.

### Visualizations

- [Visualizing MBTA Data](http://mbtaviz.github.io/) - 显示人们如何使用波士顿地铁系统的交互式图表.
- [MIT COAXS](http://mittransportanalyst.github.io/) - 使用基于可访问性的利益相关者参与来共同创造交通走廊的规划（显示路线场景使用 [OpenTripPlanner Analyst](http://www.opentripplanner.org/analyst/)).
- [TRAVIC Transit Visualization Client](http://tracker.geops.ch/)  - 可视化基于静态 GTFS 数据（有时是实时数据）移动的车辆. 支持超过260个城市.  geOps 组织的 Github 帐户是 [here](https://github.com/geops).
- [MTA Frequency](http://www.tyleragreen.com/maps/new_york/) - 使用纽约市地铁和公共汽车的频率可视化 [Transitland](https://transit.land/).
- [Traze](https://traze.app/) 经过 [Veridict](https://www.veridict.com)  - 来自世界各地的公共交通车辆的可视化. 与其他用户协作以获取实时更新，即使该机构无法提供实时更新. 基于许多来源，包括 GTFS 和 GTFS-RT.  （以前称为 [Livemap24](https://www.livemap24.com)). 
- [SEPTA Rail OTP Report](https://apps.phor.net/septa/) - 使用 GTFS 的在线准时性能报告和深入分析工具.
- [TransitFlow](https://github.com/transitland/transitland-processing-animation) 使用 Processing 和 Transitland 为世界各地的 GTFS 数据制作动画.
- [All Transit](https://all-transit.com)  - 使用 Mapbox GL JS、Deck.gl 和 Transitland 的交互式 GTFS 路线和时间表动画（针对美国城市）.  Github 存储库 [here](https://github.com/kylebarron/all-transit).
- [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz) - 使用 GTFS 数据进行动画和可视化的 Web 应用程序 [gtfspy](https://github.com/CxAalto/gtfspy).
- [Mapnificent](https://www.mapnificent.net/)  - 显示您可以在给定时间内乘坐公共交通工具到达的区域. 开源 [on GitHub](https://github.com/mapnificent/mapnificent)，住在 https://www.mapnificent.net/.
- [Toronto Transit Explorer](https://github.com/sidewalklabs/totx)  - 一个 Java 应用程序，可将多伦多市的交通、骑自行车和步行的可访问性可视化. 托管的实时版本 [here](https://totx.sidewalklabs.com/) . 使用修改后的版本 [R5](https://github.com/conveyal/r5) 用于路由.
- [fastest-bus-analysis-in-the-west](https://github.com/vta/fastest-bus-analysis-in-the-west)  - 一个 Python Pandas 脚本，它结合了 Ridership/APC、Swiftly 速度和停留数据、公交车站库存、GTFS 和地理空间形状，以创建按站、按路线、时间分组可过滤数据集进行交叉分析. 然后将数据集可视化 [Tableau](https://public.tableau.com/profile/vivek7797#!/vizhome/stopsandspeedanalyses/Story1) 帮助 VTA 规划人员通过站点整合和专用车道等加速方法找到使公共汽车和铁路网络更快、更可靠的地方.
- [TNExT](https://github.com/ODOT-PTS/TNExT) - Transit Network Explorer Tool (TNExT) 是一种基于 Web 的软件工具，用于对俄勒冈州的区域和全州交通网络进行可视化、分析和报告.

### GTFS

- [GTFS Spec](https://developers.google.com/transit/gtfs/)  - 通用传输数据馈送（GTFS）规范. 也可在 [Español](https://developers.google.com/transit/gtfs/?hl=es), [Français](https://developers.google.com/transit/gtfs/?hl=fr).
- [GTFS Best Practices](http://gtfs.org/best-practices/) - GTFS 提要生产者的最佳实践.

#### GTFS Libraries

可以轻松使用各种语言的 GTFS 数据的软件.

#### C
- [CGTFS](https://github.com/rakhack/cgtfs)  - 用于读取静态 GTFS 提要的 C 库. 支持将解包的提要读入应用程序内存或 SQLite 数据库.
- [RRRR Rapid Real-time Routing](https://github.com/bliksemlabs/rrrr) - RRRR（通常读作 R4）是 RAPTOR 公共交通路由算法的 C 语言实现.

#### C++
-  [just_gtfs](https://github.com/mapsme/just_gtfs) - 用于读写 GTFS 的 C++17 头文件库（用于 [MAPS.ME](https://github.com/mapsme/omim) ）. 主要特点：快速读写 GTFS 提要，支持 [extended GTFS route types](https://developers.google.com/transit/gtfs/reference/extended-route-types)，简单地使用 GTFS 日期和时间格式.

#### C#
- [ESRI public-transit-tools](https://github.com/Esri/public-transit-tools) - 用于在 ArcGIS 中处理公共交通数据的工具（需要 ArcGIS 许可）.
- [GTFS Feed Parser](https://github.com/OsmSharp/GTFS) - GTFS 解析器的 .Net/Mono 实现.

#### Go
- [Go GTFS Parser](https://github.com/geops/gtfsparser) - Go 的 GTFS 解析库.

#### Java
- [GTFS to SQL](https://github.com/OpenMobilityData/GtfsToSql) - 将 GTFS 提要解析到 SQL 数据库中（用于 [OpenMobilityData](https://openmobilitydata.org/)).
- [OneBusAway GTFS Modules](https://github.com/OneBusAway/onebusaway-gtfs-modules/wiki) - 基于 Java 的库，用于读取、写入和转换 GTFS 格式的公共交通数据，包括数据库支持.
- [R5: Rapid Realistic Routing on Real-world and Reimagined networks](https://github.com/conveyal/r5)  - 用于多模式（公交/自行车/步行/汽车）网络的基于 Java 的路由引擎. 它目前计划在一个时间窗口内进行多次旅行以进行分析，但最终可能会支持点对点的旅行计划.
- [SQL to GTFS](https://github.com/OpenMobilityData/SqlToGtfs) - 将使用“GtfsToSql”生成的 SQLite 文件转换回压缩的 GTFS 文件.

#### JavaScript
- [gtfs-sequelize](https://github.com/evansiroky/gtfs-sequelize) - Node.js 库使用建模静态 GTFS [sequelize.js](http://sequelizejs.com/).
- [gtfs-utils](https://github.com/public-transport/gtfs-utils) – 处理 GTFS 数据集的实用程序（例如，“扁平化”`calendar.txt` 和 `calendar_dates.txt`，计算行程的到达/离开时间）.
- [gtfs-via-postgres](https://github.com/derhuerst/gtfs-via-postgres) – 另一个使用 PostgreSQL 处理 GTFS 的工具.
- [Node-GTFS](https://github.com/BlinkTagInc/node-gtfs)  - 从 GTFS 文件加载传输数据，解压缩并将其存储到 SQLite 数据库. 提供了一些查询机构、路线、站点和时间的方法.

#### PostgreSQL
- [gtfs-schema](https://github.com/tyleragreen/gtfs-schema) - 用于 GTFS 提要的 PostgreSQL 模式.
- [gtfs-via-postgres](https://github.com/derhuerst/gtfs-via-postgres) – 另一个使用 PostgreSQL 处理 GTFS 的工具.

#### Python
- [ESRI public-transit-tools](https://github.com/Esri/public-transit-tools) - 用于在 ArcGIS 中处理公共交通数据的工具（需要 ArcGIS 许可）.
- [gtfsdb](https://github.com/OpenTransitTools/gtfsdb) - 用于将 GTFS 文件转换为关系数据库的 Python 库.
- [gtfslib-python](https://github.com/afimb/gtfslib-python) - python 中的开源库，用于读取 GTFS 文件和计算有关公共交通网络的各种统计数据和指标.
- [gtfsman](https://github.com/geops/gtfsman) - Python 中类似存储库的工具，用于管理和更新大量 GTFS 提要.
- [gtfspy](https://github.com/CxAalto/gtfspy)  - 使用 Python3 进行公共交通网络分析和旅行时间计算. 与 Postgres/PostGIS、Oracle、MySQL 和 SQLite 兼容. 使用人 [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz).
- [GTFS Kit](https://github.com/mrcagney/gtfs_kit)  - 一个 Python 3.6+ 工具包，用于分析 General Transit Feed Specification (GTFS) 数据. 取代 [GTFSTK](https://github.com/araichev/gtfstk).
- [GTFSTK](https://github.com/araichev/gtfstk)  - 用于分析内存中 GTFS 数据的 Python 3 工具包. 使用 Pandas 和 Shapely 来提高速度. 被取代 [GTFS Kit](https://github.com/mrcagney/gtfs_kit).
- [Make GTFS](https://github.com/mrcagney/make_gtfs) - 一个 Python 库，用于根据基本路线信息制作 GTFS 提要.
- [Mapzen GTFS](https://github.com/transitland/mapzen-gtfs) - 一个 Python GTFS 库，支持读取单个 GTFS 表，或构建一个图表来表示提要中的每个机构.
- [multigtfs](https://github.com/tulsawebdevs/django-multi-gtfs) - 一个用于导入和导出 GTFS 的 Django 应用程序.
- [partridge](https://github.com/remix/partridge) - 基于 Pandas DataFrames 构建的快速、宽容的 Python GTFS 阅读器.

#### R
- [trread](https://github.com/r-gtfs/trread) - R 的传输 (GTFS) 文件阅读器. 

#### Ruby
- [GTFS-viz](https://github.com/vasile/GTFS-viz) - Ruby 脚本，可将一组 GTFS 文件转换为 SQLite 数据库 + GeoJSONs（需要 [Transit Map](https://github.com/vasile/transit-map) web application)

#### GTFS Converters

从各种静态计划格式到 GTFS 的转换器.

- [Chouette](http://www.chouette.mobi/)  - 转换法语-Transmodel、SIRI、NETeX. 有关更多信息，请参阅 Chouette.mobi 网站.
- [extract-gtfs-pathways](https://github.com/derhuerst/extract-gtfs-pathways) – 从 GTFS 数据集中以 GeoJSON 形式提取路径的命令行工具.
- [extract-gtfs-shapes](https://github.com/derhuerst/extract-gtfs-shapes) – 从 GTFS 数据集中提取形状作为 GeoJSON 的命令行工具.
- [GTFS-OSM-Sync](https://github.com/CUTR-at-USF/gtfs-osm-sync) - 用于同步 GTFS 格式数据的 Java 工具 [OpenStreetMap.org](http://www.openstreetmap.org/).
- [gtfs-service-area](https://github.com/cal-itp/gtfs-service-area)  - 从静态 GTFS 计算公交服务区. 结果输出为单层 .geojson 文件.  Docker 化版本 [gtfs-to-geojson](https://github.com/BlinkTagInc/gtfs-to-geojson).
- [gtfs-to-geojson](https://github.com/BlinkTagInc/gtfs-to-geojson)  - 将 GTFS 形状的交通数据和停靠点转换为 geoJSON 的 Javascript 工具. 这对于创建公交路线地图很有用.
- [gtsf](https://github.com/r-gtfs/gtsf) - R. 中的通用传输 (GTFS) 简单（地理）特征 (sf) 可用于通过 GDAL 从 GTFS 转换为 Shapefile、GeoJSON 和其他格式.
- [hafas-generate-gtfs](https://github.com/derhuerst/hafas-generate-gtfs) *(work-in-progress)*] – 一种用于从 HAFAS 端点生成 GTFS 转储的 Javascript 工具.
- [Hafas2GTFS](https://github.com/geops/hafas2gtfs) - 用 Python 编写的 Hafas2GTFS 转换器，针对 SBB HAFAS 提要进行了优化.
- [kml-to-gtfs-shapes](https://github.com/bdferris/kml-to-gtfs-shapes/tree/gh-pages)  - 用于将 KML 文件中的折线转换为 GTFS shape.txt 文件的 Javascript 工具. 托管在 GitHub 上 [here](http://bdferris.github.io/kml-to-gtfs-shapes/).
- [o2g](https://github.com/hiposfer/o2g) - 从 OpenStreetMap 中提取 GTFS 提要的简单工具.
- [Open-Transport SYNTHESE Convertors](https://github.com/Open-Transport/synthese/wiki) - 转换 French-Transmodel、SIRI、NETeX、HAFAS、HASTUS、VDV452 等.
- [onebusaway-gtfs-to-barefoot](https://github.com/OneBusAway/onebusaway-gtfs-to-barefoot) - 用于创建一个 Java 工具 [Barefoot](https://github.com/bmwcarit/barefoot) 来自 GTFS 文件的映射文件.
- [onebusaway-vdv-modules](https://github.com/OneBusAway/onebusaway-vdv-modules) - 用于处理 VDV 格式的交通数据的 Java 库，包括将 VDV-452 计划数据转换为 GTFS.
- [osm2gtfs](https://github.com/grote/osm2gtfs) - 将 OpenStreetMap 数据和日程信息转换为 GTFS.
- [transit_model](https://github.com/CanalTP/transit_model) - 一个 Rust 库，用于转换为/从以下格式：GTFS、NTFS（对于 Navitia，请参阅 [Software for Creating APIs](#software-for-creating-apis)), TransXChange ([UK standard format](http://naptan.dft.gov.uk/transxchange/documentation.htm)), KV1 ([Netherland standard format](http://bison.connekt.nl/standaarden/)) 或 NetEx ([European standard format](http://netex-cen.eu/)).
- [transloc-gtfs-rectifier](https://github.com/laidig/transloc-gtfs-rectifier) - 尝试将 GTFS stop_ids 分配给的 Python 应用程序 [TransLoc](http://transloc.com/) 使用的 ID [TransLoc's API](https://market.mashape.com/transloc/openapi-1-2) ([TransLoc](http://transloc.com/) 在他们的 API 中没有提供 GTFS `stop_ids`）.
- [Transmodel and IFF to GTFS](https://github.com/bliksemlabs/bliksemintegration)  - 导入和同步 (Transmodel) BISON Koppelvlak1、IFF（HP/EDS 编写的格式，有点类似于 ATCO CIF）以导入铁路网络的时间表. 内部伪 NETeX 数据结构允许导出到 GTFS，并且有一些概念证明可以导出到其他格式，例如 NETeX、GTFS 和 IFF.

#### GTFS Data Collection and Maintenance Tools

- [bus-router](https://github.com/atlregional/bus-router) - 使用从 [Google Maps Directions API](https://developers.google.com/maps/documentation/directions/) 要么 [OSRM](https://github.com/Project-OSRM/osrm-backend/wiki/Server-api).
- [GTFS Editor](https://github.com/conveyal/gtfs-editor) 一个（自托管）基于 Web 的 GTFS 编辑框架.  （注意：该项目已被弃用，以支持 [IBI Data Tools](https://github.com/ibi-group/datatools-ui).)
- [GTFS Editor for Vagrant](https://github.com/laidig/vagrant-gtfs-editor) 使用以下命令快速设置 GTFS 编辑器（上图） [Vagrant](https://www.vagrantup.com/)
- [static-GTFS-manager](https://github.com/WRI-Cities/static-GTFS-manager) - 一个（自托管）基于浏览器的用户界面，用于创建、编辑、导出静态 GTFS（请参阅 [related post](https://groups.google.com/forum/#!topic/transit-developers/GFz5rTJTB0I) ）. 现场演示 [here](https://static-gtfs-manager.herokuapp.com/).
- [TransitWand](http://transitwand.com/)  - 用于收集交通数据的开源网络和移动应用程序. 使用它来创建 GTFS 提要、捕获乘客数量或生成 GIS 数据集.
- [IBI Data Tools](https://github.com/ibi-group/datatools-ui)  - 处理 GTFS 编辑、验证、质量检查和部署到 OpenTripPlanner 的 Web 应用程序.  （结合并建立在已弃用的功能上 [Gtfs Data Manager](https://github.com/conveyal/gtfs-data-manager) 和 [GTFS Editor](https://github.com/conveyal/gtfs-editor).)
- [GTFS.html](https://gtfs.pleasantprogrammer.com)  - 一个完全基于浏览器的工具来查看 GTFS 提要. 使用它来查看路线、站点、时间表等.
- [pfaedle](https://github.com/ad-freiburg/pfaedle) - 使用 OpenStreetMap 数据对 GTFS 进行精确地图匹配
- [GTFS shape mapfit](https://github.com/HSLdevcom/gtfs_shape_mapfit)  - 适合 GTFS 形状文件并停止到给定 OSM 映射文件的 Python 工具. 用途 [pymapmatch](https://github.com/tru-hy/pymapmatch) 为匹配.
- [GTFS Builder](http://nationalrtap.org/Web-Apps/GTFS-Builder)  - 一个免费的基于 Web 的应用程序，可帮助您创建 GTFS 文件. 由国家农村交通援助计划 (RTAP) 维护.
- [gtfs-station-builder](https://github.com/kostjerry/gtfs-station-builder) - 帮助构建站点内部结构的UI工具（包括pathways.txt）

#### GTFS Analysis Tools

- [Peartree](https://github.com/kuanb/peartree) - 用于将交通数据转换为有向图以进行网络分析的 Python 库.
- [gtfsr](https://github.com/ropensci/gtfsr) - 一个 R 包，用于轻松导入、验证和映射遵循通用公交源规范 (GTFS) 格式的公交数据.
- [tidytransit](https://github.com/r-transit/tidytransit) （以前 [bustt](https://github.com/r-transit/bustt) ) - 将 GTFS 数据读入 tidyverse 和简单特征数据帧，以绘制公交站点和路线图、计算公交频率并验证公交信息.  tidytransit 是一个 [fork](https://en.wikipedia.org/wiki/Fork_\(software_development\)）  [gtfsr](https://github.com/ropensci/gtfsr), 发布到 [CRAN](https://cran.r-project.org/)，具有频率/车头时距计算功能. 
- [transitr](https://github.com/tmelliott/transitr) - 用于实时构建和建模交通网络以获得车辆 ETA 的 R 包
- [Busbuzzard](https://github.com/bmander/busbuzzard) - 从交通车辆的经验数据推断概率时间表.
- [ESRI ArcGIS Public Transit Tools (GTFS)](https://github.com/Esri/public-transit-tools) - 用于在 ArcGIS 中处理公共交通数据的工具

#### GTFS Timetable Publishing Tools

- [GTFS to HTML](https://github.com/BlinkTagInc/gtfs-to-html) - A 直接从 GTFS 公交数据创建 HTML 格式的人类可读、用户友好的公交时间表. 
- [TimeTablePublisher (TTPUB)](https://github.com/OpenTransitTools/ttpub) - 由 TriMet 开发的网络发布系统，允许运输机构检查、修改原始调度数据并将其转换为易于阅读的时间表以供客户信息使用

#### GTFS Validators

- [Conveyal's gtfs-validator](https://github.com/conveyal/gtfs-validator) - 基于 OneBusAway GTFS 模块的基于 Java 的 GTFS 验证器，在 Java 中运行，并且比 Google 提供的更快.
- [Conveyal's gtfs-lib](https://github.com/conveyal/gtfs-lib/) - Conveyal 的继任者 [gtfs-validator](https://github.com/conveyal/gtfs-validator)，一个基于 Java 的库，用于加载和保存具有磁盘支持存储的任意大小的 GTFS 提要.
- [Google's feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) - 谷歌支持的基于 Python 的 GTFS 验证器.
- [GTFS Data Package Specification](https://github.com/Stephen-Gates/GTFS) - 一种 [Data Package specification](http://specs.frictionlessdata.io/data-packages/) 验证完成 [Good Tables](http://goodtables.okfnlabs.org/) . 包括数据包、模式、测试，并以东南昆士兰 GTFS 数据为例.
- [GTFS Meta-Validator (hosted by Omni)](http://gtfsvalidator.omnimodal.io) - 基于 Web 的 GTFS 验证器，可同时运行 [the Google Python feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) 和 [Conveyal's gtfs-validator](https://github.com/conveyal/gtfs-validator) 在上传的 GTFS 文件上.
- [gtfstidy](https://github.com/patrickbr/gtfstidy) - 基于 Go 的工具，用于整理和验证 GTFS 提要.
- [gtfs-validator-api](https://github.com/cal-itp/gtfs-validator-api) - 这个 Python 包是一个薄包装 [MobilityData/gtfs-validator](https://github.com/MobilityData/gtfs-validator) 处理生成的中间文件并查找 gtfs-validator 的输出文件，因此可以为其指定特定名称或作为字符串返回.
- [GTFSVTOR](https://github.com/mecatran/gtfsvtor) - 一个开源的 GTFS 验证器，用 Java 实现，在 GPLv3 下获得许可，由维护者维护 [Mecatran](https://www.mecatran.com/).
- [MobilityData's gtfs-validator](https://github.com/MobilityData/gtfs-validator) - 一个开源 GTFS 验证器规范地遵循 GTFS 规范，在 Java 中实现，在 Apache v2.0 下获得许可，由 Apache v2.0 维护 [MobilityData](https://mobilitydata.org/).
- [Reflect GTFS Validator (hosted by Foursquare ITP)](https://reflect.foursquareitp.com) - 运输时间表和 GTFS 验证平台 [Foursquare ITP](https://www.foursquareitp.com) 其中包括一个基于 Web 的免费 G​​TFS 验证器 [gtfs-lib](https://github.com/conveyal/gtfs-lib/).
- [Transit App's gtfs-fares-v2-validator](https://github.com/TransitApp/gtfs-fares-v2-validator) - 一个基于 GTFS-Fares-v2 数据验证器的 Python 工具 [draft specification](https://docs.google.com/document/d/19j-f-wZ5C_kYXmkLBye1g42U-kvfSVgYLkkG5oyBauY/edit#).
- [Transport Validator](https://github.com/etalab/transport-validator/) - 在中实现的开源验证器 [Rust](https://www.rust-lang.org/) . 使用 [French National Access Point](https://transport.data.gouv.fr/validation/).


#### GTFS Realtime

- [GTFS-realtime documentation](https://github.com/google/transit/tree/master/gtfs-realtime) . 也可在 [Español](https://github.com/google/transit/tree/master/gtfs-realtime/spec/es).
- [GTFS-realtime Autodoc](https://laidig.github.io/gtfs-rt-autodoc/index.html) - 自动生成的 GTFS-realtime 文档，从官方生成 [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto) 并包括一些扩展.

#### GTFS Realtime Libraries & Demo Apps

- [gtfs-realtime-bindings](https://github.com/google/gtfs-realtime-bindings) - 从官方生成的 Java、.NET、Node.js、Python 和 Ruby 的官方绑定 [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto).
- [GTFS-realtime Exporter](https://github.com/OneBusAway/onebusaway-gtfs-realtime-exporter/wiki) - 基于 Java 的工具，可帮助生成和共享 GTFS 相关时间提要.
- [GTFS-realtime Alerts Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-alerts-producer-demo/wiki) - 基于 Java 的演示项目，用于生成 GTFS 实时服务警报.
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - 基于 Java 的 Web 应用程序，用于生成 GTFS 实时服务警报.
- [GTFS-realtime TripUpdates & VehiclePositions Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-trip-updates-producer-demo/wiki) - 基于 Java 的演示项目，用于生成 GTFS 实时 TripUpdates（估计到达）和车辆位置.
- [GTFS-realtime Vehicle Positions Consumer/Visualizer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-visualizer/wiki) - 基于 Java 的演示项目，用于使用 GTFS 实时车辆位置提要并在地图上显示此信息.

#### GTFS Realtime Validators

- [gtfs-realtime-validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator)  - 由南佛罗里达大学城市交通研究中心开发的 GTFS 实时验证工具. 还包括一个集成版本 [gtfs-validator](https://github.com/conveyal/gtfs-validator) 工具.

#### GTFS Realtime (and Other Real-time API) Archival Tools

- [GTFS-realtime to SQL](https://github.com/OpenMobilityData/GtfsRealTimeToSql) - 将 GTFS-RealTime 提要解析到 SQL 数据库中（用于 [OpenMobilityData.org](https://openmobilitydata.org))
- [gtfsrdb](https://github.com/CUTR-at-USF/gtfsrdb) - 支持读取和归档 GTFS 实时提要到数据库的 Python 工具
- [retro-gtfs](https://github.com/SAUSy-Lab/retro-gtfs) - 从 Nextbus API 收集实时数据并将其存档为 GTFS 格式（即追溯 GTFS）的 Python 应用程序.

#### GTFS Realtime Convertors

- [SIRI 到 GTFS-实时](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) - 基于 Java 的命令行实用程序，用于从 [SIRI format](http://user47094.vs.easily.co.uk/siri/) 到 GTFS-实时
- [OrbCAD SQL Server to GTFS-realtime](https://github.com/CUTR-at-USF/HART-GTFS-realtimeGenerator/) - 基于 Java 的命令行实用程序，可从 OrbCAD SQL Server 中提取车辆位置和行程更新信息，并将其导出为 GTFS 实时 TripUpdates 和 VehiclePositions 格式.
- [NextBus API to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-nextbus-cli/wiki) - 基于 Java 的命令行实用程序，用于从 [NextBus API format](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) 到 GTFS 实时. 请注意，NextBus 现在直接为其产品提供 GTFS 实时 API. 看 [Cubic site](http://nextbus.cubic.com/Products/Real-Time-Rider-Information) 和 [this FAQ](https://medium.com/omnimodal/want-more-riders-open-up-your-nextbus-api-with-gtfs-realtime-7387c80f31e1#.pkuzizhl5).
- [Syncromatics API to GTFS-realtime](https://github.com/CUTR-at-USF/bullrunner-gtfs-realtime-generator) - 基于 Java 的命令行实用程序，用于从 [Syncromatics API](http://www.syncromatics.com/) 格式为 GTFS 实时 TripUpdates 和 VehiclePositons.
- [KV6,15,17, and ARNU to GTFS-realtime](https://github.com/bliksemlabs/bliksemintegration-realtime)  - 基于 Java 的工具，用于处理传入的 KV6、15、17 和 ARNU，并将它们与 RID 集成数据库中存在的静态交通数据进行匹配. 然后继续将这些数据导出为 ARNU RITinfo、GTFS(realtime) 和 KV78turbo
- [WMATA BusPositions API to GTFS-realtime](https://github.com/kurtraschke/wmata-gtfsrealtime) - 从 WMATA 转换的基于 Java 的工具 [BusPositions API](https://developer.wmata.com/docs/services/54763629281d83086473f231/operations/5476362a281d830c946a3d68) 和警报 RSS 提要来自 [MetroAlerts](http://www.wmata.com/rider_tools/metro_service_status/rail_bus.cfm?) 到 GTFS 实时 TripUpdates、VehiclePositions 和 Alerts 提要.
- [SEPTA API 到 GTFS-实时](https://github.com/kurtraschke/septa-gtfsrealtime) - 基于Java的转换工具 [SEPTA's](http://www.septa.org/) [real-time bus and rail data](http://www3.septa.org/hackathon/) 到 GTFS-实时
- [CTA API to GTFS-realtime](https://github.com/kurtraschke/ctatt-gtfsrealtime) - 基于Java的转换工具 [CTA's](http://www.transitchicago.com/) [Train Tracker data](http://www.transitchicago.com/developers/traintracker.aspx) 到 GTFS 实时.
- [Detroit DOT to GTFS-realtime](https://github.com/prashtx/ddot-avl) - 从中提取实时信息 [DDOT's](http://www.detroitmi.gov/How-Do-I/Locate-Transportation/Bus-Schedules) TransitMaster 安装（数据库）并转换为 GTFS-realtime
- [Live Transit Event Trigger](https://github.com/ipublic/live_transit_event_trigger) - 从中提取数据 [Ride On's](http://www.montgomerycountymd.gov/dot-transit/) OrbCAD 数据库并导出为 GTFS-realtime.
- [SoundTransit 到 GTFS-实时](https://github.com/bdferris/onebusaway-sound-transit-realtime) - 将文本文件源转换为 [Sound Transit](http://www.soundtransit.org/) 到 GTFS-实时
- [Civic Transit](https://github.com/jestin/CivicTransit) - 屏幕抓取 [KCATA’s](http://www.kcata.org/) 安装 TransitMaster WebWatch 以生成 GTFS 实时提要.
- [GTFS-realtime VehiclePositions to GTFS-realtime TripUpdates (TransitClock)](http://thetransitclock.org)  - 可以使用原始车辆位置并以 GTFS-realtime 等格式生成预测时间的 Java 应用程序. 旧称“过境”.
- [gtfs-realtime-translators](https://github.com/Intersection/gtfs-realtime-translators)  - 基于 Python 的工具，可将自定义到达 API 格式转换为 GTFS 实时格式. 截至 2019 年 7 月，它支持 LA Metro 和 SEPTA.
- [Transloc API to GTFS-realtime](https://github.com/jonathonwpowell/transloc-to-gtfs-real-time) - 基于 Node.js 的工具，用于将 Transloc API 转换为 GTFS-realtime.
- [hafas-gtfs-rt-feed](https://github.com/derhuerst/hafas-gtfs-rt-feed) – 一种用于从 HAFAS 端点生成 GTFS 实时源的 Javascript 工具.
- [GTFS-realtime to SIRI-Lite](https://github.com/etalab/transpo-rt/) - 一种 [Rust](https://www.rust-lang.org/) 网络服务器将多个 GTFS-RT 提要转换为 SIRI-Lite API.

#### GTFS Realtime Utilities

- [gtfs-rt-dump](https://github.com/kurtraschke/gtfs-rt-dump) - 将协议缓冲区格式转换为纯文本，以便以纯文本形式轻松查看 GTFS 实时提要（用于调试目的）
- [GTFS-realtime Printer](https://github.com/laidig/gtfs-rt-printer) - 基于 Java 的实用程序，用于从 GTFS 实时文件或 URL 打印信息.
- [gtfs-rt-inspector](https://public-transport.github.io/gtfs-rt-inspector/) <i>– Web app to inspect &amp; analyze any (CORS-enabled) GTFS Realtime feed.</i> <b>– 用于检查和分析任何（启用 CORS 的）GTFS 实时提要的 Web 应用程序。</b> <i>Open-source on</i><b>开源于</b> [GitHub](https://github.com/public-transport/gtfs-rt-inspector).
- [print-gtfs-rt-cli](https://github.com/derhuerst/print-gtfs-rt-cli) – 用于从标准输入读取 GTFS 实时提要、打印人类可读或作为 JSON 的 Javascript 工具.
- [GTFS-realtime Munin Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-munin-plugin) - 提供一个 [Munin](http://munin-monitoring.org/) 用于记录有关 GTFS 实时提要的信息的插件.
- [GTFS-realtime Nagio Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-nagios-plugin) - 提供一个 [Nagios](https://www.nagios.org/) 用于监控 GTFS 实时提要的插件
- [GTFS-realtime-test-service](https://github.com/CUTR-at-USF/gtfs-realtime-test-service) - 用于模拟 GTFS 实时提要内容的工具（例如，用于测试 GTFS 实时消费应用程序）.
- [gtfs-rt-differential-to-full-dataset](https://github.com/derhuerst/gtfs-rt-differential-to-full-dataset) – 用于将连续 GTFS 实时流的“DIFFERENTIAL”增量数据转换为“FULL_DATASET”转储的 Javascript 工具.
- [gtfs-rt-admin](https://github.com/conveyal/gtfs-rt-admin) - 用于管理 GTFS-RT 服务警报（JavaScript 和 Java）的管理工具.
- [manual-gtfsrt](https://github.com/pailakka/manual-gtfsrt) - 基于 Go 的工具，可提供从可编辑 JSON 创建的 GTFS-RT 提要.
- [Transit Network Model](https://github.com/tmelliott/TransitNetworkModel) - 使用 GTFS 实时 VehiclePositions、粒子滤波器和卡尔曼滤波器生成预测的工具.
- [bus_kalman](https://github.com/cmoscardi/bus_kalman) - 一个卡尔曼滤波器，用于使用 NYC MTA 实时数据插入公交车行程时间.

### SIRI

- [SIRI API](https://github.com/OneBusAway/onebusaway/wiki/SIRI-Resources) - 从 v1.0 和 v1.3 生成的 Java 类 [SIRI](http://user47094.vs.easily.co.uk/siri/) 模式.
- [SIRI 2.0 API](https://github.com/laidig/siri-20-java) - 从 v2.0 生成的 Java 类 [SIRI](http://user47094.vs.easily.co.uk/siri/) 模式.
- [SIRI to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) - 基于 Java 的命令行实用程序，用于从 [SIRI format](http://user47094.vs.easily.co.uk/siri/) 到 GTFS 实时.
- [SIRI 2.0 Autodoc](https://laidig.github.io/siri-20-java/doc/) - 从（非常好）带注释的 SIRI 2.0 模式定义自动生成的文档.
- [King County Metro Legacy AVL to SIRI](https://github.com/bdferris/onebusaway-king-county-metro/tree/master/onebusaway-king-county-metro-legacy-avl-to-siri) - 基于Java的转换工具 [King County Metro's](http://metro.kingcounty.gov/) 将传统 AVL 格式转换为 SIRI.
- [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki) - 一个开源 Android 库，用于与实时交通数据的 RESTful SIRI 接口交互，例如当前使用的数据 [MTA Bus Time API](http://bustime.mta.info/wiki/Developers/SIRIIntro).
- [SIRI 1.3 POJOs (Android-compatible)](https://github.com/CUTR-at-USF/onebusaway-siri-api-v13-pojos/wiki)  - Android 兼容的纯旧 Java 对象 (POJOS)，用于 SIRI v1.3 API 的数据绑定（反序列化 XML/JSON）响应. 使用 [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki).
- [pysiri2validator](https://github.com/laidig/pysiri2validator) - 用 Python 3 编写的 SIRI 2.0 的简单验证器.
- [Edwig](https://github.com/af83/edwig) - 用于实时公共交通数据交换的 golang 服务器，使用 SIRI 协议.

### Other multimodal data formats

- [Alliance for Parking Data Standards (APDS)](https://www.allianceforparkingdatastandards.org/) - 由 [International Parking Institute (IPI)](https://www.parking.org/)， 这 [British Parking Association (BPA)](http://www.britishparking.co.uk/)，以及 [European Parking Association (EPA)](http://www.europeanparking.eu/) , APDS 是一个非营利组织，其使命是开发、推广、管理和维护统一的全球标准，使组织能够跨全球平台共享停车数据.  APDS 1.0 版文档是 [here](https://www.allianceforparkingdatastandards.org/resources).
- [CurbLR](https://github.com/curblr/curblr-spec) - 路缘法规的规范.
- - [Dyno-Demand](https://github.com/osplanning-data-standards/dyno-demand) - 基于 GTFS 的旅行需求数据格式，专注于个人乘客*需求*，适用于旧金山县交通管理局、LMZ LLC 和 UrbanLabs LLC 开发的动态网络建模.
- [Dyno-Path](https://github.com/osplanning-data-standards/dyno-path) - （正在开发中 - 见 [this post](https://github.com/osplanning-data-standards/GTFS-PLUS/pull/52#issuecomment-331231000)) 个人乘客*轨迹*的数据.
- [General Bikeshare Feed Specification (GBFS)](https://github.com/NABSA/gbfs) - 共享单车实时信息的开放数据标准由成员开发 [North American Bikeshare Association (NABSA)](http://nabsa.net/).
    - [gbfs-validator](https://github.com/PierrickP/gbfs-validator) - 3rd party tool to validate GBFS feeds.
    - [gbfs R package](https://github.com/ds-civic-data/gbfs) - 与 R 中的 GBFS 提要接口的功能，允许用户为指定的城市/共享单车程序保存和积累整洁的 .rds 数据集.
- [GTFS-flex](https://github.com/MobilityData/gtfs-flex) - 一种将灵活的公共交通服务建模为 GTFS 扩展的数据格式.
- [GTFS-plus](https://github.com/osplanning-data-standards/GTFS-PLUS) - 基于 GTFS 的交通网络格式，用于*车辆和容量数据*，适用于由普吉特海湾地区委员会、UrbanLabs LLC、LMZ LLC 和旧金山县交通管理局开发的动态交通建模.
- [GTFS-ride](https://github.com/ODOT-PTS/GTFS-ride) - 由俄勒冈州交通部和俄勒冈州立大学合作开发的开放式固定路线公交乘客数据标准.
- [GTFS-stat](https://github.com/osplanning-data-standards/GTFS-STAT) - An extension to a GTFS transit network with additional files that contain performance data developed by UrbanLabs LLC and San Francisco County Transportation Authority.
- [General Modeling Network Specification (GMNS)](https://github.com/zephyr-data-specs/GMNS)  - 一种共享可路由道路网络文件的格式，旨在用于多模式静态和动态交通规划和运营模型.  Volpe/FHWA 与 Zephyr 基金会合作.
- [General Travel Network Specification](https://zephyrtransport.org/trb17projects/7-general-travel-network-specification/) - 用于共享旅行需求模型网络的计划数据规范.
- [Managed and Tolled Lanes Feed Specification (MTLFS)](https://github.com/vta/Managed-and-Tolled-Lanes-Feed-Specification) - 包含托管和收费车道收费供稿规范 (MTLFS) 的架构提案，并定义了所有这些文件中使用的字段 [Santa Clara Valley Transportation Authority](http://www.vta.org/).
- [Mobility as a Service API](http://maas-api.org/) - 一组开放文档和测试套件，用于定义与 MaaS 兼容的 API（例如， [MaaS Transport Service Provider Booking API](https://github.com/maasglobal/maas-tsp-api/blob/master/specs/Booking.md)).
- [Mobility Data Specification (MDS)](https://github.com/openmobilityfoundation/mobility-data-specification)  - 一种为市政当局和作为服务提供商的移动性实施实时数据共享、测量和监管的格式. 它旨在确保政府有能力强制执行、评估和管理提供者. 由维护 [Open Mobility Foundation](https://www.openmobilityfoundation.org/).
- [NCHRP 08-119 Developing Data Standards and Guidance for Transportation Planning and Traffic Operations - Phase 1 (Anticipated)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4543) - 本研究的目标是制定标准和/或指南，供运输界使用和采用，用于收集、管理和共享用于运输规划和运营的静态和实时数据.
- [NeTex](http://netex-cen.eu/) - 一种通用 XML 格式，设计用于在分布式系统管理的分布式系统之间交换复杂的静态传输数据 [CEN standards process](https://www.cen.eu/work/ENdev/how/Pages/default.aspx).
- [OMX: The Open Matrix data file format](https://github.com/osPlanning/omx) - 二维数组对象和相关元数据的结构化集合，可能用于交通建模行业.
- [Open Sales and Distribution Model (OSDM)](https://github.com/UnionInternationalCheminsdeFer/OSDM)  - 旨在大幅简化铁路旅行客户的预订流程，并降低分销商和铁路运营商的复杂性和分销成本. 包含离线模型和在线 API 的规范. 由维护 [International Union of Railways (UIC)](https://github.com/UnionInternationalCheminsdeFer).
- [SAE Shared and Digital Mobility Committee](http://articles.sae.org/15799/) - 似乎正在为汽车共享和运输网络公司 (TNC)/拼车制定数据标准.
- [shared-row](https://github.com/d-wasserman/shared-row) - SharedStreets 参考的通行权 (ROW) 规范.
- [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120)  - 本研究的目的是为参与提供需求响应运输的实体制定交易数据的技术规范. 预计完工日期为 2018 年底.
- [TIDES project](https://groups.google.com/forum/#!forum/tidesproject) - 公交 ITS 数据交换规范 (TIDES) 是一项提议的工作，旨在为历史公交 ITS 数据（包括 AVL、APC 和 AFC 数据）创建标准数据结构、API 和数据管理工具.
- [Transport Operator Mobility-as-a-service Provider (TOMP)-API](https://github.com/TOMP-WG/TOMP-API) - 荷兰工作组的目标是开发一个 API，供运输运营商和移动即服务提供商用于运营商发现、旅行计划、最终用户交互、预订和支付.

### Resources

与开放交通数据相关的在线课程、博客文章和报告.

#### On-line courses

- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) - 一个免费的、在线的、自定进度的课程，用于学习 GTFS 和 GTFS-realtime.
- [Open Transit Data Toolkit](http://transitdatatoolkit.com/) - 一系列帮助人们利用开放交通数据的课程.
- [MBTA GTFS Onboarding](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb)  - MBTA 为 GTFS 静态创建的交互式教程. 一种 [stand-alone Docker image](https://github.com/mbta/gtfs_onboarding) 可在 GitHub 上以及 [hosted/no-install version](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb) 的 Jupyter 笔记本.
- [Planetizen "Building a Transit Map Web App" course](https://courses.planetizen.com/course/building-transit-map-app) - 无需编码经验即可设置您自己的基于 Web 的地图应用程序的视频教程. 

#### Blog posts

- [When(ish) is my bus? Data and code](https://github.com/mjskay/when-ish-is-my-bus)  - Whenish 背后的数据和代码 (R) 是我的总线？ 数据包括三天的历史车辆位置和调查结果.
- ["Legacy AVL system? It's okay, join the club." by Kurt Raschke](https://kurtraschke.com/2015/01/legacy-avl-export) - Discussion of options for transforming legacy AVL system data into the GTFS-realtime format.
- ["GTFS Best Practices now available!" by Sean Barbeau](https://medium.com/@sjbarbeau/gtfs-best-practices-now-available-88ac67194233) - 讨论开放数据格式（如 GTFS）和 2017 年初推出的 GTFS 最佳实践所面临的一些挑战，以帮助解决数据质量问题.
- ["What's new in GTFS-realtime v2.0" by Sean Barbeau](https://medium.com/@sjbarbeau/whats-new-in-gtfs-realtime-v2-0-cd45e6a861e9) - 讨论 GTFS-realtime v1.0 的不足和 v2.0 的改进.
- ["AVL, CAD, and Real-Time Passenger Info for Beginners" by Tony Laidig](http://transitdata.net/avl-cad-and-real-time-passenger-info-for-beginners/) - 提供对用于跟踪车辆的技术的一般介绍.
- ["Visualizing Better Transportation: Data & Tools" by Steve Pepple](https://medium.com/@stevepepple/visualizing-better-transportation-data-tools-e48b8317a21c) - 旧金山湾区和北美其他城市的交通相关数据和工具的集合，最初是在旧金山 ARUP 的 2018 年交通周活动中收集和讨论的.
- ["How to use GTFS data to track transit vehicles in realtime" by Tom Camp](https://www.ably.io/blog/gtfs-data-track-transit-vehicles-realtime) - 使用 GTFS 和 GTFS Realtime 提供持续的实时更新.

#### Academic papers

- [Tang et al. - "Ridership effects of real-time bus information system: A case study in the City of Chicago"](https://www.sciencedirect.com/science/article/pii/S0968090X12000022) - 在伊利诺伊州芝加哥进行的实验表明，当乘客通过短信或电子邮件访问实时信息时，乘客人数略有增加.
- [Kay et al. - "When(ish) is my bus? User-centered Visualizations of Uncertainty in Everyday, Mobile Predictive Systems"](http://faculty.washington.edu/jhullman/busUncertaintyVis.pdf) - Paper attempts to answr the question of "how do we communicate uncertainty in transit predictions?" Explains the problem, existing solutions and designs a [better interface for letting users know when to arrive at the bus stop](https://github.com/mjskay/when-ish-is-my-bus/blob/master/quantile-dotplots.md#quantile-dotplots).
- [Watkins et al. - "Where Is My Bus? Impact of mobile real-time information on the perceived and actual wait time of transit riders"](https://www.sciencedirect.com/science/article/pii/S0965856411001030) - 西澳州西雅图市的实验表明，当乘客通过移动应用程序访问实时信息时，他们认为公交车等待时间更短.
- [Brakewood et al. - “An experiment evaluating the impacts of real-time transit information on bus riders in Tampa, Florida”](https://www.sciencedirect.com/science/article/pii/S0965856414002146)  - 在佛罗里达州坦帕的受控实验表明，与没有实时信息的乘客相比，通过移动应用程序访问实时信息的乘客的等待时间减少了近 2 分钟. 获得实时信息的骑手也减少了焦虑和沮丧，并更好地接受了代理.
- [Brakewood et al. - "The impact of real-time information on bus ridership in New York City"](https://www.sciencedirect.com/science/article/pii/S0968090X15000297) - 纽约市的实验表明，当向乘客提供实时信息时，长途路线的乘客人数会增加.
- [Brakewood and Watkins - "A literature review of the passenger benefits of real-time transit information"](https://www.tandfonline.com/doi/full/10.1080/01441647.2018.1472147?scroll=top&needAccess=true) (2018) - 许多不同研究的概述，这些研究着眼于实时交通信息的好处.

#### Government reports
- [APTA Policy Development and Research - Public Transportation Embracing Open Data](http://www.apta.com/resources/reportsandpublications/Documents/APTA-Embracing-Open-Data.pdf) - APTA 对开放交通数据的好处和挑战的讨论（以下 TCRP 报告的简短摘要）.
- [TCRP Synthesis 115 - Open Data: Challenges and Opportunities for Transit Agencies](http://onlinepubs.trb.org/Onlinepubs/tcrp/tcrp_syn_115.pdf) (2015) - 一份关于开放交通数据的好处和挑战的综合报告.
- [TCRP Research Report 213: Data Sharing Guidance for Public Transit Agencies – Now and in the Future](http://www.trb.org/Main/Blurbs/180188.aspx) (2020) - 一份旨在帮助机构做出有关共享数据的决策的报告，包括如何评估收益、成本和风险.
- [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120)  - 本研究的目的是为参与提供需求响应运输的实体制定交易数据的技术规范. 预计完工日期为 2018 年底.

#### Community-maintained lists
- [Vendors Providing GTFS Creation/Maintenance services](https://docs.google.com/spreadsheets/u/1/d/1Gc9mu4BIYC8ORpv2IbbVnT3q8VQ3xkeY7Hz068vT_GQ/pubhtml) - 添加新供应商 [here](http://goo.gl/forms/YDbPSPmufS).
- [Entities Providing Transportation Software Development Consulting Services](https://docs.google.com/spreadsheets/u/1/d/1n44CNMCK1vt1nyrsdYz-KD_hYxUMNIm6Me69M6ROBIg/pubhtml) - 添加新实体 [here](http://goo.gl/forms/cc6kcVERuP).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Luqmaan Dawoodjee](https://github.com/luqmaan) 和 [Center for Urban Transportation Research](https://www.cutr.usf.edu/) 在 [University of South Florida](http://www.usf.edu/) 已放弃本作品的所有版权和相关或邻接权.

## About

最初创建者 [Luqmaan Dawoodjee](https://github.com/luqmaan)，现在由 [Center for Urban Transportation Research](https://www.cutr.usf.edu/) 在 [University of South Florida](http://www.usf.edu/).

此列表旨在作为仅供参考的社区资源 - 项目/产品的列表并不意味着认可.
