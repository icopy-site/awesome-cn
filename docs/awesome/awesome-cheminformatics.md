<div class="github-widget" data-repo="hsiaoyi0504/awesome-cheminformatics"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cheminformatics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Cheminformatics (also known as chemoinformatics, chemioinformatics and chemical informatics) is the use of computer and informational techniques applied to a range of problems in the field of chemistry.— [Wikipedia](https://en.wikipedia.org/wiki/Cheminformatics)

A curated list of awesome Cheminformatics software, resources, and libraries. Mostly command line based, and free or open-source. Please feel free to [contribute](https://github.com/hsiaoyi0504/awesome-cheminformatics/blob/master/CONTRIBUTING.md) !



## Applications

<a id="app-visualization"></a>
### Visualization

* [PyMOL](https://sourceforge.net/projects/pymol/) - Python-enhanced molecular graphics tool.
* [Jmol](http://jmol.sourceforge.net/) - Browser-based HTML5 viewer and stand-alone Java viewer for chemical structures in 3D.
* [VMD](http://www.ks.uiuc.edu/Research/vmd/) - Molecular visualization program for displaying, animating, and analyzing large biomolecular systems using 3-D graphics and built-in scripting.
* [Chimera](https://www.cgl.ucsf.edu/chimera/) - Highly extensible program for interactive molecular visualization and analysis. [Source](https://www.cgl.ucsf.edu/chimera/docs/sourcecode.html) is available.
* [ChimeraX](https://www.cgl.ucsf.edu/chimerax/) - The next-generation molecular visualization program, following UCSF Chimera. Source is available [here](https://www.cgl.ucsf.edu/chimerax/docs/devel/conventions.html).
* [DataWarrior](http://www.openmolecules.org/datawarrior/index.html) - A program for data Visualization and analysis which combines dynamic graphical views and interactive row filtering with chemical intelligence.

<a id="app-cmd"></a>
### Command Line Tools

* [Open Babel](http://openbabel.org/wiki/Main_Page) - Chemical toolbox designed to speak the many languages of chemical data.
* [MayaChemTools](http://www.mayachemtools.org/index.html) - Collection of Perl and Python scripts, modules, and classes that support day-to-day computational discovery needs.
* [Packmol](http://m3g.iqm.unicamp.br/packmol/home.shtml) - Initial configurations for molecular dynamics simulations by packing optimization.
* [BCL::Commons](http://meilerlab.org/index.php/bclcommons/show/b_apps_id/1)

<a id="app-docking"></a>
### Docking

* [AutoDock Vina](http://vina.scripps.edu/) - Molecular docking and virtual screening.
* [smina](https://sourceforge.net/projects/smina/) - Customized [AutoDock Vina](http://vina.scripps.edu/) to better support scoring function development and high-performance energy minimization.

<a id="app-virtual"></a>
### Virtual Machine

* [myChEMBL](http://chembl.blogspot.com/2015/07/mychembl-20-has-landed.html) - A version of ChEMBL built using Open Source software (Ubuntu, PostgreSQL, RDKit)
* [3D e-Chem Virtual Machine](https://github.com/3D-e-Chem/3D-e-Chem-VM) - 

## Libraries

<a id="lib-general"></a>
### General Purpose

* [RDKit](http://www.rdkit.org/) - Collection of cheminformatics and machine-learning software written in C++ and Python.
* [Indigo](https://github.com/epam/Indigo) - Universal molecular toolkit that can be used for molecular fingerprinting, substructure search, and molecular visualization written in C++ package, with Java, C#, and Python wrappers.
* [CDK (Chemistry Development Kit)](https://sourceforge.net/projects/cdk/) - Algorithms for structural chemo- and bioinformatics, implemented in Java.
* [ChemmineR](https://www.bioconductor.org/packages/release/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html) - Cheminformatics package for analyzing drug-like small molecule data in R.
* [ChemPy](https://github.com/bjodah/chempy) - A Python package useful for chemistry (mainly physical/inorganic/analytical chemistry)
* [MolecularGraph.jl](https://github.com/mojaie/MolecularGraph.jl) - A graph-based molecule modeling and chemoinformatics analysis toolkit fully implemented in Julia
* [datamol](https://github.com/datamol-org/datamol): - Molecular Manipulation Made Easy. A light wrapper build on top of RDKit.
* [CGRtools](https://github.com/cimm-kzn/CGRtools) - Toolkit for processing molecules, reactions and condensed graphs of reactions. Can be used for chemical standardization, MCS search, tautomers generation with backward compatibility to RDKit and NetworkX.

<a id="lib-format"></a>
### Format Checking

* [ChEMBL_Structure_Pipeline (formerly standardiser)](https://github.com/chembl/ChEMBL_Structure_Pipeline) - Tool designed to provide a simple way of standardising molecules as a prelude to e.g. molecular modelling exercises.
* [MolVS](https://github.com/mcs07/MolVS) - Molecule validation and standardization based on [RDKit](http://www.rdkit.org/).
* [rd_filters](https://github.com/PatWalters/rd_filters) - A script to run structural alerts using the RDKit and ChEMBL
* [pdb-tools](https://github.com/haddocking/pdb-tools) - A swiss army knife for manipulating and editing PDB files.

<a id="lib-visualization"></a>
### Visualization

* [Kekule.js](http://partridgejiang.github.io/Kekule.js/) - 前端 JavaScript 库，用于在 Web 浏览器上提供表示、绘制、编辑、比较和搜索分子结构的能力。
* [3Dmol.js](https://github.com/3dmol/3Dmol.js) - An object-oriented, webGL based JavaScript library for online molecular visualization.
* [JChemPaint](https://github.com/JChemPaint/jchempaint) - Chemical 2D structure editor application/applet based on the [Chemistry Development Kit](https://sourceforge.net/projects/cdk/).
* [rdeditor](https://github.com/EBjerrum/rdeditor) - Simple RDKit molecule editor GUI using PySide.
* [nglviewer](http://nglviewer.org/nglview/latest/) - Interactive molecular graphics for Jupyter notebooks.
* [RDKit.js](https://www.npmjs.com/package/@rdkit/rdkit) - Official JavaScript distribution of cheminformatics functionality from the RDKit - a C++ library for cheminformatics.

<a id="lib-des"></a>
### Molecular Descriptors

* [mordred](https://github.com/mordred-descriptor/mordred) - Molecular descriptor calculator based on [RDKit](http://www.rdkit.org/).
* [DescriptaStorus](https://github.com/bp-kelley/descriptastorus) - Descriptor computation(chemistry) and (optional) storage for machine learning.
* [mol2vec](https://github.com/samoturk/mol2vec) - Vector representations of molecular substructures.
* [Align-it](http://silicos-it.be.s3-website-eu-west-1.amazonaws.com/software/align-it/1.0.4/align-it.html#alignit-generating-pharmacophore-points) - Align molecules according their pharmacophores.
* [Rcpi](https://nanx.me/Rcpi/index.html) - R/Bioconductor package to generate various descriptors of proteins, compounds and their interactions.

<a id="lib-ml"></a>
### Machine Learning

* [DeepChem](https://github.com/deepchem/deepchem) - Deep learning library for Chemistry based on Tensorflow
* [ChemML](https://github.com/hachmannlab/chemml) - ChemML is a machine learning and informatics program suite for the analysis, mining, and modeling of chemical and materials data. (based on Tensorflow)
* [OpenChem](https://github.com/Mariewelt/OpenChem) - OpenChem is a deep learning toolkit for Computational Chemistry with PyTorch backend.
* [chainer-chemistry](https://github.com/pfnet-research/chainer-chemistry) - 生物学和化学深度学习的图书馆。
* [pytorch-geometric](https://pytorch-geometric.readthedocs.io/en/latest/) - A PyTorch library provides implementation of many graph convolution algorithms.
* [chemmodlab](https://github.com/jrash/ChemModLab) - A Cheminformatics Modeling Laboratory for Fitting and Assessing Machine Learning Models in R.
* [Summit](https://github.com/sustainable-processes/summit) - A python package for optimizing chemical reactions using machine learning (contains 10 algorithms + several benchmarks).

<a id="lib-web"></a>
### Web APIs

* [webchem](https://github.com/ropensci/webchem) - Chemical Information from the Web.
* [PubChemPy](http://pubchempy.readthedocs.io) - Python wrapper for the PubChem PUG REST API.
* [ChemSpiPy](http://chemspipy.readthedocs.org) - Python wrapper for the ChemSpider API.
* [CIRpy](http://cirpy.readthedocs.org/) - Python wrapper for the [NCI Chemical Identifier Resolver (CIR)](https://cactus.nci.nih.gov/chemical/structure).
* [Beaker](https://github.com/chembl/chembl_beaker) - [RDKit](http://www.rdkit.org/) and [OSRA](https://cactus.nci.nih.gov/osra/) in the [Bottle](http://bottlepy.org/docs/dev/) on [Tornado](http://www.tornadoweb.org/en/stable/).
* [chemminetools](https://github.com/girke-lab/chemminetools) - Open source web framework for small molecule analysis based on Django.

<a id="lib-db"></a>
### Databases

* [razi](https://github.com/rvianello/razi) - Cheminformatic extension for the SQLAlchemy database.

<a id="lib-dock"></a>
### Docking
* [Rosetta](https://www.rosettacommons.org/docs/latest/Home) - A comprehensive software suite for modeling macromolecular structures. Used larely for protein-protein docking.

<a id="lib-md"></a>
### Molecular Dynamics

* [Gromacs](http://www.gromacs.org/) - Molecular dynamics package mainly designed for simulations of proteins, lipids and nucleic acids.
* [OpenMM](http://openmm.org/) - High performance toolkit for molecular simulation including extensive language bindings for Python, C, C++, and even Fortran.
* [NAMD](https://www.ks.uiuc.edu/Research/namd/) - a parallel molecular dynamics code designed for high-performance simulation of large biomolecular systems.
* [MDTraj](https://github.com/mdtraj/mdtraj) - Analysis of molecular dynamics trajectories.
* [cclib](https://github.com/cclib/cclib) - Parsers and algorithms for computational chemistry logfiles.

<a id="lib-others"></a>
### Others

* [eiR](https://github.com/girke-lab/eiR) - Accelerated similarity searching of small molecules
* [OPSIN](https://github.com/dan2097/opsin) - Open Parser for Systematic IUPAC nomenclature
* [Cookiecutter for Computational Molecular Sciences](https://github.com/MolSSI/cookiecutter-cms) - Python-centric Cookiecutter for Molecular Computational Chemistry Packages by [MolSSL](https://molssi.org/)

## Journals

* [Journal of Cheminformatics](https://jcheminf.biomedcentral.com/)
* [Journal of Chemical Information and Modeling (ACS Publications)](https://pubs.acs.org/journal/jcisd8)

## Resources

### Courses

* [Learncheminformatics.com](http://learncheminformatics.com/) - "Cheminformatics: Navigating the world of chemical data" courese at Indiana University.
* [Python for chemoinformatics](https://github.com/Mishima-syk/py4chemoinformatics)
* [TeachOpenCADD](https://github.com/volkamerlab/TeachOpenCADD) - A teaching platform for computer-aided drug design (CADD) using open source packages and data.
* [Cheminformatics OLCC](https://chem.libretexts.org/Courses/Intercollegiate_Courses/Cheminformatics_OLCC_(2019)) - Cheminformatics course of the Collaborative Intercollegiate Online Chemistry Course (OLCC) course of University of Arkansas at Little Rock by Robert Belford
* [BigChem](http://bigchem.eu/alllectures) - All lectures of [BigChem](http://bigchem.eu/) (A Horizon 2020 MSC ITN EID project, which provides innovative education in large chemical data analysis.)
* [Molecular modeling course](https://dasher.wustl.edu/chem478/) - by Dr. [Jay Ponder](https://dasher.wustl.edu/), a professor from WashU St.Louis.
* [Simulation in Chemistry and Biochemistry](https://dasher.wustl.edu/chem430/) - by Dr. [Jay Ponder](https://dasher.wustl.edu/), a professor from WashU St.Louis.

### Blogs

* [Open Source Molecular Modeling](https://opensourcemolecularmodeling.github.io/README.html) - Updateable catalog of open source molecular modeling software.
* [PubChem Blog](https://pubchemblog.ncbi.nlm.nih.gov/) - News, updates and tutorials about [PubChem](https://pubchem.ncbi.nlm.nih.gov/).
* [The ChEMBL-og blog](http://chembl.blogspot.tw/) - Stories and news from Computational Chemical Biology Group at [EMBL-EBI](https://www.ebi.ac.uk/).
* [ChEMBL blog](http://chembl.github.io/) - ChEMBL on GitHub.
* [SteinBlog](http://www.steinbeck-molecular.de/steinblog/) - Blog of [Christoph Steinbeck](http://www.steinbeck-molecular.de/steinblog/index.php/about/), who is the head of cheminformatics and metabolism at the EMBL-EBI.
* [Practical Cheminformatics](http://practicalcheminformatics.blogspot.com/) - Blog with in-depth examples of practical application of cheminformatics.
* [So much to do, so little time - Trying to squeeze sense out of chemical data](http://blog.rguha.net/) - Bolg of [Rajarshi Guha](http://blog.rguha.net/?page_id=8), who is a research scientist at NIH Center for Advancing Translational Science.
  * Some old blogs [1](https://rguha.wordpress.com/) [2](http://www.rguha.net/index.html).
* [Noel O'Blog](http://baoilleach.blogspot.tw/) - Blog of [Noel O'Boyle](https://www.redbrick.dcu.ie/~noel/), who is a Senior Software Engineer at NextMove Software.
* [chem-bla-ics](http://chem-bla-ics.blogspot.tw/) - Blog of [Egon Willighagen](http://egonw.github.io/), who is an assistant professor at Maastricht University.
<!---
* [Asad's Blog](https://chembioinfo.com/) - Bolg of Syed Asad Rahman, who is a research scientist in the [Thornton group](http://www.ebi.ac.uk/research/thornton) at EMBL-EBI.
-->
* [steeveslab-blog](http://asteeves.github.io/) - Some examples using [RDKit](http://www.rdkit.org/).
* [Macs in Chemistry](http://www.macinchem.org/) - Provide a resource for chemists using Apple Macintosh computers.
* [DrugDiscovery.NET](http://www.drugdiscovery.net/) - Blog of [Andreas Bender](http://www.andreasbender.de/), who is a Reader for Molecular Informatics at University of Cambridge.
* [Is life worth living?](https://iwatobipen.wordpress.com/) - Some examples for cheminformatics libraries.
* [Cheminformatics 2.0](https://cheminf20.org/) - Blog of [Alex M. Clark](https://twitter.com/aclarkxyz), a research scientist at Collaborative Drug Discovery.
* [Depth-First](https://depth-first.com/) - Blog of [Richard L. Apodaca](https://depth-first.com/about/), a chemist living in La Jolla, California.
* [Cheminformania](https://www.cheminformania.com) - Blog of [Ph.D, Esben Jannik Bjerrum](https://www.cheminformania.com/about/esben-jannik-bjerrum/), who is a Principle Scientist and a Machine Learning and AI specialists at AstraZeneca.

### Books

* [Computational Approaches in Cheminformatics and Bioinformatics](https://books.google.com/books/about/Computational_Approaches_in_Cheminformat.html?id=bLqV4rYQoYsC) -  Include insights from public (NIH), academic, and industrial sources at the same time.
* [Chemoinformatics for Drug Discovery](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118742785) - Materials about how to use Chemoinformatics strategies to improve drug discovery results.
* [Molecular Descriptors for Chemoinformatics](https://onlinelibrary.wiley.com/doi/book/10.1002/9783527628766) - More than 3300 descriptors and related terms for chemoinformatic analysis of chemical compound properties.

<a id="see-also"></a>
## See Also

* [deeplearning-biology](https://github.com/hussius/deeplearning-biology#chemoinformatics-and-drug-discovery-) - Chemoinformatics and drug discovery section in deeplearning-biology repo.
* [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry) - Another list focuses on Python stuff related to Chemistry.
* [awesome-small-molecule-ml](https://github.com/benb111/awesome-small-molecule-ml) - A list of papers, data sets, and other resources for machine learning for small-molecule drug discovery.
* [MolSSI Molecular Software Database](https://molssi.org/software-search/)
＊[Pages created by Tobias Kind, PhD](https://fiehnlab.ucdavis.edu/staff/kind/metabolomics)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
