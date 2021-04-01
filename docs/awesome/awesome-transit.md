<div class="github-widget" data-repo="CUTR-at-USF/awesome-transit"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-transit [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![RSS](https://img.shields.io/badge/Subscribe-RSS-blue.svg)](https://github.com/CUTR-at-USF/awesome-transit/commits/master.atom)

##### Community list of transit APIs, apps, datasets, research, and software :bus::star2::train::star2::steam_locomotive:

有什么要添加或更改的吗？ 打开一个 [pull request](https://github.com/CUTR-at-USF/awesome-transit/pulls) 或者 [issue](https://github.com/CUTR-at-USF/awesome-transit/issues).

------------------------------



### Getting started

如果这是您第一次处理过境数据，则可能会发现以下链接有用：

- [GTFS](https://developers.google.com/transit/gtfs/)  -GTFS供稿是一组文本文件，其中包含不经常更改的公交数据，例如停靠点，路线，行程和其他时间表数据. 运输机构通常每几个月更新一次GTFS Feed.
- [GTFS Realtime](https://developers.google.com/transit/gtfs-realtime/)  -GTFS Realtime由三个二进制文件组成，这些文件包含实时车辆位置，实时到达信息和服务警报. 运输机构通常每分钟更新一次这些文件.
- [OpenMobilityData](https://openmobilitydata.org/)  （以前的TransitFeeds）-来自世界各地的GTFS / GTFS实时数据Feed列表. 如果您想获取某个代理商的实时数据，这是一个很好的起点.
- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) -免费的，在线的，自定进度的课程，用于学习GTFS和实时GTFS.
- [Open Transit Data Toolkit](http://transitdatatoolkit.com/) -一系列帮助人们利用开放式公交数据的课程.
- [MBTA GTFS Onboarding](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb)  -MBTA为GTFS static创建的交互式教程. 一个 [stand-alone Docker image](https://github.com/mbta/gtfs_onboarding) 可在GitHub以及 [hosted/no-install version](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb) Jupyter笔记本.


### Community

提问和寻找其他社区资源的地方.

- [TransitWiki](http://transitwiki.org)  -交通规划人员的社区Wiki. 像这个仓库，但更好.
- [MobilityData Slack chat](https://mobilitydata-io.herokuapp.com/)
- [Transit Developers mailing list](https://groups.google.com/forum/#!forum/transit-developers)
-OneBusAway
  - [OneBusAway User mailing list](http://groups.google.com/group/onebusaway-users)
  - [OneBusAway Developers mailing list](http://groups.google.com/group/onebusaway-developers)
  - [OneBusAway API mailing list](http://groups.google.com/group/onebusaway-api)
  - [OneBusAway Slack chat](https://onebusaway.herokuapp.com/)
- [Transit Techies NYC](https://transittechies.nyc/) -基于NYC的聚会，对对此仓库感兴趣的人. [Speaker list](https://transittechies.nyc/past) 包括此仓库的许多贡献者.

### Data

访问GTFS以及其他过境和多式联运数据的集合的地方

#### 3rd party GTFS URL directories
- [Transitland](https://transit.land/)  -许多运输机构GTFS数据集的社区可编辑列表. 还提供了以JSON / GeoJSON形式访问数据的API，并提供了一个操场来试用数据.
- [OpenMobilityData](https://openmobilitydata.org/) -GTFS和 [GTFS-RT](https://openmobilitydata.org/search?q=gtfsrt) 饲料. [Archives 和 validates](https://openmobilitydata.org/p/capital-metro/24) GTFS供稿，并允许您预览 [GTFS](https://openmobilitydata.org/p/capital-metro/24/latest) 和 [GTFS-RT](https://openmobilitydata.org/p/capital-metro/495) 通过浏览器.
- [~~GTFS Data Exchange~~ (Deprecated)](http://www.gtfs-data-exchange.com/agencies)  -以前是GTFS供稿网址的权威目录. 在2016年关闭.但可应要求提供2008年至2016年的93 GB数据.

#### Transit agency data archives
- [CapMetrics](https://github.com/scascketta/CapMetrics)  -奥斯汀的运输代理（CapMetro）的历史车辆位置. 数据收集者 [capmetricsd](https://github.com/scascketta/capmetricsd)，一个Go守护程序.

#### National government datasets
- [National Transit Database (USA)](https://www.transit.dot.gov/ntd) -由美国联邦运输管理局（Federal Transit Administration）管理的有关美国运输系统的信息和统计数据.
- [Transport (France)](https://transport.data.gouv.fr/) -法国公交系统的GTFS数据集.
- [European long-distance transport operators (EU) *(Unofficial)*](https://github.com/public-transport/european-transport-operators) -可用API端点，GTFS提要和客户端库的非正式列表

#### Proprietary (non-standard) vendor APIs
- [Transport API](https://www.transportapi.com/)  -REST API，用于英国的汇总运输数据. 收费访问.
- [TransLoc OpenAPI](https://market.mashape.com/transloc/openapi-1-2) -REST API，用于购买了TransLoc的AVL硬件和软件的美国60多个运输系统的实时车辆，路线，站点和到达数据.
- [NextBus API](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) -REST API，用于购买了NextBus硬件和/或软件的代理商的实时车辆，路线，停靠点和到达数据.
- [Navitia.io](http://www.navitia.io/) -REST API，用于行程计划，停车时间表，isocrhons，以及美国和欧盟的更多信息. [Navitia](https://github.com/CanalTP/navitia) 是实时API背后的开源引擎.
- [CityBikes](http://api.citybik.es)  -REST API，用于汇总来自世界各地的bikeshare数据. 供电 [pyBikes](https://github.com/eskerda/pybikes).
- [HAFAS](https://de.wikipedia.org/wiki/HAFAS) –专有的公共交通管理软件 [HaCon](https://www.hacon.de) ([list of endpoints](https://gist.github.com/derhuerst/2b7ed83bfa5f115125a5))

#### Crowdsourced transit data
- [Citylines.co](https://www.citylines.co)  -绘制公交系统地图的协作平台，重点是其历史演变. 数据可以从GeoJSON或CSV下载 [citylines.co/data](https://www.citylines.co/data).
- [OpenStreetMap (OSM)](https://www.openstreetmap.org) -用于绘制世界地图的协作平台，包括运输，运输和路由数据.

### Software for Creating APIs

可以设置为提供用于传输和多模式数据的API的软件.

- [OneBusAway](http://onebusaway.org/) -使用GTFS和GTFS-Realtime（以及 [other formats](https://github.com/OneBusAway/onebusaway-application-modules/wiki/Real-Time-Data-Configuration-Guide)），并将它们变成易于使用 [REST API](http://developer.onebusaway.org/modules/onebusaway-application-modules/current/api/where/index.html).
- [OpenTripPlanner](http://www.opentripplanner.org/) -一个用于多模式和多机构旅程计划的开源平台，以及返回有关多模式图的信息（使用GTFS和 [OpenStreetMap](http://www.openstreetmap.org/)).
- [TransitClock](http://thetransitclock.org)  -可以消耗原始车辆位置并以GTFS-realtime之类的格式生成预测时间的Java应用程序. 前身为“运输时间”.
- [Linked Connections](http://linkedconnections.org/)  -开源的，可扩展的多式联运路线计划引擎，该引擎允许客户端执行路线计划算法（与服务器相反）. 使用GTFS数据.
- [TransiCast](http://www.transicast.com/)  -以单一，集成的呼叫和响应格式提供北美地区的公共交通数据. 数据以流可解析的XML和JSON格式提供. 开源 [Google Code](https://code.google.com/archive/p/rasa/) . 托管版本在www.transitcast.com [requires payment](http://www.transicast.com/coststructure.html).
- [gtfs-server](https://github.com/denysvitali/gtfs-server) -用Rust编写的Web服务器，它使用PostGIS作为后端通过HTTP端点提供GTFS数据
- [Navitia](https://github.com/CanalTP/navitia) 是背后的开源引擎 [Navitia.io](http://www.navitia.io/) 实时API.
- [pyBikes](https://github.com/eskerda/pybikes) -软件供电 [CityBikes](http://api.citybik.es) 有关全球自行车共享系统的信息
- [hafas-rest-api](https://github.com/public-transport/hafas-rest-api) –暴露一个 [HAFAS](https://de.wikipedia.org/wiki/HAFAS) 端点作为REST API.
- [GraphHopper Routing Engine](https://github.com/graphhopper/graphhopper/#public-transit)  OpenStreetMap的开源路由引擎. 用作Java库或服务器.

### Agency Tools

公交机构的工具. 也可以看看 [GTFS Data Collection and Maintenance Tools](#gtfs-data-collection-and-maintenance-tools) 适用于GTFS的工具.

- [Remix](http://getremix.com/) -一个网络应用程序，可让运输公司轻松地规划路线.
- [AC Transit RestroomFinder](https://github.com/actransitorg/ACTransit.RestroomFinder) -使用GPS和屏幕上的地图，为公交运营商和现场工作人员确定最近的授权洗手间.
- [AC Transit Training and Education Department (TED) application](https://github.com/actransitorg/ACTransit.Training) -尽管该系统支持新课程和学徒计划，但该应用程序支持学区对运输和维护员工的培训操作，主要是在公共汽车操作员和重型教练机修工（学徒和旅程）中担任.
- [AC Transit Customer Relations application (CusRel)](https://github.com/actransitorg/ACTransit.CusRel) -用于客户问题和反馈的公交票务系统：部门间路由与通知，部门/人员分配，简单的工作流程，票务搜索，预先罐装报告，每日提醒等.
- [TransAM](http://camsys.software/products/transam)  -公共交通机构的开源资产管理平台. 开源 [on Github](https://github.com/camsys/transam_core).
- [RidePilot](https://github.com/camsys/ridepilot) -开源的计算机辅助计划和调度（CASD）软件系统，可满足小型人力服务运输机构的需求（有关更多信息，请参阅 [Cambridge Systematics's marketing site](http://camsys.software/products/ridepilot)).
- [TNExT](https://github.com/ODOT-PTS/TNExT) -公交网络浏览器工具（TNExT）是基于网络的软件工具，旨在对俄勒冈州的区域和州范围的公交网络进行可视化，分析和报告.
-路线趋势（[webapp](https://metrotransitmn.shinyapps.io/route-trends/), [GitHub](https://github.com/metrotransit/route-trends)）-一个R Shiny应用程序，用于提取乘车时间序列，并根据以下信息返回季节，趋势和残差分量 [STL methodology](https://otexts.com/fpp2/stl.html) 以及包括这些成分的不确定性在内的预测. 由...赞助 [Metro Transit](https://www.metrotransit.org/) （明尼阿波利斯-圣保罗）.
- [TBEST](https://tbest.org/)  -TBEST（过境登机估算和模拟工具）致力于开发基于GIS的多方面建模，规划和分析工具，该工具将社会经济，土地使用和过境网络数据集成到一个基于场景的过境乘客的平台中估计和分析. 由佛罗里达州交通运输部资助. 免费使用，但不开放源代码.

### Hardware

实验和生产运输硬件.

- [Bus Tracking GPS](https://github.com/herrdragon/busTrackingGps) -迈阿密代码，用于跟踪公交车的廉价开源解决方案的原型.

### Apps

人们在乘搭交通工具时使用的应用程式.

#### Web Apps (open source)
- [Instabus](http://instabus.org)  -奥斯汀（CapMetro）公共交通的实时地图. 完全不依赖服务器/后端，完全在GitHub页面上运行.
- [OpenTripPlanner Client GWT](https://github.com/mecatran/OpenTripPlanner-client-gwt) -用于OpenTripPlanner的基于Google Web Toolkit的Web界面
- [OpenTripPlanner.js](https://github.com/conveyal/otp.js) -OpenTripPlanner的基于Javascript的客户端（已不再开发）
- [OTP-UI React Component Library](https://github.com/opentripplanner/otp-ui)  -React Javascript组件库，可用于构建旅行计划者webapp. 见 [Storybook](http://www.opentripplanner.org/otp-ui) 进行演示.
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) -用于产生GTFS实时服务警报的基于Java的Web应用程序.
- [HRT BUS Web app](https://github.com/Code4HR/hrt-bus-api) -HRT总线API通过应用程序编程接口从Hampton Roads Transit发布实时总线数据，供开发人员从中制作应用程序.
- [Transit-Map](https://github.com/vasile/transit-map) -Web应用程序，使用公共交通工具的时间表在地图上为车辆（标记）添加动画效果，以插补其在路线（折线）上的位置.
- [Transitive.js](https://github.com/conveyal/transitive.js) -使用Leaflet或D3创建公交路线的可自定义网络地图图层.
- [Google I/O Transport Tracker](https://github.com/googlemaps/transport-tracker) -根据开放源代码显示Google I / O会议的班车到达时间 [transport-tracker project](https://github.com/googlemaps/transport-tracker) . 注意：要自己实施此操作，您需要 [Google Maps APIs Premium Plan license](https://developers.google.com/maps/pricing-and-plans/).
- [1-Click](http://camsys.software/products/1-click)  -一个虚拟的“旅行聚合器”，可在各种可用模式下收集信息：公共交通，私人，铁路，乘车共享，拼车，志愿者，辅助公交以及步行和骑自行车. 开源 [on GitHub](https://github.com/camsys/oneclick).
- [Bustime](https://www.bustime.ru)  -通过WebSocket更新进行公共交通实时监控. 开源 [on GitHub](https://github.com/norn/bustime).
- [Transit Tracker](https://transittracker.ca/#/) -加拿大大蒙特利尔和多伦多的实时车辆位置
- [GTFS Builder](http://nationalrtap.org/Web-Apps/GTFS-Builder)  -一个免费的基于Web的应用程序，可帮助您创建GTFS文件. 由国家农村交通援助计划（RTAP）维护.
- [Dede](https://dedriver.org)  -映射实时运动的独立且通用的乘客信息系统（PIS）. 带有GTFS-实时格式或“车辆位置”实体的消息提要 [Dede app](https://github.com/dancesWithCycles/dede-android) 可用作数据源.
- [MBTA tile-server](https://github.com/mbta/tile-server) -用于创建Docker容器的脚本，该容器封装了开发地图图块以在MBTA.com上使用所必需的所有元素

#### Web Apps (closed source)
- [TransitScreen](http://transitscreen.com/) -所有本地交通选择的自定义实时显示
- [Citylines.co](https://www.citylines.co) -绘制公交系统地图的协作平台，重点是其历史演变.
- [Bikeshare Map](http://bikes.oobrien.com/) -全球所有自行车共享站的状态
- [Bongo](http://ebongo.org)  -对爱荷华市，科拉维尔和爱荷华大学的实时公交跟踪. 将三个不同的运输系统组合到一个UI中.
- [Brand New Subway](http://jpwright.net/subway/) -互动交通规划游戏，玩家可以根据自己的喜好改变NYC地铁系统.
- [CityMapper Webapp](https://citymapper.com/nyc) -真正完善的webapp，带有旅行计划器和路线状态，适用于30多个城市.
- [YourStop](http://yourstop.info)  -移动友好的Web应用程序，使用GTFS提要并显示实时和计划的停靠行程. 与MBTA，YRT / Viva和马里兰MTA一起推出.
- [DC MetroHero](https://dcmetrohero.com)  -华盛顿特区WMATA Metrorail和Metrobus系统的实时车辆位置以及到达和离开的信息. 提供WebApp，Android和iOS应用程序.

#### Native Apps (open source)

-OneBusAway应用- [Android](https://play.google.com/store/apps/details?id=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [Fire Phone](http://www.amazon.com/gp/mas/dl/android?p=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [iOS](https://itunes.apple.com/us/app/onebusaway/id329380089)  [*(source code)*](https://github.com/OneBusAway/onebusaway-iphone), [Windows Phone](https://www.microsoft.com/en-us/store/apps/onebusaway/9nblggh0cbd9) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows-phone), [Windows 8](https://www.microsoft.com/en-us/store/apps/onebusaway/9wzdncrdm5pc) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows8), [Google Glass GDK](https://github.com/OneBusAway/onebusaway-android/pull/219) [*(source code)*](https://github.com/OneBusAway/onebusaway-android/pull/219), [Alexa skill](https://www.amazon.com/OneBusAway/dp/B01ELVUYCW/) [*(source code)*](https://github.com/OneBusAway/onebusaway-alexa)
- [OpenTripPlanner Android](https://github.com/CUTR-at-USF/OpenTripPlanner-for-Android/wiki) -适用于 [OpenTripPlanner](http://www.opentripplanner.org/)
- [OpenTripPlanner iOS](https://github.com/opentripplanner/OpenTripPlanner-iOS) -适用于的iOS应用 [OpenTripPlanner](http://www.opentripplanner.org/)
- [Transportr](https://github.com/grote/Transportr) 使用以下内容的Android应用 [public-transport-enabler](https://github.com/schildbach/public-transport-enabler) 为了连接到世界各地许多不同的运输网络.
- [Offi Directions](https://gitlab.com/oeffi/oeffi) -一个Android应用程序，可为欧洲及其他地区的运输当局提供行程计划，时间表，实时出发时间和交通中断信息.
- [Trufi App](https://github.com/trufi-association/trufi-app) 使用以下内容的跨平台Flutter应用程序 [OpenTripPlanner](http://www.opentripplanner.org/)
- [Dede App](https://github.com/dancesWithCycles/dede-android) -一款使任何Android手机供电的应用都可以成为以下应用的自动车辆定位（AVL）设备： [Dede](https://dedriver.org) 旅客信息系统（PIS）.

#### Native Apps (closed source)

- [ally](http://www.allyapp.com/)
- [Transit](http://transitapp.com/)
- [CityMapper](https://citymapper.com/)
- [Moovit](http://moovitapp.com/)
- [Tiramisu Transit](http://www.tiramisutransit.com/)
- [TransLoc Rider](http://translocrider.com/) -超过100个公交系统的实时公交地图.
- [Transit Display](http://transitdisplay.com/) -多模式实时公交显示软件.

### Visualizations

- [Visualizing MBTA Data](http://mbtaviz.github.io/) -互动图表，显示人们如何使用波士顿的地铁系统.
- [MIT COAXS](http://mittransportanalyst.github.io/) -使用基于可访问性的涉众参与，共同设计过境走廊（显示使用 [OpenTripPlanner Analyst](http://www.opentripplanner.org/analyst/)).
- [TRAVIC Transit Visualization Client](http://tracker.geops.ch/)  -根据静态GTFS数据（有时是实时数据）可视化行驶的车辆. 支持260多个城市.  geOps组织的Github帐户是 [here](https://github.com/geops).
- [MTA Frequency](http://www.tyleragreen.com/maps/new_york/) -使用以下工具构建的纽约市地铁和公共汽车的频率可视化 [Transitland](https://transit.land/).
- [Traze](https://traze.app/) 经过 [Veridict](https://www.veridict.com)  -可视化来自世界各地的公共交通工具. 即使代理商无法提供实时更新，也可以与其他用户协作以获取实时更新. 基于许多资​​源，包括GTFS和GTFS-RT.  （以前称为 [Livemap24](https://www.livemap24.com)). 
- [SEPTA Rail OTP Report](https://apps.phor.net/septa/) -使用GTFS的在线实时绩效报告和深入分析工具.
- [TransitFlow](https://github.com/transitland/transitland-processing-animation) 使用Processing和Transitland对全球的GTFS数据进行动画处理.
- [All Transit](https://all-transit.com)  -使用Mapbox GL JS，Deck.gl和Transitland的交互式GTFS路线和时间表动画（适用于美国城市）.  Github仓库 [here](https://github.com/kylebarron/all-transit).
- [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz) -使用以下工具对GTFS数据进行动画和可视化的Web应用程序 [gtfspy](https://github.com/CxAalto/gtfspy).
- [Mapnificent](https://www.mapnificent.net/)  -显示您在给定时间内可以搭乘公共交通工具到达的区域. 开源 [on GitHub](https://github.com/mapnificent/mapnificent)，请访问https://www.mapnificent.net/.
- [Toronto Transit Explorer](https://github.com/sidewalklabs/totx)  -一个Java应用程序，可视化多伦多市内的交通，骑行和步行辅助功能. 直播版 [here](https://totx.sidewalklabs.com/) . 使用的修改版本 [R5](https://github.com/conveyal/r5) 用于路由.
- [fastest-bus-analysis-in-the-west](https://github.com/vta/fastest-bus-analysis-in-the-west)  -结合了Ridership / APC，Swiftly速度和驻留数据，公交车站库存，GTFS和地理空间形状的python Pandas脚本，以逐站，逐路线，按时间分组的可过滤数据集进行交叉分析. 然后将数据集可视化为 [Tableau](https://public.tableau.com/profile/vivek7797#!/vizhome/stopsandspeedanalyses/Story1) 通过停车站合并和专用车道等提速方法，帮助VTA规划人员找到使公交和铁路网络更快，更可靠的场所.
- [TNExT](https://github.com/ODOT-PTS/TNExT) -公交网络浏览器工具（TNExT）是基于网络的软件工具，旨在对俄勒冈州的区域和州范围的公交网络进行可视化，分析和报告.

### GTFS

- [GTFS Spec](https://developers.google.com/transit/gtfs/)  -通用公交数据Feed或GTFS的规范. 也可以在 [Español](https://developers.google.com/transit/gtfs/?hl=es), [Français](https://developers.google.com/transit/gtfs/?hl=fr).
- [GTFS Best Practices](http://gtfs.org/best-practices/) -GTFS提要的生产者的最佳实践.

#### GTFS Libraries

可轻松使用各种语言来使用GTFS数据的软件.

#### C
- [CGTFS](https://github.com/rakhack/cgtfs)  -用于读取静态GTFS提要的C库. 支持将解压缩的提要读取到应用程序内存或SQLite数据库中.
- [RRRR Rapid Real-time Routing](https://github.com/bliksemlabs/rrrr) -RRRR（通常称为R4）是RAPTOR公共交通路由算法的C语言实现.

#### C++
-  [just_gtfs](https://github.com/mapsme/just_gtfs) -用于读取和写入GTFS的C ++ 17仅限标头的库（用于 [MAPS.ME](https://github.com/mapsme/omim) ）. 主要功能：快速读取和写入GTFS提要，支持 [extended GTFS route types](https://developers.google.com/transit/gtfs/reference/extended-route-types)，可轻松使用GTFS日期和时间格式.

#### C#
- [ESRI public-transit-tools](https://github.com/Esri/public-transit-tools) -在ArcGIS中处理公共交通数据的工具（需要ArcGIS许可）.
- [GTFS Feed Parser](https://github.com/OsmSharp/GTFS) -GTFS解析器的.Net / Mono实现.

#### Go
- [Go GTFS Parser](https://github.com/geops/gtfsparser) -Go的GTFS解析库.

#### Java
- [GTFS to SQL](https://github.com/OpenMobilityData/GtfsToSql) -将GTFS供稿解析到SQL数据库（用于 [OpenMobilityData](https://openmobilitydata.org/)).
- [OneBusAway GTFS Modules](https://github.com/OneBusAway/onebusaway-gtfs-modules/wiki) -基于Java的库，用于读取，写入和转换GTFS格式的公交数据，包括数据库支持.
- [R5: Rapid Realistic Routing on Real-world and Reimagined networks](https://github.com/conveyal/r5)  -基于Java的路由引擎，用于多模式（公交/自行车/步行/汽车）网络. 目前，它出于分析目的在一个时间窗口内计划许多行程，但最终可能支持点对点的行程计划.
- [SQL to GTFS](https://github.com/OpenMobilityData/SqlToGtfs) -将使用“ GtfsToSql”生成的SQLite文件转换回压缩的GTFS文件.

#### JavaScript
- [gtfs-sequelize](https://github.com/evansiroky/gtfs-sequelize) -Node.js库使用以下方式为静态GTFS建模 [sequelize.js](http://sequelizejs.com/).
- [gtfs-utils](https://github.com/public-transport/gtfs-utils) –处理GTFS数据集的实用程序（例如，“展平”“ calendar.txt”和“ calendar_dates.txt”，计算旅行的到达/离开时间）.
- [gtfs-via-postgres](https://github.com/derhuerst/gtfs-via-postgres) –另一个使用PostgreSQL处理GTFS的工具.
- [Node-GTFS](https://github.com/BlinkTagInc/node-gtfs)  -从GTFS文件加载运输数据，将其解压缩并将其存储到SQLite数据库. 提供一些查询代理商，路线，站点和时间的方法.

#### PostgreSQL
- [gtfs-schema](https://github.com/tyleragreen/gtfs-schema) -GTFS供稿的PostgreSQL模式.
- [gtfs-via-postgres](https://github.com/derhuerst/gtfs-via-postgres) –另一个使用PostgreSQL处理GTFS的工具.

#### Python
- [ESRI public-transit-tools](https://github.com/Esri/public-transit-tools) -在ArcGIS中处理公共交通数据的工具（需要ArcGIS许可）.
- [gtfsdb](https://github.com/OpenTransitTools/gtfsdb) -用于将GTFS文件转换为关系数据库的Python库.
- [gtfslib-python](https://github.com/afimb/gtfslib-python) -python中的开放源代码库，用于读取GTFS文件并计算有关公共交通网络的各种统计信息和指标.
- [gtfsman](https://github.com/geops/gtfsman) -Python中类似于存储库的工具，用于管理和更新大量的GTFS提要.
- [gtfspy](https://github.com/CxAalto/gtfspy)  -使用Python3的公共交通网络分析和旅行时间计算. 与Postgres / PostGIS，Oracle，MySQL和SQLite兼容. 使用者 [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz).
- [GTFS Kit](https://github.com/mrcagney/gtfs_kit)  -用于分析通用运输提要规范（GTFS）数据的Python 3.6+工具套件. 取代 [GTFSTK](https://github.com/araichev/gtfstk).
- [GTFSTK](https://github.com/araichev/gtfstk)  -一个Python 3工具包，用于分析内存中的GTFS数据. 使用Pandas和Shapely来提高速度. 被取代 [GTFS Kit](https://github.com/mrcagney/gtfs_kit).
- [Make GTFS](https://github.com/mrcagney/make_gtfs) -一个Python库，用于根据基本路线信息制作GTFS供稿.
- [Mapzen GTFS](https://github.com/transitland/mapzen-gtfs) -一个Python GTFS库，它支持读取单个GTFS表或构造一个图表来表示Feed中的每个代理商.
- [multigtfs](https://github.com/tulsawebdevs/django-multi-gtfs) - A Django application to import and export GTFS.
- [partridge](https://github.com/remix/partridge) -基于pandas DataFrames的快速，宽容的Python GTFS阅读器.

#### R
- [trread](https://github.com/r-gtfs/trread) -R的运输（GTFS）文件阅读器. 

#### Ruby
- [GTFS-viz](https://github.com/vasile/GTFS-viz) -将一组GTFS文件转换为SQLite数据库+ GeoJSON的Ruby脚本（ [Transit Map](https://github.com/vasile/transit-map) Web应用程序）

#### GTFS Converters

从各种静态计划格式到GTFS的转换器.

- [Transmodel and IFF to GTFS](https://github.com/bliksemlabs/bliksemintegration)  -导入并同步（转换模型）BISON Koppelvlak1，IFF（HP / EDS编写的格式，有点类似于ATCO CIF）以导入铁路网的时间表. 内部伪NETeX数据结构允许导出到GTFS，并且有概念证明可以导出到其他格式，例如NETeX，GTFS和IFF.
- [Open-Transport SYNTHESE Convertors](https://github.com/Open-Transport/synthese/wiki) -转换French-Transmodel，SIRI，NETeX，HAFAS，HASTUS，VDV452等.
- [Chouette](http://www.chouette.mobi/)  -转换French-Transmodel，SIRI，NETeX. 有关更多信息，请参见Chouette.mobi网站.
- [osm2gtfs](https://github.com/grote/osm2gtfs) -将OpenStreetMap数据和时间表信息转换为GTFS.
- [GTFS-OSM-Sync](https://github.com/CUTR-at-USF/gtfs-osm-sync) -Java工具，用于与GTFS格式的数据同步 [OpenStreetMap.org](http://www.openstreetmap.org/).
- [onebusaway-gtfs-to-barefoot](https://github.com/OneBusAway/onebusaway-gtfs-to-barefoot) -使用Java工具创建 [Barefoot](https://github.com/bmwcarit/barefoot) GTFS文件中的mapfile.
- [o2g](https://github.com/hiposfer/o2g) -从OpenStreetMap提取GTFS提要的简单工具.
- [transloc-gtfs-rectifier](https://github.com/laidig/transloc-gtfs-rectifier) -尝试将GTFS stop_id分配给的Python应用程序 [TransLoc](http://transloc.com/) ID使用 [TransLoc's API](https://market.mashape.com/transloc/openapi-1-2) ([TransLoc](http://transloc.com/) 在其API中未提供GTFS`stop_ids`）.
- [Hafas2GTFS](https://github.com/geops/hafas2gtfs) -用Python编写的Hafas2GTFS转换器，已针对SBB HAFAS提要进行了优化.
- [hafas-generate-gtfs](https://github.com/derhuerst/hafas-generate-gtfs) *（正在执行）*] –一种从HAFAS端点生成GTFS转储的Javascript工具.
- [gtsf](https://github.com/r-gtfs/gtsf) -R中的通用运输（GTFS）简单（地理）功能（sf）可用于通过GDAL将GTFS转换为Shapefile，GeoJSON和其他格式.
- [transit_model](https://github.com/CanalTP/transit_model) -Rust库，可将其转换为以下格式：GTFS，NTFS（有关Navitia，请参见 [Software for Creating APIs](#software-for-creating-apis)），TransXChange（[UK standard format](http://naptan.dft.gov.uk/transxchange/documentation.htm)），KV1（[Netherland standard format](http://bison.connekt.nl/standaarden/)）或NeTEx（[European standard format](http://netex-cen.eu/)).
- [onebusaway-vdv-modules](https://github.com/OneBusAway/onebusaway-vdv-modules) -Java库，用于处理VDV格式的运输数据，包括将VDV-452计划数据转换为GTFS.
- [gtfs-to-geojson](https://github.com/BlinkTagInc/gtfs-to-geojson)  -Javascript工具，可将运输数据转换为GTFS形状并停止为geoJSON. 这对于创建运输路线图很有用.
- [extract-gtfs-shapes](https://github.com/derhuerst/extract-gtfs-shapes) –用于从GTFS数据集中将形状提取为GeoJSON的命令行工具.
- [extract-gtfs-pathways](https://github.com/derhuerst/extract-gtfs-pathways) –用于从GTFS数据集中提取路径作为GeoJSON的命令行工具.
- [gtfs-service-area](https://github.com/cal-itp/gtfs-service-area)  -从静态GTFS计算运输服务区域. 结果以单层.geojson文件输出. 的Dockerized版本 [gtfs-to-geojson](https://github.com/BlinkTagInc/gtfs-to-geojson).

#### GTFS Data Collection and Maintenance Tools

- [bus-router](https://github.com/atlregional/bus-router) -使用以下命令为GTFS生成缺少的shapes.txt的Python脚本 [Google Maps Directions API](https://developers.google.com/maps/documentation/directions/) 或者 [OSRM](https://github.com/Project-OSRM/osrm-backend/wiki/Server-api).
- [GTFS Editor](https://github.com/conveyal/gtfs-editor) 基于Web的GTFS编辑框架（自托管）.  （注意：不建议使用此项目， [IBI Data Tools](https://github.com/ibi-group/datatools-ui).)
- [GTFS Editor for Vagrant](https://github.com/laidig/vagrant-gtfs-editor) 使用以下命令快速设置GTFS编辑器（如上） [Vagrant](https://www.vagrantup.com/)
- [static-GTFS-manager](https://github.com/WRI-Cities/static-GTFS-manager) -基于（自托管）浏览器的用户界面，用于创建，编辑和导出静态GTFS（请参见 [related post](https://groups.google.com/forum/#!topic/transit-developers/GFz5rTJTB0I) ）. 现场演示 [here](https://static-gtfs-manager.herokuapp.com/).
- [TransitWand](http://transitwand.com/)  -用于收集运输数据的开源Web和移动应用程序. 使用它来创建GTFS提要，捕获乘客数量或生成GIS数据集.
- [IBI Data Tools](https://github.com/ibi-group/datatools-ui)  -处理GTFS编辑，验证，质量检查以及部署到OpenTripPlanner的Web应用程序.  （结合并基于已弃用的功能 [Gtfs Data Manager](https://github.com/conveyal/gtfs-data-manager) 和 [GTFS Editor](https://github.com/conveyal/gtfs-editor).)
- [GTFS.html](https://gtfs.pleasantprogrammer.com)  -完全基于浏览器的工具来查看GTFS提要. 用它来查看路线，站点，时间表等.
- [pfaedle](https://github.com/ad-freiburg/pfaedle) -使用OpenStreetMap数据进行GTFS的精确地图匹配
- [GTFS shape mapfit](https://github.com/HSLdevcom/gtfs_shape_mapfit)  -适合GTFS形状文件并停止到给定OSM映射文件的Python工具. 用途 [pymapmatch](https://github.com/tru-hy/pymapmatch) 进行匹配.
- [GTFS Builder](http://nationalrtap.org/Web-Apps/GTFS-Builder)  -一个免费的基于Web的应用程序，可帮助您创建GTFS文件. 由国家农村交通援助计划（RTAP）维护.
- [gtfs-station-builder](https://github.com/kostjerry/gtfs-station-builder) -UI工具可帮助构建站点的内部结构（包括paths.txt）

#### GTFS Analysis Tools

- [Peartree](https://github.com/kuanb/peartree) -一个Python库，用于将运输数据转换为有向图以进行网络分析.
- [gtfsr](https://github.com/ropensci/gtfsr) -一个R包，用于轻松导入，验证和映射遵循通用运输提要规范（GTFS）格式的运输数据.
- [tidytransit](https://github.com/r-transit/tidytransit) （以前 [bustt](https://github.com/r-transit/bustt) ）-将GTFS数据读取到tidyverse和简单要素数据框中，以绘制公交站点和路线图，计算公交频率并验证公交信息.  tidytransit是一个 [fork](https://en.wikipedia.org/wiki/Fork_\(software_development\)）  [gtfsr](https://github.com/ropensci/gtfsr)，发布到 [CRAN](https://cran.r-project.org/)，具有频率/车距计算功能. 
- [transitr](https://github.com/tmelliott/transitr) -用于实时构建和建模公交网络以获取车辆ETA的R包
- [Busbuzzard](https://github.com/bmander/busbuzzard) -从有关过境车辆的经验数据中推断出概率计划.
- [ESRI ArcGIS Public Transit Tools (GTFS)](https://github.com/Esri/public-transit-tools) -在ArcGIS中处理公共交通数据的工具

#### GTFS Timetable Publishing Tools

- [GTFS to HTML](https://github.com/BlinkTagInc/gtfs-to-html) -A直接从GTFS运输数据中以HTML格式创建易于理解的，用户友好的运输时间表. 
- [TimeTablePublisher (TTPUB)](https://github.com/OpenTransitTools/ttpub) -由TriMet开发的网络发布系统，该系统允许运输公司检查，修改原始时间表数据并将其转换为易于阅读的时间表，以提供客户信息.

#### GTFS Validators

- [feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) -Google支持的基于Python的GTFS验证器.
- [gtfs-validator](https://github.com/conveyal/gtfs-validator) -基于OneBusAway GTFS模块的GTFS验证程序，以Java运行，并且比Google提供的验证程序更快.
- [gtfs-lib](https://github.com/conveyal/gtfs-lib/) -Conveyal的继任者gtfs-validator，这是一个用于通过磁盘支持的存储来加载和保存任意大小的GTFS提要的库.
- [GTFS Data Package Specification](https://github.com/Stephen-Gates/GTFS) - 一个 [Data Package specification](http://specs.frictionlessdata.io/data-packages/) 通过完成验证 [Good Tables](http://goodtables.okfnlabs.org/) . 包括数据包，模式，测试，并以东南昆士兰州GTFS数据为例.
- [Web GTFS Meta-Validator (hosted by Omni)](http://gtfsvalidator.omnimodal.io) -基于网络的GTFS验证器，可同时运行 [feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) 和 [gtfs-validator](https://github.com/conveyal/gtfs-validator) 在上传的GTFS文件上.
- [gtfs-validator](https://github.com/MobilityData/gtfs-validator) -以Java实作的开放原始码GTFS验证器，由Apache v2.0授权，并由 [MobilityData](https://mobilitydata.org/).
- [gtfs-validator-api](https://github.com/cal-itp/gtfs-validator-api) -该python软件包是MobilityData / gtfs-validator的一个瘦包装，该包装处理生成的中间文件并查找gtfs-validator的输出文件，因此可以为其指定特定名称或以字符串形式返回.
- [GTFSVTOR](https://github.com/mecatran/gtfsvtor) -以Java实作的开放原始码GTFS验证器，并由GPLv3授权 [Mecatran](https://www.mecatran.com/).
- [Transport Validator](https://github.com/etalab/transport-validator/) - An open-source validator implemented in [Rust](https://www.rust-lang.org/) . 由 [French National Access Point](https://transport.data.gouv.fr/validation/).

#### GTFS Realtime

- [GTFS-realtime documentation](https://github.com/google/transit/tree/master/gtfs-realtime) . 也可以在 [Español](https://github.com/google/transit/tree/master/gtfs-realtime/spec/es).
- [GTFS-realtime Autodoc](https://laidig.github.io/gtfs-rt-autodoc/index.html) -自动生成的GTFS实时文档，由官方生成 [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto) 并包括一些扩展名.

#### GTFS Realtime Libraries & Demo Apps

- [gtfs-realtime-bindings](https://github.com/google/gtfs-realtime-bindings) -从官方生成的Java，.NET，Node.js，Python和Ruby的官方绑定 [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto).
- [GTFS-realtime Exporter](https://github.com/OneBusAway/onebusaway-gtfs-realtime-exporter/wiki) -一个基于Java的工具，可帮助产生和共享GTFS相关时间供稿.
- [GTFS-realtime Alerts Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-alerts-producer-demo/wiki) -一个基于Java的演示项目，用于生成GTFS实时服务警报.
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) -用于产生GTFS实时服务警报的基于Java的Web应用程序.
- [GTFS-realtime TripUpdates & VehiclePositions Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-trip-updates-producer-demo/wiki) -一个基于Java的演示项目，用于生成GTFS实时TripUpdate（估计到达）和车辆位置.
- [GTFS-realtime Vehicle Positions Consumer/Visualizer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-visualizer/wiki) -一个基于Java的演示项目，用于使用GTFS实时车辆位置提要，并在地图上显示此信息.

#### GTFS Realtime Validators

- [gtfs-realtime-validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator)  -由南佛罗里达大学城市交通研究中心开发的GTFS实时验证工具. 还包括集成版本 [gtfs-validator](https://github.com/conveyal/gtfs-validator) 工具.

#### GTFS Realtime (and Other Real-time API) Archival Tools

- [GTFS-realtime to SQL](https://github.com/OpenMobilityData/GtfsRealTimeToSql) -将GTFS-RealTime供稿解析到SQL数据库（用于 [OpenMobilityData.org](https://openmobilitydata.org))
- [gtfsrdb](https://github.com/CUTR-at-USF/gtfsrdb) -一个Python工具，支持将GTFS实时提要读取和存档到数据库中
- [retro-gtfs](https://github.com/SAUSy-Lab/retro-gtfs) -一个Python应用程序，它从Nextbus API收集实时数据并将其归档为GTFS格式（即追溯性GTFS）.

#### GTFS Realtime Convertors

- [SIRI 到GTFS实时](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) -基于Java的命令行实用程序，可从 [SIRI format](http://user47094.vs.easily.co.uk/siri/) 到GTFS实时
- [OrbCAD SQL Server to GTFS-realtime](https://github.com/CUTR-at-USF/HART-GTFS-realtimeGenerator/) -基于Java的命令行实用程序，可从OrbCAD SQL Server中提取车辆位置和行程更新信息，并将其导出为GTFS实时TripUpdates和VehiclePositions格式.
- [NextBus API to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-nextbus-cli/wiki) -基于Java的命令行实用程序，可从 [NextBus API format](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) 到GTFS实时. 请注意，NextBus现在直接为其产品提供GTFS实时API. 看 [Cubic site](http://nextbus.cubic.com/Products/Real-Time-Rider-Information) 和 [this FAQ](https://medium.com/omnimodal/want-more-riders-open-up-your-nextbus-api-with-gtfs-realtime-7387c80f31e1#.pkuzizhl5).
- [Syncromatics API to GTFS-realtime](https://github.com/CUTR-at-USF/bullrunner-gtfs-realtime-generator) -基于Java的命令行实用程序，可从 [Syncromatics API](http://www.syncromatics.com/) 格式转换为GTFS实时的TripUpdates和VehiclePositons.
- [KV6,15,17, and ARNU to GTFS-realtime](https://github.com/bliksemlabs/bliksemintegration-realtime)  -基于Java的工具，用于处理传入的KV6、15、17和ARNU，并将其与RID集成数据库中存在的静态公交数据进行匹配. 然后将其导出为ARNU RITinfo，GTFS（realtime）和KV78turbo
- [WMATA BusPositions API to GTFS-realtime](https://github.com/kurtraschke/wmata-gtfsrealtime) -从WMATA转换为基于Java的工具 [BusPositions API](https://developer.wmata.com/docs/services/54763629281d83086473f231/operations/5476362a281d830c946a3d68) 和警报RSS源 [MetroAlerts](http://www.wmata.com/rider_tools/metro_service_status/rail_bus.cfm?) 到GTFS实时的TripUpdates，VehiclePositions和Alerts feed.
- [SEPTA API 到GTFS实时](https://github.com/kurtraschke/septa-gtfsrealtime) -基于Java的工具进行转换 [SEPTA's](http://www.septa.org/) [real-time bus and rail data](http://www3.septa.org/hackathon/) 到GTFS实时
- [CTA API to GTFS-realtime](https://github.com/kurtraschke/ctatt-gtfsrealtime) -基于Java的工具进行转换 [CTA's](http://www.transitchicago.com/) [Train Tracker data](http://www.transitchicago.com/developers/traintracker.aspx) 到GTFS实时.
- [Detroit DOT to GTFS-realtime](https://github.com/prashtx/ddot-avl) -从中提取实时信息 [DDOT's](http://www.detroitmi.gov/How-Do-I/Locate-Transportation/Bus-Schedules) TransitMaster安装（数据库）并实时转换为GTFS
- [Live Transit Event Trigger](https://github.com/ipublic/live_transit_event_trigger) -从中提取数据 [Ride On's](http://www.montgomerycountymd.gov/dot-transit/) OrbCAD数据库并实时导出为GTFS.
- [SoundTransit 到GTFS实时](https://github.com/bdferris/onebusaway-sound-transit-realtime) -转换来自的文本文件提要 [Sound Transit](http://www.soundtransit.org/) 到GTFS实时
- [Civic Transit](https://github.com/jestin/CivicTransit) -屏幕刮 [KCATA’s](http://www.kcata.org/) 安装TransitMaster WebWatch即可生成GTFS实时供稿.
- [GTFS-realtime VehiclePositions to GTFS-realtime TripUpdates (TransitClock)](http://thetransitclock.org)  -可以消耗原始车辆位置并以GTFS-realtime之类的格式生成预测时间的Java应用程序. 前身为“运输时间”.
- [gtfs-realtime-translators](https://github.com/Intersection/gtfs-realtime-translators)  -基于Python的工具，可将自定义到达API格式转换为GTFS-实时. 自2019年7月起，它支持LA Metro和SEPTA.
- [Transloc API to GTFS-realtime](https://github.com/jonathonwpowell/transloc-to-gtfs-real-time) -基于Node.js的工具，可将Transloc API实时转换为GTFS.
- [hafas-gtfs-rt-feed](https://github.com/derhuerst/hafas-gtfs-rt-feed) –一种从HAFAS端点生成GTFS实时提要的Javascript工具.
- [GTFS-realtime to SIRI-Lite](https://github.com/etalab/transpo-rt/) - 一个 [Rust](https://www.rust-lang.org/) 网络服务器将多个GTFS-RT提要转换为SIRI-Lite API.

#### GTFS Realtime Utilities

- [gtfs-rt-dump](https://github.com/kurtraschke/gtfs-rt-dump) -将协议缓冲区格式转换为纯文本，以便于以纯文本形式轻松查看GTFS实时供稿（用于调试目的）
- [GTFS-realtime Printer](https://github.com/laidig/gtfs-rt-printer) -基于Java的实用程序，用于从GTFS实时文件或URL中打印出信息.
- [gtfs-rt-inspector](https://public-transport.github.io/gtfs-rt-inspector/)  –用于检查和分析任何（启用CORS的）GTFS Realtime提要的Web应用程序. 开源 [GitHub](https://github.com/public-transport/gtfs-rt-inspector).
- [print-gtfs-rt-cli](https://github.com/derhuerst/print-gtfs-rt-cli) –使用Javascript工具从stdin读取GTFS Realtime提要，以人类可读的方式打印或以JSON格式输出.
- [GTFS-realtime Munin Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-munin-plugin) -提供一个 [Munin](http://munin-monitoring.org/) 用于记录有关GTFS实时供稿信息的插件.
- [GTFS-realtime Nagio Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-nagios-plugin) -提供一个 [Nagios](https://www.nagios.org/) plugin for monitoring a GTFS-realtime feed
- [GTFS-realtime-test-service](https://github.com/CUTR-at-USF/gtfs-realtime-test-service) -模拟GTFS实时供稿内容的工具（例如，用于测试GTFS实时使用的应用程序）.
- [gtfs-rt-differential-to-full-dataset](https://github.com/derhuerst/gtfs-rt-differential-to-full-dataset) –使用Javascript工具将“ DIFFERENTIAL”增量数据的连续GTFS实时流转换为“ FULL_DATASET”转储.
- [gtfs-rt-admin](https://github.com/conveyal/gtfs-rt-admin) -用于管理GTFS-RT服务警报（JavaScript和Java）的管理工具.
- [manual-gtfsrt](https://github.com/pailakka/manual-gtfsrt) -基于Go的工具，可提供通过可编辑JSON创建的GTFS-RT提要.
- [Transit Network Model](https://github.com/tmelliott/TransitNetworkModel) -使用GTFS实时VehiclePositions，粒子过滤器和卡尔曼过滤器生成预测的工具.
- [bus_kalman](https://github.com/cmoscardi/bus_kalman) -卡尔曼滤波器，用于使用NYC MTA实时数据来插补公交车的行驶时间.

### SIRI

- [SIRI API](https://github.com/OneBusAway/onebusaway/wiki/SIRI-Resources) -从v1.0和v1.3生成的Java类 [SIRI](http://user47094.vs.easily.co.uk/siri/) 模式.
- [SIRI 2.0 API](https://github.com/laidig/siri-20-java) -从v2.0生成的Java类 [SIRI](http://user47094.vs.easily.co.uk/siri/) 模式.
- [SIRI to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) -基于Java的命令行实用程序，可从 [SIRI format](http://user47094.vs.easily.co.uk/siri/) 到GTFS实时.
- [SIRI 2.0 Autodoc](https://laidig.github.io/siri-20-java/doc/) -从（令人难以置信的）带注释的SIRI 2.0架构定义中自动生成的文档.
- [King County Metro Legacy AVL to SIRI](https://github.com/bdferris/onebusaway-king-county-metro/tree/master/onebusaway-king-county-metro-legacy-avl-to-siri) -基于Java的工具进行转换 [King County Metro's](http://metro.kingcounty.gov/) 旧版AVL格式转换为SIRI.
- [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki) -一个开放源代码的Android库，用于与RESTful SIRI接口进行交互以获取实时交通数据，例如当前由 [MTA Bus Time API](http://bustime.mta.info/wiki/Developers/SIRIIntro).
- [SIRI 1.3 POJOs (Android-compatible)](https://github.com/CUTR-at-USF/onebusaway-siri-api-v13-pojos/wiki)  -Android兼容的Plain Old Java Object（POJOS），用于SIRI v1.3 API的数据绑定（反序列化XML / JSON）响应. 由 [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki).
- [pysiri2validator](https://github.com/laidig/pysiri2validator) -使用Python 3编写的SIRI 2.0的简单验证器.
- [Edwig](https://github.com/af83/edwig) -使用SIRI协议进行实时公共交通数据交换的golang服务器.

### Other multimodal data formats

- [GTFS-flex](https://github.com/MobilityData/gtfs-flex) -一种数据格式，可将灵活的公共交通服务建模为GTFS的扩展.
- [NeTex](http://netex-cen.eu/) -一种通用XML格式，设计用于在由Microsoft管理的分布式系统之间交换复杂的静态传输数据. [CEN standards process](https://www.cen.eu/work/ENdev/how/Pages/default.aspx).
- [General Bikeshare Feed Specification (GBFS)](https://github.com/NABSA/gbfs) -由会员开发的实时自行车共享信息的开放数据标准 [North American Bikeshare Association (NABSA)](http://nabsa.net/).
    - [gbfs-validator](https://github.com/PierrickP/gbfs-validator) -第三方工具，用于验证GBFS供稿.
    - [gbfs R package](https://github.com/ds-civic-data/gbfs) -与R中的GBFS提要接口的功能，允许用户保存和累积指定城市/自行车共享程序的整齐.rds数据集.
- [GTFS-ride](https://github.com/ODOT-PTS/GTFS-ride) -通过俄勒冈州交通运输部和俄勒冈州立大学之间的合作伙伴关系开发的开放式，固定路线的过境乘车数据标准.
- [Managed and Tolled Lanes Feed Specification (MTLFS)](https://github.com/vta/Managed-and-Tolled-Lanes-Feed-Specification) -关于包含托管和收费车道收费提要规范（MTLFS）并定义由以下人员开发的所有这些文件中使用的字段的架构的提案： [Santa Clara Valley Transportation Authority](http://www.vta.org/).
- [GTFS-plus](https://github.com/osplanning-data-standards/GTFS-PLUS) -由Puget Sound地区委员会，UrbanLabs LLC，LMZ LLC和旧金山县交通管理局开发的，适用于动态交通模型的，基于* GTFS的交通和车辆数据格式.
- [Dyno-Demand](https://github.com/osplanning-data-standards/dyno-demand) -基于GTFS的旅行需求数据格式，重点关注由旧金山县交通管理局，LMZ LLC和UrbanLabs LLC开发的适用于动态网络建模的单个乘客*需求*.
- [Dyno-Path](https://github.com/osplanning-data-standards/dyno-path) -（正在开发中-请参见 [this post](https://github.com/osplanning-data-standards/GTFS-PLUS/pull/52#issuecomment-331231000)）个人乘客*轨迹*的数据.
- [GTFS-stat](https://github.com/osplanning-data-standards/GTFS-STAT) -GTFS传输网络的扩展，其中包含包含UrbanLabs LLC和San Francisco County Transportation Authority开发的性能数据的其他文件.
- [TIDES project](https://groups.google.com/forum/#!forum/tidesproject) -公交ITS数据交换规范（TIDES）是一项提议的工作，旨在为历史公交ITS数据（包括AVL，APC和AFC数据）创建标准数据结构，API和数据管理工具.
- [SAE Shared and Digital Mobility Committee](http://articles.sae.org/15799/) - Appears to be working on a data standard for car share and transportation network companies (TNCs) / rideshare.
- [City of Los Angeles Mobility Data Specification (MDS)](https://github.com/CityOfLosAngeles/mobility-data-specification)  -一种格式，用于为服务提供商和市政当局以及移动性实施实时数据共享，测量和监管. 旨在确保政府具有执行，评估和管理提供者的能力.
- [Alliance for Parking Data Standards (APDS)](https://www.allianceforparkingdatastandards.org/) -由 [International Parking Institute (IPI)](https://www.parking.org/)， 这 [British Parking Association (BPA)](http://www.britishparking.co.uk/)和 [European Parking Association (EPA)](http://www.europeanparking.eu/) ，APDS是一个非营利性组织，其使命是开发，促进，管理和维护统一的全球标准，该标准将使组织能够在全球各个平台之间共享停车数据.  APDS版本1.0文档是 [here](https://www.allianceforparkingdatastandards.org/resources).
- [Mobility as a Service API](http://maas-api.org/) -一组定义了MaaS兼容API的开放文档和测试套件（例如， [MaaS Transport Service Provider Booking API](https://github.com/maasglobal/maas-tsp-api/blob/master/specs/Booking.md)).
- [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120)  -这项研究的目的是为参与需求响应运输的实体制定交易数据的技术规范. 预计完成日期为2018年末.
- [NCHRP 08-119 Developing Data Standards and Guidance for Transportation Planning and Traffic Operations - Phase 1 (Anticipated)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4543) -这项研究的目的是制定标准和/或指南，以供运输界在收集，管理和共享静态和实时数据以进行运输规划和运营时使用和采用.
- [General Travel Network Specification](https://zephyrtransport.org/trb17projects/7-general-travel-network-specification/) -用于共享旅行需求模型网络的计划数据规范.
- [OMX: The Open Matrix data file format](https://github.com/osPlanning/omx) -二维数组对象和相关元数据的结构化集合，可能在运输建模行业中使用.
- [General Modeling Network Specification (GMNS)](https://github.com/zephyr-data-specs/GMNS)  -用于共享可路由道路网络文件的格式，该格式设计用于多模式静态和动态交通规划和运营模型.  Volpe / FHWA与Zephyr Foundation合作.
- [CurbLR](https://github.com/curblr/curblr-spec) -遏制法规的规范.
- [shared-row](https://github.com/d-wasserman/shared-row) -SharedStreets参考的通行权（ROW）规范.
- [Transport Operator Mobility-as-a-service Provider (TOMP)-API](https://github.com/TOMP-WG/TOMP-API) -荷兰的工作组，旨在开发供运输运营商和移动即服务提供商使用的API，以进行运营商发现，行程计划，最终用户交互，预订和付款.

### Resources

与开放的公交数据相关的在线课程，博客文章和报告.

#### On-line courses

- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) -免费的，在线的，自定进度的课程，用于学习GTFS和实时GTFS.
- [Open Transit Data Toolkit](http://transitdatatoolkit.com/) -一系列帮助人们利用开放式公交数据的课程.
- [MBTA GTFS Onboarding](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb)  -MBTA为GTFS static创建的交互式教程. 一个 [stand-alone Docker image](https://github.com/mbta/gtfs_onboarding) 可在GitHub以及 [hosted/no-install version](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb) Jupyter笔记本.
- [Planetizen "Building a Transit Map Web App" course](https://courses.planetizen.com/course/building-transit-map-app) -有关如何设置自己的基于Web的地图绘制应用程序的视频教程，无需任何编码经验. 

#### Blog posts

- [When(ish) is my bus? Data and code](https://github.com/mjskay/when-ish-is-my-bus)  -我的公交车Whenish后面的数据和代码（R）？ 数据包括三天的历史车辆位置和调查结果.
- ["Legacy AVL system? It's okay, join the club." by Kurt Raschke](https://kurtraschke.com/2015/01/legacy-avl-export) -讨论了将旧式AVL系统数据转换为GTFS实时格式的选项.
- ["GTFS Best Practices now available!" by Sean Barbeau](https://medium.com/@sjbarbeau/gtfs-best-practices-now-available-88ac67194233) -讨论了开放数据格式的一些挑战，例如GTFS和2017年初推出的GTFS最佳实践，以帮助解决数据质量问题.
- ["What's new in GTFS-realtime v2.0" by Sean Barbeau](https://medium.com/@sjbarbeau/whats-new-in-gtfs-realtime-v2-0-cd45e6a861e9) -讨论GTFS-实时v1.0的不足和v2.0的改进.
- ["AVL, CAD, and Real-Time Passenger Info for Beginners" by Tony Laidig](http://transitdata.net/avl-cad-and-real-time-passenger-info-for-beginners/) -提供用于跟踪车辆的技术的一般介绍.
- ["Visualizing Better Transportation: Data & Tools" by Steve Pepple](https://medium.com/@stevepepple/visualizing-better-transportation-data-tools-e48b8317a21c) -旧金山湾区和北美其他城市的运输相关数据和工具的集合，最初是在旧金山ARUP的2018年运输周活动上收集和讨论的.
- ["How to use GTFS data to track transit vehicles in realtime" by Tom Camp](https://www.ably.io/blog/gtfs-data-track-transit-vehicles-realtime) -使用GTFS和GTFS Realtime提供连续的实时更新.

#### Academic papers

- [Tang et al. - "Ridership effects of real-time bus information system: A case study in the City of Chicago"](https://www.sciencedirect.com/science/article/pii/S0968090X12000022) -在伊利诺伊州芝加哥市进行的实验表明，当骑手可以通过短信或电子邮件访问实时信息时，骑乘人数会适度增加.
- [Kay et al. - "When(ish) is my bus? User-centered Visualizations of Uncertainty in Everyday, Mobile Predictive Systems"](http://faculty.washington.edu/jhullman/busUncertaintyVis.pdf)  -论文试图回答“我们如何传达公交预测中的不确定性？”这一问题. 说明问题，现有解决方案并设计 [better interface for letting users know when to arrive at the bus stop](https://github.com/mjskay/when-ish-is-my-bus/blob/master/quantile-dotplots.md#quantile-dotplots).
- [Watkins et al. - "Where Is My Bus? Impact of mobile real-time information on the perceived and actual wait time of transit riders"](https://www.sciencedirect.com/science/article/pii/S0965856411001030) -西澳州西特尔（Seattl）的实验表明，当骑手能够通过移动应用访问实时信息时，他们会感觉到公交车的等待时间更短.
- [Brakewood et al. - “An experiment evaluating the impacts of real-time transit information on bus riders in Tampa, Florida”](https://www.sciencedirect.com/science/article/pii/S0965856414002146)  -在佛罗里达州坦帕市进行的对照实验表明，与没有实时信息的骑手相比，能够通过移动应用访问实时信息的骑手的等待时间减少了近2分钟. 具有实时信息的车手也减少了焦虑和沮丧，并更好地接受了代理.
- [Brakewood et al. - "The impact of real-time information on bus ridership in New York City"](https://www.sciencedirect.com/science/article/pii/S0968090X15000297) -纽约市的实验表明，向骑手提供实时信息后，长途旅行的骑行量增加.

#### Government reports
- [APTA Policy Development and Research - Public Transportation Embracing Open Data](http://www.apta.com/resources/reportsandpublications/Documents/APTA-Embracing-Open-Data.pdf) -APTA对开放式公交数据的好处和挑战的讨论（以下TCRP报告的简短摘要）.
- [TCRP Synthesis 115 - Open Data: Challenges and Opportunities for Transit Agencies](http://onlinepubs.trb.org/Onlinepubs/tcrp/tcrp_syn_115.pdf) -一份全面的报告，探讨了开放式公交数据的好处和挑战.
- [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120)  -这项研究的目的是为参与需求响应运输的实体制定交易数据的技术规范. 预计完成日期为2018年末.

#### Community-maintained lists
- [Vendors Providing GTFS Creation/Maintenance services](https://docs.google.com/spreadsheets/u/1/d/1Gc9mu4BIYC8ORpv2IbbVnT3q8VQ3xkeY7Hz068vT_GQ/pubhtml) -添加新的供应商 [here](http://goo.gl/forms/YDbPSPmufS).
- [Entities Providing Transportation Software Development Consulting Services](https://docs.google.com/spreadsheets/u/1/d/1n44CNMCK1vt1nyrsdYz-KD_hYxUMNIm6Me69M6ROBIg/pubhtml) -添加新实体 [here](http://goo.gl/forms/cc6kcVERuP).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Luqmaan Dawoodjee](https://github.com/luqmaan) 和 [Center for Urban Transportation Research](https://www.cutr.usf.edu/) at the [University of South Florida](http://www.usf.edu/) 放弃了此作品的所有版权以及相关或邻近的权利.

## About

最初创建者 [Luqmaan Dawoodjee](https://github.com/luqmaan)，现在由 [Center for Urban Transportation Research](https://www.cutr.usf.edu/) at the [University of South Florida](http://www.usf.edu/).

此列表仅用作社区资源，仅供参考，项目/产品的列表并不表示认可.
