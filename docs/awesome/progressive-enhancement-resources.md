<div class="github-widget" data-repo="jbmoelker/progressive-enhancement-resources"></div>
## Progressive Enhancement Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

关于渐进增强的综合资源集合. 从概念和策略到特征检测和测试方法. 完成（代码）示例列表.





## The Concept

[Progressive Enhancement](https://en.wikipedia.org/wiki/Progressive_enhancement) 是指在验证目标环境（如浏览器）是否具备能力后，逐步提升用户体验. 从内容开始，确保您保持功能性和可访问性.

* [The Role of Enhancement in Web Design](https://www.nngroup.com/articles/enhancement/) - 从增强的概念到丰富用户界面的标准和规则.
* [Understanding Progressive Enhancement](http://alistapart.com/article/understandingprogressiveenhancement) - 以智能方式逐层应用技术，打造令人惊叹的体验.
* [Designing with Progressive Enhancement](https://www.filamentgroup.com/dwpe/) - *关于渐进增强的书*（400 多页）.
* [Detecting (HTML5) features](http://diveinto.html5doctor.com/detect.html) - 通过示例和演示介绍不同的特征检测技术. 
* [Progressive Web Apps](https://infrequently.org/2015/06/progressive-apps-escaping-tabs-without-losing-our-soul/) - 将网站增强为类似原生的应用程序（渐进式，而非混合式）.


## Strategies

您可以通过不同的方式应用渐进增强：

* [Make the page usable with only HTML](https://www.gov.uk/service-manual/technology/using-progressive-enhancement#make-the-page-usable-with-only-html) - 这为每个设备和浏览器设置了基准.
* [Test Driven Progressive Enhancement](http://alistapart.com/article/testdriven) - 测试能力后增强核心功能体验.
* [Cut the mustard](http://responsivenews.co.uk/post/18948466399/cutting-the-mustard) - 设置增强收集的阈值.
* [分级组件，而不是浏览器](https://www.filamentgroup.com/lab/grade-the-components.html
) - 组件级功能测试和增强.
* [Feature vs Browser vs Form factor detection](http://www.html5rocks.com/en/tutorials/detection/) - 作为调整您的应用程序以适应其环境的不同策略.
* [Server-side device detection](https://www.smashingmagazine.com/2014/07/server-side-device-detection-with-javascript/) - 使用用户代理和其他 HTTP 标头信息结合设备数据库来有条件地提供文件.
* [Writing polyfills](https://addyosmani.com/blog/writing-polyfills/) - 如果您的基线对于某些浏览器仍然太高，请考虑 [polyfills](https://remysharp.com/2010/10/08/what-is-a-polyfill) （又名 [Regressive Enhancement](https://twitter.com/SlexAxton/status/25600963629)).
* [Application Shell Architecture](https://medium.com/google-developers/instant-loading-web-apps-with-an-application-shell-architecture-7c0c2f10c73) - 即时加载网络应用程序的设置.


## Feature Detection

在尝试增强体验之前，您需要确保环境能够增强体验. 您通过执行特征检测来测试它：

* [CSS feature queries](https://www.sitepoint.com/an-introduction-to-css-supports-rule-feature-queries/) ([`CSS.supports()`](https://developer.mozilla.org/en/docs/Web/API/CSS/supports) & [`@supports()`](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports)) - 使用 JS 方法或 CSS 声明原生测试是否支持特定的 CSS 功能.
* [Feature Detect ES6](https://www.npmjs.com/package/feature-detect-es6) - 检测哪些 ES2015 功能可用.
* [SVG requiredFeatures](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/requiredFeatures) - 仅当 SVG 元素的“[requiredFeatures]”计算结果为真时才渲染 SVG 元素.
* [Modernizr](https://modernizr.com/) - 广泛的功能检测套件（支持自定义构建）.
* [Feature.js](http://featurejs.com/) - 轻量级特征检测套件.
* [Conditioner.js](http://conditionerjs.com/) - 根据 HTML 属性中的指令有条件地加载 JS 模块.
* [EnhanceJS](https://www.filamentgroup.com/lab/introducing-enhancejs-smarter-safer-apply-progressive-enhancement.html) - 允许您在一组预定义的功能测试后异步加载 CSS 和 JS.


## Support Tables

不同的环境（平台、浏览器、版本）具有不同的能力. 支持表会告诉您每个环境具有哪些功能. 了解支持级别可以帮助您权衡改进与其实施的努力和影响.

* [The Web Platform](https://platform.html5.org/) - 带有文档和测试套件链接的浏览器技术概述.
* [Can I use ...?](http://caniuse.com/) - 比较桌面和移动浏览器的功能实现和限制.
* [I want to use ...](http://www.iwanttouse.com/) - 弄清楚浏览器对功能组合的支持.
* [HTML5 Test](http://html5test.com/) - 测试和比较跨浏览器的 HTML5 功能支持.
* [CSS3 Test](http://css3test.com/) - 对当前浏览器的 CSS3 功能支持进行细粒度测试.
* [Accessibility Support](https://a11ysupport.io/) - 比较跨浏览器和辅助技术对 HTML 元素和 ARIA 角色的可访问性支持.
* [State of Web Type](https://github.com/bramstein/stateofwebtype) - 支持网络上的类型和排版功能表.
* [Font Family Reunion](http://fontfamily.io/) - 默认本地（系统）字体的兼容性表.
* [HTML5 Accessibility](http://html5accessibility.com/) - 比较主流浏览器对 HTML5 标签、输入类型和属性的功能支持. 
* [WAI-ARIA Screen reader compatibility](https://www.powermapper.com/tests/screen-readers/aria/) - ARIA 角色和属性支持不同的屏幕阅读器和浏览器组合.
* [What web can do today](https://whatwebcando.today/) - 列出并检查现代 Web API，例如对设备系统、传感器和执行器的访问.
* [HTML5 Worker test](https://nolanlawson.github.io/html5workertest/) - 比较跨浏览器的 Web Workers 和 Service Workers 支持哪些 API.
* [HTML5 Please](http://html5please.com/) - 通过建议和 polyfill 链接探索功能.
* [API Catalog](https://developer.microsoft.com/en-us/microsoft-edge/platform/catalog/) - 让您比较主要桌面浏览器中 API 规范的实现.
* [Kangax's ECMAScript compatibility table](http://kangax.github.io/compat-table/) - 跨浏览器和其他运行时的 JavaScript 功能支持概述.
* [Node compatibility table](http://node.green/) - 跨 NodeJS 版本的 JavaScript 功能支持概述.
* [Is service worker ready?](https://jakearchibald.github.io/isserviceworkerready/) - 对 Progressive Web Apps 背后核心技术所涉及的所有功能的支持概述.
* [Is PWA ready?](https://ispwaready.toxicjohann.com/) - 对流行的全球浏览器和许多中国浏览器的 Progressive Web Apps 背后的核心和相关技术的支持概述.
* [Is WebRTC ready yet?](http://iswebrtcreadyyet.com/) - 支持实时通信背后的不同浏览器功能的概述.
* [Is WebVR ready?](https://iswebvrready.org/) - 概述支持 WebVR 背后的不同浏览器功能，包括显示、游戏手柄、音频和语音 API.
* [Is Houdini ready yet?](https://ishoudinireadyyet.com/) - 跨浏览器对 Houdini（公开部分 CSS 渲染引擎的低级 API）的支持概述.
* [Chrome Platform Status](https://www.chromestatus.com/features)
* [Edge Platform Status](https://developer.microsoft.com/en-us/microsoft-edge/platform/status/)
* [Firefox Platform Status](https://platform-status.mozilla.org/)
* [Webkit Platform Status](https://webkit.org/status/) （苹果浏览器）
* [MDN Compatibility tables](https://developer.mozilla.org/en-US/docs/MDN/Contribute/Structures/Compatibility_tables) - MDN 的网络技术文档在每篇文章的末尾都有一个浏览器兼容性表.
* [MDN Browser Compat Data](https://github.com/mdn/browser-compat-data) - 为 MDN 兼容性表提供支持的 npm 模块.
* [Device Bugs & Quirks](https://github.com/scottjehl/Device-Bugs) - 移动设备中奇怪的 HTML、CSS 和 JS 怪癖的众包集合，您在其他支持表中找不到.
* [Can I Email?](https://www.caniemail.com/)  - 支持电子邮件中的 HTML 和 CSS 表格. 灵感来自 [Can I use](http://caniuse.com/).
* [Project Fugu API tracker](https://fugu-tracker.web.app/) - 浏览器支持 Web API 填补“应用程序空白”的状态概述.
* [iOS PWA Compatibility](https://firt.dev/notes/pwa-ios/) - PWA 功能的支持表，包括服务工作者、清单、后台同步和推送通知（非官方，由 Maximiliano Firtman 维护）.


## Testing Methods

通过渐进式增强，您可以支持不同环境中的不同体验. 这些是测试所有这些变化的一些方法：

* [Open Device Lab](https://opendevicelab.com/) - 让您*在实际设备上手动测试*（免费）.
* [Testing in Opera Mini](https://dev.opera.com/articles/making-sites-work-opera-mini/#testing-in-opera-mini)  - 下载应用程序，在桌面上模拟，设置以测试本地网站.  （Opera Mini 占全球浏览器使用量的 5% 以上）
* [cURL](https://curl.haxx.se/docs/manual.html) - 网页查看页面的预渲染源代码.
* [Browserling](https://www.browserling.com/) - 允许您在 Windows 和 Android 平台上的不同版本浏览器中手动测试网页.
* [Run Internet Explorer using Virtual Machines](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/mac/) - 在其他平台上测试 IE 浏览器.
* [Device emulators and simulators](https://developers.google.com/web/tools/chrome-devtools/iterate/device-mode/testing-other-browsers?hl=en#device-emulators-and-simulators)
* [Configure *Desired Capabilities* in Selenium](https://github.com/SeleniumHQ/selenium/wiki/DesiredCapabilities) - 在不同场景下运行自动浏览器测试.
* Continuously run automated tests in different browsers using [BrowserStack](https://www.browserstack.com/), [Saucelabs](https://saucelabs.com/) 或其他替代品.
* [Lighthouse](https://github.com/GoogleChrome/lighthouse) - 审计和衡量渐进式 Web 应用程序的性能（通过 cli 或 [Chrome extension](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk)).
* [Progressive Enhancement checklist (1st edition, HTML)](http://adaptivewebdesign.info/1st-edition/read/chapter-6.html#the-progressive-enhancement-checklist), [Checklist of 2nd edition (PDF)](http://adaptivewebdesign.info/2nd-edition/checklist.pdf)  - 用于检查您是否已应用渐进增强最佳实践的可操作列表. 部分 [Adaptive Web Design book](http://adaptivewebdesign.info/).
* [CSS Feature Toggles](https://chrome.google.com/webstore/detail/css-feature-toggles/aeinmfddnniiloadoappmdnffcbffnjg) - Chrome DevTools 扩展以切换对选定 CSS 功能的支持，以测试渐进式增强回退.


## Examples

### Custom Form Elements

* [Fancy radio buttons](https://www.sitepoint.com/replacing-radio-buttons-without-replacing-radio-buttons/) - 基于 HTML 单选按钮，使用 CSS 伪类和元素增强了视觉效果.
* [Checkboxes & radio buttons](https://www.filamentgroup.com/dwpe/checkbox-radiobutton/)  - 具有自定义焦点、悬停和选中状态. 异步增强.
* [Toggle switch](https://ghinda.net/css-toggle-switch/) - 复选框或收音机，视觉增强到仅使用 CSS 的滑动切换开关.
* [5-star rating](http://lea.verou.me/2011/08/accessible-star-rating-widget-with-pure-css/) - 基于 HTML 单选按钮，使用 CSS 伪类和元素增强了视觉效果.
* [jQuery slider](https://github.com/filamentgroup/jQuery-Slider) - 基于标准 HTML 选择的可访问自定义滑块小部件.
* [jQuery custom file input](https://www.filamentgroup.com/lab/jquery-custom-file-input-book-designing-with-progressive-enhancement.html) - 文章和图书馆.
* [React isomorphic form](https://github.com/ghengeveld/react-isomorphic-form/)  - 一组可以在服务器端预渲染和处理的 React 表单组件. 它们是增强的客户端，不会丢失状态.

### Data Visualisations

* [Timeline](https://css-tricks.com/progressive-enhancement-data-visualizations/) - 从定义列表到 SVG 插图（带演示的文章）.
* [Charts](https://www.filamentgroup.com/lab/update-to-jquery-visualize-accessible-charts-with-html5-from-designing-with.html) - 使用 HTML5 画布（文章和库）从数据表到主题图表.

### Images

* [Responsive Carousel](http://filamentgroup.github.io/responsive-carousel/test/functional/fade-auto.html) - 图像列表增强为具有各种行为选项的响应轮播.
* [Lazy Progressive Enhancement](https://github.com/tvler/lazy-progressive-enhancement)  - 在`内延迟加载图像<noscript> `标签.  （注意：仅限 Evergreen 浏览器）

### Menus

* [Progressive hamburger menu](http://heydonworks.com/practical_aria_examples/#hamburger) - 增强到非画布菜单的页脚中的链接列表.

### Page Navigation

使用 ajax 和 `history.pushState` 在静态页面之间异步获取和转换：

* [Barba.js](http://barbajs.org/) - 添加带有事件挂钩、缓存和预取支持的页面转换.
* [SmoothState.js](https://github.com/miguel-perez/smoothState.js)  - 添加带有事件挂钩、缓存和预取支持的页面转换.  （需要 jQuery）.
* [MoOx/pjax](https://github.com/MoOx/pjax) - 类似于 jquery-pjax，但没有 jQuery 依赖.
* [Turbolinks](https://github.com/turbolinks/turbolinks)  - 添加带有事件挂钩和缓存支持的页面转换. 具有绑定到 iOS 和 Android 上的本机导航控件的适配器.


## Related Articles

* [Make the web work for everyone](https://hacks.mozilla.org/2016/07/make-the-web-work-for-everyone/) - 恳请开发人员考虑浏览器差异并构建弹性网络.
* [How many people are missing out on JavaScript enhancement?](https://gds.blog.gov.uk/2013/10/21/how-many-people-are-missing-out-on-javascript-enhancement/) - 研究为什么在 1.1% 的页面访问中没有加载 JavaScript. 

---

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

[Jasper Moelker](https://twitter.com/jbmoelker) 在法律允许的范围内，根据版权法在全球范围内放弃对本作品的所有权利，包括所有相关权利和邻接权利.

您可以复制、修改、分发和执行作品，甚至可以用于商业目的，所有这些都无需征得许可.
