<div class="github-widget" data-repo="hsiaoyi0504/awesome-cheminformatics"></div>
## Awesome Cheminformatics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt;化学信息学（也称为化学信息学，化学信息学和化学信息学）是利用计算机和信息技术应用于化学领域的一系列问题.- [Wikipedia](https://en.wikipedia.org/wiki/Cheminformatics)

 精选的Cheminformatics软件，资源和库的精选列表.  主要是基于命令行，免费或开源.  请随意 [contribute](https://github.com/hsiaoyi0504/awesome-cheminformatics/blob/master/CONTRIBUTING.md) !



## Applications

<a id="app-visualization"></a>
### Visualization

* [PyMOL](https://sourceforge.net/projects/pymol/) -  Python增强的分子图形工具.
* [Jmol](http://jmol.sourceforge.net/) - 基于浏览器的HTML5查看器和用于3D化学结构的独立Java查看器.
* [VMD](http://www.ks.uiuc.edu/Research/vmd/) - 分子可视化程序，用于使用3-D图形和内置脚本显示，动画和分析大型生物分子系统.
* [Chimera](https://www.cgl.ucsf.edu/chimera/) - 高度可扩展的交互式分子可视化和分析程序.

<a id="app-cmd"></a>
### Command Line Tools

* [Open Babel](http://openbabel.org/wiki/Main_Page) - 化学工具箱，设计用于说多种语言的化学数据.
* [MayaChemTools](http://www.mayachemtools.org/index.html) - 支持日常计算发现需求的Perl和Python脚本，模块和类的集合.
* [Packmol](http://m3g.iqm.unicamp.br/packmol/home.shtml) - 通过打包优化进行分子动力学模拟的初始配置.

<a id="app-docking"></a>
### Docking

* [AutoDock Vina](http://vina.scripps.edu/) - 分子对接和虚拟筛选.
* [smina](https://sourceforge.net/projects/smina/) - 定制 [AutoDock Vina](http://vina.scripps.edu/) 更好地支持评分功能开发和高性能能源最小化.

## Libraries

<a id="lib-general"></a>
### General Purpose

* [RDKit](http://www.rdkit.org/) - 用C ++和Python编写的cheminformatics和机器学习软件的集合.
* [Indigo](https://github.com/epam/Indigo) - Universal molecular toolkit that can be used for molecular fingerprinting, substructure search, and molecular visualization written in C++ package, with Java, C#, and Python wrappers.
* [CDK (Chemistry Development Kit)](https://sourceforge.net/projects/cdk/) - 结构化学和生物信息学的算法，用Java实现.
* [ChemmineR](https://www.bioconductor.org/packages/release/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html) - 用于分析R中类药物小分子数据的Cheminformatics软件包

<a id="lib-format"></a>
### Format Checking

* [standardiser](https://wwwdev.ebi.ac.uk/chembl/extra/francis/standardiser/) - 旨在提供标准化分子的简单方法的工具，作为例如分子建模练习的前奏.
* [MolVS](https://github.com/mcs07/MolVS) - 基于的分子验证和标准化 [RDKit](http://www.rdkit.org/).

<a id="lib-visualization"></a>
### Visulization

* [Kekule.js](http://partridgejiang.github.io/Kekule.js/) - 前端JavaScript库，用于在Web浏览器上表示，绘制，编辑，比较和搜索分子结构.
* [JChemPaint](https://github.com/JChemPaint/jchempaint) - 化学二维结构编辑器应用程序/ applet基于 [Chemistry Development Kit](https://sourceforge.net/projects/cdk/).
* [rdeditor](https://github.com/EBjerrum/rdeditor) - 使用PySide的简单RDKit分子编辑器GUI.

<a id="lib-des"></a>
### Molecular Descriptors

* [mordred](https://github.com/mordred-descriptor/mordred) - 基于分子描述子计算器 [RDKit](http://www.rdkit.org/).
* [mol2vec](https://github.com/samoturk/mol2vec) - 分子子结构的矢量表示.
* [Align-it](http://silicos-it.be.s3-website-eu-west-1.amazonaws.com/software/align-it/1.0.4/align-it.html#alignit-generating-pharmacophore-points) - 根据药效团对齐分子.

<a id="lib-ml"></a>
### Machine Learning

* [DeepChem](https://github.com/deepchem/deepchem) - 使化学的深度学习民主化.
* [chainer-chemistry](https://github.com/pfnet-research/chainer-chemistry) - 生物学和化学深度学习图书馆.

<a id="lib-web"></a>
### Web APIs

* [webchem](https://github.com/ropensci/webchem) - 来自网络的化学信息.
* [PubChemPy](http://pubchempy.readthedocs.io) -  PubChem PUG REST API的Python包装器.
* [ChemSpiPy](http://chemspipy.readthedocs.org) -  ChemSpider API的Python包装器.
* [CIRpy](http://cirpy.readthedocs.org/) - 用于NCI化学​​标识符解析器（CIR）的Python包装器.
* [Beaker](https://github.com/chembl/chembl_beaker) - [RDKit](http://www.rdkit.org/) 和 [OSRA](https://cactus.nci.nih.gov/osra/) 在里面 [Bottle](http://bottlepy.org/docs/dev/) 上 [Tornado](http://www.tornadoweb.org/en/stable/).

<a id="lib-db"></a>
### Databases

* [razi](https://github.com/rvianello/razi) -  SQLAlchemy数据库的Cheminformatic扩展.

<a id="lib-md"></a>
### Molecular Dynamics

* [Gromacs](http://www.gromacs.org/) - 分子动力学包主要设计用于模拟蛋白质，脂质和核酸.
* [OpenMM](http://openmm.org/) - 用于分子模拟的高性能工具包，包括用于Python，C，C ++甚至Fortran的广泛语言绑定.
* [MDTraj](https://github.com/mdtraj/mdtraj) - 分子动力学轨迹分析.
* [cclib](https://github.com/cclib/cclib) - 计算化学日志文件的解析器和算法.

## Journals

* [Journal of Cheminformatics](https://jcheminf.biomedcentral.com/)
* [Journal of Chemical Information and Modeling (ACS Publications)](https://pubs.acs.org/journal/jcisd8)

## Resources

### Courses

* [Learncheminformatics.com](http://learncheminformatics.com/) - 印第安纳大学的“化学信息学：浏览化学数据世界”.
* [cheminfoeducation](https://www.youtube.com/user/cheminfoeducation/videos) - 用于化学信息学教育的YouTube频道.

### Blogs

* [Open Source Molecular Modeling](https://opensourcemolecularmodeling.github.io/README.html) - 可更新的开源分子建模软件目录.
* [PubChem Blog](https://pubchemblog.ncbi.nlm.nih.gov/) - 有关的新闻，更新和教程 [PubChem](https://pubchem.ncbi.nlm.nih.gov/).
* [The ChEMBL-og blog](http://chembl.blogspot.tw/) - 来自计算化学生物学组的故事和新闻 [EMBL-EBI](https://www.ebi.ac.uk/).
* [ChEMBL blog](http://chembl.github.io/) -  GitHub上的ChEMBL.
* [SteinBlog](http://www.steinbeck-molecular.de/steinblog/) - 博客 [Christoph Steinbeck](http://www.steinbeck-molecular.de/steinblog/index.php/about/)，谁是EMBL-EBI的化学信息学和新陈代谢的负责人.
* [Practical Cheminformatics](http://practicalcheminformatics.blogspot.com/) - 博客深入了解化学信息学的实际应用实例.
* [So much to do, so little time - Trying to squeeze sense out of chemical data](http://blog.rguha.net/) -  Bolg of [Rajarshi Guha](http://blog.rguha.net/?page_id=8)，谁是美国国立卫生研究院推进转化科学中心的研究科学家.
 *一些旧博客 [1](https://rguha.wordpress.com/) [2](http://www.rguha.net/index.html).
* [Noel O'Blog](http://baoilleach.blogspot.tw/) - 博客 [Noel O'Boyle](https://www.redbrick.dcu.ie/~noel/)，谁是NextMove Software的高级软件工程师.
* [chem-bla-ics](http://chem-bla-ics.blogspot.tw/) - 博客 [Egon Willighagen](http://egonw.github.io/)，谁是马斯特里赫特大学的助理教授.
* [Asad's Blog](https://chembioinfo.com/) -  Syed Asad Rahman的Bolg，他是一名研究科学家 [Thornton group](http://www.ebi.ac.uk/research/thornton) 在EMBL-EBI.
* [steeveslab-blog](http://asteeves.github.io/) - 使用的一些例子 [RDKit](http://www.rdkit.org/).
* [Macs in Chemistry](http://www.macinchem.org/) - 为使用Apple Macintosh计算机的化学家提供资源.

### Books

* [Computational Approaches in Cheminformatics and Bioinformatics](https://books.google.com/books/about/Computational_Approaches_in_Cheminformat.html?id=bLqV4rYQoYsC) - 同时包括公共（NIH），学术和工业来源的见解.
* [Chemoinformatics for Drug Discovery](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118742785) - 有关如何使用化学信息学策略改善药物发现结果的材料.

<a id="see-also"></a>
## See Also

* [deeplearning-biology](https://github.com/hussius/deeplearning-biology#chemoinformatics-and-drug-discovery-) - 在深度学习 - 生物学回购中的化学信息学和药物发现部分.
* [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry) - 另一个列表侧重于与化学相关的Python内容.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
