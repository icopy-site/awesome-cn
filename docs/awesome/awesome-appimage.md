<div class="github-widget" data-repo="AppImage/awesome-appimage"></div>
<!--lint disable double-link-->

<div align="center">
	<div>
		<img width="500" src="https://raw.githubusercontent.com/AppImage/awesome-appimage/master/media/logo.svg?sanitize=true" alt="Awesome AppImage">
	</div>
	<a href="https://awesome.re">
		<!img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
	</a>
	<p>
		<sub>Lovingly crafted AppImage tools and resources. Follow me on <a href="https://twitter.com/probonopd">Twitter</a>.</sub>
	</p>
	<br>
</div>

## Awesome AppImage [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[AppImage](https://appimage.org) is a community-based format to distribute applications to various mainstream Linux distributions without the need for a centralized store. One app = one file! This list contains tools to work with AppImages, such as to create AppImages for applications and to integrate AppImages into the system easily. As the vibrant community around AppImage is growing, so is this list.



## AppImage discovery

### App catalogs

- [AppImage.GitHub.io](https://appimage.github.io/) - Catalog of AppImages that passed an automated test, links to upstream download pages.

### App stores

- [AppImageHub.com](https://www.appimagehub.com/) - Downloadable AppImages, powered by [Opendesktop.org](https://www.opendesktop.org/).
- [pling.com](https://www.pling.com/) - Open store where creators can publish their libre products and creative content including AppImages.
- [Manjaro Software Discover](https://software.manjaro.org/appimages) - Web-based app store that contains applications in multiple formats, including AppImage.

### App centers

- [NX Software Center](https://github.com/Nitrux/nx-software-center) - Portable Software Center for portable AppImage applications.
- [AppImagePool](https://github.com/prateekmedia/appimagepool) - Simple, modern AppImageHub Client, powered by flutter.

### App scrapers

- [appimages.scraper](https://github.com/azubieta/appimages.scraper) - Search for AppImage releases over the web.
- [AppImageRadar](https://github.com/AppImage/AppImageRadar) - Search for AppImage-related activity on GitHub using Travis CI.

## AppImage consumption tools

### Desktop integration

- [Getting Started Managing Software with AppImage on Ubuntu](https://adamtheautomator.com/appimage-ubuntu/) - Verbosely explains how to manage AppImages without the need for further software.
- [go-appimaged](https://github.com/probonopd/go-appimage/tree/master/src/appimaged) - Optional daemon that integrates AppImages into the system (experimental).
- [appimaged](https://github.com/AppImage/appimaged) - Optional daemon that integrates AppImages into the system (deprecated).
- [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher) - Integrates into users' systems and establishes a single `~/Applications` directory, assisting the user to move AppImages into there, with support for updating and removing AppImages through apps launcher.
- [appimagehelper](https://gitlab.com/posktomten/appimagehelper) - Program for creating, deleting, controlling and organizing shortcuts to AppImage.
- [LinuxPA](https://github.com/CalebQ42/LinuxPA) - PortableApps.com type launcher for Linux with AppImage support.
- [AppImage Desktop Maker](https://github.com/Alexsussa/AIDM) - Creates menu entries for AppImages without the need for a daemon.
- [Thumbnailer for AppImages](https://github.com/mttbernardini/appimage-thumbnailer) - Generates icons for AppImages that are shown in file managers of GNOME and KDE compatible desktop environments.
- [XApp Thumbnailers](https://github.com/linuxmint/xapp-thumbnailers) - Thumbnailers for GTK Desktop Environments, including one for the AppImage file format. Makes Gtk based file managers like Caja (MATE), Nautilus (GNOME), Nemo (Cinnamon), PCManFM (LXDE), and Thunar (Xfce) show application icons on AppImages.
- [AppImage To Gnome](https://github.com/DejfCold/ATG) - Monitors and (de)installs AppImages from the Gnome desktop.
- [gnome_appimage_installer](https://github.com/knork-fork/gnome_appimage_installer) - Somewhat a misnomer (AppImages don't need to be "installed"), creates a desktop file that follows the freedesktop.org spec for your AppImage files; written in bash.
- [Gear lever](https://github.com/mijorus/gearlever/) - Integrates AppImages into the Gnome desktop by drag-and-drop onto the Gear lever application.

### Updaters

- [AppImageUpdate](https://github.com/AppImage/AppImageUpdate) - Official grapical application to update AppImages; command-line tool to update AppImages.
- [AppImageUpdater](https://github.com/antony-jr/AppImageUpdater) - Simple updater for humans written in C++ and Qt.
- [appimage-update](https://github.com/AppImageCrafters/appimage-update) - AppImage Update implementation written in Go.
- [appimage-updater](https://pypi.org/project/appimage-updater/) - AppImage Update implementation written in Python, distributed on PyPi.

### Sandboxes

- [Firejail](https://github.com/netblue30/firejail) - Optional sandbox with support for AppImage built in.
- [AppImage Sandboxing Project](https://github.com/mgord9518/aisap) - Golang library to help sandbox AppImages with bwrap.

### Package managers

__Note:__ The AppImage format is explicitly designed _not to need any package managers_ or similar tools. Everything can be done in the file manager (and an optional daemon for system integration).

- [appimage-manager](https://github.com/AppImageCrafters/appimage-manager) - Command-line tool for managing AppImages allowing to search, install, remove and update applications.
- [bauh](https://github.com/vinifmor/bauh) - Graphical user interface for managing Linux applications supporting AppImage, Arch (repositories/AUR), Flatpak, Snap and native Web applications.
- [homebrew-appimage](https://github.com/athrunsun/homebrew-appimage) - Linuxbrew AppImage Formulae.
- [AIPM](https://github.com/michaeldelago/aipm) - A Package Manager for AppImages.
- [Zap](https://github.com/srevinsaju/zap) - AppImage package manager. Downloads the AppImage if it does not exist. If it already exists, updates it with AppImageUpdate. Integrates AppImage into the system.
- [RookiePM](https://github.com/18fadly-anthony/rookie) - Package manager for AppImages and Shell Scripts.
- [AppMan](https://github.com/ivan-hc/AppMan) - AppImage Manager that works like APT or Pacman.
- [jewelrystore](https://rubygems.org/gems/jewelrystore) - Command line AppImage store made in ruby.
- [ayy](https://github.com/lawl/ayy) - Package manager for AppImage. Single, static, dependency free binary. Written in Go.
- [leap](https://github.com/lnxcz/leap) - Fast and simple AppImage manager. Written in Rust.
- [Bread](https://github.com/pegvin/bread) - Download, update, remove, and run AppImages from GitHub on the command line, and integrate apps into the desktop.

### Linux distributions

Although the AppImage format was carefully designed not to need any special support from Linux distributions, there are some that offer varying degrees of AppImage friendliness out of the box.

- [Deepin](https://www.deepin.org/en/) - When you double-click an AppImage or any other executable file that lacks execute permissions, a user-friendly dialog explains the situation and asks for your permission to set the execute permission and execute the executable.
- [Nitrux](https://nxos.org/) - Promotes the use of AppImage as the main format for getting applications, has a built in app center featuring AppImages.
- [Linux Mint](https://linuxmint.com/) - Has an [AppImage thumbnailer](https://github.com/linuxmint/xapp-thumbnailers) to show application icons on AppImage files.
- [Zenwalk GNU Linux](http://www.zenwalk.org/) - Is "AppImage ready" and distributes some applications in AppImage format.

## AppImage developer tools

### Low-level tools

- [appimagetool](https://github.com/AppImage/AppImageKit/releases/tag/continuous) - Converts AppDirs into AppImages.
- [nix-bundle](https://github.com/matthewbauer/nix-bundle) - Converts Nix derivations into AppImages.

### Build systems

- [appimagecraft](https://github.com/TheAssassin/appimagecraft) - Recipe based AppImage creation tool working from source.
- [appimage-builder](https://github.com/AppImageCrafters/appimage-builder) - Recipe based AppImage creation tool working from source.
- [KDE Craft](https://invent.kde.org/packaging/craft) - Build system used by KDE that can produce AppImages and other formats.
- [appimage-tooling](https://gitlab.com/sgclarkkde/appimage-tooling) - Ruby tooling to generate Appimages.
- [AppImage.cmake](https://github.com/Ravbug/AppImage.cmake) - CMake script which facilitates generating AppImage executables for Linux.
- [rules_appimage](https://github.com/lalten/rules_appimage) - Bazel rules to package any lang_binary target as AppImage.

### Deployment tools for compiled applications

- [go-appimagetool](https://github.com/probonopd/go-appimage/tree/master/src/appimagetool) - Tool that deploys dependencies into AppDirs, and converts AppDirs into AppImages (experimental).
- [linuxdeployqt](https://github.com/probonopd/linuxdeployqt) - Deploys dependencies into AppDirs and creates AppImages; for Qt and other compiled applications.
- [linuxdeploy](https://github.com/linuxdeploy/linuxdeploy) - AppDir creation and maintenance tool using plugins.
- [XojoToAppImage](https://github.com/AlwaysOfflineSoftware/XojoToAppImage) - Graphical tool for packaging compiled Xojo Linux programs into AppImages.

### Deployment tools for Python applications

- [python-appimage](https://github.com/niess/python-appimage) - Ready to use AppImage distributions of Python (can be modified to include your application).
- [linuxdeploy-plugin-python](https://github.com/niess/linuxdeploy-plugin-python) - Bundle Python into an AppDir using a source distribution and linuxdeploy.
- [linuxdeploy-plugin-conda](https://github.com/linuxdeploy/linuxdeploy-plugin-conda) - Bundle Python into an AppDir using a source distribution, Conda, and linuxdeploy.
- [Briefcase](https://briefcase.readthedocs.io/) - Convert Python project into a standalone native application, e.g., using AppImage.
- [pycharm-appimage-support](https://gitlab.com/chezmurray/pycharm-appimage-support) - Deploy Python project as an AppImage directly from the PyCharm IDE.
- [PyAppImage](https://github.com/srevinsaju/pyappimage) - Ultimately simple python-to-appimage bundler.

### Deployment tools for Electron applications

- [electron-builder](https://github.com/electron-userland/electron-builder) - Supports AppImage as an output format.
- [electron-forge-maker-appimage](https://github.com/saleae/electron-forge-maker-appimage) - Electron Forge builder for AppImage.
- [Appnativefy](https://github.com/sarweshparajuli/appnativefy) - Create AppImage with embedded Electron browser from any website.

### Deployment tools for Windows applications

- [wine32-deploy](https://github.com/sudo-give-me-coffee/wine32-deploy) - Creates AppImages for 32-bit Windows applications that can run on 64-bit Linux systems without multilib installed.
- [AppImage For WINE](https://github.com/Hackerl/Wine_Appimage) - WINE-based AppImages and LD_PRELOAD based patches to launch WINE from AppImages.
- [ferion11/Wine_Appimage](https://github.com/ferion11/Wine_Appimage) - AppImage for WINE 32bits from PlayOnLinux, an run on no-multilib systems.
- [GameImage](https://gitlab.com/formigoni/gameimage) - Is a way to package up games with either Wine or an Emulator into a portable AppImage that could be useful for the Steam Deck.

### Deployment tools for Java applications

- [nbPackager](https://github.com/trixon/nbPackager) - Packages NetBeans Platform Application with a JRE for AppImage, Linux, macOS and Windows.

### Deployment tools for .NET Core (Mono) applications

- [Publish-AppImage for .NET](https://github.com/kuiperzone/Publish-AppImage) - Publish AppImages for .NET applications.
- [.NET Core AppImage example](https://github.com/ppy/osu-deploy/blob/697a49e9602502a2b7a899c0dff5383f6512d5d2/Program.cs#L207-L243) - Example of how to deploy .NET Core (Mono) applications as an AppImage using `dotnet publish -f netcoreapp3.1 -r linux-x64` from within a `.cs` program.
- [PupNet Deploy](https://github.com/kuiperzone/PupNet-Deploy) - Cross-platform deployment utility which publishes your .NET project and packages it as a ready-to-ship installation file in a single step.
- [DotnetPackaging](https://github.com/SuperJMN/DotnetPackaging) - Tool to distribute .NET applications in the AppImage format.

### Deployment tools for Flash applications

- [flash-to-appimage](https://github.com/CredibleOpossum/flash-to-appimage) - Script to package a Flash game (`.swf`) into an AppImage.

### Deployment tools for Rust applications

- [Cargo AppImage](https://github.com/StratusFearMe21/cargo-appimage) - Cargo program that allows you to convert your Rust programs into AppImages.

### Tools to convert from other package formats

- [pkg2appimage](https://github.com/AppImage/pkg2appimage) - Converts from deb, zip, tar.gz and other formats to AppImage using YAML recipes.
- [appimage2pkg](https://gitlab.com/nixtux-packaging/appimage2pkg) - Repack AppImage and make rpm/deb which does not require FUSE.
- [flatpak2appdir](https://github.com/sudo-give-me-coffee/flatpak2appdir) - Turn Flatpak into AppDir which in turn can be turned into AppImage.
- [make-portable](https://github.com/sudo-give-me-coffee/make-portable) - Deploys installed application to AppDir, uses strace to fetch all file system calls and copies all accessed files in to AppDir including glibc.
- [AppImage cobbler](https://gitlab.com/brinkervii/appimage-cobbler) - Python application that takes strace.log and turns it into a directory suited for an AppImage.
- [Elements](https://github.com/s-zeid/elements) - Tool to generate single-file, runc-based AppImages using a minimal (~3 MB compressed) Alpine Linux rootfs.
- [arch2appimage](https://github.com/hanzala123/arch2appimage) - Python script to convert any Arch Linux package (official/AUR) to an AppImage.
- [appimage-bash](https://github.com/valicm/appimage-bash) - GitHub Action for creating AppImage releases from binaries inside `.tar.gz` archives.
- [Package-to-appimage](https://github.com/CausaPrincipalis71/package-to-appimage) - Tool for converting `.deb` and `.rpm` packages into AppImage format by using Docker.
- [GMAppImager](https://github.com/samuelvenable/GMAppImager) - Graphically Converts GameMaker Studio 2 games to AppImage bundles.
- [AppImaGen](https://github.com/ivan-hc/AppImaGen) - Generates an AppImage from Debian or from a PPA of your choice for the previous (unfortunately not the oldest as recommended) and still supported Ubuntu LTS.

### Metadata tools

- [AppStream MetaInfo Creator](https://www.freedesktop.org/software/appstream/metainfocreator/#/) - More elaborate generator for AppStream MetaInfo files by the author of the AppStream metainfo format.

### QC tools

- [appimage-testsuite](https://github.com/aferrero2707/appimage-testsuite) - AppImage testing environment based on Docker containers for various Linux distributions.
- [appimagelint](https://github.com/TheAssassin/appimagelint) - Tool to check AppImages for compatibility, best practices etc.

### Continuous integration

- [GitHub Actions example](https://github.com/probonopd/Zoom.AppImage/blob/master/.github/workflows/main.yml) - Example of how to upload AppImages built using GitHub Actions to GitHub Releases.
- [appimage.yml](https://github.com/iotang/Project_LemonLime/blob/master/.github/workflows/appimage.yml) - Bigger, more complex example of how to build and upload AppImages using GitHub Actions.
- [build-appimage-action](https://github.com/AppImageCrafters/build-appimage-action) - GitHub Action for producing AppImages using appimage-builder.
- [jniltinho/packages](https://github.com/jniltinho/packages) - Drone.io example for producing AppImages using go-appimagetool.
- [Link to the latest build artifact on GitLab CI](https://gitlab.com/linuxappimage/element-desktop/-/jobs/artifacts/master/raw/Element.AppImage?job=run-build) - Example of how to directly link to the latest build artifact on GitLab CI (can be tricky).

### Libraries

- [QAppImageUpdate](https://github.com/antony-jr/QAppImageUpdate) - Qt5 library and plugin for updating AppImages, can be embedded into applications.
- [AppImageServices](https://github.com/azubieta/AppImageServices) - D-Bus services providing a high-level interface over the AppImage manipulation libraries for file managers, software centers and other tools.
- [libappimage](https://github.com/AppImage/libappimage) - Implements functionality for dealing with AppImage files, written in C++ using Boost.
- [libzsync-go](https://github.com/AppImageCrafters/libzsync-go) - Zsync implementation written in Go that can be used to update AppImages.
- [appenv](https://github.com/TheMarlboroMan/appenv) - Small C++ library telling where the app data resides and where the user data is by using `readlink("/proc/self/exe")`), thus allowing C++ applications to become relocatable in the filesystem.

### Templates

- [Qt Desktop Template](https://github.com/stemoretti/qt-desktop-template) - Template for creating Qt Widgets desktop applications with AppImage generation using linuxdeployqt.
- [qt-hello-world](https://github.com/AppImageCrafters/qt-hello-world) - Qt Hello World project for AppImage creation using appimage-builder.
- [qt-qml-project-template-with-ci](https://github.com/219-design/qt-qml-project-template-with-ci) - Template for a Qt/QML application with batteries included: GitHub CI, automated GUI testing, automatic code-format checks and more. Compiles for Linux (AppImage), Mac, and Android.
- [mini-qml](https://github.com/patrickelectric/mini-qml) - Minimal Qml application template with deployment for Linux (AppImage), Windows, macOS and WebAssembly.
- [wxWidgetsTemplate](https://github.com/Ravbug/wxWidgetsTemplate) - Cross-platform application template for wxWidgets C++, with pre-set files and IDE projects, supporting AppImage.
- [Briefcase Linux AppImage Template](https://github.com/beeware/briefcase-linux-appimage-template) - Cookiecutter template for building Python apps that will run under Linux, packaged as an AppImage.

## Resources

### Specs

- [AppImageSpec](https://github.com/AppImage/AppImageSpec) - Official specification for the AppImage format.
- [Desktop Entry Specification](https://specifications.freedesktop.org/desktop-entry-spec/latest/) - Specification for the matadata used inside AppImages.

### Documentation

- [docs.appimage.org](https://docs.appimage.org/) - Official AppImage documentation.
- [appimage-builder.readthedocs.io](https://appimage-builder.readthedocs.io/) - Documentation of appimage-builder, includes tutorials, examples, and more.

### Tutorials

- [Produce an AppImage that bundles everything with go-appimage](https://www.youtube.com/watch?v=XTGn_JqmDu0) - How to make an AppImage that bundles _all_ required libraries so that it should run not only on newer, but also on _older_ systems than the build system.

### Articles

- [The Background Story of AppImage](https://itsfoss.com/appimage-interview/) - Interview with the creator of AppImage, explaining the key ideas and motivations behind the concept.
- [Flatpak, Snap and AppImage](https://distrowatch.com/weekly.php?issue=20160704#opinion) - Jesse Smith on DistroWatch about AppImage, Flatpak and Snap.
- [Don't Install, Just Copy with klik](https://dot.kde.org/2005/09/16/dont-install-just-copy-klik) - Article from 2005 that gives perspective on how AppImage started, relevant only for historical reasons now.

### Videos

- [AppImage: Portable applications for Linux](https://www.youtube.com/watch?v=nzZ6Ikc7juw) - Official AppImage introduction video by its founder.
- [Comparing Linux Package Formats - Deb, Flatpak, AppImage, etc.](https://www.youtube.com/watch?v=7fPShv-8Z_4) - By Bryan Lunduke.
- [AppImage: Universal Linux Apps, Overview and Thoughts](https://www.youtube.com/watch?v=tMqES2pNxYY) - By Jeremy "Jay" LaCroix, LearnLinuxTV.
- [AppImage system integration on Ubuntu using go-appimaged](https://www.youtube.com/watch?v=L00UjifUEfE) - New appimaged daemon from the go-appimage implementation.
- [Integrate and Manage AppImages with AppImageLauncher](https://www.youtube.com/watch?v=D2WA2zdLvVk) - By Eric Adams.

### Books

- [Mastering Qt 5](https://www.amazon.de/Mastering-Qt-stunning-cross-platform-applications-ebook/dp/B07DH9YK9Q/) - Contains a section on how to package and deploy Qt applications for Linux using linuxdeployqt.

### Blogs

- [Planet AppImage](https://appimage.gitlab.io/planet/) - Blog Aggregator covering all things AppImage.
- [TheAssassin Blog](https://assassinate-you.net/tags/appimage/) - Blog covering AppImage related topics by TheAssassin.
- [AppImage Crafters Blog](https://appimagecrafters.github.io/) - Blog about AppImage creation an usage by azubieta.

### Courses

### Community

- [#AppImage channel on libera.chat](https://web.libera.chat/#AppImage) - Chat where AppImage developers and users hang out, be prepared to stay in the channel for days if you don't get answers immediately.
- [discourse.appimage.org](https://discourse.appimage.org/) - Official AppImage forum for users and application developers.
- [Stack Overflow](https://stackoverflow.com/tags/AppImage) - Questions tagged `[appimage]` on Stack Overflow.
- [r/AppImage/](https://www.reddit.com/r/AppImage/) - AppImage subreddit.

### Miscellaneous

- [AppImage wiki](https://github.com/AppImage/AppImageKit/wiki) - Official AppImage wiki.
- [AppImageZip](https://github.com/sagebind/appimagezip) - Experimental pure Rust implementation of the AppImage runtime that uses Zip as the backing file system image.
- [help-wanted](https://github.com/search?q=user%3Aappimage+label%3Ahelp-wanted+state%3Aopen&type=Issues) - AppImage issues that the AppImage team would like your help with. A great way to get started contributing to the project.
- [appdwarf](https://github.com/Phantop/appdwarf) - A tool to convert an AppDir or an existing AppImage file, either as a local file or from a URL, into a highly compressed portable image using dwarfs.

### Related

- [Similar projects](https://github.com/AppImage/AppImageKit/wiki/Similar-projects) - Comparison to other packaging systems.

### Other awesome lists

- [awesome-linuxdeploy](https://github.com/linuxdeploy/awesome-linuxdeploy) - Awesome list on linuxdeploy.
- [All Awesome Lists](https://github.com/topics/awesome) - All the Awesome lists on GitHub.

### Expired links

- [App Outlet](https://app-outlet.github.io/) - Universal app store that works with AppImages, Flatpaks and Snaps.
- [appimage2desktop](https://github.com/me1ting/appimage2desktop) - Creates a desktop file and an icon in the system for an AppImage, nothing else.
- [AppImage-Integrator](https://github.com/w-j-r/AppImage-Integrator) - A simple program to integrate AppImages into the Linux desktop written in Qt6.
- [Get AppImage](https://g.sreve/get-appimage/) - Collection of all AppImages in one website. Great search functionality.
- [AppStream Generator](https://output.jsbin.com/qoqukof) - Very simple generator for AppStream MetaInfo files which application authors can use to add metadata (like descriptions, screenshots, links) to their AppImage.
