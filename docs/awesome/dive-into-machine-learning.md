<div class="github-widget" data-repo="hangtwenty/dive-into-machine-learning"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Dive into Machine Learning [![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Hi there! You might find this guide helpful if:

* 你知道 Python 或 [you're](https://github.com/alexmojaki/futurecoder) [learning](https://nbviewer.org/github/jakevdp/WhirlwindTourOfPython/blob/master/Index.ipynb) [it](https://github.com/vinta/awesome-python#resources) [:snake:](https://github.com/ossu/computer-science#introduction-to-programming)
* You're new to [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)
* 你在乎 [the ethics of ML](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)
  * **[8 Responsible Machine Learning Principles](https://ethical.institute/principles.html)**
  * [Open Ethics Canvas](https://openethics.ai/canvas/)
* You learn by doing

F或者 some great alternatives, [jump to the end](https://github.com/hangtwenty/dive-into-machine-learning#m或者e-ways-to-dive-into-machine-learning) 或者 [check out Nam Vu's guide, Machine Learning f或者 Software Engineers](https://github.com/ZuzooVn/machine-learning-f或者-software-engineers).

当然，通往专业的道路并不容易. 另外，_我不是专家！_ 我只是想将_来自_专家的一些重要资源与您联系起来.  ML 的应用无处不在. 我认为让更多人了解更多关于机器学习的知识，尤其是动手实践，这符合公众利益，因为有很多不同的学习方式.

无论是什么促使_你_深入机器学习，如果你了解一点 Python，现在你可以在几分钟内亲身体验机器学习 _“Hello World！”_.

## Let's get started

## Tools you'll need

### If you prefer local installation

* [Python](https://www.python.org/) .  Python 3 是最好的选择.
* [Jupyter Notebook](https://jupyter.org/) .  （以前称为 IPython Notebook.）
* 一些科学计算包：
  * 麻木
  * pandas
  * scikit 学习
  * matplotlib

You can install Python 3 and all of these packages in a few clicks with the [Anaconda Python distribution](https://www.anaconda.com/download/). Anaconda is popular in Data Science and Machine Learning communities. (Use whichever tool you want.)

### Cloud-based options

您可以从浏览器中使用的一些选项：

- **[Binder](https://mybinder.org/) 是 Jupyter Notebook 的官方选择 [try JupyterLab](https://jupyter.org/try)**
- [Deepnote](https://deepnote.com/) 允许实时协作
- [Google Colab](https://colab.research.google.com/) 提供“免费”GPU

有关其他选项，请参阅：

- [markusschanta/awesome-jupyter, "Hosted Notebook Solutions"](https://github.com/markusschanta/awesome-jupyter#hosted-notebook-solutions)
- [ml-tooling/best-of-jupyter, "Notebook Environments"](https://github.com/ml-tooling/best-of-jupyter)

## Let's go!

**[Learn how to use Jupyter Notebook](http://opentechschool.github.io/python-data-intro/core/notebook.html) (5-10 minutes).** (You can [learn by screencast](https://www.youtube.com/watch?v=qb7FT68tcA8) 反而.）

Now, follow along with this brief exercise: **[An introduction to machine learning with scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html) **. 在 `ipython` 或 Jupyter Notebook 中执行此操作，在笔记本中编写代码并执行代码.

[![I'll wait.](https://user-images.githubusercontent.com/2420688/29441281-00eff0c4-837f-11e7-9666-d653a1cd2372.jpeg)](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)

## What just happened?

您刚刚使用 [scikit-learn](http://scikit-learn.org/stable/index.html). Neat huh?

## Dive in

## A Visual Introduction to Machine Learning

让我们更多地了解机器学习，以及一些常见的想法和关注点. 读 ["A Visual Introduction to Machine Learning, Part 1"](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) 经过 [Stephanie Yee](https://twitter.com/stephaniejyee) 和 [Tony Chu](https://twitter.com/tonyhschu/).

[![A Visual Introduction to Machine Learning, Part 1](https://user-images.githubusercontent.com/2420688/29441234-a2028c98-837e-11e7-88f2-1ca5a94684f6.gif)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

不会花很长时间. 这是一个美丽的介绍......尽量不要流口水太多！

## A Few Useful Things to Know about Machine Learning

行. 让我们更深入地了解.

读 **["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)** by [Prof. Pedro Domingos](https://homes.cs.washington.edu/~pedrod/). It's densely packed with valuable information, but not opaque.

花点时间看这个. 做笔记. 如果您还不完全理解，请不要担心.

整篇论文都充满了价值，但我想指出两点：

- **Data alone is not enough.** This is where science meets art in machine-learning. Quoting Domingos: "... the need for knowledge in learning should not be surprising. Machine learning is not magic; it can’t get something from nothing. What it does is get more from less. Programming, like all engineering, is a lot of work: we have to build everything from scratch. Learning is more like farming, which lets nature do most of the work. Farmers combine seeds with nutrients to grow crops. Learners combine knowledge with data to grow programs."
- **More data can beat a cleverer algorithm.** Listen up, programmers. We like cool tools. Resist the temptation to reinvent the wheel, or to over-engineer solutions. Your starting point is to [Do the Simplest Thing that Could _Possibly_ Work](http://www.artima.com/intv/simplest3.html). Quoting Domingos: "Suppose you’ve constructed the best set of features you can, but the classifiers you’re getting are still not accurate enough. What can you do now? There are two main choices: design a better learning algorithm, or gather more data. [...] As a rule of thumb, a dumb algorithm with lots and lots of data beats a clever one with modest amounts of it. (After all, machine learning is all about letting data do the heavy lifting.)"

When you work on a real Machine Learning problem, you should focus your efforts on your **domain knowledge** and **data** before optimizing your choice of algorithms. Prefer to do simple things until you _have_ to increase complexity. You should not rush into neural networks because you think they're cool. To improve your model, **get more data.** Then use your knowledge of the problem to [explore and process](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning) the data. You should only optimize the choice of algorithms after you have gathered enough data, and you've processed it well.

## Jargon note

* [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)
* Another handy term: ["Data Engineering."](https://www.coursera.org/articles/what-does-a-data-engineer-do-and-how-do-i-become-one)
  * ["MLOps"](https://ml-ops.org/) 与数据工程重叠，并且有 [an introductory MLOps section later in this guide](#production-deployment-mlops).

## Just about time for a break...

<details><summary>Totally optional: some podcast episodes of note</summary>

一、下载 [an interview with Prof. Domingos on the _Data Skeptic_ podcast](https://dataskeptic.com/blog/episodes/2018/the-master-algorithm) (2018). Prof. Domingos wrote [the paper we read earlier](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf).
You might also start reading his book, [_The Master Algorithm_ by Prof. Pedro Domingos](https://www.goodreads.com/book/show/24612233-the-master-algorithm) ，一个清晰易懂的机器学习概述.  （它也可以作为有声读物使用.）

接下来，订阅更多机器学习和数据科学播客！ 这些都是很棒的、省力的资源，您可以随意从中学到更多. 到 [learn effectively](https://www.coursera.org/learn/learning-how-to-learn)，随着时间的推移聆听，有足够的顶部空间. [By the way, don't speed up technical podcasts, that can hinder your comprehension.](https://www.theringer.com/2017/8/2/16095364/inefficiency-week-podcasts-speed-comprehension-f0ea43949e42)

订阅_**[Talking Machines](http://www.thetalkingmachines.com/)**_.

我建议这个听力顺序：

* **下载 ["Starting Simple"](http://www.thetalkingmachines.com/episodes/starting-simple-and-machine-learning-meds) 插曲，很快就会听到.**它支持我们从多明戈斯那里读到的内容. [Ryan Adams](http://people.seas.harvard.edu/~rpa/) 正如我们上面讨论的那样，谈论从简单开始.  Adams 还强调了特征工程的重要性. 特征工程是对 Domingos 所写的“知识”的练习. 在之后的一集中， [they share many concrete tips for feature engineering](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning).
* 然后，随着时间的推移，您可以收听整个播客系列（从头开始）.

想要订阅更多播客？ 这里是 [a good listicle](https://towardsdatascience.com/5-data-science-ai-and-machine-learning-podcasts-to-listen-to-now-e5078b18d184) of suggestions, [and another](https://mty.ai/blog/the-best-ai-podcasts/).

</details>

行！ 休息一下，回来神清气爽.

----

## Play to learn

接下来，从**一个或多个**笔记本开始播放.

- [Dr. Randal Olson's Example Machine Learning notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb)：“假设我们正在为一家刚刚获得资金的初创公司工作，该公司刚刚获得资金创建一个智能手机应用程序，该应用程序可以从智能手机上拍摄的照片中自动识别花卉种类.我们的数据科学负责人要求我们创建一个演示机器学习该模型对花朵进行四次测量（萼片长度、萼片宽度、花瓣长度和花瓣宽度），并仅根据这些测量值识别物种.”
	- [Launch in Binder, no installation steps required](https://mybinder.org/v2/gh/rhiever/Data-Analysis-and-Machine-Learning-Projects/master?filepath=example-data-science-notebook%2FExample%20Machine%20Learning%20Notebook.ipynb)
- 按主题分类的各种笔记本：
    - [trekhleb/machine-learning-experiments](https://github.com/trekhleb/machine-learning-experiments) - "This is a collection of interactive machine-learning experiments. Each experiment consists of 🏋️ Jupyter/Colab notebook (to see how a model was trained) and 🎨 demo page"
    - [trekhleb/homemade-machine-learning](https://github.com/trekhleb/homemade-machine-learning)
- 系列笔记本：
    - [ageron/handson-ml2](https://github.com/ageron/handson-ml2)  - “Jupyter 笔记本，带您了解 Python 中机器学习和深度学习的基础知识.”  Scikit-Learn、Keras、TensorFlow 2.

准备好后查找更多出色的 Jupyter Notebooks：

* **[Jupyter's official Gallery of Interesting Jupyter Notebooks: Statistics, Machine Learning and Data Science](https://github.com/jupyter/jupyter/wiki)** ([permalink](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks/ae03c01ed25024aa06a4479ea600895d59b38bc4))

----

## Immerse yourself

Pick one of the courses below and start on your way.

## [Recommended course: Prof. Andrew Ng's _Machine Learning_ on Coursera](https://www.coursera.org/learn/machine-learning)

**[Prof. Andrew Ng's](https://hai.stanford.edu/people/andrew-ng) [_Machine Learning_](https://www.coursera.org/learn/machine-learning) 是一个受欢迎和推崇的免费在线课程. 我已经看到了它 [recommended](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Cory-Hicks-1) [often.](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Xavier-Amatriain) [And emphatically.](https://www.forbes.com/sites/anthonykosner/2013/12/29/why-is-machine-learning-cs-229-the-most-popular-course-at-stanford/)**

您可能想在旁边玩一个宠物项目. 当你准备好了，你可以探索其中之一 [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets), [paperswithcode.com/datasets](https://paperswithcode.com/datasets)， 或者 [datasetlist.com](https://www.datasetlist.com/).

另外，建议拿一本教科书作为深入参考. 我看到最推荐的两个是 _[Understanding Machine Learning](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/copy.html)_ and _[Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)_. [You only need to use one of the two options as your main reference; here's some context/comparison to help you pick which one is right for you.](https://github.com/hangtwenty/dive-into-machine-learning/issues/29) You can download each book free as PDFs at those links - so grab them!

### Tips for this course

* [Study tips for Prof. Andrew Ng's course, by Ray Li](https://rayli.net/blog/data/coursera-machine-learning-review/)
* If you're wondering, _Is it still a relevant course?_ or trying to figure out if it fits for you personally, check out these reviews:
    * [Review: Andrew Ng's Machine Learning Course](https://towardsdatascience.com/review-andrew-ngs-machine-learning-course-b905aafdb7d9)
    * [The user reviews on Coursera](https://www.coursera.org/learn/machine-learning/reviews)

### Tips for studying on a busy schedule

It's hard to make time available every week. So, you can try to study more _effectively_ within the time you have available. Here are some ways to do that:

* ["Learning How to Learn" by Barbara Oakley](https://www.coursera.org/learn/learning-how-to-learn/) 由 Barbara Oakley 提供，Coursera 上的免费视频课程.
* Prefer book/audiobook? These are great options:
  * [Barbara Oakley's book _A Mind for Numbers: How to Excel at Math and Science_](https://barbaraoakley.com/books/a-mind-for-numbers) ([reviews](https://www.goodreads.com/book/show/18693655-a-mind-for-numbers)) — "We all have what it takes to excel in areas that don't seem to come naturally to us at first"
  * [_Make It Stick: the Science of Successful Learning_](https://www.retrievalpractice.org/make-it-stick) ([reviews](https://www.goodreads.com/book/show/18770267-make-it-stick))

### Take my tips with a grain of salt

I am not a machine learning expert. I'm just a software developer and these resources/tips were useful to me as I learned some ML on the side.

## Other courses

* **Data science courses as Jupyter Notebooks:**
  * [Practical Data Science](http://radimrehurek.com/data_science_python/)
  * [Python Data Science Handbook, as Jupyter Notebooks](https://jakevdp.github.io/PythonDataScienceHandbook/)
*  [`microsoft/Data-Science-For-Beginners`](https://github.com/microsoft/Data-Science-For-Beginners) — [added in 2021](https://dev.to/azure/free-data-science-for-beginners-curriculum-on-github-1hme) —“关于数据科学的 10 周 20 节课的课程.每节课都包括课前和课后测验、完成课程的书面说明、解决方案和作业.我们基于项目的教学法让您学习在构建的同时，这是一种让新技能‘坚持’的行之有效的方法.”
  * 也可以看看 [`microsoft/ML-For-Beginners`](https://github.com/microsoft/ML-For-Beginners)

<details>
<summary><i>More free online courses I&#39;ve seen recommended.</i><b>我看到推荐的更多免费在线课程。</b> <i>(Machine Learning, Data Science, and related topics.)</i> <b>（机器学习、数据科学和相关主题。）</b></summary>

* Coursera's [Data Science Specialization](https://www.coursera.org/specializations/jhu-data-science)
* [Prof. Pedro Domingos's introductory video series](https://www.youtube.com/playlist?list=PLTPQEx-31JXgtDaC6-3HxWcp7fq4N8YGr). [Prof. Pedro Domingos](https://homes.cs.washington.edu/~pedrod/) 写了这篇论文 ["A Few Useful Things to Know About Machine Learning"](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)，您可能还记得本指南前面的内容.
* [`ossu/data-science`](https://github.com/ossu/data-science) （也可以看看 [`ossu/computer-science`](https://github.com/ossu/computer-science))
* [Stanford CS229: Machine Learning](https://github.com/afshinea/stanford-cs-229-machine-learning)
* [Harvard CS109: Data Science](https://cs109.github.io/2015/)
* [Advanced Statistical Computing (Vanderbilt BIOS8366)](http://stronginference.com/Bios8366/lectures.html). Interactive.
* Kevin Markham's video series, [Intro to Machine Learning with scikit-learn](http://blog.kaggle.com/2015/04/08/new-video-series-introduction-to-machine-learning-with-scikit-learn/), starts with what we've already covered, then continues on at a comfortable place.
* [UC Berkeley's Data 8: The Foundations of Data Science](http://data8.org/) course and the textbook [Computational and Inferential Thinking](https://www.inferentialthinking.com/) teaches critical concepts in Data Science.
* Prof. Mark A. Girolami's [Machine Learning Module (GitHub Mirror).](https://github.com/josephmisiti/machine-learning-module) “适合有很强数学背景的人.”
* [An epic Quora thread: How can I become a data scientist?](https://www.quora.com/How-can-I-become-a-data-scientist?redirected_qid=59455)

</details>

## Getting Help: Questions, Answers, Chats

Start with the support forums and chats related to the course(s) you're taking.

Check out [datascience.stackexchange.com](https://datascience.stackexchange.com/) 和 [stats.stackexchange.com – such as the tag, _machine-learning_.](https://stats.stackexchange.com/questions/tagged/machine-learning?sort=frequent&pageSize=15) 有一些subreddits，比如 [/r/LearningMachineLearning](https://www.reddit.com/r/learningmachinelearning) 和 [/r/MachineLearning](https://www.reddit.com/r/machinelearning).

Don't forget about meetups. Also, nowadays there are many active and helpful online communities around the ML ecosystem. Look for chat invitations on project pages and so on.

## Supplement: Learning Pandas well

你会想要更熟悉 Pandas.

* **基本的**： [Things in Pandas I Wish I'd Had Known Earlier](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb) （作为 Jupyter 笔记本）
* **基本的**： [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* Another helpful tutorial: [Real World Data Cleanup with Python and Pandas](https://trendct.org/2016/08/05/real-world-data-cleanup-with-python-and-pandas/)
* [Video series from Data School, about Pandas](https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y) .  “30个常见熊猫任务的参考指南（加上6小时的支持视频）.”
* 以下是我在继续学习时发现特别有用的一些文档：
  * [Cookbook](http://pandas.pydata.org/pandas-docs/stable/cookbook.html)
  * [Data Structures](http://pandas.pydata.org/pandas-docs/stable/dsintro.html), esp. [DataFrame](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe) 部分
  * [Reshaping by pivoting DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/reshaping.html)
  * [Computational tools](http://p和as.pydata.org/p和as-docs/stable/computation.html) 和 [StackExchange thread: "What is covariance in plain language?"](https://stats.stackexchange.com/questions/29713/what-is-covariance-in-plain-language)
  * [Group By (split, apply, and combine DataFrames)](http://pandas.pydata.org/pandas-docs/stable/groupby.html)
  * [Visualizing your DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html)
*缩放“熊猫”和替代品的书签
  * [`dask`](https://dask.org/): A Pandas-like interface, but for larger-than-memory data and "under the hood" parallelism.
  * [`vaex`](https://vaex.io)
    *“用于 Python、ML 的核外混合 Apache Arrow/NumPy DataFrame，以每秒十亿行的速度可视化和探索大表格数据” 
    * "It calculates statistics such as mean, sum, count, standard deviation etc, on an N-dimensional grid for more than a billion (10^9) samples/rows per second. Visualization is done using histograms, density plots and 3d volume rendering, allowing interactive exploration of big data. Vaex uses memory mapping, zero memory copy policy and lazy computations for best performance (no memory wasted)."
  * 参见：MLOps 部分 [later in this guide](#production-deployment-mlops).

## Supplement: Cheat Sheets

我遇到了一些很好的备忘单.  （请 [submit a Pull Request](https://github.com/hangtwenty/dive-into-machine-learning/pulls) to add other useful cheat sheets.)

* [scikit-learn algorithm cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
* [`FavioVazquez/ds-cheatsheets`](https://github.com/FavioVazquez/ds-cheatsheets)
* 统计数据
  * [`wzchen/probability-cheatsheet`](https://github.com/wzchen/probability_cheatsheet) - "This cheatsheet is a 10-page reference in probability that covers a semester's worth of introductory probability. The cheatsheet is based off of Harvard's introductory probability course, Stat 110. It is co-authored by former Stat 110 Teaching Fellow William Chen and Stat 110 Professor Joe Blitzstein." 
  * [Probabilities and statistics refresher](https://stanford.edu/~shervine/teaching/cs-229/refresher-probabilities-statistics) 备忘单来自 [Stanford CS 229](https://github.com/afshinea/stanford-cs-229-machine-learning)
* [Stanford CS 229](https://github.com/afshinea/stanford-cs-229-machine-learning) [cheat sheets](https://stanford.edu/~shervine/teaching/cs-229/)，可在网络上获得 [as PDFs](https://github.com/afshinea/stanford-cs-229-machine-learning/tree/master/en)
  * [Supervised learning cheat sheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-supervised-learning)
  * [Unsupervised learning cheat sheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-unsupervised-learning)
  * [Linear algebra and calculus refresher](https://stanford.edu/~shervine/teaching/cs-229/refresher-algebra-calculus)
  * [Machine Learning tips and tricks cheat sheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-machine-learning-tips-and-tricks)
  * [Deep learning cheatsheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-deep-learning) [(more)](https://stanford.edu/~shervine/teaching/cs-230/)


## Assorted Tips and Resources

## Risks

 “机器学习系统自动从数据中学习程序.” 佩德罗·多明戈斯，在 ["A Few Useful Things to Know about Machine Learning."](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) 您生成的程序需要维护. 就像任何更快地创建程序的方式一样，您可以 [technical debt](https://en.wikipedia.org/wiki/Technical_debt).

这里是摘要 [Machine Learning: The High-Interest Credit Card of Technical Debt](https://research.google/pubs/pub43146/):

 &gt; 机器学习为快速构建复杂系统提供了一个非常强大的工具包. 本文认为，将这些快速获胜视为免费提供是危险的. 使用技术债务的框架，我们注意到在应用机器学习时，在系统级别产生大量的持续维护成本非常容易. 本文的目标是突出几个机器学习特定的风险因素和设计模式，尽可能避免或重构. 这些包括边界侵蚀、纠缠、隐藏的反馈循环、未声明的消费者、数据依赖、外部世界的变化以及各种系统级的反模式.

如果您遵循本指南，则应该阅读该论文. 你也可以 [listen to a podcast episode interviewing one of the authors of this paper](https://softwareengineeringdaily.com/2015/11/17/machine-learning-and-technical-debt-with-d-sculley/).

* **[Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning), “一个精选的开源库列表，用于部署、监控、版本和扩展你的机器学习.”** 它包括一个关于 [privacy-preserving ML](https://github.com/EthicalML/awesome-production-machine-learning#privacy-preserving-machine-learning)， 顺便一提！
* **["Rules of Machine Learning: Best Practices for [Reliable] ML Engineering,"](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)** by Martin Zinkevich, regarding ML engineering practices.
* [The High Cost of Maintaining Machine Learning Systems](http://www.kdnuggets.com/2015/01/high-cost-machine-learning-technical-debt.html)
* [Overfitting vs. Underfitting: A Conceptual Explanation](https://towardsdatascience.com/overfitting-vs-underfitting-a-conceptual-explanation-d94ee20ca7f9)
* [11 Clever Methods of Overfitting and How to Avoid Them](http://hunch.net/?p=22)
* ["So, you want to build an ethical algorithm?" An interactive tool to prompt discussions](https://cdt.info/ddtool/) [(source)](https://github.com/numfocus/algorithm-ethics)

That's not a comprehensive list, only a collection of starting-points to learn more.

## Skilling up

What are some ways to practice?

<details>
<summary><strong>One way:</strong> competitions and challenges</summary>

你需要**练习.** [On Hacker News, user olympus commented to say you could use competitions to practice 和 evaluate yourself](https://news.ycombinat或者.com/item?id=10508565). [Kaggle](https://www.kaggle.com/competitions) 和 [ChaLearn](http://www.chalearn.或者g/) are hubs f或者 Machine Learning competitions. (You can find m或者e competitions [here](https://github.com/paperswithcode/releasing-research-code#results-leaderboards) 或者 [here](https://towardsdatascience.com/12-data-science-ai-competitions-to-advance-your-skills-in-2021-32e3fcb95d8c).)

You also need **understanding.** You should review what Kaggle competition winners say about their solutions, [for example, the "No Free Hunch" blog](http://blog.kaggle.com/) . 一开始这些可能会让你头疼，但一旦你开始理解和欣赏这些，你就会知道你正在到达某个地方.
	
Competitions and challenges are just one way to practice! [Machine Learning isn't just about Kaggle competitions](https://jvns.ca/blog/2014/06/19/machine-learning-isnt-kaggle-competitions).
	
</details>

<details>
<summary><strong>另一种方法：</strong>尝试做一些实践研究</summary>

Here's a complementary way to practice: **do practice studies.**

1. **Ask a question. Start exploring some data.** The ["most important thing in data science is the question"](https://github.com/DataScienceSpecialization/courses/blob/master/01_DataScientistToolbox/03_02_whatIsData/index.Rmd#the-data-is-the-second-most-important-thing) ([Dr. Jeff T. Leek](https://github.com/jtleek)). So start with a question. Then, find [real data](https://github.com/caesar0301/awesome-public-datasets) . 分析一下. 然后 ...
 2. **传达结果.** 当您认为自己有新发现时，请要求审查. 当您仍在学习时，请在非正式社区中询问（有些是 [linked below](#some-communities-to-know-about)).
3. **Learn from feedback.** Consider [learning in public](https://www.swyx.io/learn-in-public/) ，它对某些人来说非常有用.  （不过不要给自己压力！做对你有用的事.） 

How can you come up with interesting questions? Here's one way. Pick a day each week to [look for public datasets](https://github.com/caesar0301/awesome-public-datasets) 并写下一些想到的问题. 另外，报名 [Data is Plural](https://tinyletter.com/data-is-plural) ，有趣的数据集的时事通讯. 当一个问题激发了你的灵感时，试着用你正在学习的技能来探索它.

This advice, to do practice studies and learn from review, is based on [a conversation](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-153934120) with [Dr. Randal S. Olson](http://www.randalolson.com/). Here's more advice from Olson, [quoted with permission:](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-154135498)

> I think the best advice is to tell people to always present their methods clearly and to avoid over-interpreting their results. Part of being an expert is knowing that there's rarely a clear answer, especially when you're working with real data.

As you repeat this process, your practice studies will become more scientific, interesting, and focused. Also, [here's a video about the scientific method in data science.](https://101.datascience.community/2012/06/27/the-data-scientific-method/))

</details>

<details>
<summary>更多机器学习职业相关链接</summary>

* ["Advice on building a machine learning career and reading research papers by Prof. Andrew Ng"](https://www.kdnuggets.com/2019/09/advice-building-machine-learning-career-research-papers-andrew-ng.html)
* Some links for finding/following interesting papers/code:
    * [Papers With Code](https://paperswithcode.com/) is a popular site to follow, and it can lead you to other resources. [github.com/paperswithcode](https://github.com/paperswithcode)
    * [MIT: Papers + Code](https://mitibmwatsonailab.mit.edu/research/papers-code/) — "Peer-review is the lifeblood of scientific validation and a guardrail against runaway hype in AI. Our commitment to publishing in the top venues reflects our grounding in what is real, reproducible, and truly innovative."
    * [papers.labml.ai/papers/weekly](https://papers.labml.ai/papers/weekly), [monthly](https://papers.labml.ai/papers/monthly/)
* 欢迎请求请求！
	
</details>

#### Some communities to know about

* [/r/LearnMachineLearning](https://www.reddit.com/r/learnmachinelearning/)
* [/r/MachineLearning](https://reddit.com/r/MachineLearning)
* [/r/DataIsBeautiful](https://reddit.com/r/DataIsBeautiful)
* [/r/DataScience](https://reddit.com/r/DataScience)
* [Cross-Validated: stats.stackexchange.com](https://stats.stackexchange.com/)
* [`ossu/data-science` has a Discord server and newsletter](https://github.com/ossu/data-science#:~:text=Discord%20server)

### Peer review

**[OpenReview.net](https://openreview.net/about)** “旨在促进科学交流的开放性，特别是同行评审过程.”

> * **Open Peer Review:** We provide a configurable platform for peer review that generalizes over many subtle gradations of openness, allowing conference organizers, journals, and other "reviewing entities" to configure the specific policy of their choice. We intend to act as a testbed for different policies, to help scientific communities experiment with open scholarship while addressing legitimate concerns regarding confidentiality, attribution, and bias.
&gt; * **开放出版：** 跟踪提交，协调编辑、审稿人和作者的工作，并托管……分片和分发以提高速度和可靠性.
> * **Open Access:** Free access to papers for all, free paper submissions. No fees.

<details>
<summary><em>More about OpenReview.net</em></summary>

 &gt; * **公开讨论：** 托管接受的论文及其评论和评论. 与论文发表接受相关的持续讨论论坛. 出版场所主席/编辑可以控制审查/评论表格的结构、读/写访问权限及其时间.
&gt; * **开放目录：** 包含利益冲突信息的人员集合，包括机构和关系，例如共同作者、共同 PI、同事、顾问/顾问和家庭关系.
 &gt; * **公开建议：** 科学主题和专业知识的模型. 人员名录包括科学专业知识. 审查员与数千份提交的会议的论文匹配，结合了各种类型的专业知识、投标、约束和审查员平衡. 向用户推荐论文.
> * **Open API:** We provide a simple REST API [...]
 &gt; * **开源：**我们致力于开源.  OpenReview 的许多部分已经在 [OpenReview organization on GitHub](https://github.com/openreview). Some further releases are pending a professional security review of the codebase.

> * [OpenReview.net](https://openreview.net/) 由马萨诸塞大学阿默斯特分校信息与计算机科学学院的 Andrew McCallum 信息提取与合成实验室创建
>
> * [OpenReview.net](https://openreview.net/) 建立在论文中描述的早期版本之上 [Open Scholarship and Peer Review: a Time for Experimentation](https://openreview.net/forum?id=xf0zSBd2iufMg) 发表在 [ICML 2013 Peer Review Workshop](https://openreview.net/group?id=ICML.cc/2013/PeerReview).
>
> * OpenReview is a long-term project to advance science through improved peer review, with legal nonprofit status through Code for Science & Society. We gratefully acknowledge the support of the great diversity of [OpenReview Sponsors](https://openreview.net/sponsors)——科学同行评审是神圣不可侵犯的，不应归任何一个赞助商所有.

</details>

### Production, Deployment, [MLOps](https://ml-ops.org/)

If you are learning about MLOps but find it overwhelming, these resources might help you get your bearings:

* [MLOps Stack Template](https://valohai.com/blog/the-mlops-stack/) 亨利克·斯科格斯特罗姆
* [Lessons on ML Platforms from Netflix, DoorDash, Spotify, and more](https://towardsdatascience.com/lessons-on-ml-platforms-from-netflix-doordash-spotify-and-more-f455400115c7) by Ernest Chan in *Towards Data Science*

Recommended awesomelists to save/star/watch:

* **[EthicalML/awesome-artificial-intelligence-guidelines](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)**
* **[EthicalML/awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning#privacy-preserving-machine-learning)**
* **[visenger/awesome-ml-model-governance](https://github.com/visenger/Awesome-ML-Model-Governance)**
* **[visenger/awesome-MLOps](https://github.com/visenger/awesome-mlops)**

----

## Deep Learning

Take note: some experts warn us not to get too far ahead of ourselves, and encourage learning ML fundamentals before moving onto deep learning. That's paraphrasing from some of the linked coursework in this guide — for example, Prof. Andrew Ng encourages building foundations in ML before studying DL. Perhaps you're ready for that now, or perhaps you'd like to get started soon and learn some DL in parallel to your other ML learnings.

When you're ready to dive into Deep Learning, here are some helpful resources.

* **[_Dive into Deep Learning_](https://d2l.ai/) - 一本关于深度学习的互动书**（[view on GitHub](https://github.com/d2l-ai/d2l-en))
  * 快速开始：
    * [Run this book locally, using Jupyter Notebooks](https://d2l.ai/chapter_installation/index.html)
    * [Run this book in your browser, using Google Colab](https://d2l.ai/chapter_appendix-tools-for-deep-learning/colab.html)
  * “使用 NumPy/MXNet、PyTorch 和 TensorFlow 实现”
  *“被来自 50 个国家的 200 所大学采用”
  *“整本书是在 Jupyter 笔记本中起草的，将说明图、数学和交互式示例与自包含代码无缝集成.” 
  * “你可以修改代码和调优超参数，获得即时反馈，积累深度学习实践经验.”
* [`explosion/thinc`](https://github.com/explosion/thinc) 是一个有趣的库，包含 **PyTorch**、**TensorFlow** 和 **MXNet** 模型. 
  * "Concise functional-programming approach to model definition, using composition rather than inheritance."
  *“用于描述对象和超参数树的集成配置系统.”
* [`fastai/fastbook`](https://github.com/fastai/fastbook) Jeremy Howard 和 Sylvain Gugger 着——“深度学习、fastai 和 PyTorch 简介”.
* **[Prof. Andrew Ng's](https://scholar.google.com/citations?user=mG4imMEAAAAJ&hl=en) [courses on Deep Learning](https://www.coursera.org/specializations/deep-learning)!** There five courses, as part of the [Deep Learning Specialization on Coursera](https://www.coursera.org/specializations/deep-learning) . 这些课程是他新事业的一部分， [deeplearning.ai](https://www.deeplearning.ai)
  * Some course notes about it: [ashishpatel26/Andrew-NG-Notes](https://github.com/ashishpatel26/Andrew-NG-Notes)
* **[_Deep Learning_](https://www.deeplearningbook.org/)，麻省理工学院出版社出版的免费书籍.** 由 Ian Goodfellow、Yoshua Bengio 和 Aaron Courville 撰写.
  * 一个值得注意的证明在这里： ["What are the best ways to pick up Deep Learning skills as an engineer?"](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer)
* [paperswithcode.com](https://paperswithcode.com/) — “Papers with Code 的使命是创建一个包含机器学习论文、代码、数据集、方法和评估表的免费开放资源.”
* [`labmlai/annotated_deep_learning_paper_implementations`](https://github.com/labmlai/annotated_deep_learning_paper_implementations) — "Implementations/tutorials of deep learning papers with side-by-side notes." 50+ of them! Really nicely annotated and explained.
* [JAX - official quickstart Colab Notebooks to get to know JAX](https://github.com/google/jax#quickstart-colab-in-the-cloud)
* [Distill.pub](https://distill.pub/about/) 发表了非常棒的探索性解释.
  * ["Feature Visualization: How neural networks build up their understanding of images"](https://distill.pub/2017/feature-visualization/)

### Easier sharing of deep learning models and demos

* **[Replicate](https://replicate.com) “让共享运行中的机器学习模型变得容易”**
  * Easily try out deep learning models from your browser
  * 演示链接到 GitHub 上的论文/代码，如果你想深入了解一些东西是如何工作
  * 模型在容器中运行 [`cog`](https://github.com/replicate/cog) ，“机器学习容器”. 它是一个开源工具，用于将模型放入可重现的 Docker 容器中.

----

## Collaborate with Domain Experts

Machine Learning can be powerful, but it is not magic.

每当您应用机器学习来解决问题时，您都将在某个特定的问题域中工作. 为了获得好的结果，您或您的团队将需要与“领域知识”相关的“实质性专业知识”（重复使用前面的短语）. 为自己了解你能做的事情......但你也应该**与专家合作.**如果你与专家合作，你会得到更好的结果 [subject-matter experts and domain experts](https://en.wikipedia.org/wiki/Subject-matter_expert#Domain_expert_(software)).

### Machine Learning and User Experience (UX)

我不能说得更好：

> **Machine learning won’t figure out what problems to solve.** If you aren’t aligned with a human need, you’re just going to build a very powerful system to address a very small—or perhaps nonexistent—problem.

该报价来自 ["The UX of AI" by Josh Lovejoy](https://design.google/library/ux-ai/) . 换句话说， **[You Are Not The User](https://www.nngroup.com/articles/false-consensus/).** 建议阅读： [Martin Zinkevich's "Rules of ML Engineering", Rule #23: "You are not a typical end user"](https://developers.google.com/machine-learning/guides/rules-of-ml/#human_analysis_of_the_system)

---

## Big data

<details>
<summary>以下是一些关于大数据和机器学习的有用链接.
</summary>

* [10 things statistics taught us about big data analysis](https://www.kdnuggets.com/2015/02/10-things-statistics-big-data-analysis.html) (and some more food for thought: ["What Statisticians think about Data Scientists"](https://www.datasciencecentral.com/profiles/blogs/what-statisticians-think-about-data-scientists))
* ["Talking Machines" #12](https://www.thetalkingmachines.com/episodes/economic-impact-machine-learning-and-using-kernel-trick-big-data): Interviews Prof. Andrew Ng (from [his course, which has its own module on big data](https://www.coursera.org/learn/machine-learning) ); 这一集涵盖了一些与_高维_数据相关的问题
* ["Talking Machines" #15: "Really Really Big Data and Machine Learning in Business"](https://www.thetalkingmachines.com/episodes/really-really-big-data-and-machine-learning-business)
* [0xnr/awesome-bigdata](https://github.com/0xnr/awesome-bigdata)


</details>

如果您正在使用数据密集型应用程序，我会推荐这本书：

* **[_Designing Data-Intensive Applications_](http://dataintensive.net) ** 马丁·克莱普曼.  （您可以通过 Safari Books 开始免费在线阅读.）它并不特定于机器学习，但您可以自己弥合这一差距.

## More Data Science materials

以下是一些额外的数据科学资源：

* **[Python Data Science Handbook, as Jupyter Notebooks](https://jakevdp.github.io/PythonDataScienceHandbook/)**
* Accessible data science book, no coding experience required: [_Data Smart_ by John Foreman](https://www.goodreads.com/book/show/17682206-data-smart)
* [Data Science Workflow: Overview and Challenges](https://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext) （阅读文章*以及*约瑟夫·麦卡锡的评论）

### Aside: Bayesian Statistics and Machine Learning

From [the "Bayesian Machine Learning" overview on Metacademy](https://metacademy.org/roadmaps/rgrosse/bayesian_machine_learning):

> ... Bayesian ideas have had a big impact in machine learning in the past 20 years or so because of the flexibility they provide in building structured models of real world phenomena. Algorithmic advances and increasing computational resources have made it possible to fit rich, highly structured models which were previously considered intractable.

<details>
<summary>Here are some awesome resources for learning Bayesian methods.</summary>

* The **free book** _[Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)_. Made with a "computation/understanding-first, mathematics-second point of view." Uses [PyMC](https://github.com/pymc-devs/pymc) . 它也有印刷版！
* Like learning by playing? Me too. Try [19 Questions](https://github.com/fulldecent/19-questions)，“一个机器学习游戏，它会问你问题并猜测你正在考虑的对象”，并且**解释它使用了哪些贝叶斯统计技术！**
* [_Time Series Forecasting with Bayesian Modeling by Michael Grogan_](https://www.manning.com/liveprojectseries/time-series-forecasting-with-bayesian-modeling)，一个包含 5 个项目的系列 - 付费但第一个项目是免费的.
* [Bayesian Modelling in Python](https://github.com/markdregan/Bayesian-Modelling-in-Python). Uses [PyMC](https://github.com/pymc-devs/pymc) as well.

</details>


----

## Finding Open-Source Libraries

* 书签 **[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)**，精选列表 [awesome](https://github.com/bayandin/awesome-awesomeness) 机器学习库和软件.
* 书签 [Pythonidae](https://github.com/svaksha/pythonidae/blob/master/AI.md#machine-learning), a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) libraries and software in the Python language - with a section on Machine Learning.
* For Machine-Learning libraries that might not be on PyPI, GitHub, etc., there's [MLOSS (Machine Learning Open Source Software)](http://mloss.org/software/) . 似乎有许多学术图书馆.
* 朱莉娅： [Julia.jl](https://github.com/svaksha/Julia.jl/blob/master/AI.md#machine-learning), a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) Julia 语言中的库和软件 - 包含机器学习部分.

### Natural Language Processing (NLP)

这只是一个小 

* [spaCy: Industrial-strength NLP](https://github.com/explosion/spaCy) - "spaCy is a library for advanced Natural Language Processing in Python and Cython."
  * [Advanced NLP with spaCy: A free online course](https://github.com/ines/spacy-course)
  * [spaCy projects](https://spacy.io/usage/projects) - "End-to-end NLP workflows from prototype to production"
* 有很多NLP相关的链接 [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)
* [keon/awesome-nlp](https://github.com/keon/awesome-nlp)

### Non-sequitur

These next two links are not related to ML. But since you're here, I have a hunch you might find them interesting too:

* Maggie Appleton's ["A Brief History & Ethos of the Digital Garden"](https://maggieappleton.com/garden-history)
* 王肖恩 ["Digital Garden Terms of Service"](https://www.swyx.io/digital-garden-tos/)

----

## More ways to "Dive into Machine Learning"

Here are some other guides to learning Machine Learning. They can be alternatives or supplements to this guide.

* [Example Machine Learning notebook, exercise, and guide](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) by Dr. Randal S. Olson. Mentioned in Notebooks section as well, but it has a similar goal to this guide (introduce you, and show you where to go next). Rich "Further Reading" section.
  * [`microsoft/ML-For-Beginners`](https://github.com/microsoft/ML-For-Beginners)
  * [`microsoft/Data-Science-For-Beginners`](https://github.com/microsoft/Data-Science-For-Beginners)
  * [Machine Learning Crash Course from Google](https://developers.google.com/machine-learning/crash-course/) 使用 TensorFlow API。
  * [Amazon AWS](https://aws.amazon.com/training/learn-about/machine-learning/) 亚马逊已向公众开放其内部培训并提供认证.
* [Machine Learning for Developers](http://xyclade.github.io/MachineLearning/) is good for people who are more familiar with Java or Scala than Python.
* [ageron/handson-ml2](https://github.com/ageron/handson-ml2) 又名 [_Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow_ by Aurélien Geron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
* [rasbt/python-machine-learning-book-3rd-edition](https://github.com/rasbt/python-machine-learning-book-3rd-edition) 又名 [_Python Machine Learning: Machine Learning and Deep Learning with Python, scikit-learn, and TensorFlow 2_ by Sebastian Raschka and Vahid Mirjalili](https://www.goodreads.com/book/show/25545994-python-machine-learning)
* [Machine Learning for Software Engineers, by Nam Vu](https://github.com/ZuzooVn/machine-learning-for-software-engineers) . 用他们的话说，这是一种“专为软件工程师设计的自上而下和结果至上的方法”. 当然也可以添加书签并使用它 - 它可以回答很多问题并将您与大量资源联系起来.
