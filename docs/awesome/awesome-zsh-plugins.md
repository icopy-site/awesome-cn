<div class="github-widget" data-repo="unixorn/awesome-zsh-plugins"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-zsh-plugins

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Status

[![License](https://img.shields.io/github/license/unixorn/awesome-zsh-plugins.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Funixorn%2Fawesome-zsh-plugins%2Fbadge&style=flat)](https://actions-badge.atrox.dev/unixorn/awesome-zsh-plugins/goto)
[![Join the chat at https://gitter.im/unixorn/awesome-zsh-plugins](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/unixorn/awesome-zsh-plugins?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/awesome-zsh-plugins.svg)](https://github.com/unixorn/awesome-zsh-plugins/stargazers)
[![Code Climate](https://codeclimate.com/github/unixorn/awesome-zsh-plugins/badges/gpa.svg)](https://codeclimate.com/github/unixorn/awesome-zsh-plugins)
[![Issue Count](https://codeclimate.com/github/unixorn/awesome-zsh-plugins/badges/issue_count.svg)](https://codeclimate.com/github/unixorn/awesome-zsh-plugins)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/unixorn/awesome-zsh-plugins/main.svg)](https://github.com/unixorn/awesome-zsh-plugins)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/unixorn/awesome-zsh-plugins/)

ZSH 框架、插件、教程和主题的集合，灵感来自各种很棒的列表集合.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*请阅读 [Contributing Guidelines](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Contributing.md) 在贡献之前. *

## Frameworks

这些框架使您可以更轻松地自定义 ZSH 设置.

您可以在以下位置找到各种框架的一些有趣的性能时序比较.

* [zdharma/pm-perf-test](https://github.com/zdharma/pm-perf-test)
* [rossmacarthur/zsh-plugin-manager-benchmark](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark)

### [alf](https://github.com/psyrendust/alf)

 **Alf** 是 ZSH 的超快速和可配置框架； 它以 Prezto 和 Antigen 为模型，同时在幕后使用 Oh-My-Zsh； 并提供标准默认值、别名、函数、自动完成、自动更新和可安装的提示主题和插件.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

 **ansible-role-zsh** 是一个零知识安装的 ansible 角色. 它使用抗原来管理包和 oh-my-zsh. 可以有条件地加载包. 默认情况下，它包括 powerlevel9k 主题、自动建议、语法高亮和 [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) 和 [fzf-marks](https://github.com/urbainvaes/fzf-marks) . 完全可定制.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

 **Ant-zsh** 是一个小巧轻便的 ZSH 配置环境，可满足特殊定制需求. 它包括插件、主题和基本的便捷设置.

### [antibody](https://github.com/getantibody/antibody)

 **Antibody** 是一种用 Golang 编写的更快更简单的抗原. 更多详情请访问 [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

 **antigen-hs** 替代了针对启动 shell 时的低开销而优化的抗原. 它会自动为您克隆插件.

### [antigen](https://github.com/zsh-users/antigen)

 **Antigen** 是一小组函数，可帮助您轻松管理名为 bundles 的 shell (ZSH) 插件. 这个概念与典型的 vim+pathogen 设置中的包几乎相同.  Antigen 之于 ZSH，Vundle 之于 vim.  Antigen 可以加载 oh-my-zsh 主题和插件，并会自动为您克隆它们.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)

 **Ax-ZSH** 是 ZSH 的模块化配置系统. 它提供了合理的默认值，并且可以通过插件进行扩展.

### [dotzsh](https://github.com/dotphiles/dotzsh)

 **Dotzsh** 力求独立于平台和版本. 在旧版本的 ZSH 下运行时，某些功能可能会丢失，但它应该会完全降级，并允许您在不同操作系统的多台机器上使用相同的设置而不会出现问题.

### [fresh](https://github.com/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as Bundler for your dot files.

### [miniplug](https://sr.ht/~yerinalexey/miniplug)

**miniplug** 是 ZSH 的简约插件管理器.

* 重新采购 .zshrc 时没有崩溃或双重插件加载
* 与其他框架不同，Miniplug 不会污染你的 $PATH
* 仅用于管理插件的最低限度

### [mzpm](https://github.com/Insert-Creative-Name-Here/mzpm)

**mzpm** 是 ZSH 的极简插件管理器.

### [oh-my-zsh](https://ohmyz.sh/)

 **oh-my-zsh** 是一个社区驱动的框架，用于管理您的 ZSH 配置. 包括 120 多个可选插件（rails、git、macOS、集线器、capistrano、brew、ant、macports 等），超过 120 个主题为您的早晨增添趣味，以及一个自动更新工具，让您轻松了解最新动态来自社区的更新.

### [PMS](https://github.com/JoshuaEstes/pms)

 PMS 允许您以有助于减少设置时间和提高生产力的方式管理您的外壳. 它支持主题（改变你的 shell 的外观）、插件（为你的 shell 添加功能）和点文件管理.

 PMS 框架还允许您在不同的 shell 中使用相同的框架. 在您的个人笔记本电脑上使用 ZSH，在远程服务器上使用 bash. 想尝尝鱼吗？ 来吧，尝试不同的shell.

### [prezto](https://github.com/sorin-ionescu/prezto)

 **Prezto** 通过合理的默认值、别名、函数、自动完成和提示主题丰富了 ZSH 命令行界面环境. 有一些特定于 prezto 的插件位于 [https://github.com/belak/prezto-contrib](https://github.com/belak/prezto-contrib).

### [pumice](https://github.com/ryutamaki/pumice)

**Pumice** 是 ZSH 的轻量级插件管理器.

### [pz](https://github.com/mattmc3/pz)

 ZSH 的插件管理器不必很复杂也很强大.  PZ 可以聪明的时候不会试图变得聪明.  PZ 是一个功能齐全、快速且易于理解的插件管理器，封装在一个包含大约 200 行干净 ZSH 的单个文件中.

PZ 足以很好地管理您的 ZSH 插件，然后让您摆脱困境.
### [sheldon](https://github.com/rossmacarthur/sheldon)

一个快速、可配置的 shell 插件管理器.

* 可以管理
  * 任何`git` 存储库.
    * 分支/标记/提交支持.
    * 对 GitHub 存储库的额外支持.
    * 对 Gists 的额外支持.
  * 任意远程文件，只需指定URL.
  * 本地插件，只需指定目录路径.
*高度可配置的安装方法使用 [handlebars](http://handlebarsjs.com/) 模板.
* 超快速并行安装.
* 配置文件使用 [TOML](https://github.com/toml-lang/toml) 句法.
* 使用锁定文件来更快地加载插件.

### [Toasty](https://github.com/5paceToast/toasty-zsh)

**Toasty** 是一个 ZSH 框架，旨在促进管理，而不是规定它.

### [tzpm](https://github.com/notusknot/tzpm)

最小的 ZSH 插件管理器. 仍在开发中.

### [uz](https://github.com/maxrodrigo/uz)

ZSH 微型插件管理器.

### [yazt](https://github.com/bashelled/yazt)

 Yazt 是一个简单的 zsh 主题管理器，几乎与所有东西兼容. 您可以在插件中使用提示，混合“n”匹配两个主题，稍加修改，您甚至可以在 bash 中使用它.

### [zapack](https://github.com/aiya000/zsh-zapack)

zapack 是一个基本的快速最小 ZSH 插件加载器.

### [zeesh](https://github.com/zeekay/zeesh)

 **Zeesh** 是一个跨平台的 ZSH 框架. 它类似于，但不兼容， [oh-my-zsh](http://ohmyz.sh/) . 它具有模块化插件架构，易于扩展. 它有一组丰富的默认值，但被设计为尽可能轻量级.

### [zgem](https://github.com/qoomon/zgem)

**Zgem** 是 ZSH 的插件管理器，支持从 git、http 和本地文件加载和更新插件和主题.

### [zgen](https://github.com/tarjoilija/zgen)

 **Zgen** 是受 Antigen 启发的 ZSH 轻量级插件管理器. 目标是在启动 shell 时将开销降至最低，因为没有人喜欢等待. 它目前没有得到积极维护，我建议您使用 [zgenom](https://github.com/jandamm/zgenom) fork 代替，就是这样.

### [zgenom](https://github.com/jandamm/zgenom)

ZSH 的轻量级插件管理器，是一个扩展了辉煌的分支 [zgen](https://github.com/tarjoilija/zgen) 并提供更多功能和错误修正，同时完全向后兼容.

为了在新的终端会话期间保持快速加载，`zgenom` 会生成一个静态的 `init.zsh` 文件，该文件只会获取你的插件并将它们附加到你的 `fpath` 中.

这通过在启动期间不必执行耗时的逻辑（插件检查、更新等）来最大限度地减少启动时间. 不利的一面是，每当您更新 `.zshrc` 中的插件列表时，您都必须使用 `zgenom reset` 手动刷新 init 脚本.

Zgenom 可以加载 [oh-my-zsh](http://ohmyz.sh/)-兼容和 [prezto](https://github.com/sorin-ionescu/prezto)- 兼容的插件和主题，并在您将它们添加到插件列表时自动为您“git”克隆插件.

### [zilsh](https://github.com/zilsh/zilsh)

**zilsh** 是一个 ZSH 配置系统，旨在吸引更多高级用户并遵循 vim-pathogen 的简单方法.

### [zim](https://github.com/zimfw/zimfw)

**Zim** 是一个 ZSH 配置框架，具有极快的速度和模块化扩展.

### [Zinit](https://github.com/zdharma/zinit)

**Zinit** 是一个创新的，可能（因为 Turbo） [fastest](https://github.com/zdharma/pm-perf-test) 插件管理器支持：

 - Turbo 模式 - Zsh 启动速度提高 80%！ 例如：不是 200 毫秒，而是 40 毫秒，
- 完成管理（有选择地禁用和启用完成），
- 片段（↔ 通过 URL 下载的常规文件，例如：脚本）并通过它们 Oh My Zsh 和 Prezto 插件支持（→ 低开销），
- 附件（↔ Zinit 扩展），
- 报告（来自插件加载 - 插件不再是黑匣子），
- 插件卸载（允许例如：动态主题切换），
- `bindkey` 捕获和重新映射，
- [packages](https://github.com/Zsh-Packages),
- 干净的 `fpath`（数组 `$fpath` 不用于添加补全和自动加载功能，因此它保持简洁，不臃肿），
- [services](https://github.com/zservices) ↔ 单实例，后台插件，
- 此外，一般而言：Zsh 插件标准中的所有机制——Zinit 是该标准的参考实现.

奖励：您可以使用 [zinit-console](https://github.com/zinit-zsh/zinit-console) 查看和更改 ZSH 会话的状态（例如：列出和卸载插件）并从磁盘中删除插件和片段.

该项目非常活跃——目前 &gt; 3100 次提交.

### [zit](https://github.com/thiagokokada/zit)

 **zit** 是 ZSH 的插件管理器. 它是最小的，因为它实现了作为插件管理器的最低要求：它允许用户从 Git 存储库（仅限 Git 存储库，它们的名称）安装插件，源插件并更新它们. 它没有实现一些花哨的功能，例如清除已删除的插件、自动编译已安装的插件、oh-my-zsh/prezto/其他 ZSH 框架的别名、构建二进制文件、PATH 操作等.

### [znap](https://github.com/marlonrichert/zsh-snap)

 **:zap:Znap** 是 ZSH 的轻量级插件管理器和 Git 存储库管理器，易于理解. 虽然专门为 ZSH 插件量身定制，Znap 还可以作为管理 Git 存储库的通用实用程序.

Znap

Znap 可以：

 - 立即出现任何提示. 只需一个命令，将启动时间从 ~200ms 减少到 ~40ms.
- 异步编译您的插件和函数.
- 缓存那些昂贵的`eval $(commands)`.
- 并行克隆或拉取多个存储库.
- 无需重新输入即可重新克隆所有存储库.
- 多回购管理
- 自动 `compinit` 和 `bashinit` - 你的 `.zshrc` 中不再需要它们，znap 会根据需要自动执行它们.

### [zoppo](https://github.com/zoppo/zoppo)

 **Zoppo** 是 ZSH 的残缺配置框架. 正如意大利谚语所说：“chi va con lo zoppo, impara a zoppicare”，我们意识到我们走路时带着瘸子，而现在我们自己也会瘸腿.

### [zpacker](https://github.com/happyslowly/zpacker)

**Zpacker** 是一个轻量级的 ZSH 插件和主题管理框架.

### [zpico](https://github.com/thornjad/zpico)

小巧的 ZSH 包管理器. 没有多余的装饰，没有膨胀，只有 2 kB 的 100% ZSH 代码，为您的 ZSH 环境提供完整的包管理.

### [zplug](https://github.com/zplug/zplug)

**:hibiscus: Zplug** 是下一代 ZSH 插件管理器.

- 可以管理一切
  - Zsh 插件/UNIX 命令 [GitHub](https://github.com) 和 [Bitbucket](https://bitbucket.org)
  - 要点文件（[gist.github.com](https://gist.github.com/discover))
  - 外部管理的插件，例如， [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [prezto](https://github.com/sorin-ionescu/prezto) 插件/主题
  - 二进制工件 [GitHub Releases](https://help.github.com/articles/about-releases/)
  - 本地插件
  - 等（你可以添加你 [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- 超快速并行安装/更新
- 支持延迟加载
- 分支/标记/提交支持
- 更新后、加载后挂钩
- 包之间的依赖关系
- 不像 [antigen](https://github.com/zsh-users/antigen), 不需要 ZSH 插件文件 (`*.plugin.zsh`)
- 交互界面（[fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw)， 等等）
- 缓存机制减少 [the startup time](https://github.com/zplug/zplug#vs)

### [zpm](https://github.com/zpm-zsh/zpm)

**zpm** ( ZSH Plugin Manager ) 是一个插件管理器 [ZSH](http://www.zsh.org/) 谁结合了命令式和声明式方法. 第一次运行时，zpm 会做复杂的逻辑并生成缓存，之后将只使用缓存，所以这使得这个框架非常快.

* 最快的插件管理器（真的，第一次运行后，根本不会使用zpm）
* 支持异步加载
* 包之间的依赖
* zpm 在 Linux、macOS、FreeBSD 和 Android 上运行.
* zpm 插件兼容 [oh-my-zsh](http://ohmyz.sh/).

### [zr](https://github.com/jedahan/zr)

**zr** 是一个快速、简单的 ZSH 插件管理器，用 Rust 编写，可以通过 `cargo install zr` 轻松安装.

### [zshing](https://github.com/zakariaGatter/zshing)

**zshing** 是一个类似于 Vundle/Vim 的 ZSH 插件管理器，它允许你...

*在`.zshrc`中跟踪和配置你的插件
* 安装 ZSH 插件
* 更新 ZSH 插件
* 按名称搜索所有可用的 ZSH 插件
* 清理未使用的插件
*在*单个命令中运行上述操作*
* 管理已安装插件的 __Source Plugins__

### [ztanesh](https://github.com/miohtama/ztanesh)

**Ztanesh** 旨在通过 ztanesh 项目提供的配置来提高您的 UNIX 命令行体验和生产力：这些工具将使您的 shell 更强大且更易于使用.

### [ztheme](https://github.com/SkyyySi/ztheme)

ztheme 是 ZSH 的一个小而快速的主题引擎.

### [ztupide](https://github.com/mpostaire/ztupide)

一个简单快速的 ZSH 插件管理器. 它使用 zcompile 和异步加载来加快您的 shell 启动时间.

### [zulu](https://github.com/zulu-zsh/zulu)

**Zulu** 是 ZSH 5+ 的环境管理器，旨在让您无需编写任何代码即可轻松管理您的 shell.

* 无需编辑文件即可轻松管理您的 shell 环境.
* 创建别名、函数和环境变量，并在下次 shell 启动时提供给您.
* 使用简单的命令从`$path`、`$fpath` 和`$cdpath` 添加和删除目录.
* 轻松安装软件包、插件和主题，并立即提供给您.

## Setups

本节用于完整设置 dropins - 它们不是框架，但它们也不是简单的插件/主题.

### zgenom

* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - 使用 ZSH 的简单快速入门 [zgenom](https://github.com/jandamm/zgenom) . 这包括精选的插件集合，自动配置 ZSH 以使用 [zgenom](https://github.com/jandamm/zgenom) 加载它们并定期自动更新自身、插件和快速入门工具包本身.

### zinit

* [ZPWR](https://github.com/MenkeTechnologies/zpwr) - 一个极其强大的自定义终端环境建立在 [Zinit](https://github.com/zdharma/zinit) 以获得最大速度. 一个完整的终端配置框架，包括 zsh、tmux、fzf、vim 和 spacemacs 配置. 这包括：

- 11.5k+ 选项卡完成
- 1.9k+ 别名
- 330 多个 git 别名
- 350 多个 zpwr 子命令
- 2.1k 功能
- 150 多个 zpwr 环境变量
- 170 多个 perl、python、bash、zsh 脚本
- 2.8k 行 README.md
- 46k + LOC
- 1 行安装

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - 使用组合的教程 [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io)， 和 [Tmuxinator](https://github.com/tmuxinator/tmuxinator) 打造极其高效的开发人员工作流程.
* [Arch Linux's ZSH introduction](https://wiki.archlinux.org/index.php/zsh) - 实际上不是 Arch 或 Linux 特定的.
* [GH](https://github.com/gustavohellwig/gh-zsh)  - 在基于 debian/Ubuntu 的 linux 上设置 ZSH. 安装 [Powerlevel10k](https://github.com/romkatv/powerlevel10k), [zsh-completions](https://github.com/zsh-users/zsh-completions), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), [fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting/)， 和更多.
* [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - 关于如何安装和配置 ZSH shell 的初学者友好教程.
* [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos 介绍 ZSH 和 oh-my-zsh 的视频.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) 涵盖了 ZSH 具有而 Bash 没有的一些功能，并使用了 oh-my-zsh.
* [rs-example](https://github.com/al-jshen/zshplug-rs-example) - 一个示例插件，展示了 Rust 程序如何监听和处理来自 ZSH 的命令.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - 幻灯片演示.
* [xVanjaZ](https://github.com/xVanjaZ/xVanjaZ-ZSH-Theme) - 为 oh-my-zsh 初学者编写了一个快速设置文档，展示了如何使用 [spaceship](https://github.com/denysdovhan/spaceship-prompt.git) 提示、提示处的语法高亮显示、自动建议和自定义 iTerm 2 主题.
* [ZSH for Humans](https://github.com/romkatv/zsh4humans)  - ZSH 的交钥匙配置，旨在开箱即用. 它将一组精选的 ZSH 插件组合成一个连贯的整体，感觉就像一个成品，而不是一个 DIY 入门套件.
* [ZSH Pony](https://github.com/mika/zsh-pony) - 涵盖在没有框架的情况下自定义 ZSH.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - Christian Schneider 的详尽 ZSH 技巧列表.

### Antigen

* [belak/zsh-utils](https://github.com/belak/zsh-utils) - 设计为低摩擦和低复杂性的最小 ZSH 插件集.
* [Frictionless zsh And oh-my-zsh Management With Antigen](https://thorsten-hans.com/frictionless-zsh-and-oh-my-zsh-management-with-antigen) - 指导您完成设置过程并演示如何使用 Antigen 管理插件和主题以定制您的 ZSH 体验.
* [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean 关于从 oh-my-zsh 切换到抗原的文章.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis 对 Antigen 的介绍.

### Oh-My-Zsh

* [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - Dien Bui 的 oh-my-zsh 初学者指南
* [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - Karl Hadwen 在 macOS 上使用 Oh My Zsh 的初学者指南
* [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders Ubuntu 安装指南
* [ZSH Gem 24](https://www.refining-linux.org/archives/59-ZSH-Gem-24-ZSH-frameworks.html)  - 2011 ZSH Advent 日历的一部分. 涵盖 oh-my-zsh 和 zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss 关于使用 Prezto 的博客文章， [Tmux](https://tmux.github.io) &amp; Tmuxinator.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert 关于迁移到 Prezto 的博客文章.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) - 功能丰富、闪电般快速的外壳设置，由 [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto)， 和 [Zgen](https://github.com/tarjoilija/zgen).

### Zinit (née zplugin)

* [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh)  - :crystal_ball：很棒的、可定制的 Zsh 入门套件 :stars::stars:. 包括电力线、fzf 集成、某些终端中的天气和图像查看.
* [zinit-configs](https://github.com/zdharma/zinit-configs) - 真实世界的配置文件（基本上是`.zshrc` 文件的集合）持有Zinit 调用.

### ZSH on Windows

* [superconsole](https://github.com/alexchmykhalo/superconsole) - 仅限 Windows.

  * ConEmu/zsh 开箱即用配置为在 ConEmu 重启后恢复以前打开的选项卡和 shell 工作目录
  * 开始新的 SuperConsole 会话时，在干净环境和继承环境之间进行选择
  *自定义彩色方案，各种命令的彩色输出
  * 包含 MSYS2，预装了 `zsh` 和必要的软件，使用 zsh-grml-config
  * 使用 Antigen 进行 ZSH 主题和配置管理
  * 启用 ZSH 插件数量以激活完成、突出显示和历史记录，以实现最舒适的使用
  * 为 MSYS2 环境配置了具有适当 `git` 和 git lfs 支持的 Git-for-Windows 存储库，已经安装了 `git` 客户端.
  * `git` 的 `ssh-agent` 开箱即用，将您的密钥添加到 `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` 目录
  * 由于 agkozak-zsh-prompt，非阻塞 ZSH 提示状态更新
  * 为 MSYS2 command-not-found 处理程序定制，建议安装什么包
  * Sets up `nano` as main editor, enables `nano` syntax highlighting
  * 自定义助手脚本添加到`ConEmu/msys64/3rdparty`

## Plugins

* [1999](https://github.com/DTan13/zsh1999)  - 电力线风格的主题. 包括 `git` 状态装饰、网络和电池状态.
* [256color](https://github.com/chrissicool/zsh-256color)  - 使用 256 种颜色增强终端环境. 它查看所选的“TERM”环境变量，并查看是否有相应的 ncurses 的 terminfo 有 256 种颜色可用. 结果是多色终端（如果可用）.
* [abbr (olets)](https://github.com/olets/zsh-abbr) - 管理自动扩展的缩写，当你点击空间时，这些缩写会在鱼壳的启发下展开.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - 从一些 oh-my-fish 主题中添加了 `theme_title_use_abbreviated_pa​​th` 参数的功能.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - 提供类似于`vim` 的缩写扩展的功能.
* [accurev](https://github.com/dalefukami/accurev-zsh) - ZSH 插件 [accurev](https://www.microfocus.com/en-us/products/accurev/overview).
* [actiona](https://github.com/matthieusb/act) - 让通话更轻松 [actiona](https://github.com/Jmgr/actiona) 命令行中的脚本. 包括选项卡完成.
* [alehouse](https://github.com/sticklerm3/alehouse) - 包含短别名 [brew](https://brew.sh) 命令，灵感来自 [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin).
* [alias-tips](https://github.com/djui/alias-tips) - 一个 oh-my-zsh 插件，可帮助记住您定义过的那些别名.
* [allergen](https://github.com/stanislas/allergen) - 一组与 Antigen 一起使用的自定义 ZSH 插件.
* [almostontop](https://github.com/Valiev/almostontop)  - 每次在 shell 中执行新命令之前清除以前的命令输出. 灵感来自 [alwaysontop](https://github.com/swirepe/alwaysontop) `bash` 的插件.
* [alt-and-select](https://github.com/raisty/alt-and-select)  - 将 alt-c（复制）、alt-v（粘贴）、alt-x（剪切）键盘快捷键绑定到命令：copy-region-as-kill、yank、kill-region. 将执行命令重新映射到 Alt-Shift-X.
* [ansible](https://github.com/sparsick/ansible-zsh) - 一个插件 [Ansible](https://www.ansible.com/).
* [ansiweather](https://github.com/fcambus/ansiweather) - 终端中的天气，带有 ANSI 颜色和 Unicode 符号.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH 脚本来帮助`git` 变基.
* [anyframe](https://github.com/mollifier/anyframe) - ZSH 的 peco/percol/fzf 包装插件.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - 添加用于管理 Apache2 的别名和函数.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - 在 MacBook Pro 中添加了触控栏支持 [iTerm 2](https://iterm2.com).
* [appup](https://github.com/Cloudstek/zsh-plugin-appup)  - 在当前目录（例如您的应用程序）中检测到 `docker-compose.yml` 或 `Vagrantfile` 时，添加 `start`、`stop`、`up` 和 `down` 命令. 只需运行`up`并开始编码！
* [arc](https://github.com/anton-rudeshko/zsh-arc) - 为 Yandex 版本控制系统添加别名.
* [arduino](https://github.com/raghur/zsh-arduino)  - 添加脚本以从命令行构建、上传和监控 arduino 草图. 需要 [`jq`](https://stedolan.github.io/jq/).
* [artisan](https://github.com/jessarcher/zsh-artisan) - 用于 ZSH 的 Laravel `artisan` 插件，可帮助您从项目树中的任何位置运行 `artisan`，并带有选项卡完成功能！
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - AsciiDoctor 的插件.
* [asdf](https://github.com/kiurchv/asdf.plugin.zsh) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf)，可扩展的版本管理器，支持 Ruby、Node.js、Elixir、Erlang 等.
* [asdf-direnv](https://github.com/redxtech/zsh-asdf-direnv) - 集成和完成 [asdf](https://github.com/asdf-vm/asdf) 和 [direnv](https://github.com/asdf-community/asdf-direnv).
* [assume-role](https://github.com/weizard/assume-role)  - ZSH 插件可让您轻松承担 AWS IAM 角色. 包括完成.
* [async](https://github.com/mafredri/zsh-async)  - 无需任何外部工具即可在 ZSH 中运行异步任务的库. 允许您运行多个异步作业、强制执行唯一作业（同一作业的多个实例将不会运行）、刷新所有当前正在运行的作业并创建多个工作器（每个都有自己的作业）.
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - 基于 [Sublime](https://github.com/valentinocossar/sublime) 插件，让你启动一个文件或文件夹 [Atom](https://atom.io) 从 [iTerm 2](https://iterm2.com).
* [atuin](https://github.com/ellie/atuin)  - 用 SQLite 数据库替换您现有的 shell 历史记录，并为您的命令记录额外的上下文. 此外，它还通过 Atuin 服务器在机器之间提供可选和完全加密的历史同步.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) - 自动列出带有 `colorls` 的目录.
* [auto-fortune-cowsay](https://github.com/babasbot/auto-fortune-cowsay-zsh) - 打印出一头牛的 ASCII 图片，在每次 zsh 开始时说随机警句.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh)  - 自动完整的单词和列表选择. 最初是 y.fujii 的 incr-0.2.zsh<y-fujii at mimosa-pudica.net>  .
* [auto-ls](https://github.com/desyncr/auto-ls) - cding 到新目录时自动`ls`.
* [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) - 当长时间运行的任务完成时自动发出通知.
* [auto-nvm](https://github.com/manlao/zsh-auto-nvm) - 自动切换到给定目录中指定的节点版本.
* [autocomplete](https://github.com/marlonrichert/zsh-autocomplete) - 在您键入时自动列出补全，并提供用于选择和插入它们的直观键绑定.
* [autodotenv](https://github.com/nocttuam/autodotenv) - 当你将 `cd` 放入包含 `.env` 文件的目录时，会提示你加载变量.
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) - 扩展版 [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) 插入.
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) - 如果一个目录包含一个 `.env` 文件，它会在你 `cd` 进入时自动执行.
* [autojump](https://github.com/wting/autojump)  - 一个学习的`cd` 命令 - 从命令行轻松导航目录. 安装 autojump-zsh 以获得最佳效果.
* [autopair](https://github.com/hlissner/zsh-autopair)  - 用于自动关闭、删除和跳过匹配分隔符的 ZSH 插件. 仅在 ZSH 5.0.2 或更高版本上测试.
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)- 类似于 ZSH 的快速/不显眼的自动建议.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv)  - ZSH 插件在遍历目录时自动切换 python virtualenvs 和 pipenvs. 自动检测 pipenv 和诗歌项目.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin)  - Antigen 不会像 oh-my-zsh 那样进行自动更新. 该插件为抗原添加了自动更新，包括抗原和配置中加载的包.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - oh-my-zsh 不会自动更新非核心插件，这会将插件自动更新添加到 oh-my-zsh.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - 基于 sweharris 的 AWS CLI MFA 插件 [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa) . 支持在配置文件中指定 mfa_device.
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - AWS MFA 插件.
* [aws-plugin](https://github.com/pookey/zsh-aws-plugin)  - 为 `aws` 命令添加辅助函数. 包括 mfa 和承担角色助手.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - 使用 `aws-upload` 提高您的工作效率.
* [aws-vault (blimmer)](https://github.com/blimmer/zsh-aws-vault) - 插件 [aws-vault](https://github.com/99designs/aws-vault) . 包括选项卡完成.
* [aws-vault (reegnz)](https://github.com/reegnz/aws-vault-zsh-plugin) - 更容易使用 [aws-vault](https://github.com/99designs/aws-vault) 在你的环境中.
* [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) - 为版本 2 提供补全支持 [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) 以及一些用于管理 AWS 配置文件并将其显示在提示中的实用程序.
* [awsume](https://github.com/Sordie/AWSume) - 可以显示当前的插件 [awsume](https://github.com/trek10inc/awsume) 轮廓.
* [azcli](https://github.com/dmakeienko/azcli) - 使用 azure cli 工具的助手.
* [background](https://github.com/zpm-zsh/background) - 在后台执行功能的 ZSH 插件.
* [base16](https://github.com/chriskempson/base16-shell)  - 添加脚本以允许您更改 shell 的默认 ANSI 颜色，但最重要的是，更改 shell 256 颜色空间中的 17 到 21 种颜色（如果您的终端支持）. 这个脚本可以让你的外壳保持原来的明亮颜色（例如，亮绿色仍然是绿色等等），同时为应用程序提供额外的 base16 颜色，例如 [Vim](https://www.vim.org).
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts)  - 在您的外壳中打印随机棒球相关的“有趣的事实”. 取决于正在安装的 `fortune` 和 `cowsay`.
* [basex](https://github.com/dirkk/zsh-basex) - 增加了几个 [BaseX](http://basex.org/) 简化使用的别名.
* [bash-quote](https://github.com/jtprog/bash-quote) - 从 Bash.im 获取随机报价.
* [bash](https://github.com/chrissicool/zsh-bash)  - 使 ZSH 更加兼容 Bash. 它重新定义了 source 命令以使其更像`bash`. 它还启用了`bash` 补全.
* [battery_state](https://github.com/Jactry/zsh_battery_state) - 在右侧提示中显示电池状态.
* [bd](https://github.com/Tarrasch/zsh-bd) - 跳回特定目录，无需执行 `cd ../../..`.
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) - 为法语重新映射 ZSH `vi` 模式 [bépo keyboard](http://bepo.fr/wiki/Accueil).
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) - 为 `brew` 添加更多命令别名
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - 添加辅助脚本以允许您创建 bitbucket PR 或在当前分支中打开目录.
* [blackbox](https://github.com/StackExchange/blackbox) - [Stack Exchange](https://stackexchange.com)的工具包，用于将密钥/凭据安全地存储在“git”存储库中.
* [bofh](https://github.com/fundor333/bofh) - 添加显示随机财富的功能.
* [bol](https://github.com/ikhurramraza/bol) - 打开终端窗口时打印随机报价.
* [boss-docker](https://github.com/bossjones/boss-docker-zsh-plugin) - 在 OSX 上管理 `docker`.
* [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) - 为 `git` 添加了一些方便的别名.
* [branch-manager](https://github.com/elstgav/branch-manager) - 用于管理`git` 分支的插件.
* [brew (rhuang2014)](https://github.com/rhuang2014/brew) - 独立插件 [Homebrew](https://brew.sh/) 包管理器.
* [brew (wolffaxn)](https://github.com/wolffaxn/brew-zsh-plugin) - 独立插件 [Homebrew](https://brew.sh/) 包管理器.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - 一个插件，可让您从命令行在浏览器中打开任何提交.
* [bruse](https://github.com/aubreypwd/zsh-plugin-bruse) - 使“酿造链接”不同版本的软件包变得容易.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - 在命令行中切换 optirun 的插件.
* [c](https://github.com/sebastiangraz/c) - 添加了一些 `git` 快捷方式.
* [calc](https://github.com/arzzen/calc.plugin.zsh) - ZSH 的计算器.
* [calibre-zaw-source](https://github.com/junkblocker/calibre-zaw-source) - [Calibre - E-book management](https://calibre-ebook.com/) 来源 [zaw](https://github.com/zsh-users/zaw)
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - 添加 [Can I Use...](https://caniuse.com) 支持ZSH.
* [careful_rm](https://github.com/MikeDacre/careful_rm) - `rm` 的包装器，添加垃圾/回收和有用的警告.
* [case](https://github.com/rtuin/zsh-case) - 一个 ZSH 插件，添加了两个别名 `tolower` 和 `toupper` 来切换输出大小写.
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - 一个 ZSH 插件到 `cd` 到 `git` 存储库根目录.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) - 当`cd` 进入指定目录时显示提醒.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - 一个 ZSH 插件，将 `cd` 放到当前存储库检出的根目录中.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - 当你不小心`cd` 到服务器时，`ssh` 到服务器.
* [cdbk](https://github.com/MikeDacre/cdbk) - 一个 ZSH 插件，允许轻松创建命名目录 - 您想要的任何目录的快捷方式.
* [cdc](https://github.com/evanthegrayt/cdc)  - 更容易将目录更改为用户定义的目录列表的子目录. 包括制表符补全、会话历史和 `pushd`、`popd` 和 `dirs` 等价物.
* [cdr](https://github.com/willghatch/zsh-cdr) - 为 ZSH 轻松设置 cdr.
* [change-case](https://github.com/mtxr/zsh-change-case)  - 用于在命令行中快速切换大小写的插件.  ：太阳镜：
* [cheatsheet](https://github.com/0b10/cheatsheet) - 可轻松查看、创建和编辑备忘单的插件.
* [check-deps](https://github.com/zpm-zsh/check-deps)  - ZSH 插件的助手，允许他们展示如何安装任何缺少的依赖项. 适用于 Debian（以及 Ubuntu 等衍生产品）、Arch 及其衍生产品、Nodejs 和 ZSH 插件（如果您使用的是 [zpm](https://github.com/zpm-zsh/zpm) 框架.
* [chgo](https://github.com/sbfaulkner/chgo-plugin-zsh) - 修改了 chruby 的克隆，以便在多个 Go 版本之间轻松切换.
* [clean-project](https://github.com/wwilsman/zsh-clean-project)  - 从项目中删除文件（默认情况下自动）. 用于防止 `.DS_Store` 和 `Thumbs.db` 文件弄乱你的目录.
* [clipboard](https://github.com/zpm-zsh/clipboard)  - 增加跨平台访问系统剪贴板的助手功能. 适用于 macOS、X11（和 Wayland）和 Cygwin.
* [cmd-architect](https://github.com/psprint/zsh-cmd-architect) - 根据历史记录和提示构建命令，移动、删除、添加命令段和使用多词查询搜索历史记录.
* [cmd-status](https://github.com/BlaineEXE/zsh-cmd-status) - 报告命令的状态，包括返回代码和持续时间.
* [cmdtime](https://github.com/tom-auger/cmdtime) - 显示从分叉到终端的命令的持续时间 [timer](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) 插入.
* [code-review](https://github.com/xorkevin/code-review-zsh) - 在`git merge-base target_branch base_branch`和`target_branch`上启动`git difftool`.
* [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - 计算按键次数并将统计信息记录到 [Code::Stats](https://codestats.net/).
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - 分叉自 [ohmyzsh/ohmyzsh/plugins/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh) . 着色`man` 输出.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - 为“手册”页着色.
* [colorize](https://github.com/zpm-zsh/colorize) - 为各种程序的输出着色.
* [colorls](https://github.com/Kallahan23/zsh-colorls) - 为一些 colorls 函数定义了一些有用的快捷方式.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors)  - 可以更轻松地从 CLI 为文本着色.  `red foo` 正常工作.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - ZSH 的增强颜色.
* [command-execution-timer](https://github.com/olets/command-execution-timer) - 显示交互式 shell 命令执行所需的时间.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) - oh-my-zsh command-not-found 插件的镜像，因此您不必包含所有 oh-my-zsh.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - 记录复杂的命令并对其进行评论.
* [command-time](https://github.com/popstas/zsh-command-time) - 在 ZSH 中显示长命令的执行时间和 [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Similar to `REPORTTIME` builtin, but only outputs when user + system time >= `REPORTTIME`.
* [compe](https://github.com/tamago324/compe-zsh) - 添加完成 [nvim-compe](https://github.com/hrsh7th/nvim-compe).
* [completion-generator](https://github.com/RobSis/zsh-completion-generator)  - 此插件尝试从程序的帮助文本中读取选项列表并自动生成完成功能. 请注意，这不会自动执行，您必须显式调用生成器来创建完成脚本.
* [copy-pasta](https://github.com/ChrisPenner/copy-pasta) - 像在 GUI 中一样在终端中复制和粘贴文件.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - 一个 ZSH 插件，用于通过 `ssh` 将你的 shell 配置复制到另一台机器上.
* [crash](https://github.com/molovo/crash) - 为 ZSH 添加适当的错误处理、异常和 try/catch.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - 用于 Wordpress 的 Crayon 插件的 ZSH 语法突出显示.
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - 添加一个 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 以当前比特币价格细分.
* [crystal](https://github.com/veelenga/crystal-zsh) - 一个插件 [Crystal](https://github.com/crystal-lang/crystal).
* [czhttpd](https://github.com/jsks/czhttpd) - 一个用 99.9% 纯 ZSH 编写的简单 http 服务器.
* [declare-zsh](https://github.com/zdharma/declare-zsh) - `zshrc` 中 Zinit 命令的命令行解析器.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - 收集有用和有趣的命令以改善工作流程和生活质量.
* [deer](https://github.com/Vifon/deer) - ZSH 的文件导航器深受启发 [ranger](https://ranger.github.io/).
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools)  - 用于安装 Chromium depot_tools 的简单 oh-my-zsh 插件. 安装这个插件会自动把所有的 Chromium depot_tools 放在你的路径中.
* [dev](https://github.com/sbfaulkner/dev-plugin-zsh) - 提供轻量级版本 [Shopify's internal dev tool](https://devproductivity.io/dev-shopifys-all-purpose-development-tool/index.html)
* [diff-so-fancy](https://github.com/zdharma/zsh-diff-so-fancy) - 简化将“diff-so-fancy”项目安装到您的用户帐户的过程.
* [diractions](https://github.com/AdrieanKhisbe/diractions) - 允许您将简短的逻辑/助记符名称映射到目录以快速访问它们，或在其中执行操作.
* [dircolors-solarized (joel-porquet)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors 插件，提供深色或浅色终端背景选项.
* [dircolors-solarized (pinelibg)](https://github.com/pinelibg/dircolors-solarized-zsh) - 启用 [Solarized Color Theme for GNU ls](https://github.com/seebi/dircolors-solarized).
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - 循环遍历目录堆栈.
* [directory-history](https://github.com/tymm/zsh-directory-history) - ZSH 的每个目录历史记录，它以目录敏感的方式实现向前/向后导航以及子字符串搜索.
* [direnv](https://github.com/ptavares/zsh-direnv) - 用于安装和加载的插件 [direnv](https://github.com/direnv/direnv.git) . 灵感来自 [zsh-pyenv](https://github.com/mattberther/zsh-pyenv).
* [dirrc](https://github.com/gmatheu/shell-plugins) - 当存在于你`cd` 进入的目录中时执行`.dirc`.
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - 用于在一行上显示目录堆栈信息的插件.
* [doas](https://github.com/anatolykopyl/doas-zsh-plugin) - 按两次 `esc` 可以轻松地使用 `doas` 为当前或以前的命令添加前缀.
* [docker-aliases](https://github.com/webyneter/docker-aliases) 日常使用的 Docker 别名.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) 在您的提示中显示 docker 容器状态.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - docker helper 脚本的集合.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) - ZSH 的 docker-machine 插件.
* [docker-run](https://github.com/rawkode/zsh-docker-run) - 返回“自然地”运行您的命令，我们将处理容器.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - 狗化插件.
* [dotbare](https://github.com/kazhala/dotbare) - 借助 `fzf` 进行交互式点文件管理.
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - 使用 `git` 使您的点文件在多台机器上保持同步.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - 当你进入一个目录时，自动切换到一个名为 .pyvenv 的目录中的 python 虚拟环境（你之前用 virtualenv 程序创建的）.
* [dropbox](https://github.com/zpm-zsh/dropbox) - ZSH 的 dropbox 插件，提供 `dropbox-cli` 和 `dropbox-uploader` 命令.
* [dune-quotes](https://github.com/brokendisk/dune-quotes) - 随机沙丘报价生成器插件.
* [duration](https://github.com/rtakasuke/zsh-duration) - 如果超过用户可设置的运行时间，则显示命令持续时间.
* [dwim](https://github.com/oknowton/zsh-dwim)  - 尝试预测您接下来要做什么. 它提供了一个键绑定 (control-u)，它将用您接下来要运行的命令替换当前（或上一个）命令行.
* [easy-motion](https://github.com/IngoHeimbach/zsh-easy-motion) - 一个港口 [vim-easymotion](https://github.com/easymotion/vim-easymotion) 对于 ZSH.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - 列出 EC2 实例并通过 `ssh` 轻松登录实例.
* [editing-workbench](https://github.com/psprint/zsh-editing-workbench) - 添加理智、复杂的命令行编辑（例如增量历史_word_ 完成）.
* [edward cli](https://github.com/matthieusb/zsh-edward) - 添加智能完成和别名 [edward CLI micro-service launcher](https://github.com/yext/edward).
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - 为 Elixir、IEX、Mix、Kiex 和 Phoenix 添加快捷方式.
* [emacs (cowboyd)](https://github.com/cowboyd/zsh-emacs)  - 将 Emacs 设为 CLI 操作的默认值，例如编辑 git commit 消息； 设置方便的别名.
* [emacs (flinner)](https://github.com/Flinner/zsh-emacs) - 使用 Emacs 守护进程功能，允许用户快速打开帧，无论它们是通过 ssh 连接在终端中打开的，还是在同一主机上打开的 X 帧.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: 命令行上的表情符号完成.
* [emoji-fzf](https://github.com/pschmitt/emoji-fzf.zsh) - 优秀的可配置 ZSH 插件 [emoji-fzf](https://github.com/noahp/emoji-fzf) . 它深受启发 [emoji-cli](https://github.com/b4b4r07/emoji-cli).
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) - 在方便的变量中向您的环境添加大量 ascii 艺术表情符号.
* [enhancd](https://github.com/b4b4r07/enhancd) - 一个简单的工具，通过记住用户访问过的所有目录并将其用于路径名解析来提供增强的 `cd` 命令.
* [envrc](https://github.com/fabiogibson/envrc-zsh-plugin) - 如果在目录中找到`.envrc` 文件，则自动加载和卸载环境变量.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - 双击“`”时快速插入转义的反引号.
* [evalcache](https://github.com/mroth/evalcache) - 缓存二进制初始化命令的输出，以帮助降低 shell 启动时间.
* [evil-registers](https://github.com/zsh-vi-more/evil-registers) - 扩展 ZLE vi 命令以远程访问 vim 和 nvim 编辑器的命名寄存器，以及系统选择和剪贴板.
* [exa (DarrinTisdale)](https://github.com/DarrinTisdale/zsh-aliases-exa) - 启用多个别名扩展 [exa](https://the.exa.website)，`ls` 的现代替代品.
* [exa (hermitmaster)](https://github.com/hermitmaster/zsh-exa-plugin) - 添加一些别名 [exa](https://the.exa.website)，`ls` 的现代替代品.
* [exa (mohamedelashri)](https://github.com/MohamedElashri/exa-zsh) - 添加别名 [exa](https://the.exa.website), ls 的现代替代品.
* [exa (ptavares)](https://github.com/ptavares/zsh-exa) - 安装和加载 [exa](https://github.com/ogham/exa.git).
* [exa (ritchies)](https://github.com/RitchieS/zsh-exa/) - 添加别名以使用 [exa](https://github.com/ogham/exa.git) 更轻松.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - 一个插件 [exercism.io](http://exercism.io/).
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - 用空格扩展特定别名.
* [expand](https://github.com/MenkeTechnologies/zsh-expand) - 使用空格键扩展常规别名、全局别名、不正确的拼写和短语、全局、历史扩展和 $parameters.
* [explain-shell](https://github.com/gmatheu/shell-plugins) - 打开命令 [explainshell.com](https://explainshell.com).
* [extend-history](https://github.com/xav-b/zsh-extend-history) - 通过为历史记录中的每个命令添加退出代码来扩展命令历史记录.
* [f-shortcuts](https://github.com/zpm-zsh/f-shortcuts) - 使用 F1 到 F12 键制作快捷工具栏.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - 中版本的破译版本 [oh-my-zsh](http://ohmyz.sh/) 因此其他框架的用户不必导入所有 oh-my-zsh.
* [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips)  - 帮助记住您定义和忘记的别名. 移植自 [djui/alias-tips](https://github.com/djui/alias-tips).
* [fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting) - 优化和改进了`zsh-users/zsh-syntax-highlighting`——更快的响应时间，可切换的高亮主题.
* [fav](https://github.com/ddnexus/fav) - ZSH/[fzf](https://github.com/junegunn/fzf) 插件，可以很容易地添加和调用重要目录的命名收藏夹.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - 快速跳转到您喜欢的目录.
* [figures](https://github.com/zpm-zsh/figures) - ZSH 的 Unicode 符号.
* [firebase (Seqi)](https://github.com/Seqi/firebase-zsh) - 在 Firebase 项目目录或子目录中显示当前工作项目或项目别名.
* [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) - 在提示中添加一个指示符，表明您位于带有 `firebase.json` 文件（又名“firebase 项目”）的目录中.
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - 允许在 ZSH 中识别 Apple 键盘的小键盘键.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - 此插件使 TYPO3 Flow 发行版的每个子目录中都可以使用 `flow` 命令.
* [fnm](https://github.com/dominik-schwabe/zsh-fnm) - 安装并加载 [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) 如果它丢失了.
* [forgit](https://github.com/wfxr/forgit) - 利用模糊查找器的`git`实用工具 [fzf](https://github.com/junegunn/fzf).
* [functional](https://github.com/Tarrasch/zsh-functional) - ZSH 高阶函数.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH 插件用于模糊搜索文件并立即打开匹配行上的匹配文件.
* [fz](https://github.com/changyuheng/fz) - 无缝添加模糊搜索 [z](https://github.com/rupa/z)的选项卡完成并让您轻松地在历史记录中的目录之间跳转.
* [fzf (unixorn)](https://github.com/unixorn/fzf-zsh-plugin/tree/master) - 启用 [fzf](https://github.com/junegunn/fzf) 历史记录和文件搜索.
* [fzf-fasd](https://github.com/wookayin/fzf-fasd) - 集成 [fzf](https://github.com/junegunn/fzf) 和 [fasd](https://github.com/clvv/fasd) --- 使用 fzf 的模糊搜索完成 `z` 的选项卡！
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - 插件有一个很酷的搜索键绑定 [fzf](https://github.com/junegunn/fzf) 和（可选） [bat](https://github.com/sharkdp/bat) . 在子目录的本地树中搜索文件.
* [fzf-history-search](https://github.com/joshskidmore/zsh-fzf-history-search) - 用一个替换`Ctrl+R` [fzf](https://github.com/junegunn/fzf)包括日期/时间的驱动历史搜索.
* [fzf-it](https://github.com/micakce/fzf-it) - 使用 FZF 功能将任何命令进行交互包装.
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) - 使用模糊查找器在“bash”和“zsh”中创建、导航和删除书签的小脚本 [fzf](https://github.com/junegunn/fzf).
* [fzf-prezto](https://github.com/lildude/fzf-prezto) - 找到位置的 Prezto 插件 [fzf](https://github.com/junegunn/fzf) 已安装并启用其自动完成和键绑定.
* [fzf-tab](https://github.com/Aloxaf/fzf-tab) - 将 ZSH 的默认完成选择菜单替换为 [fzf](https://github.com/junegunn/fzf).
* [fzf-utils](https://github.com/redxtech/zsh-fzf-utils) - 提供杀死进程和在路径中查找的功能 [fzf](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - 添加了一些 ZLE 小部件 [fzf](https://github.com/junegunn/fzf).
* [fzf-z](https://github.com/andrewferrier/fzf-z) - 将 *z* 插件和 *fzf* 结合在一起，让您可以在命令行的任何位置轻松浏览最近使用的目录.
* [fzy](https://github.com/aperezdc/zsh-fzy) - 使用的插件 [fzy](https://github.com/jhawthorn/fzy) 对于某些模糊匹配操作.
* [gcloud-project](https://github.com/avivl/gcloud-project) - 轻松选择 Google Cloud 项目.
* [geeknote](https://github.com/s7anley/zsh-geeknote) - [Geeknote](https://geeknote.me) ZSH 的插件.
* [gentoo](https://github.com/MattiaG-afk/gentoo-ohmyzsh) - 添加了一些别名和函数以与 Gentoo Linux 一起使用.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) 日期时间插件. 在您的提示中显示日期时间（`date` unix 命令）.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to remind you to hydrate.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) 显示当前文件夹的 npm 包版本的插件.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) 当存在 `.rs` 或 `Cargo.toml` 时，显示当前文件夹的 Rust 版本的插件.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - 用于快速下载 jQuery 库的插件 [https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com](https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com).
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - 让你使用 [zeus](https://github.com/burke/zeus) 使用正常的 rails 命令.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - 使用 gimme 管理 Go 安装.
* [git-acp](https://github.com/MenkeTechnologies/zsh-git-acp) - 将当前命令行作为提交信息，然后一键运行 git pull、add、commit 和 push.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) - 轻松将上游遥控器添加到您的 `git` 分支.
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - 中版本的破译版本 [oh-my-zsh](http://ohmyz.sh/) 因此其他框架的用户不必导入所有 oh-my-zsh.
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - 为常用`git` 命令的组合创建了许多有用的别名.
* [git-branches](https://github.com/Schroefdop/git-branches) - 制作一个“git”分支菜单，您可以切换到而无需输入长分支名称.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - 增强`git` 补全以在远程补全中包含剪贴板中的任何URL（例如来自`git clone`）.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - 额外的`git` 辅助脚本打包为插件.
* [git-flow-avh](https://github.com/nekofar/zsh-git-flow-avh) - 为 `git-flow` 命令添加短别名.
* [git-fuzzy](https://github.com/bigH/git-fuzzy) - 严重依赖于`git`的 CLI 接口 [`fzf`](https://github.com/junegunn/fzf).
* [git-ignore](https://github.com/laggardkernel/git-ignore)  - 从 gitignore.io **offline** 生成 `.gitignore` 文件.  `fzf`，完成，预览集成.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - 添加了在 GitHub 上的当前分支中打开文件夹的功能.
* [git-lfs](https://github.com/nekofar/zsh-git-lfs) - 为 git-lfs 命令添加短别名.
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - 为`git` 添加了一些功能.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - 为`git` user.email 添加提示提醒.
* [git-prune (diazod)](https://github.com/diazod/git-prune) - 允许您删除已在本地存储库中合并和/或在远程源存储库中合并的所有分支.
* [git-prune (seinh)](https://github.com/Seinh/git-prune) - 简化删除合并分支的插件.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) - 添加了`git-squash-branch` 和`git-remove-merged` 命令.
* [git-secret](https://github.com/sobolevn/git-secret) - 用于将您的私人数据存储在`git` 存储库中的 bash 工具.
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - 添加额外的 `git` 命令以使一些常见的 `git` 用法更有效.
* [git-sync](https://github.com/caarlos0/zsh-git-sync) - 一个用于同步 `git` 存储库并清理它们的 ZSH 插件.
* [git](https://github.com/davidde/git)  - 替换现有的 oh-my-zsh git 插件. 提供了很多有用的别名和函数. 替换默认插件的动机源于它带有一些不一致的事实，这使得一些流行的命令相当不直观，所以这个插件使别名保持一致.
* [gitcd (SukkaW)](https://github.com/SukkaW/zsh-gitcd) - 将命令添加到`git clone` 存储库和`cd` 到结果目录中.
* [gitcd (viko16)](https://github.com/viko16/gitcd.plugin.zsh) - 克隆后自动`cd`到`git`工作目录.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - 更新了 oh-my-zsh gitfast 插件的分支.
* [gitgo](https://github.com/ltj/gitgo) - 从命令行（仅限 macOS）在浏览器中打开 Github/Gitlab 存储库.
* [github-issues](https://github.com/zdharma/zsh-github-issues) - 在 Github 上订阅项目并在 shell 内（在提示下）接收有关新问题的通知.
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - 用于创建`.gitignore` 文件的插件.
* [gitio](https://github.com/denysdovhan/gitio-zsh) - 用于生成 GitHub 短 URL 的 ZSH 插件 [git.io](https://git.io).
* [gitstatus](https://github.com/Insert-Creative-Name-Here/gitstatus.zsh) - 可以轻松地在提示中显示您的 `git` 状态.
* [gitsync](https://github.com/washtubs/gitsync) - ZSH 插件可改进一个人在多台机器上的同一个存储库上开发的工作流程.
* [goenv (CDA0)](https://github.com/CDA0/zsh-goenv/blob/master/zsh-goenv.plugin.zsh) - 用于安装、更新和加载 goenv 的插件.
* [goenv (bbenne10)](https://github.com/bbenne10/goenv) - 管理 `$GOPATH` 类似于 Python 的 virtualenvwrapper.
* [going_places](https://github.com/or17191/going_places) - 一个有助于使用、创建和维护外壳位置列表的插件.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - 在设置 GPG 代理以在 macOS 上充当 SSH 代理时，该插件会尝试做正确的事情.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) - 用于加密和解密文件或目录的 ZSH 插件.
* [grep2awk](https://github.com/joepvd/grep2awk) - ZLE 小部件将`grep` 命令转换为`awk` 命令.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - 为 `grunt` 添加自动完成功能.
* [gsh](https://github.com/cjayross/gsh) -`git` 的辅助函数集合
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - 终端插件 [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [gtr](https://github.com/Zocker1999NET/zsh-gtr) - 允许使用标签名称 **release-YYYY-MM-DD-HH-MM** 和标题 **Release YYYY-MM-DD HH:MM** 在 git 中快速标记发布.
* [guish](https://github.com/gcarrarom/oh-my-guish) - Collection of utility functions and aliases.
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - 包装插件 [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
* [gunstage](https://github.com/LucasLarson/gunstage)  - 至少有八种方法可以在 `git` 存储库中取消暂存文件. 这是一个用于撤消`git add`的命令行shell插件.
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - ZSH 的 gvm（Go 版本管理器）插件.
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - 为`gvm`（Groovy 环境管理器）提供自动完成功能.
* [hab](https://github.com/alexdesousa/hab) - 如果在更改到新目录时找到文件`.envrc` 中定义的操作系统环境变量，则自动加载它.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - 打开终端时随机输出黑客报价.
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - 为 hadoop 函数添加了一些方便的别名.
* [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH 插件 [hanami](http://hanamirb.org) 项目.
* [hangul](https://github.com/gomjellie/zsh-hangul)  - 自动更正韩语（韩语，韩语）到英语时应该输入英语. 您必须输入英文，但如果您输入韩文，则会自动更正.
* [hbt](https://github.com/lzambarda/hbt) - 基于过去命令使用情况的启发式 ZSH 建议系统.
* [hints](https://github.com/joepvd/zsh-hints) - 在编辑缓冲区下显示全局和参数标志以及其他不完整的信息.
* [hipchat](https://github.com/robertzk/hipchat.zsh) - 从 shell 发送 hipchat 消息.
* [hist](https://github.com/marlonrichert/zsh-hist) - 在 ZSH 中编辑您的历史记录，无需离开命令行.
* [histdb](https://github.com/larkery/zsh-histdb)  - 将您的历史记录存储在 SQLite 数据库中. 可与 [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions).
* [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer)  - 通过更多交互和多行选择菜单增强历史搜索. 需要 nodejs.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter)  - 允许您指定将自动排除命令插入永久历史记录的模式. 对于防止写入机密特别有用.
* [history-here](https://github.com/leonjza/history-here) - 绑定`^G` 以快速切换当前shell 历史文件位置.
* [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) - 捕获 PageUp 键并使用 `dialog` 打开带有历史记录的弹出菜单，因此用户可以交互地浏览它并选择历史记录行以返回提示.
* [history-search-multi-word](https://github.com/zdharma/history-search-multi-word) - ZSH 的语法高亮、多词历史搜索器，绑定到 Ctrl-R，具有高级功能（例如历史条目到历史顶部的碰撞）.
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search)  - 需要在 `zsh-syntax-highlighting` 之后加载，否则它们都会中断. 您还需要将键绑定到它的函数，详细信息在 README.md 中.
* [history-sync](https://github.com/wulfgarpro/history-sync) - 一个 Oh My Zsh 插件，用于 GPG 加密，互联网同步 ZSH 历史，使用 `git`.
* [history](https://github.com/b4b4r07/zsh-history) - 扩展历史，以便可以通过 SQL 查询.
* [hitokoto](https://github.com/derry96/hitokoto) - 显示来自的随机报价 [hitokoto.cn](https://hitokoto.cn/).
* [homeassistant-cli](https://github.com/frosit/zsh-plugin-homeassistant-cli) - 提供完成和（配置）助手 [Home Assistant Command-line interface (hass-cli)](https://github.com/home-assistant/home-assistant-cli) . 并允许与命令行交互 [Home Assistant](https://home-assistant.io/) 实例.
* [homebrew](https://github.com/digitalraven/omz-homebrew) - 插件 [homebrew](https://brew.sh) 它补充了 oh-my-zsh 中内置的那个.
* [hooks](https://github.com/willghatch/zsh-hooks) - 添加缺少的钩子 - 用于插件和个人使用.
* [host-switch](https://github.com/LockonS/host-switch) - 在开发过程中更容易切换不同的 `/etc/hosts` 文件.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - 一个简单的插件，用于将 `hub` ci-status 添加到您的 ZSH 主题.
* [hub](https://github.com/soraliu/zsh-hub) - 用于分叉模型的 ZSH 插件.
* [igit](https://github.com/ytakahashi/igit) - 交互式`git`命令使用 [fzf](https://github.com/junegunn/fzf).
* [ing](https://github.com/rummik/zsh-ing) - 简化的`ping` 输出.
* [instant-repl](https://github.com/jandamm/instant-repl.zsh) - 为当前 ZSH 会话中的任何命令激活 REPL.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - `cd` 的类似鱼的交互式选项卡完成.
* [iosctl](https://github.com/obayer/iosctl) - 快速访问正在运行的模拟器的应用程序、数据和日志.
* [ipip](https://github.com/SukkaW/zsh-ipip) - 插件 [IPIP](https://en.ipip.net).
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - 在iTerm2中添加了设置标签颜色的功能，可以根据cwd或正在执行的命令自动更改颜色.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - 根据当前工作目录自动更改 iTerm 2 选项卡颜色.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - 在 MacbookPro TouchBar 中显示 iTerm2 反馈（当前目录、git 分支和状态）.
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - 从命令行管理 iTerm 2 的配色方案.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - 设置 iTerm 2 标签的颜色和标题.
* [iterm2-utilities](https://github.com/decayofmind/zsh-iterm2-utilities) - 帮助下载各种 iTerm2 实用程序，并让您无需克隆整个 iTerm2-website 存储库或依赖其他可能不同步的存储库.
* [iterm2](https://github.com/laggardkernel/zsh-iterm2) - 将 iTerm 的 ZSH 集成脚本打包到 ZSH 插件中，以避免污染您的 $HOME 目录，时间增加可忽略不计，仅为 2ms.
* [jabba](https://github.com/2m/zsh-jabba) - 添加 shell 集成代码和完成 [jabba](https://github.com/shyiko/jabba) Java 版本管理器.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - 添加了`setjdk` 命令，以便您可以在不同版本的jdk 之间轻松切换.
* [javaVersions](https://github.com/miguefl/javaVersions) - 使用单个命令在不同的 Java 版本之间切换.
* [jdk-switch](https://github.com/LockonS/jdk-switch) - 用于在 jdk 版本之间切换的仅限 macOS 的插件.
* [jenkins](https://github.com/tomplex/jenkins-zsh) - ZSH 的 jenkins 插件，深受优秀 jira 插件的启发.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - 用于延迟加载 jEnv 的 ZSH 插件.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - 添加命令 [jHipster](https://www.jhipster.tech/).
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - 从命令行创建 JIRA 票证.
* [jq](https://github.com/reegnz/jq-zsh-plugin) 具有行编辑器功能的 jq-repl.
* [jvm](https://github.com/mgryszko/jvm) - 允许在 macOS 上选择 JDK.
* [k](https://github.com/supercrabtree/k) - 带有“git”状态装饰的 ZSH 目录列表.
* [kill-node](https://github.com/vmattos/kill-node) - 用于谋杀“节点”进程家族的 ZSH 插件.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - oh-my-zsh 的 KitsuneBook 插件.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - 从 ZSH 切换 konsole 主题.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - 用于“kubectl”的 ZSH 插件，用于添加当前上下文和命名空间.
* [kubecolor](https://github.com/droctothorpe/kubecolor) - 对 `kubectl get events -w` 的输出进行简化和着色
* [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) - 用于管理 `kubectl` 的 ZSH 插件.
* [kubectx (ptavares)](https://github.com/ptavares/zsh-kubectx) - 安装和加载 [kubectx](https://github.com/ahmetb/kubectx).
* [kubectx (unixorn)](https://github.com/unixorn/kubectx-zshplugin) - 自动安装 [kubectx](https://github.com/ahmetb/kubectx) 和`kubens`.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) - 添加 [kubernetes](https://kubernetes.io) 辅助函数和别名.
* [lando (joshuabedford)](https://github.com/JoshuaBedford/lando-zsh) - 一组别名函数，可在其中使用 CLI [Lando](https://docs.lando.dev) 无需键入lando即可访问它们.
* [lando (mannuel)](https://github.com/mannuel/lando-alias-zsh) - Adds aliases for various [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) 命令.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - 提供接口 [Laradock](http://laradock.io/)的工作区.
* [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) - 为 Laravel 6 添加别名.
* [laravel-sail](https://github.com/ariaieboy/laravel-sail) - 为`sail` 命令添加快捷方式.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - 为 Laravel 5、5.1、5.2 和 5.3 添加快捷方式.
* [last-working-dir-tmux](https://github.com/Curly-Mo/last-working-dir-tmux) - 在全局和每个 tmux 会话中跟踪上次使用的工作目录，并自动跳转到新 shell 中.
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) - 打破版本的副本 [oh-my-zsh](http://ohmyz.sh/) . 跟踪上次使用的工作目录并自动跳转到新 shell 中.
* [lazyload](https://github.com/qoomon/zsh-lazyload) - 延迟加载命令并加快 ZSH 的启动时间.
* [learn](https://github.com/MenkeTechnologies/zsh-learn) - MySQL/MariadB 中的学习集合，可保存、查询和测验您所学的一切.
* [lesaint-git](https://github.com/lesaint/lesaint-git) - 替换 Oh-My-Zsh 兼容框架的 `git` 插件.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - 用于 oh-my-zsh 的 Maven 插件.
* [liferay](https://github.com/david-gutierrez-mesa/liferay-zsh) - 添加脚本 [liferay](https://github.com/liferay/liferay-portal) 发展.
* [linkfile](https://github.com/JaumeRF/linkfile-zsh) - 为您喜欢的目录添加快捷方式.
* [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) - 打开终端时输出随机 Linus Torvalds 咆哮.
* [listbox](https://github.com/gko/listbox) - 外壳的列表框元素.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - 允许搜索 [Sublime Text](https://www.sublimetext.com) 项目并在 Sublime 中打开它们.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum)  - 在命令行上生成 lorem ipsum 文本. 从 [lipsum.com](https://www.lipsum.com).
* [ls](https://github.com/zpm-zsh/ls) - 为 `ls` 的输出着色.
* [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack 是 shell 脚本的日志记录界面.
* [lux](https://github.com/pndurette/zsh-lux)  - ZSH 插件可通过 `lux` 命令切换 macOS 和其他项目和应用程序的明暗模式. 高度可定制：可以通过定义变量来配置包含的项目. 高度可扩展：可以通过定义功能来添加项目. 包括 `macos_is_dark` 辅助函数，以确定 macOS 暗模式是否处于活动状态以用于主题.
* [mac-packaging](https://github.com/Temikus/mac-packaging) - 一套用于企业 Mac 打包的常用函数 [Munki](https://www.munki.org/munki/).
* [macos](https://github.com/joow/macos) - 适用于 macOS 的 ZSH 插件.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) - 可以轻松使用 Docker 和 Magento 2.在容器上的 Magento 2 中加速和简化常用命令，如清理缓存、设置升级、编译 di 等.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - 添加 `m2` 函数来运行 magento 二进制文件，添加选项卡完成.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) - 用于模拟 `...&#39;==`../..&#39; 等的 zle 调整.
* [markedit](https://github.com/zakariaGatter/MarkEdit) - 标记文件并使用现有标记的自动完成功能对其进行编辑.
* [markgate](https://github.com/zakariaGatter/MarkGate) - 允许您标记目录，以便您可以直接跳转到它们.
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - oh-my-zsh maven 插件的一个分支.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) - 从 oh-my-zsh 中提取，因此您可以在没有 oh-my-zsh 的情况下使用它.
* [mfunc](https://github.com/hlohm/mfunc)  - 允许您即时定义持久函数，而无需将它们添加到您的配置文件中. 这些功能将永久可用，直到您将其删除.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - 用于在普通模式和 `vi` 模式之间切换命令行的 ZSH 插件.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - 用于 monorepo 管理的 ZSH 插件.
* [monthrename](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) - 将月份名称重命名为文件名中的数字.
* [morpho](https://github.com/psprint/zsh-morpho) - 用纯 ZSH 编写的终端屏幕保护程序，以及屏幕保护程序框架.
* [mouse-status](https://github.com/gryffyn/mouse-status) - 根据状态代码更改鼠标颜色，使用 libratbag.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - 用于轻松启动处理程序的 Metasploit 处理程序插件.
* [mvn-contexts](https://github.com/artemy/zsh-mvn-contexts) - 允许在 Maven 配置之间快速切换.
* [mylocation](https://github.com/fALKENdk/mylocation) - 一个插件，可根据您的 IP 地址显示您的当前位置.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - 为 mysql 表添加颜色.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - 增加了一些处理mysql的功能.
* [n](https://github.com/gretzky/n.zsh) - 使用基于项目环境自动切换节点版本 [n](https://github.com/tj/n).
* [navi](https://github.com/icatalina/zsh-navi-plugin/) - 插件 [navi](https://github.com/denisidoro/navi).
* [navigation-tools](https://github.com/psprint/zsh-navigation-tools) - 添加类似`htop` 的`kill`、目录书签浏览器、多字增量历史搜索器等.
* [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) - 从模板生成文件.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - 将退出状态代码映射到人类可读的字符串.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) - 允许您在 `nix-shell` 环境中使用 ZSH 作为默认 shell 的插件.
* [nnvm](https://github.com/torifat/nnvm)  - 基于`.nvmrc` 自动切换节点版本. 需要 [n](https://github.com/tj/n).
* [node-env-installer](https://github.com/shiro-saber/node-env-installer) - 使用 `nvm` 为当前项目安装新版本和模块.
* [node-path](https://github.com/andyrichardson/zsh-node-path) - 自动将当前目录的“npm bin”添加到您的路径中.
* [node](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty 的用于 ZSH 的 nodejs 插件，具有缓存 `nvm` 完成和自动加载 `nvm`（如果存在）.
* [nodenv (c-uo)](https://github.com/C-uo/zsh-nodenv) - 在您的工作目录中查找 nodeenv 并在找到时加载它.
* [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) - 自动加载 `nodeenv` 及其完成到 shell.
* [nodenv (mattberther)](https://github.com/unixorn/awesome-zsh-plugins/blob/master/mattberther/zsh-nodenv)  - 安装、更新和加载 `nodenv`. 受 zsh-rbenv 的启发.
* [nohup](https://github.com/micrenda/zsh-nohup) - 按`Ctrl-H`将`nohup`添加到当前命令.
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS 用户知道在他们的 macOS 版本上试图找出什么命令实际刷新 DNS 缓存的痛苦，而这个插件让这种烦恼消失了.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - 灵感来自 [terminal_velocity](https://www.seanh.cc/terminal_velocity/)，它提供了一个快速的接口来创建和访问一组 [Markdown](https://en.wikipedia.org/wiki/Markdown) 目录中的文本文件.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - 在 ZSH 中提供快速的笔记编辑体验.
* [notify (luismayta)](https://github.com/luismayta/zsh-notify) - 自动安装依赖项和 r2d2 声音的 ZSH 通知.
* [notify (marzocchi)](https://github.com/marzocchi/zsh-notify) - ZSH 插件（在 macOS 和 Linux 上），当命令以非零退出状态终止或完成时间超过 30 秒时，如果终端应用程序在后台（或命令的终端），它会发布桌面通知选项卡处于非活动状态）.
* [npm (igoradamenko)](https://github.com/igoradamenko/npm.插入.zsh)  - 添加 `npm` 别名和命令完成. 基于 Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npm (trystan2k)](https://github.com/trystan2k/zsh-npm-plugin)  - 添加 `npm` 别名. 基于 Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) 插入.
* [npms](https://github.com/torifat/npms)  - 由`fzf` 提供支持的实用程序，用于交互使用 npm 脚本. 需要 [fzf](https://github.com/junegunn/fzf) 和 [jq](https://stedolan.github.io/jq/).
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - 每当你进入一个包含 `.nvmrc` 文件的目录时，都会自动调用 `nvm use`，该文件带有一个告诉 `nvm` 使用哪个节点的字符串.
* [nvm-auto](https://github.com/dijitalmunky/nvm-auto) - 旨在尽可能减少需要键入 `nvm use`，特别是如果您经常在 node.js 版本之间切换并在项目中使用 `.nvmrc` 文件来管理您的项目需要的节点版本.
* [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy)  - 用于延迟加载 oh-my-zsh 的 **nvm** 插件的插件. 它支持对多个二进制文件/入口点延迟加载 `nvm`，默认值为 `nvm`、`node` 和 `npm`.
* [nvm](https://github.com/lukechilds/zsh-nvm) - 用于安装、更新和加载 `nvm` 的 ZSH 插件.
* [oath](https://github.com/alexdesousa/oath)  - 管理 2FA 身份验证 6 位令牌. 这篇文章对它的启发很大 [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
* [oclif completion generator](https://github.com/MunifTanjim/oclif-plugin-completion) - 为缺少它们的命令生成 shell 补全.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - 将您的终端变成矩阵.
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) - 在 Jetbrains 中打开/创建项目.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) - 从命令行打开拉取请求的 ZSH 插件.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - 为常见的 openshift origin (oc) 操作添加一些快捷方式.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` aliases.
* [operator](https://github.com/nivv/operator-theme) - 干净简洁的主题，最适合与 Menlo for Powerline 搭配使用.
* [opp](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for ZSH.
* [opt-path](https://github.com/jreese/zsh-opt-path) - 自动将 `~/opt` 子路径添加到你的 `$PATH`.
* [osx-autoproxy](https://github.com/SukkaW/zsh-osx-autoproxy) - 根据 macOS 的系统首选项配置代理环境变量.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - 此插件添加了一些命令，用于在 macOS 安装上维护各种服务器程序.
* [osx](https://github.com/mwilliammyers/plugin-osx) - 添加一些常见的 macOS 相关别名和功能.
* [p10k-promptconfig](https://github.com/doctormemes/p10k-promptconfig) - 通过在 `.zshrc` 文件中定义 `P10K_PROMPT` 变量，添加了在 Powerlevel10k 提示主题配置文件之间轻松切换的功能.
* [paci](https://github.com/iloginow/zsh-paci) - archlinux 包管理器插件.
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin)  - 长时间运行的命令的后台通知. 支持基本操作系统 Freya.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) - 防止密码进入您的命令行历史记录.
* [pctl](https://github.com/ytet5uy4/pctl) - 切换用于代理的环境变量.
* [peco-history](https://github.com/jimeh/zsh-peco-history) - 按 ctrl+R 时使用 Peco 搜索 shell 历史记录.
* [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) - 懒惰渗透测试人员的别名和功能.
* [per-directory-history](https://github.com/jimhester/per-directory-history) - ZSH 的每个目录历史记录，以及全局历史记录，以及使用“^G”在它们之间切换的能力.
* [percol](https://github.com/robturtle/percol.plugin.zsh) - 使用交互式和增量式搜索历史记录/恢复后台工作 [percol](https://github.com/mooz/percol).
* [perlbrew](https://github.com/tfiala/zsh-perlbrew/) - 安装 [perlbrew](https://perlbrew.pl/) 如果尚未安装并为您的外壳初始化它.
* [pew](https://github.com/shosca/zsh-pew) - 使用设置和管理 Python virtualenvs [pew](https://github.com/berdario/pew), 在您移动目录时自动切换 virtualenvs.
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) - 添加实用功能以使用 [PostgreSQL](https://www.postgresql.org/).
* [ph-marks](https://github.com/lainiwa/ph-marks) - 从您的终端为色情中心视频添加书签.
* [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) - 使用 php 版本自动切换 [php-version](https://github.com/wilmoore/php-version) 如果目录中存在 rc 文件.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - 插件 [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) - 自动加载 [phpenv](https://github.com/sptndc/phpenv) 和它的完成.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - 插件 [PHPUnit](https://phpunit.de/).
* [pip-app](https://github.com/sharat87/pip-app) - 可以轻松地将 Python 应用程序安装到不同的 Python virtualenvs 中，因此它们不会与系统上的任何其他 Python 要求发生冲突.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) - 自动 [pipenv](https://pipenv.readthedocs.io/en/latest/) 进入 pipenv 项目时激活.
* [pipx](https://github.com/thuandt/zsh-pipx) - 自动完成 [pipx](https://github.com/pypa/pipx).
* [pkenv](https://github.com/ptavares/zsh-pkenv) - 安装和加载 [pkenv](https://github.com/iamhsa/pkenv.git)
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - 添加 ibtool 快捷方式以生成本地化的 XIB 文件.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - Rails 的 ZSH 插件.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Visual Studio Code 插件，适用于 macOS、Windows 和 Linux 的文本编辑器.
* [plugin](https://github.com/darrenbutcher/plugin)  - 从样板模板创建自定义 oh-my-zsh 插件. 非常以 oh-my-zsh 为中心，生成的插件需要编辑才能与其他框架一起使用.
* [pnpm](https://github.com/ntnyq/omz-plugin-pnpm) - 为常用 Pnpm 命令添加有用的别名.
* [poetry (darvid)](https://github.com/darvid/zsh-poetry) - 自动激活和停用 [Poetry](https://poetry.eustace.io/)-创建了 python virtualenvs.
* [poetry (sudosabin)](https://github.com/sudosubin/zsh-poetry) - 启用诗歌`$PATH` 和自动补全.
* [posh-git-bash](https://github.com/lyze/posh-git-sh) - 在您的提示中添加 `git` 状态.
* [ppsmon](https://github.com/mzpqnxow/ppsmon)  - 读取 `/sys/class/net/$interface/` 以跟踪数据包传输速率. 它将当前速率存储到 RAM 支持的文件系统中的文件中，在该文件系统中可以轻松访问以在 shell 提示中显示. 由于使用了`/sys`，因此仅适用于 Linux.
* [pr-cwd](https://github.com/zpm-zsh/pr-cwd)  - 使用当前工作目录创建一个全局变量. 插件与 [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
* [pr-eol](https://github.com/zpm-zsh/pr-eol) - 显示可以嵌入提示中的 EOL 符号.
* [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) - Adds a variable you can use to display the execution time of the last command run.
* [pr-git](https://github.com/zpm-zsh/pr-git) - 使用可以在提示中显示的 `git` 状态信息创建一个全局变量.
* [pr-is-root](https://github.com/zpm-zsh/pr-is-root) - 设置一个环境变量，您可以在以 root 身份运行时在自定义提示中使用.
* [pr-jobs](https://github.com/zpm-zsh/pr-jobs) - 创建一个环境变量，可用于在自定义提示中显示后台作业信息.
* [pr-node](https://github.com/zpm-zsh/pr-node) - 设置一个环境变量，可用于在自定义提示中显示 nodeJS 信息.
* [pr-return](https://github.com/zpm-zsh/pr-return) - ZSH 插件，显示上次运行命令的退出状态.
* [presenter-mode](https://github.com/idadzie/zsh-presenter-mode)  - 在演示期间扩展别名. 它还增加了终端窗口的对比度以增强可见性.
* [pretty-time (sindresorhus)](https://github.com/sindresorhus/pretty-time-zsh) - 将秒转换为人类可读的字符串：165392 → 1d 21h 56m 32s.
* [pretty-time (zpm-zsh)](https://github.com/zpm-zsh/pretty-time) - 将原始秒数转换为人类可读的字符串.
* [print-alias](https://github.com/brymck/print-alias) - 每当您在命令行中使用别名时，都会打印带有扩展别名的命令.
* [printc](https://github.com/philFernandez/printc) - 允许您通过简单的 `printc` 调用在 RGB 空间中以任何颜色打印.
* [profile-secrets](https://github.com/gmatheu/shell-plugins)  - 安全地将敏感变量（api 令牌、密码等）作为终端初始化文件的一部分. 使用 gpg 使用您的机密加密/解密文件.
* [project (gko)](https://github.com/gko/project) - 在本地和 github（私有或公共存储库）上创建 node/python/ruby 项目.
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - 用于管理项目的插件.
* [prompt-generator](https://github.com/the10thWiz/zsh-prompt-generator)  - 生成自定义主题. 一些生成的主题需要与电力线兼容的字体.
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - 快速启用和禁用代理外壳环境设置.
* [proxy](https://github.com/SukkaW/zsh-proxy) - 为某些包管理器和软件配置代理设置.
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - 在 ZSH 中延迟加载 `pyenv` 的插件.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy)  - 懒加载pyenv. 最初的 `eval &quot;$(pyenv init -)&quot;` 在第一次调用 `pyenv` 时执行.
* [pyenv](https://github.com/mattberther/zsh-pyenv)  - 灵感来自 zsh-rbenv. 安装、更新或加载 `pyenv`，并添加额外的功能.
* [q (cal2195)](https://github.com/cal2195/q) - 将类似 `vim` 的宏寄存器添加到您的 ZSH shell.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - 删除/删除临时文件 [Q](https://github.com/y0ssar1an/q)，脏调试工具.
* [qiime2](https://github.com/misialq/zsh-qiime2) - 添加函数和别名以使其工作 [Quiime 2](https://qiime2.org/) 更轻松.
* [quoter](https://github.com/pxgamer/quoter-zsh) - 打开新的终端会话时显示随机报价.
* [quotify](https://github.com/damofthemoon/zsh-quotify) - 启动时显示来自我们对的鼓舞人心的编码报价.
* [randeme](https://github.com/ex-surreal/randeme)  - 为每个会话选择一个随机主题. 如果您不喜欢所选主题，您可以运行 `randeme_rm` 以不再显示该主题.
* [random-quotes](https://github.com/vkolagotla/zsh-random-quotes) - 显示随机引用或事实.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - 改变你的颜色 [Razer Mouse](https://openrazer.github.io/) 基于上次执行命令的状态. 需要 [OpenRazer](https://openrazer.github.io) linux驱动程序.
* [rbenv (ELLIOTTCABLE)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - 来自 oh-my-zsh 的 rbenv 插件的更快分支.
* [rbenv (Meroje)](https://github.com/Meroje/zsh-rbenv) - 灵感来自 [https://github.com/lukechilds/zsh-nvm/](https://github.com/lukechilds/zsh-nvm/), 使使用 ruby​​ rbenvs 更容易.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - Variant based on the original oh-my-zsh rbenv plugin.
* [rc-files](https://github.com/0b10/rc-files) - 增加了编辑各种rc文件的快捷功能.
* [recall](https://github.com/mango-tree/zsh-recall) - 使使用命令历史更容易.
* [redis](https://github.com/zservices/redis)  - 将运行`redis-server` 指向`redis.conf` 配置文件. 这可以与 [zdharma/zredis](https://github.com/zdharma/zredis) 在 shell 之间共享变量的插件.
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - 如果已删除并重新创建，则重新进入工作目录的插件.
* [reload](https://github.com/aubreypwd/zsh-plugin-reload) - 添加了快速重新加载`.zshrc` 的功能.
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - 在每个提示上方显示提醒的插件.
* [replace-multiple-dots](https://github.com/momo-lab/zsh-replace-multiple-dots) - 将 `...` 转换为 `../..`
* [revolver](https://github.com/molovo/revolver) - ZSH 脚本的进度微调器.
* [riddle-me](https://github.com/vkolagotla/zsh-riddle-me) - 显示随机谜语.
* [ripz](https://github.com/jedahan/ripz)  - 提醒您别名，以便您更多地使用它们. 依赖于取决于 [ripgrep](https://github.com/BurntSushi/ripgrep).
* [robo](https://github.com/shengyou/robo-zsh-plugin) - 一个 ZSH 插件 [Robo](https://robo.li/).
* [rockz](https://github.com/aperezdc/rockz) - 基于 VirtualZ 的 Lua + LuaRocks 虚拟环境管理器.
* [rust](https://github.com/cowboyd/zsh-rust) - 配置你的 Rust 工具链，安装 [rustup](https://rustup.rs) 如果当前尚未安装.
* [rvm](https://github.com/johnhamelink/rvm-zsh) - 启动 RVM 并添加可在用户的 `$PATH` 中访问的 ruby​​gem 二进制文件（如指南针）.
* [safe-kubectl](https://github.com/benjefferies/safe-kubectl) - 在运行 `kubectl` 时通过警告自上次 `kubectl` 命令后可定义的秒数后你所处的上下文来增加一些安全性.
* [safe-paste](https://github.com/oz/safe-paste)  - 一个安全粘贴插件. 见康拉德欧文 [bracketed-paste](https://cirw.in/blog/bracketed-paste) 博客文章.
* [safe-rm](https://github.com/mattmc3/zsh-safe-rm) - 添加安全 rm 功能，以便 `rm` 将文件放入操作系统的垃圾箱中，而不是永久删除它们.
* [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) - 当使用多个 AWS 配置文件时，例如您的阶段（开发、预生产、生产）的不同帐户，可用于确定当前导出的配置文件以及令牌是否仍然有效.
* [saml2aws](https://github.com/onyxraven/zsh-saml2aws) - 添加对 [saml2aws](https://github.com/Versent/saml2aws).
* [sandboxd](https://github.com/benvan/sandboxd) - 通过仅在需要时运行设置命令（例如，`eval &quot;$(rbenv init -)&quot;` 等），通过延迟加载加速你的 `.zshrc` 和 shell 启动.
* [saneopt](https://github.com/willghatch/zsh-saneopt) - 本着 vim-sensible 的精神，Sane 默认为 ZSH 选项.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) - 在提示中显示当前的 `chroot` 名称.
* [search-directory-history](https://github.com/cmaahs/search-directory-history) - 允许对使用创建的每个目录历史进行复杂搜索 [per-directory-history](https://github.com/jimhester/per-directory-history) 插入.
* [sed-sub](https://github.com/MenkeTechnologies/zsh-sed-sub) - 添加键绑定以在当前命令行上进行全局搜索和替换.
* [select](https://github.com/psprint/zsh-select) - 具有近似匹配和 uniq 模式的多词搜索选择列表.
* [send](https://github.com/robertzk/send.zsh) - `git add`、`git commit` 和 `git push` 的单一命令，以实现更快的 `git` 工作流程.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - 添加了许多 `git` 别名和辅助 shell 函数.
* [session-sauce](https://github.com/ChrisPenner/session-sauce) - 用于为所有项目创建和管理 tmux 会话的 fzf 接口.
* [setenv](https://github.com/kalpakrg/setenv) - 更改目录时运行脚本.
* [shelf](https://github.com/ecmma/shelf) - 可用于使用助记符为任何文件添加书签和直接访问的实用程序.
* [show-path](https://github.com/redxtech/zsh-show-path) - 提供了逐行显示`$PATH` 的函数.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - 插件可以轻松启动 python `SimpleHTTPServer` 和 `SimpleHTTPSServer`.
* [skim](https://github.com/hackerchai/skim-zsh) - 增加了对 [skim](https://github.com/lotabout/skim)
* [slugify](https://github.com/lashoun/slugify) - 将文件名和目录转换为网络友好格式.
* [smart-cd](https://github.com/dbkaplun/smart-cd) - 在 chpwd 之后运行 `ls` 和 `git status`.
* [smile](https://github.com/fundor333/smile) - 添加显示随机笑脸的功能.
* [snippets](https://github.com/willghatch/zsh-snippets) - 命令行片段扩展.
* [solarized-man](https://github.com/zlsun/solarized-man) - oh-my-zsh 插件彩色手册页的修改版本，针对 [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) theme in the terminal.
* [ssh-connect](https://github.com/gko/ssh-connect) - 一个简单的 `ssh` 管理器.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - ssh 插件.
* [sshukh](https://github.com/anatolykopyl/sshukh-zsh-plugin) - Will update your `known_hosts` file when you `ssh` into a server.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - 打印外壳启动所需的时间.
* [stashy](https://github.com/MisterRios/stashy) - 简化使用`git stash`的插件.
* [statify](https://github.com/vladmrnv/statify) - 进行基本统计分析的插件.
* [sublime](https://github.com/valentinocossar/sublime) - 与 Oh My Zsh 的官方 Sublime 插件相同，但是这会在当前 Sublime 窗口中打开文件（如果已经打开了）.
* [sudo](https://github.com/hcgraf/zsh-sudo)  - 来自 oh-my-zsh 的 `sudo` 插件，提取到一个独立的. 通过在 emacs 模式或 vi 命令模式下按 *ESC-ESC* 在当前/上一个命令之前切换 `sudo`.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - 使用 ZSH 的后缀别名直接在 shell 中打开文件.
* [svn-n-zsh](https://github.com/khrt/svn-n-zsh-plugin) - 重写股票 oh-my-zsh svn 插件.
* [switch-git](https://github.com/robin-mbg/switch-git)  - 在`git` 存储库之间轻松切换. 只需输入`sgr<some part of you repo's name>  `，按回车键即可.
* [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) - Symfony 2 和 3 的 ZSH 插件.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - 使用 dircolors 实时突出显示 ZSH 语法.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)  - 为您的 ZSH 添加语法高亮. 确保你加载了这个 _before_ zsh-users/zsh-history-substring-search 否则它们都会中断.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - 用于目录更改或编辑器启动的 ZSH 插件，仅使用小部件进行关键操作，无需键入命令.
* [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp 为系统管理员收集的工具脚本.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard)  - 为 vi 仿真键盘映射添加对 ZLE（Zsh 行编辑器）剪贴板操作的键绑定支持. 它适用于 Linux、macOS 和 Android（通过 Termux）.
* [systemd](https://github.com/le0me55i/zsh-systemd) - 为`systemd` 添加了许多别名.
* [t32](https://github.com/chrissicool/zsh-t32)  - Lauterbach Trace32 工具集的插件. 它会自动注册字体并设置所有必要的环境变量来运行 t32 工具集.
* [tab-title](https://github.com/trystan2k/zsh-tab-title)  - 根据当前目录或运行进程设置终端标签标题. 分叉自 [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh)
* [tailf](https://github.com/rummik/zsh-tailf) - 添加带有前缀换行符而不是尾随换行符的 `tailf` 函数.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - 自动完成任务簿的任务编号.
* [terminal-app](https://github.com/the8/terminal-app.zsh) - 用于与新的 El Capitan Terminal.app 功能集成的插件.
* [terminal-title](https://github.com/AnimiVulpis/zsh-terminal-title) - 添加了一个“set-term-title”函数，你可以用它来给终端窗口加上标题.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - 计算和显示通过终端运行了多少命令的插件.
* [termux](https://github.com/zpm-zsh/termux) - 增加兼容性 [Termux](https://termux.com/)
* [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) - 添加 terraform 工作区以进行提示.
* [terraform (jsporna)](https://github.com/jsporna/terraform-zsh-plugin)  - 使用别名和制表符补全扩展了原始的 oh-my-zsh 插件. 添加工作区（当不是默认值时）以进行提示.
* [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) - 添加方便的别名 [terraform](https://terraform.io/)、制表符补全和辅助函数，用于在提示中添加您的 terraform 工作区.
* [terraform (pbar1)](https://github.com/pbar1/zsh-terraform) - ZSH 的 Terraform 便利函数和别名.
* [terraform (thuandt)](https://github.com/thuandt/zsh-terraform) - 为 `terraform` 添加了便利别名，以及对 `terraform` 和 `terragrunt` 的补全.
* [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - 插件 [Terragrunt](https://github.com/gruntwork-io/terragrunt)，一个薄包装 [Terraform](https://terraform.io/) 这提供了额外的工具.
* [tfenv](https://github.com/CDA0/zsh-tfenv) - 安装、更新和加载受启发的 tfenv [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)
* [thefuck](https://github.com/laggardkernel/thefuck) - 负载 [thefuck](https://github.com/nvbn/thefuck) （一种更正您之前命令的工具）具有缓存支持，可显着减少加载时间.
* [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) - 使用的便利功能 [theia-ide](https://github.com/theia-ide/theia).
* [tig](https://github.com/zdharma/zsh-tig-plugin) - 添加了一些高级绑定，还提供了一个 ZSH 重写的函数和/或脚本 `tig-pick`.
* [timewarrior](https://github.com/svenXY/timewarrior) - 增加了对 [timewarrior](https://timewarrior.net/)，一个时间跟踪应用程序.
* [tipz](https://github.com/molovo/tipz) - 如果您有刚刚运行的命令的别名，则显示您的别名，类似于 [alias-tips](https://github.com/djui/alias-tips).
* [title](https://github.com/zpm-zsh/title) - 允许您设置终端窗口标题.
* [titles](https://github.com/jreese/zsh-titles) - 自动窗口和标签标题 [tmux](https://tmux.github.io) 和 xterm 兼容的终端.
* [tm](https://github.com/kjhaber/tm.zsh) - 简化创建新 [tmux](https://tmux.github.io) 会话、附加到现有会话、在会话之间切换以及列出活动会话.
* [tmux-auto-title](https://github.com/mbenford/zsh-tmux-auto-title) - 自动将窗口/窗格的标题设置为当前的前台命令.
* [tmux-multisession](https://github.com/nichus/zsh-tmux-multisession) - 插件 [tmux](https://tmux.github.io) 在单个服务器进程上支持多个会话.
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - 改名 [tmux](https://tmux.github.io) 窗口自动.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - 简单的插件使用 [tmux](https://tmux.github.io) 与 ZSH.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - 在正在运行的 `vim`（或 NeoVim）会话中打开来自相邻的文件 [tmux](https://tmux.github.io) 面包.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - 为`tmux`、ZSH 和 Vim/NVIM 创建统一的终端标题，模块化.
* [tmux](https://github.com/zpm-zsh/tmux) - 插件 [tmux](https://tmux.github.io).
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) - 拥有 R-EP-L 的简单 ZSH 插件 [tmux](https://tmux.github.io) 会议.
* [toggl](https://github.com/natterstefan/toggl-zsh-plugin) - 添加了“toggl-week”命令以显示跟踪的总工作时间 [toggl.com](https://toggl.com)
* [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix)  - 添加一个小部件来切换命令的前缀. 默认情况下，将 Alt+s 绑定到带有 `sudo` 前缀的命令.
* [traista](https://github.com/odgon/traista)  - 包括`git` 状态装饰和上次命令运行的颜色编码退出状态. 使用深色终端主题效果更好.
* [travis](https://github.com/denolfe/zsh-travis) - 打开当前存储库的 Travis CI 页面（如果存在）.
* [tre](https://github.com/redxtech/zsh-tre) - 使使用 [tre](https://github.com/dduan/tre#editor-aliasing) 更轻松.
* [tsm](https://github.com/RobertAudi/tsm) - 添加一个 [tmux](https://tmux.github.io) 会话管理器.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) - 为 macOS 添加工具.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 别名.
* [ugit](https://github.com/Bhupesh-V/ugit) - 允许您撤消上一次 `git` 操作.
* [undollar](https://github.com/zpm-zsh/undollar) - 从终端提示的开头去掉美元符号.
* [up (cjayross)](https://github.com/cjayross/up) - 向上浏览目录的简单方法.
* [up (peterhurford)](https://github.com/peterhurford/up.zsh) - 将向上命令添加到 `cd` 多个级别.
* [update-zsh](https://github.com/AndrewHaluza/zsh-update-plugin)  - 更新自定义 oh-my-zsh 插件. 仅适用于 oh-my-zsh 框架.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter)  - ZSH 语法高亮器的插件，如果 URL 以“良好”状态响应，则将其变为绿色，否则变为红色. 用于检查 URL 拼写错误.
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - 扩展了原始 oh-my-zsh venv 模块的功能.
* [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) - 一个包装插件 [vagrant](https://www.vagrantup.com/) 这允许从 box 目录之外调用 `vagrant` 命令. 该插件还附带了一些有助于管理多个框的额外命令，以及自定义选项卡完成.
* [vanilli.sh](https://github.com/yous/vanilli.sh) - 外壳配置的轻量级起点.
* [vapor](https://github.com/notf0und/zsh-vapor) - Laravel vapor plugin for zsh to help you to run vapor from anywhere in the project tree, with auto-completion!
* [vcshr](https://github.com/aubreypwd/zsh-plugin-vcshr) - 帮助需要使用 `vcsh` 的 vcsh 用户在 `~/.zshrc` 等中自动安装 Github 存储库.
* [velocity](https://github.com/rahulsalvi/velocity-python) - ZSH 和基于电力线的主题元素 [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) - 一种超轻量级的克隆 [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) ; 它非常希望您使用 [pyenv](https://github.com/pyenv/pyenv) （虽然你没有*有*），并且因为它基于 [`venv` module](https://docs.python.org/3/library/venv.html), (creation) 仅适用于 python &gt;= 3.3.
* [venv-wrapper](https://github.com/glostis/venv-wrapper) - 提供 ZSH 功能以使用 `venv` 简化虚拟环境的管理.
* [vi-increment](https://github.com/zsh-vi-more/vi-increment) - 添加类似`vim` 的递增/递减操作.
* [vi-mode (jeffreytse)](https://github.com/jeffreytse/zsh-vi-mode) - 适用于 ZSH 的更好、更友好的 vi(vim) 模式插件.
* [vi-mode (nyquase)](https://github.com/Nyquase/vi-mode) 添加额外的类似 vi 的功能.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - 向 ZSH 添加更多类似 `vi` 的功能.
* [vi-motions](https://github.com/zsh-vi-more/vi-motions) - 添加新的动作和文本对象，包括带引号/带括号的文本和命令.
* [vi-quote](https://github.com/zsh-vi-more/vi-quote) - 添加引用或取消引用动作的操作.
* [viexchange](https://github.com/okapia/zsh-viexchange) - 一个 `vi` 模式插件，用于在缓冲区中的两个位置之间轻松交换文本，如 vim-exchange.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) - 友好的 `vi` 模式绑定，添加基本 Emacs 键、增量搜索、模式指示器等.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - 允许您执行 `vim filename:123` 以在特定行上使用光标打开文件.
* [vimman](https://github.com/yonchu/vimman) - 在 ZSH 中查看 `vim` 插件手册（帮助），如 `man`.
* [vimto](https://github.com/laurenkt/zsh-vimto) - 改进了 ZSH `vi` 模式 (bindkey -v) 插件.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - 修改过的用于 oh-my-zsh 的 virtualenv ZSH 插件.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt)  - 来自上游的 virtualenv 插件的一个分支. 添加对在 oh-my-zsh 主题中自定义 virtualenv 提示的支持.
* [virtualz](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) 经理受 Adam Brenecki 的启发 [Virtualfish](https://github.com/adambrenecki/virtualfish) 为了 [Fish shell](http://fishshell.com/), 替换 virtualenvwrapper.
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - 一个 oh-my-zsh 插件 [virtuozzo](https://docs.virtuozzo.com/master/index.html) 裸机虚拟化系统.
* [visit](https://github.com/justinpchang/visit) - 用于更快导航的自定义插件.
* [volta (cowboyd)](https://github.com/cowboyd/zsh-volta) - 无缝安装和配置 [Volta](https://volta.sh) NodeJS 工具链管理器.
* [volta](https://github.com/ri7nz/zsh-volta) - 安装和加载 [ Volta: JS Toolchains as Code](https://github.com/volta-cli/volta).
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - 一个 oh-my-zsh 插件来控制 [VOX](https://vox.rocks/)，一款适用于 macOS 的轻量级全功能音频播放器，可以播放多种格式，包括 FLAC 和 Ogg Vorbis.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) - macOS 上的 Visual Studio Code 插件.
* [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) - 简单的插件，可以轻松地跨系统打开 VS 代码.
* [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) - 插件 [Visual Studio Code](https://code.visualstudio.com/).
* [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) - 跟踪多少 [time](https://wakatime.com/) 你已经在你的终端中度过了. 有每个项目的统计数据.
* [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) - ZSH 中命令的自动时间跟踪使用 [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - 配置着色 [grc](https://github.com/garabik/grc).
* [watch](https://github.com/enrico9034/zsh-watch-plugin) - 通过按“CTRL + W”轻松地为当前或以前的命令添加 watch 前缀.
* [watson.zsh](https://github.com/bcho/Watson.zsh) - 一个插件 [watson](https://github.com/TailorDev/Watson) 时间管理系统.
* [wd](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
* [web-search](https://github.com/sinetoami/web-search) - 添加命令以直接从 CLI 运行 bing、google、yahoo 和duckduckgo 搜索.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - 使用`git blame`突出显示文件中最后更改特定行的位置.
* [windows-title](https://github.com/mdarocha/zsh-windows-title/issues) - 使用当前目录和上次运行的命令动态更新终端窗口标题.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) - 用于在项目之间跳转的简单实用程序.
* [worktree](https://github.com/jspears/worktree) - 添加包装`git worktree`的函数.
* [xxh-plugin-zsh-zshrc](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) - 插件 [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) 将您的“~/.zshrc”复制到远程主机并使用 [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh).
* [yadm](https://github.com/juanrgon/yadm-zsh) - 如果本地 yadm 配置发生更改，则显示警告.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - 如果 `pipenv` 检测到存在一个目录，则自动激活目录的 pip 环境.
* [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez 的 oh-my-zsh 的 Yeoman 插件，兼容 ≥1.0 的 yeoman 版本（包括选项和命令自动完成）.
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH 插件，提醒您使用您定义的那些别名.
* [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) - 添加 `yt` 别名以从 YouTube 下载视频.
* [youtube-dl](https://github.com/joow/youtube-dl) - 简单的插件 [youtube-dl](https://youtube-dl.org/).
* [yup](https://github.com/redxtech/zsh-yup) - 添加辅助函数以升级yarn/npm 项目中的所有依赖项.
* [z-a-bin-gem-node](https://github.com/zinit-zsh/z-a-bin-gem-node) - [Zinit](https://github.com/zdharma/zinit) 在不改变 $PATH 的情况下公开二进制文件的扩展，安装 Ruby gems 和 Node 模块并轻松公开它们的二进制文件，并在更新相关插件或代码片段时更新 gems 和模块.
* [z-a-man](https://github.com/zinit-zsh/z-a-man) - [Zinit](https://github.com/zdharma/zinit) 为所有插件和片段生成手册页的扩展.
* [z-a-meta-plugins](https://github.com/zinit-zsh/z-a-meta-plugins) - 安装带有单个标签的插件组（[Zinit](https://github.com/zdharma/zinit) 只要）.
* [z-a-patch-dl](https://github.com/zinit-zsh/z-a-patch-dl) - [Zinit](https://github.com/zdharma/zinit) 通过提供的`dl&#39;&#39;`和`patch&#39;&#39;`ices下载文件和应用补丁的扩展.
* [z-a-rust](https://github.com/zinit-zsh/z-a-rust) - [Zinit](https://github.com/zdharma/zinit) 在插件目录中安装 rust 和 cargo 包的扩展.
* [z-a-submods](https://github.com/zinit-zsh/z-a-submods) - [Zinit](https://github.com/zdharma/zinit) 扩展允许在插件或片段中安装和管理额外的子模块.
* [z-a-test](https://github.com/zinit-zsh/z-a-test) - [Zinit](https://github.com/zdharma/zinit) 在安装和更新插件或代码片段后运行测试的扩展（例如通过`make test`）——如果它找到了其中的任何一个.
* [z-a-unscope](https://github.com/zinit-zsh/z-a-unscope) - 允许安装插件 [Zinit](https://github.com/zdharma/zinit) 无需通过查询 Github API 指定用户名.
* [z.lua](https://github.com/skywind3000/z.lua)  - 一个命令行工具，可帮助您通过学习习惯来更快地导航. 替代方案 [z.sh](https://github.com/rupa/z) 具有 Windows 和 posix shell 支持和各种改进. 比 fasd 和 autojump 快 10 倍，比 fasd 和 autojump 快 3 倍 [z.sh](https://github.com/rupa/z).
* [zabb](https://github.com/Mellbourn/zabb) - `zabb` 是一个命令，它试图找出一个目录可用的最短易记缩写 [z](https://github.com/ajeetdsouza/zoxide) 明确跳转到该目录.
* [zaw](https://github.com/zsh-users/zaw) - ZSH 之类的东西.el 小部件. 
* [zce](https://github.com/hchbaw/zce.zsh) - Vim 的 EasyMotion / Emacs 的 ZSH ace-jump-mode.
* [zcolors](https://github.com/marlonrichert/zcolors) - 使用您的 `$LS_COLORS` 为 Git 和您的 Zsh 提示、完成和 [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [zconvey](https://github.com/zdharma/zconvey) - 添加了向其他 ZSH 会话发送命令的功能，例如，您可以在所有活动的 Z shell 会话上使用它来`cd $PWD`.
* [zed](https://github.com/eendroroy/zed-zsh) - 一个简单的包装器 [z](https://github.com/rupa/z) 通过 ZSH 插件安装它.
* [zeit](https://github.com/zeit/zeit.zsh-theme) - 针对深色背景进行了优化，包括`git` 状态信息.
* [zeno](https://github.com/yuki-yano/zeno.zsh) - 模糊补全和实用插件由 [Deno](https://deno.land/).
* [zero](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details.
* [zflai](https://github.com/zdharma/zflai) - ZSH 的快速日志记录框架.
* [zfzf](https://github.com/b0o/zfzf) - ZSH 的 fzf 驱动的文件选择器，可让您快速浏览目录层次结构.
* [zgdbm](https://github.com/zdharma/zgdbm) - 添加 GDBM 作为插件.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - 在所有加载完成后使 compinit 仅运行一次 [zgen](https://github.com/tarjoilija/zgen).
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) - zimfw 的自定义附加功能，打包到 zimfw 插件中.
* [zinfo_line](https://github.com/kmhjs/zinfo_line) - 为 ZSH 主题提供更多信息.
* [zinit-console](https://github.com/zinit-zsh/zinit-console) – 半图形（诅咒）控制台 [zinit](#zinit) 插件管理器.
* [zinsults](https://github.com/ahmubashshir/zinsults) - 如果命令失败，则打印侮辱.
* [zjump](https://github.com/qoomon/zjump)  - 简化 ZSH 目录导航； 跳转到已经访问过的父文件夹或子文件夹.
* [zlong_alert](https://github.com/kevinywlui/zlong_alert.zsh) - 当一个需要很长时间（默认：15 秒）的命令完成时，使用通知发送和响铃提醒您.
* [zoxide](https://github.com/ajeetdsouza/zoxide) - 学习您的习惯的“cd”的快速替代品.
* [zredis](https://github.com/zdharma/zredis)  - 添加 Redis 数据库支持，使用 `database_key` &lt;-&gt; `shell_variable` 绑定. 支持所有数据类型.
* [zsh-in-docker](https://github.com/deluan/zsh-in-docker) - Automates ZSH + Oh-My-ZSH installation into development containers. Works with Alpine, Ubuntu, Debian, CentOS or Amazon Linux.
* [zsh-not-vim](https://github.com/redxtech/zsh-not-vim) - 提供一个功能，自动羞辱用户忘记他们不在 vim 中.
* [zsh-z (agkozak)](https://github.com/agkozak/zsh-z)  - 快速跳转到您“经常”访问的目录.  `z.sh` 的原生 ZSH 端口 - 没有 `awk`、`sed`、`sort` 或 `date`.
* [zsh-z (ptavares)](https://github.com/ptavares/zsh-z) - 安装和加载 [z](https://github.com/rupa/z.git).
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - Bashmarks 的一个端口（由 Todd Werth），一个简单的命令行书签插件，用于 oh-my-zsh.
* [zshrc](https://github.com/freak2geek/zshrc) - 从您的项目范围加载本地`.zshrc` 文件.
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - 用于在 Arch Linux 上拍摄 ZFS 前/后升级快照的插件.
* [zsnapshot](https://github.com/psprint/zsnapshot) - 添加命令将当前 ZSH 状态转储到文件中，以便以后通过获取快照文件进行恢复.
* [zui](https://github.com/zdharma/zui/) - ZSH 用户界面库——使用 ZSH 进行类似 CGI+DHTML 的快速 TUI 应用程序开发.

## Completions

这些插件在不添加额外功能或别名的情况下添加选项卡完成.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - 扩展 ZSH 的 \_urls 补全，允许它从 html 页面补全 url.
* [aliyun](https://github.com/thuandt/zsh-aliyun) - 添加完成 [Aliyun CLI](https://github.com/aliyun/aliyun-cli).
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - 完成 viasite-ansible/ansible-server.
* [antibody-completion](https://github.com/sinetoami/antibody-completion) - 此插件提供完成 [Antibody](https://github.com/getantibody/antibody) 插件管理器.
* [appspec](https://github.com/perlpunk/App-AppSpec-p5) - 根据 YAML 规范为 Bash 和 ZSH 生成补全
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - autopkg 的完成.
* [aws-completions](https://github.com/eastokes/aws-plugin-zsh) - 添加对 `awscli` 的完成支持以管理 AWS 配置文件/区域并在提示中显示它们.
* [aws_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) - 为 aws_manager CLI 添加完成.
* [bash-completions-fallback](https://github.com/3v1n0/zsh-bash-completions-fallback) - 当没有本地 ZSH 可用时，支持命令的 `bash` 补全.
* [batect](https://github.com/batect/batect-zsh-completion/) - 添加选项卡完成 [batect](https://batect.dev/) 构建系统.
* [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) - 为berkshelf 添加选项卡完成.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - 更好地完成`npm` 选项卡.
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - 添加 BOSH 自动完成功能.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) - 自制服务的完成插件.
* [buidler](https://github.com/gonzalobellino/buidler-zsh) - 为 NomicLabs Buidler 工具添加完成和有用的别名 [buidler.dev](https://buidler.dev).
* [bw](https://github.com/CupricReki/zsh-bw-completion) - 添加完成 [Bitwarden](https://bitwarden.com/).
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - 为 cabal 添加选项卡完成.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - 为 cabal 添加自动完成功能.
* [carapace](https://github.com/rsteube/carapace)  - Bash、Elvish、Fish、Oil、Powershell、Xonsh 和 ZSH 的完成生成器. 注意 - 不是动态的，您必须显式运行它才能为命令生成完成.
* [cargo](https://github.com/MenkeTechnologies/zsh-cargo-completion) - 原始 OMZ 货物完成的所有功能，通过 `cargo add` 中的 `cargo search` 额外支持远程板条箱.
* [carthage](https://github.com/squarefrog/zsh-carthage) - 提供完成和别名使用 [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) - 为所有人添加自动完成功能 [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) 命令.
* [cod](https://github.com/dim-an/cod) - bash/fish/ZSH 的完成恶魔，当它看到您使用 `--help` 运行某些东西时，它会即时创建完成功能.
* [codeception](https://github.com/shengyou/codeception-zsh-plugin) - 为 Codeception 测试框架添加命令完成.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - 显示 git 信息，是否通过 `ssh` 登录，最后一个命令的返回码.
* [comonicon](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) - 选项卡完成 [comonicon](https://github.com/Roger-luo/Comonicon.jl).
* [completions](https://github.com/zsh-users/zsh-completions) - ZSH 的额外补全集合.
* [conda](https://github.com/esc/conda-zsh-completion) - conda 的 ZSH 选项卡完成.
* [cpan](https://github.com/MenkeTechnologies/zsh-cpan-completion)  - 添加`cpan安装词<tab> ` 和 `cpanm 安装<tab> ` 完成远程 CPAN 包名称.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - 选项卡完成 [ctop](https://github.com/bcicen/ctop).
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - 自动为 DBIx::Class::Migration 的脚本和 Dancer 设置环境变量.
* [docker (chr-fritz)](https://github.com/chr-fritz/docker-completion.zshplugin) - 直接从 **Docker for Mac** 加载 `docker` ZSH 选项卡完成.
* [docker (felixr)](https://github.com/felixr/docker-zsh-completion) - 为“docker”添加选项卡完成.
* [docker (greymd)](https://github.com/greymd/docker-zsh-completion) - 为 `docker` 和 `docker-compose` 添加选项卡补全.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - 命令完成 [docker-enter](https://github.com/jpetazzo/nsenter).
* [dotnet](https://github.com/MenkeTechnologies/zsh-dotnet-completion) - Dotnet 选项卡完成.
* [dropbox](https://github.com/zpm-zsh/dropbox) - Zsh 的 dropbox 插件，提供 `dropbox-cli` 和 `dropbox-uploader` 命令.
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - ZSH 的 Drush 自动完成功能很棒.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - 一个 ZSH 插件 [duell](https://github.com/gameduell/duell).
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - 添加 etcdctl 选项卡完成.
* [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) - 定义了一个名为 extract 的函数，用于提取您传递给它的存档文件，并支持多种存档文件类型.
* [extract (thetic)](https://github.com/thetic/extract) - oh-my-zsh 提取插件的分支.
* [flowr](https://github.com/oubasan/flowr) - 完成支持 [git-flow](http://github.com/nvie/gitflow).
* [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - 为所有人添加自动完成选项 [Concourse CLI](https://www.concourse.ci/fly-cli.html) 命令.
* [fzf-gcloud](https://github.com/mbhynes/fzf-gcloud) - 模糊完成以导航和预览所有 Google Cloud SDK `gcloud` CLI 命令
* [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) - 使用 GNU Readline 为 ZSH、bash 和应用程序添加选项卡完成功能.
* [fzf-zsh-completions](https://github.com/chitoku-k/fzf-zsh-completions) - 模糊完成 [fzf](https://github.com/junegunn/fzf) 和 [ZSH](https://www.zsh.org/) 可以由默认为`**`的触发序列触发.
* [gcloud](https://github.com/littleq0903/gcloud-zsh-completion) - 为 Google Cloud SDK 添加补全.
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - 为缺乏上游补全脚本的各种 Gentoo 工具提供 ZSH 补全支持.
* [git-annex](https://github.com/Schnouki/git-annex-zsh-completion) - 允许大多数 git-annex 命令的选项卡完成.
* [git-flow](https://github.com/bobthecow/git-flow-completion) - ZSH 完成支持 [git-flow](http://github.com/nvie/gitflow).
* [gitlab-runner](https://github.com/pseyfert/zsh-gitlab-runner-completion) - gitlab-ci-multi-runner 的 ZSH 完成.
* [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) - 对 gradle 的 Bash 和 ZSH 完成支持.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - ZSH 完成对 gradle 的支持.
* [grid5000](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 插件 - 添加主题、自动完成.
* [gulp (akoenig)](https://github.com/akoenig/gulp.plugin.zsh) - 在 Z-Shell (ZSH) 中自动完成您的 gulp.js 任务.
* [gulp (srijanshetty)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - gulp 的自动完成.
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) - 完成 [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haskell](https://github.com/coot/zsh-haskell) - 为 `cabal`、`ghc` 和 `ghc-pkgs` 命令添加补全.
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) - 完成haxelib.
* [helmfile](https://github.com/Downager/zsh-helmfile) - 为 `helm` 添加自动完成功能.
* [inspr](https://github.com/ptcar2009/insprzsh) - 完成 [inspr](https://github.com/inspr/inspr)
* [ipfs](https://github.com/hellounicorn/zsh-ipfs) - 完成 [Interplanetary File System](https://ipfs.io).
* [joe](https://github.com/corvofeng/joe-completion) - 添加完成 [joe](https://github.com/karan/joe) gitignore 编辑器.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - jtool 的 ZSH 补全.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - 添加自动完成 [jumpstorm](https://github.com/netresearch/jumpstorm)
* [kafka](https://github.com/Dabz/kafka-zsh-completions) - Apache 完成 [kafka](https://kafka.apache.org).
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - 完成 [keybase](https://keybase.io/docs/command_line).
* [kitty](https://github.com/redxtech/zsh-kitty) - 完成 [kitty](https://sw.kovidgoyal.net/kitty/) 终端模拟器.
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - 添加选项卡完成 [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - 添加选项卡完成 [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
* [kubectl-fzf](https://github.com/bonnefoa/kubectl-fzf) - 快速而强大 [`fzf`](https://github.com/junegunn/fzf)- 为 `kubectl` 提供支持的自动完成功能.
* [lets](https://github.com/lets-cli/lets-zsh-plugin) - 添加自动完成 [lets](https://github.com/lets-cli/lets) cli 任务运行程序.
* [mooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - Perl 模块`MooseX::App` 的完成生成器.
* [more-completions](https://github.com/MenkeTechnologies/zsh-more-completions) - 10500 个 zsh compsys 完成！
* [msfvenom](https://github.com/Green-m/msfvenom-zsh-completion) - Metasploit 的选项卡补全.
* [mx-honey](https://github.com/mukel/mx-honey) - 提供完成 [mx](https://github.com/graalvm/mx) ; 用于开发 Graal 项目的命令行工具. 它旨在改进通常的工作流程`build unittest benchmark ...` 简化发现并提供方便的别名.
* [newman](https://github.com/selop/newman-autocomplete) - 提供自动完成 [Newman CLI](https://github.com/postmanlabs/newman).
* [nix](https://github.com/spwhitt/nix-zsh-completions) - 完成 [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/)， 和 [NixOps](https://nixos.org/nixops/).
* [node-ace](https://github.com/romch007/node-ace-zsh-completion) - 完成“节点王牌”.
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) - 为 nova 提供自动完成功能.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - 对 `npm run` 的自动完成支持.
* [nx](https://github.com/jscutlery/nx-completion)  - 完成 nx. 需要 [`jq`](https://stedolan.github.io/jq/).
* [okta](https://github.com/sirhc/okta.plugin.zsh) - 提供命令行补全 [`aws-okta`](https://github.com/segmentio/aws-okta) 命令.
* [op](https://github.com/sirhc/op.plugin.zsh) - 选项卡完成 [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) 命令行工具.
* [packer](https://github.com/wakeful/zsh-packer) - 添加选项卡完成 [packer](https://packer.io).
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc 补全插件.
* [parallels](https://github.com/benclark/parallels-zsh-plugin) - 为 Parallels 桌面添加补全.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - 方便的回购容易获得 [pass](https://www.passwordstore.org/) ZSH 的命令完成.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - pip 的自动完成插件.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - 为最常见的 pipenv 命令启用别名.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) - 完成`pipenv`.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh)  - 如果该目录中有 Pipfile，则在进入目录时自动激活 **pipenv**. 包括`pipenv` 完成.
* [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) - 为 Pivotal 添加补全 [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
* [pmy](https://github.com/relastle/pmy) - 通用上下文感知 ZSH 完成引擎由 [fzf](https://github.com/junegunn/fzf).
* [quickjump](https://github.com/fikovnik/zsh-quickjump) - 添加选项卡完成支持 [skim](https://github.com/lotabout/skim) 对于最近使用的文件和目录 [fasd](https://github.com/whjvenyl/fasd).
* [racket completion](https://github.com/racket/shell-completion) - 完成 [Racket](http://racket-lang.org).
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - 为 rakefile 目标添加快速选项卡完成.
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) - 为 Rancher CLI 添加补全.
* [razor_plugin](https://github.com/dalang/oh-my-zsh_razor_plugin) - 提供自动完成 [Razor](https://github.com/puppetlabs/Razor).
* [rustup](https://github.com/pkulev/zsh-rustup-completion) - Rustup 的选项卡完成.
* [s3cmd](https://github.com/FFKL/s3cmd-zsh-plugin) - 添加选项卡完成 [s3cmd](https://s3tools.org/s3cmd).
* [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion)  - Salesforce CLI 的 ZSH 命令完成. 需要 [jq](https://stedolan.github.io/jq/).
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) - sfdx 的自动完成插件.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - 添加自动完成 [spring-boot](http://projects.spring.io/spring-boot/) 命令.
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - 管理`ssh-agent`.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - 自动启动 `ssh-agent` 以设置和加载您想要的用于 `ssh` 连接的凭据.
* [ssh](https://github.com/zpm-zsh/ssh) - 为`ssh`添加主机完成.
* [startify](https://github.com/zdharma/zsh-startify) - 用于 ZSH 的类似 vim-startify 的插件.
* [surf](https://github.com/beardcoder/surf.plugin.zsh) - 添加冲浪完成.
* [symphony (TheGrowingPlant)](https://github.com/TheGrowingPlant/symfony.plugin.zsh) - Symfony 3 和 4 命令的自动完成.
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - 添加完成 [Test Kitchen](https://github.com/test-kitchen/test-kitchen)).
* [tinygo](https://github.com/sago35/tinygo-autocmpl) - 为 tinygo 添加选项卡补全.
* [tmux pane words](https://gist.github.com/blueyed/6856354) - 键绑定来完成你的单词 [tmux](https://tmux.github.io) 面包.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - 添加自动完成 [tugboat](https://github.com/petems/tugboat) 命令.
* [umake](https://github.com/zlsun/umake) - 标记了 Ubuntu 的选项卡完成.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - 提供自动完成功能 [vertx](https://vertx.io/) 命令.
* [web-open](https://github.com/AndrewHaluza/zsh-web-open)  - 添加别名以打开网页. 仅适用于 Ubuntu 20.
* [yabai](https://github.com/Amar1729/yabai-zsh-completions) - 为 macOS 添加补全 [yabai](https://github.com/koekeishiya/yabai/) 平铺窗口管理器.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - 为“纱线添加”、“纱线移除”、“纱线升级”、“纱线原因”和“纱线运行”添加自动完成功能.

## Themes

如果您正在使用 [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. 如果您正在使用 [zgen](https://github.com/tarjoilija/zgen)，使用 `zgen load githubuser/reponame` 将它们添加到你的 `init.zsh`.

* [000](https://github.com/Abid-Ahmad/oh-my-zsh-000-theme) - 带有用户名、主机名、完整路径、返回状态和`git` 装饰的多行提示.
* [0i0](https://github.com/0i0/0i0.zsh-theme) - 针对暗终端窗口进行了优化，使用 nerdfont `git` 状态装饰.
* [14degree](https://github.com/saims0n/14degree-zsh-theme/) - 包括`git`、`virtualenv` 和`rvm` 状态装饰.
* [4den](https://github.com/RunThem/zsh-theme-4den)  - 极简主义者. 包括 `git` 和 `hg` 状态装饰.
* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - 基于索林主题.
* [abbr (theme)](https://github.com/PhilsLab/abbr-zsh-theme)  - 显示当前目录路径的缩写版本，显示 Python virtualenv、Rust 版本、`git` 状态和最后一个命令的退出代码. 默认情况下在深色背景上效果很好，但可以轻松自定义颜色.
* [absolute](https://github.com/NelsonBrandao/absolute) - 非常干净的主题，带有 git 状态、节点版本和最后一个命令的退出代码.
* [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) - 包括 `git` 状态修饰、AWS 配置文件名称、Azure 服务主体名称、kubernetes 上下文、terraform 工作区、命令状态和当前工作目录.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS 主题，需要与电力线兼容的字体.
* [af-magic-dynamic](https://github.com/rslavin/af-magic-dynamic) - 修改版本 [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) 具有动态路径缩短功能.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - 修改版 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 中的主题.
* [aftermath](https://github.com/schanur/aftermath) - 在您在 shell 中运行的每个命令之后获得一个不错的摘要行.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) - Based on [agnoster](https://gist.github.com/3712874) 主题包含在 [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) . 显示有关 `git` 状态的详细信息.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt)  - 使用三种异步方法来保持 ZSH 提示响应，同时显示 `git` 状态和 SSH 连接、退出代码和 `vi` 模式的指示器，以及缩写的 `PROMPT_DIRTRIM` 样式的路径. 非常可定制. 即使在 Cygwin 和 MSYS2 上也是异步的.
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - 日晒 [Agnoster](https://gist.github.com/agnoster/3712874) 带有 `git` 状态信息的变体. 需要 unicode 字体并且最适合使用 [solarized](https://github.com/altercation/solarized) 终端.
* [agnoster-fseguin](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) 带有正确提示的变体.
* [agnoster-gentoo](https://github.com/r7l/agnoster-gentoo-zsh-theme) - Gentoo 风味的版本 [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme) 包括 user@hostname 和 `git` 状态装饰. 使用 unicode 字体效果更好.
* [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) - 优化 [solarized](https://ethanschoonover.com/solarized/) 配色方案，`git` 或其他 VCS 工具，以及兼容 unicode 的字体. 包括上次命令运行的状态、user@hostname、`git` 状态修饰、工作目录、是否以 root 身份运行、后台作业是否正在运行等信息.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有右键提示的变体.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 优化使用的变体 [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) 终端配色方案. 包括 `git` 状态.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) 变体，包括电池和在线状态.
* [agnoster-repopath](https://github.com/ivanfurlan/agnoster-repopath-theme) - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [Passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) themes. Includes `git` 和 `mercurial` status, current time 和 time the last comm和 took decorations in the prompt.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 添加了时间戳和换行符的变体.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - Based on [Powerline](https://github.com/Lokaltog/vim-powerline) 和 [Agnoster](https://gist.github.com/agnoster/3712874) themes 和 inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnoster](https://gist.github.com/agnoster/3712874)  - 针对solarized 终端配色方案进行了优化，显示`git` 装饰、user@host、工作目录、上一个命令的退出状态以及您是否以root 权限运行. 需要与电力线兼容的字体.
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - Based on [Agnoster](https://gist.github.com/agnoster/3712874), 显示电池寿命、日期和时间、`git` 状态、当前目录以及用户和主机信息.
* [akzsh](https://github.com/awkimball/akzsh) - 最适合深色终端主题，包括`git` 装饰.
* [alarangeiras](https://github.com/alarangeiras/alarangeiras-zsh-theme/) - 带有 `git` 状态装饰的简约主题.
* [ale](https://github.com/alepimentel/ale-zsh)  - 基于fino主题. 包括 `git`、`virtualenv` 和 `node` 状态装饰.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) - 显示了 `git` 状态的极简 ZSH 主题.
* [alien](https://github.com/eendroroy/alien)  - Powerline-esque ZSH 主题，显示`git` 装饰和最后一个命令的退出代码. 比许多其他提示更快，因为它在后台进程中异步确定 `git` 装饰.
* [alpharized](https://github.com/NicoSantangelo/Alpharized) - 优化使用 [solarized](http://ethanschoonover.com/solarized) 暗终端. 这是修改版 [avit theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme).
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - 优雅舒适的阅读主题基于 [Agnoster](https://gist.github.com/agnoster/3712874).
* [andy](https://github.com/andymcguinness/andys-theme) - 修改 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 具有更好的`git` 支持的主题.
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) - 在右侧提示中显示 `git` 信息.
* [antsy](https://github.com/jeffmhubbard/antsy-zsh-theme) - 显示 `git` 分支和状态装饰、virtualenv、退出状态、作业计数和 vi 模式指示器.
* [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) - 显示 `git` 装饰、用户、主机、是否为 root、活动的 Python 虚拟环境、当前的 Ruby 解释器、最后一个命令的视觉和数字状态、电源管理状态以及时间和日期.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme)  - 没有视觉噪音的简约主题. 只显示必要的信息：当前用户、主机名、工作目录、`git` 分支（如果存在）. 黑色和白色端子看起来都很棒.
* [aplos](https://github.com/sunquan1991/aplos) - 带有工作目录、`git` 本地信息、`git` 远程信息、时间和退出代码的最小 ZSH 提示.
* [apollo](https://github.com/mjrafferty/apollo-zsh-theme) - 一个高度可定制、兼容和高性能的 ZSH 主题，它使用模块来启用功能.
* [apple](https://github.com/bjrowlett2/apple-zsh-theme) - 带有 `git` 状态装饰的简约主题.
* [arael](https://github.com/aknackd/zsh-themes) - 叉 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [archie](https://github.com/dcavalcante/archie)  - Arch Linux 启发了 ZSH 主题. 基于 [norm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) 主题.
* [arity](https://github.com/hybras/Arity-Zsh-Theme)  - Arity 是一个简单的主题，旨在提高可读性并使概览一目了然. 包括路径和`git` 装饰.
* [aronhoyer](https://github.com/aronhoyer/zsh-theme) - 带有右侧“git”状态装饰的极简主义主题.
* [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - 带有 `git` 装饰的最小 ZSH 主题.
* [asciigit](https://github.com/cemsbr/asciigit) - 针对不想使用带有额外字形的字体的`git` 用户的仅 ASCII 主题.
* [asq](https://github.com/AugustoQueiroz/asq-theme) - Based on [theunraveler](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#theunraveler).
* [astral](https://github.com/xwmx/astral)  - 带有禅宗模式的深色背景主题. 适用于 zsh-users [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) 插入.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - 基于 [`ys`](http://blog.ysmood.org/my-ys-terminal-theme/) 和 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 主题.
* [async](https://github.com/mje-nz/zsh-themes) - 显示当前目录、`git` 状态、上一个命令的返回值（如果有错误代码）、后台作业的数量、长时间运行的命令的执行时间、当前的 python virtualenv.
* [aterminal](https://github.com/guiferpa/aterminal) - 在提示中显示 Nodejs、NPM、Docker、Go、Python、Elixir 和 Ruby 信息.
* [avil](https://github.com/avil13/avil-zsh-theme) - 带有`git` 装饰的极简主义主题.
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) - 基于 oh-my-zsh [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) 主题，变化很小.
* [avit-mod](https://github.com/zlsun/avit-mod) - oh-my-zsh 的修改版 [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) 主题.
* [banana](https://github.com/sorcererxw/banana-zsh-theme) - 包括`git` 状态装饰和当前目录.
* [bandit](https://github.com/Holger-Will/zsh_bandit) - 另一个电力线变体.
* [bar (anki-code)](https://github.com/anki-code/bar-theme) - 极简主义的设置 [p10k](https://github.com/romkatv/powerlevel10k).
* [bar (xp-bar)](https://github.com/xp-bar/zsh-bar-theme) - 包括用户名、主机、密码、`git` 状态装饰和 3 小时提醒喝水.
* [bash](https://github.com/starseekist/bash-zsh-theme) - 看起来像默认的 `bash` 提示.
* [bashi](https://github.com/eli-oat/bashi) - 针对 Ahmet Sülek 的优化 [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) 主题和 Pasquale D&#39;Silva&#39;s [Saturn Terminal](https://github.com/psql/saturn-colors) 主题.
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - 修改版本 [gitster](https://github.com/zimfw/gitster) 主题为 [ZIM](https://github.com/zimfw/zimfw).
* [bearable](https://github.com/JanmanX/bearable-zsh) - 适用于深色终端背景.
* [bedbugs](https://github.com/justino/zsh-theme-bedbugs) - 灵感来自 [Agnoster](https://gist.github.com/agnoster/3712874)，这个多行提示包括 `git` 状态信息、后台作业计数、工作目录、用户和主机名、Python virtualenv（如果存在）、最后一个命令的彩色返回值和 root/用户 sigil.
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - 灵感来自 [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme)，但带有啤酒图标.
* [bender](https://github.com/specious/bender) - 带有 git 集成的花式两行提示.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) 带有 Unicode 符号的变体.
* [biradate](https://github.com/vemonet/zsh-theme-biradate) - 基于 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 主题，但在提示中显示日期而不是用户名.
* [birame](https://github.com/maniat1k/birame) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [birav2](https://github.com/shahid64/birav2-theme) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) . 包括 `git`、`rvm` 和 `virtualenv` 状态装饰.
* [bklyn](https://github.com/gporrata/bklyn-zsh) - 变体 [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) 应用了自定义.
* [black-Void](https://github.com/black7375/BlaCk-Void-Zsh) - 包括帐户信息、root 用户、使用 ssh、目录分配、写入权限、vcs 信息装饰.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) - 另一个`git`-aware 主题.
* [blazux](https://github.com/blazux/omz-theme) - 包括`git` 状态装饰和最后一个命令退出状态的笑脸/悲伤表情指示器.
* [blinks (max13ft)](https://github.com/max13fr/blinks.zsh-theme) - 为 oh-my-zsh 添加了 mercurial 支持 [blink](https://github.com/max13fr/blinks.zsh-theme) 主题.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) - 基于现有主题 [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme).
* [bliss](https://github.com/joshjon/bliss-zsh)  - 一个精致的主题，可以在不压倒您的工作空间的情况下注入色彩. 设计用于与 [bliss iTerm](https://github.com/joshjon/bliss-iterm) 配色方案和 [bliss dircolors](https://github.com/joshjon/bliss-dircolors) . 包括 `git` 状态装饰.
* [blokkzh](https://github.com/KorvinSilver/blokkzh) - 基于内置 oh-my-zsh 的主题 [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 主题. 需要支持 unicode 的字体.
* [blox](https://github.com/yardnsm/blox-zsh-theme)  - 最小且快速的 ZSH 主题，可显示您的需求. 它由块组成：每个块都显示在一对\[方括号\]内，您可以通过简单地创建一个函数来添加块.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - 最小主题，显示`git`信息.
* [bluelines](https://github.com/apbarrero/bluelines) - 清晰的蓝色主题.
* [bogo](https://github.com/cubasepp/zsh-bogo-theme) - 灵感来自 [zeta](https://github.com/skylerlee/zeta-zsh-theme) . 包括 `git` 和 ruby​​ 版本的装饰.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - 多行主题，最适合深色背景.
* [bougenville](https://github.com/bougenville/zsh-theme) - 变体 [dallas](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dallas.zsh-theme).
* [bronze](https://github.com/reujab/bronze)  - 一个跨外壳可定制的类似电力线的提示，带有用 go 编写的图标. 需要 [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
* [brs](https://github.com/evenhold/brs-zsh-theme) - 在提示中使用“audtool”显示当前歌曲.
* [bruh](https://github.com/haze/bruh) - 包括 `git` 状态装饰.
* [brunty](https://github.com/Brunty/omz-brunty) - 布鲁蒂主题.
* [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) - Inspired by the [powerline](https://github.com/Lokaltog/vim-powerline) 和 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 主题.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF 颜色主题.
* [bubblegum](https://github.com/ice-bear-forever/bubblegum-zsh) - 极简主义的亮粉色主题，带有三角形字形和您的工作目录，仅此而已——让您拥有尽可能干净的外壳.
* [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) . 最适合搭配 [nerdfonts](https://github.com/ryanoasis/nerd-fonts).
* [bubblified (varaki)](https://github.com/varaki/bubblified-varaki.zsh-theme) - Based on [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) . 生根时改变颜色.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh)  - 灵感来自 Powerline Vim 插件. 它旨在简化，仅在相关时显示信息.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH 主题，修改为只显示时间和目录.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - 简单、干净、漂亮的主题.
* [bureau-env](https://github.com/angus-lherrou/bureau-env) - 修改 Oh-My-Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) 在 `git` 块左侧添加 Python 虚拟环境标签的主题.
* [bureau-parrot](https://github.com/BenjaminGuzman/bureau-parrot) - Based on [bureau](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme) . 包括`git` 装饰.
* [bureau](https://github.com/isqua/bureau)  - 清晰且内容丰富的两行提示. 包括为大型存储库优化的 git status.
* [buster](https://github.com/grantbuster/buster_zsh_theme)  - 与 WSL2 配合良好. 松散地基于 oh-my-zsh 的 Fox 和 Jonathan 主题.
* [cactus](https://github.com/welksonramos/cactus) - 带有 `git` 状态装饰的简约主题.
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - 糖果主题的轻型版本.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - 在提示中显示活动的 Python 版本和 `git` 装饰.
* [celestialorb](https://github.com/celestialorb/zsh-theme)  - 由@celestialorb 提供的受电力线启发的主题. 包括“git”状态装饰、Kubernetes 集群信息（如果有）、当前 AWS 配置文件和区域以及活动的 virtualenv.
* [ch4rli3](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) - 精益和简单的主题.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme)  - 基于索林. 显示 Java、Scala、Go、Node、Python 和 Ruby 的当前活动版本.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme)  - 一个小巧而美丽的 Oh-My-Zsh 主题，没有任何多余的东西. 包括 `git` 状态装饰.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) - 针对以下情况优化的 ZSH 提示 [solarized](https://github.com/altercation/solarized) 黑暗终端主题.
* [chello](https://github.com/Abdalla981/chello)  - 在深色背景上效果很好. 依赖于取决于 [autojump](https://github.com/wting/autojump), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) 和 [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [chi](https://github.com/akinjide/chi) - 针对 macOS 上的 iTerm 2 用户优化的 ZSH 主题.
* [chrisandrew.cl](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme)  - 包括`git` 装饰. 需要与电力线兼容的终端字体.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - 显示时间戳、大换行符、git 分支和状态.
* [clarity](https://github.com/nbitmage/clarity.zsh) - 专为简单性和可扩展性而设计.
* [classyTouchName](https://github.com/dylanroman03/classyTouchName) - Oh-my-zsh 主题灵感来自 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) . 在深色背景下效果更好. 包括 `git` 状态装饰.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - 带有`git`支持的最小、干净的主题.
* [clean (akz92)](https://github.com/akz92/clean) - 极简的 ZSH 主题.
* [clean (brandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - 极简主义的变体 [pure](https://github.com/sindresorhus/pure) . 纯不干净，干净不纯.
* [clean (patr1ot)](https://github.com/Patr1ot/clean.zsh-theme) - 上游的分叉 [clean](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) 添加了主机信息.
* [cleansh](https://github.com/diegoos/cleansh)  - 极简主义，包括 `git`、Ruby、node 和 Python 版本状态装饰. 使用标准字体.
* [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) - 极简主义主题，带有 `git`、nix-shell 和 virtualenv 状态装饰.
* [cloudy](https://github.com/Huvik/Cloudy) - 最小的多云 ZSH 主题.
* [clover](https://github.com/tzing/clover.zsh-theme) - 灵感来自 [zeta](https://github.com/skylerlee/zeta-zsh-theme) 和 [pure](https://github.com/sindresorhus/pure).
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - 配置文件 [cmder](http://cmder.net/) 配置为使用 ZSH 和修改后的地震模式工作 [Agnoster](https://gist.github.com/agnoster/3712874) 主题.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) - 一个与 Cmder 主题相匹配的 ZSH 主题，Cmder 是一个流行的 windows 终端模拟器.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos 为 ZSH 和 iTerm 2 设计的 Cobalt 2 主题.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) - 带有 `git` 扩展的 Cobalt 2 主题.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - 代码机器主题.
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - 灵感来自 [bashi](https://github.com/eli-oat/bashi), 在你的提示中包含一个猴子和 `git` 信息.
* [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - Based on agnoster, but has a right-prompt for vi-mode that displays `--INSERT--` and `--NORMAL--`, in a powerline look.
* [coldark](https://github.com/ArmandPhilippot/coldark-zsh-theme)  - 专为阅读舒适而设计的蓝灰色主题. 包括`git` 装饰.
* [collon](https://github.com/lambdalisue/collon.zsh)  - 带有 `git` 状态装饰、cwd、时间、主机、最后一个命令的退出状态的轻量级主题. 不需要特殊字体.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - 允许每个主机提示着色，显示 `rvm`、`virtualenv` 和 `git` 信息.
* [common](https://github.com/jackharrisonsherlock/common) - 一个简单、干净和最小的提示，显示当前工作目录、主机名、AWS 保管库角色、后台作业、当前 SHA、上一个命令的退出代码以及 `git` 分支和状态.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - 针对深色背景优化的鲜艳主题.
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) - 干净有效的 ZSH 主题，支持 git 和 npm.
* [cramin](https://github.com/FelipeCRamos/craminzsh) - 支持 github 插件的最小界面，基于 [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [cryo](https://github.com/cryocaustik/cryo-zsh-theme) - 原始 oh-my-zsh 主题的独立克隆，添加了日期和时间.
* [crème fraîche](https://github.com/koenwoortman/creme-fraiche-zsh-theme) - 最适合浅色终端背景，包括 `git` 和 `vi` 模式状态装饰.
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - 基于 Powerline Vim 插件的带有可爱表情符号的 macOS oh-my-zsh shell 主题.
* [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) - 在深色背景下效果很好，有 `git` 状态装饰.
* [cypher-ruby](https://github.com/ston1x/cypher-ruby) - 相似 [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) 但包括活动的 Ruby 版本.
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) 和 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 和 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 容器中的主题.
* [daily](https://github.com/ghlin/zsh-theme-daily) - 包括 `git` 和 `ssh` 状态装饰.
* [damino](https://github.com/njdom24/Damino-Zsh-Theme) - 带有“git”装饰的最小电力线式主题.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) - 信息丰富，最少，最重要的是，以 X 战警为主题.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - 这个版本的流行 [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) 主题已通过近乎完全的重写实现模块化和一些新功能得到增强.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - Darksoku 主题基于 [ys](http://blog.ysmood.org/my-ys-terminal-theme/) 和 [astro](https://github.com/iplaces/astro-zsh-theme) 主题.
* [dbern](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) - 包括电池状态和负载平均装饰.
* [delta (asavoy)](https://github.com/asavoy/delta-zsh-theme)  - 最小的 ZSH 主题以减少干扰. 包括一个 iTerm 颜色设置文件.
* [delta (dongri)](https://github.com/dongri/delta-zsh-theme) - 另一个带有嵌入式 `git` 状态的最小主题.
* [delta-prompt](https://github.com/cusxio/delta-prompt) - 最小的 ZSH 提示.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) - 强调终端右侧（因此得名）的主题.
* [dino](https://github.com/OdilonDamasceno/dino-zsh-theme)  - 包括 node、golang、flutter、lua、python 和 java 的装饰，还包括 `git` 装饰. 需要书呆子字体.
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - 带有自定义 LSCOLORS 和 LS_COLORS 设置文件，适用于深色和浅色终端主题.
* [diy-ys](https://github.com/aprilnops/zsh-theme) - 变体 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 没有主机名或时间.
* [dkniffin](https://github.com/dkniffin/zsh-theme) - 包括 `ruby` 版本和 `git` 状态.
* [dmx](https://github.com/domix/dmx.zsh-theme) - 针对暗终端窗口进行了优化.
* [doodleshell](https://github.com/cdodd/doodleshell-zsh-theme) - 极简主义主题，包括`git`、`terraform` 和`aws` 状态装饰.
* [dp](https://github.com/davidparsson/zsh-dp-theme) - 显示当前 git 分支的低对比度主题，如果存储库是脏的和 `$PYENV_VERSION` 的值.
* [dr4kk0nnys_v2](https://github.com/Dr4kk0nnys/Dr4kk0nnys_theme_ohmyzsh_v2/) - 适用于深色背景，包括`git` 状态装饰.
* [dracula](https://github.com/dracula/zsh) - Atom、Alfred、Chrome DevTools、iTerm 2、Sublime Text、Textmate、Terminal.app、Vim、Xcode 和 ZSH 的深色主题.
* [dragon](https://github.com/sabertazimi/dragon-zsh-theme) - 简约，包括`git` 状态信息.
* [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) 变体.
* [dtheme](https://github.com/OlukaDenis/DTheme)  - 针对使用日光化终端配色方案和 `git` 的人进行了优化. 最适合使用 unicode 字体.
* [duckster](https://github.com/ducky/duckster) - Gitster ZSH 主题的一个分支，更加新鲜.
* [ducula](https://github.com/janjoswig/Ducula)  - 灵感来自德古拉项目. 包括 `git` 状态修饰、用户名和主机名缩写、虚拟环境、当前工作目录、上一个命令的返回状态和时间.
* [dustmod](https://github.com/bmihaila/dustmod) - 源自 [dst](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) oh-my-zsh 中的主题.
* [dzhi](https://github.com/pentago/dzhi-zsh-theme) - 针对使用的人进行了优化 [Nord](https://www.nordtheme.com/) . 包括 `git` 状态装饰.
* [eckig](https://github.com/fouladi/eckig)  - 带有 utf-8 图标的极简主题. 包括 `git` 状态装饰和时钟.
* [eggshausted](https://github.com/inutano/eggshausted) - 一个`git`-aware 主题，适合那些厌倦了错误的人.
* [eleastic](https://github.com/jinseobhong/eleastic-zsh-theme) - 灵感来自 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ，针对日光化终端主题进​​行了优化，包括`git` 状态装饰. 需要与电力线兼容的字体.
* [elessar](https://github.com/fjpalacios/elessar-theme) - 基于`git`的主题 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) . 需要与电力线兼容的字体.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - 表情符号风味 [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ohmyzsh/ohmyzsh) 主题.
* [emoji](https://github.com/masaakifuruki/emoji.zsh-theme) - Based on  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh 主题，其中 `git` 提示符号替换为表情符号，以提高清晰度.
* [endless-dog](https://github.com/qwelyt/endless-dog) - 模仿 grml-zsh-config 的 oh-my-zsh 兼容主题.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - 在终端中占用大量空间.
* [eriner](https://github.com/zimfw/eriner) - 受 Powerline 启发的 Zim 叉 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 提示主题. 包括 `git` 状态装饰.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - 带有 `git` 信息的简单主题.
* [eucalyptus](https://github.com/relastle/eucalyptus) - 为极简 vi 模式用户提供的简单单行主题 [agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory 和 current path.
* [excess](https://github.com/davydovanton/excess.zsh-theme) - 简单的 ZSH 颜色主题.
* [ez-pz](https://github.com/mangosmoothie/ez-pz) - 极简主义主题，带有 `git` 状态装饰，灵感来自 [bureau](https://github.com/isqua/bureau).
* [fall](https://github.com/jottenlips/seasonal-zshthemes)  - 带有秋季图标的简约主题. 包括 `git` 状态装饰.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) - 最小的 ZSH 提示，在深色背景上效果更好.
* [fdT2K](https://github.com/FDT2k/FDT2K-theme)- Based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme), 预设包括 virtualenv, last command status, `nvm`, `docker machine` 和 `git`, `hg` 和 `bzr` 状态装饰.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme)  - 干净、简单、兼容且有意义. 在 Linux、Unix 和 Windows 上以 ANSI 颜色进行测试.
* [filthy](https://github.com/molovo/filthy) - 令人作呕的干净 ZSH 提示.
* [fish](https://github.com/Raniconduh/zshfish)  - ZSH 主题让人想起默认的鱼壳主题. 包括 `git` 状态装饰.
* [fishy-lite](https://github.com/sudorook/fishy-lite) - 原版的叉子 [fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy)  oh-my-zsh 中的主题，删除了许多无关的东西以提高加载速度. 包括可以在提示右侧启用的电池电量计和 `git` 状态显示.
* [fishy2](https://github.com/akinjide/fishy2) - ZSH 主题灵感来自 [original fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy).
* [fizzy](https://github.com/Brokenhammer72/fizzy) - 极简提示，包括 `git` 状态装饰.
* [fluent-git](https://github.com/RobertKozak/fluent-git) - 显示上次命令执行的时间、错误代码、主机名、用户名、`git` 状态、kubernetes 集群和命名空间、路径和 ssh 连接状态.
* [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) - 自定义设置 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) . 包括 `git` 状态装饰.
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - 包括上一个命令的状态、`git` 信息和当前目录.
* [frank](https://github.com/ronmackley/frank-theme)  - 弗兰克直截了当，在一行中简洁但易读地显示信息. 弗兰克坚持事实，只在重要的时候告诉你额外的事情.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - 叉 [terminal-party](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) 主题.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - 基于主题 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh 主题.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - 红色版本 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh 的主题.
* [fritz](https://github.com/fritzccc/fritz-zsh-theme)  - 在深色背景上效果很好. 包括 `git` 状态装饰.
* [frlo](https://github.com/fiorillo/frlo) - 使用您计算机的主机名提出（希望如此）独特的三色主题以显示在您的提示中，以便您一目了然地知道您登录的是哪台机器.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - 色彩缤纷的两行主题，支持 `git` 和 `svn`.
* [furio](https://github.com/hectorpalmatellez/furio-theme) - 叉子 [Cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme)  oh-my-zsh 主题. 用不同的颜色和表情符号.
* [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) - 多彩主题，在深色背景下效果更好.
* [gaia](https://github.com/gcaracuel/gaia.zsh-theme) - 最初是一个叉子 [Bureau](https://github.com/isqua/bureau) 在提示中添加新的虚拟环境信息：Kubernetess、virtualenv、rbenv 和 Java 版本. 包括 git status 集成.
* [garden](https://github.com/fecat233/garden) - 在深色终端背景下效果更好，包括 `git` 状态装饰.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto 在您需要时提示您需要的信息.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme)  - Nicola Racco 的主题. 需要 `rvm` 和 `git` 插件.
* [gbt](https://github.com/jtyr/gbt)  - Go Bullet Train 是一个非常可定制的提示构建器，其灵感来自 Bullet Train，运行速度更快. 包括许多不同状态的汽车.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - 将 oh-my-zsh gentoo 主题分解为非 omz 用户的单独存储库.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) - 将主机信息添加到 [geometry](https://github.com/geometry-zsh/geometry) 主题.
* [geometry](https://github.com/geometry-zsh/geometry) - 一个最小的 ZSH 主题，可以将任何功能添加到左侧提示或（异步）右侧提示中.
* [ghoti](https://github.com/lonr/ghoti)  - 模仿 `fish-shell` 默认提示. 包括`git` 装饰.
* [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) - 灵感来自 [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme), 包括 `git` 装饰、IP 地址、主机和路径.
* [gimbo](https://github.com/gimbo/gimbo.zsh-theme) - 一个变种 [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) 具有更多功能，一点点吸引眼球和上下文敏感的额外线条. 包括 `git` 状态修饰、历史编号、用户名/主机名上下文、目录状态、最后一个命令的状态（如果存在）以及 Python virtualenv 名称（如果存在）.
* [gimme](https://github.com/nralbrecht/gimmezsh)  - ZSH 的简单主题与`git` 集成. 灵感来自 [gitsome](https://github.com/mtully/gitsome) 主题.
* [girazz](https://github.com/mdentremont/girazz) - 对 gnzh 主题的修改，在右侧提示中添加了 `vi` 模式.
* [git-prompt (olivierverdier)](https://github.com/olivierverdier/zsh-git-prompt)  - 显示有关当前`git` 存储库的信息. 特别是分支名称、与远程分支的区别、暂存或更改的文件数量等.
* [git-prompt (woefe)](https://github.com/woefe/git-prompt.zsh) - ZSH 的快速、可定制、纯 shell、异步 Git 提示，深受 Olivier Verdier 的启发 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) 和鱼壳的“Informative VCS”提示非常相似.
* [git-simple](https://github.com/ZakharEl/git-simple-theme) - 简单的主题，包括详细的 `git` 状态装饰.
* [gitsome](https://github.com/mtully/gitsome) - 带有`git`信息的超级简单提示，针对 [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) 配色方案.
* [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) - 显示命令和`git` 状态装饰.
* [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme)  - 在 `git` 存储库中时，它显示来自 `git` 存储库根文件夹的位置. 当不在 `git` 存储库中时，它会显示相对于 home 的路径 `~`.
* [gitster (zimfw)](https://github.com/zimfw/gitster) - shashankmehta 的 Zim 叉子 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 提示主题
* [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) - 从原始分叉 [gitster](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) 主题.
* [glimmer](https://github.com/martnu/glimmer) - 包括 `git` 分支、时间和 user@host.
* [gndx](https://github.com/gndx/gndx-zsh-theme) - 包括 `git` 状态、主机名、目录和最后一个命令退出状态装饰.
* [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) - 定制 [gnzh.zsh-theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) 来自 oh-my-zsh.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) - iTerm 2 和 ZSH 的主题，包括`git` 装饰、user@host、路径和日期.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - 简单但信息丰富的主题，包括`git` 装饰和最后一个命令的返回状态.
* [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) - 极简主义，包括 `git` 状态装饰.
* [grs](https://github.com/gersontpc/zsh-theme-grs) - 包括 `git` 状态装饰、用户 ID 和工作目录.
* [gruvbox](https://github.com/sbugzu/gruvbox-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874), 使用相同的颜色 [gruvbox](https://github.com/morhetz/gruvbox) `Vim` 插件.
* [guezwhoz](https://github.com/guesswhozzz/guezwhoz-zshell) - 极简主义，包括 `git` 状态装饰.
* [guri](https://github.com/victorfsf/guri) - 一个简单快速的 Oh-My-Zsh 主题，基于 [Pure](https://github.com/sindresorhus/pure)的设计.
* [hackersaurus](https://github.com/bhilburn/hackersaurus)  - 带有 `git` 状态和最后一个命令运行的退出代码的主题嵌入在提示中. 相关 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) - 带有`git` 装饰的极简主义主题.
* [halil](https://github.com/5m0k3r/zsh-themes) - oh-my-zsh 的分叉 [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) 主题.
* [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme)  - 一个简单的主题，第一个字符是花（hana），花的汉字. 这个主题的灵感来自一个名为 DSA Hana 的键帽组. 这与 [hana atom](https://github.com/arturoalviar/hana-matcha-syntax) 主题. 包括 `git` 状态装饰.
* [handy](https://github.com/HanleyLee/Handy) - 带有 `git` 装饰的轻量级提示.
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) - 如果超过`ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`，则显示`git` 分支和状态、最后一个命令退出代码、最后一个命令执行时间.
* [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) - 基于氧化物，包括`git` 状态装饰和当前用户/主机信息.
* [haribo](https://github.com/haribo/omz-haribo-theme) - 简单的 `git` 状态 + 提示中的时间戳.
* [hcompact](https://github.com/fusion809/zsh-theme) - 显示时间、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [heart](https://github.com/gko/heart) - 浅色背景的心脏主题提示.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - 简单、严肃和干净，支持 `git` 和返回代码.
* [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - Based on [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau)，添加了 `git` 状态装饰和 `npm` 状态.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hematite](https://github.com/bigdave/hematite) - 极简主义宣传，试图仅显示在给定时间有效的状态装饰.
* [hexagon](https://github.com/diogoazevedos/hexagon) - 基于极简主义的 zsh 主题 [geometry](https://github.com/geometry-zsh/geometry).
* [hfulldate](https://github.com/fusion809/zsh-theme) - 显示时间、日期、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - 灵感来自 robbyrussell 主题 + ssh 连接状态提示.
* [hina](https://github.com/ucpr/hina) - 用 `golang` 编写，包括 `git` 状态修饰和 kubernetes 上下文.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 一个变种 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - oh-my-zsh 和 iTerm 2 的 Honukai 主题和颜色.
* [horizontal](https://github.com/nuimk/horizontal) - 带有水平分隔符的两行提示.
* [hornix](https://github.com/fusion809/zsh-theme) - 显示时间和日期、操作系统（包括 Linux 上的发行版）、目录以及是否以 root 身份运行.
* [horse-sh](https://github.com/emileswarts/horse-sh) - 一个非常小的棕色/红色 ZSH 主题.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - 简单干净，包括上次执行命令的返回码.
* [hug](https://github.com/xxninjabunnyxx/hug-zsh)  - 当你工作需要一个拥抱时. 包括 `git` 状态.
* [humbled](https://github.com/saravanabalagi/zsh-theme-humbled) - 一个干净简洁的主题，支持 `condaenv`、`virtualenv` 和 `git` 状态装饰，以粗体显示与工作目录对齐.
* [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) - 设计用于超级终端主题，包括`git` 状态装饰.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) - 为您提供您正在处理的分支和存储库状态的全面概述，而不会弄乱您的终端.
* [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX)  - 修改了 iGeek 主题. 开箱即用的 macOS，包括 `git` 状态装饰.
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - 在深色背景下效果很好.
* [ice](https://github.com/Lenart12/ice.zsh-theme) - 非常轻微的修改 [bureau](https://github.com/isqua/bureau) 主题结合 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [icicle](https://github.com/JamesConlan96/Icicle) - 包括 `git` 状态装饰，以及是否以 root 身份运行.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) - 一个超级快乐的令人敬畏的电力线风格，`git`-aware **prezto only** 主题.
* [igorsilva](https://github.com/igor9silva/zsh-theme) - 显示当前目录、自定义分隔符、当前分支、`git` 状态.
* [iguanidae](https://github.com/btd1337/iguanidae-zsh-theme) - 包括 `git`、`nvm` 和 `venv` 装饰.
* [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) - 叉 [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) 间距改进和更新的图标. 包括 `git` 状态信息.
* [imp](https://github.com/igormp/Imp) - Based on [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) 并针对深色背景进行了优化.
* [infernus](https://github.com/jshiell/infernus-zsh-theme) - 极简主题，更适合深色背景.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) - 显示“git”状态、后台作业、远程主机和其他信息的干净主题.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - 的扩展 [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) 主题使用电力线字体.
* [itg](https://github.com/itsthatguy/itg.zsh-theme) -itsthatguy 的主题.
* [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme)  - 基于精炼和 ys 主题，包括 `git` 状态装饰. 包括可选的 iterm2 配色方案.
* [jake](https://github.com/JakeHuneau/Jake.zsh-theme) - 显示时间、当前目录和 `git` 分支信息，包括分支名称和红色 + 如果分支有未推送的更改.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - 针对深色背景进行了优化，包括`git` 状态和`rvm` 状态.
* [jc](https://github.com/jclementex/jc-zsh-theme) - 对于深色终端背景，包括 `git` 状态信息.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - 松散地基于 ys 主题.
* [jerome](https://github.com/jeromescuggs/jerome-theme) - 丰富多彩的主题基于 [dieter](https://github.com/jeromescuggs/jerome-theme) 主题，但带有黄色主机名. 包括`git` 装饰.
* [jhleeeme](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) - 包括 `git` 和 python virtualenv 状态装饰、用户、密码、时间和系统名称.
* [jon](https://github.com/Jon-Schneider/jon.zsh-theme) - 一个简化 [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) 与颜色 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - 灵感来自 [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme), 包括 `git` 状态.
* [jovial](https://github.com/zthxxx/jovial) - 显示主机、用户、路径、开发环境、`git` 分支，其中 python venv 处于活动状态.
* [jpegleg](https://github.com/jpegleg/zshrc) - 类似于暗血主题，包括时间戳和`git` 装饰.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - 极简提示.
* [just-another](https://github.com/supertassu/another-theme) - 只是另一个主题，当您 sshed 到另一台机器时带有主机名.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter)  - 电力线风格的主题，带有 `git`、`svn`、`npm`、`rvm` 和网络感知. 需要电力线兼容的终端字体.
* [jyumpp](https://github.com/Jyumpp/jyumpp-zsh-theme) - Powerlevel 10K 的配置文件和安装程序.
* [kali](https://github.com/h4ck3r0/kali-theme) - 包括`git` 装饰.
* [karu](https://github.com/zaari/karu) - 极简单行 ZSH 提示.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) - 包含来自其他主题的一些功能的主题.
* [kenton](https://github.com/notnek/zsh-theme) - 针对深色背景进行了优化，包括`git` 状态信息.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) - 多彩主题，包括 iTerm 2 配色方案.
* [kgzsh](https://github.com/Kashugoyal/kgzsh) - 包括 `git` 状态装饰，适用于较暗的背景.
* [kido](https://github.com/KidoThunder/kido-zsh-theme)  - 基于`ys`和`robbyrussell`主题. 包括上次运行命令的退出代码、python virtualenv 和 VCS 状态的装饰器.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - 基于 Fishy 主题，但显示完整路径而不是缩写目录，并且仅在 `ssh` 会话和 docker 容器中显示 user@machine.
* [kiss](https://github.com/rileytwo/kiss)  - oh-my-zsh、VSCode、iTerm2、Neovim 和 RStudio 的简单主题. 包括 `git` 状态装饰.
* [kketcham](https://github.com/prototype27/kketcham) - “git”信息上带有漂亮颜色的主题.
* [klassiker](https://github.com/mrdotx/zsh-theme) - 带有`git` 装饰的极简主题.
* [klendathu](https://github.com/kegonomics/klendathu) - 使用电力线图标.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme)  - 最适合深色背景. 包括 `git` 状态装饰.
* [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - 为黑暗终端设计的两行主题，具有`git` 装饰.
* [krak3n](https://github.com/krak3n/zsh-theme) - 显示 golang 版本和当前的 `git` 分支.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) - ZSH 的黑暗主题.
* [kube](https://github.com/tigerjz32/kube-zsh-theme) - Based on [macos-terminal](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal) , 包括 `kubectl` 上下文. 有时间、目录和 `git` 状态装饰.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme)  - 针对日晒终端优化的 Agnoster 叉. 需要与电力线兼容的字体.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) - 带有 `git` 和 `hg` 状态信息的彩色主题，能够为主机名添加特定于主机的颜色.
* [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme)  - 一个简单的主题，第一个字符是九（kyuu），数字 9.主色是带有洋红色口音的蓝色. 包括 `git` 状态装饰.
* [lagune](https://github.com/noplay/lagune) - A minimal ZSH theme.
* [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) - 灵感来自 robbyrussell [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) 主题. 包括 `git` 状态装饰.
* [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) - 针对使用 unicode 兼容字体和终端应用程序的 `git` 用户优化的 ZSH 主题.
* [lambda-blazinggit](https://github.com/zalefin/lambda-blazinggit)  - 包括快速、详细的“git”信息. 需要书呆子字体和 [gitstatus](https://github.com/romkatv/gitstatus) 插入.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - 包含 `git` 信息的极简提示.
* [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) - 基于 lambda 的简单主题，带有 `git` 状态和 virtualenv 信息.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - 一个简单的 ZSH 主题，针对 `git` 的使用进行了优化.
* [lambda-pure](https://github.com/marszall87/lambda-pure) - 一个最小的 ZSH 主题，基于 Pure，添加了 NodeJS 版本.
* [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) - Lambda 和 Fishy 主题的组合，包括 `git` 状态装饰.
* [lambda-zen](https://github.com/seamile/lambda-zen) - 灵感来自 [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) 带有图形化的 `git` 状态装饰.
* [lambder](https://github.com/avillen/zsh-theme-lambder) - 包括 `git` 状态装饰，最适合深色终端主题.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - 针对暗终端进行了优化，具有适用于本地和远程系统的变体.
* [leafia](https://github.com/Ghostrick/leafia-prompt) - 显示 `git` 状态信息的 Leafy prezto 主题.
* [lean](https://github.com/miekg/lean) - 灵感来自 [pure](https://github.com/sindresorhus/pure) . 包括 `git` 状态和后台工作装饰.
* [lemon](https://github.com/carlosvitr/lemon_zsh)  - 许多美丽的颜色供您欣赏. 用心和耐心完成. 包括 `git` 状态和 ruby​​ 版本装饰.
* [leverage](https://github.com/gschnall/leverage) - Based on [minimal](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme), 使用颜色和额外的 `¬` 字符，以更好地区分命令行提示和输出.
* [lewis](https://github.com/lewisflude/oh-my-lewis)  - 黑色、白色和红色主题. 显示 `git` 状态信息.
* [lightbulb](https://github.com/lightbulb703/lightbulb-zsh-theme) - 包括内核、操作系统版本、正常运行时间和`git` 的装饰.
* [lighthaus](https://github.com/lighthaus-theme/zsh) - 赞美的提示 [Lighthaus](https://github.com/lighthaus-theme/lighthaus) 主题. 显示 `git` 信息、github/gitlab 徽标并在发生更改时显示更改.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) - 极简主义主题，最好在深色终端背景下使用.
* [lilith](https://github.com/aknackd/zsh-themes) - 修改 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) 和 [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [lime](https://github.com/yous/lime) - 简单且易于定制的 ZSH 主题.
* [limpide](https://github.com/shooteram/limpide) - 修改版本 [miloshadzic](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) 显示父目录和当前目录的主题.
* [linuxer](https://github.com/patrick330602/linuxer) - 受 Yaris Alex Gutierrez 的启发 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh)，Yad Smood 的 ys，以及 [Bureau](https://github.com/isqua/bureau) 主题.
* [liquidprompt](https://github.com/nojhan/liquidprompt)  - 功能齐全且精心设计的自适应提示，可在您需要时提供有用的信息. 它会在您需要时显示您需要什么. 当它发生变化时，您会注意到发生了什么变化，从而节省了时间和挫折.
* [lish](https://github.com/bashelled/lish)  - 休闲主题. 没有粗糙，只是光滑. 包括`git`、user@host、最后一个命令退出状态、当前目录、当前时间和根状态装饰器.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) - 挑剔的美洲驼使用的极简主义主题.
* [logico](https://github.com/logico/logico-zsh-theme)  - 有 `git` 装饰. 显示 vi 模式的远程状态和指示器.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - 基于 Sindre Sorhus 的纯主题的德克萨斯主题.
* [longsilvern](https://github.com/long263/longsilvern-zsh-theme) - 包括 `git` 和紧凑的 `pwd` 装饰.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme)  - lambda-mod 主题的变体. 有 `git` 装饰，需要与电力线兼容的终端字体.
* [luke](https://github.com/xueguangl23/luke_zsh_theme)  - 包括`git` 装饰. 基于 [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh 主题.
* [lukerandall-extended](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) - 扩展版 [lukerandall](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) 主题. 包括“git”状态和上次命令运行状态的装饰.
* [lunachar](https://github.com/r-mohammadi1/lunachar) - 极简主题，包括 `git` 状态装饰.
* [macos](https://github.com/alejandromume/macos-zsh-theme) - 包括 `git` 状态装饰.
* [mad](https://github.com/MartinWie/ohmyzsh-theme-mad) - 包括 `git` 状态装饰.
* [magicmace](https://github.com/zimfw/magicmace) - 灵感来自 xero 的 ZSH 提示和 [eriner's prompt](https://github.com/zimfw/eriner) . 包括活动 python `venv` 的状态代码、最后一个命令的退出状态、缩短的工作目录、`git` 状态装饰.
* [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN 的魔法主题.
* [maivana](https://github.com/nylo-andry/zsh-themes) - 包括 `kubectl` 上下文、`git` 状态装饰.
* [materialshell](https://github.com/carloscuesta/materialshell) - 一种 [material design](https://material.io/guidelines/style/color.html) 外壳的主题，在重要部分具有良好的对比度和颜色. 旨在轻松保护眼睛.
* [matrix](https://github.com/pot-code/matrix-zsh-theme) - 变体 [powerlevel9k](https://github.com/bhilburn/powerlevel9k) 风格看起来像黑客帝国电影三部曲中的东西. 包括 `git` 状态装饰.
* [matter](https://github.com/mrobillard/matter-zsh-theme) - 显示 `git` 状态、AWS 保管库角色、后台作业、最后一个命令的退出代码和主机名.
* [mau](https://github.com/vichargrave/mau)  - 带有猫扭曲的 ZSH 主题. 包括 `git` 状态装饰.
* [mbolis](https://github.com/mbolis/mbolis-zsh-theme) - 包括 `git` 装饰，如果 root 用户、活动作业和 [jenv](https://github.com/jenv/jenv) 一体化.
* [mdmini](https://github.com/MarioDena/MDmini) - 包括 `git` 和 `ssh` 状态装饰.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt)  - 包含键盘模式、所有权信息和其他上下文信息的最大化提示，其中 λ 作为提示字符. 需要 [hooks](https://github.com/willghatch/zsh-hooks) 插入.
* [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) - 包括 `git` 状态装饰，如果非零则显示最后一个命令的退出代码.
* [mexassi](https://github.com/Mexassi/mexassi-zsh-theme)  - 检查 `/sys/class/power_supply` 文件夹以确定系统是安装在笔记本电脑还是台式机上. 读取电池百分比 grepping acpi 命令并将其显示在提示中. 包括`git` 装饰.
* [mh-fzj](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) - 包括 `rvm` 和 `git` 状态装饰.
* [michaelpass](https://github.com/michaelpass/michaelpass.zsh-theme) - POSIX 友好的跨平台 [alanpeabody](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) mod 带有方便的时间戳和完整的 git/ruby 支持.
* [midin](https://github.com/xlshiz/midin) - 在黑暗的终端背景下运行良好，包括 `git` 状态装饰.
* [mike-was-here](https://github.com/leguim-repo/mike-was-here-theme/issues/1#issuecomment-763040593) - 极简主义，包括 `git` 状态装饰.
* [milight](https://github.com/frodoslaw/milight-zsh) - 带有 `git` 状态显示的最小 ZSH 提示，在深色终端背景下效果最佳.
* [min](https://github.com/andrepolischuk/min) - 简约的 ZSH 提示.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - 考虑到空间的 ZSH 主题.
* [mini-simple](https://github.com/ysl2/mini-simple-zsh-prompt)  - 极简主义者. 包括 `vcs` 状态装饰.
* [minima (Brolly0204)](https://github.com/Brolly0204/zsh-minima) - 包括 `git`、`node`、`golang`、`yarn`、`php`、`docker` 和 `python` 状态装饰.
* [minima (eduardnikolenko)](https://github.com/eduardnikolenko/minima)  - 一个最小的 ZSH 主题，带有 `git`、`docker`、`go`、`node`、`npm`、`python` 和其他指标. 对某些标记使用 unicode 字符.
* [minimal (5amu)](https://github.com/5amu/minimal-prompt)  - 最小提示，使用书呆子字体. 包括 `git` 和 `vpn` 状态装饰.
* [minimal (casalinovalerio)](https://github.com/casalinovalerio/minimal-prompt) - 最小提示，包括 `git` 和 vpn 状态装饰.
* [minimal (glsorre)](https://github.com/glsorre/minimal/) - 最小的异步 ZSH 主题优化用于 [Fira Code](https://github.com/tonsky/FiraCode) 字体和 [Solarized Light](https://ethanschoonover.com/solarized) 终端主题.
* [minimal (subnixr)](https://github.com/subnixr/minimal) - 最小但功能丰富的主题.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) - 黑暗终端的主题，在右侧提示中包含`git` 装饰.
* [minimal2](https://github.com/PatTheMav/minimal2)  - 最小且可扩展的 ZSH 主题. 分叉自 [subnixr's original](https://github.com/subnixr/minimal) 并适应 [Zimfw](https://github.com/zimfw/zimfw).
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) - 灵感来自 oh-my-zsh 的 kolo 主题.
* [mira](https://github.com/mbStavola/mira) - 一个修改 [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) 带有时间信息和简化的启动提示.
* [miramare](https://github.com/franbach/oh-my-deepin-miramare)  - 包括 `git` 状态装饰. 最适合搭配 [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
* [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs 的 ZSH 主题.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - 针对深色背景进行了优化.
* [mnml](https://github.com/mnml-theme/prompt) - 带有 `git` 状态装饰的最小主题.
* [mochi2](https://github.com/mochidaz/zsh-themes)  - 极简主义主题. 包括 `git` 和 `hg` 状态装饰.
* [mochi](https://github.com/mochidaz/zsh-themes)  - 简单的主题，旨在类似于 Rust 的主要功能. 包括 `git` 和 `hg` 状态装饰.
* [moderno](https://github.com/obrassard/moderno-zsh) - 一个简单而现代的 ZSH 主题，灵感来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme)  Oh-My-ZSH 的主题. 包括 `git` 状态装饰.
* [modesty](https://github.com/saravanabalagi/zsh-theme-modesty) - 一个干净、适度的 zsh 主题，带有 `condaenv`、`virtualenv` 和 `git` 状态装饰，整齐地右对齐显示.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874).
* [moonline](https://github.com/kagamilove0707/moonline.zsh) - 最小但易于扩展的提示.
* [moux](https://github.com/gagbo/moux) - 适用于深色终端背景，在“RPROMPT”中包含“git”装饰.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - 提供有关您所在存储库的有用信息（在您的提示中）.它目前适用于 [Git](https://git-scm.com/) 和 [Mercurial](https://www.mercurial-scm.org/)， 在下面 [ZSH](https://en.wikipedia.org/wiki/Zsh) 也 [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [multiline](https://github.com/jan-auer/zsh-multiline) - 基于电力线风格的主题 [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [muslim](https://github.com/nksoff/muslim) - 一个简单的最小 ZSH 提示主题.
* [musy](https://github.com/THaGKI9/musy-zsh-theme)  - 灵感来自缪斯主题. 包括 `git` 状态装饰.
* [my-hl2](https://github.com/liamm91/my-hl2)  - 包括 virtualenv、`git` 状态和目录装饰. 基于 omz  [half-life](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/half-life.zsh-theme) 主题.
* [myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia 的 myzsh 主题.
* [nanofish](https://github.com/tweekmonster/nanofish) - 为纳米技术主题添加鱼式目录提示.
* [narren](https://github.com/narrensingh/zsh-custom-theme-narren) - 包括 emojii `git` 状态装饰、退出状态 emoji 和节点版本.
* [nbrylevv](https://github.com/nbrylevv/nbrylevv-zsh-theme) - 带有文本“git”状态装饰的极简主题.
* [nctu](https://github.com/leovincentseles/nctu.zsh-theme)  - 轻量级主题，强调速度. 包括 `git` 状态装饰.
* [neewbie](https://github.com/neewbee/neewbee.zsh-theme)  - 带有 `git` 装饰的最小主题. 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell).
* [neon-potato](https://github.com/algosuna/neon-potato)  - 丰富多彩的简约主题. 包括`git` 装饰.
* [neon](https://github.com/sahariko/neon) - 一个漂亮而简约的 ZSH 主题，带有 `git` 装饰.
* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - 带有书呆子字体的 ZSH 提示主题.
* [nescalante](https://github.com/nescalante/zsh-theme) - 针对深色终端背景进行了优化，包括`git` 装饰.
* [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) - 包括`git` 装饰和`vi` 模式指示器.
* [newt](https://github.com/softmoth/zsh-prompt-newt)  - 胖而快速的主题——内外都很漂亮，风格片段做得对. 高度可定制，包括`git`、用户名、执行时间、目录、后台作业和编辑模式装饰.
* [newton](https://github.com/sebastienfilion/zsh.newton) - 包括 `git` 状态和外部 IP 地址装饰.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - 一个非常基本的主题，只有一个 macOS 自行车图标.
* [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - 多彩，显示 `git` 状态装饰.
* [nikitakot](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme)  - 小而简单的 oh-my-zsh 主题. 显示当前目录和后面的 2 个目录，`git` 和 `nodejs` 状态装饰.
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - 基于 af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - 一个简单的 oh-my-zsh 主题.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - 带有 `git` 状态装饰的极简 ZSH 主题.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) - oh-my-zsh 的节点主题，经过拆分以使其更易于与其他插件管理器一起使用.
* [nodeys (marszall87)](https://github.com/marszall87/nodeys-zsh-theme) - 基于 ys 主题，添加了 NodeJS 版本（来自 NVM 插件）.
* [nodeys (tianheg)](https://github.com/tianheg/config/blob/main/shell/nodeys.zsh-theme) - 基于 ys 主题，添加了 NodeJS 版本（来自 NVM 插件）.
* [noon](https://github.com/silky/noon.zsh-theme) - 有浅色和深色变体，显示 `git` 信息.
* [nord](https://github.com/TyWR/Nord-zsh) - 包括 `git` 状态装饰并显示活动的 conda 环境.
* [nothing](https://github.com/eendroroy/nothing) - 闪电般快速且非常简单，因为它几乎没有任何内容.
* [nox](https://github.com/kbrsh/nox) - 深色主题，显示当前工作目录和 git 状态.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme)  - 一个干净、无干扰且以“git”为重点的开发主题. 显示相对于 `git` 根目录（或 ~ 在 `git` 存储库之外时）的路径、自上次提交以来的时间、当前 SHA、分支和分支状态.
* [nunorc](https://github.com/nunorc/nunorc.zsh-theme)  - 极简主义主题，适用于深色背景. 包括 `git`、`mercurial` 和 `svn` satus 装饰.
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - prezto 和 oh-my-zsh 的简单主题.
* [nuts](https://github.com/rafaelsq/nuts.zsh-theme) - 极简主题，包括`git` 状态装饰和时间.
* [odin](https://github.com/tylerreckart/odin) - Odin 是一个 `git` 风格的 ZSH 主题.
* [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) - 带有`git` 装饰的多行主题.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - bash 和 ZSH 的自以为是的提示.
* [oh-my-posh](https://ohmyposh.dev/)  - 不是 ZSH 特定的，但非常好并且可以与 ZSH 一起使用. 允许您对所有 shell 中的提示使用相同的配置.
* [oh-my-via](https://github.com/badouralix/oh-my-via) - ZSH 的主题，主要分叉 VIA 服务器上使用的历史主题.
* [ohmypc](https://github.com/joselpadronc/OhMyPC)  - 适用于深色终端窗口. 包括`git` 装饰.
* [om](https://github.com/sirshikher/zsh-om) - 最小主题，适用于深色背景，包括`git` 状态装饰.
* [omuse](https://github.com/ouuan/omuse-zsh-theme) - 基于 Oh-My-ZSH  [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) . 具有“git”状态、时间、绝对密码、RAM 使用量、最后一个命令使用的时间和最后一个命令退出状态的装饰.
* [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) - 包括`git` 状态和virtualenv 信息.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - 简约和黑暗的 ZSH 主题.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme)  OZ0NO - 让我们呼吸干净的 ZSH.
* [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) - 一个主题 [powerlevel10k](https://github.com/romkatv/powerlevel10k) 提示强调简单性，同时仍能传达重要信息.
* [pad](https://github.com/eproxus/pad.zsh-theme) - 简洁多彩的 oh-my-zsh 主题.
* [page](https://github.com/SLIB53/page-zsh-theme)  - 支持 VCS 的简单主题. 提示显示当前工作目录的 1 级、分支和颜色编码的弯曲粗箭头.
* [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) - 允许显示主机信息，包括`git` 分支装饰.
* [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) - 在提示中显示带有图标的详细`git` 状态信息.
* [panda](https://github.com/davymai/oh-my-zsh-panda-theme)  - 包括 `git` 和 `root` 状态装饰. 最好在深色背景上.
* [papercolor](https://github.com/erikschreier/PaperColor-themes)  - ZSH、`vim` 和`tmux` 的配色方案. 包括 `git` 状态装饰.
* [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion)  - 包括`git` 状态装饰，以毫秒为单位的命令运行时间. 在 macOS 上需要 coreutils.
* [pastel](https://github.com/iboyperson/pastel) - 灵感来自于 ZSH 主题 [sugar-free](https://github.com/cbrock/sugar-free) . 包括`git` 装饰.
* [pentesters](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) - 修改版 [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) 渗透测试者的主题，包括渗透测试日志的日期、时间和 IP 地址.
* [persi](https://github.com/persiliao/persi-zsh-theme)  - 包括`git` 装饰. 适用于浅色和深色背景.
* [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) - 本着精神的最小主题 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 和纯壳主题.
* [phantomk](https://github.com/phantomk/phantomk.zsh-theme) - 丰富多彩的主题，包括 go 版本、node 版本和 `git` 状态.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - 一个干净简单的 ZSH 主题，灵感来自于 [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) 主题.
* [pi](https://github.com/tobyjamesthomas/pi) - 带有 `git` 状态装饰的简约主题.
* [plain-ui](https://github.com/purveshpatel511/plain-ui) - 极简主义，但包括 `git` 状态装饰.
* [plain](https://github.com/jimeh/plain.zsh-theme) - ZSH 的一个简单明了的主题，显示了基本的 `git` 信息.
* [planet](https://github.com/borb/planet-zsh) - 精简版 [steef](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) 从 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) - 简单、简洁的主题.
* [plantyhoe](https://github.com/totoroot/plantyhoe.zsh-theme)  - 基于对植物和苹果的热爱的极简主义主题. 包括 `git` 状态装饰.
* [platypus](https://github.com/fdv/platypus) - Platypus 是 Frédéric de Villamil 使用的 oh-my-zsh 的一个简单方便的主题.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) - 显示工作目录、上一个命令的返回状态和 `git` 当前分支.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM 的基本 oh-my-zsh 自定义主题.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - 带有`git` 状态、ruby 版本和项目路径的程序员主题.
* [powerbash](https://github.com/erikschreier/powerbash-zsh) - 适用于深色终端背景，包括 `git` 状态装饰.
* [powerless](https://github.com/martinrotter/powerless) - 受电力线启发的小而简单的纯 ZSH 提示.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - 快速重新实现 [powerlevel9k](https://github.com/bhilburn/powerlevel9k)  ZSH 主题. 可用作 powerlevel9k 的直接替代品，当给出相同的配置选项时，它将生成相同的提示，但速度更快.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k 是 ZSH 的主题，它使用 [Powerline Fonts](https://github.com/powerline/fonts) . 它可以与 vanilla ZSH 或 ZSH 框架一起使用，例如 [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen)， 和 [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - 附加组件 [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - 电力线的两线版本：一根用于信息，一根用于输入.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme)  - 另一种电力线主题. 很好的可配置性，但至少需要一个支持 256 色且具有电力线兼容终端字体的终端.
* [powerline (syui)](https://github.com/syui/powerline.zsh) - 一个“git”感知电力线主题.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - Based on [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
* [powerline-go](https://github.com/justjanne/powerline-go)  - 一个漂亮实用的低延迟提示，用 golang 编写. 包括 `git` 和 `hg` 状态修饰，上次运行命令的退出状态，当前 Python virtualenv，无论你是否在 [nix](https://nixos.org/) 壳，并且易于扩展.
* [powerline-hs](https://github.com/rdnetto/powerline-hs) - 一种 [Powerline](https://github.com/powerline/powerline) 用 Haskell 编写的克隆. 它比原始实现快得多，并使 shell 的响应速度明显更快.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - 在 Ruby 中创建，使用电力线字符模拟具有有用信息的药丸.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell)  - 漂亮实用的 Bash、ZSH、Fish 和 tcsh 提示生成器. 包括`git`、`svn`、`fossil` 和`hg` 装饰、Python virtualenv 信息和最后一个命令退出状态.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - 一种 [powerline](https://github.com/Lokaltog/vim-powerline) - 类似 Bash、ZSH 和 Fish 的提示. 显示关于 git/svn/hg/fossil 分支的重要细节，易于定制/扩展.
* [powerline-train](https://github.com/sherubthakur/powerline-train) - 电力线变体.
* [powerline](https://github.com/carlcarl/powerline-zsh) - 一种 [Powerline](https://github.com/Lokaltog/vim-powerline)- 类似提示，基于 [powerline-bash](https://github.com/milkbikis/powerline-bash) . 显示 virtualenv、`git` 状态信息和上次命令运行的退出代码.
* [powerzeesh](https://github.com/sevaho/Powerzeesh)  - 基于电力线的 ZSH 主题. 它旨在简化，仅在相关时显示信息，并针对速度和外观进行了优化. 灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) - Sublime Text、Terminal、iTerm 2 和 ZSH 的主题集合.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) - 针对黑暗终端主题优化的主题.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - oh-my-zsh 云提示的 Prezto 端口.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda 主题（用于 prezto）.
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline)  - 电力线价格. 显示 git 信息，RVM 版本.
* [probe](https://github.com/probe2k/probe_zsh) - 包括 `git` 状态装饰.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - 一个相当重量级的 ZSH 提示，基于流行的同名 `vim` 插件中的电力线字体，适用于深色背景.
* [prompt_j2](https://github.com/malinoskj2/prompt_j2) - 具有动态退出状态指示器，可以动态更改为两行以显示上下文.
* [ps1.py](https://github.com/jwodder/ps1.py) - 具有 `git` 状态、截断的目录、`chroot` 和 `virtualenv` 提示装饰.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - 易于定制，受 [spaceship](https://github.com/denysdovhan/spaceship-prompt).
* [pure-agnoster](https://github.com/yourfin/pure-agnoster)  - 纯粹和不可知论者的混搭. 具有 `git` 装饰，适用于深色和浅色终端背景.
* [pure](https://github.com/sindresorhus/pure)  - 漂亮、最小且快速的 ZSH 提示. 包括 `git` 状态装饰，如果最后一个命令失败，提示变为红色，在远程会话或容器中时的用户名和主机装饰，以及进程运行时的当前文件夹和命令.
* [purify (banminkyoz)](https://github.com/banminkyoz/purify) - 一个简单、快速和酷炫的提示.
* [purify (kyoz)](https://github.com/kyoz/purify)  - 干净而充满活力的主题，最适合深色背景. 包括 `git` 状态装饰.
* [purity](https://github.com/petermbenjamin/purity) - 灵感来自 robbyrussell 主题和 [pure](https://github.com/sindresorhus/pure) 迅速的.
* [purs](https://github.com/xcambar/purs) - 一个快速 [pure](https://github.com/sindresorhus/pure)- 灵感提示写在 [Rust](https://www.rust-lang.org/).
* [pustelto](https://github.com/Pustelto/shell_theme) - 色彩缤纷的主题灵感来自 [Spaceship](https://github.com/denysdovhan/spaceship-prompt) 主题，包括 `git` 装饰.
* [qi3ber2](https://github.com/nichus/qi3ber2)  - 一个黑暗的多行主题. 包括`git`、平均负载和最后一个命令装饰器的退出代码.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon)  - 针对深色背景进行了优化，包括`git` 信息. 主题库包括 iTerm 2 和终端颜色设置.
* [quewui](https://github.com/kauefontes/oh-my-quewui)  - 简单干净的主题针对黑暗的终端主题进​​行了优化. 包括当前时间、用户、目录和 `git` 状态的状态装饰.
* [r3nic1e](https://github.com/r3nic1e/r3nic1e) - [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 具有电池状态、`git/hg` 状态、时间、kubernetes 上下文和命名空间、最后一个命令的非零退出代码和日期装饰的变体. 需要电力线字体.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - 基于 af-magic 和 posh-git.
* [radium](https://github.com/dimitardimitrov/radium) - 专为暗终端设计，（最适合与 [Solarized](https://github.com/altercation/solarized) iTerm 2 主题）（prezto）.
* [rafiki](https://github.com/akabiru/rafiki-zsh) - 将表情符号添加到您的 ZSH 终端.
* [ramiel](https://github.com/aknackd/zsh-themes) - 叉子 [node](https://github.com/skuridin/oh-my-zsh-node-theme).
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - Based on [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) 和“robbyrussell”主题.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - 随机表情符号.
* [raspberrysh](https://github.com/MaxMalinowski/raspberrysh) - 包括`git`、python、时间、当前主机和路径装饰.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) - 简单而多彩的主题，带有 `git` 状态装饰.
* [raz](https://github.com/razman786/ohmyzsh-theme-raz) - 最小提示，包括 `git` 状态装饰.
* [rb](https://github.com/rberenguel/rb-zsh-theme) - 基于电力线风格的 ZSH 主题 [Agnoster](https://gist.github.com/agnoster/3712874) ，针对`git`和solarized终端进行了优化. 需要与电力线兼容的字体.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - 针对日光化终端配色方案进行了优化，包括`git` 状态装饰.
* [redline](https://github.com/DrissTM/redline.zsh-theme)  - 极简主义主题. 包括 `git` 状态、时间、用户.
* [reggae](https://github.com/nmercado1986/zsh-reggae-theme) - 使用颜色编码的状态装饰将大量信息压缩到提示中.
* [rei](https://github.com/arturoalviar/rei-zsh-theme) - 一个简单的主题，第一个字符是零（rei），数字 0.包括 `git` 状态装饰.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), 优化 [solarized](https://github.com/altercation/solarized) 终端主题.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - Prezto ZSH 主题基于 Sorin，使用表情符号跟踪 GIT 上下文.
* [rho](https://github.com/andrejreznik/rho-zsh-theme) - 极简主义主题.
* [river](https://github.com/revir/river-zsh-config) - 带有 `git` 信息的深色主题.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - 基于来自 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题和项目 [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - 用输出装饰 `robbyrussell` 主题以指示 **WIP** 提交.
* [robbyrussell-fullpath](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) - 原本 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 提示中有完整路径.
* [rocket](https://github.com/Alexandresl/rocket-zsh-theme) - 极简主题，包括`git`和`hg`状态装饰.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - 一个黑暗的主题.
* [roundy](https://github.com/nullxception/roundy)  - 快速，可爱和圆润的主题. 包括`git` 装饰. 需要书呆子字体和支持 unicode 的终端应用程序.
* [roz](https://github.com/rozNum/roz-zsh-theme)  - 极简主义者. 包括 `git` 状态装饰，最好在较暗的背景下使用.
* [rs](https://github.com/rogeliosamuel621/rs-zsh-theme)  - 包括`git` 装饰. 需要支持 Unicode 的终端.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) - 针对深色背景进行了优化.
* [rummik](https://github.com/rummik/zsh-theme)  - @rummik 的主题. 支持 [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), 以及提示中的 `git` 状态信息.
* [russtone](https://github.com/russtone/prompt-russtone) - 灵感来自 [pure](https://github.com/sindresorhus/pure) 和 [sorin](https://github.com/sorin-ionescu/prezto) . 包括 `git` 状态装饰.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - 丰富多彩的主题，包括`git` 装饰和当前目录.
* [rzh](https://github.com/patwhatev/rzh) - 带有由表情符号指示的 git 状态的主题.
* [s1ck94](https://github.com/zimfw/s1ck94)  - S1cK94 的（第一个已弃用，现已灭绝）最小提示的分支. 显示用户是否为 root、后台作业状态、vi 模式、最后一个命令的退出状态和 `git` 状态装饰.
* [s7c](https://github.com/Samega7Cattac/s7c.zsh-theme)  - 适用于深色背景. 包括 `git` 状态装饰.
* [samshell](https://github.com/samuelb/samshell) - 极简的 zsh 主题，带有 `git`、kubernetes 和 python virtualenv 装饰.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - 包括 `git` 状态装饰，适用于深色终端背景.
* [saturn](https://github.com/gantoreno/saturn-prompt) - 为那些喜欢空间并希望在他们的终端上拥有一点空间的人提供柔和简约的提示，具有酷炫的表情符号和高度可定制的提示元素（例如图标、颜色、时间格式等）.
* [shirnschall](https://github.com/shirnschall/shirnschall-zsh-theme) - 包括`git` 状态和`user@hostname` 装饰.
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) - 显示 `git` 状态装饰、user@host 信息、上一个命令的退出状态以及是否以 root 身份运行.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - 当使用`:sh` 命令时显示`vim` 是否在后台运行.
* [sdkman](https://github.com/matthieusb/zsh-sdkman) - 添加选项卡完成 [sdkman](https://sdkman.io/).
* [seashell](https://github.com/jottenlips/seasonal-zshthemes)  - 带有海洋风格表情符号装饰的简约主题. 包括 `git` 状态装饰.
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - 这个主题使用了很多特殊的unicode字符，看起来很花哨，但是如果没有很好的字体支持，可能会导致一些问题.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - 受节食者主题启发，使用颜色编码来提供信息.
* [senpai](https://github.com/hiroru/senpai-zsh)  - Devops 的干净提示主题. 包括 `git` 状态信息、kubernetes 上下文、AWS 配置文件、GCP 项目和 Azure 活动云.
* [seppuku](https://github.com/Helianthella/seppuku) - 灵感来自于干净和最小的主题 [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme).
* [sepshell](https://github.com/sepehr/sepshell) - 基于旧的丢失的 taybalt 主题的干净和最小的 ZSH 主题，带有`git` 平分/合并/重新定位模式和可配置的提示符号.
* [serious](https://github.com/oliversandli/serious-zsh-theme) - 包括命令退出状态和`git` 状态装饰.
* [seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - 一个简单的 omz 兼容主题，带有相应的 iTerm 2 配色方案.
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - 精益提示的演变，它本身就是对纯提示的重写.
* [shadow](https://github.com/agentshadow/shadow-zsh-theme) - 包括`git` 状态、目录、主机名、用户名和时间装饰.
* [shayan](https://github.com/shayanh/shayan-zsh-theme) - 带有 `git` 状态装饰的简单主题.
* [shellder](https://github.com/simnalamburt/shellder)  - 带有 git 分支显示的最小主题. 需要与电力线兼容的字体.
* [shichi](https://github.com/arturoalviar/shichi-zsh-theme)  - 一个简单的主题，第一个字符是七（七/娜娜），数字7.主色是红色，带黄色调. 包括 `git` 状态装饰.
* [shini](https://github.com/bashelled/shini)  - 一个很小的主题，只是大声喊出来. 包括目录、用户名、主机名、时间和 `git` 装饰.
* [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) - 分叉自 [sixlive](https://github.com/sixlive/sixlive-zsh-theme) . 有 `git` 装饰.
* [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) - 基于 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 主题. 包括 `git` 和 `hg` 状态装饰.
* [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) - 包括`git` 装饰.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - 显示当前目录和 git 信息的简单主题.
* [shtr0m](https://github.com/kyle-pollock/shtr0m) - 包括 `git` 状态装饰.
* [siegerts](https://github.com/siegerts/zsh-theme) - 在正确的提示中包含 `git` 状态装饰.
* [silver](https://github.com/reujab/silver) - 一个跨外壳可定制的类似电力线的提示，深受启发 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) . 更快的 Rust 端口 [bronze](https://github.com/reujab/bronze) . 需要 [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) . 非常可配置，包括 `git` 状态装饰.
* [simpalt](https://github.com/m-lima/simpalt) - 基于 ZSH 的信息丰富的小足迹主题 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [simple (pavdmyt)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - 基于极简主义的主题 [robbyrussel](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) 它在 iTerm 的窗口标题栏中嵌入了 `git` 状态信息，而不是在提示中使用空格.
* [simple (savecoders)](https://github.com/Savecoders/simpleTheme-zsh-theme) - 简单简约的主题，带有`git`、`username` 和执行状态装饰.
* [simple (yhiraki)](https://github.com/yhiraki/zsh-simple-prompt) - 最少的提示，不需要特殊字体.
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - 受电力线启发的简单主题，带有 `git` 装饰.
* [simple-git](https://github.com/BazaJayGee66/simple-git-theme) - 极简主义主题灵感来自 [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) . 包括`git` 装饰.
* [simple-yet-beautiful](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme)  - 极简主义主题. 包括 `git` 状态和 `user@host` 提示装饰.
* [simplezsh](https://github.com/fr0zn/simplezsh) - 带有 `git` 信息显示的最小主题.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme)  - k-kinzal 的 sinon 主题. 包括 `git` 状态装饰.
* [sit](https://github.com/svensen/sit.zsh-theme) - 带有`git`、命令退出状态和路径装饰的极简主题.
* [sixlive](https://github.com/sixlive/sixlive-zsh-theme)  - 这个主题有一个独特的目录列表. 当在一个 `git` 项目中时，目录显示的范围是当前存储库根目录.
* [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9 的 ZSH 主题.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Atom、Prism 和 ZSH 的主题系列灵感来自 He-Man 和宇宙大师的 Skeletor.
* [skill](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - 针对暗终端进行了优化，显示`git` 状态装饰.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH 主题灵感来自 [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) 和 [odin](https://github.com/tylerreckart/odin).
* [slick](https://github.com/nbari/slick) - Inspired by the [pure](https://github.com/sindresorhus/pure), [purs](https://github.com/xcambar/purs) 和 [zsh-efgit-prompt](https://github.com/ericfreese/zsh-efgit-prompt) . 需要 `cargo` 进行安装.
* [slimline](https://github.com/mengelbrecht/slimline)  - 最小、快速和优雅的 ZSH 提示. 在正确的时间显示正确的信息.
* [sm](https://github.com/blyndusk/sm-theme)  **Simplist** 和 **Minimalist** 主题，适合您 ** 最喜欢的** 终端. 包括 `git` 状态装饰.
* [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) - 的变体 [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) 主题在 [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - 带有快乐和悲伤面孔的提示.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme)  - 受老式爱好启发的简约 ZSH 主题. 没有冗长的噱头，没有表情符号，没有烦躁的旋转器，也没有其他视觉噪音. 有明暗两种模式.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - 太阳能电力线变体.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) - ZSH 的 Solarized 电力线风格主题.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) - 修复 robbyrussell 的 oh-my-zsh 主题的颜色 [solarized](https://github.com/altercation/solarized) 终端.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) - 带有 `git`、`nvm`、rvm/rbenv/chruby、python、`ssh` 和其他有用状态指示器的主题.
* [spowerline](https://mbauhardt.github.io/spowerline/) - 用 Scala 编写，灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), [tmux](https://tmux.github.io) powerline、vim powerline 和 vim 状态插件.
* [squanchy](https://github.com/gabrielecanepa/zsh-custom/tree/master/themes)  - 极简主义主题. 包括 `git`、`node` 和 `rbenv` 状态装饰.
* [staples](https://github.com/dersam/staples) - 基于局，如果通过 SSH 连接，则显示 user@host.
* [starboy](https://github.com/prdpx7/Starboy) - 一个简单的 ZSH 主题.
* [starship](https://github.com/starship/starship) - 最小，快速，高度可定制.
* [statusline](https://github.com/el1t/statusline) - 响应式 ZSH 主题，可在您需要时提供信息段.
* [steef (danihodovic)](https://github.com/danihodovic/steeef)  - ZSH steeef 主题作为独立存储库. 此 repo 背后的目的是避免在使用 steeef 主题时依赖 oh-my-zsh.  Antibody 等 ZSH 插件管理器可以使用主题，而无需使用 oh-my-zsh.
* [steef (zimfw)](https://github.com/zimfw/steeef) - 可定制的版本 [steeef's](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) 主题.
* [stellachar](https://github.com/r-mohammadi1/stellachar) - 最小，粉彩.
* [sublime](https://github.com/pjmp/sublime) - 带有 `git` 状态装饰的崇高、干净、简约的 ZSH 主题.
* [sugar-free](https://github.com/cbrock/sugar-free) - 基于 [Pure](https://github.com/sindresorhus/pure) 和 [C和y](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/c和y.zsh-theme) 主题.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme)  - 包括 `git` 状态装饰. 在深色终端背景上效果更好.
* [sulfurium](https://github.com/Sulfurium/zsh-theme) - suliumOS 的官方 ZSH 主题.
* [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) - 相似 [sunrise](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) 但包括活动的 Ruby 版本.
* [superkolo](https://github.com/Minipada/superkolo) - 将日期和退货状态添加到 [kolo](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) 主题.
* [susi](https://github.com/carcruz/susi-zsh-iterm) - 包括 `git` 状态装饰和随附的 iTerm2 配色方案.
* [sy](https://github.com/ttttmr/sy-zsh-theme) - Based on [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), 包括 `git` 状态装饰.
* [t2er](https://github.com/t2er/t2er-zsh-theme) - 带有`git` 装饰的极简主义主题.
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - 针对深色背景优化的最小 ZSH 主题.
* [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) - 包括 `git` 状态装饰和 conda/virtualenv 状态.
* [termux](https://github.com/rooted-cyber/Termux-zsh-theme) - 极简主义主题.
* [termuxer](https://github.com/patrick330602/termuxer) - 主题灵感来自 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) 和 linuxer.
* [the-time-lord](https://github.com/jhwhite/the-time-lord) - 基于的主题 [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - 带有“git”状态的彩色主题.
* [theta-async](https://github.com/jesec/zsh_theme_theta-async) - 异步版本 [theta](https://github.com/eendroroy/theta) . 包括 vcs 状态信息.
* [theta](https://github.com/eendroroy/theta)  - 包括 `git` 和 `hg` 状态装饰. 还有java、python、ruby、node、go和elixir版本信息.
* [theto](https://github.com/victorgama/theto-zsh-theme) - 需要 [Nerd Fonts](https://nerdfonts.com/), 有 `git` 状态装饰.
* [thetraveler](https://github.com/bassopenguin/thetraveler) - 受到 theunraveler 的启发，使用符号来显示 `git` 状态.
* [thnikk](https://github.com/thnikk/zsh-theme-thnikk) - 最小版本 [spaceship](https://github.com/denysdovhan/spaceship-prompt) 主题.
* [thyme (chenhao-ye)](https://github.com/chenhao-ye/thyme) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme)， 和 [bullet-train](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme).
* [thyme (kawamurakazushi)](https://github.com/kawamurakazushi/thyme) - 带有 `git` 状态装饰的简单主题.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh)  - 包括`git`信息； 最好在深色背景上.
* [tq](https://github.com/kitian616/tq-zsh-theme) - 显示 `git` 状态、时间，需要 Powerline 字体.
* [traffic](https://github.com/fcce/traffic-zsh-theme) - ZSH 的黑暗主题.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) - ZSH 的黑暗主题.
* [trinity](https://github.com/de-luca/Trinity) - 基于的简单主题 [geometry](https://github.com/geometry-zsh/geometry) . 包括`git` 装饰.
* [tsotra](https://github.com/nylo-andry/zsh-themes) - 极简主题，包括`git` 状态装饰、k8s 上下文和`rvm` 状态.
* [turs](https://github.com/eikendev/turs) - 快速，最小 [Purs](https://github.com/xcambar/purs)-灵感提示.
* [tvline](https://github.com/thvitt/tvline) - 源自 [agnoster](https://gist.github.com/agnoster/3712874) 主题，添加电力线字体增强功能.
* [type0](https://github.com/MikereDD/type0_zsh-theme) - 灵感来自 [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) 亚里斯古铁雷斯. 包括`git` 装饰.
* [typewritten](https://github.com/reobin/typewritten)  - 最小且信息丰富的主题，为重要内容留出空间. 异步`git` 装饰更新以提高速度.
* [ubunly](https://github.com/alejandromume/ubunly-zsh-theme)  - 模仿 Kali Linux 控制台. 注意 - 这个主题还重新绑定了很多键并设置了一堆主题应该单独保留的 ZSH 选项.
* [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) - 模仿默认的 Debian/Ubuntu `bash` 提示.
* [ubuntu-with-vitamins](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) - 模仿默认的 Ubuntu 提示，但带有 `git` 装饰.
* [ubuntu](https://github.com/janstuemmel/zsh-ubuntu-theme) - 最小主题，包括`git` 状态装饰.
* [ultimate](https://github.com/b4b4r07/ultimate) - 极简主义主题，带有 `git` 指示器、vim 模式指示器和缩短的路径.
* [unicorn](https://github.com/juliuscaesar/unicorn) - Inspired by the [Wild Cherry](https://github.com/mashaal/wild-cherry) 主题. 有表情符号`git` 状态装饰.
* [unit-1](https://github.com/nerdbude/Unit-1) - 带有 ITWTB 颜色的极简主题.
* [vanan](https://github.com/avano/vanan-zsh-theme) - 极简主义主题，带有用于黑暗终端的 `git` 信息.
* [vercel](https://github.com/vercel/zsh-theme) - 带有 `git` 状态装饰的简约主题.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - 修改自 themes/mgutz.zsh-theme.Looks 与 a 一起使用时看起来很棒 [Solarized](https://github.com/altercation/solarized) 配色方案.
* [vitesse](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) - 受 VS Code 的启发 [Vitesse](https://github.com/antfu/vscode-theme-vitesse) 主题. 包括 `git` 状态装饰.
* [vulcan](https://github.com/Bruceboy/vulcan-zsh-theme)  - 最小的主题让人想起默认的`bash` 主题. 包括`git` 装饰.
* [wade](https://github.com/wadehammes/wade.zsh-theme) - 流行的 ZSH 主题的混搭 [Agnoster](https://gist.github.com/agnoster/3712874) 和 [Fishy](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme)，进行一些视觉调整.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) - 基于0532主题.
* [whale](https://github.com/whalesea520/whale-zsh-theme) - 快速重新实现鲸鱼主题.
* [whales](https://github.com/lbergelson/zsh_whales_theme) - 包括`git` 状态、java 版本、上一个命令返回状态和目录的装饰器.
* [wild-cherry](https://github.com/mashaal/wild-cherry) - ZSH、iTerm 2、Sublime、Atom 和 Mou 的童话主题主题.
* [work-line](https://github.com/afnizarnur/work-line) - 带有漂亮表情符号的主题.
* [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) - 包括 `git` 状态装饰、工作目录、上一个命令的退出状态和当前的 `virtualenv`.
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme)  - 旨在在您需要时向您展示所需信息的主题.  `wynwyn` 从默认主题 `avit` 和优秀 [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xlk-simple](https://github.com/xuelingkang/xlk-simple-zsh-theme) - 带有 `git` 装饰的简单主题.
* [xm](https://github.com/Shiaoming/xm)  - 黑暗终端的主题. 有 `git` 装饰.
* [xor](https://github.com/xor3n/xor-zsh-theme) - 自我描述为简约和“功能差”，包括“git”装饰.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - 基于 Jreese 主题插件的 oh-my-zsh shell 主题.
* [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme)  - 快速、简单和精简的主题. 最适合搭配 [tmux](https://github.com/tmux/tmux/wiki) 和 [vim-airline](https://github.com/vim-airline/vim-airline).
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - 显示当前 git commit 的缩短哈希和消息.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme)  - 带有行分隔提示的最小主题. 基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 主题.
* [yazpt](https://github.com/jakshin/yazpt) - 一个干净、快速、美观的 ZSH 提示主题，精心整合了 Git/Subversion/TFVC 状态信息，与 Oh My Zsh 等流行插件管理器集成，并且易于定制和扩展.
* [yechen](https://github.com/liyechen/yechen.zsh-theme) - 带有 `git` 状态装饰的简约主题.
* [yeet](https://github.com/jeetelongname/Yeet-theme) - 带有 `git` 状态装饰的极简提示.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - 修改自 [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) 主题并针对深色背景进行了优化.
* [ys (cristiancavalli)](https://github.com/cristiancavalli/ys-zsh-custom-theme) - 干净、简单、兼容且有意义的主题，适用于深色背景.
* [ys (tinyRatP)](https://github.com/tinyRatP/ys) - 变体 [ys](https://gist.github.com/ysmood/6110461).
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - [ys](http://ysmood.org/my-ys-terminal-theme/) 支持使用大型集群的批处理提交系统的变体. 支持 Slurm、LSF/IBM Spectrum LSF 和 PBS.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - Simple ZSH theme with `git` status information.
* [ysr](https://github.com/raykle/ysr-zsh-theme) - Based on [ys](http://blog.ysmood.org/my-ys-terminal-theme/) . 包括 `git` 状态装饰.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - 黑暗优化的 ZSH 主题.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - 包括 conda 和 venv 状态.
* [yz50](https://github.com/lacanlale/yz50-zsh) - 多彩，基于 [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) 和 [crunch](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) 主题. 包括 `git` 状态装饰.
* [z4rr3t](https://github.com/inimicus/z4rr3t) - 基于 sindresorhus&#39; [pure](https://github.com/sindresorhus/pure) 主题.
* [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme) 塞尔达主题. 包括 `git` 状态装饰.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - oh-my-zsh 的定制版 [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) 有善变的支持和其他变化.
* [zemoji](https://github.com/therzka/zemoji) - Based on [wild-cherry](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ https://github.com/mashaal/wild-cherry/tree/master/zsh) . 包括退出状态、`virtualenv`、`nvm`、`rvm` 和`git` 状态装饰.
* [zero](https://github.com/arlimus/zero.zsh)  - Zero 的主题和插件. 具有浅色和深色终端背景的变体.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - 在深色背景上效果最佳，包括 `git` 状态装饰.
* [zerocake](https://github.com/ZeroPoke/ZeroCake.zsh-theme) - 在黑暗的场地上效果更好.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) - 显示用户名、`git` 状态信息、机器名称、当前工作目录和上一条命令的成功/失败状态.
* [zinc](https://gitlab.com/robobenklein/zinc) - 极速、纯 ZSH、混合异步电力线提示，易于扩展且极易配置.
* [zlambda](https://github.com/wdhg/zlambda) - 极简主义，包括没有特殊字体要求的`git` 装饰.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) - oh-my-zsh 的修改版 [maran](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) 主题.
* [zsh1999](https://github.com/DTan13/zsh1999) - 包括网络连接、电池和`git` 状态装饰.
* [zsh2000](https://github.com/inspectahstack/zsh2000) - 电力线外观 ZSH 主题，包括 `rvm` 提示、`git` 状态和分支、当前时间、用户、主机名、密码、退出状态、是否以 root 身份运行和后台作业状态.
* [zsh313](https://github.com/amirali313/zsh313-theme) - 带有 `git` 状态装饰的最小主题.
* [zshcomrade](https://github.com/landongn/zshcomrade) - ZSH 主题，同志！
* [zshpower](https://github.com/snakypy/zshpower)  - 针对 python 开发人员进行了优化. 包括 `git` 和 `pyenv` 状态装饰、用户名和主机. 尝试安装其他插件和字体，因此请在安装前阅读其说明.
* [zshred](https://github.com/redxtech/zshred) - 显示当前目录、`git` 装饰、上一个命令的退出状态和时间.
* [zwsh](https://github.com/naens/zwsh) - ZSH 的 Zpm3/Wordstar 模式/主题.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) - 相似 [Agnoster](https://github.com/agnoster/agnoster-zsh-theme)，旨在根据上下文公开信息，具有电力线美学.

## Fonts

这里列出的一些主题需要与电力线兼容的字体，这里有一些：

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - 一系列字体，包括一些漂亮的等宽图标.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - 一个漂亮的等宽字体，用 Font-Awesome、Octoicons 和 Powerline-Glyphs 修补.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - 另一种与电力线兼容的字体.
* [Hack](https://sourcefoundry.org/hack/) - 另一种专为源代码设计的电力线兼容字体.
* [Input Mono](http://input.fontbureau.com/)  - 专为代码设计的一系列字体. 它提供等宽和比例字体，并包括电力线字形.
* [Iosevka](https://github.com/be5invis/Iosevka)  - 编码员的字体，由代码构建. 高度可定制.
* [Monoid](https://larsenwork.com/monoid/) - Monoid 是可定制和优化的，即使在低分辨率显示器上，也可以在 15px 行高处以类似位图的清晰度进行编码.
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts)  - 收集了 20 多种修补字体（超过 2,000 种变体）和用于 Powerline、Font Awesome、Octicons、Devicons 和 Vim Devicons 的 FontForge 字体修补程序 Python 脚本. 包括：Droid Sans、Meslo、源代码、AnonymousPro、Hack、ProFont、Inconsolata 等等.
* [Powerline patched font collection](https://github.com/powerline/fonts) - 十几种字体的集合，经过修补以包含电力线字形.
* [Terminus](http://files.ax86.net/terminus-ttf/) - 包含电力线字形的 Terminus 的 TTF 版本.

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

大多数这些插件可以通过将 `antigen bundle githubuser/reponame` 添加到您的 .zshrc 文件来安装.  Antigen 将在您下次启动 `zsh` 时自动为您处理克隆插件. 您还可以使用 `antigen bundle githubuser/reponame` 将插件添加到正在运行的 ZSH 中，以便在将其添加到您的 `.zshrc` 之前进行测试.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1.克隆新插件到`.zsh.local/modules`
2.在`.zshrc`中加载插件模块
3. 打开一个新的 ZSH 终端窗口或选项卡

### [Oh-My-Zsh](http://ohmyz.sh/)

1.`cd ~/.oh-my-zsh/custom/plugins`
2.`git clone repo`
3. 将 repo 添加到您的插件列表中

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. 将插件克隆到您的 prezto 模块目录中
2. 将插件添加到你的 `.zpreztorc` 文件中
3.打开一个新的终端窗口或标签

### [Zgen](https://github.com/tarjoilija/zgen)

 Zgen 没有得到积极维护. 考虑切换到 [Zgenom](https://github.com/jandamm/zgenom) 叉子，也就是.

大多数这些插件都可以通过在您正在执行其他 `zgen load` 调用的同一函数中将 `zgen load githubuser/reponame` 添加到您的 .zshrc 文件中来安装.

当您执行 `zgen save` 时，Zgen 将自动为您克隆插件存储库.

### [Zgenom](https://github.com/jandamm/zgenom)

大多数这些插件都可以通过将“zgenom load githubuser/reponame”添加到您正在执行其他“zgenom load”调用的同一函数中的 .zshrc 文件来安装.

当您执行 `zgenom save` 时，Zgenom 将自动为您克隆插件存储库.

### [zplug](https://github.com/zplug/zplug)

大多数这些插件可以通过将 `zplug &quot;githubuser/reponame&quot;` 添加到你的 `.zshrc` 文件来安装.

### [zpm](https://github.com/zpm-zsh/zpm)

大多数这些插件可以通过将 `zpm load &quot;githubuser/reponame&quot;` 添加到你的 `.zshrc` 文件来安装.

## Writing New Plugins

我已经记录了一些关于编写新插件的建议 [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

## Other Resources

### ZSH Tools

* [ShellSpec](https://github.com/shellspec/shellspec) - 用于 dash、bash、ksh、ZSH 和所有 POSIX shell 的全功能 BDD 单元测试框架.
* [zshdb](https://github.com/rocky/zshdb) - ZSH 调试器
* [zunit](https://github.com/zunit-zsh/zunit) - 强大的 ZSH 单元测试框架

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - 精心挑选的出色工具、资源和工作流程提示列表，打造出色的开发环境
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - 精选的开源系统管理员资源列表
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - CLI 爱好者的精选列表.

在以下位置找到其他有用的 awesome-* 列表 [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) 和 [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) 缺一不可.
