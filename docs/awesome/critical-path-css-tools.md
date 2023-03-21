<div class="github-widget" data-repo="addyosmani/critical-path-css-tools"></div>
关键路径（首屏）CSS 工具 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
==========================================

&gt; 帮助确定首屏 CSS 优先级的工具


为获得最佳性能，PageSpeed Insights [recommends](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent) 将页面的关键（首屏）CSS 直接内联到 HTML 中. 这消除了额外的往返，并允许浏览器更快地将上面的体验绘制到用户的屏幕上. 主要思想是：

* 确定页面的首屏样式并将它们写在`之间<style>` tags in the head.
* 在页脚中加载所有其他样式表，最好是异步加载.

以下是帮助生成、内联和报告关键路径 CSS 的工具列表.

## Node modules


* [Penthouse](https://github.com/pocketjoso/penthouse) - 由 Jonas Ohlsson 生成关键路径 CSS
* [Critical](https://github.com/addyosmani/critical) - 由 Addy Osmani 生成并内联关键路径 CSS（使用 Penthouse， [Oust](https://github.com/addyosmani/oust) 和内联样式）
* [CriticalCSS](https://github.com/filamentgroup/criticalcss) - 由 FilamentGroup 发现并输出关键 CSS


## Server-side modules

* [mod_pagespeed](https://github.com/pagespeed/mod_pagespeed) - 用于自动优化 PageSpeed 的 Apache 模块
* [ngx_pagespeed](https://github.com/pagespeed/ngx_pagespeed) - 用于自动优化 PageSpeed 的 Nginx 模块

## Grunt tasks

* [grunt-penthouse](https://github.com/fatso83/grunt-penthouse)
* [grunt-critical-css](https://github.com/filamentgroup/grunt-criticalcss)
* [grunt-critical](https://github.com/bezoerb/grunt-critical)

## CasperJS

* [critical-css-casperjs](https://github.com/ibrennan/critical-css-casperjs) - CasperJS 脚本从页面中提取关键的 CSS 信息

## PhantomJS

* [dr-css-inliner](https://github.com/drdk/dr-css-inliner) - 用于在页面上内联首屏 CSS 的 PhantomJS 脚本.

## Inline sources (styles, scripts)

* [inline-styles](https://github.com/maxogden/inline-styles)  - 由 Max Ogden 取代 `<link>  ` 内联标签 ` <style>` tags + inlines CSS url() calls with data URIs
* [inline-critical](https://github.com/bezoerb/inline-critical) - Ben Zörb，内联关键路径 CSS 并使用 `loadCSS` 加载现有样式表
* [isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader/) 对于 Webpack - 允许为 React 应用程序中的任何给定页面/屏幕提取关键 CSS，并在服务器端渲染 (SSR) 期间将其内联到 HTML 中. 看 [React Starter Kit](https://github.com/kriasoft/react-starter-kit) 举个例子.

## Async load CSS

内联关键路径 CSS 后，应使用异步加载来获取站点范围内的其余样式.

* [loadCSS](https://github.com/filamentgroup/loadCSS) - 使用 JS 异步加载 CSS. [Research](https://gist.github.com/scottjehl/87176715419617ae6994) 这导致了这一点也可用.
* [async & conditional loading](https://gist.github.com/matt-bailey/602b40c77a5d3381ff26) - 用于基于 body 标签类异步和有条件地加载 CSS 文件的 POC 脚本
* [asyncLoader](https://github.com/n0mad01/asyncLoader) - 异步脚本/样式表加载器
* [basket.js](http://addyosmani.github.io/basket.js/)  - 支持本地存储缓存的异步脚本/资源加载器. 可 [extended](https://github.com/andrewwakeling/basket-css-example) 加载样式表.

注意：Guardian 目前还将其全局样式缓存到 localStorage 中以供后续页面加载. 更多信息在此 [comment](https://gist.github.com/scottjehl/87176715419617ae6994).

## Online tools

* [Penthouse online](https://jonassebastianohlsson.com/criticalpathcssgenerator/)

## Bookmarklets/Extensions

* [Snippet](https://gist.github.com/PaulKinlan/6284142) 保罗·金兰. 帕特里克哈曼有一个 [exercise](http://patrickhamann.com/workshops/performance/tasks/2_Critical_Path/2_2.html) 使用您可以尝试的片段.
* [Snippet](https://gist.github.com/scottjehl/b6129da04733e4e0f9a4) 通过斯科特耶尔
* [CSSVacuum](https://github.com/ndreckshage/CSSVacuum) 来自 ndreckshage

## Render-blocking issues detection

* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)  - 测量移动设备和桌面设备页面性能的在线工具. 它两次获取 url，一次使用移动用户代理，一次使用桌面用户代理. 
* [PSI](https://github.com/addyosmani/psi)  - PageSpeed Insights 报告的节点模块作为构建过程的一部分. 直接使用 Gulp 或使用 [grunt-pagespeed](https://github.com/jrcryer/grunt-pagespeed) 如果是 Grunt 用户. 对于本地测试，使用此任务的文章和 [ngrok](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/) 可用.
* [PageSpeed Insights DevTools extension](https://chrome.google.com/webstore/detail/pagespeed-insights-by-goo/gplegfbjlmmehdoakndmohflojccocli?hl=en) - 用于从浏览器内部运行 PageSpeed 测试的 Chrome 扩展.
* [PageSpeed Insights Checker for mobile extension](https://chrome.google.com/webstore/detail/pagespeed-insights-checke/mkjmodmicmpjedhoekkmafdgpocdkbna?hl=en) - 检查每个页面的 Mobile PageSpeed 分数并为您提供方便的预览.

## Supplementary tools

* [UnCSS](https://github.com/giakki/uncss) 从页面中删除未使用的 CSS，允许您减少可能需要为站点加载的全局 CSS. 任务可用于 [Grunt](https://github.com/addyosmani/grunt-uncss), [Gulp](https://github.com/ben-eb/gulp-uncss) 和 [other](https://addyosmani.com/blog/removing-unused-css/) 构建工具.
