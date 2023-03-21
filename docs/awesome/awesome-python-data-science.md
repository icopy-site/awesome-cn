<div class="github-widget" data-repo="krzjoa/awesome-python-data-science"></div>
<div align="center">
    <a href="https://krzjoa.github.io/awesome-python-data-science/"><img width="250" height="250" src="https://raw.githubusercontent.com/krzjoa/awesome-python-data-science/master/img/py-datascience.png" alt="pyds"></a>
    <br>
    <br>
    <br>
</div>

<h1 align="center">
    很棒的 Python 数据科学
</h1>
<div align="center"><a href="https://github.com/sindresorhus/awesome">
<img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome" border="0">
</a>
</div>
</br>

&gt; 可能是 Python 中精选的数据科学软件列表


## Machine Learning

### General Purpose Machine Learning
* [Shogun](http://www.shogun-toolbox.org/) - 机器学习工具箱.
* [xLearn](https://github.com/aksnzhy/xlearn) - 高性能、易于使用且可扩展的机器学习包.
* [mlpack](https://github.com/mlpack/mlpack) - 可扩展的 C++ 机器学习库（Python 绑定）.
* [dlib](https://github.com/davisking/dlib) - 用于在 C++（Python 绑定）中制作真实世界机器学习和数据分析应用程序的工具包.
* [pyGAM](https://github.com/dswah/pyGAM) - Python 中的广义加法模型.
* [Karate Club](https://github.com/benedekrozemberczki/karateclub) - 用于图形结构数据的无监督机器学习库.
* [Little Ball of Fur](https://github.com/benedekrozemberczki/littleballoffur) - 用于对图形结构化数据进行采样的库.

### Automated Machine Learning
* [MLBox](https://github.com/AxeldeRomblay/MLBox) - 一个强大的自动化机器学习 python 库.
* [AutoGluon](https://github.com/awslabs/autogluon) - 用于图像、文本、表格、时间序列和多模态数据的 AutoML.

### Ensemble Methods

### Imbalanced Datasets

### Random Forests

### Extreme Learning Machine
* [Python Extreme Learning Machine (ELM)](https://github.com/acba/elm) - 用于分类/回归任务的机器学习技术.

### Kernel Methods
* [liquidSVM](https://github.com/liquidSVM/liquidSVM) - SVM 的实现.

### Gradient Boosting

## Deep Learning

### PyTorch

### TensorFlow

### MXNet

### Others
* [jax](https://github.com/google/jax) - Python+NumPy 程序的可组合转换：微分、矢量化、JIT 到 GPU/TPU 等.
* [Tangent](https://github.com/google/tangent) - 纯 Python 中的源到源可调试派生.
* [autograd](https://github.com/HIPS/autograd) - 高效计算 numpy 代码的导数.
* [Myia](https://github.com/mila-udem/myia) - 深度学习框架（pre-alpha）.
* [nnabla](https://github.com/sony/nnabla) - 索尼的神经网络库.
* [Caffe](https://github.com/BVLC/caffe) - 深度学习的快速开放框架.

**[DISCONTINUED PROJECTS](https://github.com/krzjoa/awesome-python-data-science/blob/master/other/deprecated.md#deep-learning)**

## Web Scraping
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): 最容易为初学者抓取静态网站的库
* [Scrapy](https://scrapy.org/) ：快速且可扩展的抓取库. 可以在不触及核心的情况下编写规则并创建定制的爬虫
* [Selenium](https://selenium-python.readthedocs.io/installation.html#introduction)：使用 Selenium Python API 以像真实用户一样直观的方式访问 Selenium WebDriver 的所有功能.
* [Pattern](https://github.com/clips/pattern) : 为谷歌、推特和维基百科等知名网站进行高级抓取. 还有 NLP、机器学习算法和可视化
* [twitterscraper](https://github.com/taspinar/twitterscraper): 抓取 Twitter 的高效库

## Data Manipulation

### Data Frames
* [pandas](https://pandas.pydata.org/pandas-docs/stable/) - 强大的 Python 数据分析工具包.
* [pandas_profiling](https://github.com/pandas-profiling/pandas-profiling) - 从 pandas DataFrame 对象创建 HTML 分析报告
* [xpandas](https://github.com/alan-turing-institute/xpandas) - 具有 Transformers 的通用 1d/2d 数据容器.用于数据分析的功能 [The Alan Turing Institute](https://www.turing.ac.uk/).
* [Arctic](https://github.com/manahl/arctic) - 用于时间序列和滴答数据的高性能数据存储.
* [swifter](https://github.com/jmcarpenter2/swifter) - 一个以最快的方式有效地将任何功能应用于熊猫数据框或系列的包.
* [pandas_flavor](https://github.com/Zsailer/pandas_flavor) - 一个允许轻松编写自己的 Pandas 风格的包.
* [pandas-log](https://github.com/eyaltrabelsi/pandas-log) - 一个允许提供有关基本 pandas 操作的反馈并发现业务逻辑和性能问题的包.
* [vaex](https://github.com/vaexio/vaex) - 用于 Python、ML 的核外数据帧，以每秒十亿行的速度可视化和探索大表格数据.
* [xarray](https://github.com/pydata/xarray) - Xarray 结合了 NumPy 和 pandas 的最佳特性，用于多维数据选择，通过用命名维度补充数值轴标签，实现更直观、简洁和不易出错的索引例程.
* [polars](https://github.com/pola-rs/polars) - 一个快速的多线程、混合核外 DataFrame 库.


### Pipelines
* [pdpipe](https://github.com/shaypal5/pdpipe) - 熊猫数据帧的 Sasy 管道.
* [SSPipe](https://sspipe.github.io/) - 支持 DataFrames 和 Numpy 以及 Pytorch 的 Python 管道 (|) 运算符.
* [Dataset](https://github.com/analysiscenter/dataset) - 帮助您方便地处理随机或顺序批次的数据并定义数据处理.
* [meza](https://github.com/reubano/meza) - 用于处理表格数据的 Python 工具包.
* [Prodmodel](https://github.com/prodmodel/prodmodel) - 为数据科学管道构建系统.
* [Hamilton](https://github.com/stitchfix/hamilton) - 用于数据帧生成的微框架，它应用由延迟评估的 Python 函数流指定的有向无环图.

### Data-centric AI
* [cleanlab](https://github.com/cleanlab/cleanlab) - 标准的以数据为中心的 AI 包，用于数据质量和机器学习，具有混乱的真实世界数据和标签.
* [snorkel](https://github.com/snorkel-team/snorkel) - 一种在弱监督下快速生成训练数据的系统.
* [dataprep](https://github.com/sfu-db/dataprep) - 使用几行代码在 Python 中收集、清理和可视化您的数据.

### Synthetic Data


## Feature Engineering

### General
* [Featuretools](https://github.com/Featuretools/featuretools) - 自动化特征工程.

### Feature Selection
* [scikit-feature](https://github.com/jundongl/scikit-feature) - Python 中的特征选择存储库.
* [zoofs](https://github.com/jaswinder9051998/zoofs) - 基于进化算法的特征选择库.

## Visualization
### General Purposes
* [Matplotlib](https://github.com/matplotlib/matplotlib) - 用 Python 绘图.
* [seaborn](https://github.com/mwaskom/seaborn) - 使用 matplotlib 的统计数据可视化.
* [prettyplotlib](https://github.com/olgabot/prettyplotlib) - 轻松创建漂亮的 matplotlib 图.
* [python-ternary](https://github.com/marcharper/python-ternary) - 带有 matplotlib 的 Python 三元绘图库.
* [missingno](https://github.com/ResidentMario/missingno) - 缺少 Python 的数据可视化模块.
* [chartify](https://github.com/spotify/chartify/) - Python 库，可让数据科学家轻松创建图表.
* [physt](https://github.com/janpipek/physt) - 改进的直方图.
### Interactive plots
* [animatplot](https://github.com/t-makaro/animatplot) - 一个 python 包，用于在 matplotlib 上构建动画图.
* [plotly](https://plot.ly/python/) - 一个 Python 库，可以制作交互式和出版质量的图表.
* [Bokeh](https://github.com/bokeh/bokeh) - Python 的交互式网络绘图.
* [Altair](https://altair-viz.github.io/)  - Python 的声明性统计可视化库. 可以轻松地在代码中进行许多数据转换以创建图形
* [bqplot](https://github.com/bqplot/bqplot) - IPython/Jupyter 笔记本的绘图库
### Map
* [folium](https://python-visualization.github.io/folium/quickstart.html#Getting-Started) - 可以轻松地在交互式开放街道地图上可视化数据
* [geemap](https://github.com/giswqs/geemap) - 用于与 Google Earth Engine (GEE) 进行交互式映射的 Python 包
### Automatic Plotting
* [HoloViews](https://github.com/ioam/holoviews) - 停止绘制您的数据 - 注释您的数据并让它可视化.
* [AutoViz](https://github.com/AutoViML/AutoViz)：用 1 行代码自动可视化数据（非常适合机器学习）
* [SweetViz](https://github.com/fbdesignpro/sweetviz)：使用一行代码可视化和比较数据集、目标值和关联.

### NLP
* [pyLDAvis](https://github.com/bmabey/pyLDAvis)：可视化交互式主题模型


## Deployment
* [fastapi](https://fastapi.tiangolo.com/) - 现代、快速（高性能）的 web 框架，用于使用 Python 构建 API
* [streamlit](https://www.streamlit.io/) - 使部署机器学习模型变得容易
* [gradio](https://github.com/gradio-app/gradio) - 在 3 分钟内用 Python 为您的机器学习模型创建 UI.
* [datapane](https://datapane.com/) - 将脚本和笔记本转换为交互式报告的 API 集合.
* [binder](https://mybinder.org/) - 启用共享和执行 Jupyter 笔记本

## Model Explanation

* [Shapley](https://github.com/benedekrozemberczki/shapley) - 一个数据驱动的框架，用于量化机器学习集成中分类器的价值.
* [Alibi](https://github.com/SeldonIO/alibi) - 用于监控和解释机器学习模型的算法.
* [anchor](https://github.com/marcotcr/anchor) - “高精度模型不可知论解释”论文的代码.
* [aequitas](https://github.com/dssg/aequitas) - 偏见和公平审计工具包.
* [ELI5](https://github.com/TeamHG-Memex/eli5) - 用于调试/检查机器学习分类器并解释其预测的库.
* [L2X](https://github.com/Jianbo-Lab/L2X) - 用于复制论文*Learning to Explain: An Information-Theoretic Perspective on Model Interpretation* 中实验的代码.
* [PDPbox](https://github.com/SauceCat/PDPbox) - 部分依赖图工具箱.
* [PyCEbox](https://github.com/AustinRochford/PyCEbox) - Python 个人条件期望图工具箱.
* [Skater](https://github.com/datascienceinc/Skater) - 用于模型解释的 Python 库.
* [AI Explainability 360](https://github.com/IBM/AIX360) - 数据和机器学习模型的可解释性和可解释性.
* [Auralisation](https://github.com/keunwoochoi/Auralisation) - CNN 中学到的特征的可听化（用于音频）.
* [CapsNet-Visualization](https://github.com/bourdakos1/CapsNet-Visualization) - CapsNet 层的可视化，以更好地理解它是如何工作的.
* [lucid](https://github.com/tensorflow/lucid) - 用于研究神经网络可解释性的基础设施和工具的集合.
* [Netron](https://github.com/lutzroeder/Netron) - 用于深度学习和机器学习模型的可视化工具（没有 Python 代码，但可视化来自大多数 Python 深度学习框架的模型）.
* [FlashLight](https://github.com/dlguys/flashlight) - 神经网络的可视化工具.
* [tensorboard-pytorch](https://github.com/lanpa/tensorboard-pytorch) - 用于 PyTorch 的 Tensorboard（以及 chainer、mxnet、numpy 等）.

## Reinforcement Learning
* [OpenAI Gym](https://github.com/openai/gym) - 用于开发和比较强化学习算法的工具包.
* [Coach](https://github.com/NervanaSystems/coach) - 使用最先进的强化学习算法轻松进行实验.
* [garage](https://github.com/rlworkgroup/garage) - 可重复强化学习研究的工具包.
* [OpenAI Baselines](https://github.com/openai/baselines) - 强化学习算法的高质量实现.
* [Stable Baselines](https://github.com/hill-a/stable-baselines) - 一组基于 OpenAI 基线的强化学习算法的改进实现.
* [RLlib](https://ray.readthedocs.io/en/latest/rllib.html) - 可扩展的强化学习.
* [Horizon](https://github.com/facebookresearch/Horizon) - 应用强化学习平台.
* [Dopamine](https://github.com/google/dopamine) - 强化学习算法快速原型设计的研究框架.
* [ChainerRL](https://github.com/chainer/chainerrl) - 一个建立在 Chainer 之上的深度强化学习库.

## Probabilistic Methods
* [PyMC](https://github.com/pymc-devs/pymc) - Python 中的贝叶斯随机建模.
* [PyStan](https://github.com/stan-dev/pystan) - 使用 No-U-Turn 采样器（Python 接口）的贝叶斯推理.
* [pgmpy](https://github.com/pgmpy/pgmpy) - 用于处理概率图形模型的 python 库.
* [emcee](https://github.com/dfm/emcee) - 用于仿射不变 MCMC 的 Python 集成采样工具包.
* [hsmmlearn](https://github.com/jvkersch/hsmmlearn) - 具有显式持续时间的隐藏半马尔可夫模型库.
* [pyhsmm](https://github.com/mattjj/pyhsmm) - HSMM 和 HMM 中的贝叶斯推理.

## Genetic Programming
* [DEAP](https://github.com/DEAP/deap) - Python 中的分布式进化算法.
* [monkeys](https://github.com/hchasestevens/monkeys) - Python 的强类型遗传编程框架.

<a name="opt"></a>
## Optimization
* [Optuna](https://github.com/optuna/optuna) - 超参数优化框架.
* [Spearmint](https://github.com/HIPS/Spearmint) - 贝叶斯优化.
* [scikit-opt](https://github.com/guofei9987/scikit-opt) - 用于优化的启发式算法.
* [SMAC3](https://github.com/automl/SMAC3) - 基于序列模型的算法配置.
* [Optunity](https://github.com/claesenm/optunity) - 是一个包含用于超参数调整的各种优化器的库.
* [hyperopt](https://github.com/hyperopt/hyperopt) - Python 中的分布式异步超参数优化.
* [Bayesian Optimization](https://github.com/fmfn/BayesianOptimization) - 使用高斯过程进行全局优化的 Python 实现.
* [SafeOpt](https://github.com/befelix/SafeOpt) - 安全贝叶斯优化.
* [scikit-optimize](https://github.com/scikit-optimize/scikit-optimize) - 使用 scipy.optimize 接口进行基于模型的顺序优化.
* [Solid](https://github.com/100/Solid) - 用 Python 编写的综合无梯度优化框架.
* [PySwarms](https://github.com/ljvmiranda921/pyswarms) - 用于 Python 中粒子群优化的研究工具包.
* [Platypus](https://github.com/Project-Platypus/Platypus) - 用于多目标优化的免费开源 Python 库.
* [POT](https://github.com/rflamary/POT) - Python 最佳传输库.
* [Talos](https://github.com/autonomio/talos) - Keras 模型的超参数优化.
* [nlopt](https://github.com/stevengj/nlopt) - 非线性优化库（全局和局部，受约束或不受约束）.
* [OR-Tools](https://developers.google.com/optimization)  - 由谷歌优化的开源软件套件； 为六个求解器提供统一的编程接口：SCIP、GLPK、GLOP、CP-SAT、CPLEX 和 Gurobi.

## Time Series
* [darts](https://github.com/unit8co/darts) - 一个用于轻松操作和预测时间序列的 python 库.
* [statsforecast](https://github.com/Nixtla/statsforecast) - 使用统计和计量经济学模型进行闪电般的快速预测.
* [mlforecast](https://github.com/Nixtla/mlforecast) - 可扩展的基于机器学习的时间序列预测.
* [neuralforecast](https://github.com/Nixtla/neuralforecast) - 可扩展的基于机器学习的时间序列预测.
* [greykite](https://github.com/linkedin/greykite) - 接下来是一个灵活、直观、快速的预测库.
* [Prophet](https://github.com/facebook/prophet) - Automatic Forecasting Procedure.
* [PyFlux](https://github.com/RJT1990/pyflux) - Python 的开源时间序列库.
* [bayesloop](https://github.com/christophmark/bayesloop) - 促进时变参数模型的目标模型选择的概率编程框架.
* [luminol](https://github.com/linkedin/luminol) - 异常检测和关联库.
* [dateutil](https://dateutil.readthedocs.io/en/stable/) - 对标准日期时间模块的强大扩展
* [maya](https://github.com/timofurrer/maya) - 使解析字符串和更改时区变得非常容易
* [Chaos Genius](https://github.com/chaos-genius/chaos_genius) - ML 驱动的分析引擎，用于离群值/异常检测和根本原因分析

## Natural Language Processing
* [spaCy](https://spacy.io/) - 工业级自然语言处理.
* [NLTK](https://github.com/nltk/nltk) - 支持自然语言处理研究和开发的模块、数据集和教程.
* [CLTK](https://github.com/cltk/cltk) - 经典语言工具包.
* [gensim](https://radimrehurek.com/gensim/) - 人类主题建模.
* [pyMorfologik](https://github.com/dmirecki/pyMorfologik) -<a href="https://github.com/morfologik/morfologik-stemming">形态学</a>的 Python 绑定.
* [Phonemizer](https://github.com/bootphon/phonemizer) - 用于多种语言的简单文本到音素转换器.
* [flair](https://github.com/zalandoresearch/flair) - 最先进的 NLP 的非常简单的框架.


## Computer Audition
* [librosa](https://github.com/librosa/librosa) - 用于音频和音乐分析的 Python 库.
* [Yaafe](https://github.com/Yaafe/Yaafe) - 音频特征提取.
* [aubio](https://github.com/aubio/aubio) - 音频和音乐分析库.
* [Essentia](https://github.com/MTG/essentia) - 用于音频和音乐分析、描述和合成的库.
* [LibXtract](https://github.com/jamiebullock/LibXtract) - 一个简单、便携、轻量级的音频特征提取函数库.
* [Marsyas](https://github.com/marsyas/marsyas) - 音频信号的音乐分析、检索和合成.
* [muda](https://github.com/bmcfee/muda) - 用于增强带注释的音频数据的库.
* [madmom](https://github.com/CPJKU/madmom) - Python 音频和音乐信号处理库.

## Computer Vision
* [OpenCV](https://github.com/opencv/opencv) - 开源计算机视觉库.
* [scikit-image](https://github.com/scikit-image/scikit-image) - 图像处理 SciKit（SciPy 工具箱）.
* [imgaug](https://github.com/aleju/imgaug) - 用于机器学习实验的图像增强.
* [imgaug_extension](https://github.com/cadenai/imgaug_extension) - imgaug 的额外增强.
* [Augmentor](https://github.com/mdbloice/Augmentor) - 用于机器学习的 Python 图像增强库.
* [albumentations](https://github.com/albu/albumentations) - 快速图像增强库和其他库的易于使用的包装器.

## Statistics
* [statsmodels](https://github.com/statsmodels/statsmodels) - Python 中的统计建模和计量经济学.
* [stockstats](https://github.com/jealous/stockstats) - 提供基于 ``pandas.DataFrame`` 的包装器 ``StockDataFrame``，支持内联股票统计/指标.
* [weightedcalcs](https://github.com/jsvine/weightedcalcs) - 基于 pandas 的实用程序，用于计算加权平均值、中位数、分布、标准差等.
* [scikit-posthocs](https://github.com/maximtrp/scikit-posthocs) - 成对多重比较事后检验.
* [Alphalens](https://github.com/quantopian/alphalens) - 预测（alpha）股票因素的绩效分析.

## Distributed Computing
* [Veles](https://github.com/Samsung/veles) - 分布式机器学习平台.
* [Jubatus](https://github.com/jubatus/jubatus) - 分布式在线机器学习框架和库.
* [DMTK](https://github.com/Microsoft/DMTK) - Microsoft 分布式机器学习工具包.
* [PaddlePaddle](https://github.com/PaddlePaddle/Paddle) - 并行分布式深度学习.
* [Distributed](https://github.com/dask/distributed) - Python 中的分布式计算.

## Experimentation
* [mlflow](https://github.com/mlflow/mlflow) - 机器学习生命周期的开源平台.
* [Neptune](https://neptune.ai) - 轻量级 ML 实验跟踪、结果可视化和管理工具.
* [dvc](https://github.com/iterative/dvc)  - 数据版本控制 | 用于数据和模型的 Git | 机器学习实验管理.
* [envd](https://github.com/tensorchord/envd) - ️ 数据科学和 AI/ML 工程团队的机器学习开发环境.
* [Sacred](https://github.com/IDSIA/sacred) - 一个帮助您配置、组织、记录和重现实验的工具.

## Data Validation
* [great_expectations](https://github.com/great-expectations/great_expectations) - 始终了解对数据的期望.
* [pandera](https://github.com/unionai-oss/pandera) - A lightweight, flexible, and expressive statistical data testing library.
* [evidently](https://github.com/evidentlyai/evidently) - 评估和监控从验证到生产的 ML 模型.
* [TensorFlow Data Validation](https://github.com/tensorflow/data-validation) - 用于探索和验证机器学习数据的库.

## Evaluation
* [recmetrics](https://github.com/statisticianinstilettos/recmetrics) - 用于评估推荐系统的有用指标和图表库.
* [Metrics](https://github.com/benhamner/Metrics) - 机器学习评估指标.
* [AI Fairness 360](https://github.com/IBM/AIF360) - 数据集和 ML 模型、解释和算法的公平性指标，以减轻数据集和模型中的偏差.

## Computations
* [numpy](http://www.numpy.org/) - 使用 Python 进行科学计算所需的基础包.
* [bottleneck](https://github.com/kwgoodman/bottleneck) - 用 C 编写的快速 NumPy 数组函数.
* [CuPy](https://github.com/cupy/cupy) - 使用 CUDA 加速的类似 NumPy 的 API.
* [scikit-tensor](https://github.com/mnick/scikit-tensor) - 用于多线性代数和张量分解的 Python 库.
* [numdifftools](https://github.com/pbrod/numdifftools) - 解决一个或多个变量的自动数值微分问题.
* [quaternion](https://github.com/moble/quaternion) - 为 numpy 添加对四元数的内置支持.
* [adaptive](https://github.com/python-adaptive/adaptive) - 数学函数的自适应和并行采样工具.
* [NumExpr](https://github.com/pydata/numexpr) - NumPy 的快速数值表达式求值器，带有集成计算虚拟机，可通过避免为中间结果分配内存来加快计算速度.

## Spatial Analysis
* [PySal](https://github.com/pysal/pysal) - Python 空间分析库.

## Quantum Computing
* [qiskit](https://github.com/krzjoa/awesome-python-data-science/blob/master/Qiskit/qiskit) - Qiskit 是一个开源 SDK，用于在电路、算法和应用程序模块级别与量子计算机配合使用.
* [cirq](https://github.com/quantumlib/Cirq) - 用于创建、编辑和调用噪声中级量子 (NISQ) 电路的 python 框架.
* [PennyLane](https://github.com/XanaduAI/pennylane) - 量子机器学习、自动微分和混合量子经典计算的优化.
* [QML](https://github.com/qmlcode/qml) - 用于量子机器学习的 Python 工具包.

## Conversion
* [sklearn-porter](https://github.com/nok/sklearn-porter) - 将训练有素的 scikit-learn 估计器转换为 C、Java、JavaScript 等.
* [ONNX](https://github.com/onnx/onnx) - 打开神经网络交换.
* [MMdnn](https://github.com/Microsoft/MMdnn) - 一组帮助用户在不同深度学习框架之间进行互操作的工具.

## Related Resources
* [Best of Machine Learning Libraries](https://kandi.openweaver.com/collections/machine-learning/python-machine-learning) - 精选的 Python 最佳机器学习库列表.

## Contributing
欢迎投稿！  ：太阳镜：</br>
阅读<a href=https://github.com/krzjoa/awesome-python-datascience/blob/master/CONTRIBUTING.md>贡献指南</a>.

## License
本作品根据 Creative Commons Attribution 4.0 International License 获得许可 - [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

<div align="center">
    <a href="other/deprecated.md">弃用的库</a>
    <a href="other/waiting-room.md">等候室</a>
<div>
