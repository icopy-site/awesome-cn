<div class="github-widget" data-repo="tmcw/awesome-geojson"></div>
## awesome geojson [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

GeoJSON 实用程序将使您的生活更轻松.

<a href='https://www.placemark.io/'><i><img src='https://raw.githubusercontent.com/tmcw/awesome-geojson/master/.github/placemark.png' width='16' alt='Placemark' height='16' /> 由 Placemark 赞助，Placemark 是一个地图协作编辑器，对 GeoJSON 提供了大力支持

### operations

* [CoGran](https://github.com/berlinermorgenpost/cogran)：将统计数据从一组 GeoJSON 多边形重新采样到另一组
* [geo_assigner](https://github.com/stadt-karlsruhe/geo_assigner)：将属性复制到所有相交要素
* [geojson-coords](https://github.com/mapbox/geojson-coords)：从 GeoJSON 中提取坐标
* [geojson-extent](https://www.npmjs.com/package/geojson-extent)：计算geojson特征的边界框
* [geojson-flatten](https://github.com/tmcw/geojson-flatten)：将多个几何图形压平为正常几何图形
* [geojson-multiply](https://github.com/haoliangyu/geojson-multiply)：将普通 geojson 特征合并为一个多几何类型特征
* [geojson-js-utils](https://github.com/maxogden/geojson-js-utils)：用于操作 GeoJSON 的 JavaScript 辅助函数
* [geojson-merge](https://github.com/mapbox/geojson-merge)：将多个GeoJSON文件合并到一个FeatureCollection中.
* [geojson-normalize](https://github.com/mapbox/geojson-normalize)：将任何 geojson 对象标准化为 geojson 特征集合
* [geojson-pick](https://www.npmjs.com/package/geojson-pick)：从 geojson 要素集合中的要素中删除除指定属性之外的所有属性
* [geojson-random](https://github.com/tmcw/geojson-random)：生成随机geojson点、线和多边形
* [geojson-rewind](https://github.com/mapbox/geojson-rewind)：强制环绕顺序
* [rfc7946-to-d3](https://github.com/tyrasd/rfc7946-to-d3)：在 rfc7946 和 rfc7946 之间转换多边形缠绕顺序 [d3 compatible](https://github.com/d3/d3-geo#d3-geo) 惯例.
* [geojson-summary](https://github.com/mapbox/geojson-summary)：获取 geojson 文件中内容的简单英语摘要
* [point-grouper](https://github.com/substack/point-grouper)：将 geojson 点分组为包含多边形
* [geojson-join](https://github.com/tmcw/geojson-join)：将 geojson 与 json、dbf 和 csv 文件连接
* [simplify-geojson](https://github.com/maxogden/simplify-geojson)：将 ramer-douglas-peucker 线简化应用于 JS 或 CLI 中的 geojson 特征或特征集合
* [turf](https://github.com/Turfjs/turf)：空间操作和分析的函数集合
* [turf_dart](https://github.com/dartclub/turf_dart)：Dart 和 Flutter 的 turf.js 端口
* [de9im](https://github.com/dpmcmlxxvi/de9im)：空间 JavaScript 操作的快速函数集合
* [winnow](https://github.com/dmfenton/winnow)：使用 javascript 对 geojson 运行 sql 查询
* [geojson-id-streaming](https://github.com/andrewharvey/geojson-id-streaming)：为每个Feature添加唯一的id
* [geojson-mesh](https://github.com/andrewharvey/geojson-mesh)：提取 GeoJSON 中多边形的共享边界
* [geojson-polygon-labels](https://github.com/andrewharvey/geojson-polygon-labels)：从 GeoJSON 多边形生成点标签
* [geojsontools](https://github.com/micolous/geojsontools)：用于操作 GeoJSON 文件的 Python 工具
* [geojson-indoor-tools](https://github.com/armanjr/geojson-indoor-tools)：用于编辑室内 GeoJSON 特征的 Python 工具：添加房间高度、建造墙壁和创建门


### editors & viewers

* [geojson.io](http://geojson.io/)：基于网络的编辑器，支持多种文件类型导入和导出、操作、通过 GitHub 共享
* [umap](http://umap.openstreetmap.fr/en/)：网页编辑器，支持现场分享
* [geojson.tools](http://geojson.tools/)：来自 HERE XYZ 的网络编辑器
* [mapstarter](http://mapstarter.com/)：帮助从 GeoJSON 生成 svg、图像和代码
* [gjv](https://github.com/anandthakker/gjv) ：电子应用程序可以在本地查看 GeoJSON 并使用 turf 对其进行破解； 离线工作
* [GeoJSON editor](https://tomscholz.github.io/geojson-editor/)：Google 简单 geojson 编辑器的修改版本
* [geojson2image](https://github.com/brycejohnston/geojson2image)：用于从 GeoJSON 生成图像的库
* [dropchop](http://dropchop.io/)：基于Turf.js的浏览器GIS
* [Web GIS](https://drewweth.github.io/geodebugger)：查看、检查和操作地理空间数据的工具
* [img2geojson](https://caseymm.github.io/img2geojson/)：通过叠加在网络地图上并绘图来数字化图像

### validation

* [geojsonhint](https://github.com/mapbox/geojsonhint)：查找 geojson 文件中的错误
* [check-geojson](https://github.com/placemark/check-geojson)：geojsonhint 的替代方案
* [geojson-validation](https://www.npmjs.com/package/geojson-validation)：许多验证功能，加上简单的 gjv 命令行工具
* [gjf](https://github.com/yazeed44/gjf)：修复无效GeoJSON对象的工具
* [Jest-GeoJSON](https://github.com/M-Scott-Lassiter/jest-geojson)：Jest Javascript 单元测试框架的一组扩展匹配器函数，专门用于评估 GeoJSON 数据

### services

* [geojsonio-cli](https://github.com/mapbox/geojsonio-cli)：从命令行将 geojson 特征发送到 geojson.io
* [geojsonio-extension](https://github.com/mapbox/geojsonio-extension)：用于在 geojson.io 中编辑 github 文件的 chrome 扩展
* [geojsonlint](http://geojsonlint.com/)：用于 GeoJSON 验证的 REST 接口
* [mapshaper](http://mapshaper.org/)：用于GeoJSON和TopoJSON的简化和转换的简单接口
* [koop](https://koopjs.github.io)：带有插件的服务器，可将 Esri、GitHub、Socrata 和其他服务重铸为 GeoJSON 端点
* [featureserver](https://github.com/featureserver/featureserver)：开源 Esri 风格的要素服务器
* [geojson minify](https://open-innovations.github.io/geojson-minify/)：缩小文件大小的压缩器（压缩器）

### conversion

* **CSV**
  * [csv2geojson](https://github.com/mapbox/csv2geojson)：将 CSV 转换为 geojson
  * [geojson2dsv](https://github.com/tmcw/geojson2dsv)：将 geojson 转换为 CSV 和 TSV
* [geojson-mapnikify](https://github.com/mapbox/geojson-mapnikify)：将 GeoJSON 对象转换为带有嵌入 GeoJSON 数据和 simplestyle-spec 派生样式的 Mapnik XML 样式表.
* [geojson-vt](https://github.com/mapbox/geojson-vt)：在浏览器中动态将 GeoJSON 切片为矢量切片
* [vt-geojson](https://github.com/developmentseed/vt-geojson)：从 Mapbox 矢量切片中提取 GeoJSON
* [geojson2rtree](https://github.com/maxogden/geojson2rtree)：从一组 geojson 特征生成静态 rtree（使用 terraformer）
* [ogr2ogr](http://www.gdal.org/ogr2ogr.html): 将任何内容转换为任何内容
  * [fiona](https://github.com/toblerity/fiona)：ogr 之上的漂亮 python 界面
* [shp2json](https://github.com/substack/shp2json)：将 shapefile zip 档案转换为流 GeoJSON
* [togeojson](https://github.com/tmcw/togeojson)：将 GPX 和 KML 转换为 geojson
* [tokml](https://github.com/mapbox/tokml)：将 GeoJSON 转换为 KML
* [topojson](https://github.com/topojson/topojson)：将 GeoJSON 转换为 TopoJSON，从 CSV 连接数据
* [wellknown](https://github.com/mapbox/wellknown)：将 WKT 转换为 GeoJSON
* [betterknown](https://github.com/placemark/betterknown)：将 WKT 转换为 GeoJSON（众所周知的后继者）
* [esri2open](https://github.com/project-open-data/esri2open) 将专有的 Esri 格式转换为 GeoJSON
* [gtfs2geojson](https://github.com/tmcw/gtfs2geojson)：将 GTFS 交通数据转换为 GeoJSON
* [geoxform](https://github.com/koopjs/geoxform)：将任何大小的 geojson 流转换为流式 CSV、Shapefile 或 KML 等.
* [supercluster](https://github.com/mapbox/supercluster)：适用于浏览器和 Node.js 的快速 GeoJSON 集群库.
* **SVG**
  * [geojson2svg](https://github.com/gagan-bansal/geojson2svg)：给定 SVG 视图端口大小和地图范围，将 GeoJSON 转换为 SVG 字符串.
  * [geojson-svgify](https://github.com/juliuste/geojson-svgify)：将 GeoJSON 几何路径转换为 ​​SVG 折线元素.
  * [geojson-to-svg-cli](https://github.com/derhuerst/geojson-to-svg-cli)：将 GeoJSON 转换为 SVG 的命令行工具.
  * [svg-to-geojson](https://github.com/mapbox/svg-to-geojson)：将 SVG 拖放到地图上，它会将 GeoJSON 返回给您.
* [geojson2ndjson](https://www.npmjs.com/package/geojson2ndjson)：将 GeoJSON 与换行符分隔的 GeoJSON 相互转换
* [geobuf](https://www.npmjs.com/package/geobuf/v/0.2.1)：GeoJSON 与 GeoBuf 之间的转换
* **开放街道地图**
  * [osmtogeojson](https://github.com/tyrasd/osmtogeojson)：将 OpenStreetMap 数据转换为 GeoJSON
  * [osm2geojson](https://github.com/rclark/osm2geojson)：将 OSM XML 转换为 GeoJSON
  * [osm2geojson](https://github.com/aspectumapp/osm2geojson)：(Python) 将 OSM XML 和 Overpass XML/JSON 转换为 GeoJSON
  * [minjur](https://github.com/mapbox/minjur)：将 OpenStreetMap 数据转换为 GeoJSON 的速度比其他任何方法都快
  * [geojsontoosm](https://github.com/tyrasd/geojsontoosm)：将 GeoJSON 转换为 OSM XML
  * [geojson2osm](https://github.com/Rub21/geojson2osm)：将 GeoJSON 转换为 OSM XML
  * [osm-and-geojson](https://github.com/aaronlidman/osm-and-geojson)：将 GeoJSON 转换为 OSM XML 以及将 OSM XML 转换为 GeoJSON
  * [geojson2osm-es6](https://github.com/DenisCarriere/geojson2osm-es6/)：将 GeoJSON 转换为 OSM XML
  * [query-overpass](https://github.com/perliedman/query-overpass)  CLI 用于进行 Overpass 查询并将结果转换为 GeoJSON. 基于 [osmtogeojson](https://github.com/tyrasd/osmtogeojson)
* [topojson for Python](https://github.com/mattijn/topojson)：Topojson 是一个库，能够在 Python 中创建任何空间对象的 topojson 编码格式.
* [geomet](https://github.com/geomet/geomet)：常见地理空间数据格式的纯Python转换库


### data

* [natural earth](http://www.naturalearthdata.com/)：国家、省份和地理数据
* [geojson.xyz](http://geojson.xyz/)：具有热链接的适合网络大小的自然地球数据
* [world-atlas](https://github.com/topojson/world-atlas)：可定制的自然地球数据的简化版本
* [geo-maps](https://github.com/simonepri/geo-maps)：以编程方式生成的高质量 GeoJSON 地图.
* [openflights-geojson](https://github.com/tmcw/openflights-geojson): [openflights](http://openflights.org/) 机场和飞机航线
* [us-atlas](https://github.com/topojson/us-atlas)：用于美国功能的 geojson 和 topojson
* [metro-extracts](https://mapzen.com/data/metro-extracts/)：区域 OpenStreetMap 数据为 GeoJSON
* [whereonearth-airport](https://github.com/straup/whereonearth-airport)：每个机场的轮廓
* [whereonearth-building](https://github.com/straup/whereonearth-building/): 建筑轮廓
* [whereonearth repos](https://github.com/search?q=user%3Astraup+whereonearth)：Aaron Straup Cope 从 GeoPlanet 输出的其他功能
* [tgn-geojson](https://github.com/straup/tgn-geojson)： Getty 地名同义词库 (TGN) 作为 GeoJSON.
* [strava-to-geojsonio](https://github.com/taketime/strava-to-geojsonio)：将跑步和游乐设施从 Strava 导出到 GeoJSON
* [strava-geojson](https://github.com/tmcw/strava-geojson)：将所有 strava 数据导出到 geojson，在节点 &amp; [on the web](http://www.macwright.org/strava-geojson/)
* [gimme OSM](http://ustroetz.github.io/gimmeOSM/)：通过openstreetmap id获取geojson文件
* [country-levels](https://github.com/hyperknot/country-levels-export) 基于 ISO 和 FIPS 代码的完整星球 GeoJSON 提取.
* [historical-basemaps](https://github.com/aourednik/historical-basemaps)：收集世界国家和文化区域的地理参考边界，用于绘制世界范围内的历史数据.
* [99boundaries](https://github.com/TimMcCauley/nintynine-boundaries)：以 GeoJSON 和其他文件格式生成任何海上和陆地边界，或者 [download directly from the web](https://99boundaries.com)
* [france-geojson](https://github.com/gregoiredavid/france-geojson)：GeoJSON 格式的法国大区、省、区、州和市镇（大陆和海外省）的轮廓

### serialization

* [python-geojson](https://github.com/frewsxcv/python-geojson)：将 geojson 序列化为 python 数据类型/从 python 数据类型序列化
* [rgeo-geojson](https://github.com/rgeo/rgeo-geojson)：将 geojson 序列化为 ruby​​ RGeo 数据类型或从 ruby​​ RGeo 数据类型序列化 geojson
* [rust-geojson](https://github.com/georust/rust-geojson)：将 geojson 序列化为 Rust 数据类型或从 Rust 数据类型序列化 geojson
* [geojson-jackson](https://github.com/opendatalab-de/geojson-jackson)：将 GeoJSON 与 Java 数据类型序列化（基于 [Jackson](http://wiki.fasterxml.com/JacksonHome))
* [mapbox-java](https://github.com/mapbox/mapbox-java)：将 GeoJSON 与 Java 数据类型序列化（基于 [Gson](https://github.com/google/gson))
* [geojson-serializer](https://github.com/ancore/geojson-serializer)：将带有注释的 Java 序列化为 GeoJSON

### resources

* [RFC 7946 – The GeoJSON Format](https://tools.ietf.org/html/rfc7946)：IETF 当前的 GeoJSON 标准
* [GeoJSON.org](http://geojson.org/)：第一个规范，定义了 GeoJSON 结构的所有规则
* [More than you ever wanted to know about GeoJSON](http://www.macwright.org/2015/03/23/geojson-second-bite.html)：以更具叙述性的形式回顾规范背后的概念.
* [geojson-invalid-geometry](https://github.com/chrieke/geojson-invalid-geometry)：示例文件的 GeoJSON 无效几何问题列表.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/ )

在法律允许的范围内， [Tom MacWright](http://www.macwright.org) 已放弃本作品的所有版权以及相关或邻接权.
