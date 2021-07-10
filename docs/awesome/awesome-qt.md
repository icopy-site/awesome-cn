<div class="github-widget" data-repo="JesseTG/awesome-qt"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Qt  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cdn.rawgit.com/JesseTG/awesome-qt/ef9f71a9/qt.svg" align="right" width="100">](https://www.qt.io)

&gt; Qt 框架的精选工具、库和资源列表.

[Qt](https://www.qt.io) 是一个功能强大的跨平台应用程序开发框架，主要（但不限于）在 C++ 中使用. 它非常适用于 GUI 应用程序，但也可用于许多其他用途.

欢迎投稿！

## Conventions

 - 任何带有 OctoCat 的列表项 :octocat: 都有一个 GitHub 存储库或组织； 点击它查看源代码！
- 带有此 :package: 图标的列表项目在别处托管了源代码.



## Official Resources

- [Official Website](https://www.qt.io) - Qt 框架的官方网站.
- [Qt Documentation](https://doc.qt.io)  - 官方 Qt 文档. 庞大而全面.
- [Qt Newsletters](https://www.qt.io/newsletters) - 最好的 Qt，直接到您的垃圾邮件过滤器.
- [Qt Bug Tracker](https://bugreports.qt.io) - 如果您认为您发现了 Qt 或其相关项目之一的错误，请在此处报告（或查看其他人是否已经拥有）.
- [Qt Code Review](https://codereview.qt-project.org) - 了解 Qt 维护人员如何确保他们的代码编写良好.
- [Source Code](https://code.qt.io)  - 浏览构成 Qt 项目的各种源代码树. 在几个 GitHub 组织有镜像：
  - Qt [:octocat:](https://github.com/qt)
  - Qt 项目 [:octocat:](https://github.com/qtproject)
  - Qt 实验室 [:octocat:](https://github.com/qt-labs)

## Communities

如果你盖了，他们会来的. 本节描述彼此共享知识和代码的 Qt 用户的聚合. 此部分列出了最受欢迎和最活跃的社区，但您可以找到更全面的列表 [here](https://wiki.qt.io/Online_Communities) （包括其他语言的几种）如果您愿意.

### Official

- [Mailing Lists](http://lists.qt-project.org)  - Qt 用户和开发人员的邮件列表. 可以说是与 Qt 维护人员直接交流的最佳场所. 看到频繁的活动.
- [Qt Forum](https://forum.qt.io) - 如果您不喜欢电子邮件，那么您也可以考虑在论坛上寻求帮助或分享知识.
- [Qt Wiki](https://wiki.qt.io) - 用户贡献的 Qt 知识的主要来源.
- [IRC](https://webchat.freenode.net/?channels=%23qt%2C%23qt-quick%2C%23qt-creator%2C%23qt-chat) - For real-time chat with other Qt developers and users.  The most popular channels are on Freenode, and include `#qt`, `#qt-quick`, `#qt-creator`, and `#qt-chat`.
  - 有关 Qt 相关 IRC 频道的完整列表，请参阅 [here](https://wiki.qt.io/Online_Communities#IRC_channels).
   - 请注意，链接的网络聊天客户端*不*属于 Qt 项目的一部分，由此列表的作者提供只是为了方便. 这些频道可以通过任何 IRC 客户端访问.

### Unofficial

- [QtForum.org](http://www.qtforum.org) - 不要与官方混淆 [Qt forum](https://forum.qt.io).


## Tools

优秀的开发人员会编写自己的工具. 一个伟大的人使用其他人编写的工具. 本节将帮助您变得出色； 更正式地说，本节详细介绍了使用 Qt 更容易创建软件的应用程序. 您可能还对以下内容感兴趣 [Libraries](#libraries) 部分.

### Official Tools

 Qt 框架具有令人惊讶的许多工具，但它们并没有引起人们的注意. 本节描述了他们（以及这样做的明星球员）. 就本节而言，“工具”是指以 Qt 为中心的实用程序，其代码*不会*嵌入到您的应用程序中（但它们的输出可能）.

- [Qt Creator](https://www.qt.io/ide) [:octocat:](https://github.com/qtproject/qt-creator)  - Qt 绝不会将您锁定在其提供的 IDE 中，但它与框架的牢固集成使其畅销. 除此之外，它还提供了 UI 设计器、建模工具、文档浏览器和强大的 QML 支持（如果您对此感兴趣的话）. 还有一个插件系统，但不幸的是第三方插件很少.
  - [Qt Designer](https://doc.qt.io/qt-5/qtdesigner-manual.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/designer) - 如果您只想设计界面并让其他人将它们与逻辑联系起来，则可以将 GUI 设计器作为单独的应用程序使用.
  - [Qt Assistant](https://doc.qt.io/qt-5/qtassistant-index.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/assistant) - 就此而言，文档查看器也是如此.
- [Qt Visual Studio Add-in](https://doc.qt.io/archives/vs-addin) [:octocat:](https://github.com/qt-labs/vstools) - 如果您更愿意坚持使用 Visual Studio，这个插件可以让您做到这一点.
- [Qt Linguist](https://doc.qt.io/qt-5/qtlinguist-index.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/linguist)  - Qt 提供了优秀的国际化/本地化支持，这个工具对此非常负责. 使用特殊的宏在您的代码中编写可翻译的字符串，此工具将为您汇总所有这些字符串，以便您或您的翻译人员可以扩大您的软件的受众.
- [Qt Installer Framework](https://doc.qt.io/qtinstallerframework) [:octocat:](https://github.com/qtproject/installer-framework)  - 似乎没有人谈论这个，但 Qt 还提供了一种为您的应用程序编写安装程序的方法. 不支持创建 macOS 磁盘映像、应用程序包或 Linux 包，因此在考虑项目的分发时请注意这一点.
  - [`macdeployqt`](https://doc.qt.io/qt-5/osx-deployment.html) [:octocat:](https://github.com/qt/qttools/tree/dev/src/macdeployqt) - 为 Qt 项目生成 macOS 应用程序包.
- [qmake](https://doc.qt.io/qt-5/qmake-manual.html) [:octocat:](https://github.com/qt/qtbase/tree/dev/qmake) - 为 Qt 设计的捆绑构建系统，但它可以用于非 Qt 项目.
- [qbs](https://doc.qt.io/qbs) [:octocat:](https://github.com/qt-labs/qbs) - 如果 QML 更符合您的风格，请考虑使用此替代构建系统.
- [Emulator](https://doc.qt.io/emulator) - 不要忘记 Qt 的移动支持！
-`qtdiag` [:octocat:](https://github.com/qt/qttools/tree/dev/src/qtdiag)  - 命令行工具，可打印出与 Qt 安装和系统相关的大量信息. 没有链接，因为没有专门的网页； 只需在命令行上运行 `qtdiag`. 非常适合故障排除.
- `qmleasing` [:octocat:](https://github.com/qt/qtdeclarative/tree/dev/tools/qmleasing) - Lets you make easing curves suitable for QML, though if you understand the underlying math there's no reason you couldn't use the resulting numbers elsewhere.

### Third-Party Tools

- [CMake](https://doc.qt.io/qt-5/cmake-manual.html) [:octocat:](https://github.com/Kitware/CMake) - 碰巧有很好的 Qt 支持的通用 C++ 构建工具.
- [GammaRay](https://www.kdab.com/development-resources/qt-tools/gammaray) [:octocat:](https://github.com/KDAB/GammaRay)  - 强大的调试器和 Qt 内置软件的通用检查工具. 允许您检查和操作 `QObject` 层次结构、查看对象属性、在运行时编辑小部件，等等. 两句话的宣传是不公平的，认真检查一下.
- [moc-ng](https://github.com/woboq/moc-ng) [:octocat:](https://github.com/woboq/moc-ng) - 与 Qt 版本二进制兼容的 `moc` 的替代实现.
- [Qt-Inspector](https://github.com/robertknight/Qt-Inspector) [:octocat:](https://github.com/robertknight/Qt-Inspector) - 具有与 GammaRay 相似目标的检查工具，但要简单得多.
- [SIP](https://www.riverbankcomputing.com/software/sip) [:package:](https://www.riverbankcomputing.com/hg/sip)  - 为 C 或 C++ 库生成 Python 绑定. 对 Qt 信号和槽有特殊支持，并用于创建 [PyQt](https://riverbankcomputing.com/software/pyqt).
- [linuxdeployqt](https://github.com/probonopd/linuxdeployqt) [:octocat:](https://github.com/probonopd/linuxdeployqt) - 允许您将基于 Qt 的应用程序捆绑为 AppDir 或 [AppImage](http://appimage.org) ，使其可以将其发送给许多桌面 Linux 发行版的用户. 类似于官方的 `windeployqt` 和 `macdeployqt` 工具，但适用于 Linux.
- [Qompoter](https://github.com/Fylhan/qompoter) - Qt / C++ 的依赖管理器.

## Bindings in Other Languages

本节描述了能够以 C++ 以外的主要语言创建 Qt 软件的软件. 允许在 Qt 应用程序中编写运行时脚本的库列在下面 [Integrations](#integrations).

- [Python (via PyQt)](https://riverbankcomputing.com/software/pyqt) [:package:](https://www.riverbankcomputing.com/software/pyqt/download5) - 可以说是 Qt 与另一种语言的最全面和最知名的绑定.
- [Python (via PySide)](https://wiki.qt.io/PySide) [:package:](https://code.qt.io/cgit/pyside/pyside.git) - 另一个 Python 绑定，已被 Qt 项目正式采用.
- [Ring (via RingQt)](http://ring-lang.sourceforge.net/doc/qt.html) [:octocat:](https://github.com/ring-lang/ring/tree/master/extensions/ringqt) - 老实说，我也从未听说过这种语言.
- [Mono/.NET languages (via QtSharp)](https://github.com/ddobrev/QtSharp) [:octocat:](https://github.com/ddobrev/QtSharp) - Experimental wrapper for Qt that allows it to be used by .NET-based languages such as C#.  Young, but active.

看到这些 [these](https://www.ics.com/blog/using-qt-alternative-programming-languages-part-1) [three](https://www.ics.com/blog/using-qt-alternative-programming-languages-part-2) [articles](https://wiki.qt.io/Category:LanguageBindings) 如果你想要更多.

## Libraries

本节介绍两种第三方库； 那些提供自己全新功能的（例如小部件，处理特定文件格式），以及那些提供与现有软件集成的（例如脚本语言、REST API 客户端、已建立协议的实现）.


### Integrations

就本节而言，以“集成”为中心的库执行以下操作之一：

1. 作为已建立的 Web 服务的客户端.
2. 以 Qt 友好的方式包装另一个库，而不仅仅是一个实现细节（即它试图模仿包装的 API）.


- [mupdf-qt](https://xiangxw.github.io/mupdf-qt) [:octocat:](https://github.com/xiangxw/mupdf-qt) - Qt 包装器 [MuPDF](https://mupdf.com) PDF查看器.
- [neiasound](https://github.com/lucaspcamargo/neiasound) [:octocat:](https://github.com/lucaspcamargo/neiasound) - 专为游戏设计的 OpenAL 包装器，具有 [stb_vorbis](https://nothings.org/stb_vorbis) 和 [libsndfile](http://www.mega-nerd.com/libsndfile) 支持.
- [PythonQt](http://pythonqt.sourcef或者ge.net) [:package:](https://sourcef或者ge.net/projects/pythonqt)  - 使用 Python 编写 Qt 应用程序脚本. 不要混淆 [PyQt](https://riverbankcomputing.com/software/pyqt) 或者 [PySide](https://wiki.qt.io/PySide).
- [QScintilla](https://riverbankcomputing.com/software/qscintilla) [:package:](https://www.riverbankcomputing.com/software/qscintilla/download)  - 极其通用且可自定义的文本编辑器小部件，提供语法突出显示、代码完成、代码折叠、可记录宏等等. 围绕 [Scintilla](http://www.scintilla.org) . 由开发的同一家公司创建 [PyQt](https://riverbankcomputing.com/software/pyqt).
- [QtAwesome](https://github.com/gamecreature/QtAwesome) [:octocat:](https://github.com/gamecreature/QtAwesome) - 添加 [Font Awesome](https://fortawesome.github.io/Font-Awesome)  Qt 应用程序的图标. 也支持其他图标集.
- [QtLua](http://www.nongnu.org/libqtlua) [:package:](https://svn.savannah.nongnu.org/viewvc/?root=libqtlua) - 使用 Lua 作为基于 Qt 的软件的脚本语言.
- [qtruby](https://github.com/cybercatalyst/qtruby) [:octocat:](https://github.com/cybercatalyst/qtruby) - 在您的应用程序中使用 Ruby 作为脚本语言.
- [QuaZIP](http://quazip.sourceforge.net) [:package:](https://sourceforge.net/projects/quazip)  - 读取和写入 ZIP 档案. 用途 [Minizip](http://www.winimage.com/zLibDll/minizip.html) 在引擎盖下.
- [VLC-Qt](https://vlc-qt.tano.si) [:octocat:](https://github.com/vlc-qt/vlc-qt) - 包装 [libvlc](https://wiki.videolan.org/LibVLC) 它允许您向应用程序添加类似 VLC 的媒体播放器.

### New Functionality

- [Communi](https://communi.github.io) [:octocat:](https://github.com/communi/libcommuni)  - 跨平台 IRC 框架. 我们已经有足够的 IRC 客户端了，但我想这也可以用于在您的应用程序中实现聊天功能（例如用于社区支持）.
- [cutelyst](http://cutelyst.org) [:octocat:](https://github.com/cutelyst/cutelyst) - 从 Perl 的 Catalyst 框架中汲取了一些想法的 Web 框架.
- [DiceParser](https://github.com/Rolisteam/DiceParser) [:octocat:](https://github.com/Rolisteam/DiceParser) - 基于其自身语法的骰子滚轮框架. 
- [DOtherSide](https://github.com/filcuc/DOtherSide) [:octocat:](https://github.com/filcuc/DOtherSide) - 用 C 语言绑定 QML，主要设计为*其他*语言的 API，以支持 QML.
- [Felgo](https://felgo.com)  - 严重依赖 QML 的跨平台游戏引擎和应用程序框架. 有很多工具和资源，甚至可能值得拥有自己的列表.
- [glraw](https://github.com/cginternals/glraw) [:octocat:](https://github.com/cginternals/glraw)  - 将图像从任何 Qt 支持的格式转换为 OpenGL 格式的纹理. 用于加速图形应用程序中的纹理加载.
- [grantlee](https://github.com/steveire/grantlee) [:octocat:](https://github.com/steveire/grantlee) - 受 Django 启发的文本模板.
- [injeqt](https://github.com/vogel/injeqt) [:octocat:](https://github.com/vogel/injeqt) - Qt 的依赖注入.
- [KDE Frameworks](https://api.kde.org/frameworks) [:octocat:](https://github.com/KDE) [:package:](https://quickgit.kde.org)  - 用于 KDE 的大量库，但其中许多也可以与常规 Qt 应用程序一起使用. 在大多数情况下，跨平台.
- [Marble](https://marble.kde.org) [:package:](https://cgit.kde.org/marble.git) - 可以独立使用或嵌入其他应用程序的虚拟地球仪和地图.
- [qgexedit2](https://github.com/Simsys/qhexedit2) [:octocat:](https://github.com/Simsys/qhexedit2) - 在您的应用程序中嵌入十六进制编辑器.
- [qml-material](https://github.com/papyros/qml-material) [:octocat:](https://github.com/papyros/qml-material) - 在 QML 中实现的材料设计.
- [QNodeView](https://github.com/gwihlidal/QNodeView) [:octocat:](https://github.com/gwihlidal/QNodeView) - 允许您在类似于 Unreal Engine、Substance Designer 或 PureData 提供的类型的图表中创建和编辑节点的小部件.
- [QSimpleUpdater](https://github.com/alex-spataru/QSimpleUpdater) [:octocat:](https://github.com/alex-spataru/QSimpleUpdater) - 让您的应用程序自行更新.
- [qt-maybe](https://github.com/robertknight/qt-maybe) [:octocat:](https://github.com/robertknight/qt-maybe) - 类型理论的爱好者会喜欢这些总和和可选类型.
- [qt-mustache](https://github.com/robertknight/qt-mustache) [:octocat:](https://github.com/robertknight/qt-mustache) - 使成为 [Mustache](https://mustache.github.io) 模板.
- [QtAV](http://www.qtav.org) [:octocat:](https://github.com/wang-bin/QtAV) - 积极开发多媒体框架.
- [Qtilities](https://jpnaude.github.io/Qtilities) [:octocat:](https://github.com/JPNaude/Qtilities) - 一组强大的库，可为您的应用程序提供 GUI、日志记录、测试、配置和项目功能（以及其他功能）.
- [QtitanChart](http://www.devmachines.com/qtitanchart-overview)  - 图表生成框架. 商业的.
- [QtitanRibbon](http://www.devmachines.com/qtitanribbon-overview)  - 对于 Microsoft 在其软件中使用的色带的粉丝. 商业的.
- [qtnotify](https://github.com/cybercatalyst/qtnotify) [:octocat:](https://github.com/cybercatalyst/qtnotify) - Notification framework.
- [QtTerminalWidget](https://github.com/cybercatalyst/qtterminalwidget) [:octocat:](https://github.com/cybercatalyst/qtterminalwidget) - 使您的应用程序能够**任何**.
- [QtVerbalExpressions](https://github.com/VerbalExpressions/QtVerbalExpressions) [:octocat:](https://github.com/VerbalExpressions/QtVerbalExpressions)  - 使用自然英语表达创建正则表达式. 的一部分 [VerbalExpressions](https://verbalexpressions.github.io) 项目，它对多种语言做同样的事情.
- [qtwebserver](https://github.com/cybercatalyst/qtwebserver) [:octocat:](https://github.com/cybercatalyst/qtwebserver) - 如果您出于某种原因需要在 Qt 中编写 Web 应用程序服务器，这将对您有所帮助.
- [QtXlsx](http://qtxlsx.debao.me) [:octocat:](https://github.com/dbzhang800/QtXlsxWriter) - 以 Microsoft Excel 格式读取和写入电子表格.
- [Qwt](http://qwt.sourceforge.net) [:package:](https://sourceforge.net/projects/qwt) - 专为科学和技术应用程序设计的 Qt 小部件.
- [verdigris](https://github.com/woboq/verdigris) [:octocat:](https://github.com/woboq/verdigris) - 无需*使用`moc`即可编写Qt应用程序的实验性库.

## Software Repositories

如果 [Libraries](#libraries) 部分不满足您，也许其中之一会.

- [#inqlude](https://inqlude.org)  - 最著名的以 Qt 为中心的库集合. 包管理器也可用 [here](https://inqlude.org/get.html).
- [QtPods](https://github.com/qt-pods/qt-pods)  - 另一个以 Qt 为中心的包管理器. 如果您想在不使用 QtPods 的情况下查看产品，可以使用完整列表 [here](https://github.com/qt-pods/qt-pods-master/blob/master/pods.json)，并且可以通过提交拉取请求来添加.
- [Linux-Apps.com](https://www.linux-apps.com) - 尽管名称如此，Linux-Apps.com 为最终用户和开发人员聚合了各种基于 Qt 的工具和库.
- [Stephan Binner's Ubuntu PPAs](https://launchpad.net/~beineri)  - 对安装包管理器之外的任何东西犹豫不决的 Ubuntu 用户可以从这些存储库中获取任何最新版本的 Qt. 添加它们的说明可以在其中找到.

## Blogs

Each entry is followed by a standout list of articles, talks, or other resources.

- [Planet Qt](https://planet.qt.io) - 第一方和第三方Qt相关博客的官方聚合.
- [ICS](https://www.ics.com/blog)  - 以 Qt 为中心的软件咨询公司，拥有非常简洁的博客. 擅长图形应用.
  - Qt 提示和技巧 [[1](https://www.ics.com/blog/qt-tips-and-tricks-part-1), [2](https://www.ics.com/blog/qt-tips-and-tricks-part-2)] - 可以放在后口袋里的零碎物品.
  - [Mastering Qt File Selectors](https://www.ics.com/blog/mastering-qt-file-selectors)  - 有时您需要相同资产的不同变体，但直到运行时您才会知道要加载哪些变体. 这门课会为你做决定.
  - 一些鲜为人知的 Qt 工具和命令 [[1](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-1), [2](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-2), [3](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-3), [4](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-4), [5](https://www.ics.com/blog/some-lesser-known-qt-tools-and-commands-part-5)] - 留在人迹罕至的道路上，您不会找到隐藏的宝石.
  - [Using Self-Signed Certificates in Qt Code](https://www.ics.com/blog/using-self-signed-certificates-qt-code) - 谁也不信任.
  - [Integrating C++ with QML](https://www.ics.com/blog/integrating-c-qml)  - 与您的脚本语言交谈. 这就是它的用途.
  - Qt 和 OpenGL：使用开放式资产导入库 (Assimp) 加载 3D 模型 [[1](https://www.ics.com/blog/qt-and-opengl-loading-3d-model-open-asset-import-library-assimp), [2](https://www.ics.com/blog/qt-and-opengl-loading-3d-model-open-asset-import-library-assimp-part-2) ] - Assimp 支持很多不同的模型类型； 这些文章将帮助您支持所有这些文章.
  - [What's new in Qt 5: QStandardPaths](https://www.ics.com/blog/whats-new-qt-5-qstandardpaths) - 此功能已经存在几年了，但它仍然足够有用，值得列在此列表中.
  - [What's New in Qt 5.2: QCommandLineParser](https://www.ics.com/blog/whats-new-qt-52-qcommandlineparser) - 另一个老歌，但仍然是一个好东西.
- [Woboq](https://woboq.com/blog)  - 另一家也为 Qt 贡献代码的软件咨询公司. 他们似乎专注于 Qt 的核心架构.
  - [Moc myths debunked](https://woboq.com/blog/moc-myths.html)  - Qt 似乎依赖的魔法实际上只是一堆代码生成器. 这篇文章将带您快速了解最引人注目的“moc”的现实.
  - Qt 信号和插槽如何工作 [[1](https://woboq.com/blog/how-qt-signals-slots-work.html), [2](https://woboq.com/blog/how-qt-signals-slots-work-part2-qt5.html), [3](https://woboq.com/blog/how-qt-signals-slots-work-part3-queuedconnection.html) ] - Qt 的信号/插槽系统允许任何对象与任何其他对象对话. 了解这三篇文章将帮助您充分利用该功能.
  - [QMetaType knows your types](https://woboq.com/blog/qmetatype-knows-your-types.html) - C++ 以具有良好的运行时类型信息而著称，因此 Qt 提供了自己的信息.
  - [C++11 in Qt5](https://woboq.com/blog/cpp11-in-qt5.html)  - 停止像 2003 年那样编写 C++； 了解如何在 Qt 应用程序中利用最新的 C++ 功能.
  - [C++14 for Qt programmers](https://woboq.com/blog/cpp14-in-qt.html) - `s/2003/2011/`
  - [QStringLiteral explained](https://woboq.com/blog/qstringliteral.html)  - 字符串字面量在许多应用程序中被广泛使用； 如果您能让它们更快地访问，那不是很好吗？
  - [Nicer debug output in Qt using QT_MESSAGE_PATTERN](https://woboq.com/blog/nice-debug-output-with-qt.html) - 能够读取应用程序的日志真是太好了.
- [KDAB](https://www.kdab.com/category/blogs) - *另一家*专门从事Qt的咨询公司.
  - [GammaRay: Taking a deep look into your Qt application](https://www.youtube.com/watch?v=JcoFk_PVhdk) - 谈论 [GammaRay](https://www.kdab.com/development-resources/qt-tools/gammaray) 以及它如何帮助您剖析 Qt 应用程序. 在 QtCon 2016 上发表的演讲由 [Volker Krause](https://github.com/vkrause).
  - [Multithreading with Qt](https://www.youtube.com/watch?v=dcSsjxhazu0)  - 我想让我的应用程序一次做不止一次的事情. 什么可能出错？ 在 QtCon 2016 上发表的演讲由 [Giuseppe D'Angelo](https://github.com/dangelog).
  - [Linux perf for Qt developers](https://www.youtube.com/watch?v=L4NClVxqdMw)  - 如何使您的 Qt 应用程序更快，Linux 风格. 在 QtCon 2016 上发表的演讲由 [Milian Wolff](https://github.com/milianw).

## Books

- [Qt5 C++ GUI Programming Cookbook](https://www.packtpub.com/application-development/qt5-c-gui-programming-cookbook)， 经过 [Lee Zhi Eng](https://www.zhieng.com) [:octocat:](https://github.com/PacktPublishing/Qt5-C-GUI-Programming-Cookbook)  - 为那些熟悉（但不满意）基础知识的人提供高级 GUI 编程技术的概述. 书中使用的源代码是免费提供的.
- [Game Programming Using Qt: Beginner's Guide](https://www.packtpub.com/game-development/game-programming-using-qt) 作者：Witold Wysota 和 Lorenz Haas - 开始学习如何使用 QML 编程游戏的好地方.
- [Application Development with Qt Creator - 2nd Edition](https://www.packtpub.com/application-development/application-development-qt-creator-second-edition)， 经过 [Ray Rischpater](http://www.lothlorien.com/kf6gpe) - Qt 初学者指南，重点介绍 Qt Creator 及其相关工具.
- [Qt 5 Blueprints](https://www.packtpub.com/application-development/qt-5-blueprints)， 经过 [Symeon Huang](https://github.com/librehat) - 似乎是关于一个 Qt 项目的整体结构.
- [Mastering Qt 5](https://www.packtpub.com/application-development/mastering-qt-5)， 经过 [Guillaume Lazar](https://github.com/GuillaumeLazar) 和 [Robin Penea](https://github.com/synapticvoid) [:octocat:](https://github.com/PacktPublishing/Mastering-Qt-5) - Not your daddy's Qt.  Tips 和 tricks for the experienced.  The source code used in the book is available for free.
- [PySide GUI Application Development - 2nd Edition](https://www.packtpub.com/application-development/pyside-gui-application-development-second-edition)，由 Gopinath Jaganmohan 和 Venkateshwaran Loganathan 撰写 - 想象一下这些其他书籍，但使用 Python.
- [Qt5 Cadaques](https://qmlbook.github.io) [:octocat:](https://github.com/qmlbook/qmlbook) - 专注于 QML 的免费书籍，以作者曾经度假过的西班牙东北部的这个小镇命名.

## Software that Uses Qt

一个框架的好坏取决于使用它的软件. 幸运的是，很多优秀的软件都使用 Qt.

- [Autodesk Maya](http://www.autodesk.com/maya) - 3D 动画和设计软件已被用于为一些最流行的电影和电视节目创造视觉效果.
- [Davinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/) - 带有商业计划的非线性视频编辑免费软件，用于制作一些好莱坞电影.
- [CMake](https://cmake.org) [:octocat:](https://github.com/Kitware/CMake)  - 最接近标准 C++ 构建系统的东西. 捆绑的 GUI 使用 Qt.
- [CRYENGINE](https://www.cryengine.com) [:octocat:](https://github.com/CRYTEK-CRYENGINE/CRYENGINE)  - 但它可以运行孤岛危机吗？ 一些辅助工具使用 Qt.
- [Doxygen](https://www.stack.nl/~dimitri/doxygen) [:octocat:](https://github.com/doxygen/doxygen)  - 最流行的 C++ 文档生成器，尽管它也支持其他语言. 捆绑的 GUI 使用 Qt.
- [Google Earth](https://www.google.com/earth) - **虚拟地球仪.
- [KDE](https://www.kde.org) [:octocat:](https://github.com/KDE) - 最流行的 Linux 桌面环境之一.
- [LMMS](https://lmms.io/) - 数字音频工作站.
- [Malwarebytes](https://www.malwarebytes.com) - 您Windows 桌面的贴身保镖.
- [MuseScore](https://musescore.org) - 乐谱软件.
- [Parallels Desktop](https://www.parallels.com/products/desktop) - 以消费者为中心的虚拟化.
- [Qt Creator](https://www.qt.io/ide) [:octocat:](https://github.com/qtproject/qt-creator)  - 吃你自己的狗粮的东西. 列于 [official tools](#official-tools)，但不在这里列出它感觉不对.
- [Rolisteam](http://www.rolisteam.org) [:octocat:](https://github.com/Rolisteam/rolisteam) - 用于远程角色扮演游戏的虚拟桌面.
- [Shotcut](https://shotcut.org/) - 视频编辑.
- [RUBE](https://www.iforce2d.net/rube) - 适用于任何使用 Box2D 物理引擎的游戏的关卡设计工具.
- [TeamSpeak](https://www.teamspeak.com) - 当游戏玩家想要在不支持语音聊天的游戏中进行语音聊天时，他们会使用此功能.
- [Telegram Desktop](https://desktop.telegram.org) [:octocat:](https://github.com/telegramdesktop/tdesktop)  - 保证你的谈话如此安全，你会提高潜在窃听者的血压. 桌面客户端使用 Qt 并且是开源的.
- [Tiled](http://www.mapeditor.org) [:octocat:](https://github.com/bjorn/tiled)  - 也许是世界上最受欢迎的瓷砖地图编辑器. 适用于游戏中的关卡设计.
- [VirtualBox](https://www.virtualbox.org) [:package:](https://www.virtualbox.org/browser/vbox/trunk)  - x86/64 处理器的虚拟化软件. 捆绑的 GUI 使用 Qt.
- [VLC](https://www.videolan.org/vlc) [:package:](https://code.videolan.org) - 现有最灵活的开源视频播放器之一.
- [Vuo](https://vuo.org) [:octocat:](https://github.com/vuo/vuo) — 用于交互式媒体的实时可视化编程语言.
- [Wireshark](https://www.wireshark.org) [:package:](https://code.wireshark.org/review/gitweb?p=wireshark.git;a=tree)  - 最流行的数据包嗅探器. 你*是*打算用它来为善而不是恶，对吧？
- [Wolfram Mathematica](https://www.wolfram.com/mathematica) - 编程语言、符号计算器和工程师最好的朋友.
- [Yabause](https://yabause.org) [:octocat:](https://github.com/Yabause/yabause) - 现在土星模拟器.

还有一个官方展厅 [here](https://showroom.qt.io)，它允许开发人员提交他们自己的 Qt 驱动的应用程序以供显示.

## Other Relevant Awesome Lists

如果您熟悉 Awesome，您就会知道有*极其* 种类繁多的资源，其有用性取决于您的项目. 但是，如果您正在开发 Qt 应用程序，您几乎肯定也想了解这些.

- [Awesome C/C++](https://github.com/fffaraz/awesome-cpp)  - 没有理由不能使用不是为 Qt 设计的 C++ 库. 有时它们甚至可能比 Qt 提供的更适合您的需求.
- [Awesome C](https://github.com/aleksandar-todorovic/awesome-c)  - C 库也是如此； 可能想在你使用它时复习那些 RAII 技术.
- [Awesome CMake](https://github.com/onqtam/awesome-cmake) - 如果您的项目没有使用 qmake，则您可能会使用 CMake.
- [Awesome OpenGL](https://github.com/eug/awesome-opengl) - Qt 通常用于图形应用程序，甚至围绕 OpenGL 提供自己的包装器.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内， [Jesse Talavera-Greenberg](https://jessetg.github.io) 已放弃本作品的所有版权和相关或邻接权. 见 [https://github.com/JesseTG/awesome-qt/blob/master/LICENSE](https://github.com/JesseTG/awesome-qt/blob/master/LICENSE) 文件了解详情.
