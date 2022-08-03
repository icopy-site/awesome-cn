<div class="github-widget" data-repo="ChromeDevTools/awesome-chrome-devtools"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Chrome DevTools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; Chrome DevTools 生态系统中很棒的工具和资源



---

## Learning
- [Dev Tips](https://umaar.com/dev-tips/) - 大量提示作为动画 GIF.
- [DevTools Tips](https://devtoolstips.org/) - 收集插图提示作为迷你教程.
- [Can I DevTools?](https://www.canidev.tools/) - 各种工作流程，记录在案.

---

## DevTools tooling and ecosystem

### Object formatting
- [immutable-devtools](https://github.com/andrewdavey/immutable-devtools) - Immutable-js 值的自定义格式化程序.

### Network Inspection
- [betwixt](https://github.com/kdzwinel/betwixt) - 系统级网络代理，通过网络面板提供检查.
- [Weer](https://weerdbg.com/) - HTTP协议调试器**（封闭源代码）**

### CPU profile
- [call-trace](https://github.com/brendankenny/call-trace)  - 可以使用钩子检测您的 JS，然后生成完整（非采样）执行的“.cpuprofile”. 查看时间或通话次数.
- [cpuprofilify](https://github.com/thlorenz/cpuprofilify) - 将各种分析/采样工具的输出转换为 `.cpuprofile` 格式.
- [Wishbone python framework](https://wishbone.readthedocs.io/en/latest/misc/profiling.html) - 分析数据可以导出为`.cpuprofile`.

### Multimedia
- [snapline](https://github.com/pmdartus/snapline) - 将时间线截图转换为 gif.

### Timeline, Tracing & Profiling
- [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/) - 分享您的时间线录音的 URL.

### Chrome Debugger integration with Editors
- [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/) - VS Code 中的断点调试.
- [VS Code - Elements for Microsoft Edge](https://github.com/microsoft/vscode-edge-devtools) - VS Code 中的元素面板.
- [ChromeREPL](https://github.com/acarabott/ChromeREPL) - 在 Sublime Text 中，使用 Chrome 控制台.
- [Sublime Web Inspector](http://sokolovstas.github.io/SublimeWebInspector/) - 在 Sublime Text 中进行 JavaScript 断点调试.
- [WebStorm/JetBrains Chrome Extension](https://www.jetbrains.com/help/webstorm/2017.1/configuring-javascript-debugger-and-jetbrains-chrome-extension.html) - WebStorm IDE 可以调试 JavaScript，查看 DOM 树，并实时编辑 HTML、CSS 和 JS.

---

## Chrome DevTools Protocol
- [ChromeDevTools/devtools-protocol](https://github.com/chromedevtools/devtools-protocol)  - **协议 JSON 的规范位置**. 协议错误的问题跟踪器.  TypeScript 类型.
- [DevTools Protocol API Docs](https://chromedevtools.github.io/devtools-protocol/) - 易于浏览的 UI，用于探索协议的域、方法和事件.

### Developing with the protocol
- [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki) - 许多有用的食谱.
- [Chrome Protocol Proxy](https://github.com/wendigo/chrome-protocol-proxy) - 使用 devtools 协议调试客户端的工具.

### The big two automation libraries
- [Puppeteer](https://github.com/GoogleChrome/puppeteer/)  - Node.js 提供高级 API 以通过 DevTools 协议控制无头 Chrome. 也可以看看 [awesome-puppeteer](https://github.com/transitive-bullshit/awesome-puppeteer).
- [Playwright](https://github.com/microsoft/playwright)  - 使用单个 API 自动化 Chromium、Firefox 和 WebKit 的库. 适用于 Node.js、Python、.Net、Java. 也可以看看 [awesome-playwright](https://github.com/mxschmitt/awesome-playwright).

### Libraries for driving the protocol (or a layer above)

- JavaScript/Node.js： [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface)
- 打字稿/Node.js： [chrome-debugging-client](https://github.com/TracerBench/chrome-debugging-client)
- 打字稿/Node.js： [noice-json-rpc](https://www.npmjs.com/package/noice-json-rpc) - 将 CDP 公开为其 API 的基于代理的实现.
- 打字稿/Node.js： [Taiko](https://github.com/getgauge/taiko/)
- 锈： [Rust Headless Chrome](https://github.com/atroche/rust-headless-chrome/)
- 爪哇： [chrome-devtools-java-client](https://github.com/kklisura/chrome-devtools-java-client)
- 爪哇： [jvppeteer](https://github.com/fanyong920/jvppeteer)  - Java 的无头 Chrome 
- Python： [PyCDP](https://github.com/hyperiongray/python-chrome-devtools-protocol)  - 纯 Python，无 IO 包装器. 另见 [Trio CDP driver](https://github.com/hyperiongray/trio-chrome-devtools-protocol)
- Python： [chromewhip](https://github.com/chuckus/chromewhip) - 替代“splash”服务
- Python： [pyppeteer](https://github.com/pyppeteer/pyppeteer) - 木偶港口
- Python： [ChromeController](https://github.com/fake-name/ChromeController) - 高级浏览器管理
- 去： [chromedp](https://github.com/chromedp/chromedp) - 用于驱动浏览器的高级操作和任务
- 去： [cdp](https://github.com/mafredri/cdp)
- 去： [gcd](https://github.com/wirepair/gcd)
- 去： [godet](https://github.com/raff/godet)
- 去： [Rod](https://github.com/go-rod/rod)
- C#/.NET: [Puppeteer Sharp](https://github.com/kblok/puppeteer-sharp) - 木偶港口
- C#/dotnet: [chrome-dev-tools](https://github.com/BaristaLabs/chrome-dev-tools)  - 可以通过编辑车把模板来定制的协议包装器生成器. 包括 .Net Core 模板.
- 红宝石： [Ferrum](https://github.com/route/ferrum) - 在 Ruby 中控制 Chrome 的高级 API
- 红宝石： [Cuprite](https://github.com/machinio/cuprite) - 水豚司机
- 科特林： [chrome-reactive-kotlin](https://github.com/wendigo/chrome-reactive-kotlin) - 反应式 (rxjava 2.x)，Kotlin 中的低级客户端库
- 科特林： [chrome-devtools-kotlin](https://github.com/joffrey-bion/chrome-devtools-kotlin) - 基于协程的客户端库，提供低级 CDP 原语和高级扩展.
- Clojure： [clj-chrome-devtools](https://github.com/tatut/clj-chrome-devtools) - CDP 包装器 API 是自动生成的，并且会在 CDP 协议更改时更新.
- Clojure： [cuic](https://github.com/milankinen/cuic) - 通过 DevTools 协议为 UI 测试自动化提供高级 API.
- PHP： [chrome-devtools-protocol](https://github.com/jakubkulhan/chrome-devtools-protocol) - 该协议的 PHP 客户端库.
- PHP： [PuPHPeteer](https://github.com/rialto-php/puphpeteer) - 到节点 puppeteer 的 php 桥


### Browser Adapters
- [Inspect](https://inspect.dev/)  - 轻松使用针对 iOS 和 Android 的开发工具. 浏览器和 Web 视图.  **（封闭源代码）**


## Using DevTools frontend with other platforms

#### Android
- [Facebook Stetho](https://github.com/facebook/stetho) - 使用 Chrome DevTools 进行原生 Android 调试.
- [j2v8-debugger](https://github.com/AlexTrotsenko/j2v8-debugger) - 调试运行的 JavaScript [J2V8](https://github.com/eclipsesource/J2V8) 使用 Chrome 开发工具.

#### ClojureScript
- [Dirac](https://github.com/binaryage/dirac) - ClojsureScript 的调试.

#### iOS
- [PonyDebugger](https://github.com/square/PonyDebugger) - 使用 Chrome DevTools 远程网络和数据调试 iOS 应用程序.

#### Node.js
- [ndb](https://github.com/GoogleChromeLabs/ndb) - 使用 DevTools 前端改进了 Node.js 调试体验.
- [Debugging Node.js with Chrome DevTools](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - 在 Node v6.3+ 中使用完整的调试和分析支持的指南.
- [thetool](https://github.com/sfninja/thetool) - 使用 Node.js 进行 CPU、内存、覆盖率、类型分析.
- [chrome-devtools-frontend](https://www.npmjs.com/package/chrome-devtools-frontend) - Chrome 中附带的前端镜像.

#### Ruby
- [ruby/debug](https://github.com/ruby/debug) - Ruby 的调试功能.

---

## DevTools Extensions

### Accessibility (A11y)
- [Chromelens](http://chromelens.xyz) - 了解您的 Web 应用程序对于具有不同视力类型的人的外观以及用户在浏览您的页面时的路径.

### Workflow
- [Clockwork](https://chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - 查看 PHP 应用程序分析数据.
- [Emulated Device Lab](https://chrome.google.com/webstore/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) - 试验同时模拟多个设备.
- [RailsPanel](https://chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - 查看 Ruby on Rails 应用程序分析数据.
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
- [EmberJS Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - 允许您检查应用程序中的 EmberJS 对象.
- [VueJS Developer Tools](https://github.com/vuejs/vue-devtools) - 检查 VueJS 组件并操作它们的数据.
- [Angular Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) - 检查 Angular 应用程序的范围并分析其数据.
- [Augury](https://augury.angular.io) - Angular 2 应用程序的调试和分析.
- [Marionette Inspector](https://chrome.google.com/webstore/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) - 检查 Marionette 应用程序的视图、事件和实时数据.
- [Backbone Debugger](https://chrome.google.com/webstore/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - 检查 Backbone 应用程序的视图、模型、事件和路由.
- [App Inspector for Sencha](https://chrome.google.com/webstore/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) - 检查 Sencha ExtJS/Touch 应用程序的组件树、数据存储、事件和布局.
- [Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - 使用操作历史记录、撤消和重放检查 Redux.
- [Three.js](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) - 编辑任何 three.js 项目.
- [Insight](https://github.com/3Dparallax/insight/) - 一个 WebGL 调试工具包，可实现更高效的 WebGL 开发和更高效的 WebGL 应用程序.
- [BEM devtools](https://github.com/escaton/bem-chrome-devtools) - 检查在“i-bem”框架中表达的 BEM 实体.
- [Metal.js Developer Tools](https://chrome.google.com/webstore/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik) - 检查金属组件层次结构.
- [Web Component DevTools](https://chrome.google.com/webstore/detail/web-component-devtools/gdniinfdlmmmjpnhgnkmfpffipenjljo) - 检查、修改和观察页面上的 Web 组件.

### Themes
- [DevTools Author](https://chrome.google.com/webstore/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) - 用于修改与创作 Web 应用程序相关的 DevTools 部分的主题选择.
- [Zero Dark Matrix](https://chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) - Chrome 开发者工具的深色主题.
- [Material UI Theme](https://chrome.google.com/webstore/detail/material-devtools-theme-c/jmefikbdhgocdjeejjnnepgnfkkbpgjo) - 提供各种材料设计灵感的主题.

### Performance
- [sloth](https://github.com/denar90/sloth) - Chrome 扩展允许为选定的选项卡启用和保存 CPU 和网络限制.
- [TracerBench](https://github.com/TracerBench/tracerbench) - TracerBench 是用于 Web 应用程序的受控性能基准测试工具，可提供关于性能增量的清晰、可操作和可用的见解.

### Automation
- [Puppeteer IDE](https://github.com/gajananpp/puppeteer-ide-extension) - 浏览器开发工具中的独立 Puppeteer 游​​乐场.

## Alumni
旧项目，可能不再维护......但仍然很酷.

- [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway) - 允许您一次将客户端连接到多个浏览器.  
   - 多用户开发工具： [DevTools Remote](https://github.com/auchenberg/devtools-remote) - 远程调试别人的浏览器.
- [DevTools Backend](https://github.com/christian-bromann/devtools-backend) - Chrome DevTools 后端的独立实现，用于调试任意 Web 环境.
- Python CDP 驱动程序： [pychrome](https://github.com/fate0/pychrome) - 低级 CDP 传输处理程序
- [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) - 通过 CDP 公开 Mobile Safari 和 UIWebView 实例.
  - [Remote Debug iOS WebKit adapter](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter) - 基于 ios-webkit-debug-proxy 构建并将 WebKit 的远程调试协议 API 转换为 CDP.
- [IE Diagnostics Adapter](https://github.com/Microsoft/IEDiagnosticsAdapter) - Microsoft IE 11 到 CDP 的协议适配器.
- [go-debugger-devtools](https://github.com/allada/go-debugger-devtools)
