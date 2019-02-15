## Awesome Service Workers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated collection of service worker resources.

<a href="https://pwabook.com/oreillyasw"><img align="right" src="https://raw.githubusercontent.com/TalAter/awesome-progressive-web-apps/raw/master/images/mpwa.png" alt="Building Progressive Web Apps"></a>
>Service workers are at the heart of every progressive web app. Their persistent nature allows progressive web apps to fulfill our expectations of what an app should do. They are the missing link between what only native apps could do and what modern progressive web apps can do.
>
> -- <cite>[Building Progressive Web Apps - O'Reilly](https://pwabook.com/oreillyasw)</cite>

If you want to contribute, please read the [contribution guidelines](https://github.com/TalAter/awesome-service-workers/blob/master/contributing.md).

## Contents

- [Must Reads](#must-reads)
- [Learning Resources](#learning-resources)
- [Reference](#reference)
- [Browser Support](#browser-support)
- [Libraries and Tools](#libraries-and-tools)
- [Videos](#videos)
- [Case Studies](#case-studies)
- [Related Technologies](#related-technologies)

## Must Reads

- [Building Progressive Web Apps - O'Reilly](https://pwabook.com/oreillyasw) - A hands-on guide and reference for service workers, caching strategies, push notifications, and more. Everything you need to build a modern progressive web app.
- [Introduction to Service Worker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/) - A gentle introduction to service workers.
- [Offline Web Applications Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899) - A great Udacity course introducing service workers and IndexedDB.
- [Service Workers Explained](https://github.com/slightlyoff/ServiceWorker/blob/master/explainer.md) - Service workers explained by [Alex Russell](https://github.com/slightlyoff).

## Learning Resources

- [Building Offline Sites with ServiceWorkers and UpUp](https://dev.opera.com/articles/offline-with-upup-service-workers/) - A general introduction to service workers and using UpUp to provide offline functionality in minutes.
- [Introduction to Service Worker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/)
- [Service Workers 101](https://github.com/delapuente/service-workers-101) - An infographic summarizing the most important parts of service workers API.
- [ServiceWorker Cookbook by Mozilla](https://serviceworke.rs/) - A collection of recipes for different use cases.
- [The copy & paste guide to your first Service Worker](https://remysharp.com/2016/03/22/the-copy--paste-guide-to-your-first-service-worker) - Shortest available introduction, by [Remy Sharp](https://github.com/remy).
- [The offline cookbook](https://jakearchibald.com/2014/offline-cookbook/) - The bible of service worker Patterns by Jake Archibald.
- [Designing Offline-First Web Apps](http://alistapart.com/article/offline-first) - A fascinating look at design and UX considerations for dealing with various states of connectivity.

## Reference

- [Background Sync Spec](https://wicg.github.io/BackgroundSync/spec/) - The WIP spec for Background Sync.
- [Service Workers - W3C Specification](https://www.w3.org/TR/service-workers/) - The official service workers spec.

## Browser Support

- [Can I Use - Service Workers](http://caniuse.com/#feat=serviceworkers) - Up-to-date browser support table of ServiceWorker API.
- [Jake Archibald - Is Service Worker ready?](https://jakearchibald.github.io/isserviceworkerready/) - Current status of ServiceWorker support in different browsers.

## Libraries and Tools

- [UpUp](http://upup.rocks/) - A popular service worker library providing complete offline functionality for your site in 1 line of code.
- [sw-toolbox](https://github.com/GoogleChrome/sw-toolbox/) - A collection of simple helpers to simplify implementing common runtime caching patterns.
- [Manifest Generator](https://brucelawson.github.io/manifest/) - Generate a web app manifest, required for push notifications and installable web apps.
- [sw-precache](https://github.com/GoogleChrome/sw-precache/) - Generates a service worker to cache your local App Shell resources.
- [sw-offline-google-analytics](https://developers.google.com/web/updates/2016/07/offline-google-analytics) - A service worker helper library to retry offline Google Analytics requests when a connection is available.
- [Workbox](https://developers.google.com/web/tools/workbox/) - a set of libraries and Node modules that make it easy to cache assets and take full advantage of features used to build progressive web apps.

## Videos

- [Instant Loading: Building offline-first Progressive Web Apps - Google I/O 2016](https://youtu.be/cmGr0RszHc8) - A quick dive into the most common technologies and techniques for building progressive web apps.
- [Offline Web Applications Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899) - This free Udacity course is a must if you're planning to dive deep into service workers.
- [Instant Loading with Service Workers (Chrome Dev Summit 2015)](https://www.youtube.com/watch?v=jCKZDTtUA2A) - Explains how to structure your web app to optimize load time for initial and return visitors, and cover helpful service worker libraries that minimize the amount of boilerplate code you'll have to write.

## Case Studies

- [Service Workers in Production](https://developers.google.com/web/showcase/case-study/service-workers-iowa) - A case-study about how Google I/O 2015 web app was built.
- [Measuring the Real-world Performance Impact of Service Workers](https://developers.google.com/web/showcase/2016/service-worker-perf) - One of the most significant benefits of service workers (from a performance perspective, at least) is their ability to proactively control the caching of assets. A web application that can cache all of its necessary resources should load substantially faster for returning visitors. But what do these gains actually look like to real users? And how do you even measure this?

## Related Technologies

- [App Install Banners](https://github.com/TalAter/awesome-progressive-web-apps#installable-web-apps)
- [Background Sync](https://github.com/TalAter/awesome-progressive-web-apps#background-sync)
- [CacheStorage API](https://github.com/TalAter/awesome-progressive-web-apps#cachestorage-api)
- [IndexedDB](https://github.com/TalAter/awesome-progressive-web-apps#indexeddb)
- [Push Notifications](https://github.com/TalAter/awesome-progressive-web-apps#push-notifications)
