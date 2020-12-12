<div class="github-widget" data-repo="JesseTG/awesome-qt"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Qt  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cdn.rawgit.com/JesseTG/awesome-qt/ef9f71a9/qt.svg" align="right" width="100">](https://www.qt.io)

&gt;精选的Qt框架工具，库和资源列表.

[Qt](https://www.qt.io) 是一个功能强大的跨平台应用程序开发框架，主要（但不是专门）在C ++中使用. 这对GUI应用程序非常有用，但也可以用于许多其他事情.

欢迎捐款！

## Conventions

 -任何带有OctoCat的列表项：octocat：具有GitHub存储库或组织； 点击它查看源代码！
-列出带有：package：图标的项目的源代码托管在其他位置.



## Official Resources

- [Official Website](https://www.qt.io) -Qt框架的官方网站.
- [Qt Documentation](https://doc.qt.io)  -官方Qt文档. 大规模而全面.
- [Qt Newsletters](https://www.qt.io/newsletters) -最好的Qt，直接进入您的垃圾邮件过滤器.
- [Qt Bug Tracker](https://bugreports.qt.io) -如果您认为已发现Qt或其相关项目之一的错误，请在此处报告（或查看是否有人已经存在）.
- [Qt Code Review](https://codereview.qt-project.org) -了解Qt维护人员如何确保其代码编写正确.
- [Source Code](https://code.qt.io)  -浏览构成Qt项目的各种源代码树. 在几个GitHub组织中都有镜像：
  -Qt [:octocat:](https://github.com/qt)
  -Qt项目 [:octocat:](https://github.com/qtproject)
  -Qt Labs [:octocat:](https://github.com/qt-labs)

## Communities

如果你盖了，他们会来的. 本节描述了彼此共享知识和代码的Qt用户的聚集. 本部分列出了最受欢迎和最活跃的社区，但是您可以找到更全面的列表 [here](https://wiki.qt.io/Online_Communities) （包括其他几种语言）（如果需要）.

### Official

- [Mailing Lists](http://lists.qt-project.org)  -面向Qt用户和开发人员的邮件列表. 可以说是直接与Qt维护人员沟通的最佳场所. 看到频繁的活动.
- [Qt Forum](https://forum.qt.io) -如果您不喜欢电子邮件，那么您也可以考虑在论坛上寻求帮助或分享知识.
- [Qt Wiki](https://wiki.qt.io) -用户贡献的Qt知识的主要来源.
- [IRC](https://webchat.freenode.net/?channels=%23qt%2C%23qt-quick%2C%23qt-creator%2C%23qt-chat) - For real-time chat with other Qt developers and users.  The most popular channels are on Freenode, and include `#qt`, `#qt-quick`, `#qt-creator`, and `#qt-chat`.
  -有关与Qt相关的IRC频道的完整列表，请参见 [here](https://wiki.qt.io/Online_Communities#IRC_channels).
   -请注意，链接的网络聊天客户端不是Qt项目的一部分，该列表的作者仅出于方便起见而提供该链接. 可以通过任何IRC客户端访问这些频道.

### Unofficial

- [QtForum.org](http://www.qtforum.org) -不要与官员混淆 [Qt forum](https://forum.qt.io).


## Tools

优秀的开发人员会编写自己的工具. 一个伟大的人使用别人写的工具. 本节将对您有所帮助； 更正式地，本节详细介绍了使使用Qt创建软件更加容易的应用程序. 您可能也对 [Libraries](#libraries) 部分.

### Official Tools

令人惊讶的是，Qt框架有许多没有引起人们关注的工具. 本节介绍了他们（以及这样做的明星球员）. 在本节中，“工具”指的是以Qt为中心的实用程序，这些程序的代码*未**嵌入您的应用程序中（但它们的输出可能）.

- [Qt Creator](https://www.qt.io/ide) [:octocat:](https://github.com/qtproject/qt-creator)  -Qt绝不会将您锁定在其提供的IDE中，但它与框架的牢固集成使其很受欢迎. 此外，它提供了UI设计器，建模工具，文档浏览器以及对QML的大力支持（如果您喜欢的话）. 还有一个插件系统，但是不幸的是第三方插件很少.
  - [Qt Designer](https://doc.qt.io/qt-5/qtdesigner-manual.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/designer) -如果您只想设计接口并让其他人将其连接到逻辑上，则GUI设计器可作为单独的应用程序使用.
  - [Qt Assistant](https://doc.qt.io/qt-5/qtassistant-index.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/assistant) -就此而言，文档查看器也是如此.
- [Qt Visual Studio Add-in](https://doc.qt.io/archives/vs-addin) [:octocat:](https://github.com/qt-labs/vstools) -如果您希望使用Visual Studio，则可以使用此加载项.
- [Qt Linguist](https://doc.qt.io/qt-5/qtlinguist-index.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/linguist) - Qt provides excellent internationalization/localization support, and this tool is very much responsible for it.  Write translatable strings in your code with special macros, and this tool will aggregate them all for you so you or your translator(s) can broaden your software's audience.
- [Qt Installer Framework](https://doc.qt.io/qtinstallerframework) [:octocat:](https://github.com/qtproject/installer-framework)  -似乎没有人谈论这件事，但是Qt还提供了一种为应用程序编写安装程序的方法. 不支持创建macOS磁盘映像，应用程序捆绑包或Linux软件包，因此在考虑项目的分发时请注意这一点.
  - [`macdeployqt`](https://doc.qt.io/qt-5/osx-deployment.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/macdeployqt) -为Qt项目生成macOS应用程序捆绑包.
- [qmake](https://doc.qt.io/qt-5/qmake-manual.html) [:octocat:](https://github.com/qt/qtbase/tree/dev/qmake) -专为Qt设计的捆绑式构建系统，尽管它可以用于非Qt项目.
- [qbs](https://doc.qt.io/qbs) [:octocat:](https://github.com/qt-labs/qbs) -如果QML更适合您的风格，请考虑使用此替代构建系统.
- [Emulator](https://doc.qt.io/emulator) -不要忘记Qt的移动支持！
-`qtdiag` [:octocat:](https://github.com/qt/qttools/tree/dev/src/qtdiag)  -命令行工具，可打印出许多有关Qt安装和一般系统的信息. 没有链接，因为没有专用的网页； 只需在命令行上运行qtdiag即可. 非常适合进行故障排除.
-`qmleasing` [:octocat:](https://github.com/qt/qtdeclarative/tree/dev/tools/qmleasing) -让您制作适合QML的缓和曲线，尽管如果您了解基本数学原理，则没有理由不能在其他地方使用结果数字.

### Third-Party Tools

- [CMake](https://doc.qt.io/qt-5/cmake-manual.html) [:octocat:](https://github.com/Kitware/CMake) -一般的C ++构建工具，恰好具有出色的Qt支持.
- [GammaRay](https://www.kdab.com/development-resources/qt-tools/gammaray) [:octocat:](https://github.com/KDAB/GammaRay)  -用于Qt内置软件的强大调试器和常规检查工具. 使您可以检查和操作`QObject`层次结构，查看对象属性，在运行时编辑窗口小部件以及更多（远*更多）的内容. 两句简短的句子不能公平对待，请认真检查一下.
- [moc-ng](https://github.com/woboq/moc-ng) [:octocat:](https://github.com/woboq/moc-ng) -与Qt版本二进制兼容的`moc`的替代实现.
- [Qt-Inspector](https://github.com/robertknight/Qt-Inspector) [:octocat:](https://github.com/robertknight/Qt-Inspector) -具有与GammaRay相似的目标的检查工具，但简单得多.
- [SIP](https://www.riverbankcomputing.com/software/sip) [:package:](https://www.riverbankcomputing.com/hg/sip)  -为C或C ++库生成Python绑定. 对Qt信号和插槽具有特殊支持，并用于创建 [PyQt](https://riverbankcomputing.com/software/pyqt).
- [linuxdeployqt](https://github.com/probonopd/linuxdeployqt) [:octocat:](https://github.com/probonopd/linuxdeployqt) -使您可以将基于Qt的应用程序捆绑为AppDir或 [AppImage](http://appimage.org) ，从而可以将其交付给许多桌面Linux发行版的用户. 与官方的`windeployqt`和`macdeployqt`工具类似，但适用于Linux.
- [Qompoter](https://github.com/Fylhan/qompoter) -Qt / C ++的依赖管理器.

## Bindings in Other Languages

本节介绍了可以使用除C ++之外的主要语言创建Qt软件的软件. 在Qt应用程序中允许运行时脚本编写的库在下面列出 [Integrations](#integrations).

- [Python (via PyQt)](https://riverbankcomputing.com/software/pyqt) [:package:](https://www.riverbankcomputing.com/software/pyqt/download5) - Arguably the most comprehensive and well-known binding of Qt to another language.
- [Python (via PySide)](https://wiki.qt.io/PySide) [:package:](https://code.qt.io/cgit/pyside/pyside.git) -另一个Python绑定，已由Qt项目正式采用.
- [Ring (via RingQt)](http://ring-lang.sourceforge.net/doc/qt.html) [:octocat:](https://github.com/ring-lang/ring/tree/master/extensions/ringqt) -老实说，我也从未听说过这种语言.
- [Mono/.NET languages (via QtSharp)](https://github.com/ddobrev/QtSharp) [:octocat:](https://github.com/ddobrev/QtSharp) - Experimental wrapper for Qt that allows it to be used by .NET-based languages such as C#.  Young, but active.

看这些 [these](https://www.ics.com/blog/using-qt-alternative-programming-languages-part-1) [three](https://www.ics.com/blog/using-qt-alternative-programming-languages-part-2) [articles](https://wiki.qt.io/Category:LanguageBindings) 如果您想要更多.

## Libraries

This section describes two kinds of third-party libraries; those that provide their own brand-new functionality (e.g. widgets, dealing with particular file formats), and those that provide integrations with existing software (e.g. scripting languages, clients for REST APIs, implementations of established protocols).


### Integrations

就本节而言，以“集成”为重点的库执行以下操作之一：

1.充当已建立的Web服务的客户端.
2.以一种Qt友好的方式包装另一个库，而不仅仅是实现细节（即，它试图模仿包装的API）.


- [mupdf-qt](https://xiangxw.github.io/mupdf-qt) [:octocat:](https://github.com/xiangxw/mupdf-qt) -Qt包装器 [MuPDF](https://mupdf.com) PDF查看器.
- [neiasound](https://github.com/lucaspcamargo/neiasound) [:octocat:](https://github.com/lucaspcamargo/neiasound) -专为游戏设计的OpenAL包装，具有 [stb_vorbis](https://nothings.org/stb_vorbis) 和 [libsndfile](http://www.mega-nerd.com/libsndfile) 支持.
- [PythonQt](http://pythonqt.sourcef要么ge.net) [:package:](https://sourcef要么ge.net/projects/pythonqt)  -使用Python编写Qt应用程序脚本. 不要与 [PyQt](https://riverbankcomputing.com/software/pyqt) 要么 [PySide](https://wiki.qt.io/PySide).
- [QScintilla](https://riverbankcomputing.com/software/qscintilla) [:package:](https://www.riverbankcomputing.com/software/qscintilla/download)  -荒谬的通用性和可自定义的文本编辑器小部件，提供了语法突出显示，代码完成，代码折叠，可记录的宏以及更多*的功能. 建于 [Scintilla](http://www.scintilla.org) . 由同一家公司开发 [PyQt](https://riverbankcomputing.com/software/pyqt).
- [QtAwesome](https://github.com/gamecreature/QtAwesome) [:octocat:](https://github.com/gamecreature/QtAwesome) -添加 [Font Awesome](https://fortawesome.github.io/Font-Awesome)  Qt应用程序的图标. 也支持其他图标集.
- [QtLua](http://www.nongnu.org/libqtlua) [:package:](https://svn.savannah.nongnu.org/viewvc/?root=libqtlua) -将Lua用作基于Qt的软件的脚本语言.
- [qtruby](https://github.com/cybercatalyst/qtruby) [:octocat:](https://github.com/cybercatalyst/qtruby) -在应用程序中使用Ruby作为脚本语言.
- [QuaZIP](http://quazip.sourceforge.net) [:package:](https://sourceforge.net/projects/quazip)  -从ZIP档案读取和写入. 用途 [Minizip](http://www.winimage.com/zLibDll/minizip.html) 在引擎盖下.
- [VLC-Qt](https://vlc-qt.tano.si) [:octocat:](https://github.com/vlc-qt/vlc-qt) -包装 [libvlc](https://wiki.videolan.org/LibVLC) 使您可以向应用程序中添加类似VLC的媒体播放器.

### New Functionality

- [Communi](https://communi.github.io) [:octocat:](https://github.com/communi/libcommuni)  -跨平台的IRC框架. 我们已经有足够的IRC客户端了，但是我想这也可以用于在您的应用程序中实现聊天功能（例如，为社区提供支持）.
- [cutelyst](http://cutelyst.org) [:octocat:](https://github.com/cutelyst/cutelyst) -从Perl的Catalyst框架吸收一些想法的Web框架.
- [DiceParser](https://github.com/Rolisteam/DiceParser) [:octocat:](https://github.com/Rolisteam/DiceParser) -Dice Roller框架基于其自身的语法. 
- [DOtherSide](https://github.com/filcuc/DOtherSide) [:octocat:](https://github.com/filcuc/DOtherSide) -在C中对QML进行绑定，主要设计为*其他*语言的API以支持QML.
- [Felgo](https://felgo.com)  -高度依赖QML的跨平台游戏引擎和应用程序框架. 有很多工具和资源，甚至可能值得拥有自己的清单.
- [glraw](https://github.com/cginternals/glraw) [:octocat:](https://github.com/cginternals/glraw)  -将图像从任何Qt支持的格式转换为OpenGL格式的纹理. 对于加快图形应用程序中的纹理加载很有用.
- [grantlee](https://github.com/steveire/grantlee) [:octocat:](https://github.com/steveire/grantlee) -受Django启发的文本模板.
- [injeqt](https://github.com/vogel/injeqt) [:octocat:](https://github.com/vogel/injeqt) -Qt的依赖注入.
- [KDE Frameworks](https://api.kde.org/frameworks) [:octocat:](https://github.com/KDE) [:package:](https://quickgit.kde.org)  -KDE库的度量标准库，但其中许多库也可以与常规Qt应用程序一起使用. 跨平台，大部分.
- [Marble](https://marble.kde.org) [:package:](https://cgit.kde.org/marble.git) -虚拟地球仪和地图，可单独使用或嵌入其他应用程序中.
- [qgexedit2](https://github.com/Simsys/qhexedit2) [:octocat:](https://github.com/Simsys/qhexedit2) -在您的应用程序中嵌入一个十六进制编辑器.
- [qml-material](https://github.com/papyros/qml-material) [:octocat:](https://github.com/papyros/qml-material) -在QML中实施的材料设计.
- [QNodeView](https://github.com/gwihlidal/QNodeView) [:octocat:](https://github.com/gwihlidal/QNodeView) -小工具，可让您在图中创建和编辑节点，类似于虚幻引擎，Substance Designer或PureData提供的那种类型.
- [QSimpleUpdater](https://github.com/alex-spataru/QSimpleUpdater) [:octocat:](https://github.com/alex-spataru/QSimpleUpdater) -让您的应用程序自行更新.
- [qt-maybe](https://github.com/robertknight/qt-maybe) [:octocat:](https://github.com/robertknight/qt-maybe) -类型理论的爱好者将喜欢这些总和和可选类型.
- [qt-mustache](https://github.com/robertknight/qt-mustache) [:octocat:](https://github.com/robertknight/qt-mustache) -渲染 [Mustache](https://mustache.github.io) 模板.
- [QtAV](http://www.qtav.org) [:octocat:](https://github.com/wang-bin/QtAV) -积极开发的多媒体框架.
- [Qtilities](https://jpnaude.github.io/Qtilities) [:octocat:](https://github.com/JPNaude/Qtilities) -功能强大的库集，可为您的应用程序提供GUI，日志记录，测试，配置和项目功能（以及其他功能）.
- [QtitanChart](http://www.devmachines.com/qtitanchart-overview)  -图表生成框架. 商业.
- [QtitanRibbon](http://www.devmachines.com/qtitanribbon-overview)  -对于Microsoft在其软件中使用的功能区的支持者. 商业.
- [qtnotify](https://github.com/cybercatalyst/qtnotify) [:octocat:](https://github.com/cybercatalyst/qtnotify) -通知框架.
- [QtTerminalWidget](https://github.com/cybercatalyst/qtterminalwidget) [:octocat:](https://github.com/cybercatalyst/qtterminalwidget) -使您的应用程序具备“任何功能”.
- [QtVerbalExpressions](https://github.com/VerbalExpressions/QtVerbalExpressions) [:octocat:](https://github.com/VerbalExpressions/QtVerbalExpressions)  -使用自然的英语表达式创建正则表达式. 的一部分 [VerbalExpressions](https://verbalexpressions.github.io) 项目，它针对多种语言执行相同的操作.
- [qtwebserver](https://github.com/cybercatalyst/qtwebserver) [:octocat:](https://github.com/cybercatalyst/qtwebserver) -如果出于某种原因需要用Qt编写Web应用程序服务器，这将对您有所帮助.
- [QtXlsx](http://qtxlsx.debao.me) [:octocat:](https://github.com/dbzhang800/QtXlsxWriter) -读取和写入Microsoft Excel格式的电子表格.
- [Qwt](http://qwt.sourceforge.net) [:package:](https://sourceforge.net/projects/qwt) -专为科学和技术应用而设计的Qt小部件.
- [verdigris](https://github.com/woboq/verdigris) [:octocat:](https://github.com/woboq/verdigris) -实验库，使用moc无需使用*即可编写Qt应用程序.

## Software Repositories

如果 [Libraries](#libraries) 部分不满足您的要求，也许是其中之一.

- [#inqlude](https://inqlude.org)  -最著名的以Qt为中心的库聚合. 包管理器也可用 [here](https://inqlude.org/get.html).
- [QtPods](https://github.com/qt-pods/qt-pods)  -另一个以Qt为中心的软件包管理器. 如果要在不使用QtPods的情况下查看产品，则可以使用完整列表 [here](https://github.com/qt-pods/qt-pods-master/blob/master/pods.json)，并且可以通过提交拉取请求将其添加到.
- [Linux-Apps.com](https://www.linux-apps.com) -尽管名字叫Linux-Apps.com，它为最终用户和开发人员聚集了各种基于Qt的工具和库.
- [Stephan Binner's Ubuntu PPAs](https://launchpad.net/~beineri)  -犹豫不决的软件包管理器之外的用户，可以从这些存储库中获取最新版本的Qt. 在其中找到添加它们的说明.

## Blogs

每个条目后面都有引人注目的文章，演讲或其他资源列表.

- [Planet Qt](https://planet.qt.io) -第一方和第三方Qt相关博客的官方汇总.
- [ICS](https://www.ics.com/blog)  -以Qt为中心的软件咨询公司，拥有一个非常整洁的博客. 专门从事图形应用程序.
  -Qt技巧和窍门 [[1](https://www.ics.com/blog/qt-tips-and-tricks-part-1), [2](https://www.ics.com/blog/qt-tips-and-tricks-part-2)]-奇特的东西可能会留在后腰.
  - [Mastering Qt File Selectors](https://www.ics.com/blog/mastering-qt-file-selectors)  -有时您需要同一资产的不同变体，但直到运行时才知道要加载哪些变体. 本课程将为您决定.
  -一些鲜为人知的Qt工具和命令 [[1](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-1), [2](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-2), [3](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-3), [4](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-4), [5](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-5)]-您不会因为人迹罕至而找不到隐藏的宝石.
  - [Using Self-Signed Certificates in Qt Code](https://www.ics.com/blog/using-self-signed-certificates-qt-code) - 谁也不要相信.
  - [Integrating C++ with QML](https://www.ics.com/blog/integrating-c-qml)  -与您的脚本语言交谈. 那就是它的目的.
  -Qt和OpenGL：使用开放资产导入库（Assimp）加载3D模型 [[1](https://www.ics.com/blog/qt-and-opengl-loading-3d-model-open-asset-import-library-assimp), [2](https://www.ics.com/blog/qt-and-opengl-loading-3d-model-open-asset-import-library-assimp-part-2) ]-Assimp支持许多不同的模型类型； 这些文章将帮助您支持所有这些文章.
  - [What's new in Qt 5: QStandardPaths](https://www.ics.com/blog/whats-new-qt-5-qstandardpaths) -此功能已经存在了几年，但是它仍然足够有用，可以保证在此列表中有一个条目.
  - [What's New in Qt 5.2: QCommandLineParser](https://www.ics.com/blog/whats-new-qt-52-qcommandlineparser) -另一个老歌，但仍然是好东西.
- [Woboq](https://woboq.com/blog)  -另一家也向Qt提供代码的软件咨询公司. 他们似乎专门研究Qt的核心架构.
  - [Moc myths debunked](https://woboq.com/blog/moc-myths.html)  -Qt似乎依赖的魔术实际上只是一堆代码生成器. 这篇文章将带您快速了解最著名的`moc`的现实.
  -Qt信号和插槽如何工作 [[1](https://woboq.com/blog/how-qt-signals-slots-work.html), [2](https://woboq.com/blog/how-qt-signals-slots-work-part2-qt5.html), [3](https://woboq.com/blog/how-qt-signals-slots-work-part3-queuedconnection.html) ]-Qt的信号/插槽系统允许任何对象与任何其他对象通话. 了解这三篇文章将帮助您充分利用该功能.
  - [QMetaType knows your types](https://woboq.com/blog/qmetatype-knows-your-types.html) -C ++不具有良好的运行时类型信息，因此Qt拥有自己的信息.
  - [C++11 in Qt5](https://woboq.com/blog/cpp11-in-qt5.html)  -不再像2003年那样编写C ++； 了解如何在Qt应用程序中利用最新的C ++功能.
  - [C++14 for Qt programmers](https://woboq.com/blog/cpp14-in-qt.html) -`s / 2003/2011 /`
  - [QStringLiteral explained](https://woboq.com/blog/qstringliteral.html)  -字符串文字广泛用于许多应用程序中； 如果可以让他们更快地访问它们会不会很好？
  - [Nicer debug output in Qt using QT_MESSAGE_PATTERN](https://woboq.com/blog/nice-debug-output-with-qt.html) -很高兴能够读取应用程序的日志.
- [KDAB](https://www.kdab.com/category/blogs) -*另一家*专门从事Qt的咨询公司.
  - [GammaRay: Taking a deep look into your Qt application](https://www.youtube.com/watch?v=JcoFk_PVhdk) - 谈论 [GammaRay](https://www.kdab.com/development-resources/qt-tools/gammaray) 以及它如何帮助您剖析Qt应用程序. 在QtCon 2016上的演讲者 [Volker Krause](https://github.com/vkrause).
  - [Multithreading with Qt](https://www.youtube.com/watch?v=dcSsjxhazu0)  -我想让我的应用程序一次执行多个操作. 可能出什么问题了？ 在QtCon 2016上的演讲者 [Giuseppe D'Angelo](https://github.com/dangelog).
  - [Linux perf for Qt developers](https://www.youtube.com/watch?v=L4NClVxqdMw)  -如何使Linux风格的Qt应用程序更快. 在QtCon 2016上的演讲者 [Milian Wolff](https://github.com/milianw).

## Books

- [Qt5 C++ GUI Programming Cookbook](https://www.packtpub.com/application-development/qt5-c-gui-programming-cookbook)，由 [Lee Zhi Eng](https://www.zhieng.com) [:octocat:](https://github.com/PacktPublishing/Qt5-C-GUI-Programming-Cookbook)  -针对熟悉（但不满意）基础知识的高级GUI编程技术的概述. 本书中使用的源代码是免费的.
- [Game Programming Using Qt: Beginner's Guide](https://www.packtpub.com/game-development/game-programming-using-qt) Witold Wysota和Lorenz Haas撰写-开始学习如何使用QML编程游戏的好地方.
- [Application Development with Qt Creator - 2nd Edition](https://www.packtpub.com/application-development/application-development-qt-creator-second-edition)，由 [Ray Rischpater](http://www.lothlorien.com/kf6gpe) -Qt入门指南，重点是Qt Creator及其相关工具.
- [Qt 5 Blueprints](https://www.packtpub.com/application-development/qt-5-blueprints)，由 [Symeon Huang](https://github.com/librehat) -似乎与Qt项目的总体结构有关.
- [Mastering Qt 5](https://www.packtpub.com/application-development/mastering-qt-5)，由 [Guillaume Lazar](https://github.com/GuillaumeLazar) 和 [Robin Penea](https://github.com/synapticvoid) [:octocat:](https://github.com/PacktPublishing/Mastering-Qt-5) - Not your daddy's Qt.  Tips 和 tricks for the experienced.  The source code used in the book is available for free.
- [PySide GUI Application Development - 2nd Edition](https://www.packtpub.com/application-development/pyside-gui-application-development-second-edition)，由Gopinath Jaganmohan和Venkateshwaran Loganathan撰写-想象这些其他书籍，但使用Python.
- [Qt5 Cadaques](https://qmlbook.github.io) [:octocat:](https://github.com/qmlbook/qmlbook) -专注于QML的免费书籍，以作者在西班牙东北部的这个小镇命名，曾有一次去过.

## Software that Uses Qt

框架仅与使用框架的软件一样好. 幸运的是，许多出色的软件都使用Qt.

- [Autodesk Maya](http://www.autodesk.com/maya) -3D动画和设计软件，一直用于为某些最受欢迎的电影和电视节目创建视觉效果.
- [Davinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/) -具有商业计划的非线性视频编辑免费软件，用于制作一些好莱坞电影.
- [CMake](https://cmake.org) [:octocat:](https://github.com/Kitware/CMake)  -最接近标准C ++构建系统的东西. 捆绑的GUI使用Qt.
- [CRYENGINE](https://www.cryengine.com) [:octocat:](https://github.com/CRYTEK-CRYENGINE/CRYENGINE)  -但是可以运行《孤岛危机》吗？ 一些辅助工具使用Qt.
- [Doxygen](https://www.stack.nl/~dimitri/doxygen) [:octocat:](https://github.com/doxygen/doxygen)  -最受欢迎的C ++文档生成器，尽管它也支持其他语言. 捆绑的GUI使用Qt.
- [Google Earth](https://www.google.com/earth) -*虚拟地球仪.
- [KDE](https://www.kde.org) [:octocat:](https://github.com/KDE) -Linux最受欢迎的桌面环境之一.
- [Malwarebytes](https://www.malwarebytes.com) -Windows桌面的个人保镖.
- [Parallels Desktop](https://www.parallels.com/products/desktop) -以消费者为中心的虚拟化.
- [Qt Creator](https://www.qt.io/ide) [:octocat:](https://github.com/qtproject/qt-creator)  -自己吃狗粮的东西. 列于 [official tools](#official-tools)，但没有在这里列出它感觉不对.
- [Rolisteam](http://www.rolisteam.org) [:octocat:](https://github.com/Rolisteam/rolisteam) -用于远程角色扮演游戏的虚拟桌面.
- [RUBE](https://www.iforce2d.net/rube) -适用于使用Box2D物理引擎的任何游戏的关卡设计工具。
- [TeamSpeak](https://www.teamspeak.com) -当游戏玩家想要在不支持该游戏的游戏中进行语音聊天时，他们将使用此功能.
- [Telegram Desktop](https://desktop.telegram.org) [:octocat:](https://github.com/telegramdesktop/tdesktop)  -很好地确保对话的安全，您会提高潜在窃听者的血压. 桌面客户端使用Qt，并且是开源的.
- [Tiled](http://www.mapeditor.org) [:octocat:](https://github.com/bjorn/tiled)  -也许是世界上最受欢迎的tilemap编辑器. 适用于游戏中的关卡设计.
- [VirtualBox](https://www.virtualbox.org) [:package:](https://www.virtualbox.org/browser/vbox/trunk)  -用于x86 / 64处理器的虚拟化软件. 捆绑的GUI使用Qt.
- [VLC](https://www.videolan.org/vlc) [:package:](https://code.videolan.org) -现有的最灵活的开源视频播放器之一.
- [Vuo](https://vuo.org) [:octocat:](https://github.com/vuo/vuo) —用于交互式媒体的实时视觉编程语言.
- [Wireshark](https://www.wireshark.org) [:package:](https://code.wireshark.org/review/gitweb?p=wireshark.git;a=tree)  -最受欢迎的数据包嗅探器. 您*将*将其用于善良而不是邪恶，对吗？
- [Wolfram Mathematica](https://www.wolfram.com/mathematica) -编程语言，符号计算器和工程师的挚友.
- [Yabause](https://yabause.org) [:octocat:](https://github.com/Yabause/yabause) -现在土星模拟器.

还有一个官方的陈列室 [here](https://showroom.qt.io)，这使开发人员可以提交自己的Qt驱动的应用程序进行显示.

## Other Relevant Awesome Lists

如果您熟悉Awesome，那么您会知道这里的资源种类繁多，其用途将取决于您的项目. 但是，如果您正在开发Qt应用程序，则几乎可以肯定也要研究这些应用程序.

- [Awesome C/C++](https://github.com/fffaraz/awesome-cpp)  -没有理由您不能使用不是为Qt设计的C ++库. 有时它们甚至可能比Qt提供的产品更适合您的需求.
- [Awesome C](https://github.com/aleksandar-todorovic/awesome-c)  -C库也是如此； 在您使用时可能会想复习那些RAII技术.
- [Awesome CMake](https://github.com/onqtam/awesome-cmake) -如果您的项目未使用qmake，则可能使用的是CMake.
- [Awesome OpenGL](https://github.com/eug/awesome-opengl) -Qt通常用于图形应用程序，甚至提供围绕OpenGL的自己的包装器.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内， [Jesse Talavera-Greenberg](https://jessetg.github.io) 放弃了此作品的所有版权以及相关或邻近的权利. 见 [https://github.com/JesseTG/awesome-qt/blob/master/LICENSE](https://github.com/JesseTG/awesome-qt/blob/master/LICENSE) 文件以获取详细信息.
