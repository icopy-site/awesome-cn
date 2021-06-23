<div class="github-widget" data-repo="n2cholas/awesome-jax"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint ignore double-link-->

<!--lint ignore double-link-->
[JAX](https://github.com/google/jax) 带来自动微分和 [XLA compiler](https://www.tensorflow.org/xla) 一起通过一个 [NumPy](https://numpy.org/)类似 API，用于对 GPU 和 TPU 等加速器进行高性能机器学习研究.
<!--lint enable double-link-->

这是很棒的 JAX 库、项目和其他资源的精选列表. 欢迎投稿！



<a name="libraries" />

## Libraries

- 神经网络库
    - [Flax](https://raw.githubusercontent.com/google/flax) - 以灵活性和清晰度为中心. <img src="https://img.shields.io/github/stars/google/flax?style=social" align="center">
    - [Haiku](https://raw.githubusercontent.com/deepmind/dm-haiku) - 专注于简单性，由 DeepMind 的 Sonnet 的作者创建. <img src="https://img.shields.io/github/stars/deepmind/dm-haiku?style=social" align="center">
    - [Objax](https://raw.githubusercontent.com/google/objax) - 具有类似于 PyTorch 的面向对象设计. <img src="https://img.shields.io/github/stars/google/objax?style=social" align="center">
    - [Elegy](https://poets-ai.github.io/elegy/)  - Jax 生态系统的与框架无关的 Trainer 界面. 支持 Flax、Haiku 和 Optax. <img src="https://img.shields.io/github/stars/poets-ai/elegy?style=social" align="center">
    - [Trax](https://raw.githubusercontent.com/google/trax) - “含电池”深度学习库，专注于为常见工作负载提供解决方案. <img src="https://img.shields.io/github/stars/google/trax?style=social" align="center">
    - [Jraph](https://raw.githubusercontent.com/deepmind/jraph) - 轻量级图神经网络库. <img src="https://img.shields.io/github/stars/deepmind/jraph?style=social" align="center">
    - [Neural Tangents](https://raw.githubusercontent.com/google/neural-tangents) - 用于指定有限和 _infinite_ 宽度的神经网络的高级 API. <img src="https://img.shields.io/github/stars/google/neural-tangents?style=social" align="center">
    - [HuggingFace](https://raw.githubusercontent.com/huggingface/transformers) - 用于各种自然语言任务 (Flax) 的预训练 Transformer 生态系统. <img src="https://img.shields.io/github/stars/huggingface/transformers?style=social" align="center">
- [NumPyro](https://raw.githubusercontent.com/pyro-ppl/numpyro) - 基于 Pyro 库的概率编程. <img src="https://img.shields.io/github/stars/pyro-ppl/numpyro?style=social" align="center">
- [Chex](https://raw.githubusercontent.com/deepmind/chex) - 用于编写和测试可靠 JAX 代码的实用程序. <img src="https://img.shields.io/github/stars/deepmind/chex?style=social" align="center">
- [Optax](https://raw.githubusercontent.com/deepmind/optax) - 梯度处理和优化库. <img src="https://img.shields.io/github/stars/deepmind/optax?style=social" align="center">
- [RLax](https://raw.githubusercontent.com/deepmind/rlax) - 用于实现强化学习代理的库. <img src="https://img.shields.io/github/stars/deepmind/rlax?style=social" align="center">
- [JAX, M.D.](https://raw.githubusercontent.com/google/jax-md) - 加速的微分分子动力学. <img src="https://img.shields.io/github/stars/google/jax-md?style=social" align="center">
- [Coax](https://raw.githubusercontent.com/coax-dev/coax) - 将 RL 论文转化为代码，这是一种简单的方法. <img src="https://img.shields.io/github/stars/coax-dev/coax?style=social" align="center">
- [SymJAX](https://raw.githubusercontent.com/SymJAX/SymJAX) - 符号 CPU/GPU/TPU 编程. <img src="https://img.shields.io/github/stars/SymJAX/SymJAX?style=social" align="center">
- [mcx](https://raw.githubusercontent.com/rlouf/mcx) - 表达和编译用于高性能推理的概率程序. <img src="https://img.shields.io/github/stars/rlouf/mcx?style=social" align="center">
- [Distrax](https://raw.githubusercontent.com/deepmind/distrax) - 重新实现 TensorFlow Probability，包含概率分布和双射器. <img src="https://img.shields.io/github/stars/deepmind/distrax?style=social" align="center">
- [cvxpylayers](https://raw.githubusercontent.com/cvxgrp/cvxpylayers) - 构建可微凸优化层. <img src="https://img.shields.io/github/stars/cvxgrp/cvxpylayers?style=social" align="center">
- [TensorLy](https://raw.githubusercontent.com/tensorly/tensorly) - 张量学习变得简单. <img src="https://img.shields.io/github/stars/tensorly/tensorly?style=social" align="center">

<a name="new-libraries" />

### New Libraries

本节包含制作精良且有用的库，但尚未经过大量用户群的实战测试.

- 神经网络库
    - [FedJAX](https://raw.githubusercontent.com/google/fedjax) - JAX 中的联合学习，建立在 Optax 和 Haiku 之上. <img src="https://img.shields.io/github/stars/google/fedjax?style=social" align="center">
    - [Equivariant MLP](https://raw.githubusercontent.com/mfinzi/equivariant-MLP) - 构建等变神经网络层. <img src="https://img.shields.io/github/stars/mfinzi/equivariant-MLP?style=social" align="center">
    - [jax-resnet](https://raw.githubusercontent.com/n2cholas/jax-resnet/) - Flax 中 ResNet 变体的实现和检查点. <img src="https://img.shields.io/github/stars/n2cholas/jax-resnet?style=social" align="center">
- [jax-unirep](https://raw.githubusercontent.com/ElArkk/jax-unirep) - 图书馆实施 [UniRep model](https://www.nature.com/articles/s41592-019-0598-1) 用于蛋白质机器学习应用. <img src="https://img.shields.io/github/stars/ElArkk/jax-unirep?style=social" align="center">
- [jax-flows](https://raw.githubusercontent.com/ChrisWaites/jax-flows) - 在 JAX 中规范化流程. <img src="https://img.shields.io/github/stars/ChrisWaites/jax-flows?style=social" align="center">
- [sklearn-jax-kernels](https://raw.githubusercontent.com/ExpectationMax/sklearn-jax-kernels) - 使用 JAX 的 `scikit-learn` 内核矩阵. <img src="https://img.shields.io/github/stars/ExpectationMax/sklearn-jax-kernels?style=social" align="center">
- [jax-cosmo](https://raw.githubusercontent.com/DifferentiableUniverseInitiative/jax_cosmo) - 可微的宇宙学图书馆. <img src="https://img.shields.io/github/stars/DifferentiableUniverseInitiative/jax_cosmo?style=social" align="center">
- [efax](https://raw.githubusercontent.com/NeilGirdhar/efax) - JAX 中的指数族. <img src="https://img.shields.io/github/stars/NeilGirdhar/efax?style=social" align="center">
- [mpi4jax](https://raw.githubusercontent.com/PhilipVinc/mpi4jax) - 将 MPI 操作与 CPU 和 GPU 上的 Jax 代码相结合. <img src="https://img.shields.io/github/stars/PhilipVinc/mpi4jax?style=social" align="center">
- [imax](https://raw.githubusercontent.com/4rtemi5/imax) - 图像增加和转换. <img src="https://img.shields.io/github/stars/4rtemi5/imax?style=social" align="center">
- [FlaxVision](https://raw.githubusercontent.com/rolandgvc/flaxvision) - 亚麻版 TorchVision. <img src="https://img.shields.io/github/stars/rolandgvc/flaxvision?style=social" align="center">
- [Oryx](https://github.com/tensorflow/probability/tree/master/spinoffs/oryx) - 基于程序转换的概率编程语言.
- [Optimal Transport Tools](https://github.com/google-research/ott) - 捆绑实用程序以解决最佳运输问题的工具箱.
- [delta PV](https://raw.githubusercontent.com/romanodev/deltapv) - 具有自动微分功能的光伏模拟器. <img src="https://img.shields.io/github/stars/romanodev/deltapv?style=social" align="center">
- [jaxlie](https://raw.githubusercontent.com/brentyi/jaxlie) - 用于刚体变换和优化的李理论库. <img src="https://img.shields.io/github/stars/brentyi/jaxlie?style=social" align="center">
- [BRAX](https://raw.githubusercontent.com/google/brax) - 可微分物理引擎来模拟环境以及学习算法来为这些环境训练代理. <img src="https://img.shields.io/github/stars/google/brax?style=social" align="center">
- [flaxmodels](https://raw.githubusercontent.com/matthias-wright/flaxmodels) - Jax/Flax 的预训练模型. <img src="https://img.shields.io/github/stars/matthias-wright/flaxmodels?style=social" align="center">
- [CR.Sparse](https://raw.githubusercontent.com/carnotresearch/cr-sparse) - 用于稀疏表示和压缩感知的 XLA 加速算法. <img src="https://img.shields.io/github/stars/carnotresearch/cr-sparse?style=social" align="center">
- [exojax](https://raw.githubusercontent.com/HajimeKawahara/exojax) - 与 JAX 兼容的系外行星/棕矮星的自动可微谱建模. <img src="https://img.shields.io/github/stars/HajimeKawahara/exojax?style=social" align="center">

<a name="models-and-projects" />

## Models and Projects

- [Performer](https://github.com/google-research/google-research/tree/master/performer/fast_attention/jax) - 执行者（通过 FAVOR+ 的线性变换器）架构的亚麻实现.
- [Reformer](https://github.com/google/trax/tree/master/trax/models/reformer) - Implementation of the Reformer (efficient transformer) architecture.
- [Vision Transformer](https://github.com/google-research/vision_transformer) - 在亚麻的官方实施 [_An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale_](https://arxiv.org/abs/2010.11929).
- [Fourier Feature Networks](https://github.com/tancik/fourier-feature-networks) - 正式实施 [_Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains_](https://people.eecs.berkeley.edu/~bmild/fourfeat).
- [Flax Models](https://github.com/google-research/google-research/tree/master/flax_models) - 在 Flax 中实现的模型和方法的集合.
- [JaxNeRF](https://github.com/google-research/google-research/tree/master/jaxnerf) - 实施 [_NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis_](http://www.matthewtancik.com/nerf) 具有多设备 GPU/TPU 支持.
- [Big Transfer (BiT)](https://github.com/google-research/big_transfer) - 实施 [Big Transfer (BiT): General Visual Representation Learning](https://arxiv.org/abs/1912.11370).
- [NuX](https://github.com/Information-Fusion-Lab-Umass/NuX) - 使用 JAX 规范化流程.
- [kalman-jax](https://github.com/AaltoML/kalman-jax) - 使用迭代卡尔曼滤波和平滑对马尔可夫（即时间）高斯过程进行近似推断.
- [GPJax](https://github.com/thomaspinder/GPJax) - JAX 中的高斯过程.
- [jaxns](https://github.com/Joshuaalbert/jaxns) - JAX 中的嵌套采样.
- [Normalizer-Free Networks](https://github.com/deepmind/deepmind-research/tree/master/nfnets) - 官方俳句实现 [NFNets](https://arxiv.org/abs/2102.06171).
- [Distributed Shampoo](https://github.com/google-research/google-research/tree/master/scalable_shampoo) - 实施 [Second Order Optimization Made Practical](https://arxiv.org/abs/2002.09018).
- [JAX (Flax) RL](https://github.com/ikostrikov/jax-rl) - 强化学习算法的实现.

<a name="videos" />

## Videos

- [NeurIPS 2020: JAX Ecosystem Meetup](https://www.youtube.com/watch?v=iDxJxIyzSiM) - JAX，它在 DeepMind 中的使用，以及工程师、科学家和 JAX 核心团队之间的讨论.
- [Introduction to JAX](https://youtu.be/0mVmRHMaOJ4) - 在 JAX 中从头开始的简单神经网络.
- [JAX: Accelerated Machine Learning Research | SciPy 2020 | VanderPlas](https://youtu.be/z-WSrQDXkuM) - JAX 的核心设计、它如何推动新研究以及如何开始使用它.
- [Bayesian Programming with JAX + NumPyro — Andy Kitchen](https://youtu.be/CecuWGpoztw) - 介绍使用 NumPyro 的贝叶斯建模.
- [JAX: Accelerated machine-learning research via composable function transformations in Python | NeurIPS 2019 | Skye Wanderman-Milne](https://slideslive.com/38923687/jax-accelerated-machinelearning-research-via-composable-function-transformations-in-python) - JAX 介绍介绍 [_Program Transformations for Machine Learning_](https://program-transformations.github.io) 作坊.
- [JAX on Cloud TPUs | NeurIPS 2020 | Skye Wanderman-Milne and James Bradbury](https://drive.google.com/file/d/1jKxefZT1xJDUxMman6qrQVed7vWI0MIn/edit) - 演示 TPU 主机访问.
- [Deep Implicit Layers - Neural ODEs, Deep Equilibirum Models, and Beyond | NeurIPS 2020](https://slideslive.com/38935810/deep-implicit-layers-neural-odes-equilibrium-models-and-beyond) - 教程由 Zico Kolter、David Duvenaud 和 Matt Johnson 创建，Colab 笔记本可用 [_Deep Implicit Layers_](http://implicit-layers-tutorial.org).
- [Solving y=mx+b with Jax on a TPU Pod slice - Mat Kelcey](http://matpalm.com/blog/ymxb_pod_slice/) - 包含 Colab 笔记本的四部分 YouTube 教程系列，从 Jax 基础知识开始，然后在 v3-32 TPU Pod 切片上使用数据并行方法进行训练.

<a name="papers" />

## Papers

本节包含专注于 JAX 的论文（例如基于 JAX 的库白皮书、JAX 研究等）. 在 JAX 中实现的论文列在 [Models/Projects](#projects) 部分.

<!--lint ignore awesome-list-item-->
- [__Compiling machine learning programs via high-level tracing__. Roy Frostig, Matthew James Johnson, Chris Leary. _MLSys 2018_.](https://mlsys.org/Conferences/doc/2018/146.pdf) - 描述 JAX 早期版本的白皮书，详细介绍了如何跟踪和编译计算.
- [__JAX, M.D.: A Framework for Differentiable Physics__. Samuel S. Schoenholz, Ekin D. Cubuk. _NeurIPS 2020_.](https://arxiv.org/abs/1912.04232) - 引入 JAX、MD，这是一个可微物理库，其中包括模拟环境、交互势、神经网络等.
- [__Enabling Fast Differentially Private SGD via Just-in-Time Compilation and Vectorization__. Pranav Subramani, Nicholas Vadivelu, Gautam Kamath. _arXiv 2020_.](https://arxiv.org/abs/2010.09063) - 使用 JAX 的 JIT 和 VMAP 实现比现有库更快的差异私有化.
<!--lint enable awesome-list-item-->

<a name="tutorials-and-blog-posts" />

## Tutorials and Blog Posts

- [Using JAX to accelerate our research by David Budden and Matteo Hessel](https://deepmind.com/blog/article/using-jax-to-accelerate-our-research) - 描述了 DeepMind 的 JAX 和 JAX 生态系统的状态.
- [Getting started with JAX (MLPs, CNNs & RNNs) by Robert Lange](https://roberttlange.github.io/posts/2020/03/blog-post-10/) - 使用基本 JAX 运算符从头开始构建神经网络模块.
- [Tutorial: image classification with JAX and Flax Linen by 8bitmp3](https://github.com/8bitmp3/JAX-Flax-Tutorial-Image-Classification-with-Linen) - 了解如何使用 Flax 的 Linen API 创建一个简单的卷积网络并训练它识别手写数字.
- [Plugging Into JAX by Nick Doiron](https://medium.com/swlh/plugging-into-jax-16c120ec3302) - 在 Kaggle 花卉分类挑战中比较 Flax、Haiku 和 Objax.
- [Meta-Learning in 50 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/02/maml-jax.html) - JAX 和元学习的介绍.
- [Normalizing Flows in 100 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/07/nf-jax.html) - 简明实施 [RealNVP](https://arxiv.org/abs/1605.08803).
- [Differentiable Path Tracing on the GPU/TPU by Eric Jang](https://blog.evjang.com/2019/11/jaxpt.html) - 关于实现路径跟踪的教程.
- [Ensemble networks by Mat Kelcey](http://matpalm.com/blog/ensemble_nets) - 集成网络是一种将模型集成表示为单个逻辑模型的方法.
- [Out of distribution (OOD) detection by Mat Kelcey](http://matpalm.com/blog/ood_using_focal_loss) - 实现不同的OOD检测方法.
- [Understanding Autodiff with JAX by Srihari Radhakrishna](https://www.radx.in/jax.html) - 了解 autodiff 如何使用 JAX 工作.
- [From PyTorch to JAX: towards neural net frameworks that purify stateful code by Sabrina J. Mielke](https://sjmielke.com/jax-purify.htm) - 展示了如何从类似 PyTorch 的编码风格转变为更具功能性的编码风格.
- [Extending JAX with custom C++ and CUDA code by Dan Foreman-Mackey](https://github.com/dfm/extending-jax) - 演示在 JAX 中提供自定义操作所需的基础结构的教程.
- [Evolving Neural Networks in JAX by Robert Tjarko Lange](https://roberttlange.github.io/posts/2021/02/cma-es-jax/) - 探索 JAX 如何为下一代可扩展神经进化算法提供动力.
- [Exploring hyperparameter meta-loss landscapes with JAX by Luke Metz](http://lukemetz.com/exploring-hyperparameter-meta-loss-landscapes-with-jax/) - 演示如何使用 JAX 使用 SGD 和 Momentum 执行内损失优化、使用梯度的外损失优化以及使用进化策略的外损失优化.
- [Deterministic ADVI in JAX by Martin Ingram](https://martiningram.github.io/deterministic-advi/) - 使用 JAX 轻松干净地实现自动微分变分推理 (ADVI).
- [Evolved channel selection by Mat Kelcey](http://matpalm.com/blog/evolved_channel_selection/) - 训练对不同分辨率下输入通道的不同组合具有鲁棒性的分类模型，然后使用遗传算法来确定特定损失的最佳组合.
- [Introduction to JAX by Kevin Murphy](https://colab.research.google.com/github/probml/pyprobml/blob/master/notebooks/jax_intro.ipynb) - Colab 介绍了该语言的各个方面并将其应用于简单的 ML 问题.
- [Writing an MCMC sampler in JAX by Jeremie Coullon](https://www.jeremiecoullon.com/2020/11/10/mcmcjax3ways/) - 关于在 JAX 中编写 MCMC 采样器的不同方法以及速度基准测试的教程.
- [How to add a progress bar to JAX scans and loops by Jeremie Coullon](https://www.jeremiecoullon.com/2021/01/29/jax_progress_bar/) - 关于如何使用 `host_callback` 模块在 JAX 中向编译循环添加进度条的教程.

<a name="community" />

## Community

- [JAX GitHub Discussions](https://github.com/google/jax/discussions)
- [Reddit](https://www.reddit.com/r/JAX/)

## Contributing

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/n2cholas/awesome-jax/blob/master/contributing.md) 第一的.
