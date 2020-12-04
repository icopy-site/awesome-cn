<div class="github-widget" data-repo="stoeffel/awesome-fp-js"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome FP JS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

这是一个很棒的精选清单 [functional programming](https://en.wikipedia.org/wiki/Functional_programming)  JavaScript的代码和学习资源. 作为一种多范例编程语言，JavaScript可以用多种样式编写. 借助这些资源，我们希望帮助您更好地利用JavaScript对以_functional_方式编写程序的支持.

函数式编程是 [style of programming](https://wiki.haskell.org/Functional_programming) 该模型将计算建模为表达式的求值. 与命令式编程相反，命令式编程中的程序由在执行时更改全局状态的语句组成. 函数式编程通常避免使用可变状态，而倾向于_side-free free_函数和_immutable_ data. 这鼓励编写易于推理的可组合和声明式程序.



##### Tags
这些可以附加到条目中. 每个标签之前都应加一个“ +”或“-”，以指示标签含义的存在或不存在. 仅当“-”标签有可能帮助某人过滤其需求的库时，才应包括它们. 例如，`-TS`标签可能对Typescript用户筛选类型有用，但是`-CT`标签对任何人的帮助都不太可能.

 * __CT__. 范畴论. 该库似乎受Haskell，Scala或另一种基于类别理论的功能语言库的启发.
 * __TS__. 打字稿. 该库具有打字稿类型.

## Libraries

* [Ramda](https://github.com/ramda/ramda)  –一个实用的JavaScript函数库，专门针对函数式编程风格而设计. 一种易于创建功能管道且永不突变用户数据的样式.  + TS.
* [Ramda Adjunct](https://github.com/char0n/ramda-adjunct) 是Ramda的社区维护扩展.
* [Ramda-extension](https://github.com/tommmyy/ramda-extension) 是仅由Ramda函数组成的实用程序无点函数集.
* [Rambda](https://github.com/selfrefactor/rambda) -低于10kB的Ramda替代产品.
* [Rambdax](https://github.com/selfrefactor/rambdax) -Rambda的扩展版本
* [Folktale](http://folktale.origamitower.com/)  – JavaScript函数编程的标准库. 预计将于2020年中期提供打字稿支持.  -TS.
* [lodash/fp](https://github.com/lodash/lodash/wiki/FP-Guide) –的实例 [Lodash](https://github.com/lodash/lodash) 其方法可以包装成不变的，自动处理的，迭代优先，数据后处理的方法.  + TS.
* [functional.js](http://functionaljs.com) –轻量级的功能性JavaScript库，有助于进行currying和无点/默认编程.
* [101](https://github.com/tjmehta/101)  –一个现代的模块化JavaScript实用程序库，可以很好地与普通JavaScript方法配合使用.  -TS
* [fnuc](https://github.com/algesten/fnuc) – CoffeeScript（和JavaScript）的功能库，可促进功能组合和高阶功能.
* [barely-functional](https://github.com/cullophid/barely-functional)  –使用本地ES5 / 6操作的微型（2.7kb）功能编程库.  -TS.
* [bluebird-promisell](https://github.com/zhangchiqing/bluebird-promisell) -一个实用的函数式编程库，用于promise.
* [prelude.ls](http://gkz.github.io/prelude-ls/)  –某种程度上基于Haskell的Prelude模块的面向功能的实用程序库.  -TS.
* [preludejs](https://github.com/alanrsoares/prelude-js)  -适用于JavaScript的核心函数式编程.  -TS.
* [1-liners](https://github.com/1-liners/1-liners)  –功能工具再简单不过了. 一条简单而实用的实用皮带，充满爱与关怀.  -TS.
* [fn-curry](https://github.com/thunklife/fn-curry) –简化功能的简单功能.
* [curry](https://github.com/thisables/curry) –使用函数绑定语法来编写函数.
* [compose-function](https://github.com/stoeffel/compose-function) –从较小的功能组成新功能.
* [functionize](https://github.com/paldepind/functionize) –有助于使非功能库正常运行的功能集合.
* [lambdajs](https://github.com/loop-recur/lambdajs) –完整的ECMAScript API发挥了功能性的作用.
* [fp-dom](https://github.com/fp-dom/) –使DOM起作用.
* [react-on-lambda](https://github.com/sultan99/react-on-lambda) -将React中的JSX替换为函数（currying，composition等）. 
* [trifl](https://github.com/algesten/trifl) –具有单向数据流和虚拟dom的功能用户界面库.
* [funcy](https://github.com/bramstein/funcy)  –将功能模式匹配添加到JavaScript的实验.  _experimental_：triangular_flag_on_post：
* [date-fp](https://github.com/cullophid/date-fp)  –一个用于处理JavaScript日期的实用工具库.  date-fp中的所有函数都是纯函数，它们是自动运行的，并且不会改变它们所应用的日期对象.
* [js-joda](https://github.com/js-joda/js-joda) –一个不变的日期和时间库，它基于ISO8601日历提供了一个简单的，由域驱动且干净的API.
* [\_part\_](https://github.com/AutoSponge/_part_) –一个微型库，通过将本机方法用作部分应用的函数来鼓励函数编程.
* [claire](https://github.com/robotlolita/claire) –基于属性的测试库，用于明确指定代码不变性和行为.
* [FPO.js](https://github.com/getify/fpo)  – Kyle Simpson的JavaScript FP库（又名getify）. 支持命名参数样式方法.
* [Javascript Parser Combinator](https://github.com/d-plaindoux/parsec) –受Haskell的Parsec启发的Javascript解析器组合器实现
* [fun-task](https://github.com/rpominov/fun-task)  –用于管理JS中的异步代码的抽象. 任务与承诺类似，主要区别在于任务可以代表计算，而承诺只能代表计算结果. 附带流类型定义.
* [most](https://github.com/cujojs/most) –超高性能反应式编程，可帮助您在值和事件流上编写异步操作，而无副作用和可变共享状态的许多危害.
* [zen-signals](https://github.com/joaomilho/zen-signals) – possible最简单的信号库
* [funfix](https://github.com/funfix/funfix)  – Funfix是JavaScript，TypeScript和Flow中用于函数式编程的类型类和数据类型的库.  + CT，+ TS.
* [pico-lambda](https://github.com/trainyard/pico-lambda)  -数组，字符串和事物的功能方式. 基于本地方法的640b功能库.  -TS.
* [pareto-js](https://github.com/concretesolutions/pareto.js/) -一个非常小的，直观且快速的JavaScript -TS功能实用程序库.
* [fpEs](https://github.com/TeaEntityLab/fpEs/)  -一个小的库提供了基本FP和模式匹配/求和和MonadIO / Rx以及Java可选的简单用法.  -TS.
* [Creed](http://blog.briancavalier.com/creed/)  –具有先进功能的复杂且功能意识强的异步程序：协程，promise，ES2015可迭代对象，幻想世界.  -TS.
* [TGrid](https://github.com/samchon/tgrid) -网格计算框架，网络和线程扩展 [TSTL](https://github.com/samchon/tstl) ，支持RFC（远程功能调用）.  + TS.
* [Ferrum](https://github.com/adobe/ferrum)  –迭代器库，支持对象作为可迭代对象，惰性评估和`pipe（）`； 在JS中实现特性（来自Rust）/类型类（来自Haskell）.  -TS.
* [fp-ts](https://gcanti.github.io/fp-ts/)  -TypeScript中的类型化函数式编程.  + CT，+ TS.
* [iter-tools](https://github.com/iter-tools/iter-tools)  -丰富的工具集，可用于同步和异步迭代.  + TS.
* [remeda](https://remedajs.com/) 一个函数库大致取代了Ramda，但使用Typescript编写，因此更加易于使用.  + TS.
* [futil-js](https://github.com/smartprocure/futil-js) -可以想象是像lodash / fp这样的库的一部分的功能实用程序的集合，但是由于某些原因或其他原因而没有.
* [rubico](https://github.com/a-synchronous/rubico) -[a]同步功能语法
* [rocket-pipes](https://github.com/darky/rocket-pipes)  -强大的管道，可以像流行的FP库中的Maybe或Either一样链接Promise和ADT.  + TS
* [omg-curry](https://github.com/Debdut/omg-curry) -带有操作员咖喱，功能咖喱，递归和无穷咖喱的综合咖喱库.

### Data Structures

通过使用正确的任务数据结构来编写高性能的功能代码.

* [Icepick](https://github.com/aearly/icepick) 将冻结的JavaScript对象视为持久性不可变集合的实用程序
* [Immutable.js](https://github.com/facebook/immutable-js) –不可变的持久数据收集.
* [Immer](https://github.com/mweststrate/immer)  – Immer是一个很小的程序包，用于基于写时复制机制的不可变状态.  + TS.
* [Mori](https://github.com/swannodette/mori) – ClojureScript’s persistent data structures and supporting API from the comfort of vanilla JavaScript.
* [Baobab](https://github.com/Yomguithereal/baobab) –带有游标的持久且可选的不可变数据树.
* [immutable-sequence.js](https://github.com/qiao/immutable-sequence.js) –基于JavaScript的不可变序列的高性能实现，基于 [Finger Trees](https://github.com/qiao/fingertree.js).
* [Timm](http://guigrpa.github.io/timm/) –具有快速读取和可接受写入的不变性帮助器.
* [Lazy.js](https://github.com/dtao/lazy.js) –实用程序库，在后台具有懒惰的引擎，它力求尽可能少地工作，同时要尽可能地灵活.
* [DerivableJS](https://github.com/ds300/derivablejs)  – JavaScript和TypeScript的功能性反应状态.  DerivableJS使您可以对状态位之间的关系进行优雅的声明性声明.  + TS.
* [imlazy](https://github.com/benji6/imlazy) –使用ES2015迭代协议创建和处理惰性可迭代对象的库.
* [collectable](https://github.com/frptools/collectable)  –适用于现代JavaScript和TypeScript应用程序的超高性能不可变数据结构.  + TS.
* [List](https://github.com/funkia/list) -具有全面功能API的极其快速的不可变列表.
* [prelude.ts](https://github.com/emmanueltouzery/prelude.ts)  -不可变的持久性集合，功能构造（例如Option和Either）以及组合器. 以Typescript实现，但也支持javascript.  + CT，+ TS.
* [TSTL](https://github.com/samchon/tstl)  -C ++ STL（标准模板库）在TypeScript中实现. 提供遵循功能性编程规则的STL容器，迭代器，算法和函子.  + TS.

### Algebraic Data Types

使用数学定律，而不是总是重新发明自己的东西. 代数！

* [Fantasy Land](https://github.com/fantasyland/fantasy-land) –不是图书馆，而是要遵循的Monad法律规范.
* [Static Land](https://github.com/rpominov/static-land) –规范类似于Fantasy Land，但基于静态方法而非实例方法.
* [immutable-ext](https://github.com/DrBoolean/immutable-ext) –的FantasyLand扩展 [Immutable.js](https://github.com/facebook/immutable-js).
* [daggy](https://github.com/puffnfresh/daggy) –用于创建标记的构造函数的库.
* [Sanctuary](https://github.com/plaid/sanctuary)  –使用Sanctuary可以编写无空检查的安全代码.  + CT，+ TS.
* [monet.js](http://cwmyers.github.io/monet.js/)  –通过提供丰富的Monad和其他有用功能来辅助功能编程的库.  + CT，+ TS.
* [union-type](https://github.com/paldepind/union-type) –一个小的JavaScript库，用于定义和使用联合类型.
* [freeky](https://github.com/DrBoolean/freeky) –自由单子的集合.
* [Fluture](https://github.com/Avaq/Fluture) –包含控制实用程序，高性能和出色错误消息的Future库.
* [fantasy-combinators](https://github.com/fantasyland/fantasy-combinators) –通用组合器.
* [fantasy-birds](https://github.com/fantasyland/fantasy-birds)  – Haskell软件包Data.Aviary.Birds的端口. 满足您组合需求的一切.
* [crocks](https://github.com/evilsoft/crocks)  –流行的代数数据类型的集合，其主要目标是策划并提供每种类型之间的通用接口，并提供启动所需的所有辅助功能.  -TS.
* [kudo-js](https://github.com/blitzritz/kudojs) -小型实用程序库，带有一组代数数据类型和Helper函数，可帮助您以Java脚本中的功能性编程风格编写代码
* [purify](https://github.com/gigobyte/purify)  -专注于ADT的TypeScript功能编程库.  + CT，+ TS.
* [MojiScript](https://github.com/joelnet/MojiScript)-一种异步优先，自以为是的功能语言，旨在与JavaScript引擎100％兼容
* [Pratica](https://github.com/rametta/pratica)  -小型，简单，易用的FP数据类型，适合需要快速交付可靠代码的务实且高效的开发人员.  + CT，+ TS.
* [Tifi](https://github.com/mobily/tifi)  -Tifi是用于TypeScript功能编程的库. 它解决了同时存在“未定义”和“空”的问题.  Tifi的灵感来自OCaml / Reason实用程序的选项数据类型.  + CT，+ TS.

### Lenses

* [lenses](https://github.com/DrBoolean/lenses) –可组合 [kmett](https://github.com/ekmett/lens) 风格的镜片.
* [optics](https://github.com/flunc/optics) –发射器光学器件（透镜，棱镜，iso）.
* [ramda-lens](https://github.com/ramda/ramda-lens) –：ram：：mag_right：建立在Ramda上的镜头库.
* [fantasy-lenses](https://github.com/fantasyland/fantasy-lenses)  –可组合的，不可变的获取器和设置器.  （Profunctor镜头WIP）
* [nanoscope](https://github.com/5outh/nanoscope) –有点支撑的镜头.
* [partial.lenses](https://github.com/calmm-js/partial.lenses) –部分镜头是一个用于JavaScript的全面，高性能的光学库.
* [shades](https://github.com/jamesmcnamara/shades) –受lodash启发的类似镜头的Java库.

## Functional Languages that Compile to JavaScript

* [ClojureScript](https://github.com/clojure/clojurescript) –编译 [Clojure](http://clojure.org/)，这是一种托管的Lisp，具有不变的持久数据结构，适用于JavaScript.
* [Elm](http://elm-lang.org/)  –一种类型安全的功能编程语言，用于声明性创建基于Web浏览器的图形用户界面. 在Haskell中实现.
* [Fable](http://fable.io/) -编译 [F#](http://fsharp.org) 可读的JavaScript.
* [PureScript](http://www.purescript.org/) –一种小的强类型编程语言，可编译为JavaScript.
* [Idris](http://www.idris-lang.org/) –具有相关类型的通用纯函数编程语言.
* [GHCJS](https://github.com/ghcjs/ghcjs) – [Haskell](https://www.haskell.org/) 基于GHC的JavaScript编译器.
* [ElixirScript](https://github.com/bryanjos/elixirscript) –编译以下内容的子集 [Elixir](http://elixir-lang.org/)，一种动态的，功能性的语言，旨在为JavaScript构建可扩展和可维护的应用程序.
* [Js\_of\_ocaml](http://ocsigen.org/js_of_ocaml/) –编译 [OCaml](http://ocaml.org/) 字节码转换为JavaScript，从而可以在浏览器中运行OCaml程序.
* [BuckleScript](https://bucklescript.github.io/) –的JavaScript后端 [the OCaml compiler](https://ocaml.org/).
* [Reason](https://reasonml.github.io) – Reason是OCaml的新接口，OCaml是ML语言的一种高度表达的方言，具有类型推断和静态类型检查功能.
* [Scala.js](http://www.scala-js.org/) –编译 [Scala](http://www.scala-lang.org/) 到JavaScript.
* [LiveScript](http://gkz.github.io/LiveScript/) – LiveScript具有到JavaScript的直接映射，并允许您编写没有重复样板的表达代码.
* [Quack](https://github.com/quack/quack) -一种针对PHP和JS的具有渐进式和鸭子式输入的多范例编程语言.
* [ion](https://github.com/ion-lang/ion) -没有BS JS
* [RamdaScript](https://github.com/yosbelms/ramdascript) -在RamdaJS之上编译为自以为是的JavaScript的Lisp
* [RacketScript](https://github.com/vishesh/racketscript) – RacketScript旨在充分利用JavaScript和Racket的生态系统，并使它们之间的互操作性整洁流畅.
* [Koka](https://www.microsoft.com/en-us/research/project/koka/) – Koka是一种面向函数的编程语言，使用熟悉的JavaScript（如语法）将纯值与副作用计算分开.
* [TypeScript](https://www.typescriptlang.org/) -TypeScript是JavaScript的类型化超集，可编译为纯JavaScript.

## Programming Tools

* [eslint-plugin-fp](https://github.com/jfmengels/eslint-plugin-fp) -函数式编程的ESLint规则
* [4.5](https://github.com/TylorS/4.5)  –功能断言库. 如果您更喜欢JavaScript中的函数式API和实践，则此库旨在通过惰性和单函数的面向函数的断言来解决此问题.
* [hm-def](https://github.com/xodio/hm-def) –具有Hindley Milner签名的JS的运行时类型检查.
* [ftor](https://github.com/kongware/ftor) -可插入的运行时类型检查器和功能调试工具，可通过Scott Encoding支持参数和行多态性，隐式rank-2类型和代数数据类型.

## Resources

### Books

* [Professor Frisby’s Mostly Adequate Guide to Functional Programming](https://github.com/MostlyAdequate/mostly-adequate-guide)  –这是一本关于函数范式的书，该书通常使用世界上最流行的函数编程语言：JavaScript. 这是一个实用的介绍，它通过实际示例建立了直觉. 强力推荐. 通过 [Brian Lonsdorf](https://twitter.com/drboolean) (2016)
* [Functional-Light JavaScript](https://github.com/getify/functional-light-js)  –本书探讨了可应用于JavaScript的函数式编程（FP）的核心原理. 但是，这本书与众不同的是，它在没有所有繁重术语的情况下就遵循了这些原则.
* [JavaScript Allongé](https://leanpub.com/javascriptallongesix) ，“第六”版. 尽可能少地介绍功能，但也要少！  –并建立强大的组合器和装饰器. 基础书. 通过 [Reginald  Braithwaite](https://github.com/raganwald) (2016)
* [Functional Programming in JavaScript](https://www.manning.com/books/functional-programming-in-javascript) 向JavaScript开发人员讲授可改善可扩展性，模块化，可重用性，可测试性和性能的功能技术. 通过具体的示例和无术语的解释，这本书教您如何将函数式编程应用于实际的开发任务. 路易斯·阿滕西奥（2016）
* [Eloquent JavaScript](http://eloquentjavascript.net/) . 使用JavaScript进行编程的现代介绍. 玛丽恩·哈弗贝克（Marijn Haverbeke）（2014）
* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) 讲授如何使用JavaScript的函数式编程支持创建美观，安全，易于理解和测试的代码. 通过 [Michael Fogus](https://github.com/fogus) (2013)
* [Grokking Simplicity](https://www.manning.com/books/grokking-simplicity) 从第一原理讲授函数式编程. 它对所有代码示例均使用JavaScript，并使用实际场景. 通过 [Eric Normand](https://github.com/ericnormand) (2019)
* [scriptum](https://github.com/kongware/scriptum/blob/master/README.md) -简洁的功能编程库和基于该库的在线课程

### Articles

* [FP Concepts in JavaScript](https://medium.com/@collardeau/intro-to-functional-programming-concepts-in-javascript-b0650773139c)  – JavaScript中的函数式编程概念简介. 使用Ramda库通过最简单的示例来教授合成，无点样式和仿函数的概念.
* [Functional programming with JavaScript](http://stephen-young.me.uk/2013/01/20/functional-programming-with-javascript.html) – JavaScript中的函数式编程的另一篇介绍，着重于三个关键主题：作为函数应用程序的计算，无状态，避免副作用.
* [A gentle introduction to functional JavaScript](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro/) –由四部分组成的系列介绍JavaScript中的函数式编程，可帮助您快速了解函数式编程的所有炒作.
* [Functors from first principle - explained with JS](https://dev.to/snird/functors-from-first-principle-37lh) -使用JavaScript解释函子概念.
* [Why Curry Helps](https://hughfdjackson.com/javascript/why-curry-helps/) –有关如何使用currying编写可重用和声明性代码的简短概述.
* [Favoring Curry](http://fr.umio.us/favoring-curry/) -使用Ramda进行curry的实际应用.
* [Functional Mumbo Jumbo – ADTs](http://blog.jenkster.com/2016/06/functional-mumbo-jumbo-adts.html) –代数数据类型的初学者友好介绍.
* [JavaScript and Type Thinking](https://medium.com/@yelouafi/javascript-and-type-thinking-735edddc388d)  –通过_type Thinking_了解有关JavaScript代码的原因. 引入代数数据类型作为有关程序实体的概念基础.
* [Lazy, composable, and modular JavaScript](https://codewords.recurse.com/issues/four/lazy-composable-and-modular-javascript) –使用ES6的四个新功能–迭代器，生成器，粗箭头和for –结合高阶函数，函数组成和惰性评估，以编写更简洁，更模块化的JavaScript.
* [Why Ramda](http://fr.umio.us/why-ramda/)  –对于那些不习惯函数式编程的人，Ramda似乎毫无用处. 但是，它确实提供了不同的编码样式，这是纯函数式编程语言所理所当然的样式：Ramda使您可以通过函数组合轻松构建复杂的逻辑.
* [Monads in JavaScript](https://curiosity-driven.org/monads-in-javascript) – JavaScript中的Monad设计模式简介.
* [A Monad in Practicality: First-Class Failures](http://robotlolita.me/2013/12/08/a-monad-in-practicality-first-class-failures.html) –逐步了解JavaScript中特定单子结构的一些实际用例：使用Maybe单子来处理简单的故障案例，并通过“ Either”单子或“ Validation”应用函子建模更复杂的场景.
* [Functional programming](https://glebbahmutov.com/blog/tags/functional/) – Many articles on various aspects of functional programming in JavaScript by Gleb Bahmutov.
* [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon) –来自函数式编程领域的专业术语用JavaScript进行了解释.
* [Data Structures in JavaScript](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/) –一系列博客文章，用JavaScript重新实现了各种数据结构，以更好地理解它们的优点和缺点.
* [So You Want to be a Functional Programmer](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536) -通过一些示例，易于理解，介绍了Javascript和Elm中的函数式编程.
* [Functional Programming for JavaScript People](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504) - A complete introduction to functional programming patterns by Chet Corcos with a lot of javascript examples.
* [Introduction to Immutable.js and Functional Programming Concepts](https://auth0.com/blog/intro-to-immutable-js/) -在Facebook流行的JavaScript库：Immutable.js的概述中，了解功能数据结构及其用途.
* [Master the JavaScript Interview: What is Functional Programming?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0) -@ericelliott对功能原理和词汇的简单介绍.
* [Composing Software](https://medium.com/javascript-scene/the-rise-and-fall-and-rise-of-functional-programming-composable-software-c2d91b424c8c) -@ericelliott从头开始编写了一系列有关在JavaScript ES6 +中学习功能编程和组合软件技术的文章.
* [Anonymous Recursion in JavaScript](https://dev.to/simov/anonymous-recursion-in-javascript) -有关在JavaScript中实现匿名递归的简短易懂的文章.
* [Functional Composition in Javascript](https://joecortopassi.com/articles/functional-composition-in-javascript/) –逐步说明如何在javascript中编写函数.
* [Functional Programming Principles in Javascript](https://medium.freecodecamp.org/functional-programming-principles-in-javascript-1b8fc6c3563f) -实用的代码示例，用于学习函数式编程概念，例如纯函数，不变性，一流实体和高阶函数
* [Basic Monads in Javascript](https://dev.to/rametta/basic-monads-in-javascript-3el3) -用Javascript的Maybe＆Either介绍2个简单的monad.
* [F# for JavaScript Devs](https://dev.to/rametta/f-for-js-devs-2b88) - Showcasing the similarities between F# and JavaScript
* [A practical guide to writing more functional Javascript](https://medium.com/@nadeesha/a-practical-guide-to-writing-more-functional-javascript-db49409f71) -逐步指南，将命令式JavaScript转换为更具声明性的功能性JavaScript.
* [You don't (may not) need loops ➿](https://github.com/you-dont-need/You-Dont-Need-Loops) -循环是初级程序员学习的第一批构造之一，但是循环会在软件开发过程中造成许多潜在的问题，在许多情况下可以避免.

### Videos

* [Classroom Coding with Prof. Frisby](https://www.youtube.com/watch?v=h_tkIpwbsxY&list=PLK_hdtAJ4KqX0JOs_KMAmUNTNMRYhWEaC) –通过React和JavaScript中的函数式编程构建“实用” Web应用程序的系列.
* [Hey Underscore, You're Doing It Wrong!](https://www.youtube.com/watch?v=m3svKOdZijA) – Underscore.js声称是一个功能编程库，但是真的吗？
* [Functional programming patterns for the non-mathematician](https://www.youtube.com/watch?v=AvgwKjTPMmM) –了解函子，应用程序和monad的实际用例.
* [Pure JavaScript](https://vimeo.com/49384334) 克里斯蒂安·约翰森（Christian Johansen）将向您展示如何通过留下循环并采用函数作为抽象的主要单元来显着提高游戏质量.
* [Functional programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) -来自YouTube频道FunFunFunction的Mattias Petter Johansson撰写的系列，专门针对JavaScript中的函数式编程的普及.
* [Anjana Vakil: Learning Functional Programming with JavaScript - JSUnconf 2016](https://www.youtube.com/watch?v=e-5obm1G_FY) -javascript中的功能编程的简单易懂的介绍.
* [Functional Programming Basics In ES6](https://www.youtube.com/watch?v=FYXpOjwYzcs) -ES6简化了JavaScript函数编程的完整介绍.
* [JavaScript Programmers Should Learn Algebraic Data Types -- May 2018 -- UtahJS Lehi](https://www.youtube.com/watch?v=B0VoyujJWIE) -Seth House解释了ADT（代数数据类型）如何对JavaScript开发人员有用.

### Examples and Exercises

* [FPJS-Class](https://github.com/loop-recur/FPJS-Class) –通过JavaScript学习的函数式编程.
* [functional-javascript-workshop](https://github.com/timoxley/functional-javascript-workshop) –该研讨会的目的是创建一些现实的问题，可以使用简洁，原始的惯用JavaScript来解决这些问题，以教授JavaScript的基本功能编程功能.
* [functional-frontend-architecture](https://github.com/paldepind/functional-frontend-architecture)  –功能性的前端框架. 基于Ramda + union-type-js + Flyd + Snabbdom
* [cube-composer](https://github.com/sharkdp/cube-composer) –受函数编程启发的益智游戏.
* [FP Youtube Search](https://github.com/jaysoo/example-fp-youtube-search) –带有ReactJS，Redux和FP概念的YouTube搜索应用
* [Hardcore Functional Programming in JavaScript](https://frontendmasters.com/courses/functional-javascript/)  –学习应用计算机科学研究的前沿技术来解决Javascript中的实际问题. 探索函数式编程，并逐步演示了如何使用Monads，Functor，Monoids和Applicatives等抽象界面构建示例Web应用程序.  （_commercial_）
* [Escape from Callback Mountain](https://github.com/justsml/escape-from-callback-mountain)  -基于Promise的功能JavaScript的设计和重构技巧. 主要好处包括更好的可读性，可测试性和可重用性. 麻省理工学院.
* [Functional Programming for Beginners](http://paqmind.com/courses/fp-beginner/) –数十种练习，包括解决方案和解释.
* [Learn Rx](http://reactivex.io/learnrx/) –一系列互动练习，介绍功能性（反应性）编程的五个基本要素：“ map”，“ filter”，“ concatAll”，“ reduce”和“ zip”功能.
* [Holdem Evaluator](https://github.com/laberin/holdem-eval) -另一个具有Ramda功能风格的Holdem评估器

## Community

### Related Lists

* [Awesome FRP JS](https://github.com/stoeffel/awesome-frp-js) –精选的JavaScript出色（功能性）反应式编程内容列表.
* [lucasviola/Awesome Functional Programming](https://github.com/lucasviola/awesome-functional-programming) –关于函数式编程理论和学习资料的丰富资源.
* [xgrommx/Awesome Functional Programming](https://github.com/xgrommx/awesome-functional-programming) –有关函数式编程的大量文章，以及用于许多编程语言的大量函数库.
* [Functional Programming Resources In JavaScript](https://github.com/busypeoples/functional-programming-javascript)
* [tk-learning-center/Functional Programming Learning Path](https://github.com/tk-learning-center/functional-programming-learning-path) -函数式编程的学习之路

### Talk

* [Functional Programming Slack channel](https://fpchat-invite.herokuapp.com/) –具有JavaScript友好频道的社区，以及许多其他有关函数式编程的频道.


## Contribution

 ：star：欢迎提出建议和PR！  ：星：

请阅读 [contribution guidelines](https://github.com/stoeffel/awesome-fp-js/blob/master/./contributing.md) 开始.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Christoph Hermann](http://stoeffel.github.io/) 放弃了此作品的所有版权以及相关或邻近的权利.
