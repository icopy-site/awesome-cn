<div class="github-widget" data-repo="unixorn/awesome-zsh-plugins"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-zsh-plugins

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Status

[![License](https://img.shields.io/github/license/unixorn/awesome-zsh-plugins.svg)](https://opensource.org/licenses/BSD-3-Clause)
![Awesomebot](https://github.com/unixorn/awesome-zsh-plugins/actions/workflows/awesomebot.yml/badge.svg)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/awesome-zsh-plugins.svg)](https://github.com/unixorn/awesome-zsh-plugins/stargazers)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/unixorn/awesome-zsh-plugins/main.svg)](https://github.com/unixorn/awesome-zsh-plugins)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/unixorn/awesome-zsh-plugins/)

A collection of ZSH frameworks, plugins, tutorials & themes inspired by the various awesome list collections out there.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*请阅读 [Contributing Guidelines](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Contributing.md) 在贡献之前.*

## Frameworks

These frameworks make customizing your ZSH setup easier.

您可以在以下位置找到各种框架的一些有趣的性能时序比较.

* [rossmacarthur/zsh-plugin-manager-benchmark](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark)
* [pm-perf-test](https://github.com/z-shell/pm-perf-test) - 用于在多个 ZSH 框架上运行性能测试的工具.
### [alf](https://github.com/psyrendust/alf)

**Alf** is an out of this world super fast and configurable framework for ZSH; it's modeled after Prezto and Antigen while utilizing Oh-My-Zsh under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

**ansible-role-zsh** is an ansible role with zero-knowledge installation. It uses antigen to manage bundles and oh-my-zsh. Can load bundles conditionally. By default it includes powerlevel9k theme, autosuggestions, syntax-highlighting and [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) and [fzf-marks](https://github.com/urbainvaes/fzf-marks). Fully customizable.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody](https://github.com/getantibody/antibody)

**Antibody** is a faster and simpler antigen written in Golang. More details at [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

**antigen-hs** is a replacement for antigen optimized for a low overhead when starting up the shell. It will automatically clone plugins for you.

### [antigen](https://github.com/zsh-users/antigen)

**Antigen** is a small set of functions that help you easily manage your shell (ZSH) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to ZSH, what Vundle is to vim. Antigen can load oh-my-zsh themes and plugins and will automatically clone them for you.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)

 **Ax-ZSH** 是 ZSH 的模块化配置系统. 它提供了合理的默认值，并且可以通过插件进行扩展.

**Ax-ZSH** integrates well with [Powerlevel10k](https://github.com/romkatv/powerlevel10k) and other extensions, including plugins compatible with [oh-my-zsh](https://ohmyz.sh/).

### [dotzsh](https://github.com/dotphiles/dotzsh)

**Dotzsh** strives to be platform and version independent. Some functionality may be lost when running under older versions of ZSH, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.

### [fresh](https://github.com/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as Bundler for your dot files.

### [miniplug](https://sr.ht/~yerinalexey/miniplug)

**miniplug** is a minimalistic plugin manager for ZSH.

* 重新采购 .zshrc 时没有崩溃或双重插件加载
* 与其他框架不同，Miniplug 不会污染您的 $PATH
* Only does the bare minimum for managing plugins

### [mzpm](https://github.com/Insert-Creative-Name-Here/mzpm)

**mzpm** 是 ZSH 的极简插件管理器。

Features:

- Fetching and loading plugins from GitHub
- 加载本地插件
- Loading themes

### [oh-my-zsh](https://ohmyz.sh/)

**oh-my-zsh** is a community-driven framework for managing your ZSH configuration. Includes 120+ optional plugins (rails, git, macOS, hub, capistrano, brew, ant, macports, etc), over 120 themes to spice up your morning, and an auto-update tool that makes it easy to keep up with the latest updates from the community.

### [PMS](https://github.com/JoshuaEstes/pms)

 PMS 允许您以有助于减少设置时间并提高生产力的方式管理您的外壳. 它支持主题（更改 shell 的外观）、插件（向 shell 添加功能）和点文件管理.

The PMS framework also allows you to use the same framework in different shells. Use ZSH on your personal laptop, and use bash on remote servers. Wanna try fish? Go ahead, try out different shells.

### [prezto](https://github.com/sorin-ionescu/prezto)

 **Prezto** 通过健全的默认值、别名、函数、自动完成和提示主题丰富了 ZSH 命令行界面环境. 有一些特定于 prezto 的插件 [https://github.com/belak/prezto-contrib](https://github.com/belak/prezto-contrib).

### [pumice](https://github.com/ryutamaki/pumice)

**Pumice** 是 ZSH 的轻量级插件管理器.

### [pz](https://github.com/mattmc3/pz)

A plugin manager for ZSH doesn't have to be complicated to be powerful. PZ doesn't try to be clever when it can be smart. PZ is a full featured, fast, and easy to understand plugin manager encapsulated in a single file with about 200 lines of clean ZSH.

PZ does just enough to manage your Zsh plugins really well, and then gets out of your way. And it's unit tested too to make sure it works as expected!

### [sheldon](https://github.com/rossmacarthur/sheldon)

A fast, configurable, shell plugin manager.

* 可以管理
  * 任何 `git` 存储库.
    * Branch/tag/commit support.
    * 对 GitHub 存储库的额外支持.
    * 对 Gists 的额外支持.
  * Arbitrary remote files, simply specify the URL.
  * Local plugins, simply specify the directory path.
* Highly configurable install methods using [handlebars](http://handlebarsjs.com/) templating.
* Super-fast parallel installation.
* 配置文件使用 [TOML](https://github.com/toml-lang/toml) 句法.
* 使用锁定文件更快地加载插件.

### [Toasty](https://github.com/5paceToast/toasty-zsh)

**Toasty** 是一个 ZSH 框架，旨在促进管理，而不是命令它.

### [tzpm](https://github.com/notusknot/tzpm)

最小的 ZSH 插件管理器. 仍在开发中.

### [uz](https://github.com/maxrodrigo/uz)

ZSH 微插件管理器.

### [yazt](https://github.com/bashelled/yazt)

 Yazt 是一个简单的 zsh 主题管理器，几乎与所有东西兼容. 您可以在插件中使用提示，混合 &#39;n&#39; 匹配两个主题，稍加修改，您甚至可以在 bash 中使用它.

### [zapack](https://github.com/aiya000/zsh-zapack)

zapack 是一个基本的快速最小 ZSH 插件加载器.

### [zcomet](https://github.com/agkozak/zcomet)

**zcomet** is a minimalistic ZSH plugin manager that gets you to the prompt surprisingly quickly without caching (see the benchmarks). In addition to loading and updating plugins stored in Git repositories, it supports lazy-loading plugins (further reducing startup time) as well as downloading and sourcing code snippets.

### [zebrafish](https://github.com/mattmc3/zebrafish)

**Zebrafish** 是一个轻量级、功能齐全、速度极快的 ZSH 微框架，仅包含一个文件.

### [zeesh](https://github.com/zeekay/zeesh)

**Zeesh** is a cross-platform ZSH framework. It's similar to, but incompatible with, [oh-my-zsh](http://ohmyz.sh/) . 它具有模块化的插件架构，使其易于扩展. 它有一组丰富的默认值，但被设计为尽可能轻量级.

### [zgem](https://github.com/qoomon/zgem)

**Zgem** 是 ZSH 的插件管理器，支持从 git、http 和本地文件加载和更新插件和主题.

### [zgen](https://github.com/tarjoilija/zgen)

 **Zgen** 是受 Antigen 启发的 ZSH 轻量级插件管理器. 目标是在启动 shell 时有最小的开销，因为没有人喜欢等待. 它目前没有得到积极维护，我建议您使用 [zgenom](https://github.com/jandamm/zgenom) fork instead, which is.

### [zgenom](https://github.com/jandamm/zgenom)

ZSH 的轻量级插件管理器，它是一个扩展了辉煌的分支 [zgen](https://github.com/tarjoilija/zgen) 并提供更多功能和错误修复，同时完全向后兼容.

为了在新的终端会话期间保持快速加载，`zgenom` 会生成一个静态的 `init.zsh` 文件，它除了获取插件并将它们附加到您的 `fpath` 之外什么都不做.

This minimizes startup time by not having to execute time consuming logic (plugin checking, updates, etc) during startup. The downside is that you have to refresh the init script manually with `zgenom reset` whenever you update your plugin list in your `.zshrc`.

Zgenom can load [oh-my-zsh](http://ohmyz.sh/)-兼容和 [prezto](https://github.com/sorin-ionescu/prezto)-compatible plugins and themes, and will automagically `git clone` plugins for you when you add them to your plugin list.

### [ZI](https://github.com/z-shell/zi)

 **ZI** 是用于 Zsh Unix shell 的瑞士军刀. 以前称为zplugin、zinit. 紫—— [Wiki Pages](https://z-shell.pages.dev/).

Bonus: you can use [zi-console](https://github.com/z-shell/zi-console) 查看和更改 ZSH 会话的状态（例如：列出和卸载插件）并从磁盘中删除插件和片段.

### [zilsh](https://github.com/zilsh/zilsh)

**zilsh** is a ZSH config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim](https://github.com/zimfw/zimfw)

**Zim** is a ZSH configuration framework with blazing speed and modular extensions.

### [Zinit](https://github.com/zdharma-continuum/zinit)

**Zinit** 是一个创新的并且可能（由于 Turbo）最快的插件管理器，它支持：

 - Turbo 模式 – ZSH 启动速度提高 80%！ 例如：不是 200 毫秒，而是 40 毫秒
- 完成管理（有选择地禁用和启用完成）
- 片段（↔ 通过 URL 下载的常规文件，例如：脚本）并通过它们 Oh My Zsh 和 Prezto 插件支持（→ 低开销）
- Annexes (↔ Zinit extensions)
- Reports (from the plugin loads – plugins are no longer black boxes)
- 插件卸载（允许例如：动态主题切换）
- `bindkey` 捕获和重新映射
- 包
- 清理 `fpath`（数组 `$fpath` 不用于添加完成和自动加载功能，因此它保持简洁，而不是臃肿）
- 服务↔单实例后台插件
- Also, in general: all the mechanisms from the ZSH Plugin Standard – Zinit is a reference implementation of the standard.

The project is very active – currently > 3100 commits.

### [zit](https://github.com/thiagokokada/zit)

**zit** is a plugin manager for ZSH. It is minimal because it implements the bare minimum to be qualified as a plugin manager: it allows the user to install plugins from Git repositories (and Git repositories only, them why the name), source plugins and update them. It does not implement fancy functions like cleanup of removed plugins, automatic compilation of installed plugins, alias for oh-my-zsh/prezto/other ZSH frameworks, building binaries, PATH manipulation and others.

### [znap](https://github.com/marlonrichert/zsh-snap)

 **:zap:Znap** 是一个轻量级的 ZSH 插件管理器和 Git 存储库管理器，易于理解. 虽然专门为 ZSH 插件量身定制，但 Znap 还用作管理 Git 存储库的通用实用程序.

Znap

Znap 可以：

- Make any prompt appear instantly. Reduce your startup time from ~200ms to ~40ms with just one command.
- Asynchronously compile your plugins and functions.
- 缓存那些昂贵的`eval $(commands)`.
- 并行克隆或拉取多个存储库.
- Re-clone all your repos without you having to re-enter them.
- 多回购管理
- 自动 `compinit` 和 `bashinit` - 你的 `.zshrc` 中不再需要它们，znap 会根据需要自动执行它们.

### [zoppo](https://github.com/zoppo/zoppo)

**Zoppo** is the crippled configuration framework for ZSH. As an Italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.

### [zpacker](https://github.com/happyslowly/zpacker)

**Zpacker** is a lightweight ZSH plugin & theme management framework.

### [zpico](https://github.com/thornjad/zpico)

小巧的 ZSH 包管理器. 没有多余的装饰，没有臃肿，只有 2 kB 的 100% ZSH 代码，为您的 ZSH 环境提供完整的包管理.

### [zplug](https://github.com/zplug/zplug)

**:hibiscus: Zplug** is a next-generation ZSH plugin manager.

- Can manage everything
  - Zsh plugins/UNIX commands on [GitHub](https://github.com) and [Bitbucket](https://bitbucket.org)
  - Gist files ([gist.github.com](https://gist.github.com/discover))
  - Externally managed plugins e.g., [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) and [prezto](https://github.com/sorin-ionescu/prezto) 插件/主题
  - Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
  - Local plugins
  - 等等（你可以添加你 [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- 超快速并行安装/更新
- Support for lazy-loading
- 分支/标签/提交支持
- 更新后，加载后挂钩
- 包之间的依赖关系
- 不像 [antigen](https://github.com/zsh-users/antigen), 不需要 ZSH 插件文件 (`*.plugin.zsh`)
- Interactive interface ([fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw)， 等等）
- Cache mechanism for reducing [the startup time](https://github.com/zplug/zplug#vs)

### [zpm](https://github.com/zpm-zsh/zpm)

**zpm** ( ZSH Plugin Manager ) 是一个插件管理器 [ZSH](http://www.zsh.org/) who combines the imperative and declarative approach. At first run, zpm will do complex logic and generate cache, after that will be used cache only, so it makes this framework to be very fast.

* Fastest plugin manager (Really, after the first run, zpm will not be used at all)
* Support for async loading
* Dependencies between packages
* zpm 在 Linux、macOS、FreeBSD 和 Android 上运行.
* zpm plugins are compatible with [oh-my-zsh](http://ohmyz.sh/).

### [zr](https://github.com/jedahan/zr)

**zr** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zshing](https://github.com/zakariaGatter/zshing)

**zshing** is a ZSH plugin manager similar to Vundle/Vim and allows you to...

* 在 `.zshrc` 中跟踪和配置您的插件
* 安装 ZSH 插件
* Update ZSH plugins
* Search by name all available ZSH Plugins
* Clean unused plugins up
* 在*单个命令中运行上述操作*
* 管理已安装插件的 __Source Plugins__

### [ztanesh](https://github.com/miohtama/ztanesh)

**Ztanesh** 旨在通过 ztanesh 项目提供的配置提高您的 UNIX 命令行体验和生产力：这些工具将使您的 shell 更强大且更易于使用.

### [ztheme](https://github.com/SkyyySi/ztheme)

ztheme 是一个小而快的 ZSH 主题引擎.

### [ztupide](https://github.com/mpostaire/ztupide)

一个简单快速的 ZSH 插件管理器. 它使用 zcompile 和异步加载来加快你的 shell 启动时间.

### [zulu](https://github.com/zulu-zsh/zulu)

**Zulu** 是 ZSH 5+ 的环境管理器，旨在让您无需编写任何代码即可轻松管理 shell.

* Easily manage your shell environment without editing files.
* Create aliases, functions and environment variables, and have them available to you at the next shell startup.
* Add and remove directories from `$path`, `$fpath` and `$cdpath` with simple commands.
* 轻松安装包、插件和主题，并立即提供给您.

## Setups

This section is for full setup dropins - they aren't frameworks, but they're not simple plugins/themes either.

### zgenom

* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - 使用 ZSH 的简单快速入门 [zgenom](https://github.com/jandamm/zgenom) . 这会自动配置 ZSH 以使用 [zgenom](https://github.com/jandamm/zgenom) to load a curated collection of plugins and periodically automatically update itself, the plugins, and the quickstart kit itself.

### zinit

* [ZPWR](https://github.com/MenkeTechnologies/zpwr) - 一个极其强大的自定义终端环境，建立在 [Zinit](https://github.com/zdharma-continuum/zinit) 以获得最大速度. 一个完整的终端配置框架，包括 `zsh`、`tmux`、`fzf`、`vim` 和 spacemacs 配置. 这包括：

- 11.5k+ 选项卡完成
- 1.9k+ 别名
- 330+ git aliases
- 350+ zpwr subcommands
- 2.1k 功能
- 150+ zpwr environment variables
- 170+ perl, python, bash, zsh scripts
- 2.8k line README.md
- 46k+ LOC
- 1 line install

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - 使用组合的教程 [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io), and [Tmuxinator](https://github.com/tmuxinator/tmuxinator) 以实现极其高效的开发人员工作流程.
* [Arch Linux's ZSH introduction](https://wiki.archlinux.org/index.php/zsh) - 实际上不是 Arch 或 Linux 特定的.
* [GH](https://github.com/gustavohellwig/gh-zsh)  - 在基于 debian/Ubuntu 的 linux 上设置 ZSH. 安装 [Powerlevel10k](https://github.com/romkatv/powerlevel10k), [zsh-completions](https://github.com/zsh-users/zsh-completions), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting/), and more.
* [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - A beginner-friendly tutorial on how to install and configure a ZSH shell.
* [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos 介绍 ZSH 和 oh-my-zsh 的视频.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) 涵盖了 ZSH 的一些 Bash 没有的特性，并使用了 oh-my-zsh.
* [rs-example](https://github.com/al-jshen/zshplug-rs-example) - 一个示例插件，展示了 Rust 程序如何监听和处理来自 ZSH 的命令.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
* [xVanjaZ](https://github.com/xVanjaZ/xVanjaZ-ZSH-Theme) - wrote a quick setup document for oh-my-zsh beginners showing how to use the [spaceship](https://github.com/denysdovhan/spaceship-prompt.git) 提示符、提示符处的语法高亮、自动提示和自定义 iTerm 2 主题.
* [ZSH for Humans](https://github.com/romkatv/zsh4humans) - A turnkey configuration for ZSH that aims to work really well out of the box. It combines a curated set of ZSH plugins into a coherent whole that feels like a finished product rather than a DIY starter kit.
* [ZSH Pony](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - Christian Schneider 详尽的 ZSH 技巧列表.
- [ZSH Unplugged](https://github.com/mattmc3/zsh_unplugged) - 如果您想消除使用框架但仍然可以轻松使用插件，这是一个很好的资源.

### Antigen

* [belak/zsh-utils](https://github.com/belak/zsh-utils) - A minimal set of ZSH plugins designed to be low-friction and low-complexity.
* [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis 对 Antigen 的介绍.

### Oh-My-Zsh

* [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - Dien Bui 的 oh-my-zsh 初学者指南
* [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - A beginners guide to using Oh My Zsh on macOS by Karl Hadwen
* [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders installation guide for Ubuntu
* [ZSH Gem 24](https://www.refining-linux.org/archives/59-ZSH-Gem-24-ZSH-frameworks.html)  - 2011 年 ZSH 降临日历的一部分. 涵盖 oh-my-zsh 和 zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss 关于使用 Prezto 的博文， [Tmux](https://tmux.github.io) ＆Tmuxinator.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert 关于迁移到 Prezto 的博客文章.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) - 功能丰富、速度极快的外壳设置，由 [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto), and [Zgen](https://github.com/tarjoilija/zgen).

### Zinit (né zplugin)

* [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh)  - :crystal_ball: 真棒，可定制的 Zsh 入门工具包 :stars::stars:. 在某些终端中包括电力线、`fzf` 集成、天气和图像查看.
* [zinit-configs](https://github.com/zdharma-continuum/zinit-configs) - Real-world configuration files (basically a collection of `.zshrc` files) holding [zinit](https://github.com/zdharma-continuum/zinit) 调用.

### ZSH on Windows

* [superconsole](https://github.com/alexchmykhalo/superconsole) - 仅限 Windows.

  * ConEmu/zsh 开箱即用配置为在 ConEmu 重新启动后恢复以前打开的选项卡和 shell 工作目录
  * Choose between clean and inherited environment when starting new SuperConsole sessions
  *自定义彩色方案，各种命令的彩色输出
  * MSYS2 included, `zsh` and necessary software preinstalled, uses zsh-grml-config
  * 使用 Antigen 进行 ZSH 主题和配置管理
  * 启用了许多 ZSH 插件以激活完成、突出显示和历史记录，以实现最舒适的使用
  * 为 MSYS2 环境配置了正确的 `git` 和 git lfs 支持的 Git-for-Windows 存储库，`git` 客户端已经安装.
  * `git` 的 `ssh-agent` 开箱即用，将您的密钥添加到 `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` 目录
  * 非阻塞 ZSH 提示状态更新感谢 agkozak-zsh-prompt
  * Customized for MSYS2 command-not-found handler suggests what package to install
  * 将 `nano` 设置为主编辑器，启用 `nano` 语法高亮
  * Custom helper scripts added to `ConEmu/msys64/3rdparty`

## Plugins

* [1999](https://github.com/DTan13/zsh1999)  - 电力线式主题. 包括 `git` 状态装饰、网络和电池状态.
* [256color](https://github.com/chrissicool/zsh-256color)  - 使用 256 色增强终端环境. 它查看所选的 `TERM` 环境变量，并查看是否有相应的 ncurses 的 terminfo 以及 256 种颜色可用. 结果是多色终端（如果可用）.
* [abbr (olets)](https://github.com/olets/zsh-abbr) - Manages auto-expanding abbreviations that expand inline when you hit space, inspired by fish shell.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - 提供类似于 `vim` 的缩写扩展的功能.
* [accurev](https://github.com/dalefukami/accurev-zsh) - ZSH 插件 [accurev](https://www.microfocus.com/en-us/products/accurev/overview).
* [actiona](https://github.com/matthieusb/act) - Make it easier to call [actiona](https://github.com/Jmgr/actiona) 命令行中的脚本. 包括制表符补全.
* [alacritty](https://github.com/casonadams/alacritty-shell) - Control [alacritty](https://github.com/alacritty/alacritty/wiki/Color-schemes) color schemes.
* [alehouse](https://github.com/sticklerm3/alehouse) - 包含短别名 [brew](https://brew.sh) commands, inspired by [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin).
* [alias-tips](https://github.com/djui/alias-tips) - An oh-my-zsh plugin to help remembering those aliases you defined once.
* [alias](https://github.com/xylous/alias-zsh) - Tool for managing your aliases.
* [allergen](https://github.com/stanislas/allergen) - 与 Antigen 一起使用的自定义 ZSH 插件的集合.
* [almostontop](https://github.com/Valiev/almostontop) - Clears previous command output every time before new command executed in shell. Inspired by the [alwaysontop](https://github.com/swirepe/alwaysontop) plugin for `bash`.
* [alt-and-select](https://github.com/raisty/alt-and-select)  - 将 alt-c（复制）、alt-v（粘贴）、alt-x（剪切）键盘快捷键绑定到命令：copy-region-as-kill、yank、kill-region. 将执行命令重新映射到 Alt-Shift-X.
* [ansible](https://github.com/sparsick/ansible-zsh) - 一个插件 [Ansible](https://www.ansible.com/).
* [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH 脚本帮助 `git` 变基.
* [anyframe](https://github.com/mollifier/anyframe) - ZSH 的 peco/percol/fzf 包装插件.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - 添加用于管理 Apache2 的别名和功能.
* [apparix](https://github.com/micans/apparix) - Command line directory bookmarks with jumping to bookmarks, subdirectory tab completion, distant listing etc.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - 添加 MacBook Pro 触控栏支持 [iTerm 2](https://iterm2.com).
* [appup](https://github.com/Cloudstek/zsh-plugin-appup)  - 当在当前目录（例如您的应用程序）中检测到 `docker-compose.yml` 或 `Vagrantfile` 时添加 `start`、`stop`、`up` 和 `down` 命令. 只需运行 `up` 并开始编码！
* [arc](https://github.com/anton-rudeshko/zsh-arc) - 为 Yandex 版本控制系统添加别名.
* [arduino](https://github.com/raghur/zsh-arduino)  - 添加脚本以从命令行构建、上传和监控 arduino 草图. 需要 [`jq`](https://stedolan.github.io/jq/).
* [artisan](https://github.com/jessarcher/zsh-artisan) - 用于 ZSH 的 Laravel `artisan` 插件可帮助您从项目树中的任何位置运行 `artisan`，并通过选项卡完成！
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - AsciiDoctor 的插件.
* [asdf-direnv](https://github.com/redxtech/zsh-asdf-direnv) - Integration and completions for [asdf](https://github.com/asdf-vm/asdf) and [direnv](https://github.com/asdf-community/asdf-direnv).
* [asdf](https://github.com/kiurchv/asdf.plugin.zsh) - Integration and completions for [asdf](https://github.com/asdf-vm/asdf), the extendable version manager, with support for Ruby, Node.js, Elixir, Erlang and more.
* [assume-role](https://github.com/weizard/assume-role)  - ZSH 插件可让您轻松承担 AWS IAM 角色. 包括完成.
* [async](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in ZSH without requiring any external tools. Allows you to run multiple asynchronous jobs, enforce unique jobs (multiple instances of the same job will not run), flush all currently running jobs and create multiple workers (each with their own jobs).
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - Based on the [Sublime](https://github.com/valentinocossar/sublime) 插件，可让您在其中启动文件或文件夹 [Atom](https://atom.io) 从 [iTerm 2](https://iterm2.com).
* [atuin](https://github.com/ellie/atuin)  - 用 SQLite 数据库替换你现有的 shell 历史，并为你的命令记录额外的上下文. 此外，它还通过 Atuin 服务器在机器之间提供可选且完全加密的历史同步.
* [aur-install](https://github.com/redxtech/zsh-aur-install) - Small plugin to install packages from the AUR.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) - 使用“colorls”自动列出目录.
* [auto-fortune-cowsay](https://github.com/babasbot/auto-fortune-cowsay-zsh) - 打印出一头牛的 ASCII 图片，在每个 zsh 开始时说一句随机警句.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh)  - 自动完成单词和列表选择. 最初是 y.fujii 的 incr-0.2.zsh<y-fujii at mimosa-pudica.net>  .
* [auto-ls (commanda-panda)](https://github.com/commanda-panda/zsh-auto-ls) - 自动运行 `ls` 或 `color-ls` 如果在 `cd` 上可用.
* [auto-ls (desyncr)](https://github.com/desyncr/auto-ls) - cd 到新目录时自动 `ls`.
* [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) - Automatically sends out a notification when a long running task has completed.
* [auto-nvm](https://github.com/manlao/zsh-auto-nvm) - 自动切换到给定目录中指定的节点版本.
* [autocomplete](https://github.com/marlonrichert/zsh-autocomplete) - Automatically lists completions as you type and provides intuitive keybindings for selecting and inserting them.
* [autodotenv](https://github.com/nocttuam/autodotenv) - 当您将 `cd` 放入包含 `.env` 文件的目录时，会提示您加载变量.
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) - 的扩展版本 [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) 插入.
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) - 如果一个目录包含一个`.env`文件，当你`cd`进入它时它会自动执行.
* [autojump](https://github.com/wting/autojump)  - 一个学习的 `cd` 命令 - 从命令行轻松导航目录. 安装 autojump-zsh 以获得最佳效果.
* [autopair](https://github.com/hlissner/zsh-autopair)  - 用于自动关闭、删除和跳过匹配分隔符的 ZSH 插件. 仅在 ZSH 5.0.2 或更高版本上测试.
* [autoquoter](https://github.com/ianthehenry/zsh-autoquoter) - 一个 `zle` 小部件（“zsh 插件”），它会自动在某些命令的参数周围加上引号.
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)- 类似 ZSH 的快速/不显眼的自动建议.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv)  - ZSH 插件在遍历目录时自动切换 python virtualenvs 和 pipenvs. 自动检测 pipenv 和诗歌项目.
* [autoupdate-antibody](https://github.com/spikespaz/autoupdate-antibody-zsh) - 一个叉子 [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) for the [Antibody](https://getantibody.github.io) 插件管理器，增加了配合静态加载的能力.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) - Antigen doesn't do automatic updates like oh-my-zsh. This plugin adds auto updating for antigen, both of antigen and the bundles loaded in your configuration.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - oh-my-zsh 不会自动更新非核心插件，这会将插件自动更新添加到 oh-my-zsh.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - 基于 sweharris 的 AWS CLI MFA 插件 [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa). Supports specifying mfa_device in profile.
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - Plugin for AWS MFA.
* [aws-plugin](https://github.com/pookey/zsh-aws-plugin) - Adds helper functions for `aws` command. Includes mfa and assume-role helpers.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - Boost your productivity with `aws-upload`.
* [aws-vault (blimmer)](https://github.com/blimmer/zsh-aws-vault) - 插件 [aws-vault](https://github.com/99designs/aws-vault). Includes tab completions.
* [aws-vault (reegnz)](https://github.com/reegnz/aws-vault-zsh-plugin) - 使其更易于使用 [aws-vault](https://github.com/99designs/aws-vault) 在你的环境中。
* [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) - 为版本 2 提供补全支持 [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) and a few utilities to manage AWS profiles and display them in the prompt.
* [aws](https://github.com/apachler/zsh-aws) - 从原始的 oh-my-zsh 分叉 [aws](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aws) . 包括 `awscli` 的补全和一些用于管理 AWS 配置文件并在提示中显示它们的实用程序.
* [awsume](https://github.com/Sordie/AWSume) - 可以显示当前的插件 [awsume](https://github.com/trek10inc/awsume) profile.
* [azcli](https://github.com/dmakeienko/azcli) - 使用 azure cli 工具的助手.
* [azure-keyvault](https://github.com/milespossing/Azure-Keyvault-Zsh) - 使在 cli 中使用 azure keyvaults 变得不那么冗长.
* [azure-subscription](https://github.com/dmakeienko/azure-subscription-prompt) - Displays information about the Azure current Subscription and tenant.
* [background](https://github.com/zpm-zsh/background) - 在后台执行功能的 ZSH 插件.
* [base16](https://github.com/chriskempson/base16-shell) - Adds script to allow you to change your shell's default ANSI colors but most importantly, colors 17 to 21 of your shell's 256 colorspace (if supported by your terminal). This script makes it possible to honor the original bright colors of your shell (e.g. bright green is still green and so on) while providing additional base16 colors to applications such as [Vim](https://www.vim.org).
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts) - Print random baseball related "fun facts" in your shell. Depends on `fortune` and `cowsay` being installed.
* [basex](https://github.com/dirkk/zsh-basex) - 增加了几个 [BaseX](http://basex.org/) aliases for simplified usage.
* [bash-quote](https://github.com/jtprog/bash-quote) - Get random quote from Bash.im.
* [bash](https://github.com/chrissicool/zsh-bash)  - 使 ZSH 更兼容 Bash. 它重新定义了 source 命令，使其更像 `bash`. 它还启用了 `bash` 完成.
* [battery_state](https://github.com/Jactry/zsh_battery_state) - 在右侧提示中显示电池状态.
* [bd](https://github.com/Tarrasch/zsh-bd) - 跳回特定目录，无需执行 `cd ../../..`.
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) - 为法语重新映射 ZSH `vi`-mode [bépo keyboard](http://bepo.fr/wiki/Accueil).
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) - Add more command aliases for `brew`
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - 添加帮助脚本以允许您创建 bitbucket PR 或在当前分支中打开目录.
* [bitwarden](https://github.com/Game4Move78/zsh-bitwarden) - 添加管理功能 [bitwarden](https://bitwarden.com/) 会议.
* [blackbox](https://github.com/StackExchange/blackbox) - [Stack Exchange](https://stackexchange.com)'s toolkit for storing keys/credentials securely in a `git` repository.
* [bofh](https://github.com/fundor333/bofh) - Adds functions to display random bofh fortunes.
* [bol](https://github.com/ikhurramraza/bol) - Prints a random quote when you open a terminal window.
* [boss-docker](https://github.com/bossjones/boss-docker-zsh-plugin) - 在 OSX 上管理 `docker`.
* [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) - Adds some convenience aliases for `git`.
* [branch-manager](https://github.com/elstgav/branch-manager) - 用于管理 `git` 分支的插件.
* [brew (rhuang2014)](https://github.com/rhuang2014/brew) - 独立插件 [Homebrew](https://brew.sh/) Package Manager.
* [brew (wolffaxn)](https://github.com/wolffaxn/brew-zsh-plugin) - 独立插件 [Homebrew](https://brew.sh/) Package Manager.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - 一个插件，可让您从命令行在浏览器中打开任何提交.
* [bruse](https://github.com/aubreypwd/zsh-plugin-bruse) - Makes it easy to `brew link` different versions of packages.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - 在命令行中切换 optirun 的插件.
* [c](https://github.com/sebastiangraz/c) - 添加一些 `git` 快捷方式.
* [calc](https://github.com/arzzen/calc.plugin.zsh) - ZSH 的计算器.
* [calibre-zaw-source](https://github.com/junkblocker/calibre-zaw-source) - [Calibre - E-book management](https://calibre-ebook.com/) 来源 [zaw](https://github.com/zsh-users/zaw)
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - 添加 [Can I Use...](https://caniuse.com) 支持 ZSH.
* [careful_rm](https://github.com/MikeDacre/careful_rm) - A wrapper for `rm` that adds trash/recycling and useful warnings.
* [case](https://github.com/rtuin/zsh-case) - 一个 ZSH 插件，添加了两个别名 `tolower` 和 `toupper` 来切换输出大小写.
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - A ZSH plugin to `cd` to the `git` repository root directory.
* [cd-ls](https://github.com/zshzoo/cd-ls) - 在`cd`之后自动`ls`.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) - 当 `cd`-ing 进入指定目录时显示提醒.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - 一个 ZSH 插件，用于 `cd` 到当前存储库签出的根目录.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - 当你不小心 `cd` 到服务器时，`ssh` 到服务器.
* [cdbk](https://github.com/MikeDacre/cdbk) - 一个 ZSH 插件，允许轻松创建命名目录 - 任何您想要的目录的快捷方式.
* [cdc](https://github.com/evanthegrayt/cdc)  - 更容易将目录更改为用户定义的目录列表的子目录. 包括 tab-completion、会话历史和 `pushd`、`popd` 和 `dirs` 等价物.
* [cdr](https://github.com/willghatch/zsh-cdr) - Easy setup of cdr for ZSH.
* [change-case](https://github.com/mtxr/zsh-change-case) - Plugin for fast swap between upper and lower case in your command line. :sunglasses:
* [cheatsheet](https://github.com/0b10/cheatsheet) - 用于轻松查看、创建和编辑备忘单的插件.
* [check-deps](https://github.com/zpm-zsh/check-deps)  - ZSH 插件的助手，允许他们展示如何安装任何缺少的依赖项. 如果您使用的是 Debian（以及 Ubuntu 等衍生产品）、Arch 及其衍生产品、Nodejs 和 ZSH 插件 [zpm](https://github.com/zpm-zsh/zpm) 框架.
* [chgo](https://github.com/sbfaulkner/chgo-plugin-zsh) - 修改了 chruby 的克隆，以便在多个 Go 版本之间切换.
* [clean-project](https://github.com/wwilsman/zsh-clean-project) - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories.
* [clipboard](https://github.com/zpm-zsh/clipboard)  - 添加跨平台帮助函数来访问系统剪贴板. 适用于 macOS、X11（和 Wayland）和 Cygwin.
* [cmd-status](https://github.com/BlaineEXE/zsh-cmd-status) - 报告命令的状态，包括返回码和持续时间.
* [cmdtime](https://github.com/tom-auger/cmdtime) - Displays the duration of a command to the terminal forked from the [timer](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) 插入.
* [code-review](https://github.com/xorkevin/code-review-zsh) - Launches `git difftool` on `git merge-base target_branch base_branch` and `target_branch`.
* [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - Counts keypresses and logs stats to [Code::Stats](https://codestats.net/).
* [codex](https://github.com/tom-doerr/zsh_codex) - 使您能够在命令行中使用 OpenAI 强大的 Codex AI.
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - 分叉自 [ohmyzsh/ohmyzsh/plugins/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh) . 着色 `man` 输出.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - Colorize `man` pages.
* [colorize](https://github.com/zpm-zsh/colorize) - 为各种程序的输出着色.
* [colorls](https://github.com/Kallahan23/zsh-colorls) - 为一些 colorls 函数定义了一些有用的快捷方式.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - ZSH 的增强颜色.
* [command-execution-timer](https://github.com/olets/command-execution-timer) - Displays the time an interactive shell command takes to execute.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) - A mirror of the oh-my-zsh command-not-found plugin so you don't have to include all of oh-my-zsh.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - Record complex commands and comment on them.
* [command-time](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in ZSH and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Similar to `REPORTTIME` builtin, but only outputs when user + system time >= `REPORTTIME`.
* [compe](https://github.com/tamago324/compe-zsh) - 添加完成 [nvim-compe](https://github.com/hrsh7th/nvim-compe).
* [completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script.
* [completion-zstyles](https://github.com/zshzoo/completion-zstyles) - Zstyle settings for ZSH completions based on Prezto's.
* [copier](https://github.com/zshzoo/copier) - Standalone clipboard utilities from oh-my-zsh.
* [copy-pasta](https://github.com/ChrisPenner/copy-pasta) - Copy and paste files in your terminal like you would in a GUI.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - 一个 ZSH 插件，用于通过 `ssh` 将你的 shell 配置复制到另一台机器.
* [crash](https://github.com/molovo/crash) - 为 ZSH 添加正确的错误处理、异常和 try/catch.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - ZSH syntax highlighting for the Crayon Plugin for Wordpress.
* [cros-auto-notify](https://github.com/D3STY/cros-auto-notify-zsh) - Automatically sends out a notification when a long running task has completed. Works with macOS and linux (if `hterm-notify` is installed).
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - 添加一个 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 以当前比特币价格细分.
* [crystal](https://github.com/veelenga/crystal-zsh) - 一个插件 [Crystal](https://github.com/crystal-lang/crystal).
* [czhttpd](https://github.com/jsks/czhttpd) - 一个用 99.9% 纯 ZSH 编写的简单 http 服务器.
* [declare-zsh](https://github.com/z-shell/declare-zsh)  - `.zshrc` 中的 zinit 命令解析器. 它允许从命令行对 `.zshrc` 执行以下操作 - 启用和禁用插件添加或删除片段.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - Collection of useful and fun commands to improve workflow and quality of life.
* [deer](https://github.com/Vifon/deer) - ZSH 的文件导航器深受启发 [ranger](https://ranger.github.io/).
* [defer](https://github.com/romkatv/zsh-defer)  - 推迟执行 `zsh` 命令，直到 `zsh` 无事可做并等待用户输入. 其预期目的是分阶段启动“zsh”. 它的工作原理类似于 Turbo 模式 [zinit](https://github.com/zdharma-continuum/zinit).
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools) - Simple oh-my-zsh plugin for installing the chromium depot_tools. Installing this plugin will put all of the chromium depot_tools in your path automatically.
* [dev](https://github.com/sbfaulkner/dev-plugin-zsh) - Provides a lightweight version of Shopify's internal dev tool
* [diff-so-fancy](https://github.com/z-shell/zsh-diff-so-fancy) - 安装 [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) 并使其能够在 ZSH 中使用.
* [diractions](https://github.com/AdrieanKhisbe/diractions) - 允许您将简短的逻辑/助记名称映射到目录以快速访问它们，或在其中执行操作.
* [dircolors-solarized (joel-porquet)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors 插件，带有深色或浅色终端背景选项.
* [dircolors-solarized (pinelibg)](https://github.com/pinelibg/dircolors-solarized-zsh) - Enables [Solarized Color Theme for GNU ls](https://github.com/seebi/dircolors-solarized).
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - 循环浏览目录堆栈.
* [directory-history](https://github.com/tymm/zsh-directory-history) - A per directory history for ZSH which implements forward/backward navigation as well as substring search in a directory sensitive manner.
* [direnv](https://github.com/ptavares/zsh-direnv) - 用于安装和加载的插件 [direnv](https://github.com/direnv/direnv.git). Inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv).
* [dirrc](https://github.com/gmatheu/shell-plugins) - Executes `.dirc` when present in a directory you `cd` into.
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - 用于在单行上显示 dirstack 信息的插件.
* [doas (anatolykopyl)](https://github.com/anatolykopyl/doas-zsh-plugin) - 通过按“ESC”两次，可以轻松地为当前或以前的命令添加“doas”前缀.
* [doas (senderman)](https://github.com/Senderman/doas-zsh-plugin) - 通过按“ESC”两次，可以轻松地为当前或以前的命令添加“doas”前缀.
* [docker-aliases](https://github.com/webyneter/docker-aliases) 日常使用的 Docker 别名.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) Show docker container status in your prompt.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - docker 帮助脚本的集合.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) - ZSH 的 docker-machine 插件.
* [docker-run](https://github.com/rawkode/zsh-docker-run) - Go back to running your commands "naturally", we'll handle the container.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
* [dotbare](https://github.com/kazhala/dotbare) - Interactive dotfile management with the help of `fzf`.
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - Keep your dotfiles in sync across multiple machines using `git`.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - Automagically switch to a python virtual environment located (that you previously have created with virtualenv program) in a directory named `.pyvenv` when you `cd` into a directory.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for ZSH that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drupal](https://github.com/yhaefliger/zsh-drupal) - Adds aliases for common tasks and also tab-completion for `drush`. Inspired by [Artisan](https://github.com/jessarcher/zsh-artisan).
* [dune-quotes](https://github.com/brokendisk/dune-quotes) - 随机沙丘报价生成器插件.
* [duration](https://github.com/rtakasuke/zsh-duration) - Displays command duration if it exceeds a user-settable run time.
* [dwim](https://github.com/oknowton/zsh-dwim)  - 尝试预测你下一步想要做什么. 它提供了一个键绑定（control-u），它将用您接下来要运行的命令替换当前（或上一个）命令行.
* [easy-motion](https://github.com/IngoHeimbach/zsh-easy-motion) - 一个港口 [vim-easymotion](https://github.com/easymotion/vim-easymotion) for ZSH.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - List EC2 instances and `ssh` login to the instances easily.
* [editing-workbench](https://github.com/commiyou/zsh-editing-workbench) - Adds sane, complex command line editing (e.g. incremental history word completion).
* [edward cli](https://github.com/matthieusb/zsh-edward) - Adds smart completions and alises for [edward CLI micro-service launcher](https://github.com/yext/edward).
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - Adds shortcuts for Elixir, IEX, Mix, Kiex and Phoenix.
* [emacs (cowboyd)](https://github.com/cowboyd/zsh-emacs)  - 使 Emacs 成为 CLI 操作的默认设置，例如编辑 git 提交消息； 设置方便的别名.
* [emacs (flinner)](https://github.com/Flinner/zsh-emacs) - 使用 Emacs 守护进程功能，允许用户快速打开框架，无论它们是通过 ssh 连接在终端中打开的，还是在同一主机上打开的 X 框架.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: Emoji completion on the command line.
* [emoji-fzf](https://github.com/pschmitt/emoji-fzf.zsh) - Configurable ZSH plugin for the excellent [emoji-fzf](https://github.com/noahp/emoji-fzf). It is heavily inspired by [emoji-cli](https://github.com/b4b4r07/emoji-cli).
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) - 在方便的变量中添加大量 ascii 艺术表情符号到您的环境中.
* [enhancd](https://github.com/b4b4r07/enhancd) - A simple tool that provides an enhanced `cd` command by memorizing all directories visited by a user and use it for the pathname resolution.
* [envrc](https://github.com/fabiogibson/envrc-zsh-plugin) - 如果在目录中找到 `.envrc` 文件，则自动加载和卸载环境变量.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - Quickly insert escaped backticks when double-tapping "`".
* [evalcache](https://github.com/mroth/evalcache) - 缓存二进制初始化命令的输出，以帮助减少 shell 启动时间.
* [evil-registers](https://github.com/zsh-vi-more/evil-registers) - Extends ZLE vi commands to remotely access named registers of the vim and nvim editors, and system selection and clipboard.
* [exa (DarrinTisdale)](https://github.com/DarrinTisdale/zsh-aliases-exa) - Enables a number of aliases extending [exa](https://the.exa.website), `ls` 的现代替代品.
* [exa (hermitmaster)](https://github.com/hermitmaster/zsh-exa-plugin) - 添加一些别名 [exa](https://the.exa.website), `ls` 的现代替代品.
* [exa (mohamedelashri)](https://github.com/MohamedElashri/exa-zsh) - Adds aliases for [exa](https://the.exa.website), `ls` 的现代替代品.
* [exa (ptavares)](https://github.com/ptavares/zsh-exa) - 安装和加载 [exa](https://github.com/ogham/exa.git).
* [exa (ritchies)](https://github.com/RitchieS/zsh-exa/) - 添加别名以使用 [exa](https://github.com/ogham/exa.git) 更轻松.
* [exa-ls](https://github.com/birdhackor/zsh-exa-ls-plugin) - 添加别名以便您可以使用 [exa](https://the.exa.website) 作为 `ls` 和 `tree` 的替代品.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - 一个插件 [exercism.io](http://exercism.io/).
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - 用空格扩展特定别名.
* [expand](https://github.com/MenkeTechnologies/zsh-expand) - 使用空格键扩展常规别名、全局别名、不正确的拼写和短语、glob、历史扩展和 $parameters.
* [expander](https://github.com/ianthehenry/zsh-expander) - 一个“zle”小部件，允许您编写自定义扩展器并选择它们 [fzf](https://github.com/junegunn/fzf).
* [explain-shell](https://github.com/gmatheu/shell-plugins) - 打开命令 [explainshell.com](https://explainshell.com).
* [extend-history](https://github.com/xav-b/zsh-extend-history) - Extends command history by adding exit code for each command in the history.
* [f-shortcuts](https://github.com/zpm-zsh/f-shortcuts) - 使用 F1 到 F12 键制作快捷工具栏.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - 破解版中的版本 [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of oh-my-zsh.
* [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips)  - 帮助记住您定义和忘记的别名. 移植自 [djui/alias-tips](https://github.com/djui/alias-tips).
* [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting) - 优化和改进了“zsh-users/zsh-syntax-highlighting”——更好的响应时间，可切换的高亮主题.
* [fav](https://github.com/ddnexus/fav) - ZSH/[fzf](https://github.com/junegunn/fzf) 插件，使添加和调用重要目录的命名收藏夹变得非常容易.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - Fast jumps to your favorite directories.
* [figures](https://github.com/zpm-zsh/figures) - ZSH 的 Unicode 符号.
* [firebase (Seqi)](https://github.com/Seqi/firebase-zsh) - Display the current working project or project alias when in a Firebase project directory or subdirectory.
* [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) - 在提示中添加一个指示符，表明您位于具有 `firebase.json` 文件（又名“firebase 项目”）的目录中.
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - 使 Apple 键盘的数字键能够在 ZSH 中被识别.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - 这个插件在 TYPO3 Flow 发行版的每个子目录中都可以使用 `flow` 命令.
* [fnm](https://github.com/dominik-schwabe/zsh-fnm) - 安装并加载 [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) 如果它丢失了。
* [forgit](https://github.com/wfxr/forgit) - Utility tool for `git` which takes advantage of fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [functional](https://github.com/Tarrasch/zsh-functional) - ZSH higher order functions.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH 插件用于模糊搜索文件并在匹配的行上立即打开匹配的文件.
* [fuzzy-wd](https://github.com/spodin/zsh-fuzzy-wd) - Adds fuzzy search for directories warped withe the [WD](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/wd) 插入.
* [fz](https://github.com/changyuheng/fz) - 无缝添加模糊搜索 [z](https://github.com/rupa/z)的选项卡完成，让您轻松地在历史记录中的目录之间跳转.
* [fzf (unixorn)](https://github.com/unixorn/fzf-zsh-plugin/tree/master) - Enables [fzf](https://github.com/junegunn/fzf) 历史和文件搜索.
* [fzf-fasd](https://github.com/wookayin/fzf-fasd) - 整合 [fzf](https://github.com/junegunn/fzf) and [fasd](https://github.com/clvv/fasd) --- tab completion of `z` with fzf's fuzzy search!
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - 插件有一个很酷的搜索键绑定 [fzf](https://github.com/junegunn/fzf) 和（可选） [bat](https://github.com/sharkdp/bat). Searches in the local tree of subdirectories for files.
* [fzf-history-search](https://github.com/joshskidmore/zsh-fzf-history-search) - Replaces `Ctrl+R` with an [fzf](https://github.com/junegunn/fzf)-driven history search that includes date/times.
* [fzf-it](https://github.com/micakce/fzf-it) - 使用 FZF 功能使任何命令交互式包装.
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) - Little script to create, navigate and delete bookmarks in `bash` and `zsh`, using the fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [fzf-pass](https://github.com/smeagol74/zsh-fzf-pass) - Better handling of passwords using [fzf](https://github.com/junegunn/fzf) and [pass](https://www.passwordstore.org/).
* [fzf-prezto](https://github.com/lildude/fzf-prezto) - 找到哪里的 Prezto 插件 [fzf](https://github.com/junegunn/fzf) 已安装并启用其自动完成和键绑定. 这个插件作为 Prezto `zstyle` 配置选项工作.
* [fzf-tab](https://github.com/Aloxaf/fzf-tab) - Replace ZSH's default completion selection menu with [fzf](https://github.com/junegunn/fzf).
* [fzf-utils](https://github.com/redxtech/zsh-fzf-utils) - Provides functions to kill proceses and find in path with [fzf](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - Adds some ZLE widgets for [fzf](https://github.com/junegunn/fzf).
* [fzf-z](https://github.com/andrewferrier/fzf-z) - Brings together the *z* plugin and *fzf* to allow you to easily browse recently used directories at any point on the command line.
* [fzy](https://github.com/aperezdc/zsh-fzy) - Plugin that uses [fzy](https://github.com/jhawthorn/fzy) 对于某些模糊匹配操作.
* [gcloud-project](https://github.com/avivl/gcloud-project) - 轻松选择 Google Cloud 项目.
* [gdbm](https://github.com/zdharma-continuum/zgdbm) - 添加 GDBM 作为插件.
* [geeknote](https://github.com/s7anley/zsh-geeknote) - [Geeknote](https://geeknote.me) plugin for ZSH.
* [gentoo](https://github.com/MattiaG-afk/gentoo-ohmyzsh) - Adds some aliases and functions to work with Gentoo Linux.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) datetime plugin. Shows datetime (`date` unix command) in your prompt.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to remind you to hydrate.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's npm package version.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's Rust version when either a `.rs` or `Cargo.toml` is present.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - Plugin for fast downloading jQuery library from [https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com](https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com).
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - Lets you use [zeus](https://github.com/burke/zeus) 使用普通的 rails 命令.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - Manage Go installations with gimme.
* [git-acp](https://github.com/MenkeTechnologies/zsh-git-acp) - 将当前命令行作为提交信息，然后一键运行 git pull、add、commit 和 push.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) - 轻松将上游远程添加到您的 `git` 叉.
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - 破解版中的版本 [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of oh-my-zsh.
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - 为常用的 `git` 命令组合创建许多有用的别名.
* [git-branches](https://github.com/Schroefdop/git-branches) - 制作一个 `git` 分支菜单，您可以切换到该菜单，而无需输入长分支名称.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - Enhance `git` completion to include in the remotes completion (e.g. from `git clone`) any URL in the clipboard.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - 额外的 `git` 辅助脚本打包为插件.
* [git-flow-avh](https://github.com/nekofar/zsh-git-flow-avh) - Adds short aliases for the `git-flow` commands.
* [git-fuzzy](https://github.com/bigH/git-fuzzy) - A CLI interface to `git` that relies heavily on [`fzf`](https://github.com/junegunn/fzf).
* [git-ignore](https://github.com/laggardkernel/git-ignore) - Generates `.gitignore` files from gitignore.io **offline**. `fzf`, completion, preview integrated.
* [git-is-clean](https://github.com/aubreypwd/zsh-plugin-git-is-clean) - 此函数将返回真或假，具体取决于它是否发现您的存储库是脏的.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - 添加在 GitHub 上的当前分支中打开文件夹的功能.
* [git-lfs](https://github.com/nekofar/zsh-git-lfs) - 为 git-lfs 命令添加短别名.
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - Adds some functions for `git`.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for `git` user.email.
* [git-prune (diazod)](https://github.com/diazod/git-prune) - 允许您删除已合并到本地存储库和/或已合并到远程源存储库的所有分支.
* [git-prune (seinh)](https://github.com/Seinh/git-prune) - 简化删除合并分支的插件.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) - 添加 `git-squash-branch` 和 `git-remove-merged` 命令.
* [git-secret](https://github.com/sobolevn/git-secret) - 一个 bash 工具，用于将您的私人数据存储在 `git` 存储库中.
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - 添加额外的 `git` 命令以使一些常见的 `git` 用法更有效.
* [git-sync](https://github.com/caarlos0/zsh-git-sync) - A ZSH plugin to sync `git` repositories and clean them up.
* [git-worktree](https://github.com/alexiszamanidis/zsh-git-worktree) - Wraps some `git worktree` operations for simplicity and productivity. Includes `fzf` tooling.
* [git](https://github.com/davidde/git)  - 替换股票 oh-my-zsh git 插件. 提供了不少有用的别名和函数. 替换默认插件的动机源于它带有一些不一致的事实，这使得一些流行的命令相当不直观，所以这个插件使别名保持一致.
* [gitcd (SukkaW)](https://github.com/SukkaW/zsh-gitcd) - Adds command to `git clone` a repository and `cd` into the resulting directory.
* [gitcd (viko16)](https://github.com/viko16/gitcd.plugin.zsh) - 克隆后自动 `cd` 到 `git` 工作目录.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of oh-my-zsh gitfast plugin.
* [gitgo (grimmbraten)](https://github.com/grimmbraten/gitgo) - 更容易在 `git` 分支之间切换.
* [gitgo (ltj)](https://github.com/ltj/gitgo) - 从命令行在浏览器中打开 Github/Gitlab 存储库（仅限 macOS）.
* [github](https://github.com/shakir-abdo/zsh-github-plugin) - Fork of the original [github plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/github) 嵌入 [oh-my-zsh](http://ohmyz.sh/).
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - 用于创建 `.gitignore` 文件的插件.
* [gitio](https://github.com/denysdovhan/gitio-zsh) - A ZSH plugin for generating a GitHub short URL using [git.io](https://git.io).
* [gitstatus](https://github.com/Insert-Creative-Name-Here/gitstatus.zsh) - 可以轻松地在提示中显示您的 `git` 状态.
* [gitsync](https://github.com/washtubs/gitsync) - ZSH 插件可改善一个人在多台机器上的同一存储库上开发的工作流程.
* [goenv (CDA0)](https://github.com/CDA0/zsh-goenv/blob/master/zsh-goenv.plugin.zsh) - 用于安装、更新和加载 goenv 的插件.
* [goenv (bbenne10)](https://github.com/bbenne10/goenv) - 类似于 Python 的 virtualenvwrapper 管理 `$GOPATH`.
* [going_places](https://github.com/or17191/going_places) - 一个有助于使用、创建和维护 shell 位置列表的插件.
* [golinks](https://github.com/slessans/oh-my-zsh-golinks-plugin) - Launch golinks from your terminal.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - Plugin that tries to do the right thing when it comes to setting up the GPG agent to act as an SSH agent as well on macOS.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) - ZSH 插件用于加密和解密文件或目录.
* [grep2awk](https://github.com/joepvd/grep2awk) - ZLE 小部件将 `grep` 命令转换为 `awk` 命令.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - 为 `grunt` 添加自动完成功能.
* [gsh](https://github.com/cjayross/gsh) - Collection of helper functions for `git`
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - 终端插件 [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [gtr](https://github.com/Zocker1999NET/zsh-gtr) - 允许在 git 中使用标签名称 **release-YYYY-MM-DD-HH-MM** 和标题 **Release YYYY-MM-DD HH:MM** 快速标记发布.
* [guish](https://github.com/gcarrarom/oh-my-guish) - 实用函数和别名的集合.
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - Wrapper plugin for [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
* [gunstage](https://github.com/LucasLarson/gunstage) - There are at least eight ways to unstage files in a `git` repository. This is a command-line shell plugin for undoing `git add`.
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - A gvm (Go version manager) plugin for ZSH.
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - 为“gvm”（Groovy 环境管理器）提供自动完成功能.
* [hab](https://github.com/alexdesousa/hab) - Automatically loads OS environment variables defined in the file `.envrc` if it's found when changing to a new directory.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - Outputs a hacker quote randomly when you open a terminal.
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - Adds some convenience aliases for hadoop functions.
* [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH 插件 [hanami](http://hanamirb.org) projects.
* [hangul](https://github.com/gomjellie/zsh-hangul) - Auto correct hangul(한글, korean) to english when it was supposed to be typed english. 영어를 타이핑 해야되는데 한글로 타이핑된경우 자동으로 수정합니다.
* [hbt](https://github.com/lzambarda/hbt) - Heuristic ZSH suggestion system based on past command usage.
* [hints](https://github.com/joepvd/zsh-hints) - Display glob and parameter flags and other non completable info right under your editing buffer.
* [hipchat](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell.
* [hist](https://github.com/marlonrichert/zsh-hist) - 在 ZSH 中编辑您的历史记录，无需离开命令行.
* [histdb](https://github.com/larkery/zsh-histdb)  - 将您的历史记录存储在 SQLite 数据库中. 可以与 [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions).
* [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer) - Enhances history search with more interaction and a multiline selection menu. Requires nodejs.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter)  - 允许您指定将自动排除命令插入永久历史记录的模式. 对于防止写入秘密特别有用.
* [history-here](https://github.com/leonjza/history-here) - 绑定 `^G` 以快速切换当前 shell 历史文件位置.
* [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) - 捕获 PageUp 键并使用“对话框”打开带有历史记录的弹出菜单，因此用户可以交互地浏览它并选择历史记录行以返回提示.
* [history-search-multi-word](https://github.com/zdharma-continuum/history-search-multi-word) - A syntax highlighted, multi-word history searcher for ZSH, bound to Ctrl-R, with advanced functions (e.g. bump of history entry to top of history).
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search)  - 需要在 `zsh-syntax-highlighting` 之后加载，否则它们都会中断. 您还需要将键绑定到其功能，详细信息在 README.md 中.
* [history-sync](https://github.com/wulfgarpro/history-sync) - 一个 Oh My Zsh 插件，用于使用 `git` 加密的 GPG、Internet 同步 ZSH 历史记录.
* [history](https://github.com/b4b4r07/zsh-history) - 扩展历史，使其可以被 SQL 查询.
* [hitokoto](https://github.com/derry96/hitokoto) - 显示随机报价 [hitokoto.cn](https://hitokoto.cn/).
* [homeassistant-cli](https://github.com/frosit/zsh-plugin-homeassistant-cli) - 为 [Home Assistant Command-line interface (hass-cli)](https://github.com/home-assistant/home-assistant-cli). and allows command line interaction with [Home Assistant](https://home-assistant.io/) 实例.
* [homebrew](https://github.com/digitalraven/omz-homebrew) - 插件 [homebrew](https://brew.sh) that supplements the one built into oh-my-zsh and can safely run with it enabled.
* [hooks](https://github.com/willghatch/zsh-hooks) - 添加缺少的钩子 - 用于插件和个人使用.
* [host-switch](https://github.com/LockonS/host-switch) - 在开发过程中更容易切换不同的 `/etc/hosts` 文件.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - A simple plugin for adding `hub` ci-status to your ZSH theme.
* [hub](https://github.com/soraliu/zsh-hub) - ZSH plugin for forking model.
* [igit](https://github.com/ytakahashi/igit) - Interactive `git` commands using [fzf](https://github.com/junegunn/fzf).
* [ing](https://github.com/rummik/zsh-ing) - Streamlined `ping` output.
* [instant-repl](https://github.com/jandamm/instant-repl.zsh) - 为当前 ZSH 会话中的任何命令激活 REPL.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - `cd` 的类似鱼的交互式选项卡完成.
* [iosctl](https://github.com/obayer/iosctl) - 快速访问正在运行的模拟器的应用程序、数据和日志.
* [ipip](https://github.com/SukkaW/zsh-ipip) - 插件 [IPIP](https://en.ipip.net).
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - 在iTerm2中增加了设置标签颜色的功能，可以根据cwd或正在执行的命令自动改变颜色.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - 根据当前工作目录自动更改 iTerm 2 选项卡颜色.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - 在 MacbookPro TouchBar 中显示 iTerm2 反馈（当前目录、git 分支和状态）.
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - 从命令行管理您的 iTerm 2 的配色方案.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - 设置 iTerm 2 选项卡的颜色和标题.
* [iterm2-utilities](https://github.com/decayofmind/zsh-iterm2-utilities) - Helps download various iTerm2 utilities and lets you omit cloning of the whole iterm2-website repository or relying on other repos which may be out of sync.
* [iterm2](https://github.com/laggardkernel/zsh-iterm2) - Packs iTerm's ZSH integration scripts into a ZSH plugin to avoid polluting your $HOME directory, with a negligible time increase of only 2ms.
* [jabba](https://github.com/2m/zsh-jabba) - 添加外壳集成代码和完成 [jabba](https://github.com/shyiko/jabba) Java version manager.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - Adds a `setjdk` command so you can switch easily between different versions of the jdk.
* [javaVersions](https://github.com/miguefl/javaVersions) - 使用单个命令在不同的 Java 版本之间进行更改.
* [jdk-switch](https://github.com/LockonS/jdk-switch) - 一个仅用于在 jdk 版本之间切换的 macOS 插件.
* [jenkins](https://github.com/tomplex/jenkins-zsh) - ZSH 的 jenkins 插件，深受优秀 jira 插件的启发.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - 用于延迟加载 jEnv 的 ZSH 插件.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - 添加命令 [jHipster](https://www.jhipster.tech/).
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRA tickets from the command line.
* [jq (northismirror)](https://github.com/NorthIsMirror/jq-zsh-plugin) - 交互式构建 [jq](https://stedolan.github.io/jq/) expressions to give you `jq` superpowers.
* [jq (reegnz)](https://github.com/reegnz/jq-zsh-plugin) - 交互式构建 [jq](https://stedolan.github.io/jq/) expressions.
* [jvm](https://github.com/mgryszko/jvm) - Allows selection of JDK on macOS.
* [k3d](https://github.com/dwaynebradley/k3d-oh-my-zsh-plugin) - Adds aliases and tab completions for [k3d](https://k3d.io/).
* [k](https://github.com/supercrabtree/k) - Directory listings for ZSH with `git` status decorations.
* [kctl](https://github.com/yzdann/kctl) - Add helper aliases for `kubectl`.
* [kill-node](https://github.com/vmattos/kill-node) - 用于谋杀“节点”进程系列的 ZSH 插件.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook plugin for oh-my-zsh.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
* [kube-aliases](https://github.com/Dbz/kube-aliases) - 添加函数和别名以使使用 `kubectl` 更加愉快.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - `kubectl` 的 ZSH 插件，添加当前上下文和命名空间.
* [kubecolor (devopstales)](https://github.com/devopstales/kubecolor-zsh) - Adds aliases for the `kubecolor` command.
* [kubecolor (droctothorpe)](https://github.com/droctothorpe/kubecolor) - 简化和着色`kubectl get events -w`的输出
* [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) - ZSH plugin for managing `kubectl`.
* [kubectx (ptavares)](https://github.com/ptavares/zsh-kubectx) - 安装和加载 [kubectx](https://github.com/ahmetb/kubectx).
* [kubectx (unixorn)](https://github.com/unixorn/kubectx-zshplugin) - 自动安装 [kubectx](https://github.com/ahmetb/kubectx) and `kubens`.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) - 添加 [kubernetes](https://kubernetes.io) 辅助函数和别名.
* [lando (joshuabedford)](https://github.com/JoshuaBedford/lando-zsh) - 一组别名函数，用于启用 CLI [Lando](https://docs.lando.dev) without having to type lando to access them.
* [lando (mannuel)](https://github.com/mannuel/lando-alias-zsh) - 为各种添加别名 [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) 命令.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - 提供接口 [Laradock](http://laradock.io/)'s workspace.
* [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) - 为 Laravel 6 添加别名.
* [laravel-sail](https://github.com/ariaieboy/laravel-sail) - 添加 `sail` 命令的快捷方式.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - 添加 Laravel 5、5.1、5.2 和 5.3 的快捷方式.
* [laravelx](https://github.com/rsthegeek/oh-my-zsh-laravelx) - Adds some aliases for common [Laravel](https://laravel.com/docs) 命令.
* [last-working-dir-tmux](https://github.com/Curly-Mo/last-working-dir-tmux) - Keeps track of the last used working directory globally and per tmux session and automatically jumps into it for new shells.
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) - 破解版本的副本 [oh-my-zsh](http://ohmyz.sh/). Keeps track of the last used working directory and automatically jumps into it for new shells.
* [lazyload](https://github.com/qoomon/zsh-lazyload) - Lazy load commands and speed up start up time of ZSH.
* [learn](https://github.com/MenkeTechnologies/zsh-learn) - MySQL/MariadB 中的学习集合，用于保存、查询和测验您学到的所有内容.
* [lesaint-git](https://github.com/lesaint/lesaint-git) - 替换 Oh-My-Zsh 兼容框架的 `git` 插件.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - 用于 oh-my-zsh 的 Maven 插件.
* [liferay](https://github.com/david-gutierrez-mesa/liferay-zsh) - 添加脚本 [liferay](https://github.com/liferay/liferay-portal) development.
* [linkfile](https://github.com/JaumeRF/linkfile-zsh) - Add shortcuts to your favorite directories.
* [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) - 打开终端时输出随机的 Linus Torvalds 咆哮.
* [listbox](https://github.com/gko/listbox) - Listbox element for shell.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - 允许搜索 [Sublime Text](https://www.sublimetext.com) projects and opens them in Sublime.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum) - Generate lorem ipsum text on the command line. Gets its data from [lipsum.com](https://www.lipsum.com).
* [ls](https://github.com/zpm-zsh/ls) - Colorizes the output of `ls`.
* [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack is a logging interface for shell scripts.
* [lux](https://github.com/pndurette/zsh-lux)  - ZSH 插件可通过“lux”命令切换 macOS 和其他项目和应用程序的明暗模式. 高度可定制：可以通过定义变量来配置包含的项目. 高度可扩展：可以通过定义函数来添加项目. 包括 `macos_is_dark` 辅助函数以确定 macOS 暗模式是否处于活动状态以用于主题化.
* [mac-packaging](https://github.com/Temikus/mac-packaging) - 一组用于企业 Mac 打包的常用功能 [Munki](https://www.munki.org/munki/).
* [macos (joow)](https://github.com/joow/macos) - 适用于 macOS 的 ZSH 插件.
* [macos (zshzoo)](https://github.com/zshzoo/macos) - ZSH goodies for MacOS users.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) - 使使用 Docker 和 Magento 2 变得容易.在 Magento 2 容器上加速和简化常见命令，如清理缓存、设置升级、编译 di 等等.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - 添加 `m2` 函数来运行 magento 二进制文件，添加选项卡完成.
* [magic-enter](https://github.com/zshzoo/magic-enter) - Make your enter key magical by binding a ZSH command to it.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) - A zle tweak for emulating `...'==`../..' etc.
* [markedit](https://github.com/zakariaGatter/MarkEdit) - 标记文件并使用现有标记的自动完成对其进行编辑.
* [markgate](https://github.com/zakariaGatter/MarkGate) - 允许您标记目录，以便您可以直接跳转到它们.
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - A fork of the oh-my-zsh maven plugin.
* [media-sync](https://github.com/redxtech/zsh-media-sync) - A plugin to facilitate copying media between two rclone locations.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) - 从 oh-my-zsh 中提取，因此您可以在没有 oh-my-zsh 的情况下使用它.
* [mfunc](https://github.com/hlohm/mfunc)  - 允许您动态定义持久性函数，而无需将它们添加到您的配置文件中. 这些功能永久可用，直到您将其删除.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - A ZSH plugin for switching command line between normal mode and `vi` mode.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - ZSH plugin for monorepo management.
* [monthrename](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) - Renames month names to numbers in filenames.
* [mouse-status](https://github.com/gryffyn/mouse-status) - 根据状态码更改鼠标颜色，使用 libratbag.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - Metasploit handler plugin for starting handlers easily.
* [mvn-contexts](https://github.com/artemy/zsh-mvn-contexts) - 允许在 Maven 配置之间快速切换.
* [mylocation](https://github.com/fALKENdk/mylocation) - A plugin to show your current location based on your IP address.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - Adds color for mysql tables.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with mysql.
* [n](https://github.com/gretzky/n.zsh) - 使用基于项目环境的自动切换节点版本 [n](https://github.com/tj/n).
* [namelink](https://github.com/jthat/zsh-namelink) - Provides an automatically synchronized mapping of filesystem entries (typically symbolic links) in a set of directories to their counterparts in the named directory hash.
* [navi](https://github.com/icatalina/zsh-navi-plugin/) - 插件 [navi](https://github.com/denisidoro/navi).
* [navigation-tools](https://github.com/zdharma-continuum/zsh-navigation-tools) - 添加 `htop`-like kill、目录书签浏览器、多词增量历史搜索器等.
* [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) - 从模板生成文件.
* [newvwp](https://github.com/aubreypwd/zsh-plugin-newvwp) - Spins up a new WordPress site using Valet.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - Maps exit status code to human readable string.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) - Plugin that lets you use ZSH as the default shell in a `nix-shell` environment.
* [nnvm](https://github.com/torifat/nnvm) - auto-switches node versions based on `.nvmrc`. Requires [n](https://github.com/tj/n).
* [node-env-installer](https://github.com/shiro-saber/node-env-installer) - Uses `nvm` to install new versions and modules for the current project.
* [node-path](https://github.com/andyrichardson/zsh-node-path) - 自动将当前目录的“npm bin”添加到路径中.
* [node](https://github.com/srijanshetty/node.plugin.zsh) - 用于 ZSH 的 Srijan Shetty 的 nodejs 插件，具有缓存“nvm”完成和自动加载“nvm”（如果存在）.
* [nodenv (c-uo)](https://github.com/C-uo/zsh-nodenv) - Looks for nodenv in your working directory and loads it when found.
* [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) - 自动加载 `nodenv` 及其完成到 shell.
* [nodenv (mattberther)](https://github.com/mattberther/zsh-nodenv)  - 安装、更新和加载“nodeenv”. 灵感来自 zsh-rbenv.
* [nohup](https://github.com/micrenda/zsh-nohup) - Add `nohup` to the current command pressing `Ctrl-H`.
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS users know the pain of trying to figure out what command actually flushes the DNS cache on their version of macOS, and this plugin makes that annoyance go away.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - 灵感来自 [terminal_velocity](https://www.seanh.cc/terminal_velocity/)，它提供了一个快速的接口来创建和访问一组 [Markdown](https://en.wikipedia.org/wiki/Markdown) text files inside a directory.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - Provides a quick notes editing experience in ZSH.
* [notify (luismayta)](https://github.com/luismayta/zsh-notify) - 自动安装依赖项和 r2d2 声音的 ZSH 通知.
* [notify (marzocchi)](https://github.com/marzocchi/zsh-notify) - A plugin for ZSH (on macOS and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
* [npm (igoradamenko)](https://github.com/igoradamenko/npm.插入.zsh) - Add `npm` aliases & command completion. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npm (trystan2k)](https://github.com/trystan2k/zsh-npm-plugin)  - 添加 `npm` 别名. 基于 Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npm (zfben)](https://github.com/zfben/zsh-npm)  - 使用 `n` 作为带有 `noglob` 前缀等的 `npm` 别名. 基于 Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npms](https://github.com/torifat/npms)  - 由 `fzf` 提供支持的实用程序，用于交互式使用 npm 脚本. 需要 [fzf](https://github.com/junegunn/fzf) and [jq](https://stedolan.github.io/jq/).
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - 每当您进入一个包含 `.nvmrc` 文件的目录时，都会自动调用 `nvm use`，该文件带有一个告诉 `nvm` 要使用哪个节点的字符串.
* [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy) - Plugin for lazy loading of oh-my-zsh's **nvm** plugin. It supports lazy-loading `nvm` for more than one binary/entrypoint, with the defaults being `nvm`, `node` and `npm`.
* [nvm](https://github.com/lukechilds/zsh-nvm) - 用于安装、更新和加载 `nvm` 的 ZSH 插件.
* [oath](https://github.com/alexdesousa/oath)  - 管理 2FA 身份验证 6 位令牌. 这篇文章深受启发 [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
* [oclif completion generator](https://github.com/MunifTanjim/oclif-plugin-completion) - Generates shell completions for commands lacking them.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - 把你的终端变成矩阵.
* [omz-themes-standalone](https://github.com/zshzoo/omz-themes-standalone) - 给你 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 主题而不需要 oh-my-zsh 附带的所有其他内容
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) - 在 Jetbrains 中打开/创建项目.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) - A ZSH plugin to open pull requests from command line.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - 为常见的 openshift origin (oc) 操作添加一些快捷方式.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` aliases.
* [operator](https://github.com/nivv/operator-theme) - Clean and simple theme, works best with [Menlo for Powerline](https://github.com/abertsch/Menlo-for-Powerline).
* [opp](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for ZSH.
* [opt-path](https://github.com/jreese/zsh-opt-path) - Automatically add `~/opt` subpaths to your `$PATH`.
* [osx-autoproxy](https://github.com/SukkaW/zsh-osx-autoproxy) - Configures proxy environment variables based on macOS's system preferences.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - This plugin adds some commands for maintaining various server programs on a macOS install.
* [osx](https://github.com/mwilliammyers/plugin-osx) - Add some common macOS related aliases and functions.
* [p10k-promptconfig](https://github.com/doctormemes/p10k-promptconfig) - adds the ability to easily switch between Powerlevel10k prompt theme config files by defining the `P10K_PROMPT` variable in your `.zshrc` file.
* [paci](https://github.com/iloginow/zsh-paci) - Plugin for archlinux package managers.
* [package-any-node](https://github.com/zdharma-continuum/zsh-package-any-node) - Easy installing of any Node modules inside the plugin directory, exposing their binaries via shims (i.e.: forwarder scripts) created automatically by [Bin-Gem-Node](https://github.com/zdharma-continuum/z-a-bin-gem-node) annex.
* [packer](https://github.com/BreakingPitt/zsh-packer) - Adds aliases and auto-completes for Hashicorp [packer](https://www.packer.io/).
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) - Background notifications for long running commands. Supports Elementary OS Freya.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) - 防止密码进入您的命令行历史记录.
* [path-ethic](https://github.com/sha1n/path-ethic) - Helps manage your `$PATH` quickly and easily. Doesn't touch your existing `.zshrc`, `.zprofile`, but adds on top of your existing environment instead.
* [pctl](https://github.com/ytet5uy4/pctl) - Toggle the environment variables for proxying.
* [peco-history](https://github.com/jimeh/zsh-peco-history) - 按 ctrl+R 时使用 Peco 搜索 shell 历史记录.
* [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) - 懒惰渗透测试仪的别名和功能.
* [per-directory-history](https://github.com/jimhester/per-directory-history) - Per directory history for ZSH, as well as global history, and the ability to toggle between them with `^G`.
* [percol](https://github.com/robturtle/percol.plugin.zsh) - 使用交互式和增量式搜索历史/恢复后台作业 [percol](https://github.com/mooz/percol).
* [perlbrew](https://github.com/tfiala/zsh-perlbrew/) - 安装 [perlbrew](https://perlbrew.pl/) if not already installed and initializes it for your shell.
* [pew](https://github.com/shosca/zsh-pew) - 使用设置和管理 Python virtualenvs [pew](https://github.com/berdario/pew), automatically switches virtualenvs as you move directories.
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) - 添加实用功能以使用 [PostgreSQL](https://www.postgresql.org/).
* [ph-marks](https://github.com/lainiwa/ph-marks) - 从您的终端为pornhub 视频添加书签.
* [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) - Automatically switch between php versions using [php-version](https://github.com/wilmoore/php-version) 如果目录中存在 rc 文件.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - 插件 [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) - Auto-load [phpenv](https://github.com/sptndc/phpenv) 及其完成.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - 插件 [PHPUnit](https://phpunit.de/).
* [pip-app](https://github.com/sharat87/pip-app) - 可以轻松地将 python 应用程序安装到不同的 Python virtualenvs 中，这样它们就不会与系统上的任何其他 python 要求冲突.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) - 自动 [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a pipenv project.
* [pipx](https://github.com/thuandt/zsh-pipx) - 自动完成 [pipx](https://github.com/pypa/pipx).
* [pkenv](https://github.com/ptavares/zsh-pkenv) - 安装和加载 [pkenv](https://github.com/iamhsa/pkenv.git)
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - 添加 ibtool 快捷方式以生成本地化的 XIB 文件.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Visual Studio Code 插件，一个适用于 macOS、Windows 和 Linux 的文本编辑器.
* [plugin](https://github.com/darrenbutcher/plugin)  - 从样板模板创建自定义 oh-my-zsh 插件. 非常以 oh-my-zsh 为中心，生成的插件需要编辑才能与其他框架一起使用.
* [pnpm](https://github.com/ntnyq/omz-plugin-pnpm) - 为常见的 Pnpm 命令添加有用的别名.
* [poetry (darvid)](https://github.com/darvid/zsh-poetry) - Automatically activates and deactivates [Poetry](https://poetry.eustace.io/)- 创建了 python virtualenvs.
* [poetry (sudosabin)](https://github.com/sudosubin/zsh-poetry) - 启用诗歌“$PATH”和自动补全.
* [posh-git-bash](https://github.com/lyze/posh-git-sh) - Adds `git` status in your prompt.
* [ppsmon](https://github.com/mzpqnxow/ppsmon) - Reads `/sys/class/net/$interface/` to keep track of packet transmission rates. It stores the current rate to a file in the RAM backed filesystem where it can be easily accessed for display in a shell-prompt. Linux-only due to use of `/sys`.
* [pr-cwd](https://github.com/zpm-zsh/pr-cwd) - Creates a global variable with current working directory. Plugin has integration with [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
* [pr-eol](https://github.com/zpm-zsh/pr-eol) - 显示可以嵌入到提示中的 EOL 符号.
* [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) - 添加一个变量，您可以使用它来显示上次命令运行的执行时间.
* [pr-git](https://github.com/zpm-zsh/pr-git) - 创建一个带有 `git` 状态信息的全局变量，可以在提示中显示.
* [pr-is-root](https://github.com/zpm-zsh/pr-is-root) - Sets an environment variable you can use in a custom prompt when running as root.
* [pr-jobs](https://github.com/zpm-zsh/pr-jobs) - 创建一个环境变量，可用于在自定义提示中显示后台作业信息.
* [pr-node](https://github.com/zpm-zsh/pr-node) - Sets an environment variable which can be used to display nodeJS information in a custom prompt.
* [pr-return](https://github.com/zpm-zsh/pr-return) - Plugin for ZSH who displays the exit status of the last command run.
* [presenter-mode](https://github.com/idadzie/zsh-presenter-mode)  - 在演示过程中扩展别名. 它还增加了终端窗口的对比度以增强可见性.
* [pretty-time (sindresorhus)](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
* [pretty-time (zpm-zsh)](https://github.com/zpm-zsh/pretty-time) - 将原始秒数转换为人类可读的字符串.
* [print-alias](https://github.com/brymck/print-alias) - 每当您在命令行中使用别名时，打印带有扩展别名的命令.
* [printc](https://github.com/philFernandez/printc) - Allows you to print in any color in the RGB space via a simple `printc` call.
* [profile-secrets](https://github.com/gmatheu/shell-plugins) - Securely keep sensitive variables (api tokens, passwords, etc) as part of your terminal init files. Uses gpg to encrypt/decrypt the file with your secrets.
* [project (gko)](https://github.com/gko/project) - 在本地和 github（私有或公共存储库）上创建 node/python/ruby 项目.
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - Plugin for managing projects.
* [prompt-generator](https://github.com/the10thWiz/zsh-prompt-generator) - Generates custom themes. Some generated themes require powerline-compatible fonts.
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - Quickly enable and disable proxy shell environment settings.
* [proxy](https://github.com/SukkaW/zsh-proxy) - Configure proxy settings for some package managers and software.
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - 在 ZSH 中延迟加载 `pyenv` 的插件.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy)  - 延迟加载 pyenv. 第一次调用 `pyenv` 时执行初始的 `eval &quot;$(pyenv init -)&quot;`.
* [pyenv](https://github.com/mattberther/zsh-pyenv)  - 受 zsh-rbenv 启发. 安装、更新或加载 `pyenv`，并添加额外的功能.
* [pyvenv-fast](https://github.com/ACmyles/pyvenv-fast)  - 使用一个命令启动 Python venv. 设计用于 [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv).
* [q (cal2195)](https://github.com/cal2195/q) - 将 `vim` 类宏寄存器添加到您的 ZSH shell.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - Tail/remove the temp file for [Q](https://github.com/y0ssar1an/q), the Dirty Debugging Tool.
* [qiime2](https://github.com/misialq/zsh-qiime2) - Adds functions and aliases to make working with [Quiime 2](https://qiime2.org/) 更轻松.
* [quer-ps1](https://github.com/ya0201/qwer-ps1) - 一个高度可扩展的 ZSH 提示管理器
* [quoter](https://github.com/pxgamer/quoter-zsh) - 打开新的终端会话时显示随机报价.
* [quotify](https://github.com/damofthemoon/zsh-quotify) - Displays inspiring coding quotes from our pairs when starting up.
* [randeme](https://github.com/ex-surreal/randeme) - Chooses a random theme for each session. If you not like the chosen theme you can run `randeme_rm` to never show that theme again.
* [random-quotes](https://github.com/vkolagotla/zsh-random-quotes) - Displays random quotes or facts.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - Change the colour of your [Razer Mouse](https://openrazer.github.io/) 基于最后执行的命令的状态. 需要 [OpenRazer](https://openrazer.github.io) linux drivers.
* [rbenv (ecortinas)](https://github.com/ecortinas/zsh-rbenv) - Based on the [zsh-pyenv](https://github.com/mattberther/zsh-pyenv) plugin. This plugin will install rbenv and make it readily available
* [rbenv (elliottcable)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - A faster fork of the rbenv plugin from oh-my-zsh.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - 基于原始 oh-my-zsh rbenv 插件的变体.
* [rbenv (meroje)](https://github.com/Meroje/zsh-rbenv) - 灵感来自 [https://github.com/lukechilds/zsh-nvm/](https://github.com/lukechilds/zsh-nvm/), 使得使用 ruby​​ rbenvs 更容易.
* [rc-files](https://github.com/0b10/rc-files) - Adds shortcut functions for editing various rc files.
* [recall](https://github.com/mango-tree/zsh-recall) - 使使用命令历史更容易.
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - 如果它已被删除并重新创建，则重新进入工作目录的插件.
* [reload](https://github.com/aubreypwd/zsh-plugin-reload) - Adds function to quickly reload your `.zshrc`.
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - 一个在每个提示上方显示提醒的插件.
* [replace-multiple-dots](https://github.com/momo-lab/zsh-replace-multiple-dots) - 将 `...` 转换为 `../..`
* [revolver](https://github.com/molovo/revolver) - ZSH 脚本的进度微调器.
* [riddle-me](https://github.com/vkolagotla/zsh-riddle-me) - 显示随机谜语.
* [ripz](https://github.com/jedahan/ripz) - Reminds you of your aliases, so you use them more. Depends on [ripgrep](https://github.com/BurntSushi/ripgrep).
* [robo](https://github.com/shengyou/robo-zsh-plugin) - A ZSH plugin for [Robo](https://github.com/consolidation/robo/).
* [rockz](https://github.com/aperezdc/rockz) - Lua + LuaRocks virtual environment manager based upon VirtualZ.
* [rust](https://github.com/cowboyd/zsh-rust) - 配置你的 rust 工具链，安装 [rustup](https://rustup.rs) if it is not currently installed already.
* [rvm](https://github.com/johnhamelink/rvm-zsh) - 启动 RVM 并添加在用户的 `$PATH` 中可访问的 ruby​​gem 二进制文件（如指南针）.
* [safe-kubectl](https://github.com/benjefferies/safe-kubectl) - Add some safety when running `kubectl` by warning what context you're in after a definable number of seconds since the last `kubectl` command.
* [safe-paste](https://github.com/oz/safe-paste) - A safe-paste plugin. See Conrad Irwin's [bracketed-paste](https://cirw.in/blog/bracketed-paste) 博客文章.
* [safe-rm](https://github.com/mattmc3/zsh-safe-rm) - Add safe-rm functionality so that `rm` will put files in your OS's trash instead of permanently deleting them.
* [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) - 当使用多个 AWS 配置文件时，例如您的阶段（开发、预生产、生产）的不同帐户，可用于确定当前导出的配置文件以及令牌是否仍然有效.
* [saml2aws](https://github.com/onyxraven/zsh-saml2aws) - Add support for [saml2aws](https://github.com/Versent/saml2aws).
* [sandboxd](https://github.com/benvan/sandboxd) - 仅在需要时运行设置命令（例如 `eval &quot;$(rbenv init -)&quot;` 等），通过延迟加载加速您的 `.zshrc` 和 shell 启动.
* [saneopt](https://github.com/willghatch/zsh-saneopt) - Sane defaults for ZSH options, in the spirit of vim-sensible.
* [sb-upgrade](https://github.com/redxtech/zsh-sb-upgrade) - 脚本自动更新种子箱上的应用程序.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) - Show current `chroot` name in your prompt.
* [sdkman](https://github.com/ptavares/zsh-sdkman) - 安装 [sdkman](https://github.com/sdkman) 并为其添加完成和别名.
* [sealion](https://github.com/xyproto/sealion) - Allows you to set reminders that will appear in your terminal when your prompt is refreshed.
* [search-directory-history](https://github.com/cmaahs/search-directory-history) - Allows complex search of per-directory history created using the [per-directory-history](https://github.com/jimhester/per-directory-history) 插入.
* [sed-sub](https://github.com/MenkeTechnologies/zsh-sed-sub) - Adds keybindings to do global search and replace on current command line.
* [send](https://github.com/robertzk/send.zsh) - `git add`、`git commit` 和 `git push` 的单一命令可加快 `git` 工作流程.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - 添加许多 `git` 别名和辅助 shell 函数.
* [session-sauce](https://github.com/ChrisPenner/session-sauce) - An fzf interface for tmux session creation and management for all your projects.
* [setenv](https://github.com/kalpakrg/setenv) - Runs a script when you change directories.
* [shelf](https://github.com/ecmma/shelf) -Utility which can be used to bookmark and access directly any file using mnemonics.
* [shellfirm](https://github.com/kaplanelad/shellfirm)  - Shellfirm 是一个方便的实用程序，可帮助避免在没有额外批准步骤的情况下运行危险命令. 当检测到有风险的模式时，您将立即收到一个小的提示挑战，这将双重验证您的操作.
* [show-path](https://github.com/redxtech/zsh-show-path) - 提供逐行显示`$PATH`的功能.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - 轻松启动 python `SimpleHTTPServer` 和 `SimpleHTTPSServer` 的插件.
* [skim](https://github.com/hackerchai/skim-zsh) - Adds support for [skim](https://github.com/lotabout/skim)
* [slugify](https://github.com/lashoun/slugify) - 将文件名和目录转换为网络友好格式.
* [smart-cd](https://github.com/dbkaplun/smart-cd) - Runs `ls` and `git status` after chpwd.
* [smartinput](https://github.com/momo-lab/zsh-smartinput) - When you type brackets or quotes, the corresponding end brackets/quotes are automatically added.
* [smile](https://github.com/fundor333/smile) - 添加显示随机笑脸的功能.
* [snippets](https://github.com/willghatch/zsh-snippets) - 命令行片段扩展.
* [solarized-man](https://github.com/zlsun/solarized-man) - oh-my-zsh 的插件 colour-man-pages 的修改版本，针对 [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) 终端中的主题.
* [spack](https://github.com/Game4Move78/zsh-spack) - 包括一些有用的别名和加载/卸载函数 [Spack](https://github.com/spack/spack)<i>-generated modules.</i> <b>- 生成的模块。</b> <i>As it makes use of the `module` command it is much more efficient than `spack load`.</i><b>由于它使用了 `module` 命令，它比 `spack load` 更有效。</b>
* [ssh-connect](https://github.com/gko/ssh-connect) - 一个简单的 `ssh` 管理器.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - Plugin for `ssh`.
* [sshukh](https://github.com/anatolykopyl/sshukh-zsh-plugin) - 当你 `ssh` 进入服务器时，将更新你的 `known_hosts` 文件.
* [startify](https://github.com/NorthIsMirror/zsh-startify) - Shows recently used `vim` files, shell-util files, active `tmux` sessions, recently-run `git` commands and more.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - Print the time it takes for the shell to start up.
* [stashy](https://github.com/MisterRios/stashy) - Plugin that simplifies using `git stash`.
* [statify](https://github.com/vladmrnv/statify) - 进行基本统计分析的插件.
* [sublime](https://github.com/valentinocossar/sublime) - Same as the official Sublime plugin for Oh My Zsh, but this opens files in the current Sublime window, if there is one already open.
* [sudo](https://github.com/hcgraf/zsh-sudo)  - 来自 oh-my-zsh 的 `sudo` 插件，提取为独立的. 在 emacs 模式或 vi 命令模式下按 *ESC-ESC* 在当前/上一个命令之前切换 `sudo`.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - 使用 ZSH 的后缀别名直接在 shell 中打开文件.
* [svn-n-zsh](https://github.com/khrt/svn-n-zsh-plugin) - 重写股票 oh-my-zsh svn 插件.
* [switch-git](https://github.com/robin-mbg/switch-git)  - 在 `git` 存储库之间轻松切换. 只需输入`sgr<some part of you repo's name>  `，按回车，你就在那里.
* [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) - ZSH plugin for Symfony 2 and 3.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - ZSH syntax highlighting with dircolors in realtime.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)  - 为您的 ZSH 添加语法高亮. 确保你加载了这个_before_ zsh-users/zsh-history-substring-search，否则它们都会中断.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgets without typing commands.
* [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp 为系统管理员收集的工具脚本.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard)  - 为 vi 仿真键映射的 ZLE（Zsh 行编辑器）剪贴板操作添加键绑定支持. 它适用于 Linux、macOS 和 Android（通过 Termux）.
* [systemd](https://github.com/le0me55i/zsh-systemd) - 为 `systemd` 添加了许多别名.
* [t32](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [tab-title](https://github.com/trystan2k/zsh-tab-title) - Set the terminal tab title according to current directory or running process. Forked from [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh)
* [tailf](https://github.com/rummik/zsh-tailf) - Adds `tailf` function with prefixed newlines instead of trailing newlines.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - 自动完成任务簿的任务编号.
* [terminal-app](https://github.com/the8/terminal-app.zsh) - A plugin for integrating with the new El Capitan Terminal.app features.
* [terminal-title](https://github.com/AnimiVulpis/zsh-terminal-title) - Adds a `set-term-title` function you can use to title terminal windows.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - 计算并显示通过终端运行了多少命令的插件.
* [termux](https://github.com/zpm-zsh/termux) - 增加兼容性 [Termux](https://termux.com/)
* [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) - 添加 terraform 工作区以提示.
* [terraform (jsporna)](https://github.com/jsporna/terraform-zsh-plugin)  - 使用别名和制表符完成扩展原始的 oh-my-zsh 插件. 添加工作区（非默认时）以提示.
* [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) - Add convenience aliases for [terraform](https://terraform.io/)，选项卡完成和辅助功能，以在提示中添加您的 terraform 工作区.
* [terraform (pbar1)](https://github.com/pbar1/zsh-terraform) - ZSH 的 Terraform 便利函数和别名.
* [terraform (thuandt)](https://github.com/thuandt/zsh-terraform) - Adds convenience aliases for `terraform`, along with completions for `terraform` and `terragrunt`.
* [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - 插件 [Terragrunt](https://github.com/gruntwork-io/terragrunt), a thin wrapper for [Terraform](https://terraform.io/) 提供额外的工具.
* [tfenv](https://github.com/CDA0/zsh-tfenv) - Installs, updates, and loads tfenv inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)
* [tfswitch](https://github.com/ptavares/zsh-tfswitch) - 安装和加载 [tfswitch](https://github.com/warrensbox/terraform-switcher).
* [tgswitch](https://github.com/ptavares/zsh-tgswitch) - 安装和加载 [tgswitch](https://github.com/warrensbox/tgswitch).
* [thefuck](https://github.com/laggardkernel/thefuck) - Loads [thefuck](https://github.com/nvbn/thefuck) (a tool which corrects your previous command) with cache support, which reduces the loading time dramatically.
* [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) - Convenience functions for working with [theia-ide](https://github.com/theia-ide/theia).
* [tig](https://github.com/MenkeTechnologies/zsh-tig-plugin) - Adds a few advanced bindings for [tig](https://github.com/jonas/tig) and also provides a `tig-pick` script.
* [timewarrior](https://github.com/svenXY/timewarrior) - Adds support for [timewarrior](https://timewarrior.net/), a time-tracking application.
* [tipz](https://github.com/molovo/tipz) - 如果您有刚刚运行的命令的别名，则显示您的别名，类似于 [alias-tips](https://github.com/djui/alias-tips).
* [title](https://github.com/zpm-zsh/title) - Allows you to set a terminal window title.
* [titles](https://github.com/jreese/zsh-titles) - Automatic window and tab titles for [tmux](https://tmux.github.io) and xterm-compatible terminals.
* [tm](https://github.com/kjhaber/tm.zsh) - 简化创建新 [tmux](https://tmux.github.io) sessions, attaching to existing sessions, switching between sessions, and listing active sessions.
* [tmux-auto-title](https://github.com/mbenford/zsh-tmux-auto-title) - Automatically sets the title of windows/panes as the current foreground command.
* [tmux-multisession](https://github.com/nichus/zsh-tmux-multisession) - 插件 [tmux](https://tmux.github.io) 支持单个服务器进程上的多个会话.
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - Rename [tmux](https://tmux.github.io) 窗口自动.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - Simple plugin for using [tmux](https://tmux.github.io) 与 ZSH.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - Open files in a running `vim` (or NeoVim) session, from an adjacent [tmux](https://tmux.github.io) 面包.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - 为 `tmux`、ZSH 和 Vim/NVIM 模块化创建统一的终端标题.
* [tmux](https://github.com/zpm-zsh/tmux) - 插件 [tmux](https://tmux.github.io).
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) - 具有 R-EP-L 的简单 ZSH 插件 [tmux](https://tmux.github.io) session.
* [toggl](https://github.com/natterstefan/toggl-zsh-plugin) - 添加一个“toggl-week”命令来显示跟踪的总工作时间 [toggl.com](https://toggl.com)
* [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix)  - 添加一个小部件以切换命令的前缀. 默认情况下，将 Alt+s 绑定到带有 `sudo` 的命令前缀.
* [traista](https://github.com/odgon/traista)  - 包括 `git` 状态装饰和最后一次命令运行的颜色编码退出状态. 使用深色终端主题效果更好.
* [travis](https://github.com/denolfe/zsh-travis) - Opens the Travis CI page for the current repo if one exists.
* [tre](https://github.com/redxtech/zsh-tre) - Makes using [tre](https://github.com/dduan/tre#editor-aliasing) 更轻松.
* [tsm](https://github.com/RobertAudi/tsm) - Adds a [tmux](https://tmux.github.io) 会话管理器.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) - Adds tools for macOS.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 别名.
* [ugit](https://github.com/Bhupesh-V/ugit) - 让您撤消上一次 `git` 操作.
* [uncloudium](https://github.com/Talon1024/omz-uncloudium) - 添加帮助脚本以从 Google Chrome 网上商店下载 crx 文件.
* [undollar](https://github.com/zpm-zsh/undollar) - Strips the dollar sign from the beginning of the terminal prompt.
* [unique-id](https://github.com/z-shell/zsh-unique-id)  - 在其 shell 变量 `$ZUID_ID` 中提供标识正在运行的 Zshell 会话的唯一编号. 除了这个唯一的数字之外，还提供了一个唯一的代号，在 shell 变量 `$ZUID_CODENAME` 中. 一个示例用例是将日志保存在文件 `.../mylog-${ZUID_CODENAME}.log` 中，这样两个不同的 Zshell 就不会同时写入同一个文件.
* [unix-simple](https://github.com/redxtech/zsh-unix-simple) - 显示有关 unix 简单性的图形的命令.
* [up (cjayross)](https://github.com/cjayross/up) - 一种向上浏览目录的简单方法.
* [up (peterhurford)](https://github.com/peterhurford/up.zsh) - Adds an up command to `cd` multiple levels up.
* [update-zsh](https://github.com/AndrewHaluza/zsh-update-plugin)  - 更新自定义 oh-my-zsh 插件. 仅适用于 oh-my-zsh 框架.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter)  - ZSH 语法高亮插件插件，如果 URL 以“良好”状态响应，则将其变为绿色，否则变为红色. 用于检查 URL 拼写错误.
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - 扩展原始 oh-my-zsh venv 模块的功能.
* [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) - 一个包装插件 [vagrant](https://www.vagrantup.com/) 允许从 box 目录之外调用 `vagrant` 命令. 该插件还附带了一些额外的命令，可帮助管理多个框，以及自定义选项卡完成.
* [vanilli.sh](https://github.com/yous/vanilli.sh) - shell 配置的轻量级起点.
* [vapor](https://github.com/notf0und/zsh-vapor) - 用于 zsh 的 Laravel vapor 插件，可帮助您从项目树中的任何位置运行 vapor，并具有自动完成功能！
* [vcshr](https://github.com/aubreypwd/zsh-plugin-vcshr) - 帮助 vcsh 用户需要使用 `vcsh` 的 Github 存储库，以便在 `~/.zshrc` 等中自动安装.
* [velocity](https://github.com/rahulsalvi/velocity-python) - ZSH 和基于电力线的主题元素 [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) - 一种超轻量级的克隆 [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) ; 它几乎希望您使用 [pyenv](https://github.com/pyenv/pyenv) （尽管您没有*必须*），并且因为它基于 [`venv` module](https://docs.python.org/3/library/venv.html), （创建）仅适用于 python &gt;= 3.3.
* [venv-wrapper](https://github.com/glostis/venv-wrapper) - 提供 ZSH 功能以简化使用 `venv` 的虚拟环境管理.
* [vi-increment](https://github.com/zsh-vi-more/vi-increment) - Add `vim`-like increment/decrement operations.
* [vi-mode (jeffreytse)](https://github.com/jeffreytse/zsh-vi-mode) - 💻 A better and friendly vi(vim) mode plugin for ZSH.
* [vi-mode (nyquase)](https://github.com/Nyquase/vi-mode) 添加额外的类似“vi”的功能.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - 向 ZSH 添加更多类似于 `vi` 的功能.
* [vi-motions](https://github.com/zsh-vi-more/vi-motions) - Add new motions and text objects including quoted/bracketed text and commands.
* [vi-quote](https://github.com/zsh-vi-more/vi-quote) - Add an operation which quotes or unquotes a motion.
* [viexchange](https://github.com/okapia/zsh-viexchange) - A `vi` mode plugin for easily swapping text between two places in the buffer, like vim-exchange.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) - Friendly `vi`-mode bindings, adding basic Emacs keys, incremental search, mode indicators and more.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - Allows you to do `vim filename:123` to open a file with the cursor at a specific line.
* [vimman](https://github.com/yonchu/vimman) - View `vim` plugin manuals (help) like `man` in ZSH.
* [vimto](https://github.com/laurenkt/zsh-vimto) - Improved ZSH `vi` mode (bindkey -v) plugin.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - 用于 oh-my-zsh 的修改后的 virtualenv ZSH 插件。
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt)  - 来自上游的 virtualenv 插件的一个分支. 添加了对自定义 oh-my-zsh 主题中的 virtualenv 提示的支持.
* [virtualz](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) manager inspired by Adam Brenecki's [Virtualfish](https://github.com/adambrenecki/virtualfish) for the [Fish shell](http://fishshell.com/), replaces virtualenvwrapper.
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - An oh-my-zsh plugin for the [virtuozzo](https://docs.virtuozzo.com/master/index.html) 裸机虚拟化系统.
* [visit](https://github.com/justinpchang/visit) - 用于更快导航的自定义插件.
* [volta (cowboyd)](https://github.com/cowboyd/zsh-volta) - 无缝安装和配置 [Volta](https://volta.sh) NodeJS 工具链管理器.
* [volta](https://github.com/ri7nz/zsh-volta) - 安装和加载 [ Volta: JS Toolchains as Code](https://github.com/volta-cli/volta).
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - An oh-my-zsh plugin to control [VOX](https://vox.rocks/)，一款轻量级的全功能音频播放器，适用于 macOS，可以播放包括 FLAC 和 Ogg Vorbis 在内的多种格式.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for Visual Studio Code on macOS.
* [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) - Simple plugin to open VS code a little easily across systems.
* [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) - 插件 [Visual Studio Code](https://code.visualstudio.com/).
* [vterm](https://github.com/randomphrase/vterm-zsh-plugin) - Lets you run emacs commands directly from [vterm](https://github.com/vterm/vterm) 外壳会话.
* [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) - 跟踪多少 [time](https://wakatime.com/) you have spent in your terminal. Has per project stats.
* [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) - Automatic time tracking for commands in ZSH using [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - Configures colorization with [grc](https://github.com/garabik/grc).
* [watch](https://github.com/enrico9034/zsh-watch-plugin) - Easily prefix your current or previous commands with watch by pressing `CTRL + W`.
* [watson.zsh](https://github.com/bcho/Watson.zsh) - 一个插件 [watson](https://github.com/TailorDev/Watson) time management system.
* [wd](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
* [web-search (sinetoami)](https://github.com/sinetoami/web-search) - Add commands to run bing, google, yahoo, & duckduckgo searches directly from the CLI.
* [web-search (yabanahano)](https://github.com/Yabanahano/web-search) - 添加别名以使用 Google、Wiki、Bing、YouTube 和其他流行服务进行搜索.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - 使用 `git blame` 突出显示文件中最后更改特定行的位置.
* [window-title](https://github.com/olets/zsh-window-title) - Adds informative tiles to your terminal windows.
* [windows-title](https://github.com/mdarocha/zsh-windows-title) - Dynamically updates terminal window title with current directory and the last command run.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) - 用于在项目之间跳转的简单实用程序.
* [worktree](https://github.com/jspears/worktree) - 添加包装`git worktree`的函数.
* [xdg-basedirs](https://github.com/zshzoo/xdg-basedirs) - Configure apps to use XDG base directories.
* [xxh-plugin-zsh-zshrc](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) - 插件 [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) that copies your `~/.zshrc` to a remote host and sources it with [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh).
* [yadm](https://github.com/juanrgon/yadm-zsh) - 如果有本地 yadm 配置更改，则显示警告.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - Automatically activate a directory's pip environment if `pipenv` detects the presence of one.
* [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez 的 oh-my-zsh 的 Yeoman 插件，与 yeoman 版本 ≥1.0 兼容（包括选项和命令自动完成）.
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH plugin that reminds you to use those aliases you defined.
* [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) - 添加 `yt` 别名以从 YouTube 下载视频.
* [youtube-dl](https://github.com/joow/youtube-dl) - 简单的插件 [youtube-dl](https://youtube-dl.org/).
* [yup](https://github.com/redxtech/zsh-yup) - 添加帮助函数以升级 yarn/npm 项目中的所有依赖项.
* [z.lua](https://github.com/skywind3000/z.lua)  - 一个命令行工具，可帮助您通过学习习惯来更快地导航. 一个替代方案 [z.sh](https://github.com/rupa/z) with Windows and posix shells support and various improvements. 10x faster than fasd and autojump, 3x faster than [z.sh](https://github.com/rupa/z).
* [zabb](https://github.com/Mellbourn/zabb) - `zabb` is a command that tries to figure out the shortest memorable abbreviation of a directory that is usable by [z](https://github.com/ajeetdsouza/zoxide) 明确地跳转到该目录.
* [zabrze](https://github.com/Ryooooooga/zabrze) - ZSH 缩写扩展插件.
* [zaw](https://github.com/zsh-users/zaw) - ZSH any.el-like 小部件.
* [zbrowse](https://github.com/zdharma-continuum/zbrowse) - When doing shell work, it is often the case that echo $variable is invoked multiple times, to check the result of a loop, etc. With ZBrowse, you just need to press `Ctrl-B`, which invokes the ZBrowse – Zshell variable browser.
* [zce](https://github.com/hchbaw/zce.zsh) - Vim 的 EasyMotion / Emacs 的 ZSH ace-jump-mode.
* [zcolors](https://github.com/marlonrichert/zcolors) - Uses your `$LS_COLORS` to generate a coherent theme for Git and your Zsh prompt, completions and [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [zconvey](https://github.com/zdharma-continuum/zconvey) - 添加向其他 ZSH 会话发送命令的功能，例如，您可以在所有活动的 ZSH 会话上使用它来“cd $PWD”.
* [zed](https://github.com/eendroroy/zed-zsh) - 一个简单的包装器 [z](https://github.com/rupa/z) 通过 ZSH 插件安装它.
* [zeit](https://github.com/zeit/zeit.zsh-theme) - 针对深色背景进行了优化，包括 `git` 状态信息.
* [zellij (jaeheonji)](https://github.com/jaeheonji/zsh-zellij-plugin) - Provides an environment that uses [zellij](https://github.com/zellij-org/zellij). Requires `tmux`.
* [zellij (tranzystorek-io)](https://github.com/tranzystorek-io/zellij-zsh) - 提供自动启动的环境 [zellij](https://github.com/zellij-org/zellij) 作为您终端的多路复用器.
* [zeno](https://github.com/yuki-yano/zeno.zsh) - Fuzzy completion and utility plugin powered by [Deno](https://deno.land/).
* [zero](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details.
* [zflai](https://github.com/zdharma-continuum/zflai) - A fast logging framework for ZSH.
* [zfzf](https://github.com/b0o/zfzf) - A fzf-powered file picker for ZSH which allows you to quickly navigate the directory hierarchy.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - 使 compinit 在所有加载完成后只运行一次 [zgen](https://github.com/tarjoilija/zgen).
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) - zimfw 的自定义附加功能，打包到 zimfw 插件中.
* [zinfo_line](https://github.com/kmhjs/zinfo_line) - 为 ZSH 主题提供更多信息.
* [zinit-annex-bin-gem-node](https://github.com/zdharma-continuum/zinit-annex-bin-gem-node) - [zinit](https://github.com/zdharma-continuum/zinit) extension that exposes binaries without altering `$PATH`, installs Ruby gems and Node modules and easily exposes their binaries, and updates the gems and modules when the associated plugin or snippet is updated.
* [zinit-annex-default-ice](https://github.com/zdharma-continuum/zinit-annex-default-ice) - 允许用户为多个 zinit 命令定义激活的 ice.
* [zinit-annex-man](https://github.com/zdharma-continuum/zinit-annex-man) - [Zinit](https://github.com/zdharma-continuum/zinit) 为所有插件和片段生成手册页的扩展
* [zinit-annex-meta-plugins](https://github.com/zdharma-continuum/zinit-annex-meta-plugins) - 使用单个标签安装插件组（[zinit](https://github.com/zdharma-continuum/zinit) 只要）.
* [zinit-annex-patch-dl](https://github.com/zdharma-continuum/zinit-annex-patch-dl) - [zinit](https://github.com/zdharma-continuum/zinit) 通过提供的 `dl` 和 `patch` zinit ices 下载文件和应用补丁的扩展.
* [zinit-annex-readurl](https://github.com/zdharma-continuum/zinit-annex-readurl) - Adds function to automatically download the newest version of a file to which URL is hosted on a webpage.
* [zinit-annex-rust](https://github.com/zdharma-continuum/zinit-annex-rust) - [zinit](https://github.com/zdharma-continuum/zinit) extension that that installs rust and cargo packages inside plugin directories.
* [zinit-annex-submods](https://github.com/z-shell/z-a-submods) - [zinit](https://github.com/zdharma-continuum/zinit) extenstion allows installing and managing additional submodules within a plugin or snippet.
* [zinit-annex-test](https://github.com/NorthIsMirror/z-a-test) - [zinit](https://github.com/zdharma-continuum/zinit) extension that runs tests (via make test, for example) – if it finds any of them – after installing and updating a plugin or snippet.
* [zinit-annex-unscope](https://github.com/zdharma-continuum/zinit-annex-unscope) - Allows installing plugins for [zinit](https://github.com/zdharma-continuum/zinit) 无需通过查询 Github API 指定用户名.
* [zinit-console](https://github.com/z-shell/zinit-console) - 半图形（诅咒）控制台 [zinit](https://github.com/zdharma-continuum/zinit) plugin manager.
* [zinsults](https://github.com/ahmubashshir/zinsults) - Prints insults if a command fails.
* [zjump](https://github.com/qoomon/zjump)  - 简化 ZSH 目录导航； 跳转到已经访问过的父文件夹或子文件夹.
* [zlitefetch](https://github.com/ippee/zlitefetch) - 轻量级系统信息插件.
* [zlong_alert](https://github.com/kevinywlui/zlong_alert.zsh) - Uses notify-send and ring a bell to alert you when a command that has taken a long time (default: 15 seconds) has completed.
* [zman](https://github.com/mattmc3/zman) - Use `fzf` to quickly browse Zsh manuals.
* [zoxide](https://github.com/ajeetdsouza/zoxide) - A fast alternative to `cd` that learns your habits.
* [zredis](https://github.com/zdharma-continuum/zredis)  - 添加 Redis 数据库支持，使用 `database_key` &lt;-&gt; `shell_variable` 绑定. 支持所有数据类型.
* [zsh-in-docker](https://github.com/deluan/zsh-in-docker)  - 自动将 ZSH + Oh-My-ZSH 安装到开发容器中. 适用于 Alpine、Ubuntu、Debian、CentOS 或 Amazon Linux.
* [zsh-not-vim](https://github.com/redxtech/zsh-not-vim) - 提供自动羞辱用户忘记他们没有在 vim 中的功能。
* [zsh-z (agkozak)](https://github.com/agkozak/zsh-z)  - 快速跳转到您“经常”访问的目录.  `z.sh` 的原生 ZSH 端口 - 没有 `awk`、`sed`、`sort` 或 `date`.
* [zsh-z (ptavares)](https://github.com/ptavares/zsh-z) - 安装和加载 [z](https://github.com/rupa/z.git).
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - 用于 oh-my-zsh 的 Bashmarks 端口（由 Todd Werth 编写），一个简单的命令行书签插件.
* [zshrc](https://github.com/freak2geek/zshrc) - 从您的项目范围加载本地 `.zshrc` 文件.
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - 用于在 Arch Linux 上拍摄 ZFS 升级前/升级后快照的插件.
* [zsnapshot](https://github.com/zdharma-continuum/zsnapshot) - Adds command to dump the current ZSH state into a file, for later restoration by sourcing the snapshot file.
* [ztouch](https://github.com/mjrafferty/ztouch) - Adds touchbar controls for recent history commands, directory stack, cycling between modes and user-mappable commands to the touchbar on macOS.
* [zui](https://github.com/zdharma-continuum/zui) - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH.)

## Completions

These plugins add tab completions without adding extra functions or aliases.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - Extends ZSH's \_urls completion, allowing it to complete urls from html pages.
* [aliyun](https://github.com/thuandt/zsh-aliyun) - 添加完成 [Aliyun CLI](https://github.com/aliyun/aliyun-cli).
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - viasite-ansible/ansible-server 的完成.
* [antibody-completion](https://github.com/sinetoami/antibody-completion) - 这个插件提供完成 [Antibody](https://github.com/getantibody/antibody) plugin manager.
* [appspec](https://github.com/perlpunk/App-AppSpec-p5) - Generating completions for Bash and ZSH from YAML specs
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - Completions for autopkg.
* [aws-completions](https://github.com/eastokes/aws-plugin-zsh) - 添加对 `awscli` 的完成支持以管理 AWS 配置文件/区域并在提示中显示它们.
* [aws_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) - Add completions for the aws_manager CLI.
* [bash-completions-fallback](https://github.com/3v1n0/zsh-bash-completions-fallback) - 当没有本地 ZSH 可用时，支持命令的 `bash` 完成.
* [batect](https://github.com/batect/batect-zsh-completion/) - Adds tab completions for [batect](https://batect.dev/) 构建系统.
* [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - 更好的 `npm` 选项卡完成.
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - 添加 BOSH 自动完成功能.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) - Completion plugin for homebrew services.
* [buidler](https://github.com/gonzalobellino/buidler-zsh) - Adds completion and useful aliases for NomicLabs Buidler tool [buidler.dev](https://buidler.dev).
* [bw](https://github.com/CupricReki/zsh-bw-completion) - Adds completion for [Bitwarden](https://bitwarden.com/).
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - 为 cabal 添加制表符补全.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - 为 cabal 添加自动完成功能.
* [carapace](https://github.com/rsteube/carapace) - Completion generator for Bash, Elvish, Fish, Oil, Powershell, Xonsh and ZSH. Note - not dynamic, you have to explicitly run it to generate completions for a command.
* [cargo](https://github.com/MenkeTechnologies/zsh-cargo-completion) - 原始 OMZ 货物补全的所有功能，通过 `cargo add` 中的 `cargo search` 额外支持远程板条箱.
* [carthage](https://github.com/squarefrog/zsh-carthage) - 提供补全和别名以供使用 [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) - 为所有人添加自动完成功能 [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) 命令.
* [cod](https://github.com/dim-an/cod) - `bash`/`fish`/`zsh` 的完成恶魔，当它看到你使用 `--help` 运行某些东西时，它会即时创建完成函数.
* [codeception](https://github.com/shengyou/codeception-zsh-plugin) - 为 Codeception 测试框架添加命令完成.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - 显示 git 信息，是否通过 `ssh` 登录，返回最后一个命令的代码.
* [comonicon](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) - Tab completions for [comonicon](https://github.com/Roger-luo/Comonicon.jl).
* [completions](https://github.com/zsh-users/zsh-completions) - ZSH 的额外完成集合.
* [conda](https://github.com/esc/conda-zsh-completion) - conda 的 ZSH 选项卡完成.
* [cpan](https://github.com/MenkeTechnologies/zsh-cpan-completion) - Adds `cpan install word<tab>` and `cpanm install <tab>` to complete remote CPAN package names.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - Tab completions for [ctop](https://github.com/bcicen/ctop).
* [dagger](https://github.com/jygastaud/dagger-oh-my-zsh) - Completions for dagger.
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
* [docker (chr-fritz)](https://github.com/chr-fritz/docker-completion.zshplugin) - 直接从 **Docker for Mac** 加载 `docker` ZSH 选项卡完成.
* [docker (felixr)](https://github.com/felixr/docker-zsh-completion) - 为 `docker` 添加选项卡补全.
* [docker (greymd)](https://github.com/greymd/docker-zsh-completion) - Add tab completions for `docker` and `docker-compose`.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - 命令完成 [docker-enter](https://github.com/jpetazzo/nsenter).
* [dotnet](https://github.com/MenkeTechnologies/zsh-dotnet-completion) - Dotnet tab completion.
* [dropbox](https://github.com/zpm-zsh/dropbox) - Zsh 的 Dropbox 插件，提供 `dropbox-cli` 和 `dropbox-uploader` 命令.
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - ZSH 的 Drush 自动完成功能很棒.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - A ZSH plugin for [duell](https://github.com/gameduell/duell).
* [efibootmgr](https://github.com/wehlando/efibootmgr-zsh-completion) - `efibootmgr` 的选项卡完成.
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - 添加 etcdctl 选项卡补全.
* [expressvpn](https://github.com/tk7r/zsh-expressvpn) - 为 [expressVPN](https://www.expressvpn.com/support/vpn-setup/app-for-linux/) 客户.
* [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) - Defines a function called extract that extracts the archive file you pass it, and supports a wide variety of archive filetypes.
* [extract (thetic)](https://github.com/thetic/extract) - Fork of the oh-my-zsh extract plugin.
* [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - Adds autocompletion options for all [Concourse CLI](https://www.concourse.ci/fly-cli.html) 命令.
* [fzf-gcloud](https://github.com/mbhynes/fzf-gcloud) - Fuzzy completion to navigate and preview all Google Cloud SDK `gcloud` CLI commands
* [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) - 使用 GNU Readline 为 ZSH、bash 和应用程序添加选项卡完成.
* [fzf-zsh-completions](https://github.com/chitoku-k/fzf-zsh-completions) - Fuzzy completions for [fzf](https://github.com/junegunn/fzf) and [ZSH](https://www.zsh.org/) that can be triggered by a trigger sequence that defaults to `**`.
* [gcloud](https://github.com/littleq0903/gcloud-zsh-completion) - Add completions for the Google Cloud SDK.
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - 为上游缺少补全脚本的各种 Gentoo 工具提供 ZSH 补全支持.
* [git-annex](https://github.com/Schnouki/git-annex-zsh-completion) - 允许大多数 git-annex 命令的选项卡完成.
* [git-flow](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for [git-flow](http://github.com/nvie/gitflow).
* [git-fzf](https://github.com/alexiszamanidis/zsh-git-fzf)  - ZSH 插件，包装了 `git` 操作以实现简单性和生产力. 它还包含完成并结合了对 [fzf](https://github.com/junegunn/fzf).
* [github-cli](https://github.com/sudosubin/zsh-github-cli) - github cli 的选项卡完成.
* [gitlab-runner](https://github.com/pseyfert/zsh-gitlab-runner-completion) - gitlab-ci-multi-runner 的 ZSH 完成.
* [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) - Bash and ZSH completion support for gradle.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - 对 gradle 的 ZSH 完成支持.
* [grid5000](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 插件 - 添加主题、自动补全.
* [gulp (akoenig)](https://github.com/akoenig/gulp.plugin.zsh) - Autocompletion for your gulp.js tasks in the Z-Shell (ZSH).
* [gulp (srijanshetty)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - gulp 的自动补全.
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) - Completions for [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haskell](https://github.com/coot/zsh-haskell) - 为 `cabal`、`ghc` 和 `ghc-pkgs` 命令添加补全.
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib.
* [helmfile](https://github.com/Downager/zsh-helmfile) - Adds autocompletion for `helm`.
* [inspr](https://github.com/ptcar2009/insprzsh) - Completions for [inspr](https://github.com/inspr/inspr)
* [ipfs](https://github.com/hellounicorn/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.io).
* [joe](https://github.com/corvofeng/joe-completion) - Adds completions for [joe](https://github.com/karan/joe) .gitignore 编辑器.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - jtool 的 ZSH 完成.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - 添加自动完成 [jumpstorm](https://github.com/netresearch/jumpstorm)
* [jx](https://github.com/haysclark/zsh-jx) - 为 Jenkins-X cli 添加选项卡补全.
* [kafka](https://github.com/Dabz/kafka-zsh-completions) - Completions for Apache [kafka](https://kafka.apache.org).
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - Completions for [keybase](https://keybase.io/docs/command_line).
* [kitty](https://github.com/redxtech/zsh-kitty) - Completions for [kitty](https://sw.kovidgoyal.net/kitty/) 终端模拟器.
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - 添加选项卡完成 [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - 添加选项卡完成 [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
* [kubectl-fzf](https://github.com/bonnefoa/kubectl-fzf) - Fast and powerful [`fzf`](https://github.com/junegunn/fzf)-powered autocompletion for `kubectl`.
* [lazycomplete](https://github.com/rsteube/lazycomplete) - 延迟加载 shell 完成脚本.
* [lets](https://github.com/lets-cli/lets-zsh-plugin) - 添加自动完成 [lets](https://github.com/lets-cli/lets) cli task runner.
* [ls-go](https://github.com/MohamedElashri/ls-go-zsh) - Adds some useful aliases for [ls-go](https://github.com/acarl005/ls-go).
* [mooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - completion generator for Perl module `MooseX::App`.
* [more-completions](https://github.com/MenkeTechnologies/zsh-more-completions) - 10500 个 zsh compsys 完成！
* [msfvenom](https://github.com/Green-m/msfvenom-zsh-completion) - Metasploit 的选项卡完成.
* [mx-honey](https://github.com/mukel/mx-honey) - 提供完成 [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.
* [newman](https://github.com/selop/newman-autocomplete) - Provides autocompletion for the [Newman CLI](https://github.com/postmanlabs/newman).
* [nix](https://github.com/spwhitt/nix-zsh-completions) - Completions for [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/), and [NixOps](https://nixos.org/nixops/).
* [node-ace](https://github.com/romch007/node-ace-zsh-completion) - 完成“节点王牌”.
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) - 为 nova 提供自动完成功能.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - 对“npm run”的自动完成支持。
* [nx](https://github.com/jscutlery/nx-completion) - Completions for [nx](https://nx.dev). Requires [`jq`](https://stedolan.github.io/jq/).
* [okta](https://github.com/sirhc/okta.plugin.zsh) - 提供命令行补全 [`aws-okta`](https://github.com/segmentio/aws-okta) and [okta-awscli](https://github.com/jmhale/okta-awscli) 命令.
* [op](https://github.com/sirhc/op.plugin.zsh) - Tab completions for [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) 命令行工具.
* [packer](https://github.com/wakeful/zsh-packer) - 添加选项卡完成 [packer](https://packer.io).
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc 补全插件.
* [parallels](https://github.com/benclark/parallels-zsh-plugin) - 为 Parallels 桌面添加补全.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - convenience repo to easily obtain [pass](https://www.passwordstore.org/) ZSH 的命令完成.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - Autocompletion plugin for pip.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - 为最常见的 pipenv 命令启用别名.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) - `pipenv` 的完成.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh)  - 如果该目录中有 Pipfile，则在进入目录时自动激活 **pipenv**. 包括 `pipenv` 完成.
* [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) - 为 Pivotal 的添加完成 [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
* [pmy](https://github.com/relastle/pmy) - General purpose context-aware ZSH completion engine powered by [fzf](https://github.com/junegunn/fzf).
* [quickjump](https://github.com/fikovnik/zsh-quickjump) - 添加选项卡完成支持 [skim](https://github.com/lotabout/skim) for recent files and directories using [fasd](https://github.com/whjvenyl/fasd).
* [racket completion](https://github.com/racket/shell-completion) - 完成 [Racket](http://racket-lang.org).
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets.
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) - Add completions for the Rancher CLI.
* [rhoas](https://github.com/craicoverflow/rhoas-zsh-plugin) - Adds completions for [rhoas](https://developers.redhat.com/products/red-hat-openshift-streams-for-apache-kafka/overview).
* [rustup](https://github.com/pkulev/zsh-rustup-completion) - Rustup 的选项卡完成.
* [s3cmd](https://github.com/FFKL/s3cmd-zsh-plugin) - Adds tab completions for [s3cmd](https://s3tools.org/s3cmd).
* [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion)  - Salesforce CLI 的 ZSH 命令完成. 需要 [jq](https://stedolan.github.io/jq/).
* [saml2aws](https://github.com/sirhc/saml2aws.plugin.zsh) - Adds completions for [saml2aws](https://github.com/Versent/saml2aws).
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) - autocomplete plugin for sfdx.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - 添加自动完成 [spring-boot](http://projects.spring.io/spring-boot/) 命令.
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - 管理`ssh-agent`.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - 自动启动 `ssh-agent` 以设置和加载您想要的 `ssh` 连接的任何凭据.
* [ssh](https://github.com/zpm-zsh/ssh) - 为 `ssh` 添加主机补全.
* [surf](https://github.com/beardcoder/surf.plugin.zsh) - 添加完成冲浪.
* [symphony (TheGrowingPlant)](https://github.com/TheGrowingPlant/symfony.plugin.zsh) - Symfony 3 和 4 命令的自动完成.
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - 添加完成 [Test Kitchen](https://github.com/test-kitchen/test-kitchen)).
* [tinygo](https://github.com/sago35/tinygo-autocmpl) - 为 tinygo 添加选项卡补全.
* [tmux pane words](https://gist.github.com/blueyed/6856354) - 键绑定来完成您的单词 [tmux](https://tmux.github.io) 面包.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - 添加自动完成 [tugboat](https://github.com/petems/tugboat) 命令.
* [umake](https://github.com/zlsun/umake) - 标记了 Ubuntu 的选项卡完成.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - Provides autocomplete features for the [vertx](https://vertx.io/) 命令.
* [web-open](https://github.com/AndrewHaluza/zsh-web-open) - Adds alias to open web pages. Only works with Ubuntu 20.
* [yabai](https://github.com/Amar1729/yabai-zsh-completions) - 为 macOS 添加补全 [yabai](https://github.com/koekeishiya/yabai/) tiling window manager.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - 为 `yarn add`、`yarn remove`、`yarn upgrade`、`yarn why` 和 `yarn run` 添加自动完成功能.
* [zargparse](https://github.com/ctil/zargparse) - 向它传递一个使用 `argparse` 的脚本，它会将 ZSH 完成写入您的当前目录.
* [zstyle-completions](https://github.com/zshzoo/zstyle-completions) - 给 [prezto-style](https://github.com/sorin-ionescu/prezto) completions when you hit tab.

## Themes

如果你正在使用 [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. 如果你正在使用 [zgenom](https://github.com/jandamm/zgenom), add them to your `init.zsh` with `zgenom load githubuser/reponame`.

* [000](https://github.com/Abid-Ahmad/oh-my-zsh-000-theme) - 带有用户名、主机名、完整路径、返回状态和“git”装饰的多行提示.
* [0i0](https://github.com/0i0/0i0.zsh-theme) - 针对深色终端窗口进行了优化，使用 nerdfont `git` 状态装饰.
* [14degree](https://github.com/saims0n/14degree-zsh-theme/) - 包括 `git`、`virtualenv` 和 `rvm` 状态装饰.
* [4den](https://github.com/RunThem/zsh-theme-4den) - Minimalist. Includes `git` and `hg` status decorations.
* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - 基于索林主题.
* [abbr (theme)](https://github.com/PhilsLab/abbr-zsh-theme)  - 显示当前目录路径的缩写版本，显示 Python virtualenv、Rust 版本、`git` 状态和最后一个命令的退出代码. 默认情况下适用于深色背景，但可以轻松自定义颜色.
* [absolute](https://github.com/NelsonBrandao/absolute) - Very clean looking theme with git status, node version and the exit code from the last command.
* [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) - 包括 `git` 状态装饰、AWS 配置文件名称、Azure 服务主体名称、kubernetes 上下文、terraform 工作区、命令状态和当前工作目录.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS theme, requires a Powerline-compatible font.
* [af-magic-dynamic](https://github.com/rslavin/af-magic-dynamic) - Modified version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) 动态路径缩短.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - 修改版 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 中的主题.
* [aftermath](https://github.com/schanur/aftermath) - Get a nice summary line after each command you run in your shell.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) - Based on [agnoster](https://gist.github.com/3712874) 主题包含在 [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) and [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) . 显示有关 `git` 状态的详细信息.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt) - Uses three asynchronous methods to keep the ZSH prompt responsive while displaying the `git` status and indicators of SSH connection, exit codes, and `vi` mode, along with an abbreviated, `PROMPT_DIRTRIM`-style path. Very customizable. Asynchronous even on Cygwin and MSYS2.
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - 日晒 [Agnoster](https://gist.github.com/agnoster/3712874) variant with `git` status information. Requires a unicode font and works best with a [solarized](https://github.com/altercation/solarized) terminal.
* [agnoster-fseguin](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) variant with a right prompt.
* [agnoster-gentoo](https://github.com/r7l/agnoster-gentoo-zsh-theme) - A Gentoo flavored version of the [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme) 其中包括 user@hostname 和 `git` 状态装饰. 使用 unicode 字体效果更好.
* [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) - 优化 [solarized](https://ethanschoonover.com/solarized/) 配色方案、`git` 或其他 VCS 工具以及兼容 unicode 的字体. 包括上次命令运行的状态、user@hostname、`git` 状态装饰、工作目录、是否以 root 身份运行、后台作业是否正在运行等信息.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with a right-prompt.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体优化用于 [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) terminal color scheme. Includes `git` status.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体，包括电池和在线状态.
* [agnoster-repopath](https://github.com/ivanfurlan/agnoster-repopath-theme) - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) themes. Includes `git` and `mercurial` status, current time and time the last command took decorations in the prompt.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with timestamp and newline added.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - Based on [Powerline](https://github.com/Lokaltog/vim-powerline) and [Agnoster](https://gist.github.com/agnoster/3712874) 主题和灵感来自 [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnoster](https://gist.github.com/agnoster/3712874) - Optimized for solarized terminal color schemes, shows `git` decorations, user@host, working directory, the previous command's exit status and whether you are running with root privileges. Requires a Powerline-compatible font.
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - Based on [Agnoster](https://gist.github.com/agnoster/3712874), 显示电池寿命、日期和时间、`git` 状态、当前目录以及用户和主机信息.
* [akzsh](https://github.com/awkimball/akzsh) - Works best with a dark terminal theme, includes `git` decorations.
* [alarangeiras](https://github.com/alarangeiras/alarangeiras-zsh-theme/) - Minimalist theme with `git` status decorations.
* [ale](https://github.com/alepimentel/ale-zsh)  - 基于fino主题. 包括 `git`、`virtualenv` 和 `node` 状态装饰.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) - 显示 `git` 状态的极简主义 ZSH 主题.
* [alien](https://github.com/eendroroy/alien) - Powerline-esque ZSH theme that shows `git` decorations and the exit code of the last command. Faster than many other prompts because it determines the `git` decorations asynchronously in a background process.
* [almel](https://github.com/Ryooooooga/almel) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) , 用 Rust 编写. 包括 `git` 状态、user@host、最后一个命令退出状态和工作目录装饰
* [alpharized](https://github.com/NicoSantangelo/Alpharized) - 优化工作 [solarized](http://ethanschoonover.com/solarized) 黑暗的终端. 这是修改版 [avit theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme).
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - 优雅舒适的阅读主题，基于 [Agnoster](https://gist.github.com/agnoster/3712874).
* [andy](https://github.com/andymcguinness/andys-theme) - 修改 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 具有更好的 `git` 支持的主题.
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) - Shows `git` information in the right hand prompt.
* [antoinechab](https://github.com/antoinechab/antoinechab-theme) - 包括 `git` 状态、用户名、时间和当前目录装饰.
* [antsy](https://github.com/jeffmhubbard/antsy-zsh-theme) - Shows `git` branch and status decorations, virtualenv, exit status, jobs count, and vi-mode indicator.
* [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) - 显示 `git` 装饰、用户、主机、是否为 root、活动的 Python 虚拟环境、当前的 Ruby 解释器、最后一个命令的视觉和数字状态、电源管理状态以及时间和日期.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme) - Minimalistic theme without visual noise. Displays only the necessary information: current user, hostname, working directory, `git` branch if one exists. Looks great both with dark and white terminals.
* [aplos](https://github.com/sunquan1991/aplos) - 带有工作目录、`git` 本地信息、`git` 远程信息、时间和退出代码的最小 ZSH 提示.
* [apollo](https://github.com/mjrafferty/apollo-zsh-theme) - 一个高度可定制、兼容和高性能的 ZSH 主题，它使用模块来启用功能.
* [apple (aramirol)](https://github.com/aramirol/apple-zsh-custom-themes) - Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) , 包括 `vcs` 状态装饰. 通过在 `.zshrc` 中设置变量来自定义颜色.
* [apple (bjrowlett2)](https://github.com/bjrowlett2/apple-zsh-theme) - Minimalist theme with `git` status decorations.
* [arael](https://github.com/aknackd/zsh-themes) - Fork of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [archie](https://github.com/dcavalcante/archie)  - Arch Linux 启发了 ZSH 主题. 基于 [norm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) 主题.
* [arity](https://github.com/hybras/Arity-Zsh-Theme)  - Arity 是一个简单的主题，旨在提高可读性并一目了然. 包括路径和 `git` 装饰.
* [aronhoyer](https://github.com/aronhoyer/zsh-theme) - 带有右侧“git”状态装饰的极简主义主题.
* [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - 带有 `git` 装饰的最小 ZSH 主题.
* [asciigit](https://github.com/cemsbr/asciigit) - An ASCII-only theme for `git` users who don't want to use fonts with extra glyphs.
* [asq](https://github.com/AugustoQueiroz/asq-theme) - Based on [theunraveler](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#theunraveler).
* [astral](https://github.com/xwmx/astral) - Theme for dark backgrounds with zen mode. Works well with the zsh-users [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) 插入.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - 基于`ys`和 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 主题.
* [async](https://github.com/mje-nz/zsh-themes) - Shows current directory, `git` state, return value of last command if it had an error code, number of background jobs, execution time of long-running commands, current python virtualenv.
* [aub](https://github.com/FraSharp/aub) - 包括 `git` 和 `hg` 状态以及 `host` 中的 `username` 的装饰.
* [aterminal](https://github.com/guiferpa/aterminal) - 在提示符中显示 Nodejs、NPM、Docker、Go、Python、Elixir 和 Ruby 信息.
* [avil](https://github.com/avil13/avil-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) - Based on the oh-my-zsh [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme, with small changes.
* [avit-mod](https://github.com/zlsun/avit-mod) - 修改版 oh-my-zsh&#39;s [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) 主题.
* [banana](https://github.com/sorcererxw/banana-zsh-theme) - 包括 `git` 状态装饰和当前目录.
* [bandit](https://github.com/Holger-Will/zsh_bandit) - 另一个电力线变体.
* [bar (anki-code)](https://github.com/anki-code/bar-theme) - Minimalist settings for [p10k](https://github.com/romkatv/powerlevel10k).
* [bar (xp-bar)](https://github.com/xp-bar/zsh-bar-theme) - 包括用户名、主机、密码、`git` 状态装饰和 3 小时饮水提醒.
* [barion](https://github.com/SEbbaDK/barion) - A fast compiled prompt with a compact `git` status overview. Reminiscent of powerline. Requires [Crystal](https://crystal-lang.org/) 建造.
* [bash](https://github.com/starseekist/bash-zsh-theme) - 看起来像默认的 `bash` 提示.
* [bashi](https://github.com/eli-oat/bashi) - 针对 Ahmet Sülek 的优化 [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) theme and Pasquale D'Silva's [Saturn Terminal](https://github.com/psql/saturn-colors) 主题.
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - Modified version of [gitster](https://github.com/zimfw/gitster) 主题为 [ZIM](https://github.com/zimfw/zimfw).
* [bearable](https://github.com/JanmanX/bearable-zsh) - Works well with dark terminal backgrounds.
* [bedbugs](https://github.com/justino/zsh-theme-bedbugs) - 灵感来自 [Agnoster](https://gist.github.com/agnoster/3712874), this multiline prompt includes `git` status information, background job count, working directory, user and hostname, Python virtualenv when present, colored return value of last command and root/user sigil.
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - 灵感来自 [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme)，但带有啤酒图标.
* [bender](https://github.com/specious/bender) - Fancy two-line prompt with git integration.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with unicode symbols baked in.
* [biraSkull](https://github.com/Shahryar-Pirooz/biraSkull.zsh-theme) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), 包括根状态和 `git` 状态装饰.
* [biradate](https://github.com/vemonet/zsh-theme-biradate) - Based on the [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme, but displays the date instead of the username in the prompt.
* [birame](https://github.com/maniat1k/birame) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [birav2](https://github.com/shahid64/birav2-theme) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) . 包括 `git`、`rvm` 和 `virtualenv` 状态装饰.
* [bklyn](https://github.com/gporrata/bklyn-zsh) - 变体 [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) with customizations applied.
* [black-Void](https://github.com/black7375/BlaCk-Void-Zsh) - 包括帐户信息、root 用户、使用 ssh、目录注册、写入权限、vcs 信息装饰.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) - 另一个 `git`-aware 主题.
* [blazux](https://github.com/blazux/omz-theme) - 包括 `git` 状态装饰和最后一个命令退出状态的笑脸/悲伤脸指示器.
* [blinks (max13ft)](https://github.com/max13fr/blinks.zsh-theme) - 为 oh-my-zsh 添加了 mercurial 支持 [blink](https://github.com/max13fr/blinks.zsh-theme) 主题.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) - 基于现有主题 [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme).
* [bliss](https://github.com/joshjon/bliss-zsh)  - 一个精致的主题，在不压倒您的工作空间的情况下注入色彩. 设计用于与 [bliss iTerm](https://github.com/joshjon/bliss-iterm) 配色方案和 [bliss dircolors](https://github.com/joshjon/bliss-dircolors) . 包括 `git` 状态装饰.
* [blokkzh](https://github.com/KorvinSilver/blokkzh) - 基于 oh-my-zsh 的内置主题 [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 主题. 需要支持 unicode 的字体.
* [blox](https://github.com/yardnsm/blox-zsh-theme)  - 一个最小且快速的 ZSH 主题，向您展示您的需求. 它由块组成：每个块都显示在一对\[方括号\]内，您可以通过简单地创建一个函数来添加块.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - 最小的主题，显示 `git` 信息.
* [bluelines](https://github.com/apbarrero/bluelines) - 清晰的蓝色主题.
* [bluo](https://github.com/varunpbardwaj/bluo) - Col或者ful prompt segments reminiscent of [bullet-train](https://github.com/caiogondim/bullet-train.zsh) 或者 [powerlevel10k](https://github.com/romkatv/powerlevel10k). Includes `git` status dec或者ations.
* [bogo](https://github.com/cubasepp/zsh-bogo-theme) - 灵感来自 [zeta](https://github.com/skylerlee/zeta-zsh-theme). Includes `git` and ruby version decorations.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - Multiline theme, best on dark backgrounds.
* [bougenville](https://github.com/bougenville/zsh-theme) - 变体 [dallas](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dallas.zsh-theme).
* [bronze](https://github.com/reujab/bronze) - A cross-shell customizable powerline-like prompt with icons written in go. Requires [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
* [brs](https://github.com/evenhold/brs-zsh-theme) - 使用 `audtool` 在提示中显示当前歌曲.
* [bruh](https://github.com/haze/bruh) - Includes `git` status decorations.
* [brunty](https://github.com/Brunty/omz-brunty) - 布鲁蒂主题.
* [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) - Inspired by the [powerline](https://github.com/Lokaltog/vim-powerline) and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 主题.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF 颜色主题.
* [bubblegum](https://github.com/ice-bear-forever/bubblegum-zsh) - 极简主义亮粉色主题，带有三角形字形和您的工作目录，仅此而已 - 为您提供最干净的外壳.
* [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) . 最适合搭配 [nerdfonts](https://github.com/ryanoasis/nerd-fonts).
* [bubblified (varaki)](https://github.com/varaki/bubblified-varaki.zsh-theme) - Based on [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) . 生根时变色.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh)  - 灵感来自 Powerline Vim 插件. 它旨在简化，仅在相关时显示信息.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH theme, modified to just display time and directory.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - 简单、干净、漂亮的主题.
* [bureau-env](https://github.com/angus-lherrou/bureau-env) - 修改 Oh-My-Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) 将 Python 虚拟环境标签添加到 `git` 块左侧的主题.
* [bureau-parrot](https://github.com/BenjaminGuzman/bureau-parrot) - Based on [bureau](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme). Includes `git` decorations.
* [bureau](https://github.com/isqua/bureau)  - 清晰且内容丰富的两行提示. 包括为大型存储库优化的 git status.
* [buster](https://github.com/grantbuster/buster_zsh_theme)  - 与 WSL2 配合得很好. 基于 oh-my-zsh 的 Fox 和 Jonathan 主题.
* [cactus](https://github.com/welksonramos/cactus) - Minimalist theme with `git` status decorations.
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - Light version of the candy theme.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - 在提示中显示活动的 Python 版本和 `git` 装饰.
* [celestialorb](https://github.com/celestialorb/zsh-theme)  - 受@celestialorb 启发的电力线主题. 包括 `git` 状态装饰、Kubernetes 集群信息（如果有）、当前 AWS 配置文件和区域以及活动的 virtualenv.
* [cf-ps1](https://github.com/mdan16/cf-ps1) - Displays the current foundation and organization and space of [Cloud Foundry](https://www.cloudfoundry.org/) in your prompt.
* [ch4rli3](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) - Lean and simple theme.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme) - Based on sorin. Shows the current active versions of Java, Scala, Go, Node, Python and Ruby.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme)  - Oh-My-Zsh 的一个小巧而美丽的主题，没有任何多余的东西. 包括 `git` 状态装饰.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) - 优化的 ZSH 提示 [solarized](https://github.com/altercation/solarized) 黑暗的终端主题.
* [chello](https://github.com/Abdalla981/chello)  - 适用于深色背景. 依赖于取决于 [autojump](https://github.com/wting/autojump), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) and [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [chi](https://github.com/akinjide/chi) - 针对 macOS 上的 iTerm 2 用户优化的 ZSH 主题.
* [chill](https://github.com/JKerboeuf/chill.zsh-theme) - Has decorations for the current working directory, last command exit status and `git` status.
* [chinipage](https://github.com/andresemartinez/chinipage-zsh-theme) - Minimalist theme that includes `git` decorations. Requires powerline-compatible fonts and the [git-prompt](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git-prompt) 插入.
* [chrisandrew.cl](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme) - Includes `git` decorations. Requires powerline-compatible terminal font.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - 显示时间戳、大换行符、git 分支和状态.
* [clarity](https://github.com/nbitmage/clarity.zsh) - 专为简单性和可扩展性而设计.
* [classyTouchName](https://github.com/dylanroman03/classyTouchName) - Oh-my-zsh 主题灵感来自 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) . 在深色背景下效果更好. 包括 `git` 状态装饰.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - 带有 `git` 支持的最小、干净的主题.
* [clean (akz92)](https://github.com/akz92/clean) - Minimalist ZSH theme.
* [clean (brandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - 极简主义的变体 [pure](https://github.com/sindresorhus/pure). Pure is not clean, clean is not pure.
* [clean (patr1ot)](https://github.com/Patr1ot/clean.zsh-theme) - Fork of the upstream [clean](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) 添加了主机信息.
* [cleansh](https://github.com/diegoos/cleansh)  - 极简主义，包括 `git`、Ruby、node 和 Python 版本状态装饰. 适用于标准字体.
* [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) - minimalist theme with `git`, nix-shell and virtualenv status decorations.
* [cloudy](https://github.com/Huvik/Cloudy) - Minimal cloudy ZSH theme.
* [clover](https://github.com/tzing/clover.zsh-theme) - 灵感来自 [zeta](https://github.com/skylerlee/zeta-zsh-theme) and [pure](https://github.com/sindresorhus/pure).
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - Configuration file for [cmder](http://cmder.net/) 配置为使用 ZSH 和修改后的地震模式工作 [Agnoster](https://gist.github.com/agnoster/3712874) 主题.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) - 一个与 Cmder 主题相匹配的 ZSH 主题，Cmder 是一个流行的 windows 终端模拟器.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos 的 ZSH 和 iTerm 2 的 Cobalt 2 主题.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) - 带有 `git` 扩展的 Cobalt 2 主题.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Codemachine 主题.
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - 灵感来自 [bashi](https://github.com/eli-oat/bashi), 在你的提示中包含一个猴子和 `git` 信息.
* [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - 基于 agnoster，但对 vi 模式有一个正确提示，以电力线外观显示 `--INSERT--` 和 `--NORMAL--`.
* [coldark](https://github.com/ArmandPhilippot/coldark-zsh-theme) - A blue-grey theme designed for reading comfort. Includes `git` decorations.
* [collon](https://github.com/lambdalisue/collon.zsh)  - 带有“git”状态装饰、cwd、时间、主机、最后一个命令的退出状态的轻量级主题. 不需要特殊字体.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - 允许按主机提示着色，显示 `rvm`、`virtualenv` 和 `git` 信息.
* [common](https://github.com/jackharrisonsherlock/common) - A simple, clean and minimal prompt, displays current working directory, hostname, AWS vault role, background jobs, current SHA, exit code of last command, and `git` branch and status.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - 针对深色背景优化的色彩鲜艳的主题.
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) - Clean and effective ZSH theme with git and npm support.
* [cramin](https://github.com/FelipeCRamos/craminzsh) - Minimal interface with support for github plugins, based on [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [cryo](https://github.com/cryocaustik/cryo-zsh-theme) - 添加日期和时间的原始 oh-my-zsh 主题的独立克隆.
* [crème fraîche](https://github.com/koenwoortman/creme-fraiche-zsh-theme) - 最适合轻终端背景，包括 `git` 和 `vi`-mode 状态装饰.
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 Powerline Vim 插件的带有可爱表情符号的 macOS oh-my-zsh shell 主题.
* [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) - 在深色背景下效果很好，有 `git` 状态装饰.
* [cypher-ruby](https://github.com/ston1x/cypher-ruby) - 如同 [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) 但包括活动的 Ruby 版本.
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) with [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 容器中的主题.
* [daily](https://github.com/ghlin/zsh-theme-daily) - Includes `git` and `ssh` status decorations.
* [damino](https://github.com/njdom24/Damino-Zsh-Theme) - Minimal powerline-esque theme with `git` decorations.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) - Informative, minimal, and, above all, X-Men themed.
* [daniloheraclio](https://github.com/daniloheraclio/daniloheraclio-zsh-theme) 灵感来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme. Has `git` and last command exit status decorations. Requires a nerdfont to render properly.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - 这个版本的流行 [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) 主题已通过近乎完整的重写实现模块化和一些新功能得到增强.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - 基于`ys`和 [astro](https://github.com/iplaces/astro-zsh-theme) 主题.
* [dbern](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) - 包括电池状态和负载平均装饰.
* [delta (asavoy)](https://github.com/asavoy/delta-zsh-theme) - Minimal ZSH theme to reduce distractions. Includes an iTerm color settings file.
* [delta (dongri)](https://github.com/dongri/delta-zsh-theme) - Another minimal theme with embedded `git` status.
* [delta-prompt](https://github.com/cusxio/delta-prompt) - A minimal ZSH prompt.
* [destiny](https://github.com/ja1dan/Destiny)  - 一个简单、可配置的 ZSH 提示，没有依赖关系.  Destiny 已经在 Linux、macOS 和 iOS 上进行了测试.
* [devj121](https://github.com/DevJ121/devj121-zsh-theme) - 包括带有分支字形的 `git` 装饰.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) - A theme with an emphasis on the right side (hence the name) of the terminal.
* [dino](https://github.com/OdilonDamasceno/dino-zsh-theme)  - 包括 node、golang、flutter、lua、python 和 java 的装饰，还包括 `git` 装饰. 需要书呆子字体.
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - 带有自定义 LSCOLORS 和 LS_COLORS 设置文件，适用于深色和浅色终端主题.
* [diy-ys](https://github.com/aprilnops/zsh-theme) - 变体 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 没有主机名或时间.
* [dkniffin](https://github.com/dkniffin/zsh-theme) - 包括 `ruby` 版本和 `git` 状态.
* [dmx](https://github.com/domix/dmx.zsh-theme) - Optimized for dark terminal windows.
* [doodleshell](https://github.com/cdodd/doodleshell-zsh-theme) - 极简主题，包括 `git`、`terraform` 和 `aws` 状态装饰.
* [dp](https://github.com/davidparsson/zsh-dp-theme) - Low contrast theme that shows current git branch, if the repository is dirty and the value of `$PYENV_VERSION`.
* [dr4kk0nnys_v2](https://github.com/Dr4kk0nnys/Dr4kk0nnys_theme_ohmyzsh_v2/) - Works well on dark backgrounds, includes `git` status decorations.
* [dracula](https://github.com/dracula/zsh) - Atom、Alfred、Chrome DevTools、iTerm 2、Sublime Text、Textmate、Terminal.app、Vim、Xcode 和 ZSH 的深色主题.
* [dragon (jeop10)](https://github.com/jeop10/dragon) - Inspired by kali linux. Includes `git` status and working directory decorations.
* [dragon (sabertaximi)](https://github.com/sabertazimi/dragon-zsh-theme) - 简约，包括 `git` 状态信息.
* [drkat](https://github.com/katrinaalaimo/drkat-zsh-theme) - Reminiscent of [Powerline](https://github.com/powerline/powerline). Includes directory, `git` status, and hostname decorations.
* [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) 变体.
* [dtheme](https://github.com/OlukaDenis/DTheme)  - 针对使用日晒终端配色方案和“git”的人进行了优化. 最适合使用 unicode 字体.
* [duckster](https://github.com/ducky/duckster) - 一个叉子 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ZSH 主题更新鲜.
* [ducula](https://github.com/janjoswig/Ducula) - Inspired by Dracula project. Includes `git` status decorations, username and hostname abbreviations, virtual environment, current working directory, return status of last command and the time.
* [dustmod](https://github.com/bmihaila/dustmod) - Derived from the [dst](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) oh-my-zsh 中的主题.
* [dzhi](https://github.com/pentago/dzhi-zsh-theme) - Optimized for people using [Nord](https://www.nordtheme.com/) . 包括 `git` 状态装饰.
* [eckig](https://github.com/fouladi/eckig) - Minimalist theme with utf-8 icons. Includes `git` status decorations and a clock.
* [eggshausted](https://github.com/inutano/eggshausted) - A `git`-aware theme for people who are tired of getting errors.
* [eivmosn](https://github.com/eivmosn/eivmosn-omz) - 修剪了“ys”主题的变体.
* [eleastic](https://github.com/jinseobhong/eleastic-zsh-theme) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme), optimized for solarized terminal theme, includes `git` status decorations. Requires powerline-compatible font.
* [elessar](https://github.com/fjpalacios/elessar-theme) - 基于 `git` 的主题 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme). Requires a Powerline-compatible font.
* [elm](https://github.com/gacallea/elm-zsh-theme) - Includes `git` status, user@host, date, time and path decorators.
* [elsa](https://github.com/faycito/elsa) - Includes root status, pwd and `git` status decorations.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - Emoji flavored [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ohmyzsh/ohmyzsh) 主题.
* [emoji](https://github.com/masaakifuruki/emoji.zsh-theme) - Based on  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 主题，将 `git` 提示符号替换为表情符号，以提高清晰度.
* [emojirussell](https://github.com/Bergiu/emojirussell) - Based on  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 主题，带有当前工作目录的状态装饰，最后一个命令退出状态，`git` 分支和状态.
* [endless-dog](https://github.com/qwelyt/endless-dog) - oh-my-zsh-compatible theme that mimics grml-zsh-config.
* [enlightenment](https://github.com/w33tmaricich/enlightenment) - 包括 `git` 状态、`vi`-mode 指示器和最后一个命令执行时间的装饰.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - Takes up an enormous amount of space in the terminal.
* [erfan](https://github.com/ekm507/erfan-zsh-theme) - Combination of the of [af-magic](https://github.com/andyfleming/oh-my-zsh) and [macovsky](https://github.com/championswimmer/oh-my-zsh/blob/master/themes/macovsky.zsh-theme) 主题. 包括 `git` 和 `virtualenv` 状态装饰.
* [eriner](https://github.com/zimfw/eriner) - A Zim fork of the Powerline-inspired [agnoster](https://github.com/agnoster/agnoster-zsh-theme) prompt theme. Includes `git` status decorations.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - 一个带有 `git` 信息的简单主题.
* [eucalyptus](https://github.com/relastle/eucalyptus) - 简约的 vi 模式用户的简单单行主题，灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory and current path.
* [excess](https://github.com/davydovanton/excess.zsh-theme) - 简单的 ZSH 颜色主题.
* [ez-pz](https://github.com/mangosmoothie/ez-pz) - 带有“git”状态装饰的极简主义主题，灵感来自 [bureau](https://github.com/isqua/bureau).
* [fall](https://github.com/jottenlips/seasonal-zshthemes) - Minimalist theme with fall icons. Includes `git` status decorations.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) - Minimal ZSH prompt that works better on dark backgrounds.
* [fdT2K](https://github.com/FDT2k/FDT2K-theme)- Based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme)，预设包括 virtualenv、最后命令状态、`nvm`、`docker machine` 和 `git`、`hg` 和 `bzr` 状态装饰.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme) - Clean, simple, compatible and meaningful. Tested on Linux, Unix and Windows under ANSI colors.
* [filthy](https://github.com/molovo/filthy) - 令人作呕的干净 ZSH 提示.
* [fish](https://github.com/Raniconduh/zshfish) - ZSH theme reminiscent of the default fish shell theme. Includes `git` status decorations.
* [fishy-lite](https://github.com/sudorook/fishy-lite) - Fork of the original [fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy) theme in oh-my-zsh with much of the extraneous stuff cut out to improve load speeds. Includes a battery gauge and `git` status display that can be enabled on the right-hand side of the prompt.
* [fishy2](https://github.com/akinjide/fishy2) - ZSH 主题灵感来自 [original fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy).
* [fizzy](https://github.com/Brokenhammer72/fizzy) - 极简提示，包括 `git` 状态装饰.
* [fluent-git](https://github.com/RobertKozak/fluent-git) - Displays time of last command execution, error code, hostname, username, `git` status, kubernetes cluster and namespace, path and ssh connection status.
* [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) - Custom setup for [powerlevel9k](https://github.com/bhilburn/powerlevel9k) . 包括 `git` 状态装饰.
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - 包括最后一条命令的状态、`git` 信息和当前目录.
* [frank](https://github.com/ronmackley/frank-theme) - Frank keeps to the point, displaying information compactly but readably on a single line. Frank keeps to the facts and only tells you extra things when they are important.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - Fork of [terminal-party](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) 主题.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - A theme based on the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) 哦，我的 zsh 主题.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - 红色版本 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) 来自 oh-my-zsh 的主题.
* [fritz](https://github.com/fritzccc/fritz-zsh-theme) - Works well on dark backgrounds. Includes `git` status decorations.
* [frlo](https://github.com/fiorillo/frlo) - Uses your computer's hostname to come up with a (hopefully) unique three-color theme to display in your prompt, so you know at a glance which machine you're logged into.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - A colorful two-line theme with support for `git` and `svn`.
* [furio](https://github.com/hectorpalmatellez/furio-theme) - Fork of the [Cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) 哦，我的 zsh 主题. 用不同的颜色和表情符号.
* [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) - 彩色主题，在深色背景下效果更好.
* [gaia](https://github.com/gcaracuel/gaia.zsh-theme) - Originally a fork of [Bureau](https://github.com/isqua/bureau) adds new virtual environments info to the prompt: Kubernetess, virtualenv, rbenv and Java versions. Includes git status integration.
* [gal](https://github.com/x6r/gal) - gal is based on [gallois](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme).
* [garden](https://github.com/fecat233/garden) - 在深色终端背景下效果更好，包括 `git` 状态装饰.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto 在您需要的时候提示您需要的信息.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires `rvm` & `git` plugins.
* [gbt](https://github.com/jtyr/gbt) - Go Bullet Train is a very customizable prompt builder inspired by Bullet Train that runs much faster. Includes many different status cars.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - Breaks out the oh-my-zsh gentoo theme into a separate repo for non-omz users.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) - Adds host info to the [geometry](https://github.com/geometry-zsh/geometry) 主题.
* [geometry](https://github.com/geometry-zsh/geometry) - 一个最小的 ZSH 主题，可以将任何功能添加到左侧提示符或（异步）右侧提示符中.
* [ghoti](https://github.com/lonr/ghoti)  - 模仿 `fish-shell` 默认提示. 包括 `git` 装饰.
* [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) - 灵感来自 [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme), 包括 `git` 装饰、IP 地址、主机和路径.
* [gimbo](https://github.com/gimbo/gimbo.zsh-theme) - 一个变种 [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) 具有更多功能、一点眼花缭乱和上下文相关的额外线条. 包括 `git` 状态装饰、历史编号、用户名/主机名上下文、目录状态、最后一个命令的状态（如果失败）以及 Python 虚拟环境名称（如果存在）.
* [gimme](https://github.com/nralbrecht/gimmezsh)  - 带有 `git` 集成的 ZSH 的简单主题. 灵感来自 [gitsome](https://github.com/mtully/gitsome) 主题.
* [girazz](https://github.com/mdentremont/girazz) - 对 gnzh 主题的修改，在右侧提示中添加了“vi”模式.
* [git-prompt (awgn)](https://github.com/awgn/git-prompt) - A fast `git` prompt for `bash`, `zsh` and `fish`.
* [git-prompt (olivierverdier)](https://github.com/olivierverdier/zsh-git-prompt) - Displays information about the current `git` repository. In particular the branch name, difference with remote branch, number of files staged or changed, etc.
* [git-prompt (woefe)](https://github.com/woefe/git-prompt.zsh) - 受 Olivier Verdier 启发的 ZSH 的快速、可定制、纯 shell、异步 Git 提示 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) 和fish shell的“Informative VCS”提示非常相似.
* [git-prompt-kit](https://github.com/olets/git-prompt-kit) - 一组可配置的组件，用于以最少的编码创建功能丰富、高性能的 Git 感知 zsh 提示（又名主题）.
* [git-simple](https://github.com/ZakharEl/git-simple-theme) - 简单的主题，包括详细的 `git` 状态装饰.
* [gitsome](https://github.com/mtully/gitsome) - 带有 `git` 信息的超级简单提示，针对 [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) color scheme.
* [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) - 显示命令和 `git` 状态装饰.
* [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme)  - 在 `git` 存储库中时，它显示来自 `git` 存储库根文件夹的位置. 当不在 `git` repo 中时，它会显示相对于 home 的路径，`~`.
* [gitster (zimfw)](https://github.com/zimfw/gitster) - Zim fork of shashankmehta's [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 提示主题
* [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) - 从原来的分叉 [gitster](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) 主题.
* [gk3000](https://github.com/gk3000/gk3000-oh-my-zsh-theme) - Includes `git` status decorations and full path to current directory.
* [glimmer](https://github.com/martnu/glimmer) - Includes `git` branch, time and user@host.
* [gndx](https://github.com/gndx/gndx-zsh-theme) - 包括 `git` 状态、主机名、目录和最后一个命令退出状态装饰.
* [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) - 定制 [gnzh.zsh-theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 来自 oh-my-zsh.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) - iTerm 2 和 ZSH 的主题，包括 `git` 装饰、user@host、路径和日期.
* [gops](https://github.com/noxer/gops) - Fast powerline-like prompt. Includes `git` status, current directory, root status decorations.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - 简单但信息丰富的主题，包括 `git` 装饰和最后一个命令的返回状态.
* [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) - Minimalist, includes `git` status decorations.
* [grs](https://github.com/gersontpc/zsh-theme-grs) - 包括 `git` 状态装饰、用户 ID 和工作目录.
* [gruvbox (hgaiser)](https://github.com/hgaiser/gruvbox-zsh) - 设置颜色 [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [gruvbox (sbugzu)](https://github.com/sbugzu/gruvbox-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874), 使用相同的颜色 [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [guezwhoz](https://github.com/guesswhozzz/guezwhoz-zshell) - Minimalist, includes `git` status decorations.
* [guri](https://github.com/victorfsf/guri) - A Simple and fast Oh-My-Zsh theme, based on [Pure](https://github.com/sindresorhus/pure)的设计.
* [hackersaurus](https://github.com/bhilburn/hackersaurus)  - 在提示符中嵌入了带有“git”状态和最后一个命令运行的退出代码的主题. 相关 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [halil](https://github.com/5m0k3r/zsh-themes) - Fork of oh-my-zsh's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) 主题.
* [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme) - A simple theme with the first character being 花(hana), the kanji for flower. This theme was inspired by a keycap set called DSA Hana. This pairs well with the [hana atom](https://github.com/arturoalviar/hana-matcha-syntax) theme. Includes `git` status decorations.
* [handy](https://github.com/hanleylee/handy)  - 多彩和轻量级的主题. 显示 root 状态、`git` 状态、当前目录和 `user@hostname` 装饰.
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) - 如果超过 `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`，则显示 `git` 分支和状态、最后一个命令退出代码、最后一个命令执行时间.
* [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) - 基于氧化物，包括 `git` 状态装饰和当前用户/主机信息.
* [haribo](https://github.com/haribo/omz-haribo-theme) - Simple `git` status + timestamp in prompt.
* [hcompact](https://github.com/fusion809/zsh-theme) - 显示时间、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [headline](https://github.com/Moarram/headline-zsh-theme) - A responsive ZSH theme featuring Git status information and a colored line above the prompt.
* [heart](https://github.com/gko/heart) - Heart themed prompt for light backgrounds.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - Simple, no-nonsense and clean, with support for `git` and return codes.
* [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - Based on [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau)，添加了 `git` 状态装饰和 `npm` 状态.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hematite](https://github.com/bigdave/hematite) - 极简主义促销，试图仅显示在给定时间非常有用的状态装饰.
* [hexagon](https://github.com/diogoazevedos/hexagon) - 基于极简主义 zsh 主题 [geometry](https://github.com/geometry-zsh/geometry).
* [hfulldate](https://github.com/fusion809/zsh-theme) - 显示时间、日期、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - 灵感来自 robbyrussell 主题 + ssh 连接状态提示.
* [hina](https://github.com/ucpr/hina) - Written in `golang`, includes `git` status decoration and kubernetes context.
* [hip-fellow](https://github.com/haitaim/hip-fellow) - Includes `git` status decorations and works with standard fonts.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 一个变种 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [home](https://github.com/sheerun/home) - 漂亮而简短的单行主题，让您有宾至如归的感觉.
* [hometown](https://github.com/olets/hometown-prompt) - 一个功能丰富、高性能的 `git` 感知 ZSH 主题，包含用户、主机、时间、当前工作目录及其父级的段，以及 Git 存储库中详细的完整 Git 状态.
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - oh-my-zsh 和 iTerm 2 的 Honukai 主题和颜色.
* [horizontal](https://github.com/nuimk/horizontal) - 带有水平分隔符的两行提示.
* [hornix](https://github.com/fusion809/zsh-theme) - Displays time & date, OS (including distro if on Linux), directory and whether running as root.
* [horse-sh](https://github.com/emileswarts/horse-sh) - A very minimal brown/red ZSH theme.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - Simple and clean, includes the return code of the last command executed.
* [hug](https://github.com/xxninjabunnyxx/hug-zsh)  - 当你工作并需要一个拥抱时. 包括 `git` 状态.
* [humbled](https://github.com/saravanabalagi/zsh-theme-humbled) - A clean and humble theme with support for `condaenv`, `virtualenv` and `git` status decorations left aligned with the working directory in bold.
* [hydrogen](https://github.com/xylous/hydrogen) - A simple multiline zsh theme. It shows username, hostname, current directory and `git` status decorations.
* [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) - Designed to work with the hyper terminal theme, includes `git` status decorations.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) - Gives you a comprehensive overview of the branch you're working on and the status of your repository without cluttering your terminal.
* [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX) - Modified iGeek theme. Works with macOS out-of the box, includes `git` status decorations.
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - 在深色背景上效果很好.
* [ice](https://github.com/Lenart12/ice.zsh-theme) - 非常轻微的修改 [bureau](https://github.com/isqua/bureau) theme combined with [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [icicle](https://github.com/JamesConlan96/Icicle) - Includes `git` status decorations, and whether running as root.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) - A super happy awesome Powerline-style, `git`-aware **prezto only** theme.
* [igorsilva](https://github.com/igor9silva/zsh-theme) - Shows current directory, customizable delimiter, current branch, `git` status.
* [iguanidae](https://github.com/btd1337/iguanidae-zsh-theme) - Includes `git`, `nvm` and `venv` decorations.
* [illustion](https://github.com/shabane/illusion) - Includes username, current working directory, git status and last command status decorators.
* [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) - Fork of [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) with spacing improvements and an updated icon. Includes `git` status information.
* [imp](https://github.com/igormp/Imp) - Based on [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) and optimized for dark backgrounds.
* [infernus](https://github.com/jshiell/infernus-zsh-theme) - Minimalist theme, better on dark backgrounds.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) - Clean theme that shows `git` status, background jobs, remote host, and other information.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - 的扩展 [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme to use powerline fonts.
* [itg](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy 的主题.
* [ivy](https://github.com/ivyhjk/ohmyzsh-theme-ivy)  - 适用于深色背景. 包括 user@host、`git` 状态和时间装饰器. 基于 [obraun](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#obraun) 主题.
* [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme) - Based on refined and ys themes, includes `git` status decorations. Includes an optional iterm2 color scheme.
* [jake](https://github.com/JakeHuneau/Jake.zsh-theme) - Shows the time, the current directory, and `git` branch information including the branch name and a red + if the branch has un-pushed changes.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - 针对深色背景进行了优化，包括 `git` 状态和 `rvm` 状态.
* [jc](https://github.com/jclementex/jc-zsh-theme) - 对于深色终端背景，包括 `git` 状态信息.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - Loosely based on the ys theme.
* [jerome](https://github.com/jeromescuggs/jerome-theme) - 基于的多彩主题 [dieter](https://github.com/jeromescuggs/jerome-theme) 主题，但带有黄色主机名. 包括 `git` 装饰.
* [jhleeeme](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) - 包括 `git` 和 python virtualenv 状态装饰、用户、密码、时间和系统名称.
* [jon](https://github.com/Jon-Schneider/jon.zsh-theme) - 一个简化 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 与颜色 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - 灵感来自 [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme), includes `git` status.
* [jovial](https://github.com/zthxxx/jovial) - 显示主机、用户、路径、开发环境、`git` 分支，其中 python venv 处于活动状态.
* [jpegleg](https://github.com/jpegleg/zshrc) - Similar to dark blood theme, includes timestamp and `git` decorations.
* [js-magic](https://github.com/JSextonn/js-magic) - A simplified take on [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) . 包括当前工作目录和 `git` 状态装饰.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
* [just-another](https://github.com/supertassu/another-theme) - Just another theme, with hostname when you're sshed to another machine.
* [just-around-the-corner](https://github.com/DevinLeamy/just-around-the-corner)  - 倒计时直到圣诞节. 包括 `git` 状态装饰.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter) - Powerline-style theme with `git`, `svn`, `npm`, `rvm` and network awareness. Requires Powerline-compatible terminal font.
* [jyumpp](https://github.com/Jyumpp/jyumpp-zsh-theme) - Configuration file and installer for Powerlevel 10K.
* [kali](https://github.com/h4ck3r0/kali-theme) - 包括 `git` 装饰.
* [karu](https://github.com/zaari/karu) - Minimalist single line ZSH prompt.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) - Theme that includes a few features from other themes.
* [kenton](https://github.com/notnek/zsh-theme) - 针对深色背景进行了优化，包括 `git` 状态信息.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) - 丰富多彩的主题，包括 iTerm 2 配色方案.
* [kgzsh](https://github.com/Kashugoyal/kgzsh) - Includes `git` status deorations, works well on darker backgrounds.
* [kido](https://github.com/KidoThunder/kido-zsh-theme) - Based on `ys` and `robbyrussell` themes. Includes decorators for the exit code of the last command run, python virtualenv and VCS status.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - 最小的主题.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - 基于 Fishy 主题，但显示完整路径而不是缩写目录，并且仅在 `ssh` 会话和 docker 容器中显示 user@machine.
* [kirkdawson](https://github.com/kdawson133/KirkDawson)  - 受电力线启发. 包括 `git` 状态、最后命令退出状态、用户@主机名、工作目录以及用户是否以 root 身份运行的提示装饰.
* [kiss](https://github.com/rileytwo/kiss) - Simple theme for oh-my-zsh, VSCode, iTerm2, Neovim, and RStudio. Includes `git` status decorations.
* [kketcham](https://github.com/prototype27/kketcham) - Theme with nifty colors on the `git` info.
* [klassiker](https://github.com/mrdotx/zsh-theme) - 带有 `git` 装饰的极简主题.
* [korittg](https://github.com/dkorittki/korittg-zsh-theme) - Minimalistic but informative. Includes decorations for `git` status, current directory and the `kubectl` context and namespace.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme)  - 最适合深色背景. 包括 `git` 状态装饰.
* [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - Two line theme designed for dark terminals, has `git` decorations.
* [krak3n](https://github.com/krak3n/zsh-theme) - 显示 golang 版本和当前的 `git` 分支.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) - A dark theme for ZSH.
* [kube](https://github.com/tigerjz32/kube-zsh-theme) - Based on [macos-terminal](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal) , 包括 `kubectl` 上下文. 有时间、目录和 `git` 状态装饰.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme) - Agnoster fork optimized for solarized terminals. Requires powerline-compatible font.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) - 带有 `git` 和 `hg` 状态信息的彩色主题，能够将特定于主机的颜色添加到主机名.
* [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme) - A simple theme with the first character being 九(kyuu), the number 9. The primary color is blue with a magenta accent. Includes `git` status decorations.
* [lagune](https://github.com/noplay/lagune) - 一个最小的 ZSH 主题.
* [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) -  Inspired by the robbyrussell [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) theme. Includes `git` status decorations.
* [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) - 为使用 unicode 兼容字体和终端应用程序的 `git` 用户优化的 ZSH 主题.
* [lambda-blazinggit](https://github.com/zalefin/lambda-blazinggit) - Includes blazing fast, detailed `git` information. Requires Nerd Fonts and the [gitstatus](https://github.com/romkatv/gitstatus) 插入.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - 包含“git”信息的极简提示.
* [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) - Simple theme based on lambda with `git` status and virtualenv information.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - 一个简单的 ZSH 主题，针对 `git` 使用进行了优化.
* [lambda-p](https://github.com/paimanbandi/lambda-p) - Inspired by the [lambda mod](https://github.com/halfo/lambda-mod-zsh-theme) and [Lambda V](https://github.com/vkaracic/lambdav-zsh-theme) 主题. 包括 `git` 状态装饰.
* [lambda-pure](https://github.com/marszall87/lambda-pure) - A minimal ZSH theme, based on Pure, with added NodeJS version.
* [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) - Lambda 和 Fishy 主题的组合，包括 `git` 状态装饰.
* [lambda-zen](https://github.com/seamile/lambda-zen) - inspired by [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) 带有图形 `git` 状态装饰.
* [lambder](https://github.com/avillen/zsh-theme-lambder) - 包括 `git` 状态装饰，最适合深色终端主题.
* [laniksj](https://github.com/LanikSJ/laniksj-zsh-theme) - Works best on a dark background. Based on the great `ys` theme and [Honukai ZSH Theme](https://github.com/oskarkrawczyk/honukai-iterm-zsh) . 显示根状态和 `git` 状态装饰.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - 针对暗终端进行了优化，具有本地和远程系统的变体.
* [leafia](https://github.com/Ghostrick/leafia-prompt) - Leafy prezto theme that shows `git` status information.
* [lean](https://github.com/miekg/lean) - 灵感来自 [pure](https://github.com/sindresorhus/pure) . 包括 `git` 状态和后台作业装饰.
* [lemon](https://github.com/carlosvitr/lemon_zsh) - Many beautiful colors for you to enjoy. done with care and patience. Includes `git` status and ruby version decorations.
* [leon](https://github.com/prince-an/Leon_zshTheme) - Works well on light background. Includes `git` status, time, username@host, working directory and last command exit status decorations.
* [leverage](https://github.com/gschnall/leverage) - Based on [minimal](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme), uses colors, and an extra `¬` character, to better distinguish the command line prompt from your output.
* [lewis](https://github.com/lewisflude/oh-my-lewis)  - 黑色、白色和红色主题. 显示 `git` 状态信息.
* [lightbulb](https://github.com/lightbulb703/lightbulb-zsh-theme) - 包括内核、操作系统版本、正常运行时间和 `git` 的装饰.
* [lighthaus](https://github.com/lighthaus-theme/zsh) - A prompt that compliments the [Lighthaus](https://github.com/lighthaus-theme/lighthaus) 主题. 显示 `git` 信息、github/gitlab 徽标并在发生更改时显示更改.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) - 极简主义主题，最适合深色终端背景.
* [lilith](https://github.com/aknackd/zsh-themes) - Modification of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) and [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [lime](https://github.com/yous/lime) - Simple and easily customizable ZSH theme.
* [limpide](https://github.com/shooteram/limpide) - Modified version of [miloshadzic](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) theme which displays parent and current directory.
* [linuxer](https://github.com/patrick330602/linuxer) - 灵感来自 Yaris Alex Gutierrez  [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh), Yad Smood 的 `ys`, 和 [Bureau](https://github.com/isqua/bureau) 主题.
* [linuxero](https://github.com/andreshincapier/linuxero)  - 极简主义者. 包括根状态、当前目录、`git` 状态、当前 ruby​​ rvm 环境和当前 python virtualenv 的装饰.
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt with useful information when you need it. It shows you what you need when you need it. You will notice what changes when it changes, saving time and frustration.
* [lish](https://github.com/bashelled/lish)  - 一个休闲的主题. 没有粗糙，只有光滑. 包括 `git`、user@host、最后一个命令退出状态、当前目录、当前时间和根状态装饰器.
* [liver](https://github.com/RenoirTan/liver.zsh-theme) - 色彩丰富，包括 `git` 状态、用户、主机、当前和当前存储库根装饰的相对路径.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) - Minimalist theme used by discerning llamas.
* [logico](https://github.com/logico/logico-zsh-theme)  - 有 `git` 装饰. 显示 vi 模式的远程状态和指示灯.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - 基于 Sindre Sorhus 纯主题的德克萨斯主题.
* [longsilvern](https://github.com/long263/longsilvern-zsh-theme) - 包括 `git` 和紧凑的 `pwd` 装饰.
* [lorond](https://github.com/lorond/zsh-lorond/) - Compact version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) . 包括 `git` 状态，适用于标准字体.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme)  - lambda-mod 主题的变体. 具有 `git` 装饰，需要与电力线兼容的终端字体.
* [luke](https://github.com/xueguangl23/luke_zsh_theme)  - 包括 `git` 装饰. 基于 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh theme.
* [lukerandall-extended](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) - 的扩展版本 [lukerandall](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) 主题. 包括 `git` 状态的装饰和最后一次命令运行的状态.
* [lunachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/lunachar.zsh-theme) - 极简主义主题.
* [macos](https://github.com/alejandromume/macos-zsh-theme) - Includes `git` status decorations.
* [mad](https://github.com/MartinWie/ohmyzsh-theme-mad) - Includes `git` status and last command execution time decorations.
* [magicmace](https://github.com/zimfw/magicmace) - 灵感来自 xero 的 ZSH 提示和 [eriner's prompt](https://github.com/zimfw/eriner). Includes status codes for active python `venv`, exit status of last command, shortened working directory, `git` status decorations.
* [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN 的魔法主题.
* [maivana](https://github.com/nylo-andry/zsh-themes) - 包括 `kubectl` 上下文，`git` 状态装饰.
* [materialshell](https://github.com/carloscuesta/materialshell) - 一个 [material design](https://material.io/guidelines/style/color.html) 您的外壳主题具有良好的对比度和重要部分的颜色流行. 专为保护眼睛而设计.
* [matrix](https://github.com/pot-code/matrix-zsh-theme) - 变体 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) styled to look like something in the Matrix movie trilogy. Includes `git` status decorations.
* [matter](https://github.com/mrobillard/matter-zsh-theme) - 显示 `git` 状态、AWS 保管库角色、后台作业、最后一个命令的退出代码和主机名.
* [mau](https://github.com/vichargrave/mau) - A ZSH theme with a cat twist. Includes `git` status decorations. Based on the [kphoen](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kphoen.zsh-theme) and [smt](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/smt.zsh-theme) 主题.
* [mbolis](https://github.com/mbolis/mbolis-zsh-theme) - Includes `git` decorations, changes prompt color if root user, active jobs, and [jenv](https://github.com/jenv/jenv) integration.
* [mdmini](https://github.com/MarioDena/MDmini) - Includes `git` and `ssh` status decorations.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character. Requires the [hooks](https://github.com/willghatch/zsh-hooks) 插入.
* [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) - Includes `git` status decorations, shows exit code of last command if nonzero.
* [mexassi](https://github.com/Mexassi/mexassi-zsh-theme)  - 检查 `/sys/class/power_supply` 文件夹以确定系统是安装在笔记本电脑还是台式机上. 读取电池百分比 grepping acpi 命令并在提示符中显示. 包括 `git` 装饰.
* [mh-fzj](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) - 包括 `rvm` 和 `git` 状态装饰.
* [michaelpass](https://github.com/michaelpass/michaelpass.zsh-theme) - POSIX 友好的跨平台 [alanpeabody](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) mod w/方便的时间戳和完整的 git/ruby 支持.
* [midin](https://github.com/xlshiz/midin) - Works well on dark terminal background, includes `git` status decorations.
* [mike-was-here](https://github.com/leguim-repo/mike-was-here-theme/) - Minimalist, includes `git` status decorations.
* [milight](https://github.com/frodoslaw/milight-zsh) - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
* [min](https://github.com/andrepolischuk/min) - 一个简约的 ZSH 提示.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind.
* [mini-simple](https://github.com/ysl2/mini-simple-zsh-prompt)  - 极简主义者. 包括 `vcs` 状态装饰.
* [minima (Brolly0204)](https://github.com/Brolly0204/zsh-minima) - 包括`git`、`node`、`golang`、`yarn`、`php`、`docker`和`python`状态装饰.
* [minima (ednikolenko)](https://github.com/ednikolenko/minima)  - 带有 `git`、`docker`、`go`、`node`、`npm`、`python` 和其他指标的最小 ZSH 主题. 对某些标记使用 unicode 字符.
* [minimal (5amu)](https://github.com/5amu/minimal-prompt) - Minimal prompt, uses nerdfonts. Includes `git` and `vpn` status decorations.
* [minimal (casalinovalerio)](https://github.com/casalinovalerio/minimal-prompt) - 最小提示，包括 `git` 和 vpn 状态装饰.
* [minimal (glsorre)](https://github.com/glsorre/minimal/) - minimal asynchronous ZSH theme optimized for use with the [Fira Code](https://github.com/tonsky/FiraCode) 字体和 [Solarized Light](https://ethanschoonover.com/solarized) 终端主题.
* [minimal (subnixr)](https://github.com/subnixr/minimal) - Minimal yet feature-rich theme.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) - 黑暗终端的主题，包括右侧提示中的 `git` 装饰.
* [minimal2](https://github.com/PatTheMav/minimal2) - A minimal and extensible ZSH theme. Forked from [subnixr's original](https://github.com/subnixr/minimal) and adapted for [Zimfw](https://github.com/zimfw/zimfw).
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) - Inspired by kolo theme from oh-my-zsh.
* [mira](https://github.com/mbStavola/mira) - 一个修改 [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) with time info and a simplified start prompt.
* [mirage](https://github.com/robin-pfeiffer/ohmyzsh-mirage-theme/) - 包括 `git` 状态、最后命令退出代码、`sudo` 时间戳文件是否存在以及当前活动的 Python 虚拟环境的提示装饰.
* [miramare](https://github.com/franbach/oh-my-deepin-miramare)  - 包括 `git` 状态装饰. 最适合搭配 [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
* [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs' ZSH theme.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - Optimized for dark backgrounds.
* [mnml](https://github.com/mnml-theme/prompt) - 带有 `git` 状态装饰的最小主题.
* [mochi2](https://github.com/mochidaz/zsh-themes)  - 极简主义主题. 包括 `git` 和 `hg` 状态装饰.
* [mochi](https://github.com/mochidaz/zsh-themes) - Simple theme, designed to resemble rust main function. Includes `git` and `hg` status decorations.
* [moderno](https://github.com/obrassard/moderno-zsh) - 一个简单而现代的 ZSH 主题，灵感来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme)  Oh-My-ZSH 的主题. 包括 `git` 状态装饰.
* [modesty](https://github.com/saravanabalagi/zsh-theme-modesty) - A clean and modest ZSH theme with `condaenv`, `virtualenv` and `git` status decorations displayed neatly right aligned.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874).
* [momoyo](https://github.com/momoyo-droid/momoyo-zsh-theme) - Reminiscent of powerline. Includes decorations for `git` status, username, and working directory.
* [moonline](https://github.com/kagamilove0707/moonline.zsh) - 最小但易于扩展的提示.
* [moux](https://github.com/gagbo/moux) - 适用于深色终端背景，包括 `RPROMPT` 中的 `git` 装饰.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - 提供有关您所在存储库的有用信息（在您的提示中）.它目前适用于 [Git](https://git-scm.com/) and [Mercurial](https://www.mercurial-scm.org/)， 在下面 [ZSH](https://en.wikipedia.org/wiki/Zsh) as well as [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [multiline](https://github.com/jan-auer/zsh-multiline) - Powerline-esque theme based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [muslim](https://github.com/nksoff/muslim) - A simple minimal ZSH prompt theme.
* [musy](https://github.com/THaGKI9/musy-zsh-theme) - Inspured by muse theme. Includes `git` status decorations.
* [my-hl2](https://github.com/liamm91/my-hl2)  - 包括 virtualenv、`git` 状态和目录装饰. 基于 omz  [half-life](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/half-life.zsh-theme) 主题.
* [myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia 的 myzsh 主题.
* [mzt](https://github.com/honbey/mzt) - Sets up `LS_COLORS`, colorizes `diff` and includes `git` status and current working directory decorations.
* [nanofish](https://github.com/tweekmonster/nanofish) - 为纳米技术主题添加鱼式目录提示.
* [nbrylevv](https://github.com/nbrylevv/nbrylevv-zsh-theme) - Minimalist theme with text `git` status decorations.
* [nctu](https://github.com/leovincentseles/nctu.zsh-theme)  - 强调速度的轻量级主题. 包括 `git` 状态装饰.
* [neewbie](https://github.com/neewbee/neewbee.zsh-theme) - Minimal theme with `git` decorations. Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell).
* [neon-potato](https://github.com/algosuna/neon-potato)  - 多彩和简约的主题. 包括 `git` 装饰.
* [neon](https://github.com/sahariko/neon) - 带有 `git` 装饰的漂亮且最小的 ZSH 主题.
* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - A prompt theme for ZSH with Nerd Fonts.
* [nescalante](https://github.com/nescalante/zsh-theme) - Optimized for dark terminal backgrounds, includes `git` decorations.
* [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) - Includes `git` decorations and `vi`-mode indicator.
* [newt](https://github.com/softmoth/zsh-prompt-newt)  - 胖而快的主题——内外都很漂亮，风格片段做得对. 高度可定制，包括“git”、用户名、执行时间、目录、后台作业和编辑模式装饰.
* [newton](https://github.com/sebastienfilion/zsh.newton) - 包括 `git` 状态和外部 IP 地址装饰.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - 一个非常基本的主题，只有一个 macOS 自行车图标.
* [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - Colorful, shows `git` status decorations.
* [nikitakot](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme)  - 小而简单的 oh-my-zsh 主题. 显示当前目录和后面的 2 个目录，`git` 和 `nodejs` 状态装饰.
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - 基于 af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - A simple oh-my-zsh theme.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - Minimalist ZSH theme with `git` status decorations.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) - oh-my-zsh 的节点主题，为了便于与其他插件管理器一起使用而进行了拆分.
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - Based on the ys theme, with added NodeJS version (from NVM plugin).
* [noon](https://github.com/silky/noon.zsh-theme) - Has light and dark variants, shows `git` information.
* [nord](https://github.com/TyWR/Nord-zsh) - Includes `git` status decorations and displays the active conda environment.
* [normanius](https://github.com/normanius/normanius-zsh-theme) - 源自 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [nothing](https://github.com/eendroroy/nothing) - Lightning fast and really simple because it has almost nothing in it.
* [nox](https://github.com/kbrsh/nox) - 深色主题，显示当前工作目录和 git 状态.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme) - A clean, distraction free and `git` focused development theme. Shows path relative to `git` root (or ~ when outside `git` repo), time since last commit, current SHA, branch and branch state.
* [nunorc](https://github.com/nunorc/nunorc.zsh-theme) - Minimalist theme, works well on dark backgrounds. Includes `git`, `mercurial` and `svn` satus decorations.
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - A simple theme for prezto and oh-my-zsh.
* [nuts](https://github.com/rafaelsq/nuts.zsh-theme) - 极简主题，包括 `git` 状态装饰和时间.
* [oblong](https://github.com/Ansimorph/oblong) - Simple `bash`-inspired theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [basher](https://gitlab.com/Spriithy/basher) . 包括状态装饰以显示用户是否为 root、上次命令运行的退出状态、`git` 分支及其干净/脏状态.
* [odie](https://github.com/masterodie/zsh-theme-odie/) - Works well on a dark background. Includes `git` status, python virtualenv and `vi`-mode status decorations.
* [odin](https://github.com/tylerreckart/odin) - Odin is a `git`-flavored ZSH theme.
* [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) - 带有 `git` 装饰的多行主题.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated prompt for bash and ZSH.
* [oh-my-posh](https://ohmyposh.dev/)  - 不是 ZSH 特定的，但非常好，可以与 ZSH 一起使用. 允许您对所有 shell 中的提示使用相同的配置.
* [oh-my-via](https://github.com/badouralix/oh-my-via) - Theme for ZSH which mainly forks the historical theme used on VIA servers.
* [ohmypc](https://github.com/joselpadronc/OhMyPC)  - 适用于深色终端窗口. 包括 `git` 装饰.
* [om](https://github.com/sirshikher/zsh-om) - 最小主题，适用于深色背景，包括 `git` 状态装饰.
* [omszt](https://github.com/MU001999/omszt) - 带有 `git` 装饰的极简主义主题。
* [omuse](https://github.com/ouuan/omuse-zsh-theme) - 基于 Oh-My-ZSH  [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme). Has decorations for `git` status, time, absolute pwd, RAM usage, time used by last command, and last command exit status.
* [owi](https://github.com/owitech/zsh-theme/) - Minimalist theme with `git` status decorations.
* [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) - 包括 `git` 状态和 virtualenv 信息.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - 简约和黑暗的 ZSH 主题.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme) 🌏 OZ0NO - Let's Breathe a clean ZSH.
* [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) - 一个主题 [powerlevel10k](https://github.com/romkatv/powerlevel10k) prompt that puts an emphasis on simplcity while still getting important information across.
* [pad](https://github.com/eproxus/pad.zsh-theme) - 简洁多彩的 oh-my-zsh 主题.
* [page](https://github.com/SLIB53/page-zsh-theme) - A simple theme with VCS support. The prompt shows 1 level of the current working directory, branch, and a color coded curved fat arrow.
* [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) - Allows display of host information, includes `git` branch decoration.
* [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) - 在提示中使用图标显示详细的 `git` 状态信息.
* [panda](https://github.com/davymai/oh-my-zsh-panda-theme) - Includes `git` and `root` status decorations. Best on a dark background.
* [papercolor](https://github.com/erikschreier/PaperColor-themes) - Color scheme for ZSH, `vim` and `tmux`. Includes `git` status decorations.
* [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion)  - 包括 `git` 状态装饰，以毫秒为单位的命令运行时间. 在 macOS 上需要 coreutils.
* [pastel](https://github.com/iboyperson/pastel) - A ZSH theme inspired by [sugar-free](https://github.com/cbrock/sugar-free). Includes `git` decorations.
* [pecodez](https://github.com/pecodez/pecodez-zsh-theme) - Optimized for dark terminals. Has decorators for `snyk` version, `node` version, AWS profile, kubernetes context and `git` status.
* [pentesters](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) - 修改版 [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme for pentesters which includes the date, time, and IP address for pentest logging.
* [persi](https://github.com/persiliao/persi-zsh-theme)  - 包括 `git` 装饰. 适用于浅色和深色背景.
* [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) - 本着精神的最小主题 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and Pure Shell themes.
* [phantomk](https://github.com/phantomk/phantomk.zsh-theme) - Colorful theme, includes go version, node version and `git` status.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - 一个干净简单的 ZSH 主题，灵感来自于 [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) 主题.
* [pi](https://github.com/tobyjamesthomas/pi) - 带有 `git` 状态装饰的简约主题.
* [piboy](https://github.com/sflems/piboy-zsh-theme) - A simple and elegant multi-line theme for ZSH. Includes a colourized timestamp, `git` & syntax highlighting, and elevated root theme.
* [plain-ui](https://github.com/purveshpatel511/plain-ui) - Minimalist, but includes `git` status decorations.
* [plain](https://github.com/jimeh/plain.zsh-theme) - 一个简单的 ZSH 主题，显示基本的 `git` 信息.
* [planet](https://github.com/borb/planet-zsh) - A slimmed down version of [steef](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) 从 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) - 简单、简洁的主题.
* [plantyhoe](https://github.com/totoroot/plantyhoe.zsh-theme)  - 基于对植物和苹果的热爱的极简主义主题. 包括 `git` 状态装饰.
* [platypus](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) - Shows working directory, the return status of the last command, and `git` current branch.
* [polyglot](https://github.com/agkozak/polyglot) - `zsh`、`bash`、`ksh​​93`、`mksh`、`pdksh`、`dash`和busybox`ash`的动态提示，它使用基本的ASCII符号（和颜色，如果可能的话）来显示用户名，无论是本地还是远程 `ssh` 会话、缩写路径、`git` 分支和状态、最后一个命令的退出状态（如果非零）、使用 `virtualenv`、`venv`、`pipenv`、` 创建的任何虚拟环境诗歌`或`conda`.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM 的基本 oh-my-zsh 自定义主题.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - Programmer's theme with `git` status, ruby version and project path.
* [powerbash](https://github.com/erikschreier/powerbash-zsh) - 适用于深色终端背景，包括 `git` 状态装饰.
* [powerless](https://github.com/martinrotter/powerless) - Tiny & simple pure ZSH prompt inspired by powerline.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - A fast reimplementation of [powerlevel9k](https://github.com/bhilburn/powerlevel9k)  ZSH 主题. 可以用作 powerlevel9k 的直接替代品，当给定相同的配置选项时，它将生成相同的提示，只是速度更快.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k is a theme for ZSH which uses [Powerline Fonts](https://github.com/powerline/fonts). It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen), and [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 附加组件 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - 两线版本的电力线：一根用于信息，一根用于输入.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) - Another take on a powerline theme. Nicely configurable, but requires at least a 256 color-capable terminal with a powerline-compatible terminal font.
* [powerline (syui)](https://github.com/syui/powerline.zsh) - A `git` aware powerline theme.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - Based on [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
* [powerline-go](https://github.com/justjanne/powerline-go) - A beautiful and useful low-latency prompt, written in golang. Includes `git` and `hg` status decorations, exit status of the last command run, current Python virtualenv, whether you're in a [nix](https://nixos.org/) 外壳，并且易于扩展。
* [powerline-hs](https://github.com/rdnetto/powerline-hs) - 一个 [Powerline](https://github.com/powerline/powerline) clone written in Haskell. It is significantly faster than the original implementation, and makes the shell noticeably more responsive.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - 在 Ruby 中创建，使用电力线字符来模拟具有有用信息的药丸.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell) - Beautiful and useful prompt generator for Bash, ZSH, Fish, and tcsh. Includes `git`, `svn`, `fossil` and `hg` decorations, Python virtualenv information, and last command exit status.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - 一个 [powerline](https://github.com/Lokaltog/vim-powerline)-like prompt for Bash, ZSH and Fish. Shows important details about git/svn/hg/fossil branch and is easy to customize/extend.
* [powerline-train](https://github.com/sherubthakur/powerline-train) - A powerline variant.
* [powerline](https://github.com/carlcarl/powerline-zsh) - 一个 [Powerline](https://github.com/Lokaltog/vim-powerline)- 类似提示，基于 [powerline-bash](https://github.com/milkbikis/powerline-bash). Displays virtualenv, `git` status information and the exit code of the last command run.
* [powerzeesh](https://github.com/sevaho/Powerzeesh) - A Powerline based ZSH theme. It aims for simplicity, showing information only when it's relevant, optimized for speed and look. Inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) - A collection of themes for Sublime Text, Terminal, iTerm 2 and ZSH.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) - 为黑暗终端主题优化的主题.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - Prezto port of oh-my-zsh's cloud prompt.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda 主题（用于 prezto）.
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
* [probe](https://github.com/probe2k/probe_zsh) - Includes `git` status decorations.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight ZSH prompt, based on the powerline font from the popular eponymous `vim` plugin, which works well for a dark background.
* [prompt](https://github.com/nathanblair/prompt)  - 在 `sh`、`dash`、`ash`、`zsh` 和 `pwsh` 中一致的轻量级提示. 包括 `git` 状态装饰.
* [prompt_j2](https://github.com/malinoskj2/prompt_j2) - Has a dynamic exit status indicator, can change to two lines dynamically to display context.
* [promptus](https://github.com/willeccles/promptus)  - 简单、简约且可配置的 C 语言 shell 提示程序，可用于使您的提示在任何 shell 上都相同. 包括退出代码和工作目录装饰.
* [pronto](https://github.com/jthat/zsh-pronto) - Simple and fast theme with `git` decorations and timing information.
* [ps1.py](https://github.com/jwodder/ps1.py) - Has `git` status, truncated directory, `chroot` and `virtualenv` prompt decorations.
* [pskfyi](https://github.com/pskfyi/zsh-theme) - Based on [lambda](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#lambda). Themed for ubuntu but easily tweaked.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - 易于定制，受 [spaceship](https://github.com/denysdovhan/spaceship-prompt).
* [pure-agnoster](https://github.com/yourfin/pure-agnoster)  - pure 和 agnoster 的混搭. 具有 `git` 装饰，适用于深色和浅色终端背景.
* [pure](https://github.com/sindresorhus/pure) - A pretty, minimal and fast ZSH prompt. Includes `git` status decorations, prompt turns red if last command failed, username and host decorations when in a remote session or container, and current folder and command when a process is running.
* [purify (banminkyoz)](https://github.com/banminkyoz/purify) - 一个简单、快速和酷炫的提示.
* [purify (kyoz)](https://github.com/kyoz/purify)  - 干净而充满活力的主题，最适合深色背景. 包括 `git` 状态装饰.
* [purity](https://github.com/petermbenjamin/purity) - 灵感来自 robbyrussell 主题和 [pure](https://github.com/sindresorhus/pure) prompt.
* [purs](https://github.com/xcambar/purs) - A fast [pure](https://github.com/sindresorhus/pure)-灵感提示写在 [Rust](https://www.rust-lang.org/).
* [pustelto](https://github.com/Pustelto/shell_theme) - 色彩缤纷的主题灵感来自 [Spaceship](https://github.com/denysdovhan/spaceship-prompt) theme, includes `git` decorations.
* [qi3ber2](https://github.com/nichus/qi3ber2)  - 一个黑暗的多线主题. 包括`git`，最后一个命令装饰器的平均负载和退出代码.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon) - Optimized for dark backgrounds, includes `git` information. Theme repo includes iTerm 2 and Terminal color settings.
* [quewui](https://github.com/kauefontes/oh-my-quewui) - Simple and clean theme optimized for dark terminal themes. Includes status decorations for the current time, user, directory and `git` status.
* [r3nic1e](https://github.com/r3nic1e/r3nic1e) - [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 具有电池状态、`git/hg` 状态、时间、kubernetes 上下文和命名空间、最后一个命令的非零退出代码和日期装饰的变体. 需要电力线字体.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - Based on af-magic and posh-git.
* [radium](https://github.com/dimitardimitrov/radium) - Designed for dark terminals, (works best with [Solarized](https://github.com/altercation/solarized) iTerm 2 theme) (prezto).
* [radius](https://github.com/erikcc02/radius-zsh-theme) - 包括 `git` 状态装饰，包括 [desk](https://github.com/jamesob/desk) 支持.
* [rafiki](https://github.com/akabiru/rafiki-zsh) - Adds emojis to your ZSH terminal.
* [ramiel](https://github.com/aknackd/zsh-themes) - Fork of the [node](https://github.com/skuridin/oh-my-zsh-node-theme).
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - Based on [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) 和“robbyrussell”主题.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - Random emoji.
* [ranger-zoxide](https://github.com/fdw/ranger-zoxide) - 添加 [zoxide](https://github.com/ajeetdsouza/zoxide) 支持 [ranger](https://github.com/ranger/ranger) console file manager.
* [raspberrysh](https://github.com/MaxMalinowski/raspberrysh) - Includes `git`, python, time, current host and path decorations.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) - 带有“git”状态装饰的简单而多彩的主题.
* [raz](https://github.com/razman786/ohmyzsh-theme-raz) - Minimal prompt, includes `git` status decorations.
* [rb](https://github.com/rberenguel/rb-zsh-theme) - Powerline-styled ZSH theme based on [Agnoster](https://gist.github.com/agnoster/3712874), optimized for `git` and solarized terminals. Requires a Powerline-compatible font.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - 针对日晒终端配色方案进行了优化，包括 `git` 状态装饰.
* [redline](https://github.com/DrissTM/redline.zsh-theme) - Minimalist theme. Includes `git` status, time, user.
* [reggae](https://github.com/nmercado1986/zsh-reggae-theme) - 使用颜色编码的状态装饰将大量信息压缩到提示中.
* [rei](https://github.com/arturoalviar/rei-zsh-theme) - 一个简单的主题，第一个字符是零（rei），数字 0.包括 `git` 状态装饰.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), 优化为 [solarized](https://github.com/altercation/solarized) terminal themes.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - Prezto ZSH theme based on Sorin, using emojis for tracking GIT context.
* [rho](https://github.com/andrejreznik/rho-zsh-theme) - 极简主义主题.
* [ribbon](https://github.com/tactlessfish/ribbon-prompt) - Reminiscent of powerline. Includes Python `virtualenv` decorator.
* [river](https://github.com/revir/river-zsh-config) - Dark theme with `git` information.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - Based on ideas from the the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题和项目 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - 用输出装饰 `robbyrussell` 主题以指示 **WIP** 提交.
* [robbyrussell-fullpath](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) - The original [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) with a fullpath in the prompt.
* [rocket](https://github.com/Alexandresl/rocket-zsh-theme) - Minimalist theme, includes `git` and `hg` status decoration.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - 一个黑暗的主题.
* [roundy](https://github.com/nullxception/roundy)  - 快速、可爱和圆润的主题. 包括 `git` 装饰. 需要 nerd 字体和支持 unicode 的终端应用程序.
* [roz](https://github.com/rozNum/roz-zsh-theme) - Minimalist. Includes `git` status decorations, best on a darker background.
* [rs](https://github.com/rogeliosamuel621/rs-zsh-theme)  - 包括 `git` 装饰. 需要支持 unicode 的终端.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) - Optimized for dark backgrounds.
* [rummik](https://github.com/rummik/zsh-theme) - @rummik's theme. Supports [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), 和 `git` 提示中的状态信息.
* [russtone](https://github.com/russtone/prompt-russtone) - 灵感来自 [pure](https://github.com/sindresorhus/pure) and [sorin](https://github.com/sorin-ionescu/prezto) . 包括 `git` 状态装饰.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - 色彩丰富的主题，包括 `git` 装饰和当前目录.
* [rzh](https://github.com/patwhatev/rzh) - 带有 git 状态的主题由表情符号指示.
* [s1ck94](https://github.com/zimfw/s1ck94) - Fork of the (first deprecated, now extinct) minimal prompt by S1cK94. Shows whether user is root, background job status, vi-mode, exit status of last command, and `git` status decorations.
* [s7c](https://github.com/Samega7Cattac/s7c.zsh-theme)  - 适用于深色背景. 包括 `git` 状态装饰.
* [samshell](https://github.com/samuelb/samshell) - A minimalist zsh theme with `git`, kubernetes and python virtualenv decorations.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - Includes `git` status decorations, works well on a dark terminal background.
* [saturn](https://github.com/gantoreno/saturn-prompt) - 为那些热爱空间并希望在终端上拥有一点空间的人提供柔和而简约的提示，具有酷炫的表情符号和高度可定制的提示元素（例如图标、颜色、时间格式等）.
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) - Shows `git` status decorations, user@host information, the exit status of last command, and whether running as root.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - Shows if `vim` is running in the background when using `:sh` command.
* [scythe](https://github.com/kostoskistefan/scythe)  - 让人想起电力线的主题. 包括`git`，最后一个命令退出状态和目录装饰.
* [sdkman](https://github.com/matthieusb/zsh-sdkman) - 添加选项卡完成 [sdkman](https://sdkman.io/).
* [seashell](https://github.com/jottenlips/seasonal-zshthemes)  - 带有海洋灵感的表情符号装饰的最小主题. 包括 `git` 状态装饰.
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - 这个主题使用了许多特殊的 unicode 字符来花哨，但是如果没有很好的字体支持，它可能会导致一些问题.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - 受节食者主题启发，使用颜色编码提供信息.
* [senpai](https://github.com/hiroru/senpai-zsh)  - 为 Devops 清理提示主题. 包括 `git` 状态信息、kubernetes 上下文、AWS 配置文件、GCP 项目和 Azure 活动云.
* [sepshell](https://github.com/sepehr/sepshell) - 基于丢失的旧 taybalt 主题的干净和最小的 ZSH 主题，具有 `git` 平分/合并/变基模式和可配置的提示符号.
* [serious](https://github.com/oliversandli/serious-zsh-theme) - Includes command exit status and `git` status decorations.
* [seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - 一个简单的 omz 兼容主题，带有相应的 iTerm 2 配色方案.
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - 精益提示的演变，它本身就是对纯的重写.
* [shadow](https://github.com/agentshadow/shadow-zsh-theme) - 包括 `git` 状态、目录、主机名、用户名和时间装饰.
* [shayan](https://github.com/shayanh/shayan-zsh-theme) - 带有 `git` 状态装饰的简单主题.
* [shelby](https://github.com/athul/shelby)  - 用纯“golang”编写的快速、轻量级和最小提示. 包括最后一个命令退出状态、`git` 状态和当前工作目录的装饰.
* [shellder](https://github.com/simnalamburt/shellder)  - 带有 git 分支显示的最小主题. 需要与电力线兼容的字体.
* [shichi](https://github.com/arturoalviar/shichi-zsh-theme) - A simple theme with the first character being 七(shichi/nana), the number 7. The primary color is red with a yellow accent. Includes `git` status decorations.
* [shini](https://github.com/bashelled/shini) - A tiny theme that just shouts out small. Includes directory, username, hostname, time and `git` decorations.
* [shirnschall](https://github.com/shirnschall/shirnschall-zsh-theme) - Includes `git` status and `user@hostname` decorations.
* [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) - 分叉自 [sixlive](https://github.com/sixlive/sixlive-zsh-theme) . 有 `git` 装饰.
* [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) - Based on the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme. Includes `git` and `hg` status decorations.
* [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) - 包括 `git` 装饰.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - 显示当前目录和 git 信息的简单主题.
* [shtr0m](https://github.com/kyle-pollock/shtr0m) - Includes `git` status decorations.
* [siegerts](https://github.com/siegerts/zsh-theme) - 在正确的提示中包含 `git` 状态装饰.
* [silver](https://github.com/reujab/silver) - A cross-shell customizable powerline-like prompt heavily inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) . 更快的生锈端口 [bronze](https://github.com/reujab/bronze). Requires [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts). Very configurable, includes `git` status decorations.
* [simpalt](https://github.com/m-lima/simpalt) - An information-rich small-footprint theme for ZSH based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [simple (daopengz)](https://github.com/DaopengZ/simple-zsh-theme)  - 适用于浅色和深色终端主题. 包括 `vcs`、`username` 和 `path` 装饰.
* [simple (pavdmyt)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - 基于极简主义主题 [robbyrussel](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 在 iTerm 的窗口标题栏中嵌入 `git` 状态信息，而不是在提示中使用空格.
* [simple (savecoders)](https://github.com/Savecoders/simpleTheme-zsh-theme) - Simple and minimalist theme with `git`, `username` and execution status decorations.
* [simple (tourcoder)](https://github.com/tourcoder/simple.zsh-theme) - 极简提示，包括 `git` 状态装饰.
* [simple (yhiraki)](https://github.com/yhiraki/zsh-simple-prompt) - 最小提示，不需要特殊字体.
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - 受电力线启发的简单主题，带有 `git` 装饰.
* [simple-git](https://github.com/BazaJayGee66/simple-git-theme) - Minimalist theme inspired by [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme). Includes `git` decorations.
* [simple-yet-beautiful](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme) - Minimalist theme. Includes `git` status and `user@host` prompt decorations.
* [simplezsh](https://github.com/fr0zn/simplezsh) - 带有 `git` 信息显示的最小主题.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme)  - k-kinzal 的 sinon 主题. 包括 `git` 状态装饰.
* [sit](https://github.com/svensen/sit.zsh-theme) - 带有 `git`、命令退出状态和路径装饰的极简主义主题.
* [sixlive](https://github.com/sixlive/sixlive-zsh-theme)  - 这个主题有一个独特的目录列表. 在 `git` 项目中，目录显示范围为当前存储库根目录.
* [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9 的 ZSH 主题.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Theme collection for Atom, Prism and ZSH inspired by Skeletor from He-Man and the Masters of the Universe.
* [skill](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - 针对黑暗终端进行了优化，显示 `git` 状态装饰.
* [skull](https://github.com/tahadostifam/skull-zsh) - 包括 `git` 状态、python 虚拟环境和 ruby​​ `rvm` 状态装饰.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH 主题灵感来自 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [odin](https://github.com/tylerreckart/odin).
* [slick](https://github.com/nbari/slick) - Inspired by the [pure](https://github.com/sindresorhus/pure), [purs](https://github.com/xcambar/purs) and [zsh-efgit-prompt](https://github.com/ericfreese/zsh-efgit-prompt) . 安装时需要`cargo`.
* [slimline](https://github.com/mengelbrecht/slimline)  - 最小、快速和优雅的 ZSH 提示. 在正确的时间显示正确的信息.
* [sm](https://github.com/blyndusk/sm-theme) A **Simplist** & **Minimalist** theme for your **favorite** terminal. Includes `git` status decorations.
* [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) - 的变体 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 主题在 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - 带有快乐和悲伤面孔的提示.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme)  - 受老式爱好启发的简约 ZSH 主题. 没有冗长的噱头，没有表情符号，没有烦躁的微调器，也没有其他视觉噪音. 具有明暗模式.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - Solarized powerline variant.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) - ZSH 的太阳能电力线风格主题.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) - Color fix for robbyrussell's oh-my-zsh theme to work with [solarized](https://github.com/altercation/solarized) 终端.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) - Theme with `git`, `nvm`, rvm/rbenv/chruby, python, `ssh` and other useful status indicators.
* [spowerline](https://mbauhardt.github.io/spowerline/) - 用 scala 编写，灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), [tmux](https://tmux.github.io) powerline, vim powerline and the vim status plugin.
* [spyrhoo](https://github.com/FajarKim/spyrhoo-zsh-theme) - Includes time, `git` and current directory decorations.
* [squanchy](https://github.com/gabrielecanepa/zsh-custom/tree/master/themes)  - 极简主义主题. 包括 `git`、`node` 和 `rbenv` 状态装饰.
* [ssfprompt](https://github.com/hugoh/zsh-ssfprompt)  - 简单、纤薄、快速. 包括 `ssh`、virtualenv 和 vcs 装饰.
* [staples](https://github.com/dersam/staples) - 基于局，如果通过 SSH 连接，则显示 user@host.
* [starboy](https://github.com/prdpx7/Starboy) - A simple ZSH theme.
* [starship](https://starship.rs/) - Minimal, fast, extremely customizable.
* [statusline](https://github.com/el1t/statusline) - A responsive ZSH theme that provides informational segments when you need them.
* [steef (danihodovic)](https://github.com/danihodovic/steeef) - ZSH steeef theme as a standalone repository. The purpose behind this repo is avoid having a dependency on oh-my-zsh when using the steeef theme. ZSH plugin managers such as Antibody can use the theme without having to use oh-my-zsh.
* [steef (zimfw)](https://github.com/zimfw/steeef) - A customizable version of [steeef's](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) 主题.
* [stellachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/stellachar.zsh-theme) - 最小，粉彩.
* [sublime](https://github.com/pjmp/sublime) - A sublime, clean, minimalistic ZSH theme with `git` status decorations.
* [sugar-free](https://github.com/cbrock/sugar-free) - Based on the [Pure](https://github.com/sindresorhus/pure) and [Candy](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/candy.zsh-theme) 主题.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme)  - 包括 `git` 状态装饰. 在深色终端背景下效果更好.
* [sulfurium](https://github.com/Sulfurium/zsh-theme) -sulfiumOS 的官方 ZSH 主题.
* [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) - 如同 [sunrise](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) 但包括活动的 Ruby 版本.
* [superkolo](https://github.com/Minipada/superkolo) - Add date and return status to the [kolo](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) 主题.
* [susi](https://github.com/carcruz/susi-zsh-iterm) - 包括 `git` 状态装饰和随附的 iTerm2 配色方案.
* [svs](https://github.com/SvS30/svs-theme) - Clean and distraction free theme with `git` status and current path decorations.
* [sy](https://github.com/ttttmr/sy-zsh-theme) - Based on [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), 包括 `git` 状态装饰.
* [t2er](https://github.com/t2er/t2er-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - Minimal ZSH theme optimized for dark backgrounds.
* [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) - 包括 `git` 状态装饰和 conda/virtualenv 状态.
* [termux](https://github.com/rooted-cyber/Termux-zsh-theme) - 极简主义主题.
* [termuxer](https://github.com/patrick330602/termuxer) - 主题灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和linuxer.
* [the-time-lord](https://github.com/jhwhite/the-time-lord) - A theme based on [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - 带有 `git` 状态的彩色主题.
* [theta-async](https://github.com/jesec/zsh_theme_theta-async) - 异步版本 [theta](https://github.com/eendroroy/theta). Includes vcs status information.
* [theta](https://github.com/eendroroy/theta) - Includes `git` and `hg` status decorations. Also has java, python, ruby, node, go and elixir version information.
* [theto](https://github.com/heyvito/theto-zsh-theme)  - 简单的主题. 需求 [Nerd Fonts](https://nerdfonts.com/), includes `vi`-mode status and `git` decorations.
* [thetraveler](https://github.com/bassopenguin/thetraveler) - 受 unraveler 启发，使用符号来显示 `git` 状态.
* [thnikk](https://github.com/thnikk/zsh-theme-thnikk) - 的最小版本 [spaceship](https://github.com/denysdovhan/spaceship-prompt) 主题.
* [thyme (chenhao-ye)](https://github.com/chenhao-ye/thyme) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme), and [bullet-train](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme).
* [thyme (kawamurakazushi)](https://github.com/kawamurakazushi/thyme) - 带有 `git` 状态装饰的简单主题.
* [toledo](https://github.com/mmatongo/toledo) - 带有 `git` 状态装饰的快速简约主题.
* [tonni4](https://github.com/AndreyPuzanov/tonni4-zsh-theme) - 包括时间和 `git` 状态装饰器.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh)  - 包括`git`信息； 最好在深色背景上.
* [tq](https://github.com/kitian616/tq-zsh-theme) - Displays `git` status, time, requires a Powerline font.
* [traffic](https://github.com/fcce/traffic-zsh-theme) - A dark theme for ZSH.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH.
* [trinity](https://github.com/de-luca/Trinity) - A simple theme based on [geometry](https://github.com/geometry-zsh/geometry). Includes `git` decorations.
* [tron](https://github.com/iDoTron/tron-zsh-theme) - 包括 `git` 状态、工作目录、时间、user@host 和最后一个命令装饰的返回状态.
* [tsotra](https://github.com/nylo-andry/zsh-themes) - Minimalist theme, includes `git` status decorations, k8s context, and `rvm` status.
* [turs](https://github.com/eikendev/turs) - 快速，最小 [Purs](https://github.com/xcambar/purs)-启发提示.
* [tvline](https://github.com/thvitt/tvline) - Derived from the [agnoster](https://gist.github.com/agnoster/3712874) theme, adds powerline font enhancements.
* [twilight](https://github.com/Henryws/twilight-prompt) - Minimalist, but includes last command exit status, `git` status and `user@hostname` decorations.
* [type0](https://github.com/MikereDD/type0_zsh-theme) - 灵感来自 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) by yarisgutierrez. Includes `git` decorations.
* [typewritten](https://github.com/reobin/typewritten)  - 最小和信息丰富的主题，为重要的事情留下空间. 异步 `git` 装饰更新以提高速度.
* [ubunly](https://github.com/alejandromume/ubunly-zsh-theme)  - 模仿 Kali Linux 控制台. 注意 - 这个主题还重新绑定了很多键并设置了一些主题应该不理会的 ZSH 选项.
* [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) - 模仿默认的 Debian/Ubuntu `bash` 提示符.
* [ubuntu-with-vitamins](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) - 模仿默认的 Ubuntu 提示符，但带有 `git` 装饰.
* [ubuntu](https://github.com/janstuemmel/zsh-ubuntu-theme) - 最小主题，包括 `git` 状态装饰.
* [ultimate](https://github.com/b4b4r07/ultimate) - 带有 `git` 指示器、vim 模式指示器和缩短路径的极简主义主题.
* [unicorn](https://github.com/juliuscaesar/unicorn) - Inspired by the [Wild Cherry](https://github.com/mashaal/wild-cherry) 主题. 有表情符号`git`状态装饰.
* [unit-1](https://github.com/nerdbude/Unit-1) - 带有 ITWTB 颜色的极简主义主题.
* [vanan](https://github.com/avano/vanan-zsh-theme) - Minimalist theme with `git` information for dark terminals.
* [vercel](https://github.com/vercel/zsh-theme) - Minimalist theme with `git` status decorations.
* [vertepommes](https://github.com/TheRojam/vertepommes-theme)  - 基于ys. 包括 vcs 状态、用户名和当前目录装饰.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - Modified from themes/mgutz.zsh-theme.Looks great when using with a [Solarized](https://github.com/altercation/solarized) color scheme.
* [vitesse](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) - Inspired by VS Code's [Vitesse](https://github.com/antfu/vscode-theme-vitesse) theme. Includes `git` status decorations.
* [vulcan](https://github.com/Bruceboy/vulcan-zsh-theme)  - 最小的主题让人想起默认的“bash”主题. 包括 `git` 装饰.
* [wade](https://github.com/wadehammes/wade.zsh-theme) - 流行的 ZSH 主题的混搭 [Agnoster](https://gist.github.com/agnoster/3712874) and [Fishy](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme)，有一些视觉上的调整.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) - 基于0532主题.
* [whale](https://github.com/whalesea520/whale-zsh-theme) - 鲸鱼主题的快速重新实现.
* [whales](https://github.com/lbergelson/zsh_whales_theme) - 包括 `git` 状态、java 版本、最后命令返回状态和目录的装饰器.
* [wild-cherry](https://github.com/mashaal/wild-cherry) - A fairy-tale inspired theme for ZSH, iTerm 2, Sublime, Atom, & Mou.
* [wkentaro](https://github.com/wkentaro/wkentaro.zsh-theme)  - Python 用户的简单主题. 包括 virtualenv 和 `git` 状态装饰器.
* [work-line](https://github.com/afnizarnur/work-line) - Theme with nice emojis.
* [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) - 包括`git`状态装饰、工作目录、最后一个命令的退出状态和当前`virtualenv`.
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme) - A theme that aims to show you the information you need when you need it. `wynwyn` takes inspiration from the default theme `avit` and the excellent [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xavi](https://github.com/onthedock/xavi.zsh-theme) - 修改版 [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 带有 `git` 状态和当前目录的表情符号装饰的主题.
* [xlk-simple](https://github.com/xuelingkang/xlk-simple-zsh-theme) - 带有 `git` 装饰的简单主题.
* [xm](https://github.com/Shiaoming/xm)  - 黑暗终端的主题. 有 `git` 装饰.
* [xor](https://github.com/xor3n/xor-zsh-theme) - 自我描述为简约和“功能差”，包括 `git` 装饰.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - 基于 Jreese 主题插件的 oh-my-zsh shell 主题.
* [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme)  - 快速、简单和流线型的主题. 最适合搭配 [tmux](https://github.com/tmux/tmux/wiki) and [vim-airline](https://github.com/vim-airline/vim-airline).
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - 显示当前 git 提交的缩短哈希和消息.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme)  - 带有行分隔提示的最小主题. 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题.
* [yazpt](https://github.com/jakshin/yazpt) - 一个干净、快速、美观的 ZSH 提示主题，精心整合了 Git/Subversion/TFVC 状态信息，与 Oh My Zsh 等流行的插件管理器集成，并且易于定制和扩展.
* [yechen](https://github.com/liyechen/yechen.zsh-theme) - Minimalist theme with `git` status decorations.
* [yeet](https://github.com/jeetelongname/Yeet-theme) - 带有“git”状态装饰的极简提示.
* [yindev](https://github.com/menyinch/yindev-zsh-theme)  - `gndx` 的变体. 包括 `git` 状态和当前目录的装饰.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - Modified from [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) theme and optimized for a dark background.
* [ys (cristiancavalli)](https://github.com/cristiancavalli/ys-zsh-custom-theme) - 干净、简单、兼容和有意义的主题，适用于深色背景.
* [ys (tinyRatP)](https://github.com/tinyRatP/ys) - 变体 [ys](https://gist.github.com/ysmood/6110461).
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - `ys` variant with support for working with batch submission systems for large clusters. Supports Slurm, LSF / IBM Spectrum LSF, and PBS.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - 带有 `git` 状态信息的简单 ZSH 主题.
* [ysr](https://github.com/raykle/ysr-zsh-theme) - Based on `ys`. Includes `git` status decorations.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - A dark optimized ZSH theme.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - 包括 conda 和 venv 状态.
* [yz50](https://github.com/lacanlale/yz50-zsh) - 多彩，基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and [crunch](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) 主题. 包括 `git` 状态装饰.
* [z4rr3t](https://github.com/inimicus/z4rr3t) - 基于sindresorhus&#39; [pure](https://github.com/sindresorhus/pure) 主题.
* [zcraft](https://github.com/cpea2506/zcraft) - Minimalist theme with decorations for `git` status, last command exit status and the time taken by the last command.
* [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme) 以塞尔达为灵感的主题. 包括 `git` 状态装饰.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - 定制版 oh-my-zsh [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) with mercurial support and other changes.
* [zemoji](https://github.com/therzka/zemoji) - Based on [wild-cherry](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ https://github.com/mashaal/wild-cherry/tree/master/zsh). Includes exit status, `virtualenv`, `nvm`, `rvm` and `git` status decorations.
* [zero](https://github.com/arlimus/zero.zsh)  - Zero 的主题和插件. 具有浅色和深色终端背景的变体.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - 在深色背景下效果最佳，包括 `git` 状态装饰.
* [zerocake](https://github.com/ZeroPoke/ZeroCake.zsh-theme) - 在黑暗的草地上效果更好.
* [zest](https://github.com/hash-bang/zsh-theme-zest) - A functional theme for ZSH. Influenced by [zsh2000](https://github.com/consolemaverick/zsh2000), [agnoster](https://gist.github.com/agnoster/3712874) and [powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) 主题.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) - 显示用户名、`git` 状态信息、机器名称、当前工作目录和上一个命令的成功/失败状态.
* [zinc](https://gitlab.com/robobenklein/zinc) - 一个极快、纯 ZSH、混合异步电力线提示，易于扩展且极其可配置.
* [zlambda](https://github.com/wdhg/zlambda) - Minimalist, includes `git` decorations without special font requirements.
* [zodiac](https://github.com/adamalsen/zsh-zodiac) - 包括与当前年份对应的动物表情符号.
* [zprompts](https://github.com/z-shell/zprompts) - Themes (prompts) that use original `zsh` theming subsystem.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) - 修改版 oh-my-zsh&#39;s [maran](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) 主题.
* [zsh1999](https://github.com/DTan13/zsh1999) - 包括网络连接、电池和 `git` 状态装饰.
* [zsh2000](https://github.com/consolemaverick/zsh2000) - Powerline looking ZSH theme which includes the `rvm` prompt, `git` status and branch, current time, user, hostname, pwd, exit status, whether running as root and background job status.
* [zsh313](https://github.com/amirali313/zsh313-theme) - 带有 `git` 状态装饰的最小主题.
* [zshcomrade](https://github.com/landongn/zshcomrade) - A ZSH theme, comrade!
* [zshpower](https://github.com/snakypy/zshpower)  - 针对 python 开发人员进行了优化. 包括 `git` 和 `pyenv` 状态装饰、用户名和主机. 尝试安装其他插件和字体，因此请在安装前阅读其说明.
* [zshred](https://github.com/redxtech/zshred) - 显示当前目录、`git` 装饰、最后一个命令的退出状态和时间.
* [zwsh](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for ZSH.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) - 如同 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme)，旨在根据上下文披露信息，具有电力线美学.
* [zzshell](https://github.com/thezzisu/zzshell) - 受默认启发 [Oh-My-Zsh](http://ohmyz.sh/) theme. Displays exit code and `git` status decorations. Doesn't require Powerline fonts.

## Fonts

此处列出的一些主题需要与 Powerline 兼容的字体，以下是一些：

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that includes some nice monospaced Icons.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - 一个漂亮的等宽字体，用 Font-Awesome、Octoicons 和 Powerline-Glyphs 修补.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - 另一种与电力线兼容的字体.
* [Hack](https://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
* [Input Mono](https://store.typenetwork.com/foundry/djr/series/input?family=input-mono) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes powerline glyphs.
* [Iosevka](https://github.com/be5invis/Iosevka)  - 编码器的字体，由代码构建. 高度可定制.
* [Monoid](https://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more.
* [Powerline patched font collection](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include powerline gylphs.
* [Terminus](http://files.ax86.net/terminus-ttf/) - 包含电力线字形的 Terminus 的 TTF 版本.

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start `zsh`. You can also add the plugin to a running ZSH with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1. Clone new plugins into `.zsh.local/modules`
2. Load the plugin module in `.zshrc`
3.打开一个新的ZSH终端窗口或标签

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. Add the repo to your plugin list

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. Clone the plugin into your prezto modules directory
2. Add the plugin to your `.zpreztorc` file
3. Open a new terminal window or tab

### [Zgen](https://github.com/tarjoilija/zgen)

 Zgen 没有得到积极维护. 考虑切换到 [Zgenom](https://github.com/jandamm/zgenom) 叉子，也就是.

### [Zgenom](https://github.com/jandamm/zgenom)

Most of these plugins can be installed by adding `zgenom load githubuser/reponame` to your .zshrc file in the same function you're doing your other `zgenom load` calls in.

Zgenom will automatically clone the plugin repositories for you when you do a `zgenom save`.

### [zplug](https://github.com/zplug/zplug)

这些插件中的大多数都可以通过将 `zplug &quot;githubuser/reponame&quot;` 添加到您的 `.zshrc` 文件中来安装.

### [zpm](https://github.com/zpm-zsh/zpm)

这些插件中的大多数可以通过将 `zpm load &quot;githubuser/reponame&quot;` 添加到您的 `.zshrc` 文件中来安装.

## Writing New Plugins

I've documented some recommendations for writing a new plugin [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

There is also a more detailed [Zsh Plugin Standard](https://zdharma-continuum.github.io/Zsh-100-Commits-Club/Zsh-Plugin-Standard.html).

## Other Resources

### ZSH Tools

* [ShellSpec](https://github.com/shellspec/shellspec) - 用于 dash、bash、ksh、ZSH 和所有 POSIX shell 的全功能 BDD 单元测试框架.
* [zsh-bench](https://github.com/romkatv/zsh-bench)  - 交互式 ZSH 的基准. 它测量交互式“zsh”的用户可见延迟：输入延迟、命令延迟等
* [zshdb](https://github.com/rocky/zshdb) - ZSH 调试器.
* [zshelldoc](https://github.com/zdharma-continuum/zshelldoc) - Doxygen for shell scripts. Parses ZSH and Bash scripts, outputs Asciidoc document with function lists, call trees, lists of exported variables, and more.
* [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH.

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - 精选的工具、资源和工作流程技巧列表，打造出色的开发环境
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - 精选的开源系统管理员资源列表
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - A curated list for CLI lovers.

Find other useful awesome-* lists at the [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

- 这 [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) are indispensable.

- [Mastering ZSH](https://github.com/rothgar/mastering-zsh) is a great tutorial that builds on the basics to show you advanced ZSH usage, customizations, and practical examples.
