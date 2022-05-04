<div class="github-widget" data-repo="nikgraf/awesome-draft-js"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Draft.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[Draft.js](https://draftjs.org/) 是一个在 React 中构建富文本编辑器的框架.


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

* [Draft WYSIWYG](https://github.com/bkniffler/draft-wysiwyg) - 具有拖放、调整大小和工具提示的所见即所得编辑器.
* [Draft.js Editor](https://github.com/AlastairTaft/draft-js-editor/) - 受 Medium 和 Facebook Notes 启发的富文本编辑器.
* [React-RTE](https://github.com/sstur/react-rte/) - 类似于 CKEditor 或 TinyMCE 的全功能文本区域替换.
* [Facebook Notes Clone(ish)](https://github.com/andrewcoelho/react-text-editor) - 类似于 Facebook 笔记的富文本编辑器.
* [Megadraft](https://github.com/globocom/megadraft) - 富文本编辑器，具有很好的默认插件库和可扩展性.
* [Medium Draft](https://github.com/brijeshb42/medium-draft) - 类似媒体的富文本编辑器，专注于键盘快捷键.
* [React-Draft-Wyiswyg](https://github.com/jpuri/react-draft-wysiwyg) - 所见即所得的编辑器，具有各种文本编辑选项和相应的 HTML 生成.
* [Dante 2](https://github.com/michelson/dante2) - 只是另一个建立在 DraftJs 之上的 Medium 克隆.
* [Last Draft](https://github.com/vacenz/last-draft) - 使用 Draft.js 插件构建的草稿编辑器.
* [Z-Editor](https://github.com/Z-Editor/Z-Editor) - 在线 Z 符号编辑器.
* [Draftail](https://github.com/springload/draftail/) - 基于 Draft.js 的可配置富文本编辑器，专为 Wagtail 构建.
* [Braft](https://github.com/margox/braft-editor) - 可扩展的草稿 JS 编辑器

## Plugins and Decorators Built for Draft.js

* [Draft.js Plugins](https://github.com/draft-js-plugins/draft-js-plugins) - Draft.js 之上的插件架构
  - [Alignment](https://www.draft-js-plugins.com/plugin/alignment)
  - [Block Breakout](https://github.com/icelab/draft-js-block-breakout-plugin) - 键入时打破块类型.
  - [Buttons](https://github.com/vacenz/last-draft-js-plugins)
  - [Color Picker](https://github.com/vacenz/last-draft-js-plugins)
  - [Counter](https://www.draft-js-plugins.com/plugin/counter) - 字符、单词和行计数.
  - [Divider](https://github.com/simsim0709/draft-js-plugins/tree/master/draft-js-divider-plugin)
  - [Drag and Drop](https://www.draft-js-plugins.com/plugin/drag-n-drop)
  - [Embed](https://github.com/vacenz/last-draft-js-plugins)
  - [Emoji](https://www.draft-js-plugins.com/plugin/emoji) - 类似松弛的表情符号支持
  - [EmojiPicker](https://github.com/vacenz/last-draft-js-plugins)
  - [Focus](https://www.draft-js-plugins.com/plugin/focus)
  - [GifPicker](https://github.com/vacenz/last-draft-js-plugins)
  - [Hashtags](https://www.draft-js-plugins.com/plugin/hashtag) - 类似 Twitter 的标签支持
  - [Image](https://www.draft-js-plugins.com/plugin/image)
  - [Inline Toolbar](https://www.draft-js-plugins.com/plugin/inline-toolbar)
  - [Katex](https://github.com/letranloc/draft-js-katex-plugin) - 使用 Katex 插入和渲染 LaTeX.
  - [Link](https://github.com/vacenz/last-draft-js-plugins)
  - [Linkify](https://www.draft-js-plugins.com/plugin/linkify) - 自动将链接变成锚标签.
  - [List](https://github.com/samuelmeuli/draft-js-list-plugin) - 自动创建列表，嵌套列表
  - [Markdown Shortcuts](https://github.com/ngs/draft-js-markdown-shortcuts-plugin/) - Markdown 语法快捷方式.
  - [Mathjax](https://github.com/tarjei/draft-js-mathjax-plugin) - 使用 Mathjax 渲染的 (La)TeX 编辑数学.
  - [Mention](https://www.draft-js-plugins.com/plugin/mention) - 类似 Twitter 的提及支持
  - [Modal](https://github.com/vacenz/last-draft-js-plugins)
  - [Prism](https://github.com/withspectrum/draft-js-prism-plugin) - 使用 Prism 语法高亮代码块.
  - [Resizeable](https://www.draft-js-plugins.com/plugin/resizeable)
  - [RichButtons](https://github.com/jasonphillips/draft-js-richbuttons-plugin) - 添加和自定义丰富的格式按钮.
  - [Side Toolbar](https://www.draft-js-plugins.com/plugin/side-toolbar)
  - [Sidebar](https://github.com/vacenz/last-draft-js-plugins)
  - [Single Line](https://github.com/icelab/draft-js-single-line-plugin) - 限制为单行输入.
  - [Sticker](https://www.draft-js-plugins.com/plugin/sticker) - 类似 Facebook 的贴纸支持
  - [Toolbar](https://github.com/vacenz/last-draft-js-plugins)
  - [Undo](https://www.draft-js-plugins.com/plugin/undo) --撤消和重做按钮.
  - [Video](https://www.draft-js-plugins.com/plugin/video)
* [Draft.js Gutter](https://github.com/seejamescode/draft-js-gutter) - 赞美行号排水沟.
* [Draft.js Basic HTML Editor](https://github.com/dburrows/draft-js-basic-html-editor) - 接受 html 作为其输入格式，并将 html 返回到 onChange.
* [Draft.js Prism](https://github.com/SamyPesse/draft-js-prism)- 使用 Prism 突出显示代码块.
* [Draft.js Typeahead](https://github.com/dooly-ai/draft-js-typeahead) - 支持预输入功能.
* [Draft Extend](https://github.com/HubSpot/draft-extend) - 使用可配置的插件和集成的序列化构建可扩展的 Draft.js 编辑器.
* [Draft.js Code](https://github.com/SamyPesse/draft-js-code) - 一组用于更好地编辑代码的低级实用程序
* [Draft.js Annotatable](https://github.com/cltk/annotations) - Draft.js 的开箱即用注释系统，支持用户创建的注释.
* [Draft.js Regex](https://github.com/YozhikM/draft-regex) - 一组灵活的助手，如正则表达式、防止空行和粘贴 HTML 清除.

## Common Utilities

* [Redraft](https://github.com/lokiuz/redraft) - 使用提供的回调呈现 Draft.js convertToRaw 的结果，适用于 React
* [Draft.js AST Importer](https://github.com/icelab/draft-js-ast-importer)- 从配套的 draft-js-ast-exporter 导入抽象语法树 (AST) 输出.
* [Draft.js Multidecorators](https://github.com/SamyPesse/draft-js-multidecorators) - 组合多个装饰器.
* [Draft.js SimpleDecorator](https://github.com/Soreine/draft-js-simpledecorator) - 轻松创建灵活的装饰器.
* [DraftJS Utils](https://github.com/jpuri/draftjs-utils) - DraftJS 的实用功能集.
* [React Native Draft.js Render](https://github.com/globocom/react-native-draftjs-render) - Draft.js 模型的 React Native 渲染.
* [Sticky](https://github.com/nadunindunil/sticky) - 一个简单的笔记和剪贴板管理桌面应用程序

## Blog Posts & Articles

* [Facebook open sources rich text editor framework Draft.js](https://code.facebook.com/posts/1684092755205505/facebook-open-sources-rich-text-editor-framework-draft-js/)
* [This Blog Post Was Written Using Draft.js](https://dev.to/ben/this-blog-post-was-written-using-draftjs)
* [How Draft.js Represents Rich Text Data](https://medium.com/@rajaraodv/how-draft-js-represents-rich-text-data-eeabb5f25cf2#.7gd8psdvi)
* [A Beginner’s Guide to Draft.js](https://medium.com/@adrianli/a-beginner-s-guide-to-draft-js-d1823f58d8cc#.uufeulpl5)
* [Implementing todo list in Draft.js](http://bitwiser.in/2016/08/31/implementing-todo-list-in-draft-js.html)
* [Draft.js Pieces](https://cannibalcoder.com/2016/12/02/draft-js-pieces/)
* [Learning Draft.js](https://reactrocket.com/series/learning-draft-js/) - 关于如何使用 Draft.js 进行开发的系列博文
* [Why Wagtail’s new editor is built with Draft.js](https://wagtail.io/blog/why-wagtail-new-editor-is-built-with-draft-js/)
* [Rethinking rich text pipelines with Draft.js](https://wagtail.io/blog/rethinking-rich-text-pipelines-with-draft-js/)

## Live Demos
* [Draft-js Samples - An app with examples and code explanations](https://github.com/Mair/react-meetup-draftjs)
* [Draftail Playground](https://draftail-playground.herokuapp.com/) – Wagtail 的 Draft.js 依赖项作为独立演示.
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
* [StoryChief](https://www.storychief.io/)
* [HKW Technosphere Magazine](https://technosphere-magazine.hkw.de/)
* [Douban Read](https://read.douban.com/editor_ng)
* [Dooly](https://www.dooly.ai)
* [Wagtail](https://wagtail.io/)
* [Patreon](https://www.patreon.com/)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Nikolaus Graf](https://github.com/nikgraf/) 已放弃本作品的所有版权和相关或邻近权利.
