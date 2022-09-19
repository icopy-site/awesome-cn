<div class="github-widget" data-repo="AppImage/awesome-appimage"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!--lint disable double-link-->

<div align="center">
	<div>
		<img width="500" src="https://raw.githubusercontent.com/AppImage/awesome-appimage/master/media/logo.svg?sanitize=true" alt="Awesome AppImage">
	</div>
	<a href="https://awesome.re">
		<!img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
	</a>
	<p>
		<sub>精心制作的 AppImage 工具和资源.</sub> <sub>在<a href="https://twitter.com/probonopd">推特上</a>关注我.</sub>
	</p>
	<br>
</div>

## Awesome AppImage [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[AppImage](https://appimage.org) 是一种基于社区的格式，用于将应用程序分发到各种主流 Linux 发行版，而无需集中存储. 一个应用程序 = 一个文件！ 此列表包含使用 AppImages 的工具，例如为应用程序创建 AppImages 并将 AppImages 轻松集成到系统中. 随着 AppImage 周围充满活力的社区不断壮大，这个列表也在增长.



## AppImage discovery

### App catalogs

- [AppImage.GitHub.io](https://appimage.github.io/) - 通过自动化测试的 AppImages 目录，链接到上游下载页面.
- [Get AppImage](https://g.srev.in/get-appimage/)  - 在一个网站中收集所有 AppImage. 强大的搜索功能.

### App stores

- [AppImageHub.com](https://www.appimagehub.com/) - 可下载的 AppImages，由 [Opendesktop.org](https://www.opendesktop.org/).
- [pling.com](https://www.pling.com/) - 开放商店，创作者可以在其中发布他们的自由产品和创意内容，包括 AppImages.
- [App Outlet](https://app-outlet.github.io/) - 适用于 AppImages、Flatpaks 和 Snaps 的通用应用商店.
- [Linux App Store](https://linuxappstore.io/) - 适用于 AppImage、Flatpak 和 Snap 格式的 Linux 应用程序的通用应用程序商店（项目已放弃）.
- [Manjaro Software Discover](https://software.manjaro.org/appimages) - 基于 Web 的应用商店，包含多种格式的应用程序，包括 AppImage.

### App centers

- [NX Software Center](https://github.com/Nitrux/nx-software-center) - 用于便携式 AppImage 应用程序的便携式软件中心.
- [AppImagePool](https://github.com/prateekmedia/appimagepool) - 简单、现代的 AppImageHub 客户端，由 Flutter 提供支持.

### App scrapers

- [appimages.scraper](https://github.com/azubieta/appimages.scraper) - 通过网络搜索 AppImage 版本.
- [AppImageRadar](https://github.com/AppImage/AppImageRadar) - 使用 Travis CI 在 GitHub 上搜索 AppImage 相关活动.

## AppImage consumption tools

### Desktop integration

- [Getting Started Managing Software with AppImage on Ubuntu](https://adamtheautomator.com/appimage-ubuntu/) - 详细解释如何在无需其他软件的情况下管理 AppImages.
- [go-appimaged](https://github.com/probonopd/go-appimage/tree/master/src/appimaged) - 将 AppImages 集成到系统中的可选守护程序（实验性）.
- [appimaged](https://github.com/AppImage/appimaged) - 将 AppImages 集成到系统中的可选守护程序（已弃用）.
- [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher) - 集成到用户系统并建立一个单一的`~/Applications`目录，帮助用户将AppImages移动到那里，并支持通过应用程序启动器更新和删除AppImages.
- [appimage2desktop](https://github.com/me1ting/appimage2desktop) - 在系统中为 AppImage 创建桌面文件和图标，仅此而已.
- [appimagehelper](https://gitlab.com/posktomten/appimagehelper) - 用于创建、删除、控制和组织 AppImage 快捷方式的程序.
- [LinuxPA](https://github.com/CalebQ42/LinuxPA) - 适用于具有 AppImage 支持的 Linux 的 PortableApps.com 类型启动器.
- [AppImage Desktop Maker](https://github.com/Alexsussa/AIDM) - Creates menu entries for AppImages without the need for a daemon.
- [Thumbnailer for AppImages](https://github.com/mttbernardini/appimage-thumbnailer) - 为 GNOME 和 KDE 兼容桌面环境的文件管理器中显示的 AppImage 生成图标.
- [XApp Thumbnailers](https://github.com/linuxmint/xapp-thumbnailers)  - GTK 桌面环境的缩略图，包括一个用于 AppImage 文件格式的缩略图. 使基于 Gtk 的文件管理器，如 Caja (MATE)、Nautilus (GNOME)、Nemo (Cinnamon)、PCManFM (LXDE) 和 Thunar (Xfce) 在 AppImages 上显示应用程序图标.
- [AppImage To Gnome](https://github.com/DejfCold/ATG) - 从 Gnome 桌面监控和（卸载）安装 AppImages.

### Updaters

- [AppImageUpdate](https://github.com/AppImage/AppImageUpdate)  - 更新 AppImages 的官方图形应用程序； 用于更新 AppImages 的命令行工具.
- [AppImageUpdater](https://github.com/antony-jr/AppImageUpdater) - 用 C++ 和 Qt 编写的用于人类的简单更新程序.
- [appimage-update](https://github.com/AppImageCrafters/appimage-update) - 用 Go 编写的 AppImage 更新实现.

### Sandboxes

- [Firejail](https://github.com/netblue30/firejail) - 内置支持 AppImage 的可选沙箱.
- [AppImage Sandboxing Project](https://github.com/mgord9518/aisap) - 使用 bwrap 帮助沙箱 AppImages 的 Golang 库.

### Package managers

 __注意：__ AppImage 格式被明确设计为_不需要任何包管理器_或类似工具. 一切都可以在文件管理器中完成（以及用于系统集成的可选守护程序）.

- [appimage-manager](https://github.com/AppImageCrafters/appimage-manager) - 用于管理 AppImages 的命令行工具，允许搜索、安装、删除和更新应用程序.
- [bauh](https://github.com/vinifmor/bauh) - 用于管理支持 AppImage、Arch（存储库/AUR）、Flatpak、Snap 和本机 Web 应用程序的 Linux 应用程序的图形用户界面.
- [homebrew-appimage](https://github.com/athrunsun/homebrew-appimage) - Linuxbrew AppImage 公式.
- [AIPM](https://github.com/michaeldelago/aipm) - AppImages 的包管理器.
- [Zap](https://github.com/srevinsaju/zap)  - AppImage 包管理器. 如果 AppImage 不存在，则下载它. 如果它已经存在，则使用 AppImageUpdate 对其进行更新. 将 AppImage 集成到系统中.
- [RookiePM](https://github.com/18fadly-anthony/rookie) - AppImages 和 Shell 脚本的包管理器.
- [AppMan](https://github.com/ivan-hc/AppMan) - 像 APT 或 Pacman 一样工作的 AppImage 管理器.
- [jewelrystore](https://rubygems.org/gems/jewelrystore) - 用 ruby​​ 制作的命令行 AppImage 商店.
- [ayy](https://github.com/lawl/ayy)  - AppImage 的包管理器. 单一、静态、无依赖的二进制文件. 用围棋写的.

### Linux distributions

尽管 AppImage 格式经过精心设计，不需要 Linux 发行版的任何特殊支持，但仍有一些提供不同程度的开箱即用的 AppImage 友好性.

- [Deepin](https://www.deepin.org/en/) - 当您双击 AppImage 或任何其他缺少执行权限的可执行文件时，一个用户友好的对话框会解释情况并要求您设置执行权限并执行可执行文件.
- [Nitrux](https://nxos.org/) - 推广使用 AppImage 作为获取应用程序的主要格式，内置应用程序中心以 AppImages 为特色.
- [Linux Mint](https://linuxmint.com/) - 有一个 [AppImage thumbnailer](https://github.com/linuxmint/xapp-thumbnailers) 在 AppImage 文件上显示应用程序图标.
- [Zenwalk GNU Linux](http://www.zenwalk.org/) - “AppImage 准备就绪”并以 AppImage 格式分发一些应用程序.

## AppImage developer tools

### Low-level tools

- [appimagetool](https://github.com/AppImage/AppImageKit/releases/tag/continuous) - 将 AppDirs 转换为 AppImages.
- [nix-bundle](https://github.com/matthewbauer/nix-bundle) - 将 Nix 派生转换为 AppImage.

### Build systems

- [appimagecraft](https://github.com/TheAssassin/appimagecraft) - 基于配方的 AppImage 创建工具从源代码工作.
- [appimage-builder](https://github.com/AppImageCrafters/appimage-builder) - 基于配方的 AppImage 创建工具从源代码工作.
- [KDE Craft](https://invent.kde.org/packaging/craft) - KDE 使用的构建系统，可以生成 AppImages 和其他格式.
- [appimage-tooling](https://gitlab.com/sgclarkkde/appimage-tooling) - 用于生成 Appimages 的 Ruby 工具.
- [AppImage.cmake](https://github.com/Ravbug/AppImage.cmake) - 有助于为 Linux 生成 AppImage 可执行文件的 CMake 脚本.
- [rules_appimage](https://github.com/lalten/rules_appimage) - Bazel 规则将任何 lang_binary 目标打包为 AppImage.

### Deployment tools for compiled applications

- [go-appimagetool](https://github.com/probonopd/go-appimage/tree/master/src/appimagetool) - 将依赖项部署到 AppDirs 并将 AppDirs 转换为 AppImages 的工具（实验性）.
- [linuxdeployqt](https://github.com/probonopd/linuxdeployqt)  - 将依赖项部署到 AppDirs 并创建 AppImages； 用于 Qt 和其他编译的应用程序.
- [linuxdeploy](https://github.com/linuxdeploy/linuxdeploy) - 使用插件的 AppDir 创建和维护工具.

### Deployment tools for Python applications

- [python-appimage](https://github.com/niess/python-appimage) - 准备使用 Python 的 AppImage 发行版（可以修改以包含您的应用程序）.
- [linuxdeploy-plugin-python](https://github.com/niess/linuxdeploy-plugin-python) - 使用源分发和 linuxdeploy 将 Python 捆绑到 AppDir 中.
- [linuxdeploy-plugin-conda](https://github.com/linuxdeploy/linuxdeploy-plugin-conda) - 使用源代码分发、Conda 和 linuxdeploy 将 Python 捆绑到 AppDir.
- [Briefcase](https://briefcase.readthedocs.io/) - 将 Python 项目转换为独立的本机应用程序，例如，使用 AppImage.
- [pycharm-appimage-support](https://gitlab.com/chezmurray/pycharm-appimage-support) - 直接从 PyCharm IDE 将 Python 项目部署为 AppImage.
- [PyAppImage](https://github.com/srevinsaju/pyappimage) - 最终简单的 python-to-appimage 捆绑器.

### Deployment tools for Electron applications

- [electron-builder](https://github.com/electron-userland/electron-builder) - 支持 AppImage 作为输出格式.
- [electron-forge-maker-appimage](https://github.com/saleae/electron-forge-maker-appimage) - AppImage 的 Electron Forge 构建器.
- [Appnativefy](https://github.com/sarweshparajuli/appnativefy) - 从任何网站使用嵌入式电子浏览器创建 AppImage.

### Deployment tools for Windows applications

- [wine32-deploy](https://github.com/sudo-give-me-coffee/wine32-deploy) - 为无需安装 multilib 的 64 位 Linux 系统上运行的 32 位 Windows 应用程序创建 AppImages.
- [AppImage For WINE](https://github.com/Hackerl/Wine_Appimage) - 基于 WINE 的 AppImages 和基于 LD_PRELOAD 的补丁，用于从 AppImages 启动 WINE.
- [ferion11/Wine_Appimage](https://github.com/ferion11/Wine_Appimage) - 来自 PlayOnLinux 的适用于 WINE 32 位的 AppImage，可在非多库系统上运行.

### Deployment tools for Java applications

- [nbPackager](https://github.com/trixon/nbPackager) - 使用适用于 AppImage、Linux、macOS 和 Windows 的 JRE 打包 NetBeans 平台应用程序.

### Deployment tools for .NET Core (Mono) applications

- [Publish-AppImage for .NET](https://github.com/kuiperzone/Publish-AppImage) - 为 .NET 应用程序发布 AppImages.
- [.NET Core AppImage example](https://github.com/ppy/osu-deploy/blob/697a49e9602502a2b7a899c0dff5383f6512d5d2/Program.cs#L207-L243) - 如何使用 `.cs` 程序中的 `dotnet publish -f netcoreapp3.1 -r linux-x64` 将 .NET Core (Mono) 应用程序部署为 AppImage 的示例.

### Deployment tools for Flash applications

- [flash-to-appimage](https://github.com/CredibleOpossum/flash-to-appimage) - 将 Flash 游戏 (`.swf`) 打包到 AppImage 中的脚本.

### Deployment tools for Rust applications

- [Cargo AppImage](https://github.com/StratusFearMe21/cargo-appimage) - Cargo 程序，允许您将 Rust 程序转换为 AppImages.

### Tools to convert from other package formats

- [pkg2appimage](https://github.com/AppImage/pkg2appimage) - 使用 YAML 配方从 deb、zip、tar.gz 和其他格式转换为 AppImage.
- [appimage2pkg](https://gitlab.com/nixtux-packaging/appimage2pkg) - 重新打包 AppImage 并制作不需要 FUSE 的 rpm/deb.
- [flatpak2appdir](https://github.com/sudo-give-me-coffee/flatpak2appdir) - 将 Flatpak 转换为 AppDir，而 AppDir 又可以转换为 AppImage.
- [make-portable](https://github.com/sudo-give-me-coffee/make-portable) - 将安装的应用程序部署到 AppDir，使用 strace 获取所有文件系统调用并将所有访问的文件复制到 AppDir，包括 glibc.
- [AppImage cobbler](https://gitlab.com/brinkervii/appimage-cobbler) - 接受 strace.log 并将其转换为适合 AppImage 的目录的 Python 应用程序.
- [Elements](https://gitlab.com/scottywz/elements) - 使用最小（约 3 MB 压缩）Alpine Linux rootfs 生成单文件、基于 runc 的 AppImage 的工具.
- [arch2appimage](https://github.com/hanzala123/arch2appimage) - 用于将任何 Arch Linux 包（官方/AUR）转换为 AppImage 的 Python 脚本.
- [appimage-bash](https://github.com/valicm/appimage-bash) - 用于从 .tar.gz 档案中的二进制文件创建 AppImage 版本的 GitHub 操作.

### Metadata tools

- [AppStream Generator](https://output.jsbin.com/qoqukof) - 非常简单的 AppStream MetaInfo 文件生成器，应用程序作者可以使用这些生成器将元数据（如描述、屏幕截图、链接）添加到他们的 AppImage.
- [AppStream MetaInfo Creator](https://www.freedesktop.org/software/appstream/metainfocreator/#/) - AppStream 元信息格式的作者为 AppStream 元信息文件提供了更精细的生成器.

### QC tools

- [appimage-testsuite](https://github.com/aferrero2707/appimage-testsuite) - 基于 Docker 容器的 AppImage 测试环境，适用于各种 Linux 发行版.
- [appimagelint](https://github.com/TheAssassin/appimagelint) - 检查 AppImage 的兼容性、最佳实践等的工具.

### Continuous integration

- [GitHub Actions example](https://github.com/probonopd/Zoom.AppImage/blob/master/.github/workflows/main.yml) - 如何将使用 GitHub Actions 构建的 AppImages 上传到 GitHub Releases 的示例.
- [appimage.yml](https://github.com/iotang/Project_LemonLime/blob/master/.github/workflows/appimage.yml) - 更大、更复杂的示例，说明如何使用 GitHub Actions 构建和上传 AppImage.
- [build-appimage-action](https://github.com/AppImageCrafters/build-appimage-action) - 使用 appimage-builder 生成 AppImages 的 GitHub 操作.
- [jniltinho/packages](https://github.com/jniltinho/packages) - 使用 go-appimagetool 生成 AppImages 的 Drone.io 示例.
- [Link to the latest build artifact on GitLab CI](https://gitlab.com/linuxappimage/element-desktop/-/jobs/artifacts/master/raw/Element.AppImage?job=run-build) - 如何直接链接到 GitLab CI 上的最新构建工件的示例（可能很棘手）.

### Libraries

- [QAppImageUpdate](https://github.com/antony-jr/QAppImageUpdate) - 用于更新 AppImages 的 Qt5 库和插件，可以嵌入到应用程序中.
- [AppImageServices](https://github.com/azubieta/AppImageServices) - D-Bus 服务通过 AppImage 操作库为文件管理器、软件中心和其他工具提供高级接口.
- [libappimage](https://github.com/AppImage/libappimage) - 实现处理 AppImage 文件的功能，使用 Boost 用 C++ 编写.
- [libzsync-go](https://github.com/AppImageCrafters/libzsync-go) - 用 Go 编写的 Zsync 实现，可用于更新 AppImages.

### Templates

- [Qt Desktop Template](https://github.com/stemoretti/qt-desktop-template) - 使用 linuxdeployqt 创建带有 AppImage 生成的 Qt Widgets 桌面应用程序的模板.
- [qt-hello-world](https://github.com/AppImageCrafters/qt-hello-world) - 使用 appimage-builder 创建 AppImage 的 Qt Hello World 项目.
- [qt-qml-project-template-with-ci](https://github.com/219-design/qt-qml-project-template-with-ci)  - 包含电池的 Qt/QML 应用程序模板：GitHub CI、自动 GUI 测试、自动代码格式检查等. 为 Linux (AppImage)、Mac 和 Android 编译.
- [mini-qml](https://github.com/patrickelectric/mini-qml) - 用于 Linux (AppImage)、Windows、macOS 和 WebAssembly 的最小 Qml 应用程序模板.
- [wxWidgetsTemplate](https://github.com/Ravbug/wxWidgetsTemplate) - wxWidgets C++的跨平台应用模板，带有预设文件和IDE项目，支持AppImage.
- [Briefcase Linux AppImage Template](https://github.com/beeware/briefcase-linux-appimage-template) - 用于构建将在 Linux 下运行的 Python 应用程序的 Cookiecutter 模板，打包为 AppImage.

## Resources

### Specs

- [AppImageSpec](https://github.com/AppImage/AppImageSpec) - AppImage 格式的官方规范.
- [Desktop Entry Specification](https://specifications.freedesktop.org/desktop-entry-spec/latest/) - AppImages 中使用的元数据规范.

### Documentation

- [docs.appimage.org](https://docs.appimage.org/) - 官方 AppImage 文档.
- [appimage-builder.readthedocs.io](https://appimage-builder.readthedocs.io/) - appimage-builder 的文档，包括教程、示例等.

### Tutorials

- [Produce an AppImage that bundles everything with go-appimage](https://www.youtube.com/watch?v=XTGn_JqmDu0) - 如何制作一个捆绑了_所有_所需库的 AppImage，以便它不仅可以在较新的系统上运行，而且还可以在比构建系统的_旧_系统上运行.

### Articles

- [The Background Story of AppImage](https://itsfoss.com/appimage-interview/) - 采访 AppImage 的创建者，解释概念背后的关键思想和动机.
- [Flatpak, Snap and AppImage](https://distrowatch.com/weekly.php?issue=20160704#opinion) - Jesse Smith 在 DistroWatch 上关于 AppImage、Flatpak 和 Snap.
- [Don't Install, Just Copy with klik](https://dot.kde.org/2005/09/16/dont-install-just-copy-klik) - 2005 年的文章介绍了 AppImage 是如何开始的，现在仅与历史原因相关.

### Videos

- [AppImage: Portable applications for Linux](https://www.youtube.com/watch?v=nzZ6Ikc7juw) - 创始人官方AppImage介绍视频.
- [Comparing Linux Package Formats - Deb, Flatpak, AppImage, etc.](https://www.youtube.com/watch?v=7fPShv-8Z_4) - 布莱恩·伦杜克.
- [AppImage: Universal Linux Apps, Overview and Thoughts](https://www.youtube.com/watch?v=tMqES2pNxYY) - 杰里米“杰伊”拉克鲁瓦，LearnLinuxTV.
- [AppImage system integration on Ubuntu using go-appimaged](https://www.youtube.com/watch?v=L00UjifUEfE) - 来自 go-appimage 实现的新 appimaged 守护进程.
- [Integrate and Manage AppImages with AppImageLauncher](https://www.youtube.com/watch?v=D2WA2zdLvVk) - 埃里克亚当斯.

### Books

- [Mastering Qt 5](https://www.amazon.de/Mastering-Qt-stunning-cross-platform-applications-ebook/dp/B07DH9YK9Q/) - 包含有关如何使用 linuxdeployqt 为 Linux 打包和部署 Qt 应用程序的部分.

### Blogs

- [Planet AppImage](https://appimage.gitlab.io/planet/) - 涵盖所有 AppImage 的博客聚合器.
- [TheAssassin Blog](https://assassinate-you.net/tags/appimage/) - TheAssassin 涵盖 AppImage 相关主题的博客.
- [AppImage Crafters Blog](https://appimagecrafters.github.io/) - 关于 AppImage 创建和 azubieta 用法的博客.

### Courses

### Community

- [#AppImage channel on libera.chat](https://web.libera.chat/#AppImage) - 在 AppImage 开发人员和用户闲逛的地方聊天，如果您没有立即得到答案，请准备好在频道中停留几天.
- [discourse.appimage.org](https://discourse.appimage.org/) - 面向用户和应用程序开发人员的官方 AppImage 论坛.
- [Stack Overflow](https://stackoverflow.com/tags/AppImage) - Stack Overflow 上标记为“[appimage]”的问题.
- [r/AppImage/](https://www.reddit.com/r/AppImage/) - AppImage 子版块.

### Miscellaneous

- [AppImage wiki](https://github.com/AppImage/AppImageKit/wiki) - 官方 AppImage 维基.
- [AppImageZip](https://github.com/sagebind/appimagezip) - 使用 Zip 作为后备文件系统映像的 AppImage 运行时的实验性纯 Rust 实现.
- [help-wanted](https://github.com/search?q=user%3Aappimage+label%3Ahelp-wanted+state%3Aopen&type=Issues)  - AppImage 团队希望您帮助解决的 AppImage 问题. 开始为项目做出贡献的好方法.

### Related

- [Similar projects](https://github.com/AppImage/AppImageKit/wiki/Similar-projects) - 与其他包装系统的比较.

### Other awesome lists

- [awesome-linuxdeploy](https://github.com/linuxdeploy/awesome-linuxdeploy) - 关于 linuxdeploy 的很棒的列表.
- [All Awesome Lists](https://github.com/topics/awesome) - GitHub 上的所有 Awesome 列表.
