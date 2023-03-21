<div class="github-widget" data-repo="addyosmani/es6-tools"></div>

## Transpilers

* [Babel](https://github.com/babel/babel) - 将 ES6+ 代码转换为没有运行时的普通 ES5
* [Traceur compiler](https://github.com/google/traceur-compiler)  - ES6 特性 &gt; ES5. 包括类、生成器、承诺、解构模式、默认参数等.
* [es6ify](https://github.com/thlorenz/es6ify) - 跟踪器编译器包装为 [Browserify](http://browserify.org/) v2变换
* [babelify](https://github.com/babel/babelify) - Babel 转译器包装成 [Browserify](http://browserify.org/) 转换
* [es6-transpiler](https://github.com/termi/es6-transpiler)  - ES6 &gt; ES5. 包括类、解构、默认参数、传播
* 广场 [es6-module-transpiler](https://github.com/esnext/es6-module-transpiler) - ES6 模块到 AMD 或 CJS
* 脸书 [regenerator](https://github.com/facebook/regenerator) - 将 ES6 yield/generator 函数转换为 ES5
* 脸书 [jstransform](https://github.com/facebookarchive/jstransform)  - 用于可插入 JS 语法转换的简单实用程序. 附带一小组 ES6 -&gt; ES5 转换
* [defs](https://github.com/olov/defs) - ES6 块作用域 const 和 let 变量到 ES3 变量
* [es6_module_transpiler-rails](https://github.com/DavyJonesLocker/es6_module_transpiler-rails) - Rails 资产管道中的 ES6 模块
* [Some Sweet.js macros](https://github.com/jlongster/es6-macros) 从 ES6 编译到 ES5
* 比托维 [transpile](https://github.com/stealjs/transpile) - 将 ES6 转换为 AMD、CJS 和 StealJS.
* [regexpu](https://github.com/mathiasbynens/regexpu) — 将 Unicode-aware ES6 正则表达式转换为 ES5
* [Lebab](https://github.com/mohebifar/lebab) - ES5 代码到 ES6 的转换（近似值）

## Build-time transpilation

### Gulp Plugins
*巴别塔： [gulp-babel](https://github.com/babel/gulp-babel)
*绘图仪： [gulp-traceur](https://github.com/sindresorhus/gulp-traceur)
*再生器： [gulp-regenerator](https://github.com/sindresorhus/gulp-regenerator)
* ES6 模块转译器： [gulp-es6-module-transpiler](https://github.com/ryanseddon/gulp-es6-module-transpiler)
* es6 转译器： [gulp-es6-transpiler](https://github.com/sindresorhus/gulp-es6-transpiler) - ES6 → ES5
* es6-js转换： [gulp-jstransform](https://github.com/hemanth/gulp-jstransform) - ES6 → ES5 使用 FB [jstransform](https://github.com/facebook/jstransform)
*正则表达式： [gulp-regexpu](https://github.com/mathiasbynens/gulp-regexpu)
*打字稿： [gulp-typescript](https://github.com/ivogabe/gulp-typescript)

### Grunt Tasks
*巴别塔： [grunt-babel](https://github.com/babel/grunt-babel) - 将 ES6+ 代码转换为没有运行时的普通 ES5
*绘图仪： [grunt-traceur](https://github.com/aaronfrost/grunt-traceur) ES6 &gt; ES5 转译， [grunt-traceur-build](https://github.com/tarruda/grunt-traceur-build)
* ES6 模块转译器： [grunt-es6-module-transpiler](https://github.com/joefiorini/grunt-es6-module-transpiler)
*再生器： [grunt-regenerator](https://github.com/sindresorhus/grunt-regenerator) - ES6 生成器函数到 ES5
* [grunt-microlib](https://github.com/thomasboyt/grunt-microlib) - 使用 ES6 模块转译器的库工具（样本 [Gruntfile](https://github.com/jakearchibald/es6-promise/blob/c3336087fffc52e66cf5398e5b56b23a291080fc/Gruntfile.js))
* [grunt-defs](https://github.com/EE/grunt-defs) - ES6 块作用域 const 和 let 变量，到 ES3
* es6 转译器： [grunt-es6-transpiler](https://github.com/sindresorhus/grunt-es6-transpiler) - ES6 → ES5
*打字稿： [grunt-ts](https://github.com/TypeStrong/grunt-ts) - ES6+ &gt; ES5/ES3 转译

### Broccoli Plugins
*巴别塔： [broccoli-babel-transpiler](https://github.com/babel/broccoli-babel-transpiler)
*绘图仪： [broccoli-traceur](https://github.com/sindresorhus/broccoli-traceur)
*再生器： [broccoli-regenerator](https://github.com/sindresorhus/broccoli-regenerator)
* ES6 编译器： [broccoli-transpiler](https://github.com/sindresorhus/broccoli-es6-transpiler)
* ES6 模块转译器： [broccoli-es6-module-transpiler](https://github.com/mmun/broccoli-es6-module-transpiler)
* ES6 胖箭转译器： [broccoli-es6-arrow](https://github.com/hemanth/broccoli-es6-arrow.git)
*打字稿： [broccoli-tsc](https://github.com/ngParty/broccoli-tsc)

### Brunch Plugins
*巴别塔： [babel-brunch](https://github.com/babel/babel-brunch)
* ES6 模块转译器： [es6-module-transpiler-brunch](https://github.com/gcollazo/es6-module-transpiler-brunch)
*打字稿： [typescript-brunch](https://github.com/joshheyse/typescript-brunch)

## Webpack plugins
*巴别塔： [babel-loader](https://github.com/babel/babel-loader)
*绘图仪： [traceur-compiler-loader](https://github.com/gdi2290/traceur-compiler-loader)
*打字稿： [awesome-typescript-loader](https://github.com/s-panferov/awesome-typescript-loader)

## Duo plugins
*巴别塔： [duo-babel](https://github.com/babel/duo-babel)
*打字稿： [duo-typescript](https://github.com/frankwallis/duo-typescript)

## Connect plugins
*巴别塔： [babel-connect](https://github.com/babel/babel-connect)
*打字稿： [typescript-middleware](https://github.com/brn/typescript-middleware)

## Gobble plugins
*巴别塔： [gobble-babel](https://github.com/babel/gobble-babel)
*绘图仪： [gobble-es6-transpiler](https://github.com/gobblejs/gobble-es6-transpiler)

## Jade plugins
*巴别塔： [jade-babel](https://github.com/babel/jade-babel)
*绘图仪： [jade-traceur](https://www.npmjs.com/package/jade-traceur)

## Jest plugins
*巴别塔： [babel-jest](https://github.com/babel/babel-jest)

## Karma plugins
*巴别塔： [karma-babel-preprocessor](https://github.com/babel/karma-babel-preprocessor)
*绘图仪： [karma-traceur-preprocessor](https://github.com/karma-runner/karma-traceur-preprocessor)
*打字稿： [karma-typescript-preprocessor](https://github.com/sergeyt/karma-typescript-preprocessor)

## Sprockets plugins
*巴别塔： [sprockets-es6](https://github.com/josh/sprockets-es6)
*绘图仪： [sprockets-traceur](https://github.com/gunpowderlabs/sprockets-traceur)
*打字稿： [typescript-rails](https://github.com/typescript-ruby/typescript-rails)

## Browser plugins
* [Scratch JS](https://github.com/richgilbank/Scratch-JS) - 使用 Babel 或 Traceur 在页面上运行 ES6 的 Chrome/Opera DevTools 扩展
* [generator-typescript](https://github.com/mrkev/generator-typescript) - 用于 TypeScript 应用程序的 Yeoman 生成器

## Mocha plugins
* [Mocha Traceur](https://github.com/domenic/mocha-traceur) - Mocha 通过 Traceur 编译器传递 JS 文件的简单插件

## Module Loaders

* ES6 [Module Loader polyfill](https://github.com/ModuleLoader/es6-module-loader) （与最新规格和 Traceur 兼容）
* [js-loaders](https://github.com/jorendorff/js-loaders) - Mozilla 的规范兼容加载器原型
* [JSPM](http://jspm.io/) - ES6、AMD、CJS模块加载/包管理
* [Babel Module Loader](https://github.com/babel/babel-loader)
* [beck.js](https://github.com/unscriptable/beck) - 用于 ES6 模块加载器管道的工具包，用于遗留环境的垫片

## Boilerplates
* [es6-boilerplate](https://github.com/davidjnelson/es6-boilerplate) - 允许社区现在通过 traceur 结合 amd 和浏览器全局模块使用 es6 的工具，在真实浏览器中使用源映射、连接、缩小、压缩和单元测试.
* [es6-jspm-gulp-boilerplate](https://github.com/alexweber/es6-jspm-gulp-boilerplate) - 允许社区现在通过 babel 结合 jspm 使用 es6 的工具，在使用 es6 的真实浏览器中使用源映射、连接、缩小、压缩和单元测试.

## Code generation

* [generator-node-esnext](https://github.com/briandipalma/generator-node-esnext) - 用于绘图仪应用程序的 Yeoman 生成器
* [generator-es6-babel](https://github.com/HenriqueLimas/generator-es6-babel) - Babel 应用程序的 Yeoman 生成器
* [generator-gulp-babelify](https://github.com/HenriqueLimas/generator-gulp-babelify) - Yeoman 发电机 [Babel](https://babeljs.io/), [Browserify](http://browserify.org/) 和 [Gulp](http://gulpjs.com/)
* [grunt-init-es6](https://www.npmjs.com/package/grunt-init-es6) - 带有单元测试的脚手架节点模块，在 ES6 中编写
* [Loom generators with ES6 ember modules](https://github.com/ryanflorence/loom-generators-ember)
* 早午餐 [plugin](https://www.npmjs.com/package/es6-module-transpiler-brunch) 用于 ES6 模块转译

## Polyfills

* [core-js](https://github.com/zloirock/core-js) - ES6 的模块化和紧凑的 polyfill，包括 Symbols、Map、Set、Iterators、Promises、setImmediate、Array generics 等.使用的标准库 [Babel](https://github.com/babel/babel).
* [es6-shim](https://github.com/paulmillr/es6-shim) - 几乎所有新的 ES6 方法——来自 Map、Set、String、Array、Object、Object.is 等等.
* [WeakMap, Map, Set, HashMap - ES6 Collections](https://github.com/Benvie/harmony-collections)
* 聚合物 [WeakMap shim](https://github.com/Polymer/WeakMap)
* [`String.prototype.startsWith`](https://github.com/mathiasbynens/String.prototype.startsWith)
* [`String.prototype.endsWith`](https://github.com/mathiasbynens/String.prototype.endsWith)
* [`String.prototype.at`](https://github.com/mathiasbynens/String.prototype.at)
* [`String.prototype.repeat`](https://github.com/mathiasbynens/String.prototype.repeat)
* [`String.prototype.includes`](https://github.com/mathiasbynens/String.prototype.includes)
* [`String.prototype.codePointAt`](https://github.com/mathiasbynens/String.prototype.codePointAt)
* [`String.fromCodePoint`](https://github.com/mathiasbynens/String.fromCodePoint)
* [`Array.prototype.find`](https://github.com/paulmillr/Array.prototype.find)
* [`Array.prototype.findIndex`](https://github.com/paulmillr/Array.prototype.findIndex)
* [`Array.from`](https://github.com/mathiasbynens/Array.from)
* [`Array.of`](https://github.com/mathiasbynens/Array.of)
* [`Object.assign`](https://github.com/sindresorhus/object-assign)
* [`Number.isFinite`](https://github.com/sindresorhus/is-finite)
* [`Math.sign`](https://github.com/sindresorhus/math-sign)
* [`RegExp.prototype.match`](https://github.com/mathiasbynens/RegExp.prototype.match)
* [`RegExp.prototype.search`](https://github.com/mathiasbynens/RegExp.prototype.search)
* [es6-promise](https://github.com/jakearchibald/es6-promise) - 匹配 ES6 API 的 Promises 的 polyfill
* [ES6 Map Shim](https://github.com/eriwen/es6-map-shim) - 尽可能符合最新规范的破坏性垫片.
* [`Function.create`](https://github.com/walling/Function.create.js)
* [ES6 shim](https://github.com/inexorabletash/polyfill/blob/master/es6.md)
* [ES6 Symbol polyfill](https://github.com/medikoo/es6-symbol)
* [ES6 Map, Set, WeakMap](https://github.com/EliSnow/Blitz-Collections)
* [harmony-reflect](https://github.com/tvcutsem/harmony-reflect) - ES6 [reflection module](http://wiki.ecmascript.org/doku.php?id=harmony:reflect_api) （包含 [Proxy API](http://soft.vub.ac.be/~tvcutsem/proxies/))
* [ES5 based shims in pure CJS style](https://gist.github.com/medikoo/102b7d0e697627133788#list-of-ecmascript-6-shims) - Array、Object、Number、Math 和 String 函数/方法，以及 Map、Set、Symbol 和 WeakMap 对象

## Editors

* ES6 语法高亮 [Sublime Text and TextMate](https://github.com/Benvie/JavaScriptNext.tmLanguage)
* 中的 ES6 语法支持 [WebStorm](https://www.jetbrains.com/webstorm/) 和 [PhpStorm](https://www.jetbrains.com/phpstorm/), 编译为 ES5 与 [file watchers or task runners](http://blog.jetbrains.com/webstorm/2015/05/ecmascript-6-in-webstorm-transpiling/)
* 文档管理器 [plugin](https://github.com/pflannery/docpad-plugin-traceur) 对于绘图仪
*语法和转译 [package](https://github.com/gandm/language-babel)  为了 [Atom](https://atom.io/)
* 学习 Webstorm 中的 ES6 转译选项 [Read Blog Post](http://blog.jetbrains.com/webstorm/2015/05/ecmascript-6-in-webstorm-transpiling/)

## Parsers

* [Esprima](http://esprima.org) - 支持 ES6 的 JavaScript 解析器，解析为 [ESTree AST format](https://github.com/estree/estree)
* [Acorn](https://github.com/ternjs/acorn) - 一个小型、快速、基于 JavaScript 的 JavaScript 解析器，支持 ES6，解析为 [SpiderMonkey AST](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/Parser_API) 格式.
* [esparse](https://github.com/zenparsing/esparse) - 用 ES6 编写的 ES6 解析器.
* [Traceur compiler](https://github.com/google/traceur-compiler) 在 traceur.syntax.Parser 下也有内置的解析器.

## Other

* [ES.next showcase](https://github.com/sindresorhus/esnext-showcase) - ES6 特性的真实使用示例
* [looper](https://github.com/wycats/looper) - ES6 静态分析工具
* [es6-module-packager](https://www.npmjs.com/package/es6-module-packager)
* [es-dependency-graph](https://github.com/yahoo/es-dependency-graph) 和 [grunt-es-dependency-graph](https://github.com/yahoo/grunt-es-dependency-graph) - Generate a list of imports 和 exports from ES6 module files, useful for preloading, bundling, etc.
* [es6-import-validate](https://github.com/sproutsocial/es6-import-validate) 和 [grunt-es6-import-validate](https://github.com/sproutsocial/grunt-es6-import-validate) - 验证 ES6 模块中匹配的命名/默认导入语句.
* [let-er](https://github.com/getify/let-er) - 转译 [let-block block-scoping](http://wiki.ecmascript.org/doku.php?id=proposals:block_expressions#let_statement) （不被 ES6 接受）进入 ES3 或 ES6
* [Recast](https://github.com/benjamn/recast)  - 基于 Esprima 的 JavaScript 语法树转换器、保守的漂亮打印机和自动源映射生成器. 由上面列出的几个转译器使用，包括 [regenerator](https://github.com/facebook/regenerator) 和 [es6-arrow-function](https://github.com/esnext/es6-arrow-function).
* [Paws on ES6](https://github.com/hemanth/paws-on-es6) - ES6 功能的极简示例.
* [ES6 on node](http://h3manth.com/new/blog/2013/es6-on-nodejs/) - 如何在 node.js 中使用 ES6 特性.
* [es6-translate](https://github.com/calvinmetcalf/es6-translate) - 使用 ES6 加载器挂钩在 ES6 中加载（节点风格的）commonjs 包.
* [Isparta](https://github.com/douglasduteil/isparta)
* [babel-node](https://babeljs.io/docs/usage/cli/#babel-node) - 使用 Babel 运行带有 ES6 转译的节点 cli.
* [ES6 Lab setup](https://github.com/hemanth/es6-lab-setup) - 使用带有 `gulp` 和 `jasmine` 支持的 `Babel` 或 `traceur` 将 ES6 转换为 ES5 的简单设置.
* [TypeScript](http://www.typescriptlang.org/) - 具有严格类型的 ECMAScript 超集，旨在与 ES6 保持一致
* [Rollup](http://rollupjs.org/)  - Rollup 是下一代 JavaScript 模块打包器. 使用 ES2015 模块编写您的应用程序或库，然后将它们有效地捆绑到一个文件中以供在浏览器和 Node.js 中使用
