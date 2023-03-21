<div class="github-widget" data-repo="LewisJEllis/awesome-lua"></div>
## Awesome Lua [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 精选的优质 Lua 列表 [packages](#packages) 和 [resources](#resources).

受列表启发 [awesome](https://github.com/sindresorhus/awesome), [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)， 和 [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs).


## Packages


## Resources


### Implementations, Interpreters, and Bindings
- [Lua](http://www.lua.org/download.html) - Lua 的原始 ANSI C 解释器.
  - [Lua Repo](https://github.com/lua/lua) - Lua 团队看到的官方 Lua 回购镜像到 GitHub.
- [LuaJIT](http://luajit.org/luajit.html) - 用于 Lua 的高性能即时编译器.
- [LLVM-Lua](https://github.com/neopallium/llvm-lua) - 将 Lua 编译为 LLVM.
- [lua.vm.js](https://github.com/daurnimator/lua.vm.js)  - 网络上的 Lua 虚拟机； 通过 LLVM、emscripten 和 asm.js 的 C 解释器的直接端口.
- [Moonshine](https://github.com/gamesys/moonshine)  - 用 Ja​​vaScript 实现的 Lua 虚拟机. 比 lua.vm.js 慢，但有更好的文档、示例和 JS 接口.
- [Fengari](https://fengari.io/) - 用 Ja​​vascript 重写的 Lua VM，具有无缝的 JS 和 DOM 互操作性.
- [MoonSharp](https://github.com/xanathar/moonsharp) - A Lua interpreter written entirely in C# for the .NET, Mono and Unity platforms.
- [UniLua](https://github.com/xebecnan/UniLua) - A pure C# implementation of Lua 5.2, focused on compatibility with the Unity game engine.
- [lupa](https://github.com/scoder/lupa) - Python 绑定到 LuaJIT2.
- [golua](https://github.com/aarzilli/golua) - Golang 绑定到 Lua C API.
- [GopherLua](https://github.com/yuin/gopher-lua) - 使用 Go API 在 Go 中实现的 Lua 5.1 VM 和编译器.
- [LuaBridge](https://github.com/vinniefalco/LuaBridge) - 用于在 C++ 和 Lua 之间来回映射数据、函数和类的轻量级库.

注意：从 LuaJIT 到 Lua，再到 lua.vm.js 再到 Moonshine，一个基本的基准测试表明，每跳一次，性能大约下降 6 倍.


### Package Managers
- [LuaRocks](https://luarocks.org/)  - 用于将 Lua 模块安装为名为“rocks”的包的实际工具，以及公共 rock 存储库和网站. 很像 npm 或 pip.


### Build Tools and Standalone Makers
- [Lake](https://github.com/stevedonovan/Lake) - 一个用 Lua 编写的构建引擎，类似于 Ruby 的 rake.
- [Luabuild](https://github.com/stevedonovan/luabuild) - 高度可定制的 Lua 5.2 构建系统.
- [luastatic](https://github.com/ers35/luastatic) - 将 Lua 程序转换为独立可执行文件的简单工具.
- [omnia](https://github.com/tongson/omnia) - 内置电池的独立可执行文件创建器，构建于 luastatic 之上.


### Debugging and Profiling
- [ProFi](https://gist.github.com/perky/2838755) - 与 LuaJIT 一起使用并生成报告文件的简单分析器.
- [luatrace](https://github.com/geoffleyland/luatrace) - 用于跟踪/分析/剖析脚本执行和生成详细报告的工具集.
- [StackTracePlus](https://github.com/ignacio/StackTracePlus) - 直接升级到 Lua 的堆栈跟踪，添加本地上下文并提高可读性.
- [MobDebug](https://github.com/pkulchenko/MobDebug)  - 具有断点和堆栈检查功能的强大远程调试器. 由 ZeroBraneStudio 使用.
- [lovebird](https://github.com/rxi/lovebird)  - 基于浏览器的调试控制台. 最初是为 LÖVE 制作的，但适用于任何支持 LuaSocket 的项目.


### IDEs and Plugins
- [Lua Development Tools](https://eclipse.org/ldt/)  - 提供代码完成、调试等功能的 Eclipse 插件. 建立在 Metalua 之上.
- [Lua for IDEA](https://bitbucket.org/sylvanaar2/lua-for-idea/wiki/Home) - IntelliJ IDEA 插件，除其他功能外，还提供代码完成、智能突出显示和实验调试.
- [ZeroBraneStudio](https://studio.zerobrane.com/)  - 轻量级、可定制、跨平台的 Lua 专用 IDE，具有代码完成和分析功能，用 Lua 编写. 为众多 Lua 引擎提供广泛的调试支持.
- [BabeLua](https://archive.codeplex.com/?p=babelua) - VS2012-13 的 Lua 编辑器/调试器扩展，具有突出显示、自动完成、linting 和格式化功能.
- [lua-mode](https://github.com/immerrr/lua-mode) - 用于编辑 Lua 的 Emacs 主要模式.
- [vscode-lua](https://github.com/trixnz/vscode-lua) - VSCode 智能感知和 linting.


### Utility Belts
- [Lua Fun](https://github.com/luafun/luafun) - 专为 LuaJIT 设计的高性能函数式编程库.
- [Moses](https://github.com/Yonaba/Moses) - 受 Underscore.js 启发的函数式编程实用工具带.
- [Penlight](https://github.com/stevedonovan/Penlight)  - 广泛、重量级的实用程序库，灵感来自 Python 的标准库. 提供 Lua 没有的电池.
- [lua-stdlib](https://github.com/lua-stdlib/lua-stdlib)  - 中量级标准库扩展； 添加一些有用的数据结构、实用函数和基本功能的东西.
- [Microlight](https://github.com/stevedonovan/Microlight)  - 一个有用的 Lua 函数库；  Penlight 的“超轻”版本.
- [compat53](https://luarocks.org/modules/siffiejoe/compat53) - 为 Lua 5.2 和 5.1 提供 Lua-5.3 风格 API 的兼容性模块.
- [RxLua](https://github.com/bjornbytes/RxLua) - 响应式扩展、Observables 等


### Game Engines
- [LÖVE 2D](http://love2d.org/)  - 桌面游戏开发平台. 跨平台，功能齐全，被广泛采用.
- [Corona SDK](https://coronalabs.com/)  - 适用于 iOS 和 Android 的开发平台. 专有，但被众多顶级游戏和应用程序使用，总下载量超过 1.5 亿次.
- [MOAI](http://getmoai.com/)  - 开源、跨平台、手机游戏开发框架. 由 Lua 脚本支持的极简 C++ 引擎.
- [Drystal](https://drystal.github.io/) - 开源，游戏可以在 Linux 或任何具有最新网络浏览器的平台上运行.
- [Amulet](http://www.amulet.xyz/)  - 适用于小型游戏和实验的开源、音频/视频工具包. 它可以在 Windows、Mac、Linux、HTML5 和 iOS 上运行.
- [LÖVR](https://lovr.org) - 用于创建虚拟现实体验的 3D 框架，灵感来自 LÖVE 2D.


### Game Development
- 电晕
  - [Coronium](https://develephant.github.io/coronium-core-docs/) - 支持分析、数据对象、用户管理等的简单云平台.
- 狮子
  - [awesome-love2d](https://github.com/love2d-community/awesome-love2d) - 像这样的列表，但侧重于游戏开发和 LÖVE 平台.
  - [lurker](https://github.com/rxi/lurker) - 通过在运行的 LÖVE 项目中自动交换更改的 Lua 文件来缩短迭代周期.
  - [HUMP](http://vrld.github.io/hump/)  - 一组 LÖVE 的轻量级助手； 面向游戏的实用腰带.
- 美丽
  - [moaifiddle](https://moaifiddle.com) - 编辑和分享 MOAI 游戏引擎的短脚本，并使用 WebGL 在浏览器中运行它们.
- [Jumper](https://github.com/Yonaba/Jumper) - 用于基于网格的游戏的快速、轻量级且易于使用的寻路库.
- [lume](https://github.com/rxi/lume/) - 面向游戏开发的实用腰带库.
- [NoobHub](https://github.com/Overtorment/NoobHub) - Corona、LÖVE 等网络多人游戏，遵循简单的发布-订阅模型.
- 碰撞检测
  - [bump.lua](https://github.com/kikito/bump.lua) - 最小的基于矩形的碰撞检测，处理隧道和基本的碰撞解决.
  - [HardonCollider](http://vrld.github.io/HardonCollider/) - 检测任意类型的任意位置和旋转形状之间的碰撞.
- 补间
  - [flux](https://github.com/rxi/flux) - 一个快速、轻量级的 Lua 补间库，具有缓动功能和将补间组合在一起的能力.
  - [tween.lua](https://github.com/kikito/tween.lua) - 用于补间的小型库，具有多种缓动功能.
- 例子
  - [termtris](https://github.com/tylerneylon/termtris) - 俄罗斯方块克隆，以文学风格编写，“强调从能力中学习”.
  - [PacPac](https://github.com/tylerneylon/pacpac) - 用 LÖVE 制作的吃豆人克隆版.
  - [Mari0](https://github.com/Stabyourself/mari0)  - Mario 和 Portal 的融合，由 LÖVE 制作. 另见其 [wikipedia entry](https://en.wikipedia.org/wiki/Mari0).
  - [Journey to the Center of Hawkthorne](https://github.com/hawkthorne/hawkthorne-journey) - 基于社区的 2D 平台游戏 [Digital Estate Planning](https://en.wikipedia.org/wiki/Digital_Estate_Planning) 剧集，由 LÖVE 制作.


### Logging
- [lua-log](https://github.com/moteus/lua-log) - 异步日志库，带有用于文件系统、网络、ZeroMQ 等的可插入编写器.
- [LuaLogging](https://github.com/Neopallium/lualogging) - 支持各种附加程序的受 Log4j 启​​发的日志记录库.
- [luasyslog](https://luarocks.org/modules/luarocks/luasyslog) - 记录到系统日志，基于 LuaLogging.


### Web/Networking Platforms
- [OpenResty](http://openresty.org/en/)  - 通过使用 Lua 扩展 Nginx 创建的快速且可扩展的 Web 应用程序平台.  Cloudflare、淘宝、腾讯等广泛使用的当今事实上的 Lua 网络平台.
- [turbo](https://turbo.readthedocs.io/en/latest/) - 受 Tornado 启发的事件驱动、非阻塞、基于 LuaJIT 的网络套件和框架.
- [Kepler Project](https://github.com/keplerproject) - 使用一组通用标准和组件的面向 Web 的项目的集合.
- [Pegasus.lua](https://github.com/EvandroLG/pegasus.lua) - Pegasus.lua 是一个 http 服务器，用于处理用 Lua 语言编写的 Web 应用程序.


### OpenResty
- [awesome-resty](https://github.com/bungle/awesome-resty) - 像这样的列表，但专注于 OpenResty.
- 核心平台
  - [ngx_lua](https://www.nginx.com/resources/wiki/modules/lua/)  - OpenResty 的核心部分. 在 Nginx 中嵌入 Lua，并公开了用于非阻塞套接字的 cosocket API（与 LuaSocket 的 API 兼容）.
  - [OpenResty GitHub Organization](https://github.com/openresty) - ngx_lua、ngx_openresty 和许多相关模块的存储库主页.
- 第三方模块
  - [lua-resty-http](https://github.com/pintsized/lua-resty-http) - Lua HTTP 客户端驱动程序，基于 cosocket API 构建.
- 框架和工具
  - [Lapis](http://leafo.net/lapis/)  - Lua 和 OpenResty 的全栈框架. 就像 Django 或 Lua 的 Rails. 支持月亮脚本.
  - [ledge](https://github.com/pintsized/ledge) - Lua 模块提供可编写脚本的、符合 RFC 标准的 HTTP 缓存功能.
  - [Sailor](https://github.com/sailorproject/sailor) — 与 OpenResty、Apache 和其他网络服务器兼容的 MVC 网络框架.
  - [Kong](https://github.com/Kong/kong) - 微服务和 API 管理层.

在这个页面中搜索“OpenResty”以在其他类别（尤其是数据存储）下找到相关包.


### Command-line Utilities
- [ansicolors](https://github.com/kikito/ansicolors.lua) - Simple function for printing to the console in color.
- [cliargs](https://github.com/amireh/lua_cliargs) - 一个简单的命令行参数解析模块.
- [lua-term](https://github.com/hoelzro/lua-term) - 终端操作和操纵.
- [argparse](https://github.com/mpeterv/argparse) - 受 argparse for Python 启发的功能丰富的命令行解析器.

### Concurrency and Multithreading
- 基于协程的多任务处理：
  - [Lumen](https://github.com/xopxe/Lumen) - 简单的并发任务调度.
  - [ConcurrentLua](https://github.com/lefcha/concurrentlua) - 实现 Erlang 风格的消息传递并发模型.
  - [cqueues](http://25thandclement.com/~william/projects/cqueues.html) - 用于基于协程事件循环管理套接字、信号和线程的库.
- 多线程：
  - [llthreads](https://github.com/Neopallium/lua-llthreads) - 低级 pthreads 和 WIN32 线程的简单包装器.
  - [llthreads2](https://github.com/moteus/lua-llthreads2) - 更新的 llthreads 重写.
  - [lanes](https://github.com/LuaLanes/lanes) - 实现消息传递模型的库，每个 Lua 线程有一个 OS 线程.
  - [luaproc](https://github.com/askyrme/luaproc)  - 消息传递模型，允许每个操作系统线程有多个线程，并且可以轻松地在网络中推广. 也可以看看 [the paper](http://www.inf.puc-rio.br/~roberto/docs/ry08-05.pdf) 它起源于哪里.

有关差异的更多信息（特别是 `lanes` 和 `luaproc` 之间的差异），请参阅此 [comparison](http://www.luteus.biz/Download/LoriotPro_Doc/LUA/LUA_For_Windows/lanes/comparison.html) 选项； 有些过时，但涵盖了每一个的工作原理和显着差异.


### Templating
- [lustache](http://olivinelabs.com/lustache/) - 小胡子模板实施.
- [etlua](https://github.com/leafo/etlua) - 嵌入式 Lua 模板，ERB 风格.
- [lua-resty-template](https://github.com/bungle/lua-resty-template) - 面向 Lua 的 OpenResty 模板引擎，有点像 Jinja.


### Documentation
- [LDoc](http://stevedonovan.github.io/ldoc/) - 现代化和扩展的文档生成器 [LuaDoc](http://keplerproject.github.io/luadoc/).
- [Locco](http://rgieseke.github.io/locco/) - Lua端口 [Docco](http://ashkenas.com/docco/)，“快捷、百行、精通编程风格的文档生成器”.
- [docroc](https://github.com/bjornbytes/docroc) - 将注释解析为 Lua 表以生成文档.


### Object-oriented Programming
- [30log](https://github.com/Yonaba/30log) - 在 30 行中包含基本类、继承和混合的极简 OOP 库.
- [middleclass](https://github.com/kikito/middleclass) - 简单但强大的 OOP 库，具有继承、方法、元方法、类变量和混合.


### File system and OS
- [LuaFileSystem](http://keplerproject.github.io/luafilesystem/) - 扩展和补充了 Lua 的内置文件系统功能集.
- [luaposix](https://github.com/luaposix/luaposix) - POSIX API 的绑定，包括 curses.
- [lunix](http://25thandclement.com/~william/projects/lunix.html) - 绑定到常见的 Unix 系统 API，争取线程安全.
- [lua-path](https://github.com/moteus/lua-path) - 文件系统路径操作库.


### Time and Date
- [LuaDate](https://github.com/Tieske/date) - 具有解析、格式化、加法/减法、本地化和 ISO 8601 支持的日期和时间模块.
- [cron.lua](https://github.com/kikito/cron.lua) - 受 JavaScript 的 setTimeout 和 setInterval 启发的 Lua 时间相关函数.
- [luatx](https://github.com/daurnimator/luatz) - 时间、日期和时区库.


### Image Manipulation
- [magick](https://github.com/leafo/magick) - Lua 绑定到 ImageMagick for LuaJIT 使用 FFI.


### Digital Signal Processing
- [LuaFFT](https://github.com/h4rm/luafft) - 一个简单易用的纯 Lua 快速傅立叶变换包.
- [Worp](http://worp.zevv.nl/about.html) - 为 LuaJIT 编写的声音/音乐/DSP 引擎.


### Hardware and Embedded Systems
- [eLua](http://www.eluaproject.net/) - Lua，通过优化和特定功能进行扩展，以实现高效和可移植的嵌入式软件开发.


### Math and Scientific Computing
- [SciLua](http://scilua.org/) - 基于 LuaJIT 构建的数值/科学计算框架，具有与 R 的接口.
- [Torch7](http://torch.ch/) - 广泛支持机器学习算法的科学计算框架，被 Facebook、谷歌等使用.
- [lhf's Lua Tools](http://webserver2.tecgraf.puc-rio.br/~lhf/ftp/lua/) - 各种库和工具，许多与数学或数据相关.


### Parsing and Serialization
- JSON
  - [lua-cjson](https://github.com/mpx/lua-cjson/) - 在 C 中实现并暴露给 Lua 的超快 JSON 编码/解码.
  - [luajson](https://github.com/harningt/luajson) - 在 LPeg 之上的 Lua 中实现的 JSON 编码器/解码器.
  - [dkjson](http://dkolf.de/src/dkjson-lua.fsl/home) - 在纯 Lua 中实现的 JSON 编码器/解码器.
  - [json.lua](https://github.com/rxi/json.lua) - 纯 Lua 中快速而小巧的 JSON 库.
- XML
  - [LuaExpat](https://matthewwild.co.uk/projects/luaexpat/) - 通过绑定到 Expat 库的 SAX XML 解析器.
  - [SLAXML](https://github.com/Phrogz/SLAXML) - 纯 Lua SAX 类流式 XML 解析器.
- 消息包
  - [lua-MessagePack](https://github.com/fperrad/lua-MessagePack) - MessagePack 的纯 Lua 实现.
  - [lua-cmsgpack](https://github.com/antirez/lua-cmsgpack) - Redis 使用的带有 Lua 绑定的 MessagePack C 实现.=
- LPEG
  - [LPeg](http://www.inf.puc-rio.br/~roberto/lpeg/) - 基于解析表达式语法的 Lua 模式匹配库.
  - [lpeg_patterns](https://github.com/daurnimator/lpeg_patterns) - LPeg 模式的集合.
  - [LuLPeg](https://github.com/pygy/LuLPeg) - A pure Lua implementation of LPeg v0.12.
  - [LPegLJ](https://github.com/sacek/LPegLJ) - LPeg v1.0 的纯 LuaJIT 实现.
  - [LPegLabel](https://github.com/sqmedeiros/lpeglabel) - LPeg 的扩展，增加了对标记故障的支持.
- [lyaml](https://github.com/gvvaughan/lyaml) - YAML encoding/decoding via binding to LibYAML.
- [lunamark](https://github.com/jgm/lunamark)  - 将 Markdown 转换为其他文本格式，包括 HTML 和 LaTeX. 使用 LPeg 进行快速解析.
- [LXSH](https://github.com/xolox/lua-lxsh) - 用 LPeg 编写的词法分析器和语法高亮器的集合.
- [lua-pb](https://github.com/Neopallium/lua-pb) - 协议缓冲区实施.


### Humanize
- [i18n.lua](https://github.com/kikito/i18n.lua) - 具有语言环境、格式和多元化的国际化库.
- [inspect.lua](https://github.com/kikito/inspect.lua) - Lua 表的人类可读表示.
- [serpent](https://github.com/pkulchenko/serpent) - 序列化器和漂亮的打印机.
- [Ser](https://github.com/gvx/Ser) - 具有良好性能的简单序列化程序.
- [say](https://github.com/Olivine-Labs/say) - 用于 i18n 的简单字符串键值存储.


### Compression
- [lua-zlib](https://github.com/brimworks/lua-zlib) - 用于 gzip/gunzip 的 zlib 的简单流接口.
- [lua-zip](https://github.com/brimworks/lua-zip)  - Lua 绑定到 libzip. 读取和写入 zip 文件.


### Cryptography
- [LuaCrypto](https://github.com/mkottman/luacrypto) - Lua 绑定到 OpenSSL.
- [lua-lockbox](https://github.com/somesocks/lua-lockbox) - 用纯 Lua 编写的密码原语集合.
- [luatweetnacl](https://github.com/philanc/luatweetnacl) - 绑定到 tweetnacl，现代高安全性密码库.
- [luaossl](https://github.com/wahern/luaossl) - “Lua 宇宙中最全面的 OpenSSL 模块” - 由 lapis、kong 和 lua-http 使用.


### Network
- [LuaSocket](https://github.com/diegonehab/luasocket) - 为 TCP 和 UDP 提供套接字 API 并实现 HTTP、FTP 和 SMTP 的网络扩展.
- [lua-websockets](https://github.com/lipp/lua-websockets)  - WebSocket 客户端和服务器模块. 与 Web 服务器无关，在 LuaSocket 之上的 Lua 中实现.
- [lua-cURLv3](https://github.com/Lua-cURL/Lua-cURLv3) - Lua 绑定到 libcurl.
- [lua-http](https://github.com/daurnimator/lua-http)  - 具有客户端和服务器 API、TLS 和 HTTP/2 的异步 HTTP 和 WebSocket 库； 基于cqueues.


### Data Stores
- [LuaSQL](http://keplerproject.github.io/luasql/) - 用于连接到 ODBC、ADO、Oracle、MySQL、SQLite 和 PostgreSQL 的简单界面.
- [pgmoon](https://github.com/leafo/pgmoon) - 用于 OpenResty、LuaSocket 和 cqueue 的 Lua PostgreSQL 驱动程序.
- [lua-resty-mysql](https://github.com/openresty/lua-resty-mysql) - 用于 OpenResty 的 Lua MySQL 驱动程序.
- [lua-resty-cassandra](https://github.com/jbochi/lua-resty-cassandra) - OpenResty 和其他的 Lua Cassandra 客户端驱动程序.
- 雷迪斯
  - [redis-lua](https://github.com/nrk/redis-lua) - Redis 的纯 Lua 客户端库.
  - [lua-resty-redis](https://github.com/openresty/lua-resty-redis) - OpenResty 的 Lua Redis 客户端驱动程序.
  - [lredis](https://github.com/daurnimator/lredis)  - 具有流水线和 Pub/Sub 支持的异步 Redis 客户端； 基于cqueues.


### Message Brokers
- [lua-zmq](https://github.com/Neopallium/lua-zmq) - Lua 绑定到 ZeroMQ.
- [lzmq](https://github.com/zeromq/lzmq) - 更新的 Lua 绑定到 ZeroMQ.
- [lua-resty-kafka](https://github.com/doujiang24/lua-resty-kafka) - 基于 OpenResty cosockets 的 Kafka 客户端驱动程序.
- [lua-resty-rabbitmqstomp](https://github.com/wingify/lua-resty-rabbitmqstomp) - 基于 OpenResty cosockets 的 RabbitMQ 客户端库.


### Testing
- [busted](http://olivinelabs.com/busted/) - BDD 风格的单元测试框架，具有出色的文档和 Moonscript 支持.
- [telescope](https://github.com/norman/telescope) - 灵活且高度可定制的测试库.
- [luassert](https://github.com/Olivine-Labs/luassert) - 扩展 Lua 内置断言的断言库.
- [lust](https://github.com/bjornbytes/lust) - 最小的测试框架.


### Foreign Function Interfaces
- [LuaJIT FFI](http://luajit.org/ext_ffi.html) - LuaJIT 从纯 Lua 代码调用外部 C 函数和使用 C 数据结构的机制.
- [luaffi](https://github.com/jmckaskill/luaffi) - 独立的 FFI 库，与 LuaJIT FFI 接口兼容.


### Analysis Tools and ASTs
- [luadec51](https://github.com/sztupy/luadec51) - Lua 5.1 版的 Lua 反编译器.
- [luacov](http://keplerproject.github.io/luacov/) - 简单的覆盖分析器，被 busted 和 telescope 用来检查测试覆盖率.
  - [luacov-coveralls](https://github.com/moteus/luacov-coveralls) - coveralls.io 的 LuaCov 记者.
- [luacheck](https://github.com/mpeterv/luacheck) - 简单的静态分析器，可检测意外的全局变量和未定义或隐藏的局部变量.
- [Metalua](https://github.com/fab13n/metalua)  - 纯 Lua 解析器和编译器，用于生成 AST. 许多其他工具以这种方式使用 Metalua 解析器.
- [LuaInspect](https://github.com/davidm/lua-inspect)  - Lua 最强大的代码分析和 linting 工具，基于 Metalua 构建. 由 ZeroBraneStudio 等使用.
- [LuaMinify](https://github.com/stravant/LuaMinify) - Minifier，它还带来了自己的静态分析工具、词法分析器和解析器.
- [Typed Lua](https://github.com/andremm/typedlua) - 编译为纯 Lua 的 Lua 类型超集.
- [lua-parser](https://github.com/andremm/lua-parser) - 使用 LPegLabel 编写的 Lua 5.3 解析器，改进了错误消息.


### Experimental, etc
- [punchdrunk.js](https://github.com/TannerRogalsky/punchdrunk) - Moonshine + LÖVE API 重新实现 = 在浏览器中运行 LÖVE 游戏.
- [luvit](https://github.com/luvit/luvit) - Node.js 的底层架构 (libUV)，顶部是 Lua 而不是 JavaScript.
- [graphql-lua](https://github.com/bjornbytes/graphql-lua) - Lua 实现 [GraphQL](http://graphql.org/).


### Scriptable by Lua
- [luakit](https://luakit.github.io/luakit/) - 快速、小型、基于 webkit 的浏览器框架，可由 Lua 扩展.
- [Hammerspoon](http://www.hammerspoon.org)  - 一个强大的、可扩展的 OS X 自动化工具. 一个社区维护的分支 [Mjolnir](http://www.mjolnir.io/).
- [kpie](https://github.com/skx/kpie) - 用于处理窗口的脚本实用程序.
- [lumail](https://lumail.org/) - 基于控制台的邮件客户端，具有广泛的脚本功能.
- [AwesomeWM](https://awesomewm.org/) - 一个高度可配置和可扩展的 X 窗口管理器，由 Lua 编写和配置.
- [Textadept](https://foicica.com/textadept/) - 极其轻量级、可定制、跨平台的编辑器，（大部分）用 Lua 编写（并由脚本编写）.
- [KoReader](https://github.com/koreader/koreader) - 电子书阅读器应用程序支持 PDF、DJVU、EPUB、FB2 等，可在 Kindle、Kobo、PocketBook 和 Android 设备上运行.


### Miscellaneous
- [MoonScript](http://moonscript.org/)  - Moonscript 是一种编译为 Lua 的动态脚本语言. 它减少了冗长并提供了一组丰富的功能，如理解和类. 它的作者称之为“CoffeeScript for Lua”.
- [sitegen](http://leafo.net/sitegen/) - 使用 MoonScript 并支持 HTML 和 Markdown、页面分组和插件的静态站点生成器.


## Resources

### Community
- [lua-l](http://www.lua.org/lua-l.html) - 官方 Lua 邮件列表，也是 Lua 社区的焦点之一.
- [Lua.Space](http://lua.space/) - Lua 社区博客.
- [Lua Users Foundation](https://github.com/lua-users-foundation) - 以支持和促进 Lua 及其社区和生态系统为使命的个人协会.
- [lua-users.org](http://lua-users.org/) - 一个供 Lua 用户使用的站点，具有 IRC 频道、lua-l 网络存档和大型 wiki.
- 会议/聚会
  - [Lua Workshop](https://www.lua.org/community.html#workshop) - 每年 2 天的 Lua 社区会议，轮流举行.
  - [Lua Conf](http://luaconf.com/) - 在巴西举行的为期 1 天的年度 Lua 会议.
  - [FOSDEM](https://fosdem.org/) - 在布鲁塞尔举行的为期 2 天的 F/OSS 开发人员年度聚会，有时会有一个“Lua 开发室”.


### References
- [Reference Manual](http://www.lua.org/manual/5.3/) - Lua 语言的官方定义.
- [lua-users wiki](http://lua-users.org/wiki/) - 大量由社区维护的 Lua 信息和资源集合，补充了官方网站.
- [Lua Unofficial FAQ](http://www.luafaq.org/) - 回答各种与 Lua 相关的问题，包括许多形式的“如何 ___?'.


### Glossaries
- [Lua 5.3 Glossary](https://rawgit.com/dlaurie/lua-notes/master/glossary.html) - 一些基本 Lua 术语的词汇表.


### Style Guides
- [Lua-users style guide](http://lua-users.org/wiki/LuaStyleGuide)  - 通用的高级风格指南； 没有主见，很容易同意.
- [Olivine style guide](https://github.com/Olivine-Labs/lua-style-guide) - 一个更自以为是和具体，因此更严格的指南.


### Tutorials
- [Lua Crash Course](http://www.coppeliarobotics.com/helpFiles/en/luaCrashCourse.htm) - 短期速成课程复习，或当您忘记基础知识时的参考.
- [Learn Lua in 15 Minutes](http://tylerneylon.com/a/learn-lua/) - 一个注释良好的示例文件，涵盖了基础知识.
- [Learning Lua from JS](http://phrogz.net/lua/LearningLua_FromJS.html)  - Lua与JS异同概览； 对于希望使用 Lua 的 JavaScript 人员来说，这是一个很好的开始.
- [lua-users tutorial](http://lua-users.org/wiki/LuaTutorial) - 深入收集针对新手的教程.
- [Lua Missions](https://github.com/kikito/lua_missions) - 一系列“任务”，旨在沿途教授 Lua 的各个方面.
- [Creating an Image Server](http://leafo.net/posts/creating_an_image_server.html)  - 逐步设置和使用 OpenResty 构建一个简单的图像处理服务器； 玩 OpenResty 的一个很好的起点.


### Articles
- [Embedding Lua in C](https://debian-administration.org/article/264/Embedding_a_scripting_language_inside_your_C/C_code)  - 在 C 程序中嵌入 Lua 的介绍性演练. 有点过时，但仍然是一个很好的演练.
- [Lua: Good, bad, and ugly parts](http://notebook.kulchenko.com/programming/lua-good-different-bad-and-ugly-parts) - ZeroBraneStudio 的作者对 Lua 的优点、不同、缺点和丑陋的方面进行了全面总结，包括许多微妙的怪癖.
- [Lua states, libraries, coroutines and memory](http://www.thijsschreijer.nl/blog/?p=693) - 图表并解释了 Lua VM 的一些更高级的概念，特别是在与 C 接口时.


### Talks & Slides
- [Roberto's Talks](http://www.inf.puc-rio.br/~roberto/talks/index.html) - Lua 首席架构师的演讲历史，每篇都有幻灯片.
- [Lua Workshop Talks](http://www.lua.org/wshop14.html#abstracts) - 每年一次的 Lua Workshop 都会提供高质量的演讲，并且他们的历史在线，包括幻灯片.


### Books
- [Programming in Lua](http://www.lua.org/pil/)  - Lua 首席架构师所著的Lua 编程各个方面的权威介绍. 发行了三个版本； 第一版在线提供.
- [Lua Quick Reference](https://foicica.com/lua/) - 关于如何在 Lua 5.1 到 5.3 中编程和嵌入的快速参考，由 Textadept 的创建者编写.
- [Programming Gems](http://www.lua.org/gems/) - 一系列文章，涵盖了在各种用例中使用 Lua 进行良好编程的现有智慧和实践.
- [Lua Programming](https://en.wikibooks.org/wiki/Lua_Programming) - 语言的简短概述，最新的 Lua 5.2，可在线获取.


### Other Lists
- [awesome-resty](https://github.com/bungle/awesome-resty) - 像这样的列表，但专注于 OpenResty.
- [awesome-love2d](https://github.com/love2d-community/awesome-love2d) - 像这样的列表，但侧重于游戏开发和 LÖVE 平台.
- [Where Lua is Used](https://sites.google.com/site/marbux/home/where-lua-is-used) - 用 Lua 编写或可扩展的独立程序的完整列表.


## Contribute

欢迎和征求意见！ 阅读 [contribution guidelines](https://github.com/LewisJEllis/awesome-lua/blob/master/contributing.md) 第一的.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，Lewis Ellis 已放弃对本作品的所有版权和相关或邻接权.
