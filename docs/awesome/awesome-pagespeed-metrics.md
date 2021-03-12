<div class="github-widget" data-repo="csabapalfi/awesome-pagespeed-metrics"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Page Speed Metrics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt;有助于了解页面速度和用户体验的指标.

如果您刚刚开始，请查看 [web.dev/metrics](https://web.dev/metrics/) 第一的.


<!-- toc -->


<!-- tocstop -->

## Concepts

### Lab Data (Synthetic Measurements)

使用工具向您的页面提出请求并评估性能. 确保使其逼真（例如，通过节流网络和CPU）并减少噪音（例如，通过多次运行）.

- [Lighthouse](https://developers.google.com/web/tools/lighthouse/)  -建立在Google Chrome浏览器上的用于审核网页的工具. 您可以从Chrome DevTools，Chrome扩展程序或从命令行（即使是无头Chrome）运行它.
- [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) -由Google提供的免费托管的Lighthouse报告（以及更多）.
- [WebpageTest](https://www.webpagetest.org/) -免费和托管的Web性能测试（也是一个开源项目）.
- [Sitespeed.io](https://www.sitespeed.io/) -一组开源性能监视工具.
- [Calibre](https://calibreapp.com) -Web性能监控SaaS.
- [treo.sh](https://treo.sh/) -Web性能监控SaaS.
- [SpeedCurve](https://speedcurve.com/) -Web性能监控SaaS.
- [AwesomeTechStack](https://awesometechstack.com/) -网站性能监控工具.

---

### Field Data (Real User Monitoring - RUM)

从访问您页面的实际用户收集性能数据. 请注意实际开销，因为它会在您的用户浏览器中运行，并注意浏览器对最新指标的支持（例如，与您的用户群相比）.

- [Performance tracking with Google Analytics (GA)](https://philipwalton.com/articles/the-google-analytics-setup-i-use-on-every-site-i-build/#performance-tracking)
- [Chrome User Experience Report (CrUX)](https://developers.google.com/web/tools/chrome-user-experience-report/)
- [Load abandonment](https://developers.google.com/web/updates/2017/06/user-centric-performance-metrics#load_abandonment) -追踪“ visibilitychange”以解决生存偏差.
- [SpeedCurve LUX](https://speedcurve.com/features/lux/) -真实用户监控SaaS.
- [Akamai mPulse](https://www.akamai.com/uk/en/products/performance/mpulse-real-user-monitoring.jsp) -真实用户监控SaaS.
- [Sematext Experience](https://sematext.com/experience/) -真实用户监控SaaS.
- [Perfume.js](https://zizzamia.github.io/perfume/) -开源库来收集现场数据.
- [Web Vitals](https://github.com/GoogleChrome/web-vitals) -开源库来收集现场数据.
- [Vercel Analytics](https://vercel.com/docs/analytics) -基于Web Vitals的真实用户监控.

### Critical rendering path

关键的渲染路径是**在接收网络字节和在屏幕上渲染某些东西之间发生的一切**. 要优化任何渲染指标，例如 [First Contentful Paint (FCP)](#first-contentful-paint-fcp) 或者 [Speed Index](#speed-index) you have to understand how the critical rendering path w或者ks.

- [Critical rendering path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/)

### Long tasks

处理用户输入的浏览器主线程也是执行JavaScript的一个（在许多其他事物中）. 阻塞主线程的时间过长会使您的页面无响应.

用户可以将100ms内的任何视觉变化感知为即时变化. 任何通过“花费超过50毫秒”来阻塞主线程的任务都被认为是一项长任务（因为这可能会使浏览器对用户输入无响应）.

为了优化交互性指标，例如 [Total Blocking Time (TBT)](#total-blocking-time-tbt) 和 [First Input Delay (FID)](#first-input-delay-fid) you have to underst和 long tasks 和 how to avoid them as much as possible.

- [Spec - Long Tasks](https://w3c.github.io/longtasks/)
- [Blogpost - Tracking CPU with Long Tasks API](https://calendar.perfplanet.com/2017/tracking-cpu-with-long-tasks-api/)

### User-centric metrics

跟踪与用户及其体验相关的指标很重要. 为了衡量可感知的性能，我们可以通过围绕一些关键问题来选择指标来进行选择.

- [Docs - User-centric Performance Metrics - web.dev](https://web.dev/user-centric-performance-metrics/)
 -发生了吗？  -导航是否成功启动？ 服务器响应了吗？  （例如 [FCP](https://github.com/csabapalfi/awesome-web-performance-metrics/#first-contentful-paint-fcp))
 -有用/有意义吗？  -是否渲染了足够的内容以使用户可以参与其中？  （例如 [LCP](https://github.com/csabapalfi/awesome-web-performance-metrics/#largest-contentful-paint-lcp))
 -是否可用-用户可以与页面进行交互，还是仍在忙于加载？  （例如 [TBT](https://github.com/csabapalfi/awesome-web-performance-metrics/#total-blocking-time-tbt))
 -令人愉快/顺滑吗？  -交互是否顺畅自然，没有滞后和颠簸？

---

## Rendering metrics


 “第一个内容丰富的涂料（FCP）”度量标准衡量从页面开始加载到屏幕上呈现页面内容的任何部分的时间. 对于此指标，“内容”是指文本，图片（包括背景图片），<svg>  `元素，或非白色`<canvas>  `元素.

-实验室：灯塔
-领域：Chrome 60 +，CrUX
- [Docs - FCP - web.dev](https://web.dev/fcp/)
- [Spec - Paint Timing - W3C](https://w3c.github.io/paint-timing/)


最大内容绘画（LCP）度量标准报告视口中可见的最大内容元素的渲染时间.

-实验室：Lighthouse / WPT
-战场：Chrome 77+
- [Docs - LCP - web.dev](https://web.dev/largest-contentful-paint/)
- [Spec - LCP - W3C](https://github.com/WICG/largest-contentful-paint#readme)

### Cumulative Layout Shift (CLS)

 每当可见元素将其位置从一帧更改为下一帧时，都会发生布局偏移.  CLS会测量在页面整个生命周期中发生的每个意外的版式移位的所有单独版式移位分数的总和.

-实验室：Lighthouse / WPT
-战场：Chrome 77+
- [Docs - CLS - web.dev](https://web.dev/cls/)
- [Spec - Layout Instability API - W3C](https://github.com/WICG/layout-instability)

### Visually Complete

视觉上的完成是指从初始导航开始到页面的“可见（折页以上）”部分不再更改**之间的时间.  （例如，WPT使用基于视频/屏幕快照记录的页面颜色直方图对此进行测量）.

-实验室：WPT
-领域：不适用
- [Docs - Visually Complete - WPT](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)

### Speed Index

Speed Index shows **how quickly the contents of a page are visibly populated** (lower numbers are better). This is done by frequently measuring visual completeness during loading. The quicker the page is more visually complete the lower the value.

-实验室：WPT灯塔（但规格略有不同）
-领域：不适用
- [Docs - Speed Index - web.dev](https://web.dev/speed-index/)
- [Docs - Speed Index - WPT](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)
- [Talk - Speed Perception and Lighthouse](https://ldnwebperf.org/sessions/speed-perception-and-lighthouse/)

### (Hero) Element Timing

元素计时捕获**当特定元素被浏览器绘制时**. 英雄元素可以定义为最大的h1，img或背景图片（或使用Element Timing API定制的图片）

-实验室：WPT
-战场：Chrome 77+
- [Docs - Last Painted Hero - WPT](https://github.com/WPO-Foundation/webpagetest/blob/master/docs/Metrics/HeroElements.md)
- [Spec - Element Timing API](https://wicg.github.io/element-timing/)
- [Blogpost - Hero Element Timing - SpeedCurve](https://speedcurve.com/blog/web-performance-monitoring-hero-times/)

---

## Interactivity metrics

### Time to Interactive (TTI)

互动时间是**页面完全互动所花费的时间**（如在主线程中安静5秒钟）. 有时称为“持续交互”，不要与“第一交互式”或“第一CPU空闲”混淆.  （警告：最令人困惑和误解的指标之一）.

-实验室：WPT灯塔
-字段：不建议使用，因为与您的页面进行交互的用户可能会歪曲TTI的字段测量值
- [Docs - TTI - web.dev](https://web.dev/tti/)
- [Spec - TTI - Lighthouse](https://docs.google.com/document/d/1GGiI9-7KeY3TPqS3YT271upUVimo-XiL5mwWorDUD4c/edit)
- [Blogpost - TTI](https://blog.dareboost.com/en/2019/05/measuring-interactivity-time-to-interactive/)

### Total Blocking Time (TBT)

“总阻塞时间”（TBT）度量标准度量了“第一内容油漆（FCP）”和“交互时间”（TTI）之间的总时间，在该时间中，主线程被阻塞足够长的时间以防止输入响应.

-实验室：灯塔
-领域：不适用
- [Docs - TBT - web.dev](https://web.dev/tbt/)

### First Input Delay (FID)

首次输入延迟（FID）衡量的是**从用户首次与您的网站进行交互到浏览器实际上能够对该交互做出响应的时间**. 交互可以是用户单击链接，点击按钮或使用自定义的，基于JavaScript的控件.

-实验室：不适用（因为它要求用户与页面互动）
-栏位：IE9 +（以及Safari，Chrome，Firefox）（带有polyfill-0.4KB）
- [Docs - FID - web.dev](https://web.dev/fid/)
- [Polyfill - FID](https://github.com/GoogleChromeLabs/first-input-delay)

### Max Potential First Input Delay

最大潜力 [First Input Delay](#first-input-delay-fid) 您的用户可能会体验到的. 基本上等于最长的持续时间 [long task](#long-tasks) 在浏览器主线程上.

-实验室：灯塔
-领域：不适用
- [Docs - Max Potential FID - web.dev](https://web.dev/lighthouse-max-potential-fid/)

---

## Network metrics

网络计时字段数据可能会发现未优化的TLS设置，DNS查找缓慢或服务器端处理以及CDN配置问题. 另请参阅有关测量的单独部分 [transferred bytes](#transferred-bytes).

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

//是否发生了TLS漏洞？
如果（pageNav.secureConnectionStart&gt; 0）{
   // 惊人的！ 计算吧！
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

您可以使用多种工具来测量资产的字节权重. 通常，您只能跟踪这些实验室，因为字段中的数字通常是相同的（但要注意设备类型或地理位置特定的页面）.

测量自己的（和第三方）JavaScript字节至关重要，因为JavaScript是导致高字节数的主要原因 [TTI](#time-to-interactive-tti) 或者 [FID](#first-input-delay-fid) 价值观.

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

用户计时API允许开发人员创建特定于应用程序的时间戳，这些时间戳是浏览器性能时间表的一部分. 例如，您可以创建一个用户计时标记，以测量页面上特定组件加载JS的时间.

-实验室：WPT灯塔
-领域：IE 10以上版本，Safari 11以上版本（当然还有Chrome和Firefox）
- [Spec - User Timing](https://www.w3.org/TR/user-timing/)

### Server Timing

在用户浏览器或PerformanceServerTiming界面中的开发人员工具中显示任何后端服务器计时指标（例如，数据库延迟等）.

- [Docs - Server Timing](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Server-Timing)


### Frame rate

 帧速率是“浏览器可以显示帧的频率”. 一帧代表浏览器在一个事件循环迭代中所做的工作量，例如处理DOM事件，调整大小，滚动，渲染，CSS动画等.60fps（每秒帧）的帧速率是实现良好效果的常见目标快速响应的用户体验. 这意味着浏览器应在大约16.7毫秒内处理一个帧.

-实验室：Chrome和FF Devtools
-字段：尚无浏览器实现Frame Timing API，但您可以使用`requestAnimationFrame`滚动自己的fps计量器
- [Docs - Frame Timing API](https://developer.mozilla.org/en-US/docs/Web/API/Frame_Timing_API)
- [Docs - Chrome Devtools - FPS](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/#analyze_frames_per_second)
- [Docs - Firefox Developer Tools - Frame rate](https://developer.mozilla.org/en-US/docs/Tools/Performance/Frame_rate)


- [Docs - `DOMContentLoaded`](https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded)

### window.load

- [Docs - `window.load`](https://developer.mozilla.org/en-US/docs/Web/Events/load)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，Csaba Palfi放弃了该作品的所有版权以及相关或邻近的权利.
