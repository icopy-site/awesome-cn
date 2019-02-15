关键路径（首屏）CSS工具 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
==========================================

&gt;帮助优先处理CSS的工具

### Prioritize above-the-fold content first.

为了获得最佳性能，PageSpeed Insights [recommends](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)  将页面的关键（首要）CSS直接内嵌到HTML中.  这消除了额外的往返，并允许浏览器更快地将上述体验绘制到用户的屏幕上.  主要想法是：

*确定页面的上述样式并在`之间写入<style>` tags in the head.
*在页脚中加载所有其他样式表，理想情况是异步.

以下是帮助生成，内联和报告关键路径CSS的工具列表.

## Node modules


* [Penthouse](https://github.com/pocketjoso/penthouse) - 由Jonas Ohlsson生成关键路径CSS
* [Critical](https://github.com/addyosmani/critical) - 由Addy Osmani生成并内联关键路径CSS（使用Penthouse， [Oust](https://github.com/addyosmani/oust) 和内联样式）
* [CriticalCSS](https://github.com/filamentgroup/criticalcss) - 由FilamentGroup发现并输出关键的CSS


## Server-side modules

* [mod_pagespeed](https://github.com/pagespeed/mod_pagespeed) - 用于自动PageSpeed优化的Apache模块
* [ngx_pagespeed](https://github.com/pagespeed/ngx_pagespeed) - 用于自动PageSpeed优化的Nginx模块

## Grunt tasks

* [grunt-penthouse](https://github.com/fatso83/grunt-penthouse)
* [grunt-critical-css](https://github.com/filamentgroup/grunt-criticalcss)
* [grunt-critical](https://github.com/bezoerb/grunt-critical)

## CasperJS

* [critical-css-casperjs](https://github.com/ibrennan/critical-css-casperjs) -  CasperJS脚本，用于从页面中提取关键CSS信息

## PhantomJS

* [dr-css-inliner](https://github.com/drdk/dr-css-inliner) -  PhantomJS脚本在页面上内嵌CSS.

## Inline sources (styles, scripts)

* [inline-styles](https://github.com/maxogden/inline-styles)   - 由Max Ogden取代` <link>  `标签用内联` <style>` tags + inlines CSS url() calls with data URIs
* [gulp-inline-source](https://github.com/fmal/gulp-inline-source)   - 由Filip Malinowski取代` <link>  `标签用内联` <style>` tags, and replaces `<script src="https://raw.githubusercontent.com/addyosmani/critical-path-css-tools/master/">` tags with their inline content
* [inline-critical](https://github.com/bezoerb/inline-critical) - 作者BenZörb，内联关键路径CSS并使用`loadCSS`加载现有样式表
* [isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader/)  for Webpack  - 允许在React应用程序中为任何给定页面/屏幕提取关键CSS，并在服务器端呈现（SSR）期间将其内联到HTML中.  看到 [React Starter Kit](https://github.com/kriasoft/react-starter-kit) 举个例子.

## Async load CSS

在内联关键路径CSS后，应使用异步加载来获取其余的站点范围样式.

* [loadCSS](https://github.com/filamentgroup/loadCSS) - 使用JS异步加载CSS. [Research](https://gist.github.com/scottjehl/87176715419617ae6994) 导致这一点也可用.
* [async & conditional loading](https://gist.github.com/matt-bailey/602b40c77a5d3381ff26) -  POC脚本，用于根据正文标记类异步和有条件地加载CSS文件
* [asyncLoader](https://github.com/n0mad01/asyncLoader) - 异步脚本/样式表加载器
* [basket.js](http://addyosmani.github.io/basket.js/)   - 支持localStorage缓存的异步脚本/资源加载器.  可 [extended](https://github.com/andrewwakeling/basket-css-example) 加载样式表.

 注意：Guardian当前还将其全局样式缓存到localStorage中以用于后续页面加载.  更多信息 [comment](https://gist.github.com/scottjehl/87176715419617ae6994).

## Online tools

* [Penthouse online](https://jonassebastianohlsson.com/criticalpathcssgenerator/)

## Bookmarklets/Extensions

* [Snippet](https://gist.github.com/PaulKinlan/6284142)  保罗金兰  帕特里克哈曼有一个 [exercise](http://patrickhamann.com/workshops/performance/tasks/2_Critical_Path/2_2.html) 使用你可以尝试的代码片段.
* [Snippet](https://gist.github.com/scottjehl/b6129da04733e4e0f9a4) 作者：Scott Jehl
* [CSSVacuum](https://github.com/ndreckshage/CSSVacuum) 由ndreckshage

## Render-blocking issues detection

* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)   - 用于衡量移动设备和桌面设备页面性能的在线工具.  它两次获取URL，一次使用移动用户代理，一次使用桌面用户代理. 
* [PSI](https://github.com/addyosmani/psi)   - 作为构建过程的一部分，PageSpeed Insights报告的节点模块.  直接使用Gulp或使用 [grunt-pagespeed](https://github.com/jrcryer/grunt-pagespeed)  如果是Grunt用户  对于本地测试，使用此任务和 [ngrok](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/) 是可用的.
* [PageSpeed Insights DevTools extension](https://chrome.google.com/webstore/detail/pagespeed-insights-by-goo/gplegfbjlmmehdoakndmohflojccocli?hl=en) - 用于在浏览器内运行PageSpeed测试的Chrome扩展程序.
* [PageSpeed Insights Checker for mobile extension](https://chrome.google.com/webstore/detail/pagespeed-insights-checke/mkjmodmicmpjedhoekkmafdgpocdkbna?hl=en) - 检查每个页面的移动PageSpeed分数，并为您提供方便的预览.

## Supplementary tools

* [UnCSS](https://github.com/giakki/uncss)  从页面中删除未使用的CSS，允许您减少可能需要为您的站点加载的全局CSS.  任务可用 [Grunt](https://github.com/addyosmani/grunt-uncss), [Gulp](https://github.com/ben-eb/gulp-uncss) 和 [other](https://addyosmani.com/blog/removing-unused-css/) 构建工具.
