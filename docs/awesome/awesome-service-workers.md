<div class="github-widget" data-repo="TalAter/awesome-service-workers"></div>
## Awesome Service Workers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Service Worker 资源的精选集合.

<a href="https://pwabook.com/oreillyasw"><img align="right" src="https://raw.githubusercontent.com/TalAter/awesome-progressive-web-apps/raw/master/images/mpwa.png" alt="Building Progressive Web Apps"></a>
 &gt;Service Workers 是每个渐进式 Web 应用程序的核心. 它们的持久性使渐进式网络应用程序能够满足我们对应用程序应该做什么的期望. 它们是只有本机应用程序可以做的事情和现代渐进式网络应用程序可以做的事情之间缺失的联系.
>
> -- <cite>[Building Progressive Web Apps - O'Reilly](https://pwabook.com/oreillyasw)</cite>

如果你想贡献，请阅读 [contribution guidelines](https://github.com/TalAter/awesome-service-workers/blob/master/contributing.md).



## Must Reads

- [Building Progressive Web Apps - O'Reilly](https://pwabook.com/oreillyasw)  - 服务工作者、缓存策略、推送通知等的实践指南和参考. 构建现代渐进式 Web 应用程序所需的一切.
- [Introduction to Service Worker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/) - 对服务人员的温和介绍.
- [Offline Web Applications Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899) - 一个很棒的 Udacity 课程，介绍服务人员和 IndexedDB.
- [Service Workers Explained](https://github.com/slightlyoff/ServiceWorker/blob/master/explainer.md) - 服务人员解释 [Alex Russell](https://github.com/slightlyoff).

## Learning Resources

- [Building Offline Sites with ServiceWorkers and UpUp](https://dev.opera.com/articles/offline-with-upup-service-workers/) - 服务工作者的一般介绍和使用 UpUp 在几分钟内提供离线功能.
- [Introduction to Service Worker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/)
- [Service Workers 101](https://github.com/delapuente/service-workers-101) - 总结服务工作者 API 最重要部分的信息图.
- [ServiceWorker Cookbook by Mozilla](https://serviceworke.rs/) - 不同用例的食谱集合.
- [The copy & paste guide to your first Service Worker](https://remysharp.com/2016/03/22/the-copy--paste-guide-to-your-first-service-worker) - 最短的可用介绍，由 [Remy Sharp](https://github.com/remy).
- [The offline cookbook](https://jakearchibald.com/2014/offline-cookbook/) - Jake Archibald 的服务工作者模式圣经.
- [Designing Offline-First Web Apps](http://alistapart.com/article/offline-first) - 对处理各种连接状态的设计和 UX 考虑的引人入胜的看法.

## Reference

- [Background Sync Spec](https://wicg.github.io/BackgroundSync/spec/) - 后台同步的 WIP 规范.
- [Service Workers - W3C Specification](https://www.w3.org/TR/service-workers/) - 官方服务人员规范.

## Browser Support

- [Can I Use - Service Workers](http://caniuse.com/#feat=serviceworkers) - 最新的 ServiceWorker API 浏览器支持表.
- [Jake Archibald - Is Service Worker ready?](https://jakearchibald.github.io/isserviceworkerready/) - 不同浏览器对 ServiceWorker 支持的当前状态.

## Libraries and Tools

- [UpUp](http://upup.rocks/) - 一个流行的 Service Worker 库，只需一行代码即可为您的站点提供完整的离线功能.
- [sw-toolbox](https://github.com/GoogleChrome/sw-toolbox/) - 一组简单的帮助程序，用于简化常见运行时缓存模式的实现.
- [Manifest Generator](https://brucelawson.github.io/manifest/) - 生成推送通知和可安装网络应用程序所需的网络应用程序清单.
- [sw-precache](https://github.com/GoogleChrome/sw-precache/) - 生成一个服务工作者来缓存您的本地 App Shell 资源.
- [sw-offline-google-analytics](https://developers.google.com/web/updates/2016/07/offline-google-analytics) - 一个服务工作者帮助程序库，用于在连接可用时重试离线 Google Analytics 请求.
- [Workbox](https://developers.google.com/web/tools/workbox/) - 一组库和 Node 模块，可以轻松缓存资产并充分利用用于构建渐进式 Web 应用程序的功能.

## Videos

- [Instant Loading: Building offline-first Progressive Web Apps - Google I/O 2016](https://youtu.be/cmGr0RszHc8) - 快速了解用于构建渐进式 Web 应用程序的最常见技术和技巧.
- [Offline Web Applications Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899) - 如果您打算深入研究服务人员，那么这个免费的 Udacity 课程是必须的.
- [Instant Loading with Service Workers (Chrome Dev Summit 2015)](https://www.youtube.com/watch?v=jCKZDTtUA2A) - 解释如何构建您的网络应用程序以优化初始和返回访问者的加载时间，并涵盖有用的服务工作者库，这些库可以最大限度地减少您必须编写的样板代码的数量.

## Case Studies

- [Service Workers in Production](https://developers.google.com/web/showcase/case-study/service-workers-iowa) - 关于如何构建 Google I/O 2015 网络应用程序的案例研究.
- [Measuring the Real-world Performance Impact of Service Workers](https://developers.google.com/web/showcase/2016/service-worker-perf)  - service workers 最重要的好处之一（至少从性能的角度来看）是他们能够主动控制资产缓存. 一个可以缓存所有必要资源的 Web 应用程序对于返回访问者来说应该加载得更快. 但是对于真实用户来说，这些收益实际上是什么样子的呢？ 您甚至如何衡量这一点？

## Related Technologies

- [App Install Banners](https://github.com/TalAter/awesome-progressive-web-apps#installable-web-apps)
- [Background Sync](https://github.com/TalAter/awesome-progressive-web-apps#background-sync)
- [CacheStorage API](https://github.com/TalAter/awesome-progressive-web-apps#cachestorage-api)
- [IndexedDB](https://github.com/TalAter/awesome-progressive-web-apps#indexeddb)
- [Push Notifications](https://github.com/TalAter/awesome-progressive-web-apps#push-notifications)
