<div class="github-widget" data-repo="Dvergar/awesome-haxe-gamedev"></div>
<div align="center"><a href="https://haxe.org/"><img src="https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/haxe-logo.png" width="500"></a></div>

## Awesome Haxe Game Development [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

** 的游戏开发资源精选列表[Haxe 4](https://haxe.org/)**，一种高级严格类型编程语言，用于生成跨平台本机代码.

请随时更新.


## Game engines

这些是 Haxe 4 兼容的游戏引擎.

 |引擎|目标| 描述|
|-------------------------------------------------------------|------------------------------|--------------------------------------------------------------------|
|[Armory (Kha)](https://github.com/armory3d/armory)            |Web、移动、桌面、控制台|完全集成 Blender 的开源 3D 游戏引擎.  |
|[Away3D](https://github.com/openfl/away3d)                    |Web、移动、桌面 |OpenFL 的开源实时 3D 引擎.  |
|[ceramic](https://github.com/ceramic-engine/ceramic)          |Web、移动、桌面、Unity |跨平台 2D 框架.  |
|[HaxeFlixel (OpenFL)](https://github.com/HaxeFlixel/flixel)   |网络、移动、桌面、游戏机|由 OpenFL 提供支持的免费跨平台 2D 游戏引擎.  |
|[Haxegon (OpenFL)](https://github.com/haxegon/haxegon)        |Web、移动、桌面、控制台|适合初学者的编程库. 由 OpenFL 和 Starling 提供支持.
|[Heaps](https://github.com/HeapsIO/heaps)                     |Web、移动、桌面、游戏机|高性能游戏框架.  |
|[hxdefold](https://github.com/hxdefold/hxdefold)              |Web、移动、桌面 |Defold 游戏引擎的 Haxe/Lua 外部程序.  |
|[OpenFL](https://github.com/openfl/openfl)                    |Web、移动、桌面、控制台|交互式游戏和应用程序开发库.  |
|[Starling](https://github.com/openfl/starling)                |Web、移动、桌面 |“跨平台游戏引擎”，一种流行的 Stage3D 框架.  |
|[Stencyl (OpenFL)](https://github.com/Stencyl/stencyl-engine) |Web、移动、桌面 |无需代码即可创建 Flash、HTML5、iOS、Android 和桌面游戏.  |
|[unreal.hx](https://github.com/proletariatgames/unreal.hx)    |Web、移动、桌面、控制台|虚幻引擎的 Haxe 集成.  |
|[HxGodot (Godot 4.0)](https://github.com/HxGodot/hxgodot)    |Web、移动、桌面、控制台|Godot 4 的 Haxe GDExtension |


|低级引擎 |目标 |描述 |
|---------------------------------------------------|-----------------------------|-----------------------------------------------------------------------|
|[Kha](https://github.com/Kode/Kha)                  |Web、移动、桌面、控制台|超便携、高性能、开源多媒体框架.  |
|[Lime](https://github.com/openfl/lime)              |Web、移动、桌面 |为 Haxe 跨平台开发人员提供灵活、轻量级的层.  |
|[linc_glfw](https://github.com/Sunjammer/linc_glfw)|桌面 |GLFW 绑定（OpenGL、OpenGL ES 和 Vulkan 的多平台库）.|
|[NME](https://github.com/haxenme/nme)               |Web、移动、桌面 |跨平台本机后端.  |
|[3DSHaxe](https://github.com/haxenme/nme)           |3DS |制作 3ds 自制软件！  |




## Physics
|库 |说明 |
|------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
|[echo](https://github.com/AustinEast/echo/)            |简单的物理库.  |
|[haxebullet](https://github.com/armory3d/haxebullet)   |子弹 3D 物理.  |
|[nape-haxe4](https://github.com/HaxeFlixel/nape-haxe4)|Physics Engine（颈背原来的Haxe3版本可以找到 [here](https://github.com/deltaluca/nape)).|



## Architecture
```
IoC == 控制反转  
EC == 实体组件  
ECS == 实体组件系统
FSM == 有限状态机
MVC == 模型视图控制器
```

 |图书馆|建筑| 描述 |
|---------------------------------------------------|------------|------------------------------------------------------------------------------|
|[awe6](https://github.com/hypersurge/awe6)         |IoC、EC |倒转游戏框架，是一款专注于Future Proofing的开发工具.
|[ecx](https://github.com/eliasku/ecx)               |ECS |实体组件系统框架.  |
|[hexMachina](https://github.com/DoclerLabs/hexCore) |MVC |一个强大的多模块MVC框架.  |
|[OSIS](https://github.com/Dvergar/OSIS)             |ECS |具有网络支持的实体组件系统架构.  |


## Networking
 |图书馆| 描述 |
|--------------------------------------------------------------------|----------------------------------------------|
|[Anette](https://github.com/Dvergar/Anette)                          |简单的网络库（无UDP）.  |
|[colyseus-hx](https://github.com/colyseus/colyseus-hx)               |多人游戏客户端.  |
|[haxe-simple-peer (js)](https://github.com/melonin/haxe-simple-peer) |Hax externs 用于简单对等.  |
|[hxWebSockets](https://github.com/ianharrigan/hxWebSockets)          |适用于所有平台的 Websocket.  |
|内置|Heaps、OpenFL (HaxeFlixel &amp; co)、Kha (Armory).|


## Serialization and storage
 |图书馆| 描述 |
|-------------------------------------------------|-----------------------------------------------------------|
|[Bits](https://github.com/RealyUniqueName/Bits)   |具有无限数量位的二进制位标志.  |
|[CastleDB](https://github.com/ncannasse/castle)   |简化协作的结构化静态数据库.  |
|[hxbit](https://github.com/ncannasse/hxbit)      |二进制序列化和网络同步库.|
|[PODStream](https://github.com/Dvergar/PODStream) |普通旧数据序列化器.  |



## Games
|游戏|平台|引擎|截图|
|----------------------------------------------------------------------------|--------------------|-------------------|----------------------------------------------|
 |**已发布** |  |  |  |
|[Darksburg](https://store.steampowered.com/app/939100/Darksburg/)           |桌面|堆|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/darksburg.jpg)           |
|[Dead Cells](https://dead-cells.com/)                                       |桌面、控制台|堆|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/dead-cells.jpg)          |
|[Defender's Quest](http://www.defendersquest.com/)                          |桌面、控制台|HaxeFlixel (OpenFL)|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/defenders-quest.jpg)     |
|[Defender's Quest 2](https://store.steampowered.com/app/252190/Defenders_Quest_2_Mists_of_Ruin/)|桌面|HaxeFlixel (OpenFL)|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/defenders-quest-2.jpg)     |
|[Dicey Dungeons](http://diceydungeons.com/)                                 |桌面、游戏机|Haxegon (OpenFL) |![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/dicey-dungeons.jpg)      |
|[Evoland](http://evoland.shirogames.com/)                                   |桌面、移动|堆|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/evoland.jpg)             |
|[Northgard](http://northgard.net/)                                          |桌面|堆|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/northgard.jpg)           |
|[Papers, Please](http://papersplea.se/)                                     |桌面、iOS、PsVita|OpenFL |![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/papers-please.jpg)       |
|[Pocket Kingdom](https://store.steampowered.com/app/462620/Pocket_Kingdom/) |桌面|HaxePunk (OpenFL) |![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/pocket-kingdom.jpg)      |
|[rymdkapsel](https://rymdkapsel.com/)                                       |桌面、移动|OpenFL |![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/rymdkapsel.jpg)          |
|[Spellbreak](https://playspellbreak.com/)                                   |PC、PS、Xbox、Switch|unreal.hx |![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/spellbreak.jpg)          |
|[The Westport Independent](http://www.doublezeroonezero.com/westport.html)  |桌面、移动|豪华|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/westport-independent.jpg)|
 |**开发中** |  |  |  |
|[Frontier Story](https://twitter.com/jmw327)                                |桌面|堆|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/frontier-story.jpg)      |

更多展示：
* [OpenFL showcase](https://www.openfl.org/showcase)
* [HaxeFlixel showcase](https://haxeflixel.com/showcase/)
* [itch.io showcase](https://itch.io/games/made-with-haxe)
* [HaxePunk showcase](https://haxepunk.com/games/)
* [Flambe showcase](https://github.com/aduros/flambe/wiki/Showcase)
* [Kha showcase](https://github.com/Kode/Kha/wiki/Games-Built-With-Kha)

## Miscellaneous
 |类型|库| 描述 |
|---------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|第三方API |[SteamWrap](https://github.com/larsiusprime/SteamWrap)                     |SteamAPI 的本机扩展.|
|_                    |[newgrounds](https://lib.haxe.org/p/newgrounds)                            |Newgrounds API.|
|_                    |[hxgamejolt-api](https://github.com/MAJigsaw77/hxgamejolt-api)             |GameJolt API 的 Haxe 绑定.|
| 人工智能 |[goap](https://gitlab.com/haath/goap)                           |面向人工智能的目标导向行动规划器.|
|动画|[spine-hx](https://github.com/jeremyfa/spine-hx)                           |Spine 运行时自动从官方 Java/libgdx 运行时转换而来.|
|_ |HaxeFlixel |Spine 解析器.|
|_                    |[Heaps-Spine](https://github.com/Beeblerox/Heaps-Spine)                    |堆的脊椎播放器.|
|_                    |[heaps-aseprite](https://github.com/AustinEast/heaps-aseprite)             |以 Aseprite 格式加载和渲染精灵和动画.|
|_                    |[openfl-aseprite](https://github.com/miriti/openfl-aseprite)               |以 Aseprite 格式加载和渲染精灵和动画.|
|_                    |[openfl-spine](https://github.com/rainyt/openfl-spine)                     |在OpenFL引擎中渲染Spine动画，可以通过Sprite和Tilemap来实现渲染处理.|
|_                    |[ase](https://github.com/miriti/ase)                                       |.ase/.aseprite 文件格式加载器，无需外部依赖.|
|_                    |[flxgif](https://github.com/MAJigsaw77/flxgif)                             |Yagp 的 HaxeFlixel 的 Gif 播放器.|
|音频|[sfxr-hx](https://github.com/jobf/sfxr-hx)                                 |Sfxr 的纯 haxe 实现.|
|色彩处理|[nxColor](https://github.com/oscarcs/nxColor)                              |Color manipulation library.|
|碰撞|[differ](https://github.com/snowkit/differ)                                |分离轴定理碰撞库.|
|计算机视觉 |[Vision](https://github.com/ShaharMS/Vision)                               |跨平台计算机视觉库.|
|数据结构|[polygonal-ds](https://github.com/polygonal/ds)                            |游戏的数据结构.|
|编辑|[flixel-studio](https://github.com/Dovyski/flixel-studio)                  |HaxeFlixel 的游戏内编辑器.|
|帮手|[deepnightLibs](https://github.com/deepnight/deepnightLibs)                |通用游戏开发目的库.|
|程序生成|[Dungeon builder](https://github.com/julsam/dungeon-builder)               |一组地牢生成算法（可在 hx4 中进行微小更改）.|
|本地化|[firetongue](https://github.com/larsiusprime/firetongue)                   |翻译/本地化框架.|
|地图解析器|[PyxelEdit Map Importer](https://github.com/Dvergar/PyxelEdit-Map-Importer)|编辑器 PyxelEdit 生成的地图的解析器.|
|_ |堆 |Tiled 的内置解析器.|
|_ |HaxeFlixel |Tiled 和 Ogmo 解析器.|
|_                    |[LEd](https://github.com/deepnight/led-haxe-api)                           |带有类型化编译时加载器的二维关卡编辑器.|
|_                    |[TiledHX](https://github.com/yanrishatum/tiledhx)                          |一个全面的现代 Tiled 解析器.|
|数学助手|[hxmath](https://github.com/tbrosman/hxmath)                               |面向游戏的数学库.|
|_                    |[haxe-glm](https://github.com/hamaluik/haxe-glm)                           |用于使用 2、3 和 4 维向量和矩阵以及四元数的工具集.|
|_                    |[hx-vector2d](https://github.com/markknol/hx-vector2d)                      |世界上最完整的 Vector2d / Point 类. 具有运算符重载.|
|改装|[polymod](https://github.com/larsiusprime/polymod)                         |游戏/应用程序的原子模组框架.|
|颗粒|[Sparkler](https://github.com/RudenkoArts/sparkler)                        |模块化粒子系统.|
|货币化|[extension-iap](https://github.com/charmdev/extension-iap)                  |使用通用 API 为 OpenFL 项目提供应用内购买 (iOS) 和应用内计费 (Android) 的访问权限. 叉子 [this](https://github.com/HaxeExtension/extension-iap).|
|寻路|[pathfinder](https://github.com/hypersurge/pathfinder)                     |简单的 A* 寻路算法.|
|_                    |[astar](https://gitlab.com/haath/astar)                                    |与框架无关的多功能 A-star 求解器库.|
|着色器|[HGSL](https://github.com/saharan/HGSL)                                    |Haxe to GL Shading Language.|
|_                    |[parasol](https://github.com/47rooks/parasol)                              |HaxeFlixel 着色器库.|
|雪碧|[haxe-aseprite](https://github.com/PongoEngine/haxe-aseprite)              |.ase 和 .aseprite 文件的解析器.|
|纹理打包器|[hxpk](https://github.com/bendmorris/hxpk)                                 |libGDX 纹理打包器的端口.|
|补间|[actuate](https://github.com/jgranick/actuate)                             |灵活、快速的“补间”库.|
|_                    |[YATL](https://github.com/Yanrishatum/yatl)                                |又一个 (Haxe) 补间库.|
|_                    |[TweenX/TweenXCore](https://github.com/shohei909/tweenx)                   |补间库.|
|用户界面|[domkit](https://github.com/ncannasse/domkit)                              |基于 CSS 组件的严格类型 UI 框架.|
|_                    |[flixel-ui](https://github.com/HaxeFlixel/flixel-ui)                       |HaxeFlixel 的 GUI 库.|
|_                    |[HaxeUI](http://haxeui.org/)                                               |具有多个框架后端的 UI 库（HTML5、Kha、OpenFL、PixiJS、WxWidgets 以及许多其他正在进行的工作）|
|_                    |[Feathers UI](https://feathersui.com/)                                          |用于创意前端项目的跨平台图形用户界面组件|
 | 视频 |[hxCodec](https://github.com/polybiusproxy/hxCodec)                        |在 HaxeFlixel 和 OpenFL 上添加本机视频播放|

## Articles
* [Flash is dead, long live OpenFL!](http://gamasutra.com/blogs/LarsDoucet/20140318/213407/Flash_is_dead_long_live_OpenFL.php)
* [Flash is gone, what now?](https://www.linkedin.com/pulse/flash-gone-what-now-matan-uberstein/)
* [How I wrote my own 3D game engine and shipped a game with it in 20 months](https://kircode.com/post/how-i-wrote-my-own-3d-game-engine-and-shipped-a-game-with-it-in-20-months)
* [Building 42 games within a year — Insane game development](https://medium.com/@mknol/building-42-games-within-a-year-insane-game-development-5340d506068f)
* [Porting to console via Unity](https://do-games.com/blog/the-adventure-pals-console-tech-part1)

## Other haxe lists
* [awesome haxe](https://github.com/nadako/awesome-haxe)
* [awesome snowkit](https://github.com/anissen/awesome-snowkit)
* [awesome haxe js](https://github.com/MatthijsKamstra/awesome-haxe-js)
