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

ZSH 框架、插件、教程和主题的集合，灵感来自各种很棒的列表集合.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*请阅读 [Contributing Guidelines](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Contributing.md) before contributing.*

## Frameworks

这些框架使自定义 ZSH 设置更加容易.

您可以在以下位置找到各种框架的一些有趣的性能时序比较.

* [rossmacarthur/zsh-plugin-manager-benchmark](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark)
* [pm-perf-test](https://github.com/z-shell/pm-perf-test) - Tooling for running performance tests on multiple ZSH frameworks.
### [alf](https://github.com/psyrendust/alf)

**Alf** is an out of this world super fast and configurable framework for ZSH; it's modeled after Prezto and Antigen while utilizing Oh-My-Zsh under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

 **ansible-role-zsh** 是一个零知识安装的 ansible 角色. 它使用抗原来管理捆绑包和 oh-my-zsh. 可以有条件地加载包. 默认情况下，它包括 powerlevel9k 主题、自动建议、语法高亮和 [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) 和 [fzf-marks](https://github.com/urbainvaes/fzf-marks). Fully customizable.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody](https://github.com/getantibody/antibody)

**Antibody** is a faster and simpler antigen written in Golang. More details at [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

 **antigen-hs** 是抗原的替代品，优化了启动外壳时的低开销. 它会自动为您克隆插件.

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

**miniplug** 是 ZSH 的简约插件管理器.

* 重新采购 .zshrc 时没有崩溃或双重插件加载
* Unlike other frameworks, Miniplug does not pollute your $PATH
* 只做最低限度的插件管理

### [mzpm](https://github.com/Insert-Creative-Name-Here/mzpm)

**mzpm** 是 ZSH 的极简插件管理器.

Features:

- Fetching and loading plugins from GitHub
- Loading local plugins
- 加载主题

### [oh-my-zsh](https://ohmyz.sh/)

**oh-my-zsh** is a community-driven framework for managing your ZSH configuration. Includes 120+ optional plugins (rails, git, macOS, hub, capistrano, brew, ant, macports, etc), over 120 themes to spice up your morning, and an auto-update tool that makes it easy to keep up with the latest updates from the community.

### [PMS](https://github.com/JoshuaEstes/pms)

PMS allows you to manage your shell in a way to that helps decrease setup time and increases your productivity. It has support for themes (change the way your shell looks), plugins (adds functionality to your shell), and dotfile management.

 PMS 框架还允许您在不同的 shell 中使用相同的框架. 在您的个人笔记本电脑上使用 ZSH，并在远程服务器上使用 bash. 想尝尝鱼吗？ 来吧，尝试不同的贝壳.

### [prezto](https://github.com/sorin-ionescu/prezto)

**Prezto** enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes. There are some prezto-specific plugins at [https://github.com/belak/prezto-contrib](https://github.com/belak/prezto-contrib).

### [pumice](https://github.com/ryutamaki/pumice)

**Pumice** is a lightweight plugin manager for ZSH.

### [pz](https://github.com/mattmc3/pz)

 ZSH 的插件管理器不一定要复杂才能强大. 当 PZ 可以聪明时，它不会尝试变得聪明.  PZ 是一个功能齐全、快速且易于理解的插件管理器，封装在一个文件中，包含大约 200 行干净的 ZSH.

 PZ 足以很好地管理您的 Zsh 插件，然后让您摆脱困境. 它也经过单元测试，以确保它按预期工作！

### [sheldon](https://github.com/rossmacarthur/sheldon)

A fast, configurable, shell plugin manager.

* 可以管理
  * Any `git` repository.
    * 分支/标签/提交支持.
    * Extra support for GitHub repositories.
    * Extra support for Gists.
  * Arbitrary remote files, simply specify the URL.
  * Local plugins, simply specify the directory path.
*使用高度可配置的安装方法 [handlebars](http://handlebarsjs.com/) 模板.
* Super-fast parallel installation.
* 配置文件使用 [TOML](https://github.com/toml-lang/toml) 句法.
* Uses a lock file for much faster loading of plugins.

### [Toasty](https://github.com/5paceToast/toasty-zsh)

**Toasty** is a ZSH framework made to facilitate management, not dictate it.

### [tzpm](https://github.com/notusknot/tzpm)

The tiniest ZSH plugin manager. Still under development.

### [uz](https://github.com/maxrodrigo/uz)

A ZSH micro plugin manager.

### [yazt](https://github.com/bashelled/yazt)

 Yazt 是一个简单的 zsh 主题管理器，几乎与所有东西兼容. 您可以在插件中使用提示，混合 &#39;n&#39; 匹配两个主题，稍加修改，您甚至可以在 bash 中使用它.

### [zapack](https://github.com/aiya000/zsh-zapack)

zapack is a basic fast minimal ZSH plugin loader.

### [zcomet](https://github.com/agkozak/zcomet)

 **zcomet** 是一个简约的 ZSH 插件管理器，无需缓存即可让您快速获得提示（请参阅基准）. 除了加载和更新存储在 Git 存储库中的插件外，它还支持延迟加载插件（进一步减少启动时间）以及下载和获取代码片段.

### [zebrafish](https://github.com/mattmc3/zebrafish)

**Zebrafish** 是一个轻量级、功能齐全、速度极快的 ZSH 微框架，仅包含一个文件.

### [zeesh](https://github.com/zeekay/zeesh)

 **Zeesh** 是一个跨平台的 ZSH 框架. 它类似于，但不兼容， [oh-my-zsh](http://ohmyz.sh/). It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.

### [zgem](https://github.com/qoomon/zgem)

**Zgem** is a plugin manager for ZSH that supports loading and updating plugins and themes from git, http and local files.

### [zgen](https://github.com/tarjoilija/zgen)

**Zgen** is a lightweight plugin manager for ZSH inspired by Antigen. The goal is to have minimal overhead when starting up the shell because nobody likes waiting. It is currently not being actively maintained and I recommend you use the [zgenom](https://github.com/jandamm/zgenom) 叉子代替，这是.

### [zgenom](https://github.com/jandamm/zgenom)

A lightweight plugin manager for ZSH that is a fork that extends the brilliant [zgen](https://github.com/tarjoilija/zgen) 并提供更多功能和错误修复，同时完全向后兼容.

为了在新的终端会话期间保持快速加载，`zgenom` 会生成一个静态的 `init.zsh` 文件，它除了获取插件并将它们附加到您的 `fpath` 之外什么都不做.

This minimizes startup time by not having to execute time consuming logic (plugin checking, updates, etc) during startup. The downside is that you have to refresh the init script manually with `zgenom reset` whenever you update your plugin list in your `.zshrc`.

Zgenom can load [oh-my-zsh](http://ohmyz.sh/)-compatible and [prezto](https://github.com/sorin-ionescu/prezto)- 兼容的插件和主题，当您将它们添加到插件列表时，它们会自动为您“git clone”插件.

### [ZI](https://github.com/z-shell/zi)

**ZI** is a Swiss Army Knife for Zsh Unix shell. Formerly known as zplugin, zinit. ZI - [Wiki Pages](https://z-shell.pages.dev/).

Bonus: you can use [zi-console](https://github.com/z-shell/zi-console) 查看和更改 ZSH 会话的状态（例如：列出和卸载插件）并从磁盘中删除插件和片段.

### [zilsh](https://github.com/zilsh/zilsh)

**zilsh** is a ZSH config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim](https://github.com/zimfw/zimfw)

**Zim** is a ZSH configuration framework with blazing speed and modular extensions.

### [Zinit](https://github.com/zdharma-continuum/zinit)

**Zinit** 是一个创新的并且可能（由于 Turbo）最快的插件管理器，它支持：

- Turbo mode – 80% faster ZSH startup! for example: instead of 200 ms, it'll be 40 ms
- 完成管理（有选择地禁用和启用完成）
- Snippets (↔ regular files downloaded via-URL, e.g.: scripts) and through them Oh My Zsh and Prezto plugins support (→ low overhead)
- 附件（↔ Zinit 扩展）
- 报告（来自插件加载 - 插件不再是黑匣子）
- 插件卸载（允许例如：动态主题切换）
- `bindkey` 捕获和重新映射
- packages
- Clean `fpath` (the array `$fpath` is not being used to add completions and autoload functions, hence it stays concise, not bloated)
- 服务↔单实例后台插件
- Also, in general: all the mechanisms from the ZSH Plugin Standard – Zinit is a reference implementation of the standard.

The project is very active – currently > 3100 commits.

### [zit](https://github.com/thiagokokada/zit)

 **zit** 是 ZSH 的插件管理器. 它是最小的，因为它实现了作为插件管理器的最低要求：它允许用户从 Git 存储库（仅限 Git 存储库，它们为什么名称）安装插件，获取插件并更新它们. 它没有实现花哨的功能，例如清除已删除插件、自动编译已安装插件、oh-my-zsh/prezto/其他 ZSH 框架的别名、构建二进制文件、PATH 操作等.

### [znap](https://github.com/marlonrichert/zsh-snap)

**:zap:Znap** is a light-weight plugin manager & Git repo manager for ZSH that's easy to grok. While tailored for ZSH plugins specifically, Znap also functions as a general-pupose utility for managing Git repos.

Znap

Znap 可以：

 - 使任何提示立即出现. 只需一个命令即可将启动时间从 ~200ms 减少到 ~40ms.
- Asynchronously compile your plugins and functions.
- 缓存那些昂贵的`eval $(commands)`.
- Clone or pull multiple repos in parallel.
- Re-clone all your repos without you having to re-enter them.
- Multi-repo management
- 自动 `compinit` 和 `bashinit` - 你的 `.zshrc` 中不再需要它们，znap 会根据需要自动执行它们.

### [zoppo](https://github.com/zoppo/zoppo)

 **Zoppo** 是 ZSH 的残缺配置框架. 正如一句意大利谚语所说：“chi va con lo zoppo, impara a zoppicare”，我们意识到我们是带着跛子走路的，现在自己也会变成跛子.

### [zpacker](https://github.com/happyslowly/zpacker)

**Zpacker** is a lightweight ZSH plugin & theme management framework.

### [zpico](https://github.com/thornjad/zpico)

小巧的 ZSH 包管理器. 没有多余的装饰，没有臃肿，只有 2 kB 的 100% ZSH 代码，为您的 ZSH 环境提供完整的包管理.

### [zplug](https://github.com/zplug/zplug)

**:hibiscus: Zplug** is a next-generation ZSH plugin manager.

- 可以管理一切
  - Zsh 插件/UNIX 命令 [GitHub](https://github.com) 和 [Bitbucket](https://bitbucket.org)
  - 要点文件（[gist.github.com](https://gist.github.com/discover))
  - 外部管理的插件，例如， [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [prezto](https://github.com/sorin-ionescu/prezto) plugins/themes
  - Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
  - 本地插件
  - etc. (you can add your [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- Super-fast parallel installation/update
- 支持延迟加载
- 分支/标签/提交支持
- 更新后，加载后挂钩
- Dependencies between packages
- Unlike [antigen](https://github.com/zsh-users/antigen), 不需要 ZSH 插件文件 (`*.plugin.zsh`)
- 交互式界面（[fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw)， 等等）
- 减少缓存机制 [the startup time](https://github.com/zplug/zplug#vs)

### [zpm](https://github.com/zpm-zsh/zpm)

**zpm** ( ZSH Plugin Manager ) 是一个插件管理器 [ZSH](http://www.zsh.org/) 谁结合了命令式和声明式方法. 在第一次运行时，zpm 会做复杂的逻辑并生成缓存，之后将只使用缓存，因此它使这个框架非常快.

* 最快的插件管理器（真的，第一次运行后，zpm 根本不会用）
* 支持异步加载
* 包之间的依赖关系
* zpm runs on Linux, macOS, FreeBSD and Android.
* zpm plugins are compatible with [oh-my-zsh](http://ohmyz.sh/).

### [zr](https://github.com/jedahan/zr)

**zr** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zshing](https://github.com/zakariaGatter/zshing)

**zshing** 是一个类似于 Vundle/Vim 的 ZSH 插件管理器，允许您...

* 在 `.zshrc` 中跟踪和配置您的插件
* 安装 ZSH 插件
* Update ZSH plugins
* 按名称搜索所有可用的 ZSH 插件
* 清理未使用的插件
* run the above actions in a *single command*
* manages the __Source Plugins__ of your installed Plugins

### [ztanesh](https://github.com/miohtama/ztanesh)

**Ztanesh** aims to improve your UNIX command line experience and productivity with the the configuration provided by the ztanesh project: the tools will make your shell more powerful and easier to use.

### [ztheme](https://github.com/SkyyySi/ztheme)

ztheme 是一个小而快的 ZSH 主题引擎.

### [ztupide](https://github.com/mpostaire/ztupide)

一个简单快速的 ZSH 插件管理器. 它使用 zcompile 和异步加载来加快你的 shell 启动时间.

### [zulu](https://github.com/zulu-zsh/zulu)

**Zulu** 是 ZSH 5+ 的环境管理器，旨在让您无需编写任何代码即可轻松管理您的 shell.

* 无需编辑文件即可轻松管理您的 shell 环境.
* Create aliases, functions and environment variables, and have them available to you at the next shell startup.
* 使用简单的命令从 `$path`、`$fpath` 和 `$cdpath` 添加和删除目录.
* Install packages, plugins and themes easily, and have them available to you immediately.

## Setups

本节用于完整设置插件 - 它们不是框架，但它们也不是简单的插件/主题.

### zgenom

* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - A simple quickstart for using ZSH with [zgenom](https://github.com/jandamm/zgenom). This automatically configures ZSH to use [zgenom](https://github.com/jandamm/zgenom) 加载精选的插件集合并定期自动更新自身、插件和快速入门工具包本身.

### zinit

* [ZPWR](https://github.com/MenkeTechnologies/zpwr) - An extremely powerful custom terminal environment built on top of [Zinit](https://github.com/zdharma-continuum/zinit) for maximum speed.  A full terminal configuration framework including `zsh`, `tmux`, `fzf`, `vim` and spacemacs configurations.  It includes:

- 11.5k+ tab completions
- 1.9k+ 别名
- 330 多个 git 别名
- 350 多个 zpwr 子命令
- 2.1k functions
- 150+ zpwr 环境变量
- 170+ perl, python, bash, zsh scripts
- 2.8k line README.md
- 46k + LOC
- 1 行安装

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - 使用组合的教程 [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io)， 和 [Tmuxinator](https://github.com/tmuxinator/tmuxinator) to make for an extremely productive developer workflow.
* [Arch Linux's ZSH introduction](https://wiki.archlinux.org/index.php/zsh) -  Not actually Arch or Linux-specific.
* [GH](https://github.com/gustavohellwig/gh-zsh)  - 在基于 debian/Ubuntu 的 linux 上设置 ZSH. 安装 [Powerlevel10k](https://github.com/romkatv/powerlevel10k), [zsh-completions](https://github.com/zsh-users/zsh-completions), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting/), and more.
* [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - 关于如何安装和配置 ZSH shell 的初学者友好教程.
* [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) 涵盖了 ZSH 的一些 Bash 没有的特性，并使用了 oh-my-zsh.
* [rs-example](https://github.com/al-jshen/zshplug-rs-example) - An example plugin showing how a Rust program can listen to and process commands from ZSH.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
* [xVanjaZ](https://github.com/xVanjaZ/xVanjaZ-ZSH-Theme) - wrote a quick setup document for oh-my-zsh beginners showing how to use the [spaceship](https://github.com/denysdovhan/spaceship-prompt.git) 提示符、提示符处的语法高亮、自动提示和自定义 iTerm 2 主题.
* [ZSH for Humans](https://github.com/romkatv/zsh4humans)  - ZSH 的交钥匙配置，旨在开箱即用. 它将一组精选的 ZSH 插件组合成一个连贯的整体，感觉就像一个成品，而不是一个 DIY 入门套件.
* [ZSH Pony](https://github.com/mika/zsh-pony) - 涵盖在没有框架的情况下自定义 ZSH.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.
- [ZSH Unplugged](https://github.com/mattmc3/zsh_unplugged) - Good resource if you want to eliminate using a framework but still easily use plugins.

### Antigen

* [belak/zsh-utils](https://github.com/belak/zsh-utils) - 一组最小的 ZSH 插件，旨在低摩擦和低复杂性.
* [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean 关于从 oh-my-zsh 切换到抗原的文章.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis 对 Antigen 的介绍.

### Oh-My-Zsh

* [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - A beginners guide to oh-my-zsh by Dien Bui
* [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - Karl Hadwen 在 macOS 上使用 Oh My Zsh 的初学者指南
* [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders Ubuntu 安装指南
* [ZSH Gem 24](https://www.refining-linux.org/archives/59-ZSH-Gem-24-ZSH-frameworks.html) - Part of the 2011 ZSH Advent Calendar. Covers oh-my-zsh and zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, [Tmux](https://tmux.github.io) ＆Tmuxinator.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert 关于迁移到 Prezto 的博客文章.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) - A fantastically feature rich, lightning-fast shell setup, powered by [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto)， 和 [Zgen](https://github.com/tarjoilija/zgen).

### Zinit (né zplugin)

* [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh) - :crystal_ball: Awesome, customable Zsh Starter Kit :stars::stars:. Includes powerline, `fzf` integration, Weather and image viewing in some terminals.
* [zinit-configs](https://github.com/zdharma-continuum/zinit-configs) - Real-world configuration files (basically a collection of `.zshrc` files) holding [zinit](https://github.com/zdharma-continuum/zinit) 调用.

### ZSH on Windows

* [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only.

  * ConEmu/zsh out-of-the-box configured to restore previously opened tabs and shell working directories after ConEmu restart
  * 在启动新的 SuperConsole 会话时选择干净和继承的环境
  *自定义彩色方案，各种命令的彩色输出
  * MSYS2 included, `zsh` and necessary software preinstalled, uses zsh-grml-config
  * Uses Antigen for ZSH theme and config management
  * Enabled number of ZSH plugins to activate completion, highlighting and history for most comfortable use
  * Git-for-Windows repo with proper `git` and git lfs support for MSYS2 environment is configured, `git` client already installed.
  * `ssh-agent` for `git` works out-of-box, add your keys to `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` dir
  * Non-blocking ZSH prompt status updates thanks to agkozak-zsh-prompt
  * 为 MSYS2 定制的 command-not-found 处理程序建议安装什么包
  * Sets up `nano` as main editor, enables `nano` syntax highlighting
  * 自定义帮助脚本添加到 `ConEmu/msys64/3rdparty`

## Plugins

* [1999](https://github.com/DTan13/zsh1999)  - 电力线式主题. 包括 `git` 状态装饰、网络和电池状态.
* [256color](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen `TERM` environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
* [abbr (olets)](https://github.com/olets/zsh-abbr) - Manages auto-expanding abbreviations that expand inline when you hit space, inspired by fish shell.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - Provides functionality similar to `vim`'s abbreviation expansion.
* [accurev](https://github.com/dalefukami/accurev-zsh) - ZSH 插件 [accurev](https://www.microfocus.com/en-us/products/accurev/overview).
* [actiona](https://github.com/matthieusb/act) - 让打电话更容易 [actiona](https://github.com/Jmgr/actiona) 命令行中的脚本. 包括制表符补全.
* [alacritty](https://github.com/casonadams/alacritty-shell) - 控制 [alacritty](https://github.com/alacritty/alacritty/wiki/Color-schemes) 配色方案.
* [alehouse](https://github.com/sticklerm3/alehouse) - Contains short aliases for [brew](https://brew.sh) 命令，灵感来自 [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin).
* [alias-tips](https://github.com/djui/alias-tips) - An oh-my-zsh plugin to help remembering those aliases you defined once.
* [alias](https://github.com/xylous/alias-zsh) - Tool for managing your aliases.
* [allergen](https://github.com/stanislas/allergen) - 与 Antigen 一起使用的自定义 ZSH 插件的集合.
* [almostontop](https://github.com/Valiev/almostontop)  - 每次在 shell 中执行新命令之前清除先前的命令输出. 灵感来自 [alwaysontop](https://github.com/swirepe/alwaysontop) `bash` 的插件.
* [alt-and-select](https://github.com/raisty/alt-and-select) - Binds the alt-c (copy), alt-v (paste), alt-x (cut) keyboard shortcut to a commands: copy-region-as-kill, yank, kill-region. Remaps the execute command to Alt-Shift-X.
* [ansible](https://github.com/sparsick/ansible-zsh) - A plugin for [Ansible](https://www.ansible.com/).
* [ansiweather](https://github.com/fcambus/ansiweather) - 终端中的天气，带有 ANSI 颜色和 Unicode 符号.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH script to aid with `git` rebasing.
* [anyframe](https://github.com/mollifier/anyframe) - A peco/percol/fzf wrapper plugin for ZSH.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - 添加用于管理 Apache2 的别名和功能.
* [apparix](https://github.com/micans/apparix) - 带有跳转到书签、子目录选项卡完成、远程列表等的命令行目录书签.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - 添加 MacBook Pro 触控栏支持 [iTerm 2](https://iterm2.com).
* [appup](https://github.com/Cloudstek/zsh-plugin-appup) - Adds `start`, `stop`, `up` and `down` commands when it detects a `docker-compose.yml` or `Vagrantfile` in the current directory (e.g. your application). Just run `up` and get coding!
* [arc](https://github.com/anton-rudeshko/zsh-arc) - 为 Yandex 版本控制系统添加别名.
* [arduino](https://github.com/raghur/zsh-arduino) - Adds scripts to build, upload and monitor arduino sketches from a command line. Requires [`jq`](https://stedolan.github.io/jq/).
* [artisan](https://github.com/jessarcher/zsh-artisan) - Laravel `artisan` plugin for ZSH to help you to run `artisan` from anywhere in the project tree, with tab completion!
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - AsciiDoctor 的插件.
* [asdf-direnv](https://github.com/redxtech/zsh-asdf-direnv) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf) 和 [direnv](https://github.com/asdf-community/asdf-direnv).
* [asdf](https://github.com/kiurchv/asdf.plugin.zsh) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf)，可扩展的版本管理器，支持 Ruby、Node.js、Elixir、Erlang 等.
* [assume-role](https://github.com/weizard/assume-role) - ZSH plugin to allow you to assume AWS IAM roles easily. Includes completions.
* [async](https://github.com/mafredri/zsh-async)  - 在 ZSH 中运行异步任务的库，无需任何外部工具. 允许您运行多个异步作业，强制执行唯一作业（同一作业的多个实例不会运行），刷新所有当前正在运行的作业并创建多个工作人员（每个工作人员都有自己的工作）.
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - 基于 [Sublime](https://github.com/valentinocossar/sublime) plugin, lets you launch a file or folder in [Atom](https://atom.io) from [iTerm 2](https://iterm2.com).
* [atuin](https://github.com/ellie/atuin)  - 用 SQLite 数据库替换你现有的 shell 历史，并为你的命令记录额外的上下文. 此外，它还通过 Atuin 服务器在机器之间提供可选且完全加密的历史同步.
* [aur-install](https://github.com/redxtech/zsh-aur-install) - Small plugin to install packages from the AUR.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) - Automatically list directories with `colorls`.
* [auto-fortune-cowsay](https://github.com/babasbot/auto-fortune-cowsay-zsh) - Prints out an ASCII picture of a cow saying a random epigram on every zsh start.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
* [auto-ls (commanda-panda)](https://github.com/commanda-panda/zsh-auto-ls) - 自动运行 `ls` 或 `color-ls` 如果在 `cd` 上可用.
* [auto-ls (desyncr)](https://github.com/desyncr/auto-ls) - Automatically `ls` when cding to a new directory.
* [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) - 长时间运行的任务完成时自动发出通知.
* [auto-nvm](https://github.com/manlao/zsh-auto-nvm) - Automatically switches to the node version specified in a given directory.
* [autocomplete](https://github.com/marlonrichert/zsh-autocomplete) - 在您键入时自动列出完成，并提供直观的键绑定来选择和插入它们.
* [autodotenv](https://github.com/nocttuam/autodotenv) - Will prompt you to load variables when you `cd` into a directory containing a `.env` file.
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) - Extended version of the [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) plugin.
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a `.env` file, it will automatically be executed when you `cd` into it.
* [autojump](https://github.com/wting/autojump) - A `cd` command that learns - easily navigate directories from the command line. Install autojump-zsh for best results.
* [autopair](https://github.com/hlissner/zsh-autopair)  - 用于自动关闭、删除和跳过匹配分隔符的 ZSH 插件. 仅在 ZSH 5.0.2 或更高版本上测试.
* [autoquoter](https://github.com/ianthehenry/zsh-autoquoter) - A `zle` widget ("zsh plugin") that will automatically put quotes around arguments to certain commands.
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)-like fast/unobtrusive autosuggestions for ZSH.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) - ZSH plugin to automatically switch python virtualenvs and pipenvs when traversing directories. Automatically detects pipenv and poetry projects.
* [autoupdate-antibody](https://github.com/spikespaz/autoupdate-antibody-zsh) - 一个叉子 [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) 为了 [Antibody](https://getantibody.github.io) plugin manager, with the added ability to cooperate with static loading.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) - Antigen doesn't do automatic updates like oh-my-zsh. This plugin adds auto updating for antigen, both of antigen and the bundles loaded in your configuration.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - oh-my-zsh 不会自动更新非核心插件，这会将插件自动更新添加到 oh-my-zsh.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - AWS CLI MFA plugin based on sweharris' [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa). Supports specifying mfa_device in profile.
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - AWS MFA 插件.
* [aws-plugin](https://github.com/pookey/zsh-aws-plugin)  - 为 `aws` 命令添加辅助函数. 包括 mfa 和假设角色助手.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - 使用 `aws-upload` 提高您的工作效率.
* [aws-vault (blimmer)](https://github.com/blimmer/zsh-aws-vault) - 插件 [aws-vault](https://github.com/99designs/aws-vault) . 包括制表符补全.
* [aws-vault (reegnz)](https://github.com/reegnz/aws-vault-zsh-plugin) - 使其更易于使用 [aws-vault](https://github.com/99designs/aws-vault) 在你的环境中.
* [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) - Provides completion support for version 2 of the [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) 以及一些用于管理 AWS 配置文件并将其显示在提示中的实用程序.
* [aws](https://github.com/apachler/zsh-aws) - 从原始的 oh-my-zsh 分叉 [aws](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aws) . 包括 `awscli` 的补全和一些用于管理 AWS 配置文件并在提示中显示它们的实用程序.
* [awsume](https://github.com/Sordie/AWSume) - Plugin that enables showing the current [awsume](https://github.com/trek10inc/awsume) 轮廓.
* [azcli](https://github.com/dmakeienko/azcli) - Helper for using the azure cli tools.
* [azure-keyvault](https://github.com/milespossing/Azure-Keyvault-Zsh) - Makes using azure keyvaults less verbose from the cli.
* [azure-subscription](https://github.com/dmakeienko/azure-subscription-prompt) - 显示有关 Azure 当前订阅和租户的信息.
* [background](https://github.com/zpm-zsh/background) - ZSH plugin which executes functions in the background.
* [base16](https://github.com/chriskempson/base16-shell)  - 添加脚本以允许您更改 shell 的默认 ANSI 颜色，但最重要的是，更改 shell 的 256 色空间的 17 到 21 色（如果您的终端支持）. 这个脚本可以在为应用程序提供额外的 base16 颜色的同时，尊重 shell 的原始明亮颜色（例如，亮绿色仍然是绿色等等） [Vim](https://www.vim.org).
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts) - Print random baseball related "fun facts" in your shell. Depends on `fortune` and `cowsay` being installed.
* [basex](https://github.com/dirkk/zsh-basex) - Adds several [BaseX](http://basex.org/) aliases for simplified usage.
* [bash-quote](https://github.com/jtprog/bash-quote) - 从 Bash.im 获取随机报价.
* [bash](https://github.com/chrissicool/zsh-bash)  - 使 ZSH 更兼容 Bash. 它重新定义了 source 命令，使其更像 `bash`. 它还启用了 `bash` 完成.
* [battery_state](https://github.com/Jactry/zsh_battery_state) - 在右侧提示中显示电池状态.
* [bd](https://github.com/Tarrasch/zsh-bd) - 跳回特定目录，无需执行 `cd ../../..`.
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) - Remap ZSH `vi`-mode for French [bépo keyboard](http://bepo.fr/wiki/Accueil).
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) - 为“brew”添加更多命令别名
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - 添加帮助脚本以允许您创建 bitbucket PR 或在当前分支中打开目录.
* [bitwarden](https://github.com/Game4Move78/zsh-bitwarden) - 添加管理功能 [bitwarden](https://bitwarden.com/) sessions.
* [blackbox](https://github.com/StackExchange/blackbox) - [Stack Exchange](https://stackexchange.com)的工具包，用于将密钥/凭证安全地存储在 `git` 存储库中.
* [bofh](https://github.com/fundor333/bofh) - Adds functions to display random bofh fortunes.
* [bol](https://github.com/ikhurramraza/bol) - Prints a random quote when you open a terminal window.
* [boss-docker](https://github.com/bossjones/boss-docker-zsh-plugin) - 在 OSX 上管理 `docker`.
* [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) - 为 `git` 添加了一些方便的别名.
* [branch-manager](https://github.com/elstgav/branch-manager) - A plugin for managing `git` branches.
* [brew (rhuang2014)](https://github.com/rhuang2014/brew) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
* [brew (wolffaxn)](https://github.com/wolffaxn/brew-zsh-plugin) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - 一个插件，可让您从命令行在浏览器中打开任何提交.
* [bruse](https://github.com/aubreypwd/zsh-plugin-bruse) - Makes it easy to `brew link` different versions of packages.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - 在命令行中切换 optirun 的插件.
* [c](https://github.com/sebastiangraz/c) - 添加一些 `git` 快捷方式.
* [calc](https://github.com/arzzen/calc.plugin.zsh) - A calculator for ZSH.
* [calibre-zaw-source](https://github.com/junkblocker/calibre-zaw-source) - [Calibre - E-book management](https://calibre-ebook.com/) 来源 [zaw](https://github.com/zsh-users/zaw)
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - Add [Can I Use...](https://caniuse.com) support to ZSH.
* [careful_rm](https://github.com/MikeDacre/careful_rm) - `rm` 的包装器，添加了垃圾/回收和有用的警告.
* [case](https://github.com/rtuin/zsh-case) - A ZSH plugin that adds two aliases `tolower` and `toupper` to switch output case.
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - 一个 ZSH 插件到 `cd` 到 `git` 存储库根目录.
* [cd-ls](https://github.com/zshzoo/cd-ls) - 在`cd`之后自动`ls`.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) - 当 `cd`-ing 进入指定目录时显示提醒.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - 一个 ZSH 插件，用于 `cd` 到当前存储库签出的根目录.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - 当你不小心 `cd` 到服务器时，`ssh` 到服务器.
* [cdbk](https://github.com/MikeDacre/cdbk) - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want.
* [cdc](https://github.com/evanthegrayt/cdc)  - 更容易将目录更改为用户定义的目录列表的子目录. 包括 tab-completion、会话历史和 `pushd`、`popd` 和 `dirs` 等价物.
* [cdr](https://github.com/willghatch/zsh-cdr) - 为 ZSH 轻松设置 cdr.
* [change-case](https://github.com/mtxr/zsh-change-case) - Plugin for fast swap between upper and lower case in your command line. :sunglasses:
* [cheatsheet](https://github.com/0b10/cheatsheet) - Plugin to easily view, create, and edit cheatsheets.
* [check-deps](https://github.com/zpm-zsh/check-deps) - Helper for ZSH plugins that allows them to show how to install any missing dependencies. Works on Debian (and derivatives like Ubuntu), Arch and its derivatives, Nodejs and ZSH plugins if you are using the [zpm](https://github.com/zpm-zsh/zpm) framework.
* [chgo](https://github.com/sbfaulkner/chgo-plugin-zsh) - 修改了 chruby 的克隆，以便在多个 Go 版本之间切换.
* [clean-project](https://github.com/wwilsman/zsh-clean-project) - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories.
* [clipboard](https://github.com/zpm-zsh/clipboard) - Adds a cross-platform helper function to access the system clipboard. Works on macOS, X11 (and Wayland) and Cygwin.
* [cmd-status](https://github.com/BlaineEXE/zsh-cmd-status) - 报告命令的状态，包括返回码和持续时间.
* [cmdtime](https://github.com/tom-auger/cmdtime) - Displays the duration of a command to the terminal forked from the [timer](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) plugin.
* [code-review](https://github.com/xorkevin/code-review-zsh) - 在 `git merge-base target_branch base_branch` 和 `target_branch` 上启动 `git difftool`.
* [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - 计算按键并记录统计信息 [Code::Stats](https://codestats.net/).
* [codex](https://github.com/tom-doerr/zsh_codex) - Enables you to use OpenAI's powerful Codex AI in the command line.
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - Forked from [ohmyzsh/ohmyzsh/plugins/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh). Colorizes `man` output.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - 为“man”页面着色.
* [colorize](https://github.com/zpm-zsh/colorize) - Colorize the output of various programs.
* [colorls](https://github.com/Kallahan23/zsh-colorls) - Defines a few helpful shortcuts to some colorls functions.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors)  - 使 CLI 中的文本更容易着色.  `red foo` 可以正常工作.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - Enhanced colors for ZSH.
* [command-execution-timer](https://github.com/olets/command-execution-timer) - 显示交互式 shell 命令执行所需的时间.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) - A mirror of the oh-my-zsh command-not-found plugin so you don't have to include all of oh-my-zsh.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - 记录复杂的命令并对其进行评论.
* [command-time](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in ZSH and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Similar to `REPORTTIME` builtin, but only outputs when user + system time >= `REPORTTIME`.
* [compe](https://github.com/tamago324/compe-zsh) - Add completion for [nvim-compe](https://github.com/hrsh7th/nvim-compe).
* [completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script.
* [completion-zstyles](https://github.com/zshzoo/completion-zstyles) - Zstyle settings for ZSH completions based on Prezto's.
* [copier](https://github.com/zshzoo/copier) - 来自 oh-my-zsh 的独立剪贴板实用程序.
* [copy-pasta](https://github.com/ChrisPenner/copy-pasta) - 在终端中复制和粘贴文件，就像在 GUI 中一样.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - 一个 ZSH 插件，用于通过 `ssh` 将你的 shell 配置复制到另一台机器.
* [crash](https://github.com/molovo/crash) - Adds proper error handling, exceptions and try/catch for ZSH.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - 用于 Wordpress 的 Crayon 插件的 ZSH 语法突出显示.
* [cros-auto-notify](https://github.com/D3STY/cros-auto-notify-zsh)  - 长时间运行的任务完成时自动发出通知. 适用于 macOS 和 linux（如果安装了 `hterm-notify`）.
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - 添加一个 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) segment with the current bitcoin price.
* [crystal](https://github.com/veelenga/crystal-zsh) - A plugin for [Crystal](https://github.com/crystal-lang/crystal).
* [czhttpd](https://github.com/jsks/czhttpd) - 一个用 99.9% 纯 ZSH 编写的简单 http 服务器.
* [declare-zsh](https://github.com/z-shell/declare-zsh) - A parser for zinit commands in `.zshrc`. It allows to perform the following actions on `.zshrc` from the command-line - enable and disable plugins add or remove snippets.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - Collection of useful and fun commands to improve workflow and quality of life.
* [deer](https://github.com/Vifon/deer) - A file navigator for ZSH heavily inspired by [ranger](https://ranger.github.io/).
* [defer](https://github.com/romkatv/zsh-defer)  - 推迟执行 `zsh` 命令，直到 `zsh` 无事可做并等待用户输入. 其预期目的是分阶段启动“zsh”. 它的工作原理类似于 Turbo 模式 [zinit](https://github.com/zdharma-continuum/zinit).
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools)  - 用于安装 chromium depot_tools 的简单 oh-my-zsh 插件. 安装此插件将自动将所有 chromium depot_tools 放入您的路径中.
* [dev](https://github.com/sbfaulkner/dev-plugin-zsh) - Provides a lightweight version of Shopify's internal dev tool
* [diff-so-fancy](https://github.com/z-shell/zsh-diff-so-fancy) - 安装 [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) 并使其能够在 ZSH 中使用.
* [diractions](https://github.com/AdrieanKhisbe/diractions) - Allow you to map a short logical/mnemonic name to directories to quickly access them, or perform actions in them.
* [dircolors-solarized (joel-porquet)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors 插件，带有深色或浅色终端背景选项.
* [dircolors-solarized (pinelibg)](https://github.com/pinelibg/dircolors-solarized-zsh) - 启用 [Solarized Color Theme for GNU ls](https://github.com/seebi/dircolors-solarized).
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - 循环浏览目录堆栈.
* [directory-history](https://github.com/tymm/zsh-directory-history) - A per directory history for ZSH which implements forward/backward navigation as well as substring search in a directory sensitive manner.
* [direnv](https://github.com/ptavares/zsh-direnv) - 用于安装和加载的插件 [direnv](https://github.com/direnv/direnv.git) . 灵感来自 [zsh-pyenv](https://github.com/mattberther/zsh-pyenv).
* [dirrc](https://github.com/gmatheu/shell-plugins) - 当存在于你 `cd` 进入的目录中时执行 `.dirc`.
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - 用于在单行上显示 dirstack 信息的插件.
* [doas (anatolykopyl)](https://github.com/anatolykopyl/doas-zsh-plugin) - 通过按两次“ESC”，可以轻松地为当前或以前的命令添加“doas”前缀.
* [doas (senderman)](https://github.com/Senderman/doas-zsh-plugin) - 通过按两次“ESC”，可以轻松地为当前或以前的命令添加“doas”前缀.
* [docker-aliases](https://github.com/webyneter/docker-aliases) Docker aliases for everyday use.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) Show docker container status in your prompt.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - docker 帮助脚本的集合.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) - A docker-machine plugin for ZSH.
* [docker-run](https://github.com/rawkode/zsh-docker-run) - 回到“自然”运行你的命令，我们将处理容器.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
* [dotbare](https://github.com/kazhala/dotbare) - Interactive dotfile management with the help of `fzf`.
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - Keep your dotfiles in sync across multiple machines using `git`.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - Automagically switch to a python virtual environment located (that you previously have created with virtualenv program) in a directory named `.pyvenv` when you `cd` into a directory.
* [dropbox](https://github.com/zpm-zsh/dropbox) - ZSH 的 Dropbox 插件，提供 `dropbox-cli` 和 `dropbox-uploader` 命令.
* [drupal](https://github.com/yhaefliger/zsh-drupal) - Adds aliases for common tasks and also tab-completion for `drush`. Inspired by [Artisan](https://github.com/jessarcher/zsh-artisan).
* [dune-quotes](https://github.com/brokendisk/dune-quotes) - 随机沙丘报价生成器插件.
* [duration](https://github.com/rtakasuke/zsh-duration) - Displays command duration if it exceeds a user-settable run time.
* [dwim](https://github.com/oknowton/zsh-dwim) - Attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
* [easy-motion](https://github.com/IngoHeimbach/zsh-easy-motion) - 一个港口 [vim-easymotion](https://github.com/easymotion/vim-easymotion) for ZSH.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - List EC2 instances and `ssh` login to the instances easily.
* [editing-workbench](https://github.com/commiyou/zsh-editing-workbench) - 添加理智、复杂的命令行编辑（例如增量历史单词完成）.
* [edward cli](https://github.com/matthieusb/zsh-edward) - Adds smart completions and alises for [edward CLI micro-service launcher](https://github.com/yext/edward).
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - 添加 Elixir、IEX、Mix、Kiex 和 Phoenix 的快捷方式.
* [emacs (cowboyd)](https://github.com/cowboyd/zsh-emacs) - Make Emacs the default for CLI operations like editing git commit messages; set up handy aliases.
* [emacs (flinner)](https://github.com/Flinner/zsh-emacs) - 使用 Emacs 守护进程功能，允许用户快速打开框架，无论它们是通过 ssh 连接在终端中打开的，还是在同一主机上打开的 X 框架.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: Emoji completion on the command line.
* [emoji-fzf](https://github.com/pschmitt/emoji-fzf.zsh) - 优秀的可配置 ZSH 插件 [emoji-fzf](https://github.com/noahp/emoji-fzf) . 它深受启发 [emoji-cli](https://github.com/b4b4r07/emoji-cli).
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) - Adds numerous ascii art emojis to your environment in convenient variables.
* [enhancd](https://github.com/b4b4r07/enhancd) - 一个简单的工具，通过记住用户访问的所有目录并将其用于路径名解析来提供增强的“cd”命令.
* [envrc](https://github.com/fabiogibson/envrc-zsh-plugin) - Automatically loads and unloads environment variables if a `.envrc` file is found in a directory.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - 双击“`”时快速插入转义的反引号.
* [evalcache](https://github.com/mroth/evalcache) - 缓存二进制初始化命令的输出，以帮助减少 shell 启动时间.
* [evil-registers](https://github.com/zsh-vi-more/evil-registers) - 扩展 ZLE vi 命令以远程访问 vim 和 nvim 编辑器的命名寄存器，以及系统选择和剪贴板.
* [exa (DarrinTisdale)](https://github.com/DarrinTisdale/zsh-aliases-exa) - 启用多个别名扩展 [exa](https://the.exa.website), the modern replacement for `ls`.
* [exa (hermitmaster)](https://github.com/hermitmaster/zsh-exa-plugin) - 添加一些别名 [exa](https://the.exa.website), the modern replacement for `ls`.
* [exa (mohamedelashri)](https://github.com/MohamedElashri/exa-zsh) - Adds aliases for [exa](https://the.exa.website), a modern replacement for `ls`.
* [exa (ptavares)](https://github.com/ptavares/zsh-exa) - Installs and loads [exa](https://github.com/ogham/exa.git).
* [exa (ritchies)](https://github.com/RitchieS/zsh-exa/) - Adds aliases to make using [exa](https://github.com/ogham/exa.git) easier.
* [exa-ls](https://github.com/birdhackor/zsh-exa-ls-plugin) - Adds aliases so that you can use [exa](https://the.exa.website) 作为 `ls` 和 `tree` 的替代品.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/).
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - Expand specific aliases with space.
* [expand](https://github.com/MenkeTechnologies/zsh-expand) - 使用空格键扩展常规别名、全局别名、不正确的拼写和短语、glob、历史扩展和 $parameters.
* [expander](https://github.com/ianthehenry/zsh-expander) - 一个“zle”小部件，允许您编写自定义扩展器并选择它们 [fzf](https://github.com/junegunn/fzf).
* [explain-shell](https://github.com/gmatheu/shell-plugins) - 打开命令 [explainshell.com](https://explainshell.com).
* [extend-history](https://github.com/xav-b/zsh-extend-history) - Extends command history by adding exit code for each command in the history.
* [f-shortcuts](https://github.com/zpm-zsh/f-shortcuts) - Makes a shortcuts toolbar using F1 to F12 keys.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) 所以其他框架的用户不必导入所有的 oh-my-zsh.
* [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips)  - 帮助记住您定义和忘记的别名. 移植自 [djui/alias-tips](https://github.com/djui/alias-tips).
* [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting) - 优化和改进了“zsh-users/zsh-syntax-highlighting”——更好的响应时间，可切换的高亮主题.
* [fav](https://github.com/ddnexus/fav) - ZSH/[fzf](https://github.com/junegunn/fzf) plugin that makes it really easy to add and recall named favorites of your important directories.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - 快速跳转到您最喜欢的目录.
* [figures](https://github.com/zpm-zsh/figures) - Unicode symbols for ZSH.
* [firebase (Seqi)](https://github.com/Seqi/firebase-zsh) - Display the current working project or project alias when in a Firebase project directory or subdirectory.
* [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) - Add an indicator in the prompt that you're in a directory with a `firebase.json` file (aka "firebase project").
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - 使 Apple 键盘的数字键能够在 ZSH 中被识别.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - This plugin makes the `flow` command available inside every subdirectory of the TYPO3 Flow distribution.
* [fnm](https://github.com/dominik-schwabe/zsh-fnm) - Installs and loads the [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) 如果它丢失了.
* [forgit](https://github.com/wfxr/forgit) - `git` 的实用工具，它利用了模糊查找器 [fzf](https://github.com/junegunn/fzf).
* [functional](https://github.com/Tarrasch/zsh-functional) - ZSH 高阶函数.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line.
* [fuzzy-wd](https://github.com/spodin/zsh-fuzzy-wd) - 添加模糊搜索扭曲的目录 [WD](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/wd) plugin.
* [fz](https://github.com/changyuheng/fz) - Seamlessly adds fuzzy search to [z](https://github.com/rupa/z)的选项卡完成，让您轻松地在历史记录中的目录之间跳转.
* [fzf (unixorn)](https://github.com/unixorn/fzf-zsh-plugin/tree/master) - 启用 [fzf](https://github.com/junegunn/fzf) history and file searches.
* [fzf-fasd](https://github.com/wookayin/fzf-fasd) - Integrates [fzf](https://github.com/junegunn/fzf) 和 [fasd](https://github.com/clvv/fasd) --- 使用 fzf 的模糊搜索完成 `z` 的制表符！
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - Plugin to have a cool search keybinding with [fzf](https://github.com/junegunn/fzf) and (optionally) [bat](https://github.com/sharkdp/bat) . 在子目录的本地树中搜索文件.
* [fzf-history-search](https://github.com/joshskidmore/zsh-fzf-history-search) - 将 `Ctrl+R` 替换为 [fzf](https://github.com/junegunn/fzf)- 驱动的历史搜索，包括日期/时间.
* [fzf-it](https://github.com/micakce/fzf-it) - 使用 FZF 功能使任何命令交互式包装.
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) - 使用模糊查找器在 `bash` 和 `zsh` 中创建、导航和删除书签的小脚本 [fzf](https://github.com/junegunn/fzf).
* [fzf-pass](https://github.com/smeagol74/zsh-fzf-pass) - Better h和ling of passwords using [fzf](https://github.com/junegunn/fzf) 和 [pass](https://www.passwordstore.org/).
* [fzf-prezto](https://github.com/lildude/fzf-prezto) - Prezto plugin that finds where [fzf](https://github.com/junegunn/fzf) 已安装并启用其自动完成和键绑定. 这个插件作为 Prezto `zstyle` 配置选项工作.
* [fzf-tab](https://github.com/Aloxaf/fzf-tab) - Replace ZSH's default completion selection menu with [fzf](https://github.com/junegunn/fzf).
* [fzf-utils](https://github.com/redxtech/zsh-fzf-utils) - 提供杀死进程并在路径中查找的功能 [fzf](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - 添加一些 ZLE 小部件 [fzf](https://github.com/junegunn/fzf).
* [fzf-z](https://github.com/andrewferrier/fzf-z) - 将 *z* 插件和 *fzf* 结合在一起，让您可以在命令行的任何位置轻松浏览最近使用的目录.
* [fzy](https://github.com/aperezdc/zsh-fzy) - Plugin that uses [fzy](https://github.com/jhawthorn/fzy) 对于某些模糊匹配操作.
* [gcloud-project](https://github.com/avivl/gcloud-project) - 轻松选择 Google Cloud 项目.
* [gdbm](https://github.com/zdharma-continuum/zgdbm) - 添加 GDBM 作为插件.
* [geeknote](https://github.com/s7anley/zsh-geeknote) - [Geeknote](https://geeknote.me) plugin for ZSH.
* [gentoo](https://github.com/MattiaG-afk/gentoo-ohmyzsh) - 添加一些别名和函数以与 Gentoo Linux 一起使用.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) datetime plugin. Shows datetime (`date` unix command) in your prompt.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) 提醒您补水的插件.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) 显示当前文件夹的 npm 包版本的插件.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) 当 `.rs` 或 `Cargo.toml` 存在时显示当前文件夹的 Rust 版本的插件.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - 用于快速下载 jQuery 库的插件 [https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com](https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com).
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - Lets you use [zeus](https://github.com/burke/zeus) with normal rails commands.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - Manage Go installations with gimme.
* [git-acp](https://github.com/MenkeTechnologies/zsh-git-acp) - Take the current command line as the commit message and then run git pull, add, commit and push with one keystroke.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) - Easily add the upstream remote to your `git` fork.
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) 所以其他框架的用户不必导入所有的 oh-my-zsh.
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - 为常用的 `git` 命令组合创建许多有用的别名.
* [git-branches](https://github.com/Schroefdop/git-branches) - Makes a menu of `git` branches you can switch to without having to type long branch names.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - 增强 `git` 完成以包括在远程完成中（例如来自 `git clone`）剪贴板中的任何 URL.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - 额外的 `git` 辅助脚本打包为插件.
* [git-flow-avh](https://github.com/nekofar/zsh-git-flow-avh) - 为 `git-flow` 命令添加短别名.
* [git-fuzzy](https://github.com/bigH/git-fuzzy) - A CLI interface to `git` that relies heavily on [`fzf`](https://github.com/junegunn/fzf).
* [git-ignore](https://github.com/laggardkernel/git-ignore)  - 从 gitignore.io **offline** 生成 `.gitignore` 文件.  `fzf`，完成，预览集成.
* [git-is-clean](https://github.com/aubreypwd/zsh-plugin-git-is-clean) - This function will return true or false depending on if it finds out your repo is dirty or not.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub.
* [git-lfs](https://github.com/nekofar/zsh-git-lfs) - Adds short aliases for the git-lfs commands.
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - Adds some functions for `git`.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for `git` user.email.
* [git-prune (diazod)](https://github.com/diazod/git-prune) - 允许您删除已合并到本地存储库和/或已合并到远程源存储库的所有分支.
* [git-prune (seinh)](https://github.com/Seinh/git-prune) - 简化删除合并分支的插件.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) - Adds `git-squash-branch` and `git-remove-merged` commands.
* [git-secret](https://github.com/sobolevn/git-secret) - 一个 bash 工具，用于将您的私人数据存储在 `git` 存储库中.
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - Adds extra `git` commands to make some common `git` usages more efficient.
* [git-smart-commends-wrapper](https://github.com/jelek21/omz-git-smart-commands) - 包裹 [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) 使其与 oh-my-zsh 插件系统兼容.
* [git-sync](https://github.com/caarlos0/zsh-git-sync) - 一个 ZSH 插件，用于同步 `git` 存储库并清理它们.
* [git-worktree](https://github.com/alexiszamanidis/zsh-git-worktree) - Wraps some `git worktree` operations for simplicity and productivity. Includes `fzf` tooling.
* [git](https://github.com/davidde/git) - Replacement for the stock oh-my-zsh git plugin. Provides quite a few useful aliases and functions. The motivation to replace the default plugin stems from the fact that it comes with some inconsistencies that make a few popular commands rather unintuitive, so this plugin makes the aliases consistent.
* [gitcd (SukkaW)](https://github.com/SukkaW/zsh-gitcd) - Adds command to `git clone` a repository and `cd` into the resulting directory.
* [gitcd (viko16)](https://github.com/viko16/gitcd.plugin.zsh) - Automatically `cd` to a `git` working directory after cloning it.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of oh-my-zsh gitfast plugin.
* [gitgo (grimmbraten)](https://github.com/grimmbraten/gitgo) - Make it easier to switch between `git` branches.
* [gitgo (ltj)](https://github.com/ltj/gitgo) - 从命令行在浏览器中打开 Github/Gitlab 存储库（仅限 macOS）.
* [github](https://github.com/shakir-abdo/zsh-github-plugin) - Fork of the original [github plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/github) 嵌入 [oh-my-zsh](http://ohmyz.sh/).
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - 用于创建 `.gitignore` 文件的插件.
* [gitio](https://github.com/denysdovhan/gitio-zsh) - A ZSH plugin for generating a GitHub short URL using [git.io](https://git.io).
* [gitstatus](https://github.com/Insert-Creative-Name-Here/gitstatus.zsh) -  Makes it easy to show your `git` status in your prompt.
* [gitsync](https://github.com/washtubs/gitsync) - ZSH 插件可改善一个人在多台机器上的同一存储库上开发的工作流程.
* [goenv (CDA0)](https://github.com/CDA0/zsh-goenv/blob/master/zsh-goenv.plugin.zsh) - 用于安装、更新和加载 goenv 的插件.
* [goenv (bbenne10)](https://github.com/bbenne10/goenv) - Manage `$GOPATH` similarly to Python's virtualenvwrapper.
* [going_places](https://github.com/or17191/going_places) - A plugin that helps to use, create and maintain a list of shell locations.
* [golinks](https://github.com/slessans/oh-my-zsh-golinks-plugin) - Launch golinks from your terminal.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - Plugin that tries to do the right thing when it comes to setting up the GPG agent to act as an SSH agent as well on macOS.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) - ZSH plugin to encrypt and decrypt files or directories in place.
* [grep2awk](https://github.com/joepvd/grep2awk) - ZLE widget to transform `grep` command into `awk` command.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - 为 `grunt` 添加自动完成功能.
* [gsh](https://github.com/cjayross/gsh) - Collection of helper functions for `git`
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - 终端插件 [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [gtr](https://github.com/Zocker1999NET/zsh-gtr) - Allows fast tagging of a release in git using the tag name **release-YYYY-MM-DD-HH-MM** and headline **Release YYYY-MM-DD HH:MM**.
* [guish](https://github.com/gcarrarom/oh-my-guish) - Collection of utility functions and aliases.
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - 包装器插件 [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
* [gunstage](https://github.com/LucasLarson/gunstage)  - 至少有八种方法可以在 `git` 存储库中取消暂存文件. 这是一个用于撤消 `git add` 的命令行 shell 插件.
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - ZSH 的 gvm（Go 版本管理器）插件.
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - 为“gvm”（Groovy 环境管理器）提供自动完成功能.
* [hab](https://github.com/alexdesousa/hab) - Automatically loads OS environment variables defined in the file `.envrc` if it's found when changing to a new directory.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - Outputs a hacker quote randomly when you open a terminal.
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - Adds some convenience aliases for hadoop functions.
* [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH 插件 [hanami](http://hanamirb.org) projects.
* [hangul](https://github.com/gomjellie/zsh-hangul) - Auto correct hangul(한글, korean) to english when it was supposed to be typed english. 영어를 타이핑 해야되는데 한글로 타이핑된경우 자동으로 수정합니다.
* [hbt](https://github.com/lzambarda/hbt) - 基于过去命令使用的启发式 ZSH 建议系统.
* [hints](https://github.com/joepvd/zsh-hints) - Display glob and parameter flags and other non completable info right under your editing buffer.
* [hipchat](https://github.com/robertzk/hipchat.zsh) - 从外壳发送 hipchat 消息.
* [hist](https://github.com/marlonrichert/zsh-hist) - Edit your history in ZSH, without ever leaving the command line.
* [histdb](https://github.com/larkery/zsh-histdb) - Stores your history in an SQLite database. Can be integrated with [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions).
* [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer)  - 通过更多交互和多行选择菜单增强历史搜索. 需要nodejs.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter) - Allows you to specify patterns that will automatically exclude commands from being inserted into your permanent history. Particularly useful for preventing secrets being written.
* [history-here](https://github.com/leonjza/history-here) - 绑定 `^G` 以快速切换当前 shell 历史文件位置.
* [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) - 捕获 PageUp 键并使用“对话框”打开带有历史记录的弹出菜单，因此用户可以交互地浏览它并选择历史记录行以返回提示.
* [history-search-multi-word](https://github.com/zdharma-continuum/history-search-multi-word) - A syntax highlighted, multi-word history searcher for ZSH, bound to Ctrl-R, with advanced functions (e.g. bump of history entry to top of history).
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after `zsh-syntax-highlighting`, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md.
* [history-sync](https://github.com/wulfgarpro/history-sync) - 一个 Oh My Zsh 插件，用于使用 `git` 加密的 GPG、Internet 同步 ZSH 历史记录.
* [history](https://github.com/b4b4r07/zsh-history) - Extend history so that it can be queried by SQL.
* [hitokoto](https://github.com/derry96/hitokoto) - Displays a random quote from [hitokoto.cn](https://hitokoto.cn/).
* [homeassistant-cli](https://github.com/frosit/zsh-plugin-homeassistant-cli) - Provides completion and (configuration) helpers for the [Home Assistant Command-line interface (hass-cli)](https://github.com/home-assistant/home-assistant-cli). and allows command line interaction with [Home Assistant](https://home-assistant.io/) instances.
* [homebrew](https://github.com/digitalraven/omz-homebrew) - 插件 [homebrew](https://brew.sh) that supplements the one built into oh-my-zsh and can safely run with it enabled.
* [hooks](https://github.com/willghatch/zsh-hooks) - 添加缺少的钩子 - 用于插件和个人使用.
* [host-switch](https://github.com/LockonS/host-switch) - Make it easier to switch in different `/etc/hosts` files during development.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - 一个简单的插件，用于将 `hub` ci-status 添加到您的 ZSH 主题.
* [hub](https://github.com/soraliu/zsh-hub) - ZSH plugin for forking model.
* [igit](https://github.com/ytakahashi/igit) - Interactive `git` commands using [fzf](https://github.com/junegunn/fzf).
* [ing](https://github.com/rummik/zsh-ing) - Streamlined `ping` output.
* [instant-repl](https://github.com/jandamm/instant-repl.zsh) - 为当前 ZSH 会话中的任何命令激活 REPL.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - Fish-like interactive tab completion for `cd`.
* [iosctl](https://github.com/obayer/iosctl) - Quickly access App, Data, and Log of the running simulator.
* [ipip](https://github.com/SukkaW/zsh-ipip) - 插件 [IPIP](https://en.ipip.net).
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - 在iTerm2中增加了设置标签颜色的功能，可以根据cwd或正在执行的命令自动改变颜色.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - Automatically changes iTerm 2 tab color based on the current working directory.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - 在 MacbookPro TouchBar 中显示 iTerm2 反馈（当前目录、git 分支和状态）.
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - Manage your iTerm 2's color scheme from the command line.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - Set colors and titles of iTerm 2 tabs.
* [iterm2-utilities](https://github.com/decayofmind/zsh-iterm2-utilities) - 帮助下载各种 iTerm2 实用程序，并让您省略整个 iterm2 网站存储库的克隆或依赖可能不同步的其他存储库.
* [iterm2](https://github.com/laggardkernel/zsh-iterm2) - 将 iTerm 的 ZSH 集成脚本打包到 ZSH 插件中，以避免污染您的 $HOME 目录，仅增加 2ms 的时间可以忽略不计.
* [jabba](https://github.com/2m/zsh-jabba) - 添加外壳集成代码和完成 [jabba](https://github.com/shyiko/jabba) Java version manager.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - 添加 `setjdk` 命令，以便您可以在 jdk 的不同版本之间轻松切换.
* [javaVersions](https://github.com/miguefl/javaVersions) - Change between different java versions with a single command.
* [jdk-switch](https://github.com/LockonS/jdk-switch) - A macOS-only plugin for switching between jdk versions.
* [jenkins](https://github.com/tomplex/jenkins-zsh) - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - A ZSH plugin for lazy loading of jEnv.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - 添加命令 [jHipster](https://www.jhipster.tech/).
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRA tickets from the command line.
* [jq (northismirror)](https://github.com/NorthIsMirror/jq-zsh-plugin) - Interactively build [jq](https://stedolan.github.io/jq/) expressions to give you `jq` superpowers.
* [jq (reegnz)](https://github.com/reegnz/jq-zsh-plugin) - Interactively build [jq](https://stedolan.github.io/jq/) 表达式.
* [jvm](https://github.com/mgryszko/jvm) - 允许在 macOS 上选择 JDK.
* [k3d](https://github.com/dwaynebradley/k3d-oh-my-zsh-plugin) - Adds aliases and tab completions for [k3d](https://k3d.io/).
* [k](https://github.com/supercrabtree/k) - 带有 `git` 状态装饰的 ZSH 目录列表.
* [kctl](https://github.com/yzdann/kctl) - 为“kubectl”添加助手别名.
* [kill-node](https://github.com/vmattos/kill-node) - ZSH plugin for murdering `node` process families.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook plugin for oh-my-zsh.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
* [kube-aliases](https://github.com/Dbz/kube-aliases) - 添加函数和别名以使使用 `kubectl` 更加愉快.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - `kubectl` 的 ZSH 插件，添加当前上下文和命名空间.
* [kubecolor (devopstales)](https://github.com/devopstales/kubecolor-zsh) - 为 `kubecolor` 命令添加别名.
* [kubecolor (droctothorpe)](https://github.com/droctothorpe/kubecolor) - 简化和着色`kubectl get events -w`的输出
* [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) - 用于管理 `kubectl` 的 ZSH 插件.
* [kubectx (ptavares)](https://github.com/ptavares/zsh-kubectx) - Installs and loads [kubectx](https://github.com/ahmetb/kubectx).
* [kubectx (unixorn)](https://github.com/unixorn/kubectx-zshplugin) - Automatically installs [kubectx](https://github.com/ahmetb/kubectx) 和`kubens`.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) - Add [kubernetes](https://kubernetes.io) helper functions and aliases.
* [lando (joshuabedford)](https://github.com/JoshuaBedford/lando-zsh) - A collection of alias functions to enable the use of the CLIs within [Lando](https://docs.lando.dev) 无需键入lando 即可访问它们.
* [lando (mannuel)](https://github.com/mannuel/lando-alias-zsh) - 为各种添加别名 [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) 命令.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - Provides an interface to [Laradock](http://laradock.io/)的工作区.
* [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) - 为 Laravel 6 添加别名.
* [laravel-sail](https://github.com/ariaieboy/laravel-sail) - Adds shortcuts for `sail` commands.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - 添加 Laravel 5、5.1、5.2 和 5.3 的快捷方式.
* [laravelx](https://github.com/rsthegeek/oh-my-zsh-laravelx) - 为常见添加一些别名 [Laravel](https://laravel.com/docs) 命令.
* [last-working-dir-tmux](https://github.com/Curly-Mo/last-working-dir-tmux) - 跟踪全局和每个 tmux 会话最后使用的工作目录，并自动跳转到新的 shell.
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) - Broken out copy of the version in [oh-my-zsh](http://ohmyz.sh/) . 跟踪上次使用的工作目录并自动跳转到新的 shell.
* [lazyload](https://github.com/qoomon/zsh-lazyload) - Lazy load commands and speed up start up time of ZSH.
* [learn](https://github.com/MenkeTechnologies/zsh-learn) - Learning collection in MySQL/MariadB to save, query and quiz everything you learn.
* [lesaint-git](https://github.com/lesaint/lesaint-git) - 替换 Oh-My-Zsh 兼容框架的 `git` 插件.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - Maven plugins for oh-my-zsh.
* [liferay](https://github.com/david-gutierrez-mesa/liferay-zsh) - 添加脚本 [liferay](https://github.com/liferay/liferay-portal) development.
* [linkfile](https://github.com/JaumeRF/linkfile-zsh) - Add shortcuts to your favorite directories.
* [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) - 打开终端时输出随机的 Linus Torvalds 咆哮。
* [listbox](https://github.com/gko/listbox) - 外壳的列表框元素.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - 允许搜索 [Sublime Text](https://www.sublimetext.com) projects and opens them in Sublime.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum)  - 在命令行上生成 lorem ipsum 文本. 从中获取数据 [lipsum.com](https://www.lipsum.com).
* [ls](https://github.com/zpm-zsh/ls) - Colorizes the output of `ls`.
* [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack 是一个用于 shell 脚本的日志接口.
* [lux](https://github.com/pndurette/zsh-lux)  - ZSH 插件可通过“lux”命令切换 macOS 和其他项目和应用程序的明暗模式. 高度可定制：可以通过定义变量来配置包含的项目. 高度可扩展：可以通过定义函数来添加项目. 包括 `macos_is_dark` 辅助函数以确定 macOS 暗模式是否处于活动状态以用于主题化.
* [mac-packaging](https://github.com/Temikus/mac-packaging) - A set of common functions used for enterprise Mac packaging with [Munki](https://www.munki.org/munki/).
* [macos (joow)](https://github.com/joow/macos) - A ZSH plugin for macOS.
* [macos (zshzoo)](https://github.com/zshzoo/macos) - 适用于 MacOS 用户的 ZSH 好东西.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) - 使使用 Docker 和 Magento 2 变得容易.在 Magento 2 容器上加速和简化常见命令，如清理缓存、设置升级、编译 di 等等.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - Adds `m2` function to run magento binary, adds tab completions.
* [magic-enter](https://github.com/zshzoo/magic-enter) - 通过将 ZSH 命令绑定到它来使您的输入键变得神奇.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) - 用于模拟 `...&#39;==`../..&#39; 等的 zle 调整.
* [markedit](https://github.com/zakariaGatter/MarkEdit) - 标记文件并使用现有标记的自动完成对其进行编辑.
* [markgate](https://github.com/zakariaGatter/MarkGate) - 允许您标记目录，以便您可以直接跳转到它们.
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - A fork of the oh-my-zsh maven plugin.
* [media-sync](https://github.com/redxtech/zsh-media-sync) - 一个便于在两个 rclone 位置之间复制媒体的插件.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) - 从 oh-my-zsh 中提取，因此您可以在没有 oh-my-zsh 的情况下使用它.
* [mfunc](https://github.com/hlohm/mfunc)  - 允许您动态定义持久性函数，而无需将它们添加到您的配置文件中. 这些功能永久可用，直到您将其删除.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - 一个 ZSH 插件，用于在普通模式和 `vi` 模式之间切换命令行.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - 用于 monorepo 管理的 ZSH 插件.
* [monthrename](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) - Renames month names to numbers in filenames.
* [mouse-status](https://github.com/gryffyn/mouse-status) - 根据状态码更改鼠标颜色，使用 libratbag.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - Metasploit 处理程序插件，用于轻松启动处理程序.
* [mvn-contexts](https://github.com/artemy/zsh-mvn-contexts) - 允许在 Maven 配置之间快速切换.
* [mylocation](https://github.com/fALKENdk/mylocation) - 根据您的 IP 地址显示您当前位置的插件.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - 为 mysql 表添加颜色.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with mysql.
* [n](https://github.com/gretzky/n.zsh) - Auto-switches node versions based on project environment using [n](https://github.com/tj/n).
* [namelink](https://github.com/jthat/zsh-namelink) - 提供一组目录中的文件系统条目（通常是符号链接）到命名目录哈希中的对应项的自动同步映射.
* [navi](https://github.com/icatalina/zsh-navi-plugin/) - 插件 [navi](https://github.com/denisidoro/navi).
* [navigation-tools](https://github.com/zdharma-continuum/zsh-navigation-tools) - 添加 `htop`-like kill、目录书签浏览器、多词增量历史搜索器等.
* [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) -  Generates file from template.
* [newvwp](https://github.com/aubreypwd/zsh-plugin-newvwp) - 使用 Valet 启动一个新的 WordPress 网站.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - 将退出状态代码映射到人类可读的字符串.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) - Plugin that lets you use ZSH as the default shell in a `nix-shell` environment.
* [nnvm](https://github.com/torifat/nnvm)  - 基于 `.nvmrc` 自动切换节点版本. 需要 [n](https://github.com/tj/n).
* [node-env-installer](https://github.com/shiro-saber/node-env-installer) - 使用 `nvm` 为当前项目安装新版本和模块.
* [node-path](https://github.com/andyrichardson/zsh-node-path) - 自动将当前目录的“npm bin”添加到路径中.
* [node](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty's nodejs plugin for ZSH with caching of `nvm` completions and autoloading of `nvm` if present.
* [nodenv (c-uo)](https://github.com/C-uo/zsh-nodenv) - Looks for nodenv in your working directory and loads it when found.
* [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) - Auto-load `nodenv` and its completions into the shell.
* [nodenv (mattberther)](https://github.com/mattberther/zsh-nodenv)  - 安装、更新和加载“nodeenv”. 灵感来自 zsh-rbenv.
* [nohup](https://github.com/micrenda/zsh-nohup) - 按 `Ctrl-H` 将`nohup` 添加到当前命令.
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS users know the pain of trying to figure out what command actually flushes the DNS cache on their version of macOS, and this plugin makes that annoyance go away.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - 灵感来自 [terminal_velocity](https://www.seanh.cc/terminal_velocity/), it provides a fast interface to create and access a set of [Markdown](https://en.wikipedia.org/wiki/Markdown) 目录中的文本文件.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - 在 ZSH 中提供快速的笔记编辑体验.
* [notify (luismayta)](https://github.com/luismayta/zsh-notify) - 自动安装依赖项和 r2d2 声音的 ZSH 通知.
* [notify (marzocchi)](https://github.com/marzocchi/zsh-notify) - A plugin for ZSH (on macOS and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
* [npm (igoradamenko)](https://github.com/igoradamenko/npm.plugin.zsh) - Add `npm` aliases & command completion. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
* [npm (trystan2k)](https://github.com/trystan2k/zsh-npm-plugin)  - 添加 `npm` 别名. 基于 Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
* [npm (zfben)](https://github.com/zfben/zsh-npm)  - 使用 `n` 作为带有 `noglob` 前缀等的 `npm` 别名. 基于 Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
* [npms](https://github.com/torifat/npms)  - 由 `fzf` 提供支持的实用程序，用于交互式使用 npm 脚本. 需要 [fzf](https://github.com/junegunn/fzf) 和 [jq](https://stedolan.github.io/jq/).
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - Calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling `nvm` which node to use.
* [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy)  - 用于延迟加载 oh-my-zsh 的 **nvm** 插件的插件. 它支持为多个二进制/入口点延迟加载 `nvm`，默认值为 `nvm`、`node` 和 `npm`.
* [nvm](https://github.com/lukechilds/zsh-nvm) - ZSH plugin for installing, updating and loading `nvm`.
* [oath](https://github.com/alexdesousa/oath) - Manages 2FA authentication 6 digit tokens. It was highly inspired by this article about [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
* [oclif completion generator](https://github.com/MunifTanjim/oclif-plugin-completion) - Generates shell completions for commands lacking them.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - Turn your terminal into the matrix.
* [omz-themes-standalone](https://github.com/zshzoo/omz-themes-standalone) - Gives you the [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) themes without requiring everything else that comes with oh-my-zsh
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) - 在 Jetbrains 中打开/创建项目.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) - 从命令行打开拉取请求的 ZSH 插件.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - Add a few shortcuts to common openshift origin (oc) actions.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` 别名.
* [operator](https://github.com/nivv/operator-theme) - 干净简单的主题，最适合搭配 [Menlo for Powerline](https://github.com/abertsch/Menlo-for-Powerline).
* [opp](https://github.com/hchbaw/opp.zsh) - 用于 ZSH 的 Vim 的 text-objects-ish.
* [opt-path](https://github.com/jreese/zsh-opt-path) - 自动将 `~/opt` 子路径添加到您的 `$PATH`.
* [osx-autoproxy](https://github.com/SukkaW/zsh-osx-autoproxy) - 根据 macOS 的系统偏好配置代理环境变量.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - 此插件添加了一些命令，用于在 macOS 安装上维护各种服务器程序.
* [osx](https://github.com/mwilliammyers/plugin-osx) - Add some common macOS related aliases and functions.
* [p10k-promptconfig](https://github.com/doctormemes/p10k-promptconfig) - adds the ability to easily switch between Powerlevel10k prompt theme config files by defining the `P10K_PROMPT` variable in your `.zshrc` file.
* [paci](https://github.com/iloginow/zsh-paci) - archlinux 包管理器插件.
* [package-any-node](https://github.com/zdharma-continuum/zsh-package-any-node) - 在插件目录中轻松安装任何节点模块，通过由自动创建的垫片（即：转发器脚本）公开其二进制文件 [Bin-Gem-Node](https://github.com/zdharma-continuum/z-a-bin-gem-node) annex.
* [packer](https://github.com/BreakingPitt/zsh-packer) - Adds aliases and auto-completes for Hashicorp [packer](https://www.packer.io/).
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) - Background notifications for long running commands. Supports Elementary OS Freya.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) - 防止密码进入您的命令行历史记录.
* [path-ethic](https://github.com/sha1n/path-ethic)  - 帮助快速轻松地管理您的“$PATH”. 不会触及现有的 `.zshrc`、`.zprofile`，而是添加到现有环境之上.
* [pctl](https://github.com/ytet5uy4/pctl) - 切换环境变量以进行代理.
* [peco-history](https://github.com/jimeh/zsh-peco-history) - 按 ctrl+R 时使用 Peco 搜索 shell 历史记录.
* [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) - 懒惰渗透测试仪的别名和功能.
* [per-directory-history](https://github.com/jimhester/per-directory-history) - Per directory history for ZSH, as well as global history, and the ability to toggle between them with `^G`.
* [percol](https://github.com/robturtle/percol.plugin.zsh) - Interactively and incrementally search history/resume background jobs using [percol](https://github.com/mooz/percol).
* [perlbrew](https://github.com/tfiala/zsh-perlbrew/) - 安装 [perlbrew](https://perlbrew.pl/) if not already installed and initializes it for your shell.
* [pew](https://github.com/shosca/zsh-pew) - 使用设置和管理 Python virtualenvs [pew](https://github.com/berdario/pew)，在您移动目录时自动切换 virtualenvs.
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) - 添加实用功能以使用 [PostgreSQL](https://www.postgresql.org/).
* [ph-marks](https://github.com/lainiwa/ph-marks) - Bookmark pornhub videos from your terminal.
* [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) - 使用 php 版本之间自动切换 [php-version](https://github.com/wilmoore/php-version) 如果目录中存在 rc 文件.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - 插件 [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) - Auto-load [phpenv](https://github.com/sptndc/phpenv) and its completions.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - 插件 [PHPUnit](https://phpunit.de/).
* [pip-app](https://github.com/sharat87/pip-app) - 可以轻松地将 python 应用程序安装到不同的 Python virtualenvs 中，这样它们就不会与系统上的任何其他 python 要求冲突.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) - Automatic [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a pipenv project.
* [pipx](https://github.com/thuandt/zsh-pipx) - 自动完成 [pipx](https://github.com/pypa/pipx).
* [pkenv](https://github.com/ptavares/zsh-pkenv) - Installs and loads [pkenv](https://github.com/iamhsa/pkenv.git)
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - 添加 ibtool 快捷方式以生成本地化的 XIB 文件.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Plugin for Visual Studio Code, a text editor for macOS, Windows, and Linux.
* [plugin](https://github.com/darrenbutcher/plugin)  - 从样板模板创建自定义 oh-my-zsh 插件. 非常以 oh-my-zsh 为中心，生成的插件需要编辑才能与其他框架一起使用.
* [pnpm](https://github.com/ntnyq/omz-plugin-pnpm) - 为常见的 Pnpm 命令添加有用的别名.
* [poetry (darvid)](https://github.com/darvid/zsh-poetry) - 自动激活和停用 [Poetry](https://poetry.eustace.io/)- 创建了 python virtualenvs.
* [poetry (sudosabin)](https://github.com/sudosubin/zsh-poetry) - Enables poetry `$PATH` and autocompletions.
* [posh-git-bash](https://github.com/lyze/posh-git-sh) - Adds `git` status in your prompt.
* [ppsmon](https://github.com/mzpqnxow/ppsmon)  - 读取 `/sys/class/net/$interface/` 以跟踪数据包传输速率. 它将当前速率存储到 RAM 支持的文件系统中的文件中，在该文件系统中可以轻松访问它以在 shell 提示中显示. 由于使用了 `/sys`，因此仅适用于 Linux.
* [pr-cwd](https://github.com/zpm-zsh/pr-cwd)  - 使用当前工作目录创建一个全局变量. 插件与集成 [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
* [pr-eol](https://github.com/zpm-zsh/pr-eol) - Displays an EOL symbol which can be embedded in the prompt.
* [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) - 添加一个变量，您可以使用它来显示上次命令运行的执行时间.
* [pr-git](https://github.com/zpm-zsh/pr-git) - Creates a global variable with `git` status information that can be displayed in prompts.
* [pr-is-root](https://github.com/zpm-zsh/pr-is-root) - 设置一个环境变量，您可以在以 root 身份运行时在自定义提示中使用.
* [pr-jobs](https://github.com/zpm-zsh/pr-jobs) - 创建一个环境变量，可用于在自定义提示中显示后台作业信息.
* [pr-node](https://github.com/zpm-zsh/pr-node) - Sets an environment variable which can be used to display nodeJS information in a custom prompt.
* [pr-return](https://github.com/zpm-zsh/pr-return) - ZSH 插件，显示最后一次命令运行的退出状态.
* [presenter-mode](https://github.com/idadzie/zsh-presenter-mode) - Expands aliases during presentations. It also increases the terminal window's contrast to enhance visibility.
* [pretty-time (sindresorhus)](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
* [pretty-time (zpm-zsh)](https://github.com/zpm-zsh/pretty-time) - 将原始秒数转换为人类可读的字符串.
* [print-alias](https://github.com/brymck/print-alias) - 每当您在命令行中使用别名时，打印带有扩展别名的命令.
* [printc](https://github.com/philFernandez/printc) - Allows you to print in any color in the RGB space via a simple `printc` call.
* [profile-secrets](https://github.com/gmatheu/shell-plugins)  - 将敏感变量（api 令牌、密码等）安全地保存为终端初始化文件的一部分. 使用 gpg 使用您的秘密加密/解密文件.
* [project (gko)](https://github.com/gko/project) - 在本地和 github（私有或公共存储库）上创建 node/python/ruby 项目.
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - 用于管理项目的插件.
* [prompt-generator](https://github.com/the10thWiz/zsh-prompt-generator)  - 生成自定义主题. 一些生成的主题需要与电力线兼容的字体.
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - Quickly enable and disable proxy shell environment settings.
* [proxy](https://github.com/SukkaW/zsh-proxy) - Configure proxy settings for some package managers and software.
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - Plugin for lazy-loading `pyenv` in ZSH.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy) - Lazy load pyenv. The initial `eval "$(pyenv init -)"` is executed the first time `pyenv` is called.
* [pyenv](https://github.com/mattberther/zsh-pyenv)  - 受 zsh-rbenv 启发. 安装、更新或加载 `pyenv`，并添加额外的功能.
* [pyvenv-fast](https://github.com/ACmyles/pyvenv-fast)  - 使用一个命令启动 Python venv. 设计用于 [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv).
* [q (cal2195)](https://github.com/cal2195/q) - Add `vim`-like macro registers to your ZSH shell.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - 尾部/删除临时文件 [Q](https://github.com/y0ssar1an/q)，脏调试工具.
* [qiime2](https://github.com/misialq/zsh-qiime2) - Adds functions and aliases to make working with [Quiime 2](https://qiime2.org/) easier.
* [quer-ps1](https://github.com/ya0201/qwer-ps1) - A highly extendable manager for your ZSH prompt
* [quoter](https://github.com/pxgamer/quoter-zsh) - Display a random quote when opening a new terminal session.
* [quotify](https://github.com/damofthemoon/zsh-quotify) - Displays inspiring coding quotes from our pairs when starting up.
* [randeme](https://github.com/ex-surreal/randeme)  - 为每个会话选择一个随机主题. 如果您不喜欢所选主题，您可以运行 `randeme_rm` 以不再显示该主题.
* [random-quotes](https://github.com/vkolagotla/zsh-random-quotes) - 显示随机报价或事实.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - 改变你的颜色 [Razer Mouse](https://openrazer.github.io/) 基于最后执行的命令的状态. 需要 [OpenRazer](https://openrazer.github.io) linux drivers.
* [rbenv (ecortinas)](https://github.com/ecortinas/zsh-rbenv) - 基于 [zsh-pyenv](https://github.com/mattberther/zsh-pyenv) plugin. This plugin will install rbenv and make it readily available
* [rbenv (elliottcable)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - A faster fork of the rbenv plugin from oh-my-zsh.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - 基于原始 oh-my-zsh rbenv 插件的变体.
* [rbenv (meroje)](https://github.com/Meroje/zsh-rbenv) - 灵感来自 [https://github.com/lukechilds/zsh-nvm/](https://github.com/lukechilds/zsh-nvm/), makes it easier to work with ruby rbenvs.
* [rc-files](https://github.com/0b10/rc-files) - 添加用于编辑各种 rc 文件的快捷功能.
* [recall](https://github.com/mango-tree/zsh-recall) - 使使用命令历史更容易.
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - Plugin that re-enters working directory if it has been removed and re-created.
* [reload](https://github.com/aubreypwd/zsh-plugin-reload) - 添加快速重新加载您的`.zshrc`的功能.
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - A plugin which displays reminders above every prompt.
* [replace-multiple-dots](https://github.com/momo-lab/zsh-replace-multiple-dots) - Converts `...` to `../..`
* [revolver](https://github.com/molovo/revolver) - A progress spinner for ZSH scripts.
* [riddle-me](https://github.com/vkolagotla/zsh-riddle-me) - Displays random riddles.
* [ripz](https://github.com/jedahan/ripz)  - 提醒您您的别名，以便您更多地使用它们. 依赖于取决于 [ripgrep](https://github.com/BurntSushi/ripgrep).
* [robo](https://github.com/shengyou/robo-zsh-plugin) - A ZSH plugin for [Robo](https://github.com/consolidation/robo/).
* [rockz](https://github.com/aperezdc/rockz) - 基于 VirtualZ 的 Lua + LuaRocks 虚拟环境管理器.
* [rust](https://github.com/cowboyd/zsh-rust) - 配置你的 rust 工具链，安装 [rustup](https://rustup.rs) if it is not currently installed already.
* [rvm](https://github.com/johnhamelink/rvm-zsh) - 启动 RVM 并添加在用户的 `$PATH` 中可访问的 ruby​​gem 二进制文件（如指南针）.
* [safe-kubectl](https://github.com/benjefferies/safe-kubectl) - 在运行 `kubectl` 时添加一些安全性，方法是在自上次 `kubectl` 命令后的可定义秒数后警告您所处的上下文.
* [safe-paste](https://github.com/oz/safe-paste)  - 一个安全粘贴插件. 见康拉德欧文 [bracketed-paste](https://cirw.in/blog/bracketed-paste) blog post.
* [safe-rm](https://github.com/mattmc3/zsh-safe-rm) - 添加安全 rm 功能，以便 `rm` 将文件放入操作系统的垃圾箱，而不是永久删除它们.
* [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) - 当使用多个 AWS 配置文件时，例如您的阶段（开发、预生产、生产）的不同帐户，可用于确定当前导出的配置文件以及令牌是否仍然有效.
* [saml2aws](https://github.com/onyxraven/zsh-saml2aws) - Add support for [saml2aws](https://github.com/Versent/saml2aws).
* [sandboxd](https://github.com/benvan/sandboxd) - 仅在需要时运行设置命令（例如 `eval &quot;$(rbenv init -)&quot;` 等），通过延迟加载加速您的 `.zshrc` 和 shell 启动.
* [saneopt](https://github.com/willghatch/zsh-saneopt) - Sane defaults for ZSH options, in the spirit of vim-sensible.
* [sb-upgrade](https://github.com/redxtech/zsh-sb-upgrade) - 脚本自动更新种子箱上的应用程序.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) - Show current `chroot` name in your prompt.
* [sdkman](https://github.com/ptavares/zsh-sdkman) - 安装 [sdkman](https://github.com/sdkman) 并为其添加完成和别名.
* [sealion](https://github.com/xyproto/sealion) - Allows you to set reminders that will appear in your terminal when your prompt is refreshed.
* [search-directory-history](https://github.com/cmaahs/search-directory-history) - Allows complex search of per-directory history created using the [per-directory-history](https://github.com/jimhester/per-directory-history) plugin.
* [sed-sub](https://github.com/MenkeTechnologies/zsh-sed-sub) - 添加键绑定以在当前命令行上进行全局搜索和替换.
* [send](https://github.com/robertzk/send.zsh) - Single command to `git add`, `git commit`, and `git push` for much faster `git` workflow.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - Adds many `git` aliases and helper shell functions.
* [session-sauce](https://github.com/ChrisPenner/session-sauce) - An fzf interface for tmux session creation and management for all your projects.
* [setenv](https://github.com/kalpakrg/setenv) - Runs a script when you change directories.
* [shelf](https://github.com/ecmma/shelf) -Utility which can be used to bookmark and access directly any file using mnemonics.
* [shellfirm](https://github.com/kaplanelad/shellfirm)  - Shellfirm 是一个方便的实用程序，可帮助避免在没有额外批准步骤的情况下运行危险命令. 当检测到有风险的模式时，您将立即收到一个小的提示挑战，这将双重验证您的操作.
* [show-path](https://github.com/redxtech/zsh-show-path) - 提供逐行显示`$PATH`的功能.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - Plugin to easily start python `SimpleHTTPServer` and `SimpleHTTPSServer`.
* [skim](https://github.com/hackerchai/skim-zsh) - Adds support for [skim](https://github.com/lotabout/skim)
* [slugify](https://github.com/lashoun/slugify) - 将文件名和目录转换为网络友好格式.
* [smart-cd](https://github.com/dbkaplun/smart-cd) - Runs `ls` and `git status` after chpwd.
* [smartinput](https://github.com/momo-lab/zsh-smartinput) - 当您键入括号或引号时，会自动添加相应的结束括号/引号.
* [smile](https://github.com/fundor333/smile) - 添加显示随机笑脸的功能.
* [snippets](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion.
* [solarized-man](https://github.com/zlsun/solarized-man) - oh-my-zsh 的插件 colour-man-pages 的修改版本，针对 [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) 终端中的主题.
* [spack](https://github.com/Game4Move78/zsh-spack) - Includes some useful aliases and functions for loading/unloading [Spack](https://github.com/spack/spack)<i>-generated modules.</i> <b>- 生成的模块。</b> <i>As it makes use of the `module` command it is much more efficient than `spack load`.</i><b>由于它使用了 `module` 命令，它比 `spack load` 更有效。</b>
* [ssh-connect](https://github.com/gko/ssh-connect) - 一个简单的 `ssh` 管理器.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - `ssh` 的插件.
* [sshukh](https://github.com/anatolykopyl/sshukh-zsh-plugin) - Will update your `known_hosts` file when you `ssh` into a server.
* [startify](https://github.com/NorthIsMirror/zsh-startify) - Shows recently used `vim` files, shell-util files, active `tmux` sessions, recently-run `git` commands and more.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - Print the time it takes for the shell to start up.
* [stashy](https://github.com/MisterRios/stashy) - 简化使用 `git stash` 的插件.
* [statify](https://github.com/vladmrnv/statify) - Plugin that does basic statistical analysis.
* [sublime](https://github.com/valentinocossar/sublime) - 与 Oh My Zsh 的官方 Sublime 插件相同，但这会在当前 Sublime 窗口中打开文件（如果已经打开了一个文件）.
* [sudo](https://github.com/hcgraf/zsh-sudo)  - 来自 oh-my-zsh 的 `sudo` 插件，提取为独立的. 在 emacs 模式或 vi 命令模式下按 *ESC-ESC* 在当前/上一个命令之前切换 `sudo`.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - 使用 ZSH 的后缀别名直接在 shell 中打开文件。
* [svn-n-zsh](https://github.com/khrt/svn-n-zsh-plugin) - Rewrite of the stock oh-my-zsh svn plugin.
* [switch-git](https://github.com/robin-mbg/switch-git)  - 在 `git` 存储库之间轻松切换. 只需输入`sgr<some part of you repo's name>  `，按回车，你就在那里.
* [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) - Symfony 2 和 3 的 ZSH 插件.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - ZSH syntax highlighting with dircolors in realtime.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your ZSH. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgets without typing commands.
* [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard) - Adds key bindings support for ZLE (Zsh Line Editor) clipboard operations for vi emulation keymaps. It works under Linux, macOS and Android (via Termux).
* [systemd](https://github.com/le0me55i/zsh-systemd) - 为 `systemd` 添加了许多别名.
* [t32](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [tab-title](https://github.com/trystan2k/zsh-tab-title) - Set the terminal tab title according to current directory or running process. Forked from [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh)
* [tailf](https://github.com/rummik/zsh-tailf) - Adds `tailf` function with prefixed newlines instead of trailing newlines.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - Auto-completes task numbers for taskbook.
* [terminal-app](https://github.com/the8/terminal-app.zsh) - 用于与新 El Capitan Terminal.app 功能集成的插件.
* [terminal-title](https://github.com/AnimiVulpis/zsh-terminal-title) - 添加一个“set-term-title”功能，您可以使用它来命名终端窗口.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - A plugin that calculates and displays how many commands have been run via terminal.
* [termux](https://github.com/zpm-zsh/termux) - 增加兼容性 [Termux](https://termux.com/)
* [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) - 添加 terraform 工作区以提示.
* [terraform (jsporna)](https://github.com/jsporna/terraform-zsh-plugin) - Extends the original oh-my-zsh plugin with aliases and tab completions. Adds workspace (when not default) to prompt.
* [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) - 添加方便别名 [terraform](https://terraform.io/), tab completions and helper function to add your terraform workspace in the prompt.
* [terraform (pbar1)](https://github.com/pbar1/zsh-terraform) - ZSH 的 Terraform 便利函数和别名.
* [terraform (thuandt)](https://github.com/thuandt/zsh-terraform) - 为 `terraform` 添加了方便的别名，并为 `terraform` 和 `terragrunt` 添加了补全.
* [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - 插件 [Terragrunt](https://github.com/gruntwork-io/terragrunt), 一个薄包装 [Terraform](https://terraform.io/) that provides extra tools.
* [tfenv](https://github.com/CDA0/zsh-tfenv) - Installs, updates, and loads tfenv inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)
* [tfswitch](https://github.com/ptavares/zsh-tfswitch) - Installs and loads [tfswitch](https://github.com/warrensbox/terraform-switcher).
* [tgswitch](https://github.com/ptavares/zsh-tgswitch) - Installs and loads [tgswitch](https://github.com/warrensbox/tgswitch).
* [thefuck](https://github.com/laggardkernel/thefuck) - Loads [thefuck](https://github.com/nvbn/thefuck) （一种更正您先前命令的工具）具有缓存支持，可显着减少加载时间.
* [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) - 使用的便利功能 [theia-ide](https://github.com/theia-ide/theia).
* [tig](https://github.com/MenkeTechnologies/zsh-tig-plugin) - 添加一些高级绑定 [tig](https://github.com/jonas/tig) and also provides a `tig-pick` script.
* [timewarrior](https://github.com/svenXY/timewarrior) - Adds support for [timewarrior](https://timewarrior.net/)，一个时间跟踪应用程序.
* [tipz](https://github.com/molovo/tipz) - 如果您有刚刚运行的命令的别名，则显示您的别名，类似于 [alias-tips](https://github.com/djui/alias-tips).
* [title](https://github.com/zpm-zsh/title) - 允许您设置终端窗口标题.
* [titles](https://github.com/jreese/zsh-titles) - 自动窗口和标签标题 [tmux](https://tmux.github.io) and xterm-compatible terminals.
* [tm](https://github.com/kjhaber/tm.zsh) - Simplifies creating new [tmux](https://tmux.github.io) sessions, attaching to existing sessions, switching between sessions, and listing active sessions.
* [tmux-auto-title](https://github.com/mbenford/zsh-tmux-auto-title) - Automatically sets the title of windows/panes as the current foreground command.
* [tmux-multisession](https://github.com/nichus/zsh-tmux-multisession) - 插件 [tmux](https://tmux.github.io) 支持单个服务器进程上的多个会话.
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - 改名 [tmux](https://tmux.github.io) windows automatically.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - 使用简单的插件 [tmux](https://tmux.github.io) with ZSH.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - 在正在运行的“vim”（或 NeoVim）会话中打开文件，从相邻 [tmux](https://tmux.github.io) 面包.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - Create unified terminal titles for `tmux`, ZSH, and Vim/NVIM, modular.
* [tmux](https://github.com/zpm-zsh/tmux) - 插件 [tmux](https://tmux.github.io).
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) - 具有 R-EP-L 的简单 ZSH 插件 [tmux](https://tmux.github.io) session.
* [toggl](https://github.com/natterstefan/toggl-zsh-plugin) - Adds a `toggl-week` command to display the total working hours tracked on [toggl.com](https://toggl.com)
* [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix) - Add a widget to toggle a prefix to a command. Binds Alt+s to prefix a command with `sudo` by default.
* [traista](https://github.com/odgon/traista) - Includes `git` status decorations and color-coded exit status of the last command run. Better with dark terminal themes.
* [travis](https://github.com/denolfe/zsh-travis) - 打开当前存储库的 Travis CI 页面（如果存在）.
* [tre](https://github.com/redxtech/zsh-tre) - 使用 [tre](https://github.com/dduan/tre#editor-aliasing) easier.
* [tsm](https://github.com/RobertAudi/tsm) - Adds a [tmux](https://tmux.github.io) Session Manager.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) - Adds tools for macOS.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 aliases.
* [ugit](https://github.com/Bhupesh-V/ugit) - 让您撤消上一次 `git` 操作.
* [uncloudium](https://github.com/Talon1024/omz-uncloudium) - Adds helper script to download crx files from the Google Chrome web store.
* [undollar](https://github.com/zpm-zsh/undollar) - Strips the dollar sign from the beginning of the terminal prompt.
* [unique-id](https://github.com/z-shell/zsh-unique-id) - provides a unique number that identifies a running Zshell session, in its shell variable `$ZUID_ID`. Besides this unique number, also a unique codename is provided, in shell variable `$ZUID_CODENAME`. An example use case is to hold logs in files `.../mylog-${ZUID_CODENAME}.log`, so that two different Zshells will not write to the same file at the same time.
* [unix-simple](https://github.com/redxtech/zsh-unix-simple) - A command that shows a graphic about the simplicity of unix.
* [up (cjayross)](https://github.com/cjayross/up) - A simple way to navigate up through directories.
* [up (peterhurford)](https://github.com/peterhurford/up.zsh) - Adds an up command to `cd` multiple levels up.
* [update-zsh](https://github.com/AndrewHaluza/zsh-update-plugin) - Updates custom oh-my-zsh plugins. Only works with the oh-my-zsh framework.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) <i>- A plugin for the ZSH syntax highlighter that turns URLs green if they respond with a &quot;good&quot; status, and red otherwise.</i> <b>- ZSH 语法高亮插件插件，如果 URL 以“良好”状态响应，则将其变为绿色，否则变为红色。</b> <i>Useful for checking URL typos.</i><b>用于检查 URL 拼写错误。</b>
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - 扩展原始 oh-my-zsh venv 模块的功能.
* [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) - 一个包装插件 [vagrant](https://www.vagrantup.com/) 允许从 box 目录之外调用 `vagrant` 命令. 该插件还附带了一些额外的命令，可帮助管理多个框，以及自定义选项卡完成.
* [vanilli.sh](https://github.com/yous/vanilli.sh) - A lightweight start point of shell configuration.
* [vapor](https://github.com/notf0und/zsh-vapor) - Laravel vapor plugin for zsh to help you to run vapor from anywhere in the project tree, with auto-completion!
* [vcshr](https://github.com/aubreypwd/zsh-plugin-vcshr) - Help vcsh users require Github repositories using `vcsh` for auto-installation in `~/.zshrc`, etc.
* [velocity](https://github.com/rahulsalvi/velocity-python) - ZSH 和基于电力线的主题元素 [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) - 一种超轻量级的克隆 [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) ; 它几乎希望您使用 [pyenv](https://github.com/pyenv/pyenv) （尽管您没有*必须*），并且因为它基于 [`venv` module](https://docs.python.org/3/library/venv.html), (creation) only works for python >= 3.3.
* [venv-wrapper](https://github.com/glostis/venv-wrapper) - Provides ZSH functions to ease the management of your virtual environments using `venv`.
* [vi-increment](https://github.com/zsh-vi-more/vi-increment) - Add `vim`-like increment/decrement operations.
* [vi-mode (jeffreytse)](https://github.com/jeffreytse/zsh-vi-mode) - ZSH 的更好和友好的 vi(vim) 模式插件.
* [vi-mode (nyquase)](https://github.com/Nyquase/vi-mode) Add extra `vi`-like functionality.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - Add more `vi`-like functionality to ZSH.
* [vi-motions](https://github.com/zsh-vi-more/vi-motions) - Add new motions and text objects including quoted/bracketed text and commands.
* [vi-quote](https://github.com/zsh-vi-more/vi-quote) - 添加引用或取消引用动作的操作.
* [viexchange](https://github.com/okapia/zsh-viexchange) - A `vi` mode plugin for easily swapping text between two places in the buffer, like vim-exchange.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) - 友好的 `vi`-mode 绑定，添加基本的 Emacs 键、增量搜索、模式指示器等.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - Allows you to do `vim filename:123` to open a file with the cursor at a specific line.
* [vimman](https://github.com/yonchu/vimman) - 查看 `vim` 插件手册（帮助），如 ZSH 中的 `man`.
* [vimto](https://github.com/laurenkt/zsh-vimto) - Improved ZSH `vi` mode (bindkey -v) plugin.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - 用于 oh-my-zsh 的修改后的 virtualenv ZSH 插件.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt)  - 来自上游的 virtualenv 插件的一个分支. 添加了对自定义 oh-my-zsh 主题中的 virtualenv 提示的支持.
* [virtualz](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) 受 Adam Brenecki 启发的经理 [Virtualfish](https://github.com/adambrenecki/virtualfish) 为了 [Fish shell](http://fishshell.com/), replaces virtualenvwrapper.
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - An oh-my-zsh plugin for the [virtuozzo](https://docs.virtuozzo.com/master/index.html) bare-metal virtualization system.
* [visit](https://github.com/justinpchang/visit) - 用于更快导航的自定义插件.
* [volta (cowboyd)](https://github.com/cowboyd/zsh-volta) - Seamlessly install and configure the [Volta](https://volta.sh) NodeJS 工具链管理器.
* [volta](https://github.com/ri7nz/zsh-volta) - Installs and loads [ Volta: JS Toolchains as Code](https://github.com/volta-cli/volta).
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - An oh-my-zsh plugin to control [VOX](https://vox.rocks/)，一款轻量级的全功能音频播放器，适用于 macOS，可以播放包括 FLAC 和 Ogg Vorbis 在内的多种格式.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for Visual Studio Code on macOS.
* [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) - 简单的插件，可以轻松地跨系统打开 VS 代码.
* [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) - 插件 [Visual Studio Code](https://code.visualstudio.com/).
* [vterm](https://github.com/randomphrase/vterm-zsh-plugin) - Lets you run emacs commands directly from [vterm](https://github.com/vterm/vterm) 外壳会话.
* [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) - Track how much [time](https://wakatime.com/) you have spent in your terminal. Has per project stats.
* [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) - 使用 ZSH 中的命令自动时间跟踪 [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - Configures colorization with [grc](https://github.com/garabik/grc).
* [watch](https://github.com/enrico9034/zsh-watch-plugin) - 通过按“CTRL + W”，可以轻松地为当前或以前的命令添加前缀.
* [watson.zsh](https://github.com/bcho/Watson.zsh) - A plugin for the [watson](https://github.com/TailorDev/Watson) time management system.
* [wd](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
* [web-search (sinetoami)](https://github.com/sinetoami/web-search) - 添加命令以直接从 CLI 运行 bing、google、yahoo 和 duckduckgo 搜索.
* [web-search (yabanahano)](https://github.com/Yabanahano/web-search) - 添加别名以使用 Google、Wiki、Bing、YouTube 和其他流行服务进行搜索.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - Highlight where a particular line was last changed in a file using `git blame`.
* [window-title](https://github.com/olets/zsh-window-title) - 将信息图块添加到您的终端窗口.
* [windows-title](https://github.com/mdarocha/zsh-windows-title) - Dynamically updates terminal window title with current directory and the last command run.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) - Simple utility for jumping between projects.
* [worktree](https://github.com/jspears/worktree) - Adds functions that wrap `git worktree`.
* [xdg-basedirs](https://github.com/zshzoo/xdg-basedirs) - 配置应用程序以使用 XDG 基本目录.
* [xxh-plugin-zsh-zshrc](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) - 插件 [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) that copies your `~/.zshrc` to a remote host and sources it with [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh).
* [yadm](https://github.com/juanrgon/yadm-zsh) - Displays a warning if there are local yadm configuration changes.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - 如果 `pipenv` 检测到存在一个目录，则自动激活目录的 pip 环境.
* [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's Yeoman plugin for oh-my-zsh, compatible with yeoman version ≥1.0 (includes options and command auto-completion).
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH 插件，提醒您使用您定义的那些别名.
* [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) - Adds `yt` aliases to download videos from YouTube.
* [youtube-dl](https://github.com/joow/youtube-dl) - 简单的插件 [youtube-dl](https://youtube-dl.org/).
* [yup](https://github.com/redxtech/zsh-yup) - 添加帮助函数以升级 yarn/npm 项目中的所有依赖项.
* [z.lua](https://github.com/skywind3000/z.lua)  - 一个命令行工具，可帮助您通过学习习惯来更快地导航. 一个替代方案 [z.sh](https://github.com/rupa/z) with Windows and posix shells support and various improvements. 10x faster than fasd and autojump, 3x faster than [z.sh](https://github.com/rupa/z).
* [zabb](https://github.com/Mellbourn/zabb) - `zabb` is a command that tries to figure out the shortest memorable abbreviation of a directory that is usable by [z](https://github.com/ajeetdsouza/zoxide) to unambiguously jump to that directory.
* [zabrze](https://github.com/Ryooooooga/zabrze) - ZSH 缩写扩展插件.
* [zaw](https://github.com/zsh-users/zaw) - ZSH any.el-like 小部件.
* [zbrowse](https://github.com/zdharma-continuum/zbrowse) - When doing shell work, it is often the case that echo $variable is invoked multiple times, to check the result of a loop, etc. With ZBrowse, you just need to press `Ctrl-B`, which invokes the ZBrowse – Zshell variable browser.
* [zce](https://github.com/hchbaw/zce.zsh) - Vim’s EasyMotion / Emacs’s ace-jump-mode for ZSH.
* [zcolors](https://github.com/marlonrichert/zcolors) - Uses your `$LS_COLORS` to generate a coherent theme for Git and your Zsh prompt, completions and [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [zconvey](https://github.com/zdharma-continuum/zconvey) - Adds ability to send commands to other ZSH sessions, you can use this to `cd $PWD` on all active ZSH sessions, for example.
* [zed](https://github.com/eendroroy/zed-zsh) - A simple wrapper for [z](https://github.com/rupa/z) 通过 ZSH 插件安装它.
* [zeit](https://github.com/zeit/zeit.zsh-theme) - 针对深色背景进行了优化，包括 `git` 状态信息.
* [zellij (jaeheonji)](https://github.com/jaeheonji/zsh-zellij-plugin) - 提供使用环境 [zellij](https://github.com/zellij-org/zellij) . 需要`tmux`.
* [zellij (tranzystorek-io)](https://github.com/tranzystorek-io/zellij-zsh) - Provides an environment that autostarts [zellij](https://github.com/zellij-org/zellij) as your terminal's multiplexer.
* [zeno](https://github.com/yuki-yano/zeno.zsh) - Fuzzy completion and utility plugin powered by [Deno](https://deno.land/).
* [zero](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details.
* [zflai](https://github.com/zdharma-continuum/zflai) - ZSH 的快速日志记录框架.
* [zfzf](https://github.com/b0o/zfzf) - A fzf-powered file picker for ZSH which allows you to quickly navigate the directory hierarchy.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - 使 compinit 在所有加载完成后只运行一次 [zgen](https://github.com/tarjoilija/zgen).
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) - Custom extras for zimfw, packaged into a zimfw plugin.
* [zinfo_line](https://github.com/kmhjs/zinfo_line) - Makes more information available to ZSH themes.
* [zinit-annex-bin-gem-node](https://github.com/zdharma-continuum/zinit-annex-bin-gem-node) - [zinit](https://github.com/zdharma-continuum/zinit) extension that exposes binaries without altering `$PATH`, installs Ruby gems and Node modules and easily exposes their binaries, and updates the gems and modules when the associated plugin or snippet is updated.
* [zinit-annex-default-ice](https://github.com/zdharma-continuum/zinit-annex-default-ice) - 允许用户为多个 zinit 命令定义激活的 ice.
* [zinit-annex-man](https://github.com/zdharma-continuum/zinit-annex-man) - [Zinit](https://github.com/zdharma-continuum/zinit) extension that generates man pages for all plugins and snippets
* [zinit-annex-meta-plugins](https://github.com/zdharma-continuum/zinit-annex-meta-plugins) - 使用单个标签安装插件组（[zinit](https://github.com/zdharma-continuum/zinit) 只要）.
* [zinit-annex-patch-dl](https://github.com/zdharma-continuum/zinit-annex-patch-dl) - [zinit](https://github.com/zdharma-continuum/zinit) extension that downloads files and applies patches through the provided `dl` and `patch` zinit ices.
* [zinit-annex-readurl](https://github.com/zdharma-continuum/zinit-annex-readurl) - 添加功能以自动下载网页上托管 URL 的文件的最新版本.
* [zinit-annex-rust](https://github.com/zdharma-continuum/zinit-annex-rust) - [zinit](https://github.com/zdharma-continuum/zinit) extension that that installs rust and cargo packages inside plugin directories.
* [zinit-annex-submods](https://github.com/z-shell/z-a-submods) - [zinit](https://github.com/zdharma-continuum/zinit) extenstion allows installing and managing additional submodules within a plugin or snippet.
* [zinit-annex-test](https://github.com/NorthIsMirror/z-a-test) - [zinit](https://github.com/zdharma-continuum/zinit) extension that runs tests (via make test, for example) – if it finds any of them – after installing and updating a plugin or snippet.
* [zinit-annex-unscope](https://github.com/zdharma-continuum/zinit-annex-unscope) - 允许安装插件 [zinit](https://github.com/zdharma-continuum/zinit) 无需通过查询 Github API 指定用户名.
* [zinit-console](https://github.com/z-shell/zinit-console) - A semigraphical (curses) consolette for the [zinit](https://github.com/zdharma-continuum/zinit) 插件管理器.
* [zinsults](https://github.com/ahmubashshir/zinsults) - 如果命令失败，则打印侮辱.
* [zjump](https://github.com/qoomon/zjump)  - 简化 ZSH 目录导航； 跳转到已经访问过的父文件夹或子文件夹.
* [zlitefetch](https://github.com/ippee/zlitefetch) - Lightweight system information plugin.
* [zlong_alert](https://github.com/kevinywlui/zlong_alert.zsh) - Uses notify-send and ring a bell to alert you when a command that has taken a long time (default: 15 seconds) has completed.
* [zman](https://github.com/mattmc3/zman) - 使用 `fzf` 快速浏览 Zsh 手册.
* [zoxide](https://github.com/ajeetdsouza/zoxide) - 学习您习惯的“cd”的快速替代方案.
* [zredis](https://github.com/zdharma-continuum/zredis) - Adds Redis database support, with `database_key` <-> `shell_variable` binding. Supports all data types.
* [zsh-in-docker](https://github.com/deluan/zsh-in-docker) - Automates ZSH + Oh-My-ZSH installation into development containers. Works with Alpine, Ubuntu, Debian, CentOS or Amazon Linux.
* [zsh-not-vim](https://github.com/redxtech/zsh-not-vim) - 提供自动羞辱用户忘记他们没有在 vim 中的功能.
* [zsh-z (agkozak)](https://github.com/agkozak/zsh-z) - Jump quickly to directories that you have visited "frecently." A native ZSH port of `z.sh` - without `awk`, `sed`, `sort`, or `date`.
* [zsh-z (ptavares)](https://github.com/ptavares/zsh-z) - Installs and loads [z](https://github.com/rupa/z.git).
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for oh-my-zsh.
* [zshrc](https://github.com/freak2geek/zshrc) - 从您的项目范围加载本地 `.zshrc` 文件.
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - 用于在 Arch Linux 上拍摄 ZFS 升级前/升级后快照的插件.
* [zsnapshot](https://github.com/zdharma-continuum/zsnapshot) - 添加命令以将当前 ZSH 状态转储到文件中，以便以后通过获取快照文件进行恢复.
* [ztouch](https://github.com/mjrafferty/ztouch) - 为最近的历史命令、目录堆栈、模式之间的循环和用户可映射命令添加触摸栏控件到 macOS 上的触摸栏.
* [zui](https://github.com/zdharma-continuum/zui) - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH.)

## Completions

These plugins add tab completions without adding extra functions or aliases.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - 扩展 ZSH 的 \_urls 补全，允许它从 html 页面补全 url.
* [aliyun](https://github.com/thuandt/zsh-aliyun) - Add completions for the [Aliyun CLI](https://github.com/aliyun/aliyun-cli).
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - viasite-ansible/ansible-server 的完成.
* [antibody-completion](https://github.com/sinetoami/antibody-completion) - This plugin provides completion for [Antibody](https://github.com/getantibody/antibody) 插件管理器.
* [appspec](https://github.com/perlpunk/App-AppSpec-p5) - 根据 YAML 规范为 Bash 和 ZSH 生成完成
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - autopkg 的完成.
* [aws-completions](https://github.com/eastokes/aws-plugin-zsh) - 添加对 `awscli` 的完成支持以管理 AWS 配置文件/区域并在提示中显示它们.
* [aws_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) - 为 aws_manager CLI 添加完成.
* [bash-completions-fallback](https://github.com/3v1n0/zsh-bash-completions-fallback) - Support `bash` completions for commands when no native ZSH one is available.
* [batect](https://github.com/batect/batect-zsh-completion/) - 添加选项卡完成 [batect](https://batect.dev/) 构建系统.
* [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - 更好的 `npm` 选项卡完成.
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - Adds BOSH autocompletion.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) - 自制服务的完成插件.
* [buidler](https://github.com/gonzalobellino/buidler-zsh) - 为 NomicLabs Buidler 工具添加完成和有用的别名 [buidler.dev](https://buidler.dev).
* [bw](https://github.com/CupricReki/zsh-bw-completion) - Adds completion for [Bitwarden](https://bitwarden.com/).
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - 为 cabal 添加制表符补全.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal.
* [carapace](https://github.com/rsteube/carapace) - Completion generator for Bash, Elvish, Fish, Oil, Powershell, Xonsh and ZSH. Note - not dynamic, you have to explicitly run it to generate completions for a command.
* [cargo](https://github.com/MenkeTechnologies/zsh-cargo-completion) - 原始 OMZ 货物补全的所有功能，通过 `cargo add` 中的 `cargo search` 额外支持远程板条箱.
* [carthage](https://github.com/squarefrog/zsh-carthage) - 提供补全和别名以供使用 [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) - Adds autocomplete for all [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) 命令.
* [cod](https://github.com/dim-an/cod) - A completion demon for `bash`/`fish`/`zsh` which creates completion functions on the fly when it sees you run something with `--help`.
* [codeception](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - 显示 git 信息，是否通过 `ssh` 登录，返回最后一个命令的代码.
* [comonicon](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) - 选项卡完成 [comonicon](https://github.com/Roger-luo/Comonicon.jl).
* [completions](https://github.com/zsh-users/zsh-completions) - A collection of extra completions for ZSH.
* [conda](https://github.com/esc/conda-zsh-completion) - conda 的 ZSH 选项卡完成.
* [cpan](https://github.com/MenkeTechnologies/zsh-cpan-completion) - Adds `cpan install word<tab>` and `cpanm install <tab>` to complete remote CPAN package names.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - 选项卡完成 [ctop](https://github.com/bcicen/ctop).
* [dagger](https://github.com/jygastaud/dagger-oh-my-zsh) - 完成匕首.
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - 自动为 DBIx::Class::Migration 的脚本和 Dancer 设置环境变量.
* [docker (chr-fritz)](https://github.com/chr-fritz/docker-completion.zshplugin) - Loads `docker` ZSH tab completions directly from **Docker for Mac**.
* [docker (felixr)](https://github.com/felixr/docker-zsh-completion) - Add tab completions for `docker`.
* [docker (greymd)](https://github.com/greymd/docker-zsh-completion) - 为 `docker` 和 `docker-compose` 添加选项卡补全.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - Command completion for [docker-enter](https://github.com/jpetazzo/nsenter).
* [dotnet](https://github.com/MenkeTechnologies/zsh-dotnet-completion) - Dotnet tab completion.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for ZSH.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - A ZSH plugin for [duell](https://github.com/gameduell/duell).
* [efibootmgr](https://github.com/wehlando/efibootmgr-zsh-completion) - `efibootmgr` 的选项卡完成.
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - 添加 etcdctl 选项卡补全.
* [expressvpn](https://github.com/tk7r/zsh-expressvpn) - 为 [expressVPN](https://www.expressvpn.com/support/vpn-setup/app-for-linux/) 客户.
* [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) - 定义一个名为 extract 的函数，用于提取您传递给它的存档文件，并支持多种存档文件类型.
* [extract (thetic)](https://github.com/thetic/extract) - Fork of the oh-my-zsh extract plugin.
* [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - 为所有人添加自动完成选项 [Concourse CLI](https://www.concourse.ci/fly-cli.html) 命令.
* [fzf-gcloud](https://github.com/mbhynes/fzf-gcloud) - 导航和预览所有 Google Cloud SDK `gcloud` CLI 命令的模糊补全
* [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) - 使用 GNU Readline 为 ZSH、bash 和应用程序添加选项卡完成.
* [fzf-zsh-completions](https://github.com/chitoku-k/fzf-zsh-completions) - Fuzzy completions for [fzf](https://github.com/junegunn/fzf) 和 [ZSH](https://www.zsh.org/) 可以由默认为 `**` 的触发序列触发.
* [gcloud](https://github.com/littleq0903/gcloud-zsh-completion) - 为 Google Cloud SDK 添加补全.
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - providing ZSH completion support to various Gentoo tools that lack completion scripts upstream.
* [git-annex](https://github.com/Schnouki/git-annex-zsh-completion) - Allows tab completion for most git-annex commands.
* [git-flow](https://github.com/bobthecow/git-flow-completion) - ZSH 完成支持 [git-flow](http://github.com/nvie/gitflow).
* [git-fzf](https://github.com/alexiszamanidis/zsh-git-fzf) - ZSH plugin that wraps `git` operations for simplicity and productivity. It also contains completions and combines support for [fzf](https://github.com/junegunn/fzf).
* [github-cli](https://github.com/sudosubin/zsh-github-cli) - github cli 的选项卡完成.
* [gitlab-runner](https://github.com/pseyfert/zsh-gitlab-runner-completion) - ZSH completions for gitlab-ci-multi-runner.
* [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) - 对 gradle 的 Bash 和 ZSH 完成支持.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - 对 gradle 的 ZSH 完成支持.
* [grid5000](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 plugin - adds theme, autocompletions.
* [gulp (akoenig)](https://github.com/akoenig/gulp.plugin.zsh) - 在 Z-Shell (ZSH) 中自动完成 gulp.js 任务.
* [gulp (srijanshetty)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - gulp 的自动补全.
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) - 完成 [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haskell](https://github.com/coot/zsh-haskell) - Adds completions for `cabal`, `ghc` and `ghc-pkgs` commands.
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib.
* [helmfile](https://github.com/Downager/zsh-helmfile) - Adds autocompletion for `helm`.
* [inspr](https://github.com/ptcar2009/insprzsh) - 完成 [inspr](https://github.com/inspr/inspr)
* [ipfs](https://github.com/hellounicorn/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.io).
* [joe](https://github.com/corvofeng/joe-completion) - Adds completions for [joe](https://github.com/karan/joe) .gitignore 编辑器.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - jtool 的 ZSH 完成.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - 添加自动完成 [jumpstorm](https://github.com/netresearch/jumpstorm)
* [jx](https://github.com/haysclark/zsh-jx) - Adds tab completions for the Jenkins-X cli.
* [kafka](https://github.com/Dabz/kafka-zsh-completions) - 完成 Apache [kafka](https://kafka.apache.org).
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - 完成 [keybase](https://keybase.io/docs/command_line).
* [kitty](https://github.com/redxtech/zsh-kitty) - 完成 [kitty](https://sw.kovidgoyal.net/kitty/) 终端模拟器.
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - Add tab completions for [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - Add tab completions for [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
* [kubectl-fzf](https://github.com/bonnefoa/kubectl-fzf) - Fast and powerful [`fzf`](https://github.com/junegunn/fzf)- 为 `kubectl` 提供动力的自动完成功能.
* [lazycomplete](https://github.com/rsteube/lazycomplete) - 延迟加载 shell 完成脚本.
* [lets](https://github.com/lets-cli/lets-zsh-plugin) - Add autocompletion for [lets](https://github.com/lets-cli/lets) cli 任务运行器.
* [ls-go](https://github.com/MohamedElashri/ls-go-zsh) - 添加一些有用的别名 [ls-go](https://github.com/acarl005/ls-go).
* [mooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - completion generator for Perl module `MooseX::App`.
* [more-completions](https://github.com/MenkeTechnologies/zsh-more-completions) - 10500 个 zsh compsys 完成！
* [msfvenom](https://github.com/Green-m/msfvenom-zsh-completion) - Tab completions for Metasploit.
* [mx-honey](https://github.com/mukel/mx-honey) - Provides completions for [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.
* [newman](https://github.com/selop/newman-autocomplete) - Provides autocompletion for the [Newman CLI](https://github.com/postmanlabs/newman).
* [nix](https://github.com/spwhitt/nix-zsh-completions) - 完成 [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/)， 和 [NixOps](https://nixos.org/nixops/).
* [node-ace](https://github.com/romch007/node-ace-zsh-completion) - Completions for `node ace`.
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) - 为 nova 提供自动完成功能.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - 对“npm run”的自动完成支持。
* [nx](https://github.com/jscutlery/nx-completion) - 完成 [nx](https://nx.dev) . 需要 [`jq`](https://stedolan.github.io/jq/).
* [okta](https://github.com/sirhc/okta.plugin.zsh) - 提供命令行补全 [`aws-okta`](https://github.com/segmentio/aws-okta) 和 [okta-awscli](https://github.com/jmhale/okta-awscli) comm和s.
* [op](https://github.com/sirhc/op.plugin.zsh) - 选项卡完成 [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) 命令行工具.
* [packer](https://github.com/wakeful/zsh-packer) - 添加选项卡完成 [packer](https://packer.io).
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin.
* [parallels](https://github.com/benclark/parallels-zsh-plugin) - Add completions for Parallels desktop.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - 方便的回购，轻松获得 [pass](https://www.passwordstore.org/) command completion for ZSH.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - Autocompletion plugin for pip.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - Enables aliases for the most common pipenv commands.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) - `pipenv` 的完成.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh)  - 如果该目录中有 Pipfile，则在进入目录时自动激活 **pipenv**. 包括 `pipenv` 完成.
* [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) - 为 Pivotal 的添加完成 [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
* [pmy](https://github.com/relastle/pmy) - 通用的上下文感知 ZSH 完成引擎，由 [fzf](https://github.com/junegunn/fzf).
* [quickjump](https://github.com/fikovnik/zsh-quickjump) - Adds tab completion support for [skim](https://github.com/lotabout/skim) 对于最近使用的文件和目录 [fasd](https://github.com/whjvenyl/fasd).
* [racket completion](https://github.com/racket/shell-completion) - 完成 [Racket](http://racket-lang.org).
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets.
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) - Add completions for the Rancher CLI.
* [rhoas](https://github.com/craicoverflow/rhoas-zsh-plugin) - Adds completions for [rhoas](https://developers.redhat.com/products/red-hat-openshift-streams-for-apache-kafka/overview).
* [rustup](https://github.com/pkulev/zsh-rustup-completion) - Rustup 的选项卡完成.
* [s3cmd](https://github.com/FFKL/s3cmd-zsh-plugin) - 添加选项卡完成 [s3cmd](https://s3tools.org/s3cmd).
* [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion)  - Salesforce CLI 的 ZSH 命令完成. 需要 [jq](https://stedolan.github.io/jq/).
* [saml2aws](https://github.com/sirhc/saml2aws.plugin.zsh) - Adds completions for [saml2aws](https://github.com/Versent/saml2aws).
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) - sfdx 的自动完成插件.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - 添加自动完成 [spring-boot](http://projects.spring.io/spring-boot/) 命令.
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - Manage `ssh-agent`.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - Automatically starts `ssh-agent` to set up and load whichever credentials you want for `ssh` connections.
* [ssh](https://github.com/zpm-zsh/ssh) - 为 `ssh` 添加主机补全.
* [surf](https://github.com/beardcoder/surf.plugin.zsh) - 添加完成冲浪.
* [symphony (TheGrowingPlant)](https://github.com/TheGrowingPlant/symfony.plugin.zsh) - Autocompletion for Symfony 3 and 4 commands.
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - Add completions for [Test Kitchen](https://github.com/test-kitchen/test-kitchen)).
* [tinygo](https://github.com/sago35/tinygo-autocmpl) - Add tab completions for tinygo.
* [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your [tmux](https://tmux.github.io) 面包.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - 添加自动完成 [tugboat](https://github.com/petems/tugboat) 命令.
* [umake](https://github.com/zlsun/umake) - Tab completion for Ubuntu umake.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - 提供自动完成功能 [vertx](https://vertx.io/) 命令.
* [web-open](https://github.com/AndrewHaluza/zsh-web-open)  - 添加别名以打开网页. 仅适用于 Ubuntu 20.
* [yabai](https://github.com/Amar1729/yabai-zsh-completions) - 为 macOS 添加补全 [yabai](https://github.com/koekeishiya/yabai/) 平铺窗口管理器.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - 为 `yarn add`、`yarn remove`、`yarn upgrade`、`yarn why` 和 `yarn run` 添加自动完成功能.
* [zargparse](https://github.com/ctil/zargparse) - Pass it a script that uses `argparse` and it will write a ZSH completion to your current directory.
* [zstyle-completions](https://github.com/zshzoo/zstyle-completions) - 给 [prezto-style](https://github.com/sorin-ionescu/prezto) 点击选项卡时完成.

## Themes

If you're using [Antigen](https://github.com/zsh-users/antigen) ，您可以使用“antigen theme githubuser/repo”在运行的 ZSH 中测试这些主题. 如果你正在使用 [zgenom](https://github.com/jandamm/zgenom)，使用 `zgenom load githubuser/reponame` 将它们添加到您的 `init.zsh` 中.

* [000](https://github.com/Abid-Ahmad/oh-my-zsh-000-theme) - Multiline prompt with username, hostname, full path, return status and `git` decorations.
* [0i0](https://github.com/0i0/0i0.zsh-theme) - Optimized for dark terminal windows, uses nerdfont `git` status decorations.
* [14degree](https://github.com/saims0n/14degree-zsh-theme/) - 包括 `git`、`virtualenv` 和 `rvm` 状态装饰.
* [4den](https://github.com/RunThem/zsh-theme-4den) - Minimalist. Includes `git` and `hg` status decorations.
* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - Based on the Sorin theme.
* [abbr (theme)](https://github.com/PhilsLab/abbr-zsh-theme)  - 显示当前目录路径的缩写版本，显示 Python virtualenv、Rust 版本、`git` 状态和最后一个命令的退出代码. 默认情况下适用于深色背景，但可以轻松自定义颜色.
* [absolute](https://github.com/NelsonBrandao/absolute) - Very clean looking theme with git status, node version and the exit code from the last command.
* [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) - 包括 `git` 状态装饰、AWS 配置文件名称、Azure 服务主体名称、kubernetes 上下文、terraform 工作区、命令状态和当前工作目录.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS theme, requires a Powerline-compatible font.
* [af-magic-dynamic](https://github.com/rslavin/af-magic-dynamic) - 修改版 [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) 动态路径缩短.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - Modified version of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme in oh-my-zsh.
* [aftermath](https://github.com/schanur/aftermath) - 在您在 shell 中运行的每个命令后获得一个漂亮的摘要行.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) - 基于 [agnoster](https://gist.github.com/3712874) 主题包含在 [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) . 显示有关 `git` 状态的详细信息.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt) - Uses three asynchronous methods to keep the ZSH prompt responsive while displaying the `git` status and indicators of SSH connection, exit codes, and `vi` mode, along with an abbreviated, `PROMPT_DIRTRIM`-style path. Very customizable. Asynchronous even on Cygwin and MSYS2.
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - Solarized [Agnoster](https://gist.github.com/agnoster/3712874) variant with `git` status information. Requires a unicode font and works best with a [solarized](https://github.com/altercation/solarized) 终端.
* [agnoster-fseguin](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) variant with a right prompt.
* [agnoster-gentoo](https://github.com/r7l/agnoster-gentoo-zsh-theme) - Gentoo 风格的版本 [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme) that includes user@hostname and `git` status decorations. Works better with a unicode font.
* [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) - 优化 [solarized](https://ethanschoonover.com/solarized/) 配色方案、`git` 或其他 VCS 工具以及兼容 unicode 的字体. 包括上次命令运行的状态、user@hostname、`git` 状态装饰、工作目录、是否以 root 身份运行、后台作业是否正在运行等信息.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有正确提示的变体.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体优化用于 [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) 终端配色方案. 包括 `git` 状态.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体，包括电池和在线状态.
* [agnoster-repopath](https://github.com/ivanfurlan/agnoster-repopath-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [Passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) themes. Includes `git` 和 `mercurial` status, current time 和 time the last comm和 took decorations in the prompt.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 添加了时间戳和换行符的变体.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - 基于 [Powerline](https://github.com/Lokaltog/vim-powerline) 和 [Agnoster](https://gist.github.com/agnoster/3712874) themes 和 inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnoster](https://gist.github.com/agnoster/3712874) - Optimized for solarized terminal color schemes, shows `git` decorations, user@host, working directory, the previous command's exit status and whether you are running with root privileges. Requires a Powerline-compatible font.
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - 基于 [Agnoster](https://gist.github.com/agnoster/3712874), shows battery life, date & time, `git` status, current directory and user & host information.
* [akzsh](https://github.com/awkimball/akzsh) - 最适合深色终端主题，包括 `git` 装饰.
* [alarangeiras](https://github.com/alarangeiras/alarangeiras-zsh-theme/) - Minimalist theme with `git` status decorations.
* [ale](https://github.com/alepimentel/ale-zsh)  - 基于fino主题. 包括 `git`、`virtualenv` 和 `node` 状态装饰.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) - Minimalist ZSH theme with `git` status displayed.
* [alien](https://github.com/eendroroy/alien) - Powerline-esque ZSH theme that shows `git` decorations and the exit code of the last command. Faster than many other prompts because it determines the `git` decorations asynchronously in a background process.
* [almel](https://github.com/Ryooooooga/almel) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) , 用 Rust 编写. 包括 `git` 状态、user@host、最后一个命令退出状态和工作目录装饰
* [alpharized](https://github.com/NicoSantangelo/Alpharized) - Optimized to work with [solarized](http://ethanschoonover.com/solarized) dark terminals. It's a modified version of the [avit theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme).
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - 优雅舒适的阅读主题，基于 [Agnoster](https://gist.github.com/agnoster/3712874).
* [andy](https://github.com/andymcguinness/andys-theme) - Modified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme with better `git` support.
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) - Shows `git` information in the right hand prompt.
* [antoinechab](https://github.com/antoinechab/antoinechab-theme) - Includes `git` status, username, time and current directory decorations.
* [antsy](https://github.com/jeffmhubbard/antsy-zsh-theme) - 显示 `git` 分支和状态装饰、virtualenv、退出状态、作业计数和 vi 模式指示器.
* [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) - Shows `git` decorations, user, host, whether root, active Python virtual environment, current Ruby interpreter, visual and numeric status of the last command, power management status and time and date.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme) - Minimalistic theme without visual noise. Displays only the necessary information: current user, hostname, working directory, `git` branch if one exists. Looks great both with dark and white terminals.
* [aplos](https://github.com/sunquan1991/aplos) - Minimal ZSH prompt with working directory, `git` local info, `git` remote info, time and exit code.
* [apollo](https://github.com/mjrafferty/apollo-zsh-theme) - A heavily customizable, compatible and performant ZSH theme that uses modules to enable features.
* [apple (aramirol)](https://github.com/aramirol/apple-zsh-custom-themes) - 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme), includes `vcs` status decorations. Colors customizable by setting vars in your `.zshrc`.
* [apple (bjrowlett2)](https://github.com/bjrowlett2/apple-zsh-theme) - Minimalist theme with `git` status decorations.
* [arael](https://github.com/aknackd/zsh-themes) - 叉子 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [archie](https://github.com/dcavalcante/archie) - Arch Linux inspired ZSH 主题. Based on the [norm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) 主题.
* [arity](https://github.com/hybras/Arity-Zsh-Theme)  - Arity 是一个简单的主题，旨在提高可读性并一目了然. 包括路径和 `git` 装饰.
* [aronhoyer](https://github.com/aronhoyer/zsh-theme) - 带有右侧“git”状态装饰的极简主义主题.
* [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - 带有 `git` 装饰的最小 ZSH 主题.
* [asciigit](https://github.com/cemsbr/asciigit) - An ASCII-only theme for `git` users who don't want to use fonts with extra glyphs.
* [asq](https://github.com/AugustoQueiroz/asq-theme) - 基于 [theunraveler](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#theunraveler).
* [astral](https://github.com/xwmx/astral) - Theme for dark backgrounds with zen mode. Works well with the zsh-users [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) plugin.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - 基于`ys`和 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 主题.
* [async](https://github.com/mje-nz/zsh-themes) - 显示当前目录、`git` 状态、最后一个命令的返回值（如果有错误代码）、后台作业的数量、长时间运行的命令的执行时间、当前的 python virtualenv.
* [aub](https://github.com/FraSharp/aub) - 包括 `git` 和 `hg` 状态以及 `host` 中的 `username` 的装饰.
* [aterminal](https://github.com/guiferpa/aterminal) - 在提示符中显示 Nodejs、NPM、Docker、Go、Python、Elixir 和 Ruby 信息.
* [avil](https://github.com/avil13/avil-zsh-theme) - 带有 `git` 装饰的极简主义主题.
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) - 基于 oh-my-zsh [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) 主题，变化不大.
* [avit-mod](https://github.com/zlsun/avit-mod) - 修改版 oh-my-zsh&#39;s [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) 主题.
* [banana](https://github.com/sorcererxw/banana-zsh-theme) - Includes `git` status decorations and current directory.
* [bandit](https://github.com/Holger-Will/zsh_bandit) - Another Powerline variant.
* [bar (anki-code)](https://github.com/anki-code/bar-theme) - 极简主义设置 [p10k](https://github.com/romkatv/powerlevel10k).
* [bar (xp-bar)](https://github.com/xp-bar/zsh-bar-theme) - Includes username, host, pwd, `git` status decorations and  3x hour reminders to drink water.
* [barion](https://github.com/SEbbaDK/barion)  - 快速编译的提示，带有紧凑的 `git` 状态概览. 让人联想到电力线. 需要 [Crystal](https://crystal-lang.org/) to build.
* [bash](https://github.com/starseekist/bash-zsh-theme) - Looks like the default `bash` prompt.
* [bashi](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) theme and Pasquale D'Silva's [Saturn Terminal](https://github.com/psql/saturn-colors) 主题.
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - 修改版 [gitster](https://github.com/zimfw/gitster) 主题为 [ZIM](https://github.com/zimfw/zimfw).
* [bearable](https://github.com/JanmanX/bearable-zsh) - 适用于深色终端背景.
* [bedbugs](https://github.com/justino/zsh-theme-bedbugs) - 灵感来自 [Agnoster](https://gist.github.com/agnoster/3712874)，这个多行提示包括 `git` 状态信息、后台作业计数、工作目录、用户和主机名、Python virtualenv（如果存在）、最后一个命令的彩色返回值和 root/用户 sigil.
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - 灵感来自 [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme), but with beer icons.
* [bender](https://github.com/specious/bender) - 带有 git 集成的精美两行提示.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with unicode symbols baked in.
* [biraSkull](https://github.com/Shahryar-Pirooz/biraSkull.zsh-theme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), includes root status and `git` status decorations.
* [biradate](https://github.com/vemonet/zsh-theme-biradate) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme, but displays the date instead of the username in the prompt.
* [birame](https://github.com/maniat1k/birame) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [birav2](https://github.com/shahid64/birav2-theme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) . 包括 `git`、`rvm` 和 `virtualenv` 状态装饰.
* [bklyn](https://github.com/gporrata/bklyn-zsh) - Variant of [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) with customizations applied.
* [black-Void](https://github.com/black7375/BlaCk-Void-Zsh) - Includes account info, root user, using ssh, directory lotation, write permission, vcs info decorations.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) - 另一个 `git`-aware 主题.
* [blazux](https://github.com/blazux/omz-theme) - 包括 `git` 状态装饰和最后一个命令退出状态的笑脸/悲伤脸指示器.
* [blinks (max13ft)](https://github.com/max13fr/blinks.zsh-theme) - Adds mercurial support to oh-my-zsh's [blink](https://github.com/max13fr/blinks.zsh-theme) 主题.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) - Based on the existing theme [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme).
* [bliss](https://github.com/joshjon/bliss-zsh) - A delicate theme that injects color without overwhelming your workspace. Designed to be used with the [bliss iTerm](https://github.com/joshjon/bliss-iterm) 配色方案和 [bliss dircolors](https://github.com/joshjon/bliss-dircolors) . 包括 `git` 状态装饰.
* [blokkzh](https://github.com/KorvinSilver/blokkzh) - Theme based on oh-my-zsh's built in [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 主题. 需要支持 unicode 的字体.
* [blox](https://github.com/yardnsm/blox-zsh-theme) - A minimal and fast ZSH theme that shows you what you need. It consists of blocks: each block is shown inside a pair of \[square brackets\], and you can add blocks by simply creating a function.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - 最小的主题，显示 `git` 信息.
* [bluelines](https://github.com/apbarrero/bluelines) - Clear and blue theme.
* [bluo](https://github.com/varunpbardwaj/bluo) - 五颜六色的提示片段让人想起 [bullet-train](https://github.com/caiogondim/bullet-train.zsh) or [powerlevel10k](https://github.com/romkatv/powerlevel10k) . 包括 `git` 状态装饰.
* [bogo](https://github.com/cubasepp/zsh-bogo-theme) - 灵感来自 [zeta](https://github.com/skylerlee/zeta-zsh-theme) . 包括 `git` 和 ruby​​ 版本的装饰.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - Multiline theme, best on dark backgrounds.
* [bougenville](https://github.com/bougenville/zsh-theme) - Variant of [dallas](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dallas.zsh-theme).
* [bronze](https://github.com/reujab/bronze)  - 一个跨外壳可定制的类似电力线的提示，带有用 go 编写的图标. 需要 [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
* [brs](https://github.com/evenhold/brs-zsh-theme) - Displays the current song in the prompt with `audtool`.
* [bruh](https://github.com/haze/bruh) - 包括 `git` 状态装饰.
* [brunty](https://github.com/Brunty/omz-brunty) - 布鲁蒂主题.
* [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) - Inspired by the [powerline](https://github.com/Lokaltog/vim-powerline) 和 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 主题.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF color theme.
* [bubblegum](https://github.com/ice-bear-forever/bubblegum-zsh) - Minimalist bright pink theme with a triangular glyph and your working directory, nothing else—leaving you with the cleanest shell possible.
* [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) . 最适合搭配 [nerdfonts](https://github.com/ryanoasis/nerd-fonts).
* [bubblified (varaki)](https://github.com/varaki/bubblified-varaki.zsh-theme) - 基于 [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) . 生根时变色.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh) - Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH 主题，修改为只显示时间和目录.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - 简单、干净、漂亮的主题.
* [bureau-env](https://github.com/angus-lherrou/bureau-env) - Modification of the Oh-My-Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) 将 Python 虚拟环境标签添加到 `git` 块左侧的主题.
* [bureau-parrot](https://github.com/BenjaminGuzman/bureau-parrot) - 基于 [bureau](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme) . 包括 `git` 装饰.
* [bureau](https://github.com/isqua/bureau) - A clear and informative two-lined prompt. Includes git status optimized for large repositories.
* [buster](https://github.com/grantbuster/buster_zsh_theme) - Plays well with WSL2. Based loosely on Fox and Jonathan themes from oh-my-zsh.
* [cactus](https://github.com/welksonramos/cactus) - Minimalist theme with `git` status decorations.
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - Light version of the candy theme.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - 在提示中显示活动的 Python 版本和 `git` 装饰.
* [celestialorb](https://github.com/celestialorb/zsh-theme) - Powerline-inspired theme by @celestialorb. Includes `git` status decorations, Kubernetes cluster information (if any), current AWS profile and region, and  active virtualenv.
* [cf-ps1](https://github.com/mdan16/cf-ps1) - 显示当前的基础和组织和空间 [Cloud Foundry](https://www.cloudfoundry.org/) in your prompt.
* [ch4rli3](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) - 精益和简单的主题.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme)  - 基于索林. 显示 Java、Scala、Go、Node、Python 和 Ruby 的当前活动版本.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme)  - Oh-My-Zsh 的一个小巧而美丽的主题，没有任何多余的东西. 包括 `git` 状态装饰.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) - A ZSH prompt optimized for the [solarized](https://github.com/altercation/solarized) 黑暗的终端主题.
* [chello](https://github.com/Abdalla981/chello)  - 适用于深色背景. 依赖于取决于 [autojump](https://github.com/wting/autojump), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) 和 [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [chi](https://github.com/akinjide/chi) - A ZSH theme optimized for iTerm 2 users on macOS.
* [chill](https://github.com/JKerboeuf/chill.zsh-theme) - 具有当前工作目录、最后一个命令退出状态和 `git` 状态的装饰.
* [chinipage](https://github.com/andresemartinez/chinipage-zsh-theme)  - 包含 `git` 装饰的极简主义主题. 需要与电力线兼容的字体和 [git-prompt](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git-prompt) plugin.
* [chrisandrew.cl](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme)  - 包括 `git` 装饰. 需要与电力线兼容的终端字体.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - Shows timestamp, large line breaks, git branch and status.
* [clarity](https://github.com/nbitmage/clarity.zsh) - 专为简单性和可扩展性而设计.
* [classyTouchName](https://github.com/dylanroman03/classyTouchName) - Oh-my-zsh 主题灵感来自 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) . 在深色背景下效果更好. 包括 `git` 状态装饰.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - 带有 `git` 支持的最小、干净的主题.
* [clean (akz92)](https://github.com/akz92/clean) - Minimalist ZSH theme.
* [clean (brandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - A minimalist variant of [pure](https://github.com/sindresorhus/pure). Pure is not clean, clean is not pure.
* [clean (patr1ot)](https://github.com/Patr1ot/clean.zsh-theme) - 上游的分叉 [clean](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) with host information added.
* [cleansh](https://github.com/diegoos/cleansh)  - 极简主义，包括 `git`、Ruby、node 和 Python 版本状态装饰. 适用于标准字体.
* [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) - minimalist theme with `git`, nix-shell and virtualenv status decorations.
* [cloudy](https://github.com/Huvik/Cloudy) - Minimal cloudy ZSH theme.
* [clover](https://github.com/tzing/clover.zsh-theme) - 灵感来自 [zeta](https://github.com/skylerlee/zeta-zsh-theme) 和 [pure](https://github.com/sindresorhus/pure).
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - 配置文件 [cmder](http://cmder.net/) configured to work in quake mode with ZSH and a modified [Agnoster](https://gist.github.com/agnoster/3712874) 主题.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) - A ZSH theme that matches the theme of Cmder, a popular terminal emulator for windows.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) - 带有 `git` 扩展的 Cobalt 2 主题.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Codemachine theme.
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - 灵感来自 [bashi](https://github.com/eli-oat/bashi), 在你的提示中包含一个猴子和 `git` 信息.
* [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - 基于 agnoster，但对 vi 模式有一个正确提示，以电力线外观显示 `--INSERT--` 和 `--NORMAL--`.
* [coldark](https://github.com/ArmandPhilippot/coldark-zsh-theme) - A blue-grey theme designed for reading comfort. Includes `git` decorations.
* [collon](https://github.com/lambdalisue/collon.zsh) - Lightweight theme with `git` status decorations, cwd, time, host, exit status of last command. Does not require special fonts.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - 允许按主机提示着色，显示 `rvm`、`virtualenv` 和 `git` 信息.
* [common](https://github.com/jackharrisonsherlock/common) - A simple, clean and minimal prompt, displays current working directory, hostname, AWS vault role, background jobs, current SHA, exit code of last command, and `git` branch and status.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - 针对深色背景优化的色彩鲜艳的主题。
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) - 干净有效的 ZSH 主题，支持 git 和 npm.
* [cramin](https://github.com/FelipeCRamos/craminzsh) - Minimal interface with support for github plugins, based on [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [cryo](https://github.com/cryocaustik/cryo-zsh-theme) - A standalone clone of the original oh-my-zsh theme with date and time added.
* [crème fraîche](https://github.com/koenwoortman/creme-fraiche-zsh-theme) - 最适合轻终端背景，包括 `git` 和 `vi`-mode 状态装饰.
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 Powerline Vim 插件的带有可爱表情符号的 macOS oh-my-zsh shell 主题.
* [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) - 在深色背景下效果很好，有 `git` 状态装饰.
* [cypher-ruby](https://github.com/ston1x/cypher-ruby) - 如同 [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) 但包括活动的 Ruby 版本.
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) with [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) and the [agnoster](https://github.com/agnoster/agnoster-zsh-theme) theme in a container.
* [daily](https://github.com/ghlin/zsh-theme-daily) - 包括 `git` 和 `ssh` 状态装饰.
* [damino](https://github.com/njdom24/Damino-Zsh-Theme) - 带有“git”装饰的最小电力线主题.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) - 内容丰富、极简，最重要的是，以 X 战警为主题.
* [daniloheraclio](https://github.com/daniloheraclio/daniloheraclio-zsh-theme) 灵感来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题. 具有 `git` 和最后一个命令退出状态装饰. 需要 nerdfont 才能正确渲染.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - This version of the popular [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) theme has been enhanced with a near complete rewrite enabling modularity and a few new features.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - 基于`ys`和 [astro](https://github.com/iplaces/astro-zsh-theme) 主题.
* [dbern](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) - 包括电池状态和负载平均装饰.
* [delta (asavoy)](https://github.com/asavoy/delta-zsh-theme)  - 最小化 ZSH 主题以减少干扰. 包括一个 iTerm 颜色设置文件.
* [delta (dongri)](https://github.com/dongri/delta-zsh-theme) - 另一个带有嵌入式 `git` 状态的最小主题.
* [delta-prompt](https://github.com/cusxio/delta-prompt) - 一个最小的 ZSH 提示.
* [destiny](https://github.com/ja1dan/Destiny) - A simple, configurable ZSH prompt with no dependencies. Destiny has been tested on Linux, macOS and iOS.
* [devj121](https://github.com/DevJ121/devj121-zsh-theme) - Includes `git` decorations with branch glyphs.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) - A theme with an emphasis on the right side (hence the name) of the terminal.
* [dino](https://github.com/OdilonDamasceno/dino-zsh-theme) - Includes decorations for node, golang, flutter, lua, python & java, also includes `git` decorations. Requires nerdfonts.
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - Comes with custom LSCOLORS and LS_COLORS settings files, works with both dark and light terminal themes.
* [diy-ys](https://github.com/aprilnops/zsh-theme) - Variant of [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) without hostname or time.
* [dkniffin](https://github.com/dkniffin/zsh-theme) - Includes `ruby` version and `git` status.
* [dmx](https://github.com/domix/dmx.zsh-theme) - 针对深色终端窗口进行了优化.
* [doodleshell](https://github.com/cdodd/doodleshell-zsh-theme) - Minimalist theme, includes `git`, `terraform` and `aws` status decorations.
* [dp](https://github.com/davidparsson/zsh-dp-theme) - Low contrast theme that shows current git branch, if the repository is dirty and the value of `$PYENV_VERSION`.
* [dr4kk0nnys_v2](https://github.com/Dr4kk0nnys/Dr4kk0nnys_theme_ohmyzsh_v2/) - 适用于深色背景，包括 `git` 状态装饰.
* [dracula](https://github.com/dracula/zsh) - A dark theme for Atom, Alfred, Chrome DevTools, iTerm 2, Sublime Text, Textmate, Terminal.app, Vim, Xcode, and ZSH.
* [dragon (jeop10)](https://github.com/jeop10/dragon)  - 灵感来自 kali linux. 包括 `git` 状态和工作目录装饰.
* [dragon (sabertaximi)](https://github.com/sabertazimi/dragon-zsh-theme) - Minimalistic, includes `git` status information.
* [drkat](https://github.com/katrinaalaimo/drkat-zsh-theme) - 让人联想到 [Powerline](https://github.com/powerline/powerline). Includes directory, `git` status, and hostname decorations.
* [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) variant.
* [dtheme](https://github.com/OlukaDenis/DTheme) - Optimized for people using a solarized terminal color scheme and `git`. Works best with a unicode font.
* [duckster](https://github.com/ducky/duckster) - 一个叉子 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ZSH 主题更新鲜.
* [ducula](https://github.com/janjoswig/Ducula)  - 受德古拉项目的启发. 包括 `git` 状态装饰、用户名和主机名缩写、虚拟环境、当前工作目录、最后一个命令的返回状态和时间.
* [dustmod](https://github.com/bmihaila/dustmod) - Derived from the [dst](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) theme in oh-my-zsh.
* [dzhi](https://github.com/pentago/dzhi-zsh-theme) - 针对使用的人进行了优化 [Nord](https://www.nordtheme.com/) . 包括 `git` 状态装饰.
* [eckig](https://github.com/fouladi/eckig) - Minimalist theme with utf-8 icons. Includes `git` status decorations and a clock.
* [eggshausted](https://github.com/inutano/eggshausted) - A `git`-aware theme for people who are tired of getting errors.
* [eivmosn](https://github.com/eivmosn/eivmosn-omz) - Trimmed down variant of `ys` theme.
* [eleastic](https://github.com/jinseobhong/eleastic-zsh-theme) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme), optimized for solarized terminal theme, includes `git` status decorations. Requires powerline-compatible font.
* [elessar](https://github.com/fjpalacios/elessar-theme) - 基于 `git` 的主题 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) . 需要与电力线兼容的字体.
* [elm](https://github.com/gacallea/elm-zsh-theme) - Includes `git` status, user@host, date, time and path decorators.
* [elsa](https://github.com/faycito/elsa) - 包括根状态、密码和 `git` 状态装饰.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - Emoji flavored [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ohmyzsh/ohmyzsh) 主题.
* [emoji](https://github.com/masaakifuruki/emoji.zsh-theme) - 基于  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh theme with the `git` prompt symbols replaced with emoji for better clarity.
* [emojirussell](https://github.com/Bergiu/emojirussell) - 基于  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 主题，带有当前工作目录的状态装饰，最后一个命令退出状态，`git` 分支和状态.
* [endless-dog](https://github.com/qwelyt/endless-dog) - 模仿 grml-zsh-config 的 oh-my-zsh 兼容主题.
* [enlightenment](https://github.com/w33tmaricich/enlightenment) - Includes decorations for `git` status, `vi`-mode indicator, and the time for last command to execute.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - 在终端中占用大量空间.
* [erfan](https://github.com/ekm507/erfan-zsh-theme) - 的组合 [af-magic](https://github.com/和yfleming/oh-my-zsh) 和 [macovsky](https://github.com/championswimmer/oh-my-zsh/blob/master/themes/macovsky.zsh-theme) themes. Includes `git` 和 `virtualenv` status decorations.
* [eriner](https://github.com/zimfw/eriner) - 受电力线启发的 Zim 叉子 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 提示主题. 包括 `git` 状态装饰.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - 一个带有 `git` 信息的简单主题.
* [eucalyptus](https://github.com/relastle/eucalyptus) - 简约的 vi 模式用户的简单单行主题，灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory 和 current path.
* [excess](https://github.com/davydovanton/excess.zsh-theme) - 简单的 ZSH 颜色主题.
* [ez-pz](https://github.com/mangosmoothie/ez-pz) - Minimalist theme with `git` status decorations, inspired by [bureau](https://github.com/isqua/bureau).
* [fall](https://github.com/jottenlips/seasonal-zshthemes) - Minimalist theme with fall icons. Includes `git` status decorations.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) - 最小的 ZSH 提示，在深色背景下效果更好.
* [fdT2K](https://github.com/FDT2k/FDT2K-theme)- 基于 [agnoster](https://github.com/agnoster/agnoster-zsh-theme)，预设包括 virtualenv、最后命令状态、`nvm`、`docker machine` 和 `git`、`hg` 和 `bzr` 状态装饰.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme)  - 干净、简单、兼容且有意义. 在 ANSI 颜色下在 Linux、Unix 和 Windows 上进行了测试.
* [filthy](https://github.com/molovo/filthy) - 令人作呕的干净 ZSH 提示.
* [fish](https://github.com/Raniconduh/zshfish)  - ZSH 主题让人想起默认的鱼壳主题. 包括 `git` 状态装饰.
* [fishy-lite](https://github.com/sudorook/fishy-lite) - Fork of the original [fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy)  oh-my-zsh 中的主题，删除了许多无关内容以提高加载速度. 包括一个电池表和 `git` 状态显示，可以在提示的右侧启用.
* [fishy2](https://github.com/akinjide/fishy2) - ZSH 主题灵感来自 [original fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy).
* [fizzy](https://github.com/Brokenhammer72/fizzy) - Minimalist prompt, includes `git` status decorations.
* [fluent-git](https://github.com/RobertKozak/fluent-git) - Displays time of last command execution, error code, hostname, username, `git` status, kubernetes cluster and namespace, path and ssh connection status.
* [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) - 自定义设置 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) . 包括 `git` 状态装饰.
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - 包括最后一条命令的状态、`git` 信息和当前目录.
* [frank](https://github.com/ronmackley/frank-theme)  - Frank 言简意赅，在一行中简洁而易读地显示信息. 弗兰克坚持事实，只在重要的时候告诉你额外的事情.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - 叉子 [terminal-party](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) 主题.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - A theme based on the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh-theme.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - Red version of the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) theme from oh-my-zsh.
* [fritz](https://github.com/fritzccc/fritz-zsh-theme)  - 适用于深色背景. 包括 `git` 状态装饰.
* [frlo](https://github.com/fiorillo/frlo) - Uses your computer's hostname to come up with a (hopefully) unique three-color theme to display in your prompt, so you know at a glance which machine you're logged into.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - 支持 `git` 和 `svn` 的彩色两行主题.
* [furio](https://github.com/hectorpalmatellez/furio-theme) - Fork of the [Cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) oh-my-zsh theme. with different colors and emojis.
* [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) - Colorful theme, works better on a dark background.
* [gaia](https://github.com/gcaracuel/gaia.zsh-theme) - 原来是一个叉子 [Bureau](https://github.com/isqua/bureau) adds new virtual environments info to the prompt: Kubernetess, virtualenv, rbenv and Java versions. Includes git status integration.
* [gal](https://github.com/x6r/gal) - gal 基于 [gallois](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme).
* [garden](https://github.com/fecat233/garden) - 在深色终端背景下效果更好，包括 `git` 状态装饰.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto 在您需要的时候提示您需要的信息.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires `rvm` & `git` plugins.
* [gbt](https://github.com/jtyr/gbt)  - Go Bullet Train 是一个非常可定制的提示生成器，灵感来自 Bullet Train，运行速度更快. 包括许多不同状态的汽车.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - 将 oh-my-zsh gentoo 主题拆分为一个单独的 repo，供非 omz 用户使用.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) - 将主机信息添加到 [geometry](https://github.com/geometry-zsh/geometry) 主题.
* [geometry](https://github.com/geometry-zsh/geometry) - 一个最小的 ZSH 主题，可以将任何功能添加到左侧提示符或（异步）右侧提示符中.
* [ghoti](https://github.com/lonr/ghoti) - Mimics the `fish-shell` default prompt. Includes `git` decorations.
* [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) - 灵感来自 [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme), includes `git` decorations, IP address, host and path.
* [gimbo](https://github.com/gimbo/gimbo.zsh-theme) - A variant of [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) with more features, a little eye candy and context-sensitive extra lines. Includes `git` status decorations, history number, username/hostname context, directory status, status of last command if it failed, and the Python virtualenv name if present.
* [gimme](https://github.com/nralbrecht/gimmezsh)  - 带有 `git` 集成的 ZSH 的简单主题. 灵感来自 [gitsome](https://github.com/mtully/gitsome) 主题.
* [girazz](https://github.com/mdentremont/girazz) - A modification to the gnzh theme which adds `vi` mode to the right prompt.
* [git-prompt (awgn)](https://github.com/awgn/git-prompt) - `bash`、`zsh` 和 `fish` 的快速 `git` 提示.
* [git-prompt (olivierverdier)](https://github.com/olivierverdier/zsh-git-prompt) - Displays information about the current `git` repository. In particular the branch name, difference with remote branch, number of files staged or changed, etc.
* [git-prompt (woefe)](https://github.com/woefe/git-prompt.zsh) - 受 Olivier Verdier 启发的 ZSH 的快速、可定制、纯 shell、异步 Git 提示 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) and very similar to the "Informative VCS" prompt of fish shell.
* [git-prompt-kit](https://github.com/olets/git-prompt-kit) - A configurable set of components for creating feature rich, high performance Git-aware zsh prompts (aka themes) with minimal coding.
* [git-simple](https://github.com/ZakharEl/git-simple-theme) - Simple theme that includes detailed `git` status decorations.
* [gitsome](https://github.com/mtully/gitsome) - 带有 `git` 信息的超级简单提示，针对 [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) 配色方案.
* [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) - Shows command and `git` status decorations.
* [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) - When in a `git` repo, it shows the location from the `git` repository root folder. When not in a `git` repo, it shows the path relative to home, `~`.
* [gitster (zimfw)](https://github.com/zimfw/gitster) - shashankmehta 的 Zim 叉子 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 提示主题
* [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) - 从原来的分叉 [gitster](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) 主题.
* [gk3000](https://github.com/gk3000/gk3000-oh-my-zsh-theme) - 包括 `git` 状态装饰和当前目录的完整路径.
* [glimmer](https://github.com/martnu/glimmer) - 包括 `git` 分支、时间和 user@host.
* [gndx](https://github.com/gndx/gndx-zsh-theme) - Includes `git` status, hostname, directory and last command exit status decorations.
* [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) - Customization of [gnzh.zsh-theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 来自 oh-my-zsh.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) - iTerm 2 和 ZSH 的主题，包括 `git` 装饰、user@host、路径和日期.
* [gops](https://github.com/noxer/gops) - Fast powerline-like prompt. Includes `git` status, current directory, root status decorations.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - Simple yet informative theme that includes `git` decorations and the return status of the last command.
* [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) - 极简主义，包括 `git` 状态装饰.
* [grs](https://github.com/gersontpc/zsh-theme-grs) - Includes `git` status decorations, user id and working directory.
* [gruvbox (hgaiser)](https://github.com/hgaiser/gruvbox-zsh) - 设置颜色 [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [gruvbox (sbugzu)](https://github.com/sbugzu/gruvbox-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874), uses the same colors from the [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [guezwhoz](https://github.com/guesswhozzz/guezwhoz-zshell) - 极简主义，包括 `git` 状态装饰.
* [guri](https://github.com/victorfsf/guri) - 一个简单快速的 Oh-My-Zsh 主题，基于 [Pure](https://github.com/sindresorhus/pure)'s design.
* [hackersaurus](https://github.com/bhilburn/hackersaurus) - A theme with `git` status and exit code of last command run embedded in the prompt. Related to [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) - 带有 `git` 装饰的极简主义主题.
* [halil](https://github.com/5m0k3r/zsh-themes) - oh-my-zsh 的分叉 [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) 主题.
* [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme)  - 一个简单的主题，第一个字符是花（hana），即花的汉字. 这个主题的灵感来自一个名为 DSA Hana 的键帽集. 这与 [hana atom](https://github.com/arturoalviar/hana-matcha-syntax) theme. Includes `git` status decorations.
* [handy](https://github.com/hanleylee/handy)  - 多彩和轻量级的主题. 显示 root 状态、`git` 状态、当前目录和 `user@hostname` 装饰.
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) - Shows `git` branch and status, last command exit code, last command execution time if more than `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`.
* [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) - Based on oxide, includes `git` status decorations and current user/host information.
* [haribo](https://github.com/haribo/omz-haribo-theme) - Simple `git` status + timestamp in prompt.
* [hcompact](https://github.com/fusion809/zsh-theme) - 显示时间、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [headline](https://github.com/Moarram/headline-zsh-theme) - 响应式 ZSH 主题，具有 Git 状态信息和提示上方的彩色线条.
* [heart](https://github.com/gko/heart) - Heart themed prompt for light backgrounds.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - Simple, no-nonsense and clean, with support for `git` and return codes.
* [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - 基于 [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau)，添加了 `git` 状态装饰和 `npm` 状态.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hematite](https://github.com/bigdave/hematite) - 极简主义促销，试图仅显示在给定时间非常有用的状态装饰.
* [hexagon](https://github.com/diogoazevedos/hexagon) - Minimalist zsh theme based on [geometry](https://github.com/geometry-zsh/geometry).
* [hfulldate](https://github.com/fusion809/zsh-theme) - Displays time, date, OS (including distro if on Linux), directory and whether running as root.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - 灵感来自 robbyrussell 主题 + ssh 连接状态提示.
* [hina](https://github.com/ucpr/hina) - 用 `golang` 编写，包括 `git` 状态装饰和 kubernetes 上下文.
* [hip-fellow](https://github.com/haitaim/hip-fellow) - Includes `git` status decorations and works with standard fonts.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - A variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [home](https://github.com/sheerun/home) - Pretty and short one-line theme that makes you feel at home.
* [hometown](https://github.com/olets/hometown-prompt) - A feature rich, high performance `git`-aware ZSH theme with segments for the user, host, time, the current working directory and its parent, and detailed full Git status within a Git repo.
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - Honukai theme and colors for oh-my-zsh and iTerm 2.
* [horizontal](https://github.com/nuimk/horizontal) - Two line prompt with a horizontal separator.
* [hornix](https://github.com/fusion809/zsh-theme) - Displays time & date, OS (including distro if on Linux), directory and whether running as root.
* [horse-sh](https://github.com/emileswarts/horse-sh) - A very minimal brown/red ZSH theme.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - 简单干净，包括最后执行的命令的返回码.
* [hug](https://github.com/xxninjabunnyxx/hug-zsh) <i>- When you&#39;re working and need a hug.</i> <b>- 当你工作并需要一个拥抱时。</b> <i>Includes `git` status.</i><b>包括 `git` 状态。</b>
* [humbled](https://github.com/saravanabalagi/zsh-theme-humbled) - A clean and humble theme with support for `condaenv`, `virtualenv` and `git` status decorations left aligned with the working directory in bold.
* [hydrogen](https://github.com/xylous/hydrogen) - A simple multiline zsh theme. It shows username, hostname, current directory and `git` status decorations.
* [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) - Designed to work with the hyper terminal theme, includes `git` status decorations.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) - 让您全面了解您正在处理的分支和存储库的状态，而不会弄乱您的终端.
* [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX) - Modified iGeek theme. Works with macOS out-of the box, includes `git` status decorations.
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - 在深色背景上效果很好.
* [ice](https://github.com/Lenart12/ice.zsh-theme) - Very lightly modified [bureau](https://github.com/isqua/bureau) theme combined with [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [icicle](https://github.com/JamesConlan96/Icicle) - 包括 `git` 状态装饰，以及是否以 root 身份运行.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) - 一个超级快乐的电力线风格，`git`-aware **prezto only** 主题.
* [igorsilva](https://github.com/igor9silva/zsh-theme) - 显示当前目录、可自定义的分隔符、当前分支、`git` 状态.
* [iguanidae](https://github.com/btd1337/iguanidae-zsh-theme) - 包括 `git`、`nvm` 和 `venv` 装饰.
* [illustion](https://github.com/shabane/illusion) - Includes username, current working directory, git status and last command status decorators.
* [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) - 叉子 [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) 间距改进和更新的图标. 包括 `git` 状态信息.
* [imp](https://github.com/igormp/Imp) - 基于 [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) 并针对深色背景进行了优化.
* [infernus](https://github.com/jshiell/infernus-zsh-theme) - Minimalist theme, better on dark backgrounds.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) - Clean theme that shows `git` status, background jobs, remote host, and other information.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - 的扩展 [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) 使用电力线字体的主题.
* [itg](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy 的主题.
* [ivy](https://github.com/ivyhjk/ohmyzsh-theme-ivy) - Works well on dark backgrounds. Includes user@host, `git` status and time decorators. Based on the [obraun](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#obraun) 主题.
* [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme)  - 基于精致和 ys 主题，包括 `git` 状态装饰. 包括一个可选的 iterm2 颜色方案.
* [jake](https://github.com/JakeHuneau/Jake.zsh-theme) - 如果分支有未推送的更改，则显示时间、当前目录和 `git` 分支信息，包括分支名称和红色 +.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - Optimized for dark backgrounds, includes `git` status and `rvm` status.
* [jc](https://github.com/jclementex/jc-zsh-theme) - 对于深色终端背景，包括 `git` 状态信息.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - Loosely based on the ys theme.
* [jerome](https://github.com/jeromescuggs/jerome-theme) - Colorful theme based on the [dieter](https://github.com/jeromescuggs/jerome-theme) 主题，但带有黄色主机名. 包括 `git` 装饰.
* [jhleeeme](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) - Includes `git` and python virtualenv status decorations, user, pwd,time and system name.
* [jon](https://github.com/Jon-Schneider/jon.zsh-theme) - A simplified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) with the colors of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - 灵感来自 [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme), 包括 `git` 状态.
* [jovial](https://github.com/zthxxx/jovial) - Shows host, user, path, development environment, `git` branch, which python venv is active.
* [jpegleg](https://github.com/jpegleg/zshrc) - Similar to dark blood theme, includes timestamp and `git` decorations.
* [js-magic](https://github.com/JSextonn/js-magic) - 简化版 [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme). Includes current working directory and `git` status decorations.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - 极简主义提示.
* [just-another](https://github.com/supertassu/another-theme) - 只是另一个主题，当您 sshed 到另一台机器时使用主机名.
* [just-around-the-corner](https://github.com/DevinLeamy/just-around-the-corner) - Counts down the days until Christmas. Includes `git` status decorations.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter)  - 带有 `git`、`svn`、`npm`、`rvm` 和网络意识的电力线风格主题. 需要与电力线兼容的终端字体.
* [jyumpp](https://github.com/Jyumpp/jyumpp-zsh-theme) - Configuration file and installer for Powerlevel 10K.
* [kali](https://github.com/h4ck3r0/kali-theme) - 包括 `git` 装饰.
* [karu](https://github.com/zaari/karu) - 极简单行 ZSH 提示.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) - 包含其他主题的一些功能的主题.
* [kenton](https://github.com/notnek/zsh-theme) - 针对深色背景进行了优化，包括 `git` 状态信息.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) - Colorful theme, includes iTerm 2 color schemes.
* [kgzsh](https://github.com/Kashugoyal/kgzsh) - Includes `git` status deorations, works well on darker backgrounds.
* [kido](https://github.com/KidoThunder/kido-zsh-theme) - Based on `ys` and `robbyrussell` themes. Includes decorators for the exit code of the last command run, python virtualenv and VCS status.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - 基于 Fishy 主题，但显示完整路径而不是缩写目录，并且仅在 `ssh` 会话和 docker 容器中显示 user@machine.
* [kirkdawson](https://github.com/kdawson133/KirkDawson)  - 受电力线启发. 包括 `git` 状态、最后命令退出状态、用户@主机名、工作目录以及用户是否以 root 身份运行的提示装饰.
* [kiss](https://github.com/rileytwo/kiss)  - 用于 oh-my-zsh、VSCode、iTerm2、Neovim 和 RStudio 的简单主题. 包括 `git` 状态装饰.
* [kketcham](https://github.com/prototype27/kketcham) - `git` 信息上带有漂亮颜色的主题.
* [klassiker](https://github.com/mrdotx/zsh-theme) - Very minimal theme with `git` decorations.
* [korittg](https://github.com/dkorittki/korittg-zsh-theme)  - 简约但内容丰富. 包括 `git` 状态、当前目录和 `kubectl` 上下文和命名空间的装饰.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme) - Best for dark backgrounds. Includes `git` status decorations.
* [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - Two line theme designed for dark terminals, has `git` decorations.
* [krak3n](https://github.com/krak3n/zsh-theme) - Shows golang version and the current `git` branch.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) - A dark theme for ZSH.
* [kube](https://github.com/tigerjz32/kube-zsh-theme) - 基于 [macos-terminal](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal), includes `kubectl` context. Has time, directory, and `git` status decorations.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme)  - Agnoster 前叉针对日晒终端进行了优化. 需要与电力线兼容的字体.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) - Colorful theme with `git` and `hg` status information, ability to add host-specific colors to hostname.
* [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme) - A simple theme with the first character being 九(kyuu), the number 9. The primary color is blue with a magenta accent. Includes `git` status decorations.
* [lagune](https://github.com/noplay/lagune) - A minimal ZSH theme.
* [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) - 灵感来自 robbyrussell [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) theme. Includes `git` status decorations.
* [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) - A ZSH theme optimized for `git` users who use unicode-compatible fonts and terminal applications.
* [lambda-blazinggit](https://github.com/zalefin/lambda-blazinggit)  - 包括快速、详细的 `git` 信息. 需要书呆子字体和 [gitstatus](https://github.com/romkatv/gitstatus) plugin.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - 包含“git”信息的极简提示.
* [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) - 基于 lambda 的简单主题，带有 `git` 状态和 virtualenv 信息.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - 一个简单的 ZSH 主题，针对 `git` 使用进行了优化.
* [lambda-p](https://github.com/paimanb和i/lambda-p) - Inspired by the [lambda mod](https://github.com/halfo/lambda-mod-zsh-theme) 和 [Lambda V](https://github.com/vkaracic/lambdav-zsh-theme) 主题. 包括 `git` 状态装饰.
* [lambda-pure](https://github.com/marszall87/lambda-pure) - A minimal ZSH theme, based on Pure, with added NodeJS version.
* [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) - A combination of the Lambda and Fishy themes, includes `git` status decorations.
* [lambda-zen](https://github.com/seamile/lambda-zen) - 灵感来自 [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) 带有图形 `git` 状态装饰.
* [lambder](https://github.com/avillen/zsh-theme-lambder) - 包括 `git` 状态装饰，最适合深色终端主题.
* [laniksj](https://github.com/LanikSJ/laniksj-zsh-theme)  - 在深色背景下效果最佳. 基于伟大的`ys`主题和 [Honukai ZSH Theme](https://github.com/oskarkrawczyk/honukai-iterm-zsh). Shows root status and `git` status decorations.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - Optimized for dark terminals, has variants for local and remote systems.
* [leafia](https://github.com/Ghostrick/leafia-prompt) - 显示 `git` 状态信息的多叶 prezto 主题.
* [lean](https://github.com/miekg/lean) - 灵感来自 [pure](https://github.com/sindresorhus/pure). Includes `git` status and background job decorations.
* [lemon](https://github.com/carlosvitr/lemon_zsh) - Many beautiful colors for you to enjoy. done with care and patience. Includes `git` status and ruby version decorations.
* [leon](https://github.com/prince-an/Leon_zshTheme) - Works well on light background. Includes `git` status, time, username@host, working directory and last command exit status decorations.
* [leverage](https://github.com/gschnall/leverage) - 基于 [minimal](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme), 使用颜色和额外的 `¬` 字符，以更好地区分命令行提示符和输出.
* [lewis](https://github.com/lewisflude/oh-my-lewis)  - 黑色、白色和红色主题. 显示 `git` 状态信息.
* [lightbulb](https://github.com/lightbulb703/lightbulb-zsh-theme) - Includes decorations for kernel, OS version, uptime and `git`.
* [lighthaus](https://github.com/lighthaus-theme/zsh) - 一个提示，恭维 [Lighthaus](https://github.com/lighthaus-theme/lighthaus) theme. Shows `git` information, github/gitlab logo and shows changes as and when they occur.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) - Minimalist theme, best on a dark terminal background.
* [lilith](https://github.com/aknackd/zsh-themes) - Modification of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) 和 [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [lime](https://github.com/yous/lime) - 简单且易于定制的 ZSH 主题.
* [limpide](https://github.com/shooteram/limpide) - 修改版 [miloshadzic](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) 显示父目录和当前目录的主题.
* [linuxer](https://github.com/patrick330602/linuxer) - 灵感来自 Yaris Alex Gutierrez  [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh), Yad Smood 的 `ys`, 和 [Bureau](https://github.com/isqua/bureau) 主题.
* [linuxero](https://github.com/andreshincapier/linuxero) - Minimalist. Includes decorations for root status, current directory, `git` status, current ruby rvm environment and current python virtualenv.
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt with useful information when you need it. It shows you what you need when you need it. You will notice what changes when it changes, saving time and frustration.
* [lish](https://github.com/bashelled/lish) - A casual theme. No roughness, just smooth. Includes `git`, user@host, last command exit status, current directory, current time and root status decorators.
* [liver](https://github.com/RenoirTan/liver.zsh-theme) - Colorful, includes `git` status, user, host, current and relative path to the current repository root decorations.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) - 挑剔的美洲驼使用的极简主义主题.
* [logico](https://github.com/logico/logico-zsh-theme) - Has `git` decorations. Shows remote status and indicator for vi-mode.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - 基于 Sindre Sorhus 纯主题的德克萨斯主题.
* [longsilvern](https://github.com/long263/longsilvern-zsh-theme) - 包括 `git` 和紧凑的 `pwd` 装饰.
* [lorond](https://github.com/lorond/zsh-lorond/) - Compact version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) . 包括 `git` 状态，适用于标准字体.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme) - Variant of lambda-mod theme. Has `git` decorations, requires a powerline-compatible terminal font.
* [luke](https://github.com/xueguangl23/luke_zsh_theme) - Includes `git` decorations. Based on the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) 哦，我的 zsh 主题.
* [lukerandall-extended](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) - Extended version of the [lukerandall](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) 主题. 包括 `git` 状态的装饰和最后一次命令运行的状态.
* [lunachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/lunachar.zsh-theme) - 极简主义主题.
* [macos](https://github.com/alejandromume/macos-zsh-theme) - 包括 `git` 状态装饰.
* [mad](https://github.com/MartinWie/ohmyzsh-theme-mad) - 包括 `git` 状态和最后命令执行时间装饰.
* [magicmace](https://github.com/zimfw/magicmace) - Inspired by xero's ZSH prompt and [eriner's prompt](https://github.com/zimfw/eriner) . 包括活动 python `venv` 的状态代码、最后一个命令的退出状态、缩短的工作目录、`git` 状态装饰.
* [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN's magico theme.
* [maivana](https://github.com/nylo-andry/zsh-themes) - Includes `kubectl` context, `git` status decorations.
* [materialshell](https://github.com/carloscuesta/materialshell) - A [material design](https://material.io/guidelines/style/color.html) theme for your shell with a good contrast and color pops at the important parts. Designed to be easy on the eyes.
* [matrix](https://github.com/pot-code/matrix-zsh-theme) - Variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 风格看起来像 Matrix 电影三部曲中的东西. 包括 `git` 状态装饰.
* [matter](https://github.com/mrobillard/matter-zsh-theme) - Shows `git` status, AWS vault role, background jobs, exit code of last command & hostname.
* [mau](https://github.com/vichargrave/mau)  - 带有猫扭曲的 ZSH 主题. 包括 `git` 状态装饰. 基于 [kphoen](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kphoen.zsh-theme) 和 [smt](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/smt.zsh-theme) 主题.
* [mbolis](https://github.com/mbolis/mbolis-zsh-theme) - Includes `git` decorations, changes prompt color if root user, active jobs, and [jenv](https://github.com/jenv/jenv) integration.
* [mdmini](https://github.com/MarioDena/MDmini) - 包括 `git` 和 `ssh` 状态装饰.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt)  - 包含键盘模式、所有权信息和其他上下文信息的最大化提示，以 λ 作为提示字符. 需要 [hooks](https://github.com/willghatch/zsh-hooks) plugin.
* [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) - Includes `git` status decorations, shows exit code of last command if nonzero.
* [mexassi](https://github.com/Mexassi/mexassi-zsh-theme)  - 检查 `/sys/class/power_supply` 文件夹以确定系统是安装在笔记本电脑还是台式机上. 读取电池百分比 grepping acpi 命令并在提示符中显示. 包括 `git` 装饰.
* [mh-fzj](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) - 包括 `rvm` 和 `git` 状态装饰.
* [michaelpass](https://github.com/michaelpass/michaelpass.zsh-theme) - POSIX 友好的跨平台 [alanpeabody](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) mod w/ convenient timestamps and full git/ruby support.
* [midin](https://github.com/xlshiz/midin) - 适用于深色终端背景，包括 `git` 状态装饰.
* [mike-was-here](https://github.com/leguim-repo/mike-was-here-theme/) - 极简主义，包括 `git` 状态装饰.
* [milight](https://github.com/frodoslaw/milight-zsh) - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
* [min](https://github.com/andrepolischuk/min) - 一个简约的 ZSH 提示.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - 考虑到空间的 ZSH 主题.
* [mini-simple](https://github.com/ysl2/mini-simple-zsh-prompt)  - 极简主义者. 包括 `vcs` 状态装饰.
* [minima (Brolly0204)](https://github.com/Brolly0204/zsh-minima) - Includes `git`, `node`, `golang`, `yarn`, `php`, `docker` and `python` status decorations.
* [minima (ednikolenko)](https://github.com/ednikolenko/minima) - A minimal ZSH theme with `git`, `docker`, `go`, `node`, `npm`, `python` and other indicators. Uses unicode characters for some markers.
* [minimal (5amu)](https://github.com/5amu/minimal-prompt) - Minimal prompt, uses nerdfonts. Includes `git` and `vpn` status decorations.
* [minimal (casalinovalerio)](https://github.com/casalinovalerio/minimal-prompt) - Minimal prompt, includes `git` and vpn status decorations.
* [minimal (glsorre)](https://github.com/glsorre/minimal/) - 最小的异步 ZSH 主题优化用于 [Fira Code](https://github.com/tonsky/FiraCode) font and the [Solarized Light](https://ethanschoonover.com/solarized) 终端主题.
* [minimal (subnixr)](https://github.com/subnixr/minimal) - 最小但功能丰富的主题.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) - 黑暗终端的主题，包括右侧提示中的 `git` 装饰.
* [minimal2](https://github.com/PatTheMav/minimal2)  - 一个最小且可扩展的 ZSH 主题. 分叉自 [subnixr's original](https://github.com/subnixr/minimal) and adapted for [Zimfw](https://github.com/zimfw/zimfw).
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) - 灵感来自 oh-my-zsh 的 kolo 主题.
* [mira](https://github.com/mbStavola/mira) - A modified [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) with time info and a simplified start prompt.
* [mirage](https://github.com/robin-pfeiffer/ohmyzsh-mirage-theme/) - 包括 `git` 状态、最后命令退出代码、`sudo` 时间戳文件是否存在以及当前活动的 Python 虚拟环境的提示装饰.
* [miramare](https://github.com/franbach/oh-my-deepin-miramare)  - 包括 `git` 状态装饰. 最适合搭配 [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
* [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs' ZSH theme.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - 针对深色背景进行了优化.
* [mnml](https://github.com/mnml-theme/prompt) - Minimal theme with `git` status decorations.
* [mochi2](https://github.com/mochidaz/zsh-themes)  - 极简主义主题. 包括 `git` 和 `hg` 状态装饰.
* [mochi](https://github.com/mochidaz/zsh-themes) - Simple theme, designed to resemble rust main function. Includes `git` and `hg` status decorations.
* [moderno](https://github.com/obrassard/moderno-zsh) - 一个简单而现代的 ZSH 主题，灵感来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme)  Oh-My-ZSH 的主题. 包括 `git` 状态装饰.
* [modesty](https://github.com/saravanabalagi/zsh-theme-modesty) - A clean and modest ZSH theme with `condaenv`, `virtualenv` and `git` status decorations displayed neatly right aligned.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874).
* [momoyo](https://github.com/momoyo-droid/momoyo-zsh-theme)  - 让人想起电力线. 包括 `git` 状态、用户名和工作目录的装饰.
* [moonline](https://github.com/kagamilove0707/moonline.zsh) - Minimal but easily extensible prompt.
* [moux](https://github.com/gagbo/moux) - 适用于深色终端背景，包括 `RPROMPT` 中的 `git` 装饰.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - 提供有关您所在存储库的有用信息（在您的提示中）.它目前适用于 [Git](https://git-scm.com/) 和 [Mercurial](https://www.mercurial-scm.org/), under [ZSH](https://en.wikipedia.org/wiki/Zsh) 也 [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [multiline](https://github.com/jan-auer/zsh-multiline) - 基于电力线风格的主题 [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [muslim](https://github.com/nksoff/muslim) - A simple minimal ZSH prompt theme.
* [musy](https://github.com/THaGKI9/musy-zsh-theme)  - 灵感来自缪斯主题. 包括 `git` 状态装饰.
* [my-hl2](https://github.com/liamm91/my-hl2) - Includes virtualenv, `git` status and directory decorations. Based on omz's [half-life](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/half-life.zsh-theme) 主题.
* [myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia's myzsh theme.
* [mzt](https://github.com/honbey/mzt) - Sets up `LS_COLORS`, colorizes `diff` and includes `git` status and current working directory decorations.
* [nanofish](https://github.com/tweekmonster/nanofish) - Adds fish-style directory prompt to nanotech theme.
* [nbrylevv](https://github.com/nbrylevv/nbrylevv-zsh-theme) - Minimalist theme with text `git` status decorations.
* [nctu](https://github.com/leovincentseles/nctu.zsh-theme) - Lightweight theme with an emphasis on speed. Includes `git` status decorations.
* [neewbie](https://github.com/neewbee/neewbee.zsh-theme)  - 带有 `git` 装饰的最小主题. 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell).
* [neon-potato](https://github.com/algosuna/neon-potato) - Colorful and minimalist theme. Includes `git` decorations.
* [neon](https://github.com/sahariko/neon) - 带有 `git` 装饰的漂亮且最小的 ZSH 主题.
* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - 带有书呆子字体的 ZSH 提示主题.
* [nescalante](https://github.com/nescalante/zsh-theme) - 针对深色终端背景进行了优化，包括 `git` 装饰.
* [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) - 包括 `git` 装饰和 `vi` 模式指示器.
* [newt](https://github.com/softmoth/zsh-prompt-newt) - Fat & fast theme – beautiful inside and out, styled segments done right. Extremely customizable, includes `git`, username, execution time, directory, background jobs and edit mode decorations.
* [newton](https://github.com/sebastienfilion/zsh.newton) - 包括 `git` 状态和外部 IP 地址装饰.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - A very basic theme which just features an macOS bike icon.
* [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - 色彩丰富，显示 `git` 状态装饰.
* [nikitakot](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme)  - 小而简单的 oh-my-zsh 主题. 显示当前目录和后面的 2 个目录，`git` 和 `nodejs` 状态装饰.
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - Based on af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - A simple oh-my-zsh theme.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - Minimalist ZSH theme with `git` status decorations.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) - oh-my-zsh 的节点主题，为了便于与其他插件管理器一起使用而进行了拆分.
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - Based on the ys theme, with added NodeJS version (from NVM plugin).
* [noon](https://github.com/silky/noon.zsh-theme) - 有浅色和深色的变体，显示 `git` 信息.
* [nord](https://github.com/TyWR/Nord-zsh) - Includes `git` status decorations and displays the active conda environment.
* [normanius](https://github.com/normanius/normanius-zsh-theme) - 源自 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [nothing](https://github.com/eendroroy/nothing) - 闪电般快速且非常简单，因为它几乎没有任何内容.
* [nox](https://github.com/kbrsh/nox) - Dark theme, displays the current working directory and git status.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme)  - 一个干净、无干扰且以“git”为重点的开发主题. 显示相对于 `git` 根的路径（或 ~ 当在 `git` 存储库之外时）、自上次提交以来的时间、当前 SHA、分支和分支状态.
* [nunorc](https://github.com/nunorc/nunorc.zsh-theme)  - 极简主义主题，适用于深色背景. 包括 `git`、`mercurial` 和 `svn` satus 装饰.
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - prezto 和 oh-my-zsh 的简单主题.
* [nuts](https://github.com/rafaelsq/nuts.zsh-theme) - Minimalist theme, includes `git` status decorations and time.
* [oblong](https://github.com/Ansimorph/oblong) - 简单的 `bash` 启发主题，基于 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 和 [basher](https://gitlab.com/Spriithy/basher). Includes status decorations to show if user is root, the exit status of last comm和 run, `git` branch 和 its clean/dirty status.
* [odie](https://github.com/masterodie/zsh-theme-odie/)  - 在深色背景上效果很好. 包括 `git` 状态、python virtualenv 和 `vi`-mode 状态装饰.
* [odin](https://github.com/tylerreckart/odin) - Odin is a `git`-flavored ZSH theme.
* [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) - 带有 `git` 装饰的多行主题.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - 对 bash 和 ZSH 的自以为是的提示.
* [oh-my-posh](https://ohmyposh.dev/)  - 不是 ZSH 特定的，但非常好，可以与 ZSH 一起使用. 允许您对所有 shell 中的提示使用相同的配置.
* [oh-my-via](https://github.com/badouralix/oh-my-via) - Theme for ZSH which mainly forks the historical theme used on VIA servers.
* [ohmypc](https://github.com/joselpadronc/OhMyPC) - Works well with dark terminal windows. Includes `git` decorations.
* [om](https://github.com/sirshikher/zsh-om) - Minimal theme, works with dark backgrounds, includes `git` status decorations.
* [omszt](https://github.com/MU001999/omszt) - 带有 `git` 装饰的极简主义主题.
* [omuse](https://github.com/ouuan/omuse-zsh-theme) - 基于 Oh-My-ZSH  [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) . 具有 `git` 状态、时间、绝对密码、RAM 使用量、最后一个命令使用的时间和最后一个命令退出状态的装饰.
* [owi](https://github.com/owitech/zsh-theme/) - Minimalist theme with `git` status decorations.
* [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) - Includes `git` status and virtualenv information.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - 简约和黑暗的 ZSH 主题.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme)  OZ0NO - 让我们呼吸干净的 ZSH.
* [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) - 一个主题 [powerlevel10k](https://github.com/romkatv/powerlevel10k) 提示强调简单性，同时仍然可以获取重要信息.
* [pad](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme.
* [page](https://github.com/SLIB53/page-zsh-theme)  - 一个带有 VCS 支持的简单主题. 提示显示当前工作目录的 1 级、分支和一个颜色编码的弯曲粗箭头.
* [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) - 允许显示主机信息，包括 `git` 分支装饰.
* [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) - 在提示中使用图标显示详细的 `git` 状态信息.
* [panda](https://github.com/davymai/oh-my-zsh-panda-theme) - Includes `git` and `root` status decorations. Best on a dark background.
* [papercolor](https://github.com/erikschreier/PaperColor-themes) - Color scheme for ZSH, `vim` and `tmux`. Includes `git` status decorations.
* [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion)  - 包括 `git` 状态装饰，以毫秒为单位的命令运行时间. 在 macOS 上需要 coreutils.
* [pastel](https://github.com/iboyperson/pastel) - 一个受启发的 ZSH 主题 [sugar-free](https://github.com/cbrock/sugar-free) . 包括 `git` 装饰.
* [pecodez](https://github.com/pecodez/pecodez-zsh-theme) - Optimized for dark terminals. Has decorators for `snyk` version, `node` version, AWS profile, kubernetes context and `git` status.
* [pentesters](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) - Modified version of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme for pentesters which includes the date, time, and IP address for pentest logging.
* [persi](https://github.com/persiliao/persi-zsh-theme) - Includes `git` decorations. Works with both light and dark backgrounds.
* [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) - 本着精神的最小主题 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 和纯壳主题.
* [phantomk](https://github.com/phantomk/phantomk.zsh-theme) - Colorful theme, includes go version, node version and `git` status.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - A clean and simple theme for ZSH inspired and forked from the [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) 主题.
* [pi](https://github.com/tobyjamesthomas/pi) - 带有 `git` 状态装饰的简约主题.
* [piboy](https://github.com/sflems/piboy-zsh-theme) - A simple and elegant multi-line theme for ZSH. Includes a colourized timestamp, `git` & syntax highlighting, and elevated root theme.
* [plain-ui](https://github.com/purveshpatel511/plain-ui) - 极简主义，但包括 `git` 状态装饰.
* [plain](https://github.com/jimeh/plain.zsh-theme) - 一个简单的 ZSH 主题，显示基本的 `git` 信息.
* [planet](https://github.com/borb/planet-zsh) - 精简版 [steef](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) from [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) - 简单、简洁的主题.
* [plantyhoe](https://github.com/totoroot/plantyhoe.zsh-theme) - Minimalist theme based on a love of plants and apples. Includes `git` status decorations.
* [platypus](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) - 显示工作目录、上一条命令的返回状态和 `git` 当前分支.
* [polyglot](https://github.com/agkozak/polyglot) - `zsh`、`bash`、`ksh​​93`、`mksh`、`pdksh`、`dash`和busybox`ash`的动态提示，它使用基本的ASCII符号（和颜色，如果可能的话）来显示用户名，无论是本地还是远程 `ssh` 会话、缩写路径、`git` 分支和状态、最后一个命令的退出状态（如果非零）、使用 `virtualenv`、`venv`、`pipenv`、` 创建的任何虚拟环境诗歌`或`conda`.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM 的基本 oh-my-zsh 自定义主题.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - Programmer's theme with `git` status, ruby version and project path.
* [powerbash](https://github.com/erikschreier/powerbash-zsh) - Works well with dark terminal backgrounds, includes `git` status decorations.
* [powerless](https://github.com/martinrotter/powerless) - Tiny & simple pure ZSH prompt inspired by powerline.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - 快速重新实现 [powerlevel9k](https://github.com/bhilburn/powerlevel9k)  ZSH 主题. 可以用作 powerlevel9k 的直接替代品，当给定相同的配置选项时，它将生成相同的提示，只是速度更快.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k 是 ZSH 的主题，它使用 [Powerline Fonts](https://github.com/powerline/fonts). It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen)， 和 [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 附加组件 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - A two-line version of powerline: one for information, one for input.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme)  - 另一种电力线主题. 可以很好地配置，但至少需要一个支持 256 色的终端，并带有与电力线兼容的终端字体.
* [powerline (syui)](https://github.com/syui/powerline.zsh) - 一个 `git` 感知电力线主题.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
* [powerline-go](https://github.com/justjanne/powerline-go)  - 一个漂亮实用的低延迟提示，用 golang 编写. 包括 `git` 和 `hg` 状态装饰、上次命令运行的退出状态、当前 Python 虚拟环境、是否在 [nix](https://nixos.org/) 外壳，并且易于扩展.
* [powerline-hs](https://github.com/rdnetto/powerline-hs) - A [Powerline](https://github.com/powerline/powerline) 用 Haskell 编写的克隆. 它比原始实现要快得多，并且使 shell 的响应速度明显更快.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - 在 Ruby 中创建，使用电力线字符来模拟具有有用信息的药丸.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell)  - 漂亮而有用的 Bash、ZSH、Fish 和 tcsh 提示生成器. 包括 `git`、`svn`、`fossil` 和 `hg` 装饰、Python virtualenv 信息和最后一个命令退出状态.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - A [powerline](https://github.com/Lokaltog/vim-powerline) - 类似于 Bash、ZSH 和 Fish 的提示. 显示有关 git/svn/hg/fossil 分支的重要详细信息，并且易于自定义/扩展.
* [powerline-train](https://github.com/sherubthakur/powerline-train) - 电力线变体.
* [powerline](https://github.com/carlcarl/powerline-zsh) - A [Powerline](https://github.com/Lokaltog/vim-powerline)- 类似提示，基于 [powerline-bash](https://github.com/milkbikis/powerline-bash) . 显示 virtualenv、`git` 状态信息和最后一个命令运行的退出代码.
* [powerzeesh](https://github.com/sevaho/Powerzeesh)  - 基于电力线的 ZSH 主题. 它旨在简化，仅在相关时显示信息，并针对速度和外观进行了优化. 灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) - A collection of themes for Sublime Text, Terminal, iTerm 2 and ZSH.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) - 为黑暗终端主题优化的主题.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - Prezto port of oh-my-zsh's cloud prompt.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda 主题（用于 prezto）.
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
* [probe](https://github.com/probe2k/probe_zsh) - 包括 `git` 状态装饰.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight ZSH prompt, based on the powerline font from the popular eponymous `vim` plugin, which works well for a dark background.
* [prompt](https://github.com/nathanblair/prompt) - A lightweight prompt consistent across `sh`, `dash`, `ash`, `zsh`, and `pwsh`. Includes `git` status decorations.
* [prompt_j2](https://github.com/malinoskj2/prompt_j2) - 具有动态退出状态指示器，可以动态更改为两行以显示上下文.
* [promptus](https://github.com/willeccles/promptus) - Simple, minimalist and configurable shell prompt program in C which can be used to make your prompt the same on any shell. Includes exit code and working directory decorations.
* [pronto](https://github.com/jthat/zsh-pronto) - Simple and fast theme with `git` decorations and timing information.
* [ps1.py](https://github.com/jwodder/ps1.py) - 具有 `git` 状态、截断目录、`chroot` 和 `virtualenv` 提示装饰.
* [pskfyi](https://github.com/pskfyi/zsh-theme) - 基于 [lambda](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#lambda). Themed for ubuntu but easily tweaked.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - 易于定制，受 [spaceship](https://github.com/denysdovhan/spaceship-prompt).
* [pure-agnoster](https://github.com/yourfin/pure-agnoster)  - pure 和 agnoster 的混搭. 具有 `git` 装饰，适用于深色和浅色终端背景.
* [pure](https://github.com/sindresorhus/pure)  - 一个漂亮、最小和快速的 ZSH 提示. 包括 `git` 状态装饰，如果最后一个命令失败，提示变为红色，在远程会话或容器中时的用户名和主机装饰，以及进程运行时的当前文件夹和命令.
* [purify (banminkyoz)](https://github.com/banminkyoz/purify) - 一个简单、快速和酷炫的提示.
* [purify (kyoz)](https://github.com/kyoz/purify) - A clean and vibrant theme, best on dark backgrounds. Includes `git` status decorations.
* [purity](https://github.com/petermbenjamin/purity) - Inspired by robbyrussell theme and the [pure](https://github.com/sindresorhus/pure) 迅速的.
* [purs](https://github.com/xcambar/purs) - 快速 [pure](https://github.com/sindresorhus/pure)-inspired prompt written in [Rust](https://www.rust-lang.org/).
* [pustelto](https://github.com/Pustelto/shell_theme) - 色彩缤纷的主题灵感来自 [Spaceship](https://github.com/denysdovhan/spaceship-prompt) theme, includes `git` decorations.
* [qi3ber2](https://github.com/nichus/qi3ber2)  - 一个黑暗的多线主题. 包括`git`，最后一个命令装饰器的平均负载和退出代码.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon)  - 针对深色背景进行了优化，包括 `git` 信息. 主题 repo 包括 iTerm 2 和终端颜色设置.
* [quewui](https://github.com/kauefontes/oh-my-quewui) - Simple and clean theme optimized for dark terminal themes. Includes status decorations for the current time, user, directory and `git` status.
* [r3nic1e](https://github.com/r3nic1e/r3nic1e) - [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) variant with battery status, `git/hg` status, time, kubernetes context and namespace, non-zero exit code of last command and date decorations. Requires Powerline font.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - Based on af-magic and posh-git.
* [radium](https://github.com/dimitardimitrov/radium) - 专为黑暗终端设计，（与 [Solarized](https://github.com/altercation/solarized) iTerm 2 theme) (prezto).
* [radius](https://github.com/erikcc02/radius-zsh-theme) - 包括 `git` 状态装饰，包括 [desk](https://github.com/jamesob/desk) 支持.
* [rafiki](https://github.com/akabiru/rafiki-zsh) - 将表情符号添加到您的 ZSH 终端.
* [ramiel](https://github.com/aknackd/zsh-themes) - Fork of the [node](https://github.com/skuridin/oh-my-zsh-node-theme).
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - 基于 [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) 和“robbyrussell”主题.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - 随机表情符号.
* [ranger-zoxide](https://github.com/fdw/ranger-zoxide) - 添加 [zoxide](https://github.com/ajeetdsouza/zoxide) support to the [ranger](https://github.com/ranger/ranger) 控制台文件管理器.
* [raspberrysh](https://github.com/MaxMalinowski/raspberrysh) - 包括`git`、python、时间、当前主机和路径装饰.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) - Simple and colorful theme with `git` status decorations.
* [raz](https://github.com/razman786/ohmyzsh-theme-raz) - Minimal prompt, includes `git` status decorations.
* [rb](https://github.com/rberenguel/rb-zsh-theme) - 基于电力线风格的 ZSH 主题 [Agnoster](https://gist.github.com/agnoster/3712874) ，针对`git`和solarized终端进行了优化. 需要与电力线兼容的字体.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - Optimized for solarized terminal color schemes, includes `git` status decorations.
* [redline](https://github.com/DrissTM/redline.zsh-theme) - Minimalist theme. Includes `git` status, time, user.
* [reggae](https://github.com/nmercado1986/zsh-reggae-theme) - Compresses a lot of information into the prompt with color-coded status decorations.
* [rei](https://github.com/arturoalviar/rei-zsh-theme) - A simple theme with the first character being 零(rei), the number 0. Includes `git` status decorations.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), 优化为 [solarized](https://github.com/altercation/solarized) 终端主题.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - 基于 Sorin 的 Prezto ZSH 主题，使用表情符号来跟踪 GIT 上下文.
* [rho](https://github.com/andrejreznik/rho-zsh-theme) - 极简主义主题.
* [ribbon](https://github.com/tactlessfish/ribbon-prompt)  - 让人想起电力线. 包括 Python `virtualenv` 装饰器.
* [river](https://github.com/revir/river-zsh-config) - 带有 `git` 信息的深色主题.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - Based on ideas from the the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题和项目 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - Decorates the `robbyrussell` theme with output to indicate a **WIP** commit.
* [robbyrussell-fullpath](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) - 原本 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 在提示中带有完整路径.
* [rocket](https://github.com/Alexandresl/rocket-zsh-theme) - Minimalist theme, includes `git` and `hg` status decoration.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - 一个黑暗的主题.
* [roundy](https://github.com/nullxception/roundy)  - 快速、可爱和圆润的主题. 包括 `git` 装饰. 需要 nerd 字体和支持 unicode 的终端应用程序.
* [roz](https://github.com/rozNum/roz-zsh-theme) - Minimalist. Includes `git` status decorations, best on a darker background.
* [rs](https://github.com/rogeliosamuel621/rs-zsh-theme) - Includes `git` decorations. Requires unicode capable terminal.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) - 针对深色背景进行了优化.
* [rummik](https://github.com/rummik/zsh-theme)  - @rummik 的主题. 支持 [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), 和 `git` 提示中的状态信息.
* [russtone](https://github.com/russtone/prompt-russtone) - 灵感来自 [pure](https://github.com/sindresorhus/pure) 和 [sorin](https://github.com/sorin-ionescu/prezto) . 包括 `git` 状态装饰.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - 色彩丰富的主题，包括 `git` 装饰和当前目录.
* [rzh](https://github.com/patwhatev/rzh) - Theme with git states indicated by emojis.
* [s1ck94](https://github.com/zimfw/s1ck94) - Fork of the (first deprecated, now extinct) minimal prompt by S1cK94. Shows whether user is root, background job status, vi-mode, exit status of last command, and `git` status decorations.
* [s7c](https://github.com/Samega7Cattac/s7c.zsh-theme) - Works well with dark backgrounds. Includes `git` status decorations.
* [samshell](https://github.com/samuelb/samshell) - A minimalist zsh theme with `git`, kubernetes and python virtualenv decorations.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - Includes `git` status decorations, works well on a dark terminal background.
* [saturn](https://github.com/gantoreno/saturn-prompt) - A soft & minimalistic prompt for those who love space and want to have a bit of it on their terminal, featuring cool emojis & highly customizable prompt elements (such as icons, colors, time format, and more).
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) - Shows `git` status decorations, user@host information, the exit status of last command, and whether running as root.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - 当使用 `:sh` 命令时，显示 `vim` 是否在后台运行.
* [scythe](https://github.com/kostoskistefan/scythe) - Powerline-reminiscent theme. Includes `git`, last command exit status and directory decorations.
* [sdkman](https://github.com/matthieusb/zsh-sdkman) - Add tab completions for [sdkman](https://sdkman.io/).
* [seashell](https://github.com/jottenlips/seasonal-zshthemes)  - 带有海洋灵感的表情符号装饰的最小主题. 包括 `git` 状态装饰.
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - This theme uses many special unicode characters to be fancy, but it may cause some problems without well supported fonts.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - Inspired by the dieter theme, uses color-coding to provide information.
* [senpai](https://github.com/hiroru/senpai-zsh)  - 为 Devops 清理提示主题. 包括 `git` 状态信息、kubernetes 上下文、AWS 配置文件、GCP 项目和 Azure 活动云.
* [sepshell](https://github.com/sepehr/sepshell) - Clean and minimal ZSH theme based on the old lost taybalt theme, with `git` bisecting/merging/rebasing modes and configurable prompt symbols.
* [serious](https://github.com/oliversandli/serious-zsh-theme) - 包括命令退出状态和 `git` 状态装饰.
* [seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - 一个简单的 omz 兼容主题，带有相应的 iTerm 2 配色方案.
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - An evolution of lean prompt which itself is a rewrite of pure.
* [shadow](https://github.com/agentshadow/shadow-zsh-theme) - Includes `git` status, directory, host name, username and time decorations.
* [shayan](https://github.com/shayanh/shayan-zsh-theme) - 带有 `git` 状态装饰的简单主题.
* [shelby](https://github.com/athul/shelby) - Fast, lightweight and minimal prompt written in pure `golang`. Includes decorations for last command exit status, `git` status and the current working directory.
* [shellder](https://github.com/simnalamburt/shellder) - Minimal theme with git branch display. Requires a Powerline-compatible font.
* [shichi](https://github.com/arturoalviar/shichi-zsh-theme)  - 一个简单的主题，第一个字符是七（shichi/nana），数字 7.原色是红色，带有黄色调. 包括 `git` 状态装饰.
* [shini](https://github.com/bashelled/shini)  - 一个小小的主题，只是大声喊叫. 包括目录、用户名、主机名、时间和 `git` 装饰.
* [shirnschall](https://github.com/shirnschall/shirnschall-zsh-theme) - 包括 `git` 状态和 `user@hostname` 装饰.
* [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) - Forked from [sixlive](https://github.com/sixlive/sixlive-zsh-theme). Has `git` decorations.
* [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 主题. 包括 `git` 和 `hg` 状态装饰.
* [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) - 包括 `git` 装饰.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - Simple theme which displays current directory and git information.
* [shtr0m](https://github.com/kyle-pollock/shtr0m) - 包括 `git` 状态装饰.
* [siegerts](https://github.com/siegerts/zsh-theme) - Includes `git` status decorations in right prompt.
* [silver](https://github.com/reujab/silver) - A cross-shell customizable powerline-like prompt heavily inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) . 更快的生锈端口 [bronze](https://github.com/reujab/bronze) . 需要 [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) . 非常可配置，包括 `git` 状态装饰.
* [simpalt](https://github.com/m-lima/simpalt) - An information-rich small-footprint theme for ZSH based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [simple (daopengz)](https://github.com/DaopengZ/simple-zsh-theme) - Works well with both light and dark terminal themes. Includes `vcs`, `username` and `path` decorations.
* [simple (pavdmyt)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - 基于极简主义主题 [robbyrussel](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 在 iTerm 的窗口标题栏中嵌入 `git` 状态信息，而不是在提示中使用空格.
* [simple (savecoders)](https://github.com/Savecoders/simpleTheme-zsh-theme) - 带有 `git`、`username` 和执行状态装饰的简单而简约的主题.
* [simple (tourcoder)](https://github.com/tourcoder/simple.zsh-theme) - Minimalist prompt, includes `git` status decorations.
* [simple (yhiraki)](https://github.com/yhiraki/zsh-simple-prompt) - 最小提示，不需要特殊字体.
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - Powerline-inspired simple theme with `git` decorations.
* [simple-git](https://github.com/BazaJayGee66/simple-git-theme) - 极简主义主题灵感来自 [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) . 包括 `git` 装饰.
* [simple-yet-beautiful](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme)  - 极简主义主题. 包括 `git` 状态和 `user@host` 提示装饰.
* [simplezsh](https://github.com/fr0zn/simplezsh) - Minimal theme with `git` info display.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme)  - k-kinzal 的 sinon 主题. 包括 `git` 状态装饰.
* [sit](https://github.com/svensen/sit.zsh-theme) - Minimalist theme with `git`, command exit status and path decorations.
* [sixlive](https://github.com/sixlive/sixlive-zsh-theme) - This theme has a unique directory listing. When inside a `git` project, the directory display is scoped to the current repository root.
* [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9 的 ZSH 主题.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Theme collection for Atom, Prism and ZSH inspired by Skeletor from He-Man and the Masters of the Universe.
* [skill](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - Optimized for a dark terminal, displays `git` status decorations.
* [skull](https://github.com/tahadostifam/skull-zsh) - Includes `git` status, python virtual environment and ruby `rvm` status decorations.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH 主题灵感来自 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 和 [odin](https://github.com/tylerreckart/odin).
* [slick](https://github.com/nbari/slick) - Inspired by the [pure](https://github.com/sindresorhus/pure), [purs](https://github.com/xcambar/purs) 和 [zsh-efgit-prompt](https://github.com/ericfreese/zsh-efgit-prompt). Requires `cargo` for installation.
* [slimline](https://github.com/mengelbrecht/slimline)  - 最小、快速和优雅的 ZSH 提示. 在正确的时间显示正确的信息.
* [sm](https://github.com/blyndusk/sm-theme)  **Simplist** 和 **Minimalist** 主题，适用于您的 **favorite** 终端. 包括 `git` 状态装饰.
* [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) - A variant of the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme in [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - A prompt with happy and sad faces.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme)  - 受老式爱好启发的简约 ZSH 主题. 没有冗长的噱头，没有表情符号，没有烦躁的微调器，也没有其他视觉噪音. 具有明暗模式.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - 日晒电力线变体.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) - Solarized powerline-style theme for ZSH.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) - 对 robbyrussell 的 oh-my-zsh 主题进行颜色修复 [solarized](https://github.com/altercation/solarized) 终端.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) - 带有 `git`、`nvm`、rvm/rbenv/chruby、python、`ssh` 和其他有用状态指示器的主题.
* [spowerline](https://mbauhardt.github.io/spowerline/) - 用 scala 编写，灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), [tmux](https://tmux.github.io) powerline、vim powerline 和 vim 状态插件.
* [spyrhoo](https://github.com/FajarKim/spyrhoo-zsh-theme) - Includes time, `git` and current directory decorations.
* [squanchy](https://github.com/gabrielecanepa/zsh-custom/tree/master/themes)  - 极简主义主题. 包括 `git`、`node` 和 `rbenv` 状态装饰.
* [ssfprompt](https://github.com/hugoh/zsh-ssfprompt) - Simple, slim, fast. Includes `ssh`, virtualenv and vcs decorations.
* [staples](https://github.com/dersam/staples) - Based on bureau, displays user@host if connected through SSH.
* [starboy](https://github.com/prdpx7/Starboy) - 一个简单的 ZSH 主题.
* [starship](https://starship.rs/) - 最小，快速，高度可定制.
* [statusline](https://github.com/el1t/statusline) - A responsive ZSH theme that provides informational segments when you need them.
* [steef (danihodovic)](https://github.com/danihodovic/steeef)  - ZSH steeef 主题作为独立存储库. 这个 repo 背后的目的是避免在使用 steeef 主题时依赖 oh-my-zsh.  Antibody 等 ZSH 插件管理器可以使用主题，而无需使用 oh-my-zsh.
* [steef (zimfw)](https://github.com/zimfw/steeef) - A customizable version of [steeef's](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) 主题.
* [stellachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/stellachar.zsh-theme) - 最小，粉彩.
* [sublime](https://github.com/pjmp/sublime) - A sublime, clean, minimalistic ZSH theme with `git` status decorations.
* [sugar-free](https://github.com/cbrock/sugar-free) - 基于 [Pure](https://github.com/sindresorhus/pure) 和 [C和y](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/c和y.zsh-theme) 主题.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme) - Includes `git` status decorations. Works better on dark terminal backgrounds.
* [sulfurium](https://github.com/Sulfurium/zsh-theme) - The official ZSH theme of sulfuriumOS.
* [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) - 如同 [sunrise](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) 但包括活动的 Ruby 版本.
* [superkolo](https://github.com/Minipada/superkolo) - 添加日期和返回状态到 [kolo](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) 主题.
* [susi](https://github.com/carcruz/susi-zsh-iterm) - 包括 `git` 状态装饰和随附的 iTerm2 配色方案.
* [svs](https://github.com/SvS30/svs-theme) - Clean and distraction free theme with `git` status and current path decorations.
* [sy](https://github.com/ttttmr/sy-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), 包括 `git` 状态装饰.
* [t2er](https://github.com/t2er/t2er-zsh-theme) - 带有 `git` 装饰的极简主义主题.
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - 针对深色背景优化的最小 ZSH 主题.
* [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) - Includes `git` status decorations and conda/virtualenv status.
* [termux](https://github.com/rooted-cyber/Termux-zsh-theme) - 极简主义主题.
* [termuxer](https://github.com/patrick330602/termuxer) - 主题灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和linuxer.
* [the-time-lord](https://github.com/jhwhite/the-time-lord) - 基于的主题 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - Colorful theme with `git` status.
* [theta-async](https://github.com/jesec/zsh_theme_theta-async) - 异步版本 [theta](https://github.com/eendroroy/theta). Includes vcs status information.
* [theta](https://github.com/eendroroy/theta)  - 包括 `git` 和 `hg` 状态装饰. 还有 java、python、ruby、node、go 和 elixir 版本信息.
* [theto](https://github.com/heyvito/theto-zsh-theme)  - 简单的主题. 需求 [Nerd Fonts](https://nerdfonts.com/), includes `vi`-mode status and `git` decorations.
* [thetraveler](https://github.com/bassopenguin/thetraveler) - Inspired by theunraveler, uses symbols to display `git` status.
* [thnikk](https://github.com/thnikk/zsh-theme-thnikk) - A minimal version of the [spaceship](https://github.com/denysdovhan/spaceship-prompt) 主题.
* [thyme (chenhao-ye)](https://github.com/chenhao-ye/thyme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme)， 和 [bullet-train](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme).
* [thyme (kawamurakazushi)](https://github.com/kawamurakazushi/thyme) - 带有 `git` 状态装饰的简单主题.
* [toledo](https://github.com/mmatongo/toledo) - Quick minimalist theme with `git` status decorations.
* [tonni4](https://github.com/AndreyPuzanov/tonni4-zsh-theme) - Includes time and `git` status decorators.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh) - Includes `git` information; best on dark backgrounds.
* [tq](https://github.com/kitian616/tq-zsh-theme) - Displays `git` status, time, requires a Powerline font.
* [traffic](https://github.com/fcce/traffic-zsh-theme) - A dark theme for ZSH.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH.
* [trinity](https://github.com/de-luca/Trinity) - A simple theme based on [geometry](https://github.com/geometry-zsh/geometry) . 包括 `git` 装饰.
* [tron](https://github.com/iDoTron/tron-zsh-theme) - 包括 `git` 状态、工作目录、时间、user@host 和最后一个命令装饰的返回状态.
* [tsotra](https://github.com/nylo-andry/zsh-themes) - 极简主题，包括 `git` 状态装饰、k8s 上下文和 `rvm` 状态.
* [turs](https://github.com/eikendev/turs) - Fast, minimal [Purs](https://github.com/xcambar/purs)-inspired prompt.
* [tvline](https://github.com/thvitt/tvline) - Derived from the [agnoster](https://gist.github.com/agnoster/3712874) 主题，添加电力线字体增强功能.
* [twilight](https://github.com/Henryws/twilight-prompt) - 极简主义，但包括最后一个命令退出状态、`git` 状态和`user@hostname` 装饰.
* [type0](https://github.com/MikereDD/type0_zsh-theme) - 灵感来自 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) 通过 yarisgutierrez. 包括 `git` 装饰.
* [typewritten](https://github.com/reobin/typewritten) - Minimal and informative theme that leaves room for what's important. Does asynchronous `git` decoration updates for speed.
* [ubunly](https://github.com/alejandromume/ubunly-zsh-theme)  - 模仿 Kali Linux 控制台. 注意 - 这个主题还重新绑定了很多键并设置了一些主题应该不理会的 ZSH 选项.
* [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) - 模仿默认的 Debian/Ubuntu `bash` 提示符。
* [ubuntu-with-vitamins](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) - Mimics the default Ubuntu prompt, but with `git` decorations.
* [ubuntu](https://github.com/janstuemmel/zsh-ubuntu-theme) - Minimal theme, includes `git` status decorations.
* [ultimate](https://github.com/b4b4r07/ultimate) - Minimalist theme with `git` indicator, vim mode indicator and shortened path.
* [unicorn](https://github.com/juliuscaesar/unicorn) - Inspired by the [Wild Cherry](https://github.com/mashaal/wild-cherry) 主题. 有表情符号`git`状态装饰.
* [unit-1](https://github.com/nerdbude/Unit-1) - Minimalist theme with ITWTB colors.
* [vanan](https://github.com/avano/vanan-zsh-theme) - Minimalist theme with `git` information for dark terminals.
* [vercel](https://github.com/vercel/zsh-theme) - Minimalist theme with `git` status decorations.
* [vertepommes](https://github.com/TheRojam/vertepommes-theme) - Based on ys. Includes vcs status, username and current directory decorations.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - 从主题/mgutz.zsh-theme 修改.与 a 一起使用时看起来很棒 [Solarized](https://github.com/altercation/solarized) 配色方案.
* [vitesse](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) - Inspired by VS Code's [Vitesse](https://github.com/antfu/vscode-theme-vitesse) theme. Includes `git` status decorations.
* [vulcan](https://github.com/Bruceboy/vulcan-zsh-theme) - Minimal theme reminiscent of the default `bash` theme. Includes `git` decorations.
* [wade](https://github.com/wadehammes/wade.zsh-theme) - 流行的 ZSH 主题的混搭 [Agnoster](https://gist.github.com/agnoster/3712874) 和 [Fishy](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme)，有一些视觉上的调整.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) - 基于0532主题.
* [whale](https://github.com/whalesea520/whale-zsh-theme) - Fast reimplementation of the whale theme.
* [whales](https://github.com/lbergelson/zsh_whales_theme) - 包括 `git` 状态、java 版本、最后命令返回状态和目录的装饰器.
* [wild-cherry](https://github.com/mashaal/wild-cherry) - ZSH、iTerm 2、Sublime、Atom 和 Mou 的童话主题主题.
* [wkentaro](https://github.com/wkentaro/wkentaro.zsh-theme) - A simple theme for Python users. Includes virtualenv and `git` status decorators.
* [work-line](https://github.com/afnizarnur/work-line) - 带有漂亮表情符号的主题.
* [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) - 包括`git`状态装饰、工作目录、最后一个命令的退出状态和当前`virtualenv`.
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme)  - 旨在在您需要时向您展示所需信息的主题.  `wynwyn` 从默认主题 `avit` 和优秀 [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xavi](https://github.com/onthedock/xavi.zsh-theme) - Modified version of the [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 带有 `git` 状态和当前目录的表情符号装饰的主题.
* [xlk-simple](https://github.com/xuelingkang/xlk-simple-zsh-theme) - 带有 `git` 装饰的简单主题.
* [xm](https://github.com/Shiaoming/xm) - Theme for dark terminals. Has `git` decorations.
* [xor](https://github.com/xor3n/xor-zsh-theme) - Self described as minimalistic and 'feature-poor', includes `git` decorations.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - An oh-my-zsh shell theme based on the Jreese theme plugin.
* [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme)  - 快速、简单和流线型的主题. 最适合搭配 [tmux](https://github.com/tmux/tmux/wiki) 和 [vim-airline](https://github.com/vim-airline/vim-airline).
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - Shows the current git commit's shortened hash and message.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme)  - 带有行分隔提示的最小主题. 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题.
* [yazpt](https://github.com/jakshin/yazpt) - A clean, fast, good-looking ZSH prompt theme that thoughtfully incorporates Git/Subversion/TFVC status info, integrates with popular plugin managers like Oh My Zsh, and is straightforward to customize and extend.
* [yechen](https://github.com/liyechen/yechen.zsh-theme) - Minimalist theme with `git` status decorations.
* [yeet](https://github.com/jeetelongname/Yeet-theme) - Minimalist prompt with `git` status decorations.
* [yindev](https://github.com/menyinch/yindev-zsh-theme)  - `gndx` 的变体. 包括 `git` 状态和当前目录的装饰.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - Modified from [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) 主题并针对深色背景进行了优化.
* [ys (cristiancavalli)](https://github.com/cristiancavalli/ys-zsh-custom-theme) - 干净、简单、兼容和有意义的主题，适用于深色背景.
* [ys (tinyRatP)](https://github.com/tinyRatP/ys) - Variant of [ys](https://gist.github.com/ysmood/6110461).
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme)  - `ys` 变体，支持使用大型集群的批处理提交系统. 支持 Slurm、LSF/IBM Spectrum LSF 和 PBS.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - Simple ZSH theme with `git` status information.
* [ysr](https://github.com/raykle/ysr-zsh-theme)  - 基于`ys`. 包括 `git` 状态装饰.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - A dark optimized ZSH theme.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - Includes conda and venv status.
* [yz50](https://github.com/lacanlale/yz50-zsh) - 多彩，基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 和 [crunch](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) 主题. 包括 `git` 状态装饰.
* [z4rr3t](https://github.com/inimicus/z4rr3t) - 基于sindresorhus&#39; [pure](https://github.com/sindresorhus/pure) 主题.
* [zcraft](https://github.com/cpea2506/zcraft) - Minimalist theme with decorations for `git` status, last command exit status and the time taken by the last command.
* [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme) 以塞尔达为灵感的主题. 包括 `git` 状态装饰.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - 定制版 oh-my-zsh [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) 随着善变的支持和其他变化.
* [zemoji](https://github.com/therzka/zemoji) - 基于 [wild-cherry](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ https://github.com/mashaal/wild-cherry/tree/master/zsh). Includes exit status, `virtualenv`, `nvm`, `rvm` and `git` status decorations.
* [zero](https://github.com/arlimus/zero.zsh) - Zero's theme & plugin. Has variants for both light and dark terminal backgrounds.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - 在深色背景下效果最佳，包括 `git` 状态装饰.
* [zerocake](https://github.com/ZeroPoke/ZeroCake.zsh-theme) - Works better on dark brackgrounds.
* [zest](https://github.com/hash-bang/zsh-theme-zest)  - ZSH 的功能主题. 被影响 [zsh2000](https://github.com/consolemaverick/zsh2000), [agnoster](https://gist.github.com/agnoster/3712874) 和 [powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) 主题.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) - Shows username, `git` status information, machine name, the current working directory and success/fail status of last command.
* [zinc](https://gitlab.com/robobenklein/zinc) - A blazing-fast, pure ZSH, mixed asynchronous powerline prompt that's easily extensible and extremely configurable.
* [zlambda](https://github.com/wdhg/zlambda) - Minimalist, includes `git` decorations without special font requirements.
* [zodiac](https://github.com/adamalsen/zsh-zodiac) - 包括与当前年份对应的动物表情符号.
* [zprompts](https://github.com/z-shell/zprompts) - 使用原始“zsh”主题子系统的主题（提示）.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) - 修改版 oh-my-zsh&#39;s [maran](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) 主题.
* [zsh1999](https://github.com/DTan13/zsh1999) - Includes network connectivity, battery and `git` status decorations.
* [zsh2000](https://github.com/consolemaverick/zsh2000) - Powerline 外观 ZSH 主题，包括 `rvm` 提示、`git` 状态和分支、当前时间、用户、主机名、密码、退出状态、是否以 root 身份运行和后台作业状态.
* [zsh313](https://github.com/amirali313/zsh313-theme) - Minimal theme with `git` status decorations.
* [zshcomrade](https://github.com/landongn/zshcomrade) - 一个ZSH主题，同志！
* [zshpower](https://github.com/snakypy/zshpower)  - 针对 python 开发人员进行了优化. 包括 `git` 和 `pyenv` 状态装饰、用户名和主机. 尝试安装其他插件和字体，因此请在安装前阅读其说明.
* [zshred](https://github.com/redxtech/zshred) - 显示当前目录、`git` 装饰、最后一个命令的退出状态和时间.
* [zwsh](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for ZSH.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) - 如同 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), designed to disclose information contextually, with a powerline aesthetic.
* [zzshell](https://github.com/thezzisu/zzshell) - 受默认启发 [Oh-My-Zsh](http://ohmyz.sh/) theme. Displays exit code and `git` status decorations. Doesn't require Powerline fonts.

## Fonts

此处列出的一些主题需要与 Powerline 兼容的字体，以下是一些：

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - 一系列字体，包括一些不错的等宽图标.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - 另一种与电力线兼容的字体.
* [Hack](https://sourcefoundry.org/hack/) - 另一种专为源代码设计的兼容电力线的字体.
* [Input Mono](https://store.typenetwork.com/foundry/djr/series/input?family=input-mono)  - 专为代码设计的字体系列. 它提供等宽字体和比例字体，并包括电力线字形.
* [Iosevka](https://github.com/be5invis/Iosevka) - Coders’ typeface, built from code. Highly customizable.
* [Monoid](https://larsenwork.com/monoid/) - Monoid 可定制和优化，即使在低分辨率显示器上也能以 15 像素行高的位图锐度进行编码.
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts)  - 收集超过 20 种修补字体（超过 2,000 种变体）和 FontForge 字体修补程序 python 脚本，适用于 Powerline、Font Awesome、Octicons、Devions 和 Vim Devicons. 包括：Droid Sans、Meslo、源代码、AnonymousPro、Hack、ProFont、Inconsolata 等等.
* [Powerline patched font collection](https://github.com/powerline/fonts) - 十几种字体的集合，经过修补，包括电力线字形.
* [Terminus](http://files.ax86.net/terminus-ttf/) - TTF version of Terminus that includes powerline glyphs.

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

这些插件中的大多数都可以通过将 `antigen bundle githubuser/reponame` 添加到您的 .zshrc 文件中来安装.  Antigen 将在您下次启动 `zsh` 时自动为您处理克隆插件. 您还可以使用“antigen bundle githubuser/reponame”将该插件添加到正在运行的 ZSH 中进行测试，然后再将其添加到您的“.zshrc”中.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1.克隆新插件到`.zsh.local/modules`
2.在`.zshrc`中加载插件模块
3. Open a new ZSH terminal window or tab

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. 将 repo 添加到您的插件列表

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. 将插件克隆到您的 prezto 模块目录中
2. 将插件添加到您的 `.zpreztorc` 文件中
3.打开一个新的终端窗口或标签

### [Zgen](https://github.com/tarjoilija/zgen)

Zgen is not being actively maintained. Consider switching to the [Zgenom](https://github.com/jandamm/zgenom) fork, which is.

### [Zgenom](https://github.com/jandamm/zgenom)

这些插件中的大多数都可以通过将 `zgenom load githubuser/reponame` 添加到您的 .zshrc 文件中来安装，这与您正在执行其他 `zgenom load` 调用的功能相同.

当您执行 `zgenom save` 时，Zgenom 将自动为您克隆插件存储库.

### [zplug](https://github.com/zplug/zplug)

这些插件中的大多数都可以通过将 `zplug &quot;githubuser/reponame&quot;` 添加到您的 `.zshrc` 文件中来安装.

### [zpm](https://github.com/zpm-zsh/zpm)

这些插件中的大多数都可以通过将 `zpm load &quot;githubuser/reponame&quot;` 添加到您的 `.zshrc` 文件中来安装.

## Writing New Plugins

我已经记录了一些关于编写新插件的建议 [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

There is also a more detailed [Zsh Plugin Standard](https://zdharma-continuum.github.io/Zsh-100-Commits-Club/Zsh-Plugin-Standard.html).

## Other Resources

### ZSH Tools

* [ShellSpec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, ZSH and all POSIX shells.
* [zsh-bench](https://github.com/romkatv/zsh-bench) - A benchmark for interactive ZSH. It measures user-visible latency of interactive `zsh`: input lag, command lag, etc
* [zshdb](https://github.com/rocky/zshdb) - ZSH 调试器.
* [zshelldoc](https://github.com/zdharma-continuum/zshelldoc)  - 用于 shell 脚本的 Doxygen. 解析 ZSH 和 Bash 脚本，输出带有函数列表、调用树、导出变量列表等的 Asciidoc 文档.
* [zunit](https://github.com/zunit-zsh/zunit) - 一个强大的 ZSH 单元测试框架.

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - A curated list of awesome tools, resources and workflow tips making an awesome development environment
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open source sysadmin resources
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - A curated list for CLI lovers.

Find other useful awesome-* lists at the [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

- The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) 和 [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) are indispensable.

- [Mastering ZSH](https://github.com/rothgar/mastering-zsh) 是一个很棒的教程，它建立在基础之上，向您展示 ZSH 的高级用法、自定义和实际示例.
