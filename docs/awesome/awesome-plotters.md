<div class="github-widget" data-repo="beardicus/awesome-plotters"></div>
## Awesome Plotters [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

为计算机控制的绘图机和其他视觉艺术机器人提供的精选代码和资源列表.



## Hardware

### Plotters

- [AxiDraw](https://shop.evilmadscientist.com/productsmenu/846) - 笔式绘图仪 [Evil Mad Scientist](https://www.evilmadscientist.com)，非常受欢迎 [#plottertwitter](https://twitter.com/hashtag/plottertwitter).
- [Line-us](https://www.line-us.com) - 一个可爱的小kickstarted机器人绘图臂.
- [Makeblock XY Plotter](http://learn.makeblock.com/en/xy-plotter-robot-kit) -  Hackable XY绘图仪套件（已停产？）.
- [Drawing Robot](https://www.thingiverse.com/thing:2349232) -  3d-Printable AxiDraw克隆w / [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) 控制器运行grbl固件.
- [WaterColorBot](https://watercolorbot.com) -  XY艺术机器人和用水彩颜料绘图的软件.
- [EggBot](https://egg-bot.com) - 用于蛋形和球形物体的笔式绘图仪.
- [HP Pen Plotters](https://www.hpmuseum.net/exhibit.php?class=4&cat=24)   - 来自HPGL标准创建者的老式桌面和落地式笔式绘图仪.  型号7475A很常见，通常可以在eBay上找到.
- [Roland Pen Plotters](https://www.youtube.com/watch?v=6_pwzqPk6Gg)   - 复古平板HPGL笔式绘图仪.  在eBay上搜索“roland dxy”.
- [Polargraph](http://www.polargraph.co.uk) - 最初的polargraph硬件和软件项目.
- [Makelangelo](http://www.makelangelo.com) - 开源polargraph artbot.

### Motor Controllers

- [grblShield](https://github.com/synthetos/grblShield) - 转动所需的所有步进电机控制硬件 [Arduino](https://www.arduino.cc)  使用grbl固件进入基于G代码的运动控制器.  （[adafruit](https://www.adafruit.com/product/1750))
- [TinyG](https://github.com/synthetos/TinyG)   - 更加功能强大的6轴G代码运动控制硬件.  （[adafruit](https://www.adafruit.com/product/1749))
- [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) - 适用于Arduino的Grbl兼容步进电机控制屏蔽，类似于 [grblShield](https://github.com/synthetos/grblShield).
- [Raspberry Pi CNC Hat](https://wiki.protoneer.co.nz/Raspberry_Pi_CNC)   - 带步进控制器的Raspberry Pi附加板和运行grbl的微控制器.  与Pi的串行引脚接口.

### Accessories

- [WiFi232](http://biosrhythm.com/?page_id=1453)   - 通过DB25插头连接RS-232串口.  无线控制您的串行绘图仪.
- [Plotter Cable Pinout](http://sites.music.columbia.edu/cmc/chiplotle/plotter_cable.pdf)   - 适用于大多数HP和Roland绘图仪的绘图仪电缆示意图.  搜索易趣或亚马逊的“DB9到DB25串行空调制解调器电缆”或类似信息，找到它们出售.

### Pens

- [Sharpie Fine Point Plotter Adapter](https://www.thingiverse.com/thing:229982) -  3D打印适配器，适合HP-GL绘图仪中的标准Sharpie.
- [Parametric 3d-Printable Plotter Pen Adapter](https://openjscad.org/#https://gist.githubusercontent.com/beardicus/d668c0f6b96be53d16dc/raw/plotter-pen-adapter.jscad) - 可调模型，用于打印各种笔的适配器.
- [Plotter Pen STL Models](https://www.thingiverse.com/thing:227985) - 短标准和长标准绘图笔的精确STL模型.
- [Pens for AxiDraw](https://wiki.evilmadscientist.com/Pens_for_AxiDraw) - 适合一般绘图仪滥用的笔列表.
- [Pens for EggBot](https://wiki.evilmadscientist.com/Pen_choices) - 以蛋和玻璃为重点的笔建议，但仍然是普遍适用的信息.

## Software

### HPGL

HPGL是一种基于串行/文本的协议，大多数旧笔绘图仪使用，甚至许多新的乙烯切割机.

- [Chiplotle](https://github.com/drepetto/chiplotle) - 用于生成HPGL并与串行绘图仪连接的Python库.
- [HPGL Reference Guide](https://www.isoplotec.co.jp/HPGL/eHPGL.htm) - 基于HTML的HPGL参考.
- [HP 7475A Interfacing and Programming Manual](https://archive.org/details/HP7475AInterfacingandProgrammingManual) - 包含完整HPGL参考的扫描PDF手册.
- [djipco/hpgl](https://github.com/djipco/hpgl) - 与HPGL兼容的绘图仪和打印机进行通信的Node.js库.
- [hp2xx](https://www.gnu.org/software/hp2xx)   - 将HPGL转换为其他矢量和栅格格式的GNU工具.  也可以在X11中用作预览.
- [vec](https://github.com/anachrocomputer/vec) - 用于生成HPGL的示例C代码，带有龟图形界面.
- [d3-hpgl](https://github.com/aubergene/d3-hpgl) -  HTML Canvas API的适配器，因此您可以使用流行的输出HPGL [D3](https://d3js.org) 图书馆.
- [HPGL Viewer](https://github.com/drskullster/HPGLViewer) - 使用JavaScript和HTML5画布的HPGL Viewer.
- [HPGL Sender](https://github.com/LgHS/hpgl-sender) - 用于预览HPGL并将其发送到绘图仪的Web界面.

### G-code

 G代码是用于控制CNC机床的基于文本的标准.  虽然它是专为工业机器设计的，但它在许多业余爱好者的3D打印机固件中的使用已经使它在小型DIY项目中无处不在.

- [grbl](https://github.com/grbl/grbl) - 用于Atmega 328微控制器和Arduino的高性能G代码解释固件.
- [cncjs](https://github.com/cncjs/cncjs) - 基于Web的界面，用于控制运行grbl，TinyG或其他基于G代码的固件的CNC机器.
- [node-gcode](https://github.com/ryansturmer/node-gcode) - 基于Node.js的G代码解释器和模拟器.
- [svg2gcode](https://github.com/em/svg2gcode) - 基于Node.js的命令行实用程序，用于将SVG转换为G代码.
- [svg2gcode](https://github.com/vishpat/svg2gcode) - 基于Python的实用程序，用于快速SVG到G代码的转换.
- [jscut](http://jscut.org/) - 基于Web的实用程序，用于将SVG转换为G代码.
- [Universal-G-Code-Sender](https://github.com/winder/Universal-G-Code-Sender) - 基于Java的grbl兼容的跨平台G代码发送方.
- [ChiliPeppr Hardware Fiddle](http://chilipeppr.com) - 基于Web的模块化工作空间，可视化G代码和控制硬件.

### Plotter-Specific

特定于特定绘图仪或控制器的软件.

- [axidraw](https://github.com/evil-mad/axidraw) -  Inkscape的官方AxiDraw扩展.
- [axi](https://github.com/fogleman/axi) -  AxiDraw v3的非官方Python库.
- [xy](https://github.com/fogleman/xy) -  Makeblock XY绘图仪机器人套件的​​实用程序.
- [LaserGRBL](https://github.com/arkypita/LaserGRBL)   - 用于grbl控制器的激光优化Windows GUI.  可以重新用于DIY笔式绘图仪，使用螺线管进行笔上/下移动.
- [Line-us Inkscape Plugin](https://github.com/Line-us/Inkscape-Plugin) - 发送图纸到 [Line-us plotter](https://www.line-us.com) 直接来自Inkscape.
- [Line-us API Examples](https://github.com/Line-us/Line-us-Programming) - 示例代码 [Line-us](https://www.line-us.com) 绘图仪的基于G代码的API.
- [@beardicus/line-us](https://github.com/beardicus/line-us) - 用于控制的JavaScript库 [Line-us](https://www.line-us.com) 来自Node或浏览器的机器.
- [PenPlotter](https://github.com/RickMcConney/PenPlotter) - 使用重复固件的Polargraph控制器.
- [Makelangelo-firmware](https://github.com/MarginallyClever/Makelangelo-firmware) -  Makelangelo极谱图机器人的固件.
- [RoboPaint](https://github.com/evil-mad/robopaint) -  WaterColorBot软件.
- [AxiTurtle](https://github.com/ralphcrutzen/AxiTurtle) - 处理中AxiDraw的Turtle图形.
- [GRBL-Plotter](https://github.com/svenhb/GRBL-Plotter) - 绘图仪优化的Windows GUI，用于带有SVG和DXF导入的grbl控制器，以及灵活的笔上/下控制.
- [saxi](https://github.com/nornagon/saxi)   -  AxiDraw的驱动程序和库.  使用恒定加速度运动规划并自动调整大小到纸张.
- [MP2300-Tools](https://github.com/Jan--Henrik/MP2300-Tools) - 用于将HPGL转换为Graphtec的GPGL格式的软件，以及用于Graphtec绘图仪笔适配器的CAD文件.


### Vector Creation

从头开始或通过其他格式转换创建矢量图稿的工具.

- [Inkscape](https://inkscape.org) - 流行的跨平台开源矢量图形编辑器.
- [p5.js](https://p5js.org) - “JavaScript库，使编码器可供艺术家，设计师，教育工作者和初学者使用”.
- [Paper.js](http://paperjs.org) - “瑞士军刀矢量图形脚本”.
- [ln](https://github.com/fogleman/ln) - 用Go编写的基于矢量的3D渲染器.
- [autotrace](https://github.com/autotrace/autotrace) - 将位图图像转换为矢量图形.
- [stipplegen](https://github.com/evil-mad/stipplegen)   - 从位图图像创建有趣的点画图纸.  （[blog post](https://www.evilmadscientist.com/2012/stipplegen2))
- [SquiggleDraw](https://github.com/gwygonik/SquiggleDraw/commits/master) - “SquiggleDraw将根据图像创建一个SVG文件，使用亮度来改变正弦波的幅度”.
- [svgurt](https://svgurt.com) - 基于Web的PNG到SVG创意noodler.
- [maptrace](https://github.com/mzucker/maptrace) - 通过跟踪光栅图像生成防水多边形矢量地图.
- [Drawbot_image_to_gcode_v2](https://github.com/Scott-Cooper/Drawbot_image_to_gcode_v2) - 创建用于drawbot的G代码.
- [blackstripes](https://github.com/fullscreennl/blackstripes-python-extensions) - 将PNG图像转换为SVG线条图.
- [Ribbon](https://github.com/fogleman/ribbon) - 用Go编写的蛋白质带状图.
- [penplot](https://github.com/mattdesl/penplot) -  JavaScript中绘图仪艺术的开发环境.
- [penkit](https://github.com/paulgb/penkit) - 用于创建基于行的SVG图形的Python库.
- [generativeExamples](https://github.com/digitalcoleman/generativeExamples) - 示例生成可绘制PDF的处理代码.
- [Let's make map](https://svg-exporter.netlify.com) - 基于Web的工具，用于从Mapzen切片导出SVG贴图.
- [SuperformulaSVG for web](https://jasonwebb.github.io/SuperformulaSVG-for-web) - 一个生成线艺术网络应用程序.
- [scribbleplot](https://github.com/bleeptrack/scribbleplot) - 处理中的乱写图像转换.
- [Maker.js](https://maker.js.org) - 用于为CNC和激光切割机创建2D矢量图的库.
- [Turtletoy](https://turtletoy.net) - 具有SVG导出的基于浏览器的JavaScript turtle图形API.

### Vector Utilities

用于操作和优化基于矢量的文件格式的工具.

- [svgsort](https://github.com/inconvergent/svgsort) - 用于绘制SVG文件的路径规划，减少了用笔移动所花费的时间.
- [svgo](https://github.com/svg/svgo) - 基于Node.js的工具，用于优化SVG文件.
- [Polargraph Optimizer](https://github.com/ezheidtmann/polargraph-optimizer) - 优化极图的绘图计划.
- [penkit-optimize](https://github.com/paulgb/penkit/tree/master/optimizer) -  SVG优化器，它使用车辆路径求解器来最小化绘图时间.
- [svg-crowbar](https://github.com/NYTimes/svg-crowbar) - 仅限Chrome的书签，用于从HTML文档中提取SVG.

### Fonts

单行矢量字体或“雕刻字体”.

- [Summary of single line fonts](http://imajeenyus.com/computer/20150110_single_line_fonts/index.shtml) - 良好的信息和其他资源和字体的链接.
- [Hershey Vector Font](http://paulbourke.net/dataformats/hershey)   - 来自60年代的矢量字体的`.fnt`格式.  包括字体原始数据格式的良好概述.
- [hershey-fonts](https://github.com/kamalmostafa/hershey-fonts) - C library and original font data for the Hershey fonts.
- [OneLineFonts.com](https://www.onelinefonts.com) - 可以购买一些单行字体的商业网站.

## Inspiration and Instruction

博客文章，文章，教程，画廊，视频等等.

- [An Intro to Pen Plotters](https://www.tobiastoft.com/posts/an-intro-to-pen-plotters) - 有关使用旧HPGL绘图仪的详细信息.
- [1980s pen plotters of the future](https://notes.variogr.am/2012/08/12/1980s-pen-plotters-of-the-future) - 老式笔式绘图仪的另一个介绍.
- [Pen Plotter Programming: The Basics](https://medium.com/@fogleman/pen-plotter-programming-the-basics-ec0407ab5929) - 编程矢量路径的一些基础知识，包括排序，连接和简化.
- [On Generative Algorithms](https://inconvergent.net/generative) - 有趣算法的13个部分演练.
- [Roland DG DXY-990](https://hackaday.io/project/12276-roland-dg-dxy-990) - 罗兰平板绘图仪的快速入门指南.
- [The Cohen-Sutherland Line Clipping Algorithm](https://sighack.com/post/cohen-sutherland-line-clipping-algorithm) - 有趣算法的详细解释和示例.
- [Vera Molnár](https://www.surfacemag.com/articles/vera-molnar-in-thinking-machines-at-moma) - 和绘图艺术家.
- [The Recode Project](http://recodeproject.com) - “ReCode项目是一项社区驱动的努力，通过将计算机艺术翻译成现代编程语言来保护计算机艺术”.
- [Hektor](http://juerglehni.com/works/hektor) -  2002年的原始电缆拉丝机.
- [Pen Plotter Art & Algorithms](https://mattdesl.svbtle.com/pen-plotter-1) - 为绘图创建生成图形的两部分介绍.
- [Surface Projection](https://bitaesthetics.com/posts/surface-projection.html) - 一些用于创建适合绘图的线条图形的投影技术.
- [Fractal Generation with L-Systems](https://bitaesthetics.com/posts/fractal-generation-with-l-systems.html) - 用于创建基于线的分形图形的技术.
- [Pen Plotter Art & Algorithms](https://mattdesl.svbtle.com/pen-plotter-1) - 绘图仪简介，AxiDraw，`penplot`库的演练.
- [Surface Projection](https://bitaesthetics.com/posts/surface-projection.html) - 使用Python和penplot深入挖掘表面投影和隐藏线.
- [Introduction to TSP art](https://wiki.evilmadscientist.com/TSP_art) - 旅行商问题（单一路径）艺术的资源.
- [Hidden wireframe removal](https://trmm.net/Hidden_Wireframe) - 讨论和链接到线框删除STL文件的代码.

## Community

在哪里可以找到其他绘图仪和drawbot的朋友.

- [#plottertwitter](https://twitter.com/hashtag/plottertwitter) - 带有大量情节的Twitter主题标签.
- [PlotterArt Subreddit](https://www.reddit.com/r/PlotterArt)
- [AxiDraw Subreddit](https://www.reddit.com/r/axidraw)
- [Generative Art Subreddit](https://www.reddit.com/r/generative)
- [Chiplotle-discuss](https://lists.columbia.edu/mailman/listinfo/chiplotle-discuss) -  Chiplotle HPGL Python库的相当不活跃的邮件列表，带有一些普通的绘图仪说话.

## Plotter Art For Sale

- [Paul Rickards](http://biosrhythm.com/?page_id=1569)
- [Michael Fogleman](https://www.michaelfogleman.com/plotter)
- [inconvergent](http://buy.inconvergent.net)
- [Customized Streetart](https://www.literalstreetart.com) - 可选择的笔式绘图仪输出的可自定义地图.
- [Monica Rizzolli](https://www.saatchiart.com/account/artworks/155196)
- [EmergentDesign](https://emergentdesign.bigcartel.com/products)
- [BustBright](https://mkt.com/bustbright)
- [Martin O'Leary](https://shop.mewo2.com)

## Other Awesomes

- [awesome-generative-art](https://github.com/kosmos/awesome-generative-art)
- [awesome-creative-coding](https://github.com/terkelg/awesome-creative-coding)

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Brian Boucheron](https://boucheron.org/brian) 已放弃对此作品的所有版权及相关或相邻权利.
