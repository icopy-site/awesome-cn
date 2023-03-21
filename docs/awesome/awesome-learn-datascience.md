<div class="github-widget" data-repo="siboehm/awesome-learn-datascience"></div>
## Data Science Tutorials & Resources for Beginners [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

*如果你想了解更多关于数据科学的知识，但不知道从哪里开始，这个列表适合你！* :chart_with_upwards_trend:

不需要先前的知识，但 Python 和统计基础知识肯定会派上用场. 这些资源已被我当地数据科学学生组的许多初学者成功使用 [ML-KA](http://ml-ka.de/).

## What is Data Science?

- ['What is Data Science?' on Quora](https://www.quora.com/What-is-data-science)
- [Explanation of important vocabulary](https://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1?share=1) - 大数据、机器学习、数据科学的差异化.
- [Data Science for Business (Book)](https://amzn.to/2voPJUi) - 介绍数据科学及其作为商业资产的用途.

## Common Algorithms and Procedures

- [Supervised vs unsupervised learning](https://stackoverflow.com/questions/1832076/what-is-the-difference-between-supervised-learning-and-unsupervised-learning) - 两种最常见的机器学习算法. 
- [9 important Data Science algorithms and their implementation](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.05-Naive-Bayes.ipynb) 
- [Cross validation](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.03-Hyperparameters-and-Model-Validation.ipynb) - 评估算法/模型的性能.
- [Feature engineering](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.04-Feature-Engineering.ipynb) - 修改数据以更好地模拟预测.
- [Scientific introduction to 10 important Data Science algorithms](http://www.cs.umd.edu/%7Esamir/498/10Algorithms-08.pdf)
- [Model ensemble: Explanation](https://www.analyticsvidhya.com/blog/2017/02/introduction-to-ensembling-along-with-implementation-in-r/) - 将多个模型合并为一个以获得更好的性能.

## Data Science using Python
此列表仅涵盖 Python，因为许多人已经熟悉这门语言. [Data Science tutorials using R](https://github.com/ujjwalkarn/DataScienceR).

### General

- [O'Reilly Data Science from Scratch (Book)](https://amzn.to/2GSjjrK) - 带有示例代码的数据处理、实现和可视化.
- [Coursera Applied Data Science](https://www.coursera.org/specializations/data-science-python) - 使用 Python 的在线课程，涵盖大部分相关工具包. 

### Learning Python

- [YouTube tutorial series by sentdex](https://www.youtube.com/watch?v=oVp1vrfL_w4&list=PLQVvvaa0QuDe8XSftW-RAxdo6OmaeL85M)
- [Interactive Python tutorial website](http://www.learnpython.org/)

### numpy
[numpy](http://www.numpy.org/) 是一个 Python 库，它提供大型多维数组和对它们的快速数学运算.

- [Numpy tutorial on DataCamp](https://www.datacamp.com/community/tutorials/python-numpy-tutorial#gs.h3DvLnk)

### pandas
[pandas](http://pandas.pydata.org/index.html) 为 Python 提供高效的数据结构和分析工具. 它建立在 numpy 之上.

- [Introduction to pandas](http://www.synesthesiam.com/posts/an-introduction-to-pandas.html)
- [DataCamp pandas foundations](https://www.datacamp.com/courses/pandas-foundations) - 付费课程，但在创建帐户后有 30 天免费（足以完成课程）.
- [Pandas cheatsheet](https://github.com/pandas-dev/pandas/blob/master/doc/cheatsheet/Pandas_Cheat_Sheet.pdf) - 快速浏览最重要的功能.

### scikit-learn
[scikit-learn](http://scikit-learn.org/stable/) 是 Python 中最常用的机器学习和数据科学库.

- [Introduction and first model application](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.02-Introducing-Scikit-Learn.ipynb)
- [Rough guide for choosing estimators](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
- [Scikit-learn complete user guide](http://scikit-learn.org/stable/user_guide.html)
- [Model ensemble: Implementation in Python](http://machinelearningmastery.com/ensemble-machine-learning-algorithms-python-scikit-learn/)

### Jupyter Notebook
[Jupyter Notebook](https://jupyter.org/) 是一个用于轻松数据可视化和代码演示的 Web 应用程序.

- [Downloading and running first Jupyter notebook](https://jupyter.org/install.html)
- [Example notebook for data exploration](https://www.kaggle.com/sudalairajkumar/simple-exploration-notebook-instacart)
- [Seaborn data visualization tutorial](https://elitedatascience.com/python-seaborn-tutorial) - 适用于 Jupyter 的绘图库.


### Various other helpful tools and resources

- [Template folder structure for organizing Data Science projects](https://github.com/drivendata/cookiecutter-data-science)
- [Anaconda Python distribution](https://www.continuum.io/downloads) - 包含大多数重要的数据科学 Python 包.
- [Spacy](https://spacy.io/) - 用于处理基于文本的数据的开源工具包.
- [LightGBM gradient boosting framework](https://github.com/Microsoft/LightGBM) - 成功用于许多 Kaggle 挑战.
- [Amazon AWS](https://aws.amazon.com/) - 租用云服务器进行更耗时的计算（r4.xlarge 服务器是一个很好的起点）.


## Data Science Challenges for Beginners
按复杂性递增排序.

- [Walkthrough: House prices challenge](https://www.dataquest.io/blog/kaggle-getting-started/) - 通过简单的房价挑战演练.
- [Blood Donation Challenge](https://www.drivendata.org/competitions/2/warm-up-predict-blood-donations/) - 预测捐赠者是否会再次捐赠.
- [Titanic Challenge](https://www.kaggle.com/c/titanic) - 预测泰坦尼克号上的生存.
- [Water Pump Challenge](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/) - 预测非洲水泵的运行状况.

## More advanced resources and lists

- [Awesome Data Science](https://github.com/bulutyazilim/awesome-datascience)
- [Data Science Python](https://github.com/ujjwalkarn/DataSciencePython)
- [Machine Learning Tutorials](https://github.com/ujjwalkarn/Machine-Learning-Tutorials)

## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/siboehm/awesome-learn-datascience/blob/master/contributing.md) 第一的.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，Simon Böhm 已放弃所有版权和
本作品的相关或邻接权利. 免责声明：一些链接是附属链接.
