<div class="github-widget" data-repo="yissachar/awesome-dart"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
Awesome Dart [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
============

A curated list of awesome Dart frameworks, libraries, and software. Items on the list are actively maintained, well documented, and popular in the Dart community. Inspired by the [awesome](https://github.com/sindresorhus/awesome) 列表.

### Contributing

Please take a quick look at the [contribution guidelines](https://github.com/yissachar/awesome-dart/blob/master//CONTRIBUTING.md) first. If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you to all [contributors](https://github.com/yissachar/awesome-dart/graphs/contributors) ; 你摇滚！


* Libraries

----

## Client Web App Frameworks

* [AngularDart](https://angulardart.org/) - AngularDart is a development platform for building mobile and desktop web applications.
* [Flutter](https://flutter.dev/) - Flutter 是一个构建高性能、跨平台移动应用程序的框架，允许为 Android、iOS 和 Web 应用程序编写应用程序.
* [MDL/Dart](http://mdl.mikemitterer.at//) - Material Design Lite for Dart is a framework of components for web developers based on Google's Material Design philosophy.
* [OverReact](https://workiva.github.io/over_react/) - A library for building statically-typed React UI components.
* [VueDart](https://refi64.com/vuedart) - Create Vue web apps using Dart, a progressive, incrementally-adoptable framework for building Web UIs.


## Server Frameworks

* [Jaguar](https://github.com/Jaguar-dart/jaguar) - A server framework built for speed, simplicity and extensibility.
* [Start](https://github.com/lvivski/start) - Sinatra inspired web framework to serve static files, handle dynamic requests, websockets and create JSON responses.
* [Shelf](https://pub.dartlang.org/packages/shelf) - Shelf 可以轻松创建和组合 Web 服务器和部分 Web 服务器.
    * There are many packages written for Shelf. By convention they start with [shelf_](https://pub.dartlang.org/search?q=shelf_).
* [Vane](https://github.com/Scorpiion/Vane) - Framework with built-in server runtime environment and middleware system.
* [Rikulo Stream](https://github.com/rikulo/stream) - Lightweight web server with request routing, filtering, template engine, WebSocket, MVC design pattern, and file-based static resources.
* [Alfred](https://github.com/rknell/alfred) - 带有路由和中间件的受 ExpressJS 启发的最小服务器.

## Cross-platform development
* [universal_io](https://github.com/terrier989/universal_io) - _dart:io_ 也适用于浏览器.
* [universal_html](https://github.com/terrier989/universal_html) - _dart:html_ that also works in the VM/Flutter.

## Game Development

* [Flame](https://github.com/luanpotter/flame#readme) - A minimalist Flutter game engine.
* [DartRocket](https://github.com/StrykerKKD/dartrocket) - DartRocket is a HTML5 game framework written in Dart and which uses the StageXL rendering engine.
* [Pixi Dart](https://github.com/FedeOmoto/pixi) - A port of the pixi.js rendering engine.
* [Ranger](https://github.com/wdevore/Ranger-Dart) - 以 HTML5 Canvas 和场景图为中心的游戏引擎.

## Animation

* [Universal Tween Engine](https://github.com/xaguzman/tween-engine-dart) - A port of the original java Universal Tween Engine created by Aurelien Ribbon.
* [Spine Dart](https://github.com/FedeOmoto/spine) - An implementation of the Esoteric Software Spine runtime.

## Template

* [mustache_template](https://pub.dev/packages/mustache_template) - A mustache template library that supports dart2js and dart2native.
* [jaded](https://github.com/dartist/jaded) - Port of the excellent Jade view engine.

## Database

* [Postgres](https://github.com/stablekernel/postgresql-dart) - 一个 PostgreSQL 数据库驱动程序，它使用扩展的二进制协议来实现更高效和安全的查询.
* [SQLJockey](https://github.com/jamesots/sqljocky) - MySQL 连接器.
* [PostgreSQL](https://github.com/xxgreg/dart_postgresql) - PostgreSQL database driver.
* [dartabase_model](https://pub.dartlang.org/packages/dartabase_model) - 服务器端数据库对象模型，用于使用 MySQL/PGSQL 进行简单的数据操作，而无需编写 SQL.
* [dartabase_migration](https://pub.dartlang.org/packages/dartabase_migration) - Serverside Database migration for simple version controlled database structure manipulation using MySQL/PGSQL without having to write SQL.

## Package Managers

* [Pub](https://pub.dartlang.org/) - Pub is used to manage packages.

## Utilities

* [Archive](https://pub.dartlang.org/packages/archive) - A library to encode and decode various archive and compression formats.
* [built_collection](https://github.com/google/built_collection.dart) - Immutable collections via the builder pattern. 
* [built_value](https://github.com/google/built_value.dart) - 不可变的值类型、枚举类和序列化.
* [Frappe](https://pub.dartlang.org/packages/frappe)  - Dart 的函数式反应式编程库.  Frappé 扩展了 Dart 流的功能，并引入了属性/信号等新概念.
* [Quiver](https://github.com/google/quiver-dart) - A set of utility libraries that makes using many libraries easier and more convenient, or adds additional functionality.
* [route_hierarchical](https://github.com/angular/route.dart) - Route 是 Dart 的客户端路由库，有助于构建单页 Web 应用程序.
* [Darq](https://pub.dev/packages/darq) - A port of functional LINQ from the .NET library.

## Dependency Injection

* [Angular DI](https://webdev.dartlang.org/angular/guide/dependency-injection) - Angular 的依赖注入框架.
* [Dependencies](https://github.com/marcguilera/dependencies.dart) - A simple and modular dependency injection system which doesn't use mirrors.
* [package: inject](https://github.com/google/inject.dart) - Dart 和 Flutter 的编译时依赖注入

## Parsers

* [html](https://pub.dartlang.org/packages/html) <i>- A library for working with HTML documents.</i> <b>- 用于处理 HTML 文档的库。</b> <i>Previously known as html5lib.</i><b>以前称为 html5lib。</b>
* [markdown](https://github.com/dart-lang/markdown) - Parse markdown into HTML on both the client and server.
* [PetitParser](https://github.com/petitparser/dart-petitparser) - PetitParser combines ideas from scannerless parsing, parser combinators, parsing expression grammars and packrat parsers to model grammars and parsers as objects that can be reconfigured dynamically.
* [XML](https://pub.dartlang.org/packages/xml) - A lightweight library for parsing, traversing, querying and building XML documents.
* [xmlstream](https://pub.dartlang.org/packages/xml) - A streaming event-based XML Parser.
* [YAML](https://pub.dartlang.org/packages/yaml) - A parser for YAML.
* [Dart Tags](https://pub.dartlang.org/packages/dart_tags) - The library for parsing ID3 tags, written in pure Dart.


## Validation

* [Constrain](https://pub.dartlang.org/packages/constrain) - 提供受 Java Bean Validation 启发的基于约束的 Validation 库，但利用了 Dart 的卓越语言功能.
* [validator.dart](https://github.com/karan/validator.dart) - String validation and sanitization for Dart.

## ORM

* [Objectory](https://github.com/vadimtsushko/objectory) - Objectory provides typed, checked environment to model, save and query data persisted on MongoDb.

## Image

* [image](https://github.com/brendan-duncan/image) - Provides server and web apps the ability to load, manipulate, and save images with various image file formats including PNG, JPEG, GIF, WebP, TIFF, TGA, PSD, PVR, and OpenEXR.

## Testing

* [Guinness](https://github.com/vsavkin/guinness) - A port of the Jasmine library.
* [test](https://pub.dartlang.org/packages/test) - Provides a standard way of writing and running tests in Dart.

## Unions

* [Freezed](https://github.com/rrousselGit/freezed) - 不可变类的代码生成具有简单的语法/API，而不会影响功能.

## Crash monitoring

* [Sentry](https://github.com/getsentry/sentry-dart) - Sentry provides self-hosted and cloud-based error monitoring that helps all software teams discover, triage, and prioritize errors in real-time.

## Tools

* [DevTools](https://dart.dev/tools/dart-devtools) - 一套用于 Dart 和 Flutter 的调试和性能工具.
* [dart2js](https://www.dartlang.org/tools/dart2js/) - compiles Dart code to JavaScript.
* [js2dart](https://github.com/vojtajina/js2dart) - 将 Javascript 代码编译为 Dart.
* [Stagehand](https://github.com/dart-lang/stagehand) - 一个项目脚手架生成器，灵感来自 Web Starter Kit 和 Yeoman 等工具.
* [Crossdart](https://crossdart.info) - Cross-referenced source code of the packages from Pub.
* [Crossdart Github Chrome Extension](https://chrome.google.com/webstore/detail/crossdart-chrome-extensio/jmdjoliiaibifkklhipgmnciiealomhd) - 在 Github 上的 Dart 项目中添加“转到声明”和“查找用法”功能（在树视图和拉取请求中）.
* [gulp-dart](https://github.com/agudulin/gulp-dart) - A gulp plugin for compiling Dart code to JavaScript using dart2js.
* [dev_compiler](https://github.com/dart-lang/dev_compiler) - Dart to JavaScript compiler designed to create idiomatic, readable JavaScript output.
* [json2dart](https://javiercbk.github.io/json_to_dart) - 给定一个 json，它会生成 dart 类来解析和生成具有给定结构的 json.
* [webdev_proxy](https://github.com/Workiva/webdev_proxy) - A proxy wrapper around [webdev](https://github.com/dart-lang/webdev) which adds support for rerouting 404s to the index, allowing for HTML push-based routing while running locally.
* [Dart Code Metrics](https://github.com/dart-code-checker/dart-code-metrics) - Additional linter which reports code metrics, checks for anti-patterns and provides additional rules for Analyzer.
* [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic ML models into a native Dart code with zero dependencies.
* [Lakos](https://pub.dev/packages/lakos) - Visualize internal library dependencies in Graphviz and detect dependency cycles.

## Tutorials

* [Hello Dart](http://code.makery.ch/library/hello-dart/) - 有趣的 Dart 介绍.
* [Getting Started with Dart & React](https://www.leejamesrobinson.com/blog/getting-started-with-dart-and-react/)
* [Tour of Heroes](https://webdev.dartlang.org/angular/tutorial) - An app which covers the core fundamentals of AngularDart. 
* [Dart for beginner](https://www.myfreax.com/tag/dart/) - 初学者飞镖中文教程.
* [Resolving Dart package version conflicts, faster than ever](https://iiro.dev/2018/08/28/resolving-dart-package-version-conflicts/) - 如何使用 pub 中的任何包版本来解决包版本冲突.

## Community

* [Dartlang SubReddit](https://www.reddit.com/r/dartlang/)
* [Gitter Chat Channel](https://gitter.im/dart-lang/home)
* [Google Group](https://groups.google.com/a/dartlang.org/d/forum/misc)
* [Stack Overflow](https://stackoverflow.com/tags/dart)
* [Facebook Group (pt-BR)](https://www.facebook.com/groups/dartlangbr)
* [Telegram chat (ru-RU)](https://t.me/rudart)
* [Telegram chat (id-ID)](https://t.me/dart_web)


## IDEs, Editors, and Plugins

* [IntelliJ Plugin](https://www.dartlang.org/tools/webstorm/) - Dart plugin from JetBrains for WebStorm, IntelliJ IDEA, PhpStorm, PyCharm, and RubyMine.
* [Sublime Text Package](https://github.com/guillermooo/dart-sublime-bundle) - Sublime Text 3 Dart Package.
* [Emacs Plugin](https://github.com/nex3/dart-mode) - Dart 语言的 Emacs 模式.
* [Vim Plugin](https://github.com/dart-lang/dart-vim-plugin) - Vim 中 Dart 的语法高亮显示.
* [Atom Plugin](https://atom.io/packages/atom-dart) - Dart support for Atom.
* [VSCode Plugin](https://dartcode.org/) - 对 Visual Studio Code 的 Dart 支持.
* [DartPad](https://dartpad.dartlang.org/) - 在线轻量级编辑器.
* [Dart Code](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code) - 对 Visual Studio Code 的 Dart 支持.
* [Module Linker](http://fiatjaf.alhur.es/module-linker/#/dart) - Chrome Extension that adds direct links to module import statements on GitHub.

## Everything Else

There are lots of awesome libraries being added to [Pub](https://pub.dartlang.org/) all the time. If you can't find a library on this list that meets your needs, go ahead and search for it on Pub. And if you end up finding an awesome library, we would love a pull request with the info so that everyone else can discover it as well. Just make sure to read the [contributing guidelines](https://github.com/yissachar/awesome-dart/blob/master/CONTRIBUTING.md) 第一的.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
