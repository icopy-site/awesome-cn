<div class="github-widget" data-repo="hsiaoyi0504/awesome-cheminformatics"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cheminformatics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt;化学信息学（也称为化学信息学，化学信息学和化学信息学）是使用计算机和信息技术来解决化学领域中的一系列问题. [Wikipedia](https://en.wikipedia.org/wiki/Cheminformatics)

 精选的化学格式软件，资源和库的精选列表.  主要基于命令行，免费或开源.  请随意 [contribute](https://github.com/hsiaoyi0504/awesome-cheminformatics/blob/master/CONTRIBUTING.md) !



## Applications

<a id="app-visualization"></a>
### Visualization

* [PyMOL](https://sourceforge.net/projects/pymol/) -Python增强的分子图形工具.
* [Jmol](http://jmol.sourceforge.net/) -基于浏览器的HTML5查看器和用于3D化学结构的独立Java查看器.
* [VMD](http://www.ks.uiuc.edu/Research/vmd/) -分子可视化程序，用于使用3-D图形和内置脚本显示，设置动画和分析大型生物分子系统.
* [Chimera](https://www.cgl.ucsf.edu/chimera/) -用于交互式分子可视化和分析的高度可扩展程序. [Source](https://www.cgl.ucsf.edu/chimera/docs/sourcecode.html) 可用.
* [ChimeraX](https://www.cgl.ucsf.edu/chimerax/)  -UCSF Chimera之后的下一代分子可视化程序.  源可用 [here](https://www.cgl.ucsf.edu/chimerax/docs/devel/conventions.html).
* [DataWarrior](http://www.openmolecules.org/datawarrior/index.html) -数据可视化和分析程序，结合了动态图形视图和具有化学智能的交互式行过滤.

<a id="app-cmd"></a>
### Command Line Tools

* [Open Babel](http://openbabel.org/wiki/Main_Page) -化学工具箱，旨在说多种化学数据语言.
* [MayaChemTools](http://www.mayachemtools.org/index.html) -收集支持日常计算发现需求的Perl和Python脚本，模块和类.
* [Packmol](http://m3g.iqm.unicamp.br/packmol/home.shtml) -通过填料优化进行分子动力学模拟的初始配置.

<a id="app-docking"></a>
### Docking

* [AutoDock Vina](http://vina.scripps.edu/) -分子对接和虚拟筛选.
* [smina](https://sourceforge.net/projects/smina/) -定制 [AutoDock Vina](http://vina.scripps.edu/) 以更好地支持评分功能开发和高性能能耗最小化.

<a id="app-virtual"></a>
### Virtual Machine

* [myChEMBL](http://chembl.blogspot.com/2015/07/mychembl-20-has-landed.html) -使用开源软件（Ubuntu，PostgreSQL，RDKit）构建的ChEMBL版本
* [3D e-Chem Virtual Machine](https://github.com/3D-e-Chem/3D-e-Chem-VM) - 

## Libraries

<a id="lib-general"></a>
### General Purpose

* [RDKit](http://www.rdkit.org/) -收集用C ++和Python编写的化学信息学和机器学习软件.
* [Indigo](https://github.com/epam/Indigo) - Universal molecular toolkit that can be used for molecular fingerprinting, substructure search, and molecular visualization written in C++ package, with Java, C#, and Python wrappers.
* [CDK (Chemistry Development Kit)](https://sourceforge.net/projects/cdk/) -用Java实现的结构化学信息和生物信息学算法.
* [ChemmineR](https://www.bioconductor.org/packages/release/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html) -Cheminformatics软件包，用于分析R中类似药物的小分子数据.

<a id="lib-format"></a>
### Format Checking

* [standardiser](https://wwwdev.ebi.ac.uk/chembl/extra/francis/standardiser/) -设计用于提供标准化分子的简单方法的工具，例如作为分子建模练习的序幕.
* [MolVS](https://github.com/mcs07/MolVS) -基于分子的验证和标准化 [RDKit](http://www.rdkit.org/).
* [rd_filters](https://github.com/PatWalters/rd_filters) -使用RDKit和ChEMBL运行结构警报的脚本

<a id="lib-visualization"></a>
### Visulization

* [Kekule.js](http://partridgejiang.github.io/Kekule.js/) -前端JavaScript库，用于在网络浏览器上提供表示，绘制，编辑，比较和搜索分子结构的功能.
* [3Dmol.js](https://github.com/3dmol/3Dmol.js) -面向对象的基于webGL的JavaScript库，用于在线分子可视化.
* [JChemPaint](https://github.com/JChemPaint/jchempaint) -基于的化学2D结构编辑器应用程序/小程序 [Chemistry Development Kit](https://sourceforge.net/projects/cdk/).
* [rdeditor](https://github.com/EBjerrum/rdeditor) -使用PySide的简单RDKit分子编辑器GUI.
* [nglviewer](http://nglviewer.org/nglview/latest/) -Jupyter笔记本电脑的交互式分子图形.

<a id="lib-des"></a>
### Molecular Descriptors

* [mordred](https://github.com/mordred-descriptor/mordred) -基于分子描述符计算器 [RDKit](http://www.rdkit.org/).
* [mol2vec](https://github.com/samoturk/mol2vec) -分子亚结构的向量表示.
* [Align-it](http://silicos-it.be.s3-website-eu-west-1.amazonaws.com/software/align-it/1.0.4/align-it.html#alignit-generating-pharmacophore-points) -根据其药效比对分子.
* [Rcpi](https://nanx.me/Rcpi/index.html) -R / Bioconductor程序包，用于生成蛋白质，化合物及其相互作用的各种描述符.

<a id="lib-ml"></a>
### Machine Learning

* [DeepChem](https://github.com/deepchem/deepchem) -基于Tensorflow的化学深度学习库
* [chainer-chemistry](https://github.com/pfnet-research/chainer-chemistry) -生物学和化学深度学习图书馆.
* [pytorch-geometric](https://pytorch-geometric.readthedocs.io/en/latest/) -PyTorch库提供了许多图卷积算法的实现.

<a id="lib-web"></a>
### Web APIs

* [webchem](https://github.com/ropensci/webchem) -来自网络的化学信息.
* [PubChemPy](http://pubchempy.readthedocs.io) -PubChem PUG REST API的Python包装器.
* [ChemSpiPy](http://chemspipy.readthedocs.org) -ChemSpider API的Python包装器.
* [CIRpy](http://cirpy.readthedocs.org/) -NCI化学​​标识符解析器（CIR）的Python包装器.
* [Beaker](https://github.com/chembl/chembl_beaker) - [RDKit](http://www.rdkit.org/) 和 [OSRA](https://cactus.nci.nih.gov/osra/) 在里面 [Bottle](http://bottlepy.org/docs/dev/) 上 [Tornado](http://www.tornadoweb.org/en/stable/).

<a id="lib-db"></a>
### Databases

* [razi](https://github.com/rvianello/razi) -SQLAlchemy数据库的化学格式扩展.

<a id="lib-md"></a>
### Molecular Dynamics

* [Gromacs](http://www.gromacs.org/) -分子动力学软件包，主要用于模拟蛋白质，脂质和核酸.
* [OpenMM](http://openmm.org/) -用于分子模拟的高性能工具包，包括适用于Python，C，C ++甚至Fortran的广泛语言绑定.
* [MDTraj](https://github.com/mdtraj/mdtraj) -分子动力学轨迹分析.
* [cclib](https://github.com/cclib/cclib) -用于计算化学日志文件的解析器和算法.

<a id="lib-others"></a>
### Others

* [OPSIN](https://bitbucket.org/dan2097/opsin/downloads/) -用于系统IUPAC术语的开放解析器
* [Cookiecutter for Computational Molecular Sciences](https://github.com/MolSSI/cookiecutter-cms) -以Python为中心的Cookiecutter，用于分子计算化学软件包，作者： [MolSSL](https://molssi.org/)

## Journals

* [Journal of Cheminformatics](https://jcheminf.biomedcentral.com/)
* [Journal of Chemical Information and Modeling (ACS Publications)](https://pubs.acs.org/journal/jcisd8)

## Resources

### Courses

* [Learncheminformatics.com](http://learncheminformatics.com/) -印第安那大学的“化学信息学：在化学数据世界中导航”.
* [Python for chemoinformatics](https://github.com/Mishima-syk/py4chemoinformatics)
* [TeachOpenCADD](https://github.com/volkamerlab/TeachOpenCADD) -使用开源软件包和数据进行计算机辅助药物设计（CADD）的教学平台.
* [ChemInformatics course of University of Arkansas at Little Rock](https://chem.libretexts.org/Courses/University_of_Arkansas_Little_Rock/ChemInformatics_(2017)％3A_Chem_4399％2F％2F5399）-罗伯特·贝尔福德（Robert Belford）的阿肯色大学小石城分校化学信息学课程（2017年春季）
* [BigChem](http://bigchem.eu/alllectures) -的所有讲座 [BigChem](http://bigchem.eu/) （Horizo​​n 2020 MSC ITN EID项目提供了有关大型化学数据分析的创新教育.）
* [Molecular modeling course](https://dasher.wustl.edu/chem478/) -由Dr. [Jay Ponder](https://dasher.wustl.edu/)是WashU St.Louis的教授.
* [Simulation in Chemistry and Biochemistry](https://dasher.wustl.edu/chem430/) -由Dr. [Jay Ponder](https://dasher.wustl.edu/)是WashU St.Louis的教授.

### Blogs

* [Open Source Molecular Modeling](https://opensourcemolecularmodeling.github.io/README.html) -开源分子建模软件的可更新目录.
* [PubChem Blog](https://pubchemblog.ncbi.nlm.nih.gov/) -有关的新闻，更新和教程 [PubChem](https://pubchem.ncbi.nlm.nih.gov/).
* [The ChEMBL-og blog](http://chembl.blogspot.tw/) -计算化学生物学小组的故事和新闻 [EMBL-EBI](https://www.ebi.ac.uk/).
* [ChEMBL blog](http://chembl.github.io/) - ChEMBL on GitHub.
* [SteinBlog](http://www.steinbeck-molecular.de/steinblog/) -的博客 [Christoph Steinbeck](http://www.steinbeck-molecular.de/steinblog/index.php/about/)是EMBL-EBI的化学信息学和新陈代谢负责人.
* [Practical Cheminformatics](http://practicalcheminformatics.blogspot.com/) -博客，详细介绍化学信息学的实际应用.
* [So much to do, so little time - Trying to squeeze sense out of chemical data](http://blog.rguha.net/) -的Bolg [Rajarshi Guha](http://blog.rguha.net/?page_id=8)是美国国立卫生研究院转化科学促进中心的研究科学家.
 *一些旧博客 [1](https://rguha.wordpress.com/) [2](http://www.rguha.net/index.html).
* [Noel O'Blog](http://baoilleach.blogspot.tw/) -的博客 [Noel O'Boyle](https://www.redbrick.dcu.ie/~noel/)，他是NextMove Software的高级软件工程师.
* [chem-bla-ics](http://chem-bla-ics.blogspot.tw/) -的博客 [Egon Willighagen](http://egonw.github.io/)是马斯特里赫特大学的助理教授.
* [Asad's Blog](https://chembioinfo.com/) -Syed Asad Rahman的Bolg，他是 [Thornton group](http://www.ebi.ac.uk/research/thornton) 在EMBL-EBI.
* [steeveslab-blog](http://asteeves.github.io/) -使用的一些例子 [RDKit](http://www.rdkit.org/).
* [Macs in Chemistry](http://www.macinchem.org/) -为使用Apple Macintosh计算机的化学家提供资源.
* [DrugDiscovery.NET](http://www.drugdiscovery.net/) -的博客 [Andreas Bender](http://www.andreasbender.de/)，是剑桥大学分子信息学的读者.
* [Is life worth living?](https://iwatobipen.wordpress.com/) -化学信息学库的一些示例.
* [Cheminformatics 2.0](https://cheminf20.org/) -的博客 [Alex M. Clark](https://twitter.com/aclarkxyz)，他是协作药物发现公司（Collaborative Drug Discovery）的研究科学家.

### Books

* [Computational Approaches in Cheminformatics and Bioinformatics](https://books.google.com/books/about/Computational_Approaches_in_Cheminformat.html?id=bLqV4rYQoYsC) -同时包括来自公共（NIH），学术界和工业界的见解.
* [Chemoinformatics for Drug Discovery](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118742785) -有关如何使用化学信息学策略改善药物发现结果的材料.
* [Molecular Descriptors for Chemoinformatics](https://onlinelibrary.wiley.com/doi/book/10.1002/9783527628766) -超过3300个用于化学信息分析化学性质的描述符和相关术语.

<a id="see-also"></a>
## See Also

* [deeplearning-biology](https://github.com/hussius/deeplearning-biology#chemoinformatics-and-drug-discovery-) -深度学习生物学库中的化学信息学和药物发现部分.
* [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry) -另一个清单着重于与化学有关的Python内容.
* [MolSSI Molecular Software Database](https://molssi.org/software-search/)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
