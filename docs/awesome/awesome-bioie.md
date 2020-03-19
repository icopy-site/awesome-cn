<div class="github-widget" data-repo="caufieldjh/awesome-bioie"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
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

What is BioIE? It includes any effort to extract structured information from _unstructured_ (or, at least inconsistently structured) biological, clinical, or other biomedical data. The data source is often some collection of text documents written in technical language. If the resulting information is verifiable and consistent across sources, we may then consider it _knowledge_. Extracting information and producing knowledge from bio data requires adaptations upon methods developed for other types of unstructured data.

 此处包含的资源优先是那些无须花费金钱和有限许可要求的资源.  方法和数据集应公开可用并积极维护.

也可以看看 [awesome-nlp](https://github.com/keon/awesome-nlp), [awesome-biology](https://github.com/raivivek/awesome-biology) 和 [Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics).

_请阅读 [contribution guidelines](https://github.com/caufieldjh/awesome-bioie/blob/master/contributing.md)  在贡献之前.  请提出一个 [pull request](https://github.com/caufieldjh/awesome-bioie/pulls)._


## Research Overviews

* [Biomedical Informatics on the Cloud: A Treasure Hunt for Advancing Cardiovascular Medicine](https://www.ahajournals.org/doi/full/10.1161/CIRCRESAHA.117.310967) -有关如何将BioIE和生物信息学工作流程应用于心血管健康和医学研究中的问题的概述.
* [Clinical information extraction applications: A literature review](https://www.sciencedirect.com/science/article/pii/S1532046417302563) -截至2016年9月发表的临床IE论文综述.来自Mayo Clinic小组（请参见下文）.
* [Literature Based Discovery: Models, methods, and trends](https://www.sciencedirect.com/science/article/pii/S1532046417301909) -回顾基于文学的发现（LBD），或在似乎无关的科学文献之间可能找到有意义的联系的哲学. 
  *有关LBD的一些历史背景，请参阅芝加哥大学的Don Swanson和Neil Smalheiser的论文，包括 [_Undiscovered Public Knowledge_](https://www.jstor.org/stable/4307965) （付费专区）和 [_Rediscovering Don Swanson: the Past, Present and Future of Literature-Based Discovery_](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5771422/).
* [Mining Electronic Health Records (EHRs): A Survey](https://arxiv.org/abs/1702.03222)  -审查挖掘电子健康记录的方法和理念，包括将其用于不良事件检测.  截至2017年中，相关论文列表见表2.
* [Capturing the Patient's Perspective: a Review of Advances in Natural Language Processing of Health-Related Text](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6250990/)  -2017年对自然语言处理方法的回顾，该方法适用于健康记录和社交媒体文本中的信息提取.  此次审查的重要说明：“该领域的主要挑战之一是可共享的数据的可用性，社区可以使用这些数据来推动基于可比较和可重复研究的方法的开发”.


## Groups Active in the Field

* [Boston Children's Hospital Natural Language Processing Laboratory](http://www.childrenshospital.org/research/labs/natural-language-processing-laboratory) -由曾在Mayo Clinic和Apache cTAKES项目中的Guergana Savova博士领导.
* [BD2K](https://commonfund.nih.gov/bd2k) -美国国立卫生研究院（NIH）通过大数据知识（BD2K）计划资助了13个卓越中心，其中几个为BioIE开发了工具和资源.
  * [HeartBD2K](http://www.heartbd2k.org/)  -总部位于加利福尼亚大学洛杉矶分校（UCLA）.  由裴培培博士领导.
  * [KnowEng](https://knoweng.org/about/people/)  -设在伊利诺伊大学香槟分校（UIUC）.  韩佳伟博士领导.
  * [Mobilize](http://mobilize.stanford.edu/)  -总部位于斯坦福.  由Scott Delp博士领导.
* [Brown Center for Biomedical Informatics](https://www.brown.edu/academics/medical/about-us/research/centers-institutes-and-programs/biomedical-informatics/) -总部位于布朗大学，由尼尔·萨卡（Neil Sarkar）博士领导，其研究小组致力于临床NLP和IE的主题.
* [Center for Computational Pharmacology NLP Group](http://compbio.ucdenver.edu/Hunter_lab/CCP_website/index.html) -总部设在丹佛的科罗拉多大学，由拉里·亨特（Larry Hunter）领导- [see their GitHub repos here.](https://github.com/UCDenver-ccp)
*美国国立卫生研究院（NIH）/国家医学图书馆（NLM）的小组：
  * [Demner-Fushman group at NLM](https://www.lhncbc.nlm.nih.gov/personnel/dina-demner-fushman)
  * [BioNLP group at NCBI](https://www.ncbi.nlm.nih.gov/research/bionlp/) -由陆志勇博士领导，改进生物医学文献检索和管理（例如通过PubMed）.
* [JensenLab](https://jensenlab.org/) -总部位于丹麦哥本哈根大学的诺和诺德蛋白质研究基金会中心. 
* [National Centre for Text Mining (NaCTeM)](http://www.nactem.ac.uk/) -NaCTeM总部位于曼彻斯特大学，由Sophia Ananiadou教授领导，通常关注文本挖掘，但特别关注生物医学应用.
* [Mayo Clinic's clinical natural language processing program](https://www.mayo.edu/research/departments-divisions/department-health-sciences-research/medical-informatics/projects) -在过去20年中，Mayo Clinic的几个小组对BioIE（例如Apache cTAKES平台）做出了重大贡献.
* [Monarch Initiative](https://monarchinitiative.org/) -俄勒冈州立大学，俄勒冈健康与科学大学，劳伦斯·伯克利国家实验室，杰克逊实验室以及其他几家研究机构之间的共同努力，力求“利用语义整合生物学信息，并以新颖的方式展示生物信息，利用表型弥合知识鸿沟”.
* [TurkuNLP](https://turkunlp.org/) -总部位于图尔库大学，主要关注NLP，重点是BioNLP和临床应用.
* [UTHealth Houston Biomedical Natural Language Processing Lab](https://sbmi.uth.edu/nlp/) - Based in the University of Texas Health Science Center at Houston, School of Biomedical Informatics and led by Dr. Hua Xu.
* [VCU Natural Language Processing Lab](https://nlp.cs.vcu.edu/) -总部位于弗吉尼亚联邦大学，由布里奇特·麦金尼斯博士领导.
* [Zaklab](http://zaklab.org) -哈佛医学院生物医学信息学系的Isaac Kohane博士领导的小组（Kohane博士还是n2c2（以前称为i2b2）数据集的管理者-请参见 [Datasets](#datasets) 下面）.
* [Columbia University Department of Biomedical Informatics](https://www.dbmi.columbia.edu/)  -由博士领导  George Hripcsak和NoémieElhadad.


## Organizations

* [AMIA](https://www.amia.org/)  -研究生物医学信息学的许多人（当然不是全部）是美国医学信息学协会的成员.  AMIA发行期刊JAMIA（请参见下文）.
* [IMIA](https://imia-medinfo.org/)  -国际医学信息学协会.  出版《 IMIA医学信息学年鉴》.


## Journals and Events

 BioIE的跨学科性质意味着该领域的研究人员可以通过多种方式共享他们的发现和工具.  他们可能会在生物医学和生命科学领域很常见的期刊上发表论文.  他们可以发表会议论文，并在被接受后在活动中发表海报和/或口头陈述；  这是计算机科学和工程领域的普遍做法.  会议论文经常发表在论文集中.  预印本出版是一种越来越流行且被机构认可的发表发现的方式.  这些正式的书面产品周围是 [open science](https://en.wikipedia.org/wiki/Open_science)，开放数据和开源：BioIE研究人员开发的代码，数据和软件对社区来说是宝贵的资源.

### Journals

对于预印本，请尝试 [arXiv](https://arxiv.org)，尤其是主题计算和语言（cs.CL）和信息检索（cs.IR）； [bioRxiv](https://www.biorxiv.org/) ;  要么 [medRxiv](https://www.medrxiv.org/)，尤其是健康信息学主题领域.

* [Database](https://academic.oup.com/database)  -其副标题为“生物数据库与治疗杂志”.  开放存取.
* [NAR](https://academic.oup.com/nar)  -核酸研究.  具有广泛的生物分子焦点，但其年度数据库问题尤为突出.
* [JAMIA](https://academic.oup.com/jamia)  -美国医学信息学协会杂志.  关注“在临床护理，临床研究，转化科学，实施科学，影像学，教育，消费者健康，公共卫生和政策领域的文章”.
* [JBI](https://www.sciencedirect.com/journal/journal-of-biomedical-informatics)  -生物医学信息学杂志.  尽管它确实具有开放访问的“ X”版本，但默认情况下不是开放访问.
* [Scientific Data](https://www.nature.com/sdata/) -公开获取的Springer Nature期刊，出版了“具有科学价值的数据集的描述，以及促进科学数据共享和重用的研究”.

### Conferences and Other Events

* [ACM-BCB](http://acm-bcb.org/)  -ACM生物信息学，计算生物学和健康信息学会议.  自2010年以来每年举行一次.
* [BIBM](http://ieeebibm.org/BIBM2019/) -IEEE国际生物信息学和生物医学会议.
* [PSB](https://psb.stanford.edu/) -太平洋生物计算专题讨论会.

### Challenges

BioIE中的一些事件是围绕正式任务和挑战组织的，其中小组根据给定的数据集开发自己的计算解决方案.

* [BioASQ](http://bioasq.org/)  -生物医学语义索引和问题解答方面的挑战.  自2013年以来，每年举行一次挑战赛和研讨会.
* [BioCreAtIvE workshop](https://biocreative.bioinformatics.udel.edu/) -自2004年以来就组织了这些研讨会，BioCreative VI于2017年2月举行， [BioCreative/OHNLP Challenge](https://sites.google.com/view/ohnlp2018/home) 于2018年举行.请参阅 [Datasets](#datasets) 下面. 
* [SemEval workshop](http://alt.qcri.org/semeval2020/)  -计算语义分析中的任务和评估.  任务因年份而异，但通常涵盖科学和/或生物医学语言，例如 [SemEval-2019 Task 12 on Toponym Resolution in Scientific Papers](https://competitions.codalab.org/competitions/19948).
* [eHealth-KD](https://knowledge-learning.github.io/ehealthkd-2019/)  -鼓励“开发自动从以西班牙语编写的eHealth文档中提取大量知识的软件技术”面临的挑战.  以前作为 [TASS](http://www.sepln.org/workshops/tass/)，每年一次的西班牙语语义分析研讨会.


## Tutorials

 领域变化很快，以至于任何超过几年的教程都缺少关键细节.  下面列出了一些近期的教育资源.  对文本挖掘技术有良好的基础了解，对Python和R语言的一些基本经验也很有帮助.  从开始 [NLTK tutorials](https://www.nltk.org/book/) 然后尝试教程 [Flair framework](https://github.com/zalandoresearch/flair)  将以Python提供自然语言处理，文本挖掘和现代机器学习驱动方法的出色示例.  但是，大多数示例都不包含任何生物医学内容，因此最好的选择可能是边做边学.

### Guides

* [Getting Started in Text Mining](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.0040020)  -来自Cohen和Hunter的生物文本挖掘的简要介绍.  已有十多年的历史了，但仍然很有意义.  另请参阅 [earlier paper by the same authors](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1702322/).
* [Biomedical Literature Mining](https://link.springer.com/book/10.1007/978-1-4939-0709-0) -2014年以来（非免费）的《分子生物学方法》一书.各章介绍了文本挖掘的入门性原理，生物科学中的应用以及在临床或医学安全场景中的应用潜力. 

### Video Lectures and Online Courses

* [Coursera - Foundations of mining non-structured medical data](https://www.coursera.org/learn/mining-medical-data)  -大约三个小时的视频讲座，内容涉及处理各种类型和结构的医疗数据，包括文本和图像数据.  看起来相当高级，适合初学者.
* [JensenLab text mining exercises](https://jensenlab.org/training/textmining/)
* [VIB text mining and curation training](https://www.bits.vib.be/training-list/111-bits/training/previous-trainings/183-text-mining) -该培训研讨会于2013年举行，但幻灯片仍在线.


## Code Libraries

* [Biopython](https://biopython.org/) - [paper](http://dx.doi.org/10.1093/bioinformatics/btp163) - [code](https://github.com/biopython/biopython) -主要用于生物信息学和计算分子生物学目的的Python工具，但也是一种获取数据的便捷方法，包括从PubMed获得的文档/摘要（请参阅文档的第9章）.
* [Bio-SCoRes](https://github.com/kilicogluh/Bio-SCoRes) - [paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0148538) -生物医学共同参考解决方案的框架.
* [medaCy](https://github.com/NLPatVCU/medaCy)  -用于建立预测医学自然语言处理模型的系统.  建立在 [spaCy](https://spacy.io/) 框架. 
* [ScispaCy](https://github.com/allenai/SciSpaCy) - [paper](https://arxiv.org/abs/1902.07669) -版本 [spaCy](https://spacy.io/) 科学和生物医学文献的框架.
* [rentrez](https://github.com/ropensci/rentrez) - R utilities for accessing NCBI resources, including PubMed.

### Repos for Specific Datasets

* [mimic-code](https://github.com/MIT-LCP/mimic-code)  -与MIMIC-III数据集关联的代码（请参见下文）.  包括一些帮助 [tutorials](https://github.com/MIT-LCP/mimic-code/tree/master/tutorials).


## Tools, Platforms, and Services

* [cTAKES](https://ctakes.apache.org/) - [paper](https://academic.oup.com/jamia/article/17/5/507/830823) - [code](https://github.com/apache/ctakes)  -处理电子病历中文本的系统.  广泛使用和开源. 
* [CLAMP](https://clamp.uth.edu/) - [paper](https://academic.oup.com/jamia/article/25/3/331/4657212)  -旨在与临床报告中的文本配合使用的自然语言处理工具包.  看看他们 [live demo](https://clamp.uth.edu/clampdemo.php)  首先看看它的作用.  免费用于学术研究.
* [DeepPhe](https://github.com/DeepPhe/DeepPhe-Release)  -处理描述癌症表现的文件的系统.  基于cTAKES（请参见上文）.
* [DNorm](https://www.ncbi.nlm.nih.gov/research/bionlp/Tools/dnorm/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3810844/)  -一种用于疾病标准化的方法，即将疾病名称和缩写的提及链接到唯一的概念标识符.  可下载版本包括NCBI疾病语料库和BC5CDR（请参阅下面的带注释的文本数据）.
* [PubTator Central](https://www.ncbi.nlm.nih.gov/research/pubtator/) - [paper](https://academic.oup.com/nar/article/47/W1/W587/5494727)  -一个网络平台，可识别PubMed文章和PubMed Central全文中的五种不同类型的生物医学概念.  完整的注释集可下载（请参阅 [Annotated Text Data](#annotated-text-data) 下面）.
* [Pubrunner](https://github.com/jakelever/pubrunner) -在PubMed的最新文档集上运行文本挖掘工具的框架.
* [SemEHR](https://github.com/CogStack/CogStack-SemEHR) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6019046/)  -用于电子病历（EHR）的IE基础结构.  建立在 [CogStack project](https://github.com/CogStack).
* [TaggerOne](https://www.ncbi.nlm.nih.gov/research/bionlp/Tools/taggerone/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5018376/)  -执行概念归一化（另请参见上面的DNorm）.  可以接受针对特定概念类型的培训，并且可以独立于其他标准化功能执行NER.
* [TabInOut](https://github.com/nikolamilosevic86/TabInOut) - [paper](https://link.springer.com/article/10.1007/s10032-019-00317-0) -文献表中的IE框架.

### Annotation Tools

* [Anafora](https://github.com/weitechen/anafora) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5657237/) -具有裁决和进度跟踪功能的注释工具.
* [brat](https://brat.nlplab.org/) - [paper](https://www.aclweb.org/anthology/E12-2021/) - [code](https://github.com/nlplab/brat)  -臭小子快速注释工具.  支持通过浏览器直观地生成文本注释.  没有特定的主题；  适用于许多注释项目.  可视化基于 [_stav_ tool](https://github.com/nlplab/stav/). 


## Techniques

### Text Embeddings

[This paper from Hongfang Liu's group at Mayo Clinic](https://www.sciencedirect.com/science/article/pii/S1532046418301825)  演示了在生物医学或临床文本上训练的文本嵌入如何能够（但并非总是）在生物医学自然语言处理任务上表现更好.  话虽如此，预训练的嵌入可能适合您的需求，特别是因为训练特定于领域的嵌入可能需要大量计算.

### Word Embeddings

* [BioASQword2vec](http://bioasq.org/news/bioasq-releases-continuous-space-word-vectors-obtained-applying-word2vec-pubmed-abstracts) - [paper](http://bioasq.lip6.fr/info/BioASQword2vec/) -使用流行的生物医学文本（&gt; 1000万篇PubMed摘要）衍生的Qord嵌入 [word2vec](https://code.google.com/archive/p/word2vec/) 工具.
* [BioWordVec](https://figshare.com/articles/Improving_Biomedical_Word_Embeddings_with_Subword_Information_and_MeSH_Ontology/6882647) - [paper](https://www.nature.com/articles/s41597-019-0055-0) - [code](https://github.com/ncbi-nlp/BioWordVec) -从生物医学文本（&gt; 2700万篇PubMed标题和摘要）衍生的词嵌入，包括基于MeSH的子词嵌入模型.

### Language Models

* [BioBERT](https://github.com/naver/biobert-pretrained) - [paper](https://arxiv.org/abs/1901.08746) - [code](https://github.com/dmis-lab/biobert) -的PubMed和PubMed中央培训版 [BERT language model](https://arxiv.org/abs/1810.04805).
 * ClinicalBERT-经过临床训练的两种语言模型具有相似的名称.  两者都是根据MIMIC-III数据集的临床笔记文本进行训练的BERT模型.
  * [Alsentzer et al Clinical BERT](https://github.com/EmilyAlsentzer/clinicalBERT) - [paper](https://www.aclweb.org/anthology/W19-1909/)
  * [Huang et al ClinicalBERT](https://github.com/kexinhuang12345/clinicalBERT) - [paper](https://arxiv.org/abs/1904.05342)
* [Flair embeddings from PubMed](https://github.com/zalandoresearch/flair/pull/519)  -通过Flair框架和嵌入方法可用的语言模型.  到2015年为止，对5％的PubMed摘要样本进行了培训，或总计超过120万个摘要.
* [SciBERT](https://github.com/allenai/scibert) - [paper](https://arxiv.org/abs/1903.10676) -BERT模型，使用来自语义学者数据库的&gt; 1M篇论文进行训练.


## Datasets

下面列出的一些数据集需要 [UMLS Terminology Services (UTS) account](https://www.nlm.nih.gov/databases/umls.html#license_request)  访问.  请注意，通过UTS帐户授予的许可要求用户提交有关其UMLS资源使用情况的年度报告.  这没有听起来那么具有挑战性.

### Biomedical Text Sources

以下资源包含生物医学科学中的索引文本文件.
* [OHSUMED](http://davis.wpi.edu/xmdv/datasets/ohsumed.html) - [paper](https://dl.acm.org/citation.cfm?id=188557)  -1987年至1991年之间的348,566条MEDLINE条目（标题有时有时是摘要）.包括MeSH标签.  主要具有历史意义.
* [PubMed Central Open Access Subset](https://www.ncbi.nlm.nih.gov/pmc/tools/openftlist/)  -一套PubMed Central文章，可根据传统版权以外的许可使用，尽管确切的许可因出版物和来源而异.  文章以PDF和XML的形式提供.
* [CORD-19](https://pages.semanticscholar.org/coronavirus-research)  -有关COVID-19的学术手稿集.  文章主要来自PubMed Central和预印本服务器，尽管该文章集还包含纸张上的元数据，但没有全文本.

### Annotated Text Data

* [SPL-ADR-200db](https://bionlp.nlm.nih.gov/tac2017adversereactions/) - [paper](https://www.nature.com/articles/sdata20181) -包含标准化信息和文本注释的试验性数据集，涉及200种FDA批准的药物的约5,000种已知不良反应.
* [BioCreAtIvE 1](https://sourceforge.net/projects/biocreative/files/) - [paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-6-S1-S1)  -15,000个句子（10,000个培训和5,000个测试）带有蛋白质和基因名称的注释.  1,000篇全文的生物医学研究文章，带有蛋白质名称和基因本体论术语.
* [BioCreAtIvE 2](https://sourceforge.net/projects/biocreative/files/) - [paper](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2008-9-s2-s1)  -标注蛋白质和基因名称的15,000个句子（10,000个训练和5,000个测试，与第一个语料不同）.  542个链接到EntrezGene标识符的摘要.  各种研究文章都注有蛋白质与蛋白质相互作用的特征.
* [BioCreAtIvE V CDR Task Corpus (BC5CDR)](https://biocreative.bioinformatics.udel.edu/accounts/login/?next=/resources/corpora/biocreative-v-cdr-corpus/) - [paper](https://academic.oup.com/database/article/doi/10.1093/database/baw068/2630414)  -2014年或以后发表的1,500篇文章（标题和摘要）被注释了4,409种化学物质，5,818种疾病和3116种化学-疾病相互作用.  需要注册.
* [BioCreative VI CHEMPROT Corpus](https://biocreative.bioinformatics.udel.edu/resources/corpora/chemprot-corpus-biocreative-vi/#chemprot-corpus-biocreative-vi:downloads) - [paper](https://pdfs.semanticscholar.org/eed7/81f498b563df5a9e8a241c67d63dd1d92ad5.pdf)  -&gt; 2,400篇文章，注明了各种关系类型的化学-蛋白质相互作用.  需要注册.
* [CRAFT](https://github.com/UCDenver-ccp/CRAFT) - [paper](https://link.springer.com/chapter/10.1007/978-94-024-0881-2_53)  -67篇全文的生物医学文章，以各种方式注释，包括概念和共同引用.  现在是版本3.
* [n2c2 (formerly i2b2) Data](https://portal.dbmi.hms.harvard.edu/projects/n2c2-nlp/)  -哈佛医学院的生物医学信息学系（DBMI）管理着全国NLP临床挑战赛和整合生物学信息学以及床边挑战赛自2006年以来开始的数据.在访问和使用之前，它们需要进行注册.  数据集包括各种主题.  看到 [list of data challenges](https://portal.dbmi.hms.harvard.edu/data-challenges/) 用于个人说明.
* [NCBI Disease Corpus](https://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/) - [paper](https://www.sciencedirect.com/science/article/pii/S1532046413001974) -793种生物医学摘要的语料库，标有疾病名称和MeSH和 [OMIM](https://omim.org/).
* [PubTator Central datasets](https://www.ncbi.nlm.nih.gov/research/pubtator/) - [paper](https://academic.oup.com/nar/article/47/W1/W587/5494727)  -可通过RESTful API或FTP下载进行访问.  包括对超过2900万份摘要和300万份全文文档的注释.
* [Word Sense Disambiguation (WSD)](https://wsd.nlm.nih.gov/) - [paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-223)  -203个歧义词和37,888个自动提取的词在生物医学研究出版物中的使用实例.  需要UTS帐户.

### Protein-protein Interaction Annotated Corpora
 蛋白间相互作用简称为PPI.  以下几组可用 [BioC format](http://bioc.sourceforge.net/) .  较旧的设置（AIMed，BioInfer，HPRD50，IEPA和LLL）由以下公司提供： [WBI corpora repository](http://corpora.informatik.hu-berlin.de) 最初是由 [group at Turku University](http://mars.cs.utu.fi/PPICorpora/).

* [AIMed](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/aimed_bioc.xml.zip) - [paper](https://www.ncbi.nlm.nih.gov/pubmed/15811782) -225条MEDLINE摘要为PPI注释.
* [BioC-BioGRID](http://bioc.sourceforge.net/BioC-BioGRID.html) - [paper](https://academic.oup.com/database/article/doi/10.1093/database/baw147/2884890)  -120篇全文文章，注明PPI和遗传相互作用.  在BioCreative V BioC任务中使用.
* [BioInfer](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/bioinfer_bioc.xml.zip) - [paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-8-50) -来自生物医学研究摘要的1,100句话，标有关系（包括PPI），命名实体和句法依存关系的注释. [Additional information and download links are here.](http://mars.cs.utu.fi/BioInfer/)
* [HPRD50](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/hprd50_bioc.xml.zip) - [paper](https://academic.oup.com/bioinformatics/article/23/3/365/236564) -人蛋白质参考数据库参考的50篇科学摘要，标注了PPI.
* [IEPA](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/iepa_bioc.xml.zip) - [paper](http://psb.stanford.edu/psb-online/proceedings/psb02/abstracts/p326.html) -从生物医学研究摘要中提取的486句注释了共生化学物质对，包括蛋白质（因此，PPI注释）.
* [LLL](http://corpora.informatik.hu-berlin.de/corpora/brat2bioc/lll_bioc.xml.zip) - [paper](https://www.semanticscholar.org/paper/Learning-Language-in-Logic-Genic-Interaction-Nedellec/0863a9d71955341b7e1a6a6877d44d4f0bb22671) -有关枯草芽孢杆菌细菌的研究文章中的77个句子，注释了蛋白质与基因的相互作用（因此，与PPI注释相当接近）. [Additional information is here.](http://genome.jouy.inra.fr/texte/LLLchallenge/#task1)

### Other Datasets

* [Columbia Open Health Data](http://cohd.io) - [paper](https://www.nature.com/articles/sdata2018273)  -从电子健康记录中提取的疾病，药物，程序和患者人口统计的患病率和共现频率的数据库.  不包括原始记录文本.
* [Comparative Toxicogenomics Database](https://ctdbase.org/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6323936/)  -化学，基因产物，表型，疾病和环境暴露之间的人工策划关联数据库.  可用于组装相关概念的本体，例如化学品的类型.
* [MIMIC-III](https://mimic.physionet.org/) - [paper](https://www.nature.com/articles/sdata201635)  -来自约60,000个重症监护病房入院的不确定健康数据.  需要完成在线培训课程（CITI培训）并在使用前接受数据使用协议.


## Ontologies and Controlled Vocabularies

* [Disease Ontology](http://www.disease-ontology.org/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4383880/)  -人类疾病的本体.  具有到MeSH，ICD，NCI词库，SNOMED和OMIM的交叉链接.  公共区域.  适用于 [GitHub](https://github.com/DiseaseOntology/HumanDiseaseOntology) 并在 [OBO Foundry](http://www.obofoundry.org/ontology/doid.html).
* [RxNorm](https://www.nlm.nih.gov/research/umls/rxnorm/index.html) - [paper](https://academic.oup.com/jamia/article/18/4/441/734170)  -临床药物和药品包装的标准化名称，包括成分，强度和形式的组合，以及语义网络中分配的类型（请参见下文）.  每月发布.
* [SPECIALIST Lexicon](https://lexsrv3.nlm.nih.gov/Specialist/Summary/lexicon.html) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2247735/)  -包含许多生物医学术语的通用英语词典.  自1994年以来每年进行更新，到2019年仍进行更新.UMLS的一部分，但不需要下载UTS帐户.
* [UMLS Metathesaurus](https://www.nlm.nih.gov/research/umls/knowledge_sources/metathesaurus/index.html) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC308795/)  -超过380万个概念，1400万个概念名称以及200多种生物医学词汇和标识符来源之间的映射.  好大  这可能有助于准备带有 [MetamorphoSys installation tool](https://www.nlm.nih.gov/research/umls/implementation_resources/metamorphosys/help.html) 但我们仍在谈论2019年版本所需的〜30 Gb磁盘空间. [See the manual here](https://www.ncbi.nlm.nih.gov/books/NBK9684/) .  需要UTS帐户.
* [UMLS Semantic Network](https://semanticnetwork.nlm.nih.gov/) - [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2447396/)  -涵盖生物医学概念和词汇的133种语义类型和54种语义关系的列表.  Metathesaurus是否太复杂，无法满足您的需求？  尝试这个.  不需要UTS帐户下载.


## Data Models

你需要一个 [data model](https://en.wikipedia.org/wiki/Data_model) ？  如果您正在使用生物医学数据，那么答案可能是“是”.

* [Biolink](https://biolink.github.io/biolink-model/) - [code](https://github.com/biolink/biolink-model)  -生物实体的数据模型.  作为一个 [YAML](https://yaml.org/) 文件.
* [BioUML](http://wiki.biouml.org/index.php/BioUML) - [paper](https://academic.oup.com/nar/article/47/W1/W225/5498754)  -用于生物医学数据分析，集成和可视化的体系结构.  概念上基于视觉建模语言 [UML](https://www.uml.org/what-is-uml.htm).
* [OMOP Common Data Model](https://github.com/OHDSI/CommonDataModel) -观察保健数据的标准.


## Credits

[Credits](https://github.com/caufieldjh/awesome-bioie/blob/master/./CREDITS.md) 用于策展人和资源.

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

[License](https://github.com/caufieldjh/awesome-bioie/blob/master/./LICENSE)
