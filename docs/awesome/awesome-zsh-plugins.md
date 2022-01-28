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

You can find some interesting performance timing comparisons of various frameworks in the following locations.

* [rossmacarthur/zsh-plugin-manager-benchmark](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark)
* [pm-perf-test](https://github.com/z-shell/pm-perf-test) - 用于在多个 ZSH 框架上运行性能测试的工具.
### [alf](https://github.com/psyrendust/alf)

 **Alf** 是一个超快速且可配置的 ZSH 框架； 它以 Prezto 和 Antigen 为蓝本，同时在封面下使用 Oh-My-Zsh； 并提供标准默认值、别名、功能、自动完成、自动更新和可安装的提示主题和插件.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

 **ansible-role-zsh** 是一个零知识安装的 ansible 角色. 它使用抗原来管理捆绑包和 oh-my-zsh. 可以有条件地加载包. 默认情况下，它包括 powerlevel9k 主题、自动建议、语法高亮和 [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) 和 [fzf-marks](https://github.com/urbainvaes/fzf-marks) . 完全可定制.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody](https://github.com/getantibody/antibody)

**Antibody** is a faster and simpler antigen written in Golang. More details at [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

**antigen-hs** is a replacement for antigen optimized for a low overhead when starting up the shell. It will automatically clone plugins for you.

### [antigen](https://github.com/zsh-users/antigen)

 **Antigen** 是一小组功能，可帮助您轻松管理外壳 (ZSH) 插件，称为捆绑包. 这个概念与典型的 vim+pathogen 设置中的包几乎相同.  Antigen 之于 ZSH，Vundle 之于 vim.  Antigen 可以加载 oh-my-zsh 主题和插件，并会自动为您克隆它们.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)

**Ax-ZSH** is a modular configuration system for ZSH. It provides sane defaults and is extendable by plugins.

### [dotzsh](https://github.com/dotphiles/dotzsh)

 **Dotzsh** 努力实现平台和版本独立. 在旧版本的 ZSH 下运行时，某些功能可能会丢失，但它应该会完全降级，并允许您在不同操作系统的多台机器上使用相同的设置而不会出现问题.

### [fresh](https://github.com/freshshell/fresh)

 **fresh** 是一个工具，可以将其他人的 shell 配置（别名、函数等）导入到您自己的配置文件中. 我们还支持 ackrc 和 gitconfig 等文件. 将其视为您的点文件的 Bundler.

### [miniplug](https://sr.ht/~yerinalexey/miniplug)

**miniplug** 是 ZSH 的简约插件管理器.

* No crashes or double plugin loading when re-sourcing .zshrc
* Unlike other frameworks, Miniplug does not pollute your $PATH
* 只做最低限度的插件管理

### [mzpm](https://github.com/Insert-Creative-Name-Here/mzpm)

**mzpm** 是 ZSH 的极简插件管理器.

Features:

- 从 GitHub 获取和加载插件
- Loading local plugins
- 加载主题

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

 PZ 足以很好地管理您的 Zsh 插件，然后让您摆脱困境. 它也经过单元测试，以确保它按预期工作！

### [sheldon](https://github.com/rossmacarthur/sheldon)

一个快速、可配置的 shell 插件管理器.

* Can manage
  * 任何 `git` 存储库.
    * 分支/标签/提交支持.
    * Extra support for GitHub repositories.
    * Extra support for Gists.
  * 任意远程文件，只需指定 URL.
  * 本地插件，只需指定目录路径.
*使用高度可配置的安装方法 [handlebars](http://handlebarsjs.com/) 模板.
* 超快速并行安装.
* Configuration file using [TOML](https://github.com/toml-lang/toml) 句法。
* Uses a lock file for much faster loading of plugins.

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

 **zcomet** 是一个简约的 ZSH 插件管理器，无需缓存即可让您快速获得提示（请参阅基准）. 除了加载和更新存储在 Git 存储库中的插件外，它还支持延迟加载插件（进一步减少启动时间）以及下载和获取代码片段.

### [zebrafish](https://github.com/mattmc3/zebrafish)

**Zebrafish** 是一个轻量级、功能齐全、速度极快的 ZSH 微框架，仅包含一个文件.

### [zeesh](https://github.com/zeekay/zeesh)

**Zeesh** is a cross-platform ZSH framework. It's similar to, but incompatible with, [oh-my-zsh](http://ohmyz.sh/) . 它具有模块化的插件架构，使其易于扩展. 它有一组丰富的默认值，但被设计为尽可能轻量级.

### [zgem](https://github.com/qoomon/zgem)

**Zgem** 是 ZSH 的插件管理器，支持从 git、http 和本地文件加载和更新插件和主题.

### [zgen](https://github.com/tarjoilija/zgen)

 **Zgen** 是受 Antigen 启发的 ZSH 轻量级插件管理器. 目标是在启动 shell 时有最小的开销，因为没有人喜欢等待. 它目前没有得到积极维护，我建议您使用 [zgenom](https://github.com/jandamm/zgenom) 叉子代替，这是.

### [zgenom](https://github.com/jandamm/zgenom)

A lightweight plugin manager for ZSH that is a fork that extends the brilliant [zgen](https://github.com/tarjoilija/zgen) 并提供更多功能和错误修复，同时完全向后兼容.

为了在新的终端会话期间保持快速加载，`zgenom` 会生成一个静态的 `init.zsh` 文件，它除了获取插件并将它们附加到您的 `fpath` 之外什么都不做.

这通过在启动期间不必执行耗时的逻辑（插件检查、更新等）来最小化启动时间. 不利的一面是，每当您更新 `.zshrc` 中的插件列表时，都必须使用 `zgenom reset` 手动刷新 init 脚本.

Zgenom can load [oh-my-zsh](http://ohmyz.sh/)-compatible and [prezto](https://github.com/sorin-ionescu/prezto)- 兼容的插件和主题，当您将它们添加到插件列表时，它们会自动为您“git clone”插件.

### [ZI](https://github.com/z-shell/zi)

 **ZI** 是用于 Zsh Unix shell 的瑞士军刀. 以前称为zplugin、zinit. 紫—— [Wiki Pages](https://z-shell.pages.dev/).

Bonus: you can use [zi-console](https://github.com/z-shell/zi-console) to view and change the state of the ZSH session (e.g.: list and unload plugins) and to delete the plugins and snippets from the disk.

### [zilsh](https://github.com/zilsh/zilsh)

**zilsh** is a ZSH config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim](https://github.com/zimfw/zimfw)

**Zim** is a ZSH configuration framework with blazing speed and modular extensions.

### [Zinit](https://github.com/zdharma-continuum/zinit)

**Zinit** 是一个创新的并且可能（由于 Turbo）最快的插件管理器，它支持：

 - Turbo 模式 – ZSH 启动速度提高 80%！ 例如：不是 200 毫秒，而是 40 毫秒
- Completion management (selectively disable and enable completions)
- Snippets (↔ regular files downloaded via-URL, e.g.: scripts) and through them Oh My Zsh and Prezto plugins support (→ low overhead)
- 附件（↔ Zinit 扩展）
- 报告（来自插件加载 - 插件不再是黑匣子）
- 插件卸载（允许例如：动态主题切换）
- `bindkey` capturing and remapping
- packages
- 清理 `fpath`（数组 `$fpath` 不用于添加完成和自动加载功能，因此它保持简洁，而不是臃肿）
- 服务↔单实例后台插件
- Also, in general: all the mechanisms from the ZSH Plugin Standard – Zinit is a reference implementation of the standard.

该项目非常活跃——目前 &gt; 3100 次提交.

### [zit](https://github.com/thiagokokada/zit)

 **zit** 是 ZSH 的插件管理器. 它是最小的，因为它实现了作为插件管理器的最低要求：它允许用户从 Git 存储库（仅限 Git 存储库，它们为什么名称）安装插件，获取插件并更新它们. 它没有实现花哨的功能，例如清除已删除插件、自动编译已安装插件、oh-my-zsh/prezto/其他 ZSH 框架的别名、构建二进制文件、PATH 操作等.

### [znap](https://github.com/marlonrichert/zsh-snap)

 **:zap:Znap** 是一个轻量级的 ZSH 插件管理器和 Git 存储库管理器，易于理解. 虽然专门为 ZSH 插件量身定制，但 Znap 还用作管理 Git 存储库的通用实用程序.

Znap

Znap 可以：

 - 使任何提示立即出现. 只需一个命令即可将启动时间从 ~200ms 减少到 ~40ms.
- Asynchronously compile your plugins and functions.
- Cache those expensive `eval $(commands)`.
- 并行克隆或拉取多个存储库.
- 无需重新输入即可重新克隆所有存储库.
- 多回购管理
- Automatic `compinit` and `bashinit` - you no longer need them in your `.zshrc`, znap will do them automatically as needed.

### [zoppo](https://github.com/zoppo/zoppo)

**Zoppo** is the crippled configuration framework for ZSH. As an Italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.

### [zpacker](https://github.com/happyslowly/zpacker)

**Zpacker** 是一个轻量级的 ZSH 插件和主题管理框架.

### [zpico](https://github.com/thornjad/zpico)

The minuscule ZSH package manager. No frills, no bloat, just 2 kB of 100% ZSH code, providing complete package management for your ZSH environment.

### [zplug](https://github.com/zplug/zplug)

**:hibiscus: Zplug** 是下一代 ZSH 插件管理器.

- Can manage everything
  - Zsh 插件/UNIX 命令 [GitHub](https://github.com) 和 [Bitbucket](https://bitbucket.org)
  - 要点文件（[gist.github.com](https://gist.github.com/discover))
  - 外部管理的插件，例如， [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [prezto](https://github.com/sorin-ionescu/prezto) plugins/themes
  - Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
  - Local plugins
  - 等等（你可以添加你 [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- 超快速并行安装/更新
- 支持延迟加载
- 分支/标签/提交支持
- Post-update, post-load hooks
- 包之间的依赖关系
- Unlike [antigen](https://github.com/zsh-users/antigen), no ZSH plugin file (`*.plugin.zsh`) required
- Interactive interface ([fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw)， 等等）
- Cache mechanism for reducing [the startup time](https://github.com/zplug/zplug#vs)

### [zpm](https://github.com/zpm-zsh/zpm)

**zpm** ( ZSH Plugin Manager ) 是一个插件管理器 [ZSH](http://www.zsh.org/) 谁结合了命令式和声明式方法. 在第一次运行时，zpm 会做复杂的逻辑并生成缓存，之后将只使用缓存，因此它使这个框架非常快.

* 最快的插件管理器（真的，第一次运行后，zpm 根本不会用）
* 支持异步加载
* Dependencies between packages
* zpm 在 Linux、macOS、FreeBSD 和 Android 上运行.
* zpm 插件兼容 [oh-my-zsh](http://ohmyz.sh/).

### [zr](https://github.com/jedahan/zr)

**zr** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zshing](https://github.com/zakariaGatter/zshing)

**zshing** is a ZSH plugin manager similar to Vundle/Vim and allows you to...

* keep track of and configure your plugins right in the `.zshrc`
* 安装 ZSH 插件
* 更新 ZSH 插件
* Search by name all available ZSH Plugins
* 清理未使用的插件
* run the above actions in a *single command*
* 管理已安装插件的 __Source Plugins__

### [ztanesh](https://github.com/miohtama/ztanesh)

**Ztanesh** aims to improve your UNIX command line experience and productivity with the the configuration provided by the ztanesh project: the tools will make your shell more powerful and easier to use.

### [ztheme](https://github.com/SkyyySi/ztheme)

ztheme is a small and fast theme engine for ZSH.

### [ztupide](https://github.com/mpostaire/ztupide)

一个简单快速的 ZSH 插件管理器. 它使用 zcompile 和异步加载来加快你的 shell 启动时间.

### [zulu](https://github.com/zulu-zsh/zulu)

**Zulu** 是 ZSH 5+ 的环境管理器，旨在让您无需编写任何代码即可轻松管理 shell.

* Easily manage your shell environment without editing files.
* Create aliases, functions and environment variables, and have them available to you at the next shell startup.
* 使用简单的命令从 `$path`、`$fpath` 和 `$cdpath` 添加和删除目录.
* Install packages, plugins and themes easily, and have them available to you immediately.

## Setups

本节用于完整设置插件 - 它们不是框架，但它们也不是简单的插件/主题.

### zgenom

* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - 使用 ZSH 的简单快速入门 [zgenom](https://github.com/jandamm/zgenom). This automatically configures ZSH to use [zgenom](https://github.com/jandamm/zgenom) 加载精选的插件集合并定期自动更新自身、插件和快速入门工具包本身.

### zinit

* [ZPWR](https://github.com/MenkeTechnologies/zpwr) - 一个极其强大的自定义终端环境，建立在 [Zinit](https://github.com/zdharma-continuum/zinit) 以获得最大速度. 一个完整的终端配置框架，包括 `zsh`、`tmux`、`fzf`、`vim` 和 spacemacs 配置. 这包括：

- 11.5k+ tab completions
- 1.9k+ 别名
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
* [GH](https://github.com/gustavohellwig/gh-zsh)  - 在基于 debian/Ubuntu 的 linux 上设置 ZSH. 安装 [Powerlevel10k](https://github.com/romkatv/powerlevel10k), [zsh-completions](https://github.com/zsh-users/zsh-completions), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting/)， 和更多.
* [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - A beginner-friendly tutorial on how to install and configure a ZSH shell.
* [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
* [rs-example](https://github.com/al-jshen/zshplug-rs-example) - An example plugin showing how a Rust program can listen to and process commands from ZSH.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
* [xVanjaZ](https://github.com/xVanjaZ/xVanjaZ-ZSH-Theme) - 为 oh-my-zsh 初学者编写了一个快速设置文档，展示了如何使用 [spaceship](https://github.com/denysdovhan/spaceship-prompt.git) 提示符、提示符处的语法高亮、自动提示和自定义 iTerm 2 主题.
* [ZSH for Humans](https://github.com/romkatv/zsh4humans) - A turnkey configuration for ZSH that aims to work really well out of the box. It combines a curated set of ZSH plugins into a coherent whole that feels like a finished product rather than a DIY starter kit.
* [ZSH Pony](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.
- [ZSH Unplugged](https://github.com/mattmc3/zsh_unplugged) - Good resource if you want to eliminate using a framework but still easily use plugins.

### Antigen

* [belak/zsh-utils](https://github.com/belak/zsh-utils) - 一组最小的 ZSH 插件，旨在低摩擦和低复杂性.
* [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean 关于从 oh-my-zsh 切换到抗原的文章.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis 对 Antigen 的介绍.

### Oh-My-Zsh

* [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - A beginners guide to oh-my-zsh by Dien Bui
* [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - Karl Hadwen 在 macOS 上使用 Oh My Zsh 的初学者指南
* [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders installation guide for Ubuntu
* [ZSH Gem 24](https://www.refining-linux.org/archives/59-ZSH-Gem-24-ZSH-frameworks.html) - Part of the 2011 ZSH Advent Calendar. Covers oh-my-zsh and zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, [Tmux](https://tmux.github.io) & Tmuxinator.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert 关于迁移到 Prezto 的博客文章.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) - A fantastically feature rich, lightning-fast shell setup, powered by [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto)， 和 [Zgen](https://github.com/tarjoilija/zgen).

### Zinit (né zplugin)

* [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh) - :crystal_ball: Awesome, customable Zsh Starter Kit :stars::stars:. Includes powerline, `fzf` integration, Weather and image viewing in some terminals.
* [zinit-configs](https://github.com/zdharma-continuum/zinit-configs) - 真实世界的配置文件（基本上是 `.zshrc` 文件的集合）保存 [zinit](https://github.com/zdharma-continuum/zinit) invocations.

### ZSH on Windows

* [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only.

  * ConEmu/zsh 开箱即用配置为在 ConEmu 重新启动后恢复以前打开的选项卡和 shell 工作目录
  * 在启动新的 SuperConsole 会话时选择干净和继承的环境
  * Custom colorful scheme, colorful output for various commands
  * 包括 MSYS2，`zsh` 和必要的软件预装，使用 zsh-grml-config
  * 使用 Antigen 进行 ZSH 主题和配置管理
  * Enabled number of ZSH plugins to activate completion, highlighting and history for most comfortable use
  * 为 MSYS2 环境配置了正确的 `git` 和 git lfs 支持的 Git-for-Windows 存储库，`git` 客户端已经安装.
  * `git` 的 `ssh-agent` 开箱即用，将您的密钥添加到 `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` 目录
  * Non-blocking ZSH prompt status updates thanks to agkozak-zsh-prompt
  * 为 MSYS2 定制的 command-not-found 处理程序建议安装什么包
  * Sets up `nano` as main editor, enables `nano` syntax highlighting
  * 自定义帮助脚本添加到 `ConEmu/msys64/3rdparty`

## Plugins

* [1999](https://github.com/DTan13/zsh1999)  - 电力线式主题. 包括 `git` 状态装饰、网络和电池状态.
* [256color](https://github.com/chrissicool/zsh-256color)  - 使用 256 色增强终端环境. 它查看所选的 `TERM` 环境变量，并查看是否有相应的 ncurses 的 terminfo 以及 256 种颜色可用. 结果是多色终端（如果可用）.
* [abbr (olets)](https://github.com/olets/zsh-abbr) - Manages auto-expanding abbreviations that expand inline when you hit space, inspired by fish shell.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - Provides functionality similar to `vim`'s abbreviation expansion.
* [accurev](https://github.com/dalefukami/accurev-zsh) - ZSH plugin for [accurev](https://www.microfocus.com/en-us/products/accurev/overview).
* [actiona](https://github.com/matthieusb/act) - Make it easier to call [actiona](https://github.com/Jmgr/actiona) scripts from your command line. Includes tab completions.
* [alacritty](https://github.com/casonadams/alacritty-shell) - Control [alacritty](https://github.com/alacritty/alacritty/wiki/Color-schemes) 配色方案.
* [alehouse](https://github.com/sticklerm3/alehouse) - 包含短别名 [brew](https://brew.sh) 命令，灵感来自 [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin).
* [alias-tips](https://github.com/djui/alias-tips) - 一个 oh-my-zsh 插件，可帮助记住您曾经定义的那些别名.
* [alias](https://github.com/xylous/alias-zsh) - 用于管理别名的工具.
* [allergen](https://github.com/stanislas/allergen) - A collection of custom ZSH plugins to use with Antigen.
* [almostontop](https://github.com/Valiev/almostontop)  - 每次在 shell 中执行新命令之前清除先前的命令输出. 灵感来自 [alwaysontop](https://github.com/swirepe/alwaysontop) `bash` 的插件.
* [alt-and-select](https://github.com/raisty/alt-and-select) - Binds the alt-c (copy), alt-v (paste), alt-x (cut) keyboard shortcut to a commands: copy-region-as-kill, yank, kill-region. Remaps the execute command to Alt-Shift-X.
* [ansible](https://github.com/sparsick/ansible-zsh) - 一个插件 [Ansible](https://www.ansible.com/).
* [ansiweather](https://github.com/fcambus/ansiweather) - 终端中的天气，带有 ANSI 颜色和 Unicode 符号.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH script to aid with `git` rebasing.
* [anyframe](https://github.com/mollifier/anyframe) - ZSH 的 peco/percol/fzf 包装插件.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - 添加用于管理 Apache2 的别名和功能.
* [apparix](https://github.com/micans/apparix) - Command line directory bookmarks with jumping to bookmarks, subdirectory tab completion, distant listing etc.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - 添加 MacBook Pro 触控栏支持 [iTerm 2](https://iterm2.com).
* [appup](https://github.com/Cloudstek/zsh-plugin-appup) - Adds `start`, `stop`, `up` and `down` commands when it detects a `docker-compose.yml` or `Vagrantfile` in the current directory (e.g. your application). Just run `up` and get coding!
* [arc](https://github.com/anton-rudeshko/zsh-arc) - Adds aliases for Yandex version control system.
* [arduino](https://github.com/raghur/zsh-arduino) - Adds scripts to build, upload and monitor arduino sketches from a command line. Requires [`jq`](https://stedolan.github.io/jq/).
* [artisan](https://github.com/jessarcher/zsh-artisan) - Laravel `artisan` plugin for ZSH to help you to run `artisan` from anywhere in the project tree, with tab completion!
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - AsciiDoctor 的插件.
* [asdf-direnv](https://github.com/redxtech/zsh-asdf-direnv) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf) 和 [direnv](https://github.com/asdf-community/asdf-direnv).
* [asdf](https://github.com/kiurchv/asdf.plugin.zsh) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf), the extendable version manager, with support for Ruby, Node.js, Elixir, Erlang and more.
* [assume-role](https://github.com/weizard/assume-role) - ZSH plugin to allow you to assume AWS IAM roles easily. Includes completions.
* [async](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in ZSH without requiring any external tools. Allows you to run multiple asynchronous jobs, enforce unique jobs (multiple instances of the same job will not run), flush all currently running jobs and create multiple workers (each with their own jobs).
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - 基于 [Sublime](https://github.com/valentinocossar/sublime) 插件，可让您在其中启动文件或文件夹 [Atom](https://atom.io) from [iTerm 2](https://iterm2.com).
* [atuin](https://github.com/ellie/atuin)  - 用 SQLite 数据库替换你现有的 shell 历史，并为你的命令记录额外的上下文. 此外，它还可以通过 Atuin 服务器在机器之间提供可选且完全加密的历史同步.
* [aur-install](https://github.com/redxtech/zsh-aur-install) - 从 AUR 安装软件包的小插件.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) - Automatically list directories with `colorls`.
* [auto-fortune-cowsay](https://github.com/babasbot/auto-fortune-cowsay-zsh) - Prints out an ASCII picture of a cow saying a random epigram on every zsh start.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
* [auto-ls (commanda-panda)](https://github.com/commanda-panda/zsh-auto-ls) - 自动运行 `ls` 或 `color-ls` 如果在 `cd` 上可用.
* [auto-ls (desyncr)](https://github.com/desyncr/auto-ls) - cd 到新目录时自动 `ls`.
* [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) - Automatically sends out a notification when a long running task has completed.
* [auto-nvm](https://github.com/manlao/zsh-auto-nvm) - Automatically switches to the node version specified in a given directory.
* [autocomplete](https://github.com/marlonrichert/zsh-autocomplete) - Automatically lists completions as you type and provides intuitive keybindings for selecting and inserting them.
* [autodotenv](https://github.com/nocttuam/autodotenv) - 当您将 `cd` 放入包含 `.env` 文件的目录时，会提示您加载变量.
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) - Extended version of the [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) 插入.
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a `.env` file, it will automatically be executed when you `cd` into it.
* [autojump](https://github.com/wting/autojump)  - 一个学习的 `cd` 命令 - 从命令行轻松导航目录. 安装 autojump-zsh 以获得最佳效果.
* [autopair](https://github.com/hlissner/zsh-autopair) - A ZSH plugin for auto-closing, deleting and skipping over matching delimiters. Only tested on ZSH 5.0.2 or later.
* [autoquoter](https://github.com/ianthehenry/zsh-autoquoter) - A `zle` widget ("zsh plugin") that will automatically put quotes around arguments to certain commands.
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)- 类似 ZSH 的快速/不显眼的自动建议.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) - ZSH plugin to automatically switch python virtualenvs and pipenvs when traversing directories. Automatically detects pipenv and poetry projects.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin)  - Antigen 不会像 oh-my-zsh 那样进行自动更新. 该插件为抗原添加了自动更新，包括抗原和配置中加载的包.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - oh-my-zsh 不会自动更新非核心插件，这会将插件自动更新添加到 oh-my-zsh.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - 基于 sweharris 的 AWS CLI MFA 插件 [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa). Supports specifying mfa_device in profile.
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - Plugin for AWS MFA.
* [aws-plugin](https://github.com/pookey/zsh-aws-plugin)  - 为 `aws` 命令添加辅助函数. 包括 mfa 和假设角色助手.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - 使用 `aws-upload` 提高您的工作效率.
* [aws-vault (blimmer)](https://github.com/blimmer/zsh-aws-vault) - Plugin for [aws-vault](https://github.com/99designs/aws-vault). Includes tab completions.
* [aws-vault (reegnz)](https://github.com/reegnz/aws-vault-zsh-plugin) - Makes it easier to use [aws-vault](https://github.com/99designs/aws-vault) 在你的环境中。
* [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) - Provides completion support for version 2 of the [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) and a few utilities to manage AWS profiles and display them in the prompt.
* [aws](https://github.com/apachler/zsh-aws) - 从原始的 oh-my-zsh 分叉 [aws](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aws) . 包括 `awscli` 的补全和一些用于管理 AWS 配置文件并在提示中显示它们的实用程序.
* [awsume](https://github.com/Sordie/AWSume) - 可以显示当前的插件 [awsume](https://github.com/trek10inc/awsume) profile.
* [azcli](https://github.com/dmakeienko/azcli) - 使用 azure cli 工具的助手.
* [azure-keyvault](https://github.com/milespossing/Azure-Keyvault-Zsh) - 使在 cli 中使用 azure keyvaults 变得不那么冗长.
* [azure-subscription](https://github.com/dmakeienko/azure-subscription-prompt) - 显示有关 Azure 当前订阅和租户的信息.
* [background](https://github.com/zpm-zsh/background) - ZSH plugin which executes functions in the background.
* [base16](https://github.com/chriskempson/base16-shell)  - 添加脚本以允许您更改 shell 的默认 ANSI 颜色，但最重要的是，更改 shell 的 256 色空间的 17 到 21 色（如果您的终端支持）. 这个脚本可以在为应用程序提供额外的 base16 颜色的同时，尊重 shell 的原始明亮颜色（例如，亮绿色仍然是绿色等等） [Vim](https://www.vim.org).
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts)  - 在你的外壳中打印随机棒球相关的“有趣的事实”. 取决于安装的 `fortune` 和 `cowsay`.
* [basex](https://github.com/dirkk/zsh-basex) - 增加了几个 [BaseX](http://basex.org/) aliases for simplified usage.
* [bash-quote](https://github.com/jtprog/bash-quote) - 从 Bash.im 获取随机报价.
* [bash](https://github.com/chrissicool/zsh-bash)  - 使 ZSH 更兼容 Bash. 它重新定义了 source 命令，使其更像 `bash`. 它还启用了 `bash` 完成.
* [battery_state](https://github.com/Jactry/zsh_battery_state) - Show battery state in right-prompt.
* [bd](https://github.com/Tarrasch/zsh-bd) - 跳回特定目录，无需执行 `cd ../../..`.
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) - Remap ZSH `vi`-mode for French [bépo keyboard](http://bepo.fr/wiki/Accueil).
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) - 为“brew”添加更多命令别名
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - 添加帮助脚本以允许您创建 bitbucket PR 或在当前分支中打开目录.
* [bitwarden](https://github.com/Game4Move78/zsh-bitwarden) - Adds functions to manage [bitwarden](https://bitwarden.com/) sessions.
* [blackbox](https://github.com/StackExchange/blackbox) - [Stack Exchange](https://stackexchange.com)'s toolkit for storing keys/credentials securely in a `git` repository.
* [bofh](https://github.com/fundor333/bofh) - Adds functions to display random bofh fortunes.
* [bol](https://github.com/ikhurramraza/bol) - Prints a random quote when you open a terminal window.
* [boss-docker](https://github.com/bossjones/boss-docker-zsh-plugin) - 在 OSX 上管理 `docker`.
* [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) - 为 `git` 添加了一些方便的别名.
* [branch-manager](https://github.com/elstgav/branch-manager) - A plugin for managing `git` branches.
* [brew (rhuang2014)](https://github.com/rhuang2014/brew) - 独立插件 [Homebrew](https://brew.sh/) Package Manager.
* [brew (wolffaxn)](https://github.com/wolffaxn/brew-zsh-plugin) - 独立插件 [Homebrew](https://brew.sh/) Package Manager.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - 一个插件，可让您从命令行在浏览器中打开任何提交.
* [bruse](https://github.com/aubreypwd/zsh-plugin-bruse) - Makes it easy to `brew link` different versions of packages.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - A plugin to toggle optirun in the command line.
* [c](https://github.com/sebastiangraz/c) - Adds some `git` shortcuts.
* [calc](https://github.com/arzzen/calc.plugin.zsh) - A calculator for ZSH.
* [calibre-zaw-source](https://github.com/junkblocker/calibre-zaw-source) - [Calibre - E-book management](https://calibre-ebook.com/) 来源 [zaw](https://github.com/zsh-users/zaw)
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - 添加 [Can I Use...](https://caniuse.com) 支持 ZSH.
* [careful_rm](https://github.com/MikeDacre/careful_rm) - `rm` 的包装器，添加了垃圾/回收和有用的警告.
* [case](https://github.com/rtuin/zsh-case) - 一个 ZSH 插件，添加了两个别名 `tolower` 和 `toupper` 来切换输出大小写.
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - A ZSH plugin to `cd` to the `git` repository root directory.
* [cd-ls](https://github.com/zshzoo/cd-ls) - 在`cd`之后自动`ls`.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) - Display reminders when `cd`-ing into specified directories.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - 一个 ZSH 插件，用于 `cd` 到当前存储库签出的根目录.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - 当你不小心 `cd` 到服务器时，`ssh` 到服务器.
* [cdbk](https://github.com/MikeDacre/cdbk) - 一个 ZSH 插件，允许轻松创建命名目录 - 任何您想要的目录的快捷方式.
* [cdc](https://github.com/evanthegrayt/cdc) - Makes it easier to change directories to directories that are subdirs of a user-defined list of directories. Includes tab-completion, session history and `pushd`, `popd` and `dirs` equivalents.
* [cdr](https://github.com/willghatch/zsh-cdr) - Easy setup of cdr for ZSH.
* [change-case](https://github.com/mtxr/zsh-change-case) - Plugin for fast swap between upper and lower case in your command line. :sunglasses:
* [cheatsheet](https://github.com/0b10/cheatsheet) - 用于轻松查看、创建和编辑备忘单的插件.
* [check-deps](https://github.com/zpm-zsh/check-deps)  - ZSH 插件的助手，允许他们展示如何安装任何缺少的依赖项. 如果您使用的是 Debian（以及 Ubuntu 等衍生产品）、Arch 及其衍生产品、Nodejs 和 ZSH 插件 [zpm](https://github.com/zpm-zsh/zpm) 框架.
* [chgo](https://github.com/sbfaulkner/chgo-plugin-zsh) - 修改了 chruby 的克隆，以便在多个 Go 版本之间切换.
* [clean-project](https://github.com/wwilsman/zsh-clean-project) - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories.
* [clipboard](https://github.com/zpm-zsh/clipboard)  - 添加跨平台帮助函数来访问系统剪贴板. 适用于 macOS、X11（和 Wayland）和 Cygwin.
* [cmd-status](https://github.com/BlaineEXE/zsh-cmd-status) - Reports the status of commands including return code and duration.
* [cmdtime](https://github.com/tom-auger/cmdtime) - Displays the duration of a command to the terminal forked from the [timer](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) 插入.
* [code-review](https://github.com/xorkevin/code-review-zsh) - Launches `git difftool` on `git merge-base target_branch base_branch` and `target_branch`.
* [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - 计算按键并记录统计信息 [Code::Stats](https://codestats.net/).
* [codex](https://github.com/tom-doerr/zsh_codex) - Enables you to use OpenAI's powerful Codex AI in the command line.
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - 分叉自 [ohmyzsh/ohmyzsh/plugins/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh). Colorizes `man` output.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - 为“man”页面着色.
* [colorize](https://github.com/zpm-zsh/colorize) - Colorize the output of various programs.
* [colorls](https://github.com/Kallahan23/zsh-colorls) - Defines a few helpful shortcuts to some colorls functions.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - Enhanced colors for ZSH.
* [command-execution-timer](https://github.com/olets/command-execution-timer) - Displays the time an interactive shell command takes to execute.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) - oh-my-zsh command-not-found 插件的镜像，因此您不必包含所有 oh-my-zsh.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - Record complex commands and comment on them.
* [command-time](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in ZSH and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Similar to `REPORTTIME` builtin, but only outputs when user + system time >= `REPORTTIME`.
* [compe](https://github.com/tamago324/compe-zsh) - 添加完成 [nvim-compe](https://github.com/hrsh7th/nvim-compe).
* [completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script.
* [completion-zstyles](https://github.com/zshzoo/completion-zstyles) - 基于 Prezto 的 ZSH 补全的 Zstyle 设置.
* [copier](https://github.com/zshzoo/copier) - 来自 oh-my-zsh 的独立剪贴板实用程序.
* [copy-pasta](https://github.com/ChrisPenner/copy-pasta) - 在终端中复制和粘贴文件，就像在 GUI 中一样.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - 一个 ZSH 插件，用于通过 `ssh` 将你的 shell 配置复制到另一台机器.
* [crash](https://github.com/molovo/crash) - 为 ZSH 添加正确的错误处理、异常和 try/catch.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - ZSH syntax highlighting for the Crayon Plugin for Wordpress.
* [cros-auto-notify](https://github.com/D3STY/cros-auto-notify-zsh)  - 长时间运行的任务完成时自动发出通知. 适用于 macOS 和 linux（如果安装了 `hterm-notify`）.
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - 添加一个 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 以当前比特币价格细分.
* [crystal](https://github.com/veelenga/crystal-zsh) - 一个插件 [Crystal](https://github.com/crystal-lang/crystal).
* [czhttpd](https://github.com/jsks/czhttpd) - 一个用 99.9% 纯 ZSH 编写的简单 http 服务器.
* [declare-zsh](https://github.com/z-shell/declare-zsh) - A parser for zinit commands in `.zshrc`. It allows to perform the following actions on `.zshrc` from the command-line - enable and disable plugins add or remove snippets.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - 收集有用和有趣的命令，以改善工作流程和生活质量.
* [deer](https://github.com/Vifon/deer) - A file navigator for ZSH heavily inspired by [ranger](https://ranger.github.io/).
* [defer](https://github.com/romkatv/zsh-defer) - Defers execution of a `zsh` command until `zsh` has nothing else to do and is waiting for user input. Its intended purpose is staged `zsh` startup. It works similarly to Turbo mode in [zinit](https://github.com/zdharma-continuum/zinit).
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools)  - 用于安装 chromium depot_tools 的简单 oh-my-zsh 插件. 安装此插件将自动将所有 chromium depot_tools 放入您的路径中.
* [dev](https://github.com/sbfaulkner/dev-plugin-zsh) - 提供 Shopify 内部开发工具的轻量级版本
* [diff-so-fancy](https://github.com/z-shell/zsh-diff-so-fancy) - Installs [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) and enables its use in ZSH.
* [diractions](https://github.com/AdrieanKhisbe/diractions) - Allow you to map a short logical/mnemonic name to directories to quickly access them, or perform actions in them.
* [dircolors-solarized (joel-porquet)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin, with options for dark or light terminal backgrounds.
* [dircolors-solarized (pinelibg)](https://github.com/pinelibg/dircolors-solarized-zsh) - 启用 [Solarized Color Theme for GNU ls](https://github.com/seebi/dircolors-solarized).
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - 循环浏览目录堆栈.
* [directory-history](https://github.com/tymm/zsh-directory-history) - A per directory history for ZSH which implements forward/backward navigation as well as substring search in a directory sensitive manner.
* [direnv](https://github.com/ptavares/zsh-direnv) - 用于安装和加载的插件 [direnv](https://github.com/direnv/direnv.git) . 灵感来自 [zsh-pyenv](https://github.com/mattberther/zsh-pyenv).
* [dirrc](https://github.com/gmatheu/shell-plugins) - 当存在于你 `cd` 进入的目录中时执行 `.dirc`.
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - Plugin for displaying dirstack info on a single line.
* [doas (anatolykopyl)](https://github.com/anatolykopyl/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
* [doas (senderman)](https://github.com/Senderman/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
* [docker-aliases](https://github.com/webyneter/docker-aliases) Docker aliases for everyday use.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) 在提示中显示 docker 容器状态.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - docker 帮助脚本的集合.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) - A docker-machine plugin for ZSH.
* [docker-run](https://github.com/rawkode/zsh-docker-run) - 回到“自然”运行你的命令，我们将处理容器.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
* [dotbare](https://github.com/kazhala/dotbare) - Interactive dotfile management with the help of `fzf`.
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - 使用 `git` 使您的点文件在多台机器上保持同步.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - Automagically switch to a python virtual environment located (that you previously have created with virtualenv program) in a directory named `.pyvenv` when you `cd` into a directory.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for ZSH that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drupal](https://github.com/yhaefliger/zsh-drupal)  - 为常见任务添加别名，并为“drush”添加标签完成. 灵感来自 [Artisan](https://github.com/jessarcher/zsh-artisan).
* [dune-quotes](https://github.com/brokendisk/dune-quotes) - 随机沙丘报价生成器插件.
* [duration](https://github.com/rtakasuke/zsh-duration) - 如果超过用户可设置的运行时间，则显示命令持续时间.
* [dwim](https://github.com/oknowton/zsh-dwim)  - 尝试预测你下一步想要做什么. 它提供了一个键绑定 (control-u)，它将用您接下来要运行的命令替换当前（或上一个）命令行.
* [easy-motion](https://github.com/IngoHeimbach/zsh-easy-motion) - 一个港口 [vim-easymotion](https://github.com/easymotion/vim-easymotion) 对于 ZSH.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - List EC2 instances and `ssh` login to the instances easily.
* [editing-workbench](https://github.com/commiyou/zsh-editing-workbench) - 添加理智、复杂的命令行编辑（例如增量历史单词完成）.
* [edward cli](https://github.com/matthieusb/zsh-edward) - 添加智能完成和别名 [edward CLI micro-service launcher](https://github.com/yext/edward).
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - Adds shortcuts for Elixir, IEX, Mix, Kiex and Phoenix.
* [emacs (cowboyd)](https://github.com/cowboyd/zsh-emacs)  - 使 Emacs 成为 CLI 操作的默认设置，例如编辑 git 提交消息； 设置方便的别名.
* [emacs (flinner)](https://github.com/Flinner/zsh-emacs) - Uses the Emacs daemon capability, allowing the user to quickly open frames, whether they are opened in a terminal via a ssh connection, or X frames opened on the same host.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: 命令行上的表情符号补全.
* [emoji-fzf](https://github.com/pschmitt/emoji-fzf.zsh) - 优秀的可配置 ZSH 插件 [emoji-fzf](https://github.com/noahp/emoji-fzf). It is heavily inspired by [emoji-cli](https://github.com/b4b4r07/emoji-cli).
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) - 在方便的变量中添加大量 ascii 艺术表情符号到您的环境中.
* [enhancd](https://github.com/b4b4r07/enhancd) - 一个简单的工具，通过记住用户访问的所有目录并将其用于路径名解析来提供增强的“cd”命令.
* [envrc](https://github.com/fabiogibson/envrc-zsh-plugin) - 如果在目录中找到 `.envrc` 文件，则自动加载和卸载环境变量.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - 双击“`”时快速插入转义的反引号.
* [evalcache](https://github.com/mroth/evalcache) - Cache the output of a binary initialization command, to help lower shell startup time.
* [evil-registers](https://github.com/zsh-vi-more/evil-registers) - 扩展 ZLE vi 命令以远程访问 vim 和 nvim 编辑器的命名寄存器，以及系统选择和剪贴板.
* [exa (DarrinTisdale)](https://github.com/DarrinTisdale/zsh-aliases-exa) - Enables a number of aliases extending [exa](https://the.exa.website), `ls` 的现代替代品.
* [exa (hermitmaster)](https://github.com/hermitmaster/zsh-exa-plugin) - 添加一些别名 [exa](https://the.exa.website), `ls` 的现代替代品.
* [exa (mohamedelashri)](https://github.com/MohamedElashri/exa-zsh) - 添加别名 [exa](https://the.exa.website), `ls` 的现代替代品.
* [exa (ptavares)](https://github.com/ptavares/zsh-exa) - Installs and loads [exa](https://github.com/ogham/exa.git).
* [exa (ritchies)](https://github.com/RitchieS/zsh-exa/) - 添加别名以使用 [exa](https://github.com/ogham/exa.git) 更轻松.
* [exa-ls](https://github.com/birdhackor/zsh-exa-ls-plugin) - 添加别名以便您可以使用 [exa](https://the.exa.website) 作为 `ls` 和 `tree` 的替代品.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - 一个插件 [exercism.io](http://exercism.io/).
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - Expand specific aliases with space.
* [expand](https://github.com/MenkeTechnologies/zsh-expand) - 使用空格键扩展常规别名、全局别名、不正确的拼写和短语、glob、历史扩展和 $parameters.
* [expander](https://github.com/ianthehenry/zsh-expander) - 一个“zle”小部件，允许您编写自定义扩展器并选择它们 [fzf](https://github.com/junegunn/fzf).
* [explain-shell](https://github.com/gmatheu/shell-plugins) - Opens commands on [explainshell.com](https://explainshell.com).
* [extend-history](https://github.com/xav-b/zsh-extend-history) - 通过为历史记录中的每个命令添加退出代码来扩展命令历史记录.
* [f-shortcuts](https://github.com/zpm-zsh/f-shortcuts) - Makes a shortcuts toolbar using F1 to F12 keys.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of oh-my-zsh.
* [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips)  - 帮助记住您定义和忘记的别名. 移植自 [djui/alias-tips](https://github.com/djui/alias-tips).
* [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting) - Optimized and improved `zsh-users/zsh-syntax-highlighting` – better response times, switchable highlight themes.
* [fav](https://github.com/ddnexus/fav) - ZSH/[fzf](https://github.com/junegunn/fzf) 插件，使添加和调用重要目录的命名收藏夹变得非常容易.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - 快速跳转到您最喜欢的目录.
* [figures](https://github.com/zpm-zsh/figures) - ZSH 的 Unicode 符号.
* [firebase (Seqi)](https://github.com/Seqi/firebase-zsh) - 在 Firebase 项目目录或子目录中显示当前工作项目或项目别名.
* [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) - 在提示中添加一个指示符，表明您位于具有 `firebase.json` 文件（又名“firebase 项目”）的目录中.
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - Enables numpad keys of Apple keyboards to be recognized in ZSH.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - 这个插件在 TYPO3 Flow 发行版的每个子目录中都可以使用 `flow` 命令.
* [fnm](https://github.com/dominik-schwabe/zsh-fnm) - Installs and loads the [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) 如果它丢失了.
* [forgit](https://github.com/wfxr/forgit) - Utility tool for `git` which takes advantage of fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [functional](https://github.com/Tarrasch/zsh-functional) - ZSH 高阶函数.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line.
* [fuzzy-wd](https://github.com/spodin/zsh-fuzzy-wd) - 添加模糊搜索扭曲的目录 [WD](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/wd) 插入.
* [fz](https://github.com/changyuheng/fz) - 无缝添加模糊搜索 [z](https://github.com/rupa/z)'s tab completion and lets you easily jump around among directories in your history.
* [fzf (unixorn)](https://github.com/unixorn/fzf-zsh-plugin/tree/master) - 启用 [fzf](https://github.com/junegunn/fzf) history and file searches.
* [fzf-fasd](https://github.com/wookayin/fzf-fasd) - Integrates [fzf](https://github.com/junegunn/fzf) 和 [fasd](https://github.com/clvv/fasd) --- tab completion of `z` with fzf's fuzzy search!
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - 插件有一个很酷的搜索键绑定 [fzf](https://github.com/junegunn/fzf) 和（可选） [bat](https://github.com/sharkdp/bat). Searches in the local tree of subdirectories for files.
* [fzf-history-search](https://github.com/joshskidmore/zsh-fzf-history-search) - 将 `Ctrl+R` 替换为 [fzf](https://github.com/junegunn/fzf)- 驱动的历史搜索，包括日期/时间.
* [fzf-it](https://github.com/micakce/fzf-it) - Make any command interactive wrapping it with FZF functionality.
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) - 使用模糊查找器在 `bash` 和 `zsh` 中创建、导航和删除书签的小脚本 [fzf](https://github.com/junegunn/fzf).
* [fzf-pass](https://github.com/smeagol74/zsh-fzf-pass) - Better h和ling of passwords using [fzf](https://github.com/junegunn/fzf) 和 [pass](https://www.passwordstore.org/).
* [fzf-prezto](https://github.com/lildude/fzf-prezto) - Prezto plugin that finds where [fzf](https://github.com/junegunn/fzf) 已安装并启用其自动完成和键绑定. 这个插件作为 Prezto `zstyle` 配置选项工作.
* [fzf-tab](https://github.com/Aloxaf/fzf-tab) - 将 ZSH 的默认补全选择菜单替换为 [fzf](https://github.com/junegunn/fzf).
* [fzf-utils](https://github.com/redxtech/zsh-fzf-utils) - Provides functions to kill proceses and find in path with [fzf](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - Adds some ZLE widgets for [fzf](https://github.com/junegunn/fzf).
* [fzf-z](https://github.com/andrewferrier/fzf-z) - 将 *z* 插件和 *fzf* 结合在一起，让您可以在命令行的任何位置轻松浏览最近使用的目录.
* [fzy](https://github.com/aperezdc/zsh-fzy) - Plugin that uses [fzy](https://github.com/jhawthorn/fzy) 对于某些模糊匹配操作.
* [gcloud-project](https://github.com/avivl/gcloud-project) - Easy selection of Google Cloud Projects.
* [gdbm](https://github.com/zdharma-continuum/zgdbm) - Adds GDBM as a plugin.
* [geeknote](https://github.com/s7anley/zsh-geeknote) - [Geeknote](https://geeknote.me) ZSH 插件.
* [gentoo](https://github.com/MattiaG-afk/gentoo-ohmyzsh) - 添加一些别名和函数以与 Gentoo Linux 一起使用.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) datetime plugin. Shows datetime (`date` unix command) in your prompt.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) 提醒您补水的插件.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) 显示当前文件夹的 npm 包版本的插件.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's Rust version when either a `.rs` or `Cargo.toml` is present.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - 用于快速下载 jQuery 库的插件 [https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com](https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com).
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - 让您使用 [zeus](https://github.com/burke/zeus) 使用普通的 rails 命令.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - Manage Go installations with gimme.
* [git-acp](https://github.com/MenkeTechnologies/zsh-git-acp) - Take the current command line as the commit message and then run git pull, add, commit and push with one keystroke.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) - 轻松将上游远程添加到您的 `git` 叉.
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of oh-my-zsh.
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used `git` commands.
* [git-branches](https://github.com/Schroefdop/git-branches) - 制作一个 `git` 分支菜单，您可以切换到该菜单，而无需输入长分支名称.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - Enhance `git` completion to include in the remotes completion (e.g. from `git clone`) any URL in the clipboard.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Extra `git` helper scripts packaged as a plugin.
* [git-flow-avh](https://github.com/nekofar/zsh-git-flow-avh) - 为 `git-flow` 命令添加短别名.
* [git-fuzzy](https://github.com/bigH/git-fuzzy) - A CLI interface to `git` that relies heavily on [`fzf`](https://github.com/junegunn/fzf).
* [git-ignore](https://github.com/laggardkernel/git-ignore) - Generates `.gitignore` files from gitignore.io **offline**. `fzf`, completion, preview integrated.
* [git-is-clean](https://github.com/aubreypwd/zsh-plugin-git-is-clean) - This function will return true or false depending on if it finds out your repo is dirty or not.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub.
* [git-lfs](https://github.com/nekofar/zsh-git-lfs) - Adds short aliases for the git-lfs commands.
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - 为 `git` 添加了一些功能.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for `git` user.email.
* [git-prune (diazod)](https://github.com/diazod/git-prune) - Allows you to delete all branches that are already merged in your local repository and/or that were merged in your remote origin repository.
* [git-prune (seinh)](https://github.com/Seinh/git-prune) - Plugin that simplifies deleting merged branches.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) - 添加 `git-squash-branch` 和 `git-remove-merged` 命令.
* [git-secret](https://github.com/sobolevn/git-secret) - 一个 bash 工具，用于将您的私人数据存储在 `git` 存储库中.
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - Adds extra `git` commands to make some common `git` usages more efficient.
* [git-sync](https://github.com/caarlos0/zsh-git-sync) - A ZSH plugin to sync `git` repositories and clean them up.
* [git-worktree](https://github.com/alexiszamanidis/zsh-git-worktree)  - 包装一些 `git worktree` 操作以简化和提高生产力. 包括“fzf”工具.
* [git](https://github.com/davidde/git)  - 替换股票 oh-my-zsh git 插件. 提供了不少有用的别名和函数. 替换默认插件的动机源于它带有一些不一致的事实，这使得一些流行的命令相当不直观，所以这个插件使别名保持一致.
* [gitcd (SukkaW)](https://github.com/SukkaW/zsh-gitcd) - 将命令添加到 `git clone` 存储库和 `cd` 到结果目录.
* [gitcd (viko16)](https://github.com/viko16/gitcd.plugin.zsh) - Automatically `cd` to a `git` working directory after cloning it.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of oh-my-zsh gitfast plugin.
* [gitgo (grimmbraten)](https://github.com/grimmbraten/gitgo) - 更容易在 `git` 分支之间切换.
* [gitgo (ltj)](https://github.com/ltj/gitgo) - 从命令行在浏览器中打开 Github/Gitlab 存储库（仅限 macOS）.
* [github](https://github.com/shakir-abdo/zsh-github-plugin) - 原叉 [github plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/github) embedded in [oh-my-zsh](http://ohmyz.sh/).
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - Plugin for creating `.gitignore` files.
* [gitio](https://github.com/denysdovhan/gitio-zsh) - 用于生成 GitHub 短 URL 的 ZSH 插件 [git.io](https://git.io).
* [gitstatus](https://github.com/Insert-Creative-Name-Here/gitstatus.zsh) - 可以轻松地在提示中显示您的 `git` 状态.
* [gitsync](https://github.com/washtubs/gitsync) - ZSH 插件可改善一个人在多台机器上的同一存储库上开发的工作流程.
* [goenv (CDA0)](https://github.com/CDA0/zsh-goenv/blob/master/zsh-goenv.plugin.zsh) - 用于安装、更新和加载 goenv 的插件.
* [goenv (bbenne10)](https://github.com/bbenne10/goenv) - Manage `$GOPATH` similarly to Python's virtualenvwrapper.
* [going_places](https://github.com/or17191/going_places) - 一个有助于使用、创建和维护 shell 位置列表的插件.
* [golinks](https://github.com/slessans/oh-my-zsh-golinks-plugin) - Launch golinks from your terminal.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - 在设置 GPG 代理以在 macOS 上也充当 SSH 代理时尝试做正确事情的插件.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) - ZSH 插件用于加密和解密文件或目录.
* [grep2awk](https://github.com/joepvd/grep2awk) - ZLE 小部件将 `grep` 命令转换为 `awk` 命令.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for `grunt`.
* [gsh](https://github.com/cjayross/gsh) - Collection of helper functions for `git`
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - 终端插件 [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [gtr](https://github.com/Zocker1999NET/zsh-gtr) - Allows fast tagging of a release in git using the tag name **release-YYYY-MM-DD-HH-MM** and headline **Release YYYY-MM-DD HH:MM**.
* [guish](https://github.com/gcarrarom/oh-my-guish) - 实用函数和别名的集合.
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - 包装器插件 [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
* [gunstage](https://github.com/LucasLarson/gunstage)  - 至少有八种方法可以在 `git` 存储库中取消暂存文件. 这是一个用于撤消 `git add` 的命令行 shell 插件.
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - A gvm (Go version manager) plugin for ZSH.
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - 为“gvm”（Groovy 环境管理器）提供自动完成功能.
* [hab](https://github.com/alexdesousa/hab) - 如果在更改到新目录时发现文件`.envrc` 中定义的操作系统环境变量，则自动加载它.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - 打开终端时随机输出黑客报价.
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - 为 hadoop 函数添加一些方便的别名.
* [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH plugin for [hanami](http://hanamirb.org) 项目.
* [hangul](https://github.com/gomjellie/zsh-hangul)  - 自动将韩文（韩文，韩文）更正为英文，而应该输入英文. 你必须输入英文，但如果你输入韩文，它会自动更正.
* [hbt](https://github.com/lzambarda/hbt) - Heuristic ZSH suggestion system based on past command usage.
* [hints](https://github.com/joepvd/zsh-hints) - 在您的编辑缓冲区下显示全局和参数标志以及其他不可完成的信息.
* [hipchat](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell.
* [hist](https://github.com/marlonrichert/zsh-hist) - Edit your history in ZSH, without ever leaving the command line.
* [histdb](https://github.com/larkery/zsh-histdb) - Stores your history in an SQLite database. Can be integrated with [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions).
* [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer)  - 通过更多交互和多行选择菜单增强历史搜索. 需要nodejs.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter) - Allows you to specify patterns that will automatically exclude commands from being inserted into your permanent history. Particularly useful for preventing secrets being written.
* [history-here](https://github.com/leonjza/history-here) - Binds `^G` to quickly toggle the current shell history file location.
* [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) - 捕获 PageUp 键并使用“对话框”打开带有历史记录的弹出菜单，因此用户可以交互地浏览它并选择历史记录行以返回提示.
* [history-search-multi-word](https://github.com/zdharma-continuum/history-search-multi-word) - ZSH 的语法突出显示的多词历史搜索器，绑定到 Ctrl-R，具有高级功能（例如，将历史条目撞到历史顶部）.
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search)  - 需要在 `zsh-syntax-highlighting` 之后加载，否则它们都会中断. 您还需要将键绑定到其功能，详细信息在 README.md 中.
* [history-sync](https://github.com/wulfgarpro/history-sync) - 一个 Oh My Zsh 插件，用于使用 `git` 加密的 GPG、Internet 同步 ZSH 历史记录.
* [history](https://github.com/b4b4r07/zsh-history) - 扩展历史，使其可以被 SQL 查询.
* [hitokoto](https://github.com/derry96/hitokoto) - Displays a random quote from [hitokoto.cn](https://hitokoto.cn/).
* [homeassistant-cli](https://github.com/frosit/zsh-plugin-homeassistant-cli) - 为 [Home Assistant Command-line interface (hass-cli)](https://github.com/home-assistant/home-assistant-cli). and allows command line interaction with [Home Assistant](https://home-assistant.io/) 实例.
* [homebrew](https://github.com/digitalraven/omz-homebrew) - Plugin for [homebrew](https://brew.sh) that supplements the one built into oh-my-zsh and can safely run with it enabled.
* [hooks](https://github.com/willghatch/zsh-hooks) - Add missing hooks - for plugins and personal use.
* [host-switch](https://github.com/LockonS/host-switch) - 在开发过程中更容易切换不同的 `/etc/hosts` 文件.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - A simple plugin for adding `hub` ci-status to your ZSH theme.
* [hub](https://github.com/soraliu/zsh-hub) - 用于分叉模型的 ZSH 插件.
* [igit](https://github.com/ytakahashi/igit) - Interactive `git` commands using [fzf](https://github.com/junegunn/fzf).
* [ing](https://github.com/rummik/zsh-ing) - 简化的“ping”输出.
* [instant-repl](https://github.com/jandamm/instant-repl.zsh) - Activate a REPL for any command in your current ZSH session.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - Fish-like interactive tab completion for `cd`.
* [iosctl](https://github.com/obayer/iosctl) - 快速访问正在运行的模拟器的应用程序、数据和日志.
* [ipip](https://github.com/SukkaW/zsh-ipip) - Plugin for [IPIP](https://en.ipip.net).
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - 在iTerm2中增加了设置标签颜色的功能，可以根据cwd或正在执行的命令自动改变颜色.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - Automatically changes iTerm 2 tab color based on the current working directory.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - 在 MacbookPro TouchBar 中显示 iTerm2 反馈（当前目录、git 分支和状态）.
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - Manage your iTerm 2's color scheme from the command line.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - Set colors and titles of iTerm 2 tabs.
* [iterm2-utilities](https://github.com/decayofmind/zsh-iterm2-utilities) - 帮助下载各种 iTerm2 实用程序，并让您省略整个 iterm2 网站存储库的克隆或依赖可能不同步的其他存储库.
* [iterm2](https://github.com/laggardkernel/zsh-iterm2) - 将 iTerm 的 ZSH 集成脚本打包到 ZSH 插件中，以避免污染您的 $HOME 目录，仅增加 2ms 的时间可以忽略不计.
* [jabba](https://github.com/2m/zsh-jabba) - 添加外壳集成代码和完成 [jabba](https://github.com/shyiko/jabba) Java 版本管理器.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - 添加 `setjdk` 命令，以便您可以在 jdk 的不同版本之间轻松切换.
* [javaVersions](https://github.com/miguefl/javaVersions) - Change between different java versions with a single command.
* [jdk-switch](https://github.com/LockonS/jdk-switch) - A macOS-only plugin for switching between jdk versions.
* [jenkins](https://github.com/tomplex/jenkins-zsh) - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - 用于延迟加载 jEnv 的 ZSH 插件.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - Adds commands for [jHipster](https://www.jhipster.tech/).
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - 从命令行创建 JIRA 票证.
* [jq (northismirror)](https://github.com/NorthIsMirror/jq-zsh-plugin) - 交互式构建 [jq](https://stedolan.github.io/jq/) 给你“jq”超能力的表达方式.
* [jq (reegnz)](https://github.com/reegnz/jq-zsh-plugin) - 交互式构建 [jq](https://stedolan.github.io/jq/) 表达式.
* [jvm](https://github.com/mgryszko/jvm) - 允许在 macOS 上选择 JDK.
* [k3d](https://github.com/dwaynebradley/k3d-oh-my-zsh-plugin) - 添加别名和选项卡完成 [k3d](https://k3d.io/).
* [k](https://github.com/supercrabtree/k) - Directory listings for ZSH with `git` status decorations.
* [kctl](https://github.com/yzdann/kctl) - Add helper aliases for `kubectl`.
* [kill-node](https://github.com/vmattos/kill-node) - ZSH plugin for murdering `node` process families.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - 用于 oh-my-zsh 的 KitsuneBook 插件.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
* [kube-aliases](https://github.com/Dbz/kube-aliases) - 添加函数和别名以使使用 `kubectl` 更加愉快.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - ZSH plugin for `kubectl` that adds current context and namespace.
* [kubecolor (devopstales)](https://github.com/devopstales/kubecolor-zsh) - Adds aliases for the `kubecolor` command.
* [kubecolor (droctothorpe)](https://github.com/droctothorpe/kubecolor) - Simplify and colorize the output of `kubectl get events -w`
* [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) - 用于管理 `kubectl` 的 ZSH 插件.
* [kubectx (ptavares)](https://github.com/ptavares/zsh-kubectx) - Installs and loads [kubectx](https://github.com/ahmetb/kubectx).
* [kubectx (unixorn)](https://github.com/unixorn/kubectx-zshplugin) - 自动安装 [kubectx](https://github.com/ahmetb/kubectx) 和`kubens`.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) - 添加 [kubernetes](https://kubernetes.io) helper functions and aliases.
* [lando (joshuabedford)](https://github.com/JoshuaBedford/lando-zsh) - 一组别名函数，用于启用 CLI [Lando](https://docs.lando.dev) 无需键入lando 即可访问它们.
* [lando (mannuel)](https://github.com/mannuel/lando-alias-zsh) - 为各种添加别名 [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) 命令.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - Provides an interface to [Laradock](http://laradock.io/)的工作区.
* [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) - 为 Laravel 6 添加别名.
* [laravel-sail](https://github.com/ariaieboy/laravel-sail) - 添加 `sail` 命令的快捷方式.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - Add shortcuts for Laravel 5, 5.1, 5.2 & 5.3.
* [laravelx](https://github.com/rsthegeek/oh-my-zsh-laravelx) - Adds some aliases for common [Laravel](https://laravel.com/docs) 命令.
* [last-working-dir-tmux](https://github.com/Curly-Mo/last-working-dir-tmux) - Keeps track of the last used working directory globally and per tmux session and automatically jumps into it for new shells.
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) - 破解版本的副本 [oh-my-zsh](http://ohmyz.sh/) . 跟踪上次使用的工作目录并自动跳转到新的 shell.
* [lazyload](https://github.com/qoomon/zsh-lazyload) - Lazy load commands and speed up start up time of ZSH.
* [learn](https://github.com/MenkeTechnologies/zsh-learn) - MySQL/MariadB 中的学习集合，用于保存、查询和测验您学到的所有内容.
* [lesaint-git](https://github.com/lesaint/lesaint-git) - 替换 Oh-My-Zsh 兼容框架的 `git` 插件.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - 用于 oh-my-zsh 的 Maven 插件.
* [liferay](https://github.com/david-gutierrez-mesa/liferay-zsh) - Adds scripts for [liferay](https://github.com/liferay/liferay-portal) 发展.
* [linkfile](https://github.com/JaumeRF/linkfile-zsh) - 为您喜爱的目录添加快捷方式.
* [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) - 打开终端时输出随机的 Linus Torvalds 咆哮。
* [listbox](https://github.com/gko/listbox) - Listbox element for shell.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - Allows searching for [Sublime Text](https://www.sublimetext.com) projects and opens them in Sublime.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum)  - 在命令行上生成 lorem ipsum 文本. 从中获取数据 [lipsum.com](https://www.lipsum.com).
* [ls](https://github.com/zpm-zsh/ls) - Colorizes the output of `ls`.
* [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack 是一个用于 shell 脚本的日志接口.
* [lux](https://github.com/pndurette/zsh-lux)  - ZSH 插件可通过“lux”命令切换 macOS 和其他项目和应用程序的明暗模式. 高度可定制：可以通过定义变量来配置包含的项目. 高度可扩展：可以通过定义函数来添加项目. 包括 `macos_is_dark` 辅助函数以确定 macOS 暗模式是否处于活动状态以用于主题化.
* [mac-packaging](https://github.com/Temikus/mac-packaging) - 一组用于企业 Mac 打包的常用功能 [Munki](https://www.munki.org/munki/).
* [macos (joow)](https://github.com/joow/macos) - A ZSH plugin for macOS.
* [macos (zshzoo)](https://github.com/zshzoo/macos) - 适用于 MacOS 用户的 ZSH 好东西.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) - 使使用 Docker 和 Magento 2 变得容易.在 Magento 2 容器上加速和简化常见命令，如清理缓存、设置升级、编译 di 等等.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - 添加 `m2` 函数来运行 magento 二进制文件，添加选项卡完成.
* [magic-enter](https://github.com/zshzoo/magic-enter) - 通过将 ZSH 命令绑定到它来使您的输入键变得神奇.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) - A zle tweak for emulating `...'==`../..' etc.
* [markedit](https://github.com/zakariaGatter/MarkEdit) - 标记文件并使用现有标记的自动完成对其进行编辑.
* [markgate](https://github.com/zakariaGatter/MarkGate) - 允许您标记目录，以便您可以直接跳转到它们.
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - oh-my-zsh maven 插件的一个分支.
* [media-sync](https://github.com/redxtech/zsh-media-sync) - 一个便于在两个 rclone 位置之间复制媒体的插件.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) - 从 oh-my-zsh 中提取，因此您可以在没有 oh-my-zsh 的情况下使用它.
* [mfunc](https://github.com/hlohm/mfunc)  - 允许您动态定义持久性函数，而无需将它们添加到您的配置文件中. 这些功能永久可用，直到您将其删除.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - 一个 ZSH 插件，用于在普通模式和 `vi` 模式之间切换命令行.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - 用于 monorepo 管理的 ZSH 插件.
* [monthrename](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) - Renames month names to numbers in filenames.
* [mouse-status](https://github.com/gryffyn/mouse-status) - 根据状态码更改鼠标颜色，使用 libratbag.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - Metasploit handler plugin for starting handlers easily.
* [mvn-contexts](https://github.com/artemy/zsh-mvn-contexts) - Allows fast switching between maven configurations.
* [mylocation](https://github.com/fALKENdk/mylocation) - A plugin to show your current location based on your IP address.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - 为 mysql 表添加颜色.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - 增加了一些处理mysql的函数.
* [n](https://github.com/gretzky/n.zsh) - 使用基于项目环境的自动切换节点版本 [n](https://github.com/tj/n).
* [namelink](https://github.com/jthat/zsh-namelink) - 提供一组目录中的文件系统条目（通常是符号链接）到命名目录哈希中的对应项的自动同步映射.
* [navi](https://github.com/icatalina/zsh-navi-plugin/) - Plugin for [navi](https://github.com/denisidoro/navi).
* [navigation-tools](https://github.com/zdharma-continuum/zsh-navigation-tools) - Adds `htop`-like kill, directory bookmarks browser, a multi-word incremental history searcher and more.
* [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) - 从模板生成文件.
* [newvwp](https://github.com/aubreypwd/zsh-plugin-newvwp) - 使用 Valet 启动一个新的 WordPress 网站.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - 将退出状态代码映射到人类可读的字符串.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) - 允许您在 `nix-shell` 环境中使用 ZSH 作为默认 shell 的插件.
* [nnvm](https://github.com/torifat/nnvm)  - 基于 `.nvmrc` 自动切换节点版本. 需要 [n](https://github.com/tj/n).
* [node-env-installer](https://github.com/shiro-saber/node-env-installer) - 使用 `nvm` 为当前项目安装新版本和模块.
* [node-path](https://github.com/andyrichardson/zsh-node-path) - Automatically adds the "npm bin" of your current directory to your path.
* [node](https://github.com/srijanshetty/node.plugin.zsh) - 用于 ZSH 的 Srijan Shetty 的 nodejs 插件，具有缓存“nvm”完成和自动加载“nvm”（如果存在）.
* [nodenv (c-uo)](https://github.com/C-uo/zsh-nodenv) - Looks for nodenv in your working directory and loads it when found.
* [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) - 自动加载 `nodenv` 及其完成到 shell.
* [nodenv (mattberther)](https://github.com/mattberther/zsh-nodenv)  - 安装、更新和加载“nodeenv”. 灵感来自 zsh-rbenv.
* [nohup](https://github.com/micrenda/zsh-nohup) - 按 `Ctrl-H` 将`nohup` 添加到当前命令.
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS 用户知道试图找出在他们的 macOS 版本上实际刷新 DNS 缓存的命令的痛苦，而这个插件让这种烦恼消失了.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - 灵感来自 [terminal_velocity](https://www.seanh.cc/terminal_velocity/)，它提供了一个快速的接口来创建和访问一组 [Markdown](https://en.wikipedia.org/wiki/Markdown) text files inside a directory.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - 在 ZSH 中提供快速的笔记编辑体验.
* [notify (luismayta)](https://github.com/luismayta/zsh-notify) - Notifications for ZSH with auto installation of dependencies and r2d2 sounds.
* [notify (marzocchi)](https://github.com/marzocchi/zsh-notify) - ZSH 的插件（在 macOS 和 Linux 上），如果终端应用程序在后台（或命令的终端），当命令以非零退出状态终止或完成时间超过 30 秒时发布桌面通知选项卡处于非活动状态）.
* [npm (igoradamenko)](https://github.com/igoradamenko/npm.插入.zsh) - Add `npm` aliases & command completion. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npm (trystan2k)](https://github.com/trystan2k/zsh-npm-plugin) - Adds `npm` aliases. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npm (zfben)](https://github.com/zfben/zsh-npm) - Use `n` as `npm` aliases with `noglob` prefix and more. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npms](https://github.com/torifat/npms)  - 由 `fzf` 提供支持的实用程序，用于交互式使用 npm 脚本. 需要 [fzf](https://github.com/junegunn/fzf) 和 [jq](https://stedolan.github.io/jq/).
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - Calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling `nvm` which node to use.
* [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy)  - 用于延迟加载 oh-my-zsh 的 **nvm** 插件的插件. 它支持为多个二进制/入口点延迟加载“nvm”，默认值为“nvm”、“node”和“npm”.
* [nvm](https://github.com/lukechilds/zsh-nvm) - ZSH plugin for installing, updating and loading `nvm`.
* [oath](https://github.com/alexdesousa/oath)  - 管理 2FA 身份验证 6 位令牌. 这篇文章深受启发 [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
* [oclif completion generator](https://github.com/MunifTanjim/oclif-plugin-completion) - Generates shell completions for commands lacking them.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - 把你的终端变成矩阵.
* [omz-themes-standalone](https://github.com/zshzoo/omz-themes-standalone) - Gives you the [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) themes without requiring everything else that comes with oh-my-zsh
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) - Open/Create projects in Jetbrains.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) - 从命令行打开拉取请求的 ZSH 插件.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - Add a few shortcuts to common openshift origin (oc) actions.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` aliases.
* [operator](https://github.com/nivv/operator-theme) - 干净简单的主题，最适合搭配 [Menlo for Powerline](https://github.com/abertsch/Menlo-for-Powerline).
* [opp](https://github.com/hchbaw/opp.zsh) - 用于 ZSH 的 Vim 的 text-objects-ish.
* [opt-path](https://github.com/jreese/zsh-opt-path) - Automatically add `~/opt` subpaths to your `$PATH`.
* [osx-autoproxy](https://github.com/SukkaW/zsh-osx-autoproxy) - 根据 macOS 的系统偏好配置代理环境变量.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - 此插件添加了一些命令，用于在 macOS 安装上维护各种服务器程序.
* [osx](https://github.com/mwilliammyers/plugin-osx) - Add some common macOS related aliases and functions.
* [p10k-promptconfig](https://github.com/doctormemes/p10k-promptconfig) - 通过在 `.zshrc` 文件中定义 `P10K_PROMPT` 变量，添加了在 Powerlevel10k 提示主题配置文件之间轻松切换的能力.
* [paci](https://github.com/iloginow/zsh-paci) - Plugin for archlinux package managers.
* [package-any-node](https://github.com/zdharma-continuum/zsh-package-any-node) - 在插件目录中轻松安装任何节点模块，通过由自动创建的垫片（即：转发器脚本）公开其二进制文件 [Bin-Gem-Node](https://github.com/zdharma-continuum/z-a-bin-gem-node) annex.
* [packer](https://github.com/BreakingPitt/zsh-packer) - Adds aliases and auto-completes for Hashicorp [packer](https://www.packer.io/).
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin)  - 长时间运行命令的后台通知. 支持 Elementary OS Freya.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) - 防止密码进入您的命令行历史记录.
* [path-ethic](https://github.com/sha1n/path-ethic)  - 帮助快速轻松地管理您的“$PATH”. 不会触及现有的 `.zshrc`、`.zprofile`，而是添加到现有环境之上.
* [pctl](https://github.com/ytet5uy4/pctl) - 切换环境变量以进行代理.
* [peco-history](https://github.com/jimeh/zsh-peco-history) - 按 ctrl+R 时使用 Peco 搜索 shell 历史记录.
* [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) - Aliases and functions for the lazy penetration tester.
* [per-directory-history](https://github.com/jimhester/per-directory-history) - ZSH 的每个目录历史记录，以及全局历史记录，以及使用 `^G` 在它们之间切换的能力.
* [percol](https://github.com/robturtle/percol.plugin.zsh) - Interactively and incrementally search history/resume background jobs using [percol](https://github.com/mooz/percol).
* [perlbrew](https://github.com/tfiala/zsh-perlbrew/) - Installs [perlbrew](https://perlbrew.pl/) if not already installed and initializes it for your shell.
* [pew](https://github.com/shosca/zsh-pew) - 使用设置和管理 Python virtualenvs [pew](https://github.com/berdario/pew), automatically switches virtualenvs as you move directories.
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) - 添加实用功能以使用 [PostgreSQL](https://www.postgresql.org/).
* [ph-marks](https://github.com/lainiwa/ph-marks) - 从您的终端为pornhub 视频添加书签.
* [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) - Automatically switch between php versions using [php-version](https://github.com/wilmoore/php-version) 如果目录中存在 rc 文件.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - Plugin for [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) - 自动加载 [phpenv](https://github.com/sptndc/phpenv) 及其完成.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - Plugin for [PHPUnit](https://phpunit.de/).
* [pip-app](https://github.com/sharat87/pip-app) - 可以轻松地将 python 应用程序安装到不同的 Python virtualenvs 中，这样它们就不会与系统上的任何其他 python 要求冲突.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) - 自动 [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a pipenv project.
* [pipx](https://github.com/thuandt/zsh-pipx) - Autocompletions for [pipx](https://github.com/pypa/pipx).
* [pkenv](https://github.com/ptavares/zsh-pkenv) - Installs and loads [pkenv](https://github.com/iamhsa/pkenv.git)
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - 添加 ibtool 快捷方式以生成本地化的 XIB 文件.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Visual Studio Code 插件，一个适用于 macOS、Windows 和 Linux 的文本编辑器.
* [plugin](https://github.com/darrenbutcher/plugin)  - 从样板模板创建自定义 oh-my-zsh 插件. 非常以 oh-my-zsh 为中心，生成的插件需要编辑才能与其他框架一起使用.
* [pnpm](https://github.com/ntnyq/omz-plugin-pnpm) - Adds useful aliases for common Pnpm commands.
* [poetry (darvid)](https://github.com/darvid/zsh-poetry) - Automatically activates and deactivates [Poetry](https://poetry.eustace.io/)- 创建了 python virtualenvs.
* [poetry (sudosabin)](https://github.com/sudosubin/zsh-poetry) - Enables poetry `$PATH` and autocompletions.
* [posh-git-bash](https://github.com/lyze/posh-git-sh) - Adds `git` status in your prompt.
* [ppsmon](https://github.com/mzpqnxow/ppsmon)  - 读取 `/sys/class/net/$interface/` 以跟踪数据包传输速率. 它将当前速率存储到 RAM 支持的文件系统中的文件中，在该文件系统中可以轻松访问它以在 shell 提示中显示. 由于使用了 `/sys`，因此仅适用于 Linux.
* [pr-cwd](https://github.com/zpm-zsh/pr-cwd) - Creates a global variable with current working directory. Plugin has integration with [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
* [pr-eol](https://github.com/zpm-zsh/pr-eol) - 显示可以嵌入到提示中的 EOL 符号.
* [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) - Adds a variable you can use to display the execution time of the last command run.
* [pr-git](https://github.com/zpm-zsh/pr-git) - 创建一个带有 `git` 状态信息的全局变量，可以在提示中显示.
* [pr-is-root](https://github.com/zpm-zsh/pr-is-root) - Sets an environment variable you can use in a custom prompt when running as root.
* [pr-jobs](https://github.com/zpm-zsh/pr-jobs) - Creates an environment variable which can be used to display background job information in a custom prompt.
* [pr-node](https://github.com/zpm-zsh/pr-node) - Sets an environment variable which can be used to display nodeJS information in a custom prompt.
* [pr-return](https://github.com/zpm-zsh/pr-return) - ZSH 插件，显示最后一次命令运行的退出状态.
* [presenter-mode](https://github.com/idadzie/zsh-presenter-mode) - Expands aliases during presentations. It also increases the terminal window's contrast to enhance visibility.
* [pretty-time (sindresorhus)](https://github.com/sindresorhus/pretty-time-zsh) - 将秒转换为人类可读的字符串：165392 → 1d 21h 56m 32s.
* [pretty-time (zpm-zsh)](https://github.com/zpm-zsh/pretty-time) - Converts raw seconds into human-readable strings.
* [print-alias](https://github.com/brymck/print-alias) - Prints commands with aliases expanded whenever you use an alias at the command line.
* [printc](https://github.com/philFernandez/printc) - 允许您通过简单的“printc”调用以 RGB 空间中的任何颜色进行打印.
* [profile-secrets](https://github.com/gmatheu/shell-plugins)  - 将敏感变量（api 令牌、密码等）安全地保存为终端初始化文件的一部分. 使用 gpg 使用您的秘密加密/解密文件.
* [project (gko)](https://github.com/gko/project) - Create node/python/ruby project both locally and on github(private or public repository).
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - Plugin for managing projects.
* [prompt-generator](https://github.com/the10thWiz/zsh-prompt-generator) - Generates custom themes. Some generated themes require powerline-compatible fonts.
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - Quickly enable and disable proxy shell environment settings.
* [proxy](https://github.com/SukkaW/zsh-proxy) - Configure proxy settings for some package managers and software.
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - Plugin for lazy-loading `pyenv` in ZSH.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy)  - 延迟加载 pyenv. 第一次调用 `pyenv` 时执行初始的 `eval &quot;$(pyenv init -)&quot;`.
* [pyenv](https://github.com/mattberther/zsh-pyenv)  - 受 zsh-rbenv 启发. 安装、更新或加载 `pyenv`，并添加额外的功能.
* [pyvenv-fast](https://github.com/ACmyles/pyvenv-fast) - Launch a Python venv with one command. Designed for use with [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv).
* [q (cal2195)](https://github.com/cal2195/q) - 将 `vim` 类宏寄存器添加到您的 ZSH shell.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - Tail/remove the temp file for [Q](https://github.com/y0ssar1an/q)，脏调试工具.
* [qiime2](https://github.com/misialq/zsh-qiime2) - 添加函数和别名以便使用 [Quiime 2](https://qiime2.org/) 更轻松.
* [quer-ps1](https://github.com/ya0201/qwer-ps1) - A highly extendable manager for your ZSH prompt
* [quoter](https://github.com/pxgamer/quoter-zsh) - Display a random quote when opening a new terminal session.
* [quotify](https://github.com/damofthemoon/zsh-quotify) - Displays inspiring coding quotes from our pairs when starting up.
* [randeme](https://github.com/ex-surreal/randeme)  - 为每个会话选择一个随机主题. 如果您不喜欢所选主题，您可以运行 `randeme_rm` 以不再显示该主题.
* [random-quotes](https://github.com/vkolagotla/zsh-random-quotes) - 显示随机报价或事实.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - Change the colour of your [Razer Mouse](https://openrazer.github.io/) 基于最后执行的命令的状态. 需要 [OpenRazer](https://openrazer.github.io) linux drivers.
* [rbenv (ecortinas)](https://github.com/ecortinas/zsh-rbenv) - 基于 [zsh-pyenv](https://github.com/mattberther/zsh-pyenv) 插入. 该插件将安装 rbenv 并使其随时可用
* [rbenv (elliottcable)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - 来自 oh-my-zsh 的 rbenv 插件的更快分支.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - Variant based on the original oh-my-zsh rbenv plugin.
* [rbenv (meroje)](https://github.com/Meroje/zsh-rbenv) - 灵感来自 [https://github.com/lukechilds/zsh-nvm/](https://github.com/lukechilds/zsh-nvm/), makes it easier to work with ruby rbenvs.
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
* [rust](https://github.com/cowboyd/zsh-rust) - 配置你的 rust 工具链，安装 [rustup](https://rustup.rs) if it is not currently installed already.
* [rvm](https://github.com/johnhamelink/rvm-zsh) - Initiates RVM and adds rubygem binaries (like compass) accessible in the user's `$PATH`.
* [safe-kubectl](https://github.com/benjefferies/safe-kubectl) - 在运行 `kubectl` 时添加一些安全性，方法是在自上次 `kubectl` 命令后的可定义秒数后警告您所处的上下文.
* [safe-paste](https://github.com/oz/safe-paste) - A safe-paste plugin. See Conrad Irwin's [bracketed-paste](https://cirw.in/blog/bracketed-paste) 博客文章.
* [safe-rm](https://github.com/mattmc3/zsh-safe-rm) - 添加安全 rm 功能，以便 `rm` 将文件放入操作系统的垃圾箱，而不是永久删除它们.
* [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) - When using multiple AWS profiles, e.g. different accounts for your stages (development, pre-prod, prod), can be used to determine which profile is currently exported and if the token is still valid.
* [saml2aws](https://github.com/onyxraven/zsh-saml2aws) - Add support for [saml2aws](https://github.com/Versent/saml2aws).
* [sandboxd](https://github.com/benvan/sandboxd) - 仅在需要时运行设置命令（例如 `eval &quot;$(rbenv init -)&quot;` 等），通过延迟加载加速您的 `.zshrc` 和 shell 启动.
* [saneopt](https://github.com/willghatch/zsh-saneopt) - Sane defaults for ZSH options, in the spirit of vim-sensible.
* [sb-upgrade](https://github.com/redxtech/zsh-sb-upgrade) - Script to automatically update apps on a seedbox.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) - Show current `chroot` name in your prompt.
* [sdkman](https://github.com/ptavares/zsh-sdkman) - Installs [sdkman](https://github.com/sdkman) and adds completions and aliases for it.
* [sealion](https://github.com/xyproto/sealion) - 允许您设置刷新提示时将出现在终端中的提醒.
* [search-directory-history](https://github.com/cmaahs/search-directory-history) - 允许对使用创建的每个目录历史记录进行复杂搜索 [per-directory-history](https://github.com/jimhester/per-directory-history) 插入.
* [sed-sub](https://github.com/MenkeTechnologies/zsh-sed-sub) - 添加键绑定以在当前命令行上进行全局搜索和替换.
* [send](https://github.com/robertzk/send.zsh) - Single command to `git add`, `git commit`, and `git push` for much faster `git` workflow.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - 添加许多 `git` 别名和辅助 shell 函数.
* [session-sauce](https://github.com/ChrisPenner/session-sauce) - 用于所有项目的 tmux 会话创建和管理的 fzf 接口.
* [setenv](https://github.com/kalpakrg/setenv) - 更改目录时运行脚本.
* [shelf](https://github.com/ecmma/shelf) - 可用于使用助记符为任何文件添加书签和直接访问的实用程序.
* [shellfirm](https://github.com/kaplanelad/shellfirm) - Shellfirm is a handy utility to help avoid running dangerous commands without an extra step of approval. When risky patterns is detected you will immediately get a small prompt challenge that will double verify your action.
* [show-path](https://github.com/redxtech/zsh-show-path) - 提供逐行显示`$PATH`的功能.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - Plugin to easily start python `SimpleHTTPServer` and `SimpleHTTPSServer`.
* [skim](https://github.com/hackerchai/skim-zsh) - 增加了对 [skim](https://github.com/lotabout/skim)
* [slugify](https://github.com/lashoun/slugify) - Converts filenames and directories to a web friendly format.
* [smart-cd](https://github.com/dbkaplun/smart-cd) - 在 chpwd 之后运行 `ls` 和 `git status`.
* [smartinput](https://github.com/momo-lab/zsh-smartinput) - 当您键入括号或引号时，会自动添加相应的结束括号/引号.
* [smile](https://github.com/fundor333/smile) - 添加显示随机笑脸的功能.
* [snippets](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion.
* [solarized-man](https://github.com/zlsun/solarized-man) - oh-my-zsh 的插件 colour-man-pages 的修改版本，针对 [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) 终端中的主题.
* [spack](https://github.com/Game4Move78/zsh-spack) - 包括一些有用的别名和加载/卸载函数 [Spack](https://github.com/spack/spack) - 生成的模块. 由于它使用了 `module` 命令，它比 `spack load` 更有效.
* [ssh-connect](https://github.com/gko/ssh-connect) - 一个简单的 `ssh` 管理器.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - `ssh` 的插件.
* [sshukh](https://github.com/anatolykopyl/sshukh-zsh-plugin) - Will update your `known_hosts` file when you `ssh` into a server.
* [startify](https://github.com/NorthIsMirror/zsh-startify) - 显示最近使用的 `vim` 文件、shell-util 文件、活动的 `tmux` 会话、最近运行的 `git` 命令等等.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - 打印 shell 启动所需的时间.
* [stashy](https://github.com/MisterRios/stashy) - Plugin that simplifies using `git stash`.
* [statify](https://github.com/vladmrnv/statify) - Plugin that does basic statistical analysis.
* [sublime](https://github.com/valentinocossar/sublime) - 与 Oh My Zsh 的官方 Sublime 插件相同，但这会在当前 Sublime 窗口中打开文件（如果已经打开了一个文件）.
* [sudo](https://github.com/hcgraf/zsh-sudo) - The `sudo` plugin from oh-my-zsh, extracted to a standalone. Toggles `sudo` before the current/previous command by pressing *ESC-ESC* in emacs-mode or vi-command mode.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - 使用 ZSH 的后缀别名直接在 shell 中打开文件。
* [svn-n-zsh](https://github.com/khrt/svn-n-zsh-plugin) - 重写股票 oh-my-zsh svn 插件.
* [switch-git](https://github.com/robin-mbg/switch-git) - Easy switching between `git` repositories. Just type `sgr <some part of you repo's name>`, press enter and you're there.
* [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) - Symfony 2 和 3 的 ZSH 插件.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - 使用 dircolors 实时突出显示 ZSH 语法.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your ZSH. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgets without typing commands.
* [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp 为系统管理员收集的工具脚本.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard) - Adds key bindings support for ZLE (Zsh Line Editor) clipboard operations for vi emulation keymaps. It works under Linux, macOS and Android (via Termux).
* [systemd](https://github.com/le0me55i/zsh-systemd) - 为 `systemd` 添加了许多别名.
* [t32](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [tab-title](https://github.com/trystan2k/zsh-tab-title)  - 根据当前目录或正在运行的进程设置终端标签标题. 分叉自 [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh)
* [tailf](https://github.com/rummik/zsh-tailf) - 添加带有前缀换行符而不是尾随换行符的 `tailf` 函数.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - Auto-completes task numbers for taskbook.
* [terminal-app](https://github.com/the8/terminal-app.zsh) - A plugin for integrating with the new El Capitan Terminal.app features.
* [terminal-title](https://github.com/AnimiVulpis/zsh-terminal-title) - 添加一个“set-term-title”功能，您可以使用它来命名终端窗口.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - 计算并显示通过终端运行了多少命令的插件.
* [termux](https://github.com/zpm-zsh/termux) - 增加兼容性 [Termux](https://termux.com/)
* [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) - 添加 terraform 工作区以提示.
* [terraform (jsporna)](https://github.com/jsporna/terraform-zsh-plugin) - Extends the original oh-my-zsh plugin with aliases and tab completions. Adds workspace (when not default) to prompt.
* [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) - 添加方便别名 [terraform](https://terraform.io/)，选项卡完成和辅助功能，以在提示中添加您的 terraform 工作区.
* [terraform (pbar1)](https://github.com/pbar1/zsh-terraform) - ZSH 的 Terraform 便利函数和别名.
* [terraform (thuandt)](https://github.com/thuandt/zsh-terraform) - Adds convenience aliases for `terraform`, along with completions for `terraform` and `terragrunt`.
* [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - Plugin for [Terragrunt](https://github.com/gruntwork-io/terragrunt), 一个薄包装 [Terraform](https://terraform.io/) 提供额外的工具.
* [tfenv](https://github.com/CDA0/zsh-tfenv) - Installs, updates, and loads tfenv inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)
* [tfswitch](https://github.com/ptavares/zsh-tfswitch) - Installs and loads [tfswitch](https://github.com/warrensbox/terraform-switcher).
* [tgswitch](https://github.com/ptavares/zsh-tgswitch) - Installs and loads [tgswitch](https://github.com/warrensbox/tgswitch).
* [thefuck](https://github.com/laggardkernel/thefuck) - 负载 [thefuck](https://github.com/nvbn/thefuck) （一种更正您先前命令的工具）具有缓存支持，可显着减少加载时间.
* [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) - 使用的便利功能 [theia-ide](https://github.com/theia-ide/theia).
* [tig](https://github.com/MenkeTechnologies/zsh-tig-plugin) - 添加一些高级绑定 [tig](https://github.com/jonas/tig) and also provides a `tig-pick` script.
* [timewarrior](https://github.com/svenXY/timewarrior) - 增加了对 [timewarrior](https://timewarrior.net/)，一个时间跟踪应用程序.
* [tipz](https://github.com/molovo/tipz) - Displays your alias if you have an alias for the command you just ran, similarly to [alias-tips](https://github.com/djui/alias-tips).
* [title](https://github.com/zpm-zsh/title) - Allows you to set a terminal window title.
* [titles](https://github.com/jreese/zsh-titles) - Automatic window and tab titles for [tmux](https://tmux.github.io) 和 xterm 兼容的终端.
* [tm](https://github.com/kjhaber/tm.zsh) - 简化创建新 [tmux](https://tmux.github.io) 会话、附加到现有会话、在会话之间切换以及列出活动会话.
* [tmux-auto-title](https://github.com/mbenford/zsh-tmux-auto-title) - Automatically sets the title of windows/panes as the current foreground command.
* [tmux-multisession](https://github.com/nichus/zsh-tmux-multisession) - Plugin for [tmux](https://tmux.github.io) to support multiple sessions on a single server process.
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - Rename [tmux](https://tmux.github.io) windows automatically.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - 使用简单的插件 [tmux](https://tmux.github.io) with ZSH.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - 在正在运行的“vim”（或 NeoVim）会话中打开文件，从相邻 [tmux](https://tmux.github.io) pane.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - Create unified terminal titles for `tmux`, ZSH, and Vim/NVIM, modular.
* [tmux](https://github.com/zpm-zsh/tmux) - Plugin for [tmux](https://tmux.github.io).
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) - 具有 R-EP-L 的简单 ZSH 插件 [tmux](https://tmux.github.io) session.
* [toggl](https://github.com/natterstefan/toggl-zsh-plugin) - Adds a `toggl-week` command to display the total working hours tracked on [toggl.com](https://toggl.com)
* [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix)  - 添加一个小部件以切换命令的前缀. 默认情况下，将 Alt+s 绑定到带有 `sudo` 的命令前缀.
* [traista](https://github.com/odgon/traista) - Includes `git` status decorations and color-coded exit status of the last command run. Better with dark terminal themes.
* [travis](https://github.com/denolfe/zsh-travis) - 打开当前存储库的 Travis CI 页面（如果存在）.
* [tre](https://github.com/redxtech/zsh-tre) - 使用 [tre](https://github.com/dduan/tre#editor-aliasing) 更轻松.
* [tsm](https://github.com/RobertAudi/tsm) - 添加一个 [tmux](https://tmux.github.io) Session Manager.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) - 为 macOS 添加工具.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 aliases.
* [ugit](https://github.com/Bhupesh-V/ugit) - 让您撤消上一次 `git` 操作.
* [uncloudium](https://github.com/Talon1024/omz-uncloudium) - 添加帮助脚本以从 Google Chrome 网上商店下载 crx 文件.
* [undollar](https://github.com/zpm-zsh/undollar) - Strips the dollar sign from the beginning of the terminal prompt.
* [unique-id](https://github.com/z-shell/zsh-unique-id) - provides a unique number that identifies a running Zshell session, in its shell variable `$ZUID_ID`. Besides this unique number, also a unique codename is provided, in shell variable `$ZUID_CODENAME`. An example use case is to hold logs in files `.../mylog-${ZUID_CODENAME}.log`, so that two different Zshells will not write to the same file at the same time.
* [unix-simple](https://github.com/redxtech/zsh-unix-simple) - A command that shows a graphic about the simplicity of unix.
* [up (cjayross)](https://github.com/cjayross/up) - 一种向上浏览目录的简单方法.
* [up (peterhurford)](https://github.com/peterhurford/up.zsh) - Adds an up command to `cd` multiple levels up.
* [update-zsh](https://github.com/AndrewHaluza/zsh-update-plugin) - Updates custom oh-my-zsh plugins. Only works with the oh-my-zsh framework.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) <i>- A plugin for the ZSH syntax highlighter that turns URLs green if they respond with a &quot;good&quot; status, and red otherwise.</i> <b>- ZSH 语法高亮插件插件，如果 URL 以“良好”状态响应，则将其变为绿色，否则变为红色。</b> <i>Useful for checking URL typos.</i><b>用于检查 URL 拼写错误。</b>
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - Extends the functionality of the original oh-my-zsh venv module.
* [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) - A wrapper plugin for [vagrant](https://www.vagrantup.com/) 允许从 box 目录之外调用 `vagrant` 命令. 该插件还附带了一些额外的命令，可帮助管理多个框，以及自定义选项卡完成.
* [vanilli.sh](https://github.com/yous/vanilli.sh) - shell 配置的轻量级起点.
* [vapor](https://github.com/notf0und/zsh-vapor) - 用于 zsh 的 Laravel vapor 插件，可帮助您从项目树中的任何位置运行 vapor，并具有自动完成功能！
* [vcshr](https://github.com/aubreypwd/zsh-plugin-vcshr) - 帮助 vcsh 用户需要使用 `vcsh` 的 Github 存储库，以便在 `~/.zshrc` 等中自动安装.
* [velocity](https://github.com/rahulsalvi/velocity-python) - ZSH 和基于电力线的主题元素 [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) - A super-lightweight sort-of-clone of [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) ; 它几乎希望您使用 [pyenv](https://github.com/pyenv/pyenv) （尽管您没有*必须*），并且因为它基于 [`venv` module](https://docs.python.org/3/library/venv.html), （创建）仅适用于 python &gt;= 3.3.
* [venv-wrapper](https://github.com/glostis/venv-wrapper) - 提供 ZSH 功能以简化使用 `venv` 的虚拟环境管理.
* [vi-increment](https://github.com/zsh-vi-more/vi-increment) - 添加类似 `vim` 的递增/递减操作.
* [vi-mode (jeffreytse)](https://github.com/jeffreytse/zsh-vi-mode) - ZSH 的更好和友好的 vi(vim) 模式插件.
* [vi-mode (nyquase)](https://github.com/Nyquase/vi-mode) 添加额外的类似“vi”的功能.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - 向 ZSH 添加更多类似于 `vi` 的功能.
* [vi-motions](https://github.com/zsh-vi-more/vi-motions) - Add new motions and text objects including quoted/bracketed text and commands.
* [vi-quote](https://github.com/zsh-vi-more/vi-quote) - Add an operation which quotes or unquotes a motion.
* [viexchange](https://github.com/okapia/zsh-viexchange) - 一个 `vi` 模式插件，用于在缓冲区中的两个位置之间轻松交换文本，例如 vim-exchange.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) - Friendly `vi`-mode bindings, adding basic Emacs keys, incremental search, mode indicators and more.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - Allows you to do `vim filename:123` to open a file with the cursor at a specific line.
* [vimman](https://github.com/yonchu/vimman) - 查看 `vim` 插件手册（帮助），如 ZSH 中的 `man`.
* [vimto](https://github.com/laurenkt/zsh-vimto) - 改进了 ZSH `vi` 模式 (bindkey -v) 插件.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - 用于 oh-my-zsh 的修改后的 virtualenv ZSH 插件.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - A fork of the virtualenv plugin from upstream. Adds support for customizing the virtualenv prompt in oh-my-zsh themes.
* [virtualz](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) 受 Adam Brenecki 启发的经理 [Virtualfish](https://github.com/adambrenecki/virtualfish) for the [Fish shell](http://fishshell.com/), replaces virtualenvwrapper.
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - An oh-my-zsh plugin for the [virtuozzo](https://docs.virtuozzo.com/master/index.html) bare-metal virtualization system.
* [visit](https://github.com/justinpchang/visit) - 用于更快导航的自定义插件.
* [volta (cowboyd)](https://github.com/cowboyd/zsh-volta) - 无缝安装和配置 [Volta](https://volta.sh) NodeJS toolchain manager.
* [volta](https://github.com/ri7nz/zsh-volta) - Installs and loads [ Volta: JS Toolchains as Code](https://github.com/volta-cli/volta).
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - 一个 oh-my-zsh 插件来控制 [VOX](https://vox.rocks/), a lightweight full-featured audio player for macOS that can play a variety of formats including FLAC and Ogg Vorbis.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for Visual Studio Code on macOS.
* [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) - Simple plugin to open VS code a little easily across systems.
* [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) - Plugin for [Visual Studio Code](https://code.visualstudio.com/).
* [vterm](https://github.com/randomphrase/vterm-zsh-plugin) - 让您直接从 [vterm](https://github.com/vterm/vterm) shell sessions.
* [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) - Track how much [time](https://wakatime.com/) 你已经在你的终端消费了. 具有每个项目的统计信息.
* [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) - 使用 ZSH 中的命令自动时间跟踪 [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - 配置着色与 [grc](https://github.com/garabik/grc).
* [watch](https://github.com/enrico9034/zsh-watch-plugin) - 通过按“CTRL + W”，可以轻松地为当前或以前的命令添加前缀.
* [watson.zsh](https://github.com/bcho/Watson.zsh) - 一个插件 [watson](https://github.com/TailorDev/Watson) 时间管理系统.
* [wd](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
* [web-search (sinetoami)](https://github.com/sinetoami/web-search) - 添加命令以直接从 CLI 运行 bing、google、yahoo 和 duckduckgo 搜索.
* [web-search (yabanahano)](https://github.com/Yabanahano/web-search) - Adds aliases for searching with Google, Wiki, Bing, YouTube and other popular services.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - Highlight where a particular line was last changed in a file using `git blame`.
* [window-title](https://github.com/olets/zsh-window-title) - 将信息图块添加到您的终端窗口.
* [windows-title](https://github.com/mdarocha/zsh-windows-title) - 使用当前目录和最后运行的命令动态更新终端窗口标题.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) - Simple utility for jumping between projects.
* [worktree](https://github.com/jspears/worktree) - Adds functions that wrap `git worktree`.
* [xdg-basedirs](https://github.com/zshzoo/xdg-basedirs) - 配置应用程序以使用 XDG 基本目录.
* [xxh-plugin-zsh-zshrc](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) - plugin for [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) that copies your `~/.zshrc` to a remote host and sources it with [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh).
* [yadm](https://github.com/juanrgon/yadm-zsh) - Displays a warning if there are local yadm configuration changes.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - Automatically activate a directory's pip environment if `pipenv` detects the presence of one.
* [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's Yeoman plugin for oh-my-zsh, compatible with yeoman version ≥1.0 (includes options and command auto-completion).
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH 插件，提醒您使用您定义的那些别名.
* [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) - 添加 `yt` 别名以从 YouTube 下载视频.
* [youtube-dl](https://github.com/joow/youtube-dl) - Simple plugin for [youtube-dl](https://youtube-dl.org/).
* [yup](https://github.com/redxtech/zsh-yup) - Adds helper function to upgrade all the dependencies in a yarn/npm project.
* [z.lua](https://github.com/skywind3000/z.lua)  - 一个命令行工具，可帮助您通过学习习惯来更快地导航. 一个替代方案 [z.sh](https://github.com/rupa/z) with Windows and posix shells support and various improvements. 10x faster than fasd and autojump, 3x faster than [z.sh](https://github.com/rupa/z).
* [zabb](https://github.com/Mellbourn/zabb) - `zabb` 是一个命令，它试图找出可供用户使用的目录的最短记忆缩写 [z](https://github.com/ajeetdsouza/zoxide) 明确地跳转到该目录.
* [zabrze](https://github.com/Ryooooooga/zabrze) - ZSH 缩写扩展插件.
* [zaw](https://github.com/zsh-users/zaw) - ZSH anything.el-like widget.
* [zbrowse](https://github.com/zdharma-continuum/zbrowse) - 在做shell工作时，经常会调用echo $variable多次，检查循环结果等.使用ZBrowse，你只需要按下`Ctrl-B`，调用ZBrowse – Zshell变量浏览器.
* [zce](https://github.com/hchbaw/zce.zsh) - Vim 的 EasyMotion / Emacs 的 ZSH ace-jump-mode.
* [zcolors](https://github.com/marlonrichert/zcolors) - Uses your `$LS_COLORS` to generate a coherent theme for Git and your Zsh prompt, completions and [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [zconvey](https://github.com/zdharma-continuum/zconvey) - Adds ability to send commands to other ZSH sessions, you can use this to `cd $PWD` on all active ZSH sessions, for example.
* [zed](https://github.com/eendroroy/zed-zsh) - 一个简单的包装器 [z](https://github.com/rupa/z) to install it via a ZSH plugin.
* [zeit](https://github.com/zeit/zeit.zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
* [zellij (jaeheonji)](https://github.com/jaeheonji/zsh-zellij-plugin) - 提供使用环境 [zellij](https://github.com/zellij-org/zellij). Requires `tmux`.
* [zellij (tranzystorek-io)](https://github.com/tranzystorek-io/zellij-zsh) - 提供自动启动的环境 [zellij](https://github.com/zellij-org/zellij) 作为您终端的多路复用器.
* [zeno](https://github.com/yuki-yano/zeno.zsh) - Fuzzy completion and utility plugin powered by [Deno](https://deno.land/).
* [zero](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details.
* [zflai](https://github.com/zdharma-continuum/zflai) - A fast logging framework for ZSH.
* [zfzf](https://github.com/b0o/zfzf) - A fzf-powered file picker for ZSH which allows you to quickly navigate the directory hierarchy.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - Make compinit run only once after all loading is done by [zgen](https://github.com/tarjoilija/zgen).
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) - Custom extras for zimfw, packaged into a zimfw plugin.
* [zinfo_line](https://github.com/kmhjs/zinfo_line) - 为 ZSH 主题提供更多信息.
* [zinit-annex-bin-gem-node](https://github.com/zdharma-continuum/zinit-annex-bin-gem-node) - [zinit](https://github.com/zdharma-continuum/zinit) 在不更改 $PATH 的情况下公开二进制文件的扩展，安装 Ruby gems 和 Node 模块并轻松公开它们的二进制文件，并在更新相关插件或片段时更新 gems 和模块.
* [zinit-annex-default-ice](https://github.com/zdharma-continuum/zinit-annex-default-ice) - Allows user to define ices active for multiple zinit commands.
* [zinit-annex-man](https://github.com/zdharma-continuum/zinit-annex-man) - [Zinit](https://github.com/zdharma-continuum/zinit) 为所有插件和片段生成手册页的扩展
* [zinit-annex-meta-plugins](https://github.com/zdharma-continuum/zinit-annex-meta-plugins) - 使用单个标签安装插件组（[zinit](https://github.com/zdharma-continuum/zinit) only).
* [zinit-annex-patch-dl](https://github.com/zdharma-continuum/zinit-annex-patch-dl) - [zinit](https://github.com/zdharma-continuum/zinit) extension that downloads files and applies patches through the provided `dl` and `patch` zinit ices.
* [zinit-annex-readurl](https://github.com/zdharma-continuum/zinit-annex-readurl) - 添加功能以自动下载网页上托管 URL 的文件的最新版本.
* [zinit-annex-rust](https://github.com/zdharma-continuum/zinit-annex-rust) - [zinit](https://github.com/zdharma-continuum/zinit) extension that that installs rust and cargo packages inside plugin directories.
* [zinit-annex-submods](https://github.com/z-shell/z-a-submods) - [zinit](https://github.com/zdharma-continuum/zinit) 扩展允许在插件或片段中安装和管理额外的子模块.
* [zinit-annex-test](https://github.com/NorthIsMirror/z-a-test) - [zinit](https://github.com/zdharma-continuum/zinit) extension that runs tests (via make test, for example) – if it finds any of them – after installing and updating a plugin or snippet.
* [zinit-annex-unscope](https://github.com/zdharma-continuum/zinit-annex-unscope) - 允许安装插件 [zinit](https://github.com/zdharma-continuum/zinit) without specifying the user name by querying the Github API.
* [zinit-console](https://github.com/z-shell/zinit-console) - A semigraphical (curses) consolette for the [zinit](https://github.com/zdharma-continuum/zinit) 插件管理器.
* [zinsults](https://github.com/ahmubashshir/zinsults) - 如果命令失败，则打印侮辱.
* [zjump](https://github.com/qoomon/zjump) - Simplify ZSH directory navigation; jump to already visited, parent or sub folders.
* [zlitefetch](https://github.com/ippee/zlitefetch) - Lightweight system information plugin.
* [zlong_alert](https://github.com/kevinywlui/zlong_alert.zsh) - Uses notify-send and ring a bell to alert you when a command that has taken a long time (default: 15 seconds) has completed.
* [zman](https://github.com/mattmc3/zman) - Use `fzf` to quickly browse Zsh manuals.
* [zoxide](https://github.com/ajeetdsouza/zoxide) - 学习您习惯的“cd”的快速替代方案.
* [zredis](https://github.com/zdharma-continuum/zredis)  - 添加 Redis 数据库支持，使用 `database_key` &lt;-&gt; `shell_variable` 绑定. 支持所有数据类型.
* [zsh-in-docker](https://github.com/deluan/zsh-in-docker) - Automates ZSH + Oh-My-ZSH installation into development containers. Works with Alpine, Ubuntu, Debian, CentOS or Amazon Linux.
* [zsh-not-vim](https://github.com/redxtech/zsh-not-vim) - 提供自动羞辱用户忘记他们没有在 vim 中的功能.
* [zsh-z (agkozak)](https://github.com/agkozak/zsh-z)  - 快速跳转到您“经常”访问的目录.  `z.sh` 的原生 ZSH 端口 - 没有 `awk`、`sed`、`sort` 或 `date`.
* [zsh-z (ptavares)](https://github.com/ptavares/zsh-z) - Installs and loads [z](https://github.com/rupa/z.git).
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for oh-my-zsh.
* [zshrc](https://github.com/freak2geek/zshrc) - Load local `.zshrc` files from your project scopes.
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - 用于在 Arch Linux 上拍摄 ZFS 升级前/升级后快照的插件.
* [zsnapshot](https://github.com/zdharma-continuum/zsnapshot) - Adds command to dump the current ZSH state into a file, for later restoration by sourcing the snapshot file.
* [ztouch](https://github.com/mjrafferty/ztouch) - Adds touchbar controls for recent history commands, directory stack, cycling between modes and user-mappable commands to the touchbar on macOS.
* [zui](https://github.com/zdharma-continuum/zui) - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH.)

## Completions

These plugins add tab completions without adding extra functions or aliases.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - 扩展 ZSH 的 \_urls 补全，允许它从 html 页面补全 url.
* [aliyun](https://github.com/thuandt/zsh-aliyun) - 添加完成 [Aliyun CLI](https://github.com/aliyun/aliyun-cli).
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - Completions for viasite-ansible/ansible-server.
* [antibody-completion](https://github.com/sinetoami/antibody-completion) - 这个插件提供完成 [Antibody](https://github.com/getantibody/antibody) 插件管理器.
* [appspec](https://github.com/perlpunk/App-AppSpec-p5) - Generating completions for Bash and ZSH from YAML specs
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - autopkg 的完成.
* [aws-completions](https://github.com/eastokes/aws-plugin-zsh) - 添加对 `awscli` 的完成支持以管理 AWS 配置文件/区域并在提示中显示它们.
* [aws_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) - 为 aws_manager CLI 添加完成.
* [bash-completions-fallback](https://github.com/3v1n0/zsh-bash-completions-fallback) - 当没有本地 ZSH 可用时，支持命令的 `bash` 完成.
* [batect](https://github.com/batect/batect-zsh-completion/) - 添加选项卡完成 [batect](https://batect.dev/) build system.
* [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) - 为 berkshelf 添加选项卡完成.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - Better tab completion for `npm`.
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - Adds BOSH autocompletion.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) - Completion plugin for homebrew services.
* [buidler](https://github.com/gonzalobellino/buidler-zsh) - 为 NomicLabs Buidler 工具添加完成和有用的别名 [buidler.dev](https://buidler.dev).
* [bw](https://github.com/CupricReki/zsh-bw-completion) - 添加完成 [Bitwarden](https://bitwarden.com/).
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - 为 cabal 添加制表符补全.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal.
* [carapace](https://github.com/rsteube/carapace) - Completion generator for Bash, Elvish, Fish, Oil, Powershell, Xonsh and ZSH. Note - not dynamic, you have to explicitly run it to generate completions for a command.
* [cargo](https://github.com/MenkeTechnologies/zsh-cargo-completion) - All the functionality of the original OMZ cargo completion, with additional support for remote crates via `cargo search` in `cargo add`.
* [carthage](https://github.com/squarefrog/zsh-carthage) - 提供补全和别名以供使用 [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) - 为所有人添加自动完成功能 [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) 命令.
* [cod](https://github.com/dim-an/cod) - `bash`/`fish`/`zsh` 的完成恶魔，当它看到你使用 `--help` 运行某些东西时，它会即时创建完成函数.
* [codeception](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - 显示 git 信息，是否通过 `ssh` 登录，返回最后一个命令的代码.
* [comonicon](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) - 选项卡完成 [comonicon](https://github.com/Roger-luo/Comonicon.jl).
* [completions](https://github.com/zsh-users/zsh-completions) - ZSH 的额外完成集合.
* [conda](https://github.com/esc/conda-zsh-completion) - conda 的 ZSH 选项卡完成.
* [cpan](https://github.com/MenkeTechnologies/zsh-cpan-completion) - Adds `cpan install word<tab>` and `cpanm install <tab>` to complete remote CPAN package names.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - 选项卡完成 [ctop](https://github.com/bcicen/ctop).
* [dagger](https://github.com/jygastaud/dagger-oh-my-zsh) - 完成匕首.
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
* [docker (chr-fritz)](https://github.com/chr-fritz/docker-completion.zshplugin) - Loads `docker` ZSH tab completions directly from **Docker for Mac**.
* [docker (felixr)](https://github.com/felixr/docker-zsh-completion) - Add tab completions for `docker`.
* [docker (greymd)](https://github.com/greymd/docker-zsh-completion) - 为 `docker` 和 `docker-compose` 添加选项卡补全.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - Command completion for [docker-enter](https://github.com/jpetazzo/nsenter).
* [dotnet](https://github.com/MenkeTechnologies/zsh-dotnet-completion) - Dotnet tab completion.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for ZSH.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - 一个 ZSH 插件 [duell](https://github.com/gameduell/duell).
* [efibootmgr](https://github.com/wehlando/efibootmgr-zsh-completion) - Tab completions for `efibootmgr`.
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - Adds etcdctl tab completions.
* [expressvpn](https://github.com/tk7r/zsh-expressvpn) - 为 [expressVPN](https://www.expressvpn.com/support/vpn-setup/app-for-linux/) 客户.
* [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) - 定义一个名为 extract 的函数，用于提取您传递给它的存档文件，并支持多种存档文件类型.
* [extract (thetic)](https://github.com/thetic/extract) - oh-my-zsh 提取插件的分支.
* [flowr](https://github.com/oubasan/flowr) - 完成支持 [git-flow](http://github.com/nvie/gitflow).
* [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - Adds autocompletion options for all [Concourse CLI](https://www.concourse.ci/fly-cli.html) 命令.
* [fzf-gcloud](https://github.com/mbhynes/fzf-gcloud) - 导航和预览所有 Google Cloud SDK `gcloud` CLI 命令的模糊补全
* [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) - 使用 GNU Readline 为 ZSH、bash 和应用程序添加选项卡完成.
* [fzf-zsh-completions](https://github.com/chitoku-k/fzf-zsh-completions) - 模糊完成 [fzf](https://github.com/junegunn/fzf) 和 [ZSH](https://www.zsh.org/) 可以由默认为 `**` 的触发序列触发.
* [gcloud](https://github.com/littleq0903/gcloud-zsh-completion) - 为 Google Cloud SDK 添加补全.
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - providing ZSH completion support to various Gentoo tools that lack completion scripts upstream.
* [git-annex](https://github.com/Schnouki/git-annex-zsh-completion) - 允许大多数 git-annex 命令的选项卡完成.
* [git-flow](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for [git-flow](http://github.com/nvie/gitflow).
* [github-cli](https://github.com/sudosubin/zsh-github-cli) - Tab completions for the github cli.
* [gitlab-runner](https://github.com/pseyfert/zsh-gitlab-runner-completion) - ZSH completions for gitlab-ci-multi-runner.
* [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) - 对 gradle 的 Bash 和 ZSH 完成支持.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - ZSH completion support for gradle.
* [grid5000](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 插件 - 添加主题、自动补全.
* [gulp (akoenig)](https://github.com/akoenig/gulp.plugin.zsh) - 在 Z-Shell (ZSH) 中自动完成 gulp.js 任务.
* [gulp (srijanshetty)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - gulp 的自动补全.
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) - Completions for [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haskell](https://github.com/coot/zsh-haskell) - 为 `cabal`、`ghc` 和 `ghc-pkgs` 命令添加补全.
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib.
* [helmfile](https://github.com/Downager/zsh-helmfile) - Adds autocompletion for `helm`.
* [inspr](https://github.com/ptcar2009/insprzsh) - Completions for [inspr](https://github.com/inspr/inspr)
* [ipfs](https://github.com/hellounicorn/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.io).
* [joe](https://github.com/corvofeng/joe-completion) - 添加完成 [joe](https://github.com/karan/joe) .gitignore 编辑器.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - ZSH completions for jtool.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - Adds autocompletion for [jumpstorm](https://github.com/netresearch/jumpstorm)
* [jx](https://github.com/haysclark/zsh-jx) - 为 Jenkins-X cli 添加选项卡补全.
* [kafka](https://github.com/Dabz/kafka-zsh-completions) - Completions for Apache [kafka](https://kafka.apache.org).
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - Completions for [keybase](https://keybase.io/docs/command_line).
* [kitty](https://github.com/redxtech/zsh-kitty) - Completions for [kitty](https://sw.kovidgoyal.net/kitty/) terminal emulator.
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - Add tab completions for [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - Add tab completions for [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
* [kubectl-fzf](https://github.com/bonnefoa/kubectl-fzf) - 快速而强大 [`fzf`](https://github.com/junegunn/fzf)-powered autocompletion for `kubectl`.
* [lazycomplete](https://github.com/rsteube/lazycomplete) - 延迟加载 shell 完成脚本.
* [lets](https://github.com/lets-cli/lets-zsh-plugin) - 添加自动完成 [lets](https://github.com/lets-cli/lets) cli task runner.
* [ls-go](https://github.com/MohamedElashri/ls-go-zsh) - 添加一些有用的别名 [ls-go](https://github.com/acarl005/ls-go).
* [mooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - Perl 模块 `MooseX::App` 的完成生成器.
* [more-completions](https://github.com/MenkeTechnologies/zsh-more-completions) - 10500 个 zsh compsys 完成！
* [msfvenom](https://github.com/Green-m/msfvenom-zsh-completion) - Metasploit 的选项卡完成.
* [mx-honey](https://github.com/mukel/mx-honey) - Provides completions for [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.
* [newman](https://github.com/selop/newman-autocomplete) - 提供自动完成 [Newman CLI](https://github.com/postmanlabs/newman).
* [nix](https://github.com/spwhitt/nix-zsh-completions) - Completions for [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/)， 和 [NixOps](https://nixos.org/nixops/).
* [node-ace](https://github.com/romch007/node-ace-zsh-completion) - 完成“节点王牌”.
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) - 为 nova 提供自动完成功能.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - 对“npm run”的自动完成支持.
* [nx](https://github.com/jscutlery/nx-completion) - Completions for [nx](https://nx.dev) . 需要 [`jq`](https://stedolan.github.io/jq/).
* [okta](https://github.com/sirhc/okta.plugin.zsh) - 提供命令行补全 [`aws-okta`](https://github.com/segmentio/aws-okta) 和 [okta-awscli](https://github.com/jmhale/okta-awscli) comm和s.
* [op](https://github.com/sirhc/op.plugin.zsh) - 选项卡完成 [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) command line tool.
* [packer](https://github.com/wakeful/zsh-packer) - 添加选项卡完成 [packer](https://packer.io).
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin.
* [parallels](https://github.com/benclark/parallels-zsh-plugin) - Add completions for Parallels desktop.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - 方便的回购，轻松获得 [pass](https://www.passwordstore.org/) ZSH 的命令完成.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - pip 的自动完成插件.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - Enables aliases for the most common pipenv commands.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) - `pipenv` 的完成.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh) - automatically activates a **pipenv** when entering a directory if there is Pipfile in that directory. Includes `pipenv` completions.
* [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) - Adds completions for Pivotal's [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
* [pmy](https://github.com/relastle/pmy) - 通用的上下文感知 ZSH 完成引擎，由 [fzf](https://github.com/junegunn/fzf).
* [quickjump](https://github.com/fikovnik/zsh-quickjump) - 添加选项卡完成支持 [skim](https://github.com/lotabout/skim) 对于最近使用的文件和目录 [fasd](https://github.com/whjvenyl/fasd).
* [racket completion](https://github.com/racket/shell-completion) - Completion for [Racket](http://racket-lang.org).
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets.
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) - 为 Rancher CLI 添加完成.
* [rhoas](https://github.com/craicoverflow/rhoas-zsh-plugin) - 添加完成 [rhoas](https://developers.redhat.com/products/red-hat-openshift-streams-for-apache-kafka/overview).
* [rustup](https://github.com/pkulev/zsh-rustup-completion) - Rustup 的选项卡完成.
* [s3cmd](https://github.com/FFKL/s3cmd-zsh-plugin) - 添加选项卡完成 [s3cmd](https://s3tools.org/s3cmd).
* [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion)  - Salesforce CLI 的 ZSH 命令完成. 需要 [jq](https://stedolan.github.io/jq/).
* [saml2aws](https://github.com/sirhc/saml2aws.plugin.zsh) - 添加完成 [saml2aws](https://github.com/Versent/saml2aws).
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) - sfdx 的自动完成插件.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - 添加自动完成 [spring-boot](http://projects.spring.io/spring-boot/) 命令.
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - 管理`ssh-agent`.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - 自动启动 `ssh-agent` 以设置和加载您想要的 `ssh` 连接的任何凭据.
* [ssh](https://github.com/zpm-zsh/ssh) - 为 `ssh` 添加主机补全.
* [surf](https://github.com/beardcoder/surf.plugin.zsh) - 添加完成冲浪.
* [symphony (TheGrowingPlant)](https://github.com/TheGrowingPlant/symfony.plugin.zsh) - Symfony 3 和 4 命令的自动完成.
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - Add completions for [Test Kitchen](https://github.com/test-kitchen/test-kitchen)).
* [tinygo](https://github.com/sago35/tinygo-autocmpl) - Add tab completions for tinygo.
* [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your [tmux](https://tmux.github.io) pane.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - Adds autocompletion for [tugboat](https://github.com/petems/tugboat) 命令.
* [umake](https://github.com/zlsun/umake) - Tab completion for Ubuntu umake.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - 提供自动完成功能 [vertx](https://vertx.io/) 命令.
* [web-open](https://github.com/AndrewHaluza/zsh-web-open) - Adds alias to open web pages. Only works with Ubuntu 20.
* [yabai](https://github.com/Amar1729/yabai-zsh-completions) - 为 macOS 添加补全 [yabai](https://github.com/koekeishiya/yabai/) 平铺窗口管理器.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - 为 `yarn add`、`yarn remove`、`yarn upgrade`、`yarn why` 和 `yarn run` 添加自动完成功能.
* [zargparse](https://github.com/ctil/zargparse) - 向它传递一个使用 `argparse` 的脚本，它会将 ZSH 完成写入您的当前目录.
* [zstyle-completions](https://github.com/zshzoo/zstyle-completions) - 给 [prezto-style](https://github.com/sorin-ionescu/prezto) 点击选项卡时完成.

## Themes

如果你正在使用 [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. 如果你正在使用 [zgenom](https://github.com/jandamm/zgenom), add them to your `init.zsh` with `zgenom load githubuser/reponame`.

* [000](https://github.com/Abid-Ahmad/oh-my-zsh-000-theme) - Multiline prompt with username, hostname, full path, return status and `git` decorations.
* [0i0](https://github.com/0i0/0i0.zsh-theme) - Optimized for dark terminal windows, uses nerdfont `git` status decorations.
* [14degree](https://github.com/saims0n/14degree-zsh-theme/) - Includes `git`, `virtualenv` and `rvm` status decorations.
* [4den](https://github.com/RunThem/zsh-theme-4den) - Minimalist. Includes `git` and `hg` status decorations.
* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - Based on the Sorin theme.
* [abbr (theme)](https://github.com/PhilsLab/abbr-zsh-theme)  - 显示当前目录路径的缩写版本，显示 Python virtualenv、Rust 版本、`git` 状态和最后一个命令的退出代码. 默认情况下适用于深色背景，但可以轻松自定义颜色.
* [absolute](https://github.com/NelsonBrandao/absolute) - 非常干净的主题，带有 git 状态、节点版本和最后一个命令的退出代码.
* [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) - 包括 `git` 状态装饰、AWS 配置文件名称、Azure 服务主体名称、kubernetes 上下文、terraform 工作区、命令状态和当前工作目录.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS theme, requires a Powerline-compatible font.
* [af-magic-dynamic](https://github.com/rslavin/af-magic-dynamic) - 修改版 [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) 动态路径缩短.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - Modified version of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme in oh-my-zsh.
* [aftermath](https://github.com/schanur/aftermath) - 在您在 shell 中运行的每个命令后获得一个漂亮的摘要行.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) - 基于 [agnoster](https://gist.github.com/3712874) theme included in [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt). Shows detailed information about `git` status.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt)  - 使用三种异步方法来保持 ZSH 提示响应，同时显示 `git` 状态和 SSH 连接、退出代码和 `vi` 模式的指示符，以及缩写的 `PROMPT_DIRTIM` 样式路径. 非常可定制. 即使在 Cygwin 和 MSYS2 上也是异步的.
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - 日晒 [Agnoster](https://gist.github.com/agnoster/3712874) 带有 `git` 状态信息的变体. 需要 unicode 字体，最好使用 [solarized](https://github.com/altercation/solarized) terminal.
* [agnoster-fseguin](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) 带有正确提示的变体.
* [agnoster-gentoo](https://github.com/r7l/agnoster-gentoo-zsh-theme) - A Gentoo flavored version of the [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme) 其中包括 user@hostname 和 `git` 状态装饰. 使用 unicode 字体效果更好.
* [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) - Optimized for [solarized](https://ethanschoonover.com/solarized/) 配色方案、`git` 或其他 VCS 工具以及兼容 unicode 的字体. 包括上次命令运行的状态、user@hostname、`git` 状态装饰、工作目录、是否以 root 身份运行、后台作业是否正在运行等信息.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with a right-prompt.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant optimized for use with [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) terminal color scheme. Includes `git` status.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) variant, includes battery and online status.
* [agnoster-repopath](https://github.com/ivanfurlan/agnoster-repopath-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [Passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) themes. Includes `git` 和 `mercurial` status, current time 和 time the last comm和 took decorations in the prompt.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with timestamp and newline added.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - 基于 [Powerline](https://github.com/Lokaltog/vim-powerline) 和 [Agnoster](https://gist.github.com/agnoster/3712874) themes 和 inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnoster](https://gist.github.com/agnoster/3712874)  - 针对 solarized 终端配色方案进行了优化，显示 `git` 装饰、user@host、工作目录、上一个命令的退出状态以及您是否以 root 权限运行. 需要与电力线兼容的字体.
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - 基于 [Agnoster](https://gist.github.com/agnoster/3712874), 显示电池寿命、日期和时间、`git` 状态、当前目录以及用户和主机信息.
* [akzsh](https://github.com/awkimball/akzsh) - 最适合深色终端主题，包括 `git` 装饰.
* [alarangeiras](https://github.com/alarangeiras/alarangeiras-zsh-theme/) - 带有“git”状态装饰的极简主义主题.
* [ale](https://github.com/alepimentel/ale-zsh) - Based on the fino theme. Includes `git`, `virtualenv` and `node` status decorations.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) - Minimalist ZSH theme with `git` status displayed.
* [alien](https://github.com/eendroroy/alien)  - 电力线风格的 ZSH 主题，显示 `git` 装饰和最后一个命令的退出代码. 比许多其他提示更快，因为它在后台进程中异步确定 `git` 装饰.
* [almel](https://github.com/Ryooooooga/almel) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) , 用 Rust 编写. 包括 `git` 状态、user@host、最后一个命令退出状态和工作目录装饰
* [alpharized](https://github.com/NicoSantangelo/Alpharized) - Optimized to work with [solarized](http://ethanschoonover.com/solarized) 黑暗的终端. 这是修改版 [avit theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme).
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - 优雅舒适的阅读主题，基于 [Agnoster](https://gist.github.com/agnoster/3712874).
* [andy](https://github.com/andymcguinness/andys-theme) - Modified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 具有更好的 `git` 支持的主题.
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) - Shows `git` information in the right hand prompt.
* [antoinechab](https://github.com/antoinechab/antoinechab-theme) - Includes `git` status, username, time and current directory decorations.
* [antsy](https://github.com/jeffmhubbard/antsy-zsh-theme) - Shows `git` branch and status decorations, virtualenv, exit status, jobs count, and vi-mode indicator.
* [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) - Shows `git` decorations, user, host, whether root, active Python virtual environment, current Ruby interpreter, visual and numeric status of the last command, power management status and time and date.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme)  - 没有视觉噪音的简约主题. 仅显示必要的信息：当前用户、主机名、工作目录、`git` 分支（如果存在）. 深色和白色端子看起来都很棒.
* [aplos](https://github.com/sunquan1991/aplos) - Minimal ZSH prompt with working directory, `git` local info, `git` remote info, time and exit code.
* [apollo](https://github.com/mjrafferty/apollo-zsh-theme) - 一个高度可定制、兼容和高性能的 ZSH 主题，它使用模块来启用功能.
* [apple (aramirol)](https://github.com/aramirol/apple-zsh-custom-themes) - 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) , 包括 `vcs` 状态装饰. 通过在 `.zshrc` 中设置变量来自定义颜色.
* [apple (bjrowlett2)](https://github.com/bjrowlett2/apple-zsh-theme) - 带有“git”状态装饰的极简主义主题.
* [arael](https://github.com/aknackd/zsh-themes) - 叉子 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [archie](https://github.com/dcavalcante/archie) - Arch Linux inspired ZSH 主题. Based on the [norm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) 主题.
* [arity](https://github.com/hybras/Arity-Zsh-Theme)  - Arity 是一个简单的主题，旨在提高可读性并一目了然. 包括路径和 `git` 装饰.
* [aronhoyer](https://github.com/aronhoyer/zsh-theme) - Minimalist theme with right-side `git` status decorations.
* [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - 带有 `git` 装饰的最小 ZSH 主题.
* [asciigit](https://github.com/cemsbr/asciigit) - 为不想使用带有额外字形的字体的 `git` 用户提供的纯 ASCII 主题.
* [asq](https://github.com/AugustoQueiroz/asq-theme) - 基于 [theunraveler](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#theunraveler).
* [astral](https://github.com/xwmx/astral)  - 带有禅宗模式的深色背景主题. 适用于 zsh-users [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) 插入.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - 基于`ys`和 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) themes.
* [async](https://github.com/mje-nz/zsh-themes) - Shows current directory, `git` state, return value of last command if it had an error code, number of background jobs, execution time of long-running commands, current python virtualenv.
* [aub](https://github.com/FraSharp/aub) - 包括 `git` 和 `hg` 状态以及 `host` 中的 `username` 的装饰.
* [aterminal](https://github.com/guiferpa/aterminal) - 在提示符中显示 Nodejs、NPM、Docker、Go、Python、Elixir 和 Ruby 信息.
* [avil](https://github.com/avil13/avil-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) - 基于 oh-my-zsh [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme, with small changes.
* [avit-mod](https://github.com/zlsun/avit-mod) - Modified version of oh-my-zsh's [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) 主题.
* [banana](https://github.com/sorcererxw/banana-zsh-theme) - Includes `git` status decorations and current directory.
* [bandit](https://github.com/Holger-Will/zsh_bandit) - Another Powerline variant.
* [bar (anki-code)](https://github.com/anki-code/bar-theme) - 极简主义设置 [p10k](https://github.com/romkatv/powerlevel10k).
* [bar (xp-bar)](https://github.com/xp-bar/zsh-bar-theme) - 包括用户名、主机、密码、`git` 状态装饰和 3 小时饮水提醒.
* [barion](https://github.com/SEbbaDK/barion) - A fast compiled prompt with a compact `git` status overview. Reminiscent of powerline. Requires [Crystal](https://crystal-lang.org/) 建造.
* [bash](https://github.com/starseekist/bash-zsh-theme) - Looks like the default `bash` prompt.
* [bashi](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) 主题和 Pasquale D&#39;Silva  [Saturn Terminal](https://github.com/psql/saturn-colors) 主题.
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - 修改版 [gitster](https://github.com/zimfw/gitster) 主题为 [ZIM](https://github.com/zimfw/zimfw).
* [bearable](https://github.com/JanmanX/bearable-zsh) - 适用于深色终端背景.
* [bedbugs](https://github.com/justino/zsh-theme-bedbugs) - 灵感来自 [Agnoster](https://gist.github.com/agnoster/3712874)，这个多行提示包括 `git` 状态信息、后台作业计数、工作目录、用户和主机名、Python virtualenv（如果存在）、最后一个命令的彩色返回值和 root/用户 sigil.
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - 灵感来自 [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme)，但带有啤酒图标.
* [bender](https://github.com/specious/bender) - Fancy two-line prompt with git integration.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有 unicode 符号的变体.
* [biraSkull](https://github.com/Shahryar-Pirooz/biraSkull.zsh-theme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), 包括根状态和 `git` 状态装饰.
* [biradate](https://github.com/vemonet/zsh-theme-biradate) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 主题，但在提示中显示日期而不是用户名.
* [birame](https://github.com/maniat1k/birame) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [birav2](https://github.com/shahid64/birav2-theme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme). Includes `git`, `rvm` and `virtualenv` status decorations.
* [bklyn](https://github.com/gporrata/bklyn-zsh) - 变体 [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) with customizations applied.
* [black-Void](https://github.com/black7375/BlaCk-Void-Zsh) - Includes account info, root user, using ssh, directory lotation, write permission, vcs info decorations.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) - 另一个 `git`-aware 主题.
* [blazux](https://github.com/blazux/omz-theme) - 包括 `git` 状态装饰和最后一个命令退出状态的笑脸/悲伤脸指示器.
* [blinks (max13ft)](https://github.com/max13fr/blinks.zsh-theme) - 为 oh-my-zsh 添加了 mercurial 支持 [blink](https://github.com/max13fr/blinks.zsh-theme) 主题.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) - 基于现有主题 [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme).
* [bliss](https://github.com/joshjon/bliss-zsh)  - 一个精致的主题，在不压倒您的工作空间的情况下注入色彩. 设计用于与 [bliss iTerm](https://github.com/joshjon/bliss-iterm) color scheme and [bliss dircolors](https://github.com/joshjon/bliss-dircolors). Includes `git` status decorations.
* [blokkzh](https://github.com/KorvinSilver/blokkzh) - Theme based on oh-my-zsh's built in [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 主题. 需要支持 unicode 的字体.
* [blox](https://github.com/yardnsm/blox-zsh-theme)  - 一个最小且快速的 ZSH 主题，向您展示您的需求. 它由块组成：每个块都显示在一对\[方括号\]内，您可以通过简单地创建一个函数来添加块.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - 最小的主题，显示 `git` 信息.
* [bluelines](https://github.com/apbarrero/bluelines) - Clear and blue theme.
* [bluo](https://github.com/varunpbardwaj/bluo) - 五颜六色的提示片段让人想起 [bullet-train](https://github.com/caiogondim/bullet-train.zsh) 或者 [powerlevel10k](https://github.com/romkatv/powerlevel10k). Includes `git` status dec或者ations.
* [bogo](https://github.com/cubasepp/zsh-bogo-theme) - 灵感来自 [zeta](https://github.com/skylerlee/zeta-zsh-theme) . 包括 `git` 和 ruby​​ 版本的装饰.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - 多行主题，最适合深色背景.
* [bougenville](https://github.com/bougenville/zsh-theme) - 变体 [dallas](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dallas.zsh-theme).
* [bronze](https://github.com/reujab/bronze)  - 一个跨外壳可定制的类似电力线的提示，带有用 go 编写的图标. 需要 [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
* [brs](https://github.com/evenhold/brs-zsh-theme) - 使用 `audtool` 在提示中显示当前歌曲.
* [bruh](https://github.com/haze/bruh) - Includes `git` status decorations.
* [brunty](https://github.com/Brunty/omz-brunty) - Brunty theme.
* [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) - Inspired by the [powerline](https://github.com/Lokaltog/vim-powerline) 和 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) themes.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF color theme.
* [bubblegum](https://github.com/ice-bear-forever/bubblegum-zsh) - 极简主义亮粉色主题，带有三角形字形和您的工作目录，仅此而已 - 为您提供最干净的外壳.
* [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme). Works best with [nerdfonts](https://github.com/ryanoasis/nerd-fonts).
* [bubblified (varaki)](https://github.com/varaki/bubblified-varaki.zsh-theme) - 基于 [bubblified (hohmannr)](https://github.com/hohmannr/bubblified). Changes color when root.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh)  - 灵感来自 Powerline Vim 插件. 它旨在简化，仅在相关时显示信息.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH theme, modified to just display time and directory.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - Simple, clean, and beautiful theme.
* [bureau-env](https://github.com/angus-lherrou/bureau-env) - Modification of the Oh-My-Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) theme that adds a Python virtual environment label to the left of the `git` block.
* [bureau-parrot](https://github.com/BenjaminGuzman/bureau-parrot) - 基于 [bureau](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme) . 包括 `git` 装饰.
* [bureau](https://github.com/isqua/bureau) - A clear and informative two-lined prompt. Includes git status optimized for large repositories.
* [buster](https://github.com/grantbuster/buster_zsh_theme)  - 与 WSL2 配合得很好. 基于 oh-my-zsh 的 Fox 和 Jonathan 主题.
* [cactus](https://github.com/welksonramos/cactus) - 带有“git”状态装饰的极简主义主题.
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - 糖果主题的轻量版.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - Shows active Python version and `git` decorations in the prompt.
* [celestialorb](https://github.com/celestialorb/zsh-theme)  - 受@celestialorb 启发的电力线主题. 包括 `git` 状态装饰、Kubernetes 集群信息（如果有）、当前 AWS 配置文件和区域以及活动的 virtualenv.
* [cf-ps1](https://github.com/mdan16/cf-ps1) - Displays the current foundation and organization and space of [Cloud Foundry](https://www.cloudfoundry.org/) in your prompt.
* [ch4rli3](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) - 精益和简单的主题.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme)  - 基于索林. 显示 Java、Scala、Go、Node、Python 和 Ruby 的当前活动版本.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme) - A tiny and beautiful theme for Oh-My-Zsh without anything superfluous. Includes `git` status decorations.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) - A ZSH prompt optimized for the [solarized](https://github.com/altercation/solarized) dark terminal theme.
* [chello](https://github.com/Abdalla981/chello)  - 适用于深色背景. 依赖于取决于 [autojump](https://github.com/wting/autojump), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) 和 [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [chi](https://github.com/akinjide/chi) - 针对 macOS 上的 iTerm 2 用户优化的 ZSH 主题.
* [chill](https://github.com/JKerboeuf/chill.zsh-theme) - 具有当前工作目录、最后一个命令退出状态和 `git` 状态的装饰.
* [chinipage](https://github.com/andresemartinez/chinipage-zsh-theme)  - 包含 `git` 装饰的极简主义主题. 需要与电力线兼容的字体和 [git-prompt](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git-prompt) 插入.
* [chrisandrew.cl](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme)  - 包括 `git` 装饰. 需要与电力线兼容的终端字体.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - 显示时间戳、大换行符、git 分支和状态.
* [clarity](https://github.com/nbitmage/clarity.zsh) - 专为简单性和可扩展性而设计.
* [classyTouchName](https://github.com/dylanroman03/classyTouchName) - Oh-my-zsh theme inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh). Works better with dark backgrounds. Includes `git` status decorations.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - Minimal, clean theme with `git` support.
* [clean (akz92)](https://github.com/akz92/clean) - 极简主义 ZSH 主题.
* [clean (brandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - A minimalist variant of [pure](https://github.com/sindresorhus/pure). Pure is not clean, clean is not pure.
* [clean (patr1ot)](https://github.com/Patr1ot/clean.zsh-theme) - Fork of the upstream [clean](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) with host information added.
* [cleansh](https://github.com/diegoos/cleansh) - Minimalist, includes `git`, Ruby, node and Python version status decorations. Works with standard fonts.
* [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) - 带有 `git`、nix-shell 和 virtualenv 状态装饰的极简主义主题.
* [cloudy](https://github.com/Huvik/Cloudy) - 最小的多云 ZSH 主题.
* [clover](https://github.com/tzing/clover.zsh-theme) - 灵感来自 [zeta](https://github.com/skylerlee/zeta-zsh-theme) 和 [pure](https://github.com/sindresorhus/pure).
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - Configuration file for [cmder](http://cmder.net/) configured to work in quake mode with ZSH and a modified [Agnoster](https://gist.github.com/agnoster/3712874) 主题.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) - A ZSH theme that matches the theme of Cmder, a popular terminal emulator for windows.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) - Cobalt 2 theme with `git` extensions.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Codemachine 主题.
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - 灵感来自 [bashi](https://github.com/eli-oat/bashi), 在你的提示中包含一个猴子和 `git` 信息.
* [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - Based on agnoster, but has a right-prompt for vi-mode that displays `--INSERT--` and `--NORMAL--`, in a powerline look.
* [coldark](https://github.com/ArmandPhilippot/coldark-zsh-theme)  - 为阅读舒适度而设计的蓝灰色主题. 包括 `git` 装饰.
* [collon](https://github.com/lambdalisue/collon.zsh) - Lightweight theme with `git` status decorations, cwd, time, host, exit status of last command. Does not require special fonts.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - 允许按主机提示着色，显示 `rvm`、`virtualenv` 和 `git` 信息.
* [common](https://github.com/jackharrisonsherlock/common) - 一个简单、干净和最小的提示，显示当前工作目录、主机名、AWS 保管库角色、后台作业、当前 SHA、最后一个命令的退出代码以及 `git` 分支和状态.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - 针对深色背景优化的色彩鲜艳的主题.
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) - Clean and effective ZSH theme with git and npm support.
* [cramin](https://github.com/FelipeCRamos/craminzsh) - Minimal interface with support for github plugins, based on [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [cryo](https://github.com/cryocaustik/cryo-zsh-theme) - 添加日期和时间的原始 oh-my-zsh 主题的独立克隆.
* [crème fraîche](https://github.com/koenwoortman/creme-fraiche-zsh-theme) - Works best with light terminal backgrounds, includes `git` and `vi`-mode status decorations.
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 Powerline Vim 插件的带有可爱表情符号的 macOS oh-my-zsh shell 主题.
* [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) - Works well on dark background, has `git` status decorations.
* [cypher-ruby](https://github.com/ston1x/cypher-ruby) - Similar to [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) 但包括活动的 Ruby 版本.
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) 和 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) theme in a container.
* [daily](https://github.com/ghlin/zsh-theme-daily) - 包括 `git` 和 `ssh` 状态装饰.
* [damino](https://github.com/njdom24/Damino-Zsh-Theme) - 带有“git”装饰的最小电力线主题.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) - 内容丰富、极简，最重要的是，以 X 战警为主题.
* [daniloheraclio](https://github.com/daniloheraclio/daniloheraclio-zsh-theme) 灵感来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme. Has `git` and last command exit status decorations. Requires a nerdfont to render properly.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - This version of the popular [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) 主题已通过近乎完整的重写实现模块化和一些新功能得到增强.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - 基于`ys`和 [astro](https://github.com/iplaces/astro-zsh-theme) themes.
* [dbern](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) - Includes battery status and load average decorations.
* [delta (asavoy)](https://github.com/asavoy/delta-zsh-theme)  - 最小化 ZSH 主题以减少干扰. 包括一个 iTerm 颜色设置文件.
* [delta (dongri)](https://github.com/dongri/delta-zsh-theme) - 另一个带有嵌入式 `git` 状态的最小主题.
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
* [drkat](https://github.com/katrinaalaimo/drkat-zsh-theme) - 让人联想到 [Powerline](https://github.com/powerline/powerline) . 包括目录、`git` 状态和主机名装饰.
* [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) variant.
* [dtheme](https://github.com/OlukaDenis/DTheme)  - 针对使用日晒终端配色方案和“git”的人进行了优化. 最适合使用 unicode 字体.
* [duckster](https://github.com/ducky/duckster) - Gitster ZSH 主题的一个分支，更加新鲜.
* [ducula](https://github.com/janjoswig/Ducula) - Inspired by Dracula project. Includes `git` status decorations, username and hostname abbreviations, virtual environment, current working directory, return status of last command and the time.
* [dustmod](https://github.com/bmihaila/dustmod) - Derived from the [dst](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) theme in oh-my-zsh.
* [dzhi](https://github.com/pentago/dzhi-zsh-theme) - Optimized for people using [Nord](https://www.nordtheme.com/). Includes `git` status decorations.
* [eckig](https://github.com/fouladi/eckig)  - 带有 utf-8 图标的极简主义主题. 包括 `git` 状态装饰和时钟.
* [eggshausted](https://github.com/inutano/eggshausted) - 一个 `git`-aware 主题，适合那些厌倦了出错的人.
* [eivmosn](https://github.com/eivmosn/eivmosn-omz) - 修剪了“ys”主题的变体.
* [eleastic](https://github.com/jinseobhong/eleastic-zsh-theme) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme), optimized for solarized terminal theme, includes `git` status decorations. Requires powerline-compatible font.
* [elessar](https://github.com/fjpalacios/elessar-theme) - 基于 `git` 的主题 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) . 需要与电力线兼容的字体.
* [elm](https://github.com/gacallea/elm-zsh-theme) - 包括 `git` 状态、user@host、日期、时间和路径装饰器.
* [elsa](https://github.com/faycito/elsa) - 包括根状态、密码和 `git` 状态装饰.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - Emoji flavored [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ohmyzsh/ohmyzsh) 主题.
* [emoji](https://github.com/masaakifuruki/emoji.zsh-theme) - 基于  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 主题，将 `git` 提示符号替换为表情符号，以提高清晰度.
* [emojirussell](https://github.com/Bergiu/emojirussell) - 基于  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 主题，带有当前工作目录的状态装饰，最后一个命令退出状态，`git` 分支和状态.
* [endless-dog](https://github.com/qwelyt/endless-dog) - oh-my-zsh-compatible theme that mimics grml-zsh-config.
* [enlightenment](https://github.com/w33tmaricich/enlightenment) - Includes decorations for `git` status, `vi`-mode indicator, and the time for last command to execute.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - 在终端中占用大量空间.
* [erfan](https://github.com/ekm507/erfan-zsh-theme) - 的组合 [af-magic](https://github.com/和yfleming/oh-my-zsh) 和 [macovsky](https://github.com/championswimmer/oh-my-zsh/blob/master/themes/macovsky.zsh-theme) themes. Includes `git` 和 `virtualenv` status decorations.
* [eriner](https://github.com/zimfw/eriner) - 受电力线启发的 Zim 叉子 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 提示主题. 包括 `git` 状态装饰.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - A simple theme with `git` information.
* [eucalyptus](https://github.com/relastle/eucalyptus) - Simple one-line theme for minimalist vi-mode users inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory 和 current path.
* [excess](https://github.com/davydovanton/excess.zsh-theme) - 简单的 ZSH 颜色主题.
* [ez-pz](https://github.com/mangosmoothie/ez-pz) - 带有“git”状态装饰的极简主义主题，灵感来自 [bureau](https://github.com/isqua/bureau).
* [fall](https://github.com/jottenlips/seasonal-zshthemes) - Minimalist theme with fall icons. Includes `git` status decorations.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) - Minimal ZSH prompt that works better on dark backgrounds.
* [fdT2K](https://github.com/FDT2k/FDT2K-theme)- 基于 [agnoster](https://github.com/agnoster/agnoster-zsh-theme)，预设包括 virtualenv、最后命令状态、`nvm`、`docker machine` 和 `git`、`hg` 和 `bzr` 状态装饰.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme)  - 干净、简单、兼容且有意义. 在 ANSI 颜色下在 Linux、Unix 和 Windows 上进行了测试.
* [filthy](https://github.com/molovo/filthy) - A disgustingly clean ZSH prompt.
* [fish](https://github.com/Raniconduh/zshfish)  - ZSH 主题让人想起默认的鱼壳主题. 包括 `git` 状态装饰.
* [fishy-lite](https://github.com/sudorook/fishy-lite) - 原叉 [fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy)  oh-my-zsh 中的主题，删除了许多无关内容以提高加载速度. 包括一个电池表和 `git` 状态显示，可以在提示的右侧启用.
* [fishy2](https://github.com/akinjide/fishy2) - ZSH theme inspired by [original fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy).
* [fizzy](https://github.com/Brokenhammer72/fizzy) - 极简提示，包括 `git` 状态装饰.
* [fluent-git](https://github.com/RobertKozak/fluent-git) - Displays time of last command execution, error code, hostname, username, `git` status, kubernetes cluster and namespace, path and ssh connection status.
* [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) - 自定义设置 [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status decorations.
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - Includes status of last command, `git` information and current directory.
* [frank](https://github.com/ronmackley/frank-theme)  - Frank 言简意赅，在一行中简洁而易读地显示信息. 弗兰克坚持事实，只在重要的时候告诉你额外的事情.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - 叉子 [terminal-party](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) 主题.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - 基于的主题 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh-theme.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - 红色版本 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) theme from oh-my-zsh.
* [fritz](https://github.com/fritzccc/fritz-zsh-theme) - Works well on dark backgrounds. Includes `git` status decorations.
* [frlo](https://github.com/fiorillo/frlo) - 使用您计算机的主机名提出（希望）独特的三色主题以显示在您的提示中，以便您一眼就知道您登录的是哪台机器.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - 支持 `git` 和 `svn` 的彩色两行主题.
* [furio](https://github.com/hectorpalmatellez/furio-theme) - 叉子 [Cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) oh-my-zsh theme. with different colors and emojis.
* [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) - 彩色主题，在深色背景下效果更好.
* [gaia](https://github.com/gcaracuel/gaia.zsh-theme) - 原来是一个叉子 [Bureau](https://github.com/isqua/bureau) adds new virtual environments info to the prompt: Kubernetess, virtualenv, rbenv and Java versions. Includes git status integration.
* [gal](https://github.com/x6r/gal) - gal 基于 [gallois](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme).
* [garden](https://github.com/fecat233/garden) - Works better with a dark terminal background, includes `git` status decorations.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto 在您需要的时候提示您需要的信息.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme)  - Nicola Racco 的主题. 需要 `rvm` 和 `git` 插件.
* [gbt](https://github.com/jtyr/gbt)  - Go Bullet Train 是一个非常可定制的提示生成器，灵感来自 Bullet Train，运行速度更快. 包括许多不同状态的汽车.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - 将 oh-my-zsh gentoo 主题拆分为一个单独的 repo，供非 omz 用户使用.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) - 将主机信息添加到 [geometry](https://github.com/geometry-zsh/geometry) 主题.
* [geometry](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
* [ghoti](https://github.com/lonr/ghoti)  - 模仿 `fish-shell` 默认提示. 包括 `git` 装饰.
* [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) - 灵感来自 [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme), 包括 `git` 装饰、IP 地址、主机和路径.
* [gimbo](https://github.com/gimbo/gimbo.zsh-theme) - 一个变种 [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) with more features, a little eye candy and context-sensitive extra lines. Includes `git` status decorations, history number, username/hostname context, directory status, status of last command if it failed, and the Python virtualenv name if present.
* [gimme](https://github.com/nralbrecht/gimmezsh) - A simplistic theme for ZSH with `git` integration. Inspired by the [gitsome](https://github.com/mtully/gitsome) 主题.
* [girazz](https://github.com/mdentremont/girazz) - A modification to the gnzh theme which adds `vi` mode to the right prompt.
* [git-prompt (awgn)](https://github.com/awgn/git-prompt) - `bash`、`zsh` 和 `fish` 的快速 `git` 提示.
* [git-prompt (olivierverdier)](https://github.com/olivierverdier/zsh-git-prompt)  - 显示有关当前 `git` 存储库的信息. 特别是分支名称、与远程分支的差异、暂存或更改的文件数等.
* [git-prompt (woefe)](https://github.com/woefe/git-prompt.zsh) - 受 Olivier Verdier 启发的 ZSH 的快速、可定制、纯 shell、异步 Git 提示 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) and very similar to the "Informative VCS" prompt of fish shell.
* [git-prompt-kit](https://github.com/olets/git-prompt-kit) - 一组可配置的组件，用于以最少的编码创建功能丰富、高性能的 Git 感知 zsh 提示（又名主题）.
* [git-simple](https://github.com/ZakharEl/git-simple-theme) - 简单的主题，包括详细的 `git` 状态装饰.
* [gitsome](https://github.com/mtully/gitsome) - Super simple prompt with `git` info, optimized for the [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) color scheme.
* [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) - 显示命令和 `git` 状态装饰.
* [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) - When in a `git` repo, it shows the location from the `git` repository root folder. When not in a `git` repo, it shows the path relative to home, `~`.
* [gitster (zimfw)](https://github.com/zimfw/gitster) - Zim fork of shashankmehta's [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) prompt theme
* [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) - 从原来的分叉 [gitster](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) 主题.
* [gk3000](https://github.com/gk3000/gk3000-oh-my-zsh-theme) - 包括 `git` 状态装饰和当前目录的完整路径.
* [glimmer](https://github.com/martnu/glimmer) - Includes `git` branch, time and user@host.
* [gndx](https://github.com/gndx/gndx-zsh-theme) - 包括 `git` 状态、主机名、目录和最后一个命令退出状态装饰.
* [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) - Customization of [gnzh.zsh-theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) from oh-my-zsh.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) - Theme for iTerm 2 and ZSH, includes `git` decorations, user@host, path and date.
* [gops](https://github.com/noxer/gops)  - 快速类似电力线的提示. 包括 `git` 状态、当前目录、根状态装饰.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - 简单但信息丰富的主题，包括 `git` 装饰和最后一个命令的返回状态.
* [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) - Minimalist, includes `git` status decorations.
* [grs](https://github.com/gersontpc/zsh-theme-grs) - Includes `git` status decorations, user id and working directory.
* [gruvbox (hgaiser)](https://github.com/hgaiser/gruvbox-zsh) - Sets colors from the [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [gruvbox (sbugzu)](https://github.com/sbugzu/gruvbox-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874), 使用相同的颜色 [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [guezwhoz](https://github.com/guesswhozzz/guezwhoz-zshell) - Minimalist, includes `git` status decorations.
* [guri](https://github.com/victorfsf/guri) - 一个简单快速的 Oh-My-Zsh 主题，基于 [Pure](https://github.com/sindresorhus/pure)'s design.
* [hackersaurus](https://github.com/bhilburn/hackersaurus) - A theme with `git` status and exit code of last command run embedded in the prompt. Related to [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [halil](https://github.com/5m0k3r/zsh-themes) - oh-my-zsh 的分叉 [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) 主题.
* [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme) - A simple theme with the first character being 花(hana), the kanji for flower. This theme was inspired by a keycap set called DSA Hana. This pairs well with the [hana atom](https://github.com/arturoalviar/hana-matcha-syntax) theme. Includes `git` status decorations.
* [handy](https://github.com/hanleylee/handy)  - 多彩和轻量级的主题. 显示 root 状态、`git` 状态、当前目录和 `user@hostname` 装饰.
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) - Shows `git` branch and status, last command exit code, last command execution time if more than `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`.
* [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) - 基于氧化物，包括 `git` 状态装饰和当前用户/主机信息.
* [haribo](https://github.com/haribo/omz-haribo-theme) - 简单的 `git` 状态 + 提示中的时间戳.
* [hcompact](https://github.com/fusion809/zsh-theme) - 显示时间、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [headline](https://github.com/Moarram/headline-zsh-theme) - 响应式 ZSH 主题，具有 Git 状态信息和提示上方的彩色线条.
* [heart](https://github.com/gko/heart) - Heart themed prompt for light backgrounds.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - Simple, no-nonsense and clean, with support for `git` and return codes.
* [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - 基于 [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau)，添加了 `git` 状态装饰和 `npm` 状态.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hematite](https://github.com/bigdave/hematite) - 极简主义促销，试图仅显示在给定时间非常有用的状态装饰.
* [hexagon](https://github.com/diogoazevedos/hexagon) - Minimalist zsh theme based on [geometry](https://github.com/geometry-zsh/geometry).
* [hfulldate](https://github.com/fusion809/zsh-theme) - 显示时间、日期、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - Inspired by robbyrussell theme + ssh connection status prompt.
* [hina](https://github.com/ucpr/hina) - Written in `golang`, includes `git` status decoration and kubernetes context.
* [hip-fellow](https://github.com/haitaim/hip-fellow) - Includes `git` status decorations and works with standard fonts.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 一个变种 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [home](https://github.com/sheerun/home) - 漂亮而简短的单行主题，让您有宾至如归的感觉.
* [hometown](https://github.com/olets/hometown-prompt) - 一个功能丰富、高性能的 `git` 感知 ZSH 主题，包含用户、主机、时间、当前工作目录及其父级的段，以及 Git 存储库中详细的完整 Git 状态.
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - oh-my-zsh 和 iTerm 2 的 Honukai 主题和颜色.
* [horizontal](https://github.com/nuimk/horizontal) - 带有水平分隔符的两行提示.
* [hornix](https://github.com/fusion809/zsh-theme) - 显示时间和日期、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [horse-sh](https://github.com/emileswarts/horse-sh) - A very minimal brown/red ZSH theme.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - 简单干净，包括最后执行的命令的返回码.
* [hug](https://github.com/xxninjabunnyxx/hug-zsh) <i>- When you&#39;re working and need a hug.</i> <b>- 当你工作并需要一个拥抱时。</b> <i>Includes `git` status.</i><b>包括 `git` 状态。</b>
* [humbled](https://github.com/saravanabalagi/zsh-theme-humbled) - A clean and humble theme with support for `condaenv`, `virtualenv` and `git` status decorations left aligned with the working directory in bold.
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
* [illustion](https://github.com/shabane/illusion) - Includes username, current working directory, git status and last command status decorators.
* [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) - 叉子 [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) with spacing improvements and an updated icon. Includes `git` status information.
* [imp](https://github.com/igormp/Imp) - 基于 [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) and optimized for dark backgrounds.
* [infernus](https://github.com/jshiell/infernus-zsh-theme) - 极简主义主题，更适合深色背景.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) - 显示“git”状态、后台作业、远程主机和其他信息的清洁主题.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - 的扩展 [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) 使用电力线字体的主题.
* [itg](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy's theme.
* [ivy](https://github.com/ivyhjk/ohmyzsh-theme-ivy)  - 适用于深色背景. 包括 user@host、`git` 状态和时间装饰器. 基于 [obraun](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#obraun) 主题.
* [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme)  - 基于精致和 ys 主题，包括 `git` 状态装饰. 包括一个可选的 iterm2 颜色方案.
* [jake](https://github.com/JakeHuneau/Jake.zsh-theme) - 如果分支有未推送的更改，则显示时间、当前目录和 `git` 分支信息，包括分支名称和红色 +.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - Optimized for dark backgrounds, includes `git` status and `rvm` status.
* [jc](https://github.com/jclementex/jc-zsh-theme) - For dark terminal backgrounds, includes `git` status information.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - 松散地基于 ys 主题.
* [jerome](https://github.com/jeromescuggs/jerome-theme) - Colorful theme based on the [dieter](https://github.com/jeromescuggs/jerome-theme) 主题，但带有黄色主机名. 包括 `git` 装饰.
* [jhleeeme](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) - 包括 `git` 和 python virtualenv 状态装饰、用户、密码、时间和系统名称.
* [jon](https://github.com/Jon-Schneider/jon.zsh-theme) - 一个简化 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) with the colors of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - 灵感来自 [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme), 包括 `git` 状态.
* [jovial](https://github.com/zthxxx/jovial) - 显示主机、用户、路径、开发环境、`git` 分支，其中 python venv 处于活动状态.
* [jpegleg](https://github.com/jpegleg/zshrc) - 类似于暗血主题，包括时间戳和 `git` 装饰.
* [js-magic](https://github.com/JSextonn/js-magic) - A simplified take on [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) . 包括当前工作目录和 `git` 状态装饰.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
* [just-another](https://github.com/supertassu/another-theme) - Just another theme, with hostname when you're sshed to another machine.
* [just-around-the-corner](https://github.com/DevinLeamy/just-around-the-corner)  - 倒计时直到圣诞节. 包括 `git` 状态装饰.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter)  - 带有 `git`、`svn`、`npm`、`rvm` 和网络意识的电力线风格主题. 需要与电力线兼容的终端字体.
* [jyumpp](https://github.com/Jyumpp/jyumpp-zsh-theme) - Configuration file and installer for Powerlevel 10K.
* [kali](https://github.com/h4ck3r0/kali-theme) - Includes `git` decorations.
* [karu](https://github.com/zaari/karu) - 极简单行 ZSH 提示.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) - 包含其他主题的一些功能的主题.
* [kenton](https://github.com/notnek/zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) - 丰富多彩的主题，包括 iTerm 2 配色方案.
* [kgzsh](https://github.com/Kashugoyal/kgzsh) - 包括`git`状态deorations，适用于较暗的背景.
* [kido](https://github.com/KidoThunder/kido-zsh-theme)  - 基于 `ys` 和 `robbyrussell` 主题. 包括上次命令运行的退出代码、python virtualenv 和 VCS 状态的装饰器.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - Based on Fishy theme, but shows full paths instead of abbreviated directories and only shows user@machine in `ssh` sessions and docker containers.
* [kirkdawson](https://github.com/kdawson133/KirkDawson)  - 受电力线启发. 包括 `git` 状态、最后命令退出状态、用户@主机名、工作目录以及用户是否以 root 身份运行的提示装饰.
* [kiss](https://github.com/rileytwo/kiss)  - 用于 oh-my-zsh、VSCode、iTerm2、Neovim 和 RStudio 的简单主题. 包括 `git` 状态装饰.
* [kketcham](https://github.com/prototype27/kketcham) - Theme with nifty colors on the `git` info.
* [klassiker](https://github.com/mrdotx/zsh-theme) - 带有 `git` 装饰的极简主题.
* [korittg](https://github.com/dkorittki/korittg-zsh-theme) - Minimalistic but informative. Includes decorations for `git` status, current directory and the `kubectl` context and namespace.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme)  - 最适合深色背景. 包括 `git` 状态装饰.
* [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - 为深色终端设计的两行主题，具有 `git` 装饰.
* [krak3n](https://github.com/krak3n/zsh-theme) - 显示 golang 版本和当前的 `git` 分支.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) - A dark theme for ZSH.
* [kube](https://github.com/tigerjz32/kube-zsh-theme) - 基于 [macos-terminal](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal) , 包括 `kubectl` 上下文. 有时间、目录和 `git` 状态装饰.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme)  - Agnoster 前叉针对日晒终端进行了优化. 需要与电力线兼容的字体.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) - Colorful theme with `git` and `hg` status information, ability to add host-specific colors to hostname.
* [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme) - A simple theme with the first character being 九(kyuu), the number 9. The primary color is blue with a magenta accent. Includes `git` status decorations.
* [lagune](https://github.com/noplay/lagune) - 一个最小的 ZSH 主题.
* [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) - 灵感来自 robbyrussell [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) theme. Includes `git` status decorations.
* [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) - A ZSH theme optimized for `git` users who use unicode-compatible fonts and terminal applications.
* [lambda-blazinggit](https://github.com/zalefin/lambda-blazinggit)  - 包括快速、详细的 `git` 信息. 需要书呆子字体和 [gitstatus](https://github.com/romkatv/gitstatus) 插入.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - 包含“git”信息的极简提示.
* [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) - 基于 lambda 的简单主题，带有 `git` 状态和 virtualenv 信息.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - 一个简单的 ZSH 主题，针对 `git` 使用进行了优化.
* [lambda-p](https://github.com/paimanb和i/lambda-p) - Inspired by the [lambda mod](https://github.com/halfo/lambda-mod-zsh-theme) 和 [Lambda V](https://github.com/vkaracic/lambdav-zsh-theme) themes. Includes `git` status decorations.
* [lambda-pure](https://github.com/marszall87/lambda-pure) - 基于 Pure 的最小 ZSH 主题，添加了 NodeJS 版本.
* [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) - Lambda 和 Fishy 主题的组合，包括 `git` 状态装饰.
* [lambda-zen](https://github.com/seamile/lambda-zen) - inspired by [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) with graphical `git` status decorations.
* [lambder](https://github.com/avillen/zsh-theme-lambder) - 包括 `git` 状态装饰，最适合深色终端主题.
* [laniksj](https://github.com/LanikSJ/laniksj-zsh-theme)  - 在深色背景下效果最佳. 基于伟大的`ys`主题和 [Honukai ZSH Theme](https://github.com/oskarkrawczyk/honukai-iterm-zsh). Shows root status and `git` status decorations.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - 针对暗终端进行了优化，具有本地和远程系统的变体.
* [leafia](https://github.com/Ghostrick/leafia-prompt) - 显示 `git` 状态信息的多叶 prezto 主题.
* [lean](https://github.com/miekg/lean) - 灵感来自 [pure](https://github.com/sindresorhus/pure). Includes `git` status and background job decorations.
* [lemon](https://github.com/carlosvitr/lemon_zsh)  - 许多美丽的颜色供您欣赏. 小心和耐心地完成. 包括 `git` 状态和 ruby​​ 版本装饰.
* [leon](https://github.com/prince-an/Leon_zshTheme)  - 在浅色背景下效果很好. 包括 `git` 状态、时间、用户名@主机、工作目录和最后一个命令退出状态装饰.
* [leverage](https://github.com/gschnall/leverage) - 基于 [minimal](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme), 使用颜色和额外的 `¬` 字符，以更好地区分命令行提示符和输出.
* [lewis](https://github.com/lewisflude/oh-my-lewis) - Black, white and red theme. Shows `git` status information.
* [lightbulb](https://github.com/lightbulb703/lightbulb-zsh-theme) - Includes decorations for kernel, OS version, uptime and `git`.
* [lighthaus](https://github.com/lighthaus-theme/zsh) - A prompt that compliments the [Lighthaus](https://github.com/lighthaus-theme/lighthaus) 主题. 显示 `git` 信息、github/gitlab 徽标并在发生更改时显示更改.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) - Minimalist theme, best on a dark terminal background.
* [lilith](https://github.com/aknackd/zsh-themes) - Modification of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) 和 [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [lime](https://github.com/yous/lime) - Simple and easily customizable ZSH theme.
* [limpide](https://github.com/shooteram/limpide) - 修改版 [miloshadzic](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) 显示父目录和当前目录的主题.
* [linuxer](https://github.com/patrick330602/linuxer) - Inspired by Yaris Alex Gutierrez's [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh), Yad Smood's `ys`, and the [Bureau](https://github.com/isqua/bureau) 主题.
* [linuxero](https://github.com/andreshincapier/linuxero) - Minimalist. Includes decorations for root status, current directory, `git` status, current ruby rvm environment and current python virtualenv.
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt with useful information when you need it. It shows you what you need when you need it. You will notice what changes when it changes, saving time and frustration.
* [lish](https://github.com/bashelled/lish) - A casual theme. No roughness, just smooth. Includes `git`, user@host, last command exit status, current directory, current time and root status decorators.
* [liver](https://github.com/RenoirTan/liver.zsh-theme) - Colorful, includes `git` status, user, host, current and relative path to the current repository root decorations.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) - 挑剔的美洲驼使用的极简主义主题.
* [logico](https://github.com/logico/logico-zsh-theme)  - 有 `git` 装饰. 显示 vi 模式的远程状态和指示灯.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - 基于 Sindre Sorhus 纯主题的德克萨斯主题.
* [longsilvern](https://github.com/long263/longsilvern-zsh-theme) - 包括 `git` 和紧凑的 `pwd` 装饰.
* [lorond](https://github.com/lorond/zsh-lorond/) - 精简版 [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) . 包括 `git` 状态，适用于标准字体.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme)  - lambda-mod 主题的变体. 具有 `git` 装饰，需要与电力线兼容的终端字体.
* [luke](https://github.com/xueguangl23/luke_zsh_theme)  - 包括 `git` 装饰. 基于 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh theme.
* [lukerandall-extended](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) - Extended version of the [lukerandall](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) theme. Includes decorations for `git` status and the status of the last command run.
* [lunachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/lunachar.zsh-theme) - Minimalist theme.
* [macos](https://github.com/alejandromume/macos-zsh-theme) - Includes `git` status decorations.
* [mad](https://github.com/MartinWie/ohmyzsh-theme-mad) - 包括 `git` 状态和最后命令执行时间装饰.
* [magicmace](https://github.com/zimfw/magicmace) - Inspired by xero's ZSH prompt and [eriner's prompt](https://github.com/zimfw/eriner) . 包括活动 python `venv` 的状态代码、最后一个命令的退出状态、缩短的工作目录、`git` 状态装饰.
* [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN 的魔法主题.
* [maivana](https://github.com/nylo-andry/zsh-themes) - Includes `kubectl` context, `git` status decorations.
* [materialshell](https://github.com/carloscuesta/materialshell) - 一个 [material design](https://material.io/guidelines/style/color.html) 您的外壳主题具有良好的对比度和重要部分的颜色流行. 专为保护眼睛而设计.
* [matrix](https://github.com/pot-code/matrix-zsh-theme) - 变体 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 风格看起来像 Matrix 电影三部曲中的东西. 包括 `git` 状态装饰.
* [matter](https://github.com/mrobillard/matter-zsh-theme) - Shows `git` status, AWS vault role, background jobs, exit code of last command & hostname.
* [mau](https://github.com/vichargrave/mau) - A ZSH theme with a cat twist. Includes `git` status decorations. Based on the [kphoen](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kphoen.zsh-theme) 和 [smt](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/smt.zsh-theme) themes.
* [mbolis](https://github.com/mbolis/mbolis-zsh-theme) - 包括 `git` 装饰，如果是 root 用户，则更改提示颜色，活动作业和 [jenv](https://github.com/jenv/jenv) 一体化.
* [mdmini](https://github.com/MarioDena/MDmini) - 包括 `git` 和 `ssh` 状态装饰.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt)  - 包含键盘模式、所有权信息和其他上下文信息的最大化提示，以 λ 作为提示字符. 需要 [hooks](https://github.com/willghatch/zsh-hooks) 插入.
* [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) - Includes `git` status decorations, shows exit code of last command if nonzero.
* [mexassi](https://github.com/Mexassi/mexassi-zsh-theme)  - 检查 `/sys/class/power_supply` 文件夹以确定系统是安装在笔记本电脑还是台式机上. 读取电池百分比 grepping acpi 命令并在提示符中显示. 包括 `git` 装饰.
* [mh-fzj](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) - Includes `rvm` and `git` status decorations.
* [michaelpass](https://github.com/michaelpass/michaelpass.zsh-theme) - POSIX-friendly cross-platform [alanpeabody](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) mod w/ convenient timestamps and full git/ruby support.
* [midin](https://github.com/xlshiz/midin) - 适用于深色终端背景，包括 `git` 状态装饰.
* [mike-was-here](https://github.com/leguim-repo/mike-was-here-theme/) - Minimalist, includes `git` status decorations.
* [milight](https://github.com/frodoslaw/milight-zsh) - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
* [min](https://github.com/andrepolischuk/min) - 一个简约的 ZSH 提示.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind.
* [mini-simple](https://github.com/ysl2/mini-simple-zsh-prompt)  - 极简主义者. 包括 `vcs` 状态装饰.
* [minima (Brolly0204)](https://github.com/Brolly0204/zsh-minima) - 包括`git`、`node`、`golang`、`yarn`、`php`、`docker`和`python`状态装饰.
* [minima (ednikolenko)](https://github.com/ednikolenko/minima)  - 带有 `git`、`docker`、`go`、`node`、`npm`、`python` 和其他指标的最小 ZSH 主题. 对某些标记使用 unicode 字符.
* [minimal (5amu)](https://github.com/5amu/minimal-prompt) - Minimal prompt, uses nerdfonts. Includes `git` and `vpn` status decorations.
* [minimal (casalinovalerio)](https://github.com/casalinovalerio/minimal-prompt) - 最小提示，包括 `git` 和 vpn 状态装饰.
* [minimal (glsorre)](https://github.com/glsorre/minimal/) - 最小的异步 ZSH 主题优化用于 [Fira Code](https://github.com/tonsky/FiraCode) 字体和 [Solarized Light](https://ethanschoonover.com/solarized) 终端主题.
* [minimal (subnixr)](https://github.com/subnixr/minimal) - Minimal yet feature-rich theme.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) - 黑暗终端的主题，包括右侧提示中的 `git` 装饰.
* [minimal2](https://github.com/PatTheMav/minimal2)  - 一个最小且可扩展的 ZSH 主题. 分叉自 [subnixr's original](https://github.com/subnixr/minimal) and adapted for [Zimfw](https://github.com/zimfw/zimfw).
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) - 灵感来自 oh-my-zsh 的 kolo 主题.
* [mira](https://github.com/mbStavola/mira) - 一个修改 [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) 带有时间信息和简化的开始提示.
* [mirage](https://github.com/robin-pfeiffer/ohmyzsh-mirage-theme/) - 包括 `git` 状态、最后命令退出代码、`sudo` 时间戳文件是否存在以及当前活动的 Python 虚拟环境的提示装饰.
* [miramare](https://github.com/franbach/oh-my-deepin-miramare)  - 包括 `git` 状态装饰. 最适合搭配 [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
* [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs' ZSH theme.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - Optimized for dark backgrounds.
* [mnml](https://github.com/mnml-theme/prompt) - 带有 `git` 状态装饰的最小主题.
* [mochi2](https://github.com/mochidaz/zsh-themes) - Minimalist theme. Includes `git` and `hg` status decorations.
* [mochi](https://github.com/mochidaz/zsh-themes) - Simple theme, designed to resemble rust main function. Includes `git` and `hg` status decorations.
* [moderno](https://github.com/obrassard/moderno-zsh) - 一个简单而现代的 ZSH 主题，灵感来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme from Oh-My-ZSH. Includes `git` status decorations.
* [modesty](https://github.com/saravanabalagi/zsh-theme-modesty) - A clean and modest ZSH theme with `condaenv`, `virtualenv` and `git` status decorations displayed neatly right aligned.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - 基于 [agnoster](https://gist.github.com/agnoster/3712874).
* [momoyo](https://github.com/momoyo-droid/momoyo-zsh-theme)  - 让人想起电力线. 包括 `git` 状态、用户名和工作目录的装饰.
* [moonline](https://github.com/kagamilove0707/moonline.zsh) - Minimal but easily extensible prompt.
* [moux](https://github.com/gagbo/moux) - 适用于深色终端背景，包括 `RPROMPT` 中的 `git` 装饰.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - 提供有关您所在存储库的有用信息（在您的提示中）.它目前适用于 [Git](https://git-scm.com/) 和 [Mercurial](https://www.mercurial-scm.org/)， 在下面 [ZSH](https://en.wikipedia.org/wiki/Zsh) 也 [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [multiline](https://github.com/jan-auer/zsh-multiline) - Powerline-esque theme based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [muslim](https://github.com/nksoff/muslim) - A simple minimal ZSH prompt theme.
* [musy](https://github.com/THaGKI9/musy-zsh-theme) - Inspured by muse theme. Includes `git` status decorations.
* [my-hl2](https://github.com/liamm91/my-hl2)  - 包括 virtualenv、`git` 状态和目录装饰. 基于 omz  [half-life](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/half-life.zsh-theme) 主题.
* [myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia's myzsh theme.
* [mzt](https://github.com/honbey/mzt) - 设置`LS_COLORS`，着色`diff`并包括`git`状态和当前工作目录装饰.
* [nanofish](https://github.com/tweekmonster/nanofish) - 为纳米技术主题添加鱼式目录提示.
* [nbrylevv](https://github.com/nbrylevv/nbrylevv-zsh-theme) - 带有文本“git”状态装饰的极简主义主题.
* [nctu](https://github.com/leovincentseles/nctu.zsh-theme)  - 强调速度的轻量级主题. 包括 `git` 状态装饰.
* [neewbie](https://github.com/neewbee/neewbee.zsh-theme)  - 带有 `git` 装饰的最小主题. 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell).
* [neon-potato](https://github.com/algosuna/neon-potato)  - 多彩和简约的主题. 包括 `git` 装饰.
* [neon](https://github.com/sahariko/neon) - A pretty and minimal ZSH theme with `git` decorations.
* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - 带有书呆子字体的 ZSH 提示主题.
* [nescalante](https://github.com/nescalante/zsh-theme) - 针对深色终端背景进行了优化，包括 `git` 装饰.
* [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) - Includes `git` decorations and `vi`-mode indicator.
* [newt](https://github.com/softmoth/zsh-prompt-newt) - Fat & fast theme – beautiful inside and out, styled segments done right. Extremely customizable, includes `git`, username, execution time, directory, background jobs and edit mode decorations.
* [newton](https://github.com/sebastienfilion/zsh.newton) - Includes `git` status and external IP address decorations.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - A very basic theme which just features an macOS bike icon.
* [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - Colorful, shows `git` status decorations.
* [nikitakot](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme) - Small and simple oh-my-zsh theme. Shows current directory and 2 directories behind, `git` and `nodejs` status decorations.
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - 基于 af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - 一个简单的 oh-my-zsh 主题.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - 带有 `git` 状态装饰的极简主义 ZSH 主题.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) - oh-my-zsh's node theme, broken out to make it easier to use with other plugin managers.
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - 基于 ys 主题，添加了 NodeJS 版本（来自 NVM 插件）.
* [noon](https://github.com/silky/noon.zsh-theme) - Has light and dark variants, shows `git` information.
* [nord](https://github.com/TyWR/Nord-zsh) - Includes `git` status decorations and displays the active conda environment.
* [normanius](https://github.com/normanius/normanius-zsh-theme) - 源自 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [nothing](https://github.com/eendroroy/nothing) - Lightning fast and really simple because it has almost nothing in it.
* [nox](https://github.com/kbrsh/nox) - Dark theme, displays the current working directory and git status.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme)  - 一个干净、无干扰且以“git”为重点的开发主题. 显示相对于 `git` 根的路径（或 ~ 当在 `git` 存储库之外时）、自上次提交以来的时间、当前 SHA、分支和分支状态.
* [nunorc](https://github.com/nunorc/nunorc.zsh-theme)  - 极简主义主题，适用于深色背景. 包括 `git`、`mercurial` 和 `svn` satus 装饰.
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - A simple theme for prezto and oh-my-zsh.
* [nuts](https://github.com/rafaelsq/nuts.zsh-theme) - Minimalist theme, includes `git` status decorations and time.
* [oblong](https://github.com/Ansimorph/oblong) - Simple `bash`-inspired theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 和 [basher](https://gitlab.com/Spriithy/basher). Includes status decorations to show if user is root, the exit status of last comm和 run, `git` branch 和 its clean/dirty status.
* [odie](https://github.com/masterodie/zsh-theme-odie/)  - 在深色背景上效果很好. 包括 `git` 状态、python virtualenv 和 `vi`-mode 状态装饰.
* [odin](https://github.com/tylerreckart/odin) - Odin is a `git`-flavored ZSH theme.
* [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) - 带有 `git` 装饰的多行主题.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - 对 bash 和 ZSH 的自以为是的提示.
* [oh-my-posh](https://ohmyposh.dev/) - Not ZSH-specific, but very nice and works with ZSH. Allows you to use the same configuration for prompts in all shells.
* [oh-my-via](https://github.com/badouralix/oh-my-via) - ZSH 的主题，主要分叉威盛服务器上使用的历史主题.
* [ohmypc](https://github.com/joselpadronc/OhMyPC) - Works well with dark terminal windows. Includes `git` decorations.
* [om](https://github.com/sirshikher/zsh-om) - 最小主题，适用于深色背景，包括 `git` 状态装饰.
* [omszt](https://github.com/MU001999/omszt) - 带有 `git` 装饰的极简主义主题。
* [omuse](https://github.com/ouuan/omuse-zsh-theme) - Based on Oh-My-ZSH's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) . 具有 `git` 状态、时间、绝对密码、RAM 使用量、最后一个命令使用的时间和最后一个命令退出状态的装饰.
* [owi](https://github.com/owitech/zsh-theme/) - 带有“git”状态装饰的极简主义主题.
* [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) - Includes `git` status and virtualenv information.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - A Minimalistic and Dark ZSH theme.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme)  OZ0NO - 让我们呼吸干净的 ZSH.
* [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) - 一个主题 [powerlevel10k](https://github.com/romkatv/powerlevel10k) prompt that puts an emphasis on simplcity while still getting important information across.
* [pad](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme.
* [page](https://github.com/SLIB53/page-zsh-theme)  - 一个带有 VCS 支持的简单主题. 提示显示当前工作目录的 1 级、分支和一个颜色编码的弯曲粗箭头.
* [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) - Allows display of host information, includes `git` branch decoration.
* [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) - 在提示中使用图标显示详细的 `git` 状态信息.
* [panda](https://github.com/davymai/oh-my-zsh-panda-theme) - Includes `git` and `root` status decorations. Best on a dark background.
* [papercolor](https://github.com/erikschreier/PaperColor-themes)  - ZSH、`vim` 和 `tmux` 的配色方案. 包括 `git` 状态装饰.
* [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion)  - 包括 `git` 状态装饰，以毫秒为单位的命令运行时间. 在 macOS 上需要 coreutils.
* [pastel](https://github.com/iboyperson/pastel) - 一个受启发的 ZSH 主题 [sugar-free](https://github.com/cbrock/sugar-free) . 包括 `git` 装饰.
* [pecodez](https://github.com/pecodez/pecodez-zsh-theme) - Optimized for dark terminals. Has decorators for `snyk` version, `node` version, AWS profile, kubernetes context and `git` status.
* [pentesters](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) - Modified version of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) 渗透测试者的主题，其中包括渗透测试日志记录的日期、时间和 IP 地址.
* [persi](https://github.com/persiliao/persi-zsh-theme) - Includes `git` decorations. Works with both light and dark backgrounds.
* [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) - 本着精神的最小主题 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and Pure Shell themes.
* [phantomk](https://github.com/phantomk/phantomk.zsh-theme) - 丰富多彩的主题，包括 go 版本、node 版本和 `git` 状态.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - 一个干净简单的 ZSH 主题，灵感来自于 [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) 主题.
* [pi](https://github.com/tobyjamesthomas/pi) - 带有 `git` 状态装饰的简约主题.
* [piboy](https://github.com/sflems/piboy-zsh-theme) - A simple and elegant multi-line theme for ZSH. Includes a colourized timestamp, `git` & syntax highlighting, and elevated root theme.
* [plain-ui](https://github.com/purveshpatel511/plain-ui) - 极简主义，但包括 `git` 状态装饰.
* [plain](https://github.com/jimeh/plain.zsh-theme) - A plain and simple theme for ZSH which shows basic `git` information.
* [planet](https://github.com/borb/planet-zsh) - A slimmed down version of [steef](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) from [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) - 简单、简洁的主题.
* [plantyhoe](https://github.com/totoroot/plantyhoe.zsh-theme) - Minimalist theme based on a love of plants and apples. Includes `git` status decorations.
* [platypus](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) - Shows working directory, the return status of the last command, and `git` current branch.
* [polyglot](https://github.com/agkozak/polyglot) - a dynamic prompt for `zsh`, `bash`, `ksh93`, `mksh`, `pdksh`, `dash`, and busybox `ash` that uses basic ASCII symbols (and color, when possible) to show username, whether it is a local or remote `ssh` sesssion, abbreviated path, `git` branch and status, exit status of last command if non-zero, any virtual environment created with `virtualenv`, `venv`, `pipenv`, `poetry`, or `conda`.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM 的基本 oh-my-zsh 自定义主题.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - Programmer's theme with `git` status, ruby version and project path.
* [powerbash](https://github.com/erikschreier/powerbash-zsh) - Works well with dark terminal backgrounds, includes `git` status decorations.
* [powerless](https://github.com/martinrotter/powerless) - 受电力线启发的小而简单的纯 ZSH 提示.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - A fast reimplementation of [powerlevel9k](https://github.com/bhilburn/powerlevel9k)  ZSH 主题. 可以用作 powerlevel9k 的直接替代品，当给定相同的配置选项时，它将生成相同的提示，只是速度更快.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k is a theme for ZSH which uses [Powerline Fonts](https://github.com/powerline/fonts). It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen)， 和 [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 附加组件 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - A two-line version of powerline: one for information, one for input.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme)  - 另一种电力线主题. 可以很好地配置，但至少需要一个支持 256 色的终端，并带有与电力线兼容的终端字体.
* [powerline (syui)](https://github.com/syui/powerline.zsh) - 一个 `git` 感知电力线主题.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
* [powerline-go](https://github.com/justjanne/powerline-go)  - 一个漂亮实用的低延迟提示，用 golang 编写. 包括 `git` 和 `hg` 状态装饰、上次命令运行的退出状态、当前 Python 虚拟环境、是否在 [nix](https://nixos.org/) 外壳，并且易于扩展。
* [powerline-hs](https://github.com/rdnetto/powerline-hs) - 一个 [Powerline](https://github.com/powerline/powerline) clone written in Haskell. It is significantly faster than the original implementation, and makes the shell noticeably more responsive.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - Created in Ruby, uses powerline characters to simulate pills with useful information.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell)  - 漂亮而有用的 Bash、ZSH、Fish 和 tcsh 提示生成器. 包括 `git`、`svn`、`fossil` 和 `hg` 装饰、Python virtualenv 信息和最后一个命令退出状态.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - 一个 [powerline](https://github.com/Lokaltog/vim-powerline) - 类似于 Bash、ZSH 和 Fish 的提示. 显示有关 git/svn/hg/fossil 分支的重要详细信息，并且易于自定义/扩展.
* [powerline-train](https://github.com/sherubthakur/powerline-train) - 电力线变体.
* [powerline](https://github.com/carlcarl/powerline-zsh) - 一个 [Powerline](https://github.com/Lokaltog/vim-powerline)-like prompt, based on [powerline-bash](https://github.com/milkbikis/powerline-bash) . 显示 virtualenv、`git` 状态信息和最后一个命令运行的退出代码.
* [powerzeesh](https://github.com/sevaho/Powerzeesh) - A Powerline based ZSH theme. It aims for simplicity, showing information only when it's relevant, optimized for speed 和 look. Inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) - Sublime Text、Terminal、iTerm 2 和 ZSH 的主题集合.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) - Theme optimized for dark terminal themes.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - oh-my-zsh 的云提示的 Prezto 端口.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda theme (for prezto).
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
* [probe](https://github.com/probe2k/probe_zsh) - Includes `git` status decorations.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - 一个相当重量级的 ZSH 提示，基于流行的同名 `vim` 插件的电力线字体，适用于深色背景.
* [prompt](https://github.com/nathanblair/prompt) - A lightweight prompt consistent across `sh`, `dash`, `ash`, `zsh`, and `pwsh`. Includes `git` status decorations.
* [prompt_j2](https://github.com/malinoskj2/prompt_j2) - 具有动态退出状态指示器，可以动态更改为两行以显示上下文.
* [promptus](https://github.com/willeccles/promptus)  - 简单、简约且可配置的 C 语言 shell 提示程序，可用于使您的提示在任何 shell 上都相同. 包括退出代码和工作目录装饰.
* [pronto](https://github.com/jthat/zsh-pronto) - 带有“git”装饰和时间信息的简单快速的主题.
* [ps1.py](https://github.com/jwodder/ps1.py) - 具有 `git` 状态、截断目录、`chroot` 和 `virtualenv` 提示装饰.
* [pskfyi](https://github.com/pskfyi/zsh-theme) - 基于 [lambda](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#lambda). Themed for ubuntu but easily tweaked.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - Easily customizable, influenced by [spaceship](https://github.com/denysdovhan/spaceship-prompt).
* [pure-agnoster](https://github.com/yourfin/pure-agnoster)  - pure 和 agnoster 的混搭. 具有 `git` 装饰，适用于深色和浅色终端背景.
* [pure](https://github.com/sindresorhus/pure)  - 一个漂亮、最小和快速的 ZSH 提示. 包括 `git` 状态装饰，如果最后一个命令失败，提示变为红色，在远程会话或容器中时的用户名和主机装饰，以及进程运行时的当前文件夹和命令.
* [purify (banminkyoz)](https://github.com/banminkyoz/purify) - 一个简单、快速和酷炫的提示.
* [purify (kyoz)](https://github.com/kyoz/purify) - A clean and vibrant theme, best on dark backgrounds. Includes `git` status decorations.
* [purity](https://github.com/petermbenjamin/purity) - Inspired by robbyrussell theme and the [pure](https://github.com/sindresorhus/pure) 迅速的.
* [purs](https://github.com/xcambar/purs) - A fast [pure](https://github.com/sindresorhus/pure)-inspired prompt written in [Rust](https://www.rust-lang.org/).
* [pustelto](https://github.com/Pustelto/shell_theme) - Colorful theme inspired by the [Spaceship](https://github.com/denysdovhan/spaceship-prompt) theme, includes `git` decorations.
* [qi3ber2](https://github.com/nichus/qi3ber2) - A dark multiline theme. Includes `git`, load average and exit code of last command decorators.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon)  - 针对深色背景进行了优化，包括 `git` 信息. 主题 repo 包括 iTerm 2 和终端颜色设置.
* [quewui](https://github.com/kauefontes/oh-my-quewui) - Simple and clean theme optimized for dark terminal themes. Includes status decorations for the current time, user, directory and `git` status.
* [r3nic1e](https://github.com/r3nic1e/r3nic1e) - [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) variant with battery status, `git/hg` status, time, kubernetes context and namespace, non-zero exit code of last command and date decorations. Requires Powerline font.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - 基于 af-magic 和 posh-git.
* [radium](https://github.com/dimitardimitrov/radium) - Designed for dark terminals, (works best with [Solarized](https://github.com/altercation/solarized) iTerm 2 主题）（prezto）.
* [radius](https://github.com/erikcc02/radius-zsh-theme) - Includes `git` status decorations, includes [desk](https://github.com/jamesob/desk) 支持.
* [rafiki](https://github.com/akabiru/rafiki-zsh) - Adds emojis to your ZSH terminal.
* [ramiel](https://github.com/aknackd/zsh-themes) - 叉子 [node](https://github.com/skuridin/oh-my-zsh-node-theme).
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - 基于 [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) and `robbyrussell` themes.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - 随机表情符号.
* [ranger-zoxide](https://github.com/fdw/ranger-zoxide) - Adds [zoxide](https://github.com/ajeetdsouza/zoxide) 支持 [ranger](https://github.com/ranger/ranger) console file manager.
* [raspberrysh](https://github.com/MaxMalinowski/raspberrysh) - 包括`git`、python、时间、当前主机和路径装饰.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) - 带有“git”状态装饰的简单而多彩的主题.
* [raz](https://github.com/razman786/ohmyzsh-theme-raz) - 最小提示，包括 `git` 状态装饰.
* [rb](https://github.com/rberenguel/rb-zsh-theme) - 基于电力线风格的 ZSH 主题 [Agnoster](https://gist.github.com/agnoster/3712874) ，针对`git`和solarized终端进行了优化. 需要与电力线兼容的字体.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - Optimized for solarized terminal color schemes, includes `git` status decorations.
* [redline](https://github.com/DrissTM/redline.zsh-theme)  - 极简主义主题. 包括 `git` 状态、时间、用户.
* [reggae](https://github.com/nmercado1986/zsh-reggae-theme) - Compresses a lot of information into the prompt with color-coded status decorations.
* [rei](https://github.com/arturoalviar/rei-zsh-theme) - A simple theme with the first character being 零(rei), the number 0. Includes `git` status decorations.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) - 基于 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), 优化为 [solarized](https://github.com/altercation/solarized) 终端主题.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - Prezto ZSH theme based on Sorin, using emojis for tracking GIT context.
* [rho](https://github.com/andrejreznik/rho-zsh-theme) - Minimalist theme.
* [ribbon](https://github.com/tactlessfish/ribbon-prompt)  - 让人想起电力线. 包括 Python `virtualenv` 装饰器.
* [river](https://github.com/revir/river-zsh-config) - 带有 `git` 信息的深色主题.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - 基于来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题和项目 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - Decorates the `robbyrussell` theme with output to indicate a **WIP** commit.
* [robbyrussell-fullpath](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) - 原本 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 在提示中带有完整路径.
* [rocket](https://github.com/Alexandresl/rocket-zsh-theme) - Minimalist theme, includes `git` and `hg` status decoration.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - A dark theme.
* [roundy](https://github.com/nullxception/roundy)  - 快速、可爱和圆润的主题. 包括 `git` 装饰. 需要 nerd 字体和支持 unicode 的终端应用程序.
* [roz](https://github.com/rozNum/roz-zsh-theme) - Minimalist. Includes `git` status decorations, best on a darker background.
* [rs](https://github.com/rogeliosamuel621/rs-zsh-theme) - Includes `git` decorations. Requires unicode capable terminal.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) - Optimized for dark backgrounds.
* [rummik](https://github.com/rummik/zsh-theme)  - @rummik 的主题. 支持 [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), 和 `git` 提示中的状态信息.
* [russtone](https://github.com/russtone/prompt-russtone) - 灵感来自 [pure](https://github.com/sindresorhus/pure) 和 [sorin](https://github.com/sorin-ionescu/prezto). Includes `git` status decorations.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - 色彩丰富的主题，包括 `git` 装饰和当前目录.
* [rzh](https://github.com/patwhatev/rzh) - 带有 git 状态的主题由表情符号指示.
* [s1ck94](https://github.com/zimfw/s1ck94) - Fork of the (first deprecated, now extinct) minimal prompt by S1cK94. Shows whether user is root, background job status, vi-mode, exit status of last command, and `git` status decorations.
* [s7c](https://github.com/Samega7Cattac/s7c.zsh-theme)  - 适用于深色背景. 包括 `git` 状态装饰.
* [samshell](https://github.com/samuelb/samshell) - A minimalist zsh theme with `git`, kubernetes and python virtualenv decorations.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - Includes `git` status decorations, works well on a dark terminal background.
* [saturn](https://github.com/gantoreno/saturn-prompt) - 为热爱空间并希望在终端上拥有一点空间的用户提供柔和简约的提示，具有酷炫的表情符号和高度可定制的提示元素（例如图标、颜色、时间格式等）.
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) - Shows `git` status decorations, user@host information, the exit status of last command, and whether running as root.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - Shows if `vim` is running in the background when using `:sh` command.
* [scythe](https://github.com/kostoskistefan/scythe)  - 让人想起电力线的主题. 包括`git`，最后一个命令退出状态和目录装饰.
* [sdkman](https://github.com/matthieusb/zsh-sdkman) - Add tab completions for [sdkman](https://sdkman.io/).
* [seashell](https://github.com/jottenlips/seasonal-zshthemes) - Minimal theme with sea-inspired emoji decorations. Includes `git` status decorations.
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - 这个主题使用了许多特殊的 unicode 字符来花哨，但是如果没有很好的字体支持，它可能会导致一些问题.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - 受节食者主题启发，使用颜色编码提供信息.
* [senpai](https://github.com/hiroru/senpai-zsh) - Clean prompt theme for Devops. Includes `git` status information, the kubernetes context, AWS profile, GCP project and Azure active cloud.
* [sepshell](https://github.com/sepehr/sepshell) - 基于丢失的旧 taybalt 主题的干净和最小的 ZSH 主题，具有 `git` 平分/合并/变基模式和可配置的提示符号.
* [serious](https://github.com/oliversandli/serious-zsh-theme) - 包括命令退出状态和 `git` 状态装饰.
* [seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - 一个简单的 omz 兼容主题，带有相应的 iTerm 2 配色方案。
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - An evolution of lean prompt which itself is a rewrite of pure.
* [shadow](https://github.com/agentshadow/shadow-zsh-theme) - 包括 `git` 状态、目录、主机名、用户名和时间装饰.
* [shayan](https://github.com/shayanh/shayan-zsh-theme) - 带有 `git` 状态装饰的简单主题.
* [shelby](https://github.com/athul/shelby) - Fast, lightweight and minimal prompt written in pure `golang`. Includes decorations for last command exit status, `git` status and the current working directory.
* [shellder](https://github.com/simnalamburt/shellder) - Minimal theme with git branch display. Requires a Powerline-compatible font.
* [shichi](https://github.com/arturoalviar/shichi-zsh-theme)  - 一个简单的主题，第一个字符是七（shichi/nana），数字 7.原色是红色，带有黄色调. 包括 `git` 状态装饰.
* [shini](https://github.com/bashelled/shini)  - 一个小小的主题，只是大声喊叫. 包括目录、用户名、主机名、时间和 `git` 装饰.
* [shirnschall](https://github.com/shirnschall/shirnschall-zsh-theme) - 包括 `git` 状态和 `user@hostname` 装饰.
* [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) - 分叉自 [sixlive](https://github.com/sixlive/sixlive-zsh-theme) . 有 `git` 装饰.
* [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme. Includes `git` and `hg` status decorations.
* [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) - Includes `git` decorations.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - Simple theme which displays current directory and git information.
* [shtr0m](https://github.com/kyle-pollock/shtr0m) - Includes `git` status decorations.
* [siegerts](https://github.com/siegerts/zsh-theme) - 在正确的提示中包含 `git` 状态装饰.
* [silver](https://github.com/reujab/silver) - A cross-shell customizable powerline-like prompt heavily inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) . 更快的生锈端口 [bronze](https://github.com/reujab/bronze) . 需要 [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) . 非常可配置，包括 `git` 状态装饰.
* [simpalt](https://github.com/m-lima/simpalt) - An information-rich small-footprint theme for ZSH based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [simple (daopengz)](https://github.com/DaopengZ/simple-zsh-theme) - Works well with both light and dark terminal themes. Includes `vcs`, `username` and `path` decorations.
* [simple (pavdmyt)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - Minimalist theme based on [robbyrussel](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 在 iTerm 的窗口标题栏中嵌入 `git` 状态信息，而不是在提示中使用空格。
* [simple (savecoders)](https://github.com/Savecoders/simpleTheme-zsh-theme) - Simple and minimalist theme with `git`, `username` and execution status decorations.
* [simple (tourcoder)](https://github.com/tourcoder/simple.zsh-theme) - 极简提示，包括 `git` 状态装饰.
* [simple (yhiraki)](https://github.com/yhiraki/zsh-simple-prompt) - 最小提示，不需要特殊字体.
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - Powerline-inspired simple theme with `git` decorations.
* [simple-git](https://github.com/BazaJayGee66/simple-git-theme) - Minimalist theme inspired by [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) . 包括 `git` 装饰.
* [simple-yet-beautiful](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme) - Minimalist theme. Includes `git` status and `user@host` prompt decorations.
* [simplezsh](https://github.com/fr0zn/simplezsh) - Minimal theme with `git` info display.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme)  - k-kinzal 的 sinon 主题. 包括 `git` 状态装饰.
* [sit](https://github.com/svensen/sit.zsh-theme) - Minimalist theme with `git`, command exit status and path decorations.
* [sixlive](https://github.com/sixlive/sixlive-zsh-theme) - This theme has a unique directory listing. When inside a `git` project, the directory display is scoped to the current repository root.
* [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9 的 ZSH 主题.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Atom、Prism 和 ZSH 的主题系列灵感来自 He-Man 和宇宙大师的 Skeletor.
* [skill](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - 针对黑暗终端进行了优化，显示 `git` 状态装饰.
* [skull](https://github.com/tahadostifam/skull-zsh) - Includes `git` status, python virtual environment and ruby `rvm` status decorations.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH theme inspired by [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 和 [odin](https://github.com/tylerreckart/odin).
* [slick](https://github.com/nbari/slick) - Inspired by the [pure](https://github.com/sindresorhus/pure), [purs](https://github.com/xcambar/purs) 和 [zsh-efgit-prompt](https://github.com/ericfreese/zsh-efgit-prompt) . 安装时需要`cargo`.
* [slimline](https://github.com/mengelbrecht/slimline)  - 最小、快速和优雅的 ZSH 提示. 在正确的时间显示正确的信息.
* [sm](https://github.com/blyndusk/sm-theme)  **Simplist** 和 **Minimalist** 主题，适用于您的 **favorite** 终端. 包括 `git` 状态装饰.
* [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) - 的变体 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 主题在 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - 带有快乐和悲伤面孔的提示.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme) - A minimalistic ZSH theme inspired by the old-fashioned hobbies. No verbose gimmicks, no emoji, no fidget spinners, and no other visual noise. Has both light and dark modes.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - 日晒电力线变体.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) - Solarized powerline-style theme for ZSH.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) - 对 robbyrussell 的 oh-my-zsh 主题进行颜色修复 [solarized](https://github.com/altercation/solarized) 终端.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) - 带有 `git`、`nvm`、rvm/rbenv/chruby、python、`ssh` 和其他有用状态指示器的主题.
* [spowerline](https://mbauhardt.github.io/spowerline/) - 用 scala 编写，灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), [tmux](https://tmux.github.io) powerline, vim powerline and the vim status plugin.
* [spyrhoo](https://github.com/FajarKim/spyrhoo-zsh-theme) - Includes time, `git` and current directory decorations.
* [squanchy](https://github.com/gabrielecanepa/zsh-custom/tree/master/themes) - Minimalist theme. Includes `git`, `node` and `rbenv` status decorations.
* [ssfprompt](https://github.com/hugoh/zsh-ssfprompt)  - 简单、纤薄、快速. 包括 `ssh`、virtualenv 和 vcs 装饰.
* [staples](https://github.com/dersam/staples) - Based on bureau, displays user@host if connected through SSH.
* [starboy](https://github.com/prdpx7/Starboy) - 一个简单的 ZSH 主题.
* [starship](https://starship.rs/) - 最小，快速，高度可定制.
* [statusline](https://github.com/el1t/statusline) - A responsive ZSH theme that provides informational segments when you need them.
* [steef (danihodovic)](https://github.com/danihodovic/steeef)  - ZSH steeef 主题作为独立存储库. 这个 repo 背后的目的是避免在使用 steeef 主题时依赖 oh-my-zsh.  Antibody 等 ZSH 插件管理器可以使用主题，而无需使用 oh-my-zsh.
* [steef (zimfw)](https://github.com/zimfw/steeef) - A customizable version of [steeef's](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) 主题.
* [stellachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/stellachar.zsh-theme) - 最小，粉彩.
* [sublime](https://github.com/pjmp/sublime) - 带有 `git` 状态装饰的崇高、干净、简约的 ZSH 主题.
* [sugar-free](https://github.com/cbrock/sugar-free) - 基于 [Pure](https://github.com/sindresorhus/pure) 和 [C和y](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/c和y.zsh-theme) themes.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme) - Includes `git` status decorations. Works better on dark terminal backgrounds.
* [sulfurium](https://github.com/Sulfurium/zsh-theme) -sulfiumOS 的官方 ZSH 主题.
* [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) - Similar to [sunrise](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) 但包括活动的 Ruby 版本.
* [superkolo](https://github.com/Minipada/superkolo) - 添加日期和返回状态到 [kolo](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) 主题.
* [susi](https://github.com/carcruz/susi-zsh-iterm) - 包括 `git` 状态装饰和随附的 iTerm2 配色方案.
* [svs](https://github.com/SvS30/svs-theme) - 带有“git”状态和当前路径装饰的清洁和无干扰主题.
* [sy](https://github.com/ttttmr/sy-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), 包括 `git` 状态装饰.
* [t2er](https://github.com/t2er/t2er-zsh-theme) - 带有 `git` 装饰的极简主义主题。
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - Minimal ZSH theme optimized for dark backgrounds.
* [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) - 包括 `git` 状态装饰和 conda/virtualenv 状态.
* [termux](https://github.com/rooted-cyber/Termux-zsh-theme) - Minimalist theme.
* [termuxer](https://github.com/patrick330602/termuxer) - Theme inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and linuxer.
* [the-time-lord](https://github.com/jhwhite/the-time-lord) - 基于的主题 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - 带有 `git` 状态的彩色主题.
* [theta-async](https://github.com/jesec/zsh_theme_theta-async) - Async version of [theta](https://github.com/eendroroy/theta). Includes vcs status information.
* [theta](https://github.com/eendroroy/theta) - Includes `git` and `hg` status decorations. Also has java, python, ruby, node, go and elixir version information.
* [theto](https://github.com/heyvito/theto-zsh-theme)  - 简单的主题. 需求 [Nerd Fonts](https://nerdfonts.com/), includes `vi`-mode status and `git` decorations.
* [thetraveler](https://github.com/bassopenguin/thetraveler) - 受 unraveler 启发，使用符号来显示 `git` 状态.
* [thnikk](https://github.com/thnikk/zsh-theme-thnikk) - 的最小版本 [spaceship](https://github.com/denysdovhan/spaceship-prompt) 主题.
* [thyme (chenhao-ye)](https://github.com/chenhao-ye/thyme) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme)， 和 [bullet-train](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme).
* [thyme (kawamurakazushi)](https://github.com/kawamurakazushi/thyme) - 带有 `git` 状态装饰的简单主题.
* [toledo](https://github.com/mmatongo/toledo) - Quick minimalist theme with `git` status decorations.
* [tonni4](https://github.com/AndreyPuzanov/tonni4-zsh-theme) - 包括时间和 `git` 状态装饰器.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh)  - 包括`git`信息； 最好在深色背景上.
* [tq](https://github.com/kitian616/tq-zsh-theme) - Displays `git` status, time, requires a Powerline font.
* [traffic](https://github.com/fcce/traffic-zsh-theme) - A dark theme for ZSH.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH.
* [trinity](https://github.com/de-luca/Trinity) - 一个简单的主题基于 [geometry](https://github.com/geometry-zsh/geometry) . 包括 `git` 装饰.
* [tron](https://github.com/iDoTron/tron-zsh-theme) - Includes `git` status, working directory, time, user@host and return status of last command decorations.
* [tsotra](https://github.com/nylo-andry/zsh-themes) - 极简主题，包括 `git` 状态装饰、k8s 上下文和 `rvm` 状态.
* [turs](https://github.com/eikendev/turs) - Fast, minimal [Purs](https://github.com/xcambar/purs)-启发提示.
* [tvline](https://github.com/thvitt/tvline) - Derived from the [agnoster](https://gist.github.com/agnoster/3712874) 主题，添加电力线字体增强功能.
* [twilight](https://github.com/Henryws/twilight-prompt) - Minimalist, but includes last command exit status, `git` status and `user@hostname` decorations.
* [type0](https://github.com/MikereDD/type0_zsh-theme) - 灵感来自 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) 通过 yarisgutierrez. 包括 `git` 装饰.
* [typewritten](https://github.com/reobin/typewritten) - Minimal and informative theme that leaves room for what's important. Does asynchronous `git` decoration updates for speed.
* [ubunly](https://github.com/alejandromume/ubunly-zsh-theme)  - 模仿 Kali Linux 控制台. 注意 - 这个主题还重新绑定了很多键并设置了一些主题应该不理会的 ZSH 选项.
* [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) - 模仿默认的 Debian/Ubuntu `bash` 提示符.
* [ubuntu-with-vitamins](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) - 模仿默认的 Ubuntu 提示符，但带有 `git` 装饰.
* [ubuntu](https://github.com/janstuemmel/zsh-ubuntu-theme) - Minimal theme, includes `git` status decorations.
* [ultimate](https://github.com/b4b4r07/ultimate) - 带有 `git` 指示器、vim 模式指示器和缩短路径的极简主义主题.
* [unicorn](https://github.com/juliuscaesar/unicorn) - Inspired by the [Wild Cherry](https://github.com/mashaal/wild-cherry) 主题. 有表情符号`git`状态装饰.
* [unit-1](https://github.com/nerdbude/Unit-1) - Minimalist theme with ITWTB colors.
* [vanan](https://github.com/avano/vanan-zsh-theme) - 带有“git”信息的极简主义主题，适用于黑暗终端.
* [vercel](https://github.com/vercel/zsh-theme) - 带有“git”状态装饰的极简主义主题.
* [vertepommes](https://github.com/TheRojam/vertepommes-theme) - Based on ys. Includes vcs status, username and current directory decorations.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - 从主题/mgutz.zsh-theme 修改.与 a 一起使用时看起来很棒 [Solarized](https://github.com/altercation/solarized) color scheme.
* [vitesse](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) - 灵感来自 VS Code [Vitesse](https://github.com/antfu/vscode-theme-vitesse) theme. Includes `git` status decorations.
* [vulcan](https://github.com/Bruceboy/vulcan-zsh-theme) - Minimal theme reminiscent of the default `bash` theme. Includes `git` decorations.
* [wade](https://github.com/wadehammes/wade.zsh-theme) - Mashup of the popular ZSH themes [Agnoster](https://gist.github.com/agnoster/3712874) 和 [Fishy](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme), with some visual tweaks.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) - 基于0532主题.
* [whale](https://github.com/whalesea520/whale-zsh-theme) - 鲸鱼主题的快速重新实现.
* [whales](https://github.com/lbergelson/zsh_whales_theme) - 包括 `git` 状态、java 版本、最后命令返回状态和目录的装饰器.
* [wild-cherry](https://github.com/mashaal/wild-cherry) - ZSH、iTerm 2、Sublime、Atom 和 Mou 的童话主题主题.
* [wkentaro](https://github.com/wkentaro/wkentaro.zsh-theme) - A simple theme for Python users. Includes virtualenv and `git` status decorators.
* [work-line](https://github.com/afnizarnur/work-line) - 带有漂亮表情符号的主题.
* [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) - 包括`git`状态装饰、工作目录、最后一个命令的退出状态和当前`virtualenv`.
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme)  - 旨在在您需要时向您展示所需信息的主题.  `wynwyn` 从默认主题 `avit` 和优秀 [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xavi](https://github.com/onthedock/xavi.zsh-theme) - Modified version of the [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 带有 `git` 状态和当前目录的表情符号装饰的主题.
* [xlk-simple](https://github.com/xuelingkang/xlk-simple-zsh-theme) - Simple theme with `git` decorations.
* [xm](https://github.com/Shiaoming/xm)  - 黑暗终端的主题. 有 `git` 装饰.
* [xor](https://github.com/xor3n/xor-zsh-theme) - Self described as minimalistic and 'feature-poor', includes `git` decorations.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - 基于 Jreese 主题插件的 oh-my-zsh shell 主题.
* [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme) - Fast, simple 和 streamlined theme. Works best with [tmux](https://github.com/tmux/tmux/wiki) 和 [vim-airline](https://github.com/vim-airline/vim-airline).
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - 显示当前 git 提交的缩短哈希和消息.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme) - Minimal theme with line separated prompts. Based on the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题.
* [yazpt](https://github.com/jakshin/yazpt) - 一个干净、快速、美观的 ZSH 提示主题，精心整合了 Git/Subversion/TFVC 状态信息，与 Oh My Zsh 等流行的插件管理器集成，并且易于定制和扩展.
* [yechen](https://github.com/liyechen/yechen.zsh-theme) - 带有“git”状态装饰的极简主义主题.
* [yeet](https://github.com/jeetelongname/Yeet-theme) - Minimalist prompt with `git` status decorations.
* [yindev](https://github.com/menyinch/yindev-zsh-theme)  - `gndx` 的变体. 包括 `git` 状态和当前目录的装饰.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - Modified from [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) theme and optimized for a dark background.
* [ys (cristiancavalli)](https://github.com/cristiancavalli/ys-zsh-custom-theme) - 干净、简单、兼容和有意义的主题，适用于深色背景.
* [ys (tinyRatP)](https://github.com/tinyRatP/ys) - 变体 [ys](https://gist.github.com/ysmood/6110461).
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - `ys` variant with support for working with batch submission systems for large clusters. Supports Slurm, LSF / IBM Spectrum LSF, and PBS.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - 带有 `git` 状态信息的简单 ZSH 主题.
* [ysr](https://github.com/raykle/ysr-zsh-theme)  - 基于`ys`. 包括 `git` 状态装饰.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - 黑暗优化的 ZSH 主题.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - Includes conda and venv status.
* [yz50](https://github.com/lacanlale/yz50-zsh) - 多彩，基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 和 [crunch](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) themes. Includes `git` status decorations.
* [z4rr3t](https://github.com/inimicus/z4rr3t) - 基于sindresorhus&#39; [pure](https://github.com/sindresorhus/pure) 主题.
* [zcraft](https://github.com/cpea2506/zcraft) - Minimalist theme with decorations for `git` status, last command exit status and the time taken by the last command.
* [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme) 以塞尔达为灵感的主题. 包括 `git` 状态装饰.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - Customized version of oh-my-zsh [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) 随着善变的支持和其他变化.
* [zemoji](https://github.com/therzka/zemoji) - 基于 [wild-cherry](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ https://github.com/mashaal/wild-cherry/tree/master/zsh) . 包括退出状态、`virtualenv`、`nvm`、`rvm` 和 `git` 状态装饰.
* [zero](https://github.com/arlimus/zero.zsh)  - Zero 的主题和插件. 具有浅色和深色终端背景的变体.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - Works best on dark backgrounds, includes `git` status decorations.
* [zerocake](https://github.com/ZeroPoke/ZeroCake.zsh-theme) - 在黑暗的草地上效果更好.
* [zest](https://github.com/hash-bang/zsh-theme-zest)  - ZSH 的功能主题. 被影响 [zsh2000](https://github.com/consolemaverick/zsh2000), [agnoster](https://gist.github.com/agnoster/3712874) 和 [powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) themes.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) - Shows username, `git` status information, machine name, the current working directory and success/fail status of last command.
* [zinc](https://gitlab.com/robobenklein/zinc) - A blazing-fast, pure ZSH, mixed asynchronous powerline prompt that's easily extensible and extremely configurable.
* [zlambda](https://github.com/wdhg/zlambda) - Minimalist, includes `git` decorations without special font requirements.
* [zodiac](https://github.com/adamalsen/zsh-zodiac) - Includes an emoji for the animal corresponding to the current year.
* [zprompts](https://github.com/z-shell/zprompts) - 使用原始“zsh”主题子系统的主题（提示）.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) - Modified version of oh-my-zsh's [maran](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) 主题.
* [zsh1999](https://github.com/DTan13/zsh1999) - Includes network connectivity, battery and `git` status decorations.
* [zsh2000](https://github.com/consolemaverick/zsh2000) - Powerline looking ZSH theme which includes the `rvm` prompt, `git` status and branch, current time, user, hostname, pwd, exit status, whether running as root and background job status.
* [zsh313](https://github.com/amirali313/zsh313-theme) - 带有 `git` 状态装饰的最小主题.
* [zshcomrade](https://github.com/landongn/zshcomrade) - 一个ZSH主题，同志！
* [zshpower](https://github.com/snakypy/zshpower) - Optimized for python developers. Includes `git` and `pyenv` status decorations, username and host. Tries to install other plugins and fonts, so read its instructions before installing.
* [zshred](https://github.com/redxtech/zshred) - Shows current directory, `git` decorations, exit status of last command and time.
* [zwsh](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for ZSH.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) - Similar to [Agnoster](https://github.com/agnoster/agnoster-zsh-theme)，旨在根据上下文披露信息，具有电力线美学.
* [zzshell](https://github.com/thezzisu/zzshell) - Inspired by the default [Oh-My-Zsh](http://ohmyz.sh/) theme. Displays exit code and `git` status decorations. Doesn't require Powerline fonts.

## Fonts

此处列出的一些主题需要与 Powerline 兼容的字体，以下是一些：

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - 一系列字体，包括一些不错的等宽图标.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - 另一种与电力线兼容的字体.
* [Hack](https://sourcefoundry.org/hack/) - 另一种专为源代码设计的兼容电力线的字体.
* [Input Mono](https://store.typenetwork.com/foundry/djr/series/input?family=input-mono)  - 专为代码设计的字体系列. 它提供等宽字体和比例字体，并包括电力线字形.
* [Iosevka](https://github.com/be5invis/Iosevka)  - 编码器的字体，由代码构建. 高度可定制.
* [Monoid](https://larsenwork.com/monoid/) - Monoid 可定制和优化，即使在低分辨率显示器上也能以 15 像素行高的位图锐度进行编码.
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more.
* [Powerline patched font collection](https://github.com/powerline/fonts) - 十几种字体的集合，经过修补，包括电力线字形.
* [Terminus](http://files.ax86.net/terminus-ttf/) - 包含电力线字形的 Terminus 的 TTF 版本.

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start `zsh`. You can also add the plugin to a running ZSH with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1.克隆新插件到`.zsh.local/modules`
2.在`.zshrc`中加载插件模块
3.打开一个新的ZSH终端窗口或标签

### [Oh-My-Zsh](http://ohmyz.sh/)

1.`cd ~/.oh-my-zsh/custom/plugins`
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

Most of these plugins can be installed by adding `zplug "githubuser/reponame"` to your `.zshrc` file.

### [zpm](https://github.com/zpm-zsh/zpm)

Most of these plugins can be installed by adding `zpm load "githubuser/reponame"` to your `.zshrc` file.

## Writing New Plugins

我已经记录了一些关于编写新插件的建议 [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

还有更详细 [Zsh Plugin Standard](https://zdharma-continuum.github.io/Zsh-100-Commits-Club/Zsh-Plugin-Standard.html).

## Other Resources

### ZSH Tools

* [ShellSpec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, ZSH and all POSIX shells.
* [zsh-bench](https://github.com/romkatv/zsh-bench)  - 交互式 ZSH 的基准. 它测量交互式“zsh”的用户可见延迟：输入延迟、命令延迟等
* [zshdb](https://github.com/rocky/zshdb) - ZSH 调试器.
* [zshelldoc](https://github.com/zdharma-continuum/zshelldoc)  - 用于 shell 脚本的 Doxygen. 解析 ZSH 和 Bash 脚本，输出带有函数列表、调用树、导出变量列表等的 Asciidoc 文档.
* [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH.

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - 精选的工具、资源和工作流程技巧列表，打造出色的开发环境
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open source sysadmin resources
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - CLI 爱好者的精选列表.

在以下位置查找其他有用的 awesome-* 列表 [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

- The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) 和 [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) 是不可或缺的.

- [Mastering ZSH](https://github.com/rothgar/mastering-zsh) is a great tutorial that builds on the basics to show you advanced ZSH usage, customizations, and practical examples.
