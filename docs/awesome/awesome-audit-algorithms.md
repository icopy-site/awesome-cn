<div class="github-widget" data-repo="erwanlemerrer/awesome-audit-algorithms"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Audit Algorithms [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

用于审计黑盒算法的精选算法列表.
如今，许多算法（推荐、评分、分类）都在第三方提供商处运行，而用户或机构对他们如何操作其数据没有任何见解. 因此，此列表中的审计算法适用于此设置，创造了“黑盒”设置，其中一位审计员希望对这些远程算法有一些了解.

<img src="https://raw.githubusercontent.com/erwanlemerrer/awesome-audit-algorithms/blob/main/resources/audit.png" width="600" alt="banner" class="center">

&gt; 用户查询远程算法（例如，通过可用的 API），以推断有关该算法的信息.


## Papers
### 2022
- [Two-Face: Adversarial Audit of Commercial Face Recognition Systems](https://ojs.aaai.org/index.php/ICWSM/article/view/19300/19072) -（ICWSM）*对多个系统 API 和数据集进行对抗性审计，进行一些相关观察.*
- [Scaling up search engine audits: Practical insights for algorithm auditing](https://journals.sagepub.com/doi/10.1177/01655515221093029) -（信息科学杂志） [(Code)](https://github.com/gesiscss/WebBot) *使用虚拟代理的模拟浏览行为审核多个搜索引擎.*
- [A zest of lime: towards architecture-independent model distances](https://openreview.net/pdf?id=OUz_9TiTv9j) - (ICLR) *使用 LIME 测量两个远程模型之间的距离.*
- [Active Fairness Auditing](https://proceedings.mlr.press/v162/yan22c/yan22c.pdf) -（ICML）*研究基于查询的审计算法，可以以高效查询的方式估计 ML 模型的人口统计奇偶性.*
- [Look at the Variance! Efficient Black-box Explanations with Sobol-based Sensitivity Analysis](https://proceedings.neurips.cc/paper/2021/file/da94cbeff56cfda50785df477941308b-Paper.pdf) - (NeurIPS) *Sobol 索引提供了一种有效的方法来捕获图像区域之间的高阶交互及其通过方差透镜对（黑盒）神经网络预测的贡献.*
- [Your Echos are Heard: Tracking, Profiling, and Ad Targeting in the Amazon Smart Speaker Ecosystem](https://arxiv.org/pdf/2204.10920.pdf) - (arxiv) *推断 Amazon Echo 系统和广告定位算法之间的联系.*
### 2021
- [Everyday Algorithm Auditing: Understanding the Power of Everyday Users in Surfacing Harmful Algorithmic Behaviors](https://arxiv.org/pdf/2105.02980.pdf) -（CHI）*为用户提供“日常算法审计”的理由.*
- [Auditing Black-Box Prediction Models for Data Minimization Compliance](https://www.cs.bu.edu/faculty/crovella/paper-archive/minimization-audit-Neurips21.pdf) - (NeurIPS) *使用有限数量的查询测量预测模型满足的数据最小化水平.*
- [Setting the Record Straighter on Shadow Banning](https://arxiv.org/abs/2012.05101) - (INFOCOM)  [(Code)](https://gitlab.enseeiht.fr/bmorgan/infocom-2021) *考虑了推特影子禁令的可能性（即适度黑盒算法），并衡量了几个假设的概率.*
- [Extracting Training Data from Large Language Models](https://arxiv.org/pdf/2012.07805.pdf) -（USENIX 安全）*从 GPT-2 模型的训练数据中提取逐字文本序列.*
- [FairLens: Auditing black-box clinical decision support systems](https://www.sciencedirect.com/science/article/pii/S030645732100145X?casa_token=oyjFKij269MAAAAA:w_ohScpMPNMnkDdzBqAIod5QfBgQlq5Ht9mMRSOydZpOgNG-i1yuqEmBjWN__38gOGmjNL7dVT0) -（信息处理与管理）*通过比较不同的多标签分类差异度量，提供检测和解释临床 DSS 中潜在公平性问题的管道.*
- [Auditing Algorithmic Bias on Twitter](https://dl.acm.org/doi/abs/10.1145/3447535.3462491) -（网络科学）.
- [Bayesian Algorithm Execution: Estimating Computable Properties of Black-box Functions Using Mutual Information](https://proceedings.mlr.press/v139/neiswanger21a.html) -（ICML）*预算约束和贝叶斯优化程序，用于从黑盒算法中提取属性.*
### 2020
- [Black-Box Ripper: Copying black-box models using generative evolutionary algorithms](https://proceedings.neurips.cc/paper/2020/file/e8d66338fab3727e34a9179ed8804f64-Paper.pdf) -（NeurIPS）*复制黑盒神经模型的功能，但对查询量没有限制（通过教师/学生方案和进化搜索）.*
- [Auditing radicalization pathways on YouTube](https://dl.acm.org/doi/pdf/10.1145/3351095.3372879) -（FAT*）*研究激进渠道彼此的可达性，对静态渠道推荐使用随机游走.*
- [Adversarial Model Extraction on Graph Neural Networks](https://arxiv.org/abs/1912.07721) -（AAAI 图深度学习研讨会：方法论和应用）*介绍 GNN 模型提取并为此提出初步方法.*
- [Remote Explainability faces the bouncer problem](https://rdcu.be/b6qB4) -（自然机器智能第 2 卷，第 529-539 页）  [(Code)](https://github.com/erwanlemerrer/bouncer_problem) *显示不可能（通过一个请求）或难以发现远程 AI 决策的解释.*
- [GeoDA: a geometric framework for black-box adversarial attacks](https://openaccess.thecvf.com/content_CVPR_2020/papers/Rahmati_GeoDA_A_Geometric_Framework_for_Black-Box_Adversarial_Attacks_CVPR_2020_paper.pdf) - (CVPR)  [(Code)](https://github.com/thisisalirah/GeoDA) *在纯黑盒设置（无梯度，仅推断类）中制作对抗性示例来愚弄模型.*
- [The Imitation Game: Algorithm Selectionby Exploiting Black-Box Recommender](https://github.com/erwanlemerrer/erwanlemerrer.github.io/raw/master/files/imitation_blackbox_recommenders_netys-2020.pdf) - (Netys)  [(Code)](https://github.com/gdamaskinos/RecRank) *通过模仿远程和训练有素的算法的决策来参数化本地推荐算法.*
- [Auditing News Curation Systems:A Case Study Examining Algorithmic and Editorial Logic in Apple News](https://ojs.aaai.org/index.php/ICWSM/article/view/7277) - (ICWSM) *Apple News 的审计研究作为社会技术新闻管理系统（趋势故事部分）.*
- [Auditing Algorithms:  On Lessons Learned and the Risks of DataMinimization](https://dl.acm.org/doi/pdf/10.1145/3375627.3375852) - (AIES) *对 Telefónica 开发的健康推荐应用程序的实际审核（主要是基于偏见）.*
- [Extracting Training Data from Large Language Models](https://arxiv.org/pdf/2012.07805) - (arxiv) *通过查询语言模型执行训练数据提取攻击以恢复单个训练示例.*
### 2019
- [Adversarial Frontier Stitching for Remote Neural Network Watermarking](https://arxiv.org/abs/1711.01894) - (神经计算与应用) [(Alternative implementation)](https://github.com/dunky11/adversarial-frontier-stitching) *检查远程机器学习模型是否“泄露”：通过对远程模型的标准 API 请求，提取（或不提取）零位水印，该水印被插入到水印有价值的模型（例如，大型深度神经网络）中.*
- [Knockoff Nets: Stealing Functionality of Black-Box Models](https://arxiv.org/abs/1812.02766.pdf) -（CVPR）*询问对手可以在多大程度上仅基于黑盒交互窃取此类“受害者”模型的功能：图像输入，预测输出.*
- [Opening Up the Black Box:Auditing Google's Top Stories Algorithm](https://par.nsf.gov/servlets/purl/10101277) - (Flairs-32) * 对 Google 的热门故事面板的审计，该面板提供了对其用于选择和排名新闻发布者的算法选择的见解 *
- [Making targeted black-box evasion attacks effective andefficient](https://arxiv.org/pdf/1906.03397.pdf) -（arXiv）*研究对手如何最佳地使用其查询预算来针对深度神经网络进行有针对性的规避攻击.*
- [Online Learning for Measuring Incentive Compatibility in Ad Auctions](https://research.fb.com/wp-content/uploads/2019/05/Online-Learning-for-Measuring-Incentive-Compatibility-in-Ad-Auctions.pdf) -（WWW）*衡量黑盒拍卖平台的激励兼容（IC）机制（遗憾）.* 
- [TamperNN: Efficient Tampering Detection of Deployed Neural Nets](https://arxiv.org/abs/1903.00317) -（ISSRE）*制作输入的算法可以检测远程执行的分类器模型的篡改.*
- [Neural Network Model Extraction Attacks in Edge Devicesby Hearing Architectural Hints](https://arxiv.org/pdf/1903.03916.pdf) - (arxiv) *通过bus snooping获取内存访问事件，通过LSTM-CTC模型识别层序，根据内存访问模式进行层拓扑连接，数据量约束下的层维度估计，证明可以准确恢复与攻击起点相似的网络架构*
- [Stealing Knowledge from Protected Deep Neural Networks Using Composite Unlabeled Data](https://ieeexplore.ieee.org/abstract/document/8851798) -（ICNN）*可用于攻击和提取黑盒模型知识的复合方法，即使它完全隐藏了其 softmax 输出.*
- [Neural Network Inversion in Adversarial Setting via Background Knowledge Alignment](https://dl.acm.org/citation.cfm?id=3354261)  - (CCS) * 对手设置中的模型反演方法基于训练一个反演模型，该反演模型充当原始模型的反演. 在不完全了解原始训练数据的情况下，通过在从更通用的数据分布中抽取的辅助样本上训练反演模型，仍然可以进行准确的反演. *
### 2018
- [Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR](https://arxiv.org/abs/1711.00399) - (Harvard Journal of Law &amp; Technology) *为了解释关于 x 的决定，找到一个事实：最接近 x 的点改变了决定.*
- [Distill-and-Compare: Auditing Black-Box Models Using Transparent Model Distillation](https://arxiv.org/abs/1710.06169) -（AIES）*将黑盒模型视为教师，训练透明的学生模型以模仿黑盒模型分配的风险分数.*
- [Towards Reverse-Engineering Black-Box Neural Networks](https://arxiv.org/abs/1711.01768) - (ICLR) [(Code)](https://github.com/coallaoh/WhitenBlackBox) *通过分析远程神经网络模型对某些输入的响应模式，推断其内部超参数（例如层数、非线性激活类型）.*
- [Data driven exploratory attacks on black box classifiers in adversarial domains](https://www.sciencedirect.com/science/article/pii/S092523121830136X) -（神经计算）*逆向工程远程分类器模型（例如，用于逃避验证码测试）.*
- [xGEMs: Generating Examplars to Explain Black-Box Models](https://arxiv.org/pdf/1806.08867.pdf)  - (arXiv) *通过训练无监督隐式生成模型来搜索黑盒模型中的偏差. 然后通过沿数据流形扰动数据样本来定量总结黑盒模型行为. *
- [Learning Networks from Random Walk-Based Node Similarities](https://arxiv.org/pdf/1801.07386) -（NIPS）*通过观察一些随机步行通勤时间来反转图表.*
- [Identifying the Machine Learning Family from Black-Box Models](https://rd.springer.com/chapter/10.1007/978-3-030-00374-6_6) -（CAEPIA）*确定返回的预测背后是哪种机器学习模型.* 
- [Stealing Neural Networks via Timing Side Channels](https://arxiv.org/pdf/1812.11720.pdf) -（arXiv）*通过使用查询的定时攻击窃取/近似模型.*
- [Copycat CNN: Stealing Knowledge by Persuading Confession with Random Non-Labeled Data](https://arxiv.org/abs/1806.05476) - (IJCNN)  [(Code)](https://github.com/jeiks/Stealing_DL_Models) *通过使用随机自然图像（ImageNet 和 Microsoft-COCO）查询来窃取黑盒模型 (CNN) 知识.*
- [Auditing the Personalization and Composition of Politically-Related Search Engine Results Pages](https://dl.acm.org/doi/10.1145/3178876.3186143) -（WWW）*一个 Chrome 扩展程序，用于调查参与者并收集搜索引擎结果页面（SERP）和自动完成建议，以研究个性化和组合.* 
### 2017
- [Uncovering Influence Cookbooks : Reverse Engineering the Topological Impact in Peer Ranking Services](https://dl.acm.org/authorize.cfm?key=N21772) -（CSCW）*旨在确定同行排名服务中使用了哪些中心性指标.*
- [The topological face of recommendation: models and application to bias detection](https://arxiv.org/abs/1704.08991) -（复杂网络）*为推荐给用户的项目提出偏差检测框架.*
- [Membership Inference Attacks Against Machine Learning Models](http://ieeexplore.ieee.org/document/7958568/) -（安全和隐私研讨会）*给定机器学习模型和记录，确定该记录是否用作模型训练数据集的一部分.*
- [Practical Black-Box Attacks against Machine Learning](https://dl.acm.org/citation.cfm?id=3053009) -（亚洲 CCS）*了解远程服务对对抗性分类攻击有多脆弱.*
### 2016
- [Algorithmic Transparency via Quantitative Input Influence: Theory and Experiments with Learning Systems](https://www.andrew.cmu.edu/user/danupam/datta-sen-zick-oakland16.pdf) - (IEEE S&amp;P) *使用沙普利值评估特征对模型的个体、联合和边际影响.*
- [Auditing Black-Box Models for Indirect Influence](https://arxiv.org/abs/1602.07043) -（ICDM）*通过“巧妙地”将变量从数据集中删除并查看精度差距来评估变量对黑盒模型的影响*
- [Iterative Orthogonal Feature Projection for Diagnosing Bias in Black-Box Models](https://arxiv.org/abs/1611.04967) -（FATML Workshop）*执行功能排名以分析黑盒模型*
- [Bias in Online Freelance Marketplaces: Evidence from TaskRabbit](http://datworkshop.org/papers/dat16-final22.pdf) -（dat workshop）*测量 TaskRabbit 的搜索算法排名.* 
- [Stealing Machine Learning Models via Prediction APIs](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/tramer) -（Usenix 安全）  [(Code)](https://github.com/ftramer/Steal-ML) *旨在提取远程服务使用的机器学习模型.*
- [“Why Should I Trust You?”Explaining the Predictions of Any Classifier](https://arxiv.org/pdf/1602.04938v3.pdf) - (arXiv)  [(Code)](https://github.com/marcotcr/lime-experiments) *通过对数据实例进行采样来解释黑盒分类器模型.*
- [Back in Black: Towards Formal, Black Box Analysis of Sanitizers and Filters](http://ieeexplore.ieee.org/document/7546497/) -（安全和隐私）*消毒剂和过滤器的黑盒分析.*
- [Algorithmic Transparency via Quantitative Input Influence: Theory and Experiments with Learning Systems](http://ieeexplore.ieee.org/document/7546525/) -（安全和隐私）*引入衡量输入对观察系统输出影响程度的措施.*
- [An Empirical Analysis of Algorithmic Pricing on Amazon Marketplace](https://mislove.org/publications/Amazon-WWW.pdf) - （万维网） [(Code)](http://personalization.ccs.neu.edu) *开发一种检测算法定价的方法，并根据经验使用它来分析它们在亚马逊市场上的流行程度和行为.*
### 2015
- [Certifying and Removing Disparate Impact](https://arxiv.org/abs/1412.3756) -（SIGKDD）*提出基于 SVM 的方法来证明不存在偏见和消除数据集中偏见的方法.*
- [Peeking Beneath the Hood of Uber](https://dl.acm.org/citation.cfm?id=2815681) -（IMC）*推断 Uber 激增价格算法的实施细节.*
### 2014
- [窥探黑匣子：通过随机化探索分类器]() -（数据挖掘和知识发现期刊）（[code](https://github.com/tsabsch/goldeneye)) *找到可以在不改变预测样本输出标签的情况下排列的特征组*
- [XRay: Enhancing the Web's Transparency with Differential Correlation](https://www.usenix.org/node/184394) -（USENIX 安全）*审计哪些用户配置文件数据用于定位特定广告、推荐或价格.*
### 2013
- [Measuring Personalization of Web Search](https://dl.acm.org/citation.cfm?id=2488435) - (WWW) *开发了一种衡量网络搜索结果个性化的方法.*
- [Auditing: Active Learning with Outcome-Dependent Query Costs](https://www.cs.bgu.ac.il/~sabatos/papers/SabatoSarwate13.pdf) -（NIPS）*从只为负标签付费的二元分类器中学习.*

### 2012
- [Query Strategies for Evading Convex-Inducing Classifiers](http://www.jmlr.org/papers/v13/nelson12a.html)  - (JMLR) *凸分类器的规避方法. 考虑规避复杂性. *
### 2008
- [Privacy Oracle: a System for Finding Application Leakswith Black Box Differential Testing](https://dl.acm.org/citation.cfm?id=1455806) - (CCS) *Privacy Oracle：一个系统，可以发现应用程序在传输到远程服务器时泄露的个人信息.*
### 2005
- [Adversarial Learning](https://dl.acm.org/citation.cfm?id=1081950) - (KDD) *远程线性分类器的逆向工程，使用成员查询.*

## Related Events
* [Workshop on Algorithmic Audits of Algorithms (WAAA)](https://algorithmic-audits.github.io)
