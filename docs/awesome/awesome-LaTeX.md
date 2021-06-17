<div class="github-widget" data-repo="egeerardyn/awesome-LaTeX"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome LaTeX [![awesome]](https://github.com/sindresorhus/awesome) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg?style=flat)](https://github.com/egeerardyn/awesome-LaTeX/blob/master/LICENSE.md)

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/92/LaTeX_logo.svg/220px-LaTeX_logo.svg.png" align="right" width="100">](https://www.latex-project.org/)

&gt; 这是一份精选的精彩内容清单 [(La)TeX typesetting system](https://www.latex-project.org/).


<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->


<!-- /TOC -->

## Learning LaTeX

指导如何学习 LaTeX

- [learnlatex.GitHub.io](https://learnlatex.GitHub.io/) - 基于浏览器的 LaTeX 教程.

## Distributions

- [MacTeX](https://tug.org/mactex/)  - 适用于 macOS 的最常见的 LaTeX 发行版，基本上是 TeXLive，并添加了一些 Mac 特定的工具.  ！[苹果电脑]
- [TeX Live](https://www.tug.org/texlive/)  - 最常见的用于类 Unix 操作系统的 LaTeX 发行版，包括 GNU/Linux. 也适用于 Windows.  ![linux] ![windows]
- [MikTeX](https://miktex.org)  - 适用于 Windows 的最常见的 LaTeX 发行版（仅限）.  ！[视窗]

## Engines

- [pdfTeX](https://www.tug.org/applications/pdftex/)  - TeX 编译器可立即生成 PDF 文件而不是 DVI 文件（如今，这是许多用户的标准编译器）.  ！[福斯]
- [XeTeX](http://xetex.sourceforge.net)  - TeX 编译器提供比 TeX/pdfTeX 更好的 unicode 和字体支持（即您可以使用操作系统的字体，而不仅仅是 TeX 字体）.  ！[福斯]
- [LuaTeX](http://www.luatex.org)  - (La)TeX 编译器，支持 Lua 代码编写脚本，比标准 TeX/pdfTeX 改进了 unicode 和字体支持.  ！[福斯]
- [tectonic](https://tectonic-typesetting.GitHub.io/en-US/)  - 由 XeTeX 和 TeXLive 提供支持的现代自包含 (La)TeX 编译器.  ！[福斯]

### LaTeX formulas on the web

- [Auto-LaTeX Equations with Google Docs](https://sites.google.com/site/autolatexequations) - 直接在 Google Docs 中呈现高质量的数学方程.
- [MathJaX](https://www.mathjax.org)  - 用于在网络上呈现数学公式的 JavaScript 引擎. 结果看起来非常光滑.  ！[福斯]
- [mimeTeX](https://ctan.org/pkg/mimetex)  - mimeTeX 是一个相当古老的工具，可以将 LaTeX 公式渲染为您网站的 PNG 图形，而实际上不需要在您的服务器上安装 LaTeX.  ！[福斯]
- [mathTeX](https://ctan.org/pkg/mathtex)  - mathTeX 是 mimeTeX 的继承者：它可以生成更好看的图像，但需要在您的服务器上安装 LaTeX.  ！[福斯]
- [KaTeX](https://khan.GitHub.io/KaTeX/)  - KaTeX 是可汗学院制作的数学渲染库，专注于快速加载时间. 所有输出都被处理为纯 HTML 而不是固定图像.  ！[福斯]
- [Franklin.jl](https://franklinjl.org/)  - 带有 KaTeX 支持、代码评估、类似 LaTeX 的命令和可选的预渲染的静态站点生成器，在 Julia 中.  ！[福斯]
- [Purple Pi](https://github.com/nschloe/purple-pi) - 浏览器扩展，可让您在 GitHub 页面、StackOverflow 等中使用 LaTeX！[foss]

## Editors

因为用记事本编辑 LaTeX 代码并不棒.
有很多编辑器，下面是最棒的编辑器.
A complete list of LaTeX editors is collected at [tex.stackexchange.com](https://tex.stackexchange.com/) 作为 [big list of LaTeX Editors/IDEs](https://tex.stackexchange.com/q/339/9075).

- [List of popular LaTeX editors](https://tex.stackexchange.com/questions/339/latex-editors-ides) - 社区维护的流行 LaTeX 编辑器列表，包括屏幕截图和简短说明.

### LaTeX-focused

一些最棒的 LaTeX 编辑器就是这样做的：编辑 LaTeX.

- [Kile](https://kile.sourceforge.io)  - 出色的 LaTeX 编辑器，最初来自 Linux/KDE 社区. 它也可以在 Windows 和 macOS 上正常运行.  ！[福斯]
- [TeXMaker](http://www.xm1math.net/texmaker/) - 非常好的 Kile 替代品.
- [TeXStudio](https://www.texstudio.org) - 源自 TeXMaker 的跨平台 LaTeX 编辑器.
- [WinEdt](http://www.winedt.com)  - 许多人发誓的 LaTeX 编辑器. 仅适用于 ![windows].
- [TeXnicCenter](http://www.texniccenter.org)  - 相当古老但免费且体面的 LaTeX 编辑器.  ！[视窗]
- [LyX](https://www.lyx.org)  - 跨平台 WYSIWYM 编辑器，在幕后使用 LaTeX 来渲染文档.  ！[福斯]
- [TeXShop](http://pages.uoregon.edu/koch/texshop/)  - 包含在 MacTeX 中的 LaTeX 文档的严肃编辑器.  ！[苹果电脑]
- [TeXWorks](https://www.tug.org/texworks/)  - LaTeX 代码的严肃编辑器，模仿 TeXShop，但这是跨平台的.  ！[福斯]
- [BakomaTex](http://www.bakoma-tex.com) - 商业 LaTeX 编辑器，允许使用其源代码和所见即所得来编辑您的文档.
- [Inlage](http://www.inlage.com/home)  - 具有手写公式识别、Excel 导入和更多漂亮功能的商业 LaTeX 编辑器.  ！[视窗]
- [Texpad](https://www.texpadapp.com)  - 适用于 macOS 和 iOS 的商用 LaTeX 编辑器，具有出色的功能（文档概览、同步 PDF 显示、自动完成、跨设备同步等），永远不会妨碍写作.  ！[苹果电脑]

### General purpose text editors

这些编辑器不是一招式的小马：当然，他们编辑 LaTeX，但他们可以做更多！

- [Atom](https://atom.io) [![Atom][awesome]](https://github.com/mehcode/awesome-atom) ![foss]
	- [LaTeXTools](https://atom.io/packages/latextools)  - 同名 Sublime Text 包的 Atom 端口.  ！[福斯]

- [Sublime Text](https://www.sublimetext.com) [![Sublime Text][awesome]](https://github.com/dreikanter/sublime-bookmarks)
	- [LaTeXing](http://www.latexing.com) - 用于编辑 LaTeX 的商业插件.
	- [LaTeXTools](https://github.com/SublimeText/LaTeXTools)  - Sublime Text 的免费 LaTeX 插件.  ！[福斯]

- [Emacs](https://www.gnu.org/software/emacs/)  [![Emacs][awesome]](https://github.com/emacs-tw/awesome-emacs) ![foss]
	- [AucTeX](https://www.gnu.org/software/auctex/)  - 用于 LaTeX 的 Emacs 插件，还显示方程和图形的预览.  ！[福斯]
	- [RefTeX](https://www.gnu.org/software/auctex/reftex)  - 用于 LaTeX 的 Emacs 插件，增加了对标签、参考文献和引文的支持.  ！[福斯]

- [Vim](http://www.vim.org) [![Vim][awesome]](https://github.com/mhinz/vim-galore) ![foss]
	- [Vim-LaTeX](http://vim-latex.sourceforge.net) ！[福斯]
	- [LaTeX Live Preview](https://github.com/xuhdev/vim-latex-live-preview)  - 即时预览您的 LaTeX 文档.  ！[福斯]
	- [vimtex](https://github.com/lervag/vimtex)  - 用于编辑 LaTeX 文件的现代 vim 插件. 具有多种功能，包括实时预览和前向搜索.  ！[福斯]

- [IntelliJ](https://www.jetbrains.com/idea/)
	- [TeXiFy-IDEA](https://github.com/Ruben-Sten/TeXiFy-IDEA)  - IntelliJ IDEA 的免费 LaTeX 插件.  ！[福斯]

- [VS Code](https://code.visualstudio.com/) [![VS Code][awesome]](https://github.com/viatsko/awesome-vscode) ![foss]
	- [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) - Visual Studio Code 的 LaTeX 扩展！[foss]

### Online editors

允许您协作编辑文档的在线编辑器.

- [List of popular online LaTeX editors](https://tex.stackexchange.com/questions/3/compiling-documents-online/1654#1654) - 社区维护的流行在线 LaTeX 编辑器列表，包括方程编辑器.
- [Authorea](https://www.authorea.com) - 具有内置 git 支持和参考书目工具的在线编辑器.
- [ShareLaTeX](https://www.sharelatex.com) - 有非常棒的 LaTeX 文档和简单的版本控制.
- [Overleaf](https://www.overleaf.com) - 在线编辑器，还带有 WYSIWYM 编辑器和 git 支持.
- [Papeeria](https://papeeria.com) - 内置 git 支持的在线编辑器.
- [JaxEdit](https://zohooo.GitHub.io/jaxedit/) - 具有实时预览和漂亮演示模式的在线 LaTeX 编辑器.

## Bibliography tools

- [JabRef](https://www.jabref.org)  - 非常强大的跨平台 (Java) bibtex 编辑器. 不过，GUI 看起来很陈旧.  ![mac] ![windows] ![linux] ![foss]
- [Papis](https://github.com/alejandrogallo/papis) - 高度可定制，
  强大而简单的跨平台（Python）库管理器. 它有一个很
  完整的命令行界面、多个 GUI 和脚本功能.
  ![linux] ![mac] ![foss]
- [Bibdesk](http://bibdesk.sourceforge.net) - 很棒的书目编辑器！[mac].
- [Zotero](https://www.zotero.org)  - 浏览器的参考管理器，也可以导出到 bibtex 并与许多 LaTeX 编辑器集成.  ![mac] ![windows] ![linux] [![foss]](https://github.com/zotero/)
- [Mendeley](https://www.mendeley.com)  - 应用程序和云客户端来管理您的参考文献和 PDF. 可以同步到您的 LaTeX 工作流程的 bibtex 文件.  ![mac] ![windows] ![linux]
- [betterbib](https://github.com/nschloe/betterbib)  - 用于改进 BibTeX 文件的命令行实用程序. 从在线资源中获取信息.  ![mac] ![windows] ![linux] ![foss]

## Build Tools

编译 LaTeX 文档可能很乏味，构建工具可帮助您管理编译过程.

- [Arara](https://www.ctan.org/pkg/arara) ([GitHub repo](https://github.com/cereda/arara) ) - 简单的工具，允许您指定在文档中调用哪些工具，并且可以很容易地对其进行扩展.  ！[福斯]
- [latexmk](https://www.ctan.org/pkg/latexmk)  - 许多 LaTeX 编辑器（LaTeXing、TeXShop 等）常用的构建工具来构建您的 LaTeX 文件.  ！[福斯]
- [latex-makefile](https://github.com/alejandrogallo/latex-makefile)  - 基于`Makefile` 的构建工具，尝试尽可能通用和轻量级.  ！[福斯]

## Misc. Tools

- [CaTeX](https://github.com/Alexis-benoist/CaTeX) - 连接 LaTeX 文档，注意正确合并序言.
- [Pandoc](https://pandoc.org)  - 该程序几乎可以将任何文档格式（LaTeX、DOC、markdown 等）转换为几乎任何其他格式. 一个很好的工具，可以帮助使用多种格式的工作流程.  ！[福斯]
- [Codecogs Eqn Editor](https://www.codecogs.com/latex/eqneditor.php) - 在线 LaTeX 方程编辑器，可让您生成包含方程的图形.
- [LaTeXiT](https://www.chachatelier.fr/latexit/)  - LaTeXit 是一个方程编辑器，可以轻松地将渲染的方程（如 PDF、PNG 等）拖放到 Mac 上的非 LaTeX 文档中.  ！[苹果电脑]
- [KLaTeXFormula](https://klatexformula.sourceforge.io)  - LaTeXit 的跨平台替代方案.  ！[福斯]
- [EqualX](http://equalx.sourceforge.net)  - 图形化的 LaTeX 公式编辑器.  ![windows] ![linux] ![foss]
- [ChkTeX](http://baruch.ev-en.org/proj/chktex/) - Linter / code checker for LaTeX documents. ![foss]
- [LaTeXEqEdit](http://latexeqedit.sourceforge.net/index.php)  - 适用于 Windows 的 LaTeX 公式编辑器.  ![windows] ![foss]
- [Laeqed](https://www.thrysoee.dk/laeqed/)  - 跨平台 LaTeX 公式到 PNG 转换器.  ![windows] ![linux] ![mac] ![foss]
- [blacktex](https://github.com/nschloe/blacktex)  - 替换常见的 LaTeX 反模式并清理文件的命令行工具.  ![windows] ![linux] ![mac] ![foss]

## LaTeX-compatible GUI tools

- [TikzEdt](http://www.tikzedt.org) （还： [GitHub repo](https://github.com/hchapman/tikzedt) ) - 所见即所得和基于文本的 TikZ 图片编辑器.  ！[福斯]
- [TikZ-Editor](https://github.com/fredokun/TikZ-Editor)  - TikZ 数字的实时预览编辑器.  ![mac] ![linux] ![foss]
- [IPE](http://ipe.otfried.org)  - 与 LaTeX 命令和文档完美集成的绘图工具.  ！[福斯]
- [GeoGebra](https://www.geogebra.org/cms/)  - 具有输出到 TikZ 的跨平台几何工具.  ！[福斯]
- [Dia](https://wiki.gnome.org/Apps/Dia)  - 可以导出到 PSTricks 和 MetaPost 代码的跨平台图表工具.  ！[福斯]
- [TikZiT](https://tikzit.GitHub.io)  - 使用 PGF/TikZ 创建图形和字符串图的 GUI 工具.  ![windows] ![linux] ![mac] ![foss]


## Packages

- [CTAN](https://www.ctan.org) - 综合 TeX Archive Network 是寻找有用包和文档的地方.

### References

- [Cross-reference packages explained](https://tex.stackexchange.com/a/36312/9075) - 详细说明交叉引用包（cleveref、varioref、theoremref、nameref 等）：使用哪个，哪个冲突？

### Tables

- [Excel2LaTeX](https://www.ctan.org/pkg/excel2latex?lang=en)  - Excel（2010 及更早版本）宏来生成 LaTeX `tabular` 代码.  ![windows] ![mac]
- [csv2latex](http://freshmeat.sourceforge.net/projects/csv2latex)  - 将 CSV 文件从您喜欢的程序转换为 LaTeX `tabular`s.  ![linux] ![mac]
- [Tables Generator](https://www.tablesgenerator.com) - 该网站提供了一个图形界面来输入您的表格，并为 LaTeX、Markdown、HTML 等生成格式正确的代码.
- [pgfplotstable](https://www.ctan.org/pkg/pgfplotstable?lang=en)  - 该软件包以各种显示格式显示四舍五入到所需精度的数值表. 它甚至可以读取 CSV 文件以直接包含在您的 LaTeX 文档中.

### Graphics

#### PSTricks

PSTricks 是一个很棒的库，可以绘制包含在 PostScript/DVI 文件中的图形.

#### TikZ

TikZ 是一个非常棒的软件包，其中包含许多插件，可让您从 LaTeX 文档中创建图形.
通常，使用“pdflatex”比使用 PSTricks 更容易.

- [TeXample](http://www.texample.net) - 关于 LaTeX 的博客，其中包含大量 TikZ 数字.
- [LaTeX en SI](https://sciences-indus-cpge.papanicola.info/-LaTeX-en-SI-)  - 有用的网站，带有一些自定义包，可使用 TikZ 绘制特殊图（波德图、奈奎斯特图、电气原理图、框图等）. 请注意，一切都是法语.
- [tkz](http://altermundus.com/pages/tkz/index.html) - 收集基于 TikZ 的软件包以制作绘图和图表.
- [pgfplots](http://pgfplots.sourceforge.net)  - 在 TikZ/pgf 之上和风格的真正令人敬畏的绘图库. 这个库可以加载 CSV 数据文件，执行一些计算并创建漂亮的绘图.
- [A very minimal introduction to TikZ (PDF)](https://cremeronline.com/LaTeX/minimaltikz.pdf) - TikZ 世界的简短介绍文件，由 Jacques Crémer 撰写.
- [PetarV-/TikZ](https://github.com/PetarV-/TikZ) - 由 Petar Veličković 收集的可供出版的 PGF/TikZ 数字.
- [matlab2tikz](https://github.com/matlab2tikz/matlab2tikz)  - 将您的 MATLAB 绘图转换为 PGFPlots/TikZ.  ![windows]![linux]![mac]![foss]
- [tikzplotlib](https://github.com/nschloe/tikzplotlib)  - 将您的 matplotlib 绘图转换为 PGFPlots/TikZ.  ![windows]![linux]![mac]![foss]
- [TikZBlog](https://latexdraw.com) - 有关如何在 LaTeX 中绘制插图的分步教程.

### Source Code

- [minted](https://www.ctan.org/pkg/minted) - minted 包使用 [pygments](http://pygments.org/) 生成列表. 通过这种方式，LaTeX 能够格式化超过 300 种编程和标记语言以及其他文本格式.

### Typography

- [microtype](https://ctan.org/pkg/microtype) - 该软件包通过启用边距调整和字体扩展来改善文档的外观.

### Presentations, Slides

- [nics](https://nics.nilcons.com/)  - Beamer 的一个固执的替代品，我们创建它是为了让常见的任务变得非常简单，默认情况下呈现精美. 有很棒的文档和详细的备忘单来帮助您入门.

## Templates

- [LaTeX templates](https://www.latextemplates.com) - 用于 LaTeX 的论文、海报、简历、论文、书籍、演示文稿……的模板集合.
- [Ultimate Beamer Theme List](https://github.com/martinbjeldbak/ultimate-beamer-theme-list) - 链接到各种投影仪主题以及 PDF 预览.

## Symbols

- [Comprehensive LaTeX symbol list](https://www.ctan.org/tex-archive/info/symbols/comprehensive/)  - 非常广泛的 LaTeX 符号列表. 可在 [A4](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-a4.pdf) 和 [letter](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-letter.pdf) 尺寸.
- [Detexify](http://detexify.kirelabs.org/classify.html) - 您绘制符号，此站点/应用程序会告诉您 LaTeX 命令.

## Resources

- [TUG](https://www.tug.org) - TeX 用户组是一种与其他 (La)TeX 用户取得联系的方式.
- [TeXDoc](http://texdoc.net) - `texdoc` 实用程序的在线界面，用于浏览 LaTeX 包和文档.
- [Dickimaw Books: LaTeX resources](http://www.dickimaw-books.com/latexresources.html) - 对 LaTeX 有用的资源概览.
- [LaTeX cookbook](http://latex-cookbook.net) - TeXample 的兄弟，包含相当多的示例代码.
- [Visual FAQ](http://mirrors.ctan.org/info/visualFAQ/visualFAQ.pdf) - 排版问题和指向适当 TeX 常见问题解答的链接.
- [MartinThoma's LaTeX example](https://github.com/MartinThoma/LaTeX-examples/) - 包含示例 LaTeX 文档的 GitHub 存储库.
- [MacTeX Wiki: TeX Extras](http://mactex-wiki.tug.org/wiki/index.php/TeX_Extras)  - LaTeX 有用工具的概述. 其中许多是特定于 Mac 的，但相当多的也适用于其他平台.
- [LaTeX community](http://latex.org/index.php) - 关于 LaTeX 的论坛和博客.
- 德语： [Neue TeX FAQ](https://texfragen.de) - 现代和更新的 LaTeX 德语常见问题解答.
- [BibTeX Style Examples](http://www.cs.stir.ac.uk/~kjt/software/latex/showbst.html) - 常见 BibTeX 样式（BST 文件）的示例输出.
- [TeX World](http://tex.world/) - 由 TeX 用户组、DANTE 和 GUTenberg 支持的网站.
- [TeXnique](https://texnique.xyz) - LaTeX 排版游戏.

## Showcases

- [Showcase of beautiful typography done in TeX & friends](https://tex.stackexchange.com/questions/1319/showcase-of-beautiful-typography-done-in-tex-friends) - 展示 LaTeX 强大功能的一组示例.
- [Showcase of beautiful invitations in TeX](https://tex.stackexchange.com/q/281415/9075) - 使用 LaTeX 排版的邀请展示.
- [Showcase of "programming your document" paradigm](https://tex.stackexchange.com/q/219774/9075) - 展示如何像编程语言一样使用 LaTeX 的 LaTeX 文档集.
- [TUG: TeX showcase](https://www.tug.org/texshowcase/) - 来自 TUG 的网站，展示了一些 LaTeX 功能的示例.

## Tutorials

- [The (Not So) Short Introduction to LaTeX2e](http://mirrors.ctan.org/info/lshort/english/lshort.pdf) - 非常全面的 LaTeX 介绍.
- [Begin LaTeX in minutes](https://github.com/LewisVo/Begin-Latex-in-minutes) - 初学者的 LaTeX 简介，可帮助您轻松使用 LaTeX.
- [Getting to Grips with LaTeX](https://www.andy-roberts.net/writing/latex) - 完成您需要了解的有关 LaTeX 的大部分内容的完整指南.
- [LaTeX introductions in languages other than English](https://tex.stackexchange.com/questions/84384/latex-introductions-in-languages-other-than-english/84385) - 多种语言的介绍集合.

## Books

- [Wikibooks: LaTeX](https://en.wikibooks.org/wiki/LaTeX)  - LaTeX 维基书. 不是真正的纸质书，但它同样广泛.
- [The LaTeX Companion, F. Mittelbach (2004)](https://www.informit.com/store/latex-companion-9780201362992)
- [LaTeX Graphics Companion, M. Goossens (2007)](https://www.informit.com/store/latex-graphics-companion-9780321508928)
- [TeX by Topic (2007)](https://ctan.org/pkg/texbytopic)
- [TeX for the Impatient (2020)](https://ctan.org/pkg/impatient)
- [Formatting Information (2020)](http://latex.silmaril.ie/formattinginformation)  - 这是该书的基于 HTML5 的在线版本 *格式信息 - 使用 LATEX* 进行排版的介绍. 自 2000 年代初以来，它一直在不断更新.

## Blogs

- [TeXblog](http://texblog.net) - 关于 LaTeX 和所有相关内容的博客.
- [texblog.org](https://texblog.org) - 关于 LaTeX 和相关主题（教程、包、代码片段等）的博客.
- [TeX Talk](http://tex-talk.net) - 包含新闻和采访的 TeX Stack Exchange 站点的博客.

## Social media

- [LinkedIn: TeX/LaTeX User Group](https://www.linkedin.com/groups/1600297)
- [Twitter: @TeXtip](https://twitter.com/TeXtip) - 与 (La)TeX 相关的提示 [John D. Cook](https://www.johndcook.com/).
- [TeX.StackExchange](https://tex.stackexchange.com) - StackExchange TeX 部分.

---

<!-- Icons -->

## Meta Awesome-LaTeX

如果你想贡献，请阅读我们 [CONTRIBUTING](https://github.com/egeerardyn/awesome-LaTeX/blob/master/CONTRIBUTING.md) 准则.

## Legend

指示 Mac、Linux 和 Windows 兼容性的图标在程序*仅*可用于这些平台时显示. 因此，没有这些图标意味着该软件是完全跨平台的.

 | 标志 | 说明 |
|:-------------------:|:----------------------------------------------|
 |  ![mac] | [macOS](https://www.apple.com/osx/)                |
 |  ![Linux] | [GNU/Linux](https://www.gnu.org)                     |
 |  ![窗口] | [Microsoft Windows](https://www.microsoft.com/windows) |
 |  ![开源软件] | [Free Open-Source Software](https://opensource.org) |

---

所有商标均为其各自所有者的财产.

[mac]：https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/apple.svg
[linux]：https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/linux.svg
[窗口]：https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/windows.svg
[foss]：https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/foss.svg
[真棒]：https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
