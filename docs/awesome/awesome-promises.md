<div class="github-widget" data-repo="wbinnssmith/awesome-promises"></div>
<a href="https://promisesaplus.com/">
    <img src="https://promisesaplus.com/assets/logo-small.png" alt="Promises/A+ logo" align="right" />
</a>

## Awesome Promises [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; JavaScript Promises 有用资源的精选列表

灵感来自 [awesome](https://github.com/sindresorhus/awesome) 列出事情. 不要与其他令人敬畏的承诺相混淆，例如“我向你保证一百万美元”或“我保证你会保持健康并且永远不必再去健身房”.



## Resources, Blogs, and Books

### For beginners
* [Promise Cookbook](https://github.com/mattdesl/promise-cookbook)  - 为什么、什么以及如何.  “简要介绍 [...] 主要针对前端开发人员”.
* [Promises for Asynchronous Programming](http://exploringjs.com/es6/ch_promises.html) - 章节来自 [Exploring ES6](http://exploringjs.com/)
* [You Don't Know JS: Promises](https://github.com/getify/You-Dont-Know-JS/blob/master/async%20&%20performance/ch3.md) - 章节来自 [You Don't Know JS: Async & Performance](https://github.com/getify/You-Dont-Know-JS/tree/master/async%20%26%20performance)
* [JavaScript Promises: an Introduction](https://developers.google.com/web/fundamentals/getting-started/primers/promises) - JavaScript 原生承诺实现的基础知识.
* [JavaScript with Promises](http://shop.oreilly.com/product/0636920032151.do)  - 来自奥莱利. 简明扼要. 使用本地和蓝鸟.
* [Promise it won't hurt](https://github.com/stevekane/promise-it-wont-hurt) - 一个互动 [nodeschool](https://nodeschool.io/) 作坊
* [ES6 Kata Promises](http://es6katas.org/) - 承诺卡塔斯： [Basics](http://tddbin.com/#?kata=es6/language/promise/basics)
* [ES6 Promises in Depth](https://ponyfoo.com/articles/es6-promises-in-depth)
* [An Incremental Tutorial on Promises](http://www.sohamkamani.com/blog/2016/08/28/incremenal-tutorial-to-promises/) - 适合初学者的常见问题解答风格的教程.

### Deep Dive
* [Promise Fun](https://github.com/sindresorhus/promise-fun) - @sindresorhus 的注释、模式和常见 Promise 问题的解决方案
* [You're Missing the Point of Promises](https://blog.domenic.me/youre-missing-the-point-of-promises/) - Promises 不仅仅是回调聚合，而且 jQuery 的实现（3.0 之前）还不够.
* [We have a problem with promises](https://pouchdb.com/2015/05/18/we-have-a-problem-with-promises.html) - “我们中的许多人在没有真正理解它们的情况下使用承诺.”
* [Promise anti-patterns](https://github.com/petkaantonov/bluebird/wiki/Promise-anti-patterns) - 常见的误用以及如何避免它们.
* [Promise anti-patterns (2)](http://taoofcode.net/promise-anti-patterns/) - 另一组承诺反模式
* [Promise Ponderings, (Anti-)Patterns, and Apologies](https://sdgluck.github.io/2015/08/24/promise-ponderings-patterns-apologies/) - 通过常见问题及其答案展示和解释的承诺行为.
* [Javascript Promises...In Wicked Detail](http://www.mattgreer.org/articles/promises-in-wicked-detail/) - 重新创建承诺实现
* [Writing Promise-Using Specifications](https://www.w3.org/2001/tag/doc/promises-guide) - “本文档提供了有关如何编写创建、接受或操纵承诺的规范的指导”
* [Async functions - making promises friendly](https://developers.google.com/web/fundamentals/getting-started/primers/async-functions)

### References
* [Promises/A+ specification](https://promisesaplus.com/)
* [caniuse promises](http://caniuse.com/#feat=promises)
* [Fates and States](https://github.com/domenic/promises-unwrapping/blob/master/docs/states-and-fates.md) - 可能状态的快速定义.
* [Promisees](https://bevacqua.github.io/promisees/) - 承诺冒险的可视化游乐场.

## Promises/A+ Implementations (ES6/ES2015 compatible)

### Strict Implementations
这些实现不多于或少于 es6 规范. 它们制作了很棒的 polyfill，并且与原生 promise 非常兼容.

* [pinkie](https://github.com/floatdrop/pinkie)  - 小马菲尔. 面向节点，但是 [browserifyable](https://github.com/substack/node-browserify) .  *非常*小的实现.
* [native-promise-only](https://github.com/getify/native-promise-only)  - 填充. 浏览器和节点兼容.
* [es6-promise](https://github.com/stefanpenner/es6-promise)  - 选择加入 polyfill.  rsvp.js 的严格规范子集.
* [lie](https://github.com/calvinmetcalf/lie) - 小巧，可通过选择加入的 polyfill 进行浏览器验证.

### Implementations with extras
所有这些都提供了比该语言更多的功能，但仍保持兼容. 所有人的节点+浏览器.

* [bluebird](https://github.com/petkaantonov/bluebird)  - 功能齐全，性能极佳. 长堆栈跟踪和生成器/协程支持.
* [creed](https://github.com/briancavalier/creed)  - 超高性能和全功能，如 Bluebird，但面向 FP. 协程、生成器、承诺、ES2015 可迭代对象和幻想世界规范.
* [rsvp.js](https://github.com/tildeio/rsvp.js/) 重量轻，有一些额外的东西. 向下兼容IE6！
* [Q](https://github.com/kriskowal/q)  - 最初的实现之一. 长堆栈跟踪和其他好东西.
* [then/promise](https://github.com/then/promise) - 添加了 `nodeify`、`denodify` 和 `done()` 的小程序.
* [when.js](https://github.com/cujojs/when) - 包含控制流、功能和实用方法.


### Fallbacks
* [native-or-bluebird](https://www.npmjs.com/package/native-or-bluebird) - 帮助过渡到完全原生.
* [pinkie-promise](https://github.com/floatdrop/pinkie-promise)  - 使用原生，或回退到 `pinkie`. 非常适合节点库作者.
* [any-promise](https://github.com/kevinbeaty/any-promise)  - 加载第一个可用的实现. 对浏览器安全.

## Convenience Utilities
本机和严格符合规范的承诺对于兼容性、未来证明、库作者和浏览器来说都是很棒的. 然而，像 bluebird 这样的库将好东西修补到“Promise”构造函数和原型上. 解决方案？ 当然是小模块！

### sindresorhus's many Promise utilities ([see notes](https://github.com/sindresorhus/promise-fun))
* [delay](https://github.com/sindresorhus/delay) - 将承诺延迟指定的时间.
* [pify](https://github.com/sindresorhus/pify) - Promisify (&quot;denodify&quot;) 回调函数.
* [loud-rejection](https://github.com/sindresorhus/loud-rejection) - 使未处理的承诺拒绝大声失败，而不是默认的静默失败.
* [hard-rejection](https://github.com/sindresorhus/hard-rejection) - 使未处理的承诺拒绝立即失败而不是默认的静默失败
* [p-queue](https://github.com/sindresorhus/p-queue) - 具有并发控制的 Promise 队列
* [p-break](https://github.com/sindresorhus/p-break) - 打破承诺链
* [p-lazy](https://github.com/sindresorhus/p-lazy) - 创建延迟执行直到调用 .then() 或 .catch() 的惰性承诺
* [p-defer](https://github.com/sindresorhus/p-defer) - 创建延迟承诺
* [p-if](https://github.com/sindresorhus/p-if) - 条件承诺链
* [p-tap](https://github.com/sindresorhus/p-tap) - 在不影响其价值或状态的情况下进入承诺链
* [p-map](https://github.com/sindresorhus/p-map) - 同时映射承诺
* [p-all](https://github.com/sindresorhus/p-all) - 使用可选的有限并发并发运行承诺返回和异步函数
* [p-limit](https://github.com/sindresorhus/p-limit) - 以有限的并发运行多个承诺返回和异步函数
* [p-times](https://github.com/sindresorhus/p-times) - 同时运行承诺返回和异步函数特定次数
* [p-catch-if](https://github.com/sindresorhus/p-catch-if) - 条件承诺捕获处理程序
* [p-time](https://github.com/sindresorhus/p-time) - 测量承诺解决所需的时间
* [p-log](https://github.com/sindresorhus/p-log) - 记录承诺的价值/错误
* [p-filter](https://github.com/sindresorhus/p-filter) - 同时过滤承诺
* [p-settle](https://github.com/sindresorhus/p-settle) - 同时结算承诺并获得他们的履行价值或拒绝原因
* [p-memoize](https://github.com/sindresorhus/p-memoize) - 记住承诺返回和异步功能
* [p-whilst](https://github.com/sindresorhus/p-whilst) - 在条件返回 true 时重复调用函数，然后 resolve the promise
* [p-throttle](https://github.com/sindresorhus/p-throttle) - 限制承诺返回和异步功能
* [p-debounce](https://github.com/sindresorhus/p-debounce) - 消除承诺返回和异步功能
* [p-retry](https://github.com/sindresorhus/p-retry) - 重试承诺返回或异步功能
* [p-wait-for](https://github.com/sindresorhus/p-wait-for) - 等待条件为真
* [p-timeout](https://github.com/sindresorhus/p-timeout) - 在指定的时间后超时承诺
* [p-race](https://github.com/sindresorhus/p-race) - 更好的 `Promise.race()`
* [p-try](https://github.com/sindresorhus/p-try) - `Promise#try()` ponyfill - Starts a promise chain
* [p-finally](https://github.com/sindresorhus/p-finally) - `Promise#finally()` ponyfill - Invoked when the promise is settled regardless of outcome
* [p-any](https://github.com/sindresorhus/p-any) - 等待任何承诺被兑现
* [p-some](https://github.com/sindresorhus/p-some) - 等待指定数量的承诺被履行
* [p-pipe](https://github.com/sindresorhus/p-pipe) - 将承诺返回和异步函数组合成可重用的管道
* [p-each-series](https://github.com/sindresorhus/p-each-series) - 连续迭代承诺
* [p-map-series](https://github.com/sindresorhus/p-map-series) - 连续映射承诺
* [p-reduce](https://github.com/sindresorhus/p-reduce) - 使用 promises 将值列表简化为一个值的 promise
* [p-props](https://github.com/sindresorhus/p-props) - 类似于 `Promise.all()` 但用于 `Map` 和 `Object`

### Others
* [promise-method](https://github.com/wbinnssmith/promise-method)  - 独立的“bluebird.method”. 将一个同步返回的方法变成一个承诺返回的方法.
* [is-promise](https://github.com/then/is-promise) - 确定某些东西是否看起来像 Promise.
* [sprom](https://github.com/then/sprom)  - 解决流结束时的问题. 可选缓冲（小心这个！）
* [task.js](https://github.com/mozilla/task.js)  - 使用承诺和生成器以阻塞方式编写异步函数. 比如 `bluebird.coroutine`.
* [co](https://github.com/tj/co) - 类似于 `task.js` 和 `bluebird.coroutine`，但也支持 thunk.
* [lie-fs](https://www.npmjs.com/package/lie-fs) - Node 的 FS API 的承诺包装器.
* [promise-do-until](https://github.com/busterc/promise-do-until) - 重复调用一个函数，直到条件返回 true，然后 resolve promise.
* [promise-do-whilst](https://github.com/busterc/promise-do-whilst) - 在条件返回 true 时重复调用函数，然后解决承诺.
* [promise-semaphore](https://github.com/samccone/promise-semaphore) - 以可配置的串行方式推送一组要完成的工作
* [promise-nodeify](https://github.com/kevinoid/promise-nodeify) - 独立的 `nodeify` 方法，在解决或拒绝时调用 Node 风格的回调.

## License
根据许可 [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/).
