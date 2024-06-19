<div class="github-widget" data-repo="readthedocs-examples/awesome-read-the-docs"></div>
<!--lint ignore awesome-git-repo-age-->
<!--lint disable double-link-->

<!-- title -->

## Awesome Read the Docs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/readthedocs-examples/awesome-read-the-docs/actions/workflows/lint.yaml/badge.svg)](https://github.com/readthedocs-examples/awesome-read-the-docs/actions/workflows/lint.yaml)

<!-- subtitle -->

> A curated list of awesome documentation projects, useful to learn from and for bootstrapping new documentation projects.
> Plus cool real-life usages of Read the Docs.

<!-- image -->

<a href="https://docs.readthedocs.io/en/stable/tutorial/index.html" target="_blank" rel="noopener noreferrer">
  <img src="https://raw.githubusercontent.com/readthedocs-examples/awesome-read-the-docs/master/./readthedocs-logo.svg?sanitize=true" />
</a>

<!-- description -->

Read the Docs is a fully open-source platform that builds and publishes documentation.
Read more on https://about.readthedocs.com.

## Foreword

Many new and exciting documentation projects have emerged in *science and academia*, taking the world of documentation beyond just software projects.
To capture the latest development and trends, we are compiling a list of inspirational uses of documentation technology, especially outside of the traditional field of software documentation.

In addition to showing awesome and real-life Read the Docs projects, a number of [Example Projects](#example-projects) are being built to help people learn and get started.

We hope that this will inspire people writing documentation, developing new documentation projects or updating existing ones.
All projects mentioned here are **open source**, meaning that you can find their source code and understand how it's done.

The list is a work in progress, please feel invited to [contribute](#contributing)!

<!-- TOC -->
<!--lint disable awesome-toc-->
<!--lint enable awesome-toc-->


<!-- CONTENT -->


## Sphinx projects

- [CrateDB](https://crate.io/docs/crate/) - Crate.io has integrated their documentation experience into their general website. There's a total of 15 documentation projects nested. They use a custom theme, [crate-docs-theme](https://github.com/crate/crate-docs-theme) to orchestrate the projects and align them. **#sphinx** **#custom-theme**.
- [django-cms](https://docs.django-cms.org/) - django-cms's developer documentation is as extensive as it's well-organized. It uses the Furo theme. **#sphinx** **#large-project**.
- [Ray](https://docs.ray.io/) - Ray is a documentation project spanning multiple software components. It uses several extensions from the Executable Book project. Features are showcased in [this twitter thread](https://twitter.com/readthedocs/status/1663923671470047234). **#sphinx** **#themes** **#large-project**.
- [Scrapy](https://docs.scrapy.org/) - Embeds a lot of reference snippets and uses `sphinx-hoverxref` for quick reference tooltips. Lots of inspiration to be found in content organization. **#sphinx**.
- [setuptools](https://setuptools.pypa.io/) - Lots of features, using the Furo theme. [Twitter thread](https://twitter.com/readthedocs/status/1546527820150718469) with some examples. **#sphinx** **#themes**.
- [sphinx-needs](https://sphinx-needs.readthedocs.io/) - Documentation of `sphinx-needs`. **#sphinx** **#themes**.
- [sphinx-immaterial](https://sphinx-immaterial.readthedocs.io/) - Documentation of `sphinx-immaterial`, a Material theme for Sphinx, based on Material for MkDocs. **#sphinx** **#themes**.
- [Uberspace](https://manual.uberspace.de/) - Customized sidebar and footer, adding project's branding through custom CSS and HTML to `sphinx_rtd_theme`. Latest version and release date on front page. **#sphinx** **#themes** **#custom-theme**.
- [Wagtail](https://docs.wagtail.org/) - Wagtail is a Django-based CMS with a global community. The documentation spans multiple stakeholders (editors and developers), has it's own beautiful theme and is largely structured around Diátaxis ideals. The [Release Notes](https://docs.wagtail.org/en/stable/releases/index.html) and [Contribution guide](https://docs.wagtail.org/en/stable/contributing/index.html) are remarkable. Wagtail's documentation uses a minimal set of Sphinx extensions. **#sphinx** **#themes** **#diataxis**.
- [Weblate](https://docs.weblate.org/) - Weblate is a translation platform with a large documentation project with many translations and customized Read the Docs theme. Documentation aimed at all segments: users, administrators and developers. Also features an extensive Changelog. **#sphinx** **#themes** **#translation**.

## MkDocs projects

- [Argo CD](https://argo-cd.readthedocs.io/) - Material for MkDocs theme with custom colors and a nice version drop down. Animated product demo and carefully designed sidebar presenting targeted guides for Operators, Users and Developers. **#mkdocs** **#themes** **#large-project**.
- [doc2dash](https://doc2dash.readthedocs.io/) - Material for MkDocs with a custom version provider fully compatible with Read the Docs **#mkdocs** **#themes**.
- [Nautobot](https://docs.nautobot.com/) - Extensive usage of the subprojects feature to organize numerous documentation projects under the same custom domain / landing page. Each subproject has its own release cycle. Features are showcased in [this twitter thread](https://twitter.com/readthedocs/status/1595010133796462593). **#mkdocs** **#themes** **#large-project**.
- [Sidra Data Platform](https://docs.sidra.dev/en/latest/) - Material for MkDocs theme with version selector and search integrated via Read the Docs Addons. **#mkdocs** **#themes** **#business**.
- [The Haskell Tool Stack](https://docs.haskellstack.org/) - A matured MkDocs project using their documentation website as their main website. Notice both the structure and the considerate use of widgets included in Material for MkDocs **#mkdocs** **#themes**.

## API Reference

- [discord.py](https://discordpy.readthedocs.io/) - This projects very rich Python API reference uses custom extension for quick overview tables of attributes and methods + `sphinx-hoverxref` for tooltips with API reference + source link references for GitHub source code. **#apidocs** **#sphinx** **#themes**

## Science projects

- [AiiDA demonstration](https://aiida-qe-demo.readthedocs.io/) - A hardware demo/tutorial written with lots of examples and illustrations. [Behind the scenes](https://github.com/chrisjsewell/aiida-qe-demo), Conda is used by installing mambaforge and storing the setup in `environment.yml`.  **#sphinx** **#jupyter-notebook**
- [Crest Ocean System](https://crest.readthedocs.io/) - Uses sphinx-hoverxref and Executable Book. Video tutorials in text. Lots of embeds, Trello, YouTube and more. **#sphinx** **#themes**
- [jupyter-book](https://jupyterbook.org/) - Jupyter-book automatically creates Sphinx projects from projects that are friendly to Jupyter Notebook users. **#jupyter-notebook** **#sphinx** **#diataxis**.
- [jupyter-sphinx](https://jupyter-sphinx.readthedocs.io/) - Directly executes and renders Jupyter Notebooks in documentation projects. **#jupyter-notebook** **#sphinx**.
- [jupyter-tutorial](https://jupyter-tutorial.readthedocs.io/) - Uses a set of extensions for Sphinx, for instance direct rendering of `.ipynb` files with `nbsphinx`. **#jupyter-notebook** **#sphinx**.
- [msticpy](https://msticpy.readthedocs.io/) - MSTIC Jupyter and Python Security Tools, msticpy is a library for InfoSec investigation and hunting in Jupyter Notebooks. **#jupyter-notebook** **#sphinx**.
- [nbsphinx](https://nbsphinx.readthedocs.io/) - Banner and buttons to view interactive versions of currently displayed `*.ipynb` files using the Binder service. Notice also the awesome PDF version. **#jupyter-notebook** **#sphinx**.
- [poliastro](https://docs.poliastro.space/) - An extensive science project, demonstrating rich use of math formulas, interactive plotting in 3d, ``sphinx-hoverxref``, custom 404s and a nice copy button on code examples. Notice how well the navigation reflects the [Diátaxis framework](https://diataxis.fr/)  **#sphinx** **#diataxis**.
- [SunPy](https://docs.sunpy.org/) - A large documentation project for an open-source package for solar physics. Embeds the main website's menu and uses a custom theme. Extensive changelog and release notes. **#custom-theme**, **sphinx**, **#apidocs**.
- [TorchIO](https://torchio.readthedocs.io/) - An open-source Python library targeting 3D medical images in deep learning. Combines API documentation with usage examples, uses "single version" for a singular "rolling release" documentation. [Screenshots in this Twitter thread](https://twitter.com/readthedocs/status/1570339818806120450). **#themes**, **sphinx**.
- [TomoBank](https://tomobank.readthedocs.io/) - A big list of tomographic datasets and phantoms, featuring especially tables and images and maintained by science community. **#sphinx**.

<!-- END CONTENT -->

## Tag cloud

The categories in this list are intersecting at the following tags:

**#sphinx**, **#mkdocs**, **#themes**, **#custom-theme**, **#jupyter-notebook**, **#diataxis**, **#large-project**, **#apidocs**, **#translation**

## Contributing

[Contributions of any kind welcome, just follow the guidelines](https://github.com/readthedocs-examples/awesome-read-the-docs/blob/master/contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/readthedocs-examples/awesome-read-the-docs/graphs/contributors)!
