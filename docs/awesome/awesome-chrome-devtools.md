## Awesome chrome-devtools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; Chrome DevTools生态系统中令人敬畏的工具和资源

## Contents

- [Learning](#learning)
- [DevTools as an IDE](#devtools-as-an-ide)
- [DevTools tooling and ecosystem](#devtools-tooling-and-ecosystem)
- [Chrome DevTools Protocol](#chrome-devtools-protocol)
- [Protocol Driver Libraries](#protocol-driver-libraries)
- [Developing with the protocol](#developing-with-the-protocol)
- [Browser Adapters](#browser-adapters)
- [Using DevTools frontend with other platforms](#using-devtools-frontend-with-other-platforms)
- [DevTools Extensions](#devtools-extensions)

## Learning
- [Dev Tips](https://umaar.com/dev-tips/) - 作为GIF动画的大量提示.

## DevTools as an IDE
- [Chrome DevTools App](https://github.com/auchenberg/chrome-devtools-app) - 可以检查各种目标的独立应用程序.
- [DevTools Remote](https://github.com/auchenberg/devtools-remote) - 远程调试其他人的浏览器.
- [DevTools Snippets](https://github.com/bahmutov/code-snippets) - 片段集.

---

## DevTools tooling and ecosystem

### Object formatting
- [immutable-devtools](https://github.com/andrewdavey/immutable-devtools) -  Immutable-js值的自定义格式化程序.

### Network Inspection
- [betwixt](https://github.com/kdzwinel/betwixt) - 系统级网络代理，通过网络面板提供检查.

### CPU profile
- [call-trace](https://github.com/brendankenny/call-trace)   - 可以使用钩子来检测JS，然后生成完整（非采样）执行的`.cpuprofile`.  查看时间或通话计数.
- [cpuprofilify](https://github.com/thlorenz/cpuprofilify) - 将各种分析/采样工具的输出转换为`.cpuprofile`格式.
- [Wishbone python framework](https://wishbone.readthedocs.io/en/latest/misc/profiling.html) - 分析数据可以导出为`.cpuprofile`.

### Multimedia
- [snapline](https://github.com/pmdartus/snapline) - 将时间轴截图转换为gif.

### Timeline, Tracing & Profiling
- [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/) - 分享时间线录制的网址.

### Chrome Debugger integration with Editors
- [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/) - 适用于Visual Studio代码的Chrome调试程序.
- [Sublime Web Inspector](http://sokolovstas.github.io/SublimeWebInspector/) - 在Sublime Text编辑器中调试JavaScript.
- [WebStorm & JetBrains Chrome Extension](https://www.jetbrains.com/help/webstorm/2017.1/configuring-javascript-debugger-and-jetbrains-chrome-extension.html) -  WebStorm IDE可以调试JavaScript，查看DOM树，以及编辑HTML，CSS和JS.

---

## Chrome DevTools Protocol
- [DevTools Protocol API Docs](https://chromedevtools.github.io/devtools-protocol/) - 易于浏览协议的域，方法和事件的可浏览UI.
- [ChromeDevTools/devtools-protocol](https://github.com/chromedevtools/devtools-protocol) - 发出协议错误的跟踪器.
- [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway) - 允许您一次将客户端连接到多个浏览器.
- [DevTools Backend](https://github.com/christian-bromann/devtools-backend) - 独立实施Chrome DevTools后端以调试任意Web环境.
- [RemoteDebug](https://github.com/RemoteDebug) - 主动在当今的浏览器中规范调试协议.
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) -  Chrome的官方Selenium / WebDriver实现是在DevTools协议之上实现的.
- [Chrome Protocol Proxy](https://github.com/wendigo/chrome-protocol-proxy) - 使用devtools协议调试客户端的工具.
- [Puppeteer](https://github.com/GoogleChrome/puppeteer/) -  Node.js提供高级API，通过DevTools协议控制无头Chrome.

## Protocol Driver Libraries
-  JavaScript / Node.js： [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface) - 协议最常用的JavaScript API
-  TypeScript / Node.js： [chrome-debugging-client](https://github.com/krisselden/chrome-debugging-client) -  TypeScript async / await-friendly调试客户端
-  Java： [cdp4j](https://github.com/webfolderio/cdp4j) -  CDP的Java库
-  Java： [karate](https://intuit.github.io/karate/karate-core/) - 带有Java API的Web服务测试框架，用于使用CDP协议自动化Chrome
-  Python： [PyChromeDevTools](https://github.com/marty90/PyChromeDevTools) -  Google Chrome Dev Protocol的Python包装器
-  Python： [chromewhip](https://github.com/chuckus/chromewhip) -  Python 3 asyncio驱动程序，用于管理对Google Chrome Devtools端点的并发请求
-  Python： [pychrome](https://github.com/fate0/pychrome) -  Google Chrome开发协议的Python包
- 走： [chromedp](https://github.com/chromedp/chromedp) - 使用Go中的Chrome DevTools协议驱动浏览器的高级操作和任务
- 走： [cdp](https://github.com/mafredri/cdp) - 协议的Golang库
- 走： [gcd](https://github.com/wirepair/gcd) -  Go中的另一个客户端库
- 走： [godet](https://github.com/raff/godet) - 也不同，也是Go.
- C#/dotnet: [chrome-dev-tools](https://github.com/BaristaLabs/chrome-dev-tools)   - 协议包装器生成器，可以通过编辑手柄模板进行自定义.  包括.Net核心模板.
-  Ruby： [ChromeRemote](https://github.com/cavalle/chrome_remote/) -  Ruby中Chrome DevTools协议的客户端实现
- 科特林： [chrome-reactive-kotlin](https://github.com/wendigo/chrome-reactive-kotlin) -  Kotlin中的反应式（rxjava 2.x）低级客户端库
-  Clojure： [clj-chrome-devtools](https://github.com/tatut/clj-chrome-devtools)   - 协议的Clojure库.  CDP包装器API是自动生成的，并将在CDP协议更改时更新.
-  PHP： [chrome-devtools-protocol](https://github.com/jakubkulhan/chrome-devtools-protocol) - 协议的PHP客户端库.

## Developing with the protocol
- [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki) - 许多有用的食谱.
- [Getting Started with Headless Chrome](https://developers.google.com/web/updates/2017/04/headless-chrome)
- [crmux](https://github.com/sidorares/crmux) - 多路复用协议连接.
- [automated-chrome-profiling](https://github.com/paulirish/automated-chrome-profiling#readme) - 用于在Chrome中自动执行JavaScript分析的Node.js配方.
- [chrome-devtools-frontend](https://www.npmjs.com/package/chrome-devtools-frontend) -  Chrome中前端的镜像.
- [chrome-timeline-model](https://www.npmjs.com/package/devtools-timeline-model) - 使用前端作为lib来处理分析数据.
- [headless-devtools](https://github.com/cowchimp/headless-devtools)   - 从代码执行各种DevTools操作（例如，获取CSS Coverage，JS Heap快照）.  使用Puppeteer +前端作为lib.
- [crconsole](https://github.com/sidorares/crconsole) - 基于终端的chrome控制台和调试器.
- [sloth](https://github.com/denar90/sloth) -  Chrome扩展程序允许为选定的选项卡启用和保存CPU和网络限制.

## Browser Adapters
- [Remote Debug Firefox adapter](https://github.com/RemoteDebug/remotedebug-firefox-adapter) - 将Firefox的devtools协议转换为CDP.
- [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) - 通过CDP公开Mobile Safari和UIWebView实例.
- [Remote Debug iOS WebKit adapter](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter) - 构建在ios-webkit-debug-proxy上，并将WebKit的远程调试协议API转换为CDP.
- [IE Diagnostics Adapter](https://github.com/Microsoft/IEDiagnosticsAdapter) -  Microsoft IE 10/11到CDP的协议适配器.
- [Edge Diagnostics Adaptor](https://github.com/Microsoft/edge-diagnostics-adaptor) - 协议适配器，使工具能够使用CDP调试Edge.

## Using DevTools frontend with other platforms

### Android
- [Facebook Stetho](https://github.com/facebook/stetho) - 使用Chrome DevTools进行原生Android调试.

### ClojureScript
- [Dirac](https://github.com/binaryage/dirac) - 调试ClojsureScript.

### Lua
- [Mare](https://github.com/muzuiget/mare) - 使用Chrome DevTools调试Lua.

### iOS
- [PonyDebugger](https://github.com/square/PonyDebugger) - 使用Chrome DevTools远程网络和数据调试iOS应用程序.

### Go
- [go-debugger-devtools](https://github.com/allada/go-debugger-devtools)

### Node.js
- [Debugging Node.js with Chrome DevTools](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - 有关在Node v6.3 +中使用完整调试和分析支持的指南.
- [devtool](https://github.com/Jam3/devtool) - 使用Chrome DevTools调试和配置Node.js应用程序（使用Electron）.
- [buggerJS](https://github.com/buggerjs/bugger) - Provides Chrome DevTools bindings for node.


---

## DevTools Extensions

### Accessibility (A11y)
- [Chromelens](http://chromelens.xyz) - 了解您的网络应用程序将如何看待具有不同视觉类型的人以及用户在浏览您的页面时所走过的路径.

### Workflow
- [Clockwork](https://chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - 查看PHP应用程序分析数据.
- [Emulated Device Lab](https://chrome.google.com/webstore/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) - 尝试同时模拟多个设备.
- [RailsPanel](https://chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - 查看Ruby on Rails应用程序分析数据.
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - 检查React组件层次结构.
- [EmberJS Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - 允许您检查应用程序中的EmberJS对象.
- [VueJS Developer Tools](https://github.com/vuejs/vue-devtools) - 检查VueJS组件并操纵其数据.
- [Angular Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) - 检查Angular应用程序的范围并分析其数据.
- [Augury](https://augury.angular.io) -  Angular 2应用程序的调试和分析.
- [Marionette Inspector](https://chrome.google.com/webstore/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) - 检查Marionette应用程序的视图，事件和实时数据.
- [Backbone Debugger](https://chrome.google.com/webstore/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - 检查Backbone应用程序的视图，模型，事件和路由.
- [App Inspector for Sencha](https://chrome.google.com/webstore/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) - 检查Sencha ExtJS / Touch应用程序的组件树，数据存储，事件和布局.
- [Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - 检查Redux的动作历史记录，撤消和重放.
- [Three.js](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) - 编辑任何three.js项目.
- [Insight](https://github.com/3Dparallax/insight/) - 一个WebGL调试工具包，可以实现更高效的WebGL开发和更高效的WebGL应用程序.
- [BEM devtools](https://github.com/escaton/bem-chrome-devtools) - 检查在“i-bem”框架中表达的BEM实体.
- [Metal.js Developer Tools](https://chrome.google.com/webstore/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik) - 检查Metal组件层次结构.

### UX
- [DevTools Author](https://chrome.google.com/webstore/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) - 一系列主题，用于修改与创作Web应用程序相关的DevTools部分.
- [Zero Dark Matrix](https://chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) -  Chrome开发者工具的黑暗主题.

### Performance
- [Chrome React Perf](https://chrome.google.com/webstore/detail/react-perf/hacmcodfllhbnekmghgdlplbdnahmhmm) -  react-addons-perf软件包的操作界面.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

这个很棒的列表在Creative Commons 0下被许可到公共领域.有关更多信息，请参阅 [license](https://github.com/ChromeDevTools/awesome-chrome-devtools/blob/master/LICENSE) 文件.
