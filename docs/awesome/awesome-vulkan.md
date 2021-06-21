<div class="github-widget" data-repo="vinjn/awesome-vulkan"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Vulkan [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="https://raw.githubusercontent.com/SaschaWillems/Vulkan/master/images/vulkanlogoscene.png" alt="Vulkan demo scene" height="256px">

精选的 Vulkan 库、调试器和资源的精选列表. 灵感来自 [awesome-opengl](https://github.com/eug/awesome-opengl) 和其他很棒的-...东西.

* **[Hardware Support](#hardware-support)**
* **[SDK](#sdk)**
* **[IHV Document](#document)**
* **[Tutorial](#tutorial)**
* **[Apps](#apps)**
* **[Samples](#samples)**
* **[Libraries](#libraries)**
* **[Bindings](#bindings)**
* **[Tools](#tools)**
* **[Books](#books)**
* **[Khronos](#khronos)**
* **[Community](#community)**

## Hardware Support
*  [gpuinfo](http://vulkan.gpuinfo.org/) - Sascha Willems 的火山硬件数据库
*  [Khronos](https://www.khronos.org/vulkan)
*  [NVIDIA](https://developer.nvidia.com/Vulkan)
    *  [Driver for Desktop](https://developer.nvidia.com/vulkan-driver)
    *  [Driver for Android](https://developer.nvidia.com/vulkan-android)
    *  [Driver for Linux for Tegra (L4T)](https://developer.nvidia.com/embedded/vulkan)
*  [AMD](http://www.amd.com/en-gb/innovations/software-technologies/technologies-gaming/vulkan)
    *  [Open-source Driver](https://github.com/GPUOpen-Drivers/AMDVLK)
*  [Imagination](https://www.imgtec.com/developers/powervr-sdk-tools/)
* 英特尔
    *  [Open-source Driver](https://01.org/linuxgraphics/blogs/jekstrand/2016/open-source-vulkan-drivers-intel-hardware/)
    *  [Driver for Windows](https://software.intel.com/en-us/blogs/2016/03/14/new-intel-vulkan-beta-1540204404-graphics-driver-for-windows-78110-1540)
*  [Qualcomm](https://developer.qualcomm.com/software/adreno-gpu-sdk/gpu)
* 手臂
    *  [Mali GPU Best Practices](https://developer.arm.com/solutions/graphics/developer-guides/mali-gpu-best-practices)

## SDK
*  [For Windows & Linux](https://vulkan.lunarg.com/signin)
*  [For Android](https://developer.android.com/ndk/guides/graphics/index.html)

## Document
*  [AMD](http://gpuopen.com/tag/vulkan/)
    *  [Vulkan barriers explained](http://gpuopen.com/vulkan-barriers-explained/)
    *  [Vulkan Fast Paths](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/VulkanFastPaths.pdf)
    *  [Let Your Game Shine – Optimizing DirectX 12 and Vulkan Performance with AMD CodeXL	](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/Let_your_game_shine_optimizing_DirectX-12_and_Vulkan-performance_with_AMD_CodeXL.pdf)
    *  [D3D12 & Vulkan: Lessons Learned	 ](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/d3d12_vulkan_lessons_learned.pdf)
    *  [Say Hello to a New Rendering API in Town!](http://gpuopen.com/say-hello/)
    *  [Vulkan Renderpasses](http://gpuopen.com/vulkan-renderpasses/)
    *  [Performance tweets series: Barriers, fences, synchronization](http://gpuopen.com/performance-tweets-series-barriers-fences-synchronization/)
    *  [Using the Vulkan™ Validation Layers](http://gpuopen.com/using-the-vulkan-validation-layers/)
    *  [Most common mistakes in Vulkan apps](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/05/Most-common-mistakes-in-Vulkan-apps.pdf)
	*  [Vulkan Device Memory](http://gpuopen.com/vulkan-device-memory/)
*  [NVIDIA](https://developer.nvidia.com/taxonomy/term/586)
    * [Vulkan Device-Generated Commands](https://developer.nvidia.com/device-generated-commands-vulkan)
    * [Getting Vulkan Ready For VR](https://developer.nvidia.com/getting-vulkan-ready-vr)
    * [GPU-Driven Rendering](http://on-demand.gputechconf.com/gtc/2016/presentation/s6138-christoph-kubisch-pierre-boudier-gpu-driven-rendering.pdf)
    * [GDC 16 - High-performance, Low-Overhead Rendering with OpenGL and Vulkan](http://developer.download.nvidia.com/gameworks/events/GDC2016/mschott_lbishop_gl_vulkan.pdf)
    * [GDC 16 - Vulkan and NVIDIA – The Essentials](http://developer.download.nvidia.com/gameworks/events/GDC2016/Vulkan_Essentials_GDC16_tlorach.pdf)
    * [Engaging the Voyage to Vulkan](https://developer.nvidia.com/engaging-voyage-vulkan)
    * [Vulkan Shader Resource Binding](https://developer.nvidia.com/vulkan-shader-resource-binding)
    * [Vulkan Memory Management](https://developer.nvidia.com/vulkan-memory-management)
    * [OpenGL like Vulkan](https://developer.nvidia.com/opengl-vulkan)
    * [Transitioning from OpenGL to Vulkan](https://developer.nvidia.com/transitioning-opengl-vulkan)
    * [Siggraph 15 talk - Vulkan on NVIDIA GPUs](http://on-demand.gputechconf.com/siggraph/2015/presentation/SIG1501-Piers-Daniell.pdf)
*  [Arm](https://developer.arm.com/solutions/graphics/apis/vulkan)
    * [Vulkan Best Practice for Mobile Developers Tutorials](https://github.com/ARM-software/vulkan_best_practice_for_mobile_developers)
    * [Vulkan's Key Features on Arm Architecture](https://developer.arm.com/-/media/Files/pdf/graphics-and-multimedia/Vulkan%20API%20key%20features%20on%20ARM%20architecture.pdf)
    * [Porting a Graphics Engine to the Vulkan API](https://community.arm.com/groups/arm-mali-graphics/blog/2016/02/16/porting-a-graphics-engine-to-the-vulkan-api)
    * [Get Your Engine Ready for Vulkan on Mobile](https://developer.arm.com/-/media/Files/pdf/graphics-and-multimedia/Get%20Your%20Engine%20Ready%20for%20Vulkan%20on%20Mobile.pdf)
    * [Multi-Threading in Vulkan](https://community.arm.com/groups/arm-mali-graphics/blog/2016/04/19/massively-multi-thread-for-vulkan)
    * [Mali Vulkan SDK Tutorials](https://developer.arm.com/products/software/mali-sdks/vulkan) 和 [Slides](https://developer.arm.com/graphics/vulkan/vulkan-tutorials)
* 英特尔
    * [API without Secrets: Introduction to Vulkan](https://github.com/GameTechDev/IntroductionToVulkan) [[LICENSE](https://github.com/GameTechDev/IntroductionToVulkan/blob/master/license.txt)]
        * [Part 1: The Beginning](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-1)
        * [Part 2: Swap Chain](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-2)
        * [Part 3: First Triangle](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-3)
        * [Part 4: Vertex Attributes](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-4)
* [Imagination](http://blog.imgtec.com/tag/vulkan)
    * [Efficient Rendering with Vulkan on PowerVR](https://imagination-technologies-cloudfront-assets.s3.amazonaws.com/idc-docs/gdc16/6_Efficient%20rendering%20with%20Vulkan%20on%20PowerVR.pdf)
    * [Migrating to Vulkan with the New PowerVR Graphics Framework](https://www.imgtec.com/webinar/migrating-to-vulkan-with-the-powervr-framework/)
    * [Migrating from OpenGLES to Vulkan](https://www.imgtec.com/downloads/download-info/migrating-from-opengl-es-to-vulkan/)
* 三星
    * [Siggraph 2016 - Best Practices for Mobile](https://community.arm.com/cfs-file/__key/telligent-evolution-extensions-calendar-calendarfiles/00-00-00-00-05/2_2D00_mmg_2D00_siggraph2016_2D00_best_2D00_practice_2D00_andrew.pdf)
    * [Vulkan Usage Recommencation](https://developer.samsung.com/game/usage) （手机）
* 史诗
    * [Efficient use of Vulkan on UE4 Mobile](https://community.arm.com/cfs-file/__key/telligent-evolution-extensions-calendar-calendarfiles/00-00-00-00-05/6_2D00_mmg_2D00_siggraph2016_2D00_vulkan_2D00_smedis.pdf)
* 赫罗诺斯
   * [Vulkan Guide](https://github.com/KhronosGroup/Vulkan-Guide)
* [LunarG](https://lunarg.com)
    * [Vulkan SDK](https://vulkan.lunarg.com/)
    * [Vulkan SDK Version Compatibility](https://www.lunarg.com/news-insights/white-papers/vulkan-sdk-version-compatibility/)
    * [Introducing the New Vulkan Configurator](https://www.lunarg.com/news-insights/white-papers/vulkan-validation-layers/)
    * [Unified Validation Layer for Vulkan](https://www.lunarg.com/news-insights/white-papers/unified-validation-layer-for-vulkan/)
    * [Vulkan Synchronization Validation Quick Start Guide](https://www.lunarg.com/news-insights/white-papers/vulkan-synchronization-validation-quick-start-guide/)
    * [Guide to Vulkan Synchronization Validation](https://www.lunarg.com/news-insights/white-papers/guide-to-vulkan-synchronization-validation/)
    * [Vulkan GPU-Assisted Validation](https://www.lunarg.com/news-insights/white-papers/vulkan-gpu-assisted-validation/)
    * [Automatic RelaxedPrecision Decoration and Conversion in Spirv-Opt](https://www.lunarg.com/news-insights/white-papers/automatic-relaxedprecision-decoration-and-conversion-in-spirv-opt/)
    * [SPIR-V Legalization and Size Reduction with spirv-opt](https://www.lunarg.com/news-insights/white-papers/spir-v-legalization-and-size-reduction-with-spirv-opt/)
    * [All White Papers](https://www.lunarg.com/vulkan-white-papers/)

## Tutorial
*  [How to Learn Vulkan](https://www.jeremyong.com/c++/vulkan/graphics/rendering/2018/03/26/how-to-learn-vulkan.html) - 关于如何学习 Vulkan 的元帖子
*  [I Am Graphics And So Can You](https://www.fasterthan.life/blog/2017/7/11/i-am-graphics-and-so-can-you-part-1) - 针对图形学习 Vulkan 的新手的博客文章风格教程.
*  [Moving to Vulkan (Khronos UK May16)](https://www.khronos.org/assets/uploads/developers/library/2016-uk-chapter-moving-to-vulkan/Moving-to-Vulkan_Khronos-UK_May16.pdf)
*  [jhenriques's tutorial](http://jhenriques.net/development.html)
*  [Lunarg's tutorial](https://vulkan.lunarg.com/doc/sdk/1.0.26.0/windows/tutorial.html)
*  [Mike Bailey's Vulkan Page](http://web.engr.oregonstate.edu/~mjb/vulkan/)  - 提供广泛的 Vulkan 课程幻灯片.  [CC BY-NC-ND 4.0]
*  [Qualcomm Video Tutorial Series](https://developer.qualcomm.com/software/adreno-gpu-sdk/tutorial-videos) - 更倾向于移动设备的 Vulkan.
*  [Raw Vulkan](https://alain.xyz/blog/raw-vulkan) - 关于如何从头开始编写 Vulkan 应用程序的概述.
* 信号图
    * [An overview of next-generation graphics APIs](http://nextgenapis.realtimerendering.com/) - 涵盖 Vulkan、D3D12 等.
*  [Tutorial by Overv](https://vulkan-tutorial.com/) 和 [its github repository](https://github.com/Overv/VulkanTutorial) .  [CC BY-SA 4.0]
*  [vulkan-sxs](https://github.com/philiptaylor/vulkan-sxs) - 逐步解释 Vulkan API 和 [vulkan-sync](https://github.com/philiptaylor/vulkan-sync)  - 以更精确的形式重新表述 Vulkan 对执行依赖项的要求.  [麻省理工学院]
*  [Vulkan in 30 minutes](https://renderdoc.org/vulkan-in-30-minutes.html) - 博德克.
*  [Vulkan Demos and Tutorials](https://github.com/Z80Fan/VulkanDemos) .  [和]
*  [Vulkan Guide](https://vkguide.dev) .  [和]

## Apps
*  [The Talos Principle](http://www.croteam.com/talos-principle-will-support-vulkan-first-screenshot-released/) - 由 Croteam.
*  [Dota2](https://github.com/ValveSoftware/Dota-2-Vulkan/) - 通过阀门.
*  [Basemark](https://www.basemark.com/blog/basemark-extends-its-benchmarking-lead-with-a-vulkan-performance-test/) - 通过 Basemark.
*  [GFXBench 5](https://kishonti.net/news_single.jsp?id=31133884) - 由基松蒂.
*  [ProtoStar](https://www.unrealengine.com/blog/epic-games-unveils-protostar-at-samsung-galaxy-unpacked) - 由 Epic 提供，使用 Unreal Engine 4 技术构建.
*  [Doom](https://en.wikipedia.org/wiki/Doom_(2016_video_game)) - 通过 id 软件.
*  [vkQuake](https://github.com/Novum/vkQuake)  - 基于 QuakeSpasm 的 Vulkan Quake 端口.  [通用公共许可证]
*  [vkQuake2](https://github.com/kondrak/vkQuake2)  - id Software 的 Quake 2 v3.21 支持 Vulkan（Windows 和 Linux）.  [通用公共许可证]
*  [q2vkpt](https://github.com/cschied/q2vkpt/)  - 实时路径追踪器 VKPT 集成到 q2pro Quake 2 客户端.  [通用]
*  [Linux port of SteamVR](https://github.com/ValveSoftware/SteamVR-for-Linux) - SteamVR 建立在 Vulkan API 之上.
*  [3DMark](https://www.futuremark.com/pressreleases/compare-vulkan-and-directx-12-performance-with-3dmark) - 3DMark API 开销测试.
*  [Q2RTX](https://github.com/NVIDIA/Q2RTX) - NVIDIA 在 Quake II 中实现 RTX 光线追踪. [[LICENSE](https://github.com/NVIDIA/Q2RTX/blob/master/license.txt)]

## Samples
* 赫罗诺斯 [Vulkan samples](https://github.com/KhronosGroup/Vulkan-Samples) [[LICENSE](https://github.com/KhronosGroup/Vulkan-Samples/blob/master/LICENSE)]
* 萨沙·威廉姆斯 [samples](https://github.com/SaschaWillems/Vulkan) 和 [Deferred rendering of Sponza](https://github.com/SaschaWillems/VulkanSponza) 和 his talk of [Khronos_meetup_munich](https://www.saschawillems.de/blog/2016/04/11/khronos-chapter-munich-vulkan-slides/).
*（不完整）Sascha Willems  [samples port](https://github.com/jvm-graphics-labs/Vulkan) 到科特林
* 萨沙·威廉姆斯 [Vulkan-glTF-PBR](https://github.com/SaschaWillems/Vulkan-glTF-PBR)  - 使用 glTF 2.0 模型使用 Vulkan 进行基于物理的渲染.  [麻省理工学院]
*  [Vulkan Best Practice for Mobile Developers Samples](https://github.com/ARM-software/vulkan_best_practice_for_mobile_developers)
* 谷歌
    *  [Android port of LunarG samples](https://github.com/googlesamples/vulkan-basic-samples).
    *  [android tutorials](https://github.com/googlesamples/android-vulkan-tutorials).
*  [nvpro-samples](https://github.com/nvpro-samples) - NVIDIA DesignWorks 示例. [[LICENSE](https://github.com/nvpro-samples/gl_vk_threaded_cadscene/blob/master/LICENSE)]
    *  [gl_vk_chopper](https://github.com/nvpro-samples/gl_vk_chopper) - 简单的 vulkan 渲染示例.
    *  [gl_vk_threaded_cadscene](https://github.com/nvpro-samples/gl_vk_threaded_cadscene) - 使用各种技术渲染 CAD 场景的 OpenGL 和 Vulkan 比较 [the blog](https://developer.nvidia.com/vulkan-opengl-threaded-cad-scene-sample) 关于它.
    *  [gl_vk_bk3dthreaded](https://github.com/nvpro-samples/gl_vk_bk3dthreaded) - 使用“工作线程”渲染 3D 的 Vulkan 示例.
    *  [gl_vk_supersampled](https://github.com/nvpro-samples/gl_vk_supersampled) - Vulkan 示例显示高质量的超采样渲染.
*  [NVIDIA GameWorks Samples](https://github.com/NVIDIAGameWorks/GraphicsSamples) - GameWorks 跨平台图形 API 示例. [[LICENSE](https://github.com/NVIDIAGameWorks/GraphicsSamples/blob/master/license.txt)]
*  [LunarG's Samples](https://github.com/LunarG/VulkanSamples)
*  [vkcube](https://github.com/krh/vkcube) - 来自 krh 的“vkcube”示例，在 X、wayland 和 VT 控制台下使用
drm/kms.
*  [Stardust from Intel](https://github.com/GameTechDev/stardust_vulkan) - The Stardust sample application uses the Vulkan graphics API to efficiently render a cloud of animated particles. [[LICENSE](https://github.com/GameTechDev/stardust_vulkan/blob/master/license.txt)]
*  [Vulkan Quake port based on QuakeSpasm](https://github.com/Novum/vkQuake).
*  [C# Samples](https://github.com/FacticiusVir/SharpVk-Samples) - Overv 教程的端口 [SharpVk](https://github.com/FacticiusVir/SharpVk) [和]
*  [Vulkan-Forward-Plus-Renderer](https://github.com/WindyDarian/Vulkan-Forward-Plus-Renderer)  - VFPR - Vulkan Forward Plus 渲染器.  [和]
*  [Laugh Engine](https://github.com/jian-ru/laugh_engine) - 实时 PBR 渲染器的 Vulkan 实现.
*  [tinyrenderers](https://github.com/chaoticbob/tinyrenderers) - Vulkan 和 D3D12 渲染器的单头实现.
*  [TLVulkanRenderer](https://github.com/trungtle/TLVulkanRenderer)  - 简单的基于 Vulkan 的渲染器，用于我关于实时透明度的硕士论文.  [CC BY-SA 4.0]
*  [Vulkan-Hpp Samples](https://github.com/jherico/Vulkan) - Sascha Willems 使用 Vulkan-Hpp 的优秀 Vulkan 示例的分叉.
*  [SDF Font Demo](https://github.com/kocsis1david/font-demo)  - 通过估计符号距离在 Vulkan 中呈现文本.  [麻省理工学院]
*  [vulkantoy](https://github.com/jpystynen/vulkantoy)  - 带有 Vulkan 的 Shadertoy 图像着色器测试应用程序.  [和]
*  [GL_vs_VK](https://github.com/RippeR37/GL_vs_VK)  - OpenGL 和 Vulkan API 在性能方面的比较.  [麻省理工学院]
*  [Vulkan Basic Graphics Samples](https://github.com/vcoda/basic-graphics-samples) - 使用 Magma 库编写的简单图形示例的集合.
*  [Simple RTX Vulkan raytracing tutorials](https://github.com/iOrange/rtxON) .  [和]
*  [RadX](https://github.com/world8th/RadX) - GPU 上基数排序的专用示例（特别是在 NVIDIA RTX 上）.
*  [Ray Tracing In One Weekend (Vulkan RTX)](https://github.com/GPSnoopy/RayTracingInVulkan) - 使用 Vulkan 和 NVIDIA 的 RTX 扩展实现了 Peter Shirley 的 Ray Tracing In One Weekend.
*  [Gears VK](https://github.com/jeffboody/gearsvk)  - Gears VK 是对 Vulkan/Android/Linux 的著名“齿轮”演示的大量修改端口.  [麻省理工学院]
*  [Hello Triangle](https://github.com/helixd-2k18/VK_KHR_ray_tracing) , 基于 `VK_KHR_ray_tracing` 扩展.  [麻省理工学院]


## Libraries
* 2D
   *  [imgui](https://github.com/ocornut/imgui)  - 即时模式图形用户界面.  [麻省理工学院]
   *  [Skia](https://skia.googlesource.com/skia) - Google 的 2D 图形库有一个 [Vulkan](https://skia.org/user/special/vulkan) [backend](https://github.com/google/skia/tree/master/src/gpu/vk), 在一个跨平台的演示中 [sample application](https://skia.org/user/sample/viewer) 用自己 [window library](https://github.com/google/skia/tree/master/tools/viewer) .  [BSD 3 条款] [website](https://skia.org)
   *  [VKVG](https://github.com/jpbruyere/vkvg) - Vulkan 2D 图形库，API 遵循与 Cairo 图形库相同的模式，但具有新功能.

* 计算
   *  [libvc](https://github.com/alexhultman/libvc) - 用于 C++ 的 Vulkan 计算.  [[LICENSE](https://github.com/alexhultman/libvc/blob/master/LICENSE)]
   *  [Vulkan Kompute](https://github.com/axsaucedo/vulkan-kompute)  - 快速且轻量级的 Vulkan 计算框架，针对高级 GPU 处理用例进行了优化.  [Apache 许可证 2.0]
   *  [ncnn](https://github.com/Tencent/ncnn)  - 具有基于 Vulkan 的 GPU 推理的高性能神经网络推理框架.  [BSD 3 条款]
   *  [vuh](https://github.com/Glavnokoman/vuh)  - 基于 Vulkan 的 C++ GPGPU 计算框架.  [麻省理工学院]
   *  [VkFFT](https://github.com/DTolm/VkFFT) - 高效的 Vulkan FFT 库 [MPL-2.0 许可证]

* 低级
   *  [Vulkan Memory Allocator](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator)  - 易于集成来自 AMD 的 Vulkan 内存分配库.  [麻省理工学院]
      * [VulkanMemoryAllocator-Hpp] (https://github.com/malte-v/VulkanMemoryAllocator-Hpp) - VMA 的 C ++ 绑定，如 Vulkan-HPP
   *  [Fossilize](https://github.com/Themaister/Fossilize)  - 各种持久性 Vulkan 对象类型的序列化格式.  [麻省理工学院]
   *  [vk-bootstrap](https://github.com/charles-lunarg/vk-bootstrap)  - C++ 实用程序库，通过自动创建实例、物理设备、设备和交换链来启动 Vulkan 开发.  [麻省理工学院]
   *  [Google's vulkan-cpp-library](https://github.com/google/vulkan-cpp-library)  - Vulkan 抽象库使用 C++11 实现内存、资源管理、类型和线程安全以及系统独立性.  [阿帕奇]
   *  [FrameGraph](https://github.com/azhirnov/FrameGraph)  - Vulkan 抽象层，将框架表示为任务图.  [BSD 2 条款]
   *  [V-EZ](https://github.com/GPUOpen-LibrariesAndSDKs/V-EZ)  - 针对专业工作站 ISV 的 Vulkan API 的轻量级中间件层.  [麻省理工学院]
   *  [Vookoo](https://github.com/andy-thomason/Vookoo)  - Vookoo 是一组无依赖的实用程序，用于协助构建和更新 Vulkan 图形数据结构.  [麻省理工学院]
   *  [vpp](https://github.com/nyorain/vpp)  - 现代 C++ Vulkan 抽象专注于性能和简单的界面.  [麻省理工学院]
   *  [VulkanSceneGraph](https://github.com/vsg-dev) - Vulkan/C++17 场景图项目，继承 [OpenSceneGraph](http://www.openscenegraph.org).
   *  [VKt/VKh](https://github.com/helixd2s/vkt) 、Vulkan API 的工具和帮助程序，基于并使用 C++20.  [麻省理工学院]
   *  [Vulkan-WSIWindow](https://github.com/renelindsay/Vulkan-WSIWindow)  - 用于创建 Vulkan 窗口和处理输入事件的多平台库.  [Apache 许可证 2.0]

* 框架、引擎、高级渲染
   *  [Falcor](https://github.com/NVIDIAGameWorks/Falcor)  - 来自 NVIDIA 的实时渲染框架，支持 DX12 和 Vulkan.  [BSD 3 条款]
   *  [The-Forge](https://github.com/ConfettiFX/The-Forge)  - DirectX 12、Vulkan、macOS Metal 2 渲染框架.  [Apache 许可证 2.0]
   *  [Diligent Engine](https://github.com/DiligentGraphics/DiligentEngine)  - 现代跨平台低级图形库，支持 OpenGL/GLES、Direct3D11/12 和 Vulkan.  [Apache 许可证 2.0]
   *  [DemoFramework](https://github.com/NXPmicro/gtec-demo-framework) - NXP GTEC C++11 跨平台演示框架，包括大量 Vulkan、OpenGL ES、OpenVX、OpenCL、OpenVG 和 OpenCV 示例. [[BSD-3-clause](https://github.com/NXPmicro/gtec-demo-framework/blob/master/License.md)]
   *  [bgfx](https://github.com/bkaradzic/bgfx#bgfx---cross-platform-rendering-library) - 跨平台、图形 API 不可知、“自带引擎/框架”风格的渲染库. [[BSD-2-clause](https://github.com/bkaradzic/bgfx/blob/master/LICENSE)]
   *  [Cinder](https://github.com/cinder/Cinder) 和 [the story](https://libcinder.org/notes/vulkan) [behind](https://forum.libcinder.org/#Topic/23286000002614007) .  [BSD]
   *  [openFrameworks](https://github.com/openframeworks-vk/openFrameworks)  - 最著名的 C++ 创意编码框架.  [麻省理工学院]
   *  [bsf](https://github.com/GameFoundry/bsf)  - 用于开发实时图形应用程序的现代 C++14 库.  [麻省理工学院]
   *  [glfw](https://github.com/glfw/glfw) 和 [the guide](http://www.glfw.org/docs/3.2/vulkan.html).  [[LICENSE](https://github.com/glfw/glfw/blob/master/LICENSE.md)]
   *  [SDL](https://discourse.libsdl.org/t/sdl-2-0-6-released/23109)  - 在 SDL_vulkan.h 中添加了跨平台 Vulkan 图形支持.  [zlib]
   *  [Acid](https://github.com/Equilibrium-Games/Acid)  - 高速 C++17 Vulkan 游戏引擎.  [麻省理工学院]
   *  [liblava](https://github.com/liblava/liblava)  - 现代 C++ 和易于使用的框架.  [麻省理工学院]
   *  [AMD's Anvil](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil) - Vulkan 的跨平台框架. [[LICENSE](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil/blob/master/LICENSE.txt)]
     * [Introductory Vulkan sample](https://github.com/GPUOpen-LibrariesAndSDKs/HelloVulkan) .  [和]
   *  [Intrinsic Engine](https://github.com/begla/Intrinsic)  - Intrinsic 是基于 Vulkan 的跨平台图形和游戏引擎.  [Apache 许可证 2.0]
   *  [Spectrum](https://github.com/mwalczyk/spectrum_core) - 围绕 Vulkan 的正在进行的框架和抽象层.
   *  [VkHLF](https://github.com/nvpro-pipeline/VkHLF)  - Vulkan 高级框架.  [[许可证]](https://github.com/nvpro-pipeline/VkHLF/blob/master/LICENSE.txt)
   *  [Lugdunum](https://github.com/Lugdunum3D/Lugdunum)  - 使用 Vulkan 和现代 C++14 构建的现代跨平台 3D 渲染引擎.  [麻省理工学院]
   *  [Pumex](https://github.com/pumexx/pumex)  - 实现帧图和简单场景图的跨平台 Vulkan 渲染器. 能够同时在多个表面上渲染 [MIT]
   *  [small3d](https://www.gamedev.net/projects/515-small3d/), 基于 Tiny Vulkan 的 C++ 跨平台游戏开发框架 [BSD 3-clause]
   *  [Logi](https://github.com/UL-FRI-LGM/Logi)  - 轻量级面向对象的 Vulkan 抽象框架.  [BSD 2 条款]
   *  [PowerVR SDK](https://github.com/powervr-graphics/Native_SDK) - C++ 跨平台 3D 图形 SDK，可加快 Vulkan 和 GLES 的开发. [[LICENSE](https://github.com/powervr-graphics/Native_SDK/blob/4.1/LICENSE_POWERVR_SDK.txt)]

* 其他 API 互操作和实现
   *  [visor](https://github.com/baldurk/visor) - Vulkan Ignoble Software Rasterizer. [MIT]
   *  [VulkanOnD3D12](https://github.com/Chabloom/VulkanOnD3D12)  - D3D12 的 Vulkan API.  [Apache 许可证 2.0]
   *  [rostkatze](https://github.com/msiglreith/rostkatze) - 基于 D3D12 的 Vulkan 的 C++ 实现 [Apache 许可证 2.0]
   *  [VK9](https://github.com/disks86/VK9) - 使用 Vulkan 的 Direct3D 9 兼容层
   *  [VUDA](https://github.com/jgbit/vuda)  - 提供 CUDA 运行时 API 接口的仅标头库.  [麻省理工学院]
   *  [clspv](https://github.com/google/clspv)  - OpenCL C 到 Vulkan 计算着色器子集的原型编译器.  [Apache 许可证 2.0]
   *  [MoltenVK](https://github.com/KhronosGroup/MoltenVK/)  - 在 iOS 和 macOS 上运行 Vulkan.  [Apache-2.0]
   *  [Zink](https://gitlab.freedesktop.org/kusma/mesa/tree/zink)  - 在 Vulkan 之上的 OpenGL 实现，是 Mesa 项目的一部分.  [麻省理工学院]
   *  [glo / OpenGL Overload](https://github.com/g-truc/glo) - 基于 Vulkan 的 OpenGL 实现.
   *  [gfx-portability](https://github.com/gfx-rs/portability) - Vulkan Portability 在 Metal 和 D3D12 上的实现，基于 [gfx-rs](https://github.com/gfx-rs/gfx/).

* 光线追踪
   *  [vRt](https://github.com/world8th/vRt)  - 基于 Vulkan API (&gt;=1.1) 的统一光线追踪库.  [LGPL-3.0]
   *  [Quartz](https://github.com/Nadrin/Quartz)  - 基于物理的 Vulkan RTX 路径跟踪器，具有声明性的类 ES7 场景描述语言.  [LGPL-3.0]

* 科学
   *  [datoviz](https://github.com/datoviz/datoviz)  - 使用 Vulkan 实现高性能 GPU 交互式科学数据可视化.  [麻省理工学院]
   *  [iMSTK](https://gitlab.kitware.com/iMSTK/iMSTK)  - 用于使用 Vulkan 和 VTK 后端构建手术模拟的 C++ 工具包.  [Apache 许可证 2.0]
  
* 着色器
   *  [glslang](https://github.com/KhronosGroup/glslang) - 将 glsl 编译为 spirv 的库 [BSD 3-Clause]
   *  [SPIRV-Cross](https://github.com/KhronosGroup/SPIRV-Cross) - 反映 spirv 的库，简化了 Vulkan 管道布局的创建 [Apache-2.0 许可证]

## Bindings
*  [ash](https://github.com/MaikKlein/ash)  Rust 的火山绑定.  [我的]
*  [gfx-rs](https://github.com/gfx-rs/gfx)  - 适用于 Rust 的低开销 Vulkan 式 GPU API.  [Apache 许可证 2.0]
*  [libvulkan.lua](https://github.com/CapsAdmin/ffibuild/blob/master/vulkan/vulkan.lua) - 火山的 Lua 绑定.
*  [dvulkan](https://github.com/ColonelThirtyTwo/dvulkan) - 为 Vulkan 自动生成的 D 绑定.
*  [ErupteD](https://github.com/ParticlePeter/ErupteD) - 另一个为 Vulkan 自动生成的 D 绑定.
*  [flextGL](https://github.com/mosra/flextgl) - 最小的 Vulkan 标头/加载程序生成器和 [the blog post](http://blog.magnum.graphics/hacking/simple-efficient-vulkan-loading-with-flextgl/) 关于它.
*  [Silk.NET](https://github.com/dotnet/Silk.NET) - C# bindings for Vulkan and others. [MIT]
*  [vulkan](https://github.com/expipiplus1/vulkan) - Vulkan 和 Vulkan 内存分配器的 Haskell 绑定 [BSD-3-Clause]
*  [nvk](https://github.com/maierfelix/nvk)  - Vulkan 的 JavaScript 绑定.  [和]
*  [racket-vulkan](https://github.com/zyrolasting/racket-vulkan) - Vulkan 的球拍绑定 [detailed implementation notes](https://sagegerard.com/racket-vulkan-notes-index.html) .  [和]
*  [Vulkan-hpp](https://github.com/KhronosGroup/Vulkan-Hpp) 开源 Vulkan C++ API 源自 NVIDIA 和 [the blog](https://developer.nvidia.com/open-source-vulkan-c-api) 关于它.
*  [VulkanSharp](https://github.com/mono/VulkanSharp) - C# bindings for Vulkan. [MIT]
*  [Vulkano](https://github.com/vulkano-rs/vulkano)  - 围绕 Vulkan API 的安全和丰富的 Rust 包装器.  [麻省理工学院]
*  [LWJGL](https://www.lwjgl.org/)  - 轻量级 Java 游戏库 3 具有 Vulkan 绑定.  [BSD]
*  [SharpVk](https://github.com/FacticiusVir/SharpVk) - C# bindings for Vulkan with Linq-to-SPIR-V & [NuGet package](https://www.nuget.org/packages/SharpVk) .  [和]
*  [vulkan](https://github.com/realitix/vulkan)  - 使用 CFFI 生成的 Vulkan 终极 Python 绑定.  [Apache 许可证 2.0]
*  [vulkan-go](https://github.com/vulkan-go/vulkan)  - 去绑定 Vulkan.  [我的]
*  [PasVulkan](https://github.com/BeRo1985/pasvulkan) - Vulkan 绑定以及 Object Pascal [Zlib] 的高级包装库
*  [vulkan-zig](https://github.com/Snektron/vulkan-zig) - Zig [麻省理工学院] 的火山键合发生器
*  [VK²](https://github.com/kotlin-graphics/vkk), Kotlin Wrapper for Vulkan：代码表达能力和安全性满足图形能力 [Apache License 2.0]


## Tools
*  [Nsight™ Visual Studio Edition 5.2+](https://developer.nvidia.com/nvidia-nsight-visual-studio-edition).
*  [LoaderAndValidationLayers](https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers)  - 来自 KhronosGroup.  [Apache 许可证 2.0]
*  [renderdoc](https://github.com/baldurk/renderdoc)  - baldurk，一个独立的图形调试工具.  [麻省理工学院]
    * [RDCtoVkCpp](https://github.com/azhirnov/RDCtoVkCpp)  - 将 RenderDoc Vulkan 捕获转换为可编译和可执行的 C++ 代码.  [麻省理工学院]
*  [VulkanTools](https://github.com/LunarG/VulkanTools)  - LunarG 的工具，包括图层、`vktrace` 和 `vkreplay`.  [Apache 许可证 2.0]
*  [VKtracer](https://www.vktracer.com) - 适用于 Vulkan 的通用且易于使用的分析器.
*  [CodeXL](https://github.com/GPUOpen-Tools/CodeXL)  - CodeXL 开源.  [麻省理工学院]
*  [Qualcomm Adreno GPU Tools](https://developer.qualcomm.com/software/adreno-gpu-sdk/tools) - 示例、Adreno 推荐层、Adreno GPU 的最佳实践文档.
*  [Qualcomm Snapdragon Profiler](https://developer.qualcomm.com/software/snapdragon-profiler) - 包括 Adreno GPU 的 Vulkan 跟踪和帧捕获.
*  [Arm Mobile Studio](https://www.arm.com/products/development-tools/graphics/arm-mobile-studio) - 包括用于轻松跟踪图形性能问题的 Arm 图形分析器和用于整个系统性能视图的 Arm Streamline 性能分析器，以便快速确定 CPU 和 GPU 上的瓶颈.
*  [Open Capture and Analytics Tool (OCAT)](https://github.com/GPUOpen-Tools/OCAT)  - 为 D3D11、D3D12 和 Vulkan 提供 FPS 叠加和性能测量.  [麻省理工学院]
*  [gapid](https://github.com/google/gapid)  - 图形 API 调试器，可以跟踪和重放 Android OpenGL ES 和 Vulkan 应用程序.  [Apache 许可证 2.0]
*  [Arm - PerfDoc](https://github.com/ARM-software/perfdoc)  - 针对 Mali Application Developer 最佳实践文档的验证层.  [麻省理工学院]
*  [glsl_trace](https://github.com/azhirnov/glsl_trace)  - 用于 Vulkan 和 OpenGL 的着色器调试和分析库.  [麻省理工学院]
*  [MangoHud](https://github.com/flightlessmango/MangoHud)  - Vulkan 和 OpenGL 叠加层，用于监控 FPS、温度、CPU/GPU 负载.  [麻省理工学院]

## Books
* [Introduction to Computer Graphics and the Vulkan API](https://www.amazon.com/Introduction-Computer-Graphics-Vulkan-API/dp/1548616176) 作者：**Kenwright** - 使用 Vulkan API 从基础实用的角度向读者介绍令人兴奋的计算机图形主题.
* [Learning Vulkan](https://www.amazon.com/Learning-Vulkan-Parminder-Singh/dp/1786469804) - 作者：**Parminder Singh** - 使用易于理解的示例开始使用 Vulkan API 及其编程技术.
  * [Book's Examples](https://github.com/PacktPublishing/Learning-Vulkan)
* [Vulkan Cookbook](https://www.amazon.com/Vulkan-Cookbook-Pawel-Lapinski/dp/1786468158)- 作者：**Pawel Lapinski** - 探索各种图形编程和 GPU 计算方法，以充分利用 Vulkan API.
  * [Book's Examples](https://github.com/PacktPublishing/Vulkan-Cookbook)
* [Vulkan Programming Guide](https://www.amazon.com/Vulkan-Programming-Guide-Official-Learning/dp/0134464540) - 作者：**Graham Sellers** 和 **John Kessenich** - 为许多领域介绍了强大的 3D 开发技术.

## Khronos
* 规格
    *  [Vulkan 1.0 Specification](https://www.khronos.org/registry/vulkan/specs/1.0/pdf/vkspec.pdf)
    *  [Vulkan 1.0 Specification with Extensions ](https://www.khronos.org/registry/vulkan/specs/1.0-extensions/pdf/vkspec.pdf)
    *  [Vulkan 1.0 Specification with WSI Extensions](https://www.khronos.org/registry/vulkan/specs/1.0-wsi_extensions/pdf/vkspec.pdf)
    *  [Vulkan 1.1 Specification](https://www.khronos.org/registry/vulkan/specs/1.1/pdf/)
    *  [Vulkan 1.1 Specification with Extensions ](https://www.khronos.org/registry/vulkan/specs/1.1-extensions/pdf/vkspec.pdf)
    *  [Vulkan 1.1 Specification with KHR Extensions](https://www.khronos.org/registry/vulkan/specs/1.1-khr-extensions/pdf/)
    *  [Vulkan 1.2 Specification](https://www.khronos.org/registry/vulkan/specs/1.2/pdf/vkspec.pdf)
    *  [Vulkan 1.2 Specification with Extensions ](https://www.khronos.org/registry/vulkan/specs/1.2-extensions/pdf/vkspec.pdf)
    *  [Vulkan 1.2 Specification with KHR Extensions](https://www.khronos.org/registry/vulkan/specs/1.2-khr-extensions/pdf/vkspec.pdf)
* 快速参考表
    *  [Vulkan 1.0 Quick Reference Sheets](https://www.khronos.org/registry/vulkan/specs/1.0/refguide/Vulkan-1.0-web.pdf)
    *  [Vulkan 1.1 Quick Reference Sheets](https://www.khronos.org/registry/vulkan/specs/1.1/refguide/Vulkan-1.1-web.pdf)
*  [Conformance Tests (CTS)](https://github.com/KhronosGroup/Vulkan-CTS)
* 会议和演讲
    *  [GDC 2016 Presentations](https://www.khronos.org/developers/library/2016-gdc)
    *  [2016 UK Chapter: Moving to Vulkan](https://www.khronos.org/developers/library/2016-uk-chapter-moving-to-vulkan)
    *  [SIGGRAPH 2016 BOF - Vulkan](https://www.youtube.com/watch?v=CsHMiEQgrLA)
    *  [SIGGRPAH 2016 Best Practices Roundtable](https://www.youtube.com/watch?v=owuJRPKIUAg)
    *  [2016 Vulkan DevDay UK](https://www.khronos.org/developers/library/2016-vulkan-devday-uk)
    *  [2016 Vulkan DevDay Seoul](https://www.khronos.org/developers/library/2016-Vulkan-DevU-Seoul)
    *  [2017 Vulkan DevU Vancouver](https://www.khronos.org/developers/library/2017-vulkan-devu-vancouver)
    *  [2017 Vulkan Loader Webinar](https://www.khronos.org/developers/library/2017-vulkan-loader-webinar)
    *  [SIGGRAPH 2017 BOF - Vulkan](https://www.youtube.com/watch?v=Nx0u-9ZwrmQ)
    *  [2018 Vulkan Montreal Dev Day](https://www.khronos.org/developers/library/2018-vulkan-montreal-dev-day)
    *  [2018 Vulkanised!](https://www.khronos.org/developers/library/2018-vulkanised)
    *  [SIGGRAPH 2018 BOF - Vulkan](https://www.youtube.com/watch?v=FCAM-3aAzXg&t=18350s)

## Community
*  [Freenode IRC](http://webchat.freenode.net/?channels=Vulkan)
*  [Google Plus](https://plus.google.com/communities/108983304183191634377)
*  [Khronos Forum](https://forums.khronos.org/forumdisplay.php/114-Vulkan)
*  [Reddit](https://www.reddit.com/r/vulkan/)
*  [Stack Overflow](http://stackoverflow.com/questions/tagged/vulkan)
*  [Discord](https://discord.com/invite/tFdvbEj)

## Related lists
*  [awesome](https://github.com/sindresorhus/awesome) - 精选的精彩列表列表.
*  [awesome-opengl](https://github.com/eug/awesome-opengl) - 精选的 OpenGL 库、调试器和资源列表.
*  [gamedev](https://github.com/ellisonleao/magictools) - 很棒的游戏开发列表.
*  [graphics-resources](https://github.com/mattdesl/graphics-resources) - 图形编程资源列表.
*  [awesome-d3d12](https://github.com/vinjn/awesome-d3d12) - 精选的 D3D12 库、调试器和资源的精选列表.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

这项工作已获得许可 [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Contributing
请参阅 [CONTRIBUTING](https://github.com/vinjn/awesome-vulkan/blob/master/CONTRIBUTING.md) 详情.
