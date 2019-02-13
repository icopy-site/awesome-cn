## Redux Libraries & Learning Material [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/brillout/awesome-redux/master/redux-logo.svg" align="right" width="110">](http://redux.js.org/)

&gt; Redux是JavaScript应用程序的状态容器.

 - 官方网站： [`devarchy.com/redux`](https://devarchy.com/redux)
 - 使用devarchy将库添加到目录中
 
 <br/>

#### Contents
- [Code Architecture](#code-architecture)
- [Utilities](#utilities)
- [Code Style](#code-style)
- [Dev tools / Inspection tools](#dev-tools--inspection-tools)
- [React Integration](#react-integration)
- [Other Integrations](#other-integrations)
- [Boilerplate](#boilerplate)
- [Miscellaneous](#miscellaneous)
- [Learning Material](#learning-material)
- [Community](#community)

<br/>

## Code Architecture

 *旨在改善源代码的整体结构.  使代码的推理更容易.*

 - [redux-schema](https://github.com/ddsol/redux-schema) -  Redux的自动操作，缩减器和验证.
 - [redux-tcomb](https://github.com/gcanti/redux-tcomb) -  Redux的不可变和类型检查状态和操作.
 - [redux-action-tree](https://github.com/cerebral/redux-action-tree) - 使用Redux运行的脑信号.
 - [redux-elm](https://github.com/salsita/redux-elm) -  JavaScript中的Elm架构.


## Utilities

 - [redux-orm](https://github.com/tommikaikkonen/redux-orm) - 小而简单且不可变的ORM，用于管理Redux存储中的关系数据.
 - [redux-api-middleware](https://github.com/agraboso/redux-api-middleware) - 用于调用API的Redux中间件.
 - [redux-ignore](https://github.com/omnidan/redux-ignore) - 高阶减速器忽略Redux动作.
 - [redux-modifiers](https://github.com/calvinfroedge/redux-modifiers) - 用于编写Redux Reducer以在各种数据结构上运行的通用函数的集合.
 - [rereduce](https://github.com/slorber/rereduce) -  Redux的Reducer库.
 - [redux-search](https://github.com/treasure-data/redux-search) - 用于客户端搜索的Redux绑定.
 - [redux-logger](https://github.com/evgenyrodionov/redux-logger) -  Redux的Logger中间件.
 - [redux-immutable](https://github.com/gajus/redux-immutable) -  Redux-immutable用于创建与Immutable.js状态一起使用的Redux combineReducers的等效函数.
 - [reselect](https://github.com/reactjs/reselect) -  Redux的选择器库.
 - [redux-requests](https://github.com/idolize/redux-requests) - 使用Redux reducer管理正在进行的请求，以避免发出重复请求.
 - [redux-undo](https://github.com/omnidan/redux-undo) - 更高级的减少器，用于向Redux状态容器添加撤消/重做功能.
 - [redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) -  Redux的Bug报告器和错误播放工具.
 - [redux-transducers](https://github.com/acdlite/redux-transducers) -  Redux的传感器实用程序.


### Store Persistence

 - [redux-storage](https://github.com/michaelcontento/redux-storage) -  Redux的持久层，具有灵活的后端.
 - [redux-persist](https://github.com/rt2zz/redux-persist) - 坚持和补充Redux商店.


### Side Effects

*副作用/异步动作*

 - [redux-saga](https://github.com/yelouafi/redux-saga) -  Redux应用程序的替代副作用模型.
 - [redux-promise-middleware](https://github.com/pburtchaell/redux-promise-middleware) -  Redux中间件，用于通过条件乐观更新来解决和拒绝承诺.
 - [redux-effects](https://github.com/redux-effects/redux-effects) - 你编写纯函数，redux-effects处理其余的函数.
 - [redux-thunk](https://github.com/gaearon/redux-thunk) -  Redux的Thunk中间件.
 - [redux-connect](https://github.com/makeomatic/redux-connect) - 提供装饰器来解析react-router中的异步道具，对于在React中处理服务器端渲染非常有用.
 - [redux-loop](https://github.com/redux-loop/redux-loop) - 榆树效果的端口和榆树建筑到Redux，允许您通过从减速器返回来自然而纯粹地对您的效果进行排序.
 - [redux-side-effects](https://github.com/salsita/redux-side-effects) -  Redux工具套件，用于在减压器内保持所有副作用，同时保持其纯度.
 - [redux-logic](https://github.com/jeffbski/redux-logic) - 用于组织业务逻辑和动作副作用的Redux中间件.
 - [redux-observable](https://github.com/redux-observable/redux-observable) - 使用“Epics”在Redux中实现动作副作用的RxJS中间件.
 - [redux-ship](https://github.com/clarus/redux-ship) - 可组合，可测试和可打字的副作用.


## Code Style

*旨在使部分源代码更易于读/写.*

 - [redux-act](https://github.com/pauldijou/redux-act) -  Opinionated lib为Redux创建动作和缩减器.
 - [redux-crud](https://github.com/Versent/redux-crud) -  Redux CRUD应用程序的标准操作和缩减器集.


## Dev tools / Inspection tools

 - [redux-devtools-inspector](https://github.com/alexkuz/redux-devtools-inspector) - 另一个Redux DevTools监视器.
 - [redux-diff-logger](https://github.com/fcomb/redux-diff-logger) -  Redux状态之间的差异记录器.
 - [redux-devtools-chart-monitor](https://github.com/romseguy/redux-devtools-chart-monitor) -  Redux DevTools的图表监视器.
 - [redux-devtools](https://github.com/gaearon/redux-devtools) - 用于Redux的DevTools，具有热重新加载，动作重放和可自定义的UI.
 - [redux-devtools-dispatch](https://github.com/YoruNoHikage/redux-devtools-dispatch) - 手动发送您的操作以测试您的应用是否反应良好.
 - [redux-devtools-dock-monitor](https://github.com/gaearon/redux-devtools-dock-monitor) -  Redux DevTools显示器的可调整大小和可移动的底座.
 - [redux-devtools-filterable-log-monitor](https://github.com/bvaughn/redux-devtools-filterable-log-monitor) -  Redux DevTools的可过滤树视图监视器.
 - [redux-devtools-log-monitor](https://github.com/gaearon/redux-devtools-log-monitor) - 具有树视图的Redux DevTools的默认监视器.
 - [remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) - 远程Redux DevTools.


## React Integration

 - [redux-test-recorder](https://github.com/conorhastings/redux-test-recorder) -  Redux中间件，通过ui交互自动生成Reducer测试.
 - [react-redux](https://github.com/reactjs/react-redux) -  Redux的官方React绑定.
 - [react-easy-universal](https://github.com/keystonejs/react-easy-universal) - Universal Routing &amp; Rendering with React &amp; Redux was too hard. Now it&#39;s easy.
 - [redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) - 一组包装器组件，以便于使用带有Redux Form的Material UI.


### Routing

 - [redux-async-connect](https://github.com/Rezonans/redux-async-connect) - 它允许您请求异步数据，将它们存储在Redux状态并将它们连接到您的React组件.
 - [redux-tiny-router](https://github.com/Agamennon/redux-tiny-router)   - 为Redux制作的路由器，适用于通用应用程序.  停止使用路由器作为控制器，它只是状态.
 - [redux-router](https://github.com/acdlite/redux-router) -  React Router的Redux绑定 - 将您的路由器状态保留在Redux存储区中.
 - [react-router-redux](https://github.com/reactjs/react-router-redux) - 无情的简单绑定，以保持react-router和Redux同步.
 - [ground-control](https://github.com/raisemarketplace/ground-control) -  React Router＆Redux的可扩展的reducer管理和强大的数据获取功能.


### Forms

 - [redux-form](https://github.com/erikras/redux-form) - 使用react-redux在Redux存储中保持表单状态的高阶组件.
 - [react-redux-form](https://github.com/davidkpiano/react-redux-form) - 使用Redux在React中轻松创建表单.


### Component State

 - [redux-react-local](https://github.com/threepointone/redux-react-local) - 通过Redux的本地组件状态.
 - [redux-ui](https://github.com/tonyhb/redux-ui) -  React Redux的简易UI状态管理.


## Other Integrations


### Flux

 - [redux-actions](https://github.com/acdlite/redux-actions) -  Redux的Flux标准动作实用程序.
 - [redux-promise](https://github.com/acdlite/redux-promise) - 适用于Redux的FSA兼容承诺中间件.


### Backbone

 - [backbone-redux](https://github.com/redbooth/backbone-redux) - 简化方法，使您的主干集合和Redux存储保持同步.


### Falcor

 - [redux-falcor](https://github.com/ekosz/redux-falcor) - 将Redux前端连接到您的falcor后端.


### RxJS

 - [redux-observable](https://github.com/redux-observable/redux-observable) - 使用“Epics”在Redux中实现动作副作用的RxJS中间件.
 - [rx-redux](https://github.com/jas-chen/rx-redux) - 使用RxJS重新实现Redux.
 - [redux-rx](https://github.com/acdlite/redux-rx) -  Redux的RxJS实用程序.
 - [redurx](https://github.com/shiftyp/redurx) - Redux&#39;ish Functional State Management using RxJS.


### Electron

 - [redux-electron-store](https://github.com/samiskin/redux-electron-store) -  Redux存储增强器，允许电子过程之间的自动同步.


### Deku

 - [deku-redux](https://github.com/troch/deku-redux) -  deku &lt;v2中Redux的绑定.


### Other

 - [redux-rollbar-middleware](https://github.com/netguru/redux-rollbar-middleware) -  Redux中间件，它包含动作中的异常并将它们发送到具有当前状态的Rollbar.
 - [kasia](https://github.com/outlandishideas/kasia) - 针对WordPress API的React Redux工具集.


## Boilerplate

*锅炉/脚手架/入门套件/发电机/堆叠套装*

 - [redux-cli](https://github.com/SpencerCDixon/redux-cli) - 用于更快地构建Redux / React应用程序的意见CLI.
 - [reactuate](https://github.com/reactuate/reactuate) -  React / Redux堆栈（不是样板工具包）.
 - [react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) - 用于Chrome扩展React.js项目的Boilerplate.
 - [universal-redux](https://github.com/bdefore/universal-redux)   -  Npm包，可让您直接使用通用（同构）渲染编写React和Redux编码.  如果您愿意，只管理Express设置或Webpack配置.
 - [generator-react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - 使用ASP.NET Core 1构建同构React应用程序的起点，利用现有技术.
 - [generator-redux](https://github.com/banderson/generator-redux) - 用于Redux的CLI工具：使用devtools的下一代功能Flux / React.
 - [generator-react-webpack-redux](https://github.com/stylesuxx/generator-react-webpack-redux) -  React Webpack Generator，包括Redux支持.
 - [socrates](https://github.com/matthewmueller/socrates) - 小型（8kb），包含电池的Redux商店，以减少样板并促进良好习惯.


## Miscellaneous

 - [redux-core](https://github.com/jas-chen/redux-core) - 最小的Redux.


## Learning Material

 -  ** Redux的概念**

    [Redux official documentation](http://redux.js.org/) 在解释Redux的核心原则方面做得非常出色.

 -  **为什么不可变数据结构**

    该 [guide on performance](https://facebook.github.io/react/docs/advanced-performance.html) React的官方文档很好地解释了不可变数据结构是什么以及它们为何扮演重要角色.

 - **副作用**

    [Redux Loop's readme](https://github.com/redux-loop/redux-loop) 在Redux的上下文中提供了对Side Effects的深入了解.

阅读上述材料将为您使用Redux编写应用程序提供良好的开端.
如果您对更多内容感到好奇，请查看以下资源.

 -  **功能编程 - 基础知识**

    这个 [post](http://jaysoo.ca/2016/01/13/functional-programming-little-ideas/) 在构建YouTube即时搜索演示应用程序时，介绍了函数式编程的基本概念.

 -  **反应式编程**

    这个 [introduction to Reactive Programming](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754) 详细解释了反应式编程.

 -  **功能编程 - 超越**

    Well written [article](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504) 讨论了在函数式语言中实现的有趣的计算机科学概念以及它们如何应用于JavaScript.

 -  ** Monads **

     对monads感到好奇吗？  维基百科给了一个好处 [overview on monads](https://en.wikipedia.org/wiki/Monad_(functional_programming)）和 [this article](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html) 通过图形和简单示例更详细地解释了monads.


## Community

- [Reddit](https://www.reddit.com/r/reduxjs/)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/redux)
- [Discord](https://discord.gg/0ZcbPKXt5bZ6au5t)
- [Slack](http://slack.redux.io/)
- [Gitter](https://gitter.im/reactjs/redux)
- [`#rackt` on freenode](https://webchat.freenode.net/)
