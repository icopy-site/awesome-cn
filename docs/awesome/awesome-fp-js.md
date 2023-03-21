<div class="github-widget" data-repo="stoeffel/awesome-fp-js"></div>
## Awesome FP JS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

这是一个很棒的精选列表 [functional programming](https://en.wikipedia.org/wiki/Functional_programming)  JavaScript 的代码和学习资源. 作为一种多范式编程语言，JavaScript 可以用多种风格编写. 通过这些资源，我们希望帮助您更好地利用 JavaScript 的支持以_功能性_方式编写程序.

函数式编程是一个 [style of programming](https://wiki.haskell.org/Functional_programming) 它将计算建模为表达式的评估. 将此与命令式编程进行对比，在命令式编程中，程序由在执行时更改全局状态的语句组成. 函数式编程通常避免使用可变状态，而倾向于使用_side-effect free_函数和_immutable_数据. 这鼓励编写易于推理的可组合和声明性程序.



##### Tags
这些可以附加到条目中. 每一个都应该以“+”或“-”开头，以指示标签含义的存在或不存在.  “-”标签应该只在它们可能帮助某人根据他们的需要过滤库时包含. 例如，`-TS` 标签可能对 Typescript 用户筛选类型有用，但 `-CT` 标签不太可能对任何人都有帮助.

 * __CT__. 范畴论. 该库似乎受到 Haskell、Scala 或其他以范畴论为基础的函数式语言库的启发.
 * __TS__. 打字稿. 这个库有打字稿类型.

## Libraries

* [Ramda](https://github.com/ramda/ramda)  – 一个实用的 JavaScript 函数库，专为函数式编程风格而设计. 一种可以轻松创建功能性管道并且从不改变用户数据的样式.  +TS.
* [Ramda Adjunct](https://github.com/char0n/ramda-adjunct) 是社区维护的 Ramda 扩展.
* [Ramda-extension](https://github.com/tommmyy/ramda-extension) 是仅由 Ramda 函数组成的无效用点函数集.
* [Rambda](https://github.com/selfrefactor/rambda) - 比 Ramda 更快的替代品，不到 10kB.
* [Rambdax](https://github.com/selfrefactor/rambdax) - 扩展版的 Rambda
* [Folktale](http://folktale.origamitower.com/)  – 用于 JavaScript 函数式编程的标准库.  Typescript 支持预计在 2020 年年中.  -TS.
* [lodash/fp](https://github.com/lodash/lodash/wiki/FP-Guide) – 一个实例 [Lodash](https://github.com/lodash/lodash) 其方法被包装以产生不可变的、自动柯里化的、迭代优先的、数据最后的方法.  +TS.
* [functional.js](https://github.com/functionaljs/functional-js) – 一个轻量级函数式 JavaScript 库，有助于柯里化和无点/默认编程.
* [101](https://github.com/tjmehta/101)  – 一个现代的模块化 JavaScript 实用程序库，可以很好地与 vanilla JavaScript 方法配合使用.  -TS
* [fnuc](https://github.com/algesten/fnuc) – 用于 CoffeeScript（和 JavaScript）的功能库，以促进功能组合和高阶功能.
* [barely-functional](https://github.com/cullophid/barely-functional)  – 使用本机 ES5/6 操作的微型 (2.7kb) 函数式编程库.  -TS.
* [bluebird-promisell](https://github.com/zhangchiqing/bluebird-promisell) - 一个实用的 promises 函数式编程库.
* [prelude.ls](http://gkz.github.io/prelude-ls/)  – 一个功能导向的实用程序库，在某种程度上基于 Haskell 的 Prelude 模块.  -TS.
* [preludejs](https://github.com/alanrsoares/prelude-js)  - JavaScript 的硬核函数式编程.  -TS.
* [1-liners](https://github.com/1-liners/1-liners)  – 再简单不过的功能性工具. 一款极简实用的实用腰带，以爱心和专注手工打造.  -TS.
* [fn-curry](https://github.com/thunklife/fn-curry) – 柯里化函数的简单函数.
* [curry](https://github.com/thisables/curry) – 使用函数绑定语法柯里化您的函数.
* [compose-function](https://github.com/stoeffel/compose-function) – 从更小的函数组成一个新函数.
* [functionize](https://github.com/paldepind/functionize) – 有助于使非功能性库发挥作用的功能集合.
* [lambdajs](https://github.com/loop-recur/lambdajs) – 完整的 ECMAScript API 以功能方式完成.
* [fp-dom](https://github.com/fp-dom/) – 使 DOM 功能化.
* [react-on-lambda](https://github.com/sultan99/react-on-lambda) - 用函数（柯里化、组合等）替换 React 中的 JSX. 
* [trifl](https://github.com/algesten/trifl) – 具有单向数据流和虚拟 dom 的功能性用户界面库.
* [funcy](https://github.com/bramstein/funcy)  – 向 JavaScript 添加功能模式匹配的实验.  _Experimental_ :triangular_flag_on_post:
* [date-fp](https://github.com/cullophid/date-fp)  – 用于处理 JavaScript 日期的功能实用程序库.  date-fp 中的所有函数都是纯粹的、自动柯里化的，并且不会改变它们所应用的日期对象.
* [js-joda](https://github.com/js-joda/js-joda) – 一个不可变的日期和时间库，提供基于 ISO8601 日历的简单、域驱动和干净的 API.
* [\_part\_](https://github.com/AutoSponge/_part_) – 一个微型库，它通过将本机方法作为部分应用函数提供来鼓励函数式编程.
* [claire](https://github.com/robotlolita/claire) – 基于属性的测试库，用于明确指定代码不变量和行为.
* [FPO.js](https://github.com/getify/fpo)  – Kyle Simpson（又名 getify）的 JavaScript FP 库. 支持命名参数样式方法.
* [Javascript Parser Combinator](https://github.com/d-plaindoux/parsec) – 受 Haskell 的 Parsec 启发的 Javascript 解析器组合器实现
* [fun-task](https://github.com/rpominov/fun-task) – An abstraction for managing asynchronous code in JS. Tasks are similar to Promises with the key difference that Tasks can represent a computation while Promises can represent only the results of a computation. Ships with Flow type definitions.
* [most](https://github.com/cujojs/most) – 超高性能反应式编程，可帮助您在值流和事件流上编写异步操作，而没有许多副作用和可变共享状态的危险.
* [zen-signals](https://github.com/joaomilho/zen-signals) – ☯ 最简单的信号库
* [funfix](https://github.com/funfix/funfix)  – Funfix 是一个类型类和数据类型库，用于 JavaScript、TypeScript 和 Flow 中的函数式编程.  +CT，+TS.
* [pico-lambda](https://github.com/trainyard/pico-lambda)  - 数组、字符串和函数式的东西. 基于本机方法的 640b 函数库.  -TS.
* [pareto-js](https://github.com/concretesolutions/pareto.js/) - 一个非常小、直观和快速的 JavaScript 功能实用程序库 -TS.
* [fpEs](https://github.com/TeaEntityLab/fpEs/)  - 一个小型库提供基本 FP &amp; pattern-matching/sumtype &amp; MonadIO/Rx &amp; Optional for Javascript 的简单用法.  -TS.
* [Creed](http://blog.briancavalier.com/creed/)  – 具有高级功能的复杂且注重功能的异步：协程、承诺、ES2015 可迭代对象、幻想世界.  -TS.
* [TGrid](https://github.com/samchon/tgrid) - 网格计算框架，网络和线程扩展 [TSTL](https://github.com/samchon/tstl) ，支持RFC（远程函数调用）.  +TS.
* [Ferrum](https://github.com/adobe/ferrum)  – 迭代器库，支持对象作为可迭代对象、惰性求值和`pipe()`； 在 JS 中实现特征（来自 Rust）/类型类（来自 Haskell）.  -TS.
* [fp-ts](https://gcanti.github.io/fp-ts/)  - TypeScript 中的类型化函数式编程.  +CT，+TS.
* [iter-tools](https://github.com/iter-tools/iter-tools)  - 用于处理同步和异步可迭代对象的丰富工具集.  +TS.
* [remeda](https://remedajs.com/) 一个大致子集 Ramda 的函数库，但用 Typescript 编写，因此对类型更友好.  +TS.
* [futil-js](https://github.com/smartprocure/futil-js) - 功能实用程序的集合，可以想象它们是像 lodash/fp 这样的库的一部分，但由于某种原因或其他原因不是.
* [rubico](https://github.com/a-synchronous/rubico) - [a]同步功能语法
* [rocket-pipes](https://github.com/darky/rocket-pipes)  - 强大的管道，将 Promise 和 ADT 链接起来，例如流行的 FP 库中的 Maybe 或 Either.  +TS
* [omg-curry](https://github.com/Debdut/omg-curry) - 综合 Curry 库，包括 Operator Curry、函数 Curry、Decurry 和 Infinite Curries.
* [lfi](https://github.com/TomerAberbach/lfi) - 支持同步、异步和并发迭代的惰性函数迭代库.
* [ts-multimethod](https://github.com/darky/ts-multimethod)  - 受 Clojure 多方法启发的 TypeScript 多方法.  +TS
* [ts-fp-di](https://github.com/darky/ts-fp-di)  - 基于 Node.js AsyncLocalStorage 的微型 TypeScript 功能依赖注入.  +TS
* [effect-ts](https://github.com/Effect-TS/core)  – 具有丰富标准库的成熟的打字稿功能效果系统.  +TS
* [qio](https://github.com/tusharmath/qio)  – 一种类型安全、功能性、高性能、合法、可组合的数据结构，解决了节点和浏览器中有效代码的实际问题.  +TS
* [Ditox.js](https://github.com/mnasyrov/ditox)  - 用于构建模块化应用程序的强大依赖注入容器.  +TS
* [RxEffects](https://github.com/mnasyrov/rx-effects)  - 使用 RxJS 进行反应式状态和效果管理.  +TS
* [fxts](https://github.com/marpple/FxTS)  - 延迟评估和并发.  +TS
* [ts-belt](https://mobily.github.io/ts-belt/)  - TypeScript 中 FP 的快速、现代和实用的实用程序库.  （使用像 remeda 这样的数据优先方法，但是 [faster](https://mobily.github.io/ts-belt/benchmarks/v3.7.0/macbook-air-2020) 比 remeda、ramda、rambda 和 lodash/fp.）
* [fp-multik](https://github.com/lulldev/fp-multik) - JS/TS 轻量级值多方法实用程序
* [true-myth](https://github.com/true-myth/true-myth) TypeScript 中用于安全、惯用 null 和错误处理的库，具有“Maybe”和“Result”类型，支持函数式风格和更传统的方法调用风格
* [ts-pattern](https://github.com/gvergnaud/ts-pattern)  - 详尽的 TypeScript 模式匹配库，具有智能类型推断. 模式匹配是一种来自 FP 语言的代码分支技术.

### Data Structures

通过为任务使用正确的数据结构来编写高性能的功能代码.

* [Icepick](https://github.com/aearly/icepick) 将冻结的 JavaScript 对象视为持久不可变集合的实用程序
* [Immutable.js](https://github.com/facebook/immutable-js) – 不可变的持久数据集合.
* [Immer](https://github.com/mweststrate/immer)  – Immer 是一个基于写时复制机制的不可变状态的微型包.  +TS.
* [Mori](https://github.com/swannodette/mori) – ClojureScript 的持久数据结构和支持来自 vanilla JavaScript 的 API.
* [Baobab](https://github.com/Yomguithereal/baobab) – 具有游标的持久且可选的不可变数据树.
* [immutable-sequence.js](https://github.com/qiao/immutable-sequence.js) – 不可变序列在 JavaScript 中的高性能实现，基于 [Finger Trees](https://github.com/qiao/fingertree.js).
* [Timm](http://guigrpa.github.io/timm/) – 具有快速读取和可接受写入的不变性助手.
* [Lazy.js](https://github.com/dtao/lazy.js) – 一个在引擎盖下带有惰性引擎的实用程序库，它力求在尽可能灵活的同时尽可能少地工作.
* [DerivableJS](https://github.com/ds300/derivablejs)  – JavaScript 和 TypeScript 的功能反应状态.  DerivableJS 使您能够就您的状态位如何相关做出优雅的声明性陈述.  +TS.
* [imlazy](https://github.com/benji6/imlazy) – 使用 ES2015 迭代协议创建和操作惰性迭代的库.
* [collectable](https://github.com/frptools/collectable)  – 用于现代 JavaScript 和 TypeScript 应用程序的超高性能不可变数据结构.  +TS.
* [List](https://github.com/funkia/list)  - 一个非常快速的不可变列表，具有全面的功能 API. 旨在 [seamlessly integrate with Ramda](https://github.com/funkia/list#seamless-ramda-integration).
* [prelude.ts](https://github.com/emmanueltouzery/prelude.ts)  - 不可变持久集合、函数构造（例如 Option 和 Either）以及组合器. 在 Typescript 中实现，但也支持 javascript.  +CT，+TS.
* [TSTL](https://github.com/samchon/tstl)  - C++ STL（标准模板库）在 TypeScript 中实现. 提供遵循函数式编程规则的 STL 容器、迭代器、算法和仿函数.  +TS.

### Algebraic Data Types

Use the laws of math instead of always reinventing your own thing. Algebraic!

* [Fantasy Land](https://github.com/fantasyland/fantasy-land) – 不是图书馆，而是图书馆要遵循的 Monad 法则规范.
* [Static Land](https://github.com/rpominov/static-land) – 类似于 Fantasy Land 的规范，但基于静态方法而不是实例方法.
* [immutable-ext](https://github.com/DrBoolean/immutable-ext) – FantasyLand 扩展 [Immutable.js](https://github.com/facebook/immutable-js).
* [daggy](https://github.com/puffnfresh/daggy) – 用于创建标记构造函数的库.
* [Sanctuary](https://github.com/plaid/sanctuary)  – Sanctuary 使编写安全代码而不进行空检查成为可能.  +CT，+TS.
* [monet.js](http://cwmyers.github.io/monet.js/)  – 一个通过提供丰富的 Monad 和其他有用函数来辅助函数式编程的库.  +CT，+TS.
* [union-type](https://github.com/paldepind/union-type) – 用于定义和使用联合类型的小型 JavaScript 库.
* [freeky](https://github.com/DrBoolean/freeky) – 免费单子的集合.
* [Fluture](https://github.com/Avaq/Fluture) – 包含控制实用程序、高性能和大量错误消息的 Future 库.
* [fantasy-combinators](https://github.com/fantasyland/fantasy-combinators) – 公共组合器.
* [fantasy-birds](https://github.com/fantasyland/fantasy-birds)  – Haskell 包 Data.Aviary.Birds 的端口. 一切满足您的组合需求.
* [crocks](https://github.com/evilsoft/crocks)  – 流行的代数数据类型的集合，其主要目标是策划和提供不仅是每种类型之间的通用接口，而且还包括开始运行所需的所有辅助函数.  -TS.
* [kudo-js](https://github.com/blitzritz/kudojs) - 一个带有一组代数数据类型和辅助函数的小型实用程序库，可帮助您在 Javascript 中以函数式编程风格编写代码
* [purify](https://github.com/gigobyte/purify) - Functional programming library for TypeScript focusing on ADTs.  +CT, +TS.
* [MojiScript](https://github.com/joelnet/MojiScript)- 一种异步优先、自以为是的函数式语言，旨在与 JavaScript 引擎 100% 兼容
* [Pratica](https://github.com/rametta/pratica)  - 小型、简单、易用的 FP 数据类型，适用于需要快速交付可靠代码的务实和高效的开发人员.  +CT，+TS.
* [Tifi](https://github.com/mobily/tifi)  - Tifi 是一个用于 TypeScript 函数式编程的库. 它解决了同时存在 `undefined` 和 `null` 的问题.  Tifi 的灵感来自选项数据类型的 OCaml/Reason 实用程序.  +CT，+TS.

### Lenses

* [lenses](https://github.com/DrBoolean/lenses) – 可组合 [kmett](https://github.com/ekmett/lens) 款式镜片.
* [optics](https://github.com/flunc/optics) – Profunctor 光学器件（镜头、棱镜、iso）.
* [ramda-lens](https://github.com/ramda/ramda-lens) – :ram: :mag_right：基于 Ramda 构建的镜头库.
* [fantasy-lenses](https://github.com/fantasyland/fantasy-lenses)  – 可组合的、不可变的 getter 和 setter.  （Profunctor 镜片 WIP）
* [nanoscope](https://github.com/5outh/nanoscope) – 带圆点支撑的镜头.
* [partial.lenses](https://github.com/calmm-js/partial.lenses) – Partial lenses 是一个全面的、高性能的 JavaScript 光学库.
* [shades](https://github.com/jamesmcnamara/shades) – 受 lodash 启发的 Javascript 类镜头库.

## Functional Languages that Compile to JavaScript

* [ClojureScript](https://github.com/clojure/clojurescript) – 编译 [Clojure](http://clojure.org/)，一个托管的 Lisp，具有不可变的持久数据结构，到 JavaScript.
* [Elm](http://elm-lang.org/)  – 一种类型安全的函数式编程语言，用于以声明方式创建基于 Web 浏览器的图形用户界面. 在 Haskell 中实现.
* [Fable](http://fable.io/) - 编译 [F#](http://fsharp.org) 到可读的 JavaScript.
* [PureScript](http://www.purescript.org/) – 一种编译为 JavaScript 的小型强类型编程语言.
* [Idris](http://www.idris-lang.org/) – 具有依赖类型的通用纯函数式编程语言.
* [GHCJS](https://github.com/ghcjs/ghcjs) – [Haskell](https://www.haskell.org/) 到基于 GHC 的 JavaScript 编译器.
* [ElixirScript](https://github.com/bryanjos/elixirscript) – 编译一个子集 [Elixir](http://elixir-lang.org/)，一种动态的函数式语言，旨在为 JavaScript 构建可扩展和可维护的应用程序.
* [Js\_of\_ocaml](http://ocsigen.org/js_of_ocaml/) – 编译 [OCaml](http://ocaml.org/) 字节码到 JavaScript，使得在浏览器中运行 OCaml 程序成为可能.
* [Reason](https://reasonml.github.io) – Reason 是 OCaml 的新接口，OCaml 是 ML 语言的一种高度表达的方言，具有类型推断和静态类型检查的特点.
* [ReScript](https://rescript-lang.org/) –（以前称为 [Bucklescript](https://rescript-lang.org/bucklescript-rebranding)) ReScript 是一种类型安全的语言，可以编译为最高质量的干净、可读和高性能的 JavaScript 代码.
* [Scala.js](http://www.scala-js.org/) – 编译 [Scala](http://www.scala-lang.org/) 到 JavaScript.
* [LiveScript](http://gkz.github.io/LiveScript/) – LiveScript 直接映射到 JavaScript，允许您编写没有重复样板的富有表现力的代码.
* [Quack](https://github.com/quack/quack) - 一种多范式编程语言，具有针对 PHP 和 JS 的渐进和鸭子类型.
* [ion](https://github.com/ion-lang/ion) - 没有 BS JS
* [RamdaScript](https://github.com/yosbelms/ramdascript) - 在 RamdaJS 之上编译成自以为是的 JavaScript 的 Lisp
* [RacketScript](https://github.com/vishesh/racketscript) – RacketScript 旨在利用 JavaScript 和 Racket 的生态系统，并使它们之间的互操作性干净顺畅.
* [Koka](https://www.microsoft.com/en-us/research/project/koka/) – Koka 是一种面向函数的编程语言，它使用熟悉的类似 JavaScript 的语法将纯值与副作用计算分开.
* [TypeScript](https://www.typescriptlang.org/) - TypeScript 是 JavaScript 的类型化超集，可编译为纯 JavaScript.
* [Gleam](https://gleam.run) - Gleam 是一种类型化的函数式语言，可编译为 Erlang 和 JavaScript.

## Programming Tools

* [eslint-plugin-fp](https://github.com/jfmengels/eslint-plugin-fp) - 函数式编程的 ESLint 规则
* [4.5](https://github.com/TylorS/4.5)  – 功能断言库. 如果您更喜欢 JavaScript 中的函数式风格 API 和实践，这个库旨在通过面向函数的惰性断言和单子断言来解决这个问题.
* [hm-def](https://github.com/xodio/hm-def) – 使用 Hindley Milner 签名对 JS 进行运行时类型检查.
* [ftor](https://github.com/kongware/ftor) - 可插入的运行时类型检查器和功能调试工具，通过 Scott 编码支持参数和行多态性、隐式 rank-2 类型和代数数据类型.

## Resources

### Books

* [Professor Frisby’s Mostly Adequate Guide to Functional Programming](https://github.com/MostlyAdequate/mostly-adequate-guide)  – 这是一本关于函数式范式的书，使用世界上最流行的函数式编程语言：JavaScript. 这是一个实用的介绍，通过现实世界的例子建立直觉. 强力推荐. 经过 [Brian Lonsdorf](https://twitter.com/drboolean) (2016)
* [Functional-Light JavaScript](https://github.com/getify/functional-light-js)  – 本书探讨了可应用于 JavaScript 的函数式编程 (FP) 的核心原则. 但这本书的不同之处在于它在探讨这些原则时没有使用所有繁重的术语.
* [JavaScript Allongé](https://leanpub.com/javascriptallongesix) ，“六”版. 从尽可能少的功能开始——但也不少！  – 并建立强大的组合器和装饰器. 一本基础书. 经过 [Reginald  Braithwaite](https://github.com/raganwald) (2016)
* [Functional Programming in JavaScript](https://www.manning.com/books/functional-programming-in-javascript) 教授 JavaScript 开发人员功能技术，这些技术将提高可扩展性、模块化、可重用性、可测试性和性能. 本书通过具体的例子和通俗易懂的解释，教你如何将函数式编程应用到现实生活中的开发任务中. 路易斯·阿滕西奥 (2016)
* [Eloquent JavaScript](http://eloquentjavascript.net/) . 使用 JavaScript 进行编程的现代介绍. 作者：马金·哈弗贝克 (2014)
* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) 教授如何使用 JavaScript 的函数式编程支持创建美观、安全且易于理解和测试的代码. 经过 [Michael Fogus](https://github.com/fogus) (2013)
* [Grokking Simplicity](https://www.manning.com/books/grokking-simplicity) 从第一原则讲授函数式编程. 它的所有代码示例都使用 JavaScript，并且使用真实场景. 经过 [Eric Normand](https://github.com/ericnormand) (2019)
* [scriptum](https://github.com/kongware/scriptum/blob/master/README.md) - 简洁的函数式编程库和基于它的在线课程

### Articles

* [FP Concepts in JavaScript](https://medium.com/@collardeau/intro-to-functional-programming-concepts-in-javascript-b0650773139c)  – 介绍 JavaScript 中的函数式编程概念. 使用 Ramda 库通过最简单的示例来教授组合、无点样式和仿函数的概念.
* [Functional programming with JavaScript](http://stephen-young.me.uk/2013/01/20/functional-programming-with-javascript.html) – JavaScript 函数式编程的另一篇介绍，重点关注三个关键主题：作为函数应用的计算、无状态、避免副作用.
* [A gentle introduction to functional JavaScript](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro/) – 一个由四部分组成的系列介绍 JavaScript 中的函数式编程，让您快速了解关于函数式编程的所有炒作的全部内容.
* [Functors from first principle - explained with JS](https://dev.to/snird/functors-from-first-principle-37lh) - 使用 JavaScript 解释函子概念.
* [Why Curry Helps](https://hughfdjackson.com/javascript/why-curry-helps/) – 简要概述如何使用柯里化编写可重用和声明性代码.
* [Favoring Curry](http://fr.umio.us/favoring-curry/) - 使用 Ramda 进行柯里化的实际应用.
* [Functional Mumbo Jumbo – ADTs](http://blog.jenkster.com/2016/06/functional-mumbo-jumbo-adts.html) – 对初学者友好的代数数据类型介绍.
* [JavaScript and Type Thinking](https://medium.com/@yelouafi/javascript-and-type-thinking-735edddc388d)  – 学习使用_type thinking_ 推理您的 JavaScript 代码. 引入代数数据类型作为推理程序实体的概念基础.
* [Lazy, composable, and modular JavaScript](https://codewords.recurse.com/issues/four/lazy-composable-and-modular-javascript) – 使用 ES6 的四个新特性——可迭代、生成器、粗箭头和 for-of——结合高阶函数、函数组合和惰性求值，编写更简洁、更模块化的 JavaScript.
* [Why Ramda](http://fr.umio.us/why-ramda/)  – 对于那些不习惯函数式编程的人来说，Ramda 似乎毫无用处. 然而，它确实提供了一种不同的编码风格，这种风格在纯函数式编程语言中是理所当然的：Ramda 使您可以通过函数组合轻松构建复杂的逻辑.
* [Monads in JavaScript](https://curiosity-driven.org/monads-in-javascript) – 介绍 JavaScript 中的 Monad 设计模式.
* [A Monad in Practicality: First-Class Failures](http://robotlolita.me/2013/12/08/a-monad-in-practicality-first-class-failures.html) – 浏览 JavaScript 中特定 monadic 结构的一些实际用例：使用“Maybe”monad 处理简单的失败案例，并使用“Either”monad 或“Validation”应用仿函数对更复杂的场景进行建模.
* [Functional programming](https://glebbahmutov.com/blog/tags/functional/) – Gleb Bahmutov 撰写的关于 JavaScript 函数式编程各个方面的许多文章.
* [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon) – 用 Ja​​vaScript 解释的函数式编程世界的行话.
* [Data Structures in JavaScript](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/) – 一系列用 JavaScript 重新实现各种数据结构的博客文章，以更好地了解它们的优点和缺点.
* [So You Want to be a Functional Programmer](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536) - 通俗易懂，通过一些示例，介绍了 Javascript 和 Elm 中的函数式编程.
* [Functional Programming for JavaScript People](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504) - Chet Corcos 对函数式编程模式的完整介绍，包含大量 javascript 示例.
* [Introduction to Immutable.js and Functional Programming Concepts](https://auth0.com/blog/intro-to-immutable-js/) - 在 Facebook 流行的 JavaScript 库：Immutable.js 的概述中了解函数式数据结构及其用途.
* [Master the JavaScript Interview: What is Functional Programming?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0) - @ericelliott 对功能原理和词汇的简单介绍.
* [Composing Software](https://medium.com/javascript-scene/the-rise-and-fall-and-rise-of-functional-programming-composable-software-c2d91b424c8c) - 由 @ericelliott 从头开始​​学习 JavaScript ES6+ 中的函数式编程和组合软件技术的系列文章.
* [Anonymous Recursion in JavaScript](https://dev.to/simov/anonymous-recursion-in-javascript) - 关于在 JavaScript 中实现匿名递归的简短易懂的文章.
* [Functional Composition in Javascript](https://joecortopassi.com/articles/functional-composition-in-javascript/) – 逐步解释如何在 javascript 中组合函数.
* [Functional Programming Principles in Javascript](https://medium.freecodecamp.org/functional-programming-principles-in-javascript-1b8fc6c3563f) - 实用代码示例，用于学习纯函数、不变性、一流实体和高阶函数等函数式编程概念
* [Basic Monads in Javascript](https://dev.to/rametta/basic-monads-in-javascript-3el3) - 介绍 2 个简单的 Javascript 单子，Maybe 和 Either.
* [F# for JavaScript Devs](https://dev.to/rametta/f-for-js-devs-2b88) - Showcasing the similarities between F# and JavaScript
* [A practical guide to writing more functional Javascript](https://medium.com/@nadeesha/a-practical-guide-to-writing-more-functional-javascript-db49409f71) - 将命令式 JavaScript 转换为更具声明性、功能性的 JavaScript 的分步指南.
* [You don't (may not) need loops ➿](https://github.com/you-dont-need/You-Dont-Need-Loops) - 循环是初级程序员最先学习的结构之一，但它们会在软件开发过程中带来许多潜在问题，并且在许多情况下可以避免.

### Videos

* [Classroom Coding with Prof. Frisby](https://www.youtube.com/watch?v=h_tkIpwbsxY&list=PLK_hdtAJ4KqX0JOs_KMAmUNTNMRYhWEaC) – 一个使用 React 和 JavaScript 函数式编程构建“实用”Web 应用程序的系列.
* [Hey Underscore, You're Doing It Wrong!](https://www.youtube.com/watch?v=m3svKOdZijA) – Underscore.js 声称是一个函数式编程库，但它真的是这样吗？
* [Functional programming patterns for the non-mathematician](https://www.youtube.com/watch?v=AvgwKjTPMmM) – 了解仿函数、应用程序和单子的实际用例.
* [Pure JavaScript](https://vimeo.com/49384334) – Christian Johansen 将向您展示如何通过抛开循环并将函数作为主要抽象单元来显着提升您的游戏水平.
* [Functional programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) - Mattias Petter Johansson 的系列文章，来自 youtube 频道 FunFunFunction，专门介绍 JavaScript 函数式编程的普及.
* [Functional Programming in TypeScript](https://www.youtube.com/playlist?list=PLuPevXgCPUIMbCxBEnc1dNwboH6e2ImQo) - 在这个适合初学者的 YouTube 播放列表中探索使用 Typescript 的函数式编程并与 Sahand Javid 一起创建一个像 fp-ts 这样的库.
* [Anjana Vakil: Learning Functional Programming with JavaScript - JSUnconf 2016](https://www.youtube.com/watch?v=e-5obm1G_FY) - 简单易懂地介绍 javascript 中的函数式编程.
* [Functional Programming Basics In ES6](https://www.youtube.com/watch?v=FYXpOjwYzcs) - 完整介绍了 JavaScript 中的函数式编程，使 ES6 变得容易.
* [JavaScript Programmers Should Learn Algebraic Data Types -- May 2018 -- UtahJS Lehi](https://www.youtube.com/watch?v=B0VoyujJWIE) - Seth House 解释了 ADT（代数数据类型）如何对 JavaScript 开发人员有用.

### Examples and Exercises

* [FPJS-Class](https://github.com/loop-recur/FPJS-Class) – 通过 JavaScript 学习的函数式编程.
* [functional-javascript-workshop](https://github.com/timoxley/functional-javascript-workshop) – 本次研讨会的目标是创建可以使用简洁、普通、惯用的 JavaScript 解决的现实问题，以教授 JavaScript 的基本函数式编程功能.
* [functional-frontend-architecture](https://github.com/paldepind/functional-frontend-architecture)  – 一个功能性的前端框架. 基于 Ramda + union-type-js + Flyd + Snabbdom
* [cube-composer](https://github.com/sharkdp/cube-composer) – 一款受函数式编程启发的益智游戏.
* [FP Youtube Search](https://github.com/jaysoo/example-fp-youtube-search) – 具有 ReactJS、Redux 和 FP 概念的 YouTube 搜索应用程序
* [Hardcore Functional Programming in JavaScript](https://frontendmasters.com/courses/functional-javascript/)  – 学习应用计算机科学研究前沿的技术来解决 Javascript 中的实际问题. 探索函数式编程，并观看它逐步演示如何使用 Monad、Functors、Monoid 和 Applicatives 等抽象接口构建示例 Web 应用程序.  （_商业的_）
* [Escape from Callback Mountain](https://github.com/justsml/escape-from-callback-mountain)  - 基于 Promise 的函数式 JavaScript 的设计和重构技巧. 主要好处包括更好的可读性、可测试性和可重用性. 麻省理工学院.
* [Functional Programming for Beginners](http://paqmind.com/courses/fp-beginner/) – 数十个带有解决方案和解释的练习.
* [Learn Rx](http://reactivex.io/learnrx/) – 一系列交互式练习，介绍函数式（反应式）编程的五个基本要素：`map`、`filter`、`concatAll`、`reduce` 和 `zip` 函数.
* [Holdem Evaluator](https://github.com/laberin/holdem-eval) - 另一个具有 Ramda 功能风格的 Holdem Evaluator

## Community

### Related Lists

* [Awesome FRP JS](https://github.com/stoeffel/awesome-frp-js) – 精选的 JavaScript 中很棒的（函数式）反应式编程内容列表.
* [lucasviola/Awesome Functional Programming](https://github.com/lucasviola/awesome-functional-programming) – 关于函数式编程理论和学习材料的精彩资源.
* [xgrommx/Awesome Functional Programming](https://github.com/xgrommx/awesome-functional-programming) – 大量关于函数式编程的文章，以及大量用于多种编程语言的函数式库列表.
* [Functional Programming Resources In JavaScript](https://github.com/busypeoples/functional-programming-javascript)
* [tk-learning-center/Functional Programming Learning Path](https://github.com/tk-learning-center/functional-programming-learning-path) - 函数式编程的学习路径

### Talk

* [Functional Programming Slack channel](https://fpslack.com/) – 社区有一个友好的 JavaScript 频道以及许多其他关于一般函数式编程的频道.


## Contribution

 :star: 欢迎提出建议和 PR！  ：星星：

请阅读 [contribution guidelines](https://github.com/stoeffel/awesome-fp-js/blob/master/./contributing.md) 开始.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Christoph Hermann](http://stoeffel.github.io/) 已放弃该作品的所有版权和相关或邻接权.
