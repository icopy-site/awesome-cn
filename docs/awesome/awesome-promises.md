<div class="github-widget" data-repo="wbinnssmith/awesome-promises"></div>
<a href="https://promisesaplus.com/">
    <img src="https://promisesaplus.com/assets/logo-small.png" alt="Promises/A+ logo" align="right" />
</a>

## Awesome Promises [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; JavaScript Promises的有用资源的精选列表

灵感来自于 [awesome](https://github.com/sindresorhus/awesome)  列出的东西.  不要与其他令人敬畏的承诺相混淆，例如“我向你保证一百万美元”或“我保证你会保持健康，永远不必再去健身房”.



## Resources, Blogs, and Books

### For beginners
* [Promise Cookbook](https://github.com/mattdesl/promise-cookbook)   - 原因，内容和方式.  “简介[...]主要针对前端开发人员”.
* [Promises for Asynchronous Programming](http://exploringjs.com/es6/ch_promises.html) - 章节来自 [Exploring ES6](http://exploringjs.com/)
* [You Don't Know JS: Promises](https://github.com/getify/You-Dont-Know-JS/blob/master/async%20&%20performance/ch3.md) - 章节来自 [You Don't Know JS: Async & Performance](https://github.com/getify/You-Dont-Know-JS/tree/master/async%20%26%20performance)
* [JavaScript Promises: an Introduction](https://developers.google.com/web/fundamentals/getting-started/primers/promises) -  JavaScript本机承诺实现的基础知识.
* [JavaScript with Promises](http://shop.oreilly.com/product/0636920032151.do)   - 来自O&#39;Reilly.  精炼到位.  使用原生和蓝鸟.
* [Promise it won't hurt](https://github.com/stevekane/promise-it-wont-hurt) - 互动 [nodeschool](https://nodeschool.io/) 作坊
* [ES6 Kata Promises](http://es6katas.org/) -  Promises Katas： [Basics](http://tddbin.com/#?kata=es6/language/promise/basics)
* [ES6 Promises in Depth](https://ponyfoo.com/articles/es6-promises-in-depth)
* [An Incremental Tutorial on Promises](http://www.sohamkamani.com/blog/2016/08/28/incremenal-tutorial-to-promises/) - 面向初学者的常见问题解答风格教程.

### Deep Dive
* [Promise Fun](https://github.com/sindresorhus/promise-fun) -  @ sindresorhus的常见Promise问题的注释，模式和解决方案
* [You're Missing the Point of Promises](https://blog.domenic.me/youre-missing-the-point-of-promises/) -  Promise不仅仅是回调聚合，而jQuery的实现（3.0之前）是不够的.
* [We have a problem with promises](https://pouchdb.com/2015/05/18/we-have-a-problem-with-promises.html) - “我们中的许多人在没有真正理解他们的情况下使用承诺.”
* [Promise anti-patterns](https://github.com/petkaantonov/bluebird/wiki/Promise-anti-patterns) - 常见的误用以及如何避免它们.
* [Promise anti-patterns (2)](http://taoofcode.net/promise-anti-patterns/) - 另一套承诺反模式
* [Promise Ponderings, (Anti-)Patterns, and Apologies](https://sdgluck.github.io/2015/08/24/promise-ponderings-patterns-apologies/) - 承诺行为通过常见问题及其答案得到证明和解释.
* [Javascript Promises...In Wicked Detail](http://www.mattgreer.org/articles/promises-in-wicked-detail/) - 重新创建promise实现
* [Writing Promise-Using Specifications](https://www.w3.org/2001/tag/doc/promises-guide) - “本文档提供了有关如何编写创建，接受或操纵承诺的规范的指导”
* [Async functions - making promises friendly](https://developers.google.com/web/fundamentals/getting-started/primers/async-functions)

### References
* [Promises/A+ specification](https://promisesaplus.com/)
* [caniuse promises](http://caniuse.com/#feat=promises)
* [Fates and States](https://github.com/domenic/promises-unwrapping/blob/master/docs/states-and-fates.md) - 快速定义可能的状态.
* [Promisees](https://bevacqua.github.io/promisees/) - 为冒险者提供可视化的游乐场.

## Promises/A+ Implementations (ES6/ES2015 compatible)

### Strict Implementations
 这些实现不超过或少于es6规范.  它们可以制成出色的填充剂，并且与原生承诺非常相容.

* [pinkie](https://github.com/floatdrop/pinkie)   -  Ponyfill.  面向节点，但是 [browserifyable](https://github.com/substack/node-browserify) .  *极其小*的实施.
* [native-promise-only](https://github.com/getify/native-promise-only)   -  Polyfill.  浏览器和节点兼容.
* [es6-promise](https://github.com/stefanpenner/es6-promise)   - 选择性填充.  rsvp.js的严格规范子集
* [lie](https://github.com/calvinmetcalf/lie) - 小巧，可浏览，并具有选择性填充.

### Implementations with extras
 所有这些都提供了比语言更多的功能，但仍保持兼容.  节点+浏览器适合所有人.

* [bluebird](https://github.com/petkaantonov/bluebird)   - 功能齐全，性能极佳.  长堆栈跟踪和发电机/协程支持.
* [creed](https://github.com/briancavalier/creed)   - 像Bluebird一样的高性能和全功能，但面向FP.  协同程序，生成器，承诺，ES2015迭代，幻想土地规范.
* [rsvp.js](https://github.com/tildeio/rsvp.js/)   - 轻量级，额外的一些.  兼容IE6！
* [Q](https://github.com/kriskowal/q)   - 原始实现之一.  长堆栈痕迹和其他好东西.
* [then/promise](https://github.com/then/promise) - 使用`nodeify`，`denodify`和`done（）`添加小.
* [when.js](https://github.com/cujojs/when) - 包含控制流程，功能和实用方法.


### Fallbacks
* [native-or-bluebird](https://www.npmjs.com/package/native-or-bluebird) - 帮助过渡到完全原生.
* [pinkie-promise](https://github.com/floatdrop/pinkie-promise)   - 使用原生，或回到&#39;小指&#39;.  非常适合节点库作者.
* [any-promise](https://github.com/kevinbeaty/any-promise)   - 加载第一个可用的实现.  浏览器安全.

## Convenience Utilities
 本机和严格符合规范的承诺对于兼容性，面向未来，库作者和浏览器而言非常棒.  但是，像bluebird这样的库会将好东西打包到`Promise`构造函数和原型上.  解？  当然很小的模块！

### sindresorhus's many Promise utilities ([see notes](https://github.com/sindresorhus/promise-fun))
* [delay](https://github.com/sindresorhus/delay) - 延迟承诺指定的时间.
* [pify](https://github.com/sindresorhus/pify) -  Promisify（“denodify”）一个回调式函数.
* [loud-rejection](https://github.com/sindresorhus/loud-rejection) - 使未处理的承诺拒绝大声失败而不是默认的无声失败.
* [hard-rejection](https://github.com/sindresorhus/hard-rejection) - 使未处理的承诺拒绝立即失败，而不是默认的无声失败
* [p-queue](https://github.com/sindresorhus/p-queue) - 使用并发控制的Promise队列
* [p-break](https://github.com/sindresorhus/p-break) - 打破承诺链
* [p-lazy](https://github.com/sindresorhus/p-lazy) - 创建一个延迟执行的延迟，直到调用`.then（）`或`.catch（）`
* [p-defer](https://github.com/sindresorhus/p-defer) - 创建延期承诺
* [p-if](https://github.com/sindresorhus/p-if) - 有条件的承诺链
* [p-tap](https://github.com/sindresorhus/p-tap) - 点击承诺链而不影响其价值或状态
* [p-map](https://github.com/sindresorhus/p-map) - 同时映射承诺
* [p-all](https://github.com/sindresorhus/p-all) - 使用可选的有限并发运行promise-returns和async函数
* [p-limit](https://github.com/sindresorhus/p-limit) - 运行具有有限并发性的多个promise-returns和async函数
* [p-times](https://github.com/sindresorhus/p-times) - 同时运行promise-returns和async函数特定次数
* [p-catch-if](https://github.com/sindresorhus/p-catch-if) - 条件承诺捕获处理程序
* [p-time](https://github.com/sindresorhus/p-time) - 衡量承诺解决的时间
* [p-log](https://github.com/sindresorhus/p-log) - 记录承诺的值/错误
* [p-filter](https://github.com/sindresorhus/p-filter) - 同时过滤承诺
* [p-settle](https://github.com/sindresorhus/p-settle) - 同时解决承诺并获得履行价值或拒绝原因
* [p-memoize](https://github.com/sindresorhus/p-memoize) -  Memoize promise-returns和async函数
* [p-whilst](https://github.com/sindresorhus/p-whilst) - 当条件返回true时重复调用函数，然后解析promise
* [p-throttle](https://github.com/sindresorhus/p-throttle) - 节流承诺 - 返回和异步功能
* [p-debounce](https://github.com/sindresorhus/p-debounce) - 去抖承诺 - 返回和异步功能
* [p-retry](https://github.com/sindresorhus/p-retry) - 重试promise-returns或async函数
* [p-wait-for](https://github.com/sindresorhus/p-wait-for) - 等待条件成立
* [p-timeout](https://github.com/sindresorhus/p-timeout) - 在指定的时间后超时承诺
* [p-race](https://github.com/sindresorhus/p-race) - 更好的`Promise.race（）`
* [p-try](https://github.com/sindresorhus/p-try) - `Promise#try()` ponyfill - Starts a promise chain
* [p-finally](https://github.com/sindresorhus/p-finally) - `Promise#finally()` ponyfill - Invoked when the promise is settled regardless of outcome
* [p-any](https://github.com/sindresorhus/p-any) - 等待任何承诺得到履行
* [p-some](https://github.com/sindresorhus/p-some) - 等待达到指定数量的承诺
* [p-pipe](https://github.com/sindresorhus/p-pipe) - 将promise-returns和async函数编写到可重用的管道中
* [p-each-series](https://github.com/sindresorhus/p-each-series) - 连续迭代承诺
* [p-map-series](https://github.com/sindresorhus/p-map-series) - 按顺序映射承诺
* [p-reduce](https://github.com/sindresorhus/p-reduce) - 使用promises将值列表减少为值的承诺
* [p-props](https://github.com/sindresorhus/p-props) - 像`Promise.all（）`，但是对于`Map`和`Object`

### Others
* [promise-method](https://github.com/wbinnssmith/promise-method)   - 独立`bluebird.method`.  将同步返回方法转换为promise返回方法.
* [is-promise](https://github.com/then/is-promise) - 确定某些东西是否像Promise.
* [sprom](https://github.com/then/sprom)   - 流结束时解析.  可选缓冲（小心这个！）
* [task.js](https://github.com/mozilla/task.js)   - 使用promises和generator以阻塞样式编写异步函数.  喜欢`bluebird.coroutine`.
* [co](https://github.com/tj/co) - 像`task.js`和`bluebird.coroutine`，但也支持thunks.
* [lie-fs](https://www.npmjs.com/package/lie-fs) - 承诺Node的FS API的包装器.
* [promise-do-until](https://github.com/busterc/promise-do-until) - 重复调用函数，直到条件返回true，然后解析promise.
* [promise-do-whilst](https://github.com/busterc/promise-do-whilst) - 当条件返回true时重复调用函数，然后解析promise.
* [promise-semaphore](https://github.com/samccone/promise-semaphore) - 以可配置的串行方式完成一系列工作
* [promise-nodeify](https://github.com/kevinoid/promise-nodeify) - 独立的`nodeify`方法，在解析或拒绝时调用节点式回调.

## License
许可证下 [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/).
