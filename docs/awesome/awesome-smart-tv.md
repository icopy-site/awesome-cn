<div class="github-widget" data-repo="vitalets/awesome-smart-tv"></div>
## Awesome Smart TV [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome resources for building Smart TV apps

<a href="https://raw.githubusercontent.com/vitalets/awesome-smart-tv"><img align="right" width="150" src="https://user-images.githubusercontent.com/1473072/27913047-7c3a5e60-6267-11e7-8bd1-bef2bf3cd753.png"/></a>

[Smart TV](https://en.wikipedia.org/wiki/Smart_TV) is a growing platform of TVs having access to the internet and allowing to browse web-sites and install applications. It has own ecosystem with main players like Samsung, LG, Android TV and Apple TV. In this list you will find official and third-party resources for developing Smart TV apps and communicating with TV from remote devices.


## Platforms
Below are the most popular platforms for Smart TV. The full list is [here](https://en.wikipedia.org/wiki/List_of_smart_TV_platforms_and_middleware_software).

### Samsung Tizen
#### Official resources
* [Samsung TV Developers site](http://developer.samsung.com/tv) - News, documentation and SDK downloads.
* [Tizen TV Developers site](https://developer.tizen.org/tizen/tv) - Full API documentation and guides for developing Tizen TV apps.
* [Tizen Studio](https://developer.tizen.org/development/tizen-studio/download) - IDE for TV apps development including Tizen TV Emulator.
* [Smart View SDK](http://developer.samsung.com/tv/develop/extension-libraries/smart-view-sdk/download/) - Official Android, IOS and JavaScript SDK for communication between remote device and Samsung Smart TV.
* [Samsung TV Developers Forum](http://developer.samsung.com/forum/?topCtgy=06) - Ask questions and share tips when developing apps with Samsung SDKs.
* [Samsung Smart TV Bug Bounty](https://samsungtvbounty.com) - If you find bug in Samsung TV, submit it here and get a reward $1000+.
* [vscode-extension-tizentv](https://marketplace.visualstudio.com/items?itemName=tizensdk.tizentv) - A Visual Studio Code extension that provides a lightweight IDE for Tizen application developers.
* [Wits](https://github.com/Samsung/Wits) - A tool for reloading tv app's JavaScript/CSS without reinstalling the app every time you make a change.

#### Third-party remote control libraries
* [samsungctl](https://github.com/Ape/samsungctl) - Library and command line tool for remote controlling Samsung televisions via a TCP/IP connection. It currently supports both pre-2016 TVs as well most of the modern Tizen-OS TVs with Ethernet or Wi-Fi connectivity (Python).
* [samsung-tv-remote](https://github.com/Badisi/samsung-tv-remote) - Node.js module to remotely control Samsung Smart TV starting from 2016 (JavaScript).
* [homebridge-samsungtv2016](https://github.com/kyleaa/homebridge-samsungtv2016) - A plugin for [Homebridge](https://github.com/nfarina/homebridge) that allows you to control your 2016 Samsung TV with HomeKit and Siri (JavaScript).
* [homebridge-samsung-tizen](https://github.com/tavicu/homebridge-samsung-tizen) - A plugin for [Homebridge](https://github.com/nfarina/homebridge) that allows you to control your Samsung Tizen TV with HomeKit and Siri (JavaScript).
* [samsung-remote-models-2014-and-newer](https://github.com/tdudek/samsung-remote-models-2014-and-newer) - Encrypted communication with the internal web service of Samsung TV models 2014+.
* [SmartCrypto](https://github.com/sectroyer/SmartCrypto) - SmartView2 encrypted handshake API implementation in C/Python.
* [samsung-messagebox](https://github.com/shantanugoel/samsung-messagebox) - Python script to show notifications on Samsung TVs.
* [samsung-tv-control](https://github.com/Toxblh/samsung-tv-control) - Library for remote control Samsung TV in your Node.js

#### Other
* [Identification of Samsung TV models 2008-2017](http://en.tab-tv.com/?page_id=7123) - How to get screen size, matrix type, year of development, series and other parameters from Samsung TV model name.
* [Tizen Studio development references](https://github.com/claromes/tizenstudio) - Documents focused on web apps for Smart TVs e Professional Monitors, based in personal researches.
* [TizenBrew] (https://github.com/reisxd/TizenBrew) - A way to experience modded websites and you can install newer apps without fighting with Tizen Studio
* [TizenTube] (https://github.com/reisxd/TizenTube) - A TizenBrew module that enhances your favourite streaming websites viewing experience by removing ads and adding support for Sponsorblock.

### LG webOS
#### Official resources
* [webOS TV Developers Site](http://webostv.developer.lge.com) - WebOS TV apps development principles, tutorials, API documentation and packaging tools.
* [webOS TV IDE + SDK](http://webostv.developer.lge.com/sdk/download/download-sdk/) - IDE for apps development including a Command Line Interface and emulator.
* [Connect SDK](http://www.svlconnectsdk.com/) - Open source framework developed by LG that connects your mobile apps with multiple media device platforms. Currently supports 8 platforms. But seems [abandoned](https://github.com/ConnectSDK/Connect-SDK-Android/issues/364).
* [webOS TV Developers Forum](http://developer.lge.com/community/forums/RetrieveForumList.dev?prodTypeCode=TV) - Ask questions, share information and learn about Smart TV app development with other developers.

#### Third-party remote control libraries
* [lgtv2](https://github.com/hobbyquaker/lgtv2) - Node.js module for remote control of LG webOS TV via WebSocket messages (JavaScript).
* [node-red-contrib-lgtv](https://github.com/hobbyquaker/node-red-contrib-lgtv) - Module for [Node-RED](https://nodered.org) allowing  remote control of LG webOS Smart TVs (JavaScript).
* [node-webos](https://github.com/WeeJeWel/node-webos) - Node.js module to discover and control webOS TVs (JavaScript).
* [lgtv2mqtt](https://github.com/hobbyquaker/lgtv2mqtt) - Interface between LG WebOS Smart TVs and MQTT (JavaScript).
* [ares-webos-sdk](https://github.com/stevenvong/ares-webos-sdk) - webOS [CLI](http://webostv.developer.lge.com/sdk/using-webos-tv-cli/) as separate NPM module (JavaScript).
* [pylgtv](https://github.com/TheRealLink/pylgtv) - Library to control webOS based LG Tv devices (Python).
* [LGWebOSRemote](https://github.com/klattimer/LGWebOSRemote) - Command line tool for webOS remote control of LG TVs (Python).
* [homebridge-webos-tv](https://github.com/merdok/homebridge-webos-tv) - A plugin for [Homebridge](https://github.com/nfarina/homebridge) which allows you to control your webOS TV.
* [PyWebOSTV](https://github.com/supersaiyanmode/PyWebOSTV) - A generic & entensible WebOS 3.0 Client Library (Python2, Python3).
* [go-webos](https://github.com/vitalets/awesome-smart-tv/blob/master/github.com/kaperys/go-webos) - A small Go library for interaction with webOS TVs (golang).

#### Videos
* [LG Magic Motion Remote - Point, Click, and Control](https://youtu.be/yxu0G7jM_us) - Operate TV like a computer mouse.

#### Other
* [openlgtv.org.ru](http://openlgtv.org.ru) - A non-commercial project for legal reverse engineering and research on LG Television firmware. Seems a bit outdated but contains a lot of information.
* [Identification of LG TV models 2011-2017](http://en.tab-tv.com/?page_id=7111) - How to get screen size, matrix type, year of development, series and ohter parameters from LG TV model name.

### Android TV
#### Official resources
* [Android TV Developers site](https://developer.android.com/training/tv/start/start.html) - Documentation, tutorials and best practises for building Android TV apps.

#### Articles
* [How to develop Android TV App?](https://medium.com/@halilozel1903/how-to-develop-android-tv-app-5e251f3aa56b) - An article about developing apps for Android TV.

### Apple tvOS
#### Official resources
* [tvOS Developers Site](https://developer.apple.com/tvos/) - SDK, documentation and tutorials for developing tvOS apps.
* [TVML](https://developer.apple.com/documentation/tvml) -  Apple TV Markup Language for creating tvOS apps.

### Google Chromecast
#### Official resources
* [Google Cast SDK](https://developers.google.com/cast/) - Official Google Cast SDK documentation and tutorials.
* [TVs with Chromecast built-in](https://www.google.com/chromecast/built-in/tv/) - List of vendors supporting built-in Chromecast and advantages over traditional TV remote controller.

## Cross-platform frameworks
* [react-tv](https://github.com/raphamorim/react-tv) - React development for TV: renderer for low memory applications and Packager for WebOS, Tizen, Orsay.
* [TOAST](http://developer.samsung.com/tv/develop/extension-libraries/toast/) - Samsung open-source framework for multi-platform TV apps developemnt.
* [Enyo](http://enyojs.com) - LG framework for development apps for all major platforms, from phones and tablets to PCs and TVs.
* [Smartbox](https://github.com/immosmart/smartbox) - Smart TV universal library for Samsung, LG, Philips, SmartTV Aliance, STB Mag app development.
* [Mautilus Smart TV SDK](https://github.com/mautilus/sdk) - A platform-agnostic framework for developing TV Apps. Supports Samsung, LG, Philips, Sony, Panasonic and VESTEL Smart TVs.
* [BBC TAL](https://bbc.github.io/tal/) - An open source library for building applications for Smart TV developed by BBC engineers.
* [PureQML TV](https://github.com/pureqml/qmlcore-tv) - A declarative front-end framework for web-based SmartTV/STB platforms. Has experimental support of Android TV.
* [ZombieBox](https://github.com/interfaced/zombiebox) - An open source Smart TV framework. Strongly typed JavaScript, component based, built-in D-PAD navigation management, abstract video API with DRM for all platforms. Supports many platforms like Tizen, webOS, Android TV, etc. 

## Remote control protocols
* [DLNA](https://en.wikipedia.org/wiki/Digital_Living_Network_Alliance) - Industry-wide standard for sharing data over a home network. Depending on the DLNA-compatible devices you own, you might be able to stream films from your laptop to your TV, play an MP3 stored on your phone over your hi-fi system, or print a photo from your tablet on your home printer.
* [Wi-Fi Direct](https://en.wikipedia.org/wiki/Wi-Fi_Direct) - Standard enabling devices to easily connect with each other without requiring a wireless access point.
* [Miracast](https://en.wikipedia.org/wiki/Miracast) - Standard for wireless connections from devices (such as laptops, tablets, or smartphones) to displays (such as TVs, monitors or projectors). Works over Wi-Fi Direct.

## Navigation libraries
* [lrud](https://github.com/stuart-williams/lrud) - Left, Right, Up, Down. A spatial navigation library for devices with input via directional controls.
* [js-spatial-navigation](https://github.com/luke-chang/js-spatial-navigation) - A javascript-based implementation of Spatial Navigation.
* [react-js-spatial-navigation](https://github.com/dead/react-js-spatial-navigation) - A wrapper of js-spatial-navigation to react components.
* [react-key-navigation](https://github.com/dead/react-key-navigation) - Spatial Navigation components for React. Similar to the ["Focus Management"](http://bbc.github.io/tal/widgets/focus-management.html) of the [BBC TAL](https://bbc.github.io/tal/).
* [react-spatial-navigation](https://github.com/NoriginMedia/react-spatial-navigation) - HOC-based Spatial Navigation (key navigation) solution for React.

## Testing
* [Suitest](https://suite.st) - Test automation solution for Smart TVs, gaming consoles, streaming sticks etc.
* [stb-tester](https://github.com/stb-tester/stb-tester) - Automated User Interface Testing for Set-Top Boxes & Smart TVs (python).

## Misc
* [LIRC](http://lirc.org) - A package that allows you to decode and send infra-red signals of many (but not all) commonly used remote controls.
* [awesome-smarttv](https://github.com/linuxenko/awesome-smarttv) - Another list of Smart TV resources. Discovered after this one was already done :roll_eyes:.
* [docker-tizen-webos-sdk](https://github.com/vitalets/docker-tizen-webos-sdk) - Docker image with Samsung Tizen CLI and LG webOS CLI. Allows to develop, build, launch and debug Smart TV apps without installing Tizen Studio and webOS SDK.

## Community
* [Stack Overflow](http://stackoverflow.com/questions/tagged/smart-tv)
* [Reddit](https://www.reddit.com/r/smarttv)

## Contribute
Feel free to share your experience and contribute useful extension resources by creating [new issue](https://github.com/vitalets/awesome-smart-tv/issues) or [pull request](https://github.com/vitalets/awesome-smart-tv/pulls).
Please read the [contribution guidelines](https://github.com/vitalets/awesome-smart-tv/blob/master/CONTRIBUTING.md) first. Thanks!

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
