<div class="github-widget" data-repo="n2cholas/awesome-jax"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint ignore double-link-->

<!--lint ignore double-link-->
[JAX](https://github.com/google/jax) 带来自动差异化 [XLA compiler](https://www.tensorflow.org/xla) 一起通过 [NumPy](https://numpy.org/)类API，用于在GPU和TPU等加速器上进行高性能机器学习研究.
<!--lint enable double-link-->

这是精选的JAX库，项目和其他资源的精选列表. 欢迎捐款！



<a name="libraries" />

## Libraries

-神经网络图书馆
    - [Flax](https://raw.githubusercontent.com/google/flax) -以灵活性和清晰度为中心. <img src="https://img.shields.io/github/stars/google/flax?style=social" align="center">
    - [Haiku](https://raw.githubusercontent.com/deepmind/dm-haiku) -专注于简单性，由DeepMind的Sonnet作者创建. <img src="https://img.shields.io/github/stars/deepmind/dm-haiku?style=social" align="center">
    - [Objax](https://raw.githubusercontent.com/google/objax) -具有类似于PyTorch的面向对象设计. <img src="https://img.shields.io/github/stars/google/objax?style=social" align="center">
    - [Elegy](https://poets-ai.github.io/elegy/)  -用于Jax生态系统的与框架无关的Trainer界面. 支持亚麻，Haiku和Optax. <img src="https://img.shields.io/github/stars/poets-ai/elegy?style=social" align="center">
    - [Trax](https://raw.githubusercontent.com/google/trax) -“包含电池”的深度学习库专注于为常见工作负载提供解决方案. <img src="https://img.shields.io/github/stars/google/trax?style=social" align="center">
    - [Jraph](https://raw.githubusercontent.com/deepmind/jraph) -轻量级图神经网络库. <img src="https://img.shields.io/github/stars/deepmind/jraph?style=social" align="center">
    - [Neural Tangents](https://raw.githubusercontent.com/google/neural-tangents) -用于指定有限和_infinite_宽度的神经网络的高级API. <img src="https://img.shields.io/github/stars/google/neural-tangents?style=social" align="center">
- [NumPyro](https://raw.githubusercontent.com/pyro-ppl/numpyro) -基于Pyro库的概率编程. <img src="https://img.shields.io/github/stars/pyro-ppl/numpyro?style=social" align="center">
- [Chex](https://raw.githubusercontent.com/deepmind/chex) -编写和测试可靠的JAX代码的实用程序. <img src="https://img.shields.io/github/stars/deepmind/chex?style=social" align="center">
- [Optax](https://raw.githubusercontent.com/deepmind/optax) -渐变处理和优化库. <img src="https://img.shields.io/github/stars/deepmind/optax?style=social" align="center">
- [RLax](https://raw.githubusercontent.com/deepmind/rlax) -用于实施强化学习代理的图书馆. <img src="https://img.shields.io/github/stars/deepmind/rlax?style=social" align="center">
- [JAX, M.D.](https://raw.githubusercontent.com/google/jax-md) -加速的微分分子动力学. <img src="https://img.shields.io/github/stars/google/jax-md?style=social" align="center">
- [Coax](https://raw.githubusercontent.com/microsoft/coax) -通过简单的方法将RL论文转换为代码. <img src="https://img.shields.io/github/stars/microsoft/coax?style=social" align="center">
- [SymJAX](https://raw.githubusercontent.com/SymJAX/SymJAX) -符号CPU / GPU / TPU编程. <img src="https://img.shields.io/github/stars/SymJAX/SymJAX?style=social" align="center">
- [mcx](https://raw.githubusercontent.com/rlouf/mcx) -表达和编译概率程序以进行性能推断. <img src="https://img.shields.io/github/stars/rlouf/mcx?style=social" align="center">
- [Distrax](https://raw.githubusercontent.com/deepmind/distrax) -重新实现TensorFlow概率，其中包含概率分布和双射器. <img src="https://img.shields.io/github/stars/deepmind/distrax?style=social" align="center">
- [cvxpylayers](https://raw.githubusercontent.com/cvxgrp/cvxpylayers) -构造可微凸优化层. <img src="https://img.shields.io/github/stars/cvxgrp/cvxpylayers?style=social" align="center">
- [TensorLy](https://raw.githubusercontent.com/tensorly/tensorly) -张量学习变得简单. <img src="https://img.shields.io/github/stars/tensorly/tensorly?style=social" align="center">

<a name="new-libraries" />

### New Libraries

本节包含完善且有用的库，但尚未经过大型用户群的测试.

-神经网络图书馆
    - [FedJAX](https://raw.githubusercontent.com/google/fedjax) -以Optax和Haiku为基础的JAX联合学习. <img src="https://img.shields.io/github/stars/google/fedjax?style=social" align="center">
    - [Equivariant MLP](https://raw.githubusercontent.com/mfinzi/equivariant-MLP) -构造等变神经网络层. <img src="https://img.shields.io/github/stars/mfinzi/equivariant-MLP?style=social" align="center">
- [jax-unirep](https://raw.githubusercontent.com/ElArkk/jax-unirep) -图书馆实施 [UniRep model](https://www.nature.com/articles/s41592-019-0598-1) 用于蛋白质机器学习应用. <img src="https://img.shields.io/github/stars/ElArkk/jax-unirep?style=social" align="center">
- [jax-flows](https://raw.githubusercontent.com/ChrisWaites/jax-flows) -在JAX中标准化流. <img src="https://img.shields.io/github/stars/ChrisWaites/jax-flows?style=social" align="center">
- [sklearn-jax-kernels](https://raw.githubusercontent.com/ExpectationMax/sklearn-jax-kernels) -使用JAX的`scikit-learn`内核矩阵. <img src="https://img.shields.io/github/stars/ExpectationMax/sklearn-jax-kernels?style=social" align="center">
- [jax-cosmo](https://raw.githubusercontent.com/DifferentiableUniverseInitiative/jax_cosmo) -可区分的宇宙学库. <img src="https://img.shields.io/github/stars/DifferentiableUniverseInitiative/jax_cosmo?style=social" align="center">
- [efax](https://raw.githubusercontent.com/NeilGirdhar/efax) -JAX中的指数族. <img src="https://img.shields.io/github/stars/NeilGirdhar/efax?style=social" align="center">
- [mpi4jax](https://raw.githubusercontent.com/PhilipVinc/mpi4jax) -将MPI操作与您在CPU和GPU上的Jax代码结合在一起. <img src="https://img.shields.io/github/stars/PhilipVinc/mpi4jax?style=social" align="center">
- [imax](https://raw.githubusercontent.com/4rtemi5/imax) -图像增加和变换. <img src="https://img.shields.io/github/stars/4rtemi5/imax?style=social" align="center">
- [FlaxVision](https://raw.githubusercontent.com/rolandgvc/flaxvision) -TorchVision的亚麻版. <img src="https://img.shields.io/github/stars/rolandgvc/flaxvision?style=social" align="center">
- [Oryx](https://github.com/tensorflow/probability/tree/master/spinoffs/oryx) -基于程序转换的概率编程语言.
- [Optimal Transport Tools](https://github.com/google-research/ott) -捆绑实用程序以解决最佳运输问题的工具箱.

<a name="models-and-projects" />

## Models and Projects

- [Performer](https://github.com/google-research/google-research/tree/master/performer/fast_attention/jax) -Performer（通过FAVOR +的线性变压器）体系结构的亚麻实现.
- [Reformer](https://github.com/google/trax/tree/master/trax/models/reformer) -重整器（高效变压器）架构的实现.
- [Vision Transformer](https://github.com/google-research/vision_transformer) -亚麻中的正式实施 [_An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale_](https://arxiv.org/abs/2010.11929).
- [Fourier Feature Networks](https://github.com/tancik/fourier-feature-networks) -正式执行 [_Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains_](https://people.eecs.berkeley.edu/~bmild/fourfeat).
- [Flax Models](https://github.com/google-research/google-research/tree/master/flax_models) -亚麻中实现的模型和方法的集合.
- [JaxNeRF](https://github.com/google-research/google-research/tree/master/jaxnerf) - 实施 [_NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis_](http://www.matthewtancik.com/nerf) 具有多设备GPU / TPU支持.
- [Big Transfer (BiT)](https://github.com/google-research/big_transfer) - 实施 [Big Transfer (BiT): General Visual Representation Learning](https://arxiv.org/abs/1912.11370).
- [NuX](https://github.com/Information-Fusion-Lab-Umass/NuX) -使用JAX标准化流.
- [kalman-jax](https://github.com/AaltoML/kalman-jax) -使用迭代卡尔曼滤波和平滑的马尔可夫（即时间）高斯过程的近似推断.
- [GPJax](https://github.com/thomaspinder/GPJax) - Gaussian processes in JAX.
- [jaxns](https://github.com/Joshuaalbert/jaxns) -在JAX中嵌套采样.
- [Normalizer-Free Networks](https://github.com/deepmind/deepmind-research/tree/master/nfnets) -正式的Haiku实施 [NFNets](https://arxiv.org/abs/2102.06171).
- [Distributed Shampoo](https://github.com/google-research/google-research/tree/master/scalable_shampoo) - 实施 [Second Order Optimization Made Practical](https://arxiv.org/abs/2002.09018).

<a name="videos" />

## Videos

- [NeurIPS 2020: JAX Ecosystem Meetup](https://www.youtube.com/watch?v=iDxJxIyzSiM) -JAX，它在DeepMind中的使用，以及工程师，科学家和JAX核心团队之间的讨论.
- [Introduction to JAX](https://youtu.be/0mVmRHMaOJ4) -在JAX中从零开始的简单神经网络.
- [JAX: Accelerated Machine Learning Research | SciPy 2020 | VanderPlas](https://youtu.be/z-WSrQDXkuM) -JAX的核心设计，它如何推动新研究以及如何开始使用它.
- [Bayesian Programming with JAX + NumPyro — Andy Kitchen](https://youtu.be/CecuWGpoztw) -使用NumPyro进行贝叶斯建模的简介.
- [JAX: Accelerated machine-learning research via composable function transformations in Python | NeurIPS 2019 | Skye Wanderman-Milne](https://slideslive.com/38923687/jax-accelerated-machinelearning-research-via-composable-function-transformations-in-python) -中的JAX简介演示文稿 [_Program Transformations for Machine Learning_](https://program-transformations.github.io) 作坊.
- [JAX on Cloud TPUs | NeurIPS 2020 | Skye Wanderman-Milne and James Bradbury](https://drive.google.com/file/d/1jKxefZT1xJDUxMman6qrQVed7vWI0MIn/edit) -通过演示演示TPU主机访问.
- [Deep Implicit Layers - Neural ODEs, Deep Equilibirum Models, and Beyond | NeurIPS 2020](https://slideslive.com/38935810/deep-implicit-layers-neural-odes-equilibrium-models-and-beyond) -Zico Kolter，David Duvenaud和Matt Matt在Colab笔记本中创建的教程 [_Deep Implicit Layers_](http://implicit-layers-tutorial.org).
- [Solving y=mx+b with Jax on a TPU Pod slice - Mat Kelcey](http://matpalm.com/blog/ymxb_pod_slice/) -包含Colab笔记本电脑的YouTube教程系列，分为四个部分，从Jax基础开始，然后逐步发展为在v3-32 TPU Pod切片上采用数据并行方法进行培训.

<a name="papers" />

## Papers

本节包含有关JAX的论文（例如，基于JAX的库白皮书，关于JAX的研究等）.  JAX中实现的论文列在 [Models/Projects](#projects) 部分.

<!--lint ignore awesome-list-item-->
- [__Compiling machine learning programs via high-level tracing__. Roy Frostig, Matthew James Johnson, Chris Leary. _MLSys 2018_.](https://mlsys.org/Conferences/doc/2018/146.pdf) -白皮书描述了JAX的早期版本，详细介绍了如何跟踪和编译计算.
- [__JAX, M.D.: A Framework for Differentiable Physics__. Samuel S. Schoenholz, Ekin D. Cubuk. _NeurIPS 2020_.](https://arxiv.org/abs/1912.04232) -引入了MDX JAX，这是一个可微分的物理库，其中包括仿真环境，交互电位，神经网络等.
- [__Enabling Fast Differentially Private SGD via Just-in-Time Compilation and Vectorization__. Pranav Subramani, Nicholas Vadivelu, Gautam Kamath. _arXiv 2020_.](https://arxiv.org/abs/2010.09063) -使用JAX的JIT和VMAP来实现比现有库更快的差异私有.
<!--lint enable awesome-list-item-->

<a name="tutorials-and-blog-posts" />

## Tutorials and Blog Posts

- [Using JAX to accelerate our research by David Budden and Matteo Hessel](https://deepmind.com/blog/article/using-jax-to-accelerate-our-research) -在DeepMind中描述JAX和JAX生态系统的状态.
- [Getting started with JAX (MLPs, CNNs & RNNs) by Robert Lange](https://roberttlange.github.io/posts/2020/03/blog-post-10/) -基本的JAX运算符从零开始构建神经网络.
- [Tutorial: image classification with JAX and Flax Linen by 8bitmp3](https://github.com/8bitmp3/JAX-Flax-Tutorial-Image-Classification-with-Linen) -了解如何使用Flax的Linen API创建简单的卷积网络，并训练它识别手写数字.
- [Plugging Into JAX by Nick Doiron](https://medium.com/swlh/plugging-into-jax-16c120ec3302) -比较Kaggle花卉分类挑战中的亚麻，Hai句和Objax.
- [Meta-Learning in 50 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/02/maml-jax.html) -JAX和元学习简介.
- [Normalizing Flows in 100 Lines of JAX by Eric Jang](https://blog.evjang.com/2019/07/nf-jax.html) -简明的执行 [RealNVP](https://arxiv.org/abs/1605.08803).
- [Differentiable Path Tracing on the GPU/TPU by Eric Jang](https://blog.evjang.com/2019/11/jaxpt.html) -有关实施路径跟踪的教程.
- [Ensemble networks by Mat Kelcey](http://matpalm.com/blog/ensemble_nets) -集成网络是一种将一组模型表示为一个逻辑模型的方法.
- [Out of distribution (OOD) detection by Mat Kelcey](http://matpalm.com/blog/ood_using_focal_loss) -实施不同的OOD检测方法.
- [Understanding Autodiff with JAX by Srihari Radhakrishna](https://www.radx.in/jax.html) -了解autodiff如何使用JAX进行工作.
- [From PyTorch to JAX: towards neural net frameworks that purify stateful code by Sabrina J. Mielke](https://sjmielke.com/jax-purify.htm) -展示如何从类似PyTorch的编码样式转变为更具功能性的编码样式.
- [Extending JAX with custom C++ and CUDA code by Dan Foreman-Mackey](https://github.com/dfm/extending-jax) -教程演示了在JAX中提供自定义操作所需的基础结构.
- [Evolving Neural Networks in JAX by Robert Tjarko Lange](https://roberttlange.github.io/posts/2021/02/cma-es-jax/) -探索JAX如何为下一代可伸缩神经进化算法提供支持.
- [Exploring hyperparameter meta-loss landscapes with JAX by Luke Metz](http://lukemetz.com/exploring-hyperparameter-meta-loss-landscapes-with-jax/) -演示如何使用JAX执行SGD和Momentum的内部损失优化，使用梯度的外部损失优化以及使用进化策略进行外部损失优化.
- [Deterministic ADVI in JAX by Martin Ingram](https://martiningram.github.io/deterministic-advi/) -使用JAX轻松，干净地实现自动差分变异推理（ADVI）.
- [Evolved channel selection by Mat Kelcey](http://matpalm.com/blog/evolved_channel_selection/) -训练对不同分辨率的输入通道的不同组合具有鲁棒性的分类模型，然后使用遗传算法确定特定损失的最佳组合.
- [Introduction to JAX by Kevin Murphy](https://colab.research.google.com/github/probml/pyprobml/blob/master/book1/supplements/jax_intro.ipynb) -Colab介绍了语言的各个方面，并将它们应用于简单的ML问题.

<a name="community" />

## Community

- [JAX GitHub Discussions](https://github.com/google/jax/discussions)
- [Reddit](https://www.reddit.com/r/JAX/)

## Contributing

欢迎捐款！ 阅读 [contribution guidelines](https://github.com/n2cholas/awesome-jax/blob/master/contributing.md) 第一的.
