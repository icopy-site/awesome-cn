<div class="github-widget" data-repo="writing-resources/awesome-scientific-writing"></div>
## Awesome Scientific Writing [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

&gt; 科学写作可以超越 LaTeX，格式使之成为可能，
&gt; 如
> [Markdown](https://daringfireball.net/projects/markdown/) （及其多种口味），
> [reStructuredText](https://docutils.sourceforge.io/rst.html) 和
> [Jupyter notebooks](https://jupyter.org/).

:bookmark: 意味着能够**无缝引用参考文献**.

:link: 意味着能够 ** 交叉引用图表和部分
document**.



## Word Processors

- [Atom](https://atom.io) - 支持 Markdown 的流行 IDE.
  - [Markdown Preview Enhanced for Atom](https://github.com/shd101wyy/markdown-preview-enhanced) - 潘多克
    Atom 的集成和实用程序.
  - [Autocomplete BibTeX for Atom](https://github.com/apcshields/autocomplete-bibtex) - BibTeX 支持 Atom.
- [Marktext](https://github.com/marktext/marktext) - 降价文本编辑器.
- [R Studio](https://github.com/rstudio/rstudio) - R 的 IDE.
  - [bookdown](https://github.com/rstudio/bookdown) - 便于编写书籍和长篇文章的 R 包，带有 R Markdown 的报告：书签：：链接：.
  - [R Markdown](https://rmarkdown.rstudio.com/) - R 包在 Markdown 旁边写 R
   ：书签：
   ：关联：.
- [Vim](https://www.vim.org/) - 命令行文本编辑器.
  - [fzf-bibtex](https://github.com/msprev/fzf-bibtex/#readme) - 中文提供源
    与使用 fzf（Go 中实现的模糊查找器）的 Vim 集成.
  - [vim-pandoc](https://github.com/vim-pandoc/vim-pandoc) - Vim 的 Pandoc 集成和实用程序.
  - [vim-pandoc-syntax](https://github.com/vim-pandoc/vim-pandoc-syntax) - Vim 的 Pandoc 语法突出显示.
- [Visual Studio Code](https://code.visualstudio.com/) - 支持 Markdown 的流行 IDE.
  - [Markdown All in One](https://github.com/yzhang-gh/vscode-markdown/#readme) - 增强扩展
    VSCode 中的 Markdown 支持，例如预览和自动完成等等.
- [Zettlr](https://www.zettlr.com/) - Markdown 编辑器
   集成了CSL、BibLaTeX、Pandoc等众多工具
   ：书签：：链接：.

## Bibliography

用于生成引文、BibTeX 和 BibLaTeX 文件的参考文献管理器.

- [Citation Style Language (CSL) styles](https://editor.citationstyles.org/) - 众包
  包含 9000 多种免费 CSL 引文样式和在线
  编辑器创建新的.
- [JabRef](https://www.jabref.org/) - 开源书目参考管理器.
- [Zotero](https://www.zotero.org/) - 用于收集、组织、引用和发布的 FOSS 工具
  分享研究.
  - [Better BibTeX for Zotero](https://retorque.re/zotero-better-bibtex/) - 增强
    Zotero 的 BibTeX / BibLaTeX 集成.
  - [ZotFile for Zotero](http://zotfile.com/) - 增强了 Zotero 的 PDF 文件管理.
- [ZoteroBib](https://zbib.org/) - 在线书目参考管理器.

## Illustrations

绘制插图本身已使许多科学家发疯. 幸运的是，
有一些正式的语言可以用来创建漂亮的图形.

- [diagrams.net](https://www.diagrams.net/) - 开源、在线、桌面和
  容器可部署图表软件.
- [graphviz](https://graphviz.org/) - 图形可视化软件和
  使用特定领域 DOT 语言的网络.
- [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/) - 定义简单的图表而不是绘制它们.
- [Vega Lite](https://vega.github.io/vega-lite/examples/) - 定义图表和更复杂的图表.
- [PlantUML](https://plantuml.com/) - 定义 UML 图而不是绘制它们.

## Converters and Filters

补充文件和工具.

- [Cicero](https://cicero.xyz/) - 呈现 HTML 演示文稿的 Python 包
  来自 Markdown 源代码，使用 remark 或 reveal.js :link:.
- [docutils](https://docutils.sourceforge.io/docs/) - Python包可以
  将 reStructuredText 转换为各种格式并提供命令行
  工具来做到这一点：链接：.
- [Jupyter Book](https://jupyterbook.org/en/stable/) - 可转换的静态站点生成器
  CommonMark、MyST markdown 和 Jupyter notebooks 的集合到一个 HTML 网站中.
- [MyST](https://myst-parser.readthedocs.io/en/latest/) - 明显结构化的文本，
  CommonMark 降价的超集，具有类似 reStructuredText 的功能.
- [nbconvert](https://nbconvert.readthedocs.io/en/latest/) - 转换 Jupyter
  notebooks 到 `reveal.js` 演示文稿，PDF，HTML，Markdown，
  重组文本等等.
- [pandoc](https://pandoc.org/MANUAL) - 用于转换的 Haskell 库
  一种标记格式转换为另一种标记格式，以及使用此标记格式的命令行工具
  图书馆：书签：：链接：.
  - [Academic Markdown](https://github.com/smathot/academicmarkdown#readme) - Pandoc 上的 Python 包装器，具有专门的扩展来解析某些
    元素，使其成为 Pandoc Markdown 风格的超集：书签：
    ：关联：.
  - [Pandoc filters](https://github.com/jgm/pandoc/wiki/Pandoc-Filters) - 列表
    pandoc 的插件，它实现了额外的功能，例如引用和
    交叉引用.
  - [Panflute](http://scorreia.com/software/panflute/) - Pythonic 替代品
    到 John MacFarlane 的 pandocfilters.
- [Quarto](https://quarto.org)  - 将 R Markdown 和 Jupyter 笔记本编译为 PDF、幻灯片和网站. 支持 R、Python 和 Julia :bookmark: :link:.

## Spell Checking and Linting

- [GNU Aspell](http://aspell.net/) - 命令行拼写检查器.
- [Hunspell](http://hunspell.github.io/) - 命令行拼写检查器.
- [LanguageTool](https://languagetool.org/) - 开源语法、风格和
 拼写检查器.
- [Markdown lint tool](https://github.com/markdownlint/markdownlint) - 降价棉绒.
- [proselint](http://proselint.com/) - 散文短绒.
- [remarklint](https://github.com/remarkjs/remark-lint) - 降价棉绒.
- [restructuredtext-lint](https://github.com/twolfson/restructuredtext-lint) - 重组文本 linter.
- [textlint](https://textlint.github.io/) - 可插入的文本检查工具
 和降价.
- [textidote](https://sylvainhalle.github.io/textidote/) - 拼写、语法和
 LaTeX 文档的样式检查.
- [Vale](https://github.com/errata-ai/vale) - 免费的开源 linter
 考虑到速度和可扩展性而构建的散文.
- [write-good](https://github.com/btford/write-good) - 英语的朴素 linter
 散文.

## Templates

可重复使用的简约示例.

### Articles

- [Pandoc Markdown-LaTeX
   Boilerplate](https://github.com/davecap/markdown-latex-boilerplate/#readme) - Demonstrate
   如何将 Pandoc 与现有的 LaTeX 模板集成
   需要一些样板代码（即 LaTeX 序言），从而避免
   `latexmk` 依赖.
- [scientific-markdown](https://github.com/JensErat/scientific-markdown/#readme) - Example
   将 Markdown 用于使用 Pandoc 和
   `latexmk`.
- [Steve's R Markdown Templates](https://github.com/svmiller/svm-r-markdown-templates/) - 学术手稿、备忘录、Beamer 演示文稿、教学大纲和简历.

### Presentations

- [pandoc-starter](https://github.com/jez/pandoc-starter/#readme) - 模板
   文章、Beamer 演示文稿等使用 Markdown 文件和 Makefiles
   开始使用 Pandoc.
- [slides](https://github.com/cgroll/slides/#readme) - 生成 `reveal.js` 的演示
   使用 Pandoc 的演示文稿.

### Books

- [bookdown-demo](https://github.com/rstudio/bookdown-demo/#readme) - 最小
   基于 R Markdown 和 bookdown 的书籍示例.
- [Eisvogel](https://github.com/Wandmalfarbe/pandoc-latex-template) - 干净的学术 pandoc LaTeX 模板.
- [用于撰写博士论文的模板
   Markdown](https://github.com/tompollard/phd_thesis_markdown#readme) - Clean
   组织文件，为撰写博士论文提供一个框架
   主要是 Markdown 和一点点 LaTeX，并用 Pandoc 编译.

## Tutorials

如何为科学目的生成文章和演示文稿.

- [3 frameworks into one — Write your next paper with R Studio!](https://www.ds-econ.com/write-your-whole-paper-in-r-it-is-better/) - 文章概述了结合 R Markdown（bookdown）、Zotero（文献管理）和 Notion（研究论文笔记）撰写学术论文的工作流程. 
- [Book on Riemann solvers](https://github.com/clawpack/riemann_book/#readme) - 这
   示例使用自定义 `nbconvert` 模板并展示如何存储您
   自动执行时没有输出（用于版本控制）的笔记本
   它们在运行 bookbook 之前，以便 PDF 和 HTML 版本包括
   输出.
- [Dennis Tenen and Grant Wythoff](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown) - 使用 Pandoc 和 Markdown 的纯文本可持续作者身份.
- [Heads up! Quarto is here to stay. Immediately combine R & Python in your next document](https://www.ds-econ.com/quarto/)  - 总结 Quarto 的功能、使用它的原因以及它与 R Markdown 的比较. 还包含 M1 Mac 用户如何解决常见网纹问题的提示.
- [Katrin Leinweber 博士
   thesis](https://github.com/katrinleinweber/PhD-thesis/#readme) - Automated
   涉及多个工具的工作流程，但主要是 Pandoc、`latexmk` 和
   学术降价.
- [Scott Selisker](http://u.arizona.edu/~selisker/post/workflow/) - 使用 Atom 进行学术写作的纯文本工作流程.
- [教学与学习
   Jupyter](https://github.com/jupyter4edu/jupyter-edu-book/#readme) - Book
   用 R Markdown、bookdown 编写，也呈现为 HTML、PDF 和
   电子书.
- [Write your dissertation in RMarkdown](https://ourcodingclub.github.io/tutorials/rmarkdown-dissertation/) - 创建复杂 pdf 文档的分步指南，包括文本、图形、参考、图像、格式等.
- [使用 Emacs 为 ACPD 撰写科学论文
   组织模式](https://www.draketo.de/english/emacs/writing-papers-in-org-mode-acpd) - 详细
   通过与 LaTeX 无缝集成来创作论文的教程
   Org 模式下的命令.

## Other Lists

- [Awesome Jupyter](https://github.com/markusschanta/awesome-jupyter/#renderingpublishingconversion)
- [Awesome LaTeX](https://github.com/egeerardyn/awesome-LaTeX/#readme)
- [Awesome Markdown](https://github.com/BubuAnabelas/awesome-markdown/#readme)
- [Delightful Open Science](https://codeberg.org/teaserbot-labs/delightful-open-science)

### Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/writing-resources/awesome-scientific-writing/blob/master/CONTRIBUTING.md) 第一的.
