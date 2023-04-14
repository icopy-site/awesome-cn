<div class="github-widget" data-repo="tmcw/awesome-geojson"></div>
## awesome geojson [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

GeoJSON 实用程序将使您的生活更轻松.

<a href='https://www.placemark.io/'><i><img src='https://raw.githubusercontent.com/tmcw/awesome-geojson/master/.github/placemark.png' width='16' alt='Placemark' height='16' /> 由 Placemark 赞助，Placemark 是一款地图协作编辑器，非常支持 GeoJSON

### operations

* [CoGran](https://github.com/berlinermorgenpost/cogran): 将统计数据从一组 GeoJSON 多边形重新采样到另一组
* [geo_assigner](https://github.com/stadt-karlsruhe/geo_assigner)：将属性复制到所有相交的要素
* [geojson-coords](https://github.com/mapbox/geojson-coords): 从 GeoJSON 中提取坐标
* [geojson-extent](https://www.npmjs.com/package/geojson-extent)：计算geojson特征的边界框
* [geojson-flatten](https://github.com/tmcw/geojson-flatten)：将多个几何图形展平为普通几何图形
* [geojson-multiply](https://github.com/haoliangyu/geojson-multiply)：将普通的 geojson 特征合并为一个多几何类型的特征
* [geojson-js-utils](https://github.com/maxogden/geojson-js-utils): 用于操作 GeoJSON 的 JavaScript 辅助函数
* [geojson-merge](https://github.com/mapbox/geojson-merge): 将多个 GeoJSON 文件合并到一个 FeatureCollection 中.
* [geojson-normalize](https://github.com/mapbox/geojson-normalize)：将任何 geojson 对象规范化为 geojson 特征集合
* [geojson-pick](https://www.npmjs.com/package/geojson-pick)：从 geojson 要素集合中的要素中删除除指定属性外的所有属性
* [geojson-random](https://github.com/tmcw/geojson-random)：生成随机的 geojson 点、线和多边形
* [geojson-rewind](https://github.com/mapbox/geojson-rewind): 强制环绕顺序
* [rfc7946-to-d3](https://github.com/tyrasd/rfc7946-to-d3)：在rfc7946和rfc7946之间转换多边形缠绕顺序 [d3 compatible](https://github.com/d3/d3-geo#d3-geo) 惯例.
* [geojson-summary](https://github.com/mapbox/geojson-summary)：获取 geojson 文件内容的简明摘要
* [point-grouper](https://github.com/substack/point-grouper): group geojson points into containing polygons
* [geojson-join](https://github.com/tmcw/geojson-join): 将 geojson 加入 json、dbf 和 csv 文件
* [simplify-geojson](https://github.com/maxogden/simplify-geojson)：将 ramer-douglas-peucker 行简化应用于 JS 或 CLI 中的 geojson 特征或特征集合
* [turf](https://github.com/Turfjs/turf): 空间操作和分析功能的集合
* [turf_dart](https://github.com/dartclub/turf_dart): Dart 和 Flutter 的 turf.js 端口
* [de9im](https://github.com/dpmcmlxxvi/de9im): 用于空间 javascript 操作的快速函数集合
* [winnow](https://github.com/dmfenton/winnow): 使用 javascript 对 geojson 运行 sql 查询
* [geojson-id-streaming](https://github.com/andrewharvey/geojson-id-streaming): 为每个Feature添加一个唯一的id
* [geojson-mesh](https://github.com/andrewharvey/geojson-mesh): 在 GeoJSON 中提取多边形的共享边界
* [geojson-polygon-labels](https://github.com/andrewharvey/geojson-polygon-labels): 从 GeoJSON 多边形生成点标签
* [geojsontools](https://github.com/micolous/geojsontools): 用于操作 GeoJSON 文件的 Python 工具
* [geojson-indoor-tools](https://github.com/armanjr/geojson-indoor-tools): 用于编辑室内 GeoJSON 功能的 Python 工具：添加房间高度、建筑墙壁和创建门


### editors & viewers

* [geojson.io](http://geojson.io/): 基于网络的编辑器，支持多种文件类型的导入和导出，操作，通过 GitHub 共享
* [umap](http://umap.openstreetmap.fr/en/): 基于网络的编辑器，支持现场分享
* [geojson.tools](http://geojson.tools/)：来自 HERE XYZ 的基于网络的编辑器
* [mapstarter](http://mapstarter.com/): 帮助从 GeoJSON 生成 svg、图像和代码
* [gjv](https://github.com/anandthakker/gjv) ：电子应用程序可以在本地查看 GeoJSON 并使用 turf 对其进行破解； 离线工作
* [GeoJSON editor](https://tomscholz.github.io/geojson-editor/): 谷歌简单 geojson 编辑器的修改版本
* [geojson2image](https://github.com/brycejohnston/geojson2image): 用于从 GeoJSON 生成图像的库
* [dropchop](http://dropchop.io/): 基于浏览器的 GIS，基于 Turf.js
* [Web GIS](https://drewweth.github.io/geodebugger)：查看、检查和操作地理空间数据的工具
* [img2geojson](https://caseymm.github.io/img2geojson/)：通过在网络地图上叠加和绘图来数字化图像

### validation

* [geojsonhint](https://github.com/mapbox/geojsonhint)：在您的 geojson 文件中查找错误
* [check-geojson](https://github.com/placemark/check-geojson): geojsonhint 的替代品
* [geojson-validation](https://www.npmjs.com/package/geojson-validation): 许多验证功能，加上简单的 gjv 命令行工具
* [gjf](https://github.com/yazeed44/gjf): 修复无效 GeoJSON 对象的工具
* [Jest-GeoJSON](https://github.com/M-Scott-Lassiter/jest-geojson): 为评估 GeoJSON 数据量身定制的 Jest Javascript 单元测试框架的一组扩展匹配器函数

### services

* [geojsonio-cli](https://github.com/mapbox/geojsonio-cli)：从命令行将 geojson 功能发送到 geojson.io
* [geojsonio-extension](https://github.com/mapbox/geojsonio-extension): 用于在 geojson.io 中编辑 github 文件的 chrome 扩展
* [geojsonlint](http://geojsonlint.com/): 用于 GeoJSON 验证的 REST 接口
* [mapshaper](http://mapshaper.org/): 用于GeoJSON和TopoJSON简化和转换的简单接口
* [koop](https://koopjs.github.io)：带有将 Esri、GitHub、Socrata 和其他服务重铸为 GeoJSON 端点的插件的服务器
* [featureserver](https://github.com/featureserver/featureserver): 一个开源的 Esri 风格的要素服务器

### conversion

* **CSV**
  * [csv2geojson](https://github.com/mapbox/csv2geojson): 将 CSV 转换为 geojson
  * [geojson2dsv](https://github.com/tmcw/geojson2dsv): 将 geojson 转换为 CSV 和 TSV
* [geojson-mapnikify](https://github.com/mapbox/geojson-mapnikify)：将 GeoJSON 对象转换为具有嵌入式 GeoJSON 数据和 simplestyle-spec 派生样式的 Mapnik XML 样式表.
* [geojson-vt](https://github.com/mapbox/geojson-vt)：在浏览器中将 GeoJSON 动态切片为矢量切片
* [vt-geojson](https://github.com/developmentseed/vt-geojson): 从 Mapbox 矢量切片中提取 GeoJSON
* [geojson2rtree](https://github.com/maxogden/geojson2rtree)：从一组 geojson 特征生成静态 rtree（使用 terraformer）
* [ogr2ogr](http://www.gdal.org/ogr2ogr.html): 将任何东西转换成任何东西
  * [fiona](https://github.com/toblerity/fiona): 在 ogr 之上的漂亮的 python 界面
* [shp2json](https://github.com/substack/shp2json): 将 shapefile zip 存档转换为流式 GeoJSON
* [togeojson](https://github.com/tmcw/togeojson): 将 GPX 和 KML 转换为 geojson
* [tokml](https://github.com/mapbox/tokml): 将 GeoJSON 转换为 KML
* [topojson](https://github.com/topojson/topojson): 将 GeoJSON 与 TopoJSON 相互转换，从 CSV 连接数据
* [wellknown](https://github.com/mapbox/wellknown): 将 WKT 转换为 GeoJSON
* [betterknown](https://github.com/placemark/betterknown)：将 WKT 转换为 GeoJSON（wellknown 的继承者）
* [esri2open](https://github.com/project-open-data/esri2open) 将专有的 Esri 格式转换为 GeoJSON
* [gtfs2geojson](https://github.com/tmcw/gtfs2geojson): 将 GTFS 中转数据转换为 GeoJSON
* [geoxform](https://github.com/koopjs/geoxform): 将任何大小的 geojson 流转换为流式 CSV、Shapefile 或 KML 等.
* [supercluster](https://github.com/mapbox/supercluster)：用于浏览器和 Node.js 的快速 GeoJSON 集群库.
* **SVG**
  * [geojson2svg](https://github.com/gagan-bansal/geojson2svg)：在给定 SVG 视图端口大小和地图范围的情况下，将 GeoJSON 转换为 SVG 字符串.
  * [geojson-svgify](https://github.com/juliuste/geojson-svgify)：将 GeoJSON 几何路径转换为 ​​SVG 折线元素.
  * [geojson-to-svg-cli](https://github.com/derhuerst/geojson-to-svg-cli)：将 GeoJSON 转换为 SVG 的命令行工具.
  * [svg-to-geojson](https://github.com/mapbox/svg-to-geojson)：将 SVG 拖放到地图上，它会将 GeoJSON 返回给您.
* [geojson2ndjson](https://www.npmjs.com/package/geojson2ndjson)：将 GeoJSON 转换为换行符分隔的 GeoJSON 或从换行符分隔的 GeoJSON 转换
* [geobuf](https://www.npmjs.com/package/geobuf/v/0.2.1): 将 GeoJSON 与 GeoBuf 相互转换
* **开放街道地图**
  * [osmtogeojson](https://github.com/tyrasd/osmtogeojson): 将 OpenStreetMap 数据转换为 GeoJSON
  * [osm2geojson](https://github.com/rclark/osm2geojson): 将 OSM XML 转换为 GeoJSON
  * [osm2geojson](https://github.com/aspectumapp/osm2geojson): (Python) 将 OSM XML 和 Overpass XML/JSON 转换为 GeoJSON
  * [minjur](https://github.com/mapbox/minjur): 将 OpenStreetMap 数据转换为 GeoJSON 的速度比其他任何东西都快
  * [geojsontoosm](https://github.com/tyrasd/geojsontoosm): 将 GeoJSON 转换为 OSM XML
  * [geojson2osm](https://github.com/Rub21/geojson2osm): 将 GeoJSON 转换为 OSM XML
  * [osm-and-geojson](https://github.com/aaronlidman/osm-and-geojson): 将 GeoJSON 转换为 OSM XML，将 OSM XML 转换为 GeoJSON
  * [geojson2osm-es6](https://github.com/DenisCarriere/geojson2osm-es6/): 将 GeoJSON 转换为 OSM XML
  * [query-overpass](https://github.com/perliedman/query-overpass)  CLI 进行 Overpass 查询并将结果转换为 GeoJSON. 基于 [osmtogeojson](https://github.com/tyrasd/osmtogeojson)


### data

* [natural earth](http://www.naturalearthdata.com/): 国家、省份和地理数据
* [geojson.xyz](http://geojson.xyz/)：具有热链接的网络友好大小的自然地球数据
* [world-atlas](https://github.com/topojson/world-atlas)：自然地球数据的可定制简化版本
* [geo-maps](https://github.com/simonepri/geo-maps)：以编程方式生成的高质量 GeoJSON 地图.
* [openflights-geojson](https://github.com/tmcw/openflights-geojson): [openflights](http://openflights.org/) 机场和航线
* [us-atlas](https://github.com/topojson/us-atlas): geojson &amp; topojson 用于美国特征
* [metro-extracts](https://mapzen.com/data/metro-extracts/)：作为 GeoJSON 的区域 OpenStreetMap 数据
* [whereonearth-airport](https://github.com/straup/whereonearth-airport): 每个机场的轮廓
* [whereonearth-building](https://github.com/straup/whereonearth-building/): 建筑轮廓
* [whereonearth repos](https://github.com/search?q=user%3Astraup+whereonearth)：Aaron Straup Cope 从 GeoPlanet 输出的其他特征
* [tgn-geojson](https://github.com/straup/tgn-geojson): 盖蒂地名词库 (TGN) 作为 GeoJSON.
* [strava-to-geojsonio](https://github.com/taketime/strava-to-geojsonio)：将跑步和骑行从 Strava 导出到 GeoJSON
* [strava-geojson](https://github.com/tmcw/strava-geojson)：将 _all_ strava 数据导出到 geojson，在节点中 &amp; [on the web](http://www.macwright.org/strava-geojson/)
* [gimme OSM](http://ustroetz.github.io/gimmeOSM/): 通过 openstreetmap id 获取 geojson 文件
* [country-levels](https://github.com/hyperknot/country-levels-export) 基于 ISO 和 FIPS 代码的完整行星 GeoJSON 提取.
* [historical-basemaps](https://github.com/aourednik/historical-basemaps)：收集世界各国和文化区域的地理参考边界，用于绘制世界范围内的历史数据.
* [99boundaries](https://github.com/TimMcCauley/nintynine-boundaries)：以 GeoJSON 和其他文件格式生成任何海洋和陆地边界或 [download directly from the web](https://99boundaries.com)
* [france-geojson](https://github.com/gregoiredavid/france-geojson): GeoJSON 格式的法国大区、省、行政区、行政区和市镇概况（大陆和海外省）

### serialization

* [python-geojson](https://github.com/frewsxcv/python-geojson): 将 geojson 序列化为 python 数据类型/从 python 数据类型
* [rgeo-geojson](https://github.com/rgeo/rgeo-geojson): 将 geojson 序列化为 ruby​​ RGeo 数据类型或从中序列化
* [rust-geojson](https://github.com/georust/rust-geojson): 将 geojson 序列化为 rust 数据类型/从 rust 数据类型
* [geojson-jackson](https://github.com/opendatalab-de/geojson-jackson)：将 GeoJSON 序列化为 Java 数据类型（基于 [Jackson](http://wiki.fasterxml.com/JacksonHome))
* [mapbox-java](https://github.com/mapbox/mapbox-java)：将 GeoJSON 序列化为 Java 数据类型（基于 [Gson](https://github.com/google/gson))
* [geojson-serializer](https://github.com/ancore/geojson-serializer): 将带有注释的 Java 序列化为 GeoJSON

### resources

* [RFC 7946 – The GeoJSON Format](https://tools.ietf.org/html/rfc7946): IETF 当前的 GeoJSON 标准
* [GeoJSON.org](http://geojson.org/): 第一个规范，定义了 GeoJSON 结构的所有规则
* [More than you ever wanted to know about GeoJSON](http://www.macwright.org/2015/03/23/geojson-second-bite.html)：以更具叙述性的格式回顾规范背后的概念.
* [geojson-invalid-geometry](https://github.com/chrieke/geojson-invalid-geometry)：示例文件的 GeoJSON 无效几何问题列表.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/ )

在法律允许的范围内， [Tom MacWright](http://www.macwright.org) 已放弃该作品的所有版权和相关或邻接权.
