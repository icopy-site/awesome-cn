<div class="github-widget" data-repo="danielecook/Awesome-Bioinformatics"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
很棒的生物信息学 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/danielecook/Awesome-Bioinformatics.svg?branch=master)](https://travis-ci.org/danielecook/Awesome-Bioinformatics)
======================

 &gt;生物信息学是一个跨学科领域，致力于开发用于理解生物学数据的方法和软件工具.  — [Wikipedia](https://en.wikipedia.org/wiki/Bioinformatics)

 精选的生物信息学软件，资源和库的精选列表.  主要基于命令行，免费或开源.  请随意 [contribute](https://github.com/danielecook/Awesome-Bioinformatics/blob/master/CONTRIBUTING.md)!


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

----

## Package suites

 软件包套件收集用于特定语言或平台的软件包和安装工具.  我们有一些生物信息学软件.

### Bioconductor

* __[Bioconductor](https://www.bioconductor.org/)_-大量用于分析和理解高通量基因组数据的工具，包括1500多个软件包.

### Biopython

* __[Biopython](https://biopython.org/)_ _-可免费使用Python进行生物计算的工具，包括手册，包装和详尽的文档.  的一部分 [Open Bioinformatics Foundation](http://open-bio.org/) .  包含非常有用 [Entrez](https://biopython.org/DIST/docs/api/Bio.Entrez-module.html) 用于访问NCBI数据库的API的程序包.

### Bioconda

* __[Bioconda](https://bioconda.github.io/)__-的频道 [conda package manager](http://conda.pydata.org/docs/intro.html)  专业从事生物信息学软件.  包括一个存储库，该存储库包含3000多个随时可安装（带有`conda install`）生物信息学软件包.

## Data Tools

* __[GGD](https://github.com/gogetdata/ggd-cli)_ _-获取数据；  用于获取基因组数据的命令行界面
* __[SRA-Explorer](https://sra-explorer.info/)__-轻松获得SRA下载链接和其他信息.

## Data Processing

### Command Line Utilities

* __[Bioinformatics One Liners](https://github.com/stephenturner/oneliners)__-有用的单行命令的Git存储库.
* __[BioNode](https://www.bionode.io/)__-模块化和通用的生物信息学，Bionode为生物信息学分析工作流提供了可移植的UNIX命令行工具和JavaScript API.
* __[bioSyntax](http://www.bioSyntax.org/)__-vim / less / gedit / sublime中的计算生物学文件格式（SAM，VCF，GTF，FASTA，PDB等）的语法突出显示.
* __[CSVKit](https://github.com/wireservice/csvkit)__-处理CSV /制表符分隔文件的实用程序.
* __[csvtk](https://github.com/shenwei356/csvtk)__-另一个跨平台，高效，实用且美观的CSV / TSV工具包.
* __[datamash](http://www.gnu.org/software/datamash/)__-数据转换和统计.
* __[easy_qsub](https://github.com/shenwei356/easy_qsub)_ _-使用脚本模板轻松提交PBS作业.  支持多个输入文件.
* __[GNU `parallel`](http://www.gnu.org/software/parallel/)__-通用并行器，可在一台多核计算机上并行运行作业. [Here](https://www.biostars.org/p/63816/) 一些使用GNU`parallel`的示例脚本.
* __[grabix](https://github.com/arq5x/grabix)__-随机访问BGZF文件的工具.
* __[gsort](https://github.com/brentp/gsort)__-根据指定顺序对基因组文件进行排序.
* __[tabix](https://github.com/samtools/tabix)__-表文件索引.
* __[wormtable](https://github.com/wormtable/wormtable)__-大型数据集的一次写入多次读取表.
* __[zindex](https://github.com/mattgodbolt/zindex)__-在压缩的文本文件上创建索引.

## Next Generation Sequencing

### Workflow Managers

* __[BigDataScript](https://pcingola.github.io/BigDataScript/)__-一种跨系统脚本语言，用于处理具有不同大小和功能的计算机系统中的大数据管道.
* __[Bpipe](http://docs.bpipe.org)__-一种用于定义管道阶段并将它们链接在一起以构成管道的小语言.
* __[Common Workflow Language](http://www.commonwl.org/)__-用于描述分析工作流和工具的规范，该分析工作流和工具在从工作站到集群，云和高性能计算（HPC）环境的各种软件和硬件环境中均具有可移植性和可伸缩性.
* __[Cromwell](https://github.com/broadinstitute/cromwell)__-面向科学工作流程的工作流程管理系统.
* __[Galaxy](https://usegalaxy.org/)_ _-流行的基于Web的开源平台，用于数据密集型生物医学研究.  从数据分析到工作流管理再到可视化工具，具有多种功能.
* __[GATK Queue](https://gatkforums.broadinstitute.org/gatk/discussion/1288/howto-run-queue-for-the-first-time)_-流水线系统，可与GATK以及其他高通量序列分析软件一起使用.
* __[Nextflow](https://www.nextflow.io) (recommended)__ - A fluent DSL modelled around the UNIX pipe concept, that simplifies writing parallel and scalable pipelines in a portable manner.
* __[Ruffus](http://www.ruffus.org.uk)__-广泛用于科学和生物信息学的python计算管道库.
* __[SeqWare](https://seqware.github.io/)__-基于Hadoop Oozie的工作流系统，专注于云环境中的基因组数据分析.
* __[Snakemake](https://bitbucket.org/snakemake/snakemake/wiki/Home)__-Python中的工作流管理系统，旨在通过提供快速，舒适的执行环境来降低创建工作流的复杂性.
* __[Workflow Descriptor Language](https://github.com/broadinstitute/wdl)__-由Broad开发的工作流程标准.

### Pipelines

* __[Awesome-Pipeline](https://github.com/pditommaso/awesome-pipeline)__-管道资源列表.
* __[bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen)_-电池包括用于变异和RNA-Seq分析的基因组分析管道，结构变异调用，注释和预测.
* __[R-Peridot](http://www.bioinformatics-brazil.org/r-peridot/)__-可通过直观的GUI进行差异表达分析的可定制管道.

### Sequence Processing

序列处理包括诸如对原始读取数据进行多路分解和修剪低质量碱基之类的任务.

* __[AfterQC](https://github.com/OpenGene/AfterQC)__-fastq数据的自动过滤，修剪，错误消除和质量控制
* __[FastQC](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/)__-用于高通量序列数据的质量控制工具.
* __[Fastqp](https://github.com/mdshw5/fastqp)__-使用Python进行FASTQ和SAM质量控制.
* __[Fastx Tookit](http://hannonlab.cshl.edu/fastx_toolkit/)__-FASTQ / A简要介绍了预处理工具：多路分解，修剪，剪切，质量过滤和掩蔽实用程序.
* __[MultiQC](http://multiqc.info/)__-将许多样品的生物信息学分析结果汇总到一个报告中.
* __[SeqKit](https://github.com/shenwei356/seqkit)__-Golang中用于FASTA / Q文件操作的跨平台和超快速工具包.
* __[seqmagick](http://seqmagick.readthedocs.io/en/latest/)__-以方便的方式在Biopython中进行文件格式转换
* __[Seqtk](https://github.com/lh3/seqtk)__-用于处理FASTA / Q格式的序列的工具包.
* __[smof](https://github.com/incertae-sedis/smof)__-UNIX风格的FASTA操作工具.

### Data Analysis

通过引入专门的数据库，以下各项可进行可扩展的基因组分析.

* __[Hail](https://github.com/hail-is/hail)__-可扩展的基因组分析
* __[GLNexus](https://github.com/dnanexus-rnd/GLnexus)_-可扩展的gVCF合并和联合变量调用，以进行总体测序项目.

### Sequence Alignment

__De New Alignment__

__DNA重测序__

* __[Bowtie 2](https://github.com/BenLangmead/bowtie2)__-一种超快速且高效存储的工具，用于将测序读数与长参考序列进行比对.
* __[BWA](https://github.com/lh3/bwa)_-Burrow-Wheeler Aligner用于DNA序列之间的成对比对.

### Variant Calling

* __[freebayes](https://github.com/ekg/freebayes)__-基于贝叶斯单元型的多态性发现和基因分型.
* __[GATK](https://software.broadinstitute.org/gatk/)__-高通量测序数据中的变异发现
* __[samtools/bcftools/htslib](https://github.com/samtools/samtools)__-一套用于处理下一代测序数据的工具.

__结构变量调用者__

* __[Delly](https://github.com/dellytools/delly)__-通过集成的配对末端和拆分阅读分析发现结构变异.
* __[lumpy](https://github.com/arq5x/lumpy-sv)_块状：用于结构变体发现的一般概率框架.
* __[manta](https://github.com/Illumina/manta)__-用于映射测序数据的结构变体和indel调用者.
* __[gridss](https://github.com/PapenfussLab/gridss)__-GRIDSS：基因组重排识别软件套件.
* __[smoove](https://github.com/brentp/smoove)__-使用现有工具进行结构变异调用和基因分型，但是很顺利.

### BAM File Utilities

* __[Bamtools](https://github.com/pezmaster31/bamtools)__-处理BAM文件的工具集合.
* __[mergesam](https://github.com/DarwinAwardWinner/mergesam)__-自动执行常见的SAM和BAM转换.
* __[mosdepth](https://github.com/brentp/mosdepth)__-WGS，外显子组或靶向测序的快速BAM / CRAM深度计算
* __[SAMstat](https://github.com/TimoLassmann/samstat)__-显示下一代测序的序列统计信息.
* __[Somalier](https://github.com/brentp/mosdepth)__-对BAM / CRAM / VCF / GVCF进行快速的样本交换和相关性检查.
* __[Telseq](https://github.com/zd1/telseq)_-Telseq是用于从整个基因组序列数据估算端粒长度的工具.

### VCF File Utilities

* __[bcftools](https://github.com/samtools/bcftools)__-用于处理VCF文件的工具集.
* __[vcfanno](https://github.com/brentp/vcfanno)__-用其他VCF / BED / tabixed文件注释VCF.
* __[vcflib](https://github.com/vcflib/vcflib)__-用于解析和处理VCF文件的C ++库.
* __[vcftools](https://github.com/vcftools/vcftools)_-VCF操作和统计（例如，连锁不平衡，等位基因频率，Fst）.

### GFF BED File Utilities

* __[gffutils](https://github.com/daler/gffutils)__-GFF和GTF文件的操作和相互转换.
* __[BEDOPS](https://bedops.readthedocs.io/en/latest/index.html)__-快速，高度可扩展且易于并行化的基因组分析工具包.
* __[Bedtools2](https://github.com/arq5x/bedtools2)__-用于基因组算术的瑞士军刀.

### Variant Simulation

* __[Bam Surgeon](https://github.com/adamewing/bamsurgeon)__-用于将突变添加到现有`.bam`文件中的工具，用于测试突变调用者.
* __[wgsim](https://github.com/lh3/wgsim)__-__samtools附带！__-读取模拟器.

### Variant Prediction/Annotation

* __[SIFT](http://sift.jcvi.org/)__ - Predicts whether an amino acid substitution affects protein function.
* __[SnpEff](https://github.com/pcingola/SnpEff)__-遗传变异注释和效果预测工具箱.

### Python Modules

#### Data

* __[cruzdb](https://github.com/brentp/cruzdb)__-对UCSC Genome数据库的Pythonic访问.
* __[pyensembl](https://github.com/openvax/pyensembl)__-使用Pythonic访问Ensembl数据库.
* __[bioservices](https://github.com/cokelaer/bioservices)__-从Python访问生物Web服务.

#### Tools

* __[cyvcf](https://github.com/arq5x/cyvcf)__-的端口 [pyVCF](https://github.com/jamescasbon/PyVCF) 使用Cython加快速度.
* __[cyvcf2](https://github.com/brentp/cyvcf2)_ _-Cython + HTSlib ==快速VCF解析；  比pyVCF解析速度更快.
* __[pyBedTools](https://github.com/daler/pybedtools)__-Python包装器 [bedtools](https://github.com/arq5x/bedtools).
* __[pyfaidx](https://github.com/mdshw5/pyfaidx)__-通过Python方式访问FASTA文件.
* __[pysam](https://github.com/pysam-developers/pysam)__-Python包装器 [samtools](https://github.com/samtools/samtools).
* __[pyVCF](https://github.com/jamescasbon/PyVCF)__-适用于Python的VCF解析器.

## Visualization

### Genome Browsers / Gene Diagrams

以下工具可用于可视化基因组数据或构建基因组数据的自定义可视化，包括来自DNA-Seq，RNA-Seq和ChIP-Seq，变体等的序列数据.

* __[Squiggle](https://github.com/Lab41/squiggle)__-易于使用的DNA序列可视化工具，可将FASTA文件转换为基于浏览器的可视化.
* __[biodalliance](http://www.biodalliance.org/)_ _-可嵌入的基因组查看器.  来自各种来源的集成数据，并且可以直接从流行的基因组文件格式（包括bigWig，BAM和VCF）加载数据.
* __[BioJS](http://biojs.net/)__-BioJS是一个包含数百个JavaScript组件的库，使您可以使用当前的Web技术可视化和处理数据.
* __[Circleator](https://github.com/jonathancrabtree/Circleator)_-利用BioPerl和SVG对基因组相关数据进行灵活的循环可视化.
* __[DNAism](https://github.com/drio/dnaism)__-基于D3地平线图表的JavaScript库，用于DNA数据.
* __[IGV js](https://www.broadinstitute.org/igv)_ _-基于Java的浏览器.  快速，高效，可扩展的可视化工具，用于基因组数据和注释.  处理大 [variety of formats](http://software.broadinstitute.org/software/igv/fileformats).
* __[Island Plot](https://github.com/lairdm/islandplot)_ _-基于D3 JavaScript的基因组查看器.  构造SVG.
* __[JBrowse](https://jbrowse.org)__-JavaScript基因组浏览器，可通过插件进行高度自定义并跟踪自定义
* __[PHAT](https://github.com/chgibb/PHAT)__-跨平台套件的点击式，用于分析和可视化下一代测序数据集.
* __[pileup.js](https://github.com/hammerlab/pileup.js)__-JavaScript库，可用于生成交互式且高度可定制的基于Web的基因组浏览器.
* __[scribl](https://github.com/chmille4/Scribl)_ _-JavaScript库，用于绘制基于画布的基因图.   [Homepage](http://chmille4.github.io/Scribl/) 有例子.
* __[Lucid Align](https://lucidalign.com/)__-现代的序列比对查看器

### Circos Related

* __[Circos](http://circos.ca/)__-Perl软件包，用于圆形图，非常适合基因组重排.
* __[ClicO FS](https://academic.oup.com/bioinformatics/article/31/22/3685/241292)__-Circos的基于Web的交互式服务.
* __[OmicCircos](http://www.bioconductor.org/packages/release/bioc/html/OmicCircos.html)__-R软件包，用于组学数据的圆形图.
* __[J-Circos](http://www.australianprostatecentre.org/research/software/jcircos)__-一个用于与马戏团图进行交互工作的Java应用程序.
* __[rCircos](https://cran.r-project.org/web/packages/RCircos/index.html)__-R包用于圆形图.

## Database Access

* [Entrez Direct: E-utilities on the UNIX command line](http://www.ncbi.nlm.nih.gov/books/NBK179288/)  -UNIX命令行工具，以编程方式访问NCBI的数据库.  链接中提供了安装说明和示例.

## Resources

### Becoming a Bioinformatician

* [What is a bioinformatician](http://blog.fejes.ca/?p=2418)
* [Bioinformatics Curriculum Guidelines: Toward a Definition of Core Competencies](http://www.ploscompbiol.org/article/info:doi%2F10.1371%2Fjournal.pcbi.1003496)
* [Top N Reasons To Do A Ph.D. or Post-Doc in Bioinformatics/Computational Biology](http://caseybergman.wordpress.com/2012/07/31/top-n-reasons-to-do-a-ph-d-or-post-doc-in-bioinformaticscomputational-biology/)
* [A 10-Step Guide to Party Conversation For Bioinformaticians](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-1-104) -这是有关如何向未参与该领域的人员传达概念的分步指南，当您提出以下问题时：“那么，您会怎么做？”
* [A History Of Bioinformatics (In The Year 2039)](https://www.youtube.com/watch?v=uwsjwMO-TEA) -泰特斯·布朗（C. Titus Brown）关于他回顾2039年以来的生物信息学的演讲. [here](http://ivory.idyll.org/blog/2014-bosc-keynote.html).
* [A farewell to bioinformatics](http://madhadron.com/posts/2012-03-26-a-farewell-to-bioinformatics.html) -对生物信息学状态的批判性看法.
* [A Series of Interviews with Notable Bioinformaticians](http://www.acgt.me/blog/2014/3/25/101-questions-a-new-series-of-interviews-with-notable-bioinformaticians) -Keith Bradnam博士“认为向一群著名的生物信息学家提出一系列简单的问题，以评估他们对当前生物信息学研究现状的看法可能具有启发性，也许可以获取他们对自己的研究有用的任何提示生物信息学事业.”
* [Open Source Society University on Bioinformatics](https://github.com/ossu/bioinformatics) -对于那些想要免费完成世界上最好的大学的信息的人来说，这是一条坚实的道路.
* [Rosalind](http://rosalind.info/) -Rosalind是一个通过解决问题来学习生物信息学的平台.
* [A guide for the lonely bioinformatician](http://www.opiniomics.org/a-guide-for-the-lonely-bioinformatician/) - This guide is aimed at bioinformaticians, and is meant to guide them towards better career development.
* [A brief history of bioinformatics](https://doi.org/10.1093/bib/bby063)

### Bioinformatics on GitHub

* [Awesome-alternative-splicing](https://github.com/HussainAther/awesome-alternative-splicing) -有关替代拼接的资源列表，包括软件，数据库和其他工具.

### Sequencing

* [Next-Generation Sequencing Technologies - Elaine Mardis (2014)](https://youtu.be/6Is3W7JkFp8) [1:34:35]-下一代和第三代测序技术的出色（技术）概述，以及在癌症研究中的一些应用.
* [Annotated bibliography of \*Seq assays](https://liorpachter.wordpress.com/seq/) -约100篇论文，涉及从转录到转座因子发现的各种测序技术和测定.

### RNA-Seq

* [Review papers on RNA-seq (Biostars)](https://www.biostars.org/p/52152/) -包括许多有关RNA序列和分析方法的开创性论文.
* [Informatics for RNA-seq: A web resource for analysis on the cloud](https://github.com/griffithlab/rnaseq_tutorial)  -有关使用Amazon AWS云服务在云中执行RNA序列分析的教育资源.  主题包括准备数据，预处理，差异表达，异构体发现，数据可视化和解释.
* [RNA-seqlopedia](http://rnaseq.uoregon.edu/) -RNA-seqlopedia提供了一个很棒的RNA-seq概述，以及进行成功的RNA-seq实验所需的选择.
* [A survey of best practices for RNA-seq data analysis](http://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8) -为RNA序列计算分析提供了绝佳的路线图，包括挑战/障碍和需要注意的事项，以及如何将RNA序列数据与其他数据类型集成在一起.
* [Stories from the Supplement](https://www.youtube.com/watch?v=5NiFibnbE8o) [46:39]-Lior Pachter博士分享了著名RNA-seq分析软件CuffDiff和 [Cufflinks](http://cole-trapnell-lab.github.io/cufflinks/) 并解释了他们的一些方法.
* [List of RNA-seq Bioinformatics Tools](https://en.wikipedia.org/wiki/List_of_RNA-Seq_bioinformatics_tools) -分析所需的RNA-seq生物信息学工具在Wikipedia上的详尽列表，涵盖质量，控制，比对，剪接分析和可视化等分析流程的所有部分.
* [RNA-seq Analysis](https://github.com/crazyhottommy/RNA-seq-analysis) - [@crazyhottommy](https://github.com/crazyhottommy)进行RNA序列分析时有关各种步骤和注意事项的说明.

### ChIP-Seq

* [ChIP-seq analysis notes from Tommy Tang](https://github.com/crazyhottommy/ChIP-seq-analysis) -关于ChIP-seq数据的资源，包括论文，方法，软件链接和分析.

### YouTube Channels and Playlists

* [Current Topics in Genome Analysis 2016](https://www.genome.gov/12514288/current-topics-in-genome-analysis-2016-course-syllabus-handouts-and-videos/) -在NIH举行的十四次精彩系列讲座，内容涉及基因组学的当前主题，从序列分析到测序技术，甚至还有更多翻译主题，例如基因组医学.
* [GenomeTV](https://www.youtube.com/user/GenomeTV) -“ GenomeTV是NHGRI官方视频资源的集合，包括演讲，新闻纪录片，会议的完整视频集，这些视频集处理基因组研究的研究，问题和临床应用.”
* [Leading Strand](https://www.youtube.com/user/LeadingStrand)  -冷泉港实验室（CSHL）会议的主题演讲.  更多关于 [The Leading Strand](http://theleadingstrand.cshl.edu/).
* [Genomics, Big Data and Medicine Seminar Series](https://www.youtube.com/playlist?list=PLqLDR0CTP9_pboZCk6gR9Zn4kW7h9XWJI) -“我们的研讨会专门针对GBM的关键交叉领域，深入研究将深刻塑造未来的&#39;出血边缘&#39;技术和方法.”
* [Rafael Irizarry's Channel](https://www.youtube.com/user/RafalabChannel/videos) -Rafael Irizarry博士关于基因组统计的讲座和学术讲座.
* [NIH VideoCasting and Podcasting](https://www.youtube.com/user/nihvcast)  -“ NIH VideoCast通过互联网向全世界的观众直播研讨会，会议和会议，作为实时流视频.”  不仅是基因组学和生物信息学视频，而且还有许多关于特定领域的生物信息学和基因组学使用的精彩演讲.

### Blogs

* [ACGT](http://www.acgt.me/) -基思·布拉德南（Keith Bradnam）博士写道：“关于生物学，基因组学以及伪造生物信息素的丙烯醛对人类的持续威胁的思想”.
* [Opiniomics](http://www.opiniomics.org/) -Mick Watson博士写有关生物信息学，基因组和生物学的文章.
* [Bits of DNA](https://liorpachter.wordpress.com/) -Lior Pachter博士撰写了有关计算生物学的评论和评论.
* [it is NOT junk](http://www.michaeleisen.org/blog/) -迈克尔·艾森（Michael Eisen）博士撰写了“关于基因组，DNA，进化，开放科学，棒球和其他重要事物的博客”

### Miscellaneous

* [The Leek group guide to genomics papers](https://github.com/jtleek/genomicspapers/) -精心策划的基因组学论文，以加快了解基因组学，RNA序列，统计（用于基因组学），软件开发等方面的知识.
* [A New Online Computational Biology Curriculum](https://doi.org/10.1371/journal.pcbi.1003662) -“本文介绍了数百个免费视频课程的目录，这些课程对那些希望扩展其生物信息学和计算生物学知识的人们来说是必不可少的.这些课程分为11个学科领域，以大学部门为蓝本，并附有评论和职业建议. ”
* [How Perl Saved the Human Genome Project](http://www.foo.be/docs/tpj/issues/vol1_2/tpj0102-0001.html) -林肯·斯坦因（Lincoln D. Stein）的轶事，有关Perl编程语言在人类基因组计划中的重要性.
* [Educational Papers from Nature Biotechnology and PLoS Computational Biology](https://liacs.leidenuniv.nl/~hoogeboomhj/mcb/nature_primer.html) -引文链接和关于计算生物学和生物信息学中使用的各种方法的简短教育文章的链接.
* [The PeerJ Bioinformatics Software Tools Collection](https://peerj.com/collections/45-bioinformatics-software/) -由Keith Crandall和Claus White策划的工具集合，旨在整理PeerJ中最有趣，创新和相关的生物信息学工具文章.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
