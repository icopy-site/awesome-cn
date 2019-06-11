<div class="github-widget" data-repo="seriousmac/awesome-qa"></div>
## Awesome Question Answering [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) 

_A的精选清单 __[Question Answering (QA)](https://en.wikipedia.org/wiki/Question_answering)__科目是信息检索和自然语言处理（NLP）领域的计算机科学学科，用于机器学习和深度学习_

_信息检索和自然语言处理问答的策展 - 机器学习和深度学习_ <br/>
_问答系统主题的精选列表，是信息检索和自然语言处理领域的计算机科学学科 - 使用机器学习和深度学习_


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Recent Trend, BERT
### BERT
- 原纸
  - [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)，Jacob Devlin，et al.，arXiv preprint，2018.
- 质量保证
  - [SDNet: Contextualized Attention-based Deep Network for Conversational Question Answering](https://arxiv.org/abs/1812.03593), Chenguang Zhu, et al., arXiv, Dec 2018.
  - [A BERT Baseline for the Natural Questions](https://arxiv.org/abs/1901.08634)克里斯·阿尔贝蒂，等人的arXiv预印本2019年1月.
  - [Passage Re-ranking with BERT](https://arxiv.org/abs/1901.04085)，Rodrigo Nogueira，et al.，ArXiv preprint，2019年1月.
  - [End-to-End Open-Domain Question Answering with BERTserini](https://arxiv.org/abs/1902.01718)，Wei Yang，et al.，ArXiv preprint，2019年2月.
  - [Understanding the Behaviors of BERT in Ranking](https://arxiv.org/abs/1904.07531), Yifan Qiao, et al., arXiv preprint, Apr 2019.
  - [BERT Post-Training for Review Reading Comprehension and Aspect-based Sentiment Analysis](https://arxiv.org/abs/1904.02232)，Hu Xu，et al.，ArXiv preprint，Apr 2019.
  - [Investigating the Successes and Failures of BERT for Passage Re-Ranking](https://arxiv.org/abs/1905.01758)，Harshith Padigela，et al.，ArXiv preprint，2019年5月.
  - [BERT with History Answer Embedding for Conversational Question Answering](https://arxiv.org/abs/1905.05412)，Chen Qu，et al.，arXiv preprint，2019年5月.
  
## About QA
### Types of QA
- 单转QA：在不考虑任何背景的情况下回答
- 会话质量保证：使用前所未有的对话轮流
#### Subtypes of QA
- 基于知识的质量保证
- 基于表/列表的QA
- 基于文本的质量保证
- 基于社区的质量保证
- 视觉质量保证

### Analysis and Parsing for Pre-processing in QA systems
Lanugage分析
  1. [Morphological analysis](https://www.cs.bham.ac.uk/~pjh/sem1a5/pt2/pt2_intro_morphology.html)
  2. [Named Entity Recognition(NER)](https://github.com/seriousmac/awesome-qa/blob/master/mds/named-entity-recognition.md)
  3.同音异义词/一词多义分析
  4.语法分析（依赖性分析）
  5.语义识别

### Most QA systems have roughly 3 parts
1.事实提取<br/>
    1.实体提取<br/>
        1. [Named-Entity Recognition(NER)](https://github.com/seriousmac/awesome-qa/blob/master/mds/named-entity-recognition.md)
    2. [Relation Extraction](https://github.com/seriousmac/awesome-qa/blob/master/mds/relation-extraction.md) <br/>
2.理解这个问题
3.产生答案

## Events
-  Wolfram Alpha在2009年推出了答案引擎.
-  IBM Watson系统击败顶级*[Jeopardy!](https://www.jeopardy.com)* 2011年的冠军.
-  Apple的Siri在2011年集成了Wolfram Alpha的应答引擎.
- 谷歌通过推出知识图来接受质量保证，利用2012年的免费基础知识库.
  -  Amazon Echo |  Alexa（2015），Google Home |  Google智能助理（2016），INVOKE |  MS Cortana（2017），HomePod（2017）

## Systems
- [IBM Watson](https://www.ibm.com/watson/) - 具有最先进的表现. 
- [Facebook DrQA](https://research.fb.com/downloads/drqa/)   - 应用于SQuAD1.0数据集.  SQuAD2.0数据集已经发布.  但DrQA尚未测试.
- [MIT media lab's Knowledge graph](http://conceptnet.io/) - 是一个免费提供的语义网络，旨在帮助计算机理解人们使用的单词的含义.

## Competitions in QA

 |  |  数据集|  语言|  组织者|  自|  最高排名|  型号|  状态|  过度人性化|
|---|------------------|---------------|---------------------|-------|-------------------------|-------------------------|--------|------------------------|
| 0 | [Story Cloze Test](http://cs.rochester.edu/~nasrinm/files/Papers/lsdsem17-shared-task.pdf)  |  英语|  大学.  罗切斯特|  2016 |  msap |  逻辑回归|  关闭|  x |
 |  1 |  MS MARCO |  英语|  微软|  2016 |  NLP研究NLP |  MARK |  关闭|  
 |  2 |  MS MARCO V2 |  英语|  微软|  2018年|  NTT Media Intelli.  实验室.  |  面膜问答风格|  打开|  x |
| 3 | [SQuAD](https://arxiv.org/abs/1606.05250)             |  英语|  大学.  斯坦福大学|  2018年|  XLNet（单一型号）| XLNet团队|  关闭|  o |
| 4 | [SQuAD 2.0](https://rajpurkar.github.io/SQuAD-explorer/)         |  英语|  大学.  斯坦福大学|  2018年|  HIT与iFLYTEK研究联合实验室|  BERT + DAE + AoA（合奏）|  打开|  o |
| 5 | [TriviaQA](http://nlp.cs.washington.edu/triviaqa/)          |  英语|  大学.  华盛顿|  2017年|  明燕|   -  |  关闭|   -  |
| 6 | [decaNLP](https://decanlp.com/)           |  英语|  Salesforce Research |  2018年|  Salesforce Research |  MQAN |  关闭|  x |
| 7 | [DuReader Ver1.](https://ai.baidu.com/broad/introduction)           |  中文|  百度|  2015年|  尝试者|  T-Reader（单曲）|  关闭|  x |
| 8 | [DuReader Ver2.](https://ai.baidu.com/broad/introduction)           |  中文|  百度|  2017年|  文艺复兴|  AliReader |  打开|  x |
| 9 | [KorQuAD](https://korquad.github.io/)     |  韩语|  LG CNS AI研究|  2018年|  Kakao NLP团队|  BERT LM微调（单）+ KHAIII |  关闭|  o |
| 10 | [CoQA](https://stanfordnlp.github.io/coqa/)     |  英语|  大学.  斯坦福大学|  2018年|  MSRA + SDRG |  Google SQuAD 2.0 + MMFT（合奏）|  打开|  o |

## Publications
- 论文
  - ["Learning to Skim Text"](https://arxiv.org/pdf/1704.06877.pdf), Adams Wei Yu, Hongrae Lee, Quoc V. Le, 2017.
    ：在文本中仅显示您想要的内容
  - ["Deep Joint Entity Disambiguation with Local Neural Attention"](https://arxiv.org/pdf/1704.04920.pdf)，Octavian-Eugen Ganea和Thomas Hofmann，2017年.
  - ["BI-DIRECTIONAL ATTENTION FLOW FOR MACHINE COMPREHENSION"](https://arxiv.org/pdf/1611.01603.pdf)，Minjoon Seo，Aniruddha Kembhavi，Ali Farhadi，Hananneh Hajishirzi，ICLR，2017.
  - ["Capturing Semantic Similarity for Entity Linking with Convolutional Neural Networks"](http://nlp.cs.berkeley.edu/pubs/FrancisLandau-Durrett-Klein_2016_EntityConvnets_paper.pdf)，Matthew Francis-Landau，Greg Durrett和Dan Klei，NAACL-HLT 2016.
    - https://GitHub.com/matthewfl/nlp-entity-convnet
  - ["Entity Linking with a Knowledge Base: Issues, Techniques, and Solutions"](https://ieeexplore.ieee.org/document/6823700/), Wei Shen, Jianyong Wang, Jiawei Han, IEEE Transactions on Knowledge and Data Engineering(TKDE), 2014.
  - ["Introduction to “This is Watson"](https://ieeexplore.ieee.org/document/6177724/)，IBM Journal of Research and Development，DA Ferrucci，2012.
  - ["A survey on question answering technology from an information retrieval perspective"](https://www.sciencedirect.com/science/article/pii/S0020025511003860)，信息科学，2011.
  - ["Question Answering in Restricted Domains: An Overview"](https://www.mitpressjournals.org/doi/abs/10.1162/coli.2007.33.1.41)，DiegoMollá和JoséLuisVicedo，计算语言学，2007年
  -  [“自然语言问答：这里的观点”]（），L Hirschman，R Gaizauskas，自然语言工程，2001.
  - 实体消歧/实体链接

## Codes
- [BiDAF](https://github.com/allenai/bi-att-flow) - 双向注意流（BIDAF）网络是一个多阶段分层过程，它表示不同粒度级别的上下文，并使用双向注意流机制来获得查询感知上下文表示而无需提前汇总. 
    - 官方;  Tensorflow v1.2
  - [Paper](https://arxiv.org/pdf/1611.01603.pdf)
- [QANet](https://github.com/NLPLearn/QANet) -  Q＆A架构不需要循环网络：其编码器仅由卷积和自我关注组成，其中卷积模型本地交互和自我关注模拟全局交互.
   - 谷歌;  非官方;  Tensorflow v1.5
- [R-Net](https://github.com/HKUST-KnowComp/R-Net) - 用于阅读理解风格问答的端到端神经网络模型，旨在回答特定段落的问题.
   - 女士;  香港科技大学非正式;  Tensorflow v1.5
  - [Paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/r-net.pdf)
- [R-Net-in-Keras](https://github.com/YerevaNN/R-NET-in-Keras) - 在Keras重新实施R-NET.
   - 女士;  非官方;  Keras v2.0.6
  - [Paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/r-net.pdf)
- [DrQA](https://github.com/hitvoice/DrQA) -  DrQA是一个应用于开放域问答的阅读理解系统.
    -  Facebook;  官方;  Pytorch v0.4
- [BERT](https://github.com/google-research/bert)   - 一种新的语言表示模型，代表变形金刚的双向编码器表示.  与最近的语言表示模型不同，BERT旨在通过联合调节所有层中的左右上下文来预训练深度双向表示. 
   - 谷歌;  正式实施;  Tensorflow v1.11.0
  - [Paper](https://arxiv.org/abs/1810.04805)

## Lectures
- [Question Answering - Natural Language Processing](https://youtu.be/Kzi6tE4JaGo)   - 由Dragomir Radev，博士.  |  密歇根大学|  2016年

## Slides
- [Question Answering with Knowledge Bases, Web and Beyond](https://github.com/scottyih/Slides/blob/master/QA%20Tutorial.pdf)   - 作者：Scott Wen-ans Yih＆Hao Ma |  微软研究院|  2016年
- [Question Answering](https://hpi.de/fileadmin/user_upload/fachgebiete/plattner/teaching/NaturalLanguageProcessing/NLP2017/NLP8_QuestionAnswering.pdf)   - 博士  玛丽安娜内维斯|  哈索普拉特纳研究所|  第二千〇十七

## Dataset Collections
- [NLIWOD's Question answering datasets](https://github.com/dice-group/NLIWOD/tree/master/qa.datasets)
- [karthinkncode's Datasets for Natural Language Processing](https://github.com/karthikncode/nlp-datasets)

## Datasets
- [AI2 Science Questions v2.1(2017)](http://data.allenai.org/ai2-science-questions/)
    - 它包括在美国小学和中学年级的学生评估中使用的问题.  每个问题都是4路多选格式，可能包含也可能不包含图表元素.
  - 论文：http：//ai2-website.s3.amazonaws.com/publications/AI2ReasoningChallenge2018.pdf
- [Children's Book Test](https://uclmr.github.io/ai4exams/data.html)
  - 它是Facebook AI Research的bAbI项目之一，旨在实现自动文本理解和推理的目标.  CBT旨在直接衡量语言模型如何利用更广泛的语言环境.
- [DeepMind Q&A Dataset; CNN/Daily Mail](https://github.com/deepmind/rc-data)
    - 赫尔曼等人.  （2015）使用新闻文章创建了两个很棒的数据集，用于问答研究.  每个数据集包含许多文档（每个文档分别为90k和197k），每个文档公司平均有4个问题.  每个问题都是一个带有一个缺失单词/短语的句子，可以从随附的文档/上下文中找到.
  - 论文：https：//arxiv.org/abs/1506.03340
- [GraphQuestions](https://github.com/ysu1989/GraphQuestions)
  - 为QA评估生成特征丰富的问题​​集.
- [LC-QuAD](http://sda.cs.uni-bonn.de/projects/qa-dataset/)
    - 这是一个包含5000个问题和SPARQL查询的黄金标准KBQA（问题回答知识库）数据集.  LC-QuAD使用DBpedia v04.16作为目标KB.
- [MS MARCO](http://www.msmarco.org/dataset.aspx)
  - 这是用于真实世界的问答.
  - 论文：https：//arxiv.org/abs/1611.09268
- [MultiRC](https://cogcomp.org/multirc/)
  - 短段和多句话题的数据集
  - Paper: http://cogcomp.org/page/publication_view/833 
- [NarrativeQA](https://github.com/deepmind/narrativeqa)
  - 它包括维基百科摘要的文档列表，完整故事的链接以及问题和答案.
  - 论文：https：//arxiv.org/pdf/1712.07040v1.pdf
- [NewsQA](https://github.com/Maluuba/newsqa)
  - 机器理解数据集
  - 论文：https：//arxiv.org/pdf/1611.09830.pdf
- [Qestion-Answer Dataset by CMU](http://www.cs.cmu.edu/~ark/QA-data/)
  - This is a corpus of Wikipedia articles, manually-generated factoid questions from them, and manually-generated answers to these questions, for use in academic research. These data were collected by Noah Smith, Michael Heilman, Rebecca Hwa, Shay Cohen, Kevin Gimpel, and many students at Carnegie Mellon University and the University of Pittsburgh between 2008 and 2010.
- [SQuAD1.0](https://rajpurkar.github.io/SQuAD-explorer/)
  - 斯坦福问答数据集（SQUAD）是一个阅读理解数据集，由群体工作者在一组维基百科文章中提出的问题组成，其中每个问题的答案是来自相应阅读段落的文本或跨度的一部分，或者问题可能无法回答.
  - 论文：https：//arxiv.org/abs/1606.05250
- [SQuAD2.0](https://rajpurkar.github.io/SQuAD-explorer/)
    -  SQuAD2.0将SQuAD1.1中的100,000个问题与群众工作者反对写的类似于可回答的问题的50,000多个新的无法回答的问题结合起来.  为了在SQuAD2.0上做得好，系统不仅要在可能的情况下回答问题，还要确定段落何时不支持答案并且不回答问题.
  - 论文：https：//arxiv.org/abs/1806.03822
- [Story cloze test](http://cs.rochester.edu/nlp/rocstories/)
    - “Story Cloze Test”是一个新的常识推理框架，用于评估故事理解，故事生成和脚本学习.  此测试需要系统选择四句话故事的正确结尾.
  - 论文：https：//arxiv.org/abs/1604.01696
- [TriviaQA](http://nlp.cs.washington.edu/triviaqa/)
    -  TriviaQA是一个阅读理解数据集，包含超过650K的问答 - 证据三元组.  TriviaQA包括由琐事爱好者撰写的95K问答对，并独立收集证据文件，平均每个问题六个，为回答问题提供高质量的远程监督. 
  - 论文：https：//arxiv.org/abs/1705.03551
- [WikiQA](https://www.microsoft.com/en-us/download/details.aspx?id=52419&from=https%3A%2F%2Fresearch.microsoft.com%2Fen-US%2Fdownloads%2F4495da01-db8c-4041-a7f6-7984a4f6a905%2Fdefault.aspx)
  - 一组公开可用的问题和句子对，用于开放域名问答.
  
### The DeepQA Research Team in IBM Watson's publication within 5 years
- 2015
  - “IBM Watson电子医疗记录自动生成问题列表”，Murthy Devarakonda，2015年IAAI的Ching-Huei Tsou.
  - “IBM Watson Question Answering中的决策”，J.William Murdock，Ontology summit，2015.
  - ["Unsupervised Entity-Relation Analysis in IBM Watson"](http://www.cogsys.org/papers/ACS2015/article12.pdf)，Aditya Kalyanpur，J William Murdock，ACS，2015年.
  - “常识推理：基于事件微积分的方法”，ET Mueller，Morgan Kaufmann / Elsevier，2015.
- 2014
  - “以问题为导向的患者记录摘要：关于Watson应用程序的早期报告”，M.Devarakonda，张东阳，Tsing-Huei Tsou，M.Bornea，Healthcom，2014.
  - ["WatsonPaths: Scenario-based Question Answering and Inference over Unstructured Information"](http://domino.watson.ibm.com/library/Cyberdig.nsf/1e4115aea78b6e7c85256b360066f0d4/088f74984a07645485257d5f006ace96!OpenDocument&Highlight=0,RC25489)，Adam Lally，Sugato Bachi，Michael A. Barborak，David W. Buchanan，Jennifer Chu-Carroll，David A. Ferrucci *，Michael R. Glass，Aditya Kalyanpur，Erik T. Mueller，J.William Murdock，Siddharth Patwardhan，John M. Prager，Christopher A. Welty，IBM研究报告RC25489,2014.
  - ["Medical Relation Extraction with Manifold Models"](http://acl2014.org/acl2014/P14-1/pdf/P14-1078.pdf)，Chang Wang和James Fan，ACL，2014.

### MS Research's publication within 5 years
- 2018
  - “人与人交流中的表征和支持问题回答”，小杨，Ahmed Hassan Awadallah，Madian Khabsa，Wei Wang，Miaosen Wang，ACM SIGIR，2018.
  - ["FigureQA: An Annotated Figure Dataset for Visual Reasoning"](https://arxiv.org/abs/1710.07300)，Samira Ebrahimi Kahou，Vincent Michalski，Adam Atkinson，Kadar，Adam Trischler，Yoshua Bengio，ICLR，2018
- 2017
  - "Multi-level Attention Networks for Visual Question Answering", Dongfei Yu, Jianlong Fu, Tao Mei, Yong Rui, CVPR, 2017.
  - “问答和问题产生的联合模型”，王彤，Xingdi（Eric）Yuan，Adam Trischler，ICML，2017.
  - “机器理解中转移学习的两阶段综合网络”，David Golub，黄宝森，何晓东，李登，EMNLP，2017.
  - “问题 - 用语法解释的表达方式回答”，Hamid Palangi，Paul Smolensky，何晓东，李登， 
  - “基于搜索的顺序问题回答的神经结构学习”，Mohit Iyyer，Wen-tau Yih，Chang-Wei Chang，ACL，2017.
- 2016
  - ["Stacked Attention Networks for Image Question Answering"](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Yang_Stacked_Attention_Networks_CVPR_2016_paper.html), Zichao Yang, Xiaodong He, Jianfeng Gao, Li Deng, Alex Smola, CVPR, 2016.
  - ["Question Answering with Knowledge Base, Web and Beyond"](https://www.microsoft.com/en-us/research/publication/question-answering-with-knowledge-base-web-and-beyond/)，Yih，Scott Wen-tau和Ma，Hao，ACM SIGIR，2016.
  - ["NewsQA: A Machine Comprehension Dataset"](https://arxiv.org/abs/1611.09830)，Adam Trischler，Tong Wang，Xingdi Yuan，Justin Harris，Alessandro Sordoni，Philip Bachman，Kaheer Suleman，RepL4NLP，2016.
  - ["Table Cell Search for Question Answering"](https://dl.acm.org/citation.cfm?id=2883080), Sun, Huan and Ma, Hao and He, Xiaodong and Yih, Wen-tau and Su, Yu and Yan, Xifeng, WWW, 2016.
- 2015
  - ["WIKIQA: A Challenge Dataset for Open-Domain Question Answering"](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/YangYihMeek_EMNLP-15_WikiQA.pdf)，Yi Yang，Wen-tau Yih和Christopher Meek，EMNLP，2015.
  - ["Web-based Question Answering: Revisiting AskMSR"](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/AskMSRPlusTR_082815.pdf)，Chen-Tse Tsai，Wen-tau Yih和Christopher JC Burges，MSR-TR，2015.
  - ["Open Domain Question Answering via Semantic Enrichment"](https://dl.acm.org/citation.cfm?id=2741651), Huan Sun, Hao Ma, Wen-tau Yih, Chen-Tse Tsai, Jingjing Liu, and Ming-Wei Chang, WWW, 2015.
- 2014
  - ["An Overview of Microsoft Deep QA System on Stanford WebQuestions Benchmark"](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/Microsoft20Deep20QA.pdf), Zhenghao Wang, Shengquan Yan, Huaming Wang, and Xuedong Huang, MSR-TR, 2014.
  -  [“单关系问答的语义解析”]（），Wen-tau Yih，何晓东，Christopher Meek，ACL，2014.
  
### Google AI's publication within 5 years
- 2018
  -  Google QA <a name="qanet"></a>
    - ["QANet: Combining Local Convolution with Global Self-Attention for Reading Comprehension"](https://openreview.net/pdf?id=B14TlG-RW)，Adams Wei Yu，David Dohan，Minh-Thang Luong，Rui Zhao，Kai Chen，Mohammad Norouzi，Quoc V. Le，ICLR，2018.
    - ["Ask the Right Questions: Active Question Reformulation with Reinforcement Learning"](https://openreview.net/pdf?id=S1CChZ-CZ)，Christian Buck和Jannis Bulian和Massimiliano Ciaramita和WojciechPawełGajewski以及Andrea Gesmundo和Neil Houlsby以及Wei Wang，ICLR，2018.
    - ["Building Large Machine Reading-Comprehension Datasets using Paragraph Vectors"](https://arxiv.org/pdf/1612.04342.pdf)，Radu Soricut，Nan Ding，2018.
  - 句子代表
    - ["An efficient framework for learning sentence representations"](https://arxiv.org/pdf/1803.02893.pdf)，Lajanugen Logeswaran，Honglak Lee，ICLR，2018.
  - ["Did the model understand the question?"](https://arxiv.org/pdf/1805.05492.pdf)，Pramod K. Mudrakarta和Ankur Taly和Mukund Sundararajan以及K​​edar Dhhamdhere，ACL，2018年.
- 2017
  - ["Analyzing Language Learned by an Active Question Answering Agent"](https://arxiv.org/pdf/1801.07537.pdf)，Christian Buck和Jannis Bulian以及Massimiliano Ciaramita和Wojciech Gajewski以及Andrea Gesmundo和Neil Houlsby以及Wei Wang，NIPS，2017.
  - ["Learning Recurrent Span Representations for Extractive Question Answering"](https://arxiv.org/pdf/1611.01436.pdf)，Kenton Lee和Shimi Salant以及Tom Kwiatkowski和Ankur Parikh以及Dipanjan Das和Jonathan Berant，ICLR，2017年.
  - 确定相同的问题
    - ["Neural Paraphrase Identification of Questions with Noisy Pretraining"](https://arxiv.org/pdf/1704.04565.pdf)，Gaurav Singh Tomar和Thyago Duque和OscarTäckström以及Jakob Uszkoreit和Dipa​​njan Das，SCLeM，2017年.
- 2014
  - “好问题！社区问答中的问题质量”，Sujith Ravi和Bo Pang以及Vibhor Rastogi和Ravi Kumar，ICWSM，2014.

### Facebook AI Research's publication within 5 years
- 2018
  - [Embodied Question Answering](https://research.fb.com/publications/embodied-question-answering/)，Abhishek Das，Samyak Datta，Georgia Gkioxari，Stefan Lee，Devi Parikh和Dhruv Batra，CVPR，2018
  - [Do explanations make VQA models more predictable to a human?](https://research.fb.com/publications/do-explanations-make-vqa-models-more-predictable-to-a-human/)，Arjun Chandrasekaran，Viraj Prabhu，Deshraj Yadav，Prithvijit Chattopadhyay和Devi Parikh，EMNLP，2018
  - [Neural Compositional Denotational Semantics for Question Answering](https://research.fb.com/publications/neural-compositional-denotational-semantics-for-question-answering/)，Nitish Gupta，Mike Lewis，EMNLP，2018
- 2017
  -  DrQA <a name="drqa"></a>
    - [Reading Wikipedia to Answer Open-Domain Questions](https://cs.stanford.edu/people/danqi/papers/acl2017.pdf)，Danqi Chen，Adam Fisch，Jason Weston和Antoine Bordes，ACL，2017.

## Books
- 自然语言问答系统平装 -  Boris Galitsky（2003）
- 问答的新方向 -  Mark T. Maybury（2004）
- 第3部分.5.牛津计算语言学手册中的问题答案 -  Sanda Harabagiu和Dan Moldovan（2005）
- 第28章语音和语言处理中的问题回答 -  Daniel Jurafsky和James H. Martin（2017）

## Links
- [Building a Question-Answering System from Scratch— Part 1](https://towardsdatascience.com/building-a-question-answering-system-part-1-9388aadff507)
- [Qeustion Answering with Tensorflow By Steven Hewitt, O'REILLY, 2017](https://www.oreilly.com/ideas/question-answering-with-tensorflow)
- [Why question answering is hard](http://nicklothian.com/blog/2014/09/25/why-question-answering-is-hard/)


## Contributing

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/seriousmac/awesome-qa/blob/master/contributing.md) 第一.

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/share-your-work/public-domain/cc0/)

在法律允许的范围内， [seriousmac](https://github.com/seriousmac) （维护者）已放弃对此作品的所有版权及相关或邻接权利.
