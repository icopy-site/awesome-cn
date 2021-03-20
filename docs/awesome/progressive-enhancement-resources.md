<div class="github-widget" data-repo="jbmoelker/progressive-enhancement-resources"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Progressive Enhancement Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

有关渐进增强的资源的全面收集. 从概念和策略到功能检测和测试方法. 完整列出（代码）示例.





## The Concept

[Progressive Enhancement](https://en.wikipedia.org/wiki/Progressive_enhancement) 表示在验证目标环境（例如，浏览器）具备的能力后，逐渐改善其用户体验. 从内容开始，并确保您保持功能和可访问性.

* [The Role of Enhancement in Web Design](https://www.nngroup.com/articles/enhancement/) -从增强的概念到丰富用户界面的标准和规则.
* [Understanding Progressive Enhancement](http://alistapart.com/article/understandingprogressiveenhancement) -以智能的方式逐层应用技术，以创造惊人的体验.
* [Designing with Progressive Enhancement](https://www.filamentgroup.com/dwpe/) -*有关渐进增强的书*（超过400页）.
* [Detecting (HTML5) features](http://diveinto.html5doctor.com/detect.html) -通过示例和演示介绍不同的特征检测技术. 
* [Progressive Web Apps](https://infrequently.org/2015/06/progressive-apps-escaping-tabs-without-losing-our-soul/) -将网站增强为类似本机的应用程序（渐进式，非混合式）.


## Strategies

您可以采用不同的方式应用渐进增强：

* [Make the page usable with only HTML](https://www.gov.uk/service-manual/technology/using-progressive-enhancement#make-the-page-usable-with-only-html) -这将为每个设备和浏览器设置基准.
* [Test Driven Progressive Enhancement](http://alistapart.com/article/testdriven) -经过测试的功能增强了核心功能体验.
* [Cut the mustard](http://responsivenews.co.uk/post/18948466399/cutting-the-mustard) -设置收集增强的阈值.
* [等级组件，而不是浏览器]（https://www.filamentgroup.com/lab/grade-the-components.html
）-组件级功能测试和增强.
* [Feature vs Browser vs Form factor detection](http://www.html5rocks.com/en/tutorials/detection/) -作为将您的应用调整到其环境的不同策略.
* [Server-side device detection](https://www.smashingmagazine.com/2014/07/server-side-device-detection-with-javascript/) -将用户代理和其他HTTP标头信息与设备数据库结合使用，以有条件地提供文件.
* [Writing polyfills](https://addyosmani.com/blog/writing-polyfills/) -如果您的基准对于某些浏览器仍然过高，请考虑 [polyfills](https://remysharp.com/2010/10/08/what-is-a-polyfill) （又名 [Regressive Enhancement](https://twitter.com/SlexAxton/status/25600963629)).
* [Application Shell Architecture](https://medium.com/google-developers/instant-loading-web-apps-with-an-application-shell-architecture-7c0c2f10c73) -设置为即时加载Web应用程序.


## Feature Detection

在尝试增强体验之前，需要确保环境能够进行增强. 您可以通过执行功能检测来对此进行测试：

* [CSS feature queries](https://www.sitepoint.com/an-introduction-to-css-supports-rule-feature-queries/) ([`CSS.supports()`](https://developer.mozilla.org/en/docs/Web/API/CSS/supports) & [`@supports()`](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports)）-使用JS方法或CSS声明，本机测试是否支持特定的CSS功能.
* [Feature Detect ES6](https://www.npmjs.com/package/feature-detect-es6) -检测哪些ES2015功能可用.
* [SVG requiredFeatures](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/requiredFeatures) -仅在其[requiredFeatures]评估为true时才渲染SVG元素.
* [Modernizr](https://modernizr.com/) -广泛的功能检测套件（支持自定义版本）.
* [Feature.js](http://featurejs.com/) -轻量级功能检测套件.
* [Conditioner.js](http://conditionerjs.com/) -根据HTML属性中的指令有条件地加载JS模块.
* [EnhanceJS](https://www.filamentgroup.com/lab/introducing-enhancejs-smarter-safer-apply-progressive-enhancement.html) -让您在一组预定义的功能测试后异步加载CSS和JS.


## Support Tables

不同的环境（平台，浏览器，版本）具有不同的功能. 支持表告诉您每种环境具有哪些功能. 了解支持级别可以帮助您权衡一项增强与实现的工作量和影响.

* [The Web Platform](https://platform.html5.org/) -浏览器技术概述，其中包含指向文档和测试套件的链接.
* [Can I use ...?](http://caniuse.com/) -比较跨桌面和移动浏览器的功能实现和限制.
* [I want to use ...](http://www.iwanttouse.com/) -找出浏览器对功能组合的支持.
* [HTML5 Test](http://html5test.com/) -测试和比较跨浏览器的HTML5功能支持.
* [CSS3 Test](http://css3test.com/) -当前浏览器对CSS3功能支持的细粒度测试.
* [Accessibility Support](https://a11ysupport.io/) -比较跨浏览器和辅助技术对HTML元素和ARIA角色的可访问性支持.
* [State of Web Type](https://github.com/bramstein/stateofwebtype) -网络上的类型和印刷功能的支持表.
* [Font Family Reunion](http://fontfamily.io/) -默认本地（系统）字体的兼容性表.
* [HTML5 Accessibility](http://html5accessibility.com/) -比较主要浏览器对HTML5标签，输入类型和属性的功能支持. 
* [WAI-ARIA Screen reader compatibility](https://www.powermapper.com/tests/screen-readers/aria/) -ARIA角色和属性支持不同的屏幕阅读器和浏览器组合.
* [What web can do today](https://whatwebcando.today/) -列出并检查现代Web API，例如对设备系统，传感器和执行器的访问.
* [HTML5 Worker test](https://nolanlawson.github.io/html5workertest/) -比较跨浏览器的Web Workers和Service Workers支持哪些API.
* [HTML5 Please](http://html5please.com/) -通过推荐功能和指向Polyfill的链接来探索功能.
* [API Catalog](https://developer.microsoft.com/en-us/microsoft-edge/platform/catalog/) -可让您比较主要桌面浏览器中API规范的实现.
* [Kangax's ECMAScript compatibility table](http://kangax.github.io/compat-table/) -跨浏览器和其他运行时的JavaScript功能支持概述.
* [Node compatibility table](http://node.green/) -跨NodeJS版本的JavaScript功能支持概述.
* [Is service worker ready?](https://jakearchibald.github.io/isserviceworkerready/) - Overview of support for all features involved in the core technology behind Progressive Web Apps.
* [Is PWA ready?](https://ispwaready.toxicjohann.com/) -渐进式Web应用程序对流行的全球和许多中文浏览器支持的核心和相关技术的支持概述.
* [Is WebRTC ready yet?](http://iswebrtcreadyyet.com/) -实时通信背后对不同浏览器功能的支持概述.
* [Is WebVR ready?](https://iswebvrready.org/) -WebVR背后对各种浏览器功能的支持概述，包括显示，游戏手柄，音频和语音API.
* [Is Houdini ready yet?](https://ishoudinireadyyet.com/) -跨浏览器对Houdini（支持CSS渲染引擎的部分的低级API）的支持概述.
* [Chrome Platform Status](https://www.chromestatus.com/features)
* [Edge Platform Status](https://developer.microsoft.com/en-us/microsoft-edge/platform/status/)
* [Firefox Platform Status](https://platform-status.mozilla.org/)
* [Webkit Platform Status](https://webkit.org/status/) （苹果浏览器）
* [MDN Compatibility tables](https://developer.mozilla.org/en-US/docs/MDN/Contribute/Structures/Compatibility_tables) -MDN的网络技术文档在每篇文章的末尾都有一个浏览器兼容性表.
* [MDN Browser Compat Data](https://github.com/mdn/browser-compat-data) -为MDN兼容性表供电的npm模块.
* [Device Bugs & Quirks](https://github.com/scottjehl/Device-Bugs) -在移动设备中拥挤了怪异的HTML，CSS和JS怪癖的众包来源，在其他支持表中则找不到.
* [Can I Email?](https://www.caniemail.com/)  -电子邮件中HTML和CSS的支持表. 受启发 [Can I use](http://caniuse.com/).


## Testing Methods

通过逐步增强，您可以在不同的环境中支持不同的体验. 这些是测试所有这些变体的方法：

* [Open Device Lab](https://opendevicelab.com/) -让您*在实际设备上手动测试*（免费）.
* [Testing in Opera Mini](https://dev.opera.com/articles/making-sites-work-opera-mini/#testing-in-opera-mini)  -下载该应用程序，在桌面上模拟，设置以测试本地网站.  （Opera Mini占全球浏览器使用量的5％以上）
* [cURL](https://curl.haxx.se/docs/manual.html) -网页以查看页面的预渲染源代码.
* [Browserling](https://www.browserling.com/) -可让您在Windows和Android平台上的不同版本的浏览器中手动测试网页.
* [Run Internet Explorer using Virtual Machines](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/mac/) -在其他平台上测试IE浏览器.
* [Device emulators and simulators](https://developers.google.com/web/tools/chrome-devtools/iterate/device-mode/testing-other-browsers?hl=en#device-emulators-and-simulators)
* [Configure *Desired Capabilities* in Selenium](https://github.com/SeleniumHQ/selenium/wiki/DesiredCapabilities) -在不同情况下运行自动浏览器测试.
*使用以下工具在不同的浏览器中连续运行自动化测试 [BrowserStack](https://www.browserstack.com/), [Saucelabs](https://saucelabs.com/) 或其他替代方法.
* [Lighthouse](https://github.com/GoogleChrome/lighthouse) -审核和衡量渐进式Web应用程序的性能（通过cli或 [Chrome extension](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk)).
* [Progressive Enhancement checklist (1st edition, HTML)](http://adaptivewebdesign.info/1st-edition/read/chapter-6.html#the-progressive-enhancement-checklist), [Checklist of 2nd edition (PDF)](http://adaptivewebdesign.info/2nd-edition/checklist.pdf)  -可操作的列表，以检查您是否已应用渐进增强最佳实践. 部分 [Adaptive Web Design book](http://adaptivewebdesign.info/).
* [CSS Feature Toggles](https://chrome.google.com/webstore/detail/css-feature-toggles/aeinmfddnniiloadoappmdnffcbffnjg) -Chrome DevTools扩展程序可切换对所选CSS功能的支持，以测试渐进式增强后备.


## Examples

### Custom Form Elements

* [Fancy radio buttons](https://www.sitepoint.com/replacing-radio-buttons-without-replacing-radio-buttons/) -基于HTML单选按钮，使用CSS伪类和元素在视觉上进行了增强.
* [Checkboxes & radio buttons](https://www.filamentgroup.com/dwpe/checkbox-radiobutton/)  -具有自定义焦点，悬停和检查状态. 异步增强.
* [Toggle switch](https://ghinda.net/css-toggle-switch/) -复选框或单选按钮，在视觉上已增强为仅使用CSS的滑动拨动开关.
* [5-star rating](http://lea.verou.me/2011/08/accessible-star-rating-widget-with-pure-css/) -基于HTML单选按钮，使用CSS伪类和元素在视觉上进行了增强.
* [jQuery slider](https://github.com/filamentgroup/jQuery-Slider) -基于标准HTML选择的可访问的自定义滑块小部件.
* [jQuery custom file input](https://www.filamentgroup.com/lab/jquery-custom-file-input-book-designing-with-progressive-enhancement.html) -文章和图书馆.
* [React isomorphic form](https://github.com/ghengeveld/react-isomorphic-form/)  -一组可在服务器端预渲染和处理的React表单组件. 它们是增强的客户端，而不会丢失状态.

### Data Visualisations

* [Timeline](https://css-tricks.com/progressive-enhancement-data-visualizations/) -从定义列表到SVG插图（带有演示的文章）.
* [Charts](https://www.filamentgroup.com/lab/update-to-jquery-visualize-accessible-charts-with-html5-from-designing-with.html) -使用HTML5画布（文章和库）从数据表到主题图表.

### Images

* [Responsive Carousel](http://filamentgroup.github.io/responsive-carousel/test/functional/fade-auto.html) -具有各种行为选项的增强到响应式轮播中的图像列表.
* [Lazy Progressive Enhancement](https://github.com/tvler/lazy-progressive-enhancement)  -内懒加载图片<noscript>标签.  （注意：仅常绿浏览器）

### Menus

* [Progressive hamburger menu](http://heydonworks.com/practical_aria_examples/#hamburger) -页脚中的链接列表已增强到非画布菜单.

### Page Navigation

使用ajax和`history.pushState`在静态页面之间异步获取和转换：

* [Barba.js](http://barbajs.org/) -添加具有事件挂钩，缓存和预取支持的页面转换.
* [SmoothState.js](https://github.com/miguel-perez/smoothState.js)  -添加具有事件挂钩，缓存和预取支持的页面转换.  （需要jQuery）.
* [MoOx/pjax](https://github.com/MoOx/pjax) -与jquery-pjax类似，但没有jQuery依赖关系.
* [Turbolinks](https://github.com/turbolinks/turbolinks)  -添加带有事件挂钩和缓存支持的页面过渡. 具有可绑定到iOS和Android上的本机导航控件的适配器.


## Related Articles

* [Make the web work for everyone](https://hacks.mozilla.org/2016/07/make-the-web-work-for-everyone/) -恳请开发人员考虑浏览器的差异并构建具有弹性的网站.
* [How many people are missing out on JavaScript enhancement?](https://gds.blog.gov.uk/2013/10/21/how-many-people-are-missing-out-on-javascript-enhancement/) -研究为何在1.1％的网页访问中未加载JavaScript. 

---

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

[Jasper Moelker](https://twitter.com/jbmoelker) 在法律允许的范围内，放弃在全球范围内根据版权法享有此作品的所有权利，包括所有相关和邻接权.

您可以复制，修改，分发和执行作品，甚至用于商业目的，而无需征得您的许可.
