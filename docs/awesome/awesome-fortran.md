<div class="github-widget" data-repo="rabbiabram/awesome-fortran"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Fortran [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/rabbiabram/awesome-fortran.svg?branch=master)](https://travis-ci.org/rabbiabram/awesome-fortran)
 精选的Fortran框架，库和软件的精选列表.  受启发 [awesome-swift](https://github.com/Wolg/awesome-swift) 通过@Wolg.


## Functional Libraries
* [Functional Fortran](https://github.com/wavebitscientific/functional-fortran) -用于现代Fortran的函数式编程.


## Graphics Libraries
*用于图形，图形和GUI的库*

* [DISLIN](https://www.mps.mpg.de/dislin/) -高级图形和用户界面库.
* [f90gl](https://math.nist.gov/f90gl/) -OpenGL的官方NIST Fortran 90绑定的公共领域实现.
* [F03GL](http://www-stone.ch.cam.ac.uk/pub/f03gl/index.xhtml) -到OpenGL库的Fortran 2003界面，以及GLU和GLUT工具包.
* [gtk-fortran](https://github.com/vmagnin/gtk-fortran/wiki) -跨平台库，可使用以下内容构建图形用户界面（GUI） [GTK+](https://www.gtk.org/) .  当与 [Glade](https://glade.gnome.org/) RAD工具.
* [PGPLOT](https://www.astro.caltech.edu/~tjp/pgplot/) -跨平台的科学图形库.
* [VTKFortran](https://github.com/szaghi/VTKFortran) -纯Fortran（2003+）库，用于写入和读取符合VTK标准的数据.

## Math Libs
*用于计算和其他数学运算的库.*

* [BLAS](http://www.netlib.org/blas/) -用于发布库以执行基本线性代数运算（例如矢量和矩阵乘法）的应用程序编程接口标准.
* [CERNLIB](http://cernlib.web.cern.ch/cernlib/) -CERN程序库是在CERN中央计算机上以源代码和目标代码形式维护和提供的大量通用库和模块的集合
* [EISPACK](http://www.netlib.org/eispack/) -用FORTRAN编写的用于矩阵特征值和特征向量数值计算的软件库
* [FGSL](https://www.lrz.de/services/software/mathematik/gsl/fortran/index.html) -可移植的基于对象的Fortran接口 [GNU scientific library](https://www.lrz.de/services/software/mathematik/gsl/)
* [IMSL](https://www.imsl.com/products/imsl-fortran-libraries) -IMSL Fortran数值库是高性能计算商业数学和统计库的标准
* [Lis](https://www.ssisc.org/lis/index.en.html) -线性系统迭代求解器库
* [netCDF](https://github.com/Unidata/netcdf-fortran) -一组软件库和自描述的，与机器无关的数据格式，支持创建，访问和共享面向阵列的科学数据.
* [OpenBLAS](https://github.com/xianyi/OpenBLAS)  -最快的开源BLAS库之一.  几乎与英特尔MKL一样快.

## JSON Manipulation
*使用Fortran语言处理JSON数据的库.

* [FSON](https://github.com/josephalevin/fson) -Fortran 95 JSON解析器.
* [json-fortran](https://github.com/jacobwilliams/json-fortran) -Fortran 2008 JSON API.

## XML Manipulation
*使用Fortran语言处理XML数据的库.

* [fox](https://github.com/andreww/fox) -Fortran XML库
* [xml-fortran](https://sourceforge.net/projects/xml-fortran/) -用于读取和写入XML文件的全Fortran解决方案.

## Date and time manipulation
*使用Fortran语言进行日期和时间处理的库.

* [datetime-fortran](https://github.com/wavebitscientific/datetime-fortran) -一个Fortran 2003日期和时间操作库，以Python的datetime库为模型.

## Testing
*用于测试代码库和生成测试数据的库.

* [FRUIT](https://sourceforge.net/projects/fortranxunit/) -用FORTRAN 95编写的FORTRAN单元测试框架
* [Ftunit](http://flibs.sourceforge.net/ftnunit.html) -Arjen Markus提供的Fortran单元测试框架
* [pFUnit](https://sourceforge.net/projects/pfunit/)  -NASA和NGC TASC的开发人员针对具有MPI扩展的Fortran的单元测试框架.  使用并行代码和面向对象的设计.
* [Vegetables](https://gitlab.com/everythingfunctional/vegetables) -为了使代码更健康，请多吃蔬菜

## Encoding-Decoding
*使用Fortran语言对数据进行编码和解码的库.

* [BeFoR64](https://github.com/szaghi/BeFoR64)  -针对FoRtran贫困人群的Base64编码/解码库.  用于现代（2003+）Fortran项目的base64编码/解码的KISS库.

## Portability enabling
*用于启用代码可移植性的库.*

* [PENF](https://github.com/szaghi/PENF) -用于确保代码可移植性的Pure Fortran（2003+）库.

## Command-Line parsing
*用于解析命令行和构建用户界面的库.

* [FLAP](https://github.com/szaghi/FLAP)  -Fortran命令行参数解析器，适用于穷人.  一个KISS库，用于为现代（2003+）Fortran项目轻松构建漂亮的命令行界面（CLI）.
* [options.f90](https://github.com/cngilbreth/optionsf90) -现代Fortran的选项和输入处理.

## Compiling and building
*用于编译和构建Fortran项目的库.*

* [FoBiS](https://github.com/szaghi/FoBiS)  -Fortran穷人建筑系统.  用于自动构建现代Fortran项目的KISS工具.

## Preprocessor
*用于条件编译的库，用于简化代码的宏以及包括其他源文件，模板系统的*

* [Blockit/PyF95++](http://blockit.sourceforge.net/)  -一个相当简单的Python框架，用于将您的代码（或任何文本文件）解析为嵌套块.  BlockIt框架已经被用来为Fortran 95/2003语言以及一些语言扩展创建模板功能.
* [PreForM](https://github.com/szaghi/PreForM) -Fortran可怜的人的预处理程序.

## Automatic documentation
*用于构建文档的库.*

* [FORD](https://github.com/cmacmackin/ford) -用于现代Fortran程序的自动文档生成器.

## Computational Fluid Dynamics
* CFD计算库*

* [OFF](https://github.com/szaghi/OFF/tree/testing) -开源有限体积流体动力学代码.

## Docker

* [Unoficial Image](https://hub.docker.com/r/baekjoon/onlinejudge-fortran/) -@baekjoon提供的docker映像

## Web

* [Fortran Machine](https://github.com/mapmeld/fortran-machine) -用Fortran 90编写的MVC Web堆栈

## Resources
各种资源，例如书籍，网站和文章，用于提高您的Fortran开发技能和知识.

## Fortran Websites

* [The Fortran Company](https://www.fortran.com/) -FORTRAN编程语言的主页.
* [Fortran Dev](https://fortrandev.wordpress.com/) -Fortran开发博客.
* [Fortran WIKI](http://fortranwiki.org/fortran/show/HomePage) -一个讨论Fortran编程语言和科学计算各个方面的开放场所.

## Fortran Videos

* [GNU FORTRAN Lesson 1](https://www.youtube.com/watch?v=qUy8M10uZRU) -有关Fortran编程语言的视频.

## Other Awesome Lists

其他惊人的清单也可以在 [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) 清单.

## Contributing

 永远欢迎您的贡献！  请提交拉取请求或创建问题以将新的框架，库或软件添加到列表中.  不要提交一个项目，该项目在过去6个月中没有更新或太过出色了.
