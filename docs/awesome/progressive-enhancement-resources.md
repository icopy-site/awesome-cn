## Progressive Enhancement Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 关于渐进增强的全面资源集合.  从概念和策略到特征检测和测试方法.  完成（代码）示例列表.


## Contents

* [The Concept](#the-concept)
* [Strategies](#strategies)
* [Feature Detection](#feature-detection)
* [Support Tables](#support-tables)
* [Testing Methods](#testing-methods)
* [Examples](#examples)
* [Related Articles](#related-articles)


## The Concept

[Progressive Enhancement](https://en.wikipedia.org/wiki/Progressive_enhancement)  意味着在验证目标环境（例如浏览器）能够实现之后逐渐改善用户体验.  从内容开始，确保您保持功能和可访问性.

* [Progressive Enhancement: It's about the content](http://cognition.happycog.com/article/progressive-enhancement-its-about-the-content)   - 共享内容是网络的核心.  渐进增强功能可确保访问内容.
* [The Role of Enhancement in Web Design](https://www.nngroup.com/articles/enhancement/) - 从增强的概念到丰富用户界面的标准和规则.
* [Understanding Progressive Enhancement](http://alistapart.com/article/understandingprogressiveenhancement) - 以层层叠叠的智能方式应用技术，创造出令人惊叹的体验.
* [Designing with Progressive Enhancement](https://www.filamentgroup.com/dwpe/) -  *关于渐进增强的书*（400多页）.
* [Adaptive Web Design](http://adaptivewebdesign.info/2nd-edition/) - 预订从内容到设计和互动的渐进增强.
* [Detecting (HTML5) features](http://diveinto.html5doctor.com/detect.html) - 通过示例和演示介绍不同的特征检测技术. 
* [Progressive Web Apps](https://infrequently.org/2015/06/progressive-apps-escaping-tabs-without-losing-our-soul/) - 将网站增强为类似本机的应用程序（渐进式，非混合型）.


## Strategies

您可以通过不同方式应用渐进增强：

* [The Content-out Approach](https://articles.uie.com/progressive_enhancement/) - 提供广泛的内容访问，无需技术限制.
* [Make the page usable with only HTML](https://www.gov.uk/service-manual/technology/using-progressive-enhancement#make-the-page-usable-with-only-html) - 这为每个设备和浏览器设置基线.
* [Test Driven Progressive Enhancement](http://alistapart.com/article/testdriven) - 测试功能后，核心功能体验得到增强.
* [Cut the mustard](http://responsivenews.co.uk/post/18948466399/cutting-the-mustard) - 设置增强功能集合的阈值.
* [等级组件，而不是浏览器]（https://www.filamentgroup.com/lab/grade-the-components.html
） - 组件级功能测试和增强功能.
* [Feature vs Browser vs Form factor detection](http://www.html5rocks.com/en/tutorials/detection/) - 作为将应用程序调整到其环境的不同策略.
* [Server-side device detection](https://www.smashingmagazine.com/2014/07/server-side-device-detection-with-javascript/) - 使用用户代理和其他HTTP标头信息与设备数据库结合有条件地提供文件.
* [Writing polyfills](https://addyosmani.com/blog/writing-polyfills/) - 如果某些浏览器的基线仍然太高，请考虑 [polyfills](https://remysharp.com/2010/10/08/what-is-a-polyfill) （又名 [Regressive Enhancement](https://twitter.com/SlexAxton/status/25600963629)).
* [Application Shell Architecture](https://medium.com/google-developers/instant-loading-web-apps-with-an-application-shell-architecture-7c0c2f10c73) - 即时加载Web应用程序的设置.


## Feature Detection

 在尝试增强体验之前，您需要确保环境能够增强.  您可以通过执行功能检测来测试它：

* [CSS feature queries](https://www.sitepoint.com/an-introduction-to-css-supports-rule-feature-queries/) ([`CSS.supports()`](https://developer.mozilla.org/en/docs/Web/API/CSS/supports) & [`@supports()`](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports)) - Natively test if specific CSS feature is supported using JS method or CSS declaration.
* [Feature Detect ES6](https://www.npmjs.com/package/feature-detect-es6) - 检测哪些ES2015功能可用.
* [SVG requiredFeatures](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/requiredFeatures) - 只有当`[requiredFeatures]`求值为true时才渲染SVG元素.
* [Modernizr](https://modernizr.com/) - 广泛的功能检测套件（支持自定义构建）.
* [Feature.js](http://featurejs.com/) - 轻量级功能检测套件.
* [Conditioner.js](http://conditionerjs.com/) - 根据HTML属性中的指令有条件地加载JS模块.
* [EnhanceJS](https://www.filamentgroup.com/lab/introducing-enhancejs-smarter-safer-apply-progressive-enhancement.html) - 允许您在设置预定义功能测试后异步加载CSS和JS.


## Support Tables

 不同的环境（平台，浏览器，版本）具有不同的功能.  支持表告诉您每个环境具有哪些功能.  了解支持级别可以帮助您权衡增强与其实施的努力和影响.

* [The Web Platform](https://platform.html5.org/) - 浏览器技术概述，包含指向文档和测试套件的链接.
* [Can I use ...?](http://caniuse.com/) - 比较桌面和移动浏览器的功能实现和限制.
* [I want to use ...](http://www.iwanttouse.com/) - 找出浏览器对功能组合的支持.
* [HTML5 Test](http://html5test.com/) - 测试和比较跨浏览器的HTML5功能支持.
* [CSS3 Test](http://css3test.com/) -  CSS3的细粒度测试功能支持您当前的浏览器.
* [State of Web Type](http://stateofwebtype.com/) - 支持Web上的类型和印刷功能表.
* [Font Family Reunion](http://fontfamily.io/) - 默认本地（系统）字体的兼容性表.
* [HTML5 Accessibility](http://html5accessibility.com/) - 比较HTML5标签的功能支持，主要浏览器的输入类型和属性. 
* [WAI-ARIA Screen reader compatibility](https://www.powermapper.com/tests/screen-readers/aria/) -  ARIA角色和属性支持不同的屏幕阅读器和浏览器组合.
* [What web can do today](https://whatwebcando.today/) - 列出并检查现代Web API，例如访问设备系统，传感器和执行器.
* [HTML5 Worker test](https://nolanlawson.github.io/html5workertest/) - 比较浏览器中Web Workers和Service Workers支持的API.
* [HTML5 Please](http://html5please.com/) - 探索功能，包括建议和填充物的链接.
* [API Catalog](https://developer.microsoft.com/en-us/microsoft-edge/platform/catalog/) - 允许您比较主要桌面浏览器中API规范的实现.
* [Kangax's ECMAScript compatibility table](http://kangax.github.io/compat-table/) - 跨浏览器和其他运行时的JavaScript功能支持概述.
* [Node compatibility table](http://node.green/) - 跨NodeJS版本的JavaScript功能支持概述.
* [Is service worker ready?](https://jakearchibald.github.io/isserviceworkerready/) - 支持Progressive Web Apps背后的核心技术所涉及的所有功能的概述.
* [Is PWA ready?](https://ispwaready.toxicjohann.com/) - 针对流行的全球和许多中国浏览器支持Progressive Web Apps背后的核心和相关技术的概述.
* [Is WebRTC ready yet?](http://iswebrtcreadyyet.com/) - 支持实时通信背后的不同浏览器功能的概述.
* [Is WebVR ready?](https://iswebvrready.org/) - 支持WebVR背后不同浏览器功能的概述，包括显示，游戏手柄，音频和语音API.
* [Chrome Platform Status](https://www.chromestatus.com/features)
* [Edge Platform Status](https://developer.microsoft.com/en-us/microsoft-edge/platform/status/)
* [Firefox Platform Status](https://platform-status.mozilla.org/)
* [Webkit Platform Status](https://webkit.org/status/) （苹果浏览器）
* [MDN Compatibility tables](https://developer.mozilla.org/en-US/docs/MDN/Contribute/Structures/Compatibility_tables) -  MDN的Web技术文档在每篇文章末尾都有一个浏览器兼容性表.
* [MDN Browser Compat Data](https://github.com/mdn/browser-compat-data) -  npm模块为MDN兼容性表提供支持.
* [Device Bugs & Quirks](https://github.com/scottjehl/Device-Bugs) -  Crowd收集了移动设备中奇怪的HTML，CSS和JS怪癖的集合，这些在其他支持表中找不到.


## Testing Methods

 通过渐进增强，您可以支持不同环境中的不同体验  这些是测试所有这些变化的一些方法：

* [Open Device Lab](https://opendevicelab.com/) - 让您*在实际设备上手动测试*（免费）.
* [Text browsers](https://en.wikipedia.org/wiki/Text-based_web_browser)   - 测试您的内容是否可在基线访问的好方法.  尝试 [Lynx](http://lynx.browser.org/) 例如.
* [Testing in Opera Mini](https://dev.opera.com/articles/making-sites-work-opera-mini/#testing-in-opera-mini)   - 下载应用程序，在桌面上模拟，设置以测试本地网站.  （Opera Mini占全球浏览器使用率的5％以上）
* [cURL](https://curl.haxx.se/docs/manual.html) - 用于查看页面的预呈现源代码的网页.
* [Browserling](https://www.browserling.com/) - 允许您在Windows和Android平台上手动测试不同版本浏览器中的网页.
* [Run Internet Explorer using Virtual Machines](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/mac/) - 在其他平台上测试IE浏览器.
* [Device emulators and simulators](https://developers.google.com/web/tools/chrome-devtools/iterate/device-mode/testing-other-browsers?hl=en#device-emulators-and-simulators)
* [Configure *Desired Capabilities* in Selenium](https://github.com/SeleniumHQ/selenium/wiki/DesiredCapabilities) - 在不同的场景中运行自动浏览器测试.
*使用不同浏览器连续运行自动化测试 [BrowserStack](https://www.browserstack.com/), [Saucelabs](https://saucelabs.com/) 或其他替代方案.
* [Lighthouse](https://github.com/GoogleChrome/lighthouse) - 审计和测试Progressive Web Apps的性能（通过cli或 [Chrome extension](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk)).
* [Progressive Enhancement checklist (1st edition, HTML)](http://adaptivewebdesign.info/1st-edition/read/chapter-6.html#the-progressive-enhancement-checklist), [Checklist of 2nd edition (PDF)](http://adaptivewebdesign.info/2nd-edition/checklist.pdf)   - 可操作的列表，用于检查您是否已应用渐进增强最佳实践.  部分 [Adaptive Web Design book](http://adaptivewebdesign.info/).
* [CSS Feature Toggles](https://chrome.google.com/webstore/detail/css-feature-toggles/aeinmfddnniiloadoappmdnffcbffnjg) -  Chrome DevTools扩展，用于切换对所选CSS功能的支持，以测试渐进增强回退.


## Examples

### Custom Form Elements

* [Fancy radio buttons](https://www.sitepoint.com/replacing-radio-buttons-without-replacing-radio-buttons/) - 基于HTML单选按钮，使用CSS伪类和元素进行可视化增强.
* [Checkboxes & radio buttons](https://www.filamentgroup.com/dwpe/checkbox-radiobutton/)   - 具有自定义焦点，悬停和检查状态.  异步增强.
* [Toggle switch](https://ghinda.net/css-toggle-switch/) - 复选框或无线电，仅使用CSS可视化增强到滑动切换开关.
* [5-star rating](http://lea.verou.me/2011/08/accessible-star-rating-widget-with-pure-css/) - 基于HTML单选按钮，使用CSS伪类和元素进行可视化增强.
* [jQuery slider](https://github.com/filamentgroup/jQuery-Slider) - 基于标准HTML选择的可访问的自定义滑块小部件.
* [jQuery custom file input](https://www.filamentgroup.com/lab/jquery-custom-file-input-book-designing-with-progressive-enhancement.html) - 文章和图书馆.
* [React isomorphic form](https://github.com/ghengeveld/react-isomorphic-form/)   - 一组React表单组件，可以在服务器端预呈现和处理.  它们在客户端增强而不会丢失状态.

### Data Visualisations

* [Timeline](https://css-tricks.com/progressive-enhancement-data-visualizations/) - 从定义列表到SVG插图（带演示的文章）.
* [Charts](https://www.filamentgroup.com/lab/update-to-jquery-visualize-accessible-charts-with-html5-from-designing-with.html) - 使用HTML5画布（文章和库）从数据表到主题图表.

### Images

* [Responsive Carousel](http://filamentgroup.github.io/responsive-carousel/test/functional/fade-auto.html) - 增强到具有各种行为选项的响应轮播的图像列表.
* [Lazy Progressive Enhancement](https://github.com/tvler/lazy-progressive-enhancement)   - 懒惰加载`里面的图像 <noscript>  `标签.  （注意：仅限常绿浏览器）

### Menus

* [Progressive hamburger menu](http://heydonworks.com/practical_aria_examples/#hamburger) - 页脚链接列表增强到画布外菜单.

### Page Navigation

使用ajax和`history.pushState`在静态页面之间异步获取和转换：

* [Barba.js](http://barbajs.org/) - 使用事件挂钩，缓存和预取支持添加页面转换.
* [SmoothState.js](https://github.com/miguel-perez/smoothState.js)   - 使用事件挂钩，缓存和预取支持添加页面转换.  （需要jQuery）.
* [jquery-pjax](https://github.com/defunkt/jquery-pjax) - 添加页面转换，支持多个容器/内容槽（需要jQuery）.
* [MoOx/pjax](https://github.com/MoOx/pjax) - 类似于jquery-pjax，但没有jQuery依赖.
* [Turbolinks](https://github.com/turbolinks/turbolinks)   - 使用事件挂钩和缓存支持添加页面转换.  具有适配器以绑定到iOS和Android上的本机导航控件.


## Related Articles

* [Make the web work for everyone](https://hacks.mozilla.org/2016/07/make-the-web-work-for-everyone/) - 请开发人员考虑浏览器差异并构建弹性网络.
* [How many people are missing out on JavaScript enhancement?](https://gds.blog.gov.uk/2013/10/21/how-many-people-are-missing-out-on-javascript-enhancement/) - 研究为什么1.1％的页面访问JavaScript未加载. 

---

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

[Jasper Moelker](https://twitter.com/jbmoelker) 在法律允许的范围内，根据版权法放弃全球范围内对本作品的所有权利，包括所有相关和邻接权利.

您可以复制，修改，分发和执行工作，即使是出于商业目的，也可以不经许可.
