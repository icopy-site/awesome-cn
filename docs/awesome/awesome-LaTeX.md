## Awesome LaTeX [![Awesome][awesome]](https://github.com/sindresorhus/awesome) [![Issue Count](https://codeclimate.com/github/egeerardyn/awesome-LaTeX/badges/issue_count.svg)](https://codeclimate.com/github/egeerardyn/awesome-LaTeX) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg?style=flat)](https://github.com/egeerardyn/awesome-LaTeX/blob/master/LICENSE.md)

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/92/LaTeX_logo.svg/220px-LaTeX_logo.svg.png" align="right" width="100">](https://www.latex-project.org/)

&gt;这是一个精选的东西的精选列表 [(La)TeX typesetting system](https://www.latex-project.org/).

## Contents

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Contents](#contents)
- [Distributions](#distributions)
- [Engines](#engines)
	- [LaTeX formulas on the web](#latex-formulas-on-the-web)
- [Editors](#editors)
	- [LaTeX-focused](#latex-focused)
	- [General purpose text editors](#general-purpose-text-editors)
	- [Online editors](#online-editors)
- [Bibliography tools](#bibliography-tools)
- [Build Tools](#build-tools)
- [Misc. Tools](#misc-tools)
- [LaTeX-compatible GUI tools](#latex-compatible-gui-tools)
- [Packages](#packages)
	- [Tables](#tables)
	- [Graphics](#graphics)
		- [PSTricks](#pstricks)
		- [TikZ](#tikz)
	- [Source Code](#source-code)
	- [Typography](#typography)
- [Templates](#templates)
- [Symbols](#symbols)
- [Resources](#resources)
- [Showcases](#showcases)
- [Tutorials](#tutorials)
- [Books](#books)
- [Blogs](#blogs)
- [Social media](#social-media)
- [Meta Awesome-LaTeX](#meta-awesome-latex)
- [Legend](#legend)

<!-- /TOC -->

## Distributions

- [MacTeX](https://tug.org/mactex/)   - 最常见的Mac OS X LaTeX发行版，基本上是TeXLive，添加了一些特定于Mac的工具.  ！[苹果] [苹果]
- [TeX Live](https://www.tug.org/texlive/)   - 用于类Unix操作系统的最常见的LaTeX发行版，包括GNU / Linux.  也适用于Windows.  ！[Linux] [linux]！[Windows] [windows]
- [MikTeX](https://miktex.org)   - 最常见的Windows LaTeX发行版（仅限）.  ！[窗口] [窗口]

## Engines

- [pdfTeX](https://www.tug.org/applications/pdftex/)   - 立即生成PDF文件而不是DVI文件的TeX编译器（现在，这是许多用户的标准编译器）.  ！[源码] [源码]
- [XeTeX](http://xetex.sourceforge.net)   -  TeX编译器提供比TeX / pdfTeX更好的unicode和字体支持（即您可以使用操作系统的字体而不是仅使用TeX字体）.  ！[源码] [源码]
- [LuaTeX](http://www.luatex.org)   - （La）TeX编译器，支持用于编写脚本的Lua代码，并且比标准TeX / pdfTeX改进了unicode和字体支持.  ！[源码] [源码]

### LaTeX formulas on the web

- [Auto-LaTeX Equations with Google Docs](https://sites.google.com/site/autolatexequations) - 直接在Google Docs中渲染高质量的数学方程式.
- [MathJaX](https://www.mathjax.org)   - 用于在Web上呈现数学公式的JavaScript引擎.  结果看起来很光滑.  ！[源码] [源码]
- [mimeTeX](http://www.forkosh.com/mimetex.html)   -  mimeTeX是一个相当古老的工具，可以将LaTeX公式渲染为您网站的PNG图形，而无需在您的服务器上实际安装LaTeX.  ！[源码] [源码]
- [mathTeX](http://www.forkosh.com/mathtex.html)   -  mathTeX是mimeTeX的继承者：它产生更好看的图像，但它需要在你的服务器上安装LaTeX.  ！[源码] [源码]
- [KaTeX](https://khan.github.io/KaTeX/)   -  KaTeX是由可汗学院制作的数学渲染库，专注于快速加载时间.  所有输出都作为纯HTML而不是固定图像处理.  ！[源码] [源码]

## Editors

因为用记事本编辑LaTeX代码并不是很棒.
那里有很多编辑，下面是最棒的编辑.
收集完整的LaTeX编辑器列表 [tex.stackexchange.com](https://tex.stackexchange.com/) 如 [big list of LaTeX Editors/IDEs](https://tex.stackexchange.com/q/339/9075).

- [List of popular LaTeX editors](https://tex.stackexchange.com/questions/339/latex-editors-ides) - 社区维护的流行LaTeX编辑器列表，包括屏幕截图和简短描述.

### LaTeX-focused

一些最棒的LaTeX编辑器就是这样做的：编辑LaTeX.

- [Kile](https://kile.sourceforge.io)   - 最初来自Linux / KDE社区的Great LaTeX编辑器.  它在Windows和OS X上运行良好.  ！[源码] [源码]
- [TeXMaker](http://www.xm1math.net/texmaker/) - 非常好的替代Kile.
- [TeXStudio](https://www.texstudio.org) - 源自TeXMaker的跨平台LaTeX编辑器.
- [WinEdt](http://www.winedt.com)   -  LaTeX编辑很多人发誓.  仅适用于！[Windows] [windows].
- [TeXnicCenter](http://www.texniccenter.org)   - 很老但是免费且体面的LaTeX编辑器.  ！[窗口] [窗口]
- [LyX](https://www.lyx.org)   - 跨平台WYSIWYM编辑器，在后台使用LaTeX渲染文档.  ！[源码] [源码]
- [TeXShop](http://pages.uoregon.edu/koch/texshop/)   - 包含在MacTeX中的LaTeX文档的严肃编辑器.  ！[苹果] [苹果]
- [TeXWorks](https://www.tug.org/texworks/)   - 以TeXShop为模型的LaTeX代码的严肃编辑器，但这个是跨平台的.  ！[源码] [源码]
- [BakomaTex](http://www.bakoma-tex.com) - 商业LaTeX编辑器，允许使用其源代码和WYSIWYG编辑您的文档.
- [Inlage](http://www.inlage.com/home)   - 商业LaTeX编辑器，具有手写公式识别，Excel导入和更多漂亮的功能.  ！[窗口] [窗口]
- [Texpad](https://www.texpadapp.com)   - 适用于OS X和iOS的商业LaTeX编辑器，具有出色的功能（文档概述，同步PDF显示，自动完成，跨设备同步......），从不妨碍编写.  ！[苹果] [苹果]

### General purpose text editors

这些编辑不是一招的小马：当然，他们编辑LaTeX，但他们可以做更多！

- [Atom](https://atom.io) [！[Atom] [awesome]]（https://github.com/mehcode/awesome-atom）！[foss] [foss]
	- [LaTeXTools](https://atom.io/packages/latextools)   - 同名的Sublime Text包的Atom端口.  ！[源码] [源码]

- [Sublime Text](https://www.sublimetext.com) [！[Sublime Text] [awesome]]（https://github.com/dreikanter/sublime-bookmarks）
	- [LaTeXing](http://www.latexing.com) - 用于编辑LaTeX的商业插件.
	- [LaTeXTools](https://github.com/SublimeText/LaTeXTools)   -  Sublime Text的免费LaTeX插件.  ！[源码] [源码]

- [Emacs](https://www.gnu.org/software/emacs/)  [！[Emacs] [awesome]]（https://github.com/emacs-tw/awesome-emacs）！[foss] [foss]
	- [AucTeX](https://www.gnu.org/software/auctex/)   - 用于LaTeX的Emacs插件，还显示了方程式和数字的预览.  ！[源码] [源码]
	- [RefTeX](https://www.gnu.org/software/auctex/reftex)   - 用于LaTeX的Emacs插件，增加了对标签，引用和引用的支持.  ！[源码] [源码]

- [Vim](http://www.vim.org) [！[Vim] [awesome]]（https://github.com/mhinz/vim-galore）！[foss] [foss]
	- [Vim-LaTeX](http://vim-latex.sourceforge.net) [瀑布] [瀑布]
	- [LaTeX Live Preview](https://github.com/xuhdev/vim-latex-live-preview)   - 即时预览您的LaTeX文档.  ！[源码] [源码]
	- [vimtex](https://github.com/lervag/vimtex)   - 用于编辑LaTeX文件的现代vim插件.  具有多种功能，包括实时预览和前向搜索.  ！[源码] [源码]

- [IntelliJ](https://www.jetbrains.com/idea/)
	- [TeXiFy-IDEA](https://github.com/Ruben-Sten/TeXiFy-IDEA)   -  IntelliJ IDEA的免费LaTeX插件.  ！[源码] [源码]

- [VS Code](https://code.visualstudio.com/) [！[VS Code] [awesome]]（https://github.com/viatsko/awesome-vscode）！[foss] [foss]
	- [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) -  Visual Studio Code的LaTeX扩展！[foss] [foss]

### Online editors

在线编辑器，允许您协作编辑文档.

- [List of popular online LaTeX editors](https://tex.stackexchange.com/questions/3/compiling-documents-online/1654#1654) - 社区维护的流行在线LaTeX编辑器列表，包括方程式编辑器.
- [Authorea](https://www.authorea.com) - 在线编辑器，内置git支持和参考书目工具.
- [ShareLaTeX](https://www.sharelatex.com) - 具有非常棒的LaTeX文档和简单的版本控制.
- [Overleaf](https://www.overleaf.com) - 在线编辑器，还有WYSIWYM编辑器和git支持.
- [Papeeria](https://papeeria.com) - 内置git支持的在线编辑器.
- [JaxEdit](https://zohooo.github.io/jaxedit/) - 具有实时预览和漂亮演示模式的在线LaTeX编辑器.

## Bibliography tools

- [JabRef](https://www.jabref.org)   - 非常强大的跨平台（Java）bibtex编辑器.  但是，GUI看起来很陈旧.  ！[Mac] [mac]！[Windows] [windows]！[Linux] [linux]！[foss] [foss]
- [Papis](https://github.com/alejandrogallo/papis) - 极易定制，
   功能强大且简单的跨平台（Python）库管理器.  它有一个非常
  完整的命令行界面，多个GUI和脚本功能.
  ！[Linux] [linux]！[Mac] [mac]！[foss] [foss]
- [Bibdesk](http://bibdesk.sourceforge.net) - 伟大的书目编辑器！[Mac] [mac].
- [Zotero](https://www.zotero.org)   - 您的浏览器的参考管理器，也可以导出到bibtex并与许多LaTeX编辑器集成.  ！[Mac] [mac]！[Windows] [windows]！[Linux] [linux] [！[foss] [foss]]（https://github.com/zotero/）
- [Mendeley](https://www.mendeley.com)   - 应用程序和云客户端都可以管理您的参考和PDF.  可以同步到您的LaTeX工作流程的bibtex文件.  ！[Mac] [mac]！[Windows] [windows]！[Linux] [linux]

## Build Tools

Compiling LaTeX documents can be tedious, build tools help you to manage the compilation process.

- [Arara](https://www.ctan.org/pkg/arara) ([GitHub repo](https://github.com/cereda/arara) ） - 简单的工具，允许您指定在文档中调用哪些工具，并且可以非常轻松地扩展.  ！[源码] [源码]
- [latexmk](https://www.ctan.org/pkg/latexmk)   - 构建工具，这是许多LaTeX编辑器（LaTeXing，TeXShop，...）常用来构建LaTeX文件.  ！[源码] [源码]
- [latex-makefile](https://github.com/alejandrogallo/latex-makefile)   - 基于`Makefile`的构建工具，试图尽可能通用和轻量级.  ！[源码] [源码]

## Misc. Tools

- [CaTeX](https://github.com/Alexis-benoist/CaTeX) - 注意连接LaTeX文档以正确合并前导码.
- [Pandoc](https://pandoc.org)   - 该程序几乎可以将任何文档格式（LaTeX，DOC，markdown，...）转换为几乎任何其他格式.  一个很好的工具，可以帮助使用多种格式的工作流程.  ！[源码] [源码]
- [Codecogs Eqn Editor](https://www.codecogs.com/latex/eqneditor.php) - 在线LaTeX公式编辑器，允许您生成包含方程的数字.
- [LaTeXiT](https://www.chachatelier.fr/latexit/)   -  LaTeXit是一个方程编辑器，可以轻松地将渲染的方程式（如PDF，PNG，...）拖放到Mac上的非LaTeX文档中.  ！[苹果] [苹果]
- [KLaTeXFormula](https://klatexformula.sourceforge.io)   -  LaTeXit的跨平台替代方案.  ！[源码] [源码]
- [EqualX](http://equalx.sourceforge.net)   - 图形LaTeX公式编辑器.  ！[Windows] [windows]！[Linux] [linux]！[foss] [foss]
- [ChkTeX](http://baruch.ev-en.org/proj/chktex/)   -  LaTeX文档的Linter / code checker.  ！[源码] [源码]
- [LaTeXEqEdit](http://latexeqedit.sourceforge.net/index.php)   - 适用于Windows的LaTeX公式编辑器.  ！[Windows] [windows]！[foss] [foss]
- [Laeqed](https://www.thrysoee.dk/laeqed/) - Crossplatform LaTeX formula to PNG convertor. ![Windows][windows] ![Linux][linux] ![Mac][mac] ![foss][foss]

## LaTeX-compatible GUI tools

- [TikzEdt](http://www.tikzedt.org) （也：  [GitHub repo](https://github.com/hchapman/tikzedt) ） -  WIKIWYG和TikZ图片的基于文本的编辑器.  ！[源码] [源码]
- [TikZ-Editor](https://github.com/fredokun/TikZ-Editor)   -  TikZ数字的实时预览编辑器.  ！[Mac] [Mac]！[Linux] [Linux]！[foss] [foss]
- [IPE](http://ipe.otfried.org)   - 与LaTeX命令和文档完美集成的绘图工具.  ！[源码] [源码]
- [GeoGebra](https://www.geogebra.org/cms/)   - 跨平台几何工具，输出到TikZ.  ！[源码] [源码]
- [Dia](https://wiki.gnome.org/Apps/Dia)   - 跨平台图表工具，可以导出到PSTricks和MetaPost代码.  ！[源码] [源码]

## Packages

- [CTAN](https://www.ctan.org) - 全面的TeX存档网络是寻找有用的包和文档的地方.

### References

- [Cross-reference packages explained](https://tex.stackexchange.com/a/36312/9075) - 详细介绍交叉引用包（cleveref，varioref，theoremref，nameref，...）：哪个使用，哪个冲突？

### Tables

- [Excel2LaTeX](https://www.ctan.org/pkg/excel2latex?lang=en)   -  Excel（2010及更早版本）宏来生成LaTeX`表格式代码.  ！[Windows] [windows]！[Mac] [mac]
- [csv2latex](http://freshmeat.sourceforge.net/projects/csv2latex)   - 将CSV文件从您喜欢的程序转换为LaTeX`表格.  ！[Linux] [linux]！[Mac] [mac]
- [Tables Generator](https://www.tablesgenerator.com) - 该网站提供了一个图形界面来输入您的表格，并为LaTeX，Markdown，HTML等生成格式正确的代码.
- [pgfplotstable](https://www.ctan.org/pkg/pgfplotstable?lang=en)   - 此包显示以各种显示格式四舍五入到所需精度的数字表.  它甚至可以读取CSV文件以直接包含在LaTeX文档中.

### Graphics

#### PSTricks

PSTricks是一个很棒的库，用于绘制包含在PostScript / DVI文件中的数字.

#### TikZ

TikZ是一个很棒的包，有许多插件，允许您从LaTeX文档中创建数字.
通常，使用`pdflatex`比使用PSTricks更容易.

- [TeXample](http://www.texample.net) - 关于LaTeX的博客，收集了大量的TikZ数据.
- [LaTeX en SI](https://sciences-indus-cpge.papanicola.info/-LaTeX-en-SI-)   - 使用TikZ绘制特殊图表（Bode，Nyquist，电子原理图，块原理图......）的有用网站.  请注意，一切都是法语.
- [tkz](http://altermundus.com/pages/tkz/index.html) - 收集基于TikZ的包以绘制图表和图表.
- [pgfplots](http://pgfplots.sourceforge.net)   - 真正令人敬畏的绘图库在TikZ / pgf的顶部和风格.  该库可以加载CSV数据文件，执行一些计算并创建漂亮的图.
- [A very minimal introduction to TikZ (PDF)](https://cremeronline.com/LaTeX/minimaltikz.pdf) - 由JacquesCrémer撰写的关于TikZ世界的简短介绍性文件.
- [PetarV-/TikZ](https://github.com/PetarV-/TikZ) - 由PetarVeličković收集出版物就绪的PGF / TikZ数据.

### Source Code

- [minted](https://www.ctan.org/pkg/minted) - 铸造包使用 [pygments](http://pygments.org/)  生成列表.  通过这种方式，LaTeX能够格式化300多种编程和标记语言以及其他文本格式.

### Typography

- [microtype](https://ctan.org/pkg/microtype) - 此软件包通过启用边距字距调整和字体扩展来改善文档的外观.

## Templates

- [LaTeX templates](https://www.latextemplates.com) - 为LaTeX收集论文，海报，简历，论文，书籍，演示文稿等模板.
- [Ultimate Beamer Theme List](https://github.com/martinbjeldbak/ultimate-beamer-theme-list) - 链接到各种beamer主题以及PDF预览.

## Symbols

- [Comprehensive LaTeX symbol list](https://www.ctan.org/tex-archive/info/symbols/comprehensive/)   - 非常广泛的LaTeX符号列表.  可用 [A4](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-a4.pdf) 和 [letter](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-letter.pdf) 大小.
- [Detexify](http://detexify.kirelabs.org/classify.html) - 您绘制符号，此站点/应用程序将告诉您LaTeX命令.

## Resources

- [TUG](https://www.tug.org) -  TeX用户组是与其他（La）TeX用户联系的一种方式.
- [TeXDoc](http://texdoc.net) - “texdoc”实用程序的在线界面，用于浏览LaTeX软件包和文档.
- [Dickimaw Books: LaTeX resources](http://www.dickimaw-books.com/latexresources.html) - 对LaTeX有用的资源的概述.
- [LaTeX cookbook](http://latex-cookbook.net) -  TeXample的兄弟姐妹，包含相当多的示例代码.
- [Visual FAQ](http://mirrors.ctan.org/info/visualFAQ/visualFAQ.pdf) - 排版问题以及指向相应TeX FAQ答案的链接.
- [MartinThoma's LaTeX example](https://github.com/MartinThoma/LaTeX-examples/) - 包含示例LaTeX文档的GitHub存储库.
- [MacTeX Wiki: TeX Extras](http://mactex-wiki.tug.org/wiki/index.php/TeX_Extras)   -  LaTeX的有用工具概述.  其中许多都是针对Mac的，但对其他平台也很有用.
- [LaTeX community](http://latex.org/index.php) - 关于LaTeX的论坛和博客.
- 德语： [Neue TeX FAQ](https://texfragen.de) - 德语现代和更新的LaTeX常见问题解答.
- [BibTeX Style Examples](http://www.cs.stir.ac.uk/~kjt/software/latex/showbst.html) - 常见BibTeX样式（BST文件）的示例输出.
- [TeX World](http://tex.world/) -  TeX用户组，DANTE和GUTenberg支持的网站.

## Showcases

- [Showcase of beautiful typography done in TeX & friends](https://tex.stackexchange.com/questions/1319/showcase-of-beautiful-typography-done-in-tex-friends) - 一系列展示LaTeX力量的例子.
- [Showcase of beautiful invitations in TeX](https://tex.stackexchange.com/q/281415/9075) - 展示使用LaTeX排版的邀请.
- [Showcase of "programming your document" paradigm](https://tex.stackexchange.com/q/219774/9075) - 收集LaTeX文档，演示如何像编程语言一样使用LaTeX.
- [TUG: TeX showcase](https://www.tug.org/texshowcase/) - 来自TUG的网站，展示了一些LaTeX可以做什么的例子.

## Tutorials

- [The (Not So) Short Introduction to LaTeX2e](http://mirrors.ctan.org/info/lshort/english/lshort.pdf) - 非常全面的LaTeX介绍.
- [Begin LaTeX in minutes](https://github.com/LewisVo/Begin-Latex-in-minutes) - 为初学者简要介绍LaTeX，帮助您轻松使用LaTeX.
- [Getting to Grips with LaTeX](https://www.andy-roberts.net/writing/latex) - 完整指南，了解您需要了解的有关LaTeX的大部分内容.
- [LaTeX introductions in languages other than English](https://tex.stackexchange.com/questions/84384/latex-introductions-in-languages-other-than-english/84385) - 收集多种语言的介绍.

## Books

- [Wikibooks: LaTeX](https://en.wikibooks.org/wiki/LaTeX)   -  LaTeX wikibook.  不是纸质书，但同样广泛.
- [The LaTeX Companion, F. Mittelbach (2004)](https://www.informit.com/store/latex-companion-9780201362992)
- [LaTeX Graphics Companion, M. Goossens (2007)](https://www.informit.com/store/latex-graphics-companion-9780321508928)

## Blogs

- [TeXblog](http://texblog.net) - 关于LaTeX的博客和相关的一切.
- [texblog.org](https://texblog.org) - 关于LaTeX和相关主题的博客（教程，软件包，代码片段等）.
- [TeX Talk](http://tex-talk.net) -  TeX Stack Exchange网站的博客，包括新闻和采访.

## Social media

- [LinkedIn: TeX/LaTeX User Group](https://www.linkedin.com/groups/1600297)
- [Twitter: @TeXtip](https://twitter.com/TeXtip) - 与（La）TeX相关的提示 [John D. Cook](https://www.johndcook.com/).
- [TeX.StackExchange](https://tex.stackexchange.com) -  StackExchange TeX部分.

---------------------------------------------------------------------------

<!-- Icons -->

## Meta Awesome-LaTeX

如果您想贡献，请阅读我们 [CONTRIBUTING](https://github.com/egeerardyn/awesome-LaTeX/blob/master/CONTRIBUTING.md) 准则.

## Legend

 表示Mac，Linux和Windows兼容性的图标显示程序* *仅适用于这些平台.  因此缺少这些图标意味着该软件完全是跨平台的.

 |  标志|  说明|
|:-------------------:|:-------------------------------------------------------|
 |  ！[Mac] [mac] | [Mac OS X](https://www.apple.com/osx/)                 |
 |  ！[Linux] [linux] | [GNU/Linux](https://www.gnu.org)                       |
 |  ！[Windows] [windows] | [Microsoft Windows](https://www.microsoft.com/windows) |
 |  ！[FOSS] [FOSS] | [Free Open-Source Software](https://opensource.org)    |

---------------------------------------------------------------------------

所有商标均为其各自所有者的财产.

[mac]：https：//cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/apple.svg
[linux]：https：//cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/linux.svg
[windows]：https：//cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/windows.svg
[foss]：https：//cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/foss.svg
[awesome]：https：//cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
