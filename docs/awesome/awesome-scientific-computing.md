<div class="github-widget" data-repo="nschloe/awesome-scientific-computing"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Scientific Computing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)



&gt;用于科学计算和数值分析的有用资源.

科学计算和数值分析是旨在提供
借助以下方法解决各个科学领域的大规模问题的方法
 电脑.  典型的问题是常微分方程和偏微分方程（ODE，
PDE），离散化和线性代数问题的解
them.





## Basic linear algebra

- [BLAS](https://www.netlib.org/blas/) -用于执行基本矢量和矩阵运算的标准构件.
  （Fortran，公共领域， [GitHub](https://github.com/Reference-LAPACK/lapack/tree/master/BLAS))
- [OpenBLAS](https://www.openblas.net) -基于GotoBLAS2的优化的BLAS库.
  （C和汇编，BSD， [GitHub](https://github.com/xianyi/OpenBLAS))
- [BLIS](https://github.com/flame/blis) -类似于BLAS的高性能密集线性代数库.
  （C，BSD，GitHub）
- [LAPACK](https://www.netlib.org/lapack/) -求解线性方程组，线性系统的最小二乘法，特征值问题和奇异值问题的例程.
  （Fortran，BSD， [GitHub](https://github.com/Reference-LAPACK/lapack))
- [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page) -线性代数的C ++模板库.
  （C ++，MPL 2， [BitBucket](https://bitbucket.org/eigen/eigen))
- [Ginkgo](https://ginkgo-project.github.io/) -高性能manycore线性代数库，专注于稀疏系统.
  （100 ++，BSD， [GitHub](https://github.com/ginkgo-project/ginkgo))


## Multi-purpose toolkits

- [PETSc](https://www.mcs.anl.gov/petsc/) -用于PDE建模的科学应用并行解决方案的数据结构和例程.
  （C，2句BSD， [GitLab](https://gitlab.com/petsc/petsc))
- [DUNE Numerics](https://www.dune-project.org) -使用基于网格的方法解决PDE的工具箱.
  （C ++，GPL 2， [GitLab](https://gitlab.dune-project.org/core/))
- [SciPy](https://www.scipy.org) -用于统计，优化，积分，线性代数，傅立叶变换，信号和图像处理，ODE求解器等的Python模块.
  （Python，主要是BSD， [GitHub](https://github.com/scipy/scipy/))
- [NumPy](https://numpy.org/) -使用Python进行科学计算所需的基本软件包.
  （Python，BSD， [GitHub](https://github.com/numpy/numpy))


## Finite Elements

- [FEniCS](https://fenicsproject.org) -用于用Python和C ++解决PDE的开源计算平台.
  （C ++ / Python，LGPL 3， [BitBucket](https://bitbucket.org/fenics-project/))
- [libMesh](https://libmesh.github.io) -使用任意非结构化离散化进行PDE数值模拟的框架.
  （C ++，LGPL 2.1， [GitHub](https://github.com/libMesh/libmesh))
- [deal.II](https://dealii.org) -支持创建有限元代码的软件库.
  （C ++，LGPL 2.1， [GitHub](https://github.com/dealii/dealii))
- [Netgen/NGSolve](https://ngsolve.org) -高性能多物理场有限元软件.
  （C ++，LGPL 2.1， [GitHub](https://github.com/NGSolve/netgen))
- [Firedrake](https://www.firedrakeproject.org) -使用有限元方法的PDE自动化解决方案.
  （Python，LGPL 3， [GitHub](https://github.com/firedrakeproject/firedrake))
- [MOOSE](https://www.mooseframework.org) -多物理场面向对象的仿真环境.
  （C ++，LGPL 2.1， [GitHub](https://github.com/idaholab/moose))
- [MFEM](https://mfem.org) -用于有限元方法的免费，轻量级，可扩展的C ++库.
  （C ++，LGPL 2.1， [GitHub](https://github.com/mfem/mfem))
- [SfePy](https://sfepy.org) -Python中的简单有限元.
  （Python，BSD， [GitHub](https://github.com/sfepy/sfepy))
- [FreeFEM](https://freefem.org)  -高级Multiphysics-multimesh有限元语言.  （C ++，LGPL， [GitHub](https://github.com/FreeFem))

## Meshing

- [Gmsh](http://gmsh.info) -具有预处理和后处理功能的三维有限元网格生成器.
  （C ++，GPL， [GitLab](https://gitlab.onelab.info/gmsh/gmsh))
- [pygmsh](https://github.com/nschloe/pygmsh) -Gmsh的Python界面.
  （Python，麻省理工学院，GitHub）
- [MeshPy](https://mathema.tician.de/software/meshpy/) -优质的三角形和四面体网格生成.
  （Python，麻省理工学院， [GitHub](https://github.com/inducer/meshpy))
- [meshio](https://github.com/nschloe/meshio) -各种网格格式的I / O，文件转换.
  （Python，麻省理工学院，GitHub）
- [CGAL](https://www.cgal.org) -计算几何的算法.
  （C ++，混合的LGPL / GPL， [GitHub](https://github.com/CGAL/cgal))
- [pygalmesh](https://github.com/nschloe/pygalmesh) -CGAL 3D网格化功能的Python界面.
  （Python，麻省理工学院，GitHub）
- [mshr](https://bitbucket.org/fenics-project/mshr/) -FEniCS的网格生成组件.
  （Python，GPL 3，BitBucket）
- [MOAB](https://press3.mcs.anl.gov/sigma/moab-library/) -表示和评估网格数据.
  （C ++，主要是LGPL3， [BitBucket](https://bitbucket.org/fathomteam/moab/))
- [NetCDF](https://www.unidata.ucar.edu/software/netcdf/) -用于创建，访问和共享面向阵列的科学数据的软件库和数据格式.
  （C / C ++ / Fortran / Java / Python，[自定义开源
  许可]（https://www.unidata.ucar.edu/software/netcdf/copyright.html），
  [GitHub](https://github.com/Unidata/netcdf-c/))
- [HDF5](https://support.hdfgroup.org/HDF5/) -用于存储和管理数据的数据模型，库和文件格式.
  （C / Fortran，BSD）
- [XDMF](http://www.xdmf.org/index.php/Main_Page) -可扩展的数据模型和格式，可在高性能计算代码和工具之间交换科学数据.
  （C ++， [GitLab](https://gitlab.kitware.com/xdmf/xdmf))
- [TetGen](https://www.wias-berlin.de/software/index.jsp?id=TetGen) -优质的四面体网格生成器和3D Delaunay三角剖分器.
  （C ++，AGPLv3）
- [Triangle](https://www.cs.cmu.edu/~quake/triangle.html) -二维质量网格生成器和Delaunay三角剖分器.
  （C，*非免费软件*）
- [optimesh](https://github.com/nschloe/optimesh) -三角网格平滑.
  （Python，麻省理工学院，GitHub）
- [distmesh](http://persson.berkeley.edu/distmesh/) -用于非结构化三角形和四面体网格的简单生成器.
  （MATLAB，GPL 3）
- [QuadriFlow](https://stanford.edu/~jingweih/papers/quadriflow/) -一种可扩展且鲁棒的四边形方法.
  （100 ++，BSD， [GitHub](https://github.com/hjwdzh/QuadriFlow))
- [trimesh](https://trimsh.org/) -加载和使用三角网格，重点放在水密表面上.
  （Python，麻省理工学院， [GitHub](https://github.com/mikedh/trimesh))
- [dmsh](https://github.com/nschloe/dmsh) -由distmesh启发的非结构三角形网格的简单生成器.
  （Python，麻省理工学院，GitHub）
- [pmp-library](http://www.pmp-library.org/)  -多边形网格处理库.  （C ++，MIT，雇主免责声明， [GitHub](https://github.com/pmp-library/pmp-library/))
- [Mmg](https://www.mmgtools.org/)  -健壮，开放源代码和多学科的软件，可用于重新设计.  （C，LGPL 3， [GitHub](https://github.com/MmgTools/mmg))
- [meshplex](https://github.com/nschloe/meshplex)  -单工网格的快速工具.  （Python，麻省理工学院，GitHub）

## Sparse linear solvers

- [SuperLU](https://portal.nersc.gov/project/sparse/superlu/) -大型，稀疏，非对称线性方程组的直接解.
  （C，主要是BSD， [GitHub](https://github.com/xiaoyeli/superlu))
- [KryPy](https://github.com/andrenarchy/krypy) -用于线性代数系统求解的Krylov子空间方法.
  （Python，麻省理工学院，GitHub）
- [PyAMG](https://pyamg.github.io) -Python中的代数多重网格求解器.
  （Python，麻省理工学院， [GitHub](https://github.com/pyamg/pyamg))
- [hypre](https://computing.llnl.gov/projects/hypre-scalable-linear-solvers-multigrid-methods) -高性能预处理器和求解器库.
  （C，Apache 2.0 / MIT， [GitHub](https://github.com/hypre-space/hypre))


## Other libraries and tools

- [FFTW](http://www.fftw.org) -一维或多维，任意输入大小以及实数据和复杂数据的离散傅立叶变换.
  （C，GPL2， [GitHub](https://github.com/FFTW/fftw3))
- [Qhull](http://www.qhull.org) -凸包，Delaunay三角剖分，Voronoi图，围绕点的半空间交点，最远位置的Delaunay三角剖分和最远位置的Voronoi图.
  （C / C ++， [custom open source license](http://www.qhull.org/COPYING.txt),
  [GitHub](https://github.com/qhull/qhull/))
- [GSL](https://www.gnu.org/software/gsl/) -广泛的数学例程，例如随机数生成器，特殊函数和最小二乘拟合.
  （C / C ++，GPL 3， [Savannah](https://savannah.gnu.org/projects/gsl))
- [OpenFOAM](https://www.openfoam.com) -免费的开源CFD（计算流体动力学）软件.
  （C ++，GPL 3， [GitHub](https://github.com/OpenFOAM/OpenFOAM-dev))
- [ParaView](https://www.paraview.org) -基于VTK的多平台数据分析和可视化应用程序.
  （100 ++，BSD， [GitLab](https://gitlab.kitware.com/paraview/paraview))
- [quadpy](https://github.com/nschloe/quadpy) -Python中的数值积分（正交，容积）.
  （Python，麻省理工学院，GitHub）
- [FiPy](https://www.ctcms.nist.gov/fipy/) -有限体积的PDF解算器.
  （Python，[自定义开源
  许可]（https://www.nist.gov/director/copyright-fair-use-and-licensing-statements-srd-data-and-software），
  [GitHub](https://github.com/usnistgov/fipy))
- [accupy](https://github.com/nschloe/accupy) - Accurate sums and dot products for Python.
  （Python，麻省理工学院，GitHub）
- [SLEPc](http://slepc.upv.es) -特征值问题计算的可扩展库.
  （C，2句BSD， [BitBucket](https://bitbucket.org/slepc/slepc/src/master/))
- [Chebfun](https://www.chebfun.org/) -具有约15位精度的函数计算.
  （MATLAB，BSD， [GitHub](https://github.com/chebfun/chebfun))
- [pyMOR](https://pymor.org/) -使用Python减少模型订单.
  （Python，2句BSD， [GitHub](https://github.com/pymor/pymor/))
- [cvxpy](https://www.cvxpy.org/) -凸优化问题的建模语言.
  （Python，Apache 2.0， [GitHub](https://github.com/cvxgrp/cvxpy))


## Community

- [SciComp StackExchange](https://scicomp.stackexchange.com/) -StackExchange网络上的计算科学.
- [Wolfgang Bangerth's video class](https://www.math.colostate.edu/~bangerth/videos.html) -MATH 676：科学计算中的有限元方法.
- [Nick Higham's blog](https://nickhigham.wordpress.com/) -通常在MATLAB上提供一般计算建议.
- [Nick Trefethen's Video Lectures](https://people.maths.ox.ac.uk/trefethen/videos.html) -关于逼近理论/实践和科学计算的36个视频讲座.
- [John D. Cook's blog](https://www.johndcook.com/blog/) -科学计算的壮举.
- [Jack Dongarra's software list](https://www.netlib.org/utk/people/JackDongarra/la-sw.html) -解决线性代数问题的免费软件列表.
- [NA Digest](http://www.netlib.org/na-digest-html/) -收集与数值分析有关的主题和实践者的文章.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Nico Schlömer](https://github.com/nschloe)
放弃了此作品的所有版权以及相关或邻近的权利.
