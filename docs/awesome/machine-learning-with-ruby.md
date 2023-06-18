<div class="github-widget" data-repo="arbox/machine-learning-with-ruby"></div>
<img title="Awesome Machine Learning with Ruby" alt="Awesome Machine Learning with Ruby" src="https://raw.githubusercontent.com/arbox/machine-learning-with-ruby/master/header.png" align="center">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

[[RubyNLP](https://github.com/arbox/nlp-with-ruby) |
 [RubyDataScience](https://github.com/arbox/data-science-with-ruby) |
 [RubyInterop](https://github.com/arbox/ruby-interoperability)]


&gt; Ruby 机器学习链接和资源的精选列表

[机器学习][ml]是[计算科学][cs]的一个领域——
通常嵌套在 [AI][ai] 研究下——有很多实用
应用程序由于产生的算法的能力
系统地实施特定的解决方案，无需明确
程序员的指令. 显然很多算法都需要一个定义
要查看的 [features][fe] 或更大的 [training set][ts] 数据来导出
解决方案来自.

这个精选列表包括 [_awesome_][awesome] 库，
关于 [机器学习][ml] 的数据源、教程和演示文稿
利用 [Ruby][ruby] 编程语言.

此列表中的许多有用资源来自开发者
[Ruby 科学基金会][sciruby]，我们的[贡献者][贡献者]和
我们自己在各种 ML 应用程序上的日常工作.

:sparkles: 每个 [contribution](https://github.com/arbox/machine-learning-with-ruby/blob/master/contributing.md) 欢迎！ 通过pull添加链接
请求或创建问题以开始讨论.

跟着我们 [Twitter](https://twitter.com/NonWebRuby) 请传播
the word using the `#RubyML` hash tag!

<!-- nodoc -->

<!-- toc -->


<!-- tocstop -->

<!-- doc -->

## :sparkles: Tutorials

请帮助我们填写此部分！  ：笑脸：
- [Ruby neural networks](https://www.honeybadger.io/blog/ruby-neural-networks/)
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

[机器学习][ml] 纯 Ruby 或其他语言编写的算法
具有适合 Ruby 绑定的编程语言.

### Frameworks

- [LangChain.rb](https://github.com/andreibondarev/langchainrb) -
  使用 Ruby 的 LangChain 构建 ML/AI 增压应用程序.
- [weka](https://github.com/paulgoetze/weka-jruby) -
  Weka 的 JRuby 绑定，通过 Weka 实现的不同 ML 算法.
- [ai4r](https://github.com/SergioFierens/ai4r) -
  Ruby 的人工智能.
- [classifier-reborn](https://github.com/jekyll/classifier-reborn) -
  允许贝叶斯和其他类型分类的通用分类器模块.
  <sup>[[dep: GLS](#gls)]</sup>
- [scoruby](https://github.com/asafschers/scoruby) -
  Ruby 评分 API 用于 [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) （预测模型标记语言）.
- [rblearn](https://github.com/himkt/rblearn) - 特征提取和交叉验证库.
- [data_modeler](https://github.com/giuse/data_modeler) -
  使用机器学习为您的数据建模. 充足的测试覆盖率、快速启动的示例、完整的文档. 从 1.0.0 开始生产就绪.
- [shogun](https://github.com/shogun-toolbox/shogun) - 多功能且成熟
  机器学习工具箱 [Ruby bindings](https://github.com/shogun-toolbox/shogun/tree/develop/src/interfaces/ruby).
- [aws-sdk-machinelearning](https://github.com/aws/aws-sdk-ruby) -
  亚马逊网络服务的机器学习 API.
- [azure_mgmt_machine_learning](https://github.com/Azure/azure-sdk-for-ruby) -
  Microsoft Azure 的机器学习 API.
- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench) -
  用纯 Ruby 编写的不断增长的机器学习框架，使用高性能计算
  [Numo](https://github.com/ruby-numo/), CUDA绑定通过 [Cumo](https://github.com/sonots/cumo).
  目前正在实施神经网络、进化策略、矢量量化和大量
  示例和实用程序.
- [Deep NeuroEvolution](https://github.com/giuse/DNE) -
  实验装置基于 [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench)
  使用进化算法搜索深度神经网络（而不是训练）. 应用到
  [OpenAI Gym](https://github.com/openai/gym) 使用 [PyCall](https://github.com/mrkn/pycall.rb).
- [rumale](https://github.com/yoshoku/rumale) -
  Ruby 中的机器学习工具包，具有广泛的已实现算法
  （支持向量机、逻辑回归、线性回归、随机森林等）和
  接口类似于 Python 中的 [Scikit-Learn][scikit].
- [eps](https://github.com/ankane/eps) - 出口贝叶斯分类和线性回归
  使用 [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) and an alternative backend 使用 [GSL][gsl].

### Neural networks

- [neural-net-ruby](https://github.com/gbuesing/neural-net-ruby) -
  用 Ruby 编写的神经网络.
- [ruby-fann](https://github.com/tangledpath/ruby-fann) -
  Ruby 绑定到 [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
- [cerebrum](https://github.com/irfansharif/cerebrum) -
  Ruby 中人工神经网络的实验实现.
- [tlearn-rb](https://github.com/josephwilk/tlearn-rb) -
  Ruby 的递归神经网络库.
- [brains](https://github.com/jedld/brains-jruby) -
  基于 JRuby 的前馈神经网络
  [brains](https://github.com/jedld/brains).
- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/neural_network) -
  框架包括前馈和递归神经网络的纯 Ruby 实现
   （完全连接）. 使用神经进化（自然进化策略算法）进行训练.
- [rann](https://github.com/mikecmpbll/rann) -
  具有反向传播的灵活的 Ruby ANN 实现（通过时间，用于循环
  nets）、梯度检查、adagrad 和并行批处理执行.

### Deep learning

- [tensor_stream](https://github.com/jedld/tensor_stream) -
  TensorFlow for Ruby 的全新独立重新实现.
- [red-chainer](https://github.com/red-data-tools/red-chainer) - 用于 Ruby 的深度学习框架.
- [tensorflow](https://github.com/somaticio/tensorflow.rb) - 红宝石绑定 [TensorFlow](https://www.tensorflow.org/).
- [ruby-dnn](https://github.com/unagiootoro/ruby-dnn) - Ruby 的简单深度学习.
- [torch-rb](https://github.com/ankane/torch-rb) - 红宝石绑定 [LibTorch](https://github.com/pytorch/pytorch)
  使用 [rice](https://github.com/jasonroelofs/rice).
- [mxnet](https://github.com/mrkn/mxnet.rb) - 红宝石绑定 [mxnet](https://mxnet.apache.org/).

### Kernel methods

- [rb-libsvm](https://github.com/febeling/rb-libsvm) -
  支持向量机与 Ruby 和 [LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) 图书馆.
  <sup>[[dep: bundled](#bundled)]</sup>

### Evolutionary algorithms

- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/optimizer/natural_evolution_strategies) -
  包括自然进化策略算法的纯 Ruby 实现的框架
  （黑盒优化），特别是指数 NES (XNES)，
  可分离 NES (sNES)、块对角线 NES (BDNES) 等.
  应用包括神经网络搜索/训练（神经进化）.
- [simple_ga](https://github.com/giuse/simple_ga) -
  Ruby 中最简单的遗传算法实现.

### Bayesian methods

- [linnaeus](https://github.com/djcp/linnaeus) -
  Redis 支持的贝叶斯分类器.
- [naive_bayes](https://github.com/reddavis/Naive-Bayes) -
  简单朴素贝叶斯分类器.
- [nbayes](https://github.com/oasic/nbayes) -
  朴素贝叶斯的全功能 Ruby 实现.

### Decision trees

- [decisiontree](https://github.com/igrigorik/decisiontree) -
  纯 Ruby 中的决策树 ID3 算法.
  <sup>[[dep: GraphViz](#graphviz) |
        [post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.

### Clustering

- [kmeans-clusterer](https://github.com/gbuesing/kmeans-clusterer) -
  Ruby 中的 k-均值聚类.
- [k_means](https://github.com/reddavis/K-Means) -
  尝试构建一个快速、内存高效的 K-Means 程序.
- [knn](https://github.com/reddavis/knn) -
  简单的 K 最近邻算法.

### Linear classifiers

- [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) -
  LIBLINEAR 的 Ruby 接口（在文本分类方面比 LIBSVM 更有效）.
- [liblinear-ruby](https://github.com/kei500/liblinear-ruby) -
  使用 SWIG 的 LIBLINEAR 的 Ruby 接口.

### Statistical models

- [rtimbl](https://github.com/maspwr/rtimbl) -
  Memory based learners from the Timbl framework.
- [lda-ruby](https://github.com/ealdent/lda-ruby) -
  红宝石实现 [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
  （潜在狄利克雷分配）用于自动主题建模和文档聚类.
- [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) -
  基于 OpenNLP Maxent 框架的字符串数据的 JRuby 最大熵分类器.
- [omnicat](https://github.com/mustafaturan/omnicat) -
  用于文本分类的通用机架框架.
- [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) -
  作为 OmniCat 分类器策略的朴素贝叶斯文本分类实现.
  <sup>[[dep: bundled](#bundled)]</sup>

### Gradient boosting

- [xgboost](https://github.com/PairOnAir/xgboost-ruby) —
  XGBoost 的 Ruby 绑定.
  <sup>[[dep: XGBoost](#xgboost)]</sup>
- [xgb](https://github.com/ankane/xgb) —
  XGBoost 的 Ruby 绑定.
  <sup>[[dep: XGBoost](#xgboost)]</sup>
- [lightgbm](https://github.com/ankane/lightgbm) —
  LightGBM 的 Ruby 绑定.
  <sup>[[dep: LightGBM](#lightgbm)]</sup>

### Vector search

- [flann](https://github.com/mariusmuja/flann) -
  Ruby 绑定 [FLANN](https://github.com/flann-lib/flann) （近似最近邻的快速库）.
  <sup>[[flann](#flann)]</sup>
- [annoy-rb](https://github.com/yoshoku/annoy.rb) -
  Ruby 绑定 [Annoy](https://github.com/spotify/annoy) （近似最近的邻居哦，是的）.
- [hnswlib.rb](https://github.com/yoshoku/hnswlib.rb) -
  Ruby 绑定 [Hnswlib](https://github.com/nmslib/hnswlib) 它使用分层可导航小世界图实现近似最近邻搜索.
- [ngt-ruby](https://github.com/ankane/ngt-ruby) -
  Ruby 绑定 [NGT](https://github.com/yahoojapan/NGT) （用于索引高维数据的邻域图和树）.
- [milvus](https://github.com/andreibondarev/milvus) —
  Milvus Vector DB 的 Ruby 客户端.
- [pinecone](https://github.com/ScotterC/pinecone) —
  Pinecone Vector DB 的 Ruby 客户端.
- [qdrant-ruby](https://github.com/andreibondarev/qdrant-ruby) —
  Qdrant 矢量搜索数据库 API 的 Ruby 包装器.
- [weaviate-ruby](https://github.com/andreibondarev/weaviate-ruby) —
  Weaviate 矢量搜索数据库 API 的 Ruby 包装器.

## Applications of machine learning

- [phashion](https://github.com/westonplatter/phashion) -
  pHash 的 Ruby 包装器，用于检测重复多媒体文件的感知哈希库.
  <sup>[[ImageMagick](#imagemagick) | [libjpeg](#libjpeg)]</sup>

## Data structures

如果您要实现自己的 ML 算法，您可能会感兴趣
有效地存储您的功能集. 寻找合适
[data structures](https://github.com/arbox/data-science-with-ruby#data-structures)
在我们的 [Data Science with Ruby][ds-with-ruby] 列表中.

## Data visualization

请参阅 [Data Visualization](https://github.com/arbox/data-science-with-ruby#visualization)
[Data Science with Ruby][ds-with-ruby] 列表部分.

## Articles, Posts, Talks, and Presentations

- 2022
  -_在 Ruby 中发现机器学习_作者： [Justin Bowen](https://twitter.com/TonsOfFun111)
   <sup>[[video](https://www.youtube.com/watch?v=HPbizNgcyFk)]</sup>
- 2019
  - _TensorStream：将机器学习引入 Ruby_，作者： [Joseph Emmanuel Dayo](https://www.linkedin.com/in/jdayo/)
    <sup>[[post](https://medium.com/@joseph.dayo/tensorstream-bringing-machine-learning-to-ruby-114582060e3d)]</sup>
  - _使用 SVMKit 使用 Ruby 进行简单的机器学习_ by [@kojix](https://twitter.com/kojix2dayo)
    <sup>[[post](https://dev.to/kojix2/easy-machine-learning-with-ruby-using-svmkit-4n86)]</sup>
- 2018
  -_Ruby 上的深度学习编程_作者： [Kenta Murata](https://twitter.com/mrkn)
    &amp; [Yusaku Hatanaka ](https://twitter.com/hatappi)
    <sup>[[slides](https://speakerdeck.com/mrkn/deep-learning-programming-on-ruby) |
          [page](https://rubykaigi.org/2018/presentations/mrkn.html)]</sup>
  -_如何在 Ruby on Rails 中使用经过训练的 Keras 和 TensorFlow 机器学习模型_作者： [Denis Sellu](https://twitter.com/denis_sellu)
    <sup>[[post](https://www.cookieshq.co.uk/posts/how-to-use-trained-keras-and-tensorflow-machine-learning-models-within-ruby-on-rails)]</sup>
- 2017
  -_JRuby 上的科学计算_作者： [Prasun Anand](https://twitter.com/prasun_anand)
    <sup>[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
    [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
   - _是食物吗？ 机器学习简介_作者： [Matthew Mongeau](https://twitter.com/halogenandtoast)
    <sup>[[video](https://www.youtube.com/watch?v=8G709hKkthY) |
          [slides](https://www.slideshare.net/halogenandtoast/is-it-food)]</sup>
  - _Bayes 是 BAE_ by [Richard Schneeman](https://twitter.com/schneems)
    <sup>[[video](https://www.youtube.com/watch?v=bQSzZrDDV80) |
          [slides](https://speakerdeck.com/schneems/bayes-is-bae)]</sup>
  - _Ruby 圆桌会议：Ruby 中的机器学习_ 作者： [RubyThursday](https://rubythursday.com/)
    <sup>[[video](https://www.youtube.com/watch?v=ScIFARN0jCo)]</sup>
- 2016
  -_Ruby 实用机器学习_作者： [Jordan Hudgens](https://twitter.com/jordanhudgens)
    <sup>[[tutorial](https://www.crondose.com/2016/12/practical-machine-learning-ruby/)]</sup>
  -_深度学习：Ruby 开发人员简介_作者： [Geoffrey Litt](https://twitter.com/geoffreylitt)
    <sup>[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
  -_我如何使纯 Ruby word2vec 程序快 3 倍以上_作者： [Kei Sawada](https://twitter.com/remore)
    <sup>[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
  - _Dōmo arigatō，Roboto 先生：使用 Ruby 进行机器学习_ 作者： [Eric Weinstein](https://twitter.com/ericqweinstein)
    <sup>[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) |
          [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
  - _使用机器学习技术构建推荐引擎_ by [Brian Sam-Bodden](https://twitter.com/bsbodden)
    <sup>[[video](https://www.youtube.com/watch?v=SRnM_P_ygqI)]</sup>
  - :sparkles: _SciRuby 机器学习：现状和未来_ by [Kenta Murata](https://twitter.com/mrkn)
    <sup>[[slides](https://speakerdeck.com/mrkn/sciruby-machine-learning-current-status-and-future) |
          [video: jp](https://www.youtube.com/watch?v=gfQ8XEy7vO4)]</sup>
  - _Ruby 圆桌会议：Tensorflow 简介_ 作者： [RubyThursday](https://rubythursday.com/)
    <sup>[[video](https://www.youtube.com/watch?v=pYC5mXHUWkc)]</sup>
- 2015
  -_Ruby 使机器学习变得简单_作者： [Lorenzo Masini](https://twitter.com/rugginoso)
    <sup>[[post](https://www.leanpanda.com/blog/2015-08-24-machine-learning-automatic-classification/)]</sup>
  - _使用 Ruby 机器学习查找 Paris Hilton 语录_ 作者： [Rick Carlino](https://github.com/RickCarlino)
    <sup>[[tutorial](https://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
- 2014
  - _测试驱动神经网络_ by [Matthew Kirk](https://twitter.com/mjkirk)
    <sup>[[video](https://www.youtube.com/watch?v=ppf8m-3uXvU&t=36s)]</sup>
  - _今天您可以在 Ruby 应用程序中使用的五种机器学习技术_作者 [Benjamin Curtis](https://twitter.com/stympy)
    <sup>[[video](https://www.youtube.com/watch?v=crziu7dk6Vw) |
          [slides](https://speakerdeck.com/stympy/machine-learning-techniques)]</sup>
  -_机器学习的乐趣和利润_作者： [John Paul Ashenfelter](https://twitter.com/johnashenfelter)
    <sup>[[video](https://www.youtube.com/watch?v=KC5MtKHm1O4)]</sup>
- 2013
  -_在 Ruby 中使用支持向量机进行情感分析_作者： [Matthew Kirk](https://twitter.com/mjkirk)
    <sup>[[video](https://www.youtube.com/watch?v=iSug6CgxWxc) |
          [code](https://github.com/hexgnu/sentiment_analyzer)]</sup>
  - _Recommender Systems with Ruby_ by [Marcel Caraciolo](https://twitter.com/marcelcaraciolo)
    <sup>[[slides](https://www.slideshare.net/marcelcaraciolo/recommender-systems-with-ruby-adding-machine-learning-statistics-etc)]</sup>
  -_用 Ruby 检测人脸：FFI 简而言之_作者：[Marc Berszick]()
    <sup>[[post](https://www.sitepoint.com/detecting-faces-with-ruby-ffi-in-a-nutshell/)]</sup>
- 2012
  -_Ruby 机器学习，第一部分_作者： [Vasily Vasinov](https://twitter.com/vasinov)
    <sup>[[tutorial](https://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
  -_Ruby 中的递归神经网络_作者： [Joseph Wilk](https://twitter.com/josephwilk)
    <sup>[[post](http://blog.josephwilk.net/ruby/recurrent-neural-networks-in-ruby.html)]</sup>
  - _使用机器学习和 JRuby 的推荐引擎_ [Matthew Kirk](https://twitter.com/mjkirk)
    <sup>[[video](https://www.youtube.com/watch?v=hsZcrlbBg_0)]</sup>
  - _实用机器学习和 Rails_ by [Andrew Cantino](https://twitter.com/tectonic)
    和 [Ryan Stout](https://twitter.com/ryanstout)
    <sup>[[video](https://www.youtube.com/watch?v=vy_zQ1-F0JI)]</sup>

- 2011
  - _Ruby 中的集群_ [Colin Drake](https://twitter.com/colinfdrake)
    <sup>[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)]</sup>
  - _在 Ruby 中使用支持向量机进行文本分类_ [Rimas Silkaitis](https://twitter.com/neovintage)
    <sup>[[post](http://neovintage.org/2011/11/14/text-classification-using-support/)]</sup>
- 2010
  - _bayes_motel – Ruby_ 的贝叶斯分类 [Mike Perham](https://twitter.com/mperham)
    <sup>[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
  - _Intelligent Ruby：机器学习入门_ by [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[video](https://vimeo.com/22513786)]</sup>
- 2009

- 2008
  - _Ruby 中的支持向量机 (SVM)_ 作者： [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>
- 2007
  -_Ruby 中的决策树学习_作者： [Ilya Grigorik](https://twitter.com/igrigorik)
    <sup>[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>

## Projects and Code Examples

- [Wine Clustering](https://github.com/hexgnu/wine_clustering) -
  葡萄酒质量估计与不同的算法聚集在一起.
- [simple_ga](https://github.com/giuse/simple_ga) -
  Ruby 中遗传算法的基本（工作）演示.
- [Handwritten Digits Recognition](https://github.com/jdrzj/handwritten-digits-recognition) -
  使用神经网络和 Ruby 进行手写数字识别.

## Heroku buildpacks

- [GSL and Ruby buildpack](https://github.com/tomwolfe/heroku-buildpack-gsl-ruby)
- [OpenCV and Ruby buildpack](https://github.com/lilibethdlc/heroku-buildpack-ruby-opencv)
- [ImageMagick buildpack](https://github.com/mcollina/heroku-buildpack-imagemagick)

## Books, Blogs, Channels

-  [Kirk, Matthew](https://twitter.com/mjkirk).
    _深思熟虑的机器学习：一种测试驱动的方法_. 奥莱利出版社，2014 年.
   <sup>[[Amazon](https://www.amazon.com/Thoughtful-Machine-Learning-Test-Driven-Approach/dp/1449374069) |
         [code](https://github.com/thoughtfulml/examples)]</sup>
- [Practical Artificial Intelligence](https://www.practicalai.io/) -
  关于人工智能和机器学习的博客，其中包含 Ruby 中的教程和代码示例.

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
  [GSL（GNU 科学图书馆）][gls]
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
  在其他很棒的项目中，有一个 NLP 相关项目的简短列表.
- [Ruby NLP](https://github.com/diasks2/ruby-nlp) -
  NLP 的最先进的 Ruby 库集合.
- [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) -
  NLP 相关资源的一般列表（大部分不适合 Ruby 程序员）.
- [Scientific Ruby](http://sciruby.com/) -
  Ruby 的线性代数、可视化和科学计算.
- [iRuby](https://github.com/SciRuby/iruby) - 用于 Jupyter（以前称为 IPython）的 IRuby 内核.
- [Kiba](https://github.com/thbar/kiba) -
  轻 [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) （提取、转换、加载）管道.
- [Awesome OCR](https://github.com/kba/awesome-ocr) -
  大量的 OCR（光学字符识别）资源.
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) -
  使用 TensorFlow 库进行机器学习.
- [rb-gsl](https://github.com/SciRuby/rb-gsl) -
  Ruby 接口 [GNU Scientific Library](https://www.gnu.org/software/gsl/).
- [The Definitive Guide to Ruby's C API](https://silverhammermba.github.io/emberb/) -
  使用 C 编程语言嵌入和扩展 Ruby 的现代参考和教程.

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
`Awesome ML with Ruby` 作者： [Andrei Beliankou](https://github.com/arbox) 和
[Contributors][contributors].

在法律允许的范围内，将 CC0 与
`Awesome ML with Ruby` 放弃了所有版权和相关或相邻的权利
到 `Awesome ML with Ruby`.

您应该已经收到一份 CC0 合法代码的副本以及此
工作. 如果没有，请参阅<https://creativecommons.org/publicdomain/zero/1.0/> .

<!--- Links --->
[红宝石]：https://www.ruby-lang.org/en/
[很棒]：https://github.com/sindresorhus/awesome/blob/master/awesome.md
[更改-pr]：https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md
[毫升]：https://en.wikipedia.org/wiki/Machine_learning
[ds-with-ruby]：https://github.com/arbox/data-science-with-ruby
[贡献者]：https://github.com/arbox/machine-learning-with-ruby/graphs/contributors
[sciruby]：https://github.com/sciruby
[人工智能]：https://en.wikipedia.org/wiki/Artificial_intelligence
[CS]：https://en.wikipedia.org/wiki/Computational_science
[fe]: https://en.wikipedia.org/wiki/Feature_engineering
[ts]: https://en.wikipedia.org/wiki/Test_set
[gsl]：https://www.gnu.org/software/gsl/
[scikit]：https://scikit-learn.org/stable/index.html
