<div class="github-widget" data-repo="emptymalei/awesome-research"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Research Tools

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

研究工具列表. 也可在 [https://tools.kausalflow.com/tools/](https://tools.kausalflow.com/tools/).

## TOC



## Be-Organized


### Version Control System

 &gt; 首先，每个人都应该知道版本控制系统，也就是 VCS.  VCS 帮助我们跟踪文档中的更改以及文档上的协作. 不用说，版本控制是科学家最有用的工具之一.

* **混帐**
* svn
* 水银


#### Online Git Service

* [GitHub](https://github.com/)：最流行的 git 平台，内置社交和协作.
   * GitHub 还提供 GitHub Actions. 借助 Actions，您可以自动化流程.
   * GitHub 提供 GitHub Pages. 使用 GitHub Pages，on 可以托管静态文件以及 [Jekyll](https://jekyllrb.com) 建网站.
* [GitLab](https://about.gitlab.com/) ：与 GitHub 类似，GitLab 提供 git 托管、协作、社交、自动化等.  GitLab 既可以基于云，也可以使用其开源代码自托管.
  * GitLab 包括无限的免费私人存储库.
  * GitLab 自带持续集成工具，比 GitHub Actions 更强大.
* [BitBucket](https://bitbucket.org)：具有免费私有存储库的 GitHub 和 GitLab 的替代品.


#### Self-hosted Git Server

* [GitLab](http://gitlab.org/)：见上文 [Online Git Service](#online-git-service).
* [Gitea](https://gitea.io/en-us/)：用 Go 编写的无痛自托管 Git 服务.
* [Gogs](https://gogs.io/)：一个无痛的自托管 Git 服务.


#### Enterprise Git Service

* [RhodeCode](https://rhodecode.com/) ：分布式存储库的集中控制.  Mercurial、Git 和 Subversion 在一个屋檐下.


### Pomodoro

> [Pomodoro Technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) 可用于提高您的工作效率并可能改善您的健康. 这些工具几乎有无限的选择.

* [Pomotodo](https://pomotodo.com/) （`Cloud`、`Mac`、`Win`、`Android`、`iOS`、`Chrome`）：混合了待办事项列表和番茄钟，具有跨设备同步和每周报告[免费].
* [Tadam](https://tadamapp.com/) (`Mac`)：简单优雅的番茄钟 [USD$ 4.99].
* [Productivity Challenge Timer](https://play.google.com/store/apps/details?id=com.wlxd.pomochallenge&hl=en) (`Android`)：具有出色游戏化功能的番茄钟 [免费].


### GTD-Task Manager

 &gt; GTD (Getting Things Done) 方法通过使用外部工具记录待办事项列表，将它们从脑海中卸载. 它允许人们专注于一项活动任务而不是所有任务（[Wikipedia](https://en.wikipedia.org/wiki/Getting_Things_Done)).
&gt; 任务可以按上下文（@home、@computer、@office 等）、行动时间（现在、下一步行动、计划或某天）和项目进行分类. [Here](https://hamberg.no/gtd/) 我们有一个很好的 GTD 实用指南和 [here](https://gettingthingsdone.com/pdfs/tt_workflow_chart.pdf) 是流程图.

* [Microsoft To Do](https://todo.microsoft.com/tasks) （`Cloud`、`Mac`、`Win`、`Android`、`iOS`、`Win Store`、`Chrome OS`）：近乎完美的待办事项列表，合作共享.
* [Google Keep](https://keep.google.com/)（`Cloud`、`Android`、`iOS`、`Chrome OS`）
* [Evernote](https://evernote.com/) （`Cloud`、`Mac`、`Win`、`Android`、`iOS`、`Win Store`）：不是那么轻巧，但仍然非常适合管理生活，特别是因为它已经从很多其他服务.
* [Anydo](https://www.any.do/) （`Cloud`,`Mac`,`Android`,`iOS`）：很好，因为它有一个非常好的每日评论，可以帮助用户记住要做什么.
* [Todoist](https://todoist.com/) （`Cloud`、`Mac`、`Win`、`Android`、`iOS`）：Todoist 发明了记录已完成任务的业力系统.
* [Taskade](https://taskade.com/) （`Cloud`、`Mac`、`Win`、`Chrome OS`、`Firefox`、`Android`、`iOS`）：Taskade 是团队项目的协作任务列表和大纲.
* [Agenda](https://agenda.com/)(`Mac`)：以日期为中心的笔记.


## Cloud Services

*对于自托管服务，请查看 [awesome-selfhosted](https://github.com/Kickball/awesome-selfhosted) 在 GitHub 上.*


### Math and Programming Online

&gt; 有许多工具允许使用代码、执行数值计算或在线分析推导.

* [Google Colab](https://colab.research.google.com/) : 免费的 jupyter notebook 在线.  Google Colab 还提供免费的 GPU 小时数.
  *免费且功能强大.
  * 在同一个笔记本上共享和协作.
  * 可以保存在 GitHub 或 Google Drive.
* [NextJournal](https://nextjournal.com/): 可重复研究的笔记本.
  * 基本上，NextJournal 几乎可以运行任何东西.
  * 专注于可重复性.
* [Kaggle](https://www.kaggle.com/): kaggle 内置了免费的 jupyter notebook.
  * 还可以连接到 Google BigQuery 以访问大数据.
* [Azure Notebooks](https://notebooks.azure.com/): 在线 jupyter 笔记本.
* [Datalore](https://datalore.io/)：JetBrains 的在线 jupyter 笔记本.
* [CoCalc (SageMathCloud)](https://cocalc.com/)：LaTeX、R、iPython Notebook 等.
* [SageMaker](https://aws.amazon.com/sagemaker/) : 集成了很多工具的 AWS 服务.  Sagemaker 附带 Sagemake Studio，它为程序员和其他图表和数据管理工具提供 jupyter notebook.
* [WolframAlpha](https://www.wolframalpha.com/)：在线进行数学推导和搜索的优秀引擎.
* [Mathematica Online](https://www.wolfram.com/mathematica/online/)：将 Mathematica 带入云端.



### Plotting and Charting Online

&gt; 虽然可以使用上面提到的这些在线 jupyter notebook 进行绘图，但也有许多易于使用的工具可用于简单绘图.

* [plot.ly](https://plot.ly/)：在线绘图与许多云服务集成.
* [Desmos](https://www.desmos.com/calculator): 函数图.
* [GeoGebra](https://www.geogebra.org) : 很老但是还是很好的.  GeoGebra 可用于精确制图和计算.
* [graph.tk](http://graph.tk/)：具有丰富功能的在线绘图.
* [Wolfram Alpha](http://www.wolframalpha.com/)：根据您的数据等为函数制作图表.


### Datasets

&gt; Nature 提供推荐的数据存储库列表 [here](https://www.nature.com/sdata/policies/repositories).

#### General and Interdisciplinary

* [DRYAD](http://datadryad.org/) （`Storage`、`Lookup`）：Dryad 数字存储库存储精选数据.
* [Figshare](https://figshare.com/) (`Storage`, `Lookup`): 数据共享和存储
* [Data.gov](https://data.gov) （`查找`）：美国联邦政府的数据

#### Life Science

* [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) (`Lookup`): 基因序列数据库
* [National Centers for Environmental Information](https://www.ncei.noaa.gov/) （`查找`）：天气、气候、海岸、海洋和地球物理学等
* [GEOSS Portal](http://www.geoportal.org) （`查找`）：地球科学数据

#### Physical Sciences

* [US Virtual Astronomical Observatory](http://www.usvao.org/) （`查找`）
* [MAST: Barbara A. Mikulski Archive for Space Telescopes](https://mast.stsci.edu/portal/Mashup/Clients/Mast/portal.html) （`查找`）
* [Mikulski Archive for Space Telescopes](http://archive.stsci.edu/) （`查找`）

#### Arts and Humanities

* [Archaeology Data Service](http://archaeologydataservice.ac.uk/) （`查找`）：认证的存储库

#### Engineering

* [Open Energy Information (OpenEI)](http://en.openei.org/wiki/Main_Page) （`查找`）：能源信息集合的维基

#### Social Sciences

* [Inter-university Consortium for Political and Social Research (ICPSR)](https://www.icpsr.umich.edu/icpsrweb/landing.jsp) （`查找`）
* [Institute for Quantitative Social Science (IQSS)](http://library.harvard.edu/gdc) （`查找`）


### Colors

&gt; 为您的演示文稿和笔记选择令人愉悦的颜色.

* [ColorBrewer](http://colorbrewer2.org)
* [Paletton](http://paletton.com)
* [Color Calculator](https://www.sessions.edu/color-calculator/)


## Publishing and Sharing


&gt; 利用 [GitHub](http://github.com) 与他人合作. [GitHub pages](https://pages.github.com/) 也适合托管静态内容.
&gt; GitHub 提供教育福利，因此学生可以获得带有私人存储库的免费专业版.


### Writing

**Markdown 是最好的写作语言之一.** 查看这些编辑器 [Markdown section](#markdown).

**利用这些程序进行发布：**

* [Sphinx](http://sphinx-doc.org): RestructuredText 作为源文件，功能强大、灵活且模块化.
* [Gitbook](https://www.gitbook.com/) : 一个新的但很有前途的 HTML、pdf 和 epub 工具，具有在线编辑器和本地编辑器. 测验和数学之类的插件可以帮助编写科学.
* [Git-scribe](https://github.com/schacon/git-scribe): 适合写电子书.
* [Static Site Generator](#static-site-generator): 更多请参考 [Static Site Generator](#static-site-generator).


**Sphinx 主题和配置**

* [rtd theme](https://github.com/snide/sphinx_rtd_theme): 由 ReadtheDocs.org 开发
* [Alabaster](https://github.com/bitprophet/alabaster): 干净简单
* [Some beautiful themes](https://github.com/vkvn/sphinx-themes)
* [Bootstrap theme](https://ryan-roemer.github.io/sphinx-bootstrap-theme/)


**使用 Sphinx 的科学书籍**

&gt; 以下是狮身人面像可用于研究的一些示例.

* [Theoretical Physics](https://github.com/certik/theoretical-physics)
* [Statistical Physics](https://github.com/emptymalei/statisticalphysics)
* [Neutrino Physics](https://github.com/NeuPhysics/neutrino)


**写作工具**

&gt; 只需使用 [Visual Studio Code](https://code.visualstudio.com/).

* [Hemingway App](https://hemingwayapp.com/)：突出复杂的句子，指出被动语态，并建议替代词.
* [proselint](https://github.com/amperser/proselint): 使用 *Garner&#39;s Modern American Usage* 等建议的英语散文短绒.
* [write good](https://github.com/btford/write-good): 用于英语散文的幼稚 JavaScript linter.
* [artbollocks-mode](https://github.com/sachac/artbollocks-mode)：Emacs 次要模式，用于在撰写艺术（或其他主题）时避免陈词滥调和语法错误.
* [`cut_the_crap.py`](https://jugad2.blogspot.com/2015/07/cut-crap-absolutely-essential-tool-for.html)：简单的 Python 脚本来标记多余的单词并提供替代建议.
* [Rousseau](https://github.com/GitbookIO/rousseau): 用 Ja​​vaScript 编写的轻量级校对器.
* [textlint-rule-rousseau](https://github.com/azu/textlint-rule-rousseau)：使用卢梭检查英语句子的 textlint 规则.
* [De-Jargonizer](http://scienceandpublic.com/)：粘贴您的文章或上传文件以分析您写作中的行话量.


### Hosting

 &gt; 托管您的文章、笔记等. 研究也与通信有关.

* [ReadtheDocs](http://readthedocs.org/)：将您的 reStructuredText 源文件转换为 HTML、PDF 和 epub，所有这些都在线完成.
* [GitHub pages](https://pages.github.com/) : 与 Jekyll 集成并自动翻转 Markdown 帖子.  Jekyll 是一个写博客的工具.
* [GitHub](http://github.com) ：只需将 markdown、reStructuredText、PDF 或 IPython/Jupyter 笔记本文件放在 GitHub 上. 所有这些格式都可以在线预览.  **值得一提的是，IPython notebook 中的数学运算可以在 GitHub 上呈现.**
* [Aerobatic](https://www.aerobatic.com/)：GitHub Pages 的强大替代品.
* [Surge](https://surge.sh/) ：一个命令上传您的静态网站以使其生效.  Surge 还集成了 GitHub 钩子.
* [Heroku](https://www.heroku.com/): 不用解释的.
* [AWS](https://aws.amazon.com/)：亚马逊 AWS 提供学生福利.

&gt; 其他服务，例如 [Digital Ocean](https://www.digitalocean.com/) 在动态网站和云计算方面也很有用.


### Blog and CMS

&gt; 在平台做调查之前，请提醒自己：
>
&gt; **我想写，而不是运行博客软件.**


**博客/CMS软件**

&gt; 这些程序在服务器上运行，可以 [hosted using these services](#hosting).

* [Ghost](https://github.com/tryghost/Ghost)  (`Node.js`)：开放、简单、非营利； 使用降价和实时预览编写.
* [Pico](https://github.com/picocms/Pico) (`PHP`)：轻量级 cms，开源，无数据库.
* [Dropplets](https://github.com/circa75/dropplets)  (`PHP`)：开源、简洁、优雅的博客系统； 用 Markdown 写.
* [Wordpress](https://wordpress.org/) (`PHP`)：非常流行，但需要大量维护.


**这些博客/CMS 软件可以托管在 [Digital Ocean](https://www.digitalocean.com/).**


### Static Site Generator

> [Here is a nice website](https://staticsitegenerators.net/) 它告诉你所有的静态站点生成器. 尽管如此，这里还是列出了最受欢迎的列表.

* [Jekyll](http://jekyllrb.com/)  （用 `Ruby` 编写）（`Markdown`）： Jekyll 是使用最广泛的一种.  Jekyll 最好的部分是通过将源推送到 GitHub 来部署到 GitHub Pages.
* [Octopress](http://octopress.org/) （用 `Ruby` 编写）（`Markdown`）：与 Jekyll 相比，Octopress 更易于使用，同时与 Jekyll 有一定的兼容性.
* [Hexo](https://hexo.io/)  （用 `Node.js` 编写）（`Markdown`）：正如他们在其网站上所说的，“一个快速、简单且强大的博客框架”. 它支持 GFM.
* [Pelican](http://getpelican.com) （用`Python`编写）（`reStructuredText`,`Markdown`,`AsciiDoc`）：Pelican 是一个模块化框架，非常适合写博客.
  * [Pelican Svbtle Theme](https://github.com/wting/pelican-svbtle)
* [Nikola](https://getnikola.com/) （用`Python`编写）（`reStructuredText`、`Markdown`、`IPython Notebook/Jupyter`、`PHP`等）：它接受多种输入格式，包括reStructuredText和许多其他格式.
* [Hugo](http://gohugo.io/) （用`Go`编写）（`Markdown`）：易于使用且速度非常快. 它还通过插件支持更多的输入格式.
* [Hyperdraft](https://hyperdraft.rosano.ca)（用`JavaScript`编写）（`Markdown`）：在您键入纯文本或Markdown时自动生成网站.


&gt; 这些程序生成的站点可以托管在 [GitHub Pages](https://pages.github.com/).


## Note Taking

### Notebooks for Researchers

* [Findings](https://findingsapp.com)：您的研究助理和实验室笔记本，尽在一个应用程序中.

### Editors

&gt; Markdown、LaTeX 和 reStructuredText 是三种有用的语言.
> **In most cases, a tweakable text editor such as [Visual Studio Code, aka vscode](https://code.visualstudio.com) 已经足够好了.** 事实上，vscode 附带了大量可用于构建您自己的 IDE 的扩展.


#### Markdown

* [Hackmd.io](https://hackmd.io) （`Cloud`）：基本上包含您对最完整的在线降价编辑器所期望的一切.
* [StackEdit](https://stackedit.io/)(`Cloud`)：StackEdit 是一个 Markdown 编辑器，具有许多集成服务，例如数学 (MathJax)、Google Drive、Dropbox 和 GitHub.
* [CMD markdown](https://www.zybuluo.com/mdeditor) (`Cloud`): CMD 是一个支持数学 (MathJax) 的 Markdown 编辑器. 特殊之处在于它保留了编辑历史记录.  （中文用户界面.）
* [Penflip](https://www.penflip.com/) （`Cloud`）：Penflip 旨在成为作家的 GitHub. 它是基于 Markdown 和 git 的，没有数学支持.
* [Authorea](https://www.authorea.com/)(`Cloud`): 一个更强大的 Markdown 和 LaTeX 在线编辑器，可用于制作精美的学术论文.
* [Dillinger](http://dillinger.io/)(`Cloud`)：Markdown 编辑器，但没有数学模式.
* [Online Kramdown Editor](http://kramdown.herokuapp.com/)(`Cloud`)：只是另一个没有数学支持的 Markdown 编辑器.
* [Pandoc Markdown](http://pandoc.herokuapp.com/)(`Cloud`): 又一个支持数学 (MathJax) 的 Markdown 编辑器.
* [Marxico](http://marxi.co/)(`Cloud`,`Mac`,`Win`,`Chrome`): Markdown 编辑器，与 Evernote 集成，生成 pdf 并离线工作. [马克飞象](https://maxiang.io/)(`Cloud`,`Mac`,`Win`,`Chrome`)是中文版.
* [Madoko](https://www.madoko.net/) （`Cloud`、`Chrome`）：一个支持数学的 Markdown 编辑器，可以一键轻松插入图片，而您的文件保存在 Dropbox、GitHub、OneDrive 或本地磁盘上. 它生成pdf和HTML页面，并使用浏览器的本地存储离线工作. 甚至可以导入 LaTeX 文件.
* [Markx](http://markx.herokuapp.com/) (`Cloud`)：用于科学写作的 Markdown 编辑器. 包括电池.
* [typora](https://www.typora.io/)(`Mac`,`Win`)：漂亮的 UI 和现场实时预览.
* [Haroopad](http://pad.haroopress.com/) (`Mac`,`Win`,`Linux`)：一个强大的 github 风格的降价编辑器，带有有用的扩展. 支持数学 (mathjax).
* [jbt/markdown-editor](http://jbt.github.io/markdown-editor/)(`Cloud`)：只是另一个没有数学支持的在线 Markdown 编辑器.
* [Mou](http://25.io/mou/) (`Mac`)：Mou 曾经是 Mac 上最好的 Markdown 编辑器. 这还不错，但不要预购 Mou 1.0. 这个项目已经死了，非官方的. [了解为什么死掉，请阅读此文。](http://matrix.sspai.com/p/c7a3c9c0)
* [MarkdownPad](http://markdownpad.com/) (`Win`)：如果你对 .NET 没有什么不好的感觉，这很好.
* [ReText](https://github.com/retext-project/retext)  （`Mac`、`Win`、`Linux`）：ReText 是最好的之一，即使在 Linux 上也是如此. 它还支持 reStructuredText 输入.
* [Madoko](https://www.madoko.net/) (`Cloud`): **LaTeX** × Markdown ²
* [eme](https://github.com/egoist/eme) （`Win`、`Mac`、`Linux`）：数学支持.
* [Moeditor](https://moeditor.org/) （`Win`、`Mac`、`Linux`）：通用降价编辑器.

可以用 Markdown 写的笔记本软件：

* [boostnote](https://boostnote.io/) （`Win`、`Mac`、`Linux`）：Math + Markdown，支持片段注释.
* [Quiver](http://happenapps.com/) (`Mac`,`iOS`)：程序员的笔记本，math + Markdown，代码片段.
* [Findings](http://findingsapp.com/) (`Mac`)：实验者的笔记本，有组织的研究材料和笔记.
* [Notion](https://www.notion.so/) （`Win`、`Mac`、`iOS`、`Android`）：用看板、数学、日历、表格等记笔记.
* [Agenda](https://agenda.com/) （`Mac`，`iOS`）：Notes 和 GTD.


#### LaTeX


* [ShareLaTeX](https://www.sharelatex.com/) (`Cloud`)：Dropbox和GitHub的集成、预览、合作、简单的UI. 它还提供了很多模板.
* [Overleaf](https://www.overleaf.com/)(`Cloud`)：内置版本控制.
* [Authorea](https://www.authorea.com/) (`Cloud`)：易于使用的 UI. 同时支持 Markdown 和 LaTeX.
* [Papeeria](https://www.papeeria.com)(`Cloud`): 又一个在线 LaTeX 和 Markdown，带有绘图编译器和协作.
* [JaxEdit](http://jaxedit.com/)(`Cloud`)：JaxEdit 不提供完整的 LaTeX 支持，但对于简单的 LaTeX 文档和幻灯片来说已经足够了.


**您也可以使用自己的机器托管一个.**

* [FlyLaTeX](https://github.com/alabid/flylatex)：sharelatex 的免费开源版本
* [ShareLaTeX Source Code](https://github.com/sharelatex/sharelatex) : ShareLaTeX 开源了他们的代码. 我会说这是一个伟大的举措.
* [TeXStudio](http://www.texstudio.org) - 源自 TeXMaker 的跨平台 LaTeX 编辑器.
* [WinEdt](http://www.winedt.com) - 许多人发誓的 LaTeX 编辑器.
* [TeXnicCenter](http://www.texniccenter.org) - 一个相当古老但免费且体面的 LaTeX 编辑器.
* [LyX](https://www.lyx.org) - 跨平台的所见即所得编辑器，在后台使用 LaTeX 来呈现文档.
* [TeXshop](http://pages.uoregon.edu/koch/texshop/) - MacTeX 中包含的 LaTeX 文档的严肃编辑器.
* [TeXWorks](https://www.tug.org/texworks/) - LaTeX 代码的严肃编辑器，仿照 TeXShop，但这是跨平台的.



### IPython Notebook

使用 IPython Notebook 帮助您进行研究.  IPython Notebook 可以直接在 GitHub 上预览. 以下是如何使用 IPython 笔记本的一些示例.

* [Scientific Python Lectures](https://github.com/jrjohansson/scientific-python-lectures)
* [Reproduced Papers](http://reproduced-papers.github.io/)
* [More](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks)：有关 GitHub 上的更多 IPython 笔记本，请阅读这个庞大的列表.



### Mindmap

**Standalone**

* 头脑管理器
* XMind
* 多卡尔

**Online**

* [KityMinder By Baidu](https://github.com/fex-team/kityminder) : 中文界面
* [my-mind](http://my-mind.github.io/): 回购 [here](https://github.com/ondras/my-mind).
* [beautiful Mind](http://beautifulmind.io/): 回购 [here](https://github.com/ierror/BeautifulMind.io)
* [Mindmup](https://www.mindmup.com/): 回购 [here](https://github.com/mindmup)
* [mindmaps](http://drichard.org/mindmaps/): 回购 [here](https://github.com/drichard/mindmaps)


**思维导图 HTML**

* [gojs](http://gojs.net/latest/samples/mindMap.html)
* [mapjs](http://coderbay.com/create-mind-maps-with-javascript-mapjs/)
* [jsmind](https://github.com/hizzgdev/jsmind)
* [jsmind](http://sourceforge.net/projects/jsmind/)
* [mindmaps](https://github.com/drichard/mindmaps)


### Concept Map and Diagrams

1. [Gliffy](https://www.gliffy.com/): 各种图
2. [ProcessOn](http://www.processon.com/): 各种图
3. [Draw.io](http://www.draw.io/): 各种图


### Keep The Notes


 &gt; 跟踪笔记的变化总是更好，**git** 是一个不错的选择. 所以， [GitHub](http://github.com) 是近乎完美的地方.
>
&gt; 至于 LaTeX， [latexdiff](http://www.ctan.org/tex-archive/support/latexdiff/) 是检查差异的工具.

&gt; **某些程序允许您将降价注释保存在服务器上.**

* [Raneto](http://raneto.com/) ：Raneto 是一个开源知识库平台，它使用静态 Markdown 文件来支持您的知识库. 这个有好看
* [Realms](http://realms.io/) ：受 Gollum、Ghost 和 Dillinger 启发，用 Python 编写的基于 Git 的 wiki. 包括基本身份验证和注册.
* [Tiddlywiki](http://tiddlywiki.com/)：用于捕获、组织和共享复杂信息的独特非线性笔记本.
* 其他 [static site generators](#static-generator).

对于实验研究，eLabFTW 制作了一个在线实验室笔记系统： [eLabFTW](https://www.elabftw.net/).




## Presentation Tools

### Keep You Computer Awake

 &gt; 在演示过程中保持计算机处于唤醒状态很重要. 除了更改电源选项之外，以下工具也可以完成这项工作.


* [Caffeine](https://itunes.apple.com/us/app/caffeine/id411246225) (`Mac`)：就像单击一样简单.
* [Amphetamine](https://itunes.apple.com/us/app/amphetamine/id937984704?mt=12) (`Mac`)：涉及的配置更多，更智能.


### Online Load and Edit


* [Prezi](https://prezi.com/) 如果你可以的话.
* [slides.com](http://slides.com/)：易于使用远程控制页面演示.
* [Slideas](https://www.slideas.app/)：创建精美 Markdown 演示文稿的最简单方法，具有您需要的所有功能.
* [Google Drive](https://drive.google.com/): 不需要介绍
* [Sway](https://sway.com/): 微软
* [Strut](https://github.com/tantaman/Strut)
* [Impressionist](https://github.com/harish-io/Impressionist)
* [hovercraft](https://github.com/regebro/hovercraft)



### Use The Source

&gt; 需要一些前端技术.

#### HTML+CSS+JS

&gt; 使用 [colors](https://github.com/mrmrs/colors) 让您的 HTML 感觉更好.

* [Impress.js](http://impress.github.io/impress.js/): 更多关于它 [impress wiki page](https://github.com/impress/impress.js/wiki).
* [Jimpress](http://jmpressjs.github.io/jmpress.js/): impress.js 的 jQuery 版本
* [Reveal.js](https://github.com/hakimel/reveal.js)
* [Beckpoke.js](https://github.com/bespokejs/bespoke)
* [CSSS](https://github.com/LeaVerou/CSSS)
* [Scrolldeck](https://github.com/johnpolacek/scrolldeck.js)
* [Deck.js](https://github.com/imakewebthings/deck.js)
* [Shower](https://github.com/shower/shower)
* [HTML5 Rocks](http://slides.html5rocks.com/#formula-outro-slide)
* [Flowtime.js](https://github.com/marcolago/flowtime.js)
* [Slides](https://github.com/briancavalier/slides)
* [remark](https://remarkjs.com)


### IPython/Jupyter Notebook

&gt; 支持 Python、Julia、R、Scala 和更多语言 [IPython/Jupyter Notebook](https://jupyter.org/) 也可以用来做演示.
>
&gt; 参考 [math and programming online](#math-and-programming-online) 用于基于云的 Jupyter Notebooks.


### LaTeX Beamer

* [Beamer](https://bitbucket.org/rivanvx/beamer/wiki/Home) ：随标准 LaTeX 安装一起提供. 已经发明了很多主题. 一键开始编辑
  * [ShareLaTeX](https://www.sharelatex.com)
  * [Overleaf](https://www.overleaf.com/)

### Mathematica

* [Mathematica slides](http://reference.wolfram.com/language/howto/CreateASlideShow.html) 可以做成交互式的.


### The Power of SVG

**在线 SVG 编辑器：**

* [ext-sozi](https://github.com/asyazwan/ext-sozi)

**本地 SVG 编辑器：**

* [Inkscape](https://inkscape.org)(`Mac`,`Win`,`Linux`)
* [GIMP](https://www.gimp.org)(`Mac`,`Win`,`Linux`)


### Sharing Slides

* [GitHub pages](https://pages.github.com/): 对于基于 Html 的幻灯片.
* [Speaker Deck](https://speakerdeck.com/) by GitHub: PDF slides. Can be displayed online or embeded.


## Programming

### Code Editors


* [Visual Studio Code, aka VS Code](https://code.visualstudio.com/)(`Free`,`Cross-platform`,`Plugins`): 与 atom 相同的技术，但比 atom 更快，微软制造.
* [Atom](https://atom.io/) (`Free`,`Cross-platform`,`Plugins`)：基于电子的编辑器，具有众多插件和易于修改. 跨平台的设置和插件通过 [sync-settings](https://atom.io/packages/sync-settings) 插入.
* [Sublime Text](https://www.sublimetext.com/) （`免费评估`，`跨平台`，`插件`）：跨平台，快速，并带有插件. 不是免费的，但可以永远免费使用.
* [JetBrains](https://www.jetbrains.com/)（`学生免费`，`跨平台`，`插件`）：漂亮的IDE，集成了许多调试和编辑模式.
* [vim](https://github.com/vim/vim)(`Free`,`Cross-platform`,`Plugins`): 没有语言可以描述全能的 vim.
  * [Vundle](https://github.com/VundleVim/Vundle.vim): vim 插件管理器
  * [vimrc from amix](https://github.com/amix/vimrc): &quot;终极 Vim 配置：vimrc&quot;


### Softwares

* [Mathematica](http://www.wolfram.com/mathematica/): 一个软件来统治他们
* [iPython Notebook](http://ipython.org/notebook.html) (`Python`)：用于内联计算、制作图表和写笔记的有用工具.
  * [wakari.io](https://wakari.io/) 是一个商业的，主要针对数据分析.
  * [jiffylab](https://github.com/ptone/jiffylab) 是一个开源的，但做得不是很好.
  * [supervised-ipython-nbserver](https://github.com/writefaruq/supervised-ipython-nbserver) 是使用 Django/Pinax 的多用户笔记本版本.
* [Matlab](http://www.mathworks.com/products/matlab/)
* [Maple](https://www.maplesoft.com/index.aspx?L=E)
* [RStudio](https://www.rstudio.com/) (`R`)


### Scientific Computing

* [Python](https://www.python.org/)
  * [scipy](https://www.scipy.org/): 科学计算变得容易
  * [SnakeViz](https://jiffyclub.github.io/snakeviz/): python 调试和性能改进的好工具.
* [Julia](http://julialang.org/)
* [R](http://www.r-project.org/)
* [Rust](https://www.rust-lang.org/en-US/)

### Coding is Fun

* [Code Fights](https://codefights.com/)


## Academic


### Self-plagiarism

 &gt; 这可能不是那么简单，但请记住这一点. 重复使用自己的作品并不能保护您免受抄袭！ 阅读更多

* [wikipedia:Plagiarism#Self-plagiarism](https://en.wikipedia.org/wiki/Plagiarism#Self-plagiarism).

### Investigate Papers

* [Paperscape](http://paperscape.org/): 寻找有趣的论文.
* [Peerus](https://peer.us/)：监控特定主题或期刊的新论文和相关论文.
* [SciRate](https://scirate.com/)：arXiv 的前端，来自读者的费率.
* [ArXiv Sanity Preserver](http://arxiv-sanity.com/)：通过 arXiv 加速对 Andrej Karpathy 的许多机器学习的研究.
* [Iris.ai](https://the.iris.ai/)：探索科学论文以及它们如何连接到您选择的论文.
* [Publish or Perish](https://harzing.com/resources/publish-or-perish)：检索和分析学术引文，旨在使个别学者能够充分展示他们的研究影响力.
* [PubChase](http://pubchase.com/)：生命科学和医学文献推荐引擎.
* [Connected Papers](https://www.connectedpapers.com/)：可视化连接的论文，支持节点颜色、大小和与原点的距离，以区分论文是否有用以及它的相关程度.

### Get Yourself A Citable Code for Anything

* [Zenodo](https://zenodo.org/)：通过在此处获取 DOI 代码，使 GitHub 上的任何内容都可引用.

### Get Yourself A Unique and Persistent Digital Identifier

* [orcid](http://orcid.org/)：在任何研究工作流程中使用您的 ORCID 标识符，以确保您的工作获得认可.


### Add Citations to Your Code

* [duecredit](https://github.com/duecredit/duecredit)：允许您将装饰器添加到对书目详细信息进行编码的 Python 函数中.

### Open Science

* [Open Science Framework](https://osf.io/)：具有大量集成的开放科学工具.

### Bibliography

* [ReadCube/Papers](https://www.readcube.com/) ：用于参考管理、记笔记等的全平台应用程序. 以前的论文已重新命名为 ReadCube 论文.
* [Mendeley](https://www.mendeley.com/)：具有云存储和 BibTeX 支持的书目参考管理器.
* [Zotero](https://www.zotero.org/)：具有同步和 BibTeX 支持的开源书目参考管理器.
* [Zotero Style Repository](https://www.zotero.org/styles)：找到您需要的任何样式.
* [JabRef](https://www.jabref.org/)：BibTeX 格式的开源参考书目参考管理器.
* [doi2bib](https://www.doi2bib.org/): 从 DOI 中检索 BibTeX 条目.
* [crossref](https://www.crossref.org/)：使研究成果易于查找、引用、链接和评估.
* [org-ref](https://github.com/jkitchin/org-ref): Emacs 中 org-mode 的引用、交叉引用、索引、词汇表和 bibtex 实用程序.

### Tips for Researchers

* [Ten Simple Rules by PLoS One](http://collections.plos.org/ten-simple-rules) ：一系列快速的“十个简单规则”文章，供研究科学家管理职业生涯中的挑战. 文章数量是针对生命科学的，但其余文章对于任何研究人员来说都足够通用.
* 检查 [Academic Resources and Grey Literature List](https://github.com/jivoi/awesome-osint#-academic-resources-and-grey-literature)  [Awesome Open-Source Intelligence List](https://github.com/jivoi/awesome-osint) 供搜索引擎搜索论文.

## Pacifier

> **[Rainy Mood](http://www.rainymood.com/), [Coffitivity](https://coffitivity.com/) 和 [Noisli](http://www.noisli.com/) 是推荐的.**

* [Rainy Mood](http://www.rainymood.com/) (`iOS`, `Android`, `Web`): 阴雨天阴雨心情，简单但具有出色的白噪声； 每天都有新的优美配乐
* [Coffitivity](http://coffitivity.com/) (`iOS`, `Android`, `Web`, `Mac`)：一个相当简单但有用的咖啡店噪音库； 溢价有更多的三个配乐； 优雅的用户界面； 以科学研究为动力
* [Brain.fm](https://www.brain.fm/) （`Web`）：通过音频脑电波训练改善注意力、放松和睡眠. 不是免费的，但值得每一分钱.
* [Noizio](http://noiz.io/)(`iOS`, `Mac`)：一个方便的白噪声工具，保留在您的 Mac 状态栏中.
* [Noisli](http://www.noisli.com/)  （`iOS`, `Android`, `Web`, `Chrome`）：自由混合多首曲目（类似于 Soundrown，但 UI 更好）. 用户可以保存自定义设置以供以后使用. 我个人认为这个比 soundrow 有更好的火音轨.
* [Soundrown](http://soundrown.com/)(`Web`): 多首曲目的自由混音
* [Muji Sleep](http://sleep.muji.net/)（`iOS`，`Android`）
* [A Soft Murmur](http://asoftmurmur.com/) (`Web`)：多轨自由混音； 简单的用户界面； 提供定时器； 提供蜿蜒曲折
* [mynoise](https://mynoise.net/noiseMachines.php) (`iOS`, `Web`)：噪声发生器； 很多选择（实际上太多了）； 详细均衡器
* [Rainy Cafe](http://rainycafe.com/)（`Web`）：没什么好说的，只是雨天的心情和 coffitivity 的结合
* [Sleep Pillow](http://www.clearskyapps.com/portfolio/sleep) (`iOS`, `Mac`)：点击播放风格的预加载场景； 便于使用; 漂亮的设计
* [A youtube audio track of coffee shop (really long)](https://www.youtube.com/watch?v=KZV9FmHOsRg)
* [A youtube audio track of 10 hours rain fall](https://www.youtube.com/watch?v=s_2FDRtFOAw)
* [TaoMix](https://play.google.com/store/apps/details?id=air.com.demute.TaoMix) （`Android`）：混音以集中注意力
* [Calm](http://www.calm.com/)(`iOS`, `Android`, `Web`)：帮助你冷静下来
* [Raining](http://raining.fm)(`iOS`, `Android`, `Web`): 下雨打雷
* [focus@will](https://www.focusatwill.com) （`iOS`, `Android`, `Web`）：音乐来提升你的大脑； 现在付费服务


**其他一些相关的东西**

* [iSerenity](http://www.iserenity.com/)：多种选择，但不是那么好（只是我的感觉）.
* [Rany by simply noise](https://rain.simplynoise.com/): 只是下雨.
* [Natural Sound player](http://www.naturesoundplayer.com/): 很多自然的声音，很酷.
* [NatureSoundsFor.Me](http://naturesoundsfor.me/): 制作你自己的音轨，这么多种声音.
* [White.Noise](http://whitenoise247.net/): 几个不同的轨道
* [ambient mixer](http://www.ambient-mixer.com/)：轻松制作环境声
* [white noise mp3s](http://whitenoisemp3s.com/): 收听和下载



## Online Discussions

### Forums and Q&A's

 &gt; StackExchange.com 是进行专业讨论的好地方. 这是一个例子.

* [Physics.StackExchange](http://physics.stackexchange.com/)
* [Biostars](https://www.biostars.org/): StackOverflow 风格的生物信息学问答网站.
* [NeuroStars](https://neurostars.org/): StackOverflow 风格的神经信息学问答网站.
* [SEQanswers](http://seqanswers.com/): 下一代测序社区论坛.


## Open Source

 &gt; 开源很棒. 使用 git.

### Open Licenses

&gt; 通常，开放式许可证是

* [Open Definition](http://opendefinition.org/): 阅读许可证 [here](http://opendefinition.org/licenses/) 并选择你喜欢的那个.


### Use Licenses

&gt; 要选择许可证，一个简单的方法是使用

* [Choose a License](http://choosealicense.com/) 这可以帮助您通过几个步骤来决定使用哪个许可证.

&gt; CC 许可证可在以下位置找到 [Creative Commons](http://creativecommons.org/) . 如需其他徽章或图标，请查看以下内容.

* [Guokr Badge](https://github.com/opentf/GuokrBadge) ：绿色 CC 许可证徽章.  (**文档为中文.**)


## Data Visualization and Graph Making

### Data Visualization

**JS 和 jQuery**

* [D3 js](http://d3js.org/) (`js`)
* [Highcharts](http://www.highcharts.com/demo/bar-stacked) (`js`)：折线图、面积图、柱形图和条形图、饼图、散点图和气泡图等.
* [Flot](http://www.flotcharts.org/flot/examples/) (`jQuery`)
* [Raphaël](http://raphaeljs.com/) (`js`)
* [JavaScript InfoVis Toolkit](http://philogb.github.io/jit/demos.html) (`js`)
* [Paper.js](http://paperjs.org/) (`js`)


**Python**

* [matplotlib](https://github.com/jbmouret/matplotlib_for_papers)
* [seaborn](https://seaborn.pydata.org/)：统计数据可视化
* [Plotnine](https://plotnine.readthedocs.io): Python 的图形语法
* [ggplot for python](http://ggplot.yhathq.com/)
* [plot.ly](https://plot.ly/ipython-notebooks/)：需要互联网，交互式绘图.
* [bokeh](http://bokeh.pydata.org/en/latest/docs/quickstart.html#quickstart)：需要互联网，交互式绘图.

* [itermplot](https://github.com/daleroberts/itermplot)：Matplotlib 的出色 iTerm2 后端，因此您可以直接在终端中绘图.


### Graph Making

&gt; 应使用专业工具制作专业图表.

* [GeoGebra](http://www.geogebra.org/)（`Cloud`、`Mac`、`Win`、`Linux`、`Android`、`iOS`、`Win Store`）：Geogebra 是一个非常酷的工具，可以制作 2D 和 3D 数学图.
* [LaTeXDraw](https://github.com/arnobl/latexdraw)（`Linux`）：“LaTeX 的矢量绘图编辑器.”
* [TikZ](http://www.texample.net/tikz/)(`LaTeX`)
* [BoxPlotR](http://shiny.chemgrid.org/boxplotr/)(`Web`): A web-tool for generation of box plots.
* [Graphviz](https://www.graphviz.org/)(`Linux,Win,Max,Solaris,FreeBSD`)：开源图形可视化软件.

 &gt; 为您的研究地块选择百分比准确的颜色. 为什么？  ([1](https://github.com/holoviz/colorcet/blob/master/examples/index.ipynb), [2](https://bids.github.io/colormap/))

* [colorcet](https://github.com/holoviz/colorcet) 可用于研究颜色图.

## LaTeX

&gt; 比 Microsoft Word 好得多.

### Tips

* [wikibooks - LaTeX](https://en.wikibooks.org/wiki/LaTeX): 很好的手册.


### Symbols

* [Detexify](http://detexify.kirelabs.org/classify.html): 通过在线绘图找出符号是什么


### Graphing

* [TeX Example](http://www.texample.net/) （提克兹/PGF）


### Fonts

* [Font Catalogue](http://www.tug.dk/FontCatalogue/seriffonts.html)

### Templates

* [LaTeX Templates](http://www.latextemplates.com/)



### References

**数学排版**

* [Math into Type](https://github.com/emptymalei/awesome-research/blob/master/ftp://ftp.ams.org/pub/author-info/documentation/howto/mit-2.pdf) ：这是一本与数学相关的排版的好书. 这是版权材料. 请不要重新分发.


## MISC


### Terminal

* [plot in terminal](https://github.com/glamp/bashplotlib)
* [asciinema](https://asciinema.org/): 命令行录制.
* [bashplot](https://github.com/glamp/bashplotlib): 在终端绘图.
* [fuck](https://github.com/EricFreeman/fuck): 通过输入 fuck 来更正命令.

### Free Multimedia

* [CC Search](https://ccsearch.creativecommons.org/)：CC许可下的图像搜索引擎.
* [Unsplash](https://unsplash.com/)：免费的高分辨率图像.
* [Academicons](https://jpswalsh.github.io/academicons/)
* [Phylopic](http://phylopic.org/)



### More

* [QR Code Generator](https://www.unitag.io/qrcode): Adding a QR code to your poster can help you get more audience.
* [SHIELDS.io](http://shields.io/): 自己做一个漂亮的徽章.
* [TitleCap](http://titlecapitalization.com/): 不知道标题中哪个单词要大写？ [TitleCap](http://titlecapitalization.com/) 适合你.
* [On Being a Scientist](https://www.nap.edu/read/12192/): 负责任的研究行为指南.
* [DiRT Directory](http://dirtdirectory.org/)：供学术使用的数字研究工具的注册表.
* [Online Whiteboard](https://awwapp.com) ：用户可以协作的简单在线白板； 适合在线会议.
* [MapInSeconds.com](http://www.mapinseconds.com/)：通过从电子表格复制粘贴来快速创建具有相应数据的地图.
* [Unpay Wall](http://unpaywall.org/): 合法免费下载研究论文.

-----

这是一个 CC BY-SA 许可的项目. 使用源码！ 保持源代码开放！

![CC BY-SA](https://raw.githubusercontent.com/emptymalei/awesome-research/master/assets/cc_bysa.flat.guokr.png)
