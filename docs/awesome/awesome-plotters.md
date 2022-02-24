<div class="github-widget" data-repo="beardicus/awesome-plotters"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Plotters [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of code and resources for computer-controlled drawing machines and other visual art robots.



## Hardware

### Plotters

- [AxiDraw](https://shop.evilmadscientist.com/productsmenu/846) - Pen plotter from [Evil Mad Scientist](https://www.evilmadscientist.com), very popular on [#plottertwitter](https://twitter.com/hashtag/plottertwitter).
- [Line-us](https://www.line-us.com) - A cute little kickstarted robotic drawing arm.
- [Makeblock XY Plotter](http://learn.makeblock.com/en/xy-plotter-robot-kit) - Hackable XY plotter kit (discontinued?).
- [Drawing Robot](https://www.thingiverse.com/thing:2349232) - 3d-Printable AxiDraw clone w/ [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) controller running grbl firmware.
- [4xiDraw](https://www.instructables.com/id/4xiDraw/) - Yet another 3d-printable AxiDraw clone w/ [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) controller running grbl firmware.
- [WaterColorBot](https://watercolorbot.com) - XY art robot and software to plot with watercolor paints.
- [EggBot](https://egg-bot.com) - Pen plotter for egg-shaped and spherical objects.
- [HP Pen Plotters](https://www.hpmuseum.net/exhibit.php?class=4&cat=24) - Vintage desktop and floor-standing pen plotters from the creator of the HPGL standard. Model 7475A is very common and can usually be found on eBay.
- [Roland Pen Plotters](https://www.youtube.com/watch?v=6_pwzqPk6Gg) - Vintage flatbed HPGL pen plotters. Search eBay for "roland dxy".
- [Polargraph](http://www.polargraph.co.uk) - The original polargraph hardware and software project.
- [Makelangelo](http://www.makelangelo.com) - Open source polargraph artbot.
- [BrachioGraph](https://brachiograph.readthedocs.io/en/latest/) - A cheap and simple plotter made from sticks, servos, and a Raspberry Pi running Python.
- [Arduino CNC Drawing Machine](https://www.diymachines.co.uk/arduino-cnc-drawing-machine) - A fairly simple 3d-printed AxiDraw-style plotter with good video documentation.

### Motor Controllers

- [grblShield](https://github.com/synthetos/grblShield) - All the stepper motor control hardware needed to turn an [Arduino](https://www.arduino.cc) <i>into a G-code-based motion controller using the grbl firmware.</i><b>使用 grbl 固件进入基于 G 代码的运动控制器。</b> <i>(</i> <b>(</b>[adafruit](https://www.adafruit.com/product/1750))
- [TinyG](https://github.com/synthetos/TinyG) - More featureful and robust 6-axis G-code-based motion control hardware. ([adafruit](https://www.adafruit.com/product/1749))
- [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) - Grbl-compatible stepper motor control shield for Arduino, similar to the [grblShield](https://github.com/synthetos/grblShield).
- [Raspberry Pi CNC Hat](https://wiki.protoneer.co.nz/Raspberry_Pi_CNC) - Raspberry Pi add-on board w/ stepper controllers and a microcontroller running grbl. Interfaces with the Pi's serial pins.

### Accessories

- [WiFi232](http://biosrhythm.com/?page_id=1453) - Wifi to RS-232 serial via a DB25 plug. Control your serial plotter wirelessly.
- [Plotter Cable Pinout](http://sites.music.columbia.edu/cmc/chiplotle/plotter_cable.pdf) - Schematic for a plotter cable that will work for most HP and Roland plotters. Search eBay or Amazon for `DB9 to DB25 Serial Null Modem Cable` or similar to find them for sale.

### Pens

- [Sharpie Fine Point Plotter Adapter](https://www.thingiverse.com/thing:229982) - 3d-printed adapter to fit a standard Sharpie in an HP-GL plotter.
- [Parametric 3d-Printable Plotter Pen Adapter](https://openjscad.org/#https://gist.githubusercontent.com/beardicus/d668c0f6b96be53d16dc/raw/plotter-pen-adapter.jscad) - Adjustable model to print adapters for various pens.
- [Plotter Pen STL Models](https://www.thingiverse.com/thing:227985) - Accurate STL models of both short and long standard plotter pens.
- [Pens for AxiDraw](https://wiki.evilmadscientist.com/Pens_for_AxiDraw) - List of pens suitable for general plotter abuse.
- [Pens for EggBot](https://wiki.evilmadscientist.com/Pen_choices) - Egg- and glass-focused pen recommendations but still generally applicable information.
- [JetPens – The Best White Ink Pens](https://www.jetpens.com/blog/the-best-white-ink-pens/pt/340) - A comprehensive review of many white ink pens, with pictures of their coverage characteristics.

## Software

### HPGL

HPGL is a serial/text-based protocol used by most old pen plotters, and even many new vinyl cutters.

- [Chiplotle](https://github.com/drepetto/chiplotle) - Python library for generating HPGL and interfacing with serial plotters.
- [Chiplotle on Parallel Port](https://gitlab.com/mononym/chiplotle-on-parallel-port) - Tweak of Chiplotle to work with a parallel port connection.
- [HPGL Reference Guide](https://www.isoplotec.co.jp/HPGL/eHPGL.htm) - HTML-based HPGL Reference.
- [HP 7475A Interfacing and Programming Manual](https://archive.org/details/HP7475AInterfacingandProgrammingManual) - Scanned PDF manual that contains a full HPGL reference.
- [djipco/hpgl](https://github.com/djipco/hpgl) - A Node.js library to communicate with HPGL-compatible plotters and printers.
- [hp2xx](https://www.gnu.org/software/hp2xx) - GNU tool to convert HPGL into other vector and raster formats. Can also be used as a previewing in X11.
- [vec](https://github.com/anachrocomputer/vec) - Example C code for generating HPGL, with a turtle graphics interface.
- [d3-hpgl](https://github.com/aubergene/d3-hpgl) - An adapter for the HTML Canvas API so you can output HPGL using the popular [D3](https://d3js.org) library.
- [HPGL Viewer](https://github.com/drskullster/HPGLViewer) - An HPGL Viewer using JavaScript and HTML5 canvas.
- [HPGL Sender](https://github.com/LgHS/hpgl-sender) - A web interface for previewing HPGL and sending it to your plotter.
- [HPGLGraphics](https://github.com/ciaron/HPGLGraphics) - A Processing library for writing HPGL files.

### G-code

G-code is a text-based standard for controlling CNC machines. Though it was designed for industrial machines, its use in many hobbyist 3d printer firmwares has made it ubiquitous in small-scale DIY projects as well.

- [grbl](https://github.com/grbl/grbl) - A high-performance G-code interpreting firmware for the Atmega 328 microcontroller and Arduino.
- [cncjs](https://github.com/cncjs/cncjs) - A web-based interface controlling CNC machines running grbl, TinyG, or other G-code-based firmware.
- [node-gcode](https://github.com/ryansturmer/node-gcode) - Node.js G-code interpreter and simulator.
- [svg2gcode](https://github.com/em/svg2gcode) - Node.js command line utility for converting SVG to G-code.
- [svg2gcode](https://github.com/vishpat/svg2gcode) - Python utility for fast SVG to G-code conversion.
- [jscut](http://jscut.org/) - A web-based utility for converting SVG to G-code.
- [Universal-G-Code-Sender](https://github.com/winder/Universal-G-Code-Sender) - Java-based grbl-compatible cross-platform G-code sender.
- [ChiliPeppr Hardware Fiddle](http://chilipeppr.com) - Modular web-based workspaces to visualize G-code and control hardware.
- [gcode-generative-for-processing](https://github.com/o0morgan0o/gcode-generative-for-processing) - Processing library, aiming to create gcode from simple shapes. (Designed for usage with the Creality CR10)
- [gcodeplot](https://github.com/arpruss/gcodeplot) - Python utility to convert SVG and HPGL to G-code for a 3-axis CNC machine.

### Plotter-Specific

Software that is specific to a particular plotter or controller.

- [axidraw](https://github.com/evil-mad/axidraw) - Official AxiDraw extensions for Inkscape.
- [axi](https://github.com/fogleman/axi) - Unofficial Python library for the AxiDraw v3.
- [xy](https://github.com/fogleman/xy) - Makeblock XY 绘图仪机器人套件的​​实用程序。
- [LaserGRBL](https://github.com/arkypita/LaserGRBL) - Laser-optimized Windows GUI for grbl controllers. Could be repurposed for DIY pen plotters that use a solenoid for pen up/down movements.
- [Line-us Inkscape Plugin](https://github.com/Line-us/Inkscape-Plugin) - Sends drawings to the [Line-us plotter](https://www.line-us.com) directly from Inkscape.
- [Line-us API Examples](https://github.com/Line-us/Line-us-Programming) - Example code for the [Line-us](https://www.line-us.com) plotter's G-code-based API.
- [@beardicus/line-us](https://github.com/beardicus/line-us) - JavaScript library for controlling the [Line-us](https://www.line-us.com) machine from Node or the browser.
- [PenPlotter](https://github.com/RickMcConney/PenPlotter) - Polargraph controller that uses repetier firmware.
- [Makelangelo-firmware](https://github.com/MarginallyClever/Makelangelo-firmware) - Firmware for the Makelangelo polargraph robot.
- [RoboPaint](https://github.com/evil-mad/robopaint) - Software for the WaterColorBot.
- [AxiTurtle](https://github.com/ralphcrutzen/AxiTurtle) - Turtle graphics for AxiDraw in Processing.
- [GRBL-Plotter](https://github.com/svenhb/GRBL-Plotter) - Plotter-optimized Windows GUI for grbl controller with SVG and DXF import, and flexible pen up/down control.
- [saxi](https://github.com/nornagon/saxi) - Driver and library for the AxiDraw. Uses constant-acceleration motion planning and automatically resizes to paper.
- [MP2300-Tools](https://github.com/Jan--Henrik/MP2300-Tools) - Software for converting HPGL to Graphtec's GPGL format, as well as CAD files for a Graphtec plotter pen adapter.

### Vector Creation

Tools to create vector artwork from scratch or by conversion from other formats.

- [Inkscape](https://inkscape.org) - Popular cross-platform open source vector graphics editor.
- [p5.js](https://p5js.org) - "JavaScript library that makes coding accessible for artists, designers, educators, and beginners".
- [Paper.js](http://paperjs.org) - "The Swiss Army Knife of Vector Graphics Scripting".
- [ln](https://github.com/fogleman/ln) - Vector-based 3D renderer written in Go.
- [autotrace](https://github.com/autotrace/autotrace) - Converts bitmap images to vector graphics.
- [stipplegen](https://github.com/evil-mad/stipplegen) - Creates interesting stippled drawings from bitmap images. ([blog post](https://www.evilmadscientist.com/2012/stipplegen2))
- [SquiggleDraw](https://github.com/gwygonik/SquiggleDraw/commits/master) - "SquiggleDraw will create a SVG file from an image, using the brightness to change the amplitude of sine waves".
- [svgurt](https://svgurt.com) - Web-based PNG to SVG creative noodler.
- [maptrace](https://github.com/mzucker/maptrace) - Produce watertight polygonal vector maps by tracing raster images.
- [Drawbot_image_to_gcode_v2](https://github.com/Scott-Cooper/Drawbot_image_to_gcode_v2) - Creates G-code for use on drawbots.
- [blackstripes](https://github.com/fullscreennl/blackstripes-python-extensions) - Turns a PNG image into a SVG line drawing.
- [Ribbon](https://github.com/fogleman/ribbon) - Ribbon diagrams of proteins in written in Go.
- [penplot](https://github.com/mattdesl/penplot) - A development environment for plotter art in JavaScript.
- [penkit](https://github.com/paulgb/penkit) - A Python library for creating line-based SVG graphics.
- [generativeExamples](https://github.com/digitalcoleman/generativeExamples) - Example Processing code that generates plottable PDFs.
- [Let's make map](https://svg-exporter.netlify.com) - Web-based tool to export an SVG map from Mapzen tiles.
- [SuperformulaSVG for web](https://jasonwebb.github.io/SuperformulaSVG-for-web) - A generative line art web app.
- [scribbleplot](https://github.com/bleeptrack/scribbleplot) - Scribbly image transformations in Processing.
- [Maker.js](https://maker.js.org) - Library for creating 2D vector drawings for CNC and laser cutter machines.
- [Turtletoy](https://turtletoy.net) - Browser-based JavaScript turtle graphics API with SVG export.
- [cozyvec](https://github.com/brubsby/cozyvec) - Web/Standalone terminal environment for plotter art and tweet plots.
- [makio135/plotter](https://observablehq.com/collection/@makio135/plotter) - An [Observable](https://observablehq.com/) notebook collection full of plotter-oriented work.
- [PlotterFun](https://mitxela.com/plotterfun/) - Browser-based Image to SVG converter similar to SquiggleDraw.
- [SVG.js](https://svgjs.dev/) - Dependency-free lightweight library for creating, manipulating, and animating SVG.
- [Components AI](https://components.ai/) - Experimental computational design platform for exploring generative space.
- [DrawingBotV3](https://github.com/SonarSonic/DrawingBotV3) - Cross-platform software for converting images to line drawings.

### Vector Utilities

Tools to manipulate and optimize vector-based file formats.

- [svgsort](https://github.com/inconvergent/svgsort) - Path planning for plotting SVG files, reduces time spent moving with the pen up.
- [svgo](https://github.com/svg/svgo) - Node.js-based tool for optimizing SVG files.
- [Polargraph Optimizer](https://github.com/ezheidtmann/polargraph-optimizer) - Optimize drawing plan for a polargraph.
- [penkit-optimize](https://github.com/paulgb/penkit/tree/master/optimizer) - An SVG optimizer that uses a vehicle routing solver to minimize plot time.
- [svg-crowbar](https://github.com/NYTimes/svg-crowbar) - Chrome-only bookmarklet for extracting SVG from an HTML document.
- [vpype](https://github.com/abey79/vpype) - Plotter-focused Python-based CLI utility for generating and manipulating SVGs, including scaling and optimizing paths.
- [SVG Cropper](https://msurguy.github.io/svg-cropper-tool/) - A browser-based tool to crop SVGs using different primitives, custom shapes, or other SVGs.

### Fonts

Single-line vector fonts or "engraving fonts".

- [Summary of single line fonts](http://imajeenyus.com/computer/20150110_single_line_fonts/index.shtml) - Good information and links to other resources and fonts.
- [Hershey Vector Font](http://paulbourke.net/dataformats/hershey) - `.fnt` format of vector fonts from the 60s. Includes a good overview of the original data format of the fonts.
- [hershey-fonts](https://github.com/kamalmostafa/hershey-fonts) - C library and original font data for the Hershey fonts.
- [OneLineFonts.com](https://www.onelinefonts.com) - Commercial site with some single-line fonts available for purchase.
- [svg-fonts](https://gitlab.com/oskay/svg-fonts) - Single-line fonts in an SVG format, mainly for use with the [Hershey Text](https://gitlab.com/oskay/hershey-text) Inkscape plugin.
- [CNC Text Tool](https://msurguy.github.io/cnc-text-tool/) - Browser-based Hershey Text tool with export to SVG.

## Inspiration and Instruction

Blog posts, articles, tutorials, galleries, videos, et cetera.

- [An Intro to Pen Plotters](https://medium.com/quarterstudio/an-intro-to-pen-plotters-29b6bd4327ba) - Good info on getting started with old HPGL plotters.
- [1980s pen plotters of the future](https://notes.variogr.am/2012/08/12/1980s-pen-plotters-of-the-future) - Another intro to vintage pen plotters.
- [Pen Plotter Programming: The Basics](https://medium.com/@fogleman/pen-plotter-programming-the-basics-ec0407ab5929) - Some basics of programming vector paths, including sorting, joining, and simplifying.
- [On Generative Algorithms](https://inconvergent.net/generative) - Nice 13-part walkthrough of interesting algorithms.
- [Roland DG DXY-990](https://hackaday.io/project/12276-roland-dg-dxy-990) - Quickstart guide for a Roland flatbed plotter.
- [The Cohen-Sutherland Line Clipping Algorithm](https://sighack.com/post/cohen-sutherland-line-clipping-algorithm) - Detailed explanation and examples of an interesting algorithm.
- [Vera Molnár](https://www.surfacemag.com/articles/vera-molnar-in-thinking-machines-at-moma) - OG plotter artist.
- [Hektor](http://juerglehni.com/works/hektor) - The original cable-based drawbot from 2002.
- [Pen Plotter Art & Algorithms](https://mattdesl.svbtle.com/pen-plotter-1) - A two-part intro to creating generative graphics for plotting.
- [Surface Projection](https://bitaesthetics.com/posts/surface-projection.html) - Deep dive into surface projection and hidden line removal using Python and penplot.
- [Fractal Generation with L-Systems](https://bitaesthetics.com/posts/fractal-generation-with-l-systems.html) - Techniques for creating line-based fractal graphics.
- [Pen Plotter Art & Algorithms](https://mattdesl.svbtle.com/pen-plotter-1) - Introduction to plotters, AxiDraw, walkthrough of the `penplot` library.
- [Introduction to TSP art](https://wiki.evilmadscientist.com/TSP_art) - Resources for traveling salesman problem (single path) art.
- [Hidden wireframe removal](https://trmm.net/Hidden_Wireframe) - Discussion and links to code for wireframe removal of STL files.
- [How to Draw Generative Art with an Axidraw Pen Plotter](https://www.dirtalleydesign.com/blogs/news/how-to-draw-prints-with-an-axidraw-pen-plotter) - Lots of nice tips, not all specific to the Axidraw, plus some pen reviews and handy 3d-printed tools.
- [The Best XY Plotters in 2020](https://all3dp.com/2/pen-plotters-best-xy-plotters/) - Good overview of the AxiDraw and its clones, plus some DIY options.
- [Journal Intime II](https://fr.calameo.com/read/0002895619da2a1b1daf8) - One of Vera Molnár's notebooks, dated 1983–1985

## Manuals and Ephemera

Scanned plotter manuals and marketing ephemera from the [Internet Archive](https://archive.org)

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
- [Roland DPX-3300 Operation Manual](https://github.com/sismoke/Roland-DPX-3300/blob/master/manual/DPX-3300.pdf)
- [Roland DPX-3300 Service Notes (1987) (GitHub)](https://archive.org/details/dpx-3300-service-manual)
- [Roland DPX-3300 Schematics (1987)](https://archive.org/details/dpx-3300-schematics)
- [Roland DPX-3700A DPX-2700A User's Manual (Roland Direct Download)](https://downloadcenter.rolanddg.com/contents/manuals/DPX-3700A+2700A_USE_E_R8.pdf) 
- [Siemens C1613 Plotter Manual (German)](https://archive.org/details/SiemensC1613Manual)
- [Panasonic RK-P400C 4-Color Graphic Penwriter Manual](https://archive.org/details/panasonic-rk-p-400-c-manual/)

### Ephemera

- [Time Share Peripherals TSP-212 Brochure](https://archive.org/details/TNM_Time_Share_Peripherals_-_TSP-212_plotting_sys_20170630_0194)
- [Hewlett-Packard Journal Volume 29 Number 1](https://archive.org/details/Hewlett-Packard_Journal_Vol._29_No._1_1977-09_Hewlett-Packard) - Multiple articles about the development of the HP Model 9872A and 7221A pen plotters.
- [Hewlett-Packard Journal Volume 32 Number 11](https://archive.org/details/Hewlett-Packard_Journal_Vol._32_No._11_1981-11_Hewlett-Packard) - Multiple articles about the development of the HP Model 7580A plotter.
- [CalComp Precision Graphics System 900/728 Brochure (1970)](https://archive.org/details/TNM_CalComp_-_Precision_graphics_system_900-728_20170630_0196)
- [Digital Plotting Newsletter (1967)](https://archive.org/details/TNM_Digital_Plotting_Newsletter_march-april_1967__20171014_0114)
- [Versatec Printers and Plotters Brochure (1977)](https://archive.org/details/TNM_Versatec_printers_and_plotters_-_Versatec_a_X_20180227_0009)
- [Versatec Printer/Plotters, Plotters and Output Systems (1981)](https://archive.org/details/TNM_Printer-plotters_plotters_and_output_systems__20171113_0057)
- [Roland Users Group Volume 2 Number 4 (1984)](https://archive.org/details/RolandUsersGroupVolume2Number41984/page/n39/mode/2up) - _Computers and Plotters Take the Place of Drafting Tables and Pencils_ article on page 36 (PDF page 40).
- [Omega-t Systems FasPlot Plotter Brochure](https://archive.org/details/TNM_Omega-t_Systems_-_FasPlot_Plotter_20170630_0254)
- [Commodore Computer Plotter CBM 8075 Brochure (German)](https://archive.org/details/Plotter_CBM8075_198x_Commodore_DE)
- [Strobe Model 100 Graphics Plotter Brochure (1980)](https://archive.org/details/TNM_Strope_Model_100_graphics_plotter_-_Strobe_In_20180506_0009)
- [Roland DG Plotter Ad in Byte Magazine Vol 12 No 4 (1987)](https://archive.org/details/byte-magazine-1987-04/page/n159/mode/2up) ([via @OldTechAdverts](https://twitter.com/OldTechAdverts/status/1454558415355850755))

## Community

Where to find other plotter and drawbot friends.

- [#plottertwitter](https://twitter.com/hashtag/plottertwitter) - Twitter hashtag with lots o' plots.
- [PlotterArt Subreddit](https://www.reddit.com/r/PlotterArt)
- [AxiDraw Subreddit](https://www.reddit.com/r/axidraw)
- [Generative Art Subreddit](https://www.reddit.com/r/generative)
- [Plotter People](https://plotterpeople.github.io/) - In-person meetups (SF and NYC so far) with talks and plotter art galleries.
- [DrawingBots Discord Forum](https://discordapp.com/invite/XHP3dBg) - Discord forum with an active community.
- [PlotterFiles](https://plotterfiles.com/) - Community for sharing SVG files for plotters.

## Plotter Art For Sale

- [Paul Rickards](https://shop.paulrickards.com)
- [Michael Fogleman](https://www.michaelfogleman.com/plotter)
- [inconvergent](http://buy.inconvergent.net)
- [Customized Streetart](https://www.literalstreetart.com) - Customizable maps with optional pen plotter output.
- [Monica Rizzolli](https://www.saatchiart.com/account/artworks/155196)
- [EmergentDesign](https://emergentdesign.bigcartel.com/products)
- [BustBright](https://mkt.com/bustbright)
- [Martin O'Leary](https://shop.mewo2.com)
- [Geoffrey Bradway](https://www.chromatocosmos.com/)
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

To the extent possible under law, [Brian Boucheron](https://boucheron.org/brian) has waived all copyright and related or neighboring rights to this work.
