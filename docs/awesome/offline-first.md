## Offline-First [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://img.shields.io/travis/pazguille/offline-first.svg)](https://travis-ci.org/pazguille/offline-first)

&gt;用于创建脱机优先Web应用程序的有用资源

 &gt;“网络”和“在线”是两个密切相关的术语，完全是许多人的同义词.  那么为什么我们会谈论“离线”网络技术，这个术语甚至意味着什么呢？

&gt;通过https://www.html5rocks.com/en/features/offline

灵感来自于 [awesome](https://github.com/sindresorhus/awesome) list thing.

## Table of Contents
- [W3C Specification](#w3c-specification)
- [Newsletter](#newsletter)
- [Posts](#posts)
- [Presentations](#presentations)
  - [Videos](#videos)
  - [Slides](#slides)
- [Tools](#tools)
- [Books](#books)
- [Showcase](#showcase)
- [Who to Follow](#who-to-follow)
- [Contributing](#contributing)

## W3C Specification

[Offline Web Applications](http://www.w3.org/TR/offline-webapps/)
&gt;此规范突出显示了HTML5中的功能（SQL，脱机应用程序缓存API以及在线/离线事件，状态和localStorage API），并提供了有关如何使用这些功能创建脱机工作的Web应用程序的简要教程.

[Service Workers](http://www.w3.org/TR/service-workers/)
&gt;此规范描述了一种方法，该方法使应用程序能够利用持久后台处理，包括在脱机时启用Web应用程序引导的挂钩.

[IndexedDB](http://www.w3.org/TR/IndexedDB/)
 &gt;此规范为包含简单值和分层对象的记录数据库定义API.  每条记录都包含一个键和一些值.  此外，数据库维护其存储的记录的索引.  应用程序开发人员直接使用API​​通过其键或使用索引来查找记录.  可以在此API上分层查询语言.  可以使用持久B树数据结构来实现索引数据库.

[WebStorage](http://www.w3.org/TR/webstorage/)
&gt;此规范定义了用于Web客户端中键值对数据的持久数据存储的API.

## Newsletter
[The Offline First Reader](http://offlinefirst.us4.list-manage1.com/subscribe?u=12d36bbe9418ed6a43127cd62&id=7fc00bfaef) .  每月一次的读者，其中包括离线优先，涵盖新离线用例的理论，技术和用户体验.

## Posts

[Accessibility Testing for Offline First Applications](https://medium.com/ibm-watson-data-lab/accessibility-testing-for-offline-first-applications-d8d2bfd24a6e)
（Maureen McElaney  -  2017年11月6日）

[How to add an “Offline” notification to your PWA](https://medium.com/@argo49/how-to-add-an-offline-notification-to-your-pwa-c11ee640822b)
（Tyler Argo  -  2017年10月28日）

[Building Offline-First App using MVVM, RxJava, Room and Priority Job Queue](https://proandroiddev.com/offline-apps-its-easier-than-you-think-9ff97701a73f)
（James Shvarts  -  2017年10月8日）

[Supporting Offline Users — What Happens When it Breaks?](https://medium.com/offline-camp/supporting-offline-users-what-happens-when-it-breaks-562f7dcea0a9)
（John Kleinschmidt  -  2017年9月27日）

[Using React and Preact to Build My First Offline First Apps](https://medium.com/offline-camp/using-react-and-preact-to-build-my-first-offline-first-apps-8df4a1e5471b)
（尼克卡斯滕 -  2017年9月5日）

[Offline-Friendly Forms](https://mxb.at/blog/offline-forms/)
（MaxBöck -  2017年8月23日）

[Service Worker: One fallback offline image for any aspect ratio](https://hackernoon.com/service-worker-one-fallback-offline-image-for-any-aspect-ratio-b427c0f897fb)
（Sebastian Eberlein  -  2017年8月14日）

[You're Offline](https://mxb.at/blog/youre-offline/)
（MaxBöck -  2017年7月12日）

[[第2部分]通过服务工作者在Angular应用程序中获得快速离线功能]（https://medium.com/onehourcode/part-2-get-rapid-offline-capability-in-your-angular-app-with-服务工人954f17109dd0）
（Hugo Dolan  -  2017年6月28日）

[Persistent Storage API: Building for the offline web](https://deanhume.com/Home/BlogPost/persistent-storage-api--building-for-the-offline-web/10161)
（Dean Hume  -  2017年6月26日）

[[第1部分]通过服务工作者在Angular应用程序中获得快速离线功能]（https://medium.com/onehourcode/part-1-get-rapid-offline-capability-in-your-angular-app-with-服务工人762a889a503d）
（Hugo Dolan  -  2017年6月21日）

[Building an offline Web App that works in very low internet conditions using ServiceWorkers](https://medium.com/progressive-web-apps/building-offline-webapp-using-serviceworkers-8939a694cc5)
（克里希纳日 -  2017年6月16日）

[Offline POSTs in Progressive Web Apps](https://medium.com/@nitish404/offline-post-in-progressive-web-apps-3d02f893b223)
（Nitish Thakur  -  2017年6月23日）

[Offline First Design Patterns : Engineering](https://medium.com/offline-camp/offline-first-design-patterns-engineering-1c66821137d3)
（Anirudha Bedre  -  2017年3月28日）

[Introducing Redux Offline: Offline-First Architecture for Progressive Web Applications and React Native](https://hackernoon.com/introducing-redux-offline-offline-first-architecture-for-progressive-web-applications-and-react-68c5167ecfe0)
（JaniEväkallio -  2017年3月28日）

[Rethinking Offline First sync for Service Workers](https://medium.com/offline-camp/rethinking-offline-first-sync-for-service-workers-da4727b6dee)
（Nolan Lawson  -  2017年3月16日）

[Offline support: "Try again, later", no more.](https://medium.com/@yonatanvlevin/offline-support-try-again-later-no-more-afc33eba79dc)
（Yonatan V. Levin  -  2017年3月2日）

[Optimize with HTTP/2 Server Push and Service Workers!](https://blog.yld.io/2017/03/01/optimize-with-http-2-server-push-and-service-workers)
（Daniela Matos de Carvalho  -  2017年3月1日）

[Understand offline first and offline last in Android](https://medium.com/@coreflodev/understand-offline-first-and-offline-last-in-android-71191e92b426)
（Florent Guillemot  -  2017年2月27日）

[Why Offline First?](https://medium.com/buildit/why-offline-first-20470604ee36)
（Zachary Smith  -  2017年2月22日）

[Send messages when you’re back online with Service Workers and Background Sync](https://www.twilio.com/blog/2017/02/send-messages-when-youre-back-online-with-service-workers-and-background-sync.html)
（Phil Nash  -  2017年2月17日）

[Easy Offline First Apps With Webpack's Offline Plugin](https://dev.to/kayis/easy-offline-first-apps-with-webpacks-offline-plugin)
（KayPlößer -  2017年2月12日）

[Offline First React Native + Meteor Apps](https://hackernoon.com/offline-first-react-native-meteor-apps-2bee8e976ec7)
（Spencer Carli  -  2017年2月8日）

[Offline-First Web Application Using Redux and PouchDB](https://stories.jotform.com/offline-first-web-applications-d2d321444510)
（BerkayAydın -  2017年1月30日）

[Implementing "Save For Offline" with Service Workers.](https://una.im/save-offline)
（One Kravets  -  2017年1月26日）

[Moving beyond localStorage](https://journal.standardnotes.org/moving-beyond-localstorage-991e3695be15#.wqzo3mpuz)
（Mo Bitar  -  2017年1月17日）

[How much data should my Service Worker put upfront in the offline cache?](https://nicolas-hoizey.com/2017/01/how-much-data-should-my-service-worker-put-upfront-in-the-offline-cache.html)
（Nicolas Hoizey- 2017年1月12日）

[Making Resilient Web Design work offline](https://medium.com/@adactio/making-resilient-web-design-work-offline-a5854781b75b#.8khh8bnio)
（Jeremy Keith  -  2017年1月11日）

[Using Service Workers and Cache to Take Web Performance to a New Level](https://calendar.perfplanet.com/2016/service-workers-cache-web-performance-new-level/)
（Chris Love  -  2016年12月23日）

[Faking progress (service worker edition)](https://medium.com/remys-blog/faking-progress-service-worker-edition-4c3fa16e5b32#.coya1w3ki)
（雷米夏普 -  2016年12月22日）

[Introduction to Progressive Web Apps (Offline First)](https://auth0.com/blog/introduction-to-progressive-apps-part-one/)
（Prosper Otemuyiwa  -  2016年12月19日）

[Won’t Get Fooled Again: Lessons in Lie-Fi](https://medium.com/outsystems-engineering/wont-get-fooled-again-lessons-in-lie-fi-9097052ea66e#.texx2j9pd)
（Ricardo Ferreira  -  2016年12月15日）

[Designing for Accidental Disconnects: Our first attempt at an offline approach](http://blog.getchop.io/2016/12/14/designing-for-accidental-disconnects-our-first-attempt-at-an-offline-approach/)
（Vivian Cromwell  -  2016年12月14日）

[Offline Patterns: There are many jobs to be done](https://medium.com/offline-camp/offline-patterns-there-are-many-jobs-to-be-done-9f97f7e89304#.54tbekzbf)
（Steve Trevathan  -  2016年12月13日）

[Writing offline web apps is easy](https://medium.com/@aliafshar/writing-offline-web-apps-is-easy-bc5ece2ed16e#.26kewn4dd)
（Ali Afshar  -  2016年12月9日）

[Architecting a web app to “just work” offline](https://blog.superhuman.com/architecting-a-web-app-to-just-work-offline-part-1-8697f316c0eb#.i6y75or3v)
（伊斯兰教Sharabash  -  2016年12月6日）

[Offline App Architecture: how to build for the next billion](https://hackernoon.com/so-you-want-to-develop-for-the-next-billion-9eb072c26bc8#.30ev0831v)
（Arun Sasidharan  -  2016年12月4日）

[Cross-origin Service Workers: Experimenting with Foreign Fetch](https://developers.google.com/web/updates/2016/09/foreign-fetch)
（Jeff Posnick  -  2016年12月）

[Service Worker, what are you?](https://medium.com/@kosamari/service-worker-what-are-you-ca0f8df92b65#.wc6eggecd)
（丸子麻里子 -  2016年12月1日）

[Designed to be offline-first](https://medium.com/hypertrack/designed-to-be-offline-first-def41a3668b8#.a0u11gp4j)
（Arjun Attam  -  2016年11月29日）

[Hack Time: Service Workers, Background Sync, and PouchDB](https://medium.com/offline-camp/hack-time-service-workers-background-sync-and-pouchdb-3c8b71535823#.qlqbjm6dw)
（John Kleinschmidt  -  2016年11月29日）

[Offline UX Considerations](https://developers.google.com/web/fundamentals/instant-and-offline/offline-ux)
（Mustafa Kurtuldu  -  2016）

[Storing Sensitive Data Offline](https://medium.com/offline-camp/storing-sensitive-data-offline-cec851df95e3#.g78qucejz)
（Paul Frazee  -  2016年11月17日）

[Building Offline First React Native Apps](https://medium.com/differential/building-offline-first-react-native-apps-b958acac0009#.94hfszbig)
（Spencer Carli  -  2016年11月16日）

[Building a simple offline-capable Notepad app using ServiceWorker](https://hackernoon.com/building-a-simple-offline-capable-notepad-app-using-serviceworker-97b9b50767a5#.k9zhvs3ep)
（Amit Merchant  -  2016年11月15日）

[Instant Loading Web Apps with an Application Shell Architecture by Google](https://developers.google.com/web/updates/2015/11/app-shell)
（Addy Osmani＆Matt Gaunt  -  2016）

[My biggest takeaway from the second Offline Camp in Santa Margarita, CA — plus toast!](https://medium.com/@jessebeach/my-biggest-takeaway-from-the-second-offline-camp-in-santa-margarita-ca-d0dd930cd02b#.di93bftj9)
（J.RenéeBeach -  2016年11月8日）

[The offline experience in 2016](https://medium.com/@leofle/the-offline-experience-in-2016-83b1f00d7bfa#.nk8910brf)
（Lio Fleishman  -  2016年10月27日）

[I Was Wrong About Offline](https://medium.com/outsystems-engineering/i-was-wrong-about-offline-fe5426894740#.yb9hhitn0)
（TiagoSimões -  2016年10月20日）

[Offline strategies come to the Service Worker Cookbook](https://hacks.mozilla.org/2016/10/offline-strategies-come-to-the-service-worker-cookbook/)
（保存 -  2016年10月19日）

["Instant Loading" with IndexedDB (Building a PWA, Part 2)](https://bitsofco.de/bitsofcode-pwa-part-2-instant-loading-with-indexeddb/)
（Ire Aderinokun  -  2016年10月18日）

[The Service Worker Lifecycle](https://developers.google.com/web/fundamentals/instant-and-offline/service-worker/lifecycle)
（Jake Archibald  -  2016年10月13日）

["Offline First" with Service Worker (Building a PWA, Part 1)](https://bitsofco.de/bitsofcode-pwa-part-1-offline-first-with-service-worker/)
（Ire Aderinokun  -  2016年10月11日）

[Do you need Service Worker in your web app?](https://codingbox.io/do-you-need-service-worker-in-your-web-app-d68131d65e2c?gi=666f4385e803)
（Valerii Iatsko  -  2016年10月9日）

[Progressive Web Apps with React.js: Part 3 — Offline support and network resilience](https://medium.com/@addyosmani/progressive-web-apps-with-react-js-part-3-offline-support-and-network-resilience-c84db889162c?source=userActivityShare-136a881c591e-1475748613)
（Addy Osmani  -  2016年10月5日）

[Offline Reading List](https://chrisruppel.com/blog/service-worker-offline-content-list/)
（Chris Ruppel  -  2016年10月5日）

[Almost any web page can work offline](https://github.com/homam/service-workers-example) 
（罗马侯赛尼 -  5月24日，2016）

[Enabling Offline First Experiences on the Web with Service Workers](https://medium.com/offline-camp/enabling-offline-first-experiences-on-the-web-with-service-workers-e4bc8c773dae#.c6ui0i9cs)
（Dan Zajdband  -  2016年9月12日）

[Build More Reliable Web Apps with Offline](http://thenewstack.io/build-better-customer-experience-applications-using-offline-first-principles/)
（Pedro Teixeira  -  2016年9月7日）

[Songsearch – using ServiceWorker to make a 4 MB CSV easily searchable in a browser](https://www.christianheilmann.com/2016/08/26/songsearch-using-serviceworker-to-make-a-4-mb-csv-easily-searchable-in-a-browser/)
（Christian Heilmann  -  2016年8月26日）

[Offline Storage for Progressive Web Apps](https://medium.com/dev-channel/offline-storage-for-progressive-web-apps-70d52695513c#.ryrpvq43r)
（Addy Osmani  -  2016年8月15日）

[Add offline support to any Web app](https://medium.com/google-developer-experts/add-offline-support-to-any-web-app-c20edc4bea0e#.jeseb4ovf)
（Wassim Chegham  -  2016年7月23日）

[ServiceWorker: A Basic Guide to BackgroundSync](https://ponyfoo.com/articles/backgroundsync)
（Dean Hume  -  2016年7月19日）

[Offline First, the Decentralized Web, and Peer-to-Peer Technologies](https://medium.com/offline-camp/offline-first-the-decentralized-web-and-peer-to-peer-technologies-b05b7fb3bcdd#.6xdfvy6on)
（Pedro Teixeira  -  2016年7月15日）

[Offline Google Analytics Made Easy](https://developers.google.com/web/updates/2016/07/offline-google-analytics)
（Jeff Posnick  -  Jul，2016）

[Security in Offline First Apps](https://medium.com/offline-camp/offline-first-security-59bf4800e82a)
（Calvin Metcalf  -  2016年7月8日）

[My blog's Service Worker and Caching Strategy](https://paul.kinlan.me/my-blogs-service-worker-and-caching-strategy/)
（Paul Kinlan  -  2016年6月15日）

[Offline/Low-bandwidth UX Design Patterns](https://medium.com/offline-camp/offline-low-bandwidth-ux-design-patterns-51391230a79e#.sctlcxk4e)
（Steve Trevathan  -  2016年7月8日）

[Offline Content with Service Worker](https://chrisruppel.com/blog/service-worker-offline-content/)
（Chris Ruppel  -  2016年6月6日）

[Taking an online book offline](https://adactio.com/journal/10754)
（Jeremy Keith  -  2016年6月3日）

[Service Workers — Gotchas](https://medium.com/@boopathi/service-workers-gotchas-44bec65eab3f#.4q0ncllos)
（Boopathi Rajaa  -  2016年5月9日）

[Offline-first QR-code Badge Scanner](https://developer.ibm.com/clouddataservices/2016/05/05/offline-first-qr-code-badge-scanner/)
（Glynn Bird  -  2016年5月5日）

[Service Workers and PWAs: It’s About Reliable Performance, Not “Offline”](https://infrequently.org/2016/05/service-workers-and-pwas-its-about-reliable-performance-not-offline/)
（Alex Russell- 2016年5月4日）

[Progressive Web Apps: Eating your Cake](https://medium.com/@torgo/progressive-web-apps-eating-your-cake-c0a79797220f#.jp6qup8xg)
（Daniel Appelquist  -  2016年4月27日）

[Progressive Web Apps with Service Workers](http://blog.booking.com/progressive-web-apps-with-service-workers.html)
（Jesse Yang  -  2016年4月21日）

[How To Use PouchDB + SQLite For Local Storage In Ionic 2](http://gonehybrid.com/how-to-use-pouchdb-sqlite-for-local-storage-in-ionic-2/)
（Ashteya Biharisingh  -  2016年4月18日）

[Offline-First, Document Sharing, Templates: Monod is Back (not in Black)](https://tailordev.fr/blog/2016/04/15/le-lab-2-offline-first-document-sharing-templates-monod-is-back/)
（2016年4月15日）

[Issue 4: Offline badging, DevTools, Testing, Travis, Web Storage, Service Worker Scopes, Data-driven Development, Compute Engine](https://medium.com/totally-tooling-tears/issue-4-offline-badging-testing-travis-devtools-issues-web-storage-data-driven-development-8dd1cfbc410a#.mgur8g8n3)
（Addy Osmani  -  2016年4月15日）

[The New Builders Ep. 1: Craft Beer and Progressive Web Apps](https://developer.ibm.com/tv/untappd-web-apps/)
（Douglas Flora  -  2016年4月14日）

[Service Workers replacing AppCache: a sledgehammer to crack a nut](https://medium.com/@firt/service-workers-replacing-appcache-a-sledgehammer-to-crack-a-nut-5db6f473cc9b#.sdp7iqxc3)
（Maximiliano Firtman  -  2016年4月11日）

[Progressive Web Apps — Offline And Add To Home Screen](https://medium.com/@greenido/progressive-web-apps-offline-and-add-to-home-screen-2187a2487a5c#.7m52kq892)
（Ido Green  -  2016年3月28日）

[The web on my phone](https://adactio.com/journal/10410)
（Jeremy Keith  -  2016年3月23日）

[The copy & paste guide to your first Service Worker](https://remysharp.com/2016/03/22/the-copy--paste-guide-to-your-first-service-worker)
（雷米夏普 -  2016年3月22日）

[Service Workers: Save your User's Data using the Save-Data Header](http://www.deanhume.com/Home/BlogPost/service-workers--save-your-users-data-using-the-save-data-header/10139)
（Dean Hume  -  2016年3月8日）

[Service Worker notes](https://adactio.com/journal/10186)
（Jeremy Keith  -  2016年2月4日）

[Making A Service Worker: A Case Study](https://www.smashingmagazine.com/2016/02/making-a-service-worker/)
（Lyza Danger Gardner  -  2016年2月1日）

[Create a really, really simple offline page using Service Workers](http://deanhume.com/home/blogpost/create-a-really--really-simple-offline-page-using-service-workers/10135)
（Dean Hume  -  2016年1月25日）

[Offline Web Applications: Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899)
（迈克尔威尔士 -  2016年1月20日）

[Building Offline Sites with ServiceWorkers and UpUp](https://dev.opera.com/articles/offline-with-upup-service-workers/)
（Tal Ater  -  2016年1月19日）

[Instant Web Application](https://glebbahmutov.com/blog/instant-web-application/)
（Gleb Bahmutov  -  2015年12月24日）

[Introducing Background Sync](https://developers.google.com/web/updates/2015/12/background-sync)
（Jake Archibald  -  2015）

[Beyond Offline](https://hacks.mozilla.org/2015/12/beyond-offline/)
（Salvador de laPuenteGonzález -  2015年12月21日）

[Getting started with the Service Worker Toolbox ](http://deanhume.com/Home/BlogPost/getting-started-with-the-service-worker-toolbox/10134)
（Dean Hume  -  2015年12月17日）

[ServiceWorker Cookbook](https://serviceworke.rs/)
（由Mozilla提供）

[Offline Web Applications with CouchDB, PouchDB and Ember CLI](https://teamgaslight.com/blog/offline-web-applications-with-couchdb-pouchdb-and-ember-cli)
（Chris Moore  -  2015年12月10日）

[A Hoodie Case Study: How minutes.io does offline](http://hood.ie/blog/minutes-offline-case-study)
（Alex Feyerke  -  2015年12月1日）

[Reducing Single Point of Failure using Service Workers](http://calendar.perfplanet.com/2015/reducing-single-point-of-failure-using-service-workers/)
（Dean Hume  -  2015年12月1日）

[Building realtime collaborative offline-first apps with React, Redux, PouchDB and WebSockets](https://blog.yld.io/2015/11/30/building-realtime-collaborative-offline-first-apps-with-react-redux-pouchdb-and-web-sockets/)
（Pedro Teixeira  -  2015年11月30日）

[Cache-limiting in Service Workers …again](https://adactio.com/journal/9888)
（Jeremy Keith  -  2015年11月29日）

[Introducing Pokedex.org: a progressive webapp for Pokémon fans](http://www.pocketjavascript.com/blog/2015/11/23/introducing-pokedex-org)
（Nolan Lawson  -  2015年11月23日）

[Cache-limiting in Service Workers](https://adactio.com/journal/9844)
（Jeremy Keith  -  2015年11月19日）

[Offline Recipes for Service Workers](https://hacks.mozilla.org/2015/11/offline-service-workers/)
（David Walsh  -  2015年11月19日）

[Instant Loading Web Apps With An Application Shell Architecture](https://medium.com/google-developers/instant-loading-web-apps-with-an-application-shell-architecture-7c0c2f10c73)
（Addy Osmani  -  2015年11月17日）

[An Offline Experience with Service Workers](http://brandonrozek.tumblr.com/post/135657690564/service-workers)
（Brandon Rozek  -  2015年11月14日）

[Building Flipkart Lite: A Progressive Web App](https://medium.com/@AdityaPunjani/building-flipkart-lite-a-progressive-web-app-2c211e641883)
（Aditya Punjani  -  2015年11月11日）

[Your first offline web app](https://developers.google.com/web/fundamentals/getting-started/codelabs/offline/)
（Chrome开发团队 -  2015）

[Making a Simple Site Work Offline with ServiceWorker](https://css-tricks.com/serviceworker-for-offline/)
（Nicolas Bevacqua  -  2015年11月10日）

[My first Service Worker](https://medium.com/@adactio/my-first-service-worker-5e5af0b1bdbb#.tsjcjzk2n)
（Jeremy Keith  -  2015年11月7日）

[Building an offline page for theguardian.com](https://www.theguardian.com/info/developer-blog/2015/nov/04/building-an-offline-page-for-theguardiancom)
（Oliver Joseph Ash  -  2015年11月4日）

[Creating Offline-First Web Apps with Service Workers](https://auth0.com/blog/2015/10/30/creating-offline-first-web-apps-with-service-workers/)
（Ryan Chenkie  -  2015年10月30日）

[Cache sandboxed HTTP requests with Service Worker](https://medium.com/@roman01la/cache-sandboxed-http-requests-with-service-worker-6bb3801237d1#.3jjklzohz)
（Roman Liutikov  -  2015年10月26日）

[The offline experience (or, saying goodbye to imperative data fetching)](https://medium.com/@d.gieselaar/the-offline-experience-or-saying-goodbye-to-imperative-data-fetching-9b2fa487eea7)
（Dario Gieselaar  -  2015年10月25日）

[ServiceWorker: Revolution of the Web Platform](https://ponyfoo.com/articles/serviceworker-revolution)
（Nicolas Bevacqua  -  2015年10月21日）

[Taking the web offline with service workers](https://mobiforge.com/design-development/taking-web-offline-service-workers)
（Ruadhan O&#39;Donoghue  -  2015年10月21日）

[Using Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API/Using_Service_Workers)
（MDN  -  2015年10月18日）

[Don’t Wait for ServiceWorker: Adding Offline Support with One-Line](https://davidwalsh.name/dont-wait-serviceworker-adding-offline-support-oneline)
（Kenneth Ormandy  -  2015年10月14日）

[Service Workers in Production](https://developers.google.com/web/showcase/2015/service-workers-iowa)
（Jeff Posnick  -  2015年10月1日）

[How Do We Get It Done, Now?](http://alistapart.com/column/how-do-we-get-it-done-now)
（Lyza Danger Gardner  -  2015年9月30日）

[The Role of Workers and Offline Cache](https://unoyunodiez.wordpress.com/2015/08/23/modern-mobile-web-development-01/)
（2015年9月7日）

[Let's make Offline Web Applications secure!](http://sakurity.com/blog/2015/07/28/appcache.html)
（Egor Homakov  -  2015年7月28日）

[Service Worker Meeting Highlights](https://blog.wanderview.com/blog/2015/07/28/service-worker-meeting-highlights/)
（Ben Kelly  -  2015年7月28日）

[Q&A: Offline first, not just mobile first says Couchbase](http://www.cbronline.com/news/mobility/apps/qa-offline-first-not-just-mobile-first-says-couchbase-4609613)
（James Nunns  -  2015年6月26日）

[Why offline-first matters, and what developers should know about it](https://logbook.hanno.co/offline-first-matters-developers-know/)
（Marcel Kalveram  -  2015年6月2日）

[Getting Appcache’s Fallback to work, crossbrowser](https://www.iandevlin.com/blog/2015/06/html5/getting-appcaches-fallback-to-work-crossbrowser)
（Ian Devlin  -  2015年6月1日）

[Mobile Apps Offline Support](https://www.infoq.com/articles/mobile-apps-offline-support)
（Gustavo Machado  -  2015年5月29日）

[Making react-europe.org work offline with Service Workers and free SSL from Cloudflare](https://medium.com/@patcito/making-react-europe-org-work-offline-with-service-workers-f54fb0457048)
（Patrick Aljord  -  2015年5月14日）

[Offline Data Synchronization in Ionic](https://frontmag.no/artikler/utvikling/offline-data-synchronization-ionic)
（Marco Fernandes  -  2015年4月29日）

[Offline Data in the Browser](http://www.levvel.io/blog-post/offline-data-in-the-browser/)
（Assaf Weinberg  -  Mar，2015）

[Offline: When Your Apps Can’t Connect to the Internet](https://uxdesign.cc/offline-93c2f8396124)
（Daniel Sauble  -  2015年3月29日）

[Offline is not just another mobile feature](http://betanews.com/2015/03/04/offline-is-not-just-another-mobile-feature/)
（Chuck Ganapathi  -  2015年3月4日）

[Offline-first, fast, with the sw-precache module](https://developers.google.com/web/updates/2015/02/offline-first-with-sw-precache)
（Jeff Posnick  -  2015年2月23日）

[Offline is Not a Feature](http://www.formotus.com/17221/blog-mobility/offline-is-not-a-feature)
（2015年2月16日）

[The Right and Wrong Strategies When Taking Your App Offline](http://appdevelopermagazine.com/2356/2015/2/9/The-Right-and-Wrong-Strategies-When-Taking-Your-App-Offline/)
（Martin Heller  -  2015年2月9日）

[Three takeaways for web developers after two weeks of painfully slow internet](https://byrslf.co/three-takeaways-for-web-developers-after-two-weeks-of-painfully-slow-internet-9e7f6d47726e)
（Gabor Lenard  -  2015年1月25日）

[Offline first: as simple as unplug & play?](http://www.ae.be/blog-en/offline-first-simple-unplug-play/)
（Thomas Anciaux  -  2015年1月15日）

[A simple ServiceWorker app](http://blog.lamplightdev.com/2015/01/06/A-Simple-ServiceWorker-App/)
（Chris Haynes  -  2015年1月6日）

[ServiceWorker is available in Chrome 40 beta](https://plus.google.com/+IlyaGrigorik/posts/WPZsWr4QGqR)
（Ilya Grigorik  -  2014年12月11日）

[PSA: Service Workers are Coming](http://infrequently.org/2014/12/psa-service-workers-are-coming/)
（Alex Russell  -  2014年12月11日）

[The offline cookbook](https://jakearchibald.com/2014/offline-cookbook/)
（Jake Archibald  -  2014年12月9日）

[The next UX challenge on the web: gaining offline trust](https://www.christianheilmann.com/2014/12/08/the-next-ux-challenge-on-the-web-gaining-offline-trust/)
（Christian Heilmann  -  2014年12月8日）

[Service Worker Recipes](https://github.com/GoogleChrome/samples/tree/gh-pages/service-worker)
（Cesar William Alvarenga  -  2014年12月8日）

[Introduction to Service Worker](https://developers.google.com/web/fundamentals/getting-started/primers/service-workers)
（Matt Gaunt  -  2014年12月1日）

[offline decentralized single sign-on in the browser](http://substack.net/offline_decentralized_single_sign_on_in_the_browser)
（James&#39;suback&#39;Halliday  -  2014年11月27日）

[Offline Web Apps with Meteor](https://subvisual.co/blog/posts/45-offline-web-apps-with-meteor)
（GabrielPoça，2014年11月26日）

[How to build web applications that can work offline with PouchDB?](http://www.theodo.fr/blog/2014/11/how-to-build-web-applications-work-offline-pouchdb/)
（Yann Jacquot  -  2014年11月25日）

[Making Your App Work Offline: Tips and Cautionary Tales](https://quickleft.com/blog/making-your-app-work-offline-tips-and-cautionary-tales/)
（David Aragon  -  2014年11月11日）

[How Google and Mozilla are aiming to make web apps shine offline](http://www.techrepublic.com/article/how-google-and-mozilla-are-aiming-to-make-web-apps-work-as-well-offline-as-on/)
（Nick Heath  -  2014年10月30日）

[Offline-first is people-first](https://nolanlawson.com/2014/10/03/offline-first-is-people-first/)
（Nolan Lawson  -  2014年10月3日）

[Introducing Hoodie: Full Stack App Development for Front-End Developers](https://www.toptal.com/front-end/introducing-hoodie-full-stack-app-development-for-front-end-developers)
（Alvaro Oliveira  -  2014年9月24日）

[Offline-first: a new paradigm in web development](https://github.com/pazguille/offline-first/blob/master/ttps://translate.google.com/translate?hl=en&sl=nl&tl=en&u=http%3A%2F%2Fwww.e-sites.nl%2Fblog%2F400-offline-first-een-nieuw-paradigma-in-web-development.html)
（Boye Oomens  -  2014年9月16日）

[Building A Simple Cross-Browser Offline To-Do List With IndexedDB And WebSQL](https://www.smashingmagazine.com/2014/09/building-simple-cross-browser-offline-todo-list-indexeddb-websql/)
（马特安德鲁斯 -  2014年9月2日）

[Introducing MakeDrive](http://blog.humphd.org/introducing-makedrive/)
（David Humphrey  -  2014年8月25日）

[Worklight Authentication done right with AngularJs](https://medium.com/@papasimons/worklight-authentication-done-right-with-angularjs-768aa933329c)
（Gideon Simons  -  2014年8月22日）

[Taking your Worklight apps offline](https://medium.com/@papasimons/taking-your-worklight-apps-offline-e8c2c2d8533a)
（Gideon Simons  -  2014年8月19日）

[Working offline](https://developer.mozilla.org/en-US/Apps/Fundamentals/Offline)
（2014年8月12日）

[Offline First - the new paradigm in web development done Neptune style](http://scn.sap.com/community/developer-center/front-end/blog/2014/08/05/offline-first--the-new-paradigm-in-web-development-done-neptune-style) （NjålStabell -  2014年8月5日）

[Breaking Development: Offline First is the new Mobile First](http://www.lukew.com/ff/entry.asp?1902)
（Luke Wroblewski  -  2014年7月29日）

[Offline Patterns](https://www.ibm.com/developerworks/community/blogs/worklight/entry/offline_patterns?lang=en)
（Carlos Andreu  -  2014年7月3日）

[Offline Web Apps,Web Storage,IndexedDB,AppCache,File API Futures](https://www.youtube.com/watch?v=pklpK55uQmE&feature=youtu.be)
（Ali Alabbas  -  2014年5月21日）

[Service Workers: Offline Now(ish)!](https://www.youtube.com/watch?v=BKD7ZLRi9HI)
（Alex Russell  -  2014年5月21日）

[Service Worker - first draft published](https://jakearchibald.com/2014/service-worker-first-draft/)
（Jake Archibald  -  2014年5月8日）

[The BMEAN Stack and Offline-First Design](http://dailyjs.com/2014/04/10/bmean/)
（Daishi Kato  -  2014年4月11日）

[Do HTML5 apps have to be online all the time?](https://www.christianheilmann.com/2014/03/23/do-html5-apps-have-to-be-online-all-the-time/)
（Christian Heilmann  -  2014年3月23日）

[Building an Offline First App with PouchDB](https://www.sitepoint.com/building-offline-first-app-pouchdb/)
（蒂芙尼布朗 -  2014年3月10日）

[Introduction to Offline Web Apps on the Kindle Fire](https://developer.amazon.com/public/community/post/Tx21KG2QC7O71S9/Introduction-to-Offline-Web-Apps-on-the-Kindle-Fire.html)
（Russell Beattie  -  2014年1月30日）

[Designing Offline-First Web Apps](http://alistapart.com/article/offline-first)
（Alex Feyerke  -  2013年12月4日）

[Offline First: Learning from native experiences](https://medium.com/@dalmaer/offline-first-learning-from-native-experiences-4a778ce8a445)
（Dion Almaer  -  2013年12月4日）

[Offline First](http://www.kryogenix.org/days/2013/11/06/offline-first/)
（Stuart Langridge  -  2013年11月6日）

[Making the web work offline first](http://marcelkalveram.com/2013/11/developing-for-offline-first/)
（Marcel Kalveram  -  2013年11月20日）

[Say Hello to Offline First](http://hood.ie/blog/say-hello-to-offline-first.html)
（Dan Lash  -  2013年11月5日）

[Offline First: Your Next Progressive Enhancement Technique?](https://www.sitepoint.com/offline-first-next-progressive-enhancement-technique/)
（Craig Buckler  -  2013年10月30日）

[Appcache, not so much a douchebag as a complete pain in the #$%^](http://www.webdirections.org/blog/appcache-not-so-much-a-douchebag-as-a-complete-pain-in-the/)
（John Allsopp  -  2013年7月19日）

[Using HTML5 AppCache with Single Page Applications](https://techblog.dorogin.com/2013/03/using-html5-appcache-with-single-page-apps.html)
（Sergei Dorogin  -  2013年3月29日）

[Application Cache is a Douchebag](http://alistapart.com/article/application-cache-is-a-douchebag)
（Jake Archibald  -  2012年5月8日）

[Appcache Facts](http://mmariani.github.io/appcachefacts/)

[Chrome Offline Apps](https://developer.chrome.com/apps/offline_apps)

[Offline Support is Valuable, and You Can’t Add it Later](http://aanandprasad.com/articles/offline/)
（Aanand Prasad  -  2011年8月13日）

[Offline-first web app design](https://unhosted.org/practice/29/Offline-first-web-app-design.html)
（Michiel B. de Jong  -  2011）

[5 Reasons Why There are no Killer Offline Web Applications](https://www.sitepoint.com/killer-offline-web-applications/)
（Craig Buckler  -  2010年2月16日

[Offline Web Applications](https://hacks.mozilla.org/2010/01/offline-web-applications/)
（Paul Rouget  -  2010年1月7日）

[Let's take this offline](http://diveintohtml5.info/offline.html)
（Mark Pilgrim）


## Presentations

### Videos

[Offline-first for Your Static Site](https://www.youtube.com/watch?v=_kJMjJ1tm6o)
（Jeff Posnick  -  2017年1月30日）

[Service Worker and the Appification of the Web](http://www.thedotpost.com/2016/12/nolan-lawson-service-worker-and-the-appification-of-the-web)
（Nolan Lawson  -  2016年12月5日）

[Future App Model: Advanced Service Worker](https://www.youtube.com/watch?v=J2dOTKBoTL4)
（Jake Archibald- 2016年11月11日）

[Offline is the new black](https://vimeo.com/171317290)
（Max Stoiber  -  2016年6月19日）

[Service workers at scale with Facebook and Flipkart](https://www.youtube.com/watch?v=fGTUIlEM0m8&feature=youtu.be&t=2200)
（Owen Campbell-Moore，Aditya Punjani和Nate Schloss  -  2016年5月20日）

[Instant Loading: Building offline-first Progressive Web Apps](https://www.youtube.com/watch?v=cmGr0RszHc8)
（Jake Archibald  -  2016年5月20日）

[Offline First – the good parts](https://www.youtube.com/watch?v=NEferkZOGV4&feature=youtu.be)
（Gregor Martynus  -  2016年5月12日）

[Offline Web Applications: Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899)

[Totally Tooling Tips: Offline Support](https://www.youtube.com/watch?v=OBfLvqA_E4A)
（Addy Osmani＆Matt Gaunt  -  2016年4月27日）

[Using Service Workers in Ember](http://confreaks.tv/videos/emberconf2016-using-service-workers-in-ember)
（John Kleinschmidt  -  2016年3月29日）

[Offline-First Apps with PouchDB](https://www.youtube.com/watch?v=7L7esHWAjSU)
（布拉德利霍尔特 -  2015年12月11日）

[Worker as a Service](https://www.youtube.com/watch?v=5LAMbIlwilc)
（Ola Gasidlo  -  2015年11月19日）

[Taking Your Web Apps Offline](https://www.youtube.com/watch?v=EZF1EfjQlbo)
（Mike Nitchie  -  2015年11月16日）

[There is a client-side proxy (ServiceWorker) in your browser!](https://www.youtube.com/watch?v=etACK2qbHfc)
（Ilya Grigorik  -  2015年11月16日）

[OnConnectionLost: The life of an offline web application](https://www.youtube.com/watch?v=rw8Q9ZLDkEs)
（Stefanie Grewenig  -  2015年10月12日）

[Offline First and Service Workers](https://www.youtube.com/watch?v=TGwjgmAqNRo)
（Maximilian Stoiber  -  2015年10月5日）

[Offline First Podcast](https://www.youtube.com/watch?v=tilH8jgLrXQ)
（网络平台播客 -  2015年9月8日）

[The Once & Future Web](https://www.youtube.com/watch?v=RQQNNP8tFro)
（Jake Archibald  -  2015年7月28日）

[Go Offline](https://www.youtube.com/watch?v=BucGrYACJdQ)
（Rob Dodson  -  2015年6月29日）

[Taking Ember Offline](https://www.youtube.com/watch?t=20&v=VhZS4n2DMyU)
（John Kleinschmidt  -  2015年6月16日）

[Holy sync](https://www.youtube.com/watch?v=Yp1h3cd8dsg)
（Eugenio Marletti  -  2015年5月5日）

[Making Offline Suck Less with Service Workers](https://www.youtube.com/watch?v=nqecpa6MtZ0)
（Bret Little  -  2015年3月28日）

[Say Hello to Offline First](https://www.youtube.com/watch?v=ZsMS_sviJs0)
（Ola Gasidlo  -  2015年3月26日）

[The UX Of Offline-First](https://vimeo.com/125479288)
（Jake Archibald  -  2015年3月18日）

[The Web's Future is Offline](https://vimeo.com/120474703)
（John Allsopp  -  2015年2月24日）

[Building Offline First Applications with Backbone](https://www.youtube.com/watch?v=Zb01eNS6-no)
（Gregor Martynus  -  2014年12月17日）

[Working connected to create offline](https://www.youtube.com/watch?v=fj49cSQ986k)
（Christian Heilmann  -  2014年11月24日）

[The ServiceWorker is coming, look busy!](https://www.youtube.com/watch?v=Rr2vXDIVerI)
（Jake Archibald  -  2014年9月21日）

[The Next Challenge of the Web is Us](https://www.youtube.com/watch?v=QPRqQH_30hU&t=22m53s)
（Christian Heilmann  -  2014年8月1日）

[Offline First](https://www.youtube.com/watch?v=dPz_5-MEvcg)
（Alex Feyerke  -  2014年7月17日）

[The ServiceWorker: The network layer is yours to own](https://www.youtube.com/watch?v=4uQMl7mFB6g)
（Jake Archibald  -  2014年6月25日）

[Offline Web Applications](https://www.youtube.com/watch?v=AbixY3W8ayo)
（Jan Jongboom  -  2014年5月23日）

[The Offline Web](https://www.youtube.com/watch?v=nnLBdFLo2fc)
（Dale Harvey  -  2014年6月20日）

[Bring NoSQL to your mobile](https://www.youtube.com/watch?v=qfC90DQEoeY)
(Patrick Heneise - Dec 16, 2013)

[Network connectivity: optional](https://www.youtube.com/watch?v=Z7sRMg0f5Hk)
（Jake Archibald  -  2013年12月4日）

[Surviving the Offline Apocalypse](https://www.youtube.com/watch?v=Qg75x08Mtcs)
（John Kleinschmidt  -  2014年11月29日）

[Offline First](https://www.youtube.com/watch?v=7mdG-iAizVc)
（Jan Lehnardt  -  2013年5月27日）

[Offline rules: Bleeding edge web standards at the Financial Times](https://vimeo.com/64201695)
（Andrew Betts  -  2013年4月）

[What's the right way to build offline into a web application?](https://www.youtube.com/watch?v=Oic22dQMRXQ)
（Jake Archibald，Mark Christian，Alex Russell和Jonas Sicking  -  2013年2月9日）

[AppCache: Douchebag](https://www.youtube.com/watch?v=cR-TP6jOSQM)
（Jake Archibald  -  2013年1月20日）

[Application Cache And Local Storage](https://www.youtube.com/watch?v=ceODU6z4-yc)
（Scott Davis  -  2012年12月7日）

[Offline Rules](https://www.youtube.com/watch?v=RrGo1Sz4IgQ)
（Andrew Betts  -  2012年12月4日）

[Building Web Apps of the future. Tomorrow, today and yesterday.](https://www.youtube.com/watch?v=O3AukCYymEU)
（Paul Kinlan  -  2012年11月12日）

[Taking Web Apps Offline](https://www.youtube.com/watch?v=ejcJmeewtd4)
（Kevin Markman  -  2012年11月5日）

[Building Offline Web Apps with HTML5](https://www.youtube.com/watch?v=W41mvarupH0)
（Jonathan Stark  -  2012年7月25日）

[Getting off(line): appcache, localStorage for HTML5 apps that work offline](https://www.youtube.com/watch?v=dN8e-QdYyCk)
（John Allsopp  -  2012年7月3日）

### Slides

[Offline, progressive, and multithreaded](https://nolanlawson.github.io/fronteers-2016/#/)
（Nolan Lawson  -  2016年10月10日）

[Rise of the Web Workers](http://blog.nparashuram.com/2016/09/rise-of-web-workers-nationjs.html)
（Parashuram N  -  2016年9月16日）

[Building an Offline Page for theguardian.com](https://speakerdeck.com/oliverjash/building-an-offline-page-for-theguardian-dot-com-jsconf-budapest-may-2016)
（Oliver Joseph Ash  -  2016年5月14日）

[Go offline with Service Workers](https://docs.google.com/presentation/d/1crh5m2aDdZPAL07Zo1FtuAliwwghW6FMOEtXviA_BZo/edit#slide=id.p)
（Emanuel Kluge  -  2016）

[Building an Offline Page for theguardian.com](https://speakerdeck.com/oliverjash/building-an-offline-page-for-theguardian-dot-com-london-web-perf-march-2016)
（Oliver Joseph Ash  -  Mar，2016）

[Insanely fast rendering w/ Service Workers and Early Flushing](https://speakerdeck.com/mstuart/service-workers-and-early-flushing)
（Mark Stuart  -  2015年12月14日）

[Offline-First Apps with PouchDB at Node.js Interactive](https://speakerdeck.com/bradleyholt/offline-first-apps-with-pouchdb-at-node-dot-js-interactive)
（布拉德利霍尔特 -  2015年12月9日）

[Developing for Offline First Mobile Experiences](http://www.slideshare.net/NicRaboy/developing-for-offline-first-mobile-experiences)
（Nic Raboy  -  2015年12月2日）

[At your service! - More than appcache uses for Service Workers](http://delapuente.github.io/presentations/at-your-service/index.html)
（Salvador de laPuenteGonzález -  2015年10月21日）

[Offline First (Web) Apps](https://speakerdeck.com/espylaub/offline-first-web-apps-beuth-hochschule-berlin)
（Alex Feyerke  -  2015年10月20日）

[Offline-First Web Applications](https://docs.google.com/presentation/d/1gDGIyGtXMSmtT8WsyXj7ADyUjNV679T1BF5QGEKqooc/mobilepresent)
（PeterMüller -  2015）

[Server in your Client - Service Workers' rise to fame](http://slides.com/flaki/server-in-the-client#/)
（IstvánSzmozsánszky -  2015年10月7日）

[Offline-First Web Applications](https://docs.google.com/presentation/d/1gDGIyGtXMSmtT8WsyXj7ADyUjNV679T1BF5QGEKqooc/mobilepresent?slide=id.gb7f243163_0_53)
（PeterMüller -  2015年6月27日）

[Offline-first mobile web apps with PouchDB, IBM Cloudant, and IBM Bluemix](http://www.slideshare.net/IBMBluemix/offlinefirst-mobile-web-apps-with-pouchdb-ibm-cloudant-and-ibm-bluemix)
（布拉德利霍尔特 -  2015年6月22日）

[Building Offline-Enabled Apps with PouchDB](https://speakerdeck.com/bradleyholt/building-offline-enabled-apps-with-pouchdb-at-php-tek-2015)
（布拉德利霍尔特 -  2015年5月20日）

[Naked and afraid Offline Mobile](http://www.slideshare.net/ColdFusionConference/naked-and-afraid-48288396)
（马特伍德沃德 -  2015年5月18日）

[Offline first, the painless way](http://de.slideshare.net/MarcelKalveram/offline-first-the-painless-way)
（Marcel Kalveram  -  2015年5月17日）

[noBackend e Offline First: focusing on creating experiences (pt-br)](https://speakerdeck.com/joselitojunior1/nobackend-e-offline-first-foque-em-criar-experiencias-number-frontinfortaleza)
（JoselitoJúnior -  2015年5月16日）

[HOLY SYNC: a sane approach to offline-first cross-platform data syncing](https://speakerdeck.com/takhion/holy-sync-a-sane-approach-to-offline-first-cross-platform-data-syncing)
（Eugenio Marletti  -  2015年4月10日）

[Service Worker and the Offline Web](https://slidr.io/lewiscowper/service-worker-and-the-offline-web-lightning-talk)
（Lewis Cowper  -  2015年3月7日）

[Service Workers on vacay...](https://docs.google.com/presentation/d/1LUuMYDi1ssmslQKnnX3cwrdLVy2YCqyww3PBtqEP0q8/edit)
（娜塔莎鲁尼 -  2015年3月6日）

[TGIF - Offline-first](http://codekult.github.io/tgif-offline-first/)
（DiegoCalderón -  2015年1月30日）

[ServiceWorkers and High Performance Offline Apps](https://huffduffer.com/AlanDalton/202718)
（AlanDalton  -  2015年1月13日）

[Leveraging hood.ie to build for the offline state](http://de.slideshare.net/MarcelKalveram/codemotion-talk-41932602)
（Marcel Kalveram  -  2014年11月24日）

[Let's Take Drupal Offline!](http://www.slideshare.net/dickolsson/lets-take-drupal-offline-41650712)
（迪克奥尔森 -  2014年11月17日）

[Offline-first web apps - Velocity EU 2014](http://www.slideshare.net/andrewsmatt/velocity-eu-2014)
（马特安德鲁斯 -  2014年11月17日）

[Discover ServiceWorker](http://www.slideshare.net/sandropaganotti/discover-serviceworker)
（Sandro Paganotti  -  2014年11月16日）

[Offline first <3](https://speakerdeck.com/zoepage/ayb14-offline-first-1)
（Ola Gasidlo  -  2014年10月17日）

[Scaling Down: The Offline First Story](https://speakerdeck.com/wohali/scaling-down-the-offline-first-story)
（Joan Touzet  -  2014年9月16日）

[Status Web Offline](https://www.infoq.com/presentations/status-web-offline)
（Caolan McMahon  -  2014年8月21日）

[Look Ma, No Connections! Building Offline-capable Web Apps with HTML5](https://www.infoq.com/presentations/html5-offline-storage)
（Bijan Vaez  -  2014年8月1日）

[Say hello to offline first!](https://speakerdeck.com/zoepage/say-hello-to-offline-first)
（Ola Gasidlo  -  2014年5月19日）

[Offline First (Web) Apps](https://speakerdeck.com/espylaub/offline-first-web-apps)
（Alex Feyerke  -  2014年5月2日）

[Offline First – Made Simple!](https://speakerdeck.com/gr2m/offline-first-made-simple)
（Gregor Martynus  -  2014年4月24日）

[Offline First Re-Imagining Web Development For The Real World](https://qconlondon.com/london-2014/dl/qcon-london-2014/slides/CaolanMcMahon_OfflineFirstReImaginingWebDevelopmentForTheRealWorld.pdf)
（Caolan McMahon  -  Mar，2014）

## Tools

[offline-plugin](https://github.com/NekR/offline-plugin/)：用于webpack的脱机插件（ServiceWorker，AppCache）.

[Pinterest Service Workers](https://github.com/pinterest/service-workers)：用于创建/测试/试验服务工作者的实用程序集合.

[Kinto](http://www.kinto-storage.org/)：在几秒钟内为Web应用程序添加同步和共享功能.

[bottle-service](https://github.com/bahmutov/bottle-service)：从ServiceWorker缓存还原的即时Web应用程序.

[react-boilerplate](https://github.com/mxstbr/react-boilerplate)：针对性能导向的离线优先React.js应用程序的快速设置.

[Haywire](https://github.com/omnia-salud/haywire)：用于网络问题检测的最小javascript库.

[sw-toolbox](https://github.com/GoogleChrome/sw-toolbox)：服务工作者的工具集合.

[UpUp](https://www.talater.com/upup/)：脱机第一个库，旨在成为向站点添加脱机功能的最简单方法.

[simple-serviceworker-tutorial](https://github.com/jakearchibald/simple-serviceworker-tutorial)：一个非常简单的ServiceWorker示例，旨在成为ServiceWorker的交互式介绍.

[Hyperboot](https://github.com/substack/hyperboot)：离线webapp bootloader.

[MakeDrive](https://github.com/mozilla/makedrive) ：基于云的Dropbox®等效于浏览器文件系统.  设计用于Mozilla Webmaker工具和服务.
见 [Mozilla MakeDrive Wiki page](https://wiki.mozilla.org/Webmaker/MakeDrive) 用于背景信息.

[ApplicationCache](https://developer.mozilla.org/en-US/docs/Web/HTML/Using_the_application_cache)：HTML5提供了一种应用程序缓存机制，可让基于Web的应用程序脱机运行.

[IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)：IndexedDB是用于客户端存储大量结构化数据的API，以及使用索引对此数据进行高性能搜索的API.

[ServiceWorkers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) ：服务工作者就像客户端上的代理.  对于页面请求和页面请求，您将获得一个可以响应自己的获取事件，从而创建离线体验.

[localForage](https://github.com/localForage/localForage) ：离线存储，改进.  使用简单但功能强大的API包装IndexedDB，WebSQL或localStorage.

[remoteStorage](https://remotestorage.io/)：支持remoteStorage的应用自动在您的所有设备上同步数据，从桌面到平板电脑，再到智能手机，甚至是电视.

[pouchdb](https://pouchdb.com/): PouchDB is an open-source JavaScript database inspired by Apache CouchDB that is designed to run well within the browser.

[Offline.js](http://github.hubspot.com/offline/docs/welcome/)：一个非常棒的JavaScript库，可在用户失去连接时改善应用程序的体验.

[Hoodie](http://hood.ie/)：Hoodie是一个Offline First和noBackend架构，适用于网络和iOS上仅限前端的Web应用程序.

[Offline States](http://offlinestat.es/)：当我们没有互联网连接时显示应用程序的内容.

[appCache Nanny](https://github.com/gr2m/appcache-nanny)：appCache的JavaScript API

[bro-fs](https://github.com/vitalets/bro-fs)：基于承诺的包装器 [HTML5 Filesystem API](https://www.w3.org/TR/file-system-api/) 允许在Chrome中使用沙盒文件系统.

[Orbit.js](http://orbitjs.com/)：用于编排数据源之间的访问，转换和同步的框架.

[workbox](https://github.com/GoogleChrome/workbox)：用于脱机缓存的JavaScript库


## Books

[The Offline First Book](https://neighbourhood.ie/offline-first/book/)
（由Neighbourhoodie提供）

[Offline First Web Development](https://www.packtpub.com/web-development/offline-first-web-development)
（Daniel Sauble撰写）

[Building Progressive Web Apps](http://shop.oreilly.com/product/0636920052067.do)
（由Tal Ater提供）

[Client-Side Data Storage](http://shop.oreilly.com/product/0636920043676.do)
（雷蒙德·卡姆登）

[Offline First: The book (draft)](http://www.webdirections.org/offlineworkshop/ibooksDraft.pdf)
（约翰·奥尔索普）

[Pro HTML5 Programming - Chapter 12: Creating HTML5 Offline Web Applications](http://apress.jensimmons.com/v5/pro-html5-programming/ch12.html)
（Peter Lubbers，Brian Albers和Frank Salim）

## Showcase
[Minutes.io](https://minutes.io)：真棒离线第一分钟采用应用程序构建 [Hoodie](http://hood.ie/).

[2048](https://gabrielecirulli.github.io/2048/)：最初的2048是一个很棒的游戏，可以固定在你的主屏幕上. 

[hospitalrun.io](http://hospitalrun.io/)：开发世界医院的开源软件.

[pokedex.org](https://www.pokedex.org/) ：神奇宝贝的索引，构建为客户端JavaScript webapp.  由ServiceWorker，PouchDB，虚拟dom和Web工作人员提供支持.

[Soundslice](https://www.soundslice.com/)：使用交互式表示法更好地学习和教授音乐 [offline mode](https://www.soundslice.com/blog/29/introducing-soundslice-offline-mode/).

## Who to Follow
- [Matthew Riley](https://github.com/tofumatt)：在mozilla工作，localForage（localstroage，IndexedDb和WebSQL Wrapper）的创建者
- [Jake Archibald](https://github.com/jakearchibald)：自我描述的服务工作者狂热，在谷歌工作帮助使离线网络应用程序的事情.

## Contributing
 欢迎分享，建议和贡献！  如果您想贡献，我们强烈建议您这样做.  请阅读 [contribution guidelines](https://github.com/pazguille/offline-first/blob/master/CONTRIBUTING.md).

谢谢大家 [contributors](https://github.com/pazguille/offline-first/graphs/contributors).

## Maintained by
-  Guille Paz（前端开发人员| Web标准爱好者）
- 电子邮件： [guille87paz@gmail.com](https://github.com/pazguille/offline-first/blob/master/mailto:guille87paz@gmail.com)
- 推特： [@pazguille](https://twitter.com/pazguille)
- 网站： [https://pazguille.me/](https://pazguille.me/)

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
