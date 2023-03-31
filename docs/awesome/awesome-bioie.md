<div class="github-widget" data-repo="caufieldjh/awesome-bioie"></div>
<div align="center">
	<img src="https://raw.githubusercontent.com/caufieldjh/awesome-bioie/master/images/abie_head.png" alt="Awesome BioIE Logo"/>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
	</a>
	<br>
	如何从非结构化生物医学数据和文本中提取信息.
	<br>
	
</div>

什么是 BioIE？ 它包括从_非结构化_（或至少结构不一致的）生物、临床或其他生物医学数据中提取结构化信息的任何努力. 数据源通常是一些用技术语言编写的文本文档的集合. 如果由此产生的信息是可验​​证的并且跨来源是一致的，那么我们可以将其视为_知识_. 从生物数据中提取信息和产生知识需要适应为其他类型的非结构化数据开发的方法.

此处包含的资源优先是那些无需货币成本和有限许可要求即可获得的资源. 方法和数据集应可公开访问并积极维护.

也可以看看 [awesome-nlp](https://github.com/keon/awesome-nlp), [awesome-biology](https://github.com/raivivek/awesome-biology) 和 [Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics).

_请阅读 [contribution guidelines](https://github.com/caufieldjh/awesome-bioie/blob/master/contributing.md) 在贡献之前. 请通过提出一个添加您喜欢的资源 [pull request](https://github.com/caufieldjh/awesome-bioie/pulls)._


## Research Overviews

* [Biomedical Informatics on the Cloud: A Treasure Hunt for Advancing Cardiovascular Medicine](https://www.ahajournals.org/doi/full/10.1161/CIRCRESAHA.117.310967) - 概述 BioIE 和生物信息学工作流程如何应用于心血管健康和医学研究中的问题.
* [Clinical information extraction applications: A literature review](https://www.sciencedirect.com/science/article/pii/S1532046417302563) - 截至 2016 年 9 月发表的临床 IE 论文综述.来自 Mayo Clinic 小组（见下文）.
* [Literature Based Discovery: Models, methods, and trends](https://www.sciencedirect.com/science/article/pii/S1532046417301909) - 对基于文献的发现 (LBD) 的回顾，或者在看似无关的科学文献之间可能会发现有意义的联系的哲学. 
  * 有关 LBD 的一些历史背景，请参阅芝加哥大学 Don Swanson 和 Neil Smalheiser 的论文，包括 [_Undiscovered Public Knowledge_](https://www.jstor.org/stable/4307965) （付费专区）和 [_Rediscovering Don Swanson: the Past, Present and Future of Literature-Based Discovery_](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5771422/).
* [Mining Electronic Health Records (EHRs): A Survey](https://arxiv.org/abs/1702.03222)  - 回顾挖掘电子健康记录背后的方法和理念，包括将它们用于不良事件检测. 有关截至 2017 年年中的相关论文列表，请参见表 2.
* [Capturing the Patient's Perspective: a Review of Advances in Natural Language Processing of Health-Related Text](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6250990/)  - 2017 年对应用于健康记录和社交媒体文本信息提取的自然语言处理方法的回顾. 这篇评论的一个重要说明：“该领域的主要挑战之一是可共享数据的可用性，并且社区可以使用这些数据来推动基于可比较和可重复研究的方法的开发”.


## Groups Active in the Field

* [Boston Children's Hospital Natural Language Processing Laboratory](http://www.childrenshospital.org/research/labs/natural-language-processing-laboratory) - 由曾在 Mayo Clinic 和 Apache cTAKES 项目工作的 Guergana Savova 博士领导.
* [BD2K](https://commonfund.nih.gov/bd2k) - 美国国立卫生研究院 (NIH) 通过其大数据知识 (BD2K) 计划资助了 13 个卓越中心，其中一些中心为 BioIE 开发了工具和资源.
  * [HeartBD2K](http://www.heartbd2k.org/)  - 位于加州大学洛杉矶分校 (UCLA). 由平佩佩博士领衔.
  * [KnowEng](https://knoweng.org/about/people/)  - 基于伊利诺伊大学香槟分校 (UIUC). 韩嘉伟博士领衔.
  * [Mobilize](http://mobilize.stanford.edu/)  - 总部设在斯坦福大学. 由 Scott Delp 博士领导.
* [Brown Center for Biomedical Informatics](https://www.brown.edu/academics/medical/about-us/research/centers-institutes-and-programs/biomedical-informatics/) - 位于布朗大学，由 Neil Sarkar 博士指导，其研究小组致力于临床 NLP 和 IE 的主题.
* [Center for Computational Pharmacology NLP Group](http://compbio.ucdenver.edu/Hunter_lab/CCP_website/index.html) - 位于科罗拉多大学丹佛分校，由 Larry Hunter 领导 - [see their GitHub repos here.](https://github.com/UCDenver-ccp)
* 美国国立卫生研究院 (NIH) / 国家医学图书馆 (NLM) 的小组：
  * [Demner-Fushman group at NLM](https://www.lhncbc.nlm.nih.gov/personnel/dina-demner-fushman)
  * [BioNLP group at NCBI](https://www.ncbi.nlm.nih.gov/research/bionlp/) - 开发改进生物医学文献搜索和管理（例如，通过 PubMed），由 Zhiyong Lu 博士领导.
* [JensenLab](https://jensenlab.org/) - 位于丹麦哥本哈根大学的诺和诺德基金会蛋白质研究中心. 
* [National Centre for Text Mining (NaCTeM)](http://www.nactem.ac.uk/) - NaCTeM 位于曼彻斯特大学，由 Sophia Ananiadou 教授领导，主要关注文本挖掘，但特别关注生物医学应用.
* [Mayo Clinic's clinical natural language processing program](https://www.mayo.edu/research/departments-divisions/department-health-sciences-research/medical-informatics/projects) - 在过去的 20 年里，Mayo Clinic 的几个团队为 BioIE（例如 Apache cTAKES 平台）做出了重大贡献.
* [Monarch Initiative](https://monarchinitiative.org/) - 俄勒冈州立大学、俄勒冈健康与科学大学、劳伦斯伯克利国家实验室、杰克逊实验室和其他几个团体之间的共同努力，寻求“使用语义整合生物信息，并以一种新颖的方式呈现它，利用表型来弥合知识鸿沟”.
* [TurkuNLP](https://turkunlp.org/) - 在图尔库大学工作，总体上关注 NLP，重点是 BioNLP 和临床应用.
* [UTHealth Houston Biomedical Natural Language Processing Lab](https://sbmi.uth.edu/nlp/) - 设在德克萨斯大学休斯顿健康科学中心生物医学信息学院，由 Hua Xu 博士领导.
* [VCU Natural Language Processing Lab](https://nlp.cs.vcu.edu/) - 总部设在弗吉尼亚联邦大学，由 Bridget McInnes 博士领导.
* [Zaklab](http://zaklab.org) - 由哈佛医学院生物医学信息学系 Isaac Kohane 博士领导的小组（Kohane 博士也是 n2c2（以前称为 i2b2）数据集的管理者 - 请参阅 [Datasets](#datasets) 以下）.
* [Columbia University Department of Biomedical Informatics](https://www.dbmi.columbia.edu/)  - 由博士领导.  George Hripcsak 和 Noémie Elhadad.


## Organizations

* [AMIA](https://www.amia.org/)  - 许多（但肯定不是全部）研究生物医学信息学的人都是美国医学信息学协会的成员.  AMIA 出版期刊 JAMIA（见下文）.
* [IMIA](https://imia-medinfo.org/)  - 国际医学信息学协会. 出版 IMIA 医学信息学年鉴.


## Journals and Events

 BioIE 的跨学科性质意味着该领域的研究人员可以通过多种方式分享他们的发现和工具. 他们可能会在期刊上发表论文，这在生物医学和生命科学领域很常见. 他们可以发表会议论文，并在被接受后，在活动中进行海报和/或口头陈述； 这是计算机科学和工程领域的常见做法. 会议论文通常以会议论文集的形式发表. 预印本出版也是一种越来越流行和被机构接受的发表研究结果的方式. 围绕这些正式的书面产品的是 [open science](https://en.wikipedia.org/wiki/Open_science)、开放数据和开放源代码：BioIE 研究人员开发的代码、数据和软件是社区的宝贵资源.

### Journals

对于预印本，请尝试 [arXiv](https://arxiv.org)，尤其是计算与语言 (cs.CL) 和信息检索 (cs.IR) 科目； [bioRxiv](https://www.biorxiv.org/) ; 或者 [medRxiv](https://www.medrxiv.org/)，尤其是健康信息学学科领域.

* [Database](https://academic.oup.com/database)  - 它的副标题是“生物数据库和管理杂志”. 开放访问.
* [NAR](https://academic.oup.com/nar)  - 核酸研究. 具有广泛的生物分子重点，但特别值得注意的是其年度数据库问题.
* [JAMIA](https://academic.oup.com/jamia)  - 美国医学信息学协会杂志. 关注“临床护理、临床研究、转化科学、实施科学、成像、教育、消费者健康、公共卫生和政策领域的文章”.
* [JBI](https://www.sciencedirect.com/journal/journal-of-biomedical-informatics)  - 生物医学信息学杂志. 默认情况下不开放访问，尽管它确实有一个开放访问的“X”版本.
* [Scientific Data](https://www.nature.com/sdata/) - 一份开放获取的 Springer Nature 期刊，出版“具有科学价值的数据集的描述，以及促进科学数据共享和重用的研究”.

### Conferences and Other Events

* [ACM-BCB](http://acm-bcb.org/)  - 关于生物信息学、计算生物学和健康信息学的 ACM 会议. 自2010年起每年举办一次.
* [BIBM](http://ieeebibm.org/BIBM2019/) - IEEE 生物信息学和生物医学国际会议.
* [PSB](https://psb.stanford.edu/) - 太平洋生物计算研讨会.

### Challenges

BioIE 中的一些活动是围绕正式任务和挑战组织的，在这些任务和挑战中，小组根据给定的数据集开发自己的计算解决方案.

* [BioASQ](http://bioasq.org/)  - 生物医学语义索引和问答方面的挑战. 自 2013 年以来每年举办挑战赛和研讨会.
* [BioCreAtIvE workshop](https://biocreative.bioinformatics.udel.edu/) - 这些研讨会自 2004 年开始举办，BioCreative VI 于 2017 年 2 月举行， [BioCreative/OHNLP Challenge](https://sites.google.com/view/ohnlp2018/home) 于 2018 年举行.见 [Datasets](#datasets) 以下. 
* [SemEval workshop](http://alt.qcri.org/semeval2020/)  - 计算语义分析中的任务和评估. 任务因年份而异，但通常涵盖科学和/或生物医学语言，例如 [SemEval-2019 Task 12 on Toponym Resolution in Scientific Papers](https://competitions.codalab.org/competitions/19948).
* [eHealth-KD](https://knowledge-learning.github.io/ehealthkd-2019/)  - 鼓励“开发软件技术以自动从用西班牙语编写的 eHealth 文档中提取大量知识”的挑战. 以前作为的一部分举行 [TASS](http://www.sepln.org/workshops/tass/)，一年一度的西班牙语语义分析研讨会.


## Tutorials

该领域的变化非常快，以至于几年前的教程都缺少关键细节. 下面列出了一些最近的教育资源. 对文本挖掘技术有良好的基础理解非常有帮助，对 Python 和/或 R 语言有一些基本经验也是如此. 从 [NLTK tutorials](https://www.nltk.org/book/) 然后试用教程 [Flair framework](https://github.com/zalandoresearch/flair) 将提供自然语言处理、文本挖掘和现代机器学习驱动方法的优秀示例，全部使用 Python. 但是，大多数示例不包含任何生物医学内容，因此最好的选择可能是边做边学.

### Guides

* [Getting Started in Text Mining](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.0040020)  - Cohen 和 Hunter 对生物文本挖掘的简要介绍. 十多年了，但仍然很相关. 另见 [earlier paper by the same authors](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1702322/).
* [Biomedical Literature Mining](https://link.springer.com/book/10.1007/978-1-4939-0709-0) - 2014 年的《分子生物学方法》（非免费）卷.章节涵盖文本挖掘中的介绍性原理、生物科学中的应用以及在临床或医疗安全场景中的使用潜力. 

### Video Lectures and Online Courses

* [Coursera - Foundations of mining non-structured medical data](https://www.coursera.org/learn/mining-medical-data)  - 关于处理各种类型和结构的医疗数据（包括文本和图像数据）的大约三个小时的视频讲座. 看起来相当高级，适合初学者.
* [JensenLab text mining exercises](https://jensenlab.org/training/textmining/)
* [VIB text mining and curation training](https://www.bits.vib.be/training-list/111-bits/training/previous-trainings/183-text-mining) - 这个培训研讨会发生在 2013 年，但幻灯片仍然在线.


## Code Libraries

* [Biopython](https://biopython.org/) - [paper](http://dx.doi.org/10.1093/bioinformatics/btp163) - [code](https://github.com/biopython/biopython) - 主要用于生物信息学和计算分子生物学目的的 Python 工具，也是一种获取数据的便捷方式，包括来自 PubMed 的文档/摘要（参见文档的第 9 章）.
* [Bio-SCoRes](https://github.com/kilicogluh/Bio-SCoRes) - [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0148538) - 生物医学共指解析框架.
* [medaCy](https://github.com/NLPatVCU/medaCy)  - 用于构建预测医学自然语言处理模型的系统. 建立在 [spaCy](https://spacy.io/) 框架. 
* [ScispaCy](https://github.com/allenai/SciSpaCy) - [paper](https://arxiv.org/abs/1902.07669) - 的一个版本 [spaCy](https://spacy.io/) 科学和生物医学文件的框架.
* [rentrez](https://github.com/ropensci/rentrez) - 用于访问 NCBI 资源的 R 实用程序，包括 PubMed.
* [Med7](https://medium.com/@kormilitzin/med7-clinical-information-extraction-system-in-python-and-spacy-5e6f68ab1c68) - [paper](https://arxiv.org/abs/2003.01271) - [code](https://github.com/kormilitzin/med7) - 用于使用药物相关概念进行 NER 的 Python 包和模型（用于 spaCy）.

### Repos for Specific Datasets

* [mimic-code](https://github.com/MIT-LCP/mimic-code)  - 与 MIMIC-III 数据集相关的代码（见下文）. 包括一些有帮助 [tutorials](https://github.com/MIT-LCP/mimic-code/tree/master/tutorials).


## Tools, Platforms, and Services

* [cTAKES](https://ctakes.apache.org/) - [paper](https://academic.oup.com/jamia/article/17/5/507/830823) - [code](https://github.com/apache/ctakes)  - 处理电子病历文本的系统. 广泛使用和开源. 
* [CLAMP](https://clamp.uth.edu/) - [paper](https://academic.oup.com/jamia/article/25/3/331/4657212)  - 旨在与临床报告中的文本一起使用的自然语言处理工具包. 看看他们 [live demo](https://clamp.uth.edu/clampdemo.php) 首先看看它做了什么. 可免费用于学术研究.
* [DeepPhe](https://github.com/DeepPhe/DeepPhe-Release)  - 用于处理描述癌症表现的文档的系统. 基于 cTAKES（见上文）.
* [DNorm](https://www.ncbi.nlm.nih.gov/research/bionlp/Tools/dnorm/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3810844/)  - 一种疾病规范化方法，即，将提及的疾病名称和首字母缩略词与唯一的概念标识符联系起来. 可下载版本包括 NCBI 疾病语料库和 BC5CDR（参见下面的注释文本数据）.
* [PubTator Central](https://www.ncbi.nlm.nih.gov/research/pubtator/) - [paper](https://academic.oup.com/nar/article/47/W1/W587/5494727)  - 一个网络平台，可识别 PubMed 文章和 PubMed Central 全文中的五种不同类型的生物医学概念. 完整的注释集是可下载的（见 [Annotated Text Data](#annotated-text-data) 以下）.
* [Pubrunner](https://github.com/jakelever/pubrunner) - A framework for running text mining tools on the newest set(s) of documents from PubMed.
* [SemEHR](https://github.com/CogStack/CogStack-SemEHR) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6019046/)  - 用于电子健康记录 (EHR) 的 IE 基础设施. 建立在 [CogStack project](https://github.com/CogStack).
* [TaggerOne](https://www.ncbi.nlm.nih.gov/research/bionlp/Tools/taggerone/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5018376/)  - 执行概念规范化（另见上面的 DNorm）. 可以针对特定概念类型进行训练，并且可以独立于其他规范化功能执行 NER.
* [TabInOut](https://github.com/nikolamilosevic86/TabInOut) - [paper](https://link.springer.com/article/10.1007/s10032-019-00317-0) - 来自文献中表格的 IE 框架.

### Annotation Tools

* [Anafora](https://github.com/weitechen/anafora) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5657237/) - 具有裁决和进度跟踪功能的注释工具.
* [brat](https://brat.nlplab.org/) - [paper](https://www.aclweb.org/anthology/E12-2021/) - [code](https://github.com/nlplab/brat) - The brat rapid annotation tool. Supports producing text annotations visually, through the browser. Not subject specific; appropriate for many annotation projects. Visualization is based on that of the [_stav_ tool](https://github.com/nlplab/stav/).
* [MedTator](https://ohnlp.github.io/MedTator/) - [paper](https://academic.oup.com/bioinformatics/article-abstract/38/6/1776/6496915) - [code](https://github.com/OHNLP/MedTator) - 旨在具有最小依赖性的注释工具.


## Techniques

### Text Embeddings

[This paper from Hongfang Liu's group at Mayo Clinic](https://www.sciencedirect.com/science/article/pii/S1532046418301825) 演示了在生物医学或临床文本上训练的文本嵌入如何能够（但并不总是）在生物医学自然语言处理任务上表现更好. 话虽这么说，预训练嵌入可能适合您的需求，尤其是训练特定领域的嵌入可能需要大量计算.

### Word Embeddings

* [BioASQword2vec](http://bioasq.org/news/bioasq-releases-continuous-space-word-vectors-obtained-applying-word2vec-pubmed-abstracts) - [paper](http://bioasq.lip6.fr/info/BioASQword2vec/) - 使用流行的从生物医学文本（&gt; 1000 万 PubMed 摘要）派生的 Qord 嵌入 [word2vec](https://code.google.com/archive/p/word2vec/) 工具.
* [BioWordVec](https://figshare.com/articles/Improving_Biomedical_Word_Embeddings_with_Subword_Information_and_MeSH_Ontology/6882647) - [paper](https://www.nature.com/articles/s41597-019-0055-0) - [code](https://github.com/ncbi-nlp/BioWordVec) - 源自生物医学文本（&gt; 2700 万 PubMed 标题和摘要）的词嵌入，包括基于 MeSH 的子词嵌入模型.

### Language Models

#### BERT models
* [BioBERT](https://github.com/naver/biobert-pretrained) - [paper](https://arxiv.org/abs/1901.08746) - [code](https://github.com/dmis-lab/biobert) - PubMed 和 PubMed Central 训练的版本 [BERT language model](https://arxiv.org/abs/1810.04805).
 * ClinicalBERT - 在临床文本上训练的两种语言模型具有相似的名称. 两者都是根据 MIMIC-III 数据集的临床笔记文本训练的 BERT 模型.
  * [Alsentzer et al Clinical BERT](https://github.com/EmilyAlsentzer/clinicalBERT) - [paper](https://www.aclweb.org/anthology/W19-1909/)
  * [Huang et al ClinicalBERT](https://github.com/kexinhuang12345/clinicalBERT) - [paper](https://arxiv.org/abs/1904.05342)
* [SciBERT](https://github.com/allenai/scibert) - [paper](https://arxiv.org/abs/1903.10676) - 一个 BERT 模型在超过 100 万篇来自 Semantic Sc​​holar 数据库的论文上进行训练.
* [BlueBERT](https://github.com/ncbi-nlp/bluebert) - [paper](https://arxiv.org/abs/1906.05474) - 在 PubMed 文本和 MIMIC-III 笔记上预训练的 BERT 模型.
* [PubMedBERT](https://microsoft.github.io/BLURB/models.html) - [paper](https://arxiv.org/abs/2007.15779) - A BERT model trained from scratch on PubMed, with versions trained on abstracts+full texts and on abstracts alone.

#### GPT models
* [BioGPT](https://github.com/microsoft/BioGPT) - [paper](https://doi.org/10.1093/bib/bbac409) - 在 1500 万份 PubMed 摘要上预训练的 GPT-2 模型，以及针对多项生物医学任务的微调版本.

#### Other models
* [Flair embeddings from PubMed](https://github.com/zalandoresearch/flair/pull/519)  - 通过 Flair 框架和嵌入方法可用的语言模型. 截至 2015 年，培训了超过 5% 的 PubMed 摘要样本，或总共超过 120 万份摘要.


## Datasets

下面列出的一些数据集需要 [UMLS Terminology Services (UTS) account](https://www.nlm.nih.gov/databases/umls.html#license_request) 访问. 请注意，授予 UTS 帐户的许可证要求用户提交有关他们使用 UMLS 资源的年度报告. 这不像听起来那么具有挑战性.

### Biomedical Text Sources

以下资源包含生物医学科学中的索引文本文档.
* [OHSUMED](http://davis.wpi.edu/xmdv/datasets/ohsumed.html) - [paper](https://dl.acm.org/citation.cfm?id=188557)  - 1987 年至 1991 年间的 348,566 个 MEDLINE 条目（标题和有时是摘要）.包括 MeSH 标签. 主要是具有历史意义.
* [PubMed Central Open Access Subset](https://www.ncbi.nlm.nih.gov/pmc/tools/openftlist/)  - 一组 PubMed Central 文章可在传统版权以外的许可下使用，但确切的许可因出版物和来源而异. 文章以 PDF 和 XML 格式提供.
* [CORD-19](https://github.com/allenai/cord19)  - 关于 COVID-19 的学术手稿语料库. 文章主要来自 PubMed Central 和预印本服务器，尽管该集合还包括没有全文可用性的论文元数据.

### Annotated Text Data

* [SPL-ADR-200db](https://bionlp.nlm.nih.gov/tac2017adversereactions/) - [paper](https://www.nature.com/articles/sdata20181) - 包含标准化信息和文本注释的试点数据集，约 200 种 FDA 批准药物的约 5,000 种已知不良反应.
* [BioCreAtIvE 1](https://sourceforge.net/projects/biocreative/files/) - [paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-6-S1-S1)  - 15,000 个句子（10,000 个训练和 5,000 个测试）注释了蛋白质和基因名称.  1,000 篇全文生物医学研究文章，注释有蛋白质名称和基因本体术语.
* [BioCreAtIvE 2](https://sourceforge.net/projects/biocreative/files/) - [paper](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2008-9-s2-s1)  - 15,000 个句子（10,000 个训练和 5,000 个测试，与第一个语料库不同）注释了蛋白质和基因名称.  542 个摘要链接到 EntrezGene 标识符. 各种研究文章注释了蛋白质-蛋白质相互作用的特征.
* [BioCreAtIvE V CDR Task Corpus (BC5CDR)](https://biocreative.bioinformatics.udel.edu/accounts/login/?next=/resources/corpora/biocreative-v-cdr-corpus/) - [paper](https://academic.oup.com/database/article/doi/10.1093/database/baw068/2630414)  - 2014 年或之后发表的 1,500 篇文章（标题和摘要），注释了 4,409 种化学物质、5,818 种疾病和 3116 种化学-疾病相互作用. 需要注册.
* [BioCreative VI CHEMPROT Corpus](https://biocreative.bioinformatics.udel.edu/resources/corpora/chemprot-corpus-biocreative-vi/#chemprot-corpus-biocreative-vi:downloads) - [paper](https://pdfs.semanticscholar.org/eed7/81f498b563df5a9e8a241c67d63dd1d92ad5.pdf)  - &gt;2,400 篇文章注释了各种关系类型的化学-蛋白质相互作用. 需要注册.
* [CRAFT](https://github.com/UCDenver-ccp/CRAFT) - [paper](https://link.springer.com/chapter/10.1007/978-94-024-0881-2_53)  - 67 篇以各种方式注释的生物医学全文文章，包括概念和引用. 现在是第 5 版，包括将概念链接到 MONDO 疾病本体的注释.
* [n2c2 (formerly i2b2) Data](https://portal.dbmi.hms.harvard.edu/projects/n2c2-nlp/)  - 哈佛医学院生物医学信息学系 (DBMI) 管理自 2006 年以来运行的国家 NLP 临床挑战和整合生物学信息学和床边挑战的数据.它们需要注册才能访问和使用. 数据集包括各种主题. 见 [list of data challenges](https://portal.dbmi.hms.harvard.edu/data-challenges/) 用于个别说明.
* [NCBI Disease Corpus](https://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/) - [paper](https://www.sciencedirect.com/science/article/pii/S1532046413001974) - 一个包含 793 个生物医学摘要的语料库，其中注释了疾病名称和相关概念，来自 MeSH 和 [OMIM](https://omim.org/).
* [PubTator Central datasets](https://www.ncbi.nlm.nih.gov/research/pubtator/) - [paper](https://academic.oup.com/nar/article/47/W1/W587/5494727)  - 可通过 RESTful API 或 FTP 下载访问. 包括超过 2900 万份摘要和约 300 万份全文文档的注释.
* [Word Sense Disambiguation (WSD)](https://wsd.nlm.nih.gov/) - [paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-223)  - 203 个歧义词和 37,888 个自动提取的生物医学研究出版物中使用它们的实例. 需要UTS账户.
* [Clinical Questions Collection](https://www.nlm.nih.gov/databases/download/CQC.html) - 也称为 CQC 或爱荷华州收集，这些是医生在办公室访问期间提出的数千个问题以及相关的答案.
* [BioNLP ST 2013 datasets](http://2013.bionlp-st.org/)  - 来自六个共享任务的数据，尽管有些可能不容易访问； 尝试使用 CG 任务集 (BioNLP2013CG) 进行广泛的实体和事件注释.
* [BioScope](https://rgai.inf.u-szeged.hu/node/105) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2586758/) - 来自医学和生物文件的句子语料库，注释否定、推测和语言范围.
* [BioRED](https://ftp.ncbi.nlm.nih.gov/pub/lu/BioRED/) - [paper](https://arxiv.org/abs/2204.04263) - 一组超过 6.5K 的生物医学关系注释，以及新发现的标签.

### Protein-protein Interaction Annotated Corpora
蛋白质-蛋白质相互作用缩写为 PPI. 以下套装可在 [BioC format](http://bioc.sourceforge.net/) . 旧套件（AIMed、BioInfer、HPRD50、IEPA 和 LLL）可由 [WBI corpora repository](http://corpora.informatik.hu-berlin.de) 最初是从原始集派生 [group at Turku University](http://mars.cs.utu.fi/PPICorpora/).

* [AIMed](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/aimed_bioc.xml.zip) - [paper](https://www.ncbi.nlm.nih.gov/pubmed/15811782) - 为 PPI 注释的 225 个 MEDLINE 摘要.
* [BioC-BioGRID](http://bioc.sourceforge.net/BioC-BioGRID.html) - [paper](https://academic.oup.com/database/article/doi/10.1093/database/baw147/2884890)  - 120 篇带 PPI 和遗传相互作用注释的全文文章. 用于 BioCreative V BioC 任务.
* [BioInfer](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/bioinfer_bioc.xml.zip) - [paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-8-50) - 1,100 个来自生物医学研究摘要的句子，注释了关系（包括 PPI）、命名实体和句法依赖性. [Additional information and download links are here.](http://mars.cs.utu.fi/BioInfer/)
* [HPRD50](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/hprd50_bioc.xml.zip) - [paper](https://academic.oup.com/bioinformatics/article/23/3/365/236564) - 人类蛋白质参考数据库引用的 50 篇科学摘要，为 PPI 注释.
* [IEPA](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/iepa_bioc.xml.zip) - [paper](http://psb.stanford.edu/psb-online/proceedings/psb02/abstracts/p326.html) - 来自生物医学研究摘要的 486 个句子，注释了成对的共生化学物质，包括蛋白质（因此，PPI 注释）.
* [LLL](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/lll_bioc.xml.zip) - [paper](https://www.semanticscholar.org/paper/Learning-Language-in-Logic-Genic-Interaction-Nedellec/0863a9d71955341b7e1a6a6877d44d4f0bb22671) - 来自关于细菌_枯草芽孢杆菌_的研究文章的 77 句话，注释了蛋白质-基因相互作用（因此，非常接近 PPI 注释）. [Additional information is here.](http://genome.jouy.inra.fr/texte/LLLchallenge/#task1)

### Other Datasets

* [Columbia Open Health Data](http://cohd.io) - [paper](https://www.nature.com/articles/sdata2018273)  - 从电子健康记录中提取的条件、药物、程序和患者人口统计数据的流行和共现频率的数据库. 不包括原始记录文本.
* [Comparative Toxicogenomics Database](https://ctdbase.org/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6323936/)  - 化学品、基因产物、表型、疾病和环境暴露之间的人工关联数据库. 用于组装相关概念的本体，例如化学品的类型.
* [MIMIC-III](https://mimic.physionet.org/) - [paper](https://www.nature.com/articles/sdata201635)  - 来自约 60,000 名重症监护病房入院者的去识别化健康数据. 需要完成在线培训课程（CITI 培训）并在使用前接受数据使用协议.
* [MIMIC-IV](https://mimic-iv.mit.edu/) - 对 MIMIC-III 多模式患者数据的更新，现在涵盖了最近几年的入院情况，以及新的数据结构、急诊科记录和 MIMIC-CXR 图像的链接.
* [eICU Collaborative Research Database](https://eicu-crd.mit.edu/) - [paper](https://www.nature.com/articles/sdata2018178)  - 来自超过 20 万重症监护病房入院观察的数据库，具有一致的结构. 需要注册、完成培训课程和数据使用协议.


## Ontologies and Controlled Vocabularies

* [Disease Ontology](http://www.disease-ontology.org/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4383880/)  - 人类疾病的本体论. 与 MeSH、ICD、NCI 叙词表、SNOMED 和 OMIM 有交叉链接. 公共区域. 可用时间 [GitHub](https://github.com/DiseaseOntology/HumanDiseaseOntology) 并在 [OBO Foundry](http://www.obofoundry.org/ontology/doid.html).
* [RxNorm](https://www.nlm.nih.gov/research/umls/rxnorm/index.html) - [paper](https://academic.oup.com/jamia/article/18/4/441/734170)  - 临床药物和药物包装的标准化名称，具有组合的成分、强度和形式，以及来自语义网络的指定类型（见下文）. 每月发布.
* [SPECIALIST Lexicon](https://lexsrv3.nlm.nih.gov/Specialist/Summary/lexicon.html) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2247735/)  - 包含许多生物医学术语的通用英语词典. 自 1994 年以来每年更新一次，截至 2019 年仍在更新.是 UMLS 的一部分，但不需要 UTS 帐户即可下载.
* [UMLS Metathesaurus](https://www.nlm.nih.gov/research/umls/knowledge_sources/metathesaurus/index.html) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC308795/)  - 超过 380 万个概念、1400 万个概念名称和超过 200 个生物医学词汇和标识符来源之间的映射. 它很大. 它可能有助于准备 Metathesaurus 的一个子集 [MetamorphoSys installation tool](https://www.nlm.nih.gov/research/umls/implementation_resources/metamorphosys/help.html) 但我们仍在谈论 2019 版本所需的约 30 Gb 磁盘空间. [See the manual here](https://www.ncbi.nlm.nih.gov/books/NBK9684/) . 需要UTS账户.
* [UMLS Semantic Network](https://semanticnetwork.nlm.nih.gov/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2447396/)  - 涵盖生物医学概念和词汇的 133 种语义类型和 54 种语义关系列表.  Metathesaurus 是否太复杂，无法满足您的需求？ 尝试这个. 不需要 UTS 帐户即可下载.


## Data Models

你需要一个 [data model](https://en.wikipedia.org/wiki/Data_model) ？ 如果您正在处理生物医学数据，那么答案可能是“是”.

* [Biolink](https://biolink.github.io/biolink-model/) - [code](https://github.com/biolink/biolink-model)  - 生物实体的数据模型. 提供为 [YAML](https://yaml.org/) 文件.
* [BioUML](http://wiki.biouml.org/index.php/BioUML) - [paper](https://academic.oup.com/nar/article/47/W1/W225/5498754)  - 用于生物医学数据分析、集成和可视化的架构. 概念上基于可视化建模语言 [UML](https://www.uml.org/what-is-uml.htm).
* [OMOP Common Data Model](https://github.com/OHDSI/CommonDataModel) - 观察性医疗保健数据标准.


## Credits

[Credits](https://github.com/caufieldjh/awesome-bioie/blob/master/./CREDITS.md) 对于策展人和消息来源.

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

[License](https://github.com/caufieldjh/awesome-bioie/blob/master/./LICENSE)
