<div class="github-widget" data-repo="vitalets/awesome-smart-tv"></div>
## Awesome Smart TV [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 用于构建智能电视应用程序的精选资源列表

<a href="https://raw.githubusercontent.com/vitalets/awesome-smart-tv"><img align="right" width="150" src="https://user-images.githubusercontent.com/1473072/27913047-7c3a5e60-6267-11e7-8bd1-bef2bf3cd753.png"/></a>

[Smart TV](https://en.wikipedia.org/wiki/Smart_TV) 是一个不断发展的电视平台，可以访问互联网并允许浏览网站和安装应用程序. 它拥有自己的生态系统，主要参与者包括三星、LG、Android TV 和 Apple TV. 在此列表中，您将找到用于开发智能电视应用程序和从远程设备与电视通信的官方和第三方资源.


## Platforms
以下是最流行的智能电视平台. 完整列表是 [here](https://en.wikipedia.org/wiki/List_of_smart_TV_platforms_and_middleware_software).

### Samsung Tizen
#### Official resources
* [Samsung TV Developers site](http://developer.samsung.com/tv) - 新闻、文档和 SDK 下载.
* [Tizen TV Developers site](https://developer.tizen.org/tizen/tv) - 用于开发 Tizen TV 应用程序的完整 API 文档和指南.
* [Tizen Studio](https://developer.tizen.org/development/tizen-studio/download) - 用于电视应用程序开发的 IDE，包括 Tizen TV Emulator.
* [Smart View SDK](http://developer.samsung.com/tv/develop/extension-libraries/smart-view-sdk/download/) - 用于远程设备和三星智能电视之间通信的官方 Android、IOS 和 JavaScript SDK.
* [Samsung TV Developers Forum](http://developer.samsung.com/forum/?topCtgy=06) - 在使用三星 SDK 开发应用程序时提出问题并分享技巧.
* [Samsung Smart TV Bug Bounty](https://samsungtvbounty.com) - 如果您在三星电视中发现错误，请在此处提交并获得 1000 美元以上的奖励.
* [vscode-extension-tizentv](https://marketplace.visualstudio.com/items?itemName=tizensdk.tizentv) - 为 Tizen 应用程序开发人员提供轻量级 IDE 的 Visual Studio Code 扩展.
* [Wits](https://github.com/Samsung/Wits) - 用于重新加载电视应用程序的 JavaScript/CSS 的工具，而无需在每次进行更改时重新安装应用程序.

#### Third-party remote control libraries
* [samsungctl](https://github.com/Ape/samsungctl)  - 用于通过 TCP/IP 连接远程控制三星电视的库和命令行工具. 它目前支持 2016 年之前的电视以及大多数具有以太网或 Wi-Fi 连接（Python）的现代 Tizen-OS 电视.
* [samsung-tv-remote](https://github.com/Badisi/samsung-tv-remote) - 从 2016 年开始远程控制三星智能电视的 Node.js 模块 (JavaScript).
* [homebridge-samsungtv2016](https://github.com/kyleaa/homebridge-samsungtv2016) - 一个插件 [Homebridge](https://github.com/nfarina/homebridge) 允许您使用 HomeKit 和 Siri (JavaScript) 控制您的 2016 三星电视.
* [homebridge-samsung-tizen](https://github.com/tavicu/homebridge-samsung-tizen) - 一个插件 [Homebridge](https://github.com/nfarina/homebridge) 允许您使用 HomeKit 和 Siri (JavaScript) 控制您的三星 Tizen 电视.
* [samsung-remote-models-2014-and-newer](https://github.com/tdudek/samsung-remote-models-2014-and-newer) - 与三星电视型号 2014+ 的内部网络服务进行加密通信.
* [SmartCrypto](https://github.com/sectroyer/SmartCrypto) - SmartView2 加密握手 API 在 C/Python 中的实现.
* [samsung-messagebox](https://github.com/shantanugoel/samsung-messagebox) - 在三星电视上显示通知的 Python 脚本.
* [samsung-tv-control](https://github.com/Toxblh/samsung-tv-control) - 在你的 Node.js 中远程控制三星电视的库

#### Other
* [Identification of Samsung TV models 2008-2017](http://en.tab-tv.com/?page_id=7123) - 如何从三星电视型号名称中获取屏幕尺寸、矩阵类型、开发年份、系列和其他参数.
* [Tizen Studio development references](https://github.com/claromes/tizenstudio) - 基于个人研究的专注于智能电视和专业显示器网络应用程序的文档.

### LG webOS
#### Official resources
* [webOS TV Developers Site](http://webostv.developer.lge.com) - WebOS TV 应用程序开发原则、教程、API 文档和打包工具.
* [webOS TV IDE + SDK](http://webostv.developer.lge.com/sdk/download/download-sdk/) - 用于应用程序开发的 IDE，包括命令行界面和模拟器.
* [Connect SDK](http://www.svlconnectsdk.com/)  - 由 LG 开发的开源框架，可将您的移动应用程序与多个媒体设备平台连接起来. 目前支持8个平台. 但似乎 [abandoned](https://github.com/ConnectSDK/Connect-SDK-Android/issues/364).
* [webOS TV Developers Forum](http://developer.lge.com/community/forums/RetrieveForumList.dev?prodTypeCode=TV) - 提出问题、分享信息并与其他开发人员一起了解 Smart TV 应用程序开发.

#### Third-party remote control libraries
* [lgtv2](https://github.com/hobbyquaker/lgtv2) - 用于通过 WebSocket 消息 (JavaScript) 远程控制 LG webOS TV 的 Node.js 模块.
* [node-red-contrib-lgtv](https://github.com/hobbyquaker/node-red-contrib-lgtv) - 模块 [Node-RED](https://nodered.org) 允许远程控制 LG webOS 智能电视 (JavaScript).
* [node-webos](https://github.com/WeeJeWel/node-webos) - 用于发现和控制 webOS 电视 (JavaScript) 的 Node.js 模块.
* [lgtv2mqtt](https://github.com/hobbyquaker/lgtv2mqtt) - LG WebOS 智能电视和 MQTT (JavaScript) 之间的接口.
* [ares-webos-sdk](https://github.com/stevenvong/ares-webos-sdk) - 网络操作系统 [CLI](http://webostv.developer.lge.com/sdk/using-webos-tv-cli/) 作为单独的 NPM 模块 (JavaScript).
* [pylgtv](https://github.com/TheRealLink/pylgtv) - 用于控制基于 webOS 的 LG 电视设备（Python）的库.
* [LGWebOSRemote](https://github.com/klattimer/LGWebOSRemote) - 用于 LG 电视的 webOS 远程控制的命令行工具（Python）.
* [homebridge-webos-tv](https://github.com/merdok/homebridge-webos-tv) - 一个插件 [Homebridge](https://github.com/nfarina/homebridge) 它允许您控制您的 webOS 电视.
* [PyWebOSTV](https://github.com/supersaiyanmode/PyWebOSTV) - 通用且可扩展的 WebOS 3.0 客户端库（Python2、Python3）.
* [go-webos](https://github.com/vitalets/awesome-smart-tv/blob/master/github.com/kaperys/go-webos) - 用于与 webOS 电视 (golang) 交互的小型 Go 库.

#### Videos
* [LG Magic Motion Remote - Point, Click, and Control](https://youtu.be/yxu0G7jM_us) - 像电脑鼠标一样操作电视.

#### Other
* [openlgtv.org.ru](http://openlgtv.org.ru)  - 合法逆向工程和 LG 电视固件研究的非商业项目. 看起来有点过时，但包含很多信息.
* [Identification of LG TV models 2011-2017](http://en.tab-tv.com/?page_id=7111) - 如何从 LG 电视型号名称中获取屏幕尺寸、矩阵类型、开发年份、系列和其他参数.

### Android TV
#### Official resources
* [Android TV Developers site](https://developer.android.com/training/tv/start/start.html) - 用于构建 Android TV 应用程序的文档、教程和最佳实践.

#### Articles
* [How to develop Android TV App?](https://medium.com/@halilozel1903/how-to-develop-android-tv-app-5e251f3aa56b) - 一篇关于为 Android TV 开发应用程序的文章.

### Apple tvOS
#### Official resources
* [tvOS Developers Site](https://developer.apple.com/tvos/) - 用于开发 tvOS 应用程序的 SDK、文档和教程.
* [TVML](https://developer.apple.com/documentation/tvml) - 用于创建 tvOS 应用程序的 Apple TV 标记语言.

### Google Chromecast
#### Official resources
* [Google Cast SDK](https://developers.google.com/cast/) - 官方 Google Cast SDK 文档和教程.
* [TVs with Chromecast built-in](https://www.google.com/chromecast/built-in/tv/) - 支持内置 Chromecast 的供应商列表以及相对于传统电视遥控器的优势.

## Cross-platform frameworks
* [react-tv](https://github.com/raphamorim/react-tv) - 电视的 React 开发：低内存应用程序的渲染器和 WebOS、Tizen、Orsay 的打包器.
* [TOAST](http://developer.samsung.com/tv/develop/extension-libraries/toast/) - 用于开发多平台电视应用程序的三星开源框架.
* [Enyo](http://enyojs.com) - 适用于所有主要平台（从手机和平板电脑到个人电脑和电视）的开发应用程序的 LG 框架.
* [Smartbox](https://github.com/immosmart/smartbox) - 用于三星、LG、飞利浦、SmartTV Aliance、STB Mag 应用程序开发的智能电视通用库.
* [Mautilus Smart TV SDK](https://github.com/mautilus/sdk)  - 用于开发电视应用程序的平台无关框架. 支持三星、LG、飞利浦、索尼、松下和 VESTEL 智能电视.
* [BBC TAL](https://bbc.github.io/tal/) - 用于构建由 BBC 工程师开发的智能电视应用程序的开源库.
* [PureQML TV](https://github.com/pureqml/qmlcore-tv)  - 用于基于 Web 的 SmartTV/STB 平台的声明式前端框架. 有Android TV的实验性支持.
* [ZombieBox](https://github.com/interfaced/zombiebox)  - 开源智能电视框架. 强类型的 JavaScript，基于组件，内置 D-PAD 导航管理，抽象视频 API，带有适用于所有平台的 DRM. 支持许多平台，如 Tizen、webOS、Android TV 等. 

## Remote control protocols
* [DLNA](https://en.wikipedia.org/wiki/Digital_Living_Network_Alliance)  - 通过家庭网络共享数据的行业标准. 根据您拥有的 DLNA 兼容设备，您可能能够将电影从笔记本电脑流式传输到电视，通过高保真系统播放手机上存储的 MP3，或者在家用打印机上从平板电脑打印照片.
* [Wi-Fi Direct](https://en.wikipedia.org/wiki/Wi-Fi_Direct) - 标准使设备无需无线接入点即可轻松相互连接.
* [Miracast](https://en.wikipedia.org/wiki/Miracast)  - 从设备（如笔记本电脑、平板电脑或智能手机）到显示器（如电视、显示器或投影仪）的无线连接标准. 通过 Wi-Fi Direct 工作.

## Navigation libraries
* [lrud](https://github.com/stuart-williams/lrud)  - 左、右、上、下. 通过方向控制输入的设备的空间导航库.
* [js-spatial-navigation](https://github.com/luke-chang/js-spatial-navigation) - 基于 javascript 的空间导航实现.
* [react-js-spatial-navigation](https://github.com/dead/react-js-spatial-navigation) - js-spatial-navigation 的包装器来反应组件.
* [react-key-navigation](https://github.com/dead/react-key-navigation)  - React 的空间导航组件. 类似于 ["Focus Management"](http://bbc.github.io/tal/widgets/focus-management.html)  [BBC TAL](https://bbc.github.io/tal/).
* [react-spatial-navigation](https://github.com/NoriginMedia/react-spatial-navigation) - 基于 HOC 的 React 空间导航（按键导航）解决方案.

## Testing
* [Suitest](https://suite.st) - 智能电视、游戏机、流媒体棒等的测试自动化解决方案.
* [stb-tester](https://github.com/stb-tester/stb-tester) - 机顶盒和智能电视的自动化用户界面测试（python）.

## Misc
* [LIRC](http://lirc.org) - 一个包，允许您解码和发送许多（但不是全部）常用遥控器的红外线信号.
* [awesome-smarttv](https://github.com/linuxenko/awesome-smarttv)  - 另一个智能电视资源列表. 在这个已经完成之后发现：roll_eyes：.
* [docker-tizen-webos-sdk](https://github.com/vitalets/docker-tizen-webos-sdk)  - 带有 Samsung Tizen CLI 和 LG webOS CLI 的 Docker 镜像. 无需安装 Tizen Studio 和 webOS SDK 即可开发、构建、启动和调试智能电视应用程序.

## Community
* [Stack Overflow](http://stackoverflow.com/questions/tagged/smart-tv)
* [Reddit](https://www.reddit.com/r/smarttv)

## Contribute
随意分享您的经验并通过创建贡献有用的扩展资源 [new issue](https://github.com/vitalets/awesome-smart-tv/issues) or [pull request](https://github.com/vitalets/awesome-smart-tv/pulls).
请阅读 [contribution guidelines](https://github.com/vitalets/awesome-smart-tv/blob/master/CONTRIBUTING.md) 第一的. 谢谢！

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
