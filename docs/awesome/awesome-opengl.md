<div class="github-widget" data-repo="eug/awesome-opengl"></div>
## awesome-opengl [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[<img src="https://rawgit.com/eug/awesome-opengl/master/opengl-logo.svg" align="right" width="140">](https://www.opengl.org)

精选的 OpenGL 库、调试器和资源列表.




## Articles

*OpenGL 文章（非教程）*

* [(2014) Ray tracing with OpenGL Compute Shaders](https://github.com/LWJGL/lwjgl3-wiki/wiki/2.6.1.-Ray-tracing-with-OpenGL-Compute-Shaders-%28Part-I%29) 作者 **Kai Burjack** - 关于使用 OpenGL (LWJGL) 进行光线追踪的详细教程系列.
* [(2014) Things that drive me nuts about OpenGL](http://richg42.blogspot.com.au/2014/05/things-that-drive-me-nuts-about-opengl.html) 作者 **Rich Geldreich** - 对 GL API 的建设性（或非建设性）批评.
* [(2011) A trip through the graphics pipeline](https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index) 作者 **Fabian Giesen** - 关于 D3D/OpenGL 图形管道的全面而丰富的系列.
* [(2010) What is OpenGL?](http://duriansoftware.com/joe/An-intro-to-modern-OpenGL.-Chapter-1:-The-Graphics-Pipeline.html) 作者 **Joe Groff** - OpenGL 构建块简介.


## Books

*关于OpenGL的热门书籍*

* [A Trip Down the Graphics Pipeline](http://www.amazon.com/dp/1558603875) 作者 **Jim Blinn** - 包含有关图形管道的丰富信息以及学习计算机图形学核心概念的最佳资源的热门书籍.
* [Computer Graphics](http://www.amazon.com/dp/0321399528) 作者 **John F. Hughes 等人** - 对于任何参与计算机图形算法设计和实现的人来说，计算机图形学确实是必须的. 然而，这不是一本以 OpenGL 为重点的书，而是包含有价值的技术演示.
* [Interactive Computer Graphics](http://www.amazon.com/dp/0132545233) 作者 **Edward Angel 和 Dave Shreiner** - 它提供了几个使用 OpenGL 的示例，它同时涵盖了多个方面，但是如果您正在尝试自己学习 OpenGL，您可能会发现这没有帮助.
* [OpenGL ES 3.0 Programming Guide](http://www.amazon.com/dp/0321933885) 作者：**Dan Ginsburg 等人** - 它以清晰的方式提供了使用 OpenGL ES 3.0 API 的所有必要信息.
* [OpenGL Insights](http://www.amazon.com/dp/1439893764) 作者 **Patrick Cozzi、Christophe Riccio** - 丰富而全面的学习技术和技巧的资源，涵盖了 OpenGL 的几个高级主题.
* [OpenGL Programming Guide](http://www.amazon.com/dp/0321773039) 作者：**Dave Shreiner, et al.** - 它很好地涵盖了基础知识并提供了 API 的清晰参考.
* [OpenGL Shading Language](http://www.amazon.com/dp/0321637631) 作者 **Randi J. Rost, et al.** - 关于着色语言的非常清晰且写得很好的书. 此外，它还提供了几种编写着色器的说明.
* [OpenGL SuperBible](http://www.amazon.com/dp/0321712617) 作者 **Richard S. Wright 等人** - 它涵盖了计算机图形学的基本概念，并提供了使用 OpenGL 的清晰示例. 毫无疑问，这是初学者的必修课.
* [Real-Time Rendering](http://www.amazon.com/dp/1568814240) 作者：**Tomas Akenine-Moller、Eric Haines 和 Naty Hoffman** - 它很好地解释了游戏引擎的概念、游戏客户端编程的基础以及理解 DirectX 和 OpenGL 的必要知识.


## Debug

*调试和分析库*

* [apitrace](http://apitrace.github.io) - 用于跟踪 OpenGL、Direct3D 和其他图形 API 的工具.
* [CodeXL](https://github.com/GPUOpen-Tools/CodeXL) - AMD 的工具套件，包括调试器、分析器和帧/着色器分析.
* [GL-SL Debugger](http://glsl-debugger.github.io) - 用于调试 OpenGL 程序的工具.
* [GLIntercept](https://github.com/dtrebilco/glintercept) - 适用于 Windows 的 OpenGL 函数调用拦截器.
* [Intel-GPA](https://software.intel.com/en-us/gpa) - 英特尔的 OpenGL 图形性能分析器.
* [NVIDIA® Nsight™](https://developer.nvidia.com/nvidia-nsight-visual-studio-edition) - 图形应用程序的开发平台.
* [RenderDoc](https://github.com/baldurk/renderdoc) - RenderDoc 是一个独立的图形调试工具.
* [tracy](https://github.com/wolfpld/tracy) - 用于游戏和其他应用程序的实时远程遥测帧分析器.
* [vogl](https://github.com/ValveSoftware/vogl) - 由 Valve 开发的 OpenGL 捕获和回放调试器.


## GLSL Editors

*在线 GLSL 编辑器*

* [GLSL Sandbox](http://glslsandbox.com) - 片段着色器的在线实时编辑器.
* [GLSLbin](http://glslb.in) - 片段着色器沙箱支持 [glslify](https://github.com/stackgl/glslify).
* [SHDR Editor](http://shdr.bkcore.com) - 实时 GLSL 着色器编辑器、查看器和验证器.
* [Shader Toy](https://www.shadertoy.com) - 最流行的片段着色器实时编辑器.
* [ShaderFrog](http://shaderfrog.com/) - WebGL 着色器编辑器和作曲家

## Libraries

*OpenGL 应用程序的有用库*

* [assimp](https://github.com/assimp/assimp) - 以统一方式导入 3D 模型的便携式库.
* [Bullet](http://bulletphysics.org/wordpress) - 它提供最先进的碰撞检测、软体和刚体动力学.
* [fltk](https://www.fltk.org/) - 可移植地生成 UI 小部件的 C++ 工具包. [LGPLv2](https://www.fltk.org/COPYING.php)
* [freeGLUT](http://freeglut.sourceforge.net) - 允许创建/管理包含 OpenGL 上下文的窗口的成熟库.
* [GLFW](http://www.glfw.org) - 用于使用 OpenGL 上下文创建/交互窗口的现代库.
* [GLFM](https://github.com/brackeen/glfm) - 为移动设备和网络提供 OpenGL ES 上下文和输入事件.
* [glm](http://glm.g-truc.net/0.9.6/index.html) - 基于 GLSL 规范的图形软件数学库.
* [Magnum](https://github.com/mosra/magnum) - 它是现代 OpenGL 的 2D/3D 图形引擎.
* [MathFu](http://google.github.io/mathfu/) - 主要为注重简单性和效率的游戏开发的 C++ 数学库.
* [Newton](http://newtondynamics.com/forum/newton.php) - 这是一种跨平台的逼真物理学.
* [OGLplus](http://oglplus.org) - 在 OpenGL 上实现面向对象外观的库集合.
* [SDL](http://www.libsdl.org) - 旨在提供对多媒体和图形硬件的低级别访问.
* [SFML](http://www.sfml-dev.org) - 简化游戏和多媒体应用程序开发的简单界面.
* [SOIL](http://www.lonesock.net/soil.html)  - 主要用于将纹理上传到 OpenGL 的微型 C 库.  （看 [SOIL2](https://bitbucket.org/SpartanJ/soil2))
* [Pangolin](https://github.com/stevenlovegrove/Pangolin) - 用于管理 OpenGL 显示/交互和抽象视频输入的轻量级便携式快速开发库.
* [morphologica](https://github.com/ABRG-Models/morphologica) - 用于数据可视化的 OpenGL 图形引擎，尤其是数值模拟.


## Profile Loaders

*OpenGL 的配置文件加载器*

* [gl3w](https://github.com/skaslev/gl3w) - 简单的 OpenGL 核心配置文件加载器.
* [glad](https://github.com/Dav1dde/glad) - 基于官方规范的多配置文件加载器生成器.
* [glbindify](https://github.com/nnesse/glbindify) - 为 OpenGL、wgl 和 glX 生成 C 绑定的命令行工具.
* [glbinding](https://github.com/cginternals/glbinding) - 利用 C++11 功能提供类型安全的配置文件加载器.
* [GLEW](http://glew.sourceforge.net) - 用于加载 OpenGL 扩展的成熟跨平台库.


## References

*OpenGL 参考资料*

* [docs.GL](http://docs.gl) - 它是 OpenGL 的替代文档.
* [OpenGL API Tables](http://web.eecs.umich.edu/~sugih/courses/eecs487/common/notes/APITables.xml) - 几个 OpenGL 和 GLSL 版本的 API 的快速参考.
* [OpenGL Cheat Sheet](https://www.khronos.org/files/opengl43-quick-reference-card.pdf) - OpenGL 4.3 命令和语法的快速参考卡.
* [OpenGL Docs](https://www.opengl.org/sdk/docs) - 官方文档网站.
* [OpenGL Wiki](https://www.opengl.org/wiki/Main_Page) - 官方 OpenGL 维基.


## Talks

*OpenGL相关讲座*
* [Approaching Zero Driver Overhead in OpenGL](http://gdcvault.com/play/1020791/) - [Slides](http://www.slideshare.net/CassEveritt/approaching-zero-driver-overhead) - [AMA Reddit](https://www.reddit.com/r/gamedev/comments/21mbo8/we_are_the_authors_of_approaching_zero_driver) 作者 **Cass Everitt、Tim Foley、John McDonald、Graham Sellers** [1:15:54]
* [How Modern OpenGL Can Radically Reduce Driver Overhead](https://www.youtube.com/watch?v=-bCeNzgiJ8I) 作者 **Cass Everitt、John McDonald** [51:13]
* [Moving Your Games to OpenGL](https://www.youtube.com/watch?v=45O7WTc6k2Y) 作者：**Rich Geldreich、Dan Ginsburg、Peter Lohrmann、Jason Mitchell** [54:45]


## Videos

*OpenGL 视频教程*

* [Jamie King](https://www.youtube.com/playlist?list=PLRwVmtr-pp06qT6ckboaOhnm9FxmzHpbY) - 关于现代 OpenGL 和 Qt 的综合教程.
* [MakingGamesWithBen](https://www.youtube.com/playlist?list=PLSPw4ASQYyymu3PfG9gxywSPghnSMiOAW) - 关于 OpenGL 和游戏开发的视频教程（循序渐进）.
* [SIGGRAPH](https://www.youtube.com/user/ACMSIGGRAPH/playlists) - 关于计算机图形学的热门会议.
* [TheChernoProject](https://www.youtube.com/playlist?list=PLlrATfBNZ98foTJPJ_Ev03o2oq3-GGOS2) - C++ 中的 OpenGL 简介
* [thebennybox](https://www.youtube.com/user/thebennybox/playlists) - 关于 OpenGL 和游戏开发的视频教程.
* [ThinMatrix](https://www.youtube.com/user/ThinMatrix/playlists) - 关于 OpenGL 和使用 Java 进行游戏开发的视频教程.
* [sentdex](https://www.youtube.com/playlist?list=PLQVvvaa0QuDdfGpqjkEJSeWKGCP31__wD) - 关于使用 Python 的 OpenGL（即时模式）的视频教程.
* [Sonar Systems](https://www.youtube.com/playlist?list=PLRtjMdoYXLf6zUMDJVRZYV-6g6n62vet8) - 了解新的和现代的 OpenGL 3.0+.

## Websites

*OpenGL教程网站*

* [3D Game Shaders For Beginners](https://github.com/lettier/3d-game-shaders-for-beginners) 通过 **大卫莱蒂尔**
* [Learn OpenGL](https://learnopengl.com) **乔伊·德弗里斯**
* [Learning Modern 3D Graphics Programming](https://bitbucket.org/alfonse/gltut/wiki/Home) 作者：**杰森·麦克森**
* [Light House 3D](http://www.lighthouse3d.com/tutorials/glsl-core-tutorial) 由 **Light House 3D**
* [Modern OpenGL](http://www.tomdalling.com/blog/category/modern-opengl) 通过 **汤姆达林**
* [OpenGL Examples](https://github.com/McNopper/OpenGL) 通过 **诺伯特·诺珀**
* [OpenGL Step by Step](http://ogldev.atspace.co.uk) 来自 **伊泰美日**
* [OpenGL Tutorial](https://open.gl) **亚历山大·奥弗沃德**
* [OpenGL Tutorial](http://antongerdelan.net/opengl/index.html) 作者：**安东·格德兰**
* [OpenGL Tutorial](http://www.opengl-tutorial.org) 作者 **Bonder Wu**
* [OpenGL Tutorial](http://www.songho.ca/opengl) 作者 **Song Ho Ahn**

## Related lists

*类似的精彩列表*
* [awesome](https://github.com/sindresorhus/awesome) - 精选的精选清单.
* [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) - 精选的计算机视觉资源列表.
* [awesome-webgl](https://github.com/sjfricke/awesome-webgl) - 很棒的 WebGL 库、资源等精选列表.
* [awesome-vulkan](https://github.com/vinjn/awesome-vulkan) - 精选的 Vulkan 项目和生态系统列表.
* [gamedev](https://github.com/ellisonleao/magictools) - 关于游戏开发的精彩列表.
* [graphics-resources](https://github.com/mattdesl/graphics-resources) - A list of graphic programming resources.


## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

这项工作已获得许可 [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Contributing
请参见 [CONTRIBUTING](https://github.com/eug/awesome-opengl/blob/master/CONTRIBUTING.md) 了解详情.
