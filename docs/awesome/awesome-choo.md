## Awesome choo [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <div align="right">:steam_locomotive::train::train::train::train::train:</div>

> [choo](https://choo.io/) 是一个用于创建的“4kb”框架
&gt;坚固的前端应用程序

## Contents

- [Official resources](#official-resources)
- [Dependencies](#dependencies)
- [Demos](#demos)
- [Community](#community)
- [Plugins and addons](#plugins-and-addons)
- [Elements](#elements)
- [CLI Templates](#cli-templates)
- [Resources](#resources)
- [Projects using choo](#projects-using-choo)

### Official resources

- [Docs](https://github.com/yoshuawuyts/choo/blob/master/README.md)
- [Handbook](https://github.com/yoshuawuyts/choo-handbook)
- [Repo](https://github.com/yoshuawuyts/choo)
- [Website](https://choo.io/)
- [Twitter thread](https://twitter.com/yoshuawuyts/status/730087077803528193)

### Dependencies
 `choo`是一个模块化框架.  这些是它粘合在一起的依赖关系
引擎盖下：

- [bel](https://github.com/shama/bel) - 使用创建可组合DOM元素
  模板字符串.
- [hyperx](https://github.com/substack/hyperx) - 将模板字符串转换为
  图书馆后端.
- [nanomorph](https://github.com/choojs/nanomorph) - 用于真实DOM节点的超快速扩散算法.
- [nanoraf](https://github.com/yoshuawuyts/nanoraf) - 只在需要时调用RAF.
- [nanorouter](https://github.com/choojs/nanorouter) -  Smol前端路由器.
- [nanobus](https://github.com/choojs/nanobus) - 微小的消息总线.
- [nanolocation](https://github.com/choojs/nanolocation) - 小window.location库.
- [nanohref](https://github.com/choojs/nanohref) - 微小的href点击处理程序库.
- [nanoquery](https://github.com/choojs/nanoquery) - 微小的查询串模块.
- [nanotiming](https://github.com/choojs/nanotiming) - 小型计时库.

### Demos

- [Input example](http://requirebin.com/?gist=e589473373b3100a6ace29f7bbee3186) - ([repo](https://github.com/yoshuawuyts/choo/tree/master/examples/title))
- [HTTP effects](https://hyperdev.com/#!/project/fork-fang)
- [Mailbox routing](https://github.com/yoshuawuyts/choo/tree/master/examples/mailbox)
- [TodoMVC](http://shuheikagawa.com/todomvc-choo) - ([repo](https://github.com/shuhei/todomvc-choo))
- [choo-firebase](https://choo-firebase-2ec21.firebaseapp.com) - ([repo](https://github.com/mw222rs/choo-firebase))
- [Grow](https://grow.static.land) - ([repo](https://github.com/sethvincent/grow))
- [Chatbot](http://chootbot.herokuapp.com) - ([repo](https://github.com/plaey/chatbot))
- [chat-random](https://github.com/akiva/chat-random)
- [choo-leaflet-demo](https://github.com/timwis/choo-leaflet-demo)
- [choo-scriber](https://zhouhansen.github.io/choo-scriber) - ([repo](https://github.com/ZhouHansen/choo-scriber))

### Community

- [Freenode](https://webchat.freenode.net/?channels=choo)

### Plugins and addons

- [choo-location-electron](https://github.com/bcomnes/choo-location-electron) - 用电子修复`choo`的路由器.
- [choo-log](https://github.com/yoshuawuyts/choo-log) -  choo的开发记录器.
- [choo-test](https://github.com/mantoni/choo-test) - 轻松选择应用程序单元测试.
- [choo-persist](https://github.com/yoshuawuyts/choo-persist/) - 使用LocalStorage同步choo状态.
- [choo-promise](https://github.com/rahatarmanahmed/choo-promise) - 在效果和订阅中使用promises.
- [choo-pull](https://github.com/yoshuawuyts/choo-pull) - 包装处理程序在choo插件中使用pull-stream.
- [choo-redirect](https://github.com/yoshuawuyts/choo-redirect) - 将视图重定向到另一个视图.
- [choo-model](https://github.com/yoshuawuyts/choo-model) -  choo的实验状态管理库.
- [choo-resume](https://github.com/bengourley/choo-resume) -  choo-resume + hot-rld =热门应用重新加载.
- [choo-detached](https://github.com/graforlock/choo-detached) - 使用`choo`作为可安装的简单独立组件（无路由）.
- [choo-service-worker](https://github.com/choojs/choo-service-worker) - `choo`的服务工作者装​​载机.
- [choo-websocket](https://github.com/YerkoPalma/choo-websocket) - 围绕WebSocket浏览器API的小型包装器，用于`choo`应用程序.
- [choo-store](https://github.com/ungoldman/choo-store) -  choo应用程序的轻量级状态结构.

### Elements

- [dom-notifications](https://github.com/finnp/dom-notifications) - 受原子启发的通知组件.
- [choodown](https://github.com/trainyard/choodown) - 用于选择的简单降价组件.
- [choo-md-editor](https://github.com/dbtek/choo-md-editor) - 轻量级降价编辑器，可在Choo应用程序内使用或作为独立库使用.
- [choo-chartist](https://github.com/rexmortus/choo-chartist) - 使用的一个小组件 [Chartist](https://gionkunz.github.io/chartist-js/) 与choo框架.

### CLI Templates

模板 [choo-cli](https://github.com/trainyard/choo-cli)

- [trainyard/template-basic](https://github.com/trainyard/template-basic)
- [haroenv/template-webpack](https://github.com/haroenv/template-webpack)
- [simonwjackson/atomic-choo](https://github.com/simonwjackson/atomic-choo) - 通过电子，webpack和choo开始开发的一个自以为是的项目种子.

其他CLI模板
- [graforlock/choo-bandwagon](https://github.com/graforlock/choo-bandwagon)

### Resources
&gt;：movie_camera ::视频
&gt;：计算机::教程
&gt;：书::文章

- ：电脑： [Your first choo app](https://yoshuawuyts.gitbooks.io/choo/content/02_your_first_app.html)
- ：movie_camera： [TCBY community live hangout](https://www.youtube.com/watch?v=a97Mw2z1SAI)
- ：书： [A better frontend experience](https://medium.com/@yoshuawuyts/a-better-frontend-experience-7b0498c85658)
- ：书： [Composition in CycleJS, choo, React and Angular2](http://blog.krawaller.se/posts/composition-in-cyclejs-choo-react-and-angular2)
- ：书： [Stupidly smart components in choo](http://blog.krawaller.se/posts/stupidly-smart-components-in-choo)

### Projects using choo

- [boxcar](https://github.com/toddself/boxcar) - 基于选择的网格/电子表格编辑器.
- [choo-sortable](https://github.com/willkessler/choo-sortable) - 使用choo构建可排序代码.
- [hacker-choo](https://github.com/mw222rs/hacker-choo) - 用choo写的黑客Typer克隆.
- [footprint-rechoo](https://github.com/npeihl/footprint-rechoo) - 一个改写的选择 [footprint-review](http://github.com/sjcgis/footprint-review).
- [minidocs](https://github.com/freeman-lab/minidocs) - 使用choo构建的文档站点生成器.
- [dataface](https://github.com/timwis/dataface) - 桌面应用程序来管理数据库.
- [BlankUp](https://github.com/HoverBaum/BlankUp-Electron) - 多平台降价编辑器.
- [hackernews-choo](https://github.com/kvnneff/hackernews-choo) - 使用choo构建的黑客新闻阅读器.
- [tic-tac-choo](https://github.com/YerkoPalma/tic-tac-toe) - 进步的tic tac toe游戏，由choo制作.
- [enviar](https://github.com/timwis/enviar) - 短信/短信的聊天界面.
- [kaktus](https://github.com/kaktus/kaktus) - 基于`choo`和IndexedDB构建的新的简约Web浏览器.
- [civicdr.org](https://github.com/CiviCDR/civicdr.org) - 网站 [CiviCDR](https://civicdr.org/).
- [nekocafe](https://github.com/notenoughneon/nekocafe) - 网络聊天室：cat :: speech_balloon：.
- [Robotopia](https://github.com/robotopia-x/robotopia) - 向孩子们介绍使用微型虚拟机器人进行编码！
- [busca](https://github.com/afk-mcz/busca) - 一个小型的网络扩展程序，用于搜索reddit上的当前选项卡.
- [choo-ban](https://github.com/luizbaldi/choo-ban) - 使用`choo`构建的简单看板来管理董事会任务.
- [boowa](https://github.com/boowajs/boowa) - 一个有趣的博客生成器，用`choo`构建.
- [hyperamp](https://github.com/hypermodules/hyperamp) - 谦逊的音乐播放器.

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Yerko Palma](https://github.com/YerkoPalma) 已放弃对此作品的所有版权及相关或相邻权利.
