<div class="github-widget" data-repo="arbox/machine-learning-with-ruby"></div>
<img src="https://raw.githubusercontent.com/arbox/machine-learning-with-ruby/master/header.png" align="center">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

[[RubyNLP](https://github.com/arbox/nlp-with-ruby) |
 [RubyDataScience](https://github.com/arbox/data-science-with-ruby) |
 [RubyInterop](https://github.com/arbox/ruby-interoperability)]


&gt; Ruby机器学习链接和资源的策划列表

[机器学习] [ml]是[计算科学] [cs]的领域 - 
经常嵌套在[AI] [ai]研究之下 - 有许多实用
应用程序由于生成算法的能力
系统地实施一个没有明确的具体解决方案
 程序员的指示.  显然，许多算法需要定义
[特征] [fe]查看数据的大型[训练集] [ts]以得出数据
解决方案.

这个策划列表包含[_awesome _] [awesome]库，
关于[机器学习]的数据源，教程和演示文稿[ml]
利用[Ruby] [ruby]编程语言.

此列表中的许多有用资源来自于开发
[红宝石科学基金会] [sciruby]，我们的[贡献者] [贡献者]和
我们自己的日常工作在各种ML应用程序.

：闪耀：每一个 [contribution](https://github.com/arbox/machine-learning-with-ruby/blob/master/contributing.md)  不客气！  通过pull添加链接
请求或创建问题以开始讨论.

跟着我们 [Twitter](https://twitter.com/NonWebRuby) 请传播
the word using the `#RubyML` hash tag!

<!-- nodoc -->

<!-- toc -->


<!-- tocstop -->

<!-- doc -->

## :sparkles: Tutorials

 请帮助我们填写此部分！  ：笑脸：

- [How to implement linear regression in Ruby](https://www.practicalai.io/implementing-linear-regression-using-ruby/)
  <sup>[[code](https://github.com/daugaard/example-linear-regression)]</sup>
- [How to implement classification using logistic regression in Ruby](https://www.practicalai.io/implementing-classification-using-logistic-regression-in-ruby/)
- [How to implement simple binary classification using a Neural Network in Ruby](https://www.practicalai.io/implementing-simple-classification-using-neural-network-in-ruby/)
  <sup>[[code](https://github.com/daugaard/example-neural-network)]</sup>
- [How to implement classification using a SVM in Ruby](https://www.practicalai.io/implementing-classification-using-a-svm-in-ruby/)
  <sup>[[code](https://github.com/daugaard/example-svm)]</sup>
- [Unsupervised learning using k-means clustering in Ruby](https://www.practicalai.io/unsupervised-learning-using-k-means-clustering-in-ruby/)
  <sup>[[code](https://github.com/daugaard/example-kmeans-clustering)]</sup>
- [Teaching an AI to play a simple game using Q-Learning in Ruby](https://www.practicalai.io/teaching-ai-play-simple-game-using-q-learning/)
  <sup>[[code](https://github.com/daugaard/q-learning-simple-game)]</sup>
- [Teaching a Neural Network to play a game using Q-Learning in Ruby](https://www.practicalai.io/teaching-a-neural-network-to-play-a-game-with-q-learning/)
  <sup>[[code](https://github.com/daugaard/q-learning-simple-game/tree/neuralnetwork)]</sup>
- [Using the Python scikit-learn machine learning library in Ruby using PyCall](https://www.practicalai.io/using-scikit-learn-machine-learning-library-in-ruby-using-pycall/)
  <sup>[[code](https://github.com/daugaard/scikit-learn-from-ruby)]</sup>
- [How to _evolve_ neural networks in Ruby using the Machine Learning Workbench](https://github.com/giuse/machine_learning_workbench/blob/master/examples/neuroevolution.rb)

## Machine Learning Libraries

[机器学习] [纯] Ruby中的[ml]算法或其他编写
编程语言与Ruby的适当绑定.

### Frameworks

- [weka](https://github.com/paulgoetze/weka-jruby) -
  针对Weka的JRuby绑定，通过Weka实现的不同ML算法.
- [ai4r](https://github.com/SergioFierens/ai4r) -
  Ruby的人工智能.
- [classifier-reborn](https://github.com/jekyll/classifier-reborn) -
  通用分类器模块允许贝叶斯和其他类型的分类.
  <sup>[[dep: GLS](#gls)]</sup>
- [scoruby](https://github.com/asafschers/scoruby) -
  Ruby评分API [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) （预测模型标记语言）.
- [rblearn](https://github.com/himkt/rblearn) - 特征提取和交叉验证库.
- [data_modeler](https://github.com/giuse/data_modeler) -
   使用机器学习建模数据.  充足的测试覆盖率，快速启动示例，完整的文档.  生产准备就绪1.0.0.
- [shogun](https://github.com/shogun-toolbox/shogun) - 多功能和成熟
  机器学习工具箱 [Ruby bindings](https://github.com/shogun-toolbox/shogun/tree/develop/src/interfaces/ruby).
- [aws-sdk-machinelearning](https://github.com/aws/aws-sdk-ruby) -
  亚马逊网络服务的机器学习API.
- [azure_mgmt_machine_learning](https://github.com/Azure/azure-sdk-for-ruby) -
  Microsoft Azure的机器学习API.
- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench) -
  越来越多的机器学习框架用纯Ruby编写，高性能计算使用
  [Numo](https://github.com/ruby-numo/)，CUDA绑定通过 [Cumo](https://github.com/sonots/cumo).
  目前正在实施神经网络，进化策略，矢量量化和大量
  示例和实用程序.
- [Deep NeuroEvolution](https://github.com/giuse/DNE) -
  实验装置基于 [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench)
   使用进化算法搜索深度神经网络（而不是训练）.  应用程序
  [OpenAI Gym](https://github.com/openai/gym) 运用 [PyCall](https://github.com/mrkn/pycall.rb).
- [rumale](https://github.com/yoshoku/rumale) -
  Ruby中的Machine Learninig工具包，具有广泛的实现算法
  （SVM，Logistic回归，线性回归，随机森林等）和
  接口类似于Python中的[Scikit-Learn] [scikit].
- [eps](https://github.com/ankane/eps) - Bayesian Classification and Linear Regression with exports
  运用 [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) and an alternative backend 运用 [GSL][gsl].

### Neural networks

- [neural-net-ruby](https://github.com/gbuesing/neural-net-ruby) -
  用Ruby编写的神经网络.
- [ruby-fann](https://github.com/tangledpath/ruby-fann) -
  Ruby绑定到 [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
- [cerebrum](https://github.com/irfansharif/cerebrum) -
  Ruby中人工神经网络的实验实现.
- [tlearn-rb](https://github.com/josephwilk/tlearn-rb) -
  Ruby的循环神经网络库.
- [brains](https://github.com/jedld/brains-jruby) -
  基于MATLAB的JRuby前馈神经网络
  [brains](https://github.com/jedld/brains).
- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/neural_network) -
  框架包括前向和递归神经网络的纯Ruby实现
   （完全连接）.  使用神经进化训练（自然进化策略算法）进行训练.
- [rann](https://github.com/mikecmpbll/rann) -
  使用backprop实现灵活的Ruby ANN（通过时间，用于循环使用）
  网），梯度检查，adagrad和并行批处理执行.
- [tensor_stream](https://github.com/jedld/tensor_stream) -
  为TensorFlow for Ruby进行的基础和独立重新实现.
- [red-chainer](https://github.com/red-data-tools/red-chainer) -
  Ruby的深度学习框架.
- [tensorflow](https://github.com/somaticio/tensorflow.rb) -  Ruby绑定 [TensorFlow](https://www.tensorflow.org/).


### Kernel methods

- [rb-libsvm](https://github.com/febeling/rb-libsvm) -
  支持Ruby和Ruby的矢量机 [LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) 图书馆.
  <sup>[[dep: bundled](#bundled)]</sup>

### Evolutionary algorithms

- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/optimizer/natural_evolution_strategies) -
  框架包括自然进化策略算法的纯Ruby实现
  （黑盒优化），特别是指数NES（XNES），
  可分离的NES（sNES），块对角线NES（BDNES）等.
  应用包括神经网络搜索/训练（神经进化）.
- [simple_ga](https://github.com/giuse/simple_ga) -
  Ruby中最简单的遗传算法实现.

### Bayesian methods

- [linnaeus](https://github.com/djcp/linnaeus) -
  Redis支持的贝叶斯分类器.
- [naive_bayes](https://github.com/reddavis/Naive-Bayes) -
  简单的朴素贝叶斯分类器.
- [nbayes](https://github.com/oasic/nbayes) -
  功能齐全的Ruby实现Naive Bayes.

### Decision trees

- [decisiontree](https://github.com/igrigorik/decisiontree) -
  纯Ruby中的决策树ID3算法.
  <sup>[[dep: GraphViz](#graphviz) |
        [post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.

### Clustering

- [flann](https://github.com/mariusmuja/flann) -
  近似最近邻居的快速库.
  <sup>[[flann](#flann)]</sup>
- [kmeans-clusterer](https://github.com/gbuesing/kmeans-clusterer) -
  k-means在Ruby中进行聚类.
- [k_means](https://github.com/reddavis/K-Means) -
  试图建立一个快速，内存效率高的K-Means程序.
- [knn](https://github.com/reddavis/knn) -
  简单K最近邻算法.

### Linear classifiers

- [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) -
  与LIBLINEAR的Ruby接口（比LIBSVM更有效地进行文本分类）.
- [liblinear-ruby](https://github.com/kei500/liblinear-ruby) -
  使用SWIG的Ruby接口到LIBLINEAR.

### Statistical models

- [rtimbl](https://github.com/maspwr/rtimbl) -
  来自Timbl框架的基于记忆的学习者.
- [lda-ruby](https://github.com/ealdent/lda-ruby) -
  Ruby的实现 [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
  （潜在Dirichlet分配）用于自动主题建模和文档聚类.
- [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) -
  JRuby字符串数据的最大熵分类器，基于OpenNLP Maxent框架.
- [omnicat](https://github.com/mustafaturan/omnicat) -
  用于文本分类的通用机架框架.
- [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) -
  Naive Bayes文本分类实现为OmniCat分类器策略.
  <sup>[[dep: bundled](#bundled)]</sup>

### Gradient boosting

- [xgboost](https://github.com/PairOnAir/xgboost-ruby) -  XGBoost的Ruby绑定
- [xgb](https://github.com/ankane/xgb) -  XGBoost的Ruby绑定
- [lightgbm](https://github.com/ankane/lightgbm) -  LightGBM的Ruby绑定

## Applications of machine learning

- [phashion](https://github.com/westonplatter/phashion) -
  围绕pHash的Ruby包装器，用于检测重复多媒体文件的感知哈希库.
  <sup>[[ImageMagick](#imagemagick) | [libjpeg](#libjpeg)]</sup>

## Data structures

如果你要实现自己的ML算法，你可能会感兴趣
 有效地存储您的功能集.  寻找合适
[data structures](https://github.com/arbox/data-science-with-ruby#data-structures)
在我们的[Ruby with Data Science] [ds-with-ruby]列表中.

## Data visualization

请参考 [Data Visualization](https://github.com/arbox/data-science-with-ruby#visualization)
关于[带有Ruby的数据科学] [ds-with-ruby]列表的部分.

## Articles, Posts, Talks, and Presentations

- 2019
  -  _TensorStream：将机器学习引入Ruby_ [Joseph Emmanuel Dayo](https://www.linkedin.com/in/jdayo/)
    <sup>[[post](https://medium.com/@joseph.dayo/tensorstream-bringing-machine-learning-to-ruby-114582060e3d)]</sup>
  - 使用SVMKit_的Ruby轻松学习机器 [@kojix](https://twitter.com/kojix2dayo)
    <sup>[[post](https://dev.to/kojix2/easy-machine-learning-with-ruby-using-svmkit-4n86)]</sup>
- 2018
  - 在Ruby_上的_Deep学习编程 [Kenta Murata](https://twitter.com/mrkn)
    ＆ [Yusaku Hatanaka ](https://twitter.com/hatappi)
    <sup>[[slides](https://speakerdeck.com/mrkn/deep-learning-programming-on-ruby) |
          [page](https://rubykaigi.org/2018/presentations/mrkn.html)]</sup>
  - 如何在Ruby on Rails_中使用经过训练的Keras和TensorFlow机器学习模型 [Denis Sellu](https://twitter.com/denis_sellu)
    <sup>[[post](https://www.cookieshq.co.uk/posts/how-to-use-trained-keras-and-tensorflow-machine-learning-models-within-ruby-on-rails)]</sup>
- 2017
  - 关于JRuby_的科学计算 [Prasun Anand](https://twitter.com/prasun_anand)
    <sup>[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
    [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
    - 这是食物吗？  机器学习简介_由 [Matthew Mongeau](https://twitter.com/halogenandtoast)
    <sup>[[video](https://www.youtube.com/watch?v=8G709hKkthY) |
          [slides](https://www.slideshare.net/halogenandtoast/is-it-food)]</sup>
  -  _Bayes是BAE_ by [Richard Schneeman](https://twitter.com/schneems)
    <sup>[[video](https://www.youtube.com/watch?v=bQSzZrDDV80) |
          [slides](https://speakerdeck.com/schneems/bayes-is-bae)]</sup>
  -  _Ruby圆桌会议：Ruby_中的机器学习 [RubyThursday](https://rubythursday.com/)
    <sup>[[video](https://www.youtube.com/watch?v=ScIFARN0jCo)]</sup>
- 2016
  - 使用Ruby_的_Practical Machine Learning [Jordan Hudgens](https://twitter.com/jordanhudgens)
    <sup>[[tutorial](https://www.crondose.com/2016/12/practical-machine-learning-ruby/)]</sup>
  -  _Deep Learning：Ruby Developers的简介_ [Geoffrey Litt](https://twitter.com/geoffreylitt)
    <sup>[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
  - 我如何使用一个纯Ruby的word2vec程序，速度提高3倍以上 [Kei Sawada](https://twitter.com/remore)
    <sup>[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
  - _Dōmoarigatō，Roboto先生：Ruby_的机器学习 [Eric Weinstein](https://twitter.com/ericqweinstein)
    <sup>[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) |
          [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
  -  _建立机器学习技术的推荐引擎_ [Brian Sam-Bodden](https://twitter.com/bsbodden)
    <sup>[[video](https://www.youtube.com/watch?v=SRnM_P_ygqI)]</sup>
  - ：sparkles：_SciRuby机器学习：当前状态和未来_ by [Kenta Murata](https://twitter.com/mrkn)
    <sup>[[slides](https://speakerdeck.com/mrkn/sciruby-machine-learning-current-status-and-future) |
          [video: jp](https://www.youtube.com/watch?v=gfQ8XEy7vO4)]</sup>
  -  _Ruby圆桌会议：Tensorflow_简介 [RubyThursday](https://rubythursday.com/)
    <sup>[[video](https://www.youtube.com/watch?v=pYC5mXHUWkc)]</sup>
- 2015
  - 使用Ruby_ by，_Machine Learning变得简单 [Lorenzo Masini](https://twitter.com/rugginoso)
    <sup>[[post](https://www.leanpanda.com/blog/2015-08-24-machine-learning-automatic-classification/)]</sup>
  - 使用Ruby机器学习查找Paris Hilton Quotes_ [Rick Carlino](https://github.com/RickCarlino)
    <sup>[[tutorial](https://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
- 2014
  -  _Test Driven Neural Networks_ by [Matthew Kirk](https://twitter.com/mjkirk)
    <sup>[[video](https://www.youtube.com/watch?v=ppf8m-3uXvU&t=36s)]</sup>
  -  _Five机器学习技术，您可以在今天的Ruby应用程序中使用 [Benjamin Curtis](https://twitter.com/stympy)
    <sup>[[video](https://www.youtube.com/watch?v=crziu7dk6Vw) |
          [slides](https://speakerdeck.com/stympy/machine-learning-techniques)]</sup>
  -  _Machine学习乐趣和利润 [John Paul Ashenfelter](https://twitter.com/johnashenfelter)
    <sup>[[video](https://www.youtube.com/watch?v=KC5MtKHm1O4)]</sup>
- 2013
  - 使用Ruby_by中的支持向量机进行_Sentiment分析 [Matthew Kirk](https://twitter.com/mjkirk)
    <sup>[[video](https://www.youtube.com/watch?v=iSug6CgxWxc) |
          [code](https://github.com/hexgnu/sentiment_analyzer)]</sup>
  - 使用Ruby_ by的_Recommender系统 [Marcel Caraciolo](https://twitter.com/marcelcaraciolo)
    <sup>[[slides](https://www.slideshare.net/marcelcaraciolo/recommender-systems-with-ruby-adding-machine-learning-statistics-etc)]</sup>
  - 使用Ruby检测面部：FFT in a Nutshell_ by [Marc Berszick]（）
    <sup>[[post](https://www.sitepoint.com/detecting-faces-with-ruby-ffi-in-a-nutshell/)]</sup>
- 2012
  - 使用Ruby学习_Machine，第一部分由 [Vasily Vasinov](https://twitter.com/vasinov)
    <sup>[[tutorial](https://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
  -  Ruby_by中的_Recurrent神经网络 [Joseph Wilk](https://twitter.com/josephwilk)
    <sup>[[post](http://blog.josephwilk.net/ruby/recurrent-neural-networks-in-ruby.html)]</sup>
  -  _Recommendation Engines使用机器学习，和JRuby_ by [Matthew Kirk](https://twitter.com/mjkirk)
    <sup>[[video](https://www.youtube.com/watch?v=hsZcrlbBg_0)]</sup>
  -  _Practical Machine Learning和Rails_ by [Andrew Cantino](https://twitter.com/tectonic)
    和 [Ryan Stout](https://twitter.com/ryanstout)
    <sup>[[video](https://www.youtube.com/watch?v=vy_zQ1-F0JI)]</sup>

- 2011
  - 在Ruby_中的_Clustering by [Colin Drake](https://twitter.com/colinfdrake)
    <sup>[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)]</sup>
  - 使用Ruby_by中的支持向量机进行_Text分类 [Rimas Silkaitis](https://twitter.com/neovintage)
    <sup>[[post](http://neovintage.org/2011/11/14/text-classification-using-support/)]</sup>
- 2010
  -  _bayes_motel  -  Ruby_的贝叶斯分类 [Mike Perham](https://twitter.com/mperham)
    <sup>[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
  -  _Intelligent Ruby：机器学习入门_ [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[video](https://vimeo.com/22513786)]</sup>
- 2009

- 2008
  - 在Ruby_中使用_Support Vector Machines（SVM） [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>
- 2007
  - 在Ruby_中的_Decision树学习 [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>

## Projects and Code Examples

- [Wine Clustering](https://github.com/hexgnu/wine_clustering) -
  葡萄酒质量评估采用不同的算法进行聚类.
- [simple_ga](https://github.com/giuse/simple_ga) -
  Ruby中遗传算法的基本（工作）演示.

## Heroku buildpacks

- [GSL and Ruby buildpack](https://github.com/tomwolfe/heroku-buildpack-gsl-ruby)
- [OpenCV and Ruby buildpack](https://github.com/lilibethdlc/heroku-buildpack-ruby-opencv)
- [ImageMagick buildpack](https://github.com/mcollina/heroku-buildpack-imagemagick)

## Books, Blogs, Channels

-  [Kirk, Matthew](https://twitter.com/mjkirk).
    _Thoughtful机器学习：一种测试驱动的方法_.  O&#39;Reilly，2014.
   <sup>[[Amazon](https://www.amazon.com/Thoughtful-Machine-Learning-Test-Driven-Approach/dp/1449374069) |
         [code](https://github.com/thoughtfulml/examples)]</sup>
- [Practical Artificial Intelligence](https://www.practicalai.io/) -
  关于人工智能和机器学习的博客，包含Ruby中的教程和代码示例.

## Community

- [SciRuby Mailing List](https://groups.google.com/forum/#!forum/sciruby-dev)
- [SciRuby Slack](https://sciruby.slack.com/)
- [Red Data Gitter](https://gitter.im/red-data-tools/)
- [Reddit](https://www.reddit.com/r/MachineLearning/search?q=Ruby&restrict_sr=on)
- [Stack Overflow](https://stackoverflow.com/search?q=machine+learning+ruby)
- [Twitter](https://twitter.com/search?q=Machine%20Learning%20Ruby&src=typd)
- [NonWebRuby](https://twitter.com/NonWebRuby)

## Related Resources

- <a name="gls"></a>
  [GSL（GNU科学图书馆）] [gls]
- <a name="opencv"></a>
  [OpenCV](https://opencv.org/)
- <a name="empty-lines-around-access-modifier"></a>
  [Graphviz](http://www.graphviz.org/)
- <a name="gnuplot"></a>
  [Gnuplot](http://www.gnuplot.info/)
- <a name="xquartz"></a>
  [X11/XQuartz](https://www.xquartz.org/)
- <a name="imagemagic"></a>
  [ImageMagick](https://www.imagemagick.org/script/index.php)
- <a name="r"></a>
  [R](http://www.r-project.org/)
- <a name="octave"></a>
  [Octave](https://www.gnu.org/software/octave/)
- [scikit-learn algorithm cheatsheet](https://scikit-learn.org/stable/tutorial/machine_learning_map/)
- [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing) -
  在其他令人敬畏的项目中，NLP相关项目的简短列表.
- [Ruby NLP](https://github.com/diasks2/ruby-nlp) -
  用于NLP的Ruby库的最新收集.
- [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) -
  NLP相关资源的一般列表（主要不适用于Ruby程序员）.
- [Scientific Ruby](http://sciruby.com/) -
  Ruby的线性代数，可视化和科学计算.
- [iRuby](https://github.com/SciRuby/iruby) - 用于Jupyter的IRuby内核（formelly IPython）.
- [Kiba](https://github.com/thbar/kiba) -
  轻量级 [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) （Extract，Transform，Load）管道.
- [Awesome OCR](https://github.com/kba/awesome-ocr) -
  多种OCR（光学字符识别）资源.
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) -
  使用TensorFlow库进行机器学习.
- [rb-gsl](https://github.com/SciRuby/rb-gsl) -
  Ruby接口 [GNU Scientific Library](https://www.gnu.org/software/gsl/).
- [The Definitive Guide to Ruby's C API](https://silverhammermba.github.io/emberb/) -
  使用C编程语言嵌入和扩展Ruby的现代参考和教程.

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
“令人敬畏的ML与Ruby`由 [Andrei Beliankou](https://github.com/arbox) 和
[Contributors][contributors].

在法律允许的范围内，与CC0相关联的人
“令人敬畏的ML with Ruby”已放弃所有版权及相关或相邻权利
用Ruby来“令人敬畏的ML”.

您应该已经收到了CC0 legalcode的副本
 工作.  如果没有，请参阅 <https://creativecommons.org/publicdomain/zero/1.0/>  .

<!--- Links --->
[ruby]：https：//www.ruby-lang.org/en/
[awesome]：https：//github.com/sindresorhus/awesome/blob/master/awesome.md
[change-pr]：https：//github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md
[ml]：https：//en.wikipedia.org/wiki/Machine_learning
[ds-with-ruby]：https：//github.com/arbox/data-science-with-ruby
[贡献者]：https：//github.com/arbox/machine-learning-with-ruby/graphs/contributors
[sciruby]：https：//github.com/sciruby
[ai]: https://en.wikipedia.org/wiki/Artificial_intelligence
[cs]：https：//en.wikipedia.org/wiki/Computational_science
[fe]：https：//en.wikipedia.org/wiki/Feature_engineering
[ts]：https：//en.wikipedia.org/wiki/Test_set
[gsl]：https：//www.gnu.org/software/gsl/
[scikit]：https：//scikit-learn.org/stable/index.html
