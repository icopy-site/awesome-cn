<div class="github-widget" data-repo="onqtam/awesome-cmake"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome CMake [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/onqtam/awesome-cmake/master/cmake-logo.svg" align="right" width="100">](https://cmake.org/)

&gt; 精选列表 [CMake](https://cmake.org/) 脚本、模块、示例和其他

非常欢迎您的贡献（首先见 [https://github.com/onqtam/awesome-cmake/blob/master/CONTRIBUTING.md](https://github.com/onqtam/awesome-cmake/blob/master/CONTRIBUTING.md)).

还有一个文件 [`https://github.com/onqtam/awesome-cmake/blob/master/NonModernCMake.md`](https://github.com/onqtam/awesome-cmake/blob/master/NonModernCMake.md) 其他链接值得一看，但它们使用了被认为是非现代的过时做法 - 比如不使用基于 `target_*` 的依赖管理 - 请参阅 [`#16`](https://github.com/onqtam/awesome-cmake/issues/16) 和 [`#42`](https://github.com/onqtam/awesome-cmake/pull/42) 更多细节.



## Community

* [```#cmake``` on Freenode](http://webchat.freenode.net/?channels=cmake)
* [```/r/cmake``` on Reddit](https://www.reddit.com/r/cmake/)
* [```/r/cpp``` on Reddit](https://www.reddit.com/r/cpp/)
* [Official Discourse Forum](https://discourse.cmake.org/)
* [Stack Overflow](http://stackoverflow.com/questions/tagged/cmake)

## Resources

* [Latest Documentation](https://cmake.org/cmake/help/latest/)
* [FAQ](https://gitlab.kitware.com/cmake/community/-/wikis/FAQ)
* [Wiki](https://gitlab.kitware.com/cmake/community/-/wikis/home)
* [Webinars](https://cmake.org/webinars/)
* [Web Book](https://github.com/ruslo/CGold) - CGold：搭便车者 [Guide](https://cgold.readthedocs.io) 到 CMake.  [```[BSD2]```][BSD-2-Clause]
* [Modern CMake](https://github.com/toeb/moderncmake) - 现代 CMake **PDF** 和创建者的示例 [cmakepp](https://github.com/toeb/cmakepp) .  [```[带]```][带]
* [Tutorial](https://www.siliceum.com/en/blog/post/cmake_01_cmake-basics) - 现代 CMake 教程第 1 部分：CMake 基础知识
* [Article](http://foonathan.net/blog/2016/03/03/cmake-install.html) - 轻松支持 CMake 安装和 find_package().
* [Article](http://foonathan.net/blog/2016/07/07/cmake-dependency-handling.html) - 使用 CMake 和 Git 对 C++ 进行简单的依赖管理.
* [Article](https://steveire.wordpress.com/2016/08/09/opt-in-header-only-libraries-with-cmake/) - 使用 CMake 选择仅包含标头的库.
* [Article](https://rix0r.nl/blog/2015/08/13/cmake-guide/) - 现代 CMake 终极指南.
* [Article](https://web.archive.org/web/20190116071957/http://voices.canonical.com/jussi.pakkanen/2013/03/26/a-list-of-common-cmake-antipatterns/) - 常见 CMake 反模式列表（从 2013 年开始，但仍然相关）.
* [Article](http://preshing.com/20170511/how-to-build-a-cmake-based-project/) - 如何构建基于 CMake 的项目.
* [Article](http://preshing.com/20170522/learn-cmakes-scripting-language-in-15-minutes/) - 在 15 分钟内学习 CMake 的脚本语言.
* [Article](http://aosabook.org/en/cmake.html) - CMake 的架构.
* [Lecture](https://www.youtube.com/watch?v=bsXLMQ6WgIk) - Effective CMake - Daniel Pfeifer，C++Now 2017.
* [Article](https://devblogs.nvidia.com/parallelforall/building-cuda-applications-cmake/) - 使用 CMake 构建跨平台 CUDA 应用程序.
* [Tutorial](https://github.com/Wigner-GPU-Lab/Teaching/tree/master/CMake) - 了解 CMake 的分步指南.
* [Article + Lecture](https://steveire.wordpress.com/2017/11/05/embracing-modern-cmake/) - 拥抱现代 CMake - 斯蒂芬凯利.
* [Lecture](https://www.youtube.com/watch?v=eC9-iRN2b04) - 用于模块化设计的现代 CMake - Mathieu Ropert，CppCon 2017.
* [Article](https://pabloariasal.github.io/2018/02/19/its-time-to-do-cmake-right/) - 是时候做正确的 CMake（关于 CMake 的最佳文章之一）.
* 文章 - 关于 CMake 的系列文章 - Martin Hořeňovský 撰写
    * [Basic CMake usage](https://codingnest.com/basic-cmake/).
    * [Basic CMake, part 2: libraries](https://codingnest.com/basic-cmake-part-2/).
* [Lecture](https://www.youtube.com/watch?v=jt3meXdP-QI) - CMake 简介 - Florent Castelli，C++ 瑞典 2018.
* [Article](http://bastian.rieck.me/blog/posts/2018/cmake_tips/) - 一些不错且准确的 CMake 技巧.
* [Article](http://unclejimbo.github.io/2018/06/08/Modern-CMake-for-Library-Developers/) - 图书馆开发人员的现代 CMake.
* [Article](https://gist.github.com/mbinna/c61dbb39bca0e4fb7d1f73b0d66a4fd1) - Effective Modern CMake：最佳实践的精彩总结 - Manuel Binna 着.
* [Book](https://crascit.com/professional-cmake/) - 专业 CMake：实用指南（付费）.
* [Book](https://leanpub.com/effective-cmake) - Effective CMake：编写更好 CMake 的实用建议（尚未完全编写）.
* [Web Book](https://cliutils.gitlab.io/modern-cmake/) - 现代 CMake 简介.
* [YouTube Series](https://vector-of-bool.github.io/2018/08/12/cmake-good.html)  - 如何使 CMake 好.  [```[CC0-1.0]```][CC0-1.0]
* [Lecture](https://www.youtube.com/watch?v=y7ndUhdQuU8) - 更现代的 CMake ([slides & examples](https://github.com/Bagira80/More-Modern-CMake)) - Deniz Bahadir，会议 C ++ 2018.
* [Lecture](https://www.youtube.com/watch?v=y9kSr5enrSk)  - 不好了！ 更现代的 CMake ([slides](https://github.com/Bagira80/More-Modern-CMake/raw/master/OhNoMoreModernCMake.pdf)) - Deniz Bahadir，会议 C ++ 2019.
* [Article](https://cristianadam.eu/20190223/modifying-the-default-cmake-build-types/)  - 修改默认的 CMake 构建类型/标志、工具链和补丁 - 天哪！  ——克里斯蒂安·亚当.
* [Tutorial](https://github.com/schweitzer/modern-cmake-tutorial) - 如何正确使用现代 CMake 的教程和示例.

## Package Management / Build Systems

* [hunter](https://github.com/ruslo/hunter)  - C++ 的跨平台包管理器（基于 CMake ExternalProject）.  [```[BSD2]```][BSD-2-Clause]
* [cget](https://github.com/pfultz2/cget)  - CMake 包检索. 这可用于下载和安装 CMake 包.  [```[提升]```][提升]
* [cppan](https://cppan.org/)  - C++ Archive Network - 基于 CMake 的 C++ 包管理器，在 C++14 中实现.  [```[APACHE2]```][APACHE2]
* [cpm](https://github.com/iauns/cpm)  - 基于 CMake 和 Git 的 C++ 包管理器.  [```[麻省理工学院]```][麻省理工学院]
* [conan](https://github.com/conan-io/conan)  - 柯南 C++ 包管理器，用 Python 实现并具有 CMake 集成后端.  [```[麻省理工学院]```][麻省理工学院]
* [fips](https://github.com/floooh/fips)  - 用于分布式、多平台 C/C++ 项目的高级构建系统/依赖管理.  [```[麻省理工学院]```][麻省理工学院]
* [Ninja](https://github.com/ninja-build/ninja)  - 构建系统在两个主要方面不同于其他系统：它的输入文件被设计为由更高级别的构建系统（如 CMake）生成，并且它旨在尽可能快地运行构建.  [```[APACHE2]```][APACHE2]
* [vcpkg](https://github.com/Microsoft/vcpkg)  - 获取和构建 C++ 开源库的工具. 在内部使用 CMake 作为构建脚本语言.  [```[麻省理工学院]```][麻省理工学院]
* [pmm](https://github.com/AnotherFoxGuy/pmm)  - PMM 是 CMake 的一个模块，用于管理……包管理器.  [```[麻省理工学院]```][麻省理工学院]
* [cpm](https://github.com/TheLartians/CPM)  - 一个免安装的 CMake + git 依赖管理器.  [```[麻省理工学院]```][麻省理工学院]

## Modules

* [cmake-modules](https://github.com/rpavlik/cmake-modules) - [Ryan Pavlik](https://github.com/rpavlik)的 CMake 模块集合. 有许多查找模块，特别是用于虚拟现实和物理模拟的模块、一些实用程序模块，以及 CMake 本身的一些补丁或解决方法.  [```[提升]```][提升]
* [cmake-modules](https://github.com/bilke/cmake-modules)  - 这是附加 CMake 模块的集合. 他们中的大多数来自瑞安帕夫利克.  [```[提升]```][提升]
* [CMake](https://github.com/Eyescale/CMake) - [Eyescale](https://github.com/Eyescale)的常用 CMake 模块.  [```[BSD3]```][BSD-3-Clause]
* [cmake-modules](https://github.com/jedbrown/cmake-modules)  - 一些科学图书馆的 CMake 模块.  [```[BSD2]```][BSD-2-Clause]
* [cgcmake](https://github.com/chadmv/cgcmake)  - 用于与计算机图形相关的常见应用程序的 CMake 模块.  [```[麻省理工学院]```][麻省理工学院]
* [FindMathematica](https://github.com/sakra/FindMathematica)  - Mathematica 的 CMake 模块.  [```[麻省理工学院]```][麻省理工学院]
* [extra-cmake-modules](https://github.com/KDE/extra-cmake-modules) - [KDE](https://github.com/KDE)的 CMake 的额外模块和脚本.  [```[BSD3]```][BSD-3-Clause]
* [FindICU.cmake](https://github.com/julp/FindICU.cmake)  - 用于查找 Unicode (ICU) 库的国际组件的 CMake 模块.  [```[BSD2]```][BSD-2-Clause]
* [FindTBB](https://github.com/justusc/FindTBB)  - 英特尔线程构建块的 CMake 查找模块.  [```[麻省理工学院]```][麻省理工学院]
* [FindWiX](https://github.com/apriorit/FindWiX) - 用于构建的 CMake 模块 [Windows Installer](https://en.wikipedia.org/wiki/Windows_Installer) 包与 [WiX toolset](http://wixtoolset.org) .  [```[BSD3]```][BSD-3-Clause]
* [FindIDL](https://github.com/apriorit/FindIDL) - 用于构建的 CMake 模块 [IDL](https://docs.microsoft.com/en-us/windows/win32/midl/interface-definition-idl-file) 带有 MIDL 的文件并使用生成 CLR DLL [Tlbimp](https://docs.microsoft.com/en-us/dotnet/framework/tools/tlbimp-exe-type-library-importer) .  [```[带]```][带]
* [cmake-modules](https://github.com/hanjianwei/cmake-modules) - [hanjianwei](https://github.com/hanjianwei)的 CMake 模块集合.  [```[麻省理工学院]```][麻省理工学院]
* [YCM](https://github.com/robotology/ycm) - 额外的 CMake 模块 [Yet Another Robot Platform](https://github.com/robotology/yarp) 和朋友.  [```[BSD3]```][BSD-3-Clause]
* [CMakeCM](https://github.com/AnotherFoxGuy/CMakeCM)  - CMake 社区模块.  ```[无许可证]```
* [Metabench](https://github.com/ldionne/metabench)  - 用于编译时微基准测试的 CMake 模块.  [```[提升]```][提升]
* [Oranges](https://github.com/benthevining/Oranges) - [Ben Vining](https://github.com/benthevining)的 CMake 模块和工具链库 [```[GPL]```][GPL]

## Utility Scripts

它们提供了广泛的功能——从处理编译器标志到使用工具. 有些还包含模块.

* [cotire](https://github.com/sakra/cotire)  - Cotire (compile time reducer) 是一个 CMake 模块，它通过完全自动化的技术作为 C 和 C++ 的预编译头和统一构建来加速基于 CMake 的构建系统的构建过程.  [```[麻省理工学院]```][麻省理工学院]
* [ucm](https://github.com/onqtam/ucm)  - 用于管理编译器/链接器标志、收集源代码、预编译头文件、统一构建等.  [```[麻省理工学院]```][麻省理工学院]
* [cmakepp](https://github.com/toeb/cmakepp)  - CMake 构建系统的增强套件.  [```[麻省理工学院]```][麻省理工学院]
* [sugar](https://github.com/ruslo/sugar) - CMake 工具和示例：收集源文件、警告抑制等 [```[BSD2]```][BSD-2-Clause]
* [DownloadProject](https://github.com/Crascit/DownloadProject)  - CMake 模块，用于在配置时下载外部项目的源代码.  [```[麻省理工学院]```][麻省理工学院]
* [buildem](https://github.com/janelia-flyem/buildem)  - 基于模块化 CMake 的系统，利用 ExternalProject 来简化构建.  [```[许可证]```]（https://github.com/janelia-flyem/buildem/blob/master/LICENSE.txt）
* [coveralls-cmake](https://github.com/JoakimSoderberg/coveralls-cmake)  - 适用于 CMake 的工作服 JSON 覆盖率生成器和上传器.  [```[麻省理工学院]```][麻省理工学院]
* [compatibility](https://github.com/foonathan/compatibility)  - 改进的 cmake-compile-features 版本.  [```[许可证]```]（https://github.com/foonathan/compatibility/blob/master/LICENSE）
* [cmake-modules](https://github.com/Tronic/cmake-modules) - LibFindMacros development repository and other cool CMake stuff. [```[LICENSE]```](https://github.com/Tronic/cmake-modules/blob/master/LibFindMacros.cmake#L2)
* [GreatCMakeCookOff](https://github.com/UCL/GreatCMakeCookOff)  - 这是一个有用的和不太有用的 CMake 配方的存储库.  [```[麻省理工学院]```][麻省理工学院]
* [cppcheck-target-cmake](https://github.com/polysquare/cppcheck-target-cmake)  - CMake 的每个目标 CPPCheck.  [```[麻省理工学院]```][麻省理工学院]
* [clang-tidy-target-cmake](https://github.com/polysquare/clang-tidy-target-cmake)  - 使用 CMake 将 clang-tidy 检查添加到目标.  [```[麻省理工学院]```][麻省理工学院]
* [cmake-unit](https://github.com/polysquare/cmake-unit)  - CMake 的单元测试框架.  [```[麻省理工学院]```][麻省理工学院]
* [cmake-header-language](https://github.com/polysquare/cmake-header-language)  - CMake 宏来确定头文件的语言.  [```[麻省理工学院]```][麻省理工学院]
* [tooling-cmake-util](https://github.com/polysquare/tooling-cmake-util)  - 所有 polysquare CMake 工具的实用程序和通用库.  [```[麻省理工学院]```][麻省理工学院]
* [iwyu-target-cmake](https://github.com/polysquare/iwyu-target-cmake)  - 包含你使用的 CMake 集成.  [```[麻省理工学院]```][麻省理工学院]
* [sanitizers-cmake](https://github.com/arsenm/sanitizers-cmake)  - CMake 模块为二进制目标启用消毒剂.  [```[麻省理工学院]```][麻省理工学院]
* [cmake-precompiled-header](https://github.com/larsch/cmake-precompiled-header) - Visual Studio and GCC precompiled header macro. [```[LICENSE]```](https://github.com/larsch/cmake-precompiled-header/blob/master/PrecompiledHeader.cmake#L31)
* [CMakePCHCompiler](https://github.com/nanoant/CMakePCHCompiler)  - 通过自定义编译器扩展的 CMake 预编译头文件 - 支持重用！  [```[麻省理工学院]```][麻省理工学院]
* [CMake-codecov](https://github.com/RWTH-ELP/CMake-codecov)  - 启用代码覆盖并使用 CMake 目标生成覆盖报告.  [```[GPL]```][GPL]
* [cmake-get](https://github.com/pfultz2/cmake-get)  - 在配置或脚本模式下获取依赖项.  ```[无许可证]```
* [ixm](https://github.com/slurps-mad-rips/ixm)  - 尝试编写 Modern Flexible CMake 时减少 CMake 的痛苦.  [```[麻省理工学院]```][麻省理工学院]
* [CMakeCooking](https://github.com/hakuch/CMakeCooking) - 具有外部依赖项的 CMake 项目的灵活开发环境
 .  [```[APACHE2]```][APACHE2]

## Toolchains

* [dockcross](https://github.com/dockcross/dockcross)  - 在 Docker 镜像中交叉编译工具链.  [```[麻省理工学院]```][麻省理工学院]
* [android-cmake](https://github.com/taka-no-me/android-cmake)  - 适用于 Android NDK 的 CMake 工具链文件和其他脚本.  [```[BSD3]```][BSD-3-Clause]
* [ios-cmake](https://github.com/cristeab/ios-cmake)  - 使用 CMake 进行 iOS 开发的工具链文件和示例.  [```[BSD3]```][BSD-3-Clause]
* [qt-android-cmake](https://github.com/LaurentGomila/qt-android-cmake)  - 用于在没有 QtCreator 的情况下在 Android 上构建和部署基于 Qt 的应用程序.  [```[许可证]```]（https://github.com/LaurentGomila/qt-android-cmake/blob/master/license.txt）
* [mingw-w64-cmake](https://github.com/lachs0r/mingw-w64-cmake)  - 基于 CMake 的 MinGW-w64 Cross Toolchain - 构建 mpv 的 Windows 二进制文件.  [```[ISC]```][ISC]
* [cmake-avr](https://github.com/mkleemann/cmake-avr)  - AVR 的 CMake 工具链.  [```[许可证]```]（https://github.com/mkleemann/cmake-avr/blob/master/LICENSE）
* [arduino-cmake](https://github.com/francoiscampbell/arduino-cmake)  - 这是 Arduino 平台的 CMake 项目设置.  [```[MPL]```][MPL]
* [polly](https://github.com/ruslo/polly)  - 用于跨平台构建和 CI 测试的 CMake 工具链文件和脚本的集合.  [```[BSD2]```][BSD-2-Clause]
* [toolchains](https://github.com/mosra/toolchains)  - 用于与 CMake 的交叉编译. 它们主要用于 ArchLinux.  ```[无许可证]```
* [cmake](https://github.com/staticlibs/cmake/tree/master/toolchains)  - CMake 工具链文件的集合，主要用于静态链接.  [```[APACHE2]```][APACHE2]
* [Arduino-CMake-Toolchain](https://github.com/a9183756-gh/Arduino-CMake-Toolchain)  - 适用于所有官方和第 3 方 Arduino 平台的 CMake 工具链.  [```[麻省理工学院]```][麻省理工学院]

## Examples / Templates

* [cmake-init](https://github.com/cginternals/cmake-init)  - 使用 CMake 进行可靠的跨平台 C++ 项目设置的模板.  [```[许可证]```]（https://github.com/cginternals/cmake-init/blob/master/LICENSE）
* [android-cmake](https://github.com/forexample/android-cmake) - 使用示例 [ruslo/hunter](https://github.com/ruslo/hunter)  Android 应用程序的包管理器.  [```[BSD2]```][BSD-2-Clause]
* [hunter-simple](https://github.com/forexample/hunter-simple) - 使用下载/安装依赖项的示例 [ruslo/hunter](https://github.com/ruslo/hunter) 包管理器.  [```[BSD2]```][BSD-2-Clause]
* [package-example](https://github.com/forexample/package-example) - find_package 的配置模式（例如 [this](http://stackoverflow.com/questions/20746936/cmake-of-what-use-is-find-package-if-you-need-to-specify-cmake-module-path-an) 堆栈溢出问题）.  ```[无许可证]```
* [minimal_cmake_example](https://github.com/krux02/minimal_cmake_example)  - 最小的 CMake 示例，涵盖依赖项和打包.  [```[CC0-1.0]```][CC0-1.0]
* [cmake-example](https://github.com/bast/cmake-example)  - 演示各种 CMake 功能的示例项目.  [```[BSD3]```][BSD-3-Clause]
* [cmake-examples](https://github.com/ttroy50/cmake-examples)  - 教程格式的有用 CMake 示例.  [```[麻省理工学院]```][麻省理工学院]
* [mini-cmake-qt](https://github.com/euler0/mini-cmake-qt)  - Qt 5 项目的最小 CMake 模板.  [```[许可证]```]（https://github.com/euler0/mini-cmake-qt/blob/master/LICENSE）
* [BASIS](https://github.com/cmake-basis/BASIS) - CMake [BASIS](https://cmake-basis.github.io) 使创建协同工作的可共享软件和库变得容易.  [```[BSD2]```][BSD-2-Clause]
* [cpp-boilerplate](https://github.com/Lectem/cpp-boilerplate)  - 旨在成为现代 CMake 和 CI 参考的模板.  [```[麻省理工学院]```][麻省理工学院]
* [how-to-export-cpp-library](https://github.com/robotology/how-to-export-cpp-library)  - 一个与操作系统无关的模板项目，用于导出共享的、静态的或仅标头的 C++ 库，支持 ctest 和 CI，用纯 CMake 编写，并带有逐行教程注释.  [```[麻省理工学院]```][麻省理工学院]
* [modern-cmake-sample](https://github.com/pabloariasal/modern-cmake-sample)  - 使用目标的最佳实践和正确使用 CMake.  ```[无许可证]```
* [CMakeInstallExample](https://github.com/DeveloperPaul123/CMakeInstallExample)  - 使用 Cmake 的 C++ 项目 (Windows) 的安装示例.  ```[无许可证]```
* [cpp14-project-template](https://github.com/arnavb/cpp14-project-template)  - 具有 CI、测试、代码覆盖率、文档和静态分析集成的 C++14 模板.  [```[CC0-1.0]```][CC0-1.0]
* [cmake_templates](https://github.com/acdemiralp/cmake_templates)  - 用于创建 C++ 库和可执行文件（包括柯南）的模板.  ```[无许可证]```
* [cmake_snippets](https://github.com/adishavit/cmake_snippets)  - 简短的可复制粘贴 CMake 片段.  [```[BSD3]```][BSD-3-Clause]
* [cmake-cookbook](https://github.com/dev-cafe/cmake-cookbook)  - 一本包含食谱的巨大 CMake 食谱.  [```[麻省理工学院]```][麻省理工学院]
* [cpp-template](https://github.com/joshpeterson/cpp-template)  - 一个模板 C++ 存储库，使用 CMake 和 Catch.  ```[无许可证]```
* [pitchfork](https://github.com/vector-of-bool/pitchfork)  - 本机 C 和 C++ 项目的一组约定.  [```[麻省理工学院]```][麻省理工学院]
* [cmake-examples](https://github.com/pr0g/cmake-examples)  - 尽可能简单的现代 CMake 项目的集合.  [```[麻省理工学院]```][麻省理工学院]
* [cpp-project](https://github.com/bsamseth/cpp-project)  - C++ 项目的样板 - 测试、CI、覆盖率、文档.  [```[UNLICENSE]```][UNLICENSE]
* [ModernCppStarter](https://github.com/TheLartians/ModernCppStarter) - 使用 CMake、CI、代码覆盖率、clang 格式、可重现的依赖管理、使用测试的现代 C++ 项目的模板 [doctest](https://github.com/onqtam/doctest) 以及更多.  [```[UNLICENSE]```][UNLICENSE]

## Other

* [autocmake](https://github.com/coderefinery/autocmake) - 使用 autocmake.yml 文件 [Autocmake](http://autocmake.readthedocs.io/en/latest/) 将 CMake 构建块组合成 CMake 项目并生成 CMakeLists.txt 以及设置脚本，作为 CMakeLists.txt 的前端.  [```[BSD3]```][BSD-3-Clause]
* [UseLATEX](https://gitlab.kitware.com/kmorel/UseLATEX)  - 收集 CMake 宏以简化构建 LaTeX 文件.  [```[BSD3]```][BSD-3-Clause]
* [scikit-build](https://github.com/scikit-build/scikit-build)  - 改进了 CPython C 扩展的构建系统生成器.  [```[麻省理工学院]```][麻省理工学院]
* [node-cmake](https://github.com/cjntaylor/node-cmake)  - 基于 CMake 的 node.js 原生模块构建系统.  [```[ISC]```][ISC]
* [cmake-font-lock](https://github.com/Lindydancer/cmake-font-lock)  - 对 Emacs 中的 CMake 脚本的高级语法着色支持.  [```[GPL]```][GPL]
* [autovala](https://github.com/rastersoft/autovala)  - 为您的 Vala 项目自动生成 CMake 配置文件的程序.  [```[GPL]```][GPL]
* [catkin](https://github.com/ros/catkin)  - 基于 CMake 的构建系统，用于构建机器人操作系统 (ROS) 中的所有包.  [```[BSD3]```][BSD-3-Clause]
* [suitesparse-metis-for-windows](https://github.com/jlblancoc/suitesparse-metis-for-windows)  - 轻松使用 SuiteSparse+METIS 的 CMake 脚本.  [```[BSD3]```][BSD-3-Clause]
* [osg-3rdparty-cmake](https://github.com/bjornblissing/osg-3rdparty-cmake)  - 用于构建 OpenSceneGraph 第三方库的 CMake 脚本.  ```[混合许可]```
* [cmake-d](https://github.com/dcarp/cmake-d)  - D2 的 CMake.  [```[麻省理工学院]```][麻省理工学院]
* [cmakeprojectmanager2](https://github.com/h4tr3d/cmakeprojectmanager2)  - 增强了 Qt Creator 的 CMake 项目管理器插件.  ```[无许可证]```
* [cmake-lint](https://github.com/richq/cmake-lint)  - 检查 CMake 文件中的编码风格问题.  cmakelint 需要 Python.  [```[APACHE2]```][APACHE2]
* [git-cmake-format](https://github.com/kbenzie/git-cmake-format)  - 将 clang-format 集成到托管在 git 存储库中的 CMake 项目中.  [```[许可证]```]（https://github.com/kbenzie/git-cmake-format/blob/master/license.txt）
* [configure-cmake](https://github.com/nemequ/configure-cmake)  - configure-cmake 是用于基于 CMake 的项目的自动工具样式配置脚本.  [```[CC0-1.0]```][CC0-1.0]
* [cmake-ast](https://github.com/polysquare/cmake-ast)  - 用于将 CMake 文件简化为 AST 的 Python 模块.  [```[麻省理工学院]```][麻省理工学院]
* [cmake-checks-cache](https://github.com/cristianadam/cmake-checks-cache)  - CMake 检查缓存助手模块.  [```[麻省理工学院]```][麻省理工学院]
* [cmake_check](https://github.com/DaelDe/cmake_check)  - CMake 语言的静态分析（linter）（例如强制执行现代 CMake 规则）.  [```[麻省理工学院]```][麻省理工学院]
* [cmake-language-server](https://github.com/regen100/cmake-language-server) - CMake Language Server Protocol Implementation. [```[MIT]```][MIT]
* [cmake-maven-plugin](https://github.com/cmake-maven-project/cmake-maven-project)  - Maven 构建的 CMake 集成.  [```[APACHE2]```][APACHE2]
* [version-from-git](https://github.com/MhmRhm/version-from-git)  - 将 git 信息烘焙到您的二进制文件中.  [```[麻省理工学院]```][麻省理工学院]

## License

This is released under the [**```Creative Commons Attribution 4.0 International```**](http://creativecommons.org/licenses/by/4.0/) 许可证```（CC BY 4.0）```.

[ISC]：https://opensource.org/licenses/ISC
[GPL]：https://www.gnu.org/licenses/gpl-3.0.html
[GPL2]：https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[LGPL]：https://www.gnu.org/licenses/lgpl-3.0.en.html
[麻省理工学院]：https://opensource.org/licenses/MIT
[提升]：http://www.boost.org/LICENSE_1_0.txt
[BSD-2-Clause]：https://opensource.org/licenses/BSD-2-Clause
[BSD-3-Clause]：https://opensource.org/licenses/BSD-3-Clause
[APACHE2]：http://www.apache.org/licenses/LICENSE-2.0
[CC0-1.0]：https://creativecommons.org/publicdomain/zero/1.0/
[MPL]：https://www.mozilla.org/en-US/MPL/2.0/
[无许可证]：https://unlicense.org/
