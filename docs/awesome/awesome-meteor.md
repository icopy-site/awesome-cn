<div class="github-widget" data-repo="Urigo/awesome-meteor"></div>
## Awesome Meteor [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精选的Meteor包，库和软件的精选列表.

可以找到官方的Meteor资源页面 [here](https://www.meteor.com/tools/resources)


- - -


## Getting Started

*从哪儿开始*

* [Official Meteor tutorial](https://www.meteor.com/try)
* [Discover Meteor Book](https://www.discovermeteor.com/)
* [Official Guide](http://guide.meteor.com/)
* [Why Meteor](https://wiki.dandascalescu.com/essays/why_meteor) 首先，和 [Meteor vs. the MEAN stack](https://wiki.dandascalescu.com/essays/meteor_js_vs_the_mean_stack)

## Collections

*收藏家和收藏品的费用*

* [node-simple-schema](https://github.com/aldeed/node-simple-schema/) - 一个JavaScript模式验证包，支持直接验证MongoDB更新修饰符对象
* [aldeed:collection2](https://github.com/aldeed/meteor-collection2/) - 自动验证客户端和服务器上的插入和更新操作.
* [dburles:collection-helpers](https://github.com/dburles/meteor-collection-helpers/) - 使用您定义的帮助程序转换集合.
* [matb33:collection-hooks](https://github.com/matb33/meteor-collection-hooks/) - 使用insert / update / remove / find / findOne的挂钩之前/之后扩展Mongo.Collection.
* [reywood:publish-composite](https://github.com/englue/meteor-publish-composite) - 使用反应式连接从各种集合中发布一组相关文档
* [jagi:astronomy](https://github.com/jagi/meteor-astronomy/) -  Meteor的模型层

## REST

*对Meteor *的REST支持

* [simple:rest](https://github.com/stubailo/meteor-rest) - 自动使您的Meteor应用程序可通过HTTP和DDP访问.
* [nimble:restivus](https://github.com/kahmali/meteor-restivus) - 以极其轻松的方式为您的Meteor应用程序创建REST端点.

## Forms and Templates

*模板助手*

* [aldeed:autoform](https://github.com/aldeed/meteor-autoform) - UI components and helpers to easily create basic forms with automatic insert and update events, and automatic reactive validation.
* [aldeed:template-extension](https://github.com/aldeed/meteor-template-extension) -  Meteor包：替换已定义的模板，从其他模板继承帮助程序和事件.
* [kadira:blaze-layout](https://github.com/kadirahq/blaze-layout) -  Blaze布局管理器（适用于Meteor FlowRouter）
* [dispatch:scrollview](https://github.com/DispatchMe/meteor-scrollview) - 流星的高性能无限滚动视图
* [themeteorites:blaze-magic-events](https://github.com/themeteorites/blaze-magic-events) - 将事件处理程序绑定到Meteor的Blaze的html元素的新方法
* [manuel:viewmodel](https://github.com/ManuelDeLeon/viewmodel) - 流星MVVM
* [webix:webix](https://github.com/dandv/meteor-webix) -  Meteor.js  -  Webix UI集成
* [uniforms](https://github.com/vazco/uniforms) - 一堆React组件和帮助器，可以轻松生成和验证表单. [Seamlessly integrate with `aldeed:simple-schema` and `simpl-schema`](https://github.com/vazco/uniforms/blob/master/INTRODUCTION.md#quick-start).

## Users and Authentication

*处理用户和身份验证的工具*

* [accounts-base](https://guide.meteor.com/accounts.html) -  Meteor的用户帐户系统.
* [alanning:roles](https://github.com/alanning/meteor-roles) - 角色支持内置帐户包.

## Payments

*处理Meteor付款的工具*

* [Stripe](https://atmospherejs.com/mrgalaxy/stripe) -  Stripe的支付网关
* [PayPal](https://atmospherejs.com/mrt/paypal) -  PayPal的支付网关
* [BrainTree](https://atmospherejs.com/patrickml/braintree) -  BrainTree的支付网关
* [Instamojo](https://atmospherejs.com/instamojo/instamojo) -  Instamojo的支付网关

## Deployment

*部署和维护Meteor应用程序的工具*

* [When a Meteor finally hits production](https://medium.com/@davidyahalomi/when-a-meteor-finally-hits-production-6c37b81f795b) - 关于部署Meteor应用程序的博客文章
* [BulletProof Meteor](https://bulletproofmeteor.com/)
* [meteorhacks:kadira](https://github.com/meteorhacks/kadira) - 流星的性能监测.
* [meteor-up](https://github.com/arunoda/meteor-up) - 流星部署.
* [davidyaha:collection2-migrations](https://github.com/davidyaha/meteor-collection2-migrations) - 在Meteor上使用collection2和简单模式进行自动数据库迁移
* [percolate:migrations](https://github.com/percolatestudio/meteor-migrations) -  Meteor的简单迁移系统
* [meteorhacks:fast-render](https://github.com/kadirahq/fast-render) - 即使在DDP连接生效之前渲染您的应用程序
* [staringatlights:fast-render](https://github.com/abecks/meteor-fast-render) - 快速渲染的活动分支
* [meteorhacks:cluster](https://github.com/meteorhacks/cluster) -  Meteor的集群解决方案，具有负载平衡和服务发现功能
* [yogiben:admin](https://github.com/yogiben/meteor-admin) - 完整的管理仪表板解决方案
* [demeteorizer](https://github.com/onmodulus/demeteorizer) - 将Meteor应用程序转换为“标准”Node.js应用程序
* [houston:admin](https://github.com/gterrono/houston) -  Meteor的零配置，Django Admin式管理员
* [pm2-meteor](https://github.com/andruschka/pm2-meteor) - 使用PM2部署，扩展和运行Meteor应用程序的最简单方法.
* [kschingiz:meteor-elastic-apm](https://github.com/kschingiz/meteor-elastic-apm) - 基于弹性APM的流星性能监测

## Routers

* Blaze的路由器*

* [iron:router](https://github.com/iron-meteor/iron-router) - 专为Meteor设计的客户端和服务器端路由器.
* [kadira:flow-router](https://github.com/kadirahq/flow-router) -  Meteor的客户端路由器.
* [ostrio:flow-router-extra](https://github.com/VeliovGroup/flow-router)   - 仔细扩展`flow-router`包.  支持最新Meteor版本的最新版本.
* [meteorhacks:picker](https://github.com/meteorhacks/picker) -  Meteor的服务器端路由器.
* [msavin:parrot](https://github.com/msavin/Parrot) - 专为使用Meteor构建SPA而设计的Web路由器

## Offline

* Meteor离线支持工具*

* [ground:db](https://github.com/GroundMeteor/db) -  GroundDB是一个薄层，提供Meteor离线数据库和方法.

## Testing

*测试工具*

* [Meteor Testing Manual](http://www.meteortesting.com/)
* [mike:mocha](https://github.com/mad-eye/meteor-mocha-web/) - 在Meteor框架内运行mocha测试.
* [xolvio:chimp](https://github.com/xolvio/chimp)   - 测试如此简单，灵长类动物可以做到！  支持摩卡，黄瓜，茉莉和柴.
* [velocity:html-reporter](https://github.com/meteor-velocity/html-reporter) - 流星速度测试框架的HTML记者.
* [Gagarin](https://github.com/anticoders/gagarin) - 您的流星应用程序的另一个测试框架.

## SEO

*搜索引擎优化工具*

* [ostrio:spiderable-middleware](https://github.com/VeliovGroup/spiderable-middleware/) - 在ES6（ECMAScript2015）的支持下预呈现（* aka Spiderable *） -  Meteor应用程序完全被搜索引擎抓取.

## Files

*处理Meteor中的文件*

* [Meteor-CollectionFS](https://github.com/CollectionFS/Meteor-CollectionFS) -  Meteor基于web的文件系统处理和下载.
* [ostrio:files](https://github.com/VeliovGroup/Meteor-Files)   - 通过DDP，HTTP和WebRTC / DC上传文件.  到Meteor服务器FS，AWS，GridFS，DropBox或Google Drive.  快速，安全和强大.
* [netanelgilad:excel](https://github.com/netanelgilad/meteor-excel) - 解析和生成excel文件（xlsx，xls）.

## Search, sort and paginate

*搜索，排序和分页相关工具*

* [tmeasday:publish-counts](https://github.com/percolatestudio/publish-counts) - 实时发布光标的计数.
* [percolate:find-from-publication](https://github.com/versolearning/find-from-publication) - 允许查找给定出版物已发布的所有文档.
* [meteorhacks:search-source](https://github.com/meteorhacks/search-source) - 搜索的反应数据源
* [matteodem:easy-search](https://github.com/matteodem/meteor-easy-search) - 使用Blaze组件轻松搜索（+弹性搜索支持）
* [alethes:pages](https://github.com/alethes/meteor-pages) - 开箱即用的Meteor分页
* [Discover Meteor Blog about pagination](https://www.discovermeteor.com/blog/pagination-problems-meteor/)

## Mobile

*移动开发*

* [meteoric:ionic](https://github.com/meteoric/meteor-ionic) -  Meteor的离子组件.
* [driftyco:ionic](https://github.com/driftyco/ionic) -  Meteor官方Ionic支持.
* [raix:push](https://github.com/raix/push) - 推送cordova（ios，android）浏览器（Chrome，Safari，Firefox）的通知.
* [martijnwalraven:meteor-ios](https://github.com/martijnwalraven/meteor-ios) - 通过DDP将本机iOS应用程序与Meteor平台集成.
* [delight-im/Android-DDP](https://github.com/delight-im/Android-DDP) - 适用于Android的客户端的DDP.
* [okland:accounts-phone](https://github.com/okland/accounts-phone) - 基于Meteor移动电话号码的登录服务.
* [okland:camera-ui](https://github.com/okland/camera-ui)   - 用于使用用户界面拍照的Meteor包，桌面和移动设备上的一个功能调用.  允许在手机上选择相机到photoLibrary.
* [percolatestudio/cordova-plugin-safe-reload](https://github.com/percolatestudio/cordova-plugin-safe-reload) - 在破碎的流星热码推送后观看和恢复的Cordova插件.

## Data Visualization

*流星中的数据可视化：图表，地图，表格等*

* [AnyChart-Meteor](https://github.com/AnyChart/AnyChart-Meteor) - 该软件包提供了一种在Meteor中使用AnyChart JavaScript图表组件的简单方法.
* [aldeed:tabular](https://github.com/aldeed/meteor-tabular) - 用于大型或小型数据集的反应性数据表.
* [luixal:blaze-paginated-custom-list](https://github.com/luixal/meteor-blaze-paginated-custom-list) - 反应和分页项目列表.
* [luixal:meteor-apexcharts](https://github.com/luixal/meteor-apexcharts) - 为Meteor打包的Reactive ApexCharts库.

## Analytics

*Analytics*

* [okgrow:analytics](https://github.com/okgrow/analytics/) - 针对流星的Google Analytics，Mixpanel，KISSmetrics（及更多）集成.

## Cron Jobs

*流星中的Cron Jobs *

* [percolate:synced-cron](https://github.com/percolatestudio/meteor-synced-cron)   -  Meteor的Cron系统.  它支持在多个进程之间同步作业.
* [vsivsi:job-collection](https://github.com/vsivsi/meteor-job-collection/) -  Meteor的持久且反应性的作业队列，支持可在任何地方运行的分布式工作人员.
* [ostrio:cron-jobs](https://github.com/VeliovGroup/Meteor-CRON-jobs) - 具有与本机`setTimeout`和`setInterval`方法类似的API的包，但在所有正在运行的Meteor（NodeJS）实例之间同步.

## Debugging Tools

*调试工具*

* [msavin:mongol](https://github.com/msavin/Mongol/) - 用于MongoDB集合的Meteor的可视化编辑工具.
* [msavin:jetsetter](https://github.com/msavin/JetSetter) -  Meteor会话变量的可视获取/设置工具.
* [meteorhacks:kadira-debug](https://github.com/kadirahq/meteor-debug) -  Meteor的全栈调试解决方案.
* [babrahams:constellation](https://github.com/JackAdams/constellation-distro/) -  Meteor的可扩展开发控制台.
* [Meteor DDP Monitor](https://github.com/thebakeryio/meteor-ddp-monitor) - 用于监控Meteor DDP流量的Chrome Dev工具扩展

## Package Managers

*在Meteor *中使用包管理器

* [meteorhacks:npm](https://github.com/meteorhacks/npm/) - 将Npm模块与Meteor应用程序一起使用.
* [cosmos:browserify](https://github.com/elidoran/cosmos-browserify) - 在Meteor包中浏览用于客户端的npm模块.

## Scaffolding

*Scaffolding*

* [Meteor Kitchen](http://www.meteorkitchen.com/) -  Meteor的代码生成器
* [iron-cli](https://github.com/iron-meteor/iron-cli) -  Meteor应用程序的脚手架命令行工具
* [Differential - meteor-boilerplate](https://github.com/Differential/meteor-boilerplate)
* [meteoris2](https://github.com/radiegtya/meteoris2)
* [Base](https://github.com/themeteorchef/base)

## Tooling

* [ESLint-plugin-Meteor](https://github.com/dferber90/eslint-plugin-meteor/) -  Meteor的ESLint插件

## Boilerplate

* [matteodem - meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate)
* [React with Webpack + Meteor as a backend](http://julian.io/react-with-webpack-meteor-as-a-backend/)

## Open source apps
* [VulcanJS](https://github.com/VulcanJS/Vulcan) - 使用React，GraphQL和Meteor快速构建应用程序的工具包
* [Microscope](https://github.com/DiscoverMeteor/Microscope) -  Discover Meteor书的示例应用程序
* [Wekan](https://github.com/wekan/wekan) - 开源Trello式看板
* [Reaction Commerce](https://github.com/reactioncommerce/reaction) - 使用Meteor开发的开源商务平台
* [Crowducate Platform](https://github.com/Crowducate/crowducate-platform) - 开源教育平台由流星提供支持
* [Orion CMS](http://orionjs.org/)
* [Rocket.Chat](https://rocket.chat/)

## Front End Frameworks

* Blaze的替代前端框架*

* [Blaze](http://blazejs.org/guide/introduction.html)
* [React](http://react-in-meteor.readthedocs.org/en/latest/) - 使用React和Meteor
* [Angular](https://github.com/Urigo/angular-meteor) - 使用Angular和Meteor
* [Angular 2](https://github.com/Urigo/angular2-meteor) - 使用Angular 2和Meteor
* [Famo.us](https://github.com/gadicc/meteor-famous-views/) -  Famo.us和Meteor
* [Vue](https://github.com/Akryum/meteor-vue-component) - 使用Vue和Meteor（加上单文件组件和apollo支持）

* [frozeman:build-client](https://github.com/frozeman/meteor-build-client) - 捆绑Meteor应用程序的客户端部分的工具.
* [Asteroid](https://github.com/mondora/asteroid) -  Meteor后端的另一个客户端
* [ddp.js](https://github.com/mondora/ddp.js) - 同构JavaScript DDP客户端

## Alternative Databases

* MongoDB *的替代数据库

* [meteor-pg](https://github.com/Richie765/meteor-pg) - 为Meteor提供新的和改进的PostgreSQL支持
* [ostrio:neo4jdriver](https://github.com/VeliovGroup/ostrio-neo4jdriver/) -  Meo的Neo4j驱动程序，支持GrapheneDB
* [numtel:pg](https://github.com/numtel/meteor-pg) -  Meteor的Reactive PostgreSQL
* [numtel:mysql](https://github.com/numtel/meteor-mysql) -  Meteor的Reactive MySQL
* [simple:rethink](https://github.com/Slava/meteor-rethinkdb) - 针对Meteor的RethinkDB集成

## Resources

在哪里发现新的流星事物.

## Books

* [Meteor Explained](https://gumroad.com/l/meteor-explained)
* [Meteor Tips](http://meteortips.com/)
* [Meteor Cookbook](https://github.com/awatson1978/meteor-cookbook)

## Courses

* [EventedMind](https://www.eventedmind.com/)
* [Udemy — Meteor: Build a real-time web app using only JavaScript](https://www.udemy.com/meteor-course/)
* [Udemy - A Beginner's Guide to the Meteor JavaScript Framework](https://www.udemy.com/meteorjs/)
* [tuts+ - Single Page Web Apps with Meteor](http://code.tutsplus.com/courses/single-page-web-apps-with-meteor)
* [DevFreeCasts.org](http://devfreecasts.org/meteor/)
* [MeteorTuts](http://meteortuts.com/)

## Tutorials

* [Building a CMS-powered blog in Meteor](https://buttercms.com/blog/meteor-cms-blog-tutorial)
* [scotch.io - Building a Slack Clone in Meteor](https://scotch.io/tutorials/building-a-slack-clone-in-meteor-js-getting-started)
* [Rocket-Chat Slack Clone](https://rocket.chat/)
* [Meteor Learning](https://github.com/ericdouglas/Meteor-Learning) - 要学习的资源清单
* [Phusion Passenger: Meteor tutorial](https://github.com/phusion/passenger/wiki/Phusion-Passenger:-Meteor-tutorial)

## Blogs

* [Official Meteor blog](http://blog.meteor.com)
* [The Meteor podcast](http://podcast.crater.io)
* [Blog about Optimistic UIs With Meteor Latency Compensation](http://info.meteor.com/blog/optimistic-ui-with-meteor-latency-compensation)

## Websites

* [Official website](https://www.meteor.com/)
* [Official Documentation](http://docs.meteor.com/)
* [Official Guide](http://guide.meteor.com/)
* [Atmosphere](https://atmospherejs.com/) -  Meteor包，资源和工具的目录.
* [BulletProof Meteor](https://bulletproofmeteor.com/) -  Arunoda Susiripala在线制作Meteor表演的在线课程
* [Meteorpedia](http://www.meteorpedia.com) ([infrequently](http://www.meteorpedia.com/special/RecentChanges/) 更新）
* [DiscoverMeteor Encyclopedia](https://www.discovermeteor.com/encyclopedia)
* [Roadmap](https://trello.com/b/hjBDflxp/meteor-roadmap)
* [Meetups](http://meteor.meetup.com/)
* [Reddit](https://www.reddit.com/r/meteor)
* [YouTube](https://www.youtube.com/channel/UC3fBiJrFFMhKlsWM46AsAYw) 来自世界各地的聚会视频
* [Unofficial Meteor FAQ](https://github.com/oortcloud/unofficial-meteor-faq)
* [The Meteor Chef](https://themeteorchef.com)

### Q&A

* [Stack Overflow](http://stackoverflow.com/questions/tagged/meteor?sort=newest&pagesize=15)
* [Meteor forums](https://forums.meteor.com/)
* [Gitter IM channel](https://gitter.im/meteor/meteor)
* [The Meteor Chef Slack channel](https://themeteorchef.slack.com)
* IRC - #meteor on freenode


## Weekly

* [Meteor-Blog](http://info.meteor.com/blog)
* [Meteor Weekly](https://goodbits.io)
* [This Week In Meteor](https://goodbits.io)

## Twitter

* [Official Meteor](https://twitter.com/meteorjs)

## Job Boards

* [We Work Meteor](https://www.weworkmeteor.com/)

## [Contributing](https://github.com/urigo/awesome-meteor/blob/master/CONTRIBUTING.md)

欢迎您的贡献！

感谢@gillesfabio创建此回购！
