<div class="github-widget" data-repo="tmcw/awesome-geojson"></div>
## awesome geojson [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

GeoJSON实用程序将使您的生活更轻松.

### operations

* [CoGran](https://github.com/berlinermorgenpost/cogran)：将一组GeoJSON多边形的统计信息重新采样到另一组
* [geo_assigner](https://github.com/stadt-karlsruhe/geo_assigner)：将属性复制到所有相交要素
* [geojson-coords](https://github.com/mapbox/geojson-coords)：从GeoJSON中提取坐标
* [geojson-extent](https://www.npmjs.com/package/geojson-extent)：计算geojson特征的边界框
* [geojson-flatten](https://github.com/tmcw/geojson-flatten)：将多个几何体展平为普通几何体
* [geojson-multiply](https://github.com/haoliangyu/geojson-multiply)：将常规geojson要素合并为一个多几何类型要素
* [geojson-js-utils](https://github.com/maxogden/geojson-js-utils)：用于操作GeoJSON的JavaScript帮助程序函数
* [geojson-merge](https://github.com/mapbox/geojson-merge)：将多个GeoJSON文件合并到一个FeatureCollection中.
* [geojson-normalize](https://github.com/mapbox/geojson-normalize)：将任何geojson对象规范化为geojson featurecollection
* [geojson-pick](https://www.npmjs.com/package/geojson-pick)：从geojson featurecollection中的要素中删除除指定属性之外的所有属性
* [geojson-random](https://github.com/tmcw/geojson-random)：生成随机geojson点，线和多边形
* [geojson-rewind](https://github.com/mapbox/geojson-rewind)：强制戒指令
* [rfc7946-to-d3](https://github.com/tyrasd/rfc7946-to-d3)：转换rfc7946和之间的多边形绕组顺序 [d3 compatible](https://github.com/d3/d3-geo#d3-geo) 约定.
* [geojson-summary](https://github.com/mapbox/geojson-summary)：获取geojson文件中的内容的简明汇总
* [point-grouper](https://github.com/substack/point-grouper)：group geojson指向包含多边形
* [geojson-join](https://github.com/tmcw/geojson-join)：加入geojson来对抗json，dbf和csv文件
* [simplify-geojson](https://github.com/maxogden/simplify-geojson)：将ramer-douglas-peucker line简化应用于JS或CLI中的geojson特性或特征集合
* [turf](https://github.com/Turfjs/turf)：空间操作和分析功能的集合
* [winnow](https://github.com/dmfenton/winnow)：使用javascript对geojson运行sql查询
* [geojson-id-streaming](https://github.com/andrewharvey/geojson-id-streaming)：为每个功能添加唯一ID
* [geojson-mesh](https://github.com/andrewharvey/geojson-mesh)：在GeoJSON中提取多边形的共享边框
* [geojson-polygon-labels](https://github.com/andrewharvey/geojson-polygon-labels)：从GeoJSON多边形生成点标签
* [geojsontools](https://github.com/micolous/geojsontools)：用于操作GeoJSON文件的Python工具


### editors & viewers

* [geojson.io](http://geojson.io/)：基于Web的编辑器，支持许多文件类型导入和导出，操作，通过GitHub共享
* [umap](http://umap.openstreetmap.fr/en/)：基于Web的编辑器，支持现场共享
* [geojson.tools](http://geojson.tools/)：来自HERE XYZ的基于网络的编辑
* [simple geojson editor](https://google-developers.appspot.com/maps/documentation/utils/geojson/)：谷歌地图上的geojson编辑，谷歌
* [mapstarter](http://mapstarter.com/)：帮助从GeoJSON生成svg，图像和代码
* [gjv](https://github.com/anandthakker/gjv) ：电子应用程序可以在本地查看GeoJSON并使用草皮进行攻击;  离线工作
* [GeoJSON editor](https://tomscholz.github.io/geojson-editor/)：Google简单geojson编辑器的修改版本
* [geojson2image](https://github.com/brycejohnston/geojson2image)：用于从GeoJSON生成图像的库
* [dropchop](http://dropchop.io/)：基于Turf.js的基于浏览器的GIS

### validation

* [geojsonhint](https://github.com/mapbox/geojsonhint)：在geojson文件中查找错误
* [geojson-validation（https://www.npmjs.com/package/geojson-validation）：许多验证函数，以及简单的gjv命令行工具

### services

* [geojsonio-cli](https://github.com/mapbox/geojsonio-cli)：从命令行向geojson.io发送geojson功能
* [geojsonio-extension](https://github.com/mapbox/geojsonio-extension)：chrome扩展用于在geojson.io中编辑github文件
* [geojsonlint](http://geojsonlint.com/)：用于GeoJSON验证的REST接口
* [mapshaper](http://mapshaper.org/)：简化界面，简化和转换GeoJSON和TopoJSON
* [koop](https://koopjs.github.io)：带有插件的服务器，将Esri，GitHub，Socrata和其他服务重新设置为GeoJSON端点
* [featureserver](https://github.com/featureserver/featureserver)：一个开源的Esri风格的功能服务器

### conversion

* ** CSV **
  * [csv2geojson](https://github.com/mapbox/csv2geojson)：将CSV转换为geojson
  * [geojson2dsv](https://github.com/tmcw/geojson2dsv)：将geojson转换为CSV和TSV
* [geojson-mapnikify](https://github.com/mapbox/geojson-mapnikify)：将GeoJSON对象转换为具有嵌入式GeoJSON数据和simplestyle-spec派生样式的Mapnik XML样式表.
* [geojson-vt](https://github.com/mapbox/geojson-vt)：在浏览器中将GeoJSON切片成矢量图块
* [vt-geojson](https://github.com/developmentseed/vt-geojson)：从Mapbox矢量切片中提取GeoJSON
* [geojson2rtree](https://github.com/maxogden/geojson2rtree)：从一组geojson特征生成静态rtree（使用terraformer）
* [ogr2ogr](http://www.gdal.org/ogr2ogr.html)：将任何东西都转换成什么
  * [fiona](https://github.com/toblerity/fiona)：在ogr上面的漂亮的python接口
* [shp2json](https://github.com/substack/shp2json)：将shapefile zip存档转换为流式GeoJSON
* [togeojson](https://github.com/tmcw/togeojson)：将GPX和KML转换为geojson
* [tokml](https://github.com/mapbox/tokml)：将GeoJSON转换为KML
* [topojson](https://github.com/topojson/topojson)：将GeoJSON转换为TopoJSON，从CSV加入数据
* [wellknown](https://github.com/mapbox/wellknown)：将WKT转换为GeoJSON
* [esri2open](https://github.com/project-open-data/esri2open) converts proprietary Esri formats to GeoJSON
* [gtfs2geojson](https://github.com/tmcw/gtfs2geojson)：将GTFS传输数据转换为GeoJSON
* [geoxform](https://github.com/koopjs/geoxform)：将任何大小的geojson流转换为流式CSV，Shapefile或KML等.
* [supercluster](https://github.com/mapbox/supercluster)：用于浏览器和Node的快速GeoJSON群集库.
* ** SVG **
  * [geojson-svgify](https://github.com/juliuste/geojson-svgify)：将GeoJSON几何路径转换为SVG折线元素.
  * [geojson-to-svg-cli](https://github.com/derhuerst/geojson-to-svg-cli)：命令行工具将GeoJSON转换为SVG.
  * [svg-to-geojson](https://github.com/mapbox/svg-to-geojson)：在地图上拖放SVG并将GeoJSON返回给您.
* [geojson2ndjson](https://www.npmjs.com/package/geojson2ndjson)：将GeoJSON转换为换行符分隔的GeoJSON
* [geobuf](https://www.npmjs.com/package/geobuf/v/0.2.1)：将GeoJSON转换为GeoBuf /从GeoBuf转换

* ** OpenStreetMap **
  * [osmtogeojson](https://github.com/tyrasd/osmtogeojson)：将OpenStreetMap数据转换为GeoJSON
  * [osm2geojson](https://github.com/rclark/osm2geojson)：将OSM XML转换为GeoJSON
  * [minjur](https://github.com/mapbox/minjur)：将OpenStreetMap数据转换为GeoJSON的速度比其他任何方法都快
  * [geojsontoosm](https://github.com/tyrasd/geojsontoosm)：将GeoJSON转换为OSM XML
  * [geojson2osm](https://github.com/Rub21/geojson2osm)：将GeoJSON转换为OSM XML
  * [osm-and-geojson](https://github.com/aaronlidman/osm-and-geojson)：将GeoJSON转换为OSM XML和OSM XML转换为GeoJSON
  * [geojson2osm-es6](https://github.com/DenisCarriere/geojson2osm-es6/)：将GeoJSON转换为OSM XML


### data

* [natural earth](http://www.naturalearthdata.com/)：国家，省和地理数据
* [geojson.xyz](http://geojson.xyz/)：具有网络友好尺寸的自然地球数据，具有热链接
* [world-atlas](https://github.com/topojson/world-atlas)：可定制的自然地球数据简化版本
* [geo-maps](https://github.com/simonepri/geo-maps)：以编程方式生成的高质量GeoJSON地图.
* [openflights-geojson](https://github.com/tmcw/openflights-geojson): [openflights](http://openflights.org/) 机场和飞机路线
* [us-atlas](https://github.com/topojson/us-atlas)：geojson＆topojson为美国特色
* [metro-extracts](https://mapzen.com/data/metro-extracts/)：区域OpenStreetMap数据为GeoJSON
* [whereonearth-airport](https://github.com/straup/whereonearth-airport)：每个机场的轮廓
* [whereonearth-building](https://github.com/straup/whereonearth-building/)：建立大纲
* [whereonearth repos](https://github.com/search?q=user%3Astraup+whereonearth)：Aaron Straup Cope从GeoPlanet输出的其他功能
* [tgn-geojson](https://github.com/straup/tgn-geojson)：Getty The Geurus of Geographic Names（TGN）As GeoJSON.
* [strava-to-geojsonio](https://github.com/taketime/strava-to-geojsonio)：出口运行并从Strava到GeoJSON
* [strava-geojson](https://github.com/tmcw/strava-geojson)：将_all_ strava数据导出到geojson，在节点＆ [on the web](http://www.macwright.org/strava-geojson/)
* [gimme OSM](http://ustroetz.github.io/gimmeOSM/)：通过openstreetmap id获取geojson文件

### serialization

* [python-geojson](https://github.com/frewsxcv/python-geojson)：序列化geojson到/从python数据类型
* [rgeo-geojson](https://github.com/rgeo/rgeo-geojson)：序列化geojson到/来自ruby RGeo数据类型
* [rust-geojson](https://github.com/georust/rust-geojson)：将geojson序列化为/从数据类型
* [geojson-jackson](https://github.com/opendatalab-de/geojson-jackson)：将GeoJSON与Java数据类型串行化（基于 [Jackson](http://wiki.fasterxml.com/JacksonHome))
* [mapbox-java](https://github.com/mapbox/mapbox-java)：将GeoJSON与Java数据类型串行化（基于 [Gson](https://github.com/google/gson))

### resources

* [RFC 7946 – The GeoJSON Format](https://tools.ietf.org/html/rfc7946)：IETF目前的GeoJSON标准
* [geojson.win]（http://geojson.win]：规范的更易读版本.
* [GeoJSON.org](http://geojson.org/)：第一个规范，定义了GeoJSON结构的所有规则
* [More than you ever wanted to know about GeoJSON](http://www.macwright.org/2015/03/23/geojson-second-bite.html)：以更加叙述的形式回顾规范背后的概念.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/ )

在法律允许的范围内， [Tom MacWright](http://www.macwright.org) 已放弃对此作品的所有版权及相关或相邻权利.
