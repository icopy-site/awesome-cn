<div class="github-widget" data-repo="hangtwenty/dive-into-machine-learning"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Dive into Machine Learning [![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

你好呀！ 本指南适用于以下情况：

* 你知道 Python 或 [you're learning it](https://nbviewer.org/github/jakevdp/WhirlwindTourOfPython/blob/master/Index.ipynb) ：蛇：
* 你是新手 [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)
* 你关心 [the ethics of ML](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)
    * **[8 Responsible Machine Learning Principles](https://ethical.institute/principles.html)**
    * [Open Ethics Canvas](https://openethics.ai/canvas/)
* 边做边学

如果这就是你，和我一起走在前面，看看你是否想更多地了解这个领域.  （对于替代方案， [jump to the end of the guide](https://github.com/hangtwenty/dive-into-machine-learning#m或者e-ways-to-dive-into-machine-learning) 或者 [check out Nam Vu's guide, Machine Learning f或者 Software Engineers](https://github.com/ZuzooVn/machine-learning-f或者-software-engineers).)

## Let's get started

弄湿你的脚，增强你的信心.

## Tools you'll need

### If you prefer local installation

- [Python](https://www.python.org/) .  Python 3 是最好的选择.
- [Jupyter Notebook](https://jupyter.org/) .  （以前称为 IPython Notebook.）
- 一些科学计算包：
	- 麻木
	- 熊猫
	- scikit-学习
	- matplotlib

您可以通过点击几下安装 Python 3 和所有这些包 [Anaconda Python distribution](https://www.anaconda.com/download/) .  Anaconda 在数据科学和机器学习社区很受欢迎.  （使用您想要的任何工具.）

### Cloud-based options

您可以从浏览器使用的一些选项：

- **[Binder](https://mybinder.org/) 是 Jupyter Notebook 的官方选择 [try JupyterLab](https://jupyter.org/try)**
- [Deepnote](https://deepnote.com/) 允许实时协作
- [Google Colab](https://colab.research.google.com/) 提供“免费”GPU

有关其他选项，请参阅：

- [markusschanta/awesome-jupyter, "Hosted Notebook Solutions"](https://github.com/markusschanta/awesome-jupyter#hosted-notebook-solutions)
- [ml-tooling/best-of-jupyter, "Notebook Environments"](https://github.com/ml-tooling/best-of-jupyter)

## Let's go!

**[Learn how to use Jupyter Notebook](http://opentechschool.github.io/python-data-intro/core/notebook.html) （5-10 分钟）.**（您可以 [learn by screencast](https://www.youtube.com/watch?v=qb7FT68tcA8) 反而.）

现在，跟随这个简短的练习：**[An introduction to machine learning with scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html) **. 在 `ipython` 或 Jupyter Notebook 中进行. 它真的会增强你的信心.

[![I'll wait.](https://user-images.githubusercontent.com/2420688/29441281-00eff0c4-837f-11e7-9666-d653a1cd2372.jpeg)](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)

## What just happened?

您刚刚使用以下方法对一些手写数字进行了分类 [scikit-learn](http://scikit-learn.org/stable/index.html) . 整洁吧？

## Dive in

## A Visual Introduction to Machine Learning

让我们更多地了解机器学习，以及一些常见的想法和关注点. 读 ["A Visual Introduction to Machine Learning, Part 1"](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) 经过 [Stephanie Yee](https://twitter.com/stephaniejyee) 和 [Tony Chu](https://twitter.com/tonyhschu/).

[![A Visual Introduction to Machine Learning, Part 1](https://user-images.githubusercontent.com/2420688/29441234-a2028c98-837e-11e7-88f2-1ca5a94684f6.gif)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

不会花很长时间. 这是一个美丽的介绍......尽量不要流口水太多！

## A Few Useful Things to Know about Machine Learning

好的. 让我们深入探讨.

读 **["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)** 经过 [Prof. Pedro Domingos](https://homes.cs.washington.edu/~pedrod/) . 它充满了有价值的信息，但并不透明.

慢慢来吧. 做笔记. 如果您还没有完全理解，请不要担心.

整篇论文都充满了价值，但我想指出两点：

 - **仅靠数据是不够的.** 这是机器学习中科学与艺术相遇的地方. 引用 Domingos 的话：“......学习中对知识的需求不应该令人惊讶.机器学习不是魔术；它不能从无到有.它所做的是从更少的东西中获得更多.编程，就像所有工程一样，是一种很多工作：我们必须从头开始构建一切.学习更像是农业，它让自然完成大部分工作.农民将种子与营养结合起来种植庄稼.学习者将知识与数据结合起来发展计划.”
 - **更多的数据胜过更聪明的算法.** 听着，程序员. 我们喜欢很酷的工具. 抵制重新发明轮子或过度设计解决方案的诱惑. 你的出发点是 [Do the Simplest Thing that Could _Possibly_ Work](http://www.artima.com/intv/simplest3.html) . 引用 Domingos 的话：“假设你已经构建了最好的特征集，但是你得到的分类器仍然不够准确.你现在能做什么？有两个主要选择：设计一个更好的学习算法，或者收集更多数据.[...] 根据经验，拥有大量数据的愚蠢算法胜过拥有少量数据的聪明算法.（毕竟，机器学习就是让数据完成繁重的工作.） ”

当您处理真正的机器学习问题时，在优化算法选择之前，您应该将精力集中在 **领域知识** 和 **数据** 上. 更喜欢[做简单的事情]，直到你_必须_增加复杂性. 你不应该急于进入神经网络，因为你认为它们很酷. 要改进您的模型，**获取更多数据.**然后利用您对问题的了解 [explore and process](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning) 数据. 只有在收集到足够的数据并且处理得当之后，才应该优化算法的选择.

![What has the most impact in Machine Learning](https://user-images.githubusercontent.com/2420688/29441212-798d2bba-837e-11e7-90b1-21daaf8d7b73.png)

（图形灵感来自幻灯片 28 [Alex Pinto's talk, "Secure Because Math: A Deep-Dive on ML-Based Monitoring"](https://www.slideshare.net/AlexandrePinto10/secure-because-math-a-deepdive-on-machine-learningbased-monitoring-securebecausemath))

【做简单的事】：http://wiki.c2.com/?DoSimpleThings

## Jargon note

* [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1) 
* 另一个方便的术语： ["Data Engineering"](https://towardsdatascience.com/who-is-a-data-engineer-how-to-become-a-data-engineer-1167ddc12811?gi=67df10cc32ea)，可能涉及或支持 ML，但不限于 ML. ["MLOps"](https://ml-ops.org/) 与数据工程重叠，并且有 [an introductory MLOps section later in this guide](#production-deployment-mlops).

## Just about time for a break...

<details><summary>完全可选：一些播客片段</summary>

一、下载 [an interview with Prof. Domingos on the _Data Skeptic_ podcast](https://dataskeptic.com/blog/episodes/2018/the-master-algorithm)  (2018). 教授. 星期天写道 [the paper we read earlier](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) . 你也可以开始阅读他的书， [_The Master Algorithm_ by Prof. Pedro Domingos](https://www.goodreads.com/book/show/24612233-the-master-algorithm)，清晰易懂的机器学习概述. 

接下来，订阅更多机器学习和数据科学播客！ 这些是很棒的、省力的资源，您可以随意从中学习更多. 到 [learn effectively](https://www.coursera.org/learn/learning-how-to-learn)，随着时间的推移聆听，有足够的空间. [By the way, don't speed up technical podcasts, that can hinder your comprehension.](https://www.theringer.com/2017/8/2/16095364/inefficiency-week-podcasts-speed-comprehension-f0ea43949e42)

订阅_**[Talking Machines](http://www.thetalkingmachines.com/)**_.

我建议这样听顺序：

* **下载 ["Starting Simple"](http://www.thetalkingmachines.com/episodes/starting-simple-and-machine-learning-meds) 插曲，并尽快收听.** 它支持我们从多明戈斯读到的内容. [Ryan Adams](http://people.seas.harvard.edu/~rpa/) 正如我们上面讨论的那样，谈论从简单开始.  Adams 还强调了特征工程的重要性. 特征工程是多明戈斯所写的“知识”的练习. 在后来的一集中， [they share many concrete tips for feature engineering](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning).
* 然后，随着时间的推移，您可以收听整个播客系列（从头开始）.

想订阅更多播客？ 这是 [a good listicle](https://towardsdatascience.com/5-data-science-ai-and-machine-learning-podcasts-to-listen-to-now-e5078b18d184) 的建议， [and another](https://mty.ai/blog/the-best-ai-podcasts/).

</details>

好的！ 休息一下，精神焕发地回来.

----

## Play to learn

接下来，从这些 Jupyter Notebook 中挑选**一两个**并一起玩.

- [Dr. Randal Olson's Example Machine Learning notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb)：“假设我们正在为一家初创公司工作，该公司刚刚获得资金，开发了一款智能手机应用程序，可以从智能手机拍摄的照片中自动识别花卉种类.我们的数据科学负责人要求我们创建一个演示机器学习该模型从花中进行四次测量（萼片长度、萼片宽度、花瓣长度和花瓣宽度），并仅根据这些测量值识别物种.”
	- [Launch in Binder, no installation steps required](https://mybinder.org/v2/gh/rhiever/Data-Analysis-and-Machine-Learning-Projects/master?filepath=example-data-science-notebook%2FExample%20Machine%20Learning%20Notebook.ipynb)
- 按主题分类的各种笔记本：
    - [trekhleb/machine-learning-experiments](https://github.com/trekhleb/machine-learning-experiments) -“这是交互式机器学习实验的集合.每个实验都包含️ Jupyter/Colab notebook（以了解模型是如何训练的）和演示页面”
    - [trekhleb/homemade-machine-learning](https://github.com/trekhleb/homemade-machine-learning)
- 系列笔记本：
    - [ageron/handson-ml2](https://github.com/ageron/handson-ml2) - “Jupyter 笔记本使用 Scikit-Learn、Keras 和 TensorFlow 2 引导您了解 Python 中机器学习和深度学习的基础知识.”

准备好后，查找更多出色的 Jupyter Notebook：

* **[Jupyter's official Gallery of Interesting Jupyter Notebooks: Statistics, Machine Learning and Data Science](https://github.com/jupyter/jupyter/wiki)** ([permalink](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks/ae03c01ed25024aa06a4479ea600895d59b38bc4))

----

## Immerse yourself

现在你应该被迷住了，渴望了解更多. 选择以下课程之一，开始您的旅程.

## [Recommended course: Prof. Andrew Ng's _Machine Learning_ on Coursera](https://www.coursera.org/learn/machine-learning)


您可能想在旁边玩一个宠物项目. 当你准备好时，你可以探索其中之一 [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets).

另外，你应该拿一本深入的教科书作为参考. 我反复看到的两个建议是 [_Underst和ing Machine Learning_ ](http://www.cs.huji.ac.il/~shais/Underst和ingMachineLearning/copy.html) 和 _[Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)_. [You only need to use one of the two options as your main reference; here's some context/comparison to help you pick which one is right for you.](https://github.com/hangtwenty/dive-into-machine-learning/issues/29) 您可以在这些链接中以 PDF 格式免费下载每本书 - 所以抓住它们！

### Tips for studying

 * 繁忙的日程？ 读 [Ray Li's review of Prof. Andrew Ng's course](https://rayli.net/blog/data/coursera-machine-learning-review/) 一些有用的提示.
* 回顾一些 ["Learning How to Learn"](https://www.coursera.org/learn/learning-how-to-learn/) 视频. 这只是关于如何学习的一般方法. 在课程中，他们 [advocate the learn-by-doing approach](https://www.coursera.org/learn/learning-how-to-learn/lecture/8IUbH/interview-with-dr-terrence-sejnowski) ，正如我们在这里所做的那样. 您将获得各种其他易于应用的技巧，但对于使您的时间投资更有效还有很长的路要走.
* 审查提示来自 [Nam Vu's guide to learning ML as a software engineer](https://github.com/ZuzooVn/machine-learning-for-software-engineers#the-daily-plan).

## Other courses

<details>
<summary>以下是我推荐的其他一些免费在线课程.  （机器学习、数据科学和相关主题.）</summary>

* **作为 Jupyter Notebooks 的数据科学课程：**
    * [Practical Data Science](http://radimrehurek.com/data_science_python/)
    * [Python Data Science Handbook, as Jupyter Notebooks](https://jakevdp.github.io/PythonDataScienceHandbook/)
* [Prof. Pedro Domingos's introductory video series](https://homes.cs.washington.edu/~pedrod/) . 多明戈斯写了这篇论文 ["A Few Useful Things to Know About Machine Learning"](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)，在本指南前面推荐.
* Kevin Markham 的视频系列， [Intro to Machine Learning with scikit-learn](http://blog.kaggle.com/2015/04/08/new-video-series-introduction-to-machine-learning-with-scikit-learn/)，从我们已经涵盖的内容开始，然后在一个舒适的地方继续.
* [UC Berkeley's Data 8: The Foundations of Data Science](http://data8.org/) 课程和教科书 [Computational and Inferential Thinking](https://www.inferentialthinking.com/) 教授数据科学中的关键概念.
    * [Foundations of Data Science](https://www.edx.org/professional-certificate/berkeleyx-foundations-of-data-science) 现在也通过 edX 提供基于 Data 8 的在线课程.
* Mark A. Girolami 教授 [Machine Learning Module (GitHub Mirror).](https://github.com/josephmisiti/machine-learning-module) 适合有很强数学背景的人.
* [Advanced Statistical Computing (Vanderbilt BIOS8366)](http://stronginference.com/Bios8366/lectures.html) . 交互的.
* 数据科学课件调查（多一点选择你自己的冒险）
    * [An epic Quora thread: How can I become a data scientist?](https://www.quora.com/How-can-I-become-a-data-scientist?redirected_qid=59455)
    * 查看 [Jack Golding's survey of Data Science courseware](https://www.quora.com/Is-it-worth-it-to-pay-9-*-49-for-a-data-science-specialization-on-Coursera/answer/Jack-Golding) . 包括 Coursera  [Data Science Specialization](https://www.coursera.org/specializations/jhu-data-science) 其中有9门课程. 专业化证书不是免费的，但如果您不关心证书，您可以一对一免费学习课程. 该调查还涵盖 [Harvard CS109](http://cs109.github.io/2014/) 我在别处看到推荐的.
</details>

## Getting Help: Questions, Answers, Chats

从与您正在学习的课程相关的支持论坛和聊天开始.

查看 [datascience.stackexchange.com](https://datascience.stackexchange.com/) 和 [stats.stackexchange.com – such as the tag, _machine-learning_.](https://stats.stackexchange.com/questions/tagged/machine-learning?sort=frequent&pageSize=15) 有一些 subreddits，比如 [/r/LearningMachineLearning](https://www.reddit.com/r/learningmachinelearning) 和 [/r/MachineLearning](https://www.reddit.com/r/machinelearning).

不要忘记聚会. 此外，如今围绕 ML 生态系统有许多活跃且有用的在线社区. 在项目页面等上寻找聊天邀请.

## Supplement: Learning Pandas well

你会想要更熟悉 Pandas.

* **基本的**： [Things in Pandas I Wish I'd Had Known Earlier](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb) （作为 Jupyter 笔记本）
* **基本的**： [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* 另一个有用的教程： [Real World Data Cleanup with Python and Pandas](https://trendct.org/2016/08/05/real-world-data-cleanup-with-python-and-pandas/)
* [Video series from Data School, about Pandas](https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y) .  “30 项常见熊猫任务的参考指南（外加 6 小时的支持视频）.”
* [Useful Pandas Snippets](http://www.swegler.com/becky/blog/2014/08/06/useful-pandas-snippets/)
* 以下是我在继续学习过程中发现特别有用的一些文档：
	* [Cookbook](http://pandas.pydata.org/pandas-docs/stable/cookbook.html)
	* [Data Structures](http://pandas.pydata.org/pandas-docs/stable/dsintro.html)，尤其是 [DataFrame](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe) 部分
	* [Reshaping by pivoting DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/reshaping.html)
	* [Computational tools](http://p和as.pydata.org/p和as-docs/stable/computation.html) 和 [StackExchange thread: "What is covariance in plain language?"](https://stats.stackexchange.com/questions/29713/what-is-covariance-in-plain-language)
	* [Group By (split, apply, and combine DataFrames)](http://pandas.pydata.org/pandas-docs/stable/groupby.html)
	* [Visualizing your DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html)
* 书签供以后需要缩放时使用
	* [`dask`](https://dask.org/) ：类似 Pandas 的界面，但适用于大于内存的数据和“幕后”并行性. 非常有趣，但只有在您高级时才需要. 
	* 另见：MLOps 部分 [later in this guide](#production-deployment-mlops).

## Supplement: Cheat Sheets

我遇到了一些不错的备忘单.  （请 [submit a Pull Request](https://github.com/hangtwenty/dive-into-machine-learning/pulls) 添加其他有用的备忘单.）

- [scikit-learn algorithm cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
- [Matplotlib / Pandas / Python cheat sheets](https://drive.google.com/drive/folders/0ByIrJAE4KMTtaGhRcXkxNHhmY2M).

## Assorted Opinions and Other Resources

## Risks

“机器学习系统自动从
日期.”佩德罗·多明戈斯，在 ["A Few Useful Things to Know about Machine Learning."](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) 您生成的程序需要维护. 就像任何更快地创建程序的方式一样，您可以将 [technical debt](https://en.wikipedia.org/wiki/Technical_debt).

这里是摘要 [Machine Learning: The High-Interest Credit Card of Technical Debt](https://research.google/pubs/pub43146/):

 &gt; 机器学习为快速构建复杂系统提供了一个非常强大的工具包. 这篇论文认为，将这些快速的胜利视为免费的，是很危险的. 使用技术债务框架，我们注意到在应用机器学习时在系统级别产生大量的持续维护成本非常容易. 本文的目标是强调几个机器学习特定的风险因素和设计模式，以尽可能避免或重构. 这些包括边界侵蚀、纠缠、隐藏的反馈循环、未声明的消费者、数据依赖、外部世界的变化以及各种系统级的反模式.

如果您正在遵循本指南，则应该阅读该论文. 你也可以 [listen to a podcast episode interviewing one of the authors of this paper](https://softwareengineeringdaily.com/2015/11/17/machine-learning-and-technical-debt-with-d-sculley/).

- **[Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning), “一个精选的开源库列表，用于部署、监控、版本和扩展您的机器学习.”** 它包括一个关于 [privacy-preserving ML](https://github.com/EthicalML/awesome-production-machine-learning#privacy-preserving-machine-learning)， 顺便一提！
 - **[“机器学习规则：[可靠] ML 工程的最佳实践，”](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)** Martin Zinkevich，关于 ML 工程实践. 有一个 [accompanying video](http://cs.stanford.edu/~jsteinhardt/wildml2016nips/videos/1_2_Martin.wmv).
- **[Surviving Data Science "at the Speed of Hype"](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype)** 作者：John Foreman，MailChimp 的数据科学家
- [The High Cost of Maintaining Machine Learning Systems](http://www.kdnuggets.com/2015/01/high-cost-machine-learning-technical-debt.html)
- [11 Clever Methods of Overfitting and How to Avoid Them](http://hunch.net/?p=22)
- [The Perilous World of Machine Learning for Fun and Profit: Pipeline Jungles and Hidden Feedback Loops](http://www.john-foreman.com/blog/the-perilous-world-of-machine-learning-for-fun-and-profit-pipeline-jungles-and-hidden-feedback-loops)
- ["So, you want to build an ethical algorithm?" An interactive tool to prompt discussions](https://cdt.info/ddtool/) [(source)](https://github.com/numfocus/algorithm-ethics)

### Welcome to the Danger Zone

所以你正在涉足机器学习. 你有黑客技能. 也许你有一些 Domingos 意义上的“知识”（一些“实质性专业知识”或“领域知识”）. 此图略有修改自 [Drew Conway's "Data Science Venn Diagram."](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram) 它不_完美_适合我们这里的目的，但它可能会理解这一点：

[![Drew Conway's Data Science Venn Diagram, modified slightly](https://user-images.githubusercontent.com/2420688/29441268-f429d88c-837e-11e7-83ff-30874d832c89.png)](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram)

 **请**不要在您仍处于危险区域时将自己推销为机器学习专家. 不要制造糟糕的产品或发表垃圾科学. 请为道德人工智能与机器学习研究所添加书签**[Responsible Machine Learning Principles](https://ethical.institute/principles.html) **. 本指南无法告诉您如何知道自己已经“掌握”了机器学习能力……更不用说专业知识了. 如果没有学校或其他机构，就很难评估熟练程度. 所以，练习吧！

#### Towards Expertise

你需要**练习.** [On Hacker News, user olympus commented to say you could use competitions to practice 和 evaluate yourself](https://news.ycombinat或者.com/item?id=10508565). [Kaggle](https://www.kaggle.com/competitions) 和 [ChaLearn](http://www.chalearn.或者g/) 是机器学习竞赛的中心.  （你可以找到更多的比赛 [here](https://github.com/paperswithcode/releasing-research-code#results-leaderboards) 或者 [here](https://towardsdatascience.com/12-data-science-ai-competitions-to-advance-your-skills-in-2021-32e3fcb95d8c).)

You also need **understanding.** You should review what Kaggle competition winners say about their solutions, [for example, the "No Free Hunch" blog](http://blog.kaggle.com/). These might be over your head at first but once you're starting to understand and appreciate these, you know you're getting somewhere.

比赛和挑战只是练习的一种方式. 不过，你不应该限制自己——你也应该明白 [Machine Learning isn't **all** about Kaggle competitions](https://jvns.ca/blog/2014/06/19/machine-learning-isnt-kaggle-competitions).

这是练习的补充方式：**进行练习研究.**

 1. **提出问题. 开始探索一些数据.** ["most important thing in data science is the question"](https://github.com/DataScienceSpecialization/courses/blob/master/01_DataScientistToolbox/03_02_whatIsData/index.Rmd#the-data-is-the-second-most-important-thing) ([Dr. Jeff T. Leek](https://github.com/jtleek) ）. 所以从一个问题开始. 然后，找到 [real data](https://github.com/caesar0301/awesome-public-datasets) . 分析一下. 然后 ...
2. **交流结果.** 当您认为自己有新发现时，请征求意见.
 3. **修复问题.** 学习. 分享你所学到的.

并重复. 重新表述这一点，它符合 [scientific method](https://en.wikipedia.org/wiki/Scientific_method) ：制定问题（或问题陈述）、创建假设、收集数据、分析数据并交流结果.  （你应该 [watch this video about the scientific method in data science](http://101.datascience.community/2012/06/27/the-data-scientific-method/)，和/或 [read this article](http://customerthink.com/getting-insights-using-data-science-skills-and-the-scientific-method/).)

你怎么能想出有趣的问题？ 这是一种方法. 每个星期天， [browse datasets](https://github.com/caesar0301/awesome-public-datasets) 并写下一些问题. 另外，报名 [Data is Plural](https://tinyletter.com/data-is-plural) ，有趣的数据集通讯； 查看这些数据集，并写下问题. 保持好奇. 当一个问题激发了你的灵感时，开始研究.

这个建议，做实践研究和从同行评审中学习，是基于 [a conversation](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-153934120) 和 [Dr. Randal S. Olson](http://www.randalolson.com/) . 这是奥尔森的更多建议， [quoted 和 permission:](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-154135498)

 &gt; 我认为最好的建议是告诉人们总是清楚地展示他们的方法，避免过度解释他们的结果. 成为专家的一部分是知道很少有明确的答案，尤其是当您处理真实数据时.

当你重复这个过程时，你的实践研究将变得更加科学、有趣和集中. 这个过程中最重要的部分是同行评审.

#### Ask for Peer Review

以下是您可以联系进行非正式同行评审的一些社区：

* [/r/LearnMachineLearning](https://www.reddit.com/r/learnmachinelearning/)
* [/r/DataIsBeautiful](https://reddit.com/r/DataIsBeautiful)
* [/r/DataScience](https://reddit.com/r/DataScience)
* [/r/MachineLearning](https://reddit.com/r/MachineLearning)
* [Cross-Validated: stats.stackexchange.com](https://stats.stackexchange.com/)

发布到其中任何一个，并寻求反馈. 你会得到反馈. 你会学到很多. 当专家审查您的工作时，您将学到很多关于该领域的知识. 您还将练习一项关键技能：接受批评性反馈.

### Production, Deployment, [MLOps](https://ml-ops.org/)

MLOps 可以帮助您处理这样的问题：

[![image](https://user-images.githubusercontent.com/2420688/142702473-58834c0b-eda7-4496-a449-4bc24aa217b1.png)](https://valohai.com/mlops-ebook/)

如果您正在学习 MLOps 但发现它不堪重负，这些资源可能会帮助您了解方向：

* [MLOps Stack Template](https://valohai.com/blog/the-mlops-stack/) 亨里克·斯科格斯特伦 (Henrik Skogström)
* [Lessons on ML Platforms from Netflix, DoorDash, Spotify, and more](https://towardsdatascience.com/lessons-on-ml-platforms-from-netflix-doordash-spotify-and-more-f455400115c7) 作者 Ernest Chan 在 *Towards Data Science*

推荐保存/明星/观看的awesomelists：

* **[EthicalML/awesome-artificial-intelligence-guidelines](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)**
* **[EthicalML/awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning#privacy-preserving-machine-learning)**
* **[visenger/awesome-ml-model-governance](https://github.com/visenger/Awesome-ML-Model-Governance)**
* **[visenger/awesome-MLOps](https://github.com/visenger/awesome-mlops)**

----

## Deep Learning

在本指南的早期版本中，没有专门的“深度学习”部分. 该领域的专家警告不要跳得太远.

也许这是检查你的进步的一种方式：问问你自己，深度学习看起来像魔法吗？ 如果是这样，请将其视为您还没有准备好专业地使用它的标志，并让这种迷恋激励您学习更多. 我读过一些关于你可以单独学习深度学习的论点； 我读过其他人建议最好先掌握传统的机器学习. 为什么不从传统的机器学习开始，并在那里发展您的推理和直觉？ 在那之后，你只会更轻松地学习深度学习. 毕竟，您将能够解决各种有趣的问题.

无论如何，当您准备好深入学习深度学习时，这里有一些有用的资源.

* **[Dive into Deep Learning](https://d2l.ai/) - 一本关于深度学习的互动书**
    *“包含代码、数学和讨论的交互式深度学习书”
    *“使用 NumPy/MXNet、PyTorch 和 TensorFlow 实现”
    * “被来自 50 个国家的 200 所大学采用”
* **[labmlai/annotated_deep_learning_paper_implementations](https://github.com/labmlai/annotated_deep_learning_paper_implementations)** - “深度学习论文已实施，并附有注释” - “我们正在积极维护此存储库并几乎每周添加新的实施.”
 * **[大卫·汉弗莱 (David Humphrey) 的“[深度] 学习的乐趣”.](https://github.com/humphd/have-fun-with-machine-learning)** 这是“取得成功的绝佳方式”自己”和hack-first. 然后你会很兴奋地继续……
*  **[Prof. Andrew Ng's](https://www.andrewng.org/about/) [courses on Deep Learning](https://www.coursera.org/specializations/deep-learning)!** 有五门课程，作为课程的一部分 [Deep Learning Specialization on Coursera](https://www.coursera.org/specializations/deep-learning) . 这些课程是他新事业的一部分， [deeplearning.ai](https://www.deeplearning.ai)
* **[_Deep Learning_](http://www.deeplearningbook.org/)，麻省理工学院出版社出版的免费书籍.** 作者：Ian Goodfellow、Yoshua Bengio 和 Aaron Courville
* [Quora: "What are the best ways to pick up Deep Learning skills as an engineer?"](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer) — 由 Greg Brockman（OpenAI 的联合创始人兼 CTO，前 Stripe 的 CTO）回答
* [Distill.pub](https://distill.pub/about/) 发布了非常棒的可探索性解释.
  * ["Feature Visualization: How neural networks build up their understanding of images"](https://distill.pub/2017/feature-visualization/)
* [Creative Applications of Deep Learning with Tensorflow](https://github.com/pkmital/CADL)

### Easier sharing of deep learning models and demos

* **[replicate.ai](https://replicate.ai) 为了可重复的研究，“使共享正在运行的机器学习模型变得容易”**. 
    * 对于初学者，您可以尝试使用 GAN 和其他深度学习概念的一些模型.
    *加入/加入书签，以便您以后可以贡献自己的模型
    * 开源工具： [`cog`](https://github.com/replicate/cog), [`keepsake`](https://github.com/replicate/keepsake)

----

## Collaborate with Domain Experts

机器学习可以很强大，但它不是魔术.

每当您应用机器学习来解决问题时，您都将在某个特定的问题域中工作. 为了获得好的结果，您或您的团队需要“实质性专业知识”，也就是“领域知识”. 为自己学习你能做的事情......但你也应该**协作.** 如果与领域专家合作，你会获得更好的结果.  （什么是领域专家？见 [this useful subjective blurb old the ol' c2 wiki](http://wiki.c2.com/?DomainExpert) 或者 [Wikipedia entry](https://en.wikipedia.org/wiki/Subject-matter_expert#Domain_expert_(software)).)

### Machine Learning and User Experience (UX)

我说得再好不过了：

&gt; **机器学习不会弄清楚要解决什么问题.**如果你不符合人类的需求，你只会构建一个非常强大的系统来解决一个非常小的——或者可能不存在的——问题.

该报价来自 ["The UX of AI" by Josh Lovejoy](https://design.google/library/ux-ai/) . 换句话说， **[You Are Not The User](https://www.nngroup.com/articles/false-consensus/).** Suggested reading: [Martin Zinkevich's "Rules of ML Engineering", Rule #23: "You are not a typical end user"](https://developers.google.com/machine-learning/guides/rules-of-ml/#human_analysis_of_the_system)

---

## Big data

<details>
<summary>这里有一些关于大数据和机器学习的有用链接.
</summary>

* [10 things statistics taught us about big data analysis](https://simplystatistics.org/2014/05/22/10-things-statistics-taught-us-about-big-data-analysis/) （还有一些值得深思的食物： ["What Statisticians think about Data Scientists"](http://www.datasciencecentral.com/profiles/blogs/what-statisticians-think-about-data-scientists))
* ["Talking Machines" #12](http://www.thetalkingmachines.com/blog/2015/6/4/the-economic-impact-of-machine-learning-and-using-the-kernel-trick-to-dig-in-to-big-data) : 采访教授. 吴恩达（来自 [our main course, which has its own module on big data](https://www.coursera.org/learn/machine-learning) ); 这一集涵盖了一些与_高维_数据相关的问题
* ["Talking Machines" #15: "Really Really Big Data and Machine Learning in Business"](http://www.thetalkingmachines.com/blog/2015/7/16/really-really-big-data-and-machine-learning-in-business)
* 免费电子书，[_Getting Data Right: Tackling the Challenge of
   Big Data Volume and Variety_](https://www.tamr.com/landing-pages/getting-data-right/) 作者：Michael Stonebraker、Tom Davenport、James Markarian 等，O&#39;Reilly 出版. 你可以 [listen to an accompanying podcast](http://radar.oreilly.com/2015/06/the-future-of-data-at-scale.html) 也.

</details>

如果您正在使用数据密集型应用程序，我会推荐这本书：

* **[_Designing Data-Intensive Applications_](http://dataintensive.net) ** 由马丁·克莱普曼 (Martin Kleppman) 撰写.  （您可以通过 Safari Books 开始免费在线阅读.）它并非特定于机器学习，但您可以自己弥补这一差距.

## More Data Science materials

以下是一些额外的数据科学资源：

* **[Python Data Science Handbook, as Jupyter Notebooks](https://jakevdp.github.io/PythonDataScienceHandbook/)**
* 可访问的数据科学书籍，无需编码经验： [_Data Smart_ by John Foreman](https://www.goodreads.com/book/show/17682206-data-smart)
* [Data Science Workflow: Overview and Challenges](https://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext) （阅读文章*以及*约瑟夫·麦卡锡的评论）

### Optional: Bayesian Statistics and Machine Learning

From [the "Bayesian Machine Learning" overview on Metacademy](https://metacademy.org/roadmaps/rgrosse/bayesian_machine_learning):

 &gt; ... 贝叶斯思想在过去 20 年左右的时间里对机器学习产生了重大影响，因为它们在构建现实世界现象的结构化模型方面提供了灵活性. 算法的进步和不断增加的计算资源使得拟合以前被认为难以处理的丰富、高度结构化的模型成为可能.

<details>
<summary>这里有一些用于学习贝叶斯方法的很棒的资源.</summary>

两种资源都使用 Python， [PyMC](https://github.com/pymc-devs/pymc)，和 Jupyter 笔记本.

1. **免费书** _[Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)_. Made with a "computation/understanding-first, mathematics-second point of view." It's available in print too!
2. [Bayesian Modelling in Python](https://github.com/markdregan/Bayesian-Modelling-in-Python) . 这使用 [PyMC](https://github.com/pymc-devs/pymc), like #1.
 3.喜欢边玩边学？ 我也是. 尝试 [19 Questions](https://github.com/fulldecent/19-questions)，“一种机器学习游戏，它会向您提问并猜测您正在思考的对象”，并且**解释了正在使用的贝叶斯统计技术.**
</details>

----

## Finding Open-Source Libraries

* 书签 **[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)**，一个精选的列表 [awesome](https://github.com/bayandin/awesome-awesomeness) 机器学习库和软件.
* 书签 [Pythonidae](https://github.com/svaksha/pythonidae/blob/master/AI.md#machine-learning), 一个精选的列表 [awesome](https://github.com/bayandin/awesome-awesomeness) Python 语言中的库和软件 - 有一个关于机器学习的部分.
* 对于可能不在 PyPI、GitHub 等上的机器学习库，有 [MLOSS (Machine Learning Open Source Software)](http://mloss.org/software/) . 似乎有许多学术图书馆.
* 朱莉娅： [Julia.jl](https://github.com/svaksha/Julia.jl/blob/master/AI.md#machine-learning), 一个精选的列表 [awesome](https://github.com/bayandin/awesome-awesomeness) Julia 语言中的库和软件 - 有一个关于机器学习的部分.


----

## More ways to "Dive into Machine Learning"

以下是学习机器学习的其他一些指南. 它们可以作为本指南的替代或补充.

* [Example Machine Learning notebook, exercise, and guide](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb)  Randal S. Olson 博士. 在 Notebooks 部分也提到过，但它与本指南有相似的目标（介绍你，并告诉你下一步去哪里）. 丰富的“进一步阅读”部分.
* 云供应商的课程（可能特定于他们的工具/平台）
    * [Machine Learning Crash Course from Google](https://developers.google.com/machine-learning/crash-course/) 使用 TensorFlow API.
    *  [Amazon AWS](https://aws.amazon.com/training/learning-paths/machine-learning/) 亚马逊已向公众开放其内部培训，并提供认证.
* [Machine Learning for Developers](http://xyclade.github.io/MachineLearning/) 适合那些比 Python 更熟悉 Java 或 Scala 的人.
* [ageron/handson-ml2](https://github.com/ageron/handson-ml2) 又名 [_Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow_ by Aurélien Geron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
* [rasbt/python-machine-learning-book-3rd-edition](https://github.com/rasbt/python-machine-learning-book-3rd-edition) 又名 [_Python Machine Learning: Machine Learning and Deep Learning with Python, scikit-learn, and TensorFlow 2_ by Sebastian Raschka and Vahid Mirjalili](https://www.goodreads.com/book/show/25545994-python-machine-learning)
* [Machine Learning for Software Engineers, by Nam Vu](https://github.com/ZuzooVn/machine-learning-for-software-engineers) . 用他们的话说，这是一种“专为软件工程师设计的自上而下和结果至上的方法”. 绝对书签并使用它，以及 - 它可以回答很多问题并为您提供大量资源.
