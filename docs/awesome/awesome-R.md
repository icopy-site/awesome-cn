<div class="github-widget" data-repo="qinwf/awesome-R"></div>
## Awesome R

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 精选的R包和工具的精选列表.  灵感来自 [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning).

有关更好的导航，请参阅https://awesome-r.com

<p><img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">
对于<a target="_blank" href="https://github.com/rstudio/RStartHere/blob/master/top_downloads_2016/top_packages">前50个</a> CRAN下载的软件包或400+的回购软件
<img class="emoji" alt="star" src="https://awesome-r.com/star.png" height="20" align="absmiddle" width="20"></p>

- [Awesome R](#awesome-)
    - [2018](#2018)
    - [2017](#2017)
    - [Integrated Development Environments](#integrated-development-environments)
    - [Syntax](#syntax)
    - [Data Manipulation](#data-manipulation)
    - [Graphic Displays](#graphic-displays)
    - [Html Widgets](#html-widgets)
    - [Reproducible Research](#reproducible-research)
    - [Web Technologies and Services](#web-technologies-and-services)
    - [Parallel Computing](#parallel-computing)
    - [High Performance](#high-performance)
    - [Language API](#language-api)
    - [Database Management](#database-management)
    - [Machine Learning](#machine-learning)
    - [Natural Language Processing](#natural-language-processing)
    - [Bayesian](#bayesian)
    - [Optimization](#optimization)
    - [Finance](#finance)
    - [Bioinformatics and Biostatistics](#bioinformatics-and-biostatistics)
    - [Network Analysis](#network-analysis)
    - [Spatial](#spatial)
    - [R Development](#r-development)
    - [Logging](#logging)
    - [Data Packages](#data-packages)
    - [Other Tools](#other-tools)
    - [Other Interpreters](#other-interpreters)
    - [Learning R](#learning-r)
- [Resources](#resources)
    - [Websites](#websites)
    - [Books](#books)
    - [Podcasts](#podcasts)
    - [Reference Cards](#reference-cards)
    - [MOOCs](#moocs)
    - [Lists](#lists)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## 2018

* [r2d3](https://rstudio.github.io/r2d3/) -  D3可视化的R接口
* [rstats-ed](https://github.com/rstudio-education/rstats-ed) - 教授R的课程清单
* [promises](https://cran.r-project.org/web/packages/promises/index.html) - 基于Promise的异步编程的抽象
* [tinytex](https://yihui.name/tinytex/) - 轻巧且易于维护的LaTeX发行版
* [Readings in Applied Data Science](https://github.com/hadley/stats337) - 这些读数反映了哈德利关于应用数据科学的个人想法.


## 2017

* [prophet](https://github.com/facebookincubator/prophet) - 用于生成具有线性或非线性增长的多季节性的时间序列数据的高质量预测的工具.
* [tidyverse](https://github.com/tidyverse/tidyverse) - 从tidyverse轻松安装和加载包
* [purrr](https://github.com/tidyverse/purrr) -  R的函数式编程工具包
* [hrbrthemes](https://github.com/hrbrmstr/hrbrthemes) - 以意见，印刷为中心的ggplot2主题和主题组件
* [xaringan](https://github.com/yihui/xaringan) - 使用R Markdown和JavaScript库创建HTML5幻灯片
* [blogdown](https://github.com/rstudio/blogdown) - 使用R Markdown创建博客和网站
* [glue](https://github.com/tidyverse/glue) - 将字符串粘贴到R中的数据.小，快，无依赖的解释字符串文字.
* [covr](https://github.com/jimhester/covr) -  R的测试覆盖率报告
* [lintr](https://github.com/jimhester/lintr) -  R的静态代码分析
* [reprex](https://github.com/jennybc/reprex) - 渲染用于共享的R代码位，例如，在GitHub或StackOverflow上.
* [reticulate](https://github.com/rstudio/reticulate) -  R与Python的接口
* [tensorflow](https://github.com/rstudio/tensorflow) -  TensorFlow for R
* [utf8](https://github.com/patperry/r-utf8) - 操作和打印UTF-8文本，修复R的UTF-8处理中的多个错误.
* [Patchwork](https://github.com/thomasp85/patchwork) - 将单独的ggplots组合到同一图形中.

## Integrated Development Environments
*综合发展环境*

* [RStudio <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://www.rstudio.org/) - 适用于R的强大而高效的用户界面.适用于Windows，Mac和Linux.
* [Emacs + ESS](http://ess.r-project.org/) -  Emacs Speaks Statistics是emacs文本编辑器的附加软件包.
* [Sublime Text + R-Box](http://github.com/randy3k/R-Box/) -  Sublime Text 2/3的附加软件包.
* [TextMate + r.tmblundle](https://github.com/textmate/r.tmbundle) -  TextMate 1/2的附加软件包.
* [StatET](http://www.walware.de/goto/statet) - 基于Eclipse的IDE for R.
* [Revolution R Enterprise](https://mran.microsoft.com/) -  Revolution R将免费提供给学术用户，商业软件将专注于大数据，大规模多处理器功能.
* [R Commander](http://socserv.mcmaster.ca/jfox/Misc/Rcmdr/) - 提供基本图形用户界面的包.
* [Deducer](http://www.deducer.org/pmwiki/pmwiki.php?n=Main.DeducerManual?from=Main.HomePage) - 菜单驱动的数据分析GUI，带有数据编辑器等电子表格.
* [Radiant](https://radiant-rstats.github.io/docs) - 基于Shiny的独立于平台的基于浏览器的界面，用于R中的业务分析.
* [Vim-R](https://github.com/vim-scripts/Vim-R-plugin) -  R的Vim插件
* [Nvim-R](https://github.com/jalvesaq/Nvim-R) -  R的Neovim插件
* [JASP](https://jasp-stats.org/) - 一个完整的贝叶斯和Frequentist方法包，这是SPSS用户所熟悉的.
* [Bio7](http://www.bio7.org/) -  IDE包含用于生态建模的模型创建，科学图像分析和统计分析的工具.
* [RTVS](http://microsoft.github.io/RTVS-docs/) - 适用于Visual Studio的R工具.
* [rtichoke](https://github.com/randy3k/rtichoke) - 具有语法高亮功能的现代R控制台.
* [RKWard](https://rkward.kde.org/) -  R的可扩展IDE / GUI

## Syntax
*包改变了你使用R. *的方式

* [pipeR](https://github.com/renkun-ken/pipeR) - 多范式管道实施.
* [lambda.r](https://github.com/zatonovo/lambda.r) -  R中的函数编程和简单模式匹配
* [purrr](https://github.com/hadley/purrr) - 本着下划线.js精神的R的FP包.

## Data Manipulation
*烹饪数据包.*

* [haven](https://github.com/hadley/haven) - 改进了在R中导入SPSS，Stata和SAS文件的方法.
* [tidyr](https://github.com/hadley/tidyr) - 通过传播和收集功能轻松整理数据.
* [rlist](https://github.com/renkun-ken/rlist) - 用于使用列表进行非表格数据操作的工具箱.
* [jsonlite](https://github.com/jeroenooms/jsonlite) - 一种在R中解析JSON文件的强大而快速的方法
* [ff](http://ff.r-forge.r-project.org/) - 用于存储大型数据集的数据结构.
* [lubridate](https://github.com/tidyverse/lubridate) - 一组用于处理日期和时间的函数.
* [bigmemory](https://github.com/kaneplusplus/bigmemory)   - 共享内存和内存映射矩阵.  big \ *包提供了额外的工具，包括线性模型（[biglm](http://cran.r-project.org/web/packages/biglm/index.html)）和随机森林（[bigrf](https://github.com/aloysius-lim/bigrf)).
* [fuzzyjoin](https://github.com/dgrtwo/fuzzyjoin) - 在不精确的匹配上将表连接在一起.
* [tidyverse](https://github.com/hadley/tidyverse) - 从tidyverse轻松安装和加载包.

## Graphic Displays
*用于显示数据的包.*

* [ggfortify](https://github.com/sinhrks/ggfortify) - 使用一行代码的ggplot2流行统计包的统一接口.
* [ggrepel](https://github.com/slowkow/ggrepel) - 将重叠的文本标签相互分开.
* [ggalt](https://github.com/hrbrmstr/ggalt) -  ggplot2的额外坐标系，Geoms和统计变换.
* [ggtree](https://github.com/GuangchuangYu/ggtree) - 系统发育树的可视化和注释.
* [ggtech](https://github.com/ricardo-bion/ggtech) -  ggplot2技术主题和规模
* [ggplot2 Extensions](https://ggplot2-exts.github.io/ggiraph.html) - 展示ggplot2扩展.
* [lattice](https://github.com/deepayan/lattice) - 强大而优雅的高级数据可视化系统.
* [corrplot](https://github.com/taiyun/corrplot)   - 相关矩阵或一般矩阵的图形显示.  它还包含一些执行矩阵重新排序的算法.
* [rgl](http://cran.r-project.org/web/packages/rgl/index.html) - 用于R的3D可视化设备系统.
* [Cairo](http://cran.r-project.org/web/packages/Cairo/index.html) - 使用cairo图形库的R图形设备，用于创建高质量的显示输出.
* [extrafont](https://github.com/wch/extrafont) - 在R图形中使用字体的工具.
* [showtext](https://github.com/yixuan/showtext) - 使R图形设备能够使用系统字体显示文本.
* [animation](https://github.com/yihui/animation) - 一种在R中使用生成动画图形的简单方法 [ImageMagick](http://imagemagick.org/).
* [gganimate](https://github.com/dgrtwo/gganimate) - 使用ggplot2创建简单的动画.
* [misc3d](https://cran.r-project.org/web/packages/misc3d/index.html) - 处理3d图，等值面等的强大功能.
* [xkcd](https://cran.r-project.org/web/packages/xkcd/index.html) - 在图表中使用xkcd样式.
* [imager](http://dahtah.github.io/imager/) - 基于CImg库的图像处理包，用于处理图像并显示它们.
* [hrbrthemes](https://github.com/hrbrmstr/hrbrthemes) - 以意见，印刷为中心的ggplot2主题和主题组件.
* [waffle](https://github.com/hrbrmstr/waffle) - 在R中制作华夫饼（方饼）图表
* [dendextend](https://github.com/talgalili/dendextend) - 可视化，调整和比较层次聚类的树.
* [r2d3](https://rstudio.github.io/r2d3/) -  D3可视化的R接口
* [Patchwork](https://github.com/thomasp85/patchwork) - 将单独的ggplots组合到同一图形中.


## HTML Widgets
*交互式可视化包.*

* [heatmaply](https://github.com/talgalili/heatmaply) -  D3的交互式热图.
* [d3heatmap](https://github.com/rstudio/d3heatmap) - 带D3的交互式热图（不再维护）.
* [DataTables](http://rstudio.github.io/DT/) - 将R矩阵或数据帧显示为交互式HTML表.
* [dygraphs](https://github.com/rstudio/dygraphs) - 在R中绘制时间序列数据.
* [Leaflet](http://rstudio.github.io/leaflet/) - 最流行的JavaScript库交互式地图之一.
* [MetricsGraphics](http://hrbrmstr.github.io/metricsgraphics/) - 可以轻松创建D3散点图，折线图和直方图.
* [networkD3](http://christophergandrud.github.io/networkD3/) - 来自R的D3 JavaScript网络图
* [scatterD3](https://github.com/juba/scatterD3) - 带D3的交互式散点图.
* [rbokeh](http://hafen.github.io/rbokeh/) -  R接口 [Bokeh](http://bokeh.pydata.org/en/latest/).
* [threejs](https://github.com/bwlewis/rthreejs) - 交互式3D散点图和地球仪.
* [timevis](https://github.com/daattali/timevis) - 创建完全交互式时间轴可视化.
* [visNetwork](https://github.com/datastorm-open/visNetwork) - 使用vis.js库进行网络可视化.
* [wordcloud2](https://github.com/Lchiffon/wordcloud2) -  wordcloud2.js的R接口.
* [highcharter](https://github.com/jbkunst/highcharter) - 基于htmlwidgets的高级图表的R包装器

## Reproducible Research
*用于文化编程和可重复工作流程的软件包.*

* [tinytex](https://github.com/yihui/tinytex) - 轻巧且易于维护的LaTeX发行版
* [xtable](http://cran.r-project.org/web/packages/xtable/index.html) - 将表导出为LaTeX或HTML.
* [rapport](http://rapport-package.info/#intro) - 一个R模板系统.
* [rmarkdown <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://rmarkdown.rstudio.com/) -  R的动态文档
* [Sweave](https://www.statistik.lmu.de/~leisch/Sweave/) - 用于使用R编写LaTeX报告的包.
* [texreg](http://www.philipleifeld.de/software/texreg/texreg.html) - 在LaTex和HTML中格式化统计模型.
* [checkpoint](https://github.com/RevolutionAnalytics/checkpoint) - 从检查点服务器上的快照安装包.
* [brew](https://cran.r-project.org/web/packages/brew/index.html)   - 预先计算数据以增强报告模板.  可与knitr结合使用.
* [ReporteRs](http://davidgohel.github.io/ReporteRs/index.html) - 用于生成Microsoft Word，Microsoft PowerPoint和HTML报告的R包.
* [bookdown](https://bookdown.org/) - 使用R Markdown编写图书.
* [ezknitr](https://github.com/daattali/ezknitr) - 使用&#39;knitr&#39;时避免典型的工作目录痛苦
* [drake](https://github.com/ropensci/drake) - 安 [rOpenSci](https://ropensci.org/) 可重复数据科学工作流程的包装太大了 [knitr](http://yihui.name/knitr/).

## Web Technologies and Services
*上网冲浪套餐.*

* [Web Technologies List](https://github.com/ropensci/webservices) - 有关如何一起使用R和万维网的信息.
* [shinyjs](https://github.com/daattali/shinyjs) - 在几秒钟内轻松改善您的Shiny应用程序中的用户交互和用户体验.
* [RCurl](http://cran.r-project.org/web/packages/RCurl/index.html) -  R的常规网络（HTTP / FTP / ...）客户端界面
* [curl](https://github.com/jeroen/curl) - 适用于R的现代灵活的Web客户端
* [httpuv](https://github.com/rstudio/httpuv) - HTTP and WebSocket server library.
* [XML <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/XML/index.html) - 用于在R中解析和生成XML的工具.
* [OpenCPU <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://www.opencpu.org/) -  R的HTTP API
* [Rfacebook](https://github.com/pablobarbera/Rfacebook) - 通过R访问Facebook API.
* [RSiteCatalyst](https://github.com/randyzwitch/RSiteCatalyst) - 用于Adobe Analytics的R客户端库.
* [plumber](https://github.com/trestletech/plumber) - 将现有R代码公开为Web API的库.

## Parallel Computing
*并行计算包.*

* [parallel](http://cran.r-project.org/web/views/HighPerformanceComputing.html) -  R从版本2.14.0开始，其中包括一个新的软件包并行包含（略微修改）的软件包副本 [multicore](http://cran.r-project.org/web/packages/multicore/index.html) 和 [snow](http://cran.r-project.org/web/packages/snow/index.html).
* [Rmpi](http://cran.r-project.org/web/packages/Rmpi/index.html)   -  Rmpi​​为MPI API提供接口（包装器）.  它还提供交互式R从站环境.
* [foreach <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/foreach/index.html) - 并行执行循环.
* [future <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://cran.r-project.org/package=future)   - 用于R中并行和分布式处理的最小，高效，跨平台的统一Future API;  专为初学者和高级开发人员设计.
* [DistributedR](https://github.com/vertica/DistributedR) -  HP Vertica Analytics Team的可扩展高性能平台.
* [ddR](https://github.com/vertica/ddR) - 提供分布式数据结构并简化R中的分布式计算.
* [sparklyr](http://spark.rstudio.com/) - 来自RStudio的Apache Spark的R接口.
* [batchtools](https://cran.r-project.org/package=batchtools) - 使用LSF，TORQUE，Slurm，OpenLava，SGE和Docker Swarm进行高性能计算.

## High Performance
*使R更快的包装.*

* [Rcpp <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://rcpp.org/) -  Rcpp在R之上提供了强大的API，使R中的函数速度更快.
* [Rcpp11](https://github.com/Rcpp11/Rcpp11) -  Rcpp11是对Rcpp的完全重新设计，目标是C ++ 11.
* [compiler](http://stat.ethz.ch/R-manual/R-devel/library/compiler/html/compile.html) - 使用JIT加速R代码

## Language API
*其他语言的套餐.*

* [rJava](http://cran.r-project.org/web/packages/rJava/) - 低级R到Java接口.
* [jvmr](https://github.com/cran/jvmr) - 集成R，Java和Scala.
* [rJython](http://cran.r-project.org/web/packages/rJython/index.html) - 通过Jython与Python的R接口.
* [rPython](http://cran.r-project.org/web/packages/rPython/index.html) - 允许R调用Python的包.
* [runr](https://github.com/yihui/runr) - 从R运行Julia和Bash
* [RJulia](https://github.com/armgong/RJulia) -  R包叫朱莉娅.
* [JuliaCall](https://github.com/Non-Contradiction/JuliaCall) -  R和Julia之间的无缝整合.
* [RinRuby](https://sites.google.com/a/ddahl.org/rinruby-users/) - 一个Ruby库，它集成了Ruby中的R解释器.
* [R.matlab](http://cran.r-project.org/web/packages/R.matlab/index.html) - 读取和写入MAT文件以及R-to-MATLAB连接.
* [RcppOctave](https://github.com/renozao/RcppOctave) -  Octave和Matlab的无缝接口.
* [RSPerl](http://www.omegahat.org/RSPerl/) - 用于从Perl和Perl从R调用R的双向接口.
* [V8](https://github.com/jeroenooms/V8) - 嵌入式JavaScript引擎.
* [htmlwidgets](http://www.htmlwidgets.org/) - 将最好的JavaScript数据可视化带到R.
* [rpy2](http://rpy.sourceforge.net/) -  R的Python接口

## Database Management
*用于管理数据的包.*

* [RODBC](http://cran.r-project.org/web/packages/RODBC/) -  R的ODBC数据库访问
* [DBI](https://github.com/rstats-db/DBI) - 定义R和数据库管理系统之间的通用接口.
* [elastic](https://github.com/ropensci/elastic) -  Elasticsearch HTTP API的包装器
* [mongolite](https://github.com/jeroenooms/mongolite) - 用于R的流式Mongo客户端
* [odbc](https://github.com/r-dbi/odbc) - 连接到ODBC数据库（使用DBI接口）
* [RMariaDB](https://github.com/rstats-db/RMariaDB) -  MariaDB的R接口（旧的RMySQL包的替代品）
* [RMySQL](http://cran.r-project.org/web/packages/RMySQL/) -  MySQL数据库的R接口.
* [ROracle](http://cran.r-project.org/web/packages/ROracle/index.html) - 基于OCI的Oracle数据库接口
* [RPostgreSQL](https://code.google.com/p/rpostgresql/) -  PostgreSQL数据库系统的R接口.
* [RSQLite](http://cran.r-project.org/web/packages/RSQLite/) -  R的SQLite接口
* [RJDBC](http://cran.r-project.org/web/packages/RJDBC/) - 通过JDBC接口提供对数据库的访问.
* [rmongodb](https://github.com/mongosoup/rmongodb) -  MongoDB的R驱动程序.
* [rredis](http://cran.r-project.org/web/packages/rredis/) -  Redis客户端为R.
* [RCassandra](http://cran.r-project.org/web/packages/RCassandra/index.html) - 直接接口（不是Java）到Apache Cassanda的最基本功能.
* [RHive](https://github.com/nexr/RHive) -  R扩展通过Apache Hive促进分布式计算.
* [RNeo4j](https://github.com/nicolewhite/Rneo4j) -  Neo4j图形数据库驱动程序.
* [rpostgis](https://github.com/mablab/rpostgis) - 到PostGIS数据库的R接口并在R中获取空间对象

## Machine Learning
*使R更聪明的包裹.*

* [ahaz](http://cran.r-project.org/web/packages/ahaz/index.html) - 半参数加性危险回归的正则化.
* [arules](http://cran.r-project.org/web/packages/arules/index.html) - 挖掘关联规则和频繁项目集
* [bigrf](http://cran.r-project.org/web/packages/bigrf/index.html) - 大随机森林：分类和回归森林
大数据集
* [bigRR](http://cran.r-project.org/web/packages/bigRR/index.html) - 广义岭回归（p &gt;&gt; n具有特殊优势
cases)
* [bmrm](http://cran.r-project.org/web/packages/bmrm/index.html) - 规范风险最小化方案的捆绑方法
* [Boruta](http://cran.r-project.org/web/packages/Boruta/index.html) - 用于所有相关特征选择的包装算法
* [bst](http://cran.r-project.org/web/packages/bst/index.html) - 渐变提升
* [C50](http://cran.r-project.org/web/packages/C50/index.html) -  C5.0决策树和基于规则的模型
* [caret <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/caret/index.html) - 分类和回归训练
* [Clever Algorithms For Machine Learning](https://github.com/jbrownlee/CleverAlgorithmsMachineLearning)
* [CORElearn](http://cran.r-project.org/web/packages/CORElearn/index.html) - 分类，回归，特征评估和序数
evaluation
* [CoxBoost](http://cran.r-project.org/web/packages/CoxBoost/index.html) -  Cox模型通过基于可能性的单次生存提升
终点或竞争风险
* [Cubist](http://cran.r-project.org/web/packages/Cubist/index.html) - 基于规则和实例的回归建模
* [e1071](http://cran.r-project.org/web/packages/e1071/index.html) - 统计部的杂项职能（e1071），TU Wien
* [earth](http://cran.r-project.org/web/packages/earth/index.html) - 多元自适应回归样条模型
* [elasticnet](http://cran.r-project.org/web/packages/elasticnet/index.html) - 用于稀疏估计和稀疏PCA的弹性网络
* [ElemStatLearn](http://cran.r-project.org/web/packages/ElemStatLearn/index.html) - 书中的数据集，功能和例子：“元素
统计学习，数据挖掘，推理和
预测“由Trevor Hastie，Robert Tibshirani和Jerome
Friedman
* [evtree](http://cran.r-project.org/web/packages/evtree/index.html) - 全球最优树木的进化学习
* [forecast](http://cran.r-project.org/web/packages/forecast/index.html) - 使用ARIMA，ETS，STLM，TBATS和神经网络模型进行时间序列预测
* [forecastHybrid](http://cran.r-project.org/web/packages/forecastHybrid/index.html) - 来自“预测”包的ARIMA，ETS，STLM，TBATS和神经网络模型的自动集合和交叉验证
* [FSelector](https://cran.r-project.org/web/packages/FSelector/index.html) - 基于子集搜索或特征排名方法的特征选择框架.
* [frbs](http://cran.r-project.org/web/packages/frbs/index.html) - 用于分类和回归任务的基于模糊规则的系统
* [GAMBoost](http://cran.r-project.org/web/packages/GAMBoost/index.html) - 基于可能性的广义线性和加性模型
boosting
* [gamboostLSS](http://cran.r-project.org/web/packages/gamboostLSS/index.html) -  GAMLSS的推进方法
* [gbm](http://cran.r-project.org/web/packages/gbm/index.html) - 广义Boosted回归模型
* [glmnet <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/glmnet/index.html) - 套索和弹性网正则化广义线性模型
* [glmpath](http://cran.r-project.org/web/packages/glmpath/index.html) - 广义线性模型和Cox的L1正则化路径
比例风险模型
* [GMMBoost](http://cran.r-project.org/web/packages/GMMBoost/index.html) - 基于似然的推广广义混合模型
* [grplasso](http://cran.r-project.org/web/packages/grplasso/index.html) - 使用Group Lasso惩罚符合用户指定的模型
* [grpreg](http://cran.r-project.org/web/packages/grpreg/index.html) - 具有分组的回归模型的正则化路径
covariates
* [h2o <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/h2o/index.html) -  Deeplearning，Random forest，GBM，KMeans，PCA，GLM
* [hda](http://cran.r-project.org/web/packages/hda/index.html) - 异方差判别分析
* [ipred](http://cran.r-project.org/web/packages/ipred/index.html) - 改进的预测因子
* [kernlab](http://cran.r-project.org/web/packages/kernlab/index.html) -  kernlab：基于内核的机器学习实验室
* [klaR](http://cran.r-project.org/web/packages/klaR/index.html) - 分类和可视化
* [kohonen](http://cran.r-project.org/web/packages/kohonen/) - 有监督和无监督的自组织地图.
* [lars](http://cran.r-project.org/web/packages/lars/index.html) - 最小角度回归，套索和前进阶段
* [lasso2](http://cran.r-project.org/web/packages/lasso2/index.html) -  L1约束估计又名&#39;套索&#39;
* [LiblineaR](http://cran.r-project.org/web/packages/LiblineaR/index.html) - 基于Liblinear C / C ++库的线性预测模型
* [LogicReg](http://cran.r-project.org/web/packages/LogicReg/index.html) - 逻辑回归
* [maptree](http://cran.r-project.org/web/packages/maptree/index.html) - 映射，修剪和绘制树模型
* [mboost](http://cran.r-project.org/web/packages/mboost/index.html) - 基于模型的提升
* [mvpart](http://cran.r-project.org/web/packages/mvpart/index.html) - 多变量分区
* [ncvreg](http://cran.r-project.org/web/packages/ncvreg/index.html) -  SCAD和MCP惩罚回归的正则化路径
models
* [nnet](http://cran.r-project.org/web/packages/nnet/index.html) -  eed-forward神经网络和多项式对数线性模型
* [oblique.tree](http://cran.r-project.org/web/packages/oblique.tree/index.html) - 分类数据的倾斜树
* [pamr](http://cran.r-project.org/web/packages/pamr/index.html) -  Pam：微阵列的预测分析
* [party](http://cran.r-project.org/web/packages/party/index.html) - 递归派系实验室
* [partykit](http://cran.r-project.org/web/packages/partykit/index.html) - 递归派系工具包
* [penalized](http://cran.r-project.org/web/packages/penalized/index.html) -  L1（套索和融合套索）和L2（脊）惩罚估计
在GLM和Cox模型中
* [penalizedLDA](http://cran.r-project.org/web/packages/penalizedLDA/index.html) - 使用Fisher线性判别式进行惩罚分类
* [penalizedSVM](http://cran.r-project.org/web/packages/penalizedSVM/index.html) - 使用惩罚函数的特征选择SVM
* [quantregForest](http://cran.r-project.org/web/packages/quantregForest/index.html) -  quantregForest：分位数回归森林
* [randomForest](http://cran.r-project.org/web/packages/randomForest/index.html) -  randomForest：Breiman和Cutler的随机森林用于分类和回归.
* [randomForestSRC](http://cran.r-project.org/web/packages/randomForestSRC/index.html) -  randomForestSRC：生存，回归和分类的随机森林（RF-SRC）.
* [ranger](https://github.com/imbs-hl/ranger) - 随机森林的快速实施.
* [rattle](http://cran.r-project.org/web/packages/rattle/index.html) - 用于R中数据挖掘的图形用户界面
* [rda](http://cran.r-project.org/web/packages/rda/index.html) - 缩小的质心正则判别分析
* [rdetools](http://cran.r-project.org/web/packages/rdetools/index.html) - 特征空间中的相关维度估计（RDE）
* [REEMtree](http://cran.r-project.org/web/packages/REEMtree/index.html) - 纵向随机效应的回归树（面板）
Data
* [relaxo](http://cran.r-project.org/web/packages/relaxo/index.html) - 轻松的套索
* [rgenoud](http://cran.r-project.org/web/packages/rgenoud/index.html) - 使用衍生物进行GENetic优化的R版本
* [rgp](http://cran.r-project.org/web/packages/rgp/index.html) -  R遗传编程框架
* [Rmalschains](http://cran.r-project.org/web/packages/Rmalschains/index.html) - 使用Memetic算法和局部连续优化
在R中搜索链（MA-LS-Chains）
* [rminer](http://cran.r-project.org/web/packages/rminer/index.html) - 更简单地使用数据挖掘方法（例如NN和SVM）
分类和回归
* [ROCR](http://cran.r-project.org/web/packages/ROCR/index.html) - 可视化评分分类器的性能
* [RoughSets](http://cran.r-project.org/web/packages/RoughSets/index.html) - 使用粗糙集和模糊粗糙集理论进行数据分析
* [rpart](http://cran.r-project.org/web/packages/rpart/index.html) - 递归分区和回归树
* [RPMM](http://cran.r-project.org/web/packages/RPMM/index.html) - 递归分区混合模型
* [RSNNS](http://cran.r-project.org/web/packages/RSNNS/index.html) - 使用斯图加特神经网络的R中的神经网络
模拟器（SNNS）
* [Rsomoclu](https://cran.r-project.org/web/packages/Rsomoclu/index.html) - 自组织地图的并行实施.
* [RWeka](http://cran.r-project.org/web/packages/RWeka/index.html) -  R / Weka界面
* [RXshrink](http://cran.r-project.org/web/packages/RXshrink/index.html) -  RXshrink：通过广义脊或最小的最大似然收缩
角度回归
* [sda](http://cran.r-project.org/web/packages/sda/index.html) - 收缩判别分析和CAT分数变量选择
* [SDDA](http://cran.r-project.org/web/packages/SDDA/index.html) - 逐步对角判别分析
* [SuperLearner](https://github.com/ecpolley/SuperLearner) 和 [subsemble](http://cran.r-project.org/web/packages/subsemble/index.html) - 多算法集成学习包.
* [svmpath](http://cran.r-project.org/web/packages/svmpath/index.html) -  svmpath：SVM Path算法
* [tgp](http://cran.r-project.org/web/packages/tgp/index.html) - 贝叶斯treed高斯过程模型
* [tree](http://cran.r-project.org/web/packages/tree/index.html) - 分类和回归树
* [varSelRF](http://cran.r-project.org/web/packages/varSelRF/index.html) - 使用随机森林进行变量选择

## Natural Language Processing
*自然语言处理包.*

* [text2vec](https://github.com/dselivanov/text2vec) - 矢量化和Word嵌入的快速文本挖掘框架.
* [tm](http://cran.r-project.org/web/packages/tm/index.html) - 一个全面的文本挖掘框架.
* [openNLP](http://cran.r-project.org/web/packages/openNLP/index.html) -  Apache OpenNLP工具界面.
* [koRpus](http://cran.r-project.org/web/packages/koRpus/index.html) - 用于文本分析的R包.
* [zipfR](http://cran.r-project.org/web/packages/zipfR/index.html) - 词频分布的统计模型.
* [NLP](http://cran.r-project.org/web/packages/NLP/index.html) - 自然语言处理的基本功能.
* [LDAvis](https://github.com/cpsievert/LDAvis) - 主题模型的交互式可视化.
* [topicmodels](https://cran.r-project.org/web/packages/topicmodels/index.html) - 由David M. Blei为主题建模（Latent Dirichlet Allocation（LDA）和Correlated Topics Models（CTM））开发的C代码的主题建模界面.
* [syuzhet](https://cran.r-project.org/web/packages/syuzhet/index.html) - 使用三种不同的情绪词典从文本中提取情绪.
* [SnowballC](https://cran.rstudio.com/web/packages/SnowballC/index.html) - 基于C libstemmer UTF-8库的Snowball词干分析器.
* [quanteda](https://github.com/kbenoit/quanteda) - 用于文本数据定量分析的R函数.
* [Topic Models Resources](https://github.com/trinker/topicmodels_learning) - 主题模型学习和R相关资源.
* [MonkeyLearn](https://github.com/masalmon/monkeylearn) - 🐒 R package for text analysis with Monkeylearn 🐒.
* [tidytext](http://tidytextmining.com/index.html) - 将Hadley Wickham的整洁原则应用于文本挖掘.
* [utf8](https://github.com/patperry/r-utf8) - 操作和打印UTF-8文本，修复R的UTF-8处理中的多个错误.

## Bayesian
*贝叶斯推理的包.*

* [coda](http://cran.r-project.org/web/packages/coda/index.html) -  MCMC的输出分析和诊断.
* [mcmc](http://cran.r-project.org/web/packages/mcmc/index.html) - 马尔可夫链蒙特卡洛.
* [MCMCpack](http://mcmcpack.berkeley.edu/) - Markov chain Monte Carlo (MCMC) Package.
* [R2WinBUGS](http://cran.r-project.org/web/packages/R2WinBUGS/index.html) - 从R / S-PLUS运行WinBUGS和OpenBUGS.
* [BRugs](http://cran.r-project.org/web/packages/BRugs/index.html) -  OpenBUGS MCMC软件的R接口.
* [rjags](http://cran.r-project.org/web/packages/rjags/index.html) -  JAGS MCMC库的R接口.
* [rstan <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://mc-stan.org/interfaces/rstan.html) - 与Stan MCMC软件的R接口.

## Optimization
*优化套餐.*

* [lpSolve](https://cran.rstudio.com/web/packages/lpSolve/index.html) - 用于解决线性/整数程序的`Lp_solve`接口.
* [minqa](https://cran.rstudio.com/web/packages/minqa/index.html) - 通过二次近似的无导数优化算法.
* [nloptr](https://cran.rstudio.com/web/packages/nloptr/index.html) -  NLopt是一个用于非线性优化的免费/开源库.
* [ompr](https://cran.rstudio.com/web/packages/ompr/index.html) - 直接在R中以代数方式对混合整数线性程序进行建模
* [Rglpk](https://cran.rstudio.com/web/packages/Rglpk/index.html) -  R / GNU线性编程套件接口
* [ROI](https://cran.rstudio.com/web/packages/ROI/index.html) -  R优化基础设施（&#39;ROI&#39;）是一个用于处理R中优化问题的复杂框架.

## Finance
*处理钱的包裹.*

* [quantmod <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://www.quantmod.com/) -  R的定量财务建模和交易框架
* [TTR](http://cran.r-project.org/web/packages/TTR/index.html) - 用R构建技术交易规则的功能和数据
* [PerformanceAnalytics](http://cran.r-project.org/web/packages/PerformanceAnalytics/index.html) - 用于绩效和风险分析的计量经济学工具.
* [zoo <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/zoo/index.html) - 常规和不规则时间序列的S3基础设施.
* [xts](http://cran.r-project.org/web/packages/xts/index.html) - 可扩展时间序列.
* [tseries](http://cran.r-project.org/web/packages/tseries/index.html) - 时间序列分析和计算金融.
* [fAssets](http://cran.r-project.org/web/packages/fAssets/index.html) - 分析和建模金融资产.

## Bioinformatics and Biostatistics
*用于处理生物数据集的包.*

* [Bioconductor <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://www.bioconductor.org/) - 用于分析和理解高通量基因组数据的工具.
* [genetics](http://cran.r-project.org/web/packages/genetics/index.html) - 处理遗传数据的类和方法.
* [gap](http://cran.r-project.org/web/packages/gap/index.html) - 用于人口和家庭数据遗传数据分析的综合方案.
* [ape](http://cran.r-project.org/web/packages/ape/index.html) - 系统发育和进化分析.
* [pheatmap](http://cran.r-project.org/web/packages/pheatmap/index.html) - 漂亮的热图变得容易.


## Network Analysis
*用于构建，分析和可视化网络数据的软件包.*

* [Network Analysis List](https://github.com/briatte/awesome-network-analysis) - 网络分析相关资源.
* [igraph <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://igraph.org/r/) - 网络分析工具的集合.
* [network](https://cran.r-project.org/web/packages/network/index.html) - 在R中操纵关系数据的基本工具
* [sna](https://cran.r-project.org/web/packages/sna/index.html) - 基本网络措施和可视化工具.
* [netdiffuseR](https://github.com/USCCANA/netdiffuseR) - 网络扩散分析工具.
* [networkDynamic](https://cran.r-project.org/web/packages/networkDynamic/) - 支持动态，（内部）时间网络.
* [ndtv](https://cran.r-project.org/web/packages/ndtv/) - 用于构建各种格式的动态网络数据的动画可视化的工具.
* [statnet](http://statnet.org/) - 许多R网络分析包背后的项目.
* [ergm](https://cran.r-project.org/web/packages/ergm/index.html) -  R中的指数随机图模型
* [latentnet](https://cran.r-project.org/web/packages/latentnet/index.html) - 网络对象的潜在位置和群集模型.
* [tnet](https://cran.r-project.org/web/packages/tnet/index.html) - 加权，双模和纵向网络的网络措施.
* [rgexf](https://bitbucket.要么g/gvegayon/rgexf/wiki/Home) - 将网络对象从R导出到 [GEXF](http://gexf.net/f要么mat/)，用于操纵网络软件等 [Gephi](https://gephi.要么g/) 要么 [Sigma](http://sigmajs.要么g/).
* [visNetwork](https://github.com/datastorm-open/visNetwork) - 使用vis.js库进行网络可视化.

## Spatial
*探索地球的套餐.*

* [CRAN Task View: Analysis of Spatial Data](https://cran.r-project.org/web/views/Spatial.html)- 空间分析相关资源.
* [Leaflet](http://rstudio.github.io/leaflet/) - 最流行的JavaScript库交互式地图之一.
* [ggmap](https://github.com/dkahle/ggmap) - 使用ggplot2在R中绘制地图.
* [REmap](https://github.com/Lchiffon/REmap) - 用于交互式地图数据可视化的JavaScript库ECharts的R接口.
* [sf](https://cran.r-project.org/web/packages/sf/index.html) - 改进的空间数据类和方法.
* [sp](https://edzer.github.io/sp/) - 空间数据的类和方法.
* [rgeos](https://cran.r-project.org/web/packages/rgeos/index.html) - 几何引擎接口 - 开源
* [rgdal](https://cran.r-project.org/web/packages/rgdal/index.html) - 地理空间数据抽象库的绑定
* [maptools](https://cran.r-project.org/web/packages/maptools/index.html) - 用于读取和处理空间对象的工具
* [gstat](https://github.com/edzer/gstat) - 空间和时空地质统计建模，预测和模拟.
* [spacetime](https://github.com/edzer/spacetime) - 用于时空数据的R类和方法.
* [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html) - 为地图提供配色方案
* [spatstat](https://github.com/spatstat/spatstat) - 空间点模式分析，模型拟合，模拟，测试
* [spdep](https://cran.r-project.org/web/packages/spdep/index.html) - 空间依赖性：加权方案，统计和模型
* [tigris](https://github.com/walkerke/tigris) - 在R中下载并使用Census TIGER / Line shapefiles

## R Development
*包裹套餐.*

* [Package Development List](https://github.com/ropensci/PackageDevelopment) -  R包以改进包开发.
* [promises](https://cran.r-project.org/web/packages/promises/index.html) - 基于Promise的异步编程的抽象
* [lineprof](https://github.com/hadley/lineprof) - 在R中可视化行分析结果
* [packrat](https://github.com/rstudio/packrat) - 使您的R项目更加孤立，便携和可重复.
* [installr](https://github.com/talgalili/installr/) - 从R内部安装软件的功能（适用于Windows）.
* [import](https://github.com/smbache/import/) -  R的导入机制
* [modules](https://github.com/klmr/modules) -  R的替代（Python风格）模块系统
* [RStudio Addins](https://github.com/daattali/rstudio-addins) -  RStudio插件列表.
* [drat](https://github.com/eddelbuettel/drat) - 在GitHub或其他repos上创建和使用R存储库.
* [covr](https://github.com/jimhester/covr) - 测试R包的覆盖范围，并（可选）将结果上传到 [coveralls](https://coveralls.io/) 要么 [codecov](https://codecov.io/).
* [lintr](https://github.com/jimhester/lintr) -  R的静态代码分析以强制执行代码样式.
* [staticdocs](https://github.com/hadley/staticdocs) - 为R包生成静态html文档.
* [sinew](https://github.com/metrumresearchgroup/sinew) - 生成使用从函数脚本中删除的信息填充的roxygen2骨架.

## Logging
*记录包*

* [futile.logger](https://github.com/zatonovo/futile.logger) -  R中的日志包类似于log4j
* [log4r](https://github.com/johnmyleswhite/log4r) -  R的log4j导数
* [logging](https://cran.r-project.org/web/packages/logging/index.html) - 模拟python日志包的日志包.

## Data Packages
*便捷的数据包*

* [engsoccerdata](https://github.com/jalapic/engsoccerdata) - 英国和欧洲足球比赛结果1871-2016.
* [gapminder](http://github.com/jennybc/gapminder) - 摘自Gapminder数据集（过去50年来各国的数据）.

## Other Tools
* R *的便捷工具

* [git2r](https://github.com/ropensci/git2r) - 使您可以从R编程访问Git存储库.

## Other Interpreters
*替代R引擎.*

* [CXXR](https://www.cs.kent.ac.uk/projects/cxxr/) - 将R重构为C ++.
* [fastR](https://bitbucket.org/allr/fastr/wiki/Home) -  FastR是Truffle和Graal上Java语言的一种实现.
* [pqR](http://www.pqr-project.org/) -  R的“快速”实现
* [renjin](http://www.renjin.org/) - 一个基于JVM的R解释器.
* [rho](https://github.com/rho-devel/rho) - 将R语言的解释器重构为R的完全兼容，高效的VM.
* [riposte](https://github.com/jtalbot/riposte) - 快速解释器和RIT JIT
* [TERR](http://spotfire.tibco.com/discover-spotfire/what-does-spotfire-do/predictive-analytics/tibco-enterprise-runtime-for-r-terr) -  TIBCO Enterprise Runtime for R.


## Learning R
*学习套餐R. *

* [swirl <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://swirlstats.com/) - 直接在R控制台中的交互式R教程.

## Resources

在哪里发现新的R-esources.

## Websites

* [R-project](http://www.r-project.org/) - 统计计算R项目.
* [R Weekly](https://rweekly.org)   - 关于R和数据科学的每周更新.  R Weekly在GitHub上公开开发.
* [R Bloggers](http://www.r-bloggers.com/) - 网络上散布着关于R的博客.这只是许多这些Feed的聚合器.
* [Quick-R](http://www.statmethods.net/) - 一个很好的快速参考.
* [Advanced R <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://adv-r.had.co.nz/) -  Advanced R书籍的在线版本.
* [Efficient R Programming](https://csgillespie.github.io/efficientR/) -  O&#39;Reilly书籍的在线主页：高效R编程.
* [CRAN Task Views](http://cran.r-project.org/web/views/) - Task Views for CRAN packages.
* [The R Programming Wikibook](https://en.wikibooks.org/wiki/R_Programming) -  R的协作手册
* [R-users](https://www.r-users.com/) -  R用户（以及希望雇用他们的人）的工作板
* [R Cookbook](http://www.cookbook-r.com/) - 一个支持问题的面向问题的网站 [R Graphics Cookbook](http://shop.oreilly.com/product/0636920023135.do).
* [tryR](http://tryr.codeschool.com/) -  R入门的快速课程
* [RDocumentation](https://www.rdocumentation.org/) - 使用RDocumentation搜索所有CRAN，Bioconductor，Github软件包及其存档.

## Books

* [Readings in Applied Data Science](https://github.com/hadley/stats337) - 这些读数反映了哈德利关于应用数据科学的个人想法.
* [R Books List](https://github.com/RomanTsegelskyi/rbooks) -  R书籍清单.
* [The Art of R Programming](http://shop.oreilly.com/product/9781593273842.do) - 这是一个很好的资源，用于系统地学习R中的对象类型，控制语句，变量范围，类和调试等基础知识.
* [Free Books](https://cran.r-project.org/other-docs.html) -  CRAN提供多种语言的文档.
* [R Cookbook](http://shop.oreilly.com/product/9780596809164.do) - 使用R执行许多常见统计任务的快速简单介绍
*作为约翰霍普金斯数据科学专业化的一部分撰写的书籍：
  * [Exploratory Data Analysis with R](https://leanpub.com/exdata) -  R中各种数据的基本分析技能.
  * [R Programming for Data Science](https://leanpub.com/rprogramming) - 更高级的数据分析，依赖于R编程.
  * [Report Writing for Data Science in R](https://leanpub.com/reportwriting) - 基于R的方法，用于可重复研究和报告生成.
* [R Packages](http://r-pkgs.had.co.nz/) - 关于编写R包的书（纸质和网站格式）.
* [R in Action](http://www.manning.com/kabacoff2/) - 本书面向所有级别的用户，包括初级，中级和高级R，从“探索R数据结构”到运行回归和进行因子分析.
* [Use R!](http://www.springer.com/series/6991?detailsPage=titles)   -  Springer的这一系列廉价且专注的书籍出版了针对从业者的短篇书籍.  书籍可以讨论在特定主题领域中使用R，例如贝叶斯网络，ggplot2和Rcpp.
* [R for SAS and SPSS users](http://r4stats.com/books/free-version/) - 为熟悉SAS或SPSS的用户提供的优质资源.
* [An Introduction to R](https://cran.r-project.org/doc/manuals/R-intro.pdf) - 关于R的非常好的介绍性文本，也涵盖了一些高级主题.
* [Introduction to Statistical Learning with Application in R](http://www-bcf.usc.edu/~gareth/ISL/)   -  *统计学习要素的简化和“运作”版本*.  其作者提供的免费软拷贝.
* [The R Inferno](http://www.burns-stat.com/pages/Tutor/R_inferno.pdf) - 帕特里克·伯恩斯（Patrick Burns）深入了解了R的细节及其怪癖！
* [R for Data Science](http://r4ds.had.co.nz/) - 来自RStudio开发人员的免费书籍，重点是数据科学工作流程.
* [Learning R Programming](https://www.packtpub.com/big-data-and-business-intelligence/learning-r-programming) - 学习R作为从基础到高级主题的编程语言.

## Podcasts

* [Not So Standard Deviations](https://soundcloud.com/nssd-podcast) - 数据科学播客.
  * [@Roger Peng](https://twitter.com/rdpeng) 和 [@Hilary Parker](https://twitter.com/hspter).
* [R World News](http://www.rworld.news/blog/) -  R World News帮助您跟上R社区内的各种事件.
  * [@Bob Rudis](https://twitter.com/hrbrmstr) 和 [@Jay Jacobs](https://twitter.com/jayjacobs).
* [The R-Podcast](https://r-podcast.org/) - 就如何使用R提供实用建议.
  * [@Eric Nantz](https://r-podcast.org/stories/contact.html).
* [R Talk](http://rtalk.org) - 统计软件和语言的新闻和讨论R.
  * [@Oliver Keyes](https://twitter.com/quominus), [@Jasmine Dumas](https://twitter.com/jasdumas), [@Ted Hart](https://twitter.com/emhrt_) 和 [@Mikhail Popov](https://twitter.com/bearloga).
* [R Weekly](https://rweekly.org) - 关于R社区的每周新闻更新.

## Reference Cards

* [RStudio Cheat Sheets](https://www.rstudio.com/resources/cheatsheets/)
* [R Reference Card 2.0](http://cran.r-project.org/doc/contrib/Baggott-refcard-v2.pdf) - 经Emmanuel Paradis许可从R开始的材料（Matt Baggott的第2版）.
* [Regression Analysis Refcard](http://cran.r-project.org/doc/contrib/Ricci-refcard-regression.pdf) -  R回归分析参考卡.
* [Reference Card for ESS](http://ess.r-project.org/refcard.pdf) -  ESS参考卡.

## MOOCs
*大规模开放在线课程.*

* [Johns Hopkins University Data Science Specialization](https://www.coursera.org/specialization/jhudatascience/1) -  9门课程，包括：R简介，文学分析工具，Shiny等等.
* [HarvardX Biomedical Data Science](http://simplystatistics.org/2014/11/25/harvardx-biomedical-data-science-open-online-training-curriculum-launches-on-january-19/) - 生命科学R简介.
* [Explore Statistics with R](https://www.edx.org/course/explore-statistics-r-kix-kiexplorx-0) - 涵盖R中的介绍，数据处理和统计分析.

## Lists
*学习领域知识的丰富资源.*

* [Books](https://github.com/RomanTsegelskyi/rbooks) -  R书籍清单.
* [ggplot2 Extensions](https://ggplot2-exts.github.io/ggiraph.html) - 展示ggplot2扩展.
* [Network Analysis](https://github.com/briatte/awesome-network-analysis) - 网络分析相关资源.
* [Open Data](https://github.com/ropensci/opendata) - 使用R获取，解析，操作，创建和共享打开的数据.
* [Posts](https://github.com/qinwf/awesome-R/blob/master/etc/posts.md) - 伟大的R博客文章或Rticles.
* [Package Development](https://github.com/ropensci/PackageDevelopment) -  R包以改进包开发.
* [R Project Conferences](https://www.r-project.org/conferences.html)   - 有关useR的信息！  会议和DSC会议.
* [RStartHere](https://github.com/rstudio/RStartHere) - 按工作流程组织的一些最有用的R包的指南.
* [RStudio Addins](https://github.com/daattali/addinslist) -  RStudio插件列表.
* [Topic Models](https://github.com/trinker/topicmodels_learning) - 主题模型学习和R相关资源.
* [Web Technologies](https://github.com/ropensci/webservices) - 有关如何一起使用R和万维网的信息.

## Other Awesome Lists

* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)
* [lists](https://github.com/jnv/lists)
* [awesome-rshiny](https://github.com/grabear/awesome-rshiny)

## Contributing
欢迎您的贡献！

本作品采用知识共享署名 - 非商业性使用 - 相同方式共享4.0国际许可 -  [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)
