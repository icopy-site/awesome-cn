<div class="github-widget" data-repo="vitalets/awesome-smart-tv"></div>
## Awesome Smart TV [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;用于构建智能电视应用程序的精彩资源的精选列表

<a href="https://raw.githubusercontent.com/vitalets/awesome-smart-tv"><img align="right" width="150" src="https://user-images.githubusercontent.com/1473072/27913047-7c3a5e60-6267-11e7-8bd1-bef2bf3cd753.png"/></a>

[Smart TV](https://en.wikipedia.org/wiki/Smart_TV)  是一个不断发展的电视平台，可以访问互联网并允许浏览网站和安装应用程序.  它拥有自己的生态系统，主要参与者包括三星，LG，Android TV和Apple TV.  在此列表中，您将找到用于开发智能电视应用程序以及从远程设备与电视进行通信的官方和第三方资源.


## Platforms
 以下是最受欢迎的智能电视平台.  完整列表是 [here](https://en.wikipedia.org/wiki/List_of_smart_TV_platforms_and_middleware_software).

### Samsung Tizen
#### Official resources
* [Samsung TV Developers site](http://developer.samsung.com/tv) - 新闻，文档和SDK下载.
* [Tizen TV Developers site](https://developer.tizen.org/tizen/tv) - 完整的API文档和开发Tizen TV应用程序的指南.
* [Tizen Studio](https://developer.tizen.org/development/tizen-studio/download) - 用于电视应用开发的IDE，包括Tizen TV Emulator.
* [Smart View SDK](http://developer.samsung.com/tv/develop/extension-libraries/smart-view-sdk/download/) - 官方Android，IOS和JavaScript SDK，用于远程设备和Samsung Smart TV之间的通信.
* [Samsung TV Developers Forum](http://developer.samsung.com/forum/?topCtgy=06) - 使用Samsung SDK开发应用程序时提出问题并分享提示.
* [Samsung Smart TV Bug Bounty](https://samsungtvbounty.com) - If you find bug in Samsung TV, submit it here and get a reward $1000+.
* [vscode-extension-tizentv](https://marketplace.visualstudio.com/items?itemName=tizensdk.tizentv) -  Visual Studio代码扩展，为Tizen应用程序开发人员提供轻量级IDE.
* [Wits](https://github.com/Samsung/Wits) - 每次进行更改时重新加载电视应用程序的JavaScript / CSS而无需重新安装应用程序的工具.

#### Third-party remote control libraries
* [samsungctl](https://github.com/Ape/samsungctl)   - 用于通过TCP / IP连接远程控制三星电视的库和命令行工具.  它目前支持2016年之前的电视以及大多数具有以太网或Wi-Fi连接（Python）的现代Tizen-OS电视.
* [samsung-tv-remote](https://github.com/Badisi/samsung-tv-remote) - 从2016年开始远程控制三星智能电视的Node.js模块（JavaScript）.
* [homebridge-samsungtv2016](https://github.com/kyleaa/homebridge-samsungtv2016) - 一个插件 [Homebridge](https://github.com/nfarina/homebridge) 这使您可以使用HomeKit和Siri（JavaScript）控制2016年的三星电视.
* [homebridge-samsung-tizen](https://github.com/tavicu/homebridge-samsung-tizen) - 一个插件 [Homebridge](https://github.com/nfarina/homebridge) 这使您可以使用HomeKit和Siri（JavaScript）控制Samsung Tizen电视.
* [samsung-remote-models-2014-and-newer](https://github.com/tdudek/samsung-remote-models-2014-and-newer) - 与2014年以上的三星电视机型的内部网络服务进行加密通信.
* [SmartCrypto](https://github.com/sectroyer/SmartCrypto) -  C / Python中的SmartView2加密握手API实现.
* [samsung-messagebox](https://github.com/shantanugoel/samsung-messagebox) - 用于在三星电视上显示通知的Python脚本.

#### Other
* [Identification of Samsung TV models 2008-2017](http://en.tab-tv.com/?page_id=7123) - 如何从三星电视型号名称获取屏幕尺寸，矩阵类型，开发年份，系列和ohter参数.

### LG webOS
#### Official resources
* [webOS TV Developers Site](http://webostv.developer.lge.com) -  WebOS TV应用程序开发原则，教程，API文档和打包工具.
* [webOS TV IDE + SDK](http://webostv.developer.lge.com/sdk/download/download-sdk/) - 用于应用程序开发的IDE，包括命令行界面和模拟器.
* [Connect SDK](http://www.svlconnectsdk.com/)   - 由LG开发的开源框架，将您的移动应用程序与多个媒体设备平台连接起来.  目前支持8个平台.  但似乎 [abandoned](https://github.com/ConnectSDK/Connect-SDK-Android/issues/364).
* [webOS TV Developers Forum](http://developer.lge.com/community/forums/RetrieveForumList.dev?prodTypeCode=TV) - 向其他开发人员提问，分享信息并了解智能电视应用开发.

#### Third-party remote control libraries
* [lgtv2](https://github.com/hobbyquaker/lgtv2) -  Node.js模块，用于通过WebSocket消息（JavaScript）远程控制LG webOS TV.
* [node-red-contrib-lgtv](https://github.com/hobbyquaker/node-red-contrib-lgtv) - 模块 [Node-RED](https://nodered.org) 允许远程控制LG webOS智能电视（JavaScript）.
* [node-webos](https://github.com/WeeJeWel/node-webos) -  Node.js模块，用于发现和控制webOS电视（JavaScript）.
* [lgtv2mqtt](https://github.com/hobbyquaker/lgtv2mqtt) -  LG WebOS智能电视和MQTT（JavaScript）之间的接口.
* [ares-webos-sdk](https://github.com/stevenvong/ares-webos-sdk) -  webOS [CLI](http://webostv.developer.lge.com/sdk/using-webos-tv-cli/) 作为单独的NPM模块（JavaScript）.
* [pylgtv](https://github.com/TheRealLink/pylgtv) - 用于控制基于webOS的LG电视设备（Python）的库.
* [LGWebOSRemote](https://github.com/klattimer/LGWebOSRemote) - 用于LGOS远程控制LG TV（Python）的命令行工具.
* [homebridge-webos-tv](https://github.com/merdok/homebridge-webos-tv) - 一个插件 [Homebridge](https://github.com/nfarina/homebridge) 它允许您控制您的webOS电视.

#### Articles
* [LG webOS communication protocol](https://mym.hackpad.com/ep/pad/static/rLlshKkzdNj) -  webOS TV通信端点的非官方但详细的描述.

#### Videos
* [LG Magic Motion Remote - Point, Click, and Control](https://youtu.be/yxu0G7jM_us) - 像电脑鼠标一样操作电视.

#### Other
* [openlgtv.org.ru](http://openlgtv.org.ru)   - 用于LG电视固件的法律逆向工程和研究的非商业项目.  似乎有点过时但包含很多信息.
* [Identification of LG TV models 2011-2017](http://en.tab-tv.com/?page_id=7111) - 如何从LG TV型号名称获取屏幕尺寸，矩阵类型，开发年份，系列和ohter参数.

### Android TV
#### Official resources
* [Android TV Developers site](https://developer.android.com/training/tv/start/start.html) - 构建Android TV应用程序的文档，教程和最佳实践.

### Apple tvOS
#### Official resources
* [tvOS Developers Site](https://developer.apple.com/tvos/) - 用于开发tvOS应用程序的SDK，文档和教程.
* [TVML](https://developer.apple.com/documentation/tvml) - 用于创建tvOS应用程序的Apple TV标记语言.

### Google Chromecast
#### Official resources
* [Google Cast SDK](https://developers.google.com/cast/) - 官方Google Cast SDK文档和教程.
* [TVs with Chromecast built-in](https://www.google.com/chromecast/built-in/tv/) - 支持内置Chromecast的供应商列表以及优于传统电视遥控器的优势.

## Cross-platform frameworks
* [react-tv](https://github.com/raphamorim/react-tv) - 电视的反应开发：低内存应用程序的渲染器和WebOS的Packager，Tizen，Orsay.
* [TOAST](http://developer.samsung.com/tv/develop/extension-libraries/toast/) - 开发多平台电视应用的三星开源框架.
* [Enyo](http://enyojs.com) - 适用于所有主要平台的开发应用程序的LG框架，从手机和平板电脑到PC和电视.
* [Smartbox](https://github.com/immosmart/smartbox) - 适用于三星，LG，飞利浦，SmartTV Aliance，STB Mag应用开发的智能电视通用库.
* [Mautilus Smart TV SDK](https://github.com/mautilus/sdk)   - 用于开发电视应用程序的平台无关框架.  支持三星，LG，飞利浦，索尼，松下和VESTEL智能电视.
* [BBC TAL](https://bbc.github.io/tal/) - 由BBC工程师开发的用于构建智能电视应用程序的开源库.
* [PureQML TV](https://github.com/pureqml/qmlcore-tv)   - 基于Web的SmartTV / STB平台的声明式前端框架.  有Android TV的实验支持.

## Remote control protocols
* [DLNA](https://en.wikipedia.org/wiki/Digital_Living_Network_Alliance)   - 通过家庭网络共享数据的行业标准.  根据您拥有的DLNA兼容设备，您可以将电影从笔记本电脑流式传输到电视，通过高保真音响系统播放存储在手机上的MP3，或者从家用打印机上的平板电脑打印照片.
* [Wi-Fi Direct](https://en.wikipedia.org/wiki/Wi-Fi_Direct) - 标准启用设备，无需无线接入点即可轻松连接.
* [Miracast](https://en.wikipedia.org/wiki/Miracast)   - 从设备（如笔记本电脑，平板电脑或智能手机）到显示器（如电视，显示器或投影仪）的无线连接标准.  适用于Wi-Fi Direct.

## Misc
* [LIRC](http://lirc.org) - 一个软件包，允许您解码和发送许多（但不是全部）常用遥控器的红外信号.
* [smart-tv-app-dev-guidelines](https://github.com/ruiposse/smart-tv-app-dev-guidelines)   - 智能电视应用程序开发示例，教程，最佳实践和文档.  最后更新于2015年.
* [awesome-smarttv](https://github.com/linuxenko/awesome-smarttv)   - 另一个智能电视资源列表.  在这个已经完成之后发现：roll_eyes：.
* [lrud](https://github.com/stuart-williams/lrud)   - 左，右，上，下.  用于通过方向控制输入的设备的空间导航库.

## Community
* [Stack Overflow](http://stackoverflow.com/questions/tagged/smart-tv)
* [Reddit](https://www.reddit.com/r/smarttv)

## Contribute
您可以通过创建来分享您的经验并贡献有用的扩展资源 [new issue](https://github.com/vitalets/awesome-smart-tv/issues) 要么 [pull request](https://github.com/vitalets/awesome-smart-tv/pulls).
请阅读 [contribution guidelines](https://github.com/vitalets/awesome-smart-tv/blob/master/CONTRIBUTING.md)  第一.  谢谢！

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
