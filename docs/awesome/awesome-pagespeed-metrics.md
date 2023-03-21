<div class="github-widget" data-repo="csabapalfi/awesome-pagespeed-metrics"></div>
## Awesome Page Speed Metrics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; 有助于了解页面速度和用户体验的指标.

If you're just getting started check out [web.dev/metrics](https://web.dev/metrics/) 第一的.


<!-- toc -->


<!-- tocstop -->

## Concepts

### Lab Data (Synthetic Measurements)

使用工具向您的页面发出请求并评估性能. 务必使其符合实际（例如通过限制网络和 CPU）并减少噪音（例如通过多次运行）.

- [Lighthouse](https://developers.google.com/web/tools/lighthouse/)  - 基于 Google Chrome 构建的用于审核网页的工具. 您可以从 Chrome DevTools、Chrome 扩展程序或命令行（即使是无头 Chrome）运行它.
- [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Google 提供的免费托管 Lighthouse 报告（以及更多）.
- [WebpageTest](https://www.webpagetest.org/) - 免费和托管的网络性能测试（也是一个开源项目）.
- [Sitespeed.io](https://www.sitespeed.io/) - 一套开源性能监控工具.
- [Calibre](https://calibreapp.com) - Web 性能监控 SaaS.
- [treo.sh](https://treo.sh/) - Web 性能监控 SaaS.
- [SpeedCurve](https://speedcurve.com/) - Web 性能监控 SaaS.
- [AwesomeTechStack](https://awesometechstack.com/) - 网站敬畏监控工具.

---

### Field Data (Real User Monitoring - RUM)

从访问您页面的真实用户那里收集性能数据. 请注意实际开销，因为它在您用户的浏览器中运行，并注意浏览器对更新指标的支持（例如，与您的用户群相比）.

- [Performance tracking with Google Analytics (GA)](https://philipwalton.com/articles/the-google-analytics-setup-i-use-on-every-site-i-build/#performance-tracking)
- [Chrome User Experience Report (CrUX)](https://developers.google.com/web/tools/chrome-user-experience-report/)
- [Load abandonment](https://developers.google.com/web/updates/2017/06/user-centric-performance-metrics#load_abandonment) - 跟踪“visibilitychange”以解决幸存者偏差.
- [SpeedCurve LUX](https://speedcurve.com/features/lux/) - 真实用户监控 SaaS.
- [Akamai mPulse](https://www.akamai.com/uk/en/products/performance/mpulse-real-user-monitoring.jsp) - 真实用户监控 SaaS.
- [Sematext Experience](https://sematext.com/experience/) - 真实用户监控 SaaS.
- [Perfume.js](https://zizzamia.github.io/perfume/) - 开源库以收集现场数据.
- [Web Vitals](https://github.com/GoogleChrome/web-vitals) - 开源库以收集现场数据.
- [Vercel Analytics](https://vercel.com/docs/analytics) - 基于 Web Vitals 的真实用户监控.

### Critical rendering path

关键渲染路径是**接收网络字节和在屏幕上渲染某些东西之间发生的一切**. 优化任何渲染指标，例如 [First Contentful Paint (FCP)](#first-contentful-paint-fcp) 或者 [Speed Index](#speed-index) you have to understand how the critical rendering path w或者ks.

- [Critical rendering path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/)

### Long tasks

处理用户输入的浏览器主线程也是执行 JavaScript 的线程（以及许多其他内容）. 阻塞主线程时间过长会使您的页面无响应.

用户认为 100 毫秒内的任何视觉变化都是即时的. 任何阻塞主线程的任务**花费超过 50 毫秒都被认为是一项长任务**（因为它可能使浏览器对用户输入无响应）.

优化交互指标，例如 [Total Blocking Time (TBT)](#total-blocking-time-tbt) 和 [First Input Delay (FID)](#first-input-delay-fid) you have to underst和 long tasks 和 how to avoid them as much as possible.

- [Spec - Long Tasks](https://w3c.github.io/longtasks/)
- [Blogpost - Tracking CPU with Long Tasks API](https://calendar.perfplanet.com/2017/tracking-cpu-with-long-tasks-api/)

### User-centric metrics

跟踪与用户及其体验相关的指标非常重要. 为了衡量感知性能，我们可以通过围绕几个关键问题构建指标来选择指标.

- [Docs - User-centric Performance Metrics - web.dev](https://web.dev/user-centric-performance-metrics/)
 - 它正在发生吗？  - 导航是否启动成功？ 服务器响应了吗？  （例如 [FCP](https://github.com/csabapalfi/awesome-web-performance-metrics/#first-contentful-paint-fcp))
 - 它有用/有意义吗？  - 呈现的内容是否足以让用户参与其中？  （例如 [LCP](https://github.com/csabapalfi/awesome-web-performance-metrics/#largest-contentful-paint-lcp))
 - 它是否可用 - 用户是否可以与页面交互，或者它是否仍在忙于加载？  （例如 [TBT](https://github.com/csabapalfi/awesome-web-performance-metrics/#total-blocking-time-tbt))
 - 它令人愉快/流畅吗？  - 交互是否顺畅自然，没有滞后和卡顿？

---

## Rendering metrics


 First Contentful Paint (FCP) 指标测量从页面开始加载到页面内容的任何部分呈现在屏幕上的时间. 对于此指标，“内容”是指文本、图像（包括背景图像）、`<svg>  ` 元素，或非白色 `<canvas>  ` 元素.

- 实验室：灯塔
- 领域：Chrome 60+，CrUX
- [Docs - FCP - web.dev](https://web.dev/fcp/)
- [Spec - Paint Timing - W3C](https://w3c.github.io/paint-timing/)


Largest Contentful Paint (LCP) 指标报告视口内可见的最大内容元素的呈现时间.

- 实验室：Lighthouse/WPT
- 领域：Chrome 77+
- [Docs - LCP - web.dev](https://web.dev/largest-contentful-paint/)
- [Spec - LCP - W3C](https://github.com/WICG/largest-contentful-paint#readme)

### Cumulative Layout Shift (CLS)

 每当可见元素将其位置从一帧更改到下一帧时，就会发生布局偏移.  CLS 衡量页面整个生命周期内发生的每个意外布局偏移的所有单独布局偏移分数的总和.

- 实验室：Lighthouse/WPT
- 领域：Chrome 77+
- [Docs - CLS - web.dev](https://web.dev/cls/)
- [Spec - Layout Instability API - W3C](https://github.com/WICG/layout-instability)

### Visually Complete

视觉上的完整时间是指从初始导航开始到页面的**可见（首屏）部分不再发生变化**的时间.  （例如，WPT 使用基于视频/屏幕截图记录的页面颜色直方图来衡量这一点）.

- 实验室：WPT
- 领域：不适用
- [Docs - Visually Complete - WPT](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)

### Speed Index

 Speed Index 显示**页面内容明显填充的速度**（数字越低越好）. 这是通过在加载过程中经常测量视觉完整性来完成的. 页面越快视觉上越完整，价值越低.

- 实验室：Lighthouse、WPT（但规格略有不同）
- 领域：不适用
- [Docs - Speed Index - web.dev](https://web.dev/speed-index/)
- [Docs - Speed Index - WPT](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)
- [Talk - Speed Perception and Lighthouse](https://ldnwebperf.org/sessions/speed-perception-and-lighthouse/)

### (Hero) Element Timing

 Element Timing 捕获**特定元素何时被浏览器绘制**. 英雄元素可以定义为最大的 h1、img 或背景图像（或使用 Element Timing API 自定义的）

- 实验室：WPT
- 领域：Chrome 77+
- [Docs - Last Painted Hero - WPT](https://github.com/WPO-Foundation/webpagetest/blob/master/docs/Metrics/HeroElements.md)
- [Spec - Element Timing API](https://wicg.github.io/element-timing/)
- [Blogpost - Hero Element Timing - SpeedCurve](https://speedcurve.com/blog/web-performance-monitoring-hero-times/)

---

## Interactivity metrics

### Time to Interactive (TTI)

交互时间是**页面完全交互所需的时间**（如主线程安静 5 秒）. 有时称为一致交互，不要与首次交互或首次 CPU 空闲混淆.  （警告：最令人困惑和误解的指标之一）.

- 实验室：Lighthouse、WPT
- 现场：不推荐，因为与您的页面交互的用户可能会扭曲 TTI 的现场测量
- [Docs - TTI - web.dev](https://web.dev/tti/)
- [Spec - TTI - Lighthouse](https://docs.google.com/document/d/1GGiI9-7KeY3TPqS3YT271upUVimo-XiL5mwWorDUD4c/edit)
- [Blogpost - TTI](https://blog.dareboost.com/en/2019/05/measuring-interactivity-time-to-interactive/)

### Total Blocking Time (TBT)

Total Blocking Time (TBT) 度量标准测量 First Contentful Paint (FCP) 和 Time to Interactive (TTI) 之间的总时间量，其中主线程被阻塞的时间足够长以防止输入响应.

- 实验室：灯塔
- 领域：不适用
- [Docs - TBT - web.dev](https://web.dev/tbt/)

### First Input Delay (FID)

首次输入延迟 (FID) 衡量**从用户首次与您的网站交互到浏览器实际能够响应**该交互的时间. 交互可以是用户单击链接、点击按钮或使用自定义的 JavaScript 驱动的控件.

- 实验室：N/A（因为它需要用户与页面交互）
- 领域：IE9+（和 Safari、Chrome、Firefox）（带 polyfill - 0.4KB）
- [Docs - FID - web.dev](https://web.dev/fid/)
- [Polyfill - FID](https://github.com/GoogleChromeLabs/first-input-delay)

### Max Potential First Input Delay

最大潜力 [First Input Delay](#first-input-delay-fid) 您的用户可以体验到. 基本上等于最长的持续时间 [long task](#long-tasks) 在浏览器主线程上.

- 实验室：灯塔
- 领域：不适用
- [Docs - Max Potential FID - web.dev](https://web.dev/lighthouse-max-potential-fid/)

---

## Network metrics

网络时序字段数据可以揭示未优化的 TLS 设置、缓慢的 DNS 查找或服务器端处理以及 CDN 配置问题. 另请参阅有关测量的单独部分 [transferred bytes](#transferred-bytes).

- [Blogpost - Navigation and Resource Timing](https://developers.google.com/web/fundamentals/performance/navigation-and-resource-timing/)
- [Spec - Navigation Timing](https://www.w3.org/TR/navigation-timing-2/)
- [Spec - Resource Timing](https://www.w3.org/TR/resource-timing-2/)

### DNS latency

- 实验室：DNS 性能测试工具
- 领域：IE9+，Safari 9+

```js
// 测量 DNS 查找时间
var pageNav = performance.getEntriesByType(&quot;导航&quot;)[0];
var dnsTime = pageNav.domainLookupEnd - pageNav.domainLookupStart;
```

### TCP and SSL/TLS latency

- 实验室：见 [Qualys SSL Labs](https://www.ssllabs.com/ssltest/index.html) 审计
- 领域：IE9+，Safari 9+

```js
// 量化总连接时间
var pageNav = performance.getEntriesByType(&quot;导航&quot;)[0];
var connectionTime = pageNav.connectEnd - pageNav.connectStart;
 var tlsTime = 0;  // &lt;-- 默认假设为 0

// 是否发生了任何 TLS 事件？
如果（pageNav.secureConnectionStart &gt; 0）{
   // 惊人的！ 计算一下！
  tlsTime = pageNav.connectEnd - pageNav.secureConnectionStart;
}
```

### Time to First Byte (TTFB)

- 实验室：大多数服务器负载测试工具都报告了这一点
- 领域：IE9+，Safari 9+

```js
var ttfb = pageNav.responseStart - pageNav.requestStart;
```

### Transferred bytes

您可以使用多种工具测量资产的字节重量. 您通常只会跟踪这些实验室，因为现场的数字通常相同（但请注意设备类型或地理位置特定页面）.

测量自己（和第三方）的 JavaScript 字节是至关重要的，因为 JavaScript 是高 [TTI](#time-to-interactive-tti) 或者 [FID](#first-input-delay-fid) 值.

- 实验室：Lighthouse（预算）、Sitespeed.io、自定义工具
- 字段：N/A - 但数字通常与实验室中的数字相同
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

 User Timing API 允许开发人员创建特定于应用程序的时间戳，这些时间戳是浏览器性能时间线的一部分. 例如，您可以创建一个用户计时标记来测量您的 JS 何时为页面上的特定组件加载.

- 实验室：Lighthouse、WPT
- 领域：IE 10+、Safari 11+（当然还有 Chrome、Firefox）
- [Spec - User Timing](https://www.w3.org/TR/user-timing/)

### Server Timing

在用户浏览器的开发人员工具或 PerformanceServerTiming 界面中显示任何后端服务器计时指标（例如数据库延迟等）.

- [Docs - Server Timing](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Server-Timing)


### Frame rate

 帧率是**浏览器可以显示帧的频率**. 一帧表示浏览器在一个事件循环迭代中所做的工作量，例如处理 DOM 事件、调整大小、滚动、渲染、CSS 动画等.60 fps（每秒帧数）的帧速率是一个好的目标的常见目标响应式用户体验. 这意味着浏览器应该在大约 16.7 毫秒内处理一个帧.

- 实验室：Chrome 和 FF Devtools
- Field：还没有浏览器实现 Frame Timing API，但您可以使用 `requestAnimationFrame` 滚动您自己的 fps 计
- [Docs - Frame Timing API](https://developer.mozilla.org/en-US/docs/Web/API/Frame_Timing_API)
- [Docs - Chrome Devtools - FPS](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/#analyze_frames_per_second)
- [Docs - Firefox Developer Tools - Frame rate](https://developer.mozilla.org/en-US/docs/Tools/Performance/Frame_rate)


- [Docs - `DOMContentLoaded`](https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded)

### window.load

- [Docs - `window.load`](https://developer.mozilla.org/en-US/docs/Web/Events/load)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，Csaba Palfi 已放弃对本作品的所有版权和相关或邻接权.
