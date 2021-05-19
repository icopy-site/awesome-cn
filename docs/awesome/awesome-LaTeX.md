<div class="github-widget" data-repo="egeerardyn/awesome-LaTeX"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome LaTeX [![awesome]](https://github.com/sindresorhus/awesome) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg?style=flat)](https://github.com/egeerardyn/awesome-LaTeX/blob/master/LICENSE.md)

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/92/LaTeX_logo.svg/220px-LaTeX_logo.svg.png" align="right" width="100">](https://www.latex-project.org/)

&gt;这是精选的很棒的东西的清单 [(La)TeX typesetting system](https://www.latex-project.org/).


<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->


<!-- /TOC -->

## Learning LaTeX

指导如何学习LaTeX

- [learnlatex.GitHub.io](https://learnlatex.GitHub.io/) -基于浏览器的LaTeX教程.

## Distributions

- [MacTeX](https://tug.org/mactex/)  -最常见的macOS LaTeX发行版，基本上是TeXLive，其中添加了一些Mac专用工具.  ！[苹果电脑]
- [TeX Live](https://www.tug.org/texlive/)  -最常见的LaTeX发行版，用于类似Unix的操作系统，包括GNU / Linux. 在Windows上也可以使用.  ！[linux]！[windows]
- [MikTeX](https://miktex.org)  -适用于Windows的最常见的LaTeX发行版（仅）.  ！[视窗]

## Engines

- [pdfTeX](https://www.tug.org/applications/pdftex/)  -TeX编译器可立即生成PDF文件而不是DVI文件（如今，这是许多用户的标准编译器）.  ！[foss]
- [XeTeX](http://xetex.sourceforge.net)  -TeX编译器比TeX / pdfTeX提供更好的unicode和字体支持（即，您可以使用操作系统的字体，而不仅仅是TeX字体）.  ！[foss]
- [LuaTeX](http://www.luatex.org)  -（La）TeX编译器，它支持Lua代码进行脚本编写，并且比标准TeX / pdfTeX改进了对unicode和字体的支持.  ！[foss]
- [tectonic](https://tectonic-typesetting.GitHub.io/en-US/)  -由XeTeX和TeXLive提供支持的现代自包含（La）TeX编译器.  ！[foss]

### LaTeX formulas on the web

- [Auto-LaTeX Equations with Google Docs](https://sites.google.com/site/autolatexequations) -直接在Google文档中渲染高质量的数学方程式.
- [MathJaX](https://www.mathjax.org)  -JavaScript引擎可在网络上呈现数学公式. 结果看起来真的很圆滑.  ！[foss]
- [mimeTeX](https://ctan.org/pkg/mimetex)  -mimeTeX是一个相当老的工具，用于将LaTeX公式转换为您的网站的PNG数字，而实际上不需要在服务器上安装LaTeX.  ！[foss]
- [mathTeX](https://ctan.org/pkg/mathtex)  -mathTeX是mimeTeX的后继产品：它可以生成美观的图像，但需要在服务器上安装LaTeX.  ！[foss]
- [KaTeX](https://khan.GitHub.io/KaTeX/)  -KaTeX是可汗学院（Khan Academy）制作的数学渲染库，着重于快速加载时间. 所有输出均以纯HTML格式处理，而不是固定图像.  ！[foss]
- [Franklin.jl](https://franklinjl.org/)  -在Julia中，具有KaTeX支持，代码评估，类似于LaTeX的命令和可选的预渲染的静态站点生成器.  ！[foss]
- [Purple Pi](https://github.com/nschloe/purple-pi) -浏览器扩展程序，可让您在GitHub页面，StackOverflow等中使用LaTeX.

## Editors

因为用记事本编辑LaTeX代码并不好.
There are many editors out there, below are the most awesome editors.
LaTeX编辑器的完整列表在以下位置收集 [tex.stackexchange.com](https://tex.stackexchange.com/) 作为 [big list of LaTeX Editors/IDEs](https://tex.stackexchange.com/q/339/9075).

- [List of popular LaTeX editors](https://tex.stackexchange.com/questions/339/latex-editors-ides) -社区维护的流行LaTeX编辑器列表，包括屏幕截图和简短描述.

### LaTeX-focused

一些LaTeX最出色的编辑器就是这样做的：编辑LaTeX.

- [Kile](https://kile.sourceforge.io)  -伟大的LaTeX编辑器，最初来自Linux / KDE社区. 它也可以在Windows和macOS上正常运行.  ！[foss]
- [TeXMaker](http://www.xm1math.net/texmaker/) -Kile的不错替代品.
- [TeXStudio](https://www.texstudio.org) -源自TeXMaker的跨平台LaTeX编辑器.
- [WinEdt](http://www.winedt.com)  -许多人发誓的LaTeX编辑器. 仅适用于！[windows].
- [TeXnicCenter](http://www.texniccenter.org)  -相当老但免费又不错的LaTeX编辑器.  ！[视窗]
- [LyX](https://www.lyx.org)  -跨平台的所见即所得编辑器，该编辑器在后台使用LaTeX渲染文档.  ！[foss]
- [TeXShop](http://pages.uoregon.edu/koch/texshop/)  -MacTeX中包含的LaTeX文档的精简编辑器.  ！[苹果电脑]
- [TeXWorks](https://www.tug.org/texworks/)  -LaTeX代码的精巧编辑器，以TeXShop为模型，但该编辑器是跨平台的.  ！[foss]
- [BakomaTex](http://www.bakoma-tex.com) -商业LaTeX编辑器，可使用其源代码和所见即所得来编辑您的文档.
- [Inlage](http://www.inlage.com/home)  -具有手写公式识别，Excel导入和更多精美功能的商业LaTeX编辑器.  ！[视窗]
- [Texpad](https://www.texpadapp.com)  -适用于macOS和iOS的商业LaTeX编辑器，具有出色的功能（文档概述，同步的PDF显示，自动完成，跨设备同步等），这些功能永远不会妨碍编写.  ！[苹果电脑]

### General purpose text editors

这些编辑器绝非小技巧：当然，他们可以编辑LaTeX，但是他们可以做更多的事情！

- [Atom](https://atom.io) [！[Atom] [awesome]]（https://github.com/mehcode/awesome-atom）！[foss]
	- [LaTeXTools](https://atom.io/packages/latextools)  -具有相同名称的Sublime Text软件包的Atom端口.  ！[foss]

- [Sublime Text](https://www.sublimetext.com) [！[Sublime Text] [awesome]]（https://github.com/dreikanter/sublime-bookmarks）
	- [LaTeXing](http://www.latexing.com) -用于编辑LaTeX的商业插件.
	- [LaTeXTools](https://github.com/SublimeText/LaTeXTools)  -用于Sublime Text的免费LaTeX插件.  ！[foss]

- [Emacs](https://www.gnu.org/software/emacs/)  [！[Emacs] [awesome]]（https://github.com/emacs-tw/awesome-emacs）！[foss]
	- [AucTeX](https://www.gnu.org/software/auctex/)  -用于LaTeX的Emacs插件，还显示方程式和图形的预览.  ！[foss]
	- [RefTeX](https://www.gnu.org/software/auctex/reftex)  -LaTeX的Emacs插件，增加了对标签，引用和引用的支持.  ！[foss]

- [Vim](http://www.vim.org) [！[Vim] [awesome]]（https://github.com/mhinz/vim-galore）！[foss]
	- [Vim-LaTeX](http://vim-latex.sourceforge.net) ！[foss]
	- [LaTeX Live Preview](https://github.com/xuhdev/vim-latex-live-preview)  -即时预览您的LaTeX文档.  ！[foss]
	- [vimtex](https://github.com/lervag/vimtex)  -用于编辑LaTeX文件的现代vim插件. 具有多种功能，包括实时预览和前向搜索.  ！[foss]

- [IntelliJ](https://www.jetbrains.com/idea/)
	- [TeXiFy-IDEA](https://github.com/Ruben-Sten/TeXiFy-IDEA)  -IntelliJ IDEA的免费LaTeX插件.  ！[foss]

- [VS Code](https://code.visualstudio.com/) [！[VS Code] [awesome]]（https://github.com/viatsko/awesome-vscode）！[foss]
	- [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) -Visual Studio Code的LaTeX扩展！[foss]

### Online editors

允许您协同编辑文档的在线编辑器.

- [List of popular online LaTeX editors](https://tex.stackexchange.com/questions/3/compiling-documents-online/1654#1654) -社区维护的流行在线LaTeX编辑器（包括方程式编辑器）列表.
- [Authorea](https://www.authorea.com) -具有内置git支持和书目工具的在线编辑器.
- [ShareLaTeX](https://www.sharelatex.com) -拥有出色的LaTeX文档和简单的版本控制.
- [Overleaf](https://www.overleaf.com) -在线编辑器，还具有WYSIWYM编辑器和git支持.
- [Papeeria](https://papeeria.com) -具有内置git支持的在线编辑器.
- [JaxEdit](https://zohooo.GitHub.io/jaxedit/) -具有实时预览和出色演示模式的在线LaTeX编辑器.

## Bibliography tools

- [JabRef](https://www.jabref.org)  -非常强大的跨平台（Java）bibtex编辑器. 但是，GUI看起来已经过时了.  ！[mac]！[windows]！[linux]！[foss]
- [Papis](https://github.com/alejandrogallo/papis) -高度可定制
  功能强大且简单的跨平台（Python）库管理器. 它有一个非常
  完整的命令行界面，多个GUI和脚本功能.
  ！[linux]！[mac]！[foss]
- [Bibdesk](http://bibdesk.sourceforge.net) -伟大的书目编辑器！[mac].
- [Zotero](https://www.zotero.org)  -浏览器的参考管理器，也可以导出到bibtex并与许多LaTeX编辑器集成.  ！[mac]！[windows]！[linux] [！[foss]]（https://github.com/zotero/）
- [Mendeley](https://www.mendeley.com)  -应用程序和云客户端都可以管理您的参考和PDF. 可以同步到LaTeX工作流程的bibtex文件.  ！[mac]！[windows]！[linux]
- [betterbib](https://github.com/nschloe/betterbib)  -用于改进BibTeX文件的命令行实用程序. 从在线来源获取信息.  ！[mac]！[windows]！[linux]！[foss]

## Build Tools

编译LaTeX文档可能很繁琐，构建工具可帮助您管理编译过程.

- [Arara](https://www.ctan.org/pkg/arara) ([GitHub repo](https://github.com/cereda/arara) ）-简单的工具，可让您指定要在文档中调用的工具，并且可以轻松扩展它.  ！[foss]
- [latexmk](https://www.ctan.org/pkg/latexmk)  -许多LaTeX编辑器（LaTeXing，TeXShop等）常用的构建工具来构建LaTeX文件.  ！[foss]
- [latex-makefile](https://github.com/alejandrogallo/latex-makefile)  -基于`Makefile`的构建工具，它试图尽可能地通用和轻巧.  ！[foss]

## Misc. Tools

- [CaTeX](https://github.com/Alexis-benoist/CaTeX) -注意正确地合并LaTeX文档以正确合并前言.
- [Pandoc](https://pandoc.org)  -该程序将几乎所有文档格式（LaTeX，DOC，降价等）转换为几乎任何其他格式. 一个出色的工具，可帮助使用多种格式的工作流程.  ！[foss]
- [Codecogs Eqn Editor](https://www.codecogs.com/latex/eqneditor.php) -在线LaTeX方程编辑器，可让您生成包含方程的图形.
- [LaTeXiT](https://www.chachatelier.fr/latexit/)  -LaTeXit是一个方程式编辑器，可轻松将渲染的方程式（如PDF，PNG等）拖放到Mac上的非LaTeX文档中.  ！[苹果电脑]
- [KLaTeXFormula](https://klatexformula.sourceforge.io)  -LaTeXit的跨平台替代方案.  ！[foss]
- [EqualX](http://equalx.sourceforge.net)  -图形LaTeX公式编辑器.  ！[windows]！[linux]！[foss]
- [ChkTeX](http://baruch.ev-en.org/proj/chktex/)  -用于LaTeX文档的Linter /代码检查器.  ！[foss]
- [LaTeXEqEdit](http://latexeqedit.sourceforge.net/index.php)  -Windows的LaTeX公式编辑器.  ！[windows]！[foss]
- [Laeqed](https://www.thrysoee.dk/laeqed/)  -跨平台LaTeX公式到PNG转换器.  ！[windows]！[linux]！[mac]！[foss]
- [blacktex](https://github.com/nschloe/blacktex)  -命令行工具，可替换常见的LaTeX反模式并清理文件.  ！[windows]！[linux]！[mac]！[foss]

## LaTeX-compatible GUI tools

- [TikzEdt](http://www.tikzedt.org) （还： [GitHub repo](https://github.com/hchapman/tikzedt) ）-所见即所得和基于文本的TikZ图片编辑器.  ！[foss]
- [TikZ-Editor](https://github.com/fredokun/TikZ-Editor)  -TikZ人物的实时预览编辑器.  ！[mac]！[linux]！[foss]
- [IPE](http://ipe.otfried.org)  -可以与LaTeX命令和文档很好地集成的绘图工具.  ！[foss]
- [GeoGebra](https://www.geogebra.org/cms/)  -跨平台几何工具，输出到TikZ.  ！[foss]
- [Dia](https://wiki.gnome.org/Apps/Dia)  -可以导出到PSTricks和MetaPost代码的跨平台图表工具.  ！[foss]
- [TikZiT](https://tikzit.GitHub.io)  -使用PGF / TikZ创建图形和字符串图的GUI工具.  ！[windows]！[linux]！[mac]！[foss]


## Packages

- [CTAN](https://www.ctan.org) -全面的TeX存档网络是寻找有用的软件包和文档的地方.

### References

- [Cross-reference packages explained](https://tex.stackexchange.com/a/36312/9075) -详细说明交叉引用程序包（cleveref，varioref，theoremref，nameref等）：使用哪个，哪个冲突？

### Tables

- [Excel2LaTeX](https://www.ctan.org/pkg/excel2latex?lang=en)  -Excel（2010及更早版本）宏，用于生成LaTeX“表格”代码.  ！[windows]！[mac]
- [csv2latex](http://freshmeat.sourceforge.net/projects/csv2latex)  -将CSV文件从您喜欢的程序转换为LaTeX“表格”文件.  ！[linux]！[mac]
- [Tables Generator](https://www.tablesgenerator.com) -该网站提供了图形界面来输入您的表格，并为LaTeX，Markdown，HTML等生成格式正确的代码.
- [pgfplotstable](https://www.ctan.org/pkg/pgfplotstable?lang=en)  -该软件包以各种显示格式显示数值表，四舍五入到所需的精度. 它甚至可以读取CSV文件以直接包含在您的LaTeX文档中.

### Graphics

#### PSTricks

PSTricks是一个很棒的库，可以绘制图形以包含在PostScript / DVI文件中.

#### TikZ

TikZ是一个很棒的软件包，带有许多插件，可让您从LaTeX文档中创建图形.
通常，使用pdflatex比PSTricks更容易.

- [TeXample](http://www.texample.net) -有关LaTeX的博客，其中包含大量TikZ数据.
- [LaTeX en SI](https://sciences-indus-cpge.papanicola.info/-LaTeX-en-SI-)  -有用的网站，其中包含一些自定义软件包，可以使用TikZ绘制特殊的图（Bode，Nyquist，电气原理图，方框图等）. 请注意，所有内容均为法语.
- [tkz](http://altermundus.com/pages/tkz/index.html) -收集基于TikZ的软件包以绘制图表.
- [pgfplots](http://pgfplots.sourceforge.net)  -在TikZ / pgf的基础上并以TikZ / pgf的样式提供了真正出色的绘图库. 该库可以加载CSV数据文件，执行一些计算并创建漂亮的图.
- [A very minimal introduction to TikZ (PDF)](https://cremeronline.com/LaTeX/minimaltikz.pdf) - Short introductory document to the world of TikZ, written by Jacques Crémer.
- [PetarV-/TikZ](https://github.com/PetarV-/TikZ) -收集由PetarVeličković出版的可用于PGF / TikZ的数字.
- [matlab2tikz](https://github.com/matlab2tikz/matlab2tikz)  -将您的MATLAB图转换为PGFPlots / TikZ.  ！[windows]！[linux]！[mac]！[foss]
- [tikzplotlib](https://github.com/nschloe/tikzplotlib)  -将您的matplotlib图转换为PGFPlots / TikZ.  ！[windows]！[linux]！[mac]！[foss]

### Source Code

- [minted](https://www.ctan.org/pkg/minted) -铸造的包装使用 [pygments](http://pygments.org/) 生成列表. 通过这种方式，LaTeX能够格式化300多种编程和标记语言以及其他文本格式.

### Typography

- [microtype](https://ctan.org/pkg/microtype) -该软件包通过启用页边距紧缩和字体扩展来改善文档的外观.

### Presentations, Slides

- [nics](https://nics.nilcons.com/)  -我们创建了Beamer的自以为是的替代品，希望可以使普通任务变得非常容易并且默认情况下可以精美呈​​现. 拥有出色的文档和详细的备忘单，可帮助您入门.

## Templates

- [LaTeX templates](https://www.latextemplates.com) -用于LaTeX的论文，海报，简历，论文，书籍，演示文稿等模板的集合.
- [Ultimate Beamer Theme List](https://github.com/martinbjeldbak/ultimate-beamer-theme-list) -链接到各种投影仪主题以及PDF预览.

## Symbols

- [Comprehensive LaTeX symbol list](https://www.ctan.org/tex-archive/info/symbols/comprehensive/)  -LaTeX的符号非常详尽的列表. 可用于 [A4](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-a4.pdf) 和 [letter](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-letter.pdf) 大小.
- [Detexify](http://detexify.kirelabs.org/classify.html) -您绘制符号，此站点/应用程序将告诉您LaTeX命令.

## Resources

- [TUG](https://www.tug.org) -TeX用户组是与其他（La）TeX用户保持联系的一种方式.
- [TeXDoc](http://texdoc.net) -texdoc实用程序的在线界面，用于浏览LaTeX软件包和文档.
- [Dickimaw Books: LaTeX resources](http://www.dickimaw-books.com/latexresources.html) -很好地概述了对LaTeX有用的资源.
- [LaTeX cookbook](http://latex-cookbook.net) -TeXample的同级，包含很多示例代码.
- [Visual FAQ](http://mirrors.ctan.org/info/visualFAQ/visualFAQ.pdf) -排版问题，以及指向适当的TeX常见问题解答的链接.
- [MartinThoma's LaTeX example](https://github.com/MartinThoma/LaTeX-examples/) -包含示例LaTeX文档的GitHub存储库.
- [MacTeX Wiki: TeX Extras](http://mactex-wiki.tug.org/wiki/index.php/TeX_Extras)  -LaTeX有用工具的概述. 它们中的许多特定于Mac，但对于其他平台也有很多用处.
- [LaTeX community](http://latex.org/index.php) -有关LaTeX的论坛和博客.
-德语： [Neue TeX FAQ](https://texfragen.de) -现代和更新的德语LaTeX常见问题解答.
- [BibTeX Style Examples](http://www.cs.stir.ac.uk/~kjt/software/latex/showbst.html) -常见BibTeX样式（BST文件）的示例输出.
- [TeX World](http://tex.world/) -由TeX用户组，DANTE和GUTenberg支持的网站.
- [TeXnique](https://texnique.xyz) -LaTeX排版游戏.

## Showcases

- [Showcase of beautiful typography done in TeX & friends](https://tex.stackexchange.com/questions/1319/showcase-of-beautiful-typography-done-in-tex-friends) -展示LaTeX功能的示例集.
- [Showcase of beautiful invitations in TeX](https://tex.stackexchange.com/q/281415/9075) -展示使用LaTeX排版的邀请函.
- [Showcase of "programming your document" paradigm](https://tex.stackexchange.com/q/219774/9075) -收集LaTeX文档，展示如何像编程语言一样使用LaTeX.
- [TUG: TeX showcase](https://www.tug.org/texshowcase/) -来自TUG的网站，显示了LaTeX可以做什么的一些示例.

## Tutorials

- [The (Not So) Short Introduction to LaTeX2e](http://mirrors.ctan.org/info/lshort/english/lshort.pdf) -非常全面的LaTeX简介.
- [Begin LaTeX in minutes](https://github.com/LewisVo/Begin-Latex-in-minutes) -面向初学者的LaTeX简介，可帮助您轻松使用LaTeX.
- [Getting to Grips with LaTeX](https://www.andy-roberts.net/writing/latex) -完整的指南，介绍了您需要了解的有关LaTeX的大多数知识.
- [LaTeX introductions in languages other than English](https://tex.stackexchange.com/questions/84384/latex-introductions-in-languages-other-than-english/84385) -收集多种语言的介绍.

## Books

- [Wikibooks: LaTeX](https://en.wikibooks.org/wiki/LaTeX)  -LaTeX Wikibook. 并不是真正的纸质书，但它同样广泛.
- [The LaTeX Companion, F. Mittelbach (2004)](https://www.informit.com/store/latex-companion-9780201362992)
- [LaTeX Graphics Companion, M. Goossens (2007)](https://www.informit.com/store/latex-graphics-companion-9780321508928)
- [TeX by Topic (2007)](https://ctan.org/pkg/texbytopic)
- [TeX for the Impatient (2020)](https://ctan.org/pkg/impatient)

## Blogs

- [TeXblog](http://texblog.net) -关于LaTeX及其相关内容的博客.
- [texblog.org](https://texblog.org) -有关LaTeX和相关主题（教程，软件包，代码段等）的博客.
- [TeX Talk](http://tex-talk.net) -有关TeX Stack Exchange网站的博客，其中包含新闻和访谈.

## Social media

- [LinkedIn: TeX/LaTeX User Group](https://www.linkedin.com/groups/1600297)
- [Twitter: @TeXtip](https://twitter.com/TeXtip) -有关（La）TeX的提示 [John D. Cook](https://www.johndcook.com/).
- [TeX.StackExchange](https://tex.stackexchange.com) -StackExchange TeX部分.

---

<!-- Icons -->

## Meta Awesome-LaTeX

如果您想贡献，请阅读我们 [CONTRIBUTING](https://github.com/egeerardyn/awesome-LaTeX/blob/master/CONTRIBUTING.md) 准则.

## Legend

指示Mac，Linux和Windows兼容性的图标显示“仅*”程序适用于那些平台. 因此，如果没有这些图标，则表示该软件是完全跨平台的.

 | 徽标| 描述
|:-------------------:|:----------------------------------------------|
 |  ！[mac] | [macOS](https://www.apple.com/osx/)                |
 |  ！[linux] | [GNU/Linux](https://www.gnu.org)                     |
 |  ！[windows] | [Microsoft Windows](https://www.microsoft.com/windows) |
 |  ！[FOSS] | [Free Open-Source Software](https://opensource.org) |

---

所有商标均为其各自所有者的财产.

[mac]：https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/apple.svg
[Linux]：https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/linux.svg
[windows]：https：//cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/windows.svg
[foss]：https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/foss.svg
[很棒]：https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
