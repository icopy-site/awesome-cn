## Awesome Vulkan [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="https://raw.githubusercontent.com/SaschaWillems/Vulkan/master/images/vulkanlogoscene.png" alt="Vulkan demo scene" height="256px">

 精选的Vulkan库，调试器和资源的精选列表.  灵感来自 [awesome-opengl](https://github.com/eug/awesome-opengl) 和其他很棒的东西.

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
*  [gpuinfo](http://vulkan.gpuinfo.org/) -  Sascha Willems的火山硬件数据库
*  [Khronos](https://www.khronos.org/vulkan)
*  [NVIDIA](https://developer.nvidia.com/Vulkan)
    *  [Driver for Desktop](https://developer.nvidia.com/vulkan-driver)
    *  [Driver for Android](https://developer.nvidia.com/vulkan-android)
    *  [Driver for Linux for Tegra (L4T)](https://developer.nvidia.com/embedded/vulkan)
*  [AMD](http://www.amd.com/en-gb/innovations/software-technologies/technologies-gaming/vulkan)
    *  [Open-source Driver](https://github.com/GPUOpen-Drivers/AMDVLK)
*  [Imagination](https://imgtec.com/tools/powervr-early-access-program/)
*英特尔
    *  [Open-source Driver](https://01.org/linuxgraphics/blogs/jekstrand/2016/open-source-vulkan-drivers-intel-hardware/)
    *  [Driver for Windows](https://software.intel.com/en-us/blogs/2016/03/14/new-intel-vulkan-beta-1540204404-graphics-driver-for-windows-78110-1540)
*  [Qualcomm](https://developer.qualcomm.com/software/adreno-gpu-sdk/gpu)
*  [ARM](http://malideveloper.arm.com/resources/sdks/mali-vulkan-sdk/)

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
* ARM
    * [Porting a Graphics Engine to the Vulkan API](https://community.arm.com/groups/arm-mali-graphics/blog/2016/02/16/porting-a-graphics-engine-to-the-vulkan-api)
    * [Multi-Threading in Vulkan](https://community.arm.com/groups/arm-mali-graphics/blog/2016/04/19/massively-multi-thread-for-vulkan)
    * [Vulkan's Key Features on ARM Architecture](https://developer.arm.com/-/media/Files/pdf/graphics-and-multimedia/Vulkan%20API%20key%20features%20on%20ARM%20architecture.pdf)
    * [Get Your Engine Ready for Vulkan on Mobile](https://developer.arm.com/-/media/Files/pdf/graphics-and-multimedia/Get%20Your%20Engine%20Ready%20for%20Vulkan%20on%20Mobile.pdf)
    * [Mali Vulkan Tutorials](https://arm-software.github.io/vulkan-sdk/tutorials.html) 和 [Slides](https://developer.arm.com/graphics/vulkan/vulkan-tutorials) 来自的Vulkan教程 [Mali Vulkan SDK](https://developer.arm.com/products/software/mali-sdks/vulkan)
*英特尔
    * [API without Secrets: Introduction to Vulkan](https://github.com/GameTechDev/IntroductionToVulkan) [[LICENSE](https://github.com/GameTechDev/IntroductionToVulkan/blob/master/license.txt)]
        * [Part 1: The Beginning](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-1)
        * [Part 2: Swap Chain](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-2)
        * [Part 3: First Triangle](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-3)
        * [Part 4: Vertex Attributes](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-4)
* [Imagination](http://blog.imgtec.com/tag/vulkan)
    * [Efficient Rendering with Vulkan on PowerVR](https://imagination-technologies-cloudfront-assets.s3.amazonaws.com/idc-docs/gdc16/6_Efficient%20rendering%20with%20Vulkan%20on%20PowerVR.pdf)
    *  [Migrating to Vulkan with the New PowerVR Graphics Framework](https://www.imgtec.com/webinar/migrating-to-vulkan-with-the-powervr-framework/)
* Samgsung
    * [Siggraph 2016 - Best Practices for Mobile](https://community.arm.com/cfs-file/__key/telligent-evolution-extensions-calendar-calendarfiles/00-00-00-00-05/2_2D00_mmg_2D00_siggraph2016_2D00_best_2D00_practice_2D00_andrew.pdf)
    * [Vulkan Usage Recommencation](https://developer.samsung.com/game/usage) （适用于手机）
*史诗
    * [Efficient use of Vulkan on UE4 Mobile](https://community.arm.com/cfs-file/__key/telligent-evolution-extensions-calendar-calendarfiles/00-00-00-00-05/6_2D00_mmg_2D00_siggraph2016_2D00_vulkan_2D00_smedis.pdf)

## Tutorial
*  [How to Learn Vulkan](https://www.jeremyong.com/c++/vulkan/graphics/rendering/2018/03/26/how-to-learn-vulkan.html) - 关于如何学习Vulkan的元文章
*  [I Am Graphics And So Can You](https://www.fasterthan.life/blog/2017/7/11/i-am-graphics-and-so-can-you-part-1) - 面向图形学习Vulkan新手的博客文章风格教程.
*  [Moving to Vulkan (Khronos UK May16)](https://www.khronos.org/assets/uploads/developers/library/2016-uk-chapter-moving-to-vulkan/Moving-to-Vulkan_Khronos-UK_May16.pdf)
*  [jhenriques's tutorial](http://jhenriques.net/development.html)
*  [Lunarg's tutorial](https://vulkan.lunarg.com/doc/sdk/1.0.26.0/windows/tutorial.html)
*  [Qualcomm Video Tutorial Series](https://developer.qualcomm.com/software/adreno-gpu-sdk/tutorial-videos) - 更倾向于使用移动设备的Vulkan.
*  [Raw Vulkan](https://alain.xyz/blog/raw-vulkan) - 概述如何从头开始编写Vulkan应用程序.
* Siggraph
    * [An overview of next-generation graphics APIs](http://nextgenapis.realtimerendering.com/) - 涵盖Vulkan，D3D12等
*  [Tutorial by Overv](https://vulkan-tutorial.com/) 和 [its github repository](https://github.com/Overv/VulkanTutorial) .  [CC BY-SA 4.0]
*  [vulkan-sxs](https://github.com/philiptaylor/vulkan-sxs) - 逐步解释Vulkan API [vulkan-sync](https://github.com/philiptaylor/vulkan-sync)   - 以更精确的形式重新描述Vulkan对执行依赖性的要求.  [MIT]
*  [Vulkan in 30 minutes](https://renderdoc.org/vulkan-in-30-minutes.html) - 由baldurk.
*  [Vulkan Demos and Tutorials](https://github.com/Z80Fan/VulkanDemos) ，  [MIT]

## Apps
*  [The Talos Principle](http://www.croteam.com/talos-principle-will-support-vulkan-first-screenshot-released/) - 由Croteam.
*  [Dota2](https://github.com/ValveSoftware/Dota-2-Vulkan/) - 通过Valve.
*  [Basemark](https://www.basemark.com/blog/basemark-extends-its-benchmarking-lead-with-a-vulkan-performance-test/) - 由Basemark提供.
*  [GFXBench 5](https://kishonti.net/news_single.jsp?id=31133884) - 由Kishonti.
*  [ProtoStar](https://www.unrealengine.com/blog/epic-games-unveils-protostar-at-samsung-galaxy-unpacked) - 由Epic构建，采用虚幻引擎4技术构建.
*  [Doom](https://en.wikipedia.org/wiki/Doom_(2016_video_game)） - 由id Software提供.
*  [vkQuake](https://github.com/Novum/vkQuake)   - 基于QuakeSpasm的Vulkan Quake端口.  [GPL]
*  [vkQuake2](https://github.com/kondrak/vkQuake2)   -  id Software的Quake 2 v3.21，支持Vulkan（Windows和Linux）.  [GPL]
*  [q2vkpt](https://github.com/cschied/q2vkpt/)   - 集成到q2pro Quake 2客户端的实时路径跟踪器VKPT.  [GPL]
*  [Linux port of SteamVR](https://github.com/ValveSoftware/SteamVR-for-Linux) -  SteamVR建立在Vulkan API之上.
*  [3DMark](https://www.futuremark.com/pressreleases/compare-vulkan-and-directx-12-performance-with-3dmark) -  3DMark API开销测试.

## Samples
* Sascha Willems [samples](https://github.com/SaschaWillems/Vulkan) 和 [Deferred rendering of Sponza](https://github.com/SaschaWillems/VulkanSponza) 和 his talk of [Khronos_meetup_munich](https://www.saschawillems.de/vulkan/khronosmeetup/#/).
* Sascha Willems [Vulkan-glTF-PBR](https://github.com/SaschaWillems/Vulkan-glTF-PBR)   - 使用glTF 2.0模型使用Vulkan进行基于物理的渲染.  [MIT]
*  [Khronos Samples](https://github.com/KhronosGroup/Vulkan-Samples)
* 谷歌
    *  [Android port of LunarG samples](https://github.com/googlesamples/vulkan-basic-samples).
    *  [android tutorials](https://github.com/googlesamples/android-vulkan-tutorials).
*  [nvpro-samples](https://github.com/nvpro-samples) -  NVIDIA DesignWorks样片. [[LICENSE](https://github.com/nvpro-samples/gl_vk_threaded_cadscene/blob/master/LICENSE)]
    *  [gl_vk_chopper](https://github.com/nvpro-samples/gl_vk_chopper) - 简单的vulkan渲染示例.
    *  [gl_vk_threaded_cadscene](https://github.com/nvpro-samples/gl_vk_threaded_cadscene) -  OpenGL和Vulkan比较使用ve技术和渲染CAD场景 [the blog](https://developer.nvidia.com/vulkan-opengl-threaded-cad-scene-sample) 关于它.
    *  [gl_vk_bk3dthreaded](https://github.com/nvpro-samples/gl_vk_bk3dthreaded) - 使用&#39;工作线程&#39;渲染3D的Vulkan示例.
    *  [gl_vk_supersampled](https://github.com/nvpro-samples/gl_vk_supersampled) -  Vulkan样本显示高质量的超级采样渲染.
*  [NVIDIA GameWorks Samples](https://github.com/NVIDIAGameWorks/GraphicsSamples) -  GameWorks跨平台图形API示例. [[LICENSE](https://github.com/NVIDIAGameWorks/GraphicsSamples/blob/master/license.txt)]
*  [LunarG's Samples](https://github.com/LunarG/VulkanSamples)
*  [vkcube](https://github.com/krh/vkcube) - 来自krh的&#39;vkcube&#39;样本，在X，wayland和VT控制台下工作
drm/kms.
*  [Stardust from Intel](https://github.com/GameTechDev/stardust_vulkan) -  Stardust示例应用程序使用Vulkan图形API有效地渲染动画粒子云. [[LICENSE](https://github.com/GameTechDev/stardust_vulkan/blob/master/license.txt)]
*  [Vulkan Quake port based on QuakeSpasm](https://github.com/Novum/vkQuake).
*  [C# Samples](https://github.com/FacticiusVir/SharpVk-Samples) -  Overv的教程 [SharpVk](https://github.com/FacticiusVir/SharpVk) [MIT]
*  [Vulkan-Forward-Plus-Renderer](https://github.com/WindyDarian/Vulkan-Forward-Plus-Renderer)   -  VFPR  - 火山前锋和渲染器.  [MIT]
*  [Laugh Engine](https://github.com/jian-ru/laugh_engine) -  Vulkan实现实时PBR渲染器.
*  [tinyrenderers](https://github.com/chaoticbob/tinyrenderers) -  Vulkan和D3D12渲染器的单头实现.
*  [TLVulkanRenderer](https://github.com/trungtle/TLVulkanRenderer)   - 基于Vulkan的简单渲染器，用于我的实时透明度硕士论文.  [CC BY-SA 4.0]
*  [Vulkan-Hpp Samples](https://github.com/jherico/Vulkan) - 使用Vulkan-Hpp的Sascha Willems的优秀Vulkan示例.
*  [SDF Font Demo](https://github.com/kocsis1david/font-demo)   - 通过估计签名距离在Vulkan中进行文本渲染.  [MIT]
*  [vulkantoy](https://github.com/jpystynen/vulkantoy)   - 使用Vulkan的Shadertoy图像着色器测试应用程序.  [MIT]
*  [GL_vs_VK](https://github.com/RippeR37/GL_vs_VK)   - 在性能方面比较OpenGL和Vulkan API.  [MIT]
*  [Vulkan Basic Graphics Samples](https://github.com/vcoda/basic-graphics-samples) - 使用Magma库编写的简单图形样本的集合.
*  [Simple RTX Vulkan raytracing tutorials](https://github.com/iOrange/rtxON) ，  [MIT]
*  [RadX](https://github.com/world8th/RadX) -  GPU上基数排序的专用示例（特别是在NVIDIA RTX上）.

## Libraries
*  [Acid](https://github.com/Equilibrium-Games/Acid)   - 高速C ++ 17 Vulkan游戏引擎.  [MIT]
*  [bsf](https://github.com/GameFoundry/bsf)   - 用于开发实时图形应用程序的Modern C ++ 14库.  [MIT]
*  [Cinder](https://github.com/cinder/Cinder) 和 [the story](https://libcinder.org/notes/vulkan) [behind](https://forum.libcinder.org/#Topic/23286000002614007) ，  [BSD]
*  [Diligent Engine](https://github.com/DiligentGraphics/DiligentEngine)   - 一个支持OpenGL / GLES，Direct3D11 / 12和Vulkan的现代跨平台低级图形库.  [Apache许可证2.0]
*  [SDL](https://discourse.libsdl.org/t/sdl-2-0-6-released/23109)   - 在SDL_vulkan.h中添加了跨平台的Vulkan图形支持.  [ZLIB]
*  [DemoFramework](https://github.com/NXPmicro/gtec-demo-framework) - 恩智浦GTEC C ++ 11跨平台演示框架，包括Vulkan，OpenGL ES，OpenVX，OpenCL，OpenVG和OpenCV的大量示例. [[BSD-3-clause](https://github.com/NXPmicro/gtec-demo-framework/blob/master/License.md)]
*  [openFrameworks](https://github.com/openframeworks-vk/openFrameworks)   - 最着名的C ++创意编码框架.  [MIT]
*  [PowerVR SDK](https://github.com/powervr-graphics/Native_SDK) -  C ++跨平台3D图形SDK，加速Vulkan和GLES的开发. [[LICENSE](https://github.com/powervr-graphics/Native_SDK/blob/4.1/LICENSE_POWERVR_SDK.txt)]
*  [glfw](https://github.com/glfw/glfw) 和 [the guide](http://www.glfw.org/docs/3.2/vulkan.html).  [[LICENSE](https://github.com/glfw/glfw/blob/master/LICENSE.md)]
*  [MoltenVK](https://github.com/KhronosGroup/MoltenVK/)   - 在iOS和macOS上运行Vulkan.  [Apache的2.0]
*  [imgui](https://github.com/ocornut/imgui)   - 立即模式图形用户界面.  [MIT]
*  [vuh](https://github.com/Glavnokoman/vuh)   - 基于Vulkan的C ++ GPGPU计算框架.  [MIT]
*  [libvc](https://github.com/alexhultman/libvc) -  Vulkan Compute for C ++.  [[LICENSE](https://github.com/alexhultman/libvc/blob/master/LICENSE)]
*  [AMD's Anvil](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil) -  Vulkan的跨平台框架. [[LICENSE](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil/blob/master/LICENSE.txt)]
    * [Introductory Vulkan sample](https://github.com/GPUOpen-LibrariesAndSDKs/HelloVulkan) ，  [MIT]
*  [Vulkan Memory Allocator](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator)   - 易于集成AMD的Vulkan内存分配库.  [MIT]
*  [V-EZ](https://github.com/GPUOpen-LibrariesAndSDKs/V-EZ)   - 针对Professional Workstation ISV的Vulkan API的轻量级中间件层.  [MIT]
*  [Google's vulkan-cpp-library](https://github.com/google/vulkan-cpp-library)   - 使用C ++ 11进行内存，资源管理，类型和线程安全以及系统独立性的Vulkan抽象库.  [阿帕奇]
*  [Vookoo](https://github.com/andy-thomason/Vookoo)   -  Vookoo是一组无依赖项的实用程序，用于帮助构建和更新Vulkan图形数据结构.  [MIT]
*  [vpp](https://github.com/nyorain/vpp)   - 现代C ++ Vulkan Abstraction专注于性能和简单的界面.  [MIT]
*  [Intrinsic Engine](https://github.com/begla/Intrinsic)   -  Intrinsic是一款基于Vulkan的跨平台图形和游戏引擎.  [Apache许可证2.0]
*  [glo / OpenGL Overload](https://github.com/g-truc/glo) - 在Vulkan之上的OpenGL实现.
*  [Skia](https://skia.googlesource.com/skia) - 谷歌的2D图形库有一个 [Vulkan](https://skia.org/user/special/vulkan) [backend](https://github.com/google/skia/tree/master/src/gpu/vk)，在跨平台演示 [sample application](https://skia.org/user/sample/viewer) 有自己 [window library](https://github.com/google/skia/tree/master/tools/viewer) .  [BSD 3条款] [website](https://skia.org)
*  [Spectrum](https://github.com/mwalczyk/spectrum_core) -  Vulkan周围的工作进度框架和抽象层.
*  [VkHLF](https://github.com/nvpro-pipeline/VkHLF)   -  Vulkan高级框架.  [[LICENSE]]（https://github.com/nvpro-pipeline/VkHLF/blob/master/LICENSE.txt）
*  [VulkanOnD3D12](https://github.com/Chabloom/VulkanOnD3D12)   -  D3D12的Vulkan API.  [Apache许可证2.0]
*  [visor](https://github.com/baldurk/visor)   -  Volcano Ignoble Software Rasterizer.  [MIT]
*  [Lugdunum](https://github.com/Lugdunum3D/Lugdunum)   - 使用Vulkan和现代C ++ 14构建的现代跨平台3D渲染引擎.  [MIT]
*  [Vulkan-WSIWindow](https://github.com/renelindsay/Vulkan-WSIWindow)   - 多平台库，用于创建Vulkan窗口，并处理输入事件.  [Apache许可证2.0]
*  [Falcor](https://github.com/NVIDIAGameWorks/Falcor)   - 来自NVIDIA的实时渲染框架，支持DX12和Vulkan.  [BSD 3条款]
*  [The-Forge](https://github.com/ConfettiFX/The-Forge)   -  DirectX 12，Vulkan，macOS Metal 2渲染框架.  [Apache许可证2.0]
*  [FrameGraph](https://github.com/azhirnov/FrameGraph)   -  Vulkan抽象层，将框架表示为任务图.  [BSD 2条款]
*  [VK9](https://github.com/disks86/VK9) - 使用Vulkan的Direct3D 9兼容层
*  [gfx-rs](https://github.com/gfx-rs/gfx)   -  Rust的高性能无绑定图形API.  [Apache许可证2.0]
*  [vRt](https://github.com/world8th/vRt)   - 基于Vulkan API（&gt; = 1.1）的统一光线跟踪库.  [LGPL-3.0]
*  [rostkatze](https://github.com/msiglreith/rostkatze) - 坐在D3D12上的Vulkan的C ++实现[Apache License 2.0]
*  [Fossilize](https://github.com/Themaister/Fossilize)   - 各种持久性Vulkan对象类型的序列化格式.  [MIT]
*  [Vulkan/VkSceneGraph](https://github.com/vsg-dev) -  Vulkan / C ++ 17场景图项目，继承者 [OpenSceneGraph](http://www.openscenegraph.org).
*  [clspv](https://github.com/google/clspv)   -  OpenCL C子集到Vulkan计算着色器的原型编译器.  [Apache许可证2.0]
*  [Pumex](https://github.com/pumexx/pumex)   - 实现框架图和简单场景图的跨平台Vulkan渲染器.  能够同时在多个表面上渲染[MIT]
*  [VUDA](https://github.com/jgbit/vuda)   -  header-only lib，提供CUDA Runtime API接口.  [MIT]
*  [Zink](https://gitlab.freedesktop.org/kusma/mesa/tree/zink)   - 作为Mesa项目的一部分，Vulkan之上的OpenGL实现.  [无执照]
*  [ncnn](https://github.com/Tencent/ncnn)   - 基于Vulkan的GPU推理的高性能神经网络推理框架.  [BSD 3条款]
## Bindings
*  [libvulkan.lua](https://github.com/CapsAdmin/ffibuild/blob/master/vulkan/vulkan.lua) -  Lua绑定Vulkan.
*  [dvulkan](https://github.com/ColonelThirtyTwo/dvulkan) - 为Vulkan自动生成D绑定.
*  [ErupteD](https://github.com/ParticlePeter/ErupteD) - Another Auto-generated D bindings for Vulkan.
*  [flextGL](https://github.com/mosra/flextgl) - 最小的Vulkan头/装载机生成器和 [the blog post](http://blog.magnum.graphics/hacking/simple-efficient-vulkan-loading-with-flextgl/) 关于它.
*  [Haskell bindings for Vulkan](https://github.com/expipiplus1/vulkan) - [[LICENSE](https://github.com/expipiplus1/vulkan/blob/master/LICENSE)]
*  [Vulkan-hpp](https://github.com/KhronosGroup/Vulkan-Hpp) 开源Vulkan C ++ API源自NVIDIA和 [the blog](https://developer.nvidia.com/open-source-vulkan-c-api) 关于它.
*  [VulkanSharp](https://github.com/mono/VulkanSharp) - C# bindings for Vulkan. [MIT]
*  [Vulkano](https://github.com/vulkano-rs/vulkano)   -  Vulkan API周围安全且丰富的Rust包装.  [MIT]
*  [LWJGL](https://www.lwjgl.org/)   - 轻量级Java游戏库3具有Vulkan绑定.  [BSD]
*  [SharpVk](https://github.com/FacticiusVir/SharpVk) - C# bindings for Vulkan with Linq-to-SPIR-V & [NuGet package](https://www.nuget.org/packages/SharpVk) ，  [MIT]
*  [vulkan](https://github.com/realitix/vulkan)   - 使用CFFI生成的Vulkan的终极Python绑定.  [Apache许可证2.0]
*  [vulkan-go](https://github.com/vulkan-go/vulkan)   - 为Vulkan绑定绑定.  [MH]

## Tools
*  [Nsight™ Visual Studio Edition 5.2+](https://developer.nvidia.com/nvidia-nsight-visual-studio-edition).
*  [LoaderAndValidationLayers](https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers)   - 来自KhronosGroup.  [Apache许可证2.0]
*  [renderdoc](https://github.com/baldurk/renderdoc)   - 由baldurk，一个独立的图形调试工具.  [MIT]
*  [VulkanTools](https://github.com/LunarG/VulkanTools)   -  LunarG的工具包括图层，`vktrace`和`vkreplay`.  [Apache许可证2.0]
*  [CodeXL](https://github.com/GPUOpen-Tools/CodeXL)   -  CodeXL开源.  [MIT]
*  [Qualcomm GPU Tools](https://developer.qualcomm.com/software/adreno-gpu-sdk/tools).
*  [Mali Graphics Debugger](http://malideveloper.arm.com/resources/tools/mali-graphics-debugger/).
*  [Open Capture and Analytics Tool (OCAT)](https://github.com/GPUOpen-Tools/OCAT)   - 为D3D11，D3D12和Vulkan提供FPS覆盖和性能测量.  [MIT]
*  [gapid](https://github.com/google/gapid)   -  Graphics API Debugger，可以跟踪和重放Android OpenGL ES和Vulkan应用程序.  [Apache许可证2.0]
*  [ARM - PerfDoc](https://github.com/ARM-software/perfdoc)   - 针对Mali Application Developer最佳实践文档的验证层.  [MIT]

## Books
* [Introduction to Computer Graphics and the Vulkan API](https://www.amazon.com/Introduction-Computer-Graphics-Vulkan-API/dp/1548616176) 作者** Kenwright **  - 使用Vulkan API从读者的实际角度向读者介绍计算机图形学的激动人心的主题.
* [Learning Vulkan](https://www.amazon.com/Learning-Vulkan-Parminder-Singh/dp/1786469804) -  by ** Parminder Singh **  - 使用易于理解的示例开始使用Vulkan API及其编程技术.
  * [Book's Examples](https://github.com/PacktPublishing/Learning-Vulkan)
* [Vulkan Cookbook](https://www.amazon.com/Vulkan-Cookbook-Pawel-Lapinski/dp/1786468158)-  ** Pawel Lapinski **  - 探索各种图形编程和GPU计算方法，以充分利用Vulkan API.
  * [Book's Examples](https://github.com/PacktPublishing/Vulkan-Cookbook)
* [Vulkan Programming Guide](https://www.amazon.com/Vulkan-Programming-Guide-Official-Learning/dp/0134464540) - 由** Graham Sellers **和** John Kessenich **  - 为许多领域推出强大的3D开发技术.

## Khronos
*规格
    *  [Vulkan 1.0 Specification](https://www.khronos.org/registry/vulkan/specs/1.0/pdf/vkspec.pdf)
    *  [Vulkan 1.0 Specification with Extensions ](https://www.khronos.org/registry/vulkan/specs/1.0-extensions/pdf/vkspec.pdf)
    *  [Vulkan 1.0 Specification with WSI Extensions](https://www.khronos.org/registry/vulkan/specs/1.0-wsi_extensions/pdf/vkspec.pdf)
    *  [Vulkan 1.1 Specification](https://www.khronos.org/registry/vulkan/specs/1.1/pdf/)
    *  [Vulkan 1.1 Specification with Extensions ](https://www.khronos.org/registry/vulkan/specs/1.1-extensions/pdf/vkspec.pdf)
    *  [Vulkan 1.1 Specification with KHR Extensions](https://www.khronos.org/registry/vulkan/specs/1.1-khr-extensions/pdf/)
*快速参考表
    *  [Vulkan 1.0 Quick Reference Sheets](https://www.khronos.org/registry/vulkan/specs/1.0/refguide/Vulkan-1.0-web.pdf)
    *  [Vulkan 1.1 Quick Reference Sheets](https://www.khronos.org/registry/vulkan/specs/1.1/refguide/Vulkan-1.1-web.pdf)
*  [Conformance Tests (CTS)](https://github.com/KhronosGroup/Vulkan-CTS)
*会议和演讲
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
*  [Discord](https://discord.gg/JyJDbyH)

## Related lists
*  [awesome](https://github.com/sindresorhus/awesome) - 精选列表的精选列表.
*  [awesome-opengl](https://github.com/eug/awesome-opengl) - 精选的OpenGL库，调试器和资源的精选列表.
*  [gamedev](https://github.com/ellisonleao/magictools) - 关于游戏开发的精彩列表.
*  [graphics-resources](https://github.com/mattdesl/graphics-resources) - 图形编程资源列表.
*  [awesome-d3d12](https://github.com/vinjn/awesome-d3d12) - 精选的D3D12库，调试器和资源的精选列表.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

这项工作是根据a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Contributing
请参阅 [CONTRIBUTING](https://github.com/vinjn/awesome-vulkan/blob/master/CONTRIBUTING.md) 详情.
