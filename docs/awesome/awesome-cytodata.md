<div class="github-widget" data-repo="cytodata/awesome-cytodata"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Cytodata [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; 精选的细胞数据资源列表.

![cytodata logo](https://raw.githubusercontent.com/cytodata/awesome-cytodata/master/cytodata-logo.png)

[Cytodata](https://cytodata.org/) 是指参与**生物表型**的**基于图像的分析**的研究人员和资源社区.
这些**生物表型**通常由遗传或化学扰动引起，通常代表疾病状态.
**基于图像的分析** 用于检查这些表型以揭示生物学洞察力，包括发现遗传改变的影响和确定化合物的作用机制.

此页面代表了软件、数据集、地标出版物和基于图像的分析方法的精选列表.
我们的目标是为新老研究人员提供一个发现和记录出色的 Cytodata 资源的地方.



## Datasets

带注释的数据集，包括**原始图像**和**处理过的配置文件**，用于基于图像的化学和遗传扰动分析.

### Raw Images

- [Broad Bioimage Benchmark Collection](https://data.broadinstitute.org/bbbc/)  - Broad Bioimage Benchmark Collection (BBBC) 是可免费下载的显微镜图像集的集合. 除了图像本身之外，每组图像还包括对生物学应用的描述和某种类型的“基本事实”（预期结果）.
- [Image Data Resource](https://idr.openmicroscopy.org/) - 来自已发表科学研究的图像数据集的公共存储库.
- [RxRx1](https://www.rxrx.ai/rxrx1)  - RxRx1 是一组 125,514 张高分辨率 512x512 6 通道荧光显微镜图像，这些图像显示了四种细胞类型的 51 个实验批次中 1,108 次遗传扰动下的人类细胞. 这些图像是由 Recursion Pharmaceuticals 在其位于犹他州盐湖城的实验室中制作的. 研究人员将使用该数据集来研究处理生物批次效应的方法和基准测试方法，以及领域适应、迁移学习和 k-shot 学习等机器学习领域.
- [RxRx19](https://www.rxrx.ai/rxrx19) - RxRx19 是第一个证明挽救 COVID-19 形态学效应的形态学数据集. 
- [Human Protein Atlas](https://www.proteinatlas.或者g/humanproteome/subcellular) - 在其他检测中，HPA 进行了共聚焦成像，显示了超过 2/3 的人类蛋白质在细胞系中的位置. [Raw images](https://github.com/CellProfiling/HPA-competition#script-to-download-hpav18) 或者 [infered protein subcellular locations](https://www.proteinatlas.或者g/about/download) 可以下载.

### Chemical Perturbations

- [Gustafsdottir et al. 2013](https://doi.org/10.1371/journal.pone.0080999) - U2OS 细胞中 1,600 种生物活性化合物的细胞绘画概况（从公共 S3 存储桶访问：`s3://cytodata/datasets/Bioactives-BBBC022-Gustafsdottir/profiles/Bioactives-BBBC022-Gustafsdottir/`）.
- [Wawer et al. 2014](https://doi.org/10.1073/pnas.1410933111) - U2OS 细胞中 31,770 种化合物的细胞绘画概况（[Click to download](http://www.broadinstitute.org/mlpcn/data/Broad.PNAS2014.ProfilingData.zip)).
- [Bray et al. 2017](https://doi.org/10.1093/gigascience/giw014) - 来自 U2OS 细胞中 30,616 种化合物的细胞绘画概况（中心驱动研究项目 _CDRP_）（[Download from GigaDB](https://doi.org/10.5524/100351)  | 从公共 S3 存储桶访问：`s3://cytodata/datasets/CDRPBIO-BBBC036-Bray/profiles_cp/CDRPBIO-BBBC036-Bray/`).
- [Haghighi et al. 2021](https://doi.org/10.1038/s41592-022-01667-0) - 细胞绘画在 4 个实验中与 L1000 配置文件相匹配，包括化合物和遗传筛选（[Details on GitHub](https://github.com/carpenterlab/2021_Haghighi_submitted)).

### Genetic Perturbations

- [Singh et al. 2015](https://doi.org/10.1371/journal.pone.0131370) - 来自 41 个基因的 3,072 个细胞绘画图谱在 U2OS 细胞中被 RNA 干扰 (RNAi) 击倒 ([Access from GitHub](https://github.com/carpenterlab/2016_bray_natprot/blob/6dcdcf72cd90bb2dbf238b3ecf94691246d8f104/supplementary_files/profiles.csv.zip)).
- [Rohban et al. 2017](https://doi.org/10.7554/eLife.24060.001) - 来自 U2OS 细胞中 220 个过表达基因的细胞绘画数据（从公共 S3 存储桶访问：`s3://cytodata/datasets/TA-ORF-BBBC037-Rohban/profiles_cp/TA-ORF-BBBC037-Rohban/`）.
- 未发表 - A549 细胞中 53 个基因的 596 个过表达等位基因的细胞绘画概况（从公共 S3 存储桶访问：`s3://cytodata/datasets/LUAD-BBBC043-Caicedo/profiles_cp/LUAD-BBBC043-Caicedo/`）
- 未发表 - 来自 CRISPR 实验的 3,456 个细胞绘画图谱敲除 A549、ES2 和 HCC44 细胞中的 59 个基因（[Access from GitHub](https://github.com/broadinstitute/cell-health/tree/master/0.generate-profiles/data/profiles)).

## Software

用于基于图像的生物表型分析的开源软件包.

- [Advanced Cell Classifier](https://www.cellclassifier.org/) - 一个软件包，用于使用机器学习对大型数据集中的细胞进行探索、注释和分类.
- [CellProfiler](http://cellprofiler.org/) - CellProfiler 是一款用于测量和分析细胞图像的免费开源软件.
- [CellProfiler Analyst](http://cellprofiler.org/cp-analyst/) - 大型生物图像集的交互式数据探索、分析和分类.
- [Cytominer](https://github.com/cytomining/cytominer) - R 中基于图像的细胞分析方法.
- [EBImage](https://github.com/aoles/EBImage) - R 的图像处理工具箱.
- [HTSvis](http://htsvis.dkfz.de/HTSvis/) - 用于探索性数据分析和阵列高通量屏幕可视化的网络应用程序.
- [BioProfiling.jl](https://github.com/menchelab/BioProfiling.jl) - 用于在 Julia 中过滤和管理形态学配置文件的工具包.
- [PyCytominer](https://github.com/cytomining/pycytominer) - 在 Python 中进行基于图像的细胞分析的方法.
- [ImJoy](https://imjoy.io) - 一个平台编译工具，用于使用 GUI 进行基于深度学习的图像分析.
- [histoCAT](https://github.com/BodenmillerGroup/histoCAT) - 为组织学和多重成像提取定量表型描述符和上下文信息的工具箱.

## Publications

与基于图像的分析相关的出版物.

### Reviews

- [Image-based profiling for drug discovery: due for a machine-learning upgrade?](https://www.nature.com/articles/s41573-020-00117-w) - 2020 年从 Carpenter 实验室/制药公司的角度审查基于图像的分析应用.
- [Data-analysis strategies for image-based cell profiling](https://doi.org/10.1038/nmeth.4397) - 介绍从一组显微镜图像中创建高质量的基于图像（即形态学）的配置文件所需的步骤.
- [High-content screening for quantitative cell biology](https://doi.org/10.1016/j.tcb.2016.03.008) - 描述 HCS 最近的一些应用，从特定生物过程所需基因的鉴定到遗传相互作用的表征.
- [Microscopy-based high-content screening](https://doi.org/10.1016/j.cell.2015.11.007) - 描述基于图像的筛选实验的最新技术，描述实验方法和图像分析方法，并讨论挑战和未来方向，包括利用 CRISPR/Cas9 介导的基因组工程.
- [Applications in image-based profiling of perturbations](https://doi.org/10.1016/j.copbio.2016.04.003) - 描述基于图像的分析的应用，包括目标和 MOA 识别、铅跳跃、图书馆富集、基因注释和疾病特定表型的识别
- [Large-scale image-based screening and profiling of cellular phenotypes](https://doi.org/10.1002/cyto.a.22909) - 基于图像的分析概述，包括其应用和挑战.
- [How cells explore shape space: A quantitative statistical perspective of cellular morphogenesis](https://dx.doi.org/10.1002%2Fbies.201400011) - 基于定量描述符的细胞形状变化生物学讨论.
- [Machine learning and image-based profiling in drug discovery](https://doi.org/10.1016/J.COISB.2018.05.004) - 介绍形态分析和讨论机器学习必须提供的内容.
- [Pooled genetic screens with image-based profiling](https://doi.org/10.15252/msb.202110768) - 审查可用于遗传筛选的不同方式以及哪些方式适用于形态学分析.

### Collections

- [Deep learning in microscopy](https://www.nature.com/collections/cfcdjceech) - 发表在 Nature Methods 上的一系列评论和研究文章，涉及深度学习的多个用例，包括降噪、分割、跟踪和表征学习.
- [High-Content Imaging and Informatics](https://journals.sagepub.com/toc/jbxb/25/7) - SLAS Discovery 发表的高内涵成像方法和应用文章合集.

### Applications

- [Expanding the antibacterial selectivity of polyether ionophore antibiotics through diversity-focused semisynthesis](https://rdcu.be/ccBFH) - 2020 年的 Poulsen 实验室论文，其中根据 Cell Painting 测定，测试了抗生素使哺乳动物细胞尽可能完好无损的能力.
- [Image-based multivariate profiling of drug responses from single cells](https://doi.org/10.1038/nmeth1032) - 基于约 300 个单细胞表型测量对未处理和处理过的人类癌细胞进行分类的多变量方法.
- [Discovering metabolic disease gene interactions by correlated effects on cellular morphology](https://doi.org/10.1016/j.molmet.2019.03.001) - 分析脂肪细胞分化过程中的疾病-基因相互作用.
- [Phenotypic profiling of the human genome by time-lapse microscopy reveals cell division genes](https://doi.org/10.1038/nature08869) - 本研究提供了对细胞分裂表型的深入分析，并将整个高含量数据集作为资源提供给社区.
- [Bioactivity screening of environmental chemicals using imaging-based high-throughput phenotypic profiling](https://doi.org/10.1016/j.taap.2019.114876) - 使用基于图像的分析来筛选环境化学品的生物活性
- [Repurposing High-Throughput Image Assays Enables Biological Activity Prediction for Drug Discovery](https://doi.org/10.1016/j.chembiol.2018.01.015) - 使用基于图像的配置文件来预测其他不相关测定中小分子的生物活性. 
- [Tales of 1,008 Small Molecules: Phenomic Profiling through Live-cell Imaging in a Panel of Reporter Cell Lines](https://doi.org/10.1038/s41598-020-69354-8) - 展示多药理学在 MOA 预测中的作用，同时提供在未来基于图像的分析研究中克服它的解决方案.
- [Mapping the perturbome network of cellular perturbations](https://doi.org/10.1038/s41467-019-13058-9) - 药物组合的基于图像的分析和网络分析.
- [Morphological profiling of human T and NK lymphocytes by high-content cell imaging](https://doi.org/10.1016/j.celrep.2021.109318) - 免疫突触肌动蛋白组织的基于图像的分析.
- [A subcellular map of the human proteome](https://doi.org/10.1126/science.aal3321) - 根据人类蛋白质图谱的共聚焦显微镜图像对蛋白质亚细胞定位进行分类.
- [A multi-scale map of cell structure fusing protein images and interactions](https://doi.org/10.1038/s41586-021-04115-9) - 结合蛋白质的共聚焦成像和质谱表示来预测物理接近度并表征细胞组织.
- [Predicting cell health phenotypes using image-based morphology profiling](https://doi.org/10.1091/mbc.E20-12-0784) - 基于图像的配置文件作为细胞凋亡、增殖和其他细胞健康描述符的预测因子.
- [Systematic genetics and single‐cell imaging reveal widespread morphological pleiotropy and cell‐to‐cell variability](https://doi.org/10.15252/msb.20199243) - 分析单细胞概况以表征可变性、多效性和不完全外显率.
- [Large‐scale image‐based profiling of single‐cell phenotypes in arrayed CRISPR‐Cas9 gene perturbation screens](https://doi.org/10.15252/msb.20178064) - 展示成像阵列 CRISPR 屏幕的可行性，并提供一种表征单个细胞转染功效的方法.
- [Multiparametric phenotyping of compound effects on patient derived organoids](https://doi.org/10.1038/s41467-022-30722-9) -分析对患者来源的类器官的化学影响.
- [A chemical-genetic interaction map of small molecules using high-throughput imaging in cancer cells](https://doi.org/10.15252/MSB.20156400) - 分析 12 个基因敲除细胞系中 1280 种化合物诱导的形态变化.
- [Time-resolved mapping of genetic interactions to model rewiring of signaling pathways](https://doi.org/10.7554/eLife.40174) - 基于多个形态描述符的跨时间遗传相互作用变化.
- [High-Content Imaging of Unbiased Chemical Perturbations Reveals that the Phenotypic Plasticity of the Actin Cytoskeleton Is Constrained](https://doi.org/10.1016/j.cels.2019.09.002) - 在大型复合屏幕中定义形态簇.
- [A map of directional genetic interactions in a metazoan cell](https://doi.org/10.7554/eLife.05464) - 通过整合 21 个表型描述符来表征遗传相互作用.
- [The phenotypic landscape of essential human genes](https://doi.org/10.1016/j.cell.2022.10.017) - 将合并的 CRISPR 筛选中的形态学描述符与原位测序进行比较
- [Evaluation of Gene Expression and Phenotypic Profiling Data as Quantitative Descriptors for Predicting Drug Targets and Mechanisms of Action](https://doi.org/10.1101/580654) - 基准分析模式，包括基于图像的配置文件，用于行动预测机制.
- [The molecular architecture of cell cycle arrest](https://doi.org/10.15252/msb.202211087) - 比较细胞周期各个阶段的细胞特征.
- [Integrated intracellular organization and its variations in human iPS cells](https://doi.org/10.1038/s41586-022-05563-7) - 在多个 iPSC 中分解 3D 细胞和核形状并研究细胞结构之间的关联.
- [Single-cell metabolic profiling of human cytotoxic T cells](https://doi.org/10.1038/s41587-020-0651-8) - 结合代谢分析和空间信息来定义肿瘤微环境中的免疫亚群.
- [The single-cell pathology landscape of breast cancer](https://doi.org/10.1038/s41586-019-1876-x) - 根据来自多重成像的形状、强度和背景信息来定义细胞群及其在乳腺癌中的相互作用.
- [Identification of phenotype-specific networks from paired gene expression–cell shape imaging data](https://doi.org/10.1101%2Fgr.276059.121) - 通过匹配表达和成像数据寻找细胞形态学背后的基因网络.
- [Predicting drug polypharmacology from cell morphology readouts using variational autoencoder latent space arithmetic](https://doi.org/10.1371/journal.pcbi.1009888) - 使用自动编码器对细胞形态进行建模，以估计药物组合的效果.
- [Deep Morphology Learning Enhances Ex Vivo Drug Profiling-Based Precision Medicine](https://doi.org/10.1158/2643-3230.BCD-21-0219) - 具体描述如何从患者材料中提取形态学信息并指导治疗.

### Methods

- [Cell Painting, a high-content image-based assay for morphological profiling using multiplexed fluorescent dyes](https://doi.org/10.1038/nprot.2016.105) - 描述使用 Cell Painting 进行实验设计和执行的协议.
- [Multiplex Cytological Profiling Assay to Measure Diverse Cellular States](https://doi.org/10.1371/journal.pone.0080999) - 细胞绘画分析.
- [CIDRE: an illumination-correction method for optical microscopy](https://doi.org/10.1038/nmeth.3323) - 基于能量最小化的光照校正追溯法.
- [Retrospective shading correction based entropy minimization](https://doi.org/10.1046/j.1365-2818.2000.00669.x) - 基于熵最小化的追溯阴影校正方法.
- [Capturing single-cell heterogeneity via data fusion improves image-based profiling](https://doi.org/10.1038/s41467-019-10154-8) - 将离散度和协方差添加到总体平均值以捕获单细胞异质性.
- [Minimum redundancy feature selection from microarray gene expression data](https://doi.org/10.1142/S0219720005001004) - 最小冗余 - 最大相关性特征选择框架.
- [Learning unsupervised feature representations for single cell microscopy images with paired cell inpainting](https://doi.org/10.1371/journal.pcbi.1007348) - 在没有标记训练数据的情况下学习显微图像中单个细胞特征表示的自监督方法.
- [Weakly supervised learning of single-cell feature embeddings](https://doi.org/10.1109/CVPR.2018.00970) - 使用弱监督方法训练 CNN 进行特征学习.
- [Accurate Prediction of Biological Assays with High-Throughput Microscopy Images and Convolutional Networks](https://doi.org/10.1021/acs.jcim.8b00670) - 使用 CNN 进行端到端学习，以使用基于图像的配置文件预测不相关测定中小分子的生物活性.
- [Evaluation of Deep Learning Strategies for Nucleus Segmentation in Fluorescence Images](https://doi.org/10.1002/cyto.a.23863) - 比较几种用于核分割的深度学习方法. 
- [Automating Morphological Profiling with Generic Deep Convolutional Networks](https://doi.org/10.1101/085118) - 转移通用 CNN 的激活特征以提取特征以进行基于图像的分析.
- [A BaSiC tool for background and shading correction of optical microscopy images](https://doi.org/10.1038/ncomms14836) - 考虑空间和时间依赖性偏差的照明校正方法.
- [Cellpose: a generalist algorithm for cellular segmentation](https://doi.org/10.1038/s41592-020-01018-x) - 具有预训练权重的细胞和细胞核分割的通才深度学习模型.
- [Deep Learning Automates the Quantitative Analysis of Individual Cells in Live-Cell Imaging Experiments](https://doi.org/10.1371/journal.pcbi.1005177) - DeepCell：深度学习分割模型的集合.
- [改进表型测量
High-Content Imaging Screens](https://doi.org/10.1101/161422) - 使用迁移学习嵌入单细胞和复合图谱，以作用预测机制为例.
- [The Multidimensional Perturbation Value](https://doi.org/10.1177/1087057112469257) - 提出一个分数来定义屏幕中的重要活动.
- [Label-Free Prediction of Cell Painting from Brightfield Images](https://doi.org/10.1038/s41598-022-12914-x) - 重建细胞绘画染料的图像并确保保留相应的形态学测量值.
- [ShapoGraphy: A User-Friendly Web Application for Creating Bespoke and Intuitive Visualisation of Biomedical Data](https://doi.org/10.3389/fbinf.2022.788607) - 可视化形态剖面的方法.
- [CytoGAN: Generative Modeling of Cell Images](https://doi.org/10.1101/227645) - Generative network displaying potential for learning latent representation of biological conditions from cell images.
- [Self-supervised feature extraction from image time series in plant phenotyping using triplet networks](https://doi.org/https://doi.org/10.1093/bioinformatics/btaa905) - Direct extraction of phenotypic features from plant images.
- [Morphology and gene expression profiling provide complementary information for mapping cell state](https://doi.org/10.1016/j.cels.2022.10.001) - 比较相同扰动的细胞绘画和 L1000 分析中包含的信息.
- [Fully unsupervised deep mode of action learning for phenotyping high-content cellular images](https://doi.org/10.1093/bioinformatics/btab497)  - 无监督的方法来表示细胞形态与集群对应的有意义的关系，如作用机制. 概述了用于形态学分析和分类的深度学习方法.
- [Automated high-speed 3D imaging of organoid cultures with multi-scale phenotypic quantification](https://doi.org/10.1038/s41592-022-01508-0) - 使用光片显微镜提取类器官 3D 形态描述符的实验和计算工作流程.

## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/cytodata/awesome-cytodata/blob/master/contributing.md) 第一的.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)
