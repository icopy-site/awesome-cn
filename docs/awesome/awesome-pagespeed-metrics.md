<div class="github-widget" data-repo="csabapalfi/awesome-pagespeed-metrics"></div>
## Awesome Page Speed Metrics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Metrics to help understand page speed and user experience.

If you're just getting started check out [web.dev/metrics](https://web.dev/metrics/) first.


<!-- toc -->


<!-- tocstop -->

## Concepts

### Lab Data (Synthetic Measurements)

Make a request to your page with a tool and evaluate performance. Be sure to make it realistic (e.g. by throttling network and CPU) and reduce noise (e.g. by running multiple times).

- [Lighthouse](https://developers.google.com/web/tools/lighthouse/) - A tool built on Google Chrome to audit web pages. You can run it from Chrome DevTools, a Chrome Extension or from the command line (even with headless Chrome).
- [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Free and hosted Lighthouse reporting (and more) by Google.
- [WebpageTest](https://www.webpagetest.org/) - Free and hosted web performance testing (also an open source project).
- [Sitespeed.io](https://www.sitespeed.io/) - A set of open source performance monitoring tools.
- [Calibre](https://calibreapp.com) - Web performance monitoring SaaS.
- [treo.sh](https://treo.sh/) - Web performance monitoring SaaS.
- [SpeedCurve](https://speedcurve.com/) - Web performance monitoring SaaS.
- [AwesomeTechStack](https://awesometechstack.com/) - Website awesomeness monitoring Tool.

---

### Field Data (Real User Monitoring - RUM)

Collect performance data from real users visiting your page. Be mindful of the actual overhead, as it runs in your user's browser and watch out for browser support of more recent metrics (e.g. compared to your user-base).

- [Performance tracking with Google Analytics (GA)](https://philipwalton.com/articles/the-google-analytics-setup-i-use-on-every-site-i-build/#performance-tracking)
- [Chrome User Experience Report (CrUX)](https://developers.google.com/web/tools/chrome-user-experience-report/)
- [Load abandonment](https://developers.google.com/web/updates/2017/06/user-centric-performance-metrics#load_abandonment) - Track  `visibilitychange` to account for survivorship bias.
- [SpeedCurve LUX](https://speedcurve.com/features/lux/) - Real User Monitoring SaaS.
- [Akamai mPulse](https://www.akamai.com/uk/en/products/performance/mpulse-real-user-monitoring.jsp) - Real User Monitoring SaaS.
- [Sematext Experience](https://sematext.com/experience/) - Real User Monitoring SaaS.
- [Perfume.js](https://zizzamia.github.io/perfume/) - Open Source Library to collect Field Data.
- [Web Vitals](https://github.com/GoogleChrome/web-vitals) - Open Source Library to collect Field Data.
- [Vercel Analytics](https://vercel.com/docs/analytics) - Real User Monitoring based on Web Vitals.

### Critical rendering path

The critical rendering path is **everything that happens between receiving network bytes and rendering something on the screen**. To optimize any rendering metrics like [First Contentful Paint (FCP)](#first-contentful-paint-fcp) or [Speed Index](#speed-index) you have to understand how the critical rendering path works.

- [Critical rendering path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/)

### Long tasks

The browser Main Thread that handles user input is also the one executing JavaScript (among many other things). Blocking the Main Thread for too long can make your page unresponsive.

A user perceives any visual change within 100ms as instant. Any task blocking the Main Thread by **taking longer than 50ms is considered a long task** (as it might make the browser unresponsive to user input).

To optimize interactivity metrics like [Total Blocking Time (TBT)](#total-blocking-time-tbt) and [First Input Delay (FID)](#first-input-delay-fid) you have to understand long tasks and how to avoid them as much as possible.

- [Spec - Long Tasks](https://w3c.github.io/longtasks/)
- [Blogpost - Tracking CPU with Long Tasks API](https://calendar.perfplanet.com/2017/tracking-cpu-with-long-tasks-api/)

### User-centric metrics

It's important to track metrics relevant to users and their experience. To measure the perceived performance we can choose metrics by framing them around a few key questions.

- [Docs - User-centric Performance Metrics - web.dev](https://web.dev/user-centric-performance-metrics/)
- Is it happening? - Did the navigation start successfully? Has the server responded? (e.g [FCP](https://github.com/csabapalfi/awesome-web-performance-metrics/#first-contentful-paint-fcp))
- Is it useful/meaningful? - Has enough content rendered that users can engage with it? (e.g. [LCP](https://github.com/csabapalfi/awesome-web-performance-metrics/#largest-contentful-paint-lcp))
- Is it usable - Can users interact with the page, or is it still busy loading? (e.g [TBT](https://github.com/csabapalfi/awesome-web-performance-metrics/#total-blocking-time-tbt))
- Is it delightful/smooth? - Are the interactions smooth and natural, free of lag and jank?

---

## Rendering metrics


The First Contentful Paint (FCP) metric measures the time from when the page starts loading to when any part of the page's content is rendered on the screen. For this metric, "content" refers to text, images (including background images), `<svg>` elements, or non-white `<canvas>` elements.

- Lab: Lighthouse
- Field: Chrome 60+, CrUX
- [Docs - FCP - web.dev](https://web.dev/fcp/)
- [Spec - Paint Timing - W3C](https://w3c.github.io/paint-timing/)


The Largest Contentful Paint (LCP) metric reports the render time of the largest content element visible within the viewport.

- Lab: Lighthouse/WPT
- Field: Chrome 77+
- [Docs - LCP - web.dev](https://web.dev/largest-contentful-paint/)
- [Spec - LCP - W3C](https://github.com/WICG/largest-contentful-paint#readme)

### Cumulative Layout Shift (CLS)

 A layout shift occurs any time a visible element changes its position from one frame to the next. CLS measures the sum total of all individual layout shift scores for every unexpected layout shift that occurs during the entire lifespan of the page.

- Lab: Lighthouse/WPT
- Field: Chrome 77+
- [Docs - CLS - web.dev](https://web.dev/cls/)
- [Spec - Layout Instability API - W3C](https://github.com/WICG/layout-instability)

### Visually Complete

The Visually Complete is the time from the start of the initial navigation until the **visible (above the fold) part of your page is no longer changing**. (e.g. WPT measures this using a color histogram of the page based on video/screenshots recording).

- Lab: WPT
- Field: N/A
- [Docs - Visually Complete - WPT](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)

### Speed Index

Speed Index shows **how quickly the contents of a page are visibly populated** (lower numbers are better). This is done by frequently measuring visual completeness during loading. The quicker the page is more visually complete the lower the value.

- Lab: Lighthouse, WPT (but slightly different spec)
- Field: N/A
- [Docs - Speed Index - web.dev](https://web.dev/speed-index/)
- [Docs - Speed Index - WPT](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)
- [Talk - Speed Perception and Lighthouse](https://ldnwebperf.org/sessions/speed-perception-and-lighthouse/)

### (Hero) Element Timing

Element Timing captures **when specific elements are painted** by the browser. Hero elements can be defined as the largest h1, img or background image (or custom ones using the Element Timing API)

- Lab: WPT
- Field: Chrome 77+
- [Docs - Last Painted Hero - WPT](https://github.com/WPO-Foundation/webpagetest/blob/master/docs/Metrics/HeroElements.md)
- [Spec - Element Timing API](https://wicg.github.io/element-timing/)
- [Blogpost - Hero Element Timing - SpeedCurve](https://speedcurve.com/blog/web-performance-monitoring-hero-times/)

---

## Interactivity metrics

### Time to Interactive (TTI)

Time to interactive is **the time it takes for the page to become fully interactive** (as in Main Thread quiet for 5s). Sometimes called Consistently Interactice and not to be confused with First Interactive or First CPU Idle. (Warning: one of the most confusing and misunderstood metrics).

- Lab: Lighthouse, WPT
- Field: Not recommended as users interacting with your page can skew field measurements of TTI
- [Docs - TTI - web.dev](https://web.dev/tti/)
- [Spec - TTI - Lighthouse](https://docs.google.com/document/d/1GGiI9-7KeY3TPqS3YT271upUVimo-XiL5mwWorDUD4c/edit)
- [Blogpost - TTI](https://blog.dareboost.com/en/2019/05/measuring-interactivity-time-to-interactive/)

### Total Blocking Time (TBT)

The Total Blocking Time (TBT) metric measures the total amount of time between First Contentful Paint (FCP) and Time to Interactive (TTI) where the main thread was blocked for long enough to prevent input responsiveness.

- Lab: Lighthouse
- Field: N/A
- [Docs - TBT - web.dev](https://web.dev/tbt/)

### First Input Delay (FID)

First Input Delay (FID) measures **the time from when a user first interacts with your site to the time when the browser is actually able to respond** to that interaction. An interaction can be when users click a link, tap on a button, or use a custom, JavaScript-powered control.

- Lab: N/A (as it requires the user to interact with the page)
- Field: IE9+ (and Safari, Chrome, Firefox) (with polyfill - 0.4KB)
- [Docs - FID - web.dev](https://web.dev/fid/)
- [Polyfill - FID](https://github.com/GoogleChromeLabs/first-input-delay)

### Max Potential First Input Delay

The maximum potential [First Input Delay](#first-input-delay-fid) that your users could experience. Basically equals to the duration of the longest [long task](#long-tasks) on the browser Main Thread.

- Lab: Lighthouse
- Field: N/A
- [Docs - Max Potential FID - web.dev](https://web.dev/lighthouse-max-potential-fid/)

---

## Network metrics

Network timing field data can uncover a non-optimized TLS setup, slow DNS lookups or server side processing and issues with CDN configuration. See also a separate section about measuring [transferred bytes](#transferred-bytes).

- [Blogpost - Navigation and Resource Timing](https://developers.google.com/web/fundamentals/performance/navigation-and-resource-timing/)
- [Spec - Navigation Timing](https://www.w3.org/TR/navigation-timing-2/)
- [Spec - Resource Timing](https://www.w3.org/TR/resource-timing-2/)

### DNS latency

- Lab: DNS performance testing tools
- Field: IE9+, Safari 9+

```js
// Measuring DNS lookup time
var pageNav = performance.getEntriesByType("navigation")[0];
var dnsTime = pageNav.domainLookupEnd - pageNav.domainLookupStart;
```

### TCP and SSL/TLS latency

- Lab: See [Qualys SSL Labs](https://www.ssllabs.com/ssltest/index.html) for an audit
- Field: IE9+, Safari 9+

```js
// Quantifying total connection time
var pageNav = performance.getEntriesByType("navigation")[0];
var connectionTime = pageNav.connectEnd - pageNav.connectStart;
var tlsTime = 0; // <-- Assume 0 by default

// Did any TLS stuff happen?
if (pageNav.secureConnectionStart > 0) {
  // Awesome! Calculate it!
  tlsTime = pageNav.connectEnd - pageNav.secureConnectionStart;
}
```

### Time to First Byte (TTFB)

- Lab: most server load testing tools report this
- Field: IE9+, Safari 9+

```js
var ttfb = pageNav.responseStart - pageNav.requestStart;
```

### Transferred bytes

You can measure the byte weight of your assets with a number of tools. You would normally track these Lab only as the numbers are usually the same in the Field (but be mindful of device type or geographical location specific pages).

Measuring own (and third-party) JavaScript bytes is crucial as JavaScript is the main cause of high [TTI](#time-to-interactive-tti) or [FID](#first-input-delay-fid) values.

- Lab: Lighthouse (budgets), Sitespeed.io, custom tools
- Field: N/A - but numbers usually the same as in Lab
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

The User Timing API allows the developer to create application specific timestamps that are part of the browser's performance timeline. e.g. you can create a user timing mark to measure when your JS has loaded for a specific component on the page.

- Lab: Lighthouse, WPT
- Field: IE 10+, Safari 11+ (and Chrome, Firefox of course)
- [Spec - User Timing](https://www.w3.org/TR/user-timing/)

### Server Timing

Surface any backend server timing metrics (e.g. database latency, etc.) in the developer tools in the user's browser or in the PerformanceServerTiming interface.

- [Docs - Server Timing](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Server-Timing)

### Frame rate

 The frame rate is the **frequency at which the browser can display frames**. A frame represents the amount of work a browser does in one event loop iteration such as processing DOM events, resizing, scrolling, rendering, CSS animations, etc. A frame rate of 60 fps (frames per second) is a common target for a good responsive user experience. This means the browser should process a frame in about 16.7 ms.

- Lab: Chrome and FF Devtools
- Field: No browser implements the Frame Timing API yet but you can roll your own fps meter using `requestAnimationFrame`
- [Docs - Frame Timing API](https://developer.mozilla.org/en-US/docs/Web/API/Frame_Timing_API)
- [Docs - Chrome Devtools - FPS](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/#analyze_frames_per_second)
- [Docs - Firefox Developer Tools - Frame rate](https://developer.mozilla.org/en-US/docs/Tools/Performance/Frame_rate)


- [Docs - `DOMContentLoaded`](https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded)

### window.load

- [Docs - `window.load`](https://developer.mozilla.org/en-US/docs/Web/Events/load)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Csaba Palfi has waived all copyright and related or neighboring rights to this work.
