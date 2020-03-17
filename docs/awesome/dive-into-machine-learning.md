<div class="github-widget" data-repo="hangtwenty/dive-into-machine-learning"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Dive into Machine Learning [![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 **嗨，您好！  本指南适合您：**

* **您是新手 [Machine Learning.](https://en.wikipedia.org/wiki/Machine_learning)**
* **您了解Python.**（至少是基础知识！如果您想了解更多Python， [try this](https://github.com/hangtwenty/python-is-for-lovers))

 我是通过首先黑客学习Python的，后来变得更认真.*我想通过机器学习来做到这一点.  如果这是您的风格，请和我一起领先一步.

<br/>

## [Does your employer support your growth?](https://github.com/hangtwenty/dive-into-machine-learning/blob/master/"https://triplebyte.com/iv/RoKMZpG/cp/header")

 如果您正在阅读本指南，则喜欢边做边学.  您的雇主应根据您的优势和兴趣为您提供项目.  如果没有，您应该继续前进！

<a href="https://triplebyte.com/iv/RoKMZpG/cp/header"><img align="right" src="https://user-images.githubusercontent.com/2420688/67127456-3f4b1700-f1ae-11e9-8cad-371212258d5c.png" width="300"  alt="Triplebyte"><a href="https://triplebyte.com/iv/RoKMZpG/cp/header">参加三字节编码测验，然后**让工作来找您.**</a> <a href="https://triplebyte.com/iv/RoKMZpG/cp/header">您可以使用我的链接来支持 .</a>

<br/>

## Let's get started

 我建议你先弄湿脚.  您会增强信心.

## Tools you'll need

- [Python](https://www.python.org/) .  Python 3是最好的选择.
- [IPython and the Jupyter Notebook](http://ipython.org/) .  （FKA IPython和IPython Notebook.）
-一些科学计算软件包：
	-麻木
	-大熊猫
	-scikit学习
	-matplotlib

您只需单击几下即可安装Python 3和所有这些软件包 [Anaconda Python distribution](https://www.anaconda.com/download/) .  Anaconda在数据科学和机器学习社区中很受欢迎.

 如果您使用的是Python 2.7，请不要担心.  您不必仅为本指南而迁移到Python 3.  另外，如果您使用的是pip / virtualenv而不是Anaconda，那也没关系！  并重新：安装软件包，这是一个有用的文档： [conda vs. pip vs. virtualenv](https://conda.io/docs/commands.html#conda-vs-pip-vs-virtualenv-commands)

## Let's go!

**[Learn how to use IPython Notebook](http://opentechschool.github.io/python-data-intro/core/notebook.html) （5-10分钟）.**（您可以 [learn by screencast](https://www.youtube.com/watch?v=qb7FT68tcA8) 代替.）

现在，遵循此简短练习（10分钟）：**[An introduction to machine learning with scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html) **.  在`ipython`或IPython Notebook中执行.  它将真正增强您的信心.

[![I'll wait.](https://user-images.githubusercontent.com/2420688/29441281-00eff0c4-837f-11e7-9666-d653a1cd2372.jpeg)](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)

## What just happened?

 您刚刚使用[scikit-learn]对一些手写数字进行了分类.  整洁吧？

[scikit-learn] is the go-to library for machine learning in Python. [It's used widely.](http://scikit-learn.org/stable/testimonials/testimonials.html) Machine learning is hard. You'll be glad your tools are easy to work with.

[scikit-learn]：http://scikit-learn.org/stable/index.html

 我鼓励您查看[scikit-learn]主页，并花费大约5分钟的时间查看策略的名称（分类，回归等）及其应用.  暂时不要点击！  只需看一下词汇表即可.

## Dive in

## A Visual Introduction to Machine Learning

 让我们进一步了解机器学习，以及一些常见的想法和问题.  读 ["A Visual Introduction to Machine Learning, Part 1"](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) 通过 [Stephanie Yee](https://twitter.com/stephaniejyee) 和 [Tony Chu](https://twitter.com/tonyhschu/).

[![A Visual Introduction to Machine Learning, Part 1](https://user-images.githubusercontent.com/2420688/29441234-a2028c98-837e-11e7-88f2-1ca5a94684f6.gif)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

 不会花很长时间.  这是一个美丽的介绍...尽量不要流口水！

## A Few Useful Things to Know about Machine Learning

 好.  让我们更深入.

阅读**["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)**由 [Prof. Pedro Domingos](https://homes.cs.washington.edu/~pedrod/) .  它挤满了有价值的信息，但并非不透明.  作者了解到，有很多“黑人艺术”和民间智慧，他们邀请您加入.

 慢慢来吧.  做笔记.  如果您还不了解所有内容，请不要担心.

整篇论文都充满了价值，但我想指出两点：

 -**仅数据是不够的.**这是科学与机器学习相遇的地方.  引用多明戈斯的话：“ ...学习中对知识的需求应该不足为奇.机器学习不是魔术；它不可能从一无所获.它所做的就是事半功倍.像所有工程学一样，编程是一种大量工作：我们必须从头开始构建所有内容.学习更像是农业，它可以让自然完成大部分工作.农民将种子与营养物结合起来种植农作物.学习者将知识与数据结合起来制定计划.”
 -**更多数据胜过更聪明的算法.**程序员，请注意.  我们喜欢很棒的工具.  抵制重新发明轮子或过度设计解决方案的诱惑.  您的出发点是 [Do the Simplest Thing that Could _Possibly_ Work](http://www.artima.com/intv/simplest3.html) .  引用多明戈斯的话：“假设您已经构建了最好的功能集，但是获得的分类器仍然不够准确.现在可以做什么？主要有两个选择：设计更好的学习算法或收集根据经验，有很多数据的愚蠢算法比有少量数据的聪明算法要好（毕竟，机器学习只不过是让数据承担繁重的工作.） ”

 当您处理真正的机器学习问题时，应在优化算法选择之前将精力集中在“领域知识”和“数据”上.  在增加复杂性之前，最好先参考[做简单的事情].  您不应急于进入神经网络，因为您认为它们很酷.  要改善模型，**获取更多数据.**然后使用对问题的了解来 [explore and process](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning)  数据.  只有在收集到足够的数据并且处理好之后，才应该优化算法的选择.

![What has the most impact in Machine Learning](https://user-images.githubusercontent.com/2420688/29441212-798d2bba-837e-11e7-90b1-21daaf8d7b73.png)

（图表的灵感来自于 [Alex Pinto's talk, "Secure Because Math: A Deep-Dive on ML-Based Monitoring"](https://www.youtube.com/watch?v=TYVCVzEJhhQ).)

[做简单的事情]：http：//wiki.c2.com/？DoSimpleThings

## Jargon note

* [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1) 
*另一个方便的术语： [_**Data Engineering**_](https://towardsdatascience.com/who-is-a-data-engineer-how-to-become-a-data-engineer-1167ddc12811?gi=67df10cc32ea)，可能涉及或支持机器学习，但不仅限于机器学习.

## Just about time for a break...

在您休息之前，请获取一些播客. 

一，下载 [an interview with Prof. Domingos on the _Data Skeptic_ podcast](https://dataskeptic.com/blog/episodes/2018/the-master-algorithm)  （2018）.  教授  多明戈斯写道 [the paper we read earlier](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) .  您可能还开始阅读他的书， [_The Master Algorithm_ by Prof. Pedro Domingos](https://www.goodreads.com/book/show/24612233-the-master-algorithm)，这是一个清晰易懂的机器学习概述. 

Next, subscribe to more machine learning and data science podcasts! These are great, low-effort resources that you can casually learn more from. To [learn effectively](https://www.coursera.org/learn/learning-how-to-learn)，随着时间的流逝，留有足够的顶部空间. [Do not speed up your podcasts!](https://www.theringer.com/2017/8/2/16095364/inefficiency-week-podcasts-speed-comprehension-f0ea43949e42)

订阅_ **[Talking Machines](http://www.thetalkingmachines.com/)**_.

我建议以下收听顺序：

* **下载 ["Starting Simple"](http://www.thetalkingmachines.com/episodes/starting-simple-and-machine-learning-meds) 剧集，并尽快收听.**它支持我们从多明戈斯那里读到的内容. [Ryan Adams](http://people.seas.harvard.edu/~rpa/)  如上所述，我们讨论了从简单开始.  Adams还强调了特征工程的重要性.  功能工程是Domingos编写的“知识”的练习.  在以后的一集中 [they share many concrete tips for feature engineering](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning).
*然后，随着时间的流逝，您可以收听整个播客系列（从头开始）.

 想订阅更多播客吗？  这是 [a good listicle](https://towardsdatascience.com/5-data-science-ai-and-machine-learning-podcasts-to-listen-to-now-e5078b18d184) 建议， [and another](https://mty.ai/blog/the-best-ai-podcasts/).

 好！  休息片刻，再回来刷新.

----

## Play to learn

接下来，选择这些IPython笔记本中的“一两个”并一起玩.

- [Face Recognition on a subset of the Labeled Faces in the Wild](http://nbviewer.jupyter.org/github/ogrisel/notebooks/blob/master/Labeled%20Faces%20in%20the%20Wild%20recognition.ipynb)
- [Machine Learning from Disaster](http://agconti.github.io/kaggle-titanic/)：使用Titanic数据，“演示基本的数据处理，分析和可视化技术.显示有监督的机器学习技术的示例.”
- [Election Forecasting](https://github.com/jseabold/538model)：模型的复制 [Nate Silver](https://fivethirtyeight.com/contributors/nate-silver/) 曾对《纽约时报》的2012年美国总统大选做出预测.
- [An example Machine Learning notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb)：“假设我们正在为一家刚获得资金的初创公司工作，该初创公司创建了一个智能手机应用程序，该应用程序可以从智能手机上拍摄的照片中自动识别花朵的种类.数据科学负责人已委托我们创建演示机器学习可以从花朵上进行四次测量的模型（掌长，萼片宽度，花瓣长度和花瓣宽度），并仅根据这些测量来识别物种.”
-ClickSecurity的“数据黑客”系列（感谢 [hummus](https://github.com/hummus)!)
	- [Detect Algorithmically Generated Domains](http://nbviewer.jupyter.org/github/ClickSecurity/data_hacking/blob/master/dga_detection/DGA_Domain_Detection.ipynb)
	- [Detect SQL Injection](http://nbviewer.jupyter.org/github/ClickSecurity/data_hacking/blob/master/sql_injection/sql_injection.ipynb)
	- [Java Class File Analysis](http://nbviewer.jupyter.org/github/ClickSecurity/data_hacking/blob/master/java_classification/java_classification.ipynb)：此Java代码是恶意的还是良性的？
-如果您希望更多地关注数据科学，请从 [this excellent list of Data Science ipython notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) .  “不断更新的数据科学Python笔记本：Spark，Hadoop MapReduce，HDFS，AWS，Kaggle，scikit-learn，matplotlib，pandas，NumPy，SciPy和各种命令行.”
-或更通用的教程/概述...
	- [Tutorial introduction to machine learning with sklearn](http://amueller.github.io/sklearn_tutorial/)
	- [An Introduction to Supervised Learning via Scikit Learn](http://bugra.github.io/work/notes/2014-11-22/an-introduction-to-supervised-learning-scikit-learn/)
	- [An Introduction to Unsupervised Learning via Scikit Learn](http://bugra.github.io/work/notes/2014-11-16/an-introduction-to-unsupervised-learning-scikit-learn/)

还有更多找到出色的IPython Notebook的地方：

* [A Gallery of Interesting IPython notebooks (wiki page on GitHub): Statistics, Machine Learning and Data Science](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#statistics-machine-learning-and-data-science)
* [Fabian Pedregosa's larger, automatic gallery](https://web.archive.org/web/20180227081121/http://nb.bianp.net/sort/views/)

 _知道另一个很棒的笔记本吗？  请提交PR！_

----

## Immerse yourself

 现在，您应该着迷了，并渴望了解更多信息.  选择以下课程之一，然后开始前进.

## [Recommended course: Prof. Andrew Ng's _Machine Learning_ on Coursera](https://www.coursera.org/learn/machine-learning)


 如果您决定随身携带一个宠物项目，这将很有帮助，因此您可以运用自己的知识.  您可以使用其中之一 [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets) .  记住，IPython Notebook是您的朋友.

 此外，您还应该阅读一本深入的教科书以用作参考.  最好的两个选择是 [_Underst和ing Machine Learning_ ](http://www.cs.huji.ac.il/~shais/Underst和ingMachineLearning/copy.html) 和 _[Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)_. You'll see these recommended as reference textbooks. [You only need to use one of the two options as your main reference; here's some context/comparison to help you pick which one is right for you.](https://github.com/hangtwenty/dive-into-machine-learning/issues/29) 您可以在这些链接处免费以PDF格式下载每本书-因此抓住它们吧！

### Tips for studying

 *繁忙的时间表？  读 [Ray Li's review of Prof. Andrew Ng's course](https://rayli.net/blog/data/coursera-machine-learning-review/) 一些有用的提示.
*查看一些 ["Learning How to Learn"](https://www.coursera.org/learn/learning-how-to-learn/)  视频.  这只是关于一般学习的方法.  在课程中，他们 [advocate the learn-by-doing approach](https://www.coursera.org/learn/learning-how-to-learn/lecture/8IUbH/interview-with-dr-terrence-sejnowski) ，就像我们在这里所做的那样.  您将获得各种易于使用的其他技巧，但要使您的时间投入更有效，还有很长的路要走.

## Other courses

 这是我推荐的其他一些免费在线课程.  （机器学习，数据科学和相关主题.）

* [Prof. Pedro Domingos's introductory video series](https://homes.cs.washington.edu/~pedrod/) .  多明戈斯写了这篇论文 ["A Few Useful Things to Know About Machine Learning"](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)，在本指南前面建议.
* Kevin Markham的视频系列 [Intro to Machine Learning with scikit-learn](http://blog.kaggle.com/2015/04/08/new-video-series-introduction-to-machine-learning-with-scikit-learn/) ，从我们已经介绍的内容开始，然后在一个舒适的地方继续.  视频播放后，您可以做Markham&#39;s [General Assembly's Data Science course.](https://github.com/justmarkham/DAT8)  互动.  万锦市的课程也在华盛顿特区亲自授课.
* [UC Berkeley's Data 8: The Foundations of Data Science](http://data8.org/) 课程和教科书 [Computational and Inferential Thinking](https://www.inferentialthinking.com/) 讲授数据科学中的关键概念.
    *教科书还提供了数据科学的学术定义：**“数据科学是关于通过探索，预测和推理从庞大而多样的数据集中得出有用的结论”.**
    * [Foundations of Data Science](https://www.edx.org/professional-certificate/berkeleyx-foundations-of-data-science) 现在，也可以通过edX提供基于Data 8的在线课程.
*作为IPython笔记本的数据科学课程：
	* [Practical Data Science](http://radimrehurek.com/data_science_python/)
	* [Learn Data Science (an entire self-directed course!)](http://learnds.com/)
	*补充材料： [donnemartin/data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) .  “不断更新的数据科学Python笔记本：Spark，Hadoop MapReduce，HDFS，AWS，Kaggle，scikit-learn，matplotlib，pandas，NumPy，SciPy和各种命令行.”
*马克·A·吉罗拉米教授 [Machine Learning Module (GitHub Mirror).](https://github.com/josephmisiti/machine-learning-module) 适用于具有强大数学背景的人.
*数据科学课件调查（更多“选择自己的冒险”）
	* 查看 [Jack Golding's survey of Data Science courseware](https://www.quora.com/Is-it-worth-it-to-pay-9-*-49-for-a-data-science-specialization-on-Coursera/answer/Jack-Golding) .  包括Coursera [Data Science Specialization](https://www.coursera.org/specializations/jhu-data-science)  其中有9门课程.  专业证书不是免费的，但是如果您不关心证书，则可以免费按1比1的课程学习.  该调查还涵盖 [Harvard CS109](http://cs109.github.io/2014/) 我在其他地方看到过推荐.
	* [Another epic Quora thread: How can I become a data scientist?](https://www.quora.com/How-can-I-become-a-data-scientist?redirected_qid=59455)
	*数据科学周刊 [Big List of Data Science Resources](https://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) 有一个 [List of Data Science MOOCs](https://www.datascienceweekly.org/data-science-resources/data-science-moocs)
* [Advanced Statistical Computing (Vanderbilt BIOS8366)](http://stronginference.com/Bios8366/lectures.html) .  交互式（很多IPython Notebook材料）
* [Data Science (Harvard CS109)](http://cs109.github.io/2014/)


## Getting Help: Questions, Answers, Chats

从支持论坛和与您所修课程有关的聊天开始.

查看 [datascience.stackexchange.com](https://datascience.stackexchange.com/) 和 [stats.stackexchange.com – such as the tag, _machine-learning_.](https://stats.stackexchange.com/questions/tagged/machine-learning?sort=frequent&pageSize=15) 有一些子问题，例如 [/r/machinelearning](https://www.reddit.com/r/machinelearning).

关于Quora的讨论也很多，例如： [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)

 在肉空间中寻求帮助和社区，请参加聚会.  数据科学周刊 [Big List of Data Science Resources](http://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) 可能会帮助您.

## Supplement: Learning Pandas well

您将要更加熟悉熊猫.

* **基本**： [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* **基本**： [Things in Pandas I Wish I'd Had Known Earlier](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb) （IPython笔记本）
*另一个有用的教程： [Real World Data Cleanup with Python and Pandas](https://trendct.org/2016/08/05/real-world-data-cleanup-with-python-and-pandas/)
* [Video series from Data School, about Pandas](https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y) .  “参考指南，介绍30个常见的熊猫任务（加上6个小时的支持视频）.”
* [Useful Pandas Snippets](http://www.swegler.com/becky/blog/2014/08/06/useful-pandas-snippets/)
*以下是我在继续学习中发现特别有用的一些文档：
	* [Cookbook](http://pandas.pydata.org/pandas-docs/stable/cookbook.html)
	* [Data Structures](http://pandas.pydata.org/pandas-docs/stable/dsintro.html)，尤其是 [DataFrame](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe) 部分
	* [Reshaping by pivoting DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/reshaping.html)
	* [Computational tools](http://p和as.pydata.org/p和as-docs/stable/computation.html) 和 [StackExchange thread: "What is covariance in plain language?"](https://stats.stackexchange.com/questions/29713/what-is-covariance-in-plain-language)
	* [Group By (split, apply, and combine DataFrames)](http://pandas.pydata.org/pandas-docs/stable/groupby.html)
	* [Visualizing your DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html)
*书签，供以后需要缩放时使用
	* [The `odo` library](http://odo.readthedocs.io/) 用于在_many_格式之间进行转换.
	* [`dask`](https://dask.org/) ：类似于Pandas的界面，但用于大于内存的数据和“底层”并行性.  非常有趣，但仅在您变得高级时才需要. 

## Supplement: Cheat Sheets

 我遇到过一些很好的备忘单.  （请 [submit a Pull Request](https://github.com/hangtwenty/dive-into-machine-learning/pulls) 添加其他有用的备忘单.）

- [scikit-learn algorithm cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
 -[Metacademy：用于[机器学习]知识的程序包管理器]（http://hunch.net/?p=2714）.  机器学习概念的思维导图，每个概念都有非常详细的信息.
- [Matplotlib / Pandas / Python cheat sheets](https://drive.google.com/drive/folders/0ByIrJAE4KMTtaGhRcXkxNHhmY2M).

## Assorted Opinions and Other Resources

## More Data Science materials

我不再重复上面提到的材料，但是这里有一些其他数据科学资源：

* **极易访问的数据科学书： [_Data Smart_ by John Foreman](http://www.john-foreman.com/data-smart-book.html)**
* **[An entire self-directed course in Data Science, as a IPython Notebook](http://learnds.com/)**
* [Data Science Workflow: Overview and Challenges](https://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext) （请阅读文章*，以及* Joseph McCarthy的评论）
*有趣的IPython Notebook： [Web Scraping Indeed.com for Key Data Science Job Skills](http://nbviewer.jupyter.org/github/jmsteinw/Notebooks/blob/master/IndeedJobs.ipynb)
*斯瓦米·钱德拉塞卡兰（Swami Chandrasekaran） ["Becoming a Data Scientist"](http://nirvacana.com/thoughts/becoming-a-data-scientist/) 是数据科学课程的简洁，可打印的图片
* [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook) 是您可以在Internet上找到的最好的入门级书籍之一.


## Bayesian Statistics and Machine Learning

From [the "Bayesian Machine Learning" overview on Metacademy](https://metacademy.org/roadmaps/rgrosse/bayesian_machine_learning):

 &gt; ...在过去的20年左右的时间里，贝叶斯思想在机器学习中产生了巨大的影响，因为它们在构建现实世界现象的结构化模型中提供了灵活性.  算法的进步和不断增长的计算资源使人们有可能拟合以前认为难处理的丰富，高度结构化的模型.

 您可以通过研究以下资源之一来了解更多信息.  两种资源都使用Python， [PyMC](https://github.com/pymc-devs/pymc)和Jupyter笔记本.
* **免费书籍** _[Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)._ Made with a "computation/understanding-first, mathematics-second point of view." It's available in print too!
* [Bayesian Modelling in Python](https://github.com/markdregan/Bayesian-Modelling-in-Python)

## Risks

“机器学习系统会自动从
日期.“ Pedro Domingos，在 ["A Few Useful Things to Know about Machine Learning."](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)  您生成的程序将需要维护.  与以更快的速度创建程序的任何方式一样，您可以 [technical debt](https://en.wikipedia.org/wiki/Technical_debt).

这是摘要 [Machine Learning: The High-Interest Credit Card of Technical Debt](https://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/43146.pdf):

 &gt;机器学习提供了功能强大的工具包，可快速构建复杂的系统.  本文认为，将这些快速胜利视为免费是危险的.  使用技术债务框架，我们注意到在应用机器学习时，很容易在系统级别上承担大量的日常维护成本.  本文的目的是强调几种机器学习的特定风险因素和设计模式，这些风险和设计模式应尽可能避免或重构.  其中包括边界侵蚀，纠缠，隐藏的反馈循环，未声明的使用者，数据依赖项，外部世界的变化以及各种系统级反模式.

 如果您遵循本指南，则应阅读该论文.  你也可以 [listen to a podcast episode interviewing one of the authors of this paper](https://softwareengineeringdaily.com/2015/11/17/machine-learning-and-technical-debt-with-d-sculley/).

关于在生产环境中运行以ML为动力的系统所面临的挑战的更多文章：

 -** [Martin Zinkevich撰写的[“机器学习规则：[可靠] ML工程的最佳实践，”]（http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf）**关于ML工程实践和模式在Google生产中.  可选的： [accompanying video](http://cs.stanford.edu/~jsteinhardt/wildml2016nips/videos/1_2_Martin.wmv).
- [**"What’s your ML Test Score? A rubric for ML production systems"**](https://0586f9b3-a-62cb3a1a-s-sites.googlegroups.com/site/wildml2016nips/SculleyPaper1.pdf?attachauth=ANoY7crRjdpoElseeyOPu-wR0eV9Engf3Cm9LKs0PAB4j-nDQuw9gE426Ug2HM-0BZ7qJjtLHVtpgwbP6zfNYyE_2gWkU5ACKczAIuKCTHq9nT0JEGpEL5TCT3APmScXKkS8HTqhJz-wen6vbq9XeHh_M5Heg49ozxsIiGMzX7PvIKxpnvViDOBLNymVQOkxuvX0-xnQThxU9CjEWQH25vOwdpJi-VQl1w%3D%3D&attredirects=0) 作者：埃里克·布雷克（Eric Breck），蔡善清（Chanqing Cai），埃里克·尼尔森（Eric Nielsen），迈克尔·萨利布（Michael Salib），斯卡利（D.Sculley），谷歌.
- **[Surviving Data Science "at the Speed of Hype"](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype)** MailChimp的数据科学家John Foreman
- [The High Cost of Maintaining Machine Learning Systems](http://www.kdnuggets.com/2015/01/high-cost-machine-learning-technical-debt.html)
- [11 Clever Methods of Overfitting and How to Avoid Them](http://hunch.net/?p=22)
- [The Perilous World of Machine Learning for Fun and Profit: Pipeline Jungles and Hidden Feedback Loops](http://www.john-foreman.com/blog/the-perilous-world-of-machine-learning-for-fun-and-profit-pipeline-jungles-and-hidden-feedback-loops)


### Welcome to the Danger Zone

 因此，您正在涉足机器学习.  你有黑客技巧.  也许您在多明戈斯的意义上有一些“知识”（一些“实质专长”或“领域知识”）.  该图是从Drew Conway的“数据科学维恩图”中稍作修改的.  这不是适合我们的_perfect_，但它可能会说明问题：

[![Drew Conway's Data Science Venn Diagram, modified slightly](https://user-images.githubusercontent.com/2420688/29441268-f429d88c-837e-11e7-83ff-30874d832c89.png)](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram)

 **请**当您仍处于危险区域时，请勿以机器学习专家的身份推销自己.  不要制造不良产品或发布垃圾科学.  （也请 [don't be evil](https://arstechnica.co.uk/security/2016/02/the-nsas-skynet-program-may-be-killing-thousands-of-innocent-people/) .）本指南无法告诉您如何将自己“融入”机器学习能力中，更不用说专业知识了.  没有学校或其他机构，很难评估熟练程度.  对于自学成才的人来说这是一个普遍的问题.

#### Towards Expertise

您需要**练习.** [On Hacker News, user olympus commented to say you could use competitions to practice 和 evaluate yourself](https://news.ycombinator.com/item?id=10508565). [Kaggle](https://www.kaggle.com/competitions) 和 [ChaLearn](http://www.chalearn.org/)  是机器学习竞赛的中心.  你可以找到一些 [examples of code for popular Kaggle competitions here](https://github.com/apeeyush/machine-learning) .  对于较小的练习， [try HackerRank](https://www.hackerrank.com/domains/ai/machine-learning/page/1).

您还需要了解.**您应该查看Kaggle竞赛获胜者对他们的解决方案的评价， [for example, the "No Free Hunch" blog](http://blog.kaggle.com/) .  这些一开始可能会让人感到头疼，但是一旦您开始理解和欣赏它们，就知道自己正在走向某个领域.

 竞争和挑战只是实践的一种方式.  但是，您不应该限制自己-并且还应该了解 [Machine Learning isn't **all** about Kaggle competitions](https://jvns.ca/blog/2014/06/19/machine-learning-isnt-kaggle-competitions).

这是一种练习的补充方法：**进行练习研究.**

 1. **问一个问题.  开始自己的学习.** ["most important thing in data science is the question"](https://github.com/DataScienceSpecialization/courses/blob/master/01_DataScientistToolbox/03_02_whatIsData/index.Rmd#the-data-is-the-second-most-important-thing) ([Dr. Jeff T. Leek](https://github.com/jtleek) ）.  因此，从一个问题开始.  然后找到 [real data](https://github.com/caesar0301/awesome-public-datasets) .  分析一下.  然后 ...
2. **传达结果.**当您发现新发现时，请与他人进行同行评审.
 3. **修复问题.**学习.  分享您所学.

 重复一遍.  重新措辞，它适合 [scientific method](https://en.wikipedia.org/wiki/Scientific_method) ：制定问题（或问题陈述），创建假设，收集数据，分析数据并传达结果.  （你应该 [watch this video about the scientific method in data science](http://101.datascience.community/2012/06/27/the-data-scientific-method/)和/或 [read this article](http://customerthink.com/getting-insights-using-data-science-skills-and-the-scientific-method/).)

 您如何提出有趣的问题？  这是一种方法.  每个星期天， [browse datasets](https://github.com/caesar0301/awesome-public-datasets)  并写下一些问题.  另外，注册 [Data is Plural](https://tinyletter.com/data-is-plural) ，一个有趣的数据集通讯；  查看这些数据集并写下问题.  保持好奇心.  当有问题启发您时，请开始研究.

该建议用于进行实践研究并从同行评审中学习，是基于 [a conversation](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-153934120) 与 [Dr. Randal S. Olson](http://www.randalolson.com/) .  这是奥尔森的更多建议， [quoted 与 permission:](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-154135498)

 &gt;我认为最好的建议是告诉人们始终清楚地展示他们的方法，并避免过度解释他们的结果.  成为专家的一部分是知道很少有一个明确的答案，尤其是当您使用真实数据时.

 当您重复此过程时，您的实践研究将变得更加科学，有趣和专注.  此过程中最重要的部分是同行评审.

#### Ask for Peer Review

您可以在以下社区中进行同行评审：

* [Cross-Validated: stats.stackexchange.com](https://stats.stackexchange.com/)
* [/r/DataIsBeautiful](https://reddit.com/r/DataIsBeautiful)
* [/r/DataScience](https://reddit.com/r/DataScience)
* [/r/MachineLearning](https://reddit.com/r/MachineLearning)
* [Hacker News: news.ycombinator.com](https://news.ycombinator.com) .  您可能要提交为“ Show HN”

 发布到任何一个，并寻求反馈.  您会得到反馈.  您会学到很多.  当专家审查您的工作时，您将学到很多有关该领域的知识.  您还将练习一项关键技能：接受关键反馈.

 当我阅读有关“拉取请求”的反馈时，首先我要对自己重复：“我不会防御，我不会防御，我也不会防御.”  在阅读有关机器学习工作的评论之前，您可能需要这样做.

----

## Collaborate with Domain Experts!

机器学习可以强大，但不是魔术.

 每当您应用机器学习来解决问题时，您都将在特定的问题领域中工作.  为了获得良好的结果，您或您的团队将需要“专业知识”，也就是“领域知识”.  了解自己可以做的事情...但是您也应该**合作.**如果您与域名专家合作，将会获得更好的结果.  （什么是域名专家？请参阅 [Wikipedia entry](https://en.wikipedia.org/wiki/Subject-matter_expert)， 要么 [c2 wiki's rather subjective but useful blurb](http://wiki.c2.com/?DomainExpert).)

### :bow: A note about Machine Learning and User Experience (UX)

我无法说得更好：

&gt; **机器学习无法解决要解决的问题.**如果您不符合人类的需求，那么您将建立一个非常强大的系统来解决非常小的（甚至可能根本不存在的）问题.

报价来自 ["The UX of AI" by  Josh Lovejoy](https://design.google/library/ux-ai/)，整篇文章很棒！

换一种说法， **[You Are Not The User](https://www.nngroup.com/articles/false-consensus/).**

今天我们是 [_surrounded_](https://en.wikipedia.org/wiki/Machine_learning#Applications)  通过利用机器学习的软件.  通常，结果直接面向用户，旨在增强用户体验.

 在开始将ML应用于_your_软件之前，您应该对UX以及ML和UX之间的关系有更好的了解.  作为进入该主题的非正式方式，请从以下开始：

* [Rule #23 of _Martin Zinkevich's Rules of ML Engineering_](https://developers.google.com/machine-learning/guides/rules-of-ml/#human_analysis_of_the_system)：**“您不是典型的最终用户.” **
*有一些很棒 [thoughtful discussions of this on Quora](https://www.quora.com/search?q=machine+learning+ux)

 然后，如果您认识在UX中工作的同事或朋友，请带他们出去喝咖啡或吃午餐，然后动动脑筋.  我认为他们会有鼓励和谨慎的话.  您绝不会成为专家，但也许会在/何时寻求帮助，评论或指导来帮助您确定. 

剧透：您应该尽可能与UX专家合作！

### :bow: A note about Machine Learning and Security (InfoSec, AppSec)

有关此主题的BlackHat直播非常棒， [Secure Because Math: Understanding Machine Learning-Based Security Products.](https://www.blackhat.com/html/webcast/02192015-secure-because-math.html) 幻灯片是 [here](https://www.blackhat.com/html/webcast/02192015-secure-because-math.html), [video recording is here.](https://attendee.gotowebinar.com/recording/80449431422110210)  如果您使用ML推荐某些介质，则过度安装可能是无害的.  如果您依靠ML保护免受威胁，那么过度拟合可能会带来彻底的危险.  如果您对此空间感兴趣，请查看完整的演示文稿.

如果您想更深入地探索这个空间，下面的链接中有很多阅读材料：

* [Security Data Science and Machine Learning Guide](http://www.covert.io/the-definitive-security-datascience-and-machinelearning-guide/)
* [Awesome ML for Cybersecurity](https://github.com/jivoi/awesome-ml-for-cybersecurity)
* [Awesome AI Security](https://github.com/RandomAdversary/Awesome-AI-Security)
* [Awesome Adversarial Machine Learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning)

----


## Deep Learning

 在本指南的早期版本中，没有特定的“深度学习”部分.  我故意省略了它.  我认为前进太远对我们没有效果.  我也知道，如果您成为传统机器学习的专家，无论我是否已将其纳入本指南，您都将能够进入深度学习等高级课程.  我们只是想让您从这里开始！

 也许这是一种检查进度的方法：问问自己，深度学习看起来像魔术吗？  如果是这样，请以此为标志，表明您尚未准备好专业地使用它.  让迷恋激发您学习更多的知识.  我已经读到一些论点，您可以孤立地学习深度学习.  我读过其他人的建议，最好是首先掌握传统的机器学习.  为什么不从传统的机器学习开始，然后在那里发展您的推理和直觉？  之后，您将只有更轻松的时间来学习深度学习.  毕竟，您将能够解决各种有趣的问题.

无论如何，当您决定准备好学习深度学习时，这里有一些有用的资源.

* **[Dive into Deep Learning](https://d2l.ai/) -一本关于深度学习的互动书
 * ** [戴维·汉弗莱（David Humphrey）的“通过[深度]学习获得乐趣”.]（https://github.com/humphd/have-fun-with-machine-learning）**这是“取得成功的绝佳方法自己”和“ hack-first”.  然后，您会兴奋地前进到...
*  **[Prof. Andrew Ng's](https://www.andrewng.org/about/) [courses on Deep Learning](https://www.coursera.org/specializations/deep-learning)！**有五门课程，作为 [Deep Learning Specialization on Coursera](https://www.coursera.org/specializations/deep-learning) .  这些课程是他的新事业的一部分， [deeplearning.ai](https://www.deeplearning.ai)
* **[Machine Learning Crash Course from Google.](https://developers.google.com/machine-learning/crash-course/)** Google对机器学习的快节奏，实用的介绍，涵盖了使用TensorFlow构建深度神经网络.
* **[_Deep Learning_](http://www.deeplearningbook.org/)，由麻省理工学院出版社出版的免费书.**伊恩·古德费洛（Ian Goodfellow），约书亚（Yoshua Bengio）和亚伦·库维尔（Aaron Courville）
* [YerevaNN's Deep Learning Guide](http://yerevann.com/a-guide-to-deep-learning/)
* [Quora: "What are the best ways to pick up Deep Learning skills as an engineer?"](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer) —由Greg Brockman（OpenAI的联合创始人兼CTO，以前是Stripe的CTO）回答
* [Creative Applications of Deep Learning with Tensorflow](https://github.com/pkmital/CADL)
* [Dive into Deep Learning](https://d2l.ai/) -一本关于深度学习的互动书


## "Big" Data?

如果您完全使用数据密集型应用程序，我将推荐这本书：

* **[_Designing Data-Intensive Applications_](http://dataintensive.net) **马丁·克莱普曼（Martin Kleppman）.  （您可以开始免费通过Safari图书在线阅读它.）它不是特定于机器学习的，但是您可以自己弥补这一差距.

最后，这里是有关大数据和机器学习的其他有用链接.

* [10 things statistics taught us about big data analysis](https://simplystatistics.org/2014/05/22/10-things-statistics-taught-us-about-big-data-analysis/) （还有一些值得深思的地方： ["What Statisticians think about Data Scientists"](http://www.datasciencecentral.com/profiles/blogs/what-statisticians-think-about-data-scientists))
* ["Talking Machines" #12](http://www.thetalkingmachines.com/blog/2015/6/4/the-economic-impact-of-machine-learning-and-using-the-kernel-trick-to-dig-in-to-big-data) ：访谈教授  Ng（来自 [our main course, which has its own module on big data](https://www.coursera.org/learn/machine-learning) ）;  本集涵盖了与_high-Dimension_数据相关的一些问题
- ["Talking Machines" #15: "Really Really Big Data and Machine Learning in Business"](http://www.thetalkingmachines.com/blog/2015/7/16/really-really-big-data-and-machine-learning-in-business)
-免费电子书，[_正确获取数据：应对挑战
 大数据量和种类_]（https://www.tamr.com/landing-pages/getting-data-right/），由O&#39;Reilly出版，由Michael Stonebraker，Tom Davenport，James Markarian等撰写.  您可以 [listen to an accompanying podcast](http://radar.oreilly.com/2015/06/the-future-of-data-at-scale.html) 太.

----

## Finding Open-Source Libraries

* 书签 **[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)**，精选清单 [awesome](https://github.com/bayandin/awesome-awesomeness) 机器学习库和软件.
* 书签 [Pythonidae](https://github.com/svaksha/pythonidae/blob/master/AI.md#machine-learning)，精选 [awesome](https://github.com/bayandin/awesome-awesomeness) Python语言的库和软件-以及有关机器学习的部分.
* [TensorFlow](https://www.tensorflow.org/) 一直是 [really big deal.](https://news.ycombinator.com/item?id=10532957)  像您这样的人将使用TensorFlow做令人兴奋的事情.  这是一个框架.  框架可以帮助您管理复杂性.  只需记住以下经验法则即可：**“无论工具多么酷，“更多的数据都比聪明的算法更重要” **（Domingos）.  另请注意，TensorFlow并非同类唯一的机器学习框架：**[Check this great, detailed comparison of TensorFlow, Torch, 和 Theano.](https://github.com/zer0n/deepframeworks)** 也可以看看 [Newmu/Theano-Tutorials](https://github.com/Newmu/Theano-Tutorials) 和  [nlintz/TensorFlow-Tutorials](https://github.com/nlintz/TensorFlow-Tutorials) .  另请参见上面有关深度学习的部分.
    *另外，请考虑 [Lore](https://github.com/instacart/lore/) .  “ Lore是一个python框架，使机器学习（尤其是深度学习）对工程师来说更容易实现，对数据科学家而言则是可维护的.” 
*对于可能不在PyPI，GitHub等上的机器学习库，有 [MLOSS (Machine Learning Open Source Software)](http://mloss.org/software/) .  似乎拥有许多大学图书馆.
* 书签 [Julia.jl](https://github.com/svaksha/Julia.jl/blob/master/AI.md#machine-learning)，精选 [awesome](https://github.com/bayandin/awesome-awesomeness) Julia语言的库和软件-以及有关机器学习的部分.

----

## Alternative ways to "Dive into Machine Learning"

 这是机器学习的其他指南.  它们可以替代或补充本指南.

* ["How would your curriculum for a machine learning beginner look like?"](https://sebastianraschka.com/faq/docs/ml-curriculum.html) by Sebastian Raschka. A selection of the core online courses and books for getting started with machine learning and gaining expert knowledge. It contextualizes Raschka's own book, [_Python Machine Learning_](https://github.com/rasbt/python-machine-learning-book) （无论如何我都会链接到它！）另请参见 [`pattern_classification` GitHub repository](https://github.com/rasbt/pattern_classification) 由作者维护，其中包含有关各种机器学习算法和各种与数据科学相关的资源的IPython笔记本.
* [Materials for Learning Machine Learning](http://jacksimpson.co/materials-for-learning-machine-learning/) 杰克·辛普森（Jack Simpson）
*云供应商提供的课程（可能特定于他们的工具/平台）
    * [Machine Learning Crash Course from Google](https://developers.google.com/machine-learning/crash-course/)  使用TensorFlow API  这是Google对机器学习的快节奏，实用的介绍，其中包括一系列课程，包括视频讲座，真实案例研究和动手实践练习.
    *  [Amazon AWS](https://aws.amazon.com/training/learning-paths/machine-learning/)  亚马逊已向公众开放其内部培训，并提供认证.  30门课程-45个小时以上的内容.
* [Machine Learning for Developers](http://xyclade.github.io/MachineLearning/)  是另一个很好的介绍，如果您更熟悉Java或Scala，可能会更好.  它使用Smile（一个可以在Java和Scala中同时使用的机器学习库）为开发人员受众介绍机器学习.
* [Example Machine Learning notebook, exercise, and guide](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb)  由Randal S. Olson博士撰写.  在“笔记本”部分中也提到过，但是它的目标与本指南类似（向您介绍并向您展示下一步的方向）.  丰富的“进一步阅读”部分.
* [Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers)  由Nam Vu.  这是专为软件工程师设计的自上而下，结果优先的方法.
*有关后续新闻消息，请查看 [Sam DeBrule's list](https://machinelearnings.co/a-humans-guide-to-machine-learning-e179f43b67a0) 这里.
* [Distill](https://distill.pub/about/)  是一本致力于对机器学习最新研究进行清晰且交互式解释的期刊.  它们提供了传统学术出版的替代方法，可以提高该领域的可访问性和透明度.
* [您的指南在这里]
