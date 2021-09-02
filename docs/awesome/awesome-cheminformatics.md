<div class="github-widget" data-repo="hsiaoyi0504/awesome-cheminformatics"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cheminformatics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; 化学信息学（也称为化学信息学、化学信息学和化学信息学）是将计算机和信息技术应用于化学领域的一系列问题.— [Wikipedia](https://en.wikipedia.org/wiki/Cheminformatics)

精选的化学信息学软件、资源和库列表. 主要基于命令行，免费或开源. 请随意 [contribute](https://github.com/hsiaoyi0504/awesome-cheminformatics/blob/master/CONTRIBUTING.md) !



## Applications

<a id="app-visualization"></a>
### Visualization

* [PyMOL](https://sourceforge.net/projects/pymol/) - Python-enhanced molecular graphics tool.
* [Jmol](http://jmol.sourceforge.net/) - 基于浏览器的 HTML5 查看器和用于 3D 化学结构的独立 Java 查看器.
* [VMD](http://www.ks.uiuc.edu/Research/vmd/) - 使用 3-D 图形和内置脚本显示、动画和分析大型生物分子系统的分子可视化程序.
* [Chimera](https://www.cgl.ucsf.edu/chimera/) - 用于交互式分子可视化和分析的高度可扩展程序. [Source](https://www.cgl.ucsf.edu/chimera/docs/sourcecode.html) 可用.
* [ChimeraX](https://www.cgl.ucsf.edu/chimerax/)  - 继 UCSF Chimera 之后的下一代分子可视化程序. 来源可用 [here](https://www.cgl.ucsf.edu/chimerax/docs/devel/conventions.html).
* [DataWarrior](http://www.openmolecules.org/datawarrior/index.html) - 将动态图形视图和交互式行过滤与化学智能相结合的数据可视化和分析程序.

<a id="app-cmd"></a>
### Command Line Tools

* [Open Babel](http://openbabel.org/wiki/Main_Page) - 旨在讲多种化学数据语言的化学工具箱.
* [MayaChemTools](http://www.mayachemtools.org/index.html) - 支持日常计算发现需求的 Perl 和 Python 脚本、模块和类的集合.
* [Packmol](http://m3g.iqm.unicamp.br/packmol/home.shtml) - 通过填充优化进行分子动力学模拟的初始配置.
* [BCL::Commons](http://meilerlab.org/index.php/bclcommons/show/b_apps_id/1)

<a id="app-docking"></a>
### Docking

* [AutoDock Vina](http://vina.scripps.edu/) - 分子对接和虚拟筛选.
* [smina](https://sourceforge.net/projects/smina/) - 定制 [AutoDock Vina](http://vina.scripps.edu/) 更好地支持评分功能开发和高性能能源最小化.

<a id="app-virtual"></a>
### Virtual Machine

* [myChEMBL](http://chembl.blogspot.com/2015/07/mychembl-20-has-landed.html) - 使用开源软件（Ubuntu、PostgreSQL、RDKit）构建的 ChEMBL 版本
* [3D e-Chem Virtual Machine](https://github.com/3D-e-Chem/3D-e-Chem-VM) - 

## Libraries

<a id="lib-general"></a>
### General Purpose

* [RDKit](http://www.rdkit.org/) - 用 C++ 和 Python 编写的化学信息学和机器学习软件的集合.
* [Indigo](https://github.com/epam/Indigo) - Universal molecular toolkit that can be used for molecular fingerprinting, substructure search, and molecular visualization written in C++ package, with Java, C#, and Python wrappers.
* [CDK (Chemistry Development Kit)](https://sourceforge.net/projects/cdk/) - 结构化学和生物信息学算法，用 Java 实现.
* [ChemmineR](https://www.bioconductor.org/packages/release/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html) - 用于在 R 中分析类药物小分子数据的化学信息学包.
* [ChemPy](https://github.com/bjodah/chempy) - 一个对化学有用的 Python 包（主要是物理/无机/分析化学）
* [MolecularGraph.jl](https://github.com/mojaie/MolecularGraph.jl) - 在 Julia 中完全实现的基于图的分子建模和化学信息学分析工具包
* [datamol](https://github.com/datamol-org/datamol) ： - 分子操纵变得容易. 构建在 RDKit 之上的轻量级包装器.

<a id="lib-format"></a>
### Format Checking

* [ChEMBL_Structure_Pipeline (formerly standardiser)](https://github.com/chembl/ChEMBL_Structure_Pipeline) - 旨在提供标准化分子的简单方法的工具，作为分子建模练习的前奏.
* [MolVS](https://github.com/mcs07/MolVS) - 分子验证和标准化基于 [RDKit](http://www.rdkit.org/).
* [rd_filters](https://github.com/PatWalters/rd_filters) - 使用 RDKit 和 ChEMBL 运行结构警报的脚本

<a id="lib-visualization"></a>
### Visualization

* [Kekule.js](http://partridgejiang.github.io/Kekule.js/) - 前端 JavaScript 库，用于提供在 Web 浏览器上表示、绘制、编辑、比较和搜索分子结构的能力.
* [3Dmol.js](https://github.com/3dmol/3Dmol.js) - 一个面向对象的、基于 webGL 的 JavaScript 库，用于在线分子可视化.
* [JChemPaint](https://github.com/JChemPaint/jchempaint) - 基于化学二维结构编辑器应用程序/小程序 [Chemistry Development Kit](https://sourceforge.net/projects/cdk/).
* [rdeditor](https://github.com/EBjerrum/rdeditor) - 使用 PySide 的简单 RDKit 分子编辑器 GUI.
* [nglviewer](http://nglviewer.org/nglview/latest/) - Jupyter 笔记本的交互式分子图形.
* [RDKit.js](https://www.npmjs.com/package/@rdkit/rdkit) - 来自 RDKit 的化学信息学功能的官方 JavaScript 发行版 - 化学信息学的 C++ 库.

<a id="lib-des"></a>
### Molecular Descriptors

* [mordred](https://github.com/mordred-descriptor/mordred) - 基于的分子描述符计算器 [RDKit](http://www.rdkit.org/).
* [DescriptaStorus](https://github.com/bp-kelley/descriptastorus) - 用于机器学习的描述符计算（化学）和（可选）存储.
* [mol2vec](https://github.com/samoturk/mol2vec) - 分子子结构的矢量表示.
* [Align-it](http://silicos-it.be.s3-website-eu-west-1.amazonaws.com/software/align-it/1.0.4/align-it.html#alignit-generating-pharmacophore-points) - 根据其药效团排列分子.
* [Rcpi](https://nanx.me/Rcpi/index.html) - R/Bioconductor 包，用于生成蛋白质、化合物及其相互作用的各种描述符.

<a id="lib-ml"></a>
### Machine Learning

* [DeepChem](https://github.com/deepchem/deepchem) - 基于 Tensorflow 的化学深度学习库
* [ChemML](https://github.com/hachmannlab/chemml)  - ChemML 是一个机器学习和信息学程序套件，用于化学和材料数据的分析、挖掘和建模.  （基于 Tensorflow）
* [OpenChem](https://github.com/Mariewelt/OpenChem) - OpenChem 是一个用于计算化学的深度学习工具包，带有 PyTorch 后端.
* [chainer-chemistry](https://github.com/pfnet-research/chainer-chemistry) - 生物学和化学深度学习图书馆.
* [pytorch-geometric](https://pytorch-geometric.readthedocs.io/en/latest/) - PyTorch 库提供了许多图卷积算法的实现.
* [chemmodlab](https://github.com/jrash/ChemModLab) - 在 R 中拟合和评估机器学习模型的化学信息学建模实验室.
* [Summit](https://github.com/sustainable-processes/summit) - 使用机器学习优化化学反应的 python 包（包含 10 种算法 + 几个基准）.

<a id="lib-web"></a>
### Web APIs

* [webchem](https://github.com/ropensci/webchem) - 来自网络的化学信息.
* [PubChemPy](http://pubchempy.readthedocs.io) - PubChem PUG REST API 的 Python 包装器.
* [ChemSpiPy](http://chemspipy.readthedocs.org) - ChemSpider API 的 Python 包装器.
* [CIRpy](http://cirpy.readthedocs.org/) - Python 包装器 [NCI Chemical Identifier Resolver (CIR)](https://cactus.nci.nih.gov/chemical/structure).
* [Beaker](https://github.com/chembl/chembl_beaker) - [RDKit](http://www.rdkit.org/) 和 [OSRA](https://cactus.nci.nih.gov/osra/) 在里面 [Bottle](http://bottlepy.org/docs/dev/) 在 [Tornado](http://www.tornadoweb.org/en/stable/).
* [chemminetools](https://github.com/girke-lab/chemminetools) - 基于 Django 的用于小分子分析的开源 Web 框架.

<a id="lib-db"></a>
### Databases

* [razi](https://github.com/rvianello/razi) - SQLAlchemy 数据库的化学信息扩展.

<a id="lib-dock"></a>
### Docking
* [Rosetta](https://www.rosettacommons.org/docs/latest/Home)  - 用于模拟大分子结构的综合软件套件. 很少用于蛋白质-蛋白质对接.

<a id="lib-md"></a>
### Molecular Dynamics

* [Gromacs](http://www.gromacs.org/) - 分子动力学包主要设计用于模拟蛋白质、脂质和核酸.
* [OpenMM](http://openmm.org/) - 用于分子模拟的高性能工具包，包括针对 Python、C、C++ 甚至 Fortran 的广泛语言绑定.
* [NAMD](https://www.ks.uiuc.edu/Research/namd/) - 为大型生物分子系统的高性能模拟而设计的并行分子动力学代码.
* [MDTraj](https://github.com/mdtraj/mdtraj) - 分子动力学轨迹分析.
* [cclib](https://github.com/cclib/cclib) - 计算化学日志文件的解析器和算法.

<a id="lib-others"></a>
### Others

* [eiR](https://github.com/girke-lab/eiR) - 加速小分子的相似性搜索
* [OPSIN](https://github.com/dan2097/opsin) - 系统 IUPAC 命名法的开放解析器
* [Cookiecutter for Computational Molecular Sciences](https://github.com/MolSSI/cookiecutter-cms) - 用于分子计算化学包的以 Python 为中心的 Cookiecutter [MolSSL](https://molssi.org/)

## Journals

* [Journal of Cheminformatics](https://jcheminf.biomedcentral.com/)
* [Journal of Chemical Information and Modeling (ACS Publications)](https://pubs.acs.org/journal/jcisd8)

## Resources

### Courses

* [Learncheminformatics.com](http://learncheminformatics.com/) - 印第安纳大学的“化学信息学：浏览化学数据世界”课程.
* [Python for chemoinformatics](https://github.com/Mishima-syk/py4chemoinformatics)
* [TeachOpenCADD](https://github.com/volkamerlab/TeachOpenCADD) - 使用开源包和数据的计算机辅助药物设计 (CADD) 教学平台.
* [Cheminformatics OLCC](https://chem.libretexts.org/Courses/Intercollegiate_Courses/Cheminformatics_OLCC_(2019)) - 罗伯特·贝尔福德 (Robert Belford) 的阿肯色大学小石城大学合作校际在线化学课程 (OLCC) 课程的化学信息学课程
* [BigChem](http://bigchem.eu/alllectures) - 所有讲座 [BigChem](http://bigchem.eu/) （Horizo​​n 2020 MSC ITN EID 项目，提供大型化学数据分析方面的创新教育.）
* [Molecular modeling course](https://dasher.wustl.edu/chem478/) - 由博士 [Jay Ponder](https://dasher.wustl.edu/)，来自华盛顿大学圣路易斯分校的教授.
* [Simulation in Chemistry and Biochemistry](https://dasher.wustl.edu/chem430/) - 由博士 [Jay Ponder](https://dasher.wustl.edu/)，来自华盛顿大学圣路易斯分校的教授.

### Blogs

* [Open Source Molecular Modeling](https://opensourcemolecularmodeling.github.io/README.html) - 开源分子建模软件的可更新目录.
* [PubChem Blog](https://pubchemblog.ncbi.nlm.nih.gov/) - 有关的新闻、更新和教程 [PubChem](https://pubchem.ncbi.nlm.nih.gov/).
* [The ChEMBL-og blog](http://chembl.blogspot.tw/) - 来自计算化学生物学组的故事和新闻 [EMBL-EBI](https://www.ebi.ac.uk/).
* [ChEMBL blog](http://chembl.github.io/) - GitHub 上的 ChEMBL.
* [SteinBlog](http://www.steinbeck-molecular.de/steinblog/) - 博客 [Christoph Steinbeck](http://www.steinbeck-molecular.de/steinblog/index.php/about/)，他是 EMBL-EBI 化学信息学和代谢的负责人.
* [Practical Cheminformatics](http://practicalcheminformatics.blogspot.com/) - 包含化学信息学实际应用深入示例的博客.
* [So much to do, so little time - Trying to squeeze sense out of chemical data](http://blog.rguha.net/) - 博格 [Rajarshi Guha](http://blog.rguha.net/?page_id=8)，他是 NIH 促进转化科学中心的研究科学家.
 * 一些旧博客 [1](https://rguha.wordpress.com/) [2](http://www.rguha.net/index.html).
* [Noel O'Blog](http://baoilleach.blogspot.tw/) - 博客 [Noel O'Boyle](https://www.redbrick.dcu.ie/~noel/)，他是 NextMove Software 的高级软件工程师.
* [chem-bla-ics](http://chem-bla-ics.blogspot.tw/) - 博客 [Egon Willighagen](http://egonw.github.io/)，他是马斯特里赫特大学的助理教授.
<!---
* [Asad's Blog](https://chembioinfo.com/) - Syed Asad Rahman 的 Bolg，他是该领域的研究科学家 [Thornton group](http://www.ebi.ac.uk/research/thornton) 在 EMBL-EBI.
-->
* [steeveslab-blog](http://asteeves.github.io/) - 一些使用的例子 [RDKit](http://www.rdkit.org/).
* [Macs in Chemistry](http://www.macinchem.org/) - 为使用 Apple Macintosh 计算机的化学家提供资源.
* [DrugDiscovery.NET](http://www.drugdiscovery.net/) - 博客 [Andreas Bender](http://www.andreasbender.de/)，他是剑桥大学分子信息学的读者.
* [Is life worth living?](https://iwatobipen.wordpress.com/) - 化学信息学图书馆的一些例子.
* [Cheminformatics 2.0](https://cheminf20.org/) - 博客 [Alex M. Clark](https://twitter.com/aclarkxyz)，协作药物发现的研究科学家.
* [Depth-First](https://depth-first.com/) - 博客 [Richard L. Apodaca](https://depth-first.com/about/)，住在加利福尼亚州拉霍亚的化学家.

### Books

* [Computational Approaches in Cheminformatics and Bioinformatics](https://books.google.com/books/about/Computational_Approaches_in_Cheminformat.html?id=bLqV4rYQoYsC) - 同时包括来自公共 (NIH)、学术和工业来源的见解.
* [Chemoinformatics for Drug Discovery](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118742785) - 关于如何使用化学信息学策略来改善药物发现结果的材料.
* [Molecular Descriptors for Chemoinformatics](https://onlinelibrary.wiley.com/doi/book/10.1002/9783527628766) - 超过 3300 个描述词和相关术语，用于化合物特性的化学信息学分析.

<a id="see-also"></a>
## See Also

* [deeplearning-biology](https://github.com/hussius/deeplearning-biology#chemoinformatics-and-drug-discovery-) - deeplearning-biology repo 中的化学信息学和药物发现部分.
* [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry) - 另一个列表侧重于与化学相关的 Python 内容.
* [MolSSI Molecular Software Database](https://molssi.org/software-search/)
＊[Pages created by Tobias Kind, PhD](https://fiehnlab.ucdavis.edu/staff/kind/metabolomics)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
