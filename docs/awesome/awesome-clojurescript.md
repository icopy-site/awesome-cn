<img src="https://avatars2.githubusercontent.com/u/12118456?v=3&s=75"
     ALIGN = “右”/&gt;

## Awesome ClojureScript

##### A community driven list of ClojureScript frameworks, libraries and wrappers.

---

  - [Books](#books)
  - [Canvas](#canvas)
  - [Client/Server Communication](#clientserver-communication)
  - [Code Analysis](#code-analysis)
  - [Data Serialization](#data-serialization)
  - [Data Visualization](#data-visualization)
  - [Database](#database)
  - [Development](#development)
  - [Document Object Model](#document-object-model)
  - [Documentation](#documentation)
  - [Graphics](#graphics)
  - [HTTP Handler](#http-handler)
  - [Internationalization](#internationalization)
  - [JavaScript Interoperability](#javascript-interoperability)
  - [Miscellaneous](#miscellaneous)
  - [React.js Interface](#reactjs-interface)
  - [Reactive Programming](#reactive-programming)
  - [Routing](#routing)
  - [State Management](#state-management)
  - [Testing](#testing)
  - [Validation](#validation)
  - [Web Framework & Template](#web-framework--template)
  - [WebSockets](#websockets)


- [Contributing](#contributing)
- [License](#license)

* * *

### Books
- [ClojureScript Unraveled](http://funcool.github.io/clojurescript-unraveled/) - 全面介绍ClojureScript语言及其惯用法.
- [Transforming Data with ClojureScript](http://langintro.com/cljsbook/index.html) -  ClojureScript的初学者指南，包含交互式示例和练习.

### Canvas
- [Monet](https://github.com/rm-hull/monet) - 一个小型ClojureScript库，可以更轻松地使用画布和视觉效果.
- [Quamolit](https://github.com/Quamolit/quamolit) - 一个微小的声明性动画库，灵感来自React.


### Client/Server Communication
- [cljs-ajax](https://github.com/JulianBirch/cljs-ajax) -  ClojureScript和Clojure的简单Ajax客户端.
- 累积 [server](https://github.com/Cumulo/cumulo-server)/[client](https://github.com/Cumulo/cumulo-client) - 基于WebSocets和diff / patch在客户端之间同步数据的一对库.
- [Fetch](https://github.com/LightTable/fetch) -  ClojureScript库，使客户端/服务器交互无痛.


### Code Analysis
- [kibit](https://github.com/jonase/kibit) - 静态代码分析器，用于查找可以使用更惯用的函数或宏重写的代码模式.


### Data Serialization
- [Cljson](https://github.com/tailrecursion/cljson) - 用于加速浏览器数据反序列化的Clojure / ClojureScript库.
- [Transit](https://github.com/cognitect/transit-cljs) - 用于在以不同编程语言编写的应用程序之间传递值的数据交换格式和库集.


### Data Visualization
- [C2](https://keminglabs.com/c2) - 它允许您以声明方式创建基于数据的HTML和SVG标记.


### Database
- [Datascript](https://github.com/tonsky/datascript) -  ClojureScript中的不可变内存数据库和Datalog查询引擎.
- [Jaki](https://github.com/pandeiro/jaki) - 一个简单的ClojureScript CouchDB客户端.
- [Konserve](https://github.com/replikativ/konserve) - 具有core.async的clojuresque键值/文档存储协议.
- [specql](https://github.com/tatut/specql) - 用于使用命名空间键的简单PostgreSQL查询的库.

### Development
- [Ambly](https://github.com/omcljs/ambly) -  ClojureScript REPL到iOS JavaScriptCore.
- [cljs-devtools](https://github.com/binaryage/cljs-devtools) - 在Chrome Devtools中更好地呈现ClojureScript值.
- [Devcards](https://github.com/bhauman/devcards) -  Devcards旨在为ClojureScript提供可视化的REPL体验.
- [lein-cljsbuild](https://github.com/emezeske/lein-cljsbuild) -  Leiningen插件，使ClojureScript开发变得简单.
- [lein-figwheel](https://github.com/bhauman/lein-figwheel) - 将ClojureScript代码更改推送到客户端的Leiningen插件.
- [Lumo](https://github.com/anmonteiro/lumo) - 快速，跨平台，独立的ClojureScript环境.
- [Planck](https://github.com/mfikes/planck) - 基于JavaScriptCore的macOS和Linux的独立ClojureScript REPL.
- [Ribol](http://docs.caudate.me/ribol/) -  clojure / clojurescript的条件重启.
- [shadow-cljs](https://github.com/thheller/shadow-cljs) -  ClojureScript编译变得简单


### Document Object Model
- [cljs-binding](https://github.com/fluentsoftware/cljs-binding) – It binds html elements to ClojureScript functions.
- [Crate](https://github.com/ibdknox/crate) -  Hiccup的ClojureScript实现.
- [Dominator](https://github.com/dubiousdavid/dominator) -  ClojureScript中的Virtual-Dom.
- [Dommy](https://github.com/plumatic/dommy) - 一个严肃的ClojureScript模板和DOM操作库.
- [Enfocus](http://ckirkendall.github.io/enfocus-site/) - 受Enlive启发的ClojureScript的DOM操作和模板库.
- [Freactive](https://github.com/aaronc/freactive) - 一个高性能，纯粹的Clojurescript，声明性DOM库，灵感来自试剂，om，反射和打嗝.
- [Hiccups](https://github.com/teropa/hiccups) - 打嗝的ClojureScript端口.
- [Hickory](https://github.com/davidsantiago/hickory) - 它将HTML解析为Clojure数据结构，因此您可以分析，转换和输出回HTML.
- [json-html](https://github.com/yogthos/json-html) - 提供JSON并获取具有该JSON的人类表示的DOM节点.
- [Kioo](https://github.com/ckirkendall/kioo) - 用于Facebook的React和Om在ClojureScript中的DOM操作和模板库.
- [Sablono](https://github.com/r0man/sablono) - 用于ClojureScript中Facebook反应的Lisp / Hiccup风格模板.


### Documentation
- [codox](https://github.com/weavejester/codox) - 用于从Clojure或ClojureScript源代码生成API文档的工具.


### Graphics
- [geom](https://github.com/thi-ng/geom) - 用于Clojure / Clojurescript的2D / 3D几何工具包.


### HTTP Handler
- [Castra](https://github.com/hoplon/castra) -  Clojure的HTTP远程过程调用处理程序.


### Internationalization
- [Tower](https://github.com/ptaoussanis/tower) -  Clojure（脚本）i18n和L10n库.
- [Tempura](https://github.com/ptaoussanis/tempura) - 一个Clojure（脚本）i18n库，接替Tower


### JavaScript Interoperability
- [CLJSJS](http://cljsjs.github.io/) -  Clojurescript开发人员依赖Javascript库的简便方法.
- [Jayq](https://github.com/ibdknox/jayq) - 用于jQuery的ClojureScript包装器.
- [Purnam](https://github.com/zcaudate/purnam) - 一个ClojureScript库，旨在提供更好的clojurescript / javascript互操作，测试和文档工具.
- [Pylon](https://github.com/bodil/pylon) -  100％Clojurescript中的Javascript类系统.


### Miscellaneous
- [Automat](https://github.com/ztellman/automat) - 一个用于定义和使用有限状态自动机的Clojure（脚本）库，受Ragel的启发.
- [Bardo](https://github.com/pleasetrythisathome/bardo) - 用于功能插值和转换的Clojure（脚本）库.
- [core.async](https://github.com/clojure/core.async/) -  Clojure（脚本）库，旨在为异步编程和通信提供便利.
- [Entanglement](https://github.com/Frozenlock/entanglement) - 它从其他原子创建原子并将数据链接在一起.
- [Garden](https://github.com/noprompt/garden) - 用于在Clojure和ClojureScript中渲染CSS的库.
- [inflections-clj](https://github.com/r0man/inflections-clj) - 用于Clojure和ClojureScript的类似Rails的变形库.
- [Instaparse](https://github.com/lbradstreet/instaparse-cljs) - 它旨在成为在ClojureScript中构建解析器的最简单方法.
- [Keybind](https://github.com/piranha/keybind) - 用于在浏览器中处理键绑定（快捷方式）的库.
- [markdown-clj](https://github.com/yogthos/markdown-clj) -  Clojure / ClojureScript中的Markdown解析器.
- [om-tools](https://github.com/plumatic/om-tools) - 它旨在提供使用Om的API构建组件时经常有用的高阶抽象和实用程序.
- [Quil](https://github.com/quil/quil) - 处理和图形编程库.
- [reforms](https://github.com/bilus/reforms) -  Om和Reagent的美丽Bootstrap 3表格.
- [reagent-forms](https://github.com/reagent-project/reagent-forms/) - 试剂的Bootstrap表单组件.
- [Respo](https://github.com/mvc-works/respo) - 受React启发的A ** Respo ** nsive DOM库.
- [Sepal.clj](https://github.com/Cirru/sepal.clj) - 使用宏系统从字符串和向量的向量生成Clojure代码的库.
- [Truss](https://github.com/ptaoussanis/truss) -  Clojure / ClojureScript的自称断言API.

### [React.js](https://facebook.github.io/react/) Interface
- [Brutha](https://github.com/weavejester/brutha) -  React的简单而实用的ClojureScript接口.
- [Om](https://github.com/omcljs/om) -  React的强大接口，利用其面向对象的结构.
- [Quiescent](https://github.com/levand/quiescent) - 它有利于功能性风格，完全无国籍.
- [re-com](https://github.com/Day8/re-com) -  Reagent可重用组件的ClojureScript库.
- [Reagent](http://reagent-project.github.io/) - 简约，功能齐全.
- [Rum](https://github.com/tonsky/rum) -  Decomplected，可扩展，简单.


### Reactive Programming
- [Javelin](https://github.com/hoplon/javelin) -  ClojureScript的功能反应式编程库.
- [Manifold-cljs](https://github.com/dm3/manifold-cljs) - 港口 [Manifold](https://github.com/ztellman/manifold) 到ClojureScript.
- [Reagi](https://github.com/weavejester/reagi) - 用于Clojure和ClojureScript的FRP库，构建于core.async之上.
- [rx-cljs](https://github.com/leonardoborges/rx-cljs) - 用于Javascript的Reactive Extensions（Rx）的ClojureScript包装器.
- [Yolk](https://github.com/Cicayda/yolk) - 一个围绕bacon.js的瘦ClojureScript包装器.


### Routing
- [Bidi](https://github.com/juxt/bidi) -  Clojure（脚本）数据驱动的路由库.
- [Router](https://github.com/darkleaf/router)   - 用于Clojure / Script的双向环路由器.  REST面向.
- [Secretary](https://github.com/gf3/secretary) -  ClojureScript的客户端路由器.
- [Silk](https://github.com/DomKM/silk) - 用于Clojure和ClojureScript的同构路由库.


### State Management
- [component](https://github.com/stuartsierra/component) - 在Clojure（脚本）中管理有状态对象的生命周期.
- [hodgepodge](http://funcool.github.io/hodgepodge/) -  HTML5存储的惯用ClojureScript接口.
- [mount](https://github.com/tolitius/mount) - 一个美丽的惯用状态管理库.
- [plato](https://github.com/eneroth/plato) - 在ClojureScript中将原子状态持续保存到本地存储.
- [storage-atom](https://github.com/alandipert/storage-atom) - 由HTML5 Web存储支持的ClojureScript原子.
- [Waltz](https://github.com/ibdknox/waltz) -  ClojureScript库，可帮助使用非确定性有限状态机管理客户端应用程序中的状态.


### Testing
- [cljs.test](https://github.com/clojure/clojurescript/wiki/Testing) -  ClojureScript的集成测试框架（合并自 [clojurescript.test](https://github.com/cemerick/clojurescript.test)) 
- [Expectations](http://jayfields.com/expectations/) - 极简主义的单元测试框架.
- [Speclj](https://github.com/slagyr/speclj) -  Clojure和ClojureScript的TDD / BDD框架.
- [test.check](https://github.com/clojure/test.check) - 受QuickCheck启发的基于属性的生成测试工具.


### Validation
- [Bouncer](https://github.com/leonardoborges/bouncer) - 用于Clojure和Clojurescript应用程序的验证DSL.
- [Validateur](http://clojurevalidations.info/) - 受Ruby的ActiveModel启发的Clojure验证库.


### Web Framework & Template
- [atw-om](https://github.com/zaiste/atw-om) - 使用Clojure / Compojure，ClojureScript / Om和core.async的Web应用程序模板.
- [Chestnut](https://github.com/plexus/chestnut) - 带有实时重新加载的ClojureScript / Om的应用程序模板.
- [Clops](https://github.com/sveri/closp) - 一个固定的，完整的堆栈和易于使用的Web框架.
- [descjop](https://github.com/karad/lein_template_descjop) - 使用Electron的基于Web的桌面应用程序的模板.
- [electron-template](https://github.com/ducky427/electron-template) - 使用Electron，ClojureScript和Reagent创建基于Web的桌面应用程序的模板.
- [Fulcro](http://fulcrologic.github.io/fulcro) - 用于在clj / cljs中开发单页全栈Web应用程序的库.
- [Hoplon](http://hoplon.io) - 在Clojure和ClojureScript，客户端和服务器端编写所有内容.
- [Keechma](http://keechma.com) -  ClojureScript和Reagent的微前端框架.
- [Luminus](http://www.luminusweb.net/) - 旨在提供强大，可扩展且易于使用的平台.
- [Macchiato](https://github.com/macchiato-framework/macchiato-core) - 它旨在为Node.js提供一个易于使用的平台.
- [Mies](https://github.com/swannodette/mies) - 最小的ClojureScript项目模板.
- [Precept](https://github.com/CoNarrative/precept) - 声明性编程框架.
- [re-frame](https://github.com/Day8/re-frame) -  Clojurescript中用于编写SPA的试剂框架.
- [Tenzing](http://martinklepsch.github.io/tenzing/) - 没有使用Boot的后端的ClojureScript模板.
- [WebFUI](https://github.com/drcode/webfui) -  ClojureScript的客户端Web框架.


### WebSockets
- [Chord](https://github.com/jarohen/chord) - 旨在弥合CLJ / CLJS，web-socket和core.async三元组之间的差距.
- [Sente](https://github.com/ptaoussanis/sente) -  Clojure（脚本）+ core.async + WebSockets / Ajax.


* * *


## Contributing
 欢迎所有的贡献.  请阅读 [Contributing](https://github.com/hantuzun/awesome-clojurescript/blob/master/CONTRIBUTING.md) 在打开拉取请求之前.


## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

[Han Tuzun](http://hantuzun.com) 在法律允许的范围内，根据版权法，包括所有相关和相邻权利，放弃他在全球范围内工作的所有权利，将工作投入到公有领域.

您可以复制，修改，分发和执行工作，即使是出于商业目的，也可以不经许可.
