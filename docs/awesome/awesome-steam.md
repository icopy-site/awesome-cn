## Awesome Steam [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of [packages](#packages) and [resources](#resources) regarding [Steam](http://store.steampowered.com/) development.

*Please read the [contribution guidelines](https://github.com/scholtzm/awesome-steam/blob/master/CONTRIBUTING.md) before contributing.*

The purpose of this document is to provide a quick overview over existing packages (libraries, modules etc.) and resources available regarding Steam client automation and WebAPI usage. Whenever you need to start a new project, have a look at the list of packages and see if there is anything useful for your use case. If you need technical details or tutorials, check out the resources section.

## Table of Contents

- [Packages](#packages)
  - [Node.js](#nodejs)
  - [C#](#c)
  - [PHP](#php)
  - [Go](#go)
  - [Python](#python)
  - [C++](#c-1)
  - [Java](#java)
  - [Objective-C](#objective-c)
  - [Ruby](#ruby)

- [Resources](#resources)
  - [General](#general-1)
  - [Tutorials](#tutorials)
  - [Posts](#posts)
  - [Standalone Tools](#standalone-tools)
  - [Discussion Boards](#discussion-boards)
  - [Third-Party Services](#third-party-services)

## Packages

> 💡 Many of these package repositories provide helpful READMEs and wiki pages, which explain the usage and/or provide examples. Do not forget to check them out when using particular package.

### Node.js

#### General

- [steam](https://github.com/seishun/node-steam) - Interface directly with Steam servers from Node.js.
- [steam-client](https://github.com/DoctorMcKay/node-steam-client) - API-compatible fork of node-steam's SteamClient.
- [steam-user](https://github.com/DoctorMcKay/node-steam-user) - Feature-rich easy-to-use Steam client.
- [vapor](https://github.com/scholtzm/vapor) - Lightweight Steam client framework.
- [steam-parentbot](https://github.com/dragonbanshee/node-steam-parentbot) - Simple base class for a Steam bot.

#### WebAPI

- [steam-webapi](https://github.com/DoctorMcKay/node-steam-webapi) - Complete WebAPI wrapper with support for extra HTTP headers sent by Steam.
- [steamapi](https://github.com/lloti/node-steamapi) - A nice Steam API wrapper.

#### Trading

- [steam-trade](https://github.com/seishun/node-steam-trade) - Node.js wrapper around Steam live trading.
- [steam-tradeoffers](https://github.com/Alex7Kom/node-steam-tradeoffers) - Steam Trade Offers for Node.js.
- [steam-tradeoffer-manager](https://github.com/DoctorMcKay/node-steam-tradeoffer-manager) - Simple and sane Steam trade offer management.

#### Game Interaction

- [steam-gameserver](https://github.com/DoctorMcKay/node-steam-gameserver) - Steam client handler for Gameserver and AnonGameserver account types.
- [tf2](https://github.com/DoctorMcKay/node-tf2) - Interact directly with TF2 game coordinator.
- [csgo](https://github.com/joshuaferrara/node-csgo) - Interact directly with CS:GO game coordinator.
- [dota2](https://github.com/RJacksonm1/node-dota2) - Interact directly with Dota 2 game coordinator.

#### Community & Store Automation

- [steamcommunity](https://github.com/DoctorMcKay/node-steamcommunity) - Interact with steamcommunity.com. Also allows to confirm trade offers.
- [steamstore](https://github.com/DoctorMcKay/node-steamstore) - Interact with store.steampowered.com.
- [steam-weblogon](https://github.com/Alex7Kom/node-steam-weblogon) - Retrieve SteamCommunity cookies if you are running Steam network client.
- [steam-web-api-key](https://github.com/Alex7Kom/node-steam-web-api-key) - Automatically registers and retrieves Steam API key.
- [steam-parental](https://github.com/Alex7Kom/node-steam-parental) - Disable parental lock.

#### Authentication

- [steam-login](https://github.com/cpancake/steam-login) - Simple Connect / Express Steam authentication library.
- [passport-steam](https://github.com/liamcurry/passport-steam) - Steam (OpenID) authentication strategy for Passport and Node.js.
- [meteor-accounts-steam](https://github.com/scholtzm/meteor-accounts-steam) - Steam OpenID integration for Meteor Accounts.

#### Misc

- [steam-resources](https://github.com/seishun/node-steam-resources) - Steam's enums, protobufs and structs.
- [steam-crypto](https://github.com/seishun/node-steam-crypto) - Node.js implementation of Steam crypto.
- [steam-groups](https://github.com/scholtzm/node-steam-groups) - Custom node-steam handler which provides group functions.
- [steamid](https://github.com/DoctorMcKay/node-steamid) - SteamID usage and conversion made easy.
- [steam-totp](https://github.com/DoctorMcKay/node-steam-totp) - Easily generate 2FA codes used by Steam.
- [steam-chat-bot](https://github.com/Steam-Chat-Bot/node-steam-chat-bot) - Simplified interface for a steam chat bot.
- [vdf](https://github.com/RJacksonm1/node-vdf) - vdf to object and vice versa.
- [steamrep](https://github.com/scholtzm/node-steamrep) - Check user's SteamRep reputation.
- [reptf](https://github.com/scholtzm/node-reptf) - Check user's rep.tf reputation.

### C&#35;

#### General

- [SteamKit2](https://github.com/SteamRE/SteamKit) - .NET library designed to interoperate with Valve's Steam network.
- [SteamAuth](https://github.com/geel9/SteamAuth) - A C# library that provides vital Steam Mobile Authenticator functionality.
- [SteamBot](https://github.com/Jessecar96/SteamBot) - Automated bot software for interacting with steam trade.
- [SteamTradeOffersBot](https://github.com/waylaidwanderer/SteamTradeOffersBot) - SteamBot fork which focuses on trade offers.
- [SteamStandardProject](https://github.com/ObsidianMinor/SteamStandardProject) - A collection of .NET Standard libraries using common types that provide functionality in one or more parts of Steam.

#### Misc

- [BackpackLogin](https://github.com/igeligel/BackpackLogin) - A .NET Standard library for logging into backpack.tf using Steam credentials.
- [TeamFortressOutpostApi](https://github.com/igeligel/TeamFortressOutpostApi) - A .NET Standard class library which allows user to interact with TF2Outpost.
- [SteamGaugesApi](https://github.com/igeligel/SteamGaugesApi) - A .NET Standard 2.0 library to automatically use the API of [steamgauges](https://steamgaug.es/).

### PHP

- [SteamCommunity](https://github.com/waylaidwanderer/PHP-SteamCommunity) - A PHP library for interacting with the Steam Community website.
- [SteamAuthentication](https://github.com/SmItH197/SteamAuthentication) - Steam OpenID authentication with PHP.
- [SteamAuthOOP](https://github.com/BlackCetha/SteamAuthOOP) - An object-oriented alternative to SteamAuthentication.
- [steam-api](https://github.com/DaMitchell/steam-api-php) - A PHP wrapper for the Steam API.
- [steamid](https://github.com/DoctorMcKay/php-steamid) - SteamID class for PHP.
- [steam-totp](https://github.com/DoctorMcKay/php-steam-totp) - PHP library to deal with Steam's proprietary TOTP algorithm.
- [steam-auth](https://github.com/vikas5914/steam-auth) - An alternative Steam authentication library with Composer support.

### Go

- [steam](https://github.com/Philipp15b/go-steam) - Steam's protocol in Go.
- [steam-mobileauth](https://github.com/YellowOrWhite/go-steam-mobileauth) - Port of SteamAuth in Go.

### Python

#### General

- [steam](https://github.com/ValvePython/steam) - Module for various interactions with Steam.
- [PySteamKit](https://bitbucket.org/AzuiSleet/pysteamkit) - Python port of SteamKit.
- [steamodd](https://github.com/Lagg/steamodd) - Steam tools library.
- [steampy](https://github.com/bukson/steampy) - Fully automated Steam trade offers library with SteamGuard support.
- [SteamAPI](https://github.com/smiley/steamapi) - An object-oriented Python 2.7+ library for accessing the Steam Web API.
- [Steam-Trade](https://github.com/Zwork101/steam-trade) - An asynchronous, event-based trade library.

#### Game Interaction

- [csgo](https://github.com/ValvePython/csgo) - Python module for interacting with CSGO's Game Coordinator.
- [dota2](https://github.com/ValvePython/dota2) - Python module for interacting with Dota 2's Game Coordinator.

#### Misc

- [vpk](https://github.com/ValvePython/vpk) - Python module for working with Valve's Pack format.
- [vdf](https://github.com/ValvePython/vdf) - Python module for working with Valve's KeyValue format.

### C++

- [SteamPP](https://github.com/seishun/SteamPP) - C++ library to interoperate with Steam servers.

### Java

- [SteamKit-Java](https://github.com/Top-Cat/SteamKit-Java) - Java port of SteamKit.

### Objective-C

- [SteamAuth](https://github.com/michaelchum/SteamAuth) - An iOS wrapper around Steam's OpenID login.

### Ruby

- [steam-trade](https://github.com/OmG3r/steam-trade) - Ruby gem for sending trade offers.

## Resources

### General

- [Steam WebAPI @ ValveSoftware](https://developer.valvesoftware.com/wiki/Steam_Web_API)
- [Steam WebAPI @ TF2 Wiki](https://wiki.teamfortress.com/wiki/WebAPI)
- [Steam WebAPI Documentation by xpaw](https://lab.xpaw.me/steam_api_documentation.html)
- [Steam as OpenID Provider](http://steamcommunity.com/dev)
- [Steam API Key Registration](http://steamcommunity.com/dev/apikey)
- [Steam Error Codes](https://steamerrors.com/) - List of `EResult` codes with possible explanations.

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

- [NetHook2](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHook2) - Intercept Steam client's network messages.
- [NetHook2 Analyzer](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHookAnalyzer2) - Inspect messages dumped by NetHook2.
- [steam-auth-web-util](http://scholtzm.github.io/steam-auth-web-util/) - Generate 2FA codes directly in your web browser.
- [SteamDesktopAuthenticator](https://github.com/Jessecar96/SteamDesktopAuthenticator) - Desktop implementation of Steam's mobile authenticator app.

### Discussion Boards

- [/r/SteamBot](https://www.reddit.com/r/SteamBot)
- [/r/SteamBot Discord](https://discord.gg/0i5X3oDHJbDUsiGC)
- [/r/nodesteam](https://www.reddit.com/r/nodesteam)
- [DoctorMcKay's Dev Forum](https://dev.doctormckay.com/)
- [node-steam-forum](https://github.com/steam-forward/node-steam-forum)

### Third-Party Services

Websites listed below may provide free and/or paid services and are listed alphabetically according to their domain name.

- [backpack.tf](https://backpack.tf/developer) - Provides TF2 prices and Steam market/inventory related services.
- [steamanalyst.com](https://steamanalyst.com/) - Provides CS:GO prices.
- [steamapi.io](https://steamapi.io/) - Provides prices for several games and Steam market/inventory related services.
- [steamapis.com](https://steamapis.com/) - Provides prices for several games and Steam market/inventory related services.
- [steamlytics.xyz](https://steamlytics.xyz/) - Provides CS:GO prices and Steam market/inventory related services.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author and contributors of this text have waived all copyright and related or neighboring rights to this work.
