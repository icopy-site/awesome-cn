<div class="github-widget" data-repo="hangtwenty/dive-into-machine-learning"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Dive into Machine Learning [![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Hi there! You might find this guide helpful if:

* You know Python or [you're](https://github.com/alexmojaki/futurecoder) [learning](https://nbviewer.org/github/jakevdp/WhirlwindTourOfPython/blob/master/Index.ipynb) [it](https://github.com/vinta/awesome-python#resources) [:snake:](https://github.com/ossu/computer-science#introduction-to-programming)
* 你是新手 [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)
* You care about [the ethics of ML](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)
  * **[8 Responsible Machine Learning Principles](https://ethical.institute/principles.html)**
  * [Open Ethics Canvas](https://openethics.ai/canvas/)
* 你边做边学

对于一些很棒的选择， [jump to the end](https://github.com/hangtwenty/dive-into-machine-learning#more-ways-to-dive-into-machine-learning) or [check out Nam Vu's guide, Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers).

当然，通往专业的道路并不容易. 另外，_我不是专家！_ 我只是想将_来自_专家的一些重要资源与您联系起来.  ML 的应用无处不在. 我认为让更多人了解更多关于机器学习的知识，尤其是动手实践，这符合公众利益，因为有很多不同的学习方式.

无论是什么促使_你_深入机器学习，如果你了解一点 Python，现在你可以在几分钟内亲身体验机器学习 _“Hello World！”_.

## Let's get started

## Tools you'll need

### If you prefer local installation

* [Python](https://www.python.org/) .  Python 3 是最好的选择.
* [Jupyter Notebook](https://jupyter.org/). (Formerly known as IPython Notebook.)
* 一些科学计算包：
  * 麻木
  * 熊猫
  * scikit-learn
  * matplotlib

只需单击几下，您就可以安装 Python 3 和所有这些包 [Anaconda Python distribution](https://www.anaconda.com/download/) .  Anaconda 在数据科学和机器学习社区中很受欢迎.  （使用适合您的任何工具. [If you're unsure or need more context about using conda/virtualenv/poetry/pipenv, here's a very helpful guide](https://brainsteam.co.uk/2021/04/01/opinionated-guide-to-virtualenvs/#recommended-setups-for-various-use-cases))

### Cloud-based options

Some options you can use from your browser:

- **[Binder](https://mybinder.org/) is Jupyter Notebook's official choice to [try JupyterLab](https://jupyter.org/try)**
- [Deepnote](https://deepnote.com/) allows for real-time collaboration
- [Google Colab](https://colab.research.google.com/) provides "free" GPUs

For other options, see:

- [markusschanta/awesome-jupyter, "Hosted Notebook Solutions"](https://github.com/markusschanta/awesome-jupyter#hosted-notebook-solutions)
- [ml-tooling/best-of-jupyter, "Notebook Environments"](https://github.com/ml-tooling/best-of-jupyter)

## Let's go!

**[Learn how to use Jupyter Notebook](http://opentechschool.github.io/python-data-intro/core/notebook.html) （5-10 分钟）.**（您可以 [learn by screencast](https://www.youtube.com/watch?v=qb7FT68tcA8) instead.)

现在，跟着这个简短的练习：**[An introduction to machine learning with scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html) **. 在 `ipython` 或 Jupyter Notebook 中执行此操作，在笔记本中编写代码并执行代码.

[![I'll wait.](https://user-images.githubusercontent.com/2420688/29441281-00eff0c4-837f-11e7-9666-d653a1cd2372.jpeg)](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)

## What just happened?

You just classified some hand-written digits using [scikit-learn](http://scikit-learn.org/stable/index.html). Neat huh?

## Dive in

## A Visual Introduction to Machine Learning

Let's learn a bit more about Machine Learning, and a couple of common ideas and concerns. Read ["A Visual Introduction to Machine Learning, Part 1"](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) 经过 [Stephanie Yee](https://twitter.com/stephaniejyee) and [Tony Chu](https://twitter.com/tonyhschu/).

[![A Visual Introduction to Machine Learning, Part 1](https://user-images.githubusercontent.com/2420688/29441234-a2028c98-837e-11e7-88f2-1ca5a94684f6.gif)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

不会花很长时间. 这是一个美丽的介绍......尽量不要流口水太多！

## A Few Useful Things to Know about Machine Learning

行. 让我们更深入地了解.

读 **["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)** by [Prof. Pedro Domingos](https://homes.cs.washington.edu/~pedrod/). It's densely packed with valuable information, but not opaque.

花点时间看这个. 做笔记. 如果您还不完全理解，请不要担心.

The whole paper is packed with value, but I want to call out two points:

- **Data alone is not enough.** This is where science meets art in machine-learning. Quoting Domingos: "... the need for knowledge in learning should not be surprising. Machine learning is not magic; it can’t get something from nothing. What it does is get more from less. Programming, like all engineering, is a lot of work: we have to build everything from scratch. Learning is more like farming, which lets nature do most of the work. Farmers combine seeds with nutrients to grow crops. Learners combine knowledge with data to grow programs."
 - **更多数据可以击败更聪明的算法.**听着，程序员. 我们喜欢很酷的工具. 抵制重新发明轮子或过度设计解决方案的诱惑. 你的出发点是 [Do the Simplest Thing that Could _Possibly_ Work](http://www.artima.com/intv/simplest3.html) . 引用 Domingos 的话：“假设你已经构建了最好的一组特征，但是你得到的分类器仍然不够准确.你现在能做什么？主要有两个选择：设计更好的学习算法，或者收集更多数据.[...]根据经验，拥有大量数据的愚蠢算法胜过拥有少量数据的聪明算法.（毕竟，机器学习就是让数据完成繁重的工作.） &quot;

When you work on a real Machine Learning problem, you should focus your efforts on your **domain knowledge** and **data** before optimizing your choice of algorithms. Prefer to do simple things until you _have_ to increase complexity. You should not rush into neural networks because you think they're cool. To improve your model, **get more data.** Then use your knowledge of the problem to [explore and process](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning) the data. You should only optimize the choice of algorithms after you have gathered enough data, and you've processed it well.

## Jargon note

* [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)
* Another handy term: ["Data Engineering."](https://www.coursera.org/articles/what-does-a-data-engineer-do-and-how-do-i-become-one)
  * ["MLOps"](https://ml-ops.org/) overlaps with Data Eng, and there's [an introductory MLOps section later in this guide](#production-deployment-mlops).

----

## Play to learn

接下来，从**一个或多个**笔记本开始播放.

- [Dr. Randal Olson's Example Machine Learning notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb)：“假设我们正在为一家刚刚获得资金创建智能手机应用程序的初创公司工作，该应用程序可以从智能手机上拍摄的照片中自动识别花卉种类.我们的数据科学负责人要求我们创建一个演示机器学习该模型对花朵进行四次测量（萼片长度、萼片宽度、花瓣长度和花瓣宽度），并仅根据这些测量值识别物种.”
    - [Launch in Binder, no installation steps required](https://mybinder.org/v2/gh/rhiever/Data-Analysis-and-Machine-Learning-Projects/master?filepath=example-data-science-notebook%2FExample%20Machine%20Learning%20Notebook.ipynb)
- 按主题分类的各种笔记本：
    - [trekhleb/machine-learning-experiments](https://github.com/trekhleb/machine-learning-experiments)
    - [trekhleb/homemade-machine-learning](https://github.com/trekhleb/homemade-machine-learning)
- Notebooks in a series:
    - [ageron/handson-ml2](https://github.com/ageron/handson-ml2)  - “Jupyter 笔记本，带您了解 Python 中机器学习和深度学习的基础知识.”  Scikit-Learn、Keras、TensorFlow 2.

Find more great Jupyter Notebooks when you're ready:

* **[Jupyter's official Gallery of Interesting Jupyter Notebooks: Statistics, Machine Learning and Data Science](https://github.com/jupyter/jupyter/wiki)** ([permalink](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks/ae03c01ed25024aa06a4479ea600895d59b38bc4))

----

## Immerse yourself

Pick one of the courses below and start on your way.

## [Recommended course: Prof. Andrew Ng's _Machine Learning_ on Coursera](https://www.coursera.org/learn/machine-learning)

**[Prof. Andrew Ng's](https://hai.stanford.edu/people/andrew-ng) [_Machine Learning_](https://www.coursera.org/learn/machine-learning) is a popular and esteemed free online course. I've seen it [recommended](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Cory-Hicks-1) [often.](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Xavier-Amatriain) [And emphatically.](https://www.forbes.com/sites/anthonykosner/2013/12/29/why-is-machine-learning-cs-229-the-most-popular-course-at-stanford/)**

建议拿一本教科书作为深入的参考. 我看到最推荐的两个是 _[Understanding Machine Learning](https://web.archive.org/web/20210717194345/http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/copy.html)_
and _[Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)_. [You only need to use one of the two options as your main reference; here's some context/comparison to help you pick which one is right for you.](https://github.com/hangtwenty/dive-into-machine-learning/issues/29)

### Public datasets and pet projects

您可能想在旁边玩一个宠物项目. 当你准备好了，你
could explore one of these: [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets), [paperswithcode.com/datasets](https://paperswithcode.com/datasets), [datasetlist.com](https://www.datasetlist.com/)

### Tips for this course

* [Study tips for Prof. Andrew Ng's course, by Ray Li](https://rayli.net/blog/data/coursera-machine-learning-review/)
* 如果您想知道，_它仍然是一门相关的课程吗？_ 或想知道它是否适合您，请查看以下评论​​：
    * [Review: Andrew Ng's Machine Learning Course](https://towardsdatascience.com/review-andrew-ngs-machine-learning-course-b905aafdb7d9)
    * [The user reviews on Coursera](https://www.coursera.org/learn/machine-learning/reviews)

### Tips for studying on a busy schedule

每周都很难抽出时间. 所以，你可以尝试在你有空的时间内更有效地学习. 以下是一些方法：

* ["Learning How to Learn" by Barbara Oakley](https://www.coursera.org/learn/learning-how-to-learn/) 由 Barbara Oakley 提供，Coursera 上的免费视频课程.
 * 喜欢书籍/有声读物？ 这些是很好的选择：
  * [Barbara Oakley's book _A Mind for Numbers: How to Excel at Math and Science_](https://barbaraoakley.com/books/a-mind-for-numbers) ([reviews](https://www.goodreads.com/book/show/18693655-a-mind-for-numbers)) — "We all have what it takes to excel in areas that don't seem to come naturally to us at first"
  * [_Make It Stick: the Science of Successful Learning_](https://www.retrievalpractice.org/make-it-stick) ([reviews](https://www.goodreads.com/book/show/18770267-make-it-stick))

### Take my tips with a grain of salt

I am not a machine learning expert. I'm just a software developer and these resources/tips were useful to me as I learned some ML on the side.

## Other courses

* **Data science courses as Jupyter Notebooks:**
  * [Practical Data Science](http://radimrehurek.com/data_science_python/)
  * [Python Data Science Handbook, as Jupyter Notebooks](https://jakevdp.github.io/PythonDataScienceHandbook/)
*  [`microsoft/Data-Science-For-Beginners`](https://github.com/microsoft/Data-Science-For-Beginners) — [added in 2021](https://dev.to/azure/free-data-science-for-beginners-curriculum-on-github-1hme) — "10-week, 20-lesson curriculum all about Data Science. Each lesson includes pre-lesson and post-lesson quizzes, written instructions to complete the lesson, a solution, and an assignment. Our project-based pedagogy allows you to learn while building, a proven way for new skills to 'stick'."
  * See also [`microsoft/ML-For-Beginners`](https://github.com/microsoft/ML-For-Beginners)

<details>
<summary><i>More free online courses I&#39;ve seen recommended.</i><b>我看到推荐的更多免费在线课程。</b> <i>(Machine Learning, Data Science, and related topics.)</i> <b>（机器学习、数据科学和相关主题。）</b></summary>

* Coursera  [Data Science Specialization](https://www.coursera.org/specializations/jhu-data-science)
* [Prof. Pedro Domingos's introductory video series](https://www.youtube.com/playlist?list=PLTPQEx-31JXgtDaC6-3HxWcp7fq4N8YGr). [Prof. Pedro Domingos](https://homes.cs.washington.edu/~pedrod/) wrote the paper ["A Few Useful Things to Know About Machine Learning"](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)，您可能还记得本指南前面的内容.
* [`ossu/data-science`](https://github.com/ossu/data-science) （也可以看看 [`ossu/computer-science`](https://github.com/ossu/computer-science))
* [Stanford CS229: Machine Learning](https://github.com/afshinea/stanford-cs-229-machine-learning)
* [Harvard CS109: Data Science](https://cs109.github.io/2015/)
* [Advanced Statistical Computing (Vanderbilt BIOS8366)](http://stronginference.com/Bios8366/lectures.html). Interactive.
* Kevin Markham's video series, [Intro to Machine Learning with scikit-learn](http://blog.kaggle.com/2015/04/08/new-video-series-introduction-to-machine-learning-with-scikit-learn/)，从我们已经介绍的内容开始，然后在舒适的地方继续.
* [UC Berkeley's Data 8: The Foundations of Data Science](http://data8.org/) course and the textbook [Computational and Inferential Thinking](https://www.inferentialthinking.com/) 教授数据科学中的关键概念.
* Mark A. Girolami 教授 [Machine Learning Module (GitHub Mirror).](https://github.com/josephmisiti/machine-learning-module) “适合有很强数学背景的人.”
* [An epic Quora thread: How can I become a data scientist?](https://www.quora.com/How-can-I-become-a-data-scientist?redirected_qid=59455)

</details>

## Getting Help: Questions, Answers, Chats

Start with the support forums and chats related to the course(s) you're taking.

查看 [datascience.stackexchange.com](https://datascience.stackexchange.com/) and [stats.stackexchange.com – such as the tag, _machine-learning_.](https://stats.stackexchange.com/questions/tagged/machine-learning?sort=frequent&pageSize=15) 有一些subreddits，比如 [/r/LearningMachineLearning](https://www.reddit.com/r/learningmachinelearning) and [/r/MachineLearning](https://www.reddit.com/r/machinelearning).

不要忘记聚会. 此外，现在围绕 ML 生态系统有许多活跃且有用的在线社区. 在项目页面等上寻找聊天邀请.

## Supplement: Learning Pandas well

你会想要更熟悉 Pandas.

* **Essential**: [Things in Pandas I Wish I'd Had Known Earlier](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb) (as a Jupyter Notebook)
* **Essential**: [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* Another helpful tutorial: [Real World Data Cleanup with Python and Pandas](https://trendct.org/2016/08/05/real-world-data-cleanup-with-python-and-pandas/)
* [Video series from Data School, about Pandas](https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y) .  “30个常见熊猫任务的参考指南（加上6小时的支持视频）.”
* 以下是我在继续学习时发现特别有用的一些文档：
  * [Cookbook](http://pandas.pydata.org/pandas-docs/stable/cookbook.html)
  * [Data Structures](http://pandas.pydata.org/pandas-docs/stable/dsintro.html), esp. [DataFrame](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe) section
  * [Reshaping by pivoting DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/reshaping.html)
  * [Computational tools](http://pandas.pydata.org/pandas-docs/stable/computation.html) and [StackExchange thread: "What is covariance in plain language?"](https://stats.stackexchange.com/questions/29713/what-is-covariance-in-plain-language)
  * [Group By (split, apply, and combine DataFrames)](http://pandas.pydata.org/pandas-docs/stable/groupby.html)
  * [Visualizing your DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html)
*缩放“熊猫”和替代品的书签
  * [`dask`](https://dask.org/): A Pandas-like interface, but for larger-than-memory data and "under the hood" parallelism.
  * [`vaex`](https://vaex.io)：“用于 Python、ML 的核外混合 Apache Arrow/NumPy DataFrame，以每秒 10 亿行的速度可视化和探索大表格数据”

## Supplement: Troubleshooting

These debugging tools can be used inside (or outside) a Jupyter notebook:

* [`birdseye`](https://birdseye.readthedocs.io/en/latest/integrations.html#jupyter-ipython-notebooks),
  [`snoop`](https://github.com/alexmojaki/snoop)
* [`pandas-log`](https://github.com/eyaltrabelsi/pandas-log.git)

There are many more tools than that, but those might get you started, or might be
especially useful while you're learning. Beyond learning, troubleshooting is more than just
logs or debuggers, of course... [there's also some MLOps links, later in this guide](#production-deployment-mlops).

## Supplement: Cheat Sheets

Some good cheat sheets I've come across. (Please [submit a Pull Request](https://github.com/hangtwenty/dive-into-machine-learning/pulls) 添加其他有用的备忘单.）

* [scikit-learn algorithm cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
* [`FavioVazquez/ds-cheatsheets`](https://github.com/FavioVazquez/ds-cheatsheets)
* 统计数据
  * [`wzchen/probability-cheatsheet`](https://github.com/wzchen/probability_cheatsheet) - “这份备忘单是一份 10 页的概率参考资料，涵盖了一个学期的概论介绍.备忘单基于哈佛的概论概论课程 Stat 110.它由前 Stat 110 教学研究员 William Chen 和 Stat 合着110 乔布利茨斯坦教授.” 
  * [Probabilities and statistics refresher](https://stanford.edu/~shervine/teaching/cs-229/refresher-probabilities-statistics) 备忘单来自 [Stanford CS 229](https://github.com/afshinea/stanford-cs-229-machine-learning)
* [Stanford CS 229](https://github.com/afshinea/stanford-cs-229-machine-learning) [cheat sheets](https://stanford.edu/~shervine/teaching/cs-229/), available on the web and [as PDFs](https://github.com/afshinea/stanford-cs-229-machine-learning/tree/master/en)
  * [Supervised learning cheat sheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-supervised-learning)
  * [Unsupervised learning cheat sheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-unsupervised-learning)
  * [Linear algebra and calculus refresher](https://stanford.edu/~shervine/teaching/cs-229/refresher-algebra-calculus)
  * [Machine Learning tips and tricks cheat sheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-machine-learning-tips-and-tricks)
  * [Deep learning cheatsheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-deep-learning) [(more)](https://stanford.edu/~shervine/teaching/cs-230/)


## Assorted Tips and Resources

## Risks - some starting points

"Machine learning systems automatically learn programs from data." Pedro Domingos, in ["A Few Useful Things to Know about Machine Learning."](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) The programs you generate will require maintenance. Like any way of creating programs faster, you can rack up [technical debt](https://en.wikipedia.org/wiki/Technical_debt).

这里是摘要 [Machine Learning: The High-Interest Credit Card of Technical Debt](https://research.google/pubs/pub43146/):

> Machine learning offers a fantastically powerful toolkit for building complex systems quickly. This paper argues that it is dangerous to think of these quick wins as coming for free. Using the framework of technical debt, we note that it is remarkably easy to incur massive ongoing maintenance costs at the system level when applying machine learning. The goal of this paper is highlight several machine learning specific risk factors and design patterns to be avoided or refactored where possible. These include boundary erosion, entanglement, hidden feedback loops, undeclared consumers, data dependencies, changes in the external world, and a variety of system-level anti-patterns.

如果您遵循本指南，则应该阅读该论文. 你也可以 [listen to a podcast episode interviewing one of the authors of this paper](https://softwareengineeringdaily.com/2015/11/17/machine-learning-and-technical-debt-with-d-sculley/).

* **[Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning), “一个精选的开源库列表，用于部署、监控、版本和扩展你的机器学习.”** 它包括一个关于 [privacy-preserving ML](https://github.com/EthicalML/awesome-production-machine-learning#privacy-preserving-machine-learning)， 顺便一提！
* **[“机器学习规则：[可靠] ML 工程的最佳实践”](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)**，作者 Martin Zinkevich，关于 ML 工程实践.
* [The High Cost of Maintaining Machine Learning Systems](http://www.kdnuggets.com/2015/01/high-cost-machine-learning-technical-debt.html)
* [Overfitting vs. Underfitting: A Conceptual Explanation](https://towardsdatascience.com/overfitting-vs-underfitting-a-conceptual-explanation-d94ee20ca7f9)
* [11 Clever Methods of Overfitting and How to Avoid Them](http://hunch.net/?p=22)
* ["So, you want to build an ethical algorithm?" An interactive tool to prompt discussions](https://cdt.info/ddtool/) [(source)](https://github.com/numfocus/algorithm-ethics)

当然，这不是一个完整的列表！ 它们只是一些网关和起点.  _知道其他资源吗？ 请分享它们，欢迎请求请求！_

## Skilling up

有哪些练习方法？

<details>
<summary><strong>One way:</strong> competitions and challenges</summary>

你需要**练习.** [On Hacker News, user olympus commented to say you could use competitions to practice and evaluate yourself](https://news.ycombinator.com/item?id=10508565). [Kaggle](https://www.kaggle.com/competitions) and [ChaLearn](http://www.chalearn.org/) are hubs for Machine Learning competitions. (You can find more competitions [here](https://github.com/paperswithcode/releasing-research-code#results-leaderboards) or [here](https://towardsdatascience.com/12-data-science-ai-competitions-to-advance-your-skills-in-2021-32e3fcb95d8c).)

您还需要**理解.**您应该查看 Kaggle 竞赛获胜者对他们的解决方案的评价， [for example, the "No Free Hunch" blog](http://blog.kaggle.com/) . 一开始这些可能会让你头疼，但一旦你开始理解和欣赏这些，你就会知道你正在到达某个地方.

比赛和挑战只是练习的一种方式！ [Machine Learning isn't just about Kaggle competitions](https://jvns.ca/blog/2014/06/19/machine-learning-isnt-kaggle-competitions).

</details>

<details>
<summary><strong>另一种方法：</strong>尝试做一些实践研究</summary>

这是一种互补的练习方式：**做练习研究.**

 1. **问一个问题. 开始探索一些数据.** ["most important thing in data science is the question"](https://github.com/DataScienceSpecialization/courses/blob/master/01_DataScientistToolbox/03_02_whatIsData/index.Rmd#the-data-is-the-second-most-important-thing) ([Dr. Jeff T. Leek](https://github.com/jtleek) ）. 所以从一个问题开始. 然后，找到 [real data](https://github.com/caesar0301/awesome-public-datasets). Analyze it. Then ...
2. **Communicate results.** When you think you have a novel finding, ask for review. When you're still learning, ask in informal communities (some are [linked below](#some-communities-to-know-about)).
3. **Learn from feedback.** Consider [learning in public](https://www.swyx.io/learn-in-public/), it works great for some folks. (Don't pressure yourself yet though! Everybody is different, and it's good to know your learning style.) 

你怎么能想出有趣的问题？ 这是一种方法. 每周选择一天 [look for public datasets](https://github.com/caesar0301/awesome-public-datasets) and write down some questions that come to mind. Also, sign up for [Data is Plural](https://tinyletter.com/data-is-plural)<i>, a newsletter of interesting datasets.</i> <b>，有趣的数据集的时事通讯。</b> <i>When a question inspires you, try exploring it with the skills you&#39;re learning.</i><b>当一个问题激发了你的灵感时，试着用你正在学习的技能来探索它。</b>

这个建议，做实践研究和从复习中学习，是基于 [a conversation](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-153934120) 和 [Dr. Randal S. Olson](http://www.randalolson.com/) . 这是奥尔森的更多建议， [quoted 和 permission:](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-154135498)

 &gt; 我认为最好的建议是告诉人们始终清楚地展示他们的方法，并避免过度解释他们的结果. 作为专家的一部分是知道很少有明确的答案，尤其是当您使用真实数据时.

当你重复这个过程时，你的实践研究会变得更加科学、有趣和专注. 还， [here's a video about the scientific method in data science.](https://101.datascience.community/2012/06/27/the-data-scientific-method/))

</details>

<details>
<summary>更多机器学习职业相关链接</summary>

* ["Advice on building a machine learning career and reading research papers by Prof. Andrew Ng"](https://www.kdnuggets.com/2019/09/advice-building-machine-learning-career-research-papers-andrew-ng.html)
* Some links for finding/following interesting papers/code:
    * [Papers With Code](https://paperswithcode.com/) 是一个受欢迎的网站，它可以引导您访问其他资源. [github.com/paperswithcode](https://github.com/paperswithcode)
    * [MIT: Papers + Code](https://mitibmwatsonailab.mit.edu/research/papers-code/) ——“同行评审是科学验证的命脉，也是防止人工智能失控炒作的护栏.我们对在顶级场所发表论文的承诺反映了我们在真实、可重复和真正创新方面的基础.”
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

 &gt; * **开放同行评审：**我们为同行评审提供了一个可配置的平台，该平台概括了许多微妙的开放等级，允许会议组织者、期刊和其他“评审实体”配置他们选择的具体政策. 我们打算充当不同政策的试验台，帮助科学界尝试开放学术，同时解决有关保密、归属和偏见的合理问题.
> * **Open Publishing:** Track submissions, coordinate the efforts of editors, reviewers and authors, and host… Sharded and distributed for speed and reliability.
> * **Open Access:** Free access to papers for all, free paper submissions. No fees.

<details>
<summary><em>更多关于 OpenReview.net</em></summary>

> * **Open Discussion:** Hosting of accepted papers, with their reviews, comments. Continued discussion forum associated with the paper post acceptance. Publication venue chairs/editors can control structure of review/comment forms, read/write access, and its timing.
&gt; * **开放目录：** 包含利益冲突信息的人员集合，包括机构和关系，例如共同作者、共同 PI、同事、顾问/顾问和家庭关系.
> * **Open Recommendations:** Models of scientific topics and expertise. Directory of people includes scientific expertise. Reviewer-paper matching for conferences with thousands of submissions, incorporating expertise, bidding, constraints, and reviewer balancing of various sorts. Paper recommendation to users.
> * **Open API:** We provide a simple REST API [...]
> * **Open Source:** We are committed to open source. Many parts of OpenReview are already in the [OpenReview organization on GitHub](https://github.com/openreview) . 一些进一步的版本正在等待对代码库的专业安全审查.

> * [OpenReview.net](https://openreview.net/) is created by Andrew McCallum’s Information Extraction and Synthesis Laboratory in the College of Information and Computer Sciences at University of Massachusetts Amherst
>
> * [OpenReview.net](https://openreview.net/) is built over an earlier version described in the paper [Open Scholarship and Peer Review: a Time for Experimentation](https://openreview.net/forum?id=xf0zSBd2iufMg) published in the [ICML 2013 Peer Review Workshop](https://openreview.net/group?id=ICML.cc/2013/PeerReview).
>
> * OpenReview is a long-term project to advance science through improved peer review, with legal nonprofit status through Code for Science & Society. We gratefully acknowledge the support of the great diversity of [OpenReview Sponsors](https://openreview.net/sponsors)––scientific peer review is sacrosanct, and should not be owned by any one sponsor.

</details>

### Production, Deployment, [MLOps](https://ml-ops.org/)

If you are learning about MLOps but find it overwhelming, these resources might help you get your bearings:

* [MLOps Stack Template](https://valohai.com/blog/the-mlops-stack/) 亨利克·斯科格斯特罗姆
* [Lessons on ML Platforms from Netflix, DoorDash, Spotify, and more](https://towardsdatascience.com/lessons-on-ml-platforms-from-netflix-doordash-spotify-and-more-f455400115c7) 作者：Ernest Chan 在 *Towards Data Science*

推荐的收藏/收藏/观看：

* **[EthicalML/awesome-artificial-intelligence-guidelines](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)**
* **[EthicalML/awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning#privacy-preserving-machine-learning)**
* **[visenger/awesome-ml-model-governance](https://github.com/visenger/Awesome-ML-Model-Governance)**
* **[visenger/awesome-MLOps](https://github.com/visenger/awesome-mlops)**

----

## Deep Learning

Take note: some experts warn us not to get too far ahead of ourselves, and encourage learning ML fundamentals before moving onto deep learning. That's paraphrasing from some of the linked coursework in this guide — for example, Prof. Andrew Ng encourages building foundations in ML before studying DL. Perhaps you're ready for that now, or perhaps you'd like to get started soon and learn some DL in parallel to your other ML learnings.

When you're ready to dive into Deep Learning, here are some helpful resources.

* **[_Dive into Deep Learning_](https://d2l.ai/) - An interactive book about deep learning** ([view on GitHub](https://github.com/d2l-ai/d2l-en))
  * Quickstart:
    * [Run this book locally, using Jupyter Notebooks](https://d2l.ai/chapter_installation/index.html)
    * [Run this book in your browser, using Google Colab](https://d2l.ai/chapter_appendix-tools-for-deep-learning/colab.html)
  * “使用 NumPy/MXNet、PyTorch 和 TensorFlow 实现”
  *“被来自 50 个国家的 200 所大学采用”
  *“整本书是在 Jupyter 笔记本中起草的，将说明图、数学和交互式示例与自包含代码无缝集成.” 
  * "You can modify the code and tune hyperparameters to get instant feedback to accumulate practical experiences in deep learning."
* [`explosion/thinc`](https://github.com/explosion/thinc) 是一个有趣的库，包含 **PyTorch**、**TensorFlow** 和 **MXNet** 模型. 
  *“使用组合而不是继承来定义模型的简明函数式编程方法.”
  * "Integrated config system to describe trees of objects and hyperparameters."
* [`fastai/fastbook`](https://github.com/fastai/fastbook) Jeremy Howard 和 Sylvain Gugger 着——“深度学习、fastai 和 PyTorch 简介”.
* **[Prof. Andrew Ng's](https://scholar.google.com/citations?user=mG4imMEAAAAJ&hl=en) [courses on Deep Learning](https://www.coursera.org/specializations/deep-learning)!** 作为课程的一部分，有五门课程 [Deep Learning Specialization on Coursera](https://www.coursera.org/specializations/deep-learning). These courses are part of his new venture, [deeplearning.ai](https://www.deeplearning.ai)
  *一些关于它的课程笔记： [ashishpatel26/Andrew-NG-Notes](https://github.com/ashishpatel26/Andrew-NG-Notes)
* **[_Deep Learning_](https://www.deeplearningbook.org/), a free book published MIT Press.** By Ian Goodfellow, Yoshua Bengio and Aaron Courville.
  * A notable testimonial for it is here: ["What are the best ways to pick up Deep Learning skills as an engineer?"](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer)
* [paperswithcode.com](https://paperswithcode.com/) — "The mission of Papers with Code is to create a free and open resource with Machine Learning papers, code, datasets, methods and evaluation tables."
* [`labmlai/annotated_deep_learning_paper_implementations`](https://github.com/labmlai/annotated_deep_learning_paper_implementations)  ——“深度学习论文的实现/教程，并排注释.” 其中50多个！ 真的很好的注释和解释.
* [Distill.pub](https://distill.pub/about/) 发布探索性的解释，绝对值得探索和关注！

### Easier sharing of deep learning models and demos

* **[Replicate](https://replicate.com) "makes it easy to share a running machine learning model"**
  * 从您的浏览器轻松试用深度学习模型
  * 演示链接到 GitHub 上的论文/代码，如果你想深入了解一些东西是如何工作
  * The models run in containers built by [`cog`](https://github.com/replicate/cog) ，“机器学习容器”. 它是一个开源工具，用于将模型放入可重现的 Docker 容器中.

----

## Collaborate with Domain Experts

Machine Learning can be powerful, but it is not magic.

Whenever you apply Machine Learning to solve a problem, you are going to be working in some specific problem domain. To get good results, you or your team will need "substantive expertise" (to re-use a phrase from earlier), which is related to "domain knowledge." Learn what you can, for yourself... But you should also **collaborate with experts.** You'll have better results if you collaborate with [subject-matter experts and domain experts](https://en.wikipedia.org/wiki/Subject-matter_expert#Domain_expert_(software)).

### Machine Learning and User Experience (UX)

I couldn't say it better:

&gt; **机器学习无法弄清楚要解决什么问题.**如果你不符合人类的需求，你只会构建一个非常强大的系统来解决一个非常小的——或者可能不存在的——问题.

该报价来自 ["The UX of AI" by Josh Lovejoy](https://design.google/library/ux-ai/) . 换句话说， **[You Are Not The User](https://www.nngroup.com/articles/false-consensus/).** Suggested reading: [Martin Zinkevich's "Rules of ML Engineering", Rule #23: "You are not a typical end user"](https://developers.google.com/machine-learning/guides/rules-of-ml/#human_analysis_of_the_system)

---

## More Data Science materials

以下是一些额外的数据科学资源：

* **[Python Data Science Handbook, as Jupyter Notebooks](https://jakevdp.github.io/PythonDataScienceHandbook/)**
* 可访问的数据科学书籍，无需编码经验： [_Data Smart_ by John Foreman](https://www.goodreads.com/book/show/17682206-data-smart)
* [Data Science Workflow: Overview and Challenges](https://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext) （阅读文章*以及*约瑟夫·麦卡锡的评论）
* [`r0f1/datascience`](https://github.com/r0f1/datascience) — "A curated list of awesome resources for practicing data science using Python, including not only libraries, but also links to tutorials, code snippets, blog posts and talks."

### Aside: Bayesian Statistics and Machine Learning

From [the "Bayesian Machine Learning" overview on Metacademy](https://metacademy.org/roadmaps/rgrosse/bayesian_machine_learning):

 &gt; ...贝叶斯思想在过去 20 年左右的时间里对机器学习产生了重大影响，因为它们在构建现实世界现象的结构化模型方面提供了灵活性. 算法的进步和不断增加的计算资源使得拟合以前被认为难以处理的丰富、高度结构化的模型成为可能.

<details>
<summary>Here are some awesome resources for learning Bayesian methods.</summary>

* **免费书** _[Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)_. Made with a "computation/understanding-first, mathematics-second point of view." Uses [PyMC](https://github.com/pymc-devs/pymc). It's available in print too!
* Like learning by playing? Me too. Try [19 Questions](https://github.com/fulldecent/19-questions), "a machine learning game which asks you questions and guesses an object you are thinking about," and **explains which Bayesian statistics techniques it's using!**
* [_Time Series Forecasting with Bayesian Modeling by Michael Grogan_](https://www.manning.com/liveprojectseries/time-series-forecasting-with-bayesian-modeling)，一个包含 5 个项目的系列 - 付费但第一个项目是免费的.
* [Bayesian Modelling in Python](https://github.com/markdregan/Bayesian-Modelling-in-Python) . 用途 [PyMC](https://github.com/pymc-devs/pymc) 也是.

</details>


----

## Non-sequitur

These next two links are non-sequiturs, not specifically related to ML. But since you're here, I have a hunch you might find them interesting too:

*玛吉阿普尔顿 ["A Brief History & Ethos of the Digital Garden"](https://maggieappleton.com/garden-history)
* 王肖恩 ["Digital Garden Terms of Service"](https://www.swyx.io/digital-garden-tos/)

----

## More ways to "Dive into Machine Learning"

以下是学习机器学习的其他一些指南. 它们可以是本指南的替代品或补充品.

* [Example Machine Learning notebook, exercise, and guide](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) by Dr. Randal S. Olson. Mentioned in Notebooks section as well, but it has a similar goal to this guide (introduce you, and show you where to go next). Rich "Further Reading" section.
  * [`microsoft/ML-For-Beginners`](https://github.com/microsoft/ML-For-Beginners)
  * [`microsoft/Data-Science-For-Beginners`](https://github.com/microsoft/Data-Science-For-Beginners)
  * [Machine Learning Crash Course from Google](https://developers.google.com/machine-learning/crash-course/) 使用 TensorFlow API.
  * [Amazon AWS](https://aws.amazon.com/training/learn-about/machine-learning/) Amazon have open up their internal training to the public and also offer certification.
* [Machine Learning for Developers](http://xyclade.github.io/MachineLearning/) 适合那些比 Python 更熟悉 Java 或 Scala 的人.
* [ageron/handson-ml2](https://github.com/ageron/handson-ml2) aka [_Hands-On Machine Learning_ 2nd Edition by Aurélien Geron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
* [rasbt/python-machine-learning-book-3rd-edition](https://github.com/rasbt/python-machine-learning-book-3rd-edition) aka [_Python Machine Learning: Machine Learning and Deep Learning with Python, scikit-learn, and TensorFlow 2_ by Sebastian Raschka and Vahid Mirjalili](https://www.goodreads.com/book/show/25545994-python-machine-learning)
* [`josephmisiti/awesome-machine-learning`](https://github.com/josephmisiti/awesome-machine-learning), [`svaksha/Pythonidae`](https://github.com/svaksha/pythonidae/blob/master/AI.md#machine-learning) 
* [Machine Learning for Software Engineers, by Nam Vu](https://github.com/ZuzooVn/machine-learning-for-software-engineers). In their words, it's a "top-down and results-first approach designed for software engineers." Definitely bookmark and use it, as well - it can answer lots of questions and connect you with great resources.
