<div class="github-widget" data-repo="beardicus/awesome-plotters"></div>
## Awesome Plotters [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of code and resources for computer-controlled drawing machines and other visual art robots.



## Hardware

### Plotters

- [AxiDraw](https://shop.evilmadscientist.com/productsmenu/846) - Pen plotter from [Evil Mad Scientist](https://www.evilmadscientist.com), very popular on #plottertwitter.
- [Line-us](https://www.line-us.com) - A cute little kickstarted robotic drawing arm.
- [Drawing Robot](https://www.thingiverse.com/thing:2349232) - 3d-Printable AxiDraw clone w/ Arduino CNC Shield controller running grbl firmware.
- [4xiDraw](https://www.instructables.com/id/4xiDraw/) - Yet another 3d-printable AxiDraw clone w/ Arduino CNC Shield controller running grbl firmware.
- [WaterColorBot](https://watercolorbot.com) - XY art robot and software to plot with watercolor paints.
- [EggBot](https://egg-bot.com) - Pen plotter for egg-shaped and spherical objects.
- [HP Pen Plotters](https://www.hpmuseum.net/exhibit.php?class=4&cat=24) - Vintage desktop and floor-standing pen plotters from the creator of the HPGL standard. Model 7475A is very common and can usually be found on eBay.
- [Roland Pen Plotters](https://www.youtube.com/watch?v=6_pwzqPk6Gg) - Vintage flatbed HPGL pen plotters. Search eBay for "roland dxy".
- [BrachioGraph](https://brachiograph.readthedocs.io/en/latest/) - A cheap and simple plotter made from sticks, servos, and a Raspberry Pi running Python. Here's [video of a BrachioGraph talk at PyCon UK](https://www.youtube.com/watch?v=u4Jh1daCl60) from the creator.
- [Arduino CNC Drawing Machine](https://www.diymachines.co.uk/arduino-cnc-drawing-machine) - A fairly simple 3d-printed AxiDraw-style plotter with good video documentation.
- [PlotterXY](https://github.com/jamescarruthers/PlotterXY) - A coreXY plotter made from extrusion, 3d-printed parts, and an inexpensive 3d-printer control board.
- [NextDraw](https://store.bantamtools.com/collections/bantam-tools-nextdraw) – The [Bantam Tools](https://www.bantamtools.com) successor to the popular AxiDraw pen plotter.

### Motor Controllers

- [grblShield](https://github.com/synthetos/grblShield) - All the stepper motor control hardware needed to turn an [Arduino](https://www.arduino.cc) into a G-code-based motion controller using the grbl firmware. ([adafruit](https://www.adafruit.com/product/1750))
- [TinyG](https://github.com/synthetos/TinyG) - More featureful and robust 6-axis G-code-based motion control hardware. ([adafruit](https://www.adafruit.com/product/1749))
- [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield) - Grbl-compatible stepper motor control shield for Arduino, similar to the grblShield.
- [Raspberry Pi CNC Hat](https://wiki.protoneer.co.nz/Raspberry_Pi_CNC) - Raspberry Pi add-on board w/ stepper controllers and a microcontroller running grbl. Interfaces with the Pi's serial pins.
- [EBB Driver Board](https://shop.evilmadscientist.com/productsmenu/188) - USB-based dual stepper motor controller board, originally designed for the EggBot.

### Accessories and Adapters

- [WiFi232](http://biosrhythm.com/?page_id=1453) - Wifi to RS-232 serial via a DB25 plug. Control your serial plotter wirelessly.
- [Plotter Cable Pinout](http://sites.music.columbia.edu/cmc/chiplotle/plotter_cable.pdf) - Schematic for a plotter cable that will work for most HP and Roland plotters. Search eBay or Amazon for `DB9 to DB25 Serial Null Modem Cable` or similar to find them for sale.
- [PlotAdapter](https://github.com/rhalkyard/plotadapter) - "Serial-GPIB converter for HP Plotters", uses an Arduino microcontroller to convert serial HPGL to the GPIB/HP-IB expected by some older HP plotters.

### Pens

- [Sharpie Fine Point Plotter Adapter](https://www.printables.com/model/156721-sharpie-fine-point-plotter-adapter) - 3d-printed adapter to fit a standard Sharpie in an HP-GL plotter.
- [Parametric 3d-Printable Plotter Pen Adapter](https://openjscad.xyz/#https://gist.githubusercontent.com/beardicus/d668c0f6b96be53d16dc/raw/plotter-pen-adapter.jscad) - Adjustable model to print adapters for various pens.
- [Plotter Pen STL Models](https://www.printables.com/model/156722-plotter-pen) - Accurate STL models of both short and long standard plotter pens.
- [Pens for AxiDraw](https://wiki.evilmadscientist.com/Pens_for_AxiDraw) - List of pens suitable for general plotter abuse.
- [Pens for EggBot](https://wiki.evilmadscientist.com/Pen_choices) - Egg- and glass-focused pen recommendations but still generally applicable information.
- [JetPens – The Best White Ink Pens](https://www.jetpens.com/blog/the-best-white-ink-pens/pt/340) - A comprehensive review of many white ink pens, with pictures of their coverage characteristics.

## Software

### HPGL

HPGL is a serial/text-based protocol used by most old pen plotters, and even many new vinyl cutters.

- [Chiplotle](https://github.com/drepetto/chiplotle) - Python library for generating HPGL and interfacing with serial plotters.
- [Chiplotle3](https://github.com/cyprienh/chiplotle3) - Chiplotle fork updated for Python 3.x compatibility.
- [HPGL Reference Guide](https://www.isoplotec.co.jp/HPGL/eHPGL.htm) - HTML-based HPGL Reference.
- [HP 7475A Interfacing and Programming Manual](https://archive.org/details/HP7475AInterfacingandProgrammingManual) - Scanned PDF manual that contains a full HPGL reference.
- [djipco/hpgl](https://github.com/djipco/hpgl) - A Node.js library to communicate with HPGL-compatible plotters and printers.
- [hp2xx](https://www.gnu.org/software/hp2xx) - GNU tool to convert HPGL into other vector and raster formats. Can also be used as a previewing in X11.
- [vec](https://github.com/anachrocomputer/vec) - Example C code for generating HPGL, with a turtle graphics interface.
- [d3-hpgl](https://github.com/aubergene/d3-hpgl) - An adapter for the HTML Canvas API so you can output HPGL using the popular [D3](https://d3js.org) library.
- [HPGL Viewer](https://github.com/drskullster/HPGLViewer) - An HPGL Viewer using JavaScript and HTML5 canvas.
- [HPGL Sender](https://github.com/LgHS/hpgl-sender) - A web interface for previewing HPGL and sending it to your plotter.
- [HPGLGraphics](https://github.com/ciaron/HPGLGraphics) - A Processing library for writing HPGL files.
- [processing2hpgl](https://github.com/awdriggs/processing2hpgl) - A Processing library that allows for direct communication with HPGL pen plotters from within a Processing sketch.

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

### Plotter Control

Software for controlling plotter hardware.

- [axidraw](https://github.com/evil-mad/axidraw) - Official AxiDraw extensions for Inkscape.
- [axi](https://github.com/fogleman/axi) - Unofficial Python library for the AxiDraw v3.
- [xy](https://github.com/fogleman/xy) - Utilities for the Makeblock XY Plotter Robot Kit.
- [LaserGRBL](https://github.com/arkypita/LaserGRBL) - Laser-optimized Windows GUI for grbl controllers. Could be repurposed for DIY pen plotters that use a solenoid for pen up/down movements.
- [Line-us Inkscape Plugin](https://github.com/Line-us/Inkscape-Plugin) - Sends drawings to the Line-us plotter directly from Inkscape.
- [Line-us API Examples](https://github.com/Line-us/Line-us-Programming) - Example code for the Line-us plotter's G-code-based API.
- [@beardicus/line-us](https://github.com/beardicus/line-us) - JavaScript library for controlling the Line-us machine from Node or the browser.
- [PenPlotter](https://github.com/RickMcConney/PenPlotter) - Polargraph controller that uses repetier firmware.
- [Makelangelo-firmware](https://github.com/MarginallyClever/Makelangelo-firmware) - Firmware for the Makelangelo polargraph robot.
- [RoboPaint](https://github.com/evil-mad/robopaint) - Software for the WaterColorBot.
- [AxiTurtle](https://github.com/ralphcrutzen/AxiTurtle) - Turtle graphics for AxiDraw in Processing.
- [GRBL-Plotter](https://github.com/svenhb/GRBL-Plotter) - Plotter-optimized Windows GUI for grbl controller with SVG and DXF import, and flexible pen up/down control.
- [saxi](https://github.com/nornagon/saxi) - Driver and library for the AxiDraw. Uses constant-acceleration motion planning and automatically resizes to paper.
- [MP2300-Tools](https://github.com/Jan--Henrik/MP2300-Tools) - Software for converting HPGL to Graphtec's GPGL format, as well as CAD files for a Graphtec plotter pen adapter.
- [Inkcut](https://github.com/inkcut/inkcut) - Application for controlling 2D plotters, cutters, engravers, and CNC machines.

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
- [LineDream](https://linedream.marcrleonard.com/) - A generative art library for Python that can export SVGs.
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
- [linedraw](https://github.com/LingDong-/linedraw) - Python tool to convert images to sketchy vector line drawings.
- [plotter.vision](https://plotter.vision/) - Interactive website for hidden line removal of STL files to generate plottable SVG. Also supports Red/Blue 3D glasses.
- [plotting-maps](https://github.com/piebro/plotting-maps) - A simple web tool to create OpenStreetMap SVG maps for plotting.
- [ThreadPlotter](https://github.com/LiciaHe/threadPlotter) — "A toolkit for the design and fabrication of delicate punch needle embroidery using X-Y plotters".


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
- [svg-fonts](https://gitlab.com/oskay/svg-fonts) - Single-line fonts in an SVG format, mainly for use with the [Hershey Text](https://gitlab.com/oskay/hershey-text) Inkscape plugin.
- [CNC Text Tool](https://msurguy.github.io/cnc-text-tool/) - Browser-based Hershey Text tool with export to SVG.
- [hf2gcode](https://github.com/Andy1978/hf2gcode) - Generates G-code from text with a Hershey font.
- [FifteenTwenty: Commodore 1520 plotter font](https://github.com/scruss/FifteenTwenty) – [Blog post](https://scruss.com/blog/2016/04/23/fifteentwenty-commodore-1520-plotter-font/) about the creation of this font from the original ROM.

## Inspiration, Instruction, and Research

Blog posts, articles, tutorials, galleries, videos, et cetera.

- [An Intro to Pen Plotters](https://medium.com/quarterstudio/an-intro-to-pen-plotters-29b6bd4327ba) - Good info on getting started with old HPGL plotters.
- [An Introduction to Pen Plotting](https://mrmrs.cc/writing/pen-plotting-intro/) - Another getting started article with modern pen plotters.
- [Pen Plotter Programming: The Basics](https://medium.com/@fogleman/pen-plotter-programming-the-basics-ec0407ab5929) - Some basics of programming vector paths, including sorting, joining, and simplifying.
- [On Generative Algorithms](https://inconvergent.net/generative) - Nice 13-part walkthrough of interesting algorithms.
- [Roland DG DXY-990](https://hackaday.io/project/12276-roland-dg-dxy-990) - Quickstart guide for a Roland flatbed plotter.
- [The Cohen-Sutherland Line Clipping Algorithm](https://sighack.com/post/cohen-sutherland-line-clipping-algorithm) - Detailed explanation and examples of an interesting algorithm.
- [Vera Molnár](https://www.surfacemag.com/articles/vera-molnar-in-thinking-machines-at-moma) - OG plotter artist.
- [Hektor](http://juerglehni.com/works/hektor) - The original cable-based drawbot from 2002.
- [Pen Plotter Art & Algorithms](https://mattdesl.svbtle.com/pen-plotter-1) - A two-part intro to creating generative graphics for plotting.
- [Surface Projection](https://bitaesthetics.com/posts/surface-projection.html) - Deep dive into surface projection and hidden line removal using Python and penplot.
- [Fractal Generation with L-Systems](https://bitaesthetics.com/posts/fractal-generation-with-l-systems.html) - Techniques for creating line-based fractal graphics.
- [Introduction to TSP art](https://wiki.evilmadscientist.com/TSP_art) - Resources for traveling salesman problem (single path) art.
- [Hidden wireframe removal](https://trmm.net/Hidden_Wireframe) - Discussion and links to code for wireframe removal of STL files.
- [How to Draw Generative Art with an Axidraw Pen Plotter](https://www.dirtalleydesign.com/blogs/news/how-to-draw-prints-with-an-axidraw-pen-plotter) - Lots of nice tips, not all specific to the Axidraw, plus some pen reviews and handy 3d-printed tools.
- [The Best XY Plotters in 2020](https://all3dp.com/2/pen-plotters-best-xy-plotters/) - Good overview of the AxiDraw and its clones, plus some DIY options.
- [What is a pen plotter 2022?](https://www.youtube.com/watch?v=J1NpYzETm3M) - Nice video introduction to modern plotters in 2022.
- [Tools, Tricks, and Hacks: Exploring Novel Digital Fabrication Workflows on #PlotterTwitter](https://dl.acm.org/doi/abs/10.1145/3411764.3445653) - Research paper on the novel workflows of the plotter community ([Video Summary](https://www.youtube.com/watch?v=xqhT-8ElJ68)).
- [Orbis Tertius](https://www.glkitty.com/pages/orbistertius.html) - An immersive digital installation with plotter output of Martian topography.
- [Tech Tangents: Plotting For The First Time - HP 7470A](https://www.youtube.com/watch?v=tk4c4WMZJZ8) - Nice video showing an HP 7470A operated from an HP 85 computer.
- [CuriousMarc: HP 7475A Plotter and HPGL Demo](https://www.youtube.com/watch?v=Tr7Mbw9gLpk) - Video of an HP 7475A plotting some demos.
- [CuriousMarc: Refilling or Replacing Vintage HP Plotter Pens](https://www.youtube.com/watch?v=h-oj4HrTH14) - Video showing how to open, clean, and refill vintage HP plotter pens.
- [Commodore 1520 Plotter Demonstration](https://www.youtube.com/watch?v=QwPTluBvKLU) - Video of the Commodore 1520 plotter in action, including a cover-off shot of the mechanism.
- [Tech Tangents: Gold Standard Plotter - HP 7475A](https://www.youtube.com/watch?v=8785ktWD7vQ) - Video with some HPGL and plotter history, plus operating an HP 7475A from an IBM 5160 microcomputer.
- [curiousmarc.com: HP 7475A Plotter](https://www.curiousmarc.com/computing/hp-7475a-plotter) - A great collection of info, ephemera, plot files, three YouTube videos, and a 3d-printable replacement part for the HP 7475A.
- [From Lettering Guides to CNC Plotters](https://www.typotheque.com/articles/from-lettering-guides-to-cnc-plotters-a-brief-history-of-technical-lettering-tools) - "A Brief History of Technical Lettering Tools".
- [Building an interactive plotter art installation](https://lostpixels.io/writings/building-interactive-plotter-art) - Nice writeup (with videos) of an interactive plotter art exhibit at SIGGRAPH 2023.
- [Taxan KPL 710 Demo Plot](https://www.youtube.com/watch?v=Xms3sZONQjo) - A handheld recording of the Taxan KPL 710 running its demo plot.
- [Sweet-P Six Shooter SP-600 Plotter Demonstration](https://www.youtube.com/watch?v=xE9LVOMbKxk) – A recording of the Sweet-P SP-600 running its demo plot.
- [Bottle Plotter](https://vgnotepad.blogspot.com/2024/04/bottle-plotter.html) – Blog post about building a cylindrical pen plotter for drawing on wine bottles.
- [Buildlog.net Atari 1020 Plotter Retrofit](https://www.buildlog.net/blog/2019/10/inktober-project-2019-post-5/) – Blog post and video about converting an Atari 1020 plotter to use a ESP32-based GRBL controller.
- [Texas Instruments HX-1000 Plotter Photos](http://www.hexbus.com/TI-99_4A_Home_Computer_Page/Hexbus_HX-1000_Printer_Plotter.html) – Photo gallery of the plotter's exterior, interior, and packaging.
- [Making cheap HP plotter pens](https://scruss.com/blog/2014/04/06/making-cheap-hp-plotter-pens-yet-another-hp-gl-viewer/) – Blog post mainly about using vinyl cutter parts as pen holders.
- [Marcel Schwittlick and The Long Run](https://www.artxcode.io/journal/marcel-schwittlick-the-long-run) – Interview with Marcel, and lots of photos and videos of his work and workspace.
- [Lars Wander and Mixing Paint With Code](https://www.artxcode.io/journal/lars-wander-interview) – Interview with Lars Wander, plus art and videos.
- [Flatulence, Crystals, and Happy Little Accidents by Nick Fitzgerald (RustConf 2019)](https://www.youtube.com/watch?v=Ho3xr4b60Zg) — A RustConf talk with very little Rust, more about the creative process of generative art and pen plotters.
- [Recreating Retro Plotter Art, by Sher Minn (Plotter People #1)](https://www.youtube.com/watch?v=OR_TzMFhv50) — Conference talk with lots of great computer and plotter history.
- [20+ Questions About My Plotter Painting Practice](https://www.eyesofpanda.com/project/plotter_painting_q_a/) – Q&A blog post with lots of details about more painterly plotting.
- [How to Watercolor Paint with a Robotic Drawing Machine: An Interview with Licia He](https://www.dirtalleydesign.com/blogs/news/how-to-watercolor-painting-with-a-robotic-drawing-machine-an-interview-with-licia-he)
- [300 Days with Plotters](https://liciahe.medium.com/300-days-with-plotters-14159ab64034) – Blog post by Licia He about a successful 100 day plotting challenge.

## Manuals, Ephemera, Papers, and Patents

Scanned plotter manuals, marketing ephemera, academic papers, and patents. Thank you to the [Internet Archive](https://archive.org) for most of these.

### Manuals

Sorted alphabetically by company name and product name.

- [Apple Color Plotter User's Manual](https://archive.org/details/AppleColorPlotter)
- [Atari 1020 Color Printer Owner's Guide (1982)](https://archive.org/details/atari-1020-color-printer) – A higher-quality scan is also available as [a PDF on buildlog.net](https://www.buildlog.net/blog/wp-content/uploads/2019/09/atari-1020-color-printer-owners-guide.pdf)
- [Atari 1020 Color Printer Field Service Manual (1983)](https://archive.org/details/atari1020colorprinterfieldservicemanualrev.011983atari)
- [CalComp Artisan Plus 1023/1025/1026 User's Guide (1990)](https://archive.org/details/calcomp-artisan-plus-1023-1025-1026-users-guide)
- [Programming CalComp Pen Plotters (1968)](https://archive.org/details/bitsavers_calcompProlottersJun68_2464236)
- [Commodore 1520 Printer Plotter Manual (1983)](https://archive.org/details/1520PrinterPlotterUsersManualStyleA)
- [Commodore 1520 Printer Plotter Manual](https://archive.org/details/1520PrinterPlotterusersManualStyleB)
- [Control Data 165/165-2 Plotter Manual](https://archive.org/details/bitsavers_cdc160139c_4086972)
- [Esterline Angus Spartan X-Y Recorder Instruction Manual](https://archive.org/details/manualsplus_03665) – Rev 1178
- [Esterline Angus Spartan X-Y Recorder Instruction Manual (1980)](https://archive.org/details/manualsplus_03659) – Revs 1080, 1178, 0480
- [Esterline Angus Model XY530 Recorder Instruction Manual](https://archive.org/details/manualsplus_03657)
- [Esterline Angus Model XY575 Recorder Instruction Manual (1976)](https://archive.org/details/manualsplus_03641)
- [Fluke 1771A Intelligent Digital Plotter User's Manual (1983)](https://archive.org/details/manualsplus_03096)
- [Gerber GS750 Plus User Manual (1995) (manualslib)](https://www.manualslib.com/manual/465193/Gerber-Gs750-Plus.html)
- [Gerber Signmaker IVB User's Manual (1983) (manualslib)](https://www.manualslib.com/manual/464167/Gerber-Signmaker-Ivb.html)
- [Graphtec Pen Plotter MP303 Series Service Manual (2004)](https://archive.org/details/manualzilla-id-5807113)
- [Houston Instrument DMP-160 Plotter Operation Manual](https://archive.org/details/houston-instrument-dmp-160-series-plotters-operation-manual)
- [Houston Instrument DM/PL Command Language (1984)](https://archive.org/details/hi-dmpl-command-language)
- [Houston Instrument DMP-40V Operation Manual (1988)](https://archive.org/details/dmp-40v)
- [Houston Instrument HIPLOT DMP-51/52 Operation Manual (1985)](https://archive.org/details/hi-dmp-51-52-operation-manual)
- [Houston Instrument Interface Notes for DM/PL Intelligent Plotters (1983)](https://archive.org/details/hi-interface-notes-dm-pl-plotters)
- [Houston Instrument Stand Assembly Procedure DMP-50 Series Plotter](https://archive.org/details/hi-stand-assembly-procedure-dmp-50-series-plotter)
- [Houston Instrument DMP-60 Series Plotters Operation Manual (1990)](https://archive.org/details/houston-instruments-dmp-60-manual)
- [HP 7470A Interconnection Guide](https://archive.org/details/manualzilla-id-7029812)
- [HP 7470A Operator's Manual (manualslib)](https://www.manualslib.com/manual/1089592/Hp-7470a.html)
- [HP 7475A Graphics Plotter Operation and Interconnection Manual](https://archive.org/details/HP7475AOperationManual)
- [HP 7570A DraftPro Plotter Hardware Support Manual](https://archive.org/details/7570adraftproplotterhardwaresupportmanual0757090000201pagesdec86)
- [HP 7580B Drafting Plotter Service Manual (1986)](https://archive.org/details/hp-7580-b-plotter-service-manual)
- [HP 7585B Drafting Plotter Service Manual (1983)](https://archive.org/details/bitsavers_hpplotter0_18190273)
- [HP DraftPro Plotter User's Guide (1986)](https://archive.org/details/draftproplotterusersguide0757090017163pagesmay86)
- [HP DraftPro Plotter Programmers Reference (1986)](https://archive.org/details/draftproprogrammersreference0757090001387pagessep86)
- [Mutoh ET202 Scriber (German)](https://archive.org/details/mutoh-et202-leichtgemacht)
- [Olivetti PL10 Microplotter User Guide (1983)](https://archive.org/details/olivettipl10microplotter)
- [Olivetti P6060 Programming Manual (1979) (Italian)](https://archive.org/details/olivettip6060prestazionigrafiche)
- [Philips X-Y Flat Bed Recorder PM 8120 (1971)](https://archive.org/details/manualsplus_03520)
- [Radio Shack TRS-80 Plotter Printer Manual](https://archive.org/details/Plotter_Printer_19xx_Radio_Shack)
- [Radio Shack TRS-80 Color Graphic Printer Operation Manual](https://archive.org/details/cgp-115_operation_manual)
- [Radio Shack TRS-80 Color Graphic Printer Service Manual](https://archive.org/details/cgp-115-service-manual)
- [Roland DXY-880 Operation Manual (1984)](https://archive.org/details/RolandDXY880PlotterOperationManual)
- [Roland DXY-980 Operation Manual (1985)](https://archive.org/details/rolanddxy980operationmanual)
- [Roland DXY-990 Operation Manual (1986)](https://archive.org/details/roland-dxy-990)
- [Roland DXY-1300 -1200 -1100 Command Reference Manual](https://archive.org/details/rolanddxy130012001100commandreferencemanualaf)
- [Roland DXY-1350A -1150A User's Manual (1997) (manualslib)](https://www.manualslib.com/manual/884553/Roland-Dxy_1350.html)
- [Roland DPX-2000 User's Manual](https://archive.org/details/roland-dpx-2000-manual)
- [Roland DPX-3300 Operation Manual (GitHub)](https://github.com/sismoke/Roland-DPX-3300/blob/master/manual/DPX-3300.pdf)
- [Roland DPX-3300 Service Notes (1987)](https://archive.org/details/dpx-3300-service-manual)
- [Roland DPX-3300 Schematics (1987)](https://archive.org/details/dpx-3300-schematics)
- [Roland DPX-3700A DPX-2700A User's Manual (Roland Direct Download)](https://downloadcenter.rolanddg.com/contents/manuals/DPX-3700A+2700A_USE_E_R8.pdf)
- [Roland XY Plotter DXY-1350A DXY-1150A User's Manual (1997)](https://archive.org/details/manualzilla-id-5691908)
- [Rotring Tubular Plotter Points Practical Tips and Information](https://archive.org/details/rotingtubularplotterpointprakticaltipsandinformation)
- [Rotring NC-scriber CS 50 Operating Instructions (1989)](https://archive.org/details/rotring_NC-scriber_CS_50_Operating_Instructions)
- [SEGA SP-400 Operation Manual](https://archive.org/details/sega-sp-400) – This doesn't present as a flippable book on the archive, but the original page scans are still available for download.
- [Sekonic SPL-450+/SPL-455 User Manual (1990) (German)](https://archive.org/details/sekonicspl450spl455)
- [Siemens C1613 Plotter Manual (German)](https://archive.org/details/SiemensC1613Manual)
- [Silver Reed Colour PenGraph EB-50 Operating Manual (1984)](https://archive.org/details/silver-reed-colour-pengraph-eb-50-operating-manual)
- [Taxan X-Y Plotter KPL 710 Instruction Manual](https://pzwiki.wdka.nl/mediadesign/File:Taxan_kpl710_x-y_plotter.pdf)
- [Tectronix 4662 Interactive Digital Plotter User Manual (1976)](https://archive.org/details/bitsavers_tektronix42InteractiveDigitalPlotterUserManualNov1_40423494)
- [Tectronix HC100 Instruction Manual (1987)](https://archive.org/details/manualsonline-id-212d14c3-7d2f-4e64-906f-1a22e86d1f35/)
- [Panasonic RK-P400C 4-Color Graphic Penwriter Manual](https://archive.org/details/panasonic-rk-p-400-c-manual)
- [Panasonic Penwriter Manual Excerpt: RS232 Protocol Section](https://archive.org/details/panasonicpenwriterprotocol)
- [[Unknown Brand] LP 2002 Photo Plotter Attachment Operating Manual (German)](https://archive.org/details/lp-2002-betriebsanleitung/) - Also see [Martin Bircher's thread](https://mastodon.social/@artandtech/109382879937442706) with pictures of this device.

### Ephemera

- [Time Share Peripherals TSP-212 Brochure](https://archive.org/details/TNM_Time_Share_Peripherals_-_TSP-212_plotting_sys_20170630_0194)
- [Hewlett-Packard Journal Volume 29 Number 1](https://archive.org/details/Hewlett-Packard_Journal_Vol._29_No._1_1977-09_Hewlett-Packard) - Multiple articles about the development of the HP Model 9872A and 7221A pen plotters.
- [Hewlett-Packard Journal Volume 32 Number 10](https://archive.org/details/Hewlett-Packard_Journal_Vol._32_No._10_1981-10_Hewlett-Packard) - Multiple articles about the development of the HP Model 7580A plotter.
- [Hewlett-Packard Journal Volume 32 Number 11](https://archive.org/details/Hewlett-Packard_Journal_Vol._32_No._11_1981-11_Hewlett-Packard) - Multiple articles about the development of the HP Model 7580A plotter.
- [Hewlett-Packard Journal Volume 33 Number 12 (1982)](https://archive.org/details/Hewlett-Packard_Journal_Vol._33_No._12_1982-12_Hewlett-Packard) - Multiple articles about the HP Model 7470A plotter.
- [CalComp Precision Graphics System 900/728 Brochure (1970)](https://archive.org/details/TNM_CalComp_-_Precision_graphics_system_900-728_20170630_0196)
- [Digital Plotting Newsletter (1967)](https://archive.org/details/TNM_Digital_Plotting_Newsletter_march-april_1967__20171014_0114)
- [Versatec Printers and Plotters Brochure (1977)](https://archive.org/details/TNM_Versatec_printers_and_plotters_-_Versatec_a_X_20180227_0009)
- [Versatec Printer/Plotters, Plotters and Output Systems (1981)](https://archive.org/details/TNM_Printer-plotters_plotters_and_output_systems__20171113_0057)
- [Roland Users Group Volume 2 Number 4 (1984)](https://archive.org/details/RolandUsersGroupVolume2Number41984/page/n39/mode/2up) - _Computers and Plotters Take the Place of Drafting Tables and Pencils_ article on page 36 (PDF page 40).
- [Omega-t Systems FasPlot Plotter Brochure](https://archive.org/details/TNM_Omega-t_Systems_-_FasPlot_Plotter_20170630_0254)
- [Commodore Computer Plotter CBM 8075 Brochure (German)](https://archive.org/details/Plotter_CBM8075_198x_Commodore_DE)
- [Strobe Model 100 Graphics Plotter Brochure (1980)](https://archive.org/details/TNM_Strope_Model_100_graphics_plotter_-_Strobe_In_20180506_0009)
- [Roland DG Plotter Ad in Byte Magazine Vol 12 No 4 (1987)](https://archive.org/details/byte-magazine-1987-04/page/n159/mode/2up) ([via @OldTechAdverts](https://twitter.com/OldTechAdverts/status/1454558415355850755))
- [Auerbach On Digital Plotters And Image Digitizers (1972)](https://archive.org/details/auerbachondigitalplottersandimagedigitizers) - A book about plotters and digitizers.
- [CalComp Graphics Products Brochure (1981)](https://archive.org/details/TNM_CalComp_graphics_products_plotters_and_printe_20171101_0032)
- [CalComp Plotters in 1968](https://www.youtube.com/watch?v=AAc4VLR6-Dg) - Promotional video showing a flatbed CalComp plotter and its output.
- [Houston Instrument DMP-41 and DMP-42 Plotters Brochure](https://archive.org/details/hi-dmp-41-42-brochure)
- [Houston Instrument DMP-51/52 Series Brochure](https://archive.org/details/hi-dmp-51-52-brochure)
- [Houston Instrument Omnigraphic Plotter Brochure](https://archive.org/details/TNM_Omnigraphic_Plotter_20171016_0228)
- [Sweet-P Plotter Brochure and Price List](https://archive.org/details/bitsavers_enterCompuersonalPlotterprricelistBrochure_4929854) – Four-page color marketing brochure with attached suggested retail price list.
- [IEEE Electronic Systems News Autumn (1985)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=5345111) – Review of the three-color Penman robotic plotter.
- [Apple II Business Graphics Film (1982)](https://archive.org/details/apple-ii-business-graphics) – There's a Strobe Model 100 Graphics Plotter drawing bar charts at 4:57.
- [Elektor Magazine Selbstbauplotter MONDRIAN II (1990) (German)](https://archive.org/details/elektor_202310) – Also see [a model of this plotter on GrabCAD](https://grabcad.com/library/plotter-mondrian-1).

### Papers

- [Toward Aesthetic Guidelines for Paintings with the Aid of a Computer (1975) (PDF)](https://rednoise.org/softas/uploads/molnar.pdf) – Vera Molnar
- [Pen Plotter as a Low-Cost Platform for Rapid Device Prototyping with Solution-Processable Nanomaterials (2023) (PDF)](https://onlinelibrary.wiley.com/doi/pdf/10.1002/adem.202300226)
- [Preparation of V2O5 Thin Film by Sol–Gel Technique and Pen Plotter Printing](https://www.proquest.com/docview/2791602751)
- [PatternPortrait: Draw Me Like One of Your Scribbles (2024)](https://arxiv.org/abs/2401.13001)
- [Can I teach a robot to replicate a line art (2019)](https://arxiv.org/abs/1910.07860)

### Patents

- [Adaptor for universal X-Y plotter pen](https://patents.google.com/patent/US4943817)

## Community

Where to find other plotter and drawbot friends.

- [PlotterArt Subreddit](https://www.reddit.com/r/PlotterArt)
- [AxiDraw Subreddit](https://www.reddit.com/r/axidraw)
- [Generative Art Subreddit](https://www.reddit.com/r/generative)
- [Plotter People](https://plotterpeople.github.io/) - In-person meetups (SF and NYC so far) with talks and plotter art galleries.
- [DrawingBots Discord Forum](https://discordapp.com/invite/XHP3dBg) - Discord forum with an active community.
- [PlotterFiles](https://plotterfiles.com/) - Community for sharing SVG files for plotters.
- #PenPlotter - Mastodon/ActivityPub hashtag that plotter folks are mostly congregating under.

## Plotter Art For Sale

- [Paul Rickards](https://shop.paulrickards.com)
- [Michael Fogleman](https://www.michaelfogleman.com/plotter)
- [inconvergent](http://buy.inconvergent.net)
- [Monica Rizzolli](https://www.saatchiart.com/account/artworks/155196)
- [EmergentDesign](https://emergentdesign.bigcartel.com/products)
- [BustBright](https://mkt.com/bustbright)
- [Martin O'Leary](https://shop.mewo2.com)
- [Geoffrey Bradway](https://www.chromatocosmos.com/)
- [brubsby](http://shop.brubsby.com/)
- [Arjan van der Meij](https://dutchplottr.nl/en/)
- [Nadieh Bremer](https://shop.visualcinnamon.com/collections/pen-plotter-prints)
- [Michelle Chandra](https://www.dirtalleydesign.com/)
- [Pedro Alcocer](https://store.pedroalcocer.com/)
- [AndyMakes](https://shop.andymakes.com/)
- [Marcel Schwittlick](https://schwittlick.bigcartel.com/)
- [Adam Fuhrer](https://adamfuhrer.bigcartel.com)
- [Ingrid Burrington](https://wares.lifewinning.com)

## Other Awesomes

- [awesome-generative-art](https://github.com/kosmos/awesome-generative-art)
- [awesome-creative-coding](https://github.com/terkelg/awesome-creative-coding)
- [awesome-3d-engines-for-plotters](https://github.com/msurguy/awesome-3d-engines-for-plotters)
