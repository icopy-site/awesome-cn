## Dive into Machine Learning [![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 **嗨，您好！  本指南适合您：**

* **你是新来 [Machine Learning.](https://en.wikipedia.org/wiki/Machine_learning)**
* **你知道Python.**（至少基础知识！如果你想了解更多Python， [try this](https://github.com/hangtwenty/python-is-for-lovers))

 我先通过黑客攻击学习Python，然后再学习*.我想用机器学习来做这件事.  如果这是你的风格，请和我一起领先一步.

 _注意：_“数据”中有几个字段，机器学习只是一个.  了解背景情况很好： [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)

## Get your feet wet!

 我建议你尽快弄湿脚.  你会增强自信心.

## Tools you'll need

- [Python](https://www.python.org/) .  Python 3是最好的选择.
- [IPython and the Jupyter Notebook](http://ipython.org/) .  （FKA IPython和IPython Notebook.）
- 一些科学计算包：
	-  numpy
	- 熊猫
	-  scikit-learn
	-  matplotlib

您只需点击几下即可安装Python 3和所有这些软件包 [Anaconda Python distribution](https://www.anaconda.com/download/) .  Anaconda在数据科学和机器学习社区中很受欢迎.

 如果您使用的是Python 2.7，请不要担心.  您不必为本指南迁移到Python 3.  此外，如果您使用pip / virtualenv而不是Anaconda，那也没关系！  并重新：安装包，这是一个有用的文档： [conda vs. pip vs. virtualenv](https://conda.io/docs/commands.html#conda-vs-pip-vs-virtualenv-commands)

## Let's go!

**[Learn how to use IPython Notebook](http://opentechschool.github.io/python-data-intro/core/notebook.html) （5-10分钟）.**（你可以 [learn by screencast](https://www.youtube.com/watch?v=qb7FT68tcA8) 代替.）

现在，继续这个简短的练习（10分钟）：**[An introduction to machine learning with scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html) **.  在`ipython`或IPython Notebook中执行此操作.  这真的会增强你的信心.

[![I'll wait.](https://user-images.githubusercontent.com/2420688/29441281-00eff0c4-837f-11e7-9666-d653a1cd2372.jpeg)](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)

## What just happened?

 您只是使用[scikit-learn]对一些手写数字进行了分类.  整洁吧？

[scikit-learn]是Python中机器学习的首选库. [It's used widely.](http://scikit-learn.org/stable/testimonials/testimonials.html)  机器学习很难.  您会很高兴您的工具易于使用.

[scikit-learn]：http：//scikit-learn.org/stable/index.html

 我鼓励您查看[scikit-learn]主页，花大约5分钟查看策略名称（分类，回归等）及其应用程序.  不要点击了！  只是瞥一眼词汇.

## Dive in

## A Visual Introduction to Machine Learning

 让我们进一步了解机器学习，以及一些常见的想法和关注点.  读 ["A Visual Introduction to Machine Learning, Part 1"](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) 通过 [Stephanie Yee](https://twitter.com/stephaniejyee) and [Tony Chu](https://twitter.com/tonyhschu/).

[![A Visual Introduction to Machine Learning, Part 1](https://user-images.githubusercontent.com/2420688/29441234-a2028c98-837e-11e7-88f2-1ca5a94684f6.gif)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

 不会花很长时间.  这是一个美丽的介绍......尽量不要流口水！

## A Few Useful Things to Know about Machine Learning

 好.  让我们深入了解.

阅读**["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)** [Prof. Pedro Domingos](https://homes.cs.washington.edu/~pedrod/) .  它密集地包含有价值的信息，但不是不透明的.  作者明白，有很多“黑人艺术”和民间智慧，他们邀请你进来.

 花点时间玩这个.  做笔记.  如果您还不了解它，请不要担心.

整篇论文充满了价值，但我想说出两点：

  -  **仅数据还不够.**这就是科学与机器学习中的艺术相遇的地方.  引用多明戈斯：“......对学习知识的需求不应该令人惊讶.机器学习不是魔术;它不能从无到有.它的作用是从更少的东西中获得更多.编程，就像所有的工程，是一个很多工作：我们必须从零开始构建一切.学习更像农业，让大自然完成大部分工作.农民将种子与养分结合起来种植农作物.学习者将知识与数据相结合，以发展计划.“
  -  **更多数据胜过更聪明的算法.**听，程序员.  我们喜欢很酷的工具.  抵制重新发明轮子或过度设计解决方案的诱惑.  你的出发点是 [Do the Simplest Thing that Could _Possibly_ Work](http://www.artima.com/intv/simplest3.html) .  引用多明戈斯：“假设你已经构建了最好的功能集，但是你得到的分类器仍然不够准确.你现在能做什么？有两个主要选择：设计一个更好的学习算法，或者收集更多数据.[...]根据经验，一个拥有大量数据的愚蠢算法胜过一个数量适中的聪明算法.（毕竟，机器学习就是让数据完成繁重的工作.） “

 当您处理真正的机器学习问题时，在优化您的算法选择之前，您应该将精力集中在**领域知识**和**数据**上.  喜欢[做简单的事情]直到你__ve_增加复杂性.  你不应该急于进入神经网络，因为你觉得它们很酷.  为了改进您的模型，**获取更多数据.**然后使用您对问题的了解 [explore and process](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning)  数据.  在收集到足够的数据后，您应该只优化算法的选择，并且您已经很好地处理了它.

![What has the most impact in Machine Learning](https://user-images.githubusercontent.com/2420688/29441212-798d2bba-837e-11e7-90b1-21daaf8d7b73.png)

（图表的灵感来自于幻灯片 [Alex Pinto's talk, "Secure Because Math: A Deep-Dive on ML-Based Monitoring"](https://www.youtube.com/watch?v=TYVCVzEJhhQ).)

[做简单的事情]：http：//wiki.c2.com/？DoSimpleThings

## Just about time for a break...

休息之前，先抓一些播客. 

首先，下载 [an interview with Prof. Domingos on the _Data Skeptic_ podcast](https://dataskeptic.com/blog/episodes/2018/the-master-algorithm)  （2018）.  教授  多明戈斯写道 [the paper we read earlier](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) .  你也可以开始阅读他的书， [_The Master Algorithm_ by Prof. Pedro Domingos](https://www.goodreads.com/book/show/24612233-the-master-algorithm)，清晰易懂的机器学习概述. 

 接下来，订阅更多的机器学习和数据科学播客！  这些都是优秀的，省力的资源，您可以随意学习更多.  至 [learn effectively](https://www.coursera.org/learn/learning-how-to-learn)随着时间的推移，倾听大量的顶空. [Do not speed up your podcasts!](https://www.theringer.com/2017/8/2/16095364/inefficiency-week-podcasts-speed-comprehension-f0ea43949e42)

订阅_ **[Talking Machines](http://www.thetalkingmachines.com/)**_.

我建议这个听力顺序：

* **下载 ["Starting Simple"](http://www.thetalkingmachines.com/blog/2015/4/23/starting-simple-and-machine-learning-in-meds) 插曲，并尽快听.**它支持我们从多明戈斯读到的东西. [Ryan Adams](http://people.seas.harvard.edu/~rpa/)  如上所述，谈论开始简单.  亚当斯还强调了特征工程的重要性.  特征工程是多明戈斯所写的“知识”的练习.  在后面的一集中， [they share many concrete tips for feature engineering](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning).
*然后，随着时间的推移，您可以收听整个播客系列（从头开始）.

 想订阅更多播客？  这里 [a good listicle](https://towardsdatascience.com/5-data-science-ai-and-machine-learning-podcasts-to-listen-to-now-e5078b18d184) 的建议， [and another](https://mty.ai/blog/the-best-ai-podcasts/).

 好！  休息一下，回来时精神焕发.

----

## Play to learn

接下来，挑选**这些IPython笔记本中的一个或两个**并一起玩.

- [Face Recognition on a subset of the Labeled Faces in the Wild](http://nbviewer.jupyter.org/github/ogrisel/notebooks/blob/master/Labeled%20Faces%20in%20the%20Wild%20recognition.ipynb)
- [Machine Learning from Disaster](http://agconti.github.io/kaggle-titanic/)：使用泰坦尼克号数据，“演示基本数据调整，分析和可视化技术.显示监督机器学习技术的示例.”
- [Election Forecasting](https://github.com/jseabold/538model)：模型的复制 [Nate Silver](https://fivethirtyeight.com/contributors/nate-silver/) 用于预测2012年美国总统选举_纽约时报_.
- [An example Machine Learning notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb)：“让我们假装我们正在为一家刚刚获得资助的创业公司工作，创建一个智能手机应用程序，通过智能手机拍摄的照片自动识别花卉种类.我们的数据科学负责人已经完成了创建演示机器学习的任务从花中进行四次测量的模型（萼片长度，萼片宽度，花瓣长度和花瓣宽度），并根据这些测量结果单独识别物种.“
-  ClickSecurity的“数据黑客”系列（谢谢 [hummus](https://github.com/hummus)!)
	- [Detect Algorithmically Generated Domains](http://nbviewer.jupyter.org/github/ClickSecurity/data_hacking/blob/master/dga_detection/DGA_Domain_Detection.ipynb)
	- [Detect SQL Injection](http://nbviewer.jupyter.org/github/ClickSecurity/data_hacking/blob/master/sql_injection/sql_injection.ipynb)
	- [Java Class File Analysis](http://nbviewer.jupyter.org/github/ClickSecurity/data_hacking/blob/master/java_classification/java_classification.ipynb)：这个Java代码是恶意的还是良性的？
- 如果你想要更多的数据科学，请从中选择一个笔记本 [this excellent list of Data Science ipython notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) .  “不断更新的数据科学Python笔记本：Spark，Hadoop MapReduce，HDFS，AWS，Kaggle，scikit-learn，matplotlib，pandas，NumPy，SciPy和各种命令行.”
- 或更通用的教程/概述......
	- [Tutorial introduction to machine learning with sklearn](http://amueller.github.io/sklearn_tutorial/)
	- [An Introduction to Supervised Learning via Scikit Learn](http://bugra.github.io/work/notes/2014-11-22/an-introduction-to-supervised-learning-scikit-learn/)
	- [An Introduction to Unsupervised Learning via Scikit Learn](http://bugra.github.io/work/notes/2014-11-16/an-introduction-to-unsupervised-learning-scikit-learn/)

还有更多地方可以找到优秀的IPython笔记本：

* [A Gallery of Interesting IPython notebooks (wiki page on GitHub): Statistics, Machine Learning and Data Science](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#statistics-machine-learning-and-data-science)
* [Fabian Pedregosa's larger, automatic gallery](http://fa.bianp.net/blog/2015/ipythonjupyter-notebook-gallery/)


 _知道另一个伟大的笔记本吗？  请提交PR！_

----

## Immerse yourself

 现在你应该被迷住，渴望了解更多.  选择以下课程之一，然后开始学习.

## [Recommended course: Prof. Andrew Ng's _Machine Learning_ on Coursera](https://www.coursera.org/learn/machine-learning)

**[Prof. Andrew Ng's](http://www.andrewng.org/about/) [_Machine Learning_](https://www.coursera.org/learn/machine-learning)  是一个受欢迎和受尊敬的免费在线课程.  我已经看到了它 [recommended](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Cory-Hicks-1) [often.](https://www.coursetalk.com/providers/coursera/courses/machine-learning?page=1&sort=-content_rating#reviews) [And](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Xavier-Amatriain) [emphatically.](https://www.forbes.com/sites/anthonykosner/2013/12/29/why-is-machine-learning-cs-229-the-most-popular-course-at-stanford/)**

 如果你决定一个宠物项目，你可以随时随地玩，这样你就有办法运用你的知识.  你可以使用其中一个 [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets) .  请记住，IPython Notebook是你的朋友.

 此外，您应该获取一本深入的教科书作为参考.  两个最佳选择是 [_Understanding Machine Learning_ ](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/copy.html) and _[Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)_. You'll see these recommended as reference textbooks. [You only need to use one of the two options as your main reference; here's some context/comparison to help you pick which one is right for you.](https://github.com/hangtwenty/dive-into-machine-learning/issues/29) 您可以在这些链接上免费下载每本书作为PDF  - 所以抓住它们吧！

### Tips for studying

 *忙碌的日程安排？  读 [Ray Li's review of Prof. Andrew Ng's course](https://rayli.net/blog/data/coursera-machine-learning-review/) 一些有用的提示.
*回顾一些 ["Learning How to Learn"](https://www.coursera.org/learn/learning-how-to-learn/)  视频.  这只是关于如何一般地学习.  在课程中，他们 [advocate the learn-by-doing approach](https://www.coursera.org/learn/learning-how-to-learn/lecture/8IUbH/interview-with-dr-terrence-sejnowski) ，就像我们在这里做的那样.  您将获得易于应用的各种其他提示，但要大大提高您的时间投资效率.

## Other courses

 这里有一些我见过推荐的免费在线课程.  （机器学习，数据科学和相关主题.）

* [Prof. Pedro Domingos's introductory video series](https://homes.cs.washington.edu/~pedrod/) .  多明戈斯写了这篇论文 ["A Few Useful Things to Know About Machine Learning"](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)，本指南前面的建议.
* Kevin Markham的视频系列， [Intro to Machine Learning with scikit-learn](http://blog.kaggle.com/2015/04/08/new-video-series-introduction-to-machine-learning-with-scikit-learn/) ，从我们已经涵盖的内容开始，然后继续在一个舒适的地方.  在视频之后你可以做Markham [General Assembly's Data Science course.](https://github.com/justmarkham/DAT8)  互动.  马克姆的课程也在华盛顿特区亲自提供.
* [UC Berkeley's Data 8: The Foundations of Data Science](http://data8.org/) 课程和教科书 [Computational and Inferential Thinking](https://www.inferentialthinking.com/) 教授数据科学中的关键概念.
    *教科书还提供了数据科学的学术定义：**“数据科学是通过探索，预测和推理从大型和多样化的数据集中得出有用的结论”.**
    * [Prof. Michael I. Jordan](https://people.eecs.berkeley.edu/~jordan/) （与Spark相关）讨论了本课程的设计 [video](https://youtu.be/ggq7HiDO0OU?t=1227)
*数据科学课程作为IPython笔记本：
	* [Practical Data Science](http://radimrehurek.com/data_science_python/)
	* [Learn Data Science (an entire self-directed course!)](http://learnds.com/)
	*补充材料： [donnemartin/data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) .  “不断更新的数据科学Python笔记本：Spark，Hadoop MapReduce，HDFS，AWS，Kaggle，scikit-learn，matplotlib，pandas，NumPy，SciPy和各种命令行.”
* Mark A. Girolami教授 [Machine Learning Module (GitHub Mirror).](https://github.com/josephmisiti/machine-learning-module) 适合具有强大数学背景的人士.
*数据科学课件调查（更多选择你自己的冒险）
	* 查看 [Jack Golding's survey of Data Science courseware](https://www.quora.com/Is-it-worth-it-to-pay-9-*-49-for-a-data-science-specialization-on-Coursera/answer/Jack-Golding) .  包括Coursera&#39;s [Data Science Specialization](https://www.coursera.org/specializations/jhu-data-science)  有9门课程.  专业证书不是免费的，但如果您不关心证书，您可以免费参加1-by-1课程.  调查还包括 [Harvard CS109](http://cs109.github.io/2014/) 我在其他地方看过推荐的.
	* [Another epic Quora thread: How can I become a data scientist?](https://www.quora.com/How-can-I-become-a-data-scientist?redirected_qid=59455)
	*数据科学周刊 [Big List of Data Science Resources](https://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) 有个 [List of Data Science MOOCs](https://www.datascienceweekly.org/data-science-resources/data-science-moocs)
* [Advanced Statistical Computing (Vanderbilt BIOS8366)](http://stronginference.com/Bios8366/lectures.html) .  互动（很多IPython笔记本电脑素材）
* [Data Science (Harvard CS109)](http://cs109.github.io/2014/)


## Getting Help: Questions, Answers, Chats

从支持论坛和与您正在学习的课程相关的聊天开始.

查看 [datascience.stackexchange.com](https://datascience.stackexchange.com/) and [stats.stackexchange.com – such as the tag, _machine-learning_.](https://stats.stackexchange.com/questions/tagged/machine-learning?sort=frequent&pageSize=15) 有一些像这样的子评价 [/r/machinelearning](https://www.reddit.com/r/machinelearning).

关于Quora还有许多相关的讨论，例如： [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)

 在meatspace的帮助和社区，寻找聚会.  数据科学周刊 [Big List of Data Science Resources](http://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) 可以帮到你.

## Supplement: Learning Pandas well

你会想要更熟悉熊猫.

* **基本**： [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* **基本**： [Things in Pandas I Wish I'd Had Known Earlier](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb) （IPython笔记本）
*另一个有用的教程： [Real World Data Cleanup with Python and Pandas](https://trendct.org/2016/08/05/real-world-data-cleanup-with-python-and-pandas/)
* [Video series from Data School, about Pandas](https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y) .  “30种常见熊猫任务参考指南（加上6小时支持视频）.”
* [Useful Pandas Snippets](http://www.swegler.com/becky/blog/2014/08/06/useful-pandas-snippets/)
*以下是我发现的一些文档，特别有用，因为我继续学习：
	* [Cookbook](http://pandas.pydata.org/pandas-docs/stable/cookbook.html)
	* [Data Structures](http://pandas.pydata.org/pandas-docs/stable/dsintro.html), esp. [DataFrame](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe) 部分
	* [Reshaping by pivoting DataFrames](http://pandas.pydata.org/pandas-docs/version/0.15.0/reshaping.html)
	* [Computational tools](http://pandas.pydata.org/pandas-docs/stable/computation.html) and [StackExchange thread: "What is covariance in plain language?"](https://stats.stackexchange.com/questions/29713/what-is-covariance-in-plain-language)
	* [Group By (split, apply, and combine DataFrames)](http://pandas.pydata.org/pandas-docs/stable/groupby.html)
	* [Visualizing your DataFrames](http://pandas.pydata.org/pandas-docs/version/0.15.0/visualization.html)
*以后需要缩放时的书签
	* [The `odo` library](http://odo.readthedocs.io/) 用于在_many_格式之间进行转换.
	* [`dask`](https://dask.org/) ：类似熊猫的界面，但对于大于内存的数据和“引擎盖下”的并行性.  非常有趣，但只有在你升级时才需要. 

## Supplement: Cheat Sheets

 我遇到过一些好的备忘单.  （请 [submit a Pull Request](https://github.com/hangtwenty/dive-into-machine-learning/pulls) 添加其他有用的备忘单.）

- [scikit-learn algorithm cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
  -  [Metacademy：[机器学习]知识的包管理员]（http://hunch.net/?p=2714）.  机器学习概念的思维导图，每个都有很多细节.
- [Matplotlib / Pandas / Python cheat sheets](https://drive.google.com/drive/folders/0ByIrJAE4KMTtaGhRcXkxNHhmY2M).

## Assorted Opinions and Other Resources

## More Data Science materials

我不是在重复上面提到的材料，但是这里有一些其他数据科学资源：

* **极易获取的数据科学书籍： [_Data Smart_ by John Foreman](http://www.john-foreman.com/data-smart-book.html)**
* **[An entire self-directed course in Data Science, as a IPython Notebook](http://learnds.com/)**
* [Data Science Workflow: Overview and Challenges](https://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext) （阅读文章*以及*约瑟夫麦卡锡的评论）
*有趣的小IPython笔记本： [Web Scraping Indeed.com for Key Data Science Job Skills](http://nbviewer.jupyter.org/github/jmsteinw/Notebooks/blob/master/IndeedJobs.ipynb)
* Swami Chandrasekaran&#39;s ["Becoming a Data Scientist"](http://nirvacana.com/thoughts/becoming-a-data-scientist/) 是数据科学课程的简洁，可打印的图片

## Bayesian Statistics and Machine Learning

From [the "Bayesian Machine Learning" overview on Metacademy](https://metacademy.org/roadmaps/rgrosse/bayesian_machine_learning):

 &gt; ...贝叶斯思想在过去20年左右的时间里对机器学习产生了重大影响，因为它们在构建现实世界现象的结构化模型时提供了灵活性.  算法的进步和不断增加的计算资源使得可以适应以前被认为难以处理的丰富，高度结构化的模型.

 您可以通过学习以下资源之一来了解更多信息.  两种资源都使用Python， [PyMC](https://github.com/pymc-devs/pymc)和Jupyter笔记本.
* **免费书，** _[Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)._ Made with a "computation/understanding-first, mathematics-second point of view." It's available in print too!
* [Bayesian Modelling in Python](https://github.com/markdregan/Bayesian-Modelling-in-Python)

## Risks

“机器学习系统自动学习程序
数据.“Pedro Domingos，in ["A Few Useful Things to Know about Machine Learning."](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)  您生成的程序将需要维护.  与任何更快地创建程序的方式一样，您可以使用 [technical debt](https://en.wikipedia.org/wiki/Technical_debt).

这是摘要 [Machine Learning: The High-Interest Credit Card of Technical Debt](https://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/43146.pdf):

 &gt;机器学习为快速构建复杂系统提供了一个非常强大的工具包.  本文认为将这些快速获胜视为免费提供是危险的.  使用技术债务框架，我们注意到在应用机器学习时，在系统级别产生大量持续维护成本非常容易.  本文的目标是强调几种机器学习特定的风险因素和设计模式，尽可能避免或重构.  这些包括边界侵蚀，纠缠，隐藏的反馈循环，未申报的消费者，数据依赖性，外部世界的变化以及各种系统级反模式.

 如果您正在阅读本指南，则应阅读该文章.  你也可以 [listen to a podcast episode interviewing one of the authors of this paper](https://softwareengineeringdaily.com/2015/11/17/machine-learning-and-technical-debt-with-d-sculley/).

关于在生产中运行ML动力系统的挑战的更多文章：

  -  ** [“机器学习规则：[可靠] ML工程的最佳实践，”]（http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf）**作者：Martin Zinkevich，关于ML工程实践和模式在谷歌生产.  可选的： [accompanying video](http://cs.stanford.edu/~jsteinhardt/wildml2016nips/videos/1_2_Martin.wmv).
- [**"What’s your ML Test Score? A rubric for ML production systems"**](https://0586f9b3-a-62cb3a1a-s-sites.googlegroups.com/site/wildml2016nips/SculleyPaper1.pdf?attachauth=ANoY7crRjdpoElseeyOPu-wR0eV9Engf3Cm9LKs0PAB4j-nDQuw9gE426Ug2HM-0BZ7qJjtLHVtpgwbP6zfNYyE_2gWkU5ACKczAIuKCTHq9nT0JEGpEL5TCT3APmScXKkS8HTqhJz-wen6vbq9XeHh_M5Heg49ozxsIiGMzX7PvIKxpnvViDOBLNymVQOkxuvX0-xnQThxU9CjEWQH25vOwdpJi-VQl1w%3D%3D&attredirects=0) 作者：Eric Breck，Shanqing Cai，Eric Nielsen，Michael Salib，D.Sculley，Google.
- **[Surviving Data Science "at the Speed of Hype"](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype)**来自MailChimp的数据科学家John Foreman
- [The High Cost of Maintaining Machine Learning Systems](http://www.kdnuggets.com/2015/01/high-cost-machine-learning-technical-debt.html)
- [11 Clever Methods of Overfitting and How to Avoid Them](http://hunch.net/?p=22)
- [The Perilous World of Machine Learning for Fun and Profit: Pipeline Jungles and Hidden Feedback Loops](http://www.john-foreman.com/blog/the-perilous-world-of-machine-learning-for-fun-and-profit-pipeline-jungles-and-hidden-feedback-loops)


### Welcome to the Danger Zone

 所以你正在涉足机器学习.  你有黑客技能.  也许你在多明戈斯的意义上有一些“知识”（一些“实质性专业知识”或“领域知识”）.  该图略微改编自Drew Conway的“数据科学维恩图”.  它不适合我们，但它可能适用于：

[![Drew Conway's Data Science Venn Diagram, modified slightly](https://user-images.githubusercontent.com/2420688/29441268-f429d88c-837e-11e7-83ff-30874d832c89.png)](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram)

 **请不要在您还在危险区时将自己推销为机器学习专家.  不要制造不良产品或发布垃圾科学.  （还请 [don't be evil](https://arstechnica.co.uk/security/2016/02/the-nsas-skynet-program-may-be-killing-thousands-of-innocent-people/) .）本指南无法告诉您如何知道自己已经“成功”进入机器学习能力......更不用说专业知识了.  没有学校或其他机构，很难评估熟练程度.  对于自学成才的人来说，这是一个普遍的问题.

#### Towards Expertise

你需要**练习.** [On Hacker News, user olympus commented to say you could use competitions to practice and evaluate yourself](https://news.ycombinator.com/item?id=10508565). [Kaggle](https://www.kaggle.com/competitions) and [ChaLearn](http://www.chalearn.org/)  是机器学习比赛的中心.  你可以找到一些 [examples of code for popular Kaggle competitions here](https://github.com/apeeyush/machine-learning) .  对于较小的练习， [try HackerRank](https://www.hackerrank.com/domains/ai/machine-learning/page/1).

你还需要**理解.**你应该回顾一下Kaggle比赛获胜者对他们的解决方案所说的话， [for example, the "No Free Hunch" blog](http://blog.kaggle.com/). These might be over your head at first but once you're starting to understand and appreciate these, you know you're getting somewhere.

 竞争和挑战只是实践的一种方式.  但是你不应该限制自己 - 而且你也应该理解这一点 [Machine Learning isn't **all** about Kaggle competitions](https://jvns.ca/blog/2014/06/19/machine-learning-isnt-kaggle-competitions).

这是一种互补的练习方式：**做练习.**

 1. **提出问题.  开始自己的学习.** ["most important thing in data science is the question"](https://github.com/DataScienceSpecialization/courses/blob/master/01_DataScientistToolbox/03_02_whatIsData/index.Rmd#the-data-is-the-second-most-important-thing) ([Dr. Jeff T. Leek](https://github.com/jtleek) ）.  所以先从一个问题开始.  然后，找到 [real data](https://github.com/caesar0301/awesome-public-datasets) .  分析一下.  然后 ...
2. **传达结果.**当您有一个新的发现时，请联系同行评审.
 3. **修复问题.**学习.  分享你学到的东西.

 并重复一遍.  重新措辞，它符合 [scientific method](https://en.wikipedia.org/wiki/Scientific_method) ：制定问题（或问题陈述），创建假设，收集数据，分析数据和沟通结果.  （你应该 [watch this video about the scientific method in data science](http://101.datascience.community/2012/06/27/the-data-scientific-method/)和/或 [read this article](http://customerthink.com/getting-insights-using-data-science-skills-and-the-scientific-method/).)

 你怎么能提出有趣的问题？  这是一种方式.  每个星期天， [browse datasets](https://github.com/caesar0301/awesome-public-datasets)  并写下一些问题.  另外，注册 [Data is Plural](https://tinyletter.com/data-is-plural) ，有趣数据集的通讯;  看看这些，数据集，写下问题.  保持好奇.  当一个问题启发你时，开始一项研究.

这个建议，以做实践研究和从同行评审中学习，是基于 [a conversation](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-153934120) with [Dr. Randal S. Olson](http://www.randalolson.com/) .  以下是奥尔森的更多建议， [quoted with permission:](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-154135498)

 &gt;我认为最好的建议是告诉人们总是清楚地展示他们的方法并避免过度解释他们的结果.  作为专家的一部分是知道很少有明确的答案，特别是当你使用真实数据时.

 当您重复此过程时，您的实践研究将变得更加科学，有趣和专注.  这个过程中最重要的部分是同行评审.

#### Ask for Peer Review

以下是一些您可以联系同行评审的社区：

* [Cross-Validated: stats.stackexchange.com](https://stats.stackexchange.com/)
* [/r/DataIsBeautiful](https://reddit.com/r/DataIsBeautiful)
* [/r/DataScience](https://reddit.com/r/DataScience)
* [/r/MachineLearning](https://reddit.com/r/MachineLearning)
* [Hacker News: news.ycombinator.com](https://news.ycombinator.com) .  您可能想要提交为“显示HN”

 发布到任何一个，并要求反馈.  你会得到反馈.  你会学到很多东西.  当专家审查您的工作时，您将学到很多关于该领域的知识.  您还将练习一项关键技能：接受批判性反馈.

 当我阅读关于我的Pull请求的反馈时，首先我重复一遍，“我不会得到防御，我不会得到防御，我不会得到防御.”  在阅读有关机器学习工作的评论之前，您可能希望这样做.

----

## Collaborate with Domain Experts!

机器学习可以很强大，但它并不神奇.

 每当您应用机器学习来解决问题时，您将在某个特定的问题域中工作.  为了获得良好的结果，您或您的团队将需要“实质性专业知识”AKA“领域知识”.  了解您可以为自己做些什么......但您也应该**合作.**如果您与领域专家合作，您将获得更好的结果.  （什么是领域专家？请参阅 [Wikipedia entry](https://en.wikipedia.org/wiki/Subject-matter_expert)， 要么 [c2 wiki's rather subjective but useful blurb](http://wiki.c2.com/?DomainExpert).)

### :bow: A note about Machine Learning and User Experience (UX)

我不能说得更好：

&gt; **机器学习不会弄清楚要解决的问题.**如果你不符合人类需求，那么你只需构建一个非常强大的系统来解决一个非常小或者可能不存在的问题.

报价来自 ["The UX of AI" by  Josh Lovejoy](https://design.google/library/ux-ai/)，整篇文章很棒！

换一种说法， **[You Are Not The User](https://www.nngroup.com/articles/false-consensus/).**

今天我们是 [_surrounded_](https://en.wikipedia.org/wiki/Machine_learning#Applications)  通过利用机器学习的软件.  通常，结果直接面向用户，旨在增强用户体验.

 在开始将ML用于_your_软件之前，您应该更好地了解UX，以及ML和UX如何关联.  作为进入这一主题的非正式方式，从这开始：

* [Rule #23 of _Martin Zinkevich's Rules of ML Engineering_](https://developers.google.com/machine-learning/guides/rules-of-ml/#human_analysis_of_the_system)：**“您不是典型的最终用户.”**
*有一些很棒 [thoughtful discussions of this on Quora](https://www.quora.com/search?q=machine+learning+ux)

 然后，如果你认识一个在UX工作的同事或朋友，可以带他们去喝咖啡或午餐然后挑选他们的大脑.  我认为他们会有鼓励和谨慎的话.  你不会以任何方式成为专家，但也许它会帮助你知道是否/什么时候寻求帮助，审查或指导. 

Spoiler：你应该尽可能地与UX专家合作！

### :bow: A note about Machine Learning and Security (InfoSec, AppSec)

关于这个主题有一个很棒的BlackHat网络广播， [Secure Because Math: Understanding Machine Learning-Based Security Products.](https://www.blackhat.com/html/webcast/02192015-secure-because-math.html) 幻灯片是 [here](https://www.blackhat.com/html/webcast/02192015-secure-because-math.html), [video recording is here.](https://attendee.gotowebinar.com/recording/80449431422110210)  如果你使用ML推荐一些媒体，过度拟合可能是无害的.  如果你依靠ML来保护免受威胁，那么过度拟合可能会非常危险.  如果您对此空间感兴趣，请查看完整的演示文稿.

如果你想更深入地探索这个空间，下面的链接中有一个_lot_阅读材料：

* [Security Data Science and Machine Learning Guide](http://www.covert.io/the-definitive-security-datascience-and-machinelearning-guide/)
* [Awesome ML for Cybersecurity](https://github.com/jivoi/awesome-ml-for-cybersecurity)
* [Awesome AI Security](https://github.com/RandomAdversary/Awesome-AI-Security)
* [Awesome Adversarial Machine Learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning)

----


## Deep Learning

 在本指南的早期版本中，没有特定的“深度学习”部分.  我故意省略了它.  我认为我们跳得太远是没有效果的.  我也知道，如果你成为传统机器学习的专家，你将能够进入深度学习等高级科目，无论我是否将其纳入本指南.  我们只是想让你从这里开始！

 也许这是一种检查你的进步的方法：问问自己，深度学习看起来像魔术吗？  如果是这样，那就把它作为一个标志，表明你还没准备好专业地使用它.  让魅力激励你学习更多.  我读过一些人认为你可以孤立地学习深度学习;  我读过其他人推荐最好先掌握传统的机器学习.  为什么不从传统的机器学习开始，在那里发展你的推理和直觉？  在此之后，您将更容易学习深度学习.  完成所有这些后，您将能够解决各种有趣的问题.

无论如何，当您决定进入深度学习时，这里有一些有用的资源.

 * ** [“与[深度学习”一起享受David Humphrey的乐趣.]（https://github.com/humphd/have-fun-with-machine-learning）**这是一个“获得成功”的绝佳方式你自己“和黑客第一.  然后你会感到很兴奋，继续...
*  **[Prof. Andrew Ng's](https://www.andrewng.org/about/) [courses on Deep Learning](https://www.coursera.org/specializations/deep-learning)！**有五门课程，作为一部分 [Deep Learning Specialization on Coursera](https://www.coursera.org/specializations/deep-learning) .  这些课程是他新创业的一部分， [deeplearning.ai](https://www.deeplearning.ai)
* **[Machine Learning Crash Course from Google.](https://developers.google.com/machine-learning/crash-course/)**谷歌快速，实用的机器学习介绍，涵盖了使用TensorFlow构建深度神经网络.
* **[_Deep Learning_](http://www.deeplearningbook.org/)，麻省理工学院出版社出版的免费书籍.**伊恩·古德费罗，Yoshua Bengio和Aaron Courville
* [YerevaNN's Deep Learning Guide](http://yerevann.com/a-guide-to-deep-learning/)
* [Quora: "What are the best ways to pick up Deep Learning skills as an engineer?"](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer) - 由Greg Brockman回答（OpenAI的联合创始人兼首席技术官，Stripe的首席技术官）
* [Sonnet](https://github.com/deepmind/sonnet)   - 构建在TensorFlow之上的python库，用于构建复杂的神经网络.  由Google DeepMind制作.
* [Build a deep learning model in 15 minutes](https://tech.instacart.com/how-to-build-a-deep-learning-model-in-15-minutes-a3684c6f71e) 运用 [Lore](https://github.com/instacart/lore/).

## "Big" Data?

扩展数据分析现在是一个熟悉的问题，并且不乏解决它的方法. [Beware needless hype and companies selling you flashy, proprietary solutions.](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype)  您可以使用开源工具完成所有工作.  即使“购买”而不是“构建”，您也可以从使用已知良好堆栈的供应商处购买.  这里没有消息.

有 [other lists of Awesome Machine Learning tools](https://github.com/josephmisiti/awesome-machine-learning) 所以我不会重新做那一切.  但是在大数据部分，如果我没有提及，我将会失职......

* **[Apache Spark.](https://spark.apache.org/mllib/)**“MLlib是Apache Spark的可扩展机器学习库.”
	 *除了可扩展性，Spark还有很棒的API.  更重要的是， [Spark has DataFrames and easy co-operability with pandas!](https://databricks.com/blog/2015/02/17/introducing-dataframes-in-spark-for-large-scale-data-science.html)
	*伯克利有 [a course on Scalable Machine Learning, focusing on Apache Spark.](https://www.edx.org/course/scalable-machine-learning-uc-berkeleyx-cs190-1x#.VOC70VPF_lQ)

如果您正在使用数据密集型应用程序，我会推荐这本书：

* **[_Designing Data-Intensive Applications_](http://dataintensive.net) ** Martin Kleppman.  （您可以通过Safari Books免费在线阅读.）它并非特定于机器学习，但您可以自己弥补这一差距.

最后，这里有一些关于大数据和ML的其他有用的链接.

* [10 things statistics taught us about big data analysis](https://simplystatistics.org/2014/05/22/10-things-statistics-taught-us-about-big-data-analysis/) （还有一些值得深思的东西： ["What Statisticians think about Data Scientists"](http://www.datasciencecentral.com/profiles/blogs/what-statisticians-think-about-data-scientists))
* ["Talking Machines" #12](http://www.thetalkingmachines.com/blog/2015/6/4/the-economic-impact-of-machine-learning-and-using-the-kernel-trick-to-dig-in-to-big-data) ：访谈教授  Andrew Ng（来自 [our main course, which has its own module on big data](https://www.coursera.org/learn/machine-learning) ）;  本集涵盖了与_high-dimensional_数据相关的一些问题
- ["Talking Machines" #15: "Really Really Big Data and Machine Learning in Business"](http://www.thetalkingmachines.com/blog/2015/7/16/really-really-big-data-and-machine-learning-in-business)
- 免费电子书，[_获取数据权：应对挑战
 大数据量和多样性_（https://www.tamr.com/landing-pages/getting-data-right/）由Michael Stonebraker，Tom Davenport，James Markarian和其他人出版，由O&#39;Reilly出版.  您可以 [listen to an accompanying podcast](http://radar.oreilly.com/2015/06/the-future-of-data-at-scale.html) 太.

----

## Finding Open-Source Libraries

* 书签 **[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)**，精选的清单 [awesome](https://github.com/bayandin/awesome-awesomeness) 机器学习库和软件.
* 书签 [Pythonidae](https://github.com/svaksha/pythonidae/blob/master/AI.md#machine-learning)，精选的清单 [awesome](https://github.com/bayandin/awesome-awesomeness) Python语言中的库和软件 - 有关机器学习的部分.
* [TensorFlow](https://www.tensorflow.org/) 一直是 [really big deal.](https://news.ycombinator.com/item?id=10532957)  喜欢你的人会用TensorFlow做一些令人兴奋的事情.  这是一个框架.  框架可以帮助您管理复杂性.  请记住这条经验法则：**“更多数据胜过更聪明的算法”**（Domingos），无论你的工具有多酷.  另请注意，TensorFlow不是同类中唯一的机器学习框架：**[Check this great, detailed comparison of TensorFlow, Torch, and Theano.](https://github.com/zer0n/deepframeworks)** 也可以看看 [Newmu/Theano-Tutorials](https://github.com/Newmu/Theano-Tutorials) and  [nlintz/TensorFlow-Tutorials](https://github.com/nlintz/TensorFlow-Tutorials) .  另请参阅上面的深度学习部分.
    *另外，考虑一下 [Lore](https://github.com/instacart/lore/) .  “Lore是一个python框架，使机器学习[特别是深度学习]对于工程师来说是平易近人的，并且可以为数据科学家维护.” 
*对于可能不在PyPI，GitHub等上的机器学习库，有 [MLOSS (Machine Learning Open Source Software)](http://mloss.org/software/) .  似乎有许多学术图书馆.
* 书签 [Julia.jl](https://github.com/svaksha/Julia.jl/blob/master/AI.md#machine-learning)，精选的清单 [awesome](https://github.com/bayandin/awesome-awesomeness) Julia语言中的图书馆和软件 - 有关机器学习的部分.
* [CreativeAI.net](http://www.creativeai.net/) .  好吧不完全是_libraries_，但这通常很有趣，值得订阅...警告，很容易被吸进:)

----

## Alternative ways to "Dive into Machine Learning"

 以下是机器学习的其他指南.  它们可以是本指南的替代或补充.

* ["How would your curriculum for a machine learning beginner look like?"](https://sebastianraschka.com/faq/docs/ml-curriculum.html)  作者：Sebastian Raschka.  精选的核心在线课程和书籍，用于开始机器学习和获取专业知识.  它将Raschka自己的书置于语境中， [_Python Machine Learning_](https://github.com/rasbt/python-machine-learning-book) （无论如何我都会联系到这里！）另见 [`pattern_classification` GitHub repository](https://github.com/rasbt/pattern_classification) 由作者维护，其中包含有关各种机器学习算法和各种数据科学相关资源的IPython笔记本.
* [Materials for Learning Machine Learning](http://jacksimpson.co/materials-for-learning-machine-learning/) 杰克辛普森
* [Machine Learning Crash Course from Google](https://developers.google.com/machine-learning/crash-course/)  使用TensorFlow API.  这是Google快速，实用的机器学习入门，包括视频讲座，实际案例研究和动手练习练习等一系列课程.
* [Machine Learning for Developers](http://xyclade.github.io/MachineLearning/)  是另一个很好的介绍，如果您对Java或Scala更熟悉，可能会更好.  它使用Smile（一种可在Java和Scala中使用的机器学习库）为开发人员引入机器学习.
* [Example Machine Learning notebook, exercise, and guide](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb)  Randal S. Olson博士.  在笔记本部分也提到过，但它与本指南的目标相似（向您介绍，并告诉您下一步该怎么做）.  丰富的“进一步阅读”部分.
* [Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers)  由Nam Vu.  这是为软件工程师设计的自上而下和结果优先的方法.
*对于一些新闻来源，请查看 [Sam DeBrule's list](https://machinelearnings.co/a-humans-guide-to-machine-learning-e179f43b67a0) 这里.
* [Distill](https://distill.pub/about/)  是一本致力于对机器学习中最新研究的清晰和互动解释的期刊.  它们提供了传统学术出版物的替代方案，可以促进该领域的可及性和透明度.
* [你的导游在这里]
