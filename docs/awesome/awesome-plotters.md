<div class="github-widget" data-repo="beardicus/awesome-plotters"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Plotters [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

计算机控制绘图机和其他视觉艺术机器人的代码和资源精选列表.



## Hardware

### Plotters

- [AxiDraw](https://shop.evilmadscientist.com/productsmenu/846) - 笔式绘图仪 [Evil Mad Scientist](https://www.evilmadscientist.com), very popular on #plottertwitter.
- [Line-us](https://www.line-us.com) - 一个可爱的小机器人绘图臂.
- [Drawing Robot](https://www.thingiverse.com/thing:2349232) - 带有运行 grbl 固件的 Arduino CNC Shield 控制器的 3d 可打印 AxiDraw 克隆.
- [4xiDraw](https://www.instructables.com/id/4xiDraw/) - 另一个 3d 可打印 AxiDraw 克隆，带有运行 grbl 固件的 Arduino CNC Shield 控制器.
- [WaterColorBot](https://watercolorbot.com) - XY 艺术机器人和软件来绘制水彩颜料.
- [EggBot](https://egg-bot.com) - 用于蛋形和球形物体的笔式绘图仪.
- [HP Pen Plotters](https://www.hpmuseum.net/exhibit.php?class=4&cat=24)  - 来自 HPGL 标准创建者的老式台式和落地式笔式绘图仪.  7475A 型号非常常见，通常可以在 eBay 上找到.
- [Roland Pen Plotters](https://www.youtube.com/watch?v=6_pwzqPk6Gg)  - 老式平板 HPGL 笔式绘图仪. 在 eBay 上搜索“roland dxy”.
- [Polargraph](http://www.polargraph.co.uk) - 原始的极谱仪硬件和软件项目.
- [BrachioGraph](https://brachiograph.readthedocs.io/en/latest/) - 由摇杆、伺服系统和运行 Python 的 Raspberry Pi 制成的廉价而简单的绘图仪.
- [Arduino CNC Drawing Machine](https://www.diymachines.co.uk/arduino-cnc-drawing-machine) - 一个相当简单的 3d 打印 AxiDraw 风格的绘图仪，带有良好的视频文档.

### Motor Controllers

- [grblShield](https://github.com/synthetos/grblShield) - 转动电机所需的所有步进电机控制硬件 [Arduino](https://www.arduino.cc) 使用 grbl 固件进入基于 G 代码的运动控制器.  ([adafruit](https://www.adafruit.com/product/1750))
- [TinyG](https://github.com/synthetos/TinyG)  - 功能更强大、更强大的 6 轴基于 G 代码的运动控制硬件.  ([adafruit](https://www.adafruit.com/product/1749))
- [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) - 用于 Arduino 的 Grbl 兼容步进电机控制屏蔽，类似于 grblShield.
- [Raspberry Pi CNC Hat](https://wiki.protoneer.co.nz/Raspberry_Pi_CNC)  - 带有步进控制器和运行 grbl 的微控制器的 Raspberry Pi 附加板. 与 Pi 的串行引脚接口.
- [EBB Driver Board](https://shop.evilmadscientist.com/productsmenu/188) - 基于 USB 的双步进电机控制器板，最初是为 EggBot 设计的.

### Accessories

- [WiFi232](http://biosrhythm.com/?page_id=1453)  - 通过 DB25 插头 Wifi 到 RS-232 串行. 无线控制您的串行绘图仪.
- [Plotter Cable Pinout](http://sites.music.columbia.edu/cmc/chiplotle/plotter_cable.pdf)  - 适用于大多数 HP 和 Roland 绘图仪的绘图仪电缆示意图. 在 eBay 或亚马逊上搜索“DB9 到 DB25 串行零调制解调器电缆”或类似产品，以找到出售的产品.

### Pens

- [Sharpie Fine Point Plotter Adapter](https://www.printables.com/model/156721-sharpie-fine-point-plotter-adapter) - 3d 打印适配器，可将标准 Sharpie 安装在 HP-GL 绘图仪中.
- [Parametric 3d-Printable Plotter Pen Adapter](https://openjscad.xyz/#https://gist.githubusercontent.com/beardicus/d668c0f6b96be53d16dc/raw/plotter-pen-adapter.jscad) - 可调节模型打印各种笔的适配器.
- [Plotter Pen STL Models](https://www.printables.com/model/156722-plotter-pen) - 短和长标准绘图笔的准确 STL 模型.
- [Pens for AxiDraw](https://wiki.evilmadscientist.com/Pens_for_AxiDraw) - 适用于一般绘图仪滥用的笔列表.
- [Pens for EggBot](https://wiki.evilmadscientist.com/Pen_choices) - 以鸡蛋和玻璃为重点的钢笔建议，但仍然是普遍适用的信息.
- [JetPens – The Best White Ink Pens](https://www.jetpens.com/blog/the-best-white-ink-pens/pt/340) - 对许多白色墨水笔的全面审查，并附有其覆盖特征的图片.

## Software

### HPGL

HPGL 是大多数旧笔式绘图仪甚至许多新的乙烯基切割机都使用的基于串行/文本的协议.

- [Chiplotle](https://github.com/drepetto/chiplotle) - 用于生成 HPGL 并与串行绘图仪连接的 Python 库.
- [HPGL Reference Guide](https://www.isoplotec.co.jp/HPGL/eHPGL.htm) - 基于 HTML 的 HPGL 参考.
- [HP 7475A Interfacing and Programming Manual](https://archive.org/details/HP7475AInterfacingandProgrammingManual) - 包含完整 HPGL 参考的扫描 PDF 手册.
- [djipco/hpgl](https://github.com/djipco/hpgl) - 一个 Node.js 库，用于与 HPGL 兼容的绘图仪和打印机进行通信.
- [hp2xx](https://www.gnu.org/software/hp2xx)  - 将 HPGL 转换为其他矢量和光栅格式的 GNU 工具. 也可以在 X11 中用作预览.
- [vec](https://github.com/anachrocomputer/vec) - 用于生成 HPGL 的示例 C 代码，带有海龟图形界面.
- [d3-hpgl](https://github.com/aubergene/d3-hpgl) - HTML Canvas API 的适配器，因此您可以使用流行的输出 HPGL [D3](https://d3js.org) 图书馆.
- [HPGL Viewer](https://github.com/drskullster/HPGLViewer) - 使用 JavaScript 和 HTML5 画布的 HPGL 查看器.
- [HPGL Sender](https://github.com/LgHS/hpgl-sender) - 用于预览 HPGL 并将其发送到绘图仪的 Web 界面.
- [HPGLGraphics](https://github.com/ciaron/HPGLGraphics) - 用于编写 HPGL 文件的处理库.

### G-code

 G 代码是用于控制 CNC 机床的基于文本的标准. 虽然它是为工业机器设计的，但它在许多爱好者 3d 打印机固件中的使用使其在小型 DIY 项目中也无处不在.

- [grbl](https://github.com/grbl/grbl) - 用于 Atmega 328 微控制器和 Arduino 的高性能 G 代码解释固件.
- [cncjs](https://github.com/cncjs/cncjs) - 基于 Web 的界面控制运行 grbl、TinyG 或其他基于 G 代码的固件的 CNC 机器.
- [node-gcode](https://github.com/ryansturmer/node-gcode) - Node.js G 代码解释器和模拟器.
- [svg2gcode](https://github.com/em/svg2gcode) - 用于将 SVG 转换为 G 代码的 Node.js 命令行实用程序.
- [svg2gcode](https://github.com/vishpat/svg2gcode) - 用于快速 SVG 到 G 代码转换的 Python 实用程序.
- [jscut](http://jscut.org/) - 用于将 SVG 转换为 G 代码的基于 Web 的实用程序.
- [Universal-G-Code-Sender](https://github.com/winder/Universal-G-Code-Sender) - 基于 Java 的 grbl 兼容的跨平台 G 代码发送器.
- [ChiliPeppr Hardware Fiddle](http://chilipeppr.com) - 模块化的基于网络的工作空间，用于可视化 G 代码和控制硬件.
- [gcode-generative-for-processing](https://github.com/o0morgan0o/gcode-generative-for-processing)  - 处理库，旨在从简单的形状创建 gcode.  （专为与 Creality CR10 一起使用而设计）
- [gcodeplot](https://github.com/arpruss/gcodeplot) - 用于将 SVG 和 HPGL 转换为 3 轴 CNC 机床的 G 代码的 Python 实用程序.

### Plotter-Specific

特定于特定绘图仪或控制器的软件.

- [axidraw](https://github.com/evil-mad/axidraw) - Inkscape 的官方 AxiDraw 扩展.
- [axi](https://github.com/fogleman/axi) - AxiDraw v3 的非官方 Python 库.
- [xy](https://github.com/fogleman/xy) - Makeblock XY 绘图仪机器人套件的​​实用程序.
- [LaserGRBL](https://github.com/arkypita/LaserGRBL)  - 用于 grbl 控制器的激光优化 Windows GUI. 可重新用于使用螺线管进行笔上下移动的 DIY 笔式绘图仪.
- [Line-us Inkscape Plugin](https://github.com/Line-us/Inkscape-Plugin) - 直接从 Inkscape 将绘图发送到 Line-us 绘图仪.
- [Line-us API Examples](https://github.com/Line-us/Line-us-Programming) - Line-us 绘图仪基于 G 代码的 API 的示例代码.
- [@beardicus/line-us](https://github.com/beardicus/line-us) - 用于从 Node 或浏览器控制 Line-us 机器的 JavaScript 库.
- [PenPlotter](https://github.com/RickMcConney/PenPlotter) - 使用 repetier 固件的 Polargraph 控制器.
- [Makelangelo-firmware](https://github.com/MarginallyClever/Makelangelo-firmware) - Makeangelo 极谱仪机器人的固件.
- [RoboPaint](https://github.com/evil-mad/robopaint) - WaterColorBot 软件.
- [AxiTurtle](https://github.com/ralphcrutzen/AxiTurtle) - 处理中 AxiDraw 的海龟图形.
- [GRBL-Plotter](https://github.com/svenhb/GRBL-Plotter) - 带有 SVG 和 DXF 导入的 grbl 控制器的绘图仪优化 Windows GUI，以及灵活的上/下笔控制.
- [saxi](https://github.com/nornagon/saxi)  - AxiDraw 的驱动程序和库. 使用恒定加速度运动规划并自动调整到纸张大小.
- [MP2300-Tools](https://github.com/Jan--Henrik/MP2300-Tools) - 用于将 HPGL 转换为 Graphtec 的 GPGL 格式的软件，以及用于 Graphtec 绘图笔适配器的 CAD 文件.

### Vector Creation

从头开始或通过从其他格式转换来创建矢量图的工具.

- [Inkscape](https://inkscape.org) - 流行的跨平台开源矢量图形编辑器.
- [p5.js](https://p5js.org) - “让艺术家、设计师、教育工作者和初学者可以使用编码的 JavaScript 库”.
- [Paper.js](http://paperjs.org) - “矢量图形脚本的瑞士军刀”.
- [ln](https://github.com/fogleman/ln) - 用 Go 编写的基于矢量的 3D 渲染器.
- [autotrace](https://github.com/autotrace/autotrace) - 将位图图像转换为矢量图形.
- [stipplegen](https://github.com/evil-mad/stipplegen)  - 从位图图像创建有趣的点画图.  ([blog post](https://www.evilmadscientist.com/2012/stipplegen2))
- [SquiggleDraw](https://github.com/gwygonik/SquiggleDraw/commits/master) - “SquiggleDraw 将从图像创建一个 SVG 文件，使用亮度来改变正弦波的幅度”.
- [svgurt](https://svgurt.com) - 基于 Web 的 PNG 到 SVG 创意面条机.
- [maptrace](https://github.com/mzucker/maptrace) - 通过跟踪光栅图像生成防水的多边形矢量图.
- [Drawbot_image_to_gcode_v2](https://github.com/Scott-Cooper/Drawbot_image_to_gcode_v2) - 创建用于绘图机器人的 G 代码.
- [blackstripes](https://github.com/fullscreennl/blackstripes-python-extensions) - 将 PNG 图像转换为 SVG 线条图.
- [Ribbon](https://github.com/fogleman/ribbon) - 用 Go 编写的蛋白质带状图.
- [penplot](https://github.com/mattdesl/penplot) - JavaScript 中绘图仪艺术的开发环境.
- [penkit](https://github.com/paulgb/penkit) - 用于创建基于线的 SVG 图形的 Python 库.
- [generativeExamples](https://github.com/digitalcoleman/generativeExamples) - 生成可打印 PDF 的示例处理代码.
- [Let's make map](https://svg-exporter.netlify.com) - 从 Mapzen 瓦片中导出 SVG 地图的基于 Web 的工具.
- [SuperformulaSVG for web](https://jasonwebb.github.io/SuperformulaSVG-for-web) - 一个生成的线条艺术网络应用程序.
- [scribbleplot](https://github.com/bleeptrack/scribbleplot) - 处理中的涂鸦图像转换.
- [Maker.js](https://maker.js.org) - 用于为 CNC 和激光切割机创建 2D 矢量绘图的库.
- [Turtletoy](https://turtletoy.net) - 带有 SVG 导出功能的基于浏览器的 JavaScript 海龟图形 API.
- [cozyvec](https://github.com/brubsby/cozyvec) - 用于绘图仪艺术和推文图的 Web/独立终端环境.
- [makio135/plotter](https://observablehq.com/collection/@makio135/plotter) - 一个 [Observable](https://observablehq.com/) 笔记本收藏充满了面向绘图仪的工作.
- [PlotterFun](https://mitxela.com/plotterfun/) - 基于浏览器的图像到 SVG 转换器，类似于 SquiggleDraw.
- [SVG.js](https://svgjs.dev/) - 用于创建、操作和动画 SVG 的无依赖轻量级库.
- [Components AI](https://components.ai/) - 用于探索生成空间的实验计算设计平台.
- [DrawingBotV3](https://github.com/SonarSonic/DrawingBotV3) - 用于将图像转换为线条图的跨平台软件.
- [linedraw](https://github.com/LingDong-/linedraw) - 用于将图像转换为粗略矢量线图的 Python 工具.

### Vector Utilities

用于操作和优化基于矢量的文件格式的工具.

- [svgsort](https://github.com/inconvergent/svgsort) - 用于绘制 SVG 文件的路径规划，减少了用笔移动所花费的时间.
- [svgo](https://github.com/svg/svgo) - 基于 Node.js 的优化 SVG 文件的工具.
- [Polargraph Optimizer](https://github.com/ezheidtmann/polargraph-optimizer) - 优化极谱仪的绘图计划.
- [penkit-optimize](https://github.com/paulgb/penkit/tree/master/optimizer) - 一个 SVG 优化器，它使用车辆路径求解器来最小化绘图时间.
- [svg-crowbar](https://github.com/NYTimes/svg-crowbar) - 仅用于从 HTML 文档中提取 SVG 的 Chrome 小书签.
- [vpype](https://github.com/abey79/vpype) - 以绘图仪为中心的基于 Python 的 CLI 实用程序，用于生成和操作 SVG，包括缩放和优化路径.
- [SVG Cropper](https://msurguy.github.io/svg-cropper-tool/) - 基于浏览器的工具，用于使用不同的基元、自定义形状或其他 SVG 裁剪 SVG.

### Fonts

单行矢量字体或“雕刻字体”.

- [Summary of single line fonts](http://imajeenyus.com/computer/20150110_single_line_fonts/index.shtml) - Good information and links to other resources and fonts.
- [Hershey Vector Font](http://paulbourke.net/dataformats/hershey)  - 60 年代矢量字体的“.fnt”格式. 包括对字体原始数据格式的一个很好的概述.
- [hershey-fonts](https://github.com/kamalmostafa/hershey-fonts) - 好时字体的 C 库和原始字体数据.
- [OneLineFonts.com](https://www.onelinefonts.com) - 一些单行字体可供购买的商业网站.
- [svg-fonts](https://gitlab.com/oskay/svg-fonts) - SVG 格式的单行字体，主要用于 [Hershey Text](https://gitlab.com/oskay/hershey-text) Inkscape 插件.
- [CNC Text Tool](https://msurguy.github.io/cnc-text-tool/) - 基于浏览器的 Hershey 文本工具，可导出为 SVG.

## Inspiration and Instruction

博客文章、文章、教程、画廊、视频等.

- [An Intro to Pen Plotters](https://medium.com/quarterstudio/an-intro-to-pen-plotters-29b6bd4327ba) - 有关开始使用旧 HPGL 绘图仪的好信息.
- [Pen Plotter Programming: The Basics](https://medium.com/@fogleman/pen-plotter-programming-the-basics-ec0407ab5929) - 编程矢量路径的一些基础知识，包括排序、连接和简化.
- [On Generative Algorithms](https://inconvergent.net/generative) - 有趣的算法的 13 部分精彩演练.
- [Roland DG DXY-990](https://hackaday.io/project/12276-roland-dg-dxy-990) - 罗兰平板绘图仪快速入门指南.
- [The Cohen-Sutherland Line Clipping Algorithm](https://sighack.com/post/cohen-sutherland-line-clipping-algorithm) - 一个有趣的算法的详细解释和例子.
- [Vera Molnár](https://www.surfacemag.com/articles/vera-molnar-in-thinking-machines-at-moma) - 和绘图艺术家.
- [Hektor](http://juerglehni.com/works/hektor) - 2002 年最初的基于电缆的绘图机器人.
- [Pen Plotter Art & Algorithms](https://mattdesl.svbtle.com/pen-plotter-1) - 创建用于绘图的生成图形的两部分介绍.
- [Surface Projection](https://bitaesthetics.com/posts/surface-projection.html) - 使用 Python 和 penplot 深入研究表面投影和隐藏线移除.
- [Fractal Generation with L-Systems](https://bitaesthetics.com/posts/fractal-generation-with-l-systems.html) - 创建基于线的分形图形的技术.
- [Introduction to TSP art](https://wiki.evilmadscientist.com/TSP_art) - 旅行商问题（单路径）艺术资源.
- [Hidden wireframe removal](https://trmm.net/Hidden_Wireframe) - 讨论和链接到用于删除 STL 文件的线框代码.
- [How to Draw Generative Art with an Axidraw Pen Plotter](https://www.dirtalleydesign.com/blogs/news/how-to-draw-prints-with-an-axidraw-pen-plotter) - 很多不错的提示，并非都是针对 Axidraw 的，还有一些笔评论和方便的 3D 打印工具.
- [The Best XY Plotters in 2020](https://all3dp.com/2/pen-plotters-best-xy-plotters/) - 很好地概述了 AxiDraw 及其克隆，以及一些 DIY 选项.
- [What is a pen plotter 2022?](https://www.youtube.com/watch?v=J1NpYzETm3M) - 2022 年现代绘图仪的精彩视频介绍.

## Manuals and Ephemera

扫描的绘图仪手册和营销蜉蝣，大部分来自 [Internet Archive](https://archive.org)

### Manuals

- [Apple Color Plotter User's Manual](https://archive.org/details/AppleColorPlotter)
- [Atari 1020 Color Printer Owner's Guide (1982)](https://archive.org/details/atari-1020-color-printer)
- [Atari 1020 Color Printer Field Service Manual (1983)](https://archive.org/details/atari1020colorprinterfieldservicemanualrev.011983atari)
- [Programming CalComp Pen Plotters (1968)](https://archive.org/details/bitsavers_calcompProlottersJun68_2464236)
- [Commodore 1520 Printer Plotter Manual (1983)](https://archive.org/details/1520PrinterPlotterUsersManualStyleA)
- [Commodore 1520 Printer Plotter Manual](https://archive.org/details/1520PrinterPlotterusersManualStyleB)
- [Control Data 165/165-2 Plotter Manual](https://archive.org/details/bitsavers_cdc160139c_4086972)
- [Houston Instrument DMP-160 Plotter Operation Manual](https://archive.org/details/houston-instrument-dmp-160-series-plotters-operation-manual)
- [HP 7475A Graphics Plotter Operation and Interconnection Manual](https://archive.org/details/HP7475AOperationManual)
- [HP 7570A DraftPro Plotter Hardware Support Manual](https://archive.org/details/7570adraftproplotterhardwaresupportmanual0757090000201pagesdec86)
- [HP 7585B Drafting Plotter Service Manual (1983)](https://archive.org/details/bitsavers_hpplotter0_18190273)
- [HP DraftPro Plotter User's Guide (1986)](https://archive.org/details/draftproplotterusersguide0757090017163pagesmay86)
- [HP DraftPro Plotter Programmers Reference (1986)](https://archive.org/details/draftproprogrammersreference0757090001387pagessep86)
- [Olivetti PL10 Microplotter User Guide (1983)](https://archive.org/details/olivettipl10microplotter)
- [Radio Shack TRS-80 Plotter Printer Manual](https://archive.org/details/Plotter_Printer_19xx_Radio_Shack)
- [Radio Shack TRS-80 Color Graphic Printer Operation Manual](https://archive.org/details/cgp-115_operation_manual)
- [Radio Shack TRS-80 Color Graphic Printer Service Manual](https://archive.org/details/cgp-115-service-manual)
- [Roland DXY-880 Operation Manual (1984)](https://archive.org/details/RolandDXY880PlotterOperationManual)
- [Roland DXY-980 Operation Manual (1985)](https://archive.org/details/rolanddxy980operationmanual)
- [Roland DXY-990 Operation Manual (1986)](https://archive.org/details/roland-dxy-990)
- [Roland DXY-1300 -1200 -1100 Command Reference Manual](https://archive.org/details/rolanddxy130012001100commandreferencemanualaf)
- [Roland DPX-2000 User's Manual](https://archive.org/details/roland-dpx-2000-manual)
- [Roland DPX-3300 Operation Manual (GitHub)](https://github.com/sismoke/Roland-DPX-3300/blob/master/manual/DPX-3300.pdf)
- [Roland DPX-3300 Service Notes (1987)](https://archive.org/details/dpx-3300-service-manual)
- [Roland DPX-3300 Schematics (1987)](https://archive.org/details/dpx-3300-schematics)
- [Roland DPX-3700A DPX-2700A User's Manual (Roland Direct Download)](https://downloadcenter.rolanddg.com/contents/manuals/DPX-3700A+2700A_USE_E_R8.pdf)
- [Rotring Tubular Plotter Points Practical Tips and Information](https://archive.org/details/rotingtubularplotterpointprakticaltipsandinformation)
- [Siemens C1613 Plotter Manual (German)](https://archive.org/details/SiemensC1613Manual)
- [Panasonic RK-P400C 4-Color Graphic Penwriter Manual](https://archive.org/details/panasonic-rk-p-400-c-manual)

### Ephemera

- [Time Share Peripherals TSP-212 Brochure](https://archive.org/details/TNM_Time_Share_Peripherals_-_TSP-212_plotting_sys_20170630_0194)
- [Hewlett-Packard Journal Volume 29 Number 1](https://archive.org/details/Hewlett-Packard_Journal_Vol._29_No._1_1977-09_Hewlett-Packard) - 多篇关于 HP 9872A 和 7221A 笔式绘图仪开发的文章.
- [Hewlett-Packard Journal Volume 32 Number 11](https://archive.org/details/Hewlett-Packard_Journal_Vol._32_No._11_1981-11_Hewlett-Packard) - 多篇关于 HP 7580A 绘图仪开发的文章.
- [CalComp Precision Graphics System 900/728 Brochure (1970)](https://archive.org/details/TNM_CalComp_-_Precision_graphics_system_900-728_20170630_0196)
- [Digital Plotting Newsletter (1967)](https://archive.org/details/TNM_Digital_Plotting_Newsletter_march-april_1967__20171014_0114)
- [Versatec Printers and Plotters Brochure (1977)](https://archive.org/details/TNM_Versatec_printers_and_plotters_-_Versatec_a_X_20180227_0009)
- [Versatec Printer/Plotters, Plotters and Output Systems (1981)](https://archive.org/details/TNM_Printer-plotters_plotters_and_output_systems__20171113_0057)
- [Roland Users Group Volume 2 Number 4 (1984)](https://archive.org/details/RolandUsersGroupVolume2Number41984/page/n39/mode/2up) - _计算机和绘图仪代替绘图表和铅笔_第 36 页的文章（PDF 第 40 页）.
- [Omega-t Systems FasPlot Plotter Brochure](https://archive.org/details/TNM_Omega-t_Systems_-_FasPlot_Plotter_20170630_0254)
- [Commodore Computer Plotter CBM 8075 Brochure (German)](https://archive.org/details/Plotter_CBM8075_198x_Commodore_DE)
- [Strobe Model 100 Graphics Plotter Brochure (1980)](https://archive.org/details/TNM_Strope_Model_100_graphics_plotter_-_Strobe_In_20180506_0009)
- [Roland DG Plotter Ad in Byte Magazine Vol 12 No 4 (1987)](https://archive.org/details/byte-magazine-1987-04/page/n159/mode/2up) ([via @OldTechAdverts](https://twitter.com/OldTechAdverts/status/1454558415355850755))
- [Auerbach On Digital Plotters And Image Digitizers (1972)](https://archive.org/details/auerbachondigitalplottersandimagedigitizers) - 一本关于绘图仪和数字化仪的书.
- [CalComp Graphics Products Brochure (1981)](https://archive.org/details/TNM_CalComp_graphics_products_plotters_and_printe_20171101_0032)
- [CalComp Plotters in 1968](https://www.youtube.com/watch?v=AAc4VLR6-Dg) - 展示平板 CalComp 绘图仪及其输出的宣传视频.

## Community

在哪里可以找到其他绘图仪和绘图机器人朋友.

- [#plottertwitter](https://twitter.com/hashtag/plottertwitter) - 带有很多情节的推特标签.
- [PlotterArt Subreddit](https://www.reddit.com/r/PlotterArt)
- [AxiDraw Subreddit](https://www.reddit.com/r/axidraw)
- [Generative Art Subreddit](https://www.reddit.com/r/generative)
- [Plotter People](https://plotterpeople.github.io/) - 面对面的聚会（到目前为止，旧金山和纽约市），包括会谈和绘图艺术画廊.
- [DrawingBots Discord Forum](https://discordapp.com/invite/XHP3dBg) - 拥有活跃社区的 Discord 论坛.
- [PlotterFiles](https://plotterfiles.com/) - 为绘图仪共享 SVG 文件的社区.

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
