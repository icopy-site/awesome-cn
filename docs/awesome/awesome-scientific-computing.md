<div class="github-widget" data-repo="nschloe/awesome-scientific-computing"></div>
## Awesome Scientific Computing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


&gt; 科学计算和数值分析的有用资源.

科学计算和数值分析是旨在提供
在科学的帮助下解决来自各个科学领域的大规模问题的方法
电脑. 典型问题是常微分方程和偏微分方程（ODE，
PDEs），它们的离散化，以及由以下问题引起的线性代数问题的解
them.



## Basic linear algebra

- [BLAS](https://netlib.org/blas/) - 用于执行基本向量和矩阵运算的标准构建块.
  （Fortran，公共领域， [GitHub](https://github.com/Reference-LAPACK/lapack/tree/master/BLAS))
- [OpenBLAS](https://www.openblas.net) - 基于GotoBLAS2优化的BLAS库.
  （C 和汇编，BSD， [GitHub](https://github.com/xianyi/OpenBLAS))
- [BLIS](https://github.com/flame/blis) - 类似于 BLAS 的高性能密集线性代数库.
  (C, BSD, GitHub)
- [LAPACK](https://netlib.org/lapack/) - 求解线性方程组、线性最小二乘法、特征值问题等的例程.
  (Fortran, BSD, [GitHub](https://github.com/Reference-LAPACK/lapack))
- [Eigen](https://eigen.tuxfamily.org/index.php?title=Main_Page) - 用于线性代数的 C++ 模板库.
  （C++，MPL 2， [GitLab](https://gitlab.com/libeigen/eigen))
- [Ginkgo](https://ginkgo-project.github.io/) - 高性能众核线性代数库，专注于稀疏系统.
  (C++, BSD, [GitHub](https://github.com/ginkgo-project/ginkgo))
- [blaze](https://bitbucket.org/blaze-lib/blaze) - 用于密集和稀疏算术的高性能 C++ 数学库.
  (C++, BSD, 比特桶)

## Multi-purpose toolkits

- [PETSc](https://www.mcs.anl.gov/petsc/) - 由 PDE 建模的科学应用程序的并行解决方案.
  (C, 2-clause BSD, [GitLab](https://gitlab.com/petsc/petsc))
- [DUNE Numerics](https://www.dune-project.org) - 使用基于网格的方法求解偏微分方程的工具箱.
  (C++, GPL 2, [GitLab](https://gitlab.dune-project.org/core/))
- [SciPy](https://scipy.org) - 用于统计、优化、集成、线性代数等的 Python 模块.
  （Python，主要是 BSD， [GitHub](https://github.com/scipy/scipy/))
- [NumPy](https://numpy.org/) - 使用 Python 进行科学计算所需的基础包.
  （蟒蛇，BSD， [GitHub](https://github.com/numpy/numpy))
- [DifferentialEquations.jl](https://diffeq.sciml.ai/)  - 用于数值求解不同类型微分方程的工具箱.  （朱莉娅，麻省理工学院， [GitHub](https://github.com/SciML/DifferentialEquations.jl))

## Finite Elements

- [FEniCS](https://fenicsproject.org) - 用 Python 和 C++ 求解偏微分方程的计算平台.
  （C++/Python，LGPL 3， [GitHub](https://github.com/FEniCS)/[Bitbucket](https://bitbucket.org/fenics-project/))
- [libMesh](https://libmesh.github.io) - 使用非结构化离散化的 PDE 数值模拟框架.
  （C++，LGPL 2.1， [GitHub](https://github.com/libMesh/libmesh))
- [deal.II](https://dealii.org) - 支持创建有限元代码的软件库.
  （C++，LGPL 2.1， [GitHub](https://github.com/dealii/dealii))
- [Netgen/NGSolve](https://ngsolve.org) - 高性能多物理场有限元软件.
  （C++，LGPL 2.1， [GitHub](https://github.com/NGSolve/netgen))
- [Firedrake](https://www.firedrakeproject.org) - 使用有限元法求解偏微分方程的自动化系统.
  （蟒蛇，LGPL 3， [GitHub](https://github.com/firedrakeproject/firedrake))
- [MOOSE](https://mooseframework.inl.gov/) - 多物理场面向对象仿真环境.
  （C++，LGPL 2.1， [GitHub](https://github.com/idaholab/moose))
- [MFEM](https://mfem.org) - 用于有限元方法的免费、轻量级、可扩展的 C++ 库.
  (C++, BSD-3-Clause, [GitHub](https://github.com/mfem/mfem))
- [SfePy](https://sfepy.org) - Python 中的简单有限元.
  （蟒蛇，BSD， [GitHub](https://github.com/sfepy/sfepy))
- [FreeFEM](https://freefem.org) - 高级多物理场-多网格有限元语言.
  (C++, LGPL, [GitHub](https://github.com/FreeFem))
- [libceed](https://libceed.readthedocs.io/en/latest/index.html) - 高效可扩展离散化代码.
  (C, 2-clause BSD, [GitHub](https://github.com/CEED/libCEED))
- [scikit-fem](https://github.com/kinnala/scikit-fem) - 简单的有限元装配器.
  （Python、BSD/GPL、GitHub）

## Meshing

### Triangular and tetrahedral meshing

- [Gmsh](https://gmsh.info) - 具有预处理和后处理设施的三维有限元网格生成器.
  (C++, GPL, [GitLab](https://gitlab.onelab.info/gmsh/gmsh))
- [pygmsh](https://github.com/nschloe/pygmsh) - Gmsh 的 Python 接口.
  （Python、GPL 3、GitHub）
- [MeshPy](https://mathema.tician.de/software/meshpy/) - 优质的三角形和四面体网格生成.
  （蟒蛇，麻省理工学院， [GitHub](https://github.com/inducer/meshpy))
- [CGAL](https://www.cgal.org) - 计算几何算法.
  （C++，混合 LGPL/GPL， [GitHub](https://github.com/CGAL/cgal))
- [pygalmesh](https://github.com/meshpro/pygalmesh) - 用于 CGAL 的 3D 网格划分功能的 Python 接口.
  （Python、GPL 3、GitHub）
- [TetGen](https://www.wias-berlin.de/software/index.jsp?id=TetGen) - 优质四面体网格生成器和 3D Delaunay 三角剖分器.
  （C++，AGPLv3）
- [Triangle](https://www.cs.cmu.edu/~quake/triangle.html) - 二维质量网格生成器和 Delaunay 三角剖分器.
  （C，_非自由软件_）
- [distmesh](http://persson.berkeley.edu/distmesh/) - 用于非结构化三角形和四面体网格的简单生成器.
  （MATLAB，GPL 3）
- [trimesh](https://trimsh.org/) - 加载和使用三角形网格，重点是水密表面.
  （蟒蛇，麻省理工学院， [GitHub](https://github.com/mikedh/trimesh))
- [dmsh](https://github.com/meshpro/dmsh) - 受 distmesh 启发的非结构化三角形网格的简单生成器.
  （Python，专有，GitHub）
- [TetWild](https://yixin-hu.github.io/tetwild.pdf) - 为三角形表面网格生成四面体网格.
  (C++, GPL 3, [GitHub](https://github.com/Yixin-Hu/TetWild))
- [TriWild](https://cims.nyu.edu/gcl/papers/2019-TriWild.pdf) - 具有曲线约束的稳健三角测量.
  （C++，MPL 2， [GitHub](https://github.com/wildmeshing/TriWild))
- [fTetWild](https://arxiv.org/abs/1908.03581) - 与 TetWild 相同，但速度更快.
  （C++，MPL 2， [GitHub](https://github.com/wildmeshing/fTetWild))
- [SeismicMesh](https://github.com/krober10nd/SeismicMesh) - 平行 2D/3D 三角形/四面体网格生成，去除条子.
  （Python 和 C++，GPL 3，GitHub）

### Quadrilateral and hexahedral meshing

- [QuadriFlow](https://stanford.edu/~jingweih/papers/quadriflow/) - 来自三角测量的可扩展且强大的四边形测量.
  (C++, BSD, [GitHub](https://github.com/hjwdzh/QuadriFlow))

### Mesh tools

- [meshio](https://github.com/nschloe/meshio) - 各种网格格式的 I/O，文件转换.
  （Python、麻省理工学院、GitHub）
- [MOAB](https://sigma.mcs.anl.gov/moab-library/) - 表示和评估网格数据.
  （C++，主要是 LGPL 3， [Bitbucket](https://bitbucket.org/fathomteam/moab/))
- [optimesh](https://github.com/meshpro/optimesh) - 三角网格平滑.
  （Python，专有，GitHub）
- [pmp-library](https://www.pmp-library.org/) - 多边形网格处理库.
  （C++，麻省理工学院与雇主免责声明， [GitHub](https://github.com/pmp-library/pmp-library/))
- [Mmg](https://www.mmgtools.org/) - 用于重新划分网格的强大、开源和多学科软件.
  （C，LGPL 3， [GitHub](https://github.com/MmgTools/mmg))
- [meshplex](https://github.com/meshpro/meshplex) - 单纯形网格的快速工具.
  （Python，专有，GitHub）

## Data formats

- [NetCDF](https://www.unidata.ucar.edu/software/netcdf/) - 面向阵列的科学数据的软件库和数据格式.
  （C/C++/Fortran/Java/Python，[自定义开源
  许可](https://www.unidata.ucar.edu/software/netcdf/copyright.html),
  [GitHub](https://github.com/Unidata/netcdf-c/))
- [HDF5](https://support.hdfgroup.org/HDF5/) - 用于存储和管理数据的数据模型、库和文件格式.
  (C/Fortran, BSD, [GitHub](https://github.com/HDFGroup/hdf5))
- [XDMF](https://xdmf.org/index.php/Main_Page) - 高性能计算代码数据的可扩展数据模型和格式.
  (C++, [GitLab](https://gitlab.kitware.com/xdmf/xdmf))
- [Zarr](https://zarr.readthedocs.io/en/stable/) - 用于存储分块、压缩、N 维数组的格式.
  （蟒蛇，麻省理工学院， [GitHub](https://github.com/zarr-developers/zarr-python))

## Sparse linear solvers

- [SuperLU](https://portal.nersc.gov/project/sparse/superlu/) - 大型、稀疏、非对称线性方程组的直接解.
  （C，主要是 BSD， [GitHub](https://github.com/xiaoyeli/superlu))
- [PyAMG](https://pyamg.readthedocs.io/en/latest/) - Python 中的代数多重网格求解器.
  （蟒蛇，麻省理工学院， [GitHub](https://github.com/pyamg/pyamg))
- [hypre](https://computing.llnl.gov/projects/hypre-scalable-linear-solvers-multigrid-methods) - 高性能预调节器和求解器库.
  （C，Apache 2.0/麻省理工学院， [GitHub](https://github.com/hypre-space/hypre))

## Visualization

- [ParaView](https://www.paraview.org) - 基于VTK的多平台数据分析和可视化应用.
  (C++, BSD, [GitLab](https://gitlab.kitware.com/paraview/paraview))
- [VTK](https://vtk.org/) - 处理图像并创建 3D 计算机图形.
  (C++, BSD, [GitLab](https://gitlab.kitware.com/vtk/vtk))
- [Mayavi](https://docs.enthought.com/mayavi/mayavi/) - Python 中的 3D 科学数据可视化和绘图.
  （蟒蛇，BSD， [GitHub](https://github.com/enthought/mayavi))
- [Polyscope](https://polyscope.run/) - 用于 3D 几何处理的查看器和用户界面.
  （C++，麻省理工学院， [GitHub](https://github.com/nmwsharp/polyscope))
- [PyVista](https://docs.pyvista.org/) - 通过 VTK 的简化界面进行 3D 绘图和网格分析.
  （蟒蛇，麻省理工学院， [GitHub](https://github.com/pyvista/pyvista))
- [vedo](https://vedo.embl.es) - 基于 VTK 的 3D 对象的科学分析和可视化库.
  （蟒蛇，麻省理工学院， [GitHub](https://github.com/marcomusy/vedo))
- [yt](https://yt-project.org/) - 用于体积数据分析和可视化的工具包.
  （蟒蛇，BSD， [GitHub](https://github.com/yt-project/yt))
- [F3D](https://f3d.app/) - 具有科学可视化工具的跨平台、快速且简约的 3D 查看器.
  (C++, BSD, [GitHub](https://github.com/f3d-app/f3d))
- [TTK](https://topology-tool-kit.github.io/) - 拓扑数据分析和可视化.
  (C++/Python, BSD, [GitHub](https://github.com/topology-tool-kit/ttk))
- [morphologica](https://github.com/ABRG-Models/morphologica)  - 仅标头的现代 OpenGL 代码可在运行时可视化数值模拟.  （C++、阿帕奇 2.0、GitHub）

## Other libraries and tools

- [FFTW](http://www.fftw.org) - 一维或多维离散傅里叶变换，任意输入大小，实数和复数.
  （C，GPL2， [GitHub](https://github.com/FFTW/fftw3))
- [Qhull](http://www.qhull.org) - 凸包、Delaunay 三角剖分、Voronoi 图、关于点的半空间交集等.
  (C/C++, [custom open source license](http://www.qhull.org/COPYING.txt),
  [GitHub](https://github.com/qhull/qhull/))
- [GSL](https://www.gnu.org/software/gsl/) - 随机数生成器、特殊函数和最小二乘拟合等.
  （C/C++，GPL 3， [Savannah](https://savannah.gnu.org/projects/gsl))
- [OpenFOAM](https://www.openfoam.com) - 免费、开源的 CFD（计算流体动力学）软件.
  (C++, GPL 3, [GitHub](https://github.com/OpenFOAM/OpenFOAM-dev))
- [quadpy](https://github.com/sigma-py/quadpy) - Python 中的数值积分（正交、立方）.
  （Python，专有，GitHub）
- [FiPy](https://www.ctcms.nist.gov/fipy/) - 有限体积 PDE 求解器.
  （Python，[自定义开源
  许可证]（https://www.nist.gov/open/copyright-fair-use-and-licensing-statements-srd-data-software-and-technical-series-publications），
  [GitHub](https://github.com/usnistgov/fipy))
- [accupy](https://github.com/sigma-py/accupy) - Python 的准确求和和点积.
  （Python、GPL 3、GitHub）
- [SLEPc](https://slepc.upv.es) - Scalable Library for Eigenvalue Problem Computations.
  (C, 2-clause BSD, [GitLab](https://gitlab.com/slepc/slepc))
- [Chebfun](https://www.chebfun.org/) - 计算精度约为 15 位数字的函数.
  （MATLAB，BSD， [GitHub](https://github.com/chebfun/chebfun))
- [pyMOR](https://pymor.org/) - 使用 Python 减少模型订单.
  (Python, 2-clause BSD, [GitHub](https://github.com/pymor/pymor/))
- [cvxpy](https://www.cvxpy.org/) - 凸优化问题的建模语言.
  （蟒蛇，阿帕奇2.0， [GitHub](https://github.com/cvxpy/cvxpy))
- [PyWavelets](https://pywavelets.readthedocs.io/en/latest/) - Python 中的小波变换.
  （蟒蛇，麻省理工学院， [GitHub](https://github.com/PyWavelets/pywt))
- [NFFT](https://www-user.tu-chemnitz.de/~potts/nfft/) - 非等空间快速傅立叶变换.
  （C/MATLAB，GPL 2， [GitHub](https://github.com/NFFT/nfft))
- [preCICE](https://precice.org/) - 用于分区多物理仿真（FSI、CHT 等）的耦合库.
  （C++，LGPL 3， [GitHub](https://github.com/precice/))
- [orthopy](https://github.com/sigma-py/orthopy) - 有效地计算正交多项式.
  （Python，专有，GitHub）
- [pyGAM](https://pygam.readthedocs.io/en/latest/) - Python 中的广义加法模型.
  （蟒蛇，阿帕奇2.0， [GitHub](https://github.com/dswah/pyGAM))
- [Dedalus](https://dedalus-project.org/) - 用谱法求解偏微分方程.
  （蟒蛇，GPL 3， [GitHub](https://github.com/DedalusProject/dedalus))
- [PyGMO](https://esa.github.io/pygmo/) - 大规模并行优化.
  （Python/C++，MPL 2， [GitHub](https://github.com/esa/pygmo2))
- [shenfun](https://shenfun.readthedocs.io/en/latest/) - 用于光谱 Galerkin 方法的高性能 Python 库.
  （蟒蛇，BSD-2， [GitHub](https://github.com/spectralDNS/shenfun))
- [PyDMD](https://github.com/mathLab/PyDMD) - Python 中的动态模式分解 (DMD).
  （Python、麻省理工学院、GitHub）
- [HPDDM](https://github.com/hpddm/hpddm) - 域分解方法的高性能统一框架.
  （C++，LGPL 3，GitHub）

## Community

- [SciComp StackExchange](https://scicomp.stackexchange.com/) - StackExchange 网络上的计算科学.
- [Wolfgang Bangerth's video class](https://www.math.colostate.edu/~bangerth/videos.html) - MATH 676：科学计算中的有限元方法.
- [Nick Higham's blog](https://nhigham.com/) - 主要是关于 MATLAB，一般计算建议.
- [Nick Trefethen's Video Lectures](https://people.maths.ox.ac.uk/trefethen/videos.html) - 36 个关于逼近理论/实践和科学计算的视频讲座.
- [John D. Cook's blog](https://www.johndcook.com/blog/) - 科学计算的壮举.
- [Jack Dongarra's software list](https://netlib.org/utk/people/JackDongarra/la-sw.html) - 用于解决线性代数问题的免费软件列表.
- [NA Digest](https://netlib.org/na-digest-html/) - 收集与数值分析相关的主题的文章和实践者.
- [Gabriel Peyré on Twitter](https://twitter.com/gabrielpeyre) - 每天一条关于计算数学的推文.
- [Discord: Numerical Software](https://discord.com/invite/hnTJ5MRX2Y) - 数字软件上的 Discord 消息服务器.
