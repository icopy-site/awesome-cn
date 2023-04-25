<div class="github-widget" data-repo="egeerardyn/awesome-LaTeX"></div>
## Awesome LaTeX [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg?style=flat)](https://github.com/egeerardyn/awesome-LaTeX/blob/master/LICENSE.md)

[![LaTeX Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/92/LaTeX_logo.svg/220px-LaTeX_logo.svg.png)](https://www.latex-project.org/)

&gt; 这是为 [(La)TeX typesetting system](https://www.latex-project.org/).


<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->


<!-- /TOC -->

## Learning LaTeX

指导如何学习 LaTeX


## Distributions

- [MacTeX](https://tug.org/mactex/)  - 最常见的 macOS LaTeX 发行版，基本上是添加了一些 Mac 特定工具的 TeXLive.  ！[苹果]
- [TeX Live](https://www.tug.org/texlive/)  - 最常见的用于类 Unix 操作系统的 LaTeX 发行版，包括 GNU/Linux. 也适用于 Windows.  ![Linux] ![窗户]
- [MikTeX](https://miktex.org)  - 适用于 Windows 的最常见 LaTeX 发行版，但也适用于 Mac、Linux 或作为 Docker 映像.  ![linux] ![windows] ![mac] ![foss]

## Docker Images

当一个人的目标是无需安装即可运行的 LaTeX 环境时，Docker 镜像可能是最佳选择.

- [reitzig/texlive-docker](https://github.com/reitzig/texlive-docker) - 具有包安装可能性的最小 TeXLive 系统
- [Island of TeX/texlive](https://gitlab.com/islandoftex/images/texlive) - 基于 debian 的完整 TeXLive 系统
- [dante-ev/docker-texlive](https://github.com/dante-ev/docker-texlive) - 基于 debian 的完整 TeXLive 系统，预装了 pandoc、perl 和 python

## Engines

- [pdfTeX](https://www.tug.org/applications/pdftex/)  - TeX 编译器可以立即生成 PDF 文件而不是 DVI 文件（如今，这是许多用户的标准编译器）.  ![源代码]
- [XeTeX](http://xetex.sourceforge.net)  - TeX 编译器提供比 TeX/pdfTeX 更好的 unicode 和字体支持（即您可以使用操作系统的字体，而不仅仅是 TeX 字体）.  ![源代码]
- [LuaTeX](https://www.luatex.org)  - (La)TeX 编译器支持用于脚本的 Lua 代码，并且比标准 TeX/pdfTeX 改进了 unicode 和字体支持.  ![源代码]
- [tectonic](https://tectonic-typesetting.GitHub.io/en-US/)  - 由 XeTeX 和 TeXLive 提供支持的现代、独立的 (La)TeX 编译器.  ![源代码]

### LaTeX formulas on the web

- [Auto-LaTeX Equations with Google Docs](https://sites.google.com/site/autolatexequations) - 直接在 Google 文档中呈现高质量的数学方程式.
- [MathJaX](https://www.mathjax.org)  - 用于在网络上呈现数学公式的 JavaScript 引擎. 结果看起来真的很光滑.  ![源代码]
- [mimeTeX](https://ctan.org/pkg/mimetex)  - mimeTeX 是一个相当古老的工具，可以为您的网站将 LaTeX 公式呈现为 PNG 图形，而实际上不需要在您的服务器上安装 LaTeX.  ![源代码]
- [mathTeX](https://ctan.org/pkg/mathtex)  - mathTeX 是 mimeTeX 的继任者：它生成更漂亮的图像，但它需要在您的服务器上安装 LaTeX.  ![源代码]
- [KaTeX](https://khan.GitHub.io/KaTeX/)  - KaTeX 是可汗学院制作的数学渲染库，专注于快速加载时间. 所有输出都被处理为纯 HTML 而不是固定图像.  ![源代码]
- [Franklin.jl](https://franklinjl.org/)  - 在 Julia 中具有 KaTeX 支持、代码评估、类似 LaTeX 的命令和可选的预渲染的静态站点生成器.  ![源代码]
- [xhub](https://github.com/nschloe/xhub)  - 允许您在 GitHub 页面中使用 LaTeX 的浏览器扩展.  ![源代码]

## Editors

因为用记事本编辑 LaTeX 代码并不牛逼.
那里有很多编辑器，下面是最棒的编辑器.
LaTeX 编辑器的完整列表收集于 [tex.stackexchange.com](https://tex.stackexchange.com/) 作为 [big list of LaTeX Editors/IDEs](https://tex.stackexchange.com/q/339/9075).

- [List of popular LaTeX editors](https://tex.stackexchange.com/questions/339/latex-editors-ides) - 社区维护的流行 LaTeX 编辑器列表，包括屏幕截图和简短描述.

### LaTeX-focused

一些最棒的 LaTeX 编辑器就是这样做的：编辑 LaTeX.

- [Kile](https://kile.sourceforge.io)  - 伟大的 LaTeX 编辑器，最初来自 Linux/KDE 社区. 它在 Windows 和 macOS 上也运行良好.  ![源代码]
- [TeXMaker](https://www.xm1math.net/texmaker/) - 非常好的 Kile 替代品.
- [TeXStudio](https://www.texstudio.org) - 源于 TeXMaker 的跨平台 LaTeX 编辑器.
- [WinEdt](https://www.winedt.com)  - 许多人发誓的 LaTeX 编辑器. 仅适用于 ![windows].
- [TeXnicCenter](https://www.texniccenter.org)  - 相当古老但免费且体面的 LaTeX 编辑器.  ！[视窗]
- [LyX](https://www.lyx.org)  - 跨平台的 WYSIWYM 编辑器，在幕后使用 LaTeX 呈现文档.  ![源代码]
- [TeXShop](https://pages.uoregon.edu/koch/texshop/)  - MacTeX 中包含的 LaTeX 文档的严肃编辑器.  ！[苹果]
- [TeXWorks](https://www.tug.org/texworks/)  - LaTeX 代码的严肃编辑器，以 TeXShop 为蓝本，但这个是跨平台的.  ![源代码]
- [BakomaTex](https://www.bakoma-tex.com) - 商业 LaTeX 编辑器，允许使用其源代码和所见即所得来编辑您的文档.
- [Inlage](https://www.inlage.com/home)  - 具有手写公式识别、Excel 导入和更多漂亮功能的商业 LaTeX 编辑器.  ！[视窗]
- [Texpad](https://www.texpad.com)  - 适用于 macOS 和 iOS 的商业 LaTeX 编辑器，具有出色的功能（文档概览、同步 PDF 显示、自动完成、跨设备同步等），永远不会妨碍写作.  ！[苹果]

### General purpose text editors

这些编辑器不是只会一招的小马：当然，他们编辑 LaTeX，但他们可以做更多！

- [Atom](https://atom.io) [![Atom][awesome]](https://github.com/mehcode/awesome-atom) ![foss]
  - [LaTeXTools](https://atom.io/packages/latextools)  - 同名的 Sublime Text 包的 Atom 端口.  ![源代码]

- [Sublime Text](https://www.sublimetext.com) [![Sublime Text][棒极了]](https://github.com/dreikanter/sublime-bookmarks)
  - [LaTeXing](https://github.com/LaTeXing/LaTeXing)  - 编辑 LaTeX 的免费插件.  ![源代码]
  - [LaTeXTools](https://github.com/SublimeText/LaTeXTools)  - 用于 Sublime Text 的免费 LaTeX 插件.  ![源代码]

- [Emacs](https://www.gnu.org/software/emacs/)  [![Emacs][棒极了]](https://github.com/emacs-tw/awesome-emacs) ![foss]
  - [AucTeX](https://www.gnu.org/software/auctex/)  - 用于 LaTeX 的 Emacs 插件，还可以显示方程式和图形的预览.  ![源代码]
  - [RefTeX](https://www.gnu.org/software/auctex/reftex)  - 用于 LaTeX 的 Emacs 插件，增加了对标签、参考和引用的支持.  ![源代码]

- [Vim](https://www.vim.org) [![Vim][棒极了]](https://github.com/mhinz/vim-galore) ![foss]
  - [Vim-LaTeX](http://vim-latex.sourceforge.net) ![源代码]
  - [LaTeX Live Preview](https://github.com/xuhdev/vim-latex-live-preview)  - 即时预览您的 LaTeX 文档.  ![源代码]
  - [vimtex](https://github.com/lervag/vimtex)  - 用于编辑 LaTeX 文件的现代 vim 插件. 具有多种功能，包括实时预览和向前搜索.  ![源代码]

- [IntelliJ](https://www.jetbrains.com/idea/)
  - [TeXiFy-IDEA](https://github.com/Hannah-Sten/TeXiFy-IDEA)  - 适用于 IntelliJ IDEA 的免费 LaTeX 插件.  ![源代码]

- [VS Code](https://code.visualstudio.com/) [![VS Code][awesome]](https://github.com/viatsko/awesome-vscode) ![foss]
  - [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) - Visual Studio Code 的 LaTeX 扩展！[foss]
  - [LTeX](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex) - LanguageTool 语法/拼写检查！[foss]
  - [a-nau/latex-devcontainer](https://github.com/a-nau/latex-devcontainer) - 无需本地安装即可轻松使用 LaTeX 的 Devcontainer 设置！[foss]

### Online editors

允许您协作编辑文档的在线编辑器.

- [List of popular online LaTeX editors](https://tex.stackexchange.com/questions/3/compiling-documents-online/1654#1654) - 社区维护的流行在线 LaTeX 编辑器列表，包括方程式编辑器.
- [Authorea](https://www.authorea.com) - 具有内置 git 支持和参考书目工具的在线编辑器.
- [ShareLaTeX](https://www.sharelatex.com) - 具有非常棒的 LaTeX 文档和简单的版本控制.
- [Overleaf](https://www.overleaf.com) - 在线编辑器，还带有 WYSIWYM 编辑器和 git 支持.
- [Papeeria](https://papeeria.com) - 内置 git 支持的在线编辑器.
- [JaxEdit](https://zohooo.GitHub.io/jaxedit/) - 具有实时预览和漂亮演示模式的在线 LaTeX 编辑器.

## Bibliography tools

- [JabRef](https://www.jabref.org)  - 非常强大的跨平台 (Java) bibtex 编辑器.  ![mac] ![windows] ![linux] ![foss]
- [Papis](https://github.com/papis/papis) - Extremely customizable,
  强大而简单的跨平台（Python）库管理器. 它有一个非常
  完整的命令行界面、多个 GUI 和脚本功能.
  ![linux] ![mac] ![foss]
- [Bibdesk](http://bibdesk.sourceforge.net) - 很棒的 ![mac] 参考书目编辑器.
- [Zotero](https://www.zotero.org)  - 浏览器的参考管理器，它也可以导出到 bibtex 并与许多 LaTeX 编辑器集成.  ![mac] ![windows] ![linux] ![foss]
- [Mendeley](https://www.mendeley.com)  - 用于管理您的参考资料和 PDF 的应用程序和云客户端. 可以为您的 LaTeX 工作流程同步出一个 bibtex 文件.  ![mac] ![windows] ![linux]
- [betterbib](https://github.com/nschloe/betterbib)  - 用于改进 BibTeX 文件的命令行实用程序. 从在线资源中获取信息.  ![mac] ![windows] ![linux] ![foss]

## Build Tools

编译 LaTeX 文档可能很乏味，构建工具可以帮助您管理编译过程.

- [Arara](https://www.ctan.org/pkg/arara) ([GitHub repo](https://github.com/islandoftex/arara) ) - 简单的工具，允许您指定在文档中调用哪些工具，并且可以很容易地扩展它.  ![源代码]
- [latexmk](https://www.ctan.org/pkg/latexmk)  - 许多 LaTeX 编辑器（LaTeXing、TeXShop 等）常用的构建工具来构建您的 LaTeX 文件.  ![源代码]

### GitHub Actions

- [xu-cheng/latex-action](https://github.com/xu-cheng/latex-action) - GitHub Action 编译 LaTeX 文档
- [dante-ev/latex-action](https://github.com/dante-ev/latex-action)  - DANTE eV 用于编译 LaTeX 文档的 GitHub 操作. 提供完整的 TeXLive 和预安装的 perl 和 python.

## Misc. Tools

- [CaTeX](https://github.com/Alexis-benoist/CaTeX) - 连接 LaTeX 文档，注意正确合并序言.
- [Pandoc](https://pandoc.org)  - 该程序将几乎所有文档格式（LaTeX、DOC、markdown 等）转换为几乎任何其他格式. 一个很好的工具来帮助使用多种格式的工作流程.  ![源代码]

### Quality Check Tools

- [ChkTeX](https://www.nongnu.org/chktex/)  - 用于 LaTeX 文档的 Linter / 代码检查器.  ![源代码]
- [blacktex](https://github.com/nschloe/blacktex)  - 替换常见的 LaTeX 反模式并清理文件的命令行工具.  ![windows] ![linux] ![mac] ![foss]
- [TeXtidote](https://github.com/sylvainhalle/textidote)  - LaTeX 文档的跨平台 (Java) 拼写、语法和样式检查器.  ![windows] ![linux] ![mac] ![foss]

### Tools centered around equations

- [Codecogs Eqn Editor](https://editor.codecogs.com/) - 在线 LaTeX 方程式编辑器，可让您生成包含方程式的图形.
- [EqualX](https://equalx.sourceforge.io/)  - 图形化 LaTeX 公式编辑器.  ![windows] ![linux] ![foss]
- [KLaTeXFormula](https://klatexformula.sourceforge.io)  - LaTeXit 的跨平台替代品.  ![源代码]
- [Laeqed](https://www.thrysoee.dk/laeqed/)  - 跨平台 LaTeX 公式到 PNG 转换器.  ![windows] ![linux] ![mac] ![foss]
- [LaTeXEqEdit](http://latexeqedit.sourceforge.net/)  - 适用于 Windows 的 LaTeX 公式编辑器.  ![窗户] ![源代码]
- [LaTeXiT](https://www.chachatelier.fr/latexit/)  - LaTeXit 是一个方程式编辑器，可以轻松地将呈现的方程式（如 PDF、PNG 等）拖放到 Mac 上的非 LaTeX 文档中.  ！[苹果]
- [pix2tex](https://lukas-blecher.github.io/LaTeX-OCR/) - LaTeX OCR ![windows] ![linux] ![mac] ![foss]

## LaTeX-compatible GUI tools

- [TikzEdt](https://www.tikzedt.org) （还： [GitHub repo](https://github.com/hchapman/tikzedt) ) - 所见即所得和基于文本的 TikZ 图片编辑器.  ![源代码]
- [TikZ-Editor](https://github.com/fredokun/TikZ-Editor)  - TikZ 图形的实时预览编辑器.  ![mac] ![linux] ![foss]
- [IPE](https://ipe.otfried.org)  - 与 LaTeX 命令和文档完美集成的绘图工具.  ![源代码]
- [GeoGebra](https://www.geogebra.org/) - Cross-platform geometry tool with output to TikZ. ![foss]
- [Dia](https://wiki.gnome.org/Apps/Dia)  - 可以导出到 PSTricks 和 MetaPost 代码的跨平台图表工具.  ![源代码]
- [TikZiT](https://tikzit.GitHub.io)  - 使用 PGF/TikZ 创建图形和字符串图的 GUI 工具.  ![windows] ![linux] ![mac] ![foss]
- [LaTeXDraw](https://latexdraw.sourceforge.net/)  - 以 LaTeX 作为一等公民的基于矢量的绘图工具.  ![windows] ![linux] ![mac] ![foss]

## Packages

- [CTAN](https://www.ctan.org) - Comprehensive TeX Archive Network 是寻找有用包和文档的地方.

### References

- [Cross-reference packages explained](https://tex.stackexchange.com/a/36312/9075) - 详细说明交叉引用包（cleveref、varioref、theoremref、nameref 等）：使用哪个，哪个冲突？

### Tables

- [Excel2LaTeX](https://www.ctan.org/pkg/excel2latex?lang=en)  - 用于生成 LaTeX `tabular` 代码的 Excel（2010 及更早版本）宏.  ![窗户] ![苹果电脑]
- [csv2latex](http://freshmeat.sourceforge.net/projects/csv2latex)  - 将 CSV 文件从您最喜欢的程序转换为 LaTeX `tabular`s.  ![Linux] ![苹果电脑]
- [Tables Generator](https://www.tablesgenerator.com) - 本网站提供了一个图形界面来输入您的表格，并为 LaTeX、Markdown、HTML 等生成格式正确的代码.
- [pgfplotstable](https://www.ctan.org/pkg/pgfplotstable?lang=en)  - 该软件包以各种显示格式显示数值表，四舍五入到所需的精度. 它甚至可以读取 CSV 文件以直接包含在您的 LaTeX 文档中.

### Graphics

#### PSTricks

PSTricks 是一个很棒的库，可以绘制包含在 PostScript/DVI 文件中的图形.

#### TikZ

TikZ 是一个很棒的软件包，包含许多插件，可让您从 LaTeX 文档中创建图形.
通常，使用 `pdflatex` 比使用 PSTricks 更容易.

- [TeXample](https://www.texample.net) - 关于 LaTeX 的博客，包含大量 TikZ 图.
- [LaTeX en SI](https://sciences-indus-cpge.papanicola.info/-LaTeX-en-SI-)  - 有用的网站，带有一些自定义包，可以使用 TikZ 绘制特殊图（Bode、Nyquist、电气原理图、块原理图等）. 请注意，一切都是法语.
- [pgfplots](http://pgfplots.sourceforge.net)  - 在 TikZ/pgf 之上并以 TikZ/pgf 的风格真正令人敬畏的绘图库. 这个库可以加载 CSV 数据文件，执行一些计算并创建漂亮的图.
- [A very minimal introduction to TikZ (PDF)](https://cremeronline.com/LaTeX/minimaltikz.pdf) - 由 Jacques Crémer 撰写的 TikZ 世界的简短介绍性文件.
- [PetarV-/TikZ](https://github.com/PetarV-/TikZ) - 由 Petar Veličković 收集的出版就绪的 PGF/TikZ 数字.
- [matlab2tikz](https://github.com/matlab2tikz/matlab2tikz)  - 将您的 MATLAB 图转换为 PGFPlots/TikZ.  ![windows] ![linux] ![mac] ![foss]
- [tikzplotlib](https://github.com/nschloe/tikzplotlib)  - 将您的 matplotlib 图转换为 PGFPlots/TikZ.  ![windows] ![linux] ![mac] ![foss]
- [TikZBlog](https://latexdraw.com) - 关于如何在 LaTeX 中绘制插图的分步教程.

### Source Code

- [minted](https://www.ctan.org/pkg/minted) - minted 包使用 [pygments](https://pygments.org/) 生成列表. 通过这种方式，LaTeX 能够格式化 300 多种编程和标记语言以及其他文本格式.

### Typography

- [microtype](https://ctan.org/pkg/microtype) - 此软件包通过启用边距字距调整和字体扩展来改善文档的外观.

### Presentations, Slides

- [nics](https://nics.nilcons.com/)  - Beamer 的自以为是的替代品，我们创建它的目的是希望让常见任务变得非常简单并且默认情况下呈现精美. 有很棒的文档和详细的备忘单，可帮助您入门.

## Templates

- [LaTeX templates](https://www.latextemplates.com) - 用于 LaTeX 的论文、海报、简历、论文、书籍、演示文稿等模板集合.
- [Ultimate Beamer Theme List](https://github.com/martinbjeldbak/ultimate-beamer-theme-list) - 链接到各种 beamer 主题以及 PDF 预览.
- [LaTeX Beamer Theme Overview](https://github.com/UweZiegenhagen/LaTeX-Beamer-Theme-Overview/blob/main/OVERVIEW.md) - TeXLive 中包含的 beamer 主题的视觉概览

## Symbols

- [Comprehensive LaTeX symbol list](https://www.ctan.org/tex-archive/info/symbols/comprehensive/)  - 非常广泛的 LaTeX 符号列表. 适用于 [A4](https://mirrors.ctan.org/info/symbols/comprehensive/symbols-a4.pdf) 和 [letter](https://mirrors.ctan.org/info/symbols/comprehensive/symbols-letter.pdf) 尺寸.
- [Detexify](https://detexify.kirelabs.org/classify.html) - 你绘制符号，这个网站/应用程序会告诉你 LaTeX 命令.

## Resources

- [TUG](https://www.tug.org) - TeX 用户组是一种与其他 (La)TeX 用户联系的方式.
- [TeXDoc](https://texdoc.net) - 用于浏览 LaTeX 包和文档的 `texdoc` 实用程序的在线界面.
- [Dickimaw Books: LaTeX resources](https://www.dickimaw-books.com/latexresources.html) - 对 LaTeX 有用的资源的概述.
- [LaTeX cookbook](https://latex-cookbook.net) - TeXample 的兄弟，包含相当多的示例代码.
- [Visual FAQ](https://ctan.org/pkg/visualfaq) - 排版问题和相应 TeX 常见问题解答的链接.
- [MartinThoma's LaTeX example](https://github.com/MartinThoma/LaTeX-examples/) - 包含示例 LaTeX 文档的 GitHub 存储库.
- [LaTeX community](https://latex.org/forum) - 关于 LaTeX 的论坛.
- 德语： [Neue TeX FAQ](https://texfragen.de) - 现代和更新的德语 LaTeX 常见问题解答.
- [BibTeX Style Examples](http://www.cs.stir.ac.uk/~kjt/software/latex/showbst.html) - 常见 BibTeX 样式（BST 文件）的示例输出.
- [TeX World](https://tex.world/) - TeX 用户组、DANTE 和 GUTenberg 支持的网站.
- [TeXnique](https://texnique.xyz) - LaTeX 排版游戏.

## Showcases

- [Showcase of beautiful typography done in TeX & friends](https://tex.stackexchange.com/questions/1319/showcase-of-beautiful-typography-done-in-tex-friends) - 展示 LaTeX 强大功能的示例集.
- [Showcase of beautiful invitations in TeX](https://tex.stackexchange.com/q/281415/9075) - 使用 LaTeX 排版的邀请函展示.
- [Showcase of "programming your document" paradigm](https://tex.stackexchange.com/q/219774/9075) - 演示 LaTeX 如何像编程语言一样使用的 LaTeX 文档集.
- [TUG: TeX showcase](https://www.tug.org/texshowcase/) - 来自 TUG 的网站显示了 LaTeX 可以做什么的一些例子.
- [Awesome LaTeX drawing](https://github.com/xinychen/awesome-latex-drawing) - 使用 LaTeX 的学术绘图示例精选列表

## Tutorials

- [LearnLaTeX.org](https://www.learnlatex.org/) - 基于浏览器的 LaTeX 教程.
- [The (Not So) Short Introduction to LaTeX2e](https://mirrors.ctan.org/info/lshort/english/lshort.pdf) - 非常全面的 LaTeX 介绍.
- [Begin LaTeX in minutes](https://github.com/luong-komorebi/Begin-Latex-in-minutes) - 初学者LaTeX简介，让你轻松上手LaTeX.
- [Getting to Grips with LaTeX](https://www.andy-roberts.net/writing/latex) - 完成您需要了解的有关 LaTeX 的大部分内容的完整指南.
- [LaTeX introductions in languages other than English](https://tex.stackexchange.com/questions/84384/latex-introductions-in-languages-other-than-english/84385) - 多种语言的介绍集.

## Books

- [Wikibooks: LaTeX](https://en.wikibooks.org/wiki/LaTeX)  - LaTeX wikibook. 不是真正的纸质书，但它同样广泛.
- [The LaTeX Companion, F. Mittelbach (2004)](https://www.informit.com/store/latex-companion-9780201362992)
- [LaTeX Graphics Companion, M. Goossens (2007)](https://www.informit.com/store/latex-graphics-companion-9780321508928)
- [TeX by Topic (2007)](https://ctan.org/pkg/texbytopic)
- [TeX for the Impatient (2020)](https://ctan.org/pkg/impatient)
- [Formatting Information (2020)](https://latex.silmaril.ie/formattinginformation)  - 这是本书基于 HTML5 的在线版本 *Formatting Information - 使用 LATEX* 排版的介绍. 自 2000 年代初以来，它一直在不断更新.

## Blogs

- [TeXblog](https://texblog.net) - 关于 LaTeX 和所有相关内容的博客.
- [texblog.org](https://texblog.org) - 关于 LaTeX 和相关主题（教程、包、代码片段等）的博客.
- [TeX Talk](https://tex-talk.net) - TeX Stack Exchange 网站的博客，提供新闻和采访.

## Social media

- [LinkedIn: TeX/LaTeX User Group](https://www.linkedin.com/groups/1600297)
- [Twitter: @TeXtip](https://twitter.com/TeXtip) - 与 (La)TeX 相关的提示 [John D. Cook](https://www.johndcook.com/).
- [TeX.StackExchange](https://tex.stackexchange.com) - StackExchange TeX 部分.
- [TopAnswers TeX](https://topanswers.xyz/tex) - 为 TeX 和朋友提供的免费开源问答网站

---

<!-- Icons -->

## Meta Awesome-LaTeX

如果你想贡献，请阅读我们 [CONTRIBUTING](https://github.com/egeerardyn/awesome-LaTeX/blob/master/CONTRIBUTING.md) 准则.

## Legend

指示 Mac、Linux 和 Windows 兼容性的图标会在某个程序*仅*适用于这些平台时显示. 因此，没有这些图标意味着该软件是完全跨平台的.

 | 标志 | 说明 |
|:-------------------:|:-------------------------------------------------------|
 |  ![苹果电脑] | [macOS](https://www.apple.com/macos)                   |
 |  ![Linux] | [GNU/Linux](https://www.gnu.org)                       |
 |  ![窗口] | [Microsoft Windows](https://www.microsoft.com/windows) |
 |  ![源码] | [Free Open-Source Software](https://opensource.org)    |

---

所有商标均为其各自所有者的财产.

[mac]: https://cdn.jsdelivr.net/gh/egeerardyn/awesome-LaTeX@700138fe725574e1741f148df6d1f77a8aa07eee/fig/apple.svg
[Linux]: https://cdn.jsdelivr.net/gh/egeerardyn/awesome-LaTeX@700138fe725574e1741f148df6d1f77a8aa07eee/fig/linux.svg
[窗户]：https://cdn.jsdelivr.net/gh/egeerardyn/awesome-LaTeX@700138fe725574e1741f148df6d1f77a8aa07eee/fig/windows.svg
[源码]：https://cdn.jsdelivr.net/gh/egeerardyn/awesome-LaTeX@700138fe725574e1741f148df6d1f77a8aa07eee/fig/foss.svg
[很棒]：https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
