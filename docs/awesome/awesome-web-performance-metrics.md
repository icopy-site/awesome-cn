<div class="github-widget" data-repo="csabapalfi/awesome-web-performance-metrics"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Web Performance Metrics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt;有助于了解页面速度和用户体验的指标.


<!-- toc -->


<!-- tocstop -->

## Concepts

### Lab Data (Synthetic Measurements)

 使用工具对页面进行请求并评估性能.  确保使其逼真（例如，通过节流网络和CPU）并减少噪音（例如，通过多次运行）.

- [Lighthouse](https://developers.google.com/web/tools/lighthouse/)  -一种基于Google Chrome浏览器的工具，用于审核网页.  您可以从Chrome DevTools，Chrome扩展程序或从命令行（即使使用无头Chrome）运行它.
- [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) -Google提供的免费托管的Lighthouse报告（以及更多）.
- [WebpageTest](https://www.webpagetest.org/) -免费和托管的Web性能测试（也是一个开源项目）.
- [Sitespeed.io](https://www.sitespeed.io/) -一组开源性能监视工具.
- [Calibre](https://calibreapp.com) -Web性能监控SaaS.
- [treo.sh](https://treo.sh/) -Web性能监控SaaS.
- [SpeedCurve](https://speedcurve.com/) -Web性能监控SaaS.

---

### Field Data (Real User Monitoring - RUM)

 从访问您页面的实际用户收集性能数据.  请注意实际开销，因为它会在您的用户浏览器中运行，并注意浏览器对最新指标的支持（例如，与您的用户群相比）.

- [Performance tracking with Google Analytics (GA)](https://philipwalton.com/articles/the-google-analytics-setup-i-use-on-every-site-i-build/#performance-tracking)
- [Chrome User Experience Report (CrUX)](https://developers.google.com/web/tools/chrome-user-experience-report/)
- [Load abandonment](https://developers.google.com/web/updates/2017/06/user-centric-performance-metrics#load_abandonment) -追踪“ visibilitychange”以解决生存偏差.
- [SpeedCurve LUX](https://speedcurve.com/features/lux/) -真实用户监控SaaS.
- [Akamai mPulse](https://www.akamai.com/uk/en/products/performance/mpulse-real-user-monitoring.jsp) -真实用户监控SaaS.
- [Sematext Experience](https://sematext.com/experience/) -真实用户监控SaaS.

### Critical rendering path

 关键的渲染路径是**在接收网络字节和在屏幕上渲染某些东西之间发生的一切**.  要优化任何渲染指标，例如 [First Contentful Paint (FCP)](#first-contentful-paint-fcp) 要么 [Speed Index](#speed-index) you have to understand how the critical rendering path w要么ks.

- [Critical rendering path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/)

### Long tasks

 处理用户输入的浏览器主线程也是执行JavaScript的一个（在许多其他事物中）.  阻塞主线程的时间过长会使页面无响应.

 用户将100ms内的任何视觉变化视为瞬间.  任何通过“花费超过50毫秒的时间来阻塞主线程”的任务都被认为是一项长任务**（因为这可能会使浏览器对用户输入无响应）.

为了优化交互性指标，例如 [Time to Interactive (TTI)](#time-to-interactive-tti) 和 [First Input Delay (FID)](#first-input-delay-fid) you have to underst和 long tasks 和 how to avoid them as much as possible.

- [Spec - Long Tasks](https://w3c.github.io/longtasks/)
- [Blogpost - Tracking CPU with Long Tasks API](https://calendar.perfplanet.com/2017/tracking-cpu-with-long-tasks-api/)

### User-centric metrics

 用户通常在寻找视觉反馈和保证.  为了衡量这种感知的性能（在加载的各个阶段），我们可以选择可以直接回答以下问题的指标.

- [User-centric Performance Metrics](https://developers.google.com/web/updates/2017/06/user-centric-performance-metrics)
 -发生了吗？  -导航是否成功启动？  服务器响应了吗？  （例如 [FCP](https://github.com/csabapalfi/awesome-web-performance-metrics/#first-contentful-paint-fcp))
 -有用/有意义吗？  -是否渲染了足够的内容以使用户可以参与其中？  （例如 [FMP](https://github.com/csabapalfi/awesome-web-performance-metrics/#first-meaningful-paint-fmp))
 -是否可用-用户可以与页面进行交互，还是仍在忙于加载？  （例如 [TTI](https://github.com/csabapalfi/awesome-web-performance-metrics/#time-to-interactive-tti))
 -令人愉快/顺滑吗？  -交互是否顺畅自然，没有滞后和颠簸？

### Apdex score

应用程序性能指数，或 [Apdex](https://en.wikipedia.org/wiki/Apdex)，是在与您的网站或应用程序进行交互时，根据请求的响应时间来衡量用户满意度的衡量标准. 

- [Apdex technical specification](http://www.apdex.org/index.php/category/specification/)
- [How to Use Apdex Score to Measure User Satisfaction](https://sematext.com/blog/how-to-use-your-apdex-score-to-measure-user-satisfaction/)

---

## Rendering metrics


 第一个内容丰富的油漆标记“第一个文本或图像”（包括背景图像），非白色画布或SVG的绘制时间.  这包括带有待定Web字体的文本.  这是用户第一次开始使用页面内容.

-实验室：灯塔
-领域：Chrome 60以上版本，Opera 47以上版本，CrUX
- [Docs - FCP - Lighthouse](https://developers.google.com/web/tools/lighthouse/audits/first-contentful-paint)
- [Spec - FCP - W3C](https://w3c.github.io/paint-timing/)


### First Meaningful Paint (FMP)

 当页面的主要内容可见时，“第一个有意义的绘画”将进行测量**.  从本质上讲，这是发生最大的折页式布局更改并加载Web字体后的绘画.

-实验室：灯塔
-领域：不适用
- [Docs - FMP - Lighthouse](https://developers.google.com/web/tools/lighthouse/audits/first-meaningful-paint)
- [Spec - First Meaningful Paint](https://docs.google.com/document/d/1BR94tJdZLsin5poeet0XoTW60M0SjvOJQttKT-JK8HI/view)

### Speed Index

 速度索引显示**页面内容的填充速度有多快**（数字越小越好）.  这是通过在加载过程中经常测量外观完整性来完成的.  页面越直观越完整，值越低.

-实验室：WPT灯塔（但规格略有不同）
-领域：不适用
- [Docs - Speed Index - Lighthouse](https://developers.google.com/web/tools/lighthouse/audits/speed-index)
- [Docs - Speed Index - WPT](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)
- [Talk - Speed Perception and Lighthouse](https://ldnwebperf.org/events/speed-perception-and-lighthouse/)


### Start render

“开始渲染”是指从初始导航的开始到**绘制第一个非白色内容**到浏览器显示的时间.

-实验室：WPT
- [Docs - Start Render - WPT](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics)


### First Paint (FP)

 First Paint报告“导航后第一次呈现浏览器”的时间.  这不包括默认背景画，但包括非默认背景画.  这是开发人员关心页面加载的第一个关键时刻-当浏览器开始呈现页面时.

-实验室：LightHouse JSON报告包括但不包括HTML报告，也类似于 [Start render](#start-render) 在WPT中
-领域：Chrome 60以上版本，Opera 47以上版本，CrUX
- [Spec - FP - W3C](https://w3c.github.io/paint-timing/)

### Visually Complete

 视觉上的完成是指从初始导航开始到页面的“可见（折页以上）”部分不再更改**的时间.  （使用基于视频/屏幕快照记录的颜色直方图进行测量）.

-实验室：WPT
-领域：不适用
- [Docs - Visually Complete - WPT](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)

### Hero Element Timing

“英雄元素定时”在浏览器绘制特定元素时进行捕获（例如，您的“ h1”或英雄图像等）.

-实验室：WPT
-字段：不适用，但请参见下面的未填写的polyfill
- [W3C GitHub issue - Element Timing API](https://github.com/w3c/charter-webperf/issues/30)
- [Spec - Hero Element Timing](https://docs.google.com/document/d/1yRYfYR1DnHtgwC4HRR04ipVVhT1h5gkI6yPmKCgJkyQ/edit#)
- [Blogpost - Hero Element Timing - SpeedCurve](https://speedcurve.com/blog/web-performance-monitoring-hero-times/)
- [Polyfill - Hero Element Timing](https://github.com/tdresser/hero-element-polyfill) -另请参阅 [announcement here](https://groups.google.com/a/chromium.org/forum/m/#!topic/progressive-web-metrics/ND6JVZRWqqg)
- [Blogpost - User Timing for Element Timing - SpeedCurve](https://speedcurve.com/blog/user-timing-and-custom-metrics/)
- [Blogpost - Last Painted Hero coming to WebpageTest](https://speedcurve.com/blog/last-painted-hero/)
- [Docs - Element Timing Explainer](https://docs.google.com/document/d/1blFeMVdqxB0V3BAJh60ptOBFY7cJSXnf7VyW3wspbZ8/edit#heading=h.eny79fwwx642)
- [Docs - Hero Text Element Timestamps](https://docs.google.com/document/d/1co1yefZWQ4QvG_2WT0nCrqxcAgjU08um9Boe_JzHkdE/edit#heading=h.zwg1kfkhqmx)


### Cumulative Layout Shift score (CLS)

 源自Layout Instability API的指标.  累积布局偏移（CLS）分数是通过计算从页面加载到页面生命周期状态变为隐藏为止的所有意外（而不是用户交互的0.5秒以内）布局偏移分数的总和来确定的.

-实验室：不适用
-领域：CrUX + Chrome 73+（原始试用版）
- [Spec - Layout Instability](https://github.com/WICG/layout-instability)
- [Chrome - Origin Trial for Layout Stability API](https://developers.chrome.com/origintrials/#/view_trial/1215971899390033921)
- [Blogpost - The Layout Instability API](https://web.dev/layout-instability-api/)


-实验室：不适用
-领域：不适用（Chrome：正在开发中）
- [Spec - Largest Contentful Paint](https://github.com/WICG/LargestContentfulPaint)
- [Docs - Largest Contentful Paint](https://docs.google.com/document/d/1ySnglZJiCbOrOMX8PNgE0mRKmt9vglNDyggE8oYN8gQ/edit#heading=h.hjlf1s5m20ko)
- [Blogpost - Largest Contentful Paint](https://web.dev/largest-contentful-paint/)

---

## Interactivity metrics

### First CPU Idle

“第一CPU空闲”标志着**页面主线程足够安静以处理用户输入的第一次**.

-实验室：WPT灯塔（但在WPT中被称为“首次互动”）
-领域：不适用
- [Docs - First Interactive - WPT](https://github.com/WPO-Foundation/webpagetest/blob/master/docs/Metrics/TimeToInteractive.md)
- [Docs - First CPU Idle - Lighthouse](https://developers.google.com/web/tools/lighthouse/audits/first-cpu-idle)

### Time to Interactive (TTI)

 互动时间是**页面完全互动所花费的时间**（如在主线程中安静5s）.  不要与First Interactive或First CPU Idle混淆.  （警告：最令人困惑和误解的指标之一）.

-字段：不建议使用，因为与您的页面进行交互的用户可能会扭曲TTI的字段度量
- [Polyfill - TTI](https://github.com/GoogleChromeLabs/tti-polyfill)
- [Spec - TTI - Lighthouse](https://docs.google.com/document/d/1GGiI9-7KeY3TPqS3YT271upUVimo-XiL5mwWorDUD4c/edit)
- [Blogpost - TTI](https://blog.dareboost.com/en/2019/05/measuring-interactivity-time-to-interactive/)

### First Input Delay (FID)

 首次输入延迟（FID）用于衡量**从用户首次与您的网站进行交互到浏览器实际上能够对该交互做出响应的时间**.  交互可以是用户单击链接，点击按钮或使用自定义的JavaScript驱动的控件.

-实验室：不适用（因为它要求用户与页面互动）
-栏位：IE9 +（以及Safari，Chrome，Firefox）（带有polyfill-0.4KB）
- [Docs - FID](https://developers.google.com/web/updates/2018/05/first-input-delay)
- [Polyfill - FID](https://github.com/GoogleChromeLabs/first-input-delay)


### First Interactive


### Consistently Interactive

See [Time to Interactive (TTI)](#time-to-interactive-tti) .  WPT仍将TTI称为“持续交互”，但仅可用于Chrome浏览器，而不能出现在UI中（仅在原始结果XML / JSON中）.

### Estimated Input Latency

 估计的输入延迟是**在页面加载最繁忙的5s窗口内，应用对用户输入做出响应所花费的时间的估算值（以毫秒为单位）.  如果您的延迟时间超过50毫秒，则用户可能会认为您的应用比较落后. 

-实验室：灯塔
-领域：不适用
- [Docs - Estimated Input Latency - Lighthouse](https://developers.google.com/web/tools/lighthouse/audits/estimated-input-latency)

### Max Potential First Input Delay

最大潜力 [First Input Delay](#first-input-delay-fid)  您的用户可能会体验到的.  基本上等于最长的持续时间 [long task](#long-tasks) 在浏览器主线程上.

-实验室：灯塔
-领域：不适用

### Total Blocking Time

-实验室：灯塔
-领域：不适用
- [Total Blocking Time](https://docs.google.com/document/d/1xCERB_X7PiP5RAZDwyIkODnIXoBk-Oo7Mi9266aEdGg/edit)

---

## Network metrics

 网络计时字段数据可能会发现未优化的TLS设置，DNS查找缓慢或服务器端处理以及CDN配置问题.  另请参阅有关测量的单独部分 [transferred bytes](#transferred-bytes).

- [Blogpost - Navigation and Resource Timing](https://developers.google.com/web/fundamentals/performance/navigation-and-resource-timing/)
- [Spec - Navigation Timing](https://www.w3.org/TR/navigation-timing-2/)
- [Spec - Resource Timing](https://www.w3.org/TR/resource-timing-2/)

### DNS latency

-实验室：DNS性能测试工具
-领域：IE9 +，Safari 9+

```js
//测量DNS查找时间
var pageNav = performance.getEntriesByType（“ navigation”）[0];
var dnsTime = pageNav.domainLookupEnd-pageNav.domainLookupStart;
```

### TCP and SSL/TLS latency

-实验室：请参阅 [Qualys SSL Labs](https://www.ssllabs.com/ssltest/index.html) 进行审核
-领域：IE9 +，Safari 9+

```js
//量化总连接时间
var pageNav = performance.getEntriesByType（“ navigation”）[0];
var connectionTime = pageNav.connectEnd-pageNav.connectStart;
 var tlsTime = 0;  // &lt;-默认为0

//是否发生了TLS错误？
如果（pageNav.secureConnectionStart&gt; 0）{
   //太棒了！  计算吧！
  tlsTime = pageNav.connectEnd-pageNav.secureConnectionStart;
}
```

### Time to First Byte (TTFB)

-实验室：大多数服务器负载测试工具都会报告此问题
-领域：IE9 +，Safari 9+

```js
var ttfb = pageNav.responseStart-pageNav.requestStart;
```

### Transferred bytes

 您可以使用多种工具来测量资产的字节权重.  通常，您只能跟踪这些实验室，因为字段中的编号通常是相同的（但要注意设备类型或地理位置特定的页面）.

测量自己的（和第三方）JavaScript字节至关重要，因为JavaScript是导致高字节数的主要原因 [TTI](#time-to-interactive-tti) 要么 [FID](#first-input-delay-fid) 价值观.

-实验室：灯塔（预算），Sitespeed.io，自定义工具
-字段：不适用-但数字通常与实验室相同
- [Sitespeed.io PageXray](https://www.sitespeed.io/documentation/pagexray/)
- [Lighthouse Performance Budgets](https://developers.google.com/web/tools/lighthouse/audits/budgets)
- [Can You Afford It?: Real-world Web Performance Budgets](https://infrequently.org/2017/10/can-you-afford-it-real-world-web-performance-budgets/)
- [Which third party scripts are most excessive](https://github.com/patrickhulce/third-party-web)

---

## Other metrics

### Google PageSpeed Insights score

- [About PageSpeed Insights](https://developers.google.com/speed/docs/insights/v5/about)
- [What's in the Google PageSpeed score](https://medium.com/expedia-group-tech/whats-in-the-google-pagespeed-score-a5fc93f91e91)
- [How Google Pagespeed works](https://calibreapp.com/blog/how-pagespeed-works/)


### User Timing

 使用用户计时API，开发人员可以创建特定于应用程序的时间戳，这些时间戳是浏览器性能时间表的一部分.  例如，您可以创建一个用户计时标记，以测量页面上特定组件的JS加载时间.

-实验室：WPT灯塔
-领域：IE 10 +，Safari 11+（当然还有Chrome，Firefox）
- [Spec - User Timing](https://www.w3.org/TR/user-timing/)

### Server Timing

在用户浏览器或PerformanceServerTiming界面中的开发人员工具中显示任何后端服务器计时指标（例如，数据库延迟等）.

- [Docs - Server Timing](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Server-Timing)


### Frame rate

  帧频是“浏览器可以显示帧的频率”.  一帧表示浏览器在一个事件循环迭代中所做的工作量，例如处理DOM事件，调整大小，滚动，渲染，CSS动画等.60fps（每秒帧数）的帧速率是一个好的目标.快速响应的用户体验.  这意味着浏览器应在大约16.7毫秒内处理一个帧.

-实验室：Chrome和FF Devtools
-字段：还没有浏览器实现Frame Timing API，但是您可以使用`requestAnimationFrame`滚动自己的fps计量器
- [Docs - Frame Timing API](https://developer.mozilla.org/en-US/docs/Web/API/Frame_Timing_API)
- [Docs - Chrome Devtools - FPS](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/#analyze_frames_per_second)
- [Docs - Firefox Developer Tools - Frame rate](https://developer.mozilla.org/en-US/docs/Tools/Performance/Frame_rate)


- [Docs - `DOMContentLoaded`](https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded)

### window.load

- [Docs - `window.load`](https://developer.mozilla.org/en-US/docs/Web/Events/load)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，Csaba Palfi放弃了该作品的所有版权以及相关或邻近的权利.
