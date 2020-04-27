<div class="github-widget" data-repo="Dvergar/awesome-haxe-gamedev"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center"><a href="https://haxe.org/"><img src="https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/haxe-logo.png" width="500"></a></div>

## Awesome Haxe Game Development [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

精选的**游戏开发资源清单[Haxe 4](https://haxe.org/)**，一种高级的严格类型化的编程语言，用于生成跨平台的本机代码.

随时更新.


## Game engines

这些是兼容Haxe 4的游戏引擎.

 |引擎|目标|  描述|
|-------------------------------------------------------------|------------------------------|--------------------------------------------------------------------|
|[Armory (Kha)](https://github.com/armory3d/armory)            | Web，移动，桌面，控制台|具有完整Blender集成的开源3D游戏引擎.  |
|[Away3D](https://github.com/openfl/away3d)                    | Web，移动，桌面|用于OpenFL的开源，实时3D引擎.  |
|[HaxeFlixel (OpenFL)](https://github.com/HaxeFlixel/flixel)   | Web，移动，桌面，控制台|由OpenFL提供支持的免费，跨平台2D游戏引擎.  |
|[Haxegon (OpenFL)](https://github.com/haxegon/haxegon)        | Web，移动，桌面，控制台|面向初学者的编程库.  由OpenFL和Starling提供支持.
|[Heaps](https://github.com/HeapsIO/heaps)                     | Web，移动，桌面，控制台|高性能游戏框架.  |
|[hxdefold](https://github.com/hxdefold/hxdefold)              | Web，移动设备，台式机|用于Defold游戏引擎的Haxe / Lua externs.  |
|[OpenFL](https://github.com/openfl/openfl)                    | Web，移动，桌面，控制台|交互式游戏和应用程序开发库.  |
|[Starling](https://github.com/openfl/starling)                | Web，移动，桌面|“跨平台游戏引擎”，一种流行的Stage3D框架.  |
|[Stencyl (OpenFL)](https://github.com/Stencyl/stencyl-engine) | Web，移动，台式机|无需代码即可创建Flash，HTML5，iOS，Android和台式机游戏.  |
|[unreal.hx](https://github.com/proletariatgames/unreal.hx)    | Web，移动，桌面，控制台|虚幻引擎的哈希集成.  |


|低级引擎|目标|描述|
|---------------------------------------------------|-----------------------------|-----------------------------------------------------------------------|
|[Kha](https://github.com/Kode/Kha)                  | Web，移动，桌面，控制台|超便携式，高性能，开源多媒体框架.  |
|[Lime](https://github.com/openfl/lime)              | Web，移动，桌面|适用于Haxe跨平台开发人员的灵活，轻便的层.  |
|[linc_glfw](https://github.com/Sunjammer/linc_glfw)|桌面| GLFW绑定（用于OpenGL，Op​​enGL ES和Vulkan的多平台库）.
|[NME](https://github.com/haxenme/nme)               | Web，移动，桌面|用于Haxe项目的跨平台本机后端.  |




## Physics
|库|描述|
|------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
|[echo](https://github.com/AustinEast/echo/)            |简单物理库.  |
|[haxebullet](https://github.com/armory3d/haxebullet)  |Bullet 3D Physics for Haxe.                                                                                |
|[nape-haxe4](https://github.com/HaxeFlixel/nape-haxe4)|物理引擎（可以找到nape的原始Haxe3版本 [here](https://github.com/deltaluca/nape)).|



## Architecture
```
IoC ==控制反转  
EC ==实体组件  
ECS ==实体组件系统
FSM ==有限状态机
MVC ==模型视图控制器
```

 |图书馆|建筑|  描述
|---------------------------------------------------|------------|------------------------------------------------------------------------------|
|[awe6](https://github.com/hypersurge/awe6)         | IoC，EC |反向游戏框架是一种专注于未来验证的开发工具.
|[ecx](https://github.com/eliasku/ecx)               | ECS |实体组件系统框架.  |
|[hexMachina](https://github.com/DoclerLabs/hexCore) | MVC |强大的多模块MVC框架.  |
|[OSIS](https://github.com/Dvergar/OSIS)             | ECS |具有网络支持的实体组件系统体系结构.  |


## Networking
 |图书馆|  描述
|--------------------------------------------------------------------|----------------------------------------------|
|[Anette](https://github.com/Dvergar/Anette)                          |简单的网络库（无UDP）.  |
|[colyseus-hx](https://github.com/colyseus/colyseus-hx)               |多人游戏客户端.  |
|[haxe-simple-peer (js)](https://github.com/melonin/haxe-simple-peer) |用于简单对等的haxe externs.  |
|[hxWebSockets](https://github.com/ianharrigan/hxWebSockets)          |用于所有Haxe平台的Websocket.  |
|内置|堆，OpenFL（HaxeFlixel＆co），Kha（Armory）.|


## Serialization and storage
 |图书馆|  描述
|-------------------------------------------------|-----------------------------------------------------------|
|[Bits](https://github.com/RealyUniqueName/Bits)   |具有无限位数的二进制位标志.  |
|[CastleDB](https://github.com/ncannasse/castle)   |结构化的静态数据库可简化协作.  |
|[hxbit](https://github.com/ncannasse/hxbit)      |二进制序列化和网络同步库.
|[PODStream](https://github.com/Dvergar/PODStream) |普通的旧数据序列化程序.  |



## Games
|游戏|平台|引擎|截屏|
|---------------------------------------------------------------------------|--------------------|-------------------|----------------------------------------------|
 | **已释放** |  |  |  |
|[Dead Cells](https://dead-cells.com/)                                      |桌面，控制台|堆|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/dead-cells.jpg)          |
|[Defender's Quest](http://www.defendersquest.com/)                         |桌面，控制台| HaxeFlixel（OpenFL）|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/defenders-quest.jpg)     |
|[Dicey Dungeons](http://diceydungeons.com/)                                |桌面，控制台| Haxegon（OpenFL）|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/dicey-dungeons.jpg)      |
|[Evoland](http://evoland.shirogames.com/)                                  |便携式桌面|堆|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/evoland.jpg)             |
|[Northgard](http://northgard.net/)                                         |桌面|堆|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/northgard.jpg)           |
|[Papers, Please](http://papersplea.se/)                                    |桌面，iOS，PsVita | OpenFL |![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/papers-please.jpg)       |
|[Pocket Kingdom](https://store.steampowered.com/app/462620/Pocket_Kingdom/)|桌面| HaxePunk（OpenFL）|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/pocket-kingdom.jpg)      |
|[rymdkapsel](https://rymdkapsel.com/)                                      |便携式桌面| OpenFL |![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/rymdkapsel.jpg)          |
|[The Westport Independent](http://www.doublezeroonezero.com/westport.html) |便携式桌面|豪华型|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/westport-independent.jpg)|
 | **正在开发** | |  |  |  |
|[Darksburg](https://store.steampowered.com/app/939100/Darksburg/)           |桌面，？  |堆|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/darksburg.jpg)           |
|[Frontier Story](https://twitter.com/jmw327)                               |桌面|堆|![Screenshot](https://raw.githubusercontent.com/Dvergar/awesome-haxe-gamedev/master/images/frontier-story.jpg)      |

更多展示柜：
* [OpenFL showcase](https://www.openfl.org/showcase)
* [HaxeFlixel showcase](https://haxeflixel.com/showcase/)
* [itch.io showcase](https://itch.io/games/made-with-haxe)
* [HaxePunk showcase](https://haxepunk.com/games/)
* [Flambe showcase](https://github.com/aduros/flambe/wiki/Showcase)
* [Kha showcase](https://github.com/Kode/Kha/wiki/Games-Built-With-Kha)

## Miscellaneous
 |类型|库|  描述
|---------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|动画|[spine-hx](https://github.com/jeremyfa/spine-hx)                            | Haxe的Spine运行时自动从官方Java / libgdx运行时转换而来.  对于堆： [Heaps-Spine](https://github.com/Beeblerox/Heaps-Spine).                        |
| _ | HaxeFlixel |通过脊柱解析器 [flixel-addons](https://github.com/HaxeFlixel/flixel-addons/tree/dev/flixel/addons/editors).                                                                    |
|_                    |[Heaps-Spine](https://github.com/Beeblerox/Heaps-Spine)                     |用于堆的脊椎播放器.  |
|颜色处理|[nxColor](https://github.com/oscarcs/nxColor)                               |颜色处理库.  |
|碰撞|[differ](https://github.com/snowkit/differ)                                 |分离轴定理碰撞库.  |
|数据结构|[polygonal-ds](https://github.com/polygonal/ds)                             |游戏的数据结构.  |
|编辑器|[flixel-studio](https://github.com/Dovyski/flixel-studio)                   | HaxeFlixel的游戏内编辑器.  |
|程序生成|[Dungeon builder](https://github.com/julsam/dungeon-builder)                |一组地牢生成算法（使用w / hx4 w /较小更改）.  |
|本地化|[firetongue](https://github.com/larsiusprime/firetongue)                    |用Haxe编写的翻译/本地化框架.  |
|地图解析器|[PyxelEdit Map Importer](https://github.com/Dvergar/PyxelEdit-Map-Importer) |解析器，用于编辑器PyxelEdit生成的地图.  |
 | _ |堆| Tiled的内置解析器.  |
| _ | HaxeFlixel |用于Tiled和Ogmo的解析器，通过 [flixel-addons](https://github.com/HaxeFlixel/flixel-addons/tree/dev/flixel/addons/editors).                                                         |
|数学助手|[hxmath](https://github.com/tbrosman/hxmath)                                |面向Haxe语言的面向游戏的数学库.  |
|_                    |[haxe-glm](https://github.com/hamaluik/haxe-glm)                            |使用2维，3维和4维向量和矩阵以及四元数的工具集.  |
|_                    |[hx-vector2d](https://github.com/markknol/hx-vector2d)                      |世界上最完整的Vector2d / Point类.  随着运算符的重载.  |
|改装|[polymod](https://github.com/larsiusprime/polymod)                          | Haxe游戏/应用程序的原子改装框架.  |
|颗粒|[Sparkler](https://github.com/RudenkoArts/sparkler)                         |模块化粒子系统.  |
|获利|[extension-iap](https://github.com/charmdev/extension-iap)                  |使用通用API为OpenFL项目提供对应用程序内购买（iOS）和应用程序内计费（Android）的访问.  前叉 [this](https://github.com/HaxeExtension/extension-iap).|
|寻路|[pathfinder](https://github.com/hypersurge/pathfinder)                      |简单的A *寻路算法.  |
|精灵|[haxe-aseprite](https://github.com/PongoEngine/haxe-aseprite)               .ase和.aseprite文件的解析器.  |
|蒸汽|[SteamWrap](https://github.com/larsiusprime/SteamWrap)                      | Steam API的哈希本机扩展.  |
|Texture Packer       |[hxpk](https://github.com/bendmorris/hxpk)                                  | libGDX Texture Packer的端口.  |
|补间|[actuate](https://github.com/jgranick/actuate)                              |灵活，快速的“补间”库.  |
|_                    |[YATL](https://github.com/Yanrishatum/yatl)                                 |另一个（补间）补间库.  |
|洋葱|[domkit](https://github.com/ncannasse/domkit)                               |基于CSS组件的严格类型UI框架.  |
|_                    |[flixel-ui](https://github.com/HaxeFlixel/flixel-ui)                        | HaxeFlixel的GUI库.  |
|_                    |[HaxeUI](http://haxeui.org/)                                                |具有多个框架后端的UI库（HT​​ML5，Kha，OpenFL，PixiJS，WxWidgets以及许多其他正在进行中的工作）|  |

## Jobs
* [Squidly](https://twitter.com/squuuidly/status/1243925472121151488) - 打开 [a bounties page](https://github.com/chosencharacters/squidBounties) HaxeFlixel功能，其中之一是 [already claimed](https://github.com/chosencharacters/squidBounties/issues/2).
* [Kaleido Games](https://twitter.com/KaleidoGames) -使OpenFL与之合作的赏金 [(FNA/UWP)](https://community.openfl.org/t/bounty-to-make-openfl-work-with-fna-uwp-300usd-150usd/12328).
* [NX Studio](https://studionx.ru/) - 寻找 [a Haxe programmer](https://hh.ru/vacancy/35432606)  参与他们的游戏“ Throne Rush”.  _（俄罗斯莫斯科）_
* [Shiro Games](https://twitter.com/ncannasse/status/1166704326485651457) -招募不同的角色来扩展他们的工作室并从事即将到来的令人兴奋的项目！
* Lars Doucet的各种清单 [open bounties](https://github.com/larsiusprime/larsBounties/issues).

_来源：haxe.io_

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

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
