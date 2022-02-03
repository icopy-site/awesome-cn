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

*Please read the [Contributing Guidelines](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Contributing.md) before contributing.*

## Frameworks

These frameworks make customizing your ZSH setup easier.

You can find some interesting performance timing comparisons of various frameworks in the following locations.

* [rossmacarthur/zsh-plugin-manager-benchmark](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark)
* [pm-perf-test](https://github.com/z-shell/pm-perf-test) - 用于在多个 ZSH 框架上运行性能测试的工具.
### [alf](https://github.com/psyrendust/alf)

 **Alf** 是一个超快速且可配置的 ZSH 框架； 它以 Prezto 和 Antigen 为蓝本，同时在封面下使用 Oh-My-Zsh； 并提供标准默认值、别名、功能、自动完成、自动更新和可安装的提示主题和插件.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

**ansible-role-zsh** is an ansible role with zero-knowledge installation. It uses antigen to manage bundles and oh-my-zsh. Can load bundles conditionally. By default it includes powerlevel9k theme, autosuggestions, syntax-highlighting and [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) and [fzf-marks](https://github.com/urbainvaes/fzf-marks) . 完全可定制.

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

**Ax-ZSH** integrates well with [Powerlevel10k](https://github.com/romkatv/powerlevel10k) 和其他扩展，包括兼容的插件 [oh-my-zsh](https://ohmyz.sh/).

### [dotzsh](https://github.com/dotphiles/dotzsh)

 **Dotzsh** 努力实现平台和版本独立. 在旧版本的 ZSH 下运行时，某些功能可能会丢失，但它应该会完全降级，并允许您在不同操作系统的多台机器上使用相同的设置而不会出现问题.

### [fresh](https://github.com/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as Bundler for your dot files.

### [miniplug](https://sr.ht/~yerinalexey/miniplug)

**miniplug** 是 ZSH 的简约插件管理器.

* 重新采购 .zshrc 时没有崩溃或双重插件加载
* Unlike other frameworks, Miniplug does not pollute your $PATH
* Only does the bare minimum for managing plugins

### [mzpm](https://github.com/Insert-Creative-Name-Here/mzpm)

**mzpm** 是 ZSH 的极简插件管理器。

Features:

- 从 GitHub 获取和加载插件
- Loading local plugins
- Loading themes

### [oh-my-zsh](https://ohmyz.sh/)

 **oh-my-zsh** 是一个社区驱动的框架，用于管理您的 ZSH 配置. 包括 120 多个可选插件（rails、git、macOS、hub、capistrano、brew、ant、macports 等），超过 120 个主题为您的早晨增添趣味，以及一个自动更新工具，可以轻松跟上最新的来自社区的更新.

### [PMS](https://github.com/JoshuaEstes/pms)

PMS allows you to manage your shell in a way to that helps decrease setup time and increases your productivity. It has support for themes (change the way your shell looks), plugins (adds functionality to your shell), and dotfile management.

 PMS 框架还允许您在不同的 shell 中使用相同的框架. 在您的个人笔记本电脑上使用 ZSH，并在远程服务器上使用 bash. 想尝尝鱼吗？ 来吧，尝试不同的贝壳.

### [prezto](https://github.com/sorin-ionescu/prezto)

**Prezto** enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes. There are some prezto-specific plugins at [https://github.com/belak/prezto-contrib](https://github.com/belak/prezto-contrib).

### [pumice](https://github.com/ryutamaki/pumice)

**Pumice** 是 ZSH 的轻量级插件管理器.

### [pz](https://github.com/mattmc3/pz)

A plugin manager for ZSH doesn't have to be complicated to be powerful. PZ doesn't try to be clever when it can be smart. PZ is a full featured, fast, and easy to understand plugin manager encapsulated in a single file with about 200 lines of clean ZSH.

PZ does just enough to manage your Zsh plugins really well, and then gets out of your way. And it's unit tested too to make sure it works as expected!

### [sheldon](https://github.com/rossmacarthur/sheldon)

A fast, configurable, shell plugin manager.

* 可以管理
  * 任何 `git` 存储库.
    * 分支/标签/提交支持.
    * Extra support for GitHub repositories.
    * Extra support for Gists.
  * 任意远程文件，只需指定 URL.
  * 本地插件，只需指定目录路径.
* Highly configurable install methods using [handlebars](http://handlebarsjs.com/) templating.
* 超快速并行安装.
* 配置文件使用 [TOML](https://github.com/toml-lang/toml) 句法。
* Uses a lock file for much faster loading of plugins.

### [Toasty](https://github.com/5paceToast/toasty-zsh)

**Toasty** 是一个 ZSH 框架，旨在促进管理，而不是命令它.

### [tzpm](https://github.com/notusknot/tzpm)

最小的 ZSH 插件管理器. 仍在开发中.

### [uz](https://github.com/maxrodrigo/uz)

ZSH 微插件管理器.

### [yazt](https://github.com/bashelled/yazt)

Yazt is a simple zsh theme manager in maintence that is compatible with nearly everything. You can use prompts in plugins, mix 'n' match two themes, with a few modifications, you can even use it in bash.

### [zapack](https://github.com/aiya000/zsh-zapack)

zapack 是一个基本的快速最小 ZSH 插件加载器.

### [zcomet](https://github.com/agkozak/zcomet)

 **zcomet** 是一个极简的 ZSH 插件管理器，它可以让你在没有缓存的情况下快速获得提示（参见基准测试）. 除了加载和更新存储在 Git 存储库中的插件外，它还支持延迟加载插件（进一步减少启动时间）以及下载和获取代码片段.

### [zebrafish](https://github.com/mattmc3/zebrafish)

**Zebrafish** is a lightweight, full-featured, blazing-fast ZSH micro-framework in just one file.

### [zeesh](https://github.com/zeekay/zeesh)

**Zeesh** is a cross-platform ZSH framework. It's similar to, but incompatible with, [oh-my-zsh](http://ohmyz.sh/). It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.

### [zgem](https://github.com/qoomon/zgem)

**Zgem** 是 ZSH 的插件管理器，支持从 git、http 和本地文件加载和更新插件和主题.

### [zgen](https://github.com/tarjoilija/zgen)

 **Zgen** 是受 Antigen 启发的 ZSH 轻量级插件管理器. 目标是在启动 shell 时有最小的开销，因为没有人喜欢等待. 它目前没有得到积极维护，我建议您使用 [zgenom](https://github.com/jandamm/zgenom) fork instead, which is.

### [zgenom](https://github.com/jandamm/zgenom)

A lightweight plugin manager for ZSH that is a fork that extends the brilliant [zgen](https://github.com/tarjoilija/zgen) and provides more features and bugfixes while being fully backwards compatible.

To keep loading fast during new terminal sessions, `zgenom` generates a static `init.zsh` file which does nothing but source your plugins and append them to your `fpath`.

This minimizes startup time by not having to execute time consuming logic (plugin checking, updates, etc) during startup. The downside is that you have to refresh the init script manually with `zgenom reset` whenever you update your plugin list in your `.zshrc`.

Zgenom can load [oh-my-zsh](http://ohmyz.sh/)-compatible and [prezto](https://github.com/sorin-ionescu/prezto)-compatible plugins and themes, and will automagically `git clone` plugins for you when you add them to your plugin list.

### [ZI](https://github.com/z-shell/zi)

 **ZI** 是用于 Zsh Unix shell 的瑞士军刀. 以前称为zplugin、zinit. 紫—— [Wiki Pages](https://z-shell.pages.dev/).

Bonus: you can use [zi-console](https://github.com/z-shell/zi-console) 查看和更改 ZSH 会话的状态（例如：列出和卸载插件）并从磁盘中删除插件和片段.

### [zilsh](https://github.com/zilsh/zilsh)

**zilsh** is a ZSH config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim](https://github.com/zimfw/zimfw)

**Zim** is a ZSH configuration framework with blazing speed and modular extensions.

### [Zinit](https://github.com/zdharma-continuum/zinit)

**Zinit** is an innovative and probably (because of the Turbo) the fastest plugin manager with support for:

- Turbo mode – 80% faster ZSH startup! for example: instead of 200 ms, it'll be 40 ms
- Completion management (selectively disable and enable completions)
- Snippets (↔ regular files downloaded via-URL, e.g.: scripts) and through them Oh My Zsh and Prezto plugins support (→ low overhead)
- 附件（↔ Zinit 扩展）
- 报告（来自插件加载 - 插件不再是黑匣子）
- Plugin unloading (allows e.g.: dynamic theme switching)
- `bindkey` 捕获和重新映射
- packages
- Clean `fpath` (the array `$fpath` is not being used to add completions and autoload functions, hence it stays concise, not bloated)
- Services ↔ a single-instance, background plugins
- Also, in general: all the mechanisms from the ZSH Plugin Standard – Zinit is a reference implementation of the standard.

The project is very active – currently > 3100 commits.

### [zit](https://github.com/thiagokokada/zit)

 **zit** 是 ZSH 的插件管理器. 它是最小的，因为它实现了作为插件管理器的最低要求：它允许用户从 Git 存储库（仅限 Git 存储库，它们为什么名称）安装插件，获取插件并更新它们. 它没有实现花哨的功能，例如清除已删除插件、自动编译已安装插件、oh-my-zsh/prezto/其他 ZSH 框架的别名、构建二进制文件、PATH 操作等.

### [znap](https://github.com/marlonrichert/zsh-snap)

 **:zap:Znap** 是一个轻量级的 ZSH 插件管理器和 Git 存储库管理器，易于理解. 虽然专门为 ZSH 插件量身定制，但 Znap 还用作管理 Git 存储库的通用实用程序.

Znap

Znap can:

- Make any prompt appear instantly. Reduce your startup time from ~200ms to ~40ms with just one command.
- Asynchronously compile your plugins and functions.
- Cache those expensive `eval $(commands)`.
- 并行克隆或拉取多个存储库.
- Re-clone all your repos without you having to re-enter them.
- 多回购管理
- 自动 `compinit` 和 `bashinit` - 你的 `.zshrc` 中不再需要它们，znap 会根据需要自动执行它们.

### [zoppo](https://github.com/zoppo/zoppo)

**Zoppo** is the crippled configuration framework for ZSH. As an Italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.

### [zpacker](https://github.com/happyslowly/zpacker)

**Zpacker** is a lightweight ZSH plugin & theme management framework.

### [zpico](https://github.com/thornjad/zpico)

<i>The minuscule ZSH package manager.</i><b>小巧的 ZSH 包管理器。</b> <i>No frills, no bloat, just 2 kB of 100% ZSH code, providing complete package management for your ZSH environment.</i><b>没有多余的装饰，没有臃肿，只有 2 kB 的 100% ZSH 代码，为您的 ZSH 环境提供完整的包管理。</b>

### [zplug](https://github.com/zplug/zplug)

**:hibiscus: Zplug** is a next-generation ZSH plugin manager.

- Can manage everything
  - Zsh 插件/UNIX 命令 [GitHub](https://github.com) and [Bitbucket](https://bitbucket.org)
  - Gist files ([gist.github.com](https://gist.github.com/discover))
  - Externally managed plugins e.g., [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) and [prezto](https://github.com/sorin-ionescu/prezto) plugins/themes
  - Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
  - Local plugins
  - etc. (you can add your [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- 超快速并行安装/更新
- 支持延迟加载
- Branch/tag/commit support
- 更新后，加载后挂钩
- 包之间的依赖关系
- Unlike [antigen](https://github.com/zsh-users/antigen), 不需要 ZSH 插件文件 (`*.plugin.zsh`)
- Interactive interface ([fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw), and so on)
- Cache mechanism for reducing [the startup time](https://github.com/zplug/zplug#vs)

### [zpm](https://github.com/zpm-zsh/zpm)

**zpm** ( ZSH Plugin Manager ) is a plugin manager for [ZSH](http://www.zsh.org/) who combines the imperative and declarative approach. At first run, zpm will do complex logic and generate cache, after that will be used cache only, so it makes this framework to be very fast.

* Fastest plugin manager (Really, after the first run, zpm will not be used at all)
* Support for async loading
* Dependencies between packages
* zpm 在 Linux、macOS、FreeBSD 和 Android 上运行.
* zpm 插件兼容 [oh-my-zsh](http://ohmyz.sh/).

### [zr](https://github.com/jedahan/zr)

**zr** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zshing](https://github.com/zakariaGatter/zshing)

**zshing** is a ZSH plugin manager similar to Vundle/Vim and allows you to...

* 在 `.zshrc` 中跟踪和配置您的插件
* Install ZSH plugins
* 更新 ZSH 插件
* Search by name all available ZSH Plugins
* Clean unused plugins up
* run the above actions in a *single command*
* manages the __Source Plugins__ of your installed Plugins

### [ztanesh](https://github.com/miohtama/ztanesh)

**Ztanesh** aims to improve your UNIX command line experience and productivity with the the configuration provided by the ztanesh project: the tools will make your shell more powerful and easier to use.

### [ztheme](https://github.com/SkyyySi/ztheme)

ztheme is a small and fast theme engine for ZSH.

### [ztupide](https://github.com/mpostaire/ztupide)

A simple and fast ZSH plugin manager. It uses zcompile and async loading to speed up your shell startup time.

### [zulu](https://github.com/zulu-zsh/zulu)

**Zulu** is a environment manager for ZSH 5+, which aims to make it easy to manage your shell without writing any code.

* 无需编辑文件即可轻松管理您的 shell 环境.
* Create aliases, functions and environment variables, and have them available to you at the next shell startup.
* 使用简单的命令从 `$path`、`$fpath` 和 `$cdpath` 添加和删除目录.
* Install packages, plugins and themes easily, and have them available to you immediately.

## Setups

This section is for full setup dropins - they aren't frameworks, but they're not simple plugins/themes either.

### zgenom

* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - 使用 ZSH 的简单快速入门 [zgenom](https://github.com/jandamm/zgenom). This automatically configures ZSH to use [zgenom](https://github.com/jandamm/zgenom) 加载精选的插件集合并定期自动更新自身、插件和快速入门工具包本身.

### zinit

* [ZPWR](https://github.com/MenkeTechnologies/zpwr) - 一个极其强大的自定义终端环境，建立在 [Zinit](https://github.com/zdharma-continuum/zinit) 以获得最大速度. 一个完整的终端配置框架，包括 `zsh`、`tmux`、`fzf`、`vim` 和 spacemacs 配置. 这包括：

- 11.5k+ 选项卡完成
- 1.9k+ aliases
- 330+ git aliases
- 350 多个 zpwr 子命令
- 2.1k 功能
- 150+ zpwr 环境变量
- 170 多个 perl、python、bash、zsh 脚本
- 2.8k line README.md
- 46k+ LOC
- 1 line install

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - 使用组合的教程 [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io)， 和 [Tmuxinator](https://github.com/tmuxinator/tmuxinator) to make for an extremely productive developer workflow.
* [Arch Linux's ZSH introduction](https://wiki.archlinux.org/index.php/zsh) - 实际上不是 Arch 或 Linux 特定的.
* [GH](https://github.com/gustavohellwig/gh-zsh) - Setup ZSH on debian/Ubuntu-based linuxes. Installs [Powerlevel10k](https://github.com/romkatv/powerlevel10k), [zsh-completions](https://github.com/zsh-users/zsh-completions), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting/)， 和更多.
* [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - A beginner-friendly tutorial on how to install and configure a ZSH shell.
* [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
* [rs-example](https://github.com/al-jshen/zshplug-rs-example) - An example plugin showing how a Rust program can listen to and process commands from ZSH.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
* [xVanjaZ](https://github.com/xVanjaZ/xVanjaZ-ZSH-Theme) - wrote a quick setup document for oh-my-zsh beginners showing how to use the [spaceship](https://github.com/denysdovhan/spaceship-prompt.git) prompt, syntax highlighting at the prompt, autosuggestion and a custom iTerm 2 theme.
* [ZSH for Humans](https://github.com/romkatv/zsh4humans) - A turnkey configuration for ZSH that aims to work really well out of the box. It combines a curated set of ZSH plugins into a coherent whole that feels like a finished product rather than a DIY starter kit.
* [ZSH Pony](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.
- [ZSH Unplugged](https://github.com/mattmc3/zsh_unplugged) - Good resource if you want to eliminate using a framework but still easily use plugins.

### Antigen

* [belak/zsh-utils](https://github.com/belak/zsh-utils) - 一组最小的 ZSH 插件，旨在低摩擦和低复杂性.
* [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis' introduction to Antigen.

### Oh-My-Zsh

* [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - A beginners guide to oh-my-zsh by Dien Bui
* [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - A beginners guide to using Oh My Zsh on macOS by Karl Hadwen
* [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders installation guide for Ubuntu
* [ZSH Gem 24](https://www.refining-linux.org/archives/59-ZSH-Gem-24-ZSH-frameworks.html) - Part of the 2011 ZSH Advent Calendar. Covers oh-my-zsh and zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, [Tmux](https://tmux.github.io) & Tmuxinator.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) - A fantastically feature rich, lightning-fast shell setup, powered by [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto)， 和 [Zgen](https://github.com/tarjoilija/zgen).

### Zinit (né zplugin)

* [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh) - :crystal_ball: Awesome, customable Zsh Starter Kit :stars::stars:. Includes powerline, `fzf` integration, Weather and image viewing in some terminals.
* [zinit-configs](https://github.com/zdharma-continuum/zinit-configs) - Real-world configuration files (basically a collection of `.zshrc` files) holding [zinit](https://github.com/zdharma-continuum/zinit) 调用.

### ZSH on Windows

* [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only.

  * ConEmu/zsh 开箱即用配置为在 ConEmu 重新启动后恢复以前打开的选项卡和 shell 工作目录
  * Choose between clean and inherited environment when starting new SuperConsole sessions
  *自定义彩色方案，各种命令的彩色输出
  * MSYS2 included, `zsh` and necessary software preinstalled, uses zsh-grml-config
  * Uses Antigen for ZSH theme and config management
  * Enabled number of ZSH plugins to activate completion, highlighting and history for most comfortable use
  * 为 MSYS2 环境配置了正确的 `git` 和 git lfs 支持的 Git-for-Windows 存储库，`git` 客户端已经安装.
  * `git` 的 `ssh-agent` 开箱即用，将您的密钥添加到 `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` 目录
  * Non-blocking ZSH prompt status updates thanks to agkozak-zsh-prompt
  * 为 MSYS2 定制的 command-not-found 处理程序建议安装什么包
  * Sets up `nano` as main editor, enables `nano` syntax highlighting
  * Custom helper scripts added to `ConEmu/msys64/3rdparty`

## Plugins

* [1999](https://github.com/DTan13/zsh1999) - Powerline-esque theme. Includes `git` status decorations, network and battery status.
* [256color](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen `TERM` environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
* [abbr (olets)](https://github.com/olets/zsh-abbr) - Manages auto-expanding abbreviations that expand inline when you hit space, inspired by fish shell.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - Provides functionality similar to `vim`'s abbreviation expansion.
* [accurev](https://github.com/dalefukami/accurev-zsh) - ZSH 插件 [accurev](https://www.microfocus.com/en-us/products/accurev/overview).
* [actiona](https://github.com/matthieusb/act) - Make it easier to call [actiona](https://github.com/Jmgr/actiona) 命令行中的脚本. 包括制表符补全.
* [alacritty](https://github.com/casonadams/alacritty-shell) - Control [alacritty](https://github.com/alacritty/alacritty/wiki/Color-schemes) color schemes.
* [alehouse](https://github.com/sticklerm3/alehouse) - Contains short aliases for [brew](https://brew.sh) 命令，灵感来自 [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin).
* [alias-tips](https://github.com/djui/alias-tips) - 一个 oh-my-zsh 插件，可帮助记住您曾经定义的那些别名.
* [alias](https://github.com/xylous/alias-zsh) - Tool for managing your aliases.
* [allergen](https://github.com/stanislas/allergen) - A collection of custom ZSH plugins to use with Antigen.
* [almostontop](https://github.com/Valiev/almostontop)  - 每次在 shell 中执行新命令之前清除先前的命令输出. 灵感来自 [alwaysontop](https://github.com/swirepe/alwaysontop) `bash` 的插件.
* [alt-and-select](https://github.com/raisty/alt-and-select) - Binds the alt-c (copy), alt-v (paste), alt-x (cut) keyboard shortcut to a commands: copy-region-as-kill, yank, kill-region. Remaps the execute command to Alt-Shift-X.
* [ansible](https://github.com/sparsick/ansible-zsh) - A plugin for [Ansible](https://www.ansible.com/).
* [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH script to aid with `git` rebasing.
* [anyframe](https://github.com/mollifier/anyframe) - A peco/percol/fzf wrapper plugin for ZSH.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - Adds aliases and functions for managing Apache2.
* [apparix](https://github.com/micans/apparix) - Command line directory bookmarks with jumping to bookmarks, subdirectory tab completion, distant listing etc.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - Adds MacBook Pro touchbar support in [iTerm 2](https://iterm2.com).
* [appup](https://github.com/Cloudstek/zsh-plugin-appup) - Adds `start`, `stop`, `up` and `down` commands when it detects a `docker-compose.yml` or `Vagrantfile` in the current directory (e.g. your application). Just run `up` and get coding!
* [arc](https://github.com/anton-rudeshko/zsh-arc) - Adds aliases for Yandex version control system.
* [arduino](https://github.com/raghur/zsh-arduino) - Adds scripts to build, upload and monitor arduino sketches from a command line. Requires [`jq`](https://stedolan.github.io/jq/).
* [artisan](https://github.com/jessarcher/zsh-artisan) - Laravel `artisan` plugin for ZSH to help you to run `artisan` from anywhere in the project tree, with tab completion!
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - A plugin for AsciiDoctor.
* [asdf-direnv](https://github.com/redxtech/zsh-asdf-direnv) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf) and [direnv](https://github.com/asdf-community/asdf-direnv).
* [asdf-prompt](https://github.com/CurryEleison/zsh-asdf-prompt) - 提供可在提示中使用的功能，显示当前工具版本的版本信息.
* [asdf](https://github.com/kiurchv/asdf.plugin.zsh) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf), the extendable version manager, with support for Ruby, Node.js, Elixir, Erlang and more.
* [assume-role](https://github.com/weizard/assume-role) - ZSH plugin to allow you to assume AWS IAM roles easily. Includes completions.
* [async](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in ZSH without requiring any external tools. Allows you to run multiple asynchronous jobs, enforce unique jobs (multiple instances of the same job will not run), flush all currently running jobs and create multiple workers (each with their own jobs).
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - Based on the [Sublime](https://github.com/valentinocossar/sublime) 插件，可让您在其中启动文件或文件夹 [Atom](https://atom.io) from [iTerm 2](https://iterm2.com).
* [atuin](https://github.com/ellie/atuin) - Replaces your existing shell history with a SQLite database, and records additional context for your commands. Additionally, it provides optional and fully encrypted synchronisation of your history between machines, via an Atuin server.
* [aur-install](https://github.com/redxtech/zsh-aur-install) - 从 AUR 安装软件包的小插件.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) - Automatically list directories with `colorls`.
* [auto-fortune-cowsay](https://github.com/babasbot/auto-fortune-cowsay-zsh) - Prints out an ASCII picture of a cow saying a random epigram on every zsh start.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
* [auto-ls (commanda-panda)](https://github.com/commanda-panda/zsh-auto-ls) - Automatically runs `ls` or `color-ls` if available on `cd`.
* [auto-ls (desyncr)](https://github.com/desyncr/auto-ls) - cd 到新目录时自动 `ls`.
* [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) - Automatically sends out a notification when a long running task has completed.
* [auto-nvm](https://github.com/manlao/zsh-auto-nvm) - Automatically switches to the node version specified in a given directory.
* [autocomplete](https://github.com/marlonrichert/zsh-autocomplete) - Automatically lists completions as you type and provides intuitive keybindings for selecting and inserting them.
* [autodotenv](https://github.com/nocttuam/autodotenv) - 当您将 `cd` 放入包含 `.env` 文件的目录时，会提示您加载变量.
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) - Extended version of the [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) 插入.
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a `.env` file, it will automatically be executed when you `cd` into it.
* [autojump](https://github.com/wting/autojump) - A `cd` command that learns - easily navigate directories from the command line. Install autojump-zsh for best results.
* [autopair](https://github.com/hlissner/zsh-autopair) - A ZSH plugin for auto-closing, deleting and skipping over matching delimiters. Only tested on ZSH 5.0.2 or later.
* [autoquoter](https://github.com/ianthehenry/zsh-autoquoter) - A `zle` widget ("zsh plugin") that will automatically put quotes around arguments to certain commands.
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)-like fast/unobtrusive autosuggestions for ZSH.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) - ZSH plugin to automatically switch python virtualenvs and pipenvs when traversing directories. Automatically detects pipenv and poetry projects.
* [autoupdate-antibody](https://github.com/spikespaz/autoupdate-antibody-zsh) - 一个叉子 [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) 为了 [Antibody](https://getantibody.github.io) plugin manager, with the added ability to cooperate with static loading.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin)  - Antigen 不会像 oh-my-zsh 那样进行自动更新. 该插件为抗原添加了自动更新，包括抗原和配置中加载的包.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - oh-my-zsh doesn't automatically update non-core plugins, this adds plugin autoupdating to oh-my-zsh.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - AWS CLI MFA plugin based on sweharris' [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa). Supports specifying mfa_device in profile.
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - AWS MFA 插件.
* [aws-plugin](https://github.com/pookey/zsh-aws-plugin) - Adds helper functions for `aws` command. Includes mfa and assume-role helpers.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - Boost your productivity with `aws-upload`.
* [aws-vault (blimmer)](https://github.com/blimmer/zsh-aws-vault) - 插件 [aws-vault](https://github.com/99designs/aws-vault). Includes tab completions.
* [aws-vault (reegnz)](https://github.com/reegnz/aws-vault-zsh-plugin) - 使其更易于使用 [aws-vault](https://github.com/99designs/aws-vault) 在你的环境中。
* [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) - Provides completion support for version 2 of the [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) and a few utilities to manage AWS profiles and display them in the prompt.
* [aws](https://github.com/apachler/zsh-aws) - 从原始的 oh-my-zsh 分叉 [aws](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aws). Includes completions for `awscli` and a few utilities for managing AWS profiles and displaying them in your prompt.
* [awsume](https://github.com/Sordie/AWSume) - Plugin that enables showing the current [awsume](https://github.com/trek10inc/awsume) profile.
* [azcli](https://github.com/dmakeienko/azcli) - 使用 azure cli 工具的助手.
* [azure-keyvault](https://github.com/milespossing/Azure-Keyvault-Zsh) - 使在 cli 中使用 azure keyvaults 变得不那么冗长.
* [azure-subscription](https://github.com/dmakeienko/azure-subscription-prompt) - Displays information about the Azure current Subscription and tenant.
* [background](https://github.com/zpm-zsh/background) - ZSH plugin which executes functions in the background.
* [base16](https://github.com/chriskempson/base16-shell) - Adds script to allow you to change your shell's default ANSI colors but most importantly, colors 17 to 21 of your shell's 256 colorspace (if supported by your terminal). This script makes it possible to honor the original bright colors of your shell (e.g. bright green is still green and so on) while providing additional base16 colors to applications such as [Vim](https://www.vim.org).
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts) - Print random baseball related "fun facts" in your shell. Depends on `fortune` and `cowsay` being installed.
* [basex](https://github.com/dirkk/zsh-basex) - 增加了几个 [BaseX](http://basex.org/) aliases for simplified usage.
* [bash-quote](https://github.com/jtprog/bash-quote) - 从 Bash.im 获取随机报价.
* [bash](https://github.com/chrissicool/zsh-bash) - Makes ZSH more Bash compatible. It redefines the source command to act more like `bash` does. It also enables `bash` completions.
* [battery_state](https://github.com/Jactry/zsh_battery_state) - Show battery state in right-prompt.
* [bd](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`.
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) - Remap ZSH `vi`-mode for French [bépo keyboard](http://bepo.fr/wiki/Accueil).
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) - Add more command aliases for `brew`
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - Adds helper scripts to allow you to create bitbucket PRs or open a directory in the current branch.
* [bitwarden](https://github.com/Game4Move78/zsh-bitwarden) - 添加管理功能 [bitwarden](https://bitwarden.com/) sessions.
* [blackbox](https://github.com/StackExchange/blackbox) - [Stack Exchange](https://stackexchange.com)'s toolkit for storing keys/credentials securely in a `git` repository.
* [bofh](https://github.com/fundor333/bofh) - Adds functions to display random bofh fortunes.
* [bol](https://github.com/ikhurramraza/bol) - Prints a random quote when you open a terminal window.
* [boss-docker](https://github.com/bossjones/boss-docker-zsh-plugin) - Manages `docker` on OSX.
* [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) - Adds some convenience aliases for `git`.
* [branch-manager](https://github.com/elstgav/branch-manager) - A plugin for managing `git` branches.
* [brew (rhuang2014)](https://github.com/rhuang2014/brew) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
* [brew (wolffaxn)](https://github.com/wolffaxn/brew-zsh-plugin) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - A plugin that lets you open any commit in your browser from the command line.
* [bruse](https://github.com/aubreypwd/zsh-plugin-bruse) - Makes it easy to `brew link` different versions of packages.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - A plugin to toggle optirun in the command line.
* [c](https://github.com/sebastiangraz/c) - Adds some `git` shortcuts.
* [calc](https://github.com/arzzen/calc.plugin.zsh) - A calculator for ZSH.
* [calibre-zaw-source](https://github.com/junkblocker/calibre-zaw-source) - [Calibre - E-book management](https://calibre-ebook.com/) source for [zaw](https://github.com/zsh-users/zaw)
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - 添加 [Can I Use...](https://caniuse.com) 支持 ZSH.
* [careful_rm](https://github.com/MikeDacre/careful_rm) - A wrapper for `rm` that adds trash/recycling and useful warnings.
* [case](https://github.com/rtuin/zsh-case) - A ZSH plugin that adds two aliases `tolower` and `toupper` to switch output case.
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - A ZSH plugin to `cd` to the `git` repository root directory.
* [cd-ls](https://github.com/zshzoo/cd-ls) - Automatically `ls` after `cd`.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) - Display reminders when `cd`-ing into specified directories.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - A ZSH plugin to `cd` to the current repository checkout's root directory.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - `ssh` to a server when you accidentally `cd` to it.
* [cdbk](https://github.com/MikeDacre/cdbk) - 一个 ZSH 插件，允许轻松创建命名目录 - 任何您想要的目录的快捷方式.
* [cdc](https://github.com/evanthegrayt/cdc)  - 更容易将目录更改为用户定义的目录列表的子目录. 包括 tab-completion、会话历史和 `pushd`、`popd` 和 `dirs` 等价物.
* [cdr](https://github.com/willghatch/zsh-cdr) - Easy setup of cdr for ZSH.
* [change-case](https://github.com/mtxr/zsh-change-case) - Plugin for fast swap between upper and lower case in your command line. :sunglasses:
* [cheatsheet](https://github.com/0b10/cheatsheet) - 用于轻松查看、创建和编辑备忘单的插件.
* [check-deps](https://github.com/zpm-zsh/check-deps) - Helper for ZSH plugins that allows them to show how to install any missing dependencies. Works on Debian (and derivatives like Ubuntu), Arch and its derivatives, Nodejs and ZSH plugins if you are using the [zpm](https://github.com/zpm-zsh/zpm) 框架.
* [chgo](https://github.com/sbfaulkner/chgo-plugin-zsh) - Clone of chruby modified to make it easy to switch between multiple Go versions.
* [clean-project](https://github.com/wwilsman/zsh-clean-project) - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories.
* [clipboard](https://github.com/zpm-zsh/clipboard) - Adds a cross-platform helper function to access the system clipboard. Works on macOS, X11 (and Wayland) and Cygwin.
* [cmd-status](https://github.com/BlaineEXE/zsh-cmd-status) - 报告命令的状态，包括返回码和持续时间.
* [cmdtime](https://github.com/tom-auger/cmdtime) - Displays the duration of a command to the terminal forked from the [timer](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) 插入.
* [code-review](https://github.com/xorkevin/code-review-zsh) - Launches `git difftool` on `git merge-base target_branch base_branch` and `target_branch`.
* [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - 计算按键并记录统计信息 [Code::Stats](https://codestats.net/).
* [codex](https://github.com/tom-doerr/zsh_codex) - Enables you to use OpenAI's powerful Codex AI in the command line.
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - Forked from [ohmyzsh/ohmyzsh/plugins/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh). Colorizes `man` output.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - Colorize `man` pages.
* [colorize](https://github.com/zpm-zsh/colorize) - Colorize the output of various programs.
* [colorls](https://github.com/Kallahan23/zsh-colorls) - Defines a few helpful shortcuts to some colorls functions.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - Enhanced colors for ZSH.
* [command-execution-timer](https://github.com/olets/command-execution-timer) - Displays the time an interactive shell command takes to execute.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) - oh-my-zsh command-not-found 插件的镜像，因此您不必包含所有 oh-my-zsh.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - Record complex commands and comment on them.
* [command-time](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in ZSH and [powerlevel9k](https://github.com/bhilburn/powerlevel9k) . 类似于 `REPORTTIME` 内置，但仅在用户 + 系统时间 &gt;= `REPORTTIME` 时输出.
* [compe](https://github.com/tamago324/compe-zsh) - 添加完成 [nvim-compe](https://github.com/hrsh7th/nvim-compe).
* [completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script.
* [completion-zstyles](https://github.com/zshzoo/completion-zstyles) - Zstyle settings for ZSH completions based on Prezto's.
* [conda](https://github.com/ThemysciraData/conda.plugin.zsh) - 添加功能以提供 `conda` 的提示段和一些基本功能的别名.
* [copier](https://github.com/zshzoo/copier) - Standalone clipboard utilities from oh-my-zsh.
* [copy-pasta](https://github.com/ChrisPenner/copy-pasta) - 在终端中复制和粘贴文件，就像在 GUI 中一样.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - A ZSH plugin to copy your shell configuration to another machine over `ssh`.
* [crash](https://github.com/molovo/crash) - Adds proper error handling, exceptions and try/catch for ZSH.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - 用于 Wordpress 的 Crayon 插件的 ZSH 语法突出显示.
* [cros-auto-notify](https://github.com/D3STY/cros-auto-notify-zsh)  - 长时间运行的任务完成时自动发出通知. 适用于 macOS 和 linux（如果安装了 `hterm-notify`）.
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - Add a [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 以当前比特币价格细分.
* [crystal](https://github.com/veelenga/crystal-zsh) - A plugin for [Crystal](https://github.com/crystal-lang/crystal).
* [czhttpd](https://github.com/jsks/czhttpd) - A simple http server written in 99.9% pure ZSH.
* [declare-zsh](https://github.com/z-shell/declare-zsh) - A parser for zinit commands in `.zshrc`. It allows to perform the following actions on `.zshrc` from the command-line - enable and disable plugins add or remove snippets.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - 收集有用和有趣的命令，以改善工作流程和生活质量.
* [deer](https://github.com/Vifon/deer) - A file navigator for ZSH heavily inspired by [ranger](https://ranger.github.io/).
* [defer](https://github.com/romkatv/zsh-defer) - Defers execution of a `zsh` command until `zsh` has nothing else to do and is waiting for user input. Its intended purpose is staged `zsh` startup. It works similarly to Turbo mode in [zinit](https://github.com/zdharma-continuum/zinit).
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools)  - 用于安装 chromium depot_tools 的简单 oh-my-zsh 插件. 安装此插件将自动将所有 chromium depot_tools 放入您的路径中.
* [dev](https://github.com/sbfaulkner/dev-plugin-zsh) - 提供 Shopify 内部开发工具的轻量级版本
* [diff-so-fancy](https://github.com/z-shell/zsh-diff-so-fancy) - 安装 [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) and enables its use in ZSH.
* [diractions](https://github.com/AdrieanKhisbe/diractions) - Allow you to map a short logical/mnemonic name to directories to quickly access them, or perform actions in them.
* [dircolors-solarized (joel-porquet)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin, with options for dark or light terminal backgrounds.
* [dircolors-solarized (pinelibg)](https://github.com/pinelibg/dircolors-solarized-zsh) - Enables [Solarized Color Theme for GNU ls](https://github.com/seebi/dircolors-solarized).
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - Cycle through the directory stack.
* [directory-history](https://github.com/tymm/zsh-directory-history) - A per directory history for ZSH which implements forward/backward navigation as well as substring search in a directory sensitive manner.
* [direnv](https://github.com/ptavares/zsh-direnv) - A plugin for installing and loading [direnv](https://github.com/direnv/direnv.git). Inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv).
* [dirrc](https://github.com/gmatheu/shell-plugins) - 当存在于你 `cd` 进入的目录中时执行 `.dirc`.
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - 用于在单行上显示 dirstack 信息的插件.
* [doas (anatolykopyl)](https://github.com/anatolykopyl/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
* [doas (senderman)](https://github.com/Senderman/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
* [docker-aliases](https://github.com/webyneter/docker-aliases) Docker aliases for everyday use.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) 在提示中显示 docker 容器状态.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - A collection of docker helper scripts.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) - ZSH 的 docker-machine 插件.
* [docker-run](https://github.com/rawkode/zsh-docker-run) - Go back to running your commands "naturally", we'll handle the container.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
* [dotbare](https://github.com/kazhala/dotbare) - Interactive dotfile management with the help of [fzf](https://github.com/junegunn/fzf).
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - 使用 `git` 使您的点文件在多台机器上保持同步.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - Automagically switch to a python virtual environment located (that you previously have created with virtualenv program) in a directory named `.pyvenv` when you `cd` into a directory.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for ZSH that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drupal](https://github.com/yhaefliger/zsh-drupal)  - 为常见任务添加别名，并为“drush”添加标签完成. 灵感来自 [Artisan](https://github.com/jessarcher/zsh-artisan).
* [dune-quotes](https://github.com/brokendisk/dune-quotes) - Random Dune quote generator plugin.
* [duration](https://github.com/rtakasuke/zsh-duration) - Displays command duration if it exceeds a user-settable run time.
* [dwim](https://github.com/oknowton/zsh-dwim)  - 尝试预测你下一步想要做什么. 它提供了一个键绑定 (control-u)，它将用您接下来要运行的命令替换当前（或上一个）命令行.
* [easy-motion](https://github.com/IngoHeimbach/zsh-easy-motion) - A port of [vim-easymotion](https://github.com/easymotion/vim-easymotion) 对于 ZSH.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - List EC2 instances and `ssh` login to the instances easily.
* [editing-workbench](https://github.com/commiyou/zsh-editing-workbench) - Adds sane, complex command line editing (e.g. incremental history word completion).
* [edward cli](https://github.com/matthieusb/zsh-edward) - 添加智能完成和别名 [edward CLI micro-service launcher](https://github.com/yext/edward).
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - Adds shortcuts for Elixir, IEX, Mix, Kiex and Phoenix.
* [emacs (cowboyd)](https://github.com/cowboyd/zsh-emacs) - Make Emacs the default for CLI operations like editing git commit messages; set up handy aliases.
* [emacs (flinner)](https://github.com/Flinner/zsh-emacs) - Uses the Emacs daemon capability, allowing the user to quickly open frames, whether they are opened in a terminal via a ssh connection, or X frames opened on the same host.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: Emoji completion on the command line.
* [emoji-fzf](https://github.com/pschmitt/emoji-fzf.zsh) - Configurable ZSH plugin for the excellent [emoji-fzf](https://github.com/noahp/emoji-fzf). It is heavily inspired by [emoji-cli](https://github.com/b4b4r07/emoji-cli).
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) - 在方便的变量中添加大量 ascii 艺术表情符号到您的环境中.
* [enhancd](https://github.com/b4b4r07/enhancd) - 一个简单的工具，通过记住用户访问的所有目录并将其用于路径名解析来提供增强的“cd”命令.
* [envrc](https://github.com/fabiogibson/envrc-zsh-plugin) - Automatically loads and unloads environment variables if a `.envrc` file is found in a directory.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - Quickly insert escaped backticks when double-tapping "`".
* [evalcache](https://github.com/mroth/evalcache) - 缓存二进制初始化命令的输出，以帮助减少 shell 启动时间.
* [evil-registers](https://github.com/zsh-vi-more/evil-registers) - Extends ZLE vi commands to remotely access named registers of the vim and nvim editors, and system selection and clipboard.
* [exa (DarrinTisdale)](https://github.com/DarrinTisdale/zsh-aliases-exa) - Enables a number of aliases extending [exa](https://the.exa.website), `ls` 的现代替代品.
* [exa (hermitmaster)](https://github.com/hermitmaster/zsh-exa-plugin) - Adds some aliases for [exa](https://the.exa.website), `ls` 的现代替代品.
* [exa (mohamedelashri)](https://github.com/MohamedElashri/exa-zsh) - 添加别名 [exa](https://the.exa.website), `ls` 的现代替代品.
* [exa (ptavares)](https://github.com/ptavares/zsh-exa) - Installs and loads [exa](https://github.com/ogham/exa.git).
* [exa (ritchies)](https://github.com/RitchieS/zsh-exa/) - Adds aliases to make using [exa](https://github.com/ogham/exa.git) easier.
* [exa-ls](https://github.com/birdhackor/zsh-exa-ls-plugin) - 添加别名以便您可以使用 [exa](https://the.exa.website) as a drop-in replacement for `ls` and `tree`.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/).
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - Expand specific aliases with space.
* [expand](https://github.com/MenkeTechnologies/zsh-expand) - Expands regular aliases, global aliases, incorrect spellings and phrases, globs, history expansion and $parameters with the spacebar key.
* [expander](https://github.com/ianthehenry/zsh-expander) - A `zle` widget that allows you to write custom expanders and select them with [fzf](https://github.com/junegunn/fzf).
* [explain-shell](https://github.com/gmatheu/shell-plugins) - Opens commands on [explainshell.com](https://explainshell.com).
* [extend-history](https://github.com/xav-b/zsh-extend-history) - 通过为历史记录中的每个命令添加退出代码来扩展命令历史记录.
* [f-shortcuts](https://github.com/zpm-zsh/f-shortcuts) - Makes a shortcuts toolbar using F1 to F12 keys.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of oh-my-zsh.
* [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips) - Helps remember the aliases you defined and forgot about. Ported from [djui/alias-tips](https://github.com/djui/alias-tips).
* [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting) - 优化和改进了“zsh-users/zsh-syntax-highlighting”——更好的响应时间，可切换的高亮主题.
* [fav](https://github.com/ddnexus/fav) - ZSH/[fzf](https://github.com/junegunn/fzf) 插件，使添加和调用重要目录的命名收藏夹变得非常容易.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - 快速跳转到您最喜欢的目录.
* [figures](https://github.com/zpm-zsh/figures) - Unicode symbols for ZSH.
* [firebase (Seqi)](https://github.com/Seqi/firebase-zsh) - Display the current working project or project alias when in a Firebase project directory or subdirectory.
* [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) - 在提示中添加一个指示符，表明您位于具有 `firebase.json` 文件（又名“firebase 项目”）的目录中.
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - 使 Apple 键盘的数字键能够在 ZSH 中被识别.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - This plugin makes the `flow` command available inside every subdirectory of the TYPO3 Flow distribution.
* [fnm](https://github.com/dominik-schwabe/zsh-fnm) - Installs and loads the [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) 如果它丢失了.
* [forgit](https://github.com/wfxr/forgit) - `git` 的实用工具，它利用了模糊查找器 [fzf](https://github.com/junegunn/fzf).
* [functional](https://github.com/Tarrasch/zsh-functional) - ZSH 高阶函数.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line.
* [fuzzy-wd](https://github.com/spodin/zsh-fuzzy-wd) - Adds fuzzy search for directories warped withe the [WD](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/wd) 插入.
* [fz](https://github.com/changyuheng/fz) - 无缝添加模糊搜索 [z](https://github.com/rupa/z)'s tab completion and lets you easily jump around among directories in your history.
* [fzf (unixorn)](https://github.com/unixorn/fzf-zsh-plugin/tree/master) - Enables [fzf](https://github.com/junegunn/fzf) history and file searches.
* [fzf-fasd](https://github.com/wookayin/fzf-fasd) - Integrates [fzf](https://github.com/junegunn/fzf) and [fasd](https://github.com/clvv/fasd) --- tab completion of `z` with fzf's fuzzy search!
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - 插件有一个很酷的搜索键绑定 [fzf](https://github.com/junegunn/fzf) and (optionally) [bat](https://github.com/sharkdp/bat) . 在子目录的本地树中搜索文件.
* [fzf-history-search](https://github.com/joshskidmore/zsh-fzf-history-search) - 将 `Ctrl+R` 替换为 [fzf](https://github.com/junegunn/fzf)-driven history search that includes date/times.
* [fzf-it](https://github.com/micakce/fzf-it) - 使用 FZF 功能使任何命令交互式包装.
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) - Little script to create, navigate and delete bookmarks in `bash` and `zsh`, using the fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [fzf-pass](https://github.com/smeagol74/zsh-fzf-pass) - Better handling of passwords using [fzf](https://github.com/junegunn/fzf) and [pass](https://www.passwordstore.org/).
* [fzf-prezto](https://github.com/lildude/fzf-prezto) - Prezto plugin that finds where [fzf](https://github.com/junegunn/fzf) 已安装并启用其自动完成和键绑定. 这个插件作为 Prezto `zstyle` 配置选项工作.
* [fzf-tab](https://github.com/Aloxaf/fzf-tab) - Replace ZSH's default completion selection menu with [fzf](https://github.com/junegunn/fzf).
* [fzf-utils](https://github.com/redxtech/zsh-fzf-utils) - Provides functions to kill proceses and find in path with [fzf](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - Adds some ZLE widgets for [fzf](https://github.com/junegunn/fzf).
* [fzf-z](https://github.com/andrewferrier/fzf-z) - Brings together the *z* plugin and *fzf* to allow you to easily browse recently used directories at any point on the command line.
* [fzy](https://github.com/aperezdc/zsh-fzy) - 使用的插件 [fzy](https://github.com/jhawthorn/fzy) for certain fuzzy matching operations.
* [gcloud-project](https://github.com/avivl/gcloud-project) - Easy selection of Google Cloud Projects.
* [gdbm](https://github.com/zdharma-continuum/zgdbm) - Adds GDBM as a plugin.
* [geeknote](https://github.com/s7anley/zsh-geeknote) - [Geeknote](https://geeknote.me) plugin for ZSH.
* [gentoo](https://github.com/MattiaG-afk/gentoo-ohmyzsh) - 添加一些别名和函数以与 Gentoo Linux 一起使用.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) datetime plugin. Shows datetime (`date` unix command) in your prompt.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) 提醒您补水的插件.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) 显示当前文件夹的 npm 包版本的插件.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's Rust version when either a `.rs` or `Cargo.toml` is present.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - 用于快速下载 jQuery 库的插件 [https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com](https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com).
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - Lets you use [zeus](https://github.com/burke/zeus) 使用普通的 rails 命令.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - Manage Go installations with gimme.
* [git-acp](https://github.com/MenkeTechnologies/zsh-git-acp) - Take the current command line as the commit message and then run git pull, add, commit and push with one keystroke.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) - 轻松将上游远程添加到您的 `git` 叉.
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of oh-my-zsh.
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used `git` commands.
* [git-branches](https://github.com/Schroefdop/git-branches) - 制作一个 `git` 分支菜单，您可以切换到该菜单，而无需输入长分支名称.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - Enhance `git` completion to include in the remotes completion (e.g. from `git clone`) any URL in the clipboard.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Extra `git` helper scripts packaged as a plugin.
* [git-flow-avh](https://github.com/nekofar/zsh-git-flow-avh) - Adds short aliases for the `git-flow` commands.
* [git-fuzzy](https://github.com/bigH/git-fuzzy) - A CLI interface to `git` that relies heavily on [`fzf`](https://github.com/junegunn/fzf).
* [git-ignore](https://github.com/laggardkernel/git-ignore) - Generates `.gitignore` files from gitignore.io **offline**. [fzf](https://github.com/junegunn/fzf)、完成、预览一体化.
* [git-is-clean](https://github.com/aubreypwd/zsh-plugin-git-is-clean) - This function will return true or false depending on if it finds out your repo is dirty or not.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub.
* [git-lfs](https://github.com/nekofar/zsh-git-lfs) - Adds short aliases for the git-lfs commands.
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - Adds some functions for `git`.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for `git` user.email.
* [git-prune (diazod)](https://github.com/diazod/git-prune) - Allows you to delete all branches that are already merged in your local repository and/or that were merged in your remote origin repository.
* [git-prune (seinh)](https://github.com/Seinh/git-prune) - 简化删除合并分支的插件.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) - Adds `git-squash-branch` and `git-remove-merged` commands.
* [git-secret](https://github.com/sobolevn/git-secret) - 一个 bash 工具，用于将您的私人数据存储在 `git` 存储库中。
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - Adds extra `git` commands to make some common `git` usages more efficient.
* [git-smart-commends-wrapper](https://github.com/jelek21/omz-git-smart-commands) - 包裹 [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) to make it compatible with the oh-my-zsh plugins system.
* [git-sync](https://github.com/caarlos0/zsh-git-sync) - A ZSH plugin to sync `git` repositories and clean them up.
* [git-tree](https://github.com/dehlen/git-tree-zsh) - [fzf](https://github.com/junegunn/fzf) powered `git worktree` helper.
* [git-worktree](https://github.com/alexiszamanidis/zsh-git-worktree) - Wraps some `git worktree` operations for simplicity and productivity. Includes `fzf` tooling.
* [git](https://github.com/davidde/git)  - 替换股票 oh-my-zsh git 插件. 提供了不少有用的别名和函数. 替换默认插件的动机源于它带有一些不一致的事实，这使得一些流行的命令相当不直观，所以这个插件使别名保持一致.
* [gitcd (SukkaW)](https://github.com/SukkaW/zsh-gitcd) - 将命令添加到 `git clone` 存储库和 `cd` 到结果目录.
* [gitcd (viko16)](https://github.com/viko16/gitcd.plugin.zsh) - Automatically `cd` to a `git` working directory after cloning it.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of oh-my-zsh gitfast plugin.
* [gitgo (grimmbraten)](https://github.com/grimmbraten/gitgo) - Make it easier to switch between `git` branches.
* [gitgo (ltj)](https://github.com/ltj/gitgo) - Open a Github/Gitlab repository in your browser from the command line (macOS only).
* [github](https://github.com/shakir-abdo/zsh-github-plugin) - Fork of the original [github plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/github) embedded in [oh-my-zsh](http://ohmyz.sh/).
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - 用于创建 `.gitignore` 文件的插件.
* [gitio](https://github.com/denysdovhan/gitio-zsh) - A ZSH plugin for generating a GitHub short URL using [git.io](https://git.io).
* [gitstatus](https://github.com/Insert-Creative-Name-Here/gitstatus.zsh) - 可以轻松地在提示中显示您的 `git` 状态.
* [gitsync](https://github.com/washtubs/gitsync) - ZSH plugin to improve workflows for one person developing on the same repository on multiple machines.
* [goenv (CDA0)](https://github.com/CDA0/zsh-goenv/blob/master/zsh-goenv.plugin.zsh) - Plugin for installing, updating and loading goenv.
* [goenv (bbenne10)](https://github.com/bbenne10/goenv) - Manage `$GOPATH` similarly to Python's virtualenvwrapper.
* [going_places](https://github.com/or17191/going_places) - 一个有助于使用、创建和维护 shell 位置列表的插件.
* [golinks](https://github.com/slessans/oh-my-zsh-golinks-plugin) - Launch golinks from your terminal.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - Plugin that tries to do the right thing when it comes to setting up the GPG agent to act as an SSH agent as well on macOS.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) - ZSH plugin to encrypt and decrypt files or directories in place.
* [grep2awk](https://github.com/joepvd/grep2awk) - ZLE widget to transform `grep` command into `awk` command.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - 为 `grunt` 添加自动完成功能.
* [gsh](https://github.com/cjayross/gsh) - Collection of helper functions for `git`
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - terminal plugin for [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [gtr](https://github.com/Zocker1999NET/zsh-gtr) - Allows fast tagging of a release in git using the tag name **release-YYYY-MM-DD-HH-MM** and headline **Release YYYY-MM-DD HH:MM**.
* [guish](https://github.com/gcarrarom/oh-my-guish) - Collection of utility functions and aliases.
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - Wrapper plugin for [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
* [gunstage](https://github.com/LucasLarson/gunstage)  - 至少有八种方法可以在 `git` 存储库中取消暂存文件. 这是一个用于撤消 `git add` 的命令行 shell 插件.
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - A gvm (Go version manager) plugin for ZSH.
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - Provides autocompletion for `gvm` (Groovy enVironment Manager).
* [hab](https://github.com/alexdesousa/hab) - 如果在更改到新目录时发现文件`.envrc` 中定义的操作系统环境变量，则自动加载它.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - Outputs a hacker quote randomly when you open a terminal.
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - 为 hadoop 函数添加一些方便的别名.
* [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH 插件 [hanami](http://hanamirb.org) 项目.
* [hangul](https://github.com/gomjellie/zsh-hangul) - Auto correct hangul(한글, korean) to english when it was supposed to be typed english. 영어를 타이핑 해야되는데 한글로 타이핑된경우 자동으로 수정합니다.
* [hbt](https://github.com/lzambarda/hbt) - Heuristic ZSH suggestion system based on past command usage.
* [hints](https://github.com/joepvd/zsh-hints) - Display glob and parameter flags and other non completable info right under your editing buffer.
* [hipchat](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell.
* [hist](https://github.com/marlonrichert/zsh-hist) - Edit your history in ZSH, without ever leaving the command line.
* [histdb](https://github.com/larkery/zsh-histdb) - Stores your history in an SQLite database. Can be integrated with [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions).
* [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer) - Enhances history search with more interaction and a multiline selection menu. Requires nodejs.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter) - Allows you to specify patterns that will automatically exclude commands from being inserted into your permanent history. Particularly useful for preventing secrets being written.
* [history-here](https://github.com/leonjza/history-here) - Binds `^G` to quickly toggle the current shell history file location.
* [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) - Captures the PageUp key and uses `dialog` to open a popup menu with the history, so the user can interactively navigate through it and pick the history line to bring back to the prompt.
* [history-search-multi-word](https://github.com/zdharma-continuum/history-search-multi-word) - ZSH 的语法突出显示的多词历史搜索器，绑定到 Ctrl-R，具有高级功能（例如，将历史条目撞到历史顶部）.
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after `zsh-syntax-highlighting`, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md.
* [history-sync](https://github.com/wulfgarpro/history-sync) - An Oh My Zsh plugin for GPG encrypted, Internet synchronized ZSH history using `git`.
* [history](https://github.com/b4b4r07/zsh-history) - Extend history so that it can be queried by SQL.
* [hitokoto](https://github.com/derry96/hitokoto) - Displays a random quote from [hitokoto.cn](https://hitokoto.cn/).
* [homeassistant-cli](https://github.com/frosit/zsh-plugin-homeassistant-cli) - Provides completion and (configuration) helpers for the [Home Assistant Command-line interface (hass-cli)](https://github.com/home-assistant/home-assistant-cli). and allows command line interaction with [Home Assistant](https://home-assistant.io/) 实例.
* [homebrew](https://github.com/digitalraven/omz-homebrew) - 插件 [homebrew](https://brew.sh) that supplements the one built into oh-my-zsh and can safely run with it enabled.
* [hooks](https://github.com/willghatch/zsh-hooks) - 添加缺少的钩子 - 用于插件和个人使用.
* [host-switch](https://github.com/LockonS/host-switch) - Make it easier to switch in different `/etc/hosts` files during development.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - A simple plugin for adding `hub` ci-status to your ZSH theme.
* [hub](https://github.com/soraliu/zsh-hub) - ZSH plugin for forking model.
* [igit](https://github.com/ytakahashi/igit) - Interactive `git` commands using [fzf](https://github.com/junegunn/fzf).
* [ing](https://github.com/rummik/zsh-ing) - 简化的“ping”输出.
* [instant-repl](https://github.com/jandamm/instant-repl.zsh) - Activate a REPL for any command in your current ZSH session.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - Fish-like interactive tab completion for `cd`.
* [iosctl](https://github.com/obayer/iosctl) - 快速访问正在运行的模拟器的应用程序、数据和日志.
* [ipip](https://github.com/SukkaW/zsh-ipip) - 插件 [IPIP](https://en.ipip.net).
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - Adds function to set the tab color in iTerm2 and can automatically change color based on cwd or command being executed.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - Automatically changes iTerm 2 tab color based on the current working directory.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - Display iTerm2 feedback in the MacbookPro TouchBar (Current directory, git branch & status).
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - Manage your iTerm 2's color scheme from the command line.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - Set colors and titles of iTerm 2 tabs.
* [iterm2-utilities](https://github.com/decayofmind/zsh-iterm2-utilities) - 帮助下载各种 iTerm2 实用程序，让您无需克隆整个 iterm2 网站存储库或依赖其他可能不同步的存储库.
* [iterm2](https://github.com/laggardkernel/zsh-iterm2) - 将 iTerm 的 ZSH 集成脚本打包到 ZSH 插件中，以避免污染您的 $HOME 目录，仅增加 2ms 的时间可以忽略不计.
* [jabba](https://github.com/2m/zsh-jabba) - 添加外壳集成代码和完成 [jabba](https://github.com/shyiko/jabba) Java version manager.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - 添加 `setjdk` 命令，以便您可以在 jdk 的不同版本之间轻松切换.
* [javaVersions](https://github.com/miguefl/javaVersions) - Change between different java versions with a single command.
* [jdk-switch](https://github.com/LockonS/jdk-switch) - A macOS-only plugin for switching between jdk versions.
* [jenkins](https://github.com/tomplex/jenkins-zsh) - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - A ZSH plugin for lazy loading of jEnv.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - Adds commands for [jHipster](https://www.jhipster.tech/).
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - 从命令行创建 JIRA 票证.
* [jq (northismirror)](https://github.com/NorthIsMirror/jq-zsh-plugin) - 交互式构建 [jq](https://stedolan.github.io/jq/) expressions to give you `jq` superpowers.
* [jq (reegnz)](https://github.com/reegnz/jq-zsh-plugin) - 交互式构建 [jq](https://stedolan.github.io/jq/) 表达式.
* [jvm](https://github.com/mgryszko/jvm) - 允许在 macOS 上选择 JDK.
* [k3d](https://github.com/dwaynebradley/k3d-oh-my-zsh-plugin) - 添加别名和选项卡完成 [k3d](https://k3d.io/).
* [k](https://github.com/supercrabtree/k) - Directory listings for ZSH with `git` status decorations.
* [kctl](https://github.com/yzdann/kctl) - Add helper aliases for `kubectl`.
* [kill-node](https://github.com/vmattos/kill-node) - ZSH plugin for murdering `node` process families.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - 用于 oh-my-zsh 的 KitsuneBook 插件.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
* [kube-aliases](https://github.com/Dbz/kube-aliases) - Adds functions and aliases to make working with `kubectl` more pleasant.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - ZSH plugin for `kubectl` that adds current context and namespace.
* [kubecolor (devopstales)](https://github.com/devopstales/kubecolor-zsh) - Adds aliases for the `kubecolor` command.
* [kubecolor (droctothorpe)](https://github.com/droctothorpe/kubecolor) - Simplify and colorize the output of `kubectl get events -w`
* [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) - 用于管理 `kubectl` 的 ZSH 插件.
* [kubectx (ptavares)](https://github.com/ptavares/zsh-kubectx) - Installs and loads [kubectx](https://github.com/ahmetb/kubectx).
* [kubectx (unixorn)](https://github.com/unixorn/kubectx-zshplugin) - 自动安装 [kubectx](https://github.com/ahmetb/kubectx) and `kubens`.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) - 添加 [kubernetes](https://kubernetes.io) helper functions and aliases.
* [lando (joshuabedford)](https://github.com/JoshuaBedford/lando-zsh) - A collection of alias functions to enable the use of the CLIs within [Lando](https://docs.lando.dev) without having to type lando to access them.
* [lando (mannuel)](https://github.com/mannuel/lando-alias-zsh) - Adds aliases for various [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) commands.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - Provides an interface to [Laradock](http://laradock.io/)的工作区.
* [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) - Adds aliases for Laravel 6.
* [laravel-sail](https://github.com/ariaieboy/laravel-sail) - Adds shortcuts for `sail` commands.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - Add shortcuts for Laravel 5, 5.1, 5.2 & 5.3.
* [laravelx](https://github.com/rsthegeek/oh-my-zsh-laravelx) - Adds some aliases for common [Laravel](https://laravel.com/docs) commands.
* [last-working-dir-tmux](https://github.com/Curly-Mo/last-working-dir-tmux) - Keeps track of the last used working directory globally and per tmux session and automatically jumps into it for new shells.
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) - 破解版本的副本 [oh-my-zsh](http://ohmyz.sh/). Keeps track of the last used working directory and automatically jumps into it for new shells.
* [lazyload](https://github.com/qoomon/zsh-lazyload) - Lazy load commands and speed up start up time of ZSH.
* [learn](https://github.com/MenkeTechnologies/zsh-learn) - MySQL/MariadB 中的学习集合，用于保存、查询和测验您学到的所有内容.
* [lesaint-git](https://github.com/lesaint/lesaint-git) - Replacement `git` plugin for Oh-My-Zsh-compatible frameworks.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - Maven plugins for oh-my-zsh.
* [liferay](https://github.com/david-gutierrez-mesa/liferay-zsh) - Adds scripts for [liferay](https://github.com/liferay/liferay-portal) 发展.
* [linkfile](https://github.com/JaumeRF/linkfile-zsh) - Add shortcuts to your favorite directories.
* [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) - 打开终端时输出随机的 Linus Torvalds 咆哮。
* [listbox](https://github.com/gko/listbox) - Listbox element for shell.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - Allows searching for [Sublime Text](https://www.sublimetext.com) projects and opens them in Sublime.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum) - Generate lorem ipsum text on the command line. Gets its data from [lipsum.com](https://www.lipsum.com).
* [ls](https://github.com/zpm-zsh/ls) - Colorizes the output of `ls`.
* [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack is a logging interface for shell scripts.
* [lux](https://github.com/pndurette/zsh-lux) - ZSH plugin to toggle the light & dark modes of macOS and other items and applications via the `lux` command. Highly customizable: included items can be configured by defining variables. Highly extensible: items can be added by defining functions. Includes `macos_is_dark` helper function to determine if the macOS dark mode is active for use in theming.
* [mac-packaging](https://github.com/Temikus/mac-packaging) - 一组用于企业 Mac 打包的常用功能 [Munki](https://www.munki.org/munki/).
* [macos (joow)](https://github.com/joow/macos) - A ZSH plugin for macOS.
* [macos (zshzoo)](https://github.com/zshzoo/macos) - 适用于 MacOS 用户的 ZSH 好东西.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) - Makes it easy to work with Docker and Magento 2. Speeds up and simplifies common commands like clean cache, setup upgrade, compile di and much more in Magento 2 on containers.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - 添加 `m2` 函数来运行 magento 二进制文件，添加选项卡完成.
* [magic-enter](https://github.com/zshzoo/magic-enter) - Make your enter key magical by binding a ZSH command to it.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) - A zle tweak for emulating `...'==`../..' etc.
* [markedit](https://github.com/zakariaGatter/MarkEdit) - Mark files and edit them with autocompletion for existing marks.
* [markgate](https://github.com/zakariaGatter/MarkGate) - Allows you to mark directories so you can jump directly to them.
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - A fork of the oh-my-zsh maven plugin.
* [media-sync](https://github.com/redxtech/zsh-media-sync) - A plugin to facilitate copying media between two rclone locations.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) - Extracted from oh-my-zsh so you can use it without oh-my-zsh.
* [mfunc](https://github.com/hlohm/mfunc) - Allows you to define persistent functions on-the-fly, without the need to add them to your config files. These functions are permanently available until you delete them.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - A ZSH plugin for switching command line between normal mode and `vi` mode.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - ZSH plugin for monorepo management.
* [monthrename](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) - Renames month names to numbers in filenames.
* [mouse-status](https://github.com/gryffyn/mouse-status) - Changes mouse color based on status code, uses libratbag.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - Metasploit handler plugin for starting handlers easily.
* [mvn-contexts](https://github.com/artemy/zsh-mvn-contexts) - 允许在 Maven 配置之间快速切换.
* [mylocation](https://github.com/fALKENdk/mylocation) - A plugin to show your current location based on your IP address.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - Adds color for mysql tables.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - 增加了一些处理mysql的函数.
* [n](https://github.com/gretzky/n.zsh) - Auto-switches node versions based on project environment using [n](https://github.com/tj/n).
* [namelink](https://github.com/jthat/zsh-namelink) - Provides an automatically synchronized mapping of filesystem entries (typically symbolic links) in a set of directories to their counterparts in the named directory hash.
* [navi](https://github.com/icatalina/zsh-navi-plugin/) - 插件 [navi](https://github.com/denisidoro/navi).
* [navigation-tools](https://github.com/zdharma-continuum/zsh-navigation-tools) - Adds `htop`-like kill, directory bookmarks browser, a multi-word incremental history searcher and more.
* [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) - 从模板生成文件.
* [newvwp](https://github.com/aubreypwd/zsh-plugin-newvwp) - Spins up a new WordPress site using Valet.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - 将退出状态代码映射到人类可读的字符串.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) - Plugin that lets you use ZSH as the default shell in a `nix-shell` environment.
* [nnvm](https://github.com/torifat/nnvm)  - 基于 `.nvmrc` 自动切换节点版本. 需要 [n](https://github.com/tj/n).
* [node-env-installer](https://github.com/shiro-saber/node-env-installer) - Uses `nvm` to install new versions and modules for the current project.
* [node-path](https://github.com/andyrichardson/zsh-node-path) - 自动将当前目录的“npm bin”添加到路径中.
* [node](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty's nodejs plugin for ZSH with caching of `nvm` completions and autoloading of `nvm` if present.
* [nodenv (c-uo)](https://github.com/C-uo/zsh-nodenv) - Looks for nodenv in your working directory and loads it when found.
* [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) - 自动加载 `nodenv` 及其完成到 shell.
* [nodenv (mattberther)](https://github.com/mattberther/zsh-nodenv) - Installs, updates and loads `nodenv`. Inspired by zsh-rbenv.
* [nohup](https://github.com/micrenda/zsh-nohup) - 按 `Ctrl-H` 将`nohup` 添加到当前命令.
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS 用户知道试图找出在他们的 macOS 版本上实际刷新 DNS 缓存的命令的痛苦，而这个插件让这种烦恼消失了.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - Inspired by [terminal_velocity](https://www.seanh.cc/terminal_velocity/), it provides a fast interface to create and access a set of [Markdown](https://en.wikipedia.org/wiki/Markdown) text files inside a directory.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - 在 ZSH 中提供快速的笔记编辑体验.
* [notify (luismayta)](https://github.com/luismayta/zsh-notify) - Notifications for ZSH with auto installation of dependencies and r2d2 sounds.
* [notify (marzocchi)](https://github.com/marzocchi/zsh-notify) - ZSH 的插件（在 macOS 和 Linux 上），如果终端应用程序在后台（或命令的终端），当命令以非零退出状态终止或完成时间超过 30 秒时发布桌面通知选项卡处于非活动状态）.
* [npm (igoradamenko)](https://github.com/igoradamenko/npm.插入.zsh) - Add `npm` aliases & command completion. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npm (trystan2k)](https://github.com/trystan2k/zsh-npm-plugin) - Adds `npm` aliases. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npm (zfben)](https://github.com/zfben/zsh-npm) - Use `n` as `npm` aliases with `noglob` prefix and more. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npms](https://github.com/torifat/npms) - Utility powered by `fzf` for using npm scripts interactively. Requires [fzf](https://github.com/junegunn/fzf) and [jq](https://stedolan.github.io/jq/).
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - Calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling `nvm` which node to use.
* [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy) - Plugin for lazy loading of oh-my-zsh's **nvm** plugin. It supports lazy-loading `nvm` for more than one binary/entrypoint, with the defaults being `nvm`, `node` and `npm`.
* [nvm](https://github.com/lukechilds/zsh-nvm) - ZSH plugin for installing, updating and loading `nvm`.
* [oath](https://github.com/alexdesousa/oath) - Manages 2FA authentication 6 digit tokens. It was highly inspired by this article about [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
* [oclif completion generator](https://github.com/MunifTanjim/oclif-plugin-completion) - Generates shell completions for commands lacking them.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - Turn your terminal into the matrix.
* [omz-themes-standalone](https://github.com/zshzoo/omz-themes-standalone) - Gives you the [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) themes without requiring everything else that comes with oh-my-zsh
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) - Open/Create projects in Jetbrains.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) - 从命令行打开拉取请求的 ZSH 插件.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - Add a few shortcuts to common openshift origin (oc) actions.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` aliases.
* [operator](https://github.com/nivv/operator-theme) - 干净简单的主题，最适合搭配 [Menlo for Powerline](https://github.com/abertsch/Menlo-for-Powerline).
* [opp](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for ZSH.
* [opt-path](https://github.com/jreese/zsh-opt-path) - Automatically add `~/opt` subpaths to your `$PATH`.
* [osx-autoproxy](https://github.com/SukkaW/zsh-osx-autoproxy) - 根据 macOS 的系统偏好配置代理环境变量.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - 此插件添加了一些命令，用于在 macOS 安装上维护各种服务器程序.
* [osx](https://github.com/mwilliammyers/plugin-osx) - Add some common macOS related aliases and functions.
* [p10k-promptconfig](https://github.com/doctormemes/p10k-promptconfig) - 通过在 `.zshrc` 文件中定义 `P10K_PROMPT` 变量，添加了在 Powerlevel10k 提示主题配置文件之间轻松切换的能力.
* [paci](https://github.com/iloginow/zsh-paci) - Plugin for archlinux package managers.
* [package-any-node](https://github.com/zdharma-continuum/zsh-package-any-node) - Easy installing of any Node modules inside the plugin directory, exposing their binaries via shims (i.e.: forwarder scripts) created automatically by [Bin-Gem-Node](https://github.com/zdharma-continuum/z-a-bin-gem-node) annex.
* [packer](https://github.com/BreakingPitt/zsh-packer) - Adds aliases and auto-completes for Hashicorp [packer](https://www.packer.io/).
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) - Background notifications for long running commands. Supports Elementary OS Freya.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) - Keeps passwords from entering your command line history.
* [path-ethic](https://github.com/sha1n/path-ethic) - Helps manage your `$PATH` quickly and easily. Doesn't touch your existing `.zshrc`, `.zprofile`, but adds on top of your existing environment instead.
* [pctl](https://github.com/ytet5uy4/pctl) - Toggle the environment variables for proxying.
* [peco-history](https://github.com/jimeh/zsh-peco-history) - Search shell history with Peco when pressing ctrl+R.
* [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) - Aliases and functions for the lazy penetration tester.
* [per-directory-history](https://github.com/jimhester/per-directory-history) - Per directory history for ZSH, as well as global history, and the ability to toggle between them with `^G`.
* [percol](https://github.com/robturtle/percol.plugin.zsh) - Interactively and incrementally search history/resume background jobs using [percol](https://github.com/mooz/percol).
* [perlbrew](https://github.com/tfiala/zsh-perlbrew/) - 安装 [perlbrew](https://perlbrew.pl/) if not already installed and initializes it for your shell.
* [pew](https://github.com/shosca/zsh-pew) - Sets up and manages Python virtualenvs using [pew](https://github.com/berdario/pew), automatically switches virtualenvs as you move directories.
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) - Adds utility functions to work with [PostgreSQL](https://www.postgresql.org/).
* [ph-marks](https://github.com/lainiwa/ph-marks) - Bookmark pornhub videos from your terminal.
* [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) - Automatically switch between php versions using [php-version](https://github.com/wilmoore/php-version) if an rc-file is present in a directory.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - 插件 [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) - Auto-load [phpenv](https://github.com/sptndc/phpenv) 及其完成.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - 插件 [PHPUnit](https://phpunit.de/).
* [pip-app](https://github.com/sharat87/pip-app) - Makes it easy to install python applications into distinct Python virtualenvs so they don't conflict with any other python requirements on your system.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) - Automatic [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a pipenv project.
* [pipx](https://github.com/thuandt/zsh-pipx) - 自动完成 [pipx](https://github.com/pypa/pipx).
* [pkenv](https://github.com/ptavares/zsh-pkenv) - Installs and loads [pkenv](https://github.com/iamhsa/pkenv.git)
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - Adds ibtool shortcuts to generate localized XIB files.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Visual Studio Code 插件，一个适用于 macOS、Windows 和 Linux 的文本编辑器.
* [plugin](https://github.com/darrenbutcher/plugin) - Creates custom oh-my-zsh plugins from a boilerplate template. Very oh-my-zsh centric, the generated plugins will need editing to work with other frameworks.
* [pnpm](https://github.com/ntnyq/omz-plugin-pnpm) - 为常见的 Pnpm 命令添加有用的别名.
* [poetry (darvid)](https://github.com/darvid/zsh-poetry) - Automatically activates and deactivates [Poetry](https://poetry.eustace.io/)-created python virtualenvs.
* [poetry (sudosabin)](https://github.com/sudosubin/zsh-poetry) - Enables poetry `$PATH` and autocompletions.
* [posh-git-bash](https://github.com/lyze/posh-git-sh) - Adds `git` status in your prompt.
* [ppsmon](https://github.com/mzpqnxow/ppsmon)  - 读取 `/sys/class/net/$interface/` 以跟踪数据包传输速率. 它将当前速率存储到 RAM 支持的文件系统中的文件中，在该文件系统中可以轻松访问它以在 shell 提示中显示. 由于使用了 `/sys`，因此仅适用于 Linux.
* [pr-cwd](https://github.com/zpm-zsh/pr-cwd)  - 使用当前工作目录创建一个全局变量. 插件与集成 [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
* [pr-eol](https://github.com/zpm-zsh/pr-eol) - Displays an EOL symbol which can be embedded in the prompt.
* [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) - Adds a variable you can use to display the execution time of the last command run.
* [pr-git](https://github.com/zpm-zsh/pr-git) - 创建一个带有 `git` 状态信息的全局变量，可以在提示中显示.
* [pr-is-root](https://github.com/zpm-zsh/pr-is-root) - Sets an environment variable you can use in a custom prompt when running as root.
* [pr-jobs](https://github.com/zpm-zsh/pr-jobs) - Creates an environment variable which can be used to display background job information in a custom prompt.
* [pr-node](https://github.com/zpm-zsh/pr-node) - Sets an environment variable which can be used to display nodeJS information in a custom prompt.
* [pr-return](https://github.com/zpm-zsh/pr-return) - Plugin for ZSH who displays the exit status of the last command run.
* [presenter-mode](https://github.com/idadzie/zsh-presenter-mode) - Expands aliases during presentations. It also increases the terminal window's contrast to enhance visibility.
* [pretty-time (sindresorhus)](https://github.com/sindresorhus/pretty-time-zsh) - 将秒转换为人类可读的字符串：165392 → 1d 21h 56m 32s.
* [pretty-time (zpm-zsh)](https://github.com/zpm-zsh/pretty-time) - 将原始秒数转换为人类可读的字符串.
* [print-alias](https://github.com/brymck/print-alias) - Prints commands with aliases expanded whenever you use an alias at the command line.
* [printc](https://github.com/philFernandez/printc) - 允许您通过简单的“printc”调用以 RGB 空间中的任何颜色进行打印.
* [profile-secrets](https://github.com/gmatheu/shell-plugins) - Securely keep sensitive variables (api tokens, passwords, etc) as part of your terminal init files. Uses gpg to encrypt/decrypt the file with your secrets.
* [project (gko)](https://github.com/gko/project) - Create node/python/ruby project both locally and on github(private or public repository).
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - Plugin for managing projects.
* [prompt-generator](https://github.com/the10thWiz/zsh-prompt-generator) - Generates custom themes. Some generated themes require powerline-compatible fonts.
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - Quickly enable and disable proxy shell environment settings.
* [proxy](https://github.com/SukkaW/zsh-proxy) - 为某些包管理器和软件配置代理设置.
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - Plugin for lazy-loading `pyenv` in ZSH.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy)  - 延迟加载 pyenv. 第一次调用 `pyenv` 时执行初始的 `eval &quot;$(pyenv init -)&quot;`.
* [pyenv](https://github.com/mattberther/zsh-pyenv) - Inspired by zsh-rbenv. Installs, updates or loads `pyenv`, and adds extra functionality.
* [pyvenv-fast](https://github.com/ACmyles/pyvenv-fast) - Launch a Python venv with one command. Designed for use with [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv).
* [q (cal2195)](https://github.com/cal2195/q) - Add `vim`-like macro registers to your ZSH shell.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - Tail/remove the temp file for [Q](https://github.com/y0ssar1an/q), the Dirty Debugging Tool.
* [qiime2](https://github.com/misialq/zsh-qiime2) - Adds functions and aliases to make working with [Quiime 2](https://qiime2.org/) easier.
* [quer-ps1](https://github.com/ya0201/qwer-ps1) - A highly extendable manager for your ZSH prompt
* [quoter](https://github.com/pxgamer/quoter-zsh) - Display a random quote when opening a new terminal session.
* [quotify](https://github.com/damofthemoon/zsh-quotify) - Displays inspiring coding quotes from our pairs when starting up.
* [randeme](https://github.com/ex-surreal/randeme)  - 为每个会话选择一个随机主题. 如果您不喜欢所选主题，您可以运行 `randeme_rm` 以不再显示该主题.
* [random-quotes](https://github.com/vkolagotla/zsh-random-quotes) - 显示随机报价或事实.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - Change the colour of your [Razer Mouse](https://openrazer.github.io/) based on the status of the last executed command. Requires [OpenRazer](https://openrazer.github.io) linux drivers.
* [rbenv (ecortinas)](https://github.com/ecortinas/zsh-rbenv) - Based on the [zsh-pyenv](https://github.com/mattberther/zsh-pyenv) 插入. 该插件将安装 rbenv 并使其随时可用
* [rbenv (elliottcable)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - 来自 oh-my-zsh 的 rbenv 插件的更快分支.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - 基于原始 oh-my-zsh rbenv 插件的变体.
* [rbenv (meroje)](https://github.com/Meroje/zsh-rbenv) - Inspired by [https://github.com/lukechilds/zsh-nvm/](https://github.com/lukechilds/zsh-nvm/), makes it easier to work with ruby rbenvs.
* [rc-files](https://github.com/0b10/rc-files) - 添加用于编辑各种 rc 文件的快捷功能.
* [recall](https://github.com/mango-tree/zsh-recall) - Makes using command history easier.
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - 如果它已被删除并重新创建，则重新进入工作目录的插件.
* [reload](https://github.com/aubreypwd/zsh-plugin-reload) - 添加快速重新加载您的`.zshrc`的功能.
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - A plugin which displays reminders above every prompt.
* [replace-multiple-dots](https://github.com/momo-lab/zsh-replace-multiple-dots) - Converts `...` to `../..`
* [revolver](https://github.com/molovo/revolver) - A progress spinner for ZSH scripts.
* [riddle-me](https://github.com/vkolagotla/zsh-riddle-me) - 显示随机谜语.
* [ripz](https://github.com/jedahan/ripz)  - 提醒您您的别名，以便您更多地使用它们. 依赖于取决于 [ripgrep](https://github.com/BurntSushi/ripgrep).
* [robo](https://github.com/shengyou/robo-zsh-plugin) - 一个 ZSH 插件 [Robo](https://github.com/consolidation/robo/).
* [rockz](https://github.com/aperezdc/rockz) - Lua + LuaRocks virtual environment manager based upon VirtualZ.
* [rust](https://github.com/cowboyd/zsh-rust) - Configure your rust toolchain, installing [rustup](https://rustup.rs) if it is not currently installed already.
* [rvm](https://github.com/johnhamelink/rvm-zsh) - 启动 RVM 并添加在用户的 `$PATH` 中可访问的 ruby​​gem 二进制文件（如指南针）.
* [safe-kubectl](https://github.com/benjefferies/safe-kubectl) - 在运行 `kubectl` 时添加一些安全性，方法是在自上一个 `kubectl` 命令后的可定义秒数后警告您所处的上下文.
* [safe-paste](https://github.com/oz/safe-paste) - A safe-paste plugin. See Conrad Irwin's [bracketed-paste](https://cirw.in/blog/bracketed-paste) 博客文章.
* [safe-rm](https://github.com/mattmc3/zsh-safe-rm) - Add safe-rm functionality so that `rm` will put files in your OS's trash instead of permanently deleting them.
* [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) - When using multiple AWS profiles, e.g. different accounts for your stages (development, pre-prod, prod), can be used to determine which profile is currently exported and if the token is still valid.
* [saml2aws](https://github.com/onyxraven/zsh-saml2aws) - Add support for [saml2aws](https://github.com/Versent/saml2aws).
* [sandboxd](https://github.com/benvan/sandboxd) - Speed up your `.zshrc` & shell startup with lazy-loading by only running setup commands (e.g. `eval "$(rbenv init -)"`, etc) when you need them.
* [saneopt](https://github.com/willghatch/zsh-saneopt) - Sane defaults for ZSH options, in the spirit of vim-sensible.
* [sb-upgrade](https://github.com/redxtech/zsh-sb-upgrade) - 脚本自动更新种子箱上的应用程序.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) - Show current `chroot` name in your prompt.
* [sdkman](https://github.com/ptavares/zsh-sdkman) - 安装 [sdkman](https://github.com/sdkman) and adds completions and aliases for it.
* [sealion](https://github.com/xyproto/sealion) - 允许您设置刷新提示时将出现在终端中的提醒.
* [search-directory-history](https://github.com/cmaahs/search-directory-history) - Allows complex search of per-directory history created using the [per-directory-history](https://github.com/jimhester/per-directory-history) 插入.
* [sed-sub](https://github.com/MenkeTechnologies/zsh-sed-sub) - Adds keybindings to do global search and replace on current command line.
* [send](https://github.com/robertzk/send.zsh) - Single command to `git add`, `git commit`, and `git push` for much faster `git` workflow.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - Adds many `git` aliases and helper shell functions.
* [session-sauce](https://github.com/ChrisPenner/session-sauce) - An fzf interface for tmux session creation and management for all your projects.
* [setenv](https://github.com/kalpakrg/setenv) - Runs a script when you change directories.
* [shelf](https://github.com/ecmma/shelf) - 可用于使用助记符为任何文件添加书签和直接访问的实用程序.
* [shellfirm](https://github.com/kaplanelad/shellfirm) - Shellfirm is a handy utility to help avoid running dangerous commands without an extra step of approval. When risky patterns is detected you will immediately get a small prompt challenge that will double verify your action.
* [show-path](https://github.com/redxtech/zsh-show-path) - Provides a function shows the `$PATH` line by line.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - Plugin to easily start python `SimpleHTTPServer` and `SimpleHTTPSServer`.
* [skim](https://github.com/hackerchai/skim-zsh) - Adds support for [skim](https://github.com/lotabout/skim)
* [slugify](https://github.com/lashoun/slugify) - 将文件名和目录转换为网络友好格式.
* [smart-cd](https://github.com/dbkaplun/smart-cd) - Runs `ls` and `git status` after chpwd.
* [smartinput](https://github.com/momo-lab/zsh-smartinput) - 当您键入括号或引号时，会自动添加相应的结束括号/引号.
* [smile](https://github.com/fundor333/smile) - Adds function to display random smileys.
* [snippets](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion.
* [solarized-man](https://github.com/zlsun/solarized-man) - A modified version of oh-my-zsh's plugin colored-man-pages, optimized for the [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) theme in the terminal.
* [spack](https://github.com/Game4Move78/zsh-spack) - Includes some useful aliases and functions for loading/unloading [Spack](https://github.com/spack/spack) - 生成的模块. 由于它使用了 `module` 命令，它比 `spack load` 更有效.
* [ssh-connect](https://github.com/gko/ssh-connect) - A simple `ssh` manager.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - Plugin for `ssh`.
* [sshukh](https://github.com/anatolykopyl/sshukh-zsh-plugin) - Will update your `known_hosts` file when you `ssh` into a server.
* [startify](https://github.com/NorthIsMirror/zsh-startify) - Shows recently used `vim` files, shell-util files, active `tmux` sessions, recently-run `git` commands and more.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - Print the time it takes for the shell to start up.
* [stashy](https://github.com/MisterRios/stashy) - Plugin that simplifies using `git stash`.
* [statify](https://github.com/vladmrnv/statify) - Plugin that does basic statistical analysis.
* [sublime](https://github.com/valentinocossar/sublime) - 与 Oh My Zsh 的官方 Sublime 插件相同，但这会在当前 Sublime 窗口中打开文件（如果已经打开了一个文件）.
* [sudo](https://github.com/hcgraf/zsh-sudo)  - 来自 oh-my-zsh 的 `sudo` 插件，提取为独立的. 在 emacs 模式或 vi 命令模式下按 *ESC-ESC* 在当前/上一个命令之前切换 `sudo`.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - 使用 ZSH 的后缀别名直接在 shell 中打开文件。
* [svn-n-zsh](https://github.com/khrt/svn-n-zsh-plugin) - 重写股票 oh-my-zsh svn 插件.
* [switch-git](https://github.com/robin-mbg/switch-git) - Easy switching between `git` repositories. Just type `sgr <some part of you repo's name>`, press enter and you're there.
* [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) - Symfony 2 和 3 的 ZSH 插件.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - 使用 dircolors 实时突出显示 ZSH 语法.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your ZSH. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgets without typing commands.
* [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard) - Adds key bindings support for ZLE (Zsh Line Editor) clipboard operations for vi emulation keymaps. It works under Linux, macOS and Android (via Termux).
* [systemd](https://github.com/le0me55i/zsh-systemd) - Adds many aliases for `systemd`.
* [t32](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [tab-title](https://github.com/trystan2k/zsh-tab-title)  - 根据当前目录或正在运行的进程设置终端标签标题. 分叉自 [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh)
* [tailf](https://github.com/rummik/zsh-tailf) - Adds `tailf` function with prefixed newlines instead of trailing newlines.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - Auto-completes task numbers for taskbook.
* [terminal-app](https://github.com/the8/terminal-app.zsh) - A plugin for integrating with the new El Capitan Terminal.app features.
* [terminal-title](https://github.com/AnimiVulpis/zsh-terminal-title) - Adds a `set-term-title` function you can use to title terminal windows.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - 计算并显示通过终端运行了多少命令的插件.
* [termux](https://github.com/zpm-zsh/termux) - Adds compatibility for [Termux](https://termux.com/)
* [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) - Add terraform workspace to prompt.
* [terraform (jsporna)](https://github.com/jsporna/terraform-zsh-plugin) - Extends the original oh-my-zsh plugin with aliases and tab completions. Adds workspace (when not default) to prompt.
* [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) - Add convenience aliases for [terraform](https://terraform.io/)，选项卡完成和辅助功能，以在提示中添加您的 terraform 工作区.
* [terraform (pbar1)](https://github.com/pbar1/zsh-terraform) - Terraform convenience functions and aliases for ZSH.
* [terraform (thuandt)](https://github.com/thuandt/zsh-terraform) - Adds convenience aliases for `terraform`, along with completions for `terraform` and `terragrunt`.
* [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - 插件 [Terragrunt](https://github.com/gruntwork-io/terragrunt), a thin wrapper for [Terraform](https://terraform.io/) 提供额外的工具.
* [tfenv](https://github.com/CDA0/zsh-tfenv) - Installs, updates, and loads tfenv inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)
* [tfswitch](https://github.com/ptavares/zsh-tfswitch) - Installs and loads [tfswitch](https://github.com/warrensbox/terraform-switcher).
* [tgswitch](https://github.com/ptavares/zsh-tgswitch) - Installs and loads [tgswitch](https://github.com/warrensbox/tgswitch).
* [thefuck](https://github.com/laggardkernel/thefuck) - Loads [thefuck](https://github.com/nvbn/thefuck) (a tool which corrects your previous command) with cache support, which reduces the loading time dramatically.
* [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) - Convenience functions for working with [theia-ide](https://github.com/theia-ide/theia).
* [tig](https://github.com/MenkeTechnologies/zsh-tig-plugin) - Adds a few advanced bindings for [tig](https://github.com/jonas/tig) and also provides a `tig-pick` script.
* [timewarrior](https://github.com/svenXY/timewarrior) - Adds support for [timewarrior](https://timewarrior.net/), a time-tracking application.
* [tipz](https://github.com/molovo/tipz) - Displays your alias if you have an alias for the command you just ran, similarly to [alias-tips](https://github.com/djui/alias-tips).
* [title](https://github.com/zpm-zsh/title) - Allows you to set a terminal window title.
* [titles](https://github.com/jreese/zsh-titles) - Automatic window and tab titles for [tmux](https://tmux.github.io) and xterm-compatible terminals.
* [tm](https://github.com/kjhaber/tm.zsh) - 简化创建新 [tmux](https://tmux.github.io) sessions, attaching to existing sessions, switching between sessions, and listing active sessions.
* [tmux-auto-title](https://github.com/mbenford/zsh-tmux-auto-title) - Automatically sets the title of windows/panes as the current foreground command.
* [tmux-multisession](https://github.com/nichus/zsh-tmux-multisession) - 插件 [tmux](https://tmux.github.io) 支持单个服务器进程上的多个会话.
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - Rename [tmux](https://tmux.github.io) windows automatically.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - Simple plugin for using [tmux](https://tmux.github.io) with ZSH.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - Open files in a running `vim` (or NeoVim) session, from an adjacent [tmux](https://tmux.github.io) pane.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - Create unified terminal titles for `tmux`, ZSH, and Vim/NVIM, modular.
* [tmux](https://github.com/zpm-zsh/tmux) - 插件 [tmux](https://tmux.github.io).
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) - Simple ZSH plugin to have a R-EP-L [tmux](https://tmux.github.io) session.
* [toggl](https://github.com/natterstefan/toggl-zsh-plugin) - Adds a `toggl-week` command to display the total working hours tracked on [toggl.com](https://toggl.com)
* [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix)  - 添加一个小部件以切换命令的前缀. 默认情况下，将 Alt+s 绑定到带有 `sudo` 的命令前缀.
* [traista](https://github.com/odgon/traista) - Includes `git` status decorations and color-coded exit status of the last command run. Better with dark terminal themes.
* [travis](https://github.com/denolfe/zsh-travis) - Opens the Travis CI page for the current repo if one exists.
* [tre](https://github.com/redxtech/zsh-tre) - Makes using [tre](https://github.com/dduan/tre#editor-aliasing) easier.
* [tsm](https://github.com/RobertAudi/tsm) - Adds a [tmux](https://tmux.github.io) Session Manager.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) - 为 macOS 添加工具.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 aliases.
* [ugit](https://github.com/Bhupesh-V/ugit) - Lets you undo your last `git` operation.
* [uncloudium](https://github.com/Talon1024/omz-uncloudium) - Adds helper script to download crx files from the Google Chrome web store.
* [undollar](https://github.com/zpm-zsh/undollar) - Strips the dollar sign from the beginning of the terminal prompt.
* [unique-id](https://github.com/z-shell/zsh-unique-id) - provides a unique number that identifies a running Zshell session, in its shell variable `$ZUID_ID`. Besides this unique number, also a unique codename is provided, in shell variable `$ZUID_CODENAME`. An example use case is to hold logs in files `.../mylog-${ZUID_CODENAME}.log`, so that two different Zshells will not write to the same file at the same time.
* [unix-simple](https://github.com/redxtech/zsh-unix-simple) - A command that shows a graphic about the simplicity of unix.
* [up (cjayross)](https://github.com/cjayross/up) - 一种向上浏览目录的简单方法.
* [up (peterhurford)](https://github.com/peterhurford/up.zsh) - Adds an up command to `cd` multiple levels up.
* [update-zsh](https://github.com/AndrewHaluza/zsh-update-plugin) - Updates custom oh-my-zsh plugins. Only works with the oh-my-zsh framework.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) <i>- A plugin for the ZSH syntax highlighter that turns URLs green if they respond with a &quot;good&quot; status, and red otherwise.</i> <b>- ZSH 语法高亮插件插件，如果 URL 以“良好”状态响应，则将其变为绿色，否则变为红色。</b> <i>Useful for checking URL typos.</i><b>用于检查 URL 拼写错误。</b>
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - Extends the functionality of the original oh-my-zsh venv module.
* [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) - 一个包装插件 [vagrant](https://www.vagrantup.com/) that allows for calling `vagrant` commands from outside of the box directory. The plugin also ships with a few extra commands that help to manage more than one box, along with custom tab-completion.
* [vanilli.sh](https://github.com/yous/vanilli.sh) - shell 配置的轻量级起点.
* [vapor](https://github.com/notf0und/zsh-vapor) - 用于 zsh 的 Laravel vapor 插件，可帮助您从项目树中的任何位置运行 vapor，并具有自动完成功能！
* [vcshr](https://github.com/aubreypwd/zsh-plugin-vcshr) - 帮助 vcsh 用户需要使用 `vcsh` 的 Github 存储库，以便在 `~/.zshrc` 等中自动安装.
* [velocity](https://github.com/rahulsalvi/velocity-python) - Powerline-based theme elements for ZSH and [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) - A super-lightweight sort-of-clone of [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/); it pretty much expects you to be using [pyenv](https://github.com/pyenv/pyenv) (though you don't *have* to), and because it's based on the [`venv` module](https://docs.python.org/3/library/venv.html), （创建）仅适用于 python &gt;= 3.3.
* [venv-wrapper](https://github.com/glostis/venv-wrapper) - 提供 ZSH 功能以简化使用 `venv` 的虚拟环境管理.
* [vi-increment](https://github.com/zsh-vi-more/vi-increment) - 添加类似 `vim` 的递增/递减操作.
* [vi-mode (jeffreytse)](https://github.com/jeffreytse/zsh-vi-mode) - 💻 A better and friendly vi(vim) mode plugin for ZSH.
* [vi-mode (nyquase)](https://github.com/Nyquase/vi-mode) 添加额外的类似“vi”的功能.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - 向 ZSH 添加更多类似于 `vi` 的功能.
* [vi-motions](https://github.com/zsh-vi-more/vi-motions) - 添加新的动作和文本对象，包括带引号/括号的文本和命令.
* [vi-quote](https://github.com/zsh-vi-more/vi-quote) - Add an operation which quotes or unquotes a motion.
* [viexchange](https://github.com/okapia/zsh-viexchange) - 一个 `vi` 模式插件，用于在缓冲区中的两个位置之间轻松交换文本，例如 vim-exchange.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) - Friendly `vi`-mode bindings, adding basic Emacs keys, incremental search, mode indicators and more.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - Allows you to do `vim filename:123` to open a file with the cursor at a specific line.
* [vimman](https://github.com/yonchu/vimman) - View `vim` plugin manuals (help) like `man` in ZSH.
* [vimto](https://github.com/laurenkt/zsh-vimto) - 改进了 ZSH `vi` 模式 (bindkey -v) 插件.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - A modified virtualenv ZSH plugin for oh-my-zsh.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - A fork of the virtualenv plugin from upstream. Adds support for customizing the virtualenv prompt in oh-my-zsh themes.
* [virtualz](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) manager inspired by Adam Brenecki's [Virtualfish](https://github.com/adambrenecki/virtualfish) 为了 [Fish shell](http://fishshell.com/), replaces virtualenvwrapper.
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - An oh-my-zsh plugin for the [virtuozzo](https://docs.virtuozzo.com/master/index.html) bare-metal virtualization system.
* [visit](https://github.com/justinpchang/visit) - Custom plugin for faster navigation.
* [volta (cowboyd)](https://github.com/cowboyd/zsh-volta) - 无缝安装和配置 [Volta](https://volta.sh) NodeJS toolchain manager.
* [volta](https://github.com/ri7nz/zsh-volta) - Installs and loads [ Volta: JS Toolchains as Code](https://github.com/volta-cli/volta).
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - 一个 oh-my-zsh 插件来控制 [VOX](https://vox.rocks/), a lightweight full-featured audio player for macOS that can play a variety of formats including FLAC and Ogg Vorbis.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for Visual Studio Code on macOS.
* [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) - Simple plugin to open VS code a little easily across systems.
* [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) - 插件 [Visual Studio Code](https://code.visualstudio.com/).
* [vterm](https://github.com/randomphrase/vterm-zsh-plugin) - 让您直接从 [vterm](https://github.com/vterm/vterm) shell sessions.
* [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) - Track how much [time](https://wakatime.com/) you have spent in your terminal. Has per project stats.
* [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) - Automatic time tracking for commands in ZSH using [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - 配置着色与 [grc](https://github.com/garabik/grc).
* [watch](https://github.com/enrico9034/zsh-watch-plugin) - 通过按“CTRL + W”，可以轻松地为当前或以前的命令添加前缀.
* [watson.zsh](https://github.com/bcho/Watson.zsh) - 一个插件 [watson](https://github.com/TailorDev/Watson) time management system.
* [wd](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
* [web-search (sinetoami)](https://github.com/sinetoami/web-search) - Add commands to run bing, google, yahoo, & duckduckgo searches directly from the CLI.
* [web-search (yabanahano)](https://github.com/Yabanahano/web-search) - 添加别名以使用 Google、Wiki、Bing、YouTube 和其他流行服务进行搜索.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - Highlight where a particular line was last changed in a file using `git blame`.
* [window-title](https://github.com/olets/zsh-window-title) - 将信息图块添加到您的终端窗口.
* [windows-title](https://github.com/mdarocha/zsh-windows-title) - 使用当前目录和最后运行的命令动态更新终端窗口标题.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) - Simple utility for jumping between projects.
* [worktree](https://github.com/jspears/worktree) - Adds functions that wrap `git worktree`.
* [xdg-basedirs](https://github.com/zshzoo/xdg-basedirs) - Configure apps to use XDG base directories.
* [xxh-plugin-zsh-zshrc](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) - plugin for [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) that copies your `~/.zshrc` to a remote host and sources it with [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh).
* [yadm](https://github.com/juanrgon/yadm-zsh) - Displays a warning if there are local yadm configuration changes.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - Automatically activate a directory's pip environment if `pipenv` detects the presence of one.
* [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's Yeoman plugin for oh-my-zsh, compatible with yeoman version ≥1.0 (includes options and command auto-completion).
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH plugin that reminds you to use those aliases you defined.
* [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) - 添加 `yt` 别名以从 YouTube 下载视频.
* [youtube-dl](https://github.com/joow/youtube-dl) - 简单的插件 [youtube-dl](https://youtube-dl.org/).
* [yup](https://github.com/redxtech/zsh-yup) - Adds helper function to upgrade all the dependencies in a yarn/npm project.
* [z.lua](https://github.com/skywind3000/z.lua) - A command line tool which helps you navigate faster by learning your habits. An alternative to [z.sh](https://github.com/rupa/z) with Windows and posix shells support and various improvements. 10x faster than fasd and autojump, 3x faster than [z.sh](https://github.com/rupa/z).
* [zabb](https://github.com/Mellbourn/zabb) - `zabb` is a command that tries to figure out the shortest memorable abbreviation of a directory that is usable by [z](https://github.com/ajeetdsouza/zoxide) 明确地跳转到该目录.
* [zabrze](https://github.com/Ryooooooga/zabrze) - A ZSH abbreviation expansion plugin.
* [zaw](https://github.com/zsh-users/zaw) - ZSH anything.el-like widget.
* [zbrowse](https://github.com/zdharma-continuum/zbrowse) - 在做shell工作时，经常会调用echo $variable多次，检查循环结果等.使用ZBrowse，你只需要按`Ctrl-B`，调用ZBrowse – Zshell变量浏览器.
* [zce](https://github.com/hchbaw/zce.zsh) - Vim 的 EasyMotion / Emacs 的 ZSH ace-jump-mode.
* [zcolors](https://github.com/marlonrichert/zcolors) - Uses your `$LS_COLORS` to generate a coherent theme for Git and your Zsh prompt, completions and [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [zconvey](https://github.com/zdharma-continuum/zconvey) - Adds ability to send commands to other ZSH sessions, you can use this to `cd $PWD` on all active ZSH sessions, for example.
* [zed](https://github.com/eendroroy/zed-zsh) - 一个简单的包装器 [z](https://github.com/rupa/z) 通过 ZSH 插件安装它.
* [zeit](https://github.com/zeit/zeit.zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
* [zellij (jaeheonji)](https://github.com/jaeheonji/zsh-zellij-plugin) - Provides an environment that uses [zellij](https://github.com/zellij-org/zellij). Requires `tmux`.
* [zellij (tranzystorek-io)](https://github.com/tranzystorek-io/zellij-zsh) - 提供自动启动的环境 [zellij](https://github.com/zellij-org/zellij) 作为您终端的多路复用器.
* [zeno](https://github.com/yuki-yano/zeno.zsh) - Fuzzy completion and utility plugin powered by [Deno](https://deno.land/).
* [zero](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details.
* [zflai](https://github.com/zdharma-continuum/zflai) - A fast logging framework for ZSH.
* [zfzf](https://github.com/b0o/zfzf) - A fzf-powered file picker for ZSH which allows you to quickly navigate the directory hierarchy.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - 使 compinit 在所有加载完成后只运行一次 [zgen](https://github.com/tarjoilija/zgen).
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) - Custom extras for zimfw, packaged into a zimfw plugin.
* [zinfo_line](https://github.com/kmhjs/zinfo_line) - 为 ZSH 主题提供更多信息.
* [zinit-annex-bin-gem-node](https://github.com/zdharma-continuum/zinit-annex-bin-gem-node) - [zinit](https://github.com/zdharma-continuum/zinit) 在不更改 $PATH 的情况下公开二进制文件的扩展，安装 Ruby gems 和 Node 模块并轻松公开它们的二进制文件，并在更新相关插件或片段时更新 gems 和模块.
* [zinit-annex-default-ice](https://github.com/zdharma-continuum/zinit-annex-default-ice) - Allows user to define ices active for multiple zinit commands.
* [zinit-annex-man](https://github.com/zdharma-continuum/zinit-annex-man) - [Zinit](https://github.com/zdharma-continuum/zinit) extension that generates man pages for all plugins and snippets
* [zinit-annex-meta-plugins](https://github.com/zdharma-continuum/zinit-annex-meta-plugins) - Install groups of plugins with a single label ([zinit](https://github.com/zdharma-continuum/zinit) 只要）.
* [zinit-annex-patch-dl](https://github.com/zdharma-continuum/zinit-annex-patch-dl) - [zinit](https://github.com/zdharma-continuum/zinit) extension that downloads files and applies patches through the provided `dl` and `patch` zinit ices.
* [zinit-annex-readurl](https://github.com/zdharma-continuum/zinit-annex-readurl) - Adds function to automatically download the newest version of a file to which URL is hosted on a webpage.
* [zinit-annex-rust](https://github.com/zdharma-continuum/zinit-annex-rust) - [zinit](https://github.com/zdharma-continuum/zinit) extension that that installs rust and cargo packages inside plugin directories.
* [zinit-annex-submods](https://github.com/z-shell/z-a-submods) - [zinit](https://github.com/zdharma-continuum/zinit) extenstion allows installing and managing additional submodules within a plugin or snippet.
* [zinit-annex-test](https://github.com/NorthIsMirror/z-a-test) - [zinit](https://github.com/zdharma-continuum/zinit) extension that runs tests (via make test, for example) – if it finds any of them – after installing and updating a plugin or snippet.
* [zinit-annex-unscope](https://github.com/zdharma-continuum/zinit-annex-unscope) - Allows installing plugins for [zinit](https://github.com/zdharma-continuum/zinit) without specifying the user name by querying the Github API.
* [zinit-console](https://github.com/z-shell/zinit-console) - A semigraphical (curses) consolette for the [zinit](https://github.com/zdharma-continuum/zinit) plugin manager.
* [zinsults](https://github.com/ahmubashshir/zinsults) - Prints insults if a command fails.
* [zjump](https://github.com/qoomon/zjump) - Simplify ZSH directory navigation; jump to already visited, parent or sub folders.
* [zlitefetch](https://github.com/ippee/zlitefetch) - Lightweight system information plugin.
* [zlong_alert](https://github.com/kevinywlui/zlong_alert.zsh) - Uses notify-send and ring a bell to alert you when a command that has taken a long time (default: 15 seconds) has completed.
* [zman](https://github.com/mattmc3/zman) - Use `fzf` to quickly browse Zsh manuals.
* [zoxide](https://github.com/ajeetdsouza/zoxide) - 学习您习惯的“cd”的快速替代方案.
* [zredis](https://github.com/zdharma-continuum/zredis)  - 添加 Redis 数据库支持，使用 `database_key` &lt;-&gt; `shell_variable` 绑定. 支持所有数据类型.
* [zsh-in-docker](https://github.com/deluan/zsh-in-docker) - Automates ZSH + Oh-My-ZSH installation into development containers. Works with Alpine, Ubuntu, Debian, CentOS or Amazon Linux.
* [zsh-not-vim](https://github.com/redxtech/zsh-not-vim) - 提供自动羞辱用户忘记他们没有在 vim 中的功能。
* [zsh-z (agkozak)](https://github.com/agkozak/zsh-z)  - 快速跳转到您“经常”访问的目录.  `z.sh` 的原生 ZSH 端口 - 没有 `awk`、`sed`、`sort` 或 `date`.
* [zsh-z (ptavares)](https://github.com/ptavares/zsh-z) - Installs and loads [z](https://github.com/rupa/z.git).
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for oh-my-zsh.
* [zshrc](https://github.com/freak2geek/zshrc) - 从您的项目范围加载本地 `.zshrc` 文件.
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - Plugin for taking ZFS pre/post upgrade snapshots on Arch Linux.
* [zsnapshot](https://github.com/zdharma-continuum/zsnapshot) - Adds command to dump the current ZSH state into a file, for later restoration by sourcing the snapshot file.
* [ztouch](https://github.com/mjrafferty/ztouch) - Adds touchbar controls for recent history commands, directory stack, cycling between modes and user-mappable commands to the touchbar on macOS.
* [zui](https://github.com/zdharma-continuum/zui) - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH.)

## Completions

These plugins add tab completions without adding extra functions or aliases.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - 扩展 ZSH 的 \_urls 补全，允许它从 html 页面补全 url.
* [aliyun](https://github.com/thuandt/zsh-aliyun) - Add completions for the [Aliyun CLI](https://github.com/aliyun/aliyun-cli).
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - Completions for viasite-ansible/ansible-server.
* [antibody-completion](https://github.com/sinetoami/antibody-completion) - 这个插件提供完成 [Antibody](https://github.com/getantibody/antibody) plugin manager.
* [appspec](https://github.com/perlpunk/App-AppSpec-p5) - Generating completions for Bash and ZSH from YAML specs
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - autopkg 的完成.
* [aws-completions](https://github.com/eastokes/aws-plugin-zsh) - Adds completion support for `awscli` to manage AWS profiles/regions and display them in the prompt.
* [aws_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) - Add completions for the aws_manager CLI.
* [bash-completions-fallback](https://github.com/3v1n0/zsh-bash-completions-fallback) - 当没有本地 ZSH 可用时，支持命令的 `bash` 完成.
* [batect](https://github.com/batect/batect-zsh-completion/) - Adds tab completions for [batect](https://batect.dev/) 构建系统.
* [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - Better tab completion for `npm`.
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - Adds BOSH autocompletion.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) - Completion plugin for homebrew services.
* [buidler](https://github.com/gonzalobellino/buidler-zsh) - Adds completion and useful aliases for NomicLabs Buidler tool [buidler.dev](https://buidler.dev).
* [bw](https://github.com/CupricReki/zsh-bw-completion) - Adds completion for [Bitwarden](https://bitwarden.com/).
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - Add tab completion for cabal.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal.
* [carapace](https://github.com/rsteube/carapace) - Completion generator for Bash, Elvish, Fish, Oil, Powershell, Xonsh and ZSH. Note - not dynamic, you have to explicitly run it to generate completions for a command.
* [cargo](https://github.com/MenkeTechnologies/zsh-cargo-completion) - All the functionality of the original OMZ cargo completion, with additional support for remote crates via `cargo search` in `cargo add`.
* [carthage](https://github.com/squarefrog/zsh-carthage) - Provides completions and aliases for use with [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) - 为所有人添加自动完成功能 [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) commands.
* [cod](https://github.com/dim-an/cod) - A completion demon for `bash`/`fish`/`zsh` which creates completion functions on the fly when it sees you run something with `--help`.
* [codeception](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Displays git info, whether you're logged in via `ssh`, return code of last command.
* [comonicon](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) - Tab completions for [comonicon](https://github.com/Roger-luo/Comonicon.jl).
* [completions](https://github.com/zsh-users/zsh-completions) - ZSH 的额外完成集合.
* [conda](https://github.com/esc/conda-zsh-completion) - ZSH tab completion for conda.
* [cpan](https://github.com/MenkeTechnologies/zsh-cpan-completion) - Adds `cpan install word<tab>` and `cpanm install <tab>` to complete remote CPAN package names.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - Tab completions for [ctop](https://github.com/bcicen/ctop).
* [dagger](https://github.com/jygastaud/dagger-oh-my-zsh) - Completions for dagger.
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
* [docker (chr-fritz)](https://github.com/chr-fritz/docker-completion.zshplugin) - Loads `docker` ZSH tab completions directly from **Docker for Mac**.
* [docker (felixr)](https://github.com/felixr/docker-zsh-completion) - Add tab completions for `docker`.
* [docker (greymd)](https://github.com/greymd/docker-zsh-completion) - 为 `docker` 和 `docker-compose` 添加选项卡补全.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - Command completion for [docker-enter](https://github.com/jpetazzo/nsenter).
* [dotnet](https://github.com/MenkeTechnologies/zsh-dotnet-completion) - dotnet 选项卡完成.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for ZSH.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - 一个 ZSH 插件 [duell](https://github.com/gameduell/duell).
* [efibootmgr](https://github.com/wehlando/efibootmgr-zsh-completion) - Tab completions for `efibootmgr`.
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - Adds etcdctl tab completions.
* [expressvpn](https://github.com/tk7r/zsh-expressvpn) - Adds tab completions for the [expressVPN](https://www.expressvpn.com/support/vpn-setup/app-for-linux/) client.
* [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) - Defines a function called extract that extracts the archive file you pass it, and supports a wide variety of archive filetypes.
* [extract (thetic)](https://github.com/thetic/extract) - oh-my-zsh 提取插件的分支.
* [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - Adds autocompletion options for all [Concourse CLI](https://www.concourse.ci/fly-cli.html) commands.
* [fzf-gcloud](https://github.com/mbhynes/fzf-gcloud) - Fuzzy completion to navigate and preview all Google Cloud SDK `gcloud` CLI commands
* [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) - Add tab completion for ZSH, bash & applications using GNU Readline.
* [fzf-zsh-completions](https://github.com/chitoku-k/fzf-zsh-completions) - 模糊完成 [fzf](https://github.com/junegunn/fzf) and [ZSH](https://www.zsh.org/) that can be triggered by a trigger sequence that defaults to `**`.
* [gcloud](https://github.com/littleq0903/gcloud-zsh-completion) - 为 Google Cloud SDK 添加补全.
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - providing ZSH completion support to various Gentoo tools that lack completion scripts upstream.
* [git-annex](https://github.com/Schnouki/git-annex-zsh-completion) - 允许大多数 git-annex 命令的选项卡完成.
* [git-flow](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for [git-flow](http://github.com/nvie/gitflow).
* [git-fzf](https://github.com/alexiszamanidis/zsh-git-fzf) - ZSH plugin that wraps `git` operations for simplicity and productivity. It also contains completions and combines support for [fzf](https://github.com/junegunn/fzf).
* [github-cli](https://github.com/sudosubin/zsh-github-cli) - github cli 的选项卡完成.
* [gitlab-runner](https://github.com/pseyfert/zsh-gitlab-runner-completion) - ZSH completions for gitlab-ci-multi-runner.
* [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) - Bash and ZSH completion support for gradle.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - ZSH completion support for gradle.
* [grid5000](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 插件 - 添加主题、自动补全.
* [gulp (akoenig)](https://github.com/akoenig/gulp.plugin.zsh) - Autocompletion for your gulp.js tasks in the Z-Shell (ZSH).
* [gulp (srijanshetty)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - Autocompletion for gulp.
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) - 完成 [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haskell](https://github.com/coot/zsh-haskell) - 为 `cabal`、`ghc` 和 `ghc-pkgs` 命令添加补全.
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib.
* [helmfile](https://github.com/Downager/zsh-helmfile) - Adds autocompletion for `helm`.
* [inspr](https://github.com/ptcar2009/insprzsh) - 完成 [inspr](https://github.com/inspr/inspr)
* [ipfs](https://github.com/hellounicorn/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.io).
* [joe](https://github.com/corvofeng/joe-completion) - 添加完成 [joe](https://github.com/karan/joe) gitignore editor.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - ZSH completions for jtool.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - 添加自动完成 [jumpstorm](https://github.com/netresearch/jumpstorm)
* [jx](https://github.com/haysclark/zsh-jx) - 为 Jenkins-X cli 添加选项卡补全.
* [kafka](https://github.com/Dabz/kafka-zsh-completions) - Completions for Apache [kafka](https://kafka.apache.org).
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - 完成 [keybase](https://keybase.io/docs/command_line).
* [kitty](https://github.com/redxtech/zsh-kitty) - 完成 [kitty](https://sw.kovidgoyal.net/kitty/) terminal emulator.
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - Add tab completions for [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - Add tab completions for [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
* [kubectl-fzf](https://github.com/bonnefoa/kubectl-fzf) - Fast and powerful [`fzf`](https://github.com/junegunn/fzf)- 为 `kubectl` 提供动力的自动完成功能.
* [lazycomplete](https://github.com/rsteube/lazycomplete) - Lazy loading for shell completion scripts.
* [lets](https://github.com/lets-cli/lets-zsh-plugin) - Add autocompletion for [lets](https://github.com/lets-cli/lets) cli 任务运行器.
* [ls-go](https://github.com/MohamedElashri/ls-go-zsh) - 添加一些有用的别名 [ls-go](https://github.com/acarl005/ls-go).
* [mooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - completion generator for Perl module `MooseX::App`.
* [more-completions](https://github.com/MenkeTechnologies/zsh-more-completions) - 10500 zsh compsys completions!
* [msfvenom](https://github.com/Green-m/msfvenom-zsh-completion) - Metasploit 的选项卡完成.
* [mx-honey](https://github.com/mukel/mx-honey) - Provides completions for [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.
* [newman](https://github.com/selop/newman-autocomplete) - 提供自动完成 [Newman CLI](https://github.com/postmanlabs/newman).
* [nix](https://github.com/spwhitt/nix-zsh-completions) - 完成 [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/)， 和 [NixOps](https://nixos.org/nixops/).
* [node-ace](https://github.com/romch007/node-ace-zsh-completion) - 完成“节点王牌”.
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) - Provides auto-complete for nova.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - 对“npm run”的自动完成支持.
* [nx](https://github.com/jscutlery/nx-completion) - 完成 [nx](https://nx.dev). Requires [`jq`](https://stedolan.github.io/jq/).
* [okta](https://github.com/sirhc/okta.plugin.zsh) - Provides command line completions for the [`aws-okta`](https://github.com/segmentio/aws-okta) and [okta-awscli](https://github.com/jmhale/okta-awscli) commands.
* [op](https://github.com/sirhc/op.plugin.zsh) - Tab completions for [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) command line tool.
* [packer](https://github.com/wakeful/zsh-packer) - Adds tab completion for [packer](https://packer.io).
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin.
* [parallels](https://github.com/benclark/parallels-zsh-plugin) - Add completions for Parallels desktop.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - 方便的回购，轻松获得 [pass](https://www.passwordstore.org/) ZSH 的命令完成.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - Autocompletion plugin for pip.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - Enables aliases for the most common pipenv commands.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) - Completions for `pipenv`.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh) - automatically activates a **pipenv** when entering a directory if there is Pipfile in that directory. Includes `pipenv` completions.
* [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) - Adds completions for Pivotal's [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
* [pmy](https://github.com/relastle/pmy) - General purpose context-aware ZSH completion engine powered by [fzf](https://github.com/junegunn/fzf).
* [quickjump](https://github.com/fikovnik/zsh-quickjump) - 添加选项卡完成支持 [skim](https://github.com/lotabout/skim) 对于最近使用的文件和目录 [fasd](https://github.com/whjvenyl/fasd).
* [racket completion](https://github.com/racket/shell-completion) - Completion for [Racket](http://racket-lang.org).
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets.
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) - Add completions for the Rancher CLI.
* [rhoas](https://github.com/craicoverflow/rhoas-zsh-plugin) - 添加完成 [rhoas](https://developers.redhat.com/products/red-hat-openshift-streams-for-apache-kafka/overview).
* [rustup](https://github.com/pkulev/zsh-rustup-completion) - Tab completions for Rustup.
* [s3cmd](https://github.com/FFKL/s3cmd-zsh-plugin) - Adds tab completions for [s3cmd](https://s3tools.org/s3cmd).
* [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion) - ZSH command completion for the Salesforce CLI. Requires [jq](https://stedolan.github.io/jq/).
* [saml2aws](https://github.com/sirhc/saml2aws.plugin.zsh) - 添加完成 [saml2aws](https://github.com/Versent/saml2aws).
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) - sfdx 的自动完成插件.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - Adds autocompletions for [spring-boot](http://projects.spring.io/spring-boot/) commands.
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - Manage `ssh-agent`.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - 自动启动 `ssh-agent` 以设置和加载您想要的 `ssh` 连接的任何凭据.
* [ssh](https://github.com/zpm-zsh/ssh) - Add host completion for `ssh`.
* [surf](https://github.com/beardcoder/surf.plugin.zsh) - Add completions for surf.
* [symphony (TheGrowingPlant)](https://github.com/TheGrowingPlant/symfony.plugin.zsh) - Symfony 3 和 4 命令的自动完成.
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - Add completions for [Test Kitchen](https://github.com/test-kitchen/test-kitchen)).
* [tinygo](https://github.com/sago35/tinygo-autocmpl) - Add tab completions for tinygo.
* [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your [tmux](https://tmux.github.io) pane.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - 添加自动完成 [tugboat](https://github.com/petems/tugboat) command.
* [umake](https://github.com/zlsun/umake) - Tab completion for Ubuntu umake.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - Provides autocomplete features for the [vertx](https://vertx.io/) command.
* [web-open](https://github.com/AndrewHaluza/zsh-web-open) - Adds alias to open web pages. Only works with Ubuntu 20.
* [yabai](https://github.com/Amar1729/yabai-zsh-completions) - Add completions for macOS [yabai](https://github.com/koekeishiya/yabai/) tiling window manager.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - Add autocompletions for `yarn add`, `yarn remove`, `yarn upgrade`, `yarn why` and `yarn run`.
* [zargparse](https://github.com/ctil/zargparse) - 向它传递一个使用 `argparse` 的脚本，它会将 ZSH 完成写入您的当前目录.
* [zstyle-completions](https://github.com/zshzoo/zstyle-completions) - 给 [prezto-style](https://github.com/sorin-ionescu/prezto) 点击选项卡时完成.

## Themes

如果你正在使用 [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. 如果你正在使用 [zgenom](https://github.com/jandamm/zgenom), add them to your `init.zsh` with `zgenom load githubuser/reponame`.

* [000](https://github.com/Abid-Ahmad/oh-my-zsh-000-theme) - Multiline prompt with username, hostname, full path, return status and `git` decorations.
* [0i0](https://github.com/0i0/0i0.zsh-theme) - Optimized for dark terminal windows, uses nerdfont `git` status decorations.
* [14degree](https://github.com/saims0n/14degree-zsh-theme/) - Includes `git`, `virtualenv` and `rvm` status decorations.
* [4den](https://github.com/RunThem/zsh-theme-4den) - Minimalist. Includes `git` and `hg` status decorations.
* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - Based on the Sorin theme.
* [abbr (theme)](https://github.com/PhilsLab/abbr-zsh-theme) - Displays an abbreviated version of the current directory path, shows the Python virtualenv, Rust version, `git` status, and the exit code of last command. Works well on dark backgrounds by default but colors can be easily customized.
* [absolute](https://github.com/NelsonBrandao/absolute) - Very clean looking theme with git status, node version and the exit code from the last command.
* [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) - Includes `git` status decorations, name of your AWS profile, name of your Azure Service Principal, kubernetes context, terraform workspace, command status and current working directory.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS theme, requires a Powerline-compatible font.
* [af-magic-dynamic](https://github.com/rslavin/af-magic-dynamic) - Modified version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) with dynamic path shortening.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - Modified version of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme in oh-my-zsh.
* [aftermath](https://github.com/schanur/aftermath) - 在您在 shell 中运行的每个命令后获得一个漂亮的摘要行.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) - 基于 [agnoster](https://gist.github.com/3712874) theme included in [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) and [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) . 显示有关 `git` 状态的详细信息.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt)  - 使用三种异步方法来保持 ZSH 提示响应，同时显示 `git` 状态和 SSH 连接、退出代码和 `vi` 模式的指示符，以及缩写的 `PROMPT_DIRTIM` 样式路径. 非常可定制. 即使在 Cygwin 和 MSYS2 上也是异步的.
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - Solarized [Agnoster](https://gist.github.com/agnoster/3712874) variant with `git` status information. Requires a unicode font and works best with a [solarized](https://github.com/altercation/solarized) terminal.
* [agnoster-fseguin](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) 带有正确提示的变体.
* [agnoster-gentoo](https://github.com/r7l/agnoster-gentoo-zsh-theme) - A Gentoo flavored version of the [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme) 其中包括 user@hostname 和 `git` 状态装饰. 使用 unicode 字体效果更好.
* [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) - 优化 [solarized](https://ethanschoonover.com/solarized/) color scheme, `git` or other VCS tools, and unicode-compatible fonts. Includes status of last command run, user@hostname, `git` status decorations, working directory, whether running as root, whether background jobs are running, and other information.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with a right-prompt.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体优化用于 [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) terminal color scheme. Includes `git` status.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体，包括电池和在线状态.
* [agnoster-repopath](https://github.com/ivanfurlan/agnoster-repopath-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) themes. Includes `git` and `mercurial` status, current time and time the last command took decorations in the prompt.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with timestamp and newline added.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - 基于 [Powerline](https://github.com/Lokaltog/vim-powerline) and [Agnoster](https://gist.github.com/agnoster/3712874) themes and inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnoster](https://gist.github.com/agnoster/3712874)  - 针对 solarized 终端配色方案进行了优化，显示 `git` 装饰、用户@主机、工作目录、上一个命令的退出状态以及您是否以 root 权限运行. 需要与电力线兼容的字体.
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - 基于 [Agnoster](https://gist.github.com/agnoster/3712874), 显示电池寿命、日期和时间、`git` 状态、当前目录以及用户和主机信息.
* [akzsh](https://github.com/awkimball/akzsh) - 最适合深色终端主题，包括 `git` 装饰.
* [alarangeiras](https://github.com/alarangeiras/alarangeiras-zsh-theme/) - Minimalist theme with `git` status decorations.
* [ale](https://github.com/alepimentel/ale-zsh) - Based on the fino theme. Includes `git`, `virtualenv` and `node` status decorations.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) - Minimalist ZSH theme with `git` status displayed.
* [alien](https://github.com/eendroroy/alien) - Powerline-esque ZSH theme that shows `git` decorations and the exit code of the last command. Faster than many other prompts because it determines the `git` decorations asynchronously in a background process.
* [almel](https://github.com/Ryooooooga/almel) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme), written in Rust. Includes `git` status, user@host, last command exit status and working directory decorations
* [alpharized](https://github.com/NicoSantangelo/Alpharized) - Optimized to work with [solarized](http://ethanschoonover.com/solarized) 黑暗的终端. 这是修改版 [avit theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme).
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - An elegant and comfortable-reading theme based on [Agnoster](https://gist.github.com/agnoster/3712874).
* [andy](https://github.com/andymcguinness/andys-theme) - Modified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 具有更好的 `git` 支持的主题.
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) - Shows `git` information in the right hand prompt.
* [antoinechab](https://github.com/antoinechab/antoinechab-theme) - Includes `git` status, username, time and current directory decorations.
* [antsy](https://github.com/jeffmhubbard/antsy-zsh-theme) - Shows `git` branch and status decorations, virtualenv, exit status, jobs count, and vi-mode indicator.
* [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) - Shows `git` decorations, user, host, whether root, active Python virtual environment, current Ruby interpreter, visual and numeric status of the last command, power management status and time and date.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme) - Minimalistic theme without visual noise. Displays only the necessary information: current user, hostname, working directory, `git` branch if one exists. Looks great both with dark and white terminals.
* [aplos](https://github.com/sunquan1991/aplos) - Minimal ZSH prompt with working directory, `git` local info, `git` remote info, time and exit code.
* [apollo](https://github.com/mjrafferty/apollo-zsh-theme) - 一个高度可定制、兼容和高性能的 ZSH 主题，它使用模块来启用功能.
* [apple (aramirol)](https://github.com/aramirol/apple-zsh-custom-themes) - 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) , 包括 `vcs` 状态装饰. 通过在 `.zshrc` 中设置变量来自定义颜色.
* [apple (bjrowlett2)](https://github.com/bjrowlett2/apple-zsh-theme) - Minimalist theme with `git` status decorations.
* [arael](https://github.com/aknackd/zsh-themes) - Fork of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [archie](https://github.com/dcavalcante/archie) - Arch Linux inspired ZSH theme. Based on the [norm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) theme.
* [arity](https://github.com/hybras/Arity-Zsh-Theme) - Arity is a simple theme designed for readability and to give an overview at a glance. Includes path and `git` decorations.
* [aronhoyer](https://github.com/aronhoyer/zsh-theme) - Minimalist theme with right-side `git` status decorations.
* [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - A minimal ZSH theme with `git` decorations.
* [asciigit](https://github.com/cemsbr/asciigit) - 为不想使用带有额外字形的字体的 `git` 用户提供的纯 ASCII 主题.
* [asq](https://github.com/AugustoQueiroz/asq-theme) - 基于 [theunraveler](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#theunraveler).
* [astral](https://github.com/xwmx/astral)  - 带有禅宗模式的深色背景主题. 适用于 zsh-users [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) 插入.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - Based on the `ys` and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 主题.
* [async](https://github.com/mje-nz/zsh-themes) - Shows current directory, `git` state, return value of last command if it had an error code, number of background jobs, execution time of long-running commands, current python virtualenv.
* [aub](https://github.com/FraSharp/aub) - Includes decorations for `git` and `hg` status and `username` at `host`.
* [aterminal](https://github.com/guiferpa/aterminal) - Displays Nodejs, NPM, Docker, Go, Python, Elixir and Ruby information in the prompt.
* [avil](https://github.com/avil13/avil-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) - Based on the oh-my-zsh [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme, with small changes.
* [avit-mod](https://github.com/zlsun/avit-mod) - 修改版 oh-my-zsh&#39;s [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme.
* [banana](https://github.com/sorcererxw/banana-zsh-theme) - Includes `git` status decorations and current directory.
* [bandit](https://github.com/Holger-Will/zsh_bandit) - Another Powerline variant.
* [bar (anki-code)](https://github.com/anki-code/bar-theme) - 极简主义设置 [p10k](https://github.com/romkatv/powerlevel10k).
* [bar (xp-bar)](https://github.com/xp-bar/zsh-bar-theme) - 包括用户名、主机、密码、`git` 状态装饰和 3 小时饮水提醒.
* [barion](https://github.com/SEbbaDK/barion) - A fast compiled prompt with a compact `git` status overview. Reminiscent of powerline. Requires [Crystal](https://crystal-lang.org/) 建造.
* [bash](https://github.com/starseekist/bash-zsh-theme) - Looks like the default `bash` prompt.
* [bashi](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) 主题和 Pasquale D&#39;Silva  [Saturn Terminal](https://github.com/psql/saturn-colors) theme.
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - Modified version of [gitster](https://github.com/zimfw/gitster) 主题为 [ZIM](https://github.com/zimfw/zimfw).
* [bearable](https://github.com/JanmanX/bearable-zsh) - Works well with dark terminal backgrounds.
* [bedbugs](https://github.com/justino/zsh-theme-bedbugs) - Inspired by [Agnoster](https://gist.github.com/agnoster/3712874), this multiline prompt includes `git` status information, background job count, working directory, user and hostname, Python virtualenv when present, colored return value of last command and root/user sigil.
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - Inspired by [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme)，但带有啤酒图标.
* [bender](https://github.com/specious/bender) - Fancy two-line prompt with git integration.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with unicode symbols baked in.
* [biraSkull](https://github.com/Shahryar-Pirooz/biraSkull.zsh-theme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), 包括根状态和 `git` 状态装饰.
* [biradate](https://github.com/vemonet/zsh-theme-biradate) - Based on the [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 主题，但在提示中显示日期而不是用户名.
* [birame](https://github.com/maniat1k/birame) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [birav2](https://github.com/shahid64/birav2-theme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme). Includes `git`, `rvm` and `virtualenv` status decorations.
* [bklyn](https://github.com/gporrata/bklyn-zsh) - 变体 [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) with customizations applied.
* [black-Void](https://github.com/black7375/BlaCk-Void-Zsh) - Includes account info, root user, using ssh, directory lotation, write permission, vcs info decorations.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) - Another `git`-aware theme.
* [blazux](https://github.com/blazux/omz-theme) - Includes `git` status decoration and a smiley/sad face indicator of the last command's exit status.
* [blinks (max13ft)](https://github.com/max13fr/blinks.zsh-theme) - 为 oh-my-zsh 添加了 mercurial 支持 [blink](https://github.com/max13fr/blinks.zsh-theme) theme.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) - 基于现有主题 [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme).
* [bliss](https://github.com/joshjon/bliss-zsh)  - 一个精致的主题，在不压倒您的工作空间的情况下注入色彩. 设计用于与 [bliss iTerm](https://github.com/joshjon/bliss-iterm) color scheme and [bliss dircolors](https://github.com/joshjon/bliss-dircolors). Includes `git` status decorations.
* [blokkzh](https://github.com/KorvinSilver/blokkzh) - Theme based on oh-my-zsh's built in [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) theme. Requires a font with unicode support.
* [blox](https://github.com/yardnsm/blox-zsh-theme) - A minimal and fast ZSH theme that shows you what you need. It consists of blocks: each block is shown inside a pair of \[square brackets\], and you can add blocks by simply creating a function.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - Minimal theme, displays `git` information.
* [bluelines](https://github.com/apbarrero/bluelines) - Clear and blue theme.
* [bluo](https://github.com/varunpbardwaj/bluo) - 五颜六色的提示片段让人想起 [bullet-train](https://github.com/caiogondim/bullet-train.zsh) 或者 [powerlevel10k](https://github.com/romkatv/powerlevel10k). Includes `git` status dec或者ations.
* [bogo](https://github.com/cubasepp/zsh-bogo-theme) - Inspired by [zeta](https://github.com/skylerlee/zeta-zsh-theme). Includes `git` and ruby version decorations.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - 多行主题，最适合深色背景.
* [bougenville](https://github.com/bougenville/zsh-theme) - 变体 [dallas](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dallas.zsh-theme).
* [bronze](https://github.com/reujab/bronze)  - 一个跨外壳可定制的类似电力线的提示，带有用 go 编写的图标. 需要 [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
* [brs](https://github.com/evenhold/brs-zsh-theme) - 使用 `audtool` 在提示中显示当前歌曲.
* [bruh](https://github.com/haze/bruh) - Includes `git` status decorations.
* [brunty](https://github.com/Brunty/omz-brunty) - 布鲁蒂主题.
* [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) - Inspired by the [powerline](https://github.com/Lokaltog/vim-powerline) and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 主题.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF color theme.
* [bubblegum](https://github.com/ice-bear-forever/bubblegum-zsh) - 极简主义亮粉色主题，带有三角形字形和您的工作目录，仅此而已 - 为您提供最干净的外壳.
* [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) . 最适合搭配 [nerdfonts](https://github.com/ryanoasis/nerd-fonts).
* [bubblified (varaki)](https://github.com/varaki/bubblified-varaki.zsh-theme) - 基于 [bubblified (hohmannr)](https://github.com/hohmannr/bubblified). Changes color when root.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh) - Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH theme, modified to just display time and directory.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - Simple, clean, and beautiful theme.
* [bureau-env](https://github.com/angus-lherrou/bureau-env) - Modification of the Oh-My-Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) theme that adds a Python virtual environment label to the left of the `git` block.
* [bureau-parrot](https://github.com/BenjaminGuzman/bureau-parrot) - 基于 [bureau](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme). Includes `git` decorations.
* [bureau](https://github.com/isqua/bureau) - A clear and informative two-lined prompt. Includes git status optimized for large repositories.
* [buster](https://github.com/grantbuster/buster_zsh_theme) - Plays well with WSL2. Based loosely on Fox and Jonathan themes from oh-my-zsh.
* [cactus](https://github.com/welksonramos/cactus) - Minimalist theme with `git` status decorations.
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - Light version of the candy theme.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - Shows active Python version and `git` decorations in the prompt.
* [celestialorb](https://github.com/celestialorb/zsh-theme) - Powerline-inspired theme by @celestialorb. Includes `git` status decorations, Kubernetes cluster information (if any), current AWS profile and region, and  active virtualenv.
* [cf-ps1](https://github.com/mdan16/cf-ps1) - Displays the current foundation and organization and space of [Cloud Foundry](https://www.cloudfoundry.org/) in your prompt.
* [ch4rli3](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) - Lean and simple theme.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme) - Based on sorin. Shows the current active versions of Java, Scala, Go, Node, Python and Ruby.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme)  - Oh-My-Zsh 的一个小巧而美丽的主题，没有任何多余的东西. 包括 `git` 状态装饰.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) - A ZSH prompt optimized for the [solarized](https://github.com/altercation/solarized) 黑暗的终端主题.
* [chello](https://github.com/Abdalla981/chello) - Works well on dark backgrounds. Depends on [autojump](https://github.com/wting/autojump), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) and [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [chi](https://github.com/akinjide/chi) - 针对 macOS 上的 iTerm 2 用户优化的 ZSH 主题.
* [chill](https://github.com/JKerboeuf/chill.zsh-theme) - Has decorations for the current working directory, last command exit status and `git` status.
* [chinipage](https://github.com/andresemartinez/chinipage-zsh-theme)  - 包含 `git` 装饰的极简主义主题. 需要与电力线兼容的字体和 [git-prompt](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git-prompt) 插入.
* [chrisandrew.cl](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme)  - 包括 `git` 装饰. 需要与电力线兼容的终端字体.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - 显示时间戳、大换行符、git 分支和状态.
* [clarity](https://github.com/nbitmage/clarity.zsh) - Designed for for simpleness and extensibility.
* [classyTouchName](https://github.com/dylanroman03/classyTouchName) - Oh-my-zsh theme inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh). Works better with dark backgrounds. Includes `git` status decorations.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - Minimal, clean theme with `git` support.
* [clean (akz92)](https://github.com/akz92/clean) - Minimalist ZSH theme.
* [clean (brandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - A minimalist variant of [pure](https://github.com/sindresorhus/pure). Pure is not clean, clean is not pure.
* [clean (patr1ot)](https://github.com/Patr1ot/clean.zsh-theme) - Fork of the upstream [clean](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) with host information added.
* [cleansh](https://github.com/diegoos/cleansh) - Minimalist, includes `git`, Ruby, node and Python version status decorations. Works with standard fonts.
* [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) - 带有 `git`、nix-shell 和 virtualenv 状态装饰的极简主义主题.
* [cloudy](https://github.com/Huvik/Cloudy) - 最小的多云 ZSH 主题.
* [clover](https://github.com/tzing/clover.zsh-theme) - Inspired by [zeta](https://github.com/skylerlee/zeta-zsh-theme) and [pure](https://github.com/sindresorhus/pure).
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - 配置文件 [cmder](http://cmder.net/) configured to work in quake mode with ZSH and a modified [Agnoster](https://gist.github.com/agnoster/3712874) theme.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) - A ZSH theme that matches the theme of Cmder, a popular terminal emulator for windows.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) - Cobalt 2 theme with `git` extensions.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Codemachine theme.
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - Inspired by [bashi](https://github.com/eli-oat/bashi), includes a monkey and `git` information in your prompt.
* [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - Based on agnoster, but has a right-prompt for vi-mode that displays `--INSERT--` and `--NORMAL--`, in a powerline look.
* [coldark](https://github.com/ArmandPhilippot/coldark-zsh-theme)  - 为阅读舒适度而设计的蓝灰色主题. 包括 `git` 装饰.
* [collon](https://github.com/lambdalisue/collon.zsh) - Lightweight theme with `git` status decorations, cwd, time, host, exit status of last command. Does not require special fonts.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - Allows per-host prompt coloring, displays `rvm`, `virtualenv` and `git` information.
* [common](https://github.com/jackharrisonsherlock/common) - 一个简单、干净和最小的提示，显示当前工作目录、主机名、AWS 保管库角色、后台作业、当前 SHA、最后一个命令的退出代码以及 `git` 分支和状态.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - 针对深色背景优化的色彩鲜艳的主题.
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) - Clean and effective ZSH theme with git and npm support.
* [cramin](https://github.com/FelipeCRamos/craminzsh) - Minimal interface with support for github plugins, based on [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [cryo](https://github.com/cryocaustik/cryo-zsh-theme) - 添加日期和时间的原始 oh-my-zsh 主题的独立克隆.
* [crème fraîche](https://github.com/koenwoortman/creme-fraiche-zsh-theme) - Works best with light terminal backgrounds, includes `git` and `vi`-mode status decorations.
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - A macOS oh-my-zsh shell theme with Cute emoji based on the Powerline Vim plugin.
* [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) - Works well on dark background, has `git` status decorations.
* [cypher-ruby](https://github.com/ston1x/cypher-ruby) - Similar to [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) but includes the active Ruby version.
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) with [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) theme in a container.
* [daily](https://github.com/ghlin/zsh-theme-daily) - Includes `git` and `ssh` status decorations.
* [damino](https://github.com/njdom24/Damino-Zsh-Theme) - 带有“git”装饰的最小电力线主题.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) - 内容丰富、极简，最重要的是，以 X 战警为主题.
* [daniloheraclio](https://github.com/daniloheraclio/daniloheraclio-zsh-theme) Inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme. Has `git` and last command exit status decorations. Requires a nerdfont to render properly.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - This version of the popular [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) theme has been enhanced with a near complete rewrite enabling modularity and a few new features.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - Based on the `ys` and [astro](https://github.com/iplaces/astro-zsh-theme) 主题.
* [dbern](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) - Includes battery status and load average decorations.
* [delta (asavoy)](https://github.com/asavoy/delta-zsh-theme) - Minimal ZSH theme to reduce distractions. Includes an iTerm color settings file.
* [delta (dongri)](https://github.com/dongri/delta-zsh-theme) - Another minimal theme with embedded `git` status.
* [delta-prompt](https://github.com/cusxio/delta-prompt) - 一个最小的 ZSH 提示.
* [destiny](https://github.com/ja1dan/Destiny)  - 一个简单、可配置的 ZSH 提示，没有依赖关系.  Destiny 已经在 Linux、macOS 和 iOS 上进行了测试.
* [devj121](https://github.com/DevJ121/devj121-zsh-theme) - Includes `git` decorations with branch glyphs.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) - A theme with an emphasis on the right side (hence the name) of the terminal.
* [dino](https://github.com/OdilonDamasceno/dino-zsh-theme) - Includes decorations for node, golang, flutter, lua, python & java, also includes `git` decorations. Requires nerdfonts.
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - 带有自定义 LSCOLORS 和 LS_COLORS 设置文件，适用于深色和浅色终端主题.
* [diy-ys](https://github.com/aprilnops/zsh-theme) - 变体 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 没有主机名或时间.
* [dkniffin](https://github.com/dkniffin/zsh-theme) - 包括 `ruby` 版本和 `git` 状态.
* [dmx](https://github.com/domix/dmx.zsh-theme) - Optimized for dark terminal windows.
* [doodleshell](https://github.com/cdodd/doodleshell-zsh-theme) - 极简主题，包括 `git`、`terraform` 和 `aws` 状态装饰.
* [dp](https://github.com/davidparsson/zsh-dp-theme) - 显示当前 git 分支的低对比度主题，如果存储库是脏的并且 `$PYENV_VERSION` 的值.
* [dr4kk0nnys_v2](https://github.com/Dr4kk0nnys/Dr4kk0nnys_theme_ohmyzsh_v2/) - Works well on dark backgrounds, includes `git` status decorations.
* [dracula](https://github.com/dracula/zsh) - A dark theme for Atom, Alfred, Chrome DevTools, iTerm 2, Sublime Text, Textmate, Terminal.app, Vim, Xcode, and ZSH.
* [dragon (jeop10)](https://github.com/jeop10/dragon)  - 灵感来自 kali linux. 包括 `git` 状态和工作目录装饰.
* [dragon (sabertaximi)](https://github.com/sabertazimi/dragon-zsh-theme) - Minimalistic, includes `git` status information.
* [drkat](https://github.com/katrinaalaimo/drkat-zsh-theme) - Reminiscent of [Powerline](https://github.com/powerline/powerline) . 包括目录、`git` 状态和主机名装饰.
* [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) variant.
* [dtheme](https://github.com/OlukaDenis/DTheme) - Optimized for people using a solarized terminal color scheme and `git`. Works best with a unicode font.
* [duckster](https://github.com/ducky/duckster) - 一个叉子 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ZSH theme that's more ducky fresh.
* [ducula](https://github.com/janjoswig/Ducula) - Inspired by Dracula project. Includes `git` status decorations, username and hostname abbreviations, virtual environment, current working directory, return status of last command and the time.
* [dustmod](https://github.com/bmihaila/dustmod) - Derived from the [dst](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) theme in oh-my-zsh.
* [dzhi](https://github.com/pentago/dzhi-zsh-theme) - 针对使用的人进行了优化 [Nord](https://www.nordtheme.com/). Includes `git` status decorations.
* [eckig](https://github.com/fouladi/eckig)  - 带有 utf-8 图标的极简主义主题. 包括 `git` 状态装饰和时钟.
* [eggshausted](https://github.com/inutano/eggshausted) - A `git`-aware theme for people who are tired of getting errors.
* [eivmosn](https://github.com/eivmosn/eivmosn-omz) - 修剪了“ys”主题的变体.
* [eleastic](https://github.com/jinseobhong/eleastic-zsh-theme) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme), optimized for solarized terminal theme, includes `git` status decorations. Requires powerline-compatible font.
* [elessar](https://github.com/fjpalacios/elessar-theme) - A `git`-aware theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) . 需要与电力线兼容的字体.
* [elm](https://github.com/gacallea/elm-zsh-theme) - 包括 `git` 状态、user@host、日期、时间和路径装饰器.
* [elsa](https://github.com/faycito/elsa) - 包括根状态、密码和 `git` 状态装饰.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - Emoji flavored [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ohmyzsh/ohmyzsh) theme.
* [emoji](https://github.com/masaakifuruki/emoji.zsh-theme) - 基于  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 主题，将 `git` 提示符号替换为表情符号，以提高清晰度.
* [emojirussell](https://github.com/Bergiu/emojirussell) - 基于  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh theme, with status decorations for current working directory, last command exit status, `git` branch and status.
* [endless-dog](https://github.com/qwelyt/endless-dog) - oh-my-zsh-compatible theme that mimics grml-zsh-config.
* [enlightenment](https://github.com/w33tmaricich/enlightenment) - Includes decorations for `git` status, `vi`-mode indicator, and the time for last command to execute.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - 在终端中占用大量空间.
* [erfan](https://github.com/ekm507/erfan-zsh-theme) - Combination of the of [af-magic](https://github.com/andyfleming/oh-my-zsh) and [macovsky](https://github.com/championswimmer/oh-my-zsh/blob/master/themes/macovsky.zsh-theme) 主题. 包括 `git` 和 `virtualenv` 状态装饰.
* [eriner](https://github.com/zimfw/eriner) - A Zim fork of the Powerline-inspired [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 提示主题. 包括 `git` 状态装饰.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - A simple theme with `git` information.
* [eucalyptus](https://github.com/relastle/eucalyptus) - Simple one-line theme for minimalist vi-mode users inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory and current path.
* [excess](https://github.com/davydovanton/excess.zsh-theme) - Simple ZSH color theme.
* [ez-pz](https://github.com/mangosmoothie/ez-pz) - 带有“git”状态装饰的极简主义主题，灵感来自 [bureau](https://github.com/isqua/bureau).
* [fall](https://github.com/jottenlips/seasonal-zshthemes) - Minimalist theme with fall icons. Includes `git` status decorations.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) - 最小的 ZSH 提示，在深色背景下效果更好.
* [fdT2K](https://github.com/FDT2k/FDT2K-theme)- 基于 [agnoster](https://github.com/agnoster/agnoster-zsh-theme), preset to include virtualenv, last command status, `nvm`, `docker machine` and `git`, `hg` and `bzr` status decorations.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme) - Clean, simple, compatible and meaningful. Tested on Linux, Unix and Windows under ANSI colors.
* [filthy](https://github.com/molovo/filthy) - 令人作呕的干净 ZSH 提示.
* [fish](https://github.com/Raniconduh/zshfish)  - ZSH 主题让人想起默认的鱼壳主题. 包括 `git` 状态装饰.
* [fishy-lite](https://github.com/sudorook/fishy-lite) - Fork of the original [fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy)  oh-my-zsh 中的主题，删除了许多无关内容以提高加载速度. 包括一个电池表和 `git` 状态显示，可以在提示的右侧启用.
* [fishy2](https://github.com/akinjide/fishy2) - ZSH theme inspired by [original fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy).
* [fluent-git](https://github.com/RobertKozak/fluent-git) - Displays time of last command execution, error code, hostname, username, `git` status, kubernetes cluster and namespace, path and ssh connection status.
* [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) - Custom setup for [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status decorations.
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - 包括最后一条命令的状态、`git` 信息和当前目录.
* [frank](https://github.com/ronmackley/frank-theme) - Frank keeps to the point, displaying information compactly but readably on a single line. Frank keeps to the facts and only tells you extra things when they are important.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - Fork of [terminal-party](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) theme.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - 基于的主题 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh-theme.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - 红色版本 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) theme from oh-my-zsh.
* [fritz](https://github.com/fritzccc/fritz-zsh-theme) - Works well on dark backgrounds. Includes `git` status decorations.
* [frlo](https://github.com/fiorillo/frlo) - Uses your computer's hostname to come up with a (hopefully) unique three-color theme to display in your prompt, so you know at a glance which machine you're logged into.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - 支持 `git` 和 `svn` 的彩色两行主题.
* [furio](https://github.com/hectorpalmatellez/furio-theme) - Fork of the [Cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) oh-my-zsh theme. with different colors and emojis.
* [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) - 彩色主题，在深色背景下效果更好.
* [gaia](https://github.com/gcaracuel/gaia.zsh-theme) - Originally a fork of [Bureau](https://github.com/isqua/bureau) adds new virtual environments info to the prompt: Kubernetess, virtualenv, rbenv and Java versions. Includes git status integration.
* [gal](https://github.com/x6r/gal) - gal is based on [gallois](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme).
* [garden](https://github.com/fecat233/garden) - Works better with a dark terminal background, includes `git` status decorations.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto prompt with the information you need the moment you need it.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires `rvm` & `git` plugins.
* [gbt](https://github.com/jtyr/gbt)  - Go Bullet Train 是一个非常可定制的提示生成器，灵感来自 Bullet Train，运行速度更快. 包括许多不同状态的汽车.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - 将 oh-my-zsh gentoo 主题拆分为一个单独的 repo，供非 omz 用户使用.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) - 将主机信息添加到 [geometry](https://github.com/geometry-zsh/geometry) theme.
* [geometry](https://github.com/geometry-zsh/geometry) - 一个最小的 ZSH 主题，可以将任何功能添加到左侧提示符或（异步）右侧提示符中.
* [ghoti](https://github.com/lonr/ghoti)  - 模仿 `fish-shell` 默认提示. 包括 `git` 装饰.
* [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) - Inspired by [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme), 包括 `git` 装饰、IP 地址、主机和路径.
* [gimbo](https://github.com/gimbo/gimbo.zsh-theme) - A variant of [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) with more features, a little eye candy and context-sensitive extra lines. Includes `git` status decorations, history number, username/hostname context, directory status, status of last command if it failed, and the Python virtualenv name if present.
* [gimme](https://github.com/nralbrecht/gimmezsh)  - 带有 `git` 集成的 ZSH 的简单主题. 灵感来自 [gitsome](https://github.com/mtully/gitsome) theme.
* [girazz](https://github.com/mdentremont/girazz) - A modification to the gnzh theme which adds `vi` mode to the right prompt.
* [git-prompt (awgn)](https://github.com/awgn/git-prompt) - A fast `git` prompt for `bash`, `zsh` and `fish`.
* [git-prompt (olivierverdier)](https://github.com/olivierverdier/zsh-git-prompt)  - 显示有关当前 `git` 存储库的信息. 特别是分支名称、与远程分支的差异、暂存或更改的文件数等.
* [git-prompt (woefe)](https://github.com/woefe/git-prompt.zsh) - A fast, customizable, pure-shell, asynchronous Git prompt for ZSH heavily inspired by Olivier Verdier's [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) and very similar to the "Informative VCS" prompt of fish shell.
* [git-prompt-kit](https://github.com/olets/git-prompt-kit) - 一组可配置的组件，用于以最少的编码创建功能丰富、高性能的 Git 感知 zsh 提示（又名主题）.
* [git-simple](https://github.com/ZakharEl/git-simple-theme) - 简单的主题，包括详细的 `git` 状态装饰.
* [gitsome](https://github.com/mtully/gitsome) - 带有 `git` 信息的超级简单提示，针对 [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) color scheme.
* [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) - 显示命令和 `git` 状态装饰.
* [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) - When in a `git` repo, it shows the location from the `git` repository root folder. When not in a `git` repo, it shows the path relative to home, `~`.
* [gitster (zimfw)](https://github.com/zimfw/gitster) - Zim fork of shashankmehta's [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) prompt theme
* [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) - Forked from the original [gitster](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) theme.
* [gk3000](https://github.com/gk3000/gk3000-oh-my-zsh-theme) - Includes `git` status decorations and full path to current directory.
* [glimmer](https://github.com/martnu/glimmer) - Includes `git` branch, time and user@host.
* [gndx](https://github.com/gndx/gndx-zsh-theme) - 包括 `git` 状态、主机名、目录和最后一个命令退出状态装饰.
* [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) - Customization of [gnzh.zsh-theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 来自 oh-my-zsh.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) - Theme for iTerm 2 and ZSH, includes `git` decorations, user@host, path and date.
* [gops](https://github.com/noxer/gops)  - 快速类似电力线的提示. 包括 `git` 状态、当前目录、根状态装饰.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - 简单但信息丰富的主题，包括 `git` 装饰和最后一个命令的返回状态.
* [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) - Minimalist, includes `git` status decorations.
* [grs](https://github.com/gersontpc/zsh-theme-grs) - Includes `git` status decorations, user id and working directory.
* [gruvbox (hgaiser)](https://github.com/hgaiser/gruvbox-zsh) - Sets colors from the [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [gruvbox (sbugzu)](https://github.com/sbugzu/gruvbox-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874), 使用相同的颜色 [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [guezwhoz](https://github.com/guesswhozzz/guezwhoz-zshell) - Minimalist, includes `git` status decorations.
* [gundam](https://github.com/adriamanu/gundam-zsh-theme) - Gundam flavored theme. Includes decorations for current directory, username, date and `git` status.
* [guri](https://github.com/victorfsf/guri) - 一个简单快速的 Oh-My-Zsh 主题，基于 [Pure](https://github.com/sindresorhus/pure)'s design.
* [hackersaurus](https://github.com/bhilburn/hackersaurus) - A theme with `git` status and exit code of last command run embedded in the prompt. Related to [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [halil](https://github.com/5m0k3r/zsh-themes) - oh-my-zsh 的分叉 [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) theme.
* [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme) - A simple theme with the first character being 花(hana), the kanji for flower. This theme was inspired by a keycap set called DSA Hana. This pairs well with the [hana atom](https://github.com/arturoalviar/hana-matcha-syntax) theme. Includes `git` status decorations.
* [handy](https://github.com/hanleylee/handy) <i>- Colorful and lightweight theme.</i> <b>- 多彩和轻量级的主题。</b> <i>Shows root status, `git` status, current directory and `user@hostname` decorations.</i><b>显示 root 状态、`git` 状态、当前目录和 `user@hostname` 装饰。</b>
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) - Shows `git` branch and status, last command exit code, last command execution time if more than `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`.
* [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) - 基于氧化物，包括 `git` 状态装饰和当前用户/主机信息.
* [haribo](https://github.com/haribo/omz-haribo-theme) - 简单的 `git` 状态 + 提示中的时间戳.
* [hcompact](https://github.com/fusion809/zsh-theme) - Displays time, OS (including distro if on Linux), directory and whether running as root.
* [headline](https://github.com/Moarram/headline-zsh-theme) - A responsive ZSH theme featuring Git status information and a colored line above the prompt.
* [heart](https://github.com/gko/heart) - Heart themed prompt for light backgrounds.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - Simple, no-nonsense and clean, with support for `git` and return codes.
* [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - 基于 [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau), with added `git` status decorations and `npm` status.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hematite](https://github.com/bigdave/hematite) - Minimalist promot that tries to show only the status decorations that are actively useful at a given time.
* [hexagon](https://github.com/diogoazevedos/hexagon) - Minimalist zsh theme based on [geometry](https://github.com/geometry-zsh/geometry).
* [hfulldate](https://github.com/fusion809/zsh-theme) - 显示时间、日期、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - Inspired by robbyrussell theme + ssh connection status prompt.
* [hina](https://github.com/ucpr/hina) - Written in `golang`, includes `git` status decoration and kubernetes context.
* [hip-fellow](https://github.com/haitaim/hip-fellow) - 包括 `git` 状态装饰并使用标准字体.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - A variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [home](https://github.com/sheerun/home) - 漂亮而简短的单行主题，让您有宾至如归的感觉.
* [hometown](https://github.com/olets/hometown-prompt) - 一个功能丰富、高性能的 `git` 感知 ZSH 主题，包含用户、主机、时间、当前工作目录及其父级的段，以及 Git 存储库中详细的完整 Git 状态.
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - Honukai theme and colors for oh-my-zsh and iTerm 2.
* [horizontal](https://github.com/nuimk/horizontal) - 带有水平分隔符的两行提示.
* [hornix](https://github.com/fusion809/zsh-theme) - 显示时间和日期、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [horse-sh](https://github.com/emileswarts/horse-sh) - A very minimal brown/red ZSH theme.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - Simple and clean, includes the return code of the last command executed.
* [hug](https://github.com/xxninjabunnyxx/hug-zsh) <i>- When you&#39;re working and need a hug.</i> <b>- 当你工作并需要一个拥抱时。</b> <i>Includes `git` status.</i><b>包括 `git` 状态。</b>
* [humbled](https://github.com/saravanabalagi/zsh-theme-humbled) - 一个简洁的主题，支持 `condaenv`、`virtualenv` 和 `git` 状态装饰，以粗体与工作目录对齐.
* [hydrogen](https://github.com/xylous/hydrogen)  - 一个简单的多行 zsh 主题. 它显示用户名、主机名、当前目录和 `git` 状态装饰.
* [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) - Designed to work with the hyper terminal theme, includes `git` status decorations.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) - 让您全面了解您正在处理的分支和存储库的状态，而不会弄乱您的终端.
* [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX) - Modified iGeek theme. Works with macOS out-of the box, includes `git` status decorations.
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - Works well on a dark background.
* [ice](https://github.com/Lenart12/ice.zsh-theme) - Very lightly modified [bureau](https://github.com/isqua/bureau) theme combined with [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [icicle](https://github.com/JamesConlan96/Icicle) - 包括 `git` 状态装饰，以及是否以 root 身份运行.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) - A super happy awesome Powerline-style, `git`-aware **prezto only** theme.
* [igorsilva](https://github.com/igor9silva/zsh-theme) - 显示当前目录、可自定义的分隔符、当前分支、`git` 状态.
* [iguanidae](https://github.com/btd1337/iguanidae-zsh-theme) - 包括 `git`、`nvm` 和 `venv` 装饰.
* [illusion](https://github.com/shabane/illusion) - Includes username, current working directory, `git` status and last command status decorators.
* [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) - Fork of [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) with spacing improvements and an updated icon. Includes `git` status information.
* [imp](https://github.com/igormp/Imp) - 基于 [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) and optimized for dark backgrounds.
* [infernus](https://github.com/jshiell/infernus-zsh-theme) - Minimalist theme, better on dark backgrounds.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) - Clean theme that shows `git` status, background jobs, remote host, and other information.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - An extension of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme to use powerline fonts.
* [itg](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy's theme.
* [ivy](https://github.com/ivyhjk/ohmyzsh-theme-ivy) - Works well on dark backgrounds. Includes user@host, `git` status and time decorators. Based on the [obraun](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#obraun) theme.
* [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme) - Based on refined and ys themes, includes `git` status decorations. Includes an optional iterm2 color scheme.
* [jake](https://github.com/JakeHuneau/Jake.zsh-theme) - 如果分支有未推送的更改，则显示时间、当前目录和 `git` 分支信息，包括分支名称和红色 +.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - Optimized for dark backgrounds, includes `git` status and `rvm` status.
* [jc](https://github.com/jclementex/jc-zsh-theme) - For dark terminal backgrounds, includes `git` status information.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - 松散地基于 ys 主题.
* [jerome](https://github.com/jeromescuggs/jerome-theme) - Colorful theme based on the [dieter](https://github.com/jeromescuggs/jerome-theme) theme, but with a yellow hostname. Includes `git` decorations.
* [jhleeeme](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) - Includes `git` and python virtualenv status decorations, user, pwd,time and system name.
* [jon](https://github.com/Jon-Schneider/jon.zsh-theme) - 一个简化 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) with the colors of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - Inspired by [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme), 包括 `git` 状态.
* [jovial](https://github.com/zthxxx/jovial) - 显示主机、用户、路径、开发环境、`git` 分支，其中 python venv 处于活动状态.
* [jpegleg](https://github.com/jpegleg/zshrc) - 类似于暗血主题，包括时间戳和 `git` 装饰.
* [js-magic](https://github.com/JSextonn/js-magic) - A simplified take on [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) . 包括当前工作目录和 `git` 状态装饰.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
* [just-another](https://github.com/supertassu/another-theme) - Just another theme, with hostname when you're sshed to another machine.
* [just-around-the-corner](https://github.com/DevinLeamy/just-around-the-corner)  - 倒计时直到圣诞节. 包括 `git` 状态装饰.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter) - Powerline-style theme with `git`, `svn`, `npm`, `rvm` and network awareness. Requires Powerline-compatible terminal font.
* [jyumpp](https://github.com/Jyumpp/jyumpp-zsh-theme) - Configuration file and installer for Powerlevel 10K.
* [kali](https://github.com/h4ck3r0/kali-theme) - Includes `git` decorations.
* [karu](https://github.com/zaari/karu) - 极简单行 ZSH 提示.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) - 包含其他主题的一些功能的主题.
* [kenton](https://github.com/notnek/zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) - 丰富多彩的主题，包括 iTerm 2 配色方案.
* [kgzsh](https://github.com/Kashugoyal/kgzsh) - Includes `git` status deorations, works well on darker backgrounds.
* [kido](https://github.com/KidoThunder/kido-zsh-theme) - Based on `ys` and `robbyrussell` themes. Includes decorators for the exit code of the last command run, python virtualenv and VCS status.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - 基于 Fishy 主题，但显示完整路径而不是缩写目录，并且仅在 `ssh` 会话和 docker 容器中显示 user@machine.
* [kirkdawson](https://github.com/kdawson133/KirkDawson) - Powerline-inspired. Includes prompt decorations for `git` status, last command exit status, user@hostname, working directory and whether the user is running as root.
* [kiss](https://github.com/rileytwo/kiss) - Simple theme for oh-my-zsh, VSCode, iTerm2, Neovim, and RStudio. Includes `git` status decorations.
* [kketcham](https://github.com/prototype27/kketcham) - Theme with nifty colors on the `git` info.
* [klassiker](https://github.com/mrdotx/zsh-theme) - 带有 `git` 装饰的极简主题.
* [korittg](https://github.com/dkorittki/korittg-zsh-theme)  - 简约但内容丰富. 包括 `git` 状态、当前目录和 `kubectl` 上下文和命名空间的装饰.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme)  - 最适合深色背景. 包括 `git` 状态装饰.
* [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - Two line theme designed for dark terminals, has `git` decorations.
* [krak3n](https://github.com/krak3n/zsh-theme) - Shows golang version and the current `git` branch.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) - A dark theme for ZSH.
* [kube](https://github.com/tigerjz32/kube-zsh-theme) - 基于 [macos-terminal](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal), includes `kubectl` context. Has time, directory, and `git` status decorations.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme)  - Agnoster 前叉针对日晒终端进行了优化. 需要与电力线兼容的字体.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) - Colorful theme with `git` and `hg` status information, ability to add host-specific colors to hostname.
* [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme) - A simple theme with the first character being 九(kyuu), the number 9. The primary color is blue with a magenta accent. Includes `git` status decorations.
* [lagune](https://github.com/noplay/lagune) - 一个最小的 ZSH 主题.
* [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) -  Inspired by the robbyrussell [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) theme. Includes `git` status decorations.
* [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) - A ZSH theme optimized for `git` users who use unicode-compatible fonts and terminal applications.
* [lambda-blazinggit](https://github.com/zalefin/lambda-blazinggit) - Includes blazing fast, detailed `git` information. Requires Nerd Fonts and the [gitstatus](https://github.com/romkatv/gitstatus) 插入.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - Minimalist prompt that includes `git` information.
* [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) - Simple theme based on lambda with `git` status and virtualenv information.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - A simple ZSH theme, optimized for `git` usage.
* [lambda-p](https://github.com/paimanbandi/lambda-p) - Inspired by the [lambda mod](https://github.com/halfo/lambda-mod-zsh-theme) and [Lambda V](https://github.com/vkaracic/lambdav-zsh-theme) 主题. 包括 `git` 状态装饰.
* [lambda-pure](https://github.com/marszall87/lambda-pure) - 基于 Pure 的最小 ZSH 主题，添加了 NodeJS 版本.
* [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) - A combination of the Lambda and Fishy themes, includes `git` status decorations.
* [lambda-zen](https://github.com/seamile/lambda-zen) - inspired by [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) with graphical `git` status decorations.
* [lambder](https://github.com/avillen/zsh-theme-lambder) - Includes `git` status decorations, works best with a dark terminal theme.
* [laniksj](https://github.com/LanikSJ/laniksj-zsh-theme)  - 在深色背景下效果最佳. 基于伟大的`ys`主题和 [Honukai ZSH Theme](https://github.com/oskarkrawczyk/honukai-iterm-zsh). Shows root status and `git` status decorations.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - Optimized for dark terminals, has variants for local and remote systems.
* [leafia](https://github.com/Ghostrick/leafia-prompt) - Leafy prezto theme that shows `git` status information.
* [lean](https://github.com/miekg/lean) - Inspired by [pure](https://github.com/sindresorhus/pure). Includes `git` status and background job decorations.
* [lemon](https://github.com/carlosvitr/lemon_zsh)  - 许多美丽的颜色供您欣赏. 小心和耐心地完成. 包括 `git` 状态和 ruby​​ 版本装饰.
* [leon](https://github.com/prince-an/Leon_zshTheme)  - 在浅色背景下效果很好. 包括 `git` 状态、时间、用户名@主机、工作目录和最后一个命令退出状态装饰.
* [leverage](https://github.com/gschnall/leverage) - 基于 [minimal](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme), uses colors, and an extra `¬` character, to better distinguish the command line prompt from your output.
* [lewis](https://github.com/lewisflude/oh-my-lewis)  - 黑色、白色和红色主题. 显示 `git` 状态信息.
* [lightbulb](https://github.com/lightbulb703/lightbulb-zsh-theme) - Includes decorations for kernel, OS version, uptime and `git`.
* [lighthaus](https://github.com/lighthaus-theme/zsh) - A prompt that compliments the [Lighthaus](https://github.com/lighthaus-theme/lighthaus) 主题. 显示 `git` 信息、github/gitlab 徽标并在发生更改时显示更改.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) - Minimalist theme, best on a dark terminal background.
* [lilith](https://github.com/aknackd/zsh-themes) - 修改 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) and [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [lime](https://github.com/yous/lime) - Simple and easily customizable ZSH theme.
* [limpide](https://github.com/shooteram/limpide) - Modified version of [miloshadzic](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) theme which displays parent and current directory.
* [linuxer](https://github.com/patrick330602/linuxer) - 灵感来自 Yaris Alex Gutierrez  [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh), Yad Smood 的 `ys`, 和 [Bureau](https://github.com/isqua/bureau) theme.
* [linuxero](https://github.com/andreshincapier/linuxero) - Minimalist. Includes decorations for root status, current directory, `git` status, current ruby rvm environment and current python virtualenv.
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt with useful information when you need it. It shows you what you need when you need it. You will notice what changes when it changes, saving time and frustration.
* [lish](https://github.com/bashelled/lish) - A casual theme. No roughness, just smooth. Includes `git`, user@host, last command exit status, current directory, current time and root status decorators.
* [liver](https://github.com/RenoirTan/liver.zsh-theme) - Colorful, includes `git` status, user, host, current and relative path to the current repository root decorations.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) - Minimalist theme used by discerning llamas.
* [logico](https://github.com/logico/logico-zsh-theme)  - 有 `git` 装饰. 显示 vi 模式的远程状态和指示灯.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - Texas-themed theme based on Sindre Sorhus' pure theme.
* [longsilvern](https://github.com/long263/longsilvern-zsh-theme) - Includes `git` and compact `pwd` decorations.
* [lorond](https://github.com/lorond/zsh-lorond/) - Compact version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme). Includes `git` status, works with standard fonts.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme)  - lambda-mod 主题的变体. 具有 `git` 装饰，需要与电力线兼容的终端字体.
* [luke](https://github.com/xueguangl23/luke_zsh_theme)  - 包括 `git` 装饰. 基于 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh theme.
* [lukerandall-extended](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) - Extended version of the [lukerandall](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) theme. Includes decorations for `git` status and the status of the last command run.
* [lunachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/lunachar.zsh-theme) - Minimalist theme.
* [macos](https://github.com/alejandromume/macos-zsh-theme) - Includes `git` status decorations.
* [mad](https://github.com/MartinWie/ohmyzsh-theme-mad) - Includes `git` status and last command execution time decorations.
* [magicmace](https://github.com/zimfw/magicmace) - Inspired by xero's ZSH prompt and [eriner's prompt](https://github.com/zimfw/eriner). Includes status codes for active python `venv`, exit status of last command, shortened working directory, `git` status decorations.
* [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN's magico theme.
* [maivana](https://github.com/nylo-andry/zsh-themes) - Includes `kubectl` context, `git` status decorations.
* [materialshell](https://github.com/carloscuesta/materialshell) - A [material design](https://material.io/guidelines/style/color.html) 您的外壳主题具有良好的对比度和重要部分的颜色流行. 专为保护眼睛而设计.
* [matrix](https://github.com/pot-code/matrix-zsh-theme) - 变体 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) styled to look like something in the Matrix movie trilogy. Includes `git` status decorations.
* [matter](https://github.com/mrobillard/matter-zsh-theme) - Shows `git` status, AWS vault role, background jobs, exit code of last command & hostname.
* [mau](https://github.com/vichargrave/mau) - A ZSH theme with a cat twist. Includes `git` status decorations. Based on the [kphoen](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kphoen.zsh-theme) and [smt](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/smt.zsh-theme) 主题.
* [mbolis](https://github.com/mbolis/mbolis-zsh-theme) - Includes `git` decorations, changes prompt color if root user, active jobs, and [jenv](https://github.com/jenv/jenv) 一体化.
* [mdmini](https://github.com/MarioDena/MDmini) - Includes `git` and `ssh` status decorations.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt)  - 包含键盘模式、所有权信息和其他上下文信息的最大化提示，以 λ 作为提示字符. 需要 [hooks](https://github.com/willghatch/zsh-hooks) 插入.
* [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) - 包括 `git` 状态装饰，如果非零则显示最后一个命令的退出代码.
* [mexassi](https://github.com/Mexassi/mexassi-zsh-theme) - Checks the `/sys/class/power_supply` folders to determine if the system is installed on a laptop or desktop machine. Reads the battery percentage grepping acpi command and displays it in the prompt. Includes `git` decorations.
* [mh-fzj](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) - Includes `rvm` and `git` status decorations.
* [michaelpass](https://github.com/michaelpass/michaelpass.zsh-theme) - POSIX 友好的跨平台 [alanpeabody](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) mod w/ convenient timestamps and full git/ruby support.
* [midin](https://github.com/xlshiz/midin) - 适用于深色终端背景，包括 `git` 状态装饰.
* [mike-was-here](https://github.com/leguim-repo/mike-was-here-theme/) - Minimalist, includes `git` status decorations.
* [milight](https://github.com/frodoslaw/milight-zsh) - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
* [min](https://github.com/andrepolischuk/min) - A minimalistic ZSH prompt.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind.
* [mini-simple](https://github.com/ysl2/mini-simple-zsh-prompt) - Minimalist. Includes `vcs` status decorations.
* [minima (Brolly0204)](https://github.com/Brolly0204/zsh-minima) - Includes `git`, `node`, `golang`, `yarn`, `php`, `docker` and `python` status decorations.
* [minima (ednikolenko)](https://github.com/ednikolenko/minima) - A minimal ZSH theme with `git`, `docker`, `go`, `node`, `npm`, `python` and other indicators. Uses unicode characters for some markers.
* [minimal (5amu)](https://github.com/5amu/minimal-prompt) - Minimal prompt, uses nerdfonts. Includes `git` and `vpn` status decorations.
* [minimal (casalinovalerio)](https://github.com/casalinovalerio/minimal-prompt) - 最小提示，包括 `git` 和 vpn 状态装饰.
* [minimal (glsorre)](https://github.com/glsorre/minimal/) - minimal asynchronous ZSH theme optimized for use with the [Fira Code](https://github.com/tonsky/FiraCode) 字体和 [Solarized Light](https://ethanschoonover.com/solarized) terminal theme.
* [minimal (subnixr)](https://github.com/subnixr/minimal) - Minimal yet feature-rich theme.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) - Theme for dark terminals, includes `git` decorations in the right-side prompt.
* [minimal2](https://github.com/PatTheMav/minimal2) - A minimal and extensible ZSH theme. Forked from [subnixr's original](https://github.com/subnixr/minimal) and adapted for [Zimfw](https://github.com/zimfw/zimfw).
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) - Inspired by kolo theme from oh-my-zsh.
* [mira](https://github.com/mbStavola/mira) - 一个修改 [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) 带有时间信息和简化的开始提示.
* [mirage](https://github.com/robin-pfeiffer/ohmyzsh-mirage-theme/) - Includes prompt decorations for `git` status, last command exit code, whether `sudo` timestamp file is present and current active Python virtual environment.
* [miramare](https://github.com/franbach/oh-my-deepin-miramare) - Includes `git` status decorations. Works best with [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
* [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs 的 ZSH 主题.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - Optimized for dark backgrounds.
* [mnml](https://github.com/mnml-theme/prompt) - 带有 `git` 状态装饰的最小主题.
* [mochi2](https://github.com/mochidaz/zsh-themes) - Minimalist theme. Includes `git` and `hg` status decorations.
* [mochi](https://github.com/mochidaz/zsh-themes) - Simple theme, designed to resemble rust main function. Includes `git` and `hg` status decorations.
* [moderno](https://github.com/obrassard/moderno-zsh) - A simple and modern ZSH theme inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme)  Oh-My-ZSH 的主题. 包括 `git` 状态装饰.
* [modesty](https://github.com/saravanabalagi/zsh-theme-modesty) - A clean and modest ZSH theme with `condaenv`, `virtualenv` and `git` status decorations displayed neatly right aligned.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874).
* [momoyo](https://github.com/momoyo-droid/momoyo-zsh-theme)  - 让人想起电力线. 包括 `git` 状态、用户名和工作目录的装饰.
* [moonline](https://github.com/kagamilove0707/moonline.zsh) - Minimal but easily extensible prompt.
* [moux](https://github.com/gagbo/moux) - Works well with a dark terminal background, includes `git` decorations in `RPROMPT`.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - Provides useful information (in your prompt) about the repository that you are in. It currently works for [Git](https://git-scm.com/) and [Mercurial](https://www.mercurial-scm.org/), under [ZSH](https://en.wikipedia.org/wiki/Zsh) as well as [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [multiline](https://github.com/jan-auer/zsh-multiline) - Powerline-esque theme based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [muslim](https://github.com/nksoff/muslim) - 一个简单的最小 ZSH 提示主题.
* [musy](https://github.com/THaGKI9/musy-zsh-theme) - Inspured by muse theme. Includes `git` status decorations.
* [my-hl2](https://github.com/liamm91/my-hl2)  - 包括 virtualenv、`git` 状态和目录装饰. 基于 omz  [half-life](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/half-life.zsh-theme) theme.
* [myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia's myzsh theme.
* [mzt](https://github.com/honbey/mzt) - 设置`LS_COLORS`，着色`diff`并包括`git`状态和当前工作目录装饰.
* [nanofish](https://github.com/tweekmonster/nanofish) - Adds fish-style directory prompt to nanotech theme.
* [nbrylevv](https://github.com/nbrylevv/nbrylevv-zsh-theme) - Minimalist theme with text `git` status decorations.
* [nctu](https://github.com/leovincentseles/nctu.zsh-theme)  - 强调速度的轻量级主题. 包括 `git` 状态装饰.
* [neewbie](https://github.com/neewbee/neewbee.zsh-theme) - Minimal theme with `git` decorations. Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell).
* [neon-potato](https://github.com/algosuna/neon-potato)  - 多彩和简约的主题. 包括 `git` 装饰.
* [neon](https://github.com/sahariko/neon) - 带有 `git` 装饰的漂亮且最小的 ZSH 主题.
* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - A prompt theme for ZSH with Nerd Fonts.
* [nescalante](https://github.com/nescalante/zsh-theme) - Optimized for dark terminal backgrounds, includes `git` decorations.
* [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) - Includes `git` decorations and `vi`-mode indicator.
* [newt](https://github.com/softmoth/zsh-prompt-newt) - Fat & fast theme – beautiful inside and out, styled segments done right. Extremely customizable, includes `git`, username, execution time, directory, background jobs and edit mode decorations.
* [newton](https://github.com/sebastienfilion/zsh.newton) - Includes `git` status and external IP address decorations.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - A very basic theme which just features an macOS bike icon.
* [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - Colorful, shows `git` status decorations.
* [nikitakot](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme) - Small and simple oh-my-zsh theme. Shows current directory and 2 directories behind, `git` and `nodejs` status decorations.
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - Based on af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - A simple oh-my-zsh theme.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - 带有 `git` 状态装饰的极简主义 ZSH 主题.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) - oh-my-zsh's node theme, broken out to make it easier to use with other plugin managers.
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - 基于 ys 主题，添加了 NodeJS 版本（来自 NVM 插件）.
* [noon](https://github.com/silky/noon.zsh-theme) - Has light and dark variants, shows `git` information.
* [nord](https://github.com/TyWR/Nord-zsh) - Includes `git` status decorations and displays the active conda environment.
* [normanius](https://github.com/normanius/normanius-zsh-theme) - Derived from [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [nothing](https://github.com/eendroroy/nothing) - Lightning fast and really simple because it has almost nothing in it.
* [nox](https://github.com/kbrsh/nox) - Dark theme, displays the current working directory and git status.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme) - A clean, distraction free and `git` focused development theme. Shows path relative to `git` root (or ~ when outside `git` repo), time since last commit, current SHA, branch and branch state.
* [nunorc](https://github.com/nunorc/nunorc.zsh-theme) - Minimalist theme, works well on dark backgrounds. Includes `git`, `mercurial` and `svn` satus decorations.
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - A simple theme for prezto and oh-my-zsh.
* [nuts](https://github.com/rafaelsq/nuts.zsh-theme) - Minimalist theme, includes `git` status decorations and time.
* [oblong](https://github.com/Ansimorph/oblong) - Simple `bash`-inspired theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [basher](https://gitlab.com/Spriithy/basher). Includes status decorations to show if user is root, the exit status of last command run, `git` branch and its clean/dirty status.
* [odie](https://github.com/masterodie/zsh-theme-odie/) - Works well on a dark background. Includes `git` status, python virtualenv and `vi`-mode status decorations.
* [odin](https://github.com/tylerreckart/odin) - Odin is a `git`-flavored ZSH theme.
* [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) - Multiline theme with `git` decorations.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - 对 bash 和 ZSH 的自以为是的提示.
* [oh-my-posh](https://ohmyposh.dev/) - Not ZSH-specific, but very nice and works with ZSH. Allows you to use the same configuration for prompts in all shells.
* [oh-my-via](https://github.com/badouralix/oh-my-via) - Theme for ZSH which mainly forks the historical theme used on VIA servers.
* [ohmypc](https://github.com/joselpadronc/OhMyPC) - Works well with dark terminal windows. Includes `git` decorations.
* [om](https://github.com/sirshikher/zsh-om) - 最小主题，适用于深色背景，包括 `git` 状态装饰.
* [omszt](https://github.com/MU001999/omszt) - 带有 `git` 装饰的极简主义主题。
* [omuse](https://github.com/ouuan/omuse-zsh-theme) - Based on Oh-My-ZSH's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme). Has decorations for `git` status, time, absolute pwd, RAM usage, time used by last command, and last command exit status.
* [owczarczak](https://github.com/ThemysciraData/owczarczak.zsh-theme)  - 灵感来自比拉、节食者和菲诺时间. 包括 `venv` 和 vcs 状态装饰.
* [owi](https://github.com/owitech/zsh-theme/) - Minimalist theme with `git` status decorations.
* [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) - Includes `git` status and virtualenv information.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - A Minimalistic and Dark ZSH theme.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme)  OZ0NO - 让我们呼吸干净的 ZSH.
* [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) - 一个主题 [powerlevel10k](https://github.com/romkatv/powerlevel10k) prompt that puts an emphasis on simplcity while still getting important information across.
* [pad](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme.
* [page](https://github.com/SLIB53/page-zsh-theme) - A simple theme with VCS support. The prompt shows 1 level of the current working directory, branch, and a color coded curved fat arrow.
* [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) - Allows display of host information, includes `git` branch decoration.
* [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) - Shows detailed `git` status information with icons in the prompt.
* [panda](https://github.com/davymai/oh-my-zsh-panda-theme)  - 包括 `git` 和 `root` 状态装饰. 最好在深色背景上.
* [papercolor](https://github.com/erikschreier/PaperColor-themes) - Color scheme for ZSH, `vim` and `tmux`. Includes `git` status decorations.
* [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) - Includes `git` status decorations, command run time in milliseconds. Requires coreutils on macOS.
* [pastel](https://github.com/iboyperson/pastel) - 一个受启发的 ZSH 主题 [sugar-free](https://github.com/cbrock/sugar-free). Includes `git` decorations.
* [pecodez](https://github.com/pecodez/pecodez-zsh-theme) - Optimized for dark terminals. Has decorators for `snyk` version, `node` version, AWS profile, kubernetes context and `git` status.
* [pentesters](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) - Modified version of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) 渗透测试者的主题，其中包括渗透测试日志记录的日期、时间和 IP 地址.
* [persi](https://github.com/persiliao/persi-zsh-theme) - Includes `git` decorations. Works with both light and dark backgrounds.
* [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) - Minimal theme in the spirit of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and Pure Shell themes.
* [phantomk](https://github.com/phantomk/phantomk.zsh-theme) - 丰富多彩的主题，包括 go 版本、node 版本和 `git` 状态.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - 一个干净简单的 ZSH 主题，灵感来自于 [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) theme.
* [pi](https://github.com/tobyjamesthomas/pi) - A minimalist theme with `git` status decorations.
* [piboy](https://github.com/sflems/piboy-zsh-theme) - A simple and elegant multi-line theme for ZSH. Includes a colourized timestamp, `git` & syntax highlighting, and elevated root theme.
* [plain-ui](https://github.com/purveshpatel511/plain-ui) - 极简主义，但包括 `git` 状态装饰.
* [plain](https://github.com/jimeh/plain.zsh-theme) - A plain and simple theme for ZSH which shows basic `git` information.
* [planet](https://github.com/borb/planet-zsh) - A slimmed down version of [steef](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) from [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) - Simple, no-frills theme.
* [plantyhoe](https://github.com/totoroot/plantyhoe.zsh-theme) - Minimalist theme based on a love of plants and apples. Includes `git` status decorations.
* [platypus](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) - Shows working directory, the return status of the last command, and `git` current branch.
* [polyglot](https://github.com/agkozak/polyglot) - a dynamic prompt for `zsh`, `bash`, `ksh93`, `mksh`, `pdksh`, `dash`, and busybox `ash` that uses basic ASCII symbols (and color, when possible) to show username, whether it is a local or remote `ssh` sesssion, abbreviated path, `git` branch and status, exit status of last command if non-zero, any virtual environment created with `virtualenv`, `venv`, `pipenv`, `poetry`, or `conda`.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM's basic oh-my-zsh custom theme.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - Programmer's theme with `git` status, ruby version and project path.
* [powerbash](https://github.com/erikschreier/powerbash-zsh) - Works well with dark terminal backgrounds, includes `git` status decorations.
* [powerless](https://github.com/martinrotter/powerless) - Tiny & simple pure ZSH prompt inspired by powerline.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - A fast reimplementation of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ZSH theme. Can be used as a drop-in replacement for powerlevel9k, when given the same configuration options it will generate the same prompt, only faster.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k is a theme for ZSH which uses [Powerline Fonts](https://github.com/powerline/fonts). It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen)， 和 [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 附加组件 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - A two-line version of powerline: one for information, one for input.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) - Another take on a powerline theme. Nicely configurable, but requires at least a 256 color-capable terminal with a powerline-compatible terminal font.
* [powerline (syui)](https://github.com/syui/powerline.zsh) - A `git` aware powerline theme.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
* [powerline-go](https://github.com/justjanne/powerline-go)  - 一个漂亮实用的低延迟提示，用 golang 编写. 包括 `git` 和 `hg` 状态装饰、上次命令运行的退出状态、当前 Python 虚拟环境、是否在 [nix](https://nixos.org/) shell, and is easy to extend.
* [powerline-hs](https://github.com/rdnetto/powerline-hs) - A [Powerline](https://github.com/powerline/powerline) clone written in Haskell. It is significantly faster than the original implementation, and makes the shell noticeably more responsive.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - 在 Ruby 中创建，使用电力线字符来模拟具有有用信息的药丸.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell) - Beautiful and useful prompt generator for Bash, ZSH, Fish, and tcsh. Includes `git`, `svn`, `fossil` and `hg` decorations, Python virtualenv information, and last command exit status.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - A [powerline](https://github.com/Lokaltog/vim-powerline)-like prompt for Bash, ZSH and Fish. Shows important details about git/svn/hg/fossil branch and is easy to customize/extend.
* [powerline-train](https://github.com/sherubthakur/powerline-train) - 电力线变体.
* [powerline](https://github.com/carlcarl/powerline-zsh) - A [Powerline](https://github.com/Lokaltog/vim-powerline)- 类似提示，基于 [powerline-bash](https://github.com/milkbikis/powerline-bash). Displays virtualenv, `git` status information and the exit code of the last command run.
* [powerzeesh](https://github.com/sevaho/Powerzeesh) - A Powerline based ZSH theme. It aims for simplicity, showing information only when it's relevant, optimized for speed and look. Inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) - A collection of themes for Sublime Text, Terminal, iTerm 2 and ZSH.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) - 为黑暗终端主题优化的主题.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - oh-my-zsh 的云提示的 Prezto 端口.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda 主题（用于 prezto）.
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
* [probe](https://github.com/probe2k/probe_zsh) - Includes `git` status decorations.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight ZSH prompt, based on the powerline font from the popular eponymous `vim` plugin, which works well for a dark background.
* [prompt](https://github.com/nathanblair/prompt) - A lightweight prompt consistent across `sh`, `dash`, `ash`, `zsh`, and `pwsh`. Includes `git` status decorations.
* [prompt_j2](https://github.com/malinoskj2/prompt_j2) - Has a dynamic exit status indicator, can change to two lines dynamically to display context.
* [promptus](https://github.com/willeccles/promptus) - Simple, minimalist and configurable shell prompt program in C which can be used to make your prompt the same on any shell. Includes exit code and working directory decorations.
* [pronto](https://github.com/jthat/zsh-pronto) - Simple and fast theme with `git` decorations and timing information.
* [ps1.py](https://github.com/jwodder/ps1.py) - Has `git` status, truncated directory, `chroot` and `virtualenv` prompt decorations.
* [pskfyi](https://github.com/pskfyi/zsh-theme) - 基于 [lambda](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#lambda). Themed for ubuntu but easily tweaked.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - 易于定制，受 [spaceship](https://github.com/denysdovhan/spaceship-prompt).
* [pure-agnoster](https://github.com/yourfin/pure-agnoster) - Mashup of pure and agnoster. Has `git` decorations and works well with both dark and light terminal backgrounds.
* [pure](https://github.com/sindresorhus/pure)  - 一个漂亮、最小和快速的 ZSH 提示. 包括 `git` 状态装饰，如果最后一个命令失败，提示变为红色，在远程会话或容器中时的用户名和主机装饰，以及进程运行时的当前文件夹和命令.
* [purify (banminkyoz)](https://github.com/banminkyoz/purify) - A simple, fast & cool prompt.
* [purify (kyoz)](https://github.com/kyoz/purify) - A clean and vibrant theme, best on dark backgrounds. Includes `git` status decorations.
* [purity](https://github.com/petermbenjamin/purity) - Inspired by robbyrussell theme and the [pure](https://github.com/sindresorhus/pure) prompt.
* [purs](https://github.com/xcambar/purs) - A fast [pure](https://github.com/sindresorhus/pure)-inspired prompt written in [Rust](https://www.rust-lang.org/).
* [pustelto](https://github.com/Pustelto/shell_theme) - 色彩缤纷的主题灵感来自 [Spaceship](https://github.com/denysdovhan/spaceship-prompt) theme, includes `git` decorations.
* [qi3ber2](https://github.com/nichus/qi3ber2) - A dark multiline theme. Includes `git`, load average and exit code of last command decorators.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon)  - 针对深色背景进行了优化，包括 `git` 信息. 主题 repo 包括 iTerm 2 和终端颜色设置.
* [quewui](https://github.com/kauefontes/oh-my-quewui) - Simple and clean theme optimized for dark terminal themes. Includes status decorations for the current time, user, directory and `git` status.
* [r3nic1e](https://github.com/r3nic1e/r3nic1e) - [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) variant with battery status, `git/hg` status, time, kubernetes context and namespace, non-zero exit code of last command and date decorations. Requires Powerline font.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - 基于 af-magic 和 posh-git.
* [radium](https://github.com/dimitardimitrov/radium) - Designed for dark terminals, (works best with [Solarized](https://github.com/altercation/solarized) iTerm 2 theme) (prezto).
* [radius](https://github.com/erikcc02/radius-zsh-theme) - Includes `git` status decorations, includes [desk](https://github.com/jamesob/desk) support.
* [rafiki](https://github.com/akabiru/rafiki-zsh) - Adds emojis to your ZSH terminal.
* [ramiel](https://github.com/aknackd/zsh-themes) - Fork of the [node](https://github.com/skuridin/oh-my-zsh-node-theme).
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - 基于 [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) 和“robbyrussell”主题.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - Random emoji.
* [ranger-zoxide](https://github.com/fdw/ranger-zoxide) - 添加 [zoxide](https://github.com/ajeetdsouza/zoxide) support to the [ranger](https://github.com/ranger/ranger) console file manager.
* [raspberrysh](https://github.com/MaxMalinowski/raspberrysh) - Includes `git`, python, time, current host and path decorations.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) - 带有“git”状态装饰的简单而多彩的主题.
* [raz](https://github.com/razman786/ohmyzsh-theme-raz) - 最小提示，包括 `git` 状态装饰.
* [rb](https://github.com/rberenguel/rb-zsh-theme) - Powerline-styled ZSH theme based on [Agnoster](https://gist.github.com/agnoster/3712874), optimized for `git` and solarized terminals. Requires a Powerline-compatible font.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - Optimized for solarized terminal color schemes, includes `git` status decorations.
* [redline](https://github.com/DrissTM/redline.zsh-theme)  - 极简主义主题. 包括 `git` 状态、时间、用户.
* [reggae](https://github.com/nmercado1986/zsh-reggae-theme) - Compresses a lot of information into the prompt with color-coded status decorations.
* [rei](https://github.com/arturoalviar/rei-zsh-theme) - A simple theme with the first character being 零(rei), the number 0. Includes `git` status decorations.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), 优化为 [solarized](https://github.com/altercation/solarized) 终端主题.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - Prezto ZSH theme based on Sorin, using emojis for tracking GIT context.
* [rho](https://github.com/andrejreznik/rho-zsh-theme) - Minimalist theme.
* [ribbon](https://github.com/tactlessfish/ribbon-prompt) - Reminiscent of powerline. Includes Python `virtualenv` decorator.
* [river](https://github.com/revir/river-zsh-config) - Dark theme with `git` information.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - Based on ideas from the the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme and the project [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - Decorates the `robbyrussell` theme with output to indicate a **WIP** commit.
* [robbyrussell-fullpath](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) - 原本 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) with a fullpath in the prompt.
* [rocket](https://github.com/Alexandresl/rocket-zsh-theme) - Minimalist theme, includes `git` and `hg` status decoration.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - A dark theme.
* [roundy](https://github.com/nullxception/roundy) - fast, cute and roundy theme. Includes `git` decorations. Requires nerd fonts and a unicode-capable terminal application.
* [roz](https://github.com/rozNum/roz-zsh-theme) - Minimalist. Includes `git` status decorations, best on a darker background.
* [rs](https://github.com/rogeliosamuel621/rs-zsh-theme) - Includes `git` decorations. Requires unicode capable terminal.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) - Optimized for dark backgrounds.
* [rummik](https://github.com/rummik/zsh-theme) - @rummik's theme. Supports [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), and `git` status information in the prompt.
* [russtone](https://github.com/russtone/prompt-russtone) - Inspired by [pure](https://github.com/sindresorhus/pure) and [sorin](https://github.com/sorin-ionescu/prezto). Includes `git` status decorations.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - Colorful theme, includes `git` decorations and the current directory.
* [rzh](https://github.com/patwhatev/rzh) - Theme with git states indicated by emojis.
* [s1ck94](https://github.com/zimfw/s1ck94)  - S1cK94 的（第一次弃用，现已灭绝）最小提示的分支. 显示用户是否为 root、后台作业状态、vi 模式、最后一个命令的退出状态和 `git` 状态装饰.
* [s7c](https://github.com/Samega7Cattac/s7c.zsh-theme) - Works well with dark backgrounds. Includes `git` status decorations.
* [samshell](https://github.com/samuelb/samshell) - A minimalist zsh theme with `git`, kubernetes and python virtualenv decorations.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - Includes `git` status decorations, works well on a dark terminal background.
* [saturn](https://github.com/gantoreno/saturn-prompt) - A soft & minimalistic prompt for those who love space and want to have a bit of it on their terminal, featuring cool emojis & highly customizable prompt elements (such as icons, colors, time format, and more).
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) - Shows `git` status decorations, user@host information, the exit status of last command, and whether running as root.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - 当使用 `:sh` 命令时，显示 `vim` 是否在后台运行.
* [scythe](https://github.com/kostoskistefan/scythe)  - 让人想起电力线的主题. 包括`git`，最后一个命令退出状态和目录装饰.
* [sdkman](https://github.com/matthieusb/zsh-sdkman) - Add tab completions for [sdkman](https://sdkman.io/).
* [seashell](https://github.com/jottenlips/seasonal-zshthemes) - Minimal theme with sea-inspired emoji decorations. Includes `git` status decorations.
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - 这个主题使用了许多特殊的 unicode 字符来花哨，但是如果没有很好的字体支持，它可能会导致一些问题.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - 受节食者主题启发，使用颜色编码提供信息.
* [senpai](https://github.com/hiroru/senpai-zsh)  - 为 Devops 清理提示主题. 包括 `git` 状态信息、kubernetes 上下文、AWS 配置文件、GCP 项目和 Azure 活动云.
* [sepshell](https://github.com/sepehr/sepshell) - 基于丢失的旧 taybalt 主题的干净和最小的 ZSH 主题，具有 `git` 平分/合并/变基模式和可配置的提示符号.
* [serious](https://github.com/oliversandli/serious-zsh-theme) - 包括命令退出状态和 `git` 状态装饰.
* [seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - 一个简单的 omz 兼容主题，带有相应的 iTerm 2 配色方案.
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - An evolution of lean prompt which itself is a rewrite of pure.
* [shadow](https://github.com/agentshadow/shadow-zsh-theme) - 包括 `git` 状态、目录、主机名、用户名和时间装饰.
* [shayan](https://github.com/shayanh/shayan-zsh-theme) - Simple theme with `git` status decorations.
* [shelby](https://github.com/athul/shelby) - Fast, lightweight and minimal prompt written in pure `golang`. Includes decorations for last command exit status, `git` status and the current working directory.
* [shellder](https://github.com/simnalamburt/shellder) - Minimal theme with git branch display. Requires a Powerline-compatible font.
* [shichi](https://github.com/arturoalviar/shichi-zsh-theme)  - 一个简单的主题，第一个字符是七（shichi/nana），数字 7.原色是红色，带有黄色调. 包括 `git` 状态装饰.
* [shini](https://github.com/bashelled/shini)  - 一个小小的主题，只是大声喊叫. 包括目录、用户名、主机名、时间和 `git` 装饰.
* [shirnschall](https://github.com/shirnschall/shirnschall-zsh-theme) - Includes `git` status and `user@hostname` decorations.
* [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) - Forked from [sixlive](https://github.com/sixlive/sixlive-zsh-theme) . 有 `git` 装饰.
* [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) - Based on the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme. Includes `git` and `hg` status decorations.
* [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) - Includes `git` decorations.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - Simple theme which displays current directory and git information.
* [shtr0m](https://github.com/kyle-pollock/shtr0m) - Includes `git` status decorations.
* [siegerts](https://github.com/siegerts/zsh-theme) - 在正确的提示中包含 `git` 状态装饰.
* [silver](https://github.com/reujab/silver) - A cross-shell customizable powerline-like prompt heavily inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme). A faster rust port of [bronze](https://github.com/reujab/bronze). Requires [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) . 非常可配置，包括 `git` 状态装饰.
* [simpalt](https://github.com/m-lima/simpalt) - An information-rich small-footprint theme for ZSH based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [simple (daopengz)](https://github.com/DaopengZ/simple-zsh-theme) - Works well with both light and dark terminal themes. Includes `vcs`, `username` and `path` decorations.
* [simple (pavdmyt)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - Minimalist theme based on [robbyrussel](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) that embeds `git` status information in iTerm's window title bar instead of using space in the prompt.
* [simple (savecoders)](https://github.com/Savecoders/simpleTheme-zsh-theme) - 带有 `git`、`username` 和执行状态装饰的简单而简约的主题.
* [simple (tourcoder)](https://github.com/tourcoder/simple.zsh-theme) - 极简提示，包括 `git` 状态装饰.
* [simple (yhiraki)](https://github.com/yhiraki/zsh-simple-prompt) - Minimal prompt, doesn't require special fonts.
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - Powerline-inspired simple theme with `git` decorations.
* [simple-git](https://github.com/BazaJayGee66/simple-git-theme) - Minimalist theme inspired by [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme). Includes `git` decorations.
* [simple-yet-beautiful](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme) - Minimalist theme. Includes `git` status and `user@host` prompt decorations.
* [simplezsh](https://github.com/fr0zn/simplezsh) - Minimal theme with `git` info display.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme) - k-kinzal's sinon theme. Includes `git` status decorations.
* [sit](https://github.com/svensen/sit.zsh-theme) - Minimalist theme with `git`, command exit status and path decorations.
* [sixlive](https://github.com/sixlive/sixlive-zsh-theme) - This theme has a unique directory listing. When inside a `git` project, the directory display is scoped to the current repository root.
* [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9's ZSH theme.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Atom、Prism 和 ZSH 的主题系列灵感来自 He-Man 和宇宙大师的 Skeletor.
* [skill](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - 针对黑暗终端进行了优化，显示 `git` 状态装饰.
* [skull](https://github.com/tahadostifam/skull-zsh) - Includes `git` status, python virtual environment and ruby `rvm` status decorations.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH theme inspired by [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [odin](https://github.com/tylerreckart/odin).
* [slick](https://github.com/nbari/slick) - Inspired by the [pure](https://github.com/sindresorhus/pure), [purs](https://github.com/xcambar/purs) and [zsh-efgit-prompt](https://github.com/ericfreese/zsh-efgit-prompt). Requires `cargo` for installation.
* [slimline](https://github.com/mengelbrecht/slimline) - Minimal, fast and elegant ZSH prompt. Displays the right information at the right time.
* [sm](https://github.com/blyndusk/sm-theme) A **Simplist** & **Minimalist** theme for your **favorite** terminal. Includes `git` status decorations.
* [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) - 的变体 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 主题在 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - 带有快乐和悲伤面孔的提示.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme) - A minimalistic ZSH theme inspired by the old-fashioned hobbies. No verbose gimmicks, no emoji, no fidget spinners, and no other visual noise. Has both light and dark modes.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - 日晒电力线变体.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) - Solarized powerline-style theme for ZSH.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) - Color fix for robbyrussell's oh-my-zsh theme to work with [solarized](https://github.com/altercation/solarized) terminals.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) - 带有 `git`、`nvm`、rvm/rbenv/chruby、python、`ssh` 和其他有用状态指示器的主题.
* [spowerline](https://mbauhardt.github.io/spowerline/) - Written in scala, inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), [tmux](https://tmux.github.io) powerline、vim powerline 和 vim 状态插件.
* [spyrhoo](https://github.com/FajarKim/spyrhoo-zsh-theme) - Includes time, `git` and current directory decorations.
* [squanchy](https://github.com/gabrielecanepa/zsh-custom/tree/master/themes) - Minimalist theme. Includes `git`, `node` and `rbenv` status decorations.
* [ssfprompt](https://github.com/hugoh/zsh-ssfprompt)  - 简单、纤薄、快速. 包括 `ssh`、virtualenv 和 vcs 装饰.
* [staples](https://github.com/dersam/staples) - Based on bureau, displays user@host if connected through SSH.
* [starboy](https://github.com/prdpx7/Starboy) - 一个简单的 ZSH 主题.
* [starship](https://starship.rs/) - Minimal, fast, extremely customizable.
* [statusline](https://github.com/el1t/statusline) - A responsive ZSH theme that provides informational segments when you need them.
* [steef (danihodovic)](https://github.com/danihodovic/steeef) - ZSH steeef theme as a standalone repository. The purpose behind this repo is avoid having a dependency on oh-my-zsh when using the steeef theme. ZSH plugin managers such as Antibody can use the theme without having to use oh-my-zsh.
* [steef (zimfw)](https://github.com/zimfw/steeef) - A customizable version of [steeef's](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) theme.
* [steeple](https://github.com/erwanjugand/steeple-zsh-theme) - Minimalist theme with `git` status decorations.
* [stellachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/stellachar.zsh-theme) - Minimal, pastels.
* [sublime](https://github.com/pjmp/sublime) - A sublime, clean, minimalistic ZSH theme with `git` status decorations.
* [sugar-free](https://github.com/cbrock/sugar-free) - Based on the [Pure](https://github.com/sindresorhus/pure) and [Candy](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/candy.zsh-theme) 主题.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme) - Includes `git` status decorations. Works better on dark terminal backgrounds.
* [sulfurium](https://github.com/Sulfurium/zsh-theme) -sulfiumOS 的官方 ZSH 主题.
* [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) - Similar to [sunrise](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) but includes the active Ruby version.
* [superkolo](https://github.com/Minipada/superkolo) - 添加日期和返回状态到 [kolo](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) theme.
* [susi](https://github.com/carcruz/susi-zsh-iterm) - Includes `git` status decorations and an accompanying iTerm2 color scheme.
* [svs](https://github.com/SvS30/svs-theme) - 带有“git”状态和当前路径装饰的清洁和无干扰主题.
* [sy](https://github.com/ttttmr/sy-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), includes `git` status decorations.
* [t2er](https://github.com/t2er/t2er-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - Minimal ZSH theme optimized for dark backgrounds.
* [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) - Includes `git` status decorations and conda/virtualenv status.
* [termux](https://github.com/rooted-cyber/Termux-zsh-theme) - Minimalist theme.
* [termuxer](https://github.com/patrick330602/termuxer) - 主题灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和linuxer.
* [the-time-lord](https://github.com/jhwhite/the-time-lord) - A theme based on [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - 带有 `git` 状态的彩色主题.
* [theta-async](https://github.com/jesec/zsh_theme_theta-async) - Async version of [theta](https://github.com/eendroroy/theta). Includes vcs status information.
* [theta](https://github.com/eendroroy/theta) - Includes `git` and `hg` status decorations. Also has java, python, ruby, node, go and elixir version information.
* [theto](https://github.com/heyvito/theto-zsh-theme) - Simplistic theme.  Needs [Nerd Fonts](https://nerdfonts.com/), includes `vi`-mode status and `git` decorations.
* [thetraveler](https://github.com/bassopenguin/thetraveler) - 受 unraveler 启发，使用符号来显示 `git` 状态.
* [thnikk](https://github.com/thnikk/zsh-theme-thnikk) - A minimal version of the [spaceship](https://github.com/denysdovhan/spaceship-prompt) theme.
* [thyme (chenhao-ye)](https://github.com/chenhao-ye/thyme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme)， 和 [bullet-train](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme).
* [thyme (kawamurakazushi)](https://github.com/kawamurakazushi/thyme) - Simple theme with `git` status decorations.
* [toledo](https://github.com/mmatongo/toledo) - Quick minimalist theme with `git` status decorations.
* [tonni4](https://github.com/AndreyPuzanov/tonni4-zsh-theme) - Includes time and `git` status decorators.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh)  - 包括`git`信息； 最好在深色背景上.
* [tq](https://github.com/kitian616/tq-zsh-theme) - Displays `git` status, time, requires a Powerline font.
* [traffic](https://github.com/fcce/traffic-zsh-theme) - A dark theme for ZSH.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH.
* [trinity](https://github.com/de-luca/Trinity) - 一个简单的主题基于 [geometry](https://github.com/geometry-zsh/geometry). Includes `git` decorations.
* [tron](https://github.com/iDoTron/tron-zsh-theme) - Includes `git` status, working directory, time, user@host and return status of last command decorations.
* [tsotra](https://github.com/nylo-andry/zsh-themes) - Minimalist theme, includes `git` status decorations, k8s context, and `rvm` status.
* [turs](https://github.com/eikendev/turs) - Fast, minimal [Purs](https://github.com/xcambar/purs)-启发提示.
* [tvline](https://github.com/thvitt/tvline) - Derived from the [agnoster](https://gist.github.com/agnoster/3712874) 主题，添加电力线字体增强功能.
* [twilight](https://github.com/Henryws/twilight-prompt) - Minimalist, but includes last command exit status, `git` status and `user@hostname` decorations.
* [type0](https://github.com/MikereDD/type0_zsh-theme) - Inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) by yarisgutierrez. Includes `git` decorations.
* [typewritten](https://github.com/reobin/typewritten) - Minimal and informative theme that leaves room for what's important. Does asynchronous `git` decoration updates for speed.
* [ubunly](https://github.com/alejandromume/ubunly-zsh-theme) - Mimics the Kali Linux console. Note - this theme also rebinds a lot of keys and sets a bunch of ZSH options that themes should leave alone.
* [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) - 模仿默认的 Debian/Ubuntu `bash` 提示符.
* [ubuntu-with-vitamins](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) - Mimics the default Ubuntu prompt, but with `git` decorations.
* [ubuntu](https://github.com/janstuemmel/zsh-ubuntu-theme) - Minimal theme, includes `git` status decorations.
* [ultimate](https://github.com/b4b4r07/ultimate) - 带有 `git` 指示器、vim 模式指示器和缩短路径的极简主义主题.
* [unicorn](https://github.com/juliuscaesar/unicorn) - Inspired by the [Wild Cherry](https://github.com/mashaal/wild-cherry) theme. Has emoji `git` status decorations.
* [unit-1](https://github.com/nerdbude/Unit-1) - Minimalist theme with ITWTB colors.
* [vanan](https://github.com/avano/vanan-zsh-theme) - 带有“git”信息的极简主义主题，适用于黑暗终端.
* [vercel](https://github.com/vercel/zsh-theme) - Minimalist theme with `git` status decorations.
* [vertepommes](https://github.com/TheRojam/vertepommes-theme) - Based on ys. Includes vcs status, username and current directory decorations.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - 从主题/mgutz.zsh-theme 修改.与 a 一起使用时看起来很棒 [Solarized](https://github.com/altercation/solarized) color scheme.
* [vitesse](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) - Inspired by VS Code's [Vitesse](https://github.com/antfu/vscode-theme-vitesse) theme. Includes `git` status decorations.
* [vulcan](https://github.com/Bruceboy/vulcan-zsh-theme) - Minimal theme reminiscent of the default `bash` theme. Includes `git` decorations.
* [wade](https://github.com/wadehammes/wade.zsh-theme) - Mashup of the popular ZSH themes [Agnoster](https://gist.github.com/agnoster/3712874) and [Fishy](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme)，有一些视觉上的调整.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) - Based on the 0532 theme.
* [whale](https://github.com/whalesea520/whale-zsh-theme) - 鲸鱼主题的快速重新实现.
* [whales](https://github.com/lbergelson/zsh_whales_theme) - Includes decorators for `git` status, java version, last command return status, and directory.
* [wild-cherry](https://github.com/mashaal/wild-cherry) - A fairy-tale inspired theme for ZSH, iTerm 2, Sublime, Atom, & Mou.
* [wkentaro](https://github.com/wkentaro/wkentaro.zsh-theme) - A simple theme for Python users. Includes virtualenv and `git` status decorators.
* [work-line](https://github.com/afnizarnur/work-line) - Theme with nice emojis.
* [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) - Includes `git` status decorations, working directory, exit status of last command and current `virtualenv`.
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme) - A theme that aims to show you the information you need when you need it. `wynwyn` takes inspiration from the default theme `avit` and the excellent [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xavi](https://github.com/onthedock/xavi.zsh-theme) - Modified version of the [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) theme with emoji decorations for `git` status and current directory.
* [xlk-simple](https://github.com/xuelingkang/xlk-simple-zsh-theme) - Simple theme with `git` decorations.
* [xm](https://github.com/Shiaoming/xm)  - 黑暗终端的主题. 有 `git` 装饰.
* [xor](https://github.com/xor3n/xor-zsh-theme) - Self described as minimalistic and 'feature-poor', includes `git` decorations.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - An oh-my-zsh shell theme based on the Jreese theme plugin.
* [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme) - Fast, simple and streamlined theme. Works best with [tmux](https://github.com/tmux/tmux/wiki) and [vim-airline](https://github.com/vim-airline/vim-airline).
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - 显示当前 git 提交的缩短哈希和消息.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme) - Minimal theme with line separated prompts. Based on the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme.
* [yazpt](https://github.com/jakshin/yazpt) - 一个干净、快速、美观的 ZSH 提示主题，精心整合了 Git/Subversion/TFVC 状态信息，与 Oh My Zsh 等流行的插件管理器集成，并且易于定制和扩展.
* [yechen](https://github.com/liyechen/yechen.zsh-theme) - Minimalist theme with `git` status decorations.
* [yeet](https://github.com/jeetelongname/Yeet-theme) - Minimalist prompt with `git` status decorations.
* [yindev](https://github.com/menyinch/yindev-zsh-theme) - Variant of `gndx`. Includes decorations for `git` status and current directory.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - 修改自 [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) theme and optimized for a dark background.
* [ys (cristiancavalli)](https://github.com/cristiancavalli/ys-zsh-custom-theme) - Clean, simple, compatible and meaningful theme meant for dark backgrounds.
* [ys (tinyRatP)](https://github.com/tinyRatP/ys) - 变体 [ys](https://gist.github.com/ysmood/6110461).
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - `ys` variant with support for working with batch submission systems for large clusters. Supports Slurm, LSF / IBM Spectrum LSF, and PBS.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - 带有 `git` 状态信息的简单 ZSH 主题.
* [ysr](https://github.com/raykle/ysr-zsh-theme)  - 基于`ys`. 包括 `git` 状态装饰.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - 黑暗优化的 ZSH 主题.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - Includes conda and venv status.
* [yz50](https://github.com/lacanlale/yz50-zsh) - Colorful, based off of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and [crunch](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) 主题. 包括 `git` 状态装饰.
* [z4rr3t](https://github.com/inimicus/z4rr3t) - Based on sindresorhus' [pure](https://github.com/sindresorhus/pure) theme.
* [zcraft](https://github.com/cpea2506/zcraft) - Minimalist theme with decorations for `git` status, last command exit status and the time taken by the last command.
* [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme) Zelda-inspired theme. Includes `git` status decorations.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - 定制版 oh-my-zsh [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) 随着善变的支持和其他变化.
* [zemoji](https://github.com/therzka/zemoji) - 基于 [wild-cherry](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ https://github.com/mashaal/wild-cherry/tree/master/zsh). Includes exit status, `virtualenv`, `nvm`, `rvm` and `git` status decorations.
* [zero](https://github.com/arlimus/zero.zsh)  - Zero 的主题和插件. 具有浅色和深色终端背景的变体.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - 在深色背景下效果最佳，包括 `git` 状态装饰.
* [zerocake](https://github.com/ZeroPoke/ZeroCake.zsh-theme) - 在黑暗的草地上效果更好.
* [zest](https://github.com/hash-bang/zsh-theme-zest) - A functional theme for ZSH. Influenced by [zsh2000](https://github.com/consolemaverick/zsh2000), [agnoster](https://gist.github.com/agnoster/3712874) and [powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) 主题.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) - Shows username, `git` status information, machine name, the current working directory and success/fail status of last command.
* [zinc](https://gitlab.com/robobenklein/zinc) - A blazing-fast, pure ZSH, mixed asynchronous powerline prompt that's easily extensible and extremely configurable.
* [zlambda](https://github.com/wdhg/zlambda) - Minimalist, includes `git` decorations without special font requirements.
* [zodiac](https://github.com/adamalsen/zsh-zodiac) - Includes an emoji for the animal corresponding to the current year.
* [zprompts](https://github.com/z-shell/zprompts) - 使用原始“zsh”主题子系统的主题（提示）.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) - 修改版 oh-my-zsh&#39;s [maran](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) theme.
* [zsh1999](https://github.com/DTan13/zsh1999) - Includes network connectivity, battery and `git` status decorations.
* [zsh2000](https://github.com/consolemaverick/zsh2000) - Powerline looking ZSH theme which includes the `rvm` prompt, `git` status and branch, current time, user, hostname, pwd, exit status, whether running as root and background job status.
* [zsh313](https://github.com/amirali313/zsh313-theme) - 带有 `git` 状态装饰的最小主题.
* [zshcomrade](https://github.com/landongn/zshcomrade) - A ZSH theme, comrade!
* [zshpower](https://github.com/snakypy/zshpower) - Optimized for python developers. Includes `git` and `pyenv` status decorations, username and host. Tries to install other plugins and fonts, so read its instructions before installing.
* [zshred](https://github.com/redxtech/zshred) - Shows current directory, `git` decorations, exit status of last command and time.
* [zwsh](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for ZSH.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) - Similar to [Agnoster](https://github.com/agnoster/agnoster-zsh-theme)，旨在根据上下文披露信息，具有电力线美学.
* [zzshell](https://github.com/thezzisu/zzshell) - Inspired by the default [Oh-My-Zsh](http://ohmyz.sh/) theme. Displays exit code and `git` status decorations. Doesn't require Powerline fonts.

## Fonts

Some of the themes listed here require Powerline-compatible fonts, here are a few:

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that includes some nice monospaced Icons.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - Another Powerline-compatible font.
* [Hack](https://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
* [Input Mono](https://store.typenetwork.com/foundry/djr/series/input?family=input-mono) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes powerline glyphs.
* [Iosevka](https://github.com/be5invis/Iosevka)  - 编码器的字体，由代码构建. 高度可定制.
* [Monoid](https://larsenwork.com/monoid/) - Monoid 可定制和优化，即使在低分辨率显示器上也能以 15 像素行高的位图清晰度进行编码.
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more.
* [Powerline patched font collection](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include powerline gylphs.
* [Terminus](http://files.ax86.net/terminus-ttf/) - 包含电力线字形的 Terminus 的 TTF 版本.

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

这些插件中的大多数都可以通过将 `antigen bundle githubuser/reponame` 添加到您的 .zshrc 文件中来安装.  Antigen 将在您下次启动 `zsh` 时自动为您处理克隆插件. 您还可以使用“antigen bundle githubuser/reponame”将该插件添加到正在运行的 ZSH 中进行测试，然后再将其添加到您的“.zshrc”中.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1.克隆新插件到`.zsh.local/modules`
2.在`.zshrc`中加载插件模块
3.打开一个新的ZSH终端窗口或标签

### [Oh-My-Zsh](http://ohmyz.sh/)

1.`cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. 将 repo 添加到您的插件列表

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. Clone the plugin into your prezto modules directory
2. 将插件添加到您的 `.zpreztorc` 文件中
3. Open a new terminal window or tab

### [Zgen](https://github.com/tarjoilija/zgen)

Zgen is not being actively maintained. Consider switching to the [Zgenom](https://github.com/jandamm/zgenom) fork, which is.

### [Zgenom](https://github.com/jandamm/zgenom)

这些插件中的大多数都可以通过将 `zgenom load githubuser/reponame` 添加到您的 .zshrc 文件中来安装，这与您正在执行其他 `zgenom load` 调用的功能相同.

当您执行 `zgenom save` 时，Zgenom 将自动为您克隆插件存储库.

### [zplug](https://github.com/zplug/zplug)

这些插件中的大多数都可以通过将 `zplug &quot;githubuser/reponame&quot;` 添加到您的 `.zshrc` 文件中来安装.

### [zpm](https://github.com/zpm-zsh/zpm)

Most of these plugins can be installed by adding `zpm load "githubuser/reponame"` to your `.zshrc` file.

## Writing New Plugins

I've documented some recommendations for writing a new plugin [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

还有更详细 [Zsh Plugin Standard](https://zdharma-continuum.github.io/Zsh-100-Commits-Club/Zsh-Plugin-Standard.html).

## Other Resources

### ZSH Tools

* [ShellSpec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, ZSH and all POSIX shells.
* [zsh-bench](https://github.com/romkatv/zsh-bench)  - 交互式 ZSH 的基准. 它测量交互式“zsh”的用户可见延迟：输入延迟、命令延迟等
* [zshdb](https://github.com/rocky/zshdb) - A ZSH debugger.
* [zshelldoc](https://github.com/zdharma-continuum/zshelldoc) - Doxygen for shell scripts. Parses ZSH and Bash scripts, outputs Asciidoc document with function lists, call trees, lists of exported variables, and more.
* [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH.

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - 精选的工具、资源和工作流程技巧列表，打造出色的开发环境
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open source sysadmin resources
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - A curated list for CLI lovers.

Find other useful awesome-* lists at the [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

- The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) 是不可或缺的.

- [Mastering ZSH](https://github.com/rothgar/mastering-zsh) is a great tutorial that builds on the basics to show you advanced ZSH usage, customizations, and practical examples.
