<div class="github-widget" data-repo="rabbiabram/awesome-fortran"></div>
## Awesome Fortran [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/rabbiabram/awesome-fortran.svg?branch=master)](https://travis-ci.org/rabbiabram/awesome-fortran)
精选的 Fortran 框架、库和软件列表. 灵感来自 [awesome-swift](https://github.com/Wolg/awesome-swift) 通过@Wolg.


## Functional Libraries
* [Functional Fortran](https://github.com/wavebitscientific/functional-fortran) - 现代 Fortran 函数式编程.


## Graphics Libraries
*用于图形、图形和 GUI 的库*

* [DISLIN](https://www.mps.mpg.de/dislin/) - 高级图形和用户界面库.
* [f90gl](https://math.nist.gov/f90gl/) - 用于 OpenGL 的官方 NIST Fortran 90 绑定的公共域实现.
* [F03GL](http://www-stone.ch.cam.ac.uk/pub/f03gl/index.xhtml) - OpenGL 库的 Fortran 2003 接口，以及 GLU 和 GLUT 工具包.
* [gtk-fortran](https://github.com/vmagnin/gtk-fortran/wiki) - 用于构建图形用户界面 (GUI) 的跨平台库 [GTK+](https://www.gtk.org/) . 结合使用时非常有用 [Glade](https://glade.gnome.org/) RAD 工具.
* [PGPLOT](https://www.astro.caltech.edu/~tjp/pgplot/) - 跨平台科学图形库.
* [VTKFortran](https://github.com/szaghi/VTKFortran) - 纯 Fortran (2003+) 库，用于写入和读取符合 VTK 标准的数据.

## Math Libs
*用于计算和其他数学运算的库.*

* [BLAS](http://www.netlib.org/blas/) - 用于发布库以执行基本线性代数运算（如向量和矩阵乘法）的应用程序编程接口标准.
* [CERNLIB](http://cernlib.web.cern.ch/cernlib/) - CERN 程序库是在 CERN 中央计算机上以源代码和目标代码形式维护和提供的大量通用库和模块的集合
* [EISPACK](http://www.netlib.org/eispack/) - 用于矩阵特征值和特征向量数值计算的软件库，用 FORTRAN 语言编写
* [FGSL](https://www.lrz.de/services/software/mathematik/gsl/fortran/index.html) - 可移植的、基于对象的 Fortran 接口 [GNU scientific library](https://www.lrz.de/services/software/mathematik/gsl/)
* [IMSL](https://www.imsl.com/products/imsl-fortran-libraries) - IMSL Fortran 数值库是高性能计算商业数学和统计库的标准
* [Lis](https://www.ssisc.org/lis/index.en.html) - 线性系统的迭代求解器库
* [netCDF](https://github.com/Unidata/netcdf-fortran) - 一组软件库和自描述、独立于机器的数据格式，支持创建、访问和共享面向阵列的科学数据.
* [OpenBLAS](https://github.com/xianyi/OpenBLAS)  - 最快的开源 BLAS 库之一. 几乎与英特尔 MKL 一样快.

## JSON Manipulation
*使用 Fortran 语言处理 JSON 数据的库.*

* [FSON](https://github.com/josephalevin/fson) - Fortran 95 JSON 解析器.
* [json-fortran](https://github.com/jacobwilliams/json-fortran) - Fortran 2008 JSON API.

## XML Manipulation
*使用 Fortran 语言处理 XML 数据的库.*

* [fox](https://github.com/andreww/fox) - Fortran XML 库
* [xml-fortran](https://sourceforge.net/projects/xml-fortran/) - 用于读取和写入 XML 文件的全 Fortran 解决方案.

## Date and time manipulation
*使用 Fortran 语言进行日期和时间操作的库.*

* [datetime-fortran](https://github.com/wavebitscientific/datetime-fortran) - Fortran 2003 日期和时间操作库，以 Python 的日期时间库为模型.

## Testing
*用于测试代码库和生成测试数据的库.*

* [FRUIT](https://sourceforge.net/projects/fortranxunit/) - FORTRAN 单元测试框架，用 FORTRAN 95 编写
* [Ftunit](http://flibs.sourceforge.net/ftnunit.html) - Arjen Markus 的 Fortran 单元测试框架
* [pFUnit](https://sourceforge.net/projects/pfunit/)  - Fortran 的单元测试框架，由 NASA 和 NGC TASC 的开发人员提供 MPI 扩展. 使用并行代码和面向对象的设计.
* [Vegetables](https://gitlab.com/everythingfunctional/vegetables) - 为了更健康的代码库，吃你的蔬菜

## Encoding-Decoding
*使用 Fortran 语言编码和解码数据的库.*

* [BeFoR64](https://github.com/szaghi/BeFoR64)  - 用于 Fortran 穷人的 Base64 编码/解码库. 用于现代（2003+）Fortran 项目的 base64 编码/解码的 KISS 库.

## Portability enabling
*用于实现代码可移植性的库.*

* [PENF](https://github.com/szaghi/PENF) - 用于确保代码可移植性的纯 Fortran (2003+) 库.

## Command-Line parsing
*用于解析命令行和构建用户界面的库.*

* [FLAP](https://github.com/szaghi/FLAP)  - 穷人的 Fortran 命令行参数解析器. 一个 KISS 库，用于为现代 (2003+) Fortran 项目轻松构建漂亮的命令行界面 (CLI).
* [options.f90](https://github.com/cngilbreth/optionsf90) - 现代 Fortran 的选项和输入处理.

## Compiling and building
*用于编译和构建 Fortran 项目的库.*

* [FoBiS](https://github.com/szaghi/FoBiS)  - 穷人的 Fortran 建筑系统. 用于自动构建现代 Fortran 项目的 KISS 工具.

## Preprocessor
*用于条件编译的库、用于代码简化的宏以及包含其他源文件、模板系统.*

* [Blockit/PyF95++](http://blockit.sourceforge.net/)  - 一个相当简单的 Python 框架，用于将您的代码（或任何文本文件）解析为嵌套块.  BlockIt 框架已经用于为 Fortran 95/2003 语言创建模板功能以及一些语言扩展.
* [PreForM](https://github.com/szaghi/PreForM) - Fortran 穷人的预处理器.

## Automatic documentation
*用于构建文档的库.*

* [FORD](https://github.com/cmacmackin/ford) - 现代 Fortran 程序的自动文档生成器.

## Computational Fluid Dynamics
*CFD 计算库*

* [OFF](https://github.com/szaghi/OFF/tree/testing) - 开源有限体积流体动力学代码.

## Docker

* [Unoficial Image](https://hub.docker.com/r/baekjoon/onlinejudge-fortran/) - @baekjoon 提供的 docker 图像

## Web

* [Fortran Machine](https://github.com/mapmeld/fortran-machine) - 用 Fortran 90 编写的 MVC 网络堆栈

## Resources
用于提高 Fortran 开发技能和知识的各种资源，例如书籍、网站和文章.

## Fortran Websites

* [The Fortran Company](https://www.fortran.com/) - FORTRAN 编程语言的主页.
* [Fortran Dev](https://fortrandev.wordpress.com/) - Fortran 开发博客.
* [Fortran WIKI](http://fortranwiki.org/fortran/show/HomePage) - 一个讨论 Fortran 编程语言和科学计算各个方面的开放场所.

## Fortran Videos

* [GNU FORTRAN Lesson 1](https://www.youtube.com/watch?v=qUy8M10uZRU) - 关于 Fortran 编程语言的视频.

## Other Awesome Lists

其他非常棒的列表可以在 [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) 列表.

## Contributing

随时欢迎您的贡献！ 请提交拉取请求或创建问题以将新框架、库或软件添加到列表中. 不要提交在过去 6 个月内没有更新或不是很棒的项目.
