<div class="github-widget" data-repo="ChromeDevTools/awesome-chrome-devtools"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Chrome DevTools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; Chrome DevTools生态系统中的强大工具和资源



---

## Learning
- [Dev Tips](https://umaar.com/dev-tips/) -大量的提示作为GIF动画.
- [DevTools Snippets](https://github.com/bahmutov/code-snippets) -片段摘要.

### Multiuser DevTools
- [DevTools Remote](https://github.com/auchenberg/devtools-remote) -远程调试其他人的浏览器.

---

## DevTools tooling and ecosystem

### Object formatting
- [immutable-devtools](https://github.com/andrewdavey/immutable-devtools) -Immutable-js值的自定义格式化程序.

### Network Inspection
- [betwixt](https://github.com/kdzwinel/betwixt) -系统级网络代理，通过“网络”面板提供检查.
- [Weer](https://weerdbg.com/) -HTTP协议调试器**（关闭源）**

### CPU profile
- [call-trace](https://github.com/brendankenny/call-trace)  -可以使用钩子对JS进行检测，然后生成完整（非采样）执行的`.cpuprofile`. 查看时间或通话计数.
- [cpuprofilify](https://github.com/thlorenz/cpuprofilify) -将各种性能分析/采样工具的输出转换为`.cpuprofile`格式.
- [Wishbone python framework](https://wishbone.readthedocs.io/en/latest/misc/profiling.html) -分析数据可以导出为`.cpuprofile`.

### Multimedia
- [snapline](https://github.com/pmdartus/snapline) -将时间轴屏幕截图转换为gif.

### Timeline, Tracing & Profiling
- [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/) -共享时间线录音的URL.

### Chrome Debugger integration with Editors
- [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/) -VS Code中的断点调试.
- [VS Code - Elements for Microsoft Edge](https://github.com/microsoft/vscode-edge-devtools) -VS Code中的Elements面板.
- [ChromeREPL](https://github.com/acarabott/ChromeREPL) -在Sublime Text中，使用Chrome控制台.
- [Sublime Web Inspector](http://sokolovstas.github.io/SublimeWebInspector/) -Sublime Text中的JavaScript Breakpoint调试功能.
- [WebStorm/JetBrains Chrome Extension](https://www.jetbrains.com/help/webstorm/2017.1/configuring-javascript-debugger-and-jetbrains-chrome-extension.html) -WebStorm IDE可以调试JavaScript，查看DOM树以及实时编辑HTML，CSS和JS.

---

## Chrome DevTools Protocol
- [ChromeDevTools/devtools-protocol](https://github.com/chromedevtools/devtools-protocol)  -**协议JSON的规范位置**. 协议错误的问题跟踪器.  TypeScript类型.
- [DevTools Protocol API Docs](https://chromedevtools.github.io/devtools-protocol/) -易于浏览的UI，用于浏览协议的域，方法和事件.

### Developing with the protocol
- [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki) -许多有用的食谱.
- [Chrome Protocol Proxy](https://github.com/wendigo/chrome-protocol-proxy) -使用devtools协议调试客户端的工具.
- [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway) -允许您一次将客户端连接到多个浏览器.
- [DevTools Backend](https://github.com/christian-bromann/devtools-backend) -Chrome DevTools后端的独立实现，可调试任意网络环境.
- [RemoteDebug](https://github.com/RemoteDebug) -主动在当今的浏览器中标准化调试协议.
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) -Chrome的官方Selenium / WebDriver实现是在DevTools协议之上实现的.
- [BrowserGap Community Edition](https://github.com/dosycorp/browsergap.ce)  -远程浏览器产品，开源. 大量使用原始的，树梢的Chrome DevTools协议.

### Automation
- [Puppeteer](https://github.com/GoogleChrome/puppeteer/) -Node.js提供了高级API，以通过DevTools协议控制无头Chrome.
  -Python端口： [pyppeteer](https://github.com/pyppeteer/pyppeteer)
  -休息端口： [Rust Headless Chrome](https://github.com/atroche/rust-headless-chrome/)
  -.NET端口： [Puppeteer Sharp](https://github.com/kblok/puppeteer-sharp)
  -Ruby端口： [Ferrum](https://github.com/route/ferrum)
  - [headless-devtools](https://github.com/cowchimp/headless-devtools) -Puppeteer插件可获取CSS Coverage或JS Heap快照.
  - [PuPHPeteer](https://github.com/rialto-php/puphpeteer) -使用PHP控制Puppeteer的PHP桥.
- [Playwright](https://github.com/microsoft/playwright) -Node.js库，可通过单个API自动化Chromium，Firefox和WebKit.
- [Taiko](https://github.com/getgauge/taiko/) -一个Node.js模块，可使用DevTools协议自动执行Chrome / Chromium.
-还有下面的所有“协议驱动程序库”

### Protocol Driver Libraries
-JavaScript / Node.js： [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface) -该协议最常用的JavaScript API
-TypeScript / Node.js： [chrome-debugging-client](https://github.com/krisselden/chrome-debugging-client)
-Java： [chrome-devtools-java-client](https://github.com/kklisura/chrome-devtools-java-client)
-Java： [karate](https://intuit.github.io/karate/karate-core/) -带有Java API的Web服务测试框架，可自动执行Chrome浏览器
-Java： [jvppeteer](https://github.com/fanyong920/jvppeteer)  -适用于Java的无头Chrome 
- Python： [PyCDP](https://github.com/hyperiongray/python-chrome-devtools-protocol)  -纯Python，无IO包装器. 另请参阅 [Trio CDP driver](https://github.com/hyperiongray/trio-chrome-devtools-protocol)
- Python： [chromewhip](https://github.com/chuckus/chromewhip) -直接替换`splash`服务
- Python： [pychrome](https://github.com/fate0/pychrome) -低级CDP传输处理程序
- Python： [ChromeController](https://github.com/fake-name/ChromeController) -高级浏览器mgmt
- 去： [chromedp](https://github.com/chromedp/chromedp) -驱动浏览器的高级操作和任务
- 去： [cdp](https://github.com/mafredri/cdp)
- 去： [gcd](https://github.com/wirepair/gcd)
- 去： [godet](https://github.com/raff/godet)
- 去： [Rod](https://github.com/go-rod/rod)
- C#/dotnet: [chrome-dev-tools](https://github.com/BaristaLabs/chrome-dev-tools)  -协议包装器生成器，可以通过编辑车把模板进行自定义. 包括.Net Core模板.
-红宝石： [Cuprite](https://github.com/machinio/cuprite) -水豚司机
-红宝石： [ChromeRemote](https://github.com/cavalle/chrome_remote/)
-Kotlin： [chrome-reactive-kotlin](https://github.com/wendigo/chrome-reactive-kotlin) -Kotlin中的反应式（rxjava 2.x）低级客户端库
-Kotlin： [chrome-devtools-kotlin](https://github.com/joffrey-bion/chrome-devtools-kotlin) -基于协程的客户端库，提供低级CDP原语和高级扩展.
-Clojure： [clj-chrome-devtools](https://github.com/tatut/clj-chrome-devtools) -CDP包装器API是自动生成的，并且在CDP协议更改时将更新.
-PHP： [chrome-devtools-protocol](https://github.com/jakubkulhan/chrome-devtools-protocol) -该协议的PHP客户端库.

### Browser Adapters
- [Remote Debug Firefox adapter](https://github.com/RemoteDebug/remotedebug-firefox-adapter) -将Firefox的devtools协议翻译为CDP.
- [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) -通过CDP公开Mobile Safari和UIWebView实例.
  - [Remote Debug iOS WebKit adapter](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter) -基于ios-webkit-debug-proxy构建，并将WebKit的远程调试协议API转换为CDP.
- [IE Diagnostics Adapter](https://github.com/Microsoft/IEDiagnosticsAdapter) -用于Microsoft IE 11到CDP的协议适配器.


## Using DevTools frontend with other platforms

#### Android
- [Facebook Stetho](https://github.com/facebook/stetho) -使用Chrome DevTools进行本机Android调试.
- [j2v8-debugger](https://github.com/AlexTrotsenko/j2v8-debugger) -调试运行在其中的JavaScript [J2V8](https://github.com/eclipsesource/J2V8) 使用Chrome DevTools.

#### ClojureScript
- [Dirac](https://github.com/binaryage/dirac) -ClojsureScript的调试.

#### Lua
- [Mare](https://github.com/muzuiget/mare) -使用Chrome DevTools进行Lua调试.

#### iOS
- [PonyDebugger](https://github.com/square/PonyDebugger) -使用Chrome DevTools进行远程网络和数据调试iOS应用.

#### Go
- [go-debugger-devtools](https://github.com/allada/go-debugger-devtools)

#### Node.js
- [ndb](https://github.com/GoogleChromeLabs/ndb) -使用DevTools前端改进了Node.js调试体验.
- [Debugging Node.js with Chrome DevTools](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) -关于在Node v6.3 +中使用完整调试和性能分析支持的指南.
- [thetool](https://github.com/sfninja/thetool) -CPU，内存，覆盖率，使用Node进行类型分析.
- [chrome-devtools-frontend](https://www.npmjs.com/package/chrome-devtools-frontend) -Chrome随附的前端镜像.

---

## DevTools Extensions

### Accessibility (A11y)
- [Chromelens](http://chromelens.xyz) -查看具有不同类型视力的人的Web应用程序外观，以及用户在浏览页面时浏览的路径.

### Workflow
- [Clockwork](https://chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) -查看PHP应用程序分析数据.
- [Emulated Device Lab](https://chrome.google.com/webstore/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) -尝试同时仿真多个设备.
- [RailsPanel](https://chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) -查看Ruby on Rails应用程序性能分析数据.
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) -检查React组件层次结构.
- [EmberJS Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) -允许您检查应用程序中的EmberJS对象.
- [VueJS Developer Tools](https://github.com/vuejs/vue-devtools) -检查VueJS组件并处理其数据.
- [Angular Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) -检查Angular应用程序的范围并分析其数据.
- [Augury](https://augury.angular.io) - Debugging and Profiling for Angular 2 applications.
- [Marionette Inspector](https://chrome.google.com/webstore/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) -检查木偶应用程序的视图，事件和实时数据.
- [Backbone Debugger](https://chrome.google.com/webstore/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) -检查Backbone应用程序的视图，模型，事件和路由.
- [App Inspector for Sencha](https://chrome.google.com/webstore/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) -检查Sencha ExtJS / Touch应用程序的组件树，数据存储，事件和布局.
- [Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) -检查Redux的动作历史记录，撤消和重播.
- [Three.js](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) -编辑任何three.js项目.
- [Insight](https://github.com/3Dparallax/insight/) -WebGL调试工具包，可实现更高效的WebGL开发和更高效的WebGL应用程序.
- [BEM devtools](https://github.com/escaton/bem-chrome-devtools) -检查以“ i-bem”框架表示的BEM实体.
- [Metal.js Developer Tools](https://chrome.google.com/webstore/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik) -检查金属组件层次结构.

### Themes
- [DevTools Author](https://chrome.google.com/webstore/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) -选择了一些主题来修改与编写Web应用程序有关的DevTools部分.
- [Zero Dark Matrix](https://chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) -Chrome开发者工具的深色主题.
- [Material UI Theme](https://chrome.google.com/webstore/detail/material-devtools-theme-c/jmefikbdhgocdjeejjnnepgnfkkbpgjo) -提供各种受材料设计启发的主题.

### Performance
- [sloth](https://github.com/denar90/sloth) -Chrome扩展程序可以启用和保存选定标签的CPU和网络限制.
- [TracerBench](https://github.com/TracerBench/tracerbench) -TracerBench是用于Web应用程序的受控性能基准测试工具，可提供对性能增量的清晰，可操作和可用的见解.
