<div class="github-widget" data-repo="hsiaoyi0504/awesome-cheminformatics"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cheminformatics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; 化学信息学（也称为化学信息学、化学信息学和化学信息学）是使用计算机和信息技术应用于化学领域的一系列问题.— [Wikipedia](https://en.wikipedia.org/wiki/Cheminformatics)

很棒的化学信息学软件、资源和库的精选列表. 主要基于命令行，免费或开源. 请随意 [contribute](https://github.com/hsiaoyi0504/awesome-cheminformatics/blob/master/CONTRIBUTING.md) !



## Applications

<a id="app-visualization"></a>
### Visualization

* [PyMOL](https://sourceforge.net/projects/pymol/) - Python-enhanced molecular graphics tool.
* [Jmol](http://jmol.sourceforge.net/) - 基于浏览器的 HTML5 查看器和用于 3D 化学结构的独立 Java 查看器.
* [VMD](http://www.ks.uiuc.edu/Research/vmd/) - 用于使用 3-D 图形和内置脚本显示、动画和分析大型生物分子系统的分子可视化程序.
* [Chimera](https://www.cgl.ucsf.edu/chimera/) - 用于交互式分子可视化和分析的高度可扩展程序. [Source](https://www.cgl.ucsf.edu/chimera/docs/sourcecode.html) 可用.
* [ChimeraX](https://www.cgl.ucsf.edu/chimerax/)  - 继 UCSF Chimera 之后的下一代分子可视化程序. 来源可用 [here](https://www.cgl.ucsf.edu/chimerax/docs/devel/conventions.html).
* [DataWarrior](http://www.openmolecules.org/datawarrior/index.html) - 将动态图形视图和交互式行过滤与化学智能相结合的数据可视化和分析程序.

<a id="app-cmd"></a>
### Command Line Tools

* [Open Babel](http://openbabel.org/wiki/Main_Page) - 化学工具箱设计用于讲多种语言的化学数据.
* [MayaChemTools](http://www.mayachemtools.org/index.html) - 支持日常计算发现需求的 Perl 和 Python 脚本、模块和类的集合.
* [Packmol](http://m3g.iqm.unicamp.br/packmol/home.shtml) - Initial configurations for molecular dynamics simulations by packing optimization.
* [BCL::Commons](http://meilerlab.org/index.php/bclcommons/show/b_apps_id/1)

<a id="app-docking"></a>
### Docking

* [AutoDock Vina](http://vina.scripps.edu/) - Molecular docking and virtual screening.
* [smina](https://sourceforge.net/projects/smina/) - 定制 [AutoDock Vina](http://vina.scripps.edu/) 更好地支持评分功能开发和高性能能量最小化.

<a id="app-virtual"></a>
### Virtual Machine

* [myChEMBL](http://chembl.blogspot.com/2015/07/mychembl-20-has-landed.html) - 使用开源软件（Ubuntu、PostgreSQL、RDKit）构建的 ChEMBL 版本
* [3D e-Chem Virtual Machine](https://github.com/3D-e-Chem/3D-e-Chem-VM) - 

## Libraries

<a id="lib-general"></a>
### General Purpose

* [RDKit](http://www.rdkit.org/) - 用 C++ 和 Python 编写的化学信息学和机器学习软件的集合.
* [Indigo](https://github.com/epam/Indigo) - Universal molecular toolkit that can be used for molecular fingerprinting, substructure search, and molecular visualization written in C++ package, with Java, C#, and Python wrappers.
* [CDK (Chemistry Development Kit)](https://sourceforge.net/projects/cdk/) - Algorithms for structural chemo- and bioinformatics, implemented in Java.
* [ChemmineR](https://www.bioconductor.org/packages/release/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html) - Cheminformatics package for analyzing drug-like small molecule data in R.
* [ChemPy](https://github.com/bjodah/chempy) - 一个对化学有用的 Python 包（主要是物理/无机/分析化学）
* [MolecularGraph.jl](https://github.com/mojaie/MolecularGraph.jl) - 在 Julia 中完全实现的基于图形的分子建模和化学信息学分析工具包
* [datamol](https://github.com/datamol-org/datamol) : - 分子操作变得容易. 构建在 RDKit 之上的轻量级包装器.

<a id="lib-format"></a>
### Format Checking

* [ChEMBL_Structure_Pipeline (formerly standardiser)](https://github.com/chembl/ChEMBL_Structure_Pipeline) - Tool designed to provide a simple way of standardising molecules as a prelude to e.g. molecular modelling exercises.
* [MolVS](https://github.com/mcs07/MolVS) - 基于分子验证和标准化 [RDKit](http://www.rdkit.org/).
* [rd_filters](https://github.com/PatWalters/rd_filters) - 使用 RDKit 和 ChEMBL 运行结构警报的脚本
* [pdb-tools](https://github.com/haddocking/pdb-tools) - 用于操作和编辑 PDB 文件的瑞士军刀.

<a id="lib-visualization"></a>
### Visualization

* [Kekule.js](http://partridgejiang.github.io/Kekule.js/) - 前端 JavaScript 库，用于提供在 Web 浏览器上表示、绘制、编辑、比较和搜索分子结构的能力.
* [3Dmol.js](https://github.com/3dmol/3Dmol.js) - An object-oriented, webGL based JavaScript library for online molecular visualization.
* [JChemPaint](https://github.com/JChemPaint/jchempaint) - 化学二维结构编辑器应用程序/小程序基于 [Chemistry Development Kit](https://sourceforge.net/projects/cdk/).
* [rdeditor](https://github.com/EBjerrum/rdeditor) - 使用 PySide 的简单 RDKit 分子编辑器 GUI.
* [nglviewer](http://nglviewer.org/nglview/latest/) - Interactive molecular graphics for Jupyter notebooks.
* [RDKit.js](https://www.npmjs.com/package/@rdkit/rdkit) - 来自 RDKit 的化学信息学功能的官方 JavaScript 分发 - 化学信息学的 C++ 库.

<a id="lib-des"></a>
### Molecular Descriptors

* [mordred](https://github.com/mordred-descriptor/mordred) - Molecular descriptor calculator based on [RDKit](http://www.rdkit.org/).
* [DescriptaStorus](https://github.com/bp-kelley/descriptastorus) - Descriptor computation(chemistry) and (optional) storage for machine learning.
* [mol2vec](https://github.com/samoturk/mol2vec) - Vector representations of molecular substructures.
* [Align-it](http://silicos-it.be.s3-website-eu-west-1.amazonaws.com/software/align-it/1.0.4/align-it.html#alignit-generating-pharmacophore-points) - 根据其药效团排列分子.
* [Rcpi](https://nanx.me/Rcpi/index.html) - R/Bioconductor package to generate various descriptors of proteins, compounds and their interactions.

<a id="lib-ml"></a>
### Machine Learning

* [DeepChem](https://github.com/deepchem/deepchem) - 基于 Tensorflow 的化学深度学习库
* [ChemML](https://github.com/hachmannlab/chemml)  - ChemML 是一个机器学习和信息学程序套件，用于分析、挖掘和建模化学和材料数据.  （基于张量流）
* [OpenChem](https://github.com/Mariewelt/OpenChem) - OpenChem 是一个用于计算化学的深度学习工具包，带有 PyTorch 后端.
* [chainer-chemistry](https://github.com/pfnet-research/chainer-chemistry) - 生物学和化学深度学习的图书馆。
* [pytorch-geometric](https://pytorch-geometric.readthedocs.io/en/latest/) - PyTorch 库提供了许多图形卷积算法的实现.
* [chemmodlab](https://github.com/jrash/ChemModLab) - 用于在 R 中拟合和评估机器学习模型的化学信息学建模实验室.
* [Summit](https://github.com/sustainable-processes/summit) - 用于使用机器学习优化化学反应的 python 包（包含 10 个算法 + 几个基准）.

<a id="lib-web"></a>
### Web APIs

* [webchem](https://github.com/ropensci/webchem) - 来自网络的化学信息.
* [PubChemPy](http://pubchempy.readthedocs.io) - Python wrapper for the PubChem PUG REST API.
* [ChemSpiPy](http://chemspipy.readthedocs.org) - ChemSpider API 的 Python 包装器.
* [CIRpy](http://cirpy.readthedocs.org/) - Python wrapper for the [NCI Chemical Identifier Resolver (CIR)](https://cactus.nci.nih.gov/chemical/structure).
* [Beaker](https://github.com/chembl/chembl_beaker) - [RDKit](http://www.rdkit.org/) and [OSRA](https://cactus.nci.nih.gov/osra/) in the [Bottle](http://bottlepy.org/docs/dev/) on [Tornado](http://www.tornadoweb.org/en/stable/).
* [chemminetools](https://github.com/girke-lab/chemminetools) - Open source web framework for small molecule analysis based on Django.

<a id="lib-db"></a>
### Databases

* [razi](https://github.com/rvianello/razi) - Cheminformatic extension for the SQLAlchemy database.

<a id="lib-dock"></a>
### Docking
* [Rosetta](https://www.rosettacommons.org/docs/latest/Home)  - 用于模拟大分子结构的综合软件套件. 很少用于蛋白质-蛋白质对接.

<a id="lib-md"></a>
### Molecular Dynamics

* [Gromacs](http://www.gromacs.org/) - 主要用于模拟蛋白质、脂质和核酸的分子动力学软件包.
* [OpenMM](http://openmm.org/) - High performance toolkit for molecular simulation including extensive language bindings for Python, C, C++, and even Fortran.
* [NAMD](https://www.ks.uiuc.edu/Research/namd/) - a parallel molecular dynamics code designed for high-performance simulation of large biomolecular systems.
* [MDTraj](https://github.com/mdtraj/mdtraj) - 分子动力学轨迹分析.
* [cclib](https://github.com/cclib/cclib) - Parsers and algorithms for computational chemistry logfiles.

<a id="lib-others"></a>
### Others

* [eiR](https://github.com/girke-lab/eiR) - Accelerated similarity searching of small molecules
* [OPSIN](https://github.com/dan2097/opsin) - Open Parser for Systematic IUPAC nomenclature
* [Cookiecutter for Computational Molecular Sciences](https://github.com/MolSSI/cookiecutter-cms) - 用于分子计算化学包的以 Python 为中心的 Cookiecutter 由 [MolSSL](https://molssi.org/)

## Journals

* [Journal of Cheminformatics](https://jcheminf.biomedcentral.com/)
* [Journal of Chemical Information and Modeling (ACS Publications)](https://pubs.acs.org/journal/jcisd8)

## Resources

### Courses

* [Learncheminformatics.com](http://learncheminformatics.com/) - 印第安纳大学的“化学信息学：探索化学数据世界”课程.
* [Python for chemoinformatics](https://github.com/Mishima-syk/py4chemoinformatics)
* [TeachOpenCADD](https://github.com/volkamerlab/TeachOpenCADD) - A teaching platform for computer-aided drug design (CADD) using open source packages and data.
* [Cheminformatics OLCC](https://chem.libretexts.org/Courses/Intercollegiate_Courses/Cheminformatics_OLCC_(2019)) - Cheminformatics course of the Collaborative Intercollegiate Online Chemistry Course (OLCC) course of University of Arkansas at Little Rock by Robert Belford
* [BigChem](http://bigchem.eu/alllectures) - 所有讲座 [BigChem](http://bigchem.eu/) （Horizo​​n 2020 MSC ITN EID 项目，提供大型化学数据分析方面的创新教育.）
* [Molecular modeling course](https://dasher.wustl.edu/chem478/) - 由博士. [Jay Ponder](https://dasher.wustl.edu/), a professor from WashU St.Louis.
* [Simulation in Chemistry and Biochemistry](https://dasher.wustl.edu/chem430/) - 由博士. [Jay Ponder](https://dasher.wustl.edu/), a professor from WashU St.Louis.

### Blogs

* [Open Source Molecular Modeling](https://opensourcemolecularmodeling.github.io/README.html) - Updateable catalog of open source molecular modeling software.
* [PubChem Blog](https://pubchemblog.ncbi.nlm.nih.gov/) - 新闻、更新和教程 [PubChem](https://pubchem.ncbi.nlm.nih.gov/).
* [The ChEMBL-og blog](http://chembl.blogspot.tw/) - Stories and news from Computational Chemical Biology Group at [EMBL-EBI](https://www.ebi.ac.uk/).
* [ChEMBL blog](http://chembl.github.io/) - ChEMBL on GitHub.
* [SteinBlog](http://www.steinbeck-molecular.de/steinblog/) - 博客 [Christoph Steinbeck](http://www.steinbeck-molecular.de/steinblog/index.php/about/)，他是 EMBL-EBI 化学信息学和新陈代谢的负责人.
* [Practical Cheminformatics](http://practicalcheminformatics.blogspot.com/) - Blog with in-depth examples of practical application of cheminformatics.
* [So much to do, so little time - Trying to squeeze sense out of chemical data](http://blog.rguha.net/) - 博尔格 [Rajarshi Guha](http://blog.rguha.net/?page_id=8)，他是美国国立卫生研究院推进转化科学中心的研究科学家.
 * 一些旧博客 [1](https://rguha.wordpress.com/) [2](http://www.rguha.net/index.html).
* [Noel O'Blog](http://baoilleach.blogspot.tw/) - 博客 [Noel O'Boyle](https://www.redbrick.dcu.ie/~noel/), who is a Senior Software Engineer at NextMove Software.
* [chem-bla-ics](http://chem-bla-ics.blogspot.tw/) - 博客 [Egon Willighagen](http://egonw.github.io/)，他是马斯特里赫特大学的助理教授.
<!---
* [Asad's Blog](https://chembioinfo.com/) - 赛义德·阿萨德·拉赫曼 (Syed Asad Rahman) 的博尔格 (Bolg of Syed Asad Rahman)，他是 [Thornton group](http://www.ebi.ac.uk/research/thornton) 在 EMBL-EBI.
-->
* [steeveslab-blog](http://asteeves.github.io/) - 一些使用示例 [RDKit](http://www.rdkit.org/).
* [Macs in Chemistry](http://www.macinchem.org/) - Provide a resource for chemists using Apple Macintosh computers.
* [DrugDiscovery.NET](http://www.drugdiscovery.net/) - 博客 [Andreas Bender](http://www.andreasbender.de/)，他是剑桥大学分子信息学的读者.
* [Is life worth living?](https://iwatobipen.wordpress.com/) - Some examples for cheminformatics libraries.
* [Cheminformatics 2.0](https://cheminf20.org/) - 博客 [Alex M. Clark](https://twitter.com/aclarkxyz), Collaborative Drug Discovery 的研究科学家.
* [Depth-First](https://depth-first.com/) - 博客 [Richard L. Apodaca](https://depth-first.com/about/), a chemist living in La Jolla, California.
* [Cheminformania](https://www.cheminformania.com) - 博客 [Ph.D, Esben Jannik Bjerrum](https://www.cheminformania.com/about/esben-jannik-bjerrum/), who is a Principle Scientist and a Machine Learning and AI specialists at AstraZeneca.

### Books

* [Computational Approaches in Cheminformatics and Bioinformatics](https://books.google.com/books/about/Computational_Approaches_in_Cheminformat.html?id=bLqV4rYQoYsC) -  Include insights from public (NIH), academic, and industrial sources at the same time.
* [Chemoinformatics for Drug Discovery](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118742785) - 关于如何使用化学信息学策略来改善药物发现结果的材料.
* [Molecular Descriptors for Chemoinformatics](https://onlinelibrary.wiley.com/doi/book/10.1002/9783527628766) - More than 3300 descriptors and related terms for chemoinformatic analysis of chemical compound properties.

<a id="see-also"></a>
## See Also

* [deeplearning-biology](https://github.com/hussius/deeplearning-biology#chemoinformatics-and-drug-discovery-) - Chemoinformatics and drug discovery section in deeplearning-biology repo.
* [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry) - Another list focuses on Python stuff related to Chemistry.
* [awesome-small-molecule-ml](https://github.com/benb111/awesome-small-molecule-ml) - 用于小分子药物发现的机器学习的论文、数据集和其他资源列表.
* [MolSSI Molecular Software Database](https://molssi.org/software-search/)
＊[Pages created by Tobias Kind, PhD](https://fiehnlab.ucdavis.edu/staff/kind/metabolomics)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
