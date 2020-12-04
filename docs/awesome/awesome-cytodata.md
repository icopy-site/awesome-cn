<div class="github-widget" data-repo="cytodata/awesome-cytodata"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cytodata [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt;精选的绝佳细胞数据资源清单.

![cytodata logo](https://raw.githubusercontent.com/cytodata/awesome-cytodata/master/cytodata-logo.png)

[Cytodata](https://cytodata.org/) 指参与生物表型的基于图像的分析的研究人员和资源社区.
这些“生物学表型”通常是由遗传或化学扰动引起的，通常代表疾病状态.
**基于图像的分析**用于检查这些表型，以发现生物学见解，包括发现遗传改变的影响并确定化合物的作用机理.

此页面代表软件，数据集，地标出版物和基于图像的分析方法的精选列表.
我们的目标是为新老研究人员提供一个发现和记录精妙的Cytodata资源的地方.



## Datasets

带注释的数据集，包括“原始图像”和“处理后的配置文件”，用于基于图像的化学和遗传扰动分析.

### Raw Images

- [Broad Bioimage Benchmark Collection](https://data.broadinstitute.org/bbbc/)  -广泛的生物影像基准收集（BBBC）是可免费下载的显微图像集的集合. 除了图像本身，每组图像还包括对生物应用程序的描述以及某种类型的“地面真相”（预期结果）.
- [Image Data Resource](https://idr.openmicroscopy.org/) -来自已发表科学研究的图像数据集的公共存储库.
- [RxRx1](https://www.rxrx.ai/rxrx1)  -RxRx1是一组125,514幅高分辨率的512x512 6通道荧光显微镜图像，在4种细胞类型的51个实验批次中，经过1108次遗传扰动后，人类细胞处于该状态. 这些图像是由Recursion Pharmaceuticals在犹他州盐湖城的实验室中制作的. 研究人员将使用该数据集来研究和基准化方法，以处理生物批次效应以及机器学习领域，例如领域适应，转移学习和k-shot学习.
- [RxRx19](https://www.rxrx.ai/rxrx19) -RxRx19是第一个形态数据集，展示了COVID-19形态效应的挽救. 

### Chemical Perturbations

- [Gustafsdottir et al. 2013](https://doi.org/10.1371/journal.pone.0080999) -U2OS细胞中1600种生物活性化合物的细胞绘画特征（可从公共S3存储桶访问：`s3：// cytodata / datasets / Bioactives-BBBC022-Gustafsdottir / profiles / Bioactives-BBBC022-Gustafsdottir /）.
- [Wawer et al. 2014](https://doi.org/10.1073/pnas.1410933111) -U2OS细胞中31,770种化合物的细胞绘画特征（[Click to download](http://www.broadinstitute.org/mlpcn/data/Broad.PNAS2014.ProfilingData.zip)).
- [Bray et al. 2017](https://doi.org/10.1093/gigascience/giw014) -U2OS细胞中30,616种化合物的细胞绘画特征（中心驱动研究项目_CDRP _）（[Download from GigaDB](https://doi.org/10.5524/100351)  | 从公共S3存储桶访问：`s3：// cytodata / datasets / CDRPBIO-BBBC036-Bray / profiles_cp / CDRPBIO-BBBC036-Bray /）.

### Genetic Perturbations

- [Singh et al. 2015](https://doi.org/10.1371/journal.pone.0131370) -U2OS细胞中来自RNA干扰（RNAi）的41个基因的3,072个细胞绘画图谱（[Access from GitHub](https://github.com/carpenterlab/2016_bray_natprot/blob/6dcdcf72cd90bb2dbf238b3ecf94691246d8f104/supplementary_files/profiles.csv.zip)).
- [Rohban et al. 2017](https://doi.org/10.7554/eLife.24060.001) -来自U2OS细胞中220个过表达基因的细胞绘画数据（来自公共S3存储桶：`s3：// cytodata / datasets / TA-ORF-BBBC037-Rohban / profiles_cp / TA-ORF-BBBC037-Rohban /`）.
-未发表-A549细胞中53个基因的596个过表达等位基因的细胞绘画图谱（来自公共S3存储桶：`s3：// cytodata / datasets / LUAD-BBBC043-Caicedo / profiles_cp / LUAD-BBBC043-Caicedo /`）
- Unpublished - 3,456 cell painting profiles from CRISPR experiments knocking down 59 genes in A549, ES2, and HCC44 cells ([Access from GitHub](https://github.com/broadinstitute/cell-health/tree/master/0.generate-profiles/data/profiles)).

## Software

开源软件包，用于基于图像的生物表型分析.

- [Advanced Cell Classifier](https://www.cellclassifier.org/) -使用机器学习对大型数据集中的细胞进行探索，注释和分类的软件包.
- [CellProfiler](http://cellprofiler.org/) -CellProfiler是用于测量和分析细胞图像的免费开源软件.
- [CellProfiler Analyst](http://cellprofiler.org/cp-analyst/) -大型生物图像集的交互式数据探索，分析和分类.
- [Cytominer](https://github.com/cytomining/cytominer) -基于图像的单元分析的方法.
- [EBImage](https://github.com/aoles/EBImage) -R的图像处理工具箱.
- [HTSvis](http://htsvis.dkfz.de/HTSvis/) -用于探索性数据分析和可视化阵列高通量屏幕的Web应用程序.

## Publications

与基于图像的性能分析有关的出版物.

### Reviews

- [Data-analysis strategies for image-based cell profiling](https://doi.org/10.1038/nmeth.4397) -介绍从显微镜图像集中创建高质量的基于图像（即形态学）的轮廓所需的步骤.
- [High-content screening for quantitative cell biology](https://doi.org/10.1016/j.tcb.2016.03.008) -描述HCS的一些最新应用，从特定生物学过程所需的基因鉴定到遗传相互作用的表征.
- [Microscopy-based high-content screening](https://doi.org/10.1016/j.cell.2015.11.007) -描述基于图像的筛选实验的最新技术，描述实验方法和图像分析方法以及讨论挑战和未来方向，包括利用CRISPR / Cas9介导的基因组工程.
- [Applications in image-based profiling of perturbations](https://doi.org/10.1016/j.copbio.2016.04.003) -描述基于图像的轮廓分析的应用，包括靶标和MOA识别，铅跳跃，文库富集，基因注释和疾病特异性表型的识别

### Applications

- [Image-based multivariate profiling of drug responses from single cells](https://doi.org/10.1038/nmeth1032) -基于约300个单细胞表型测量结果对未治疗和已治疗的人类癌细胞进行分类的多变量方法.
- [Discovering metabolic disease gene interactions by correlated effects on cellular morphology](https://doi.org/10.1016/j.molmet.2019.03.001) -在脂肪细胞分化过程中分析疾病与基因的相互作用.
- [Phenotypic profiling of the human genome by time-lapse microscopy reveals cell division genes](https://doi.org/10.1038/nature08869) -这项研究提供了对细胞分裂表型的深入分析，并使整个高内涵数据集可作为资源提供给社区.
- [Bioactivity screening of environmental chemicals using imaging-based high-throughput phenotypic profiling](https://doi.org/10.1016/j.taap.2019.114876) -使用基于图像的分析来筛选环境化学品的生物活性
- [Repurposing High-Throughput Image Assays Enables Biological Activity Prediction for Drug Discovery](https://doi.org/10.1016/j.chembiol.2018.01.015) -使用基于图像的配置文件来预测小分子在其他无关测定中的生物活性. 
- [Tales of 1,008 Small Molecules: Phenomic Profiling through Live-cell Imaging in a Panel of Reporter Cell Lines](https://doi.org/10.1101/2020.03.13.990093) -演示多药理学在MOA预测中的作用，同时提供解决方案，以在未来基于图像的性能分析研究中克服该问题.

### Methods

- [Cell Painting, a high-content image-based assay for morphological profiling using multiplexed fluorescent dyes](https://doi.org/10.1038/nprot.2016.105) -使用Cell Painting描述实验设计和执行的协议.
- [Multiplex Cytological Profiling Assay to Measure Diverse Cellular States](https://doi.org/10.1371/journal.pone.0080999) -细胞绘画测定.
- [CIDRE: an illumination-correction method for optical microscopy](https://doi.org/10.1038/nmeth.3323) -基于能量最小化的照明校正的追溯方法.
- [Retrospective shading correction based entropy minimization](https://doi.org/10.1046/j.1365-2818.2000.00669.x) -基于熵最小化的回顾性阴影校正方法.
- [Capturing single-cell heterogeneity via data fusion improves image-based profiling](https://doi.org/10.1038/s41467-019-10154-8) -将分散和协方差添加到总体平均值以捕获单细胞异质性.
- [Minimum redundancy feature selection from microarray gene expression data](https://doi.org/10.1142/S0219720005001004) -最小冗余-最大相关性功能选择框架.
- [Learning unsupervised feature representations for single cell microscopy images with paired cell painting](https://doi.org/10.1101/395954) -自我监督的方法，无需标记训练数据即可在显微镜图像中学习单个细胞的特征表示.
- [Weakly supervised learning of single-cell feature embeddings](https://doi.org/10.1109/CVPR.2018.00970) -使用弱监督方法对CNN进行特征学习.
- [Accurate Prediction of Biological Assays with High-Throughput Microscopy Images and Convolutional Networks](https://doi.org/10.1021/acs.jcim.8b00670) -使用基于图像的配置文件，在不相关的分析中使用CNN进行端到端学习，以预测小分子的生物活性.
- [Evaluation of Deep Learning Strategies for Nucleus Segmentation in Fluorescence Images](https://doi.org/10.1002/cyto.a.23863) -比较几种用于核分割的深度学习方法. 
- [Automating Morphological Profiling with Generic Deep Convolutional Networks](https://doi.org/10.1101/085118) -转移通用CNN的激活特征以提取特征以进行基于图像的分析.

## Contribute

欢迎捐款！ 阅读 [contribution guidelines](https://github.com/cytodata/awesome-cytodata/blob/master/contributing.md) 第一.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)
