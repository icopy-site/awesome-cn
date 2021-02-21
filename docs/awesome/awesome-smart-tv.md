<div class="github-widget" data-repo="vitalets/awesome-smart-tv"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Smart TV [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精选清单，用于构建智能电视应用程序

<a href="https://raw.githubusercontent.com/vitalets/awesome-smart-tv"><img align="right" width="150" src="https://user-images.githubusercontent.com/1473072/27913047-7c3a5e60-6267-11e7-8bd1-bef2bf3cd753.png"/></a>

[Smart TV](https://en.wikipedia.org/wiki/Smart_TV) 是不断发展的电视平台，可以访问互联网并允许浏览网站和安装应用程序. 它拥有自己的生态系统，主要参与者包括三星，LG，Android TV和Apple TV. 在此列表中，您将找到用于开发智能电视应用程序以及从远程设备与电视进行通信的官方和第三方资源.


## Platforms
以下是智能电视最受欢迎的平台. 完整列表是 [here](https://en.wikipedia.org/wiki/List_of_smart_TV_platforms_and_middleware_software).

### Samsung Tizen
#### Official resources
* [Samsung TV Developers site](http://developer.samsung.com/tv) -新闻，文档和SDK下载.
* [Tizen TV Developers site](https://developer.tizen.org/tizen/tv) - Full API documentation and guides for developing Tizen TV apps.
* [Tizen Studio](https://developer.tizen.org/development/tizen-studio/download) -用于电视应用程序开发的IDE，包括Tizen TV Emulator.
* [Smart View SDK](http://developer.samsung.com/tv/develop/extension-libraries/smart-view-sdk/download/) -官方Android，IOS和JavaScript SDK，用于在远程设备和Samsung Smart TV之间进行通信.
* [Samsung TV Developers Forum](http://developer.samsung.com/forum/?topCtgy=06) -在使用Samsung SDK开发应用程序时提出问题并分享提示.
* [Samsung Smart TV Bug Bounty](https://samsungtvbounty.com) -如果您发现三星电视中的错误，请在此处提交并获得$ 1000 +的奖励.
* [vscode-extension-tizentv](https://marketplace.visualstudio.com/items?itemName=tizensdk.tizentv) -一个Visual Studio Code扩展，为Tizen应用程序开发人员提供了轻量级的IDE.
* [Wits](https://github.com/Samsung/Wits) -一种用于重新加载电视应用程序的JavaScript / CSS而无需在每次更改时都重新安装应用程序的工具.

#### Third-party remote control libraries
* [samsungctl](https://github.com/Ape/samsungctl)  -用于通过TCP / IP连接远程控制三星电视的库和命令行工具. 它目前支持2016年前的电视以及大多数具有以太网或Wi-Fi连接（Python）的现代Tizen-OS电视.
* [samsung-tv-remote](https://github.com/Badisi/samsung-tv-remote) -从2016年开始，Node.js模块可远程控制Samsung Smart TV（JavaScript）.
* [homebridge-samsungtv2016](https://github.com/kyleaa/homebridge-samsungtv2016) -的插件 [Homebridge](https://github.com/nfarina/homebridge) 这样您就可以使用HomeKit和Siri（JavaScript）控制您的2016 Samsung TV.
* [homebridge-samsung-tizen](https://github.com/tavicu/homebridge-samsung-tizen) -的插件 [Homebridge](https://github.com/nfarina/homebridge) 使您可以通过HomeKit和Siri（JavaScript）控制Samsung Tizen TV.
* [samsung-remote-models-2014-and-newer](https://github.com/tdudek/samsung-remote-models-2014-and-newer) -与三星电视型号2014+的内部Web服务的加密通信.
* [SmartCrypto](https://github.com/sectroyer/SmartCrypto) -C / Python中的SmartView2加密握手API实现.
* [samsung-messagebox](https://github.com/shantanugoel/samsung-messagebox) -在三星电视上显示通知的Python脚本.
* [samsung-tv-control](https://github.com/Toxblh/samsung-tv-control) -Node.js中用于远程控制三星电视的库

#### Other
* [Identification of Samsung TV models 2008-2017](http://en.tab-tv.com/?page_id=7123) -如何从三星电视型号名称获取屏幕尺寸，矩阵类型，开发年份，系列和其他参数.
* [Tizen Studio development references](https://github.com/claromes/tizenstudio) -基于个人研究的文档，专注于智能电视e专业显示器的Web应用程序.

### LG webOS
#### Official resources
* [webOS TV Developers Site](http://webostv.developer.lge.com) -WebOS TV应用程序开发原理，教程，API文档和打包工具.
* [webOS TV IDE + SDK](http://webostv.developer.lge.com/sdk/download/download-sdk/) -用于应用程序开发的IDE，包括命令行界面和模拟器.
* [Connect SDK](http://www.svlconnectsdk.com/)  -LG开发的开源框架，可将您的移动应用程序与多个媒体设备平台连接起来. 目前支持8个平台. 但是似乎 [abandoned](https://github.com/ConnectSDK/Connect-SDK-Android/issues/364).
* [webOS TV Developers Forum](http://developer.lge.com/community/forums/RetrieveForumList.dev?prodTypeCode=TV) -提出问题，共享信息并与其他开发人员一起学习有关智能电视应用程序的开发.

#### Third-party remote control libraries
* [lgtv2](https://github.com/hobbyquaker/lgtv2) -Node.js模块，用于通过WebSocket消息（JavaScript）远程控制LG webOS TV.
* [node-red-contrib-lgtv](https://github.com/hobbyquaker/node-red-contrib-lgtv) -模块 [Node-RED](https://nodered.org) 允许远程控制LG webOS智能电视（JavaScript）.
* [node-webos](https://github.com/WeeJeWel/node-webos) -Node.js模块，用于发现和控制WebOS电视（JavaScript）.
* [lgtv2mqtt](https://github.com/hobbyquaker/lgtv2mqtt) -LG WebOS智能电视和MQTT（JavaScript）之间的接口.
* [ares-webos-sdk](https://github.com/stevenvong/ares-webos-sdk) -webOS [CLI](http://webostv.developer.lge.com/sdk/using-webos-tv-cli/) 作为单独的NPM模块（JavaScript）.
* [pylgtv](https://github.com/TheRealLink/pylgtv) -用于控制基于webOS的LG Tv设备的库（Python）.
* [LGWebOSRemote](https://github.com/klattimer/LGWebOSRemote) -用于LG TV的webOS远程控制的命令行工具（Python）.
* [homebridge-webos-tv](https://github.com/merdok/homebridge-webos-tv) -的插件 [Homebridge](https://github.com/nfarina/homebridge) 这使您可以控制webOS电视.
* [PyWebOSTV](https://github.com/supersaiyanmode/PyWebOSTV) -通用且可扩展的WebOS 3.0客户端库（Python2，Python3）.
* [go-webos](https://github.com/vitalets/awesome-smart-tv/blob/master/github.com/kaperys/go-webos) -小型Go库，用于与webOS电视（golang）进行交互.

#### Videos
* [LG Magic Motion Remote - Point, Click, and Control](https://youtu.be/yxu0G7jM_us) -像电脑鼠标一样操作电视.

#### Other
* [openlgtv.org.ru](http://openlgtv.org.ru)  -一个非商业项目，用于合法反向工程和LG电视固件的研究. 似乎有些过时了，但包含了很多信息.
* [Identification of LG TV models 2011-2017](http://en.tab-tv.com/?page_id=7111) -如何从LG TV型号名称中获取屏幕尺寸，矩阵类型，开发年份，系列和其他参数.

### Android TV
#### Official resources
* [Android TV Developers site](https://developer.android.com/training/tv/start/start.html) -用于构建Android TV应用程序的文档，教程和最佳做法.

#### Articles
* [How to develop Android TV App?](https://medium.com/@halilozel1903/how-to-develop-android-tv-app-5e251f3aa56b) -有关为Android TV开发应用程序的文章.

### Apple tvOS
#### Official resources
* [tvOS Developers Site](https://developer.apple.com/tvos/) -用于开发tvOS应用程序的SDK，文档和教程.
* [TVML](https://developer.apple.com/documentation/tvml) -用于创建tvOS应用程序的Apple TV标记语言.

### Google Chromecast
#### Official resources
* [Google Cast SDK](https://developers.google.com/cast/) -官方的Google Cast SDK文档和教程.
* [TVs with Chromecast built-in](https://www.google.com/chromecast/built-in/tv/) -支持内置Chromecast的厂商列表以及相对于传统电视遥控器的优势.

## Cross-platform frameworks
* [react-tv](https://github.com/raphamorim/react-tv) -TV的React开发：适用于低内存应用程序的渲染器，以及适用于WebOS，Tizen和Orsay的Packager.
* [TOAST](http://developer.samsung.com/tv/develop/extension-libraries/toast/) -开发多平台电视应用程序的三星开源框架.
* [Enyo](http://enyojs.com) -LG框架，适用于从电话和平板电脑到PC和电视的所有主要平台的开发应用程序.
* [Smartbox](https://github.com/immosmart/smartbox) -适用于三星，LG，飞利浦，SmartTV Aliance，STB Mag应用程序开发的智能电视通用库.
* [Mautilus Smart TV SDK](https://github.com/mautilus/sdk)  -用于开发TV Apps的与平台无关的框架. 支持三星，LG，飞利浦，索尼，松下和VESTEL智能电视.
* [BBC TAL](https://bbc.github.io/tal/) -由BBC工程师开发的用于构建智能电视应用程序的开源库.
* [PureQML TV](https://github.com/pureqml/qmlcore-tv)  -用于基于Web的SmartTV / STB平台的声明性前端框架. 具有对Android TV的实验支持.
* [ZombieBox](https://github.com/interfaced/zombiebox)  -开源的智能电视框架. 类型严格的JavaScript，基于组件的内置D-PAD导航管理，带有DRM的抽象视频API，适用于所有平台. 支持Tizen，webOS，Android TV等许多平台. 

## Remote control protocols
* [DLNA](https://en.wikipedia.org/wiki/Digital_Living_Network_Alliance)  -通过家庭网络共享数据的行业标准. 根据所拥有的DLNA兼容设备的不同，您可能可以将电影从笔记本电脑流式传输到电视上，可以通过高保真系统播放手机上存储的MP3，或者在家用打印机上从平板电脑上打印照片.
* [Wi-Fi Direct](https://en.wikipedia.org/wiki/Wi-Fi_Direct) -标准启用设备，无需无线接入点即可轻松相互连接.
* [Miracast](https://en.wikipedia.org/wiki/Miracast)  -从设备（例如笔记本电脑，平板电脑或智能手机）到显示器（例如电视，显示器或投影仪）的无线连接的标准. 通过Wi-Fi Direct工作.

## Navigation libraries
* [lrud](https://github.com/stuart-williams/lrud)  -左，右，上，下. 通过方向控制输入的设备的空间导航库.
* [js-spatial-navigation](https://github.com/luke-chang/js-spatial-navigation) -基于JavaScript的空间导航实现.
* [react-js-spatial-navigation](https://github.com/dead/react-js-spatial-navigation) -用来响应组件的js-spatial-navigation的包装器.
* [react-key-navigation](https://github.com/dead/react-key-navigation)  -用于React的空间导航组件. 类似于 ["Focus Management"](http://bbc.github.io/tal/widgets/focus-management.html)  [BBC TAL](https://bbc.github.io/tal/).
* [react-spatial-navigation](https://github.com/NoriginMedia/react-spatial-navigation) -React的基于HOC的空间导航（键导航）解决方案.

## Testing
* [Suitest](https://suite.st) -用于智能电视，游戏机，流媒体棒等的测试自动化解决方案.
* [stb-tester](https://github.com/stb-tester/stb-tester) -机顶盒和智能电视（python）的自动用户界面测试.

## Misc
* [LIRC](http://lirc.org) -允许您解码和发送许多（但不是全部）常用遥控器的红外信号的软件包.
* [awesome-smarttv](https://github.com/linuxenko/awesome-smarttv)  -另一个智能电视资源列表. 在完成此操作后发现：roll_eyes:.
* [docker-tizen-webos-sdk](https://github.com/vitalets/docker-tizen-webos-sdk)  -使用Samsung Tizen CLI和LG webOS CLI的Docker映像. 无需安装Tizen Studio和webOS SDK，即可开发，构建，启动和调试智能电视应用程序.

## Community
* [Stack Overflow](http://stackoverflow.com/questions/tagged/smart-tv)
* [Reddit](https://www.reddit.com/r/smarttv)

## Contribute
随时分享您的经验，并通过创建来贡献有用的扩展资源 [new issue](https://github.com/vitalets/awesome-smart-tv/issues) 或者 [pull request](https://github.com/vitalets/awesome-smart-tv/pulls).
请阅读 [contribution guidelines](https://github.com/vitalets/awesome-smart-tv/blob/master/CONTRIBUTING.md) 第一的. 谢谢！

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
