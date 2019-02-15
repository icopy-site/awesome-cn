## Awesome Draft.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[Draft.js](https://draftjs.org/) 是一个在React中构建富文本编辑器的框架.

**目录**

- [Community](https://github.com/nikgraf/awesome-draft-js#community)
- [Presentations](https://github.com/nikgraf/awesome-draft-js#presentations)
- [Projects on Top of Draft.js](https://github.com/nikgraf/awesome-draft-js#standalone-editors-built-on-draftjs)
- [Common Utilities](https://github.com/nikgraf/awesome-draft-js#common-utilities)
- [Blog Posts & Articles](https://github.com/nikgraf/awesome-draft-js#blog-posts--articles)
- [Live Demos](https://github.com/nikgraf/awesome-draft-js#live-demos)
- [Usage in Production](https://github.com/nikgraf/awesome-draft-js#usage-in-production)
- [License](https://github.com/nikgraf/awesome-draft-js#license)

## Community

* [Slack channel](https://draftjs.herokuapp.com/)

## Presentations
* [Rich Text Editing with React @ React.js Conf 2016 by Isaac Salier-Hellendag ](https://www.youtube.com/watch?v=feUYwoLhE_4)
* [Rich text editing with Draft.js & DraftJS Plugins by Nik Graf](https://www.youtube.com/watch?v=gxNuHZXZMgs)
* [React Ep. 37: Draftjs by What I Learned Today – Atomic Jolt](https://www.youtube.com/watch?v=0k9suXgCtTA)
* [008 - Draft.js Plugins @ React30](https://www.youtube.com/watch?v=w-PqnpMizcQ)
* [Draft.js at HubSpot by Ben Briggs](https://product.hubspot.com/blog/tech-talk-at-night-react-meetup)
* [Draft.js under the hood - React Melbourne meetup](https://www.youtube.com/watch?feature=player_embedded&v=vOZAO3jFSHI)

## Standalone Editors Built on Draft.js

* [Draft WYSIWYG](https://github.com/bkniffler/draft-wysiwyg) -  WYSIWYG编辑器，具有拖放功能，调整大小和工具提示.
* [Draft.js Editor](https://github.com/AlastairTaft/draft-js-editor/) - 受Medium＆Facebook Notes启发的富文本编辑器.
* [React-RTE](https://github.com/sstur/react-rte/) - 类似于CKEditor或TinyMCE的全功能textarea替代品.
* [Facebook Notes Clone(ish)](https://github.com/andrewcoelho/react-text-editor) - 富文本编辑器类似于Facebook笔记.
* [Megadraft](https://github.com/globocom/megadraft) - 富文本编辑器，具有良好的插件和可扩展性默认基础.
* [Medium Draft](https://github.com/brijeshb42/medium-draft) - 类似中型的富文本编辑器，侧重于键盘快捷键.
* [React-Draft-Wyiswyg](https://github.com/jpuri/react-draft-wysiwyg) -  WYISWYG编辑器，具有各种文本编辑选项和相应的HTML生成.
* [Dante 2](https://github.com/michelson/dante2) - 构建在DraftJs之上的另一个中等克隆.
* [Last Draft](https://github.com/vacenz/last-draft) - 使用Draft.js插件构建的草稿编辑器.
* [Z-Editor](https://github.com/Z-Editor/Z-Editor) - 在线Z-notations编辑器.
* [Draftail](https://github.com/springload/draftail/) - 基于Draft.js的可配置富文本编辑器，专为Wagtail构建.
* [Braft](https://github.com/margox/braft-editor) - 可扩展的JS JS编辑器

## Plugins and Decorators Built for Draft.js

* [Draft.js Plugins](https://github.com/draft-js-plugins/draft-js-plugins) -  Draft.js之上的插件架构
  - [Alignment](https://www.draft-js-plugins.com/plugin/alignment)
  - [Autolist](https://github.com/icelab/draft-js-autolist-plugin) - 自动无序/有序列表创建.
  - [Block Breakout](https://github.com/icelab/draft-js-block-breakout-plugin) - 键入时中断块类型.
  - [Buttons](https://github.com/vacenz/last-draft-js-plugins)
  - [Color Picker](https://github.com/vacenz/last-draft-js-plugins)
  - [Counter](https://www.draft-js-plugins.com/plugin/counter) - 字符，单词和行计数.
  - [Divider](https://github.com/simsim0709/draft-js-plugins/tree/master/draft-js-divider-plugin)
  - [Drag and Drop](https://www.draft-js-plugins.com/plugin/drag-n-drop)
  - [Embed](https://github.com/vacenz/last-draft-js-plugins)
  - [Emoji](https://www.draft-js-plugins.com/plugin/emoji) - 类似Slack的表情符号支持
  - [EmojiPicker](https://github.com/vacenz/last-draft-js-plugins)
  - [Focus](https://www.draft-js-plugins.com/plugin/focus)
  - [GifPicker](https://github.com/vacenz/last-draft-js-plugins)
  - [Hashtags](https://www.draft-js-plugins.com/plugin/hashtag) - 类似Twitter的标签支持
  - [Image](https://www.draft-js-plugins.com/plugin/image)
  - [Inline Toolbar](https://www.draft-js-plugins.com/plugin/inline-toolbar)
  - [Katex](https://github.com/letranloc/draft-js-katex-plugin) - 使用Katex插入和渲染LaTeX.
  - [Link](https://github.com/vacenz/last-draft-js-plugins)
  - [Linkify](https://www.draft-js-plugins.com/plugin/linkify) - 自动将链接转换为锚标记.
  - [Markdown Shortcuts](https://github.com/ngs/draft-js-markdown-shortcuts-plugin/) -  Markdown语法快捷方式.
  - [Mathjax](https://github.com/efloti/draft-js-mathjax-plugin) - 使用Mathjax渲染的（La）TeX编辑数学.
  - [Mention](https://www.draft-js-plugins.com/plugin/mention) - 类似Twitter的提及支持
  - [Modal](https://github.com/vacenz/last-draft-js-plugins)
  - [Prism](https://github.com/withspectrum/draft-js-prism-plugin) - 使用Prism语法突出显示代码块.
  - [Resizeable](https://www.draft-js-plugins.com/plugin/resizeable)
  - [RichButtons](https://github.com/jasonphillips/draft-js-richbuttons-plugin) - 添加和自定义丰富的格式按钮.
  - [Side Toolbar](https://www.draft-js-plugins.com/plugin/side-toolbar)
  - [Sidebar](https://github.com/vacenz/last-draft-js-plugins)
  - [Single Line](https://github.com/icelab/draft-js-single-line-plugin) - 限制为单行输入.
  - [Sticker](https://www.draft-js-plugins.com/plugin/sticker) - 类似Facebook的贴纸支持
  - [Toolbar](https://github.com/vacenz/last-draft-js-plugins)
  - [Undo](https://www.draft-js-plugins.com/plugin/undo) - 撤消和重做按钮.
  - [Video](https://www.draft-js-plugins.com/plugin/video)
* [Draft.js Gutter](https://github.com/seejamescode/draft-js-gutter) - 赞美行号排水沟.
* [Draft.js Basic HTML Editor](https://github.com/dburrows/draft-js-basic-html-editor) - 接受html作为其输入格式，并将html返回到onChange.
* [Draft.js Prism](https://github.com/SamyPesse/draft-js-prism)- 使用Prism突出显示代码块.
* [Draft.js Typeahead](https://github.com/dooly-ai/draft-js-typeahead) - 支持预先输入功能.
* [Draft Extend](https://github.com/HubSpot/draft-extend) - 使用可配置的插件和集成的序列化构建可扩展的Draft.js编辑器.
* [Draft.js Code](https://github.com/SamyPesse/draft-js-code) - 用于更好代码编辑的低级实用程序的集合
* [Draft.js Annotatable](https://github.com/cltk/annotations) -  Draft.js的开箱即用注释系统，支持用户创建的注释.
* [Draft.js Regex](https://github.com/YozhikM/draft-regex) - 一组灵活的帮助程序，如正则表达式，空行防止和粘贴HTML清除.

## Common Utilities

* [BackDraft.js](https://github.com/evanc/backdraft-js) - 将rawContentBlock转换为标记字符串的功能.
* [Draft.js Exporter](https://github.com/rkpasia/draft-js-exporter) - 从Draft.js导出和格式化内容.
* [Draft.js: Export ContentState to HTML](https://github.com/sstur/draft-js-utils/tree/master/packages/draft-js-export-html) - 将ContentState导出为HTML.
* [Draft.js: Export ContentState to PDFMake](https://github.com/datagenno/draft-js-export-pdfmake) - 将ContentState导出为PDFMake.
* [Redraft](https://github.com/lokiuz/redraft) - 使用提供的回调渲染Draft.js convertToRaw的结果，与React配合良好
* [Draft.js exporter (Ruby)](https://github.com/ignitionworks/draftjs_exporter) - 将Draft.js内容状态导出为HTML.
* [Draft.js exporter (Python)](https://github.com/springload/draftjs_exporter) - 将Draft.js原始ContentState转换为HTML的库
* [Draft.js AST Exporter](https://github.com/icelab/draft-js-ast-exporter) - 将内容导出为抽象语法树（AST）.
* [Draft.js AST Importer](https://github.com/icelab/draft-js-ast-importer)- 从伴侣draft-js-ast-exporter导入抽象语法树（AST）输出.
* [Draft.js Multidecorators](https://github.com/SamyPesse/draft-js-multidecorators) - 组合多个装饰器.
* [Draft.js SimpleDecorator](https://github.com/Soreine/draft-js-simpledecorator) - 轻松创建灵活的装饰.
* [DraftJS Utils](https://github.com/jpuri/draftjs-utils) -  DraftJS的一组实用功能.
* [DraftJs to HTML](https://github.com/jpuri/draftjs-to-html) - 用于为DraftJS编辑器内容生成HTML的库.
* [Draft Convert](https://github.com/HubSpot/draft-convert) - 使用HTML扩展序列化和反序列化Draft.js ContentState.
* [HTML to DraftJS](https://github.com/jpuri/html-to-draftjs) - 将纯HTML转换为DraftJS编辑器内容.
* [Draft.js Exporter (Go)](https://github.com/ejilay/draftjs) - 将Draft.js内容状态导出为HTML.
* [React Native Draft.js Render](https://github.com/globocom/react-native-draftjs-render) -  Draft.js模型的React Native渲染.
* [Draft.js filters](https://github.com/thibaudcolas/draftjs-filters) - 过滤Draft.js内容以仅保留您允许的格式.
* [Sticky](https://github.com/nadunindunil/sticky) - 简单的笔记和剪贴板管理桌面应用程序

## Blog Posts & Articles

* [Facebook open sources rich text editor framework Draft.js](https://code.facebook.com/posts/1684092755205505/facebook-open-sources-rich-text-editor-framework-draft-js/)
* [This Blog Post Was Written Using Draft.js](https://dev.to/ben/this-blog-post-was-written-using-draftjs)
* [How Draft.js Represents Rich Text Data](https://medium.com/@rajaraodv/how-draft-js-represents-rich-text-data-eeabb5f25cf2#.7gd8psdvi)
* [A Beginner’s Guide to Draft.js](https://medium.com/@adrianli/a-beginner-s-guide-to-draft-js-d1823f58d8cc#.uufeulpl5)
* [Implementing todo list in Draft.js](http://bitwiser.in/2016/08/31/implementing-todo-list-in-draft-js.html)
* [Draft.js Pieces](https://cannibalcoder.com/2016/12/02/draft-js-pieces/)
* [Learning Draft.js](https://reactrocket.com/series/learning-draft-js/) - 关于如何使用draft.js开发的系列博客文章
* [Why Wagtail’s new editor is built with Draft.js](https://wagtail.io/blog/why-wagtail-new-editor-is-built-with-draft-js/)
* [Rethinking rich text pipelines with Draft.js](https://wagtail.io/blog/rethinking-rich-text-pipelines-with-draft-js/)

## Live Demos

* [REACTing Codepen Comment Editor - Draft.js](https://codepen.io/rkpasia/full/jqbrpq)
* [Draft.js Examples - A Heroku app w/ several example Draft.js Editors from different projects](http://draftjs-examples.herokuapp.com/)
* [Draft-js Samples - An app with examples and code explanations](https://github.com/Mair/react-meetup-draftjs)
* [Draftail Playground](https://draftail-playground.herokuapp.com/) -  Wagtail的Draft.js依赖项作为独立演示.
* [Draft drag and drop demo for mobile browser](https://github.com/jan4984/draft-dnd-example)

## Playgrounds for Examples from Official Repository (v.0.10.0)
* [Rich Text Editor](https://codepen.io/Kiwka/pen/YNYvyG)
* [Color Editor](https://codepen.io/Kiwka/pen/oBpVve)
* [Convert from HTML Editor](https://codepen.io/Kiwka/pen/YNYgWa)
* [Entity Editor](https://codepen.io/Kiwka/pen/wgpOoZ)
* [Link Editor](https://codepen.io/Kiwka/pen/ZLvPeO)
* [Media Editor](https://codepen.io/Kiwka/pen/rjpRzj)
* [Plain Text Editor](https://codepen.io/Kiwka/pen/jyYJzb)
* [Decorators Editor - Tweet example](https://codepen.io/Kiwka/pen/KaZERV)

## Usage in Production
* [Small Teaser](https://www.smallteaser.com/login?targetUrl=%2Farticles%2Fwrite)
* [HKW Technosphere Magazine](https://technosphere-magazine.hkw.de/)
* [Douban Read](https://read.douban.com/editor_ng)
* [Dooly](https://www.dooly.ai)
* [Wagtail](https://wagtail.io/)
* [Patreon](https://www.patreon.com/)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Nikolaus Graf](https://github.com/nikgraf/) 已放弃对此作品的所有版权及相关或相邻权利.
