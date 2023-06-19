<div class="github-widget" data-repo="readthedocs-examples/awesome-read-the-docs"></div>
<!--lint ignore awesome-git-repo-age-->
<!--lint disable double-link-->

<!-- title -->

## Awesome Read the Docs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/readthedocs-examples/awesome-read-the-docs/actions/workflows/lint.yaml/badge.svg)](https://github.com/readthedocs-examples/awesome-read-the-docs/actions/workflows/lint.yaml)

<!-- subtitle -->

&gt; 很棒的文档项目的精选列表，有助于学习和引导新的文档项目.
&gt; 加上 Read the Docs 的酷炫现实生活用法.

<!-- image -->

<a href="https://docs.readthedocs.io/en/stable/tutorial/index.html" target="_blank" rel="noopener noreferrer">
  <img src="https://raw.githubusercontent.com/readthedocs-examples/awesome-read-the-docs/master/./readthedocs-logo.svg?sanitize=true" />
</a>

<!-- description -->

Read the Docs 是一个完全开源的平台，可以构建和发布文档.
阅读更多 [readthedocs.org](https://readthedocs.org/) 和 [readthedocs.com](https://readthedocs.com/) （阅读商业文档）.

## Foreword

*科学界和学术界*出现了许多新的和令人兴奋的文档项目，使文档世界不仅仅是软件项目.
为了捕捉最新的发展和趋势，我们正在编制一份文档技术的鼓舞人心的用途清单，尤其是在传统的软件文档领域之外.

除了展示真棒和真实的 Read the Docs 项目外，还有一些 [Example Projects](#example-projects) 旨在帮助人们学习和入门.

我们希望这会激励人们编写文档、开发新文档项目或更新现有文档.
这里提到的所有项目都是**开源**，这意味着您可以找到它们的源代码并了解它是如何完成的.

该列表是一项正在进行的工作，请感觉受邀 [contribute](#contributing)!

<!-- TOC -->
<!--lint disable awesome-toc-->
<!--lint enable awesome-toc-->


<!-- CONTENT -->


## Sphinx projects

- [CrateDB](https://crate.io/docs/crate/)  - Crate.io 已将他们的文档体验整合到他们的通用网站中. 总共嵌套了 15 个文档项目. 他们使用自定义主题， [crate-docs-theme](https://github.com/crate/crate-docs-theme) to orchestrate the projects and align them. **#sphinx** **#custom-theme**.
- [Ray](https://docs.ray.io/)  - Ray 是一个跨越多个软件组件的文档项目. 它使用了 Executable Book 项目的几个扩展. 功能展示在 [this twitter thread](https://twitter.com/readthedocs/status/1663923671470047234). **#sphinx** **#themes** **#large-project**.
- [Scrapy](https://docs.scrapy.org/) - Embeds a lot of reference snippets and uses `sphinx-hoverxref` for quick reference tooltips. Lots of inspiration to be found in content organization. **#sphinx**.
- [setuptools](https://setuptools.pypa.io/) - 许多功能，使用 Furo 主题. [Twitter thread](https://twitter.com/readthedocs/status/1546527820150718469) with some examples. **#sphinx** **#themes**.
- [sphinx-needs](https://sphinx-needs.readthedocs.io/) - Documentation of `sphinx-needs`. **#sphinx** **#themes**.
- [sphinx-immaterial](https://sphinx-immaterial.readthedocs.io/) - Documentation of `sphinx-immaterial`, a Material theme for Sphinx, based on Material for MkDocs. **#sphinx** **#themes**.
- [Uberspace](https://manual.uberspace.de/) - Customized sidebar and footer, adding project's branding through custom CSS and HTML to `sphinx_rtd_theme`. Latest version and release date on front page. **#sphinx** **#themes** **#custom-theme**.
- [Wagtail](https://docs.wagtail.org/) - Wagtail is a Django-based CMS with a global community. The documentation spans multiple stakeholders (editors 和 developers), has it's own beautiful theme 和 is largely structured around Diátaxis ideals. The [Release Notes](https://docs.wagtail.org/en/stable/releases/index.html) 和 [Contribution guide](https://docs.wagtail.org/en/stable/contributing/index.html) are remarkable. Wagtail's documentation uses a minimal set of Sphinx extensions. **#sphinx** **#themes** **#diataxis**.
- [Weblate](https://docs.weblate.org/) - Weblate is a translation platform with a large documentation project with many translations and customized Read the Docs theme. Documentation aimed at all segments: users, administrators and developers. Also features an extensive Changelog. **#sphinx** **#themes** **#translation**.

## MkDocs projects

- [Argo CD](https://argo-cd.readthedocs.io/) - Material for MkDocs theme with custom colors and a nice version drop down. Animated product demo and carefully designed sidebar presenting targeted guides for Operators, Users and Developers. **#mkdocs** **#themes** **#large-project**.
- [doc2dash](https://doc2dash.readthedocs.io/) - Material for MkDocs with a custom version provider fully compatible with Read the Docs **#mkdocs** **#themes**.
- [Nautobot](https://docs.nautobot.com/)  - 广泛使用子项目功能，在同一自定义域/登录页面下组织大量文档项目. 每个子项目都有自己的发布周期. 功能展示在 [this twitter thread](https://twitter.com/readthedocs/status/1595010133796462593). **#mkdocs** **#themes** **#large-project**.
- [The Haskell Tool Stack](https://docs.haskellstack.org/) - A matured MkDocs project using their documentation website as their main website. Notice both the structure and the considerate use of widgets included in Material for MkDocs **#mkdocs** **#themes**.

## API Reference

- [discord.py](https://discordpy.readthedocs.io/) - This projects very rich Python API reference uses custom extension for quick overview tables of attributes and methods + `sphinx-hoverxref` for tooltips with API reference + source link references for GitHub source code. **#apidocs** **#sphinx** **#themes**

## Science projects

- [AiiDA demonstration](https://aiida-qe-demo.readthedocs.io/) - 包含大量示例和插图的硬件演示/教程. [Behind the scenes](https://github.com/chrisjsewell/aiida-qe-demo), Conda is used by installing mambaforge and storing the setup in `environment.yml`.  **#sphinx** **#jupyter-notebook**
- [Crest Ocean System](https://crest.readthedocs.io/) - Uses sphinx-hoverxref and Executable Book. Video tutorials in text. Lots of embeds, Trello, YouTube and more. **#sphinx** **#themes**
- [jupyter-book](https://jupyterbook.org/) - Jupyter-book automatically creates Sphinx projects from projects that are friendly to Jupyter Notebook users. **#jupyter-notebook** **#sphinx** **#diataxis**.
- [jupyter-sphinx](https://jupyter-sphinx.readthedocs.io/) - Directly executes and renders Jupyter Notebooks in documentation projects. **#jupyter-notebook** **#sphinx**.
- [jupyter-tutorial](https://jupyter-tutorial.readthedocs.io/) - Uses a set of extensions for Sphinx, for instance direct rendering of `.ipynb` files with `nbsphinx`. **#jupyter-notebook** **#sphinx**.
- [msticpy](https://msticpy.readthedocs.io/) - MSTIC Jupyter and Python Security Tools, msticpy is a library for InfoSec investigation and hunting in Jupyter Notebooks. **#jupyter-notebook** **#sphinx**.
- [nbsphinx](https://nbsphinx.readthedocs.io/) - Banner and buttons to view interactive versions of currently displayed `*.ipynb` files using the Binder service. Notice also the awesome PDF version. **#jupyter-notebook** **#sphinx**.
- [poliastro](https://docs.poliastro.space/)  - 一个广泛的科学项目，展示了数学公式的丰富使用、3d 交互式绘图、``sphinx-hoverxref``、自定义 404s 和代码示例上的漂亮复制按钮. 注意导航如何很好地反映了 [Diátaxis framework](https://diataxis.fr/)  **#sphinx** **#diataxis**.
- [SunPy](https://docs.sunpy.org/) - A large documentation project for an open-source package for solar physics. Embeds the main website's menu and uses a custom theme. Extensive changelog and release notes. **#custom-theme**, **sphinx**, **#apidocs**.
- [TorchIO](https://torchio.readthedocs.io/)  - 一个针对深度学习中的 3D 医学图像的开源 Python 库. 将 API 文档与使用示例相结合，使用“单一版本”作为单一的“滚动发布”文档. [Screenshots in this Twitter thread](https://twitter.com/readthedocs/status/1570339818806120450). **#themes**, **sphinx**.
- [TomoBank](https://tomobank.readthedocs.io/) - A big list of tomographic datasets and phantoms, featuring especially tables and images and maintained by science community. **#sphinx**.

<!-- END CONTENT -->

## Example projects

- [Basic Sphinx example](https://github.com/readthedocs-examples/example-sphinx-basic) - Basic example of using Sphinx on Read the Docs. **#sphinx**.
- [Basic MkDocs example](https://github.com/readthedocs-examples/example-mkdocs-basic) - Basic example of using MkDocs on Read the Docs. **#mkdocs**.
- [Jupyter Book example](https://github.com/readthedocs-examples/example-jupyter-book) - Using Jupyter Book on Read the Docs with popular extensions. **#jupyter-notebook** **#sphinx**.

## Tag cloud

此列表中的类别在以下标签处相交：

**#sphinx**, **#mkdocs**, **#themes**, **#custom-theme**, **#jupyter-notebook**, **#diataxis**, **#large-project**, **#apidocs**, **#translation**

## Contributing

[Contributions of any kind welcome, just follow the guidelines](https://github.com/readthedocs-examples/awesome-read-the-docs/blob/master/contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/readthedocs-examples/awesome-read-the-docs/graphs/contributors)!
