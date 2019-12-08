<div class="github-widget" data-repo="arbox/machine-learning-with-ruby"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<img src="https://raw.githubusercontent.com/arbox/machine-learning-with-ruby/master/header.png" align="center">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

[[RubyNLP](https://github.com/arbox/nlp-with-ruby) |
 [RubyDataScience](https://github.com/arbox/data-science-with-ruby) |
 [RubyInterop](https://github.com/arbox/ruby-interoperability)]


&gt; Ruby机器学习链接和资源的精选列表

[机器学习] [ml]是[计算科学] [cs]的领域-
通常嵌套在[AI] [ai]研究下-具有许多实用性
由于产生的算法的能力
系统地实施特定解决方案而无需明确
 程序员的指令.  显然，许多算法都需要定义
[features] [fe]的取值或较大的[training set] [ts]数据来推导
从解决.

该精选列表包括[_awesome _] [awesome]个库，
[机器学习] [ml]的数据源，教程和演示文稿
利用[Ruby] [ruby]编程语言.

此列表中的许多有用资源来自开发
[The Ruby Science Foundation] [sciruby]，我们的[贡献者] [贡献者]和
我们自己在各种ML应用程序上的日常工作.

：sparkles：每 [contribution](https://github.com/arbox/machine-learning-with-ruby/blob/master/contributing.md)  不客气！  通过拉添加链接
请求或提出问题以开始讨论.

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

用纯Ruby或其他语言编写的[机器学习] [ml]算法
带有适当绑定的Ruby编程语言.

### Frameworks

- [weka](https://github.com/paulgoetze/weka-jruby) -
  Weka的JRuby绑定，通过Weka实现的不同ML算法.
- [ai4r](https://github.com/SergioFierens/ai4r) -
  Ruby的人工智能.
- [classifier-reborn](https://github.com/jekyll/classifier-reborn) -
  通用分类器模块，允许贝叶斯和其他类型的分类.
  <sup>[[dep: GLS](#gls)]</sup>
- [scoruby](https://github.com/asafschers/scoruby) -
  Ruby评分API [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) （预测模型标记语言）.
- [rblearn](https://github.com/himkt/rblearn) -特征提取和交叉验证库.
- [data_modeler](https://github.com/giuse/data_modeler) -
   使用机器学习对数据建模.  足够的测试范围，快速入门的示例，完整的文档.  从1.0.0开始生产.
- [shogun](https://github.com/shogun-toolbox/shogun) -多功能且成熟
  机器学习工具箱 [Ruby bindings](https://github.com/shogun-toolbox/shogun/tree/develop/src/interfaces/ruby).
- [aws-sdk-machinelearning](https://github.com/aws/aws-sdk-ruby) -
  Amazon Web Services的机器学习API.
- [azure_mgmt_machine_learning](https://github.com/Azure/azure-sdk-for-ruby) -
  Microsoft Azure的机器学习API.
- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench) -
  用纯Ruby编写的成长型机器学习框架，使用高性能计算
  [Numo](https://github.com/ruby-numo/)，通过CUDA绑定 [Cumo](https://github.com/sonots/cumo).
  目前正在实现神经网络，进化策略，矢量量化以及大量
  示例和实用程序.
- [Deep NeuroEvolution](https://github.com/giuse/DNE) -
  基于的实验设置 [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench)
   寻求使用进化算法的深度神经网络（而不是训练）.  应用到
  [OpenAI Gym](https://github.com/openai/gym) 使用 [PyCall](https://github.com/mrkn/pycall.rb).
- [rumale](https://github.com/yoshoku/rumale) -
  Ruby中的Machine Learninig工具包，具有广泛的已实现算法
  （支持向量机，逻辑回归，线性回归，随机森林等）和
  类似于Python中[Scikit-Learn] [scikit]的接口.
- [eps](https://github.com/ankane/eps) -带出口的贝叶斯分类和线性回归
  使用 [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) and an alternative backend 使用 [GSL][gsl].

### Neural networks

- [neural-net-ruby](https://github.com/gbuesing/neural-net-ruby) -
  用Ruby编写的神经网络.
- [ruby-fann](https://github.com/tangledpath/ruby-fann) -
  Ruby绑定到 [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
- [cerebrum](https://github.com/irfansharif/cerebrum) -
  Ruby中人工神经网络的实验实现.
- [tlearn-rb](https://github.com/josephwilk/tlearn-rb) -
  Ruby的递归神经网络库.
- [brains](https://github.com/jedld/brains-jruby) -
  基于JRuby的前馈神经网络
  [brains](https://github.com/jedld/brains).
- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/neural_network) -
  框架，包括前馈和循环神经网络的纯Ruby实现
   （完全连接）.  可使用神经进化训练（自然进化策略算法）.
- [rann](https://github.com/mikecmpbll/rann) -
  灵活的Ruby ANN实现，具有反向支持（穿越时，可循环使用）
  网络），梯度检查，adagrad和并行批处理执行.

### Deep learning

- [tensor_stream](https://github.com/jedld/tensor_stream) -
  TensorFlow for Ruby的基础和独立重新实现.
- [red-chainer](https://github.com/red-data-tools/red-chainer) -
  Ruby的深度学习框架.
- [tensorflow](https://github.com/somaticio/tensorflow.rb) -的Ruby绑定 [TensorFlow](https://www.tensorflow.org/).
- [ruby-dnn](https://github.com/unagiootoro/ruby-dnn) -Ruby的简单深度学习.
- [torch-rb](https://github.com/ankane/torch-rb) -的Ruby绑定 [LibTorch](https://github.com/pytorch/pytorch)
  使用 [rice](https://github.com/jasonroelofs/rice).

### Kernel methods

- [rb-libsvm](https://github.com/febeling/rb-libsvm) -
  使用Ruby和 [LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) 图书馆.
  <sup>[[dep: bundled](#bundled)]</sup>

### Evolutionary algorithms

- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/optimizer/natural_evolution_strategies) -
  框架，包括自然进化策略算法的纯Ruby实现
  （黑盒优化），特别是指数NES（XNES），
  可分离NES（sNES），块对角NES（BDNES）等.
  应用包括神经网络搜索/训练（神经进化）.
- [simple_ga](https://github.com/giuse/simple_ga) -
  Ruby中最简单的遗传算法实现.

### Bayesian methods

- [linnaeus](https://github.com/djcp/linnaeus) -
  Redis支持的贝叶斯分类器.
- [naive_bayes](https://github.com/reddavis/Naive-Bayes) -
  简单的朴素贝叶斯分类器.
- [nbayes](https://github.com/oasic/nbayes) -
  Naive Bayes的全功能Ruby实现.

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
  Ruby中的k均值聚类.
- [k_means](https://github.com/reddavis/K-Means) -
  试图构建一个快速的，内存有效的K-Means程序.
- [knn](https://github.com/reddavis/knn) -
  简单的K最近邻算法.

### Linear classifiers

- [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) -
  Ruby与LIBLINEAR的接口（在文本分类方面比LIBSVM效率更高）.
- [liblinear-ruby](https://github.com/kei500/liblinear-ruby) -
  使用SWIG的LIBLINEAR的Ruby接口.

### Statistical models

- [rtimbl](https://github.com/maspwr/rtimbl) -
  Timbl框架中基于记忆的学习者.
- [lda-ruby](https://github.com/ealdent/lda-ruby) -
  Ruby的实现 [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
  （潜在Dirichlet分配），用于自动主题建模和文档聚类.
- [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) -
  基于OpenNLP Maxent框架的字符串数据的JRuby最大熵分类器.
- [omnicat](https://github.com/mustafaturan/omnicat) -
  用于文本分类的通用机架框架.
- [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) -
  朴素贝叶斯文本分类实施作为OmniCat分类器策略.
  <sup>[[dep: bundled](#bundled)]</sup>

### Gradient boosting

- [xgboost](https://github.com/PairOnAir/xgboost-ruby) -
  XGBoost的Ruby绑定.
  <sup>[[dep: XGBoost](#xgboost)]</sup>
- [xgb](https://github.com/ankane/xgb) -
  XGBoost的Ruby绑定.
  <sup>[[dep: XGBoost](#xgboost)]</sup>
- [lightgbm](https://github.com/ankane/lightgbm) -
  LightGBM的Ruby绑定.
  <sup>[[dep: LightGBM](#lightgbm)]</sup>

## Applications of machine learning

- [phashion](https://github.com/westonplatter/phashion) -
  围绕pHash的Ruby包装器，pHash是用于检测重复的多媒体文件的感知哈希库.
  <sup>[[ImageMagick](#imagemagick) | [libjpeg](#libjpeg)]</sup>

## Data structures

如果您打算实现自己的ML算法，那么您可能会感兴趣
 有效地存储功能集.  寻找合适
[data structures](https://github.com/arbox/data-science-with-ruby#data-structures)
在[使用Ruby的数据科学] [ds-with-ruby]列表中.

## Data visualization

请参考 [Data Visualization](https://github.com/arbox/data-science-with-ruby#visualization)
[使用Ruby的数据科学] [ds-with-ruby]列表上的“数据”部分.

## Articles, Posts, Talks, and Presentations

- 2019
  -_TensorStream：将机器学习带到Ruby_ [Joseph Emmanuel Dayo](https://www.linkedin.com/in/jdayo/)
    <sup>[[post](https://medium.com/@joseph.dayo/tensorstream-bringing-machine-learning-to-ruby-114582060e3d)]</sup>
  -_使用SVMKit_通过Ruby轻松进行机器学习 [@kojix](https://twitter.com/kojix2dayo)
    <sup>[[post](https://dev.to/kojix2/easy-machine-learning-with-ruby-using-svmkit-4n86)]</sup>
- 2018
  -_关于Ruby的深度学习编程_ [Kenta Murata](https://twitter.com/mrkn)
    和 [Yusaku Hatanaka ](https://twitter.com/hatappi)
    <sup>[[slides](https://speakerdeck.com/mrkn/deep-learning-programming-on-ruby) |
          [page](https://rubykaigi.org/2018/presentations/mrkn.html)]</sup>
  - _How to use trained Keras and TensorFlow machine learning models within Ruby on Rails_ by [Denis Sellu](https://twitter.com/denis_sellu)
    <sup>[[post](https://www.cookieshq.co.uk/posts/how-to-use-trained-keras-and-tensorflow-machine-learning-models-within-ruby-on-rails)]</sup>
- 2017
  -_JRuby上的科学计算_ by [Prasun Anand](https://twitter.com/prasun_anand)
    <sup>[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
    [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
   -_是食物吗？  机器学习入门_ [Matthew Mongeau](https://twitter.com/halogenandtoast)
    <sup>[[video](https://www.youtube.com/watch?v=8G709hKkthY) |
          [slides](https://www.slideshare.net/halogenandtoast/is-it-food)]</sup>
  -_Bayes是BAE_ [Richard Schneeman](https://twitter.com/schneems)
    <sup>[[video](https://www.youtube.com/watch?v=bQSzZrDDV80) |
          [slides](https://speakerdeck.com/schneems/bayes-is-bae)]</sup>
  -_Ruby圆桌会议：Ruby中的机器学习_ [RubyThursday](https://rubythursday.com/)
    <sup>[[video](https://www.youtube.com/watch?v=ScIFARN0jCo)]</sup>
- 2016
  -_使用Ruby进行实用机器学习_ [Jordan Hudgens](https://twitter.com/jordanhudgens)
    <sup>[[tutorial](https://www.crondose.com/2016/12/practical-machine-learning-ruby/)]</sup>
  -_深度学习：Ruby开发人员简介_ by [Geoffrey Litt](https://twitter.com/geoffreylitt)
    <sup>[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
  -_我如何使纯Ruby word2vec程序快3倍以上_ [Kei Sawada](https://twitter.com/remore)
    <sup>[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
  -_Dōmoarigatō，Roboto先生：使用Ruby进行机器学习 [Eric Weinstein](https://twitter.com/ericqweinstein)
    <sup>[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) |
          [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
  -_使用机器学习技术构建推荐引擎_ [Brian Sam-Bodden](https://twitter.com/bsbodden)
    <sup>[[video](https://www.youtube.com/watch?v=SRnM_P_ygqI)]</sup>
  -：火花：_SciRuby机器学习：当前状态和未来_作者 [Kenta Murata](https://twitter.com/mrkn)
    <sup>[[slides](https://speakerdeck.com/mrkn/sciruby-machine-learning-current-status-and-future) |
          [video: jp](https://www.youtube.com/watch?v=gfQ8XEy7vO4)]</sup>
  -_Ruby圆桌会议：Tensorflow简介_ [RubyThursday](https://rubythursday.com/)
    <sup>[[video](https://www.youtube.com/watch?v=pYC5mXHUWkc)]</sup>
- 2015
  -_通过Ruby_实现机器学习变得简单 [Lorenzo Masini](https://twitter.com/rugginoso)
    <sup>[[post](https://www.leanpanda.com/blog/2015-08-24-machine-learning-automatic-classification/)]</sup>
  -_使用Ruby机器学习查找巴黎希尔顿行情_ [Rick Carlino](https://github.com/RickCarlino)
    <sup>[[tutorial](https://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
- 2014
  -_测试驱动的神经网络_ [Matthew Kirk](https://twitter.com/mjkirk)
    <sup>[[video](https://www.youtube.com/watch?v=ppf8m-3uXvU&t=36s)]</sup>
  -_您今天可以在Ruby应用中使用的五种机器学习技术_ [Benjamin Curtis](https://twitter.com/stympy)
    <sup>[[video](https://www.youtube.com/watch?v=crziu7dk6Vw) |
          [slides](https://speakerdeck.com/stympy/machine-learning-techniques)]</sup>
  -_机器学习的乐趣和利润_ [John Paul Ashenfelter](https://twitter.com/johnashenfelter)
    <sup>[[video](https://www.youtube.com/watch?v=KC5MtKHm1O4)]</sup>
- 2013
  -_使用Ruby中的支持向量机进行情感分析_ [Matthew Kirk](https://twitter.com/mjkirk)
    <sup>[[video](https://www.youtube.com/watch?v=iSug6CgxWxc) |
          [code](https://github.com/hexgnu/sentiment_analyzer)]</sup>
  -_使用Ruby的推荐系统_ [Marcel Caraciolo](https://twitter.com/marcelcaraciolo)
    <sup>[[slides](https://www.slideshare.net/marcelcaraciolo/recommender-systems-with-ruby-adding-machine-learning-statistics-etc)]</sup>
  -_用Ruby检测人脸：坚果壳中的FFI_作者：[Marc Berszick]（）
    <sup>[[post](https://www.sitepoint.com/detecting-faces-with-ruby-ffi-in-a-nutshell/)]</sup>
- 2012
  -_使用Ruby进行机器学习，第一部分 [Vasily Vasinov](https://twitter.com/vasinov)
    <sup>[[tutorial](https://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
  -_Ruby中的递归神经网络_ [Joseph Wilk](https://twitter.com/josephwilk)
    <sup>[[post](http://blog.josephwilk.net/ruby/recurrent-neural-networks-in-ruby.html)]</sup>
  -_使用机器学习的推荐引擎和JRuby_ by [Matthew Kirk](https://twitter.com/mjkirk)
    <sup>[[video](https://www.youtube.com/watch?v=hsZcrlbBg_0)]</sup>
  -_实用机器学习和Rails_ by [Andrew Cantino](https://twitter.com/tectonic)
    和 [Ryan Stout](https://twitter.com/ryanstout)
    <sup>[[video](https://www.youtube.com/watch?v=vy_zQ1-F0JI)]</sup>

- 2011
  -_在Ruby中聚类_ [Colin Drake](https://twitter.com/colinfdrake)
    <sup>[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)]</sup>
  -_使用Ruby中的支持向量机进行文本分类_ [Rimas Silkaitis](https://twitter.com/neovintage)
    <sup>[[post](http://neovintage.org/2011/11/14/text-classification-using-support/)]</sup>
- 2010
  -_bayes_motel – Ruby_的贝叶斯分类，作者为 [Mike Perham](https://twitter.com/mperham)
    <sup>[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
  -_智能Ruby：机器学习入门_ [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[video](https://vimeo.com/22513786)]</sup>
- 2009

- 2008
  -_Ruby中的支持向量机（SVM）_ [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>
- 2007
  -_Ruby中的决策树学习_ [Ilya Grigorik](https://twitter.com/igrigorik)
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
    _有思想的机器学习：一种测试驱动的方法_.  奥赖利（O&#39;Reilly），2014年.
   <sup>[[Amazon](https://www.amazon.com/Thoughtful-Machine-Learning-Test-Driven-Approach/dp/1449374069) |
         [code](https://github.com/thoughtfulml/examples)]</sup>
- [Practical Artificial Intelligence](https://www.practicalai.io/) -
  有关人工智能和机器学习的博客，其中包含Ruby中的教程和代码示例.

## Community

- [SciRuby Mailing List](https://groups.google.com/forum/#!forum/sciruby-dev)
- [SciRuby Slack](https://sciruby.slack.com/)
- [Red Data Gitter](https://gitter.im/red-data-tools/)
- [Reddit](https://www.reddit.com/r/MachineLearning/search?q=Ruby&restrict_sr=on)
- [Stack Overflow](https://stackoverflow.com/search?q=machine+learning+ruby)
- [Twitter](https://twitter.com/search?q=Machine%20Learning%20Ruby&src=typd)
- [NonWebRuby](https://twitter.com/NonWebRuby)

## Related Resources

- <a name="lightgbm"></a>
  [LightGBM](https://github.com/microsoft/LightGBM)
- <a name="xgboost"></a>
  [XGBoost](https://github.com/dmlc/xgboost)
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
  在其他很棒的项目中，还有与NLP相关的项目的简短列表.
- [Ruby NLP](https://github.com/diasks2/ruby-nlp) -
  最新的NLP Ruby库集合.
- [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) -
  NLP相关资源的一般列表（大多数不适用于Ruby程序员）.
- [Scientific Ruby](http://sciruby.com/) -
  Ruby的线性代数，可视化和科学计算.
- [iRuby](https://github.com/SciRuby/iruby) -Jupyter的IRuby内核（以前为IPython）.
- [Kiba](https://github.com/thbar/kiba) -
  轻量级 [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) （提取，转换，加载）管道.
- [Awesome OCR](https://github.com/kba/awesome-ocr) -
  大量的OCR（光学字符识别）资源.
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) -
  使用TensorFlow库进行机器学习
- [rb-gsl](https://github.com/SciRuby/rb-gsl) -
  Ruby接口 [GNU Scientific Library](https://www.gnu.org/software/gsl/).
- [The Definitive Guide to Ruby's C API](https://silverhammermba.github.io/emberb/) -
  《使用C编程语言嵌入和扩展Ruby的现代参考和教程》.

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
Ruby的“很棒的ML” [Andrei Beliankou](https://github.com/arbox) 和
[Contributors][contributors].

在法律允许的范围内，将CC0与
“使用Ruby的Awesome ML”放弃了所有版权以及相关或邻近的权利
到“使用Ruby的超棒ML”.

您应该已经收到了CC0法律代码的副本以及此副本
 工作.  如果没有，请参阅 <https://creativecommons.org/publicdomain/zero/1.0/>  .

<!--- Links --->
[ruby]：https：//www.ruby-lang.org/en/
[真棒]：https://github.com/sindresorhus/awesome/blob/master/awesome.md
[change-pr]：https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md
[ml]：https：//en.wikipedia.org/wiki/Machine_learning
[ds-with-ruby]：https://github.com/arbox/data-science-with-ruby
[贡献者]：https://github.com/arbox/machine-learning-with-ruby/graphs/contributors
[sciruby]：https://github.com/sciruby
[ai]: https://en.wikipedia.org/wiki/Artificial_intelligence
[cs]：https：//en.wikipedia.org/wiki/Computational_science
[fe]：https：//en.wikipedia.org/wiki/Feature_engineering
[ts]：https：//en.wikipedia.org/wiki/Test_set
[gsl]：https://www.gnu.org/software/gsl/
[scikit]：https：//scikit-learn.org/stable/index.html
