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

这些框架使自定义 ZSH 设置更加容易.

You can find some interesting performance timing comparisons of various frameworks in the following locations.

* [rossmacarthur/zsh-plugin-manager-benchmark](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark)
* [pm-perf-test](https://github.com/z-shell/pm-perf-test) - Tooling for running performance tests on multiple ZSH frameworks.
### [alf](https://github.com/psyrendust/alf)

**Alf** is an out of this world super fast and configurable framework for ZSH; it's modeled after Prezto and Antigen while utilizing Oh-My-Zsh under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

 **ansible-role-zsh** 是一个零知识安装的 ansible 角色. 它使用抗原来管理捆绑包和 oh-my-zsh. 可以有条件地加载包. 默认情况下，它包括 powerlevel9k 主题、自动建议、语法高亮和 [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) and [fzf-marks](https://github.com/urbainvaes/fzf-marks). Fully customizable.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody](https://github.com/getantibody/antibody)

**Antibody** is a faster and simpler antigen written in Golang. More details at [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

 **antigen-hs** 是抗原的替代品，优化了启动外壳时的低开销. 它会自动为您克隆插件.

### [antigen](https://github.com/zsh-users/antigen)

 **Antigen** 是一小组功能，可帮助您轻松管理外壳 (ZSH) 插件，称为捆绑包. 这个概念与典型的 vim+pathogen 设置中的包几乎相同.  Antigen 之于 ZSH，Vundle 之于 vim.  Antigen 可以加载 oh-my-zsh 主题和插件，并会自动为您克隆它们.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)

**Ax-ZSH** is a modular configuration system for ZSH. It provides sane defaults and is extendable by plugins.

**Ax-ZSH** 与 [Powerlevel10k](https://github.com/romkatv/powerlevel10k) 和其他扩展，包括兼容的插件 [oh-my-zsh](https://ohmyz.sh/).

### [dotzsh](https://github.com/dotphiles/dotzsh)

**Dotzsh** strives to be platform and version independent. Some functionality may be lost when running under older versions of ZSH, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.

### [fresh](https://github.com/freshshell/fresh)

 **fresh** 是一个工具，可以将其他人的 shell 配置（别名、函数等）导入到您自己的配置文件中. 我们还支持 ackrc 和 gitconfig 等文件. 将其视为您的点文件的 Bundler.

### [miniplug](https://sr.ht/~yerinalexey/miniplug)

**miniplug** 是 ZSH 的简约插件管理器.

* No crashes or double plugin loading when re-sourcing .zshrc
* Unlike other frameworks, Miniplug does not pollute your $PATH
* Only does the bare minimum for managing plugins

### [mzpm](https://github.com/Insert-Creative-Name-Here/mzpm)

**mzpm** 是 ZSH 的极简插件管理器。

Features:

- Fetching and loading plugins from GitHub
- 加载本地插件
- Loading themes

### [oh-my-zsh](https://ohmyz.sh/)

 **oh-my-zsh** 是一个社区驱动的框架，用于管理您的 ZSH 配置. 包括 120 多个可选插件（rails、git、macOS、hub、capistrano、brew、ant、macports 等），超过 120 个主题为您的早晨增添趣味，以及一个自动更新工具，可以轻松跟上最新的来自社区的更新.

### [PMS](https://github.com/JoshuaEstes/pms)

 PMS 允许您以有助于减少设置时间并提高生产力的方式管理您的外壳. 它支持主题（改变 shell 的外观）、插件（向 shell 添加功能）和点文件管理.

 PMS 框架还允许您在不同的 shell 中使用相同的框架. 在您的个人笔记本电脑上使用 ZSH，并在远程服务器上使用 bash. 想尝尝鱼吗？ 来吧，尝试不同的贝壳.

### [prezto](https://github.com/sorin-ionescu/prezto)

**Prezto** enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes. There are some prezto-specific plugins at [https://github.com/belak/prezto-contrib](https://github.com/belak/prezto-contrib).

### [pumice](https://github.com/ryutamaki/pumice)

**Pumice** is a lightweight plugin manager for ZSH.

### [pz](https://github.com/mattmc3/pz)

A plugin manager for ZSH doesn't have to be complicated to be powerful. PZ doesn't try to be clever when it can be smart. PZ is a full featured, fast, and easy to understand plugin manager encapsulated in a single file with about 200 lines of clean ZSH.

 PZ 足以很好地管理您的 Zsh 插件，然后让您摆脱困境. 它也经过单元测试，以确保它按预期工作！

### [sheldon](https://github.com/rossmacarthur/sheldon)

一个快速、可配置的 shell 插件管理器.

* Can manage
  * Any `git` repository.
    * 分支/标签/提交支持.
    * Extra support for GitHub repositories.
    * 对 Gists 的额外支持.
  * Arbitrary remote files, simply specify the URL.
  * 本地插件，只需指定目录路径.
* Highly configurable install methods using [handlebars](http://handlebarsjs.com/) templating.
* Super-fast parallel installation.
* Configuration file using [TOML](https://github.com/toml-lang/toml) 句法。
* Uses a lock file for much faster loading of plugins.

### [Toasty](https://github.com/5paceToast/toasty-zsh)

**Toasty** is a ZSH framework made to facilitate management, not dictate it.

### [tzpm](https://github.com/notusknot/tzpm)

The tiniest ZSH plugin manager. Still under development.

### [uz](https://github.com/maxrodrigo/uz)

A ZSH micro plugin manager.

### [yazt](https://github.com/bashelled/yazt)

Yazt is a simple zsh theme manager in maintence that is compatible with nearly everything. You can use prompts in plugins, mix 'n' match two themes, with a few modifications, you can even use it in bash.

### [zapack](https://github.com/aiya000/zsh-zapack)

zapack is a basic fast minimal ZSH plugin loader.

### [zcomet](https://github.com/agkozak/zcomet)

**zcomet** is a minimalistic ZSH plugin manager that gets you to the prompt surprisingly quickly without caching (see the benchmarks). In addition to loading and updating plugins stored in Git repositories, it supports lazy-loading plugins (further reducing startup time) as well as downloading and sourcing code snippets.

### [zebrafish](https://github.com/mattmc3/zebrafish)

**Zebrafish** is a lightweight, full-featured, blazing-fast ZSH micro-framework in just one file.

### [zeesh](https://github.com/zeekay/zeesh)

 **Zeesh** 是一个跨平台的 ZSH 框架. 它类似于，但不兼容， [oh-my-zsh](http://ohmyz.sh/). It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.

### [zgem](https://github.com/qoomon/zgem)

**Zgem** is a plugin manager for ZSH that supports loading and updating plugins and themes from git, http and local files.

### [zgen](https://github.com/tarjoilija/zgen)

**Zgen** is a lightweight plugin manager for ZSH inspired by Antigen. The goal is to have minimal overhead when starting up the shell because nobody likes waiting. It is currently not being actively maintained and I recommend you use the [zgenom](https://github.com/jandamm/zgenom) fork instead, which is.

### [zgenom](https://github.com/jandamm/zgenom)

ZSH 的轻量级插件管理器，它是一个扩展了辉煌的分支 [zgen](https://github.com/tarjoilija/zgen) and provides more features and bugfixes while being fully backwards compatible.

To keep loading fast during new terminal sessions, `zgenom` generates a static `init.zsh` file which does nothing but source your plugins and append them to your `fpath`.

这通过在启动期间不必执行耗时的逻辑（插件检查、更新等）来最小化启动时间. 不利的一面是，每当您更新 `.zshrc` 中的插件列表时，都必须使用 `zgenom reset` 手动刷新 init 脚本.

Zgenom can load [oh-my-zsh](http://ohmyz.sh/)-兼容和 [prezto](https://github.com/sorin-ionescu/prezto)- 兼容的插件和主题，当您将它们添加到插件列表时，它们会自动为您“git clone”插件.

### [ZI](https://github.com/z-shell/zi)

**ZI** is a Swiss Army Knife for Zsh Unix shell. Formerly known as zplugin, zinit. ZI - [Wiki Pages](https://z-shell.pages.dev/).

Bonus: you can use [zi-console](https://github.com/z-shell/zi-console) to view and change the state of the ZSH session (e.g.: list and unload plugins) and to delete the plugins and snippets from the disk.

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
- Reports (from the plugin loads – plugins are no longer black boxes)
- Plugin unloading (allows e.g.: dynamic theme switching)
- `bindkey` capturing and remapping
- 包
- Clean `fpath` (the array `$fpath` is not being used to add completions and autoload functions, hence it stays concise, not bloated)
- Services ↔ a single-instance, background plugins
- Also, in general: all the mechanisms from the ZSH Plugin Standard – Zinit is a reference implementation of the standard.

该项目非常活跃——目前 &gt; 3100 次提交.

### [zit](https://github.com/thiagokokada/zit)

**zit** is a plugin manager for ZSH. It is minimal because it implements the bare minimum to be qualified as a plugin manager: it allows the user to install plugins from Git repositories (and Git repositories only, them why the name), source plugins and update them. It does not implement fancy functions like cleanup of removed plugins, automatic compilation of installed plugins, alias for oh-my-zsh/prezto/other ZSH frameworks, building binaries, PATH manipulation and others.

### [znap](https://github.com/marlonrichert/zsh-snap)

**:zap:Znap** is a light-weight plugin manager & Git repo manager for ZSH that's easy to grok. While tailored for ZSH plugins specifically, Znap also functions as a general-pupose utility for managing Git repos.

Znap

Znap can:

 - 使任何提示立即出现. 只需一个命令即可将启动时间从 ~200ms 减少到 ~40ms.
- Asynchronously compile your plugins and functions.
- Cache those expensive `eval $(commands)`.
- Clone or pull multiple repos in parallel.
- 无需重新输入即可重新克隆所有存储库.
- Multi-repo management
- Automatic `compinit` and `bashinit` - you no longer need them in your `.zshrc`, znap will do them automatically as needed.

### [zoppo](https://github.com/zoppo/zoppo)

 **Zoppo** 是 ZSH 的残缺配置框架. 正如一句意大利谚语所说：“chi va con lo zoppo, impara a zoppicare”，我们意识到我们是带着跛子走路的，现在自己也会变成跛子.

### [zpacker](https://github.com/happyslowly/zpacker)

**Zpacker** 是一个轻量级的 ZSH 插件和主题管理框架.

### [zpico](https://github.com/thornjad/zpico)

<i>The minuscule ZSH package manager.</i><b>小巧的 ZSH 包管理器。</b> <i>No frills, no bloat, just 2 kB of 100% ZSH code, providing complete package management for your ZSH environment.</i><b>没有多余的装饰，没有臃肿，只有 2 kB 的 100% ZSH 代码，为您的 ZSH 环境提供完整的包管理。</b>

### [zplug](https://github.com/zplug/zplug)

**:hibiscus: Zplug** 是下一代 ZSH 插件管理器.

- Can manage everything
  - Zsh plugins/UNIX commands on [GitHub](https://github.com) and [Bitbucket](https://bitbucket.org)
  - 要点文件（[gist.github.com](https://gist.github.com/discover))
  - Externally managed plugins e.g., [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) and [prezto](https://github.com/sorin-ionescu/prezto) plugins/themes
  - Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
  - 本地插件
  - etc. (you can add your [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- Super-fast parallel installation/update
- Support for lazy-loading
- Branch/tag/commit support
- Post-update, post-load hooks
- Dependencies between packages
- Unlike [antigen](https://github.com/zsh-users/antigen), no ZSH plugin file (`*.plugin.zsh`) required
- Interactive interface ([fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw), and so on)
- Cache mechanism for reducing [the startup time](https://github.com/zplug/zplug#vs)

### [zpm](https://github.com/zpm-zsh/zpm)

**zpm** ( ZSH Plugin Manager ) is a plugin manager for [ZSH](http://www.zsh.org/) who combines the imperative and declarative approach. At first run, zpm will do complex logic and generate cache, after that will be used cache only, so it makes this framework to be very fast.

* 最快的插件管理器（真的，第一次运行后，zpm 根本不会用）
* 支持异步加载
* 包之间的依赖关系
* zpm runs on Linux, macOS, FreeBSD and Android.
* zpm plugins are compatible with [oh-my-zsh](http://ohmyz.sh/).

### [zr](https://github.com/jedahan/zr)

**zr** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zshing](https://github.com/zakariaGatter/zshing)

**zshing** is a ZSH plugin manager similar to Vundle/Vim and allows you to...

* keep track of and configure your plugins right in the `.zshrc`
* Install ZSH plugins
* 更新 ZSH 插件
* Search by name all available ZSH Plugins
* 清理未使用的插件
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

* Easily manage your shell environment without editing files.
* Create aliases, functions and environment variables, and have them available to you at the next shell startup.
* 使用简单的命令从 `$path`、`$fpath` 和 `$cdpath` 添加和删除目录.
* Install packages, plugins and themes easily, and have them available to you immediately.

## Setups

This section is for full setup dropins - they aren't frameworks, but they're not simple plugins/themes either.

### zgenom

* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - A simple quickstart for using ZSH with [zgenom](https://github.com/jandamm/zgenom). This automatically configures ZSH to use [zgenom](https://github.com/jandamm/zgenom) 加载精选的插件集合并定期自动更新自身、插件和快速入门工具包本身.

### zinit

* [ZPWR](https://github.com/MenkeTechnologies/zpwr) - An extremely powerful custom terminal environment built on top of [Zinit](https://github.com/zdharma-continuum/zinit) for maximum speed.  A full terminal configuration framework including `zsh`, `tmux`, `fzf`, `vim` and spacemacs configurations.  It includes:

- 11.5k+ tab completions
- 1.9k+ aliases
- 330+ git aliases
- 350+ zpwr subcommands
- 2.1k functions
- 150+ zpwr 环境变量
- 170+ perl, python, bash, zsh scripts
- 2.8k line README.md
- 46k+ LOC
- 1 line install

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - 使用组合的教程 [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io), and [Tmuxinator](https://github.com/tmuxinator/tmuxinator) to make for an extremely productive developer workflow.
* [Arch Linux's ZSH introduction](https://wiki.archlinux.org/index.php/zsh) -  Not actually Arch or Linux-specific.
* [GH](https://github.com/gustavohellwig/gh-zsh) - Setup ZSH on debian/Ubuntu-based linuxes. Installs [Powerlevel10k](https://github.com/romkatv/powerlevel10k), [zsh-completions](https://github.com/zsh-users/zsh-completions), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting/)， 和更多.
* [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - 关于如何安装和配置 ZSH shell 的初学者友好教程.
* [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
* [rs-example](https://github.com/al-jshen/zshplug-rs-example) - An example plugin showing how a Rust program can listen to and process commands from ZSH.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
* [xVanjaZ](https://github.com/xVanjaZ/xVanjaZ-ZSH-Theme) - 为 oh-my-zsh 初学者编写了一个快速设置文档，展示了如何使用 [spaceship](https://github.com/denysdovhan/spaceship-prompt.git) prompt, syntax highlighting at the prompt, autosuggestion and a custom iTerm 2 theme.
* [ZSH for Humans](https://github.com/romkatv/zsh4humans)  - ZSH 的交钥匙配置，旨在开箱即用. 它将一组精选的 ZSH 插件组合成一个连贯的整体，感觉就像一个成品，而不是一个 DIY 入门套件.
* [ZSH Pony](https://github.com/mika/zsh-pony) - 涵盖在没有框架的情况下自定义 ZSH.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.
- [ZSH Unplugged](https://github.com/mattmc3/zsh_unplugged) - 如果您想消除使用框架但仍然可以轻松使用插件，这是一个很好的资源.

### Antigen

* [belak/zsh-utils](https://github.com/belak/zsh-utils) - A minimal set of ZSH plugins designed to be low-friction and low-complexity.
* [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis' introduction to Antigen.

### Oh-My-Zsh

* [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - A beginners guide to oh-my-zsh by Dien Bui
* [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - Karl Hadwen 在 macOS 上使用 Oh My Zsh 的初学者指南
* [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders installation guide for Ubuntu
* [ZSH Gem 24](https://www.refining-linux.org/archives/59-ZSH-Gem-24-ZSH-frameworks.html)  - 2011 年 ZSH 降临日历的一部分. 涵盖 oh-my-zsh 和 zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, [Tmux](https://tmux.github.io) & Tmuxinator.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) - 功能丰富、速度极快的外壳设置，由 [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto), and [Zgen](https://github.com/tarjoilija/zgen).

### Zinit (né zplugin)

* [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh)  - :crystal_ball: 真棒，可定制的 Zsh 入门工具包 :stars::stars:. 在某些终端中包括电力线、`fzf` 集成、天气和图像查看.
* [zinit-configs](https://github.com/zdharma-continuum/zinit-configs) - 真实世界的配置文件（基本上是 `.zshrc` 文件的集合）保存 [zinit](https://github.com/zdharma-continuum/zinit) invocations.

### ZSH on Windows

* [superconsole](https://github.com/alexchmykhalo/superconsole) - 仅限 Windows.

  * ConEmu/zsh out-of-the-box configured to restore previously opened tabs and shell working directories after ConEmu restart
  * 在启动新的 SuperConsole 会话时选择干净和继承的环境
  * Custom colorful scheme, colorful output for various commands
  * 包括 MSYS2，`zsh` 和必要的软件预装，使用 zsh-grml-config
  * Uses Antigen for ZSH theme and config management
  * 启用了许多 ZSH 插件以激活完成、突出显示和历史记录，以实现最舒适的使用
  * Git-for-Windows repo with proper `git` and git lfs support for MSYS2 environment is configured, `git` client already installed.
  * `ssh-agent` for `git` works out-of-box, add your keys to `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` dir
  * Non-blocking ZSH prompt status updates thanks to agkozak-zsh-prompt
  * Customized for MSYS2 command-not-found handler suggests what package to install
  * Sets up `nano` as main editor, enables `nano` syntax highlighting
  * 自定义帮助脚本添加到 `ConEmu/msys64/3rdparty`

## Plugins

* [1999](https://github.com/DTan13/zsh1999) - Powerline-esque theme. Includes `git` status decorations, network and battery status.
* [256color](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen `TERM` environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
* [abbr (olets)](https://github.com/olets/zsh-abbr) - Manages auto-expanding abbreviations that expand inline when you hit space, inspired by fish shell.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - Provides functionality similar to `vim`'s abbreviation expansion.
* [accurev](https://github.com/dalefukami/accurev-zsh) - ZSH plugin for [accurev](https://www.microfocus.com/en-us/products/accurev/overview).
* [actiona](https://github.com/matthieusb/act) - Make it easier to call [actiona](https://github.com/Jmgr/actiona) scripts from your command line. Includes tab completions.
* [alacritty](https://github.com/casonadams/alacritty-shell) - 控制 [alacritty](https://github.com/alacritty/alacritty/wiki/Color-schemes) 配色方案.
* [alehouse](https://github.com/sticklerm3/alehouse) - Contains short aliases for [brew](https://brew.sh) 命令，灵感来自 [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin).
* [alias-tips](https://github.com/djui/alias-tips) - 一个 oh-my-zsh 插件，可帮助记住您曾经定义的那些别名.
* [alias](https://github.com/xylous/alias-zsh) - 用于管理别名的工具.
* [allergen](https://github.com/stanislas/allergen) - A collection of custom ZSH plugins to use with Antigen.
* [almostontop](https://github.com/Valiev/almostontop)  - 每次在 shell 中执行新命令之前清除先前的命令输出. 灵感来自 [alwaysontop](https://github.com/swirepe/alwaysontop) plugin for `bash`.
* [alt-and-select](https://github.com/raisty/alt-and-select) - Binds the alt-c (copy), alt-v (paste), alt-x (cut) keyboard shortcut to a commands: copy-region-as-kill, yank, kill-region. Remaps the execute command to Alt-Shift-X.
* [ansible](https://github.com/sparsick/ansible-zsh) - A plugin for [Ansible](https://www.ansible.com/).
* [ansiweather](https://github.com/fcambus/ansiweather) - 终端中的天气，带有 ANSI 颜色和 Unicode 符号.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH script to aid with `git` rebasing.
* [anyframe](https://github.com/mollifier/anyframe) - A peco/percol/fzf wrapper plugin for ZSH.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - Adds aliases and functions for managing Apache2.
* [apparix](https://github.com/micans/apparix) - 带有跳转到书签、子目录选项卡完成、远程列表等的命令行目录书签.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - Adds MacBook Pro touchbar support in [iTerm 2](https://iterm2.com).
* [appup](https://github.com/Cloudstek/zsh-plugin-appup) - Adds `start`, `stop`, `up` and `down` commands when it detects a `docker-compose.yml` or `Vagrantfile` in the current directory (e.g. your application). Just run `up` and get coding!
* [arc](https://github.com/anton-rudeshko/zsh-arc) - Adds aliases for Yandex version control system.
* [arduino](https://github.com/raghur/zsh-arduino) - Adds scripts to build, upload and monitor arduino sketches from a command line. Requires [`jq`](https://stedolan.github.io/jq/).
* [artisan](https://github.com/jessarcher/zsh-artisan) - Laravel `artisan` plugin for ZSH to help you to run `artisan` from anywhere in the project tree, with tab completion!
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - A plugin for AsciiDoctor.
* [asdf-direnv](https://github.com/redxtech/zsh-asdf-direnv) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf) and [direnv](https://github.com/asdf-community/asdf-direnv).
* [asdf-prompt](https://github.com/CurryEleison/zsh-asdf-prompt) - 提供可在提示中使用的功能，显示当前工具版本的版本信息.
* [asdf](https://github.com/kiurchv/asdf.plugin.zsh) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf)，可扩展的版本管理器，支持 Ruby、Node.js、Elixir、Erlang 等.
* [assume-role](https://github.com/weizard/assume-role) - ZSH plugin to allow you to assume AWS IAM roles easily. Includes completions.
* [async](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in ZSH without requiring any external tools. Allows you to run multiple asynchronous jobs, enforce unique jobs (multiple instances of the same job will not run), flush all currently running jobs and create multiple workers (each with their own jobs).
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - 基于 [Sublime](https://github.com/valentinocossar/sublime) plugin, lets you launch a file or folder in [Atom](https://atom.io) 从 [iTerm 2](https://iterm2.com).
* [atuin](https://github.com/ellie/atuin) - Replaces your existing shell history with a SQLite database, and records additional context for your commands. Additionally, it provides optional and fully encrypted synchronisation of your history between machines, via an Atuin server.
* [aur-install](https://github.com/redxtech/zsh-aur-install) - Small plugin to install packages from the AUR.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) - 使用“colorls”自动列出目录.
* [auto-fortune-cowsay](https://github.com/babasbot/auto-fortune-cowsay-zsh) - Prints out an ASCII picture of a cow saying a random epigram on every zsh start.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
* [auto-ls (commanda-panda)](https://github.com/commanda-panda/zsh-auto-ls) - Automatically runs `ls` or `color-ls` if available on `cd`.
* [auto-ls (desyncr)](https://github.com/desyncr/auto-ls) - Automatically `ls` when cding to a new directory.
* [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) - Automatically sends out a notification when a long running task has completed.
* [auto-nvm](https://github.com/manlao/zsh-auto-nvm) - Automatically switches to the node version specified in a given directory.
* [autocomplete](https://github.com/marlonrichert/zsh-autocomplete) - 在您键入时自动列出完成，并提供直观的键绑定来选择和插入它们.
* [autodotenv](https://github.com/nocttuam/autodotenv) - Will prompt you to load variables when you `cd` into a directory containing a `.env` file.
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) - Extended version of the [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) plugin.
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a `.env` file, it will automatically be executed when you `cd` into it.
* [autojump](https://github.com/wting/autojump) - A `cd` command that learns - easily navigate directories from the command line. Install autojump-zsh for best results.
* [autopair](https://github.com/hlissner/zsh-autopair) - A ZSH plugin for auto-closing, deleting and skipping over matching delimiters. Only tested on ZSH 5.0.2 or later.
* [autoquoter](https://github.com/ianthehenry/zsh-autoquoter) - A `zle` widget ("zsh plugin") that will automatically put quotes around arguments to certain commands.
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)-like fast/unobtrusive autosuggestions for ZSH.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) - ZSH plugin to automatically switch python virtualenvs and pipenvs when traversing directories. Automatically detects pipenv and poetry projects.
* [autoupdate-antibody](https://github.com/spikespaz/autoupdate-antibody-zsh) - A fork of [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) for the [Antibody](https://getantibody.github.io) plugin manager, with the added ability to cooperate with static loading.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin)  - Antigen 不会像 oh-my-zsh 那样进行自动更新. 该插件为抗原添加了自动更新，包括抗原和配置中加载的包.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - oh-my-zsh doesn't automatically update non-core plugins, this adds plugin autoupdating to oh-my-zsh.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - AWS CLI MFA plugin based on sweharris' [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa). Supports specifying mfa_device in profile.
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - AWS MFA 插件.
* [aws-plugin](https://github.com/pookey/zsh-aws-plugin) - Adds helper functions for `aws` command. Includes mfa and assume-role helpers.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - Boost your productivity with `aws-upload`.
* [aws-vault](https://github.com/blimmer/zsh-aws-vault) - Plugin for [aws-vault](https://github.com/99designs/aws-vault) . 包括制表符补全.
* [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) - Provides completion support for version 2 of the [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) and a few utilities to manage AWS profiles and display them in the prompt.
* [aws](https://github.com/apachler/zsh-aws) - 从原始的 oh-my-zsh 分叉 [aws](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aws). Includes completions for `awscli` and a few utilities for managing AWS profiles and displaying them in your prompt.
* [awsume](https://github.com/Sordie/AWSume) - Plugin that enables showing the current [awsume](https://github.com/trek10inc/awsume) profile.
* [azcli](https://github.com/dmakeienko/azcli) - Helper for using the azure cli tools.
* [azure-keyvault](https://github.com/milespossing/Azure-Keyvault-Zsh) - Makes using azure keyvaults less verbose from the cli.
* [azure-subscription](https://github.com/dmakeienko/azure-subscription-prompt) - Displays information about the Azure current Subscription and tenant.
* [background](https://github.com/zpm-zsh/background) - 在后台执行功能的 ZSH 插件.
* [base16](https://github.com/chriskempson/base16-shell) - Adds script to allow you to change your shell's default ANSI colors but most importantly, colors 17 to 21 of your shell's 256 colorspace (if supported by your terminal). This script makes it possible to honor the original bright colors of your shell (e.g. bright green is still green and so on) while providing additional base16 colors to applications such as [Vim](https://www.vim.org).
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts)  - 在你的外壳中打印随机棒球相关的“有趣的事实”. 取决于安装的 `fortune` 和 `cowsay`.
* [basex](https://github.com/dirkk/zsh-basex) - Adds several [BaseX](http://basex.org/) aliases for simplified usage.
* [bash-quote](https://github.com/jtprog/bash-quote) - Get random quote from Bash.im.
* [bash](https://github.com/chrissicool/zsh-bash) - Makes ZSH more Bash compatible. It redefines the source command to act more like `bash` does. It also enables `bash` completions.
* [battery_state](https://github.com/Jactry/zsh_battery_state) - Show battery state in right-prompt.
* [bd](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`.
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) - Remap ZSH `vi`-mode for French [bépo keyboard](http://bepo.fr/wiki/Accueil).
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) - Add more command aliases for `brew`
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - Adds helper scripts to allow you to create bitbucket PRs or open a directory in the current branch.
* [bitwarden](https://github.com/Game4Move78/zsh-bitwarden) - Adds functions to manage [bitwarden](https://bitwarden.com/) sessions.
* [blackbox](https://github.com/StackExchange/blackbox) - [Stack Exchange](https://stackexchange.com)'s toolkit for storing keys/credentials securely in a `git` repository.
* [bofh](https://github.com/fundor333/bofh) - Adds functions to display random bofh fortunes.
* [bol](https://github.com/ikhurramraza/bol) - Prints a random quote when you open a terminal window.
* [boss-docker](https://github.com/bossjones/boss-docker-zsh-plugin) - Manages `docker` on OSX.
* [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) - Adds some convenience aliases for `git`.
* [branch-manager](https://github.com/elstgav/branch-manager) - 用于管理 `git` 分支的插件.
* [brew (rhuang2014)](https://github.com/rhuang2014/brew) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
* [brew (wolffaxn)](https://github.com/wolffaxn/brew-zsh-plugin) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - A plugin that lets you open any commit in your browser from the command line.
* [bruse](https://github.com/aubreypwd/zsh-plugin-bruse) - Makes it easy to `brew link` different versions of packages.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - A plugin to toggle optirun in the command line.
* [c](https://github.com/sebastiangraz/c) - Adds some `git` shortcuts.
* [calc](https://github.com/arzzen/calc.plugin.zsh) - A calculator for ZSH.
* [calibre-zaw-source](https://github.com/junkblocker/calibre-zaw-source) - [Calibre - E-book management](https://calibre-ebook.com/) source for [zaw](https://github.com/zsh-users/zaw)
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - Add [Can I Use...](https://caniuse.com) support to ZSH.
* [careful_rm](https://github.com/MikeDacre/careful_rm) - `rm` 的包装器，添加了垃圾/回收和有用的警告.
* [case](https://github.com/rtuin/zsh-case) - A ZSH plugin that adds two aliases `tolower` and `toupper` to switch output case.
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - A ZSH plugin to `cd` to the `git` repository root directory.
* [cd-ls](https://github.com/zshzoo/cd-ls) - Automatically `ls` after `cd`.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) - Display reminders when `cd`-ing into specified directories.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - A ZSH plugin to `cd` to the current repository checkout's root directory.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - `ssh` to a server when you accidentally `cd` to it.
* [cdbk](https://github.com/MikeDacre/cdbk) - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want.
* [cdc](https://github.com/evanthegrayt/cdc) - Makes it easier to change directories to directories that are subdirs of a user-defined list of directories. Includes tab-completion, session history and `pushd`, `popd` and `dirs` equivalents.
* [cdr](https://github.com/willghatch/zsh-cdr) - 为 ZSH 轻松设置 cdr.
* [change-case](https://github.com/mtxr/zsh-change-case) - Plugin for fast swap between upper and lower case in your command line. :sunglasses:
* [cheatsheet](https://github.com/0b10/cheatsheet) - Plugin to easily view, create, and edit cheatsheets.
* [check-deps](https://github.com/zpm-zsh/check-deps) - Helper for ZSH plugins that allows them to show how to install any missing dependencies. Works on Debian (and derivatives like Ubuntu), Arch and its derivatives, Nodejs and ZSH plugins if you are using the [zpm](https://github.com/zpm-zsh/zpm) framework.
* [chgo](https://github.com/sbfaulkner/chgo-plugin-zsh) - Clone of chruby modified to make it easy to switch between multiple Go versions.
* [clean-project](https://github.com/wwilsman/zsh-clean-project) - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories.
* [clipboard](https://github.com/zpm-zsh/clipboard) - Adds a cross-platform helper function to access the system clipboard. Works on macOS, X11 (and Wayland) and Cygwin.
* [cmd-status](https://github.com/BlaineEXE/zsh-cmd-status) - Reports the status of commands including return code and duration.
* [cmdtime](https://github.com/tom-auger/cmdtime) - Displays the duration of a command to the terminal forked from the [timer](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) plugin.
* [code-review](https://github.com/xorkevin/code-review-zsh) - 在 `git merge-base target_branch base_branch` 和 `target_branch` 上启动 `git difftool`.
* [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - Counts keypresses and logs stats to [Code::Stats](https://codestats.net/).
* [codex](https://github.com/tom-doerr/zsh_codex) - 使您能够在命令行中使用 OpenAI 强大的 Codex AI.
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - Forked from [ohmyzsh/ohmyzsh/plugins/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh). Colorizes `man` output.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - 为“man”页面着色.
* [colorize](https://github.com/zpm-zsh/colorize) - 为各种程序的输出着色.
* [colorls](https://github.com/Kallahan23/zsh-colorls) - Defines a few helpful shortcuts to some colorls functions.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - ZSH 的增强颜色.
* [command-execution-timer](https://github.com/olets/command-execution-timer) - Displays the time an interactive shell command takes to execute.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) - A mirror of the oh-my-zsh command-not-found plugin so you don't have to include all of oh-my-zsh.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - Record complex commands and comment on them.
* [command-time](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in ZSH and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Similar to `REPORTTIME` builtin, but only outputs when user + system time >= `REPORTTIME`.
* [compe](https://github.com/tamago324/compe-zsh) - Add completion for [nvim-compe](https://github.com/hrsh7th/nvim-compe).
* [completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script.
* [completion-zstyles](https://github.com/zshzoo/completion-zstyles) - 基于 Prezto 的 ZSH 补全的 Zstyle 设置.
* [conda](https://github.com/ThemysciraData/conda.plugin.zsh) - Adds function to provide a prompt segment for `conda` and aliases for some base functions.
* [copier](https://github.com/zshzoo/copier) - 来自 oh-my-zsh 的独立剪贴板实用程序.
* [copy-pasta](https://github.com/ChrisPenner/copy-pasta) - Copy and paste files in your terminal like you would in a GUI.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - A ZSH plugin to copy your shell configuration to another machine over `ssh`.
* [crash](https://github.com/molovo/crash) - Adds proper error handling, exceptions and try/catch for ZSH.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - 用于 Wordpress 的 Crayon 插件的 ZSH 语法突出显示.
* [cros-auto-notify](https://github.com/D3STY/cros-auto-notify-zsh) - Automatically sends out a notification when a long running task has completed. Works with macOS and linux (if `hterm-notify` is installed).
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - Add a [powerlevel9k](https://github.com/bhilburn/powerlevel9k) segment with the current bitcoin price.
* [crystal](https://github.com/veelenga/crystal-zsh) - A plugin for [Crystal](https://github.com/crystal-lang/crystal).
* [czhttpd](https://github.com/jsks/czhttpd) - A simple http server written in 99.9% pure ZSH.
* [declare-zsh](https://github.com/z-shell/declare-zsh) - A parser for zinit commands in `.zshrc`. It allows to perform the following actions on `.zshrc` from the command-line - enable and disable plugins add or remove snippets.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - Collection of useful and fun commands to improve workflow and quality of life.
* [deer](https://github.com/Vifon/deer) - A file navigator for ZSH heavily inspired by [ranger](https://ranger.github.io/).
* [defer](https://github.com/romkatv/zsh-defer) - Defers execution of a `zsh` command until `zsh` has nothing else to do and is waiting for user input. Its intended purpose is staged `zsh` startup. It works similarly to Turbo mode in [zinit](https://github.com/zdharma-continuum/zinit).
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools) - Simple oh-my-zsh plugin for installing the chromium depot_tools. Installing this plugin will put all of the chromium depot_tools in your path automatically.
* [dev](https://github.com/sbfaulkner/dev-plugin-zsh) - 提供 Shopify 内部开发工具的轻量级版本
* [diff-so-fancy](https://github.com/z-shell/zsh-diff-so-fancy) - Installs [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) and enables its use in ZSH.
* [diractions](https://github.com/AdrieanKhisbe/diractions) - Allow you to map a short logical/mnemonic name to directories to quickly access them, or perform actions in them.
* [dircolors-solarized (joel-porquet)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin, with options for dark or light terminal backgrounds.
* [dircolors-solarized (pinelibg)](https://github.com/pinelibg/dircolors-solarized-zsh) - Enables [Solarized Color Theme for GNU ls](https://github.com/seebi/dircolors-solarized).
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - Cycle through the directory stack.
* [directory-history](https://github.com/tymm/zsh-directory-history) - A per directory history for ZSH which implements forward/backward navigation as well as substring search in a directory sensitive manner.
* [direnv](https://github.com/ptavares/zsh-direnv) - A plugin for installing and loading [direnv](https://github.com/direnv/direnv.git) . 灵感来自 [zsh-pyenv](https://github.com/mattberther/zsh-pyenv).
* [dirrc](https://github.com/gmatheu/shell-plugins) - Executes `.dirc` when present in a directory you `cd` into.
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - Plugin for displaying dirstack info on a single line.
* [doas (anatolykopyl)](https://github.com/anatolykopyl/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
* [doas (senderman)](https://github.com/Senderman/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
* [docker-aliases](https://github.com/webyneter/docker-aliases) Docker aliases for everyday use.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) Show docker container status in your prompt.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - A collection of docker helper scripts.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) - A docker-machine plugin for ZSH.
* [docker-run](https://github.com/rawkode/zsh-docker-run) - Go back to running your commands "naturally", we'll handle the container.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
* [dotbare](https://github.com/kazhala/dotbare) - Interactive dotfile management with the help of [fzf](https://github.com/junegunn/fzf).
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - 使用 `git` 使您的点文件在多台机器上保持同步.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - 当您 `cd` 进入目录时，自动切换到位于名为 `.pyvenv` 的目录中的 Python 虚拟环境（您之前使用 virtualenv 程序创建的）.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for ZSH that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drupal](https://github.com/yhaefliger/zsh-drupal) - Adds aliases for common tasks and also tab-completion for `drush`. Inspired by [Artisan](https://github.com/jessarcher/zsh-artisan).
* [dune-quotes](https://github.com/brokendisk/dune-quotes) - Random Dune quote generator plugin.
* [duration](https://github.com/rtakasuke/zsh-duration) - 如果超过用户可设置的运行时间，则显示命令持续时间.
* [dwim](https://github.com/oknowton/zsh-dwim) - Attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
* [easy-motion](https://github.com/IngoHeimbach/zsh-easy-motion) - A port of [vim-easymotion](https://github.com/easymotion/vim-easymotion) 对于 ZSH.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - List EC2 instances and `ssh` login to the instances easily.
* [editing-workbench](https://github.com/commiyou/zsh-editing-workbench) - Adds sane, complex command line editing (e.g. incremental history word completion).
* [edward cli](https://github.com/matthieusb/zsh-edward) - Adds smart completions and alises for [edward CLI micro-service launcher](https://github.com/yext/edward).
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - 添加 Elixir、IEX、Mix、Kiex 和 Phoenix 的快捷方式.
* [emacs (cowboyd)](https://github.com/cowboyd/zsh-emacs) - Make Emacs the default for CLI operations like editing git commit messages; set up handy aliases.
* [emacs (flinner)](https://github.com/Flinner/zsh-emacs) - Uses the Emacs daemon capability, allowing the user to quickly open frames, whether they are opened in a terminal via a ssh connection, or X frames opened on the same host.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: 命令行上的表情符号补全.
* [emoji-fzf](https://github.com/pschmitt/emoji-fzf.zsh) - Configurable ZSH plugin for the excellent [emoji-fzf](https://github.com/noahp/emoji-fzf) . 它深受启发 [emoji-cli](https://github.com/b4b4r07/emoji-cli).
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) - Adds numerous ascii art emojis to your environment in convenient variables.
* [enhancd](https://github.com/b4b4r07/enhancd) - A simple tool that provides an enhanced `cd` command by memorizing all directories visited by a user and use it for the pathname resolution.
* [envrc](https://github.com/fabiogibson/envrc-zsh-plugin) - Automatically loads and unloads environment variables if a `.envrc` file is found in a directory.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - Quickly insert escaped backticks when double-tapping "`".
* [evalcache](https://github.com/mroth/evalcache) - Cache the output of a binary initialization command, to help lower shell startup time.
* [evil-registers](https://github.com/zsh-vi-more/evil-registers) - 扩展 ZLE vi 命令以远程访问 vim 和 nvim 编辑器的命名寄存器，以及系统选择和剪贴板.
* [exa (DarrinTisdale)](https://github.com/DarrinTisdale/zsh-aliases-exa) - Enables a number of aliases extending [exa](https://the.exa.website), the modern replacement for `ls`.
* [exa (hermitmaster)](https://github.com/hermitmaster/zsh-exa-plugin) - Adds some aliases for [exa](https://the.exa.website), the modern replacement for `ls`.
* [exa (mohamedelashri)](https://github.com/MohamedElashri/exa-zsh) - Adds aliases for [exa](https://the.exa.website), a modern replacement for `ls`.
* [exa (ptavares)](https://github.com/ptavares/zsh-exa) - 安装和加载 [exa](https://github.com/ogham/exa.git).
* [exa (ritchies)](https://github.com/RitchieS/zsh-exa/) - Adds aliases to make using [exa](https://github.com/ogham/exa.git) easier.
* [exa-ls](https://github.com/birdhackor/zsh-exa-ls-plugin) - Adds aliases so that you can use [exa](https://the.exa.website) as a drop-in replacement for `ls` and `tree`.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/).
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - Expand specific aliases with space.
* [expand](https://github.com/MenkeTechnologies/zsh-expand) - Expands regular aliases, global aliases, incorrect spellings and phrases, globs, history expansion and $parameters with the spacebar key.
* [expander](https://github.com/ianthehenry/zsh-expander) - A `zle` widget that allows you to write custom expanders and select them with [fzf](https://github.com/junegunn/fzf).
* [explain-shell](https://github.com/gmatheu/shell-plugins) - Opens commands on [explainshell.com](https://explainshell.com).
* [extend-history](https://github.com/xav-b/zsh-extend-history) - 通过为历史记录中的每个命令添加退出代码来扩展命令历史记录.
* [f-shortcuts](https://github.com/zpm-zsh/f-shortcuts) - Makes a shortcuts toolbar using F1 to F12 keys.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of oh-my-zsh.
* [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips) - Helps remember the aliases you defined and forgot about. Ported from [djui/alias-tips](https://github.com/djui/alias-tips).
* [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting) - Optimized and improved `zsh-users/zsh-syntax-highlighting` – better response times, switchable highlight themes.
* [fav](https://github.com/ddnexus/fav) - ZSH/[fzf](https://github.com/junegunn/fzf) plugin that makes it really easy to add and recall named favorites of your important directories.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - Fast jumps to your favorite directories.
* [figures](https://github.com/zpm-zsh/figures) - Unicode symbols for ZSH.
* [firebase (Seqi)](https://github.com/Seqi/firebase-zsh) - Display the current working project or project alias when in a Firebase project directory or subdirectory.
* [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) - Add an indicator in the prompt that you're in a directory with a `firebase.json` file (aka "firebase project").
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - Enables numpad keys of Apple keyboards to be recognized in ZSH.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - This plugin makes the `flow` command available inside every subdirectory of the TYPO3 Flow distribution.
* [fnm](https://github.com/dominik-schwabe/zsh-fnm) - Installs and loads the [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) 如果它丢失了。
* [forgit](https://github.com/wfxr/forgit) - Utility tool for `git` which takes advantage of fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [functional](https://github.com/Tarrasch/zsh-functional) - ZSH higher order functions.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line.
* [fuzzy-wd](https://github.com/spodin/zsh-fuzzy-wd) - 添加模糊搜索扭曲的目录 [WD](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/wd) plugin.
* [fz](https://github.com/changyuheng/fz) - Seamlessly adds fuzzy search to [z](https://github.com/rupa/z)'s tab completion and lets you easily jump around among directories in your history.
* [fzf (unixorn)](https://github.com/unixorn/fzf-zsh-plugin/tree/master) - Enables [fzf](https://github.com/junegunn/fzf) 历史和文件搜索.
* [fzf-fasd](https://github.com/wookayin/fzf-fasd) - Integrates [fzf](https://github.com/junegunn/fzf) and [fasd](https://github.com/clvv/fasd) --- tab completion of `z` with fzf's fuzzy search!
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - Plugin to have a cool search keybinding with [fzf](https://github.com/junegunn/fzf) and (optionally) [bat](https://github.com/sharkdp/bat). Searches in the local tree of subdirectories for files.
* [fzf-history-search](https://github.com/joshskidmore/zsh-fzf-history-search) - 将 `Ctrl+R` 替换为 [fzf](https://github.com/junegunn/fzf)- 驱动的历史搜索，包括日期/时间.
* [fzf-it](https://github.com/micakce/fzf-it) - Make any command interactive wrapping it with FZF functionality.
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) - Little script to create, navigate and delete bookmarks in `bash` and `zsh`, using the fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [fzf-pass](https://github.com/smeagol74/zsh-fzf-pass) - Better handling of passwords using [fzf](https://github.com/junegunn/fzf) and [pass](https://www.passwordstore.org/).
* [fzf-prezto](https://github.com/lildude/fzf-prezto) - Prezto plugin that finds where [fzf](https://github.com/junegunn/fzf) has been installed and enables its auto-completion and key-bindings. This plugin works as a Prezto `zstyle` configuration option.
* [fzf-tab](https://github.com/Aloxaf/fzf-tab) - 将 ZSH 的默认补全选择菜单替换为 [fzf](https://github.com/junegunn/fzf).
* [fzf-utils](https://github.com/redxtech/zsh-fzf-utils) - 提供杀死进程并在路径中查找的功能 [fzf](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - 添加一些 ZLE 小部件 [fzf](https://github.com/junegunn/fzf).
* [fzf-z](https://github.com/andrewferrier/fzf-z) - Brings together the *z* plugin and *fzf* to allow you to easily browse recently used directories at any point on the command line.
* [fzy](https://github.com/aperezdc/zsh-fzy) - 使用的插件 [fzy](https://github.com/jhawthorn/fzy) for certain fuzzy matching operations.
* [gcloud-project](https://github.com/avivl/gcloud-project) - Easy selection of Google Cloud Projects.
* [gdbm](https://github.com/zdharma-continuum/zgdbm) - Adds GDBM as a plugin.
* [geeknote](https://github.com/s7anley/zsh-geeknote) - [Geeknote](https://geeknote.me) ZSH 插件.
* [gentoo](https://github.com/MattiaG-afk/gentoo-ohmyzsh) - Adds some aliases and functions to work with Gentoo Linux.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) datetime plugin. Shows datetime (`date` unix command) in your prompt.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to remind you to hydrate.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's npm package version.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's Rust version when either a `.rs` or `Cargo.toml` is present.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - Plugin for fast downloading jQuery library from [https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com](https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com).
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - 让您使用 [zeus](https://github.com/burke/zeus) with normal rails commands.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - Manage Go installations with gimme.
* [git-acp](https://github.com/MenkeTechnologies/zsh-git-acp) - Take the current command line as the commit message and then run git pull, add, commit and push with one keystroke.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) - Easily add the upstream remote to your `git` fork.
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of oh-my-zsh.
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used `git` commands.
* [git-branches](https://github.com/Schroefdop/git-branches) - Makes a menu of `git` branches you can switch to without having to type long branch names.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - 增强 `git` 完成以包括在远程完成中（例如来自 `git clone`）剪贴板中的任何 URL.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Extra `git` helper scripts packaged as a plugin.
* [git-flow-avh](https://github.com/nekofar/zsh-git-flow-avh) - 为 `git-flow` 命令添加短别名.
* [git-fuzzy](https://github.com/bigH/git-fuzzy) - A CLI interface to `git` that relies heavily on [`fzf`](https://github.com/junegunn/fzf).
* [git-ignore](https://github.com/laggardkernel/git-ignore) - Generates `.gitignore` files from gitignore.io **offline**. [fzf](https://github.com/junegunn/fzf), completion, preview integrated.
* [git-is-clean](https://github.com/aubreypwd/zsh-plugin-git-is-clean) - This function will return true or false depending on if it finds out your repo is dirty or not.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub.
* [git-lfs](https://github.com/nekofar/zsh-git-lfs) - Adds short aliases for the git-lfs commands.
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - 为 `git` 添加了一些功能.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for `git` user.email.
* [git-prune (diazod)](https://github.com/diazod/git-prune) - Allows you to delete all branches that are already merged in your local repository and/or that were merged in your remote origin repository.
* [git-prune (seinh)](https://github.com/Seinh/git-prune) - Plugin that simplifies deleting merged branches.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) - Adds `git-squash-branch` and `git-remove-merged` commands.
* [git-secret](https://github.com/sobolevn/git-secret) - 一个 bash 工具，用于将您的私人数据存储在 `git` 存储库中。
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - Adds extra `git` commands to make some common `git` usages more efficient.
* [git-smart-commends-wrapper](https://github.com/jelek21/omz-git-smart-commands) - Wraps [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) to make it compatible with the oh-my-zsh plugins system.
* [git-sync](https://github.com/caarlos0/zsh-git-sync) - A ZSH plugin to sync `git` repositories and clean them up.
* [git-tree](https://github.com/dehlen/git-tree-zsh) - [fzf](https://github.com/junegunn/fzf) 供电的 `git worktree` 助手.
* [git-worktree](https://github.com/alexiszamanidis/zsh-git-worktree)  - 包装一些 `git worktree` 操作以简化和提高生产力. 包括“fzf”工具.
* [git](https://github.com/davidde/git) - Replacement for the stock oh-my-zsh git plugin. Provides quite a few useful aliases and functions. The motivation to replace the default plugin stems from the fact that it comes with some inconsistencies that make a few popular commands rather unintuitive, so this plugin makes the aliases consistent.
* [gitcd (SukkaW)](https://github.com/SukkaW/zsh-gitcd) - 将命令添加到 `git clone` 存储库和 `cd` 到结果目录.
* [gitcd (viko16)](https://github.com/viko16/gitcd.plugin.zsh) - Automatically `cd` to a `git` working directory after cloning it.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of oh-my-zsh gitfast plugin.
* [gitgo (grimmbraten)](https://github.com/grimmbraten/gitgo) - Make it easier to switch between `git` branches.
* [gitgo (ltj)](https://github.com/ltj/gitgo) - Open a Github/Gitlab repository in your browser from the command line (macOS only).
* [github](https://github.com/shakir-abdo/zsh-github-plugin) - 原叉 [github plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/github) embedded in [oh-my-zsh](http://ohmyz.sh/).
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - Plugin for creating `.gitignore` files.
* [gitio](https://github.com/denysdovhan/gitio-zsh) - 用于生成 GitHub 短 URL 的 ZSH 插件 [git.io](https://git.io).
* [gitstatus](https://github.com/Insert-Creative-Name-Here/gitstatus.zsh) -  Makes it easy to show your `git` status in your prompt.
* [gitsync](https://github.com/washtubs/gitsync) - ZSH plugin to improve workflows for one person developing on the same repository on multiple machines.
* [goenv (CDA0)](https://github.com/CDA0/zsh-goenv/blob/master/zsh-goenv.plugin.zsh) - Plugin for installing, updating and loading goenv.
* [goenv (bbenne10)](https://github.com/bbenne10/goenv) - Manage `$GOPATH` similarly to Python's virtualenvwrapper.
* [going_places](https://github.com/or17191/going_places) - A plugin that helps to use, create and maintain a list of shell locations.
* [golinks](https://github.com/slessans/oh-my-zsh-golinks-plugin) - Launch golinks from your terminal.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - 在设置 GPG 代理以在 macOS 上也充当 SSH 代理时尝试做正确事情的插件.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) - ZSH plugin to encrypt and decrypt files or directories in place.
* [grep2awk](https://github.com/joepvd/grep2awk) - ZLE widget to transform `grep` command into `awk` command.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for `grunt`.
* [gsh](https://github.com/cjayross/gsh) - Collection of helper functions for `git`
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - terminal plugin for [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [gtr](https://github.com/Zocker1999NET/zsh-gtr) - Allows fast tagging of a release in git using the tag name **release-YYYY-MM-DD-HH-MM** and headline **Release YYYY-MM-DD HH:MM**.
* [guish](https://github.com/gcarrarom/oh-my-guish) - Collection of utility functions and aliases.
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - Wrapper plugin for [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
* [gunstage](https://github.com/LucasLarson/gunstage) - There are at least eight ways to unstage files in a `git` repository. This is a command-line shell plugin for undoing `git add`.
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - A gvm (Go version manager) plugin for ZSH.
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - Provides autocompletion for `gvm` (Groovy enVironment Manager).
* [hab](https://github.com/alexdesousa/hab) - Automatically loads OS environment variables defined in the file `.envrc` if it's found when changing to a new directory.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - 打开终端时随机输出黑客报价.
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - 为 hadoop 函数添加一些方便的别名.
* [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH plugin for [hanami](http://hanamirb.org) projects.
* [hangul](https://github.com/gomjellie/zsh-hangul)  - 自动将韩文（韩文，韩文）更正为英文，而应该输入英文. 你必须输入英文，但如果你输入韩文，它会自动更正.
* [hbt](https://github.com/lzambarda/hbt) - 基于过去命令使用的启发式 ZSH 建议系统.
* [hints](https://github.com/joepvd/zsh-hints) - 在您的编辑缓冲区下显示全局和参数标志以及其他不可完成的信息.
* [hipchat](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell.
* [hist](https://github.com/marlonrichert/zsh-hist) - Edit your history in ZSH, without ever leaving the command line.
* [histdb](https://github.com/larkery/zsh-histdb) - Stores your history in an SQLite database. Can be integrated with [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions).
* [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer)  - 通过更多交互和多行选择菜单增强历史搜索. 需要nodejs.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter)  - 允许您指定将自动排除命令插入永久历史记录的模式. 对于防止写入秘密特别有用.
* [history-here](https://github.com/leonjza/history-here) - Binds `^G` to quickly toggle the current shell history file location.
* [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) - Captures the PageUp key and uses `dialog` to open a popup menu with the history, so the user can interactively navigate through it and pick the history line to bring back to the prompt.
* [history-search-multi-word](https://github.com/zdharma-continuum/history-search-multi-word) - A syntax highlighted, multi-word history searcher for ZSH, bound to Ctrl-R, with advanced functions (e.g. bump of history entry to top of history).
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after `zsh-syntax-highlighting`, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md.
* [history-sync](https://github.com/wulfgarpro/history-sync) - An Oh My Zsh plugin for GPG encrypted, Internet synchronized ZSH history using `git`.
* [history](https://github.com/b4b4r07/zsh-history) - Extend history so that it can be queried by SQL.
* [hitokoto](https://github.com/derry96/hitokoto) - Displays a random quote from [hitokoto.cn](https://hitokoto.cn/).
* [homeassistant-cli](https://github.com/frosit/zsh-plugin-homeassistant-cli) - Provides completion and (configuration) helpers for the [Home Assistant Command-line interface (hass-cli)](https://github.com/home-assistant/home-assistant-cli). and allows command line interaction with [Home Assistant](https://home-assistant.io/) instances.
* [homebrew](https://github.com/digitalraven/omz-homebrew) - Plugin for [homebrew](https://brew.sh) that supplements the one built into oh-my-zsh and can safely run with it enabled.
* [hooks](https://github.com/willghatch/zsh-hooks) - Add missing hooks - for plugins and personal use.
* [host-switch](https://github.com/LockonS/host-switch) - Make it easier to switch in different `/etc/hosts` files during development.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - 一个简单的插件，用于将 `hub` ci-status 添加到您的 ZSH 主题.
* [hub](https://github.com/soraliu/zsh-hub) - 用于分叉模型的 ZSH 插件.
* [igit](https://github.com/ytakahashi/igit) - Interactive `git` commands using [fzf](https://github.com/junegunn/fzf).
* [ing](https://github.com/rummik/zsh-ing) - 简化的“ping”输出.
* [instant-repl](https://github.com/jandamm/instant-repl.zsh) - Activate a REPL for any command in your current ZSH session.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - Fish-like interactive tab completion for `cd`.
* [iosctl](https://github.com/obayer/iosctl) - Quickly access App, Data, and Log of the running simulator.
* [ipip](https://github.com/SukkaW/zsh-ipip) - Plugin for [IPIP](https://en.ipip.net).
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - Adds function to set the tab color in iTerm2 and can automatically change color based on cwd or command being executed.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - 根据当前工作目录自动更改 iTerm 2 选项卡颜色.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - Display iTerm2 feedback in the MacbookPro TouchBar (Current directory, git branch & status).
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - Manage your iTerm 2's color scheme from the command line.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - 设置 iTerm 2 选项卡的颜色和标题.
* [iterm2-utilities](https://github.com/decayofmind/zsh-iterm2-utilities) - 帮助下载各种 iTerm2 实用程序，让您无需克隆整个 iterm2 网站存储库或依赖其他可能不同步的存储库.
* [iterm2](https://github.com/laggardkernel/zsh-iterm2) - Packs iTerm's ZSH integration scripts into a ZSH plugin to avoid polluting your $HOME directory, with a negligible time increase of only 2ms.
* [jabba](https://github.com/2m/zsh-jabba) - 添加外壳集成代码和完成 [jabba](https://github.com/shyiko/jabba) Java 版本管理器.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - Adds a `setjdk` command so you can switch easily between different versions of the jdk.
* [javaVersions](https://github.com/miguefl/javaVersions) - 使用单个命令在不同的 Java 版本之间进行更改.
* [jdk-switch](https://github.com/LockonS/jdk-switch) - A macOS-only plugin for switching between jdk versions.
* [jenkins](https://github.com/tomplex/jenkins-zsh) - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - A ZSH plugin for lazy loading of jEnv.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - Adds commands for [jHipster](https://www.jhipster.tech/).
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRA tickets from the command line.
* [jq](https://github.com/reegnz/jq-zsh-plugin) - Interactively build [jq](https://stedolan.github.io/jq/) 表达式.
* [jvm](https://github.com/mgryszko/jvm) - 允许在 macOS 上选择 JDK.
* [k3d](https://github.com/dwaynebradley/k3d-oh-my-zsh-plugin) - Adds aliases and tab completions for [k3d](https://k3d.io/).
* [k](https://github.com/supercrabtree/k) - Directory listings for ZSH with `git` status decorations.
* [kctl](https://github.com/yzdann/kctl) - Add helper aliases for `kubectl`.
* [kill-node](https://github.com/vmattos/kill-node) - ZSH plugin for murdering `node` process families.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook plugin for oh-my-zsh.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
* [kube-aliases](https://github.com/Dbz/kube-aliases) - Adds functions and aliases to make working with `kubectl` more pleasant.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - ZSH plugin for `kubectl` that adds current context and namespace.
* [kubecolor (devopstales)](https://github.com/devopstales/kubecolor-zsh) - Adds aliases for the `kubecolor` command.
* [kubecolor (droctothorpe)](https://github.com/droctothorpe/kubecolor) - Simplify and colorize the output of `kubectl get events -w`
* [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) - ZSH plugin for managing `kubectl`.
* [kubectx (ptavares)](https://github.com/ptavares/zsh-kubectx) - 安装和加载 [kubectx](https://github.com/ahmetb/kubectx).
* [kubectx (unixorn)](https://github.com/unixorn/kubectx-zshplugin) - Automatically installs [kubectx](https://github.com/ahmetb/kubectx) and `kubens`.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) - Add [kubernetes](https://kubernetes.io) helper functions and aliases.
* [lando (joshuabedford)](https://github.com/JoshuaBedford/lando-zsh) - A collection of alias functions to enable the use of the CLIs within [Lando](https://docs.lando.dev) without having to type lando to access them.
* [lando (mannuel)](https://github.com/mannuel/lando-alias-zsh) - Adds aliases for various [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) commands.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - 提供接口 [Laradock](http://laradock.io/)'s workspace.
* [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) - Adds aliases for Laravel 6.
* [laravel-sail](https://github.com/ariaieboy/laravel-sail) - Adds shortcuts for `sail` commands.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - Add shortcuts for Laravel 5, 5.1, 5.2 & 5.3.
* [laravelx](https://github.com/rsthegeek/oh-my-zsh-laravelx) - Adds some aliases for common [Laravel](https://laravel.com/docs) commands.
* [last-working-dir-tmux](https://github.com/Curly-Mo/last-working-dir-tmux) - 跟踪全局和每个 tmux 会话最后使用的工作目录，并自动跳转到新的 shell.
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) - Broken out copy of the version in [oh-my-zsh](http://ohmyz.sh/). Keeps track of the last used working directory and automatically jumps into it for new shells.
* [lazyload](https://github.com/qoomon/zsh-lazyload) - Lazy load commands and speed up start up time of ZSH.
* [learn](https://github.com/MenkeTechnologies/zsh-learn) - Learning collection in MySQL/MariadB to save, query and quiz everything you learn.
* [lesaint-git](https://github.com/lesaint/lesaint-git) - Replacement `git` plugin for Oh-My-Zsh-compatible frameworks.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - Maven plugins for oh-my-zsh.
* [liferay](https://github.com/david-gutierrez-mesa/liferay-zsh) - Adds scripts for [liferay](https://github.com/liferay/liferay-portal) 发展.
* [linkfile](https://github.com/JaumeRF/linkfile-zsh) - 为您喜爱的目录添加快捷方式.
* [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) - 打开终端时输出随机的 Linus Torvalds 咆哮.
* [listbox](https://github.com/gko/listbox) - 外壳的列表框元素.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - Allows searching for [Sublime Text](https://www.sublimetext.com) 项目并在 Sublime 中打开它们.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum) - Generate lorem ipsum text on the command line. Gets its data from [lipsum.com](https://www.lipsum.com).
* [ls](https://github.com/zpm-zsh/ls) - Colorizes the output of `ls`.
* [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack 是一个用于 shell 脚本的日志接口.
* [lux](https://github.com/pndurette/zsh-lux) - ZSH plugin to toggle the light & dark modes of macOS and other items and applications via the `lux` command. Highly customizable: included items can be configured by defining variables. Highly extensible: items can be added by defining functions. Includes `macos_is_dark` helper function to determine if the macOS dark mode is active for use in theming.
* [mac-packaging](https://github.com/Temikus/mac-packaging) - A set of common functions used for enterprise Mac packaging with [Munki](https://www.munki.org/munki/).
* [macos (joow)](https://github.com/joow/macos) - A ZSH plugin for macOS.
* [macos (zshzoo)](https://github.com/zshzoo/macos) - ZSH goodies for MacOS users.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) - Makes it easy to work with Docker and Magento 2. Speeds up and simplifies common commands like clean cache, setup upgrade, compile di and much more in Magento 2 on containers.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - Adds `m2` function to run magento binary, adds tab completions.
* [magic-enter](https://github.com/zshzoo/magic-enter) - 通过将 ZSH 命令绑定到它来使您的输入键变得神奇.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) - 用于模拟 `...&#39;==`../..&#39; 等的 zle 调整.
* [markedit](https://github.com/zakariaGatter/MarkEdit) - Mark files and edit them with autocompletion for existing marks.
* [markgate](https://github.com/zakariaGatter/MarkGate) - Allows you to mark directories so you can jump directly to them.
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - oh-my-zsh maven 插件的一个分支.
* [media-sync](https://github.com/redxtech/zsh-media-sync) - 一个便于在两个 rclone 位置之间复制媒体的插件.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) - Extracted from oh-my-zsh so you can use it without oh-my-zsh.
* [mfunc](https://github.com/hlohm/mfunc) - Allows you to define persistent functions on-the-fly, without the need to add them to your config files. These functions are permanently available until you delete them.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - 一个 ZSH 插件，用于在普通模式和 `vi` 模式之间切换命令行.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - ZSH plugin for monorepo management.
* [monthrename](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) - Renames month names to numbers in filenames.
* [mouse-status](https://github.com/gryffyn/mouse-status) - Changes mouse color based on status code, uses libratbag.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - Metasploit 处理程序插件，用于轻松启动处理程序.
* [mvn-contexts](https://github.com/artemy/zsh-mvn-contexts) - Allows fast switching between maven configurations.
* [mylocation](https://github.com/fALKENdk/mylocation) - 根据您的 IP 地址显示您当前位置的插件.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - Adds color for mysql tables.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with mysql.
* [n](https://github.com/gretzky/n.zsh) - Auto-switches node versions based on project environment using [n](https://github.com/tj/n).
* [namelink](https://github.com/jthat/zsh-namelink) - Provides an automatically synchronized mapping of filesystem entries (typically symbolic links) in a set of directories to their counterparts in the named directory hash.
* [navi](https://github.com/icatalina/zsh-navi-plugin/) - Plugin for [navi](https://github.com/denisidoro/navi).
* [navigation-tools](https://github.com/zdharma-continuum/zsh-navigation-tools) - Adds `htop`-like kill, directory bookmarks browser, a multi-word incremental history searcher and more.
* [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) -  Generates file from template.
* [newvwp](https://github.com/aubreypwd/zsh-plugin-newvwp) - 使用 Valet 启动一个新的 WordPress 网站.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - 将退出状态代码映射到人类可读的字符串.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) - 允许您在 `nix-shell` 环境中使用 ZSH 作为默认 shell 的插件.
* [nnvm](https://github.com/torifat/nnvm) - auto-switches node versions based on `.nvmrc`. Requires [n](https://github.com/tj/n).
* [node-env-installer](https://github.com/shiro-saber/node-env-installer) - 使用 `nvm` 为当前项目安装新版本和模块.
* [node-path](https://github.com/andyrichardson/zsh-node-path) - Automatically adds the "npm bin" of your current directory to your path.
* [node](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty's nodejs plugin for ZSH with caching of `nvm` completions and autoloading of `nvm` if present.
* [nodenv (c-uo)](https://github.com/C-uo/zsh-nodenv) - Looks for nodenv in your working directory and loads it when found.
* [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) - Auto-load `nodenv` and its completions into the shell.
* [nodenv (mattberther)](https://github.com/mattberther/zsh-nodenv) - Installs, updates and loads `nodenv`. Inspired by zsh-rbenv.
* [nohup](https://github.com/micrenda/zsh-nohup) - Add `nohup` to the current command pressing `Ctrl-H`.
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS 用户知道试图找出在他们的 macOS 版本上实际刷新 DNS 缓存的命令的痛苦，而这个插件让这种烦恼消失了.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - Inspired by [terminal_velocity](https://www.seanh.cc/terminal_velocity/), it provides a fast interface to create and access a set of [Markdown](https://en.wikipedia.org/wiki/Markdown) text files inside a directory.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - Provides a quick notes editing experience in ZSH.
* [notify (luismayta)](https://github.com/luismayta/zsh-notify) - Notifications for ZSH with auto installation of dependencies and r2d2 sounds.
* [notify (marzocchi)](https://github.com/marzocchi/zsh-notify) - A plugin for ZSH (on macOS and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
* [npm (igoradamenko)](https://github.com/igoradamenko/npm.plugin.zsh) - Add `npm` aliases & command completion. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
* [npm (trystan2k)](https://github.com/trystan2k/zsh-npm-plugin) - Adds `npm` aliases. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
* [npm (zfben)](https://github.com/zfben/zsh-npm) - Use `n` as `npm` aliases with `noglob` prefix and more. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
* [npms](https://github.com/torifat/npms) - Utility powered by `fzf` for using npm scripts interactively. Requires [fzf](https://github.com/junegunn/fzf) and [jq](https://stedolan.github.io/jq/).
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - Calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling `nvm` which node to use.
* [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy) - Plugin for lazy loading of oh-my-zsh's **nvm** plugin. It supports lazy-loading `nvm` for more than one binary/entrypoint, with the defaults being `nvm`, `node` and `npm`.
* [nvm](https://github.com/lukechilds/zsh-nvm) - ZSH plugin for installing, updating and loading `nvm`.
* [oath](https://github.com/alexdesousa/oath) - Manages 2FA authentication 6 digit tokens. It was highly inspired by this article about [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
* [oclif completion generator](https://github.com/MunifTanjim/oclif-plugin-completion) - Generates shell completions for commands lacking them.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - Turn your terminal into the matrix.
* [omz-themes-standalone](https://github.com/zshzoo/omz-themes-standalone) - Gives you the [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) themes without requiring everything else that comes with oh-my-zsh
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) - Open/Create projects in Jetbrains.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) - A ZSH plugin to open pull requests from command line.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - 为常见的 openshift origin (oc) 操作添加一些快捷方式.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` 别名.
* [operator](https://github.com/nivv/operator-theme) - Clean and simple theme, works best with [Menlo for Powerline](https://github.com/abertsch/Menlo-for-Powerline).
* [opp](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for ZSH.
* [opt-path](https://github.com/jreese/zsh-opt-path) - Automatically add `~/opt` subpaths to your `$PATH`.
* [osx-autoproxy](https://github.com/SukkaW/zsh-osx-autoproxy) - Configures proxy environment variables based on macOS's system preferences.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - 此插件添加了一些命令，用于在 macOS 安装上维护各种服务器程序.
* [osx](https://github.com/mwilliammyers/plugin-osx) - Add some common macOS related aliases and functions.
* [p10k-promptconfig](https://github.com/doctormemes/p10k-promptconfig) - adds the ability to easily switch between Powerlevel10k prompt theme config files by defining the `P10K_PROMPT` variable in your `.zshrc` file.
* [paci](https://github.com/iloginow/zsh-paci) - Plugin for archlinux package managers.
* [package-any-node](https://github.com/zdharma-continuum/zsh-package-any-node) - 在插件目录中轻松安装任何节点模块，通过由自动创建的垫片（即：转发器脚本）公开其二进制文件 [Bin-Gem-Node](https://github.com/zdharma-continuum/z-a-bin-gem-node) annex.
* [packer](https://github.com/BreakingPitt/zsh-packer) - Adds aliases and auto-completes for Hashicorp [packer](https://www.packer.io/).
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin)  - 长时间运行命令的后台通知. 支持 Elementary OS Freya.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) - Keeps passwords from entering your command line history.
* [path-ethic](https://github.com/sha1n/path-ethic)  - 帮助快速轻松地管理您的“$PATH”. 不会触及现有的 `.zshrc`、`.zprofile`，而是添加到现有环境之上.
* [pctl](https://github.com/ytet5uy4/pctl) - Toggle the environment variables for proxying.
* [peco-history](https://github.com/jimeh/zsh-peco-history) - Search shell history with Peco when pressing ctrl+R.
* [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) - Aliases and functions for the lazy penetration tester.
* [per-directory-history](https://github.com/jimhester/per-directory-history) - ZSH 的每个目录历史记录，以及全局历史记录，以及使用 `^G` 在它们之间切换的能力.
* [percol](https://github.com/robturtle/percol.plugin.zsh) - Interactively and incrementally search history/resume background jobs using [percol](https://github.com/mooz/percol).
* [perlbrew](https://github.com/tfiala/zsh-perlbrew/) - Installs [perlbrew](https://perlbrew.pl/) if not already installed and initializes it for your shell.
* [pew](https://github.com/shosca/zsh-pew) - Sets up and manages Python virtualenvs using [pew](https://github.com/berdario/pew), automatically switches virtualenvs as you move directories.
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) - Adds utility functions to work with [PostgreSQL](https://www.postgresql.org/).
* [ph-marks](https://github.com/lainiwa/ph-marks) - Bookmark pornhub videos from your terminal.
* [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) - Automatically switch between php versions using [php-version](https://github.com/wilmoore/php-version) if an rc-file is present in a directory.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - Plugin for [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) - 自动加载 [phpenv](https://github.com/sptndc/phpenv) and its completions.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - Plugin for [PHPUnit](https://phpunit.de/).
* [pip-app](https://github.com/sharat87/pip-app) - Makes it easy to install python applications into distinct Python virtualenvs so they don't conflict with any other python requirements on your system.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) - Automatic [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a pipenv project.
* [pipx](https://github.com/thuandt/zsh-pipx) - Autocompletions for [pipx](https://github.com/pypa/pipx).
* [pkenv](https://github.com/ptavares/zsh-pkenv) - 安装和加载 [pkenv](https://github.com/iamhsa/pkenv.git)
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - Adds ibtool shortcuts to generate localized XIB files.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Plugin for Visual Studio Code, a text editor for macOS, Windows, and Linux.
* [plugin](https://github.com/darrenbutcher/plugin) - Creates custom oh-my-zsh plugins from a boilerplate template. Very oh-my-zsh centric, the generated plugins will need editing to work with other frameworks.
* [pnpm](https://github.com/ntnyq/omz-plugin-pnpm) - Adds useful aliases for common Pnpm commands.
* [poetry (darvid)](https://github.com/darvid/zsh-poetry) - Automatically activates and deactivates [Poetry](https://poetry.eustace.io/)-created python virtualenvs.
* [poetry (sudosabin)](https://github.com/sudosubin/zsh-poetry) - Enables poetry `$PATH` and autocompletions.
* [posh-git-bash](https://github.com/lyze/posh-git-sh) - Adds `git` status in your prompt.
* [ppsmon](https://github.com/mzpqnxow/ppsmon)  - 读取 `/sys/class/net/$interface/` 以跟踪数据包传输速率. 它将当前速率存储到 RAM 支持的文件系统中的文件中，在该文件系统中可以轻松访问它以在 shell 提示中显示. 由于使用了 `/sys`，因此仅适用于 Linux.
* [pr-cwd](https://github.com/zpm-zsh/pr-cwd) - Creates a global variable with current working directory. Plugin has integration with [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
* [pr-eol](https://github.com/zpm-zsh/pr-eol) - Displays an EOL symbol which can be embedded in the prompt.
* [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) - Adds a variable you can use to display the execution time of the last command run.
* [pr-git](https://github.com/zpm-zsh/pr-git) - Creates a global variable with `git` status information that can be displayed in prompts.
* [pr-is-root](https://github.com/zpm-zsh/pr-is-root) - Sets an environment variable you can use in a custom prompt when running as root.
* [pr-jobs](https://github.com/zpm-zsh/pr-jobs) - Creates an environment variable which can be used to display background job information in a custom prompt.
* [pr-node](https://github.com/zpm-zsh/pr-node) - Sets an environment variable which can be used to display nodeJS information in a custom prompt.
* [pr-return](https://github.com/zpm-zsh/pr-return) - Plugin for ZSH who displays the exit status of the last command run.
* [presenter-mode](https://github.com/idadzie/zsh-presenter-mode) - Expands aliases during presentations. It also increases the terminal window's contrast to enhance visibility.
* [pretty-time (sindresorhus)](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
* [pretty-time (zpm-zsh)](https://github.com/zpm-zsh/pretty-time) - Converts raw seconds into human-readable strings.
* [print-alias](https://github.com/brymck/print-alias) - Prints commands with aliases expanded whenever you use an alias at the command line.
* [printc](https://github.com/philFernandez/printc) - 允许您通过简单的“printc”调用以 RGB 空间中的任何颜色进行打印.
* [profile-secrets](https://github.com/gmatheu/shell-plugins)  - 将敏感变量（api 令牌、密码等）安全地保存为终端初始化文件的一部分. 使用 gpg 使用您的秘密加密/解密文件.
* [project (gko)](https://github.com/gko/project) - Create node/python/ruby project both locally and on github(private or public repository).
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - Plugin for managing projects.
* [prompt-generator](https://github.com/the10thWiz/zsh-prompt-generator)  - 生成自定义主题. 一些生成的主题需要与电力线兼容的字体.
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - Quickly enable and disable proxy shell environment settings.
* [proxy](https://github.com/SukkaW/zsh-proxy) - Configure proxy settings for some package managers and software.
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - Plugin for lazy-loading `pyenv` in ZSH.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy) - Lazy load pyenv. The initial `eval "$(pyenv init -)"` is executed the first time `pyenv` is called.
* [pyenv](https://github.com/mattberther/zsh-pyenv) - Inspired by zsh-rbenv. Installs, updates or loads `pyenv`, and adds extra functionality.
* [pyvenv-fast](https://github.com/ACmyles/pyvenv-fast) - Launch a Python venv with one command. Designed for use with [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv).
* [q (cal2195)](https://github.com/cal2195/q) - Add `vim`-like macro registers to your ZSH shell.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - Tail/remove the temp file for [Q](https://github.com/y0ssar1an/q)，脏调试工具.
* [qiime2](https://github.com/misialq/zsh-qiime2) - 添加函数和别名以便使用 [Quiime 2](https://qiime2.org/) easier.
* [quer-ps1](https://github.com/ya0201/qwer-ps1) - A highly extendable manager for your ZSH prompt
* [quoter](https://github.com/pxgamer/quoter-zsh) - Display a random quote when opening a new terminal session.
* [quotify](https://github.com/damofthemoon/zsh-quotify) - Displays inspiring coding quotes from our pairs when starting up.
* [randeme](https://github.com/ex-surreal/randeme) - Chooses a random theme for each session. If you not like the chosen theme you can run `randeme_rm` to never show that theme again.
* [random-quotes](https://github.com/vkolagotla/zsh-random-quotes) - Displays random quotes or facts.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - 改变你的颜色 [Razer Mouse](https://openrazer.github.io/) based on the status of the last executed command. Requires [OpenRazer](https://openrazer.github.io) linux drivers.
* [rbenv (ecortinas)](https://github.com/ecortinas/zsh-rbenv) - 基于 [zsh-pyenv](https://github.com/mattberther/zsh-pyenv) plugin. This plugin will install rbenv and make it readily available
* [rbenv (elliottcable)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - 来自 oh-my-zsh 的 rbenv 插件的更快分支.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - Variant based on the original oh-my-zsh rbenv plugin.
* [rbenv (meroje)](https://github.com/Meroje/zsh-rbenv) - Inspired by [https://github.com/lukechilds/zsh-nvm/](https://github.com/lukechilds/zsh-nvm/), makes it easier to work with ruby rbenvs.
* [rc-files](https://github.com/0b10/rc-files) - 添加用于编辑各种 rc 文件的快捷功能.
* [recall](https://github.com/mango-tree/zsh-recall) - Makes using command history easier.
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - Plugin that re-enters working directory if it has been removed and re-created.
* [reload](https://github.com/aubreypwd/zsh-plugin-reload) - 添加快速重新加载您的`.zshrc`的功能.
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - A plugin which displays reminders above every prompt.
* [replace-multiple-dots](https://github.com/momo-lab/zsh-replace-multiple-dots) - Converts `...` to `../..`
* [revolver](https://github.com/molovo/revolver) - ZSH 脚本的进度微调器.
* [riddle-me](https://github.com/vkolagotla/zsh-riddle-me) - Displays random riddles.
* [ripz](https://github.com/jedahan/ripz) - Reminds you of your aliases, so you use them more. Depends on [ripgrep](https://github.com/BurntSushi/ripgrep).
* [robo](https://github.com/shengyou/robo-zsh-plugin) - A ZSH plugin for [Robo](https://github.com/consolidation/robo/).
* [rockz](https://github.com/aperezdc/rockz) - 基于 VirtualZ 的 Lua + LuaRocks 虚拟环境管理器.
* [rust](https://github.com/cowboyd/zsh-rust) - Configure your rust toolchain, installing [rustup](https://rustup.rs) if it is not currently installed already.
* [rvm](https://github.com/johnhamelink/rvm-zsh) - Initiates RVM and adds rubygem binaries (like compass) accessible in the user's `$PATH`.
* [safe-kubectl](https://github.com/benjefferies/safe-kubectl) - Add some safety when running `kubectl` by warning what context you're in after a definable number of seconds since the last `kubectl` command.
* [safe-paste](https://github.com/oz/safe-paste)  - 一个安全粘贴插件. 见康拉德欧文 [bracketed-paste](https://cirw.in/blog/bracketed-paste) blog post.
* [safe-rm](https://github.com/mattmc3/zsh-safe-rm) - Add safe-rm functionality so that `rm` will put files in your OS's trash instead of permanently deleting them.
* [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) - When using multiple AWS profiles, e.g. different accounts for your stages (development, pre-prod, prod), can be used to determine which profile is currently exported and if the token is still valid.
* [saml2aws](https://github.com/onyxraven/zsh-saml2aws) - Add support for [saml2aws](https://github.com/Versent/saml2aws).
* [sandboxd](https://github.com/benvan/sandboxd) - Speed up your `.zshrc` & shell startup with lazy-loading by only running setup commands (e.g. `eval "$(rbenv init -)"`, etc) when you need them.
* [saneopt](https://github.com/willghatch/zsh-saneopt) - Sane defaults for ZSH options, in the spirit of vim-sensible.
* [sb-upgrade](https://github.com/redxtech/zsh-sb-upgrade) - Script to automatically update apps on a seedbox.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) - Show current `chroot` name in your prompt.
* [sdkman](https://github.com/ptavares/zsh-sdkman) - Installs [sdkman](https://github.com/sdkman) and adds completions and aliases for it.
* [sealion](https://github.com/xyproto/sealion) - Allows you to set reminders that will appear in your terminal when your prompt is refreshed.
* [search-directory-history](https://github.com/cmaahs/search-directory-history) - 允许对使用创建的每个目录历史记录进行复杂搜索 [per-directory-history](https://github.com/jimhester/per-directory-history) plugin.
* [sed-sub](https://github.com/MenkeTechnologies/zsh-sed-sub) - 添加键绑定以在当前命令行上进行全局搜索和替换.
* [send](https://github.com/robertzk/send.zsh) - `git add`、`git commit` 和 `git push` 的单一命令可加快 `git` 工作流程.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - Adds many `git` aliases and helper shell functions.
* [session-sauce](https://github.com/ChrisPenner/session-sauce) - 用于所有项目的 tmux 会话创建和管理的 fzf 接口.
* [setenv](https://github.com/kalpakrg/setenv) - 更改目录时运行脚本.
* [shelf](https://github.com/ecmma/shelf) -Utility which can be used to bookmark and access directly any file using mnemonics.
* [shellfirm](https://github.com/kaplanelad/shellfirm) - Shellfirm is a handy utility to help avoid running dangerous commands without an extra step of approval. When risky patterns is detected you will immediately get a small prompt challenge that will double verify your action.
* [show-path](https://github.com/redxtech/zsh-show-path) - Provides a function shows the `$PATH` line by line.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - Plugin to easily start python `SimpleHTTPServer` and `SimpleHTTPSServer`.
* [skim](https://github.com/hackerchai/skim-zsh) - 增加了对 [skim](https://github.com/lotabout/skim)
* [slugify](https://github.com/lashoun/slugify) - Converts filenames and directories to a web friendly format.
* [smart-cd](https://github.com/dbkaplun/smart-cd) - 在 chpwd 之后运行 `ls` 和 `git status`.
* [smartinput](https://github.com/momo-lab/zsh-smartinput) - When you type brackets or quotes, the corresponding end brackets/quotes are automatically added.
* [smile](https://github.com/fundor333/smile) - Adds function to display random smileys.
* [snippets](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion.
* [solarized-man](https://github.com/zlsun/solarized-man) - A modified version of oh-my-zsh's plugin colored-man-pages, optimized for the [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) theme in the terminal.
* [spack](https://github.com/Game4Move78/zsh-spack) - Includes some useful aliases and functions for loading/unloading [Spack](https://github.com/spack/spack) - 生成的模块. 由于它使用了 `module` 命令，它比 `spack load` 更有效.
* [ssh-connect](https://github.com/gko/ssh-connect) - A simple `ssh` manager.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - `ssh` 的插件.
* [sshukh](https://github.com/anatolykopyl/sshukh-zsh-plugin) - Will update your `known_hosts` file when you `ssh` into a server.
* [startify](https://github.com/NorthIsMirror/zsh-startify) - 显示最近使用的 `vim` 文件、shell-util 文件、活动的 `tmux` 会话、最近运行的 `git` 命令等等.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - 打印 shell 启动所需的时间.
* [stashy](https://github.com/MisterRios/stashy) - 简化使用 `git stash` 的插件.
* [statify](https://github.com/vladmrnv/statify) - Plugin that does basic statistical analysis.
* [sublime](https://github.com/valentinocossar/sublime) - Same as the official Sublime plugin for Oh My Zsh, but this opens files in the current Sublime window, if there is one already open.
* [sudo](https://github.com/hcgraf/zsh-sudo) - The `sudo` plugin from oh-my-zsh, extracted to a standalone. Toggles `sudo` before the current/previous command by pressing *ESC-ESC* in emacs-mode or vi-command mode.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - 使用 ZSH 的后缀别名直接在 shell 中打开文件。
* [svn-n-zsh](https://github.com/khrt/svn-n-zsh-plugin) - Rewrite of the stock oh-my-zsh svn plugin.
* [switch-git](https://github.com/robin-mbg/switch-git) - Easy switching between `git` repositories. Just type `sgr <some part of you repo's name>`, press enter and you're there.
* [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) - Symfony 2 和 3 的 ZSH 插件.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - ZSH syntax highlighting with dircolors in realtime.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your ZSH. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgets without typing commands.
* [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard) - Adds key bindings support for ZLE (Zsh Line Editor) clipboard operations for vi emulation keymaps. It works under Linux, macOS and Android (via Termux).
* [systemd](https://github.com/le0me55i/zsh-systemd) - Adds many aliases for `systemd`.
* [t32](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [tab-title](https://github.com/trystan2k/zsh-tab-title)  - 根据当前目录或正在运行的进程设置终端标签标题. 分叉自 [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh)
* [tailf](https://github.com/rummik/zsh-tailf) - 添加带有前缀换行符而不是尾随换行符的 `tailf` 函数.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - Auto-completes task numbers for taskbook.
* [terminal-app](https://github.com/the8/terminal-app.zsh) - 用于与新 El Capitan Terminal.app 功能集成的插件.
* [terminal-title](https://github.com/AnimiVulpis/zsh-terminal-title) - Adds a `set-term-title` function you can use to title terminal windows.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - A plugin that calculates and displays how many commands have been run via terminal.
* [termux](https://github.com/zpm-zsh/termux) - Adds compatibility for [Termux](https://termux.com/)
* [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) - Add terraform workspace to prompt.
* [terraform (jsporna)](https://github.com/jsporna/terraform-zsh-plugin)  - 使用别名和制表符完成扩展原始的 oh-my-zsh 插件. 添加工作区（非默认时）以提示.
* [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) - Add convenience aliases for [terraform](https://terraform.io/), tab completions and helper function to add your terraform workspace in the prompt.
* [terraform (pbar1)](https://github.com/pbar1/zsh-terraform) - Terraform convenience functions and aliases for ZSH.
* [terraform (thuandt)](https://github.com/thuandt/zsh-terraform) - Adds convenience aliases for `terraform`, along with completions for `terraform` and `terragrunt`.
* [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - Plugin for [Terragrunt](https://github.com/gruntwork-io/terragrunt), a thin wrapper for [Terraform](https://terraform.io/) that provides extra tools.
* [tfenv](https://github.com/CDA0/zsh-tfenv) - Installs, updates, and loads tfenv inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)
* [tfswitch](https://github.com/ptavares/zsh-tfswitch) - 安装和加载 [tfswitch](https://github.com/warrensbox/terraform-switcher).
* [tgswitch](https://github.com/ptavares/zsh-tgswitch) - 安装和加载 [tgswitch](https://github.com/warrensbox/tgswitch).
* [thefuck](https://github.com/laggardkernel/thefuck) - 负载 [thefuck](https://github.com/nvbn/thefuck) (a tool which corrects your previous command) with cache support, which reduces the loading time dramatically.
* [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) - Convenience functions for working with [theia-ide](https://github.com/theia-ide/theia).
* [tig](https://github.com/MenkeTechnologies/zsh-tig-plugin) - 添加一些高级绑定 [tig](https://github.com/jonas/tig) and also provides a `tig-pick` script.
* [timewarrior](https://github.com/svenXY/timewarrior) - 增加了对 [timewarrior](https://timewarrior.net/)，一个时间跟踪应用程序.
* [tipz](https://github.com/molovo/tipz) - Displays your alias if you have an alias for the command you just ran, similarly to [alias-tips](https://github.com/djui/alias-tips).
* [title](https://github.com/zpm-zsh/title) - Allows you to set a terminal window title.
* [titles](https://github.com/jreese/zsh-titles) - Automatic window and tab titles for [tmux](https://tmux.github.io) 和 xterm 兼容的终端.
* [tm](https://github.com/kjhaber/tm.zsh) - Simplifies creating new [tmux](https://tmux.github.io) sessions, attaching to existing sessions, switching between sessions, and listing active sessions.
* [tmux-auto-title](https://github.com/mbenford/zsh-tmux-auto-title) - Automatically sets the title of windows/panes as the current foreground command.
* [tmux-multisession](https://github.com/nichus/zsh-tmux-multisession) - Plugin for [tmux](https://tmux.github.io) to support multiple sessions on a single server process.
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - Rename [tmux](https://tmux.github.io) windows automatically.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - 使用简单的插件 [tmux](https://tmux.github.io) with ZSH.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - Open files in a running `vim` (or NeoVim) session, from an adjacent [tmux](https://tmux.github.io) pane.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - Create unified terminal titles for `tmux`, ZSH, and Vim/NVIM, modular.
* [tmux](https://github.com/zpm-zsh/tmux) - Plugin for [tmux](https://tmux.github.io).
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) - Simple ZSH plugin to have a R-EP-L [tmux](https://tmux.github.io) session.
* [toggl](https://github.com/natterstefan/toggl-zsh-plugin) - Adds a `toggl-week` command to display the total working hours tracked on [toggl.com](https://toggl.com)
* [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix) - Add a widget to toggle a prefix to a command. Binds Alt+s to prefix a command with `sudo` by default.
* [traista](https://github.com/odgon/traista) - Includes `git` status decorations and color-coded exit status of the last command run. Better with dark terminal themes.
* [travis](https://github.com/denolfe/zsh-travis) - Opens the Travis CI page for the current repo if one exists.
* [tre](https://github.com/redxtech/zsh-tre) - Makes using [tre](https://github.com/dduan/tre#editor-aliasing) easier.
* [tsm](https://github.com/RobertAudi/tsm) - 添加一个 [tmux](https://tmux.github.io) Session Manager.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) - Adds tools for macOS.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 aliases.
* [ugit](https://github.com/Bhupesh-V/ugit) - Lets you undo your last `git` operation.
* [uncloudium](https://github.com/Talon1024/omz-uncloudium) - Adds helper script to download crx files from the Google Chrome web store.
* [undollar](https://github.com/zpm-zsh/undollar) - Strips the dollar sign from the beginning of the terminal prompt.
* [unique-id](https://github.com/z-shell/zsh-unique-id) - provides a unique number that identifies a running Zshell session, in its shell variable `$ZUID_ID`. Besides this unique number, also a unique codename is provided, in shell variable `$ZUID_CODENAME`. An example use case is to hold logs in files `.../mylog-${ZUID_CODENAME}.log`, so that two different Zshells will not write to the same file at the same time.
* [unix-simple](https://github.com/redxtech/zsh-unix-simple) - 显示有关 unix 简单性的图形的命令.
* [up (cjayross)](https://github.com/cjayross/up) - A simple way to navigate up through directories.
* [up (peterhurford)](https://github.com/peterhurford/up.zsh) - Adds an up command to `cd` multiple levels up.
* [update-zsh](https://github.com/AndrewHaluza/zsh-update-plugin) - Updates custom oh-my-zsh plugins. Only works with the oh-my-zsh framework.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) - A plugin for the ZSH syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos.
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - Extends the functionality of the original oh-my-zsh venv module.
* [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) - A wrapper plugin for [vagrant](https://www.vagrantup.com/) that allows for calling `vagrant` commands from outside of the box directory. The plugin also ships with a few extra commands that help to manage more than one box, along with custom tab-completion.
* [vanilli.sh](https://github.com/yous/vanilli.sh) - A lightweight start point of shell configuration.
* [vapor](https://github.com/notf0und/zsh-vapor) - Laravel vapor plugin for zsh to help you to run vapor from anywhere in the project tree, with auto-completion!
* [vcshr](https://github.com/aubreypwd/zsh-plugin-vcshr) - Help vcsh users require Github repositories using `vcsh` for auto-installation in `~/.zshrc`, etc.
* [velocity](https://github.com/rahulsalvi/velocity-python) - Powerline-based theme elements for ZSH and [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) - A super-lightweight sort-of-clone of [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/); it pretty much expects you to be using [pyenv](https://github.com/pyenv/pyenv) (though you don't *have* to), and because it's based on the [`venv` module](https://docs.python.org/3/library/venv.html), （创建）仅适用于 python &gt;= 3.3.
* [venv-wrapper](https://github.com/glostis/venv-wrapper) - Provides ZSH functions to ease the management of your virtual environments using `venv`.
* [vi-increment](https://github.com/zsh-vi-more/vi-increment) - Add `vim`-like increment/decrement operations.
* [vi-mode (jeffreytse)](https://github.com/jeffreytse/zsh-vi-mode) - 💻 A better and friendly vi(vim) mode plugin for ZSH.
* [vi-mode (nyquase)](https://github.com/Nyquase/vi-mode) Add extra `vi`-like functionality.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - Add more `vi`-like functionality to ZSH.
* [vi-motions](https://github.com/zsh-vi-more/vi-motions) - 添加新的动作和文本对象，包括带引号/括号的文本和命令.
* [vi-quote](https://github.com/zsh-vi-more/vi-quote) - Add an operation which quotes or unquotes a motion.
* [viexchange](https://github.com/okapia/zsh-viexchange) - 一个 `vi` 模式插件，用于在缓冲区中的两个位置之间轻松交换文本，例如 vim-exchange.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) - 友好的 `vi`-mode 绑定，添加基本的 Emacs 键、增量搜索、模式指示器等.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - Allows you to do `vim filename:123` to open a file with the cursor at a specific line.
* [vimman](https://github.com/yonchu/vimman) - View `vim` plugin manuals (help) like `man` in ZSH.
* [vimto](https://github.com/laurenkt/zsh-vimto) - Improved ZSH `vi` mode (bindkey -v) plugin.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - 用于 oh-my-zsh 的修改后的 virtualenv ZSH 插件.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - A fork of the virtualenv plugin from upstream. Adds support for customizing the virtualenv prompt in oh-my-zsh themes.
* [virtualz](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) 受 Adam Brenecki 启发的经理 [Virtualfish](https://github.com/adambrenecki/virtualfish) for the [Fish shell](http://fishshell.com/), replaces virtualenvwrapper.
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - 一个 oh-my-zsh 插件 [virtuozzo](https://docs.virtuozzo.com/master/index.html) bare-metal virtualization system.
* [visit](https://github.com/justinpchang/visit) - Custom plugin for faster navigation.
* [volta (cowboyd)](https://github.com/cowboyd/zsh-volta) - Seamlessly install and configure the [Volta](https://volta.sh) NodeJS toolchain manager.
* [volta](https://github.com/ri7nz/zsh-volta) - 安装和加载 [ Volta: JS Toolchains as Code](https://github.com/volta-cli/volta).
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - 一个 oh-my-zsh 插件来控制 [VOX](https://vox.rocks/), a lightweight full-featured audio player for macOS that can play a variety of formats including FLAC and Ogg Vorbis.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for Visual Studio Code on macOS.
* [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) - 简单的插件，可以轻松地跨系统打开 VS 代码.
* [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) - Plugin for [Visual Studio Code](https://code.visualstudio.com/).
* [vterm](https://github.com/randomphrase/vterm-zsh-plugin) - Lets you run emacs commands directly from [vterm](https://github.com/vterm/vterm) shell sessions.
* [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) - 跟踪多少 [time](https://wakatime.com/) 你已经在你的终端消费了. 具有每个项目的统计信息.
* [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) - Automatic time tracking for commands in ZSH using [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - 配置着色与 [grc](https://github.com/garabik/grc).
* [watch](https://github.com/enrico9034/zsh-watch-plugin) - 通过按“CTRL + W”，可以轻松地为当前或以前的命令添加前缀.
* [watson.zsh](https://github.com/bcho/Watson.zsh) - A plugin for the [watson](https://github.com/TailorDev/Watson) 时间管理系统.
* [wd](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
* [web-search (sinetoami)](https://github.com/sinetoami/web-search) - Add commands to run bing, google, yahoo, & duckduckgo searches directly from the CLI.
* [web-search (yabanahano)](https://github.com/Yabanahano/web-search) - Adds aliases for searching with Google, Wiki, Bing, YouTube and other popular services.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - 使用 `git blame` 突出显示文件中最后更改特定行的位置.
* [window-title](https://github.com/olets/zsh-window-title) - Adds informative tiles to your terminal windows.
* [windows-title](https://github.com/mdarocha/zsh-windows-title) - Dynamically updates terminal window title with current directory and the last command run.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) - Simple utility for jumping between projects.
* [worktree](https://github.com/jspears/worktree) - Adds functions that wrap `git worktree`.
* [xdg-basedirs](https://github.com/zshzoo/xdg-basedirs) - 配置应用程序以使用 XDG 基本目录.
* [xxh-plugin-zsh-zshrc](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) - plugin for [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) that copies your `~/.zshrc` to a remote host and sources it with [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh).
* [yadm](https://github.com/juanrgon/yadm-zsh) - Displays a warning if there are local yadm configuration changes.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - Automatically activate a directory's pip environment if `pipenv` detects the presence of one.
* [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's Yeoman plugin for oh-my-zsh, compatible with yeoman version ≥1.0 (includes options and command auto-completion).
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH plugin that reminds you to use those aliases you defined.
* [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) - Adds `yt` aliases to download videos from YouTube.
* [youtube-dl](https://github.com/joow/youtube-dl) - Simple plugin for [youtube-dl](https://youtube-dl.org/).
* [yup](https://github.com/redxtech/zsh-yup) - Adds helper function to upgrade all the dependencies in a yarn/npm project.
* [z.lua](https://github.com/skywind3000/z.lua) - A command line tool which helps you navigate faster by learning your habits. An alternative to [z.sh](https://github.com/rupa/z) with Windows and posix shells support and various improvements. 10x faster than fasd and autojump, 3x faster than [z.sh](https://github.com/rupa/z).
* [zabb](https://github.com/Mellbourn/zabb) - `zabb` 是一个命令，它试图找出可供用户使用的目录的最短记忆缩写 [z](https://github.com/ajeetdsouza/zoxide) to unambiguously jump to that directory.
* [zabrze](https://github.com/Ryooooooga/zabrze) - A ZSH abbreviation expansion plugin.
* [zaw](https://github.com/zsh-users/zaw) - ZSH anything.el-like widget.
* [zbrowse](https://github.com/zdharma-continuum/zbrowse) - When doing shell work, it is often the case that echo $variable is invoked multiple times, to check the result of a loop, etc. With ZBrowse, you just need to press `Ctrl-B`, which invokes the ZBrowse – Zshell variable browser.
* [zce](https://github.com/hchbaw/zce.zsh) - Vim’s EasyMotion / Emacs’s ace-jump-mode for ZSH.
* [zcolors](https://github.com/marlonrichert/zcolors) - Uses your `$LS_COLORS` to generate a coherent theme for Git and your Zsh prompt, completions and [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [zconvey](https://github.com/zdharma-continuum/zconvey) - Adds ability to send commands to other ZSH sessions, you can use this to `cd $PWD` on all active ZSH sessions, for example.
* [zed](https://github.com/eendroroy/zed-zsh) - A simple wrapper for [z](https://github.com/rupa/z) to install it via a ZSH plugin.
* [zeit](https://github.com/zeit/zeit.zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
* [zellij (jaeheonji)](https://github.com/jaeheonji/zsh-zellij-plugin) - 提供使用环境 [zellij](https://github.com/zellij-org/zellij). Requires `tmux`.
* [zellij (tranzystorek-io)](https://github.com/tranzystorek-io/zellij-zsh) - Provides an environment that autostarts [zellij](https://github.com/zellij-org/zellij) as your terminal's multiplexer.
* [zeno](https://github.com/yuki-yano/zeno.zsh) - Fuzzy completion and utility plugin powered by [Deno](https://deno.land/).
* [zero](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details.
* [zflai](https://github.com/zdharma-continuum/zflai) - ZSH 的快速日志记录框架.
* [zfzf](https://github.com/b0o/zfzf) - A fzf-powered file picker for ZSH which allows you to quickly navigate the directory hierarchy.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - Make compinit run only once after all loading is done by [zgen](https://github.com/tarjoilija/zgen).
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) - Custom extras for zimfw, packaged into a zimfw plugin.
* [zinfo_line](https://github.com/kmhjs/zinfo_line) - Makes more information available to ZSH themes.
* [zinit-annex-bin-gem-node](https://github.com/zdharma-continuum/zinit-annex-bin-gem-node) - [zinit](https://github.com/zdharma-continuum/zinit) extension that exposes binaries without altering `$PATH`, installs Ruby gems and Node modules and easily exposes their binaries, and updates the gems and modules when the associated plugin or snippet is updated.
* [zinit-annex-default-ice](https://github.com/zdharma-continuum/zinit-annex-default-ice) - Allows user to define ices active for multiple zinit commands.
* [zinit-annex-man](https://github.com/zdharma-continuum/zinit-annex-man) - [Zinit](https://github.com/zdharma-continuum/zinit) extension that generates man pages for all plugins and snippets
* [zinit-annex-meta-plugins](https://github.com/zdharma-continuum/zinit-annex-meta-plugins) - Install groups of plugins with a single label ([zinit](https://github.com/zdharma-continuum/zinit) only).
* [zinit-annex-patch-dl](https://github.com/zdharma-continuum/zinit-annex-patch-dl) - [zinit](https://github.com/zdharma-continuum/zinit) extension that downloads files and applies patches through the provided `dl` and `patch` zinit ices.
* [zinit-annex-readurl](https://github.com/zdharma-continuum/zinit-annex-readurl) - Adds function to automatically download the newest version of a file to which URL is hosted on a webpage.
* [zinit-annex-rust](https://github.com/zdharma-continuum/zinit-annex-rust) - [zinit](https://github.com/zdharma-continuum/zinit) extension that that installs rust and cargo packages inside plugin directories.
* [zinit-annex-submods](https://github.com/z-shell/z-a-submods) - [zinit](https://github.com/zdharma-continuum/zinit) 扩展允许在插件或片段中安装和管理额外的子模块.
* [zinit-annex-test](https://github.com/NorthIsMirror/z-a-test) - [zinit](https://github.com/zdharma-continuum/zinit) extension that runs tests (via make test, for example) – if it finds any of them – after installing and updating a plugin or snippet.
* [zinit-annex-unscope](https://github.com/zdharma-continuum/zinit-annex-unscope) - Allows installing plugins for [zinit](https://github.com/zdharma-continuum/zinit) without specifying the user name by querying the Github API.
* [zinit-console](https://github.com/z-shell/zinit-console) - 半图形（诅咒）控制台 [zinit](https://github.com/zdharma-continuum/zinit) plugin manager.
* [zinsults](https://github.com/ahmubashshir/zinsults) - Prints insults if a command fails.
* [zjump](https://github.com/qoomon/zjump) - Simplify ZSH directory navigation; jump to already visited, parent or sub folders.
* [zlitefetch](https://github.com/ippee/zlitefetch) - Lightweight system information plugin.
* [zlong_alert](https://github.com/kevinywlui/zlong_alert.zsh) - Uses notify-send and ring a bell to alert you when a command that has taken a long time (default: 15 seconds) has completed.
* [zman](https://github.com/mattmc3/zman) - Use `fzf` to quickly browse Zsh manuals.
* [zoxide](https://github.com/ajeetdsouza/zoxide) - A fast alternative to `cd` that learns your habits.
* [zredis](https://github.com/zdharma-continuum/zredis) - Adds Redis database support, with `database_key` <-> `shell_variable` binding. Supports all data types.
* [zsh-in-docker](https://github.com/deluan/zsh-in-docker)  - 自动将 ZSH + Oh-My-ZSH 安装到开发容器中. 适用于 Alpine、Ubuntu、Debian、CentOS 或 Amazon Linux.
* [zsh-not-vim](https://github.com/redxtech/zsh-not-vim) - 提供自动羞辱用户忘记他们没有在 vim 中的功能。
* [zsh-z (agkozak)](https://github.com/agkozak/zsh-z) - Jump quickly to directories that you have visited "frecently." A native ZSH port of `z.sh` - without `awk`, `sed`, `sort`, or `date`.
* [zsh-z (ptavares)](https://github.com/ptavares/zsh-z) - 安装和加载 [z](https://github.com/rupa/z.git).
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for oh-my-zsh.
* [zshrc](https://github.com/freak2geek/zshrc) - Load local `.zshrc` files from your project scopes.
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - Plugin for taking ZFS pre/post upgrade snapshots on Arch Linux.
* [zsnapshot](https://github.com/zdharma-continuum/zsnapshot) - Adds command to dump the current ZSH state into a file, for later restoration by sourcing the snapshot file.
* [ztouch](https://github.com/mjrafferty/ztouch) - Adds touchbar controls for recent history commands, directory stack, cycling between modes and user-mappable commands to the touchbar on macOS.
* [zui](https://github.com/zdharma-continuum/zui) - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH.)

## Completions

These plugins add tab completions without adding extra functions or aliases.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - Extends ZSH's \_urls completion, allowing it to complete urls from html pages.
* [aliyun](https://github.com/thuandt/zsh-aliyun) - Add completions for the [Aliyun CLI](https://github.com/aliyun/aliyun-cli).
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - Completions for viasite-ansible/ansible-server.
* [antibody-completion](https://github.com/sinetoami/antibody-completion) - This plugin provides completion for [Antibody](https://github.com/getantibody/antibody) plugin manager.
* [appspec](https://github.com/perlpunk/App-AppSpec-p5) - Generating completions for Bash and ZSH from YAML specs
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - autopkg 的完成.
* [aws-completions](https://github.com/eastokes/aws-plugin-zsh) - Adds completion support for `awscli` to manage AWS profiles/regions and display them in the prompt.
* [aws_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) - 为 aws_manager CLI 添加完成.
* [bash-completions-fallback](https://github.com/3v1n0/zsh-bash-completions-fallback) - Support `bash` completions for commands when no native ZSH one is available.
* [batect](https://github.com/batect/batect-zsh-completion/) - 添加选项卡完成 [batect](https://batect.dev/) build system.
* [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) - 为 berkshelf 添加选项卡完成.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - Better tab completion for `npm`.
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - Adds BOSH autocompletion.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) - 自制服务的完成插件.
* [buidler](https://github.com/gonzalobellino/buidler-zsh) - Adds completion and useful aliases for NomicLabs Buidler tool [buidler.dev](https://buidler.dev).
* [bw](https://github.com/CupricReki/zsh-bw-completion) - 添加完成 [Bitwarden](https://bitwarden.com/).
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - Add tab completion for cabal.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal.
* [carapace](https://github.com/rsteube/carapace) - Completion generator for Bash, Elvish, Fish, Oil, Powershell, Xonsh and ZSH. Note - not dynamic, you have to explicitly run it to generate completions for a command.
* [cargo](https://github.com/MenkeTechnologies/zsh-cargo-completion) - All the functionality of the original OMZ cargo completion, with additional support for remote crates via `cargo search` in `cargo add`.
* [carthage](https://github.com/squarefrog/zsh-carthage) - Provides completions and aliases for use with [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) - Adds autocomplete for all [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) commands.
* [cod](https://github.com/dim-an/cod) - A completion demon for `bash`/`fish`/`zsh` which creates completion functions on the fly when it sees you run something with `--help`.
* [codeception](https://github.com/shengyou/codeception-zsh-plugin) - 为 Codeception 测试框架添加命令完成.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Displays git info, whether you're logged in via `ssh`, return code of last command.
* [comonicon](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) - 选项卡完成 [comonicon](https://github.com/Roger-luo/Comonicon.jl).
* [completions](https://github.com/zsh-users/zsh-completions) - A collection of extra completions for ZSH.
* [conda](https://github.com/esc/conda-zsh-completion) - ZSH tab completion for conda.
* [cpan](https://github.com/MenkeTechnologies/zsh-cpan-completion) - Adds `cpan install word<tab>` and `cpanm install <tab>` to complete remote CPAN package names.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - 选项卡完成 [ctop](https://github.com/bcicen/ctop).
* [dagger](https://github.com/jygastaud/dagger-oh-my-zsh) - 完成匕首.
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
* [docker (chr-fritz)](https://github.com/chr-fritz/docker-completion.zshplugin) - Loads `docker` ZSH tab completions directly from **Docker for Mac**.
* [docker (felixr)](https://github.com/felixr/docker-zsh-completion) - Add tab completions for `docker`.
* [docker (greymd)](https://github.com/greymd/docker-zsh-completion) - Add tab completions for `docker` and `docker-compose`.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - Command completion for [docker-enter](https://github.com/jpetazzo/nsenter).
* [dotnet](https://github.com/MenkeTechnologies/zsh-dotnet-completion) - dotnet 选项卡完成.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - ZSH 的 Drush 自动完成功能很棒.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - A ZSH plugin for [duell](https://github.com/gameduell/duell).
* [efibootmgr](https://github.com/wehlando/efibootmgr-zsh-completion) - Tab completions for `efibootmgr`.
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - Adds etcdctl tab completions.
* [expressvpn](https://github.com/tk7r/zsh-expressvpn) - Adds tab completions for the [expressVPN](https://www.expressvpn.com/support/vpn-setup/app-for-linux/) client.
* [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) - Defines a function called extract that extracts the archive file you pass it, and supports a wide variety of archive filetypes.
* [extract (thetic)](https://github.com/thetic/extract) - Fork of the oh-my-zsh extract plugin.
* [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - Adds autocompletion options for all [Concourse CLI](https://www.concourse.ci/fly-cli.html) commands.
* [fzf-gcloud](https://github.com/mbhynes/fzf-gcloud) - 导航和预览所有 Google Cloud SDK `gcloud` CLI 命令的模糊补全
* [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) - Add tab completion for ZSH, bash & applications using GNU Readline.
* [fzf-zsh-completions](https://github.com/chitoku-k/fzf-zsh-completions) - 模糊完成 [fzf](https://github.com/junegunn/fzf) and [ZSH](https://www.zsh.org/) 可以由默认为 `**` 的触发序列触发.
* [gcloud](https://github.com/littleq0903/gcloud-zsh-completion) - 为 Google Cloud SDK 添加补全.
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - providing ZSH completion support to various Gentoo tools that lack completion scripts upstream.
* [git-annex](https://github.com/Schnouki/git-annex-zsh-completion) - Allows tab completion for most git-annex commands.
* [git-flow](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for [git-flow](http://github.com/nvie/gitflow).
* [git-fzf](https://github.com/alexiszamanidis/zsh-git-fzf) - ZSH plugin that wraps `git` operations for simplicity and productivity. It also contains completions and combines support for [fzf](https://github.com/junegunn/fzf).
* [github-cli](https://github.com/sudosubin/zsh-github-cli) - Tab completions for the github cli.
* [gitlab-runner](https://github.com/pseyfert/zsh-gitlab-runner-completion) - ZSH completions for gitlab-ci-multi-runner.
* [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) - Bash and ZSH completion support for gradle.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - ZSH completion support for gradle.
* [grid5000](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 plugin - adds theme, autocompletions.
* [gulp (akoenig)](https://github.com/akoenig/gulp.plugin.zsh) - Autocompletion for your gulp.js tasks in the Z-Shell (ZSH).
* [gulp (srijanshetty)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - Autocompletion for gulp.
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) - Completions for [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haskell](https://github.com/coot/zsh-haskell) - Adds completions for `cabal`, `ghc` and `ghc-pkgs` commands.
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib.
* [helmfile](https://github.com/Downager/zsh-helmfile) - Adds autocompletion for `helm`.
* [inspr](https://github.com/ptcar2009/insprzsh) - Completions for [inspr](https://github.com/inspr/inspr)
* [ipfs](https://github.com/hellounicorn/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.io).
* [joe](https://github.com/corvofeng/joe-completion) - Adds completions for [joe](https://github.com/karan/joe) gitignore editor.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - ZSH completions for jtool.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - Adds autocompletion for [jumpstorm](https://github.com/netresearch/jumpstorm)
* [jx](https://github.com/haysclark/zsh-jx) - Adds tab completions for the Jenkins-X cli.
* [kafka](https://github.com/Dabz/kafka-zsh-completions) - Completions for Apache [kafka](https://kafka.apache.org).
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - Completions for [keybase](https://keybase.io/docs/command_line).
* [kitty](https://github.com/redxtech/zsh-kitty) - Completions for [kitty](https://sw.kovidgoyal.net/kitty/) terminal emulator.
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - 添加选项卡完成 [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - 添加选项卡完成 [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
* [kubectl-fzf](https://github.com/bonnefoa/kubectl-fzf) - 快速而强大 [`fzf`](https://github.com/junegunn/fzf)-powered autocompletion for `kubectl`.
* [lazycomplete](https://github.com/rsteube/lazycomplete) - Lazy loading for shell completion scripts.
* [lets](https://github.com/lets-cli/lets-zsh-plugin) - Add autocompletion for [lets](https://github.com/lets-cli/lets) cli task runner.
* [ls-go](https://github.com/MohamedElashri/ls-go-zsh) - Adds some useful aliases for [ls-go](https://github.com/acarl005/ls-go).
* [mooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - Perl 模块 `MooseX::App` 的完成生成器.
* [more-completions](https://github.com/MenkeTechnologies/zsh-more-completions) - 10500 zsh compsys completions!
* [msfvenom](https://github.com/Green-m/msfvenom-zsh-completion) - Tab completions for Metasploit.
* [mx-honey](https://github.com/mukel/mx-honey) - Provides completions for [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.
* [newman](https://github.com/selop/newman-autocomplete) - Provides autocompletion for the [Newman CLI](https://github.com/postmanlabs/newman).
* [nix](https://github.com/spwhitt/nix-zsh-completions) - Completions for [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/), and [NixOps](https://nixos.org/nixops/).
* [node-ace](https://github.com/romch007/node-ace-zsh-completion) - Completions for `node ace`.
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) - Provides auto-complete for nova.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - 对“npm run”的自动完成支持。
* [nx](https://github.com/jscutlery/nx-completion) - Completions for [nx](https://nx.dev). Requires [`jq`](https://stedolan.github.io/jq/).
* [okta](https://github.com/sirhc/okta.plugin.zsh) - Provides command line completions for the [`aws-okta`](https://github.com/segmentio/aws-okta) and [okta-awscli](https://github.com/jmhale/okta-awscli) commands.
* [op](https://github.com/sirhc/op.plugin.zsh) - 选项卡完成 [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) command line tool.
* [packer](https://github.com/wakeful/zsh-packer) - Adds tab completion for [packer](https://packer.io).
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin.
* [parallels](https://github.com/benclark/parallels-zsh-plugin) - 为 Parallels 桌面添加补全.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - 方便的回购，轻松获得 [pass](https://www.passwordstore.org/) command completion for ZSH.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - pip 的自动完成插件.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - Enables aliases for the most common pipenv commands.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) - Completions for `pipenv`.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh) - automatically activates a **pipenv** when entering a directory if there is Pipfile in that directory. Includes `pipenv` completions.
* [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) - Adds completions for Pivotal's [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
* [pmy](https://github.com/relastle/pmy) - General purpose context-aware ZSH completion engine powered by [fzf](https://github.com/junegunn/fzf).
* [quickjump](https://github.com/fikovnik/zsh-quickjump) - Adds tab completion support for [skim](https://github.com/lotabout/skim) for recent files and directories using [fasd](https://github.com/whjvenyl/fasd).
* [racket completion](https://github.com/racket/shell-completion) - Completion for [Racket](http://racket-lang.org).
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets.
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) - 为 Rancher CLI 添加完成.
* [rhoas](https://github.com/craicoverflow/rhoas-zsh-plugin) - Adds completions for [rhoas](https://developers.redhat.com/products/red-hat-openshift-streams-for-apache-kafka/overview).
* [rustup](https://github.com/pkulev/zsh-rustup-completion) - Tab completions for Rustup.
* [s3cmd](https://github.com/FFKL/s3cmd-zsh-plugin) - 添加选项卡完成 [s3cmd](https://s3tools.org/s3cmd).
* [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion) - ZSH command completion for the Salesforce CLI. Requires [jq](https://stedolan.github.io/jq/).
* [saml2aws](https://github.com/sirhc/saml2aws.plugin.zsh) - Adds completions for [saml2aws](https://github.com/Versent/saml2aws).
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) - autocomplete plugin for sfdx.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - Adds autocompletions for [spring-boot](http://projects.spring.io/spring-boot/) commands.
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - Manage `ssh-agent`.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - Automatically starts `ssh-agent` to set up and load whichever credentials you want for `ssh` connections.
* [ssh](https://github.com/zpm-zsh/ssh) - Add host completion for `ssh`.
* [surf](https://github.com/beardcoder/surf.plugin.zsh) - Add completions for surf.
* [symphony (TheGrowingPlant)](https://github.com/TheGrowingPlant/symfony.plugin.zsh) - Autocompletion for Symfony 3 and 4 commands.
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - 添加完成 [Test Kitchen](https://github.com/test-kitchen/test-kitchen)).
* [tinygo](https://github.com/sago35/tinygo-autocmpl) - 为 tinygo 添加选项卡补全.
* [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your [tmux](https://tmux.github.io) pane.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - Adds autocompletion for [tugboat](https://github.com/petems/tugboat) command.
* [umake](https://github.com/zlsun/umake) - Tab completion for Ubuntu umake.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - 提供自动完成功能 [vertx](https://vertx.io/) command.
* [web-open](https://github.com/AndrewHaluza/zsh-web-open)  - 添加别名以打开网页. 仅适用于 Ubuntu 20.
* [yabai](https://github.com/Amar1729/yabai-zsh-completions) - Add completions for macOS [yabai](https://github.com/koekeishiya/yabai/) tiling window manager.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - Add autocompletions for `yarn add`, `yarn remove`, `yarn upgrade`, `yarn why` and `yarn run`.
* [zargparse](https://github.com/ctil/zargparse) - Pass it a script that uses `argparse` and it will write a ZSH completion to your current directory.
* [zstyle-completions](https://github.com/zshzoo/zstyle-completions) - 给 [prezto-style](https://github.com/sorin-ionescu/prezto) completions when you hit tab.

## Themes

If you're using [Antigen](https://github.com/zsh-users/antigen) ，您可以使用“antigen theme githubuser/repo”在运行的 ZSH 中测试这些主题. 如果你正在使用 [zgenom](https://github.com/jandamm/zgenom), add them to your `init.zsh` with `zgenom load githubuser/reponame`.

* [000](https://github.com/Abid-Ahmad/oh-my-zsh-000-theme) - 带有用户名、主机名、完整路径、返回状态和“git”装饰的多行提示.
* [0i0](https://github.com/0i0/0i0.zsh-theme) - Optimized for dark terminal windows, uses nerdfont `git` status decorations.
* [14degree](https://github.com/saims0n/14degree-zsh-theme/) - Includes `git`, `virtualenv` and `rvm` status decorations.
* [4den](https://github.com/RunThem/zsh-theme-4den) - Minimalist. Includes `git` and `hg` status decorations.
* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - Based on the Sorin theme.
* [abbr (theme)](https://github.com/PhilsLab/abbr-zsh-theme) - Displays an abbreviated version of the current directory path, shows the Python virtualenv, Rust version, `git` status, and the exit code of last command. Works well on dark backgrounds by default but colors can be easily customized.
* [absolute](https://github.com/NelsonBrandao/absolute) - 非常干净的主题，带有 git 状态、节点版本和最后一个命令的退出代码.
* [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) - Includes `git` status decorations, name of your AWS profile, name of your Azure Service Principal, kubernetes context, terraform workspace, command status and current working directory.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS theme, requires a Powerline-compatible font.
* [af-magic-dynamic](https://github.com/rslavin/af-magic-dynamic) - Modified version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) with dynamic path shortening.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - Modified version of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme in oh-my-zsh.
* [aftermath](https://github.com/schanur/aftermath) - Get a nice summary line after each command you run in your shell.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) - 基于 [agnoster](https://gist.github.com/3712874) theme included in [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) and [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt). Shows detailed information about `git` status.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt)  - 使用三种异步方法来保持 ZSH 提示响应，同时显示 `git` 状态和 SSH 连接、退出代码和 `vi` 模式的指示符，以及缩写的 `PROMPT_DIRTIM` 样式路径. 非常可定制. 即使在 Cygwin 和 MSYS2 上也是异步的.
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - Solarized [Agnoster](https://gist.github.com/agnoster/3712874) 带有 `git` 状态信息的变体. 需要 unicode 字体，最好使用 [solarized](https://github.com/altercation/solarized) 终端.
* [agnoster-fseguin](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) variant with a right prompt.
* [agnoster-gentoo](https://github.com/r7l/agnoster-gentoo-zsh-theme) - A Gentoo flavored version of the [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme) that includes user@hostname and `git` status decorations. Works better with a unicode font.
* [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) - Optimized for [solarized](https://ethanschoonover.com/solarized/) color scheme, `git` or other VCS tools, and unicode-compatible fonts. Includes status of last command run, user@hostname, `git` status decorations, working directory, whether running as root, whether background jobs are running, and other information.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with a right-prompt.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant optimized for use with [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) terminal color scheme. Includes `git` status.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) variant, includes battery and online status.
* [agnoster-repopath](https://github.com/ivanfurlan/agnoster-repopath-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) themes. Includes `git` and `mercurial` status, current time and time the last command took decorations in the prompt.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 添加了时间戳和换行符的变体.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - 基于 [Powerline](https://github.com/Lokaltog/vim-powerline) and [Agnoster](https://gist.github.com/agnoster/3712874) themes and inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnoster](https://gist.github.com/agnoster/3712874)  - 针对 solarized 终端配色方案进行了优化，显示 `git` 装饰、用户@主机、工作目录、上一个命令的退出状态以及您是否以 root 权限运行. 需要与电力线兼容的字体.
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - 基于 [Agnoster](https://gist.github.com/agnoster/3712874), shows battery life, date & time, `git` status, current directory and user & host information.
* [akzsh](https://github.com/awkimball/akzsh) - Works best with a dark terminal theme, includes `git` decorations.
* [alarangeiras](https://github.com/alarangeiras/alarangeiras-zsh-theme/) - 带有“git”状态装饰的极简主义主题.
* [ale](https://github.com/alepimentel/ale-zsh) - Based on the fino theme. Includes `git`, `virtualenv` and `node` status decorations.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) - Minimalist ZSH theme with `git` status displayed.
* [alien](https://github.com/eendroroy/alien)  - 电力线风格的 ZSH 主题，显示 `git` 装饰和最后一个命令的退出代码. 比许多其他提示更快，因为它在后台进程中异步确定 `git` 装饰.
* [almel](https://github.com/Ryooooooga/almel) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme), written in Rust. Includes `git` status, user@host, last command exit status and working directory decorations
* [alpharized](https://github.com/NicoSantangelo/Alpharized) - 优化工作 [solarized](http://ethanschoonover.com/solarized) dark terminals. It's a modified version of the [avit theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme).
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - An elegant and comfortable-reading theme based on [Agnoster](https://gist.github.com/agnoster/3712874).
* [andy](https://github.com/andymcguinness/andys-theme) - 修改 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme with better `git` support.
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) - Shows `git` information in the right hand prompt.
* [antoinechab](https://github.com/antoinechab/antoinechab-theme) - Includes `git` status, username, time and current directory decorations.
* [antsy](https://github.com/jeffmhubbard/antsy-zsh-theme) - 显示 `git` 分支和状态装饰、virtualenv、退出状态、作业计数和 vi 模式指示器.
* [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) - Shows `git` decorations, user, host, whether root, active Python virtual environment, current Ruby interpreter, visual and numeric status of the last command, power management status and time and date.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme)  - 没有视觉噪音的简约主题. 仅显示必要的信息：当前用户、主机名、工作目录、`git` 分支（如果存在）. 深色和白色端子看起来都很棒.
* [aplos](https://github.com/sunquan1991/aplos) - Minimal ZSH prompt with working directory, `git` local info, `git` remote info, time and exit code.
* [apollo](https://github.com/mjrafferty/apollo-zsh-theme) - A heavily customizable, compatible and performant ZSH theme that uses modules to enable features.
* [apple (aramirol)](https://github.com/aramirol/apple-zsh-custom-themes) - 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme), includes `vcs` status decorations. Colors customizable by setting vars in your `.zshrc`.
* [apple (bjrowlett2)](https://github.com/bjrowlett2/apple-zsh-theme) - 带有“git”状态装饰的极简主义主题.
* [arael](https://github.com/aknackd/zsh-themes) - 叉子 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [archcraft](https://github.com/mrx04programmer/ZshTheme-ArchCraft) - Greenish theme, optimized for dark backgrounds. Includes `git` status decorations.
* [archie](https://github.com/dcavalcante/archie) - Arch Linux inspired ZSH theme. Based on the [norm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) theme.
* [arity](https://github.com/hybras/Arity-Zsh-Theme) - Arity is a simple theme designed for readability and to give an overview at a glance. Includes path and `git` decorations.
* [aronhoyer](https://github.com/aronhoyer/zsh-theme) - Minimalist theme with right-side `git` status decorations.
* [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - A minimal ZSH theme with `git` decorations.
* [asciigit](https://github.com/cemsbr/asciigit) - An ASCII-only theme for `git` users who don't want to use fonts with extra glyphs.
* [asq](https://github.com/AugustoQueiroz/asq-theme) - 基于 [theunraveler](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#theunraveler).
* [astral](https://github.com/xwmx/astral) - Theme for dark backgrounds with zen mode. Works well with the zsh-users [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) plugin.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - Based on the `ys` and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) themes.
* [async](https://github.com/mje-nz/zsh-themes) - 显示当前目录、`git` 状态、最后一个命令的返回值（如果有错误代码）、后台作业的数量、长时间运行的命令的执行时间、当前的 python virtualenv.
* [aub](https://github.com/FraSharp/aub) - Includes decorations for `git` and `hg` status and `username` at `host`.
* [aterminal](https://github.com/guiferpa/aterminal) - Displays Nodejs, NPM, Docker, Go, Python, Elixir and Ruby information in the prompt.
* [avil](https://github.com/avil13/avil-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) - Based on the oh-my-zsh [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme, with small changes.
* [avit-mod](https://github.com/zlsun/avit-mod) - Modified version of oh-my-zsh's [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme.
* [banana](https://github.com/sorcererxw/banana-zsh-theme) - Includes `git` status decorations and current directory.
* [bandit](https://github.com/Holger-Will/zsh_bandit) - 另一个电力线变体.
* [bar (anki-code)](https://github.com/anki-code/bar-theme) - 极简主义设置 [p10k](https://github.com/romkatv/powerlevel10k).
* [bar (xp-bar)](https://github.com/xp-bar/zsh-bar-theme) - Includes username, host, pwd, `git` status decorations and  3x hour reminders to drink water.
* [barion](https://github.com/SEbbaDK/barion) - A fast compiled prompt with a compact `git` status overview. Reminiscent of powerline. Requires [Crystal](https://crystal-lang.org/) to build.
* [bash](https://github.com/starseekist/bash-zsh-theme) - Looks like the default `bash` prompt.
* [bashi](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) theme and Pasquale D'Silva's [Saturn Terminal](https://github.com/psql/saturn-colors) theme.
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - Modified version of [gitster](https://github.com/zimfw/gitster) 主题为 [ZIM](https://github.com/zimfw/zimfw).
* [bearable](https://github.com/JanmanX/bearable-zsh) - 适用于深色终端背景.
* [bedbugs](https://github.com/justino/zsh-theme-bedbugs) - Inspired by [Agnoster](https://gist.github.com/agnoster/3712874), this multiline prompt includes `git` status information, background job count, working directory, user and hostname, Python virtualenv when present, colored return value of last command and root/user sigil.
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - Inspired by [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme), but with beer icons.
* [bender](https://github.com/specious/bender) - 带有 git 集成的精美两行提示.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有 unicode 符号的变体.
* [biraSkull](https://github.com/Shahryar-Pirooz/biraSkull.zsh-theme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), includes root status and `git` status decorations.
* [biradate](https://github.com/vemonet/zsh-theme-biradate) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 主题，但在提示中显示日期而不是用户名.
* [birame](https://github.com/maniat1k/birame) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [birav2](https://github.com/shahid64/birav2-theme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme). Includes `git`, `rvm` and `virtualenv` status decorations.
* [bklyn](https://github.com/gporrata/bklyn-zsh) - Variant of [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) 应用了自定义.
* [black-Void](https://github.com/black7375/BlaCk-Void-Zsh) - Includes account info, root user, using ssh, directory lotation, write permission, vcs info decorations.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) - Another `git`-aware theme.
* [blazux](https://github.com/blazux/omz-theme) - Includes `git` status decoration and a smiley/sad face indicator of the last command's exit status.
* [blinks (max13ft)](https://github.com/max13fr/blinks.zsh-theme) - Adds mercurial support to oh-my-zsh's [blink](https://github.com/max13fr/blinks.zsh-theme) theme.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) - Based on the existing theme [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme).
* [bliss](https://github.com/joshjon/bliss-zsh) - A delicate theme that injects color without overwhelming your workspace. Designed to be used with the [bliss iTerm](https://github.com/joshjon/bliss-iterm) color scheme and [bliss dircolors](https://github.com/joshjon/bliss-dircolors). Includes `git` status decorations.
* [blokkzh](https://github.com/KorvinSilver/blokkzh) - Theme based on oh-my-zsh's built in [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) theme. Requires a font with unicode support.
* [blox](https://github.com/yardnsm/blox-zsh-theme) - A minimal and fast ZSH theme that shows you what you need. It consists of blocks: each block is shown inside a pair of \[square brackets\], and you can add blocks by simply creating a function.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - Minimal theme, displays `git` information.
* [bluelines](https://github.com/apbarrero/bluelines) - 清晰的蓝色主题.
* [bluo](https://github.com/varunpbardwaj/bluo) - Colorful prompt segments reminiscent of [bullet-train](https://github.com/caiogondim/bullet-train.zsh) or [powerlevel10k](https://github.com/romkatv/powerlevel10k). Includes `git` status decorations.
* [bogo](https://github.com/cubasepp/zsh-bogo-theme) - Inspired by [zeta](https://github.com/skylerlee/zeta-zsh-theme). Includes `git` and ruby version decorations.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - Multiline theme, best on dark backgrounds.
* [bougenville](https://github.com/bougenville/zsh-theme) - Variant of [dallas](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dallas.zsh-theme).
* [bronze](https://github.com/reujab/bronze)  - 一个跨外壳可定制的类似电力线的提示，带有用 go 编写的图标. 需要 [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
* [brs](https://github.com/evenhold/brs-zsh-theme) - Displays the current song in the prompt with `audtool`.
* [bruh](https://github.com/haze/bruh) - Includes `git` status decorations.
* [brunty](https://github.com/Brunty/omz-brunty) - Brunty theme.
* [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) - Inspired by the [powerline](https://github.com/Lokaltog/vim-powerline) and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) themes.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF color theme.
* [bubblegum](https://github.com/ice-bear-forever/bubblegum-zsh) - Minimalist bright pink theme with a triangular glyph and your working directory, nothing else—leaving you with the cleanest shell possible.
* [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme). Works best with [nerdfonts](https://github.com/ryanoasis/nerd-fonts).
* [bubblified (varaki)](https://github.com/varaki/bubblified-varaki.zsh-theme) - 基于 [bubblified (hohmannr)](https://github.com/hohmannr/bubblified). Changes color when root.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh) - Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH 主题，修改为只显示时间和目录.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - Simple, clean, and beautiful theme.
* [bureau-env](https://github.com/angus-lherrou/bureau-env) - Modification of the Oh-My-Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) theme that adds a Python virtual environment label to the left of the `git` block.
* [bureau-parrot](https://github.com/BenjaminGuzman/bureau-parrot) - 基于 [bureau](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme). Includes `git` decorations.
* [bureau](https://github.com/isqua/bureau) - A clear and informative two-lined prompt. Includes git status optimized for large repositories.
* [buster](https://github.com/grantbuster/buster_zsh_theme) - Plays well with WSL2. Based loosely on Fox and Jonathan themes from oh-my-zsh.
* [cactus](https://github.com/welksonramos/cactus) - 带有“git”状态装饰的极简主义主题.
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - 糖果主题的轻量版.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - Shows active Python version and `git` decorations in the prompt.
* [celestialorb](https://github.com/celestialorb/zsh-theme) - Powerline-inspired theme by @celestialorb. Includes `git` status decorations, Kubernetes cluster information (if any), current AWS profile and region, and  active virtualenv.
* [cf-ps1](https://github.com/mdan16/cf-ps1) - Displays the current foundation and organization and space of [Cloud Foundry](https://www.cloudfoundry.org/) in your prompt.
* [ch4rli3](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) - 精益和简单的主题.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme)  - 基于索林. 显示 Java、Scala、Go、Node、Python 和 Ruby 的当前活动版本.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme) - A tiny and beautiful theme for Oh-My-Zsh without anything superfluous. Includes `git` status decorations.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) - 优化的 ZSH 提示 [solarized](https://github.com/altercation/solarized) dark terminal theme.
* [chello](https://github.com/Abdalla981/chello) - Works well on dark backgrounds. Depends on [autojump](https://github.com/wting/autojump), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) and [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [chi](https://github.com/akinjide/chi) - A ZSH theme optimized for iTerm 2 users on macOS.
* [chill](https://github.com/JKerboeuf/chill.zsh-theme) - Has decorations for the current working directory, last command exit status and `git` status.
* [chinipage](https://github.com/andresemartinez/chinipage-zsh-theme) - Minimalist theme that includes `git` decorations. Requires powerline-compatible fonts and the [git-prompt](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git-prompt) plugin.
* [chrisandrew.cl](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme)  - 包括 `git` 装饰. 需要与电力线兼容的终端字体.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - Shows timestamp, large line breaks, git branch and status.
* [clarity](https://github.com/nbitmage/clarity.zsh) - Designed for for simpleness and extensibility.
* [classyTouchName](https://github.com/dylanroman03/classyTouchName) - Oh-my-zsh theme inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh). Works better with dark backgrounds. Includes `git` status decorations.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - Minimal, clean theme with `git` support.
* [clean (akz92)](https://github.com/akz92/clean) - 极简主义 ZSH 主题.
* [clean (brandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - A minimalist variant of [pure](https://github.com/sindresorhus/pure). Pure is not clean, clean is not pure.
* [clean (patr1ot)](https://github.com/Patr1ot/clean.zsh-theme) - 上游的分叉 [clean](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) with host information added.
* [cleansh](https://github.com/diegoos/cleansh) - Minimalist, includes `git`, Ruby, node and Python version status decorations. Works with standard fonts.
* [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) - minimalist theme with `git`, nix-shell and virtualenv status decorations.
* [cloudy](https://github.com/Huvik/Cloudy) - Minimal cloudy ZSH theme.
* [clover](https://github.com/tzing/clover.zsh-theme) - Inspired by [zeta](https://github.com/skylerlee/zeta-zsh-theme) and [pure](https://github.com/sindresorhus/pure).
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - Configuration file for [cmder](http://cmder.net/) configured to work in quake mode with ZSH and a modified [Agnoster](https://gist.github.com/agnoster/3712874) theme.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) - A ZSH theme that matches the theme of Cmder, a popular terminal emulator for windows.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) - Cobalt 2 theme with `git` extensions.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Codemachine theme.
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - Inspired by [bashi](https://github.com/eli-oat/bashi), includes a monkey and `git` information in your prompt.
* [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - Based on agnoster, but has a right-prompt for vi-mode that displays `--INSERT--` and `--NORMAL--`, in a powerline look.
* [coldark](https://github.com/ArmandPhilippot/coldark-zsh-theme)  - 为阅读舒适度而设计的蓝灰色主题. 包括 `git` 装饰.
* [collon](https://github.com/lambdalisue/collon.zsh)  - 带有“git”状态装饰、cwd、时间、主机、最后一个命令的退出状态的轻量级主题. 不需要特殊字体.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - Allows per-host prompt coloring, displays `rvm`, `virtualenv` and `git` information.
* [common](https://github.com/jackharrisonsherlock/common) - A simple, clean and minimal prompt, displays current working directory, hostname, AWS vault role, background jobs, current SHA, exit code of last command, and `git` branch and status.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - 针对深色背景优化的色彩鲜艳的主题。
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) - 干净有效的 ZSH 主题，支持 git 和 npm.
* [cramin](https://github.com/FelipeCRamos/craminzsh) - Minimal interface with support for github plugins, based on [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [cryo](https://github.com/cryocaustik/cryo-zsh-theme) - A standalone clone of the original oh-my-zsh theme with date and time added.
* [crème fraîche](https://github.com/koenwoortman/creme-fraiche-zsh-theme) - Works best with light terminal backgrounds, includes `git` and `vi`-mode status decorations.
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - A macOS oh-my-zsh shell theme with Cute emoji based on the Powerline Vim plugin.
* [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) - Works well on dark background, has `git` status decorations.
* [cypher-ruby](https://github.com/ston1x/cypher-ruby) - Similar to [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) but includes the active Ruby version.
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) 和 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) and the [agnoster](https://github.com/agnoster/agnoster-zsh-theme) theme in a container.
* [daily](https://github.com/ghlin/zsh-theme-daily) - Includes `git` and `ssh` status decorations.
* [damino](https://github.com/njdom24/Damino-Zsh-Theme) - 带有“git”装饰的最小电力线主题.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) - Informative, minimal, and, above all, X-Men themed.
* [daniloheraclio](https://github.com/daniloheraclio/daniloheraclio-zsh-theme) Inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题. 具有 `git` 和最后一个命令退出状态装饰. 需要 nerdfont 才能正确渲染.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - This version of the popular [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) theme has been enhanced with a near complete rewrite enabling modularity and a few new features.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - Based on the `ys` and [astro](https://github.com/iplaces/astro-zsh-theme) themes.
* [dbern](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) - Includes battery status and load average decorations.
* [delta (asavoy)](https://github.com/asavoy/delta-zsh-theme) - Minimal ZSH theme to reduce distractions. Includes an iTerm color settings file.
* [delta (dongri)](https://github.com/dongri/delta-zsh-theme) - 另一个带有嵌入式 `git` 状态的最小主题.
* [delta-prompt](https://github.com/cusxio/delta-prompt) - A minimal ZSH prompt.
* [destiny](https://github.com/ja1dan/Destiny) - A simple, configurable ZSH prompt with no dependencies. Destiny has been tested on Linux, macOS and iOS.
* [devj121](https://github.com/DevJ121/devj121-zsh-theme) - Includes `git` decorations with branch glyphs.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) - A theme with an emphasis on the right side (hence the name) of the terminal.
* [dino](https://github.com/OdilonDamasceno/dino-zsh-theme)  - 包括 node、golang、flutter、lua、python 和 java 的装饰，还包括 `git` 装饰. 需要书呆子字体.
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - Comes with custom LSCOLORS and LS_COLORS settings files, works with both dark and light terminal themes.
* [diy-ys](https://github.com/aprilnops/zsh-theme) - Variant of [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) without hostname or time.
* [dkniffin](https://github.com/dkniffin/zsh-theme) - Includes `ruby` version and `git` status.
* [dmx](https://github.com/domix/dmx.zsh-theme) - Optimized for dark terminal windows.
* [doodleshell](https://github.com/cdodd/doodleshell-zsh-theme) - Minimalist theme, includes `git`, `terraform` and `aws` status decorations.
* [dp](https://github.com/davidparsson/zsh-dp-theme) - Low contrast theme that shows current git branch, if the repository is dirty and the value of `$PYENV_VERSION`.
* [dr4kk0nnys_v2](https://github.com/Dr4kk0nnys/Dr4kk0nnys_theme_ohmyzsh_v2/) - 适用于深色背景，包括 `git` 状态装饰.
* [dracula](https://github.com/dracula/zsh) - Atom、Alfred、Chrome DevTools、iTerm 2、Sublime Text、Textmate、Terminal.app、Vim、Xcode 和 ZSH 的深色主题.
* [dragon (jeop10)](https://github.com/jeop10/dragon) - Inspired by kali linux. Includes `git` status and working directory decorations.
* [dragon (sabertaximi)](https://github.com/sabertazimi/dragon-zsh-theme) - Minimalistic, includes `git` status information.
* [drkat](https://github.com/katrinaalaimo/drkat-zsh-theme) - 让人联想到 [Powerline](https://github.com/powerline/powerline). Includes directory, `git` status, and hostname decorations.
* [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) variant.
* [dtheme](https://github.com/OlukaDenis/DTheme) - Optimized for people using a solarized terminal color scheme and `git`. Works best with a unicode font.
* [duckster](https://github.com/ducky/duckster) - A fork of the [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ZSH theme that's more ducky fresh.
* [ducula](https://github.com/janjoswig/Ducula)  - 受德古拉项目的启发. 包括 `git` 状态装饰、用户名和主机名缩写、虚拟环境、当前工作目录、最后一个命令的返回状态和时间.
* [dustmod](https://github.com/bmihaila/dustmod) - Derived from the [dst](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) theme in oh-my-zsh.
* [dzhi](https://github.com/pentago/dzhi-zsh-theme) - Optimized for people using [Nord](https://www.nordtheme.com/). Includes `git` status decorations.
* [eckig](https://github.com/fouladi/eckig)  - 带有 utf-8 图标的极简主义主题. 包括 `git` 状态装饰和时钟.
* [eggshausted](https://github.com/inutano/eggshausted) - 一个 `git`-aware 主题，适合那些厌倦了出错的人.
* [eivmosn](https://github.com/eivmosn/eivmosn-omz) - Trimmed down variant of `ys` theme.
* [eleastic](https://github.com/jinseobhong/eleastic-zsh-theme) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme), optimized for solarized terminal theme, includes `git` status decorations. Requires powerline-compatible font.
* [elessar](https://github.com/fjpalacios/elessar-theme) - A `git`-aware theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme). Requires a Powerline-compatible font.
* [elm](https://github.com/gacallea/elm-zsh-theme) - 包括 `git` 状态、user@host、日期、时间和路径装饰器.
* [elsa](https://github.com/faycito/elsa) - Includes root status, pwd and `git` status decorations.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - Emoji flavored [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ohmyzsh/ohmyzsh) theme.
* [emoji](https://github.com/masaakifuruki/emoji.zsh-theme) - 基于  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh theme with the `git` prompt symbols replaced with emoji for better clarity.
* [emojirussell](https://github.com/Bergiu/emojirussell) - 基于  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh theme, with status decorations for current working directory, last command exit status, `git` branch and status.
* [endless-dog](https://github.com/qwelyt/endless-dog) - 模仿 grml-zsh-config 的 oh-my-zsh 兼容主题.
* [enlightenment](https://github.com/w33tmaricich/enlightenment) - Includes decorations for `git` status, `vi`-mode indicator, and the time for last command to execute.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - Takes up an enormous amount of space in the terminal.
* [erfan](https://github.com/ekm507/erfan-zsh-theme) - 的组合 [af-magic](https://github.com/andyfleming/oh-my-zsh) and [macovsky](https://github.com/championswimmer/oh-my-zsh/blob/master/themes/macovsky.zsh-theme) themes. Includes `git` and `virtualenv` status decorations.
* [eriner](https://github.com/zimfw/eriner) - A Zim fork of the Powerline-inspired [agnoster](https://github.com/agnoster/agnoster-zsh-theme) prompt theme. Includes `git` status decorations.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - A simple theme with `git` information.
* [eucalyptus](https://github.com/relastle/eucalyptus) - Simple one-line theme for minimalist vi-mode users inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory and current path.
* [excess](https://github.com/davydovanton/excess.zsh-theme) - Simple ZSH color theme.
* [ez-pz](https://github.com/mangosmoothie/ez-pz) - Minimalist theme with `git` status decorations, inspired by [bureau](https://github.com/isqua/bureau).
* [fall](https://github.com/jottenlips/seasonal-zshthemes) - Minimalist theme with fall icons. Includes `git` status decorations.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) - Minimal ZSH prompt that works better on dark backgrounds.
* [fdT2K](https://github.com/FDT2k/FDT2K-theme)- 基于 [agnoster](https://github.com/agnoster/agnoster-zsh-theme), preset to include virtualenv, last command status, `nvm`, `docker machine` and `git`, `hg` and `bzr` status decorations.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme) - Clean, simple, compatible and meaningful. Tested on Linux, Unix and Windows under ANSI colors.
* [filthy](https://github.com/molovo/filthy) - A disgustingly clean ZSH prompt.
* [fish](https://github.com/Raniconduh/zshfish) - ZSH theme reminiscent of the default fish shell theme. Includes `git` status decorations.
* [fishy-lite](https://github.com/sudorook/fishy-lite) - 原叉 [fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy) theme in oh-my-zsh with much of the extraneous stuff cut out to improve load speeds. Includes a battery gauge and `git` status display that can be enabled on the right-hand side of the prompt.
* [fishy2](https://github.com/akinjide/fishy2) - ZSH theme inspired by [original fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy).
* [fluent-git](https://github.com/RobertKozak/fluent-git) - Displays time of last command execution, error code, hostname, username, `git` status, kubernetes cluster and namespace, path and ssh connection status.
* [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) - 自定义设置 [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status decorations.
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - Includes status of last command, `git` information and current directory.
* [frank](https://github.com/ronmackley/frank-theme) - Frank keeps to the point, displaying information compactly but readably on a single line. Frank keeps to the facts and only tells you extra things when they are important.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - 叉子 [terminal-party](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) theme.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - 基于的主题 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh-theme.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - Red version of the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) theme from oh-my-zsh.
* [fritz](https://github.com/fritzccc/fritz-zsh-theme)  - 适用于深色背景. 包括 `git` 状态装饰.
* [frlo](https://github.com/fiorillo/frlo) - 使用您计算机的主机名提出（希望）独特的三色主题以显示在您的提示中，以便您一眼就知道您登录的是哪台机器.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - 支持 `git` 和 `svn` 的彩色两行主题.
* [furio](https://github.com/hectorpalmatellez/furio-theme) - 叉子 [Cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) oh-my-zsh theme. with different colors and emojis.
* [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) - Colorful theme, works better on a dark background.
* [gaia](https://github.com/gcaracuel/gaia.zsh-theme) - 原来是一个叉子 [Bureau](https://github.com/isqua/bureau) adds new virtual environments info to the prompt: Kubernetess, virtualenv, rbenv and Java versions. Includes git status integration.
* [gal](https://github.com/x6r/gal) - gal 基于 [gallois](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme).
* [garden](https://github.com/fecat233/garden) - Works better with a dark terminal background, includes `git` status decorations.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto prompt with the information you need the moment you need it.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires `rvm` & `git` plugins.
* [gbt](https://github.com/jtyr/gbt)  - Go Bullet Train 是一个非常可定制的提示生成器，灵感来自 Bullet Train，运行速度更快. 包括许多不同状态的汽车.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - 将 oh-my-zsh gentoo 主题拆分为一个单独的 repo，供非 omz 用户使用.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) - Adds host info to the [geometry](https://github.com/geometry-zsh/geometry) theme.
* [geometry](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
* [ghoti](https://github.com/lonr/ghoti) - Mimics the `fish-shell` default prompt. Includes `git` decorations.
* [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) - Inspired by [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme), includes `git` decorations, IP address, host and path.
* [gimbo](https://github.com/gimbo/gimbo.zsh-theme) - A variant of [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) with more features, a little eye candy and context-sensitive extra lines. Includes `git` status decorations, history number, username/hostname context, directory status, status of last command if it failed, and the Python virtualenv name if present.
* [gimme](https://github.com/nralbrecht/gimmezsh) - A simplistic theme for ZSH with `git` integration. Inspired by the [gitsome](https://github.com/mtully/gitsome) theme.
* [girazz](https://github.com/mdentremont/girazz) - A modification to the gnzh theme which adds `vi` mode to the right prompt.
* [git-prompt (awgn)](https://github.com/awgn/git-prompt) - A fast `git` prompt for `bash`, `zsh` and `fish`.
* [git-prompt (olivierverdier)](https://github.com/olivierverdier/zsh-git-prompt)  - 显示有关当前 `git` 存储库的信息. 特别是分支名称、与远程分支的差异、暂存或更改的文件数等.
* [git-prompt (woefe)](https://github.com/woefe/git-prompt.zsh) - A fast, customizable, pure-shell, asynchronous Git prompt for ZSH heavily inspired by Olivier Verdier's [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) 和fish shell的“Informative VCS”提示非常相似.
* [git-prompt-kit](https://github.com/olets/git-prompt-kit) - A configurable set of components for creating feature rich, high performance Git-aware zsh prompts (aka themes) with minimal coding.
* [git-simple](https://github.com/ZakharEl/git-simple-theme) - Simple theme that includes detailed `git` status decorations.
* [gitsome](https://github.com/mtully/gitsome) - Super simple prompt with `git` info, optimized for the [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) 配色方案.
* [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) - Shows command and `git` status decorations.
* [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme)  - 在 `git` 存储库中时，它显示来自 `git` 存储库根文件夹的位置. 当不在 `git` repo 中时，它会显示相对于 home 的路径，`~`.
* [gitster (zimfw)](https://github.com/zimfw/gitster) - Zim fork of shashankmehta's [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) prompt theme
* [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) - Forked from the original [gitster](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) theme.
* [gk3000](https://github.com/gk3000/gk3000-oh-my-zsh-theme) - 包括 `git` 状态装饰和当前目录的完整路径.
* [glimmer](https://github.com/martnu/glimmer) - Includes `git` branch, time and user@host.
* [gndx](https://github.com/gndx/gndx-zsh-theme) - Includes `git` status, hostname, directory and last command exit status decorations.
* [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) - Customization of [gnzh.zsh-theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) from oh-my-zsh.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) - Theme for iTerm 2 and ZSH, includes `git` decorations, user@host, path and date.
* [gops](https://github.com/noxer/gops)  - 快速类似电力线的提示. 包括 `git` 状态、当前目录、根状态装饰.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - Simple yet informative theme that includes `git` decorations and the return status of the last command.
* [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) - 极简主义，包括 `git` 状态装饰.
* [grs](https://github.com/gersontpc/zsh-theme-grs) - Includes `git` status decorations, user id and working directory.
* [gruvbox (hgaiser)](https://github.com/hgaiser/gruvbox-zsh) - Sets colors from the [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [gruvbox (sbugzu)](https://github.com/sbugzu/gruvbox-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874), uses the same colors from the [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [guezwhoz](https://github.com/guesswhozzz/guezwhoz-zshell) - 极简主义，包括 `git` 状态装饰.
* [guri](https://github.com/victorfsf/guri) - A Simple and fast Oh-My-Zsh theme, based on [Pure](https://github.com/sindresorhus/pure)的设计.
* [hackersaurus](https://github.com/bhilburn/hackersaurus) - A theme with `git` status and exit code of last command run embedded in the prompt. Related to [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [halil](https://github.com/5m0k3r/zsh-themes) - Fork of oh-my-zsh's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) theme.
* [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme)  - 一个简单的主题，第一个字符是花（hana），即花的汉字. 这个主题的灵感来自一个名为 DSA Hana 的键帽集. 这与 [hana atom](https://github.com/arturoalviar/hana-matcha-syntax) theme. Includes `git` status decorations.
* [handy](https://github.com/hanleylee/handy) <i>- Colorful and lightweight theme.</i> <b>- 多彩和轻量级的主题。</b> <i>Shows root status, `git` status, current directory and `user@hostname` decorations.</i><b>显示 root 状态、`git` 状态、当前目录和 `user@hostname` 装饰。</b>
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) - Shows `git` branch and status, last command exit code, last command execution time if more than `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`.
* [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) - Based on oxide, includes `git` status decorations and current user/host information.
* [haribo](https://github.com/haribo/omz-haribo-theme) - 简单的 `git` 状态 + 提示中的时间戳.
* [hcompact](https://github.com/fusion809/zsh-theme) - Displays time, OS (including distro if on Linux), directory and whether running as root.
* [headline](https://github.com/Moarram/headline-zsh-theme) - A responsive ZSH theme featuring Git status information and a colored line above the prompt.
* [heart](https://github.com/gko/heart) - Heart themed prompt for light backgrounds.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - 简单、严肃和干净，支持 `git` 和返回码.
* [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - 基于 [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau), with added `git` status decorations and `npm` status.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hematite](https://github.com/bigdave/hematite) - Minimalist promot that tries to show only the status decorations that are actively useful at a given time.
* [hexagon](https://github.com/diogoazevedos/hexagon) - Minimalist zsh theme based on [geometry](https://github.com/geometry-zsh/geometry).
* [hfulldate](https://github.com/fusion809/zsh-theme) - Displays time, date, OS (including distro if on Linux), directory and whether running as root.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - Inspired by robbyrussell theme + ssh connection status prompt.
* [hina](https://github.com/ucpr/hina) - 用 `golang` 编写，包括 `git` 状态装饰和 kubernetes 上下文.
* [hip-fellow](https://github.com/haitaim/hip-fellow) - 包括 `git` 状态装饰并使用标准字体.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - A variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [home](https://github.com/sheerun/home) - Pretty and short one-line theme that makes you feel at home.
* [hometown](https://github.com/olets/hometown-prompt) - A feature rich, high performance `git`-aware ZSH theme with segments for the user, host, time, the current working directory and its parent, and detailed full Git status within a Git repo.
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - Honukai theme and colors for oh-my-zsh and iTerm 2.
* [horizontal](https://github.com/nuimk/horizontal) - Two line prompt with a horizontal separator.
* [hornix](https://github.com/fusion809/zsh-theme) - Displays time & date, OS (including distro if on Linux), directory and whether running as root.
* [horse-sh](https://github.com/emileswarts/horse-sh) - A very minimal brown/red ZSH theme.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - Simple and clean, includes the return code of the last command executed.
* [hug](https://github.com/xxninjabunnyxx/hug-zsh) <i>- When you&#39;re working and need a hug.</i> <b>- 当你工作并需要一个拥抱时。</b> <i>Includes `git` status.</i><b>包括 `git` 状态。</b>
* [humbled](https://github.com/saravanabalagi/zsh-theme-humbled) - A clean and humble theme with support for `condaenv`, `virtualenv` and `git` status decorations left aligned with the working directory in bold.
* [hydrogen](https://github.com/xylous/hydrogen) - A simple multiline zsh theme. It shows username, hostname, current directory and `git` status decorations.
* [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) - Designed to work with the hyper terminal theme, includes `git` status decorations.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) - Gives you a comprehensive overview of the branch you're working on and the status of your repository without cluttering your terminal.
* [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX) - Modified iGeek theme. Works with macOS out-of the box, includes `git` status decorations.
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - Works well on a dark background.
* [ice](https://github.com/Lenart12/ice.zsh-theme) - 非常轻微的修改 [bureau](https://github.com/isqua/bureau) theme combined with [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [icicle](https://github.com/JamesConlan96/Icicle) - Includes `git` status decorations, and whether running as root.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) - 一个超级快乐的电力线风格，`git`-aware **prezto only** 主题.
* [igorsilva](https://github.com/igor9silva/zsh-theme) - 显示当前目录、可自定义的分隔符、当前分支、`git` 状态.
* [iguanidae](https://github.com/btd1337/iguanidae-zsh-theme) - 包括 `git`、`nvm` 和 `venv` 装饰.
* [illusion](https://github.com/shabane/illusion) - Includes username, current working directory, `git` status and last command status decorators.
* [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) - 叉子 [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) with spacing improvements and an updated icon. Includes `git` status information.
* [imp](https://github.com/igormp/Imp) - 基于 [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) 并针对深色背景进行了优化.
* [infernus](https://github.com/jshiell/infernus-zsh-theme) - Minimalist theme, better on dark backgrounds.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) - 显示“git”状态、后台作业、远程主机和其他信息的清洁主题.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - An extension of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme to use powerline fonts.
* [itg](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy's theme.
* [ivy](https://github.com/ivyhjk/ohmyzsh-theme-ivy) - Works well on dark backgrounds. Includes user@host, `git` status and time decorators. Based on the [obraun](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#obraun) theme.
* [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme)  - 基于精致和 ys 主题，包括 `git` 状态装饰. 包括一个可选的 iterm2 颜色方案.
* [jake](https://github.com/JakeHuneau/Jake.zsh-theme) - 如果分支有未推送的更改，则显示时间、当前目录和 `git` 分支信息，包括分支名称和红色 +.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - Optimized for dark backgrounds, includes `git` status and `rvm` status.
* [jc](https://github.com/jclementex/jc-zsh-theme) - For dark terminal backgrounds, includes `git` status information.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - Loosely based on the ys theme.
* [jerome](https://github.com/jeromescuggs/jerome-theme) - 基于的多彩主题 [dieter](https://github.com/jeromescuggs/jerome-theme) theme, but with a yellow hostname. Includes `git` decorations.
* [jhleeeme](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) - Includes `git` and python virtualenv status decorations, user, pwd,time and system name.
* [jon](https://github.com/Jon-Schneider/jon.zsh-theme) - A simplified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) with the colors of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - Inspired by [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme), includes `git` status.
* [jovial](https://github.com/zthxxx/jovial) - Shows host, user, path, development environment, `git` branch, which python venv is active.
* [jpegleg](https://github.com/jpegleg/zshrc) - Similar to dark blood theme, includes timestamp and `git` decorations.
* [js-magic](https://github.com/JSextonn/js-magic) - 简化版 [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme). Includes current working directory and `git` status decorations.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
* [just-another](https://github.com/supertassu/another-theme) - Just another theme, with hostname when you're sshed to another machine.
* [just-around-the-corner](https://github.com/DevinLeamy/just-around-the-corner) - Counts down the days until Christmas. Includes `git` status decorations.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter) - Powerline-style theme with `git`, `svn`, `npm`, `rvm` and network awareness. Requires Powerline-compatible terminal font.
* [jyumpp](https://github.com/Jyumpp/jyumpp-zsh-theme) - Configuration file and installer for Powerlevel 10K.
* [kali](https://github.com/h4ck3r0/kali-theme) - Includes `git` decorations.
* [karu](https://github.com/zaari/karu) - 极简单行 ZSH 提示.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) - 包含其他主题的一些功能的主题.
* [kenton](https://github.com/notnek/zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) - Colorful theme, includes iTerm 2 color schemes.
* [kgzsh](https://github.com/Kashugoyal/kgzsh) - 包括`git`状态deorations，适用于较暗的背景.
* [kido](https://github.com/KidoThunder/kido-zsh-theme) - Based on `ys` and `robbyrussell` themes. Includes decorators for the exit code of the last command run, python virtualenv and VCS status.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - Based on Fishy theme, but shows full paths instead of abbreviated directories and only shows user@machine in `ssh` sessions and docker containers.
* [kirkdawson](https://github.com/kdawson133/KirkDawson) - Powerline-inspired. Includes prompt decorations for `git` status, last command exit status, user@hostname, working directory and whether the user is running as root.
* [kiss](https://github.com/rileytwo/kiss) - Simple theme for oh-my-zsh, VSCode, iTerm2, Neovim, and RStudio. Includes `git` status decorations.
* [kketcham](https://github.com/prototype27/kketcham) - Theme with nifty colors on the `git` info.
* [klassiker](https://github.com/mrdotx/zsh-theme) - Very minimal theme with `git` decorations.
* [korittg](https://github.com/dkorittki/korittg-zsh-theme) - Minimalistic but informative. Includes decorations for `git` status, current directory and the `kubectl` context and namespace.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme) - Best for dark backgrounds. Includes `git` status decorations.
* [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - 为深色终端设计的两行主题，具有 `git` 装饰.
* [krak3n](https://github.com/krak3n/zsh-theme) - Shows golang version and the current `git` branch.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) - A dark theme for ZSH.
* [kube](https://github.com/tigerjz32/kube-zsh-theme) - 基于 [macos-terminal](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal), includes `kubectl` context. Has time, directory, and `git` status decorations.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme)  - Agnoster 前叉针对日晒终端进行了优化. 需要与电力线兼容的字体.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) - Colorful theme with `git` and `hg` status information, ability to add host-specific colors to hostname.
* [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme) - A simple theme with the first character being 九(kyuu), the number 9. The primary color is blue with a magenta accent. Includes `git` status decorations.
* [lagune](https://github.com/noplay/lagune) - A minimal ZSH theme.
* [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) - 灵感来自 robbyrussell [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) theme. Includes `git` status decorations.
* [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) - 为使用 unicode 兼容字体和终端应用程序的 `git` 用户优化的 ZSH 主题.
* [lambda-blazinggit](https://github.com/zalefin/lambda-blazinggit) - Includes blazing fast, detailed `git` information. Requires Nerd Fonts and the [gitstatus](https://github.com/romkatv/gitstatus) plugin.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - Minimalist prompt that includes `git` information.
* [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) - Simple theme based on lambda with `git` status and virtualenv information.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - A simple ZSH theme, optimized for `git` usage.
* [lambda-p](https://github.com/paimanbandi/lambda-p) - Inspired by the [lambda mod](https://github.com/halfo/lambda-mod-zsh-theme) and [Lambda V](https://github.com/vkaracic/lambdav-zsh-theme) themes. Includes `git` status decorations.
* [lambda-pure](https://github.com/marszall87/lambda-pure) - A minimal ZSH theme, based on Pure, with added NodeJS version.
* [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) - A combination of the Lambda and Fishy themes, includes `git` status decorations.
* [lambda-zen](https://github.com/seamile/lambda-zen) - inspired by [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) with graphical `git` status decorations.
* [lambder](https://github.com/avillen/zsh-theme-lambder) - Includes `git` status decorations, works best with a dark terminal theme.
* [laniksj](https://github.com/LanikSJ/laniksj-zsh-theme)  - 在深色背景下效果最佳. 基于伟大的`ys`主题和 [Honukai ZSH Theme](https://github.com/oskarkrawczyk/honukai-iterm-zsh). Shows root status and `git` status decorations.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - Optimized for dark terminals, has variants for local and remote systems.
* [leafia](https://github.com/Ghostrick/leafia-prompt) - 显示 `git` 状态信息的多叶 prezto 主题.
* [lean](https://github.com/miekg/lean) - Inspired by [pure](https://github.com/sindresorhus/pure). Includes `git` status and background job decorations.
* [lemon](https://github.com/carlosvitr/lemon_zsh)  - 许多美丽的颜色供您欣赏. 小心和耐心地完成. 包括 `git` 状态和 ruby​​ 版本装饰.
* [leon](https://github.com/prince-an/Leon_zshTheme)  - 在浅色背景下效果很好. 包括 `git` 状态、时间、用户名@主机、工作目录和最后一个命令退出状态装饰.
* [leverage](https://github.com/gschnall/leverage) - 基于 [minimal](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme), uses colors, and an extra `¬` character, to better distinguish the command line prompt from your output.
* [lewis](https://github.com/lewisflude/oh-my-lewis) - Black, white and red theme. Shows `git` status information.
* [lightbulb](https://github.com/lightbulb703/lightbulb-zsh-theme) - 包括内核、操作系统版本、正常运行时间和 `git` 的装饰.
* [lighthaus](https://github.com/lighthaus-theme/zsh) - A prompt that compliments the [Lighthaus](https://github.com/lighthaus-theme/lighthaus) theme. Shows `git` information, github/gitlab logo and shows changes as and when they occur.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) - 极简主义主题，最适合深色终端背景.
* [lilith](https://github.com/aknackd/zsh-themes) - Modification of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) and [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [lime](https://github.com/yous/lime) - Simple and easily customizable ZSH theme.
* [limpide](https://github.com/shooteram/limpide) - Modified version of [miloshadzic](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) 显示父目录和当前目录的主题.
* [linuxer](https://github.com/patrick330602/linuxer) - Inspired by Yaris Alex Gutierrez's [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh), Yad Smood's `ys`, and the [Bureau](https://github.com/isqua/bureau) theme.
* [linuxero](https://github.com/andreshincapier/linuxero) - Minimalist. Includes decorations for root status, current directory, `git` status, current ruby rvm environment and current python virtualenv.
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt with useful information when you need it. It shows you what you need when you need it. You will notice what changes when it changes, saving time and frustration.
* [lish](https://github.com/bashelled/lish)  - 一个休闲的主题. 没有粗糙，只有光滑. 包括 `git`、user@host、最后一个命令退出状态、当前目录、当前时间和根状态装饰器.
* [liver](https://github.com/RenoirTan/liver.zsh-theme) - Colorful, includes `git` status, user, host, current and relative path to the current repository root decorations.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) - 挑剔的美洲驼使用的极简主义主题.
* [logico](https://github.com/logico/logico-zsh-theme) - Has `git` decorations. Shows remote status and indicator for vi-mode.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - Texas-themed theme based on Sindre Sorhus' pure theme.
* [longsilvern](https://github.com/long263/longsilvern-zsh-theme) - Includes `git` and compact `pwd` decorations.
* [lorond](https://github.com/lorond/zsh-lorond/) - 精简版 [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme). Includes `git` status, works with standard fonts.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme) - Variant of lambda-mod theme. Has `git` decorations, requires a powerline-compatible terminal font.
* [luke](https://github.com/xueguangl23/luke_zsh_theme) - Includes `git` decorations. Based on the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) 哦，我的 zsh 主题.
* [lukerandall-extended](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) - Extended version of the [lukerandall](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) theme. Includes decorations for `git` status and the status of the last command run.
* [lunachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/lunachar.zsh-theme) - Minimalist theme.
* [macos](https://github.com/alejandromume/macos-zsh-theme) - Includes `git` status decorations.
* [mad](https://github.com/MartinWie/ohmyzsh-theme-mad) - 包括 `git` 状态和最后命令执行时间装饰.
* [magicmace](https://github.com/zimfw/magicmace) - Inspired by xero's ZSH prompt and [eriner's prompt](https://github.com/zimfw/eriner). Includes status codes for active python `venv`, exit status of last command, shortened working directory, `git` status decorations.
* [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN's magico theme.
* [maivana](https://github.com/nylo-andry/zsh-themes) - 包括 `kubectl` 上下文，`git` 状态装饰.
* [materialshell](https://github.com/carloscuesta/materialshell) - A [material design](https://material.io/guidelines/style/color.html) theme for your shell with a good contrast and color pops at the important parts. Designed to be easy on the eyes.
* [matrix](https://github.com/pot-code/matrix-zsh-theme) - Variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) styled to look like something in the Matrix movie trilogy. Includes `git` status decorations.
* [matter](https://github.com/mrobillard/matter-zsh-theme) - Shows `git` status, AWS vault role, background jobs, exit code of last command & hostname.
* [mau](https://github.com/vichargrave/mau)  - 带有猫扭曲的 ZSH 主题. 包括 `git` 状态装饰. 基于 [kphoen](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kphoen.zsh-theme) and [smt](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/smt.zsh-theme) themes.
* [mbolis](https://github.com/mbolis/mbolis-zsh-theme) - 包括 `git` 装饰，如果是 root 用户，则更改提示颜色，活动作业和 [jenv](https://github.com/jenv/jenv) integration.
* [mdmini](https://github.com/MarioDena/MDmini) - Includes `git` and `ssh` status decorations.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character. Requires the [hooks](https://github.com/willghatch/zsh-hooks) plugin.
* [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) - 包括 `git` 状态装饰，如果非零则显示最后一个命令的退出代码.
* [mexassi](https://github.com/Mexassi/mexassi-zsh-theme) - Checks the `/sys/class/power_supply` folders to determine if the system is installed on a laptop or desktop machine. Reads the battery percentage grepping acpi command and displays it in the prompt. Includes `git` decorations.
* [mh-fzj](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) - Includes `rvm` and `git` status decorations.
* [michaelpass](https://github.com/michaelpass/michaelpass.zsh-theme) - POSIX-friendly cross-platform [alanpeabody](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) mod w/ convenient timestamps and full git/ruby support.
* [midin](https://github.com/xlshiz/midin) - Works well on dark terminal background, includes `git` status decorations.
* [mike-was-here](https://github.com/leguim-repo/mike-was-here-theme/) - 极简主义，包括 `git` 状态装饰.
* [milight](https://github.com/frodoslaw/milight-zsh) - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
* [min](https://github.com/andrepolischuk/min) - A minimalistic ZSH prompt.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind.
* [mini-simple](https://github.com/ysl2/mini-simple-zsh-prompt) - Minimalist. Includes `vcs` status decorations.
* [minima (Brolly0204)](https://github.com/Brolly0204/zsh-minima) - Includes `git`, `node`, `golang`, `yarn`, `php`, `docker` and `python` status decorations.
* [minima (ednikolenko)](https://github.com/ednikolenko/minima) - A minimal ZSH theme with `git`, `docker`, `go`, `node`, `npm`, `python` and other indicators. Uses unicode characters for some markers.
* [minimal (5amu)](https://github.com/5amu/minimal-prompt) - Minimal prompt, uses nerdfonts. Includes `git` and `vpn` status decorations.
* [minimal (casalinovalerio)](https://github.com/casalinovalerio/minimal-prompt) - Minimal prompt, includes `git` and vpn status decorations.
* [minimal (glsorre)](https://github.com/glsorre/minimal/) - 最小的异步 ZSH 主题优化用于 [Fira Code](https://github.com/tonsky/FiraCode) font and the [Solarized Light](https://ethanschoonover.com/solarized) terminal theme.
* [minimal (subnixr)](https://github.com/subnixr/minimal) - Minimal yet feature-rich theme.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) - Theme for dark terminals, includes `git` decorations in the right-side prompt.
* [minimal2](https://github.com/PatTheMav/minimal2) - A minimal and extensible ZSH theme. Forked from [subnixr's original](https://github.com/subnixr/minimal) and adapted for [Zimfw](https://github.com/zimfw/zimfw).
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) - 灵感来自 oh-my-zsh 的 kolo 主题.
* [mira](https://github.com/mbStavola/mira) - A modified [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) 带有时间信息和简化的开始提示.
* [mirage](https://github.com/robin-pfeiffer/ohmyzsh-mirage-theme/) - Includes prompt decorations for `git` status, last command exit code, whether `sudo` timestamp file is present and current active Python virtual environment.
* [miramare](https://github.com/franbach/oh-my-deepin-miramare) - Includes `git` status decorations. Works best with [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
* [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs' ZSH theme.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - 针对深色背景进行了优化.
* [mnml](https://github.com/mnml-theme/prompt) - Minimal theme with `git` status decorations.
* [mochi2](https://github.com/mochidaz/zsh-themes) - Minimalist theme. Includes `git` and `hg` status decorations.
* [mochi](https://github.com/mochidaz/zsh-themes) - Simple theme, designed to resemble rust main function. Includes `git` and `hg` status decorations.
* [moderno](https://github.com/obrassard/moderno-zsh) - A simple and modern ZSH theme inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme from Oh-My-ZSH. Includes `git` status decorations.
* [modesty](https://github.com/saravanabalagi/zsh-theme-modesty) - A clean and modest ZSH theme with `condaenv`, `virtualenv` and `git` status decorations displayed neatly right aligned.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874).
* [momoyo](https://github.com/momoyo-droid/momoyo-zsh-theme) - Reminiscent of powerline. Includes decorations for `git` status, username, and working directory.
* [moonline](https://github.com/kagamilove0707/moonline.zsh) - 最小但易于扩展的提示.
* [moux](https://github.com/gagbo/moux) - Works well with a dark terminal background, includes `git` decorations in `RPROMPT`.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - Provides useful information (in your prompt) about the repository that you are in. It currently works for [Git](https://git-scm.com/) and [Mercurial](https://www.mercurial-scm.org/), under [ZSH](https://en.wikipedia.org/wiki/Zsh) as well as [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [multiline](https://github.com/jan-auer/zsh-multiline) - 基于电力线风格的主题 [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [muslim](https://github.com/nksoff/muslim) - 一个简单的最小 ZSH 提示主题.
* [musy](https://github.com/THaGKI9/musy-zsh-theme) - Inspured by muse theme. Includes `git` status decorations.
* [my-hl2](https://github.com/liamm91/my-hl2) - Includes virtualenv, `git` status and directory decorations. Based on omz's [half-life](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/half-life.zsh-theme) theme.
* [myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia's myzsh theme.
* [mzt](https://github.com/honbey/mzt) - 设置`LS_COLORS`，着色`diff`并包括`git`状态和当前工作目录装饰.
* [nanofish](https://github.com/tweekmonster/nanofish) - Adds fish-style directory prompt to nanotech theme.
* [nbrylevv](https://github.com/nbrylevv/nbrylevv-zsh-theme) - 带有文本“git”状态装饰的极简主义主题.
* [nctu](https://github.com/leovincentseles/nctu.zsh-theme) - Lightweight theme with an emphasis on speed. Includes `git` status decorations.
* [neewbie](https://github.com/neewbee/neewbee.zsh-theme) - Minimal theme with `git` decorations. Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell).
* [neon-potato](https://github.com/algosuna/neon-potato) - Colorful and minimalist theme. Includes `git` decorations.
* [neon](https://github.com/sahariko/neon) - A pretty and minimal ZSH theme with `git` decorations.
* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - 带有书呆子字体的 ZSH 提示主题.
* [nescalante](https://github.com/nescalante/zsh-theme) - Optimized for dark terminal backgrounds, includes `git` decorations.
* [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) - 包括 `git` 装饰和 `vi` 模式指示器.
* [newt](https://github.com/softmoth/zsh-prompt-newt) - Fat & fast theme – beautiful inside and out, styled segments done right. Extremely customizable, includes `git`, username, execution time, directory, background jobs and edit mode decorations.
* [newton](https://github.com/sebastienfilion/zsh.newton) - Includes `git` status and external IP address decorations.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - A very basic theme which just features an macOS bike icon.
* [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - Colorful, shows `git` status decorations.
* [nikitakot](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme) - Small and simple oh-my-zsh theme. Shows current directory and 2 directories behind, `git` and `nodejs` status decorations.
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - Based on af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - 一个简单的 oh-my-zsh 主题.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - Minimalist ZSH theme with `git` status decorations.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) - oh-my-zsh's node theme, broken out to make it easier to use with other plugin managers.
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - Based on the ys theme, with added NodeJS version (from NVM plugin).
* [noon](https://github.com/silky/noon.zsh-theme) - Has light and dark variants, shows `git` information.
* [nord](https://github.com/TyWR/Nord-zsh) - Includes `git` status decorations and displays the active conda environment.
* [normanius](https://github.com/normanius/normanius-zsh-theme) - Derived from [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [nothing](https://github.com/eendroroy/nothing) - Lightning fast and really simple because it has almost nothing in it.
* [nox](https://github.com/kbrsh/nox) - Dark theme, displays the current working directory and git status.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme) - A clean, distraction free and `git` focused development theme. Shows path relative to `git` root (or ~ when outside `git` repo), time since last commit, current SHA, branch and branch state.
* [nunorc](https://github.com/nunorc/nunorc.zsh-theme)  - 极简主义主题，适用于深色背景. 包括 `git`、`mercurial` 和 `svn` satus 装饰.
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - prezto 和 oh-my-zsh 的简单主题.
* [nuts](https://github.com/rafaelsq/nuts.zsh-theme) - Minimalist theme, includes `git` status decorations and time.
* [oblong](https://github.com/Ansimorph/oblong) - Simple `bash`-inspired theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [basher](https://gitlab.com/Spriithy/basher). Includes status decorations to show if user is root, the exit status of last command run, `git` branch and its clean/dirty status.
* [odie](https://github.com/masterodie/zsh-theme-odie/) - Works well on a dark background. Includes `git` status, python virtualenv and `vi`-mode status decorations.
* [odin](https://github.com/tylerreckart/odin) - Odin is a `git`-flavored ZSH theme.
* [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) - Multiline theme with `git` decorations.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - 对 bash 和 ZSH 的自以为是的提示.
* [oh-my-posh](https://ohmyposh.dev/) - Not ZSH-specific, but very nice and works with ZSH. Allows you to use the same configuration for prompts in all shells.
* [oh-my-via](https://github.com/badouralix/oh-my-via) - ZSH 的主题，主要分叉威盛服务器上使用的历史主题.
* [ohmypc](https://github.com/joselpadronc/OhMyPC) - Works well with dark terminal windows. Includes `git` decorations.
* [om](https://github.com/sirshikher/zsh-om) - Minimal theme, works with dark backgrounds, includes `git` status decorations.
* [omszt](https://github.com/MU001999/omszt) - 带有 `git` 装饰的极简主义主题。
* [omuse](https://github.com/ouuan/omuse-zsh-theme) - Based on Oh-My-ZSH's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) . 具有 `git` 状态、时间、绝对密码、RAM 使用量、最后一个命令使用的时间和最后一个命令退出状态的装饰.
* [owczarczak](https://github.com/ThemysciraData/owczarczak.zsh-theme)  - 灵感来自比拉、节食者和菲诺时间. 包括 `venv` 和 vcs 状态装饰.
* [owi](https://github.com/owitech/zsh-theme/) - 带有“git”状态装饰的极简主义主题.
* [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) - Includes `git` status and virtualenv information.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - A Minimalistic and Dark ZSH theme.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme) 🌏 OZ0NO - Let's Breathe a clean ZSH.
* [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) - 一个主题 [powerlevel10k](https://github.com/romkatv/powerlevel10k) prompt that puts an emphasis on simplcity while still getting important information across.
* [pad](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme.
* [page](https://github.com/SLIB53/page-zsh-theme)  - 一个带有 VCS 支持的简单主题. 提示显示当前工作目录的 1 级、分支和一个颜色编码的弯曲粗箭头.
* [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) - Allows display of host information, includes `git` branch decoration.
* [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) - Shows detailed `git` status information with icons in the prompt.
* [panda](https://github.com/davymai/oh-my-zsh-panda-theme) - Includes `git` and `root` status decorations. Best on a dark background.
* [papercolor](https://github.com/erikschreier/PaperColor-themes) - Color scheme for ZSH, `vim` and `tmux`. Includes `git` status decorations.
* [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) - Includes `git` status decorations, command run time in milliseconds. Requires coreutils on macOS.
* [pastel](https://github.com/iboyperson/pastel) - A ZSH theme inspired by [sugar-free](https://github.com/cbrock/sugar-free). Includes `git` decorations.
* [pecodez](https://github.com/pecodez/pecodez-zsh-theme) - Optimized for dark terminals. Has decorators for `snyk` version, `node` version, AWS profile, kubernetes context and `git` status.
* [pentesters](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) - Modified version of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) 渗透测试者的主题，其中包括渗透测试日志记录的日期、时间和 IP 地址.
* [persi](https://github.com/persiliao/persi-zsh-theme) - Includes `git` decorations. Works with both light and dark backgrounds.
* [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) - Minimal theme in the spirit of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and Pure Shell themes.
* [phantomk](https://github.com/phantomk/phantomk.zsh-theme) - Colorful theme, includes go version, node version and `git` status.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - A clean and simple theme for ZSH inspired and forked from the [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) theme.
* [pi](https://github.com/tobyjamesthomas/pi) - A minimalist theme with `git` status decorations.
* [piboy](https://github.com/sflems/piboy-zsh-theme) - A simple and elegant multi-line theme for ZSH. Includes a colourized timestamp, `git` & syntax highlighting, and elevated root theme.
* [plain-ui](https://github.com/purveshpatel511/plain-ui) - Minimalist, but includes `git` status decorations.
* [plain](https://github.com/jimeh/plain.zsh-theme) - A plain and simple theme for ZSH which shows basic `git` information.
* [planet](https://github.com/borb/planet-zsh) - 精简版 [steef](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) 从 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) - Simple, no-frills theme.
* [plantyhoe](https://github.com/totoroot/plantyhoe.zsh-theme) - Minimalist theme based on a love of plants and apples. Includes `git` status decorations.
* [platypus](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) - Shows working directory, the return status of the last command, and `git` current branch.
* [polyglot](https://github.com/agkozak/polyglot) - a dynamic prompt for `zsh`, `bash`, `ksh93`, `mksh`, `pdksh`, `dash`, and busybox `ash` that uses basic ASCII symbols (and color, when possible) to show username, whether it is a local or remote `ssh` sesssion, abbreviated path, `git` branch and status, exit status of last command if non-zero, any virtual environment created with `virtualenv`, `venv`, `pipenv`, `poetry`, or `conda`.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM's basic oh-my-zsh custom theme.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - Programmer's theme with `git` status, ruby version and project path.
* [powerbash](https://github.com/erikschreier/powerbash-zsh) - Works well with dark terminal backgrounds, includes `git` status decorations.
* [powerless](https://github.com/martinrotter/powerless) - 受电力线启发的小而简单的纯 ZSH 提示.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - A fast reimplementation of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ZSH theme. Can be used as a drop-in replacement for powerlevel9k, when given the same configuration options it will generate the same prompt, only faster.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k is a theme for ZSH which uses [Powerline Fonts](https://github.com/powerline/fonts). It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen), and [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 附加组件 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - 两线版本的电力线：一根用于信息，一根用于输入.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) - Another take on a powerline theme. Nicely configurable, but requires at least a 256 color-capable terminal with a powerline-compatible terminal font.
* [powerline (syui)](https://github.com/syui/powerline.zsh) - 一个 `git` 感知电力线主题.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
* [powerline-go](https://github.com/justjanne/powerline-go) - A beautiful and useful low-latency prompt, written in golang. Includes `git` and `hg` status decorations, exit status of the last command run, current Python virtualenv, whether you're in a [nix](https://nixos.org/) 外壳，并且易于扩展。
* [powerline-hs](https://github.com/rdnetto/powerline-hs) - A [Powerline](https://github.com/powerline/powerline) 用 Haskell 编写的克隆. 它比原始实现要快得多，并且使 shell 的响应速度明显更快.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - Created in Ruby, uses powerline characters to simulate pills with useful information.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell) - Beautiful and useful prompt generator for Bash, ZSH, Fish, and tcsh. Includes `git`, `svn`, `fossil` and `hg` decorations, Python virtualenv information, and last command exit status.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - A [powerline](https://github.com/Lokaltog/vim-powerline) - 类似于 Bash、ZSH 和 Fish 的提示. 显示有关 git/svn/hg/fossil 分支的重要详细信息，并且易于自定义/扩展.
* [powerline-train](https://github.com/sherubthakur/powerline-train) - A powerline variant.
* [powerline](https://github.com/carlcarl/powerline-zsh) - A [Powerline](https://github.com/Lokaltog/vim-powerline)-like prompt, based on [powerline-bash](https://github.com/milkbikis/powerline-bash). Displays virtualenv, `git` status information and the exit code of the last command run.
* [powerzeesh](https://github.com/sevaho/Powerzeesh)  - 基于电力线的 ZSH 主题. 它旨在简化，仅在相关时显示信息，并针对速度和外观进行了优化. 灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) - Sublime Text、Terminal、iTerm 2 和 ZSH 的主题集合.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) - Theme optimized for dark terminal themes.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - oh-my-zsh 的云提示的 Prezto 端口.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda theme (for prezto).
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
* [probe](https://github.com/probe2k/probe_zsh) - Includes `git` status decorations.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - 一个相当重量级的 ZSH 提示，基于流行的同名 `vim` 插件的电力线字体，适用于深色背景.
* [prompt](https://github.com/nathanblair/prompt) - A lightweight prompt consistent across `sh`, `dash`, `ash`, `zsh`, and `pwsh`. Includes `git` status decorations.
* [prompt_j2](https://github.com/malinoskj2/prompt_j2) - Has a dynamic exit status indicator, can change to two lines dynamically to display context.
* [promptus](https://github.com/willeccles/promptus) - Simple, minimalist and configurable shell prompt program in C which can be used to make your prompt the same on any shell. Includes exit code and working directory decorations.
* [pronto](https://github.com/jthat/zsh-pronto) - 带有“git”装饰和时间信息的简单快速的主题.
* [ps1.py](https://github.com/jwodder/ps1.py) - Has `git` status, truncated directory, `chroot` and `virtualenv` prompt decorations.
* [pskfyi](https://github.com/pskfyi/zsh-theme) - 基于 [lambda](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#lambda). Themed for ubuntu but easily tweaked.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - Easily customizable, influenced by [spaceship](https://github.com/denysdovhan/spaceship-prompt).
* [pure-agnoster](https://github.com/yourfin/pure-agnoster) - Mashup of pure and agnoster. Has `git` decorations and works well with both dark and light terminal backgrounds.
* [pure](https://github.com/sindresorhus/pure) - A pretty, minimal and fast ZSH prompt. Includes `git` status decorations, prompt turns red if last command failed, username and host decorations when in a remote session or container, and current folder and command when a process is running.
* [purify (banminkyoz)](https://github.com/banminkyoz/purify) - A simple, fast & cool prompt.
* [purify (kyoz)](https://github.com/kyoz/purify) - A clean and vibrant theme, best on dark backgrounds. Includes `git` status decorations.
* [purity](https://github.com/petermbenjamin/purity) - 灵感来自 robbyrussell 主题和 [pure](https://github.com/sindresorhus/pure) 迅速的.
* [purs](https://github.com/xcambar/purs) - 快速 [pure](https://github.com/sindresorhus/pure)-inspired prompt written in [Rust](https://www.rust-lang.org/).
* [pustelto](https://github.com/Pustelto/shell_theme) - Colorful theme inspired by the [Spaceship](https://github.com/denysdovhan/spaceship-prompt) theme, includes `git` decorations.
* [qi3ber2](https://github.com/nichus/qi3ber2) - A dark multiline theme. Includes `git`, load average and exit code of last command decorators.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon)  - 针对深色背景进行了优化，包括 `git` 信息. 主题 repo 包括 iTerm 2 和终端颜色设置.
* [quewui](https://github.com/kauefontes/oh-my-quewui) - Simple and clean theme optimized for dark terminal themes. Includes status decorations for the current time, user, directory and `git` status.
* [r3nic1e](https://github.com/r3nic1e/r3nic1e) - [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 具有电池状态、`git/hg` 状态、时间、kubernetes 上下文和命名空间、最后一个命令的非零退出代码和日期装饰的变体. 需要电力线字体.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - 基于 af-magic 和 posh-git.
* [radium](https://github.com/dimitardimitrov/radium) - Designed for dark terminals, (works best with [Solarized](https://github.com/altercation/solarized) iTerm 2 主题）（prezto）.
* [radius](https://github.com/erikcc02/radius-zsh-theme) - Includes `git` status decorations, includes [desk](https://github.com/jamesob/desk) support.
* [rafiki](https://github.com/akabiru/rafiki-zsh) - Adds emojis to your ZSH terminal.
* [ramiel](https://github.com/aknackd/zsh-themes) - 叉子 [node](https://github.com/skuridin/oh-my-zsh-node-theme).
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - 基于 [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) and `robbyrussell` themes.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - Random emoji.
* [ranger-zoxide](https://github.com/fdw/ranger-zoxide) - Adds [zoxide](https://github.com/ajeetdsouza/zoxide) support to the [ranger](https://github.com/ranger/ranger) console file manager.
* [raspberrysh](https://github.com/MaxMalinowski/raspberrysh) - 包括`git`、python、时间、当前主机和路径装饰.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) - Simple and colorful theme with `git` status decorations.
* [raz](https://github.com/razman786/ohmyzsh-theme-raz) - Minimal prompt, includes `git` status decorations.
* [rb](https://github.com/rberenguel/rb-zsh-theme) - 基于电力线风格的 ZSH 主题 [Agnoster](https://gist.github.com/agnoster/3712874) ，针对`git`和solarized终端进行了优化. 需要与电力线兼容的字体.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - 针对日晒终端配色方案进行了优化，包括 `git` 状态装饰.
* [redline](https://github.com/DrissTM/redline.zsh-theme) - Minimalist theme. Includes `git` status, time, user.
* [reggae](https://github.com/nmercado1986/zsh-reggae-theme) - Compresses a lot of information into the prompt with color-coded status decorations.
* [rei](https://github.com/arturoalviar/rei-zsh-theme) - A simple theme with the first character being 零(rei), the number 0. Includes `git` status decorations.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), 优化为 [solarized](https://github.com/altercation/solarized) 终端主题.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - 基于 Sorin 的 Prezto ZSH 主题，使用表情符号来跟踪 GIT 上下文.
* [rho](https://github.com/andrejreznik/rho-zsh-theme) - Minimalist theme.
* [ribbon](https://github.com/tactlessfish/ribbon-prompt) - Reminiscent of powerline. Includes Python `virtualenv` decorator.
* [river](https://github.com/revir/river-zsh-config) - Dark theme with `git` information.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - 基于来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme and the project [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - 用输出装饰 `robbyrussell` 主题以指示 **WIP** 提交.
* [robbyrussell-fullpath](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) - 原本 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) with a fullpath in the prompt.
* [rocket](https://github.com/Alexandresl/rocket-zsh-theme) - Minimalist theme, includes `git` and `hg` status decoration.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - A dark theme.
* [roundy](https://github.com/nullxception/roundy) - fast, cute and roundy theme. Includes `git` decorations. Requires nerd fonts and a unicode-capable terminal application.
* [roz](https://github.com/rozNum/roz-zsh-theme) - Minimalist. Includes `git` status decorations, best on a darker background.
* [rs](https://github.com/rogeliosamuel621/rs-zsh-theme) - Includes `git` decorations. Requires unicode capable terminal.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) - 针对深色背景进行了优化.
* [rummik](https://github.com/rummik/zsh-theme)  - @rummik 的主题. 支持 [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), and `git` status information in the prompt.
* [russtone](https://github.com/russtone/prompt-russtone) - Inspired by [pure](https://github.com/sindresorhus/pure) and [sorin](https://github.com/sorin-ionescu/prezto). Includes `git` status decorations.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - Colorful theme, includes `git` decorations and the current directory.
* [rzh](https://github.com/patwhatev/rzh) - Theme with git states indicated by emojis.
* [s1ck94](https://github.com/zimfw/s1ck94) - Fork of the (first deprecated, now extinct) minimal prompt by S1cK94. Shows whether user is root, background job status, vi-mode, exit status of last command, and `git` status decorations.
* [s7c](https://github.com/Samega7Cattac/s7c.zsh-theme) - Works well with dark backgrounds. Includes `git` status decorations.
* [samshell](https://github.com/samuelb/samshell) - A minimalist zsh theme with `git`, kubernetes and python virtualenv decorations.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - Includes `git` status decorations, works well on a dark terminal background.
* [saturn](https://github.com/gantoreno/saturn-prompt) - A soft & minimalistic prompt for those who love space and want to have a bit of it on their terminal, featuring cool emojis & highly customizable prompt elements (such as icons, colors, time format, and more).
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) - Shows `git` status decorations, user@host information, the exit status of last command, and whether running as root.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - Shows if `vim` is running in the background when using `:sh` command.
* [scythe](https://github.com/kostoskistefan/scythe) - Powerline-reminiscent theme. Includes `git`, last command exit status and directory decorations.
* [sdkman](https://github.com/matthieusb/zsh-sdkman) - 添加选项卡完成 [sdkman](https://sdkman.io/).
* [seashell](https://github.com/jottenlips/seasonal-zshthemes) - Minimal theme with sea-inspired emoji decorations. Includes `git` status decorations.
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - This theme uses many special unicode characters to be fancy, but it may cause some problems without well supported fonts.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - Inspired by the dieter theme, uses color-coding to provide information.
* [senpai](https://github.com/hiroru/senpai-zsh) - Clean prompt theme for Devops. Includes `git` status information, the kubernetes context, AWS profile, GCP project and Azure active cloud.
* [sepshell](https://github.com/sepehr/sepshell) - Clean and minimal ZSH theme based on the old lost taybalt theme, with `git` bisecting/merging/rebasing modes and configurable prompt symbols.
* [serious](https://github.com/oliversandli/serious-zsh-theme) - 包括命令退出状态和 `git` 状态装饰.
* [seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - 一个简单的 omz 兼容主题，带有相应的 iTerm 2 配色方案。
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - 精益提示的演变，它本身就是对纯的重写.
* [shadow](https://github.com/agentshadow/shadow-zsh-theme) - 包括 `git` 状态、目录、主机名、用户名和时间装饰.
* [shayan](https://github.com/shayanh/shayan-zsh-theme) - Simple theme with `git` status decorations.
* [shelby](https://github.com/athul/shelby) - Fast, lightweight and minimal prompt written in pure `golang`. Includes decorations for last command exit status, `git` status and the current working directory.
* [shellder](https://github.com/simnalamburt/shellder) - Minimal theme with git branch display. Requires a Powerline-compatible font.
* [shichi](https://github.com/arturoalviar/shichi-zsh-theme)  - 一个简单的主题，第一个字符是七（shichi/nana），数字 7.原色是红色，带有黄色调. 包括 `git` 状态装饰.
* [shini](https://github.com/bashelled/shini) - A tiny theme that just shouts out small. Includes directory, username, hostname, time and `git` decorations.
* [shirnschall](https://github.com/shirnschall/shirnschall-zsh-theme) - 包括 `git` 状态和 `user@hostname` 装饰.
* [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) - Forked from [sixlive](https://github.com/sixlive/sixlive-zsh-theme). Has `git` decorations.
* [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 主题. 包括 `git` 和 `hg` 状态装饰.
* [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) - Includes `git` decorations.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - Simple theme which displays current directory and git information.
* [shtr0m](https://github.com/kyle-pollock/shtr0m) - Includes `git` status decorations.
* [siegerts](https://github.com/siegerts/zsh-theme) - Includes `git` status decorations in right prompt.
* [silver](https://github.com/reujab/silver) - A cross-shell customizable powerline-like prompt heavily inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme). A faster rust port of [bronze](https://github.com/reujab/bronze). Requires [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) . 非常可配置，包括 `git` 状态装饰.
* [simpalt](https://github.com/m-lima/simpalt) - An information-rich small-footprint theme for ZSH based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [simple (daopengz)](https://github.com/DaopengZ/simple-zsh-theme) - Works well with both light and dark terminal themes. Includes `vcs`, `username` and `path` decorations.
* [simple (pavdmyt)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - Minimalist theme based on [robbyrussel](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) that embeds `git` status information in iTerm's window title bar instead of using space in the prompt.
* [simple (savecoders)](https://github.com/Savecoders/simpleTheme-zsh-theme) - Simple and minimalist theme with `git`, `username` and execution status decorations.
* [simple (tourcoder)](https://github.com/tourcoder/simple.zsh-theme) - Minimalist prompt, includes `git` status decorations.
* [simple (yhiraki)](https://github.com/yhiraki/zsh-simple-prompt) - Minimal prompt, doesn't require special fonts.
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - 受电力线启发的简单主题，带有 `git` 装饰.
* [simple-git](https://github.com/BazaJayGee66/simple-git-theme) - Minimalist theme inspired by [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme). Includes `git` decorations.
* [simple-yet-beautiful](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme) - Minimalist theme. Includes `git` status and `user@host` prompt decorations.
* [simplezsh](https://github.com/fr0zn/simplezsh) - Minimal theme with `git` info display.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme) - k-kinzal's sinon theme. Includes `git` status decorations.
* [sit](https://github.com/svensen/sit.zsh-theme) - 带有 `git`、命令退出状态和路径装饰的极简主义主题.
* [sixlive](https://github.com/sixlive/sixlive-zsh-theme) - This theme has a unique directory listing. When inside a `git` project, the directory display is scoped to the current repository root.
* [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9's ZSH theme.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Atom、Prism 和 ZSH 的主题系列灵感来自 He-Man 和宇宙大师的 Skeletor.
* [skill](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - Optimized for a dark terminal, displays `git` status decorations.
* [skull](https://github.com/tahadostifam/skull-zsh) - 包括 `git` 状态、python 虚拟环境和 ruby​​ `rvm` 状态装饰.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH theme inspired by [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [odin](https://github.com/tylerreckart/odin).
* [slick](https://github.com/nbari/slick) - Inspired by the [pure](https://github.com/sindresorhus/pure), [purs](https://github.com/xcambar/purs) and [zsh-efgit-prompt](https://github.com/ericfreese/zsh-efgit-prompt). Requires `cargo` for installation.
* [slimline](https://github.com/mengelbrecht/slimline) - Minimal, fast and elegant ZSH prompt. Displays the right information at the right time.
* [sm](https://github.com/blyndusk/sm-theme) A **Simplist** & **Minimalist** theme for your **favorite** terminal. Includes `git` status decorations.
* [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) - A variant of the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme in [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - A prompt with happy and sad faces.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme) - A minimalistic ZSH theme inspired by the old-fashioned hobbies. No verbose gimmicks, no emoji, no fidget spinners, and no other visual noise. Has both light and dark modes.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - Solarized powerline variant.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) - ZSH 的太阳能电力线风格主题.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) - Color fix for robbyrussell's oh-my-zsh theme to work with [solarized](https://github.com/altercation/solarized) terminals.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) - Theme with `git`, `nvm`, rvm/rbenv/chruby, python, `ssh` and other useful status indicators.
* [spowerline](https://mbauhardt.github.io/spowerline/) - Written in scala, inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), [tmux](https://tmux.github.io) powerline, vim powerline and the vim status plugin.
* [spyrhoo](https://github.com/FajarKim/spyrhoo-zsh-theme) - Includes time, `git` and current directory decorations.
* [squanchy](https://github.com/gabrielecanepa/zsh-custom/tree/master/themes) - Minimalist theme. Includes `git`, `node` and `rbenv` status decorations.
* [ssfprompt](https://github.com/hugoh/zsh-ssfprompt) - Simple, slim, fast. Includes `ssh`, virtualenv and vcs decorations.
* [staples](https://github.com/dersam/staples) - Based on bureau, displays user@host if connected through SSH.
* [starboy](https://github.com/prdpx7/Starboy) - A simple ZSH theme.
* [starship](https://starship.rs/) - Minimal, fast, extremely customizable.
* [statusline](https://github.com/el1t/statusline) - A responsive ZSH theme that provides informational segments when you need them.
* [steef (danihodovic)](https://github.com/danihodovic/steeef)  - ZSH steeef 主题作为独立存储库. 这个 repo 背后的目的是避免在使用 steeef 主题时依赖 oh-my-zsh.  Antibody 等 ZSH 插件管理器可以使用主题，而无需使用 oh-my-zsh.
* [steef (zimfw)](https://github.com/zimfw/steeef) - A customizable version of [steeef's](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) theme.
* [steeple](https://github.com/erwanjugand/steeple-zsh-theme) - 带有“git”状态装饰的极简主义主题.
* [stellachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/stellachar.zsh-theme) - Minimal, pastels.
* [sublime](https://github.com/pjmp/sublime) - 带有 `git` 状态装饰的崇高、干净、简约的 ZSH 主题.
* [sugar-free](https://github.com/cbrock/sugar-free) - 基于 [Pure](https://github.com/sindresorhus/pure) and [Candy](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/candy.zsh-theme) themes.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme) - Includes `git` status decorations. Works better on dark terminal backgrounds.
* [sulfurium](https://github.com/Sulfurium/zsh-theme) - The official ZSH theme of sulfuriumOS.
* [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) - Similar to [sunrise](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) but includes the active Ruby version.
* [superkolo](https://github.com/Minipada/superkolo) - 添加日期和返回状态到 [kolo](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) theme.
* [susi](https://github.com/carcruz/susi-zsh-iterm) - Includes `git` status decorations and an accompanying iTerm2 color scheme.
* [svs](https://github.com/SvS30/svs-theme) - 带有“git”状态和当前路径装饰的清洁和无干扰主题.
* [sy](https://github.com/ttttmr/sy-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), includes `git` status decorations.
* [t2er](https://github.com/t2er/t2er-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - 针对深色背景优化的最小 ZSH 主题.
* [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) - Includes `git` status decorations and conda/virtualenv status.
* [termux](https://github.com/rooted-cyber/Termux-zsh-theme) - Minimalist theme.
* [termuxer](https://github.com/patrick330602/termuxer) - Theme inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and linuxer.
* [the-time-lord](https://github.com/jhwhite/the-time-lord) - 基于的主题 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - Colorful theme with `git` status.
* [theta-async](https://github.com/jesec/zsh_theme_theta-async) - Async version of [theta](https://github.com/eendroroy/theta). Includes vcs status information.
* [theta](https://github.com/eendroroy/theta) - Includes `git` and `hg` status decorations. Also has java, python, ruby, node, go and elixir version information.
* [theto](https://github.com/heyvito/theto-zsh-theme) - Simplistic theme.  Needs [Nerd Fonts](https://nerdfonts.com/), includes `vi`-mode status and `git` decorations.
* [thetraveler](https://github.com/bassopenguin/thetraveler) - Inspired by theunraveler, uses symbols to display `git` status.
* [thnikk](https://github.com/thnikk/zsh-theme-thnikk) - A minimal version of the [spaceship](https://github.com/denysdovhan/spaceship-prompt) theme.
* [thyme (chenhao-ye)](https://github.com/chenhao-ye/thyme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme), and [bullet-train](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme).
* [thyme (kawamurakazushi)](https://github.com/kawamurakazushi/thyme) - Simple theme with `git` status decorations.
* [toledo](https://github.com/mmatongo/toledo) - Quick minimalist theme with `git` status decorations.
* [tonni4](https://github.com/AndreyPuzanov/tonni4-zsh-theme) - Includes time and `git` status decorators.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh) - Includes `git` information; best on dark backgrounds.
* [tq](https://github.com/kitian616/tq-zsh-theme) - Displays `git` status, time, requires a Powerline font.
* [traffic](https://github.com/fcce/traffic-zsh-theme) - A dark theme for ZSH.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH.
* [trinity](https://github.com/de-luca/Trinity) - A simple theme based on [geometry](https://github.com/geometry-zsh/geometry). Includes `git` decorations.
* [tron](https://github.com/iDoTron/tron-zsh-theme) - Includes `git` status, working directory, time, user@host and return status of last command decorations.
* [tsotra](https://github.com/nylo-andry/zsh-themes) - 极简主题，包括 `git` 状态装饰、k8s 上下文和 `rvm` 状态.
* [turs](https://github.com/eikendev/turs) - Fast, minimal [Purs](https://github.com/xcambar/purs)-inspired prompt.
* [tvline](https://github.com/thvitt/tvline) - Derived from the [agnoster](https://gist.github.com/agnoster/3712874) 主题，添加电力线字体增强功能.
* [twilight](https://github.com/Henryws/twilight-prompt) - Minimalist, but includes last command exit status, `git` status and `user@hostname` decorations.
* [type0](https://github.com/MikereDD/type0_zsh-theme) - Inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) 通过 yarisgutierrez. 包括 `git` 装饰.
* [typewritten](https://github.com/reobin/typewritten)  - 最小和信息丰富的主题，为重要的事情留下空间. 异步 `git` 装饰更新以提高速度.
* [ubunly](https://github.com/alejandromume/ubunly-zsh-theme) - Mimics the Kali Linux console. Note - this theme also rebinds a lot of keys and sets a bunch of ZSH options that themes should leave alone.
* [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) - 模仿默认的 Debian/Ubuntu `bash` 提示符。
* [ubuntu-with-vitamins](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) - Mimics the default Ubuntu prompt, but with `git` decorations.
* [ubuntu](https://github.com/janstuemmel/zsh-ubuntu-theme) - Minimal theme, includes `git` status decorations.
* [ultimate](https://github.com/b4b4r07/ultimate) - Minimalist theme with `git` indicator, vim mode indicator and shortened path.
* [unicorn](https://github.com/juliuscaesar/unicorn) - Inspired by the [Wild Cherry](https://github.com/mashaal/wild-cherry) theme. Has emoji `git` status decorations.
* [unit-1](https://github.com/nerdbude/Unit-1) - Minimalist theme with ITWTB colors.
* [vanan](https://github.com/avano/vanan-zsh-theme) - Minimalist theme with `git` information for dark terminals.
* [vercel](https://github.com/vercel/zsh-theme) - 带有“git”状态装饰的极简主义主题.
* [vertepommes](https://github.com/TheRojam/vertepommes-theme) - Based on ys. Includes vcs status, username and current directory decorations.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - Modified from themes/mgutz.zsh-theme.Looks great when using with a [Solarized](https://github.com/altercation/solarized) 配色方案.
* [vitesse](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) - 灵感来自 VS Code [Vitesse](https://github.com/antfu/vscode-theme-vitesse) theme. Includes `git` status decorations.
* [vulcan](https://github.com/Bruceboy/vulcan-zsh-theme) - Minimal theme reminiscent of the default `bash` theme. Includes `git` decorations.
* [wade](https://github.com/wadehammes/wade.zsh-theme) - Mashup of the popular ZSH themes [Agnoster](https://gist.github.com/agnoster/3712874) and [Fishy](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme), with some visual tweaks.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) - Based on the 0532 theme.
* [whale](https://github.com/whalesea520/whale-zsh-theme) - Fast reimplementation of the whale theme.
* [whales](https://github.com/lbergelson/zsh_whales_theme) - Includes decorators for `git` status, java version, last command return status, and directory.
* [wild-cherry](https://github.com/mashaal/wild-cherry) - A fairy-tale inspired theme for ZSH, iTerm 2, Sublime, Atom, & Mou.
* [wkentaro](https://github.com/wkentaro/wkentaro.zsh-theme)  - Python 用户的简单主题. 包括 virtualenv 和 `git` 状态装饰器.
* [work-line](https://github.com/afnizarnur/work-line) - 带有漂亮表情符号的主题.
* [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) - Includes `git` status decorations, working directory, exit status of last command and current `virtualenv`.
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme)  - 旨在在您需要时向您展示所需信息的主题.  `wynwyn` 从默认主题 `avit` 和优秀 [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xavi](https://github.com/onthedock/xavi.zsh-theme) - Modified version of the [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) theme with emoji decorations for `git` status and current directory.
* [xlk-simple](https://github.com/xuelingkang/xlk-simple-zsh-theme) - Simple theme with `git` decorations.
* [xm](https://github.com/Shiaoming/xm) - Theme for dark terminals. Has `git` decorations.
* [xor](https://github.com/xor3n/xor-zsh-theme) - Self described as minimalistic and 'feature-poor', includes `git` decorations.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - An oh-my-zsh shell theme based on the Jreese theme plugin.
* [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme) - Fast, simple and streamlined theme. Works best with [tmux](https://github.com/tmux/tmux/wiki) and [vim-airline](https://github.com/vim-airline/vim-airline).
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - Shows the current git commit's shortened hash and message.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme) - Minimal theme with line separated prompts. Based on the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme.
* [yazpt](https://github.com/jakshin/yazpt) - A clean, fast, good-looking ZSH prompt theme that thoughtfully incorporates Git/Subversion/TFVC status info, integrates with popular plugin managers like Oh My Zsh, and is straightforward to customize and extend.
* [yechen](https://github.com/liyechen/yechen.zsh-theme) - 带有“git”状态装饰的极简主义主题.
* [yeet](https://github.com/jeetelongname/Yeet-theme) - Minimalist prompt with `git` status decorations.
* [yindev](https://github.com/menyinch/yindev-zsh-theme) - Variant of `gndx`. Includes decorations for `git` status and current directory.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - Modified from [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) theme and optimized for a dark background.
* [ys (cristiancavalli)](https://github.com/cristiancavalli/ys-zsh-custom-theme) - Clean, simple, compatible and meaningful theme meant for dark backgrounds.
* [ys (tinyRatP)](https://github.com/tinyRatP/ys) - Variant of [ys](https://gist.github.com/ysmood/6110461).
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme)  - `ys` 变体，支持使用大型集群的批处理提交系统. 支持 Slurm、LSF/IBM Spectrum LSF 和 PBS.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - Simple ZSH theme with `git` status information.
* [ysr](https://github.com/raykle/ysr-zsh-theme)  - 基于`ys`. 包括 `git` 状态装饰.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - A dark optimized ZSH theme.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - Includes conda and venv status.
* [yz50](https://github.com/lacanlale/yz50-zsh) - Colorful, based off of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and [crunch](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) themes. Includes `git` status decorations.
* [z4rr3t](https://github.com/inimicus/z4rr3t) - Based on sindresorhus' [pure](https://github.com/sindresorhus/pure) theme.
* [zcraft](https://github.com/cpea2506/zcraft) - Minimalist theme with decorations for `git` status, last command exit status and the time taken by the last command.
* [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme) Zelda-inspired theme. Includes `git` status decorations.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - Customized version of oh-my-zsh [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) with mercurial support and other changes.
* [zemoji](https://github.com/therzka/zemoji) - 基于 [wild-cherry](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ https://github.com/mashaal/wild-cherry/tree/master/zsh) . 包括退出状态、`virtualenv`、`nvm`、`rvm` 和 `git` 状态装饰.
* [zero](https://github.com/arlimus/zero.zsh) - Zero's theme & plugin. Has variants for both light and dark terminal backgrounds.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - Works best on dark backgrounds, includes `git` status decorations.
* [zerocake](https://github.com/ZeroPoke/ZeroCake.zsh-theme) - Works better on dark brackgrounds.
* [zest](https://github.com/hash-bang/zsh-theme-zest) - A functional theme for ZSH. Influenced by [zsh2000](https://github.com/consolemaverick/zsh2000), [agnoster](https://gist.github.com/agnoster/3712874) and [powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) themes.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) - Shows username, `git` status information, machine name, the current working directory and success/fail status of last command.
* [zinc](https://gitlab.com/robobenklein/zinc) - A blazing-fast, pure ZSH, mixed asynchronous powerline prompt that's easily extensible and extremely configurable.
* [zlambda](https://github.com/wdhg/zlambda) - Minimalist, includes `git` decorations without special font requirements.
* [zodiac](https://github.com/adamalsen/zsh-zodiac) - Includes an emoji for the animal corresponding to the current year.
* [zprompts](https://github.com/z-shell/zprompts) - Themes (prompts) that use original `zsh` theming subsystem.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) - Modified version of oh-my-zsh's [maran](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) theme.
* [zsh1999](https://github.com/DTan13/zsh1999) - Includes network connectivity, battery and `git` status decorations.
* [zsh2000](https://github.com/consolemaverick/zsh2000) - Powerline looking ZSH theme which includes the `rvm` prompt, `git` status and branch, current time, user, hostname, pwd, exit status, whether running as root and background job status.
* [zsh313](https://github.com/amirali313/zsh313-theme) - Minimal theme with `git` status decorations.
* [zshcomrade](https://github.com/landongn/zshcomrade) - A ZSH theme, comrade!
* [zshpower](https://github.com/snakypy/zshpower) - Optimized for python developers. Includes `git` and `pyenv` status decorations, username and host. Tries to install other plugins and fonts, so read its instructions before installing.
* [zshred](https://github.com/redxtech/zshred) - Shows current directory, `git` decorations, exit status of last command and time.
* [zwsh](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for ZSH.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) - Similar to [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), designed to disclose information contextually, with a powerline aesthetic.
* [zzshell](https://github.com/thezzisu/zzshell) - Inspired by the default [Oh-My-Zsh](http://ohmyz.sh/) theme. Displays exit code and `git` status decorations. Doesn't require Powerline fonts.

## Fonts

Some of the themes listed here require Powerline-compatible fonts, here are a few:

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - 一系列字体，包括一些不错的等宽图标.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - Another Powerline-compatible font.
* [Hack](https://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
* [Input Mono](https://store.typenetwork.com/foundry/djr/series/input?family=input-mono)  - 专为代码设计的字体系列. 它提供等宽字体和比例字体，并包括电力线字形.
* [Iosevka](https://github.com/be5invis/Iosevka) - Coders’ typeface, built from code. Highly customizable.
* [Monoid](https://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more.
* [Powerline patched font collection](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include powerline gylphs.
* [Terminus](http://files.ax86.net/terminus-ttf/) - TTF version of Terminus that includes powerline glyphs.

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start `zsh`. You can also add the plugin to a running ZSH with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1. Clone new plugins into `.zsh.local/modules`
2.在`.zshrc`中加载插件模块
3. Open a new ZSH terminal window or tab

### [Oh-My-Zsh](http://ohmyz.sh/)

1.`cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. Add the repo to your plugin list

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. Clone the plugin into your prezto modules directory
2. 将插件添加到您的 `.zpreztorc` 文件中
3. Open a new terminal window or tab

### [Zgen](https://github.com/tarjoilija/zgen)

Zgen is not being actively maintained. Consider switching to the [Zgenom](https://github.com/jandamm/zgenom) 叉子，也就是.

### [Zgenom](https://github.com/jandamm/zgenom)

这些插件中的大多数都可以通过将 `zgenom load githubuser/reponame` 添加到您的 .zshrc 文件中来安装，这与您正在执行其他 `zgenom load` 调用的功能相同.

Zgenom will automatically clone the plugin repositories for you when you do a `zgenom save`.

### [zplug](https://github.com/zplug/zplug)

Most of these plugins can be installed by adding `zplug "githubuser/reponame"` to your `.zshrc` file.

### [zpm](https://github.com/zpm-zsh/zpm)

Most of these plugins can be installed by adding `zpm load "githubuser/reponame"` to your `.zshrc` file.

## Writing New Plugins

I've documented some recommendations for writing a new plugin [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

There is also a more detailed [Zsh Plugin Standard](https://zdharma-continuum.github.io/Zsh-100-Commits-Club/Zsh-Plugin-Standard.html).

## Other Resources

### ZSH Tools

* [ShellSpec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, ZSH and all POSIX shells.
* [zsh-bench](https://github.com/romkatv/zsh-bench) - A benchmark for interactive ZSH. It measures user-visible latency of interactive `zsh`: input lag, command lag, etc
* [zshdb](https://github.com/rocky/zshdb) - A ZSH debugger.
* [zshelldoc](https://github.com/zdharma-continuum/zshelldoc) - Doxygen for shell scripts. Parses ZSH and Bash scripts, outputs Asciidoc document with function lists, call trees, lists of exported variables, and more.
* [zunit](https://github.com/zunit-zsh/zunit) - 一个强大的 ZSH 单元测试框架.

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - A curated list of awesome tools, resources and workflow tips making an awesome development environment
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open source sysadmin resources
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - A curated list for CLI lovers.

在以下位置查找其他有用的 awesome-* 列表 [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

- The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) are indispensable.

- [Mastering ZSH](https://github.com/rothgar/mastering-zsh) 是一个很棒的教程，它建立在基础之上，向您展示 ZSH 的高级用法、自定义和实际示例.
