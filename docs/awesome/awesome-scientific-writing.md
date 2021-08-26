<div class="github-widget" data-repo="writing-resources/awesome-scientific-writing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Scientific Writing [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

&gt; 科学写作可以扩展到 LaTeX 之外，通过格式、
&gt; 比如
> [Markdown](https://daringfireball.net/projects/markdown/) （及其多种口味），
> [reStructuredText](https://docutils.sourceforge.io/rst.html) 和
> [Jupyter notebooks](https://jupyter.org/).

:bookmark: 表示能够**无缝引用参考文献**.

:link: 表示能够在
document**.



## Word Processors

- [Atom](https://atom.io) - 支持 Markdown 的流行 IDE.
  - [Markdown Preview Enhanced for Atom](https://github.com/shd101wyy/markdown-preview-enhanced) - 潘多克
    Atom 的集成和实用程序.
  - [Autocomplete BibTeX for Atom](https://github.com/apcshields/autocomplete-bibtex) - 对 Atom 的 BibTeX 支持.
- [Marktext](https://marktext.app/) - Markdown 文本编辑器.
- [R Studio](https://github.com/rstudio/rstudio) - R 的 IDE.
  - [bookdown](https://github.com/rstudio/bookdown) - R 包，方便写书和长篇文章，用 R Markdown 报告：书签：：链接：.
  - [R Markdown](https://rmarkdown.rstudio.com/) - R 包在 Markdown 旁边写 R
   ：书签：
   ：关联：.
- [Vim](https://www.vim.org/) - 命令行文本编辑器.
  - [fzf-bibtex](https://github.com/msprev/fzf-bibtex/#readme) - BibTeX 源
    使用 fzf（在 Go 中实现的模糊查找器）的 Vim 集成.
  - [vim-pandoc](https://github.com/vim-pandoc/vim-pandoc) - Vim 的 Pandoc 集成和实用程序.
  - [vim-pandoc-syntax](https://github.com/vim-pandoc/vim-pandoc-syntax) - Vim 的 Pandoc 语法高亮.
- [Visual Studio Code](https://code.visualstudio.com/) - 支持 Markdown 的流行 IDE.
  - [Markdown All in One](https://github.com/yzhang-gh/vscode-markdown/#readme) - 增强的扩展
    VSCode 中的 Markdown 支持，例如预览和自动完成等等.
- [Zettlr](https://www.zettlr.com/) - Markdown 编辑器
   集成了 CSL、BibLaTeX、Pandoc 和许多其他工具
   ：书签：：链接：.

## Bibliography

参考管理器生成引文、BibTeX 和 BibLaTeX 文件.

- [Citation Style Language (CSL) styles](https://editor.citationstyles.org/) - 众包
  拥有超过 9000 种免费 CSL 引文样式和在线
  编辑器来创建新的.
- [JabRef](https://www.jabref.org/) - 开源书目参考管理器.
- [Zotero](https://www.zotero.org/) - 用于收集、组织、引用和的 FOSS 工具
  分享研究.
  - [Better BibTeX for Zotero](https://retorque.re/zotero-better-bibtex/) - 增强
    Zotero 的 BibTeX / BibLaTeX 集成.
  - [ZotFile for Zotero](http://zotfile.com/) - 增强了 Zotero 的 PDF 文件管理.
- [ZoteroBib](https://zbib.org/) - 在线书目参考管理器.

## Illustrations

绘制插图本身已经让许多科学家发疯了. 幸运的是，
有一些正式的语言可以用来创建漂亮的图形.

- [diagrams.net](https://www.diagrams.net/) - 开源、在线、桌面和
  容器可部署图表软件.
- [graphviz](https://graphviz.org/) - 图形和可视化软件
  使用特定于域的 DOT 语言的网络.
- [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/) - 定义简单的图表而不是绘制它们.
- [Vega Lite](https://vega.github.io/vega-lite/examples/) - 定义图表和更复杂的图表.
- [PlantUML](https://plantuml.com/) - 定义 UML 图而不是绘制它们.

## Converters and Filters

补充文件和工具.

- [Cicero](https://cicero.xyz/) - 呈现 HTML 演示文稿的 Python 包
  从 Markdown 源使用 remark 或reveal.js :link:.
- [docutils](https://docutils.sourceforge.io/docs/) - 可以的 Python 包
  将 reStructuredText 转换为各种格式并提供命令行
  工具来做到这一点：链接：.
- [Jupyter Book](https://jupyterbook.org/) - 一个静态站点生成器，可以转换
  将 CommonMark、MyST markdown 和 Jupyter notebook 集合到一个 HTML 网站中.
- [MyST](https://myst-parser.readthedocs.io/en/latest/) - 明显结构化的文本，
  CommonMark markdown 的超集，具有类似 reStructuredText 的功能.
- [nbconvert](https://nbconvert.readthedocs.io/en/latest/) - 转换 Jupyter
  笔记本到 `reveal.js` 演示文稿、PDF、HTML、Markdown、
  reStructuredText 等.
  - [bookbook](https://github.com/takluyver/bookbook/#readme) - 实验性的 Python
    扩展“nbconvert”并添加交叉引用能力的包
    在笔记本内和笔记本之间：链接：.
  - [ipypublish](https://github.com/chrisjsewell/ipypublish/#readme) - 工作流程
    创建和编辑可出版的科学报告和演示文稿，
    从一个或多个 Jupyter Notebook 中，无需离开浏览器：书签：
    ：关联：.
- [pandoc](https://pandoc.org/MANUAL) - 用于转换的 Haskell 库
  一种标记格式到另一种格式，以及使用此格式的命令行工具
  图书馆：书签：：链接：.
  - [Academic Markdown](https://github.com/smathot/academicmarkdown#readme) - 在 Pandoc 上的 Python 包装器，带有专门的扩展来解析某些
    元素，使其成为 Pandoc Markdown 风格的超集：书签：
    ：关联：.
  - [Pandoc filters](https://github.com/jgm/pandoc/wiki/Pandoc-Filters) - 清单
    pandoc 的插件，它实现了额外的功能，例如引用和
    交叉引用.
  - [Panflute](http://scorreia.com/software/panflute/) - Pythonic 替代品
    到约翰麦克法兰的 pandocfilters.

## Spell Checking and Linting

- [GNU Aspell](http://aspell.net/) - 命令行拼写检查器.
- [Hunspell](http://hunspell.github.io/) - 命令行拼写检查器.
- [LanguageTool](https://languagetool.org/) - 开源语法、风格和
 拼写检查程序.
- [Markdown lint tool](https://github.com/markdownlint/markdownlint) - 降价功能区.
- [proselint](http://proselint.com/) - 散文短绒.
- [remarklint](https://github.com/remarkjs/remark-lint) - 降价功能区.
- [restructuredtext-lint](https://github.com/twolfson/restructuredtext-lint) - reStructuredText linter.
- [textlint](https://textlint.github.io/) - 用于文本的可插入 linting 工具
 和降价.
- [textidote](https://sylvainhalle.github.io/textidote/) - 拼写、语法和
 LaTeX 文档的样式检查.
- [Vale](https://errata-ai.github.io/vale/) - 免费、开源的 linter
 散文构建时考虑了速度和可扩展性.
- [write-good](https://github.com/btford/write-good) - 用于英语的天真 linter
 散文.

## Templates

可重用的极简示例.

### Articles

- [Pandoc Markdown-LaTeX
   Boilerplate](https://github.com/davecap/markdown-latex-boilerplate/#readme) - Demonstrate
   如何将 Pandoc 与现有的 LaTeX 模板集成
   需要一些样板代码（即 LaTeX 前导码），从而避免
   `latexmk` 依赖.
- [scientific-markdown](https://github.com/JensErat/scientific-markdown/#readme) - 例子
   将 Markdown 用于使用 Pandoc 的科学出版物和
   `latexmk`.
- [Steve's R Markdown Templates](https://github.com/svmiller/svm-r-markdown-templates/) - 学术手稿、备忘录、Beamer 演示文稿、教学大纲和简历.

### Presentations

- [pandoc-starter](https://github.com/jez/pandoc-starter/#readme) - 模板
   使用 Markdown 文件和 Makefiles 的文章、Beamer 演示文稿等
   开始使用 Pandoc.
- [slides](https://github.com/cgroll/slides/#readme) - 生成`reveal.js`的演示
   使用 Pandoc 进行演示.

### Books

- [bookdown-demo](https://github.com/rstudio/bookdown-demo/#readme) - 最小
   基于 R Markdown 和 bookdown 的书籍示例.
- [Eisvogel](https://github.com/Wandmalfarbe/pandoc-latex-template) - 干净的学术 pandoc LaTeX 模板.
- [撰写博士论文的模板
   Markdown](https://github.com/tompollard/phd_thesis_markdown#readme) - Clean
   组织文件以提供撰写博士论文的框架
   主要是 Markdown 加一点 LaTeX，并用 Pandoc 编译.

## Tutorials

如何为科学目的生成文章和演示文稿.

- [Book on Riemann solvers](https://github.com/clawpack/riemann_book/#readme) - 这个
   示例使用自定义的 `nbconvert` 模板并展示了如何存储您
   notebooks with no output (for version control) while automatically executing
   它们在运行 `bookbook` 之前，以便 PDF 和 HTML 版本包括
   输出.
- [Dennis Tenen and Grant Wythoff](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown) - 使用 Pandoc 和 Markdown 的纯文本可持续作者.
- [Katrin Leinweber 的博士学位.
   thesis](https://github.com/katrinleinweber/PhD-thesis/#readme) - Automated
   工作流程涉及多种工具，但主要是 Pandoc、`latexmk` 和
   学术降价.
- [Scott Selisker](http://u.arizona.edu/~selisker/post/workflow/) - 使用 Atom 进行学术写作的纯文本工作流程.
- [教学与学习
   Jupyter](https://github.com/jupyter4edu/jupyter-edu-book/#readme) - Book
   用 R Markdown、bookdown 编写，也呈现为 HTML、PDF 和
   电子版.
- [使用 Emacs 为 ACPD 撰写科学论文
   Org-mode](https://www.draketo.de/english/emacs/writing-papers-in-org-mode-acpd) - 详细
   通过与 LaTeX 无缝集成来创作论文的教程
   组织模式中的命令.

## Other Lists

- [Awesome Jupyter](https://github.com/markusschanta/awesome-jupyter/#renderingpublishingconversion)
- [Awesome LaTeX](https://github.com/egeerardyn/awesome-LaTeX/#readme)
- [Awesome Markdown](https://github.com/BubuAnabelas/awesome-markdown/#readme)
- [Delightful Open Science](https://codeberg.org/teaserbot-labs/delightful-open-science)

### Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/writing-resources/awesome-scientific-writing/blob/master/CONTRIBUTING.md) 第一的.
