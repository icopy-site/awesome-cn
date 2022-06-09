<div class="github-widget" data-repo="stoeffel/awesome-fp-js"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome FP JS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

这是一个很棒的精选列表 [functional programming](https://en.wikipedia.org/wiki/Functional_programming)  JavaScript 的代码和学习资源. 作为一种多范式编程语言，JavaScript 可以以多种风格编写. 通过这些资源，我们希望帮助您更好地利用 JavaScript 对以_功能_方式编写程序的支持.

函数式编程是一种 [style of programming](https://wiki.haskell.org/Functional_programming) 它将计算建模为表达式的评估. 将此与命令式编程进行对比，其中程序由执行时更改全局状态的语句组成. 函数式编程通常会避免使用可变状态，而是倾向于使用 _side-effect free_ 函数和 _immutable_ 数据. 这鼓励编写易于推理的可组合和声明性程序.



##### Tags
这些可以附加到条目中. 每个都应以“+”或“-”开头，以指示标签含义的存在或不存在.  “-”标签只有在它们可能帮助某人过滤库以满足他们的需要时才应该包含. 例如，“-TS”标签可能对 Typescript 用户筛选类型有用，但“-CT”标签不太可能对任何人有帮助.

 * __CT__. 范畴论. 这个库似乎受到了 Haskell、Scala 或其他以范畴论为基础的函数式语言库的启发.
 * __TS__. 打字稿. 这个库有打字稿类型.

## Libraries

* [Ramda](https://github.com/ramda/ramda)  – 一个实用的 JavaScript 函数库，专为函数式编程风格而设计. 一种可以轻松创建功能管道并且永远不会改变用户数据的样式.  +TS.
* [Ramda Adjunct](https://github.com/char0n/ramda-adjunct) 是 Ramda 的社区维护扩展.
* [Ramda-extension](https://github.com/tommmyy/ramda-extension) 是一组仅由 Ramda 函数组成的实用无点函数.
* [Rambda](https://github.com/selfrefactor/rambda) - 一个更快的 Ramda 替代方案，小于 10kB.
* [Rambdax](https://github.com/selfrefactor/rambdax) - 兰布达的扩展版
* [Folktale](http://folktale.origamitower.com/)  – 用于 JavaScript 函数式编程的标准库. 预计 2020 年中期支持打字稿.  -TS.
* [lodash/fp](https://github.com/lodash/lodash/wiki/FP-Guide) – 一个实例 [Lodash](https://github.com/lodash/lodash) 其方法被包装以产生不可变的、自动柯里化的、迭代优先的、数据最后的方法.  +TS.
* [functional.js](https://github.com/functionaljs/functional-js) – 一个轻量级的函数式 JavaScript 库，有助于进行柯里化和无点/默认编程.
* [101](https://github.com/tjmehta/101)  - 一个现代和模块化的 JavaScript 实用程序库，可与 vanilla JavaScript 方法很好地配合使用.  -TS
* [fnuc](https://github.com/algesten/fnuc) – CoffeeScript（和 JavaScript）的函数库，用于促进函数组合和高阶函数.
* [barely-functional](https://github.com/cullophid/barely-functional)  – 一个使用原生 ES5/6 操作的小型 (2.7kb) 函数式编程库.  -TS.
* [bluebird-promisell](https://github.com/zhangchiqing/bluebird-promisell) - Promise 的实用函数式编程库.
* [prelude.ls](http://gkz.github.io/prelude-ls/)  – 基于 Haskell 的 Prelude 模块的面向功能的实用程序库.  -TS.
* [preludejs](https://github.com/alanrsoares/prelude-js)  - JavaScript 的核心函数式编程.  -TS.
* [1-liners](https://github.com/1-liners/1-liners)  – 再简单不过的功能性工具. 一条简单实用的实用腰带，以爱心和关注手工制作.  -TS.
* [fn-curry](https://github.com/thunklife/fn-curry) – 一个简单的函数来柯里化一个函数.
* [curry](https://github.com/thisables/curry) – 使用函数绑定语法对函数进行咖喱.
* [compose-function](https://github.com/stoeffel/compose-function) – 从较小的函数中组合一个新函数.
* [functionize](https://github.com/paldepind/functionize) – 一组有助于使非功能性库发挥作用的功能.
* [lambdajs](https://github.com/loop-recur/lambdajs) – 完整的 ECMAScript API 以功能方式完成.
* [fp-dom](https://github.com/fp-dom/) – 使 DOM 功能化.
* [react-on-lambda](https://github.com/sultan99/react-on-lambda) - 用函数（currying、composition 等）替换 React 中的 JSX. 
* [trifl](https://github.com/algesten/trifl) – 具有单向数据流和虚拟 dom 的功能性用户界面库.
* [funcy](https://github.com/bramstein/funcy)  – 在 JavaScript 中添加功能模式匹配的实验.  _实验性_ :triangular_flag_on_post:
* [date-fp](https://github.com/cullophid/date-fp)  – 用于处理 JavaScript 日期的功能实用程序库.  date-fp 中的所有函数都是纯的、自动柯里化的，并且不会改变它们应用到的日期对象.
* [js-joda](https://github.com/js-joda/js-joda) – 一个不可变的日期和时间库，提供基于 ISO8601 日历的简单、域驱动和干净的 API.
* [\_part\_](https://github.com/AutoSponge/_part_) – 一个微型库，通过将本机方法作为部分应用函数提供来鼓励函数式编程.
* [claire](https://github.com/robotlolita/claire) – 一个基于属性的测试库，用于明确指定代码不变量和行为.
* [FPO.js](https://github.com/getify/fpo)  – Kyle Simpson（又名 getify）的 JavaScript FP 库. 支持命名参数样式方法.
* [Javascript Parser Combinator](https://github.com/d-plaindoux/parsec) – 受 Haskell 的 Parsec 启发的 Javascript 解析器组合器实现
* [fun-task](https://github.com/rpominov/fun-task)  – 用于管理 JS 中的异步代码的抽象.  Tasks 类似于 Promises，关键区别在于 Tasks 可以表示计算，而 Promises 只能表示计算的结果. 附带流类型定义.
* [most](https://github.com/cujojs/most) – 超高性能的反应式编程，可帮助您在值和事件流上组合异步操作，而不会出现副作用和可变共享状态的许多危害.
* [zen-signals](https://github.com/joaomilho/zen-signals) – ☯ 最简单的信号库
* [funfix](https://github.com/funfix/funfix)  – Funfix 是一个类型类和数据类型库，用于 JavaScript、TypeScript 和 Flow 中的函数式编程.  +CT，+TS.
* [pico-lambda](https://github.com/trainyard/pico-lambda)  - 数组，字符串和事物的功能方式. 基于本机方法的 640b 函数库.  -TS.
* [pareto-js](https://github.com/concretesolutions/pareto.js/) - 适用于 JavaScript -TS 的极小、直观且快速的功能实用程序库.
* [fpEs](https://github.com/TeaEntityLab/fpEs/)  - 一个小型库提供基本 FP &amp; 模式匹配/sumtype &amp; MonadIO/Rx &amp; Optional for Javascript 的简单用法.  -TS.
* [Creed](http://blog.briancavalier.com/creed/)  – 具有高级功能的复杂且具有功能性的异步：协程、承诺、ES2015 迭代、幻想世界.  -TS.
* [TGrid](https://github.com/samchon/tgrid) - 网格计算框架、网络和线程扩展 [TSTL](https://github.com/samchon/tstl) ，支持RFC（远程函数调用）.  +TS.
* [Ferrum](https://github.com/adobe/ferrum)  – 支持作为可迭代对象、惰性评估和`pipe()`的对象的迭代器库； 在 JS 中实现 Traits（来自 Rust）/Type Classes（来自 Haskell）.  -TS.
* [fp-ts](https://gcanti.github.io/fp-ts/)  - TypeScript 中的类型化函数式编程.  +CT，+TS.
* [iter-tools](https://github.com/iter-tools/iter-tools)  - 用于处理同步和异步迭代的丰富工具集.  +TS.
* [remeda](https://remedajs.com/) 一个函数库，大致是 Ramda 的子集，但用 Typescript 编写，因此对类型更友好.  +TS.
* [futil-js](https://github.com/smartprocure/futil-js) - 一组功能实用程序，可以想象成为像 lodash/fp 这样的库的一部分，但由于某种原因或其他原因不是.
* [rubico](https://github.com/a-synchronous/rubico) - [a]同步功能语法
* [rocket-pipes](https://github.com/darky/rocket-pipes)  - 强大的管道，链接 Promise 和 ADT，例如来自流行的 FP 库的 Maybe 或 Either.  +TS
* [omg-curry](https://github.com/Debdut/omg-curry) - 综合 Curry 库，包含 Operator Curry、Curry from functions、Decurry 和 Infinite Curries.
* [lfi](https://github.com/TomerAberbach/lfi) - 一个支持同步、异步和并发迭代的惰性函数迭代库.
* [ts-multimethod](https://github.com/darky/ts-multimethod)  - 受 Clojure 多方法启发的 TypeScript 多方法.  +TS
* [ts-fp-di](https://github.com/darky/ts-fp-di)  - 基于 Node.js AsyncLocalStorage 的微型 TypeScript 函数依赖注入.  +TS
* [effect-ts](https://github.com/Effect-TS/core)  - 一个成熟的打字稿功能效果系统，具有丰富的标准库.  +TS
* [qio](https://github.com/tusharmath/qio)  – 一种类型安全、功能性、高性能、合法、可组合的数据结构，可解决节点和浏览器中效果完整代码的实际问题.  +TS
* [Ditox.js](https://github.com/mnasyrov/ditox)  - 用于构建模块化应用程序的强大依赖注入容器.  +TS
* [RxEffects](https://github.com/mnasyrov/rx-effects)  - 使用 RxJS 进行反应式状态和效果管理.  +TS
* [fxts](https://github.com/marpple/FxTS)  - 延迟评估和并发.  +TS
* [ts-belt](https://mobily.github.io/ts-belt/)  - TypeScript 中用于 FP 的快速、现代且实用的实用程序库.  （使用数据优先的方法，如 remeda，但 [faster](https://mobily.github.io/ts-belt/benchmarks/v3.7.0/macbook-air-2020) 比 remeda、ramda、rambda 和 lodash / fp.)
* [fp-multik](https://github.com/lulldev/fp-multik) - JS/TS 轻量级值-多方法实用程序
* [true-myth](https://github.com/true-myth/true-myth) TypeScript 中用于安全、惯用的 null 和错误处理的库，具有“Maybe”和“Result”类型，支持函数式风格和更传统的方法调用风格

### Data Structures

通过为任务使用正确的数据结构来编写高性能的功能代码.

* [Icepick](https://github.com/aearly/icepick) 将冻结的 JavaScript 对象视为持久不可变集合的实用程序
* [Immutable.js](https://github.com/facebook/immutable-js) – 不可变的持久数据集合.
* [Immer](https://github.com/mweststrate/immer)  – Immer 是一个基于写时复制机制的不可变状态的微型包.  +TS.
* [Mori](https://github.com/swannodette/mori) – ClojureScript 的持久数据结构和支持 API 来自普通 JavaScript 的舒适.
* [Baobab](https://github.com/Yomguithereal/baobab) – 带有游标的持久和可选的不可变数据树.
* [immutable-sequence.js](https://github.com/qiao/immutable-sequence.js) – JavaScript 中不可变序列的高性能实现，基于 [Finger Trees](https://github.com/qiao/fingertree.js).
* [Timm](http://guigrpa.github.io/timm/) – 具有快速读取和可接受写入的不变性助手.
* [Lazy.js](https://github.com/dtao/lazy.js) - 一个实用程序库，在引擎盖下有一个惰性引擎，力求在尽可能灵活的同时做尽可能少的工作.
* [DerivableJS](https://github.com/ds300/derivablejs) – Functional Reactive State for JavaScript and TypeScript. DerivableJS enables you to make elegant declarative statements about how your bits of state are related. +TS.
* [imlazy](https://github.com/benji6/imlazy) - 使用 ES2015 迭代协议创建和操作惰性迭代的库.
* [collectable](https://github.com/frptools/collectable) – Super high-performance immutable data structures for modern JavaScript and TypeScript applications. +TS.
* [List](https://github.com/funkia/list) - 一个非常快速的不可变列表，具有全面的功能 API.
* [prelude.ts](https://github.com/emmanueltouzery/prelude.ts)  - 不可变的持久性集合、功能构造（如 Option 和 Either）以及组合器. 在 Typescript 中实现，但也支持 javascript.  +CT，+TS.
* [TSTL](https://github.com/samchon/tstl)  - C++ STL（标准模板库）在 TypeScript 中实现. 提供了遵循函数式编程规则的 STL 容器、迭代器、算法和仿函数.  +TS.

### Algebraic Data Types

使用数学定律，而不是总是重新发明你自己的东西. 代数！

* [Fantasy Land](https://github.com/fantasyland/fantasy-land) – 不是图书馆，而是图书馆遵循的 Monad 法则规范.
* [Static Land](https://github.com/rpominov/static-land) – 规范类似于 Fantasy Land，但基于静态方法而不是实例方法.
* [immutable-ext](https://github.com/DrBoolean/immutable-ext) - FantasyLand 扩展 [Immutable.js](https://github.com/facebook/immutable-js).
* [daggy](https://github.com/puffnfresh/daggy) - 用于创建标记构造函数的库.
* [Sanctuary](https://github.com/plaid/sanctuary)  – Sanctuary 可以编写没有空检查的安全代码.  +CT，+TS.
* [monet.js](http://cwmyers.github.io/monet.js/)  – 通过提供一组丰富的 Monad 和其他有用的函数来帮助函数式编程的库.  +CT，+TS.
* [union-type](https://github.com/paldepind/union-type) – 一个用于定义和使用联合类型的小型 JavaScript 库.
* [freeky](https://github.com/DrBoolean/freeky) – 免费单子的集合.
* [Fluture](https://github.com/Avaq/Fluture) – 包含控制实用程序、高性能和大量错误消息的 Future 库.
* [fantasy-combinators](https://github.com/fantasyland/fantasy-combinators) – 通用组合子.
* [fantasy-birds](https://github.com/fantasyland/fantasy-birds)  – Haskell 包 Data.Aviary.Birds 的端口. 一切满足您的组合需求.
* [crocks](https://github.com/evilsoft/crocks)  – 流行的代数数据类型的集合，其主要目标是管理和提供不仅在每种类型之间的通用接口，而且还提供开始运行所需的所有辅助函数.  -TS.
* [kudo-js](https://github.com/blitzritz/kudojs) - 一个带有一组代数数据类型和辅助函数的小型实用程序库，可帮助您在 Javascript 中以函数式编程风格编写代码
* [purify](https://github.com/gigobyte/purify)  - 专注于 ADT 的 TypeScript 函数式编程库.  +CT，+TS.
* [MojiScript](https://github.com/joelnet/MojiScript)- 一种异步优先、固执己见的函数式语言，旨在与 JavaScript 引擎 100% 兼容
* [Pratica](https://github.com/rametta/pratica)  - 小型、简单、易用的 FP 数据类型，适用于需要快速交付可靠代码的务实且高效的开发人员.  +CT，+TS.
* [Tifi](https://github.com/mobily/tifi)  - Tifi 是 TypeScript 中用于函数式编程的库. 它解决了 `undefined` 和 `null` 都存在的问题.  Tifi 受到选项数据类型的 OCaml/Reason 实用程序的启发.  +CT，+TS.

### Lenses

* [lenses](https://github.com/DrBoolean/lenses) – 可组合 [kmett](https://github.com/ekmett/lens) 风格的镜头.
* [optics](https://github.com/flunc/optics) – Profunctor 光学（透镜、棱镜、iso）.
* [ramda-lens](https://github.com/ramda/ramda-lens) – :ram: :mag_right：基于 Ramda 构建的镜头库.
* [fantasy-lenses](https://github.com/fantasyland/fantasy-lenses)  – 可组合的、不可变的 getter 和 setter.  （Profunctor 镜头 WIP）
* [nanoscope](https://github.com/5outh/nanoscope) – 带点支撑的镜头.
* [partial.lenses](https://github.com/calmm-js/partial.lenses) – Partial lens 是一个全面的、高性能的 JavaScript 光学库.
* [shades](https://github.com/jamesmcnamara/shades) – 一个受 lodash 启发的类似镜头的 Javascript 库.

## Functional Languages that Compile to JavaScript

* [ClojureScript](https://github.com/clojure/clojurescript) – 编译 [Clojure](http://clojure.org/)，具有不可变持久数据结构的托管 Lisp 到 JavaScript.
* [Elm](http://elm-lang.org/)  – 一种类型安全的函数式编程语言，用于以声明方式创建基于 Web 浏览器的图形用户界面. 在 Haskell 中实现.
* [Fable](http://fable.io/) - 编译 [F#](http://fsharp.org) 可读的 JavaScript.
* [PureScript](http://www.purescript.org/) – 一种小型强类型编程语言，可编译为 JavaScript.
* [Idris](http://www.idris-lang.org/) – 具有依赖类型的通用纯函数式编程语言.
* [GHCJS](https://github.com/ghcjs/ghcjs) – [Haskell](https://www.haskell.org/) 到基于 GHC 的 JavaScript 编译器.
* [ElixirScript](https://github.com/bryanjos/elixirscript) – 编译一个子集 [Elixir](http://elixir-lang.org/)，一种用于构建可扩展和可维护应用程序的动态函数式语言，适用于 JavaScript.
* [Js\_of\_ocaml](http://ocsigen.org/js_of_ocaml/) – 编译 [OCaml](http://ocaml.org/) 字节码到 JavaScript，使得在浏览器中运行 OCaml 程序成为可能.
* [Reason](https://reasonml.github.io) – Reason 是 OCaml 的新接口，OCaml 是 ML 语言的一种高度表达方言，具有类型推断和静态类型检查.
* [ReScript](https://rescript-lang.org/) –（以前称为 [Bucklescript](https://rescript-lang.org/bucklescript-rebranding)) ReScript 是一种类型安全的语言，可以编译成最高质量的干净、可读和高性能的 JavaScript 代码.
* [Scala.js](http://www.scala-js.org/) – 编译 [Scala](http://www.scala-lang.org/) 到 JavaScript.
* [LiveScript](http://gkz.github.io/LiveScript/) – LiveScript 具有与 JavaScript 的直接映射，允许您编写没有重复样板的富有表现力的代码.
* [Quack](https://github.com/quack/quack) - 一种多范式编程语言，具有针对 PHP 和 JS 的渐进式和鸭式类型.
* [ion](https://github.com/ion-lang/ion) - 没有 BS JS
* [RamdaScript](https://github.com/yosbelms/ramdascript) - 在 RamdaJS 之上编译成自以为是的 JavaScript 的 Lisp
* [RacketScript](https://github.com/vishesh/racketscript) – RacketScript 旨在利用 JavaScript 和 Racket 的生态系统，并使它们之间的互操作性清晰流畅.
* [Koka](https://www.microsoft.com/en-us/research/project/koka/) – Koka 是一种面向函数的编程语言，它使用熟悉的类似 JavaScript 的语法将纯值与副作用计算分开.
* [TypeScript](https://www.typescriptlang.org/) - TypeScript 是 JavaScript 的类型化超集，可编译为纯 JavaScript.
* [Gleam](https://gleam.run) - Gleam 是一种类型化的函数式语言，可编译为 Erlang 和 JavaScript.

## Programming Tools

* [eslint-plugin-fp](https://github.com/jfmengels/eslint-plugin-fp) - 函数式编程的 ESLint 规则
* [4.5](https://github.com/TylorS/4.5)  – 一个功能性断言库. 如果你更喜欢 JavaScript 中的函数式 API 和实践，这个库旨在通过惰性和单子的面向函数的断言来解决这个问题.
* [hm-def](https://github.com/xodio/hm-def) – 使用 Hindley Milner 签名的 JS 运行时类型检查.
* [ftor](https://github.com/kongware/ftor) - 一个可插入的运行时类型检查器和功能调试工具，通过 Scott Encoding 支持参数和行多态性、隐式 rank-2 类型和代数数据类型.

## Resources

### Books

* [Professor Frisby’s Mostly Adequate Guide to Functional Programming](https://github.com/MostlyAdequate/mostly-adequate-guide)  – 这是一本使用世界上最流行的函数式编程语言 JavaScript 来介绍函数式范式的书. 这是一个实用的介绍，通过真实世界的例子建立直觉. 强力推荐. 经过 [Brian Lonsdorf](https://twitter.com/drboolean) (2016)
* [Functional-Light JavaScript](https://github.com/getify/functional-light-js)  – 本书探讨了可应用于 JavaScript 的函数式编程 (FP) 的核心原则. 但这本书的不同之处在于，它在处理这些原则时没有使用所有繁重的术语.
* [JavaScript Allongé](https://leanpub.com/javascriptallongesix) ，“六”版. 从尽可能少的功能开始——但也不能少！  - 并建立强大的组合器和装饰器. 一本基础书. 经过 [Reginald  Braithwaite](https://github.com/raganwald) (2016)
* [Functional Programming in JavaScript](https://www.manning.com/books/functional-programming-in-javascript) 教授 JavaScript 开发人员功能性技术，这些技术将提高可扩展性、模块化、可重用性、可测试性和性能. 通过具体的例子和无术语的解释，本书教你如何将函数式编程应用到现实生活中的开发任务中. 路易斯·阿滕西奥 (2016)
* [Eloquent JavaScript](http://eloquentjavascript.net/) . 使用 JavaScript 进行编程的现代介绍. 玛丽恩·哈弗贝克 (Marijn Haverbeke) (2014)
* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) 教授如何使用 JavaScript 的函数式编程支持创建美观、安全、易于理解和测试的代码. 经过 [Michael Fogus](https://github.com/fogus) (2013)
* [Grokking Simplicity](https://www.manning.com/books/grokking-simplicity) 从第一原理讲授函数式编程. 它对所有代码示例使用 JavaScript，并使用真实场景. 经过 [Eric Normand](https://github.com/ericnormand) (2019)
* [scriptum](https://github.com/kongware/scriptum/blob/master/README.md) - 一个简洁的函数式编程库和基于它的在线课程

### Articles

* [FP Concepts in JavaScript](https://medium.com/@collardeau/intro-to-functional-programming-concepts-in-javascript-b0650773139c)  – 介绍 JavaScript 中的函数式编程概念. 使用 Ramda 库通过最简单的示例教授组合、无点样式和函子的概念.
* [Functional programming with JavaScript](http://stephen-young.me.uk/2013/01/20/functional-programming-with-javascript.html) – JavaScript 函数式编程的另一个介绍，重点关注三个关键主题：计算作为函数的应用、无状态、避免副作用.
* [A gentle introduction to functional JavaScript](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro/) – A four-part series introduction functional programming in JavaScript that gets you up to speed what all the hype about functional programming is all about.
* [Functors from first principle - explained with JS](https://dev.to/snird/functors-from-first-principle-37lh) - 使用 JavaScript 解释函子概念.
* [Why Curry Helps](https://hughfdjackson.com/javascript/why-curry-helps/) – 关于如何使用柯里化编写可重用和声明性代码的简短概述.
* [Favoring Curry](http://fr.umio.us/favoring-curry/) - 使用 Ramda 进行柯里化的实际应用.
* [Functional Mumbo Jumbo – ADTs](http://blog.jenkster.com/2016/06/functional-mumbo-jumbo-adts.html) – 适合初学者的代数数据类型介绍.
* [JavaScript and Type Thinking](https://medium.com/@yelouafi/javascript-and-type-thinking-735edddc388d)  – 学习用 _type thinking_ 推理你的 JavaScript 代码. 代数数据类型被引入作为推理程序实体的概念基础.
* [Lazy, composable, and modular JavaScript](https://codewords.recurse.com/issues/four/lazy-composable-and-modular-javascript) – 使用 ES6 的四个新特性——可迭代、生成器、胖箭头和 for-of——结合高阶函数、函数组合和惰性求值，编写更简洁、更模块化的 JavaScript.
* [Why Ramda](http://fr.umio.us/why-ramda/)  – 对于那些不习惯函数式编程的人来说，Ramda 似乎毫无用处. 但是，它确实提供了一种不同的编码风格，这种风格在纯函数式编程语言中被认为是理所当然的：Ramda 使您可以通过函数式组合轻松构建复杂的逻辑.
* [Monads in JavaScript](https://curiosity-driven.org/monads-in-javascript) – 介绍 JavaScript 中的 Monad 设计模式.
* [A Monad in Practicality: First-Class Failures](http://robotlolita.me/2013/12/08/a-monad-in-practicality-first-class-failures.html) – 浏览 JavaScript 中特定 monadic 结构的一些实际用例：使用 `Maybe` monad 处理简单的失败案例，并使用 `Either` monad 或 `Validation` applicative functor 为更复杂的场景建模.
* [Functional programming](https://glebbahmutov.com/blog/tags/functional/) – Gleb Bahmutov 撰写的许多关于 JavaScript 函数式编程各个方面的文章.
* [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon) – 用 Ja​​vaScript 解释的函数式编程世界的行话.
* [Data Structures in JavaScript](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/) – 一系列博客文章，重新实现 JavaScript 中的各种数据结构，以更好地了解它们的优点和缺点.
* [So You Want to be a Functional Programmer](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536) - 易于理解，并附有一些示例，介绍了 Javascript 和 Elm 中的函数式编程.
* [Functional Programming for JavaScript People](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504) - Chet Corcos 对函数式编程模式的完整介绍，其中包含大量 javascript 示例.
* [Introduction to Immutable.js and Functional Programming Concepts](https://auth0.com/blog/intro-to-immutable-js/) - 在 Facebook 流行的 JavaScript 库概览中了解函数式数据结构及其用途：Immutable.js.
* [Master the JavaScript Interview: What is Functional Programming?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0) - @ericelliott 对功能原理和词汇的简单介绍.
* [Composing Software](https://medium.com/javascript-scene/the-rise-and-fall-and-rise-of-functional-programming-composable-software-c2d91b424c8c) - @ericelliott 撰写的一系列关于从头开始学习 JavaScript ES6+ 中的函数式编程和组合软件技术的文章.
* [Anonymous Recursion in JavaScript](https://dev.to/simov/anonymous-recursion-in-javascript) - 关于在 JavaScript 中实现匿名递归的简短易懂的文章.
* [Functional Composition in Javascript](https://joecortopassi.com/articles/functional-composition-in-javascript/) - 逐步解释如何在 javascript 中编写函数.
* [Functional Programming Principles in Javascript](https://medium.freecodecamp.org/functional-programming-principles-in-javascript-1b8fc6c3563f) - 学习函数式编程概念的实用代码示例，如纯函数、不变性、一等实体和高阶函数
* [Basic Monads in Javascript](https://dev.to/rametta/basic-monads-in-javascript-3el3) - 介绍 2 个简单的 Javascript 单子，Maybe &amp; Either.
* [F# for JavaScript Devs](https://dev.to/rametta/f-for-js-devs-2b88) - Showcasing the similarities between F# and JavaScript
* [A practical guide to writing more functional Javascript](https://medium.com/@nadeesha/a-practical-guide-to-writing-more-functional-javascript-db49409f71) - 将命令式 JavaScript 转换为更具声明性的函数式 JavaScript 的分步指南.
* [You don't (may not) need loops ➿](https://github.com/you-dont-need/You-Dont-Need-Loops) - 循环是初级程序员最先学习的结构之一，但它们可能会在软件开发过程中造成许多潜在问题，并且在许多情况下可以避免.

### Videos

* [Classroom Coding with Prof. Frisby](https://www.youtube.com/watch?v=h_tkIpwbsxY&list=PLK_hdtAJ4KqX0JOs_KMAmUNTNMRYhWEaC) – 使用 React 和 JavaScript 函数式编程构建“实用”Web 应用程序的系列.
* [Hey Underscore, You're Doing It Wrong!](https://www.youtube.com/watch?v=m3svKOdZijA) – Underscore.js 声称是一个函数式编程库，但这是真的吗？
* [Functional programming patterns for the non-mathematician](https://www.youtube.com/watch?v=AvgwKjTPMmM) – 了解函子、应用程序和单子的实际用例.
* [Pure JavaScript](https://vimeo.com/49384334) – Christian Johansen 将向您展示如何通过将循环抛在脑后并将函数作为抽象的主要单元来显着提升您的游戏.
* [Functional programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) - 来自 YouTube 频道 FunFunFunction 的 Mattias Petter Johansson 的系列文章，专门介绍 JavaScript 中函数式编程的普及.
* [Anjana Vakil: Learning Functional Programming with JavaScript - JSUnconf 2016](https://www.youtube.com/watch?v=e-5obm1G_FY) - 简单易懂地介绍 javascript 中的函数式编程.
* [Functional Programming Basics In ES6](https://www.youtube.com/watch?v=FYXpOjwYzcs) - 完整的 javascript 函数式编程介绍使 ES6 变得简单.
* [JavaScript Programmers Should Learn Algebraic Data Types -- May 2018 -- UtahJS Lehi](https://www.youtube.com/watch?v=B0VoyujJWIE) - Seth House 解释了 ADT（代数数据类型）如何对 JavaScript 开发人员有用.

### Examples and Exercises

* [FPJS-Class](https://github.com/loop-recur/FPJS-Class) – 通过 JavaScript 学习的函数式编程.
* [functional-javascript-workshop](https://github.com/timoxley/functional-javascript-workshop) – 本次研讨会的目标是创建可以使用简洁、普通、惯用的 JavaScript 解决的现实问题，以教授 JavaScript 的基本函数式编程特性.
* [functional-frontend-architecture](https://github.com/paldepind/functional-frontend-architecture)  – 一个功能性的前端框架. 基于 Ramda + union-type-js + Flyd + Snabbdom
* [cube-composer](https://github.com/sharkdp/cube-composer) - 受函数式编程启发的益智游戏.
* [FP Youtube Search](https://github.com/jaysoo/example-fp-youtube-search) – 带有 ReactJS、Redux 和 FP 概念的 YouTube 搜索应用
* [Hardcore Functional Programming in JavaScript](https://frontendmasters.com/courses/functional-javascript/)  – 学习应用计算机科学研究前沿的技术来解决 Javascript 中的实际问题. 探索函数式编程，并逐步演示如何使用 Monads、Functors、Monoids 和 Applicatives 等抽象接口构建示例 Web 应用程序.  （_商业的_）
* [Escape from Callback Mountain](https://github.com/justsml/escape-from-callback-mountain)  - 基于 Promise 的函数式 JavaScript 的设计和重构技巧. 主要好处包括更好的可读性、可测试性和可重用性. 麻省理工学院.
* [Functional Programming for Beginners](http://paqmind.com/courses/fp-beginner/) - 数十个带有解决方案和解释的练习.
* [Learn Rx](http://reactivex.io/learnrx/) – 一系列互动练习，介绍函数式（反应式）编程的五个基本要素：`map`、`filter`、`concatAll`、`reduce` 和 `zip` 函数.
* [Holdem Evaluator](https://github.com/laberin/holdem-eval) - 另一个具有 Ramda 功能风格的 Holdem Evaluator

## Community

### Related Lists

* [Awesome FRP JS](https://github.com/stoeffel/awesome-frp-js) – JavaScript 中很棒的（函数式）响应式编程内容的精选列表.
* [lucasviola/Awesome Functional Programming](https://github.com/lucasviola/awesome-functional-programming) – 关于函数式编程理论和学习材料的精彩资源.
* [xgrommx/Awesome Functional Programming](https://github.com/xgrommx/awesome-functional-programming) - 大量关于函数式编程的文章，以及用于许多编程语言的大量函数库.
* [Functional Programming Resources In JavaScript](https://github.com/busypeoples/functional-programming-javascript)
* [tk-learning-center/Functional Programming Learning Path](https://github.com/tk-learning-center/functional-programming-learning-path) - 函数式编程的学习路径

### Talk

* [Functional Programming Slack channel](https://fpchat-invite.herokuapp.com/) – 社区拥有一个友好的 JavaScript 频道以及许多其他关于函数式编程的一般频道.


## Contribution

 :star: 欢迎提出建议和 PR！  ：星星：

请阅读 [contribution guidelines](https://github.com/stoeffel/awesome-fp-js/blob/master/./contributing.md) 开始.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Christoph Hermann](http://stoeffel.github.io/) 已放弃本作品的所有版权和相关或邻近权利.
