<div class="github-widget" data-repo="CUTR-at-USF/awesome-transit"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-transit [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![RSS](https://img.shields.io/badge/Subscribe-RSS-blue.svg)](https://github.com/CUTR-at-USF/awesome-transit/commits/master.atom)

##### Community list of transit APIs, apps, datasets, research, and software :bus::star2::train::star2::steam_locomotive:

有什么要添加或更改的吗？ 打开一个 [pull request](https://github.com/CUTR-在-USF/awesome-transit/pulls) 或者 [issue](https://github.com/CUTR-在-USF/awesome-transit/issues) 在 [CUTR-在-USF/awesome-transit](https://github.com/CUTR-在-USF/awesome-transit).

------------------------------



### Getting started

如果这是您第一次处理公交数据，您可能会发现这些链接很有用：

- [GTFS](https://developers.google.com/transit/gtfs/)  - GTFS 提要是一组文本文件，其中包含不经常更改的公交数据，例如停靠点、路线、行程和其他时间表数据. 公交机构通常每隔几个月更新一次 GTFS 提要.
- [GTFS Realtime](https://developers.google.com/transit/gtfs-realtime/)  - GTFS Realtime 由三​​个二进制文件组成，其中包含实时车辆位置、实时到达信息和服务警报. 运输机构通常每分钟更新一次这些文件.
- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) - 一个免费的在线自学课程，用于学习 GTFS 和实时 GTFS.
- [Open Transit Data Toolkit](http://transitdatatoolkit.com/) - 一系列帮助人们利用开放交通数据的课程.
- [MBTA GTFS Onboarding](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb)  - MBTA 为 GTFS 静态创建的交互式教程. 一种 [stand-alone Docker image](https://github.com/mbta/gtfs_onboarding) 可在 GitHub 以及 [hosted/no-install version](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb) Jupyter 笔记本.


### Community

提问和寻找其他社区资源的地方.

- [German Open Transport Meetup](https://github.com/transportkollektiv/meetup/wiki) - 你可以参加一个 [biweekly](https://hackmd.okfn.de/opentransportmeetup#) 德语开放交通社区的聚会.
- [OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner) 社区
    - [OpenTripPlanner User mailing list](https://groups.google.com/forum/#!forum/opentripplanner-users)
    - [OpenTripPlanner Developers mailing list](https://groups.google.com/forum/#!forum/opentripplanner-dev)
- [TransitWiki](http://transitwiki.org)  - 交通规划者的社区维基. 喜欢这个回购，但更好.
- [MobilityData Slack chat](https://mobilitydata-io.herokuapp.com/)
- [Transit Developers mailing list](https://groups.google.com/forum/#!forum/transit-developers)
- OneBusAway
    - [OneBusAway User mailing list](http://groups.google.com/group/onebusaway-users)
    - [OneBusAway Developers mailing list](http://groups.google.com/group/onebusaway-developers)
    - [OneBusAway API mailing list](http://groups.google.com/group/onebusaway-api)
    - [OneBusAway Slack chat](https://onebusaway.herokuapp.com/)
- [Transit Techies NYC](https://transittechies.nyc/) - 为那些对这个 repo 感兴趣的人在纽约举行的聚会. [Speaker list](https://transittechies.nyc/past) 包括此 repo 的许多贡献者.

### Data

访问 GTFS 和其他运输和多式联运数据集合的地方

#### 3rd party GTFS URL directories
- [~~GTFS Data Exchange~~ (Deprecated)](http://www.gtfs-data-exchange.com/agencies)  - 以前是 GTFS 提要 URL 的最终目录.  2016 年关闭.但 2008 年至 2016 年的 93 GB 数据可根据要求提供.
- [~~OpenMobilityData~~ (Deprecated)](https://openmobilitydata.org/) - GTFS 列表和 [GTFS-RT](https://openmobilitydata.org/search?q=gtfsrt) 饲料. [Archives 和 validates](https://openmobilitydata.org/p/capital-metro/24) GTFS 提要并允许您预览 [GTFS](https://openmobilitydata.org/p/capital-metro/24/latest) 和 [GTFS-RT](https://openmobilitydata.org/p/capital-metro/495) 通过浏览器. 前身为 TransitFeeds.com. [MobilityData announced](https://database.mobilitydata.org/#h.u71vp6xgkckf) 它将于 2022 年初报废，停产日期待定.
- [The Mobility Database](https://database.mobilitydata.org/) - JSON 和 CSV 文件 [on GitHub](https://github.com/MobilityData/mobility-database-catalogs) 这是一个包含全球 1300 多个移动数据集的存储库. 包含 OpenMobilityData/TransitFeeds.com 的内容.
- [Transitland](https://transit.land/)  - 许多交通机构 GTFS 数据集的社区可编辑列表. 还提供了一个 API 来以 JSON/GeoJSON 的形式访问数据，以及一个试验数据的游乐场.

#### Transit agency data archives
- [CapMetrics](https://github.com/scascketta/CapMetrics)  - 奥斯汀交通机构 (CapMetro) 的历史车辆位置. 数据由以下人员收集 [capmetricsd](https://github.com/scascketta/capmetricsd), 一个 Go 守护进程.

#### National government datasets
- [National Transit Database (USA)](https://www.transit.dot.gov/ntd) - 美国交通系统的信息和统计数据，由联邦交通管理局管理.
- [Transport (France)](https://transport.data.gouv.fr/) - 法国交通系统的 GTFS 数据集.
- [European long-distance transport operators (EU) *(Unofficial)*](https://github.com/public-transport/european-transport-operators) - 可用 API 端点、GTFS 提要和客户端库的非官方列表

#### Proprietary (non-standard) vendor APIs
- [Transport API](https://www.transportapi.com/)  - 用于英国汇总过境数据的 REST API. 收费访问.
- [TransLoc OpenAPI](https://market.mashape.com/transloc/openapi-1-2) - 用于美国 60 多个已购买 TransLoc 的 AVL 硬件和软件的交通系统的实时车辆、路线、停靠站和到达数据的 REST API.
- [NextBus API](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) - 为已购买 NextBus 硬件和/或软件的机构提供实时车辆、路线、停靠站和到达数据的 REST API.
- [Navitia.io](http://www.navitia.io/) - REST API 用于美国和欧盟的旅程计划、停止时间表、等速线等. [Navitia](https://github.com/CanalTP/navitia) 是实时 API 背后的开源引擎.
- [CityBikes](http://api.citybik.es)  - 用于来自世界各地的共享单车数据的 REST API. 供电 [pyBikes](https://github.com/eskerda/pybikes).
- [HAFAS](https://de.wikipedia.org/wiki/HAFAS) – 专有的公共交通管理软件 [HaCon](https://www.hacon.de) ([list of endpoints](https://gist.github.com/derhuerst/2b7ed83bfa5f115125a5))
- [Citymapper API](https://docs.external.citymapper.com/api/) - 用于交通旅程规划的 REST API、实时交通数据和步行、自行车、踏板车旅行时间.

#### Crowdsourced transit data
- [Citylines.co](https://www.citylines.co)  - 一个用于绘制交通系统地图的协作平台，重点是其历史演变. 数据可以从 GeoJSON 或 CSV 下载 [citylines.co/data](https://www.citylines.co/data).
- [OpenStreetMap (OSM)](https://www.openstreetmap.org) - 用于绘制世界地图的协作平台，包括运输、过境和路线数据.
- [GTFS-Hub](https://github.com/mfdz/gtfs-hub)  - 社区测试，可能质量/内容增强，部分合并或过滤（当前德国）运输机构的 GTFS 提要. 维护者 [MITFAHR|DE|ZENTRALE](https://github.com/mfdz).

#### Sample GTFS and GTFS Realtime datasets used for software testing
- [sample-gtfs-feed](https://github.com/public-transport/sample-gtfs-feed) - 用于测试的虚构 GTFS 数据集.
- [transitfeed unit tests](https://github.com/google/transitfeed/tree/master/tests/data) - 为原始 Google 创建的测试数据 [Python GTFS validator](https://github.com/google/transitfeed/wiki/FeedValidator).
- [Transitland GTFS and GTFS Realtime unit tests](https://github.com/interline-io/transitland-lib) - 用于测试 [transitland-lib](https://github.com/interline-io/transitland-lib) 为 Transitland 处理 GTFS 和 GTFS 实时解析和验证的库：
    - [GTFS - "bad entities" at the single row level](https://github.com/interline-io/transitland-lib/tree/master/test/data/bad-entities)
    - [GTFS - validation errors that that involve entities in one or more files](https://github.com/interline-io/transitland-lib/tree/master/test/data/validator/errors)
    - [GTFS - best practices](https://github.com/interline-io/transitland-lib/tree/master/test/data/validator/best-practices)
    - [GTFS Realtime - JSON test cases that are turned into PB contents](https://github.com/interline-io/transitland-server/tree/main/test/data/rt)
- [gtfs-realtime-validator unit tests](https://github.com/MobilityData/gtfs-realtime-validator/tree/master/gtfs-realtime-validator-lib/src/test/) - 一些 [GTFS datasets (zip files)](https://github.com/MobilityData/gtfs-realtime-validator/tree/master/gtfs-realtime-validator-lib/src/test/resources) 包含并定义了大量的 GTFS RT 消息 [programmatically in Java](https://github.com/MobilityData/gtfs-realtime-validator/tree/master/gtfs-realtime-validator-lib/src/test/java/edu/usf/cutr/gtfsrtvalidator/lib/test/rules) 通过 gtfs-realtime-bindings 库.
- [OpenTripPlanner unit tests](https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/src/test) - 一些 [GTFS datasets](https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/src/test/resources/gtfs) 为单元测试定义（[GtfsTest](https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/src/test/java/org/opentripplanner/GtfsTest.java) 和 [mmri folder](https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/src/test/java/org/opentripplanner/mmri)).

### Software for Creating APIs

您可以设置为提供 API 来传输和多式联运数据的软件.

- [GraphHopper Routing Engine](https://github.com/graphhopper/graphhopper/#public-transit)  OpenStreetMap 的开源路由引擎. 将其用作 Java 库或服务器.
- [gtfs-server](https://github.com/denysvitali/gtfs-server) - 一个 Web 服务器，用 Rust 编写，使用 PostGIS 作为后端，通过 HTTP 端点提供 GTFS 数据
- [hafas-rest-api](https://github.com/public-transport/hafas-rest-api) – 暴露一个 [HAFAS](https://de.wikipedia.org/wiki/HAFAS) 端点作为 REST API.
- [Linked Connections](http://linkedconnections.org/)  - 一个开源的、可扩展的多式联运路线规划引擎，它允许客户端执行路线规划算法（而不是服务器）. 使用 GTFS 数据.
- [MOTIS](https://github.com/motis-project/motis)  - 多目标旅游信息系统，用 C++ 和 Java 编写. 可以使用 GTFS 或 HAFAS 格式的时间表以及 GTFS-RT（和 RISML，德国铁路公司的专有格式）中的实时信息作为输入数据. 对于行人路线（由 Per Pedes Routing 处理）和汽车路线（由 OSRM 处理），使用 OpenStreetMap 数据.
- [Navitia](https://github.com/CanalTP/navitia) 是背后的开源引擎 [Navitia.io](http://www.navitia.io/) 实时 API.
- [OneBusAway](http://onebusaway.org/) - 一个使用 GTFS 和 GTFS-Realtime 的 Java 应用程序（以及 [other formats](https://github.com/OneBusAway/onebusaway-application-modules/wiki/Real-Time-Data-Configuration-Guide)) 并将它们变成易于使用 [REST API](http://developer.onebusaway.org/modules/onebusaway-application-modules/current/api/where/index.html).
- [OpenTripPlanner](http://www.opentripplanner.org/) - 用于多模式和多机构旅程规划的开源平台，以及返回有关多模式图的信息（使用 GTFS 和 [OpenStreetMap](http://www.openstreetmap.org/)).
- [pyBikes](https://github.com/eskerda/pybikes) - 软件供电 [CityBikes](http://api.citybik.es) 全球共享单车系统信息
- [TransitClock](http://thetransitclock.org)  - 可以使用原始车辆位置并以 GTFS-realtime 等格式生成预测时间的 Java 应用程序. 以前称为“时空”.
- [TransiCast](http://www.transicast.com/)  - 以单一、集成的呼叫和响应格式提供北美的公共交通数据. 数据以流可解析的 XML 和 JSON 格式提供. 开源于 [Google Code](https://code.google.com/archive/p/rasa/) .  www.transitcast.com 上的托管版本 [requires payment](http://www.transicast.com/coststructure.html).

### Agency Tools

交通机构的工具. 也可以看看 [GTFS Data Collection and Maintenance Tools](#gtfs-data-collection-and-maintenance-tools) 对于特定于 GTFS 的工具.

- [Remix](http://getremix.com/) - 一个让交通机构轻松规划路线的网络应用程序.
- [AC Transit RestroomFinder](https://github.com/actransitorg/ACTransit.RestroomFinder) - 使用 GPS 和屏幕地图为公交运营商和现场工作人员确定最近的授权洗手间.
- [AC Transit Training and Education Department (TED) application](https://github.com/actransitorg/ACTransit.Training) - 该应用程序支持学区对运输和维修人员的培训操作，主要是在巴士操作员和重型教练机技工（学徒和旅程）的职位上，尽管该系统支持新课程和学徒计划.
- [AC Transit Customer Relations application (CusRel)](https://github.com/actransitorg/ACTransit.CusRel) - 用于客户问题和反馈的公共交通票务系统：带有通知的部门间路由、部门/人员分配、简单的工作流程、票务搜索、预装报告、每日提醒等.
- [TransAM](http://camsys.software/products/transam)  - 公共交通机构的开源资产管理平台. 开源 [on Github](https://github.com/camsys/transam_core).
- [RidePilot](https://github.com/camsys/ridepilot) - 一个开源的计算机辅助调度和调度 (CASD) 软件系统，以满足小型人力服务运输机构的需求（更多信息请参阅 [Cambridge Systematics's marketing site](http://camsys.software/products/ridepilot)).
- [TNExT](https://github.com/ODOT-PTS/TNExT) - Transit Network Explorer Tool (TNExT) 是一个基于 Web 的软件工具，用于可视化、分析和报告俄勒冈州的区域和全州交通网络.
- 路线趋势（[webapp](https://metrotransitmn.shinyapps.io/route-trends/), [GitHub](https://github.com/metrotransit/route-trends)) - 一个 R Shiny 应用程序，用于提取乘客时间序列，并根据 [STL methodology](https://otexts.com/fpp2/stl.html) 和预测，包括基于这些组成部分的不确定性. 由...赞助 [Metro Transit](https://www.metrotransit.org/) （明尼阿波利斯-圣保罗）.
- [TBEST](https://tbest.org/)  - TBEST (Transit Boardings Estimation and Simulation Tool) 致力于开发基于 GIS 的多方面建模、规划和分析工具，将社会经济、土地使用和交通网络数据集成到基于场景的交通乘客的平台中估计和分析. 由佛罗里达州交通部资助. 免费使用，但不是开源的.

### Hardware

实验和生产运输硬件.

- [Bus Tracking GPS](https://github.com/herrdragon/busTrackingGps) - 用于跟踪公交巴士的廉价开源解决方案的迈阿密原型代码.

### Apps

人们在乘坐交通工具时使用的应用程序.

#### Web Apps (open source)
- [Instabus](http://instabus.org)  - 奥斯汀 (CapMetro) 公共交通的实时地图. 完全没有服务器/后端依赖，完全在 GitHub 页面上运行.
- [OpenTripPlanner Client GWT](https://github.com/mecatran/OpenTripPlanner-client-gwt) - 用于 OpenTripPlanner 的基于 Google Web Toolkit 的 Web 界面
- [OpenTripPlanner.js](https://github.com/conveyal/otp.js) - 基于 Javascript 的 OpenTripPlanner 客户端（不再开发中）
- [OTP-UI React Component Library](https://github.com/opentripplanner/otp-ui)  - React Javascript 组件库，可用于构建行程规划器 webapps. 见 [Storybook](http://www.opentripplanner.org/otp-ui) 演示.
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - 基于 Java 的 Web 应用程序，用于生成 GTFS 实时服务警报.
- [HRT BUS Web app](https://github.com/Code4HR/hrt-bus-api) - HRT Bus API 通过应用程序编程接口发布来自 Hampton Roads Transit 的实时巴士数据，供开发人员从中制作应用程序.
- [Transit-Map](https://github.com/vasile/transit-map) - 使用公共交通时间表在地图上为车辆（标记）设置动画的 Web 应用程序，以插入其沿路线（折线）的位置.
- [Transitive.js](https://github.com/conveyal/transitive.js) - 使用 Leaflet 或 D3 创建可自定义的交通路线网络地图图层.
- [Google I/O Transport Tracker](https://github.com/googlemaps/transport-tracker) - 显示谷歌 I/O 会议的班车到达时间，基于开源 [transport-tracker project](https://github.com/googlemaps/transport-tracker) . 注意：要自己实现此功能，您需要一个 [Google Maps APIs Premium Plan license](https://developers.google.com/maps/pricing-and-plans/).
- [1-Click](http://camsys.software/products/1-click)  - 一个虚拟的“旅行聚合器”，汇集了各种可用模式的信息：公共交通、私人、铁路、拼车、拼车、志愿者、辅助交通以及步行和骑自行车. 开源 [on GitHub](https://github.com/camsys/oneclick).
- [Bustime](https://www.bustime.ru)  - 使用 WebSocket 更新进行公共交通实时监控. 开源 [on GitHub](https://github.com/norn/bustime).
- [Transit Tracker](https://transittracker.ca/#/) - 加拿大大蒙特利尔和多伦多的实时车辆位置
- [GTFS Builder](http://nationalrtap.org/Web-Apps/GTFS-Builder)  - 一个免费的基于 Web 的应用程序，可帮助您创建 GTFS 文件. 由国家农村交通援助计划 (RTAP) 维护.
- [Dede](https://dedriver.org)  - 一个独立且通用的乘客信息系统 (PIS) 映射实时运动. 带有 GTFS-Realtime 格式的车辆位置实体的消息馈送或 [Dede app](https://github.com/dancesWithCycles/dede-android) 可以用作数据源.
- [MBTA tile-server](https://github.com/mbta/tile-server) - 用于创建 Docker 容器的脚本，该容器封装了开发用于 MBTA.com 的地图图块所需的所有元素
- [Tiramisu Transit](https://github.com/CMU-RERC-APT/tiramisu3-pr)  - 一款自适应移动交通应用程序，显示由卡内基梅隆大学开发和部署的实时公交车到站信息. 不再维护.

#### Web Apps (closed source)
- [TransitScreen](http://transitscreen.com/) - 所有当地交通选择的自定义实时显示
- [Citylines.co](https://www.citylines.co) - 一个用于绘制交通系统地图的协作平台，重点是其历史演变.
- [Bikeshare Map](http://bikes.oobrien.com/) - 全球所有共享单车站点的状态
- [Bongo](http://ebongo.org)  - 爱荷华市、科拉尔维尔和爱荷华大学的实时交通跟踪. 将三个不同的交通系统组合到一个 UI 中.
- [Brand New Subway](http://jpwright.net/subway/) - 一款交互式交通规划游戏，让玩家可以随心所欲地改变纽约地铁系统.
- [CityMapper Webapp](https://citymapper.com/nyc) - 真正完善的 web 应用程序，带有 30 多个城市的旅行计划和路线状态.
- [YourStop](http://yourstop.info)  - 移动友好的网络应用程序，它使用 GTFS 提要并显示实时和预定的停靠行程. 与 MBTA、YRT/Viva 和马里兰州 MTA 一起推出.
- [DC MetroHero](https://dcmetrohero.com)  - 华盛顿特区的 WMATA Metrorail 和 Metrobus 系统的实时车辆位置和到达和离开信息.  WebApp、Android 和 iOS 应用程序可用.

#### Native Apps (open source)

- OneBusAway 应用程序 - [Android](https://play.google.com/store/apps/details?id=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [Fire Phone](http://www.amazon.com/gp/mas/dl/android?p=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [iOS](https://itunes.apple.com/us/app/onebusaway/id329380089)  [*(source code)*](https://github.com/OneBusAway/onebusaway-ios), [Windows Phone](https://www.microsoft.com/en-us/store/apps/onebusaway/9nblggh0cbd9) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows-phone), [Windows 8](https://www.microsoft.com/en-us/store/apps/onebusaway/9wzdncrdm5pc) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows8), [Google Glass GDK](https://github.com/OneBusAway/onebusaway-android/pull/219) [*(source code)*](https://github.com/OneBusAway/onebusaway-android/pull/219), [Alexa skill](https://www.amazon.com/OneBusAway/dp/B01ELVUYCW/) [*(source code)*](https://github.com/OneBusAway/onebusaway-alexa)
- [OpenTripPlanner Android](https://github.com/CUTR-at-USF/OpenTripPlanner-for-Android/wiki) - 一个Android应用程序 [OpenTripPlanner](http://www.opentripplanner.org/)
- [OpenTripPlanner iOS](https://github.com/opentripplanner/OpenTripPlanner-iOS) - 一个 iOS 应用程序 [OpenTripPlanner](http://www.opentripplanner.org/)
- [opentripplanner-client-library](https://github.com/CUTR-at-USF/opentripplanner-client-library) - Kotlin 多平台库，用于发出 API 请求并解析来自 OpenTripPlanner v2 服务器的响应，以获取旅行计划、自行车租赁信息以及适用于 Android、iOS 和 Web 的服务器元数据.
- [Transportr](https://github.com/grote/Transportr) 一个 Android 应用程序，使用 [public-transport-enabler](https://github.com/schildbach/public-transport-enabler) 为了连接到全球许多不同的运输网络.
- [Offi Directions](https://gitlab.com/oeffi/oeffi) - 一款为欧洲及其他地区的交通当局提供旅行计划、时间表、实时出发时间和中断信息的 Android 应用程序.
- [Trufi App](https://github.com/trufi-association/trufi-app) - 一个跨平台的 Flutter 应用程序，使用 [OpenTripPlanner](http://www.opentripplanner.org/)
- [Dede App](https://github.com/dancesWithCycles/dede-android) - 使任何 Android 手机成为自动车辆定位 (AVL) 设备的应用程序 [Dede](https://dedriver.org) 乘客信息系统（PIS）.
- [MACS Transit Android App](https://github.com/yeSpud/MACSTransitApp)  - 适用于阿拉斯加费尔班克斯 MACS Transit 系统的 Android 设备巴士跟踪器应用程序. 使用 RouteMatch API.
- [Tiramisu Transit](https://github.com/CMU-RERC-APT/tiramisu3-pr#mobile-app-client)  - 一款自适应移动交通应用程序，显示由卡内基梅隆大学开发和部署的实时公交车到站信息. 使用 Ionic 框架编写. 不再维护.

#### Native Apps (closed source)

- [ally](http://www.allyapp.com/)
- [Transit](http://transitapp.com/)
- [CityMapper](https://citymapper.com/)
- [Moovit](http://moovitapp.com/)
- [TransLoc Rider](http://translocrider.com/) - 超过 100 个公交系统的实时公交地图.
- [Transit Display](http://transitdisplay.com/) - 多式联运和实时公交显示软件.
- [Ualabee](https://ualabee.com/company/) - 社区驱动的行程规划器，专注于用户交互，用户可以报告异常、上传图片、编辑公交数据以及与其他乘客聊天.

### SDKs
- [Citymapper SDK](https://citymapper.com/powers) - 允许您为步行、骑自行车、踏板车和过境添加旅程计划和转弯导航到原生 iOS 和 Android 应用程序.

### Visualizations

- [All Transit](https://all-transit.com)  - 使用 Mapbox GL JS、Deck.gl 和 Transitland 的交互式 GTFS 路线和时间表动画（适用于美国城市）.  Github 仓库 [here](https://github.com/kylebarron/all-transit).
- [fastest-bus-analysis-in-the-west](https://github.com/vta/fastest-bus-analysis-in-the-west)  - 一个 python Pandas 脚本，它结合了 Ridership/APC、Swiftly 速度和停留数据、公交车站库存、GTFS 和地理空间形状，以创建逐站、逐路、时间分组可过滤数据集以进行交叉分析. 然后将数据集可视化为 [Tableau](https://public.tableau.com/profile/vivek7797#!/vizhome/stopsandspeedanalyses/Story1) 通过站点合并和专用车道等加速方法，帮助 VTA 规划人员找到使公共汽车和铁路网络更快、更可靠的地方.
- [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz) - 用于 GTFS 数据动画和可视化的 Web 应用程序 [gtfspy](https://github.com/CxAalto/gtfspy).
- [gtfs-visualizations](https://github.com/cmichi/gtfs-visualizations) - 用于可视化 GTFS 数据集路径的开源 NodeJS 应用程序.
- [Mapnificent](https://www.mapnificent.net/)  - 显示您可以在给定时间内乘坐公共交通工具到达的区域. 开源 [on GitHub](https://github.com/mapnificent/mapnificent)，住在 https://www.mapnificent.net/.
- [MIT COAXS](http://mittransportanalyst.github.io/) - 使用基于可访问性的利益相关者参与的公交走廊的共同创意规划（显示使用的路线场景 [OpenTripPlanner Analyst](http://www.opentripplanner.org/analyst/)).
- [MOTIS](https://motis-project.de/) - 多式联运信息系统，包括 [visualization](https://europe.motis-project.de/)
- [MTA Frequency](http://www.tyleragreen.com/maps/new_york/) - 使用建造的纽约市地铁和公共汽车的频率可视化 [Transitland](https://transit.land/).
- [SEPTA Rail OTP Report](https://apps.phor.net/septa/) - 使用 GTFS 的在线准时性能报告和向下钻取工具.
- [TNExT](https://github.com/ODOT-PTS/TNExT) - Transit Network Explorer Tool (TNExT) 是一个基于 Web 的软件工具，用于可视化、分析和报告俄勒冈州的区域和全州交通网络.
- [Toronto Transit Explorer](https://github.com/sidewalklabs/totx)  - 一个 Java 应用程序，可视化多伦多市内的交通、骑自行车和步行可达性. 托管的实时版本 [here](https://totx.sidewalklabs.com/) . 使用修改后的版本 [R5](https://github.com/conveyal/r5) 用于路由.
- [Transit Vis](https://github.com/zackAemmer/transit_vis)  - 一种可视化工具，用于显示源自 King County Metro GTFS-RT feed (OneBusAway API) 的性能指标. 可见 [here](https://www.transitvis.com/) . 用于 [this paper](https://link.springer.com/article/10.1007/s12469-022-00291-7).
- [TransitFlow](https://github.com/transitland/transitland-processing-animation) 使用 Processing 和 Transitland 为世界各地的 GTFS 数据制作动画.
- [TRAVIC Transit Visualization Client](http://tracker.geops.ch/)  - 可视化基于静态 GTFS 数据（有时是实时数据）移动的车辆. 支持260多个城市.  geOps 组织的 Github 帐户是 [here](https://github.com/geops).
- [Traze](https://traze.app/) 经过 [Veridict](https://www.veridict.com)  - 来自世界各地的公共交通车辆的可视化. 与其他用户合作以获取实时更新，即使该机构无法提供. 基于多个来源，包括 GTFS 和 GTFS-RT.  （以前称为 [Livemap24](https://www.livemap24.com)). 
- [Visualizing MBTA Data](http://mbtaviz.github.io/) - 显示人们如何使用波士顿地铁系统的交互式图表.

### GTFS

- [GTFS Spec](https://developers.google.com/transit/gtfs/)  - 通用运输数据馈送规范，或 GTFS. 也可在 [Español](https://developers.google.com/transit/gtfs/?hl=es), [Français](https://developers.google.com/transit/gtfs/?hl=fr).
- [GTFS Best Practices](http://gtfs.org/best-practices/) - GTFS 提要生产者的最佳实践.

#### GTFS Libraries

使使用各种语言的 GTFS 数据变得容易的软件.

##### C
- [CGTFS](https://github.com/rakhack/cgtfs)  - 用于读取静态 GTFS 提要的 C 库. 支持将未打包的提要读入应用程序内存或 SQLite 数据库.
- [RRRR Rapid Real-time Routing](https://github.com/bliksemlabs/rrrr) - RRRR（通常发音为 R4）是 RAPTOR 公共交通路由算法的 C 语言实现.

##### C++
-  [just_gtfs](https://github.com/mapsme/just_gtfs) - 用于读写 GTFS 的 C++17 仅头文件库（用于 [MAPS.ME](https://github.com/mapsme/omim) ）. 主要特点：GTFS提要的快速读写，支持 [extended GTFS route types](https://developers.google.com/transit/gtfs/reference/extended-route-types)，简单地使用 GTFS 日期和时间格式.

##### C#
- [ESRI public-transit-tools](https://github.com/Esri/public-transit-tools) - 在 ArcGIS 中处理公共交通数据的工具（需要 ArcGIS 许可证）.
- [GTFS Feed Parser](https://github.com/OsmSharp/GTFS) - GTFS 解析器的 .Net/Mono 实现.

##### Go
- [Go GTFS Parser](https://github.com/geops/gtfsparser) - Go 的 GTFS 解析库.

##### Java
- [OneBusAway GTFS Modules](https://github.com/OneBusAway/onebusaway-gtfs-modules/wiki) - 基于 Java 的库，用于读取、写入和转换 GTFS 格式的公共交通数据，包括数据库支持.

##### JavaScript
- [gtfs-sequelize](https://github.com/evansiroky/gtfs-sequelize) - 使用 Node.js 库对静态 GTFS 进行建模 [sequelize.js](http://sequelizejs.com/).
- [gtfs-utils](https://github.com/public-transport/gtfs-utils) – 处理 GTFS 数据集的实用程序（例如，“扁平化”`calendar.txt` &amp; `calendar_dates.txt`，计算行程的到达/离开时间）.
- [gtfs-via-postgres](https://github.com/derhuerst/gtfs-via-postgres) – 另一个使用 PostgreSQL 处理 GTFS 的工具.
- [Node-GTFS](https://github.com/BlinkTagInc/node-gtfs)  - 从 GTFS 文件加载传输数据，解压缩并将其存储到 SQLite 数据库. 提供一些查询代理、路线、站点和时间的方法.

##### PostgreSQL
- [gtfs-schema](https://github.com/tyleragreen/gtfs-schema) - GTFS 提要的 PostgreSQL 架构.
- [gtfs-via-postgres](https://github.com/derhuerst/gtfs-via-postgres) – 另一个使用 PostgreSQL 处理 GTFS 的工具.

##### Python
- [combine_gtfs_feeds](https://github.com/psrc/combine_gtfs_feeds) - 一种将多个 gtfs 提要合并到一个提要/数据集中的 Python 工具.
- [ESRI public-transit-tools](https://github.com/Esri/public-transit-tools) - 在 ArcGIS 中处理公共交通数据的工具（需要 ArcGIS 许可证）.
- [gtfsdb](https://github.com/OpenTransitTools/gtfsdb) - 用于将 GTFS 文件转换为关系数据库的 Python 库.
- [gtfslib-python](https://github.com/afimb/gtfslib-python) - python 中的开源库，用于读取 GTFS 文件并计算有关公共交通网络的各种统计数据和指标.
- [gtfsman](https://github.com/geops/gtfsman) - Python 中类似存储库的工具，用于管理和更新大量 GTFS 提要.
- [gtfspy](https://github.com/CxAalto/gtfspy)  - 使用 Python3 进行公共交通网络分析和旅行时间计算. 与 Postgres/PostGIS、Oracle、MySQL 和 SQLite 兼容. 使用者 [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz).
- [GTFS Kit](https://github.com/mrcagney/gtfs_kit)  - 用于分析通用运输饲料规范 (GTFS) 数据的 Python 3.6+ 工具包. 取代 [GTFSTK](https://github.com/araichev/gtfstk).
- [GTFSTK](https://github.com/araichev/gtfstk)  - 用于分析内存中 GTFS 数据的 Python 3 工具包. 使用 Pandas 和 Shapely 来提高速度. 被取代 [GTFS Kit](https://github.com/mrcagney/gtfs_kit).
- [Make GTFS](https://github.com/mrcagney/make_gtfs) - 一个 Python 库，用于根据基本路线信息制作 GTFS 提要.
- [Mapzen GTFS](https://github.com/transitland/mapzen-gtfs) - 一个 Python GTFS 库，支持读取单个 GTFS 表，或构建一个图表来表示提要中的每个机构.
- [multigtfs](https://github.com/tulsawebdevs/django-multi-gtfs) - 一个用于导入和导出 GTFS 的 Django 应用程序.
- [partridge](https://github.com/remix/partridge) - 基于 pandas DataFrames 构建的快速、宽容的 Python GTFS 阅读器.

##### R
- [trread](https://github.com/r-gtfs/trread) - R 的传输 (GTFS) 文件阅读器. 

##### Ruby
- [GTFS-viz](https://github.com/vasile/GTFS-viz) - 将一组 GTFS 文件转换为 SQLite 数据库 + GeoJSON 的 Ruby 脚本（需要 [Transit Map](https://github.com/vasile/transit-map) Web应用程序）

#### GTFS Converters

各种静态计划格式与 GTFS 之间的转换器.

- [Chouette](http://www.chouette.mobi/)  - 转换 French-Transmodel、SIRI、NETeX. 有关更多信息，请参见 Chouette.mobi 网站.
- [extract-gtfs-pathways](https://github.com/derhuerst/extract-gtfs-pathways) – 从 GTFS 数据集中将路径提取为 GeoJSON 的命令行工具.
- [extract-gtfs-shapes](https://github.com/derhuerst/extract-gtfs-shapes) – 从 GTFS 数据集中提取形状为 GeoJSON 的命令行工具.
- [GTFS-OSM-Sync](https://github.com/CUTR-at-USF/gtfs-osm-sync) - 用于同步 GTFS 格式数据的 Java 工具 [OpenStreetMap.org](http://www.openstreetmap.org/).
- [gtfs-service-area](https://github.com/cal-itp/gtfs-service-area)  - 从静态 GTFS 计算中转服务区. 结果作为单层 .geojson 文件输出.  Docker化版本 [gtfs-to-geojson](https://github.com/BlinkTagInc/gtfs-to-geojson).
- [GTFS-route-shapes](https://github.com/kotrc/GTFS-route-shapes) - 一个 Python 脚本，用于为 GTFS 存档中的每条运输路线生成单个 geoJSON 形状.
- [gtfs-to-geojson](https://github.com/BlinkTagInc/gtfs-to-geojson)  - 将 GTFS 形状和站点中的交通数据转换为 geoJSON 的 Javascript 工具. 这对于创建交通路线图很有用.
- [gtfs2gps](https://github.com/ipeaGIT/gtfs2gps) - 一个 R 包，可将 GTFS 格式的公共交通数据转换为“data.table”中类似 GPS 的记录，其中每一行代表每辆车在给定空间分辨率下的时间戳.
- [gtsf](https://github.com/r-gtfs/gtsf) - R中的通用传输（GTFS）简单（地理）特征（sf）可用于通过GDAL将GTFS转换为Shapefile、GeoJSON和其他格式.
- [hafas-generate-gtfs](https://github.com/derhuerst/hafas-generate-gtfs) *(work-in-progress)* – 从 HAFAS 端点生成 GTFS 转储的 Javascript 工具.
- [Hafas2GTFS](https://github.com/geops/hafas2gtfs) - 用 Python 编写的 Hafas2GTFS 转换器，针对 SBB HAFAS 提要进行了优化.
- [kml-to-gtfs-shapes](https://github.com/bdferris/kml-to-gtfs-shapes/tree/gh-pages) - Javascript tool to convert polylines from a KML file into a GTFS shapes.txt file. Hosted on GitHub [here](http://bdferris.github.io/kml-to-gtfs-shapes/).
- [o2g](https://github.com/hiposfer/o2g) - 从 OpenStreetMap 中提取 GTFS 提要的简单工具.
- [Open-Transport SYNTHESE Convertors](https://github.com/Open-Transport/synthese/wiki) - 转换 French-Transmodel、SIRI、NETeX、HAFAS、HASTUS、VDV452 等.
- [onebusaway-gtfs-to-barefoot](https://github.com/OneBusAway/onebusaway-gtfs-to-barefoot) - 一个 Java 工具来创建一个 [Barefoot](https://github.com/bmwcarit/barefoot) 来自 GTFS 文件的映射文件.
- [onebusaway-vdv-modules](https://github.com/OneBusAway/onebusaway-vdv-modules) - 用于处理 VDV 格式的公交数据的 Java 库，包括将 VDV-452 调度数据转换为 GTFS.
- [osm2gtfs](https://github.com/grote/osm2gtfs) - 将 OpenStreetMap 数据和时间表信息转换为 GTFS.
- [transit_model](https://github.com/CanalTP/transit_model) - 一个 Rust 库，可以转换为以下格式：GTFS、NTFS（对于 Navitia，请参阅 [Software for Creating APIs](#software-for-creating-apis)), TransXChange ([UK standard format](http://naptan.dft.gov.uk/transxchange/documentation.htm)), KV1 ([Netherland standard format](http://bison.connekt.nl/standaarden/)) 或 NeTEx ([European standard format](http://netex-cen.eu/)).
- [transloc-gtfs-rectifier](https://github.com/laidig/transloc-gtfs-rectifier) - 尝试将 GTFS stop_ids 分配给的 Python 应用程序 [TransLoc](http://transloc.com/) 使用的 ID [TransLoc's API](https://market.mashape.com/transloc/openapi-1-2) ([TransLoc](http://transloc.com/) 在他们的 API 中没有提供 GTFS `stop_ids`）.
- [Transmodel and IFF to GTFS](https://github.com/bliksemlabs/bliksemintegration)  - 导入和同步（Transmodel）BISON Koppelvlak1，IFF（HP/EDS 编写的格式，有点类似于 ATCO CIF）以导入铁路网络的时间表. 内部伪 NETeX 数据结构允许导出到 GTFS，并且有概念证明可以导出到其他格式，例如 NETeX、GTFS 和 IFF.

#### GTFS Data Collection and Maintenance Tools

- [bus-router](https://github.com/atlregional/bus-router) - 使用路由为 GTFS 生成缺失 shape.txt 的 Python 脚本 [Google Maps Directions API](https://developers.google.com/maps/documentation/directions/) 或者 [OSRM](https://github.com/Project-OSRM/osrm-backend/wiki/Server-api).
- [gtfs-blocks-to-transfers](https://github.com/TransitApp/GTFS-blocks-to-transfers) - 用于转换 GTFS 块的 Python 工具，由设置定义 [trip.block\_id](https://github.com/google/transit/blob/master/gtfs/spec/en/reference.md#example-blocks-and-service-day) 成一系列 [trip-to-trip transfers (proposal)](https://github.com/google/transit/pull/303).
- [GTFS Editor](https://github.com/conveyal/gtfs-editor)  - 一个（自托管）基于 Web 的 GTFS 编辑框架.  （注意：此项目已被弃用，取而代之的是 [IBI Data Tools](https://github.com/ibi-group/datatools-ui).)
- [GTFS Editor for Vagrant](https://github.com/laidig/vagrant-gtfs-editor) - 使用快速设置 GTFS 编辑器（上图） [Vagrant](https://www.vagrantup.com/)
- [static-GTFS-manager](https://github.com/WRI-Cities/static-GTFS-manager) - 一个（自托管）基于浏览器的用户界面，用于创建、编辑、导出静态 GTFS（参见 [related post](https://groups.google.com/forum/#!topic/transit-developers/GFz5rTJTB0I) ）. 现场演示 [here](https://static-gtfs-manager.herokuapp.com/).
- [TransitWand](https://github.com/conveyal/transit-wand)  - 用于收集公交数据的开源网络和移动应用程序. 使用它来创建 GTFS 提要、捕获乘客数量或生成 GIS 数据集.
- [IBI Data Tools](https://github.com/ibi-group/datatools-ui)  - 处理 GTFS 编辑、验证、质量检查和部署到 OpenTripPlanner 的 Web 应用程序.  （结合并建立在已弃用的功能之上 [Gtfs Data Manager](https://github.com/conveyal/gtfs-data-manager) 和 [GTFS Editor](https://github.com/conveyal/gtfs-editor).)
- [GTFS.html](https://gtfs.pleasantprogrammer.com)  - 一个完全基于浏览器的工具，用于查看 GTFS 提要. 用它来查看路线、站点、时间表等.
- [pfaedle](https://github.com/ad-freiburg/pfaedle) - 使用 OpenStreetMap 数据对 GTFS 进行精确的地图匹配
- [GTFS shape mapfit](https://github.com/HSLdevcom/gtfs_shape_mapfit)  - 适合 GTFS 形状文件并停止到给定 OSM 映射文件的 Python 工具. 用途 [pymapmatch](https://github.com/tru-hy/pymapmatch) 为匹配.
- [GTFS Builder](http://nationalrtap.org/Web-Apps/GTFS-Builder)  - 一个免费的基于 Web 的应用程序，可帮助您创建 GTFS 文件. 由国家农村交通援助计划 (RTAP) 维护.
- [gtfs-station-builder](https://github.com/kostjerry/gtfs-station-builder) - 帮助建立车站内部结构的 UI 工具（包括路径.txt）
- [GTFS Text-to-Speech Tester](https://github.com/BlinkTagInc/node-gtfs-tts) - 一个命令行工具，它使用文本到语音朗读 GTFS 停止名称，以确定哪些需要用于 stops.txt 中的 tts_stop_name 的文本到语音值. 

#### GTFS Analysis Tools

- [Peartree](https://github.com/kuanb/peartree) - 用于将公交数据转换为有向图以进行网络分析的 Python 库.
- [gtfsr](https://github.com/ropensci/gtfsr) - 一个 R 包，用于轻松导入、验证和映射遵循通用运输馈送规范 (GTFS) 格式的运输数据.
- [R5: Rapid Realistic Routing on Real-world and Reimagined networks](https://github.com/conveyal/r5)  - Conveyal 为多模式（公交/自行车/步行/汽车）网络开发的基于 Java 的路由引擎. 它目前计划在一个时间窗口内进行多次旅行，以进行场景规划和分析. 一个相关的 R 包装程序包（[r5r](https://github.com/ipeaGIT/r5r/) )由IPEA独立开发. 另见 Higgins 等人的性能比较.  （2022），链接如下.
- [tidytransit](https://github.com/r-transit/tidytransit) （以前 [bustt](https://github.com/r-transit/bustt) ) - 将 GTFS 数据读取到 tidyverse 和简单的特征数据帧中，以绘制公交站点和路线图、计算公交频率并验证公交提要.  tidytransit 是一个 [fork](https://en.wikipedia.org/wiki/Fork_\(software_development\)）  [gtfsr](https://github.com/ropensci/gtfsr), 发布到 [CRAN](https://cran.r-project.org/)，具有频率/时距计算功能. 
- [transitr](https://github.com/tmelliott/transitr) - 用于实时构建和建模交通网络以获得车辆 ETA 的 R 包
- [Busbuzzard](https://github.com/bmander/busbuzzard) - 从关于运输车辆的经验数据推断概率时间表.
- [ESRI ArcGIS Public Transit Tools (GTFS)](https://github.com/Esri/public-transit-tools) - 在 ArcGIS 中处理公共交通数据的工具
- [GTFS-to-Chart](https://github.com/BlinkTagInc/gtfs-to-chart) - 根据 GTFS 数据创建显示运输路线上所有车辆的字符串图表.

#### GTFS Timetable Publishing Tools

- [GTFS-to-HTML](https://gtfstohtml.com) - 直接从 GTFS 生成 HTML 或 PDF 格式的人类可读时间表. 
- [TimeTablePublisher (TTPUB)](https://github.com/OpenTransitTools/ttpub) - 由 TriMet 开发的网络发布系统，允许运输机构检查、修改原始调度数据并将其转换为易于阅读的时间表，以供客户参考

#### GTFS Validators

- [Conveyal's gtfs-validator](https://github.com/conveyal/gtfs-validator) - A Java-based GTFS validator based on the OneBusAway GTFS Modules, runs in Java and is faster than the Google provided one.
- [Conveyal's gtfs-lib](https://github.com/conveyal/gtfs-lib/) - Conveyal 的继任者 [gtfs-validator](https://github.com/conveyal/gtfs-validator)，一个基于 Java 的库，用于通过磁盘支持的存储加载和保存任意大小的 GTFS 提要.
- [Google's feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) - 谷歌支持的基于 Python 的 GTFS 验证器.
- [GTFS Data Package Specification](https://github.com/Stephen-Gates/GTFS) - 一种 [Data Package specification](http://specs.frictionlessdata.io/data-packages/) 验证完成 [Good Tables](http://goodtables.okfnlabs.org/) . 包括数据包、模式、测试，并以昆士兰东南部 GTFS 数据为例.
- [GTFS Meta-Validator (hosted by Omni)](http://gtfsvalidator.omnimodal.io) - 一个基于 Web 的 GTFS 验证器，可同时运行 [the Google Python feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) 和 [Conveyal's gtfs-validator](https://github.com/conveyal/gtfs-validator) 在上传的 GTFS 文件上.
- [gtfstidy](https://github.com/patrickbr/gtfstidy) - 一个基于 Go 的工具，用于整理和验证 GTFS 提要.
- [gtfs-validator-api](https://github.com/cal-itp/gtfs-validator-api) - 这个 Python 包是一个薄包装 [MobilityData/gtfs-validator](https://github.com/MobilityData/gtfs-validator) 它处理生成的中间文件并找到 gtfs-validator 的输出文件，因此可以给它一个特定的名称或作为字符串返回.
- [GTFSVTOR](https://github.com/mecatran/gtfsvtor) - 在 Java 中实现的开源 GTFS 验证器，在 GPLv3 下获得许可，由维护 [Mecatran](https://www.mecatran.com/).
- [MobilityData's gtfs-validator](https://github.com/MobilityData/gtfs-validator) - 一个开源的 GTFS 验证器，规范地遵循在 Java 中实现的 GTFS 规范，在 Apache v2.0 下获得许可，由维护 [MobilityData](https://mobilitydata.org/).
- [Reflect GTFS Validator (hosted by Foursquare ITP)](https://reflect.foursquareitp.com) - 中转时间表和 GTFS 验证平台由 [Foursquare ITP](https://www.foursquareitp.com) 其中包括一个免费的、基于 Web 的 GTFS 验证器，基于 [gtfs-lib](https://github.com/conveyal/gtfs-lib/).
- [Transit App's gtfs-fares-v2-validator](https://github.com/TransitApp/gtfs-fares-v2-validator) - 一个 Python 工具，用于验证 GTFS-Fares-v2 数据，基于 [draft specification](https://docs.google.com/document/d/19j-f-wZ5C_kYXmkLBye1g42U-kvfSVgYLkkG5oyBauY/edit#).
- [Transport Validator](https://github.com/etalab/transport-validator/) - 实现的开源验证器 [Rust](https://www.rust-lang.org/) . 被使用 [French National Access Point](https://transport.data.gouv.fr/validation/).


### GTFS Realtime

- [GTFS-realtime documentation](https://github.com/google/transit/tree/master/gtfs-realtime) . 也可在 [Español](https://github.com/google/transit/tree/master/gtfs-realtime/spec/es).
- [GTFS-realtime Autodoc](https://laidig.github.io/gtfs-rt-autodoc/index.html) - GTFS-realtime自动生成文档，由官方生成 [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto) 并包括一些扩展.

#### GTFS Realtime Libraries & Demo Apps

- [gtfs-realtime-bindings](https://github.com/google/gtfs-realtime-bindings) - 从官方生成的 Java、.NET、Node.js、Python 和 Ruby 的官方绑定 [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto).
- [GTFS-realtime Exporter](https://github.com/OneBusAway/onebusaway-gtfs-realtime-exporter/wiki) - 一个基于 Java 的工具，有助于生成和共享 GTFS-relatime 提要.
- [GTFS-realtime Alerts Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-alerts-producer-demo/wiki) - 一个基于 Java 的演示项目，用于生成 GTFS 实时服务警报.
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - 基于 Java 的 Web 应用程序，用于生成 GTFS 实时服务警报.
- [GTFS-realtime TripUpdates & VehiclePositions Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-trip-updates-producer-demo/wiki) - 一个基于 Java 的演示项目，用于生成 GTFS 实时 TripUpdates（估计到达）和车辆位置.
- [GTFS-realtime Vehicle Positions Consumer/Visualizer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-visualizer) - 一个基于 Java 的演示项目，用于使用 GTFS 实时车辆位置提要并在地图上显示此信息.

#### GTFS Realtime Validators

- [gtfs-realtime-validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator)  - 由南佛罗里达大学城市交通研究中心开发的 GTFS 实时验证工具. 还包括一个集成版本 [gtfs-validator](https://github.com/conveyal/gtfs-validator) 工具.

#### GTFS Realtime (and Other Real-time API) Archival Tools

- [GTFS-realtime to SQL](https://github.com/OpenMobilityData/GtfsRealTimeToSql) - 将 GTFS-RealTime 提要解析为 SQL 数据库（用于 [OpenMobilityData.org](https://openmobilitydata.org))
- [gtfsrdb](https://github.com/CUTR-at-USF/gtfsrdb) - 一个 Python 工具，支持读取和归档 GTFS 实时提要到数据库中
- [retro-gtfs](https://github.com/SAUSy-Lab/retro-gtfs) - 从 Nextbus API 收集实时数据并将其归档为 GTFS 格式（即追溯 GTFS）的 Python 应用程序.

#### GTFS Realtime Convertors

- [SIRI 到 GTFS 实时](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) - 一个基于 Java 的命令行实用程序，用于从 [SIRI format](https://www.siri.org.uk/) 到 GTFS 实时
- [OrbCAD SQL Server to GTFS-realtime](https://github.com/CUTR-at-USF/HART-GTFS-realtimeGenerator/) - 基于 Java 的命令行实用程序，可从 OrbCAD SQL Server 中提取车辆位置和行程更新信息，并将其导出为 GTFS 实时 TripUpdates 和 VehiclePositions 格式.
- [NextBus API to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-nextbus-cli/wiki) - 一个基于 Java 的命令行实用程序，用于从 [NextBus API format](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) 到 GTFS 实时. 请注意，NextBus 现在直接为其产品提供 GTFS 实时 API. 看 [Cubic site](http://nextbus.cubic.com/Products/Real-Time-Rider-Information) 和 [this FAQ](https://medium.com/omnimodal/want-more-riders-open-up-your-nextbus-api-with-gtfs-realtime-7387c80f31e1#.pkuzizhl5).
- [Syncromatics API to GTFS-realtime](https://github.com/CUTR-at-USF/bullrunner-gtfs-realtime-generator) - 一个基于 Java 的命令行实用程序，用于从 [Syncromatics API](http://www.syncromatics.com/) 格式为 GTFS 实时 TripUpdates 和 VehiclePositons.
- [KV6,15,17, and ARNU to GTFS-realtime](https://github.com/bliksemlabs/bliksemintegration-realtime)  - 基于 Java 的工具，用于处理传入的 KV6、15、17 和 ARNU，并将它们与 RID 集成数据库中存在的静态交通数据相匹配. 然后它继续将此数据导出为 ARNU RITinfo、GTFS（实时）和 KV78turbo
- [WMATA BusPositions API to GTFS-realtime](https://github.com/kurtraschke/wmata-gtfsrealtime) - 从 WMATA 转换的基于 Java 的工具 [BusPositions API](https://developer.wmata.com/docs/services/54763629281d83086473f231/operations/5476362a281d830c946a3d68) 和警报 RSS 提要来自 [MetroAlerts](http://www.wmata.com/rider_tools/metro_service_status/rail_bus.cfm?) 到 GTFS 实时 TripUpdates、VehiclePositions 和警报源.
- [SEPTA API 到 GTFS 实时](https://github.com/kurtraschke/septa-gtfsrealtime) - 基于 Java 的转换工具 [SEPTA's](http://www.septa.org/) [real-time bus and rail data](http://www3.septa.org/hackathon/) 到 GTFS 实时
- [CTA API to GTFS-realtime](https://github.com/kurtraschke/ctatt-gtfsrealtime) - 基于 Java 的转换工具 [CTA's](http://www.transitchicago.com/) [Train Tracker data](http://www.transitchicago.com/developers/traintracker.aspx) 到 GTFS 实时.
- [Detroit DOT to GTFS-realtime](https://github.com/prashtx/ddot-avl) - 从中提取实时信息 [DDOT's](http://www.detroitmi.gov/How-Do-I/Locate-Transportation/Bus-Schedules) TransitMaster 安装（数据库）并转换为 GTFS-realtime
- [Live Transit Event Trigger](https://github.com/ipublic/live_transit_event_trigger) - 从中提取数据 [Ride On's](http://www.montgomerycountymd.gov/dot-transit/) OrbCAD 数据库并导出为实时 GTFS.
- [SoundTransit 到 GTFS 实时](https://github.com/bdferris/onebusaway-sound-transit-realtime) - 转换文本文件源 [Sound Transit](http://www.soundtransit.org/) 到 GTFS 实时
- [Civic Transit](https://github.com/jestin/CivicTransit) - Screen-scrapes [KCATA’s](http://www.kcata.org/) TransitMaster WebWatch 安装以生成 GTFS 实时提要.
- [GTFS-realtime VehiclePositions to GTFS-realtime TripUpdates (TransitClock)](http://thetransitclock.org)  - 可以使用原始车辆位置并以 GTFS-realtime 等格式生成预测时间的 Java 应用程序. 以前称为“时空”.
- [gtfs-realtime-translators](https://github.com/Intersection/gtfs-realtime-translators)  - 基于 Python 的工具，用于将自定义到达 API 格式转换为实时 GTFS. 截至 2019 年 7 月，它支持 LA Metro 和 SEPTA.
- [Transloc API to GTFS-realtime](https://github.com/jonathonwpowell/transloc-to-gtfs-real-time) - 基于 Node.js 的工具，用于将 Transloc API 转换为 GTFS-realtime.
- [hafas-gtfs-rt-feed](https://github.com/derhuerst/hafas-gtfs-rt-feed) – 用于从 HAFAS 端点生成 GTFS 实时提要的 Javascript 工具.
- [GTFS-realtime to SIRI-Lite](https://github.com/etalab/transpo-rt/) - 一种 [Rust](https://www.rust-lang.org/) 用于将多个 GTFS-RT 提要转换为 SIRI-Lite API 的网络服务器.

#### GTFS Realtime Utilities

- [bus_kalman](https://github.com/cmoscardi/bus_kalman) - 一个卡尔曼滤波器，用于使用 NYC MTA 实时数据插入公交车行程时间.
- [Concentrate](https://github.com/mbta/concentrate)  - 将来自多个来源的实时交通信息合并到单个输出文件中. 由 [ 维护
马萨诸塞湾交通管理局 (MBTA)](https://github.com/mbta).
- [gtfs-realtime-test-service](https://github.com/CUTR-at-USF/gtfs-realtime-test-service) - 用于模拟 GTFS 实时提要内容的工具（例如，用于测试 GTFS 实时消费应用程序）.
- [GTFS-realtime Munin Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-munin-plugin) - 提供一个 [Munin](http://munin-monitoring.org/) plugin for logging information about a GTFS-realtime feed.
- [GTFS-realtime Nagio Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-nagios-plugin) - 提供一个 [Nagios](https://www.nagios.org/) 用于监控 GTFS 实时提要的插件
- [GTFS-realtime Printer](https://github.com/laidig/gtfs-rt-printer) - 基于 Java 的实用程序，用于从 GTFS 实时文件或 URL 中打印信息.
- [gtfs-rt-admin](https://github.com/conveyal/gtfs-rt-admin) - 用于管理 GTFS-RT 服务警报（JavaScript 和 Java）的管理工具.
- [gtfs-rt-differential-to-full-dataset](https://github.com/derhuerst/gtfs-rt-differential-to-full-dataset) – 用于将“DIFFERENTIAL”增量数据的连续 GTFS 实时流转换为“FULL_DATASET”转储的 Javascript 工具.
- [gtfs-rt-dump](https://github.com/kurtraschke/gtfs-rt-dump) - 将协议缓冲区格式转换为纯文本，以便以纯文本形式轻松查看 GTFS 实时提要（用于调试目的）
- [gtfs-rt-inspector](https://public-transport.github.io/gtfs-rt-inspector/)  – 用于检查和分析任何（启用了 CORS）的 GTFS 实时提要的 Web 应用程序. 开源于 [GitHub](https://github.com/public-transport/gtfs-rt-inspector).
- [GTFS Data Pipeline for TfNSW Bus Datasets](https://github.com/teckkean/GTFS-Data-Pipeline-TfNSW-Bus)  - 为 TfNSW 的 GTFS 静态和实时数据集开发的数据管道. 使用管道生成的数据集已用于通过公共交通信息和优先系统 (PTIPS) 验证 TfNSW 的交通信号优先请求的性能.
- [manual-gtfsrt](https://github.com/pailakka/manual-gtfsrt) - 基于 Go 的工具，提供由可编辑 JSON 创建的 GTFS-RT 提要.
- [print-gtfs-rt-cli](https://github.com/derhuerst/print-gtfs-rt-cli) - 用于从标准输入读取 GTFS 实时提要、打印人类可读或 JSON 格式的 Javascript 工具.
- [transitcast](https://github.com/OpenTransitTools/transitcast)  - 使用 GTFS 和 GTFS-RT 车辆位置馈送生成每个车辆从预定停止移动到预定停止所需的估计转换时间，并记录这些“observed_stop_time”表. 这些记录稍后可用于训练机器学习模型以进行车辆行驶预测. 由 TriMet 创建，作为 [an FTA IMI project](https://trimet.org/imi/program.htm).
- [transit-feed-quality-calculator](https://github.com/CUTR-at-USF/transit-feed-quality-calculator) - 一个使用 [gtfs-realtime-validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator) 评估大量运输提要的质量，从全局目录中获取提要 URL ([TransitFeeds.com/OpenMobilityData.org](https://openmobilitydata.org/)).
- [Transit Network Model](https://github.com/tmelliott/TransitNetworkModel) - 使用 GTFS 实时车辆位置、粒子滤波器和卡尔曼滤波器生成预测的工具. 

### SIRI

- [SIRI API](https://github.com/OneBusAway/onebusaway/wiki/SIRI-Resources) - 从 v1.0 和 v1.3 生成的 Java 类 [SIRI](https://www.siri.org.uk/) 模式.
- [SIRI 2.0 API](https://github.com/laidig/siri-20-java) - 从 v2.0 生成的 Java 类 [SIRI](https://www.siri.org.uk/) 模式.
- [SIRI to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) - 一个基于 Java 的命令行实用程序，用于从 [SIRI format](https://www.siri.org.uk/) 到 GTFS 实时.
- [SIRI 2.0 Autodoc](https://laidig.github.io/siri-20-java/doc/) - 从（非常好）带注释的 SIRI 2.0 模式定义中自动生成文档.
- [King County Metro Legacy AVL to SIRI](https://github.com/bdferris/onebusaway-king-county-metro/tree/master/onebusaway-king-county-metro-legacy-avl-to-siri) - 基于 Java 的转换工具 [King County Metro's](http://metro.kingcounty.gov/) 旧版 AVL 格式转为 SIRI.
- [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki) - 一个开源的 Android 库，用于与 RESTful SIRI 接口进行交互以获取实时交通数据，例如当前正在使用的交通数据 [MTA Bus Time API](http://bustime.mta.info/wiki/Developers/SIRIIntro).
- [SIRI 1.3 POJOs (Android-compatible)](https://github.com/CUTR-at-USF/onebusaway-siri-api-v13-pojos/wiki)  - Android 兼容的普通旧 Java 对象 (POJOS) 用于 SIRI v1.3 API 的数据绑定（反序列化 XML/JSON）响应. 被使用 [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki).
- [pysiri2validator](https://github.com/laidig/pysiri2validator) - 用 Python 3 编写的 SIRI 2.0 的简单验证器.
- [Edwig](https://github.com/af83/edwig) - 用于实时公共交通数据交换的 golang 服务器，使用 SIRI 协议.

### Other multimodal data formats

- [Alliance for Parking Data Standards (APDS)](https://www.allianceforparkingdatastandards.org/) - 由 [International Parking Institute (IPI)](https://www.parking.org/)， 这 [British Parking Association (BPA)](http://www.britishparking.co.uk/), 和 [European Parking Association (EPA)](http://www.europeanparking.eu/) , APDS 是一个非营利组织，其使命是开发、推广、管理和维护统一的全球标准，使组织能够跨全球平台共享停车数据.  APDS 1.0 版文档是 [here](https://www.allianceforparkingdatastandards.org/resources).
- [CurbLR](https://github.com/curblr/curblr-spec) - 路边法规规范.
- [Dyno-Demand](https://github.com/osplanning-data-standards/dyno-demand) - 基于 GTFS 的旅行需求数据格式，专注于个人乘客*需求*，适用于旧金山县交通管理局、LMZ LLC 和 UrbanLabs LLC 开发的动态网络建模.
- [Dyno-Path](https://github.com/osplanning-data-standards/dyno-path) - (Under development - see [this post](https://github.com/osplanning-data-standards/GTFS-PLUS/pull/52#issuecomment-331231000)) 个别乘客*轨迹*的数据.
- [General Bikeshare Feed Specification (GBFS)](https://github.com/NABSA/gbfs) - 由成员开发的实时共享单车信息的开放数据标准 [North American Bikeshare Association (NABSA)](http://nabsa.net/).
    - [gbfs-validator](https://github.com/PierrickP/gbfs-validator) - 验证 GBFS 提要的第 3 方工具.
    - [gbfs R package](https://github.com/ds-civic-data/gbfs) - 与 R 中的 GBFS 提要接口的功能，允许用户为指定的城市/自行车共享程序保存和积累整洁的 .rds 数据集.
- [GTFS-flex](https://github.com/MobilityData/gtfs-flex) - 一种将灵活的公共交通服务建模为 GTFS 扩展的数据格式.
- [GTFS-plus](https://github.com/osplanning-data-standards/GTFS-PLUS) - 一种基于 GTFS 的交通网络格式，用于*车辆和容量数据*，适用于 Puget Sound 地区委员会、UrbanLabs LLC、LMZ LLC 和旧金山县交通管理局开发的动态交通建模.
- [GTFS-ride](https://github.com/ODOT-PTS/GTFS-ride) - 通过俄勒冈州交通部和俄勒冈州立大学合作开发的开放、固定路线过境乘客数据标准.
- [GTFS-stat](https://github.com/osplanning-data-standards/GTFS-STAT) - GTFS 交通网络的扩展，包含由 UrbanLabs LLC 和旧金山县交通管理局开发的性能数据的附加文件.
- [General Modeling Network Specification (GMNS)](https://github.com/zephyr-data-specs/GMNS)  - 一种用于共享可路由道路网络文件的格式，旨在用于多模式静态和动态交通规划和运营模型.  Volpe/FHWA 与 Zephyr 基金会合作.
- [General Travel Network Specification](https://zephyrtransport.org/trb17projects/7-general-travel-network-specification/) - 用于共享旅行需求模型网络的计划数据规范.
- [Managed and Tolled Lanes Feed Specification (MTLFS)](https://github.com/vta/Managed-and-Tolled-Lanes-Feed-Specification) - 提议包含管理和收费车道收费饲料规范 (MTLFS) 的模式，并定义由开发的所有这些文件中使用的字段 [Santa Clara Valley Transportation Authority](http://www.vta.org/).
- [Mobility as a Service API](http://maas-api.org/) - 一组定义 MaaS 兼容 API 的开放文档和测试套件（例如， [MaaS Transport Service Provider Booking API](https://github.com/maasglobal/maas-tsp-api/blob/master/specs/Booking.md)).
- [Mobility Data Specification (MDS)](https://github.com/openmobilityfoundation/mobility-data-specification)  - 一种为市政当局和作为服务提供商的移动性实施实时数据共享、测量和监管的格式. 它旨在确保政府有能力强制执行、评估和管理提供者. 由维护 [Open Mobility Foundation](https://www.openmobilityfoundation.org/).
- [NCHRP 08-119 Developing Data Standards and Guidance for Transportation Planning and Traffic Operations - Phase 1 (Anticipated)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4543) - 本研究的目的是制定标准和/或指南，供交通界在收集、管理和共享交通规划和运营的静态和实时数据时使用和采用.
- [NeTex](http://netex-cen.eu/) - 一种通用 XML 格式，设计用于在由管理的分布式系统之间交换复杂的静态传输数据 [CEN standards process](https://www.cen.eu/work/ENdev/how/Pages/default.aspx).
- [OMX: The Open Matrix data file format](https://github.com/osPlanning/omx) - 二维数组对象和相关元数据的结构化集合，可能用于交通建模行业.
- [Open Sales and Distribution Model (OSDM)](https://github.com/UnionInternationalCheminsdeFer/OSDM)  - 旨在大幅简化铁路旅行客户的预订流程，并降低分销商和铁路运营商的复杂性和分销成本. 包含离线模型和在线 API 的规范. 由维护 [International Union of Railways (UIC)](https://github.com/UnionInternationalCheminsdeFer).
- [SAE Shared and Digital Mobility Committee](http://articles.sae.org/15799/) - 似乎正在为汽车共享和交通网络公司 (TNC) / 拼车制定数据标准.
- [shared-row](https://github.com/d-wasserman/shared-row) - SharedStreets 参考的通行权 (ROW) 规范.
- [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120)  - 本研究的目的是为参与提供需求响应运输的实体制定交易数据的技术规范. 预计完成日期为 2018 年底.
- [TIDES project](https://groups.google.com/forum/#!forum/tidesproject) - 公交 ITS 数据交换规范 (TIDES) 是一项提议的努力，旨在为历史公交 ITS 数据（包括 AVL、APC 和 AFC 数据）创建标准数据结构、API 和数据管理工具.
- [Cal-ITP Operational Data Standard (ODS)](https://docs.calitp.org/operational-data-standard/) - 旨在解决缺乏标准格式来表示司机、调度员和规划人员用于执行交通运营的交通时间表的问题. 
- [Transport Operator Mobility-as-a-service Provider (TOMP)-API](https://github.com/TOMP-WG/TOMP-API) - 荷兰的工作组，目标是开发一种 API，供运输运营商和移动即服务提供商使用，用于运营商发现、旅行计划、最终用户交互、预订和支付.

### Resources

与开放交通数据相关的在线课程、博客文章和报告.

#### On-line courses

- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) - 一个免费的在线自学课程，用于学习 GTFS 和实时 GTFS.
- [Open Transit Data Toolkit](http://transitdatatoolkit.com/) - 一系列帮助人们利用开放交通数据的课程.
- [MBTA GTFS Onboarding](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb)  - MBTA 为 GTFS 静态创建的交互式教程. 一种 [stand-alone Docker image](https://github.com/mbta/gtfs_onboarding) 可在 GitHub 以及 [hosted/no-install version](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb) Jupyter 笔记本.
- [Planetizen "Building a Transit Map Web App" course](https://courses.planetizen.com/course/building-transit-map-app) - 关于设置您自己的基于 Web 的地图应用程序的视频教程，无需编码经验. 

#### Blog posts

- [When(ish) is my bus? Data and code](https://github.com/mjskay/when-ish-is-my-bus)  - Whenish 背后的数据和代码 (R) 是我的公共汽车吗？ 数据包括三天的历史车辆位置和调查结果.
- ["Legacy AVL system? It's okay, join the club." by Kurt Raschke](https://kurtraschke.com/2015/01/legacy-avl-export) - 讨论将遗留 AVL 系统数据转换为 GTFS 实时格式的选项.
- ["GTFS Best Practices now available!" by Sean Barbeau](https://medium.com/@sjbarbeau/gtfs-best-practices-now-available-88ac67194233) - 讨论开放数据格式的一些挑战，如 GTFS 和 2017 年初推出的 GTFS 最佳实践，以帮助解决数据质量问题.
- ["What's new in GTFS-realtime v2.0" by Sean Barbeau](https://medium.com/@sjbarbeau/whats-new-in-gtfs-realtime-v2-0-cd45e6a861e9) - 讨论 GTFS-realtime v1.0 的不足和 v2.0 的改进.
- ["AVL, CAD, and Real-Time Passenger Info for Beginners" by Tony Laidig](http://transitdata.net/avl-cad-and-real-time-passenger-info-for-beginners/) - 提供用于跟踪车辆的技术的一般介绍.
- ["Visualizing Better Transportation: Data & Tools" by Steve Pepple](https://medium.com/@stevepepple/visualizing-better-transportation-data-tools-e48b8317a21c) - 旧金山湾区和北美其他城市的交通相关数据和工具集合，最初是在旧金山 ARUP 的 2018 年交通周活动中收集和讨论的.
- ["How to use GTFS data to track transit vehicles in realtime" by Tom Camp](https://www.ably.io/blog/gtfs-data-track-transit-vehicles-realtime) - 使用 GTFS 和 GTFS Realtime 提供持续的实时更新.

#### Academic papers

- [Tang et al. - "Ridership effects of real-time bus information system: A case study in the City of Chicago"](https://www.sciencedirect.com/science/article/pii/S0968090X12000022) - 在伊利诺伊州芝加哥进行的实验表明，当乘客通过短信或电子邮件访问实时信息时，乘客人数略有增加.
- [Kay et al. - "When(ish) is my bus? User-centered Visualizations of Uncertainty in Everyday, Mobile Predictive Systems"](http://faculty.washington.edu/jhullman/busUncertaintyVis.pdf)  - 论文试图回答“我们如何在过境预测中传达不确定性？”的问题. 解释问题、现有解决方案并设计一个 [better interface for letting users know when to arrive at the bus stop](https://github.com/mjskay/when-ish-is-my-bus/blob/master/quantile-dotplots.md#quantile-dotplots).
- [Watkins et al. - "Where Is My Bus? Impact of mobile real-time information on the perceived and actual wait time of transit riders"](https://www.sciencedirect.com/science/article/pii/S0965856411001030) - 在 Seatl,e WA 进行的实验表明，当乘客可以通过移动应用程序访问实时信息时，他们会感觉到更短的公交车等待时间.
- [Brakewood et al. - “An experiment evaluating the impacts of real-time transit information on bus riders in Tampa, Florida”](https://www.sciencedirect.com/science/article/pii/S0965856414002146)  - 佛罗里达州坦帕市的对照实验表明，通过移动应用程序访问实时信息的乘客与没有实时信息的乘客相比，等待时间减少了近 2 分钟. 拥有实时信息的骑手也减少了焦虑和沮丧，并更好地接受了代理.
- [Brakewood et al. - "The impact of real-time information on bus ridership in New York City"](https://www.sciencedirect.com/science/article/pii/S0968090X15000297) - 纽约市的实验表明，当向乘客提供实时信息时，长途路线上的乘客量会增加.
- [Brakewood and Watkins - "A literature review of the passenger benefits of real-time transit information"](https://www.tandfonline.com/doi/full/10.1080/01441647.2018.1472147?scroll=top&needAccess=true) (2018) - 许多不同研究的概述，这些研究着眼于实时交通信息的好处.
- [Gramacki et al. - "gtfs2vec - Learning GTFS Embeddings for comparing Public Transport Offer in Microregions"](https://github.com/CUTR-at-USF/awesome-transit/blob/master/2021)  - 使用 Uber 的 H3 空间指数和机器学习来识别城市公共交通服务质量“相似”的区域. 可用的源代码 [on GitHub](https://github.com/pwr-inf/gtfs2vec).
- [Higgins et al. - "Calculating place-based transit accessibility: Methods, tools and algorithmic dependence" (2022)](https://doi.org/10.5198/jtlu.2022.2012) - 比较用于计算步行和公共交通可达性的软件工具，包括 ArcGIS Pro、Emme、R5R 和 OpenTripPlanner.
- [Aemmer et al. - "Measurement and classification of transit delays using GTFS-RT data"](https://link.springer.com/article/10.1007/s12469-022-00291-7)  - 提出了一种从通用交通馈送规范的实时 (GTFS-RT) 组件中提取交通性能指标并将它们聚合到道路段的方法. 与 [Transit Vis](https://github.com/zackAemmer/transit_vis), 可见 [here](https://www.transitvis.com/).

#### Government reports
- [APTA Policy Development and Research - Public Transportation Embracing Open Data](http://www.apta.com/resources/reportsandpublications/Documents/APTA-Embracing-Open-Data.pdf) - APTA 对开放交通数据的好处和挑战的讨论（以下 TCRP 报告的简短摘要）.
- [TCRP Synthesis 115 - Open Data: Challenges and Opportunities for Transit Agencies](http://onlinepubs.trb.org/Onlinepubs/tcrp/tcrp_syn_115.pdf) (2015) - 一份关于开放交通数据的好处和挑战的综合报告.
- [TCRP Research Report 213: Data Sharing Guidance for Public Transit Agencies – Now and in the Future](http://www.trb.org/Main/Blurbs/180188.aspx) (2020) - 一份旨在帮助机构做出共享数据决策的报告，包括如何评估收益、成本和风险.
- [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120)  - 本研究的目的是为参与提供需求响应运输的实体制定交易数据的技术规范. 预计完成日期为 2018 年底.

#### Community-maintained lists
- [Vendors Providing GTFS Creation/Maintenance services](https://docs.google.com/spreadsheets/u/1/d/1Gc9mu4BIYC8ORpv2IbbVnT3q8VQ3xkeY7Hz068vT_GQ/pubhtml) - 添加新的供应商 [here](http://goo.gl/forms/YDbPSPmufS).
- [Entities Providing Transportation Software Development Consulting Services](https://docs.google.com/spreadsheets/u/1/d/1n44CNMCK1vt1nyrsdYz-KD_hYxUMNIm6Me69M6ROBIg/pubhtml) - 添加新实体 [here](http://goo.gl/forms/cc6kcVERuP).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Luqmaan Dawoodjee](https://github.com/luqmaan) 和 [Center for Urban Transportation Research](https://www.cutr.usf.edu/) at the [University of South Florida](http://www.usf.edu/) 已放弃本作品的所有版权和相关或邻接权.

## About

最初由 [Luqmaan Dawoodjee](https://github.com/luqmaan)，现在由 [Center for Urban Transportation Research](https://www.cutr.usf.edu/) at the [University of South Florida](http://www.usf.edu/).

此列表旨在作为仅供参考的社区资源 - 项目/产品的列表并不意味着认可.
