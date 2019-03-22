<div class="github-widget" data-repo="nschloe/awesome-scientific-computing"></div>
## Awesome Scientific Computing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)



&gt;有用的科学计算和数值分析资源.

科学计算和数值分析是旨在提供的研究领域
在各种科学领域解决大规模问题的方法
 电脑.  典型的问题是普通和偏微分方程（ODEs，
偏微分方程，它们的离散化，以及由此产生的线性代数问题的解决方案
them.





## Basic linear algebra

- [BLAS](https://www.netlib.org/blas/) - 用于执行基本矢量和矩阵运算的标准构建块.
  （Fortran，公共领域， [GitHub](https://github.com/Reference-LAPACK/lapack/tree/master/BLAS))
- [OpenBLAS](https://www.openblas.net) - 基于GotoBLAS2的优化BLAS库.
  （Fortran，BSD， [GitHub](https://github.com/xianyi/OpenBLAS))
- [BLIS](https://github.com/flame/blis) - 高性能BLAS类密集线性代数库.
  （C ++，BSD，GitHub）
- [LAPACK](https://www.netlib.org/lapack/) - 用于求解线性方程组，线性系统最小二乘解，特征值问题和奇异值问题的例程.
  （Fortran，BSD， [GitHub](https://github.com/Reference-LAPACK/lapack))
- [Eigen](https://eigen.tuxfamily.org/index.php?title=Main_Page) - 线性代数的C ++模板库.
  （C ++，MPL 2， [BitBucket](https://bitbucket.org/eigen/eigen))


## Frameworks

- [PETSc](https://www.mcs.anl.gov/petsc/) - 由PDE建模的科学应用并行解决方案的数据结构和例程.
  （C，2条款BSD， [BitBucket](https://bitbucket.org/petsc/petsc/src))
- [DUNE Numerics](https://www.dune-project.org) - 使用基于网格的方法解决PDE的工具箱.
  （C ++，GPL 2， [GitLab](https://gitlab.dune-project.org/core/))
- [Trilinos](https://trilinos.org) - 用于解决大规模，复杂的多物理工程和科学问题的算法和支持技术.
  （主要是C ++，主要是BSD， [GitHub](https://github.com/trilinos/))
- [SciPy](https://www.scipy.org) - 用于统计，优化，集成，线性代数，傅立叶变换，信号和图像处理，ODE求解器等的Python模块.
  （Python，主要是BSD， [GitHub](https://github.com/scipy/scipy/))
- [NumPy](https://www.numpy.org) - 使用Python进行科学计算所需的基础包.
  （Python，BSD， [GitHub](https://github.com/numpy/numpy))


## Finite Elements

- [FEniCS](https://fenicsproject.org) - 用于在Python和C ++中解决PDE的开源计算平台.
  （C ++ / Python，LGPL 3， [BitBucket](https://bitbucket.org/fenics-project/))
- [libMesh](https://libmesh.github.io) - 使用任意非结构离散化的偏微分方程数值模拟框架.
  （C ++，LGPL 2.1， [GitHub](https://github.com/libMesh/libmesh))
- [deal.II](https://dealii.org) - 支持创建有限元代码的软件库.
  （C ++，LGPL 2.1， [GitHub](https://github.com/dealii/dealii))
- [Netgen/NGSolve](https://ngsolve.org) - 高性能多物理场有限元软件.
  （C ++，LGPL 2.1， [GitHub](https://github.com/NGSolve/netgen))
- [Firedrake](https://www.firedrakeproject.org) - 使用有限元方法解决PDE的自动化系统.
  （Python，LGPL 3， [GitHub](https://github.com/firedrakeproject/firedrake))
- [MOOSE](https://www.mooseframework.org) - 面向对象的多物理场仿真环境.
  （C / Python，LGPL 2.1， [GitHub](https://github.com/idaholab/moose))
- [MFEM](https://mfem.org) - 用于有限元方法的免费，轻量级，可扩展的C ++库.
  （C ++，LGPL 2.1， [GitHub](https://github.com/mfem/mfem))
- [SfePy](https://sfepy.org) -  Python中的简单有限元.
  （Python，BSD， [GitHub](https://github.com/sfepy/sfepy))


## Meshing

- [Gmsh](http://gmsh.info) - 具有预处理和后处理设施的三维有限元网格生成器.
  （C ++，GPL， [GitLab](https://gitlab.onelab.info/gmsh/gmsh))
- [pygmsh](https://github.com/nschloe/pygmsh) -  Gmsh的Python界面.
  （Python，MIT，GitHub）
- [MeshPy](https://mathema.tician.de/software/meshpy/) - 优质的三角形和四面体网格生成.
  （Python，麻省理工学院， [GitHub](https://github.com/inducer/meshpy))
- [meshio](https://github.com/nschloe/meshio) - 各种网格格式的I / O，文件转换.
  （Python，MIT，GitHub）
- [CGAL](https://www.cgal.org) - 计算几何的算法.
  （C ++，混合LGPL / GPL， [GitHub](https://github.com/CGAL/cgal))
- [pygalmesh](https://github.com/nschloe/pygalmesh) - 用于CGAL 3D网格划分功能的Python界面.
  （Python，MIT，GitHub）
- [mshr](https://bitbucket.org/fenics-project/mshr/) -  FEniCS的网格生成组件.
  （Python，GPL 3，BitBucket）
- [MOAB](https://press3.mcs.anl.gov/sigma/moab-library/) - 表示和评估网格数据.
  （C ++，主要是LGPL3， [BitBucket](https://bitbucket.org/fathomteam/moab/))
- [NetCDF](https://www.unidata.ucar.edu/software/netcdf/) - 用于创建，访问和共享面向阵列的科学数据的软件库和数据格式.
  （C / C ++ / Fortran / Java / Python，[自定义开源
  许可证（https://www.unidata.ucar.edu/software/netcdf/copyright.html），
  [GitHub](https://github.com/Unidata/netcdf-c/))
- [HDF5](https://support.hdfgroup.org/HDF5/) - 用于存储和管理数据的数据模型，库和文件格式.
  （C / Fortran，BSD）
- [XDMF](http://www.xdmf.org/index.php/Main_Page) - 可扩展数据模型和格式，用于在高性能计算代码和工具之间交换科学数据.
  （C ++， [GitLab](https://gitlab.kitware.com/xdmf/xdmf))
- [TetGen](https://www.wias-berlin.de/software/index.jsp?id=TetGen) - 优质四面体网格生成器和3D Delaunay三角形.
  （C ++，AGPLv3）
- [Triangle](https://www.cs.cmu.edu/~quake/triangle.html) - 二维质量网格生成器和Delaunay三角形.
  （C，*非自由软件*）
- [optimesh](https://github.com/nschloe/optimesh) - 三角网格平滑.
  （Python，MIT，GitHub）
- [distmesh](http://persson.berkeley.edu/distmesh/) - 用于非结构化三角形和四面体网格的简单生成器.
  （MATLAB，GPL 3）
- [QuadriFlow](https://stanford.edu/~jingweih/papers/quadriflow/) - 可扩展且稳健的四边形方法.
  （100 ++，BSD， [GitHub](https://github.com/hjwdzh/QuadriFlow))
- [trimesh](https://trimsh.org/) - 加载和使用三角形网格，重点是防水表面.
  （Python，麻省理工学院， [GitHub](https://github.com/mikedh/trimesh))


## Sparse linear solvers

- [SuperLU](https://crd-legacy.lbl.gov/~xiaoye/SuperLU/) - 直接求解大型，稀疏，非对称线性方程组.
  （C，主要是BSD， [GitHub](https://github.com/xiaoyeli/superlu))
- [KryPy](https://github.com/andrenarchy/krypy) - 用于求解线性代数系统的Krylov子空间方法.
  （Python，MIT，GitHub）
- [PyAMG](https://pyamg.github.io) -  Python中的代数多重网格求解器.
  （Python，麻省理工学院， [GitHub](https://github.com/pyamg/pyamg))


## Other libraries and tools

- [FFTW](http://www.fftw.org) - 一维或多维的离散傅里叶变换，任意输入大小，以及实数和复数数据.
  （C，GPL2， [GitHub](https://github.com/FFTW/fftw3))
- [Qhull](http://www.qhull.org) - 凸壳，Delaunay三角剖分，Voronoi图，关于点的半空间交点，最远位置的Delaunay三角剖分，以及最远位置的Voronoi图.
  （C / C ++， [custom open source license](http://www.qhull.org/COPYING.txt),
  [GitHub](https://github.com/qhull/qhull/))
- [GSL](https://www.gnu.org/software/gsl/) - 广泛的数学例程，如随机数生成器，特殊函数和最小二乘拟合.
  （C / C ++，GPL 3， [Savannah](https://savannah.gnu.org/projects/gsl))
- [OpenFOAM](https://www.openfoam.com) - 免费的开源CFD（计算流体动力学）软件.
  （C ++，GPL 3， [GitHub](https://github.com/OpenFOAM/OpenFOAM-dev))
- [ParaView](https://www.paraview.org) - 基于VTK的多平台数据分析和可视化应用.
  （100 ++，BSD， [GitLab](https://gitlab.kitware.com/paraview/paraview))
- [quadpy](https://github.com/nschloe/quadpy) - Numerical integration (quadrature, cubature) in Python.
  （Python，MIT，GitHub）
- [FiPy](https://www.ctcms.nist.gov/fipy/) - 有限体积PDF解算器.
  （Python，[自定义开源
  许可证（https://www.nist.gov/director/copyright-fair-use-and-licensing-statements-srd-data-and-software），
  [GitHub](https://github.com/usnistgov/fipy))
- [accupy](https://github.com/nschloe/accupy) -  Python的准确总和和点积.
  （Python，MIT，GitHub）
- [SLEPc](http://slepc.upv.es) - 特征值问题计算的可扩展库.
  （C，2条款BSD， [BitBucket](https://bitbucket.org/slepc/slepc/src/master/))
- [Chebfun](https://www.chebfun.org/) - 具有大约15位精度的功能计算.
  （MATLAB，BSD，[GitHub](https://github.com/chebfun/chebfun))


## Community

- [SciComp StackExchange](https://scicomp.stackexchange.com/) -  StackExchange网络上的计算科学.
- [Wolfgang Bangerth's video class](https://www.math.colostate.edu/~bangerth/videos.html) -  MATH 676：科学计算中的有限元方法.
- [Nick Higham's blog](https://nickhigham.wordpress.com/) - 主要在MATLAB上，一般计算建议.
- [Nick Trefethen's Video Lectures](https://people.maths.ox.ac.uk/trefethen/videos.html) - 关于近似理论/实践和科学计算的36个视频讲座.
- [John D. Cook's blog](https://www.johndcook.com/blog/) - 科学计算的功能.
- [Jack Dongarra's software list](https://www.netlib.org/utk/people/JackDongarra/la-sw.html) - 用于解决线性代数问题的免费软件列表.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Nico Schlömer](https://github.com/nschloe)
已放弃对此作品的所有版权及相关或相邻权利.
