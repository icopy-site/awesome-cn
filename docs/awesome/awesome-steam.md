<div class="github-widget" data-repo="scholtzm/awesome-steam"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Steam [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 精选列表 [packages](#packages) 和 [resources](#resources) 关于 [Steam](http://store.steampowered.com/) 发展.

*请阅读 [contribution guidelines](https://github.com/scholtzm/awesome-steam/blob/master/CONTRIBUTING.md) 在贡献之前.*

本文档的目的是提供对现有软件包（库、模块等）和 Steam 客户端自动化和 WebAPI 使用方面可用资源的快速概述. 每当您需要开始一个新项目时，请查看软件包列表，看看是否有任何对您的用例有用的东西. 如果您需要技术细节或教程，请查看资源部分.




## Packages

 &gt; 这些软件包存储库中的许多都提供有用的 README 和 wiki 页面，它们解释了用法和/或提供示例. 使用特定包时不要忘记检查它们.

### Node.js

#### General

- [steam](https://github.com/seishun/node-steam) - 从 Node.js 直接与 Steam 服务器交互.
- [steam-client](https://github.com/DoctorMcKay/node-steam-client) - node-steam 的 SteamClient 的 API 兼容分支.
- [steam-user](https://github.com/DoctorMcKay/node-steam-user) - 功能丰富且易于使用的 Steam 客户端.
- [vapor](https://github.com/scholtzm/vapor) - 轻量级 Steam 客户端框架.
- [steam-parentbot](https://github.com/dragonbanshee/node-steam-parentbot) - Steam 机器人的简单基类.

#### WebAPI

- [steam-webapi](https://github.com/DoctorMcKay/node-steam-webapi) - 完整的 WebAPI 包装器，支持 Steam 发送的额外 HTTP 标头.
- [steamapi](https://github.com/lloti/node-steamapi) - 一个不错的 Steam API 包装器.

#### Trading

- [steam-trade](https://github.com/seishun/node-steam-trade) - 围绕 Steam 实时交易的 Node.js 包装器.
- [steam-tradeoffers](https://github.com/Alex7Kom/node-steam-tradeoffers) - Node.js 的 Steam 交易优惠.
- [steam-tradeoffer-manager](https://github.com/DoctorMcKay/node-steam-tradeoffer-manager) - 简单而理智的 Steam 交易报价管理.
- [steam-inventory-stream](https://github.com/timvandam/steam-inventory-stream) - 获取库存作为可读流.
- [steam-inventory-api-ng](https://github.com/itsjfx/node-steam-inventory-api-ng) - 具有重试和代理支持等高级功能的 Steam 库存 API 包装器.

#### Game Interaction

- [steam-gameserver](https://github.com/DoctorMcKay/node-steam-gameserver) - 用于 Gameserver 和 AnonGameserver 帐户类型的 Steam 客户端处理程序.
- [tf2](https://github.com/DoctorMcKay/node-tf2) - 直接与 TF2 游戏协调员互动.
- [csgo](https://github.com/joshuaferrara/node-csgo) - 直接与 CS:GO 游戏协调员互动.
- [dota2](https://github.com/RJacksonm1/node-dota2) - 直接与 Dota 2 游戏协调员互动.

#### Community & Store Automation

- [steamcommunity](https://github.com/DoctorMcKay/node-steamcommunity)  - 与 steamcommunity.com 互动. 还允许确认交易报价.
- [steamstore](https://github.com/DoctorMcKay/node-steamstore) - 与 store.steampowered.com 互动.
- [steam-weblogon](https://github.com/Alex7Kom/node-steam-weblogon) - 如果您正在运行 Steam 网络客户端，则检索 SteamCommunity cookie.
- [steam-web-api-key](https://github.com/Alex7Kom/node-steam-web-api-key) - 自动注册和检索 Steam API 密钥.
- [steam-parental](https://github.com/Alex7Kom/node-steam-parental) - 禁用家长锁.

#### Authentication

- [steam-login](https://github.com/cpancake/steam-login) - Simple Connect / Express Steam 身份验证库.
- [passport-steam](https://github.com/liamcurry/passport-steam) - Passport 和 Node.js 的 Steam (OpenID) 身份验证策略.
- [meteor-accounts-steam](https://github.com/scholtzm/meteor-accounts-steam) - 流星帐户的 Steam OpenID 集成.

#### Misc

- [steam-resources](https://github.com/seishun/node-steam-resources) - Steam 的枚举、protobuf 和结构.
- [steam-crypto](https://github.com/seishun/node-steam-crypto) - Steam 加密的 Node.js 实现.
- [steam-groups](https://github.com/scholtzm/node-steam-groups) - 提供组功能的自定义节点蒸汽处理程序.
- [steamid](https://github.com/DoctorMcKay/node-steamid) - SteamID 的使用和转换变得容易.
- [steam-totp](https://github.com/DoctorMcKay/node-steam-totp) - 轻松生成 Steam 使用的 2FA 代码.
- [steam-chat-bot](https://github.com/Steam-Chat-Bot/node-steam-chat-bot) - 蒸汽聊天机器人的简化界面.
- [vdf](https://github.com/RJacksonm1/node-vdf) - vdf 反对，反之亦然.
- [steamrep](https://github.com/scholtzm/node-steamrep) - 检查用户的 SteamRep 声誉.
- [reptf](https://github.com/scholtzm/node-reptf) - 检查用户的 rep.tf 信誉.
- [steamapis](https://github.com/itsjfx/node-steamapis) - 使用 API 的模块 [steamapis.com](https://steamapis.com).

### C&#35;

#### General

- [SteamKit2](https://github.com/SteamRE/SteamKit) - .NET 库，旨在与 Valve 的 Steam 网络互操作.
- [SteamAuth](https://github.com/geel9/SteamAuth) - A C# library that provides vital Steam Mobile Authenticator functionality.
- [SteamBot](https://github.com/Jessecar96/SteamBot) - 用于与蒸汽交易交互的自动化机器人软件.
- [SteamTradeOffersBot](https://github.com/waylaidwanderer/SteamTradeOffersBot) - 专注于贸易报价的 SteamBot 分叉.
- [SteamStandardProject](https://github.com/ObsidianMinor/SteamStandardProject) - 一组 .NET 标准库，使用在 Steam 的一个或多个部分中提供功能的通用类型.

#### Misc

- [BackpackLogin](https://github.com/igeligel/BackpackLogin) - 一个 .NET 标准库，用于使用 Steam 凭据登录到 pack.tf.
- [TeamFortressOutpostApi](https://github.com/igeligel/TeamFortressOutpostApi) - 一个允许用户与 TF2Outpost 交互的 .NET Standard 类库.
- [SteamGaugesApi](https://github.com/igeligel/SteamGaugesApi) - 一个 .NET Standard 2.0 库来自动使用 API [steamgauges](https://steamgaug.es/).

### PHP

- [SteamCommunity](https://github.com/waylaidwanderer/PHP-SteamCommunity) - 用于与 Steam 社区网站交互的 PHP 库.
- [SteamAuthentication](https://github.com/SmItH197/SteamAuthentication) - 使用 PHP 进行 Steam OpenID 身份验证.
- [SteamAuthOOP](https://github.com/BlackCetha/SteamAuthOOP) - SteamAuthentication 的面向对象替代方案.
- [steam-api](https://github.com/DaMitchell/steam-api-php) - Steam API 的 PHP 包装器.
- [steamid](https://github.com/DoctorMcKay/php-steamid) - PHP 的 SteamID 类.
- [steam-totp](https://github.com/DoctorMcKay/php-steam-totp) - 处理 Steam 专有 TOTP 算法的 PHP 库.
- [steam-auth](https://github.com/vikas5914/steam-auth) - 具有 Composer 支持的替代 Steam 身份验证库.

### Go

- [steam](https://github.com/Philipp15b/go-steam) - Steam 的 Go 协议.
- [steam-mobileauth](https://github.com/YellowOrWhite/go-steam-mobileauth) - Go 中的 SteamAuth 端口.

### Python

#### General

- [steam](https://github.com/ValvePython/steam) - 用于与 Steam 进行各种交互的模块.
- [PySteamKit](https://bitbucket.org/AzuiSleet/pysteamkit) - SteamKit 的 Python 端口.
- [steamodd](https://github.com/Lagg/steamodd) - Steam 工具库.
- [steampy](https://github.com/bukson/steampy) - 全自动 Steam 交易提供支持 SteamGuard 的库.
- [SteamAPI](https://github.com/smiley/steamapi) - 一个面向对象的 Python 2.7+ 库，用于访问 Steam Web API.
- [Steam-Trade](https://github.com/Zwork101/steam-trade) - 一个异步的、基于事件的交易库.

#### Game Interaction

- [csgo](https://github.com/ValvePython/csgo) - 用于与 CSGO 游戏协调器交互的 Python 模块.
- [dota2](https://github.com/ValvePython/dota2) - 用于与 Dota 2 的游戏协调器交互的 Python 模块.

#### Misc

- [vpk](https://github.com/ValvePython/vpk) - 用于处理 Valve 的 Pack 格式的 Python 模块.
- [vdf](https://github.com/ValvePython/vdf) - 用于处理 Valve 的 KeyValue 格式的 Python 模块.

### C++

- [SteamPP](https://github.com/seishun/SteamPP) - 与 Steam 服务器互操作的 C++ 库.

### Java

- [SteamKit-Java](https://github.com/Top-Cat/SteamKit-Java) - SteamKit 的 Java 端口.
- [JavaSteam](https://github.com/Longi94/JavaSteam) - Java 库，提供直接与 Valve 的 Steam 服务器交互的接口.

### Objective-C

- [SteamAuth](https://github.com/michaelchum/SteamAuth) - 围绕 Steam 的 OpenID 登录的 iOS 包装器.

### Ruby

- [steam-trade](https://github.com/OmG3r/steam-trade) - 用于发送交易报价的红宝石.

## Resources

### General

- [Steam WebAPI @ ValveSoftware](https://developer.valvesoftware.com/wiki/Steam_Web_API)
- [Steam WebAPI @ TF2 Wiki](https://wiki.teamfortress.com/wiki/WebAPI)
- [Steam WebAPI Documentation by xPaw](https://lab.xpaw.me/steam_api_documentation.html)
- [Steam Internal WebAPI Documentation by Revadike](https://github.com/Revadike/UnofficialSteamWebAPI)
- [Steam as OpenID Provider](http://steamcommunity.com/dev)
- [Steam API Key Registration](http://steamcommunity.com/dev/apikey)
- [Steam Error Codes](https://steamerrors.com/) - 带有可能解释的“EResult”代码列表.

### Tutorials

- [Creating a Steam Trade Bot with Node.js](https://firepowered.org/developer/create-a-steam-trade-bot-with-nodejs-iojs-updated-for-node-steam-v1-0/)
- [Charred's node.js Guide to Steam Bots](https://github.com/charredgrass/nodejs-bot-guide)
- [In-depth Steam Bot Guide with Node.js](https://github.com/andrewda/node-steam-guide)
- [Retrieving 2FA Keys from iOS Device](http://forums.backpack.tf/index.php?/topic/45995-guide-how-to-get-your-shared-secret-from-ios-device-steam-mobile/)

### Posts

- [Item IDs Explained](https://dev.doctormckay.com/topic/332-identifying-steam-items/)
- [Everything Related to Escrow](https://www.reddit.com/r/SteamBot/comments/3udhkd/everything_related_to_escrow/)
- [Understanding Avatar Hash](https://www.reddit.com/r/SteamBot/comments/3cv6k7/problem_downloading_an_avatar_using/)

### Standalone Tools

- [NetHook2](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHook2) - 拦截 Steam 客户端的网络消息.
- [NetHook2 Analyzer](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHookAnalyzer2) - 检查 NetHook2 转储的消息.
- [steam-auth-web-util](http://scholtzm.github.io/steam-auth-web-util/) - 直接在您的网络浏览器中生成 2FA 代码.
- [SteamDesktopAuthenticator](https://github.com/Jessecar96/SteamDesktopAuthenticator) - Steam 移动验证器应用程序的桌面实施.
- [protonenv](https://github.com/rizkiarm/protonenv) - 简单的 Proton 版本和前缀管理.
- [steam-desktop-authenticator-multiplatform](https://github.com/tre3p/steam-desktop-authenticator-multiplatform) - Steam 桌面验证器.

### Discussion Boards

- [/r/SteamBot](https://www.reddit.com/r/SteamBot)
- [/r/SteamBot Discord](https://discord.gg/0i5X3oDHJbDUsiGC)
- [/r/nodesteam](https://www.reddit.com/r/nodesteam)
- [DoctorMcKay's Dev Forum](https://dev.doctormckay.com/)
- [node-steam-forum](https://github.com/steam-forward/node-steam-forum)

### Third-Party Services

下面列出的网站可能提供免费和/或付费服务，并根据其域名的字母顺序列出.

- [backpack.tf](https://backpack.tf/developer) - 提供 TF2 价格和 Steam 市场/库存相关服务.
- [steamanalyst.com](https://steamanalyst.com/) - 提供 CS:GO 价格.
- [hexa.one](https://hexa.one/) - 提供多个游戏和 Steam 市场/库存相关服务的价格.
- [steamapis.com](https://steamapis.com/) - 提供多个游戏和 Steam 市场/库存相关服务的价格.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author and contributors of this text have waived all copyright and related or neighboring rights to this work.
