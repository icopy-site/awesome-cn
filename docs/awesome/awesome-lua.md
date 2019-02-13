## Awesome Lua [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精选的Lua精选清单 [packages](#packages) 和 [resources](#resources).

灵感来自清单 [awesome](https://github.com/sindresorhus/awesome), [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)，和 [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs).


## Packages
- [Implementations, Interpreters, and Bindings](#implementations-interpreters-and-bindings)
- [Package Managers](#package-managers)
- [Build Tools and Standalone Makers](#build-tools-and-standalone-makers)
- [Debugging and Profiling](#debugging-and-profiling)
- [IDEs and Plugins](#ides-and-plugins)
- [Utility Belts](#utility-belts)
- [Game Engines](#game-engines)
- [Game Development](#game-development)
- [Logging](#logging)
- [Web/Networking Platforms](#webnetworking-platforms)
- [OpenResty](#openresty)
- [Command-line Utilities](#command-line-utilities)
- [Concurrency and Multithreading](#concurrency-and-multithreading)
- [Templating](#templating)
- [Documentation](#documentation)
- [Object-oriented Programming](#object-oriented-programming)
- [File system and OS](#file-system-and-os)
- [Time and Date](#time-and-date)
- [Image Manipulation](#image-manipulation)
- [Digital Signal Processing](#digital-signal-processing)
- [Hardware and Embedded Systems](###hardware-and-embedded-systems)
- [Math and Scientific Computing](#math-and-scientific-computing)
- [Parsing and Serialization](#parsing-and-serialization)
- [Humanize](#humanize)
- [Compression](#compression)
- [Cryptography](#cryptography)
- [Network](#network)
- [Data Stores](#data-stores)
- [Message Brokers](#message-brokers)
- [Testing](#testing)
- [Foreign Function Interfaces](#foreign-function-interfaces)
- [Analysis Tools and ASTs](#analysis-tools-and-asts)
- [Experimental, etc](#experimental-etc)
- [Scriptable by Lua](#scriptable-by-lua)
- [Miscellaneous](#miscellaneous)


## Resources
- [Community](#community)
- [References](#references)
- [Style Guides](#style-guides)
- [Tutorials](#tutorials)
- [Articles](#articles)
- [Talks & Slides](#talks--slides)
- [Books](#books)
- [Other Lists](#other-lists)


### Implementations, Interpreters, and Bindings
- [Lua](http://www.lua.org/download.html) -  Lua最初的ANSI C解释器.
  - [Lua Repo](https://github.com/lua/lua) -  Lua团队看到的官方Lua回购镜像反映给GitHub.
- [LuaJIT](http://luajit.org/luajit.html) -  Lua的高性能Just-In-Time编译器.
- [LLVM-Lua](https://github.com/neopallium/llvm-lua) - 将Lua编译为LLVM.
- [lua.vm.js](https://github.com/daurnimator/lua.vm.js)   - 网络上的Lua VM;  通过LLVM，emscripten和asm.js直接移植C解释器.
- [Moonshine](https://github.com/gamesys/moonshine)   - 用JavaScript实现的Lua VM.  比lua.vm.js慢，但有更好的文档，示例和JS接口.
- [Fengari](https://fengari.io/) - 使用无缝的JS和DOM互操作性在Javascript中重写Lua VM.
- [MoonSharp](https://github.com/xanathar/moonsharp) - A Lua interpreter written entirely in C# for the .NET, Mono and Unity platforms.
- [UniLua](https://github.com/xebecnan/UniLua) - A pure C# implementation of Lua 5.2, focused on compatibility with the Unity game engine.
- [lupa](https://github.com/scoder/lupa) - 与LuaJIT2的Python绑定.
- [golua](https://github.com/aarzilli/golua) -  Golang绑定到Lua C API.
- [GopherLua](https://github.com/yuin/gopher-lua) -  Lua 5.1 VM和编译器在Go with Go API中实现.
- [LuaBridge](https://github.com/vinniefalco/LuaBridge) - 一个轻量级库，用于在C ++和Lua之间来回映射数据，函数和类.

注意：从LuaJIT到Lua再到lua.vm.js到Moonshine，一个基本的基准测试表明每次跳跃性能下降大约6倍.


### Package Managers
- [LuaRocks](https://luarocks.org/)   - 事实上的工具，用于将Lua模块安装为名为“rocks”的软件包，以及公共摇滚存储库和网站.  很像npm或pip.


### Build Tools and Standalone Makers
- [Lake](https://github.com/stevedonovan/Lake) - 用Lua编写的构建引擎，类似于Ruby的rake.
- [Luabuild](https://github.com/stevedonovan/luabuild) - 高度可定制的Lua 5.2构建系统.
- [luastatic](https://github.com/ers35/luastatic) - 将Lua程序转换为独立可执行文件的简单工具.
- [omnia](https://github.com/tongson/omnia) - 包含电池的独立可执行文件的创建者，建立在luastatic之上.


### Debugging and Profiling
- [ProFi](https://gist.github.com/perky/2838755) - 简单的分析器，与LuaJIT一起使用并生成报告文件.
- [luatrace](https://github.com/geoffleyland/luatrace) - 用于跟踪/分析/分析脚本执行和生成详细报告的工具集.
- [StackTracePlus](https://github.com/ignacio/StackTracePlus) - 直接升级到Lua的堆栈跟踪，增加了本地环境并提高了可读性.
- [MobDebug](https://github.com/pkulchenko/MobDebug)   - 具有断点和堆栈检查功能的强大远程调试器.  由ZeroBraneStudio使用.
- [lovebird](https://github.com/rxi/lovebird)   - 基于浏览器的调试控制台.  最初是为LÖVE制作的，但适用于任何支持LuaSocket的项目.


### IDEs and Plugins
- [Lua Development Tools](https://eclipse.org/ldt/)   -  Eclipse插件，提供代码完成，调试等.  建立在Metalua上.
- [Lua for IDEA](https://bitbucket.org/sylvanaar2/lua-for-idea/wiki/Home) -  IntelliJ IDEA插件，其中包括代码完成，智能突出显示和实验调试.
- [ZeroBraneStudio](https://studio.zerobrane.com/)   - 轻量级，可定制，跨平台的Lua专用IDE，带有代码完成和分析，用Lua编写.  为众多Lua引擎提供广泛的调试支持.
- [BabeLua](https://archive.codeplex.com/?p=babelua) -  VS2012-13的Lua编辑器/调试器扩展，具有突出显示，自动完成，linting和格式化功能.
- [lua-mode](https://github.com/immerrr/lua-mode) - 用于编辑Lua的Emacs主要模式.
- [vscode-lua](https://github.com/trixnz/vscode-lua) -  VSCode intellisense和linting.


### Utility Belts
- [Lua Fun](https://github.com/luafun/luafun) - 为LuaJIT设计的高性能函数编程库.
- [Moses](https://github.com/Yonaba/Moses) - 功能性编程实用带，灵感来自Underscore.js.
- [Penlight](https://github.com/stevedonovan/Penlight)   - 广泛，重量级的实用程序库，灵感来自Python的标准库.  提供Lua没有的电池.
- [lua-stdlib](https://github.com/lua-stdlib/lua-stdlib)   - 中等重量标准库扩展;  添加了一些有用的数据结构，实用程序功能和基本功能.
- [Microlight](https://github.com/stevedonovan/Microlight)   - 一个有用的Lua函数库;  Penlight的&#39;extra light&#39;版本.
- [compat53](https://luarocks.org/modules/siffiejoe/compat53) - 兼容性模块为Lua 5.2和5.1提供Lua-5.3样式的API.
- [RxLua](https://github.com/bjornbytes/RxLua) - 反应性扩展，可观察性等


### Game Engines
- [LÖVE 2D](http://love2d.org/)   - 桌面游戏开发平台.  跨平台，功能齐全，采用良好.
- [Corona SDK](https://coronalabs.com/)   - 适用于iOS和Android的开发平台.  专有，但被众多顶级游戏和应用程序使用，总下载量超过1.5亿次.
- [MOAI](http://getmoai.com/)   - 开源，跨平台，移动游戏开发框架.  由Lua脚本编写的简约C ++引擎.
- [Drystal](https://drystal.github.io/) - 开源，游戏可以在Linux或任何具有最新Web浏览器的平台上运行.
- [Amulet](http://www.amulet.xyz/)   - 适用于小型游戏和实验的开源，音频/视频工具包.  它可以在Windows，Mac，Linux，HTML5和iOS上运行.
- [LÖVR](https://lovr.org) - 受LÖVE2D启发的用于创建虚拟现实体验的3D框架.


### Game Development
- 电晕
  - [Coronium](https://develephant.github.io/coronium-core-docs/) - 支持分析，数据对象，用户管理等的简单云平台.
- 爱
  - [awesome-love2d](https://github.com/love2d-community/awesome-love2d) - 像这样的列表，但专注于游戏开发和LÖVE平台.
  - [lurker](https://github.com/rxi/lurker) - 通过在正在运行的LÖVE项目中自动交换已更改的Lua文件来缩短迭代周期.
  - [HUMP](http://vrld.github.io/hump/)   - LÖVE的一套轻量级助手;  面向游戏的实用腰带.
- MOAI
  - [moaifiddle](https://moaifiddle.com) - 编辑和共享MOAI游戏引擎的短脚本，并使用WebGL在浏览器中运行它们.
- [Jumper](https://github.com/Yonaba/Jumper) - 用于基于网格的游戏的快速，轻量且易于使用的寻路库.
- [lume](https://github.com/rxi/lume/) - 适用于游戏开发的实用带库.
- [NoobHub](https://github.com/Overtorment/NoobHub) - 遵循简单的pub-sub模型，为Corona，LÖVE等网络多人游戏.
- 碰撞检测
  - [bump.lua](https://github.com/kikito/bump.lua) - 最小的基于矩形的碰撞检测，可处理隧道和基本的碰撞分辨率.
  - [HardonCollider](http://vrld.github.io/HardonCollider/) - 检测任意类型的任意定位和旋转形状之间的碰撞.
- 补间
  - [flux](https://github.com/rxi/flux) - 一个快速，轻量级的Lua补间库，具有缓动功能和将补间组合在一起的能力.
  - [tween.lua](https://github.com/kikito/tween.lua) - 用于补间的小型库，具有多种缓动功能.
- 例子
  - [termtris](https://github.com/tylerneylon/termtris) - 一个俄罗斯方块克隆，以文化风格编写，“强调学习能力”.
  - [PacPac](https://github.com/tylerneylon/pacpac) - 用LÖVE制作的吃豆人克隆.
  - [Mari0](https://github.com/Stabyourself/mari0)   - 用LÖVE制作的Mario和Portal的融合.  另见它 [wikipedia entry](https://en.wikipedia.org/wiki/Mari0).
  - [Journey to the Center of Hawkthorne](https://github.com/hawkthorne/hawkthorne-journey) - 基于社区的2D平台游戏 [Digital Estate Planning](https://en.wikipedia.org/wiki/Digital_Estate_Planning) 插曲，用LÖVE制作.


### Logging
- [lua-log](https://github.com/moteus/lua-log) - 具有用于文件系统，网络，ZeroMQ等的可插拔编写器的异步日志记录库.
- [LuaLogging](https://github.com/Neopallium/lualogging) - 支持各种appender的Log4j启发式日志库.
- [luasyslog](https://luarocks.org/modules/luarocks/luasyslog) - 根据LuaLogging登录到syslog.


### Web/Networking Platforms
- [OpenResty](http://openresty.org/en/)   - 通过使用Lua扩展Nginx创建的快速且可扩展的Web应用程序平台.  今天是事实上的Lua网络平台，大量使用Cloudflare，淘宝，腾讯等.
- [turbo](https://turbo.readthedocs.io/en/latest/) - 受Tornado启发的事件驱动，非阻塞，基于LuaJIT的网络套件和框架.
- [Kepler Project](https://github.com/keplerproject) - 使用一组通用标准和组件的面向Web的项目的集合.
- [Pegasus.lua](https://github.com/EvandroLG/pegasus.lua) -  Pegasus.lua是一个http服务器，用于处理用Lua语言编写的Web应用程序.


### OpenResty
- [awesome-resty](https://github.com/bungle/awesome-resty) - 像这样的列表，但专注于OpenResty.
- 核心平台
  - [ngx_lua](https://www.nginx.com/resources/wiki/modules/lua/)   -  OpenResty的核心部分.  在Nginx中嵌入Lua并公开了用于非阻塞套接字的cosocket API（与LuaSocket的API兼容）.
  - [OpenResty GitHub Organization](https://github.com/openresty) -  ngx_lua，ngx_openresty和许多相关模块的存储库的主页.
- 第三方模块
  - [lua-resty-http](https://github.com/pintsized/lua-resty-http) -  Lua HTTP客户端驱动程序，构建在cosocket API上.
- 框架和工具
  - [Lapis](http://leafo.net/lapis/)   -  Lua和OpenResty的全栈框架.  就像Lua的Django或Rails一样.  支持Moonscript.
  - [ledge](https://github.com/pintsized/ledge) -  Lua模块提供可编写脚本，符合RFC的HTTP缓存功能.
  - [Sailor](https://github.com/sailorproject/sailor) - 与OpenResty，Apache和其他Web服务器兼容的MVC Web框架.
  - [Kong](https://github.com/Kong/kong) - 微服务和API管理层.

在此页面中搜索“OpenResty”以查找其他类别（特别是数据存储）下的相关包.


### Command-line Utilities
- [ansicolors](https://github.com/kikito/ansicolors.lua) - Simple function for printing to the console in color.
- [cliargs](https://github.com/amireh/lua_cliargs) - 一个简单的命令行参数解析模块.
- [lua-term](https://github.com/hoelzro/lua-term) - 终端操作和操作.
- [argparse](https://github.com/mpeterv/argparse) - 一个功能丰富的命令行解析器，受到argparse for Python的启发.

### Concurrency and Multithreading
- 基于协同程序的多任务处理：
  - [Lumen](https://github.com/xopxe/Lumen) - 简单的并发任务调度.
  - [ConcurrentLua](https://github.com/lefcha/concurrentlua) - 实现Erlang风格的消息传递并发模型.
  - [cqueues](http://25thandclement.com/~william/projects/cqueues.html) - 用于管理基于带协同程序的事件循环的套接字，信号和线程的库.
- 多线程：
  - [llthreads](https://github.com/Neopallium/lua-llthreads) - 用于低级pthreads和WIN32线程的简单包装器.
  - [llthreads2](https://github.com/moteus/lua-llthreads2) - 更新的llthreads重写.
  - [lanes](https://github.com/LuaLanes/lanes) - 库实现消息传递模型，每个Lua线程有一个OS线程.
  - [luaproc](https://github.com/askyrme/luaproc)   - 消息传递模型，允许每个OS线程有多个线程，并且可以轻松地在网络中进行通用化.  也可以看看 [the paper](http://www.inf.puc-rio.br/~roberto/docs/ry08-05.pdf) 它起源于哪里.

有关差异的更多信息（特别是`lanes`和`luaproc`之间），请参阅此内容 [comparison](http://www.luteus.biz/Download/LoriotPro_Doc/LUA/LUA_For_Windows/lanes/comparison.html)  期权;  有点过时，但涵盖了每个人的工作方式和重大差异.


### Templating
- [lustache](http://olivinelabs.com/lustache/) -  Mustache模板实现.
- [etlua](https://github.com/leafo/etlua) - 嵌入式Lua模板，ERB风格.
- [lua-resty-template](https://github.com/bungle/lua-resty-template) - 面向Lua的OpenResty模板引擎，有点像Jinja.


### Documentation
- [LDoc](http://stevedonovan.github.io/ldoc/) - 文档生成器，现代化和扩展 [LuaDoc](http://keplerproject.github.io/luadoc/).
- [Locco](http://rgieseke.github.io/locco/) -  Lua港口 [Docco](http://ashkenas.com/docco/)，“快速，肮脏，百行，文字编程风格的文档生成器”.
- [docroc](https://github.com/bjornbytes/docroc) - 将注释解析到Lua表中以生成文档.


### Object-oriented Programming
- [30log](https://github.com/Yonaba/30log) - 极简主义的OOP库，包含30行的基本类，继承和mixin.
- [middleclass](https://github.com/kikito/middleclass) - 简单但强大的OOP库，包含继承，方法，元方法，类变量和mixins.


### File system and OS
- [LuaFileSystem](http://keplerproject.github.io/luafilesystem/) - 扩展和补充Lua内置的文件系统功能集.
- [luaposix](https://github.com/luaposix/luaposix) -  POSIX API的绑定，包括curses.
- [lunix](http://25thandclement.com/~william/projects/lunix.html) - 绑定到常见的Unix系统API，努力实现线程安全.
- [lua-path](https://github.com/moteus/lua-path) - 文件系统路径操作库.


### Time and Date
- [LuaDate](https://github.com/Tieske/date) - 具有解析，格式化，加法/减法，本地化和ISO 8601支持的日期和时间模块.
- [cron.lua](https://github.com/kikito/cron.lua) -  Lua的时间相关函数，受JavaScript的setTimeout和setInterval启发.
- [luatx](https://github.com/daurnimator/luatz) - 时间，日期和时区库.


### Image Manipulation
- [magick](https://github.com/leafo/magick) - 使用FFI将Lua绑定到ImageMagick for LuaJIT.


### Digital Signal Processing
- [LuaFFT](https://github.com/h4rm/luafft) - 纯Lua中易于使用的快速傅里叶变换包.
- [Worp](http://worp.zevv.nl/about.html) - 为LuaJIT编写的声音/音乐/ DSP引擎.


### Hardware and Embedded Systems
- [eLua](http://www.eluaproject.net/) -  Lua，通过优化和特定功能进行扩展，实现高效便携的嵌入式软件开发.


### Math and Scientific Computing
- [SciLua](http://scilua.org/) - 基于LuaJIT构建的数字/科学计算框架，具有到R的接口.
- [Torch7](http://torch.ch/) - 广泛支持机器学习算法的科学计算框架，由Facebook，Google等使用.
- [lhf's Lua Tools](http://webserver2.tecgraf.puc-rio.br/~lhf/ftp/lua/) - 各种图书馆和工具，许多数学或数据相关.


### Parsing and Serialization
-  JSON
  - [lua-cjson](https://github.com/mpx/lua-cjson/) - 在C中实现快速JSON编码/解码并暴露给Lua.
  - [luajson](https://github.com/harningt/luajson) - 在Lue上实现的JSON编码器/解码器在LPeg之上.
  - [dkjson](http://dkolf.de/src/dkjson-lua.fsl/home) - 以纯Lua实现的JSON编码器/解码器.
  - [json.lua](https://github.com/rxi/json.lua) - 纯Lua中快速而小巧的JSON库.
-  XML
  - [LuaExpat](https://matthewwild.co.uk/projects/luaexpat/) - 通过绑定到Expat库的SAX XML解析器.
  - [SLAXML](https://github.com/Phrogz/SLAXML) - 纯Lua SAX类似流XML解析器.
-  MessagePack
  - [lua-MessagePack](https://github.com/fperrad/lua-MessagePack) -  Pure Lua实现MessagePack.
  - [lua-cmsgpack](https://github.com/antirez/lua-cmsgpack) -  Redis使用的具有Lua绑定的MessagePack C实现.=
-  LPeg
  - [LPeg](http://www.inf.puc-rio.br/~roberto/lpeg/) -  Lua的模式匹配库，基于解析表达式语法.
  - [lpeg_patterns](https://github.com/daurnimator/lpeg_patterns) - 一系列LPeg模式.
  - [LuLPeg](https://github.com/pygy/LuLPeg) - A pure Lua implementation of LPeg v0.12.
  - [LPegLJ](https://github.com/sacek/LPegLJ) -  LPeg v1.0的纯LuaJIT实现.
  - [LPegLabel](https://github.com/sqmedeiros/lpeglabel) -  LPeg的扩展，增加了对标记失败的支持.
- [lyaml](https://github.com/gvvaughan/lyaml) - 通过绑定到LibYAML进行YAML编码/解码.
- [lunamark](https://github.com/jgm/lunamark)   - 将Markdown转换为其他文本格式，包括HTML和LaTeX.  使用LPeg进行快速解析.
- [LXSH](https://github.com/xolox/lua-lxsh) - 用LPeg编写的词法分析器和语法荧光笔的集合.
- [lua-pb](https://github.com/Neopallium/lua-pb) -  Protocol Buffers实现.


### Humanize
- [i18n.lua](https://github.com/kikito/i18n.lua) - 具有区域设置，格式和复数的国际化库.
- [inspect.lua](https://github.com/kikito/inspect.lua) -  Lua表的人类可读表示.
- [serpent](https://github.com/pkulchenko/serpent) - 串行器和漂亮的打印机.
- [Ser](https://github.com/gvx/Ser) - 具有良好性能的死简单序列化器.
- [say](https://github.com/Olivine-Labs/say) -  i18n的简单字符串键值存储.


### Compression
- [lua-zlib](https://github.com/brimworks/lua-zlib) -  zlib for gzip / gunzip的简单流媒体接口.
- [lua-zip](https://github.com/brimworks/lua-zip)   -  Lua绑定到libzip.  读取和写入zip文件.


### Cryptography
- [LuaCrypto](https://github.com/mkottman/luacrypto) -  Lua绑定到OpenSSL.
- [lua-lockbox](https://github.com/somesocks/lua-lockbox) - 用纯Lua编写的加密原语的集合.
- [luatweetnacl](https://github.com/philanc/luatweetnacl) - 绑定到tweetnacl，现代高安全性加密库.
- [luaossl](https://github.com/wahern/luaossl) - “Lua宇宙中最全面的OpenSSL模块” - 由lapis，kong和lua-http使用.


### Network
- [LuaSocket](https://github.com/diegonehab/luasocket) - 网络扩展，为TCP和UDP提供套接字API，并实现HTTP，FTP和SMTP.
- [lua-websockets](https://github.com/lipp/lua-websockets)   -  WebSocket客户端和服务器模块.  与Web服务器无关，在Lua的LuaSocket上实现.
- [lua-cURLv3](https://github.com/Lua-cURL/Lua-cURLv3) -  Lua绑定到libcurl.
- [lua-http](https://github.com/daurnimator/lua-http)   - 具有客户端和服务器API，TLS和HTTP / 2的异步HTTP和WebSocket库;  基于cqueues.


### Data Stores
- [LuaSQL](http://keplerproject.github.io/luasql/) - 用于连接ODBC，ADO，Oracle，MySQL，SQLite和PostgreSQL的简单界面.
- [pgmoon](https://github.com/leafo/pgmoon) - 用于OpenResty，LuaSocket和cqueues的Lua PostgreSQL驱动程序.
- [lua-resty-mysql](https://github.com/openresty/lua-resty-mysql) - 用于OpenResty的Lua MySQL驱动程序.
- [lua-resty-cassandra](https://github.com/jbochi/lua-resty-cassandra) -  Lua Cassandra OpenResty和其他人的客户端驱动程序.
-  Redis
  - [redis-lua](https://github.com/nrk/redis-lua) -  Redis的Pure Lua客户端库.
  - [lua-resty-redis](https://github.com/openresty/lua-resty-redis) -  Lua Redis OpenResty的客户端驱动程序.
  - [lredis](https://github.com/daurnimator/lredis)   - 具有流水线和Pub / Sub支持的异步Redis客户端;  基于cqueues.


### Message Brokers
- [lua-zmq](https://github.com/Neopallium/lua-zmq) - Lua bindings to ZeroMQ.
- [lzmq](https://github.com/zeromq/lzmq) - 更新的Lua绑定到ZeroMQ.
- [lua-resty-kafka](https://github.com/doujiang24/lua-resty-kafka) - 基于OpenResty cosockets的Kafka客户端驱动程序.
- [lua-resty-rabbitmqstomp](https://github.com/wingify/lua-resty-rabbitmqstomp) - 基于OpenResty cosockets的RabbitMQ客户端库.


### Testing
- [busted](http://olivinelabs.com/busted/) -  BDD风格的单元测试框架，具有出色的文档和Moonscript支持.
- [telescope](https://github.com/norman/telescope) - 灵活且高度可定制的测试库.
- [luassert](https://github.com/Olivine-Labs/luassert) - 断言库扩展了Lua的内置断言.
- [lust](https://github.com/bjornbytes/lust) - 最小的测试框架.


### Foreign Function Interfaces
- [LuaJIT FFI](http://luajit.org/ext_ffi.html) -  LuaJIT调用外部C函数和使用纯Lua代码中的C数据结构的机制.
- [luaffi](https://github.com/jmckaskill/luaffi) - 独立FFI库，与LuaJIT FFI接口兼容.


### Analysis Tools and ASTs
- [luadec51](https://github.com/sztupy/luadec51) -  Lua版本5.1的Lua Decompiler.
- [luacov](http://keplerproject.github.io/luacov/) - 简单的覆盖分析仪，被破坏和望远镜用于检查测试覆盖范围.
  - [luacov-coveralls](https://github.com/moteus/luacov-coveralls) -  LuaCov记者为coveralls.io.
- [luacheck](https://github.com/mpeterv/luacheck) - 简单的静态分析仪，可以检测偶然的全局变量和未定义或阴影的局部变量.
- [Metalua](https://github.com/fab13n/metalua)   - 纯Lua解析器和编译器，用于生成AST.  许多其他工具以这种方式使用Metalua解析器.
- [LuaInspect](https://github.com/davidm/lua-inspect)   -  Lua最强大的代码分析和linting工具，基于Metalua构建.  由ZeroBraneStudio等人使用.
- [LuaMinify](https://github.com/stravant/LuaMinify) -  Minifier，它还带有自己的静态分析工具，词法分析器和解析器.
- [Typed Lua](https://github.com/andremm/typedlua) - 一个Lua的打字超集，编译成普通的Lua.
- [lua-parser](https://github.com/andremm/lua-parser) - 使用LPegLabel编写的Lua 5.3解析器，具有改进的错误消息.


### Experimental, etc
- [punchdrunk.js](https://github.com/TannerRogalsky/punchdrunk) -  Moonshine +LÖVEAPI重新实现=在浏览器中运行LÖVE游戏.
- [luvit](https://github.com/luvit/luvit) -  Node.js的底层架构（libUV），顶部是Lua而不是JavaScript.
- [graphql-lua](https://github.com/bjornbytes/graphql-lua) -  Lua的实现 [GraphQL](http://graphql.org/).


### Scriptable by Lua
- [luakit](https://luakit.github.io/luakit/) -  Lua可扩展的基于webkit的快速，小型，基于Webkit的浏览器框架.
- [Hammerspoon](http://www.hammerspoon.org)   - 功能强大，可扩展的OS X自动化工具.  社区维护的分支 [Mjolnir](http://www.mjolnir.io/).
- [kpie](https://github.com/skx/kpie) - 用于处理窗口的脚本实用程序.
- [lumail](https://lumail.org/) - 基于控制台的邮件客户端，具有广泛的脚本功能.
- [AwesomeWM](https://awesomewm.org/) - 一个高度可配置和可扩展的X窗口管理器，由Lua编写和配置.
- [Textadept](https://foicica.com/textadept/) - 非常轻量级，可定制的跨平台编辑器，（大部分）编写（由Lua编写）.
- [KoReader](https://github.com/koreader/koreader) - 电子书阅读器应用程序支持PDF，DJVU，EPUB，FB2等，可在Kindle，Kobo，PocketBook和Android设备上运行.


### Miscellaneous
- [MoonScript](http://moonscript.org/)   -  Moonscript是一种动态脚本语言，可编译为Lua.  它减少了冗长，并提供了丰富的功能，如理解和类.  它的作者称它为&#39;CoffeeScript for Lua&#39;.
- [sitegen](http://leafo.net/sitegen/) - 一个静态站点生成器，它使用MoonScript并支持HTML和Markdown，页面分组和插件.


## Resources

### Community
- [lua-l](http://www.lua.org/lua-l.html) - 官方Lua邮件列表，以及Lua社区的焦点之一.
- [Lua.Space](http://lua.space/) -  Lua社区博客.
- [Lua Users Foundation](https://github.com/lua-users-foundation) - 个人协会，其使命是支持和促进Lua及其社区和生态系统.
- [lua-users.org](http://lua-users.org/) -  Lua用户的网站，包括IRC频道，lua-l的网络存档和大型wiki.
- 会议/聚会
  - [Lua Workshop](https://www.lua.org/community.html#workshop) -  Lua社区为期2天的年度会议，轮流地点.
  - [Lua Conf](http://luaconf.com/) - 在巴西举行的为期一天的Lua会议.
  - [FOSDEM](https://fosdem.org/) - 在布鲁塞尔举行的为期两天的F / OSS开发人员聚会，有时会有一个“Lua devroom”.


### References
- [Reference Manual](http://www.lua.org/manual/5.3/) -  Lua语言的官方定义.
- [lua-users wiki](http://lua-users.org/wiki/) - 社区维护的大量Lua信息和资源，是官方网站的补充.
- [Lua Unofficial FAQ](http://www.luafaq.org/) - 回答各种与Lua相关的问题，包括许多形式的“如何做” ___?'.


### Glossaries
- [Lua 5.3 Glossary](https://rawgit.com/dlaurie/lua-notes/master/glossary.html) - 一些基本Lua术语的词汇表.


### Style Guides
- [Lua-users style guide](http://lua-users.org/wiki/LuaStyleGuide)   - 一般的高级风格指南;  不受欢迎，容易同意.
- [Olivine style guide](https://github.com/Olivine-Labs/lua-style-guide) - 更具见解性和具体性，因此更严格的指南.


### Tutorials
- [Lua Crash Course](http://www.coppeliarobotics.com/helpFiles/en/luaCrashCourse.htm) - 短暂的速成课程读取，或您忘记基础知识的参考.
- [Learn Lua in 15 Minutes](http://tylerneylon.com/a/learn-lua/) - 一个评论很好的示例文件，涵盖了基础知识.
- [Learning Lua from JS](http://phrogz.net/lua/LearningLua_FromJS.html)   -  Lua和JS之间的相同点和不同点的概述;  对于希望选择Lua的JavaScript人来说，这是一个很好的开始.
- [lua-users tutorial](http://lua-users.org/wiki/LuaTutorial) - 深入收集针对新移民的教程.
- [Lua Missions](https://github.com/kikito/lua_missions) - 一系列“使命”，旨在教授Lua的各个方面.
- [Creating an Image Server](http://leafo.net/posts/creating_an_image_server.html)   - 通过设置和使用OpenResty来构建一个简单的图像处理服务器;  使用OpenResty的一个很好的起点.


### Articles
- [Embedding Lua in C](https://debian-administration.org/article/264/Embedding_a_scripting_language_inside_your_C/C_code)   - 将Lua嵌入C程序的入门演练.  有点过时了，但仍然是一个很棒的演练.
- [Lua: Good, bad, and ugly parts](http://notebook.kulchenko.com/programming/lua-good-different-bad-and-ugly-parts) - 由ZeroBraneStudio的作者全面总结Lua的优点，不同，不良和丑陋的方面，包括许多微妙的怪癖.
- [Lua states, libraries, coroutines and memory](http://www.thijsschreijer.nl/blog/?p=693) - 图表并解释了一些更高级的Lua VM概念，特别是在与C接口时.


### Talks & Slides
- [Roberto's Talks](http://www.inf.puc-rio.br/~roberto/talks/index.html) -  Lua首席建筑师提供的谈话历史，每个都有幻灯片.
- [Lua Workshop Talks](http://www.lua.org/wshop14.html#abstracts) - 每年〜每年一次的Lua研讨会都会举办高质量的讲座，其中包括在线的幻灯片，包括幻灯片.


### Books
- [Programming in Lua](http://www.lua.org/pil/)   -  Lua编程的所有方面的权威介绍，由Lua的首席架构师编写.  三个版本发布;  第一版在线提供.
- [Lua Quick Reference](https://foicica.com/lua/) - 由Textadept的创建者快速参考如何编程和嵌入Lua 5.1到5.3.
- [Programming Gems](http://www.lua.org/gems/) - 一系列文章，涵盖了各种用例中Lua编程良好的现有智慧和实践.
- [Lua Programming](https://en.wikibooks.org/wiki/Lua_Programming) - 简短的语言概述，Lua 5.2的最新版本，以及在线提供.


### Other Lists
- [awesome-resty](https://github.com/bungle/awesome-resty) - 像这样的列表，但专注于OpenResty.
- [awesome-love2d](https://github.com/love2d-community/awesome-love2d) - 像这样的列表，但专注于游戏开发和LÖVE平台.
- [Where Lua is Used](https://sites.google.com/site/marbux/home/where-lua-is-used) - 使用Lua编写或可扩展的独立程序的完整列表.


## Contribute

 欢迎和希望的贡献！  阅读 [contribution guidelines](https://github.com/LewisJEllis/awesome-lua/blob/master/contributing.md) 第一.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，Lewis Ellis已放弃所有版权及相关或相邻的权利.
