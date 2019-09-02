<div class="github-widget" data-repo="JesseTG/awesome-qt"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Qt  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cdn.rawgit.com/JesseTG/awesome-qt/ef9f71a9/qt.svg" align="right" width="100">](https://www.qt.io)

&gt; Qt框架的精彩工具，库和资源的精选列表.

[Qt](https://www.qt.io)  是一个功能强大的跨平台应用程序开发框架，主要用于（但不是唯一）C ++.  它非常适合GUI应用程序，但也可以用于许多其他事情.

欢迎捐款！

## Conventions

  - 任何带有OctoCat的列表项：octocat：有一个GitHub仓库或组织;  点击它查看源代码！
- 使用此列出项目：package：icon具有托管在其他位置的源代码.



## Official Resources

- [Official Website](https://www.qt.io) -  Qt框架的官方网站.
- [Qt Documentation](https://doc.qt.io)   - 官方Qt文档.  庞大而全面.
- [Qt Newsletters](https://www.qt.io/newsletters) - 最好的Qt，直接到你的垃圾邮件过滤器.
- [Qt Bug Tracker](https://bugreports.qt.io) - 如果您认为自己发现了Qt或其中一个相关项目的错误，请在此处报告（或查看是否已有其他人）.
- [Qt Code Review](https://codereview.qt-project.org) - 了解Qt维护者如何确保他们的代码编写良好.
- [Source Code](https://code.qt.io)   - 浏览组成Qt项目的各种源树.  在几个GitHub组织中有镜像：
  -  Qt [:octocat:](https://github.com/qt)
  -  Qt项目 [:octocat:](https://github.com/qtproject)
  -  Qt Labs [:octocat:](https://github.com/qt-labs)

## Communities

 如果你盖了，他们会来的.  本节描述了彼此共享知识和代码的Qt用户的聚合.  本节列出了最受欢迎和最活跃的社区，但您可以找到更全面的列表 [here](https://wiki.qt.io/Online_Communities) （如果您愿意，可以包括其他几种语言）.

### Official

- [Mailing Lists](http://lists.qt-project.org)   -  Qt用户和开发人员的邮件列表.  可以说是与Qt维护者直接沟通的最佳场所.  看到频繁的活动.
- [Qt Forum](https://forum.qt.io) - 如果电子邮件不是你的东西，那么你也可以考虑在论坛上获得帮助或分享知识.
- [Qt Wiki](https://wiki.qt.io) - 用户贡献的Qt知识的主要来源.
- [IRC](https://webchat.freenode.net/?channels=%23qt%2C%23qt-quick%2C%23qt-creator%2C%23qt-chat) - For real-time chat with other Qt developers and users.  The most popular channels are on Freenode, and include `#qt`, `#qt-quick`, `#qt-creator`, and `#qt-chat`.
  - 有关与Qt相关的IRC频道的完整列表，请参阅 [here](https://wiki.qt.io/Online_Communities#IRC_channels).
    - 请注意，链接的网络聊天客户端不是Qt项目的一部分，仅为方便起见，由此列表的作者提供.  可以通过任何IRC客户端访问这些通道.

### Unofficial

- [QtForum.org](http://www.qtforum.org) - 不要与官员混淆 [Qt forum](https://forum.qt.io).


## Tools

 一个优秀的开发人员编写他或她自己的工具.  一个伟大的人使用别人写的工具.  这部分将帮助你变得更好;  更正式地说，本节详细介绍了使用Qt创建软件更容易的应用程序.  您可能也对此感兴趣 [Libraries](#libraries) 部分.

### Official Tools

 令人惊讶的是，Qt框架有许多工具无法引起人们的关注.  这部分描述了它们（以及做过的明星球员）.  出于本节的目的，“工具”指的是以Qt为中心的实用程序，其代码不会嵌入您的应用程序中（但可能会输出它们）.

- [Qt Creator](https://www.qt.io/ide) [:octocat:](https://github.com/qtproject/qt-creator)   -  Qt绝不会锁定你提供的IDE，但它与框架的紧密集成使它成为一个很好的销售.  除此之外，它还提供了UI设计器，建模工具，文档浏览器以及强大的QML支持（如果您涉及到这类内容）.  还有一个插件系统，但遗憾的是第三方插件很少.
  - [Qt Designer](https://doc.qt.io/qt-5/qtdesigner-manual.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/designer) - 如果您只是设计接口并让其他人将它们连接到逻辑，则GUI设计器可作为单独的应用程序使用.
  - [Qt Assistant](https://doc.qt.io/qt-5/qtassistant-index.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/assistant) - 就此而言，文档查看器也是如此.
- [Qt Visual Studio Add-in](https://doc.qt.io/archives/vs-addin) [:octocat:](https://github.com/qt-labs/vstools) - 如果你更喜欢坚持使用Visual Studio，这个加载项可以让你这样做.
- [Qt Linguist](https://doc.qt.io/qt-5/qtlinguist-index.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/linguist) - Qt provides excellent internationalization/localization support, and this tool is very much responsible for it.  Write translatable strings in your code with special macros, and this tool will aggregate them all for you so you or your translator(s) can broaden your software's audience.
- [Qt Installer Framework](https://doc.qt.io/qtinstallerframework) [:octocat:](https://github.com/qtproject/installer-framework)   - 似乎没有人谈论这个问题，但Qt还提供了一种为应用程序编写安装程序的方法.  不支持创建macOS磁盘映像，应用程序包或Linux软件包，因此在考虑项目的分发时请注意这一点.
  - [`macdeployqt`](https://doc.qt.io/qt-5/osx-deployment.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/macdeployqt) - 为Qt项目生成macOS应用程序包.
- [qmake](https://doc.qt.io/qt-5/qmake-manual.html) [:octocat:](https://github.com/qt/qtbase/tree/dev/qmake) - 为Qt设计的捆绑构建系统，尽管它可以用于非Qt项目.
- [qbs](https://doc.qt.io/qbs) [:octocat:](https://github.com/qt-labs/qbs) - 如果QML更符合您的风格，请考虑使用此备用构建系统.
- [Emulator](https://doc.qt.io/emulator) - 别忘了Qt的移动支持！
- `qtdiag` [:octocat:](https://github.com/qt/qttools/tree/dev/src/qtdiag)   - 命令行工具，可以打印出与Qt安装和系统有关的大量信息.  没有链接，因为没有专门的网页;  只需在命令行上运行`qtdiag`.  非常适合排除故障
- `qmleasing` [:octocat:](https://github.com/qt/qtdeclarative/tree/dev/tools/qmleasing) - 允许您制作适合QML的缓动曲线，但如果您了解基础数学，则无法在其他地方使用结果数字.

### Third-Party Tools

- [CMake](https://doc.qt.io/qt-5/cmake-manual.html) [:octocat:](https://github.com/Kitware/CMake) - 通用C ++构建工具恰好有很好的Qt支持.
- [GammaRay](https://www.kdab.com/development-resources/qt-tools/gammaray) [:octocat:](https://github.com/KDAB/GammaRay)   - 用于Qt构建软件的强大调试器和通用检测工具.  允许您检查和操作`QObject`层次结构，查看对象属性，在运行时编辑窗口小部件，远，*远*更多.  两句话模糊不能正义，认真检查出来.
- [moc-ng](https://github.com/woboq/moc-ng) [:octocat:](https://github.com/woboq/moc-ng) - 与mt版本二进制兼容的`moc`的替代实现.
- [Qt-Inspector](https://github.com/robertknight/Qt-Inspector) [:octocat:](https://github.com/robertknight/Qt-Inspector) - 具有与GammaRay类似目标的检查工具，虽然简单得多.
- [SIP](https://www.riverbankcomputing.com/software/sip) [:package:](https://www.riverbankcomputing.com/hg/sip)   - 为C或C ++库生成Python绑定.  对Qt信号和插槽有特殊支持，并用于创建 [PyQt](https://riverbankcomputing.com/software/pyqt).
- [linuxdeployqt](https://github.com/probonopd/linuxdeployqt) [:octocat:](https://github.com/probonopd/linuxdeployqt) - 允许您将基于Qt的应用程序捆绑为AppDir或 [AppImage](http://appimage.org) ，使其可以发送给许多桌面Linux发行版的用户.  类似于官方的`windeployqt`和`macdeployqt`工具，但适用于Linux.

## Bindings in Other Languages

 本节介绍可以使用C ++以外的主要语言创建Qt软件的软件.  允许在Qt应用程序中运行时编写脚本的库列在下面 [Integrations](#integrations).

- [Python (via PyQt)](https://riverbankcomputing.com/software/pyqt) [:package:](https://www.riverbankcomputing.com/software/pyqt/download5) - Arguably the most comprehensive and well-known binding of Qt to another language.
- [Python (via PySide)](https://wiki.qt.io/PySide) [:package:](https://code.qt.io/cgit/pyside/pyside.git) -  Python的另一个绑定，已被Qt项目正式采用.
- [Ring (via RingQt)](http://ring-lang.sourceforge.net/doc/qt.html) [:octocat:](https://github.com/ring-lang/ring/tree/master/extensions/ringqt) - 说实话，我也从未听说过这种语言.
- [Mono/.NET languages (via QtSharp)](https://github.com/ddobrev/QtSharp) [:octocat:](https://github.com/ddobrev/QtSharp) - Experimental wrapper for Qt that allows it to be used by .NET-based languages such as C#.  Young, but active.

看到这些 [these](https://www.ics.com/blog/using-qt-alternative-programming-languages-part-1) [three](https://www.ics.com/blog/using-qt-alternative-programming-languages-part-2) [articles](https://wiki.qt.io/Category:LanguageBindings) 如果你想要更多.

## Libraries

This section describes two kinds of third-party libraries; those that provide their own brand-new functionality (e.g. widgets, dealing with particular file formats), and those that provide integrations with existing software (e.g. scripting languages, clients for REST APIs, implementations of established protocols).


### Integrations

出于本节的目的，“集成”聚焦库执行以下操作之一：

1.充当已建立的Web服务的客户端.
2.以Qt友好的方式包装另一个库，而不仅仅是一个实现细节（即它试图模仿包装的API）.


- [mupdf-qt](https://xiangxw.github.io/mupdf-qt) [:octocat:](https://github.com/xiangxw/mupdf-qt) -  Qt包装 [MuPDF](https://mupdf.com) PDF查看器.
- [neiasound](https://github.com/lucaspcamargo/neiasound) [:octocat:](https://github.com/lucaspcamargo/neiasound) - 为游戏设计的OpenAL包装 [stb_vorbis](https://nothings.org/stb_vorbis) 和 [libsndfile](http://www.mega-nerd.com/libsndfile) 支持.
- [PythonQt](http://pythonqt.sourcef要么ge.net) [:package:](https://sourcef要么ge.net/projects/pythonqt)   - 使用Python编写Qt应用程序脚本.  不要混淆 [PyQt](https://riverbankcomputing.com/software/pyqt) 要么 [PySide](https://wiki.qt.io/PySide).
- [QScintilla](https://riverbankcomputing.com/software/qscintilla) [:package:](https://www.riverbankcomputing.com/software/qscintilla/download)   - 荒谬的多功能和可自定义的文本编辑器小部件，提供语法高亮，代码完成，代码折叠，可记录宏，以及*更多*.  周围建造 [Scintilla](http://www.scintilla.org) .  由开发的同一家公司创建 [PyQt](https://riverbankcomputing.com/software/pyqt).
- [QtAwesome](https://github.com/gamecreature/QtAwesome) [:octocat:](https://github.com/gamecreature/QtAwesome) - 添加 [Font Awesome](https://fortawesome.github.io/Font-Awesome)  Qt应用程序的图标.  其他图标集也受支持.
- [QtLua](http://www.nongnu.org/libqtlua) [:package:](https://svn.savannah.nongnu.org/viewvc/?root=libqtlua) - 使用Lua作为基于Qt的软件的脚本语言.
- [qtruby](https://github.com/cybercatalyst/qtruby) [:octocat:](https://github.com/cybercatalyst/qtruby) - 在您的应用程序中使用Ruby作为脚本语言.
- [QuaZIP](http://quazip.sourceforge.net) [:package:](https://sourceforge.net/projects/quazip)   - 读取和写入ZIP存档.  用途 [Minizip](http://www.winimage.com/zLibDll/minizip.html) 引擎盖下.
- [VLC-Qt](https://vlc-qt.tano.si) [:octocat:](https://github.com/vlc-qt/vlc-qt) - 包装纸 [libvlc](https://wiki.videolan.org/LibVLC) 这使您可以在应用程序中添加类似VLC的媒体播放器.

### New Functionality

- [Communi](https://communi.github.io) [:octocat:](https://github.com/communi/libcommuni)   - 跨平台IRC框架.  我们已经有足够的IRC客户端，但我想这也可用于在您的应用程序中实现聊天功能（例如，用于社区支持）.
- [cutelyst](http://cutelyst.org) [:octocat:](https://github.com/cutelyst/cutelyst) - 从Perl的Catalyst框架中获取一些想法的Web框架.
- [DiceParser](https://github.com/Rolisteam/DiceParser) [:octocat:](https://github.com/Rolisteam/DiceParser) -  Dice Roller框架基于自己的语法. 
- [DOtherSide](https://github.com/filcuc/DOtherSide) [:octocat:](https://github.com/filcuc/DOtherSide) - 在C中绑定QML，主要设计为*其他*语言的API以支持QML.
- [Felgo](https://felgo.com)   - 跨平台的游戏引擎和应用程序框架，严重依赖于QML.  有很多工具和资源，甚至可能值得拥有自己的列表.
- [glraw](https://github.com/cginternals/glraw) [:octocat:](https://github.com/cginternals/glraw)   - 将图像从任何Qt支持的格式转换为OpenGL格式纹理.  用于加速图形应用程序中的纹理加载.
- [grantlee](https://github.com/steveire/grantlee) [:octocat:](https://github.com/steveire/grantlee) -  Django启发的文本模板.
- [injeqt](https://github.com/vogel/injeqt) [:octocat:](https://github.com/vogel/injeqt) -  Qt的依赖注入.
- [KDE Frameworks](https://api.kde.org/frameworks) [:octocat:](https://github.com/KDE) [:package:](https://quickgit.kde.org)   - 针对KDE的度量标准库，但其中许多库也可用于常规Qt应用程序.  跨平台，大部分.
- [Marble](https://marble.kde.org) [:package:](https://cgit.kde.org/marble.git) - 虚拟地球和地图，可以单独使用或嵌入其他应用程序中.
- [qgexedit2](https://github.com/Simsys/qhexedit2) [:octocat:](https://github.com/Simsys/qhexedit2) - 在您的应用程序中嵌入十六进制编辑器.
- [qml-material](https://github.com/papyros/qml-material) [:octocat:](https://github.com/papyros/qml-material) - 用QML实现的Material Design.
- [QNodeView](https://github.com/gwihlidal/QNodeView) [:octocat:](https://github.com/gwihlidal/QNodeView) - 小部件，允许您在图形中创建和编辑节点，类似于虚幻引擎，物质设计器或PureData提供的类型.
- [QSimpleUpdater](https://github.com/alex-spataru/QSimpleUpdater) [:octocat:](https://github.com/alex-spataru/QSimpleUpdater) - 让您的应用程序自行更新.
- [qt-maybe](https://github.com/robertknight/qt-maybe) [:octocat:](https://github.com/robertknight/qt-maybe) - 类型理论的粉丝将享受这些总和和可选类型.
- [qt-mustache](https://github.com/robertknight/qt-mustache) [:octocat:](https://github.com/robertknight/qt-mustache) - 渲染 [Mustache](https://mustache.github.io) 模板.
- [QtAV](http://www.qtav.org) [:octocat:](https://github.com/wang-bin/QtAV) - 积极开发多媒体框架.
- [Qtilities](https://jpnaude.github.io/Qtilities) [:octocat:](https://github.com/JPNaude/Qtilities) - 功能强大的库集，为您的应用程序提供GUI，日志记录，测试，配置和项目功能（以及其他功能）.
- [QtitanChart](http://www.devmachines.com/qtitanchart-overview)   - 图表生成框架.  商业.
- [QtitanRibbon](http://www.devmachines.com/qtitanribbon-overview)   - 适用于Microsoft在其软件中使用的色带的粉丝.  商业.
- [qtnotify](https://github.com/cybercatalyst/qtnotify) [:octocat:](https://github.com/cybercatalyst/qtnotify) - 通知框架.
- [QtTerminalWidget](https://github.com/cybercatalyst/qtterminalwidget) [:octocat:](https://github.com/cybercatalyst/qtterminalwidget) - 使您的应用程序能够**任何**.
- [QtVerbalExpressions](https://github.com/VerbalExpressions/QtVerbalExpressions) [:octocat:](https://github.com/VerbalExpressions/QtVerbalExpressions)   - 使用自然英语表达式创建正则表达式.  的一部分 [VerbalExpressions](https://verbalexpressions.github.io) 项目，它为各种语言做同样的事情.
- [qtwebserver](https://github.com/cybercatalyst/qtwebserver) [:octocat:](https://github.com/cybercatalyst/qtwebserver) - 如果由于某种原因需要在Qt中编写Web应用程序服务器，这将对您有所帮助.
- [QtXlsx](http://qtxlsx.debao.me) [:octocat:](https://github.com/dbzhang800/QtXlsxWriter) - 以Microsoft Excel格式读写电子表格.
- [Qwt](http://qwt.sourceforge.net) [:package:](https://sourceforge.net/projects/qwt) - 为科学和技术应用设计的Qt小部件.
- [verdigris](https://github.com/woboq/verdigris) [:octocat:](https://github.com/woboq/verdigris) - 使用`moc`编写Qt应用程序*而不使用*的实验库.

## Software Repositories

如果 [Libraries](#libraries) 部分不满足你，也许其中一个会.

- [#inqlude](https://inqlude.org)   - 那里最着名的以Qt为中心的图书馆聚合.  包管理器也可用 [here](https://inqlude.org/get.html).
- [QtPods](https://github.com/qt-pods/qt-pods)   - 另一个以Qt为中心的包管理器.  如果您想在不使用QtPods的情况下查看产品，可以使用完整列表 [here](https://github.com/qt-pods/qt-pods-master/blob/master/pods.json)，可以通过提交拉取请求来添加.
- [Linux-Apps.com](https://www.linux-apps.com) - 尽管名称如此，Linux-Apps.com为最终用户和开发人员聚合了各种基于Qt的工具和库.
- [Stephan Binner's Ubuntu PPAs](https://launchpad.net/~beineri)   - 犹豫不决的用户如果在包管理器之外安装任何东西，可以从这些存储库中获取任何最新版本的Qt.  在其中找到添加它们的说明.

## Blogs

每个条目后面都有一个突出的文章，会谈或其他资源列表.

- [Planet Qt](https://planet.qt.io) - 第一方和第三方Qt相关博客的官方汇总.
- [ICS](https://www.ics.com/blog)   - 以Qt为中心的软件咨询公司，拥有一个非常巧妙的博客.  擅长图形应用.
  -  Qt提示和技巧 [[1](https://www.ics.com/blog/qt-tips-and-tricks-part-1), [2](https://www.ics.com/blog/qt-tips-and-tricks-part-2)]  - 可能很好的保留在你的后袋中的赔率和结束.
  - [Mastering Qt File Selectors](https://www.ics.com/blog/mastering-qt-file-selectors)   - 有时您需要同一资产的不同变体，但在运行时之前您不会知道要加载哪些变体.  本课程将由您决定.
  - 一些鲜为人知的Qt工具和命令 [[1](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-1), [2](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-2), [3](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-3), [4](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-4), [5](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-5)]  - 你不会在人迹罕至的地方找到隐藏的宝石.
  - [Using Self-Signed Certificates in Qt Code](https://www.ics.com/blog/using-self-signed-certificates-qt-code) - 谁也不信任.
  - [Integrating C++ with QML](https://www.ics.com/blog/integrating-c-qml)   - 与您的脚本语言交谈.  这就是它的用途.
  -  Qt和OpenGL：使用开放资产导入库加载3D模型（Assimp） [[1](https://www.ics.com/blog/qt-and-opengl-loading-3d-model-open-asset-import-library-assimp), [2](https://www.ics.com/blog/qt-and-opengl-loading-3d-model-open-asset-import-library-assimp-part-2) ]  -  Assimp支持许多不同的模型类型;  这些文章将帮助您支持所有这些.
  - [What's new in Qt 5: QStandardPaths](https://www.ics.com/blog/whats-new-qt-5-qstandardpaths) - 这个功能已经存在了几年，但它仍然有用，足以保证在此列表中输入.
  - [What's New in Qt 5.2: QCommandLineParser](https://www.ics.com/blog/whats-new-qt-52-qcommandlineparser) - 另一个老人，但还是个好人.
- [Woboq](https://woboq.com/blog)   - 另一家软件咨询公司也为Qt提供代码.  他们似乎专注于Qt的核心架构.
  - [Moc myths debunked](https://woboq.com/blog/moc-myths.html)   -  Qt似乎依赖的魔力实际上只是一堆代码生成器.  这篇文章将带你快速了解最着名的“moc”的现实.
  -  Qt信号和插槽如何工作 [[1](https://woboq.com/blog/how-qt-signals-slots-work.html), [2](https://woboq.com/blog/how-qt-signals-slots-work-part2-qt5.html), [3](https://woboq.com/blog/how-qt-signals-slots-work-part3-queuedconnection.html) ]  -  Qt的信号/插槽系统允许任何对象与任何其他对象通信.  理解这三篇文章将有助于您充分利用该功能.
  - [QMetaType knows your types](https://woboq.com/blog/qmetatype-knows-your-types.html) -  C ++不具备良好的运行时类型信息，因此Qt带来了自己的.
  - [C++11 in Qt5](https://woboq.com/blog/cpp11-in-qt5.html)   - 停止编写类似2003年的C ++;  了解如何利用Qt应用程序中的最新C ++功能.
  - [C++14 for Qt programmers](https://woboq.com/blog/cpp14-in-qt.html) - `s / 2003/2011 /`
  - [QStringLiteral explained](https://woboq.com/blog/qstringliteral.html)   - 字符串文字广泛用于许多应用程序;  如果你能让它们更快地访问，那不是很好吗？
  - [Nicer debug output in Qt using QT_MESSAGE_PATTERN](https://woboq.com/blog/nice-debug-output-with-qt.html) - 能够读取应用程序的日志非常好.
- [KDAB](https://www.kdab.com/category/blogs) -  *另一家专门研究Qt的咨询公司.
  - [GammaRay: Taking a deep look into your Qt application](https://www.youtube.com/watch?v=JcoFk_PVhdk) - 谈论 [GammaRay](https://www.kdab.com/development-resources/qt-tools/gammaray)  以及它如何帮助您剖析您的Qt应用程序.  2016年QtCon上的演讲 [Volker Krause](https://github.com/vkrause).
  - [Multithreading with Qt](https://www.youtube.com/watch?v=dcSsjxhazu0)   - 我想让我的应用程序一次做多次.  什么可能出错？  2016年QtCon上的演讲 [Giuseppe D'Angelo](https://github.com/dangelog).
  - [Linux perf for Qt developers](https://www.youtube.com/watch?v=L4NClVxqdMw)   - 如何使您的Qt应用程序更快，Linux风格.  2016年QtCon上的演讲 [Milian Wolff](https://github.com/milianw).

## Books

- [Qt5 C++ GUI Programming Cookbook](https://www.packtpub.com/application-development/qt5-c-gui-programming-cookbook)，通过 [Lee Zhi Eng](https://www.zhieng.com) [:octocat:](https://github.com/PacktPublishing/Qt5-C-GUI-Programming-Cookbook)   - 为熟悉（但不满意）基础知识的人员提供高级GUI编程技术概述.  本书中使用的源代码是免费提供的.
- [Game Programming Using Qt: Beginner's Guide](https://www.packtpub.com/game-development/game-programming-using-qt) 作者：Witold Wysota和Lorenz Haas  - 开始学习如何使用QML编写游戏的好地方.
- [Application Development with Qt Creator - 2nd Edition](https://www.packtpub.com/application-development/application-development-qt-creator-second-edition)，通过 [Ray Rischpater](http://www.lothlorien.com/kf6gpe) -  Qt初学者指南，重点关注Qt Creator及其相关工具.
- [Qt 5 Blueprints](https://www.packtpub.com/application-development/qt-5-blueprints)，通过 [Symeon Huang](https://github.com/librehat) - 似乎是关于Qt项目的整体结构.
- [Mastering Qt 5](https://www.packtpub.com/application-development/mastering-qt-5)，通过 [Guillaume Lazar](https://github.com/GuillaumeLazar) 和 [Robin Penea](https://github.com/synapticvoid) [:octocat:](https://github.com/PacktPublishing/Mastering-Qt-5) - Not your daddy's Qt.  Tips 和 tricks for the experienced.  The source code used in the book is available for free.
- [PySide GUI Application Development - 2nd Edition](https://www.packtpub.com/application-development/pyside-gui-application-development-second-edition)，Gopinath Jaganmohan和Venkateshwaran Loganathan  - 想象一下这些其他书籍，但是用Python.
- [Qt5 Cadaques](https://qmlbook.github.io) [:octocat:](https://github.com/qmlbook/qmlbook) - 专注于QML的免费书籍，以西班牙东北部的这个城镇命名，作者度假一次.

## Software that Uses Qt

 框架只与使用它的软件一样好.  幸运的是，很多很棒的软件都使用Qt.

- [Autodesk Maya](http://www.autodesk.com/maya) -  3D动画和设计软件，用于为有史以来最流行的电影和电视节目创建视觉效果.
- [CMake](https://cmake.org) [:octocat:](https://github.com/Kitware/CMake)   - 最接近标准C ++构建系统的东西.  捆绑的GUI使用Qt.
- [CRYENGINE](https://www.cryengine.com) [:octocat:](https://github.com/CRYTEK-CRYENGINE/CRYENGINE)   - 但它可以运行孤岛危机吗？  一些辅助工具使用Qt.
- [Doxygen](https://www.stack.nl/~dimitri/doxygen) [:octocat:](https://github.com/doxygen/doxygen)   - 最受欢迎的C ++文档生成器，但它也支持其他语言.  捆绑的GUI使用Qt.
- [Google Earth](https://www.google.com/earth) -  *虚拟地球仪.
- [KDE](https://www.kde.org) [:octocat:](https://github.com/KDE) -  Linux最流行的桌面环境之一.
- [Malwarebytes](https://www.malwarebytes.com) - 您的Windows桌面的个人保镖.
- [Parallels Desktop](https://www.parallels.com/products/desktop) - 以消费者为中心的虚拟化
- [Qt Creator](https://www.qt.io/ide) [:octocat:](https://github.com/qtproject/qt-creator)   - 吃东西吃狗粮的东西.  在上市 [official tools](#official-tools)，但不在这里列出它感觉不对.
- [Rolisteam](http://www.rolisteam.org) [:octocat:](https://github.com/Rolisteam/rolisteam) - 用于远程角色扮演游戏的虚拟桌面.
- [RUBE](https://www.iforce2d.net/rube) - 任何使用Box2D物理引擎的游戏的关卡设计工具。
- [TeamSpeak](https://www.teamspeak.com) - 当游戏玩家希望在不支持游戏的游戏中进行语音聊天时，他们会使用此功能.
- [Telegram Desktop](https://desktop.telegram.org) [:octocat:](https://github.com/telegramdesktop/tdesktop)   - 保证你的谈话得好，你会提高潜在窃听者的血压.  桌面客户端使用Qt并且是开源的.
- [Tiled](http://www.mapeditor.org) [:octocat:](https://github.com/bjorn/tiled)   - 也许是世界上最受欢迎的tilemap编辑器.  适合游戏中的关卡设计.
- [VirtualBox](https://www.virtualbox.org) [:package:](https://www.virtualbox.org/browser/vbox/trunk)   - 适用于x86 / 64处理器的虚拟化软件.  捆绑的GUI使用Qt.
- [VLC](https://www.videolan.org/vlc) [:package:](https://code.videolan.org) - 现存最灵活的开源视频播放器之一.
- [Vuo](https://vuo.org) [:octocat:](https://github.com/vuo/vuo) - 用于交互式媒体的实时可视化编程语言.
- [Wireshark](https://www.wireshark.org) [:package:](https://code.wireshark.org/review/gitweb?p=wireshark.git;a=tree)   - 那里最流行的数据包嗅探器.  你*将*用于善而不是邪恶，对吧？
- [Wolfram Mathematica](https://www.wolfram.com/mathematica) - 编程语言，符号计算器和工程师最好的朋友.
- [Yabause](https://yabause.org) [:octocat:](https://github.com/Yabause/yabause) - 现在是土星模拟器.

还有一个官方陈列室 [here](https://showroom.qt.io)，让开发人员提交自己的Qt驱动的应用程序进行显示.

## Other Relevant Awesome Lists

 如果您熟悉Awesome，您就会知道有非常多种资源，其实用性取决于您的项目.  但是，如果您正在开发Qt应用程序，那么您几乎肯定也想要查看这些应用程序.

- [Awesome C/C++](https://github.com/fffaraz/awesome-cpp)   - 没有理由不能使用不是为Qt设计的C ++库.  有时它们甚至可能比Qt提供的更好地满足您的需求.
- [Awesome C](https://github.com/aleksandar-todorovic/awesome-c)   -  C库也是如此;  当你在这里时，他们可能想要了解那些RAII技术.
- [Awesome CMake](https://github.com/onqtam/awesome-cmake) - 如果你没有为你的项目使用qmake，你很可能会使用CMake.
- [Awesome OpenGL](https://github.com/eug/awesome-opengl) -  Qt通常用于图形应用程序，甚至提供自己的OpenGL包装器.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内， [Jesse Talavera-Greenberg](https://jessetg.github.io)  已放弃对此作品的所有版权及相关或相邻权利.  见 [https://github.com/JesseTG/awesome-qt/blob/master/LICENSE](https://github.com/JesseTG/awesome-qt/blob/master/LICENSE) 文件了解详情.
