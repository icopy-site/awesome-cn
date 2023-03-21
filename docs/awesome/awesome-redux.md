<div class="github-widget" data-repo="brillout/awesome-redux"></div>
## Redux Libraries & Learning Material [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/brillout/awesome-redux/master/redux-logo.svg" align="right" width="110">](http://redux.js.org/)

&gt; Redux 是 JavaScript 应用程序的状态容器.

 - 官方网站： [`devarchy.com/redux`](https://devarchy.com/redux)
 - 使用 devarchy 将图书馆添加到目录
 
 <br/>


<br/>

## Code Architecture

 *旨在完善源代码的整体结构. 使对代码的推理更容易. *

 - [redux-schema](https://github.com/ddsol/redux-schema) - Redux 的自动操作、reducer 和验证.
 - [redux-tcomb](https://github.com/gcanti/redux-tcomb) - Redux 的不可变和类型检查状态和操作.
 - [redux-action-tree](https://github.com/cerebral/redux-action-tree) - 与 Redux 一起运行的大脑信号.
 - [redux-elm](https://github.com/salsita/redux-elm) - JavaScript 中的 Elm 架构.


## Utilities

 - [redux-orm](https://github.com/tommikaikkonen/redux-orm) - 小型、简单且不可变的 ORM，用于管理 Redux 存储中的关系数据.
 - [redux-api-middleware](https://github.com/agraboso/redux-api-middleware) - 用于调用 API 的 Redux 中间件.
 - [redux-ignore](https://github.com/omnidan/redux-ignore) - 忽略 Redux 动作的高阶减速器.
 - [redux-modifiers](https://github.com/calvinfroedge/redux-modifiers) - 用于编写 Redux reducer 以对各种数据结构进行操作的通用函数集合.
 - [rereduce](https://github.com/slorber/rereduce) - Redux 的减速器库.
 - [redux-search](https://github.com/treasure-data/redux-search) - 用于客户端搜索的 Redux 绑定.
 - [redux-logger](https://github.com/evgenyrodionov/redux-logger) - 用于 Redux 的记录器中间件.
 - [redux-immutable](https://github.com/gajus/redux-immutable) - Redux-immutable 用于创建与 Immutable.js 状态一起使用的 Redux combineReducers 的等效功能.
 - [reselect](https://github.com/reactjs/reselect) - Redux 的选择器库.
 - [redux-requests](https://github.com/idolize/redux-requests) - 使用 Redux reducer 管理飞行中的请求以避免发出重复请求.
 - [redux-undo](https://github.com/omnidan/redux-undo) - 向 Redux 状态容器添加撤消/重做功能的高阶减速器.
 - [redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) - 用于 Redux 的错误报告器和错误回放工具.
 - [redux-transducers](https://github.com/acdlite/redux-transducers) - 用于 Redux 的传感器实用程序.


### Store Persistence

 - [redux-storage](https://github.com/michaelcontento/redux-storage) - 具有灵活后端的 Redux 的持久层.
 - [redux-persist](https://github.com/rt2zz/redux-persist) - 坚持并补充 Redux 商店.


### Side Effects

*副作用/异步操作*

 - [redux-saga](https://github.com/yelouafi/redux-saga) - Redux 应用程序的替代副作用模型.
 - [redux-promise-middleware](https://github.com/pburtchaell/redux-promise-middleware) - Redux 中间件，用于通过有条件的乐观更新解决和拒绝承诺.
 - [redux-effects](https://github.com/redux-effects/redux-effects) - You write pure functions, redux-effects handles the rest.
 - [redux-thunk](https://github.com/gaearon/redux-thunk) - 用于 Redux 的 Thunk 中间件.
 - [redux-connect](https://github.com/makeomatic/redux-connect) - 提供用于解析 react-router 中的异步 props 的装饰器，对于处理 React 中的服务器端渲染非常有用.
 - [redux-loop](https://github.com/redux-loop/redux-loop) - elm-effects 和 Elm Architecture 到 Redux 的端口，允许您通过从 reducer 返回它们来自然而纯粹地对您的效果进行排序.
 - [redux-side-effects](https://github.com/salsita/redux-side-effects) - Redux 工具集，用于将所有副作用保留在你的减速器中，同时保持它们的纯度.
 - [redux-logic](https://github.com/jeffbski/redux-logic) - 用于组织业务逻辑和操作副作用的 Redux 中间件.
 - [redux-observable](https://github.com/redux-observable/redux-observable) - 使用“Epics”在 Redux 中用于动作副作用的 RxJS 中间件.
 - [redux-ship](https://github.com/clarus/redux-ship) - 可组合、可测试和可打字的副作用.


## Code Style

*旨在使部分源代码更易于阅读/编写.*

 - [redux-act](https://github.com/pauldijou/redux-act) - 为 Redux 创建动作和 reducers 的自以为是的库.
 - [redux-crud](https://github.com/Versent/redux-crud) - 用于 Redux CRUD 应用程序的一组标准操作和缩减器.


## Dev tools / Inspection tools

 - [redux-devtools-inspector](https://github.com/alexkuz/redux-devtools-inspector) - 另一个 Redux DevTools 监视器.
 - [redux-diff-logger](https://github.com/fcomb/redux-diff-logger) - Redux 状态之间的差异记录器.
 - [redux-devtools-chart-monitor](https://github.com/romseguy/redux-devtools-chart-monitor) - Redux DevTools 的图表监视器.
 - [redux-devtools](https://github.com/gaearon/redux-devtools) - 用于 Redux 的 DevTools，具有热重载、动作回放和可自定义的 UI.
 - [redux-devtools-dispatch](https://github.com/YoruNoHikage/redux-devtools-dispatch) - 手动发送您的操作以测试您的应用程序是否反应良好.
 - [redux-devtools-dock-monitor](https://github.com/gaearon/redux-devtools-dock-monitor) - 用于 Redux DevTools 监视器的可调整大小和可移动的底座.
 - [redux-devtools-filterable-log-monitor](https://github.com/bvaughn/redux-devtools-filterable-log-monitor) - 用于 Redux DevTools 的可过滤树视图监视器.
 - [redux-devtools-log-monitor](https://github.com/gaearon/redux-devtools-log-monitor) - 具有树视图的 Redux DevTools 的默认监视器.
 - [remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) - 远程 Redux DevTools.


## React Integration

 - [redux-test-recorder](https://github.com/conorhastings/redux-test-recorder) - Redux 中间件通过 ui 交互自动为 reducers 生成测试.
 - [react-redux](https://github.com/reactjs/react-redux) - Redux 的官方 React 绑定.
 - [react-easy-universal](https://github.com/keystonejs/react-easy-universal) - Universal Routing &amp; Rendering with React &amp; Redux was too hard. Now it&#39;s easy.
 - [redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) - 一组包装器组件，以方便将 Material UI 与 Redux Form 结合使用.


### Routing

 - [redux-async-connect](https://github.com/Rezonans/redux-async-connect) - 它允许您请求异步数据，将它们存储在 Redux 状态并将它们连接到您的 React 组件.
 - [redux-tiny-router](https://github.com/Agamennon/redux-tiny-router)  - 为 Redux 和通用应用程序制作的路由器. 停止将路由器用作控制器，它只是状态.
 - [redux-router](https://github.com/acdlite/redux-router) - React Router 的 Redux 绑定——将路由器状态保存在 Redux 存储中.
 - [react-router-redux](https://github.com/reactjs/react-router-redux) - 无情的简单绑定以保持 react-router 和 Redux 同步.
 - [ground-control](https://github.com/raisemarketplace/ground-control) - 可扩展的 reducer 管理和强大的 React Router 和 Redux 数据获取.


### Forms

 - [redux-form](https://github.com/erikras/redux-form) - 高阶组件使用 react-redux 将表单状态保存在 Redux 存储中.
 - [react-redux-form](https://github.com/davidkpiano/react-redux-form) - 使用 Redux 在 React 中轻松创建表单.


### Component State

 - [redux-react-local](https://github.com/threepointone/redux-react-local) - 通过 Redux 的本地组件状态.
 - [redux-ui](https://github.com/tonyhb/redux-ui) - React Redux 的简单 UI 状态管理.


## Other Integrations


### Flux

 - [redux-actions](https://github.com/acdlite/redux-actions) - 用于 Redux 的 Flux Standard Action 实用程序.
 - [redux-promise](https://github.com/acdlite/redux-promise) - 适用于 Redux 的符合 FSA 的承诺中间件.


### Backbone

 - [backbone-redux](https://github.com/redbooth/backbone-redux) - 保持主干集合和 Redux 存储同步的简单方法.


### Falcor

 - [redux-falcor](https://github.com/ekosz/redux-falcor) - 将你的 Redux 前端连接到你的 falcor 后端.


### RxJS

 - [redux-observable](https://github.com/redux-observable/redux-observable) - 使用“Epics”在 Redux 中用于动作副作用的 RxJS 中间件.
 - [rx-redux](https://github.com/jas-chen/rx-redux) - 使用 RxJS 重新实现 Redux.
 - [redux-rx](https://github.com/acdlite/redux-rx) - 用于 Redux 的 RxJS 实用程序.
 - [redurx](https://github.com/shiftyp/redurx) - Redux&#39;ish Functional State Management using RxJS.


### Electron

 - [redux-electron-store](https://github.com/samiskin/redux-electron-store) - 允许电子进程之间自动同步的 Redux 存储增强器.


### Deku

 - [deku-redux](https://github.com/troch/deku-redux) - deku &lt; v2 中 Redux 的绑定.


### Other

 - [redux-rollbar-middleware](https://github.com/netguru/redux-rollbar-middleware) - Redux 中间件，将异常包装在动作中，并将它们以当前状态发送到 Rollbar.
 - [kasia](https://github.com/outlandishideas/kasia) - 用于 WordPress API 的 React Redux 工具集.


## Boilerplate

*样板/脚手架/入门套件/发电机/堆栈集成*

 - [redux-cli](https://github.com/SpencerCDixon/redux-cli) - 用于更快构建 Redux/React 应用程序的自以为是的 CLI.
 - [reactuate](https://github.com/reactuate/reactuate) - React/Redux 堆栈（不是样板工具包）.
 - [react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) - 用于 Chrome 扩展 React.js 项目的样板.
 - [universal-redux](https://github.com/bdefore/universal-redux)  - Npm 包，可让您直接跳入使用通用（同构）渲染编写 React 和 Redux 代码. 如果你愿意，只管理 Express 设置或 Webpack 配置.
 - [generator-react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - 利用现有技术，使用 ASP.NET Core 1 构建同构 React 应用程序的起点.
 - [generator-redux](https://github.com/banderson/generator-redux) - 适用于 Redux 的 CLI 工具：下一代功能性 Flux/React with devtools.
 - [generator-react-webpack-redux](https://github.com/stylesuxx/generator-react-webpack-redux) - React Webpack 生成器，包括 Redux 支持.
 - [socrates](https://github.com/matthewmueller/socrates) - 小型 (8kb)、包含电池的 Redux 商店，可减少样板文件并促进良好习惯.


## Miscellaneous

 - [redux-core](https://github.com/jas-chen/redux-core) - 最小的 Redux.


## Learning Material

 - **Redux 的概念**

    [Redux official documentation](http://redux.js.org/) 很好地解释了 Redux 的核心原则.

 - **为什么不可变数据结构**

    这 [guide on performance](https://facebook.github.io/react/docs/advanced-performance.html) React 的官方文档很好地解释了什么是不可变数据结构以及它们为何发挥重要作用.

 - **副作用**

    [Redux Loop's readme](https://github.com/redux-loop/redux-loop) 在 Redux 的背景下对副作用有很好的了解.

阅读上述材料将为您使用 Redux 编写应用程序提供一个良好的开端.
如果您对更多信息感到好奇，请查看以下资源.

 - **函数式编程 - 基础**

    这 [post](http://jaysoo.ca/2016/01/13/functional-programming-little-ideas/) 在构建 YouTube 即时搜索演示应用程序时回顾了函数式编程的基本概念.

 - **响应式编程**

    这 [introduction to Reactive Programming](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754) 清晰地解释了响应式编程.

 - **函数式编程 - 超越**

    写得好 [article](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504) 它讨论了用函数式语言实现的有趣的计算机科学概念，以及这些概念如何应用于 JavaScript.

 - **单子**

    对 monad 感到好奇？ 维基百科给出了一个很好 [overview on monads](https://en.wikipedia.org/wiki/Monad_(functional_programming)） 和 [this article](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html) 通过图形和简单示例更详细地解释 monad.


## Community

- [Reddit](https://www.reddit.com/r/reduxjs/)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/redux)
- [Discord](https://discord.gg/0ZcbPKXt5bZ6au5t)
- [Slack](http://slack.redux.io/)
- [Gitter](https://gitter.im/reactjs/redux)
- [`#rackt` on freenode](https://webchat.freenode.net/)
