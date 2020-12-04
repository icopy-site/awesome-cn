<div class="github-widget" data-repo="beardicus/awesome-plotters"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Plotters [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

用于计算机控制的绘图机和其他视觉艺术机器人的精选代码和资源清单.



## Hardware

### Plotters

- [AxiDraw](https://shop.evilmadscientist.com/productsmenu/846) -来自的笔式绘图仪 [Evil Mad Scientist](https://www.evilmadscientist.com)，在 [#plottertwitter](https://twitter.com/hashtag/plottertwitter).
- [Line-us](https://www.line-us.com) -可爱的小启动机器人绘图臂.
- [Makeblock XY Plotter](http://learn.makeblock.com/en/xy-plotter-robot-kit) -可破解的XY绘图仪套件（已停产？）.
- [Drawing Robot](https://www.thingiverse.com/thing:2349232) -带3d打印的AxiDraw克隆 [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) 控制器运行grbl固件.
- [4xiDraw](https://www.instructables.com/id/4xiDraw/) -另一个3d可打印的AxiDraw克隆，带有 [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) 控制器运行grbl固件.
- [WaterColorBot](https://watercolorbot.com) -XY艺术机器人和软件以水彩颜料作图.
- [EggBot](https://egg-bot.com) -用于蛋形和球形物体的笔式绘图仪.
- [HP Pen Plotters](https://www.hpmuseum.net/exhibit.php?class=4&cat=24)  -HPGL标准创建者提供的老式台式和落地式笔式绘图仪.  7475A型非常常见，通常可以在eBay上找到.
- [Roland Pen Plotters](https://www.youtube.com/watch?v=6_pwzqPk6Gg)  -老式平板HPGL笔式绘图仪. 在eBay上搜索“ roland dxy”.
- [Polargraph](http://www.polargraph.co.uk) -原始的Polargraph硬件和软件项目.
- [Makelangelo](http://www.makelangelo.com) -开源Polargraph Artbot.
- [BrachioGraph](https://brachiograph.readthedocs.io/en/latest/) -一种便宜，简单的绘图仪，由棍棒，伺服器和运行Python的Raspberry Pi制成.

### Motor Controllers

- [grblShield](https://github.com/synthetos/grblShield) -所有需要的步进电机控制硬件 [Arduino](https://www.arduino.cc) 使用grbl固件导入基于G代码的运动控制器.  （[adafruit](https://www.adafruit.com/product/1750))
- [TinyG](https://github.com/synthetos/TinyG)  -功能更强大的基于6轴G代码的运动控制硬件.  （[adafruit](https://www.adafruit.com/product/1749))
- [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) -与Arduino兼容的Grbl步进电机控制板，类似于 [grblShield](https://github.com/synthetos/grblShield).
- [Raspberry Pi CNC Hat](https://wiki.protoneer.co.nz/Raspberry_Pi_CNC)  -带步进控制器的Raspberry Pi附加板和运行grbl的微控制器. 与Pi的串行引脚接口.

### Accessories

- [WiFi232](http://biosrhythm.com/?page_id=1453)  -通过DB25插头Wifi到RS-232串行. 无线控制串行绘图仪.
- [Plotter Cable Pinout](http://sites.music.columbia.edu/cmc/chiplotle/plotter_cable.pdf)  -适用于大多数HP和Roland绘图仪的绘图仪电缆的示意图. 在eBay或Amazon上搜索“ DB9到DB25串行零调制解调器电缆”或类似产品以查找出售.

### Pens

- [Sharpie Fine Point Plotter Adapter](https://www.thingiverse.com/thing:229982) -3d打印适配器，适合HP-GL绘图仪中的标准Sharpie.
- [Parametric 3d-Printable Plotter Pen Adapter](https://openjscad.org/#https://gist.githubusercontent.com/beardicus/d668c0f6b96be53d16dc/raw/plotter-pen-adapter.jscad) -可调型号，可打印各种笔的适配器.
- [Plotter Pen STL Models](https://www.thingiverse.com/thing:227985) -短和长标准绘图笔的精确STL模型.
- [Pens for AxiDraw](https://wiki.evilmadscientist.com/Pens_for_AxiDraw) -适用于一般绘图仪滥用的笔清单.
- [Pens for EggBot](https://wiki.evilmadscientist.com/Pen_choices) -以鸡蛋和玻璃杯为重点的钢笔建议，但仍普遍适用.
- [JetPens – The Best White Ink Pens](https://www.jetpens.com/blog/the-best-white-ink-pens/pt/340) -对许多白色墨水笔进行全面审查，并附上其覆盖范围的图片.

## Software

### HPGL

HPGL是大多数旧笔式绘图仪，甚至许多新的乙烯基切纸机都使用的基于串行/文本的协议.

- [Chiplotle](https://github.com/drepetto/chiplotle) -用于生成HPGL并与串行绘图仪接口的Python库.
- [HPGL Reference Guide](https://www.isoplotec.co.jp/HPGL/eHPGL.htm) -基于HTML的HPGL参考.
- [HP 7475A Interfacing and Programming Manual](https://archive.org/details/HP7475AInterfacingandProgrammingManual) -已扫描的PDF手册，其中包含完整的HPGL参考.
- [djipco/hpgl](https://github.com/djipco/hpgl) -一个Node.js库，可与HPGL兼容的绘图仪和打印机进行通信.
- [hp2xx](https://www.gnu.org/software/hp2xx)  -GNU工具，可将HPGL转换为其他矢量和栅格格式. 也可以在X11中用作预览.
- [vec](https://github.com/anachrocomputer/vec) -用于生成HPGL的C示例​​代码，带有龟图形界面.
- [d3-hpgl](https://github.com/aubergene/d3-hpgl) -HTML Canvas API的适配器，因此您可以使用常用的输出HPGL [D3](https://d3js.org) 图书馆.
- [HPGL Viewer](https://github.com/drskullster/HPGLViewer) -使用JavaScript和HTML5画布的HPGL Viewer.
- [HPGL Sender](https://github.com/LgHS/hpgl-sender) -用于预览HPGL并将其发送到绘图仪的Web界面.
- [HPGLGraphics](https://github.com/ciaron/HPGLGraphics) -用于编写HPGL文件的处理库.

### G-code

 G代码是用于控制CNC机器的基于文本的标准. 尽管它是为工业机器设计的，但它在许多爱好者3D打印机固件中的使用也使其在小型DIY项目中无处不在.

- [grbl](https://github.com/grbl/grbl) -用于Atmega 328微控制器和Arduino的高性能G代码解释固件.
- [cncjs](https://github.com/cncjs/cncjs) -基于Web的界面，用于控制运行grbl，TinyG或其他基于G代码的固件的CNC机床.
- [node-gcode](https://github.com/ryansturmer/node-gcode) -基于Node.js的G代码解释器和模拟器.
- [svg2gcode](https://github.com/em/svg2gcode) -基于Node.js的命令行实用程序，用于将SVG转换为G代码.
- [svg2gcode](https://github.com/vishpat/svg2gcode) -基于Python的实用程序，可将SVG快速转换为G代码.
- [jscut](http://jscut.org/) -用于将SVG转换为G代码的基于Web的实用程序.
- [Universal-G-Code-Sender](https://github.com/winder/Universal-G-Code-Sender) -基于Java的grbl兼容跨平台G代码发送者.
- [ChiliPeppr Hardware Fiddle](http://chilipeppr.com) -基于Web的模块化工作区，以可视化G代码并控制硬件.
- [gcode-generative-for-processing](https://github.com/o0morgan0o/gcode-generative-for-processing)  -处理库，旨在从简单形状创建gcode.  （设计用于Creality CR10）

### Plotter-Specific

特定于绘图仪或控制器的软件.

- [axidraw](https://github.com/evil-mad/axidraw) -Inkscape的官方AxiDraw扩展.
- [axi](https://github.com/fogleman/axi) -AxiDraw v3的非官方Python库.
- [xy](https://github.com/fogleman/xy) -Makeblock XY绘图仪机器人套件的​​实用程序.
- [LaserGRBL](https://github.com/arkypita/LaserGRBL)  -针对grbl控制器的激光优化Windows GUI. 可以重新用于使用螺线管进行笔上/下移动的DIY笔式绘图仪.
- [Line-us Inkscape Plugin](https://github.com/Line-us/Inkscape-Plugin) -将图纸发送到 [Line-us plotter](https://www.line-us.com) 直接来自Inkscape.
- [Line-us API Examples](https://github.com/Line-us/Line-us-Programming) -的示例代码 [Line-us](https://www.line-us.com) 绘图仪基于G代码的API.
- [@beardicus/line-us](https://github.com/beardicus/line-us) -JavaScript库，用于控制 [Line-us](https://www.line-us.com) 节点或浏览器访问计算机.
- [PenPlotter](https://github.com/RickMcConney/PenPlotter) -使用高级固件的Polargraph控制器.
- [Makelangelo-firmware](https://github.com/MarginallyClever/Makelangelo-firmware) -Makelangelo极谱图机器人的固件.
- [RoboPaint](https://github.com/evil-mad/robopaint) -WaterColorBot的软件.
- [AxiTurtle](https://github.com/ralphcrutzen/AxiTurtle) -处理中AxiDraw的Turtle图形.
- [GRBL-Plotter](https://github.com/svenhb/GRBL-Plotter) -适用于grbl控制器的绘图仪优化的Windows GUI，具有SVG和DXF导入功能以及灵活的笔上/下控制功能.
- [saxi](https://github.com/nornagon/saxi)  -AxiDraw的驱动程序和库. 使用恒定加速运动计划，并自动调整为纸张大小.
- [MP2300-Tools](https://github.com/Jan--Henrik/MP2300-Tools) -用于将HPGL转换为Graphtec的GPGL格式的软件，以及用于Graphtec绘图仪笔适配器的CAD文件.

### Vector Creation

从零开始或通过其他格式转换创建矢量插图的工具.

- [Inkscape](https://inkscape.org) -流行的跨平台开源矢量图形编辑器.
- [p5.js](https://p5js.org) -“ JavaScript库，使艺术家，设计师，教育者和初学者都可以访问编码”.
- [Paper.js](http://paperjs.org) -《矢量图形脚本的瑞士军刀》.
- [ln](https://github.com/fogleman/ln) -用Go语言编写的基于矢量的3D渲染器.
- [autotrace](https://github.com/autotrace/autotrace) -将位图图像转换为矢量图形.
- [stipplegen](https://github.com/evil-mad/stipplegen)  -从位图图像创建有趣的点画.  （[blog post](https://www.evilmadscientist.com/2012/stipplegen2))
- [SquiggleDraw](https://github.com/gwygonik/SquiggleDraw/commits/master) -“ SquiggleDraw将使用亮度更改正弦波的幅度，从图像创建SVG文件”.
- [svgurt](https://svgurt.com) -基于Web的PNG到SVG创意面条.
- [maptrace](https://github.com/mzucker/maptrace) -通过跟踪栅格图像来生成水密多边形矢量地图.
- [Drawbot_image_to_gcode_v2](https://github.com/Scott-Cooper/Drawbot_image_to_gcode_v2) -创建可在绘图机器人上使用的G代码.
- [blackstripes](https://github.com/fullscreennl/blackstripes-python-extensions) -将PNG图像转换为SVG线图.
- [Ribbon](https://github.com/fogleman/ribbon) -用Go语言编写的蛋白质带状图.
- [penplot](https://github.com/mattdesl/penplot) -JavaScript中绘图仪艺术的开发环境.
- [penkit](https://github.com/paulgb/penkit) -用于创建基于行的SVG图形的Python库.
- [generativeExamples](https://github.com/digitalcoleman/generativeExamples) -生成可打印PDF的示例处理代码.
- [Let's make map](https://svg-exporter.netlify.com) -基于网络的工具，可从Mapzen磁贴中导出SVG地图.
- [SuperformulaSVG for web](https://jasonwebb.github.io/SuperformulaSVG-for-web) -生成线条艺术的网络应用.
- [scribbleplot](https://github.com/bleeptrack/scribbleplot) -处理中的图像image草变换.
- [Maker.js](https://maker.js.org) -用于为CNC和激光切割机创建2D矢量绘图的库.
- [Turtletoy](https://turtletoy.net) -具有SVG导出功能的基于浏览器的JavaScript turtle图形API.
- [cozyvec](https://github.com/brubsby/cozyvec) -Web / Standalone终端环境，用于绘图员艺术作品和推文图.
- [makio135/plotter](https://observablehq.com/collection/@makio135/plotter) -一个 [Observable](https://observablehq.com/) 笔记本收集器中充满了针对绘图仪的工作.

### Vector Utilities

用于操纵和优化基于矢量的文件格式的工具.

- [svgsort](https://github.com/inconvergent/svgsort) -用于绘制SVG文件的路径规划，减少了用笔向上移动所花费的时间.
- [svgo](https://github.com/svg/svgo) -基于Node.js的工具，用于优化SVG文件.
- [Polargraph Optimizer](https://github.com/ezheidtmann/polargraph-optimizer) -优化极谱图的绘制计划.
- [penkit-optimize](https://github.com/paulgb/penkit/tree/master/optimizer) -使用车辆路径求解器的SVG优化器，以最大程度地缩短绘图时间.
- [svg-crowbar](https://github.com/NYTimes/svg-crowbar) -仅限Chromebook的书签，用于从HTML文档中提取SVG.
- [vpype](https://github.com/abey79/vpype) -基于绘图仪的基于Python的CLI实用程序，用于生成和处理SVG，包括缩放和优化路径.

### Fonts

单行矢量字体或“雕刻字体”.

- [Summary of single line fonts](http://imajeenyus.com/computer/20150110_single_line_fonts/index.shtml) -良好的信息以及其他资源和字体的链接.
- [Hershey Vector Font](http://paulbourke.net/dataformats/hershey)  -60年代矢量字体的`.fnt`格式. 很好地概述了字体的原始数据格式.
- [hershey-fonts](https://github.com/kamalmostafa/hershey-fonts) -C库和好时字体的原始字体数据.
- [OneLineFonts.com](https://www.onelinefonts.com) -具有一些单行字体的商业站点可供购买.
- [svg-fonts](https://gitlab.com/oskay/svg-fonts) -SVG格式的单行字体，主要用于 [Hershey Text](https://gitlab.com/oskay/hershey-text) Inkscape插件.

## Inspiration and Instruction

博客文章，文章，教程，画廊，视频等.

- [An Intro to Pen Plotters](https://medium.com/quarterstudio/an-intro-to-pen-plotters-29b6bd4327ba) -有关旧HPGL绘图仪入门的良好信息.
- [1980s pen plotters of the future](https://notes.variogr.am/2012/08/12/1980s-pen-plotters-of-the-future) -老式笔式绘图仪的另一个介绍.
- [Pen Plotter Programming: The Basics](https://medium.com/@fogleman/pen-plotter-programming-the-basics-ec0407ab5929) -编程矢量路径的一些基础知识，包括排序，联接和简化.
- [On Generative Algorithms](https://inconvergent.net/generative) -有趣的算法的漂亮的13部分演练.
- [Roland DG DXY-990](https://hackaday.io/project/12276-roland-dg-dxy-990) -罗兰平板绘图仪的快速入门指南.
- [The Cohen-Sutherland Line Clipping Algorithm](https://sighack.com/post/cohen-sutherland-line-clipping-algorithm) -有趣算法的详细说明和示例.
- [Vera Molnár](https://www.surfacemag.com/articles/vera-molnar-in-thinking-machines-at-moma) -绘图员艺术家.
- [Hektor](http://juerglehni.com/works/hektor) -2002年的原始基于电缆的牵引机器人.
- [Pen Plotter Art & Algorithms](https://mattdesl.svbtle.com/pen-plotter-1) -分为两部分的介绍，介绍了如何生成绘图图形.
- [Surface Projection](https://bitaesthetics.com/posts/surface-projection.html) -使用Python和penplot深入研究表面投影和隐藏线去除.
- [Fractal Generation with L-Systems](https://bitaesthetics.com/posts/fractal-generation-with-l-systems.html) -用于创建基于线的分形图形的技术.
- [Pen Plotter Art & Algorithms](https://mattdesl.svbtle.com/pen-plotter-1) -绘图仪简介，AxiDraw，`penplot`库的演练.
- [Introduction to TSP art](https://wiki.evilmadscientist.com/TSP_art) -用于旅行业务员问题（单路径）艺术的资源.
- [Hidden wireframe removal](https://trmm.net/Hidden_Wireframe) - Discussion and links to code for wireframe removal of STL files.
- [How to Draw Generative Art with an Axidraw Pen Plotter](https://www.dirtalleydesign.com/blogs/news/how-to-draw-prints-with-an-axidraw-pen-plotter) -很多不错的技巧，并非都是Axidraw特有的，还有一些笔评论和方便的3D打印工具.
- [The Best XY Plotters in 2020](https://all3dp.com/2/pen-plotters-best-xy-plotters/) -很好地概述了AxiDraw及其克隆，以及一些DIY选项.

## Community

在哪里可以找到其他绘图仪和绘图机器人的朋友.

- [#plottertwitter](https://twitter.com/hashtag/plottertwitter) -有很多情节的Twitter主题标签.
- [PlotterArt Subreddit](https://www.reddit.com/r/PlotterArt)
- [AxiDraw Subreddit](https://www.reddit.com/r/axidraw)
- [Generative Art Subreddit](https://www.reddit.com/r/generative)
- [Plotter People](https://plotterpeople.github.io/) -举行个人见面会（到目前为止，SF和NYC），进行讲座和绘图员艺术画廊.

## Plotter Art For Sale

- [Paul Rickards](https://shop.paulrickards.com)
- [Michael Fogleman](https://www.michaelfogleman.com/plotter)
- [inconvergent](http://buy.inconvergent.net)
- [Customized Streetart](https://www.literalstreetart.com) -具有可选笔式绘图仪输出的可自定义地图.
- [Monica Rizzolli](https://www.saatchiart.com/account/artworks/155196)
- [EmergentDesign](https://emergentdesign.bigcartel.com/products)
- [BustBright](https://mkt.com/bustbright)
- [Martin O'Leary](https://shop.mewo2.com)
- [Geoffrey Bradway](https://www.chromatocosmos.com/)
- [Yuin Chien](http://store.yuinchien.com/)
- [Andrew Heumann](https://shop.andrewheumann.com/)
- [brubsby](http://shop.brubsby.com/)
- [Arjan van der Meij](https://dutchplottr.nl/en/)
- [Nadieh Bremer](https://shop.visualcinnamon.com/collections/pen-plotter-prints)
- [Michelle Chandra](https://www.dirtalleydesign.com/)
- [Jessica In](https://www.jessicain.net/shop-originals)
- [Pedro Alcocer](https://store.pedroalcocer.com/)
- [AndyMakes](https://shop.andymakes.com/)
- [Marcel Schwittlick](https://schwittlick.bigcartel.com/)


## Other Awesomes

- [awesome-generative-art](https://github.com/kosmos/awesome-generative-art)
- [awesome-creative-coding](https://github.com/terkelg/awesome-creative-coding)

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Brian Boucheron](https://boucheron.org/brian) 放弃了此作品的所有版权以及相关或邻近的权利.
