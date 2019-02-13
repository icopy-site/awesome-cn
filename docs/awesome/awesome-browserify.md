<div align="center"><img src="https://raw.githubusercontent.com/browserify/awesome-browserify/master/browserify.png" alt="Browserify!"></div>

## Awesome Browserify [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;：crystal_ball：精彩的精选列表 [Browserify](https://github.com/substack/node-browserify) 资源，库和工具.

请帮助改进此列表 [contributing](https://github.com/browserify/awesome-browserify/blob/master/contributing.md)!

## Contents

- [About](#about)
- [Official Resources](#official-resources)
- [Community Resources](#community-resources)
- [Tutorials](#tutorials)
- [Articles](#articles)
- [Demos](#demos)
- [Videos](#videos)
- [Tools](#tools)
  - [Development Servers](#development-servers)
  - [Plugins](#plugins)
  - [Watchers](#watchers)
  - [CSS Bundlers](#css-bundlers)
  - [Transforms](#transforms)
  - [Node in the Browser](#node-in-the-browser)
  - [Production Tools](#production-tools)

## About

Browserify通过捆绑所有依赖项，让您在浏览器中“需要（&#39;modules&#39;）`.

 您可以使用节点样式的`require（）`来组织浏览器代码并加载由npm安装的模块.  Browserify将递归地分析你的应用程序中的所有`require（）`调用，以便构建一个可以在一个浏览器中提供服务的软件包. <script>` tag.

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
- [Browserify guide](http://zhaoda.net/2015/10/16/browserify-guide/) （中文）

## Articles

- [Introduction to Browserify](https://writingjavascript.org/posts/introduction-to-browserify)
- [Using npm on the client side](http://dontkry.com/posts/code/using-npm-on-the-client-side.html)
- [How Browserify Works](http://benclinkinbeard.com/posts/how-browserify-works/)
- [Gulp + Browserify: The Everything Post](https://www.viget.com/articles/gulp-browserify-starter-faq)
- [Browserify vs Component](http://www.forbeslindesay.co.uk/post/44144487088/browserify-vs-component)
- [Browserify for Webpack users](https://gist.github.com/substack/68f8d502be42d5cd4942)
- [Browserify vs. Webpack](https://mattdesl.svbtle.com/browserify-vs-webpack)

## Demos

- [Canvas Splitter](http://requirebin.com/?gist=maxogden/9576799) 通过 [hughsk](http://github.com/hughsk)
- [Infinite 2D Cave Generator](http://requirebin.com/?gist=maxogden/9557700) 通过 [hughsk](http://github.com/hughsk)
- [2D Velocity Control](http://requirebin.com/?gist=maxogden/9557776) 通过 [sethvincent](http://github.com/sethvincent)

## Videos

- [James Halliday (substack) - LXJS 2013 - Modularidade para todos](https://www.youtube.com/watch?v=DCQNm6yiZh0)
- [Getting Started with Browserify](https://www.youtube.com/watch?v=CTAa8IcQh1U) 通过 [shama](https://github.com/shama/)
- [Transform your Bundles with Browserify](https://www.youtube.com/watch?v=Uk2bgp8OLT8) 通过 [shama](https://github.com/shama/)

## Tools

### Development Servers

- [budo](https://github.com/mattdesl/budo) - 用于快速原型设计的开发服务器.
- [beefy](https://github.com/chrisdickinson/beefy) - 本地开发服务器，旨在使浏览器快速和有趣.
- [wzrd](https://github.com/maxogden/wzrd) - 超级最小的browserify开发服务器.

### Plugins

- [browserify-hmr](https://github.com/AgentME/browserify-hmr) -  Browserify的热模块替换插件.

### Watchers

- [watchify](https://github.com/substack/watchify) - 浏览器构建的监视模式.
- [persistify](https://github.com/royriojas/persistify) - 围绕`browserify`的包装器进行增量构建.

### CSS bundlers

- [sheetify](https://github.com/stackcss/sheetify) - 用于browserify的模块化CSS捆绑器.
- [parcelify](https://github.com/rotundasoftware/parcelify) - 将css添加到browserify使用的npm模块中.
- [css-modulesify](https://github.com/css-modules/css-modulesify) -  Browserify插件加载CSS模块.

### Transforms

- [babelify](https://github.com/babel/babelify) -  Browserify变换为babel.
- [aliasify](https://github.com/benbria/aliasify) - 重新映射需要在构建时调用.
- [brfs](https://github.com/substack/brfs) - `fs.readFileSync（）`和`fs.readFile（）`静态资产browserify转换.

### Node in the Browser

- [crypto-browserify](https://github.com/crypto-browserify/crypto-browserify) - 节点的“加密”模块的端口到浏览器.
- [stream-browserify](https://github.com/substack/stream-browserify) - 来自节点核心的`stream`模块，用于浏览器！
- [buffer](https://github.com/feross/buffer) - 来自node.js的`buffer`模块，用于浏览器.
- [requirebin](http://requirebin.com/) - 使用NPM中的模块编写浏览器JavaScript程序.

### Production Tools

- [wzrd.in](https://wzrd.in/)   -  Browserify CDN.  Browserify作为一种增值服务！
- [bankai](https://github.com/yoshuawuyts/bankai)   -  DIY资产服务器.  将HTML，CSS和JS作为流提供.

## Contributing

 欢迎捐款！  请阅读 [contributing guidelines](https://github.com/browserify/awesome-browserify/blob/master/contributing.md) 在开始之前.

## License

The [browserify logo](https://raw.githubusercontent.com/browserify/awesome-browserify/master/browserify.png) 是 [substack](https://github.com/substack).

所有其他内容都将发布到公共领域 [CC0-1.0](https://spdx.org/licenses/CC0-1.0.html).

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
