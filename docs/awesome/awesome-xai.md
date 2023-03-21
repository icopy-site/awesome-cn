<div class="github-widget" data-repo="altamiracorp/awesome-xai"></div>
<div align="center">

<!-- title -->
<!--lint ignore no-dead-urls-->
## Awesome XAI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- subtitle -->
XAI 和可解释的 ML 论文、方法、评论和
resources.

<!-- image -->
<img src="https://raw.githubusercontent.com/altamiracorp/awesome-xai/main/images/icon.svg" width="256" style="max-width: 25% !important"/>

<!-- description -->
可解释人工智能 (XAI) 是机器学习研究的一个分支，旨在
使各种机器学习技术更容易理解.

</div>

<!-- TOC -->



<!-- CONTENT -->
## Papers

### Landmarks

这些是我们最喜欢的一些论文. 他们有助于了解该领域
和它的关键方面. 我们相信这篇论文值得一读
entirety.

- [Explanation in Artificial Intelligence: Insights from the Social Sciences](https://arxiv.org/abs/1706.07269)  - 本文提供了对社会科学研究的介绍性解释. 作者提供了 4 个主要发现：(1) 解释是约束性的，(2) 解释是有选择的，(3) 概率可能无关紧要，(4) 解释是社会性的. 这些符合解释是-上下文-的一般主题.
- [Sanity Checks for Saliency Maps](https://arxiv.org/abs/1810.03292)  - 任何使用显着图的人的重要读物. 本文提出了两个实验来确定显着图是否有用：（1）模型参数随机化测试比较来自训练和未训练模型的图，（2）数据随机化测试比较来自在原始数据集上训练的模型和在同一数据集上训练的模型的图带有随机标签. 他们发现“一些广泛部署的显着性方法独立于训练模型的数据和模型参数”.

### Surveys

- [Explainable Deep Learning: A Field Guide for the Uninitiated](https://arxiv.org/abs/2004.14545) - 对 XAI 的深入描述侧重于深度学习的技术.

### Evaluations

- [Quantifying Explainability of Saliency Methods in Deep Neural Networks](https://arxiv.org/abs/2009.02899) - 基于对生成的数据集的实验，分析不同的基于热图的显着性方法如何执行.

### XAI Methods

- [Ada-SISE](https://arxiv.org/abs/2102.07799) - 用于解释的自适应语义输入采样.
- [ALE](https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/rssb.12377) - 累积局部效应图.
- [ALIME](https://link.springer.com/chapter/10.1007/978-3-030-33607-3_49) - 基于自动编码器的本地可解释性方法.
- [Anchors](https://ojs.aaai.org/index.php/AAAI/article/view/11491) - 高精度模型无关的解释.
- [Auditing](https://link.springer.com/article/10.1007/s10115-017-1116-3) - 审计黑盒模型.
- [BayLIME](https://arxiv.org/abs/2012.03058) - 贝叶斯局部可解释模型不可知论解释.
- [Break Down](http://ema.drwhy.ai/breakDown.html#BDMethod) - 分解附加属性的情节.
- [CAM](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Zhou_Learning_Deep_Features_CVPR_2016_paper.pdf) - 类激活映射.
- [CDT](https://ieeexplore.ieee.org/abstract/document/4167900) - 贝叶斯决策树集成的自信解释.
- [CICE](https://christophm.github.io/interpretable-ml-book/ice.html) - 居中的 ICE 图.
- [CMM](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.40.2710&rep=rep1&type=pdf) - 结合多种模型metalearner.
- [Conj Rules](https://www.sciencedirect.com/science/article/pii/B9781558603356500131) - 使用采样和查询从经过训练的神经网络中提取规则.
- [CP](https://ieeexplore.ieee.org/abstract/document/6597214) - 贡献传播.
- [DecText](https://dl.acm.org/doi/abs/10.1145/775047.775113) - 从训练有素的神经网络中提取决策树.
- [DeepLIFT](https://ieeexplore-ieee-org.ezproxy.libraries.wright.edu/abstract/document/9352498) - 用于图像注释的深度标签特定特征学习.
- [DTD](https://www.sciencedirect.com/science/article/pii/S0031320316303582) - 深度泰勒分解.
- [ExplainD](https://www.aaai.org/Papers/IAAI/2006/IAAI06-018.pdf) - 附加分类器中证据的解释.
- [FIRM](https://link.springer.com/chapter/10.1007/978-3-642-04174-7_45) - 特征重要性排名措施.
- [Fong, et. al.](https://openaccess.thecvf.com/content_iccv_2017/html/Fong_Interpretable_Explanations_of_ICCV_2017_paper.html) - 有意义的扰动模型.
- [G-REX](https://www.academia.edu/download/51462700/s0362-546x_2896_2900267-220170122-9600-1njrpyx.pdf) - 使用遗传算法提取规则.
- [Gibbons, et. al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3977175/) - 使用决策树解释随机森林.
- [GoldenEye](https://link-springer-com.ezproxy.libraries.wright.edu/article/10.1007/s10618-014-0368-8) - 通过随机化探索分类器.
- [GPD](https://arxiv.org/abs/0912.1128) - 高斯过程决策.
- [GPDT](https://ieeexplore.ieee.org/abstract/document/4938655) - 进化决策树的遗传程序.
- [GradCAM](https://openaccess.thecvf.com/content_iccv_2017/html/Selvaraju_Grad-CAM_Visual_Explanations_ICCV_2017_paper.html) - 梯度加权类激活映射.
- [GradCAM++](https://ieeexplore.ieee.org/abstract/document/8354201/) - 广义的基于梯度的视觉解释.
- [Hara, et. al.](https://arxiv.org/abs/1606.05390) - 使树集成可解释.
- [ICE](https://www.tandfonline.com/doi/abs/10.1080/10618600.2014.907095) - 个人条件期望图.
- [IG](http://proceedings.mlr.press/v70/sundararajan17a/sundararajan17a.pdf) - 综合渐变.
- [inTrees](https://link.springer.com/article/10.1007/s41060-018-0144-8) - 用 inTrees 解释树集合.
- [IOFP](https://arxiv.org/abs/1611.04967) - 迭代正交特征投影.
- [IP](https://arxiv.org/abs/1703.00810) - 信息平面可视化.
- [KL-LIME](https://arxiv.org/abs/1810.02678) - 基于 LIME 的 Kullback-Leibler 预测.
- [Krishnan, et. al.](https://www.sciencedirect.com/science/article/abs/pii/S0031320398001812) - 从训练有素的神经网络中提取决策树.
- [Lei, et. al.](https://arxiv.org/abs/1606.04155) - 使用生成器和编码器合理化神经预测.
- [LIME](https://dl.acm.org/doi/abs/10.1145/2939672.2939778) - 本地可解释的与模型无关的解释.
- [LOCO](https://amstat.tandfonline.com/doi/abs/10.1080/01621459.2017.1307116#.YEkdZ7CSmUk) - 保留一个协变量.
- [LORE](https://arxiv.org/abs/1805.10820) - 基于本地规则的解释.
- [Lou, et. al.](https://dl.acm.org/doi/abs/10.1145/2487575.2487579) - 具有成对交互的准确可理解模型.
- [LRP](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0130140) - 逐层相关性传播.
- [MCR](https://www.jmlr.org/papers/volume20/18-760/18-760.pdf) - 模型类依赖.
- [MES](https://ieeexplore.ieee.org/abstract/document/7738872) - 模型解释系统.
- [MFI](https://arxiv.org/abs/1611.07567) - 非线性算法的特征重要性度量.
- [NID](https://www.sciencedirect.com/science/article/abs/pii/S0304380002000649) - 神经解释图.
- [OptiLIME](https://arxiv.org/abs/2006.05714) - 优化石灰.
- [PALM](https://dl.acm.org/doi/abs/10.1145/3077257.3077271) - 分区感知本地模型.
- [PDA](https://arxiv.org/abs/1702.04595) - 预测差异分析：可视化深度神经网络决策.
- [PDP](https://projecteuclid.org/download/pdf_1/euclid.aos/1013203451) - 部分依赖图.
- [POIMs](https://academic.oup.com/bioinformatics/article/24/13/i6/233341) - 用于理解 SVM 信号检测器的位置低聚物重要性矩阵.
- [ProfWeight](https://arxiv.org/abs/1807.07506) - 将信息从深层网络传输到更简单的模型.
- [Prospector](https://dl.acm.org/doi/abs/10.1145/2858036.2858529) - 交互式部分依赖诊断.
- [QII](https://ieeexplore.ieee.org/abstract/document/7546525) - 定量输入影响.
- [REFNE](https://content.iospress.com/articles/ai-communications/aic272) - 从训练有素的神经网络集合中提取符号规则.
- [RETAIN](https://arxiv.org/abs/1608.05745) - 逆时注意力模型.
- [RISE](https://arxiv.org/abs/1806.07421) - 用于解释的随机输入采样.
- [RxREN](https://link.springer.com/article/10.1007%2Fs11063-011-9207-8) - 用于规则提取的逆向工程神经网络.
- [SHAP](https://arxiv.org/abs/1705.07874) - 解释模型预测的统一方法.
- [SIDU](https://arxiv.org/abs/2101.10710) - 相似性、差异性和独特性输入扰动.
- [Simonynan, et. al](https://arxiv.org/abs/1312.6034) - 可视化 CNN 类.
- [Singh, et. al](https://arxiv.org/abs/1611.07579) - 作为黑盒解释的程序.
- [STA](https://arxiv.org/abs/1610.09036) - 通过单树近似解释模型.
- [Strumbelj, et. al.](https://www.jmlr.org/papers/volume11/strumbelj10a/strumbelj10a.pdf) - 使用博弈论解释个人分类.
- [SVM+P](https://www.academia.edu/download/2471122/3uecwtv9xcwxg6r.pdf) - 从支持向量机中提取规则.
- [TCAV](https://openreview.net/forum?id=S1viikbCW) - 使用概念激活向量进行测试.
- [Tolomei, et. al.](https://dl.acm.org/doi/abs/10.1145/3097983.3098039) - 通过可操作的特征调整对树集合进行可解释的预测.
- [Tree Metrics](https://www.researchgate.net/profile/Edward-George-2/publication/2610587_Making_Sense_of_a_Forest_of_Trees/links/55b1085d08aec0e5f430eb40/Making-Sense-of-a-Forest-of-Trees.pdf) - 理解一片树林.
- [TreeSHAP](https://arxiv.org/abs/1706.06060) - 树合奏的一致特征属性.
- [TreeView](https://arxiv.org/abs/1611.07429) - 特征空间划分.
- [TREPAN](http://www.inf.ufrgs.br/~engel/data/media/file/cmp121/TREPAN_craven.nips96.pdf) - 提取经过训练的网络的树结构表示.
- [TSP](https://dl.acm.org/doi/abs/10.1145/3412815.3416893) - 树空间原型.
- [VBP](http://www.columbia.edu/~aec2163/NonFlash/Papers/VisualBackProp.pdf) - 视觉反向传播.
- [VEC](https://ieeexplore.ieee.org/abstract/document/5949423) - 可变效应特性曲线.
- [VIN](https://dl.acm.org/doi/abs/10.1145/1014052.1014122) - 可变交互网络.
- [X-TREPAN](https://arxiv.org/abs/1508.07551) - 人工神经网络中可理解决策树的适应提取.
- [Xu, et. al.](http://proceedings.mlr.press/v37/xuc15) - 展示、参加、讲述注意力模型.

### Interpretable Models

- [Decision List](https://christophm.github.io/interpretable-ml-book/rules.html) - 就像没有分支的决策树.
- [Decision Trees](https://en.wikipedia.org/wiki/Decision_tree) - 树提供了解释.
- [Explainable Boosting Machine](https://www.youtube.com/watch?v=MREiHgHgl0k) - 基于学习到的特征向量图进行预测的方法.
- [k-Nearest Neighbors](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm) - 原型聚类方法.
- [Linear Regression](https://en.wikipedia.org/wiki/Linear_regression) - 易于绘制和理解的回归.
- [Logistic Regression](https://en.wikipedia.org/wiki/Logistic_regression) - 易于绘制和理解的分类.
- [Naive Bayes](https://en.wikipedia.org/wiki/Naive_Bayes_classifier) - 良好的分类，使用条件概率的估计不佳.
- [RuleFit](https://christophm.github.io/interpretable-ml-book/rulefit.html) - Sparse linear model as decision rules including feature interactions.


### Critiques

- [Attention is not Explanation](https://arxiv.org/abs/1902.10186)  - 作者进行了一系列 NLP 实验，这些实验认为注意力并不能提供有意义的解释. 他们还证明不同的注意力可以产生相似的模型输出.
- [Attention is not --not-- Explanation](https://arxiv.org/abs/1908.04626)  - 这是对上述论文的反驳. 作者争辩说，多种解释可能是有效的，并且这种注意力可以产生*一个*有效的解释，如果不是 - 有效的解释.
- [Do Not Trust Additive Explanations](https://arxiv.org/abs/1903.11420) - 作者认为加性解释（例如 LIME、SHAP、Break Down）未能将特征相互作用考虑在内，因此不可靠.
- [Please Stop Permuting Features An Explanation and Alternatives](https://arxiv.org/abs/1905.03151)  - 作者证明了为什么置换特征会产生误导，尤其是在特征依赖性很强的情况下. 他们提供了几个先前描述的替代方案.
- [Stop Explaining Black Box Machine Learning Models for High States Decisions and Use Interpretable Models Instead](https://www.nature.com/articles/s42256-019-0048-x?fbclid=IwAR3156gP-ntoAyw2sHTXo0Z8H9p-2wBKe5jqitsMCdft7xA0P766QvSthFs)  - 作者提出了可解释 ML 的许多问题和可解释 ML 的挑战：（1）构建最佳逻辑模型，（2）构建最佳稀疏评分系统，（3）定义可解释性并为特定方法创建方法. 他们还提出了为什么可解释模型可能存在于许多不同领域的论据.
- [The (Un)reliability of Saliency Methods](https://link.springer.com/chapter/10.1007/978-3-030-28954-6_14)  - 作者演示了在向输入数据添加常量偏移时显着性方法如何改变归因. 他们认为方法应该满足*输入不变性*，显着性方法反映了模型对输入转换的敏感性.


## Repositories

- [EthicalML/xai](https://github.com/EthicalML/xai)  - 专门针对表格数据的 XAI 工具包. 它实现了多种数据和模型评估技术.
- [MAIF/shapash](https://github.com/MAIF/shapash) - 基于 SHAP 和 LIME 的前端解释器.
- [PAIR-code/what-if-tool](https://github.com/PAIR-code/what-if-tool) - 用于 Tensorboard 或 Notebooks 的工具，允许调查模型性能和公平性.
- [slundberg/shap](https://github.com/slundberg/shap) - 用于使用 Shapley 加法解释的 Python 模块.


## Videos

- [Debate: Interpretability is necessary for ML](https://www.youtube.com/watch?v=93Xv8vJ2acI) - 关于 ML 是否需要可解释性的辩论，Rich Caruana 和 Patrice Simard 支持，Kilian Weinberger 和 Yann LeCun 反对.


## Follow

他们的观点不一定是我们的观点.  ：眨眼：

- [The Institute for Ethical AI & Machine Learning](https://ethical.institute/index.html) - 一家总部位于英国的研究中心，对道德 AI/ML 进行研究，其中经常涉及 XAI.
- [Tim Miller](https://twitter.com/tmiller_unimelb) - XAI 杰出的研究人员之一.
- [Rich Caruana](https://www.microsoft.com/en-us/research/people/rcaruana/) - Explainable Boosting Machines 背后的人.

我们还应该追随谁！？

## Contributing

[Contributions of any kind welcome, just follow the guidelines](https://github.com/altamiracorp/awesome-xai/blob/master/contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/altamiracorp/awesome-xai/graphs/contributors)!
