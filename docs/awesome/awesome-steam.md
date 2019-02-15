<div class="github-widget" data-repo="scholtzm/awesome-steam"></div>
## Awesome Steam [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精选的清单 [packages](#packages) 和 [resources](#resources) 关于 [Steam](http://store.steampowered.com/) 发展.

*请阅读 [contribution guidelines](https://github.com/scholtzm/awesome-steam/blob/master/CONTRIBUTING.md) 在贡献之前.*

 本文档的目的是提供有关Steam客户端自动化和WebAPI使用的现有软件包（库，模块等）和可用资源的快速概述.  每当您需要启动一个新项目时，请查看包列表，看看是否有任何对您的用例有用的内容.  如果您需要技术细节或教程，请查看资源部分.




## Packages

 &gt;许多这些软件包存储库提供了有用的自述文件和维基页面，它们解释了用法和/或提供了示例.  使用特定包装时不要忘记检查它们.

### Node.js

#### General

- [steam](https://github.com/seishun/node-steam) - 直接与Node.js的Steam服务器连接.
- [steam-client](https://github.com/DoctorMcKay/node-steam-client) - 与API兼容的node-steam的SteamClient分支.
- [steam-user](https://github.com/DoctorMcKay/node-steam-user) - 功能丰富，易于使用的Steam客户端.
- [vapor](https://github.com/scholtzm/vapor) - 轻量级Steam客户端框架.
- [steam-parentbot](https://github.com/dragonbanshee/node-steam-parentbot) -  Steam机器人的简单基类.

#### WebAPI

- [steam-webapi](https://github.com/DoctorMcKay/node-steam-webapi) - 完整的WebAPI包装器，支持Steam发送的额外HTTP标头.
- [steamapi](https://github.com/lloti/node-steamapi) - 一个不错的Steam API包装器.

#### Trading

- [steam-trade](https://github.com/seishun/node-steam-trade) -  Node.js包装Steam实时交易.
- [steam-tradeoffers](https://github.com/Alex7Kom/node-steam-tradeoffers) -  Node.js的Steam交易优惠
- [steam-tradeoffer-manager](https://github.com/DoctorMcKay/node-steam-tradeoffer-manager) - 简单而理智的Steam交易报价管理.

#### Game Interaction

- [steam-gameserver](https://github.com/DoctorMcKay/node-steam-gameserver) -  Gameserver和AnonGameserver帐户类型的Steam客户端处理程序.
- [tf2](https://github.com/DoctorMcKay/node-tf2) - 直接与TF2游戏协调员互动.
- [csgo](https://github.com/joshuaferrara/node-csgo) - 直接与CS：GO游戏协调员互动.
- [dota2](https://github.com/RJacksonm1/node-dota2) - 直接与Dota 2游戏协调员互动.

#### Community & Store Automation

- [steamcommunity](https://github.com/DoctorMcKay/node-steamcommunity)   - 与steamcommunity.com互动.  还允许确认交易报价.
- [steamstore](https://github.com/DoctorMcKay/node-steamstore) - 与store.steampowered.com互动.
- [steam-weblogon](https://github.com/Alex7Kom/node-steam-weblogon) - 如果您正在运行Steam网络客户端，请检索SteamCommunity cookie.
- [steam-web-api-key](https://github.com/Alex7Kom/node-steam-web-api-key) - 自动注册和检索Steam API密钥.
- [steam-parental](https://github.com/Alex7Kom/node-steam-parental) - 禁用父母锁定.

#### Authentication

- [steam-login](https://github.com/cpancake/steam-login) - 简单的Connect / Express Steam身份验证库.
- [passport-steam](https://github.com/liamcurry/passport-steam) -  Passport和Node.js的Steam（OpenID）身份验证策略.
- [meteor-accounts-steam](https://github.com/scholtzm/meteor-accounts-steam) -  Meteor Accounts的Steam OpenID集成.

#### Misc

- [steam-resources](https://github.com/seishun/node-steam-resources) -  Steam的枚举，protobufs和结构.
- [steam-crypto](https://github.com/seishun/node-steam-crypto) -  Steam加密的Node.js实现.
- [steam-groups](https://github.com/scholtzm/node-steam-groups) - 定制节点 - 蒸汽处理器，提供组功能.
- [steamid](https://github.com/DoctorMcKay/node-steamid) -  SteamID的使用和转换变得简单.
- [steam-totp](https://github.com/DoctorMcKay/node-steam-totp) - 轻松生成Steam使用的2FA代码.
- [steam-chat-bot](https://github.com/Steam-Chat-Bot/node-steam-chat-bot) - 简化蒸汽聊天机器人的界面.
- [vdf](https://github.com/RJacksonm1/node-vdf) - 对象反对vdf，反之亦然.
- [steamrep](https://github.com/scholtzm/node-steamrep) - 检查用户的SteamRep声誉.
- [reptf](https://github.com/scholtzm/node-reptf) - 检查用户的rep.tf声誉.

### C&#35;

#### General

- [SteamKit2](https://github.com/SteamRE/SteamKit) -  .NET库旨在与Valve的Steam网络进行互操作.
- [SteamAuth](https://github.com/geel9/SteamAuth) - A C# library that provides vital Steam Mobile Authenticator functionality.
- [SteamBot](https://github.com/Jessecar96/SteamBot) - 用于与蒸汽贸易交互的自动化僵尸软件.
- [SteamTradeOffersBot](https://github.com/waylaidwanderer/SteamTradeOffersBot) -  SteamBot fork专注于贸易优惠.
- [SteamStandardProject](https://github.com/ObsidianMinor/SteamStandardProject) - 使用常见类型的.NET标准库集合，这些类型在Steam的一个或多个部分中提供功能.

#### Misc

- [BackpackLogin](https://github.com/igeligel/BackpackLogin) - 用于使用Steam凭据登录backpack.tf的.NET标准库.
- [TeamFortressOutpostApi](https://github.com/igeligel/TeamFortressOutpostApi) -  .NET标准类库，允许用户与TF2Outpost进行交互.
- [SteamGaugesApi](https://github.com/igeligel/SteamGaugesApi) -  .NET Standard 2.0库，自动使用API [steamgauges](https://steamgaug.es/).

### PHP

- [SteamCommunity](https://github.com/waylaidwanderer/PHP-SteamCommunity) - 用于与Steam社区网站交互的PHP库.
- [SteamAuthentication](https://github.com/SmItH197/SteamAuthentication) - 使用PHP进行Steam OpenID身份验证.
- [SteamAuthOOP](https://github.com/BlackCetha/SteamAuthOOP) - 面向对象的SteamAuthentication替代方案.
- [steam-api](https://github.com/DaMitchell/steam-api-php) -  Steam API的PHP包装器.
- [steamid](https://github.com/DoctorMcKay/php-steamid) -  PHP的SteamID类.
- [steam-totp](https://github.com/DoctorMcKay/php-steam-totp) - 用于处理Steam专有TOTP算法的PHP库.
- [steam-auth](https://github.com/vikas5914/steam-auth) - 具有Composer支持的备用Steam身份验证库.

### Go

- [steam](https://github.com/Philipp15b/go-steam) -  Go中的Steam协议.
- [steam-mobileauth](https://github.com/YellowOrWhite/go-steam-mobileauth) -  Go的SteamAuth港口.

### Python

#### General

- [steam](https://github.com/ValvePython/steam) - 与Steam进行各种交互的模块.
- [PySteamKit](https://bitbucket.org/AzuiSleet/pysteamkit) -  SteamKit的Python端口.
- [steamodd](https://github.com/Lagg/steamodd) -  Steam工具库.
- [steampy](https://github.com/bukson/steampy) - 全自动Steam交易提供具有SteamGuard支持的库.
- [SteamAPI](https://github.com/smiley/steamapi) - 面向对象的Python 2.7+库，用于访问Steam Web API.
- [Steam-Trade](https://github.com/Zwork101/steam-trade) - 基于事件的异步交易库.

#### Game Interaction

- [csgo](https://github.com/ValvePython/csgo) - 用于与CSGO的游戏协调员交互的Python模块.
- [dota2](https://github.com/ValvePython/dota2) - 用于与Dota 2的游戏协调员交互的Python模块.

#### Misc

- [vpk](https://github.com/ValvePython/vpk) - 用于处理Valve的Pack格式的Python模块.
- [vdf](https://github.com/ValvePython/vdf) - 用于处理Valve的KeyValue格式的Python模块.

### C++

- [SteamPP](https://github.com/seishun/SteamPP) - 与Steam服务器互操作的C ++库.

### Java

- [SteamKit-Java](https://github.com/Top-Cat/SteamKit-Java) -  SteamKit的Java端口.

### Objective-C

- [SteamAuth](https://github.com/michaelchum/SteamAuth) - 围绕Steam的OpenID登录的iOS包装器.

### Ruby

- [steam-trade](https://github.com/OmG3r/steam-trade) - 用于发送交易报价的Ruby gem.

## Resources

### General

- [Steam WebAPI @ ValveSoftware](https://developer.valvesoftware.com/wiki/Steam_Web_API)
- [Steam WebAPI @ TF2 Wiki](https://wiki.teamfortress.com/wiki/WebAPI)
- [Steam WebAPI Documentation by xpaw](https://lab.xpaw.me/steam_api_documentation.html)
- [Steam as OpenID Provider](http://steamcommunity.com/dev)
- [Steam API Key Registration](http://steamcommunity.com/dev/apikey)
- [Steam Error Codes](https://steamerrors.com/) - “EResult”代码列表以及可能的解释.

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

- [NetHook2](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHook2) - 拦截Steam客户端的网络消息.
- [NetHook2 Analyzer](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHookAnalyzer2) - 检查NetHook2转储的邮件.
- [steam-auth-web-util](http://scholtzm.github.io/steam-auth-web-util/) - 直接在Web浏览器中生成2FA代码.
- [SteamDesktopAuthenticator](https://github.com/Jessecar96/SteamDesktopAuthenticator) -  Steam的移动验证器应用程序的桌面实现.

### Discussion Boards

- [/r/SteamBot](https://www.reddit.com/r/SteamBot)
- [/r/SteamBot Discord](https://discord.gg/0i5X3oDHJbDUsiGC)
- [/r/nodesteam](https://www.reddit.com/r/nodesteam)
- [DoctorMcKay's Dev Forum](https://dev.doctormckay.com/)
- [node-steam-forum](https://github.com/steam-forward/node-steam-forum)

### Third-Party Services

下面列出的网站可能提供免费和/或付费服务，并根据其域名按字母顺序列出.

- [backpack.tf](https://backpack.tf/developer) - 提供TF2价格和蒸汽市场/库存相关服务.
- [steamanalyst.com](https://steamanalyst.com/) - 提供CS：GO价格.
- [steamapi.io](https://steamapi.io/) - 提供多种游戏和Steam市场/库存相关服务的价格.
- [steamapis.com](https://steamapis.com/) - 提供多种游戏和Steam市场/库存相关服务的价格.
- [steamlytics.xyz](https://steamlytics.xyz/) - 提供CS：GO价格和Steam市场/库存相关服务.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，本文的作者和撰稿人放弃了本作品的所有版权及相关或相邻权利.
