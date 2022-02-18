<div class="github-widget" data-repo="cytodata/awesome-cytodata"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cytodata [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome cytodata resources.

![cytodata logo](https://raw.githubusercontent.com/cytodata/awesome-cytodata/master/cytodata-logo.png)

[Cytodata](https://cytodata.org/) refers to a community of researchers and resources involved in the **image-based profiling** of **biological phenotypes**.
These **biological phenotypes** are typically induced by genetic or chemical perturbations and often represent disease states.
**Image-based profiling** is used to inspect these phenotypes to uncover biological insight including discovering the impact of genetic alterations and determining the mechanism of action of compounds.

This page represents a curated list of software, datasets, landmark publications, and image-based profiling methods.
Our goal is to provide researchers, both new and established, a place to discover and document awesome Cytodata resources.



## Datasets

Annotated datasets, including **raw images** and **processed profiles**, for image-based profiling of chemical and genetic perturbations.

### Raw Images

- [Broad Bioimage Benchmark Collection](https://data.broadinstitute.org/bbbc/) - The Broad Bioimage Benchmark Collection (BBBC) is a collection of freely downloadable microscopy image sets. In addition to the images themselves, each set includes a description of the biological application and some type of "ground truth" (expected results).
- [Image Data Resource](https://idr.openmicroscopy.org/) - Public repository of image datasets from published scientific studies.
- [RxRx1](https://www.rxrx.ai/rxrx1) - RxRx1 is a set of 125,514 high-resolution 512x512 6-channel fluorescence microscopy images of human cells under 1,108 genetic perturbations in 51 experimental batches across four cell types.  The images were produced by Recursion Pharmaceuticals in their labs in Salt Lake City, Utah.  Researchers will use this dataset for studying and benchmarking methods for dealing with biological batch effects, as well as areas in machine learning such as domain adaptation, transfer learning, and k-shot learning.
- [RxRx19](https://www.rxrx.ai/rxrx19) - RxRx19 is the first morphological dataset that demonstrates the rescue of morphological effects of COVID-19. 
- [Human Protein Atlas](https://www.proteinatlas.org/humanproteome/subcellular) - Among other assays, the HPA performed confocal imaging of displaying the location of more than 2/3 of human proteins in cell lines. [Raw images](https://github.com/CellProfiling/HPA-competition#script-to-download-hpav18) or [infered protein subcellular locations](https://www.proteinatlas.org/about/download) can be downloaded.

### Chemical Perturbations

- [Gustafsdottir et al. 2013](https://doi.org/10.1371/journal.pone.0080999) - Cell painting profiles from 1,600 bioactive compounds in U2OS cells (Access from public S3 bucket: `s3://cytodata/datasets/Bioactives-BBBC022-Gustafsdottir/profiles/Bioactives-BBBC022-Gustafsdottir/`).
- [Wawer et al. 2014](https://doi.org/10.1073/pnas.1410933111) - Cell painting profiles from 31,770 compounds in U2OS cells ([Click to download](http://www.broadinstitute.org/mlpcn/data/Broad.PNAS2014.ProfilingData.zip)).
- [Bray et al. 2017](https://doi.org/10.1093/gigascience/giw014) - Cell painting profiles from 30,616 compounds in U2OS cells (Center Driven Research Project _CDRP_) ([Download from GigaDB](https://doi.org/10.5524/100351) | Access from public S3 bucket: `s3://cytodata/datasets/CDRPBIO-BBBC036-Bray/profiles_cp/CDRPBIO-BBBC036-Bray/`).
- [Haghighi et al. 2021](https://doi.org/10.1101/2021.09.08.459417) - Cell painting matched to L1000 profiles in 4 experiments, including compound and genetic screens ([Details on GitHub](https://github.com/carpenterlab/2021_Haghighi_submitted)).

### Genetic Perturbations

- [Singh et al. 2015](https://doi.org/10.1371/journal.pone.0131370) - 3,072 cell painting profiles from 41 genes knocked down with RNA interference (RNAi) in U2OS cells ([Access from GitHub](https://github.com/carpenterlab/2016_bray_natprot/blob/6dcdcf72cd90bb2dbf238b3ecf94691246d8f104/supplementary_files/profiles.csv.zip)).
- [Rohban et al. 2017](https://doi.org/10.7554/eLife.24060.001) - Cell painting data from 220 overexpressed genes in U2OS cells (Access from public S3 bucket: `s3://cytodata/datasets/TA-ORF-BBBC037-Rohban/profiles_cp/TA-ORF-BBBC037-Rohban/`).
- Unpublished - Cell painting profiles of 596 overexpressed alleles from 53 genes in A549 cells (Access from public S3 bucket: `s3://cytodata/datasets/LUAD-BBBC043-Caicedo/profiles_cp/LUAD-BBBC043-Caicedo/`)
- Unpublished - 3,456 cell painting profiles from CRISPR experiments knocking down 59 genes in A549, ES2, and HCC44 cells ([Access from GitHub](https://github.com/broadinstitute/cell-health/tree/master/0.generate-profiles/data/profiles)).

## Software

Open source software packages for image-based profiling of biological phenotypes.

- [Advanced Cell Classifier](https://www.cellclassifier.org/) - A software package for exploration, annotation and classification of cells within large datasets using machine learning.
- [CellProfiler](http://cellprofiler.org/) - CellProfiler is a free open-source software for measuring and analyzing cell images.
- [CellProfiler Analyst](http://cellprofiler.org/cp-analyst/) - 大型生物图像集的交互式数据探索、分析和分类。
- [Cytominer](https://github.com/cytomining/cytominer) - Methods for image-based cell profiling in R.
- [EBImage](https://github.com/aoles/EBImage) - Image processing toolbox for R.
- [HTSvis](http://htsvis.dkfz.de/HTSvis/) - A web app for exploratory data analysis and visualization of arrayed high-throughput screens.
- [BioProfiling.jl](https://github.com/menchelab/BioProfiling.jl) - Toolkit for filtering and curation of morphological profiles in Julia.
- [PyCytominer](https://github.com/cytomining/pycytominer) - Methods for image-based cell profiling in Python.
- [ImJoy](https://imjoy.io) - 一个平台编译工具，用于使用 GUI 进行基于深度学习的图像分析。

## Publications

Publications related to image-based profiling.

### Reviews

- [Image-based profiling for drug discovery: due for a machine-learning upgrade?](https://www.nature.com/articles/s41573-020-00117-w) - 2020 review of applications in image-based profiling from a Carpenter lab/pharma perspective.
- [Data-analysis strategies for image-based cell profiling](https://doi.org/10.1038/nmeth.4397) - Introduce the steps required to create high-quality image-based (i.e., morphological) profiles from a collection of microscopy images.
- [High-content screening for quantitative cell biology](https://doi.org/10.1016/j.tcb.2016.03.008) - Describe some recent applications of HCS, ranging from the identification of genes required for specific biological processes to the characterization of genetic interactions.
- [Microscopy-based high-content screening](https://doi.org/10.1016/j.cell.2015.11.007) - Describe the state of the art for image-based screening experiments and delineate experimental approaches and image-analysis approaches as well as discussing challenges and future directions, including leveraging CRISPR/Cas9-mediated genome engineering.
- [Applications in image-based profiling of perturbations](https://doi.org/10.1016/j.copbio.2016.04.003) - Describes applications of image-based profiling including target and MOA identification, lead hopping, library enrichment, gene annotation and identification of disease-specific phenotypes
- [Large-scale image-based screening and profiling of cellular phenotypes](https://doi.org/10.1002/cyto.a.22909) - Overview of image-based profiling, including its applications and challenges.
- [How cells explore shape space: A quantitative statistical perspective of cellular morphogenesis](https://dx.doi.org/10.1002%2Fbies.201400011) - Discussion on the biology of cell shape changes based on quantitative descriptors.
- [Machine learning and image-based profiling in drug discovery](https://doi.org/10.1016/J.COISB.2018.05.004) - Introduction to morphological profiling and discussion on what machine learning has to offer.

### Collections

- [Deep learning in microscopy](https://www.nature.com/collections/cfcdjceech) - A collection of review and research articles published in Nature Methods related to multiple use cases of deep learning, including noise reduction, segmentation, tracking and representation learning.
- [High-Content Imaging and Informatics](https://journals.sagepub.com/toc/jbxb/25/7) - A collection of high-content imaging method and application articles published in SLAS Discovery.

### Applications

- [Expanding the antibacterial selectivity of polyether ionophore antibiotics through diversity-focused semisynthesis](https://rdcu.be/ccBFH) - Poulsen lab paper from 2020 where antibiotics are tested for their ability to leave mammalian cells as intact as possible, per the Cell Painting assay.
- [Image-based multivariate profiling of drug responses from single cells](https://doi.org/10.1038/nmeth1032) - A multivariate method for classifying untreated and treated human cancer cells based on ∼300 single-cell phenotypic measurements.
- [Discovering metabolic disease gene interactions by correlated effects on cellular morphology](https://doi.org/10.1016/j.molmet.2019.03.001) - Profiling disease-gene interaction during adipocyte differentiation.
- [Phenotypic profiling of the human genome by time-lapse microscopy reveals cell division genes](https://doi.org/10.1038/nature08869) - This study provides an in-depth analysis of cell division phenotypes and makes the entire high-content data set available as a resource to the community.
- [Bioactivity screening of environmental chemicals using imaging-based high-throughput phenotypic profiling](https://doi.org/10.1016/j.taap.2019.114876) - Use of image-based profiling to screen the bioactivity of environmental chemicals
- [Repurposing High-Throughput Image Assays Enables Biological Activity Prediction for Drug Discovery](https://doi.org/10.1016/j.chembiol.2018.01.015) - Using image-based profiles to predict the bioactivity of small molecules in other unrelated assays. 
- [Tales of 1,008 Small Molecules: Phenomic Profiling through Live-cell Imaging in a Panel of Reporter Cell Lines](https://doi.org/10.1101/2020.03.13.990093) - Demonstrating the effects of polypharmacology in MOA prediction while offering solutions for overcoming it in future image-based profiling studies.
- [Mapping the perturbome network of cellular perturbations](https://doi.org/10.1038/s41467-019-13058-9) - Image-based profiling and network analysis of drug combinations.
- [Morphological profiling of human T and NK lymphocytes by high-content cell imaging](https://doi.org/10.1016/j.celrep.2021.109318) - Image-based profiling of actin organization at the immunological synapse.
- [A subcellular map of the human proteome](https://doi.org/10.1126/science.aal3321) - Classification of protein subcellular location from confocal microscopy images of the Human Protein Atlas.
- [A multi-scale map of cell structure fusing protein images and interactions](https://doi.org/10.1038/s41586-021-04115-9) - Combining confocal imaging and mass spectrometry representations of proteins to predict physical proximity and characterize cellular organization.
- [Predicting cell health phenotypes using image-based morphology profiling](https://doi.org/10.1091/mbc.E20-12-0784) - Image-based profiles as predictors of apoptosis, proliferation and other cell health descriptors.
- [Systematic genetics and single‐cell imaging reveal widespread morphological pleiotropy and cell‐to‐cell variability](https://doi.org/10.15252/msb.20199243) - Analysis of single-cell profiles to characterize variability, pleiotropy and incomplete penetrance.
- [Large‐scale image‐based profiling of single‐cell phenotypes in arrayed CRISPR‐Cas9 gene perturbation screens](https://doi.org/10.15252/msb.20178064) - Demonstrates feasibility of imaging arrayed CRISPR screens and offers a way to characterize transfection efficacy in individual cells.
- [Multiparametric phenotyping of compound effects on patient derived organoids](https://doi.org/10.1101/660993 ) - Profiling chemical effects on patient-derived organoids.
- [A chemical-genetic interaction map of small molecules using high-throughput imaging in cancer cells](https://doi.org/10.15252/MSB.20156400) - Profiling the morphological changes induced in 1280 compounds in 12 knockout cell lines.
- [Time-resolved mapping of genetic interactions to model rewiring of signaling pathways](https://doi.org/10.7554/eLife.40174) - Changes in genetic interactions across time based on multiple morphological descriptors.
- [High-Content Imaging of Unbiased Chemical Perturbations Reveals that the Phenotypic Plasticity of the Actin Cytoskeleton Is Constrained](https://doi.org/10.1016/j.cels.2019.09.002) - Defining morphological clusters in a large compound screen.
- [A map of directional genetic interactions in a metazoan cell](https://doi.org/10.7554/eLife.05464) - Characterizing genetic interactions by integrating 21 phenotypic descriptors.
- [The phenotypic landscape of essential human genes](https://doi.org/10.1101/2021.11.28.470116) - Comparing morphological descriptors in a pooled CRISPR screen with in-situ sequencing
- [Evaluation of Gene Expression and Phenotypic Profiling Data as Quantitative Descriptors for Predicting Drug Targets and Mechanisms of Action](https://doi.org/10.1101/580654) - Benchmarking profiling modalities, including image-based profiles, for mechanism of action prediction.

### Methods

- [Cell Painting, a high-content image-based assay for morphological profiling using multiplexed fluorescent dyes](https://doi.org/10.1038/nprot.2016.105) - Protocol describing the design and execution of experiments using Cell Painting.
- [Multiplex Cytological Profiling Assay to Measure Diverse Cellular States](https://doi.org/10.1371/journal.pone.0080999) - Cell Painting assay.
- [CIDRE: an illumination-correction method for optical microscopy](https://doi.org/10.1038/nmeth.3323) - Retrospective method for illumination-correction based on energy minimization.
- [Retrospective shading correction based entropy minimization](https://doi.org/10.1046/j.1365-2818.2000.00669.x) - Method for retrospective shading correction based on entropy minimization.
- [Capturing single-cell heterogeneity via data fusion improves image-based profiling](https://doi.org/10.1038/s41467-019-10154-8) - Adds dispersion and covariances to population averages to capture single-cell heterogeneity.
- [Minimum redundancy feature selection from microarray gene expression data](https://doi.org/10.1142/S0219720005001004) - Minimum redundancy - maximum relevance feature selection framework.
- [Learning unsupervised feature representations for single cell microscopy images with paired cell inpainting](https://doi.org/10.1371/journal.pcbi.1007348) - Selfsupervised method to learn feature representations of single cells in microscopy images without labelled training data.
- [Weakly supervised learning of single-cell feature embeddings](https://doi.org/10.1109/CVPR.2018.00970) - Training CNNs using a weakly supervised approach for feature learning.
- [Accurate Prediction of Biological Assays with High-Throughput Microscopy Images and Convolutional Networks](https://doi.org/10.1021/acs.jcim.8b00670) - End-to-end learning with CNNs to predict bioactivity of small molecules in unrelated assays using image-based profiles.
- [Evaluation of Deep Learning Strategies for Nucleus Segmentation in Fluorescence Images](https://doi.org/10.1002/cyto.a.23863) - Comparing several deep learning methods for nuclear segmentation. 
- [Automating Morphological Profiling with Generic Deep Convolutional Networks](https://doi.org/10.1101/085118) - Transfer of activation features of generic CNNs to extract features for image-based profiling.
- [A BaSiC tool for background and shading correction of optical microscopy images](https://doi.org/10.1038/ncomms14836) - Illumination-correction method accounting for space- and time-dependent biases.
- [Cellpose: a generalist algorithm for cellular segmentation](https://doi.org/10.1038/s41592-020-01018-x) - Generalist deep learning model for cell and nucleus segmentation with pre-trained weights.
- [Deep Learning Automates the Quantitative Analysis of Individual Cells in Live-Cell Imaging Experiments](https://doi.org/10.1371/journal.pcbi.1005177) - DeepCell: collection of deep learning segmentation models.
- [Improving Phenotypic Measurements in
High-Content Imaging Screens](https://doi.org/10.1101/161422) - Embedding single-cell and compound profiles using transfer learning, examplified on mechanism of action prediction.
- [The Multidimensional Perturbation Value](https://doi.org/10.1177/1087057112469257) - Proposing a score to define significant activity in screens.
- [Label-Free Prediction of Cell Painting from Brightfield Images](https://doi.org/10.1101/2021.11.05.467394) - Reconstructing images for Cell Painting dyes and ensuring corresponding morphological measurements are preserved.
- [ShapoGraphy: a glyph-oriented visualisation approach for creating pictorial
representations of bioimaging data](https://doi.org/10.1101/2021.04.07.438792) - Method to visualize morphological profiles.
- [CytoGAN: Generative Modeling of Cell Images](https://doi.org/10.1101/227645) - Generative network displaying potential for learning latent representation of biological conditions from cell images.
- [Self-supervised feature extraction from image time series in plant phenotyping using triplet networks](https://doi.org/https://doi.org/10.1093/bioinformatics/btaa905) - Direct extraction of phenotypic features from plant images.

## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/cytodata/awesome-cytodata/blob/master/contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)
