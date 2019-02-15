令人敬畏的生物信息学 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/danielecook/Awesome-Bioinformatics.svg?branch=master)](https://travis-ci.org/danielecook/Awesome-Bioinformatics)
======================

 &gt;生物信息学是一个跨学科领域，开发用于理解生物数据的方法和软件工具.   -  [Wikipedia](https://en.wikipedia.org/wiki/Bioinformatics)

 精选的生物信息学软件，资源和库的精选列表.  主要是基于命令行，免费或开源.  请随意 [contribute](https://github.com/danielecook/Awesome-Bioinformatics/blob/master/CONTRIBUTING.md)!

**目录**

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Package suites](#package-suites)
  - [R: Bioconductor](#bioconductor)
  - [Python: Biopython](#biopython)
  - [Bioconda](#bioconda)
- [Data Processing](#data-processing)
  - [Command Line Utilities](#command-line-utilities)
- [Next Generation Sequencing](#next-generation-sequencing)
  - [Pipelines/Pipeline frameworks](#pipelinespipeline-frameworks)
  - [Sequence Processing](#sequence-processing)
  - [Sequence Alignment](#sequence-alignment)
  - [Variant Calling](#variant-calling)
  - [BAM File Utilities](#bam-file-utilities)
  - [VCF File Utilities](#vcf-file-utilities)
  - [GFF BED File Utilities](#gff-bed-file-utilities)
  - [Variant Simulation](#variant-simulation)
  - [Variant Filtering / Quality Control](#variant-filtering--quality-control)
  - [Variant Prediction/Annotation](#variant-predictionannotation)
  - [Python Modules](#python-modules)
    - [Data](#data)
    - [Tools](#tools)
- [Visualization](#visualization)
  - [Genome Browsers / Gene diagrams](#genome-browsers--gene-diagrams)
  - [Circos Related](#circos-related)
- [Database Access](#database-access)
- [Resources](#resources)
  - [Becoming a Bionformatician](#becoming-a-bioinformatician)
  - [Sequencing](#sequencing)
  - [RNA-Seq](#rna-seq)
  - [ChIP-Seq](#chip-seq)
  - [YouTube Channels and Playlists](#youtube-channels-and-playlists)
  - [Blogs](#blogs)
  - [Miscellaneous](#miscellaneous)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

----

## Package suites

 软件包套件为特定语言或平台收集软件包和安装工具.  我们有一些生物信息学软件.

### Bioconductor

* __[Bioconductor](https://www.bioconductor.org/)__  - 用于分析和理解高通量基因组数据的大量工具，包括1500多个软件包.

### Biopython

* __[Biopython](https://biopython.org/)_ _  - 免费提供的Python生物计算工具，包括食谱，包装和全面的文档.  的一部分 [Open Bioinformatics Foundation](http://open-bio.org/) .  包含非常有用 [Entrez](https://biopython.org/DIST/docs/api/Bio.Entrez-module.html) 用于API访问NCBI数据库的包.

### Bioconda

* __[Bioconda](https://bioconda.github.io/)__  - 一个频道 [conda package manager](http://conda.pydata.org/docs/intro.html)  专注于生物信息学软件.  包括一个包含3000+可立即安装（带有“conda install”）生物信息学包的存储库.

## Data Processing

### Command Line Utilities

* __[Bioinformatics One Liners](https://github.com/stephenturner/oneliners)__  - 有用的单行命令的Git repo.
* __[BioNode](https://www.bionode.io/)__  - 模块化和通用生物信息学，Bionode为生物信息学分析工作流程提供可管理的UNIX命令行工具和JavaScript API.
* __[bioSyntax](http://www.bioSyntax.org/)__  -  vim / less / gedit / sublime中的计算生物学文件格式（SAM，VCF，GTF，FASTA，PDB等）的语法突出显示.
* __[CSVKit](https://github.com/wireservice/csvkit)__  - 用于处理CSV /制表符分隔文件的实用程序.
* __[csvtk](https://github.com/shenwei356/csvtk)__  - 另一个跨平台，高效，实用且漂亮的CSV / TSV工具包.
* __[datamash](http://www.gnu.org/software/datamash/)__  - 数据转换和统计.
* __[easy_qsub](https://github.com/shenwei356/easy_qsub)_ _  - 使用脚本模板轻松提交PBS作业.  支持多个输入文件.
* __[GNU `parallel`](http://www.gnu.org/software/parallel/)__  - 在单个多核计算机上并行运行作业的通用并行程序. [Here](https://www.biostars.org/p/63816/) 是一些使用GNU“parallel”的示例脚本.
* __[grabix](https://github.com/arq5x/grabix)__  - 用于随机访问BGZF文件的小工具.
* __[tabix](https://github.com/samtools/tabix)__  - 表文件索引.
* __[wormtable](https://github.com/wormtable/wormtable)__  - 针对大型数据集的Write-once-read-many表.
* __[zindex](https://github.com/mattgodbolt/zindex)__  - 在压缩文本文件上创建索引.

## Next Generation Sequencing

### Pipelines/Pipeline frameworks

* __[Awesome-Pipeline](https://github.com/pditommaso/awesome-pipeline)__  - 管道资源列表.
* __[bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen)__  - 电池包括用于变体和RNA-Seq分析的基因组分析管道，结构变体调用，注释和预测.
* __[BigDataScript](https://pcingola.github.io/BigDataScript/)__  - 跨系统脚本语言，用于处理不同大小和功能的计算机系统中的大数据管道.
* __[Bpipe](http://docs.bpipe.org)__  - 一种用于定义管道阶段并将它们链接在一起以形成管道的小语言.
* __[Common Workflow Language](http://www.commonwl.org/)__  - 用于描述分析工作流程和工具的规范，这些工作流程和工具可在各种软件和硬件环境（从工作站到集群，云和高性能计算（HPC）环境）中移植和扩展.
* __[Cromwell](https://github.com/broadinstitute/cromwell)__  - 面向科学工作流程的工作流管理系统.
* __[Galaxy](https://usegalaxy.org/)_ _  - 一个流行的开源，基于Web的数据密集型生物医学研究平台.  具有多种功能，从数据分析到工作流管理再到可视化工具.
* __[GATK Queue](https://gatkforums.broadinstitute.org/gatk/discussion/1288/howto-run-queue-for-the-first-time)__  - 与GATK本身一起工作的流水线系统以及其他高通量序列分析软件.
* __[Nextflow](https://www.nextflow.io)__  - 以UNIX管道概念为模型的流畅DSL，简化了以可移植方式编写并行和可扩展管道的过程.
* __[R-Peridot](http://www.bioinformatics-brazil.org/r-peridot/)__  - 使用直观的GUI进行差异表达式分析的可定制管道.
* __[Ruffus](http://www.ruffus.org.uk)__  - 用于科学和生物信息学的python的计算管道库.
* __[SeqWare](https://seqware.github.io/)__  - 基于Hadoop Oozie的工作流系统专注于云环境中的基因组数据分析.
* __[Snakemake](https://bitbucket.org/snakemake/snakemake/wiki/Home)__  -  Python中的工作流管理系统，旨在通过提供快速，舒适的执行环境来降低创建工作流的复杂性.
* __[Workflow Descriptor Language](https://github.com/broadinstitute/wdl)__  -  Broad开发的工作流程标准.

### Sequence Processing

序列处理包括诸如解复用原始读取数据和修剪低质量基础之类的任务.

* __[AfterQC](https://github.com/OpenGene/AfterQC)__  -  fastq数据的自动过滤，修剪，错误删除和质量控制
* __[FastQC](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/)__  - 用于高通量序列数据的质量控制工具.
* __[Fastqp](https://github.com/mdshw5/fastqp)__  - 使用Python进行FASTQ和SAM质量控制.
* __[Fastx Tookit](http://hannonlab.cshl.edu/fastx_toolkit/)__  -  FASTQ / A短读取预处理工具：解复用，修剪，剪切，质量过滤和屏蔽实用程序.
* __[MultiQC](http://multiqc.info/)__  - 将来自许多样本的生物信息学分析的结果汇总到单个报告中.
* __[SeqKit](https://github.com/shenwei356/seqkit)__  -  Golang中用于FASTA / Q文件操作的跨平台和超快工具包.
* __[seqmagick](http://seqmagick.readthedocs.io/en/latest/)__  - 以方便的方式在Biopython中进行文件格式转换
* __[Seqtk](https://github.com/lh3/seqtk)__  - 用于处理FASTA / Q格式序列的工具包.
* __[smof](https://github.com/incertae-sedis/smof)__  -  UNIX风格的FASTA操作工具.

### Sequence Alignment

__De新对齐___

__DNA重新测序___

* __[Bowtie 2](https://github.com/BenLangmead/bowtie2)__  - 用于将测序读数与长参考序列比对的超快且记忆效率高的工具.
* __[BWA](https://github.com/lh3/bwa)__  -  Burrow-Wheeler Aligner用于DNA序列之间的成对比对.

### Variant Calling

* __[freebayes](https://github.com/ekg/freebayes)__  - 基于贝叶斯单倍型的多态性发现和基因分型.
* __[GATK](https://software.broadinstitute.org/gatk/)__  - 高吞吐量测序数据中的变体发现.
* __[samtools/bcftools/htslib](https://github.com/samtools/samtools)__  - 一套用于处理下一代测序数据的工具.

### BAM File Utilities

* __[Bamtools](https://github.com/pezmaster31/bamtools)__  - 用于处理BAM文件的工具集合.
* __[bam toolbox](https://github.com/AndersenLab/bam-toolbox)_ _MtDNA：核覆盖;  BAM工具箱可以输出MtDNA：核覆盖率，代表线粒体含量.
* __[mergesam](https://github.com/DarwinAwardWinner/mergesam)__  - 自动执行常见的SAM和BAM转换.
* __[SAMstat](https://github.com/TimoLassmann/samstat)__  - 显示下一代测序的序列统计数据.
* __[Telseq](https://github.com/zd1/telseq)__  -  Telseq是一种从全基因组序列数据中估计端粒长度的工具.

### VCF File Utilities

* __[bcftools](https://github.com/samtools/bcftools)__  - 用于操作VCF文件的工具集.
* __[vcfanno](https://github.com/brentp/vcfanno)__  - 使用其他VCF / BED / tabixed文件注释VCF.
* __[vcflib](https://github.com/vcflib/vcflib)__  - 用于解析和操作VCF文件的C ++库.
* __[vcftools](https://github.com/vcftools/vcftools)__  -  VCF操作和统计（例如连锁不平衡，等位基因频率，Fst）.

### GFF BED File Utilities

* __[gffutils](https://github.com/daler/gffutils)__  -  GFF和GTF文件操作和互换.
* __[BEDOPS](https://bedops.readthedocs.io/en/latest/index.html)__  - 快速，高度可扩展且易于并行化的基因组分析工具包.
* __[Bedtools2](https://github.com/arq5x/bedtools2)__  - 用于基因组算术的瑞士军刀.

### Variant Simulation

* __[Bam Surgeon](https://github.com/adamewing/bamsurgeon)__  - 用于向现有`.bam`文件添加突变的工具，用于测试突变调用者.
* __[wgsim](https://github.com/lh3/wgsim)__  -  __Comes with samtools！__  - 读取模拟器.

### Variant Filtering / Quality Control

### Variant Prediction/Annotation

* __[SIFT](http://sift.jcvi.org/)__  - 预测氨基酸取代是否影响蛋白质功能.
* __[SnpEff](https://github.com/pcingola/SnpEff)__  - 遗传变异注释和效果预测工具箱.

### Python Modules

#### Data

* __[cruzdb](https://github.com/brentp/cruzdb)__  -  Pythonic访问UCSC基因组数据库.
* __[pyensembl](https://github.com/openvax/pyensembl)__  -  Pythonic访问Ensembl数据库.
* __[bioservices](https://github.com/cokelaer/bioservices)__  - 从Python访问Biological Web Services.

#### Tools

* __[cyvcf](https://github.com/arq5x/cyvcf)__  - 港口 [pyVCF](https://github.com/jamescasbon/PyVCF) 使用Cython获得速度.
* __[cyvcf2](https://github.com/brentp/cyvcf2)_ _  -  Cython + HTSlib ==快速VCF解析;  解析比pyVCF更快.
* __[pyBedTools](https://github.com/daler/pybedtools)__  -  Python包装器 [bedtools](https://github.com/arq5x/bedtools).
* __[pyfaidx](https://github.com/mdshw5/pyfaidx)__  -  Pythonic访问FASTA文件.
* __[pysam](https://github.com/pysam-developers/pysam)__  -  Python包装器 [samtools](https://github.com/samtools/samtools).
* __[pyVCF](https://github.com/jamescasbon/PyVCF)__  - 用于Python的VCF解析器.

## Visualization

### Genome Browsers / Gene Diagrams

以下工具可用于可视化基因组数据或构建基因组数据的定制可视化，包括来自DNA-Seq，RNA-Seq和ChIP-Seq，变体等的序列数据.

* __[Squiggle](https://github.com/Lab41/squiggle)__  - 易于使用的DNA序列可视化工具，可将FASTA文件转换为基于浏览器的可视化.
* __[biodalliance](http://www.biodalliance.org/)_ _  - 嵌入式基因组查看器.  集成来自各种来源的数据，可直接从流行的基因组学文件格式（包括bigWig，BAM和VCF）加载数据.
* __[BioJS](http://biojs.net/)__  -  BioJS是一个包含数百个JavaScript组件的库，使您能够使用当前的Web技术可视化和处理数据.
* __[Circleator](https://github.com/jonathancrabtree/Circleator)__  - 使用BioPerl和SVG对基因组相关数据进行灵活的圆形可视化.
* __[DNAism](https://github.com/drio/dnaism)__  - 用于DNA数据的基于D3的基于D3的JavaScript库的Horizo​​n chart.
* __[IGV js](https://www.broadinstitute.org/igv)_ _  - 基于Java的浏览器.  用于基因组数据和注释的快速，高效，可扩展的可视化工具.  处理大 [variety of formats](http://software.broadinstitute.org/software/igv/fileformats).
* __[Island Plot](https://github.com/lairdm/islandplot)_ _  -  D3基于JavaScript的基因组查看器.  构造SVG.
* __[JBrowse](https://jbrowse.org)__ - JavaScript genome browser that is highly customizable via plugins and track customizations
* __[PHAT](https://github.com/chgibb/PHAT)__  - 指向并单击，跨平台套件，用于分析和可视化下一代测序数据集.
* __[pileup.js](https://github.com/hammerlab/pileup.js)__  - 可用于生成交互式和高度可定制的基于Web的基因组浏览器的JavaScript库.
* __[scribl](https://github.com/chmille4/Scribl)_ _  - 用于绘制基于画布的基因图的JavaScript库.  该 [Homepage](http://chmille4.github.io/Scribl/) 有例子.

### Circos Related

* __[Circos](http://circos.ca/)__  - 用于圆形图的Perl包，非常适合基因组重排.
* __[ClicO FS](https://academic.oup.com/bioinformatics/article/31/22/3685/241292)__  -  Circos的基于Web的交互式服务.
* __[OmicCircos](http://www.bioconductor.org/packages/release/bioc/html/OmicCircos.html)__  - 用于组学数据的圆形图的R包.
* __[J-Circos](http://www.australianprostatecentre.org/research/software/jcircos)__  - 用于与circos图进行交互式工作的Java应用程序.
* __[rCircos](https://cran.r-project.org/web/packages/RCircos/index.html)__  - 圆形地块的R包.

## Database Access

* [Entrez Direct: E-utilities on the UNIX command line](http://www.ncbi.nlm.nih.gov/books/NBK179288/)   -  UNIX命令行工具，以编程方式访问NCBI的数据库.  链接中提供了安装说明和示例.

## Resources

### Becoming a Bioinformatician

* [What is a bioinformatician](http://blog.fejes.ca/?p=2418)
* [Bioinformatics Curriculum Guidelines: Toward a Definition of Core Competencies](http://www.ploscompbiol.org/article/info:doi%2F10.1371%2Fjournal.pcbi.1003496)
* [Top N Reasons To Do A Ph.D. or Post-Doc in Bioinformatics/Computational Biology](http://caseybergman.wordpress.com/2012/07/31/top-n-reasons-to-do-a-ph-d-or-post-doc-in-bioinformaticscomputational-biology/)
* [A 10-Step Guide to Party Conversation For Bioinformaticians](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-1-104) - 这是一个循序渐进的指南，介绍如何向不参与该领域的人传达概念，当被问到这样的问题时：“那么，你做了什么？”
* [A History Of Bioinformatics (In The Year 2039)](https://www.youtube.com/watch?v=uwsjwMO-TEA) -  C. Titus Brown谈到他从2039年开始回顾生物信息学的一次演讲.他的笔记可以在这里找到 [here](http://ivory.idyll.org/blog/2014-bosc-keynote.html).
* [A farewell to bioinformatics](http://madhadron.com/posts/2012-03-26-a-farewell-to-bioinformatics.html) - 对生物信息学状态的批判性观点.
* [A Series of Interviews with Notable Bioinformaticians](http://www.acgt.me/blog/2014/3/25/101-questions-a-new-series-of-interviews-with-notable-bioinformaticians) -  Keith Bradnam博士“认为向一群着名的生物信息学家提出一系列简单的问题以评估他们对生物信息学研究现状的看法可能是有益的，并且可能会得到关于对他们有用的东西的任何提示.生物信息学的职业生涯.“
* [Open Source Society University on Bioinformatics](https://github.com/ossu/bioinformatics) - 希望通过世界上最好的大学免费完成自己时间的生物信息学课程的人们的坚实途径.
* [Rosalind](http://rosalind.info/) - 罗莎琳德是一个通过解决问题来学习生物信息学的平台.
* [A guide for the lonely bioinformatician](http://www.opiniomics.org/a-guide-for-the-lonely-bioinformatician/) - 本指南面向生物信息学家，旨在指导他们实现更好的职业发展.
* [A brief history of bioinformatics](https://doi.org/10.1093/bib/bby063)

### Sequencing

* [Next-Generation Sequencing Technologies - Elaine Mardis (2014)](https://youtu.be/6Is3W7JkFp8) [1:34:35]  - 对下一代和第三代测序技术的优秀（技术）概述，以及癌症研究中的一些应用.
* [Annotated bibliography of \*Seq assays](https://liorpachter.wordpress.com/seq/) - 从转录到转座因子发现的各种测序技术和测定的~100篇论文一览表.
* [For all you seq... (PDF)](http://www.illumina.com/content/dam/illumina-marketing/documents/applications/ngs-library-prep/ForAllYouSeqMethods.pdf)  （3456x5471） -  Illumina的大量信息图表说明了有多少测序技术有效.  技术包括蛋白质 - 蛋白质相互作用，RNA转录，RNA-蛋白质相互作用，RNA低水平检测，RNA修饰，RNA结构，DNA重排和标记，DNA低水平检测，表观遗传学和DNA-蛋白质相互作用.  参考文献包括.

### RNA-Seq

* [Review papers on RNA-seq (Biostars)](https://www.biostars.org/p/52152/) - 包括大量关于RNA-seq和分析方法的开创性论文.
* [Informatics for RNA-seq: A web resource for analysis on the cloud](https://github.com/griffithlab/rnaseq_tutorial)   - 使用Amazon AWS云服务在云中执行RNA-seq分析的教育资源.  主题包括准备数据，预处理，差异表达，同种型发现，数据可视化和解释.
* [RNA-seqlopedia](http://rnaseq.uoregon.edu/) -  RNA-seqlopedia提供了RNA-seq的精彩概述以及进行成功的RNA-seq实验所需的选择.
* [A survey of best practices for RNA-seq data analysis](http://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8) - 为RNA-seq计算分析提供了令人敬畏的路线图，包括挑战/障碍和需要注意的事项，以及如何将RNA-seq数据与其他数据类型集成.
* [Stories from the Supplement](https://www.youtube.com/watch?v=5NiFibnbE8o) [46:39]  -  Lior Pachter博士分享他的故事来自着名的RNA-seq分析软件CuffDiff和 [Cufflinks](http://cole-trapnell-lab.github.io/cufflinks/) 并解释了他们的一些方法.
* [List of RNA-seq Bioinformatics Tools](https://en.wikipedia.org/wiki/List_of_RNA-Seq_bioinformatics_tools) - 维基百科上有关分析所需的RNA-seq生物信息学工具的广泛列表，包括质量控制，校准，剪接分析和可视化的分析管道的所有部分.
* [RNA-seq Analysis](https://github.com/crazyhottommy/RNA-seq-analysis) - [@crazyhottommy](https://github.com/crazyhottommy)关于进行RNA-seq分析时的各种步骤和注意事项的说明.

### ChIP-Seq

* [ChIP-seq analysis notes from Tommy Tang](https://github.com/crazyhottommy/ChIP-seq-analysis) - 关于ChIP-seq数据的资源，包括论文，方法，软件链接和分析.

### YouTube Channels and Playlists

* [Current Topics in Genome Analysis 2016](https://www.genome.gov/12514288/current-topics-in-genome-analysis-2016-course-syllabus-handouts-and-videos/) -  NIH提供的14个关于基因组学当前主题的优秀系列讲座，包括序列分析，测序技术，以及基因组医学等更多翻译主题.
* [GenomeTV](https://www.youtube.com/user/GenomeTV) - “GenomeTV是NHGRI的官方视频资源集，包括讲座，新闻纪录片，以及针对基因组研究的研究，问题和临床应用的会议的完整视频集.”
* [Leading Strand](https://www.youtube.com/user/LeadingStrand)   - 冷泉港实验室（CSHL）会议的主题演讲.  更多关于 [The Leading Strand](http://theleadingstrand.cshl.edu/).
* [Genomics, Big Data and Medicine Seminar Series](https://www.youtube.com/playlist?list=PLqLDR0CTP9_pboZCk6gR9Zn4kW7h9XWJI) - “我们的研讨会致力于GBM的关键交叉，深入研究&#39;前沿&#39;技术和将深刻塑造未来的方法.”
* [Rafael Irizarry's Channel](https://www.youtube.com/user/RafalabChannel/videos) -  Rafael Irizarry博士关于基因组学统计学的讲座和学术会谈.
* [NIH VideoCasting and Podcasting](https://www.youtube.com/user/nihvcast)   - “NIH VideoCast通过互联网向世界各地的观众播放研讨会，会议和会议，作为实时流媒体视频.”  不仅仅是基因组学和生物信息学视频，而是关于生物信息学和基因组学领域特定用途的许多重要讨论.

### Blogs

* [ACGT](http://www.acgt.me/) -  Keith Bradnam博士撰写了关于生物学，基因组学和人类对生物信息学的伪造使用对人类的持续威胁的想法.
* [Opiniomics](http://www.opiniomics.org/) -  Mick Watson博士撰写了关于生物信息学，基因组和生物学的文章.
* [Bits of DNA](https://liorpachter.wordpress.com/) -  Lior Pachter博士撰写关于计算生物学的评论和评论.
* [it is NOT junk](http://www.michaeleisen.org/blog/) -  Michael Eisen博士写的“关于基因组，DNA，进化，开放科学，棒球和其他重要事物的博客”

### Miscellaneous

* [The Leek group guide to genomics papers](https://github.com/jtleek/genomicspapers/) - 专业策划的基因组学论文，以加快基因组学，RNA-seq，统计学（用于基因组学），软件开发等方面的速度.
* [A New Online Computational Biology Curriculum](https://doi.org/10.1371/journal.pcbi.1003662) - “本文介绍了数百个免费视频课程的目录，这些课程对于那些希望扩展生物信息学和计算生物学知识的人来说具有潜在的兴趣.这些课程分为11个主题领域，模仿大学系，并附有评论和职业建议. “
* [How Perl Saved the Human Genome Project](http://www.foo.be/docs/tpj/issues/vol1_2/tpj0102-0001.html) -  Lincoln D. Stein关于Perl编程语言在人类基因组计划中的重要性的轶事.
* [Educational Papers from Nature Biotechnology and PLoS Computational Biology](https://liacs.leidenuniv.nl/~hoogeboomhj/mcb/nature_primer.html) - 关于计算生物学和生物信息学中使用的各种方法的引物和简短教育文章的链接页.
* [The PeerJ Bioinformatics Software Tools Collection](https://peerj.com/collections/45-bioinformatics-software/) - 收集由Keith Crandall和Claus White策划的工具，旨在整理PeerJ中最有趣，最具创新性和相关性的生物信息学工具文章.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
