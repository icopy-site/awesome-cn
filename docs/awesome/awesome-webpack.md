<h3 align="center">
	<img width="355" src="https://raw.githubusercontent.com/webpack-contrib/awesome-webpack/master/media/awesome_webpack_branding.png" alt="awesome-webpack">
	<br>
</h3>

**[webpack](https://github.com/webpack/webpack)**是**模块捆绑器**.

webpack takes modules with dependencies and generates static assets representing those modules.
<br>
## Awesome Webpack [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/webpack-contrib/awesome-webpack.svg?branch=master)](https://travis-ci.org/webpack-contrib/awesome-webpack)

> A curated list of awesome Webpack resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome)  名单.  随意改善此列表 [contributing](https://github.com/webpack-contrib/awesome-webpack/blob/master/contributing.md)!
<!--lint disable list-item-indent-->

### Contents

- [Resources](#webpack-ecosystem)
  - [Documentation](#documentation)
  - [Community](#community)
  - [Twitter Follows](#twitter)
- [Libraries](#libraries)
  - [Loaders](#loaders)
    - [File Type](#file-type)
    - [Component & Template](#component--template)
    - [Styles](#styles)
    - [Language & Framework](#language--framework)
    - [Utility](#utility)
    - [Testing](#testing)
  - [Integrations](#integration-libraries)
  - [Plugins](#webpack-plugins)
  - [Tools](#webpack-tools)
- [Research & Training](#research--training)
  - [Articles](#articles)
  - [Videos](#videos)
  - [Courses](#courses)
  - [Books](#books)
  - [Webpack Examples](#webpack-examples)
  - [Community Examples](#community-examples)
    - [Angular](#angular)
    - [Framework Agnostic](#framework-agnostic)
    - [React](#react)
  - [Other](#other)

<!--lint disable list-item-indent-->

## Webpack Ecosystem

&nbsp; &nbsp; **Remember to** [Cast your vote for upcoming Webpack features!](https://webpack.js.org/vote/)

### Support Webpack

- [Webpack Open Collective](https://opencollective.com/webpack) - Help support the teams ongoing development efforts.

### Documentation

- [Webpack 1.x](http://webpack.github.io/docs/) - Webpack 1.x Documentation
- [Webpack 2.x](https://webpack.js.org//) -  Webpack 2.x文档

### Community

- [StackOverflow](http://stackoverflow.com/tags/webpack)
- [Medium](https://medium.com/tag/webpack)
- [Gitter Chat](https://gitter.im/webpack/webpack)

### Twitter

*人们对Webpack充满热情（没有特别的顺序）*

- [Sean T. Larkin - @TheLarkInn](https://twitter.com/TheLarkInn) TPM在 [Microsoft](https://twitter.com/MSEdgeDev) .  Developer Advocate和webpack核心团队成员.
- [Juho Vepsäläinen - @bebraw](https://twitter.com/bebraw) 从 [SurviveJS](https://twitter.com/survivejs) and webpack core team member.
- [Eric Clemmons - @ericclemmons](https://twitter.com/ericclemmons) 软件开发副总裁 [HigherEdHQ](https://twitter.com/HigherEdHQ) .  Webpack成员.
- [Patrick Stapleton - @gdi2290](https://twitter.com/gdi2290) 从 [AngularClass](https://angularclass.com), [AngularAir](https://angularair.com) 和 [Angular Universal](https://github.com/angular/universal) .  Webpack成员.
- [Kent C. Dodds - @kentcdodds](https://twitter.com/kentcdodds) 从 [PayPal Engineering](https://twitter.com/PayPalEng) 和 [JavaScript Air](https://twitter.com/JavaScriptAir) .  Webpack成员.
- [Johannes Ewald - @Jhnnns](https://twitter.com/Jhnnns): Webpack core team member.
- [Joshua Wiens - @d3viant0ne](https://twitter.com/d3viant0ne)：技术主管 [EasyMetrics](https://easymetrics.com) .  Webpack成员.
- [Jonathan Creamer - @jcreamer898](https://twitter.com/jcreamer898): Microsoft MVP and [Telerik](https://github.com/telerik) 开发者专家.
- [Kees Kluskens - @keeskluskens](https://twitter.com/keeskluskens)： - 软件工程师 [Code Yellow](https://codeyellow.nl)，Webpack核心团队成员.

[Back to top](#table-of-contents)


## Libraries

### Loaders

#### File Type

- [File Loader](https://github.com/webpack/file-loader): File loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [URL Loader](https://github.com/webpack/url-loader): URL loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [HTML Loader](https://github.com/webpack/html-loader) ：用于Webpack的HTML加载器模块.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [Raw Loader](https://github.com/webpack/raw-loader): Raw file loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Image Loader](https://github.com/thetalecrafter/img-loader): Image minimizing loader for webpack. -- *Maintainer*: `Andy VanWagoner` [![Github][githubicon]](https://github.com/thetalecrafter) [![Twitter][twittericon]](https://twitter.com/thetalecrafter)
- [Responsive Loader](https://github.com/herrstucki/responsive-loader) ：响应式图像的加载程序.   -  *维护者*：`Jeremy Stucki` [！[Github] [githubicon]]（https://github.com/herrstucki）
- [SVG Url Loader](https://github.com/bhovhannes/svg-url-loader): Loader which loads SVG file as utf-8 encoded Url. -- *Maintainer*: `Hovhannes Babayan` [![Github][githubicon]](https://github.com/bhovhannes)
- [json5 Loader](https://github.com/webpack/json5-loader) ：用于Webpack的json5加载程序模块.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [json Loader](https://github.com/webpack/json-loader) ：用于Webpack的json loader模块.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [mermaid Loader](https://github.com/popul/mermaid-loader): [mermaid](http://knsv.github.io/mermaid/) loader module (diagrams) for Webpack. -- *Maintainer*: `Paul Musso` [![Github][githubicon]](https://github.com/popul)
- [wasm loader](https://github.com/ballercat/wasm-loader): wasm binary loader module for Webpack. -- *Maintainer*: `Arthur Buldauskas` [![Github][githubicon]](https://github.com/wasm-loader)
- [Imagemin Loader/Plugin](https://github.com/itgalaxy/imagemin-webpack): Image minimizing loader + plugin for webpack. -- *Maintainer*: `itgalaxy inc.` [![Github][githubicon]](https://github.com/itgalaxy)
- [Bin Exec Loader](https://github.com/milewski/bin-exec-loader): Pipe any file through any binary. -- *Maintainer*: `Rafael Milewski` [![Github][githubicon]](https://github.com/milewski)
- [GraphQL Loader](https://github.com/stephen/graphql-loader): `.graphql` document loader. -- *Maintainer*: `Stephen Wan` [![Github][githubicon]](https://github.com/stephen)
- [C/C++ Loader](https://github.com/ClickSimply/cpp-wasm-loader): Load native C/C++ files with minimal bundle bloat. -- *Maintainer*: `Scott Lott` [![Github][githubicon]](https://github.com/ClickSimply)

#### Component & Template

- [Angular2 Template Loader](https://github.com/TheLarkInn/angular2-template-loader): Inlines html and style's in Angular2 components. -- *Maintainer*: `Sean Larkin` [![Github][githubicon]](https://github.com/TheLarkInn) [![Twitter][twittericon]](https://twitter.com/TheLarkInn)
- [Handlebars Loader](https://github.com/pcardune/handlebars-loader) ：Webpack的把手模板加载器.   -  *维护者*：`Paul Carduner` [！[Github] [githubicon]]（https://github.com/pcardune)[！[Twitter] [twittericon]]（https://twitter.com/pcardune）
- [Vue Loader](https://github.com/vuejs/vue-loader): Webpack loader for Vue.js components. -- *Maintainer*: `Vuejs Team` [![Github][githubicon]](https://github.com/vuejs) [![Twitter][twittericon]](https://twitter.com/vuejs)
- [SVG React Loader](https://github.com/jhamlet/svg-react-loader)   -  Webpack SVG to React Component Loader.   -  *维护者*：`Jerry Hamlet` [！[Github] [githubicon]]（https://github.com/jhamlet）[！[Twitter] [twittericon]]（https://twitter.com/jerryhamlet）
- [Underscore Loader](https://github.com/emaphp/underscore-template-loader)   - 下划线和Lodash模板加载器.   -  *维护者*：&#39;Emmanuel Antico` [！[Github] [githubicon]]（https://github.com/emaphp）[！[Twitter] [twittericon]]（https://twitter.com/emaphp）
- [ngTemplate Loader](https://github.com/WearyMonkey/ngtemplate-loader)   -  Angular1模板加载器.   -  *维护者*：`Toby Rahilly` [！[Github] [githubicon]]（https://github.com/WearyMonkey）
- [ngInlineStylesLoader](https://github.com/seveves/ng-inline-styles-loader) ：优化角度组件的内联css.   -  *维护者*：`Severin Friede` [！[Github] [githubicon]]（https://github.com/seveves）
- [Markup-inline Loader](https://github.com/asnowwolf/markup-inline-loader) 内联SVG到HTML  -  * Maintainer *：`Zhicheng Wang` [！[Github] [githubicon]]（https://github.com/asnowwolf）
- [Polymer Loader](https://github.com/webpack-contrib/polymer-webpack-loader) - Loader for Polymer elements. -- *Maintainers*: `Rob Dodson` [![Github][githubicon]](https://github.com/robdodson) - `Chad Killingsworth` [![Github][githubicon]](https://github.com/ChadKillingsworth) - `Bryan Coulter` [![Github][githubicon]](https://github.com/bryandcoulter)
- [Tag Loader](https://github.com/riot/tag-loader)   -  Riot标签文件的加载器.   -  *维护者*：&#39;防暴队&#39;[！[Github] [githubicon]]（https://github.com/riot）[！[Twitter] [twittericon]]（https://twitter.com/riotjs_）
- [Twig Loader](https://github.com/zimmo-be/twig-loader) - Twig template loader. -- *Maintainer*: `Zimmo.be Team` [![Github][githubicon]](https://github.com/zimmo-be)

#### Styles

- [Style Loader](https://github.com/webpack/style-loader): Style loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [PostCSS Loader](https://github.com/postcss/postcss-loader): PostCSS loader for Webpack. -- *Maintainer*: `PostCSS Team` [![Github][githubicon]](https://github.com/postcss) [![Twitter][twittericon]](https://twitter.com/PostCSS)
- [CSS Loader](https://github.com/webpack/css-loader) ：Webpack的CSS加载器模块.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [SASS Loader](https://github.com/jtangelder/sass-loader) ：Webpack的SASS加载程序.   -  *维护者*：`Jorik Tangelder` [！[Github] [githubicon]]（https://github.com/jtangelder）[！[Twitter] [twittericon]]（https://twitter.com/jorikdelaporik）
- [Less Loader](https://github.com/webpack/less-loader) ：较少的Webpack加载程序模块.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [Stylus Loader](https://github.com/shama/stylus-loader): A stylus loader for webpack. -- *Maintainer*: `Kyle Robinson Young` [![Github][githubicon]](https://github.com/shama) [![Twitter][twittericon]](https://twitter.com/shamakry)
- [Isomorphic Style Loader](https://github.com/kriasoft/isomorphic-style-loader) ：Webpack的同构CSS样式加载器.   -  * Maintainer *：`Kriasoft Team` [！[Github] [githubicon]]（https://github.com/kriasoft）[！[Twitter] [twittericon]]（https://twitter.com/kriasoft）
- [Mini css extract plugin](https://github.com/webpack-contrib/mini-css-extract-plugin): 
轻量级CSS提取插件 -  * Maintainer *：`Webpack Contrib` [！[Github] [githubicon]]（https://github.com/webpack-contrib）

#### Language & Framework

- [TS Loader](https://github.com/TypeStrong/ts-loader): TypeScript loader for webpack. -- *Maintainer*: `TypeStrong Team` [![Github][githubicon]](https://github.com/TypeStrong)
- [Awesome TypeScript Loader](https://github.com/s-panferov/awesome-typescript-loader) ：Webpack的令人敬畏的TS加载程序.   -  *维护者*：`Stanislav Panferov` [！[Github] [githubicon]]（https://github.com/s-panferov)[！[Twitter] [twittericon]]（https://twitter.com/巴贝尔）
- [Coffee Loader](https://github.com/webpack/coffee-loader) ：用于Webpack的咖啡加载器模块.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [Bootstrap Loader](https://github.com/shakacode/bootstrap-loader): Load Bootstrap styles in your Webpack bundle. -- *Maintainer*: `ShakaCode Team` [![Github][githubicon]](https://github.com/shakacode) [![Twitter][twittericon]](https://twitter.com/shakacode)
- [PostHTML Loader](https://github.com/posthtml/posthtml-loader): PostHTML loader for Webpack. -- *Maintainer*: `PostHTML Team` [![Github][githubicon]](https://github.com/posthtml) [![Twitter][twittericon]](https://twitter.com/PostHTML)
- [ELM Loader](https://github.com/rtfeldman/elm-webpack-loader): Webpack loader for the Elm programming language. -- *Maintainer*: `Richard Feldman` [![Github][githubicon]](https://github.com/rtfeldman) [![Twitter][twittericon]](https://twitter.com/rtfeldman)
- [Fengari Loader](https://github.com/fengari-lua/fengari-loader/): Run Lua code using [Fengari](https://fengari.io) .   -  *维护者*：`Daurnimator` [！[Github] [githubicon]]（https://github.com/daurnimator）[！[Twitter] [twittericon]]（https://twitter.com/daurnimator）

#### Utility

- [Babel Loader](https://github.com/babel/babel-loader): Webpack plugin for Babel. -- *Maintainer*: `Babel Team` [![Github][githubicon]](https://github.com/babel) [![Twitter][twittericon]](https://twitter.com/babel)
- [ESLint Loader](https://github.com/MoOx/eslint-loader) ：Webpack的ESLint加载程序.   -  *维护者*：`Maxime Thirouin` [！[Github] [githubicon]]（https://github.com/MoOx)[！[Twitter] [twittericon]]（https://twitter.com/MoOx）
- [JSHint Loader](https://github.com/webpack/jshint-loader) ：用于Webpack的JSHint加载程序模块.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [JSCS Loader](https://github.com/unindented/jscs-loader): Run your source through the JSCS style checker. -- *Maintainer*: `Daniel Perez Alvarez` [![Github][githubicon]](https://github.com/unindented)
- [Bundle Loader](https://github.com/webpack/bundle-loader) ：Webpack的捆绑加载器.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [Worker Loader](https://github.com/webpack/worker-loader) ：Webpack的Worker loader模块.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [Resolve URL Loader](https://github.com/bholloway/resolve-url-loader): Resolves relative paths in url() statements. -- *Maintainer*: `Ben Holloway` [![Github][githubicon]](https://github.com/bholloway)
- [Import Loader](https://github.com/webpack/imports-loader): Imports loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [SourceMap Loader](https://github.com/webpack/source-map-loader): Extract sourceMappingURL comments from modules. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Combine Loader](https://www.npmjs.com/package/webpack-combine-loaders) - Converts a loaders array into a single loader string.  -- *Maintainer*: `James Friend` [![Github][githubicon]](https://github.com/jsdf)
- [Icon Font Loader](https://github.com/vusion/icon-font-loader) - Converts svgs into font icons in CSS.  -- *Maintainer*: `Forrest R. Zhao` [![Github][githubicon]](https://github.com/rainfore)
- [Icons Loader](https://www.npmjs.com/package/icons-loader) - Generates an iconfont from SVG dependencies.  -- *Maintainer*: `Mike Vercoelen` [![Github][githubicon]](https://github.com/mikevercoelen)
- [Modernizr Loader](https://www.npmjs.com/package/modernizr-loader)   - 将您的modernizr构建与webpack捆绑在一起.   -  *维护者*：`Peerigon Devs` [！[Github] [githubicon]]（https://github.com/peerigon）
- [ngRouter Loader](https://github.com/shlomiassaf/ng-router-loader) - 使用角度路由器的AOT能力的NgModule延迟加载 -  *维护者*：`Shlomi Assaf` [！[Github] [githubicon]]（https://github.com/shlomiassaf）[！[Twitter] [twittericon]]（https ：//twitter.com/shlomiassaf）
- [Lingui Loader](https://github.com/lingui/js-lingui/tree/master/packages/loader) - 为jsLingui，i18n库动态编译消息目录 -  * Maintainer *：`TomášEhrlich`[！[Github] [githubicon]]（https://github.com/tricoder42)[！[Twitter] [twittericon] ]（https://twitter.com/tomas_ehrlich）
- [Shell Loader](https://github.com/localjo/shell-loader) -  Run an arbitrary shell script on source files. -- *Maintainer*: `Jo Sprague` [![Github][githubicon]](https://github.com/localjo)

#### Testing

- [Mocha Loader](https://github.com/webpack/mocha-loader) ：用于Webpack的Mocha加载器模块.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [Karma Webpack](https://github.com/webpack/karma-webpack): Use Karma with Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Istanbul Webpack plugin](https://github.com/DxCx/webpack-istanbul-plugin) ：使用伊斯坦布尔仪器整箱.   -  *维护者*：`Hagai Cohen` [！[Github] [githubicon]]（https://github.com/DxCx）

[Back to top](#table-of-contents)

### Integration Libraries

- [Dotenv Webpack](https://github.com/mrsteele/dotenv-webpack): Compiles environment variables into your bundle via dotenv. -- *Maintainer*: `Matthew Steele` [![Github][githubicon]](https://github.com/mrsteele) [![Twitter][twittericon]](https://twitter.com/Matt_R_Steele)
- [Terse Webpack](https://github.com/ericclemmons/terse-webpack)   - 使用预设在简洁的API中简化了Webpack.   -  *维护者*：`Eric Clemmons` [！[Github] [githubicon]]（https://github.com/ericclemmons）[！[Twitter] [twittericon]]（https://twitter.com/ericclemmons）
- [SystemJS Webpack](https://github.com/guybedford/systemjs-webpack-plugin) - Webpack bundling for SystemJS.  -- *Maintainer*: `Guy Bedford` [![Github][githubicon]](https://github.com/guybedford) [![Twitter][twittericon]](https://twitter.com/guybedford)
- [Gulp Webpack Stream](https://github.com/shama/webpack-stream) - Run webpack through a stream interface.  -- *Maintainer*: `Kyle Robinson Young` [![Github][githubicon]](https://github.com/shama) [![Twitter][twittericon]](https://twitter.com/shamakry)
- [Webpack Blocks](https://github.com/andywer/webpack-blocks) - Configure webpack using functional feature blocks.  -- *Maintainer*: `Andy Wermke` [![Github][githubicon]](https://github.com/andywer) [![Twitter][twittericon]](https://twitter.com/andywritescode)
- [Webpacker](https://github.com/rails/webpacker) - Offical webpack gem for integration into ruby on rails projects.  -- *Maintainer*: `Rails` [![Github][githubicon]](https://github.com/rails)
- [WebpackAspnetMiddleware](https://github.com/frankwallis/WebpackAspnetMiddleware) - Development middleware for ASP.NET 5.  -- *Maintainer*: `Frank Wallis` [![Github][githubicon]](https://github.com/frankwallis)
- [Consul Key/Value Webpack](https://github.com/marlonmleite/consul-env-webpack-plugin): Compiles environment variables into your bundle via [Consul KV-store](https://www.consul.io/api/kv.html) .   -  *维护者*：`Marlon Maxwel` [！[Github] [githubicon]]（https://github.com/marlonmleite）

[Back to top](#table-of-contents)

### Webpack Plugins

- [Extract Text Plugin](https://github.com/webpack/extract-text-webpack-plugin): Extract text from bundle into a file. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [DefinePlugin](https://webpack.js.org/plugins/define-plugin/): Create global constants which can be configured at compile time. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Compression Plugin](https://github.com/webpack/compression-webpack-plugin) ：准备资产以使用Content-Encoding提供服务.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [Offline Plugin](https://github.com/NekR/offline-plugin): Offline plugin (ServiceWorker, AppCache) for Webpack. -- *Maintainer*: `Arthur Stolyar` [![Github][githubicon]](https://github.com/NekR) [![Twitter][twittericon]](https://twitter.com/nekrtemplar)
- [Rewire Plugin](https://github.com/jhnns/rewire-webpack) ：Webpack包的依赖注入.   -  *维护者*：`Johannes Ewald` [！[Github] [githubicon]]（https://github.com/jhnns）[！[Twitter] [twittericon]]（https://twitter.com/Jhnnns）
- [HTML Webpack Plugin](https://github.com/ampedandwired/html-webpack-plugin) ：简化HTML文件的创建.   -  *维护者*：`Jan Nicklas` [！[Github] [githubicon]]（https://github.com/jantimon）[！[Twitter] [twittericon]]（https://twitter.com/jantimon）
- [Copy Webpack Plugin](https://github.com/kevlened/copy-webpack-plugin) ：复制webpack中的文件和目录.   -  *维护者*：`Len Boyette` [！[Github] [githubicon]]（https://github.com/kevlened）[！[Twitter] [twittericon]]（https://twitter.com/kevlened）
- [Split By Path](https://github.com/BohdanTkachenko/webpack-split-by-path): Split By Path Webpack Plugin. -- *Maintainer*: `Bohdan Tkachenko` [![Github][githubicon]](https://github.com/BohdanTkachenko) [![Twitter][twittericon]](https://twitter.com/bohdantkachenko)
- [SW Precache](https://github.com/goldhand/sw-precache-webpack-plugin)   - 生成服务工作者以预先缓存捆绑.   -  *维护者*：`Will Farley` [！[Github] [githubicon]]（https://github.com/goldhand）
- [CoreJS Plugin](https://github.com/gdi2290/core-js-webpack-plugin) - Core-JS as a webpack plugin. -- *Maintainer*: `PatrickJS` [![Github][githubicon]](https://github.com/gdi2290)
- [Bundle Analyzer](https://github.com/th0r/webpack-bundle-analyzer) - Utility that represents bundles as an interactive treemap. -- *Maintainer*: `Yuriy Grunin` [![Github][githubicon]](https://github.com/th0r)
- [Module Mapping](https://github.com/spartez/module-mapping-webpack-plugin) - Maps modules onto different files. -- *Maintainer*: `Spartez Team` [![Github][githubicon]](https://github.com/spartez) [![Twitter][twittericon]](https://twitter.com/thisisspartez)
- [Serverless Webpack](https://github.com/elastic-coders/serverless-webpack)   - 无服务器插件捆绑你的lambda.   -  * Maintainer *：`Elastic Coders` [！[Github] [githubicon]]（https://github.com/elastic-coders)[！[Twitter] [twittericon]]（https://twitter.com/ ElasticCoders）
- [Prerender SPA](https://github.com/chrisvfritz/prerender-spa-plugin)   - 为SPA提供与框架无关的静态站点生成.   -  *维护者*：`Chris Fritz` [！[Github] [githubicon]]（https://github.com/chrisvfritz）[！[Twitter] [twittericon]]（https://twitter.com/chrisvfritz）
- [Static Site Generator Plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) - Minimal, unopinionated static site generator. -- *Maintainer*: `Mark Dalgleish` [![Github][githubicon]](https://github.com/markdalgleish)
- [SVG Sprite Plugin](https://github.com/TodayTix/svg-sprite-webpack-plugin) - Plugin for SVG sprites and icons. -- *Maintainer*: `Jeremy Tice` ([`TodayTix`](https://github.com/TodayTix)）[！[Github] [githubicon]]（https://github.com/jetpacmonkey）[！[Twitter] [twittericon]]（https://twitter.com/jetpacmonkey）
- [Imagemin Webpack Plugin](https://github.com/Klathmon/imagemin-webpack-plugin) - Minify images with Imagemin. -- *Maintainer*: `Gregory Benner` [![Github][githubicon]](https://github.com/Klathmon) [![Twitter][twittericon]](https://twitter.com/Klathmon)
- [Prepack Webpack Plugin](https://github.com/gajus/prepack-webpack-plugin) - A webpack plugin for prepack. -- *Maintainer*: `Gajus Kuizinas` [![Github][githubicon]](https://github.com/gajus)
- [Modules CDN Webpack Plugin](https://github.com/mastilver/modules-cdn-webpack-plugin)   - 从CDN动态加载模块.   -  *维护者*：`Thomas Sileghem` [！[Github] [githubicon]]（https://github.com/mastilver）
- [Generate package.json Plugin](https://github.com/lostpebble/generate-package-json-webpack-plugin) - Limit dependencies in a deployment `package.json` to only those that are actually being used by your bundle. -- *Maintainer*: `Paul Myburgh` [![Github][githubicon]](https://github.com/lostpebble)
- [Progressive Web App Manifest](https://github.com/arthurbergmz/webpack-pwa-manifest)   -  PWA清单管理器和生成器.   -  *维护者*：`Arthur A. Bergamaschi` [！[Github] [githubicon]]（https://github.com/arthurbergmz）
- [Friendly errors](https://github.com/geowarin/friendly-errors-webpack-plugin) - Recognizes certain classes of webpack errors and cleans, aggregates and prioritizes them. -- *Maintainer*: `Geoffroy Warin` [![Github][githubicon]](https://github.com/geowarin)
- [FileManager Webpack Plugin](https://github.com/gregnb/filemanager-webpack-plugin) - Copy, move, delete files and directories before and after Webpack builds -- *Maintainer*: `Gregory Nowakowski` [![Github][githubicon]](https://github.com/gregnb)
- [Duplicate Package Checker Webpack Plugin](https://github.com/darrenscerri/duplicate-package-checker-webpack-plugin) - Warns you when multiple versions of the same package exist in your bundle -- *Maintainer*: `Darren Scerri` [![Github][githubicon]](https://github.com/darrenscerri)
- [PurgeCSS Webpack Plugin](https://github.com/FullHuman/purgecss-webpack-plugin) - 用purgecss删除未使用的css的插件 -  * Maintainer *：`Floriel Fedry` [！[Github] [githubicon]]（https://github.com/Ffloriel）
- [Circular Dependency Plugin](https://github.com/aackerman/circular-dependency-plugin) - 捆绑时检测具有循环依赖关系的模块 -  * Maintainer *：`Aaron Ackerman` [！[Github] [githubicon]]（https://github.com/aackerman）
- [Public Path Manipulation Plugin](https://github.com/agoldis/webpack-require-from) - control `publicPath` of dynamically loaded resources at runtime  -- *Maintainer*: `Andrew Goldis` [![Github][githubicon]](https://github.com/agoldis)
- [Build Notifier Plugin](https://github.com/roccoc/webpack-build-notifier)   - 显示构建错误和警告的操作系统级别通知.   -  *维护者*：`Rocco Cataldo` [！[Github] [githubicon]]（https://github.com/roccoc）
- [Chrome Extension Reloader](https://github.com/rubenspgcavalcante/webpack-chrome-extension-reloader) - 开发Chrome扩展时热重新加载 -  *维护者*：`Rubens PG Cavalcante` [！[Github] [githubicon]]（https://github.com/rubenspgcavalcante）[！[Twitter] [twittericon]]（https： //twitter.com/rubenspgc）

[Back to top](#table-of-contents)

### Webpack Tools

- [Webpack Dev Middleware](https://github.com/webpack/webpack-dev-middleware) ：用于争用实时捆绑包的中间件.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [Webpack Dev Server](https://github.com/webpack/webpack-dev-server) ：提供webpack应用程序.  更新浏览器.   -  * Maintainer *：`Webpack Team` [！[Github] [githubicon]]（https://github.com/webpack）
- [Webpack Merge](https://github.com/survivejs/webpack-merge)   - 为Webpack设计的合并.   -  *维护者*：`JuhoVepsäläinen`[！[Github] [githubicon]]（https://github.com/bebraw）[！[Twitter] [twittericon]]（https://twitter.com/bebraw）
- [NPM Install Webpack](https://github.com/ericclemmons/npm-install-webpack-plugin)   - 使用Webpack自动安装和保存deps.   -  *维护者*：`Eric Clemmons` [！[Github] [githubicon]]（https://github.com/ericclemmons）[！[Twitter] [twittericon]]（https://twitter.com/ericclemmons）
- [Webpack Validator](https://github.com/js-dxtools/webpack-validator)   - 使用Joi验证您的webpack配置.   -  *维护者*：`js-dxtools Team` [！[Github] [githubicon]]（https://github.com/js-dxtools）
- [Webpack Config Utils](https://github.com/kentcdodds/webpack-config-utils)   -  Util.  使您的webpack配置更容易阅读.   -  * Maintainer *：`Ken​​t C. Dodds` [！[Github] [githubicon]]（https://github.com/kentcdodds）[！[Twitter] [twittericon]]（https://twitter.com/ kentcdodds）
- [Angular2 Webpack Toolkit](https://github.com/AngularClass/webpack-toolkit) -  Angular 2的Webpack工具和帮助器. -  * Maintainer *：`AngularClass` [！[Github] [githubicon]]（https://github.com/AngularClass）[！[Twitter] [twittericon]]（https： //twitter.com/AngularClass）
- [Webpack Bundle Analyzer](https://github.com/th0r/webpack-bundle-analyzer)   - 将捆绑包表示为交互式树形图.   -  *维护者*：`Yuriy Grunin` [！[Github] [githubicon]]（https://github.com/th0r)[！[Twitter] [twittericon]]（https://twitter.com/grunin_ya）
- [HJS Webpack](https://github.com/HenrikJoreteg/hjs-webpack): Helpers/presets for setting up webpack with hotloading. -- *Maintainer*: `Henrik Joreteg` [![Github][githubicon]](https://github.com/HenrikJoreteg)
- [Webpack Dashboard](https://github.com/FormidableLabs/webpack-dashboard) ：webpack dev服务器的CLI仪表板.   -  * Maintainer *：`Formidable Labs` [！[Github] [githubicon]]（https://github.com/FormidableLabs）
- [Neutrino](https://github.com/mozilla-neutrino/neutrino-dev) ：结合Webpack的强大功能和预设的简单性.   -  *维护者*：`Eli Perelman` [！[Github] [githubicon]]（https://github.com/eliperelman）
- [Webpack Chain](https://github.com/mozilla-neutrino/webpack-chain): A chaining API to generate and simplify the mod. of Webpack 2 configurations. -- *Maintainer*: `Eli Perelman` [![Github][githubicon]](https://github.com/eliperelman)
- [Speed Measure Plugin](https://github.com/stephencookdev/speed-measure-webpack-plugin)   - 测量webpack插件和加载器的速度.   -  *维护者*：`Stephen Cook` [！[Github] [githubicon]]（https://github.com/stephencookdev）
- [packtracker.io](https://packtracker.io/?utm_source=github&utm_medium=awesome-webpack&utm_campaign=social) - Webpack bundle analysis on every commit, report webpack stats to every pull request.


[Back to top](#table-of-contents)

## Research & Training

### Articles

- Andrew Welch | 23-Oct-18 - [An Annotated webpack 4 Config for Frontend Web Development](https://nystudio107.com/blog/an-annotated-webpack-4-config-for-frontend-web-development)
  - GáborSoós|  17年4月24日 -  [How to do proper tree-shaking in Webpack 2](https://blog.craftlab.hu/how-to-do-proper-tree-shaking-in-webpack-2-e27852af8b21)
  -  Mark Erikson |  07年3月7日 -  [Declaratively Rendering Earth in 3D, Building a Cesium + React App with Webpack](http://blog.isquaredsoftware.com/2017/03/declarative-earth-part-1-cesium-webpack/)
  -  Joseph Zimmerman |  2月2日至17日 -  [A Detailed Introduction To Webpack.](https://www.smashingmagazine.com/2017/02/a-detailed-introduction-to-webpack/)
- Jamund Ferguson | 22-Jul-16 - [Manually Tuning Webpack Builds.](https://medium.com/@xjamundx/manually-tuning-webpack-builds-284923f47f44#.lbvkidezh)
- Sean T. Larkin | 21-Jul-16 - [Learn and Debug webpack with Chrome Dev Tools!.](https://medium.com/webpack/webpack-bits-learn-and-debug-webpack-with-chrome-dev-tools-da1c5b19554#.gpoentuxe)
  -  Raja Rao DV |  16年4月10日 -  [Webpack  —  The Confusing Parts.](https://medium.com/@rajaraodv/webpack-the-confusing-parts-58712f8fcad9#.qmfmplobc)
  - 安德鲁雷|  09年4月9日 -  [Webpack: When To Use and Why.](http://blog.andrewray.me/webpack-when-to-use-and-why/)
  -  Jonathan Creamer |  25年2月25日 -  [WebPack Code splitting with ES6 and Babel 6.](http://jonathancreamer.com/webpack-code-splitting-with-es6-and-babel-6/)
  -  Grgur Grisogono |  16年2月15日 -  [Webpack 2 Tree Shaking Configuration.](https://medium.com/modus-create-front-end-development/webpack-2-tree-shaking-configuration-9f1de90f3233#.5pddvz5lz)
  -  Ilya Zayats |  07年2月7日 -  [How to split your apps by routes with Webpack.](https://medium.com/@somebody32/how-to-split-your-apps-by-routes-with-webpack-36b7a8a6231#.iy99i4f7r)
  -  Sebastian De Deyne |  04年2月16日 -  [Adventure Time With Webpack.](https://sebastiandedeyne.com/posts/2016/adventure-time-with-webpack)
- Jonathan Creamer | 10-Jan-16 - [Advanced WebPack Part 2 - Code Splitting.](http://jonathancreamer.com/advanced-webpack-part-2-code-splitting)
  - 安迪Ccs |  02年1月2日 -  [Webpack and Docker for Development and Deployment.](https://medium.com/@andyccs/webpack-and-docker-for-development-and-deployment-ae0e73243db4#.2yutcm8s4)
- Jonathan Creamer | 08-Jun-16 - [Advanced WebPack Part 3 - Creating a custom notifier plugin.](http://jonathancreamer.com/advanced-webpack-part-3-creating-a-custom-notifier-plugin)
  - 纳德会|  07  -  15  -  [Beginner’s guide to Webpack.](https://medium.com/@dabit3/beginner-s-guide-to-webpack-b1f1a3638460#.xb01fcsoq)
  -  Jonathan Creamer |  02-9月15日 -  [Advanced WebPack Part 1 - The CommonsChunk Plugin.](http://jonathancreamer.com/advanced-webpack-part-1-the-commonschunk-plugin/)
  -  Maxime Fabre |  16-Oct-15  -  [Webpack your bags.](https://blog.madewithlove.be/post/webpack-your-bags/?utm_content=buffer480f4&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

### Videos

  -  Naomi A. Jacobs通过BuzzJS 2.0 2017 |  2月27日至2017年 -  [Webpack: It's Not Magic](https://www.youtube.com/watch?v=_QEM9kdV-b0)
- Jack Franklin at HalfStack2016 | 18-Nov-16 | [Seamless client side JavaScript w/ Webpack](https://opbeat.com/community/posts/seamless-client-side-javascript-with-webpack-by-jack-franklin)
- Emil Oberg via YouTube |  Nov-4-2016 - [Introduction to Webpack 2, what is it?](https://www.youtube.com/watch?v=C_ZtQClrVYw)
  -  Emil Oberg通过YouTube |  2016年11月4日 -  [Webpack 2 - A full tutorial](https://www.youtube.com/watch?v=eWmkBNBTbMM)
- Sean Larkin NEJS Conf | 30-Sep-16 | [Webpack: Core Concepts](https://www.youtube.com/watch?v=AZPYL30ozCY&feature=youtu.be)
  - 来自First Principles的前端中心Webpack |  18年8月22日 -  [Intro to Webpack](https://www.youtube.com/watch?v=WQue1AN93YU)
  -  AngularAir的肖恩·拉金|  03年8月3日 -  [ngAir 75 - Webpack 2 with Sean Larkin.](https://plus.google.com/events/c76mih8qcjj0ffocpdlcbegvejs)
  -  Eric Clemmons与Kent C. Dodds聊天  01年7月1日 -  [Webpack HMR.](https://www.youtube.com/watch?v=PthDwpgrhmQ)
  -  Mirko Nasato（第五部分系列）  07年6月7日 -  [Angular2 with Webpack Project Setup.](https://www.youtube.com/playlist?list=PLgGUMhSgtxJyIQ4vI3BzlCzZLHL79Ew6p)
- Jonathan Creamer at Nodevember | 05-Dec-15 - [Advanced WebPack.](https://www.youtube.com/watch?v=MzVFrIAwwS8)
- Kyle Robinson Young | 08-Jul-15 - [Getting Started with Webpack.](https://www.youtube.com/watch?v=TaWKUpahFZM)
  -  Tasveer Singh在TorontoJS Tech Talk |  09年4月9日 -  [Webpack.](https://www.youtube.com/watch?v=TaWKUpahFZM)
  -  Mountain West JS的Jeremy Lund  28-Mar-15  -  [Gift Wrap Your Code with Webpack.](https://www.youtube.com/watch?v=ANMN9M9LhNQ)

### Courses

- [Webpack for Everyone](https://laracasts.com/series/webpack-for-everyone) - 免费Laracasts系列 [Jeffrey Way](http://twitter.com/jeffrey_way)
- [Webpack 4 Fundamentals](https://frontendmasters.com/courses/webpack-fundamentals/) - 关于Webpack基础知识的简要介绍 [Sean Larkin](https://twitter.com/thelarkinn)
- [Web Performance with Webpack](https://frontendmasters.com/courses/performance-webpack/) - Solving common web performace problems using Webpack by [Sean Larkin](https://twitter.com/thelarkinn)
- [Intro to webpack (playlist)](https://egghead.io/playlists/intro-to-webpack-4ca2d994) - 几个视频的Egghead.io播放列表 [Kent C. Dodds](https://twitter.com/kentcdodds) （第一个是免费的）.
- [Angular and Webpack for modular applications](https://egghead.io/courses/angular-and-webpack-for-modular-applications) - Egghead.io course by [Kent C. Dodds](https://twitter.com/kentcdodds)
- [Using Webpack for Production JavaScript Applications](https://egghead.io/courses/using-webpack-for-production-javascript-applications) - Egghead.io course by [Kent C. Dodds](https://twitter.com/kentcdodds) （高级）
- [Webpack Fundamentals](https://www.pluralsight.com/courses/webpack-fundamentals) - [Joe Eames](https://twitter.com/josepheames) for Pluralsight (intermediate)
- [Webpack Academy](https://webpack.academy) - A comprehensive webpack learning resource.

### Books

- [SurviveJS - Webpack](http://survivejs.com/webpack/introduction) ：从webpack学徒到掌握的免费书籍指导.  涵盖开发，产品和高级主题.

### Webpack Examples

- [Webpack Examples](https://github.com/webpack/webpack/tree/master/examples)：常见Webpack功能的示例.

### Community Examples

#### Angular

- [Angular2 Webpack Starter](https://github.com/AngularClass/angular2-webpack-starter) -  Webpack驱动的Angular 2入门套件 [AngularClass](https://github.com/AngularClass).
- [Angular2 Webpack](https://github.com/preboot/angular2-webpack) - A complete, yet simple, starter for Angular 2 using Webpack from [Preboot](https://github.com/preboot).
- [Angular2 Webpack Visual Studio](https://github.com/damienbod/Angular2WebpackVisualStudio) - ASP.NET Core, Angular2 with Webpack and Visual Studio from [Damien Bod](https://github.com/damienbod).
- [Angular2 Starter](https://github.com/schempy/angular2-typescript-webpack) - 带有Typescript和Webpack的Angular2入门套件 [Brian Schemp](https://github.com/schempy).
- [Angular2 SPA](https://github.com/aspnet/JavaScriptServices/tree/dev/templates/Angular2Spa) - Angular 2 ASP.NET Core Spa from [Steve Sanderson](https://github.com/SteveSandersonMS).
- [Angular2 Seed](https://github.com/angular/angular2-seed/) - 一个简单的启动器，展示了Angular2的基本概念 [Pawel Kozlowski](https://github.com/pkozlowski-opensource).

#### Framework Agnostic

- [Annotated webpack 4 Config](https://github.com/nystudio107/annotated-webpack-4-config) - This is the companion github repo for the [An Annotated webpack 4 Config for Frontend Web Development](https://nystudio107.com/blog/an-annotated-webpack-4-config-for-frontend-web-development) article.
- [ES6 TodoMVC with Webpack](https://github.com/kentcdodds/es6-todomvc) - Repo used to teach webpack. (Check branches).  from [Kent C. Dodds](https://github.com/kentcdodds).

#### React

- [Create React App](https://github.com/facebookincubator/create-react-app) - 创建没有构建配置的React应用程序 [Dan Abramov](https://github.com/gaearon).
- [React Starter Kit](https://github.com/kriasoft/react-starter-kit) - Isomorphic web app boilerplate from [Kriasoft Team](https://github.com/kriasoft).
- [React Redux Universal](https://github.com/erikras/react-redux-universal-hot-example) - 用于通用webapp的起始样板 [Erik Rasmussen](https://github.com/erikras).
- [Frontend Boilerplate](https://github.com/tj/frontend-boilerplate) - A boilerplate of things that mostly shouldn't exist from [TJ Holowaychuk](https://github.com/tj).
- [ReactGo](https://github.com/reactGo/reactGo) - 来自的全栈通用Redux的一站式解决方案 [Ken Ding](https://github.com/choonkending).
- [React Native Calculator](https://github.com/benoitvallon/react-native-nw-react-calculator) - 使用相同代码的移动，桌面和网站应用程序 [Benoit Vallon](https://github.com/benoitvallon).
- [React Cordova Boilerplate](https://github.com/unimonkiez/react-cordova-boilerplate) - 与Cordova的React的TodoMVC示例 [Yuval Saraf](https://github.com/unimonkiez).
- [React Universally](https://github.com/ctrlplusb/react-universally) - A starter kit giving you the minimum for a production ready universal react application.
- [Budgeting Application](https://github.com/ModusCreateOrg/budgeting-sample-app-webpack2) - 针对dev和prod优化的全功能样板应用程序，包括PRPL [Modus Create](https://github.com/ModusCreateOrg).
- [Razzle Material-UI Styled Example](https://github.com/kireerik/razzle-material-ui-styled-example) - 使用带有压缩的Express的Styled Components [Erik Engi](https://github.com/kireerik).

### Other

- [Juho, Johannes, Tobias & Sean on JavaScript Air](http://jsair.io/webpack) - [JavaScript Air](https://javascriptair.com) podcast
- [Webpack interview questions](https://github.com/styopdev/webpack-interview-questions) - Interview questions with answers.
- [Visual config tool for webpack](https://webpack.jakoblind.no) - A visual tool for creating webpack configs in your browser

[Back to top](#table-of-contents)

[twittericon]: https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg
[githubicon]: https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg
