<div class="github-widget" data-repo="beardicus/awesome-plotters"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Plotters [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

计算机控制绘图机和其他视觉艺术机器人的代码和资源的精选列表.



## Hardware

### Plotters

- [AxiDraw](https://shop.evilmadscientist.com/productsmenu/846) - 笔式绘图仪来自 [Evil Mad Scientist](https://www.evilmadscientist.com)，很受欢迎 [#plottertwitter](https://twitter.com/hashtag/plottertwitter).
- [Line-us](https://www.line-us.com) - 一个可爱的小机器人绘图臂.
- [Makeblock XY Plotter](http://learn.makeblock.com/en/xy-plotter-robot-kit) - 可破解的 XY 绘图仪套件（已停产？）.
- [Drawing Robot](https://www.thingiverse.com/thing:2349232) - 带 3D 打印的 AxiDraw 克隆 [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) 控制器运行 grbl 固件.
- [4xiDraw](https://www.instructables.com/id/4xiDraw/) - 另一个可 3D 打印的 AxiDraw 克隆带 [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) 控制器运行 grbl 固件.
- [WaterColorBot](https://watercolorbot.com) - XY 艺术机器人和软件，用于绘制水彩颜料.
- [EggBot](https://egg-bot.com) - Pen plotter for egg-shaped and spherical objects.
- [HP Pen Plotters](https://www.hpmuseum.net/exhibit.php?class=4&cat=24)  - 来自 HPGL 标准创建者的老式台式和落地式笔式绘图仪.  7475A 型非常常见，通常可以在 eBay 上找到.
- [Roland Pen Plotters](https://www.youtube.com/watch?v=6_pwzqPk6Gg)  - 老式平板 HPGL 笔式绘图仪. 在 eBay 上搜索“roland dxy”.
- [Polargraph](http://www.polargraph.co.uk) - 原始极谱硬件和软件项目.
- [Makelangelo](http://www.makelangelo.com) - 开源极坐标图艺术机器人.
- [BrachioGraph](https://brachiograph.readthedocs.io/en/latest/) - 由木棒、伺服系统和运行 Python 的 Raspberry Pi 制成的廉价而简单的绘图仪.
- [Arduino CNC Drawing Machine](https://www.diymachines.co.uk/arduino-cnc-drawing-machine) - 一个相当简单的 3D 打印 AxiDraw 风格的绘图仪，具有良好的视频文档.

### Motor Controllers

- [grblShield](https://github.com/synthetos/grblShield) - 转动一个所需的所有步进电机控制硬件 [Arduino](https://www.arduino.cc) 使用 grbl 固件转换为基于 G 代码的运动控制器.  ([adafruit](https://www.adafruit.com/product/1750))
- [TinyG](https://github.com/synthetos/TinyG)  - 功能更强大、功能更强大的基于 G 代码的 6 轴运动控制硬件.  ([adafruit](https://www.adafruit.com/product/1749))
- [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) - 适用于 Arduino 的 Grbl 兼容步进电机控制屏蔽，类似于 [grblShield](https://github.com/synthetos/grblShield).
- [Raspberry Pi CNC Hat](https://wiki.protoneer.co.nz/Raspberry_Pi_CNC)  - 带有步进控制器和运行 grbl 的微控制器的 Raspberry Pi 附加板. 与 Pi 的串行引脚接口.

### Accessories

- [WiFi232](http://biosrhythm.com/?page_id=1453)  - 通过 DB25 插头 Wifi 到 RS-232 串行. 以无线方式控制您的串行绘图仪.
- [Plotter Cable Pinout](http://sites.music.columbia.edu/cmc/chiplotle/plotter_cable.pdf)  - 适用于大多数 HP 和 Roland 绘图仪的绘图仪电缆示意图. 在 eBay 或 Amazon 上搜索“DB9 到 DB25 串行空调制解调器电缆”或类似产品，以找到出售的产品.

### Pens

- [Sharpie Fine Point Plotter Adapter](https://www.thingiverse.com/thing:229982) - 适合 HP-GL 绘图仪中的标准 Sharpie 的 3D 打印适配器.
- [Parametric 3d-Printable Plotter Pen Adapter](https://openjscad.org/#https://gist.githubusercontent.com/beardicus/d668c0f6b96be53d16dc/raw/plotter-pen-adapter.jscad) - 可调节型号以打印各种笔的适配器.
- [Plotter Pen STL Models](https://www.thingiverse.com/thing:227985) - 短和长标准绘图笔的准确 STL 模型.
- [Pens for AxiDraw](https://wiki.evilmadscientist.com/Pens_for_AxiDraw) - 适合一般绘图仪滥用的笔列表.
- [Pens for EggBot](https://wiki.evilmadscientist.com/Pen_choices) - 以鸡蛋和玻璃为重点的笔建议，但仍然普遍适用的信息.
- [JetPens – The Best White Ink Pens](https://www.jetpens.com/blog/the-best-white-ink-pens/pt/340) - 对许多白色墨水笔的全面回顾，并附有其覆盖特性的图片.

## Software

### HPGL

HPGL 是一种基于串行/文本的协议，被大多数旧的笔式绘图仪甚至许多新的乙烯基切割机使用.

- [Chiplotle](https://github.com/drepetto/chiplotle) - 用于生成 HPGL 并与串行绘图仪接口的 Python 库.
- [Chiplotle on Parallel Port](https://gitlab.com/mononym/chiplotle-on-parallel-port) - 调整 Chiplotle 以使用并行端口连接.
- [HPGL Reference Guide](https://www.isoplotec.co.jp/HPGL/eHPGL.htm) - 基于 HTML 的 HPGL 参考.
- [HP 7475A Interfacing and Programming Manual](https://archive.org/details/HP7475AInterfacingandProgrammingManual) - 包含完整 HPGL 参考的 PDF 扫描手册.
- [djipco/hpgl](https://github.com/djipco/hpgl) - 与 HPGL 兼容的绘图仪和打印机通信的 Node.js 库.
- [hp2xx](https://www.gnu.org/software/hp2xx)  - 将 HPGL 转换为其他矢量和光栅格式的 GNU 工具. 也可用作 X11 中的预览.
- [vec](https://github.com/anachrocomputer/vec) - 使用海龟图形界面生成 HPGL 的示例 C 代码.
- [d3-hpgl](https://github.com/aubergene/d3-hpgl) - 用于 HTML Canvas API 的适配器，因此您可以使用流行的输出 HPGL [D3](https://d3js.org) 图书馆.
- [HPGL Viewer](https://github.com/drskullster/HPGLViewer) - 使用 JavaScript 和 HTML5 画布的 HPGL 查看器.
- [HPGL Sender](https://github.com/LgHS/hpgl-sender) - 用于预览 HPGL 并将其发送到绘图仪的 Web 界面.
- [HPGLGraphics](https://github.com/ciaron/HPGLGraphics) - 用于编写 HPGL 文件的处理库.

### G-code

 G 代码是用于控制 CNC 机器的基于文本的标准. 虽然它是为工业机器设计的，但它在许多业余爱好者 3d 打印机固件中的使用使它在小型 DIY 项目中也无处不在.

- [grbl](https://github.com/grbl/grbl) - 用于 Atmega 328 微控制器和 Arduino 的高性能 G 代码解释固件.
- [cncjs](https://github.com/cncjs/cncjs) - 基于 Web 的界面控制运行 grbl、TinyG 或其他基于 G 代码的固件的 CNC 机器.
- [node-gcode](https://github.com/ryansturmer/node-gcode) - 基于 Node.js 的 G 代码解释器和模拟器.
- [svg2gcode](https://github.com/em/svg2gcode) - 基于 Node.js 的命令行实用程序，用于将 SVG 转换为 G 代码.
- [svg2gcode](https://github.com/vishpat/svg2gcode) - 基于 Python 的实用程序，用于快速 SVG 到 G 代码的转换.
- [jscut](http://jscut.org/) - 用于将 SVG 转换为 G 代码的基于 Web 的实用程序.
- [Universal-G-Code-Sender](https://github.com/winder/Universal-G-Code-Sender) - 基于 Java 的 grbl 兼容的跨平台 G 代码发送器.
- [ChiliPeppr Hardware Fiddle](http://chilipeppr.com) - 基于 Web 的模块化工作区，用于可视化 G 代码和控制硬件.
- [gcode-generative-for-processing](https://github.com/o0morgan0o/gcode-generative-for-processing)  - 处理库，旨在从简单的形状创建 gcode.  （专为与 Creality CR10 一起使用而设计）

### Plotter-Specific

特定于特定绘图仪或控制器的软件.

- [axidraw](https://github.com/evil-mad/axidraw) - Inkscape 的官方 AxiDraw 扩展.
- [axi](https://github.com/fogleman/axi) - AxiDraw v3 的非官方 Python 库.
- [xy](https://github.com/fogleman/xy) - Makeblock XY 绘图仪机器人套件的​​实用程序.
- [LaserGRBL](https://github.com/arkypita/LaserGRBL)  - 用于 grbl 控制器的激光优化 Windows GUI. 可以重新用于 DIY 笔式绘图仪，使用螺线管进行笔上/下移动.
- [Line-us Inkscape Plugin](https://github.com/Line-us/Inkscape-Plugin) - 将图纸发送到 [Line-us plotter](https://www.line-us.com) 直接来自 Inkscape.
- [Line-us API Examples](https://github.com/Line-us/Line-us-Programming) - 示例代码 [Line-us](https://www.line-us.com) 绘图仪的基于 G 代码的 API.
- [@beardicus/line-us](https://github.com/beardicus/line-us) - 用于控制的 JavaScript 库 [Line-us](https://www.line-us.com) 来自 Node 或浏览器的机器.
- [PenPlotter](https://github.com/RickMcConney/PenPlotter) - 使用重复固件的 Polargraph 控制器.
- [Makelangelo-firmware](https://github.com/MarginallyClever/Makelangelo-firmware) - Makelangelo polargraph 机器人的固件.
- [RoboPaint](https://github.com/evil-mad/robopaint) - WaterColorBot 软件.
- [AxiTurtle](https://github.com/ralphcrutzen/AxiTurtle) - 处理中 AxiDraw 的海龟图形.
- [GRBL-Plotter](https://github.com/svenhb/GRBL-Plotter) - 绘图仪优化的 Windows GUI，用于带有 SVG 和 DXF 导入的 grbl 控制器，以及灵活的上/下笔控制.
- [saxi](https://github.com/nornagon/saxi)  - AxiDraw 的驱动程序和库. 使用恒定加速度运动规划并自动调整纸张大小.
- [MP2300-Tools](https://github.com/Jan--Henrik/MP2300-Tools) - 用于将 HPGL 转换为 Graphtec 的 GPGL 格式的软件，以及用于 Graphtec 绘图笔适配器的 CAD 文件.

### Vector Creation

从头开始或通过从其他格式转换来创建矢量图的工具.

- [Inkscape](https://inkscape.org) - 流行的跨平台开源矢量图形编辑器.
- [p5.js](https://p5js.org) - “JavaScript 库，使艺术家、设计师、教育工作者和初学者都可以进行编码”.
- [Paper.js](http://paperjs.org) - “矢量图形脚本的瑞士军刀”.
- [ln](https://github.com/fogleman/ln) - 用 Go 编写的基于矢量的 3D 渲染器.
- [autotrace](https://github.com/autotrace/autotrace) - 将位图图像转换为矢量图形.
- [stipplegen](https://github.com/evil-mad/stipplegen)  - 从位图图像创建有趣的点画图.  ([blog post](https://www.evilmadscientist.com/2012/stipplegen2))
- [SquiggleDraw](https://github.com/gwygonik/SquiggleDraw/commits/master) - “SquiggleDraw 将从图像创建一个 SVG 文件，使用亮度来改变正弦波的幅度”.
- [svgurt](https://svgurt.com) - 基于 Web 的 PNG 到 SVG 创意面条.
- [maptrace](https://github.com/mzucker/maptrace) - 通过跟踪光栅图像生成防水多边形矢量地图.
- [Drawbot_image_to_gcode_v2](https://github.com/Scott-Cooper/Drawbot_image_to_gcode_v2) - 创建用于绘图机器人的 G 代码.
- [blackstripes](https://github.com/fullscreennl/blackstripes-python-extensions) - 将 PNG 图像转换为 SVG 线条图.
- [Ribbon](https://github.com/fogleman/ribbon) - 用 Go 编写的蛋白质丝带图.
- [penplot](https://github.com/mattdesl/penplot) - JavaScript 绘图仪艺术的开发环境.
- [penkit](https://github.com/paulgb/penkit) - 用于创建基于行的 SVG 图形的 Python 库.
- [generativeExamples](https://github.com/digitalcoleman/generativeExamples) - 生成可打印 PDF 的示例处理代码.
- [Let's make map](https://svg-exporter.netlify.com) - 基于 Web 的工具，用于从 Mapzen 图块导出 SVG 地图.
- [SuperformulaSVG for web](https://jasonwebb.github.io/SuperformulaSVG-for-web) - 生成式线条艺术网络应用程序.
- [scribbleplot](https://github.com/bleeptrack/scribbleplot) - 处理中的涂鸦图像转换.
- [Maker.js](https://maker.js.org) - 用于为 CNC 和激光切割机创建 2D 矢量绘图的库.
- [Turtletoy](https://turtletoy.net) - 基于浏览器的 JavaScript 海龟图形 API，带有 SVG 导出.
- [cozyvec](https://github.com/brubsby/cozyvec) - 绘图仪艺术和推文图的 Web/独立终端环境.
- [makio135/plotter](https://observablehq.com/collection/@makio135/plotter) - 一个 [Observable](https://observablehq.com/) 笔记本系列充满了面向绘图员的工作.
- [PlotterFun](https://mitxela.com/plotterfun/) - 基于浏览器的图像到 SVG 转换器，类似于 SquiggleDraw.

### Vector Utilities

操作和优化基于矢量的文件格式的工具.

- [svgsort](https://github.com/inconvergent/svgsort) - 用于绘制 SVG 文件的路径规划，减少了用笔移动所花费的时间.
- [svgo](https://github.com/svg/svgo) - 用于优化 SVG 文件的基于 Node.js 的工具.
- [Polargraph Optimizer](https://github.com/ezheidtmann/polargraph-optimizer) - 优化极坐标图的绘制计划.
- [penkit-optimize](https://github.com/paulgb/penkit/tree/master/optimizer) - 一个 SVG 优化器，它使用车辆路径求解器来最小化绘图时间.
- [svg-crowbar](https://github.com/NYTimes/svg-crowbar) - 仅用于从 HTML 文档中提取 SVG 的 Chrome 书签.
- [vpype](https://github.com/abey79/vpype) - 以绘图仪为中心的基于 Python 的 CLI 实用程序，用于生成和操作 SVG，包括缩放和优化路径.

### Fonts

单行矢量字体或“雕刻字体”.

- [Summary of single line fonts](http://imajeenyus.com/computer/20150110_single_line_fonts/index.shtml) - 良好的信息和其他资源和字体的链接.
- [Hershey Vector Font](http://paulbourke.net/dataformats/hershey)  - 60 年代矢量字体的`.fnt` 格式. 包括对字体原始数据格式的很好的概述.
- [hershey-fonts](https://github.com/kamalmostafa/hershey-fonts) - Hershey 字体的 C 库和原始字体数据.
- [OneLineFonts.com](https://www.onelinefonts.com) - 有一些单行字体可供购买的商业网站.
- [svg-fonts](https://gitlab.com/oskay/svg-fonts) - SVG 格式的单行字体，主要用于 [Hershey Text](https://gitlab.com/oskay/hershey-text) Inkscape 插件.
- [CNC Text Tool](https://msurguy.github.io/cnc-text-tool/) - 基于浏览器的 Hershey 文本工具，可导出为 SVG.

## Inspiration and Instruction

博客文章、文章、教程、画廊、视频等.

- [An Intro to Pen Plotters](https://medium.com/quarterstudio/an-intro-to-pen-plotters-29b6bd4327ba) - 有关开始使用旧 HPGL 绘图仪的好信息.
- [1980s pen plotters of the future](https://notes.variogr.am/2012/08/12/1980s-pen-plotters-of-the-future) - 老式钢笔绘图仪的另一个介绍.
- [Pen Plotter Programming: The Basics](https://medium.com/@fogleman/pen-plotter-programming-the-basics-ec0407ab5929) - 编程矢量路径的一些基础知识，包括排序、连接和简化.
- [On Generative Algorithms](https://inconvergent.net/generative) - 有趣算法的 13 部分演练.
- [Roland DG DXY-990](https://hackaday.io/project/12276-roland-dg-dxy-990) - Roland 平板绘图仪的快速入门指南.
- [The Cohen-Sutherland Line Clipping Algorithm](https://sighack.com/post/cohen-sutherland-line-clipping-algorithm) - 一个有趣算法的详细解释和示例.
- [Vera Molnár](https://www.surfacemag.com/articles/vera-molnar-in-thinking-machines-at-moma) - 和绘图师.
- [Hektor](http://juerglehni.com/works/hektor) - 2002 年的原始电缆牵引机器人.
- [Pen Plotter Art & Algorithms](https://mattdesl.svbtle.com/pen-plotter-1) - 创建用于绘图的生成图形的两部分介绍.
- [Surface Projection](https://bitaesthetics.com/posts/surface-projection.html) - 使用 Python 和 Penplot 深入研究表面投影和隐藏线去除.
- [Fractal Generation with L-Systems](https://bitaesthetics.com/posts/fractal-generation-with-l-systems.html) - 创建基于线的分形图形的技术.
- [Pen Plotter Art & Algorithms](https://mattdesl.svbtle.com/pen-plotter-1) - 绘图仪介绍、AxiDraw、`penplot` 库演练.
- [Introduction to TSP art](https://wiki.evilmadscientist.com/TSP_art) - 旅行商问题（单路径）艺术的资源.
- [Hidden wireframe removal](https://trmm.net/Hidden_Wireframe) - 讨论和链接到用于去除 STL 文件的线框的代码.
- [How to Draw Generative Art with an Axidraw Pen Plotter](https://www.dirtalleydesign.com/blogs/news/how-to-draw-prints-with-an-axidraw-pen-plotter) - 很多不错的技巧，并非都是 Axidraw 特有的，还有一些笔评和方便的 3D 打印工具.
- [The Best XY Plotters in 2020](https://all3dp.com/2/pen-plotters-best-xy-plotters/) - 很好地概述了 AxiDraw 及其克隆，以及一些 DIY 选项.
- [Journal Intime II](https://fr.calameo.com/read/0002895619da2a1b1daf8) - Vera Molnár 的笔记本之一，日期为 1983-1985

## Manuals and Ephemera

扫描的绘图仪手册和营销信息来自 [Internet Archive](https://archive.org)

### Manuals

- [Apple Color Plotter User's Manual](https://archive.org/details/AppleColorPlotter)
- [Programming CalComp Pen Plotters (1968)](https://archive.org/details/bitsavers_calcompProlottersJun68_2464236)
- [Commodore 1520 Printer Plotter Manual (1983)](https://archive.org/details/1520PrinterPlotterUsersManualStyleA)
- [Commodore 1520 Printer Plotter Manual](https://archive.org/details/1520PrinterPlotterusersManualStyleB)
- [Control Data 165/165-2 Plotter Manual](https://archive.org/details/bitsavers_cdc160139c_4086972)
- [HP 7475A Graphics Plotter Operation and Interconnection Manual](https://archive.org/details/HP7475AOperationManual)
- [HP 7570A DraftPro Plotter Hardware Support Manual](https://archive.org/details/7570adraftproplotterhardwaresupportmanual0757090000201pagesdec86)
- [HP 7585B Drafting Plotter Service Manual (1983)](https://archive.org/details/bitsavers_hpplotter0_18190273)
- [HP DraftPro Plotter User's Guide (1986)](https://archive.org/details/draftproplotterusersguide0757090017163pagesmay86)
- [HP DraftPro Plotter Programmers Reference (1986)](https://archive.org/details/draftproprogrammersreference0757090001387pagessep86)
- [Radio Shack TRS-80 Plotter Printer Manual](https://archive.org/details/Plotter_Printer_19xx_Radio_Shack)
- [Roland DXY-880 Operation Manual (1984)](https://archive.org/details/RolandDXY880PlotterOperationManual)
- [Roland DPX-3300 Service Notes (1987)](https://archive.org/details/dpx-3300-service-manual)
- [Roland DPX-3300 Schematics (1987)](https://archive.org/details/dpx-3300-schematics)
- [Siemens C1613 Plotter Manual (German)](https://archive.org/details/SiemensC1613Manual)

### Ephemera

- [Time Share Peripherals TSP-212 Brochure](https://archive.org/details/TNM_Time_Share_Peripherals_-_TSP-212_plotting_sys_20170630_0194)
- [Hewlett-Packard Journal Volume 29 Number 1](https://archive.org/details/Hewlett-Packard_Journal_Vol._29_No._1_1977-09_Hewlett-Packard) - 多篇关于 HP 9872A 型和 7221A 型笔式绘图仪开发的文章.
- [Hewlett-Packard Journal Volume 32 Number 11](https://archive.org/details/Hewlett-Packard_Journal_Vol._32_No._11_1981-11_Hewlett-Packard) - 有关 HP 7580A 型绘图仪开发的多篇文章.
- [CalComp Precision Graphics System 900/728 Brochure (1970)](https://archive.org/details/TNM_CalComp_-_Precision_graphics_system_900-728_20170630_0196)
- [Digital Plotting Newsletter (1967)](https://archive.org/details/TNM_Digital_Plotting_Newsletter_march-april_1967__20171014_0114)
- [Versatec Printers and Plotters Brochure (1977)](https://archive.org/details/TNM_Versatec_printers_and_plotters_-_Versatec_a_X_20180227_0009)
- [Versatec Printer/Plotters, Plotters and Output Systems (1981)](https://archive.org/details/TNM_Printer-plotters_plotters_and_output_systems__20171113_0057)
- [Roland Users Group Volume 2 Number 4 (1984)](https://archive.org/details/RolandUsersGroupVolume2Number41984/page/n39/mode/2up) - 第 36 页（PDF 第 40 页）_计算机和绘图仪取代绘图表和铅笔_文章.
- [Omega-t Systems FasPlot Plotter Brochure](https://archive.org/details/TNM_Omega-t_Systems_-_FasPlot_Plotter_20170630_0254)
- [Commodore Computer Plotter CBM 8075 Brochure (German)](https://archive.org/details/Plotter_CBM8075_198x_Commodore_DE)
- [Strobe Model 100 Graphics Plotter Brochure (1980)](https://archive.org/details/TNM_Strope_Model_100_graphics_plotter_-_Strobe_In_20180506_0009)

## Community

在哪里可以找到其他绘图仪和绘图机器人的朋友.

- [#plottertwitter](https://twitter.com/hashtag/plottertwitter) - 带有很多情节的 Twitter 标签.
- [PlotterArt Subreddit](https://www.reddit.com/r/PlotterArt)
- [AxiDraw Subreddit](https://www.reddit.com/r/axidraw)
- [Generative Art Subreddit](https://www.reddit.com/r/generative)
- [Plotter People](https://plotterpeople.github.io/) - 面对面的聚会（迄今为止的旧金山和纽约），包括会谈和绘图艺术画廊.
- [DrawingBots Discord Forum](https://discordapp.com/invite/XHP3dBg) - 社区活跃的 Discord 论坛.
- [PlotterFiles](https://plotterfiles.com/) - 共享绘图仪 SVG 文件的社区.

## Plotter Art For Sale

- [Paul Rickards](https://shop.paulrickards.com)
- [Michael Fogleman](https://www.michaelfogleman.com/plotter)
- [inconvergent](http://buy.inconvergent.net)
- [Customized Streetart](https://www.literalstreetart.com) - 带有可选笔式绘图仪输出的可定制地图.
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
- [awesome-3d-engines-for-plotters](https://github.com/msurguy/awesome-3d-engines-for-plotters)

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Brian Boucheron](https://boucheron.org/brian) 已放弃本作品的所有版权和相关或邻接权.
