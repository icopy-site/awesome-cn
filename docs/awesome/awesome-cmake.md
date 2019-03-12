<div class="github-widget" data-repo="onqtam/awesome-cmake"></div>
## Awesome CMake [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/onqtam/awesome-cmake/master/cmake-logo.svg" align="right" width="100">](https://cmake.org/)

&gt;精选的精选列表 [CMake](https://cmake.org/) 脚本，模块，示例等

非常欢迎你的贡献（首先看看 [https://github.com/onqtam/awesome-cmake/blob/master/CONTRIBUTING.md](https://github.com/onqtam/awesome-cmake/blob/master/CONTRIBUTING.md)).



## Community

* [```#cmake``` on Freenode](http://webchat.freenode.net/?channels=cmake)
* [```/r/cmake``` on Reddit](https://www.reddit.com/r/cmake/)
* [```/r/cpp``` on Reddit](https://www.reddit.com/r/cpp/)
* [Mailing Lists](https://cmake.org/mailing-lists/)
* [Stack Overflow](http://stackoverflow.com/questions/tagged/cmake)

## Resources

* [Latest Documentation](https://cmake.org/cmake/help/latest/)
* [FAQ](https://cmake.org/Wiki/CMake_FAQ)
* [Wiki](https://cmake.org/Wiki/CMake)
* [Webinars](https://cmake.org/webinars/)
* [Web Book](https://github.com/ruslo/CGold) -  CGold：Hitchhiker [Guide](https://cgold.readthedocs.io)  到了CMake.  [```[BSD2]```] [BSD2子句]
* [Modern CMake](https://github.com/toeb/moderncmake) - Modern CMake **PDF** and samples by the creator of [cmakepp](https://github.com/toeb/cmakepp) ，  [```[W]```] [带]
* [Article](http://foonathan.net/blog/2016/03/03/cmake-install.html) - 轻松支持CMake安装和find_package（）.
* [Article](http://foonathan.net/blog/2016/07/07/cmake-dependency-handling.html) - 使用CMake和Git轻松管理C ++.
* [Article](https://steveire.wordpress.com/2016/08/09/opt-in-header-only-libraries-with-cmake/) - 使用CMake选择加入标题的库.
* [Article](https://rix0r.nl/blog/2015/08/13/cmake-guide/) - 现代CMake的终极指南.
* [Article](http://voices.canonical.com/jussi.pakkanen/2013/03/26/a-list-of-common-cmake-antipatterns/) - 常见的CMake反模式列表（从2013年开始，但仍然相关）.
* [Article](http://preshing.com/20170511/how-to-build-a-cmake-based-project/) - 如何构建基于CMake的项目.
* [Article](http://preshing.com/20170522/learn-cmakes-scripting-language-in-15-minutes/) - 在15分钟内学习CMake的脚本语言.
* [Article](http://aosabook.org/en/cmake.html) -  CMake的架构.
* [Lecture](https://www.youtube.com/watch?v=bsXLMQ6WgIk) - 有效的CMake  - 作者：Daniel Pfeifer，C ++ Now 2017.
* [Article](https://devblogs.nvidia.com/parallelforall/building-cuda-applications-cmake/) - 使用CMake构建跨平台CUDA应用程序.
* [Tutorial](https://github.com/Wigner-GPU-Lab/Teaching/tree/master/CMake) - 了解CMake的逐步指南.
* [Article + Lecture](https://steveire.wordpress.com/2017/11/05/embracing-modern-cmake/) - 拥抱现代CMake  - 由Stephen Kelly撰写.
* [Lecture](https://www.youtube.com/watch?v=eC9-iRN2b04) - 模块化设计的现代CMake  - 作者：Mathieu Ropert，CppCon 2017.
* [Article](https://juan-medina.com/2017/07/01/moderncppci/) - 现代C ++ CI（虽然它使用非现代的CMake，如```include_directories（）```.
* [Article](https://pabloariasal.github.io/2018/02/19/its-time-to-do-cmake-right/) - 现在是做正确的时间（关于CMake的最佳文章之一）.
*文章 - 关于CMake的系列文章 - 作者：MartinHořeňovský
    * [Basic CMake usage](https://codingnest.com/basic-cmake/).
    * [Basic CMake, part 2: libraries](https://codingnest.com/basic-cmake-part-2/).
* [Lecture](https://www.youtube.com/watch?v=jt3meXdP-QI) -  CMake简介 - 作者：Florent Castelli，C ++ Sweden 2018.
* [Article](http://bastian.rieck.me/blog/posts/2018/cmake_tips/) - 一些漂亮和准确的CMake技巧.
* [Article](http://unclejimbo.github.io/2018/06/08/Modern-CMake-for-Library-Developers/) - 图书馆开发人员的现代CMake.
* [Article](https://gist.github.com/mbinna/c61dbb39bca0e4fb7d1f73b0d66a4fd1) - 有效的现代CMake：Manuel Binna对大多数良好实践的总结.
* [Book](https://crascit.com/professional-cmake/) - 专业CMake：实用指南（付费）.
* [Book](https://leanpub.com/effective-cmake) - 有效的CMake：写出更好的CMake的实用建议（尚未完全编写）.
* [Web Book](https://cliutils.gitlab.io/modern-cmake/) - 现代CMake简介.
* [YouTube Series](https://vector-of-bool.github.io/2018/08/12/cmake-good.html)   - 如何做好.  [```[CC0-1.0]```] [CC0-1.0]
* [Lecture](https://www.youtube.com/watch?v=y7ndUhdQuU8) - 更现代的CMake  -  Deniz Bahadir，Meeting C ++ 2018.
* [Article](https://cristianadam.eu/20190223/modifying-the-default-cmake-build-types/)   - 修改默认的CMake构建类型/标志，工具链和补丁 - 哦，我的！   - 克里斯蒂安亚当.

## Package Management / Build Systems

* [hunter](https://github.com/ruslo/hunter)   -  C ++的跨平台包管理器（基于CMake ExternalProject）.  [```[BSD2]```] [BSD2子句]
* [cget](https://github.com/pfultz2/cget)   -  CMake包检索.  这可用于下载和安装CMake软件包.  [```[BOOST]```] [BOOST]
* [cppan](https://cppan.org/)   -  C ++ Archive Network  - 基于CMake的C ++ Package Manager，用C ++实现14.  [```[APACHE2]```] [APACHE2]
* [cpm](https://github.com/iauns/cpm)   - 基于CMake和Git的C ++包管理器.  [```[MIT]```] [MIT]
* [conan](https://github.com/conan-io/conan)   -  Conan C ++ Package Manager，用Python实现，具有CMake集成后端.  [```[MIT]```] [MIT]
* [fips](https://github.com/floooh/fips)   - 用于分布式多平台C / C ++项目的高级构建系统/依赖关系管理.  [```[MIT]```] [MIT]
* [Ninja](https://github.com/ninja-build/ninja)   - 在两个主要方面构建与其他系统不同的系统：它旨在使其输入文件由更高级别的构建系统（如CMake）生成，并且旨在尽可能快地运行构建.  [```[APACHE2]```] [APACHE2]
* [vcpkg](https://github.com/Microsoft/vcpkg)   - 获取和构建C ++开源库的工具.  在内部使用CMake作为构建脚本语言.  [```[MIT]```] [MIT]
* [pmm](https://github.com/vector-of-bool/pmm)   -  PMM是CMake的一个模块，用于管理包管理器.  [```[MIT]```] [MIT]

## Modules

* [cmake-modules](https://github.com/rpavlik/cmake-modules) - [Ryan Pavlik](https://github.com/rpavlik) 的CMake模块集合.  有许多查找模块，特别是虚拟现实和物理模拟，一些实用程序模块，以及CMake本身的一些补丁或变通方法.  [```[BOOST]```] [BOOST]
* [cmake-modules](https://github.com/bilke/cmake-modules)   - 这是其他CMake模块的集合.  他们大多数来自瑞安帕夫利克.  [```[BOOST]```] [BOOST]
* [CMake](https://github.com/Eyescale/CMake) - [Eyescale](https://github.com/Eyescale) 常见的CMake模块.  [```[BSD3]```] [BSD3子句]
* [sdl2-cmake-scripts](https://github.com/tcbrindle/sdl2-cmake-scripts)   - 用于查找SDL2，SDL2_image和SDL2_ttf库和标头的CMake脚本.  [```[BSD2]```] [BSD2子句]
* [vfxcmake](https://github.com/nerdvegas/vfxcmake)   -  CMake查找常用vfx软件和常规CMake实用程序代码的模块.  [```[LGPL]```] [LGPL]
* [cmake-modules](https://github.com/jedbrown/cmake-modules)   - 一些科学图书馆的CMake模块.  [```[BSD2]```] [BSD2子句]
* [cgcmake](https://github.com/chadmv/cgcmake)   - 用于与计算机图形相关的常见应用的CMake模块.  [```[MIT]```] [MIT]
* [FindMathematica](https://github.com/sakra/FindMathematica)   -  Mathematica的CMake模块.  [```[W]```] [带]
* [extra-cmake-modules](https://github.com/KDE/extra-cmake-modules) - [KDE](https://github.com/KDE) 用于CMake的额外模块和脚本.  [```[BSD3]```] [BSD3子句]
* [FindICU.cmake](https://github.com/julp/FindICU.cmake)   -  CMake模块，用于查找Unicode（ICU）库的国际组件.  [```[BSD2]```] [BSD2子句]
* [FindTBB](https://github.com/justusc/FindTBB)   - 用于英特尔线程构建模块的CMake查找模块.  [```[MIT]```] [MIT]
* [FindWiX](https://github.com/apriorit/FindWiX) - 用于建筑的CMake模块 [Windows Installer](https://en.wikipedia.org/wiki/Windows_Installer) 包裹 [WiX toolset](http://wixtoolset.org) .  [```[BSD3]```] [BSD3子句]
* [cmake-modules](https://github.com/hanjianwei/cmake-modules) - [hanjianwei](https://github.com/hanjianwei) 的CMake模块集合.  [```[MIT]```] [MIT]
* [YCM](https://github.com/robotology/ycm) - 额外的CMake模块 [Yet Another Robot Platform](https://github.com/robotology/yarp)  和朋友.  [```[BSD3]```] [BSD3子句]
* [CMakeCM](https://github.com/vector-of-bool/CMakeCM)   -  CMake社区模块.  ```[NO LICENSE]```

## Utility Scripts

 它们提供了广泛的功能 - 从处理编译器标志到使用工具.  有些还包含模块.

* [cotire](https://github.com/sakra/cotire)   -  Cotire（编译时缩减器）是一个CMake模块，它通过完全自动化技术作为预编译头和C和C ++的统一构建来加速基于CMake的构建系统的构建过程.  [```[MIT]```] [MIT]
* [ucm](https://github.com/onqtam/ucm) - For managing compiler/linker flags, collecting sources, precompiled headers, unity builds and others. [```[MIT]```][MIT]
* [cmakepp](https://github.com/toeb/cmakepp)   -  CMake构建系统的增强套件.  [```[MIT]```] [MIT]
* [sugar](https://github.com/ruslo/sugar) -  CMake工具和示例：收集源文件，抑制警告等.[```[BSD2]```[BSD-2-Clause]
* [DownloadProject](https://github.com/Crascit/DownloadProject)   -  CMake模块，用于在配置时下载外部项目的源.  [```[MIT]```] [MIT]
* [buildem](https://github.com/janelia-flyem/buildem)   - 基于模块化CMake的系统，利用ExternalProject简化构建.  [```[LICENSE]```]（https://github.com/janelia-flyem/buildem/blob/master/LICENSE.txt）
* [coveralls-cmake](https://github.com/JoakimSoderberg/coveralls-cmake)   - 用于CMake的工作服JSON覆盖生成器和上传器.  [```[MIT]```] [MIT]
* [compatibility](https://github.com/foonathan/compatibility)   - 改进版的cmake-compile-features.  [```[LICENSE]```]（https://github.com/foonathan/compatibility/blob/master/LICENSE）
* [cmake-modules](https://github.com/Tronic/cmake-modules) - LibFindMacros development repository and other cool CMake stuff. [```[LICENSE]```](https://github.com/Tronic/cmake-modules/blob/master/LibFindMacros.cmake#L2)
* [GreatCMakeCookOff](https://github.com/UCL/GreatCMakeCookOff)   - 这是一个有用且不太有用的CMake食谱的存储库.  [```[MIT]```] [MIT]
* [cppcheck-target-cmake](https://github.com/polysquare/cppcheck-target-cmake)   - 针对CMake的每目标CPPCheck.  [```[MIT]```] [MIT]
* [clang-tidy-target-cmake](https://github.com/polysquare/clang-tidy-target-cmake)   - 使用CMake为目标添加铿锵的检查.  [```[MIT]```] [MIT]
* [cmake-unit](https://github.com/polysquare/cmake-unit)   -  CMake的单元测试框架.  [```[MIT]```] [MIT]
* [cmake-header-language](https://github.com/polysquare/cmake-header-language)   -  CMake宏以确定头文件的语言.  [```[MIT]```] [MIT]
* [tooling-cmake-util](https://github.com/polysquare/tooling-cmake-util)   - 所有polysquare CMake工具的实用程序和通用库.  [```[MIT]```] [MIT]
* [iwyu-target-cmake](https://github.com/polysquare/iwyu-target-cmake)   -  CMake集成包括您使用的内容.  [```[MIT]```] [MIT]
* [sanitizers-cmake](https://github.com/arsenm/sanitizers-cmake)   -  CMake模块，为二进制目标启用消毒剂.  [```[MIT]```] [MIT]
* [cmake-precompiled-header](https://github.com/larsch/cmake-precompiled-header) - Visual Studio and GCC precompiled header macro. [```[LICENSE]```](https://github.com/larsch/cmake-precompiled-header/blob/master/PrecompiledHeader.cmake#L31)
* [CMakePCHCompiler](https://github.com/nanoant/CMakePCHCompiler)   - 通过自定义编译器扩展CMake预编译头 - 具有重用支持！  [```[MIT]```] [MIT]
* [CMake-codecov](https://github.com/RWTH-ELP/CMake-codecov)   - 启用代码覆盖并使用CMake目标生成覆盖率报告.  [```[GPL]```] [GPL]
* [leatherman](https://github.com/puppetlabs/leatherman)   -  C ++和CMake实用程序库的集合.  [```[APACHE2]```] [APACHE2]
* [cmake-get](https://github.com/pfultz2/cmake-get)   - 在配置或脚本模式下获取依赖项.  ```[NO LICENSE]```

## Toolchains

* [dockcross](https://github.com/dockcross/dockcross)   - 在Docker镜像中交叉编译工具链.  [```[MIT]```] [MIT]
* [android-cmake](https://github.com/taka-no-me/android-cmake)   - 用于Android NDK的CMake工具链文件和其他脚本.  [```[BSD3]```] [BSD3子句]
* [ios-cmake](https://github.com/cristeab/ios-cmake)   - 使用CMake for iOS开发的工具链文件和示例.  [```[BSD3]```] [BSD3子句]
* [qt-android-cmake](https://github.com/LaurentGomila/qt-android-cmake)   - 在没有QtCreator的情况下在Android上构建和部署基于Qt的应用程序.  [```[LICENSE]```]（https://github.com/LaurentGomila/qt-android-cmake/blob/master/license.txt）
* [mingw-w64-cmake](https://github.com/lachs0r/mingw-w64-cmake)   - 基于CMake的MinGW-w64交叉工具链 - 构建mpv的Windows二进制文件.  [```[ISC]```] [ISC]
* [cmake-avr](https://github.com/mkleemann/cmake-avr)   - 用于AVR的CMake工具链.  [```[LICENSE]```]（https://github.com/mkleemann/cmake-avr/blob/master/LICENSE）
* [arduino-cmake](https://github.com/francoiscampbell/arduino-cmake)   - 这是Arduino平台的CMake项目设置.  [```[MPL]```] [MPL]
* [polly](https://github.com/ruslo/polly)   - 用于跨平台构建和CI测试的CMake工具链文件和脚本的集合.  [```[BSD2]```] [BSD2子句]
* [toolchains](https://github.com/mosra/toolchains)   - 使用CMake进行交叉编译.  它们主要用于ArchLinux.  ```[NO LICENSE]```
* [cmake](https://github.com/staticlibs/cmake/tree/master/toolchains)   - 收集CMake工具链文件，主要用于静态链接.  [```[APACHE2]```] [APACHE2]

## Examples / Templates

* [cmake-init](https://github.com/cginternals/cmake-init)   - 使用CMake进行可靠的跨平台C ++项目设置的模板.  [```[LICENSE]```]（https://github.com/cginternals/cmake-init/blob/master/LICENSE）
* [learning-cmake](https://github.com/Akagi201/learning-cmake)   - 这是一个简单的CMake练习项目，包含一些不同的场景.  [```[GPL2]```] [GPL2]
* [cmake_test](https://github.com/skebanga/cmake_test)   - 使用CMake的小示例项目.  ```[NO LICENSE]```
* [android-cmake](https://github.com/forexample/android-cmake) - 使用示例 [ruslo/hunter](https://github.com/ruslo/hunter)  Android应用程序的包管理器.  [```[BSD2]```] [BSD2子句]
* [hunter-simple](https://github.com/forexample/hunter-simple) - 使用下载/安装依赖项的示例 [ruslo/hunter](https://github.com/ruslo/hunter)  包经理.  [```[BSD2]```] [BSD2子句]
* [weather](https://github.com/ruslo/weather) - 使用示例 [Hunter](http://github.com/ruslo/hunter)  CMake的跨平台包管理器，用于构建使用Boost，CppNetlib.URI，GTest，JSON Spirit的应用程序.  平台：Windows（Visual Studio），Linux，Mac OS X + iOS.  [```[BSD2]```] [BSD2子句]
* [package-example](https://github.com/forexample/package-example) -  find_package的配置模式（示例为 [this](http://stackoverflow.com/questions/20746936/cmake-of-what-use-is-find-package-if-you-need-to-specify-cmake-module-path-an)  Stack Overflow问题）.  ```[NO LICENSE]```
* [CMakeTemplates](https://github.com/OutOfOrder/CMakeTemplates)   - 我用于每个游戏端口的初始CMake模板集.  ```[NO LICENSE]```
* [minimal_cmake_example](https://github.com/krux02/minimal_cmake_example)   - 最小CMake示例，涵盖依赖关系和打包.  [```[CC0-1.0]```] [CC0-1.0]
* [cmake-example](https://github.com/bast/cmake-example)   - 演示各种CMake功能的示例项目.  [```[BSD3]```] [BSD3子句]
* [cmake-examples](https://github.com/ttroy50/cmake-examples)   - 教程格式中有用的CMake示例.  [```[MIT]```] [MIT]
* [cmake-templates](https://github.com/district10/cmake-templates)   - 一些CMake模板.  Qt，Boost，OpenCV，C ++ 11等等[```[MIT]```[MIT]
* [CppProjectTemplate](https://github.com/Barthelemy/CppProjectTemplate)   - 使用CMake，boost和Doxygen的基础但有效的C ++项目.  [```[MIT]```] [MIT]
* [mini-cmake-qt](https://github.com/euler0/mini-cmake-qt)   -  Qt 5项目的最小CMake模板.  [```[LICENSE]```]（https://github.com/euler0/mini-cmake-qt/blob/master/LICENSE）
* [CMake-VisualStudio-Example](https://github.com/cognitivewaves/CMake-VisualStudio-Example) -  Visual Studio开发人员的CMake示例 -  [blog post](http://cognitivewaves.wordpress.com/cmake-and-visual-studio/) .  ```[NO LICENSE]```
* [Cpp-Project-Template](https://github.com/NewProggie/Cpp-Project-Template)   - 包含CMake构建系统的C ++引导程序项目模板.  [```[MIT]```] [MIT]
* [BASIS](https://github.com/cmake-basis/BASIS) -  CMake [BASIS](https://cmake-basis.github.io)  可以轻松创建可共享的可共享软件和库.  [```[BSD2]```] [BSD2子句]
* [OpenGL_CMake_Skeleton](https://github.com/ArthurSonzogni/OpenGL_CMake_Skeleton)   - 使用GLFW，Glew和glm准备使用CMake骨架.  [```[MIT]```] [MIT]
* [coveralls-cmake-example](https://github.com/JoakimSoderberg/coveralls-cmake-example) - 示例项目 [coveralls-cmake](https://github.com/JoakimSoderberg/coveralls-cmake) .  ```[NO LICENSE]```
* [cppbase](https://github.com/kartikkumar/cppbase)   - 用于简单的基于CMake的C ++项目的模板.  [```[MIT]```] [MIT]
* [Arduino-CMake-Template](https://github.com/maxbader/Arduino-CMake-Template)   - 使用CMake进行Arduino开发的起点.  ```[NO LICENSE]```
* [c-template](https://github.com/fletcher/c-template)   - 用于设置交流项目的Boilerplate，包括CuTest，CMake构建设置.  [```[MIT]```] [MIT]
* [cpp_project_template](https://github.com/duckie/cpp_project_template)   - 简单的模板，可以快速启动CMake管理的C ++项目.  [```[MIT]```] [MIT]
* [cpp-boilerplate](https://github.com/Lectem/cpp-boilerplate)   - 模板旨在成为现代CMake和CI的参考.  [```[MIT]```] [MIT]
* [ci_helloworld](https://github.com/ainfosec/ci_helloworld)   - 一个如何为C和C ++设置完整CI环境的简单示例.  [```[MIT]```] [MIT]
* [how-to-export-cpp-library](https://github.com/robotology/how-to-export-cpp-library)   - 与操作系统无关的模板项目，用于导出共享，静态或仅限标头的C ++库，运动ctest和CI支持，使用逐行教程注释以简单的CMake编写.  [```[MIT]```] [MIT]
* [ModernCppCI](https://github.com/LearningByExample/ModernCppCI)   - 使用CI进行现代C ++项目的一个例子（虽然它使用非现代的CMake，如```include_directories（）```.  [```[MIT]```] [MIT]
* [modern-cmake-sample](https://github.com/pabloariasal/modern-cmake-sample)   - 使用目标的最佳做法和正确使用CMake.  ```[NO LICENSE]```
* [CMakeInstallExample](https://github.com/DeveloperPaul123/CMakeInstallExample)   - 使用Cmake的C ++项目（Windows）的安装示例.  ```[NO LICENSE]```
* [cpp14-project-template](https://github.com/arnavb/cpp14-project-template)   - 带有CI，测试，代码覆盖，文档和静态分析集成的C ++ 14模板.  [```[CC0-1.0]```] [CC0-1.0]
* [cmake_templates](https://github.com/acdemiralp/cmake_templates)   - 用于创建C ++库和可执行文件（包括conan）的模板.  ```[NO LICENSE]```
* [cmake_snippets](https://github.com/adishavit/cmake_snippets)   - 短拷贝可粘贴的CMake片段.  [```[BSD3]```] [BSD3子句]
* [cmake-cookbook](https://github.com/dev-cafe/cmake-cookbook)   - 一本充满食谱的巨大CMake食谱.  [```[MIT]```] [MIT]
* [cpp-template](https://github.com/joshpeterson/cpp-template)   - 使用CMake和Catch的模板C ++存储库.  ```[NO LICENSE]```
* [pitchfork](https://github.com/vector-of-bool/pitchfork)   - 一组用于本机C和C ++项目的约定.  [```[MIT]```] [MIT]
* [cleanCppProject](https://github.com/kracejic/cleanCppProject)   - 使用现代CMake的项目模板，包装，测试，文档，静态/动态分析，CI.  [```[MIT]```] [MIT]
* [cmake-examples](https://github.com/pr0g/cmake-examples)   - 尽可能简单的现代CMake项目集合.  [```[MIT]```] [MIT]

## Other

* [autocmake](https://github.com/coderefinery/autocmake) - 使用autocmake.yml文件 [Autocmake](http://autocmake.readthedocs.io/en/latest/)  将CMake构建块组成一个CMake项目并生成CMakeLists.txt以及一个设置脚本，该脚本充当CMakeLists.txt的前端.  [```[BSD3]```] [BSD3子句]
* [UseLATEX](https://gitlab.kitware.com/kmorel/UseLATEX)   - 收集CMake宏以简化构建LaTeX文件.  [```[BSD3]```] [BSD3子句]
* [python-cmake-buildsystem](https://github.com/python-cmake-buildsystem/python-cmake-buildsystem)   -  CPython的替换构建系统.  [```[APACHE2]```] [APACHE2]
* [scikit-build](https://github.com/scikit-build/scikit-build)   - 改进了CPython C扩展的构建系统生成器.  [```[MIT]```] [MIT]
* [protobuf-cmake](https://github.com/jesperes/protobuf-cmake)   - 针对Google Protobufs的CMake构建支持.  [```[BSD3]```] [BSD3子句]
* [node-cmake](https://github.com/cjntaylor/node-cmake)   -  node.js本机模块的基于CMake的构建系统.  [```[ISC]```] [ISC]
* [cmake-font-lock](https://github.com/Lindydancer/cmake-font-lock)   - 为Emacs中的CMake脚本提供高级语法着色支持.  [```[GPL]```] [GPL]
* [stm32-cmake](https://github.com/ObKo/stm32-cmake)   - 用于开发STM32-ST的ARM Cortex-M0（3,4,7）MCU的应用程序.  [```[MIT]```] [MIT]
* [autovala](https://github.com/rastersoft/autovala)   - 为Vala项目自动生成CMake配置文件的程序.  [```[GPL]```] [GPL]
* [catkin](https://github.com/ros/catkin)   - 基于CMake的构建系统，用于构建机器人操作系统（ROS）中的所有软件包.  [```[BSD3]```] [BSD3子句]
* [suitesparse-metis-for-windows](https://github.com/jlblancoc/suitesparse-metis-for-windows)   - 用于无痛使用SuiteSparse + METIS的CMake脚本.  [```[BSD3]```] [BSD3子句]
* [cython-cmake-example](https://github.com/thewtex/cython-cmake-example)   - 使用CMake构建Cython模块的实用程序和示例.  [```[LICENSE]```]（https://github.com/thewtex/cython-cmake-example/blob/master/LICENSE）
* [osg-3rdparty-cmake](https://github.com/bjornblissing/osg-3rdparty-cmake)   - 用于构建OpenSceneGraph第三方库的CMake脚本.  ````[MIXED LICENSE]```
* [cmake-d](https://github.com/dcarp/cmake-d)   - 针对D2的CMake.  [```[MY]```] [MY]
* [cmakeprojectmanager2](https://github.com/h4tr3d/cmakeprojectmanager2)   - 针对Qt Creator的增强型CMake项目管理器插件.  ```[NO LICENSE]```
* [cmake-lint](https://github.com/richq/cmake-lint)   - 检查CMake文件中的编码样式问题.  cmakelint需要Python.  [```[APACHE2]```] [APACHE2]
* [git-cmake-format](https://github.com/kbenzie/git-cmake-format)   - 将clang格式集成到git存储库中托管的CMake项目中.  [```[LICENSE]```]（https://github.com/kbenzie/git-cmake-format/blob/master/license.txt）
* [configure-cmake](https://github.com/nemequ/configure-cmake)   -  configure-cmake是基于CMake的项目的autotools风格的配置脚本.  [```[CC0-1.0]```] [CC0-1.0]
* [tbb](https://github.com/wjakob/tbb)   - 使用CMake构建线程构建块.  [```[APACHE2]```] [APACHE2]
* [sqlite.cmake.build](https://github.com/snikulov/sqlite.cmake.build)   - 用于sqlite合并的CMake脚本.  ```[NO LICENSE]```
* [cmake-ast](https://github.com/polysquare/cmake-ast)   - 用于将CMake文件减少为AST的Python模块.  [```[MIT]```] [MIT]
* [cmake_format](https://github.com/cheshirekow/cmake_format)   -  CMakeLists.txt文件的源代码格式化程序.  [```[GPL]```] [GPL]
* [cmake-checks-cache](https://github.com/cristianadam/cmake-checks-cache)   -  CMake检查缓存助手模块.  [```[MIT]```] [MIT]
* [cmrc](https://github.com/vector-of-bool/cmrc)   - 单个CMake脚本中的资源编译器（将任意数据编译到程序中）.  [```[MIT]```] [MIT]
* [cmake_check](https://github.com/DaelDe/cmake_check)   -  CMake语言的静态分析（linter）（例如，强制执行现代CMake规则）.  [```[MIT]```] [MIT]

## License

这是在下发布 [**```Creative Commons Attribution 4.0 International```**](http://creativecommons.org/licenses/by/4.0/) 许可证```（CC BY 4.0）```.

[ISC]：https：//opensource.org/licenses/ISC
[GPL]：https：//www.gnu.org/licenses/gpl-3.0.html
[GPL2]：https：//www.gnu.org/licenses/old-licenses/gpl-2.0.html
[LGPL]：https：//www.gnu.org/licenses/lgpl-3.0.en.html
[麻省理工学院]：https：//opensource.org/licenses/MIT
[BOOST]：http：//www.boost.org/LICENSE_1_0.txt
[BSD-2-Clause]：https：//opensource.org/licenses/BSD-2-Clause
[BSD-3-Clause]：https：//opensource.org/licenses/BSD-3-Clause
[APACHE2]：http：//www.apache.org/licenses/LICENSE-2.0
[CC0-1.0]：https：//creativecommons.org/publicdomain/zero/1.0/
[MPL]：https：//www.mozilla.org/en-US/MPL/2.0/
