<div class="github-widget" data-repo="browserify/awesome-browserify"></div>
<div align="center"><img src="https://raw.githubusercontent.com/browserify/awesome-browserify/master/browserify.png" alt="Browserify!"></div>

## Awesome Browserify [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; :crystal_ball: 精选列表 [Browserify](https://github.com/substack/node-browserify) 资源、库和工具.

请通过以下方式帮助改进此列表 [contributing](https://github.com/browserify/awesome-browserify/blob/master/contributing.md)!



## About

Browserify 通过捆绑所有依赖项，让您在浏览器中“require(&#39;modules&#39;)”.

您可以使用节点样式的“require()”来组织您的浏览器代码并加载由 npm 安装的模块.  Browserify 将递归地分析您应用程序中的所有 `require()` 调用，以便构建一个包，您可以在单个 ` 中为浏览器提供服务<script>` tag.

## Official Resources

- [Docs](https://github.com/substack/node-browserify#usage)
- [Handbook](https://github.com/substack/browserify-handbook)
- [Repo](https://github.com/substack/node-browserify)
- [Website](http://browserify.org/)

## Community Resources

- [IRC](http://webchat.freenode.net/?channels=browserify)
- [Twitter](http://twitter.com/browserify)
- [StackOverflow](http://stackoverflow.com/questions/tagged/browserify)

## Tutorials

- [Hello World with Browserify](http://browserify.org/#middle-section)
- [Browserify Adventure](https://github.com/workshopper/browserify-adventure)
- [A Gentle Browserify Walkthrough](https://ponyfoo.com/articles/a-gentle-browserify-walkthrough)
- [Browserify guide](http://zhaoda.net/2015/10/16/browserify-guide/) （中国人）

## Articles

- [Introduction to Browserify](https://writingjavascript.org/posts/introduction-to-browserify)
- [Using npm on the client side](http://dontkry.com/posts/code/using-npm-on-the-client-side.html)
- [How Browserify Works](http://benclinkinbeard.com/posts/how-browserify-works/)
- [Gulp + Browserify: The Everything Post](https://www.viget.com/articles/gulp-browserify-starter-faq)
- [Browserify vs Component](http://www.forbeslindesay.co.uk/post/44144487088/browserify-vs-component)
- [Browserify for Webpack users](https://gist.github.com/substack/68f8d502be42d5cd4942)
- [Browserify vs. Webpack](https://mattdesl.svbtle.com/browserify-vs-webpack)

## Demos

- [Canvas Splitter](http://requirebin.com/?gist=maxogden/9576799) 经过 [hughsk](http://github.com/hughsk)
- [Infinite 2D Cave Generator](http://requirebin.com/?gist=maxogden/9557700) 经过 [hughsk](http://github.com/hughsk)
- [2D Velocity Control](http://requirebin.com/?gist=maxogden/9557776) 经过 [sethvincent](http://github.com/sethvincent)

## Videos

- [James Halliday (substack) - LXJS 2013 - Modularidade para todos](https://www.youtube.com/watch?v=DCQNm6yiZh0)
- [Getting Started with Browserify](https://www.youtube.com/watch?v=CTAa8IcQh1U) 经过 [shama](https://github.com/shama/)
- [Transform your Bundles with Browserify](https://www.youtube.com/watch?v=Uk2bgp8OLT8) 经过 [shama](https://github.com/shama/)

## Tools

### Development Servers

- [budo](https://github.com/mattdesl/budo) - 用于快速原型制作的开发服务器.
- [beefy](https://github.com/chrisdickinson/beefy) - 旨在使使用 browserify 快速有趣的本地开发服务器.
- [wzrd](https://github.com/maxogden/wzrd) - 超级最小的 browserify 开发服务器.

### Plugins

- [browserify-hmr](https://github.com/AgentME/browserify-hmr) - Browserify 的热模块替换插件.

### Watchers

- [watchify](https://github.com/substack/watchify) - browserify 构建的观察模式.
- [persistify](https://github.com/royriojas/persistify) - 围绕“browserify”进行包装以进行增量构建.

### CSS bundlers

- [sheetify](https://github.com/stackcss/sheetify) - 用于 browserify 的模块化 CSS 捆绑器.
- [parcelify](https://github.com/rotundasoftware/parcelify) - 将 css 添加到使用 browserify 使用的 npm 模块.
- [css-modulesify](https://github.com/css-modules/css-modulesify) - Browserify 插件加载 CSS 模块.

### Transforms

- [babelify](https://github.com/babel/babelify) - 巴别塔的 Browserify 转换.
- [aliasify](https://github.com/benbria/aliasify) - 重新映射需要在构建时调用.
- [brfs](https://github.com/substack/brfs) - `fs.readFileSync()` 和 `fs.readFile()` 静态资产浏览器转换.

### Node in the Browser

- [crypto-browserify](https://github.com/crypto-browserify/crypto-browserify) - 节点的“crypto”模块到浏览器的端口.
- [stream-browserify](https://github.com/substack/stream-browserify) - 来自 node core 的 `stream` 模块，适用于浏览器！
- [buffer](https://github.com/feross/buffer) - 来自 node.js 的 `buffer` 模块，用于浏览器.
- [requirebin](http://requirebin.com/) - 使用来自 NPM 的模块编写浏览器 JavaScript 程序.

### Production Tools

- [wzrd.in](https://wzrd.in/)  - 浏览 CDN.  Browserify 即服务！
- [bankai](https://github.com/yoshuawuyts/bankai)  - DIY 资产服务器. 将 HTML、CSS 和 JS 作为流提供.

## Contributing

欢迎投稿！ 请阅读 [contributing guidelines](https://github.com/browserify/awesome-browserify/blob/master/contributing.md) 在开始之前.

## License

The [browserify logo](https://raw.githubusercontent.com/browserify/awesome-browserify/master/browserify.png) 由 [substack](https://github.com/substack).

所有其他内容都发布到公共领域 [CC0-1.0](https://spdx.org/licenses/CC0-1.0.html).

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
