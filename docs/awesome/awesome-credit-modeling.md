<div class="github-widget" data-repo="mourarthur/awesome-credit-modeling"></div>
## Awesome Credit Modeling
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![GitHub](https://img.shields.io/github/license/mourarthur/awesome-credit-modeling?style=flat-square)](https://github.com/mourarthur/awesome-credit-modeling/blob/master/LICENSE)

越来越多关于信用和信用风险建模的精彩论文、文章和各种资源.



## Introduction

- [Statistical Classification Methods in Consumer Credit Scoring: A Review](https://www.jstor.org/stable/2983268) - 信用评分主题的经典介绍和复习.

- [Consumer Finance: Challenges for Operational Research](https://www.jstor.org/stable/40540227)  - 回顾信用评分（消费金融风险评估方式）的发展以及信用评分的含义. 概述运筹学支持消费金融建模的 10 大挑战.

- [Machine Learning in Credit Risk Modeling](https://james.finance/static/assets/whitepapers/Machine-Learning-in-Credit-Risk-Modeling-James-white-paper.pdf) - James (formerly CrowdProcess) is a now-defunct online credit risk management startup that provided risk management tools to financial institutions. This whitepaper offers an overview of machine learning applications in the field of credit risk modeling.

- ['Lending by numbers': credit scoring and the constitution of risk within American consumer credit](https://www.tandfonline.com/doi/abs/10.1080/03085140601089846)  - 检查统计信用评分技术如何被贷方应用于控制美国消费信贷违约水平的问题. 探索他们感知的方法论、程序和时间风险.

- [Machine Learning in Financial Crisis Prediction: A Survey](https://ieeexplore.ieee.org/document/6069610)  - 回顾 1995 年至 2010 年期间的 130 篇期刊论文，重点关注用于破产预测和信用评分建模的最先进机器学习技术的发展. 还介绍了他们目前的成就和局限性.

## Credit Scoring

- [Super-App Behavioral Patterns in Credit Risk Models: Financial, Statistical and Regulatory Implications](https://arxiv.org/abs/2005.14658)  - 与传统局数据相比，介绍源自基于应用程序的市场的替代数据对信用评分模型的影响. 这些替代数据源已证明它们在预测银行和金融机构传统上服务不足的细分市场中的借款人行为方面非常强大. 同时，必须仔细验证替代数据，以克服不同司法管辖区的监管障碍.

- [Benchmarking state-of-the-art classification algorithms for credit scoring: An update of research](https://www.sciencedirect.com/science/article/abs/pii/S0377221715004208)  - 记分卡的开发取得了多项进展，包括新颖的学习方法、性能测量和可靠地比较不同分类器的技术，信用评分文献没有反映这些. 本文将几种新颖的分类算法与信用评分的最新技术进行了比较. 此外，还检查了替代记分卡的评估在已建立的和新的预测准确性指标中的差异程度.

- [Financial credit risk assessment: a recent review](https://dl.acm.org/doi/10.1007/s10462-015-9434-x)  - 准确评估金融信用风险和预测企业倒闭对经济和社会都起着至关重要的作用. 为此，近年来提出了越来越多的方法和算法.

- [Classification methods applied to credit scoring: Systematic review and overall comparison](https://www.sciencedirect.com/science/article/abs/pii/S1876735416300101)  - 控制和有效管理信用风险的需要导致金融机构擅长改进为此目的设计的技术，导致金融机构和咨询公司开发各种量化模型. 因此，越来越多的关于信用评分的学术研究显示了多种分类方法用于区分好坏借款人. 本文旨在对二元分类技术在信用评分财务分析中的理论和应用进行系统的文献综述. 总体结果显示了信用评级主要技术的使用和重要性，以及多年来科学范式的一些变化.

- [A literature review on the application of evolutionary computing to credit scoring](https://link.springer.com/article/10.1057/jors.2012.145) - 本文的目的是通过对 2000 年至 2012 年期间发表的科学文章的全面回顾，总结进化算法在信用评分中应用的最新进展.

- [A comparative study on base classifiers in ensemble methods for credit scoring](https://www.sciencedirect.com/science/article/abs/pii/S0957417416306947)  - 在过去几年中，人工智能方法在信用风险评估中的应用意味着对经典方法的改进. 最近的工作表明，分类器的集合对于这类任务取得了更好的结果.

- [Classifier Technology and the Illusion of Progress](https://projecteuclid.org/euclid.ss/1149600839)  - 已经开发了许多用于监督分类的工具，从线性判别分析等早期方法到神经网络和支持向量机等现代发展方法. 已经进行了大量的比较研究，试图确定这些方法的相对优势. 本文认为，这些比较往往没有考虑到实际问题的重要方面，因此更复杂方法的明显优势可能是一种错觉. 特别是，简单方法通常产生的性能几乎与更复杂的方法一样好，以至于性能差异可能被经典监督分类范式中通常未考虑的其他不确定性来源所淹没.

- [Good practice in retail credit scorecard assessment](https://www.tandfonline.com/doi/abs/10.1057/palgrave.jors.2601932)  - 在零售银行业务中，称为“记分卡”的预测统计模型用于将客户分配到不同类别，从而分配到适当的行动或干预措施. 此类分配是根据客户的预测分数是高于还是低于给定阈值进行的. 随着时间的推移，此类记分卡的预测能力会逐渐减弱，因此需要对绩效进行监控. 零售银行业常用的绩效衡量指标包括基尼系数、Kolmogorov–Smirnov 统计量、均值差和信息值. 然而，所有这些措施都使用了与分数大小无关的信息，并且未能使用与错误分类的数字相关的关键信息. 结果是，此类措施有时会严重误导，导致做出质量低劣的决策，并采取错误的行动.

- [Example-Dependent Cost-Sensitive Logistic Regression for Credit Scoring](https://ieeexplore.ieee.org/document/7033125)  - 一些现实世界的分类问题在本质上是依赖于示例的成本敏感的，其中由于错误分类而导致的成本因示例而异. 信用评分是成本敏感分类的典型例子. 但是，通常使用不考虑与贷款业务相关的实际财务成本的方法来处理它. 在本文中，我们提出了一个新的基于示例的信用评分成本矩阵. 此外，我们提出了一种将示例相关成本引入逻辑回归的算法.

- [A survey of credit and behavioural scoring: forecasting financial risk of lending to consumers](https://www.sciencedirect.com/science/article/abs/pii/S0169207000000340) - This article surveys the techniques used — both statistical and operational research based — to help organisations decide whether or not to grant credit to consumers. It also discusses the need to incorporate economic conditions into the scoring systems and the way the systems could change from estimating the probability of a consumer defaulting to estimating the profit a consumer will bring to the lending organisation.

- [The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients](https://www.sciencedirect.com/science/article/abs/pii/S0957417407006719)  - 本研究比较了六种数据挖掘方法中违约概率的预测准确性. 从风险管理的角度来看，估计违约概率的预测准确性的结果将比分类的二元结果更有价值——可信或不可信的客户.

- [Credit scoring using the clustered support vector machine](https://www.sciencedirect.com/science/article/abs/pii/S0957417414005119)  - 介绍使用集群支持向量机 (CSVM) 开发信用记分卡. 这种最近设计的算法解决了与基于传统非线性支持向量机 (SVM) 的分类方法相关的一些局限性. 具体来说，众所周知，随着历史信用评分数据集变得越来越大，这些非线性方法虽然非常准确，但计算量却越来越大.  CSVM 可以达到相当水平的分类性能，同时保持相对便宜的计算.

- [Multiple classifier application to credit risk assessment](https://www.sciencedirect.com/science/article/abs/pii/S0957417409008847) ([Corrigendum](https://www.sciencedirect.com/science/article/pii/S0957417410012364) ) - 本文探讨了五个分类器在信用风险预测准确性方面对不同类型噪声的预测行为，以及如何通过使用分类器集成来提高这种准确性. 给出了四个信用数据集的基准测试结果，并与每个单独的分类器在各种属性噪声水平下的预测准确性的性能进行了比较.

- [Consumer credit-risk models via machine-learning algorithms](https://alo.mit.edu/wp-content/uploads/2015/06/Household-behaviorConsumer-credit-riskCredit-card-borrowingMachine-learningNonparametric-estimation.pdf)  - 作者应用机器学习技术构建消费者信用风险的非线性非参数预测模型. 他们能够构建样本外预测，显着提高信用卡持有人拖欠和违约的分类率.

- [Bankruptcy prediction for credit risk using neural networks: A survey and new results](https://ieeexplore.ieee.org/document/935101)  - 公司破产的预测是一个重要且广泛研究的课题，因为它会对银行贷款决策和盈利能力产生重大影响. 这项工作回顾了破产预测的主题，重点是神经网络 (NN) 模型并开发了 NN 破产预测模型，为 NN 系统提出了新的指标.

- [Recent developments in consumer credit risk assessment](https://www.sciencedirect.com/science/article/abs/pii/S0377221706011866)  - 尽管研究人员考虑了许多其他类型的分类器，但通常使用逻辑回归模型估计向信贷申请人贷款的风险，但数据质量问题可能会阻止这些基于实验室的结果在实践中实现. 对接受申请人的样本而不是申请人群体的样本代表进行分类器训练似乎不会导致偏差，尽管它确实会导致难以设置截止值.

## Institutional Credit Risk

- [Modeling Institutional Credit Risk with Financial News](https://arxiv.org/abs/2004.08204)  - 当前降级风险建模工作取决于第三方评级机构和风险管理咨询公司提供的多种量化指标. 已经广泛推动使用替代数据源，例如金融新闻、财报电话会议记录或社交媒体内容，以可能在行业中获得竞争优势. 本文提出了一种仅使用由神经网络嵌入表示的新闻数据的预测降级模型.

- [Availability of Credit to Small Businesses](https://www.federalreserve.gov/publications/2017-september-availability-of-credit-to-small-businesses.htm)  - 1996 年经济增长和减少监管文书工作法案第 2227 条要求，联邦储备系统理事会每五年向国会提交一份报告，详细说明所有债权人对小企业的贷款范围. 最近的一个日期是 2017 年 9 月.

- [Credit Scoring and the Availability, Price, and Risk of Small Business Credit](https://muse.jhu.edu/article/181124) - 发现在控制银行规模和银行间的其他差异后，小企业信用评分与 100,000 美元以下的小企业信贷的数量增加、平均价格更高和平均风险水平更高有关.

- [Random Survival Forests Models for SME Credit Risk Measurement](https://link.springer.com/article/10.1007/s11009-008-9078-2) - 扩展了中小型企业信用风险违约领域实证研究的现有文献，提出了一种基于随机生存森林 (RSF) 的非参数方法，并将其性能与标准 logit 模型进行了比较.

- [Credit Risk Assessment Using Statistical and Machine Learning: Basic Methodology and Risk Modeling Applications](https://link.springer.com/article/10.1023/A:1008699112516)  - 通过风险建模实现更有效利用资源的目标的一个重要因素是在机构的信贷组合中找到个体风险的准确预测因子. 在这种情况下，作者对抵押贷款数据集的不同统计和机器学习建模方法进行了比较分析，目的是了解它们的局限性和潜力.

## Sample Selection

- [Reject inference in application scorecards: evidence from France](https://econpapers.repec.org/paper/drmwpaper/2016-10.htm) - 关于该主题的良好介绍和讨论.

- [Reject inference, augmentation, and sample selection](https://www.sciencedirect.com/science/article/abs/pii/S0377221706011969) - 深入讨论.

- [Instance sampling in credit scoring: An empirical study of sample size and balancing](http://www.research.lancs.ac.uk/portal/en/publications/instance-sampling-in-credit-scoring-an-empirical-study-of-sample-size-and-balancing(89b83914-c7f2-499a-8fa1-844d6cb6004d).html) - 讨论了信用建模中的传统抽样约定，并认为使用更大的样本可以显着提高跨算法的准确性.

## Feature Selection

- [A multi-objective approach for profit-driven feature selection in credit scoring](https://www.sciencedirect.com/science/article/pii/S0167923619300570)  - 在信用评分中，特征选择旨在去除不相关的数据，以提高评分卡的性能和可解释性. 标准技术将特征选择视为单一目标任务，并依赖于相关性等统计标准. 最近的研究表明，使用基于利润的指标可能会提高企业评分模型的质量.

- [Data mining feature selection for credit scoring models](https://link.springer.com/article/10.1057/palgrave.jors.2601976)  - 使用的特征可能对信用评分模型的性能产生重要影响. 为信用评分模型选择最佳特征集的过程通常是非系统的，并且以某种程度的任意试验为主. 本文对四种机器学习特征选择方法进行了实证研究.

- [Combination of feature selection approaches with SVM in credit scoring](https://www.sciencedirect.com/science/article/abs/pii/S0957417409010719)  - 有效的信用评分分类模型将客观地帮助依赖直觉经验的管理者. 本研究提出了四种使用 SVM（支持向量机）分类器进行特征选择的方法，这些方法保留了足够的信息用于分类目的.
